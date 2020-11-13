---
layout: post
date: 2020-11-13 13:50:34 +0000
tags: open-source good-docs software-documentation
title: "Open code, no docs: cooking without a recipe - and good enough vs perfect"
---

![picture of several rows of sushi laid out on a wooden slab, including sushi rolls and other shapes.](/images/bladimir-garcia-sushi-unsplash.jpg)

Cooking is a learned skill, but we have a shortcut trick to help people cook dishes they've never cooked before: the recipe.

Example: If you gave me a box with pasta, tomatoes, garlic, and herbs, I'd probably be comfortable making spaghetti with a tomato sauce, since this is food I've cooked many times. If I was given a box full of less familiar ingredients - let's say sushi rice, seaweed sheets, and other supplies- I might struggle to make beautiful sushi rolls or neat little blocks of rice topped by fish or egg, even if I had pictures of the completed foods to look at.

Give me a detailed recipe and the right tools, however, it would get a lot easier: even though I'd never made it before, I would know what steps to take, what prerequisites there might be (for example, a bamboo mat, and some vinegar that didn't come with the sushi kit) and in which order. There might even be tips for how to deal with tricky bits I'd never tried before, like getting the rice to stick together or using the bamboo mat to make rolls.

Software and code is much the same. Given an unfamiliar code snippet with no docs, if I have domain familiarity I might be able to get it running. I might load up an .Rmd file in RStudio and press the "knit" button even if no-one has written instructions to do so, and I'd use `install.packages` to install missing dependencies if needed. While I'm by no means a strong R coder, I've used R before enough to know that this might work. If, however, you gave me a FORTRAN program, I'd have no idea where to get started on my own. This is where the "recipe" for the code might help - if there was a Readme file, I might learn what environments or dependencies I'd need to install, and what commands to run to actually compile and execute the software, what data I might need if any, and how to run tests. (Aside: Whilst I have actually made sushi in the past, I know almost nothing about FORTRAN - I even had to do a quick web search to double-check that FORTRAN is indeed a compiled language.)

## Spirit vs rule of the law
Many journals encourage or even require data and/or code availability when research software is published.  Whilst the availability of code in research papers has certainly gotten better over the last few years, code doesn't always come with good recipes (running docs) to run it, a result of complying with minimum measures that aren't checked, enforced, or understood. I don't think this is malicious or lazy, in most cases - it's probably just that people aren't aware of what's needed or didn't think to check and test the docs when reviewing.

To fix this, we need a culture change from many angles.

When we're **reviewing papers that concern code and software, we need to actually check it runs**. For a 20-line script that analyses or formats some results or creates a graph, it's probably going to be pretty quick to check, although it also seems possible that it's not critical to the scientific results if the script is that small. For longer scripts and software suites, it may take more time. If we want published software to be more than a pretty anecdote, it seems worth the time taken to do so, especially if we think this is software that could or should be re-used by others. If the docs aren't there or the reviewers are unable to run the software, the paper and its associated software will only be improved if we add in a recipe for how the code is run.

When **policy** is being created, ensure there is sufficient nuance for the policy to be useful - "open source code with running docs" is going to be more useful than merely "open code". (For now let's not get into the rabbit hole of how we articulate whether the running docs are sufficient).

Importantly, though, **we can't let perfect be the enemy of the good**. Whilst we certainly want necessary nuance in policy guidance, we don't want to spend so much time worrying about the nuances of good practice that we make it hard to achieve; we need to be practical about what a useful minimum is, and provide next steps and best practice guidelines for those who do wish to learn more. Cries of "that's not truly open" and "you must be 100% reproducible" [can serve to scare people away from the good-intent baby steps they planned to take](https://lgatto.github.io/open-and-open/). We need to ensure that while we think of these culture changes towards open, reproducible and re-usable work, we also ensure it becomes more inclusive.  
