---
title: Managing Microsoft Teams Integration with Business Central| Microsoft Docs
description: Manage Business Central integration with Microsoft Teams.
author: jswymer
ms.service: dynamics365-business-central
ms.topic: get-started-article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: Teams, MS Teams, Microsoft Teams, Skype, Link, Microsoft 365, collaborate, collaboration, teamwork
ms.date: 10/08/2020
ms.author: jswymer
ms.openlocfilehash: 3c04dfb2f77eba906b2567ca9438849e1cc20861
ms.sourcegitcommit: 4bca699d2a5ce182eb5572d72fac4fb478c4f293
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 10/12/2020
ms.locfileid: "3989367"
---
# <a name="managing-microsoft-teams-integration-with-business-central"></a><span data-ttu-id="f5fdb-103">Managing Microsoft Teams Integration with Business Central</span><span class="sxs-lookup"><span data-stu-id="f5fdb-103">Managing Microsoft Teams Integration with Business Central</span></span>

[!INCLUDE [teams_preview.md](includes/teams_preview.md)]

<span data-ttu-id="f5fdb-104">This article provides an overview of what you can do as an administrator to control Microsoft Teams integration with [!INCLUDE [prodshort](includes/prodshort.md)].</span><span class="sxs-lookup"><span data-stu-id="f5fdb-104">This article provides an overview of what you can do as an administrator to control Microsoft Teams integration with [!INCLUDE [prodshort](includes/prodshort.md)].</span></span>

## <a name="in-microsoft-teams"></a><span data-ttu-id="f5fdb-105">In Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="f5fdb-105">In Microsoft Teams</span></span>

### <a name="minimum-requirements"></a><span data-ttu-id="f5fdb-106">Minimum requirements</span><span class="sxs-lookup"><span data-stu-id="f5fdb-106">Minimum requirements</span></span>

<span data-ttu-id="f5fdb-107">This section describes the minimum requirements for the [!INCLUDE [prodshort](includes/prodshort.md)] app features to work in Teams.</span><span class="sxs-lookup"><span data-stu-id="f5fdb-107">This section describes the minimum requirements for the [!INCLUDE [prodshort](includes/prodshort.md)] app features to work in Teams.</span></span>

- <span data-ttu-id="f5fdb-108">Required licences</span><span class="sxs-lookup"><span data-stu-id="f5fdb-108">Required licenses</span></span>

    <span data-ttu-id="f5fdb-109">This table gives you an overview of the licences needed for the [!INCLUDE [prodshort](includes/prodshort.md)] app features to work in Teams.</span><span class="sxs-lookup"><span data-stu-id="f5fdb-109">This table gives you an overview of the licenses needed for the [!INCLUDE [prodshort](includes/prodshort.md)] app features to work in Teams.</span></span>

    |<span data-ttu-id="f5fdb-110">What</span><span class="sxs-lookup"><span data-stu-id="f5fdb-110">What</span></span>|<span data-ttu-id="f5fdb-111">Teams licence</span><span class="sxs-lookup"><span data-stu-id="f5fdb-111">Teams license</span></span>|<span data-ttu-id="f5fdb-112">Business Central licence</span><span class="sxs-lookup"><span data-stu-id="f5fdb-112">Business Central license</span></span>|
    |----|---|---|
    |<span data-ttu-id="f5fdb-113">Paste a link to a [!INCLUDE [prodshort](includes/prodshort.md)] record into a conversation, and send it as a card.</span><span class="sxs-lookup"><span data-stu-id="f5fdb-113">Paste a link to a [!INCLUDE [prodshort](includes/prodshort.md)] record into a conversation, and send it as a card.</span></span>|<span data-ttu-id="f5fdb-114">![check mark](media/check.png "cheque")</span><span class="sxs-lookup"><span data-stu-id="f5fdb-114">![check mark](media/check.png "check")</span></span>|<span data-ttu-id="f5fdb-115">![check mark](media/check.png "cheque")</span><span class="sxs-lookup"><span data-stu-id="f5fdb-115">![check mark](media/check.png "check")</span></span>|
    |<span data-ttu-id="f5fdb-116">View a card of a [!INCLUDE [prodshort](includes/prodshort.md)] record in a conversation.</span><span class="sxs-lookup"><span data-stu-id="f5fdb-116">View a card of a [!INCLUDE [prodshort](includes/prodshort.md)] record in a conversation.</span></span>|<span data-ttu-id="f5fdb-117">![check mark](media/check.png "cheque")</span><span class="sxs-lookup"><span data-stu-id="f5fdb-117">![check mark](media/check.png "check")</span></span>||
    |<span data-ttu-id="f5fdb-118">View more details of card for a [!INCLUDE [prodshort](includes/prodshort.md)] record in a conversation.</span><span class="sxs-lookup"><span data-stu-id="f5fdb-118">View more details of card for a [!INCLUDE [prodshort](includes/prodshort.md)] record in a conversation.</span></span>|<span data-ttu-id="f5fdb-119">![check mark](media/check.png "cheque")</span><span class="sxs-lookup"><span data-stu-id="f5fdb-119">![check mark](media/check.png "check")</span></span>|<span data-ttu-id="f5fdb-120">![check mark](media/check.png "cheque")</span><span class="sxs-lookup"><span data-stu-id="f5fdb-120">![check mark](media/check.png "check")</span></span>|

- <span data-ttu-id="f5fdb-121">Allow URL previews</span><span class="sxs-lookup"><span data-stu-id="f5fdb-121">Allow URL previews</span></span>

    <span data-ttu-id="f5fdb-122">**Allow URL previews** policy setting must be turned on.</span><span class="sxs-lookup"><span data-stu-id="f5fdb-122">**Allow URL previews** policy setting must be turned on.</span></span> <span data-ttu-id="f5fdb-123">Otherwise, a card can't be generated for Business Central links pasted into a Teams conversation.</span><span class="sxs-lookup"><span data-stu-id="f5fdb-123">Otherwise, a card can't be generated for Business Central links pasted into a Teams conversation.</span></span> <span data-ttu-id="f5fdb-124">For more information about this setting, see [Manage messaging policies in Teams](/microsoftteams/messaging-policies-in-teams).</span><span class="sxs-lookup"><span data-stu-id="f5fdb-124">For more information about this setting, see [Manage messaging policies in Teams](/microsoftteams/messaging-policies-in-teams).</span></span>

### <a name="managing-the-business-central-app-optional"></a><span data-ttu-id="f5fdb-125">Managing the Business Central app (optional)</span><span class="sxs-lookup"><span data-stu-id="f5fdb-125">Managing the Business Central app (optional)</span></span>

<span data-ttu-id="f5fdb-126">As a Teams administrator, you can manage all apps for your organisation, including the [!INCLUDE [prodshort](includes/prodshort.md)] app.</span><span class="sxs-lookup"><span data-stu-id="f5fdb-126">As a Teams administrator, you can manage all apps for your organization, including the [!INCLUDE [prodshort](includes/prodshort.md)] app.</span></span> <span data-ttu-id="f5fdb-127">You can approve or install the [!INCLUDE [prodshort](includes/prodshort.md)] app for your organisation, block user's from installing the app and more.</span><span class="sxs-lookup"><span data-stu-id="f5fdb-127">You can approve or install the [!INCLUDE [prodshort](includes/prodshort.md)] app for your organization, block user's from installing the app, and more.</span></span>

<span data-ttu-id="f5fdb-128">For more information, see the following articles in the Microsoft Teams documentation:</span><span class="sxs-lookup"><span data-stu-id="f5fdb-128">For more information, see the following articles in the Microsoft Teams documentation:</span></span>

- [<span data-ttu-id="f5fdb-129">Manage your apps in the Microsoft Teams admin centre</span><span class="sxs-lookup"><span data-stu-id="f5fdb-129">Manage your apps in the Microsoft Teams admin center</span></span>](https://docs.microsoft.com/MicrosoftTeams/manage-apps)
- [<span data-ttu-id="f5fdb-130">Manage app setup policies in Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="f5fdb-130">Manage app setup policies in Microsoft Teams</span></span>](https://docs.microsoft.com/microsoftteams/teams-app-setup-policies)

## <a name="in-prodshort"></a><span data-ttu-id="f5fdb-131">In [!INCLUDE [prodshort](includes/prodshort.md)]</span><span class="sxs-lookup"><span data-stu-id="f5fdb-131">In [!INCLUDE [prodshort](includes/prodshort.md)]</span></span>

### <a name="minimum-requirements"></a><span data-ttu-id="f5fdb-132">Minimum requirements</span><span class="sxs-lookup"><span data-stu-id="f5fdb-132">Minimum requirements</span></span>

- <span data-ttu-id="f5fdb-133">[!INCLUDE [prodshort](includes/prodshort.md)] version:</span><span class="sxs-lookup"><span data-stu-id="f5fdb-133">[!INCLUDE [prodshort](includes/prodshort.md)] version:</span></span>

    <span data-ttu-id="f5fdb-134">[!INCLUDE [prodshort](includes/prodshort.md)] 2020 release wave 2 (version 17) or later.</span><span class="sxs-lookup"><span data-stu-id="f5fdb-134">[!INCLUDE [prodshort](includes/prodshort.md)] 2020 release wave 2 (version 17) or later.</span></span> <span data-ttu-id="f5fdb-135">Teams integration is only supported for [!INCLUDE [prodshort](includes/prodshort.md)] online; not on-premises.</span><span class="sxs-lookup"><span data-stu-id="f5fdb-135">Teams integration is only supported for [!INCLUDE [prodshort](includes/prodshort.md)] online; not on-premises.</span></span>

- <span data-ttu-id="f5fdb-136">Codeunit **2718 Page Summary Provider** is published as a web service:</span><span class="sxs-lookup"><span data-stu-id="f5fdb-136">Codeunit **2718 Page Summary Provider** is published as a web service:</span></span>

    <span data-ttu-id="f5fdb-137">This codeunit is published as a web service by default.</span><span class="sxs-lookup"><span data-stu-id="f5fdb-137">This codeunit is published as a web service by default.</span></span> <span data-ttu-id="f5fdb-138">The codeunit is part of the [!INCLUDE [prodshort](includes/prodshort.md)] system application.</span><span class="sxs-lookup"><span data-stu-id="f5fdb-138">The codeunit is part of the [!INCLUDE [prodshort](includes/prodshort.md)] system application.</span></span> <span data-ttu-id="f5fdb-139">It's used to get the field data for a [!INCLUDE [prodshort](includes/prodshort.md)] page added to a Teams conversation.</span><span class="sxs-lookup"><span data-stu-id="f5fdb-139">It's used to get the field data for a [!INCLUDE [prodshort](includes/prodshort.md)] page added to a Teams conversation.</span></span> 

- <span data-ttu-id="f5fdb-140">User permissions:</span><span class="sxs-lookup"><span data-stu-id="f5fdb-140">User permissions:</span></span>

    <span data-ttu-id="f5fdb-141">For the most part, the pages and data that users can view and edit in a Teams conversation is controlled by their permissions in [!INCLUDE [prodshort](includes/prodshort.md)].</span><span class="sxs-lookup"><span data-stu-id="f5fdb-141">For the most part, the pages and data that users can view and edit in a Teams conversation is controlled by their permissions in [!INCLUDE [prodshort](includes/prodshort.md)].</span></span>
    
    - <span data-ttu-id="f5fdb-142">To paste a [!INCLUDE [prodshort](includes/prodshort.md)] link into a Teams conversation and have it expand into a card, users must have at least read permission on the page and its data.</span><span class="sxs-lookup"><span data-stu-id="f5fdb-142">To paste a [!INCLUDE [prodshort](includes/prodshort.md)] link into a Teams conversation and have it expand into a card, users must have at least read permission on the page and its data.</span></span>
    - <span data-ttu-id="f5fdb-143">Once a card is submitted into a conversation, any user in that conversation can view that card without permission to Business Central.</span><span class="sxs-lookup"><span data-stu-id="f5fdb-143">Once a card is submitted into a conversation, any user in that conversation can view that card without permission to Business Central.</span></span>
    - <span data-ttu-id="f5fdb-144">To view more details for a card or open the record in [!INCLUDE [prodshort](includes/prodshort.md)], users must have read permission on the page and its data.</span><span class="sxs-lookup"><span data-stu-id="f5fdb-144">To view more details for a card or open the record in [!INCLUDE [prodshort](includes/prodshort.md)], users must have read permission on the page and its data.</span></span>
    - <span data-ttu-id="f5fdb-145">To change data, user's need modify permissions.</span><span class="sxs-lookup"><span data-stu-id="f5fdb-145">To change data, user's need modify permissions.</span></span>
    
    <span data-ttu-id="f5fdb-146">For information about permissions, see [Assign Permissions to Users and Groups](ui-define-granular-permissions.md).</span><span class="sxs-lookup"><span data-stu-id="f5fdb-146">For information about permissions, see [Assign Permissions to Users and Groups](ui-define-granular-permissions.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="f5fdb-147">See Also</span><span class="sxs-lookup"><span data-stu-id="f5fdb-147">See Also</span></span>
[<span data-ttu-id="f5fdb-148">Business Central and Microsoft Teams Integration Overview</span><span class="sxs-lookup"><span data-stu-id="f5fdb-148">Business Central and Microsoft Teams Integration Overview</span></span>](across-teams-overview.md)  
<span data-ttu-id="f5fdb-149">[Install the [!INCLUDE [prodshort](includes/prodshort.md)] App for Microsoft Teams](across-install-app-for-teams.md)</span><span class="sxs-lookup"><span data-stu-id="f5fdb-149">[Install the [!INCLUDE [prodshort](includes/prodshort.md)] App for Microsoft Teams](across-install-app-for-teams.md)</span></span>  
[<span data-ttu-id="f5fdb-150">Developing for Teams Integration</span><span class="sxs-lookup"><span data-stu-id="f5fdb-150">Developing for Teams Integration</span></span>](/dynamics365/business-central/dev-itpro/developer/devenv-develop-for-teams)  
[<span data-ttu-id="f5fdb-151">Getting Started</span><span class="sxs-lookup"><span data-stu-id="f5fdb-151">Getting Started</span></span>](product-get-started.md)  

## [!INCLUDE[d365fin](includes/free_trial_md.md)]  