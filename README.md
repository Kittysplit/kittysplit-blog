# The Kittysplit Blog

The blog is generated using http://jekyllrb.com/. This repo was forked from https://github.com/jekyll/jekyll

To build and serve locally: `jekyll serve --watch`

## Deploying
Change the output directory as appropriate
```
jekyll build -d /home/wrede/repos/kittysplit/src/main/webapp/blog
```
alternatively
`cp -R _site/* /home/wrede/repos/kittysplit/src/main/webapp/blog`

## Installing on Ubuntu
1. ```sudo apt-get install ruby ruby-dev make gcc nodejs```
2. ```sudo gem install jekyll --no-rdoc --no-ri```

