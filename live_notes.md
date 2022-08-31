0-2:

# 1:

* I like how although we focus on thinking about rails when we get into this, this gives us a good gem authoring foundation
which I think is sorely lacking in the ruby community
* Version 0.0.1 is a good shout I think. it allows you to iterate through three tiers of breaking changes
* Love this quote
>  Repeating that technique will get it in your fingers. It’s always good to know the
> simplest way to do a task -- you can fall back to it when clever
> tricks aren’t working.
* Github copilot really is doing some helping here. My initial config.ru was autocompleted 😂
* I love that we're using Rack raw here as well. Nearly every imaginable ruby web framework has Rack as a dependency so
mastery of that allows you to jump off however you imagine.
* I've found it best to have a "rebuilding_rails" directory containing:
  1. rulers gem
  2. any applications I want to use it
  3. my notes
* Did anyone diverge?
* nice to keep a copy of rails/rails open. found myself looking through all the rails command options
* was two chapters too much? shall we try one next time?
> When the various conveniences fail, you’ll know how to do it the old-fashioned way
* Because of rails autoloading prowess the last 19 years and the fact that people don't often author their own gems; are
a lot of rubyists weaker at correctly "requiring" things? (thought about this while using require)
* Super neat how the gem is using git to generate its `spec.files`
* that is wild how you can just use unicorn, puma, thin, etc. as a drop in for rackup on config.ru. so simple!


# 2:

* const_get "ruby magic"
* a little quicker, but very rich on the meat
* how did you do your error rendering? I found that unicorn complained about rendering it to the browser but rackup
went swimmingly!***
* I got redirect working! and default pages (show it off)***
* optional: go through my reading the file, couldn't get the file reading quite right and maybe a blindspot is raw file
loading and reading
