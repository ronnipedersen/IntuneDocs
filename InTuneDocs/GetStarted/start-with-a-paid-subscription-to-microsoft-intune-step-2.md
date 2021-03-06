---
# required metadata

title: Configure a custom domain name | Microsoft Intune
description: Add a custom domain name for your Intune subscription
keywords:
author: nathbarnms.author: nathbarn
manager: angrobe
ms.date: 08/29/2016
ms.topic: get-started-article
ms.prod:
ms.service: microsoft-intune
ms.technology:
ms.assetid: 2382f36f-13d8-4a32-81ad-6cfa604889c3

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: jeffgilb
ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom:

---


# Configure a custom domain name

By default, Intune uses the **<domain>.onmicrosoft.com** domain name that was created when you first subscribed to the service. When your organization owns a custom domain, you can configure your instance of Intune to use that domain instead of the domain name provided with your subscription.

Before you create new user accounts or synchronize accounts from your on-premises Active Directory, we strongly recommend that you decide whether to use only the .onmicrosoft.com domain or to add one or more of your custom domain names. Configuring a custom domain before adding users can help simplify the management of user identities for your subscription by enabling users to sign in with the credentials they use to access other domain resources.

When you subscribe to a cloud-based service from Microsoft, your instance of that service becomes a Microsoft  [Azure AD tenant](http://technet.microsoft.com/library/jj573650.aspx#BKMK_WhatIsAnAzureADTenant), which provides identity and directory services for your cloud-based service. And, because the tasks to configure Intune to use your organizations custom domain name are the same as for other Azure AD tenants, you can use the information and procedures found in [Add your domain](https://azure.microsoft.com/documentation/articles/active-directory-add-domain/).

> [!TIP]
> For more information about using your custom domain with a cloud-based service from Microsoft, see [Conceptual overview of custom domain names in Azure Active Directory](https://azure.microsoft.com/documentation/articles/active-directory-add-domain-concepts/).

### Next steps
Congratulations! You have just completed step 2 of the *Intune quick start guide*.

>[!div class="step-by-step"]

>[&larr; **Sign in to Intune**](.\start-with-a-paid-subscription-to-microsoft-intune-step-1.md)     [**Add users to Intune** &rarr;](.\start-with-a-paid-subscription-to-microsoft-intune-step-3.md)  
