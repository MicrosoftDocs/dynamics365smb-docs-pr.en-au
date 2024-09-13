---
title: Sustainability financial reporting
description: Describes how to use financial reports to create various views and reports for analyzing sustainability performance data.
author: altotovi
ms.topic: conceptual
ms.search.keywords: reporting
ms.search.form: '104, 108, 490'
ms.date: 08/22/2024
ms.author: altotovi
ms.service: dynamics-365-business-central
---

# <a name="analyzing-sustainability-entries-with-financial-reports"></a>Analyzing sustainability entries with financial reports

The *Financial Reports* feature gives you insights into the financial data shown on your chart of accounts (COA). You can set up financial reports to analyse figures in general ledger (G/L) accounts, and compare general ledger entries with budget entries. But you can also analyze statistical and sustainability data with the same feature, and even combine all three types of data.  

## <a name="prerequisites-for-financial-reporting"></a>Prerequisites for financial reporting

Setting up financial reports requires an understanding of the structure of the data you want to analyze. There are some key concepts that you likely need to pay attention to before you design your financial reports: 

1. Related to the Chart of Accounts: 
   1. Map G/L posting accounts to G/L account categories. 
   2. Design how you use dimensions.
   3. Set up G/L budgets.  
2. Related to the Sustainability:   
   1. Set up your sustainability accounts. 
   2. Set up your carbon fees and CO2e in the **Emission Fees**.
   3. Design how you use dimensions.  
3. Related to the Statistical accounts: 
   1. Set up your statistical accounts. 
   2. Design how you use dimensions.  

> [!NOTE]
> Financial reports doens't work directly with CO2, CH4, or N2O emissions. Instead of that it uses the CO2 equivalent model and that means you must first configure **CO2e** (carbon-dioxide equivalent) on the **Emission Fees** page.  

> [!NOTE]
> More detaials about using Financial reports with financial data and chart of accounts can be found here [Build Financial Reports Using Financial Data and Account Categories](bi-how-work-account-schedule.md).   

## <a name="create-a-new-financial-report"></a>Create a new financial report

To quickly create your own financial reports, start by copying an existing one, as described in step 3 below. 

1. Choose the ![Lightbulb that opens the Tell Me feature 1.](media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Financial Reports**, then choose the related link.  
2. On the **Financial Reports** page, choose the **New** action to create a new financial report name.  
3. Fill in the report short name in **Name** (you can't change the name later) field and enter **Description**.  
4. Choose a row definition and a column definition.   
5. Choose the **Edit Report Definition** action to access more properties on the financial report.  
6. On the **Options** FastTab, you can edit the report description, change the row and column definitions, and define how to show dates. Dates can be a Day/Week/Month/Quarter/Year hierarchy, or use accounting periods. To learn more, go to [Comparing accounting periods using period formulas](bi-column-definitions.md#comparing-accounting-periods-using-period-formulas). 
7. On the **Dimensions** FastTab, you can define dimension filters for the report.  
8. You can preview the report in the area below the **Dimensions** FastTab.   

If you want to analyze your sustainability or statistical data, you can achieve this by setting up the **Row Definition**.  

To create or edit a row definition, follow the steps:

1. On the **Financial Reports** page, select the relevant financial report, and then choose the **Edit Row Definition** action. 
2. Set up rows as in the following steps.  

> [!NOTE]
> The **Row No.** field shows the first 10 characters of an identifier, such as an account number. If you add elements with identifiers that start with the same 10 characters, you'll have duplicates in the **Row No.** field. If needed, you can manually edit the identifiers after you insert the elements. The full identifiers are displayed in the **Totalling** field.

> [!NOTE]
> You can combine all **Totalling Types**, i.e. Posting accounts, Sust. Accounts, Statistical Account.

> [!NOTE]
> Row definitions aren't versioned. When you change a row definition, the old version is replaced and your changes will be saved to the database. 

### <a name="analyzing-sustainability-data"></a>Analyzing sustainability data

1. Enter the **Row No.** to identify your raw and add **Description** as a text that will appear on the financial report line. 
2. In the Totaling Type column, choose the **Sust. Accounts** option.   
3. In the Totaling field, choose one or more sustainability accounts using all applicable filters. 
4. In the **Amount Type** choose one of the options:   
   1. **CO2e** if you want to report CO2 equivalent value from the **CO2e Emission** field in the **Sustainability Ledger Entries**. 
   2. **Carbon Fee** if you want to report financial equivalent (carbon fee) from the **Carbon Fee** field on the **Sustainability Ledger Entries**. 
5. If you choose **Formula** as a **Totaling Type** you can use mathematical formulas in the **Totaling** column.  

### <a name="analyzing-statistical-data"></a>Analyzing statistical data

1. Enter the **Row No.** to identify your row and add **Description** as a text that will appear on the financial report line. 
2. In the **Totaling Type** column, choose the **Statistical Accounts** option.   
3. In the **Totaling** field, choose one or more sustainability accounts using all applicable filters. 
4. If you choose **Formula** as a **Totaling Type**, you can use mathematical formulas in the **Totaling** column.  

## <a name="see-also"></a>See also

[Sustainability Management Overview](finance-manage-sustainability.md)    
[Sustainability reports and analytics in Business Central](sustainability-reports.md)   
[Sustainability API](/dynamics365/business-central/dev-itpro/api-sustainability/sustainability-api?toc=/dynamics365/business-central/toc.json)    
[Prepare financial reporting](bi-how-work-account-schedule.md)    
[Row definition in Financial Reporting](bi-row-definitions.md)    
[Column definition in the Financial reporting](bi-column-definitions.md)    
[Finance](finance.md)    
[Work with [!INCLUDE[prod_short](includes/prod_short.md)]](ui-work-product.md)    

[!INCLUDE[footer-include](includes/footer-banner.md)]
