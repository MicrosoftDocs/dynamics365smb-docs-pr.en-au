---
title: How to Calculate and Post Withholding Tax Settlements
description: You can use the Calc. and Post WHT Settlement page to calculate and post the withholding tax (WHT).
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.search.keywords: 
ms.date: 10/01/2018
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: caf7cf5afe370af0c4294c794c0ff9bc8ff4c31c
ms.openlocfilehash: 76e046af7e36e1cb091f24cbe9e3d23a5231cb3b
ms.contentlocale: en-au
ms.lasthandoff: 11/22/2018

---
# <a name="calculate-and-post-withholding-tax-settlements"></a><span data-ttu-id="315ae-103">Calculate and Post Withholding Tax Settlements</span><span class="sxs-lookup"><span data-stu-id="315ae-103">Calculate and Post Withholding Tax Settlements</span></span>
<span data-ttu-id="315ae-104">You can use the **Calc. and Post WHT Settlement** page to calculate and post the withholding tax (WHT).</span><span class="sxs-lookup"><span data-stu-id="315ae-104">You can use the **Calc. and Post WHT Settlement** page to calculate and post the withholding tax (WHT).</span></span>  

<span data-ttu-id="315ae-105">You can close WHT entries that are open or not settled and transfer the corresponding amount to the WHT settlement account.</span><span class="sxs-lookup"><span data-stu-id="315ae-105">You can close WHT entries that are open or not settled and transfer the corresponding amount to the WHT settlement account.</span></span>  

<span data-ttu-id="315ae-106">The sum of all withheld amounts is reported as a truncated whole number to the Australian tax authorities.</span><span class="sxs-lookup"><span data-stu-id="315ae-106">The sum of all withheld amounts is reported as a truncated whole number to the Australian tax authorities.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="315ae-107">The truncated cents are accounted for in a rounding account.</span><span class="sxs-lookup"><span data-stu-id="315ae-107">The truncated cents are accounted for in a rounding account.</span></span>  

## <a name="to-calculate-and-post-withholding-tax-settlements"></a><span data-ttu-id="315ae-108">To calculate and post withholding tax settlements</span><span class="sxs-lookup"><span data-stu-id="315ae-108">To calculate and post withholding tax settlements</span></span>  

1.  <span data-ttu-id="315ae-109">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Calc. and Post WHT Settlement**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="315ae-109">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Calc. and Post WHT Settlement**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="315ae-110">On the **Options** FastTab, fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="315ae-110">On the **Options** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="315ae-111">Field</span><span class="sxs-lookup"><span data-stu-id="315ae-111">Field</span></span>|<span data-ttu-id="315ae-112">Description</span><span class="sxs-lookup"><span data-stu-id="315ae-112">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="315ae-113">**Starting Date**</span><span class="sxs-lookup"><span data-stu-id="315ae-113">**Starting Date**</span></span>|<span data-ttu-id="315ae-114">The start date of the period for which WHT has to be settled.</span><span class="sxs-lookup"><span data-stu-id="315ae-114">The start date of the period for which WHT has to be settled.</span></span>|  
    |<span data-ttu-id="315ae-115">**Ending Date**</span><span class="sxs-lookup"><span data-stu-id="315ae-115">**Ending Date**</span></span>|<span data-ttu-id="315ae-116">The end date of the period for which WHT has to be settled.</span><span class="sxs-lookup"><span data-stu-id="315ae-116">The end date of the period for which WHT has to be settled.</span></span>|  
    |<span data-ttu-id="315ae-117">**Posting Date**</span><span class="sxs-lookup"><span data-stu-id="315ae-117">**Posting Date**</span></span>|<span data-ttu-id="315ae-118">The posting date of the WHT settlement entries.</span><span class="sxs-lookup"><span data-stu-id="315ae-118">The posting date of the WHT settlement entries.</span></span>|  
    |<span data-ttu-id="315ae-119">**Document No.**</span><span class="sxs-lookup"><span data-stu-id="315ae-119">**Document No.**</span></span>|<span data-ttu-id="315ae-120">The document number of the WHT settlement entries.</span><span class="sxs-lookup"><span data-stu-id="315ae-120">The document number of the WHT settlement entries.</span></span>|  
    |<span data-ttu-id="315ae-121">**Description**</span><span class="sxs-lookup"><span data-stu-id="315ae-121">**Description**</span></span>|<span data-ttu-id="315ae-122">The WHT settlement description.</span><span class="sxs-lookup"><span data-stu-id="315ae-122">The WHT settlement description.</span></span>|  
    |<span data-ttu-id="315ae-123">**Settlement Account Type**</span><span class="sxs-lookup"><span data-stu-id="315ae-123">**Settlement Account Type**</span></span>|<span data-ttu-id="315ae-124">The settlement account type.</span><span class="sxs-lookup"><span data-stu-id="315ae-124">The settlement account type.</span></span>|  
    |<span data-ttu-id="315ae-125">**Settlement Account**</span><span class="sxs-lookup"><span data-stu-id="315ae-125">**Settlement Account**</span></span>|<span data-ttu-id="315ae-126">The account number based on the account type selected in the **Settlement Account Type** field.</span><span class="sxs-lookup"><span data-stu-id="315ae-126">The account number based on the account type selected in the **Settlement Account Type** field.</span></span>|  
    |<span data-ttu-id="315ae-127">**Rounding G/L Account**</span><span class="sxs-lookup"><span data-stu-id="315ae-127">**Rounding G/L Account**</span></span>|<span data-ttu-id="315ae-128">The account to which the truncated amount is to be posted.</span><span class="sxs-lookup"><span data-stu-id="315ae-128">The account to which the truncated amount is to be posted.</span></span>|  
    |<span data-ttu-id="315ae-129">**Show WHT Entries**</span><span class="sxs-lookup"><span data-stu-id="315ae-129">**Show WHT Entries**</span></span>|<span data-ttu-id="315ae-130">Select to view the withholding tax entries for the specified period.</span><span class="sxs-lookup"><span data-stu-id="315ae-130">Select to view the withholding tax entries for the specified period.</span></span>|  
    |<span data-ttu-id="315ae-131">**Post**</span><span class="sxs-lookup"><span data-stu-id="315ae-131">**Post**</span></span>|<span data-ttu-id="315ae-132">Select to post the WHT settlement entries.</span><span class="sxs-lookup"><span data-stu-id="315ae-132">Select to post the WHT settlement entries.</span></span>|  

3.  <span data-ttu-id="315ae-133">Choose the **Print** button to print the report or choose the **Preview** button to view it on the screen.</span><span class="sxs-lookup"><span data-stu-id="315ae-133">Choose the **Print** button to print the report or choose the **Preview** button to view it on the screen.</span></span>  

## <a name="see-also"></a><span data-ttu-id="315ae-134">See Also</span><span class="sxs-lookup"><span data-stu-id="315ae-134">See Also</span></span>  
 <span data-ttu-id="315ae-135">[Withholding Tax](withholding-tax.md) </span><span class="sxs-lookup"><span data-stu-id="315ae-135">[Withholding Tax](withholding-tax.md) </span></span>  
 <span data-ttu-id="315ae-136">[Set Up Withholding Tax](how-to-set-up-withholding-tax.md) </span><span class="sxs-lookup"><span data-stu-id="315ae-136">[Set Up Withholding Tax](how-to-set-up-withholding-tax.md) </span></span>  
 <span data-ttu-id="315ae-137">[Set Up Revenue Types for Withholding Tax](how-to-set-up-revenue-types-for-withholding-tax.md) </span><span class="sxs-lookup"><span data-stu-id="315ae-137">[Set Up Revenue Types for Withholding Tax](how-to-set-up-revenue-types-for-withholding-tax.md) </span></span>  
 [<span data-ttu-id="315ae-138">View Withholding Tax Entries</span><span class="sxs-lookup"><span data-stu-id="315ae-138">View Withholding Tax Entries</span></span>](how-to-view-withholding-tax-entries.md)

