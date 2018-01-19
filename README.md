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

#### All the Things

Class | BS3 | Notes
:----- |:---:|:-----
`.border` ||
`.border-top` ||
`.border-right` ||
`.border-bottom` ||
`.border-left` ||
`.border-0` ||
`.border-top-0` ||
`.border-right-0` ||
`.border-bottom-0` ||
`.border-left-0` ||
`.border-primary` ||
`.border-secondary` || Not ported. Uses color only available in BS4.
`.border-success` ||
`.border-danger` ||
`.border-warning` ||
`.border-info` ||
`.border-light` || Not ported. Uses color only available in BS4.
`.border-dark` || Not ported. Uses color only available in BS4.
`.border-white` ||
`.rounded` ||
`.rounded-top` ||
`.rounded-right` ||
`.rounded-bottom` ||
`.rounded-left` ||
`.rounded-circle` ||
`.rounded-0` ||
`.clearfix` | X |
`.close` | X |
`.text-primary` | X |
`.text-secondary` || Not ported. Uses color only available in BS4.
`.text-success` | X |
`.text-info` | X |
`.text-warning` | X |
`.text-danger` | X |
`.text-light` || Not ported. Uses color only available in BS4.
`.text-dark` || Not ported. Uses color only available in BS4.
`.text-muted` | X |
`.text-white` | X |
`.bg-primary` | X |
`.bg-secondary` || Not ported. Uses color only available in BS4.
`.bg-success` | X |
`.bg-danger` | X |
`.bg-warning` | X |
`.bg-info` | X |
`.bg-light` || Not ported. Uses color only available in BS4.
`.bg-dark` || Not ported. Uses color only available in BS4.
`.bg-white` ||
`.d-none` || Also provides `.d-(sm\|md\|lg)-none`
`.d-inline` || Also provides `.d-(sm\|md\|lg)-inline`
`.d-inline-block` || Also provides `.d-(sm\|md\|lg)-inline-block`
`.d-block` || Also provides `.d-(sm\|md\|lg)-block`
`.d-table` || Also provides `.d-(sm\|md\|lg)-table`
`.d-table-row` || Also provides `.d-(sm\|md\|lg)-table-row`
`.d-table-cell` || Also provides `.d-(sm\|md\|lg)-table-cell`
`.d-flex` || Also provides `.d-(sm\|md\|lg)-flex`
`.d-inline-flex` || Also provides `.d-(sm\|md\|lg)-inline-flex`
`.d-print-none` ||
`.d-print-inline` ||
`.d-print-inline-block` ||
`.d-print-block` ||
`.d-print-table` ||
`.d-print-table-row` ||
`.d-print-table-cell` ||
`.d-print-flex` ||
`.d-print-inline-flex` ||
Flexbox utilities|| Too many too list! See the [Bootstrap 4 docs](https://getbootstrap.com/docs/4.0/utilities/flex/).
`.float-left` || Also provides `.float-(sm\|md\|lg)-left`
`.float-right` || Also provides `.float-(sm\|md\|lg)-right`
`.float-none` || Also provides `.float-(sm\|md\|lg)-none`
`.text-hide` | X |
`.fixed-top` ||
`.fixed-bottom` ||
`.sticky-top` ||
`.sr-only` | X |
`.sr-only-focusable` | X |
`.w-25` ||
`.w-50` ||
`.w-75` ||
`.w-100` ||
`.h-25` ||
`.h-50` ||
`.h-75` ||
`.h-100` ||
`.mw-100` ||
`.mh-100` ||
`.m-[0-4], .m(t\|r\|b\|l\|x\|y)-[0-4]` || Also provides responsive, e.g. `.mr-(sm\|md\|lg)-1`
`.m-auto, .m(t\|r\|b\|l\|x\|y)-auto` || Also provides responsive, e.g. `.m-(sm-md-lg)-auto`
`.p-[0-4], .p(t\|r\|b\|l\|x\|y)-[0-4]` || Also provides responsive, e.g. `.pr-(sm\|md\|lg)-1`
`.text-justify` ||
`.text-left` | X | Also provides `.text-(sm\|md\|lg)-left`
`.text-center` | X | Also provides `.text-(sm\|md\|lg)-center`
`.text-right` | X | Also provides `.text-(sm\|md\|lg)-right`
`.text-nowrap` ||
`.text-truncate` ||
`.text-lowercase` ||
`.text-uppercase` ||
`.text-capitalize` ||
`.font-weight-bold` ||
`.font-weight-normal` ||
`.font-weight-light` || Not ported. Uses color only available in BS4.
`.font-italic` ||
`.text-hide` ||
`.align-baseline` ||
`.align-top` ||
`.align-middle` ||
`.align-bottom` ||
`.align-text-top` ||
`.align-text-bottom` ||
`.visible` ||
`.invisible` ||

#### Deprecated

BS3 Class | Notes
:----- | -----
`.caret` | Not available in BS4
`.center-block` | Same as `.mx-auto`
`.show` | Same as `.d-(inline\|block\|etc)`
`.hide` | Same as `.d-none`
`.pull-left` | Same as `.float-left`
`.pull-right` | Same as `.float-right`
`.visible-*`, `.hidden-*` | Replaced by `.d-*` utilities
