---
# required metadata

title: Database movement toolkit
description: This topic explains how to download and use the Database movement toolkit, a series of scripts that enhance the customer experience for movement of data between developer environments and sandbox environments. 
author: laneswenka
manager: AnnBe
ms.date: 09/30/2020
ms.topic: article
ms.prod: 
ms.service: dynamics-ax-platform
ms.technology: 

# optional metadata

# ms.search.form: 
audience: Developer, IT Pro
# ms.devlang: 
ms.reviewer: sericks
ms.search.scope:  Operations
# ms.tgt_pltfrm: 
# ms.custom: 
ms.search.region: Global
# ms.search.industry: 
ms.author: laswenka
ms.search.validFrom: 2017-06-16
ms.dyn365.ops.version: Platform update 30
---

# Database movement toolkit

The Database movement toolkit is a ZIP file hosted in Microsoft Dynamics Lifecycle Services (LCS). This toolkit is available for download. It contains a series of scripts that enhance the customer experience for movement of data between developer environments and sandbox environments. This topic explains the components of the toolkit, how to download it, and any recent changes.

## Download the latest version

The toolkit is available in the LCS Shared Asset Library under the **Models** section.  Search for the entry titled **Database Movement Toolkit** and then download it to your Tier1 DevTest environment.  

## Toolkit components

The toolkit contains the following primary components:

- **Sqlpackage.exe** - This tool is used to perform extract and publish actions against Microsoft Azure SQL databases, as well as SQL Server databases hosted on Tier1 DevTest environments.  
- **PowerShell 7.0** - This is a self-contained version of PowerShell that includes capabilities for parallelism, which increases the performance of transferring data between environments.  
- **PowerShell script** - There are several scripts included to provide an enhanced and more automated experience for scenarios such as AX 2012 data upgrade.

## Supported scenarios

The toolkit currently supports the following scenarios. More will be added over time.  

* [Upgrade from AX 2012 - Data upgrade in sandbox environments](../migration-upgrade/upgrade-data-sandbox-dacpac.md)

## Versions

### Version 1
| Feature | Details |
| :------ | :------ |
| Initial | Toolkit uploaded to LCS Shared Asset Library.|


