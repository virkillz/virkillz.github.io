---
layout: post
title: Obelisk Static site generator for elixir
date: 2017-09-12 13:32:20 +0300
description: Generate a website from bunch of markdown. Elixir way
img: jekyll.png 
fig-caption: 
tags: [elixir, jekyll]
---

## Obelisk Static site generator for elixir

As my favorite programming language, elixir. I want to be able to do blogging with static page and write blogpost with markdown. Currently my easiest option is jekyll. The problem with jekyll is it is built on Ruby and for every new theme or functionality it depends on gem. This create issue in my local machine where many of gem installation require root/sudoer. If I HAVE to use it, of course I will find a way to make it works.

However, there are tons on alternative. For example, I already familiar with Nuxt.js, but it is by nature not support markdown to be used as blogging platform. There are hugo which is more flexible.

But since currently, I'm in love with elixir, naturally I want elixir to have similar functionality. Spesifically for blogging purpose, I'm looking for a tool which easily able to:

- [ ] Allow me to write blog post using mark down and easy to publish
- [ ] Allow change template easily
- [ ] Have templating language which I'm familiar with or at least very easy to started.
- [ ] Built on language and ecosystem I already have will be a plus.


https://www.staticgen.com/ bring me to Obelisk. A static site build on elixir. They use eex as templating engine in a flow I'm already familiar with.

https://github.com/BennyHallett/obelisk.git