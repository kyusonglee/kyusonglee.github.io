---
layout: post
title: Sequence Labeling
subtitle: How to setup non-interactive tests in DialCrowd Admin
tags: [sequence labeling, crowdsourcing, name entity recognition]
---

-  **Goals and Expectations:** The goal of this crowdsourcing feature is to categorize different types of entities. After entering the website of sequence labeling, the worker will be asked to select specific words or a phrase in a sentence and choose the corresponding type of entity that phrase can be categorized into to using the buttons below the sentence. If the worker is not sure which type of entity it belongs to, choose "other".

# Sequence Labeling
![Image](../img/sl-1.jpg)
**Figure 1**
![Image](../img/sl-2.png)
**Figure 2**

Figure 1 and figure 2 shows an overall process of creating a project of sequence labeling using DialCrowd:

- First, select a type of evaluation: non-interactive testing.
- Second, choose "Sequence Labeling"
- Third, click the "New Project" button and name the new project. Please also input your name and set the password.
- Finally, if you successfully create the "New project", you will see your project in the table. Please click the enter (edit) icon to start. We will provide several examples that you can follow.

## (1) Basic information 
In order to setup a new sequence labeling project, requesters need to fill out the following information:
![Image](../img/sl-3.png)
**Figure 3**

- After creating a new project, the requesters set the settings and configurations of his project.
- First, the requester puts down the background information and genereic instructions.
- Then, the requester sets the amount of work for the worker. (The above example indicates that 5 sentences will be shown to workers. Each sentence will be worked by 10 workers.)

## (2) Upload your data
The data can be uploaded by uploading a .txt file that contains the sentences for the workers to analyze using sequence labeling. Separate the sentences with line change in the txt file. The place where the requester uploads the file is marked in figure 3.

![Image](../img/sl-4.png)
**Figure 4**
Figure 4 shows the sentences that the requester uploads.

## (3) Add Class
You need to define class categories (e.g., inform, request, confirm, etc) and example sentences for workers.  
These exmaples will be shown in DialCrowd Workers. 

## (4) Save your project
## (5) Test and deploy
You can download the format for uploading your data. You can preview the DialCrowd Worker's website.




