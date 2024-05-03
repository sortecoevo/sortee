---
banner: /blog/images/202404codeclub.png
date: "2024-05-03"
author: Natalie van Dis
summary: In this month’s Training Session, Stefan Vriend, Freddy Hillemann and Joey Burant hosted a workshop on how to code review a manuscript, using a checklist they developed for Ecology and Evolution.
categories:
- blog
tags: 
- open-code
- reproducibility
- code-club
title: "Debrief of SORTEE Code Club: Code Review Checklist for Ecology and Evolution - Tuesday April 16" 
---
&nbsp;

*The Member Engagement Committee runs Code Club every third Tuesday of the month. Time can vary depending on the host and will be announced at least two weeks in advance on [SORTEE’s Slack](https://sortee.org/join).*


In this month’s Training Session, Stefan Vriend, Freddy Hillemann and Joey Burant hosted a workshop on how to code review a manuscript, using a checklist they developed for Ecology and Evolution.

### Data and peer-reviewed code in one place
Stefan, Joey and Freddy have experience with data and code reviewing through their work on the [SPI-Birds](https://spibirds.org/en) and [CoreBirds](https://www.researchgate.net/publication/372427302_CoreBirds_Connecting_Open_Research_outputs_in_the_Ecology_of_Birds) projects. These projects focus on creating data and code standards for studies of individually-marked birds, as well as the development of a metadata repository and library of standardized code. They aim to have the data and peer-reviewed code stored together in one place to increase study reproducibility.    

&nbsp;

[![checklist](/blog/images/202404codeclub.png)](https://osf.io/kncw6/wiki/home/)

&nbsp;

### 17-step checklist to facilitate code review

We learnt about the 4 R’s (Reported, Run, Reliable, Reproducible) in [an earlier Code Club session](https://www.sortee.org/blog/2024/03/06/2024_code_club_kickoff/). Stefan, Joey and Freddy developed a code review checklist consisting of 17 questions that operationalize the 4R’s, making them more concrete.    

Through an interactive demo, we learnt how to use this checklist for code review, highlighting some common code mistakes as well as tips to improve our own code. You can view the checklist and all the workshop material we used [here](https://osf.io/kncw6/).    

We first went through questions related to the 4 R’s. For example, in the paper used for the demo, all the analysis steps reported in the methods were found back in the code, but not vice versa. A big plus was that one could reproduce the manuscript Figures with the provided code, which is often not included. However, there was still some package versioning missing (Reproducibility). The code was also not consistently commented throughout, for example making it hard to judge whether code errors were taken into account or if these errors indicated mistakes in the analysis (Reliability).   

We then went through additional considerations included in the checklist, related to Organisation & Structure (e.g. code readability, consistent formatting) and more opinionated considerations related to code efficiency. Stefan’s tip for code readability: “The more space and room to breathe, the more readable your code!”    

### What’s next?
The next Code Club meeting will be a **Hacky Hour on Tuesday May 21 at 8-9h UTC +00:00** (zoom link will be posted on [SORTEE’s Slack](https://sortee.org/join)).  We will do a code review exercise and kick off the “Find an ORTEE Code Reviewer list” to supplement the already existing [Find an ORTEE Reviewer list](https://docs.google.com/spreadsheets/d/13akCaEoyy-9XBOqEqaXXNRd9EXC4W7cVSjjisOdtJhk/edit#gid=0).

In the code review exercise, we will practice with (1) sharing code, (2) setting a goal for code review, and (3) doing code review using the 17-step checklist. You can bring a piece of your own code (old or new) for the exercise, for example code using the base R `mean()` function (read about the code mistake to look out for in [the previous Code Club debrief](https://www.sortee.org/blog/2024/04/04/202403_code_club/)). Don’t know what to bring? No worries, there will be pieces of code ready for you to use in the exercise.   

You can check the [Code Club schedule here](https://docs.google.com/spreadsheets/d/1rOOOE7ghPduwtFftG0DJJf0DXVigAdcmQ0xdEwbKQXo/edit?usp=sharing) for upcoming meetings. To receive calendar invites in your local time zone, [sign up here](https://forms.gle/yKrEm6xAKZtom5kt7).    

### Suggest a topic 
To propose a Code Club meeting topic, please use [this form.](https://forms.gle/eZy81dUymiZNJetu8)
