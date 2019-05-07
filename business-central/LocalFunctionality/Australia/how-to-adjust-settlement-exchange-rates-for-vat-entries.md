---
title: How to Adjust Settlement Exchange Rates for GST Entries
description: You can use the Adjust Settlement Exch. Rates batch job to settle GST entries according to the government exchange rate as defined in the **Currency Exchange Rate** table.
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.search.keywords: ''
ms.date: 04/01/2019
ms.author: sgroespe
ms.openlocfilehash: 3096382318805587c77734dd6550934242dcdc86
ms.sourcegitcommit: bd78a5d990c9e83174da1409076c22df8b35eafd
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 03/31/2019
ms.locfileid: "916267"
---
# <a name="adjust-settlement-exchange-rates-for-vat-entries"></a><span data-ttu-id="1f941-103">Adjust Settlement Exchange Rates for GST Entries</span><span class="sxs-lookup"><span data-stu-id="1f941-103">Adjust Settlement Exchange Rates for VAT Entries</span></span>
<span data-ttu-id="1f941-104">You can use the **Adjust Settlement Exch. Rates** batch job to settle GST entries according to the government exchange rate as defined in the **Currency Exchange Rate** table.</span><span class="sxs-lookup"><span data-stu-id="1f941-104">You can use the **Adjust Settlement Exch. Rates** batch job to settle VAT entries according to the government exchange rate as defined in the **Currency Exchange Rate** table.</span></span>  

## <a name="to-adjust-settlement-exchange-rates-for-vat"></a><span data-ttu-id="1f941-105">To adjust settlement exchange rates for GST</span><span class="sxs-lookup"><span data-stu-id="1f941-105">To adjust settlement exchange rates for VAT</span></span>  

1.  <span data-ttu-id="1f941-106">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Adjust Settlement Exch. Rates**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="1f941-106">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Adjust Settlement Exch. Rates**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="1f941-107">On the **Options** FastTab, fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="1f941-107">On the **Options** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="1f941-108">Field</span><span class="sxs-lookup"><span data-stu-id="1f941-108">Field</span></span>|<span data-ttu-id="1f941-109">Description</span><span class="sxs-lookup"><span data-stu-id="1f941-109">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="1f941-110">**Settlement Period**</span><span class="sxs-lookup"><span data-stu-id="1f941-110">**Settlement Period**</span></span>|<span data-ttu-id="1f941-111">Specifies the start date of the settlement period.</span><span class="sxs-lookup"><span data-stu-id="1f941-111">Specifies the start date of the settlement period.</span></span>|  
    |<span data-ttu-id="1f941-112">**Ending Date**</span><span class="sxs-lookup"><span data-stu-id="1f941-112">**Ending Date**</span></span>|<span data-ttu-id="1f941-113">Specifies the end date of the settlement period.</span><span class="sxs-lookup"><span data-stu-id="1f941-113">Specifies the end date of the settlement period.</span></span>|  
    |<span data-ttu-id="1f941-114">**Posting Description**</span><span class="sxs-lookup"><span data-stu-id="1f941-114">**Posting Description**</span></span>|<span data-ttu-id="1f941-115">Specifies the posting description.</span><span class="sxs-lookup"><span data-stu-id="1f941-115">Specifies the posting description.</span></span>|  
    |<span data-ttu-id="1f941-116">**Document No.**</span><span class="sxs-lookup"><span data-stu-id="1f941-116">**Document No.**</span></span>|<span data-ttu-id="1f941-117">Specifies the document number for which you want to settle GST entries.</span><span class="sxs-lookup"><span data-stu-id="1f941-117">Specifies the document number for which you want to settle VAT entries.</span></span>|  
    |<span data-ttu-id="1f941-118">**Posting Date**</span><span class="sxs-lookup"><span data-stu-id="1f941-118">**Posting Date**</span></span>|<span data-ttu-id="1f941-119">Specifies the posting date of the document.</span><span class="sxs-lookup"><span data-stu-id="1f941-119">Specifies the posting date of the document.</span></span>|  
    |<span data-ttu-id="1f941-120">**Use Daily Settlement Exch. Rate**</span><span class="sxs-lookup"><span data-stu-id="1f941-120">**Use Daily Settlement Exch. Rate**</span></span>|<span data-ttu-id="1f941-121">Select if you want to use the daily settlement exchange rate.</span><span class="sxs-lookup"><span data-stu-id="1f941-121">Select if you want to use the daily settlement exchange rate.</span></span>|  

3.  <span data-ttu-id="1f941-122">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="1f941-122">Choose the **OK** button.</span></span>  

<span data-ttu-id="1f941-123">The GST entries are adjusted and you can view them in the **GST Register** report.</span><span class="sxs-lookup"><span data-stu-id="1f941-123">The VAT entries are adjusted and you can view them in the **VAT Register** report.</span></span>
