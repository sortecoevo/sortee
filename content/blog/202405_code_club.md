---
banner: /blog/images/202405codeclub.png
date: "2024-06-04"
author: Natalie van Dis
summary: In May’s Hacky Hour, we did a code review exercise using the 17-step checklist for Ecology and Evolution. Participants reviewed each other’s code or that of already published papers and discussed what would constitute the “perfect” piece of Open, Reliable and Transparent (ORT) code.
categories:
- blog
tags: 
- open-code
- reproducibility
- code-club
title: "Debrief of SORTEE Code Club: Hacky Hour Code Review Exercise - Tuesday May 21" 
---
&nbsp;

*The Member Engagement Committee runs Code Club every third Tuesday of the month. Time can vary depending on the host and will be announced at least two weeks in advance on [SORTEE’s Slack](https://sortee.org/join).*   

In May’s Hacky Hour, we did a code review exercise using the [17-step checklist for Ecology and Evolution.](https://www.sortee.org/blog/2024/05/03/202404_code_club/) Participants reviewed each other’s code or that of already published papers and discussed what would constitute the “perfect” piece of Open, Reliable and Transparent (ORT) code.   

### Request a code review on SORTEE’s GitHub
For the code exercise, participants were split into pairs and exchanged their code with each other or they worked on an already published paper. We worked with a [HackMD](https://hackmd.io/@8fJ_d1O7Thq_0GNEZ0O-MA/H19cC3Nm0) file and submitted our code review request as an issue on [SORTEE’s Code Club GitHub.](https://github.com/SORTEE/peer-code-review/issues) Note that you can request a code review via this GitHub anytime, also outside of Coding Club hour! Join [SORTEE’s Slack channel](https://sortee.org/join) #code_club and request for your GitHub account to be added as a member.    

&nbsp;

[![checklist](/blog/images/202404codeclub.png)](https://osf.io/kncw6/wiki/home/)

&nbsp;

### Short and focused code review sessions by formulating a goal
Code reviews can be extensive and in-depth, but they can also be short and focused. To practice short and focused code reviews, participants formulated a clear goal for their code review, for example focusing on one of the 4 R’s of code review (Reported, Run, Reliable, Reproducible) or one of the other sections highlighted in the [17-step code review checklist for Ecology and Evolution.](https://forms.gle/7bmDwTg7DiFGZqPt5)    

### In search of the ‘perfect’ ORT code: Reported   
Focusing on code review goal ‘Reported’, participants discussed what code aspects would constitute the ‘perfect’ Open, Reliable and Transparent (ORT) piece of code. How much code should one include? There is an obvious trade-off between completeness and accessibility of the code. Participants agreed that in the context of Open Science, anything you share should be easily accessible and understandable. Thus you should only publish code that is relevant for your manuscript - i.e. the code that reproduces your reported results and matches your methods from A to Z - but leave out additional code you also ran but did not end up in the manuscript (for example, code for exploratory figures and data wrangling that you used to wrap your head around the dataset). 

Participants felt it is important to publish code for both the actual statistical analysis as well as the data wrangling done beforehand, because coding errors during data wrangling can have a large impact on downstream analyses. For example, indexing the wrong data column has catastrophic effects for the reliability of your results (see for examples [SORTEE’s library of code mistakes](https://docs.google.com/presentation/d/12QN3WUc5v1Df7OArEox2U7l_N_qnHHuwzjCYiI4idC8/edit?usp=sharing)). In the best case scenario, you would deposit both the raw data and all the code to reproduce data wrangling and the statistical analysis. However, even if you are not able to openly publish the raw data files - for example because the data provider did not agree to this sharing - it is important to still publish the data wrangling code (in a separate script) that produced the processed data files you eventually used for analysis (main script). In that case, the ‘perfect’ piece of code would include a simulated dataset that resembles the raw dataset you were unable to share.   

### What's next
The next Code Club meeting will be a **Training Session on Tuesday June 18 at 13:00-14:30h UTC +00:00**. Note the different time and duration compared to previous meetings! (zoom link will be posted on [SORTEE’s Slack](https://sortee.org/join/)). Steffi LaZerte will host a workshop on how to code your own website hosted on Github!   

In the first half of the workshop, Steffi will take us through the basics of coding your own website by showing [her own personal website](https://github.com/steffilazerte/steffilazerte.github.io) as an example. In the second half, you will get to put this information into practice and start coding your own website, gaining some experience with version control via git and Github in the process.    

You can check the [Code Club schedule here](https://docs.google.com/spreadsheets/d/1rOOOE7ghPduwtFftG0DJJf0DXVigAdcmQ0xdEwbKQXo/edit?usp=sharing) for upcoming meetings. To receive calendar invites in your local time zone, [sign up here](https://forms.gle/yKrEm6xAKZtom5kt7).    

### Suggest a topic 
To propose a Code Club meeting topic, please use [this form.](https://forms.gle/eZy81dUymiZNJetu8)
