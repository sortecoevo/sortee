---
title: 'SORTEE Code Club: Introduction to data simulation and power analysis'
author: "Cecilia Baldoni & Corné de Groot"
date: "2025-11-28"
summary: "The authors debriefs about the latest SORTEE Code Club, all about data simulation and power analysis!"
categories:
- blog
tags:
- code club
- code
banner: img/2025_Code_club.png
---
&nbsp;

**SORTEE Code Club debrief: Introduction to data simulation and power analysis - November, 18th 2025**

Author: Cecilia Baldoni & Corné de Groot 
  

The Member Engagement Committee runs **Code Club every third Tuesday of the month**. Time can vary depending on the host and will be announced at least two weeks in advance on [SORTEE's Slack](https://sortee.org/join). For more information, see [SORTEE's Code Club page](https://www.sortee.org/code_club/).

On Tuesday, November 18th, we hosted a beginner-friendly `Training Session` on data simulation and power analyses in R. Data simulation is a powerful technique for understanding how study designs influence the reliability of effect size estimates, and for planning studies with appropriate statistical power. By simulating data before conducting a real study, researchers can gain confidence in their statistical approaches and make more transparent decisions about study design and sample sizes.

We walked through the workflow of building a simulation from the ground up: defining a realistic data structure, setting parameter values for both fixed and random effects, and then generating simulated datasets based on those parameters. The key insight is that to simulate data, you need to explicitly define the underlying biological and statistical structure of your study.

To conduct a power analysis, we converted the simulation into a function and repeatedly generated 100 simulated datasets. We then fit statistical models to each dataset and examined how often effects were detected—this gives you an estimate of statistical power for your study design. This approach lets you ask critical questions before data collection: "Given my study design and expected effect sizes, how likely am I to detect a true effect?"

During this session, we explored two complementary approaches. First, we used the frequentist framework with `lmerTest`, which relies on p-values to assess whether effects are statistically significant. This is the traditional approach most researchers are familiar with. Second, we demonstrated a Bayesian approach using `brms` and `Stan`, which estimates posterior distributions for parameters instead of p-values. In the Bayesian framework, you assess whether the 95% credible interval excludes zero to determine if effects are reliably estimated. The key difference: frequentist power asks "how often will I detect an effect if it's real?", while Bayesian methods provide direct estimates of parameter uncertainty and precision. For complex hierarchical models, the Bayesian approach can offer valuable insights that complement traditional power analyses.

Data simulation makes your statistical assumptions explicit and transparent, improving the reproducibility and rigor of your research!

All code and materials from the session are available on [GitHub](https://github.com/SORTEE/CodeClub/tree/main/20251118_DataSim_Power): check out the supporting materials and scripts to follow along and adapt the code for your own research questions.

**What's next?**

The SORTEE Code Club will come back **on Tuesday, December 16th** (the zoom link will be posted on [SORTEE's Slack](https://sortee.org/join/)). 

  

You can check [the Code Club schedule here](https://docs.google.com/spreadsheets/d/1rOOOE7ghPduwtFftG0DJJf0DXVigAdcmQ0xdEwbKQXo/edit?usp=sharing) for upcoming meetings. To receive calendar invites in your local time zone, [sign up here](https://forms.gle/yKrEm6xAKZtom5kt7).

  

**Suggest a topic**

To propose a Code Club meeting topic, please use [this form](https://forms.gle/eZy81dUymiZNJetu8).
