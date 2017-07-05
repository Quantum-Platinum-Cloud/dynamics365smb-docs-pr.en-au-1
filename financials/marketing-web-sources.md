---
title: Setting Up Web Sources for Contact Companies | Microsoft Docs
description: Describes how to use web sources for contacts in Financials
services: project-madeira
documentationcenter: 
author: jswymer
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: internet
ms.date: 03/28/2017
ms.author: jswymer
ms.translationtype: Human Translation
ms.sourcegitcommit: a31be0f9d07e2abb591e26f6bae34c6f6e4dcda6
ms.openlocfilehash: 8a452619aeeee907cf61fd5d1a8fce409ad2e42d
ms.contentlocale: en-au
ms.lasthandoff: 05/04/2017


---
# <a name="setting-up-web-sources-for-contact-companies"></a>Setting Up Web Sources for Contact Companies
You can use web sources with your contact companies to identify, for example, search engines and web sites, on the Internet that you want to use to search for information about the contacts. When assigning web sources, you specify which search engine and search word the application will use to find the requested information.

Using web sources on contacts is a two-step process. First, you define the web source code. You only have to perform this step one time for each web source. Once you have a web source code, you can start to assign the code to contact persons.

## <a name="to-define-a-web-source-code"></a>to define a web source code
1. In the top right corner, choose the **Search for Page or Report** icon ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon"), enter **Web Sources**, and then choose the related link.
2. Choose the **New** actions.
3. Fill in the **Code**, **Description**, and **URL** fields.

    Type %1 in the **URL** field to insert a placeholder for a search word in the URL. When you launch the web source from a contact, the %1 is replaced with the search word, for example, the name of the company that you have entered in the **Contact Web Sources** window.

Repeat these steps to set up as many web sources as you want.

## <a name="to-assign-web-sources-to-a-contact-company"></a>to assign web sources to a contact company
When assigning web sources, you specify which search engine and search word that the application will use to find the requested information.

1. Open the contact.
2. Choose the **Company** action, and then choose the **Web Sources** action. The **Contact Web Sources** window opens.
3. In the **Web Source Code** field, choose the web source you want to assign.
4. In the **Search Word** field, enter the search word that you want to use to find the information.

Repeat these steps to assign as many web sources as you want.

You can also assign web sources from the **Contact List** window by following the same procedure.

## <a name="see-also"></a>See Also
[Creating Contact Companies](marketing-create-contact-companies.md)  
[Working With [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)
