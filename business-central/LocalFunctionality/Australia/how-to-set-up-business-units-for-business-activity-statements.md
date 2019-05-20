---
title: How to Set Up Business Units for Business Activity Statements
description: Describes how to consolidate the financial statements of various companies into one financial statement.
services: project-madeira
documentationcenter: ''
author: bholtorf
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: ''
ms.date: 04/01/2019
ms.author: bholtorf
ms.openlocfilehash: 26c6c10c582c5e1302b260f9a90f9b651d3fb861
ms.sourcegitcommit: 60b87e5eb32bb408dd65b9855c29159b1dfbfca8
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 04/29/2019
ms.locfileid: "1237873"
---
# <a name="set-up-business-units-for-business-activity-statements"></a><span data-ttu-id="eef71-103">Set Up Business Units for Business Activity Statements</span><span class="sxs-lookup"><span data-stu-id="eef71-103">Set Up Business Units for Business Activity Statements</span></span>
<span data-ttu-id="eef71-104">In [!INCLUDE[d365fin](../../includes/d365fin_md.md)], you can consolidate the financial statements of various companies into one financial statement.</span><span class="sxs-lookup"><span data-stu-id="eef71-104">In [!INCLUDE[d365fin](../../includes/d365fin_md.md)], you can consolidate the financial statements of various companies into one financial statement.</span></span>  

<span data-ttu-id="eef71-105">You must set up a consolidation company to perform the consolidation.</span><span class="sxs-lookup"><span data-stu-id="eef71-105">You must set up a consolidation company to perform the consolidation.</span></span> <span data-ttu-id="eef71-106">In this company, the total amounts for all accounts in the group, from both the parent company and subsidiaries are added together.</span><span class="sxs-lookup"><span data-stu-id="eef71-106">In this company, the total amounts for all accounts in the group, from both the parent company and subsidiaries are added together.</span></span> <span data-ttu-id="eef71-107">You must also indicate the general ledger accounts in the consolidated company to which the total should be transferred.</span><span class="sxs-lookup"><span data-stu-id="eef71-107">You must also indicate the general ledger accounts in the consolidated company to which the total should be transferred.</span></span>  

<span data-ttu-id="eef71-108">You can use the **BAS Business Units** page to set up the following:</span><span class="sxs-lookup"><span data-stu-id="eef71-108">You can use the **BAS Business Units** page to set up the following:</span></span>  

- <span data-ttu-id="eef71-109">Parent company</span><span class="sxs-lookup"><span data-stu-id="eef71-109">Parent company</span></span>  
- <span data-ttu-id="eef71-110">Subsidiaries</span><span class="sxs-lookup"><span data-stu-id="eef71-110">Subsidiaries</span></span>  
- <span data-ttu-id="eef71-111">Affiliates</span><span class="sxs-lookup"><span data-stu-id="eef71-111">Affiliates</span></span>  

<span data-ttu-id="eef71-112">You must set up information on the **General Ledger Setup** page before you can set up business units.</span><span class="sxs-lookup"><span data-stu-id="eef71-112">You must set up information on the **General Ledger Setup** page before you can set up business units.</span></span>  

## <a name="to-set-up-general-ledger-for-a-business-activity-statement"></a><span data-ttu-id="eef71-113">To set up general ledger for a business activity statement</span><span class="sxs-lookup"><span data-stu-id="eef71-113">To set up general ledger for a business activity statement</span></span>  
1. <span data-ttu-id="eef71-114">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **General Ledger Setup**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="eef71-114">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **General Ledger Setup**, and then choose the related link.</span></span>  
2. <span data-ttu-id="eef71-115">Fill in the required fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="eef71-115">Fill in the required fields as described in the following table.</span></span>  

    |<span data-ttu-id="eef71-116">Field</span><span class="sxs-lookup"><span data-stu-id="eef71-116">Field</span></span>|<span data-ttu-id="eef71-117">Description</span><span class="sxs-lookup"><span data-stu-id="eef71-117">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="eef71-118">**BAS to be Lodged as a Group**</span><span class="sxs-lookup"><span data-stu-id="eef71-118">**BAS to be Lodged as a Group**</span></span>|<span data-ttu-id="eef71-119">Select if you are logging a business activity statement for a group of companies.</span><span class="sxs-lookup"><span data-stu-id="eef71-119">Select if you are logging a business activity statement for a group of companies.</span></span>|  
    |<span data-ttu-id="eef71-120">**BAS Group Company**</span><span class="sxs-lookup"><span data-stu-id="eef71-120">**BAS Group Company**</span></span>|<span data-ttu-id="eef71-121">Select if this company is the main company in the group of companies for which you are lodging a group business activity statement.</span><span class="sxs-lookup"><span data-stu-id="eef71-121">Select if this company is the main company in the group of companies for which you are lodging a group business activity statement.</span></span>|  

3.  <span data-ttu-id="eef71-122">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="eef71-122">Choose the **OK** button.</span></span>  

## <a name="to-set-a-business-unit-for-a-business-activity-statement"></a><span data-ttu-id="eef71-123">To set a business unit for a business activity statement</span><span class="sxs-lookup"><span data-stu-id="eef71-123">To set a business unit for a business activity statement</span></span>  
1. <span data-ttu-id="eef71-124">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **BAS Business Units**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="eef71-124">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **BAS Business Units**, and then choose the related link.</span></span>  
2. <span data-ttu-id="eef71-125">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="eef71-125">Fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="eef71-126">Field</span><span class="sxs-lookup"><span data-stu-id="eef71-126">Field</span></span>|<span data-ttu-id="eef71-127">Description</span><span class="sxs-lookup"><span data-stu-id="eef71-127">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="eef71-128">**Company Name**</span><span class="sxs-lookup"><span data-stu-id="eef71-128">**Company Name**</span></span>|<span data-ttu-id="eef71-129">Specify the name of the company which will be added to the group company's business activity statement.</span><span class="sxs-lookup"><span data-stu-id="eef71-129">Specify the name of the company which will be added to the group company's business activity statement.</span></span>|  
    |<span data-ttu-id="eef71-130">**Document No.**</span><span class="sxs-lookup"><span data-stu-id="eef71-130">**Document No.**</span></span>|<span data-ttu-id="eef71-131">Specify the BAS document number that has to be consolidated.</span><span class="sxs-lookup"><span data-stu-id="eef71-131">Specify the BAS document number that has to be consolidated.</span></span> <span data-ttu-id="eef71-132">This field is associated with the **BAS Version** field.</span><span class="sxs-lookup"><span data-stu-id="eef71-132">This field is associated with the **BAS Version** field.</span></span>|  
    |<span data-ttu-id="eef71-133">**BAS Version**</span><span class="sxs-lookup"><span data-stu-id="eef71-133">**BAS Version**</span></span>|<span data-ttu-id="eef71-134">Specify the BAS version number in which the transaction was included.</span><span class="sxs-lookup"><span data-stu-id="eef71-134">Specify the BAS version number in which the transaction was included.</span></span> <span data-ttu-id="eef71-135">This field is associated with the **Document No.** field.</span><span class="sxs-lookup"><span data-stu-id="eef71-135">This field is associated with the **Document No.** field.</span></span>|  

3. <span data-ttu-id="eef71-136">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="eef71-136">Choose the **OK** button.</span></span>  

## <a name="see-also"></a><span data-ttu-id="eef71-137">See Also</span><span class="sxs-lookup"><span data-stu-id="eef71-137">See Also</span></span>  
[<span data-ttu-id="eef71-138">Australian Local Functionality</span><span class="sxs-lookup"><span data-stu-id="eef71-138">Australian Local Functionality</span></span>](australia-local-functionality.md)   

