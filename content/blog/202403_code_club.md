---
banner: /blog/images/202403codeclub.png
date: "2024-04-04"
author: Natalie van Dis
categories:
- blog
tags: 
- open-code
- reproducibility
title: "Debrief of SORTEE Code Club: Hacky Hour - Tuesday March 19" 
---
&nbsp;

*The Member Engagement Committee runs Code Club every third Tuesday of the month. Time can vary depending on the host and will be announced at least two weeks in advance on [SORTEE’s Slack](https://sortee.org/join).*

In this month’s Hacky Hour, 9 participants shared their code mistakes, starting up [the SORTEE library of code mistakes!](https://docs.google.com/presentation/d/12QN3WUc5v1Df7OArEox2U7l_N_qnHHuwzjCYiI4idC8/edit?usp=sharing) The goal is twofold: the normalization of coding errors and building a resource of (common) code mistakes that you can use during code review.

&nbsp;

![SORTEE Code Club: Hacky Hour](/blog/images/202403codeclub.png)

&nbsp;

**Sharing code mistakes, problems, tips & tricks**

The Hacky Hour revolved around the 4 R’s of Code review - **R**eported, **R**un, **R**eliable, and **R**eproducible - that we learnt about in [the previous Code Club meeting.](https://www.sortee.org/blog/2024/03/06/2024_code_club_kickoff/) Participants shared their code mistakes, problems, tips and tricks in a collaborative document, practising with (Markdown language)[https://www.markdownguide.org/basic-syntax/] at the same time.

We learnt how to say ‘computer’ in 8 different languages as an icebreaker, followed by the opportunity to request a code review. We then discussed the best way to report software versions (**R**eported), how to use Quarto (**R**eported) and easy ways to keep track of memory and CPU usage in R (**R**un). You can read back what we discussed in [this HackMD document](https://hackmd.io/Pj5KsJSzQduk4zEYmlmkmg).

&nbsp;

**Sharing code mistakes: watch out with the mean() function in R!**

One of the coding mistakes shared among peers was about using the `mean()` function in R. This base function takes a vector of numbers (e.g. `c(2,4)`) and calculates the mean. But if one forgets to put the numbers in a vector, only the first number will be used to calculate the mean! Without giving any warning. The other numbers will be interpreted as arguments changing the function’s usage, which probably is often not the intended behavior by the coder…

```
> mean(2, 4)
[1] 2

> mean(c(2, 4))
[1] 3

```

&nbsp;

**What’s next?**

The next Code Club meeting will be a **Training session on Tuesday April 16 at 8-9h UTC +00:00** (zoom link will be posted on [SORTEE’s Slack](https://sortee.org/join)). We will discuss the development of a code review checklist for Ecology and Evolution.

Stefan Vriend, Joey Burant and Freddy Hillemann have turned the 4 R’s into a code review checklist for Ecology and Evolution. They will host a workshop where we will use this checklist to code review published papers, followed by a discussion on how it can be improved. 

You can check the [Code Club schedule here](https://docs.google.com/spreadsheets/d/1rOOOE7ghPduwtFftG0DJJf0DXVigAdcmQ0xdEwbKQXo/edit?usp=sharing) for upcoming meetings.
