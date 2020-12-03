---
title: Working with Power BI Reports in Business Central| Microsoft Docs
description: Getting insight, business intelligence, and KPIs from your Business Central data is easy with the Business Central apps for Power BI.
author: jswymer
ms.service: dynamics365-business-central
ms.topic: get-started-article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: account schedule, analysis, reporting, financial report, business intelligence, KPI
ms.date: 10/01/2020
ms.author: jswymer
ms.openlocfilehash: 28e332137346aae320b73c326bb3a41d3b7e7097
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 10/01/2020
ms.locfileid: "3927205"
---
# <a name="working-with-power-bi-reports-in-prodshort"></a>Working with Power BI Reports in [!INCLUDE [prodshort](includes/prodshort.md)]

In this article, you learn some of the basics about viewing Power BI reports in [!INCLUDE [prodshort](includes/prodshort.md)].

## <a name="overview"></a>Overview

Power BI reports give you insight into your [!INCLUDE[prodshort](includes/prodshort.md)]. Various pages in [!INCLUDE [prodshort](includes/prodshort.md)] include a Power BI reports part that can display Power BI reports. The role centre is a typical page where you'll see a Power BI reports part. Some list pages, like **Items** , also include a Power BI part.

[!INCLUDE [prodshort](includes/prodshort.md)] works together with the Power BI service. Reports for displaying in [!INCLUDE [prodshort](includes/prodshort.md)] are stored in a Power BI service. In [!INCLUDE [prodshort](includes/prodshort.md)], you can switch the report displayed in the Power BI part to any Power BI report available in your Power BI service. The first time you sign into [!INCLUDE [prodshort](includes/prodshort.md)], and until you connect to a Power BI service, parts will be empty, as shown here:

![Power BI part in Business Central](./media/power-bi-part.png)

## <a name="prerequisites"></a>Prerequisites

If you're using [!INCLUDE[prodshort](includes/prodshort.md)] on-premises, it must be enabled for Power BI integration. This task is typically done by an administrator. For more information, see [Set up [!INCLUDE[prodshort](includes/prodshort.md)] on-premises for Power BI integration](admin-powerbi-setup.md#setup).

> [!NOTE]
> [!INCLUDE[prodshort](includes/prodshort.md)] online is already set up to integrate with Power BI.

## <a name="get-ready"></a>Get ready

Sign up for the Power BI service. If you haven't already signed up, go to [https://powerbi.microsoft.com](https://powerbi.microsoft.com). When you sign up, use your work email address and password.

## <a name="connect-to-power-bi---one-time-only"></a>Connect to Power BI - one time only

When you first sign into [!INCLUDE [prodshort](includes/prodshort.md)], you might see an empty Power BI part on some page, as shown in the previous figure. The first thing to do is to connect to your Power BI account. Once connected, you can see reports. You only have to do this step once.

To connect to Power BI, select the **Get Started with Power BI** link in the **Power BI Reports** part.

During the connecting process, [!INCLUDE [prodshort](includes/prodshort.md)] communicates with the Power BI service to determine if you have a valid Power BI account and licence. Once your licence is verified, the default Power BI report displays on the page. If there a report isn't shown, you can select a report from the part.

> [!TIP]
> With [!INCLUDE [prodshort](includes/prodshort.md)] online, this this step will automatically upload default Power BI reports used in [!INCLUDE [prodshort](includes/prodshort.md)] to your Power BI workspace.

##### <a name="from-prodshort-on-premises"></a>From [!INCLUDE [prodshort](includes/prodshort.md)] on-premises

Connecting to Power BI from [!INCLUDE [prodshort](includes/prodshort.md)] is similar to online. However, you'll be prompted on the **AZURE ACTIVE DIRECTORY SERVICE PERMISSIONS** page to grant access to Power BI Services. To grant access, select **Authorise Azure Services** , and then **Accept** .

Once connected, you can select a report from the Power BI part on pages.

## <a name="show-power-bi-reports-on-list-pages"></a>Show Power BI reports on list pages

[!INCLUDE[prodlong](includes/prodlong.md)] includes a Power BI FactBox on several key list pages. This FactBox provides additional insight into the data in the list. As you move between rows in the list, the report is updated and filtered for the selected entry. If you don't see this part, then from the action bar, select **Actions** > **Display** > **Show/Hide Power BI Reports** . For more information, see [Creating Power BI Reports for Displaying List Data in [!INCLUDE[prodshort](includes/prodshort.md)]](across-how-use-powerbi-reports-factbox.md).

## <a name="select-power-bi-reports"></a>Select Power BI reports

A Power BI part on a page can display any Power BI report that's available to you. To switch to view another report, choose the **Select Report** action from the drop-down command list at the top of the part.  

The **Power BI Reports Selection** page shows a list of all the Power BI reports that you have access to. This list is retrieved from your Power BI workspace. Select the **Enable** box for each report that you want to display on the page, and then choose **OK** . You'll return to the page, and the last report you enabled will appear. Using the drop-down command list, use the **Previous** and **Next** commands to navigate between reports.  

## <a name="get-reports"></a>Get reports

If you don't see any reports on the **Power BI Reports Selection** page, or don't see the report you want, choose **Get Reports** . This action lets you look for reports from two locations: *My Organisation* or from *Services* .

- Choose **My Organisation** to go to the Power BI services. From here, you can view the reports within your organisation that you've been given rights to view. You can then add them to your workspace.
- Choose **Services** to go to Microsoft AppSource where you can install Power BI apps.  

> [!TIP]
> If you have Power BI Desktop, you can also create new Power BI reports. Then, once those reports are published to your Power BI workspace, they will appear on the **Power BI Reports Selection** page.  

## <a name="manage-and-modify-reports"></a>Manage and modify reports

You can make changes to a report in the Power BI part. The changes that you make will then be published to the Power BI service. If the report is shared with other users, they'll also see the changes, unless you save the changes to a new report.

To modify a report, choose the **Manage Report** action from the drop-down command list in the Power BI part. Then start making changes. Once you finish making changes, select **File** > **Save** . If it's a shared report, and you don't want to make the change for all users, select **Save As** to avoid making this change for all users.

When you return to the role centre, the updated report will appear. If you used **Save As** , you'll have to choose **Select Report** , and then enable the new report to see it.

> [!NOTE]
> This capability is not available with [!INCLUDE [prodshort](includes/prodshort.md)] on-premises.

## <a name="upload-reports"></a><a name="upload"></a>Upload reports

Power BI Reports can be distributed among users as .pbix files. If you have any .pbix files, you can upload and share them with all users of [!INCLUDE [prodshort](includes/prodshort.md)]. The reports are shared within each company in [!INCLUDE [prodshort](includes/prodshort.md)].  

To upload a report, select the **Upload Report** action from the drop-down command list on the **Power BI Reports** part. Then, locate the .pbix file that defines the reports that you want to share. You can change the default name of the file.  

After the report uploads to your Power BI workspace, it automatically uploads to other users' Power BI workspaces.

> [!NOTE]
> Uploading a report requires that you have SUPER user permissions in [!INCLUDE[prodshort](includes/prodshort.md)]. Also, you can't upload reports with [!INCLUDE [prodshort](includes/prodshort.md)] on-premises. With on-premises, you upload reports directly to your Power BI workspace. For more information, see [Working with [!INCLUDE [prodshort](includes/prodshort.md)] Data In Power BI](across-working-with-business-central-in-powerbi.md).

## <a name="fixing-problems"></a>Fixing problems

However, if something goes wrong, this section provides a workaround for the most typical issues.  

### <a name="you-dont-have-a-power-bi-account"></a>You don't have a Power BI account

A Power BI account hasn't been set up. To get a valid Power BI account, you must have a licence, and you must have previously signed into Power BI to create a Power BI workspace.   

### <a name="message-there-are-no-enabled-reports-choose-select-report-to-see-a-list-of-reports-that-you-can-display"></a>Message: There are no enabled reports. Choose Select Report to see a list of reports that you can display.

This message appears if the default report failed to deploy to your Power BI workspace. Or it deployed but didn't refresh successfully. Navigate to the report in your Power BI workspace, select **Dataset** , **Settings** , and then manually update the credentials. Once the dataset successfully refreshes, navigate back to [!INCLUDE[prodshort](includes/prodshort.md)] and manually select the report from the **Select Reports** page.


## <a name="see-related-training-at-microsoft-learn"></a>See Related Training at [Microsoft Learn](/learn/modules/configure-powerbi-excel-dynamics-365-business-central/index)

## <a name="see-also"></a>See Also

[Business Central and Power BI](admin-powerbi.md)  
[Building Power BI Reports to Display [!INCLUDE [prodlong](includes/prodlong.md)] Data](across-how-use-financials-data-source-powerbi.md)  
[Power BI Integration Component and Architecture Overview for [!INCLUDE[prodshort](includes/prodshort.md)]](admin-powerbi-overview.md)  
[Working with [!INCLUDE [prodshort](includes/prodshort.md)] Data in Power BI](across-working-with-business-central-in-powerbi.md)  
[Power BI for consumers](/power-bi/consumer/end-user-consumer)  
[The 'new look' of the Power BI service](/power-bi/service-new-look)  
[Quickstart: Connect to data in Power BI Desktop](/power-bi/desktop-quickstart-connect-to-data)  
[Power BI documentation](/power-bi/)  
[Business Intelligence](bi.md)  
[Getting Started](product-get-started.md)  
[Importing Business Data from Other Finance Systems](across-import-data-configuration-packages.md)  
[Setting Up [!INCLUDE[d365fin](includes/d365fin_md.md)]](setup.md)  
[Using [!INCLUDE[d365fin](includes/d365fin_md.md)] as a Power BI Data Source](across-how-use-financials-data-source-powerbi.md)  
[Using [!INCLUDE[d365fin](includes/d365fin_md.md)] as a Power Apps Data Source](across-how-use-financials-data-source-powerapps.md)  
[Using [!INCLUDE[d365fin](includes/d365fin_md.md)] in Power Automate](across-how-use-financials-data-source-flow.md)  

## [!INCLUDE[d365fin](includes/free_trial_md.md)]  