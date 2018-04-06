---
title: Design Details - Warehouse Overview | Microsoft Docs
description: To support the physical handling of items on the zone and bin level, all information must be traced for each transaction or movement in the warehouse. This is managed in the **Warehouse Entry** table. Each transaction is stored in a warehouse register.
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/23/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: d7fb34e1c9428a64c71ff47be8bcff174649c00d
ms.openlocfilehash: 54d716a069384bf4acdc5c0e24e4e1e292e2be43
ms.contentlocale: en-au
ms.lasthandoff: 03/22/2018

---
# <a name="design-details-warehouse-overview"></a><span data-ttu-id="148ba-105">Design Details: Warehouse Overview</span><span class="sxs-lookup"><span data-stu-id="148ba-105">Design Details: Warehouse Overview</span></span>
<span data-ttu-id="148ba-106">To support the physical handling of items on the zone and bin level, all information must be traced for each transaction or movement in the warehouse.</span><span class="sxs-lookup"><span data-stu-id="148ba-106">To support the physical handling of items on the zone and bin level, all information must be traced for each transaction or movement in the warehouse.</span></span> <span data-ttu-id="148ba-107">This is managed in the **Warehouse Entry** table.</span><span class="sxs-lookup"><span data-stu-id="148ba-107">This is managed in the **Warehouse Entry** table.</span></span> <span data-ttu-id="148ba-108">Each transaction is stored in a warehouse register.</span><span class="sxs-lookup"><span data-stu-id="148ba-108">Each transaction is stored in a warehouse register.</span></span>  

<span data-ttu-id="148ba-109">Warehouse documents and a warehouse journal are used to register item movements in the warehouse.</span><span class="sxs-lookup"><span data-stu-id="148ba-109">Warehouse documents and a warehouse journal are used to register item movements in the warehouse.</span></span> <span data-ttu-id="148ba-110">Every time that an item in the warehouse is moved, received, put away, picked, shipped, or adjusted, warehouse entries are registered to store the physical information about zone, bin, and quantity.</span><span class="sxs-lookup"><span data-stu-id="148ba-110">Every time that an item in the warehouse is moved, received, put away, picked, shipped, or adjusted, warehouse entries are registered to store the physical information about zone, bin, and quantity.</span></span> <span data-ttu-id="148ba-111">For more information, see [Design Details: Inbound Warehouse Flow](design-details-outbound-warehouse-flow.md).</span><span class="sxs-lookup"><span data-stu-id="148ba-111">For more information, see [Design Details: Inbound Warehouse Flow](design-details-outbound-warehouse-flow.md).</span></span>  

<span data-ttu-id="148ba-112">The **Bin Content** table is used to handle all the different dimensions of the contents of a bin per item, such as unit of measure, maximum quantity, and minimum quantity.</span><span class="sxs-lookup"><span data-stu-id="148ba-112">The **Bin Content** table is used to handle all the different dimensions of the contents of a bin per item, such as unit of measure, maximum quantity, and minimum quantity.</span></span> <span data-ttu-id="148ba-113">The **Bin Content** table also contains flow fields to the warehouse entries, warehouse instructions, and warehouse journal lines, which ensures that the availability of an item per bin and a bin for an item can be calculated quickly.</span><span class="sxs-lookup"><span data-stu-id="148ba-113">The **Bin Content** table also contains flow fields to the warehouse entries, warehouse instructions, and warehouse journal lines, which ensures that the availability of an item per bin and a bin for an item can be calculated quickly.</span></span> <span data-ttu-id="148ba-114">For more information, see [Design Details: Availability in the Warehouse](design-details-availability-in-the-warehouse.md).</span><span class="sxs-lookup"><span data-stu-id="148ba-114">For more information, see [Design Details: Availability in the Warehouse](design-details-availability-in-the-warehouse.md).</span></span>  

<span data-ttu-id="148ba-115">When item postings occur outside the warehouse module, a default adjustment bin per location is used to synchronise warehouse entries with inventory entries.</span><span class="sxs-lookup"><span data-stu-id="148ba-115">When item postings occur outside the warehouse module, a default adjustment bin per location is used to synchronize warehouse entries with inventory entries.</span></span> <span data-ttu-id="148ba-116">During physical inventory of the warehouse, any differences between the calculated and counted quantities are recorded in the adjustment bin and then posted as correcting item ledger entries.</span><span class="sxs-lookup"><span data-stu-id="148ba-116">During physical inventory of the warehouse, any differences between the calculated and counted quantities are recorded in the adjustment bin and then posted as correcting item ledger entries.</span></span> <span data-ttu-id="148ba-117">For more information, see [Design Details: Integration with Inventory](design-details-integration-with-inventory.md).</span><span class="sxs-lookup"><span data-stu-id="148ba-117">For more information, see [Design Details: Integration with Inventory](design-details-integration-with-inventory.md).</span></span>  

<span data-ttu-id="148ba-118">The following illustration outlines typical warehouse flows.</span><span class="sxs-lookup"><span data-stu-id="148ba-118">The following illustration outlines typical warehouse flows.</span></span>  

<span data-ttu-id="148ba-119">![Overview of warehouse processes](media/design_details_warehouse_management_overview.png "design_details_warehouse_management_overview")</span><span class="sxs-lookup"><span data-stu-id="148ba-119">![Overview of warehouse processes](media/design_details_warehouse_management_overview.png "design_details_warehouse_management_overview")</span></span>  

## <a name="basic-or-advanced-warehousing"></a><span data-ttu-id="148ba-120">Basic or Advanced Warehousing</span><span class="sxs-lookup"><span data-stu-id="148ba-120">Basic or Advanced Warehousing</span></span>  
<span data-ttu-id="148ba-121">Warehouse functionality in [!INCLUDE[d365fin](includes/d365fin_md.md)] can be implemented in different complexity levels, depending on a company’s processes and order volume.</span><span class="sxs-lookup"><span data-stu-id="148ba-121">Warehouse functionality in [!INCLUDE[d365fin](includes/d365fin_md.md)] can be implemented in different complexity levels, depending on a company’s processes and order volume.</span></span> <span data-ttu-id="148ba-122">The main difference is that activities are performed order-by-order in basic warehousing when they are consolidated for multiple orders in advanced warehousing.</span><span class="sxs-lookup"><span data-stu-id="148ba-122">The main difference is that activities are performed order-by-order in basic warehousing when they are consolidated for multiple orders in advanced warehousing.</span></span>  

 <span data-ttu-id="148ba-123">To differentiate between the different complexity levels, this documentation refers to two general denominations, Basic and Advanced Warehousing.</span><span class="sxs-lookup"><span data-stu-id="148ba-123">To differentiate between the different complexity levels, this documentation refers to two general denominations, Basic and Advanced Warehousing.</span></span> <span data-ttu-id="148ba-124">This simple differentiation covers several different complexity levels as defined by product granules and location setup, each supported by different UI documents.</span><span class="sxs-lookup"><span data-stu-id="148ba-124">This simple differentiation covers several different complexity levels as defined by product granules and location setup, each supported by different UI documents.</span></span> <span data-ttu-id="148ba-125">For more information, see [Design Details: Warehouse Setup](design-details-warehouse-setup.md).</span><span class="sxs-lookup"><span data-stu-id="148ba-125">For more information, see [Design Details: Warehouse Setup](design-details-warehouse-setup.md).</span></span>  

> [!NOTE]  
>  <span data-ttu-id="148ba-126">The most advanced level of warehousing is referred to as “WMS installations” in this documentation, since this level requires the most advanced granule, Warehouse Management Systems.</span><span class="sxs-lookup"><span data-stu-id="148ba-126">The most advanced level of warehousing is referred to as “WMS installations” in this documentation, since this level requires the most advanced granule, Warehouse Management Systems.</span></span>  

 <span data-ttu-id="148ba-127">The following different UI documents are used in basic and advanced warehousing.</span><span class="sxs-lookup"><span data-stu-id="148ba-127">The following different UI documents are used in basic and advanced warehousing.</span></span>  

## <a name="basic-ui-documents"></a><span data-ttu-id="148ba-128">Basic UI Documents</span><span class="sxs-lookup"><span data-stu-id="148ba-128">Basic UI Documents</span></span>  

-   <span data-ttu-id="148ba-129">**Inventory Put-away**</span><span class="sxs-lookup"><span data-stu-id="148ba-129">**Inventory Put-away**</span></span>  
-   <span data-ttu-id="148ba-130">**Inventory Pick**</span><span class="sxs-lookup"><span data-stu-id="148ba-130">**Inventory Pick**</span></span>  
-   <span data-ttu-id="148ba-131">**Inventory Movement**</span><span class="sxs-lookup"><span data-stu-id="148ba-131">**Inventory Movement**</span></span>  
-   <span data-ttu-id="148ba-132">**Item Journal**</span><span class="sxs-lookup"><span data-stu-id="148ba-132">**Item Journal**</span></span>  
-   <span data-ttu-id="148ba-133">**Item Reclassification Journal**</span><span class="sxs-lookup"><span data-stu-id="148ba-133">**Item Reclassification Journal**</span></span>  
-   <span data-ttu-id="148ba-134">(Various reports)</span><span class="sxs-lookup"><span data-stu-id="148ba-134">(Various reports)</span></span>  

## <a name="advanced-ui-documents"></a><span data-ttu-id="148ba-135">Advanced UI Documents</span><span class="sxs-lookup"><span data-stu-id="148ba-135">Advanced UI Documents</span></span>  

-   <span data-ttu-id="148ba-136">**Warehouse Receipt**</span><span class="sxs-lookup"><span data-stu-id="148ba-136">**Warehouse Receipt**</span></span>  
-   <span data-ttu-id="148ba-137">**Put-away Worksheet**</span><span class="sxs-lookup"><span data-stu-id="148ba-137">**Put-away Worksheet**</span></span>  
-   <span data-ttu-id="148ba-138">**Warehouse Put-away**</span><span class="sxs-lookup"><span data-stu-id="148ba-138">**Warehouse Put-away**</span></span>  
-   <span data-ttu-id="148ba-139">**Pick Worksheet**</span><span class="sxs-lookup"><span data-stu-id="148ba-139">**Pick Worksheet**</span></span>  
-   <span data-ttu-id="148ba-140">**Warehouse Pick**</span><span class="sxs-lookup"><span data-stu-id="148ba-140">**Warehouse Pick**</span></span>  
-   <span data-ttu-id="148ba-141">**Movement Worksheet**</span><span class="sxs-lookup"><span data-stu-id="148ba-141">**Movement Worksheet**</span></span>  
-   <span data-ttu-id="148ba-142">**Warehouse Movement**</span><span class="sxs-lookup"><span data-stu-id="148ba-142">**Warehouse Movement**</span></span>  
-   <span data-ttu-id="148ba-143">**Internal Whse. Pick**</span><span class="sxs-lookup"><span data-stu-id="148ba-143">**Internal Whse. Pick**</span></span>  
-   <span data-ttu-id="148ba-144">**Internal Whse. Put-away**</span><span class="sxs-lookup"><span data-stu-id="148ba-144">**Internal Whse. Put-away**</span></span>  
-   <span data-ttu-id="148ba-145">**Bin Creation Worksheet**</span><span class="sxs-lookup"><span data-stu-id="148ba-145">**Bin Creation Worksheet**</span></span>  
-   <span data-ttu-id="148ba-146">**Bin Content Creation Worksheet**</span><span class="sxs-lookup"><span data-stu-id="148ba-146">**Bin Content Creation Worksheet**</span></span>  
-   <span data-ttu-id="148ba-147">**Whse. Item Journal**</span><span class="sxs-lookup"><span data-stu-id="148ba-147">**Whse. Item Journal**</span></span>  
-   <span data-ttu-id="148ba-148">**Whse. Item Reclass. Journal**</span><span class="sxs-lookup"><span data-stu-id="148ba-148">**Whse. Item Reclass. Journal**</span></span>  
-   <span data-ttu-id="148ba-149">(Various reports)</span><span class="sxs-lookup"><span data-stu-id="148ba-149">(Various reports)</span></span>  

<span data-ttu-id="148ba-150">For more information about each document, see the respective window topics.</span><span class="sxs-lookup"><span data-stu-id="148ba-150">For more information about each document, see the respective window topics.</span></span>  

### <a name="terminology"></a><span data-ttu-id="148ba-151">Terminology</span><span class="sxs-lookup"><span data-stu-id="148ba-151">Terminology</span></span>  
<span data-ttu-id="148ba-152">To align with the financial concepts of purchases and sales, [!INCLUDE[d365fin](includes/d365fin_md.md)] warehouse documentation refers to the following terms for item flow in the warehouse.</span><span class="sxs-lookup"><span data-stu-id="148ba-152">To align with the financial concepts of purchases and sales, [!INCLUDE[d365fin](includes/d365fin_md.md)] warehouse documentation refers to the following terms for item flow in the warehouse.</span></span>  

|<span data-ttu-id="148ba-153">Term</span><span class="sxs-lookup"><span data-stu-id="148ba-153">Term</span></span>|<span data-ttu-id="148ba-154">Description</span><span class="sxs-lookup"><span data-stu-id="148ba-154">Description</span></span>|  
|----------|---------------------------------------|  
|<span data-ttu-id="148ba-155">Inbound flow</span><span class="sxs-lookup"><span data-stu-id="148ba-155">Inbound flow</span></span>|<span data-ttu-id="148ba-156">Items moving into the warehouse location, such as purchases and inbound transfers.</span><span class="sxs-lookup"><span data-stu-id="148ba-156">Items moving into the warehouse location, such as purchases and inbound transfers.</span></span>|  
|<span data-ttu-id="148ba-157">Internal flow</span><span class="sxs-lookup"><span data-stu-id="148ba-157">Internal flow</span></span>|<span data-ttu-id="148ba-158">Items moving inside the warehouse location, such as production components and output.</span><span class="sxs-lookup"><span data-stu-id="148ba-158">Items moving inside the warehouse location, such as production components and output.</span></span>|  
|<span data-ttu-id="148ba-159">Outbound flow</span><span class="sxs-lookup"><span data-stu-id="148ba-159">Outbound flow</span></span>|<span data-ttu-id="148ba-160">Items moving out of the warehouse location, such as sales and outbound transfers.</span><span class="sxs-lookup"><span data-stu-id="148ba-160">Items moving out of the warehouse location, such as sales and outbound transfers.</span></span>|  

## <a name="see-also"></a><span data-ttu-id="148ba-161">See Also</span><span class="sxs-lookup"><span data-stu-id="148ba-161">See Also</span></span>  
 [<span data-ttu-id="148ba-162">Design Details: Warehouse Management</span><span class="sxs-lookup"><span data-stu-id="148ba-162">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)

