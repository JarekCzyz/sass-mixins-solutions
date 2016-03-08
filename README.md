## Sass @mixins , @function , @extend
<strong>SCSS simple solutions</strong> that are useful every day, the main idea is to make work <strong>easier</strong> and effective.

### Install with Bower

You can install the package using [Bower](http://bower.io/). 

	$ bower install --save-dev sass-mixins-solutions



### Some important mixins:
* [allmq](mixins/_allmq.scss) - globally media queries mixin and special for Iphone /Ipad
* [center element](mixins/_center.scss) - center element in horizontal , vertical in (flexbox , transform or table) 
   - <strong>http://sassmeister.com/gist/1134e7f98f4b31c2b711 </strong>
* [longshadow](mixins/_longshadow.scss) - create longshadow on element
* [multiple](mixins/_multiple.scss) - small mixins (text-overflow, resiable , circle , absolute) in one file
   - <strong> http://sassmeister.com/gist/a884e33f62b2c0536d94</strong>
* [placeholder](mixins/_placeholder.scss) - mixin for placeholder in for example in input form
* [selection](mixins/_selection.scss) - change background and color in selection element in all documents body
* [svgfallback](mixins/_svgfallback.scss) - svg img [svg - png] fallback with modernizr class : inlinesvg , backgroundsize
   - <strong> http://sassmeister.com/gist/a3befa69f426fcbcab7c</strong>
* [transparent](mixins/_transparent.scss) - transparent background-color with fallback in IE9
* [unvisible](mixins/_unvisible.scss) - hide text or hide element without display:none

### Some important function:
* [z-index](functions/_z-index.scss) - organize z-index in array - example ( http://sassmeister.com/gist/cffa96ad7cea70ef5ef7 )


### Some important extended:
* [puregrid](extended/_puregrid.scss) - extended for row and for col class.


### In the future :

* Mixin flexbox grid used with fallback
* Mixin to responsive menu

<hr>
### Special Thanks:
* Rafal Bromirski - mixin _allmq.scss - https://github.com/paranoida/sass-mediaqueries

### License

[The MIT License](LICENSE.md)
