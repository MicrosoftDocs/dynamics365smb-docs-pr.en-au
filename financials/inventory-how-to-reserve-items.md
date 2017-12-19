---
title: How to Reserve Items | Microsoft Docs
description: You can reserve items for sales orders, purchase orders, and production orders. You can reserve items on inventory or inbound on open document lines.
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/14/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 2c13559bb3dc44cdb61697f5135c5b931e34d2a8
ms.openlocfilehash: b03209b5681c264f7d788d3d731d32b60f1709b6
ms.contentlocale: en-au
ms.lasthandoff: 09/22/2017

---
# <a name="how-to-reserve-items"></a><span data-ttu-id="e998a-104">How to: Reserve Items</span><span class="sxs-lookup"><span data-stu-id="e998a-104">How to: Reserve Items</span></span>
<span data-ttu-id="e998a-105">You can reserve items for sales orders, purchase orders, service orders, assembly orders, and production orders.</span><span class="sxs-lookup"><span data-stu-id="e998a-105">You can reserve items for sales orders, purchase orders, service orders, assembly orders, and production orders.</span></span> <span data-ttu-id="e998a-106">You can reserve items on inventory or inbound on open document or journal lines.</span><span class="sxs-lookup"><span data-stu-id="e998a-106">You can reserve items on inventory or inbound on open document or journal lines.</span></span> <span data-ttu-id="e998a-107">You perform the work in the **Reservation** window.</span><span class="sxs-lookup"><span data-stu-id="e998a-107">You perform the work in the **Reservation** window.</span></span>

<span data-ttu-id="e998a-108">Each line in the **Reservation** window, which you open to reserve items, displays information about one type of line (sales, purchase, journal) or inventory entry.</span><span class="sxs-lookup"><span data-stu-id="e998a-108">Each line in the **Reservation** window, which you open to reserve items, displays information about one type of line (sales, purchase, journal) or inventory entry.</span></span> <span data-ttu-id="e998a-109">The lines describe how many items are available to be reserved from each type of line or entry.</span><span class="sxs-lookup"><span data-stu-id="e998a-109">The lines describe how many items are available to be reserved from each type of line or entry.</span></span>

## <a name="to-reserve-items-for-sales"></a><span data-ttu-id="e998a-110">To reserve items for sales</span><span class="sxs-lookup"><span data-stu-id="e998a-110">To reserve items for sales</span></span>
<span data-ttu-id="e998a-111">The following describes how to reserve items from a sales order.</span><span class="sxs-lookup"><span data-stu-id="e998a-111">The following describes how to reserve items from a sales order.</span></span> <span data-ttu-id="e998a-112">The steps are similar for purchase, service, and assembly orders.</span><span class="sxs-lookup"><span data-stu-id="e998a-112">The steps are similar for purchase, service, and assembly orders.</span></span>  
1.  <span data-ttu-id="e998a-113">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales Orders**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="e998a-113">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales Orders**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="e998a-114">On a sales order, on the **Lines** FastTab, choose the **Reserve** action.</span><span class="sxs-lookup"><span data-stu-id="e998a-114">On a sales order, on the **Lines** FastTab, choose the **Reserve** action.</span></span> <span data-ttu-id="e998a-115">The **Reservation** window opens.</span><span class="sxs-lookup"><span data-stu-id="e998a-115">The **Reservation** window opens.</span></span>  
3. <span data-ttu-id="e998a-116">Select the line that you want to reserve the items from.</span><span class="sxs-lookup"><span data-stu-id="e998a-116">Select the line that you want to reserve the items from.</span></span>  
4. <span data-ttu-id="e998a-117">Choose one of the following actions.</span><span class="sxs-lookup"><span data-stu-id="e998a-117">Choose one of the following actions.</span></span>  

    |<span data-ttu-id="e998a-118">**Function**</span><span class="sxs-lookup"><span data-stu-id="e998a-118">**Function**</span></span>|<span data-ttu-id="e998a-119">**Description**</span><span class="sxs-lookup"><span data-stu-id="e998a-119">**Description**</span></span>|
    |------------------|---------------------|  
    |<span data-ttu-id="e998a-120">**Auto Reserve**</span><span class="sxs-lookup"><span data-stu-id="e998a-120">**Auto Reserve**</span></span>|<span data-ttu-id="e998a-121">To automatically reserve items in the **Reservation** window.</span><span class="sxs-lookup"><span data-stu-id="e998a-121">To automatically reserve items in the **Reservation** window.</span></span>|  
    |<span data-ttu-id="e998a-122">**Reserve from Current Line**</span><span class="sxs-lookup"><span data-stu-id="e998a-122">**Reserve from Current Line**</span></span>|<span data-ttu-id="e998a-123">To reserve the items from the document on the line you have selected.</span><span class="sxs-lookup"><span data-stu-id="e998a-123">To reserve the items from the document on the line you have selected.</span></span>|  
    |<span data-ttu-id="e998a-124">**Cancel Reservation from Current Line**</span><span class="sxs-lookup"><span data-stu-id="e998a-124">**Cancel Reservation from Current Line**</span></span>|<span data-ttu-id="e998a-125">To cancel reservation of the items from the document on the line you have selected.</span><span class="sxs-lookup"><span data-stu-id="e998a-125">To cancel reservation of the items from the document on the line you have selected.</span></span>|

> [!NOTE]  
>  <span data-ttu-id="e998a-126">If item tracking lines exist for the sales order, the reservation system will take you through special steps.</span><span class="sxs-lookup"><span data-stu-id="e998a-126">If item tracking lines exist for the sales order, the reservation system will take you through special steps.</span></span> <span data-ttu-id="e998a-127">For more information, see the "To reserve a specific serial or lot number" section.</span><span class="sxs-lookup"><span data-stu-id="e998a-127">For more information, see the "To reserve a specific serial or lot number" section.</span></span>  

## <a name="to-reserve-an-item-for-a-production-order-line"></a><span data-ttu-id="e998a-128">To reserve an item for a production order line</span><span class="sxs-lookup"><span data-stu-id="e998a-128">To reserve an item for a production order line</span></span>  
<span data-ttu-id="e998a-129">You can reserve items for production orders.</span><span class="sxs-lookup"><span data-stu-id="e998a-129">You can reserve items for production orders.</span></span> <span data-ttu-id="e998a-130">You have to distinguish between production order lines, meaning the parent item, and production order components.</span><span class="sxs-lookup"><span data-stu-id="e998a-130">You have to distinguish between production order lines, meaning the parent item, and production order components.</span></span>

<span data-ttu-id="e998a-131">In the following procedure, a firm planned production order is used.</span><span class="sxs-lookup"><span data-stu-id="e998a-131">In the following procedure, a firm planned production order is used.</span></span>   
1. <span data-ttu-id="e998a-132">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Firm Planned Prod. Order**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="e998a-132">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Firm Planned Prod. Order**, and then choose the related link.</span></span>  
2. <span data-ttu-id="e998a-133">Open the firm planned production order you want to reserve parent items for.</span><span class="sxs-lookup"><span data-stu-id="e998a-133">Open the firm planned production order you want to reserve parent items for.</span></span>  
3. <span data-ttu-id="e998a-134">Select the relevant production order line.</span><span class="sxs-lookup"><span data-stu-id="e998a-134">Select the relevant production order line.</span></span>  
4. <span data-ttu-id="e998a-135">On the **Lines** FastTab, choose the **Reserve** action.</span><span class="sxs-lookup"><span data-stu-id="e998a-135">On the **Lines** FastTab, choose the **Reserve** action.</span></span>
5. <span data-ttu-id="e998a-136">In the **Reservation** window, select the **Sales Line, Order** line, and then choose the **Reserve from Current Line** action.</span><span class="sxs-lookup"><span data-stu-id="e998a-136">In the **Reservation** window, select the **Sales Line, Order** line, and then choose the **Reserve from Current Line** action.</span></span>  

<span data-ttu-id="e998a-137">The quantity you entered in the firm planned production order line is now reserved.</span><span class="sxs-lookup"><span data-stu-id="e998a-137">The quantity you entered in the firm planned production order line is now reserved.</span></span>

## <a name="to-reserve-items-for-production-order-components"></a><span data-ttu-id="e998a-138">To reserve items for production order components</span><span class="sxs-lookup"><span data-stu-id="e998a-138">To reserve items for production order components</span></span>  
<span data-ttu-id="e998a-139">You can reserve items for production orders.</span><span class="sxs-lookup"><span data-stu-id="e998a-139">You can reserve items for production orders.</span></span> <span data-ttu-id="e998a-140">You have to distinguish between production order lines, meaning the parent item, and production order components.</span><span class="sxs-lookup"><span data-stu-id="e998a-140">You have to distinguish between production order lines, meaning the parent item, and production order components.</span></span>

<span data-ttu-id="e998a-141">In the following procedure, a firm planned production order is used.</span><span class="sxs-lookup"><span data-stu-id="e998a-141">In the following procedure, a firm planned production order is used.</span></span>    
1. <span data-ttu-id="e998a-142">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Firm Planned Prod. Order**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="e998a-142">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Firm Planned Prod. Order**, and then choose the related link.</span></span>  
2. <span data-ttu-id="e998a-143">Open the firm planned production order you want to reserve component items for.</span><span class="sxs-lookup"><span data-stu-id="e998a-143">Open the firm planned production order you want to reserve component items for.</span></span>  
3. <span data-ttu-id="e998a-144">Select the relevant production order line.</span><span class="sxs-lookup"><span data-stu-id="e998a-144">Select the relevant production order line.</span></span>  
4. <span data-ttu-id="e998a-145">On the **Lines** FastTab, choose **Line**, and then choose **Components**.</span><span class="sxs-lookup"><span data-stu-id="e998a-145">On the **Lines** FastTab, choose **Line**, and then choose **Components**.</span></span>  
5. <span data-ttu-id="e998a-146">Select the relevant component line.</span><span class="sxs-lookup"><span data-stu-id="e998a-146">Select the relevant component line.</span></span>  
6. <span data-ttu-id="e998a-147">Choose On the **Lines** FastTab, choose the **Reserve** action.</span><span class="sxs-lookup"><span data-stu-id="e998a-147">Choose On the **Lines** FastTab, choose the **Reserve** action.</span></span>  
7. <span data-ttu-id="e998a-148">In the **Reservation** window, select a line, and then choose the **Reserve from Current Line** action.</span><span class="sxs-lookup"><span data-stu-id="e998a-148">In the **Reservation** window, select a line, and then choose the **Reserve from Current Line** action.</span></span>  

<span data-ttu-id="e998a-149">The quantity you entered in the firm planned production component line is now reserved.</span><span class="sxs-lookup"><span data-stu-id="e998a-149">The quantity you entered in the firm planned production component line is now reserved.</span></span>

## <a name="to-change-a-reservation"></a><span data-ttu-id="e998a-150">To change a reservation</span><span class="sxs-lookup"><span data-stu-id="e998a-150">To change a reservation</span></span>  
<span data-ttu-id="e998a-151">Sometimes, you may want to change an item reservation.</span><span class="sxs-lookup"><span data-stu-id="e998a-151">Sometimes, you may want to change an item reservation.</span></span>   
1. <span data-ttu-id="e998a-152">From the document line that you have reserved from, on the **Lines** FastTab, choose the **Reserve** action.</span><span class="sxs-lookup"><span data-stu-id="e998a-152">From the document line that you have reserved from, on the **Lines** FastTab, choose the **Reserve** action.</span></span>  
2. <span data-ttu-id="e998a-153">In the **Reservation** window, choose the **Reservation Entries** action.</span><span class="sxs-lookup"><span data-stu-id="e998a-153">In the **Reservation** window, choose the **Reservation Entries** action.</span></span>
3. <span data-ttu-id="e998a-154">The **Reservation Entries** window, update the **Quantity** field on the line you want to change.</span><span class="sxs-lookup"><span data-stu-id="e998a-154">The **Reservation Entries** window, update the **Quantity** field on the line you want to change.</span></span>
4. <span data-ttu-id="e998a-155">Confirm the subsequent message, by choosing the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="e998a-155">Confirm the subsequent message, by choosing the **OK** button.</span></span>

## <a name="to-cancel-a-reservation"></a><span data-ttu-id="e998a-156">To cancel a reservation</span><span class="sxs-lookup"><span data-stu-id="e998a-156">To cancel a reservation</span></span>  
<span data-ttu-id="e998a-157">Sometimes, you may want to cancel an item reservation.</span><span class="sxs-lookup"><span data-stu-id="e998a-157">Sometimes, you may want to cancel an item reservation.</span></span>   
1. <span data-ttu-id="e998a-158">From the document line that you want to cancel a reservation from, on the **Lines** FastTab, choose the **Reserve** action.</span><span class="sxs-lookup"><span data-stu-id="e998a-158">From the document line that you want to cancel a reservation from, on the **Lines** FastTab, choose the **Reserve** action.</span></span>  
2. <span data-ttu-id="e998a-159">In the **Reservation** window, choose **Reservation Entries** action.</span><span class="sxs-lookup"><span data-stu-id="e998a-159">In the **Reservation** window, choose **Reservation Entries** action.</span></span>  
3.  <span data-ttu-id="e998a-160">In the **Reservation Entries** window, choose the **Cancel Reservation** action.</span><span class="sxs-lookup"><span data-stu-id="e998a-160">In the **Reservation Entries** window, choose the **Cancel Reservation** action.</span></span>  
4.  <span data-ttu-id="e998a-161">Confirm the subsequent message, by choosing the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="e998a-161">Confirm the subsequent message, by choosing the **OK** button.</span></span>  

## <a name="to-reserve-a-specific-serial-or-lot-number"></a><span data-ttu-id="e998a-162">To reserve a specific serial or lot number</span><span class="sxs-lookup"><span data-stu-id="e998a-162">To reserve a specific serial or lot number</span></span>  
<span data-ttu-id="e998a-163">From outbound documents for item-tracked items, such as sales orders or production component lists, you can reserve specific serial or lot numbers.</span><span class="sxs-lookup"><span data-stu-id="e998a-163">From outbound documents for item-tracked items, such as sales orders or production component lists, you can reserve specific serial or lot numbers.</span></span> <span data-ttu-id="e998a-164">This may be relevant, for example, if you need production components from a specific lot to ensure consistency with earlier production batches, or because a customer has requested a specific serial number.</span><span class="sxs-lookup"><span data-stu-id="e998a-164">This may be relevant, for example, if you need production components from a specific lot to ensure consistency with earlier production batches, or because a customer has requested a specific serial number.</span></span> <span data-ttu-id="e998a-165">For more information, see [How to: Work with Serial and Lot Numbers](inventory-how-work-item-tracking.md).</span><span class="sxs-lookup"><span data-stu-id="e998a-165">For more information, see [How to: Work with Serial and Lot Numbers](inventory-how-work-item-tracking.md).</span></span>

<span data-ttu-id="e998a-166">This is referred to as a specific reservation, because you reserve from the quantity of  Item X that belongs to Lot X. If you simply reserve from quantities of Item X, then it is a normal, non-specific, reservation.</span><span class="sxs-lookup"><span data-stu-id="e998a-166">This is referred to as a specific reservation, because you reserve from the quantity of  Item X that belongs to Lot X. If you simply reserve from quantities of Item X, then it is a normal, non-specific, reservation.</span></span> <span data-ttu-id="e998a-167">For more information, see [Design Details - Item Tracking and Reservations](design-details-item-tracking-and-reservations.md).</span><span class="sxs-lookup"><span data-stu-id="e998a-167">For more information, see [Design Details - Item Tracking and Reservations](design-details-item-tracking-and-reservations.md).</span></span>

<span data-ttu-id="e998a-168">The following procedure is based on a sales order.</span><span class="sxs-lookup"><span data-stu-id="e998a-168">The following procedure is based on a sales order.</span></span>    
1. <span data-ttu-id="e998a-169">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales Orders**, and then select the related link.</span><span class="sxs-lookup"><span data-stu-id="e998a-169">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales Orders**, and then select the related link.</span></span>  
2. <span data-ttu-id="e998a-170">Create a sales order line for an item-tracked item.</span><span class="sxs-lookup"><span data-stu-id="e998a-170">Create a sales order line for an item-tracked item.</span></span>  
3. <span data-ttu-id="e998a-171">Assign serial and lot numbers to the sales order line.</span><span class="sxs-lookup"><span data-stu-id="e998a-171">Assign serial and lot numbers to the sales order line.</span></span> <span data-ttu-id="e998a-172">For more information, see [How to: Work with Serial and Lot Numbers](inventory-how-work-item-tracking.md).</span><span class="sxs-lookup"><span data-stu-id="e998a-172">For more information, see [How to: Work with Serial and Lot Numbers](inventory-how-work-item-tracking.md).</span></span>
4. <span data-ttu-id="e998a-173">On the sales order line, choose the **Reserve** action.</span><span class="sxs-lookup"><span data-stu-id="e998a-173">On the sales order line, choose the **Reserve** action.</span></span>  
5. <span data-ttu-id="e998a-174">Choose the **Yes** button to reserve specific serial or lot numbers.</span><span class="sxs-lookup"><span data-stu-id="e998a-174">Choose the **Yes** button to reserve specific serial or lot numbers.</span></span>  
6. <span data-ttu-id="e998a-175">In the   **Item Tracking List** window, select the serial and lot number combination that you have just assigned.</span><span class="sxs-lookup"><span data-stu-id="e998a-175">In the   **Item Tracking List** window, select the serial and lot number combination that you have just assigned.</span></span>  
7. <span data-ttu-id="e998a-176">Choose the **OK** button to open the **Reservation** window showing only supply with the specified item tracking number.</span><span class="sxs-lookup"><span data-stu-id="e998a-176">Choose the **OK** button to open the **Reservation** window showing only supply with the specified item tracking number.</span></span> <span data-ttu-id="e998a-177">If there are any non-specific reservations on any of the item tracking numbers that you have specified for this line, you are informed of the quantity that has already been reserved.</span><span class="sxs-lookup"><span data-stu-id="e998a-177">If there are any non-specific reservations on any of the item tracking numbers that you have specified for this line, you are informed of the quantity that has already been reserved.</span></span>  
8. <span data-ttu-id="e998a-178">Choose either the **Auto Reserve** or the **Reserve from Current Line** action to create the reservation on the specific item tracking numbers.</span><span class="sxs-lookup"><span data-stu-id="e998a-178">Choose either the **Auto Reserve** or the **Reserve from Current Line** action to create the reservation on the specific item tracking numbers.</span></span>

## <a name="see-also"></a><span data-ttu-id="e998a-179">See Also</span><span class="sxs-lookup"><span data-stu-id="e998a-179">See Also</span></span>
[<span data-ttu-id="e998a-180">Inventory</span><span class="sxs-lookup"><span data-stu-id="e998a-180">Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="e998a-181">Design Details: Reservation, Order Tracking, and Action Messaging</span><span class="sxs-lookup"><span data-stu-id="e998a-181">Design Details: Reservation, Order Tracking, and Action Messaging</span></span>](design-details-reservation-order-tracking-and-action-messaging.md)  
[<span data-ttu-id="e998a-182">Design Details - Item Tracking and Reservations</span><span class="sxs-lookup"><span data-stu-id="e998a-182">Design Details - Item Tracking and Reservations</span></span>](design-details-item-tracking-and-reservations.md)  
[<span data-ttu-id="e998a-183">How to: Work with Serial and Lot Numbers</span><span class="sxs-lookup"><span data-stu-id="e998a-183">How to: Work with Serial and Lot Numbers</span></span>](inventory-how-work-item-tracking.md)  
<span data-ttu-id="e998a-184">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="e998a-184">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
