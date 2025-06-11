---
banner: img/ECR_Asks_logo.png
date: "2025-06-10"
author: Oakleigh Wilson
summary: The second in the new blog series called ECR Asks, where early career researchers interview SORTEE members for advice.
categories:
- blog
tags:
- ECR Asks
title: "ECR Asks: Dr. Malgorzata Lagisz"

---
‘ECR Asks’ is a new series of Q\&A sessions where I speak with experienced SORTEE members to explore their journey in, and perspectives on, open science and transparent research. With the goal of supporting early career researchers like myself, this series aims to answer big questions and share practical insights on navigating the ever evolving landscape of open science and academia.

I extend my sincere thanks to Losia for taking the time to generously share her experience with me. I’m looking forward to applying everything I learnt from our conversation, and hope many ECRs will find her thoughts and guidance helpful.

# Q\&A

{{< figure src="/img/Losia_Lagisz.png" width="300px" alt="headshot of Malgorzata Lagisz">}}  

&nbsp;  

In this month’s Q\&A I spoke with [Malgorzata (Losia) Lagisz](https://mlagisz.weebly.com/), Research Fellow at the University of New South Wales, Sydney, Australia. Losia is a methodologist for evidence synthesis who specialises in designing research questions, criteria, scope, and overall optimisation for systematic analyses. Her research topics branch across multiple fields, from molecular biology and evolution to collaborations in biomedical, environmental, conservation and even social sciences research. A strong advocate for open science, Losia fosters transparency in research through initiatives in open data sharing, reporting standards, and the recognition and promotion of diversity, equity, and inclusion. She is a founding member of SORTEE and currently serves on the Board of Directors.

Losia joined me on the 29th of April to discuss a [recently co-authored paper](https://doi.org/10.1016/j.tree.2024.04.007), *‘Leveraging AI to Improve Evidence Synthesis in Conservation’*, published June 2024 in Trends in Ecology & Evolution, a topic she has also written about on [her lab’s website](https://www.i-deel.org/blog/around-meta-analysis-15-emerging-large-language-models-llm-tools). In this interview, she explains how AI-enhanced research tools can be rigorously and transparently implemented in evidence synthesis, and offers helpful tips for ECRs trying out this research style for the first time.

This interview has been edited for length and clarity.

&nbsp;  

## What is Systematic Evidence Synthesis, and how did you get started in this field?

***ECR:** *For those of us who perhaps aren't as familiar with the terms: What is the difference between a systematic review, a critical review, a meta-analysis, and a meta-review? The* TREE *paper refers to ‘systematic evidence syntheses’, but what does this mean exactly?*

**ML:** The terminology is a mess. Although there are plenty of articles trying to clarify the terminology, even within the same field, the same terms are used in very different contexts with assumed different meanings. I think in every paper you just need to define what you mean by a given term in the context of your work. However, traditionally, systematic review would be a review on a very focused topic — for example, assessing a single type of intervention against a control intervention. Critical reviews are more open, more user-oriented, and tend to be less academic and statistical. They encompass different aspects and contexts of intervention using quantitative as well as qualitative methodologies, such as looking at the social acceptance, or economic value. A meta-analysis is basically the quantitative part of a systematic review, using meta-analytic statistical models (a type of weighted regression), but it has also been referred to as a separate type of review. ‘Systematic evidence synthesis’ is a broad term including all sorts of review types that use some elements of a systematic approach to collect evidence in order to reduce bias.

***ECR:** How did you first get into evidence synthesis as a research approach and topic?*

**ML:** During my postdoc there was a specific project where I was asked to collect data for a very large meta-analysis, with a broad question on the effects of dietary restriction on longevity across all species. I needed to extract concrete numbers that often weren’t included in the original paper, which meant lots of work looking through lots of additional articles. Of course, there were lots of missing data, assumptions, and heterogeneity, and I thought, “Oh, this is so messy\! Every study is so different, we will never see any pattern”. To our surprise, however, there were some clear patterns, and this made me a believer... With enough sample size and meticulous data collection, if there is a general pattern across organisms and studies, you will be able to detect it using meta-analysis. We learnt a lot from this experience and it all grew and diversified from that initial project.

&nbsp;  

## What stages of systematic evidence synthesis can AI be useful for?

***ECR:** When you begin a new systematic synthesis, at what point do you bring in the AI?*

**ML:** When we start systematic reviews, we begin by defining the scope and focused question, which we do by talking to experts. When we begin our initial scoping search, we don’t use AI. By doing broad, non-AI searches through, e.g., search engines like Google, we can see beyond the specific dataset that the AI was trained on (and limited to). This allows us to get a general look across the academic articles, grey literature, and other kinds of documents. We iteratively integrate this information as we refine our questions and methods.

AI can be quite useful for refining the search and data extraction criteria because when you write the AI prompt, you start thinking like an algorithm with a lot of clear descriptions, and this helps us create better documentation and project plans. For the actual screening, AI can be as effective as a human screener, but the problem is a lack of transparency due to AI being privately-owned, black-box algorithms. In this case, we just need to be fully transparent about how we use the AI and use it only in parallel with, not instead of, human screeners to compare and cross-check decisions. 

For data extraction, I would say it's not quite there yet, because, especially in ecological or evolutionary data, experiment designs can be very heterogeneous and complex such that even human researchers struggle to figure out those things (e.g. there could be multiple experiments presented in the same paper and an algorithm could easily mix them up). When details are poorly reported (which is typical) they can require a lot of guesswork, discussion, extra searching in the raw data, and assumptions which, from our experience, AI cannot really do yet. It would help to better incentivize the standards of reporting to make it more transparent and robust, but, in the meantime, you cannot trust AI for complex data and complex studies. For super simple cases, AI can assist data extractions, but you still need to double check everything (e.g., against a human extractor).

***ECR:** Could you explain more about double checking, particularly with human-in-the-loop (HITL) systems? How do you balance AI autonomy against the human reviewer to optimise both accuracy and speed?*

**ML:** That’s a really good question and I think everybody's working on that right now\! Historically, most of the focus has been on the screening so there are fewer papers explicitly evaluating performance of AI for data extraction, but we’re trying to get there. Basically, it will be a human doing the work, but in parallel with AI, continuously cross-checking each other because both humans and AI make mistakes. For example, AI can help you find the relevant text fragments to support data extraction. While you will still need to read those sections to make sure they are interpreted correctly, it is faster compared to reading the whole paper — but yes, don’t rely on it completely (AI may miss relevant information, especially if it is not explicit or hidden in the supplementary files).

&nbsp;  

## Red Flags in AI Systematic Synthesis Openness and Transparency

***ECR:** In the interest of transparent, open science, we need to report our use of AI in research, but how far do you go with that reporting? If you use ChatGPT as a sounding board for early ideas, or as a grammar-checker, does all of that need to be reported, or just for the big things?*

**ML:** It depends on the journal’s expectation and policy, but lots of journals don't have that policy yet. When we use AI for screening or data extraction, we would report the exact prompt and platform used, model and version number, and the dates on which everything was conducted. But at the moment, there is no expectation to do more documentation than that. In our case, we generally only use AI (like Grammarly) to edit our drafts, which is only refining the text, not generative use, which often is not required to be reported.

***ECR:** Are there any red flags that stand out in terms of reporting, transparency, and openness when you’re reviewing other researchers’ — particularly early career researchers’ — work?*

**ML:** Yes, when they don’t provide their raw data\! I want not only the summary calculations, but also the raw values and metadata with detailed descriptions of every variable and assumption. Especially for evidence synthesis, if you extract numbers from primary research, you should to provide information about where it comes from in the original paper including recording the table or figure number with enough information so you can find that exact actual data and crosscheck it as needed (as well as helping you to cross-check it yourself, especially if you are getting some crazy values in your analyses). Sometimes, when I’m reviewing, a number will be in the extracted summary data but not in the original paper. I don’t know what they did to that number. Did they calculate a total? Divide it? Multiply it? Why is this number like that? Where is it from?

If the authors record their sources, assumptions, and data transformations,it gives me confidence that they were tidy and rigorous. But if that’s missing, it can seem dodgy, as if they’re hiding how they got their numbers and preventing replication.

&nbsp;  

## ECRs and AI in Systematic Evidence Synthesis

***ECR:** The paper talks about how AI is here to stay and how it’s not a question of whether to use it, but* how*. To what extent does this perspective apply to ECRs, particularly PhD students who are still building and developing core research skills? Are there some skills that are best learnt by doing things manually?*

**ML:** We cannot escape AI now so the most important thing is critical thinking and learning to use AI without compromising the quality of our research. To do that, you often do actually need to have expert knowledge of a topic though. You need a sense of when the AI results look suspicious or too superficial and, in order to spot that, you do need to know what’s missing — which you cannot do without actually reading the articles by yourself, conducting hands-on research, and making the mistakes you learn from. If you haven’t done hands-on work in multiple areas, it can be really hard for you to spot what is missing or when AI has misinterpreted something.

***ECR:** For researchers just starting out, who don’t have that expert knowledge yet, what would your advice be?*

**ML:** For systematic evidence synthesis, you need to frame your question appropriately. You can make your question really broad, thinking, “Oh, that's going to go into *Nature*”, but it might actually be just too big for you (at least at this early stage). For systematic literature searches, you can always easily find thousands of records that match your keywords (especially if they are broad) but it's better to make your search sensitive (get the right stuff) and doable (not take 5 years to screen and extract data, even with AI’s help). So, when you’re starting out, you should aim for the smallest possible valuable review. For example, learn the methods and the literature by doing a systematic map (that is, a synthesis on “what has been researched” instead of “what has been found”), and, after you’ve figured out what’s missing in the existing syntheses, and what has just enough evidence, *then* you can take that next step to use a meta-analysis or other approach to fill the knowledge gap.

Remember, AI is just there to help with efficiency. You still need to think for yourself, and that's your most important skill. Always honestly ask yourself (and/or your mentors): what's important, why are we doing this, how are we doing it, how can we make it reliable and transparent? That’s the core of good science, and AI can help, but never replace that.
