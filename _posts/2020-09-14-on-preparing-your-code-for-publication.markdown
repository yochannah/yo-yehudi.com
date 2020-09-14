---
layout: post
date: 2020-09-14 111:06:04 +0100
categories: science open-source reproducibility replicability code-quality
title: On preparing code for publication
---

Previously, I wrote a little about why open code is important in research. I'm in the process of reviewing R code for a publication that is nearly ready to go live, and adding a few thoughts here on what useful steps a novice coder can take to make their code re-runnable and possibly even re-usable.  

## Getting started

We'll assume at this point you have:

- some code that you used to produce your results. (This might be R, python, Matlab, or some other tool that works for you).
- a set of results that you hope are reproducible.

## Ask someone else to look at it

Once you're at this stage, my next tip: find a friend or colleague who can write code at least as well as you. Ask them to try producing the same results you have already produced. If you don't know someone who could do this, check if your institute has a research software engineering team - they may be able to provide a short consultation without too much fuss.

### Sharing my code is scary - what if it's not good enough?

Programmer secret tip: Bug reports are awesome and make your work better in the end. Much like it's helpful to get someone else to proof read a document to spot errors and discontinuities, getting someone else to review your code will only make it better. The person reviewing your code will ask questions about how to run it, how to fix weird errors, what tools are required to make this work - and as you fix the documentation and tooling, it'll make a better product.

## Useful tools to get the code review going

1. Share the code and results with your friendly code-reviewer, as well as any underlying data needed to make it run. Some solutions to possible difficult points:
  - Private data: Create a few lines of fake data that is shaped like the real data, if you can't share the real data for ethical reasons, or if sharing it would require long and complicated background checks or approval processes.
  - keeping track of code changes is complicated: Try putting your code on [GitHub](https://github.com/), under a private repository if needed. Add your friend's github user to the private repo so they can access it. If you've never used Git before, programs like [GitHub Desktop](https://desktop.github.com/) (Windows, Mac) or [GitKraken](https://www.gitkraken.com/download) (Mac, Linux, Windows) can make it smooth, and don't require you to learn the command line.
2. Try to include some running instructions. A text file with steps to get going would be great - it might be something as short as "install R and RStudio, install libraries x, y, z, and then open up MyAnalysis.Rmd in RStudio and run the knit command". Any steps that you've missed off, your code-reviewing friend will probably come back and ask you about.  
3. Now it's up to your code-reviewing friend. Ask them to make note of places they struggled or got stuck.
  - If they resolved it on their own, they should still either fix the code / running instructions, or ask you to do so.
  - If you're using GitHub, they could open an [issue on GitHub](https://guides.github.com/features/issues/) as a way to record the difficulty. Step through each issue and fix it or document how to deal with it.
  - If you find that they can't replicate your results with your original data, try to figure out why, and whether the old results or the new ones are correct. You might need to bring in a third person here to see what results they end up with!

At some point, you and your friend will have worked out all the kinks in the process. Congratulations! If there's no reason to keep the code private, it's time to [add a licence to your repository](https://choosealicense.com/) if you haven't already. If you're not sure, consider adding a permissive licence such as MIT, which allows you to use the code privately if needed but also allows open re-use and sharing. It's important to add _some_ licence - if you don't add any, the code might be online but [it's illegal to re-use at all](https://choosealicense.com/no-permission/) 😭. 
