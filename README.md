##Forked from ericelliott / h5Validate 0.9.1 and modified by coupeez

August 20 2015
version 0.1.0

 - support commonJS/NPM style module loader.
 - require('jquery'); expected to be installed in node_modules
 - Rename library main file: jquery.h5Vlaidate.js -> h5Validate.js
 - Include main: property in package.json in support of commonJS

# <a href="https://github.com/ericelliott/h5Validate">h5Validate</a>

Hi,

I'm Eric Elliott, author of ["Programming JavaScript Applications" (O'Reilly)](http://pjabook.com). A few years ago, I wrote this jQuery plugin that understands HTML5 forms and knows how to validate them, even in browsers that don't yet support HTML5.

In browsers that do support HTML5, h5Validate adds some much-needed features, such as the ability to customize the user interface when an input fails validation.

For demo and usage, see <a href="https://github.com/ericelliott/h5Validate">the h5Validate homepage</a>.

## Status

A lot has changed since I wrote this library in 2010. So much, in fact, that I've started a new project based on the great work we did here. It's called [h5v2](https://github.com/ericelliott/h5v2). It's brand new, we haven't even ported the unit tests, yet.

Wouldn't you like a library like h5Validate written to work with node-style modules, Browserify, and web components? I'd love your help. [Take a look at the issues and contribute!](https://github.com/ericelliott/h5v2/issues)
