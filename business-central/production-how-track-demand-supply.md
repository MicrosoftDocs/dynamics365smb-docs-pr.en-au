---
title: How to Track Relations Between Demand and Supply | Microsoft Docs
description: From any supply or demand document in the so-called order network, you can track the order demand (tracked quantity), forecast, blanket sales order, or planning parameter (untracked quantity) that has given rise to the planning line in question.
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: ''
ms.date: 10/01/2020
ms.author: edupont
ms.openlocfilehash: 3d053de6193593256e404803d61b14f4681dc771
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 10/01/2020
ms.locfileid: "3921546"
---
# <a name="track-relations-between-demand-and-supply"></a><span data-ttu-id="015a7-103">Track Relations Between Demand and Supply</span><span class="sxs-lookup"><span data-stu-id="015a7-103">Track Relations Between Demand and Supply</span></span>
<span data-ttu-id="015a7-104">From any supply or demand document in the so-called order network, you can track the order demand (tracked quantity), forecast, blanket sales order, or planning parameter (untracked quantity) that has given rise to the planning line in question.</span><span class="sxs-lookup"><span data-stu-id="015a7-104">From any supply or demand document in the so-called order network, you can track the order demand (tracked quantity), forecast, blanket sales order, or planning parameter (untracked quantity) that has given rise to the planning line in question.</span></span>

<span data-ttu-id="015a7-105">The planning worksheets also offers supporting planning information about non-order entities to help the planner obtain an optimal supply plan.</span><span class="sxs-lookup"><span data-stu-id="015a7-105">The planning worksheets also offers supporting planning information about non-order entities to help the planner obtain an optimal supply plan.</span></span> <span data-ttu-id="015a7-106">For more information, see [Untracked Planning Elements](production-how-track-demand-supply.md#untracked-planning-elements).</span><span class="sxs-lookup"><span data-stu-id="015a7-106">For more information, see [Untracked Planning Elements](production-how-track-demand-supply.md#untracked-planning-elements).</span></span>

## <a name="to-track-linked-items"></a><span data-ttu-id="015a7-107">To track linked items</span><span class="sxs-lookup"><span data-stu-id="015a7-107">To track linked items</span></span>
<span data-ttu-id="015a7-108">Order tracking shows how sales orders, production orders, and purchase orders are related to the manufacturing order through the planning and reservation systems.</span><span class="sxs-lookup"><span data-stu-id="015a7-108">Order tracking shows how sales orders, production orders, and purchase orders are related to the manufacturing order through the planning and reservation systems.</span></span>

<span data-ttu-id="015a7-109">The following describes how to track linked items on a firm planned production order.</span><span class="sxs-lookup"><span data-stu-id="015a7-109">The following describes how to track linked items on a firm planned production order.</span></span> <span data-ttu-id="015a7-110">The steps are similar for all other order types, and from planning worksheet lines.</span><span class="sxs-lookup"><span data-stu-id="015a7-110">The steps are similar for all other order types, and from planning worksheet lines.</span></span>

1. <span data-ttu-id="015a7-111">Choose the ![Lightbulb that opens the Tell Me feature](media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Firm Planned Prod. Order** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="015a7-111">Choose the ![Lightbulb that opens the Tell Me feature](media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Firm Planned Prod. Order** , and then choose the related link.</span></span>
2. <span data-ttu-id="015a7-112">Open the relevant firm planned production order from the list.</span><span class="sxs-lookup"><span data-stu-id="015a7-112">Open the relevant firm planned production order from the list.</span></span>
3. <span data-ttu-id="015a7-113">On the **Lines** FastTab, choose the **Functions** action, and then choose the **Order Tracking** action.</span><span class="sxs-lookup"><span data-stu-id="015a7-113">On the **Lines** FastTab, choose the **Functions** action, and then choose the **Order Tracking** action.</span></span>

<span data-ttu-id="015a7-114">The lines in the **Order Tracking** display the documents that are related to the current production order line.</span><span class="sxs-lookup"><span data-stu-id="015a7-114">The lines in the **Order Tracking** display the documents that are related to the current production order line.</span></span>

## <a name="untracked-planning-elements"></a><span data-ttu-id="015a7-115">Untracked Planning Elements</span><span class="sxs-lookup"><span data-stu-id="015a7-115">Untracked Planning Elements</span></span>
<span data-ttu-id="015a7-116">The **Untracked Planning Elements** page opens when you choose the **Untracked Qty.** field on the **order Planning** page.</span><span class="sxs-lookup"><span data-stu-id="015a7-116">The **Untracked Planning Elements** page opens when you choose the **Untracked Qty.** field on the **order Planning** page.</span></span> <span data-ttu-id="015a7-117">It serves two purposes:</span><span class="sxs-lookup"><span data-stu-id="015a7-117">It serves two purposes:</span></span>

1. <span data-ttu-id="015a7-118">To hold information about untracked quantities displayed when the user looks up from the Order Tracking page to see untracked quantities.</span><span class="sxs-lookup"><span data-stu-id="015a7-118">To hold information about untracked quantities displayed when the user looks up from the Order Tracking page to see untracked quantities.</span></span>
2. <span data-ttu-id="015a7-119">To hold warning messages displayed when the user chooses the **Warning** icon on the **Planning Worksheet** page.</span><span class="sxs-lookup"><span data-stu-id="015a7-119">To hold warning messages displayed when the user chooses the **Warning** icon on the **Planning Worksheet** page.</span></span>

<span data-ttu-id="015a7-120">The page contains entries which account for an untracked surplus quantity in order tracking network.</span><span class="sxs-lookup"><span data-stu-id="015a7-120">The page contains entries which account for an untracked surplus quantity in order tracking network.</span></span> <span data-ttu-id="015a7-121">These entries are generated during the planning run and explain where the untracked surplus quantity in the order tracking lines came from.</span><span class="sxs-lookup"><span data-stu-id="015a7-121">These entries are generated during the planning run and explain where the untracked surplus quantity in the order tracking lines came from.</span></span> <span data-ttu-id="015a7-122">This untracked surplus can come from:</span><span class="sxs-lookup"><span data-stu-id="015a7-122">This untracked surplus can come from:</span></span>

- <span data-ttu-id="015a7-123">Production forecast</span><span class="sxs-lookup"><span data-stu-id="015a7-123">Production forecast</span></span>
- <span data-ttu-id="015a7-124">Blanket orders</span><span class="sxs-lookup"><span data-stu-id="015a7-124">Blanket orders</span></span>
- <span data-ttu-id="015a7-125">Safety stock quantity</span><span class="sxs-lookup"><span data-stu-id="015a7-125">Safety stock quantity</span></span>
- <span data-ttu-id="015a7-126">Reorder point</span><span class="sxs-lookup"><span data-stu-id="015a7-126">Reorder point</span></span>
- <span data-ttu-id="015a7-127">Maximum inventory</span><span class="sxs-lookup"><span data-stu-id="015a7-127">Maximum inventory</span></span>
- <span data-ttu-id="015a7-128">Reorder quantity</span><span class="sxs-lookup"><span data-stu-id="015a7-128">Reorder quantity</span></span>
- <span data-ttu-id="015a7-129">Maximum order quantity</span><span class="sxs-lookup"><span data-stu-id="015a7-129">Maximum order quantity</span></span>
- <span data-ttu-id="015a7-130">Minimum order quantity</span><span class="sxs-lookup"><span data-stu-id="015a7-130">Minimum order quantity</span></span>
- <span data-ttu-id="015a7-131">Order multiple</span><span class="sxs-lookup"><span data-stu-id="015a7-131">Order multiple</span></span>
- <span data-ttu-id="015a7-132">Dampener (% of lot size)</span><span class="sxs-lookup"><span data-stu-id="015a7-132">Dampener (% of lot size)</span></span>

## <a name="see-also"></a><span data-ttu-id="015a7-133">See Also</span><span class="sxs-lookup"><span data-stu-id="015a7-133">See Also</span></span>  
<span data-ttu-id="015a7-134">[Planning](production-planning.md) </span><span class="sxs-lookup"><span data-stu-id="015a7-134">[Planning](production-planning.md) </span></span>  
[<span data-ttu-id="015a7-135">Setting Up Manufacturing</span><span class="sxs-lookup"><span data-stu-id="015a7-135">Setting Up Manufacturing</span></span>](production-configure-production-processes.md)  
<span data-ttu-id="015a7-136">[Manufacturing](production-manage-manufacturing.md)  </span><span class="sxs-lookup"><span data-stu-id="015a7-136">[Manufacturing](production-manage-manufacturing.md)  </span></span>  
[<span data-ttu-id="015a7-137">Inventory</span><span class="sxs-lookup"><span data-stu-id="015a7-137">Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="015a7-138">Purchasing</span><span class="sxs-lookup"><span data-stu-id="015a7-138">Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="015a7-139">Design Details: Reservation, Tracking, and Action Messaging</span><span class="sxs-lookup"><span data-stu-id="015a7-139">Design Details: Reservation, Tracking, and Action Messaging</span></span>](design-details-reservation-order-tracking-and-action-messaging.md)  
<span data-ttu-id="015a7-140">[Design Details: Supply Planning](design-details-supply-planning.md) </span><span class="sxs-lookup"><span data-stu-id="015a7-140">[Design Details: Supply Planning](design-details-supply-planning.md) </span></span>  
[<span data-ttu-id="015a7-141">Setup Best Practices: Supply Planning</span><span class="sxs-lookup"><span data-stu-id="015a7-141">Setup Best Practices: Supply Planning</span></span>](setup-best-practices-supply-planning.md)  
<span data-ttu-id="015a7-142">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="015a7-142">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
