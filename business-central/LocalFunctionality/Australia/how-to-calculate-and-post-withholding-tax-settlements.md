---
title: How to Calculate and Post Withholding Tax Settlements
description: You can use the Calc. and Post WHT Settlement page to calculate and post the withholding tax (WHT).
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.search.keywords: ''
ms.date: 04/01/2020
ms.author: sgroespe
ms.openlocfilehash: e4a51b4f1f471e5bb3c318b55903ec23c1cb2e90
ms.sourcegitcommit: 88e4b30eaf6fa32af0c1452ce2f85ff1111c75e2
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 04/01/2020
ms.locfileid: "3180800"
---
# <a name="calculate-and-post-withholding-tax-settlements"></a><span data-ttu-id="7a594-103">Calculate and Post Withholding Tax Settlements</span><span class="sxs-lookup"><span data-stu-id="7a594-103">Calculate and Post Withholding Tax Settlements</span></span>
<span data-ttu-id="7a594-104">You can use the **Calc. and Post WHT Settlement** page to calculate and post the withholding tax (WHT).</span><span class="sxs-lookup"><span data-stu-id="7a594-104">You can use the **Calc. and Post WHT Settlement** page to calculate and post the withholding tax (WHT).</span></span>  

<span data-ttu-id="7a594-105">You can close WHT entries that are open or not settled and transfer the corresponding amount to the WHT settlement account.</span><span class="sxs-lookup"><span data-stu-id="7a594-105">You can close WHT entries that are open or not settled and transfer the corresponding amount to the WHT settlement account.</span></span>  

<span data-ttu-id="7a594-106">The sum of all withheld amounts is reported as a truncated whole number to the Australian tax authorities.</span><span class="sxs-lookup"><span data-stu-id="7a594-106">The sum of all withheld amounts is reported as a truncated whole number to the Australian tax authorities.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="7a594-107">The truncated cents are accounted for in a rounding account.</span><span class="sxs-lookup"><span data-stu-id="7a594-107">The truncated cents are accounted for in a rounding account.</span></span>  

## <a name="to-calculate-and-post-withholding-tax-settlements"></a><span data-ttu-id="7a594-108">To calculate and post withholding tax settlements</span><span class="sxs-lookup"><span data-stu-id="7a594-108">To calculate and post withholding tax settlements</span></span>  

1.  <span data-ttu-id="7a594-109">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Calc. and Post WHT Settlement**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="7a594-109">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Calc. and Post WHT Settlement**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="7a594-110">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="7a594-110">Fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="7a594-111">Field</span><span class="sxs-lookup"><span data-stu-id="7a594-111">Field</span></span>|<span data-ttu-id="7a594-112">Description</span><span class="sxs-lookup"><span data-stu-id="7a594-112">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="7a594-113">**Starting Date**</span><span class="sxs-lookup"><span data-stu-id="7a594-113">**Starting Date**</span></span>|<span data-ttu-id="7a594-114">The start date of the period for which WHT has to be settled.</span><span class="sxs-lookup"><span data-stu-id="7a594-114">The start date of the period for which WHT has to be settled.</span></span>|  
    |<span data-ttu-id="7a594-115">**Ending Date**</span><span class="sxs-lookup"><span data-stu-id="7a594-115">**Ending Date**</span></span>|<span data-ttu-id="7a594-116">The end date of the period for which WHT has to be settled.</span><span class="sxs-lookup"><span data-stu-id="7a594-116">The end date of the period for which WHT has to be settled.</span></span>|  
    |<span data-ttu-id="7a594-117">**Posting Date**</span><span class="sxs-lookup"><span data-stu-id="7a594-117">**Posting Date**</span></span>|<span data-ttu-id="7a594-118">The posting date of the WHT settlement entries.</span><span class="sxs-lookup"><span data-stu-id="7a594-118">The posting date of the WHT settlement entries.</span></span>|  
    |<span data-ttu-id="7a594-119">**Document No.**</span><span class="sxs-lookup"><span data-stu-id="7a594-119">**Document No.**</span></span>|<span data-ttu-id="7a594-120">The document number of the WHT settlement entries.</span><span class="sxs-lookup"><span data-stu-id="7a594-120">The document number of the WHT settlement entries.</span></span>|  
    |<span data-ttu-id="7a594-121">**Description**</span><span class="sxs-lookup"><span data-stu-id="7a594-121">**Description**</span></span>|<span data-ttu-id="7a594-122">The WHT settlement description.</span><span class="sxs-lookup"><span data-stu-id="7a594-122">The WHT settlement description.</span></span>|  
    |<span data-ttu-id="7a594-123">**Settlement Account Type**</span><span class="sxs-lookup"><span data-stu-id="7a594-123">**Settlement Account Type**</span></span>|<span data-ttu-id="7a594-124">The settlement account type.</span><span class="sxs-lookup"><span data-stu-id="7a594-124">The settlement account type.</span></span>|  
    |<span data-ttu-id="7a594-125">**Settlement Account**</span><span class="sxs-lookup"><span data-stu-id="7a594-125">**Settlement Account**</span></span>|<span data-ttu-id="7a594-126">The account number based on the account type selected in the **Settlement Account Type** field.</span><span class="sxs-lookup"><span data-stu-id="7a594-126">The account number based on the account type selected in the **Settlement Account Type** field.</span></span>|  
    |<span data-ttu-id="7a594-127">**Rounding G/L Account**</span><span class="sxs-lookup"><span data-stu-id="7a594-127">**Rounding G/L Account**</span></span>|<span data-ttu-id="7a594-128">The account to which the truncated amount is to be posted.</span><span class="sxs-lookup"><span data-stu-id="7a594-128">The account to which the truncated amount is to be posted.</span></span>|  
    |<span data-ttu-id="7a594-129">**Show WHT Entries**</span><span class="sxs-lookup"><span data-stu-id="7a594-129">**Show WHT Entries**</span></span>|<span data-ttu-id="7a594-130">Select to view the withholding tax entries for the specified period.</span><span class="sxs-lookup"><span data-stu-id="7a594-130">Select to view the withholding tax entries for the specified period.</span></span>|  
    |<span data-ttu-id="7a594-131">**Post**</span><span class="sxs-lookup"><span data-stu-id="7a594-131">**Post**</span></span>|<span data-ttu-id="7a594-132">Select to post the WHT settlement entries.</span><span class="sxs-lookup"><span data-stu-id="7a594-132">Select to post the WHT settlement entries.</span></span>|  

3.  <span data-ttu-id="7a594-133">Choose the **Print** button to print the report, or choose the **Preview** button to view it on the screen.</span><span class="sxs-lookup"><span data-stu-id="7a594-133">Choose the **Print** button to print the report, or choose the **Preview** button to view it on the screen.</span></span>  

## <a name="see-also"></a><span data-ttu-id="7a594-134">See Also</span><span class="sxs-lookup"><span data-stu-id="7a594-134">See Also</span></span>  
 <span data-ttu-id="7a594-135">[Withholding Tax](withholding-tax.md) </span><span class="sxs-lookup"><span data-stu-id="7a594-135">[Withholding Tax](withholding-tax.md) </span></span>  
 <span data-ttu-id="7a594-136">[Set Up Withholding Tax](how-to-set-up-withholding-tax.md) </span><span class="sxs-lookup"><span data-stu-id="7a594-136">[Set Up Withholding Tax](how-to-set-up-withholding-tax.md) </span></span>  
 <span data-ttu-id="7a594-137">[Set Up Revenue Types for Withholding Tax](how-to-set-up-revenue-types-for-withholding-tax.md) </span><span class="sxs-lookup"><span data-stu-id="7a594-137">[Set Up Revenue Types for Withholding Tax](how-to-set-up-revenue-types-for-withholding-tax.md) </span></span>  
 [<span data-ttu-id="7a594-138">View Withholding Tax Entries</span><span class="sxs-lookup"><span data-stu-id="7a594-138">View Withholding Tax Entries</span></span>](how-to-view-withholding-tax-entries.md)
