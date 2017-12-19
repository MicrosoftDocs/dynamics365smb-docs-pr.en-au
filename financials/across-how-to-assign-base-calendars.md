---
title: How to Set Up Base Calendars | Microsoft Docs
description: "You can assign a base calendar to your company and its business partners, such as customers, vendors, or locations. Delivery and receipt dates on future sales order, purchase order, transfer order, and production order lines are calculated according to the calendar’s specified working days."
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
ms.openlocfilehash: d37170cabe2b03200e3d3f5f7b5c2a679eb8f46c
ms.contentlocale: en-au
ms.lasthandoff: 09/22/2017

---
# <a name="how-to-set-up-base-calendars"></a><span data-ttu-id="56cf9-104">How to: Set Up Base Calendars</span><span class="sxs-lookup"><span data-stu-id="56cf9-104">How to: Set Up Base Calendars</span></span>
<span data-ttu-id="56cf9-105">You can assign a base calendar to your company and its business partners, such as customers, vendors, or locations.</span><span class="sxs-lookup"><span data-stu-id="56cf9-105">You can assign a base calendar to your company and its business partners, such as customers, vendors, or locations.</span></span> <span data-ttu-id="56cf9-106">Delivery and receipt dates on future sales order, purchase order, transfer order, and production order lines are calculated according to the calendar’s specified working days.</span><span class="sxs-lookup"><span data-stu-id="56cf9-106">Delivery and receipt dates on future sales order, purchase order, transfer order, and production order lines are calculated according to the calendar’s specified working days.</span></span> <span data-ttu-id="56cf9-107">The main task in setting up a new base calendar is to specify and define the non-working days that you want to apply.</span><span class="sxs-lookup"><span data-stu-id="56cf9-107">The main task in setting up a new base calendar is to specify and define the non-working days that you want to apply.</span></span>  

## <a name="to-set-up-a-base-calendar"></a><span data-ttu-id="56cf9-108">To set up a base calendar</span><span class="sxs-lookup"><span data-stu-id="56cf9-108">To set up a base calendar</span></span>  
1.  <span data-ttu-id="56cf9-109">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Base Calendar**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="56cf9-109">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Base Calendar**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="56cf9-110">Choose the **New** action.</span><span class="sxs-lookup"><span data-stu-id="56cf9-110">Choose the **New** action.</span></span>  
3.  <span data-ttu-id="56cf9-111">Fill in the **Code** field.</span><span class="sxs-lookup"><span data-stu-id="56cf9-111">Fill in the **Code** field.</span></span>  
4. <span data-ttu-id="56cf9-112">Choose the **Maintain Base Calendar Changes** action.</span><span class="sxs-lookup"><span data-stu-id="56cf9-112">Choose the **Maintain Base Calendar Changes** action.</span></span>
5. <span data-ttu-id="56cf9-113">In the **Base Calendar Changes** window, use the **Recurring System** field to mark a particular date or day as a recurring nonworking day.</span><span class="sxs-lookup"><span data-stu-id="56cf9-113">In the **Base Calendar Changes** window, use the **Recurring System** field to mark a particular date or day as a recurring nonworking day.</span></span> <span data-ttu-id="56cf9-114">You can select either the **Annual Recurring** or **Weekly Recurring** option.</span><span class="sxs-lookup"><span data-stu-id="56cf9-114">You can select either the **Annual Recurring** or **Weekly Recurring** option.</span></span>  

    <span data-ttu-id="56cf9-115">If you select **Annual Recurring**, you must also enter the relevant date in the **Date** field.</span><span class="sxs-lookup"><span data-stu-id="56cf9-115">If you select **Annual Recurring**, you must also enter the relevant date in the **Date** field.</span></span>  

    <span data-ttu-id="56cf9-116">If you select **Weekly Recurring**, you must also select the relevant day of the week in the **Day** field.</span><span class="sxs-lookup"><span data-stu-id="56cf9-116">If you select **Weekly Recurring**, you must also select the relevant day of the week in the **Day** field.</span></span> <span data-ttu-id="56cf9-117">If you leave the field empty, you must fill in the **Date** field.</span><span class="sxs-lookup"><span data-stu-id="56cf9-117">If you leave the field empty, you must fill in the **Date** field.</span></span> <span data-ttu-id="56cf9-118">The **Day** field is filled in automatically.</span><span class="sxs-lookup"><span data-stu-id="56cf9-118">The **Day** field is filled in automatically.</span></span>  

<span data-ttu-id="56cf9-119">When you make an entry, the **Nonworking** field is selected.</span><span class="sxs-lookup"><span data-stu-id="56cf9-119">When you make an entry, the **Nonworking** field is selected.</span></span> <span data-ttu-id="56cf9-120">You can choose to clear the check mark to make it a working day.</span><span class="sxs-lookup"><span data-stu-id="56cf9-120">You can choose to clear the check mark to make it a working day.</span></span>  
 <span data-ttu-id="56cf9-121">When you return to the base calendar card, you will observe that the nonworking day entries that you made have been updated.</span><span class="sxs-lookup"><span data-stu-id="56cf9-121">When you return to the base calendar card, you will observe that the nonworking day entries that you made have been updated.</span></span> <span data-ttu-id="56cf9-122">These entries now appear in red and the **Nonworking** field is selected.</span><span class="sxs-lookup"><span data-stu-id="56cf9-122">These entries now appear in red and the **Nonworking** field is selected.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="56cf9-123">When setting up a new base calendar, you can select and copy lines from an existing calendar.</span><span class="sxs-lookup"><span data-stu-id="56cf9-123">When setting up a new base calendar, you can select and copy lines from an existing calendar.</span></span> <span data-ttu-id="56cf9-124">You do this in the relevant **Base Calendar Changes** window.</span><span class="sxs-lookup"><span data-stu-id="56cf9-124">You do this in the relevant **Base Calendar Changes** window.</span></span>  

> [!IMPORTANT]  
>  <span data-ttu-id="56cf9-125">Any base calendar defined for the vendor or the location affects how the dates are calculated and rounded to working days.</span><span class="sxs-lookup"><span data-stu-id="56cf9-125">Any base calendar defined for the vendor or the location affects how the dates are calculated and rounded to working days.</span></span>
<span data-ttu-id="56cf9-126">Specifies a date formula for the time that it takes to replenish the item.</span><span class="sxs-lookup"><span data-stu-id="56cf9-126">Specifies a date formula for the time that it takes to replenish the item.</span></span> <span data-ttu-id="56cf9-127">It is used to calculate the **Planned Receipt Date** field, if calculating forward, and **Order Date** field, if calculating backwards.</span><span class="sxs-lookup"><span data-stu-id="56cf9-127">It is used to calculate the **Planned Receipt Date** field, if calculating forward, and **Order Date** field, if calculating backwards.</span></span> <span data-ttu-id="56cf9-128">See the "Lead Time Calculation" section.</span><span class="sxs-lookup"><span data-stu-id="56cf9-128">See the "Lead Time Calculation" section.</span></span>

## <a name="lead-time-calculation"></a><span data-ttu-id="56cf9-129">Lead Time Calculation</span><span class="sxs-lookup"><span data-stu-id="56cf9-129">Lead Time Calculation</span></span>
<span data-ttu-id="56cf9-130">Any base calendar defined for the vendor or the location affects how the dates are calculated and rounded to working days.</span><span class="sxs-lookup"><span data-stu-id="56cf9-130">Any base calendar defined for the vendor or the location affects how the dates are calculated and rounded to working days.</span></span> <span data-ttu-id="56cf9-131">Accordingly, the two date fields on purchase order lines are calculated as follows under different conditions.</span><span class="sxs-lookup"><span data-stu-id="56cf9-131">Accordingly, the two date fields on purchase order lines are calculated as follows under different conditions.</span></span>

|<span data-ttu-id="56cf9-132">Calculation Direction</span><span class="sxs-lookup"><span data-stu-id="56cf9-132">Calculation Direction</span></span>|<span data-ttu-id="56cf9-133">Vendor Calendar Defined</span><span class="sxs-lookup"><span data-stu-id="56cf9-133">Vendor Calendar Defined</span></span>|<span data-ttu-id="56cf9-134">Vendor Calendar Not Defined</span><span class="sxs-lookup"><span data-stu-id="56cf9-134">Vendor Calendar Not Defined</span></span>|
|---------------------|-----------------------|---------------------------|
|<span data-ttu-id="56cf9-135">Forward</span><span class="sxs-lookup"><span data-stu-id="56cf9-135">Forward</span></span>|<span data-ttu-id="56cf9-136">planned receipt date = order date + vendor lead time (per the vendor calendar and rounded to the next working day in first the vendor calendar and then the location calendar)</span><span class="sxs-lookup"><span data-stu-id="56cf9-136">planned receipt date = order date + vendor lead time (per the vendor calendar and rounded to the next working day in first the vendor calendar and then the location calendar)</span></span>|<span data-ttu-id="56cf9-137">planned receipt date = order date + vendor lead time (per the location calendar)</span><span class="sxs-lookup"><span data-stu-id="56cf9-137">planned receipt date = order date + vendor lead time (per the location calendar)</span></span>|
|<span data-ttu-id="56cf9-138">Backward</span><span class="sxs-lookup"><span data-stu-id="56cf9-138">Backward</span></span>|<span data-ttu-id="56cf9-139">order date = planned receipt date - vendor lead time (per the vendor calendar and rounded to the previous working day in first the vendor calendar and then the location calendar)</span><span class="sxs-lookup"><span data-stu-id="56cf9-139">order date = planned receipt date - vendor lead time (per the vendor calendar and rounded to the previous working day in first the vendor calendar and then the location calendar)</span></span>|<span data-ttu-id="56cf9-140">order date = planned receipt date - vendor lead time (per the location calendar)</span><span class="sxs-lookup"><span data-stu-id="56cf9-140">order date = planned receipt date - vendor lead time (per the location calendar)</span></span>|

> [!NOTE]
> <span data-ttu-id="56cf9-141">In addition to the lead time calculation that affects the planned receipt date and order date, as shown in the above table, warehouse handling time and safety lead time may be added to the formulas to make up the value in the **Expected Receipt Date** field, as follows: Planned Receipt Date + Safety Lead Time + Inbound Warehouse Handling Time = Expected Receipt Date.</span><span class="sxs-lookup"><span data-stu-id="56cf9-141">In addition to the lead time calculation that affects the planned receipt date and order date, as shown in the above table, warehouse handling time and safety lead time may be added to the formulas to make up the value in the **Expected Receipt Date** field, as follows: Planned Receipt Date + Safety Lead Time + Inbound Warehouse Handling Time = Expected Receipt Date.</span></span>

> [!Important]
> <span data-ttu-id="56cf9-142">If your location uses a significantly different calendar than your vendors do, then it is important that you set up specific calendars for those vendors, to calculate optimal vendor lead times.</span><span class="sxs-lookup"><span data-stu-id="56cf9-142">If your location uses a significantly different calendar than your vendors do, then it is important that you set up specific calendars for those vendors, to calculate optimal vendor lead times.</span></span> <span data-ttu-id="56cf9-143">For information about how to set up vendor calendars, see the "To assign a base calendar" section.</span><span class="sxs-lookup"><span data-stu-id="56cf9-143">For information about how to set up vendor calendars, see the "To assign a base calendar" section.</span></span>

<span data-ttu-id="56cf9-144">The contents of the **Lead Time Calculation** field is copied from either the item card or the SKU card, if the lead time is defined for the item, or in the **Item Vendor Catalogue** window, if the lead time is defined for the vendor.</span><span class="sxs-lookup"><span data-stu-id="56cf9-144">The contents of the **Lead Time Calculation** field is copied from either the item card or the SKU card, if the lead time is defined for the item, or in the **Item Vendor Catalog** window, if the lead time is defined for the vendor.</span></span>

## <a name="to-customize-a-calendar"></a><span data-ttu-id="56cf9-145">To customise a calendar</span><span class="sxs-lookup"><span data-stu-id="56cf9-145">To customize a calendar</span></span>
<span data-ttu-id="56cf9-146">The main task in customising a base calendar for your company, or one of its business partners, is to enter any changes to working and nonworking day status.</span><span class="sxs-lookup"><span data-stu-id="56cf9-146">The main task in customizing a base calendar for your company, or one of its business partners, is to enter any changes to working and nonworking day status.</span></span>

<span data-ttu-id="56cf9-147">For example, while a base calendar would typically list all Saturdays as non-working days, the customised calendar for a particular location may list all Saturdays during the months of November and December, and leading up to the holiday season, as working days.</span><span class="sxs-lookup"><span data-stu-id="56cf9-147">For example, while a base calendar would typically list all Saturdays as non-working days, the customized calendar for a particular location may list all Saturdays during the months of November and December, and leading up to the holiday season, as working days.</span></span>

<span data-ttu-id="56cf9-148">The following procedure uses the case of the location as an example.</span><span class="sxs-lookup"><span data-stu-id="56cf9-148">The following procedure uses the case of the location as an example.</span></span> <span data-ttu-id="56cf9-149">Note that at this point, you have already assigned a base calendar to the location.</span><span class="sxs-lookup"><span data-stu-id="56cf9-149">Note that at this point, you have already assigned a base calendar to the location.</span></span>

1. <span data-ttu-id="56cf9-150">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Locations**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="56cf9-150">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Locations**, and then choose the related link.</span></span>
2. <span data-ttu-id="56cf9-151">Open the location that you want to update, and then select the **Customised Calendar** field.</span><span class="sxs-lookup"><span data-stu-id="56cf9-151">Open the location that you want to update, and then select the **Customized Calendar** field.</span></span> <span data-ttu-id="56cf9-152">Note that a calendar must be selected in the **Base Calendar Code** field.</span><span class="sxs-lookup"><span data-stu-id="56cf9-152">Note that a calendar must be selected in the **Base Calendar Code** field.</span></span>
3. <span data-ttu-id="56cf9-153">In the **Customised Calendar Entries** window opens, choose the **Maintain Customised Calendar Changes** action.</span><span class="sxs-lookup"><span data-stu-id="56cf9-153">In the **Customized Calendar Entries** window opens, choose the **Maintain Customized Calendar Changes** action.</span></span>
4. <span data-ttu-id="56cf9-154">In the **Customised Calendar Changes**, add lines for customised calendar entries.</span><span class="sxs-lookup"><span data-stu-id="56cf9-154">In the **Customized Calendar Changes**, add lines for customized calendar entries.</span></span>

    <span data-ttu-id="56cf9-155">When you enter a line, the **Nonworking** check box is selected.</span><span class="sxs-lookup"><span data-stu-id="56cf9-155">When you enter a line, the **Nonworking** check box is selected.</span></span> <span data-ttu-id="56cf9-156">You can clear the check box if you want to change the status to a working day.</span><span class="sxs-lookup"><span data-stu-id="56cf9-156">You can clear the check box if you want to change the status to a working day.</span></span>

    <span data-ttu-id="56cf9-157">You can use the **Recurring System** field to set a particular date or day as a recurring nonworking day.</span><span class="sxs-lookup"><span data-stu-id="56cf9-157">You can use the **Recurring System** field to set a particular date or day as a recurring nonworking day.</span></span> <span data-ttu-id="56cf9-158">You can select either the **Annual Recurring** or **Weekly Recurring** option.</span><span class="sxs-lookup"><span data-stu-id="56cf9-158">You can select either the **Annual Recurring** or **Weekly Recurring** option.</span></span>

    <span data-ttu-id="56cf9-159">If you select **Annual Recurring**, you must also enter the relevant date in the **Date** field.</span><span class="sxs-lookup"><span data-stu-id="56cf9-159">If you select **Annual Recurring**, you must also enter the relevant date in the **Date** field.</span></span> <span data-ttu-id="56cf9-160">If you select **Weekly Recurring**, you must also select the relevant day of the week in the **Day** field.</span><span class="sxs-lookup"><span data-stu-id="56cf9-160">If you select **Weekly Recurring**, you must also select the relevant day of the week in the **Day** field.</span></span> <span data-ttu-id="56cf9-161">If you leave the field empty, you must fill in the **Date** field.</span><span class="sxs-lookup"><span data-stu-id="56cf9-161">If you leave the field empty, you must fill in the **Date** field.</span></span> <span data-ttu-id="56cf9-162">The **Day** field is then filled in automatically.</span><span class="sxs-lookup"><span data-stu-id="56cf9-162">The **Day** field is then filled in automatically.</span></span> <span data-ttu-id="56cf9-163">This could be useful if you want to mark an individual date as a nonworking or working day.</span><span class="sxs-lookup"><span data-stu-id="56cf9-163">This could be useful if you want to mark an individual date as a nonworking or working day.</span></span>

5. <span data-ttu-id="56cf9-164">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="56cf9-164">Choose the **OK** button.</span></span>

<span data-ttu-id="56cf9-165">In the **Customised Calendar Entries** window, you will observe that the date entries are updated with the changes that you made.</span><span class="sxs-lookup"><span data-stu-id="56cf9-165">In the **Customized Calendar Entries** window, you will observe that the date entries are updated with the changes that you made.</span></span>

<span data-ttu-id="56cf9-166">On the Location card, you will observe that the **Customised Calendar** field contains **Yes**, indicating that a customised calendar has been set up.</span><span class="sxs-lookup"><span data-stu-id="56cf9-166">On the Location card, you will observe that the **Customized Calendar** field contains **Yes**, indicating that a customized calendar has been set up.</span></span>

> [!Important]
> <span data-ttu-id="56cf9-167">If you do not fill in the **Location Code** field on an order line, your company’s calendar is used.</span><span class="sxs-lookup"><span data-stu-id="56cf9-167">If you do not fill in the **Location Code** field on an order line, your company’s calendar is used.</span></span>


<span data-ttu-id="56cf9-168">If you do not fill in the **Shipping Agent Code** field on the order line, your company’s calendar is used.</span><span class="sxs-lookup"><span data-stu-id="56cf9-168">If you do not fill in the **Shipping Agent Code** field on the order line, your company’s calendar is used.</span></span>

> [!NOTE]  
> <span data-ttu-id="56cf9-169">If you make changes to a base calendar for which customised calendar changes exist, all existing customised calendars are updated automatically.</span><span class="sxs-lookup"><span data-stu-id="56cf9-169">If you make changes to a base calendar for which customized calendar changes exist, all existing customized calendars are updated automatically.</span></span>

## <a name="to-assign-a-base-calendar"></a><span data-ttu-id="56cf9-170">To assign a base calendar</span><span class="sxs-lookup"><span data-stu-id="56cf9-170">To assign a base calendar</span></span>  
<span data-ttu-id="56cf9-171">The following procedure schedules delivery dates on sales order lines for a customer as an example.</span><span class="sxs-lookup"><span data-stu-id="56cf9-171">The following procedure schedules delivery dates on sales order lines for a customer as an example.</span></span>

<span data-ttu-id="56cf9-172">Base calendars are assigned to your own company, customers, vendors, locations, and shipping agents as follows:</span><span class="sxs-lookup"><span data-stu-id="56cf9-172">Base calendars are assigned to your own company, customers, vendors, locations, and shipping agents as follows:</span></span>  

-   <span data-ttu-id="56cf9-173">On the **Company Information** and **Customer** cards, the base calendar is assigned on the **Shipping** FastTab.</span><span class="sxs-lookup"><span data-stu-id="56cf9-173">On the **Company Information** and **Customer** cards, the base calendar is assigned on the **Shipping** FastTab.</span></span>  
-   <span data-ttu-id="56cf9-174">On the **Vendor** card, the base calendar is assigned on the **Receiving** FastTab.</span><span class="sxs-lookup"><span data-stu-id="56cf9-174">On the **Vendor** card, the base calendar is assigned on the **Receiving** FastTab.</span></span>  
-   <span data-ttu-id="56cf9-175">On the **Location** card, the base calendar is assigned on the **Warehouse** FastTab.</span><span class="sxs-lookup"><span data-stu-id="56cf9-175">On the **Location** card, the base calendar is assigned on the **Warehouse** FastTab.</span></span>  
-   <span data-ttu-id="56cf9-176">In the **Shipping Agents** window, the base calendar is assigned in the **Shipping Agent Services** window.</span><span class="sxs-lookup"><span data-stu-id="56cf9-176">In the **Shipping Agents** window, the base calendar is assigned in the **Shipping Agent Services** window.</span></span>  

1.  <span data-ttu-id="56cf9-177">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Customers**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="56cf9-177">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Customers**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="56cf9-178">Open the **Customer** card for whom you will assign a base calendar.</span><span class="sxs-lookup"><span data-stu-id="56cf9-178">Open the **Customer** card for whom you will assign a base calendar.</span></span>  
3.  <span data-ttu-id="56cf9-179">On the **Shipping** FastTab, in the **Base Calendar Code** field, select the base calendar that you want to assign.</span><span class="sxs-lookup"><span data-stu-id="56cf9-179">On the **Shipping** FastTab, in the **Base Calendar Code** field, select the base calendar that you want to assign.</span></span>  

> [!IMPORTANT]  
>  -   <span data-ttu-id="56cf9-180">If you do not assign a base calendar to a company, all dates are calculated as working days.</span><span class="sxs-lookup"><span data-stu-id="56cf9-180">If you do not assign a base calendar to a company, all dates are calculated as working days.</span></span>  
> -   <span data-ttu-id="56cf9-181">If you enter a blank location on an order line, all dates are calculated as working days.</span><span class="sxs-lookup"><span data-stu-id="56cf9-181">If you enter a blank location on an order line, all dates are calculated as working days.</span></span>  
> -   <span data-ttu-id="56cf9-182">Any base calendar defined for the vendor or the location affects how the dates are calculated and rounded to working days.</span><span class="sxs-lookup"><span data-stu-id="56cf9-182">Any base calendar defined for the vendor or the location affects how the dates are calculated and rounded to working days.</span></span>

> [!NOTE]  
>  <span data-ttu-id="56cf9-183">Before you can make customised calendar entries, you must first assign a base calendar to the company.</span><span class="sxs-lookup"><span data-stu-id="56cf9-183">Before you can make customized calendar entries, you must first assign a base calendar to the company.</span></span>  

## <a name="see-also"></a><span data-ttu-id="56cf9-184">See Also</span><span class="sxs-lookup"><span data-stu-id="56cf9-184">See Also</span></span>
[<span data-ttu-id="56cf9-185">Purchasing</span><span class="sxs-lookup"><span data-stu-id="56cf9-185">Purchasing</span></span>](purchasing-manage-purchasing.md)  
<span data-ttu-id="56cf9-186">[Manufacturing](production-manage-manufacturing.md)  </span><span class="sxs-lookup"><span data-stu-id="56cf9-186">[Manufacturing](production-manage-manufacturing.md)  </span></span>  
[<span data-ttu-id="56cf9-187">Inventory</span><span class="sxs-lookup"><span data-stu-id="56cf9-187">Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="56cf9-188">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="56cf9-188">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
