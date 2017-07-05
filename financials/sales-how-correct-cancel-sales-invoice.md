---
title: 'How to: Correct or Cancel Unpaid Sales Invoices| Microsoft Docs'
description: 'How to: Correct or Cancel Unpaid Sales Invoices'
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: undo, credit memo, return
ms.date: 03/29/2017
ms.author: sgroespe
ms.translationtype: Human Translation
ms.sourcegitcommit: a31be0f9d07e2abb591e26f6bae34c6f6e4dcda6
ms.openlocfilehash: 9289aeb9b44ec300646fbe6e6fdbf77e72cd7b08
ms.contentlocale: en-au
ms.lasthandoff: 05/04/2017


---
# <a name="how-to-correct-or-cancel-unpaid-sales-invoices"></a>How to: Correct or Cancel Unpaid Sales Invoices
You can correct or cancel a posted sales invoice. This is useful if you make a mistake or if the customer requests a change.

**Note**: After a posted sales invoice has been partially or fully paid, you cannot correct or cancel it from the posted sales invoice itself. Instead, you must manually create a sales CR/Adj note to void the sale and reimburse the customer. For more information, see [How to: Process Sales Returns or Cancellations](sales-how-process-sales-returns-cancellations.md).

In the **Posted Sales Invoice** window, you can choose the **Correct** action or the **Cancel** action to perform the actions that are described in the following table.

| Action | Description |
| --- | --- |
| **Correct** |The posted sales invoice is cancelled. A new sales invoice with the same information is created. You can make the correction and then continue the sales process. The new sales invoice has a different number than the initial sales invoice. A corrective sales CR/Adj note is automatically created and posted to void the initial posted sales invoice. On the initial posted sales invoice, the Cancelled and Paid check boxes are selected. |
| **Cancel** |The posted sales invoice is cancelled. A corrective sales CR/Adj note is automatically created and posted to void the initial posted sales invoice. On the initial posted sales invoice, the Cancelled and Paid check boxes are selected. |

When you correct or cancel a posted sales invoice, the corrective sales CR/Adj note is applied to all general ledger and inventory ledger entries that were created when the initial sales invoice was posted. This reverses the posted sales invoice in your financial records and leaves the corrective posted sales CR/Adj note for your audit trail.

## <a name="to-correct-a-posted-sales-invoice"></a>To correct a posted sales invoice
1. In the top right corner, choose the **Search for Page or Report** icon ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon"), enter **Posted Sales Invoices**, and then choose the related link.  
2. Select the posted sales invoice that you want to correct.

    **Note**: If the **Cancelled** check box is selected, then you cannot correct the posted sales invoice because it has already been corrected or cancelled.
3. In the **Posted Sales Invoice** window, choose the **Correct** action.  
4. A new sales invoice with the same information is created where you can make the correction. The **Cancelled** field on the initial posted sales invoice is changed to **Yes**.

    A sales CR/Adj note is automatically created and posted to void the initial posted sales invoice.
5. Choose the **Show Corrective CR/Adj Note** action to view the posted sales CR/Adj note that voids the initial posted sales invoice.

## <a name="to-cancel-a-posted-sales-invoice"></a>To cancel a posted sales invoice
1. In the top right corner, choose the **Search for Page or Report** icon ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon"), enter **Posted Sales Invoices**, and then choose the related link.  
2. Select the posted sales invoice that you want to cancel.

    **Note**: If the **Cancelled** check box is selected, then you cannot cancel the posted sales invoice because it has already been cancelled or corrected.
3. In the **Posted Sales Invoice** window, choose the **Cancel** action.

    A sales CR/Adj note is automatically created and posted to void the initial posted sales invoice. The **Cancelled** field on the initial posted sales invoice is changed to **Yes**.
4. Choose **Show Corrective CR/Adj Note** to view the posted sales CR/Adj note that voids the initial posted sales invoice.

## <a name="see-also"></a>See Also
[Sales](sales-manage-sales.md)  
[Setting Up Sales](sales-setup-sales.md)  
[How to: Send Documents by Email](ui-how-send-documents-email.md)  
[Working With [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)
