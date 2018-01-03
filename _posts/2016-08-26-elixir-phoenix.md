---
layout: post
title: Rebuilding Kittysplit with Elixir and Phoenix
---

Last year we completely rewrote Kittysplit in Elixir and with the Phoenix Framework. Here’s a brief summary of what we learned and why we did it.

## Version 1: Google App Engine
The first version of Kittysplit consisted of a Java backend running on Google App Engine (GAE) and a Javascript frontend (you can still reach it [here](http://old.kittysplit.com/)). GAE, a Platform as a Service, comes with a lot of goodies already baked in, such as a noSQL datastore and automatic scaling of your application. They have a free tier which we quickly left behind, but it turned out that the hosting costs were peanuts (a few dollars a month).

![_config.yml]({{ site.baseurl }}/images/2016-08-gae.png)

The frontend consisted of hand-crafted Javascript which made do without any kind of framework, the main reason being that our frontend guys had absolutely zero framework experience at the time.

These choices were great for getting started quickly and we launched our MVP without a hitch. However, a year later after lots of great feedback and increasing traction it became clear we needed something new for 2 main reasons:

1. Google App Engine only supports Servlet API 2.5, which is ancient. The fact that Google [ignores requests to support API 3+](https://code.google.com/p/googleappengine/issues/detail?id=3091) is seen by some as the writing on the wall for Java support on GAE.
2. Providing a Javascript web app in more than one language is a big royal pain. It is possible to do internationalization on the frontend but it’s much easier when it’s done server-side.

So, despite many smart people claiming that you should [never rewrite something from scratch](http://www.joelonsoftware.com/articles/fog0000000069.html), we decided to go ahead and do it anyway. It turned out to be a big success, partially because we didn’t migrate the old data.

## Version 2: Enter Elixir and Phoenix
The decision to go with Phoenix/Elixir was not motivated by any deep-seated conviction that this was going to be The Great Leap Forward. It was more a healthy curiosity for an interesting new project.  We had heard the buzz building in the distance and we felt like getting our hands dirty.

![Phoenix Logo]({{ site.baseurl }}/images/2016-08-phoenix.png)

The rewrite of Kittysplit began in January 2015 and we had the first working prototype a week later. We had a feature-complete beta version in March and released to production in May. Overall, it was a flawless experience. It would have been even quicker if we hadn’t added some new features and redesigned the app in the process. We also translated everything, added ridiculous-mode [test coverage](https://cucumber.io/) and created an awesome [build pipeline](https://jenkins.io/).

When we began development, both Elixir and Phoenix had not had their final initial releases but this was not a problem at all. Their creators, [José Valim](https://twitter.com/josevalim) and [Chris McCord](https://twitter.com/chris_mccord), were both available on IRC and very helpful and friendly.

## Performance
The performance of Elixir and Phoenix is spectacular. We haven’t done any benchmarking but the application is now clearly much more responsive, something that our users have actively noticed. And this despite the fact that our app went from being client-side to server-side!

We currently run Kittysplit on 2 very moderately sized [Digital Ocean](https://www.digitalocean.com/?refcode=b300ef2a9cbc) virtual servers, which do the job of serving 2.000 users and 10.000 page-views per day without breaking a sweat. They are both 2 GB, 2 CPU machines with a 40 GB SSD. Due to their light-weight specs we even sometimes refer to them as toasters.

![A really nice toaster]({{ site.baseurl }}/images/2016-08-toaster.jpg)

## Overall
We are very happy with the choice we made and have learned a bunch. Sadly we haven’t required channels yet but we’ll find a feature that needs them soon enough (aka developer-candy-driven development).
