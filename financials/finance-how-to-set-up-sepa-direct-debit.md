---
title: Set up SEPA Direct Debit | Microsoft Docs
description: Learn how to set up SEPA Direct Debit in Dynamics 365 Business edition .
author: SorenGP
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/21/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: ba26b354d235981bd7291f9ac6402779f554ac7a
ms.openlocfilehash: 96c851c58decbeb46afcd79a9c5275d16c8072d4
ms.contentlocale: en-au
ms.lasthandoff: 11/10/2017

---
# <a name="how-to-set-up-sepa-direct-debit"></a><span data-ttu-id="8187d-103">How to: Set Up SEPA Direct Debit</span><span class="sxs-lookup"><span data-stu-id="8187d-103">How to: Set Up SEPA Direct Debit</span></span>
<span data-ttu-id="8187d-104">From the **Direct Debit Collections** window, you can export instructions to your electronic bank to perform a direct debit collection from the customer’s bank account to your bank account.</span><span class="sxs-lookup"><span data-stu-id="8187d-104">From the **Direct Debit Collections** window, you can export instructions to your electronic bank to perform a direct debit collection from the customer’s bank account to your bank account.</span></span> [!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="8187d-105"> supports the SEPA direct debit format, but in your country/region, other formats for electronic payments may be available.</span><span class="sxs-lookup"><span data-stu-id="8187d-105"> supports the SEPA direct debit format, but in your country/region,other formats for electronic payments may be available.</span></span>  

<span data-ttu-id="8187d-106">To enable export of a bank file formats that are not supported out of the box in [!INCLUDE[d365fin](includes/d365fin_md.md)] , you can set up a data exchange definition by using the data exchange framework.</span><span class="sxs-lookup"><span data-stu-id="8187d-106">To enable export of a bank file formats that are not supported out of the box in [!INCLUDE[d365fin](includes/d365fin_md.md)] , you can set up a data exchange definition by using the data exchange framework.</span></span> <span data-ttu-id="8187d-107">For more information, see [How to: Set Up Data Exchange Definitions](across-how-to-set-up-data-exchange-definitions.md).</span><span class="sxs-lookup"><span data-stu-id="8187d-107">For more information, see [How to: Set Up Data Exchange Definitions](across-how-to-set-up-data-exchange-definitions.md).</span></span>  

<span data-ttu-id="8187d-108">Before you can process customer payments electronically by exporting direct debit instructions in the SEPA Direct Debit format, you must perform the following setup steps:</span><span class="sxs-lookup"><span data-stu-id="8187d-108">Before you can process customer payments electronically by exporting direct debit instructions in the SEPA Direct Debit format, you must perform the following setup steps:</span></span>  

* <span data-ttu-id="8187d-109">Set up the export format of the bank file that instructs your bank to perform a direct debit collection from the customer’s bank account to your bank account.</span><span class="sxs-lookup"><span data-stu-id="8187d-109">Set up the export format of the bank file that instructs your bank to perform a direct debit collection from the customer’s bank account to your bank account.</span></span>  
* <span data-ttu-id="8187d-110">Set up the customer’s payment method.</span><span class="sxs-lookup"><span data-stu-id="8187d-110">Set up the customer’s payment method.</span></span>  
* <span data-ttu-id="8187d-111">Set up the direct-debit mandate that reflects your agreement with the customer to collect their payments in a certain agreement period.</span><span class="sxs-lookup"><span data-stu-id="8187d-111">Set up the direct-debit mandate that reflects your agreement with the customer to collect their payments in a certain agreement period.</span></span>  

### <a name="to-set-up-your-bank-account-for-sepa-direct-debit"></a><span data-ttu-id="8187d-112">To set up your bank account for SEPA direct debit</span><span class="sxs-lookup"><span data-stu-id="8187d-112">To set up your bank account for SEPA direct debit</span></span>  
1. <span data-ttu-id="8187d-113">In the **Search** box, enter **Bank Accounts**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="8187d-113">In the **Search** box, enter **Bank Accounts**, and then choose the related link.</span></span>  
2. <span data-ttu-id="8187d-114">Open the bank account that you want to use for direct debit.</span><span class="sxs-lookup"><span data-stu-id="8187d-114">Open the bank account that you want to use for direct debit.</span></span>  
3. <span data-ttu-id="8187d-115">On the **Transfer** FastTab, in the **SEPA Direct Debit Export Format** field, choose the option for SEPA direct debit.</span><span class="sxs-lookup"><span data-stu-id="8187d-115">On the **Transfer** FastTab, in the **SEPA Direct Debit Export Format** field, choose the option for SEPA direct debit.</span></span>  

### <a name="to-set-up-the-customers-payment-method-for-sepa-direct-debit"></a><span data-ttu-id="8187d-116">To set up the customer’s payment method for SEPA direct debit</span><span class="sxs-lookup"><span data-stu-id="8187d-116">To set up the customer’s payment method for SEPA direct debit</span></span>  
1. <span data-ttu-id="8187d-117">In the **Search** box, enter **Payment Methods**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="8187d-117">In the **Search** box, enter **Payment Methods**, and then choose the related link.</span></span>  
2. <span data-ttu-id="8187d-118">Choose the **New** action.</span><span class="sxs-lookup"><span data-stu-id="8187d-118">Choose the **New** action.</span></span>  
3. <span data-ttu-id="8187d-119">Set up a payment method.</span><span class="sxs-lookup"><span data-stu-id="8187d-119">Set up a payment method.</span></span> <span data-ttu-id="8187d-120">Fill in the direct debit\-specific fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="8187d-120">Fill in the direct debit\-specific fields as described in the following table.</span></span>  

    |<span data-ttu-id="8187d-121">Field</span><span class="sxs-lookup"><span data-stu-id="8187d-121">Field</span></span>|<span data-ttu-id="8187d-122">Description</span><span class="sxs-lookup"><span data-stu-id="8187d-122">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="8187d-123">**Direct Debit**</span><span class="sxs-lookup"><span data-stu-id="8187d-123">**Direct Debit**</span></span>|<span data-ttu-id="8187d-124">Specify if the payment method is for SEPA direct debit collection.</span><span class="sxs-lookup"><span data-stu-id="8187d-124">Specify if the payment method is for SEPA direct debit collection.</span></span>|  
    |<span data-ttu-id="8187d-125">**Direct Debit Pmt. Terms Code**</span><span class="sxs-lookup"><span data-stu-id="8187d-125">**Direct Debit Pmt. Terms Code**</span></span>|<span data-ttu-id="8187d-126">Specify the payment terms, such as DON’T PAY, that are displayed on sales invoices that are paid with SEPA direct debit to indicate to the customer that the payment will be collected automatically.</span><span class="sxs-lookup"><span data-stu-id="8187d-126">Specify the payment terms, such as DON’T PAY, that are displayed on sales invoices that are paid with SEPA direct debit to indicate to the customer that the payment will be collected automatically.</span></span> <span data-ttu-id="8187d-127">Alternatively, leave the field empty.</span><span class="sxs-lookup"><span data-stu-id="8187d-127">Alternatively, leave the field empty.</span></span>|  

    > [!NOTE]  
    >  <span data-ttu-id="8187d-128">Do not enter a value in the **Bal. Account No.** field.</span><span class="sxs-lookup"><span data-stu-id="8187d-128">Do not enter a value in the **Bal. Account No.** field.</span></span>  

4. <span data-ttu-id="8187d-129">Choose the **OK** button to close the **Payment Methods** window.</span><span class="sxs-lookup"><span data-stu-id="8187d-129">Choose the **OK** button to close the **Payment Methods** window.</span></span>  
5. <span data-ttu-id="8187d-130">In the **Search** box, enter **Customers**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="8187d-130">In the **Search** box, enter **Customers**, and then choose the related link.</span></span>  
6. <span data-ttu-id="8187d-131">Open the customer card for the customer that you want to set up for SEPA direct debit collection.</span><span class="sxs-lookup"><span data-stu-id="8187d-131">Open the customer card for the customer that you want to set up for SEPA direct debit collection.</span></span>  
7. <span data-ttu-id="8187d-132">Choose the **Payment Method Code** field, and then select the payment method code that you specified in step 3.</span><span class="sxs-lookup"><span data-stu-id="8187d-132">Choose the **Payment Method Code** field, and then select the payment method code that you specified in step 3.</span></span>  
8. <span data-ttu-id="8187d-133">Repeat steps 6 and 7 for all customers that you want to set up for SEPA direct debit collection.</span><span class="sxs-lookup"><span data-stu-id="8187d-133">Repeat steps 6 and 7 for all customers that you want to set up for SEPA direct debit collection.</span></span>  

#### <a name="to-set-up-the-direct-debit-mandate-that-represents-the-customer-agreement"></a><span data-ttu-id="8187d-134">To set up the direct-debit mandate that represents the customer agreement</span><span class="sxs-lookup"><span data-stu-id="8187d-134">To set up the direct-debit mandate that represents the customer agreement</span></span>  
1. <span data-ttu-id="8187d-135">In the **Search** box, enter **Customers**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="8187d-135">In the **Search** box, enter **Customers**, and then choose the related link.</span></span>  
2. <span data-ttu-id="8187d-136">Open the card for the customer that you want to set up for SEPA direct debits.</span><span class="sxs-lookup"><span data-stu-id="8187d-136">Open the card for the customer that you want to set up for SEPA direct debits.</span></span>  
3. <span data-ttu-id="8187d-137">Choose the **Bank Accounts** action.</span><span class="sxs-lookup"><span data-stu-id="8187d-137">Choose the **Bank Accounts** action.</span></span>  
4. <span data-ttu-id="8187d-138">In the **Customer Bank Account List** window, select the customer bank account that will use direct debits, and then, on the **Home** tab, in the **Process** group, choose **Direct Debit Mandates**.</span><span class="sxs-lookup"><span data-stu-id="8187d-138">In the **Customer Bank Account List** window, select the customer bank account that will use direct debits, and then, on the **Home** tab, in the **Process** group, choose **Direct Debit Mandates**.</span></span>  
5. <span data-ttu-id="8187d-139">In the **SEPA Direct Debit Mandates** window, fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="8187d-139">In the **SEPA Direct Debit Mandates** window, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="8187d-140">Field</span><span class="sxs-lookup"><span data-stu-id="8187d-140">Field</span></span>|<span data-ttu-id="8187d-141">Description</span><span class="sxs-lookup"><span data-stu-id="8187d-141">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="8187d-142">**Customer Bank Account Code**</span><span class="sxs-lookup"><span data-stu-id="8187d-142">**Customer Bank Account Code**</span></span>|<span data-ttu-id="8187d-143">Specifies the bank account from which direct\-debit payments are collected.</span><span class="sxs-lookup"><span data-stu-id="8187d-143">Specifies the bank account from which direct\-debit payments are collected.</span></span> <span data-ttu-id="8187d-144">This field is filled automatically.</span><span class="sxs-lookup"><span data-stu-id="8187d-144">This field is filled automatically.</span></span>|  
    |<span data-ttu-id="8187d-145">**Valid From**</span><span class="sxs-lookup"><span data-stu-id="8187d-145">**Valid From**</span></span>|<span data-ttu-id="8187d-146">Specify the date when the direct\-debit mandate starts.</span><span class="sxs-lookup"><span data-stu-id="8187d-146">Specify the date when the direct\-debit mandate starts.</span></span>|  
    |<span data-ttu-id="8187d-147">**Valid To**</span><span class="sxs-lookup"><span data-stu-id="8187d-147">**Valid To**</span></span>|<span data-ttu-id="8187d-148">Specify the date when the direct\-debit mandate ends.</span><span class="sxs-lookup"><span data-stu-id="8187d-148">Specify the date when the direct\-debit mandate ends.</span></span>|  
    |<span data-ttu-id="8187d-149">**Date of Signature**</span><span class="sxs-lookup"><span data-stu-id="8187d-149">**Date of Signature**</span></span>|<span data-ttu-id="8187d-150">Specify the date when the customer signed the direct\-debit mandate.</span><span class="sxs-lookup"><span data-stu-id="8187d-150">Specify the date when the customer signed the direct\-debit mandate.</span></span>|  
    |<span data-ttu-id="8187d-151">**Sequence Type**</span><span class="sxs-lookup"><span data-stu-id="8187d-151">**Sequence Type**</span></span>|<span data-ttu-id="8187d-152">Specify if the agreement covers multiple (**Recurring**) or a single (**One Off**) direct debit collection.</span><span class="sxs-lookup"><span data-stu-id="8187d-152">Specify if the agreement covers multiple (**Recurring**) or a single (**One Off**) direct debit collection.</span></span>|  
    |<span data-ttu-id="8187d-153">**Expected Number of Debits**</span><span class="sxs-lookup"><span data-stu-id="8187d-153">**Expected Number of Debits**</span></span>|<span data-ttu-id="8187d-154">Specify how many direct debit collections you expect to make.</span><span class="sxs-lookup"><span data-stu-id="8187d-154">Specify how many direct debit collections you expect to make.</span></span> <span data-ttu-id="8187d-155">This field is only relevant if you selected **Recurring** in the **Sequence Type** field.</span><span class="sxs-lookup"><span data-stu-id="8187d-155">This field is only relevant if you selected **Recurring** in the **Sequence Type** field.</span></span>|  
    |<span data-ttu-id="8187d-156">**Debit Counter**</span><span class="sxs-lookup"><span data-stu-id="8187d-156">**Debit Counter**</span></span>|<span data-ttu-id="8187d-157">Specifies how many direct debit collections have been made using this direct\-debit mandate.</span><span class="sxs-lookup"><span data-stu-id="8187d-157">Specifies how many direct debit collections have been made using this direct\-debit mandate.</span></span> <span data-ttu-id="8187d-158">This field is automatically updated.</span><span class="sxs-lookup"><span data-stu-id="8187d-158">This field is automatically updated.</span></span>|  
    |<span data-ttu-id="8187d-159">**Blocked**</span><span class="sxs-lookup"><span data-stu-id="8187d-159">**Blocked**</span></span>|<span data-ttu-id="8187d-160">Specify that direct debit collections cannot be made using this direct\-debit mandate.</span><span class="sxs-lookup"><span data-stu-id="8187d-160">Specify that direct debit collections cannot be made using this direct\-debit mandate.</span></span>|  

6.  <span data-ttu-id="8187d-161">Repeat steps 1 through 5 for all customers that you want to set up for SEPA direct debits.</span><span class="sxs-lookup"><span data-stu-id="8187d-161">Repeat steps 1 through 5 for all customers that you want to set up for SEPA direct debits.</span></span>  

 <span data-ttu-id="8187d-162">The direct-debit mandate is automatically inserted in the **Direct Debit Mandate ID** field when you create a sales invoice for the customer that you selected in step 2.</span><span class="sxs-lookup"><span data-stu-id="8187d-162">The direct-debit mandate is automatically inserted in the **Direct Debit Mandate ID** field when you create a sales invoice for the customer that you selected in step 2.</span></span> <span data-ttu-id="8187d-163">For more information, see [How to: Create Recurring Sales and Purchase Lines](sales-how-work-standard-lines.md).</span><span class="sxs-lookup"><span data-stu-id="8187d-163">For more information, see [How to: Create Recurring Sales and Purchase Lines](sales-how-work-standard-lines.md).</span></span>  

## <a name="see-also"></a><span data-ttu-id="8187d-164">See Also</span><span class="sxs-lookup"><span data-stu-id="8187d-164">See Also</span></span>  
[<span data-ttu-id="8187d-165">Collecting Payments with SEPA Direct Debit</span><span class="sxs-lookup"><span data-stu-id="8187d-165">Collecting Payments with SEPA Direct Debit</span></span>](finance-collect-payments-with-sepa-direct-debit.md)  
<span data-ttu-id="8187d-166">[How to: Set Up Data Exchange Definitions](across-how-to-set-up-data-exchange-definitions.md)
[How to: Create Recurring Sales and Purchase Lines](sales-how-work-standard-lines.md)
[Exchanging Data Electronically](across-data-exchange.md)</span><span class="sxs-lookup"><span data-stu-id="8187d-166">[How to: Set Up Data Exchange Definitions](across-how-to-set-up-data-exchange-definitions.md)
[How to: Create Recurring Sales and Purchase Lines](sales-how-work-standard-lines.md)
[Exchanging Data Electronically](across-data-exchange.md)</span></span>
