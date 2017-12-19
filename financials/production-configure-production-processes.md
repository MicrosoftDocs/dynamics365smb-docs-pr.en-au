---
title: Configure Production Processes | Microsoft Docs
description: To convert material into produced end items, production resources, such as bills of material, routings, machine operators, and machinery must be set up in the system.
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/04/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 2c13559bb3dc44cdb61697f5135c5b931e34d2a8
ms.openlocfilehash: de493a4697c3a5c2fb8581545a29ee832fe1c3dc
ms.contentlocale: en-au
ms.lasthandoff: 09/22/2017

---
# <a name="setting-up-manufacturing"></a><span data-ttu-id="a6d61-103">Setting Up Manufacturing</span><span class="sxs-lookup"><span data-stu-id="a6d61-103">Setting Up Manufacturing</span></span>
<span data-ttu-id="a6d61-104">To convert material into produced end items, production resources, such as bills of material, routings, machine operators, and machinery must be set up in the system.</span><span class="sxs-lookup"><span data-stu-id="a6d61-104">To convert material into produced end items, production resources, such as bills of material, routings, machine operators, and machinery must be set up in the system.</span></span>

<span data-ttu-id="a6d61-105">Operators and machines are represented in the system as machine centres that may be organised in work centres and work centre groups.</span><span class="sxs-lookup"><span data-stu-id="a6d61-105">Operators and machines are represented in the system as machine centers that may be organized in work centers and work center groups.</span></span> <span data-ttu-id="a6d61-106">When these resources are established, they can be loaded with operations according to the item's defined material (BOM) and process (routing) structure, and according to the capacity of the machine or work centre.</span><span class="sxs-lookup"><span data-stu-id="a6d61-106">When these resources are established, they can be loaded with operations according to the item's defined material (BOM) and process (routing) structure, and according to the capacity of the machine or work center.</span></span> <span data-ttu-id="a6d61-107">You can also set the production capacity of each resource.</span><span class="sxs-lookup"><span data-stu-id="a6d61-107">You can also set the production capacity of each resource.</span></span> <span data-ttu-id="a6d61-108">Capacity is defined by the work time available in the machine and work centres, and is governed by calendars for each level.</span><span class="sxs-lookup"><span data-stu-id="a6d61-108">Capacity is defined by the work time available in the machine and work centers, and is governed by calendars for each level.</span></span> <span data-ttu-id="a6d61-109">A work centre calendar specifies the working days or hours, shifts, holidays, and absence that determine the work centre’s gross available capacity (typically measured in minutes).</span><span class="sxs-lookup"><span data-stu-id="a6d61-109">A work center calendar specifies the working days or hours, shifts, holidays, and absence that determine the work center’s gross available capacity (typically measured in minutes).</span></span> <span data-ttu-id="a6d61-110">All of this is determined by defined efficiency and capacity values.</span><span class="sxs-lookup"><span data-stu-id="a6d61-110">All of this is determined by defined efficiency and capacity values.</span></span>  

<span data-ttu-id="a6d61-111">When you have set up manufacturing, you can plan and execute production orders.</span><span class="sxs-lookup"><span data-stu-id="a6d61-111">When you have set up manufacturing, you can plan and execute production orders.</span></span> <span data-ttu-id="a6d61-112">For more information, see [Planning](production-planning.md) and [Manufacturing](production-manage-manufacturing.md).</span><span class="sxs-lookup"><span data-stu-id="a6d61-112">For more information, see [Planning](production-planning.md) and [Manufacturing](production-manage-manufacturing.md).</span></span>  

 <span data-ttu-id="a6d61-113">The following table describes a sequence of tasks, with links to the topics that describe them.</span><span class="sxs-lookup"><span data-stu-id="a6d61-113">The following table describes a sequence of tasks, with links to the topics that describe them.</span></span>   

|<span data-ttu-id="a6d61-114">**To**</span><span class="sxs-lookup"><span data-stu-id="a6d61-114">**To**</span></span>|<span data-ttu-id="a6d61-115">**See**</span><span class="sxs-lookup"><span data-stu-id="a6d61-115">**See**</span></span>|  
|------------|-------------|  
|<span data-ttu-id="a6d61-116">Configure the manufacturing features, such as defining shop floor work hours and selecting planning principles.</span><span class="sxs-lookup"><span data-stu-id="a6d61-116">Configure the manufacturing features, such as defining shop floor work hours and selecting planning principles.</span></span>|<span data-ttu-id="a6d61-117">The **Manufacturing Setup** page.</span><span class="sxs-lookup"><span data-stu-id="a6d61-117">The **Manufacturing Setup** page.</span></span>|  
|<span data-ttu-id="a6d61-118">Define a standard working week in the manufacturing department in terms of starting and ending times of each work day and related work shift.</span><span class="sxs-lookup"><span data-stu-id="a6d61-118">Define a standard working week in the manufacturing department in terms of starting and ending times of each work day and related work shift.</span></span>|[<span data-ttu-id="a6d61-119">How to: Create Shop Calendars</span><span class="sxs-lookup"><span data-stu-id="a6d61-119">How to: Create Shop Calendars</span></span>](production-how-to-create-work-center-calendars.md)|  
|<span data-ttu-id="a6d61-120">Organise fixed values and requirements of production resources as work centres or machine centres to govern their output of production performed.</span><span class="sxs-lookup"><span data-stu-id="a6d61-120">Organize fixed values and requirements of production resources as work centers or machine centers to govern their output of production performed.</span></span>|[<span data-ttu-id="a6d61-121">How to: Set Up Work Centres and Machine Centres</span><span class="sxs-lookup"><span data-stu-id="a6d61-121">How to: Set Up Work Centers and Machine Centers</span></span>](production-how-to-set-up-work-and-machine-centers.md)|
|<span data-ttu-id="a6d61-122">Organise production operations in the required order and assign them to work or machine centres with the required work times.</span><span class="sxs-lookup"><span data-stu-id="a6d61-122">Organize production operations in the required order and assign them to work or machine centers with the required work times.</span></span>|[<span data-ttu-id="a6d61-123">How to: Create Routings</span><span class="sxs-lookup"><span data-stu-id="a6d61-123">How to: Create Routings</span></span>](production-how-to-create-routings.md)|
|<span data-ttu-id="a6d61-124">Organise production components or subassemblies under a produced parent item and certify the BOM for execution at work centres.</span><span class="sxs-lookup"><span data-stu-id="a6d61-124">Organize production components or subassemblies under a produced parent item and certify the BOM for execution at work centers.</span></span>|[<span data-ttu-id="a6d61-125">How to: Create Production BOMs</span><span class="sxs-lookup"><span data-stu-id="a6d61-125">How to: Create Production BOMs</span></span>](production-how-to-create-production-boms.md)|
|<span data-ttu-id="a6d61-126">Make sure that the right component quantity is available when produced items are stocked in one unit of measure but produced in another.</span><span class="sxs-lookup"><span data-stu-id="a6d61-126">Make sure that the right component quantity is available when produced items are stocked in one unit of measure but produced in another.</span></span>|[<span data-ttu-id="a6d61-127">How to: Work With Manufacturing Batch Units of Measure</span><span class="sxs-lookup"><span data-stu-id="a6d61-127">How to: Work With Manufacturing Batch Units of Measure</span></span>](production-how-to-use-the-manufacturing-batch-unit-of-measure.md)|  
|<span data-ttu-id="a6d61-128">Define families of production items with similar manufacturing processes to save consumption.</span><span class="sxs-lookup"><span data-stu-id="a6d61-128">Define families of production items with similar manufacturing processes to save consumption.</span></span> <span data-ttu-id="a6d61-129">For example, four pieces of the same item can be produced from one sheet and 10 pieces of another, different, item at the same time.</span><span class="sxs-lookup"><span data-stu-id="a6d61-129">For example, four pieces of the same item can be produced from one sheet and 10 pieces of another, different, item at the same time.</span></span>|[<span data-ttu-id="a6d61-130">How to: Work With Production Families</span><span class="sxs-lookup"><span data-stu-id="a6d61-130">How to: Work With Production Families</span></span>](production-how-work-family.md)|
|<span data-ttu-id="a6d61-131">Use standard tasks to simplify the creation of routings by quickly attaching extra information to recurring operations.</span><span class="sxs-lookup"><span data-stu-id="a6d61-131">Use standard tasks to simplify the creation of routings by quickly attaching extra information to recurring operations.</span></span>|[<span data-ttu-id="a6d61-132">How to: Set Up Standard Routing Lines</span><span class="sxs-lookup"><span data-stu-id="a6d61-132">How to: Set Up Standard Routing Lines</span></span>](production-how-set-up-standard-routing-lines.md)|  
|<span data-ttu-id="a6d61-133">Prepare work centres and routings to represent subcontracted production operations.</span><span class="sxs-lookup"><span data-stu-id="a6d61-133">Prepare work centers and routings to represent subcontracted production operations.</span></span>|[<span data-ttu-id="a6d61-134">How to: Subcontract Manufacturing</span><span class="sxs-lookup"><span data-stu-id="a6d61-134">How to: Subcontract Manufacturing</span></span>](production-how-to-subcontract-manufacturing.md)|  

## <a name="see-also"></a><span data-ttu-id="a6d61-135">See Also</span><span class="sxs-lookup"><span data-stu-id="a6d61-135">See Also</span></span>
<span data-ttu-id="a6d61-136">[Manufacturing](production-manage-manufacturing.md)  </span><span class="sxs-lookup"><span data-stu-id="a6d61-136">[Manufacturing](production-manage-manufacturing.md)  </span></span>  
<span data-ttu-id="a6d61-137">[Planning](production-planning.md) </span><span class="sxs-lookup"><span data-stu-id="a6d61-137">[Planning](production-planning.md) </span></span>  
[<span data-ttu-id="a6d61-138">Inventory</span><span class="sxs-lookup"><span data-stu-id="a6d61-138">Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="a6d61-139">Purchasing</span><span class="sxs-lookup"><span data-stu-id="a6d61-139">Purchasing</span></span>](purchasing-manage-purchasing.md)  
<span data-ttu-id="a6d61-140">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="a6d61-140">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
