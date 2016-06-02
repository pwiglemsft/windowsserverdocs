---
title: STEP 8: Configure INET1
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: 
  - techgroup-networking
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 693acb5c-dffc-4484-8286-163bb67724c9
author: coreyp
---
# STEP 8: Configure INET1
To enable client computers to connect to Remote Access servers over the Internet, you must configure a DNS entry for 2\-EDGE1 on INET1.  
  
### To create the 2\-EDGE1 DNS entry  
  
1.  [!INCLUDE[clickstart](includes/clickstart_md.md)]**dnsmgmt.msc**, and then press ENTER.  
  
2.  In the console tree, open **Forward Lookup Zones**, click **contoso.com**, then right\-click **contoso.com**, and then click **New Host \(A or AAAA\)**.  
  
3.  In **Name**, type **2\-EDGE1**. In **IP address**, type **131.107.0.20**. Click **Add Host**, click **OK**, and then click **Done**.  
  
