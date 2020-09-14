---
layout: post
date: 2020-09-14 11:06:04 +0100
tags: science open-source reproducibility replicability code-quality
title: Why do we need open code in research?
---

For a long time, reproducibility and replicability - that is, the ability to re-run analyses and re-use research code - has been a passion of mine. Since I started working at the Wellcome Trust, though, it's also become a part of my job, and one I need to think about strategically. The goal is reasonably straightforward: **when research has a computational aspect, how do we ensure that it is robust enough that others can examine the methods (i.e. the code<sup>*</sup>) and at the very least re-run them, or ideally also re-use them for future analyses on different data?**

## Some of the "why" of open code:

1. It's easy to make mistakes. **We're human**. If we can't see the code, we can't see if somewhere in the magic sauce we made an oopsie, e.g. making `2 + 2 = 5`, or perhaps more likely, a decimal point error or an off-by-one error. The bigger the codebase, the harder it is to spot an error and the less likely it'll be thoroughly reviewed - but at least with open methods, we can spot and correct mistakes if they do happen.
2. We should be **building on each others' shoulders to advance knowledge**, rather than repeating the same work over and over, and rather than competing. If your work was useful, interesting, and re-usable - it should be re-used! Otherwise it's little more than a nice story. It seems a shame to create nice stories when we could create nice stories _and_ useful re-usable tools.

<sup>*</sup> or the excel spreadsheet, or whatever tool you used. Non-code computational analyses are important, and if the method works, we shouldn't consider it somehow lesser.

Next in this series, I'll write a little for the "what" of open code.
