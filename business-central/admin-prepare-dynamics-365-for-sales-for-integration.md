---
title: Integrating with Dynamics 365 for Sales| Microsoft Docs
description: Learn how to get Dynamics 365 Business Central ready to integrate with Dynamics 365 for Sales.
services: project-madeira
documentationcenter: ''
author: bholtorf
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: sales, crm, integration, integrating
ms.date: 04/01/2019
ms.author: bholtorf
ms.openlocfilehash: 991d8432c24b1963da019e3c8b665f9ad009d077
ms.sourcegitcommit: 60b87e5eb32bb408dd65b9855c29159b1dfbfca8
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 04/29/2019
ms.locfileid: "1247288"
---
# <a name="integrating-with-dynamics-365-for-sales"></a>Integrating with Dynamics 365 for Sales
The sales person role is often considered as one the most outward-facing jobs in a business. However, it can be helpful for sales people to be able to look inward in the business and see what is happening on the back end. By integrating [!INCLUDE[d365fin](includes/d365fin_md.md)] and [!INCLUDE[crm_md](includes/crm_md.md)], you can give your sales people that insight by enabling them to view information in [!INCLUDE[d365fin](includes/d365fin_md.md)] while they are working in [!INCLUDE[crm_md](includes/crm_md.md)]. For example, when preparing a sales quote it could be useful to know whether you have enough inventory to fulfil the order. For more information, see [Using Dynamics 365 for Sales from Business Central](marketing-integrate-dynamicscrm.md).

> [!Note]
> These steps describe the process of integrating online versions of [!INCLUDE[crm_md](includes/crm_md.md)] and [!INCLUDE[d365fin](includes/d365fin_md.md)].

<!--## Software Requirements
You must have an Office 365 subscription, and both [!INCLUDE[crm_md](includes/crm_md.md)] and [!INCLUDE[d365fin](includes/d365fin_md.md)] must be part of the same organization.  -->

## <a name="overview-of-the-integration-process"></a>Overview of the Integration Process
The following steps provide an overview of the steps to integrate [!INCLUDE[crm_md](includes/crm_md.md)] with [!INCLUDE[d365fin](includes/d365fin_md.md)].

> [!Note]  
> These tasks require the **System Administrator** security role in [!INCLUDE[crm_md](includes/crm_md.md)] and [!INCLUDE[d365fin](includes/d365fin_md.md)].  

1. In the Office 365 admin centre, set up a user account for connecting to and synchronising data with [!INCLUDE[crm_md](includes/crm_md.md)]. For more information, see [Setting Up Integration with Dynamics 365 for Sales](admin-setting-up-integration-with-dynamics-sales.md).

2. Assign licences for [!INCLUDE[crm_md](includes/crm_md.md)] to the [!INCLUDE[d365fin](includes/d365fin_md.md)] users who will use the integrated apps.

3. Set up a connection to [!INCLUDE[crm_md](includes/crm_md.md)]. For more information, see [Set Up a Connection to Dynamics 365 for Sales](admin-how-to-set-up-a-dynamics-crm-connection.md).  

4. Optional: Couple [!INCLUDE[d365fin](includes/d365fin_md.md)] and [!INCLUDE[crm_md](includes/crm_md.md)] records. For more information, see [Couple and Synchronise Records Manually](admin-how-to-couple-and-synchronize-records-manually.md).

5. Synchronise data between the apps. For more information, see [Synchronising Business Central and Dynamics 365 for Sales](admin-synchronizing-business-central-and-sales.md).  

## <a name="about-the-business-central-integration-solution"></a>About the Business Central Integration Solution
The solution lets people view information in [!INCLUDE[d365fin](includes/d365fin_md.md)] while they are working in [!INCLUDE[crm_md](includes/crm_md.md)]. For example, it can provide insights into customer statistics, allows users to couple and view records in [!INCLUDE[d365fin](includes/d365fin_md.md)] from [!INCLUDE[crm_md](includes/crm_md.md)], and allows people to see whether products are available in [!INCLUDE[d365fin](includes/d365fin_md.md)].

By default, the Set Up Dynamics 365 for Sales Connection assisted setup guide will import the [!INCLUDE[d365fin](includes/d365fin_md.md)] integration solution. To do that, the setup guide uses an administrator user account. This account must also be a valid user in [!INCLUDE[crm_md](includes/crm_md.md)] with the following security roles:

* System Administrator  
* Solution Customizer  

For more information, see [Setting Up User Accounts for Integrating with Dynamics 365 for Sales](admin-setting-up-integration-with-dynamics-sales.md), [Create users in Microsoft Dynamics 365 (online) and assign security roles](/dynamics365/customer-engagement/admin/create-users-assign-online-security-roles.md), and [Managing Users and Permissions](ui-how-users-permissions.md).  

This account is used only one time during the setup. After the solution is imported into [!INCLUDE[d365fin](includes/d365fin_md.md)] the account is no longer needed. Integration will continue to use the user account that was created specifically for the integration.

In addition to customising [!INCLUDE[crm_md](includes/crm_md.md)], the [!INCLUDE[d365fin](includes/d365fin_md.md)] integration solution also creates the following roles in [!INCLUDE[crm_md](includes/crm_md.md)] for the integration:

* **Integration Administrator** - Allows users to manage the connection between [!INCLUDE[d365fin](includes/d365fin_md.md)] and [!INCLUDE[crm_md](includes/crm_md.md)]. Typically assigned only to the user account for synchronisation.  
* **Integration User** - Allows users to access synchronised data. Typically assigned to the user account for synchronisation and any other user who needs to view or access the synchronised data.
* **Product Availability User** - Allows users to query product availability in [!INCLUDE[d365fin](includes/d365fin_md.md)] from [!INCLUDE[crm_md](includes/crm_md.md)].

At the end of the setup guide, [!INCLUDE[d365fin](includes/d365fin_md.md)] prompts you to couple sales people to users in [!INCLUDE[crm_md](includes/crm_md.md)]. Records in [!INCLUDE[crm_md](includes/crm_md.md)] usually have an owner (user) assigned to them, and if coupling between the user in [!INCLUDE[crm_md](includes/crm_md.md)] and the sales person in [!INCLUDE[d365fin](includes/d365fin_md.md)] does not exist, synchronisation will fail. You can also do this later by using the **Couple Salespersons** action on the **Microsoft Dynamics 365 Connection Setup** page.

## <a name="see-also"></a>See Also  
[Setting Up User Accounts for Integrating with Dynamics 365 for Sales](admin-setting-up-integration-with-dynamics-sales.md)  
[Set Up a Connection to Dynamics 365 for Sales](admin-how-to-set-up-a-dynamics-crm-connection.md)
[Synchronising Business Central and Dynamics 365 for Sales](admin-synchronizing-business-central-and-sales.md)