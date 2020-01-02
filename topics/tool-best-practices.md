---
title: "Do's and don'ts in the release plans"
ms.date: 08/21/2019
ms.service: 
ms.topic: "conceptual"
author: "ReneeW-CPub"
ms.author: "renwe"
---
# Do's and don'ts in the release plans

We author some things differently in the release plans than in other docs. The differences are necessary because we create a custom PDF from the Markdown files, and this presents specific conversion issues. Because it is very time-consuming to produce a PDF of 350 pages or more, we limit certain functionality to avoid manual fixes in the PDF version. 

With that in mind, here are some do's and don'ts for release plans:

- Don't manually rename or delete topics in GitHub. If you revise a release plan title or remove a title from release plans in the Release Planner tool, the tool will handle it when the GitHub PRs are created. 

- Don't use HTML formatting. It breaks the PDFs. 

- Do remove the **en-us/** from URLs used in topics; this is important for localization.

- Don't use referential links for any links except within the current release plan version you are working in. For example, referential links to another version of the release plans will break in the PDF. 

- Do put a blank line after a sentence introducing a list. This keeps the list from breaking in the PDF.

- Don't add border tags to images ([!div class="mx-imgBorder"]). The tags result in a non-caption style and strip the alt-text from the PDF during the conversion process. 

**April '19 and earlier only**:
- **Don't rename or remove topics that have been merged or published. If you want to remove or rename a topic, WAIT!!!!** Follow these instructions **only**: [Deleting or renaming topic files](delete-rename.md)

- Do remember to put changes in the change history (change-history.md) topic. See the comments in the topic for formatting you can copy and paste.

- Do remember to update the TOC file when you add or remove a topic.  

- Do remember to update the planned features table if you add or remove a topic. 

