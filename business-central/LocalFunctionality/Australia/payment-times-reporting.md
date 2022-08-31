---
title: Payment Times Reporting in the Australian version
description: Payment Times Reporting is not directly supported in the Australian version of Business Central, but this article can help you get to the data you need to report.
author: sorenfriisalexandersen
ms.topic: conceptual
ms.search.keywords: ''
ms.date: 06/07/2021
ms.author: soalex
ms.openlocfilehash: 7f3389cf252efb45af3341f605a7755102b91a3e
ms.sourcegitcommit: ef80c461713fff1a75998766e7a4ed3a7c6121d0
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 02/15/2022
ms.locfileid: "8135558"
---
# <a name="payment-times-reporting-in-the-australian-version"></a>Payment Times Reporting in the Australian Version

Businesses in Australia that have a group-wide revenue of AUD 100,000,000 or more must report to the authorities how they pay their small business vendors. A company is considered a reporting entity if they exceed that revenue threshold, or if a company has a revenue of AUD 10,000,000 or more while also being part of a controlling corporation with a revenue of AUD 100,000,000 or more. Small businesses must register in a system that is made available by the authorities, and reporting entities must look up their vendors in this system to check if a given vendor qualifies as a small business vendor and report the relevant amounts. See more about the reporting rules and registration at lookup in the Small Business identification tool here: [https://www.industry.gov.au/regulations-and-standards/payment-times-reporting-scheme](https://www.industry.gov.au/regulations-and-standards/payment-times-reporting-scheme).

## <a name="support-for-payment-times-reporting-in-business-central"></a>Support for Payment Times Reporting in Business Central
 
Business Central supports Australian businesses in running their financial reporting. While Business Central does not have a dedicated report for reporting according to the Payment Times Reporting Scheme, the data that you need for the report is present. However, for more automated reporting, you must find and install an add-in that is built by a Business Central partner.  

## <a name="reporting-the-payment-times"></a>Reporting the Payment Times

As a reporting entity, you must provide the authorities with two files:

 * A declaration document that states that the reported numbers are true, signed by a responsible member of the reporting entity or controlling corporation.
 * A delimited text file that contains a line with the reported information in various fields.

Examples and descriptions of these files can be found on the Australian authorities' website: [https://www.industry.gov.au/regulations-and-standards/payment-times-reporting-scheme](https://www.industry.gov.au/regulations-and-standards/payment-times-reporting-scheme).

The information in the following sections relates only to the delimited text file. The content is intended as model for getting some of the relevant information from Business Central in a manual fashion. Partner-provided capabilities may exist that provide functionality to automate this.

### <a name="marking-a-vendor-as-a-small-business-vendor"></a>Marking a vendor as a Small Business Vendor

Consider creating a new **Vendor Posting Group** to be set on vendors that are confirmed to be small business vendors in the **Small Business** identification tool. You must look up a vendor in this tool to get this confirmation. Once a vendor is set to this vendor posting group, the posting group will be propagated to the vendor ledger entries, which is key for you to be able to find relevant entries for the report.  

### <a name="the-reporting-data"></a>The reporting data

As you will see from the example template of the delimited text file, much of the information needed for reporting is textual and has to do with trade agreements and explanations for various business decisions. However, there are also numbers that must be reported.  

From a reporting perspective, the interesting thing is how the reporting entity pays its small business vendors. The authorities have defined buckets into which these payments fall and must be reported.

For example, in June 2021, these buckets are:

* Invoices paid within 20 days after the day of receipt
* Invoices paid between 21 days and 30 days after the day of receipt
* Invoices paid between 31 days and 60 days after the day of receipt
* Invoices paid between 61 days and 90 days after the day of receipt
* Invoices paid between 91 days and 120 days after the day of receipt
* Invoices paid more than 120 days after the day of receipt 

As a scenario, you must report how many invoices from small business vendors have been paid between 21 and 30 days after the day of receipt of the invoice. You must also report the proportional invoice amount of those invoices compared to the total number of invoices from small business vendors.

### <a name="finding-the-data-for-the-payment-times-report"></a>Finding the data for the Payment Times Report

As mentioned above, many fields and much of the data needed for the report does not reside in Business Central. The invoice data does, and you can find this data in the vendor ledger entries. The following procedure illustrates how you can find the relevant data.

#### <a name="to-find-vendor-ledger-entries"></a>To find vendor ledger entries

1. Choose the ![Lightbulb that opens the Tell Me feature.](../../media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Vendor Ledger Entries**, and then choose the related link.  
2. Filter the view to include entries within the reporting period.
3. Use the **Filter Totals** and use the **Date Filter** to specify a range that exceeds the reporting period. You can use this to exclude invoices from the list that have not yet been paid, by comparing the **Original Amount** and **Remaining Amount** fields. 
4. Filter the list to show only invoices by setting a filter on **Document Type**.
5. Filter on the **Vendor Posting Group** to only see invoices from small business vendors. 

    You can now go through invoices one by one and select the **Applied Entries** action to see information about payments that have been applied to the invoice.
6. In the **Applied Entries** page, make sure you look at records where **Document Type** is **Payment**, so you do not report on invoices that have been closed by a CR/Adj note, for example.
7. If there is a payment for the invoice, use the **Posting Date** to determine how many days have elapsed since receipt of the invoice by comparing it to the **Posting Date** of the Invoice **Vendor Ledger Entry**. 
8. Note down how this invoice affects the bucket (such as 21 to 30 days) when it comes to the number of invoices and the proportional number of small business vendor invoices.

As an alternative, consider exporting the full list of vendor ledger entries to Excel by using the action **Page** > **Open in Excel**. In Excel, you can do more advanced calculations and formulas to find the applied entries and payments for an invoice.

> [!NOTE]
> Invoices and their corresponding payments are all vendor ledger entries. Using Excel to find the relevant payments for a given invoice may be more convenient for you. 


## <a name="see-also"></a>See Also

[Australia Local Functionality](australia-local-functionality.md)  


[!INCLUDE[footer-include](../../includes/footer-banner.md)]
