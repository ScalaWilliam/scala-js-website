# Website for Scala.js

This is the source code for the Scala.js website at
[http://www.scala-js.org/](http://www.scala-js.org/).

If you intended to look at the Scala.js source code itself,
you can find it here: [github.com/scala-js/scala-js](https://github.com/scala-js/scala-js).

# Contributing

The key to contributing is being able to edit and
preview your content. [Your pull requests are welcome](https://github.com/scala-js/scala-js-website/compare)!

## Set up
As this website is built with [Jekyll](http://jekyllrb.com/),
we will need to set up some Ruby tooling.

First, install RVM (Ruby Version Manager): https://rvm.io/rvm/install
Then run the following commands:
```bash
$ source ~/.rvm/scripts/rvm
# Use Ruby 2.2.3
$ rvm use 2.2.3 --install --fuzzy
# Set up Bundler, a Ruby package manager
# It downloads dependencies specified in a Gemfile
# but into a local path unlike gem 
$ gem install bundler
# Install dependencies such as Jekyll and its plugins
$ bundle install
# Test run of page build
$ bundle exec jekyll build
```

## Editing live
This is what you would do after initial installation:
```bash
$ source ~/.rvm/scripts/rvm; rvm use 2.2.3
$ bundle exec jekyll serve
```
