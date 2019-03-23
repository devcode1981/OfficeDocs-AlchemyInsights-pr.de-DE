---
title: 646 Konfigurieren von AADConnect
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 6/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 646
ms.assetid: 599698ac-6709-477a-a66f-169b3165064e
ms.openlocfilehash: 6cc4afb4b0f67fb76ecc7ff8f564b1cd36cc291c
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/22/2019
ms.locfileid: "30779511"
---
# <a name="configure-sync-features"></a>Konfigurieren von Synchronisierungsfeatures

Azure AD Connect umfasst mehrere Features, die standardmäßig aktiviert sind oder die Sie später aktivieren können. Einige Features erfordern zusätzliche Konfiguration in bestimmten Umgebungen.
  
- [Filter](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) Grenzen die Objekte werden mit Azure AD synchronisiert. Standardmäßig werden alle Benutzer, Kontakte, Gruppen und Windows 10-Computerkonten synchronisiert. Sie können Objekte basierend auf Domänen, Organisationseinheiten oder anderen Attributen einschließen oder ausschließen. 
    
- [Password Hash Synchronisierung](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) synchronisiert den Kennworthash vom lokalen Active Directory mit Azure AD. Auf diese Weise kann die Kennwortverwaltung an einem Ort, aber in lokalen und Cloud-Umgebungen verwendet werden. Da Active Directory die autorisierende Quelle ist, können Sie Ihre eigenen Kennwortrichtlinien verwenden. 
    
- [Self-Service Password Reset (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) ermöglicht es Benutzern, ihre eigenen Kennwörter in der Cloud zurückzusetzen, während Sie weiterhin Ihre lokale Kennwortrichtlinie anwenden. 
    
- [](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) Durch das Rückschreiben von Geräten können registrierte Geräte in Azure AD in das lokale Active Directory zurückgeschrieben werden, damit Sie für bedingten Zugriff verwendet werden können. 
    
- Verhindern Sie, dass [versehentliche Löschvorgänge](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) standardmäßig aktiviert sind, um zu viele gleichzeitige Objektlöschungen zu verhindern (mehr als 500 Objekte pro Synchronisierung). Sie können diese Einstellung ändern, um die Anforderungen Ihrer Organisation zu erfüllen. 
    
- Das [Automatische Upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) ist für Express Installationen standardmäßig aktiviert und stellt sicher, dass Ihre Version von Azure AD Connect immer aktuell ist. 
    
