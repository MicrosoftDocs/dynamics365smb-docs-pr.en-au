---
title: Optional Activities for Closing Periods | Microsoft Docs
description: This topic outlines the optional processes and activities for closing accounting periods in Business Central.
services: project-madeira
documentationcenter: ''
author: jswymer
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: year closing, close accounting period, close fiscal year, aging, creditor payments, vendor payments
ms.date: 10/01/2020
ms.author: jswymer
ms.openlocfilehash: 104f63e07e4bfd8945f73581a4fb7810f946304f
ms.sourcegitcommit: 2e7307fbe1eb3b34d0ad9356226a19409054a402
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 12/17/2020
ms.locfileid: "4755575"
---
# <a name="overview-of-tasks-to-close-accounting-periods"></a><span data-ttu-id="82841-103">Overview of Tasks to Close Accounting Periods</span><span class="sxs-lookup"><span data-stu-id="82841-103">Overview of Tasks to Close Accounting Periods</span></span>
[!INCLUDE[prod_short](includes/prod_short.md)] <span data-ttu-id="82841-104">does not force you to close periods, however, there are many period-end (month-end) activities that you can do.</span><span class="sxs-lookup"><span data-stu-id="82841-104">does not force you to close periods, however, there are many period-end (month-end) activities that you can do.</span></span> <span data-ttu-id="82841-105">This topic provides an overview of optional processes and activities for closing periods.</span><span class="sxs-lookup"><span data-stu-id="82841-105">This topic provides an overview of optional processes and activities for closing periods.</span></span>  

## <a name="general-ledger"></a><span data-ttu-id="82841-106">General Ledger</span><span class="sxs-lookup"><span data-stu-id="82841-106">General Ledger</span></span>
* <span data-ttu-id="82841-107">Specify system-wide and user-specific posting periods.</span><span class="sxs-lookup"><span data-stu-id="82841-107">Specify system-wide and user-specific posting periods.</span></span>  

    <span data-ttu-id="82841-108">This specifies the dates between which you allow posting.</span><span class="sxs-lookup"><span data-stu-id="82841-108">This specifies the dates between which you allow posting.</span></span> <span data-ttu-id="82841-109">Depending on your business, you may want to allow posting at the start of the period, or toward the end.</span><span class="sxs-lookup"><span data-stu-id="82841-109">Depending on your business, you may want to allow posting at the start of the period, or toward the end.</span></span> <span data-ttu-id="82841-110">For more information, see [Specify Posting Periods](finance-how-specify-posting-periods.md).</span><span class="sxs-lookup"><span data-stu-id="82841-110">For more information, see [Specify Posting Periods](finance-how-specify-posting-periods.md).</span></span>  
* <span data-ttu-id="82841-111">Make all necessary G/L adjustments.</span><span class="sxs-lookup"><span data-stu-id="82841-111">Make all necessary G/L adjustments.</span></span>  
* <span data-ttu-id="82841-112">Update and post Recurring Journals.</span><span class="sxs-lookup"><span data-stu-id="82841-112">Update and post Recurring Journals.</span></span>  
  <!--* Process Consolidations-->
* <span data-ttu-id="82841-113">Run account schedules as follows:</span><span class="sxs-lookup"><span data-stu-id="82841-113">Run account schedules as follows:</span></span>  
  * <span data-ttu-id="82841-114">Open the **Account Schedule** page, and then choose the **Print** action.</span><span class="sxs-lookup"><span data-stu-id="82841-114">Open the **Account Schedule** page, and then choose the **Print** action.</span></span>  

## <a name="sales-and-receivables"></a><span data-ttu-id="82841-115">Sales and Receivables</span><span class="sxs-lookup"><span data-stu-id="82841-115">Sales and Receivables</span></span>
* <span data-ttu-id="82841-116">Post all sales orders, invoices, credit memos, and return orders.</span><span class="sxs-lookup"><span data-stu-id="82841-116">Post all sales orders, invoices, credit memos, and return orders.</span></span>  
* <span data-ttu-id="82841-117">Post all cash receipt journals.</span><span class="sxs-lookup"><span data-stu-id="82841-117">Post all cash receipt journals.</span></span>  
* <span data-ttu-id="82841-118">Update and post recurring journals that are related to sales and receivables.</span><span class="sxs-lookup"><span data-stu-id="82841-118">Update and post recurring journals that are related to sales and receivables.</span></span>  
* <span data-ttu-id="82841-119">Reconcile accounts receivable to the general ledger.</span><span class="sxs-lookup"><span data-stu-id="82841-119">Reconcile accounts receivable to the general ledger.</span></span>  
* <span data-ttu-id="82841-120">Run the **Delete Invoiced Sales Orders** batch job.</span><span class="sxs-lookup"><span data-stu-id="82841-120">Run the **Delete Invoiced Sales Orders** batch job.</span></span>  

## <a name="purchases-and-payables"></a><span data-ttu-id="82841-121">Purchases and Payables</span><span class="sxs-lookup"><span data-stu-id="82841-121">Purchases and Payables</span></span>
* <span data-ttu-id="82841-122">Post all purchase orders, invoices, credit memos, and return orders.</span><span class="sxs-lookup"><span data-stu-id="82841-122">Post all purchase orders, invoices, credit memos, and return orders.</span></span>  
* <span data-ttu-id="82841-123">Post all payment journals.</span><span class="sxs-lookup"><span data-stu-id="82841-123">Post all payment journals.</span></span>  
* <span data-ttu-id="82841-124">Update and post recurring journals that are related to purchases & payables.</span><span class="sxs-lookup"><span data-stu-id="82841-124">Update and post recurring journals that are related to purchases & payables.</span></span>  
* <span data-ttu-id="82841-125">Run the **Aged Accounts Payable** report and reconcile accounts payable to the general ledger.</span><span class="sxs-lookup"><span data-stu-id="82841-125">Run the **Aged Accounts Payable** report and reconcile accounts payable to the general ledger.</span></span>  
* <span data-ttu-id="82841-126">Run the **Delete Invoiced Purchase Orders** batch job.</span><span class="sxs-lookup"><span data-stu-id="82841-126">Run the **Delete Invoiced Purchase Orders** batch job.</span></span>  

<span data-ttu-id="82841-127">Fixed Assets</span><span class="sxs-lookup"><span data-stu-id="82841-127">Fixed Assets</span></span>
* <span data-ttu-id="82841-128">Post all maintenance costs have been posted through the fixed asset journals or invoices.</span><span class="sxs-lookup"><span data-stu-id="82841-128">Post all maintenance costs have been posted through the fixed asset journals or invoices.</span></span>
* <span data-ttu-id="82841-129">Post adjustments.</span><span class="sxs-lookup"><span data-stu-id="82841-129">Post adjustments.</span></span>
* <span data-ttu-id="82841-130">Post appreciation.</span><span class="sxs-lookup"><span data-stu-id="82841-130">Post appreciation.</span></span>
* <span data-ttu-id="82841-131">Post depreciation.</span><span class="sxs-lookup"><span data-stu-id="82841-131">Post depreciation.</span></span>
* <span data-ttu-id="82841-132">Update and post the recurring fixed asset journal.</span><span class="sxs-lookup"><span data-stu-id="82841-132">Update and post the recurring fixed asset journal.</span></span>

<span data-ttu-id="82841-133">Intercompany</span><span class="sxs-lookup"><span data-stu-id="82841-133">Intercompany</span></span>
* <span data-ttu-id="82841-134">Process Intercompany Transactions</span><span class="sxs-lookup"><span data-stu-id="82841-134">Process Intercompany Transactions</span></span>

## <a name="calculate-and-process-sales-tax"></a><span data-ttu-id="82841-135">Calculate and Process Sales Tax</span><span class="sxs-lookup"><span data-stu-id="82841-135">Calculate and Process Sales Tax</span></span>
* <span data-ttu-id="82841-136">Complete Tax Statements.</span><span class="sxs-lookup"><span data-stu-id="82841-136">Complete Tax Statements.</span></span>  

## <a name="see-also"></a><span data-ttu-id="82841-137">See Also</span><span class="sxs-lookup"><span data-stu-id="82841-137">See Also</span></span>
[<span data-ttu-id="82841-138">Closing Years and Periods</span><span class="sxs-lookup"><span data-stu-id="82841-138">Closing Years and Periods</span></span>](year-close-years-periods.md)  
[<span data-ttu-id="82841-139">Closing Books</span><span class="sxs-lookup"><span data-stu-id="82841-139">Closing Books</span></span>](year-close-books.md)  
<span data-ttu-id="82841-140">[Working with [!INCLUDE[prod_short](includes/prod_short.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="82841-140">[Working with [!INCLUDE[prod_short](includes/prod_short.md)]](ui-work-product.md)</span></span>
