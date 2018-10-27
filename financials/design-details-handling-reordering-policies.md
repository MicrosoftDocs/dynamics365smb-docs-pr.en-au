---
title: Design Details - Handling Reordering Policies | Microsoft Docs
description: Overview of tasks for defining a reorder policy in supply planning.
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
ms.sourcegitcommit: cce3a3a8331d8f1ac6665d9b9a9908b172cfecaa
ms.openlocfilehash: 2a6658508f8e12a11989d54da6d6c8e3a36631cc
ms.contentlocale: en-au
ms.lasthandoff: 10/27/2018

---
# <a name="design-details-handling-reordering-policies"></a><span data-ttu-id="69f82-103">Design Details: Handling Reordering Policies</span><span class="sxs-lookup"><span data-stu-id="69f82-103">Design Details: Handling Reordering Policies</span></span>
<span data-ttu-id="69f82-104">For an item to participate in supply planning, a reorder policy must be defined.</span><span class="sxs-lookup"><span data-stu-id="69f82-104">For an item to participate in supply planning, a reorder policy must be defined.</span></span> <span data-ttu-id="69f82-105">The following four reordering policies exist:</span><span class="sxs-lookup"><span data-stu-id="69f82-105">The following four reordering policies exist:</span></span>  
  
* <span data-ttu-id="69f82-106">Fixed Reorder Qty.</span><span class="sxs-lookup"><span data-stu-id="69f82-106">Fixed Reorder Qty.</span></span>  
* <span data-ttu-id="69f82-107">Maximum Qty.</span><span class="sxs-lookup"><span data-stu-id="69f82-107">Maximum Qty.</span></span>  
* <span data-ttu-id="69f82-108">Order</span><span class="sxs-lookup"><span data-stu-id="69f82-108">Order</span></span>  
* <span data-ttu-id="69f82-109">Lot-for-Lot</span><span class="sxs-lookup"><span data-stu-id="69f82-109">Lot-for-Lot</span></span>  
  
<span data-ttu-id="69f82-110">Fixed Reorder Qty. and Maximum Qty. policies relate to inventory planning.</span><span class="sxs-lookup"><span data-stu-id="69f82-110">Fixed Reorder Qty. and Maximum Qty. policies relate to inventory planning.</span></span> <span data-ttu-id="69f82-111">Although inventory planning is technically simpler than the balancing procedure, these policies must coexist with the step-by-step balancing of supply and order tracking.</span><span class="sxs-lookup"><span data-stu-id="69f82-111">Although inventory planning is technically simpler than the balancing procedure, these policies must coexist with the step-by-step balancing of supply and order tracking.</span></span> <span data-ttu-id="69f82-112">To control the integration between the two, and to provide visibility into the involved planning logic, strict principles govern how reordering policies are handled.</span><span class="sxs-lookup"><span data-stu-id="69f82-112">To control the integration between the two, and to provide visibility into the involved planning logic, strict principles govern how reordering policies are handled.</span></span>  
  
## <a name="in-this-section"></a><span data-ttu-id="69f82-113">In This Section</span><span class="sxs-lookup"><span data-stu-id="69f82-113">In This Section</span></span>  
[<span data-ttu-id="69f82-114">Design Details: The Role of the Reorder Point</span><span class="sxs-lookup"><span data-stu-id="69f82-114">Design Details: The Role of the Reorder Point</span></span>](design-details-the-role-of-the-reorder-point.md)  
[<span data-ttu-id="69f82-115">Design Details: Monitoring the Projected Inventory Level and the Reorder Point</span><span class="sxs-lookup"><span data-stu-id="69f82-115">Design Details: Monitoring the Projected Inventory Level and the Reorder Point</span></span>](design-details-monitoring-the-projected-inventory-level-and-the-reorder-point.md)  
[<span data-ttu-id="69f82-116">Design Details: The Role of the Time Bucket</span><span class="sxs-lookup"><span data-stu-id="69f82-116">Design Details: The Role of the Time Bucket</span></span>](design-details-the-role-of-the-time-bucket.md)  
[<span data-ttu-id="69f82-117">Design Details: Staying under the Overflow Level</span><span class="sxs-lookup"><span data-stu-id="69f82-117">Design Details: Staying under the Overflow Level</span></span>](design-details-staying-under-the-overflow-level.md)  
[<span data-ttu-id="69f82-118">Design Details: Handling Projected Negative Inventory</span><span class="sxs-lookup"><span data-stu-id="69f82-118">Design Details: Handling Projected Negative Inventory</span></span>](design-details-handling-projected-negative-inventory.md)  
[<span data-ttu-id="69f82-119">Design Details: Reordering Policies</span><span class="sxs-lookup"><span data-stu-id="69f82-119">Design Details: Reordering Policies</span></span>](design-details-reordering-policies.md)  
  
## <a name="see-also"></a><span data-ttu-id="69f82-120">See Also</span><span class="sxs-lookup"><span data-stu-id="69f82-120">See Also</span></span>  
<span data-ttu-id="69f82-121">[Design Details: Planning Parameters](design-details-planning-parameters.md) </span><span class="sxs-lookup"><span data-stu-id="69f82-121">[Design Details: Planning Parameters](design-details-planning-parameters.md) </span></span>  
<span data-ttu-id="69f82-122">[Design Details: Planning Assignment Table](design-details-planning-assignment-table.md) </span><span class="sxs-lookup"><span data-stu-id="69f82-122">[Design Details: Planning Assignment Table](design-details-planning-assignment-table.md) </span></span>  
<span data-ttu-id="69f82-123">[Design Details: Central Concepts of the Planning System](design-details-central-concepts-of-the-planning-system.md) </span><span class="sxs-lookup"><span data-stu-id="69f82-123">[Design Details: Central Concepts of the Planning System](design-details-central-concepts-of-the-planning-system.md) </span></span>  
<span data-ttu-id="69f82-124">[Design Details: Balancing Demand and Supply](design-details-balancing-demand-and-supply.md) </span><span class="sxs-lookup"><span data-stu-id="69f82-124">[Design Details: Balancing Demand and Supply](design-details-balancing-demand-and-supply.md) </span></span>  
[<span data-ttu-id="69f82-125">Design Details: Supply Planning</span><span class="sxs-lookup"><span data-stu-id="69f82-125">Design Details: Supply Planning</span></span>](design-details-supply-planning.md)
