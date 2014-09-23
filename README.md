Hackfodlr customized for CODE4HK
============
[![Build Status](https://travis-ci.org/code4hk/hackfoldr-2.0.svg?branch=master)](https://travis-ci.org/code4hk/hackfoldr-2.0)

Thanks g0vTW!!!!

Using:
* Sass
* Compass
* Semantic UI
* Jade
* jQuery
* Handlebars
* Tabletop
* Fire.app or gulp.js

Development
------------

* development on master branch
* deploy on gh-pages branch (It would auto deploy via travis-ci. You only commit on master branch and push.)

### Fire.app for development
* development:
    * using Fire.app to watch .jade and .sass
    * using Github for Windows or git on linux to sync and commit

### Gulp.js for development
* pre-dev:
    * install: [node](http://nodejs.org/)
    * install: ruby 2.0.0 (use [rubyuinstaller](http://rubyinstaller.org) on windows, use `rvm install 2.0.0` on linux/mac)
    * install sass (`gem install sass --version "3.3.3"`)
    * install compass (`gem install compass --version "1.0.0.alpha.19"`)
    * `npm i`
* devlopment:
    * `npm run build` (1st time to create `_public` folder)
    * `npm start`
    * open `http://localhost:3000/` to see the result.


Mockup / Prototype
------------

http://hack.etblue.tw/

License
------------

Same as hackfoldr
