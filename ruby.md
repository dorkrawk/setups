# Set Up Your Computer To Do Some Ruby

## Assumptions / Caveats

* You're running a fairly recent version of MacOS
* There are other ways to do this, but this way is pretty good
* You can use the command line (Terminal or iTerm2 etc.)

## Install Homebrew

[Homebrew](https://brew.sh/) is a package manager, useful for installing software on MacOS.

run this:
```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
## Install rbenv

[rbenv](https://github.com/rbenv/rbenv) helps you manage your Ruby versions and makes it easier to not use the version of Ruby that comes with the OS (which is usually out of date)

we'll install rbenv via Homebrew:
```
brew install rbenv
rbenv init
```

**Now close your terminal and open up a new window/tab to make sure the changes take effect.**

see https://github.com/rbenv/rbenv#homebrew-on-macos for more details

## Install Ruby

We'll install Ruby via rbenv (more details here: https://github.com/rbenv/rbenv#installing-ruby-versions). We're installing version **2.7.1** as that is the current version on my laptop at the time of writing.  Then we'll install [Bundler](https://bundler.io/) to help manage our Gems.

```
rbenv install 2.7.1
ruby --version # check to make sure it says 2.7.1.something
gem install bundler
```
