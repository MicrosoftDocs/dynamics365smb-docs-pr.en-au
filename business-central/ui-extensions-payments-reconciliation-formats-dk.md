---
title: Using the Payments and Reconciliations (DK) Extension | Microsoft Docs
description: This extension makes it easy to export files that are pre-formatted to meet bank requirements for electronic submissions.
author: bholtorf
ms.service: dynamics365-business-central
ms.topic: conceptual
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms. search.keywords: extension, bank, formats
ms.date: 04/01/2021
ms.author: bholtorf
ms.openlocfilehash: fdd8fced06d8efd5ab6959267bfc0171c4decdd2
ms.sourcegitcommit: 766e2840fd16efb901d211d7fa64d96766ac99d9
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 03/31/2021
ms.locfileid: "5785093"
---
# <a name="the-payments-and-reconciliations-dk-extension"></a><span data-ttu-id="d794b-103">The Payments and Reconciliations (DK) Extension</span><span class="sxs-lookup"><span data-stu-id="d794b-103">The Payments and Reconciliations (DK) Extension</span></span>

<span data-ttu-id="d794b-104">Make fast, error-free payments by exporting files that are formatted specifically for exchanges with your vendor or bank.</span><span class="sxs-lookup"><span data-stu-id="d794b-104">Make fast, error-free payments by exporting files that are formatted specifically for exchanges with your vendor or bank.</span></span> <span data-ttu-id="d794b-105">These files speed up the payment and reconciliation processes, and eliminate errors that can happen when you manually enter the information on a bank website.</span><span class="sxs-lookup"><span data-stu-id="d794b-105">These files speed up the payment and reconciliation processes, and eliminate errors that can happen when you manually enter the information on a bank website.</span></span>  

<span data-ttu-id="d794b-106">This extension supports file formats for several Danish banks.</span><span class="sxs-lookup"><span data-stu-id="d794b-106">This extension supports file formats for several Danish banks.</span></span> <span data-ttu-id="d794b-107">When you export payment information to a file, the extension packages the data into the format that your bank requires.</span><span class="sxs-lookup"><span data-stu-id="d794b-107">When you export payment information to a file, the extension packages the data into the format that your bank requires.</span></span> <span data-ttu-id="d794b-108">For example, the formats include Bankdata-V3, BEC, SDC, and FIK, which many different banks use, and some that are more specialised for certain banks, for example, Danske Bank and Nordea.</span><span class="sxs-lookup"><span data-stu-id="d794b-108">For example, the formats include Bankdata-V3, BEC, SDC, and FIK, which many different banks use, and some that are more specialized for certain banks, for example, Danske Bank and Nordea.</span></span> <span data-ttu-id="d794b-109">The extension also includes some formats for importing and reconciling bank statements.</span><span class="sxs-lookup"><span data-stu-id="d794b-109">The extension also includes some formats for importing and reconciling bank statements.</span></span>  

> [!Note]
> <span data-ttu-id="d794b-110">To use the extension, you must know the format that your bank or vendor requires.</span><span class="sxs-lookup"><span data-stu-id="d794b-110">To use the extension, you must know the format that your bank or vendor requires.</span></span> <span data-ttu-id="d794b-111">Some banks or vendors provide this information on their websites; however, you might need to contact their customer service to get the information.</span><span class="sxs-lookup"><span data-stu-id="d794b-111">Some banks or vendors provide this information on their websites; however, you might need to contact their customer service to get the information.</span></span>  

## <a name="supported-bank-formats"></a><span data-ttu-id="d794b-112">Supported Bank Formats</span><span class="sxs-lookup"><span data-stu-id="d794b-112">Supported Bank Formats</span></span>
<span data-ttu-id="d794b-113">This extension can apply the following file formats for payment files:</span><span class="sxs-lookup"><span data-stu-id="d794b-113">This extension can apply the following file formats for payment files:</span></span>  

* <span data-ttu-id="d794b-114">BANKDATA-V3</span><span class="sxs-lookup"><span data-stu-id="d794b-114">BANKDATA-V3</span></span>  
* <span data-ttu-id="d794b-115">BEC-INDLAND</span><span class="sxs-lookup"><span data-stu-id="d794b-115">BEC-INDLAND</span></span>  
* <span data-ttu-id="d794b-116">BEC-CSV</span><span class="sxs-lookup"><span data-stu-id="d794b-116">BEC-CSV</span></span>  
* <span data-ttu-id="d794b-117">DANSKEBANK-CMKV</span><span class="sxs-lookup"><span data-stu-id="d794b-117">DANSKEBANK-CMKV</span></span>  
* <span data-ttu-id="d794b-118">DANSKEBANK-CMKXKSX</span><span class="sxs-lookup"><span data-stu-id="d794b-118">DANSKEBANK-CMKXKSX</span></span>  
* <span data-ttu-id="d794b-119">DANSKEBANK</span><span class="sxs-lookup"><span data-stu-id="d794b-119">DANSKEBANK</span></span>  
* <span data-ttu-id="d794b-120">FIK71</span><span class="sxs-lookup"><span data-stu-id="d794b-120">FIK71</span></span>  
* <span data-ttu-id="d794b-121">NORDEA-ERHVERV-CSV</span><span class="sxs-lookup"><span data-stu-id="d794b-121">NORDEA-ERHVERV-CSV</span></span>  
* <span data-ttu-id="d794b-122">NORDEA</span><span class="sxs-lookup"><span data-stu-id="d794b-122">NORDEA</span></span>  
* <span data-ttu-id="d794b-123">NORDEA-UNITEL-V3</span><span class="sxs-lookup"><span data-stu-id="d794b-123">NORDEA-UNITEL-V3</span></span>  
* <span data-ttu-id="d794b-124">SDC</span><span class="sxs-lookup"><span data-stu-id="d794b-124">SDC</span></span>  
* <span data-ttu-id="d794b-125">SDC-CSV</span><span class="sxs-lookup"><span data-stu-id="d794b-125">SDC-CSV</span></span>  

## <a name="to-set-up-the-extension"></a><span data-ttu-id="d794b-126">To set up the extension</span><span class="sxs-lookup"><span data-stu-id="d794b-126">To set up the extension</span></span>

<span data-ttu-id="d794b-127">There are a few steps to get started.</span><span class="sxs-lookup"><span data-stu-id="d794b-127">There are a few steps to get started.</span></span>  

* <span data-ttu-id="d794b-128">Allow payment data exports.</span><span class="sxs-lookup"><span data-stu-id="d794b-128">Allow payment data exports.</span></span> <span data-ttu-id="d794b-129">To help protect your data, this is not readily available.</span><span class="sxs-lookup"><span data-stu-id="d794b-129">To help protect your data, this is not readily available.</span></span>  
* <span data-ttu-id="d794b-130">Set up purchase and payables so that you do not require external document numbers on invoices.</span><span class="sxs-lookup"><span data-stu-id="d794b-130">Set up purchase and payables so that you do not require external document numbers on invoices.</span></span> <span data-ttu-id="d794b-131">If needed, you can use the reference number to refer to a specific invoice.</span><span class="sxs-lookup"><span data-stu-id="d794b-131">If needed, you can use the reference number to refer to a specific invoice.</span></span>  
* <span data-ttu-id="d794b-132">Specify the payment method for each vendor.</span><span class="sxs-lookup"><span data-stu-id="d794b-132">Specify the payment method for each vendor.</span></span> <span data-ttu-id="d794b-133">Payment methods define how you pay invoices from the vendor.</span><span class="sxs-lookup"><span data-stu-id="d794b-133">Payment methods define how you pay invoices from the vendor.</span></span> <span data-ttu-id="d794b-134">For example, Bank, Cash, Cheque or Account.</span><span class="sxs-lookup"><span data-stu-id="d794b-134">For example, Bank, Cash, Check, or Account.</span></span>  
* <span data-ttu-id="d794b-135">Specify the type of format to use for each of your bank accounts.</span><span class="sxs-lookup"><span data-stu-id="d794b-135">Specify the type of format to use for each of your bank accounts.</span></span> <span data-ttu-id="d794b-136">For example, NORDEA, DANSKEBANK, SDC, and so on.</span><span class="sxs-lookup"><span data-stu-id="d794b-136">For example, NORDEA, DANSKEBANK, SDC, and so on.</span></span>  

<span data-ttu-id="d794b-137">Additionally, you must assign vendors to a domestic **Gen. Bus. Posting Group** and a **Vendor Posting Group**.</span><span class="sxs-lookup"><span data-stu-id="d794b-137">Additionally, you must assign vendors to a domestic **Gen. Bus. Posting Group** and a **Vendor Posting Group**.</span></span> <span data-ttu-id="d794b-138">The Country/Region setting for the vendor must be Denmark (DK).</span><span class="sxs-lookup"><span data-stu-id="d794b-138">The Country/Region setting for the vendor must be Denmark (DK).</span></span> <span data-ttu-id="d794b-139">For more information, see [Setting Up Posting Groups](finance-posting-groups.md).</span><span class="sxs-lookup"><span data-stu-id="d794b-139">For more information, see [Setting Up Posting Groups](finance-posting-groups.md).</span></span>  

### <a name="to-allow-prod_short-to-export-payment-data"></a><span data-ttu-id="d794b-140">To allow [!INCLUDE[prod_short](includes/prod_short.md)] to export payment data</span><span class="sxs-lookup"><span data-stu-id="d794b-140">To allow [!INCLUDE[prod_short](includes/prod_short.md)] to export payment data</span></span>

1. <span data-ttu-id="d794b-141">Choose the ![Lightbulb that opens the Tell Me feature](media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Payment Journal**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="d794b-141">Choose the ![Lightbulb that opens the Tell Me feature](media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Payment Journal**, and then choose the related link.</span></span>  
2. <span data-ttu-id="d794b-142">On the **Edit Payment Journal** page, choose the **Bank** batch.</span><span class="sxs-lookup"><span data-stu-id="d794b-142">On the **Edit Payment Journal** page, choose the **Bank** batch.</span></span>  
3. <span data-ttu-id="d794b-143">Choose the **Allow Payment Export** check box.</span><span class="sxs-lookup"><span data-stu-id="d794b-143">Choose the **Allow Payment Export** check box.</span></span>  

### <a name="to-specify-a-payment-method-for-a-vendor"></a><span data-ttu-id="d794b-144">To specify a payment method for a vendor</span><span class="sxs-lookup"><span data-stu-id="d794b-144">To specify a payment method for a vendor</span></span>

<span data-ttu-id="d794b-145">The following table shows the combinations of FIK and GIRO payment methods that [!INCLUDE[prod_short](includes/prod_short.md)] supports.</span><span class="sxs-lookup"><span data-stu-id="d794b-145">The following table shows the combinations of FIK and GIRO payment methods that [!INCLUDE[prod_short](includes/prod_short.md)] supports.</span></span>

|<span data-ttu-id="d794b-146">Combination</span><span class="sxs-lookup"><span data-stu-id="d794b-146">Combination</span></span>|<span data-ttu-id="d794b-147">Type 01</span><span class="sxs-lookup"><span data-stu-id="d794b-147">Type 01</span></span> | <span data-ttu-id="d794b-148">Type 04</span><span class="sxs-lookup"><span data-stu-id="d794b-148">Type 04</span></span> | <span data-ttu-id="d794b-149">Type 71</span><span class="sxs-lookup"><span data-stu-id="d794b-149">Type 71</span></span> | <span data-ttu-id="d794b-150">Type 73</span><span class="sxs-lookup"><span data-stu-id="d794b-150">Type 73</span></span> |
|----|--------|---------|---------|---------|
|<span data-ttu-id="d794b-151">Giro Account No. or FIK Creditor No.?</span><span class="sxs-lookup"><span data-stu-id="d794b-151">Giro Account No. or FIK Creditor No.?</span></span> | <span data-ttu-id="d794b-152">Giro Account No.</span><span class="sxs-lookup"><span data-stu-id="d794b-152">Giro Account No.</span></span> | <span data-ttu-id="d794b-153">Giro Account No.</span><span class="sxs-lookup"><span data-stu-id="d794b-153">Giro Account No.</span></span> | <span data-ttu-id="d794b-154">FIK Creditor No.</span><span class="sxs-lookup"><span data-stu-id="d794b-154">FIK Creditor No.</span></span> | <span data-ttu-id="d794b-155">FIK Creditor No.</span><span class="sxs-lookup"><span data-stu-id="d794b-155">FIK Creditor No.</span></span>|
|<span data-ttu-id="d794b-156">Allows Message to Recipient?</span><span class="sxs-lookup"><span data-stu-id="d794b-156">Allows Message to Recipient?</span></span> | <span data-ttu-id="d794b-157">Yes</span><span class="sxs-lookup"><span data-stu-id="d794b-157">Yes</span></span> |<span data-ttu-id="d794b-158">No</span><span class="sxs-lookup"><span data-stu-id="d794b-158">No</span></span> |<span data-ttu-id="d794b-159">No</span><span class="sxs-lookup"><span data-stu-id="d794b-159">No</span></span> | <span data-ttu-id="d794b-160">Yes</span><span class="sxs-lookup"><span data-stu-id="d794b-160">Yes</span></span> |
|<span data-ttu-id="d794b-161">Contains Payment Reference number?</span><span class="sxs-lookup"><span data-stu-id="d794b-161">Contains Payment Reference number?</span></span> | <span data-ttu-id="d794b-162">No</span><span class="sxs-lookup"><span data-stu-id="d794b-162">No</span></span> | <span data-ttu-id="d794b-163">Yes, 16 digits.</span><span class="sxs-lookup"><span data-stu-id="d794b-163">Yes, 16 digits.</span></span> | <span data-ttu-id="d794b-164">Yes, 15 digits.</span><span class="sxs-lookup"><span data-stu-id="d794b-164">Yes, 15 digits.</span></span> | <span data-ttu-id="d794b-165">No</span><span class="sxs-lookup"><span data-stu-id="d794b-165">No</span></span>|

1. <span data-ttu-id="d794b-166">Choose the ![Lightbulb that opens the Tell Me feature](media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Vendors**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="d794b-166">Choose the ![Lightbulb that opens the Tell Me feature](media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Vendors**, and then choose the related link.</span></span>  
2. <span data-ttu-id="d794b-167">Open the card, expand the **Payments** tab, in the **Payment Method** field choose the payment method.</span><span class="sxs-lookup"><span data-stu-id="d794b-167">Open the card, expand the **Payments** tab, in the **Payment Method** field choose the payment method.</span></span>  
3. <span data-ttu-id="d794b-168">Depending on your selection, you must complete other fields.</span><span class="sxs-lookup"><span data-stu-id="d794b-168">Depending on your selection, you must complete other fields.</span></span> <span data-ttu-id="d794b-169">See the table above for a description of the combinations.</span><span class="sxs-lookup"><span data-stu-id="d794b-169">See the table above for a description of the combinations.</span></span>  

### <a name="to-specify-the-format-to-use-for-a-bank-account"></a><span data-ttu-id="d794b-170">To specify the format to use for a bank account</span><span class="sxs-lookup"><span data-stu-id="d794b-170">To specify the format to use for a bank account</span></span>

1. <span data-ttu-id="d794b-171">Choose the ![Lightbulb that opens the Tell Me feature](media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Bank Accounts**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="d794b-171">Choose the ![Lightbulb that opens the Tell Me feature](media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Bank Accounts**, and then choose the related link.</span></span>  
2. <span data-ttu-id="d794b-172">Open the card for the bank account.</span><span class="sxs-lookup"><span data-stu-id="d794b-172">Open the card for the bank account.</span></span>  
3. <span data-ttu-id="d794b-173">In the **Payment Export Format** field, choose the format for your export file.</span><span class="sxs-lookup"><span data-stu-id="d794b-173">In the **Payment Export Format** field, choose the format for your export file.</span></span>  

## <a name="choosing-the-fik-or-giro-payment-information-for-vendor-invoices"></a><span data-ttu-id="d794b-174">Choosing the FIK or Giro payment information for vendor invoices</span><span class="sxs-lookup"><span data-stu-id="d794b-174">Choosing the FIK or Giro payment information for vendor invoices</span></span>

1. <span data-ttu-id="d794b-175">Choose the ![Lightbulb that opens the Tell Me feature](media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Purchase Invoices**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="d794b-175">Choose the ![Lightbulb that opens the Tell Me feature](media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Purchase Invoices**, and then choose the related link.</span></span>
2. <span data-ttu-id="d794b-176">Choose the vendor.</span><span class="sxs-lookup"><span data-stu-id="d794b-176">Choose the vendor.</span></span> <span data-ttu-id="d794b-177">Remember, this must be a Danish vendor with an address in Denmark.</span><span class="sxs-lookup"><span data-stu-id="d794b-177">Remember, this must be a Danish vendor with an address in Denmark.</span></span>
3. <span data-ttu-id="d794b-178">Create an invoice.</span><span class="sxs-lookup"><span data-stu-id="d794b-178">Create an invoice.</span></span> <span data-ttu-id="d794b-179">The **Payment Method** and **Vendor Number** fields are filled in based on settings on the Vendor card.</span><span class="sxs-lookup"><span data-stu-id="d794b-179">The **Payment Method** and **Vendor Number** fields are filled in based on settings on the Vendor card.</span></span> <span data-ttu-id="d794b-180">You can change them if you want.</span><span class="sxs-lookup"><span data-stu-id="d794b-180">You can change them if you want.</span></span>
4. <span data-ttu-id="d794b-181">In the **Payment Reference** field, enter the 15-digit number from the vendor invoice.</span><span class="sxs-lookup"><span data-stu-id="d794b-181">In the **Payment Reference** field, enter the 15-digit number from the vendor invoice.</span></span>  

    > [!Tip]
    > <span data-ttu-id="d794b-182">You only have to add the last 11 digits of the number.</span><span class="sxs-lookup"><span data-stu-id="d794b-182">You only have to add the last 11 digits of the number.</span></span> [!INCLUDE[prod_short](includes/prod_short.md)] <span data-ttu-id="d794b-183">will add four zeros to the beginning of the number.</span><span class="sxs-lookup"><span data-stu-id="d794b-183">will add four zeros to the beginning of the number.</span></span>  

5. <span data-ttu-id="d794b-184">Post the invoice.</span><span class="sxs-lookup"><span data-stu-id="d794b-184">Post the invoice.</span></span>

## <a name="to-use-the-extension-to-export-payment-data"></a><span data-ttu-id="d794b-185">To use the extension to export payment data</span><span class="sxs-lookup"><span data-stu-id="d794b-185">To use the extension to export payment data</span></span>

1. <span data-ttu-id="d794b-186">Choose the ![Lightbulb that opens the Tell Me feature](media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Payment Journals**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="d794b-186">Choose the ![Lightbulb that opens the Tell Me feature](media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Payment Journals**, and then choose the related link.</span></span>  
2. <span data-ttu-id="d794b-187">Choose the **Suggest Vendor Payment Journals** action.</span><span class="sxs-lookup"><span data-stu-id="d794b-187">Choose the **Suggest Vendor Payment Journals** action.</span></span>  

    > [!Tip]
    > <span data-ttu-id="d794b-188">If you want to export only specific payments, use the options for filtering the data.</span><span class="sxs-lookup"><span data-stu-id="d794b-188">If you want to export only specific payments, use the options for filtering the data.</span></span>  

3. <span data-ttu-id="d794b-189">If needed, you can add filters to export only specific payments.</span><span class="sxs-lookup"><span data-stu-id="d794b-189">If needed, you can add filters to export only specific payments.</span></span>  
4. <span data-ttu-id="d794b-190">In the **Bank Payment Type** field, choose **Electronic Payment**.</span><span class="sxs-lookup"><span data-stu-id="d794b-190">In the **Bank Payment Type** field, choose **Electronic Payment**.</span></span>  
5. <span data-ttu-id="d794b-191">Choose the **Export** action.</span><span class="sxs-lookup"><span data-stu-id="d794b-191">Choose the **Export** action.</span></span>  

## <a name="see-also"></a><span data-ttu-id="d794b-192">See also</span><span class="sxs-lookup"><span data-stu-id="d794b-192">See also</span></span>

<span data-ttu-id="d794b-193">[Customising Business Central for [!INCLUDE[prod_short](includes/prod_short.md)] Using Extensions](ui-extensions.md)</span><span class="sxs-lookup"><span data-stu-id="d794b-193">[Customizing Business Central for [!INCLUDE[prod_short](includes/prod_short.md)] Using Extensions](ui-extensions.md)</span></span>  
[<span data-ttu-id="d794b-194">Collect Payments with SEPA Direct Debit</span><span class="sxs-lookup"><span data-stu-id="d794b-194">Collect Payments with SEPA Direct Debit</span></span>](finance-collect-payments-with-sepa-direct-debit.md)  
[<span data-ttu-id="d794b-195">Working with General Journals</span><span class="sxs-lookup"><span data-stu-id="d794b-195">Working with General Journals</span></span>](ui-work-general-journals.md)  


[!INCLUDE[footer-include](includes/footer-banner.md)]