---
title: Withholding Tax
description: Withholding Tax (WHT) is tax withheld by a company when making a payment to a vendor, in which the full amount owed to that vendor is reduced by the tax withheld. The withheld tax is then remitted to the Australian Taxation Office (ATO) during the next Business Activity Statement (BAS) submission.
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
ms.sourcegitcommit: 046a42582dc66368fded90a4bb45add71a95d979
ms.openlocfilehash: b0d91f0c6eb1033c3c45af996dd9f10b29bead6a
ms.contentlocale: en-au
ms.lasthandoff: 07/02/2018

---
# <a name="withholding-tax"></a><span data-ttu-id="573e5-104">Withholding Tax</span><span class="sxs-lookup"><span data-stu-id="573e5-104">Withholding Tax</span></span>
<span data-ttu-id="573e5-105">Withholding Tax (WHT) is tax withheld by a company when making a payment to a vendor, in which the full amount owed to that vendor is reduced by the tax withheld.</span><span class="sxs-lookup"><span data-stu-id="573e5-105">Withholding Tax (WHT) is tax withheld by a company when making a payment to a vendor, in which the full amount owed to that vendor is reduced by the tax withheld.</span></span> <span data-ttu-id="573e5-106">The withheld tax is then remitted to the Australian Taxation Office (ATO) during the next Business Activity Statement (BAS) submission.</span><span class="sxs-lookup"><span data-stu-id="573e5-106">The withheld tax is then remitted to the Australian Taxation Office (ATO) during the next Business Activity Statement (BAS) submission.</span></span>  

<span data-ttu-id="573e5-107">The Australian government requires taxes to be withheld from payment to vendors under the following circumstances:</span><span class="sxs-lookup"><span data-stu-id="573e5-107">The Australian government requires taxes to be withheld from payment to vendors under the following circumstances:</span></span>  

-   <span data-ttu-id="573e5-108">The vendor is a local supplier who has not supplied an Australian Business Number (ABN) before the payment is processed, and the individual transaction amount is greater than the specified threshold amount.</span><span class="sxs-lookup"><span data-stu-id="573e5-108">The vendor is a local supplier who has not supplied an Australian Business Number (ABN) before the payment is processed, and the individual transaction amount is greater than the specified threshold amount.</span></span>  

-   <span data-ttu-id="573e5-109">The vendor is a non-resident supplier and the payment is to be made to this non-resident entity in the form of interest, royalty, or dividend payments.</span><span class="sxs-lookup"><span data-stu-id="573e5-109">The vendor is a non-resident supplier and the payment is to be made to this non-resident entity in the form of interest, royalty, or dividend payments.</span></span> <span data-ttu-id="573e5-110">Currently, there is no minimum threshold amount.</span><span class="sxs-lookup"><span data-stu-id="573e5-110">Currently, there is no minimum threshold amount.</span></span> <span data-ttu-id="573e5-111">Withholding rates may vary due to payment, or international tax treaties existing between Australia and the vendor's country.</span><span class="sxs-lookup"><span data-stu-id="573e5-111">Withholding rates may vary due to payment, or international tax treaties existing between Australia and the vendor's country.</span></span>  

<span data-ttu-id="573e5-112">Fields within **WHT Business Posting Groups** and **WHT Product Posting Groups** must be set up in the **WHT Posting Setup** window so that the correct WHT calculations are made for each vendor.</span><span class="sxs-lookup"><span data-stu-id="573e5-112">Fields within **WHT Business Posting Groups** and **WHT Product Posting Groups** must be set up in the **WHT Posting Setup** window so that the correct WHT calculations are made for each vendor.</span></span>  

-   <span data-ttu-id="573e5-113">**WHT Calculation Rule** – This field controls how calculation applies to the **WHT Minimum Invoice Amount**, or the invoice threshold amount.</span><span class="sxs-lookup"><span data-stu-id="573e5-113">**WHT Calculation Rule** – This field controls how calculation applies to the **WHT Minimum Invoice Amount**, or the invoice threshold amount.</span></span> <span data-ttu-id="573e5-114">The following options exist:</span><span class="sxs-lookup"><span data-stu-id="573e5-114">The following options exist:</span></span>  

    - <span data-ttu-id="573e5-115">**Less than**</span><span class="sxs-lookup"><span data-stu-id="573e5-115">**Less than**</span></span>  
    - <span data-ttu-id="573e5-116">**Less than or equal to**</span><span class="sxs-lookup"><span data-stu-id="573e5-116">**Less than or equal to**</span></span>  
    - <span data-ttu-id="573e5-117">**Equal to**</span><span class="sxs-lookup"><span data-stu-id="573e5-117">**Equal to**</span></span>  
    - <span data-ttu-id="573e5-118">**Greater than**</span><span class="sxs-lookup"><span data-stu-id="573e5-118">**Greater than**</span></span>  
    - <span data-ttu-id="573e5-119">**Greater than or equal to**</span><span class="sxs-lookup"><span data-stu-id="573e5-119">**Greater than or equal to**</span></span>  

<span data-ttu-id="573e5-120">In Australia, WHT is not calculated if the individual invoice amount is less than or equal to the threshold amount.</span><span class="sxs-lookup"><span data-stu-id="573e5-120">In Australia, WHT is not calculated if the individual invoice amount is less than or equal to the threshold amount.</span></span> <span data-ttu-id="573e5-121">Australian companies should select **Less than or equal to**.</span><span class="sxs-lookup"><span data-stu-id="573e5-121">Australian companies should select **Less than or equal to**.</span></span>  

- <span data-ttu-id="573e5-122">**WHT Minimum Invoice Amount** – Enter the invoice threshold amount.</span><span class="sxs-lookup"><span data-stu-id="573e5-122">**WHT Minimum Invoice Amount** – Enter the invoice threshold amount.</span></span>  

- <span data-ttu-id="573e5-123">**WHT %** – Enter the relevant WHT rate for the particular combination of **WHT Business Posting Group** and **WHT Product Posting Group**.</span><span class="sxs-lookup"><span data-stu-id="573e5-123">**WHT %** – Enter the relevant WHT rate for the particular combination of **WHT Business Posting Group** and **WHT Product Posting Group**.</span></span> <span data-ttu-id="573e5-124">If you do not wish to calculate any withholding amount, enter 0.00.</span><span class="sxs-lookup"><span data-stu-id="573e5-124">If you do not wish to calculate any withholding amount, enter 0.00.</span></span>  

- <span data-ttu-id="573e5-125">**Realised WHT Type** – Select **Payment** to calculate only the withholding amount at the time of payment.</span><span class="sxs-lookup"><span data-stu-id="573e5-125">**Realised WHT Type** – Select **Payment** to calculate only the withholding amount at the time of payment.</span></span> <span data-ttu-id="573e5-126">The other options of **Invoice** and **Earliest** do not apply to Australia.</span><span class="sxs-lookup"><span data-stu-id="573e5-126">The other options of **Invoice** and **Earliest** do not apply to Australia.</span></span>  

- <span data-ttu-id="573e5-127">**Payable WHT Account Code** – Enter the number of the G/L account to which you want to post **Purchase WHT** for the particular combination of **WHT Business Posting Group** and **WHT Product Posting Group**.</span><span class="sxs-lookup"><span data-stu-id="573e5-127">**Payable WHT Account Code** – Enter the number of the G/L account to which you want to post **Purchase WHT** for the particular combination of **WHT Business Posting Group** and **WHT Product Posting Group**.</span></span>  

- <span data-ttu-id="573e5-128">**Purch. WHT Adjustment Account No.** – Select an account number for **Purchase CR/Adj Note** adjustments.</span><span class="sxs-lookup"><span data-stu-id="573e5-128">**Purch. WHT Adjustment Account No.** – Select an account number for **Purchase CR/Adj Note** adjustments.</span></span>  

- <span data-ttu-id="573e5-129">**Revenue Types** – Drill down to the **WHT Revenue Types** window.</span><span class="sxs-lookup"><span data-stu-id="573e5-129">**Revenue Types** – Drill down to the **WHT Revenue Types** window.</span></span> <span data-ttu-id="573e5-130">These values determine how the combination of **WHT Business Posting Group** and **WHT Product Posting Group** are displayed in reports.</span><span class="sxs-lookup"><span data-stu-id="573e5-130">These values determine how the combination of **WHT Business Posting Group** and **WHT Product Posting Group** are displayed in reports.</span></span> <span data-ttu-id="573e5-131">You must enter a value in order for this combination to appear in the WHT reports.</span><span class="sxs-lookup"><span data-stu-id="573e5-131">You must enter a value in order for this combination to appear in the WHT reports.</span></span>  

## <a name="wht-for-suppliers-without-an-abn"></a><span data-ttu-id="573e5-132">WHT for Suppliers Without an ABN</span><span class="sxs-lookup"><span data-stu-id="573e5-132">WHT for Suppliers Without an ABN</span></span>  
<span data-ttu-id="573e5-133">Ensure that there is a valid combination of **General Business** and **General Product Posting Groups** with the correct threshold.</span><span class="sxs-lookup"><span data-stu-id="573e5-133">Ensure that there is a valid combination of **General Business** and **General Product Posting Groups** with the correct threshold.</span></span> <span data-ttu-id="573e5-134">For example, in Australia today the minimum threshold is $75 with a rate of 46.50%.</span><span class="sxs-lookup"><span data-stu-id="573e5-134">For example, in Australia today the minimum threshold is $75 with a rate of 46.50%.</span></span>  

<span data-ttu-id="573e5-135">The percentage withheld is specified in **WHT Posting Setup**.</span><span class="sxs-lookup"><span data-stu-id="573e5-135">The percentage withheld is specified in **WHT Posting Setup**.</span></span> <span data-ttu-id="573e5-136">The amount to be withheld is calculated automatically at the time of payment.</span><span class="sxs-lookup"><span data-stu-id="573e5-136">The amount to be withheld is calculated automatically at the time of payment.</span></span> <span data-ttu-id="573e5-137">The WHT certificate is printed automatically, and then sent to the vendor with payment.</span><span class="sxs-lookup"><span data-stu-id="573e5-137">The WHT certificate is printed automatically, and then sent to the vendor with payment.</span></span> <span data-ttu-id="573e5-138">The WHT certificate explains the reasons for not sending the full invoiced amount.</span><span class="sxs-lookup"><span data-stu-id="573e5-138">The WHT certificate explains the reasons for not sending the full invoiced amount.</span></span>  

## <a name="wht-for-foreign-suppliers"></a><span data-ttu-id="573e5-139">WHT for Foreign Suppliers</span><span class="sxs-lookup"><span data-stu-id="573e5-139">WHT for Foreign Suppliers</span></span>  
<span data-ttu-id="573e5-140">Ensure that a valid combination of **General Business** and **General Product PostingGroups** has been established for vendors for whom you need to withhold tax, other than for non-ABN.</span><span class="sxs-lookup"><span data-stu-id="573e5-140">Ensure that a valid combination of **General Business** and **General Product PostingGroups** has been established for vendors for whom you need to withhold tax, other than for non-ABN.</span></span>  

## <a name="see-also"></a><span data-ttu-id="573e5-141">See Also</span><span class="sxs-lookup"><span data-stu-id="573e5-141">See Also</span></span>  
 <span data-ttu-id="573e5-142">[Set Up Withholding Tax](how-to-set-up-withholding-tax.md) </span><span class="sxs-lookup"><span data-stu-id="573e5-142">[Set Up Withholding Tax](how-to-set-up-withholding-tax.md) </span></span>  
 <span data-ttu-id="573e5-143">[Set Up Vendors Without ABN for Calculating the Withholding Tax](how-to-set-up-vendors-without-abn-for-calculating-the-withholding-tax.md) </span><span class="sxs-lookup"><span data-stu-id="573e5-143">[Set Up Vendors Without ABN for Calculating the Withholding Tax](how-to-set-up-vendors-without-abn-for-calculating-the-withholding-tax.md) </span></span>  
 <span data-ttu-id="573e5-144">[Set Up Revenue Types for Withholding Tax](how-to-set-up-revenue-types-for-withholding-tax.md) </span><span class="sxs-lookup"><span data-stu-id="573e5-144">[Set Up Revenue Types for Withholding Tax](how-to-set-up-revenue-types-for-withholding-tax.md) </span></span>  
 <span data-ttu-id="573e5-145">[Calculate and Post Withholding Tax Settlements](how-to-calculate-and-post-withholding-tax-settlements.md) </span><span class="sxs-lookup"><span data-stu-id="573e5-145">[Calculate and Post Withholding Tax Settlements](how-to-calculate-and-post-withholding-tax-settlements.md) </span></span>  
 <span data-ttu-id="573e5-146">[View Withholding Tax Entries](how-to-view-withholding-tax-entries.md) </span><span class="sxs-lookup"><span data-stu-id="573e5-146">[View Withholding Tax Entries](how-to-view-withholding-tax-entries.md) </span></span>  
 [<span data-ttu-id="573e5-147">Australia Local Functionality</span><span class="sxs-lookup"><span data-stu-id="573e5-147">Australia Local Functionality</span></span>](australia-local-functionality.md)
