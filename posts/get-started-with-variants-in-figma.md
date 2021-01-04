---
layout: layouts/post.njk
date: 2020-11-03T15:39:08Z
tags:
- Design
title: Get started with Variants in Figma
description: An introduction to the latest feature in Figma.
canonical: https://uxdesign.cc/all-you-need-to-know-to-start-using-variants-in-figma-e05915c424d6
elsewhere: true
canonicalname: 'UX Collective'

---

Figma released an update last week to bring the Variants feature to everyone. Variants were first announced back in September, at Config Europe 2020. They’re now available to everyone using Figma in-browser or on the Desktop app.

Let’s take a look at how they work.

### What are Variants

Variants are a way of grouping similar components together. You do this by selecting the components and combining them into something called a _component set_. Each component then becomes a _variant_ in that _component set_.

![A diagram showing how individual components can be grouped as a component set containing variants.](/img/variants-1.png)

Grouping similar components as variants in a component set is **unbelievably useful** when you’re using those components in your designs. Moreover, the benefits are compounded when you are designing complex screens across a range of devices.

### When to use Variants

Variants are great to use if you’ve ever made multiple versions of the same component.

As you can see above, creating buttons are a great example of this. Often a design system needs multiple types and combinations of buttons: large buttons, small buttons, buttons with icons, buttons in a hover state, buttons in an inactive state, and so on. Previously, it was incredibly difficult to swap between instances of a button, and it could only be done at the lowest grouping level.

So, if your design system was set up so that a button is created like so:

**> Button / Primary / Large / With Icon / Hover**

Then you’d only be able to swap between that last grouping, e.g. between default/hover/inactive/pressed.

Using variants instead makes swapping way quicker and easier. All the variants are available in the sidebar for you to access quickly.

![The new instance panel in the Figma sidebar showing variant options.](/img/variants-2.png)

### Why are they called Variants

All of this may sound like a really good way to handle component _states_. You’re probably therefore wondering, like I was, why the name ‘variants’ was used. Wayne Ng, from the Figma team, shed some light on this on Twitter, by [sharing a clip](https://twitter.com/worldwydewayne/status/1321518571424411653) of a usability test that Figma conducted with the team at Fidelity, who was testing an early beta of Variants.

From that clip:

> \[Calling it\] ‘states’ waters down the power of it… It makes you think, just, states of a button, or states of an object, as opposed to ‘super customizable component that you can do whatever you want with… feature’

### What we still can’t do… yet

Prototyping between variants doesn’t work exactly as you might expect just yet. You can’t hover on a button in its default state and have it seamlessly swap to a hover state, without wiring up lots of duplicate screens. This makes prototyping multiple states simply not feasible for most moderately complex designs.

This might be something that’s coming soon though. Back in September, at Config Europe 2020, the Figma team showed off a new feature for prototyping simple component interactions, which means you won’t have to wire up every iteration of a component state when prototyping. You can [watch the video here.](https://youtu.be/lWy4fB3G9Gc?t=798) It’s coming in January 2021 and is something I’m really looking forward to.

It’s also worth pointing out that you _do_ still need to create every permutation of a component in your design system. So the creative process isn’t sped up. But by using variants, you’ll speed up when actually using components, and you’ll benefit in both efficiency and organisation.

### Developer-friendly

Variants also bring your design closer to code.

The updated _Inspect_ panel allows the developers who will eventually implement your designs to copy a set of properties in one click.

This means that, if you align with your developers about what terminology they use, you’ll be able to save them a lot of time when setting up Variants.

![The new Inspect panel for copying variant properties.](/img/variants-3.png)

### How to get started

The best way to get started is just to try it out!

![A screenshot showing where the Combine as Variants option is in the sidebar.](/img/variants-4.png)  
_You can see the new_ **_Combine as Variants_** _option on the right hand sidebar._

If you have a Figma file with a design system, or even just one with a few similar components, give Variants a spin. Select a group of components and hit that magical _Combine as Variants_ button in the sidebar. So long as they are labelled with properties separated by a ‘/’ divider, it’ll work automagically.

(I would probably duplicate the file first, though, just in case you need to go back.)

Play around with options for naming properties and check out the new way of swapping between instances. You’ll soon see how valuable and time-saving it is.

![A screenshot of the official Figma Variants Playground file.](/img/variants-5.png)

**I also highly recommend checking out the** [**official Figma introduction file**](https://www.figma.com/community/file/903303571898472063). It takes about ten minutes to go through. You’ll learn about a lot of hidden things which you might not spot, such as making properties into toggles by using boolean values, and reordering properties.