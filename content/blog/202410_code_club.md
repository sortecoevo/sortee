---
banner: /blog/images/202410codeclub.png
date: "2024-12-09"
author: Natalie van Dis
summary: Publishing our code and data is an important Open, Reliable, and Transparent practice to ensure the reproducibility of research. To facilitate the production and reviewing of code, Arthur Rodrigues and Natalie van Dis hosted the Code Club meetings of October and November with a Hackathon aimed at Creating a Code Standard.
categories:
- blog
tags: 
- open-code
- code-club
title: "Debrief of SORTEE Code Club: Hackathon ‘Creating a Code Standard’ - Wednesday October 16" 
---
&nbsp;

*The Member Engagement Committee runs Code Club every third Tuesday of the month. Time can vary depending on the host and will be announced at least two weeks in advance on [SORTEE’s Slack](https://sortee.org/join). For more information, see [SORTEE’s Code Club page.](https://www.sortee.org/code_club/)*   

&nbsp;

### ‘Creating a Code Standard’
Publishing our code and data is an important 
Open, Reliable, and Transparent practice to ensure the reproducibility of research. 
To facilitate the production and reviewing of code, 
[Arthur Rodrigues](https://avrodrigues.github.io/) and [Natalie van Dis](https://scholar.google.com/citations?user=UTC6iJMAAAAJ&hl=nl&oi=ao) hosted the Code Club meetings of 
October and November with a Hackathon aimed at Creating a Code Standard.  

### What is a Code Standard and why do we need one?
The Code Standard we are writing is a piece of code with accompanying metadata files 
that implements the best Open, Reliable, and Transparent (ORT) coding practices 
for the field of Ecology and Evolution. 

While there are already many nice resources on ORT coding for our field 
([see here](https://hackmd.io/@8fJ_d1O7Thq_0GNEZ0O-MA/SJqbq-ZkJl#Useful-links) for some examples), 
these existing resources are all descriptions of coding practices. 
The Code Standard is meant to supplement these resources with **a real-life example 
of a common ecology/evolution analysis that can be used as an accessible 
and easy way to implement ORT practices in your own code.** 
It’s just as if a colleague shares their code with you to show you how they 
implement ORT coding practices!

### Deciding what is perfect ORT code
The goal is to make the Code Standard as perfectly Open, Reliable, and Transparent as possible. 
But when is code perfectly ORT? 
That’s what the Hackathon was all about: to decide as a community what we consider 
to be perfect ORT code in Ecology & Evolution. 

During two online interactive hackathon sessions, 18 participants reviewed, 
discussed, and rewrote an existing piece of code - 
focusing on the [4Rs of code review](https://www.sortee.org/blog/2024/03/06/2024_code_club_kickoff/) (Reported, Run, Reliable, Reproducible) 
to make the code as ORT as possible. A poll on [SORTEE’s Slack](https://sortee.org/join) indicated 
that R is the coding language that is mostly used by the community. 
So we worked on an existing piece of R code [from a published paper,](https://doi.org/10.1098/rspb.2023.0414)
performing a relatively simple and common ecology/evolution analysis.

&nbsp;

![Slack poll](/blog/images/202410codeclub.png)    
*Slack poll: which coding language is mostly used in the Ecology and Evolution field?*

&nbsp;

Hackathon participants identified ORT aspects that the code needed to improve on, 
noting down their recommendations in the Hackathon’s [HackMD file.](https://hackmd.io/@8fJ_d1O7Thq_0GNEZ0O-MA/SJqbq-ZkJl) 
They then implemented these recommendations by using git to edit the code in 
[the CodeStandard Github repository.](https://github.com/SORTEE/CodeStandard)

### Key ORT practices in the Ecology and Evolution field
For each of the 4Rs of code review (Reported, Run, Reliable, Reproducible), 
Hackathon participants identified ORT practices that make it as easy as possible 
for someone else to understand, run, and reuse your code. 
Some key practices include:

- Reported: Add comments in the code to improve match between methods section and code.

- Run: Use [R projects](https://bookdown.org/ndphillips/YaRrr/projects-in-rstudio.html) & the [R package renv](https://rstudio.github.io/renv/articles/renv.html) to create easily reproducible R environments.

- Reliable: Add explicit checks in the code to make sure it does what is intended. 
For example, implement tests in your code checking that data wrangling steps have the desired outcome (e.g. number of rows are as expected after a filtering step) or checking that the degrees of freedom in your analysis are as expected.

- Reproducible: Make sure your whole data wrangling and analysis workflow is code-based.

**Check out the [CodeStandard Github repo](https://github.com/SORTEE/CodeStandard) for an example on how to implement these practices in your own coding!** (But note: still under construction 🙂)

&nbsp;

![Code standard repo](/blog/images/202410_2_codeclub.png)   
*Code edits made with git during the Hackathon to make a piece of R code as perfectly ORT as possible.*

&nbsp;

### Code Standard expected to be finished end 2025
Thanks to all the participants, 
the Hackathon sessions were a great start to the writing of a Code Standard 
for the field of Ecology and Evolution! 
We plan to finish writing the Code Standard in the coming year. 
Keep an eye on the [CodeStandard Github repo](https://github.com/SORTEE/CodeStandard) for more best ORT practices and how to implement them 
in your own coding.

### What's next
The two Hackathon sessions this November and December were the last Code Club meetings of the year. 
The Member Engagement Committee plans to start up the meetings again with a new Code Club Leader at the beginning of next year. 
Keep an eye on [SORTEE’s social media channels](https://linktr.ee/sortecoevo) and [SORTEE’s Slack](https://sortee.org/join/) for the next Code Club meeting!

You can check the [Code Club schedule here](https://docs.google.com/spreadsheets/d/1rOOOE7ghPduwtFftG0DJJf0DXVigAdcmQ0xdEwbKQXo/edit?usp=sharing) for upcoming meetings. 
To receive calendar invites in your local time zone, [sign up here](https://forms.gle/yKrEm6xAKZtom5kt7).    

### Suggest a topic
To propose a Code Club meeting topic, please use [this form.](https://forms.gle/eZy81dUymiZNJetu8)
