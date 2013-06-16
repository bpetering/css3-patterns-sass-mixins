css3-patterns-sass-mixins
=========================

CSS3 Patterns (http://lea.verou.me/css3patterns/) converted to Sass mixins, with customizable colors and sizes.


Demo
----

Look here.


Quick start
-----------

1. Copy _css3-pattern-mixins.scss into your SCSS library folder

2. Include the mixin file like normal in your main Sass scripts:

    @include "css3-pattern-mixins";

3. When styling an element that can have a background: set, include
   the mixin (and optionally specify colors and sizes):

    .some-element {
        @include japanese-cube();
    }
    .other-element {
        @include carbon(#424242)
    }

4. Profit.
