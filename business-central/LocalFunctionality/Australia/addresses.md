---
title: Addresses in Australia
description: Use the Postcode feature to improve accuracy for cases in which a single postcode can include multiple cities in the same region.
ms.custom: en-AU
author: brentholtorf
ms.topic: conceptual
ms.devlang: al
ms.search.keywords: null
ms.date: 11/22/2023
ms.author: bholtorf
ms.service: dynamics-365-business-central
---
# <a name="about-addresses-in-the-australian-version"></a>About addresses in the Australian version

A single postcode can include multiple cities in the same region. At the same time, cities with the same name are sometimes located in different states.  

For example, Australian postcode 4069 covers the cities of Chapel Hill and Kenmore in the state of Queensland. However, there's also a city named Chapel Hill in the state of South Australia, located in postcode 5153.  

To avoid confusion and improve address accuracy, available options display when you enter data in address fields. For example, when you enter a postcode on a customer card, you can select from a list of all available cities for that postcode in the **City** field drop-down list. Likewise, when you enter a city name, you can select from a list of all available states in the **State** field drop-down list.  

To enable this functionality, you must enter the data into the **Postcode** table. You can do this manually, or you can download a copy of the Australian postcodes from the Australian Post Office website.  

To increase postal efficiency in Australia, the postal department introduced an address bar coding system in which every address is assigned a unique identifier called a Delivery Point Identifier (DPID). From the DPID, a bar code is generated and printed for each address. Companies can receive discounts on bulk mailings if they use these bar codes. To retrieve a DPID, you must connect to the local postal database that uses authorised Address Matching Approval System (AMAS) software. You can reduce your number of postal returns by validating customer addresses using the AMAS database.  

When you print an address that has a DPID, a bar code is printed together with the address. If you can't print bar codes, the DPID is printed together with the address.  

Contact your Microsoft partner for information on how to obtain AMAS software.  

## <a name="see-also"></a>See also
 [Australia Local Functionality](australia-local-functionality.md)


[!INCLUDE[footer-include](../../includes/footer-banner.md)]
