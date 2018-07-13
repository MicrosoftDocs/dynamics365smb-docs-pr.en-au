---
title: Electronic Funds Transfer (EFT)
description: You can pay vendors using the electronic funds transfer (EFT) system in Australia.
services: project-madeira
documentationcenter: 
author: bholtorf
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 05/29/2018
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: 046a42582dc66368fded90a4bb45add71a95d979
ms.openlocfilehash: 9d4432debae0b3c13e304d17930a8e58b630809d
ms.contentlocale: en-au
ms.lasthandoff: 07/02/2018

---
# <a name="electronic-funds-transfer-eft"></a><span data-ttu-id="ae2be-103">Electronic Funds Transfer (EFT)</span><span class="sxs-lookup"><span data-stu-id="ae2be-103">Electronic Funds Transfer (EFT)</span></span>
<span data-ttu-id="ae2be-104">You can pay vendors using the electronic funds transfer (EFT) system in Australia.</span><span class="sxs-lookup"><span data-stu-id="ae2be-104">You can pay vendors using the electronic funds transfer (EFT) system in Australia.</span></span>  

## <a name="setting-up-electronic-funds-transfer-in-included365finincludesd365finmdmd"></a><span data-ttu-id="ae2be-105">Setting up Electronic Funds Transfer in [!INCLUDE[d365fin](../../includes/d365fin_md.md)]</span><span class="sxs-lookup"><span data-stu-id="ae2be-105">Setting up Electronic Funds Transfer in [!INCLUDE[d365fin](../../includes/d365fin_md.md)]</span></span>  
[!INCLUDE[d365fin](../../includes/d365fin_md.md)]<span data-ttu-id="ae2be-106"> can export EFT files that you can then upload to your bank’s website for additional processing.</span><span class="sxs-lookup"><span data-stu-id="ae2be-106"> can export EFT files that you can then upload to your bank’s website for additional processing.</span></span> <span data-ttu-id="ae2be-107">To submit EFT files, you must set up the following information:</span><span class="sxs-lookup"><span data-stu-id="ae2be-107">To submit EFT files, you must set up the following information:</span></span>  

* <span data-ttu-id="ae2be-108">You must add EFT information to the bank account or bank accounts that you will use to pay vendors electronically.</span><span class="sxs-lookup"><span data-stu-id="ae2be-108">You must add EFT information to the bank account or bank accounts that you will use to pay vendors electronically.</span></span> <span data-ttu-id="ae2be-109">The EFT-specific fields are on the **Transfer** FastTab on the **Bank Account** page.</span><span class="sxs-lookup"><span data-stu-id="ae2be-109">The EFT-specific fields are on the **Transfer** FastTab on the **Bank Account** page.</span></span>  
* <span data-ttu-id="ae2be-110">For those vendors that you want to pay electronically, you must select the **EFT Payment** check box and specify the vendor bank account in the **EFT Vendor Bank Account Code** field on the **Vendor** page.</span><span class="sxs-lookup"><span data-stu-id="ae2be-110">For those vendors that you want to pay electronically, you must select the **EFT Payment** check box and specify the vendor bank account in the **EFT Vendor Bank Account Code** field on the **Vendor** page.</span></span>  

<span data-ttu-id="ae2be-111">When you have set up bank accounts and vendors, you can create EFT file that are based on entries in the payment journal.</span><span class="sxs-lookup"><span data-stu-id="ae2be-111">When you have set up bank accounts and vendors, you can create EFT file that are based on entries in the payment journal.</span></span> <span data-ttu-id="ae2be-112">When you create an EFT file, an entry is made in the **EFT Register** table.</span><span class="sxs-lookup"><span data-stu-id="ae2be-112">When you create an EFT file, an entry is made in the **EFT Register** table.</span></span> <span data-ttu-id="ae2be-113">On the EFT Register page you can drill down to see the vendor ledger entries for the EFT file.</span><span class="sxs-lookup"><span data-stu-id="ae2be-113">On the EFT Register page you can drill down to see the vendor ledger entries for the EFT file.</span></span> <span data-ttu-id="ae2be-114">On the Payment Journal page, you can also import existing EFT register entries to the payment journal by using the **Transfer EFT Register** batch job.</span><span class="sxs-lookup"><span data-stu-id="ae2be-114">On the Payment Journal page, you can also import existing EFT register entries to the payment journal by using the **Transfer EFT Register** batch job.</span></span>

## <a name="see-also"></a><span data-ttu-id="ae2be-115">See Also</span><span class="sxs-lookup"><span data-stu-id="ae2be-115">See Also</span></span>  
[<span data-ttu-id="ae2be-116">Export Payments to a Bank File</span><span class="sxs-lookup"><span data-stu-id="ae2be-116">Export Payments to a Bank File</span></span>](../../payables-how-export-payments-bank-file.md)  
[<span data-ttu-id="ae2be-117">Australia Local Functionality</span><span class="sxs-lookup"><span data-stu-id="ae2be-117">Australia Local Functionality</span></span>](australia-local-functionality.md)
