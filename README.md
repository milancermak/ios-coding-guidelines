## About
As the repo description mentions, this is an /opinionated/ guide on writting better iOS code.

During my career as an iOS developer, I have been working on a bunch of apps with varying code quality - some were brilliant, some terrible. There were apps I wrote from scratch, others I've taken over after other developers. I worked on projects both as a single developer but also in teams. Throughout this time I've made notes of what worked and what didn't.

I'm deeply interested in best practices of creating software, plus I want to share what I've learnt (from mistakes of others as well as my own) with the rest of the community so anyone can improve their code, because trust me, working on a codebase that is loaded with crap is painful, demotivating and unproductive.

A lot of the tips presented in this guide might seem really basic or they might not be iOS specific at all. I've included them nevertheless because I saw these elemental rules of software engineering broken one by one, multiple times.

## High-level focus
Everything in this guide to these principles I follow with my code:
 * *Consistency*
 * *Correctness*
 * *Collaboration*

*Consistency* is, by far, the most important of them all. Consistency means following the same rules for naming, structure and organization of your code and project. The brain is a pattern matching and recognition machines; it instantly makes assumptions about another part of the code based on the bit and pieces you saw elsewhere. This will help you make a hotfix of an unfamiliar codebase just a couple of mintues before an important demo of the app to a VC (yup, this actually happened to me). Even if you write bad code, it's better if it's consistently bad. Consistent code is far easier to comprehend, navigate and manipulate.

The second principle I strive for is *Correctness*. Objective-C is a neat language allowing for a lot of magic, both good and bad. Likewise, the iOS SDK is a wonderfull piece of software offering a lot of possibilites. To a newcommer, this might get overwhelming, because, similarly as in Perl, (there's more than one way to do it)[http://en.wikipedia.org/wiki/There%27s_more_than_one_way_to_do_it]. One might be tempted to cut corners now and then (and put EVERYTHING to AppDelegate); this will work, but it is not the correct way to do it. Borrowing from the Zen of Python, (there should be one - and preferably only one - obvious way to do it)[http://www.python.org/dev/peps/pep-0020/]. This holds true for Objective-C alike.

Finally, when I write code, I also optimize for *Collaboration*. By that I mean code that's easy to modify, not just by other folks but also by the future me, who, honestly, is as an different person. Between now and then I'll work on another projects and forget all about this one so when a client asks to do "a simple modification to the app", it's a piece of cake. The advantages of this principle are really self-evident. Your colleagues will respect your skills and trust you. Your whole team will be more productive, hence you'll achieve you goal sooner, please your clients/boss, etc. Hell, you might even get more pull-requests. The cherry-on-top is that collaboration-friendly code is a logical implication of the previous two rules. If you write consistent and correct code, you get it out of the box.

I tend to follow these rules not just for all the programming I do, not just iOS apps. It makes life easier and more enjoyable.

## TODO
This guide is a work in progress. Here's a summary (in no particular order) of topics I want to add:
 * Writing modern, clean and correct Objective-C
 * Naming
 * Xcode project template
 * API design
 * Code formatting and code organization
 * Common mistakes
 * Best practices
 * Advanced topics

Be sure to star the repo and check back often. Pull requests welcomed.

## License
<a rel="license" href="http://creativecommons.org/licenses/by/3.0/deed.en_US"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by/3.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/3.0/deed.en_US">Creative Commons Attribution 3.0 Unported License</a>.
