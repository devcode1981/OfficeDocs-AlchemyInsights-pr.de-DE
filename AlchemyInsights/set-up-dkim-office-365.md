---
title: Einrichten von DKIM in Office 365
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1388
ms.assetid: ''
ms.openlocfilehash: 0f81fe02135f3d0901ffe5a26d7aa3dad70c3770
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/07/2019
ms.locfileid: "34765077"
---
# <a name="setup-dkim-in-office-365"></a><span data-ttu-id="0e249-102">Einrichten von DKIM in Office 365</span><span class="sxs-lookup"><span data-stu-id="0e249-102">Setup DKIM in Office 365</span></span>

<span data-ttu-id="0e249-103">Die vollständigen Anweisungen zum Konfigurieren von DKIM für benutzerdefinierte Domänen in Office 365 finden Sie [hier](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).</span><span class="sxs-lookup"><span data-stu-id="0e249-103">The complete instructions for configuring DKIM for custom domains in Office 365 are [here](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).</span></span>

1. <span data-ttu-id="0e249-104">Für **jede** benutzerdefinierte Domäne müssen Sie **zwei** DKIM-CNAME-Einträge im DNS-Hostingdienst Ihrer Domäne erstellen (in der Regel die Domänenregistrierungsstelle).</span><span class="sxs-lookup"><span data-stu-id="0e249-104">For **each** custom domain, you need to create **two** DKIM CNAME records at your domain's DNS hosting service (typically, the domain registrar).</span></span> <span data-ttu-id="0e249-105">Für contoso.com und fourthcoffee.com sind beispielsweise vier DKIM-CNAME-Einträge erforderlich: zwei für contoso.com und zwei für fourthcoffee.com.</span><span class="sxs-lookup"><span data-stu-id="0e249-105">For example, contoso.com and fourthcoffee.com require four DKIM CNAME records: two for contoso.com and two for fourthcoffee.com.</span></span>

   <span data-ttu-id="0e249-106">Die DKIM-CNAME-Einträge für **jede** benutzerdefinierte Domäne verwenden die folgenden Formate:</span><span class="sxs-lookup"><span data-stu-id="0e249-106">The DKIM CNAME records for **each** custom domain use the following formats:</span></span>

   - <span data-ttu-id="0e249-107">**Hostname**:`selector1._domainkey.<CustomDomain>`</span><span class="sxs-lookup"><span data-stu-id="0e249-107">**Host name**: `selector1._domainkey.<CustomDomain>`</span></span>

     <span data-ttu-id="0e249-108">**Verweist auf Adresse oder Wert**:`selector1-<DomainGUID>._domainkey.<InitialDomain>`</span><span class="sxs-lookup"><span data-stu-id="0e249-108">**Points to address or value**: `selector1-<DomainGUID>._domainkey.<InitialDomain>`</span></span>

     <span data-ttu-id="0e249-109">**TTL**: 3600</span><span class="sxs-lookup"><span data-stu-id="0e249-109">**TTL**: 3600</span></span>

   - <span data-ttu-id="0e249-110">**Hostname**:`selector2._domainkey.<CustomDomain>`</span><span class="sxs-lookup"><span data-stu-id="0e249-110">**Host name**: `selector2._domainkey.<CustomDomain>`</span></span>

     <span data-ttu-id="0e249-111">**Verweist auf Adresse oder Wert**:`selector2-<DomainGUID>._domainkey.<InitialDomain>`</span><span class="sxs-lookup"><span data-stu-id="0e249-111">**Points to address or value**: `selector2-<DomainGUID>._domainkey.<InitialDomain>`</span></span>

     <span data-ttu-id="0e249-112">**TTL**: 3600</span><span class="sxs-lookup"><span data-stu-id="0e249-112">**TTL**: 3600</span></span>

   <span data-ttu-id="0e249-113">\<DomainGUID\> ist der Text Links `.mail.protection.outlook.com` neben dem angepassten MX-Eintrag für die benutzerdefinierte Domäne (beispielsweise `contoso-com` für die Domäne contoso.com).</span><span class="sxs-lookup"><span data-stu-id="0e249-113">\<DomainGUID\> is the text to the left of `.mail.protection.outlook.com` in the customized MX record for the custom domain (for example, `contoso-com` for the domain contoso.com).</span></span> <span data-ttu-id="0e249-114">\<InitialDomain\> ist die Domäne, die Sie bei der Registrierung für Office 365 verwendet haben (beispielsweise contoso.onmicrosoft.com).</span><span class="sxs-lookup"><span data-stu-id="0e249-114">\<InitialDomain\> is the domain you used when you signed up for Office 365 (for example, contoso.onmicrosoft.com).</span></span>

2. <span data-ttu-id="0e249-115">Nachdem Sie die CNAME-Einträge für Ihre benutzerdefinierten Domänen erstellt haben, führen Sie die folgenden Schritte aus:</span><span class="sxs-lookup"><span data-stu-id="0e249-115">After you've created the CNAME records for your custom domains, complete the following instructions:</span></span>

   <span data-ttu-id="0e249-116">a.</span><span class="sxs-lookup"><span data-stu-id="0e249-116">a.</span></span> <span data-ttu-id="0e249-117">[Melden Sie sich bei Office 365](https://support.office.microsoft.com/article/e9eb7d51-5430-4929-91ab-6157c5a050b4) mit Ihrem Firmen- oder Schulkonto an.</span><span class="sxs-lookup"><span data-stu-id="0e249-117">[Sign in to Office 365](https://support.office.microsoft.com/article/e9eb7d51-5430-4929-91ab-6157c5a050b4) with your work or school account.</span></span>

   <span data-ttu-id="0e249-118">b.</span><span class="sxs-lookup"><span data-stu-id="0e249-118">b.</span></span> <span data-ttu-id="0e249-119">Klicken Sie oben links auf das App-Startsymbol, und wählen Sie **Admin** aus.</span><span class="sxs-lookup"><span data-stu-id="0e249-119">Select the app launcher icon in the upper-left and choose **Admin**.</span></span>

   <span data-ttu-id="0e249-120">c.</span><span class="sxs-lookup"><span data-stu-id="0e249-120">c.</span></span> <span data-ttu-id="0e249-121">Erweitern Sie im unteren linken Navigationsbereich **Admin**, und klicken Sie dann auf **Exchange**.</span><span class="sxs-lookup"><span data-stu-id="0e249-121">In the lower-left navigation, expand **Admin** and choose **Exchange**.</span></span>

   <span data-ttu-id="0e249-122">d.</span><span class="sxs-lookup"><span data-stu-id="0e249-122">d.</span></span> <span data-ttu-id="0e249-123">Wechseln Sie zu **Protection** > **DKIM**.</span><span class="sxs-lookup"><span data-stu-id="0e249-123">Go to **Protection** > **DKIM**.</span></span>

   <span data-ttu-id="0e249-124">e.</span><span class="sxs-lookup"><span data-stu-id="0e249-124">e.</span></span> <span data-ttu-id="0e249-125">Wählen Sie die Domäne aus, und wählen Sie dann für **Signieren Nachrichten für diese Domäne mit DKIM-Signaturen** **aktivieren** aus.</span><span class="sxs-lookup"><span data-stu-id="0e249-125">Select the domain and then choose **Enable** for **Sign messages for this domain with DKIM signatures**.</span></span> <span data-ttu-id="0e249-126">Wiederholen Sie diesen Schritt für jede benutzerdefinierte Domäne.</span><span class="sxs-lookup"><span data-stu-id="0e249-126">Repeat this step for each custom domain.</span></span>