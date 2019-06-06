---
title: Problembehandlung bei Zugriff verweigerten Nachrichten
ms.author: kirks
author: Techwriter40
ms.date: 6/29/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 5958ad06ca905f713b5f56aa5c536e95a485f01c
ms.sourcegitcommit: 241e21b6da226563bf70bdb1f5bad3d91c38cd2c
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/05/2019
ms.locfileid: "34735737"
---
# <a name="troubleshoot-access-denied-messages"></a><span data-ttu-id="d220a-102">Problembehandlung bei Zugriff verweigerten Nachrichten</span><span class="sxs-lookup"><span data-stu-id="d220a-102">Troubleshoot Access Denied messages</span></span>

<span data-ttu-id="d220a-103">Wenn Sie beim Versuch, eine SharePoint Online-Website zu durchsuchen, eine Meldung zum Zugriff verweigert erhalten, lesen Sie die folgenden Artikel.</span><span class="sxs-lookup"><span data-stu-id="d220a-103">If you are receiving an access denied message when attempting to browse a Sharepoint Online site, please see the below articles.</span></span>

## <a name="add-and-license-the-user"></a><span data-ttu-id="d220a-104">Hinzufügen und lizenzieren des Benutzers</span><span class="sxs-lookup"><span data-stu-id="d220a-104">Add and License the user</span></span>

<span data-ttu-id="d220a-105">Stellen Sie sicher, dass Sie [Benutzern in Office 365 für Unternehmen Lizenzen zuweisen](https://docs.microsoft.com/en-us/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span><span class="sxs-lookup"><span data-stu-id="d220a-105">Ensure that you [Assign licenses to users in Office 365 for business](https://docs.microsoft.com/en-us/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span></span>

<span data-ttu-id="d220a-106">Zuweisen von Berechtigungen</span><span class="sxs-lookup"><span data-stu-id="d220a-106">Assign Permissions</span></span>

<span data-ttu-id="d220a-107">Wenn dem Benutzer eine SharePoint-Lizenz zugewiesen wurde und weiterhin eine Nachricht mit Zugriff verweigert erhalten wird, stellen Sie sicher, dass Ihnen die [entsprechende Berechtigungsstufe zugewiesen](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels)ist.</span><span class="sxs-lookup"><span data-stu-id="d220a-107">If the user has been assigned a Sharepoint license and is still receiving an access denied message, please ensure they have the [appropriate permission level assigned](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels).</span></span>

<span data-ttu-id="d220a-108">Verwenden der Access-Anforderungsfunktion in Frage stellen</span><span class="sxs-lookup"><span data-stu-id="d220a-108">Consider using the access request feature</span></span>

<span data-ttu-id="d220a-109">Mit der [Zugriffs Anforderungs](https://support.office.com/en-us/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) Funktion können Benutzer Zugriff auf Inhalte anfordern, für die Sie derzeit keine Berechtigung haben.</span><span class="sxs-lookup"><span data-stu-id="d220a-109">The [access request](https://support.office.com/en-us/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) feature allows people to request access to content that they do not currently have permission to see.</span></span> 

<span data-ttu-id="d220a-110">Benutzerdefiniertes Skript zulassen verursacht möglicherweise Zugriffs Verweigerungs Probleme</span><span class="sxs-lookup"><span data-stu-id="d220a-110">Allow custom script may cause access denied issues</span></span>

<span data-ttu-id="d220a-111">Es gibt bestimmte Szenarien, in denen das Feature "benutzerdefiniertes Skript zulassen" möglicherweise einen Zugriff verweigert darstellt.</span><span class="sxs-lookup"><span data-stu-id="d220a-111">There are certain scenarios where the "Allow custom script" feature may be presenting an access denied.</span></span> <span data-ttu-id="d220a-112">Eine Liste der betroffenen Features, Sicherheitsüberlegungen und die Möglichkeit, das Feature zu deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="d220a-112">For a list of features affected, security considerations and the ability to disable the feature.</span></span> <span data-ttu-id="d220a-113">Bitte besuchen, [zulassen oder verhindern, dass benutzerdefiniertes Skript](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script)</span><span class="sxs-lookup"><span data-stu-id="d220a-113">Please visit , [Allow or prevent custom script](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script)</span></span>

<span data-ttu-id="d220a-114">Hinweis: Wenn eine OneDrive-oder SharePoint-Website nicht für mehrere Benutzer verfügbar ist, die zuvor Zugriff hatten, ist möglicherweise ein vorübergehendes Dienst Problem aufgetreten.</span><span class="sxs-lookup"><span data-stu-id="d220a-114">Note: If a OneDrive or SharePoint site is not available to multiple users who previously had access, there may be a temporary service issue.</span></span> <span data-ttu-id="d220a-115">[Überprüfen Sie das Dienst Integritäts Dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="d220a-115">[Check the service health dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span></span>


  
