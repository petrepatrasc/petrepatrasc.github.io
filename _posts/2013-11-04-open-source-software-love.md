---
layout: post
title:  "cat software-love = open source"
date:   2013-11-04 14:50:13
categories: open source love
---

Today I'm going to be writing a bit about open source software, and why I think that it translates into love for humanity and progress - I'll also touch on a few interesting things that I've been hacking away at recently.

## Open source

![Open source](http://www.design-by-izo.com/wp-content/uploads/2010/09/heart-opensource-440x280.png)

### Viktor

Let's have a look at *Viktor Örneland*'s [design of a telephone](http://thenounproject.com/noun/telephone/#icon-No1025) - he built this vector icon (most likely in his spare time) and considered that his work was something that would benefit humanity - he didn't want to obtain any profit, fame or blog hits through it, and thus he released it as a **Public Domain Mark** - meaning that anyone can use it freely, commercially or publicly, without attribution:

> The person who associated a work with this deed has dedicated the work to the public domain by waiving all of his or her rights to the work worldwide under copyright law, including all related and neighboring rights, to the extent allowed by law.

> You can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission.
    
Because of Viktor's involvement in the community, the next time you need a telephone icon for a project you're working on, you can use this timeless vector freely, without worrying about attribution, VAT or country laws.

### OSS

![May the source be with you](http://www.kinvey.com/blog/images/2013/09/may-the-source-be-with-you_open-source.jpg)

Software has had its own share of legendary packages - the likes of **Wordpress, Linux, Firefox, VLC, 7-ZIP, Gimp and Open-Office** have been developed through community efforts and bright-minded leaders. We see open source everywhere these days, and it drives the progress of human kind - community work is much more than an ideal, it's a means to *free speech*, to *the good of all*. 

It is a clear separation from the monetization that we see in our daily lives - and the most touching part of it is that open source contributors aren't looking for donations, or free money; instead, most of them would like to see a community growing around their product, connecting people from different backgrounds and specialties, into creating wonderful and driving experiences.

### This probably isn't for me

**Yes, it is**. People can help with whatever - whether it means translating an application into a different language, adding some tests to existing code, or creating a video/presentation to highlight the key features of a product. You can literally join and change any open source project out there and adapt it to how you want.

What's even more amazing is the trend that we're seeing in some QA tools; let's have a look at [Travis](https://travis-ci.org/) or [Codeship](https://www.codeship.io/). Both systems allow you to checkout a VCS project and run your automated tests - if the build passes, all is great, and you can deploy to other systems automatically; if the build fails, you're immediately notified via email or chat/IRC services. For private projects, Travis costs 129$/month for unlimited projects, while Codeship is 9$/month, for limited projects and builds - however, if the project that you're developing is open source, then using both services is **free of charge, forever**.

### So what now?

Consider having a look at [How non-programmers can contribute to open source projects](http://opensource.com/life/13/10/contribute-open-source-project-no-code) by **Duncan McKean** if you're not the technical type. If you're a developer/designer, head on over to [GitHub](http://www.github.com) and all shall be revealed. Heck, might as well watch this [video on collaborating using GitHub](http://www.youtube.com/watch?v=RTP7rj3pny0) that I've made some while ago, or feel free to pop a question if I can help personally.

## Things going on with me

![Where is my mind](http://impossiblypossible.files.wordpress.com/2008/08/where-is-my-mind.jpg)

In the last few weeks, I've been working heavily on two open source projects (which I don't need to touch on just now) and thus have been pretty tired. I've also explored a lot of workflows with continuous integration and QA tools (*Travis, Codeship, Scrutinizer, Coveralls*) and have experienced cloud deployment using *Fortrabbit*, but I'll talk about them a bit more in the future since I want to also launch an associated video series to compliment the posts - suffice to say is that at the moment I simply push to a **GitHub** branch, **Travis** picks up and runs my build, **Scrutinizer** analyses code quality for the project (cyclomatic complexity, etc.), **Coveralls** checks the code coverage for my tests, **Codeship** makes a final check of the tests and deploys to my cloud Paas, **Fortrabbit**, updating dependencies as needed.

### Digital Analytics Fundamentals

![Google Analytics](https://lh6.googleusercontent.com/-NtT5gMJiTr0/AAAAAAAAAAI/AAAAAAAABec/H54w2yEed_E/photo.jpg)

I've taken some time to participate in the **Digital Analytics Fundamentals** course from *Google*, and managed to get my certification with 100% in the final exam. I've found great value in following the course, and hope that Google decides to run the same format for other Apps - the mix between video and text proved very useful, and the Cisco format of having assessment questions at the end of each chapter is of course, a very good decision. 

### Careers 2.0

![Careers 2.0](http://i.stack.imgur.com/ogH8O.jpg)

I've also recently been invited to Careers 2.0, and I'm very much loving it so far - the level of customization in the resume generator is so developer-oriented that it's clear to me I'll never go back to other tools. Much more than that, it feels that Careers is a living ecosystem, where profile management is more about expressing yourself on a variety of topics (Open source, articles written, community help, favorite readings), thus expressing much more breadth. [Have a look at my profile here](http://careers.stackoverflow.com/petrepatrasc).

Is the service as social as **LinkedIn** for instance? No, and that's very much OK - again, this is coming from a developer's perspective. Have a look at [*Log in or sign up with GitHub, but not with Facebook*](http://blog.leahculver.com/2012/02/log-in-or-sign-up-with-github.html) by **Leah Culver**, it's a very good read on how developers tend to stay away from social networks and appreciate dedicated tools much more.

- Petre.