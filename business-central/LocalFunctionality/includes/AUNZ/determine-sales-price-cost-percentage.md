---
author: edupont04
ms.service: dynamics365-business-central
ms.topic: include
ms.date: 10/01/2020
ms.author: edupont
ms.openlocfilehash: 55caefb76847eadcc3471893a6afb472d68ad91d
ms.sourcegitcommit: 428f180604e5afcf94fa0e92a0615f58c88e13cd
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 10/02/2020
ms.locfileid: "3959601"
---
<span data-ttu-id="2bf2c-101">Use the cost plus percentage function to set a sales price based on the cost of an item.</span><span class="sxs-lookup"><span data-stu-id="2bf2c-101">Use the cost plus percentage function to set a sales price based on the cost of an item.</span></span> <span data-ttu-id="2bf2c-102">The cost of the item can be calculated along with cost plus calculation.</span><span class="sxs-lookup"><span data-stu-id="2bf2c-102">The cost of the item can be calculated along with cost plus calculation.</span></span> <span data-ttu-id="2bf2c-103">The discount will be based on this calculation.</span><span class="sxs-lookup"><span data-stu-id="2bf2c-103">The discount will be based on this calculation.</span></span> <span data-ttu-id="2bf2c-104">This functionality eliminates the need for the use of spreadsheets in determining percentage discounts as they correspond to cost plus percentage.</span><span class="sxs-lookup"><span data-stu-id="2bf2c-104">This functionality eliminates the need for the use of spreadsheets in determining percentage discounts as they correspond to cost plus percentage.</span></span>  

## <a name="to-determine-sales-tax-by-cost-plus-percentage"></a><span data-ttu-id="2bf2c-105">To determine US sales tax by cost plus percentage</span><span class="sxs-lookup"><span data-stu-id="2bf2c-105">To determine sales tax by cost plus percentage</span></span>  

1.  <span data-ttu-id="2bf2c-106">Choose the **Receivables** action.</span><span class="sxs-lookup"><span data-stu-id="2bf2c-106">Choose the **Receivables** action.</span></span>  
3.  <span data-ttu-id="2bf2c-107">Choose the **Customers** action.</span><span class="sxs-lookup"><span data-stu-id="2bf2c-107">Choose the **Customers** action.</span></span>  
4.  <span data-ttu-id="2bf2c-108">Open the card for a relevant customer.</span><span class="sxs-lookup"><span data-stu-id="2bf2c-108">Open the card for a relevant customer.</span></span>  

     <span data-ttu-id="2bf2c-109">–or–</span><span class="sxs-lookup"><span data-stu-id="2bf2c-109">–or–</span></span>  

    <span data-ttu-id="2bf2c-110">Choose the **New** action.</span><span class="sxs-lookup"><span data-stu-id="2bf2c-110">Choose the **New** action.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="2bf2c-111">For a new customer, in the **No.**</span><span class="sxs-lookup"><span data-stu-id="2bf2c-111">For a new customer, in the **No.**</span></span> <span data-ttu-id="2bf2c-112">field, enter the customer number.</span><span class="sxs-lookup"><span data-stu-id="2bf2c-112">field, enter the customer number.</span></span>  

5.  <span data-ttu-id="2bf2c-113">To open the **Sales Prices** page, choose the **Prices** action.</span><span class="sxs-lookup"><span data-stu-id="2bf2c-113">To open the **Sales Prices** page, choose the **Prices** action.</span></span>  
6.  <span data-ttu-id="2bf2c-114">In the **General** section, fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="2bf2c-114">In the **General** section, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="2bf2c-115">Field</span><span class="sxs-lookup"><span data-stu-id="2bf2c-115">Field</span></span>|<span data-ttu-id="2bf2c-116">Description</span><span class="sxs-lookup"><span data-stu-id="2bf2c-116">Description</span></span>|  
    |-----------|-----------------|  
    |<span data-ttu-id="2bf2c-117">**Sales Type Filter**</span><span class="sxs-lookup"><span data-stu-id="2bf2c-117">**Sales Type Filter**</span></span>|<span data-ttu-id="2bf2c-118">Select one of the following options:</span><span class="sxs-lookup"><span data-stu-id="2bf2c-118">Select one of the following options:</span></span><br /><br /> <span data-ttu-id="2bf2c-119">-   **Customer**</span><span class="sxs-lookup"><span data-stu-id="2bf2c-119">-   **Customer**</span></span><br /><span data-ttu-id="2bf2c-120">-   **Customer Price Group**</span><span class="sxs-lookup"><span data-stu-id="2bf2c-120">-   **Customer Price Group**</span></span><br /><span data-ttu-id="2bf2c-121">-   **All Customers**</span><span class="sxs-lookup"><span data-stu-id="2bf2c-121">-   **All Customers**</span></span><br /><span data-ttu-id="2bf2c-122">-   **Campaign**</span><span class="sxs-lookup"><span data-stu-id="2bf2c-122">-   **Campaign**</span></span><br /><span data-ttu-id="2bf2c-123">-   **None**</span><span class="sxs-lookup"><span data-stu-id="2bf2c-123">-   **None**</span></span>|  
    |<span data-ttu-id="2bf2c-124">**Sales Code Filter**</span><span class="sxs-lookup"><span data-stu-id="2bf2c-124">**Sales Code Filter**</span></span>|<span data-ttu-id="2bf2c-125">The sales code.</span><span class="sxs-lookup"><span data-stu-id="2bf2c-125">The sales code.</span></span>|  
    |<span data-ttu-id="2bf2c-126">**Item No. Filter**</span><span class="sxs-lookup"><span data-stu-id="2bf2c-126">**Item No. Filter**</span></span>|<span data-ttu-id="2bf2c-127">The item number.</span><span class="sxs-lookup"><span data-stu-id="2bf2c-127">The item number.</span></span>|  
    |<span data-ttu-id="2bf2c-128">**Starting Date Filter**</span><span class="sxs-lookup"><span data-stu-id="2bf2c-128">**Starting Date Filter**</span></span>|<span data-ttu-id="2bf2c-129">The starting date.</span><span class="sxs-lookup"><span data-stu-id="2bf2c-129">The starting date.</span></span>|  
    |<span data-ttu-id="2bf2c-130">**Currency Code Filter**</span><span class="sxs-lookup"><span data-stu-id="2bf2c-130">**Currency Code Filter**</span></span>|<span data-ttu-id="2bf2c-131">The currency code.</span><span class="sxs-lookup"><span data-stu-id="2bf2c-131">The currency code.</span></span>|  

7.  <span data-ttu-id="2bf2c-132">Enter information into the relevant fields.</span><span class="sxs-lookup"><span data-stu-id="2bf2c-132">Enter information into the relevant fields.</span></span>  
8.  <span data-ttu-id="2bf2c-133">To send the details to a recipient, choose the **Send To** action, and then select one of the following formats:</span><span class="sxs-lookup"><span data-stu-id="2bf2c-133">To send the details to a recipient, choose the **Send To** action, and then select one of the following formats:</span></span>  

    - <span data-ttu-id="2bf2c-134">**Recipient as Attachment**</span><span class="sxs-lookup"><span data-stu-id="2bf2c-134">**Recipient as Attachment**</span></span>  
    - <span data-ttu-id="2bf2c-135">**Microsoft Word**</span><span class="sxs-lookup"><span data-stu-id="2bf2c-135">**Microsoft Word**</span></span>  
    - <span data-ttu-id="2bf2c-136">**Microsoft Excel**</span><span class="sxs-lookup"><span data-stu-id="2bf2c-136">**Microsoft Excel**</span></span>  

9. <span data-ttu-id="2bf2c-137">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="2bf2c-137">Choose the **OK** button.</span></span>  
