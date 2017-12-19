---
title: Send Electronic Documents | Microsoft Docs
description: learn how to send invoices electronically.
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
ms.sourcegitcommit: 8b2e20e694279a8c06188e0e429ef3b4fb43aea2
ms.openlocfilehash: eb9a20547c7eef346fa199eaa136211dcdd09dab
ms.contentlocale: en-au
ms.lasthandoff: 09/27/2017

---
# <a name="how-to-send-electronic-documents"></a><span data-ttu-id="a9681-103">How to: Send Electronic Documents</span><span class="sxs-lookup"><span data-stu-id="a9681-103">How to: Send Electronic Documents</span></span>
<span data-ttu-id="a9681-104">The generic version of [!INCLUDE[d365fin](includes/d365fin_md.md)] supports sending electronic invoices and CR/Adj Notes in the PEPPOL format, which is supported by the largest document exchange service providers.</span><span class="sxs-lookup"><span data-stu-id="a9681-104">The generic version of [!INCLUDE[d365fin](includes/d365fin_md.md)] supports sending electronic invoices and credit memos in the PEPPOL format, which is supported by the largest document exchange service providers.</span></span> <span data-ttu-id="a9681-105">A document exchange service provider dispatches electronic documents between trading partners.</span><span class="sxs-lookup"><span data-stu-id="a9681-105">A document exchange service provider dispatches electronic documents between trading partners.</span></span> <span data-ttu-id="a9681-106">To provide support for other electronic document formats, you use the data exchange framework.</span><span class="sxs-lookup"><span data-stu-id="a9681-106">To provide support for other electronic document formats, you use the data exchange framework.</span></span>  

 <span data-ttu-id="a9681-107">In the generic version of [!INCLUDE[d365fin](includes/d365fin_md.md)], a document exchange service is preconfigured and ready to be set up for your company.</span><span class="sxs-lookup"><span data-stu-id="a9681-107">In the generic version of [!INCLUDE[d365fin](includes/d365fin_md.md)], a document exchange service is preconfigured and ready to be set up for your company.</span></span> <span data-ttu-id="a9681-108">For more information, see [How to: Set Up a Document Exchange Service](across-how-to-set-up-a-document-exchange-service.md).</span><span class="sxs-lookup"><span data-stu-id="a9681-108">For more information, see [How to: Set Up a Document Exchange Service](across-how-to-set-up-a-document-exchange-service.md).</span></span>  

 <span data-ttu-id="a9681-109">To send a sales invoice as an electronic PEPPOL document, you select the **Electronic Document** option in the **Post and Send** dialogue box from where you can also set up the customer’s default document sending profile.</span><span class="sxs-lookup"><span data-stu-id="a9681-109">To send a sales invoice as an electronic PEPPOL document, you select the **Electronic Document** option in the **Post and Send** dialog box from where you can also set up the customer’s default document sending profile.</span></span> <span data-ttu-id="a9681-110">First, you must set up various master data, such as company information, customers, items, and units of measure.</span><span class="sxs-lookup"><span data-stu-id="a9681-110">First, you must set up various master data, such as company information, customers, items, and units of measure.</span></span> <span data-ttu-id="a9681-111">These are used to identify the business partners and items when converting data in fields in [How to: Set Up Electronic Document Sending and Receiving](across-how-to-set-up-electronic-document-sending-and-receiving.md).</span><span class="sxs-lookup"><span data-stu-id="a9681-111">These are used to identify the business partners and items when converting data in fields in [How to: Set Up Electronic Document Sending and Receiving](across-how-to-set-up-electronic-document-sending-and-receiving.md).</span></span>  

### <a name="to-send-an-electronic-sales-invoice"></a><span data-ttu-id="a9681-112">To send an electronic sales invoice</span><span class="sxs-lookup"><span data-stu-id="a9681-112">To send an electronic sales invoice</span></span>  

1.  <span data-ttu-id="a9681-113">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoices**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="a9681-113">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoices**, and then choose the related link.</span></span>  

2.  <span data-ttu-id="a9681-114">Create a new sales invoice.</span><span class="sxs-lookup"><span data-stu-id="a9681-114">Create a new sales invoice.</span></span>  

3.  <span data-ttu-id="a9681-115">When the sales invoice is ready to be invoiced, on the **Actions** tab, in the **Posting** group, choose **Post and Send**.</span><span class="sxs-lookup"><span data-stu-id="a9681-115">When the sales invoice is ready to be invoiced, on the **Actions** tab, in the **Posting** group, choose **Post and Send**.</span></span>  

     <span data-ttu-id="a9681-116">If the customer’s default sending profile is **Electronic Document**, then it will be shown in the **Post and Send Confirmation** dialogue box and you just have to choose the **Yes** button to post and send the invoice electronically in the selected format.</span><span class="sxs-lookup"><span data-stu-id="a9681-116">If the customer’s default sending profile is **Electronic Document**, then it will be shown in the **Post and Send Confirmation** dialog box and you just have to choose the **Yes** button to post and send the invoice electronically in the selected format.</span></span>  

4.  <span data-ttu-id="a9681-117">In the **Post and Send Confirmation** dialogue box, choose the AssistEdit button to the right of the **Send Document to** field.</span><span class="sxs-lookup"><span data-stu-id="a9681-117">In the **Post and Send Confirmation** dialog box, choose the AssistEdit button to the right of the **Send Document to** field.</span></span>  

5.  <span data-ttu-id="a9681-118">In the **Send Document to** dialogue box, in the **Electronic Document** field, choose **Through Document Exchange Service**.</span><span class="sxs-lookup"><span data-stu-id="a9681-118">In the **Send Document to** dialog box, in the **Electronic Document** field, choose **Through Document Exchange Service**.</span></span>  

6.  <span data-ttu-id="a9681-119">In the **Format** field, choose **PEPPOL**.</span><span class="sxs-lookup"><span data-stu-id="a9681-119">In the **Format** field, choose **PEPPOL**.</span></span>  

7.  <span data-ttu-id="a9681-120">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="a9681-120">Choose the **OK** button.</span></span> <span data-ttu-id="a9681-121">The **Post and Send Confirmation** dialogue box appears.</span><span class="sxs-lookup"><span data-stu-id="a9681-121">The **Post and Send Confirmation** dialog box appears.</span></span> <span data-ttu-id="a9681-122">**Electronic Document (PEPPOL)** is added to the **Send Document to** field.</span><span class="sxs-lookup"><span data-stu-id="a9681-122">**Electronic Document (PEPPOL)** is added to the **Send Document to** field.</span></span>  

8.  <span data-ttu-id="a9681-123">Choose the **Yes** button.</span><span class="sxs-lookup"><span data-stu-id="a9681-123">Choose the **Yes** button.</span></span>  

     <span data-ttu-id="a9681-124">The sales invoice is posted and sent to the customer as an electronic document in the PEPPOL format.</span><span class="sxs-lookup"><span data-stu-id="a9681-124">The sales invoice is posted and sent to the customer as an electronic document in the PEPPOL format.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="a9681-125">You can also send a posted sales invoice as an electronic document.</span><span class="sxs-lookup"><span data-stu-id="a9681-125">You can also send a posted sales invoice as an electronic document.</span></span> <span data-ttu-id="a9681-126">The procedure is the same as described in this topic for non-posted sales documents.</span><span class="sxs-lookup"><span data-stu-id="a9681-126">The procedure is the same as described in this topic for non-posted sales documents.</span></span> <span data-ttu-id="a9681-127">In the **Posted Sales Invoice** window, on the **Actions** tab, in the **General** group, choose **Activity Log** to view the status of the electronic document.</span><span class="sxs-lookup"><span data-stu-id="a9681-127">In the **Posted Sales Invoice** window, on the **Actions** tab, in the **General** group, choose **Activity Log** to view the status of the electronic document.</span></span> <span data-ttu-id="a9681-128">For more information, see **Activity Log**.</span><span class="sxs-lookup"><span data-stu-id="a9681-128">For more information, see **Activity Log**.</span></span>  

## <a name="see-also"></a><span data-ttu-id="a9681-129">See Also</span><span class="sxs-lookup"><span data-stu-id="a9681-129">See Also</span></span>  
[<span data-ttu-id="a9681-130">How to: Invoice Sales</span><span class="sxs-lookup"><span data-stu-id="a9681-130">How to: Invoice Sales</span></span>](sales-how-invoice-sales.md)  
[<span data-ttu-id="a9681-131">How to: Set Up Document Sending Profiles</span><span class="sxs-lookup"><span data-stu-id="a9681-131">How to: Set Up Document Sending Profiles</span></span>](sales-how-setup-document-send-profiles.md)  
[<span data-ttu-id="a9681-132">How to: Set Up Electronic Document Sending and Receiving</span><span class="sxs-lookup"><span data-stu-id="a9681-132">How to: Set Up Electronic Document Sending and Receiving</span></span>](across-how-to-set-up-electronic-document-sending-and-receiving.md)  
[<span data-ttu-id="a9681-133">How to: Set Up a Document Exchange Service</span><span class="sxs-lookup"><span data-stu-id="a9681-133">How to: Set Up a Document Exchange Service</span></span>](across-how-to-set-up-a-document-exchange-service.md)  
[<span data-ttu-id="a9681-134">How to: Set Up Data Exchange Definitions</span><span class="sxs-lookup"><span data-stu-id="a9681-134">How to: Set Up Data Exchange Definitions</span></span>](across-how-to-set-up-data-exchange-definitions.md)  
[<span data-ttu-id="a9681-135">Exchanging Data Electronically</span><span class="sxs-lookup"><span data-stu-id="a9681-135">Exchanging Data Electronically</span></span>](across-data-exchange.md)  
[<span data-ttu-id="a9681-136">General Business Functionality</span><span class="sxs-lookup"><span data-stu-id="a9681-136">General Business Functionality</span></span>](ui-across-business-areas.md)  
