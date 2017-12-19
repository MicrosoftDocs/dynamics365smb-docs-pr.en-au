---
title: Process Incoming and Outgoing IC Transactions| Microsoft Docs
description: Intercompany transactions that you receive from your intercompany partners are listed in the intercompany inbox where you process them manually or automatically.
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: incoming document
ms.date: 07/07/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 2c13559bb3dc44cdb61697f5135c5b931e34d2a8
ms.openlocfilehash: 5cf49fa7b1c2d4385cd05f44e10237078e1214a4
ms.contentlocale: en-au
ms.lasthandoff: 09/22/2017

---
# <a name="how-to-manage-the-intercompany-inbox-and-outbox"></a><span data-ttu-id="043a2-103">How to: Manage the Intercompany Inbox and Outbox</span><span class="sxs-lookup"><span data-stu-id="043a2-103">How to: Manage the Intercompany Inbox and Outbox</span></span>
<span data-ttu-id="043a2-104">All of the intercompany transactions that you receive electronically from your intercompany partners are listed in the intercompany Inbox.</span><span class="sxs-lookup"><span data-stu-id="043a2-104">All of the intercompany transactions that you receive electronically from your intercompany partners are listed in the intercompany Inbox.</span></span>  

## <a name="organizing-the-inbox"></a><span data-ttu-id="043a2-105">Organising the Inbox</span><span class="sxs-lookup"><span data-stu-id="043a2-105">Organizing the Inbox</span></span>  
 <span data-ttu-id="043a2-106">You can use the filter fields at the top of the inbox window to determine which transactions are shown in the window.</span><span class="sxs-lookup"><span data-stu-id="043a2-106">You can use the filter fields at the top of the inbox window to determine which transactions are shown in the window.</span></span> <span data-ttu-id="043a2-107">For example, if you only want to look at transactions a particular partner created, you can enter filters in the **Transaction Source** and **Intercompany Partner Code** filters.</span><span class="sxs-lookup"><span data-stu-id="043a2-107">For example, if you only want to look at transactions a particular partner created, you can enter filters in the **Transaction Source** and **Intercompany Partner Code** filters.</span></span>  

### <a name="transaction-source"></a><span data-ttu-id="043a2-108">Transaction Source</span><span class="sxs-lookup"><span data-stu-id="043a2-108">Transaction Source</span></span>  
<span data-ttu-id="043a2-109">What you can do with a transaction depends whether it was:</span><span class="sxs-lookup"><span data-stu-id="043a2-109">What you can do with a transaction depends whether it was:</span></span>  

- <span data-ttu-id="043a2-110">Created by your intercompany partner</span><span class="sxs-lookup"><span data-stu-id="043a2-110">Created by your intercompany partner</span></span>  
- <span data-ttu-id="043a2-111">Rejected by your intercompany partner and returned to you</span><span class="sxs-lookup"><span data-stu-id="043a2-111">Rejected by your intercompany partner and returned to you</span></span>  

<span data-ttu-id="043a2-112">You can use the **Show Transaction Source** field to filter the **Intercompany Inbox Transactions** window so that it displays only one of these types of transactions.</span><span class="sxs-lookup"><span data-stu-id="043a2-112">You can use the **Show Transaction Source** field to filter the **Intercompany Inbox Transactions** window so that it displays only one of these types of transactions.</span></span> <span data-ttu-id="043a2-113">(You can also filter by intercompany partner, or by the contents of the **Line Action** field.)</span><span class="sxs-lookup"><span data-stu-id="043a2-113">(You can also filter by intercompany partner, or by the contents of the **Line Action** field.)</span></span>  

#### <a name="created-by-intercompany-partner"></a><span data-ttu-id="043a2-114">Created by Intercompany Partner</span><span class="sxs-lookup"><span data-stu-id="043a2-114">Created by Intercompany Partner</span></span>  
 <span data-ttu-id="043a2-115">When you receive a new transaction that was created by your partner, you can choose to either:</span><span class="sxs-lookup"><span data-stu-id="043a2-115">When you receive a new transaction that was created by your partner, you can choose to either:</span></span>

- <span data-ttu-id="043a2-116">Accept the transaction</span><span class="sxs-lookup"><span data-stu-id="043a2-116">Accept the transaction</span></span>  
- <span data-ttu-id="043a2-117">Reject the transaction (Return to partner)</span><span class="sxs-lookup"><span data-stu-id="043a2-117">Reject the transaction (Return to partner)</span></span>  
- <span data-ttu-id="043a2-118">Cancel the transaction (Delete the transaction but do not return it to your partner)</span><span class="sxs-lookup"><span data-stu-id="043a2-118">Cancel the transaction (Delete the transaction but do not return it to your partner)</span></span>  

#### <a name="returned-from-intercompany-partner"></a><span data-ttu-id="043a2-119">Returned from Intercompany Partner</span><span class="sxs-lookup"><span data-stu-id="043a2-119">Returned from Intercompany Partner</span></span>  
 <span data-ttu-id="043a2-120">If the transaction was rejected by your intercompany partner, your only choice is to cancel the transaction in the inbox.</span><span class="sxs-lookup"><span data-stu-id="043a2-120">If the transaction was rejected by your intercompany partner, your only choice is to cancel the transaction in the inbox.</span></span> <span data-ttu-id="043a2-121">Then you must create correction lines or reverse the journal or document in your company.</span><span class="sxs-lookup"><span data-stu-id="043a2-121">Then you must create correction lines or reverse the journal or document in your company.</span></span>  

## <a name="re-creating-inbox-entries"></a><span data-ttu-id="043a2-122">Re-creating Inbox Entries</span><span class="sxs-lookup"><span data-stu-id="043a2-122">Re-creating Inbox Entries</span></span>  
 <span data-ttu-id="043a2-123">If you accepted a transaction in your inbox but then deleted the document or journal instead of posting it, you can re-create the inbox entry and accept it again.</span><span class="sxs-lookup"><span data-stu-id="043a2-123">If you accepted a transaction in your inbox but then deleted the document or journal instead of posting it, you can re-create the inbox entry and accept it again.</span></span>  

## <a name="getting-an-overview-of-intercompany-transactions-for-a-period"></a><span data-ttu-id="043a2-124">Getting an Overview of Intercompany Transactions for a Period</span><span class="sxs-lookup"><span data-stu-id="043a2-124">Getting an Overview of Intercompany Transactions for a Period</span></span>  
 <span data-ttu-id="043a2-125">You can get an overview of all of the intercompany transactions that you have sent and received in a period.</span><span class="sxs-lookup"><span data-stu-id="043a2-125">You can get an overview of all of the intercompany transactions that you have sent and received in a period.</span></span> <span data-ttu-id="043a2-126">The **Intercompany Transactions** report lists all intercompany G/L entries, customer ledger entries, and vendor ledger entries.</span><span class="sxs-lookup"><span data-stu-id="043a2-126">The **Intercompany Transactions** report lists all intercompany G/L entries, customer ledger entries, and vendor ledger entries.</span></span>

 > [!NOTE]  
 > <span data-ttu-id="043a2-127">If the intercompany partners are in the same database, then transactions are transferred without the need for file or email.</span><span class="sxs-lookup"><span data-stu-id="043a2-127">If the intercompany partners are in the same database, then transactions are transferred without the need for file or email.</span></span> <span data-ttu-id="043a2-128">See the **Transfer Type** field in the **Intercompany Partner** window.</span><span class="sxs-lookup"><span data-stu-id="043a2-128">See the **Transfer Type** field in the **Intercompany Partner** window.</span></span> <br /><br />
<span data-ttu-id="043a2-129">In that case, you can set the system up to bypass the inbox and outbox by selecting the **Auto. Accept Transactions** check box in the **Intercompany Partner** window and the **Auto. Send Transactions** check box in the **Intercompany Setup** window respectively.</span><span class="sxs-lookup"><span data-stu-id="043a2-129">In that case, you can set the system up to bypass the inbox and outbox by selecting the **Auto. Accept Transactions** check box in the **Intercompany Partner** window and the **Auto. Send Transactions** check box in the **Intercompany Setup** window respectively.</span></span>

## <a name="to-import-intercompany-transactions-from-a-file"></a><span data-ttu-id="043a2-130">To import intercompany transactions from a file</span><span class="sxs-lookup"><span data-stu-id="043a2-130">To import intercompany transactions from a file</span></span>  
<span data-ttu-id="043a2-131">If you have an intercompany partner that is not in the same database as your company, you can receive intercompany transactions from that partner in an .xml file.</span><span class="sxs-lookup"><span data-stu-id="043a2-131">If you have an intercompany partner that is not in the same database as your company, you can receive intercompany transactions from that partner in an .xml file.</span></span> <span data-ttu-id="043a2-132">Then you must import the transactions into your inbox.</span><span class="sxs-lookup"><span data-stu-id="043a2-132">Then you must import the transactions into your inbox.</span></span>  

1.  <span data-ttu-id="043a2-133">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Company Information** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="043a2-133">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Company Information** , and then choose the related link.</span></span>
2. <span data-ttu-id="043a2-134">Save the file to the location that you specified in the **Intercompany Inbox Details** field in the **Company Information** window.</span><span class="sxs-lookup"><span data-stu-id="043a2-134">Save the file to the location that you specified in the **Intercompany Inbox Details** field in the **Company Information** window.</span></span>  
3. <span data-ttu-id="043a2-135">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Intercompany Inbox Transactions**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="043a2-135">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Intercompany Inbox Transactions**, and then choose the related link.</span></span>
4. <span data-ttu-id="043a2-136">In the **Intercompany Inbox Transactions** window, choose the **Import Transaction File** action.</span><span class="sxs-lookup"><span data-stu-id="043a2-136">In the **Intercompany Inbox Transactions** window, choose the **Import Transaction File** action.</span></span>  
5. <span data-ttu-id="043a2-137">In the window that appears, select the .xml file that contains the transactions, and then choose the **Open** button.</span><span class="sxs-lookup"><span data-stu-id="043a2-137">In the window that appears, select the .xml file that contains the transactions, and then choose the **Open** button.</span></span>  

<span data-ttu-id="043a2-138">The transactions are imported into the inbox and you can now process them.</span><span class="sxs-lookup"><span data-stu-id="043a2-138">The transactions are imported into the inbox and you can now process them.</span></span>

## <a name="to-process-incoming-intercompany-transactions"></a><span data-ttu-id="043a2-139">To process incoming intercompany transactions</span><span class="sxs-lookup"><span data-stu-id="043a2-139">To process incoming intercompany transactions</span></span>  
<span data-ttu-id="043a2-140">When your intercompany partners send you intercompany transactions, the transactions end up in your intercompany inbox.</span><span class="sxs-lookup"><span data-stu-id="043a2-140">When your intercompany partners send you intercompany transactions, the transactions end up in your intercompany inbox.</span></span> <span data-ttu-id="043a2-141">You must evaluate each transaction in your inbox and act upon it.</span><span class="sxs-lookup"><span data-stu-id="043a2-141">You must evaluate each transaction in your inbox and act upon it.</span></span>  

1. <span data-ttu-id="043a2-142">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Intercompany Inbox Transactions**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="043a2-142">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Intercompany Inbox Transactions**, and then choose the related link.</span></span>  
2. <span data-ttu-id="043a2-143">In the **Intercompany Inbox Transactions** window, select a line, and then choose an action, such as **Accept**, to process the line.</span><span class="sxs-lookup"><span data-stu-id="043a2-143">In the **Intercompany Inbox Transactions** window, select a line, and then choose an action, such as **Accept**, to process the line.</span></span>
3. <span data-ttu-id="043a2-144">In the **Complete IC Inbox Action** window, fill in the fields as necessary.</span><span class="sxs-lookup"><span data-stu-id="043a2-144">In the **Complete IC Inbox Action** window, fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4. <span data-ttu-id="043a2-145">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="043a2-145">Choose the **OK** button.</span></span>  

<span data-ttu-id="043a2-146">For lines that you processed with the **Accept** action, document or journal lines will be created in your company.</span><span class="sxs-lookup"><span data-stu-id="043a2-146">For lines that you processed with the **Accept** action, document or journal lines will be created in your company.</span></span> <span data-ttu-id="043a2-147">Open each document or journal, make any necessary changes, and then post them.</span><span class="sxs-lookup"><span data-stu-id="043a2-147">Open each document or journal, make any necessary changes, and then post them.</span></span>  

<span data-ttu-id="043a2-148">Lines that you processed with the **Return to Partner** action will be moved to the outbox from where you can then send them to your partner.</span><span class="sxs-lookup"><span data-stu-id="043a2-148">Lines that you processed with the **Return to Partner** action will be moved to the outbox from where you can then send them to your partner.</span></span>

<span data-ttu-id="043a2-149">For lines that you processed with the **Returned by Partner** action, you must now post a correction to the original transaction that you posted in your company.</span><span class="sxs-lookup"><span data-stu-id="043a2-149">For lines that you processed with the **Returned by Partner** action, you must now post a correction to the original transaction that you posted in your company.</span></span>

## <a name="to-process-outgoing-intercompany-transactions"></a><span data-ttu-id="043a2-150">To process outgoing intercompany transactions</span><span class="sxs-lookup"><span data-stu-id="043a2-150">To process outgoing intercompany transactions</span></span>  
<span data-ttu-id="043a2-151">When you post an intercompany journal or document, or send an intercompany order confirmation, the transactions are sent to your intercompany outbox.</span><span class="sxs-lookup"><span data-stu-id="043a2-151">When you post an intercompany journal or document, or send an intercompany order confirmation, the transactions are sent to your intercompany outbox.</span></span> <span data-ttu-id="043a2-152">In order for them to be sent on to your intercompany partners, you must open the outbox and process them.</span><span class="sxs-lookup"><span data-stu-id="043a2-152">In order for them to be sent on to your intercompany partners, you must open the outbox and process them.</span></span>  

1.  <span data-ttu-id="043a2-153">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Intercompany Outbox Transactions**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="043a2-153">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Intercompany Outbox Transactions**, and then choose the related link.</span></span>  
2. <span data-ttu-id="043a2-154">In the **Intercompany Outbox Transactions** window, select a line, and then choose an action, such as **Return to Inbox**, to process the line.</span><span class="sxs-lookup"><span data-stu-id="043a2-154">In the **Intercompany Outbox Transactions** window, select a line, and then choose an action, such as **Return to Inbox**, to process the line.</span></span>

<span data-ttu-id="043a2-155">Lines that you processed with the **Send to Intercompany Partner** action will be sent to the relevant partner's inbox.</span><span class="sxs-lookup"><span data-stu-id="043a2-155">Lines that you processed with the **Send to Intercompany Partner** action will be sent to the relevant partner's inbox.</span></span>

<span data-ttu-id="043a2-156">Lines that you processed with the **Return to Inbox** action will be moved to the inbox where you can then accept them to create documents or journal lines in your company.</span><span class="sxs-lookup"><span data-stu-id="043a2-156">Lines that you processed with the **Return to Inbox** action will be moved to the inbox where you can then accept them to create documents or journal lines in your company.</span></span>  

<span data-ttu-id="043a2-157">For lines that you processed with the **Cancel** action, you must now post a correction to the original transaction that you posted in your company.</span><span class="sxs-lookup"><span data-stu-id="043a2-157">For lines that you processed with the **Cancel** action, you must now post a correction to the original transaction that you posted in your company.</span></span>  

## <a name="to-recreate-intercompany-inbox-transactions"></a><span data-ttu-id="043a2-158">To recreate intercompany inbox transactions</span><span class="sxs-lookup"><span data-stu-id="043a2-158">To recreate intercompany inbox transactions</span></span>  
<span data-ttu-id="043a2-159">Occasionally, you may want to re-create a transaction in the inbox or outbox.</span><span class="sxs-lookup"><span data-stu-id="043a2-159">Occasionally, you may want to re-create a transaction in the inbox or outbox.</span></span> <span data-ttu-id="043a2-160">For example, if you accepted a transaction in your inbox but then deleted the document or journal instead of posting it, you can re-create the inbox entry and accept it again.</span><span class="sxs-lookup"><span data-stu-id="043a2-160">For example, if you accepted a transaction in your inbox but then deleted the document or journal instead of posting it, you can re-create the inbox entry and accept it again.</span></span>  

<span data-ttu-id="043a2-161">The following procedure describes to re-create inbox transactions, but the same steps also apply to the outbox.</span><span class="sxs-lookup"><span data-stu-id="043a2-161">The following procedure describes to re-create inbox transactions, but the same steps also apply to the outbox.</span></span>

  1.  <span data-ttu-id="043a2-162">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Handled IC Inbox Transactions**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="043a2-162">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Handled IC Inbox Transactions**, and then choose the related link.</span></span>  

  2.  <span data-ttu-id="043a2-163">In the **Handled IC Inbox Transactions** window, select the line with the transaction that you want to re-create in the inbox, and then choose the **Re-create Inbox Transaction** action.</span><span class="sxs-lookup"><span data-stu-id="043a2-163">In the **Handled IC Inbox Transactions** window, select the line with the transaction that you want to re-create in the inbox, and then choose the **Re-create Inbox Transaction** action.</span></span>  

## <a name="see-also"></a><span data-ttu-id="043a2-164">See Also</span><span class="sxs-lookup"><span data-stu-id="043a2-164">See Also</span></span>
[<span data-ttu-id="043a2-165">Managing Intercompany Transactions</span><span class="sxs-lookup"><span data-stu-id="043a2-165">Managing Intercompany Transactions</span></span>](intercompany-manage.md)  
[<span data-ttu-id="043a2-166">Finance</span><span class="sxs-lookup"><span data-stu-id="043a2-166">Finance</span></span>](finance.md)  
[<span data-ttu-id="043a2-167">Setting Up Finance</span><span class="sxs-lookup"><span data-stu-id="043a2-167">Setting Up Finance</span></span>](finance-setup-finance.md)  
[<span data-ttu-id="043a2-168">Working with General Journals</span><span class="sxs-lookup"><span data-stu-id="043a2-168">Working with General Journals</span></span>](ui-work-general-journals.md)  
<span data-ttu-id="043a2-169">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="043a2-169">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
