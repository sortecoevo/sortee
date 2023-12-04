---
banner: ../img/logo.png
date: "2023-12-05"
author: Andrew Anderson
categories:
- blog
tags: 
- open-code
- reproducibility
title: "Setting the record straight: how data and code transparency caught an error and how I fixed it" 
---
&nbsp;

### "We were unable to reproduce your results, and I think the reason is that there is a bug in how you are calculating your correlation coefficients."

&nbsp;

That was part of an email I got this summer that absolutely crushed me. It doesn’t take much empathy to feel that knot in your stomach and existential dread from imposter syndrome, especially if you are currently a graduate student, post-doc, or another early-career researcher. What happens when you or someone else catches an error post-publication is not something most scientists know, certainly none of my peers or advisors did, but I got to experience the process from a supportive group of colleagues, advisors, and journal editors. I’m not writing this piece to commiserate on the fears, anxieties, and setbacks we have as scientists, nor am I going to belabor the details of the analysis or the justifications/explanations of how I missed the error; I’m writing this because the larger picture of the scientific process, when aided by data transparency, works to make our collective knowledge better.

The genesis of this paper was born out of both the direction I envisioned my research heading and the fact I couldn’t generate new data for the last two years of my PhD. My advisor changed institutions and I opted to stay to finish out my degree, so we came up with the idea to use publicly available genomes to answer questions about larger patterns of sexual selection. That analysis stretched through my post-doc until I got [a paper published that I am really proud of](https://academic.oup.com/evolut/article/76/6/1331/6882231). The paper itself is a testament to data transparency; I used public genomes and published transcriptomic data from a number of sources to generate a full story. This was my sixth publication, and by now my advisor had instilled in me a need to make all my [code available on GitHub](https://github.com/AndersonDrew/Primate_ARE), even if I wasn’t putting out a usable program.

About a year after the publication, I got that fateful email. To be clear, the line I shared was about halfway through the text of the email, the beginning was a description of what they were trying to do and how my paper shaped their research question. What was especially helpful was the fact that they could reproduce my results using my code, but the code they had written had given them conflicting information which was why they went through my code and notations. Further, they went through and identified where they thought my code had gone wrong and provided a side-by-side analysis of how their recommendation would change the data. With their recommendations, I went back and reanalyzed all the data and did various sanity checks to confirm they did, in fact, catch a mistake and it did alter my results.

I didn’t know what to do at this point, but my advisor stated we should contact the journal and find out if they wanted a corrigendum (a statement of error) with the correct values. After a dialogue with the editors, we decided the new values could alter the interpretation enough that the paper should be a retraction/resubmission. While I worked on fixing the data and how I interpreted it, [the journal put out a statement of concern](https://academic.oup.com/evolut/article/77/10/2340/7254508). After about a month of work to ensure there were no other mistakes and adjusting figures, I submitted the new draft where the editors reviewed the changes. From there, type-setting and other editing was done as with all papers and [it was published](https://academic.oup.com/evolut/advance-article/doi/10.1093/evolut/qpad181/7440095) along with a [letter of retraction](https://academic.oup.com/evolut/advance-article/doi/10.1093/evolut/qpad182/7440094) from the editors based on what we had told them were the major changes.

As a researcher who wants to have correct data out there, this was an amazing process and the end result of a better paper feels good; but, in all honesty, as someone trying to land a tenure-track job, this felt bad. During the process everyone worked together to get the information right, and I was repeatedly told I did the right thing. Here’s the catch though: because my data and code were available there was no moral choice to make because I made it _before_ there was a problem. Once the error was found, the only option was to correct the record. Will this affect my future as a scientist? Who knows. But I do know I can stand behind my work, know that I can fix the record if I make a mistake (not planning on making a habit of it), and that participating in open data helps every scientist work together to propel our collective knowledge forward.

Some things I learned that I want others to know from this (with apologies if you’ve heard it before):
1. Document and upload ALL of your code. A lot of journals require this to publish, but be sure anyone can take your data from start to finish without filling in any gaps.
2.	Note why you are doing what you’re doing in your code. Admittedly, I didn’t do this enough in my code. As I went back through all of it, I realized what was “obvious” to me at the time was a lot more convoluted just a year later.
3.	Try to review code when reviewing a manuscript. This is especially hard and I’m not sure someone would’ve caught the error this way. Journals are moving in this direction. Alternatively, ask a colleague to review your code (preferably one that isn’t too deeply involved in your study).
4.	If you find an error in someone else’s work, write to the authors to inform them and lay out exactly what you suspect went wrong. I am grateful for the researchers who were so thorough in examining my original code.
5.	If you find or are informed of an error in your own work, take a breath and contact the journal to figure out how they want to move forward. You never know who’s reading your work and planning to pursue questions from your results. Remind yourself that they deserve to have a correct record.
6.	This is a big one: SCIENCE WORKS! We share data and knowledge and try to build on previous findings. When something doesn’t seem be correct, we can go back and refine or re-examine it.

&nbsp;

#### Acknowledgements
Thanks to my PhD advisor Adam Jones my post-doc mentor Suzy Renn for their support through the process, the Matt Dean Lab for bringing the error to my attention, and the editors at Evolution for their understanding and work in correcting the record.

&nbsp;

__Andrew Anderson__ can be found at:

[andersonevolve.com](https://andersonevolve.com/)

[@andersonevolve.bsky.social](https://bsky.app/profile/andersonevolve.bsky.social)

[@andersonevolve](https://twitter.com/AndersonEvolve)
