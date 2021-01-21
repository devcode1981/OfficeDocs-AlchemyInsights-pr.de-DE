---
title: App-Proxy-Konfiguration
ms.author: v-jmathew
author: v-jmathew
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004356"
- "7800"
ms.openlocfilehash: 0b782705afa8eab338687590baff90de4e17ccb9
ms.sourcegitcommit: 83fe2a8d060794fdf58445b469b30a3294b7a9b6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 01/15/2021
ms.locfileid: "49876558"
---
# <a name="app-proxy-configuration"></a><span data-ttu-id="b141b-102">App-Proxy-Konfiguration</span><span class="sxs-lookup"><span data-stu-id="b141b-102">App Proxy Configuration</span></span>

1. <span data-ttu-id="b141b-103">Informationen zum Konfigurieren einer Anwendungsproxyanwendung in Azure AD, um Ihre lokalen Anwendungen in der Cloud verfügbar zu machen, finden Sie unter Konfigurieren einer [Anwendungsproxyanwendung.](https://docs.microsoft.com/azure/active-directory/application-proxy-config-how-to)</span><span class="sxs-lookup"><span data-stu-id="b141b-103">To understand how to configure an Application Proxy application within Azure AD to expose your on-premises applications to the cloud, see [How to configure an Application Proxy application](https://docs.microsoft.com/azure/active-directory/application-proxy-config-how-to).</span></span>
2. <span data-ttu-id="b141b-104">Einmaliges Anmelden (Single Sign-On, SSO) ermöglicht Ihren Benutzern den Zugriff auf eine Anwendung, ohne sich mehrmals authentifizieren zu müssen.</span><span class="sxs-lookup"><span data-stu-id="b141b-104">Single sign-on (SSO) allows your users to access an application without authenticating multiple times.</span></span> <span data-ttu-id="b141b-105">Sie ermöglicht die einmalige Authentifizierung in der Cloud, für Azure Active Directory und ermöglicht es dem Dienst oder Connector, die Identität des Benutzers anzunehmen, um alle zusätzlichen Authentifizierungsanforderungen der Anwendung zu bewältigen.</span><span class="sxs-lookup"><span data-stu-id="b141b-105">It allows the single authentication to occur in the cloud, against Azure Active Directory, and allows the service or Connector to impersonate the user to complete any additional authentication challenges from the application.</span></span> <span data-ttu-id="b141b-106">Weitere Informationen finden Sie unter [Konfigurieren des einmaligen Anmeldens bei einer Anwendungsproxyanwendung.](https://docs.microsoft.com/azure/active-directory/application-proxy-config-sso-how-to)</span><span class="sxs-lookup"><span data-stu-id="b141b-106">To learn more, see [How to configure single sign-on to an Application Proxy application](https://docs.microsoft.com/azure/active-directory/application-proxy-config-sso-how-to).</span></span>
3. <span data-ttu-id="b141b-107">Verwenden [Sie diesen Artikel,](https://docs.microsoft.com/azure/active-directory/application-proxy-config-problem) um häufige Probleme zu behandeln, die beim Erstellen einer neuen Anwendungsproxyanwendung auftreten.</span><span class="sxs-lookup"><span data-stu-id="b141b-107">Use [this article](https://docs.microsoft.com/azure/active-directory/application-proxy-config-problem) to troubleshoot common issues people face when creating a new application proxy application.</span></span>
4. <span data-ttu-id="b141b-108">Wenn sie ein Problem beim Einrichten der Back-End-Authentifizierung für Ihre Anwendung haben, müssen Sie möglicherweise die Konfigurationen der eingeschränkten [Kerberos-Delegierung für](https://docs.microsoft.com/azure/active-directory/application-proxy-back-end-kerberos-constrained-delegation-how-to) Anwendungsproxy behandeln oder anleitungen zum Konfigurieren der Anwendung mit [PingAccess](https://docs.microsoft.com/azure/active-directory/application-proxy-back-end-ping-access-how-to) befolgen, um das Problem zu beheben.</span><span class="sxs-lookup"><span data-stu-id="b141b-108">If you are having a problem setting up back-end authentication to your application you may need to [Troubleshoot Kerberos constrained delegation configurations for Application Proxy](https://docs.microsoft.com/azure/active-directory/application-proxy-back-end-kerberos-constrained-delegation-how-to) or follow guidance on [configuring application with PingAccess](https://docs.microsoft.com/azure/active-directory/application-proxy-back-end-ping-access-how-to) to resolve your issue.</span></span>