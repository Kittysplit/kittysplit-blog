---
layout: post
title: Chromedriver error on Ubuntu
---
I was seeing the following error when running Chromedriver on Ubuntu:


{% highlight bash%}
/usr/lib/chromium-browser/chromedriver: error while loading shared libraries: libgfx.so: cannot open shared object file: No such file or directory
{% endhighlight %}

This can be fixed by placing the following links
{% highlight bash%}
sudo ln -s /usr/lib/chromium-browser/libs/lib*.so /usr/lib/
{% endhighlight %}


