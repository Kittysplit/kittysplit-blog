---
layout: post
title: Goodbye, Ubuntu
---
[Kittysplit](http://www.kittysplit.com/) was made on computers running Ubuntu. The initial backend and the frontend were written on two indestructible Thinkpads which famously run the free operating system perfectly. 

![_config.yml]({{ site.baseurl }}/images/2015-03-goodbye-ubuntu-thinkpad.jpg)

It was only later that Macs entered the developer fray. However, things have changed. Ubuntu is now being retired forever at Kittysplit Towers as a developer OS. Here we list the reasons why.

Admittedly some of theses reasons are not developer specific, but they are worth mentioning because they illustrate why Ubuntu failed in its wider mission to become a "Linux of the people".  

## Too much web developer tool futzing 
Installing all the latest and greatest frontend dev tools does not work out of the box with Ubuntu. Things like Node.js, Bower, SASS and so on need extra PPAs, setting up system-wide  links or using sudo to install what should be user-space libraries. On Mac OSX it works flawlessly using homebrew.

## The installation process is unreliable
It’s true that one of Ubuntu’s early triumphs was making the installation of Linux vastly simpler than everything that came before. But then it seemed like Ubuntu gave up when the task was 90% complete &mdash; a recurring theme. Wubi, a Windows installer with lots of potential, was eventually [discontinued](http://www.omgubuntu.co.uk/2013/04/wubi-advice).

The Ubuntu install process has always been slightly wonky. We would often see the odd error occurring when installing from scratch and, though unsettling, it was never serious. Recently, however, we managed to accidentally wipe the USB stick that the install was actually happening from. How can this be?

It seems that the installation process has gotten more, not less, fragile as time passed.

## Things are too slow
For some reason, logging into the system from the login screen takes up to 10 seconds. We’ve tried switching off various indexing services but it only helped only a little. Speaking of indexing, the Dash search feature is incredibly slow too. Comparing it to OSX Spotlight is like comparing a squashed turnip to an apple and mint smoothie.

Then there’s the Ubuntu Software Center. It takes so long starting up that you get the impression that it’s being compiled from source each time. Whilst it’s basically a really nice idea, it has got “started but not finished” written all over it, like many other Ubuntu-specific things. Of course, a developer uses the command line to install things, but Ubuntu is aimed at the masses, remember?

## The terminal is crappy
The terminal is the one tool that every developer will be using daily, so why was this not improved a long time ago?
Opening up HTTP links takes ages (what’s it compiling this time?). Changing the colour scheme is very well hidden in some sub-settings. Resizing the terminal does not lead to a nice reformatting of output. And, last but not least: the shortcut to paste ist not CTRL+V like in all other apps since the beginning of recorded history, but CTRL+SHIFT+V. Totally baffling. 

## Ubuntu is ugly
Ah, the old “Ubuntu doesn’t look good” chestnut. Of course, beauty is always in the eye of the beholder and just because everyone one else has gone for flat design, doesn’t mean that Ubuntu has to. 

However, the fact is that Ubuntu looks dated. After several promising iterations on the icons and the color scheme, things &mdash; in the true Ubuntu way &mdash; just stopped.

The font-rendering has always been pretty awful (although this could be an eye-of-the-beholder-type thing). And GTK widgets just look bad, especially since on many dialogs they are misaligned.

And whilst we’re on the subject of looks, it’s baffling that the Grub Bootloader was never styled (as it is for other distros). This is the first thing that a user will see when he (dual) boots his machine. It’s the very first impression and the point where the design experience starts. Why give the user the idea he’s been teleported into DOS-world?

## The Amazon search result debacle
It’s fine to make money and to try and monetize your users. But to claim that this feature in any way adds value for the user is just bizarre. Privacy issues aside, how did Ubuntu fail to see that absolutely nobody is going to want to see Amazon products in the search results when they’re actually looking for files and apps. 

## General smell of decay and abandonment
Ubuntu Desktop feels like a ghost town. There have been no exciting features or design improvement in the past 2 years. Looking at [Launchpad](https://launchpad.net/), the project management platform for all things Ubuntu, one sees that the last blog post was [made in 2013](http://blog.launchpad.net/). Addtionally, all of the Ubuntu-specific projects that are featured on the front page appear to be stale or dead. 

A quick peek at Google Trends seems to tell a similar tale.

<script type="text/javascript" src="//www.google.com/trends/embed.js?hl=en-US&q=ubuntu&tz&content=1&cid=TIMESERIES_GRAPH_0&export=5&w=400&h=330"></script>

It seems that Ubuntu has exhausted itself in a string of misadventures,  bad bets and features and policies that annoyed its community. The ones that spring to mind are:  [Ubuntu Edge](http://en.wikipedia.org/wiki/Ubuntu_Edge), [Ubuntu TV](http://www.ubuntu.com/tv), moving the windows buttons, [Wayland vs Mir](http://en.wikipedia.org/wiki/Mir_(software)#Controversy), [Ubuntu one](http://blog.canonical.com/2014/04/02/shutting-down-ubuntu-one-file-services/), [Ubuntu vs Banshee](http://www.zdnet.com/article/shuttleworth-on-the-ubuntu-banshee-controversy-mistakes-were-made/),  and [trademark “abuse”](http://arstechnica.com/information-technology/2013/11/canonical-abused-trademark-law-to-target-a-site-critical-of-ubuntu-privacy/).

People are moving on and so are we. Goodbye Ubuntu. It’s been emotional. (But don't worry, you can still use Kittysplit to [split expenses between friends](http://kittysplit.com).)
