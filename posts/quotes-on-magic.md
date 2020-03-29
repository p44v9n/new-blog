---
layout: layouts/post.njk
comments: true
title: Quotes on Magic
description: Building a random quote website
tags: Dev
date: 2017-05-24
---

A week or so ago I made a super simple site. I made the majority of it in a day but have been constantly tweaking it (mainly the CSS!) and adding content. It's a site that displays a random quote about magic / a quote by a magician.

The site is now live at [http://quotesonmagic.com/](http://quotesonmagic.com/).

The idea comes from [this challenge](https://www.freecodecamp.com/challenges/build-a-random-quote-machine) on [freeCodeCamp](https://www.freecodecamp.com), a really cool online course for learning to code. The challenge said to host on Codepen, but I've hosted on Github Pages (and the whole thing is [here on GitHub](http://github.com/p44v9n/magicquotes/) if you want to take a look).

The challenge had these requirements:

- click a button to show a random quote
- click a button to tweet the quote, trimming characters as appropriate

This site has both those things. I've also set it so it will tag the person whose quote it is on Twitter if they're on Twitter, by adding an extra field to the (json) list of quotes.

The whole thing is really light-weight. Just vanilla JavaScript ([that great framework by that dude Brendan ;)](https://hackernoon.com/how-i-converted-my-react-app-to-vanillajs-and-whether-or-not-it-was-a-terrible-idea-4b14b1b2faff)) in one JS file, most of it being a huge object with the content. Even has space for an easter egg if you're not on mobile. Also a reset plus a 275 line CSS file, most of which is for the cool link hover effects (from [Tympanus.net](http://tympanus.net/Development/CreativeLinkEffects/)). Lots of hacky CSS to get it to look nice cross-device, but it seems like it's all working fine glitch-free. Definitely wasn't made mobile first though. Just the old school developer style of adding more and more rules to fix things you previously broke. ([Two CSS properties walk into a bar. A barstool in a totally different bar falls over.](https://twitter.com/thomasfuchs/status/493790680397803521?lang=en)) And submit page is done all static / frontend only by using [Formspree](https://formspree.io/).

Some things that could be added are:

- a permalink to each quote (right now this happens on the /all page, as when that generates each quote it gives it an id="#". but would be cool to do something to solve this with address bar hashing)
- a better random (or rather, a less random) algorithm so we don't get same quote twice in a row when cycling through
- a better way of storing all the content instead of just in that JS file (anyone got any ideas?)
- a better way of submitting quotes (though no idea how to do this without a backend)

Also, the big white circle was meant to have a little reload icon in it, but I quite like how it looks as is. Supe minimal. Also also, I was going to use a random background image of fixed size using [Unsplash Source](https://source.unsplash.com/), but I didn't like the load times and I didn't like how often it gave images I didn't like. However, might use this idea ([it's just a single line that's commented out at the mo](https://github.com/p44v9n/magicquotes/blob/master/css/styles.css#L3)) if this ever becomes a Chrome extension new tab page. (That might be a fun thing to code up? Never made a Chrome extension before). 

Domain will stay up for a year or so, so if you're reading this in 2018 and the above link doesn't work try hitting up [this link instead](https://p44v9n.github.io/magicquotes/).

Lastly, if you have more suggestions for quotes to add please send them my way!

P