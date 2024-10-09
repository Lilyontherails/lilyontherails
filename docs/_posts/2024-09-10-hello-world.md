---
layout: post
title: "Hello, world!"
date: 2024-09-10
categories: misc
---

As is tradition, the sentence "Hello, world" needs to be printed in some form when someone is being introduced 
to a programming language or any tool or project that requires some form of coding. This post is exactly
just that.

In this site I shall post musings on seemingly unrelated topics born out of spontaneous ideas on things
to do and to which I have actually dedicated a few hours or days arriving at something. Of little import the
results may be, but they still need to be documented in some form anyway. For sometimes it is not the
destination that matters, but the journey one takes to arrive at it.

I already have a few ideas lined up, detailed below. All that needs to be done is to put them in writing.

Back in October 2020, [SurfChu85](https://x.com/SurfChu85), [Ayane Satomi](https://github.com/sr229), 
[KaidenFrizu](https://github.com/KaidenFrizu), and I (who is known as [Eyenine](https://osu.ppy.sh/users/1259391) 
in the osu! community) did some statistical analysis on Arknights's gacha system, known in-game as 
"headhunting". Specifically, from a known time-dependent but resetting function for the success 
probability of getting a 6\* operator, we simulated the gacha and obtained a "negative distribution"[^1]" 
and an estimate for the expected value of number of failed pulls before getting a successful 6\* operator 
pull. Frizu ([^2]) and Ayane ([^3]) documented their part of the work, including codes written in R and 
Python and results. I revisited the problem in 2023 using a more analytical approach and found a mathematical
expression for the negative distribution. It may be possible to use this result to reproduce the success 
probability function of a similar gacha system given the base success rate and the effective success rate, 
as is the case in HoYoverse games such as Genshin Impact and Honkai: Star Rail.

[^1]: As far as I know, "negative distribution" is not a mathematical term in any sense, but is something I made up
to refer to the probability distribution of the number of failures in succession before getting a success in an 
experiment for which the probability of success and failure varies with the number of trials. This term is in 
reference to the [negative binomial distribution](https://en.wikipedia.org/wiki/Negative_binomial_distribution)
which is the same probability distribution but for an experiment whose success and failure probabilities are
constant.

[^2]: Frizu, "Arknights’ Non-6★ Headhunting Streak EDA". https://rpubs.com/Frizu/arknightsgacha

[^3]: Ayane Satomi, "Mapping out Gacha Pull Probabilities using Python and Google Colaboratory". 
https://dev.to/sr229/mapping-out-gacha-pull-probabilities-in-google-colaboratory-3ij9

In August 2024 I was introduced to a clicker minigame bot called 
[Grow A Tree](https://discord.com/application-directory/972637072991068220) when the bot was added to a
Discord server I frequent. In this minigame, members take turns clicking a button that waters the tree and 
starting a "growth timer" (effectively a cooldown timer) during which the tree will grow by one feet. 
The growth timer increases as the tree gets taller. When watering the tree, there is a chance that the community
composter is applied to the tree, reducing the growth time by a certain percent. The chance of the composter being
applied and the reduction in growth time depends on the efficiency and quality levels of the composter,
respectively, which can be upgraded using coins collected by the members through various random events. 
I looked into the most coin-optimal way to upgrade the composter to maximum efficiency and quality.

More updates will be posted in the future as they come. The spontaneous nature of the ideas for these posts 
means that update schedules are bound to be infrequent and erratic.
