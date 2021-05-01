---
layout: post
title: Intro to Writing Discord Bots in Rust
description: How create your first Discord bot using the most loved language
date: 2021-05-01 16:00:23 +0600
categories: Rust Discord
---
Discord is a instant message platform with more than 150 million monthly active users. The main appeal seems to a combination of the wide reach that platforms like StackOverflow have, as well as the instant delivery of the instant messaging concept. One of the best features of Discord is it's seemingly unlimited hackability of the platform via it's "Bot" system. The Bot system allows developers to add functionality to Discord communities by writing software that interfaces in a similar way that people do. I want to give you an introduction on how to do that in Rust.

## Interaction
Most interaction with Discord bots happens via commands, not dissimilar to terminal applications. Commands may look like `!play Eat it by Weird Al`.\
![Example of command](/assets/images/pong.png)