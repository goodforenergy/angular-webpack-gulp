# Welcome

Hello, and welcome to a new approach for variable management. This app uses Angular, Jquery and Sass, and utilises a number of other tools to support ease of development:

* Gulp - a stream based JS task runner, for building
* Webpack - module support
* Node / npm - for dependency management
* Compass - support for Sass

# To Run

* Install the pre-requisites listed below
* Run `npm install` inside the top level directory to grab dependencies
* ???

## Pre-Requisites

On OS X you're recommended to increase the [ulimit](http://superuser.com/a/443168/6877) as it's ridiculously low by default. Use `ulimit -S -n 2048`.

### Node

If you don't already have it installed, install Node. If you use homebrew, you can install using

	brew install node

Otherwise, you can download and install from [here](http://nodejs.org/download/).

### Gulp

Gulp must be installed globally in order to use the command line tools.

	npm install -g gulp

# Building

This project is built using Gulp, a JavaScript task runner.

## Pre-Requisites

In addition to Node and Gulp, you will need the following:

### Ruby

I recommend installing Ruby using RVM. Even if your system comes with Ruby (I'm looking at you OSX) it is often preferable to have a user installation that will allow the installation of gems without the need for `sudo`. Install RVM and Ruby using

	\curl -sSL https://get.rvm.io | bash -s stable --ruby

`ruby -v` will now tell you which version of Ruby you are using. Check out the [RVM docs](http://rvm.io/rvm/basics) to read how to switch between Ruby versions.

### Compass

If you don't already have Compass installed, install using:

	gem update --system
	gem install compass

### Install npm dependencies

	npm install

This runs through all dependencies listed in `package.json` and downloads them to a `node_modules` folder in your project directory.
