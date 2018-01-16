⚠⚠⚠
**NO LONGER MAINTAINED:** With [every major browser](https://caniuse.com/#search=flexbox) supporting Flexbox now, and tools like [autoprefixer](https://github.com/postcss/autoprefixer) covering this and so much more, I am no longer maintaining this repo (as may already be apparent). Feel free to fork and continue using it if you must, but you should really use Autoprefixer now!
⚠⚠⚠

## Sass flexbox mixin
This is a set of mixins for those who want to mess
around with flexbox using the native support of current
browsers. For full support table check: http://caniuse.com/flexbox

Basically this will use:
- Fallback, old syntax (IE10, mobile webkit browsers - no wrapping)
- Final standards syntax (FF, Safari, Chrome, IE11, Opera)

## Installation
#### Bower

`bower install sass-flex-mixin`

------------------------
This was inspired by: 
- http://dev.opera.com/articles/view/advanced-cross-browser-flexbox/
	
With help from: 
- http://www.w3.org/TR/css3-flexbox/
- http://the-echoplex.net/flexyboxes/
- http://msdn.microsoft.com/en-us/library/ie/hh772069%28v=vs.85%29.aspx

A version compatible with Compass is provided by @trinonsense, on the compass branch.

Licensed under MIT.
