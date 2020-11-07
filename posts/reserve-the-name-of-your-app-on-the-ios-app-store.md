---
layout: layouts/post.njk
date: 2020-10-28T15:28:01Z
tags:
- Sound Off
title: Reserve the name of your app on the iOS app store
description: A quick guide to reserving the name of your app on the app store
canonical: https://medium.com/sound-off/how-to-reserve-the-name-of-your-app-2752c0a4e91b

---
It’s really simple to reserve the name of your iPhone app in the Apple app. Years ago there used to be [a ‘bad guy’ way](https://blog.salsitasoft.com/apples-new-app-name-reservation-policy/) of doing this, involving rejecting the app yourself so a name could be preserved indefinitely — but Apple has since changed their policies about name reservation.

There used to be an expiry limit for reserving your app name — initially, it was 90 days, then it rose to 120 days and in 2015 to 180 days — but that time limit has now been removed.

**There’s currently (as of writing) no information publicly available online about how long your app name will stay reserved**, but I’d be willing to bet if you don’t submit a build within three months after reserving a name, you’d be likely to lose it at the hands of the Apple Gods.

As of 2020, these are the steps you should take to reserve the name of your iPhone app:

* You first need to set up an [**Apple Developer account**](https://developer.apple.com/).

You can make the Developer account using your normal Apple ID. Being part of the Apple Developer Program [gets you access](https://developer.apple.com/programs/how-it-works/) to all the tools, resources, and SDKs you need to build an app. The annual fee for this program is **$99 USD**.

* Once you have a Developer Account, log in to [**App Store Connect**](https://appstoreconnect.apple.com/)**.**

This is what App Store Connect looks like:

![](/img/app-store.png)  

App Store Connect (previously called iTunes Connect) is the place where you manage all your apps sold on the App Store, whether they’re for iPhone, iPad, Mac, Apple Watch, or Apple TV. It’s where you to submit and manage your apps, invite your users to your TestFlight beta, add your tax and banking information, and more.

Once you’re all set up and in App Store Connect, complete the following:

![](/img/app-store-2.png)

* Click **My Apps,**
* Click the **+ button** and click Add New App
* Add information about your app: the app’s name, a unique SKU for the App Store, the language it will be in, and which platforms it’s for.

At this stage, you’ll also be asked for a bundle ID. The bundle ID must match the one you used in Xcode. **It can’t be changed after you upload your first build, so make sure you (or your developers) are certain of your bundle ID.** The standard format is a reverse domain name; this naming scheme is the same for both the Apple App Store and the Google Play Store. So, for example, if your company is called Acme Inc, and has the domain name _www.acmeinc.com_, and is releasing a podcast app, the bundle ID might be: _com.acmeinc.podcasts._

At this stage, the name and subtitle will still need to be reviewed one more time before it's approved in the App Store, as these are localized depending on your region — but you’ll have your SKU confirmed and your app name reserved.

Once you’ve completed this, you’ll be all good to go!

Remember, before starting this, **do a thorough search of the App Store** and online to check that your chosen app name is actually available. (It’s also worth checking for registered trademarks at this point, and check with a lawyer in case you spot any areas of potential conflict.)

Also, before starting on your app-creating journey, stop to consider: [should you _really_ be building your app idea?](https://medium.com/sound-off/should-you-build-your-app-idea-4fbc97c777fa)