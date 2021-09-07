---
banner: img/banners/ecoevotransparency.jpg
date: "2017-12-12"
author: Shinichi Nakagawa
categories:
- blog
tags:
- Open Science
- reproducibility
title: Why ‘MORE’ published research findings are false

---

*[This post has been originally posted on [ecoevotransparency.org](http://www.ecoevotransparency.org/)]*    


In a classic [article]( https://doi.org/10.1371/journal.pmed.0020124
) titled “Why most published research findings are false”,  John Ioannidis explains 5 main reasons for just that. These reasons are largely related to large ‘false positive reporting probabilities’ (FPRP) in most studies, and ‘researcher degrees of freedom’, facilitating the practice as such ‘p-hacking’. If you aren’t familiar with these terms (FPRP, researcher degrees of freedom, and p-hacking), please read Tim Parker and his colleagues’ [paper]( https://doi.org/10.1371/journal.pmed.0020124).    

I would like to add one more important reason why research findings are often wrong (thus, the title of this blog). Many researchers simply get their stats wrong. This point has been talked about less in the current discussion of the ‘reproducibility crisis’. There are many ways to getting stats wrong, but I will discuss a few examples here.   

In our lab’s recent [article](https://bmcbiol.biomedcentral.com/articles/10.1186/s12915-017-0448-5), we explore one way that biologists, especially when statistically accounting for body size, can produce unreliable results. Problems arise when a researcher divides a non-size trait measurement by size (e.g., food intake by weight), and uses this derived variable in a statistical model (a worryingly common practice!).Traits are usually allometrically related to each other, meaning, for example, food intake will not increase linearly with weight. In fact, food intake increases slower than weight. The consequence of using the derived variable is that we may find statistically significant results where no actual effect exists ([see Fig 1](https://bmcbiol.biomedcentral.com/articles/10.1186/s12915-017-0448-5)). An easy solution for this issue is to log-transform and fit the trait of interest as a response with size as a predictor (i.e., allometrically related traits are log-linear to each other).   

But surprisingly, even this solution can lead to wrong conclusions. We discussed a situation where an experimental treatment affects both a trait of interest (food intake) and size (weight). In such a situation, size is known as an [intermediate outcome](https://statmodeling.stat.columbia.edu/2006/04/28/amusing_example/), and fitting size as a predictor could result in wrongly estimating an experimental effect. I have made similar mistakes because it’s difficult to know when and how to control for size. It depends on both your question and the nature of relationships between the trait of interest and size. For example, if the experiment affected both body size and appetite and also body size influences appetite as well, then, you do not want to control for body size. This is because the effect of body size on appetite is due to the experimental effect (complicated!).   

Although I said, ‘getting stats wrong’ is less talked about, there are exceptions. For instance, the pitfalls of pseudoreplication (statistical non-independence) have been known for many years, but researchers continue to overlook this problem. Recently my good friend Wolfgang Forstmeier and his colleagues devoted part of a paper on avoiding false positives (Type I error) to explaining the importance of accounting for pseudo-replication in statistical models. If you work in a probabilistic discipline, this article is a must read! As you will find out, not all pseudoreplication is obvious. Modelling pseudoreplication properly can reduce Type I dramatically (BTW, we recently wrote about [statistical non-independence and the importance of sensitivity analysis](https://onlinelibrary.wiley.com/doi/full/10.1111/mec.14031)).   

What can we do to prevent these stats mistakes? Doing stats right is more difficult than I used to think. When I was a PhD student, I thought I was good at statistical modelling, but I made many statistical mistakes including ones mentioned above. Statistical modelling is difficult because we need to understand both statistics and biological properties of a system under investigation. A statistician can help with the former but not the latter. If statisticians can’t recognize all our potential mistakes, I think this means that we as biologists should become better statisticians.   

Luckily, we have some amazing resource. I would recommend all graduate students read Gelman and Hill’s [book](http://www.stat.columbia.edu/~gelman/arm/). Also, you will learn a lot from Andrew Gelman’s [blog](https://statmodeling.stat.columbia.edu/) where he often talks about common statistical mistakes and scientific reproducibility. Although no match to Gelman and Hill, I am doing y part to educate biology students about stats by writing a new kind of stats book, which is based on conversations, i.e. a play (an excerpt [here](http://www.i-deel.org/blog/r-statistical-modeling-via-biologists-dialogues))!   

I would like to thank Tim Parker for detailed comments on an earlier version of this blog.   

&nbsp;
&nbsp;

[*The opinions expressed in this blog post are those of the authors and are not necessarily endorsed by SORTEE."]  