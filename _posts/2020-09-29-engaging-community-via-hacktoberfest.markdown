---
layout: post
date: 2020-09-29 12:36:04 +0100
tags: open-source hacktoberfest community
title: Engaging community via Hacktoberfest
---

[Hacktoberfest](https://hacktoberfest.digitalocean.com/) is a month-long drive to get more people contributing to open source, with a single premise: Once you're [registered](https://hacktoberfest.digitalocean.com/login) (you'll need to make a GitHub account if you haven't already) for Hacktoberfest you need to make four [pull requests](http://oss-watch.ac.uk/resources/pullrequest) to open source projects on [GitHub](http://oss-watch.ac.uk/resources/pullrequest), and you'll get a free tshirt (or, new for 2020 - plant a tree instead).

Your average geek loves "free" stuff, and probably loves geek-branded stuff even more, so this works surprisingly well in pulling in contributors to open source projects. If we look under the skin beyond "free stuff", there's incredible value in this initiative, whether you're a project maintainer, an experienced coder, or a complete newbie - it's even entirely possible to contribute without writing a single line of code.

## Making contributions to projects

If you're in or near the tech world, I'd highly recommend having a go at this, even if you aren't too fussed about a cool geeky shirt. There are a few reasons beyond the shirt that participating is useful:

- learn about open source norms. There are a lot of terms thrown about, like pull request, commit, repo, fork, branch - sometimes the best way to learn is by diving in, and many of the ways of working collaboratively on GitHub may be of benefit even in your private projects - there's a whole field called "inner source" for companies that use open source work methods internally within their organisation.
- experience - if you're new to coding, or if you've only coded for organisations that keep their code private, having a few publicly recorded code contributions can do wonders for future job applications.
- altruism. Give a little and feel good about it 💪 - perhaps consider picking a project that inspires you, like an astronomy project, a project encouraging diversity in tech, a project that helps scientists work with cancer data, or just a project that you use in your daily life.

## Soliciting contributions

If you're a github repo maintainer and you're interested in soliciting contributions, congratulations: you're in it for the long game in a way that might require a gentle mind shift. At the face of it, you're getting contributions to your project, but despite the fact that no money is being exchanged, it's not labour for free. Think critically about the value exchange that is coming up: people are contributing code, and you're offering guidance and specific tasks to work on.

To get going, create some issues in your repo - these could be new code features, requests to review docs, to set up or update CI, add or create tests, create a logo, or fix a straightforward bug. Please don't ask people to do the awful, weeks-long hairy bugs - you want the exchange to be fun and worthwhile for everyone, not just worthwhile for you. Label each task with the label "hacktoberfest", and people will come. Some tips to create tasks:

1. Make sure your tasks are well-defined and bite-sized. If your task is vague, or if it's going to take a week to do - people probably won't want to do it. 1-2 hours of work is the largest "chunk" size I'd recommend for each ticket you create.
2. The subject line for each task is the first thing people will see, so make it compelling. Some possible subject lines:
  - [easier if you know javascript] add event handler for touch events, not just mouse clicks
  - [design task] create logo for biology machine learning project
  - [documentation - no coding required] translate getting started docs to a language of your choice
3. Make sure you tell people what to do when they're stuck or need help - link to your community chat, tell them who to @mention on github, or provide a twitter or email. This helps increase engagement and their ability to finish the task if they have questions.
4. If you know what line of code or folder people should be looking in, link to it!
5. Link small chunked tasks - so if you have someone looking at the logo design task, point them also to any other design tasks at the same time. Here's an example issue on the [Open Bioinformatics Foundation](https://github.com/OBF/obf-docs/issues/82) docs repo where the contributor picked up both issues.
6. Link to your getting started docs - how to install and run the project - so people don't have to go hunting.

I could probably add more, but at this point, you may be thinking "goodness, this is a lot of work!" and you wouldn't be wrong. Often, preparing tasks - especially if you're preparing them for complete beginners - can take longer than fixing it yourself. So why do it at all? Here are a few reasons:

1. You may be gaining a longer term contributor. You learn about their behaviours, code style, interpersonal skills - and when vacancies come up, you can encourage them to apply, safe in the knowledge you already know working with them is good.
2. Getting more eyeballs over your code is usually a good thing! Perhaps your setup guide is missing a step, or perhaps you have no guide for windows coders, only for mac and linux. You'll spend time helping the contributors figure it out, but end up with something better in the end - and you might be lucky enough they'll fix the missing docs on the way. [InterMine gained an incredible Windows "getting started" guide](https://github.com/intermine/InterMine-Data-Browser-Tool/pull/78) from a new open source contributor who worked out how to set things up on her system.
3. Bring in skills and perspectives you might not have on the team. Sometimes it's not practical to hire for small tasks, but you'd still like a professional to do it. [Open Life Science](https://github.com/open-life-science/open-life-science.github.io/issues/1) had a logo created via Hacktoberfest contributions, and [Code Is Science](https://github.com/codeisscience/code-is-science/issues/12) gained both a gorgeous design implementations and then a front end design/tech lead via Hacktoberfest contributions. People also come from all around the world, giving different cultural expectations and technical conditions - having a contributor from a low bandwidth area might make you re-think your page load times or help you design an offline-ready application.

My final tip - if you can (I know this isn't always possible), spend a small chunk of cash and print a bunch of stickers. Tell all contributors who complete a PR to email you their snail mail address if they'd like one, and include a little hand written note. Your contributors will always remember you if you show thanks, and more inclined to come back again. Repeating my intro from the start of this section - Hacktoberfest is the long game, where you create opportunities and value exchange for _both_ sides.
