# The Kittysplit Blog

This was forked from https://github.com/jekyll/jekyll

Installing Jekyll on Ubuntu: http://michaelchelen.net/81fa/install-jekyll-2-ubuntu-14-04/

To build and serve locally: `jekyll serve --watch`

## Deploying
```
TARGET=/home/wrede/repos/kittysplit/src/main/webapp/blog
jekyll build $TARGET
```
alternatively
`cp -R _site/* /home/wrede/repos/kittysplit/src/main/webapp/blog`
