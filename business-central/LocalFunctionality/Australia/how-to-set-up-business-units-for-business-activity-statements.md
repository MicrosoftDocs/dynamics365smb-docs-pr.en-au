---
title: Set Up Business Units for Business Activity Statements (AU)
description: Describes how to consolidate the financial statements of various companies into one financial statement.
author: bholtorf
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: ''
ms.date: 10/01/2020
ms.author: bholtorf
ms.openlocfilehash: 21b36e721b9be780f320c422e10d13c60bd70873
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 10/01/2020
ms.locfileid: "3914674"
---
# <a name="set-up-business-units-for-business-activity-statements-in-the-australian-version"></a><span data-ttu-id="af148-103">Set Up Business Units for Business Activity Statements in the Australian Version</span><span class="sxs-lookup"><span data-stu-id="af148-103">Set Up Business Units for Business Activity Statements in the Australian Version</span></span>

<span data-ttu-id="af148-104">In [!INCLUDE[d365fin](../../includes/d365fin_md.md)], you can consolidate the financial statements of various companies into one financial statement.</span><span class="sxs-lookup"><span data-stu-id="af148-104">In [!INCLUDE[d365fin](../../includes/d365fin_md.md)], you can consolidate the financial statements of various companies into one financial statement.</span></span>  

<span data-ttu-id="af148-105">You must set up a consolidation company to perform the consolidation.</span><span class="sxs-lookup"><span data-stu-id="af148-105">You must set up a consolidation company to perform the consolidation.</span></span> <span data-ttu-id="af148-106">In this company, the total amounts for all accounts in the group, from both the parent company and subsidiaries, are added together.</span><span class="sxs-lookup"><span data-stu-id="af148-106">In this company, the total amounts for all accounts in the group, from both the parent company and subsidiaries, are added together.</span></span> <span data-ttu-id="af148-107">You must also indicate the general ledger accounts in the consolidated company to which the total should be transferred.</span><span class="sxs-lookup"><span data-stu-id="af148-107">You must also indicate the general ledger accounts in the consolidated company to which the total should be transferred.</span></span>  

<span data-ttu-id="af148-108">You can use the **BAS Business Units** page to set up the following:</span><span class="sxs-lookup"><span data-stu-id="af148-108">You can use the **BAS Business Units** page to set up the following:</span></span>  

- <span data-ttu-id="af148-109">Parent company</span><span class="sxs-lookup"><span data-stu-id="af148-109">Parent company</span></span>  
- <span data-ttu-id="af148-110">Subsidiaries</span><span class="sxs-lookup"><span data-stu-id="af148-110">Subsidiaries</span></span>  
- <span data-ttu-id="af148-111">Affiliates</span><span class="sxs-lookup"><span data-stu-id="af148-111">Affiliates</span></span>  

<span data-ttu-id="af148-112">You must provide information on the **General Ledger Setup** page before you can set up business units.</span><span class="sxs-lookup"><span data-stu-id="af148-112">You must provide information on the **General Ledger Setup** page before you can set up business units.</span></span>  

## <a name="to-set-up-a-general-ledger-for-a-business-activity-statement"></a><span data-ttu-id="af148-113">To set up a general ledger for a business activity statement</span><span class="sxs-lookup"><span data-stu-id="af148-113">To set up a general ledger for a business activity statement</span></span>  
1. <span data-ttu-id="af148-114">Choose the ![Lightbulb that opens the Tell Me feature](../../media/ui-search/search_small.png "Tell me what you want to do") icon, enter **General Ledger Setup** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="af148-114">Choose the ![Lightbulb that opens the Tell Me feature](../../media/ui-search/search_small.png "Tell me what you want to do") icon, enter **General Ledger Setup** , and then choose the related link.</span></span>  
2. <span data-ttu-id="af148-115">Fill in the required fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="af148-115">Fill in the required fields as described in the following table.</span></span>  

    |<span data-ttu-id="af148-116">Field</span><span class="sxs-lookup"><span data-stu-id="af148-116">Field</span></span>|<span data-ttu-id="af148-117">Description</span><span class="sxs-lookup"><span data-stu-id="af148-117">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="af148-118">**BAS to be Lodged as a Group**</span><span class="sxs-lookup"><span data-stu-id="af148-118">**BAS to be Lodged as a Group**</span></span>|<span data-ttu-id="af148-119">Select if you are logging a business activity statement for a group of companies.</span><span class="sxs-lookup"><span data-stu-id="af148-119">Select if you are logging a business activity statement for a group of companies.</span></span>|  
    |<span data-ttu-id="af148-120">**BAS Group Company**</span><span class="sxs-lookup"><span data-stu-id="af148-120">**BAS Group Company**</span></span>|<span data-ttu-id="af148-121">Select if this company is the main company in the group of companies for which you are logging a group business activity statement.</span><span class="sxs-lookup"><span data-stu-id="af148-121">Select if this company is the main company in the group of companies for which you are logging a group business activity statement.</span></span>|  

3.  <span data-ttu-id="af148-122">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="af148-122">Choose the **OK** button.</span></span>  

## <a name="to-set-a-business-unit-for-a-business-activity-statement"></a><span data-ttu-id="af148-123">To set a business unit for a business activity statement</span><span class="sxs-lookup"><span data-stu-id="af148-123">To set a business unit for a business activity statement</span></span>  
1. <span data-ttu-id="af148-124">Choose the ![Lightbulb that opens the Tell Me feature](../../media/ui-search/search_small.png "Tell me what you want to do") icon, enter **BAS Business Units** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="af148-124">Choose the ![Lightbulb that opens the Tell Me feature](../../media/ui-search/search_small.png "Tell me what you want to do") icon, enter **BAS Business Units** , and then choose the related link.</span></span>  
2. <span data-ttu-id="af148-125">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="af148-125">Fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="af148-126">Field</span><span class="sxs-lookup"><span data-stu-id="af148-126">Field</span></span>|<span data-ttu-id="af148-127">Description</span><span class="sxs-lookup"><span data-stu-id="af148-127">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="af148-128">**Company Name**</span><span class="sxs-lookup"><span data-stu-id="af148-128">**Company Name**</span></span>|<span data-ttu-id="af148-129">Specify the name of the company that will be added to the group company's business activity statement.</span><span class="sxs-lookup"><span data-stu-id="af148-129">Specify the name of the company that will be added to the group company's business activity statement.</span></span>|  
    |<span data-ttu-id="af148-130">**Document No.**</span><span class="sxs-lookup"><span data-stu-id="af148-130">**Document No.**</span></span>|<span data-ttu-id="af148-131">Specify the BAS document number that has to be consolidated.</span><span class="sxs-lookup"><span data-stu-id="af148-131">Specify the BAS document number that has to be consolidated.</span></span> <span data-ttu-id="af148-132">This field is associated with the **BAS Version** field.</span><span class="sxs-lookup"><span data-stu-id="af148-132">This field is associated with the **BAS Version** field.</span></span>|  
    |<span data-ttu-id="af148-133">**BAS Version**</span><span class="sxs-lookup"><span data-stu-id="af148-133">**BAS Version**</span></span>|<span data-ttu-id="af148-134">Specify the BAS version number in which the transaction was included.</span><span class="sxs-lookup"><span data-stu-id="af148-134">Specify the BAS version number in which the transaction was included.</span></span> <span data-ttu-id="af148-135">This field is associated with the **Document No.** field.</span><span class="sxs-lookup"><span data-stu-id="af148-135">This field is associated with the **Document No.** field.</span></span>|  

3. <span data-ttu-id="af148-136">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="af148-136">Choose the **OK** button.</span></span>  

## <a name="see-also"></a><span data-ttu-id="af148-137">See Also</span><span class="sxs-lookup"><span data-stu-id="af148-137">See Also</span></span>  
[<span data-ttu-id="af148-138">Australian Local Functionality</span><span class="sxs-lookup"><span data-stu-id="af148-138">Australian Local Functionality</span></span>](australia-local-functionality.md)   

