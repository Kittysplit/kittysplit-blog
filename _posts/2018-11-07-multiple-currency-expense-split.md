---
layout: post
title: Multiple currencies in one Kitty
---

You know the feeling when someone's telling a story that involves the cost of something in a foreign currency? "Can you believe that a sandwich costs 25 doubloons over there!" and they expect you to not only know the exchange rate but to do the conversion in your head. We find it annoying when that happens and sadly it's a problem that our newly released feature doesn't solve.

Instead, this new feature will make it much simpler to go on these types of international trips and track all costs in the native currency! That's almost almost as good, we feel.

![Splitting costs]({{ site.baseurl }}/images/2018-11-currencies.jpg 'Different currencies')

## Euros, Pounds, Yen, Krona, Doubloons, BitCoin

Now you can enter expenses into [Kittysplit](https://kittysplit.com) in any currency you want and we'll convert it back to your "home" currency (this is the currency you specify when creating the Kitty). It really is that simple.

In the background of course, things are slightly more complex. We fetch the exchange rates from [Fixer.io](https://fixer.io/), a simple and lightweight API for current and historical foreign exchange (forex) rates. To make it as fair as possible, we fetch the exchange rate for the given date of the expense, which we feel is rather smart 🤓. Editing an expense will only change the rate if the date changes too. We keep the most current rates for all currencies and a refresh every 12-24 hours.

## One more thing

Currency conversion is only available in [super Kitties](/kittysplit-premium-features/). This makes the small fee invested to upgrade your Kitty all the more worth it! Remember, when you pay for the upgrade we will automatically add the cost to your Kitty, meaning you'll hardly notice it.


## More goodies are on the way! 🎁

We are currently working on a bunch of other things that we’ll be launching within the next few months. Do give us feedback and let us know what you think.
