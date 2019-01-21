---
title: "Topic types and their requirements"
ms.date: 01/21/2019
ms.service: 
ms.topic: "conceptual"
author: "ReneeW-CPub"
ms.author: "renwe"
---
# Topic types and their requirements
Here are general requirements for each type of topic we have in the Release Notes. 

Also check out these great examples of each type: 

- Feature: [Late Payment Prediction extension](https://docs.microsoft.com/en-us/business-applications-release-notes/October18/dynamics365-business-central/late-payment-prediction)

- Summary of what's new: 
  - Online-only table: [Summary of what's new in Microsoft Flow](https://docs.microsoft.com/en-us/business-applications-release-notes/October18/microsoft-flow/planned-features)
  - Cloud/online or on-premises table: [Summary of what's new in Finance and Operations](https://docs.microsoft.com/en-us/business-applications-release-notes/October18/dynamics365-finance-operations/planned-features)

- Change history: [Change history](https://docs.microsoft.com/en-us/business-applications-release-notes/October18/change-history)
  For example, see how Talent and PowerApps did their change history tables. 

- Overview: [Overview of Dynamics 365 for Finance and Operations October '18 release](https://docs.microsoft.com/en-us/business-applications-release-notes/October18/dynamics365-finance-operations/)



## Feature topics

- Start by saying the value proposition of the feature.
- Include screenshots or an image to help users see the benefits, if a visual element can add interest.
- Be as descriptive as you can. And go back when you know more to add more info. It's the number one piece of feedback we get from customers about the Release Notes. They want more details about your features. 
- Once a feature ships, make sure to add the links to the shipped docs that went with it so users can get as much info as possible.
- If this is a new feature, it should have the new feature label.
- If you change a feature’s title, make the same change in these places:
  - the title tag of the topic for that feature 
  - the H1 of the same topic
  - For features that will ship to public preview in the six-month window of the release, ensure that “(Public Preview)” appears at the end of the H1.
  -  the link from toc.md to the feature topic
  - the link from planned-features.md to the feature topic
  - the link (if any) from change-history to the feature topic
- Ensure that the description tag follows the same guidelines as other topics do for SEO, etc.
- Ensure that the body of the topic (everything after the H1) meets the same guidelines as other topics do: no PII, minimum resolution for screen shots is 1920, etc.
- Ensure that toc.md shows features in the same sequence as planned-features.md.

If you are using the Flow/PA authoring tool, these are additional guidelines for you:
- If you are the CP Owner, don’t update any metadata tags except title and description.

> [!NOTE]
> As of January 2019, we are not adding border tags to images in release notes only. This is because the tags result in a non-caption style and strip the alt-text in the PDF. This might be resolved at some point, but for now we should not add border tags. We will work around the tags already in release notes topics.


## Summary of what's new (planned-features.md) topics 

Feature column:
- Put the name of the feature
- When possible, make the name a link to the topic about the feature
- Ensure that the feature’s entry appears with other features of the same release type and date

Release type column:
- For features in public preview, use "Public Preview", not just "Preview". (We do not put private preview features in the Release Notes.)

Cloud/Online or on-premises column:
-Use either "Cloud" or "Online" in the column heading, depending on which word your product uses. 
  - Cloud or on-premises
  - Online or on-premises
 -Values for the cells can be "Cloud," "Online", "On-premises", or "Both". Only use "Both" if online and on-premises are shipping at the same time.

Date column:
- For before a feature ships, use the month and year the feature is planned to ship. Example: April 2019
- For once the features has shipped, use the day, month, and year. Example: April 12, 2019
- For features that are not scheduled, put "Undetermined"
- For features that are both not scheduled and might ship after the current release notes timeframe, put "Undetermined (may release after ". For example: Undetermined (may release after March 2019)


Weekly release column:
- Use the same version information that customers are being given and make it a link to the corresponding weekly release notes topic.
- Please note this applies only to some teams, such as Flow.


## Change history (change-history.md) topic
If a change is made to a published topic, make sure it's represented in the Change history topic.

General guidelines:
- See the comments at the top of the change-history.md file for a template for each type of table you might need. Use those templates so we are consistent within the topic. 
- Ensure that an entry is created in change-history.md, and follow the precedents in existing entries. (For example, link to the feature topic, and don’t include the year when you specify a date.)
- Don’t create multiple entries for the same feature. For example, a feature may slip more than once, slip before being removed, etc. In those cases, just update the existing entry to the new date or move the entry to the table for removed features, etc. as appropriate.
- Do not put private preview features in the Release Notes.

Types of change tables:
- Features added
- Release date changed
- Feature description changed
- Feature section changed
- Features removed

Feature column:
- Put the name of the feature
- When possible, make the name a link to the topic about the feature

Change and Additional info columns:
- Put a concise description that describes the nature of the change and uses the same wording as other Change and Additional info columns.

Date changed, Date added, and Date removed columns:
- Put the month and day you made the change in the Release Notes. Example: September 24  

## Overview topics
It's important to write a strong overview that outlines all the investments for the product area you are covering, and to group those investments by themes. More guidance coming soon...

## Topic metadata

- author- PM’s GitHub user name
- ms.author - PM alias
- ms.reviewer – CP owner alias
- ms.manager – not needed. Don’t use.
- description – Write a good description loaded with keywords. Minimum 75, max 300 characters including spaces. Per APEX, displays on the search page inline with the article date stamp. If your intro para describes your article's intent, you can use it here edited for length.
- title (page title) - This is the page title that will appear in search results and if a users hovers their mouse over the browser tab. This should be similar to the H1 heading in the topic, but not the same per SEO instructions. Goal is for page titles to be 59 char or less, including spaces. 
- ms.type – For almost all topics, use the topic type “article”. Exceptions: overviews use “overview” and planned-features uses “summary”. 
- ms.date – 01/21/2019 (always use mm/dd/yyyy format)
- ms.service – business-applications
- ms.assetid: xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx (this is needed only for topics generated with the Flow/PA authoring tool, and not for topics authored directly in GitHub.)

