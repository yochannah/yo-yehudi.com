---
layout: post
title:  "Codes of Conduct reporting avenues and bottlenecks"
date:   2021-08-02 21:42:43 +0100
categories: science open-source community code-of-conduct
---

As part of my research, I'm tracking OSS community sustainability elements. Some of this is done automatically using GitHub APIs. Yes, OSS comes in many flavours, but GitHub is particularly popular so the easiest to script for. 

Some of the stuff I'm looking at isn't easily scripted either. I can check for CODE_OF_CONDUCT.md, but checking for the existence of enforcement contacts is best done manually, given that codes of conduct can have varied language. 

Over the weekend I went through about 40 repos, noting down if they had enforcement info, and noted a few common patterns. [I originally tweeted a thread about this](https://twitter.com/yoyehudi/status/1421874261522894848), but at Michelle Barker's suggestion decided to commit this to a less ephemeral format. 

## The six types of Code of Conduct enforecement

1. No Code of Conduct. 
2. Has CoC, but enforcement info (who to contact / what to do if someone isn't behaving in line with the code of conduct) is broken/missing. Well intended but problematic if anyone wants to raise an issue.
3. General email address for issues: 
    a. 📧🍼 Has CoC, some general enforcement contact that's nonspecific, i.e. conduct@somesite.org. This is better than nothing, but - who does the reporting go to?
    b. 📧🍼 Has CoC, and the general email recipients are listed.  conduct@somesite.org, reaches Joy and Sam only.
4. 📧🍼  Has CoC, goes to single named person, e.g. please email sam@somesite.org.
5. Backup contact:
    a. 📧 Has CoC, with multiple contacts, including a backup in case one of the contacts themselves is the problem. 
    b.  📧 Has CoC, multiple contacts. Backup is unaffiliated with the project.
6. 📝 Has CoC, has reporting form that doesn't require an individual to send an email. 

## Thoughts on the different types

- **Anonymous options are good** 📝 Option (6) can be combined with any of the above that I've annotated with an email emoji - but almost every enforcement avenue in the repos I surveyed seemed to default to email. Anonymous reporting forms can be harder to respond to if there's no way to contact the reporter, but may provide a layer of safety that allows some people to come forwards when they otherwise might not. Creating a pseudonym email is an option, but it's still a barrier many might not bother with. 
- 🍼🍼🍼 **Don't let a single person be a bottleneck** - If the person who needs to be reported is the sole contact, is on the committee, or _might_ be behind a general reporting email address, and there's no backup reporting address like in option 5, you could have an unfixable problem. I've annotated places where this could be a risk with the bottle emoji.
- Following on from the previous point: **Always name all CoC committee participants** - this is specific feedback on option 3. Mystery committee doesn't equal safety.
- **Backup / ombudspeople are great** - someone you trust enough to act impartially who is generally unaffiliated with the project is best, but even two different individual contacts is better than one single contact. 

## Best of all worlds?

Combining the strengths of all of these, the strongest option I can see is: 

- Two or more _named_ email reporting contacts, one of whom is  unaffiliated with the project. 
- An anonymous reporting form that leaves contact details optional.

## Other? 

I'm also curious what other patterns people have seen that don't fit into some combination of the above options - what strengths or weaknesses might they have? Comments welcome on the original [tweet thread](https://twitter.com/yoyehudi/status/1421874261522894848)
