---
title: "Deleting or renaming topic files | MicrosoftDocs"
ms.date: 08/30/2018
ms.service: 
ms.topic: "conceptual"
author: "buck1ey"
ms.author: "buckg"
manager: "renwe"
---

# Deleting or renaming topic files

I'm making a test change to this topic.

## Deleting topic files

Deleting a topic in GitHub will cause any existing links to the topic to error on docs.microsoft.com. To give customers a better experience, we can put redirections in place.

There are also localization considerations with deletions. If the deleting isn't coordinated correctly, the localization handback can fail.

Follow this process for deleting a file.

 -  Writer/Editor updates TOC, planned features, change history, and any other topics referencing the removed content. They then coordinate the appropriate reviews and push the changes to "master"
   > [!NOTE]
   > These changes can be pushed live at any time. They will effectively hide the removed content from users. Actually deleting/renaming the topic needs to be timed with localization.
 -	Writer/Editor opens TFS item, using [this template](https://dynamicscrm.visualstudio.com/OneCRM/CRM.Internal.CPub.ContentEngineering/_workitems/create/Task?templateId=5f40a615-c903-4905-9240-2c720bd56075&ownerId=b9f83a31-db17-49e3-848b-c891c5b1e1c1), for CE listing topics to delete, and redirection target for each deleted topic
 -	CE coordinates timing with localization
 -	CE deletes topic(s), and implements redirect(s) in a working branch
 -	CE opens PR from working branch to "master", adds Writer/Editor as reviewer
 -	When approved by Writer/Editor, CE merges to "master" and deletes working branch


## Renaming a topic file

   > [!WARNING]
   > Changing a topic file name can break a localization handback.

**Topic file names should not be changed**. Changing a topic file name can break a localization handback, cause significant additional localization cost, and create errors for customers.

If you have a business case for renaming a topic file, contact [crmce](mailto:crmce@microsoft.com) and outline your reasons for the rename. If your case is approved by AnnBe, Content Publishing Director, your Cpub contacts will work with you to implement the rename.

   >[!NOTE]
   >The approval bar for file renaming is very high. The risk of breaking a localization handback is high, so approvals will be rare exceptions.
