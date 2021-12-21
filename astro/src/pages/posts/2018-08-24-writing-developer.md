---
title: Writing like a Developer
excerpt: "Having spent a fair bit of time both writing and coding, I’ve noticed that these two seemingly disparate crafts have a lot in common. They share some vocabulary: we *read* and *write* code; a coding *language* has a particular *syntax*; Python even has *dictionaries*. More importantly, however, both disciplines have best practices, communal knowledge gained over years that we must learn in order to consider ourselves skilled practitioners. These best practices have the common objective of more-effectively communicating one’s ideas to other people"
published: true
categories:
  - writing
  - bestpractices
publishDate: 24 Aug 2018
setup: |
  import Layout from '../../layouts/BlogPost.astro'
---

Prose and code aren’t so different after all

![“A hand taking a clear shot of hanging lights with the camera of a smartphone” by [Dustin Lee](https://unsplash.com/@dustinlee?utm_source=medium&utm_medium=referral) on [Unsplash](https://unsplash.com?utm_source=medium&utm_medium=referral)](https://cdn-images-1.medium.com/max/8000/0*eAb05VbkEMFdwDql)*“A hand taking a clear shot of hanging lights with the camera of a smartphone” by [Dustin Lee](https://unsplash.com/@dustinlee?utm_source=medium&utm_medium=referral) on [Unsplash](https://unsplash.com?utm_source=medium&utm_medium=referral)*

Having spent a fair bit of time both writing and coding, I’ve noticed that these two seemingly disparate crafts have a lot in common. They share some vocabulary: we *read* and *write* code; a coding *language* has a particular *syntax*; Python even has *dictionaries*. More importantly, however, both disciplines have best practices, communal knowledge gained over years that we must learn in order to consider ourselves skilled practitioners. These best practices have the common objective of more-effectively communicating one’s ideas to other people. So, before you write your next blog post, try approaching your prose with the same principles that you apply to your code, and the result will be clearer, more-persuasive writing.

## **Single Responsibility Principle**

The hardest working principle in the dev business doesn’t just apply to coding. As we’ve all heard many times already, the single responsibility principle can be boiled down to the idea that each part of our code (class, method, etc.) should do only one thing and do it well. We don’t want to leave a bunch of sporks lying around. Each piece is aligned with, and contributes to, the whole, of course, but if we’re working on a class or method that is doing too much, the standard recommendation is to break it up into separate pieces.

A good piece of writing should have a similar organising principle, with the piece itself having one purpose, and each paragraph and sentence contributing to that purpose while only doing one thing at a time. If you’re writing a tutorial, don’t editorialise on your tool preferences or offer your opinion on the latest Twitter UI change. If you’re writing an opinion piece, don’t offer you’re top five tips for improving front-end performance. Writing an outline goes a long ways toward accomplishing this, as it becomes immediately clear if a paragraph deviates from the main idea when you’re only comparing a handful of topic sentences.

## **Sketch an Outline**

Before coding a new feature, we should (but often don’t) plan out our classes, especially their interfaces, consider how our code will fit into the existing application. One doesn’t necessarily have to resort to intricate UML diagrams that would put the Cave of Altamira to shame, but a little planning goes a long way toward identifying potential problems and minimising backtracking due to going down the wrong path.

Similarly, before writing an essay or tutorial, organise your thoughts into a concrete structure to make sure they all fit together and flow in a logical order. In the heat of the moment, it’s easy to follow an idea only to realise that after a few paragraphs you are in full-on tangent mode and have left behind the main purpose of your post a few hundred words ago. Such digressions during the writing process aren’t always a waste of time: they can help clarify your thinking about other parts of your post, for example. The problem is when one becomes overly enamored of such tangents and decides to include them in the final draft, diluting the main purpose of the piece of writing.

## **Always keep the requirements in mind**

Scope creep, the larding of new, non-essential requirements onto a feature branch, is anathema to us as devs: it delays deployment, often breaking real or imagined deadlines, resulting in the hapless dev being blamed for working so slowly. There is an inverted form of scope creep, however, that we should be equally vigilant against, that of the dev diving down a rabbit hole of paying off tech debt, spending weeks on refactoring old classes or components, while the project manager is just waiting around for that new drop-down menu. We shouldn’t go to the other extreme of doing the bare minimum for each ticket, of course, but being mindful of the requirements of the project that we’re working on gives us something concrete to guide our code. Do we need a brand new class, a new higher-order component, or can we extend existing code? How much clean-up of legacy code is required for us to accomplish the objectives of this ticket? Achieving the right balance is difficult and good, clear requirements give us reasonable boundaries to help with these decisions.

When writing, especially as an amateur, you’re unlikely to be assigned specific topics revealed unto thee from on high. You write whatever the hell you want, and anyone is free to read it or ignore it. Therefore, you’ll want to think hard about who your intended audience is, and what you want to communicate to them: these are your requirements. A blog post should have a more-casual tone than an academic article, for example. Otherwise, you’ll come off as stilted and overly dry to the general public (unless your intended audience are academics). Also, you’ll have to be conscious of your use of technical language, especially esoteric jargon that a general audience is unlikely to understand. People might be willing to look up the meaning of an acronym or two, but if a post is littered with them, the readers will eventually give up.

![Photo by [Priscilla Du Preez](https://unsplash.com/@priscilladupreez?utm_source=medium&utm_medium=referral) on [Unsplash](https://unsplash.com?utm_source=medium&utm_medium=referral)](https://cdn-images-1.medium.com/max/10944/0*vFeIF14wRcjZ_Pzb)*Photo by [Priscilla Du Preez](https://unsplash.com/@priscilladupreez?utm_source=medium&utm_medium=referral) on [Unsplash](https://unsplash.com?utm_source=medium&utm_medium=referral)*

## **Linting, testing, code reviews**

Just as git add . && git commit — amend — no-edit && git push — force isn’t a great idea, especially while on master, simply because you’ve finished writing a post doesn’t mean you’re ready to hit ‘publish’ just yet. When writing code, we use linters to correct style and basic errors, tests to catch more-complicated errors, and finally we do code reviews to get a second opinion on everything we’ve done, all before we can even think about merging into master. When writing prose, you have similar tools at our disposal. Spell-check and grammar-check can catch the basic errors for you. Also, reading your piece aloud can make problems with flow or awkward sentences more obvious, but having someone else review your writing and offer suggestions is often the best way to make sure that you’re communicating your ideas clearly.

## **Don’t overdo best practices**

I am a perfectionist by nature, and I have a feeling that I’m not alone among developers in this respect. The downside of perfectionism is that it can go too far and cause excessive procrastination. No code, no piece of writing will ever be as good as it is while it’s still a vague concept inside your head, which can inspire people to put off disappointment by keeping all that work hypothetical for as long as possible, whether it means spending weeks over-engineering a small feature request or thinking through a blog post rather than just writing down their ideas. It requires discipline, but if you have an idea for a piece, just write it, and don’t worry too much whether it’s good, because it’s definitely not. First drafts are never good. The important thing is to give your thoughts a definite shape in the form of words on a page or screen, because you can always go back later, revise and refine your writing, hopefully making it good in the process. But if you’re waiting for perfection, or sufficient inspiration, you’ll never write anything, good or bad.

## **Write with empathy**

We talk a lot about best practices and come up with evocative acronyms for them, like DRY and SOLID, but I’ve also seen developers far smarter than I admit that a little duplication is preferable to the wrong abstraction, and we’ve all seen code optimised to the point unintelligibility. Best practices in coding are meant to make reading and writing code easier for humans, not machines, and when we forget that, viewing these principles as goods for their own sake rather than means toward the good of making things easier for the next developer who comes across our code, we are writing fundamentally bad code.

So, if you’re going to put your writing out into the world, try to consider it from the perspective of your potential readers. Will they find it interesting, useful? Will they be confused or bored? The cleverness of your arguments and the depth of your knowledge won’t amount to much if no one can understand you or be bothered to finish your piece. The ultimate goal of publishing one’s writing, regardless of the forum or style, is to have people read it and get some value out of it. Otherwise, you might as well just jot down your thoughts in a notebook that’s headed for the shredder as soon as you’re done.
