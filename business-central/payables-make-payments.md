---
title: Overview of Tasks to Manage Payments to Vendors| Microsoft Docs
description: Outlines tasks to manage payments to vendors or creditors, including posting payment lines and getting an overview of the balance due.
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: print check, vendor payment, creditor, debt, balance due, AP
ms.date: 11/17/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: d7fb34e1c9428a64c71ff47be8bcff174649c00d
ms.openlocfilehash: fb3a95c63963c2f209dfa8d6c04711a3e5dc8339
ms.contentlocale: en-au
ms.lasthandoff: 03/22/2018

---
# <a name="making-payments"></a>Making Payments
When you make payments to vendors or reimbursements to employees, you post the related payment lines in the **Payment Journal** window. You can use the **Suggest Vendor Payments** function to find vendor payments that are due. You can also use the **Vendor - Summary Ageing** report to get an overview of due vendor payments.

From the payment journal, you can print computer cheques or record when cheques are written. If you select **Computer Cheque** in the **Bank Payment Type** field, then any lines representing cheques must be printed before the payment journal can be posted.

When the payments are posted, you can export them to a bank file for upload to your bank for processing.

After the payments are made at your bank, you must apply them to their related open vendor or employee ledger entries. You can do this manually or by importing a bank statement file and applying the payments automatically. For more information, see [Applying Payments Automatically and Reconciling Bank Accounts](receivables-apply-payments-auto-reconcile-bank-accounts.md).

The following table describes a sequence of tasks, with links to the topics that describe them.

| To | See |
| --- | --- |
|Use the **Payment Journal** window, which is a based on the general journal, to post payments to vendors or employees.|[Working with General Journals](ui-work-general-journals.md)|
| Use a function to suggest vendor payments according to selected criteria, such as due date, discount eligibility, and your liquidity. |[Suggest Vendor Payments](payables-how-suggest-vendor-payments.md) |
|Reimburse employees for personal expenses during business activities by making payment to their bank account.|[Record and Reimburse Employees' Expenses](finance-how-record-reimburse-employee-expenses.md)|
| Issue cheques for vendor payments, either as print-outs or as computer cheques. Void cheques before or after posting. |[Work With Cheques](payables-how-work-checks.md) |
| Pay the vendor by cash or cheque, and post the payment when you post the invoice. |[Settle Purchase Invoices Promptly](finance-how-to-settle-purchase-invoices-promptly.md) |
| Make sure that your bank only clears validated cheques and amounts by sending them a file that contains vendor, cheque, and payment information. |[Export a Positive Pay file](finance-how-positive-pay.md) |
|Export payments from the **Payment Journal** window to a bank file that you upload to your bank for processing, including EFT (electronic funds transfer) in North America. |[Export Payments to a Bank File](payables-how-export-payments-bank-file.md)|
|Make electronic payments according to the EU SEPA Credit Transfer standard.|[Making Payments with Bank Data Conversion Service or SEPA Credit Transfer](finance-make-payments-with-bank-data-conversion-service-or-sepa-credit-transfer.md)|    

## <a name="see-also"></a>See Also
[Managing Payables](payables-manage-payables.md)  
[Purchasing](purchasing-manage-purchasing.md)  
[Managing Receivables](receivables-manage-receivables.md)  
[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  
