---
title: "Do's and don'ts in the Release Notes"
ms.date: 01/21/2019
ms.service: 
ms.topic: "conceptual"
author: "ReneeW-CPub"
ms.author: "renwe"
---
# Do's and don'ts in the Release Notes

## Don'ts
There are some things that we author differently in the Release Notes from other docs. The differences are usually necessary because we create a custom PDF from the markdown files, which presents specific conversion issues. Since it is very time-consuming to produce a 350+ PDF, we limit certain functionality to avoid manual fixes in the PDF version. Here are the don'ts for the Release Notes:

- **Don't rename or remove topics that have been merged or published. If you want to remove or rename a topic, WAIT!!!!** Follow these instructions **only**: [Deleting or renaming topic files](delete-rename.md)
- Don't use HTML formatting in tables. 
- Don't use bookmarks as links. In the PDF, they will not go to the correct place. 
- Don't use referential links for any links except within the current Release Notes version you are working in. For example, referential links to other Release Notes break in the PDF. 
- Don't add border tags to images ([!div class="mx-imgBorder"]). The tags result in a non-caption style and strip the alt-text from the PDF during the conversion process. 


## Do's
- Do remember to put changes in the Change history (change-history.md) topic. See the comments in the topic for formatting you can copy and paste.
- Do remember to update the TOC file when you add new topics.  
