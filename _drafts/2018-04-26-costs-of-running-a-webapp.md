---
layout: post
title: How much does it cost to run a webapp?
---
How much does running a webapp like [Kittysplit](https://kittysplit.com) actually cost? Maybe more than you think.

<div style="width:100%;height:0;padding-bottom:74%;position:relative;"><iframe src="https://giphy.com/embed/l0HFkA6omUyjVYqw8" width="100%" height="100%" style="position:absolute" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div><p><a href="https://giphy.com/gifs/baby-money-little-rascals-l0HFkA6omUyjVYqw8">via GIPHY</a></p>

Here's a monthly breakdown:

* 65 USD for running the servers. We have 2 servers hosted on Digital Ocean, one running the app and one running the database.
* 9 USD for hosting our code on GitHub.
* 4 USD for storing our database backups on Amazon S3.
* 10 USD for using Sendgrid to send emails.
* 20 USD for Bugsnag for error reporting and monitoring.
* 7 USD for Papertrail which is a cloud logging services.

In total that's **115 USD or 95 EUR**. Of course, not included in this the time we invest, office space, Internet, snacks or whiskey. And to be honest, the time we invest is the biggest cost by a very long way.

So how much money do we make? That's an excellent question. The vague answer is "not a lot", but we'll illuminate that in another post.
