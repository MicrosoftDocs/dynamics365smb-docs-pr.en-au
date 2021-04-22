---
title: Set Up Withholding Tax in the Australian version
description: Withholding tax (WHT) is the tax withheld by a company when it makes a payment to a vendor, in which the full amount owed to the vendor is reduced by the tax withheld in the Australian version. The withheld tax is then remitted to the Australian Taxation Office (ATO) when the next Business Activity Statement (BAS) is submitted.
author: edupont04
ms.service: dynamics365-business-central
ms.topic: conceptual
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: ''
ms.date: 04/01/2021
ms.author: edupont
ms.openlocfilehash: 100215bd59ed27b32abe6a9ab47c8f03760d2661
ms.sourcegitcommit: 766e2840fd16efb901d211d7fa64d96766ac99d9
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 03/31/2021
ms.locfileid: "5774438"
---
# <a name="set-up-withholding-tax-in-the-australian-version"></a><span data-ttu-id="8ed0a-104">Set Up Withholding Tax in the Australian Version</span><span class="sxs-lookup"><span data-stu-id="8ed0a-104">Set Up Withholding Tax in the Australian Version</span></span>

<span data-ttu-id="8ed0a-105">Withholding tax (WHT) is the tax withheld by a company when it makes a payment to a vendor, in which the full amount owed to the vendor is reduced by the tax withheld.</span><span class="sxs-lookup"><span data-stu-id="8ed0a-105">Withholding tax (WHT) is the tax withheld by a company when it makes a payment to a vendor, in which the full amount owed to the vendor is reduced by the tax withheld.</span></span> <span data-ttu-id="8ed0a-106">The withheld tax is then remitted to the Australian Taxation Office (ATO) when the next Business Activity Statement (BAS) is submitted.</span><span class="sxs-lookup"><span data-stu-id="8ed0a-106">The withheld tax is then remitted to the Australian Taxation Office (ATO) when the next Business Activity Statement (BAS) is submitted.</span></span>  

<span data-ttu-id="8ed0a-107">If a supplier without an Australian Business Number (ABN) provides an invoice, a withholding tax amount must be withheld if the total amount of the invoice is more than the threshold amount.</span><span class="sxs-lookup"><span data-stu-id="8ed0a-107">If a supplier without an Australian Business Number (ABN) provides an invoice, a withholding tax amount must be withheld if the total amount of the invoice is more than the threshold amount.</span></span> <span data-ttu-id="8ed0a-108">To use withholding tax, you must first enable WHT in the **General Ledger Setup** page and set up product posting groups and business posting groups for WHT.</span><span class="sxs-lookup"><span data-stu-id="8ed0a-108">To use withholding tax, you must first enable WHT in the **General Ledger Setup** page and set up product posting groups and business posting groups for WHT.</span></span>  

## <a name="to-enable-withholding-tax"></a><span data-ttu-id="8ed0a-109">To enable withholding tax</span><span class="sxs-lookup"><span data-stu-id="8ed0a-109">To enable withholding tax</span></span>

1. <span data-ttu-id="8ed0a-110">Choose the ![Lightbulb that opens the Tell Me feature](../../media/ui-search/search_small.png "Tell me what you want to do") icon, enter **General Ledger Setup**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="8ed0a-110">Choose the ![Lightbulb that opens the Tell Me feature](../../media/ui-search/search_small.png "Tell me what you want to do") icon, enter **General Ledger Setup**, and then choose the related link.</span></span>  

2. <span data-ttu-id="8ed0a-111">On the **Local Functionalities** FastTab, choose the **Enable WHT** field.</span><span class="sxs-lookup"><span data-stu-id="8ed0a-111">On the **Local Functionalities** FastTab, choose the **Enable WHT** field.</span></span>  

3. <span data-ttu-id="8ed0a-112">Optionally, choose the **Round Amount for WHT Calc** field.</span><span class="sxs-lookup"><span data-stu-id="8ed0a-112">Optionally, choose the **Round Amount for WHT Calc** field.</span></span>

    <span data-ttu-id="8ed0a-113">If you choose this field, all WHT amounts will be rounded down to the nearest number.</span><span class="sxs-lookup"><span data-stu-id="8ed0a-113">If you choose this field, all WHT amounts will be rounded down to the nearest number.</span></span> <span data-ttu-id="8ed0a-114">For example, if the WHT amount on an invoice is calculated to be 33.90, and the **Round Amount for WHT Calc** field is chosen in the General Ledger Setup, then the WHT amount will round to 33.</span><span class="sxs-lookup"><span data-stu-id="8ed0a-114">For example, if the WHT amount on an invoice is calculated to be 33.90, and the **Round Amount for WHT Calc** field is chosen in the General Ledger Setup, then the WHT amount will round to 33.</span></span>

[!INCLUDE [wht-posting-group-setup](../includes/AUNZ/wht-posting-group-setup.md)]

## <a name="see-also"></a><span data-ttu-id="8ed0a-115">See Also</span><span class="sxs-lookup"><span data-stu-id="8ed0a-115">See Also</span></span>

[<span data-ttu-id="8ed0a-116">Set Up Revenue Types for Withholding Tax</span><span class="sxs-lookup"><span data-stu-id="8ed0a-116">Set Up Revenue Types for Withholding Tax</span></span>](how-to-set-up-revenue-types-for-withholding-tax.md)  
[<span data-ttu-id="8ed0a-117">View Withholding Tax Entries</span><span class="sxs-lookup"><span data-stu-id="8ed0a-117">View Withholding Tax Entries</span></span>](how-to-view-withholding-tax-entries.md)  
[<span data-ttu-id="8ed0a-118">Calculate and Post Withholding Tax Settlements</span><span class="sxs-lookup"><span data-stu-id="8ed0a-118">Calculate and Post Withholding Tax Settlements</span></span>](how-to-calculate-and-post-withholding-tax-settlements.md)  
[<span data-ttu-id="8ed0a-119">Withholding Tax</span><span class="sxs-lookup"><span data-stu-id="8ed0a-119">Withholding Tax</span></span>](withholding-tax.md)  
[<span data-ttu-id="8ed0a-120">Australian Taxation Office (ATO)</span><span class="sxs-lookup"><span data-stu-id="8ed0a-120">Australian Taxation Office (ATO)</span></span>](https://www.ato.gov.au/)  


[!INCLUDE[footer-include](../../includes/footer-banner.md)]