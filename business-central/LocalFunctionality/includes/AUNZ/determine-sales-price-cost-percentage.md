---
author: edupont04
ms.service: dynamics365-business-central
ms.topic: include
ms.date: 04/01/2021
ms.author: edupont
ms.openlocfilehash: 6b07817a0642651ace96c1b6f3e85063a5d93c7a
ms.sourcegitcommit: 766e2840fd16efb901d211d7fa64d96766ac99d9
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 03/31/2021
ms.locfileid: "5771564"
---
<span data-ttu-id="054ad-101">Use the cost plus percentage function to set a sales price based on the cost of an item.</span><span class="sxs-lookup"><span data-stu-id="054ad-101">Use the cost plus percentage function to set a sales price based on the cost of an item.</span></span> <span data-ttu-id="054ad-102">The cost of the item can be calculated along with cost plus calculation.</span><span class="sxs-lookup"><span data-stu-id="054ad-102">The cost of the item can be calculated along with cost plus calculation.</span></span> <span data-ttu-id="054ad-103">The discount will be based on this calculation.</span><span class="sxs-lookup"><span data-stu-id="054ad-103">The discount will be based on this calculation.</span></span> <span data-ttu-id="054ad-104">This functionality eliminates the need for the use of spreadsheets in determining percentage discounts as they correspond to cost plus percentage.</span><span class="sxs-lookup"><span data-stu-id="054ad-104">This functionality eliminates the need for the use of spreadsheets in determining percentage discounts as they correspond to cost plus percentage.</span></span>  

## <a name="to-determine-sales-tax-by-cost-plus-percentage"></a><span data-ttu-id="054ad-105">To determine US sales tax by cost plus percentage</span><span class="sxs-lookup"><span data-stu-id="054ad-105">To determine sales tax by cost plus percentage</span></span>  

1.  <span data-ttu-id="054ad-106">Choose the **Receivables** action.</span><span class="sxs-lookup"><span data-stu-id="054ad-106">Choose the **Receivables** action.</span></span>  
3.  <span data-ttu-id="054ad-107">Choose the **Customers** action.</span><span class="sxs-lookup"><span data-stu-id="054ad-107">Choose the **Customers** action.</span></span>  
4.  <span data-ttu-id="054ad-108">Open the card for a relevant customer.</span><span class="sxs-lookup"><span data-stu-id="054ad-108">Open the card for a relevant customer.</span></span>  

     <span data-ttu-id="054ad-109">–or–</span><span class="sxs-lookup"><span data-stu-id="054ad-109">–or–</span></span>  

    <span data-ttu-id="054ad-110">Choose the **New** action.</span><span class="sxs-lookup"><span data-stu-id="054ad-110">Choose the **New** action.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="054ad-111">For a new customer, in the **No.**</span><span class="sxs-lookup"><span data-stu-id="054ad-111">For a new customer, in the **No.**</span></span> <span data-ttu-id="054ad-112">field, enter the customer number.</span><span class="sxs-lookup"><span data-stu-id="054ad-112">field, enter the customer number.</span></span>  

5.  <span data-ttu-id="054ad-113">To open the **Sales Prices** page, choose the **Prices** action.</span><span class="sxs-lookup"><span data-stu-id="054ad-113">To open the **Sales Prices** page, choose the **Prices** action.</span></span>  
6.  <span data-ttu-id="054ad-114">In the **General** section, fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="054ad-114">In the **General** section, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="054ad-115">Field</span><span class="sxs-lookup"><span data-stu-id="054ad-115">Field</span></span>|<span data-ttu-id="054ad-116">Description</span><span class="sxs-lookup"><span data-stu-id="054ad-116">Description</span></span>|  
    |-----------|-----------------|  
    |<span data-ttu-id="054ad-117">**Sales Type Filter**</span><span class="sxs-lookup"><span data-stu-id="054ad-117">**Sales Type Filter**</span></span>|<span data-ttu-id="054ad-118">Select one of the following options:</span><span class="sxs-lookup"><span data-stu-id="054ad-118">Select one of the following options:</span></span><br /><br /> <span data-ttu-id="054ad-119">-   **Customer**</span><span class="sxs-lookup"><span data-stu-id="054ad-119">-   **Customer**</span></span><br /><span data-ttu-id="054ad-120">-   **Customer Price Group**</span><span class="sxs-lookup"><span data-stu-id="054ad-120">-   **Customer Price Group**</span></span><br /><span data-ttu-id="054ad-121">-   **All Customers**</span><span class="sxs-lookup"><span data-stu-id="054ad-121">-   **All Customers**</span></span><br /><span data-ttu-id="054ad-122">-   **Campaign**</span><span class="sxs-lookup"><span data-stu-id="054ad-122">-   **Campaign**</span></span><br /><span data-ttu-id="054ad-123">-   **None**</span><span class="sxs-lookup"><span data-stu-id="054ad-123">-   **None**</span></span>|  
    |<span data-ttu-id="054ad-124">**Sales Code Filter**</span><span class="sxs-lookup"><span data-stu-id="054ad-124">**Sales Code Filter**</span></span>|<span data-ttu-id="054ad-125">The sales code.</span><span class="sxs-lookup"><span data-stu-id="054ad-125">The sales code.</span></span>|  
    |<span data-ttu-id="054ad-126">**Item No. Filter**</span><span class="sxs-lookup"><span data-stu-id="054ad-126">**Item No. Filter**</span></span>|<span data-ttu-id="054ad-127">The item number.</span><span class="sxs-lookup"><span data-stu-id="054ad-127">The item number.</span></span>|  
    |<span data-ttu-id="054ad-128">**Starting Date Filter**</span><span class="sxs-lookup"><span data-stu-id="054ad-128">**Starting Date Filter**</span></span>|<span data-ttu-id="054ad-129">The starting date.</span><span class="sxs-lookup"><span data-stu-id="054ad-129">The starting date.</span></span>|  
    |<span data-ttu-id="054ad-130">**Currency Code Filter**</span><span class="sxs-lookup"><span data-stu-id="054ad-130">**Currency Code Filter**</span></span>|<span data-ttu-id="054ad-131">The currency code.</span><span class="sxs-lookup"><span data-stu-id="054ad-131">The currency code.</span></span>|  

7.  <span data-ttu-id="054ad-132">Enter information into the relevant fields.</span><span class="sxs-lookup"><span data-stu-id="054ad-132">Enter information into the relevant fields.</span></span>  
8.  <span data-ttu-id="054ad-133">To send the details to a recipient, choose the **Send To** action, and then select one of the following formats:</span><span class="sxs-lookup"><span data-stu-id="054ad-133">To send the details to a recipient, choose the **Send To** action, and then select one of the following formats:</span></span>  

    - <span data-ttu-id="054ad-134">**Recipient as Attachment**</span><span class="sxs-lookup"><span data-stu-id="054ad-134">**Recipient as Attachment**</span></span>  
    - <span data-ttu-id="054ad-135">**Microsoft Word**</span><span class="sxs-lookup"><span data-stu-id="054ad-135">**Microsoft Word**</span></span>  
    - <span data-ttu-id="054ad-136">**Microsoft Excel**</span><span class="sxs-lookup"><span data-stu-id="054ad-136">**Microsoft Excel**</span></span>  

9. <span data-ttu-id="054ad-137">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="054ad-137">Choose the **OK** button.</span></span>  
