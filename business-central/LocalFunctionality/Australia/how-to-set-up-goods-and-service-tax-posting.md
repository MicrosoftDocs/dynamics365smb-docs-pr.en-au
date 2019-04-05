---
title: How to Set Up Goods and Service Tax Posting
description: Describes the steps to start applying goods and services tax (GST) to goods and services.
services: project-madeira
documentationcenter: ''
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: ''
ms.date: 10/01/2018
ms.author: sgroespe
ms.openlocfilehash: b4f6df1125bd5f90f05aa183fbd9edeae9fb5277
ms.sourcegitcommit: 1bcfaa99ea302e6b84b8361ca02730b135557fc1
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 03/08/2019
ms.locfileid: "826269"
---
# <a name="set-up-goods-and-service-tax-posting"></a><span data-ttu-id="da274-103">Set Up Goods and Service Tax Posting</span><span class="sxs-lookup"><span data-stu-id="da274-103">Set Up Goods and Service Tax Posting</span></span>
<span data-ttu-id="da274-104">Goods and services tax (GST) is the tax that is applied on most goods and services.</span><span class="sxs-lookup"><span data-stu-id="da274-104">Goods and services tax (GST) is the tax that is applied on most goods and services.</span></span> <span data-ttu-id="da274-105">The GST that is paid and received during a period is reported in the Business Activity Statement (BAS) that has to be submitted to the Australian Taxation Office (ATO).</span><span class="sxs-lookup"><span data-stu-id="da274-105">The GST that is paid and received during a period is reported in the Business Activity Statement (BAS) that has to be submitted to the Australian Taxation Office (ATO).</span></span>  

<span data-ttu-id="da274-106">To set up posting details for GST, you must define the posting groups, rate of GST, and the accounts to which GST is to be posted.</span><span class="sxs-lookup"><span data-stu-id="da274-106">To set up posting details for GST, you must define the posting groups, rate of GST, and the accounts to which GST is to be posted.</span></span> <span data-ttu-id="da274-107">You can set up this information for a particular combination business posting groups and product posting groups.</span><span class="sxs-lookup"><span data-stu-id="da274-107">You can set up this information for a particular combination business posting groups and product posting groups.</span></span>  

<span data-ttu-id="da274-108">You must set up GST posting before you generate the BAS report.</span><span class="sxs-lookup"><span data-stu-id="da274-108">You must set up GST posting before you generate the BAS report.</span></span>  

## <a name="to-set-up-goods-and-sales-tax-posting"></a><span data-ttu-id="da274-109">To set up goods and sales tax posting</span><span class="sxs-lookup"><span data-stu-id="da274-109">To set up goods and sales tax posting</span></span>  
1. <span data-ttu-id="da274-110">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **VAT Posting Setup**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="da274-110">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **VAT Posting Setup**, and then choose the related link.</span></span>  
2. <span data-ttu-id="da274-111">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="da274-111">Fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="da274-112">Field</span><span class="sxs-lookup"><span data-stu-id="da274-112">Field</span></span>|<span data-ttu-id="da274-113">Description</span><span class="sxs-lookup"><span data-stu-id="da274-113">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="da274-114">**GST Bus. Posting Group**</span><span class="sxs-lookup"><span data-stu-id="da274-114">**VAT Bus. Posting Group**</span></span>|<span data-ttu-id="da274-115">Specifies the GST business posting group code.</span><span class="sxs-lookup"><span data-stu-id="da274-115">Specifies the VAT business posting group code.</span></span>|  
    |<span data-ttu-id="da274-116">**GST Prod. Posting Group**</span><span class="sxs-lookup"><span data-stu-id="da274-116">**VAT Prod. Posting Group**</span></span>|<span data-ttu-id="da274-117">Specifies the GST product posting group code.</span><span class="sxs-lookup"><span data-stu-id="da274-117">Specifies the VAT product posting group code.</span></span>|  
    |<span data-ttu-id="da274-118">**GST Identifier**</span><span class="sxs-lookup"><span data-stu-id="da274-118">**VAT Identifier**</span></span>|<span data-ttu-id="da274-119">Specifies the code that is used to group similar GST setups with similar attributes.</span><span class="sxs-lookup"><span data-stu-id="da274-119">Specifies the code that is used to group similar VAT setups with similar attributes.</span></span><br /><br /> <span data-ttu-id="da274-120">For example, you can group a number of GST posting setups that have a common GST percentage.</span><span class="sxs-lookup"><span data-stu-id="da274-120">For example, you can group a number of VAT posting setups that have a common VAT percentage.</span></span>|  
    |<span data-ttu-id="da274-121">**GST %**</span><span class="sxs-lookup"><span data-stu-id="da274-121">**VAT %**</span></span>|<span data-ttu-id="da274-122">Specifies the GST rate.</span><span class="sxs-lookup"><span data-stu-id="da274-122">Specifies the VAT rate.</span></span>|  
    |<span data-ttu-id="da274-123">**GST Calculation Type**</span><span class="sxs-lookup"><span data-stu-id="da274-123">**VAT Calculation Type**</span></span>|<span data-ttu-id="da274-124">Specifies the method that is used to calculate the purchase or sale of items.</span><span class="sxs-lookup"><span data-stu-id="da274-124">Specifies the method that is used to calculate the purchase or sale of items.</span></span>|  
    |<span data-ttu-id="da274-125">**GST Account**</span><span class="sxs-lookup"><span data-stu-id="da274-125">**Sales VAT Account**</span></span>|<span data-ttu-id="da274-126">Specifies the number of the general ledger account to which you want to post the sales GST.</span><span class="sxs-lookup"><span data-stu-id="da274-126">Specifies the number of the general ledger account to which you want to post the sales VAT.</span></span><br /><br /> <span data-ttu-id="da274-127">If you have selected the **Reverse Charge GST** option in the **GST Calculation Type** field, then do not enter a value in this field.</span><span class="sxs-lookup"><span data-stu-id="da274-127">If you have selected the **Reverse Charge VAT** option in the **VAT Calculation Type** field, then do not enter a value in this field.</span></span>|  
    |<span data-ttu-id="da274-128">**Input Tax Credit Account**</span><span class="sxs-lookup"><span data-stu-id="da274-128">**Purchase VAT Account**</span></span>|<span data-ttu-id="da274-129">Specifies the number of the general ledger account to which you want to post the input tax credit.</span><span class="sxs-lookup"><span data-stu-id="da274-129">Specifies the number of the general ledger account to which you want to post the purchase VAT.</span></span>|  
    |<span data-ttu-id="da274-130">**Reverse Chrg. GST Acc.**</span><span class="sxs-lookup"><span data-stu-id="da274-130">**Reverse Chrg. VAT Acc.**</span></span>|<span data-ttu-id="da274-131">Specifies the number of the general ledger account to which you want to post the reverse charge GST.</span><span class="sxs-lookup"><span data-stu-id="da274-131">Specifies the number of the general ledger account to which you want to post the reverse charge VAT.</span></span><br /><br /> <span data-ttu-id="da274-132">You can enter a value in this field only if you have selected the **Reverse Charge GST** option in the **GST Calculation Type** field.</span><span class="sxs-lookup"><span data-stu-id="da274-132">You can enter a value in this field only if you have selected the **Reverse Charge VAT** option in the **VAT Calculation Type** field.</span></span>|  

3.  <span data-ttu-id="da274-133">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="da274-133">Choose the **OK** button.</span></span>  

## <a name="see-also"></a><span data-ttu-id="da274-134">See Also</span><span class="sxs-lookup"><span data-stu-id="da274-134">See Also</span></span>  
<span data-ttu-id="da274-135">[Australian Local Functionality](australia-local-functionality.md)
[Print Goods and Service Tax Settlement Reports](how-to-print-goods-and-service-tax-settlement-reports.md)</span><span class="sxs-lookup"><span data-stu-id="da274-135">[Australian Local Functionality](australia-local-functionality.md)
[Print Goods and Service Tax Settlement Reports](how-to-print-goods-and-service-tax-settlement-reports.md)</span></span>
