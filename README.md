# GetEmPixels

Allows you to accurately obtain an element’s em value in pixels using JavaScript. No more blindly dividing by hard-coded values.

* Author: Tyson Matanich - http://matanich.com
* License: MIT

## The basics

GetEmPixels is simple to use and has only one function.

```javascript
// Get the em or rem value of the documentElement
getEmPixels();

// Get the em value of the #footer element
getEmPixels(document.getElementById('footer'));
```

## Size and delivery

Currently, `getEmPixels.js` compresses to around 481 bytes (~0.47 KB) after minify. To minify, you might try these online tools: [Microsoft Ajax Minifier]:(http://ajaxmin.codeplex.com/), [Uglify]:(http://marijnhaverbeke.nl/uglifyjs), [Yahoo Compressor]:(http://refresh-sf.com/yui/), or [Closure Compiler](http://closure-compiler.appspot.com/home).

## Support

GetEmPixels supports a broad range of browsers and devices (there are currently no known unsupported browsers).