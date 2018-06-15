---
title: Configuring API Templates | Microsoft Docs
description: Describing the steps you must go through to configure API templates for Dynamics 365 Business Central.
services: project-madeira
documentationcenter: 
author: SusanneWindfeldPedersen
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: API templates, configuring templates
ms.date: 05/16/2018
ms.author: solsen
ms.translationtype: HT
ms.sourcegitcommit: ad1b888d475c0523c5a905e804a3f89ab4531b28
ms.openlocfilehash: 1695a6950dabc1b2f0a2f85ad9e0c565012c92e1
ms.contentlocale: en-au
ms.lasthandoff: 05/17/2018

---

# <a name="configuring-api-templates"></a>Configuring API Templates
The API library for [!INCLUDE[d365fin_md](includes/d365fin_md.md)] provides a simplified representation of the underlying entities. All the properties in the application are not exposed through the associated API. The **API Setup** window allows you to define templates that are used to populate empty properties on an entity when you create a POST action through the API. 

For example, if a configuration template is defined for the item entity, when a new item record is created through the items API, any properties for the new item that are not defined in the API call will be populated from the selected template. If, for example, no value is defined for the **Gen. Prod. Posting Group** field through the API, but a value is defined in the selected template, then the posting group value defined in the template will be applied to the new item. 

## <a name="setting-up-the-entity-template"></a>Setting up the Entity Template
To use templates with the API library, you must first set up and define properties for the templates. You can set up these templates in the **Configuration Templates** window. For more information, see [Prepare to Migrate Customer Data](admin-use-templates-to-prepare-customer-data-for-migration.md). 

## <a name="assign-the-template-to-an-api"></a>Assign the template to an API

To assign a template to an API, you must go through the following steps.

1. Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **API Setup**, and choose the related link.
2. Choose **New**, and then choose the **Order** value for the record.  
If there is more than one template selected for an API (Page ID), the templates are applied in the order defined in the **Order** column.   
When each template is applied, field values defined in the template are only applied to fields that have not already had a value defined, either explicitly in the API, or in a previously applied template in the order. 
3. Select a **Page ID** value.  
This is the page for the API to which the template will be applied. The **Page ID** lookup provides a list of all APIs available in the library.
4. Select a value in the **Template Code** field.  
The template code is the code for the template that was defined in the **Configuration Templates** window. The template values defined are applied to the API. 
5. In the **Conditions** field, specify which template should be applied.  
The defined template is applied to a new record created through the API if, and only if, the conditions defined in the **Conditions** field are met by the values already defined for the new instance of the entity.

## <a name="see-also"></a>See Also
[API Documentation](/dynamics-nav/fin-graph)  
[Developing Connect Apps for [!INCLUDE[d365fin_md](includes/d365fin_md.md)]](/dynamics365/business-central/dev-itpro/developer/devenv-develop-connect-apps)  
[Enabling the APIs](/dynamics-nav/enabling-apis-for-dynamics-nav)  
[Endpoints for the APIs](/dynamics-nav/endpoints-apis-for-dynamics)  
[Setting Up a Company with RapidStart Services](admin-set-up-a-company-with-rapidstart.md)  
[Administration](admin-setup-and-administration.md)