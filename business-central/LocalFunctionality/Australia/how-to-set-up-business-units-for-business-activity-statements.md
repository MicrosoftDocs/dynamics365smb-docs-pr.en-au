---
title: Set Up Business Units for Business Activity Statements (AU)
description: Describes how to consolidate the financial statements of various companies into one financial statement.
author: bholtorf
ms.service: dynamics365-business-central
ms.topic: conceptual
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: ''
ms.date: 04/01/2021
ms.author: bholtorf
ms.openlocfilehash: d742c7aca3c06b0b8d43ee3490b2e93ef0387f1f
ms.sourcegitcommit: 766e2840fd16efb901d211d7fa64d96766ac99d9
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 03/31/2021
ms.locfileid: "5774442"
---
# <a name="set-up-business-units-for-business-activity-statements-in-the-australian-version"></a><span data-ttu-id="42905-103">Set Up Business Units for Business Activity Statements in the Australian Version</span><span class="sxs-lookup"><span data-stu-id="42905-103">Set Up Business Units for Business Activity Statements in the Australian Version</span></span>

<span data-ttu-id="42905-104">In [!INCLUDE[prod_short](../../includes/prod_short.md)], you can consolidate the financial statements of various companies into one financial statement.</span><span class="sxs-lookup"><span data-stu-id="42905-104">In [!INCLUDE[prod_short](../../includes/prod_short.md)], you can consolidate the financial statements of various companies into one financial statement.</span></span>  

<span data-ttu-id="42905-105">You must set up a consolidation company to perform the consolidation.</span><span class="sxs-lookup"><span data-stu-id="42905-105">You must set up a consolidation company to perform the consolidation.</span></span> <span data-ttu-id="42905-106">In this company, the total amounts for all accounts in the group, from both the parent company and subsidiaries, are added together.</span><span class="sxs-lookup"><span data-stu-id="42905-106">In this company, the total amounts for all accounts in the group, from both the parent company and subsidiaries, are added together.</span></span> <span data-ttu-id="42905-107">You must also indicate the general ledger accounts in the consolidated company to which the total should be transferred.</span><span class="sxs-lookup"><span data-stu-id="42905-107">You must also indicate the general ledger accounts in the consolidated company to which the total should be transferred.</span></span>  

<span data-ttu-id="42905-108">You can use the **BAS Business Units** page to set up the following:</span><span class="sxs-lookup"><span data-stu-id="42905-108">You can use the **BAS Business Units** page to set up the following:</span></span>  

- <span data-ttu-id="42905-109">Parent company</span><span class="sxs-lookup"><span data-stu-id="42905-109">Parent company</span></span>  
- <span data-ttu-id="42905-110">Subsidiaries</span><span class="sxs-lookup"><span data-stu-id="42905-110">Subsidiaries</span></span>  
- <span data-ttu-id="42905-111">Affiliates</span><span class="sxs-lookup"><span data-stu-id="42905-111">Affiliates</span></span>  

<span data-ttu-id="42905-112">You must provide information on the **General Ledger Setup** page before you can set up business units.</span><span class="sxs-lookup"><span data-stu-id="42905-112">You must provide information on the **General Ledger Setup** page before you can set up business units.</span></span>  

## <a name="to-set-up-a-general-ledger-for-a-business-activity-statement"></a><span data-ttu-id="42905-113">To set up a general ledger for a business activity statement</span><span class="sxs-lookup"><span data-stu-id="42905-113">To set up a general ledger for a business activity statement</span></span>  
1. <span data-ttu-id="42905-114">Choose the ![Lightbulb that opens the Tell Me feature](../../media/ui-search/search_small.png "Tell me what you want to do") icon, enter **General Ledger Setup**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="42905-114">Choose the ![Lightbulb that opens the Tell Me feature](../../media/ui-search/search_small.png "Tell me what you want to do") icon, enter **General Ledger Setup**, and then choose the related link.</span></span>  
2. <span data-ttu-id="42905-115">Fill in the required fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="42905-115">Fill in the required fields as described in the following table.</span></span>  

    |<span data-ttu-id="42905-116">Field</span><span class="sxs-lookup"><span data-stu-id="42905-116">Field</span></span>|<span data-ttu-id="42905-117">Description</span><span class="sxs-lookup"><span data-stu-id="42905-117">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="42905-118">**BAS to be Lodged as a Group**</span><span class="sxs-lookup"><span data-stu-id="42905-118">**BAS to be Lodged as a Group**</span></span>|<span data-ttu-id="42905-119">Select if you are logging a business activity statement for a group of companies.</span><span class="sxs-lookup"><span data-stu-id="42905-119">Select if you are logging a business activity statement for a group of companies.</span></span>|  
    |<span data-ttu-id="42905-120">**BAS Group Company**</span><span class="sxs-lookup"><span data-stu-id="42905-120">**BAS Group Company**</span></span>|<span data-ttu-id="42905-121">Select if this company is the main company in the group of companies for which you are logging a group business activity statement.</span><span class="sxs-lookup"><span data-stu-id="42905-121">Select if this company is the main company in the group of companies for which you are logging a group business activity statement.</span></span>|  

3.  <span data-ttu-id="42905-122">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="42905-122">Choose the **OK** button.</span></span>  

## <a name="to-set-a-business-unit-for-a-business-activity-statement"></a><span data-ttu-id="42905-123">To set a business unit for a business activity statement</span><span class="sxs-lookup"><span data-stu-id="42905-123">To set a business unit for a business activity statement</span></span>  
1. <span data-ttu-id="42905-124">Choose the ![Lightbulb that opens the Tell Me feature](../../media/ui-search/search_small.png "Tell me what you want to do") icon, enter **BAS Business Units**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="42905-124">Choose the ![Lightbulb that opens the Tell Me feature](../../media/ui-search/search_small.png "Tell me what you want to do") icon, enter **BAS Business Units**, and then choose the related link.</span></span>  
2. <span data-ttu-id="42905-125">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="42905-125">Fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="42905-126">Field</span><span class="sxs-lookup"><span data-stu-id="42905-126">Field</span></span>|<span data-ttu-id="42905-127">Description</span><span class="sxs-lookup"><span data-stu-id="42905-127">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="42905-128">**Company Name**</span><span class="sxs-lookup"><span data-stu-id="42905-128">**Company Name**</span></span>|<span data-ttu-id="42905-129">Specify the name of the company that will be added to the group company's business activity statement.</span><span class="sxs-lookup"><span data-stu-id="42905-129">Specify the name of the company that will be added to the group company's business activity statement.</span></span>|  
    |<span data-ttu-id="42905-130">**Document No.**</span><span class="sxs-lookup"><span data-stu-id="42905-130">**Document No.**</span></span>|<span data-ttu-id="42905-131">Specify the BAS document number that has to be consolidated.</span><span class="sxs-lookup"><span data-stu-id="42905-131">Specify the BAS document number that has to be consolidated.</span></span> <span data-ttu-id="42905-132">This field is associated with the **BAS Version** field.</span><span class="sxs-lookup"><span data-stu-id="42905-132">This field is associated with the **BAS Version** field.</span></span>|  
    |<span data-ttu-id="42905-133">**BAS Version**</span><span class="sxs-lookup"><span data-stu-id="42905-133">**BAS Version**</span></span>|<span data-ttu-id="42905-134">Specify the BAS version number in which the transaction was included.</span><span class="sxs-lookup"><span data-stu-id="42905-134">Specify the BAS version number in which the transaction was included.</span></span> <span data-ttu-id="42905-135">This field is associated with the **Document No.** field.</span><span class="sxs-lookup"><span data-stu-id="42905-135">This field is associated with the **Document No.** field.</span></span>|  

3. <span data-ttu-id="42905-136">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="42905-136">Choose the **OK** button.</span></span>  

## <a name="see-also"></a><span data-ttu-id="42905-137">See Also</span><span class="sxs-lookup"><span data-stu-id="42905-137">See Also</span></span>  
[<span data-ttu-id="42905-138">Australian Local Functionality</span><span class="sxs-lookup"><span data-stu-id="42905-138">Australian Local Functionality</span></span>](australia-local-functionality.md)   



[!INCLUDE[footer-include](../../includes/footer-banner.md)]