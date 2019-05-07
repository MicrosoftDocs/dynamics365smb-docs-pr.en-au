---
title: How to Set Up Business Units for Business Activity Statements
description: Describes how to consolidate the financial statements of various companies into one financial statement.
services: project-madeira
documentationcenter: ''
author: bholtorf
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: ''
ms.date: 04/01/2019
ms.author: bholtorf
ms.openlocfilehash: 26c6c10c582c5e1302b260f9a90f9b651d3fb861
ms.sourcegitcommit: bd78a5d990c9e83174da1409076c22df8b35eafd
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 03/31/2019
ms.locfileid: "917350"
---
# <a name="set-up-business-units-for-business-activity-statements"></a>Set Up Business Units for Business Activity Statements
In [!INCLUDE[d365fin](../../includes/d365fin_md.md)], you can consolidate the financial statements of various companies into one financial statement.  

You must set up a consolidation company to perform the consolidation. In this company, the total amounts for all accounts in the group, from both the parent company and subsidiaries are added together. You must also indicate the general ledger accounts in the consolidated company to which the total should be transferred.  

You can use the **BAS Business Units** page to set up the following:  

- Parent company  
- Subsidiaries  
- Affiliates  

You must set up information on the **General Ledger Setup** page before you can set up business units.  

## <a name="to-set-up-general-ledger-for-a-business-activity-statement"></a>To set up general ledger for a business activity statement  
1. Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **General Ledger Setup**, and then choose the related link.  
2. Fill in the required fields as described in the following table.  

    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |**BAS to be Lodged as a Group**|Select if you are logging a business activity statement for a group of companies.|  
    |**BAS Group Company**|Select if this company is the main company in the group of companies for which you are lodging a group business activity statement.|  

3.  Choose the **OK** button.  

## <a name="to-set-a-business-unit-for-a-business-activity-statement"></a>To set a business unit for a business activity statement  
1. Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **BAS Business Units**, and then choose the related link.  
2. Fill in the fields as described in the following table.  

    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |**Company Name**|Specify the name of the company which will be added to the group company's business activity statement.|  
    |**Document No.**|Specify the BAS document number that has to be consolidated. This field is associated with the **BAS Version** field.|  
    |**BAS Version**|Specify the BAS version number in which the transaction was included. This field is associated with the **Document No.** field.|  

3. Choose the **OK** button.  

## <a name="see-also"></a>See Also  
[Australian Local Functionality](australia-local-functionality.md)   

