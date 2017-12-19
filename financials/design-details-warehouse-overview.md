---
title: Design Details - Warehouse Overview | Microsoft Docs
description: To support the physical handling of items on the zone and bin level, all information must be traced for each transaction or movement in the warehouse. This is managed in the **Warehouse Entry** table. Each transaction is stored in a warehouse register.
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/23/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 2c13559bb3dc44cdb61697f5135c5b931e34d2a8
ms.openlocfilehash: f5dc30ab398ae41ab8c36b6c207d2f48036cc98c
ms.contentlocale: en-au
ms.lasthandoff: 09/22/2017

---
# <a name="design-details-warehouse-overview"></a><span data-ttu-id="5a953-105">Design Details: Warehouse Overview</span><span class="sxs-lookup"><span data-stu-id="5a953-105">Design Details: Warehouse Overview</span></span>
<span data-ttu-id="5a953-106">To support the physical handling of items on the zone and bin level, all information must be traced for each transaction or movement in the warehouse.</span><span class="sxs-lookup"><span data-stu-id="5a953-106">To support the physical handling of items on the zone and bin level, all information must be traced for each transaction or movement in the warehouse.</span></span> <span data-ttu-id="5a953-107">This is managed in the **Warehouse Entry** table.</span><span class="sxs-lookup"><span data-stu-id="5a953-107">This is managed in the **Warehouse Entry** table.</span></span> <span data-ttu-id="5a953-108">Each transaction is stored in a warehouse register.</span><span class="sxs-lookup"><span data-stu-id="5a953-108">Each transaction is stored in a warehouse register.</span></span>  

<span data-ttu-id="5a953-109">Warehouse documents and a warehouse journal are used to register item movements in the warehouse.</span><span class="sxs-lookup"><span data-stu-id="5a953-109">Warehouse documents and a warehouse journal are used to register item movements in the warehouse.</span></span> <span data-ttu-id="5a953-110">Every time that an item in the warehouse is moved, received, put away, picked, shipped, or adjusted, warehouse entries are registered to store the physical information about zone, bin, and quantity.</span><span class="sxs-lookup"><span data-stu-id="5a953-110">Every time that an item in the warehouse is moved, received, put away, picked, shipped, or adjusted, warehouse entries are registered to store the physical information about zone, bin, and quantity.</span></span> <span data-ttu-id="5a953-111">For more information, see [Design Details: Inbound Warehouse Flow](design-details-outbound-warehouse-flow.md).</span><span class="sxs-lookup"><span data-stu-id="5a953-111">For more information, see [Design Details: Inbound Warehouse Flow](design-details-outbound-warehouse-flow.md).</span></span>  

<span data-ttu-id="5a953-112">The **Bin Content** table is used to handle all the different dimensions of the contents of a bin per item, such as unit of measure, maximum quantity, and minimum quantity.</span><span class="sxs-lookup"><span data-stu-id="5a953-112">The **Bin Content** table is used to handle all the different dimensions of the contents of a bin per item, such as unit of measure, maximum quantity, and minimum quantity.</span></span> <span data-ttu-id="5a953-113">The **Bin Content** table also contains flow fields to the warehouse entries, warehouse instructions, and warehouse journal lines, which ensures that the availability of an item per bin and a bin for an item can be calculated quickly.</span><span class="sxs-lookup"><span data-stu-id="5a953-113">The **Bin Content** table also contains flow fields to the warehouse entries, warehouse instructions, and warehouse journal lines, which ensures that the availability of an item per bin and a bin for an item can be calculated quickly.</span></span> <span data-ttu-id="5a953-114">For more information, see [Design Details: Availability in the Warehouse](design-details-availability-in-the-warehouse.md).</span><span class="sxs-lookup"><span data-stu-id="5a953-114">For more information, see [Design Details: Availability in the Warehouse](design-details-availability-in-the-warehouse.md).</span></span>  

<span data-ttu-id="5a953-115">When item postings occur outside the warehouse module, a default adjustment bin per location is used to synchronise warehouse entries with inventory entries.</span><span class="sxs-lookup"><span data-stu-id="5a953-115">When item postings occur outside the warehouse module, a default adjustment bin per location is used to synchronize warehouse entries with inventory entries.</span></span> <span data-ttu-id="5a953-116">During physical inventory of the warehouse, any differences between the calculated and counted quantities are recorded in the adjustment bin and then posted as correcting item ledger entries.</span><span class="sxs-lookup"><span data-stu-id="5a953-116">During physical inventory of the warehouse, any differences between the calculated and counted quantities are recorded in the adjustment bin and then posted as correcting item ledger entries.</span></span> <span data-ttu-id="5a953-117">For more information, see [Design Details: Integration with Inventory](design-details-integration-with-inventory.md).</span><span class="sxs-lookup"><span data-stu-id="5a953-117">For more information, see [Design Details: Integration with Inventory](design-details-integration-with-inventory.md).</span></span>  

<span data-ttu-id="5a953-118">The following illustration outlines typical warehouse flows.</span><span class="sxs-lookup"><span data-stu-id="5a953-118">The following illustration outlines typical warehouse flows.</span></span>  

<span data-ttu-id="5a953-119">![Overview of warehouse processes](media/design_details_warehouse_management_overview.png "design_details_warehouse_management_overview")</span><span class="sxs-lookup"><span data-stu-id="5a953-119">![Overview of warehouse processes](media/design_details_warehouse_management_overview.png "design_details_warehouse_management_overview")</span></span>  

## <a name="basic-or-advanced-warehousing"></a><span data-ttu-id="5a953-120">Basic or Advanced Warehousing</span><span class="sxs-lookup"><span data-stu-id="5a953-120">Basic or Advanced Warehousing</span></span>  
<span data-ttu-id="5a953-121">Warehouse functionality in [!INCLUDE[d365fin](includes/d365fin_md.md)] can be implemented in different complexity levels, depending on a company’s processes and order volume.</span><span class="sxs-lookup"><span data-stu-id="5a953-121">Warehouse functionality in [!INCLUDE[d365fin](includes/d365fin_md.md)] can be implemented in different complexity levels, depending on a company’s processes and order volume.</span></span> <span data-ttu-id="5a953-122">The main difference is that activities are performed order-by-order in basic warehousing when they are consolidated for multiple orders in advanced warehousing.</span><span class="sxs-lookup"><span data-stu-id="5a953-122">The main difference is that activities are performed order-by-order in basic warehousing when they are consolidated for multiple orders in advanced warehousing.</span></span>  

 <span data-ttu-id="5a953-123">To differentiate between the different complexity levels, this documentation refers to two general denominations, Basic and Advanced Warehousing.</span><span class="sxs-lookup"><span data-stu-id="5a953-123">To differentiate between the different complexity levels, this documentation refers to two general denominations, Basic and Advanced Warehousing.</span></span> <span data-ttu-id="5a953-124">This simple differentiation covers several different complexity levels as defined by product granules and location setup, each supported by different UI documents.</span><span class="sxs-lookup"><span data-stu-id="5a953-124">This simple differentiation covers several different complexity levels as defined by product granules and location setup, each supported by different UI documents.</span></span> <span data-ttu-id="5a953-125">For more information, see [Design Details: Warehouse Setup](design-details-warehouse-setup.md).</span><span class="sxs-lookup"><span data-stu-id="5a953-125">For more information, see [Design Details: Warehouse Setup](design-details-warehouse-setup.md).</span></span>  

> [!NOTE]  
>  <span data-ttu-id="5a953-126">The most advanced level of warehousing is referred to as “WMS installations” in this documentation, since this level requires the most advanced granule, Warehouse Management Systems.</span><span class="sxs-lookup"><span data-stu-id="5a953-126">The most advanced level of warehousing is referred to as “WMS installations” in this documentation, since this level requires the most advanced granule, Warehouse Management Systems.</span></span>  

 <span data-ttu-id="5a953-127">The following different UI documents are used in basic and advanced warehousing.</span><span class="sxs-lookup"><span data-stu-id="5a953-127">The following different UI documents are used in basic and advanced warehousing.</span></span>  

## <a name="basic-ui-documents"></a><span data-ttu-id="5a953-128">Basic UI Documents</span><span class="sxs-lookup"><span data-stu-id="5a953-128">Basic UI Documents</span></span>  

-   <span data-ttu-id="5a953-129">**Inventory Put-away**</span><span class="sxs-lookup"><span data-stu-id="5a953-129">**Inventory Put-away**</span></span>  
-   <span data-ttu-id="5a953-130">**Inventory Pick**</span><span class="sxs-lookup"><span data-stu-id="5a953-130">**Inventory Pick**</span></span>  
-   <span data-ttu-id="5a953-131">**Inventory Movement**</span><span class="sxs-lookup"><span data-stu-id="5a953-131">**Inventory Movement**</span></span>  
-   <span data-ttu-id="5a953-132">**Item Journal**</span><span class="sxs-lookup"><span data-stu-id="5a953-132">**Item Journal**</span></span>  
-   <span data-ttu-id="5a953-133">**Item Reclassification Journal**</span><span class="sxs-lookup"><span data-stu-id="5a953-133">**Item Reclassification Journal**</span></span>  
-   <span data-ttu-id="5a953-134">(Various reports)</span><span class="sxs-lookup"><span data-stu-id="5a953-134">(Various reports)</span></span>  

## <a name="advanced-ui-documents"></a><span data-ttu-id="5a953-135">Advanced UI Documents</span><span class="sxs-lookup"><span data-stu-id="5a953-135">Advanced UI Documents</span></span>  

-   <span data-ttu-id="5a953-136">**Warehouse Receipt**</span><span class="sxs-lookup"><span data-stu-id="5a953-136">**Warehouse Receipt**</span></span>  
-   <span data-ttu-id="5a953-137">**Put-away Worksheet**</span><span class="sxs-lookup"><span data-stu-id="5a953-137">**Put-away Worksheet**</span></span>  
-   <span data-ttu-id="5a953-138">**Warehouse Put-away**</span><span class="sxs-lookup"><span data-stu-id="5a953-138">**Warehouse Put-away**</span></span>  
-   <span data-ttu-id="5a953-139">**Pick Worksheet**</span><span class="sxs-lookup"><span data-stu-id="5a953-139">**Pick Worksheet**</span></span>  
-   <span data-ttu-id="5a953-140">**Warehouse Pick**</span><span class="sxs-lookup"><span data-stu-id="5a953-140">**Warehouse Pick**</span></span>  
-   <span data-ttu-id="5a953-141">**Movement Worksheet**</span><span class="sxs-lookup"><span data-stu-id="5a953-141">**Movement Worksheet**</span></span>  
-   <span data-ttu-id="5a953-142">**Warehouse Movement**</span><span class="sxs-lookup"><span data-stu-id="5a953-142">**Warehouse Movement**</span></span>  
-   <span data-ttu-id="5a953-143">**Internal Whse. Pick**</span><span class="sxs-lookup"><span data-stu-id="5a953-143">**Internal Whse. Pick**</span></span>  
-   <span data-ttu-id="5a953-144">**Internal Whse. Put-away**</span><span class="sxs-lookup"><span data-stu-id="5a953-144">**Internal Whse. Put-away**</span></span>  
-   <span data-ttu-id="5a953-145">**Bin Creation Worksheet**</span><span class="sxs-lookup"><span data-stu-id="5a953-145">**Bin Creation Worksheet**</span></span>  
-   <span data-ttu-id="5a953-146">**Bin Content Creation Worksheet**</span><span class="sxs-lookup"><span data-stu-id="5a953-146">**Bin Content Creation Worksheet**</span></span>  
-   <span data-ttu-id="5a953-147">**Whse. Item Journal**</span><span class="sxs-lookup"><span data-stu-id="5a953-147">**Whse. Item Journal**</span></span>  
-   <span data-ttu-id="5a953-148">**Whse. Item Reclass. Journal**</span><span class="sxs-lookup"><span data-stu-id="5a953-148">**Whse. Item Reclass. Journal**</span></span>  
-   <span data-ttu-id="5a953-149">(Various reports)</span><span class="sxs-lookup"><span data-stu-id="5a953-149">(Various reports)</span></span>  

<span data-ttu-id="5a953-150">For more information about each document, see the respective window topics.</span><span class="sxs-lookup"><span data-stu-id="5a953-150">For more information about each document, see the respective window topics.</span></span>  

### <a name="terminology"></a><span data-ttu-id="5a953-151">Terminology</span><span class="sxs-lookup"><span data-stu-id="5a953-151">Terminology</span></span>  
<span data-ttu-id="5a953-152">To align with the financial concepts of purchases and sales, [!INCLUDE[d365fin](includes/d365fin_md.md)] warehouse documentation refers to the following terms for item flow in the warehouse.</span><span class="sxs-lookup"><span data-stu-id="5a953-152">To align with the financial concepts of purchases and sales, [!INCLUDE[d365fin](includes/d365fin_md.md)] warehouse documentation refers to the following terms for item flow in the warehouse.</span></span>  

|<span data-ttu-id="5a953-153">Term</span><span class="sxs-lookup"><span data-stu-id="5a953-153">Term</span></span>|<span data-ttu-id="5a953-154">Description</span><span class="sxs-lookup"><span data-stu-id="5a953-154">Description</span></span>|  
|----------|---------------------------------------|  
|<span data-ttu-id="5a953-155">Inbound flow</span><span class="sxs-lookup"><span data-stu-id="5a953-155">Inbound flow</span></span>|<span data-ttu-id="5a953-156">Items moving into the warehouse location, such as purchases and inbound transfers.</span><span class="sxs-lookup"><span data-stu-id="5a953-156">Items moving into the warehouse location, such as purchases and inbound transfers.</span></span>|  
|<span data-ttu-id="5a953-157">Internal flow</span><span class="sxs-lookup"><span data-stu-id="5a953-157">Internal flow</span></span>|<span data-ttu-id="5a953-158">Items moving inside the warehouse location, such as production components and output.</span><span class="sxs-lookup"><span data-stu-id="5a953-158">Items moving inside the warehouse location, such as production components and output.</span></span>|  
|<span data-ttu-id="5a953-159">Outbound flow</span><span class="sxs-lookup"><span data-stu-id="5a953-159">Outbound flow</span></span>|<span data-ttu-id="5a953-160">Items moving out of the warehouse location, such as sales and outbound transfers.</span><span class="sxs-lookup"><span data-stu-id="5a953-160">Items moving out of the warehouse location, such as sales and outbound transfers.</span></span>|  

## <a name="see-also"></a><span data-ttu-id="5a953-161">See Also</span><span class="sxs-lookup"><span data-stu-id="5a953-161">See Also</span></span>  
 [<span data-ttu-id="5a953-162">Design Details: Warehouse Management</span><span class="sxs-lookup"><span data-stu-id="5a953-162">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)
