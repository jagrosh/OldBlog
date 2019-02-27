---
layout: post
title: "Bot Concept: Accurate Leveling"
categories: Discord
tags: Discord Discord-Bots development concept
author: jagrosh
date: 2019-02-26
---

* content
{:toc}

## Motivation
I've discussed it [before](https://blog.jagrosh.com/2018/04/14/creating-and-growing-a-discord-server/#part-4-tips), but I'm not a big fan of bots that give "levels" or "experience" for sending messages. The most common way of handling this is just to simply give a set (or slightly-varying) amount of points for sending a message. Sometimes there is a cooldown, sometimes there is a minimum message length, sometimes there is a max number of points per day or time period. However, all of these systems suffer from the same problem: *it encourages users simply to send messages, rather than contribute positively to conversations*. I'm sure that some readers out there are thinking "yes, I want as much activity as possible," but from my experience, **not all activity is good activity**. 

## Goal
### Do:
- Encourage users to interact with the server
- Encourage users to contribute to conversations with relevant questions and comments
- Give proper representation to positive contributors on the server
### Don't:
- Encourage users to spam
- Encourage users to say irrelevant or 'filler' messages
- Encourage users to try to game the system
- Interrupt conversations with "level-up" messages
- Require extra work/learning on the user's part

## Other Social Media
So, how do other social media services solve this problem? Well, let's take a look at a few services that have a comparable problem, and see how they tackle it.
### Reddit
While reddit doesn't have the same structure to a normal chatroom, it _does_ have a good way of showing a user's experience, in the form of karma. Karma is gained from users up-voting your messages, and lost from users down-voting your messages (below zero). This becomes a fairly accurate representation of contribution, as meaningful contributions will likely get up-voted and gain karma, while pointless contributions or spam will result in the loss of karma. Additionally, it becomes more valuable to provide useful replies than it does to provide many meaningless replies. In short, karma is a good measure of quality over quantity.  
Of course, there are flaws to this system as well. For example, the karma system relies on the fact that every message has its own vote counter, which is not very feasible for (and would be obtrusive to) conversations in Discord. Even if some sort of reaction system were used, it would still require extra work by the end users, and they would need to learn how to use this system.
### League of Legends
I know what you're thinking: "League of Legends isn't even social media, it's a game!" That's true, but it does have a contribution system worth discussing. At the end of every match, each player is presented with a prompt to award 'honor' to one player on their team (or to nobody). This is nonintrusive during the game, yet still provides a decent indicator of who was friendly and cooperative during the match. Players are incentivized to be pleasant because players that receive a lot of honor get additional badges on their profile (and also because - in general - friendly, cooperative players are more likely to have better teamwork and thus win more).  
Again, there are issues with this system as well. League of Legends has strongly-defined matches; there is a clear difference between being in a match and being in the post-match lobby. Conversations don't always have as clear of a structure, as particular participants may drop out of a conversation at any point, new participants can join at any point, and conversations can slowly change topic over time without any 'end.' 

## Solution
