---
title: Create a Customer, Vendor, or Bank Account From a Contact | Microsoft Docs
description: Describes hoe to create a customer, vendor, or bank account from a contact in Financials
services: project-madeira
documentationcenter: 
author: jswymer
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: relationship, client, prospect
ms.date: 02/28/2017
ms.author: jswymer
ms.translationtype: Human Translation
ms.sourcegitcommit: a31be0f9d07e2abb591e26f6bae34c6f6e4dcda6
ms.openlocfilehash: 6ecbc24e447917e6316b0579fa8c3ee046e73915
ms.contentlocale: en-au
ms.lasthandoff: 05/04/2017


---
# <a name="create-a-customer-vendor-or-bank-account-from-a-contact"></a>Create a Customer, Vendor, or Bank Account From a Contact
You may want to record some of your existing contacts as customers, vendors, or bank accounts. Creating a customer, vendor, or bank account from a contact enables you use existing data. When you create a customer, vendor, or bank account this way, it is synchronised with the contact. Synchronisation makes information that is common between contacts and customers, vendors, or bank account the same.

Before you can record contacts this way, you must specify a business relation code for customers, vendors, and bank accounts in the **Marketing Setup** window. If you will be recording contacts as bank accounts, you must also specify numbers series for bank accounts in the **General Ledger Setup** window.

## <a name="to-create-a-contact-as-a-customer-vendor-or-bank-account"></a>To create a contact as a customer, vendor, or bank account
1. In the top right corner, choose the **Search for Page or Report** icon ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon"), enter **Contacts**, and then choose the related link.
2. Select the contact you want to create as a customer, vendor, or bank account.
3. Choose the **Create As** action, and then choose either **Customer**, **Vendor**, or **Bank**.
4. Confirm the subsequent message.

The contact information is transferred from the **Contact** card to the **Bank Account** card, the **Customer** card, or the **Vendor** card. You may want to add specific information to each of the cards, such as invoicing and payment details.

## <a name="see-also"></a>See Also
[How to: Create Contact Companies](marketing-create-contact-companies.md)  
[How to: Create Contact Persons](marketing-create-contact-persons.md)  
[Setting Up Relationship Management](marketing-setup-marketing.md)  
[Synchronizing Contacts With Customers, Vendors, and Bank Accounts](marketing-synchronize-contacts-customers-vendors-bank-accounts.md)  
[How to: Link Contacts to Existing Customers, Vendors, or Bank Accounts](marketing-how-link-contact.md)  
[Assign Business Relations to a Contact](marketing-business-relations.md#AssignBusRelContact)  
[Working With Financials](ui-work-product.md)
