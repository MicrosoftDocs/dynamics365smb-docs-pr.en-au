---
title: Validate Exemption Certification Numbers
description: Let Business Central validate Exemption Certification numbers and other company information for your contacts, customers, and vendors, based on the European Union VIES GST Number Validation service.
author: andregu
ms.service: dynamics365-business-central
ms.topic: conceptual
ms.reviewer: edupont
ms.search.keywords: VAT, posting, tax, value-added tax
ms.date: 04/01/2021
ms.author: andregu
ms.openlocfilehash: 9e7c60e884ad65e209a2513d63c9434a90d9b449
ms.sourcegitcommit: 766e2840fd16efb901d211d7fa64d96766ac99d9
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 03/31/2021
ms.locfileid: "5770299"
---
# <a name="validate-vat-registration-numbers"></a>Validate Exemption Certification Numbers

It is important that the Exemption Certification numbers you have for customers, vendors, and contacts are valid, if you use [!INCLUDE [prod_short](includes/prod_short.md)] in a country that uses GST. For example, companies sometimes change their tax liability status, and in some countries tax authorities might ask you to provide reports, such as the **EC Sales List** report, that list the Exemption Certification numbers you use when you do business.

The European Commission provides the VIES VAT Number Validation service on its website, which is public and free. [!INCLUDE [prod_short](includes/prod_short.md)] can save you a step and let you use the VIES service to validate and track GST numbers and other company information for customers, vendors, and contacts. The service in [!INCLUDE [prod_short](includes/prod_short.md)] is named **EU VAT Reg. No. Validation Service**. The service is available on the **Service Connections** page, and you can start using it right away. The service connection is free, and additional sign up is not required.

## <a name="configure-the-service-to-verify-vat-registration-numbers-automatically"></a>Configure the service to verify Exemption Certification numbers automatically

To enable the **EU Exempt. Cert. No. Validation Service**, open the entry in the **Service Connection** page. If the **Service Endpoint** field is not already filled in, use the **Set Default Endpoint** action. Then set the **Enabled** field, and you are good to go.  

> [!IMPORTANT]
> To enable the validation service, you must have administrator permissions.

Optionally, set up templates for the types of GST-related data that you want the service to also check. For more information, see the [Validation templates](#validation-templates) section.

When you use our service connection, we record a history of VAT numbers and verifications for each customer, vendor, or contact, in the **VAT Registration Log**, so you can easily track them. The log is specific to each customer. For example, the log is useful for proving that you have verified that the current GST number is correct. When you verify a VAT number, the **Request Identifier** column in the log will reflect that you have taken action.

You can view the GST Registration log on the Customer, Vendor, or Contact cards, on the **Invoicing** FastTab, by choosing the lookup button in the **Exemption Certification No.** field.  

There are a couple of things to note about the VIES VAT Number Validation service:

* The service uses the http protocol, which means that data transferred through the service is not encrypted.  
* You may experience downtime for this service for which Microsoft is not responsible. The service is part of a broad EU network of national VAT registers.

> [!IMPORTANT]
> It is your responsibility to check that the data is valid. On occasion, data with errors is returned by the VIES VAT Number Validation service. If validation fails, validate the Exemption Certification numbers on the [web site](https://ec.europa.eu/taxation_customs/vies/), print the result or save it to a shared location, and then add the link to the record for your customer, vendor, or contact. For more information, see [Manage Attachments, Links, and Notes on Cards and Documents](ui-how-add-link-to-record.md).

## <a name="validation-templates"></a>Validation templates

[!INCLUDE [2020rw_online_only](includes/2020rw_online_only.md)]

You can use the VIES service to also check other company information, such as the address, as well as the Exemption Certification number. In the **Exempt. Cert. No. Validation Templates** page, create an entry for each country that you want to get further validation for, and then specify the information that you want to get validated automatically.  

For example, add an entry for Spain where you want to get validation for name, street, city, and postcode, and then another entry for Germany where you just want validation for postcode, for example. Then, in the **EU Exemption Certificate No. Validation Service Setup** page, specify the default template.  

> [!NOTE]
> Always make sure that the default template works for your needs. You can change the default to match your requirements, such as get validation for all fields or no fields.

The next time that you specify a Exemption Certification number, the service validates the number and any additional data as determined by your validation templates. If the specified values are different from the values that are returned by the service, you will see the details in the **Validation Details** page where you can accept or reset the values.  

## <a name="see-also"></a>See Also

[Set Up Value-Added Tax](finance-setup-vat.md)  
[Setting Up Unrealized Value Added Tax](finance-setup-unrealized-vat.md)  
[Report GST to a Tax Authority](finance-how-report-vat.md)  
[Work with GST on Sales and Purchases](finance-work-with-vat.md)  
[Local functionality in Business Central](about-localization.md)  


[!INCLUDE[footer-include](includes/footer-banner.md)]
