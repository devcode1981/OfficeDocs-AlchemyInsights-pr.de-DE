---
title: Beheben von Bluetooth-Problemen in Windows 10
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001475"
- "3506"
ms.openlocfilehash: 94dda7a42632f57ce3aef5f467b87df1033b8d49
ms.sourcegitcommit: 9a35768444824cde9e192f1d9daafc9157437244
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 02/25/2020
ms.locfileid: "42268632"
---
# <a name="fix-bluetooth-problems-in-windows-10"></a><span data-ttu-id="1b9a8-102">Beheben von Bluetooth-Problemen in Windows 10</span><span class="sxs-lookup"><span data-stu-id="1b9a8-102">Fix Bluetooth problems in Windows 10</span></span>

<span data-ttu-id="1b9a8-103">Wenn das Bluetooth-Symbol fehlt oder Bluetooth nicht aktiviert oder deaktiviert werden kann, möchten Sie möglicherweise die Bluetooth-Problembehandlung ausführen.</span><span class="sxs-lookup"><span data-stu-id="1b9a8-103">If the Bluetooth icon is missing or Bluetooth can't be turned on or off, you may want to run the Bluetooth troubleshooter.</span></span> <span data-ttu-id="1b9a8-104">[Öffnen Sie die Problembehandlungseinstellungen](ms-settings:troubleshoot), klicken Sie unter **Suchen und beheben anderer Probleme**auf **Bluetooth** , und klicken Sie dann auf **Problembehandlung ausführen**.</span><span class="sxs-lookup"><span data-stu-id="1b9a8-104">[Open the Troubleshoot settings](ms-settings:troubleshoot), click **Bluetooth** under **Find and fix other problems**, click **Run the troubleshooter**.</span></span>

<span data-ttu-id="1b9a8-105">Wenn das Bluetooth-Symbol nicht angezeigt wird, aber Bluetooth im Geräte-Manager angezeigt wird:</span><span class="sxs-lookup"><span data-stu-id="1b9a8-105">If you don't see the Bluetooth icon, but Bluetooth does appear in Device Manager:</span></span>

1. <span data-ttu-id="1b9a8-106">Klicken Sie im Geräte-Manager auf **Bluetooth**.</span><span class="sxs-lookup"><span data-stu-id="1b9a8-106">In Device Manager, click **Bluetooth**.</span></span> <span data-ttu-id="1b9a8-107">Halten Sie den Bluetooth-Adapternamen gedrückt (oder klicken Sie mit der rechten Maustaste), und klicken Sie auf **Gerät deinstallieren**.</span><span class="sxs-lookup"><span data-stu-id="1b9a8-107">Press and hold (or right-click) the Bluetooth adapter name and click **Uninstall device**.</span></span>

2. <span data-ttu-id="1b9a8-108">Fahren Sie Ihr Windows-Gerät herunter, warten Sie einige Sekunden, und schalten Sie es dann wieder ein.</span><span class="sxs-lookup"><span data-stu-id="1b9a8-108">Shut down your Windows device, wait a few seconds, and then turn it back on.</span></span> <span data-ttu-id="1b9a8-109">Der Treiber wird von Windows erneut installiert.</span><span class="sxs-lookup"><span data-stu-id="1b9a8-109">Windows will try to reinstall the driver.</span></span>

<span data-ttu-id="1b9a8-110">Wenn Sie vor kurzem Windows 10-Updates installiert oder auf Windows 10 aktualisiert haben, sollten Sie nach Treiberupdates suchen:</span><span class="sxs-lookup"><span data-stu-id="1b9a8-110">If you recently installed Windows 10 updates or upgraded to Windows 10, you may want to check for driver updates:</span></span>

1. <span data-ttu-id="1b9a8-111">Klicken Sie im Geräte-Manager auf **Bluetooth**, und klicken Sie dann auf den Namen des Bluetooth-Adapters (der das Wort "Radio" enthalten kann).</span><span class="sxs-lookup"><span data-stu-id="1b9a8-111">In Device Manager, click **Bluetooth**, and then click the Bluetooth adapter name (which may include the word "radio").</span></span>

2. <span data-ttu-id="1b9a8-112">Halten Sie den Bluetooth-Adapter gedrückt (oder klicken Sie mit der rechten Maustaste darauf), und klicken Sie dann auf automatische **Treiber** > **Suche aktualisieren für aktualisierte Treibersoftware**.</span><span class="sxs-lookup"><span data-stu-id="1b9a8-112">Press and hold (or right-click) the Bluetooth adapter, and then click **Update driver** > **Search automatically for updated driver software**.</span></span> <span data-ttu-id="1b9a8-113">Führen Sie die Schritte aus, und klicken Sie dann auf **Schließen**.</span><span class="sxs-lookup"><span data-stu-id="1b9a8-113">Follow the steps, then click **Close**.</span></span>

      - <span data-ttu-id="1b9a8-114">Wenn Windows keinen neuen Bluetooth-Treiber finden kann, besuchen Sie die Website des PC-Herstellers, und laden Sie von dort den neuesten Bluetooth-Treiber herunter.</span><span class="sxs-lookup"><span data-stu-id="1b9a8-114">If Windows can't find a new Bluetooth driver, visit the PC manufacturer's website and download the latest Bluetooth driver from there.</span></span>

    - <span data-ttu-id="1b9a8-115">Nachdem Sie das Programm heruntergeladen haben, klicken Sie auf **Treiber** > aktualisieren**Durchsuchen** > nach dem Speicherort der Treiber**Dateien durchsuchen** des Speicherorts, an dem die Treiberdateien gespeichert sind > **OK** > **, und**führen Sie die folgenden Schritte aus, um zu installieren.</span><span class="sxs-lookup"><span data-stu-id="1b9a8-115">After you download it, click **Update driver** > **Browse my computer for driver software** > **Browse** for the location where the driver files are stored > **OK** > **Next**, and follow the steps to install.</span></span>

3. <span data-ttu-id="1b9a8-116">Nachdem Sie den aktualisierten Treiber installiert haben, starten Sie den Computer neu, und überprüfen Sie dann, ob das Verbindungsproblem behoben wurde.</span><span class="sxs-lookup"><span data-stu-id="1b9a8-116">After installing the updated driver, restart the machine, and then check whether that fixes the connection issue.</span></span>

<span data-ttu-id="1b9a8-117">Weitere Informationen zur Behandlung von Bluetooth-Problemen finden Sie im vollständigen Artikel Beheben von [Bluetooth-Problemen in Windows 10](https://support.microsoft.com/help/14169/windows-10-fix-bluetooth-problems).</span><span class="sxs-lookup"><span data-stu-id="1b9a8-117">For more details of how to troubleshoot Bluetooth problems, please see the full article, [Fix Bluetooth problems in Windows 10](https://support.microsoft.com/help/14169/windows-10-fix-bluetooth-problems).</span></span>