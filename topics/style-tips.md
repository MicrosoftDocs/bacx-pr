---
title: Style tips for release notes
ms.date: 11/26/2018
ms.service: 
ms.topic: article
author: almostdunh
ms.author: v-ladunh
ms.reviewer: renwe

---

# Style tips for release notes

Here are style tips to help you as you create and develop your release notes topics for the April '19 release.

## Topic organization  

### Separate topics
To enable linking within a PDF, it’s better to have single-feature files in GitHub than to group features together in a single file. 

### Heading levels
Don’t skip heading levels within a topic. The first level should always be a heading 1 (#) and the next lower-level heading should be a heading 2 (##). Don’t jump from a heading 1 to a heading 3 or lower.

## Linking

### Page titles
Use  the title of the article or page and add a hyperlink. Don’t use the URL alone as your link, and don’t use “here” as a link – let readers know what you want them to see. Example:

  For instructions on how to set up the duplicate detection job, see [Run system jobs to detect duplicates](run-bulk-system-jobs-detect-duplicate-records.md).

### External links

**Important:** If you’re linking from release notes to a URL that is not part of the same release notes version, use the full URL. Otherwise, the link won’t work in the PDF. Example:

  For more information about all extensibility capabilities, see the [Extensibility home page](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page).

### Localization tip
Remove the language portion of a URL: /en-us/  This helps localizers. But test the link to make sure it still works. 

## Images

### Names in screenshots 

Check your images for names of people, companies, or other PII. Any names must be from Microsoft-approved fictitious names lists. More information: [List of approved names and other resources](https://microsoft.sharepoint-df.com/teams/Dynamics365CustomerEngagementEditingResources/_layouts/15/WopiFrame.aspx?sourcedoc=%7b0ea74ded-c03c-452d-a0de-6c89d54f7107%7d&action=edit&wd=target%28Style%20Guidelines.one%7C19ceab96-642a-49ba-8020-8958ea8cdb93%2FFictitious%20Names%7C0e4ac149-4669-4c0e-b262-f10ff3158758%2F%29)

### Image paths

Your image path must match the image file name exactly, including capitalization. For example, if .PNG is all caps in the file name, it must be all caps in the image path. (In fact, all of GitHub is case-sensitive, not just images.) Example:

  ../admin/media/cc-duplicate-detection-rule-cc-duplicate-detection-rule.PNG

### Captions 

In the image path, enter information about an image both within the straight brackets and again in the quotation marks. This provide alt-text and hover text. If you want a caption to appear beneath the image, use text in italics below the image path. Example:

  ![Schedule assistant displays results on the hour as part of interval scheduling](media/filters-share.png “Schedule assistant displays results on the hour as part of interval scheduling”)

  *Schedule assistant displays results on the hour as part of interval scheduling*

## Formatting and style

### Term-definition lists 

Use bold for the key word or term, followed by a non-bold colon. Example: 

  The features include:
  - Queues: A redesigned experience helps to prioritize and monitor the progress of the assigned work.
  - Subjects: A powerful mechanism to classify cases, knowledge base articles, products, and sales literature.
  - Case settings: Links cases together, enabling better response and tracking for common issues.

### Months 

Use the full name of the month in date columns of tables for planned features or change history. No need to abbreviate. 

### Feature names 

Names in tables of planned features and change history should match the topic heading. This helps readers know they’ve landed on the right topic when they select the link. 

### When writing, keep in mind

- The use of “we” (Microsoft) and “you” is OK, but don’t use “I” unless you’re writing a blog.
- Use exclamation marks sparingly, if ever.  



