---
title: Consolidate Data from Multiple Companies | Microsoft Docs
description: Get an summary view of the financial health accross your businesses.
documentationcenter: 
author: bholtorf
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: consolidation, subsidiaries, consolidate
ms.date: 07/14/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: ba26b354d235981bd7291f9ac6402779f554ac7a
ms.openlocfilehash: 9739f89c45dd63d03235fef4204b2adeb48ac4d3
ms.contentlocale: en-au
ms.lasthandoff: 11/10/2017

---

# <a name="how-to-work-with-the-consolidated-trial-balance-report"></a><span data-ttu-id="50b36-103">How To: Work with the Consolidated Trial Balance Report</span><span class="sxs-lookup"><span data-stu-id="50b36-103">How To: Work with the Consolidated Trial Balance Report</span></span>
<span data-ttu-id="50b36-104">If you have more than one company in [!INCLUDE[d365fin](includes/d365fin_md.md)], the Consolidated Trial Balance Report on the Accountant Role Centre can give you an overview of the financial health of your overall business.</span><span class="sxs-lookup"><span data-stu-id="50b36-104">If you have more than one company in [!INCLUDE[d365fin](includes/d365fin_md.md)], the Consolidated Trial Balance Report on the Accountant Role Center can give you an overview of the financial health of your overall business.</span></span>  

<span data-ttu-id="50b36-105">The report combines general ledger (G/L) entries from each of your companies in a new company that you create to contain the consolidated data.</span><span class="sxs-lookup"><span data-stu-id="50b36-105">The report combines general ledger (G/L) entries from each of your companies in a new company that you create to contain the consolidated data.</span></span> <span data-ttu-id="50b36-106">This company is typically referred to as the "consolidated company."</span><span class="sxs-lookup"><span data-stu-id="50b36-106">This company is typically referred to as the "consolidated company."</span></span> <span data-ttu-id="50b36-107">The consolidated company is just a container for the consolidated data, and does not have any live business data.</span><span class="sxs-lookup"><span data-stu-id="50b36-107">The consolidated company is just a container for the consolidated data, and does not have any live business data.</span></span> <span data-ttu-id="50b36-108">The companies that you include in the consolidated company become **Business Units** in the report.</span><span class="sxs-lookup"><span data-stu-id="50b36-108">The companies that you include in the consolidated company become **Business Units** in the report.</span></span>

<span data-ttu-id="50b36-109">You can consolidate:</span><span class="sxs-lookup"><span data-stu-id="50b36-109">You can consolidate:</span></span>  

* <span data-ttu-id="50b36-110">Across companies that have different charts of accounts.</span><span class="sxs-lookup"><span data-stu-id="50b36-110">Across companies that have different charts of accounts.</span></span>  
* <span data-ttu-id="50b36-111">Companies that use different fiscal years and different currencies.</span><span class="sxs-lookup"><span data-stu-id="50b36-111">Companies that use different fiscal years and different currencies.</span></span>  
* <span data-ttu-id="50b36-112">Either the full amount or a percentage of a company's financial information</span><span class="sxs-lookup"><span data-stu-id="50b36-112">Either the full amount or a percentage of a company's financial information</span></span>
* <span data-ttu-id="50b36-113">Using different currency exchange rates in individual G/L accounts</span><span class="sxs-lookup"><span data-stu-id="50b36-113">Using different currency exchange rates in individual G/L accounts</span></span>

<span data-ttu-id="50b36-114">Depending on the complexity of your businesses, there are two ways to set up the report:</span><span class="sxs-lookup"><span data-stu-id="50b36-114">Depending on the complexity of your businesses, there are two ways to set up the report:</span></span>

* <span data-ttu-id="50b36-115">If you don't need advanced settings, such as including a company that you only own part of, you can use the **Company Consolidation** assisted setup guide to quickly set up a consolidation.</span><span class="sxs-lookup"><span data-stu-id="50b36-115">If you don't need advanced settings, such as including a company that you only own part of, you can use the **Company Consolidation** assisted setup guide to quickly set up a consolidation.</span></span> <span data-ttu-id="50b36-116">The guide helps you through the basic steps.</span><span class="sxs-lookup"><span data-stu-id="50b36-116">The guide helps you through the basic steps.</span></span>
* <span data-ttu-id="50b36-117">If you do need more advanced settings, you can set up the consolidated company and business units yourself.</span><span class="sxs-lookup"><span data-stu-id="50b36-117">If you do need more advanced settings, you can set up the consolidated company and business units yourself.</span></span>

## <a name="to-do-a-simple-consolidation-setup"></a><span data-ttu-id="50b36-118">To do a simple consolidation setup</span><span class="sxs-lookup"><span data-stu-id="50b36-118">To do a simple consolidation setup</span></span>
<span data-ttu-id="50b36-119">If your consolidation is straightforward, for example because you wholly-own the business units to consolidate, the **Company Consolidation** assisted setup guide will help you through the following steps:</span><span class="sxs-lookup"><span data-stu-id="50b36-119">If your consolidation is straightforward, for example because you wholly-own the business units to consolidate, the **Company Consolidation** assisted setup guide will help you through the following steps:</span></span>

* <span data-ttu-id="50b36-120">Choose whether to create a new consolidated company, or whether to consolidate the data in a company that you have already created for the consolidation.</span><span class="sxs-lookup"><span data-stu-id="50b36-120">Choose whether to create a new consolidated company, or whether to consolidate the data in a company that you have already created for the consolidation.</span></span> <span data-ttu-id="50b36-121">The company should not contain transactions.</span><span class="sxs-lookup"><span data-stu-id="50b36-121">The company should not contain transactions.</span></span>
* <span data-ttu-id="50b36-122">Preview the results.</span><span class="sxs-lookup"><span data-stu-id="50b36-122">Preview the results.</span></span> [!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="50b36-123"> verifies that the master data and transactions can be successfully transferred to the consolidated company.</span><span class="sxs-lookup"><span data-stu-id="50b36-123"> verifies that the master data and transactions can be successfully transferred to the consolidated company.</span></span>

<span data-ttu-id="50b36-124">To use the assisted setup guide, follow these steps:</span><span class="sxs-lookup"><span data-stu-id="50b36-124">To use the assisted setup guide, follow these steps:</span></span>

1. <span data-ttu-id="50b36-125">On the **Accountant** Role Centre, choose the **Assisted Setup** action.</span><span class="sxs-lookup"><span data-stu-id="50b36-125">On the **Accountant** Role Center, choose the **Assisted Setup** action.</span></span>
2. <span data-ttu-id="50b36-126">Choose **Set up consolidation reporting**, and then complete each step in the assisted setup guide.</span><span class="sxs-lookup"><span data-stu-id="50b36-126">Choose **Set up consolidation reporting**, and then complete each step in the assisted setup guide.</span></span>

## <a name="to-do-an-advanced-consolidation-setup"></a><span data-ttu-id="50b36-127">To do an advanced consolidation setup</span><span class="sxs-lookup"><span data-stu-id="50b36-127">To do an advanced consolidation setup</span></span>
<span data-ttu-id="50b36-128">If you need more advanced settings for your consolidation, you can set up consolidation manually.</span><span class="sxs-lookup"><span data-stu-id="50b36-128">If you need more advanced settings for your consolidation, you can set up consolidation manually.</span></span> <span data-ttu-id="50b36-129">For example, if you have companies that you own only partially, or you have companies that you don’t want to include in the consolidation.</span><span class="sxs-lookup"><span data-stu-id="50b36-129">For example, if you have companies that you own only partially, or you have companies that you don’t want to include in the consolidation.</span></span> <span data-ttu-id="50b36-130">You set up the consolidated company in the say way that you set up other companies.</span><span class="sxs-lookup"><span data-stu-id="50b36-130">You set up the consolidated company in the say way that you set up other companies.</span></span> <span data-ttu-id="50b36-131">For more information, see [Getting Ready for Doing Business](ui-get-ready-business.md).</span><span class="sxs-lookup"><span data-stu-id="50b36-131">For more information, see [Getting Ready for Doing Business](ui-get-ready-business.md).</span></span>  

[!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="50b36-132"> lets you set up a list of companies to consolidate, verify the accounting data before you consolidate it, import files, and generate consolidation reports.</span><span class="sxs-lookup"><span data-stu-id="50b36-132"> lets you set up a list of companies to consolidate, verify the accounting data before you consolidate it, import files, and generate consolidation reports.</span></span>  

1. <span data-ttu-id="50b36-133">Sign in to the consolidated company.</span><span class="sxs-lookup"><span data-stu-id="50b36-133">Sign in to the consolidated company.</span></span>
2. <span data-ttu-id="50b36-134">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Business Units**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="50b36-134">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Business Units**, and then choose the related link.</span></span>  
3. <span data-ttu-id="50b36-135">Choose **New**, and then fill in the required fields.</span><span class="sxs-lookup"><span data-stu-id="50b36-135">Choose **New**, and then fill in the required fields.</span></span>  

<span data-ttu-id="50b36-136">If your business unit uses a foreign currency, you must specify the exchange rate to use in the consolidation.</span><span class="sxs-lookup"><span data-stu-id="50b36-136">If your business unit uses a foreign currency, you must specify the exchange rate to use in the consolidation.</span></span> <span data-ttu-id="50b36-137">You must also enter consolidation information about the business unit's general ledger accounts.</span><span class="sxs-lookup"><span data-stu-id="50b36-137">You must also enter consolidation information about the business unit's general ledger accounts.</span></span> <span data-ttu-id="50b36-138">These processes are described in the following sections.</span><span class="sxs-lookup"><span data-stu-id="50b36-138">These processes are described in the following sections.</span></span>

### <a name="to-prepare-general-ledger-accounts-for-consolidation"></a><span data-ttu-id="50b36-139">To prepare general ledger accounts for consolidation</span><span class="sxs-lookup"><span data-stu-id="50b36-139">To prepare general ledger accounts for consolidation</span></span>
<span data-ttu-id="50b36-140">If the chart of accounts in the business unit differs from the consolidated company, you must prepare general ledger accounts for consolidation.</span><span class="sxs-lookup"><span data-stu-id="50b36-140">If the chart of accounts in the business unit differs from the consolidated company, you must prepare general ledger accounts for consolidation.</span></span> <span data-ttu-id="50b36-141">You can specify the accounts to post debits and credits to, and the method to use to translate currencies in the consolidated company.</span><span class="sxs-lookup"><span data-stu-id="50b36-141">You can specify the accounts to post debits and credits to, and the method to use to translate currencies in the consolidated company.</span></span> <span data-ttu-id="50b36-142">For example, this is useful if you frequently run the report.</span><span class="sxs-lookup"><span data-stu-id="50b36-142">For example, this is useful if you frequently run the report.</span></span>

1. <span data-ttu-id="50b36-143">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Chart of Accounts**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="50b36-143">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Chart of Accounts**, and then choose the related link.</span></span>  
2. <span data-ttu-id="50b36-144">Open the card for the account, and then fill in the fields on the **Consolidation** FastTab.</span><span class="sxs-lookup"><span data-stu-id="50b36-144">Open the card for the account, and then fill in the fields on the **Consolidation** FastTab.</span></span>

### <a name="to-specify-exchange-rates-for-consolidations"></a><span data-ttu-id="50b36-145">To specify exchange rates for consolidations</span><span class="sxs-lookup"><span data-stu-id="50b36-145">To specify exchange rates for consolidations</span></span>
<span data-ttu-id="50b36-146">If a business unit uses a different currency than the consolidated company, you must specify exchange rate methods for each account before you consolidate.</span><span class="sxs-lookup"><span data-stu-id="50b36-146">If a business unit uses a different currency than the consolidated company, you must specify exchange rate methods for each account before you consolidate.</span></span> <span data-ttu-id="50b36-147">For each account, the content of the **Consol. Translation Method** field determines the exchange rate.</span><span class="sxs-lookup"><span data-stu-id="50b36-147">For each account, the content of the **Consol. Translation Method** field determines the exchange rate.</span></span> <span data-ttu-id="50b36-148">On each business unit card, in the **Currency Exchange Rate Table** field, you specify whether consolidation will use exchange rates from the business unit or the consolidated company.</span><span class="sxs-lookup"><span data-stu-id="50b36-148">On each business unit card, in the **Currency Exchange Rate Table** field, you specify whether consolidation will use exchange rates from the business unit or the consolidated company.</span></span> <span data-ttu-id="50b36-149">If you use exchange rates from the consolidated company, you can change the exchange rates for a business unit.</span><span class="sxs-lookup"><span data-stu-id="50b36-149">If you use exchange rates from the consolidated company, you can change the exchange rates for a business unit.</span></span> <span data-ttu-id="50b36-150">For business units, if the **Currency Exchange Rate Table** field on the business unit card contains **Local**, you can change the exchange rate from the business unit card.</span><span class="sxs-lookup"><span data-stu-id="50b36-150">For business units, if the **Currency Exchange Rate Table** field on the business unit card contains **Local**, you can change the exchange rate from the business unit card.</span></span> <span data-ttu-id="50b36-151">The exchange rates are copied from the **Currency Exchange Rate** table, but you can change them before consolidating.</span><span class="sxs-lookup"><span data-stu-id="50b36-151">The exchange rates are copied from the **Currency Exchange Rate** table, but you can change them before consolidating.</span></span>

<span data-ttu-id="50b36-152">The following table describes the exchange rate methods you can use for accounts.</span><span class="sxs-lookup"><span data-stu-id="50b36-152">The following table describes the exchange rate methods you can use for accounts.</span></span>

|<span data-ttu-id="50b36-153">Exchange rate</span><span class="sxs-lookup"><span data-stu-id="50b36-153">Exchange rate</span></span> | <span data-ttu-id="50b36-154">Typical use</span><span class="sxs-lookup"><span data-stu-id="50b36-154">Typical use</span></span> |
|---|---|
|<span data-ttu-id="50b36-155">Average Rate (Manual)</span><span class="sxs-lookup"><span data-stu-id="50b36-155">Average Rate (Manual)</span></span> | <span data-ttu-id="50b36-156">You manually calculate the average rate for the period to consolidate.</span><span class="sxs-lookup"><span data-stu-id="50b36-156">You manually calculate the average rate for the period to consolidate.</span></span> <span data-ttu-id="50b36-157">Calculate the average either as an arithmetic average or as a best estimate, and specify the result for each business unit.</span><span class="sxs-lookup"><span data-stu-id="50b36-157">Calculate the average either as an arithmetic average or as a best estimate, and specify the result for each business unit.</span></span> <span data-ttu-id="50b36-158">Used for income statement accounts.</span><span class="sxs-lookup"><span data-stu-id="50b36-158">Used for income statement accounts.</span></span>|
|<span data-ttu-id="50b36-159">Closing Rate</span><span class="sxs-lookup"><span data-stu-id="50b36-159">Closing Rate</span></span> | <span data-ttu-id="50b36-160">Used for balance sheet accounts.</span><span class="sxs-lookup"><span data-stu-id="50b36-160">Used for balance sheet accounts.</span></span>|
|<span data-ttu-id="50b36-161">Last Closing Rate</span><span class="sxs-lookup"><span data-stu-id="50b36-161">Last Closing Rate</span></span> | <span data-ttu-id="50b36-162">The rate that was valid in the foreign exchange market on the date for which the balance sheet or income statement is being prepared.</span><span class="sxs-lookup"><span data-stu-id="50b36-162">The rate that was valid in the foreign exchange market on the date for which the balance sheet or income statement is being prepared.</span></span> <span data-ttu-id="50b36-163">You enter this rate for each business unit.</span><span class="sxs-lookup"><span data-stu-id="50b36-163">You enter this rate for each business unit.</span></span> <span data-ttu-id="50b36-164">Used for balance sheet accounts.</span><span class="sxs-lookup"><span data-stu-id="50b36-164">Used for balance sheet accounts.</span></span>|
|<span data-ttu-id="50b36-165">Historical Rate</span><span class="sxs-lookup"><span data-stu-id="50b36-165">Historical Rate</span></span> | <span data-ttu-id="50b36-166">The exchange rate that was valid when the transaction occurred.</span><span class="sxs-lookup"><span data-stu-id="50b36-166">The exchange rate that was valid when the transaction occurred.</span></span>|
|<span data-ttu-id="50b36-167">Composite Rate</span><span class="sxs-lookup"><span data-stu-id="50b36-167">Composite Rate</span></span> | <span data-ttu-id="50b36-168">The current period amounts are translated at the average rate and added to the previously recorded balance in the consolidated company.</span><span class="sxs-lookup"><span data-stu-id="50b36-168">The current period amounts are translated at the average rate and added to the previously recorded balance in the consolidated company.</span></span> <span data-ttu-id="50b36-169">This method is typically used for retained earnings accounts because they include amounts from different periods and are therefore a composite of amounts translated with different exchange rates.</span><span class="sxs-lookup"><span data-stu-id="50b36-169">This method is typically used for retained earnings accounts because they include amounts from different periods and are therefore a composite of amounts translated with different exchange rates.</span></span>|
|<span data-ttu-id="50b36-170">Equity Rate</span><span class="sxs-lookup"><span data-stu-id="50b36-170">Equity Rate</span></span> | <span data-ttu-id="50b36-171">This is similar to **Composite**.</span><span class="sxs-lookup"><span data-stu-id="50b36-171">This is similar to **Composite**.</span></span> <span data-ttu-id="50b36-172">Differences are posted to separate general ledger accounts.</span><span class="sxs-lookup"><span data-stu-id="50b36-172">Differences are posted to separate general ledger accounts.</span></span>|   

<span data-ttu-id="50b36-173">To specify exchange rates for business units, follow these steps:</span><span class="sxs-lookup"><span data-stu-id="50b36-173">To specify exchange rates for business units, follow these steps:</span></span>

1. <span data-ttu-id="50b36-174">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Business Units**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="50b36-174">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Business Units**, and then choose the related link.</span></span>  
2. <span data-ttu-id="50b36-175">On the **Business Unit List** page, choose the business unit, and then choose the **Average Rate (Manual)** action.</span><span class="sxs-lookup"><span data-stu-id="50b36-175">On the **Business Unit List** page, choose the business unit, and then choose the **Average Rate (Manual)** action.</span></span>   
3. <span data-ttu-id="50b36-176">On the **Change Exchange Rate** page, the contents of the **Relational Exch. Rate** field have been copied from the **Currency Exchange Rate** table, but you can modify them.</span><span class="sxs-lookup"><span data-stu-id="50b36-176">On the **Change Exchange Rate** page, the contents of the **Relational Exch. Rate** field have been copied from the **Currency Exchange Rate** table, but you can modify them.</span></span> <span data-ttu-id="50b36-177">Close the page.</span><span class="sxs-lookup"><span data-stu-id="50b36-177">Close the page.</span></span>  
4. <span data-ttu-id="50b36-178">Choose the **Closing Rate** action.</span><span class="sxs-lookup"><span data-stu-id="50b36-178">Choose the **Closing Rate** action.</span></span>  
5. <span data-ttu-id="50b36-179">In the **Relational Exch. Rate Amount** field, enter the exchange rate.</span><span class="sxs-lookup"><span data-stu-id="50b36-179">In the **Relational Exch. Rate Amount** field, enter the exchange rate.</span></span>

<!-- ### To include or exclude dimensions

COMMENTING THIS OUT BECAUSE i CANNOT REPRODUCE THE SETTINGS. tHERE IS NO CONSOLIDATION CODE FIELD ON DIMENSIONS OR DIMENSIOIN VALUES.

You can consolidate dimension information and general ledger accounts, as follows:

* To exclude dimension information in the consolidation, leave the **Consolidation Code** field blank, and do not choose dimensions in the **Copy Dimensions** fields in any consolidation functions or reports described later in this topic.
* To include dimension information in the consolidation, leave the **Consolidation Code** field blank. However, the consolidation will only work if the dimension values in the business unit are the same as the consolidated company.
* To consolidate the dimension value code in the business unit with a different dimension value code in the consolidated company, fill in the **Consolidation Code**. -->

### <a name="to-exclude-a-company-from-consolidation"></a><span data-ttu-id="50b36-180">To exclude a company from consolidation</span><span class="sxs-lookup"><span data-stu-id="50b36-180">To exclude a company from consolidation</span></span>
<span data-ttu-id="50b36-181">If you do not want to include a business unit in the consolidation, you can exclude it.</span><span class="sxs-lookup"><span data-stu-id="50b36-181">If you do not want to include a business unit in the consolidation, you can exclude it.</span></span> <span data-ttu-id="50b36-182">To do that, go to the business unit card, and clear the **Consolidate** check box.</span><span class="sxs-lookup"><span data-stu-id="50b36-182">To do that, go to the business unit card, and clear the **Consolidate** check box.</span></span>

### <a name="to-include-a-partially-owned-company-in-consolidation"></a><span data-ttu-id="50b36-183">To include a partially-owned company in consolidation</span><span class="sxs-lookup"><span data-stu-id="50b36-183">To include a partially-owned company in consolidation</span></span>
<span data-ttu-id="50b36-184">If you own only part of a company, you can include a percentage of each transaction that corresponds to the percentage of the company you own.</span><span class="sxs-lookup"><span data-stu-id="50b36-184">If you own only part of a company, you can include a percentage of each transaction that corresponds to the percentage of the company you own.</span></span> <span data-ttu-id="50b36-185">For example, if you own 70% of the company, consolidation will include $70 of an invoice for $100.</span><span class="sxs-lookup"><span data-stu-id="50b36-185">For example, if you own 70% of the company, consolidation will include $70 of an invoice for $100.</span></span> <span data-ttu-id="50b36-186">To specify the percentage of the company you own, go to the business unit card, and enter the percentage in the **Consolidation %** field.</span><span class="sxs-lookup"><span data-stu-id="50b36-186">To specify the percentage of the company you own, go to the business unit card, and enter the percentage in the **Consolidation %** field.</span></span>  

### <a name="to-test-the-data-before-you-consolidate"></a><span data-ttu-id="50b36-187">To test the data before you consolidate</span><span class="sxs-lookup"><span data-stu-id="50b36-187">To test the data before you consolidate</span></span>
<span data-ttu-id="50b36-188">You can test your data before you transfer it to the consolidated company.</span><span class="sxs-lookup"><span data-stu-id="50b36-188">You can test your data before you transfer it to the consolidated company.</span></span> [!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="50b36-189"> looks for differences in the information in the business units and the consolidated company.</span><span class="sxs-lookup"><span data-stu-id="50b36-189"> looks for differences in the information in the business units and the consolidated company.</span></span> <span data-ttu-id="50b36-190">For example, whether account numbers or dimension codes are different.</span><span class="sxs-lookup"><span data-stu-id="50b36-190">For example, whether account numbers or dimension codes are different.</span></span> <span data-ttu-id="50b36-191">You must correct errors before you can run the report.</span><span class="sxs-lookup"><span data-stu-id="50b36-191">You must correct errors before you can run the report.</span></span> <span data-ttu-id="50b36-192">You can test the database or, if you are importing data from an XML file, you can test the file.</span><span class="sxs-lookup"><span data-stu-id="50b36-192">You can test the database or, if you are importing data from an XML file, you can test the file.</span></span>   

1. <span data-ttu-id="50b36-193">Open the consolidated company.</span><span class="sxs-lookup"><span data-stu-id="50b36-193">Open the consolidated company.</span></span>  
2. <span data-ttu-id="50b36-194">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Business Units**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="50b36-194">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Business Units**, and then choose the related link.</span></span>  
3. <span data-ttu-id="50b36-195">Do one of the following:</span><span class="sxs-lookup"><span data-stu-id="50b36-195">Do one of the following:</span></span>  

    * <span data-ttu-id="50b36-196">To test a file, choose the **Test File** action, enter the name of the file to test, and then choose **Print**.</span><span class="sxs-lookup"><span data-stu-id="50b36-196">To test a file, choose the **Test File** action, enter the name of the file to test, and then choose **Print**.</span></span>  
    * <span data-ttu-id="50b36-197">To test the database, choose **Test Database**.</span><span class="sxs-lookup"><span data-stu-id="50b36-197">To test the database, choose **Test Database**.</span></span>  

## <a name="to-run-the-consolidation"></a><span data-ttu-id="50b36-198">To run the consolidation</span><span class="sxs-lookup"><span data-stu-id="50b36-198">To run the consolidation</span></span>
<span data-ttu-id="50b36-199">After you have tested the data, you can transfer it to the consolidated company.</span><span class="sxs-lookup"><span data-stu-id="50b36-199">After you have tested the data, you can transfer it to the consolidated company.</span></span>  

1. <span data-ttu-id="50b36-200">Sign in to the consolidated company.</span><span class="sxs-lookup"><span data-stu-id="50b36-200">Sign in to the consolidated company.</span></span>  
2. <span data-ttu-id="50b36-201">On the **Accountant Role Centre**, choose the **Run Consolidation** action.</span><span class="sxs-lookup"><span data-stu-id="50b36-201">On the **Accountant Role Center**, choose the **Run Consolidation** action.</span></span>  
3. <span data-ttu-id="50b36-202">Fill in the required fields.</span><span class="sxs-lookup"><span data-stu-id="50b36-202">Fill in the required fields.</span></span>  
4. <span data-ttu-id="50b36-203">In the **Where** field, choose **Company Name**, and then choose the consolidated company in the **is** field.</span><span class="sxs-lookup"><span data-stu-id="50b36-203">In the **Where** field, choose **Company Name**, and then choose the consolidated company in the **is** field.</span></span>  

## <a name="to-export-data-from-dynamics-nav-and-import-it-in-included365finincludesd365finmdmd"></a><span data-ttu-id="50b36-204">To export data from Dynamics NAV and import it in [!INCLUDE[d365fin](includes/d365fin_md.md)]</span><span class="sxs-lookup"><span data-stu-id="50b36-204">To export data from Dynamics NAV and import it in [!INCLUDE[d365fin](includes/d365fin_md.md)]</span></span>
<span data-ttu-id="50b36-205">If data for a business unit is in another database, you must export the data to a file before you can include it in the consolidation.</span><span class="sxs-lookup"><span data-stu-id="50b36-205">If data for a business unit is in another database, you must export the data to a file before you can include it in the consolidation.</span></span> <span data-ttu-id="50b36-206">Each company must be exported separately.</span><span class="sxs-lookup"><span data-stu-id="50b36-206">Each company must be exported separately.</span></span> <span data-ttu-id="50b36-207">For this purpose, use the **Export Consolidation** batch job.</span><span class="sxs-lookup"><span data-stu-id="50b36-207">For this purpose, use the **Export Consolidation** batch job.</span></span>  

<span data-ttu-id="50b36-208">After you run the batch job, all entries in general ledger accounts are processed.</span><span class="sxs-lookup"><span data-stu-id="50b36-208">After you run the batch job, all entries in general ledger accounts are processed.</span></span> <span data-ttu-id="50b36-209">For every combination of selected dimensions and date, the contents of the entries' **Amount** fields are totalled and exported.</span><span class="sxs-lookup"><span data-stu-id="50b36-209">For every combination of selected dimensions and date, the contents of the entries' **Amount** fields are totaled and exported.</span></span> <span data-ttu-id="50b36-210">The next combination of selected dimensions and date with the same account number is processed, then the combinations in the next account number are processed, and so on.</span><span class="sxs-lookup"><span data-stu-id="50b36-210">The next combination of selected dimensions and date with the same account number is processed, then the combinations in the next account number are processed, and so on.</span></span>  

<span data-ttu-id="50b36-211">The exported entries contain the following fields: **Account No.**, **Posting Date**, and **Amount**.</span><span class="sxs-lookup"><span data-stu-id="50b36-211">The exported entries contain the following fields: **Account No.**, **Posting Date**, and **Amount**.</span></span> <span data-ttu-id="50b36-212">If dimensions information was also exported, dimension codes and dimension values are also included.</span><span class="sxs-lookup"><span data-stu-id="50b36-212">If dimensions information was also exported, dimension codes and dimension values are also included.</span></span>  

1. <span data-ttu-id="50b36-213">For each exported line, if the total of the **Amount** fields is a debit, the account number that is set up in the business unit's **Consol. Debit Acc.** field is exported to the line.</span><span class="sxs-lookup"><span data-stu-id="50b36-213">For each exported line, if the total of the **Amount** fields is a debit, the account number that is set up in the business unit's **Consol. Debit Acc.** field is exported to the line.</span></span> <span data-ttu-id="50b36-214">If the total is a credit, the corresponding number in the **Consol. Credit Acc.** field is exported to the line.</span><span class="sxs-lookup"><span data-stu-id="50b36-214">If the total is a credit, the corresponding number in the **Consol. Credit Acc.** field is exported to the line.</span></span>  
2. <span data-ttu-id="50b36-215">The date used for each exported line is either the period's ending date or, if the transfer occurs each day, the exact date of the calculation.</span><span class="sxs-lookup"><span data-stu-id="50b36-215">The date used for each exported line is either the period's ending date or, if the transfer occurs each day, the exact date of the calculation.</span></span>  
3. <span data-ttu-id="50b36-216">The dimension value exported for the entry will be the consolidated company dimension value that is set up in the **Consolidation Code** field for that dimension value.</span><span class="sxs-lookup"><span data-stu-id="50b36-216">The dimension value exported for the entry will be the consolidated company dimension value that is set up in the **Consolidation Code** field for that dimension value.</span></span> <span data-ttu-id="50b36-217">If no consolidated company dimension value has been entered in the **Consolidated Code** field for that dimension value, the dimension value itself will be exported to the line.</span><span class="sxs-lookup"><span data-stu-id="50b36-217">If no consolidated company dimension value has been entered in the **Consolidated Code** field for that dimension value, the dimension value itself will be exported to the line.</span></span>   
4. <span data-ttu-id="50b36-218">The XML files also contain the currency exchange rates in the consolidation period.</span><span class="sxs-lookup"><span data-stu-id="50b36-218">The XML files also contain the currency exchange rates in the consolidation period.</span></span> <span data-ttu-id="50b36-219">These rates are included in a separate section at the beginning of the file.</span><span class="sxs-lookup"><span data-stu-id="50b36-219">These rates are included in a separate section at the beginning of the file.</span></span>

## <a name="see-also"></a><span data-ttu-id="50b36-220">See Also</span><span class="sxs-lookup"><span data-stu-id="50b36-220">See Also</span></span>
<span data-ttu-id="50b36-221">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="50b36-221">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  
[<span data-ttu-id="50b36-222">Exporting Your Business Data to Excel</span><span class="sxs-lookup"><span data-stu-id="50b36-222">Exporting Your Business Data to Excel</span></span>](about-export-data.md)
