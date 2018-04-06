---
title: Design Details - Cost Components | Microsoft Docs
description: Cost components are different types of costs that make up the value of an inventory increase or decrease.
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: d7fb34e1c9428a64c71ff47be8bcff174649c00d
ms.openlocfilehash: e1410e2511b2f1dd27e80ea23d6e08b2b5063158
ms.contentlocale: en-au
ms.lasthandoff: 03/22/2018

---
# <a name="design-details-cost-components"></a>Design Details: Cost Components
Cost components are different types of costs that make up the value of an inventory increase or decrease.  

 The following table shows the different cost components and any subordinate cost components that they consist of.  

|Cost Component|Subordinate Cost Component|Description|  
|--------------------|--------------------------------|---------------------------------------|  
|Direct cost|Unit cost (direct purchase price)|Cost that can be traced to a cost object.|  
|Direct cost|Freight cost (item charge)|Cost that can be traced to a cost object.|  
|Direct cost|Insurance cost (item charge)|Cost that can be traced to a cost object.|  
|Indirect cost||Cost that cannot be traced to a cost object.|  
|Variance|Purchase variance|The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.|  
|Variance|Material variance|The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.|  
|Variance|Capacity variance|The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.|  
|Variance|Subcontracted variance|The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.|  
|Variance|Capacity overhead variance|The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.|  
|Variance|Manufacturing overhead variance|The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.|  
|Revaluation||A depreciation or appreciation of the current inventory value.|  
|Rounding||Residuals caused by the way in which valuation of inventory decreases are calculated.|  

> [!NOTE]  
>  Freight and insurance costs are item charges that can be added to an item’s cost at any time. When you run the **Adjust Cost - Item Entries** batch job, the value of any related inventory decreases are updated accordingly.  

## <a name="see-also"></a>See Also  
 [Design Details: Inventory Costing](design-details-inventory-costing.md)   
 [Design Details: Variance](design-details-variance.md) [Managing Inventory Costs](finance-manage-inventory-costs.md)  
 [Finance](finance.md)  
 [Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  
