---
layout: post
title: A super simple way to split-test a call-to-action
---

Split testing is of course a very broad topic with truckloads of tools, frameworks, opinions, caveats, and pitfalls. We’re not going to go into all of that, but describe a very easy methodology for testing a call-to-action using Google Analytics.

![call to action]({{ site.baseurl }}/images/2016-08-call-to-action.png)

In our [product](https://www.kittysplit.com/en/) we have a link which leads to a share dialog and the option to donate some money to our cause. Naturally, we want people to click on this link, so we decided to test which text will get the most clicks.


Here’s how we setup the test:

1. We created a list of candidates for the call-to-action and pick one at random to display. This is literally 3 lines of code on the server side.
2. When the link (or button) is clicked on, we send an event to Google Analytics with the call-to-action as a label.
3. That's it!

If you use the excellent [Autotrack library](https://analytics.googleblog.com/2016/02/introducing-autotrack-for-analyticsjs.html), then you don’t even need to write javascript to track the event. For us, the HTML looks like this:

`<a href="#" data-event-category="UI" data-event-action="share link" data-event-label="You owe us a hug!" >a hug!</a>`

Setting up the whole thing should not take more than 30mins. By the way, instead of testing texts, you could also test colors and send the color code as label.

You can then fetch the data directly from Google Analytics. Here’s the results of our test:

![test results]({{ site.baseurl }}/images/2016-08-test-results.png)

As you can see, the winner is almost twice as likely to be clicked on as the next candidate. That’s pretty good data for such a “cheap” test!
