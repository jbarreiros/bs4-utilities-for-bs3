# Bootstrap 4's Utility Classes for Bootstrap 3

Backports Bootstrap 4's awesome [utility/helper classes](https://getbootstrap.com/docs/4.0/utilities) for use in your Bootstrap 3 project.

## Using

* Install with [npm](https://www.npmjs.com/): `npm install bs4-utilities-for-bs3`
* CSS only
  * `<link rel="stylesheet" href="dist/css/bs4-utilities-for-bs3.css">`
* Import SASS
  * `@import 'node_modules/bs4-utilities-for-bs3/src/bs4-utilities-for-bs3'`
  * Tip: Avoid specifying "node_modules/" in the path by using the [includePaths option](https://github.com/sass/node-sass#includepaths).

## Reference

* [Bootstrap 3 classes](http://getbootstrap.com/css/#helper-classes)
* [Bootstrap 4 classes](https://getbootstrap.com/docs/4.0/utilities)

#### Spacing

BS4 size | BS3 size | Notes
:-------- |:-------- |:-----
1 | xs | Ex: `.mt-1` for `margin-top: $padding-xs-vertical;`
2 | sm | Ex: `.ml-2` for `margin-left: $padding-sm-horizontal;`
3 | _default_ | Ex: `.pt-3` for `padding-top: $padding-base-vertical;`
4 | lg | Ex: `.pl-4` for `padding-left: $padding-lg-horizontal;`
5 | NA | BS3 doesn't have an equivalent size.

#### Utilities deprecated/removed in BS4

BS3 Class | Notes
:----- | -----
`.caret` | Not available in BS4
`.center-block` | Same as `.mx-auto`
`.show` | Same as `.d-(inline\|block\|etc)`
`.hide` | Same as `.d-none`
`.pull-left` | Same as `.float-left`
`.pull-right` | Same as `.float-right`
`.visible-*`, `.hidden-*` | Replaced by `.d-*` utilities
