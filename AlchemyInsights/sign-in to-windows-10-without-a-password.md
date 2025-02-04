---
title: Anmeldung bei Windows 10 ohne Verwendung eines Kennworts
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001690"
- "3766"
ms.openlocfilehash: 839b945c457cb007f13605c5b903ded75dadd1d7
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/14/2020
ms.locfileid: "47719952"
---
# <a name="sign-in-to-windows-10-without-using-a-password"></a>Anmeldung bei Windows 10 ohne Verwendung eines Kennworts

Um zu vermeiden, dass beim Windows-Start ein Kennwort eingegeben werden muss, empfehlen wir Ihnen, wenn verfügbar, eine der Windows Hello Secure-Anmeldeoptionen wie PIN, Face Recognition oder Fingerabdruck. Wenn Sie die sichere Anmeldung wirklich deaktivieren möchten, lesen Sie die Anweisungen unter "Automatisches Anmelden bei Windows 10".

**Sichere Windows Hello-Alternativen zum Kontokennwort**

Wechseln Sie zu **Einstellungen > Konten > Anmeldeoptionen** (oder klicken Sie [hier](ms-settings:signinoptions?activationSource=GetHelp)). Die verfügbaren Anmeldeoptionen werden aufgelistet. Zum Beispiel:

![Anmeldeoptionen.](media/sign-in-options.png)

Klicken oder tippen Sie auf eine der Optionen, um Sie zu konfigurieren. Wenn Sie das nächste Mal Windows starten oder entsperren, können Sie die neue Option anstelle eines Kennworts verwenden. 

**Automatisches Anmelden bei Windows 10**

**Hinweis**: die automatische Anmeldung ist praktisch, führt jedoch ein Sicherheitsrisiko ein, insbesondere dann, wenn Ihr PC von mehreren Personen zugänglich ist. 

1. Klicken oder tippen Sie auf die Schaltfläche **Start** in der Taskleiste.

2. Geben Sie **netplwiz** ein, und drücken Sie die EINGABETASTE, um das Fenster Benutzerkonten zu öffnen.

3. Klicken Sie unter **Benutzerkonten**auf das Konto, für das Sie sich beim Start von Windows automatisch anmelden möchten.

4. Deaktivieren Sie das Kontrollkästchen "Benutzer müssen einen Benutzernamen und ein Kennwort für die Verwendung dieses Computers eingeben".

    ![Benutzer müssen eine Option für Benutzername und Kennwort eingeben.](media/users-must-enter-username.png)

5. Klicken Sie auf **OK**. Sie werden aufgefordert, das Kennwort für das ausgewählte Konto einzugeben und zu bestätigen. Klicken Sie zum Abschließen auf **OK**. Das nächste Mal, wenn Windows 10 gestartet wird, wird es sich automatisch bei dem ausgewählten Konto anmelden.
