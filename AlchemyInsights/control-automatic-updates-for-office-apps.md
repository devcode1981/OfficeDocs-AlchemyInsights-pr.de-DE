---
title: Steuern automatischer Updates für Office-Apps
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
- "1743"
- "9000140"
ms.openlocfilehash: 5c56c3adcc9a06db43d4df6f367657cb8ff0c8c8
ms.sourcegitcommit: b10cea11b4975354b91193327b58aa4740d34833
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/28/2020
ms.locfileid: "45431619"
---
# <a name="control-automatic-updates-for-office-apps"></a><span data-ttu-id="a0f13-102">Steuern automatischer Updates für Office-Apps</span><span class="sxs-lookup"><span data-stu-id="a0f13-102">Control automatic updates for Office Apps</span></span>

<span data-ttu-id="a0f13-103">Standardmäßig werden Updates für Office-Apps automatisch heruntergeladen und im Hintergrund angewendet, und zwar ohne Eingriff von Benutzern.</span><span class="sxs-lookup"><span data-stu-id="a0f13-103">By default, updates for Office Apps are downloaded automatically and applied in the background without any user intervention.</span></span> <span data-ttu-id="a0f13-104">Administratoren können jedoch mithilfe der Office-Updateeinstellungen steuern, wie Updates angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="a0f13-104">However, administrators can control how updates are applied by using Office Update settings.</span></span> <span data-ttu-id="a0f13-105">Mithilfe der Updateeinstellungen können Administratoren automatische Updates aktivieren oder deaktivieren, die Schaltfläche **Jetzt aktualisieren** in Office ein- oder ausblenden, Updatestichtage festlegen und vieles mehr.</span><span class="sxs-lookup"><span data-stu-id="a0f13-105">Update settings allow administrators to enable or disable automatic updates, show or hide the **Update Now** button in Office, set update deadlines, and more.</span></span> <span data-ttu-id="a0f13-106">Ausführliche Informationen finden Sie unter:</span><span class="sxs-lookup"><span data-stu-id="a0f13-106">For detailed information, see:</span></span>

- [<span data-ttu-id="a0f13-107">Konfigurieren von Updateeinstellungen für Office</span><span class="sxs-lookup"><span data-stu-id="a0f13-107">Configure update settings for Office</span></span>](https://docs.microsoft.com/deployoffice/configure-update-settings-for-office-365-proplus)  
- [<span data-ttu-id="a0f13-108">Automatische Aktualisierung für Office ist nicht aktiviert</span><span class="sxs-lookup"><span data-stu-id="a0f13-108">Automatic updating for Office is not enabled</span></span>](https://support.microsoft.com/help/2753538/automatic-updating-for-office-2013-and-office-2016-click-to-run-is-not)  
- [<span data-ttu-id="a0f13-109">Definieren, wie Office nach der Installation aktualisiert wird</span><span class="sxs-lookup"><span data-stu-id="a0f13-109">Define how Office is updated after it's installed</span></span>](https://docs.microsoft.com/deployoffice/configuration-options-for-the-office-2016-deployment-tool#updates-element)

<span data-ttu-id="a0f13-110">Um die bestehenden Updateeinstellungen zu überprüfen, die auf einen Clientcomputer angewendet werden, führen Sie diese Schritte aus:</span><span class="sxs-lookup"><span data-stu-id="a0f13-110">To review the existing updates settings applied to a client machine, follow these steps:</span></span>

1. <span data-ttu-id="a0f13-111">Öffnen Sie den Registrierungs-Editor über **Start** > **Ausführen** > **regedit**.</span><span class="sxs-lookup"><span data-stu-id="a0f13-111">Open the Registry Editor by going to **Start** > **Run** > **regedit**.</span></span>
2. <span data-ttu-id="a0f13-112">Wechseln Sie zu folgendem Speicherort, und überprüfen Sie die Einstellungen von Office Update:</span><span class="sxs-lookup"><span data-stu-id="a0f13-112">Switch to the following location and review the Office Update settings:</span></span>  
    <span data-ttu-id="a0f13-113">a.</span><span class="sxs-lookup"><span data-stu-id="a0f13-113">a.</span></span> <span data-ttu-id="a0f13-114">HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Office</span><span class="sxs-lookup"><span data-stu-id="a0f13-114">HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Office</span></span>\  
    <span data-ttu-id="a0f13-115">b.</span><span class="sxs-lookup"><span data-stu-id="a0f13-115">b.</span></span> <span data-ttu-id="a0f13-116">ClickToRun\Configuration</span><span class="sxs-lookup"><span data-stu-id="a0f13-116">ClickToRun\Configuration</span></span>

<span data-ttu-id="a0f13-117">**Hinweis** Wenn der OfficeMgmtCOM-Schlüssel festgelegt ist, wird unter **Office** > **Konto** > **Office-Updates** möglicherweise die Meldung "Updates werden von Ihrem Systemadministrator verwaltet" angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a0f13-117">**Note**  If the OfficeMgmtCOM key is set, you might see the "Updates are managed by your system administrator" message in **Office** > **Account** > **Office Updates**.</span></span> <span data-ttu-id="a0f13-118">Weitere Informationen finden Sie unter [Verwalten von Updates für Microsoft 365 Apps mithilfe des Microsoft Endpoint Configuration Manager](https://docs.microsoft.com/deployoffice/manage-updates-to-office-365-proplus-with-system-center-configuration-manager#method-1-use-office-deployment-tool-to-enable-office-365-clients-to-receive-updates-from-configuration-manager).</span><span class="sxs-lookup"><span data-stu-id="a0f13-118">For more info, see [Manage updates to Microsoft 365 Apps with Microsoft Endpoint Configuration Manager](https://docs.microsoft.com/deployoffice/manage-updates-to-office-365-proplus-with-system-center-configuration-manager#method-1-use-office-deployment-tool-to-enable-office-365-clients-to-receive-updates-from-configuration-manager).</span></span>  