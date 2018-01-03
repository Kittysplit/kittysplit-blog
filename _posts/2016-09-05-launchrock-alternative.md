---
layout: post
title: We rolled our own Launchrock
---

We did not have a good experience with Launchrock. It failed at almost the exact
moment when a PR opportunity came through, meaning that potential users ended up
seeing an error page instead a signup form.

Also, quite frankly, Launchrock as a product feels unfinished. It's UI is pretty creaky in places and the whole thing feels slow.

![Launchrock alternative]({{ site.baseurl }}/images/2016-09-landing.png)

But instead of complaining (and paying our Launchrock subscription), we built our own solution using Python Flask. It gets by with a file-based SQLite database, which is absolutely adequate for 99% of all scenarios. It also offers i18n, which Launchrock didn't have.

Here's the code on [GitHub](https://github.com/trsc/flask-landingpage).
