---
title: Behandeln von Problemen im Zusammenhang mit Benutzern
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 01/15/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "7813"
- "9004358"
ms.openlocfilehash: d9964e50bdea0c41ac14ab3783b579034b5f2c8c
ms.sourcegitcommit: 6d02eb533fd74199af6b20f714b3720991da2c4a
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/18/2021
ms.locfileid: "49886852"
---
# <a name="announcements"></a><span data-ttu-id="cb6d9-102">Ankündigungen</span><span class="sxs-lookup"><span data-stu-id="cb6d9-102">Announcements</span></span>

<span data-ttu-id="cb6d9-103">Folgen Sie den Anweisungen von Google zum Testen der Kompatibilität, um zu testen, ob Ihre Apps betroffen sind.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-103">Follow Google's guidance on testing compatibility to test whether your apps are affected.</span></span> <span data-ttu-id="cb6d9-104">Die Anleitungen von Google finden Sie unter https://docs.microsoft.com/azure/active-directory/external-identities/google-federation#deprecation-of-webview-sign-in-support.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-104">Google's guidance is available in https://docs.microsoft.com/azure/active-directory/external-identities/google-federation#deprecation-of-webview-sign-in-support.</span></span>

<span data-ttu-id="cb6d9-105">Verwenden Sie die Systemwebansicht oder den Systembrowser, wenn Sie Ihre Benutzer mit Google-Privatanwenderkonten anmelden.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-105">Ensure you use the system webview or system browser when signing in your users with consumer Google accounts.</span></span> <span data-ttu-id="cb6d9-106">Weitere Informationen finden Sie unter [Probleme bei der Anmeldung bei Anwendungen (nur Chrome-Browser)](https://docs.microsoft.com/office365/troubleshoot/miscellaneous/chrome-behavior-affects-applications).</span><span class="sxs-lookup"><span data-stu-id="cb6d9-106">For more information, see [Issues signing in to application(s) using Chrome browser only](https://docs.microsoft.com/office365/troubleshoot/miscellaneous/chrome-behavior-affects-applications).</span></span>


<span data-ttu-id="cb6d9-107">**Ich kann keinen neuen Benutzer in meinem Azure AD-Verzeichnis erstellen**</span><span class="sxs-lookup"><span data-stu-id="cb6d9-107">**I can't create a new user in my Azure AD directory**</span></span>

<span data-ttu-id="cb6d9-108">Führen Sie die folgenden Schritte aus, wenn keine neuen Benutzer in Azure AD erstellt werden können:</span><span class="sxs-lookup"><span data-stu-id="cb6d9-108">To troubleshoot the issue of not being able to create a new user in Azure AD, perform the following steps:</span></span>

1. <span data-ttu-id="cb6d9-109">Vergewissern Sie sich, dass Sie berechtigt sind, einen neuen Standardbenutzer zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-109">Ensure that you are authorized to create a new standard user.</span></span> <span data-ttu-id="cb6d9-110">Nur wer über die Rolle eines globalen Administrators oder Benutzeradministrators in Azure Active Directory (AD) verfügt, kann einen neuen Standardbenutzer erstellen.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-110">Only the global administrator or user administrator role in Azure Active Directory (AD) can create a new standard user.</span></span> <span data-ttu-id="cb6d9-111">Wenn Sie keine dieser Rollen besitzen, bitten Sie einen Administrator, Sie einer dieser Rollen hinzuzufügen oder das neue Benutzerkonto für Sie zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-111">If you're not in one of these roles, ask an administrator to add you to one of these roles or to create the new user account for you.</span></span>
2. <span data-ttu-id="cb6d9-112">Stellen Sie sicher, dass der Benutzername zu der Domäne gehört, die in Azure AD verifiziert wurde.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-112">Ensure that the user name is in a domain that is verified in your Azure AD.</span></span> <span data-ttu-id="cb6d9-113">Wenn es in Azure AD keine verifizierten benutzerdefinierten Domänennamen gibt, können Sie Ihre anfängliche Azure AD-Domäne verwenden, welche mit "\*.onmicrosoft.com" endet.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-113">If you do not have any verified custom domain names in your Azure AD, you can use your Azure AD initial domain, which ends with \*.onmicrosoft.com.</span></span>
3. <span data-ttu-id="cb6d9-114">Stellen Sie sicher, dass der Benutzername zu einer Domäne gehört, die nicht mit Azure AD über Ihr lokales AD verbunden ist.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-114">Ensure that the user name is in a domain that is not federated to Azure AD from your on-premises AD.</span></span> <span data-ttu-id="cb6d9-115">Benutzer mit über lokale Umgebungen verbundenen Domänennamen können nicht in der Cloud hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-115">Users cannot be added in the cloud with domain names that are federated from on-premises.</span></span>
4. <span data-ttu-id="cb6d9-116">Stellen Sie sicher, dass noch kein anderer Benutzer oder Kontakt den Benutzernamen aufweist, den Sie dem neuen Benutzer zuweisen möchten.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-116">Ensure that no other user or contact already has the user name that you want to assign to the new user.</span></span> <span data-ttu-id="cb6d9-117">Benutzernamen müssen in Azure AD eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-117">User names must be unique across Azure AD.</span></span>
5. <span data-ttu-id="cb6d9-118">Weitere Informationen für Ihr Azure AD finden Sie unter [Azure AD-Rollen und -Administratoren](https://ms.portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/RolesAndAdministrators).</span><span class="sxs-lookup"><span data-stu-id="cb6d9-118">See [Azure AD roles and administrators](https://ms.portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/RolesAndAdministrators) for your Azure AD.</span></span>
6. <span data-ttu-id="cb6d9-119">Informieren Sie sich über die [Domänennamen,](https://ms.portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/Domains) für Ihr Azure AD.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-119">See the [domain names](https://ms.portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/Domains) for your Azure AD.</span></span>
7. <span data-ttu-id="cb6d9-120">Überprüfen Sie die [Überwachungsprotokolle](https://ms.portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/Audit), um detailliertere Informationen zu einem kürzlich erstellten oder gelöschten Benutzer zu erhalten, z. B. wer die Aktion ausgeführt hat und wann.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-120">Review [Audit logs](https://ms.portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/Audit) to see more detailed information about a recently created or deleted user like who performed the action and when.</span></span>
8. <span data-ttu-id="cb6d9-121">Weitere Informationen zum Hinzufügen neuer Benutzer finden Sie unter [Verwenden des Azure-Portals zum Erstellen eines neuen Benutzers in Azure AD](https://docs.microsoft.com/azure/active-directory/fundamentals/add-users-azure-active-directory) .</span><span class="sxs-lookup"><span data-stu-id="cb6d9-121">For more information on adding new users, see [Use the Azure portal to create a new user in your Azure AD](https://docs.microsoft.com/azure/active-directory/fundamentals/add-users-azure-active-directory) .</span></span>
9. <span data-ttu-id="cb6d9-122">Weitere Informationen zu Administratorrollenberechtigungen in Azure AD finden Sie unter [Administratorrollen für Azure AD](https://docs.microsoft.com/azure/active-directory/roles/permissions-reference).</span><span class="sxs-lookup"><span data-stu-id="cb6d9-122">For more information on administrator role permissions in Azure AD, see [Azure AD administrative roles](https://docs.microsoft.com/azure/active-directory/roles/permissions-reference).</span></span>
10. <span data-ttu-id="cb6d9-123">Details zum Erstellen eines Benutzers mithilfe von Azure AD PowerShell finden Sie unter [Azure AD PowerShell zum Erstellen eines neuen Benutzers](https://docs.microsoft.com/powershell/module/azuread/new-azureaduser).</span><span class="sxs-lookup"><span data-stu-id="cb6d9-123">For details on creating a user using Azure AD Powershell, see [Azure AD PowerShell to create a new user](https://docs.microsoft.com/powershell/module/azuread/new-azureaduser).</span></span>

<span data-ttu-id="cb6d9-124">**Probleme bei der Self-Service-Registrierung**</span><span class="sxs-lookup"><span data-stu-id="cb6d9-124">**Problem with self-service sign up**</span></span>

<span data-ttu-id="cb6d9-125">Führen Sie die folgenden Schritte aus, um Probleme im Zusammenhang mit der Self-Service-Registrierung zu behandeln:</span><span class="sxs-lookup"><span data-stu-id="cb6d9-125">To troubleshoot issues regarding self-service sign up, perform the following steps:</span></span>

1. <span data-ttu-id="cb6d9-126">Um die Self-Service-Registrierung mit Ihren Anwendungen zu verwenden, aktivieren Sie zuerst die Self-Service-Registrierung für Ihren Mandanten.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-126">To use self-service sign-up with your applications, first enable self-service sign-up for your tenant.</span></span> 
2. <span data-ttu-id="cb6d9-127">Wenn Sie eine Anwendung für die Unterstützung der Self-Service-Registrierung aktivieren möchten, fügen Sie sie Ihrem Benutzerablauf hinzu.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-127">To enable an application to support self-service sign up, add it to your user flow .</span></span> <span data-ttu-id="cb6d9-128">Wenn Sie das nächste Mal zur Anmeldeseite für diese Anwendung wechseln, wird die folgende Option angezeigt: \**_Noch kein Konto? Erstellen Sie eines!_* _.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-128">The next time you go to the login page for that application, you'll see an option \**_No account? Create one!_* _.</span></span> <span data-ttu-id="cb6d9-129">Dadurch wird der Self-Service-Registrierungsvorgang gestartet.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-129">This starts the self-service sign-up process.</span></span>
3. <span data-ttu-id="cb6d9-130">Informationen zum Verwenden der Self-Service-Registrierung für das Ausfüllen einer Organisation in Azure AD finden Sie unter [Self-Service-Registrierung für Azure AD](https://docs.microsoft.com/azure/active-directory/enterprise-users/directory-self-service-signup).</span><span class="sxs-lookup"><span data-stu-id="cb6d9-130">For information on how to use self-service sign up to populate an organization in Azure AD, see [Self-service sign up for Azure AD](https://docs.microsoft.com/azure/active-directory/enterprise-users/directory-self-service-signup).</span></span>
4. <span data-ttu-id="cb6d9-131">Nachdem Sie den Benutzerablauf einer oder mehreren Anwendungen zugeordnet haben, können sich Benutzer, die diese App besuchen, mithilfe der im Benutzerablauf konfigurierten Optionen registrieren und ein Gastkonto erhalten.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-131">Once you associate the user flow with one or more applications, users who visit that app will be able to sign up and gain a guest account using the options configured in the user flow.</span></span> <span data-ttu-id="cb6d9-132">Weitere Informationen zum Registrieren und Erhalten eines Gastkontos finden die Benutzer unter [Self-Service-Registrierung für Gastbenutzer](https://docs.microsoft.com/azure/active-directory/external-identities/self-service-sign-up-user-flow).</span><span class="sxs-lookup"><span data-stu-id="cb6d9-132">For more information on signing up and gaining a guest account, the users can see [Self-service sign-up for guest users](https://docs.microsoft.com/azure/active-directory/external-identities/self-service-sign-up-user-flow).</span></span>

<span data-ttu-id="cb6d9-133">_ *Probleme beim Einladen externer Benutzer*\*</span><span class="sxs-lookup"><span data-stu-id="cb6d9-133">_ *Problem inviting an external user*\*</span></span>

<span data-ttu-id="cb6d9-134">Führen Sie den folgenden Schritt aus, um Probleme beim Einladen eines externen Benutzers zu behandeln:</span><span class="sxs-lookup"><span data-stu-id="cb6d9-134">To troubleshoot issues regarding inviting an external user, perform the following step:</span></span>

<span data-ttu-id="cb6d9-135">Stellen Sie sicher, dass Sie die Einladung eines Benutzers an die E-Mail-Adresse senden, die dem Namen entspricht, mit dem sich der Benutzer anmeldet.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-135">Ensure that you send a user's invitation to the email address that matches the name that the user signs in with.</span></span> <span data-ttu-id="cb6d9-136">Wenn Sie die Einladung an die Proxy-E-Mail-Adresse eines Benutzers senden, kann der Benutzer sie nicht nutzen.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-136">If you send the invitation to a user's proxy email address, the user can't redeem it.</span></span> <span data-ttu-id="cb6d9-137">Weitere Informationen finden Sie in der [Dokumentation zu Azure Active Directory B2B](https://docs.microsoft.com/azure/active-directory/external-identities/).</span><span class="sxs-lookup"><span data-stu-id="cb6d9-137">For more information, see [Azure AD B2B documentation](https://docs.microsoft.com/azure/active-directory/external-identities/).</span></span>

<span data-ttu-id="cb6d9-138">**Ich kann einem Benutzer keine Lizenzen zuweisen**</span><span class="sxs-lookup"><span data-stu-id="cb6d9-138">**I can't assign licenses to a user**</span></span>

<span data-ttu-id="cb6d9-139">Führen Sie die folgenden Schritte aus, um Probleme im Zusammenhang mit dem Zuweisen von Lizenzen an Benutzer zu behandeln:</span><span class="sxs-lookup"><span data-stu-id="cb6d9-139">To troubleshoot issues regarding assigning licenses to a user, perform the following steps:</span></span>

1. <span data-ttu-id="cb6d9-140">Stellen Sie sicher, dass Sie zum Verwalten von Benutzerlizenzen ein Konto mit einer der dazu erforderlichen Administratorrollen verwenden: globaler Administrator, Lizenzadministrator oder Benutzeradministrator.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-140">To manage user licenses, ensure that you use an account with one of the required administrator roles: global administrator, license administrator, or user administrator.</span></span> <span data-ttu-id="cb6d9-141">Sie können die Rolle des Benutzers auf der Registerkarte **Verzeichnisrolle** im "Benutzer"-Bereich überprüfen.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-141">You can check the user’s role in the **Directory role** tab on the user blade.</span></span>
2. <span data-ttu-id="cb6d9-142">Wenn Sie gerade das Azure-Portal verwenden und die Lizenzzuweisung fehlschlägt, klicken Sie auf die Benachrichtigung in der oberen rechten Ecke.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-142">If you are using the Azure portal and license assignment is failing, click the notification in the upper-right corner.</span></span> <span data-ttu-id="cb6d9-143">Damit wird ein Bereich mit Details zu dem Fehler geöffnet.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-143">This opens a blade with details about what went wrong.</span></span> <span data-ttu-id="cb6d9-144">In den meisten Fällen reicht dies aus, um das Problem zu verstehen und es beheben zu können.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-144">In most cases that is enough to understand and resolve the problem.</span></span>
3. <span data-ttu-id="cb6d9-145">Bevor einem Benutzer eine Lizenz zugewiesen werden kann, muss die Eigenschaft **Verwendungsort** für den Benutzer festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-145">Before a license can be assigned to a user, ensure that the **Usage Location** property is set for the user.</span></span> <span data-ttu-id="cb6d9-146">Vergewissern Sie sich, dass diese Eigenschaft für den Benutzer festgelegt wurde, indem Sie die Registerkarte **Profil** im "Benutzer"-Bereich überprüfen.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-146">Verify the user has that property set by viewing the **Profile** tab on the user blade.</span></span>
4. <span data-ttu-id="cb6d9-147">Vergewissern Sie sich, dass ausreichend Lizenzen für das Produkt verfügbar sind, das Sie zuweisen möchten.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-147">Ensure there are enough available licenses for the product you are trying to assign.</span></span> <span data-ttu-id="cb6d9-148">Sie können die Anzahl der verfügbaren Lizenzen im Azure-Portal unter [Azure Active Directory -> Lizenzen -> Alle Produkte](https://ms.portal.azure.com/#blade/Microsoft_AAD_IAM/LicensesMenuBlade/Products) einsehen.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-148">You can see the number of available licenses in the Azure portal, at [Azure Active Directory -> Licenses -> All products](https://ms.portal.azure.com/#blade/Microsoft_AAD_IAM/LicensesMenuBlade/Products).</span></span>
5. <span data-ttu-id="cb6d9-149">Möglicherweise verfügt der Benutzer bereits über eine andere Lizenz, deren Dienste mit denen in der neuen Lizenz in Konflikt stehen, die Sie zuweisen möchten.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-149">The user may already have another license whose services conflict with those in the new license you are trying to assign.</span></span> <span data-ttu-id="cb6d9-150">Wenn für den Benutzer beispielsweise der Exchange Online-Dienst (Plan 1) aktiviert wurde, können Sie ihm keine Lizenz mit dem Exchange Online-Dienst (Plan 2) zuweisen.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-150">For example, if the user has the Exchange Online (Plan 1) service enabled, you won’t be able to assign a license with the Exchange Online (Plan 2).</span></span> <span data-ttu-id="cb6d9-151">Deaktivieren Sie einen der Dienste, um die neue Lizenzzuweisung zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-151">Disable one of the services to allow the new license assignment.</span></span> <span data-ttu-id="cb6d9-152">Falls Sie das Azure-Portal oder PowerShell-Cmdlets verwenden, werden auf der Seite zu den **Problemdetails** die Dienste aufgeführt, die den Konflikt verursachen.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-152">If you are using the Azure portal or PowerShell cmdlets, the **problem details** page lists the specific services that are causing the conflict.</span></span>
6. <span data-ttu-id="cb6d9-153">Wenn das Entfernen einer Lizenz fehlschlägt, verfügt der Benutzer möglicherweise über weitere Lizenzen mit Diensten, die von den Diensten abhängen, die Sie entfernen möchten.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-153">If you are trying to remove a license and that is failing, the user might have other licenses with services that depend on the services you are trying to remove.</span></span> <span data-ttu-id="cb6d9-154">Falls Sie das Azure-Portal oder PowerShell-Cmdlets verwenden, werden in der Fehlermeldung die Dienste aufgeführt, die Abhängigkeiten aufweisen.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-154">If you are using the Azure portal or PowerShell cmdlets, the error message will list the specific services that have dependencies.</span></span>
7. <span data-ttu-id="cb6d9-155">Wenn Sie verstehen möchten, warum eine Lizenz für einen Benutzer hinzugefügt/entfernt wurde (beispielsweise, wer sonst noch in Ihrer Organisation Änderungen vorgenommen hat), überprüfen Sie die Überwachungsprotokolle.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-155">If you want to understand why a license was added/removed from a user (for example, who else in your organization may have made changes), check the audit logs.</span></span> <span data-ttu-id="cb6d9-156">Legen Sie den Filter auf **Lizenzaktivitäten** fest, um alle Änderungen, einschließlich derjenigen Person, die sie vorgenommen hat, anzeigen zu lassen.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-156">Set the filter to **license activities** to show all modifications, including the "actor" that performed them.</span></span>
8. <span data-ttu-id="cb6d9-157">Falls Sie Exchange Online verwenden, wurden einige Benutzer in Ihrem Mandanten möglicherweise nicht ordnungsgemäß mit demselben Proxyadresswert konfiguriert.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-157">If you are using Exchange Online, some users in your tenant may be incorrectly configured with the same proxy address value.</span></span> <span data-ttu-id="cb6d9-158">In solchen Fällen werden möglicherweise allgemeine Fehlermeldungen angezeigt, wenn ein Lizenzvorgang fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="cb6d9-158">In such cases, you may see generic error messages when a license operation fails.</span></span> <span data-ttu-id="cb6d9-159">[Dieser Artikel](https://docs.microsoft.com/exchange/troubleshoot/administration/proxy-address-being-used) enthält weitere Informationen zu diesem Problem, einschließlich Details zum [Herstellen einer Verbindung mit Exchange Online mithilfe von Remote-PowerShell](https://docs.microsoft.com/powershell/exchange/connect-to-exchange-online-powershell). Um zu ermitteln, welche Benutzer in Ihrem Mandanten dieselbe Proxyadresse aufweisen, führen Sie dieses Exchange Online-Cmdlet aus:</span><span class="sxs-lookup"><span data-stu-id="cb6d9-159">[This article](https://docs.microsoft.com/exchange/troubleshoot/administration/proxy-address-being-used) contains more information about this problem, including information on [how to connect to Exchange Online using remote PowerShell](https://docs.microsoft.com/powershell/exchange/connect-to-exchange-online-powershell).To identify which users in your tenant, contain the same proxy address, execute this Exchange Online cmdlet:</span></span>

<span data-ttu-id="cb6d9-160">Ausführen</span><span class="sxs-lookup"><span data-stu-id="cb6d9-160">Run</span></span>

<span data-ttu-id="cb6d9-161">Get-Recipient | where {$_.EmailAddresses -match <user principal name>} | fL Name, RecipientType,emailaddresses</span><span class="sxs-lookup"><span data-stu-id="cb6d9-161">Get-Recipient | where {$_.EmailAddresses -match <user principal name>} | fL Name, RecipientType,emailaddresses</span></span>




