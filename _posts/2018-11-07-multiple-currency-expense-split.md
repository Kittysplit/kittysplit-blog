---
layout: post
title: Multiple currencies in our bill-splitting app
description: "We offer a bill-splitting app for those situations where you're travelling in multiple counties. Kittysplit is the perfect solution for these scenarios. Find out more!"
---

You know the feeling when someone's telling a story that involves the cost of something in a foreign currency? "Can you believe that a sandwich costs 25 doubloons over there!" and they expect you to not only know the exchange rate but to do the conversion in your head. We find it annoying when that happens and sadly it's a problem that the newly released feature for [Kittysplit](https://kittysplit.com) doesn't solve.

Instead, this new feature will make it much simpler to go on these types of international trips and track all costs in the native currency! That's almost almost as good, we feel.

![Splitting costs](/images/2018-11-currencies.jpg 'Different currencies')

## Travel expenses simplified: Euros, Pounds, Yen, Krona, Doubloons, BitCoin

Now you can enter expenses into [Kittysplit](https://kittysplit.com) in any currency you want and we'll convert it back to your "home" currency (this is the currency you specify when creating the Kitty). It really is that simple.

In the background of course, things are slightly more complex. We fetch the exchange rates from [Fixer.io](https://fixer.io/), a simple and lightweight API for current and historical foreign exchange (forex) rates. To make it as fair as possible, we fetch the exchange rate for the given date of the expense, which we feel is rather smart 🤓. Editing an expense will only change the rate if the date changes too. We keep the most current rates for all currencies and a refresh every 12-24 hours.

![Splitting costs](/images/en_screen_collage.png 'Different currencies')

This means that when you next go on a trip with a bunch of friends, it will be much easier to track costs and split them amongst everyone. Kittysplit doesn't even require registration (no password, no email, no hassle).

We've been on many many trips abroad and Kittysplit is always the first thing we tick off when packing our suitcase. Because of this, our trips have been much more harmonious.

## One more thing

Currency conversion is only available in [super Kitties](/kittysplit-premium-features/). This makes the small fee invested to upgrade your Kitty all the more worth it! Remember, when you pay for the upgrade we will automatically add the cost to your Kitty, meaning you'll hardly notice it.

<div class="text-center">
<br>
<a href="https://kittysplit.com/en/new" class="btn btn-lg btn-primary btn-start" >Try Kittysplit now!</a>
<br><br>
</div>

## More goodies are on the way! 🎁

We are currently working on a bunch of other things that we’ll be launching within the next few months. Do give us feedback and let us know what you think.
