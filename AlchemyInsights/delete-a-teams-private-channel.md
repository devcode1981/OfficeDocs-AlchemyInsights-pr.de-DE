---
title: Löschen eines privaten Teams-Kanals
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/24/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3781"
- "9001223"
ms.openlocfilehash: 2ee998f0c70973645c273a2a6609af2420a4f74b
ms.sourcegitcommit: b10cea11b4975354b91193327b58aa4740d34833
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/28/2020
ms.locfileid: "45431616"
---
# <a name="delete-a-teams-private-channel"></a><span data-ttu-id="d829d-102">Löschen eines privaten Teams-Kanals</span><span class="sxs-lookup"><span data-stu-id="d829d-102">Delete a Teams private channel</span></span>

<span data-ttu-id="d829d-103">Microsoft ist sich eines Problems beim Löschen eines privaten Teams-Kanals bewusst, wenn Sie für die zugrunde liegende SharePoint-Site SharePoint-Aufbewahrungsrichtlinien aktiviert haben.</span><span class="sxs-lookup"><span data-stu-id="d829d-103">Microsoft is aware of an issue deleting a Teams private channel if you have SharePoint Retention Policies enabled for the underlying SharePoint site.</span></span> <span data-ttu-id="d829d-104">Microsoft arbeitet derzeit an einer Lösung.</span><span class="sxs-lookup"><span data-stu-id="d829d-104">Microsoft is working on a fix.</span></span> <span data-ttu-id="d829d-105">In der Zwischenzeit können Sie folgenden Problemumgehungen verwenden, um den privaten Kanal zu löschen.</span><span class="sxs-lookup"><span data-stu-id="d829d-105">In the meantime, you can use the following workarounds to delete the private channel.</span></span>

<span data-ttu-id="d829d-106">**Schließen Sie die Team-/Websitesammlung aus der SharePoint-Aufbewahrungsrichtlinie aus.**</span><span class="sxs-lookup"><span data-stu-id="d829d-106">**Exclude the Team/site collection from the Sharepoint retention policy.**</span></span>

1. <span data-ttu-id="d829d-107">Wechseln Sie zum Office 365-Verwaltungsportal, und wählen Sie im linken Navigationsbereich **Alle anzeigen** aus.</span><span class="sxs-lookup"><span data-stu-id="d829d-107">Go to the Office 365 admin portal, and select **Show all** in the left navigation pane.</span></span>
2. <span data-ttu-id="d829d-108">Wechseln Sie unter **Admin Center** zu **Security & Compliance** > **Verhinderung von Datenverlust** > **Richtlinie**.</span><span class="sxs-lookup"><span data-stu-id="d829d-108">Under **Admin centers**, go to **Security & Compliance** > **Data Loss Prevention** > **Policy**.</span></span>
3. <span data-ttu-id="d829d-109">Identifizieren Sie eine Richtlinie, die für SharePoint-Sites gilt, und ändern Sie die Richtlinie so, dass die SharePoint-Site für das Team, das den privaten Kanal enthält, NICHT unter der Aufbewahrungsrichtlinie enthalten ist.</span><span class="sxs-lookup"><span data-stu-id="d829d-109">Identify any policy that applies to Sharepoint sites, and modify the policy so the Sharepoint site for the Team containing the private channel is NOT included under the retention policy.</span></span>
4. <span data-ttu-id="d829d-110">Speichern Sie die Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="d829d-110">Save the policy.</span></span>
    <span data-ttu-id="d829d-111">Es kann bis zu 24 Stunden dauern, bis Richtlinieneinstellungen wirksam werden.</span><span class="sxs-lookup"><span data-stu-id="d829d-111">It can take up to 24 hours for policy settings to take effect.</span></span>
    <span data-ttu-id="d829d-112">Nachdem die Site ausgeschlossen wurde, können Sie den privaten Kanal löschen.</span><span class="sxs-lookup"><span data-stu-id="d829d-112">After the site has been excluded, you can delete the private channel.</span></span>  
    
<span data-ttu-id="d829d-113">***Möglicherweise können*** Sie den privaten Kanal löschen, indem Sie Microsoft Teams auf Ihrem Android-Gerät verwenden.</span><span class="sxs-lookup"><span data-stu-id="d829d-113">You  ***might*** be able to delete the private channel by using Microsoft Teams on your Android device.</span></span> 

<span data-ttu-id="d829d-114">Verwandte SharePoint-Informationen finden Sie unter [Elemente in SharePoint Online oder OneDrive for Business können nicht gelöscht werden](https://docs.microsoft.com/alchemyinsights/retention-policy-ediscovery-hold).</span><span class="sxs-lookup"><span data-stu-id="d829d-114">For related SharePoint information, see [Unable to delete items in SharePoint Online or OneDrive for Business](https://docs.microsoft.com/alchemyinsights/retention-policy-ediscovery-hold).</span></span>