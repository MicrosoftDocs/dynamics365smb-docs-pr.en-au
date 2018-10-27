---
title: Track User Activity in a Change Log| Microsoft Docs
description: You can activate a user log so that you have a history of any changes made to data in tracked tables.
author: edupont04
ms.service: dynamics365-business-central
ms.topic: get-started-article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: user log, user activity, tracking
ms.date: 10/01/2018
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: cce3a3a8331d8f1ac6665d9b9a9908b172cfecaa
ms.openlocfilehash: ab9696a3cc14970def764b2741d50dbcd5207460
ms.contentlocale: en-au
ms.lasthandoff: 10/27/2018

---
# <a name="logging-changes-in-business-central"></a><span data-ttu-id="d13ad-103">Logging Changes in Business Central</span><span class="sxs-lookup"><span data-stu-id="d13ad-103">Logging Changes in Business Central</span></span>
<span data-ttu-id="d13ad-104">You can enable the change log in [!INCLUDE[d365fin](includes/d365fin_md.md)] so you have a history of activities.</span><span class="sxs-lookup"><span data-stu-id="d13ad-104">You can enable the change log in [!INCLUDE[d365fin](includes/d365fin_md.md)] so you have a history of activities.</span></span> <span data-ttu-id="d13ad-105">The log is based on changes that are made to data in the tables that you track. In the change log, entries are chronologically ordered and show changes that are made to the fields on the specified tables.</span><span class="sxs-lookup"><span data-stu-id="d13ad-105">The log is based on changes that are made to data in the tables that you track. In the change log, entries are chronologically ordered and show changes that are made to the fields on the specified tables.</span></span> <span data-ttu-id="d13ad-106">The change log collects all changes that are made to the table.</span><span class="sxs-lookup"><span data-stu-id="d13ad-106">The change log collects all changes that are made to the table.</span></span>  

## <a name="working-with-the-change-log"></a><span data-ttu-id="d13ad-107">Working with the Change Log</span><span class="sxs-lookup"><span data-stu-id="d13ad-107">Working with the Change Log</span></span>
<span data-ttu-id="d13ad-108">A common problem in many financial systems is to locate the origin of errors and changes in data.</span><span class="sxs-lookup"><span data-stu-id="d13ad-108">A common problem in many financial systems is to locate the origin of errors and changes in data.</span></span> <span data-ttu-id="d13ad-109">It could be anything from an incorrect customer telephone number to an incorrect posting to the general ledger.</span><span class="sxs-lookup"><span data-stu-id="d13ad-109">It could be anything from an incorrect customer telephone number to an incorrect posting to the general ledger.</span></span> <span data-ttu-id="d13ad-110">The change log lets you track all direct modifications a user makes to data in the database.</span><span class="sxs-lookup"><span data-stu-id="d13ad-110">The change log lets you track all direct modifications a user makes to data in the database.</span></span> <span data-ttu-id="d13ad-111">You must specify each table and field that you want the system to log, and then you must activate the change log.</span><span class="sxs-lookup"><span data-stu-id="d13ad-111">You must specify each table and field that you want the system to log, and then you must activate the change log.</span></span>  

<span data-ttu-id="d13ad-112">You activate and deactivate the change log in the **Change Log Setup** window.</span><span class="sxs-lookup"><span data-stu-id="d13ad-112">You activate and deactivate the change log in the **Change Log Setup** window.</span></span> <span data-ttu-id="d13ad-113">When you activate or deactivate the change log, this activity is logged, so you can always see which user deactivated or reactivated the change log.</span><span class="sxs-lookup"><span data-stu-id="d13ad-113">When you activate or deactivate the change log, this activity is logged, so you can always see which user deactivated or reactivated the change log.</span></span> <span data-ttu-id="d13ad-114">This cannot be turned off.</span><span class="sxs-lookup"><span data-stu-id="d13ad-114">This cannot be turned off.</span></span>  

<span data-ttu-id="d13ad-115">In the **Change Log Setup** window, if you choose the **Tables** action, you can specify which tables you want to track changes for, and which changes to track. [!INCLUDE[d365fin](includes/d365fin_md.md)] also tracks a number of system tables.</span><span class="sxs-lookup"><span data-stu-id="d13ad-115">In the **Change Log Setup** window, if you choose the **Tables** action, you can specify which tables you want to track changes for, and which changes to track. [!INCLUDE[d365fin](includes/d365fin_md.md)] also tracks a number of system tables.</span></span>

<span data-ttu-id="d13ad-116">After you have set up the change log, activated it, and made a change to data, you can view and filter the changes in the **Change Log Entries** window.</span><span class="sxs-lookup"><span data-stu-id="d13ad-116">After you have set up the change log, activated it, and made a change to data, you can view and filter the changes in the **Change Log Entries** window.</span></span> <span data-ttu-id="d13ad-117">If you want to delete entries, you can do that in the **Delete Change Log Entries** window, where you can set filters based on dates and time.</span><span class="sxs-lookup"><span data-stu-id="d13ad-117">If you want to delete entries, you can do that in the **Delete Change Log Entries** window, where you can set filters based on dates and time.</span></span>  

## <a name="see-also"></a><span data-ttu-id="d13ad-118">See Also</span><span class="sxs-lookup"><span data-stu-id="d13ad-118">See Also</span></span>
[<span data-ttu-id="d13ad-119">Changing Basic Settings</span><span class="sxs-lookup"><span data-stu-id="d13ad-119">Changing Basic Settings</span></span>](ui-change-basic-settings.md)  
[<span data-ttu-id="d13ad-120">Sorting</span><span class="sxs-lookup"><span data-stu-id="d13ad-120">Sorting</span></span>](ui-sorting.md)  
[<span data-ttu-id="d13ad-121">Using Search for Page or Report</span><span class="sxs-lookup"><span data-stu-id="d13ad-121">Using Search for Page or Report</span></span>](ui-search.md)  
<span data-ttu-id="d13ad-122">[Managing Users and Permissions](ui-how-users-permissions.md)  </span><span class="sxs-lookup"><span data-stu-id="d13ad-122">[Managing Users and Permissions](ui-how-users-permissions.md)  </span></span>  
<span data-ttu-id="d13ad-123">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="d13ad-123">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

