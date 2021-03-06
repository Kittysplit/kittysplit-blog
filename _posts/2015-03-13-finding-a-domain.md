---
layout: post
title: We found our domain name using Python
---
Finding a name for your startup is never easy. Many requirements must be met. A name should not be too generic, yet it should somehow convey an idea of what your company is about. You also need to be confident that it doesn't describe an obscure sexual practice in a foreign language. On top of that, you need to ensure that the domain name is free for a sensible top-level domain.

We found our domain name ([kittysplit.com](http://kittysplit.com)) using a simple Python script.

![Python running in terminal]({{ site.baseurl }}/images/2015_03_python.png)

It generates domain names from text building blocks and then checks if they are free. Because this script uses the system ``whois`` command, it will (probably) only run on Linux.

You can try it for yourself. Here's what you need to do.

## 1. Checkout the code
This bit is quite easy

```git clone git@github.com:caspii/domainfinder.git```

## 2. Create your own building blocks
This bit is also quite easy.

Open the file ``input.txt`` in your favorite text editor. You'll see that it contains a section called "--prefixes" and one called "--suffixes". Simply edit these sections as you see fit, taking care not to delete the actual section titles.

The python script will take each prefix, combine it with every suffix and then check if the resulting .com domain is free. For example, if you only have the prefix "ilove" and the two suffixes, "money" and "myself", then the script will check if the following domains are free:

* ilovemoney.com
* iloveymyself.com


## 3. Run the script
This is the easiest bit.

Run the command ``./find.py`` and the script will take the inputs you specified in step 2 and begin checking which domains are free.

## 4. Rejoice
You'll see the output as each domain is checked and the result in your console. All free domains are saved into a file called ``output.txt`` for later perusal.

## Tweak
If you're feeling adventurous, change the script so that other top level domains are checked, such as .net or .de.
