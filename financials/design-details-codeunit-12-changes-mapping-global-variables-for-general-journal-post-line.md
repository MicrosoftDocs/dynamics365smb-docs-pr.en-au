---
title: Design Details - Codeunit 12 Changes in Mapping Global Variables for General Journal Post Line | Microsoft Docs
description: The following changes have been implemented in this release of Dynamics 365.
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
ms.sourcegitcommit: aa56764b5f3210229ad21eae6891fb201462209c
ms.openlocfilehash: 253043c8f3b2a15f2ed6d0990192977772e98b87
ms.contentlocale: en-au
ms.lasthandoff: 12/14/2017

---
# <a name="codeunit-12-changes-mapping-global-variables-for-general-journal-post-line"></a><span data-ttu-id="12c1b-103">Codeunit 12 Changes: Mapping Global Variables for General Journal Post Line</span><span class="sxs-lookup"><span data-stu-id="12c1b-103">Codeunit 12 Changes: Mapping Global Variables for General Journal Post Line</span></span>
<span data-ttu-id="12c1b-104">The following changes have been implemented in this release of [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="12c1b-104">The following changes have been implemented in this release of [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>  

|<span data-ttu-id="12c1b-105">**Microsoft Dynamics NAV 2009 R2**</span><span class="sxs-lookup"><span data-stu-id="12c1b-105">**Microsoft Dynamics NAV 2009 R2**</span></span>|<span data-ttu-id="12c1b-106">**Microsoft Dynamics NAV 2013 R2**</span><span class="sxs-lookup"><span data-stu-id="12c1b-106">**Microsoft Dynamics NAV 2013 R2**</span></span>|<span data-ttu-id="12c1b-107">**Comment**</span><span class="sxs-lookup"><span data-stu-id="12c1b-107">**Comment**</span></span>|  
|----------------------------------------|----------------------------------------|-----------------|  
|<span data-ttu-id="12c1b-108">GLSetup@1009 : Record 98;</span><span class="sxs-lookup"><span data-stu-id="12c1b-108">GLSetup@1009 : Record 98;</span></span>|<span data-ttu-id="12c1b-109">GLSetup@1009 : Record 98;</span><span class="sxs-lookup"><span data-stu-id="12c1b-109">GLSetup@1009 : Record 98;</span></span>|<span data-ttu-id="12c1b-110">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-110">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-111">SalesSetup@1010 : Record 311;</span><span class="sxs-lookup"><span data-stu-id="12c1b-111">SalesSetup@1010 : Record 311;</span></span>||<span data-ttu-id="12c1b-112">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-112">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-113">PurchSetup@1011 : Record 312;</span><span class="sxs-lookup"><span data-stu-id="12c1b-113">PurchSetup@1011 : Record 312;</span></span>||<span data-ttu-id="12c1b-114">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-114">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-115">AccountingPeriod@1012 : Record 50;</span><span class="sxs-lookup"><span data-stu-id="12c1b-115">AccountingPeriod@1012 : Record 50;</span></span>||<span data-ttu-id="12c1b-116">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-116">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-117">GLAcc@1013 : Record 15;</span><span class="sxs-lookup"><span data-stu-id="12c1b-117">GLAcc@1013 : Record 15;</span></span>||<span data-ttu-id="12c1b-118">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-118">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-119">GLEntry@1014 : Record 17;</span><span class="sxs-lookup"><span data-stu-id="12c1b-119">GLEntry@1014 : Record 17;</span></span>|<span data-ttu-id="12c1b-120">GlobalGLEntry@1014 : Record 17;</span><span class="sxs-lookup"><span data-stu-id="12c1b-120">GlobalGLEntry@1014 : Record 17;</span></span>|<span data-ttu-id="12c1b-121">Renamed</span><span class="sxs-lookup"><span data-stu-id="12c1b-121">Renamed</span></span>|  
|<span data-ttu-id="12c1b-122">GLEntryTmp@1015 : TEMPORARY Record 17;</span><span class="sxs-lookup"><span data-stu-id="12c1b-122">GLEntryTmp@1015 : TEMPORARY Record 17;</span></span>|<span data-ttu-id="12c1b-123">TempGLEntryBuf@1010 : TEMPORARY Record 17;</span><span class="sxs-lookup"><span data-stu-id="12c1b-123">TempGLEntryBuf@1010 : TEMPORARY Record 17;</span></span>|<span data-ttu-id="12c1b-124">Renamed</span><span class="sxs-lookup"><span data-stu-id="12c1b-124">Renamed</span></span>|  
|<span data-ttu-id="12c1b-125">TempGLEntryVAT@1016 : TEMPORARY Record 17;</span><span class="sxs-lookup"><span data-stu-id="12c1b-125">TempGLEntryVAT@1016 : TEMPORARY Record 17;</span></span>|<span data-ttu-id="12c1b-126">TempGLEntryVAT@1016 : TEMPORARY Record 17;</span><span class="sxs-lookup"><span data-stu-id="12c1b-126">TempGLEntryVAT@1016 : TEMPORARY Record 17;</span></span>|<span data-ttu-id="12c1b-127">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-127">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-128">OrigGLEntry@1017 : Record 17;</span><span class="sxs-lookup"><span data-stu-id="12c1b-128">OrigGLEntry@1017 : Record 17;</span></span>||<span data-ttu-id="12c1b-129">Deleted</span><span class="sxs-lookup"><span data-stu-id="12c1b-129">Deleted</span></span>|  
|<span data-ttu-id="12c1b-130">VATPostingSetup@1019 : Record 325;</span><span class="sxs-lookup"><span data-stu-id="12c1b-130">VATPostingSetup@1019 : Record 325;</span></span>||<span data-ttu-id="12c1b-131">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-131">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-132">Cust@1020 : Record 18;</span><span class="sxs-lookup"><span data-stu-id="12c1b-132">Cust@1020 : Record 18;</span></span>||<span data-ttu-id="12c1b-133">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-133">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-134">Vend@1021 : Record 23;</span><span class="sxs-lookup"><span data-stu-id="12c1b-134">Vend@1021 : Record 23;</span></span>||<span data-ttu-id="12c1b-135">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-135">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-136">GenJnlLine@1022 : Record 81;</span><span class="sxs-lookup"><span data-stu-id="12c1b-136">GenJnlLine@1022 : Record 81;</span></span>||<span data-ttu-id="12c1b-137">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-137">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-138">GLReg@1029 : Record 45;</span><span class="sxs-lookup"><span data-stu-id="12c1b-138">GLReg@1029 : Record 45;</span></span>|<span data-ttu-id="12c1b-139">GLReg@1029 : Record 45;</span><span class="sxs-lookup"><span data-stu-id="12c1b-139">GLReg@1029 : Record 45;</span></span>|<span data-ttu-id="12c1b-140">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-140">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-141">CustPostingGr@1030 : Record 92;</span><span class="sxs-lookup"><span data-stu-id="12c1b-141">CustPostingGr@1030 : Record 92;</span></span>||<span data-ttu-id="12c1b-142">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-142">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-143">VendPostingGr@1031 : Record 93;</span><span class="sxs-lookup"><span data-stu-id="12c1b-143">VendPostingGr@1031 : Record 93;</span></span>||<span data-ttu-id="12c1b-144">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-144">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-145">Currency@1032 : Record 4;</span><span class="sxs-lookup"><span data-stu-id="12c1b-145">Currency@1032 : Record 4;</span></span>||<span data-ttu-id="12c1b-146">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-146">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-147">AddCurrency@1033 : Record 4;</span><span class="sxs-lookup"><span data-stu-id="12c1b-147">AddCurrency@1033 : Record 4;</span></span>|<span data-ttu-id="12c1b-148">AddCurrency@1033 : Record 4;</span><span class="sxs-lookup"><span data-stu-id="12c1b-148">AddCurrency@1033 : Record 4;</span></span>|<span data-ttu-id="12c1b-149">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-149">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-150">ApplnCurrency@1034 : Record 4;</span><span class="sxs-lookup"><span data-stu-id="12c1b-150">ApplnCurrency@1034 : Record 4;</span></span>||<span data-ttu-id="12c1b-151">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-151">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-152">CurrExchRate@1035 : Record 330;</span><span class="sxs-lookup"><span data-stu-id="12c1b-152">CurrExchRate@1035 : Record 330;</span></span>|<span data-ttu-id="12c1b-153">CurrExchRate@1035 : Record 330;</span><span class="sxs-lookup"><span data-stu-id="12c1b-153">CurrExchRate@1035 : Record 330;</span></span>|<span data-ttu-id="12c1b-154">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-154">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-155">VATEntry@1038 : Record 254;</span><span class="sxs-lookup"><span data-stu-id="12c1b-155">VATEntry@1038 : Record 254;</span></span>|<span data-ttu-id="12c1b-156">VATEntry@1038 : Record 254;</span><span class="sxs-lookup"><span data-stu-id="12c1b-156">VATEntry@1038 : Record 254;</span></span>|<span data-ttu-id="12c1b-157">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-157">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-158">BankAcc@1039 : Record 270;</span><span class="sxs-lookup"><span data-stu-id="12c1b-158">BankAcc@1039 : Record 270;</span></span>||<span data-ttu-id="12c1b-159">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-159">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-160">BankAccLedgEntry@1040 : Record 271;</span><span class="sxs-lookup"><span data-stu-id="12c1b-160">BankAccLedgEntry@1040 : Record 271;</span></span>||<span data-ttu-id="12c1b-161">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-161">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-162">CheckLedgEntry@1041 : Record 272;</span><span class="sxs-lookup"><span data-stu-id="12c1b-162">CheckLedgEntry@1041 : Record 272;</span></span>||<span data-ttu-id="12c1b-163">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-163">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-164">CheckLedgEntry2@1042 : Record 272;</span><span class="sxs-lookup"><span data-stu-id="12c1b-164">CheckLedgEntry2@1042 : Record 272;</span></span>||<span data-ttu-id="12c1b-165">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-165">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-166">BankAccPostingGr@1043 : Record 277;</span><span class="sxs-lookup"><span data-stu-id="12c1b-166">BankAccPostingGr@1043 : Record 277;</span></span>||<span data-ttu-id="12c1b-167">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-167">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-168">GenJnlTemplate@1044 : Record 80;</span><span class="sxs-lookup"><span data-stu-id="12c1b-168">GenJnlTemplate@1044 : Record 80;</span></span>||<span data-ttu-id="12c1b-169">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-169">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-170">TaxJurisdiction@1045 : Record 320;</span><span class="sxs-lookup"><span data-stu-id="12c1b-170">TaxJurisdiction@1045 : Record 320;</span></span>||<span data-ttu-id="12c1b-171">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-171">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-172">TaxDetail@1046 : Record 322;</span><span class="sxs-lookup"><span data-stu-id="12c1b-172">TaxDetail@1046 : Record 322;</span></span>|<span data-ttu-id="12c1b-173">TaxDetail@1046 : Record 322;</span><span class="sxs-lookup"><span data-stu-id="12c1b-173">TaxDetail@1046 : Record 322;</span></span>|<span data-ttu-id="12c1b-174">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-174">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-175">FAGLPostBuf@1047 : TEMPORARY Record 5637;</span><span class="sxs-lookup"><span data-stu-id="12c1b-175">FAGLPostBuf@1047 : TEMPORARY Record 5637;</span></span>||<span data-ttu-id="12c1b-176">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-176">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-177">UnrealizedCustLedgEntry@1084 : Record 21;</span><span class="sxs-lookup"><span data-stu-id="12c1b-177">UnrealizedCustLedgEntry@1084 : Record 21;</span></span>|<span data-ttu-id="12c1b-178">UnrealizedCustLedgEntry@1084 : Record 21;</span><span class="sxs-lookup"><span data-stu-id="12c1b-178">UnrealizedCustLedgEntry@1084 : Record 21;</span></span>|<span data-ttu-id="12c1b-179">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-179">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-180">UnrealizedVendLedgEntry@1085 : Record 25;</span><span class="sxs-lookup"><span data-stu-id="12c1b-180">UnrealizedVendLedgEntry@1085 : Record 25;</span></span>|<span data-ttu-id="12c1b-181">UnrealizedVendLedgEntry@1085 : Record 25;</span><span class="sxs-lookup"><span data-stu-id="12c1b-181">UnrealizedVendLedgEntry@1085 : Record 25;</span></span>|<span data-ttu-id="12c1b-182">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-182">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-183">GLEntryVATEntryLink@1087 : Record 253;</span><span class="sxs-lookup"><span data-stu-id="12c1b-183">GLEntryVATEntryLink@1087 : Record 253;</span></span>|<span data-ttu-id="12c1b-184">GLEntryVATEntryLink@1087 : Record 253;</span><span class="sxs-lookup"><span data-stu-id="12c1b-184">GLEntryVATEntryLink@1087 : Record 253;</span></span>|<span data-ttu-id="12c1b-185">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-185">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-186">TempVATEntry@1088 : TEMPORARY Record 254;</span><span class="sxs-lookup"><span data-stu-id="12c1b-186">TempVATEntry@1088 : TEMPORARY Record 254;</span></span>|<span data-ttu-id="12c1b-187">TempVATEntry@1088 : TEMPORARY Record 254;</span><span class="sxs-lookup"><span data-stu-id="12c1b-187">TempVATEntry@1088 : TEMPORARY Record 254;</span></span>|<span data-ttu-id="12c1b-188">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-188">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-189">ReversedGLEntryTemp@1089 : TEMPORARY Record 17;</span><span class="sxs-lookup"><span data-stu-id="12c1b-189">ReversedGLEntryTemp@1089 : TEMPORARY Record 17;</span></span>||<span data-ttu-id="12c1b-190">Moved to Codeunit17</span><span class="sxs-lookup"><span data-stu-id="12c1b-190">Moved to Codeunit17</span></span>|  
|<span data-ttu-id="12c1b-191">CostAccSetup@1092 : Record 1108;</span><span class="sxs-lookup"><span data-stu-id="12c1b-191">CostAccSetup@1092 : Record 1108;</span></span>||<span data-ttu-id="12c1b-192">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-192">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-193">GenJnlCheckLine@1048 : Codeunit 11;</span><span class="sxs-lookup"><span data-stu-id="12c1b-193">GenJnlCheckLine@1048 : Codeunit 11;</span></span>|<span data-ttu-id="12c1b-194">GenJnlCheckLine@1001 : Codeunit 11;</span><span class="sxs-lookup"><span data-stu-id="12c1b-194">GenJnlCheckLine@1001 : Codeunit 11;</span></span>|<span data-ttu-id="12c1b-195">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-195">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-196">ExchAccGLJnlLine@1049 : Codeunit 366;</span><span class="sxs-lookup"><span data-stu-id="12c1b-196">ExchAccGLJnlLine@1049 : Codeunit 366;</span></span>||<span data-ttu-id="12c1b-197">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-197">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-198">FAJnlPostLine@1050 : Codeunit 5632;</span><span class="sxs-lookup"><span data-stu-id="12c1b-198">FAJnlPostLine@1050 : Codeunit 5632;</span></span>||<span data-ttu-id="12c1b-199">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-199">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-200">SalesTaxCalculate@1051 : Codeunit 398;</span><span class="sxs-lookup"><span data-stu-id="12c1b-200">SalesTaxCalculate@1051 : Codeunit 398;</span></span>||<span data-ttu-id="12c1b-201">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-201">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-202">GenJnlApply@1052 : Codeunit 225;</span><span class="sxs-lookup"><span data-stu-id="12c1b-202">GenJnlApply@1052 : Codeunit 225;</span></span>||<span data-ttu-id="12c1b-203">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-203">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-204">DimMgt@1053 : Codeunit 408;</span><span class="sxs-lookup"><span data-stu-id="12c1b-204">DimMgt@1053 : Codeunit 408;</span></span>||<span data-ttu-id="12c1b-205">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-205">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-206">JobPostLine@1028 : Codeunit 1001;</span><span class="sxs-lookup"><span data-stu-id="12c1b-206">JobPostLine@1028 : Codeunit 1001;</span></span>||<span data-ttu-id="12c1b-207">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-207">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-208">TransferGlEntriesToCA@1091 : Codeunit 1105;</span><span class="sxs-lookup"><span data-stu-id="12c1b-208">TransferGlEntriesToCA@1091 : Codeunit 1105;</span></span>||<span data-ttu-id="12c1b-209">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-209">Changed to Local</span></span>|  
||<span data-ttu-id="12c1b-210">PaymentToleranceMgt@1002 : Codeunit 426;</span><span class="sxs-lookup"><span data-stu-id="12c1b-210">PaymentToleranceMgt@1002 : Codeunit 426;</span></span>|<span data-ttu-id="12c1b-211">Added</span><span class="sxs-lookup"><span data-stu-id="12c1b-211">Added</span></span>|  
||<span data-ttu-id="12c1b-212">AddCurrencyCode@1117 : Code[10];</span><span class="sxs-lookup"><span data-stu-id="12c1b-212">AddCurrencyCode@1117 : Code[10];</span></span>|<span data-ttu-id="12c1b-213">Added</span><span class="sxs-lookup"><span data-stu-id="12c1b-213">Added</span></span>|  
|<span data-ttu-id="12c1b-214">FiscalYearStartDate@1054 : Date;</span><span class="sxs-lookup"><span data-stu-id="12c1b-214">FiscalYearStartDate@1054 : Date;</span></span>|<span data-ttu-id="12c1b-215">FiscalYearStartDate@1011 : Date;</span><span class="sxs-lookup"><span data-stu-id="12c1b-215">FiscalYearStartDate@1011 : Date;</span></span>|<span data-ttu-id="12c1b-216">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-216">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-217">NextEntryNo@1055 : Integer;</span><span class="sxs-lookup"><span data-stu-id="12c1b-217">NextEntryNo@1055 : Integer;</span></span>|<span data-ttu-id="12c1b-218">NextEntryNo@1022 : Integer;</span><span class="sxs-lookup"><span data-stu-id="12c1b-218">NextEntryNo@1022 : Integer;</span></span>|<span data-ttu-id="12c1b-219">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-219">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-220">BalanceCheckAmount@1056 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-220">BalanceCheckAmount@1056 : Decimal;</span></span>|<span data-ttu-id="12c1b-221">BalanceCheckAmount@1056 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-221">BalanceCheckAmount@1056 : Decimal;</span></span>|<span data-ttu-id="12c1b-222">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-222">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-223">BalanceCheckAmount2@1057 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-223">BalanceCheckAmount2@1057 : Decimal;</span></span>|<span data-ttu-id="12c1b-224">BalanceCheckAmount2@1057 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-224">BalanceCheckAmount2@1057 : Decimal;</span></span>|<span data-ttu-id="12c1b-225">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-225">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-226">BalanceCheckAddCurrAmount@1058 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-226">BalanceCheckAddCurrAmount@1058 : Decimal;</span></span>|<span data-ttu-id="12c1b-227">BalanceCheckAddCurrAmount@1058 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-227">BalanceCheckAddCurrAmount@1058 : Decimal;</span></span>|<span data-ttu-id="12c1b-228">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-228">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-229">BalanceCheckAddCurrAmount2@1059 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-229">BalanceCheckAddCurrAmount2@1059 : Decimal;</span></span>|<span data-ttu-id="12c1b-230">BalanceCheckAddCurrAmount2@1059 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-230">BalanceCheckAddCurrAmount2@1059 : Decimal;</span></span>|<span data-ttu-id="12c1b-231">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-231">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-232">CurrentBalance@1060 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-232">CurrentBalance@1060 : Decimal;</span></span>|<span data-ttu-id="12c1b-233">CurrentBalance@1060 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-233">CurrentBalance@1060 : Decimal;</span></span>|<span data-ttu-id="12c1b-234">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-234">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-235">SalesTaxBaseAmount@1061 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-235">SalesTaxBaseAmount@1061 : Decimal;</span></span>||<span data-ttu-id="12c1b-236">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-236">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-237">TotalAddCurrAmount@1062 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-237">TotalAddCurrAmount@1062 : Decimal;</span></span>|<span data-ttu-id="12c1b-238">TotalAddCurrAmount@1062 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-238">TotalAddCurrAmount@1062 : Decimal;</span></span>|<span data-ttu-id="12c1b-239">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-239">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-240">TotalAmount@1063 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-240">TotalAmount@1063 : Decimal;</span></span>|<span data-ttu-id="12c1b-241">TotalAmount@1063 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-241">TotalAmount@1063 : Decimal;</span></span>|<span data-ttu-id="12c1b-242">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-242">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-243">UnrealizedRemainingAmountCust@1086 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-243">UnrealizedRemainingAmountCust@1086 : Decimal;</span></span>|<span data-ttu-id="12c1b-244">UnrealizedRemainingAmountCust@1086 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-244">UnrealizedRemainingAmountCust@1086 : Decimal;</span></span>|<span data-ttu-id="12c1b-245">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-245">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-246">UnrealizedRemainingAmountVend@1074 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-246">UnrealizedRemainingAmountVend@1074 : Decimal;</span></span>|<span data-ttu-id="12c1b-247">UnrealizedRemainingAmountVend@1074 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-247">UnrealizedRemainingAmountVend@1074 : Decimal;</span></span>|<span data-ttu-id="12c1b-248">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-248">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-249">NextVATEntryNo@1064 : Integer;</span><span class="sxs-lookup"><span data-stu-id="12c1b-249">NextVATEntryNo@1064 : Integer;</span></span>|<span data-ttu-id="12c1b-250">NextVATEntryNo@1064 : Integer;</span><span class="sxs-lookup"><span data-stu-id="12c1b-250">NextVATEntryNo@1064 : Integer;</span></span>|<span data-ttu-id="12c1b-251">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-251">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-252">FirstNewVATEntryNo@1065 : Integer;</span><span class="sxs-lookup"><span data-stu-id="12c1b-252">FirstNewVATEntryNo@1065 : Integer;</span></span>|<span data-ttu-id="12c1b-253">FirstNewVATEntryNo@1065 : Integer;</span><span class="sxs-lookup"><span data-stu-id="12c1b-253">FirstNewVATEntryNo@1065 : Integer;</span></span>|<span data-ttu-id="12c1b-254">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-254">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-255">NextTransactionNo@1066 : Integer;</span><span class="sxs-lookup"><span data-stu-id="12c1b-255">NextTransactionNo@1066 : Integer;</span></span>|<span data-ttu-id="12c1b-256">NextTransactionNo@1066 : Integer;</span><span class="sxs-lookup"><span data-stu-id="12c1b-256">NextTransactionNo@1066 : Integer;</span></span>|<span data-ttu-id="12c1b-257">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-257">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-258">NextConnectionNo@1067 : Integer;</span><span class="sxs-lookup"><span data-stu-id="12c1b-258">NextConnectionNo@1067 : Integer;</span></span>|<span data-ttu-id="12c1b-259">NextConnectionNo@1067 : Integer;</span><span class="sxs-lookup"><span data-stu-id="12c1b-259">NextConnectionNo@1067 : Integer;</span></span>|<span data-ttu-id="12c1b-260">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-260">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-261">InsertedTempGLEntryVAT@1068 : Integer;</span><span class="sxs-lookup"><span data-stu-id="12c1b-261">InsertedTempGLEntryVAT@1068 : Integer;</span></span>|<span data-ttu-id="12c1b-262">InsertedTempGLEntryVAT@1027 : Integer;</span><span class="sxs-lookup"><span data-stu-id="12c1b-262">InsertedTempGLEntryVAT@1027 : Integer;</span></span>|<span data-ttu-id="12c1b-263">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-263">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-264">LastDocNo@1069 : Code[20];</span><span class="sxs-lookup"><span data-stu-id="12c1b-264">LastDocNo@1069 : Code[20];</span></span>|<span data-ttu-id="12c1b-265">LastDocNo@1023 : Code[20];</span><span class="sxs-lookup"><span data-stu-id="12c1b-265">LastDocNo@1023 : Code[20];</span></span>|<span data-ttu-id="12c1b-266">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-266">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-267">LastLineNo@1070 : Integer;</span><span class="sxs-lookup"><span data-stu-id="12c1b-267">LastLineNo@1070 : Integer;</span></span>||<span data-ttu-id="12c1b-268">Deleted</span><span class="sxs-lookup"><span data-stu-id="12c1b-268">Deleted</span></span>|  
|<span data-ttu-id="12c1b-269">LastDate@1071 : Date;</span><span class="sxs-lookup"><span data-stu-id="12c1b-269">LastDate@1071 : Date;</span></span>|<span data-ttu-id="12c1b-270">LastDate@1021 : Date;</span><span class="sxs-lookup"><span data-stu-id="12c1b-270">LastDate@1021 : Date;</span></span>|<span data-ttu-id="12c1b-271">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-271">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-272">LastDocType@1072 : ' ,Payment,Invoice,CR/Adj Note,Finance Charge Memo,Reminder';</span><span class="sxs-lookup"><span data-stu-id="12c1b-272">LastDocType@1072 : ' ,Payment,Invoice,Credit Memo,Finance Charge Memo,Reminder';</span></span>|<span data-ttu-id="12c1b-273">LastDocType@1025 : ' ,Payment,Invoice,CR/Adj Note,Finance Charge Memo,Reminder';</span><span class="sxs-lookup"><span data-stu-id="12c1b-273">LastDocType@1025 : ' ,Payment,Invoice,Credit Memo,Finance Charge Memo,Reminder';</span></span>|<span data-ttu-id="12c1b-274">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-274">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-275">NextCheckEntryNo@1073 : Integer;</span><span class="sxs-lookup"><span data-stu-id="12c1b-275">NextCheckEntryNo@1073 : Integer;</span></span>|<span data-ttu-id="12c1b-276">NextCheckEntryNo@1028 : Integer;</span><span class="sxs-lookup"><span data-stu-id="12c1b-276">NextCheckEntryNo@1028 : Integer;</span></span>|<span data-ttu-id="12c1b-277">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-277">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-278">AddCurrGLEntryVATAmt@1075 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-278">AddCurrGLEntryVATAmt@1075 : Decimal;</span></span>|<span data-ttu-id="12c1b-279">AddCurrGLEntryVATAmt@1017 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-279">AddCurrGLEntryVATAmt@1017 : Decimal;</span></span>|<span data-ttu-id="12c1b-280">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-280">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-281">CurrencyDate@1076 : Date;</span><span class="sxs-lookup"><span data-stu-id="12c1b-281">CurrencyDate@1076 : Date;</span></span>|<span data-ttu-id="12c1b-282">CurrencyDate@1020 : Date;</span><span class="sxs-lookup"><span data-stu-id="12c1b-282">CurrencyDate@1020 : Date;</span></span>|<span data-ttu-id="12c1b-283">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-283">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-284">CurrencyFactor@1077 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-284">CurrencyFactor@1077 : Decimal;</span></span>|<span data-ttu-id="12c1b-285">CurrencyFactor@1019 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-285">CurrencyFactor@1019 : Decimal;</span></span>|<span data-ttu-id="12c1b-286">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-286">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-287">UseCurrFactorOnly@1078 : Boolean;</span><span class="sxs-lookup"><span data-stu-id="12c1b-287">UseCurrFactorOnly@1078 : Boolean;</span></span>|<span data-ttu-id="12c1b-288">UseCurrFactorOnly@1078 : Boolean;</span><span class="sxs-lookup"><span data-stu-id="12c1b-288">UseCurrFactorOnly@1078 : Boolean;</span></span>|<span data-ttu-id="12c1b-289">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-289">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-290">NonAddCurrCodeOccured@1079 : Boolean;</span><span class="sxs-lookup"><span data-stu-id="12c1b-290">NonAddCurrCodeOccured@1079 : Boolean;</span></span>|<span data-ttu-id="12c1b-291">NonAddCurrCodeOccured@1079 : Boolean;</span><span class="sxs-lookup"><span data-stu-id="12c1b-291">NonAddCurrCodeOccured@1079 : Boolean;</span></span>|<span data-ttu-id="12c1b-292">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-292">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-293">FADimAlreadyChecked@1080 : Boolean;</span><span class="sxs-lookup"><span data-stu-id="12c1b-293">FADimAlreadyChecked@1080 : Boolean;</span></span>|<span data-ttu-id="12c1b-294">FADimAlreadyChecked@1080 : Boolean;</span><span class="sxs-lookup"><span data-stu-id="12c1b-294">FADimAlreadyChecked@1080 : Boolean;</span></span>|<span data-ttu-id="12c1b-295">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-295">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-296">AllApplied@1081 : Boolean;</span><span class="sxs-lookup"><span data-stu-id="12c1b-296">AllApplied@1081 : Boolean;</span></span>||<span data-ttu-id="12c1b-297">Changed to Local</span><span class="sxs-lookup"><span data-stu-id="12c1b-297">Changed to Local</span></span>|  
|<span data-ttu-id="12c1b-298">OverrideDimErr@1018 : Boolean;</span><span class="sxs-lookup"><span data-stu-id="12c1b-298">OverrideDimErr@1018 : Boolean;</span></span>|<span data-ttu-id="12c1b-299">OverrideDimErr@1018 : Boolean;</span><span class="sxs-lookup"><span data-stu-id="12c1b-299">OverrideDimErr@1018 : Boolean;</span></span>|<span data-ttu-id="12c1b-300">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-300">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-301">JobLine@1036 : Boolean;</span><span class="sxs-lookup"><span data-stu-id="12c1b-301">JobLine@1036 : Boolean;</span></span>|<span data-ttu-id="12c1b-302">JobLine@1036 : Boolean;</span><span class="sxs-lookup"><span data-stu-id="12c1b-302">JobLine@1036 : Boolean;</span></span>|<span data-ttu-id="12c1b-303">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-303">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-304">Prepayment@1037 : Boolean;</span><span class="sxs-lookup"><span data-stu-id="12c1b-304">Prepayment@1037 : Boolean;</span></span>||<span data-ttu-id="12c1b-305">Deleted</span><span class="sxs-lookup"><span data-stu-id="12c1b-305">Deleted</span></span>|  
|<span data-ttu-id="12c1b-306">CheckUnrealizedCust@1082 : Boolean;</span><span class="sxs-lookup"><span data-stu-id="12c1b-306">CheckUnrealizedCust@1082 : Boolean;</span></span>|<span data-ttu-id="12c1b-307">CheckUnrealizedCust@1082 : Boolean;</span><span class="sxs-lookup"><span data-stu-id="12c1b-307">CheckUnrealizedCust@1082 : Boolean;</span></span>|<span data-ttu-id="12c1b-308">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-308">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-309">CheckUnrealizedVend@1083 : Boolean;</span><span class="sxs-lookup"><span data-stu-id="12c1b-309">CheckUnrealizedVend@1083 : Boolean;</span></span>|<span data-ttu-id="12c1b-310">CheckUnrealizedVend@1083 : Boolean;</span><span class="sxs-lookup"><span data-stu-id="12c1b-310">CheckUnrealizedVend@1083 : Boolean;</span></span>|<span data-ttu-id="12c1b-311">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-311">Unchanged</span></span>|  
|<span data-ttu-id="12c1b-312">GLEntryNo@1090 : Integer;</span><span class="sxs-lookup"><span data-stu-id="12c1b-312">GLEntryNo@1090 : Integer;</span></span>|<span data-ttu-id="12c1b-313">GLEntryNo@1026 : Integer;</span><span class="sxs-lookup"><span data-stu-id="12c1b-313">GLEntryNo@1026 : Integer;</span></span>|<span data-ttu-id="12c1b-314">Unchanged</span><span class="sxs-lookup"><span data-stu-id="12c1b-314">Unchanged</span></span>|  
||<span data-ttu-id="12c1b-315">GLSetupRead@1015 : Boolean;</span><span class="sxs-lookup"><span data-stu-id="12c1b-315">GLSetupRead@1015 : Boolean;</span></span>|<span data-ttu-id="12c1b-316">Added</span><span class="sxs-lookup"><span data-stu-id="12c1b-316">Added</span></span>|  
||<span data-ttu-id="12c1b-317">AmountRoundingPrecision@1012 : Decimal;</span><span class="sxs-lookup"><span data-stu-id="12c1b-317">AmountRoundingPrecision@1012 : Decimal;</span></span>|<span data-ttu-id="12c1b-318">Added</span><span class="sxs-lookup"><span data-stu-id="12c1b-318">Added</span></span>|  
||<span data-ttu-id="12c1b-319">CrCardTransactionEntryNo@1013 : Integer;</span><span class="sxs-lookup"><span data-stu-id="12c1b-319">CrCardTransactionEntryNo@1013 : Integer;</span></span>|<span data-ttu-id="12c1b-320">Added</span><span class="sxs-lookup"><span data-stu-id="12c1b-320">Added</span></span>|  

## <a name="see-also"></a><span data-ttu-id="12c1b-321">See Also</span><span class="sxs-lookup"><span data-stu-id="12c1b-321">See Also</span></span>  
 [<span data-ttu-id="12c1b-322">Design Details: Codeunit 12 Changes: Changes in General Journal Post Procedures</span><span class="sxs-lookup"><span data-stu-id="12c1b-322">Design Details: Codeunit 12 Changes: Changes in General Journal Post Procedures</span></span>](design-details-codeunit-12-changes-changes-in-general-journal-post-procedures.md)
