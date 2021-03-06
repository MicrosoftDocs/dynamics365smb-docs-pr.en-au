---
title: Addresses in Australia
description: A single postcode can include multiple cities in the same region.
ms.custom: en-AU
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: conceptual
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: ''
ms.date: 04/01/2021
ms.author: edupont
ms.openlocfilehash: 7b08df620d963db0c131c9c1598e41e15c4ead30
ms.sourcegitcommit: 766e2840fd16efb901d211d7fa64d96766ac99d9
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 03/31/2021
ms.locfileid: "5775740"
---
# <a name="addresses-in-the-australian-version"></a>Addresses in the Australian Version

A single postcode can include multiple cities in the same region.  

At the same time, cities with the same name are sometimes located in different states.  

For example, Australian postcode 4069 covers the cities of Chapel Hill and Kenmore in the state of Queensland. However, there is also a city named Chapel Hill in the state of South Australia, located in postcode 5153.  

To avoid confusion and improve address accuracy, available options display when you enter data in address fields. For example, when you enter a postcode on a customer card, you can select from a list of all available cities for that postcode in the **City** field drop-down list. Likewise, when you enter a city name, you can select from a list of all available states in the **State** field drop-down list.  

To enable this functionality, you must enter the data into the **Postcode** table. You can do this manually, or you can download a copy of the Australian postcodes from the Australian Post Office website.  

To increase postal efficiency in Australia, the postal department has introduced an address bar coding system in which every address is assigned a unique identifier called a Delivery Point Identifier (DPID). From the DPID, a bar code is generated and printed for each address. Companies can receive discounts on bulk mailings if they use these bar codes. To retrieve a DPID, you must connect to the local postal database that uses authorised Address Matching Approval System (AMAS) software. You can reduce your number of postal returns by validating customer addresses using the AMAS database.  

When you print an address that has a DPID, a bar code will be printed together with the address. If you cannot print bar codes, the DPID will be printed together with the address.  

Contact your Microsoft partner for information on how to obtain AMAS software.  

## <a name="see-also"></a>See Also  
 [Australia Local Functionality](australia-local-functionality.md)


[!INCLUDE[footer-include](../../includes/footer-banner.md)]