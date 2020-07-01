---
title: Erstellen einer Organisationsbeziehung, um es Ihren Benutzern zu ermöglichen, mit einer anderen Organisation zusammenzuarbeiten
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3800014"
- "898"
ms.openlocfilehash: 2c6cd6a178c6e012bfe1c8d769b037168ffa3254
ms.sourcegitcommit: 722e9a0ed058cb1eab2dd053be2418b60f7d4aac
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/23/2020
ms.locfileid: "44854015"
---
# <a name="create-an-organization-relationship-to-allow-your-users-to-collaborate-with-another-organization"></a><span data-ttu-id="61343-102">Erstellen einer Organisationsbeziehung, um es Ihren Benutzern zu ermöglichen, mit einer anderen Organisation zusammenzuarbeiten</span><span class="sxs-lookup"><span data-stu-id="61343-102">Create an Organization Relationship to allow your users to collaborate with another organization</span></span>

1. <span data-ttu-id="61343-103">Wechseln Sie vom Microsoft 365 Admin Center-Dashboards zu **Admin** > **Exchange**.</span><span class="sxs-lookup"><span data-stu-id="61343-103">From the Microsoft 365 admin center dashboard, go to **Admin** > **Exchange**.</span></span>
2. <span data-ttu-id="61343-104">Wechseln Sie zu **Organisation** > **Freigabe**.</span><span class="sxs-lookup"><span data-stu-id="61343-104">Go to **organization** > **sharing**.</span></span>
3. <span data-ttu-id="61343-105">Klicken Sie unterhalb von **Organisationsfreigabe** auf **Neu**.</span><span class="sxs-lookup"><span data-stu-id="61343-105">Under **Organization Sharing**, click **New** .</span></span>
4. <span data-ttu-id="61343-106">Geben Sie im Bereich **Neue Organisationsbeziehung** im Feld **Beziehungsname** einen Anzeigenamen für die Organisationsbeziehung ein.</span><span class="sxs-lookup"><span data-stu-id="61343-106">In **new organization relationship**, in the **Relationship name** box, type a friendly name for the organization relationship.</span></span>
5. <span data-ttu-id="61343-107">In the **Domains to share with** box, type the domain for the external Office 365 or Exchange on-premises organization you want to let see your calendars.</span><span class="sxs-lookup"><span data-stu-id="61343-107">In the **Domains to share with** box, type the domain for the external Office 365 or Exchange on-premises organization you want to let see your calendars.</span></span> <span data-ttu-id="61343-108">If you need to enter more than one domain, separate the domain names with a comma.</span><span class="sxs-lookup"><span data-stu-id="61343-108">If you need to enter more than one domain, separate the domain names with a comma.</span></span> <span data-ttu-id="61343-109">For example, contoso.com, service.contoso.com.</span><span class="sxs-lookup"><span data-stu-id="61343-109">For example, contoso.com, service.contoso.com.</span></span>
6. <span data-ttu-id="61343-110">Select the **Enable calendar free/busy information sharing** check box to turn on calendar sharing with the domains you listed.</span><span class="sxs-lookup"><span data-stu-id="61343-110">Select the **Enable calendar free/busy information sharing** check box to turn on calendar sharing with the domains you listed.</span></span> <span data-ttu-id="61343-111">Set the sharing level for calendar free/busy information and set which users can share calendar free/busy information.</span><span class="sxs-lookup"><span data-stu-id="61343-111">Set the sharing level for calendar free/busy information and set which users can share calendar free/busy information.</span></span>  

<span data-ttu-id="61343-112">Wählen Sie eine der folgenden Optionen zur Festlegung der Frei/Gebucht-Zugriffsebene:</span><span class="sxs-lookup"><span data-stu-id="61343-112">To set the free/busy access level, select one of the following:</span></span>

- <span data-ttu-id="61343-113">**Frei/Gebucht-Kalenderinformationen nur mit Zeit**</span><span class="sxs-lookup"><span data-stu-id="61343-113">**Calendar free/busy information with time only**</span></span>
- <span data-ttu-id="61343-114">**Frei/Gebucht-Kalenderinformationen mit Zeit, Betreff und Ort**</span><span class="sxs-lookup"><span data-stu-id="61343-114">**Calendar free/busy with time, subject, and location**</span></span>  

 <span data-ttu-id="61343-115">Um festzulegen, welche Benutzer die Frei/Gebucht-Kalenderinformationen freigeben können, wählen Sie eine der folgenden Optionen aus:</span><span class="sxs-lookup"><span data-stu-id="61343-115">To set which users will share calendar free/busy information, select one of the following:</span></span>

- <span data-ttu-id="61343-116">**Jeder in Ihrer Organisation**</span><span class="sxs-lookup"><span data-stu-id="61343-116">**Everyone in your organization**</span></span>
- <span data-ttu-id="61343-117">**Eine bestimmte Sicherheitsgruppe**</span><span class="sxs-lookup"><span data-stu-id="61343-117">**A specified security group**</span></span>  

<span data-ttu-id="61343-118">Klicken Sie auf **Durchsuchen**, um eine Sicherheitsgruppe aus der Liste auszuwählen, und klicken Sie dann auf **OK**.</span><span class="sxs-lookup"><span data-stu-id="61343-118">Click **browse** to pick the security group from a list, then click **ok**.</span></span>

<span data-ttu-id="61343-119">Klicken Sie auf **Speichern**, um die Organisationsbeziehung zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="61343-119">Click **save** to create the organization relationship.</span></span>  

<span data-ttu-id="61343-120">**Hinweis:** Bei mandantenübergreifenden Konfigurationen werden persönliche Kontakte für die Frei/Gebucht-Suche nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="61343-120">**Note:** Cross-tenant configurations do not support personal contacts for free/busy lookup.</span></span> <span data-ttu-id="61343-121">Die Kontakte müssen in die globale Adressliste aufgenommen werden, damit die Frei/Gebucht-Suche durchgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="61343-121">Contacts must be included in the global address list for free/busy lookup to work.</span></span>

<span data-ttu-id="61343-122">**Für vollständige Informationen zu diesem Thema lesen Sie:**</span><span class="sxs-lookup"><span data-stu-id="61343-122">**For full understanding of this topic please read:**</span></span>

- [<span data-ttu-id="61343-123">Erstellen einer Organisationsbeziehung in Exchange Online</span><span class="sxs-lookup"><span data-stu-id="61343-123">Create an organization relationship in Exchange Online</span></span>](https://docs.microsoft.com/exchange/sharing/organization-relationships/create-an-organization-relationship)
- [<span data-ttu-id="61343-124">Ändern einer Organisationsbeziehung in Exchange Online</span><span class="sxs-lookup"><span data-stu-id="61343-124">Modify an organization relationship in Exchange Online</span></span>](https://docs.microsoft.com/exchange/sharing/organization-relationships/modify-an-organization-relationship)
- [<span data-ttu-id="61343-125">Entfernen einer Organisationsbeziehung in Exchange Online</span><span class="sxs-lookup"><span data-stu-id="61343-125">Remove an organization relationship in Exchange Online</span></span>](https://docs.microsoft.com/exchange/sharing/organization-relationships/remove-an-organization-relationship)