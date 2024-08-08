---
title: 'Angular Console — The UI for the Angular CLI'
slug: 'angular-console-the-ui-for-the-angular-cli'
authors: ['Victor Savkin']
cover_image: '/blog/images/2018-08-09/1*TigvMknUeSYC2BWKvnDCTw.png'
tags: [nx, angular, nx-console]
---

Today we are happy to announce Angular Console — the UI for the Angular CLI.

![](/blog/images/2018-08-09/1*RRvED36YY_cKDC0Eowtclw.avif)

Angular CLI transformed the Angular ecosystem. We no longer have to spend time maintaining our webpack configurations, figuring out how to make tests run, fixing source maps — the CLI does this for us. It also helps us enforce consistent development practices by generating components, services, and state management modules. Since the CLI does so much, it can be intimidating and hard to learn. Most developers only use a fraction of the CLI’s capabilities.

Last year, we at Nrwl built a set of tools, [Nx](https://nx.dev/getting-started/intro), on top of the Angular CLI. And we saw firsthand that we can only go so far until the developers get overwhelmed and lost.

We realized that most developers don’t need more sophisticated commands — **they need a more approachable way to use what the Angular CLI already does**. And that’s what Angular Console is.

## Who is it for

We have been testing Angular Console for some time now, and every developer we showed it to found it valuable. Developers on Windows and Mac, developers who are afraid to touch the terminal, and those spend the most of their day there, Angular experts and Angular novices — everyone agreed that it helps them be more productive with Angular CLI.

### Beginner Friendly

We aim to make Angular Console a great tool for developers who are new to Angular or Angular CLI. You can create projects, interact with your editor, run generators and commands, install extensions without ever touching the terminal or having to install any node packages globally. If you get a new laptop, you can install Angular Console and start building Angular apps. Also, Angular Console highlights the properties you are likely to use for build-in generators and commands . So if you haven’t used the CLI, you don’t get overwhelmed.

### Useful to Experts

At the same time, Angular Console is a robust tool that can do everything the Angular CLI can do — it’s the UI for the CLI. Every command you can run in the terminal, you can run via Angular Console. Except you no longer have to remember all the flags, names, or paths — Angular Console will help you by providing autocompletion and validating your inputs.

![](/blog/images/2018-08-09/1*sX6YNQ3SIpjpQ9u5Xgnr_Q.avif)

As Teddy Salmon from American Airlines put it “It takes a lot of the remembering out of developing, so you can focus on code.”.

## Future Plans

When we showed this tool to the Angular team at Google, they got really excited. This is what they wanted to build for quite some time.

That’s why the Nrwl and Angular teams decided to work on it together. We will closely work with the Angular team to make sure Angular Console remains a truly generic tool useful to the whole Angular community. We are excited to plan and develop it together, with the goal of making it a first-class way of using Angular, next to the Angular CLI.

## Try it Out

Check out [angularconsole.com](https://nx.dev/getting-started/editor-setup) to download the binary and start getting more productive.

![](/blog/images/2018-08-09/1*TigvMknUeSYC2BWKvnDCTw.avif)

### Victor Savkin is a co-founder of Nrwl. We help companies develop like Google since 2016. We provide consulting, engineering and tools.

![](/blog/images/2018-08-09/0*NSLFXiKLN4PAjCOW.avif)

_If you liked this, follow_ [_@victorsavkin_](http://twitter.com/victorsavkin) _to read more about monorepos, Nx, Angular, and React._
