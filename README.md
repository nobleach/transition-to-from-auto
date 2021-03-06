[![view on npm](http://img.shields.io/npm/v/transition-to-from-auto.svg)](https://www.npmjs.org/package/transition-to-from-auto)
[![npm module downloads per month](http://img.shields.io/npm/dm/transition-to-from-auto.svg)](https://www.npmjs.org/package/transition-to-from-auto)
[![Dependency Status](https://david-dm.org/75lb/transition-to-from-auto.svg)](https://david-dm.org/75lb/transition-to-from-auto)

#transition-to-from-auto
This module exports a single function to transition an element either to or from `auto`. At the moment, this is not possible (see [webkit](https://bugs.webkit.org/show_bug.cgi?id=16020) and [firefox](https://bugzilla.mozilla.org/show_bug.cgi?id=571344) bugs).

[Demo](http://75lb.github.io/transition-to-from-auto/).

Compatible with CommonJS (browserify), AMD (requirejs) or plain JS. 

##Synopsis
```js
transition({
  selector: "p",
  property: "height",
  style: "height 0.4s ease-in-out",
  to: "auto"
});
```

##Install
```sh
$ npm install transition-to-from-auto --save
```
or 
```sh
$ bower install transition-to-from-auto --save
```
*Mac / Linux users may need to run with `sudo`*.

##Usage
See the [example](https://github.com/75lb/transition-to-from-auto/tree/master/example) folder for examples.

##API
<a name="exp_module_transition-to-from-auto"></a>
##transition(options) ⏏
transition to and from auto

**Params**

- options `Object` - the options  
  - selector `string` - the element selector  
  - to `string` - the value to transition to  
  - \[property\] `string` - the CSS property to transition, defaults to `width`  
  - \[style\] `string` - the CSS transition style, defaults to `all 0.4s ease-in-out`  



*documented by [jsdoc-to-markdown](https://github.com/75lb/jsdoc-to-markdown)*
