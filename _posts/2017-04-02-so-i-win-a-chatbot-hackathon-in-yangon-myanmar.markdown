---
layout: post
title:  "So I win a Chatbot hackathon in Yangon, Myanmar"
date:   2017-04-2 00:18:23 +0700
description: Story and notes from my hackathon experience in Yangon, Myanmar.
img: phoenix.png 
fig-caption: 
tags: [elixir, phoenix]
---

So I win a Chatbot hackathon last month in Yangon. Organized by GEN Myanmar, I win e-Commerce challenge and most favourite. Yesterday, my cousin back in Indonesia told me he want to make his own Chatbot, and my uncle ask me to give a few tips to him. I think it’s useful to put it here as well.
Design
There are several useful tips regarding how to design your chatbot.
1. Put one specific use case for your Chatbot, don’t be too generic.
Don’t aim your chatbot to be like siri, cortana, jarvis, or samantha (remember ‘hers’ the movie?). Before you start thinking to build chatbot, it’s a good thing to know the limitation of a chatbot. Unless you have some secret sauce technology, current chatbot cannot think like human. It boils down to ‘if else statement’, basically. So the best way is to think a spesific funtion and build a design around that particular function.
2. Create a persona for your chatbot.
Don’t treat chatbot like a CLI (command line interface) where you input some command and it return bare information you asked. Give it character, make it tease you or tell you occasional joke when you ask something, make it feels more like chat with a human being. But don’t get me wrong, don’t pretend to be human. Don’t lie to your user. Give a hint and disclosure upfront your users are talking to a bot. If you lie, soon or later people will find out its a bot and they will feel cheated. Give full disclosure it is a bot, and surprise them with more humanly interaction along the way.
3. Think, and rethink user experience.
When people open your bot for the first time, give them a hint about what they can do. Ask question first. This way you can guide the user trough your purpose within your bot limitation. If the platform you choose provide button or quick answer selection (such as facebook messenger, telegram, or slack), use it. Instead of user should type freely all the time, when it possible, provide them button. Try over and over again to understand every dead node across the conversation, fix it, optimize it.
4. Come to where users are.
Instead of make one website for your chatbot or build mobile apps so people can use your chatbot, when possible, use existing platform. Most of the time, it can be done with facebook messenger. It can play text, picture, video, audio (up to 20 mb) and display nice cards (up to 9 cards). You can then focus on how to attract Facebook user (which is almost everybody) to come using your page instead of open new website or download new apps.
Regarding Technology
1. Don’t reinvent the wheel.
Some of the people code the chatbot from ground up with the language they understand, simply because they not aware there already bunch of tools for it. If you prefer to have full control of your chatbot behavior and prefer to host the engine in your own server, there are ‘Program-o’ (for PHP), then you only need to program AIML for it. For general purpose chatbot especially if you use facebook messenger as your platform, chatfuel is more than enough. It have many feature such as easy integration with facebook messenger, drag and drop AI ‘programming’, easy connection with outside json API. The only drawback is : it doesn’t understand context. But most of the time, it get the jobs done and more.
2. Hack the hell out of your tool
Whatever tool you use, ensure you know much about its feature and how to extend it. Tool like chatfuel seems basic but when you know it inside out, it still amazed me what people can do with it.
3. Extend the tool you choose to create something new.
When you trust existing tool like chatfuel or program-o to handle the basic conversation flow, think about the external data source to make it interesting. Otherwise, chatbot with static data can be boring pretty quick. Ask the bot to tell joke, or ask the bot to tell what exchange rate for today (you get the idea), you can make it exciting and useful.
Regarding Hackathon strategy
1. Everything is boiled down to one minute presentation.
Most of the hackathon only provide you very limited amount of time to present your product. Don’t too focus with your product and spend the last hackathon day to prepare your presentation. Many good product in the hackathon fail to grab attention of the judge becaue their lack of prfesentation strategy. Practise to highlight the feature and the flow of your product (and why it is important to be exist) within the provided time (we got 4 minutes for this event).
2. Do your networking and collaboration.
Don’t forget this is not only a competition, use your time to talk to other people, other group, ask something, help someone, and share your product. If ready, ask them to use and get feedback. You might get ‘participant choice’ award because of that.
In the end, we can think chatbot as an interface to a software we built. Instead of provide them with static menu, we guide them with every function they choose in interactive way.
I hope this note can be useful for someone interested in AI, chatbot, or hackathon in general. Also for my cousin.