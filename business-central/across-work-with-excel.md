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
ms.date: 04/01/2019
ms.author: jswymer
ms.openlocfilehash: 68139f258595bcca2658e394a4251e30dfbe6510
ms.sourcegitcommit: bd78a5d990c9e83174da1409076c22df8b35eafd
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 03/31/2019
ms.locfileid: "925048"
---
# <a name="viewing-and-editing-in-excel-from-business-central"></a><span data-ttu-id="b3c2e-103">Viewing and Editing in Excel From Business Central</span><span class="sxs-lookup"><span data-stu-id="b3c2e-103">Viewing and Editing in Excel From Business Central</span></span> 

<span data-ttu-id="b3c2e-104">With pages that display a list of records in rows and columns, like a list of customers, sale orders, or invoices, you can also view the records using Microsoft Excel.</span><span class="sxs-lookup"><span data-stu-id="b3c2e-104">With pages that display a list of records in rows and columns, like a list of customers, sale orders, or invoices, you can also view the records using Microsoft Excel.</span></span> <span data-ttu-id="b3c2e-105">To do this, you have two options.</span><span class="sxs-lookup"><span data-stu-id="b3c2e-105">To do this, you have two options.</span></span> <span data-ttu-id="b3c2e-106">You can either select the **Open in Excel** action or the **Edit in Excel** action on the page.</span><span class="sxs-lookup"><span data-stu-id="b3c2e-106">You can either select the **Open in Excel** action or the **Edit in Excel** action on the page.</span></span> <span data-ttu-id="b3c2e-107">The differences between the two actions is as follows:</span><span class="sxs-lookup"><span data-stu-id="b3c2e-107">The differences between the two actions is as follows:</span></span>  

## <a name="open-in-excel"></a><span data-ttu-id="b3c2e-108">Open in Excel</span><span class="sxs-lookup"><span data-stu-id="b3c2e-108">Open in Excel</span></span>

-    <span data-ttu-id="b3c2e-109">With this action, Excel respects any filters on the page the limit the records shown.</span><span class="sxs-lookup"><span data-stu-id="b3c2e-109">With this action, Excel respects any filters on the page the limit the records shown.</span></span> <span data-ttu-id="b3c2e-110">This means that the Excel workbook will contain the same rows and columns that appear on the the page in [!INCLUDE[prodshort](includes/prodshort.md)].</span><span class="sxs-lookup"><span data-stu-id="b3c2e-110">This means that the Excel workbook will contain the same rows and columns that appear on the the page in [!INCLUDE[prodshort](includes/prodshort.md)].</span></span>

-    <span data-ttu-id="b3c2e-111">You can make changes to the records in Excel, but you cannot publish the changes back to [!INCLUDE[prodshort](includes/prodshort.md)].</span><span class="sxs-lookup"><span data-stu-id="b3c2e-111">You can make changes to the records in Excel, but you cannot publish the changes back to [!INCLUDE[prodshort](includes/prodshort.md)].</span></span> <span data-ttu-id="b3c2e-112">You can only save the changes to Excel file on your computer.</span><span class="sxs-lookup"><span data-stu-id="b3c2e-112">You can only save the changes to Excel file on your computer.</span></span> 

-    <span data-ttu-id="b3c2e-113">This action works on both on Windows and macOS.</span><span class="sxs-lookup"><span data-stu-id="b3c2e-113">This action works on both on Windows and macOS.</span></span> 

>[!NOTE]
><span data-ttu-id="b3c2e-114">For [!INCLUDE[prodshort](includes/prodshort.md)] on-premises, the **Open in Excel** action is not available if the **Edit in Excel** action is.</span><span class="sxs-lookup"><span data-stu-id="b3c2e-114">For [!INCLUDE[prodshort](includes/prodshort.md)] on-premises, the **Open in Excel** action is not available if the **Edit in Excel** action is.</span></span>

## <a name="edit-in-excel"></a><span data-ttu-id="b3c2e-115">Edit in Excel</span><span class="sxs-lookup"><span data-stu-id="b3c2e-115">Edit in Excel</span></span>

-    <span data-ttu-id="b3c2e-116">With this action, the Excel workbook does not respect filters on the page the limit the records shown.</span><span class="sxs-lookup"><span data-stu-id="b3c2e-116">With this action, the Excel workbook does not respect filters on the page the limit the records shown.</span></span> <span data-ttu-id="b3c2e-117">This means that the Excel workbook will contain all the available records and columns, regardless of what is shown on the page.</span><span class="sxs-lookup"><span data-stu-id="b3c2e-117">This means that the Excel workbook will contain all the available records and columns, regardless of what is shown on the page.</span></span> 

-    <span data-ttu-id="b3c2e-118">The advantage of the **Edit in Excel** action is that it lets you make changes to records in Excel and then publish the changes back to [!INCLUDE[prodshort](includes/prodshort.md)].</span><span class="sxs-lookup"><span data-stu-id="b3c2e-118">The advantage of the **Edit in Excel** action is that it lets you make changes to records in Excel and then publish the changes back to [!INCLUDE[prodshort](includes/prodshort.md)].</span></span>

-    <span data-ttu-id="b3c2e-119">It only works on Windows; not macOS.</span><span class="sxs-lookup"><span data-stu-id="b3c2e-119">It only works on Windows; not macOS.</span></span>

>[!NOTE]
><span data-ttu-id="b3c2e-120">For [!INCLUDE[prodshort](includes/prodshort.md)] on-premises, the **Edit in Excel** action is only available if the Excel add-in has been installed by your administrator.</span><span class="sxs-lookup"><span data-stu-id="b3c2e-120">For [!INCLUDE[prodshort](includes/prodshort.md)] on-premises, the **Edit in Excel** action is only available if the Excel add-in has been installed by your administrator.</span></span> <span data-ttu-id="b3c2e-121">For administrators, if you want to learn how to install the excel add-in, see [Setting up the Excel Add-In](https://docs.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/configuring-excel-addin).</span><span class="sxs-lookup"><span data-stu-id="b3c2e-121">For administrators, if you want to learn how to install the excel add-in, see [Setting up the Excel Add-In](https://docs.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/configuring-excel-addin).</span></span>

### <a name="see-the-differences-between-the-options"></a><span data-ttu-id="b3c2e-122">See the differences between the options</span><span class="sxs-lookup"><span data-stu-id="b3c2e-122">See the differences between the options</span></span> 
> [!Video https://go.microsoft.com/fwlink/?linkid=2086039]

## <a name="see-also"></a><span data-ttu-id="b3c2e-123">See Also</span><span class="sxs-lookup"><span data-stu-id="b3c2e-123">See Also</span></span>
[<span data-ttu-id="b3c2e-124">Working with Business Central</span><span class="sxs-lookup"><span data-stu-id="b3c2e-124">Working with Business Central</span></span>](ui-work-product.md)  
