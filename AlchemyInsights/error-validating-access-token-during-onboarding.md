---
title: Fehler beim Validieren des Zugriffstoken Fehlers beim on-Boarding von Desktop Analytics
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2536"
- "9000657"
ms.openlocfilehash: 7472af5c4e19e5697b5fb4802ed1cbb2c74f1d19
ms.sourcegitcommit: f1fad2129d09660ec42dbce03ce2c6b4cfc9555a
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 12/18/2019
ms.locfileid: "40741178"
---
# <a name="there-was-an-error-validating-access-token-error-during-desktop-analytics-onboarding"></a><span data-ttu-id="4c9c5-102">Fehler beim Validieren des Zugriffstokens beim Desktop Analyse-Onboarding</span><span class="sxs-lookup"><span data-stu-id="4c9c5-102">"There was an error validating access token" error during Desktop Analytics onboarding</span></span>

<span data-ttu-id="4c9c5-103">Dieser Fehler wird normalerweise beobachtet, wenn das Authentifizierungstoken abläuft.</span><span class="sxs-lookup"><span data-stu-id="4c9c5-103">This error is normally observed when the authentication token expires.</span></span> <span data-ttu-id="4c9c5-104">In der Regel wird durch das Aktualisieren der Seite das Token aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="4c9c5-104">Usually, refreshing the page refreshes the token.</span></span> <span data-ttu-id="4c9c5-105">Dieses Problem kann jedoch bestehen bleiben, wenn auf das Konto, das für die on-Board-Desktop Analyse verwendet wird, bedingte Zugriffsrichtlinien angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="4c9c5-105">However, this issue can persist if there are any Conditional Access policies applied to the account being used to on-board Desktop Analytics.</span></span> <span data-ttu-id="4c9c5-106">Sie können die Azure AD Anmelde Protokolle im Azure-Portal überprüfen, um festzustellen, ob Anmeldefehler für das für das Onboarding von Desktop Analytics verwendete Konto vorliegen.</span><span class="sxs-lookup"><span data-stu-id="4c9c5-106">You can review the Azure AD Sign In logs in the Azure Portal to see if there are any sign-in failures for the account being used for Desktop Analytics onboarding.</span></span>

<span data-ttu-id="4c9c5-107">Weitere Informationen zum bedingten Zugriff finden Sie unter [Planen der Bereitstellung für bedingten Zugriff](https://docs.microsoft.com/azure/active-directory/conditional-access/plan-conditional-access).</span><span class="sxs-lookup"><span data-stu-id="4c9c5-107">For more information about Conditional Access, visit [Plan your Conditional Access deployment](https://docs.microsoft.com/azure/active-directory/conditional-access/plan-conditional-access).</span></span>