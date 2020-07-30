---
title: Application Protection Policy (Anwendungsschutzrichtlinie)
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/22/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1073"
- "6700006"
ms.openlocfilehash: 7fed65e6749f72e6264070b360a52e72968fc8da
ms.sourcegitcommit: 6f7cbf1dc28c0693009ddf03d9768c1c65018964
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/22/2020
ms.locfileid: "45266433"
---
# <a name="application-protection-policy"></a><span data-ttu-id="c677e-102">Application Protection Policy (Anwendungsschutzrichtlinie)</span><span class="sxs-lookup"><span data-stu-id="c677e-102">Application protection policy</span></span>

<span data-ttu-id="c677e-103">Wenn Sie mit Application Protection Policy (APP) noch nicht vertraut sind, lesen Sie die [App Protection Policy-Übersicht](https://docs.microsoft.com/intune/apps/app-protection-policy).</span><span class="sxs-lookup"><span data-stu-id="c677e-103">If you're new to Application protection policy (APP), check out the [App protection policies overview](https://docs.microsoft.com/intune/apps/app-protection-policy).</span></span>

<span data-ttu-id="c677e-104">Weitere Informationen für die ersten Schritte mit APP finden Sie unter [Erstellen und Zuweisen von App-Schutzrichtlinien](https://docs.microsoft.com/intune/app-protection-policies).</span><span class="sxs-lookup"><span data-stu-id="c677e-104">To start using APP, see [How to create and assign app protection policies](https://docs.microsoft.com/intune/app-protection-policies).</span></span>

<span data-ttu-id="c677e-105">Application Protection Policy – Anforderungen:</span><span class="sxs-lookup"><span data-stu-id="c677e-105">Application protection policy requirements:</span></span>

- <span data-ttu-id="c677e-106">Der Benutzer verfügt über eine Intune- oder EMS-Lizenz.</span><span class="sxs-lookup"><span data-stu-id="c677e-106">User has an Intune or EMS license.</span></span>
- <span data-ttu-id="c677e-107">Der Benutzer gehört zu einer Gruppe, die durch Anwendungsschutzrichtlinien geschützt ist.</span><span class="sxs-lookup"><span data-stu-id="c677e-107">User belongs to a group targeted by application protection policies.</span></span>
- <span data-ttu-id="c677e-108">Nur ein Unternehmensbenutzer ist an geschützten Apps auf einem Gerät angemeldet.</span><span class="sxs-lookup"><span data-stu-id="c677e-108">Only one corporate user is signed into protected apps on a device.</span></span>
- <span data-ttu-id="c677e-109">Für die Anwendung wurde das [Intune-SDK](https://docs.microsoft.com/intune/app-sdk-get-started) implementiert.</span><span class="sxs-lookup"><span data-stu-id="c677e-109">The application has implemented the [Intune SDK](https://docs.microsoft.com/intune/app-sdk-get-started).</span></span> <span data-ttu-id="c677e-110">Eine Liste der Apps, die das SDK unterstützen, finden Sie unter [Geschützte Microsoft Intune-Apps](https://docs.microsoft.com/intune/apps-supported-intune-apps).</span><span class="sxs-lookup"><span data-stu-id="c677e-110">For a list of apps that support the SDK, see [Microsoft Intune protected apps](https://docs.microsoft.com/intune/apps-supported-intune-apps).</span></span>

<span data-ttu-id="c677e-111">Richtlinien gelten, nachdem sich ein Benutzer, der die vorstehenden Voraussetzungen erfüllt, an einer Intune-SDK-App angemeldet hat.</span><span class="sxs-lookup"><span data-stu-id="c677e-111">Policies apply after a user who meets the above requirements signs into an Intune SDK enabled app.</span></span> <span data-ttu-id="c677e-112">Die einfachste Möglichkeit, um festzustellen, ob eine Richtlinie angewendet wird, besteht darin, dass der Benutzer eine PIN in der Richtlinie festlegen muss.</span><span class="sxs-lookup"><span data-stu-id="c677e-112">The easiest way to determine if a policy is applied is by requiring that the user set a pin in the policy.</span></span> 

<span data-ttu-id="c677e-113">Weitere Informationen finden Sie unter:</span><span class="sxs-lookup"><span data-stu-id="c677e-113">For more information, see:</span></span>

[<span data-ttu-id="c677e-114">App/MAM – häufig gestellte Fragen zur Problembehandlung</span><span class="sxs-lookup"><span data-stu-id="c677e-114">APP/MAM troubleshooting FAQ</span></span>](https://docs.microsoft.com/intune/apps/troubleshoot-mam)  

[<span data-ttu-id="c677e-115">So überprüfen Sie Ihr Application Protection Policy-Setup</span><span class="sxs-lookup"><span data-stu-id="c677e-115">How to validate your app protection policy setup</span></span>](https://docs.microsoft.com/intune/app-protection-policies-validate)

[<span data-ttu-id="c677e-116">Grundlegendes zur Bereitstellungszeit für Application Protection Policy</span><span class="sxs-lookup"><span data-stu-id="c677e-116">Understand App Protection Policy delivery timing</span></span>](https://docs.microsoft.com/intune/app-protection-policy-delivery)  

[<span data-ttu-id="c677e-117">Überwachen von App-Schutzrichtlinien</span><span class="sxs-lookup"><span data-stu-id="c677e-117">How to monitor app protection policies</span></span>](https://docs.microsoft.com/intune/app-protection-policies-monitor)