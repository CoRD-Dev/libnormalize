[![normalize](http://goo.gl/oBQ1Ed)](http://necolas.github.com/normalize.css/)

Modularized and [Sassy](http://sass-lang.com/) [normalize.css](http://necolas.github.com/normalize.css/).

##Installation

Install [SASS](http://sass-lang.com/).

`cd` to your projects local repository and run:

```bash
git submodule add https://github.com/CoRD-Dev/libnormalize.git sass/normalize
```
(`sass/normalize` should be the directory your sass/scss files are kept +/normalize.)

The generated folder will contain all normalizes files.

Import normalize before any other stylesheets:

```scss
@import "normalize/normalize";

// All other imports
```


##Credits
Normalize.css is a project by [Nicolas Gallagher](https://github.com/necolas),
co-created with [Jonathan Neal](https://github.com/jonathantneal).

Normalize.scss was created by [Kyo Nagashima](https://github.com/hail2u).

libnormalize is maintained by [CoRD](http://cord-dev.github.io/) and [The_Catman](http://catmanix.github.io/).

##License
Normalize.css is Copyright © 2011-2013 Nicolas Gallagher and Jonathan Neal. It is free software, and may be redistributed under the terms specified in the LICENSE file.
