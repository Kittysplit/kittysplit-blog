# The Kittysplit Blog

The blog is generated using http://jekyllrb.com/. This repo was forked from https://github.com/jekyll/jekyll

## Deploying
The blog is hosted on github using project pages (in the `gh-pages` branch)

1. `jekyll b`
2. `git commit -am "Regenerated blog"`
2. `git push`
3. `git subtree push --prefix _site/ origin gh-pages`

## Installing on Ubuntu
1. Install Ruby Version > 2: http://stackoverflow.com/questions/26595620/how-to-install-ruby-2-1-4-on-ubuntu-14-04
1. `sudo apt-get install ruby ruby-dev make gcc nodejs`
2. `gem install jekyll github-pages --no-rdoc --no-ri` (note no `sudo`!)
