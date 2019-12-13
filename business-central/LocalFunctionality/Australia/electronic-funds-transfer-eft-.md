---
title: Electronic Funds Transfer (EFT)
description: You can pay vendors using the electronic funds transfer (EFT) system in Australia.
author: bholtorf
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: ''
ms.date: 10/01/2019
ms.author: bholtorf
ms.openlocfilehash: fd517101454aa7e70332bc1284770517e8d2d882
ms.sourcegitcommit: cfc92eefa8b06fb426482f54e393f0e6e222f712
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 12/03/2019
ms.locfileid: "2878731"
---
# <a name="electronic-funds-transfer-eft"></a><span data-ttu-id="7c3be-103">Electronic Funds Transfer (EFT)</span><span class="sxs-lookup"><span data-stu-id="7c3be-103">Electronic Funds Transfer (EFT)</span></span>
<span data-ttu-id="7c3be-104">You can pay vendors using the electronic funds transfer (EFT) system in Australia.</span><span class="sxs-lookup"><span data-stu-id="7c3be-104">You can pay vendors using the electronic funds transfer (EFT) system in Australia.</span></span>  

## <a name="setting-up-electronic-funds-transfer-in-included365finincludesd365fin_mdmd"></a><span data-ttu-id="7c3be-105">Setting up Electronic Funds Transfer in [!INCLUDE[d365fin](../../includes/d365fin_md.md)]</span><span class="sxs-lookup"><span data-stu-id="7c3be-105">Setting up Electronic Funds Transfer in [!INCLUDE[d365fin](../../includes/d365fin_md.md)]</span></span>  
[!INCLUDE[d365fin](../../includes/d365fin_md.md)] <span data-ttu-id="7c3be-106">can export EFT files that you can then upload to your bank’s website for additional processing.</span><span class="sxs-lookup"><span data-stu-id="7c3be-106">can export EFT files that you can then upload to your bank’s website for additional processing.</span></span> <span data-ttu-id="7c3be-107">To submit EFT files, you must set up the following information:</span><span class="sxs-lookup"><span data-stu-id="7c3be-107">To submit EFT files, you must set up the following information:</span></span>  

* <span data-ttu-id="7c3be-108">You must add EFT information to the bank account or bank accounts that you will use to pay vendors electronically.</span><span class="sxs-lookup"><span data-stu-id="7c3be-108">You must add EFT information to the bank account or bank accounts that you will use to pay vendors electronically.</span></span> <span data-ttu-id="7c3be-109">The EFT-specific fields are on the **Bank Account** page.</span><span class="sxs-lookup"><span data-stu-id="7c3be-109">The EFT-specific fields are on the **Bank Account** page.</span></span>  
* <span data-ttu-id="7c3be-110">For those vendors that you want to pay electronically, you must select the **EFT Payment** check box and specify the vendor bank account in the **EFT Vendor Bank Account Code** field on the **Vendor** page.</span><span class="sxs-lookup"><span data-stu-id="7c3be-110">For those vendors that you want to pay electronically, you must select the **EFT Payment** check box and specify the vendor bank account in the **EFT Vendor Bank Account Code** field on the **Vendor** page.</span></span>  

<span data-ttu-id="7c3be-111">When you have set up bank accounts and vendors, you can create EFT files that are based on entries in the payment journal.</span><span class="sxs-lookup"><span data-stu-id="7c3be-111">When you have set up bank accounts and vendors, you can create EFT files that are based on entries in the payment journal.</span></span> <span data-ttu-id="7c3be-112">When you create an EFT file, an entry is made in the **EFT Register** table.</span><span class="sxs-lookup"><span data-stu-id="7c3be-112">When you create an EFT file, an entry is made in the **EFT Register** table.</span></span> <span data-ttu-id="7c3be-113">On the **EFT Register** page, you can drill down to see the vendor ledger entries for the EFT file.</span><span class="sxs-lookup"><span data-stu-id="7c3be-113">On the **EFT Register** page, you can drill down to see the vendor ledger entries for the EFT file.</span></span> <span data-ttu-id="7c3be-114">On the **Payment Journal** page, you can also import existing EFT register entries to the payment journal by using the **Transfer EFT Register** batch job.</span><span class="sxs-lookup"><span data-stu-id="7c3be-114">On the **Payment Journal** page, you can also import existing EFT register entries to the payment journal by using the **Transfer EFT Register** batch job.</span></span>

> [!NOTE]  
> <span data-ttu-id="7c3be-115">Electronic Funds Transfer (EFT) uses posted and nonposted payments as the basis to calculate withholding tax amounts for applied invoices.</span><span class="sxs-lookup"><span data-stu-id="7c3be-115">Electronic Funds Transfer (EFT) uses posted and nonposted payments as the basis to calculate withholding tax amounts for applied invoices.</span></span> <span data-ttu-id="7c3be-116">Payments that are not applied to an invoice can only be exported to an EFT file if the **Skip WHT** check box is selected.</span><span class="sxs-lookup"><span data-stu-id="7c3be-116">Payments that are not applied to an invoice can only be exported to an EFT file if the **Skip WHT** check box is selected.</span></span> <span data-ttu-id="7c3be-117">During export of the EFT file, the payment journal lines are not deleted and cannot be deleted as long as they have a reference to an EFT register.</span><span class="sxs-lookup"><span data-stu-id="7c3be-117">During export of the EFT file, the payment journal lines are not deleted and cannot be deleted as long as they have a reference to an EFT register.</span></span> <span data-ttu-id="7c3be-118">To remove the link between the EFT register and payment journal lines, choose the **Cancel Export** action either on the **EFT Register** page or the **Payment Journal** page.</span><span class="sxs-lookup"><span data-stu-id="7c3be-118">To remove the link between the EFT register and payment journal lines, choose the **Cancel Export** action either on the **EFT Register** page or the **Payment Journal** page.</span></span>       

## <a name="see-also"></a><span data-ttu-id="7c3be-119">See Also</span><span class="sxs-lookup"><span data-stu-id="7c3be-119">See Also</span></span>  
[<span data-ttu-id="7c3be-120">Export Payments to a Bank File</span><span class="sxs-lookup"><span data-stu-id="7c3be-120">Export Payments to a Bank File</span></span>](../../payables-how-export-payments-bank-file.md)  
[<span data-ttu-id="7c3be-121">Australia Local Functionality</span><span class="sxs-lookup"><span data-stu-id="7c3be-121">Australia Local Functionality</span></span>](australia-local-functionality.md)
