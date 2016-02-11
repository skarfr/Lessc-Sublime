Lessc Build System for Sublime Text
===================================

Simple build system for lessc compiler. 

Features
--------
- It's simple!
- Minifies by default using clean-css plugin: `--clean-css="--s1 --advanced --compatibility=ie7"` !
- Generates css source map!
- Build variant for non-minified build (command Build: Non-Minified)

2 versions
----------
- `lessc.sublime-build` will compile your `<filename>.less` into `<filename>.css` within the same working folder. 
- `lessc Drupal Bootstrap.sublime-build` will try to complile the file named `style.less` located in the same working folder as your current file, into `../css/style.css`. 

Requires
--------
- Node.js (lessc) compiler. See [lesscss.org](http://lesscss.org/#using-less "Lessc Install instructions") for install instructions.
- Less plugin clean-css. See https://github.com/less/less-plugin-clean-css for install instructions.