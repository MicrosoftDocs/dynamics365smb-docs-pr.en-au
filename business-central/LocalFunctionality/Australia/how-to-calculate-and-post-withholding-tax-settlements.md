---
title: How to Calculate and Post Withholding Tax Settlements
description: You can use the Calc. and Post WHT Settlement page to calculate and post the withholding tax (WHT).
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.search.keywords: ''
ms.date: 04/01/2019
ms.author: sgroespe
ms.openlocfilehash: 4e994dbcf84cbe1d92b7a8e6980324641f5ea722
ms.sourcegitcommit: 5b6dd8d881c0eb65ece6936a94dfda3185574335
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 06/28/2019
ms.locfileid: "1710988"
---
# <a name="calculate-and-post-withholding-tax-settlements"></a><span data-ttu-id="b5307-103">Calculate and Post Withholding Tax Settlements</span><span class="sxs-lookup"><span data-stu-id="b5307-103">Calculate and Post Withholding Tax Settlements</span></span>
<span data-ttu-id="b5307-104">You can use the **Calc. and Post WHT Settlement** page to calculate and post the withholding tax (WHT).</span><span class="sxs-lookup"><span data-stu-id="b5307-104">You can use the **Calc. and Post WHT Settlement** page to calculate and post the withholding tax (WHT).</span></span>  

<span data-ttu-id="b5307-105">You can close WHT entries that are open or not settled and transfer the corresponding amount to the WHT settlement account.</span><span class="sxs-lookup"><span data-stu-id="b5307-105">You can close WHT entries that are open or not settled and transfer the corresponding amount to the WHT settlement account.</span></span>  

<span data-ttu-id="b5307-106">The sum of all withheld amounts is reported as a truncated whole number to the Australian tax authorities.</span><span class="sxs-lookup"><span data-stu-id="b5307-106">The sum of all withheld amounts is reported as a truncated whole number to the Australian tax authorities.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="b5307-107">The truncated cents are accounted for in a rounding account.</span><span class="sxs-lookup"><span data-stu-id="b5307-107">The truncated cents are accounted for in a rounding account.</span></span>  

## <a name="to-calculate-and-post-withholding-tax-settlements"></a><span data-ttu-id="b5307-108">To calculate and post withholding tax settlements</span><span class="sxs-lookup"><span data-stu-id="b5307-108">To calculate and post withholding tax settlements</span></span>  

1.  <span data-ttu-id="b5307-109">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Calc. and Post WHT Settlement**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="b5307-109">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Calc. and Post WHT Settlement**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="b5307-110">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="b5307-110">Fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="b5307-111">Field</span><span class="sxs-lookup"><span data-stu-id="b5307-111">Field</span></span>|<span data-ttu-id="b5307-112">Description</span><span class="sxs-lookup"><span data-stu-id="b5307-112">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="b5307-113">**Starting Date**</span><span class="sxs-lookup"><span data-stu-id="b5307-113">**Starting Date**</span></span>|<span data-ttu-id="b5307-114">The start date of the period for which WHT has to be settled.</span><span class="sxs-lookup"><span data-stu-id="b5307-114">The start date of the period for which WHT has to be settled.</span></span>|  
    |<span data-ttu-id="b5307-115">**Ending Date**</span><span class="sxs-lookup"><span data-stu-id="b5307-115">**Ending Date**</span></span>|<span data-ttu-id="b5307-116">The end date of the period for which WHT has to be settled.</span><span class="sxs-lookup"><span data-stu-id="b5307-116">The end date of the period for which WHT has to be settled.</span></span>|  
    |<span data-ttu-id="b5307-117">**Posting Date**</span><span class="sxs-lookup"><span data-stu-id="b5307-117">**Posting Date**</span></span>|<span data-ttu-id="b5307-118">The posting date of the WHT settlement entries.</span><span class="sxs-lookup"><span data-stu-id="b5307-118">The posting date of the WHT settlement entries.</span></span>|  
    |<span data-ttu-id="b5307-119">**Document No.**</span><span class="sxs-lookup"><span data-stu-id="b5307-119">**Document No.**</span></span>|<span data-ttu-id="b5307-120">The document number of the WHT settlement entries.</span><span class="sxs-lookup"><span data-stu-id="b5307-120">The document number of the WHT settlement entries.</span></span>|  
    |<span data-ttu-id="b5307-121">**Description**</span><span class="sxs-lookup"><span data-stu-id="b5307-121">**Description**</span></span>|<span data-ttu-id="b5307-122">The WHT settlement description.</span><span class="sxs-lookup"><span data-stu-id="b5307-122">The WHT settlement description.</span></span>|  
    |<span data-ttu-id="b5307-123">**Settlement Account Type**</span><span class="sxs-lookup"><span data-stu-id="b5307-123">**Settlement Account Type**</span></span>|<span data-ttu-id="b5307-124">The settlement account type.</span><span class="sxs-lookup"><span data-stu-id="b5307-124">The settlement account type.</span></span>|  
    |<span data-ttu-id="b5307-125">**Settlement Account**</span><span class="sxs-lookup"><span data-stu-id="b5307-125">**Settlement Account**</span></span>|<span data-ttu-id="b5307-126">The account number based on the account type selected in the **Settlement Account Type** field.</span><span class="sxs-lookup"><span data-stu-id="b5307-126">The account number based on the account type selected in the **Settlement Account Type** field.</span></span>|  
    |<span data-ttu-id="b5307-127">**Rounding G/L Account**</span><span class="sxs-lookup"><span data-stu-id="b5307-127">**Rounding G/L Account**</span></span>|<span data-ttu-id="b5307-128">The account to which the truncated amount is to be posted.</span><span class="sxs-lookup"><span data-stu-id="b5307-128">The account to which the truncated amount is to be posted.</span></span>|  
    |<span data-ttu-id="b5307-129">**Show WHT Entries**</span><span class="sxs-lookup"><span data-stu-id="b5307-129">**Show WHT Entries**</span></span>|<span data-ttu-id="b5307-130">Select to view the withholding tax entries for the specified period.</span><span class="sxs-lookup"><span data-stu-id="b5307-130">Select to view the withholding tax entries for the specified period.</span></span>|  
    |<span data-ttu-id="b5307-131">**Post**</span><span class="sxs-lookup"><span data-stu-id="b5307-131">**Post**</span></span>|<span data-ttu-id="b5307-132">Select to post the WHT settlement entries.</span><span class="sxs-lookup"><span data-stu-id="b5307-132">Select to post the WHT settlement entries.</span></span>|  

3.  <span data-ttu-id="b5307-133">Choose the **Print** button to print the report, or choose the **Preview** button to view it on the screen.</span><span class="sxs-lookup"><span data-stu-id="b5307-133">Choose the **Print** button to print the report, or choose the **Preview** button to view it on the screen.</span></span>  

## <a name="see-also"></a><span data-ttu-id="b5307-134">See Also</span><span class="sxs-lookup"><span data-stu-id="b5307-134">See Also</span></span>  
 <span data-ttu-id="b5307-135">[Withholding Tax](withholding-tax.md) </span><span class="sxs-lookup"><span data-stu-id="b5307-135">[Withholding Tax](withholding-tax.md) </span></span>  
 <span data-ttu-id="b5307-136">[Set Up Withholding Tax](how-to-set-up-withholding-tax.md) </span><span class="sxs-lookup"><span data-stu-id="b5307-136">[Set Up Withholding Tax](how-to-set-up-withholding-tax.md) </span></span>  
 <span data-ttu-id="b5307-137">[Set Up Revenue Types for Withholding Tax](how-to-set-up-revenue-types-for-withholding-tax.md) </span><span class="sxs-lookup"><span data-stu-id="b5307-137">[Set Up Revenue Types for Withholding Tax](how-to-set-up-revenue-types-for-withholding-tax.md) </span></span>  
 [<span data-ttu-id="b5307-138">View Withholding Tax Entries</span><span class="sxs-lookup"><span data-stu-id="b5307-138">View Withholding Tax Entries</span></span>](how-to-view-withholding-tax-entries.md)
