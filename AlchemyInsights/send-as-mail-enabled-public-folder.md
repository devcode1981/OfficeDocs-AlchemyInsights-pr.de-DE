---
title: Öffentlichen Ordner "als e-Mail-aktiviert senden" in Exo
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1956"
- "3500007"
ms.openlocfilehash: ed62c6d7db0ae532f806ce4fdc48f42623bcd545
ms.sourcegitcommit: 1fb324fd156008e77b7e2008af4b3dc1c0d0ea3e
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/13/2020
ms.locfileid: "48451382"
---
# <a name="sendas-mail-enabled-public-folder"></a><span data-ttu-id="17f59-102">E-Mail-aktivierter Öffentlicher Ordner für Absender</span><span class="sxs-lookup"><span data-stu-id="17f59-102">SendAs Mail Enabled Public Folder</span></span>

<span data-ttu-id="17f59-103">Im folgenden Beispiel wird dem Benutzer Jason die Berechtigung "Senden als" für den e-Mail-aktivierten Öffentlichen Ordner NewPF1 zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="17f59-103">The following example assigns "Send As" permissions for the mail-enabled public folder NewPF1 to the user Jason.</span></span>

<span data-ttu-id="17f59-104">Add-RecipientPermission-Identity ' NewPF1 ' – Trustee "Jason" – AccessRights ' Sends '</span><span class="sxs-lookup"><span data-stu-id="17f59-104">Add-RecipientPermission -Identity 'NewPF1' -Trustee "Jason" -AccessRights 'SendAs'</span></span>

<span data-ttu-id="17f59-105">Ausführliche Informationen zu Syntax und Parametern finden Sie unter Zuweisen von " [Senden als"-oder "Senden im Auftrag von"-Berechtigungen für e-Mail-aktivierte Öffentliche Ordner](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/assign-permissions-mail-enabled-pfs).</span><span class="sxs-lookup"><span data-stu-id="17f59-105">For detailed syntax and parameter information see [Assign "Send As" or "Send on Behalf" permissions for mail-enabled public folders](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/assign-permissions-mail-enabled-pfs).</span></span>
