# Skelly SCSS

Skelly is an opinionated enhancement to [Skeleton-Sass](https://github.com/WhatsNewSaes/Skeleton-Sass), which is the (un)official Sass version of [Dave Gamache's](https://twitter.com/dhg) [Skeleton](http://getskeleton.com) Framework.

-----

Skeleton is a simple, responsive boilerplate to kickstart any responsive project.

Skelly ... kind of makes things more complicated. (In a good way though!)

## Getting started

### Install Global Dependancies
  * [Node.js](http://nodejs.org)
  * [bower](http://bower.io): `[sudo] npm install bower -g`
  * [grunt.js](http://gruntjs.com): `[sudo] npm install -g grunt-cli`

### Install Local Dependancies
  * [Download zip](https://github.com/sdougbrown/skelly-scss/archive/master.zip), [clone the repo](github-mac://openRepo/https://github.com/sdougbrown/skelly-scss) or `bower install skelly-scss` from your terminal
  * cd to project folder
  * run `[sudo] npm install` (first time users)
  * run `grunt` (to watch and compile sass files)

### What's in the download?

The download includes Skelly's CSS, ~~Normalize CSS as a reset,~~ a sample favicon, an index.html as a starting point, and a demo.html to see how some classes and objects are meant to be used.

```
skeleton/
├── index.html
├── scss/
│   └── skelly.scss
├── images/
│   └── favicon.png
├── package.json
├── Gruntfile.js
└── README.md

```
### Using Skelly

You could just include `skelly.scss` and be done, if you like.  What you'll probably find more useful, though, is to include only the files that you *actually want or need*.

Note that before you import any skelly files you should be sure to include the `settings` and `mixins/_main` file.  You'll probably want to include Skelly's `settings` after your own vars/settings file in order to override the defaults set therein so that your whole project matches up a bit better.

### Contributions

This is a fork of the original work.  I'm happy to accept input, but I've primarially made adjustments to fit my own style and preferences, so I'm going to have to agree with you philosophically in order to merge your PR. :)

### Why it's awesome

Skeleton is lightweight and simple. It styles only raw HTML elements (with a few exceptions).

Skeleton provided an ideal starting point for something a little more... interesting.

Skelly adjusts some of the class names utilized with a more opinionated style, while trying to stay just as small so that it gets out of your way.  Skelly also attempts to normalize more browser behaviour than Skeleton did.

Additionally, Skelly includes a **totally re-written, mobile-first, ultra-responsive grid**, and **media shortcuts via mixins**.

- Minified, it's less than a kb
- It's a starting point, not a UI framework


## License

All parts of Skelly are free to use and abuse under the [open-source MIT license](http://opensource.org/licenses/mit-license.php).


## Colophon

Skeleton was built using [Sublime Text 3](http://www.sublimetext.com/3) and designed with [Sketch](http://bohemiancoding.com/sketch). The typeface [Raleway](http://www.google.com/fonts/specimen/Raleway) was created by [Matt McInerney](http://matt.cc/) and [Pablo Impallari](http://www.impallari.com/). Code highlighting by Google's [Prettify library](https://code.google.com/p/google-code-prettify/). Icons in the header of the documentation are all derivative work of icons from [The Noun Project](thenounproject.com). [Feather](http://thenounproject.com/term/feather/22073) by Zach VanDeHey, [Pen](http://thenounproject.com/term/pen/21163) (with cap) by Ed Harrison, [Pen](http://thenounproject.com/term/pen/32847) (with clicker) by Matthew Hall, and [Watch](http://thenounproject.com/term/watch/48015) by Julien Deveaux.


## Acknowledgement

Skeleton was created by [Dave Gamache](https://twitter.com/dhg) for a better web.

Skeleton-Sass was created by [Seth Coelen](http://sethcoelen.com) for a better Skeleton.

Skelly was created by [Doug Brown](http://douggo.com) because it's the name of a bone. (And for CSS stuff).
