---
title: An eine Microsoft 365-Gruppe gesendete Nachrichten werden nicht von allen Mitgliedern empfangen
ms.author: pebaum
author: pebaum
manager: mnirkhe
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9003200"
- "5995"
ms.openlocfilehash: 080c060f5675065704c7209bd15e4cbb1236b8db
ms.sourcegitcommit: b71e5981b7f30ef2bce4e695118d03aa68a5be4a
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/05/2021
ms.locfileid: "50480682"
---
# <a name="messages-sent-to-a-microsoft-365-group-are-not-received-by-all-members"></a>An eine Microsoft 365-Gruppe gesendete Nachrichten werden nicht von allen Mitgliedern empfangen

Stellen Sie sicher, dass alle Gruppenmitglieder den Empfang der E-Mails abonniert haben. Siehe [Folgen einer Gruppe in Outlook](https://support.microsoft.com/office/e147fc19-f548-4cd2-834f-80c6235b7c36).  

Um den Nachrichtenstatus von Mitgliedern zu überprüfen, die Gruppen-E-Mails abonniert haben, führen Sie den folgenden Befehl in [EXO PowerShell](https://docs.microsoft.com/powershell/exchange/connect-to-exchange-online-powershell?view=exchange-ps&preserve-view=true) aus:

`Get-UnifiedGroup <GroupName> | Get-UnifiedGroupLinks -LinkType Subscribers`

Verwenden Sie den folgenden EXO PowerShell-Befehl, um alle Gruppenmitglieder so zu konfigurieren, dass sie E-Mails, die an die Microsoft 365-Gruppe gesendet werden, in ihrem Posteingang erhalten:

`$Group = "Address of [Microsoft 365 Groups]"Get-UnifiedGroupLinks $Group -LinkType Member | % {Add-UnifiedGroupLinks -Identity $Group -LinkType subscriber -Links $_.Guid.toString() -Confirm:$false}`

Beispiel:

`$Group = "testg@contoso.onmicrosoft.com"Get-UnifiedGroupLinks $Group -LinkType Member | % {Add-UnifiedGroupLinks -Identity $Group -LinkType subscriber -Links $_.Guid.toString() -Confirm:$false}`