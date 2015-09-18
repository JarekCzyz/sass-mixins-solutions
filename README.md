## Sass @mixins , @function , @extend

#### Some important mixins:
* [allmq](mixins/_allmq.scss) - globally media queries mixin and Iphone
* [svgfallback](mixins/_svgfallback.scss) - svg img [svg - png] fallback with modernizr class : inlinesvg , backgroundsize

#### Some important function:
* [z-index](functions/_z-index.scss) - z-index in one place - example ( http://sassmeister.com/gist/cffa96ad7cea70ef5ef7 )

#### Some important extended:
* [puregrid](extended/_puregrid.scss) - extended for row and for col class.


#### Install with Bower

You can install the package using [Bower](http://bower.io/). Please run

	$ bower install --save-dev sass-mixins-solutions

in your project's root directory to install the mixins repository. After that
you can require the mixins file within your project.

#### In the future :

* Mixin flexbox grid used with fallback
* Mixin to responsive menu

### Special Thanks:
* Rafal Bromirski - mixin _allmq.scss - https://github.com/paranoida/sass-mediaqueries

### License

[The MIT License](LICENSE.md)