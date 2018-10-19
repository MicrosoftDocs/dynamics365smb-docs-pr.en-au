---
title: Electronic Funds Transfer (EFT)
description: You can pay vendors using the electronic funds transfer (EFT) system in Australia.
services: project-madeira
documentationcenter: 
author: bholtorf
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 10/01/2018
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: 78cb55d0c53db5b0a8252ffae6316a537be25459
ms.openlocfilehash: 642cc34b0810777ac6e5049e18443a8120d477c6
ms.contentlocale: en-au
ms.lasthandoff: 10/15/2018

---
# <a name="electronic-funds-transfer-eft"></a><span data-ttu-id="c6148-103">Electronic Funds Transfer (EFT)</span><span class="sxs-lookup"><span data-stu-id="c6148-103">Electronic Funds Transfer (EFT)</span></span>
<span data-ttu-id="c6148-104">You can pay vendors using the electronic funds transfer (EFT) system in Australia.</span><span class="sxs-lookup"><span data-stu-id="c6148-104">You can pay vendors using the electronic funds transfer (EFT) system in Australia.</span></span>  

## <a name="setting-up-electronic-funds-transfer-in-included365finincludesd365finmdmd"></a><span data-ttu-id="c6148-105">Setting up Electronic Funds Transfer in [!INCLUDE[d365fin](../../includes/d365fin_md.md)]</span><span class="sxs-lookup"><span data-stu-id="c6148-105">Setting up Electronic Funds Transfer in [!INCLUDE[d365fin](../../includes/d365fin_md.md)]</span></span>  
[!INCLUDE[d365fin](../../includes/d365fin_md.md)] <span data-ttu-id="c6148-106">can export EFT files that you can then upload to your bank’s website for additional processing.</span><span class="sxs-lookup"><span data-stu-id="c6148-106">can export EFT files that you can then upload to your bank’s website for additional processing.</span></span> <span data-ttu-id="c6148-107">To submit EFT files, you must set up the following information:</span><span class="sxs-lookup"><span data-stu-id="c6148-107">To submit EFT files, you must set up the following information:</span></span>  

* <span data-ttu-id="c6148-108">You must add EFT information to the bank account or bank accounts that you will use to pay vendors electronically.</span><span class="sxs-lookup"><span data-stu-id="c6148-108">You must add EFT information to the bank account or bank accounts that you will use to pay vendors electronically.</span></span> <span data-ttu-id="c6148-109">The EFT-specific fields are on the **Transfer** FastTab in the **Bank Account** window.</span><span class="sxs-lookup"><span data-stu-id="c6148-109">The EFT-specific fields are on the **Transfer** FastTab in the **Bank Account** window.</span></span>  
* <span data-ttu-id="c6148-110">For those vendors that you want to pay electronically, you must select the **EFT Payment** check box and specify the vendor bank account in the **EFT Vendor Bank Account Code** field in the **Vendor** window.</span><span class="sxs-lookup"><span data-stu-id="c6148-110">For those vendors that you want to pay electronically, you must select the **EFT Payment** check box and specify the vendor bank account in the **EFT Vendor Bank Account Code** field in the **Vendor** window.</span></span>  

<span data-ttu-id="c6148-111">When you have set up bank accounts and vendors, you can create EFT file that are based on entries in the payment journal.</span><span class="sxs-lookup"><span data-stu-id="c6148-111">When you have set up bank accounts and vendors, you can create EFT file that are based on entries in the payment journal.</span></span> <span data-ttu-id="c6148-112">When you create an EFT file, an entry is made in the **EFT Register** table.</span><span class="sxs-lookup"><span data-stu-id="c6148-112">When you create an EFT file, an entry is made in the **EFT Register** table.</span></span> <span data-ttu-id="c6148-113">On the EFT Register page you can drill down to see the vendor ledger entries for the EFT file.</span><span class="sxs-lookup"><span data-stu-id="c6148-113">On the EFT Register page you can drill down to see the vendor ledger entries for the EFT file.</span></span> <span data-ttu-id="c6148-114">On the Payment Journal page, you can also import existing EFT register entries to the payment journal by using the **Transfer EFT Register** batch job.</span><span class="sxs-lookup"><span data-stu-id="c6148-114">On the Payment Journal page, you can also import existing EFT register entries to the payment journal by using the **Transfer EFT Register** batch job.</span></span>

> [!NOTE]  
> <span data-ttu-id="c6148-115">Electronic Funds Transfer (EFT) uses posted and non-posted payments as the basis to calculate withholding tax amounts for applied invoices.</span><span class="sxs-lookup"><span data-stu-id="c6148-115">Electronic Funds Transfer (EFT) uses posted and non-posted payments as the basis to calculate withholding tax amounts for applied invoices.</span></span> <span data-ttu-id="c6148-116">Payments that are not applied to an invoice can only be exported to an EFT file if the **Skip WHT** check box is selected.</span><span class="sxs-lookup"><span data-stu-id="c6148-116">Payments that are not applied to an invoice can only be exported to an EFT file if the **Skip WHT** check box is selected.</span></span> <span data-ttu-id="c6148-117">During export of the EFT file, the payment journal lines are not deleted and cannot be deleted as long as they have a reference to an EFT register.</span><span class="sxs-lookup"><span data-stu-id="c6148-117">During export of the EFT file, the payment journal lines are not deleted and cannot be deleted as long as they have a reference to an EFT register.</span></span> <span data-ttu-id="c6148-118">To remove the link between the EFT register and payment journal lines, choose the **Cancel Export** action either in the **EFT Register** window or the **Payment Journal** window.</span><span class="sxs-lookup"><span data-stu-id="c6148-118">To remove the link between the EFT register and payment journal lines, choose the **Cancel Export** action either in the **EFT Register** window or the **Payment Journal** window.</span></span>       

## <a name="see-also"></a><span data-ttu-id="c6148-119">See Also</span><span class="sxs-lookup"><span data-stu-id="c6148-119">See Also</span></span>  
[<span data-ttu-id="c6148-120">Export Payments to a Bank File</span><span class="sxs-lookup"><span data-stu-id="c6148-120">Export Payments to a Bank File</span></span>](../../payables-how-export-payments-bank-file.md)  
[<span data-ttu-id="c6148-121">Australia Local Functionality</span><span class="sxs-lookup"><span data-stu-id="c6148-121">Australia Local Functionality</span></span>](australia-local-functionality.md)

