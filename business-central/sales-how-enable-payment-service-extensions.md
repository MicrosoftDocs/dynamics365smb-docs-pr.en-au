---
title: Enable Customer Payments Through Payment Services| Microsoft Docs
description: Make it easier for customers to pay their invoices by enabling payment services.
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: conceptual
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: online payment
ms.date: 04/01/2021
ms.author: edupont
ms.openlocfilehash: 7f99bffb4f06efeb4922f979deaf27df7fe75946
ms.sourcegitcommit: 766e2840fd16efb901d211d7fa64d96766ac99d9
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 03/31/2021
ms.locfileid: "5778867"
---
# <a name="enable-customer-payments-through-payment-services"></a>Enable Customer Payments Through Payment Services
As an alternative to collecting payments through bank transfer or credit cards, your customers can pay you through their account with payment services, such as Microsoft Pay, PayPal, or WorldPay.  

After you enable a payment service in [!INCLUDE[prod_short](includes/prod_short.md)], a link to the service is available on sales documents that you send by email to your customers. Customers can use the link to go to the payment service and pay the bill, directly from the sales document. If you don't want to include the link, for example, if a customer will pay with cash, you can remove the payment service from the invoice before posting.  

The Microsoft Pay, PayPal Payments Standard, and WorldPay Payments Standard extensions are installed in [!INCLUDE[prod_short](includes/prod_short.md)], and are ready for you to enable.  

## <a name="to-enable-a-payment-service-in-prod_short"></a>To enable a payment service in [!INCLUDE[prod_short](includes/prod_short.md)]
1. Choose the ![Lightbulb that opens the Tell Me feature](media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Payment Services**, and then choose the related link.  
2. On the **Payment Services** page, choose the **New** action.  
3. Select the payment service, and then close the page.  
4. On the **Payment Services** page, choose the **Setup** action.  
5. Fill in the fields as necessary. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  
6. Close the page.  

## <a name="to-select-a-payment-service-on-a-sales-invoice"></a>To select a payment service on a sales invoice
1. Choose the ![Lightbulb that opens the Tell Me feature](media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Sales Invoices**, and then choose the related link.  
2. Open the sales invoice that you want to pay by using the payment service.  
3. In the **Payment Service** field, choose the payment service.  

    > [!NOTE]  
    > The **Payment Service** field is available only if you've enabled the payment service.  

## <a name="see-also"></a>See Also  
[Setting Up Sales](sales-setup-sales.md)  
[Sales](sales-manage-sales.md)  
[Customizing [!INCLUDE[prod_short](includes/prod_short.md)] Using Extensions](ui-extensions.md)  
[Working with [!INCLUDE[prod_short](includes/prod_short.md)]](ui-work-product.md)  


[!INCLUDE[footer-include](includes/footer-banner.md)]