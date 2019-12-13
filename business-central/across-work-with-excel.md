---
title: Viewing and Editing in Excel From Business Central | Microsoft Docs
description: Learn about how you can open the pages in Microsoft Excel from Business Central for better data analysis.
author: jswymer
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: accountant, accounting, financial report
ms.date: 10/24/2019
ms.author: jswymer
ms.openlocfilehash: 99fe339426b755b70983d8ec9345858357043347
ms.sourcegitcommit: 893e13fa75b2d04dedd4a29abda216e3e54b24ae
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 11/15/2019
ms.locfileid: "2808753"
---
# <a name="viewing-and-editing-in-excel-from-business-central"></a><span data-ttu-id="6bc9c-103">Viewing and Editing in Excel From Business Central</span><span class="sxs-lookup"><span data-stu-id="6bc9c-103">Viewing and Editing in Excel From Business Central</span></span>

<span data-ttu-id="6bc9c-104">With pages that display a list of records in rows and columns, like a list of customers, sale orders, or invoices, you can also view the records using Microsoft Excel.</span><span class="sxs-lookup"><span data-stu-id="6bc9c-104">With pages that display a list of records in rows and columns, like a list of customers, sale orders, or invoices, you can also view the records using Microsoft Excel.</span></span> <span data-ttu-id="6bc9c-105">To do this, you have two options.</span><span class="sxs-lookup"><span data-stu-id="6bc9c-105">To do this, you have two options.</span></span> <span data-ttu-id="6bc9c-106">You can either select the **Open in Excel** action or the **Edit in Excel** action on the page.</span><span class="sxs-lookup"><span data-stu-id="6bc9c-106">You can either select the **Open in Excel** action or the **Edit in Excel** action on the page.</span></span> <span data-ttu-id="6bc9c-107">The differences between the two actions is as follows:</span><span class="sxs-lookup"><span data-stu-id="6bc9c-107">The differences between the two actions is as follows:</span></span>  

## <a name="open-in-excel"></a><span data-ttu-id="6bc9c-108">Open in Excel</span><span class="sxs-lookup"><span data-stu-id="6bc9c-108">Open in Excel</span></span>

- <span data-ttu-id="6bc9c-109">With this action, Excel respects any filters on the page that limit the records shown.</span><span class="sxs-lookup"><span data-stu-id="6bc9c-109">With this action, Excel respects any filters on the page that limit the records shown.</span></span> <span data-ttu-id="6bc9c-110">This means that the Excel workbook will contain the same rows and columns that appear on the page in [!INCLUDE[prodshort](includes/prodshort.md)].</span><span class="sxs-lookup"><span data-stu-id="6bc9c-110">This means that the Excel workbook will contain the same rows and columns that appear on the page in [!INCLUDE[prodshort](includes/prodshort.md)].</span></span>

- <span data-ttu-id="6bc9c-111">You can make changes to the records in Excel, but you cannot publish the changes back to [!INCLUDE[prodshort](includes/prodshort.md)].</span><span class="sxs-lookup"><span data-stu-id="6bc9c-111">You can make changes to the records in Excel, but you cannot publish the changes back to [!INCLUDE[prodshort](includes/prodshort.md)].</span></span> <span data-ttu-id="6bc9c-112">You can only save the changes to Excel file on your computer.</span><span class="sxs-lookup"><span data-stu-id="6bc9c-112">You can only save the changes to Excel file on your computer.</span></span> 

- <span data-ttu-id="6bc9c-113">This action works on both on Windows and macOS.</span><span class="sxs-lookup"><span data-stu-id="6bc9c-113">This action works on both on Windows and macOS.</span></span> 

> [!NOTE]
> <span data-ttu-id="6bc9c-114">For [!INCLUDE[prodshort](includes/prodshort.md)] on-premises, the **Open in Excel** action is available by default.</span><span class="sxs-lookup"><span data-stu-id="6bc9c-114">For [!INCLUDE[prodshort](includes/prodshort.md)] on-premises, the **Open in Excel** action is available by default.</span></span> <span data-ttu-id="6bc9c-115">However, if you set up [!INCLUDE [prodshort](includes/prodshort.md)] on-premises for editing data in Excel, then the **Open in Excel** action is replaced by the **Edit in Excel** action.</span><span class="sxs-lookup"><span data-stu-id="6bc9c-115">However, if you set up [!INCLUDE [prodshort](includes/prodshort.md)] on-premises for editing data in Excel, then the **Open in Excel** action is replaced by the **Edit in Excel** action.</span></span>

## <a name="edit-in-excel"></a><span data-ttu-id="6bc9c-116">Edit in Excel</span><span class="sxs-lookup"><span data-stu-id="6bc9c-116">Edit in Excel</span></span>

- <span data-ttu-id="6bc9c-117">With this action, Excel respects most filters on the page that limit the records shown.</span><span class="sxs-lookup"><span data-stu-id="6bc9c-117">With this action, Excel respects most filters on the page that limit the records shown.</span></span> <span data-ttu-id="6bc9c-118">This means that the Excel workbook will contain almost the same records and columns.</span><span class="sxs-lookup"><span data-stu-id="6bc9c-118">This means that the Excel workbook will contain almost the same records and columns.</span></span>

- <span data-ttu-id="6bc9c-119">The advantage of the **Edit in Excel** action is that it lets you make changes to records in Excel and then publish the changes back to [!INCLUDE[prodshort](includes/prodshort.md)].</span><span class="sxs-lookup"><span data-stu-id="6bc9c-119">The advantage of the **Edit in Excel** action is that it lets you make changes to records in Excel and then publish the changes back to [!INCLUDE[prodshort](includes/prodshort.md)].</span></span>

- <span data-ttu-id="6bc9c-120">It only works on Windows; not macOS.</span><span class="sxs-lookup"><span data-stu-id="6bc9c-120">It only works on Windows; not macOS.</span></span>

<span data-ttu-id="6bc9c-121">This was enhanced in 2019 release wave 2.</span><span class="sxs-lookup"><span data-stu-id="6bc9c-121">This was enhanced in 2019 release wave 2.</span></span> <span data-ttu-id="6bc9c-122">For more information, see [Enhancements to Excel integration](/dynamics365-release-plan/2019wave2/dynamics365-business-central/enhancements-excel-integration).</span><span class="sxs-lookup"><span data-stu-id="6bc9c-122">For more information, see [Enhancements to Excel integration](/dynamics365-release-plan/2019wave2/dynamics365-business-central/enhancements-excel-integration).</span></span>

> [!NOTE]
> <span data-ttu-id="6bc9c-123">For [!INCLUDE[prodshort](includes/prodshort.md)] on-premises, the **Edit in Excel** action is only available if the Excel add-in has been configured by your administrator.</span><span class="sxs-lookup"><span data-stu-id="6bc9c-123">For [!INCLUDE[prodshort](includes/prodshort.md)] on-premises, the **Edit in Excel** action is only available if the Excel add-in has been configured by your administrator.</span></span> <span data-ttu-id="6bc9c-124">For administrators, if you want to learn how to install the excel add-in, see [Setting up the Excel Add-In for Editing Business Central Data](/dynamics365/business-central/dev-itpro/administration/configuring-excel-addin).</span><span class="sxs-lookup"><span data-stu-id="6bc9c-124">For administrators, if you want to learn how to install the excel add-in, see [Setting up the Excel Add-In for Editing Business Central Data](/dynamics365/business-central/dev-itpro/administration/configuring-excel-addin).</span></span>

> [!NOTE]
> <span data-ttu-id="6bc9c-125">For [!INCLUDE[prodshort](includes/prodshort.md)] on-premises, this feature is only available for the Web client.</span><span class="sxs-lookup"><span data-stu-id="6bc9c-125">For [!INCLUDE[prodshort](includes/prodshort.md)] on-premises, this feature is only available for the Web client.</span></span>

### <a name="see-the-differences-between-the-options"></a><span data-ttu-id="6bc9c-126">See the differences between the options</span><span class="sxs-lookup"><span data-stu-id="6bc9c-126">See the differences between the options</span></span> 
<br><br>  

> [!Video https://go.microsoft.com/fwlink/?linkid=2086039]

## <a name="see-also"></a><span data-ttu-id="6bc9c-127">See Also</span><span class="sxs-lookup"><span data-stu-id="6bc9c-127">See Also</span></span>
[<span data-ttu-id="6bc9c-128">Working with Business Central</span><span class="sxs-lookup"><span data-stu-id="6bc9c-128">Working with Business Central</span></span>](ui-work-product.md)  
