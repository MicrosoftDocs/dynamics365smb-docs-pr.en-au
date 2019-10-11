---
title: Automatic Transfer and Combined Entries | Microsoft Docs
description: In cost accounting, you can transfer general ledger entries to a cost type by using a combined posting. You can specify if a cost type receives combined entries in the **Combine Entries** field in the cost type definition. The following table describes the different options.
services: project-madeira
documentationcenter: ''
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: ''
ms.date: 10/01/2019
ms.author: sgroespe
redirect_url: finance-transfer-and-post-cost-entries
ms.openlocfilehash: 0c07e470c1df8b9d9b5e7f7c833ff83b3c61be69
ms.sourcegitcommit: 02e704bc3e01d62072144919774f1244c42827e4
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 10/01/2019
ms.locfileid: "2306444"
---
# <a name="automatic-transfer-and-combined-entries"></a><span data-ttu-id="baceb-105">Automatic Transfer and Combined Entries</span><span class="sxs-lookup"><span data-stu-id="baceb-105">Automatic Transfer and Combined Entries</span></span>
<span data-ttu-id="baceb-106">In cost accounting, you can transfer general ledger entries to a cost type by using a combined posting.</span><span class="sxs-lookup"><span data-stu-id="baceb-106">In cost accounting, you can transfer general ledger entries to a cost type by using a combined posting.</span></span> <span data-ttu-id="baceb-107">You can specify if a cost type receives combined entries in the **Combine Entries** field in the cost type definition.</span><span class="sxs-lookup"><span data-stu-id="baceb-107">You can specify if a cost type receives combined entries in the **Combine Entries** field in the cost type definition.</span></span> <span data-ttu-id="baceb-108">The following table describes the different options.</span><span class="sxs-lookup"><span data-stu-id="baceb-108">The following table describes the different options.</span></span>  

|<span data-ttu-id="baceb-109">Combine entries</span><span class="sxs-lookup"><span data-stu-id="baceb-109">Combine entries</span></span>|<span data-ttu-id="baceb-110">Description</span><span class="sxs-lookup"><span data-stu-id="baceb-110">Description</span></span>|  
|---------------------|-----------------|  
|<span data-ttu-id="baceb-111">None</span><span class="sxs-lookup"><span data-stu-id="baceb-111">None</span></span>|<span data-ttu-id="baceb-112">Each general ledger entry is transferred individually to the corresponding cost type.</span><span class="sxs-lookup"><span data-stu-id="baceb-112">Each general ledger entry is transferred individually to the corresponding cost type.</span></span>|  
|<span data-ttu-id="baceb-113">Day</span><span class="sxs-lookup"><span data-stu-id="baceb-113">Day</span></span>|<span data-ttu-id="baceb-114">General ledger entries with the same posting date are transferred as one entry to the corresponding cost type.</span><span class="sxs-lookup"><span data-stu-id="baceb-114">General ledger entries with the same posting date are transferred as one entry to the corresponding cost type.</span></span>|  
|<span data-ttu-id="baceb-115">Month</span><span class="sxs-lookup"><span data-stu-id="baceb-115">Month</span></span>|<span data-ttu-id="baceb-116">All general ledger entries in the same calendar month are transferred as one entry to the corresponding cost type.</span><span class="sxs-lookup"><span data-stu-id="baceb-116">All general ledger entries in the same calendar month are transferred as one entry to the corresponding cost type.</span></span>|  

> [!IMPORTANT]  
>  <span data-ttu-id="baceb-117">If you have selected the **Auto Transfer from G/L** check box on the **Cost Accounting Setup** page, [!INCLUDE[d365fin](includes/d365fin_md.md)] updates the cost accounting after every posting in the general ledger.</span><span class="sxs-lookup"><span data-stu-id="baceb-117">If you have selected the **Auto Transfer from G/L** check box on the **Cost Accounting Setup** page, [!INCLUDE[d365fin](includes/d365fin_md.md)] updates the cost accounting after every posting in the general ledger.</span></span> <span data-ttu-id="baceb-118">Combined entries are not possible.</span><span class="sxs-lookup"><span data-stu-id="baceb-118">Combined entries are not possible.</span></span>  

## <a name="see-also"></a><span data-ttu-id="baceb-119">See Also</span><span class="sxs-lookup"><span data-stu-id="baceb-119">See Also</span></span>  
 <span data-ttu-id="baceb-120">[Transferring and Posting Cost Entries](finance-transfer-and-post-cost-entries.md) </span><span class="sxs-lookup"><span data-stu-id="baceb-120">[Transferring and Posting Cost Entries](finance-transfer-and-post-cost-entries.md) </span></span>  
 <span data-ttu-id="baceb-121">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="baceb-121">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
