---
banner: img/ECR_Asks_logo.png
date: "2025-09-26"
author: Oakleigh Wilson
summary: The fourth in the new blog series called ECR Asks, where early career researchers interview SORTEE members for advice.
categories:
- blog
tags:
- ECR Asks
title: "ECR Asks: Dr. Ed Ivimey-Cook"
---

'ECR Asks' is a series of Q&A sessions where I speak with experienced SORTEE members to explore their journey in, and perspectives on, open science and transparent research. With the goal of supporting early career researchers like myself, this series aims to answer big questions and share practical insights on navigating the ever evolving landscape of open science and academia.



I would like to sincerely thank Ed for sharing his time, experience, and tips with me. This conversation was an insightful glimpse into the challenges and future of code review with valuable advice for open science focused ECRs.

# Q&A

{{< figure src="/img/ed_ivimey-cook.jpg" width="200px" alt="headshot of Ed Ivimey-Cook">}} 

Peer review is a cornerstone of the scientific process where the collective scientific community collaborates to check the logic and rigour of each scientific advancement. As quantitative methods become increasingly central to all forms of research, a growing share of scientific progress and contribution now originates in the analysis of big data with complex code. Even small syntax errors in this analysis pipeline can propagate misleading and un-reproducible outcomes. To combat this, the analysis pipeline itself can be incorporated into the peer review process --- a process known as "code review". While code review is standard practice in pure-computational fields, it is still an emerging topic of discussion in ecology and evolution.

  

In this month's Q&A, I spoke with [Ed Ivimey-Cook](https://eivimeycook.github.io/), Senior Research Associate at University of Glasgow, Data Editor at [Ecology Letters](https://onlinelibrary.wiley.com/journal/14610248?gad_campaignid=22806695966&gad_source=1&gbraid=0AAAAADoE1amseeZF6QmlDC_pwO5S9qTmB&gclid=CjwKCAjwkvbEBhApEiwAKUz6-3o7eZFy3X3q21xiiz3ssICEfB7N9MiVpt7BYt2EccOtuxoSbuYshBoChYcQAvD_BwE&utm_campaign=R3MR425&utm_content=LifeSciences&utm_medium=cpc&utm_source=google), and current president of SORTEE. While Ed's primary research focuses on aging and parental effects, he has a strong focus on open science, with extensive publications that encourage transparent and reproducible code and data sharing. Ed joined me on August 13 to discuss the challenges and future of code review, and what we ECRs can do to ensure we are producing high quality code at the forefront of open science practices.

  

This interview has been edited for length and clarity.

## Current State of Code Review

ECR: In your 2025 preprint ['From Policy to Practice: Progress towards Data- and Code-Sharing in Ecology and Evolution'](https://ecoevorxiv.org/repository/view/8417/), you found that about half of all Ecology and Evolution journals encouraged or mandated data and code sharing, with more than half requiring this to be available during peer review. While your results suggest this request is mostly adhered to by the authors, in your 2023 paper, ['Implementing code review in the scientific workflow: Insights from ecology and evolutionary biology'](https://onlinelibrary.wiley.com/doi/10.1111/jeb.14230), you point out that code review isn't actually part of the current peer review process... Do you have any insight into or stats on how often the code that is provided during peer review is actually being checked?

  

EIC: Firstly, in my opinion as someone who reviews papers (and not just in my capacity as a data editor), I really like when there's data and code available during peer review. I do feel it gives me, the reviewer, a much deeper insight. For example, when a methods section is written with insufficient detail, being able to look at the code and see exactly what was done is really nice. For example, you might be able to see "oh, you've done some post-hoc testing and you've also corrected the p-values for multiple comparisons, okay, you've not actually said that you've done that, but you have". It's really great.

  

That being said, not everyone actually looks at this provided code and a review can still happen without it. The reviewer's job is to look at, for example, how appropriate the statistics are, but not necessarily whether you've done the function or written the code correctly. There's lots of reasons why a reviewer would not look at data and code. For one, it can be very time consuming and the peer-review process is already stretched thin as it is, and then, with code, it might be written in a programming language the reviewer isn't familiar with anyway (for instance the most common language in EcoEvo is R, but people use MATLAB, Python, Julia, C++ to name a few other languages). A full reproducibility check is not currently part of the peer review pipeline but as long as the data and code are up to standard, someone else can do a post-publication code review - although this may change as more journals recruit data and code editors (see recent pre-print: ['The SORTEE Guidelines for Data and Code Quality Control in Ecology and Evolutionary Biology'](https://ecoevorxiv.org/repository/view/9948/)). 

  

The more journals that mandate data and code sharing for peer review, the more the opportunity will be there for peer reviewing code. Whether or not people always do it is a different question, but we hope that there will be a move towards it in future.

## Improving Code Review

ECR: While things are moving in the right direction, not all authors are making their code and data available. How do we change that? In your 'Policy to Practice' paper, you write that journals have significant power to contribute to the increased data and code sharing, but who else might be able to incentivise change?

  

EIC: In my opinion, the influence has to come top-down. Starting with the funders, then the publishers, then the journals, and then that will lead to change for authors. Grassroots initiatives like SORTEE and other reproducibility networks are still vitally important though. 

  

Funders have a strong influence. I think if you can show that you are very pro-open science, that should be rewarded. In my own experience, it has always been received positively, but if it was more explicitly supported, it would be incentivised more (and I do believe in some countries and with some funders this has started to change for the better). This would also encourage publishing houses to engage more with open science policies. In our 'Policy to Practice' paper we found that there is sometimes quite a big discrepancy between publisher-level policies and what the individual journals accept. For example, we found that often journal-level data and code-sharing policies were at odds with the higher-level parent publisher --- which can be quite frustrating for the journal and also confusing for authors.

  

Finally, journals definitely do have massive influence with authors to start mandating data and code upon initial submission or after acceptance. While there are a lot of journals so an author could just choose to publish elsewhere, if the entire community shifts to requiring a more reproducible workflow with the assumption that data and code will be shared, then authors will eventually follow suit as well. In our paper we showed that when journals mandated data and code sharing, there was an overall increase in the amount of data and code shared.

  

ECR: While AI has dubious code-creating and problem-solving skills, a specialised AI agent can be trained to execute well-defined tasks. Is there any potential to use a specialised AI agent to run and review code?

  

EIC: That's a good idea, and there has been some work looking into this. [DataSeer ](https://dataseer.ai/)is an AI program developed by Tim Vines in 2019 that scrapes the methods section of a paper and matches it against the data to ensure consistency. It would make sense for there to be something like that for code. There was a paper released last year lead by Natalie Cooper talking about using large language models for coding (['Harnessing large language models for coding, teaching and inclusion to empower research in ecology and evolution'](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210X.14325)) that mentioned using AI for unit testing, so there's potential for it there too.

  

However, while I do think AI has its place, I'm quite reluctant to recommend it because whilst AI is very good at describing code, it still has its limitations. Currently, it doesn't really tell you why you're doing each section of the code and it can't necessarily link that code back to the manuscript's methods section. AI is becoming more powerful though, so while I do think there will always have to be a human involved to double-check everything, there will probably come a time when we have an AI that can match the code to the paper and run reproducibility tests.

## Code Review for the ECR: Tips, Tricks, and Code Clubs

ECR: In your experience as a reviewer and Data Editor, would you have any unexpected hints and tips for ECRs hoping to ensure their code lives up to fully open and transparent standards? 

  

EIC: As a 'Data Editor' I'm responsible for ensuring the data and code are up to a decent standard. I'm looking to check that the data and code are there and deposited with a persistent identifier e.g. a DOI in a suitable repository, along with metadata that adequately describes the data and code, and that everything links back to the manuscript. There are many small details I've noticed during this process.

  

Code annotations are super important. If you start with the idea of a reproducible workflow with the intention to be sending it to someone (even if maybe it's just yourself in 5 years' time), it helps to annotate your code thoroughly from the start, and will save you so much future work. In the annotations, my personal sticking point is defining which code produces exactly what figure or result (often called sign-posting), and making it clear how the code translates into the paper. For example, if you've done a lot of post-processing of figures, make it clear how this was done. Additionally, noting in your annotations how long a particular section of code is expected to run is very helpful too. If someone is going through trying to do a full reproducibility check, it can help them to know how much time and resources to set aside for each section. This is particularly the case for modelling papers. In these cases, where the model runs can take --- for example --- as much as 2 weeks, it's important to save all the model outputs along the way so it can be tested and reviewed without doing a full run.

  

There are a few little things that aren't always obvious within the code too. When working with stochastic methods that involve pseudo-random number generation, setting a seed is an important but often forgotten step but ensures that the same numbers are generated. The package ['withR'](https://withr.r-lib.org/index.html) is helpful for setting seeds for specific functions. In addition, uploading a session info file (sessionInfo())  that contains all the packages and the versions helps with full reporting of your exact environment, as well as giving citations to those important but often under-reported packages, like cleaning packages such as ['janitor'](https://cran.r-project.org/web/packages/janitor/index.html). 

  

Finally, it's really important to preserve the raw data. One of the biggest debates we have as data editors is 'what is raw data?' though. If you've done data extraction from images or videos, then technically the rawest form of data is then the images or the videos, but people are rarely uploading this and instead only upload the data they've extracted. Uploading truly raw data can be a bit tough if it's a large or long-term dataset, however you should, as a minimum, upload the data used for that specific paper.

  

ECR: Code review can also be done as a kind of internal and informal peer-to-peer review where you give your code to someone else you know and they go through it independently looking for any possible mistakes. I love this idea and would really like to set it up in my university. In your experience, how do you get these groups working and how can it be incentivised?

  

EIC: I really love the idea of incentivisation and I've done it before myself in some of my recent papers (.i.e, acknowledging or explicitly stating that someone performed a reproducibility check). It's difficult to talk about incentives because everyone has different motivations and different systems they're okay with, but in my case either someone has done a very basic code review on my stuff, and I've put them in the acknowledgements, or they've done a reproducibility check and were already an author on the paper. In terms of setting up code review groups, it helps to find people who are equally interested in reproducible research. SORTEE is the perfect place for that. We're a bit of a biased crowd, because we're all here because we're very pro-open science, but it means it's the right place to go to find people who share the same goals of improving code.
