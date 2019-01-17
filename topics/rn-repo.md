---
title: "Explore the Release Notes repo"
ms.date: 10/29/2018
ms.service: 
ms.topic: "conceptual"
author: "ReneeW-CPub"
ms.author: "renwe"
---
# Explore the Release Notes repo

The root of the [release notes repo](https://github.com/MicrosoftDocs/BusinessApplication-ReleaseNotes) contains an **articles** folder, which contains: 

- **April19** folder, which is for features that will release between April and September 2019 and for preview features going into preview between February and July 2019. 
	- For any features held back for the 2/21 disclosure moment, don't use the master branch. Use the **tierl-042019** branch. 
- **October18** folder, which is for features that will release between October 2018 and March 2019 (inclusive)
- **April18** folder, which is for features that released between April 2018 and September 2018 (inclusive)

Each version folder (April19, October18, and April18) contains:
- **toc.md**, which controls the left nav for all products in that release
- **change-history.md**, which contains information about additions, deletions, and other changes in all products in that release
	- **Note:** April19 does not have a change history topic yet. We don't need one until after it ships for the first time.
- a folder for each product area 


Each product-area folder contains:
- a topic that summarizes the product area (named **index.md** under October18 and April19 and **overview.md** under April18)
- a topic that indicates a release date for each feature (named **planned-features.md** under October18 and April19 and **whats-new…md** under April18)
- a topic for each feature
