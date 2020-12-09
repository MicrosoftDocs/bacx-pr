---
title: "Topic types | MicrosoftDocs"
ms.date: 11/20/2020
ms.service: 
ms.topic: "conceptual"
author: "tonyafehr"
ms.author: "tfehr"
manager: "AnnBe"
---

# Topic types

There are several content types, each of which uses a unique way to provide information to the user. Each topic type has been designed to deliver information in the most effective way. Because Dynamics 365 content is written for a variety of audiences, this topic shows the different content types that we use for each audience. 
<!--note from editor: Renee to add CE and PP examples. Also add links to relevant info about RP guidelines that Erica and Ashley are writing. -->
<!--note from editor: Renee to look for topics we can convert to this new style (new for CE and PP) so I can add examples here. Also, get CE and PP doc leads to review. What needs to have an exception? I'm thinking mostly in the PP content. -->
<!--note from editor: I think we need to include or have a separate topic about the standard TOC for a product. Looking at F&O, the TOCs consistently contain most of these topic types in a specific order. I'd like to do that across the CE and PP content, too. -->

- [Home page](#Home_page)
- [Overview](#Overview)
- [Get started](#Get_started)
- [What’s new](#What's_new)
- [Deprecated](#Deprecated)
- [Procedure](#Procedure)
- [Accessibility](#Accessibility)
- [FAQ](#FAQ)
- [Troubleshooting](#Troubleshooting)
- [Glossary](#Glossary)

## <a name="Home_page">Home page</a>
These are also known as *landing pages*. A home page does not just mirror the TOC nor should it be a link farm, but instead is should provide some overview information and possibly graphics that are helpful to the reader. 

### Title 
- Use “home page”, lowercase and two words, at the end of the topic title. 
- Do not use “landing page” or “welcome”. 

### Example 
[System administration home page](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/sysadmin/system-administration-home-page)


## <a name="Overview">Overview</a>
An overview topic describes what the user can do with this feature using plain terms and no jargon. Think about why the user would use this feature or product and write your topic to address this. 

An overview topic can contain but is not limited to this kind of content:

- Overview information
- Problems and solutions
- Definitions and descriptions
- Business process or architectural information
- Examples

All or a combination of those elements can be used to describe:

- What the user can do with a feature or product using plain terms and no jargon. 
- Key concepts that a user must understand to complete a task successfully.
- The situations that the topic material might apply to.
- Business process or architectural information. 
- Instructions about where and how users need to make decisions.

### Title
- Use a noun phrase for the title. 
- In general, use singular nouns. However, it’s okay to use a plural noun when the plural is obviously more suitable.
- Be careful about using “overview” in the title. Most noun phrases can stand on their own without “overview.”
- Do not use these terms in the title: Summary, User guide, Welcome

### Example
[Dual-write overview](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/data-entities/dual-write/dual-write-overview)
<!--note from editor: Add more examples that don't have overview in the title, since that's a recommendation for this type.-->

## <a name="Get_started">Get started</a>
A Get started topic provides information that will help users get started with a particular product or feature. These topics often describe at a high-level the things that users must consider and the decisions they must make in order to complete a task or series of tasks. 

Here are some things that you might want to consider when writing a Get started topic:

- List any needed prerequisites, such as required software, required tasks, or required permissions.
- The information in this topic needs to be listed in the order in which a user would complete the configuration of tasks.
- You might include both overview and procedural information in a Get started topic, basically anything needed to get the user acquainted with what they need to do to get started. 

### Title
- Write as “Get started  with &lt;Product name&gt;” or “Get started  with &lt;feature&gt;”, depending on the content in the topic. 
- Do not use “Getting started” in the title.  
 
### Example
[Get started with the Electronic invoicing add-on](https://docs.microsoft.com/dynamics365/finance/localizations/e-invoicing-get-started)

## <a name="What's_new">What's new</a>
This topic provides resources where you can learn about the new features that have recently released or new features that will be releasing over the next few months. These topics should not contain any feature descriptions. For feature descriptions, provide a link to the feature description in the release plans. Do not include any feature information that has been postponed.

If needed, you can break this information into subsections.

Some teams include a section for “In development”. This is where you can provide a high-level overview of features expected in the next release.

### Title
- Write as either “What’s new in &lt;Product name&gt; &lt;version&gt;” or “What’s new or changed in &lt;Product name&gt; &lt;version&gt;”, depending on the content in the topic. Including version information is optional. 
-	Do not use “New features” in the title.  
 
### Example
[What's new or changed in Finance and Operations apps home page](https://docs.microsoft.com/dynamics365/fin-ops-core/fin-ops/get-started/whats-new-changed?toc=/dynamics365/fin-ops-core/dev-itpro/toc.yml)


## <a name="Procedure">Procedure</a>
Procedural topics instruct a user on how to complete a task. This can be both frequent and infrequent user tasks. This topic answers the question "How do I do this?" by presenting a series of procedural steps. For this kind of content, you can – and should – include applicable conceptual information together with the procedures, if appropriate.

Sometimes procedureal content is about planning how to do something, like defining the organization structure and setting up the chart of accounts. This kind of content should include any “gotchas” related to the planning decisions that users will make.

Here are some things that you might want to consider when writing a procedure:

- List any needed prerequisites, such as required software, required tasks, or required permissions.
- When deciding how to organize the tasks, first think about whether the tasks are sequential. If they are, list them in that sequential order. If the tasks aren’t sequential, focus first on the tasks that most users will have to do, and include the less-common tasks later in the topic.
- If there is a series of tasks, include an introductory sentence or two that describes the procedures and why or when they should be completed.
- At the end of the topic, include a "Next steps" section and add a link to where the user should go next, if applicable.
- These topics typically have an "Additional resources" section, to point the user to additional information about the subject. 

### Title
- Always use precise, imperative verbs, which tell the user what to do, like “Set up” or “Configure.” 
- Avoid vague verbs, such as “About” or “Using.”
- After the verb, use a plural noun phrase unless the noun is uncountable. 

### Example
[Manage robots.txt files](https://docs.microsoft.com/dynamics365/commerce/manage-robots-txt-files)


## <a name="Deprecated">Deprecated</a>
A deprecated topic describes features that have been removed, or that are planned for removal from a particular Dynamics 365 product, such as Dynamics 365 Commerce. Basically, this topic is intended to help customers consider these removals and deprecations for planning purposes.

- A *removed* feature is no longer available in the product.
- A *deprecated* feature is not in active development and may be removed in a future update.

### Title
- Titles should be written as “Removed or deprecated features in &lt;Product name&gt;".

### Example
[Removed or deprecated features in Dynamics 365 Finance](https://docs.microsoft.com/dynamics365/finance/get-started/removed-deprecated-features-finance)


## <a name="Accessibility">Accessibility</a>
Accessibility topics describe the functionality that is designed to help users who have various disabilities use a product. Complying with Microsoft Accessibility Standard (MAS) requirements makes sure that our content is created in such a way that it maximizes accessibility for people with disabilities and supports users of various input methods and devices.

Some common sections in an accessibility topic might include: 

- Windows Narrator and keyboard-only access
- Shortcuts for the most frequently performed actions
- Navigation search
- Action search for keyboard-only users or for heads-down data entry
- Tab sequence
- Form patterns
- Responsive layout
- Guidance to help developers and customers incorporate accessible thinking in their customizations

### Title
- For SEO, titles should be “Accessibility features”.

### Example
[Accessibility features]( https://docs.microsoft.com/dynamics365/fin-ops-core/fin-ops/get-started/accessibility-features?toc=/dynamics365/human-resources/toc.json)


## <a name="FAQ">FAQ</a>
Write an FAQ to introduce concepts that the user needs to understand. Include only the concepts that are related to work that the user is trying to do. Write questions that are likely to be asked. You can include any combination of Who, What, Why, Where, When, and How questions that you need. You don't have to include all of these types. Provide answers to all of the questions. 

Be careful not to use an FAQ as a catchall topic. In most cases, this kind of content can fit into existing content to fill in gaps or troubleshooting issues. If an FAQ topic is needed, most likely the content will be based on customer/partner questions that cannot be answered by adding content to existing topics. 

Each heading should be the written in the form of a question. The subsequent section will include the answer. 

#### Writing questions 
- Make sure that you understand who the audience is for your topic. Identify the types of questions that this user would ask. 
- Phrase the questions as if the reader is asking them. Say what can I, instead of what can you. 
- Be sure that the questions are likely to be asked. Don’t make up a question to fit existing content. Instead, identify the questions and then revise the existing content to answer questions that users would ask. 
- Focus on writing questions that are related to customer tasks or scenarios, not on describing the UI. 
- Organize the questions in a logical order. For example, consider the following options: 
  - Most general to most detailed 
  - Most common to least common 
  - Least technical to most technical 
- If your topic has more than 10 questions, consider whether the topic can be subdivided. If the topic has only 3-4 questions, consider whether it can be combined with an existing non-FAQ topic. 

#### Answering questions
Include at least one sentence for the answer and if needed, include tables, lists, links, graphics, or any other type of content that is needed to answer the question. 
If you include a yes/no question, start the answer with Yes or No. Then add explanatory information. 

### Title
- Use a noun phrase for the title. 
- Always include “FAQ” at the end of the title. Do not spell out “frequently asked questions”. 
- The title should not include "Q and A" or “Q&A”.

### Example
[LinkedIn integration FAQ](https://docs.microsoft.com/dynamics365/talent/attract-linkedin-faq)


## <a name="Troubleshooting">Troubleshooting</a>
Write a troubleshooting topic to provide information about how to avoid problems that users are likely to have and how to solve these problems. Arrange the topic in order according to how frequently issues seem to occur, with the least-common issues coming last in the topic. 

For each problem that is addressed, provide a solution. Many problems have multiple possible solutions. After the solutions, tell the user where to go for more information.

- Use H2 headings for each issue so the issue shows up as an "In this article" link.
- Phrase each issue as a problem, not question, if possible.
- Include punctuation at the end of the H2 issue headings (period or question mark).
- Phrase each issue in first person (if it makes sense).
- Phrase responses in second person.
- Unless the issue is *very* simple (single sentence/paragraph answer), split the response using H3 headings, with "Issue description" and "Issue resolution". In some cases, you may need to use additional H3 headings, such as when there are multiple/different resolutions.
- Include full error message text in the H2 heading, if possible (such as: "I received the following error message: "..."). Users will be searching for this error text. If needed, you can shorten the error text by adding ellipsis and then using a block quote to include the full error text in the body.
- Create troubleshooting topics at the lowest TOC level, and place them last in the node. The issues in the troubleshooting topics will apply to the topics in that node, and be named after it. 

### Title
- Always include “Troubleshoot” at the start of the title. 
- Use a noun phrase for the title that matches the name of the parent node in the TOC. 

### Example
[Troubleshoot inbound warehouse operations](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/troubleshoot-warehouse-inbound)


## <a name="Glossary">Glossary</a>
A glossary provides an alphabetical list of definitions for words, phrases, and acronyms that are used for a product or product area. 

In general, a glossary term is:

- A key concept that is highly relevant to the product and helps users understand the product.
- Not part of the common English language, as defined by a standard dictionary such as The American Heritage Dictionary.
- Frequently used within the documentation.

The following best practices ensure that terms and definitions are consistent in a glossary. 

- Use the singular form of the term. 
- Use lowercase for the term, unless it is a proper noun. Check the style guide to see if the term is listed and follow the capitalization. 
- Enter acronyms, abbreviations, and initialisms in their full form, and include the abbreviated form in the definition. 
- Don’t restate the term as the definition. For example, don’t define tax hierarchy as A hierarchy of taxes. 
- Don’t copy definitions word-for-word from existing, non-Microsoft sources. 
- Be sure that other key concepts in the definition have also been defined. 

Be sure to write each letter of the alphabet as an individual H2 section, so that each letter of the alphabet is listed in the "In this article" pane. This makes it easy for readers to navigate the glossary. 

### Title
- Use either the standalone term “Glossary” or precede “glossary” with a product name, such as “Commerce glossary”. 
<!--note from editor: See this page. The lower left area has "Terms and concepts" instead of "glossary". What to add here about that? https://docs.microsoft.com/en-us/dynamics365/customer-insights/ -->


### Example
[Engagement insights capability glossary](https://docs.microsoft.com/dynamics365/customer-insights/engagement-insights/glossary)
