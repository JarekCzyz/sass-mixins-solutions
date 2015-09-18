## Sass @mixins , @function , @extend
SCSS simple solutions that are useful every day, the main idea is to make work easier and effective.

### Install with Bower

You can install the package using [Bower](http://bower.io/). 

	$ bower install --save-dev sass-mixins-solutions



#### Some important mixins:
* [allmq](mixins/_allmq.scss) - globally media queries mixin and special for Iphone /Ipad
* [center element](mixins/_center.scss) - center element in horizontal , vertical in (flexbox , transform or table)
* [longshadow](mixins/_longshadow.scss) - create longshadow on element
* [placeholder](mixins/_placeholder.scss) - mixin for placeholder in for example in input form
* [selection](mixins/_selection.scss) - change background and color in selection element in all documents body
* [svgfallback](mixins/_svgfallback.scss) - svg img [svg - png] fallback with modernizr class : inlinesvg , backgroundsize
* [transparent](mixins/_transparent.scss) - transparent background-color with fallback in IE9
* [unvisible](mixins/_unvisible.scss) - hide text or hide element without display:none

#### Some important function:
* [z-index](functions/_z-index.scss) - z-index in one place - example ( http://sassmeister.com/gist/cffa96ad7cea70ef5ef7 )


#### Some important extended:
* [puregrid](extended/_puregrid.scss) - extended for row and for col class.


### In the future :

* Mixin flexbox grid used with fallback
* Mixin to responsive menu

<hr>
### Special Thanks:
* Rafal Bromirski - mixin _allmq.scss - https://github.com/paranoida/sass-mediaqueries

### License

[The MIT License](LICENSE.md)
