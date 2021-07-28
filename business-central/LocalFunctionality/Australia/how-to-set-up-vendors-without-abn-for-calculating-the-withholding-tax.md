---
title: Set Up Suppliers Without ABN for Calculating WHT
description: In Business Central, Withholding Tax (WHT) is calculated for local suppliers who do not have an Australian Business Number (ABN), as required by tax law.
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: conceptual
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: ''
ms.date: 04/01/2021
ms.author: edupont
ms.openlocfilehash: 01dd5a83f3b73a44bcfe81d3edead8747ab8f930
ms.sourcegitcommit: a7cb0be8eae6ece95f5259d7de7a48b385c9cfeb
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 07/08/2021
ms.locfileid: "6438495"
---
# <a name="set-up-vendors-without-abn-for-calculating-the-withholding-tax-in-the-australian-version"></a>Set Up Suppliers Without ABN for Calculating the Withholding Tax in the Australian Version

Withholding Tax (WHT) is calculated for local suppliers who do not have an Australian Business Number (ABN), as required by tax law.  

## <a name="to-set-up-vendors-without-abn-for-calculating-the-withholding-tax"></a>To set up suppliers without ABN for calculating the withholding tax  

1.  Choose the ![Lightbulb that opens the Tell Me feature.](../../media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Suppliers**, and then choose the related link.  
2.  Choose the required supplier, and then choose the **Edit** action.  
3.  On the **Supplier Card** page, make sure the **ABN** field and the **Foreign Vend** field are empty.  
4.  Choose the **OK** button.  

    > [!NOTE]  
    >  The WHT percentage is automatically withheld in accordance with what was specified on the **WHT Posting Setup** page. The WHT certificate is produced for submission to the supplier. For more information, see [Withholding Tax](withholding-tax.md).  

## <a name="see-also"></a>See Also  
 [Withholding Tax](withholding-tax.md)   
 [Set Up Withholding Tax](how-to-set-up-withholding-tax.md)


[!INCLUDE[footer-include](../../includes/footer-banner.md)]