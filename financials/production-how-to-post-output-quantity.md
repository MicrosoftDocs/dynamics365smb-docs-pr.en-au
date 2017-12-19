---
title: How to Batch Post Production Output and Run Times| Microsoft Docs
description: The output quantity represents the work progress in the form of the finished quantity.
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 2c13559bb3dc44cdb61697f5135c5b931e34d2a8
ms.openlocfilehash: ee5ee5d08804439a79f8029eaa25ab7547349a1b
ms.contentlocale: en-au
ms.lasthandoff: 09/22/2017

---
# <a name="how-to-batch-post-output-and-run-times"></a><span data-ttu-id="92ebd-103">How to: Batch Post Output and Run Times</span><span class="sxs-lookup"><span data-stu-id="92ebd-103">How to: Batch Post Output and Run Times</span></span>
<span data-ttu-id="92ebd-104">The output quantity represents the work progress in the form of the finished quantity.</span><span class="sxs-lookup"><span data-stu-id="92ebd-104">The output quantity represents the work progress in the form of the finished quantity.</span></span>  

> [!NOTE]
> <span data-ttu-id="92ebd-105">Only when you post output quantity on the last operation, the inventory is updated automatically.</span><span class="sxs-lookup"><span data-stu-id="92ebd-105">Only when you post output quantity on the last operation, the inventory is updated automatically.</span></span>  

## <a name="to-post-output-quantities-for-one-or-more-production-order-lines"></a><span data-ttu-id="92ebd-106">To post output quantities for one or more production order lines</span><span class="sxs-lookup"><span data-stu-id="92ebd-106">To post output quantities for one or more production order lines</span></span>
1. <span data-ttu-id="92ebd-107">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Output Journal**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="92ebd-107">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Output Journal**, and then choose the related link.</span></span>  
2. <span data-ttu-id="92ebd-108">Fill in the fields with the production order data and the output data.</span><span class="sxs-lookup"><span data-stu-id="92ebd-108">Fill in the fields with the production order data and the output data.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. <span data-ttu-id="92ebd-109">If the operation has been completed, select the **Finished** field.</span><span class="sxs-lookup"><span data-stu-id="92ebd-109">If the operation has been completed, select the **Finished** field.</span></span>  

    <span data-ttu-id="92ebd-110">If the warehouse location where the items should be put away uses bins but does not require put-away processing,  assign a bin code to the journal line to specify where the items should be placed in the warehouse.</span><span class="sxs-lookup"><span data-stu-id="92ebd-110">If the warehouse location where the items should be put away uses bins but does not require put-away processing,  assign a bin code to the journal line to specify where the items should be placed in the warehouse.</span></span> <span data-ttu-id="92ebd-111">For more information, see [How to: Put Away Production or Assembly Output](warehouse-how-to-put-away-production-output.md).</span><span class="sxs-lookup"><span data-stu-id="92ebd-111">For more information, see [How to: Put Away Production or Assembly Output](warehouse-how-to-put-away-production-output.md).</span></span>  

4. <span data-ttu-id="92ebd-112">Choose the **Post** acto post the operations.</span><span class="sxs-lookup"><span data-stu-id="92ebd-112">Choose the **Post** acto post the operations.</span></span> <span data-ttu-id="92ebd-113">The output quantity will be posted.</span><span class="sxs-lookup"><span data-stu-id="92ebd-113">The output quantity will be posted.</span></span> <span data-ttu-id="92ebd-114">The item is now available for shipping.</span><span class="sxs-lookup"><span data-stu-id="92ebd-114">The item is now available for shipping.</span></span>  

## <a name="to-post-run-times-for-one-or-more-production-order-lines"></a><span data-ttu-id="92ebd-115">To post run times for one or more production order lines</span><span class="sxs-lookup"><span data-stu-id="92ebd-115">To post run times for one or more production order lines</span></span>
<span data-ttu-id="92ebd-116">The run time represents work progress in the form of the necessary working time.</span><span class="sxs-lookup"><span data-stu-id="92ebd-116">The run time represents work progress in the form of the necessary working time.</span></span>    

1.  <span data-ttu-id="92ebd-117">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Output Journal**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="92ebd-117">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Output Journal**, and then choose the related link.</span></span>  
2. <span data-ttu-id="92ebd-118">Fill in the fields with the production order data and the output data.</span><span class="sxs-lookup"><span data-stu-id="92ebd-118">Fill in the fields with the production order data and the output data.</span></span>  
3.  <span data-ttu-id="92ebd-119">If the operation is completed, select the **Finished** field.</span><span class="sxs-lookup"><span data-stu-id="92ebd-119">If the operation is completed, select the **Finished** field.</span></span>  
4. <span data-ttu-id="92ebd-120">Choose the **Post** action to post the time spent per operation.</span><span class="sxs-lookup"><span data-stu-id="92ebd-120">Choose the **Post** action to post the time spent per operation.</span></span> <span data-ttu-id="92ebd-121">Capacity ledger entries are updated for the used work or machine centres.</span><span class="sxs-lookup"><span data-stu-id="92ebd-121">Capacity ledger entries are updated for the used work or machine centers.</span></span>

## <a name="see-also"></a><span data-ttu-id="92ebd-122">See Also</span><span class="sxs-lookup"><span data-stu-id="92ebd-122">See Also</span></span>  
<span data-ttu-id="92ebd-123">[Manufacturing](production-manage-manufacturing.md)  </span><span class="sxs-lookup"><span data-stu-id="92ebd-123">[Manufacturing](production-manage-manufacturing.md)  </span></span>  
[<span data-ttu-id="92ebd-124">Setting Up Manufacturing</span><span class="sxs-lookup"><span data-stu-id="92ebd-124">Setting Up Manufacturing</span></span>](production-configure-production-processes.md)  
<span data-ttu-id="92ebd-125">[Planning](production-planning.md)    </span><span class="sxs-lookup"><span data-stu-id="92ebd-125">[Planning](production-planning.md)    </span></span>  
[<span data-ttu-id="92ebd-126">Inventory</span><span class="sxs-lookup"><span data-stu-id="92ebd-126">Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="92ebd-127">Purchasing</span><span class="sxs-lookup"><span data-stu-id="92ebd-127">Purchasing</span></span>](purchasing-manage-purchasing.md)  
<span data-ttu-id="92ebd-128">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="92ebd-128">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
