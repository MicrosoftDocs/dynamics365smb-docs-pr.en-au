---
title: How to Move Items Ad Hoc in Basic Warehouse Configurations | Microsoft Docs
description: You may occasionally need to move items between internal bins, not receiving or shipping bins, without a specific demand from a source document. You may perform these ad hoc movements, for example, to reorganise the warehouse, to bring items to an inspection area, or to move additional items to and from a production area without a system relation to the production order source document.
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/16/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 2c13559bb3dc44cdb61697f5135c5b931e34d2a8
ms.openlocfilehash: 38361c04f4ede35afd20e1fe84128fcdbfe104d0
ms.contentlocale: en-au
ms.lasthandoff: 09/22/2017

---
# <a name="how-to-move-items-ad-hoc-in-basic-warehouse-configurations"></a><span data-ttu-id="f7a4c-104">How to: Move Items Ad Hoc in Basic Warehouse Configurations</span><span class="sxs-lookup"><span data-stu-id="f7a4c-104">How to: Move Items Ad Hoc in Basic Warehouse Configurations</span></span>
<span data-ttu-id="f7a4c-105">You may occasionally need to move items between internal bins, not receiving or shipping bins, without a specific demand from a source document.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-105">You may occasionally need to move items between internal bins, not receiving or shipping bins, without a specific demand from a source document.</span></span> <span data-ttu-id="f7a4c-106">You may perform these ad hoc movements, for example, to reorganise the warehouse, to bring items to an inspection area, or to move additional items to and from a production area without a system relation to the production order source document.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-106">You may perform these ad hoc movements, for example, to reorganize the warehouse, to bring items to an inspection area, or to move additional items to and from a production area without a system relation to the production order source document.</span></span>  

<span data-ttu-id="f7a4c-107">In basic warehouse configurations, that is locations that use the **Bin Mandatory** setup field and possibly the **Require Pick** and the **Require Put-away** setup fields, you can register ad hoc movements without source documents in the following ways:</span><span class="sxs-lookup"><span data-stu-id="f7a4c-107">In basic warehouse configurations, that is locations that use the **Bin Mandatory** setup field and possibly the **Require Pick** and the **Require Put-away** setup fields, you can register ad hoc movements without source documents in the following ways:</span></span>  

    - <span data-ttu-id="f7a4c-108">With the **Internal Movement** window.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-108">With the **Internal Movement** window.</span></span>  
    - <span data-ttu-id="f7a4c-109">With the **Item Reclassification Journal** window.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-109">With the **Item Reclassification Journal** window.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="f7a4c-110">In advanced warehouse configurations, that is locations that use the **Directed Put-away and Pick** setup field, you use the **Movement Worksheet** window or the **Internal Whse. Pick** or the **Internal Whse. Put-away** windows to move items ad hoc between bins.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-110">In advanced warehouse configurations, that is locations that use the **Directed Put-away and Pick** setup field, you use the **Movement Worksheet** window or the **Internal Whse. Pick** or the **Internal Whse. Put-away** windows to move items ad hoc between bins.</span></span>  

## <a name="to-move-items-as-an-internal-movement"></a><span data-ttu-id="f7a4c-111">To move items as an internal movement</span><span class="sxs-lookup"><span data-stu-id="f7a4c-111">To move items as an internal movement</span></span>  
1.  <span data-ttu-id="f7a4c-112">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Internal Movement**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-112">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Internal Movement**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="f7a4c-113">On the **General** FastTab, fill in the **No.**</span><span class="sxs-lookup"><span data-stu-id="f7a4c-113">On the **General** FastTab, fill in the **No.**</span></span> <span data-ttu-id="f7a4c-114">field, either by leaving the field or by choosing the **AssistEdit** button to select from the number series.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-114">field, either by leaving the field or by choosing the **AssistEdit** button to select from the number series.</span></span>  
3.  <span data-ttu-id="f7a4c-115">In the **Location Code** field, enter the location where the movement takes place.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-115">In the **Location Code** field, enter the location where the movement takes place.</span></span>  

    <span data-ttu-id="f7a4c-116">If the location is set up as your default location as a warehouse employee, the location code is inserted automatically.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-116">If the location is set up as your default location as a warehouse employee, the location code is inserted automatically.</span></span>  
4.  <span data-ttu-id="f7a4c-117">In the **To Bin Code** field, enter a code for the bin that you want to move the item to.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-117">In the **To Bin Code** field, enter a code for the bin that you want to move the item to.</span></span> <span data-ttu-id="f7a4c-118">For production purposes, this could be the open shop floor bin code, for example, as defined on the location card or work centre.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-118">For production purposes, this could be the open shop floor bin code, for example, as defined on the location card or work center.</span></span>  
5.  <span data-ttu-id="f7a4c-119">In the **Due Date** field, enter the date by which the movement must be completed.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-119">In the **Due Date** field, enter the date by which the movement must be completed.</span></span>  
6.  <span data-ttu-id="f7a4c-120">On the **Lines** FastTab, choose the **Item No.** field to open the **Bin Contents List** window, and then select the item to move based on its availability in bins. Alternatively, choose the **Get Bin Contents** action to fill the internal movement lines based on your filters.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-120">On the **Lines** FastTab, choose the **Item No.** field to open the **Bin Contents List** window, and then select the item to move based on its availability in bins. Alternatively, choose the **Get Bin Contents** action to fill the internal movement lines based on your filters.</span></span> <span data-ttu-id="f7a4c-121">For more information, see the tooltip for the **Get Bin Content** action.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-121">For more information, see the tooltip for the **Get Bin Content** action.</span></span>   

    <span data-ttu-id="f7a4c-122">When you have selected the item, the **From Bin Code** field is automatically filled according to the selected bin content, but you can change it to any other bin where the item is available.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-122">When you have selected the item, the **From Bin Code** field is automatically filled according to the selected bin content, but you can change it to any other bin where the item is available.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="f7a4c-123">Because the **Item No.** field and the **From Bin Code** field are connected, their values may change interdependently when you edit either field.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-123">Because the **Item No.** field and the **From Bin Code** field are connected, their values may change interdependently when you edit either field.</span></span>  

    <span data-ttu-id="f7a4c-124">The **To Bin Code** field is filled with the value you entered on the header, but you can change it on the line to any other bin code that isn’t blocked or dedicated to special purposes.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-124">The **To Bin Code** field is filled with the value you entered on the header, but you can change it on the line to any other bin code that isn’t blocked or dedicated to special purposes.</span></span> <span data-ttu-id="f7a4c-125">For more information about making bins dedicated, see Dedicated.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-125">For more information about making bins dedicated, see Dedicated.</span></span>  
7.  <span data-ttu-id="f7a4c-126">When you have defined which bins you want to move the item from and to, enter the quantity to move in the **Quantity** field.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-126">When you have defined which bins you want to move the item from and to, enter the quantity to move in the **Quantity** field.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="f7a4c-127">Quantity must be available in the From Bin code.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-127">Quantity must be available in the From Bin code.</span></span>  

8.  <span data-ttu-id="f7a4c-128">When you are ready to process the internal movement, choose the **Create Inventory Movement** action.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-128">When you are ready to process the internal movement, choose the **Create Inventory Movement** action.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="f7a4c-129">When you have created the inventory movement, the internal movement lines are deleted.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-129">When you have created the inventory movement, the internal movement lines are deleted.</span></span>  

    <span data-ttu-id="f7a4c-130">You perform the remainder of the ad hoc movement in the **Inventory Movement** window in the same way as you would for a movement based on source documents.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-130">You perform the remainder of the ad hoc movement in the **Inventory Movement** window in the same way as you would for a movement based on source documents.</span></span> <span data-ttu-id="f7a4c-131">For more information, see for example [How to: Move Components to an Operation Area in Basic Warehouse Configurations](warehouse-how-to-move-components-to-an-operation-area-in-basic-warehousing.md)</span><span class="sxs-lookup"><span data-stu-id="f7a4c-131">For more information, see for example [How to: Move Components to an Operation Area in Basic Warehouse Configurations](warehouse-how-to-move-components-to-an-operation-area-in-basic-warehousing.md)</span></span>  

## <a name="to-move-items-with-the-item-reclassification-journal"></a><span data-ttu-id="f7a4c-132">To move items with the item reclassification journal</span><span class="sxs-lookup"><span data-stu-id="f7a4c-132">To move items with the item reclassification journal</span></span>
<span data-ttu-id="f7a4c-133">In stead of using warehouse movement documents, you can record the moving of items by reclassifying their bin codes.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-133">In stead of using warehouse movement documents, you can record the moving of items by reclassifying their bin codes.</span></span> <span data-ttu-id="f7a4c-134">For more information, see [How to: Count, Adjust, and Reclassify Inventory](inventory-how-count-adjust-reclassify.md).</span><span class="sxs-lookup"><span data-stu-id="f7a4c-134">For more information, see [How to: Count, Adjust, and Reclassify Inventory](inventory-how-count-adjust-reclassify.md).</span></span>   
1.  <span data-ttu-id="f7a4c-135">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Item Reclass. Journal**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-135">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Item Reclass. Journal**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="f7a4c-136">On each journal line, define the bins from which and to which you want to move items by filling in the **Bin Code** and the **New Bin Code** fields.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-136">On each journal line, define the bins from which and to which you want to move items by filling in the **Bin Code** and the **New Bin Code** fields.</span></span>  

    1.  <span data-ttu-id="f7a4c-137">To move a bin's entire contents to another bin, choose the **Get Bin Contents** action.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-137">To move a bin's entire contents to another bin, choose the **Get Bin Contents** action.</span></span>  
    2.  <span data-ttu-id="f7a4c-138">Fill in the filters to find the bin whose contents you would like to move and then choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-138">Fill in the filters to find the bin whose contents you would like to move and then choose the **OK** button.</span></span> <span data-ttu-id="f7a4c-139">The journal lines are filled with the contents of the bin.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-139">The journal lines are filled with the contents of the bin.</span></span>  
3.  <span data-ttu-id="f7a4c-140">Fill in the remaining fields on each journal line.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-140">Fill in the remaining fields on each journal line.</span></span>   
4.  <span data-ttu-id="f7a4c-141">Post the reclassification journal.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-141">Post the reclassification journal.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="f7a4c-142">Unlike with movement documents, a movement posted with the reclassification journal does not create a warehouse request to perform the physical task.</span><span class="sxs-lookup"><span data-stu-id="f7a4c-142">Unlike with movement documents, a movement posted with the reclassification journal does not create a warehouse request to perform the physical task.</span></span>  

## <a name="see-also"></a><span data-ttu-id="f7a4c-143">See Also</span><span class="sxs-lookup"><span data-stu-id="f7a4c-143">See Also</span></span>  
[<span data-ttu-id="f7a4c-144">Warehouse Management</span><span class="sxs-lookup"><span data-stu-id="f7a4c-144">Warehouse Management</span></span>](warehouse-manage-warehouse.md)  
[<span data-ttu-id="f7a4c-145">Inventory</span><span class="sxs-lookup"><span data-stu-id="f7a4c-145">Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="f7a4c-146">[Setting Up Warehouse Management](warehouse-setup-warehouse.md)   </span><span class="sxs-lookup"><span data-stu-id="f7a4c-146">[Setting Up Warehouse Management](warehouse-setup-warehouse.md)   </span></span>  
<span data-ttu-id="f7a4c-147">[Assembly Management](assembly-assemble-items.md)  </span><span class="sxs-lookup"><span data-stu-id="f7a4c-147">[Assembly Management](assembly-assemble-items.md)  </span></span>  
[<span data-ttu-id="f7a4c-148">Design Details: Warehouse Management</span><span class="sxs-lookup"><span data-stu-id="f7a4c-148">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)  
<span data-ttu-id="f7a4c-149">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="f7a4c-149">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
