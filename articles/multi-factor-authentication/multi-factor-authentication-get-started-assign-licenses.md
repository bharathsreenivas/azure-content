<properties
	pageTitle="Assign Licenses for Azure MFA | Microsoft Azure"
	description="Learn  how to assign user licenses for Microsoft Azure Multi-Factor Authentication."
	services="multi-factor-authentication"
	documentationCenter=""
	authors="kgremban"
	manager="femila"
	editor="yossib"/>

<tags
	ms.service="multi-factor-authentication"
	ms.workload="identity"
	ms.tgt_pltfrm="na"
	ms.devlang="na"
	ms.topic="get-started-article"
	ms.date="10/17/2016"
	ms.author="kgremban"/>

# Assigning an Azure MFA, Azure AD Premium, or Enterprise Mobility license to users

If you have purchased Azure MFA, Azure AD Premium, or Enterprise Mobility Suite licenses, you do not need to create a Multi-Factor Auth provider. Once you assign the licenses to your users, you can begin enabling them for MFA.

## To assign a license

1. Sign in to the [Azure classic portal](https://manage.windowsazure.com) as an administrator.
2. On the left, select **Active Directory**.
3. On the Active Directory page, double-click the directory that has the users you wish to enable.
4. At the top of the directory page, select **Licenses**.
![Assign Licenses](./media/multi-factor-authentication-get-started-assign-licenses/assign1.png)
5. On the Licenses page, select **Azure Multi-Factor Authentication**, **Active Directory Premium**, or **Enterprise Mobility Suite**.  If you only have one, then it should be selected automatically.
6. At the bottom of the page, click **Assign**.
![Assign Licenses](./media/multi-factor-authentication-get-started-assign-licenses/assign3.png)
6. In the box that comes up, click next to the users or groups you want to assign licenses to.  You should see a green check mark appear.
7. Click the check mark icon to save the changes.
![Assign Licenses](./media/multi-factor-authentication-get-started-assign-licenses/assign4.png)
8. You should see a message saying how many licenses were assigned and how many may have failed.  Click **Ok**.
![Assign Licenses](./media/multi-factor-authentication-get-started-assign-licenses/assign5.png)
