---
title: How to Set Up Vendors Without ABN for Calculating the Withholding Tax
description: Withholding Tax (WHT) is calculated for local vendors who do not have an Australian Business Number (ABN), as required by tax law.
services: project-madeira
documentationcenter: ''
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: ''
ms.date: 10/01/2018
ms.author: sgroespe
ms.openlocfilehash: 6b731f28dfb956395309dd3956487bac2234850f
ms.sourcegitcommit: 1bcfaa99ea302e6b84b8361ca02730b135557fc1
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 03/08/2019
ms.locfileid: "826273"
---
# <a name="set-up-vendors-without-abn-for-calculating-the-withholding-tax"></a>Set Up Vendors Without ABN for Calculating the Withholding Tax
Withholding Tax (WHT) is calculated for local vendors who do not have an Australian Business Number (ABN), as required by tax law.  

## <a name="to-set-up-vendors-without-abn-for-calculating-the-withholding-tax"></a>To set up vendors without ABN for calculating the withholding tax  

1.  Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Vendors**, and then choose the related link.  
2.  Choose the required vendor, and then choose the **Edit** action.  
3.  On the **Vendor Card** page, on the **Registration** FastTab, make sure the **ABN** field and the **Foreign Vend** field must be empty.  
4.  Choose the **OK** button.  

    > [!NOTE]  
    >  The WHT percentage is automatically withheld in accordance with what was specified on the **WHT Posting Setup** page. The WHT certificate is produced for submission to the vendor. For more information, see [Withholding Tax](withholding-tax.md).  

## <a name="see-also"></a>See Also  
 [Withholding Tax](withholding-tax.md)   
 [Set Up Withholding Tax](how-to-set-up-withholding-tax.md)
