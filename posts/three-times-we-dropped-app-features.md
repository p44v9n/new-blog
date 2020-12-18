---
layout: layouts/post.njk
date: 2020-12-16T14:59:25Z
tags:
- Sound Off
title: Three times we dropped app features
description: A lookback at our focus on MVP during app development
canonical: https://medium.com/sound-off/3-times-we-pulled-app-features-5d64be2f82ad

---
I’m the co-founder of a startup called [Sound Off](https://trysoundoff.com/). We’re building the best platform in the world for audio journaling, which is [the easiest and most accessible way](https://medium.com/sound-off/making-journaling-easy-again-3dad70d39d68) to unlock all the benefits of keeping a daily journal.

Right now we’re in the product development phase of the process. We started with a detailed plan of what we hoped to accomplish… but, of course, initial plans never go the way you’d imagine.

To be clear: developing an app isn’t the most minimally viable option we could have. Earlier in this process, [we tested out an ‘MVP’ that only used the default voice notes app](https://medium.com/sound-off/start-with-a-make-believe-product-873c5ebb643b).

However, our proposition involves the branding and the ‘feel’ of what it’s like to sound off. So to really validate our proposition, we need an app that encapsulates all of that.

Our vision for the first version of the app had a lot of features that we thought were desperately needed. But during the development process, we realised that some of those features weren’t as essential as we first thought.

When this happened, Rory and I would stop and consider our goal: determine when we reach product-market fit. The first version of the app needs to have enough to allow us to determine that. No less, no more.

And, when we realised that, we would send each other an MVP gif on Slack to admit defeat and exclaim: MVP!

Here are three times we needed MVP GIFS…

### 1. Bookmarks

Early on, we really thought that saving/starring/bookmarking your previous recordings was something important.

We designed the whole section of the app, where the save icon appears on our player, and so on.

But we realised: it doesn’t matter if people can’t save a recording to a special place. [From early testing](https://medium.com/sound-off/testing-101-bf5caafc3dee/), we knew that most people weren’t concerned with listening back immediately after recording. And we knew it was better to invest time and energy into nailing the recording process.

We had become distracted by trying to achieve feature parity with other audio apps and forgetting what the core appeal of Sound Off was: simple and frictionless audio journaling.

So we postponed it. Bookmarks will be in the app one day, but it’s not a priority feature for now.

### 2. Calendar Sizing

Our app has a calendar element. This is important: seeing your progress and watching yourself build a streak that you don’t break encourages you to build a habit. Sounding off daily means that you can keep yourself accountable, you can track your emotions, and you can watch yourself accomplish goals over time.

(We’ve also got a really awesome and intuitive way of keeping track of how you’ve felt over time, using our calendar element. More on that soon!)

So having the calendar was important for this build. After some back and forth with our superstar developers, we got it all working correctly. It was scaling to different phone models, showing dates correctly, scrolling between months…

…however, we realised that while it was functionally perfect, it still needed some aesthetic improvements.

In the calendar element, dates are displayed with circles. We could have spent hours and hours tweaking the size of each circle for dates, getting the right opacity for the days before you started the app, getting the right stroke thickness for highlighting the current day. But after getting it working to a good standard, we decided to shout ‘MVP!’ and let it be.

### 3. Volume feedback adjusting to phone sizes

When you’re sounding off, and your phone’s microphone is recording, we have an element that gives audio feedback. It took us a while to determine what that element should be, as [the style of vocal feedback in iOS’s Voice Memos app is intimidating and off-putting ](https://medium.com/sound-off/whats-the-best-audio-journal-app-bf3dc962a2d7)— not what you want when trying to calmly talk about your day.

So we devised a calming way to provide feedback, giving you the confidence that your voice is being recorded. We used a third-party library to speed up development time, which displays circles that pulse out and expand from a central point. After implementation, this element was working and responding to our voices correctly.

But on Rory’s phone (the taller iPhone X) it came out way too small compared to my phone (the short, second-generation iPhone SE), because of the relative sizes of devices.

On my phone, the feedback reached up \~2/3 of the screen; on Rory’s, it reached less than half.

No matter: we could just scale the whole element, or adjust the radius, or calculate phone width and use that in a function to… Wait! Stop! This isn’t MVP! Focus on MVP! Someone send the MVP gif!

***

_If you enjoyed this article, I’ve previously written about_ [_the power of thinking in MVPs_](https://medium.com/sound-off/start-with-a-make-believe-product-873c5ebb643b) _and_ [_extensively testing each component part of our startup_](https://medium.com/sound-off/testing-101-bf5caafc3dee?source=your_stories_page-------------------------------------)_. My co-founders, Rory and Elly, also write regularly about the psychological research behind sounding off and our journey towards developing our brand and concept._

_We’re releasing an early version of the Sound Off app very soon, and if you message me, I can add you to our beta tester list._