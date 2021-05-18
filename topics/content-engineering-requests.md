---
title: "Content Engineering Requests| MicrosoftDocs"
ms.date: 03/14/2019
ms.service: 
ms.topic: "conceptual"
author: "bishalgoswami"
ms.author: "bigoswam"
manager: "renwe"
---

# Content Engineering Requests

Test webhook.

Please use the following VSTS task templates to raise a content engineering request (content publish, content modification, reports, others). Follow these steps to raise a request.

1. Choose an appropriate template as per your need based on the task description by selecting the link in request column. 
2. Once you have identified the content engineering task you would need to create, provide all the mandatory details along with any supplementary info in the task **description** field.
3. If you could not find an appropriate task category for your requirement, please create a simple task under the **VSTS area path: OneCRM\Horizontals\CPub\Production and Publishing**.

## Content Engineering Request templates

|Requests|Description|Requested Inputs|
|-----|-----------------|----------------------------------------|
|[Publish Request](https://dynamicscrm.visualstudio.com/OneCRM/_workitems/create/Task?templateId=10356eb7-e09b-4fd3-bab1-28019c466efe&ownerId=74778d57-e6a1-43fe-b56b-be19cb488aae)|Use this template to create a publishing request. Please provide all the required details in the task description.</br></br>**Note**: Release Notes Live publishes are scheduled weekly on Tuesday and Thursday. If there is an urgent publish required for Release Notes, please follow-up with [crmce](mailto:crmce@microsoft.com).|*Pull Request Link\*, Publish to Live(Y/N)\*, Go Live Date\*, Delete source branch(Y/N)\*, Is Release Notes Publish(Y/N), Other Details*|
|[File Deletion/Redirection Request](https://dynamicscrm.visualstudio.com/OneCRM/_workitems/create/Task?templateId=adfeaa5a-22a9-4416-9755-9b9980c42822&ownerId=74778d57-e6a1-43fe-b56b-be19cb488aae)|Use this template to create a file deletion/rename or a redirection request. Please provide all the required details in the task description.</br></br>**Note**: Requesters are expected to remove all references to the deleted file(s) before creating the task.|*Repository/Docset\*, Old file path to delete/redirect\*, New file path to redirect to\*, Other Details\**|
|[File(s) Conversion Request](https://dynamicscrm.visualstudio.com/OneCRM/_workitems/create/Task?templateId=411f3c43-dfd6-4bc2-914a-c2356ad1e5f7&ownerId=74778d57-e6a1-43fe-b56b-be19cb488aae)|Use this template to create a file conversion request. Please provide the type of conversion required in the description and other specific information.|*Repository/Docset\*, Conversion Type (Word to Md, Md to Word, Others)\*, Location of File/Folder for conversion\*, Other Details*|
|[Bulk data update Request](https://dynamicscrm.visualstudio.com/OneCRM/_workitems/create/Task?templateId=762e4275-ff40-4871-8792-be0c36c8dec9&ownerId=74778d57-e6a1-43fe-b56b-be19cb488aae)|Use this template to create a bulk content operation request. Please provide the update type in the description and other required details in the task description.|*Repository/Docset\*, Bulk Update Type (Metadata, Tokens, String, Images, Others)\*, Location of File/Folder to update\*, Other Details*|
|[Repository/Docset Configuration](https://dynamicscrm.visualstudio.com/OneCRM/_workitems/create/Task?templateId=fbf014a7-ecce-4004-b44f-17a577161fcf&ownerId=74778d57-e6a1-43fe-b56b-be19cb488aae)|Use this template to create a request for operations related to repo/docset configuration. Please provide the type and other related information in the task description.|*New Repository/Docset\*, Configuration Type (UHF-Header/Footer, Hub/Landing Page, Monikers, Breadcrumbs, Searchscope, Docs Feedback, Repository syncing, Others)\*, Details\**|
|[Content Reporting](https://dynamicscrm.visualstudio.com/OneCRM/_workitems/create/Task?templateId=e86a6606-c215-4e13-9a59-3dc500b927ff&ownerId=74778d57-e6a1-43fe-b56b-be19cb488aae)|Use this template to create a request for content reports like metadata, tokens and others. Please provide the required info in the task description.|*Repository/Docset\*, Report Type (Metadata, Tokens, Others)\*, Details\**|
|[New Repository/Docset Request](https://dynamicscrm.visualstudio.com/OneCRM/_workitems/create/Task?templateId=0be2842b-9457-43a2-b1ed-677cf5c96329&ownerId=74778d57-e6a1-43fe-b56b-be19cb488aae)|Use this template to create a request for commissioning a new repository/docset. Please provide the required details in the task description.|*New Repository/Docset\*, Docset Folder\*, URL structure (ex- https://docs.microsoft.com/<product\>)\*, Target Go Live Date\*, Details*|

## Requesting access
If you don't have access to the OneCRM TFS instance, go to [http://myaccess](http://myaccess) and request access to either *CRM FTE Dev/Test Source Read-Write* (for FTEs), or *CRM Vendor Source* (for vendors).
