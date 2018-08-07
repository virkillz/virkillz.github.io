---
layout: post
title: So I write a Multichain library for elixir
date: 2018-08-07 13:32:20 +0300
description: Generate a website from bunch of markdown. Elixir way
img: multichain.jpeg 
fig-caption: 
tags: [elixir, blockchain, multichain]
---

In several projects I'm dealing with, I ended up using Multichain everytime there's a financial transaction involved. In other post, I will explain more about Multichain and what spesific business requirement it can resolved.

In previous implementation I wrote backend using python and recently: nodejs. Both have a good library where I can call the function to connect with Multichain server without crafting http call and json rpc content.

However, the latest project we decided to use elixir. Problem is, we can't find an exisiting Elixir library to connect with Multichain. 

So finally I made my own. Not only a flexible wrapper, but also an additional module to operate several usefull call which usually combined. For example, creating new keypair usually combined with importing address to the node and grant send and receive permission to it.

Anyway, hope it can help someone out there. 

Check its [Github Repo](https://github.com/virkillz/multichain-elixir)

also published as library in [Hex.pm](https://hex.pm/packages/multichain)