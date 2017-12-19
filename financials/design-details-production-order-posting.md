---
title: Design Details - Production Order Posting | Microsoft Docs
description: Similar to assembly order posting, the consumed components and the used machine time are converted and output as the produced item when the production order is finished.
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 2c13559bb3dc44cdb61697f5135c5b931e34d2a8
ms.openlocfilehash: bd25ed0204ee0e96e258974dc03d29aea44b67e6
ms.contentlocale: en-au
ms.lasthandoff: 09/22/2017

---
# <a name="design-details-production-order-posting"></a><span data-ttu-id="2dac2-103">Design Details: Production Order Posting</span><span class="sxs-lookup"><span data-stu-id="2dac2-103">Design Details: Production Order Posting</span></span>
<span data-ttu-id="2dac2-104">Similar to assembly order posting, the consumed components and the used machine time are converted and output as the produced item when the production order is finished.</span><span class="sxs-lookup"><span data-stu-id="2dac2-104">Similar to assembly order posting, the consumed components and the used machine time are converted and output as the produced item when the production order is finished.</span></span> <span data-ttu-id="2dac2-105">For more information, see [Design Details: Assembly Order Posting](design-details-assembly-order-posting.md).</span><span class="sxs-lookup"><span data-stu-id="2dac2-105">For more information, see [Design Details: Assembly Order Posting](design-details-assembly-order-posting.md).</span></span> <span data-ttu-id="2dac2-106">However, the cost flow for assembly orders is less complex, especially because assembly cost posting only occurs once and therefore does not generate work-in-process inventory.</span><span class="sxs-lookup"><span data-stu-id="2dac2-106">However, the cost flow for assembly orders is less complex, especially because assembly cost posting only occurs once and therefore does not generate work-in-process inventory.</span></span>


<span data-ttu-id="2dac2-107">Transactions that occur during the manufacturing process can be tracked through the following stages:</span><span class="sxs-lookup"><span data-stu-id="2dac2-107">Transactions that occur during the manufacturing process can be tracked through the following stages:</span></span>  

1.  <span data-ttu-id="2dac2-108">Purchase of materials and other manufacturing inputs.</span><span class="sxs-lookup"><span data-stu-id="2dac2-108">Purchase of materials and other manufacturing inputs.</span></span>  
2.  <span data-ttu-id="2dac2-109">Conversion into work in process.</span><span class="sxs-lookup"><span data-stu-id="2dac2-109">Conversion into work in process.</span></span>  
3.  <span data-ttu-id="2dac2-110">Conversion into finished goods inventory.</span><span class="sxs-lookup"><span data-stu-id="2dac2-110">Conversion into finished goods inventory.</span></span>  
4.  <span data-ttu-id="2dac2-111">Sale of finished goods.</span><span class="sxs-lookup"><span data-stu-id="2dac2-111">Sale of finished goods.</span></span>  

<span data-ttu-id="2dac2-112">Therefore, apart from regular inventory accounts, a manufacturing company must establish three separate inventory accounts to record transactions at various stages of production.</span><span class="sxs-lookup"><span data-stu-id="2dac2-112">Therefore, apart from regular inventory accounts, a manufacturing company must establish three separate inventory accounts to record transactions at various stages of production.</span></span>  

|<span data-ttu-id="2dac2-113">Inventory Account</span><span class="sxs-lookup"><span data-stu-id="2dac2-113">Inventory Account</span></span>|<span data-ttu-id="2dac2-114">Description</span><span class="sxs-lookup"><span data-stu-id="2dac2-114">Description</span></span>|  
|-----------------------|---------------------------------------|  
|<span data-ttu-id="2dac2-115">**Raw Materials account**</span><span class="sxs-lookup"><span data-stu-id="2dac2-115">**Raw Materials account**</span></span>|<span data-ttu-id="2dac2-116">Includes the cost of raw materials that are purchased but not yet transferred to production.</span><span class="sxs-lookup"><span data-stu-id="2dac2-116">Includes the cost of raw materials that are purchased but not yet transferred to production.</span></span> <span data-ttu-id="2dac2-117">The balance in the Raw Materials account indicates the cost of raw materials on hand.</span><span class="sxs-lookup"><span data-stu-id="2dac2-117">The balance in the Raw Materials account indicates the cost of raw materials on hand.</span></span><br /><br /> <span data-ttu-id="2dac2-118">When raw materials move into the production department, the cost of the materials is transferred from the Raw Materials account to the WIP account.</span><span class="sxs-lookup"><span data-stu-id="2dac2-118">When raw materials move into the production department, the cost of the materials is transferred from the Raw Materials account to the WIP account.</span></span>|  
|<span data-ttu-id="2dac2-119">**Work in Process (WIP) account**</span><span class="sxs-lookup"><span data-stu-id="2dac2-119">**Work in Process (WIP) account**</span></span>|<span data-ttu-id="2dac2-120">Accumulates the costs that are incurred during production in the accounting period.</span><span class="sxs-lookup"><span data-stu-id="2dac2-120">Accumulates the costs that are incurred during production in the accounting period.</span></span> <span data-ttu-id="2dac2-121">The WIP account is debited for the cost of raw materials that are transferred from the raw materials warehouse, the cost of direct labour performed, and the manufacturing overhead costs that are incurred.</span><span class="sxs-lookup"><span data-stu-id="2dac2-121">The WIP account is debited for the cost of raw materials that are transferred from the raw materials warehouse, the cost of direct labor performed, and the manufacturing overhead costs that are incurred.</span></span><br /><br /> <span data-ttu-id="2dac2-122">The WIP account is credited for the total manufacturing cost of units that are completed in the factory and transferred to the finished goods warehouse.</span><span class="sxs-lookup"><span data-stu-id="2dac2-122">The WIP account is credited for the total manufacturing cost of units that are completed in the factory and transferred to the finished goods warehouse.</span></span>|  
|<span data-ttu-id="2dac2-123">**Finished Goods account**</span><span class="sxs-lookup"><span data-stu-id="2dac2-123">**Finished Goods account**</span></span>|<span data-ttu-id="2dac2-124">This account includes the total manufacturing cost of units that are completed but not yet sold.</span><span class="sxs-lookup"><span data-stu-id="2dac2-124">This account includes the total manufacturing cost of units that are completed but not yet sold.</span></span> <span data-ttu-id="2dac2-125">At the time of sale, the cost of units sold is transferred from the Finished Goods account to the Cost of Goods Sold account.</span><span class="sxs-lookup"><span data-stu-id="2dac2-125">At the time of sale, the cost of units sold is transferred from the Finished Goods account to the Cost of Goods Sold account.</span></span>|  

<span data-ttu-id="2dac2-126">The inventory value is calculated by tracking the costs of all increases and decreases, as expressed by the following equation:</span><span class="sxs-lookup"><span data-stu-id="2dac2-126">The inventory value is calculated by tracking the costs of all increases and decreases, as expressed by the following equation:</span></span>  

* <span data-ttu-id="2dac2-127">inventory value = beginning balance of inventory + value of all increases - value of all decreases</span><span class="sxs-lookup"><span data-stu-id="2dac2-127">inventory value = beginning balance of inventory + value of all increases - value of all decreases</span></span>  

<span data-ttu-id="2dac2-128">Depending on the type of inventory, increases and decreases are represented by different transactions.</span><span class="sxs-lookup"><span data-stu-id="2dac2-128">Depending on the type of inventory, increases and decreases are represented by different transactions.</span></span>  

||<span data-ttu-id="2dac2-129">Increases</span><span class="sxs-lookup"><span data-stu-id="2dac2-129">Increases</span></span>|<span data-ttu-id="2dac2-130">Decreases</span><span class="sxs-lookup"><span data-stu-id="2dac2-130">Decreases</span></span>|  
|-|---------------|---------------|  
|<span data-ttu-id="2dac2-131">**Raw material inventory**</span><span class="sxs-lookup"><span data-stu-id="2dac2-131">**Raw material inventory**</span></span>|<span data-ttu-id="2dac2-132">-   Net purchases of material</span><span class="sxs-lookup"><span data-stu-id="2dac2-132">-   Net purchases of material</span></span><br /><span data-ttu-id="2dac2-133">-   Output of subassemblies</span><span class="sxs-lookup"><span data-stu-id="2dac2-133">-   Output of subassemblies</span></span><br /><span data-ttu-id="2dac2-134">-   Negative consumption</span><span class="sxs-lookup"><span data-stu-id="2dac2-134">-   Negative consumption</span></span>|<span data-ttu-id="2dac2-135">Material consumption</span><span class="sxs-lookup"><span data-stu-id="2dac2-135">Material consumption</span></span>|  
|<span data-ttu-id="2dac2-136">**WIP inventory**</span><span class="sxs-lookup"><span data-stu-id="2dac2-136">**WIP inventory**</span></span>|<span data-ttu-id="2dac2-137">-   Material consumption</span><span class="sxs-lookup"><span data-stu-id="2dac2-137">-   Material consumption</span></span><br /><span data-ttu-id="2dac2-138">-   Capacity consumption</span><span class="sxs-lookup"><span data-stu-id="2dac2-138">-   Capacity consumption</span></span><br /><span data-ttu-id="2dac2-139">-   Manufacturing overhead</span><span class="sxs-lookup"><span data-stu-id="2dac2-139">-   Manufacturing overhead</span></span>|<span data-ttu-id="2dac2-140">Output of end items (cost of goods manufactured)</span><span class="sxs-lookup"><span data-stu-id="2dac2-140">Output of end items (cost of goods manufactured)</span></span>|  
|<span data-ttu-id="2dac2-141">**Finished goods inventory**</span><span class="sxs-lookup"><span data-stu-id="2dac2-141">**Finished goods inventory**</span></span>|<span data-ttu-id="2dac2-142">Output of end items (cost of goods manufactured)</span><span class="sxs-lookup"><span data-stu-id="2dac2-142">Output of end items (cost of goods manufactured)</span></span>|<span data-ttu-id="2dac2-143">-   Sales (cost of goods sold)</span><span class="sxs-lookup"><span data-stu-id="2dac2-143">-   Sales (cost of goods sold)</span></span><br /><span data-ttu-id="2dac2-144">-   Negative output</span><span class="sxs-lookup"><span data-stu-id="2dac2-144">-   Negative output</span></span>|  
|<span data-ttu-id="2dac2-145">**Raw material inventory**</span><span class="sxs-lookup"><span data-stu-id="2dac2-145">**Raw material inventory**</span></span>|<span data-ttu-id="2dac2-146">-   Net purchases of material</span><span class="sxs-lookup"><span data-stu-id="2dac2-146">-   Net purchases of material</span></span><br /><span data-ttu-id="2dac2-147">-   Output of subassemblies</span><span class="sxs-lookup"><span data-stu-id="2dac2-147">-   Output of subassemblies</span></span><br /><span data-ttu-id="2dac2-148">-   Negative consumption</span><span class="sxs-lookup"><span data-stu-id="2dac2-148">-   Negative consumption</span></span>|<span data-ttu-id="2dac2-149">Material consumption</span><span class="sxs-lookup"><span data-stu-id="2dac2-149">Material consumption</span></span>|  

<span data-ttu-id="2dac2-150">The values of increases and decreases are recorded in the different types of manufactured inventory in the same way as for purchased inventory.</span><span class="sxs-lookup"><span data-stu-id="2dac2-150">The values of increases and decreases are recorded in the different types of manufactured inventory in the same way as for purchased inventory.</span></span> <span data-ttu-id="2dac2-151">Every time a transaction of inventory increase or decrease takes place, an item ledger entry and a corresponding general ledger entry are created for the amount.</span><span class="sxs-lookup"><span data-stu-id="2dac2-151">Every time a transaction of inventory increase or decrease takes place, an item ledger entry and a corresponding general ledger entry are created for the amount.</span></span> <span data-ttu-id="2dac2-152">For more information, see [Design Details: Inventory Posting](design-details-inventory-posting.md).</span><span class="sxs-lookup"><span data-stu-id="2dac2-152">For more information, see [Design Details: Inventory Posting](design-details-inventory-posting.md).</span></span>  

<span data-ttu-id="2dac2-153">Although values of transactions that are related to purchased goods are posted only as item ledger entries with related value entries, transactions that are related to produced items are posted as capacity ledger entries with related value entries, in addition to the item ledger entries.</span><span class="sxs-lookup"><span data-stu-id="2dac2-153">Although values of transactions that are related to purchased goods are posted only as item ledger entries with related value entries, transactions that are related to produced items are posted as capacity ledger entries with related value entries, in addition to the item ledger entries.</span></span>  

## <a name="posting-structure"></a><span data-ttu-id="2dac2-154">Posting Structure</span><span class="sxs-lookup"><span data-stu-id="2dac2-154">Posting Structure</span></span>  
<span data-ttu-id="2dac2-155">Posting production orders to WIP inventory involves output, consumption, and capacity.</span><span class="sxs-lookup"><span data-stu-id="2dac2-155">Posting production orders to WIP inventory involves output, consumption, and capacity.</span></span>  

<span data-ttu-id="2dac2-156">The following diagram shows the involved posting routines in codeunit 22.</span><span class="sxs-lookup"><span data-stu-id="2dac2-156">The following diagram shows the involved posting routines in codeunit 22.</span></span>  

<span data-ttu-id="2dac2-157">![Production order posting routines](media/design_details_inventory_costing_14_production_posting_1.png "design_details_inventory_costing_14_production_posting_1")</span><span class="sxs-lookup"><span data-stu-id="2dac2-157">![Production order posting routines](media/design_details_inventory_costing_14_production_posting_1.png "design_details_inventory_costing_14_production_posting_1")</span></span>  

<span data-ttu-id="2dac2-158">The following diagram shows the associations between the resulting entries and the cost objects.</span><span class="sxs-lookup"><span data-stu-id="2dac2-158">The following diagram shows the associations between the resulting entries and the cost objects.</span></span>  

<span data-ttu-id="2dac2-159">![Production entry flows](media/design_details_inventory_costing_14_production_posting_2.png "design_details_inventory_costing_14_production_posting_2")</span><span class="sxs-lookup"><span data-stu-id="2dac2-159">![Production entry flows](media/design_details_inventory_costing_14_production_posting_2.png "design_details_inventory_costing_14_production_posting_2")</span></span>  

<span data-ttu-id="2dac2-160">The capacity ledger entry describes the capacity consumption in terms of time units, whereas the related value entry describes the value of the specific capacity consumption.</span><span class="sxs-lookup"><span data-stu-id="2dac2-160">The capacity ledger entry describes the capacity consumption in terms of time units, whereas the related value entry describes the value of the specific capacity consumption.</span></span>  

<span data-ttu-id="2dac2-161">The item ledger entry describes the material consumption or output in terms of quantities, whereas the related value entry describes the value of this specific material consumption or output.</span><span class="sxs-lookup"><span data-stu-id="2dac2-161">The item ledger entry describes the material consumption or output in terms of quantities, whereas the related value entry describes the value of this specific material consumption or output.</span></span>  

<span data-ttu-id="2dac2-162">A value entry that describes WIP inventory value can be associated with one of the following combinations of cost objects:</span><span class="sxs-lookup"><span data-stu-id="2dac2-162">A value entry that describes WIP inventory value can be associated with one of the following combinations of cost objects:</span></span>  

-   <span data-ttu-id="2dac2-163">A production order line, a work or machine centre, and a capacity ledger entry.</span><span class="sxs-lookup"><span data-stu-id="2dac2-163">A production order line, a work or machine center, and a capacity ledger entry.</span></span>  
-   <span data-ttu-id="2dac2-164">A production order line, an item, and an item ledger entry.</span><span class="sxs-lookup"><span data-stu-id="2dac2-164">A production order line, an item, and an item ledger entry.</span></span>  
-   <span data-ttu-id="2dac2-165">Only a production order line</span><span class="sxs-lookup"><span data-stu-id="2dac2-165">Only a production order line</span></span>  

<span data-ttu-id="2dac2-166">For more information about how costs from production and assembly are posted to the general ledger, see [Design Details: Inventory Posting](design-details-inventory-posting.md).</span><span class="sxs-lookup"><span data-stu-id="2dac2-166">For more information about how costs from production and assembly are posted to the general ledger, see [Design Details: Inventory Posting](design-details-inventory-posting.md).</span></span>  

## <a name="capacity-posting"></a><span data-ttu-id="2dac2-167">Capacity Posting</span><span class="sxs-lookup"><span data-stu-id="2dac2-167">Capacity Posting</span></span>  
<span data-ttu-id="2dac2-168">Posting output from the last production order routing line results in a capacity ledger entry for the end item, in addition to its inventory increase.</span><span class="sxs-lookup"><span data-stu-id="2dac2-168">Posting output from the last production order routing line results in a capacity ledger entry for the end item, in addition to its inventory increase.</span></span>  

 <span data-ttu-id="2dac2-169">The capacity ledger entry is a record of the time that was spent to produce the item.</span><span class="sxs-lookup"><span data-stu-id="2dac2-169">The capacity ledger entry is a record of the time that was spent to produce the item.</span></span> <span data-ttu-id="2dac2-170">The related value entry describes the increase of the WIP inventory value, which is the value of the conversion cost.</span><span class="sxs-lookup"><span data-stu-id="2dac2-170">The related value entry describes the increase of the WIP inventory value, which is the value of the conversion cost.</span></span> <span data-ttu-id="2dac2-171">For more information, see “From the Capacity Ledger” in [Design Details: Accounts in the General Ledger](design-details-accounts-in-the-general-ledger.md).</span><span class="sxs-lookup"><span data-stu-id="2dac2-171">For more information, see “From the Capacity Ledger” in [Design Details: Accounts in the General Ledger](design-details-accounts-in-the-general-ledger.md).</span></span>  

## <a name="production-order-costing"></a><span data-ttu-id="2dac2-172">Production Order Costing</span><span class="sxs-lookup"><span data-stu-id="2dac2-172">Production Order Costing</span></span>  
 <span data-ttu-id="2dac2-173">To control inventory and production costs, a manufacturing company must measure the cost of production orders, because the predetermined standard cost of each produced item is capitalised in the balance sheet.</span><span class="sxs-lookup"><span data-stu-id="2dac2-173">To control inventory and production costs, a manufacturing company must measure the cost of production orders, because the predetermined standard cost of each produced item is capitalized in the balance sheet.</span></span> <span data-ttu-id="2dac2-174">For information about why produced items use the Standard costing method, see [Design Details: Costing Methods](design-details-costing-methods.md).</span><span class="sxs-lookup"><span data-stu-id="2dac2-174">For information about why produced items use the Standard costing method, see [Design Details: Costing Methods](design-details-costing-methods.md).</span></span>  

> [!NOTE]  
>  <span data-ttu-id="2dac2-175">In environments that do not use the Standard costing method, the actual rather than the standard cost of produced items is capitalised on the balance sheet.</span><span class="sxs-lookup"><span data-stu-id="2dac2-175">In environments that do not use the Standard costing method, the actual rather than the standard cost of produced items is capitalized on the balance sheet.</span></span>  

<span data-ttu-id="2dac2-176">The actual cost of a production order consists of the following cost components:</span><span class="sxs-lookup"><span data-stu-id="2dac2-176">The actual cost of a production order consists of the following cost components:</span></span>  

-   <span data-ttu-id="2dac2-177">Actual material cost</span><span class="sxs-lookup"><span data-stu-id="2dac2-177">Actual material cost</span></span>  
-   <span data-ttu-id="2dac2-178">Actual capacity cost or subcontractor cost</span><span class="sxs-lookup"><span data-stu-id="2dac2-178">Actual capacity cost or subcontractor cost</span></span>  
-   <span data-ttu-id="2dac2-179">Manufacturing overhead</span><span class="sxs-lookup"><span data-stu-id="2dac2-179">Manufacturing overhead</span></span>  

<span data-ttu-id="2dac2-180">These actual costs are posted to the production order and compared to the standard cost to calculate variances.</span><span class="sxs-lookup"><span data-stu-id="2dac2-180">These actual costs are posted to the production order and compared to the standard cost to calculate variances.</span></span> <span data-ttu-id="2dac2-181">Variances are calculated for each of the item cost components: raw materials, capacity, subcontractor, capacity overhead, and manufacturing overhead.</span><span class="sxs-lookup"><span data-stu-id="2dac2-181">Variances are calculated for each of the item cost components: raw materials, capacity, subcontractor, capacity overhead, and manufacturing overhead.</span></span> <span data-ttu-id="2dac2-182">The variances can be analysed to determine problems, such as excessive waste in processing.</span><span class="sxs-lookup"><span data-stu-id="2dac2-182">The variances can be analyzed to determine problems, such as excessive waste in processing.</span></span>  

<span data-ttu-id="2dac2-183">In standard-cost environments, the costing of a production order is based on the following mechanism:</span><span class="sxs-lookup"><span data-stu-id="2dac2-183">In standard-cost environments, the costing of a production order is based on the following mechanism:</span></span>  

1.  <span data-ttu-id="2dac2-184">When the last routing operation is posted, the production order cost is posted to the item ledger and set to the expected cost.</span><span class="sxs-lookup"><span data-stu-id="2dac2-184">When the last routing operation is posted, the production order cost is posted to the item ledger and set to the expected cost.</span></span>  

    <span data-ttu-id="2dac2-185">This cost equals the output quantity that is posted in the output journal multiplied by the standard cost that is copied from the item card.</span><span class="sxs-lookup"><span data-stu-id="2dac2-185">This cost equals the output quantity that is posted in the output journal multiplied by the standard cost that is copied from the item card.</span></span> <span data-ttu-id="2dac2-186">The cost is treated as expected cost until the production order is finished.</span><span class="sxs-lookup"><span data-stu-id="2dac2-186">The cost is treated as expected cost until the production order is finished.</span></span> <span data-ttu-id="2dac2-187">For more information, see [Design Details: Expected Cost Posting](design-details-expected-cost-posting.md).</span><span class="sxs-lookup"><span data-stu-id="2dac2-187">For more information, see [Design Details: Expected Cost Posting](design-details-expected-cost-posting.md).</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="2dac2-188">This differs from assembly order posting, which always posts actual costs.</span><span class="sxs-lookup"><span data-stu-id="2dac2-188">This differs from assembly order posting, which always posts actual costs.</span></span> <span data-ttu-id="2dac2-189">For more information, see [Design Details: Assembly Order Posting](design-details-assembly-order-posting.md).</span><span class="sxs-lookup"><span data-stu-id="2dac2-189">For more information, see [Design Details: Assembly Order Posting](design-details-assembly-order-posting.md).</span></span>  
2.  <span data-ttu-id="2dac2-190">When the production order is set to **Finished**, the order is invoiced by running the **Adjust Cost-Item Entries** batch job.</span><span class="sxs-lookup"><span data-stu-id="2dac2-190">When the production order is set to **Finished**, the order is invoiced by running the **Adjust Cost-Item Entries** batch job.</span></span> <span data-ttu-id="2dac2-191">As a result, the total cost of the order is calculated based on the standard cost of the consumed materials and capacity.</span><span class="sxs-lookup"><span data-stu-id="2dac2-191">As a result, the total cost of the order is calculated based on the standard cost of the consumed materials and capacity.</span></span> <span data-ttu-id="2dac2-192">The variances between the calculated standard costs and the actual production costs are calculated and posted.</span><span class="sxs-lookup"><span data-stu-id="2dac2-192">The variances between the calculated standard costs and the actual production costs are calculated and posted.</span></span>  

## <a name="see-also"></a><span data-ttu-id="2dac2-193">See Also</span><span class="sxs-lookup"><span data-stu-id="2dac2-193">See Also</span></span>  
 <span data-ttu-id="2dac2-194">[Design Details: Inventory Costing](design-details-inventory-costing.md) </span><span class="sxs-lookup"><span data-stu-id="2dac2-194">[Design Details: Inventory Costing](design-details-inventory-costing.md) </span></span>  
 [<span data-ttu-id="2dac2-195">Design Details: Assembly Order Posting</span><span class="sxs-lookup"><span data-stu-id="2dac2-195">Design Details: Assembly Order Posting</span></span>](design-details-assembly-order-posting.md)  
 <span data-ttu-id="2dac2-196">[Managing Inventory Costs](finance-manage-inventory-costs.md) [Finance](finance.md)</span><span class="sxs-lookup"><span data-stu-id="2dac2-196">[Managing Inventory Costs](finance-manage-inventory-costs.md) [Finance](finance.md)</span></span>  
 [<span data-ttu-id="2dac2-197">Working with Financials</span><span class="sxs-lookup"><span data-stu-id="2dac2-197">Working with Financials</span></span>](ui-work-product.md)
