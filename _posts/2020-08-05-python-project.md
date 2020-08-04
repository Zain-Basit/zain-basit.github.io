---
layout: post
title: "That project I was talking about"
date: 2020-08-05
---

So I started a project in Python like I mentioned before. I wanted to create a Discord bot, but those are usually based in C# and JavaScript, and I don't have much experience in either of those languages. So I thought I wouldn't be able to build a bot in Python. BUT! I found a pretty cool Python library called discord.py that gives you a lot of support to build a bot in Python, so I used that to build the bot. 

Like I said previously, the bot was going to be for Legends of Runeterra. I had a hard time figuring out what I wanted to name the bot, but who else to name it after than the best card player in all of Runeterra. Twisted Fate! Legend says he's never lost a fair game...or played one!

<figure>
    <img src="/images/blog3/bot.png" alt="A picture of the bot's profile menu" class="center">
    <figcaption>Here's a picture of the Bot's Profile Page</figcaption>
</figure>

As I was thinking about what I needed for the bot, I planned out a bunch of stuff I'd need to do/figure out: 

1. I had to figure out how to parse a deckcode, which is how you share decks in the card game. They look like this: CEBAEAIEBALQWAQGA4EASGBCFAXDANZ2HYAACAICAYFA
and I need to make that readable for humans. When I parsed the code, and all my formatting and decoding and MAGIC, it looks like this:

<figure>
    <img src="/images/blog3/deckembed.png" alt="A picture of a deck code that has been parsed" class="center">
    <figcaption>A deck that uses cards from Bilgewater and Piltover & Zaun</figcaption>
</figure>

2. I need to implement a way to display keywords for the cards, and what they do. You see, each card had different effects and they could be something like the Tough effect. That's when a card takes 1 less damage from ALL sources. I needed a way to display that for people who wanted to look up keywords or if they wanted a list of all keywords entirely.

<figure>
    <img src="/images/blog3/tough.png" alt="A picture of a card that has the tough keyword" class="center">
    <figcaption>This Poro Card has Tough on it</figcaption>
</figure>

3. I need a way for people to look up card names in the bot, and see their stats, cost, and description. To be honest, I need to look more at the documentation for the libraries I'm using, because I haven't figured out a way to pull this information yet. 

With all that stated, one of the first things I did was look up the Runeterra API to find a way to parse the deck codes. They had a link to a C# GitHub repo explaining how the parsing worked, and they also had other libraries for other languages. So I installed two of the Python ones and started learning them. 