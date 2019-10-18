---
layout: post
title: Should you build a native app or a web app?
description: Deciding whether to build a native app or not is hard. Of course it depends a lot on what your product is. Here we share our experiences.
---

App or no app? That’s a question that is regularly posed here at [Kittysplit Towers](https://kittysplit.com). Just to remind you, Kittysplit is a webapp for splitting expenses in a group. The app is responsive and works pretty great on a mobile browser: 80% of our users are mobile. Yet we often get the request: "please build an app!" 🙏.

Surely the answer is to build an app! Right?

![Kittysplit screenshots](/images/de_screen_collage.png)

Let's dive in. We’re actually pretty sure that many of our long dead competitors sealed their fate by deciding they needed an app. Once you have a good-enough webapp, the advantages of an additional native app are not that great.

## The case for having an app
What are the advantages of having a native app?

### 1. Do it for the mobile users
If 80% of Kittysplit users are on mobile, surely we should give them an app!

### 2. Enable offline access
People sometimes go to places with no wifi access (which we would never recommend) where they incur costs that need splitting. With an app, they could enter the expenses in offline mode and then things could sync up once they got back online.

### 3. Show your reputation and trust
It’s easier to convince potential users that your product is worthwhile and reliable if you have a large number of installs and a bunch of positive ratings in the app store.

### 4. Allow push notifications

Users could be informed that expenses have been added or edited for kitties that they’re involved with.

### 5. Allow an icon on the homescreen
 Once a user is constantly being confronted with your app icon, he’ll be much more likely to open it.

### 6. bragging rights
We’re a ~hipster~ startup from Berlin, so we absolutely need to have an app which we can wave around in smoky bars at three in the morning.

A pretty solid case so far. Let’s look at what the the other side has to say.

## The case against having an app
So what are the disadvantages of having an app?


### 1. It costs
App costs money &mdash; lots of it. Even the most basic app which does little more that say “Hello World” will have a price tag of 5k EUR. Once the app does fancy stuff like talking to a server that number skyrockets to 50k plus in no time. And then there’s the kicker: you’re going to have to build the app twice, once for iOS and once for Android. Yes, we know about cross platform solutions, but they (still) suck.

If you build a solid webapp on the other hand, you’ll serve everyone, including individualists who use Windows Phones and other wonderful contraptions.

In our case, money is not the issue (because we have none) but time is. But the same arguments still apply. As Richard Branson said: “Time is the new money”.

### 2. Developer pain
Making apps is hard. It’s getting easier, but it’s still much harder than making webapps. Quality assurance is an issue, especially on Android due to fragmentation. Making new releases is also a pain, especially on iOS, due to the review process.

When you update a webapp, on the other hand, every user will instantly get the update and probably won’t even realise.

Then there’s the issue of development speed. If you are supporting multiple platforms, you’ll need to roll out features on all of them &mdash; or at least ensure that missing features don’t break the product. This will slow down your product development drastically. Again, this is not an issue if you only have one platform

### 3. Onboarding is rubbish
If you want your product to grow virally then you need to have a really quick onboarding process. This is exactly what Kittysplit currently has: when you’re sent a link to a Kitty it takes 2 clicks to get inside and you’re ready to go. There’s *no way* that any app installation plus identification process could ever be that simple.

Onboarding is probably where we’re strongest compared to the competition (coupled with the fact that users don’t need to register). An app would be a big step backwards for us.

### 4. offline access
OK, here an app wins hands down. Still, consider the fact that being in a situation with zero internet access is becoming rarer with each passing year. When we go on holiday these days we buy a data pack, which was really expensive or not even possible five years ago.

## The verdict
In our case, the verdict is clear: we don't need an app (right now). It makes no sense to greatly slow down our development and exposing our new users to all kinds of onboarding issues for the sake of improving an uncommon scenario.

Of course, there are many cases where an app is the only way to go (photos, location-based background services or anything that relies on sensors or synchronisation). Nonetheless, there are many startups out there, not just our competitors, who would do themselves a huge favor by not putting too much priority on an app &mdash; and maybe making do without one altogether.
