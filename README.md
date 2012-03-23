# Ember Tools

Contains a very alpha and incomplete validation framework and form wizard view with validation integration using the twitter bootstrap css and html format for layout. This has been ported from a small application that was developed in coffeescript so the javascript has been converted automatically at this stage. I'll tidy this up over time.

##Getting started
tbc

##Demos
tbc

##How to build

The build tools and project structure are based largely on Ember.js for consistency and to save me the trouble of getting this setup. Thanks!

1. Install ruby 1.9.2+
2. `gem install bundler`
3. `bundle install`
4. `rake dist`

This will create a number of js files under the 'dist' folder. The easiest one to get started with is ember-tools.js. I'll document to purpose/usage of the others once i've cleaned things up.

##Developing ember-tools with Kicker

The kicker gem aids in developing by detecting changes to the file system and running tasks. The most basic example of this is to run `kicker -e "rake dist"` from the packages directory to rebuild the framework as files are modified.

