---
title: How to Determine Sales Price by Cost Plus Percentage
description: Use the cost plus percentage function to set a sales price based on the cost of an item. The cost of the item can be calculated along with cost plus calculation. The discount will be based on this calculation.
services: project-madeira
ms.custom: en-CA, fr-CA
documentationcenter: ''
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: ''
ms.date: 04/01/2019
ms.author: sgroespe
ms.openlocfilehash: d4e0034b27a8827f9db8238e7ab21cc311d604fa
ms.sourcegitcommit: 60b87e5eb32bb408dd65b9855c29159b1dfbfca8
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 04/29/2019
ms.locfileid: "1237739"
---
# <a name="determine-sales-price-by-cost-plus-percentage"></a><span data-ttu-id="c1ea5-105">Determine Sales Price by Cost Plus Percentage</span><span class="sxs-lookup"><span data-stu-id="c1ea5-105">Determine Sales Price by Cost Plus Percentage</span></span>
<span data-ttu-id="c1ea5-106">Use the cost plus percentage function to set a sales price based on the cost of an item.</span><span class="sxs-lookup"><span data-stu-id="c1ea5-106">Use the cost plus percentage function to set a sales price based on the cost of an item.</span></span> <span data-ttu-id="c1ea5-107">The cost of the item can be calculated along with cost plus calculation.</span><span class="sxs-lookup"><span data-stu-id="c1ea5-107">The cost of the item can be calculated along with cost plus calculation.</span></span> <span data-ttu-id="c1ea5-108">The discount will be based on this calculation.</span><span class="sxs-lookup"><span data-stu-id="c1ea5-108">The discount will be based on this calculation.</span></span> <span data-ttu-id="c1ea5-109">This functionality eliminates the need for the use of spreadsheets in determining percentage discounts as they correspond to cost plus percentage.</span><span class="sxs-lookup"><span data-stu-id="c1ea5-109">This functionality eliminates the need for the use of spreadsheets in determining percentage discounts as they correspond to cost plus percentage.</span></span>  

## <a name="to-determine-sales-tax-by-cost-plus-percentage"></a><span data-ttu-id="c1ea5-110">To determine US sales tax by cost plus percentage</span><span class="sxs-lookup"><span data-stu-id="c1ea5-110">To determine sales tax by cost plus percentage</span></span>  

1.  <span data-ttu-id="c1ea5-111">Choose the **Receivables** action.</span><span class="sxs-lookup"><span data-stu-id="c1ea5-111">Choose the **Receivables** action.</span></span>  
3.  <span data-ttu-id="c1ea5-112">Choose the **Customers** action.</span><span class="sxs-lookup"><span data-stu-id="c1ea5-112">Choose the **Customers** action.</span></span>  
4.  <span data-ttu-id="c1ea5-113">Open the card for a relevant customer.</span><span class="sxs-lookup"><span data-stu-id="c1ea5-113">Open the card for a relevant customer.</span></span>  

     <span data-ttu-id="c1ea5-114">–or–</span><span class="sxs-lookup"><span data-stu-id="c1ea5-114">–or–</span></span>  

    <span data-ttu-id="c1ea5-115">Choose the **New** action.</span><span class="sxs-lookup"><span data-stu-id="c1ea5-115">Choose the **New** action.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="c1ea5-116">For a new customer, in the **No.**</span><span class="sxs-lookup"><span data-stu-id="c1ea5-116">For a new customer, in the **No.**</span></span> <span data-ttu-id="c1ea5-117">field, enter the customer number.</span><span class="sxs-lookup"><span data-stu-id="c1ea5-117">field, enter the customer number.</span></span>  

5.  <span data-ttu-id="c1ea5-118">To open the **Sales Prices** page, choose the **Prices** action.</span><span class="sxs-lookup"><span data-stu-id="c1ea5-118">To open the **Sales Prices** page, choose the **Prices** action.</span></span>  
6.  <span data-ttu-id="c1ea5-119">In the **General** section, fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="c1ea5-119">In the **General** section, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="c1ea5-120">Field</span><span class="sxs-lookup"><span data-stu-id="c1ea5-120">Field</span></span>|<span data-ttu-id="c1ea5-121">Description</span><span class="sxs-lookup"><span data-stu-id="c1ea5-121">Description</span></span>|  
    |-----------|-----------------|  
    |<span data-ttu-id="c1ea5-122">**Sales Type Filter**</span><span class="sxs-lookup"><span data-stu-id="c1ea5-122">**Sales Type Filter**</span></span>|<span data-ttu-id="c1ea5-123">Select one of the following options:</span><span class="sxs-lookup"><span data-stu-id="c1ea5-123">Select one of the following options:</span></span><br /><br /> <span data-ttu-id="c1ea5-124">-   **Customer**</span><span class="sxs-lookup"><span data-stu-id="c1ea5-124">-   **Customer**</span></span><br /><span data-ttu-id="c1ea5-125">-   **Customer Price Group**</span><span class="sxs-lookup"><span data-stu-id="c1ea5-125">-   **Customer Price Group**</span></span><br /><span data-ttu-id="c1ea5-126">-   **All Customers**</span><span class="sxs-lookup"><span data-stu-id="c1ea5-126">-   **All Customers**</span></span><br /><span data-ttu-id="c1ea5-127">-   **Campaign**</span><span class="sxs-lookup"><span data-stu-id="c1ea5-127">-   **Campaign**</span></span><br /><span data-ttu-id="c1ea5-128">-   **None**</span><span class="sxs-lookup"><span data-stu-id="c1ea5-128">-   **None**</span></span>|  
    |<span data-ttu-id="c1ea5-129">**Sales Code Filter**</span><span class="sxs-lookup"><span data-stu-id="c1ea5-129">**Sales Code Filter**</span></span>|<span data-ttu-id="c1ea5-130">The sales code.</span><span class="sxs-lookup"><span data-stu-id="c1ea5-130">The sales code.</span></span>|  
    |<span data-ttu-id="c1ea5-131">**Item No. Filter**</span><span class="sxs-lookup"><span data-stu-id="c1ea5-131">**Item No. Filter**</span></span>|<span data-ttu-id="c1ea5-132">The item number.</span><span class="sxs-lookup"><span data-stu-id="c1ea5-132">The item number.</span></span>|  
    |<span data-ttu-id="c1ea5-133">**Starting Date Filter**</span><span class="sxs-lookup"><span data-stu-id="c1ea5-133">**Starting Date Filter**</span></span>|<span data-ttu-id="c1ea5-134">The starting date.</span><span class="sxs-lookup"><span data-stu-id="c1ea5-134">The starting date.</span></span>|  
    |<span data-ttu-id="c1ea5-135">**Currency Code Filter**</span><span class="sxs-lookup"><span data-stu-id="c1ea5-135">**Currency Code Filter**</span></span>|<span data-ttu-id="c1ea5-136">The currency code.</span><span class="sxs-lookup"><span data-stu-id="c1ea5-136">The currency code.</span></span>|  

7.  <span data-ttu-id="c1ea5-137">Enter information into the relevant fields.</span><span class="sxs-lookup"><span data-stu-id="c1ea5-137">Enter information into the relevant fields.</span></span>  
8.  <span data-ttu-id="c1ea5-138">To send the details to a recipient, choose the **Send To** action, and then select one of the following formats:</span><span class="sxs-lookup"><span data-stu-id="c1ea5-138">To send the details to a recipient, choose the **Send To** action, and then select one of the following formats:</span></span>  

    - <span data-ttu-id="c1ea5-139">**Recipient as Attachment**</span><span class="sxs-lookup"><span data-stu-id="c1ea5-139">**Recipient as Attachment**</span></span>  
    - <span data-ttu-id="c1ea5-140">**Microsoft Word**</span><span class="sxs-lookup"><span data-stu-id="c1ea5-140">**Microsoft Word**</span></span>  
    - <span data-ttu-id="c1ea5-141">**Microsoft Excel**</span><span class="sxs-lookup"><span data-stu-id="c1ea5-141">**Microsoft Excel**</span></span>  

9. <span data-ttu-id="c1ea5-142">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="c1ea5-142">Choose the **OK** button.</span></span>  

## <a name="see-also"></a><span data-ttu-id="c1ea5-143">See Also</span><span class="sxs-lookup"><span data-stu-id="c1ea5-143">See Also</span></span>  
 [<span data-ttu-id="c1ea5-144">Australia Local Functionality</span><span class="sxs-lookup"><span data-stu-id="c1ea5-144">Australia Local Functionality</span></span>](australia-local-functionality.md)
