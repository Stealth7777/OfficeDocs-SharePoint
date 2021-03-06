---
title: "Migration Manager FAQs"
ms.reviewer: 
ms.author: jhendr
author: JoanneHendrickson
manager: pamgreen
audience: ITPro
ms.topic: article
ms.service: sharepoint-online
localization_priority: Priority
ms.collection: 
- M365-collaboration
- SPMigration
search.appverid: MET150
description: Migration Manager FAQs
---

# Frequently Asked Questions:  Migration Manager


>[!Note]
>Features noted in this topic are part of a preview release. The content and the functionality are subject to change and are not subject to the standard SLAs for support.

**Question:** Can I migrate content from SharePoint Server? </br>
**Answer:**   At this time, Migration Manager only supports the migration of **file shares**.  It does not support the migration of content from SharePoint Server.

**Question:**  Can I run the SharePoint Migration Tool (SPMT) on the same computer that I have the Migration Manager agent installed?</br>
**Answer:**   Yes.


**Question:**  Does the file share I am migrating need to be on a Windows computer?</br>
**Answer:**    No.  As long as you can access the file share from the migration client, you can migrate it.

**Question:**  Is multi-factor authentication supported by Migration Manager?</br>
**Answer:**    Microsoft multi-factor authentication is supported; however third party multi-factor authentication is not.

**Question:**  Can I manually assign a task to a migration client I have set up?</br>
**Answer:**    No. Migration Manager does it for you by automatically distributing tasks to the next available client.


**Question:**  Where are local Migration Manager logs stored?</br>
**Answer:**    The logs are stored here:  C:\Users\<Username>\AppData\Roaming\Microsoft\SPMigration.