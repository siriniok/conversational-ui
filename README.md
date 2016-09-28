# The Conversational UI Handbook

Bots are amazing and you can hear about them everywhere now. But what they really are? Just a funny toy or a powerfull tool for your business? Here is your guide into the Converstaional UI World. We collected the most important information and tried to answer the most important questions. The handbook is fully community driven.

Feel free to share this content under [a CC license](https://creativecommons.org/licenses/by-sa/4.0/ "CC-BY-SA").
**Send a pull request with your edits and ideas!**

## General Questions

### Should my bot pass the Turing test?

### What is the ideal conversation?

The ideal conversation is the one that enables users to accomplish their task with the least effort. Depending on context, this may mean shorter or longer conversations — the one that imposes the least cognitive load on the user is the best.

## The Bot Lifecycle

![The Bot Lifecycle](https://cdn-images-1.medium.com/max/400/1*ZD3hzuZdXqQWAermzrWmXw.png)

*Image by [Beerud Sheth](https://twitter.com/beerud)*

This approach to bot developing [was described](https://chatbotsmagazine.com/the-bot-lifecycle-1ff357430db7) first time by Beerud Sheth.

### 1. Requirements

The first step is very similar to any software project: decide who is your target customer, what are the pain points he has and what benefits your bot will deliver. Here is very important to analyze existing solutions (apps, websites). Can your bot compete with them?

### 2. Spec

Now you have to develop a product spec for the bot. First, try to describe the bot in few sentences: what it does and how? Indentify the features and functionality of the bot. How it should behave in different cases? And answer the main question: how your bot will deliver benefits described in requirements?

### 3. Script

This step is unique to the bot designining process. While websites and apps have structured interfaces, bots have a conversational interface. Instead of building wireframes you need to write conbersational scripts that represents human-bot interactions (in a form of actual user conversations). The bot script must guide the user towards accomplishing the desired task. 

### 4. Architect

Design the bot. This includes both the front-end (conversational interface) and back-end components (computation performed by the bot, integration with other web services).

### 5. Dev

Now your development team can implement the bot and its conversational interface.
Developers must also insert tracking probes into the bot — these will be helpful at the Track stage.

### 6. Test

The code must be tested not just in the emulator, but also in the actual messaging platform. The QA process also needs to be aware of, and ensure compliance with, the Publish guidelines of the messaging platform. Messaging platforms have different guidelines (e.g. bots must not spam, they must introduce themselves, explain themselves, behave themselves, handle exceptions etc).

### 7. Deploy

Once the bot is built, it must be deployed to a hosted environment. The proccess of deploying bot is similar to deploying website backend. Make sure that your bot uses HTTPS protocol.

### 8. Publish

Once the bot is tested and deployed, it must now be submitted to the various app stores for approval.

### 9. Monitor

You have to monitor the bot using actual conversational scripts. The ops monitoring may indicate systems are well, but the bot may still be unresponsive to certain user conversations.

### 10. Promote

Make your bot discoverable.

### 11. Analyze

As the bot starts being used, its performance must be tracked and results analyzed. This involves reviewing both conversation logs and usage metrics. Developers must identify and fix the leakage points — where the conversations are breaking or being abandoned.

You are awesome! Repeat!

## Resources

* [Bots don’t need to pass the Turing test — just the beer test](http://venturebeat.com/2016/05/02/bots-dont-need-to-pass-the-turing-test-just-the-beer-test/) by [Amir Shevat](https://twitter.com/ashevat)
* [I was an undercover-bot for 2 months. Here is what I learned](https://chatbotsmagazine.com/bots-hype-or-glory-656f4d614efb) by [Ami Ben-David](https://twitter.com/amibendavid)
* [The Bot Lifecycle](https://chatbotsmagazine.com/the-bot-lifecycle-1ff357430db7) by [Beerud Sheth](https://twitter.com/beerud)
