# Generator-stylish
[![Build Status](https://secure.travis-ci.org/srsgores/generator-stylish.png?branch=master)](https://travis-ci.org/srsgores/generator-stylish)

A [stylish](http://userstyles.org/) generator for Yeoman.  Allows you to easily start creating a custom theme for any
 website of your choosing.

## Getting started
1. Make sure you have [yo](https://github.com/yeoman/yo) installed: `npm install -g yo`
2. Install the generator: `npm install -g generator-stylish`
3. Run: `yo stylish`
4. Follow the prompts, inserting your user information as needed

## Why It's Awesome
* Variable names are auto-generated to match the project name.  All variables are prefixed with the project name.
This is great for auto-completion (in PHPStorm, WebStorm, SublimeText 2/3, most modern IDEs)
* Author snippet at the beginning of each file with timestamp, copyright, package name,
and description
* Scaffolds out SCSS helpers based off of my [sass boilerplate](https://github.com/srsgores/sass-boilerplate).
Allows for leaner, better CSS.  Optionally includes animation mixins and helpers.

## License
[MIT License](http://en.wikipedia.org/wiki/MIT_License)
