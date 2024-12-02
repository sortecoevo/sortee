---
banner: /blog/images/2024_Figure_1.png
date: "2024-11-23"
author: Graziella V. DiRenzo, Ephraim M. Hanks & David A. W. Miller
summary: The authors provide a step-by-step guide to make sense of complex models using data simulations and discuss their recent paper.
categories:
- blog
tags: 
- simulation
- models
- validation
title: "A step-by-step guide to making sense of complex models using data simulations" 
---
&nbsp;

Simulation studies are well-known and used often throughout scientific literature, but what is meant by the term “simulation study” is very context specific. For example, simulations can range from simple population models to complex individual-based models (IBMs) or agent-based models (ABMs), and simulations can be used to explore the statistical properties of models, to validate and compare computational methods, to understand possible future scenarios, and the list goes on and on. In May 2020, Ephraim Hanks, David Miller, and I realized that there was no easy resource available to biologists that provided a taxonomy of simulation studies. We also realized that the increasing use of hierarchical modeling by biologists makes simulations an important tool for assessing how sound a given hierarchical model and the associated computing approach are.  

We noticed that it is common during peer-review of a manuscript featuring a novel hierarchical model for reviewers to request that the authors conduct a simulation study. Reasons reviewers may ask for simulations are to assess the identifiability of model parameters, to evaluate the coverage and accuracy of confidence intervals, to test the model's ability to recover true underlying parameters from synthetic data, or to compare the performance of the novel model to existing approaches. However, it was often not perfectly clear what the reviewers mean by “simulation study”, given the diversity of purposes simulations serve.  

One challenge we face in biological science is that we often don’t know the “true” values of the variables we’re measuring, such as the number of animals in a population or the amount of rainfall a forest needs to thrive. So, to test our models, we use simulations—essentially creating a virtual world where we know all the answers. By comparing the model’s estimates with the known values used to simulate the data, we can see how well the model is performing and where it might need improvement.

In our recent paper (DiRenzo et al. 2023, Methods in Ecology & Evolution [https://doi.org/10.1111/2041-210X.14030](https://doi.org/10.1111/2041-210X.14030)), we laid out a taxonomy of the various analyses that can be called “simulation studies”. We then suggest a simple framework for how simulation studies can be used for model validation in biological research using hierarchical models. Validation, in simple terms, means asking: "Can we trust the results this model gives us?" This involves everything from making sure the code that runs the model is free from bugs to checking if the model can still provide good estimates when we don’t know everything about the system we’re studying or when new data come in.

&nbsp;

![Graphical illustration of steps for each type of simulation study (6 total)](/blog/images/2024_Figure_1.png)

Figure 1. Graphical illustration of steps for each type of simulation study (6 total). Blue boxes are data-related steps, peach boxes are model-fitting steps, and green boxes are comparison steps. 

&nbsp;

Our paper offers a guide for biologists on how to use simulations effectively (Figure 1). We divide simulation studies into two main types:
1.	**Study-specific simulations:** These are focused on one particular analysis or dataset. For example, if you’re studying a specific forest, you would simulate data based on what you know about that forest and test if your model can accurately predict what’s happening there.  Some study-specific simulation studies include:
- **Basic validation simulation example:** This checks if the model and the code are working correctly to give realistic estimates.
- **Statistical properties simulation study:** Here, one looks deeper into the model and estimation approach to understand how accurate and precise parameter estimates and predictions are, and whether the proposed approach might result in biased estimates.
- **Goodness-of-fit simulation study:** This determines how well the model and estimation approach can replicate important patterns in the data you’ve observed in the real world.
2.	**General property simulations:** These are broader and focus on understanding the statistical properties of proposed methods (like estimation approaches) themselves, which can be applied to different studies in the future.
- **Simulation-based study design:** This helps us see how the model and estimation approach might perform under different conditions, like changing sample sizes or varying parameters.
- **Assessing robustness:** We test how well the model and estimation approach hold up when it is not perfectly matched to the data generating mechanism, which often happens in real-world scenarios.
- **Comparing methods:** This is often used to see if the new approach you’re proposing is better, worse, or similar to existing methods.

We provide practical guidelines in our paper for which simulation studies are best suited for answering different types of questions. We recommend that at a minimum, researchers should include a basic validation simulation whenever they’re using new models. To help others follow these steps, we’ve included a running example throughout our paper, complete with code that anyone can use, to illustrate each of the six types of simulations (Figure 1). In essence, this paper is like a user manual for testing and fine-tuning the complex “machines” we build in biological research, helping ensure they’re reliable before they hit the road.


\
\
\
**Author Bios:**

Graziella (Grace) DiRenzo:
-	Dr. DiRenzo is an Assistant Unit Leader of Wildlife at the U. S. Geological Survey, Massachusetts Cooperative Fish & Wildlife Research Unit and adjunct faculty in the department of Environmental Conservation at the University of Massachusetts, Amherst. Dr. DiRenzo received her PhD at the University of Maryland, College Park. Her research centers around disease dynamics, community and population ecology, species conservation, decision analysis, and structured decision making. She works closely with practitioners to advance actionable ecological knowledge and wildlife conservation solutions using quantitative tools and decision science.
-	You can learn more about Grace at her website: www.grazielladirenzo.weebly.com

Ephraim Hanks
-	Dr. Hanks is an Associate Professor in Statistics at Penn State University.  He received his PhD from Colorado State University.  His research involves developing novel statistical methods for problems in Ecology and Epidemiology, with an emphasis on animal movement, spatial, and spatio-temporal data.
-	You can learn more about Ephraim at his website: https://sites.psu.edu/hanks/  

David Miller
-	Dr. Miller is a Professor of Wildlife Population Ecology in the Department of Ecosystem Science and Management at Penn State University. His research focuses on the application of hierarchical statistical approaches to estimate parameters and dynamics of ecological systems using empirical data. Recent work includes developing data integration methods for species distribution models, estimating host-pathogen dynamics for latent disease state data, and quantifying patterns of life history evolution and aging in amphibians and reptiles. 
-	You can learn more about David at his website: http://www.appliedpopeco.com/

*Any use of trade, firm, or product names is for descriptive purposes only and does not imply endorsement by the U.S. Government.*

&nbsp;

**Social Links:** 

[@usgs](https://x.com/USGS)\
[@Direnzola](https://x.com/DiRenzoLab)\
[@USGSCOOPUNITS](https://x.com/USGSCoopUnits)\
[@aveamphibious](https://x.com/aveamphibious)\
[David Miller's website](http://www.appliedpopeco.com/)\
[Graziella DiRenzo's website](https://grazielladirenzo.weebly.com/)\
[USGS MA CRU website](https://www1.usgs.gov/coopunits/unit/Massachusetts)
