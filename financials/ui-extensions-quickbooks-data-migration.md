---
title: QuickBooks Data Migration | Microsoft Docs
description: Provides information about the QuickBooks Data Migration extension
services: project-madeira
documentationcenter: 
author: edupont04
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms. search.keywords: app, add-in, manifest, customize, import, implement
ms.date: 03/29/2017
ms.author: edupont
ms.translationtype: Human Translation
ms.sourcegitcommit: a31be0f9d07e2abb591e26f6bae34c6f6e4dcda6
ms.openlocfilehash: 860ee6b26071e8264deb68bec3b039f384c7be0f
ms.contentlocale: en-au
ms.lasthandoff: 05/04/2017


---
# <a name="the-quickbooks-data-migration-extension-for-dynamics-365-for-financials"></a>The QuickBooks Data Migration Extension for Dynamics 365 for Financials
This extension makes it easy to migrate customers, vendors, items, and accounts from QuickBooks to [!INCLUDE[d365fin](includes/d365fin_md.md)]. If your business uses QuickBooks today, you can export the relevant information and then open an assisted setup guide to upload the data to [!INCLUDE[d365fin](includes/d365fin_md.md)].  
For more information, see [Importing Business Data from Other Finance Systems](upload-data.md).

## <a name="exporting-data-from-quickbooks"></a>Exporting Data from QuickBooks
You must have exported some or all of your existing customers, vendors, inventory items, and accounts to an Intuit Interchange Format (IIF) file. The QuickBooks Data Migration extension includes a default mapping of QuickBooks data so that you can use your existing data to test your new [!INCLUDE[d365fin](includes/d365fin_md.md)] company. The default mapping will be sufficient in the vast majority of cases, but you can change the mapping in the assisted setup guide.  
In QuickBooks, the File menu includes a utility to export lists. For the purposes of [!INCLUDE[d365fin](includes/d365fin_md.md)], you can export the following lists:

* Customer List  
* Vendor List  
* Item List  
* Account List  

The exported data is saved as an IIF file that you can then upload to [!INCLUDE[d365fin](includes/d365fin_md.md)].

## <a name="see-also"></a>See Also
[Importing Business Data from Other Finance Systems](upload-data.md)  
[Customizing [!INCLUDE[d365fin](includes/d365fin_md.md)] Using Extensions ](ui-extensions.md)  
