---
title: Umgehen der Aktivierungssperre für überwachte iOS-Geräte mit Intune
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/23/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1277"
- "6700008"
ms.openlocfilehash: 16be4e0cd2e47fe5d5888cbbe1380774f859e4d6
ms.sourcegitcommit: 07e56267dedfc4cec1143072c791670cbf81186b
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/24/2020
ms.locfileid: "45397732"
---
# <a name="bypass-activation-lock-on-supervised-ios-devices-with-intune"></a><span data-ttu-id="6267d-102">Umgehen der Aktivierungssperre für überwachte iOS-Geräte mit Intune</span><span class="sxs-lookup"><span data-stu-id="6267d-102">Bypass activation lock on supervised iOS devices with Intune</span></span>

<span data-ttu-id="6267d-103">Die Möglichkeit, die Aktivierungssperre auf iOS-Geräten zu umgehen, erleichtert die Wiederherstellung in dem Szenario, in dem ein Benutzer die Aktivierungssperre auf einem Unternehmensgerät aktiviert und das Unternehmen verlässt.</span><span class="sxs-lookup"><span data-stu-id="6267d-103">The ability to bypass the activation lock on iOS devices makes it easier to recover from the scenario where a user enables activation lock on a corporate device, and then leaves the company.</span></span>

<span data-ttu-id="6267d-104">Zu den Voraussetzungen für die Umgehung einer Aktivierungssperre gehören:</span><span class="sxs-lookup"><span data-stu-id="6267d-104">Pre-requisites to bypassing an activation lock include:</span></span>

- <span data-ttu-id="6267d-105">Das Gerät wird "beaufsichtigt".</span><span class="sxs-lookup"><span data-stu-id="6267d-105">A device is that is "supervised."</span></span>
- <span data-ttu-id="6267d-106">Die Aktivierungssperre wird mithilfe der iOS-Geräteeinschränkungsrichtlinie in Intune erfolgreich aktiviert.</span><span class="sxs-lookup"><span data-stu-id="6267d-106">The activation lock is successfully enabled using iOS Device restriction policy in Intune.</span></span>

<span data-ttu-id="6267d-107">Außerdem sollten Sie beim Umgehen einer Aktivierungssperre:</span><span class="sxs-lookup"><span data-stu-id="6267d-107">In addition, when bypassing an activation lock, you should:</span></span>

- <span data-ttu-id="6267d-108">das zurückzusetzende Gerät physisch besitzen.</span><span class="sxs-lookup"><span data-stu-id="6267d-108">Physically possess the device being wiped.</span></span>
- <span data-ttu-id="6267d-109">vor dem Auslösen des Zurücksetzens den Code kopieren.</span><span class="sxs-lookup"><span data-stu-id="6267d-109">Copy the code before you issue the wipe.</span></span>

<span data-ttu-id="6267d-110">**Hinweis:** Beim Zurücksetzungscode wird nicht nach Groß-/Kleinschreibung unterschieden, sodass die Zeichen "-"-Zeichen nicht erforderlich sind.</span><span class="sxs-lookup"><span data-stu-id="6267d-110">**Note:** The wipe code is not case sensitive, so the "-" characters are not required.</span></span>

<span data-ttu-id="6267d-111">Weitere Informationen finden Sie unter [Umgehen der Aktivierungssperre für überwachte iOS-Geräte mit Intune](https://docs.microsoft.com/intune/device-activation-lock-bypass).</span><span class="sxs-lookup"><span data-stu-id="6267d-111">For details, see [Bypass Activation Lock on Supervised iOS devices with Intune](https://docs.microsoft.com/intune/device-activation-lock-bypass).</span></span>

<span data-ttu-id="6267d-112">**Häufig gestellte Fragen**</span><span class="sxs-lookup"><span data-stu-id="6267d-112">**FAQ**</span></span>

<span data-ttu-id="6267d-113">F: **Ich habe eine Remoteaktion zum Entfernen von Unternehmensdaten von einem Gerät gesendet, und jetzt ist das Gerät im Zustand „Ausstehend“ hängen geblieben.**</span><span class="sxs-lookup"><span data-stu-id="6267d-113">Q: **I issued a remote action to remove company data from a device, and now it’s stuck in a pending state.**</span></span>

<span data-ttu-id="6267d-114">A: Damit eine Remoteaktion erfolgreich abgeschlossen werden kann, muss das Zielgerät online und fehlerfrei sein.</span><span class="sxs-lookup"><span data-stu-id="6267d-114">A: For a remote action to successfully complete, the targeted device must be online and healthy.</span></span> <span data-ttu-id="6267d-115">In den folgenden Situationen bleibt die Remoteaktion 30 Tage lang im Zustand „Ausstehend“ oder bis das Gerät den Befehl bestätigt, falls Folgendes für das Gerät zutrifft:</span><span class="sxs-lookup"><span data-stu-id="6267d-115">In the following situations, the remote action stays in a pending state for 30 days, or until the device acknowledges the command when the device:</span></span>

- <span data-ttu-id="6267d-116">Das Gerät hat keine Verbindung.</span><span class="sxs-lookup"><span data-stu-id="6267d-116">Does not have connectivity.</span></span>
- <span data-ttu-id="6267d-117">Das Gerät verliert seinen Verwaltungsstatus bei Intune.</span><span class="sxs-lookup"><span data-stu-id="6267d-117">Loses its management status with Intune.</span></span>

<span data-ttu-id="6267d-118">Wenn Sie der Meinung sind, dass das Gerät keinen Check-In mehr vornimmt und dass es keine Unternehmensdaten entfernt, wählen Sie „Löschen“ aus.</span><span class="sxs-lookup"><span data-stu-id="6267d-118">If you think a device is no longer checking in, and that it won’t remove company data, select Delete.</span></span> <span data-ttu-id="6267d-119">Durch das Löschen wird der Gerätedatensatz entfernt, sodass er nicht mehr in der Liste der Geräte in Intune angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="6267d-119">Deleting removes the device record so that it no longer appears in the Intune list of devices.</span></span> <span data-ttu-id="6267d-120">Damit das Gerät wieder aktiv wird, muss der Benutzer das Gerät erneut registrieren.</span><span class="sxs-lookup"><span data-stu-id="6267d-120">For the device to become active again, its user must re-enroll the device.</span></span>

<span data-ttu-id="6267d-121">F: **Warum sind bestimmte Remoteaktionen für mich nicht verfügbar?**</span><span class="sxs-lookup"><span data-stu-id="6267d-121">Q: **Why are certain remote actions not available for me to use?**</span></span>

<span data-ttu-id="6267d-122">A: Nicht alle Plattformen unterstützen alle Remoteaktionen für Geräte.</span><span class="sxs-lookup"><span data-stu-id="6267d-122">A: Not all platforms support all remote device actions.</span></span> <span data-ttu-id="6267d-123">Die folgenden Remoteaktionen sind plattformspezifisch.</span><span class="sxs-lookup"><span data-stu-id="6267d-123">The following remote actions are platform-specific.</span></span>

- <span data-ttu-id="6267d-124">Aktivierungssperre umgehen (nur iOS)</span><span class="sxs-lookup"><span data-stu-id="6267d-124">Bypass Activation Lock (iOS only)</span></span>
- <span data-ttu-id="6267d-125">Sauberer Start (nur Windows)</span><span class="sxs-lookup"><span data-stu-id="6267d-125">Fresh Start (Windows only)</span></span>
- <span data-ttu-id="6267d-126">Modus für verlorene Geräte (nur iOS)</span><span class="sxs-lookup"><span data-stu-id="6267d-126">Lost mode (iOS only)</span></span>
- <span data-ttu-id="6267d-127">Gerät suchen (nur iOS)</span><span class="sxs-lookup"><span data-stu-id="6267d-127">Locate device (iOS only)</span></span>
- <span data-ttu-id="6267d-128">Neustart (nur Windows)</span><span class="sxs-lookup"><span data-stu-id="6267d-128">Restart (Windows only)</span></span>

<span data-ttu-id="6267d-129">Weitere Details zu den einzelnen Aktionen finden Sie unter [Verfügbare Geräteaktionen](https://docs.microsoft.com/intune/device-management#available-device-actions).</span><span class="sxs-lookup"><span data-stu-id="6267d-129">For more details about each action, see [Available device actions](https://docs.microsoft.com/intune/device-management#available-device-actions).</span></span>