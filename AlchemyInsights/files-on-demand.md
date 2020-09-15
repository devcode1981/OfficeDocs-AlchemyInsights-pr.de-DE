---
title: Dateien bei Bedarf
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/15/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "6432"
- "9003530"
ms.openlocfilehash: 846cda97ccd52fcb43ae4a44f73deeaaa6dc093d
ms.sourcegitcommit: b7bbe4c5419668ce8e84196db382032ca09cd176
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/08/2020
ms.locfileid: "47406572"
---
# <a name="configure-files-on-demand"></a><span data-ttu-id="4b8fd-102">OneDrive-Dateien bei Bedarf konfigurieren</span><span class="sxs-lookup"><span data-stu-id="4b8fd-102">Configure Files On-Demand</span></span>

<span data-ttu-id="4b8fd-103">Mit OneDrive-Dateien bei Bedarf können Sie auf alle Ihre Dateien in OneDrive zugreifen, ohne alle herunterladen und Speicherplatz auf Ihrem Gerät nutzen zu müssen.</span><span class="sxs-lookup"><span data-stu-id="4b8fd-103">OneDrive Files On-Demand helps you access all your files in OneDrive without having to download all of them and use storage space on your device.</span></span>

<span data-ttu-id="4b8fd-104">So konfigurieren Sie die Dateien bei Bedarf auf Ihrem PC:</span><span class="sxs-lookup"><span data-stu-id="4b8fd-104">To configure Files On-Demand on your PC:</span></span>

1. <span data-ttu-id="4b8fd-105">Wählen Sie das weiße oder blaue **OneDrive** Cloudsymbol im Benachrichtigungsbereich der Windows-Taskleiste aus.</span><span class="sxs-lookup"><span data-stu-id="4b8fd-105">Select the white or blue **OneDrive** cloud icon in the Windows taskbar notification area.</span></span> <span data-ttu-id="4b8fd-106">Wählen Sie **Hilfe & Einstellungen** Zahnradsymbol > **Einstellungen**.</span><span class="sxs-lookup"><span data-stu-id="4b8fd-106">Select the **Help & Settings** gear icon > **Settings**.</span></span>
2. <span data-ttu-id="4b8fd-107">Aktivieren Sie auf der Registerkarte **Einstellungen** das Kontrollkästchen **Platz sparen und Dateien erst bei Verwendung herunterladen**.</span><span class="sxs-lookup"><span data-stu-id="4b8fd-107">On the **Settings** tab, select the **Save space and download files as you use them** box.</span></span>  

<span data-ttu-id="4b8fd-108">Sie können Dateien bei Bedarf auch mithilfe der Registrierung konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="4b8fd-108">You can also configure Files On-Demand using the registry.</span></span>

<span data-ttu-id="4b8fd-109">Wenn Sie diese Einstellung deaktivieren, weisen Windows 10-Benutzer das gleiche Synchronisierungsverhalten wie Benutzer der früheren Versionen von Windows auf, und sie können "Dateien bei Bedarf" nicht aktivieren.</span><span class="sxs-lookup"><span data-stu-id="4b8fd-109">If you disable this setting, Windows 10 users have the same sync behavior as users of previous versions of Windows, and aren't able to turn on Files On-Demand.</span></span> <span data-ttu-id="4b8fd-110">Wenn Sie diese Einstellung nicht konfigurieren, können die Benutzer „Dateien bei Bedarf“ aktivieren oder deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="4b8fd-110">If you do not configure this setting, users can turn Files On-Demand on or off.</span></span>

<span data-ttu-id="4b8fd-111">Durch Aktivieren dieser Richtlinie wird der folgende Registrierungsschlüsselwert auf 1 festgelegt.</span><span class="sxs-lookup"><span data-stu-id="4b8fd-111">Enabling this policy sets the following registry key value to 1.</span></span> <span data-ttu-id="4b8fd-112">Das Deaktivieren dieser Richtlinie setzt den folgenden Registrierungsschlüsselwert auf 0.</span><span class="sxs-lookup"><span data-stu-id="4b8fd-112">Disabling this policy sets the following registry key value to 0.</span></span>

`[HKLM\SOFTWARE\Policies\Microsoft\OneDrive]"FilesOnDemandEnabled"="dword:00000001"`

<span data-ttu-id="4b8fd-113">Wenn die Dateien bei Bedarf-Option in „Einstellungen“ nicht angezeigt wird, stellen Sie sicher, dass der Starttyp des Dienstes „Windows-Clouddateien-Filter-Treiber“ auf 2 (AUTO_START) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="4b8fd-113">If you can't see the Files On-Demand option in "Settings," make sure the service "Windows Cloud Files Filter Driver" start type is set to 2 (AUTO_START).</span></span> <span data-ttu-id="4b8fd-114">Das Aktivieren dieses Features setzt den folgende Registrierungsschlüsselwert auf 2.</span><span class="sxs-lookup"><span data-stu-id="4b8fd-114">Enabling this feature sets the following registry key value to 2.</span></span>

`[HKLM\SYSTEM\CurrentControlSet\Services\CldFlt]"Start"="dword:00000002"`