---
title: How to Split Warehouse Activity Lines | Microsoft Docs
description: In warehouse put-aways, movements, or picks, and in inventory put-aways and inventory picks, bins are suggested for the picking or putting away of items. The actual quantity in the bin suggested may not be sufficient, or there is not enough room in the suggested bin to put away the required quantity. In these cases, you need to split the line, so that the items for one line are either taken from or placed into more than one bin.
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: conceptual
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: ''
ms.date: 04/01/2021
ms.author: edupont
ms.openlocfilehash: 08cebf3fb140fd76396add89bf8d7418aa4f115a
ms.sourcegitcommit: 766e2840fd16efb901d211d7fa64d96766ac99d9
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 03/31/2021
ms.locfileid: "5784150"
---
# <a name="split-warehouse-activity-lines"></a>Split Warehouse Activity Lines
In warehouse put-aways, movements, or picks, and in inventory put-aways and inventory picks, bins are suggested for the picking or putting away of items. The actual quantity in the bin suggested may not be sufficient, or there is not enough room in the suggested bin to put away the required quantity. In these cases, you need to split the line, so that the items for one line are either taken from or placed into more than one bin.  

The following procedure applies to warehouse documents, such as warehouse put-away, movement, and pick lines, or inventory put-away, movement, and pick lines.  

## <a name="to-split-warehouse-activity-lines"></a>To split warehouse activity lines  
1.  Open a warehouse activity line where you are trying to handle an insufficient quantity.  
2.  In the **Qty. to Handle** field, enter the reduced quantity that you are able to handle.  
3.  On the **Lines** FastTab, choose the **Actions** action, choose the **Functions** action, and then choose the **Split Line** action. A new line appears, which is a copy of the original line, except that the **Qty. to Handle** field contains the quantity that you removed from the original line.  
4.  Assign an appropriate bin and, if you are using directed put-away and pick, a zone, to this new line, or continue splitting the line as necessary until you find appropriate bins for all of the quantity.  

> [!NOTE]  
>  If the location uses directed put-away and pick and you split the lines, you must be familiar with the warehouse and be able to choose a bin that matches the storage requirements of the item and that fulfils the general requirements of the warehouse document. For example, you would not split a line on a pick document and place some items in the bulk storage.  

## <a name="see-also"></a>See Also  
[Warehouse Management](warehouse-manage-warehouse.md)  
[Inventory](inventory-manage-inventory.md)  
[Setting Up Warehouse Management](warehouse-setup-warehouse.md)     
[Assembly Management](assembly-assemble-items.md)    
[Design Details: Warehouse Management](design-details-warehouse-management.md)  
[Working with [!INCLUDE[prod_short](includes/prod_short.md)]](ui-work-product.md)


[!INCLUDE[footer-include](includes/footer-banner.md)]