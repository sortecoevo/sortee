---
banner: /blog/images/2025_Code_club.png
date: "2025-03-24"  
author: Cecilia Baldoni & Corné de Groot
summary: The authors debrief about the latest code club meeting, all to do with improving messy code!
categories:
- blog
tags: 
- code club
- code
- open science
title: "SORTEE Code Club debrief: Decode the Code (March 18th)"

---
&nbsp;

*The Member Engagement Committee runs Code Club every third Tuesday of the month. Time can vary depending on the host and will be announced at least two weeks in advance on [SORTEE’s Slack](https://www.sortee.org/join/). For more information, see [SORTEE’s Code Club page](https://www.sortee.org/code_club/).*  
  
On Tuesday, March 18th, the SORTEE Code Club gathered again for a hands-on session to improve messy code. This time, we worked with a pre-prepared script (which one participant jokingly called a "monster" script!) shared on GitHub before the meeting, allowing participants to explore it locally . The session brought together six participants, split into two breakout rooms. Each group tackled the script in their own way. While the code ran correctly, we quickly found areas where clarity, readability, and documentation could be improved.  
  
One of the coolest things that happened during this session was when a SORTEE member, who couldn’t join live, still managed to grab the script from [the SORTEE Code Club GitHub](https://github.com/SORTEE/CodeClub), dissect it in their own time, and send us their thoughts. Not only was it great to see their perspective, but it also proved that having our materials publicly accessible meant anyone could join the fun and contribute in their own time—even if a session’s timing isn’t convenient, anyone can still participate and contribute in their own time!    
  
&nbsp;  
  
**Issues and Best Practices**

Participants identified several instances of coding malpractice and areas for improvement. Some key takeaways included missing library imports, inconsistent formatting, and hard-coded variable selections. The script contained a for loop that could be replaced with the more efficient `ifelse()` function, and a missing `set.seed()` call meant that random sampling results were not reproducible. Additionally, one variable was named `c`, which conflicted with the built-in `c()` function in R.  
  
In general, the script lacked sufficient comments and explanations. Several sections would benefit from clear documentation to explain why a specific approach was taken and what each line or section of code accomplishes. Participants also noted that the assignment operator `<-` is preferred over `=` in R, and that using `TRUE` and `FALSE` instead of `T` and `F` avoids potential confusion.  
  
Did you spot any additional malpractice or areas for improvement? We’d love your input! Feel free to open an issue or submit a pull request on our GitHub repository. The more perspectives we have, the better we can make our code!
See you at the next Code Club session!  

&nbsp;  
  
**What’s next?**  
The next Code Club meeting will be **on Tuesday, April 15th at 8:00-9:00h UTC +00:00** (zoom link will be posted on [SORTEE’s Slack](https://www.sortee.org/join/)). The next session will be a training session where we will give an Introduction to Reproducible Coding Environments. 
  
You can check the [Code Club schedule here](https://docs.google.com/spreadsheets/d/1rOOOE7ghPduwtFftG0DJJf0DXVigAdcmQ0xdEwbKQXo/edit?usp=sharing) for upcoming meetings.  
To receive calendar invites in your local time zone, [sign up here](https://forms.gle/yKrEm6xAKZtom5kt7).  
  
**Suggest a topic**  
To propose a Code Club meeting topic, please use [this form](https://forms.gle/eZy81dUymiZNJetu8).  
  
