---
layout: post
title: Golang vs elixir is like one giant crane vs thousands minion
date: 2018-08-08 13:32:20 +0300
description: golang vs elixir
img: mac.jpg 
fig-caption: 
tags: [elixir, golang, erlang]
---

With so many programming language, framework, and technology in general, it is quite easy to be overwhelmed. Our time as a developer are limited, so it is understandable if we always try to find information even before we decided to invest our time to learn something new.

Elixir as relatively new programming language who offer concurrency is often compared to several programming language who offer the same in their marketing campaign. Nodejs which known to be scalable due to single-treaded-non-blocking-IO concluded to be inferor compared to elixir. There is no known argument against that. 

However, golang, another language who promote fun and power also often compared to elixir. How to compare between them two?

Golang is often described as writing C in a fun way, while elixir is described as writing erlang in a fun way. So it is kinda comparing C to erlang, in a way. C as a language is known to be closer to machine language and probably only can be beaten by assembly. You can get the most of power a machine can offer with 'closest to the metal' programming language since there is fewer additional processing layer.

What about elixir and erlang then? We need to understand that the power of erlang is not in the language itself. Erlang is nothing without Erlang Virtual Machine. EVM provide very good abstraction to handle concurrency without programmer need to think about it by himself. The code compiled into bytecode which runs on virtual machine and not the machine itself. 

Thinking this way, of course in theory golang and C can be utilised to handle the concurrency better assuming they run on the same machine. However, we talking about effort here. The reason people not code in assembly anymore is because eventhough the programming language is powerfull, it takes sooo many effort to perform a asimple task which can be done easily in other higher level programming language. We can compare how many line of code to produce 'Hello World' in assembly versus ruby or python.

In the context of modern application development where dealing with many concurrent user is most common problem, server with 4 core is better with an equivalent single core even with higher power. The problem is most of programming language is not designed to work with multi core, it is known to be very hard to program multi thread correctly. The reason is what we called 'state'. 

The story is different in erlang world where the process is handled by Virtual machine, and virtual machine will manage how and when to run process using available core. This can be done because by nature erlang is functional language. There is no state sharing, each process can be spin separately and safely.

The cost of this convenience is that we need to code in functional way. It is known to make simple task a little bit difficult. However, for functional programmer actually it makes most things simpler. They can break down many problem into very small function which take input and output, easy to compose, easy to compose, easier to debug. The only problem now is the syntax.

This is where elixir play its role. Elixir have a ruby like syntax with power of erlang virtual machine. Now functional programming is not scary anymore. Writing software which ready to handled many concurrent user as the same time, utilising all the core a server have becoming trivial things (and fun) to do.

Back to the title, how we compare golang into one giant crane because of its power to do heavy lifting. If you develop software which require big computing power such as image processing or 3d rendering, then golang can be superior since it is dealing with one heavy task. However most requirement for concurrency nowadays is not heavy lifting at all, serving a website is not heavy, but when we need to serve multiple visitor, we need tons of actor serving them. This is where minions analogy come to play. Having elixir is like having millions of minion in our army. 

Now, I hope it is quite clear how we can see the difference between those two programming language. Of course if you got more time, learn both. But the most important thing is to know which tool to use to better solve a particular problem.
