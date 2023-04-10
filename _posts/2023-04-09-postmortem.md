---
layout: post
title: A post-mortem of our project.
subtitle: What went well and what did not.
thumbnail-img: ""
cover-img: /assets/img/path.jpg
share-img: /assets/img/path.jpg
---

A postmortem of your development experience, where you discuss some of the issues that arose during the development of your process. You can (and should) include both negative and positive points; they will not count against your project mark. It is highly recommended that you include the last three items from the list above. Also ensure that you discuss the area you identified for improvement after your iteration 2 retrospective; how did it go? This should be informal, you can choose two or three of the following items to discuss, or something else you find interesting or relevant:


**What went right in the development process?**


We were able to implement the core features we needed: checkout, restaurants, search, users, etc.
Our initial planning was thorough, we didn't need to come up with new ideas later on.
We made good use of the gitlab features to keep our project organized. 
We communicated well and were on the same page. 


**What went wrong in the development process?**


HSQLDB implementation, establishing a connection and learning how to use it. 
We procrastined on work which made the days leading up to the deadline hectic. 
We had a fair amount of features that we weren't able to implement in time. 


**What would you do differently, if you had the chance to start over?**


Space out our work so that everything wasn't pushed till the end of each iteration.
Not overestimating how much we could get done per iteration.


**How large is the project (number of methods, classes, etc)? How much of this is (roughly) devoted to each major system component? And any other quantifiables (e.g. if you have a record of hours spent on tasks).**


Storage wise pretty large since we included a lot of image files in our assets and for our app.


**What took the most time? The least? Any surprises?**


The database and it's integration, merging branches and creating tests took the most time. 
UI related code and gathering information were the least time consuming since we used an API.
The website complexity, the amount of smells per iteration we recieved and having to switch our database implementation from SQLite to HSQLDB were surprizes. 


**Are there any particular design smells, or brilliant design decisions?**


We had an outstanding smell for using the builder design pattern in our restaurant constructor.

**Are there any outstanding bugs?**


TBD

**Did any features work better than expected?**


Unit tests were straight forward, SQLite before we removed it worked issue free right away as well.


**Are you using any technologies other than what was required (e.g. JMock, GUI builders, etc.)?**


We used an API that was preprocessed in python that we used for the database.


**Are you using any specific techniques covered in the course (TDD, pair programming, scrums, etc)?**


A lot of pair programming, working on features together and screen sharing to other team members. 


**How did the project change from your initial (iteration 0) vision or stories, or did it work out as predicted?**


The scope of our project shrunk, and we chose to focus on the most important features.


**What did you learn about team or large project development? What will you start doing, keep doing, or stop doing next time?**


We learned that in one feature there are many tasks so that everyone on the team can work on one feature simultaneously. We also learned that it's difficult to manage a larger team and organize tasks compared to individual projects.


**Can you draw any conclusions from what you’ve done?**


We came to the conclusion that communication is very important for these types of projects, more than we anticipated. We also realized how helpful the agile development methodology is, it allowed for more communication so that we were all on the same page with changes and keeping the project on track. 

