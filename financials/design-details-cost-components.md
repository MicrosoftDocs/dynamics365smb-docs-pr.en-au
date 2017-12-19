---
title: Design Details - Cost Components | Microsoft Docs
description: Cost components are different types of costs that make up the value of an inventory increase or decrease.
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
ms.sourcegitcommit: 2c13559bb3dc44cdb61697f5135c5b931e34d2a8
ms.openlocfilehash: 0a134142bfcb11692ed6157e873fcfa2900b9222
ms.contentlocale: en-au
ms.lasthandoff: 09/22/2017

---
# <a name="design-details-cost-components"></a><span data-ttu-id="27b83-103">Design Details: Cost Components</span><span class="sxs-lookup"><span data-stu-id="27b83-103">Design Details: Cost Components</span></span>
<span data-ttu-id="27b83-104">Cost components are different types of costs that make up the value of an inventory increase or decrease.</span><span class="sxs-lookup"><span data-stu-id="27b83-104">Cost components are different types of costs that make up the value of an inventory increase or decrease.</span></span>  

 <span data-ttu-id="27b83-105">The following table shows the different cost components and any subordinate cost components that they consist of.</span><span class="sxs-lookup"><span data-stu-id="27b83-105">The following table shows the different cost components and any subordinate cost components that they consist of.</span></span>  

|<span data-ttu-id="27b83-106">Cost Component</span><span class="sxs-lookup"><span data-stu-id="27b83-106">Cost Component</span></span>|<span data-ttu-id="27b83-107">Subordinate Cost Component</span><span class="sxs-lookup"><span data-stu-id="27b83-107">Subordinate Cost Component</span></span>|<span data-ttu-id="27b83-108">Description</span><span class="sxs-lookup"><span data-stu-id="27b83-108">Description</span></span>|  
|--------------------|--------------------------------|---------------------------------------|  
|<span data-ttu-id="27b83-109">Direct cost</span><span class="sxs-lookup"><span data-stu-id="27b83-109">Direct cost</span></span>|<span data-ttu-id="27b83-110">Unit cost (direct purchase price)</span><span class="sxs-lookup"><span data-stu-id="27b83-110">Unit cost (direct purchase price)</span></span>|<span data-ttu-id="27b83-111">Cost that can be traced to a cost object.</span><span class="sxs-lookup"><span data-stu-id="27b83-111">Cost that can be traced to a cost object.</span></span>|  
|<span data-ttu-id="27b83-112">Direct cost</span><span class="sxs-lookup"><span data-stu-id="27b83-112">Direct cost</span></span>|<span data-ttu-id="27b83-113">Freight cost (item charge)</span><span class="sxs-lookup"><span data-stu-id="27b83-113">Freight cost (item charge)</span></span>|<span data-ttu-id="27b83-114">Cost that can be traced to a cost object.</span><span class="sxs-lookup"><span data-stu-id="27b83-114">Cost that can be traced to a cost object.</span></span>|  
|<span data-ttu-id="27b83-115">Direct cost</span><span class="sxs-lookup"><span data-stu-id="27b83-115">Direct cost</span></span>|<span data-ttu-id="27b83-116">Insurance cost (item charge)</span><span class="sxs-lookup"><span data-stu-id="27b83-116">Insurance cost (item charge)</span></span>|<span data-ttu-id="27b83-117">Cost that can be traced to a cost object.</span><span class="sxs-lookup"><span data-stu-id="27b83-117">Cost that can be traced to a cost object.</span></span>|  
|<span data-ttu-id="27b83-118">Indirect cost</span><span class="sxs-lookup"><span data-stu-id="27b83-118">Indirect cost</span></span>||<span data-ttu-id="27b83-119">Cost that cannot be traced to a cost object.</span><span class="sxs-lookup"><span data-stu-id="27b83-119">Cost that cannot be traced to a cost object.</span></span>|  
|<span data-ttu-id="27b83-120">Variance</span><span class="sxs-lookup"><span data-stu-id="27b83-120">Variance</span></span>|<span data-ttu-id="27b83-121">Purchase variance</span><span class="sxs-lookup"><span data-stu-id="27b83-121">Purchase variance</span></span>|<span data-ttu-id="27b83-122">The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.</span><span class="sxs-lookup"><span data-stu-id="27b83-122">The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.</span></span>|  
|<span data-ttu-id="27b83-123">Variance</span><span class="sxs-lookup"><span data-stu-id="27b83-123">Variance</span></span>|<span data-ttu-id="27b83-124">Material variance</span><span class="sxs-lookup"><span data-stu-id="27b83-124">Material variance</span></span>|<span data-ttu-id="27b83-125">The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.</span><span class="sxs-lookup"><span data-stu-id="27b83-125">The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.</span></span>|  
|<span data-ttu-id="27b83-126">Variance</span><span class="sxs-lookup"><span data-stu-id="27b83-126">Variance</span></span>|<span data-ttu-id="27b83-127">Capacity variance</span><span class="sxs-lookup"><span data-stu-id="27b83-127">Capacity variance</span></span>|<span data-ttu-id="27b83-128">The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.</span><span class="sxs-lookup"><span data-stu-id="27b83-128">The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.</span></span>|  
|<span data-ttu-id="27b83-129">Variance</span><span class="sxs-lookup"><span data-stu-id="27b83-129">Variance</span></span>|<span data-ttu-id="27b83-130">Subcontracted variance</span><span class="sxs-lookup"><span data-stu-id="27b83-130">Subcontracted variance</span></span>|<span data-ttu-id="27b83-131">The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.</span><span class="sxs-lookup"><span data-stu-id="27b83-131">The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.</span></span>|  
|<span data-ttu-id="27b83-132">Variance</span><span class="sxs-lookup"><span data-stu-id="27b83-132">Variance</span></span>|<span data-ttu-id="27b83-133">Capacity overhead variance</span><span class="sxs-lookup"><span data-stu-id="27b83-133">Capacity overhead variance</span></span>|<span data-ttu-id="27b83-134">The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.</span><span class="sxs-lookup"><span data-stu-id="27b83-134">The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.</span></span>|  
|<span data-ttu-id="27b83-135">Variance</span><span class="sxs-lookup"><span data-stu-id="27b83-135">Variance</span></span>|<span data-ttu-id="27b83-136">Manufacturing overhead variance</span><span class="sxs-lookup"><span data-stu-id="27b83-136">Manufacturing overhead variance</span></span>|<span data-ttu-id="27b83-137">The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.</span><span class="sxs-lookup"><span data-stu-id="27b83-137">The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.</span></span>|  
|<span data-ttu-id="27b83-138">Revaluation</span><span class="sxs-lookup"><span data-stu-id="27b83-138">Revaluation</span></span>||<span data-ttu-id="27b83-139">A depreciation or appreciation of the current inventory value.</span><span class="sxs-lookup"><span data-stu-id="27b83-139">A depreciation or appreciation of the current inventory value.</span></span>|  
|<span data-ttu-id="27b83-140">Rounding</span><span class="sxs-lookup"><span data-stu-id="27b83-140">Rounding</span></span>||<span data-ttu-id="27b83-141">Residuals caused by the way in which valuation of inventory decreases are calculated.</span><span class="sxs-lookup"><span data-stu-id="27b83-141">Residuals caused by the way in which valuation of inventory decreases are calculated.</span></span>|  

> [!NOTE]  
>  <span data-ttu-id="27b83-142">Freight and insurance costs are item charges that can be added to an item’s cost at any time.</span><span class="sxs-lookup"><span data-stu-id="27b83-142">Freight and insurance costs are item charges that can be added to an item’s cost at any time.</span></span> <span data-ttu-id="27b83-143">When you run the **Adjust Cost - Item Entries** batch job, the value of any related inventory decreases are updated accordingly.</span><span class="sxs-lookup"><span data-stu-id="27b83-143">When you run the **Adjust Cost - Item Entries** batch job, the value of any related inventory decreases are updated accordingly.</span></span>  

## <a name="see-also"></a><span data-ttu-id="27b83-144">See Also</span><span class="sxs-lookup"><span data-stu-id="27b83-144">See Also</span></span>  
 <span data-ttu-id="27b83-145">[Design Details: Inventory Costing](design-details-inventory-costing.md) </span><span class="sxs-lookup"><span data-stu-id="27b83-145">[Design Details: Inventory Costing](design-details-inventory-costing.md) </span></span>  
 <span data-ttu-id="27b83-146">[Design Details: Variance](design-details-variance.md) [Managing Inventory Costs](finance-manage-inventory-costs.md)</span><span class="sxs-lookup"><span data-stu-id="27b83-146">[Design Details: Variance](design-details-variance.md) [Managing Inventory Costs](finance-manage-inventory-costs.md)</span></span>  
 [<span data-ttu-id="27b83-147">Finance</span><span class="sxs-lookup"><span data-stu-id="27b83-147">Finance</span></span>](finance.md)  
 <span data-ttu-id="27b83-148">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="27b83-148">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  
