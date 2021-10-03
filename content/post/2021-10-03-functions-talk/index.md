---
title: Functions Talk
author: 'Jeff Newmiller'
date: '2021-10-03'
slug: functions-talk
categories:
  - R
tags:
  - data analysis
  - beginners
  - functions
summary: 'I gave an introductory talk on making R functions'
lastmod: '2021-10-03T14:16:40-07:00'
featured: no
---

The [East Bay R Enthusiasts](https://www.meetup.com/r-enthusiasts/) is trying to rebound from the pandemic (after pausing for 18 months) by setting up some meetings online, and I put together some thoughts on the questions "how do I make a function" and "what should be in a function", targeted at beginner-to-intermediate R users in a [presentation](https://jdnewmil.github.io/FunctionsTalk/FunctionsTalk.html). The presentation seemed to go alright for the few that attended... hopefully attendance will increase after we get into a rhythm again.

Many beginners in R focus on using functions that are provided in the base R distribution and/or in contributed packages, but they often find themselves copying and pasting snippets into long scripts that are very repetitive with tiny differences between chunks of code. Wrapping those snippets into functions reduces the repetition and lets the user think in terms of what each block was intended to accomplish. A script composed of a few dozen clearly-named function calls that each accomplish a page-worth of statements is easier to read and think about and extend than a script with hundreds of lines.

To this end, the presentation discusses the mechanics of converting a few blocks of code into functions, and ends up discussing input, output, and analysis as distinctly different categories of functions to keep in mind as one converts script code into functions. It ends with comparing a data flow diagram of a sample analysis and two versions of R code that correspond to that diagram.

There are many other things that can be said about functions, and in a future extension of this discussion I intend to discuss function mapping and "apply"-type functions as tools for organizing repeated operations, as well as some trade-offs between performance and memory use.
