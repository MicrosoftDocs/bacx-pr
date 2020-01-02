---
title: "Best practices and requirements"
ms.date: 08/21/2019
ms.service: 
ms.topic: "conceptual"
author: "ReneeW-CPub"
ms.author: "renwe"
---

# Best practices and requirements
We author some things differently in the release plans than in other docs. The differences are necessary because we create a custom PDF from the Markdown files, and this presents specific conversion issues. Because it is very time-consuming to produce a PDF of 350 pages or more, we limit certain functionality to avoid manual fixes in the PDF version. 

## Current release plans
The following sections describe the **dos and don'ts** for release plans from 2019 release wave 2 and current 2020 release wave 1 plans. 

### Dos
| Do | Note |
| -- | -- |
| Remove the **en-us** references from URLs. | This is important for localization. |
| Put a blank line after a sentence introducing a list. | This keeps the list from breaking in the PDF. |
| Include alt-text for images. | This is an important accessibility feature. |

### Don'ts
| Don't | Note |
| -- | -- |
| Do **not** manually rename or delete topics in GitHub. | Revise titles in the Release planner app, and it will sync to GitHub when PRs are created. |
| Do **not** use HTML. | It breaks in the PDFs. |
| Do **not** use referential links for any links except within the current release plan version you are working in. | Referential links to another version of the release plans will break in the PDF. |
| Do **not** add border tags to images ([!div class="mx-imgBorder"]). | The tags result in a non-caption style and strip the alt-text from the PDF during the conversion process. |

## April '19 and earlier only
The following sections describe the **dos and don'ts** for previous releases (April '19 and earlier).

### Dos
| Do | Note|
| -- | -- |
| Remember to put changes in the Change history (change-history.md) topic. | See the comments in the topic for formatting you can copy and paste. |
| Remember to update the TOC file when you add or remove a topic. | - |
| Remember to update the planned features table if you add or remove a topic. | - |

### Don'ts 
| Don't | Note |
| -- | --|
| Do **not** rename or remove topics that have been merged or published. | If this is required, follow these instructions **ONLY**: [Deleting or renaming topic files](delete-rename.md) |
