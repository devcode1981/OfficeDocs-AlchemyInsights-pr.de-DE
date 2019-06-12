---
title: ATP für SharePoint, OneDrive und Microsoft Teams
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1037
ms.assetid: ''
ms.openlocfilehash: b304f6c7d9959e49a8152c03f11c6c864a154ea5
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/07/2019
ms.locfileid: "34765058"
---
# <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a><span data-ttu-id="1edc0-102">ATP für SharePoint, OneDrive und Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="1edc0-102">ATP for SharePoint, OneDrive, and Microsoft Teams</span></span>

<span data-ttu-id="1edc0-103">Führen Sie die folgenden Schritte aus, um Advanced Threat Protection zu aktivieren:</span><span class="sxs-lookup"><span data-stu-id="1edc0-103">Follow these steps to enable Advanced Threat Protection:</span></span>

1. <span data-ttu-id="1edc0-104">Wechseln Sie [https://protection.office.com](https://protection.office.com) zu, und melden Sie sich mit einem globalen Administrator-oder Sicherheitsadministrator Konto an.</span><span class="sxs-lookup"><span data-stu-id="1edc0-104">Go to [https://protection.office.com](https://protection.office.com) and sign in with a global administrator or security administrator account.</span></span>

2. <span data-ttu-id="1edc0-105">Wählen Sie im linken Navigationsbereich unter **Bedrohungs Verwaltung**die Option **Richtlinien** \> für **sichere Anlagen**aus.</span><span class="sxs-lookup"><span data-stu-id="1edc0-105">In the left navigation pane under **Threat management**, choose **Policy** \> **Safe Attachments**.</span></span>

3. <span data-ttu-id="1edc0-106">Wählen Sie **ATP für SharePoint, OneDrive und Microsoft Teams aktivieren**aus.</span><span class="sxs-lookup"><span data-stu-id="1edc0-106">Select **Turn on ATP for SharePoint, OneDrive, and Microsoft Teams**.</span></span>

4. <span data-ttu-id="1edc0-107">[Erstellen Sie eine Aktivitäts Warnungs Richtlinie](https://docs.microsoft.com/office365/securitycompliance/create-activity-alerts) zum Empfangen von Benachrichtigungen, wenn wir bösartige Dateien erkennen.</span><span class="sxs-lookup"><span data-stu-id="1edc0-107">[Create an activity alert policy](https://docs.microsoft.com/office365/securitycompliance/create-activity-alerts) to receive notifications when we detect malicious files.</span></span>

<span data-ttu-id="1edc0-108">Ausführliche Anweisungen finden Sie in diesem [Thema](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams).</span><span class="sxs-lookup"><span data-stu-id="1edc0-108">For complete instructions, see this [topic](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams).</span></span>

<span data-ttu-id="1edc0-109">**Hinweis**: ATP scannt nicht jede einzelne Datei in SharePoint Online, OneDrive für Unternehmen oder Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="1edc0-109">**Note**: By design, ATP doesn't scan every single file in SharePoint Online, OneDrive for Business, or Microsoft Teams.</span></span> <span data-ttu-id="1edc0-110">Dateien werden asynchron durch einen Prozess gescannt, der freigabeaktivitäten, Gast Aktivitäten und Bedrohungs Signale verwendet, um bösartige Dateien zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="1edc0-110">Files are scanned asynchronously by a process that uses sharing activity, guest activity, and threat signals to identify malicious files.</span></span> <span data-ttu-id="1edc0-111">Weitere Informationen finden Sie in diesem [Thema](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).</span><span class="sxs-lookup"><span data-stu-id="1edc0-111">For more information, see this [topic](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).</span></span>