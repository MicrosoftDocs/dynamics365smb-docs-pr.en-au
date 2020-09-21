---
title: How to Adjust Settlement Exchange Rates for GST Entries
description: You can use the Adjust Settlement Exch. Rates batch job to settle GST entries according to the government exchange rate as defined in the Currency Exchange Rate table.
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.search.keywords: ''
ms.date: 08/17/2020
ms.author: edupont
ms.openlocfilehash: fef20b9a0cf0c2dc1a3a30a42f82d6de13397c13
ms.sourcegitcommit: a80afd4e5075018716efad76d82a54e158f1392d
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 09/09/2020
ms.locfileid: "3778750"
---
# <a name="adjust-settlement-exchange-rates-for-vat-entries"></a>Adjust Settlement Exchange Rates for GST Entries

You can use the **Adjust Settlement Exch. Rates** batch job to settle GST entries according to the government exchange rate as defined in the **Currency Exchange Rate** table.  

## <a name="to-adjust-settlement-exchange-rates-for-vat"></a>To adjust settlement exchange rates for GST  

1. Choose the ![Lightbulb that opens the Tell Me feature](../../media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Adjust Settlement Exch. Rates**, and then choose the related link.  
2. Fill in the fields as described in the following table.  

    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |**Settlement Period**|Specifies the start date of the settlement period.|  
    |**Ending Date**|Specifies the end date of the settlement period.|  
    |**Posting Description**|Specifies the posting description.|  
    |**Document No.**|Specifies the document number for which you want to settle GST entries.|  
    |**Posting Date**|Specifies the posting date of the document.|  
    |**Use Daily Settlement Exch. Rate**|Select if you want to use the daily settlement exchange rate.|  

3. Choose the **OK** button.  

The GST entries are adjusted, and you can view them in the **GST Register** report.

## <a name="see-also"></a>See Also

[Australia Local Functionality](australia-local-functionality.md)  
