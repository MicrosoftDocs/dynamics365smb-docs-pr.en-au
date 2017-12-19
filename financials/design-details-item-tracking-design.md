---
title: Design Details - Item Tracking Design | Microsoft Docs
description: This topic describes the design behind item tracking in Dynamics 365.
author: SorenGP
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: design, item, tracking, tracing
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: aa56764b5f3210229ad21eae6891fb201462209c
ms.openlocfilehash: 20d04536d670e0c830ed3b92df8d570e6408fab4
ms.contentlocale: en-au
ms.lasthandoff: 12/14/2017

---
# <a name="design-details-item-tracking-design"></a><span data-ttu-id="be988-103">Design Details: Item Tracking Design</span><span class="sxs-lookup"><span data-stu-id="be988-103">Design Details: Item Tracking Design</span></span>
<span data-ttu-id="be988-104">In the first version of Item Tracking in [!INCLUDE[d365fin](includes/d365fin_md.md)] 2.60, serial numbers or lot numbers were recorded directly on item ledger entries.</span><span class="sxs-lookup"><span data-stu-id="be988-104">In the first version of Item Tracking in [!INCLUDE[d365fin](includes/d365fin_md.md)] 2.60, serial numbers or lot numbers were recorded directly on item ledger entries.</span></span> <span data-ttu-id="be988-105">This design provided full availability information and simple tracking of historic entries, but it lacked flexibility and functionality.</span><span class="sxs-lookup"><span data-stu-id="be988-105">This design provided full availability information and simple tracking of historic entries, but it lacked flexibility and functionality.</span></span>  

<span data-ttu-id="be988-106">From [!INCLUDE[d365fin](includes/d365fin_md.md)] 3.00, item tracking functionality was in a separate object structure with intricate links to posted documents and item ledger entries.</span><span class="sxs-lookup"><span data-stu-id="be988-106">From [!INCLUDE[d365fin](includes/d365fin_md.md)] 3.00, item tracking functionality was in a separate object structure with intricate links to posted documents and item ledger entries.</span></span> <span data-ttu-id="be988-107">This design was flexible and rich in functionality, but item tracking entries were not fully involved in availability calculations.</span><span class="sxs-lookup"><span data-stu-id="be988-107">This design was flexible and rich in functionality, but item tracking entries were not fully involved in availability calculations.</span></span>  

<span data-ttu-id="be988-108">Since [!INCLUDE[d365fin](includes/d365fin_md.md)] 3.60, item tracking functionality is integrated with the reservation system, which handles reservation, order tracking, and action messaging.</span><span class="sxs-lookup"><span data-stu-id="be988-108">Since [!INCLUDE[d365fin](includes/d365fin_md.md)] 3.60, item tracking functionality is integrated with the reservation system, which handles reservation, order tracking, and action messaging.</span></span> <span data-ttu-id="be988-109">For more information, see “Design Details: Reservation, Order Tracking, and Action Messaging” in “Design Details: Supply Planning”.</span><span class="sxs-lookup"><span data-stu-id="be988-109">For more information, see “Design Details: Reservation, Order Tracking, and Action Messaging” in “Design Details: Supply Planning”.</span></span>  

<span data-ttu-id="be988-110">This latest design incorporates item tracking entries in total availability calculations throughout the system, including planning, manufacturing, and warehousing.</span><span class="sxs-lookup"><span data-stu-id="be988-110">This latest design incorporates item tracking entries in total availability calculations throughout the system, including planning, manufacturing, and warehousing.</span></span> <span data-ttu-id="be988-111">The old concept of carrying serial and lot numbers on the item ledger entries is reintroduced to ensure simple access to historical data for item tracking purposes.</span><span class="sxs-lookup"><span data-stu-id="be988-111">The old concept of carrying serial and lot numbers on the item ledger entries is reintroduced to ensure simple access to historical data for item tracking purposes.</span></span> <span data-ttu-id="be988-112">In connection with item tracking improvements in [!INCLUDE[d365fin](includes/d365fin_md.md)] 3.60, the reservation system was expanded to non-order network entities, such as journals, invoices, and CR/Adj notes.</span><span class="sxs-lookup"><span data-stu-id="be988-112">In connection with item tracking improvements in [!INCLUDE[d365fin](includes/d365fin_md.md)] 3.60, the reservation system was expanded to non-order network entities, such as journals, invoices, and credit memos.</span></span>  

<span data-ttu-id="be988-113">With the addition of serial or lot numbers, the reservation system handles permanent item attributes while also handling intermittent links between supply and demand in the form of order tracking entries and reservation entries.</span><span class="sxs-lookup"><span data-stu-id="be988-113">With the addition of serial or lot numbers, the reservation system handles permanent item attributes while also handling intermittent links between supply and demand in the form of order tracking entries and reservation entries.</span></span> <span data-ttu-id="be988-114">Another different characteristic of serial or lot numbers compared to the conventional reservation data is the fact that they can be posted, either partially or fully.</span><span class="sxs-lookup"><span data-stu-id="be988-114">Another different characteristic of serial or lot numbers compared to the conventional reservation data is the fact that they can be posted, either partially or fully.</span></span> <span data-ttu-id="be988-115">Therefore, the **Reservation Entry** table (T337) now works with a related table, the **Tracking Specification** table (T336), which manages and displays summing across active and posted item tracking quantities.</span><span class="sxs-lookup"><span data-stu-id="be988-115">Therefore, the **Reservation Entry** table (T337) now works with a related table, the **Tracking Specification** table (T336), which manages and displays summing across active and posted item tracking quantities.</span></span> <span data-ttu-id="be988-116">For more information, see [Design Details: Active versus Historic Item Tracking Entries](design-details-active-versus-historic-item-tracking-entries.md).</span><span class="sxs-lookup"><span data-stu-id="be988-116">For more information, see [Design Details: Active versus Historic Item Tracking Entries](design-details-active-versus-historic-item-tracking-entries.md).</span></span>  

<span data-ttu-id="be988-117">The following diagram outlines the design of item tracking functionality in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="be988-117">The following diagram outlines the design of item tracking functionality in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>  

<span data-ttu-id="be988-118">![Item tracking design](media/design_details_item_tracking_design.png "design_details_item_tracking_design")</span><span class="sxs-lookup"><span data-stu-id="be988-118">![Item tracking design](media/design_details_item_tracking_design.png "design_details_item_tracking_design")</span></span>  

<span data-ttu-id="be988-119">The central posting object is redesigned to handle the unique subclassification of a document line in the form of serial or lot numbers, and special relation tables are added to create the one-to-many relations between posted documents and their split item ledger entries and value ledger entries.</span><span class="sxs-lookup"><span data-stu-id="be988-119">The central posting object is redesigned to handle the unique subclassification of a document line in the form of serial or lot numbers, and special relation tables are added to create the one-to-many relations between posted documents and their split item ledger entries and value ledger entries.</span></span>  

<span data-ttu-id="be988-120">Codeunit 22, **Item Jnl. – Post Line**, now splits the posting according to the item tracking numbers that are specified on the document line.</span><span class="sxs-lookup"><span data-stu-id="be988-120">Codeunit 22, **Item Jnl. – Post Line**, now splits the posting according to the item tracking numbers that are specified on the document line.</span></span> <span data-ttu-id="be988-121">Each unique item tracking number on the line creates its own item ledger entry for the item.</span><span class="sxs-lookup"><span data-stu-id="be988-121">Each unique item tracking number on the line creates its own item ledger entry for the item.</span></span> <span data-ttu-id="be988-122">This means that the link from the posted document line to the associated item ledger entries is now a one-to-many relation.</span><span class="sxs-lookup"><span data-stu-id="be988-122">This means that the link from the posted document line to the associated item ledger entries is now a one-to-many relation.</span></span> <span data-ttu-id="be988-123">This relation is handled by the following item tracking relation tables.</span><span class="sxs-lookup"><span data-stu-id="be988-123">This relation is handled by the following item tracking relation tables.</span></span>  

|<span data-ttu-id="be988-124">Field</span><span class="sxs-lookup"><span data-stu-id="be988-124">Field</span></span>|<span data-ttu-id="be988-125">Description</span><span class="sxs-lookup"><span data-stu-id="be988-125">Description</span></span>|  
|---------------|---------------------------------------|  
|<span data-ttu-id="be988-126">**Item Entry Relation** (T6507)</span><span class="sxs-lookup"><span data-stu-id="be988-126">**Item Entry Relation** (T6507)</span></span>|<span data-ttu-id="be988-127">Relates shipped or received lines to item ledger entries</span><span class="sxs-lookup"><span data-stu-id="be988-127">Relates shipped or received lines to item ledger entries</span></span>|  
|<span data-ttu-id="be988-128">**Value Entry Relation** (T6508)</span><span class="sxs-lookup"><span data-stu-id="be988-128">**Value Entry Relation** (T6508)</span></span>|<span data-ttu-id="be988-129">Relates invoiced lines to value entries</span><span class="sxs-lookup"><span data-stu-id="be988-129">Relates invoiced lines to value entries</span></span>|  

<span data-ttu-id="be988-130">For more information, see [Design Details: Item Tracking Posting Structure](design-details-item-tracking-posting-structure.md).</span><span class="sxs-lookup"><span data-stu-id="be988-130">For more information, see [Design Details: Item Tracking Posting Structure](design-details-item-tracking-posting-structure.md).</span></span>  

## <a name="see-also"></a><span data-ttu-id="be988-131">See Also</span><span class="sxs-lookup"><span data-stu-id="be988-131">See Also</span></span>  
[<span data-ttu-id="be988-132">Design Details: Item Tracking</span><span class="sxs-lookup"><span data-stu-id="be988-132">Design Details: Item Tracking</span></span>](design-details-item-tracking.md)
