<!--

@license Apache-2.0

Copyright (c) 2020 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# isPositiveZerof

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Test if a single-precision floating-point numeric value is positive zero.



<section class="usage">

## Usage

To use in Observable,

```javascript
isPositiveZerof = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/math-base-assert-is-positive-zerof@umd/browser.js' )
```

To vendor stdlib functionality and avoid installing dependency trees for Node.js, you can use the UMD server build:

```javascript
var isPositiveZerof = require( 'path/to/vendor/umd/math-base-assert-is-positive-zerof/index.js' )
```

To include the bundle in a webpage,

```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/math-base-assert-is-positive-zerof@umd/browser.js"></script>
```

If no recognized module system is present, access bundle contents via the global scope:

```html
<script type="text/javascript">
(function () {
    window.isPositiveZerof;
})();
</script>
```

#### isPositiveZerof( x )

Tests if a single-precision floating-point `numeric` value is positive zero.

```javascript
var bool = isPositiveZerof( 0.0 );
// returns true

bool = isPositiveZerof( -0.0 );
// returns false
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/math-base-assert-is-positive-zerof@umd/browser.js"></script>
<script type="text/javascript">
(function () {

var bool = isPositiveZerof( 0.0 );
// returns true

bool = isPositiveZerof( -0.0 );
// returns false

bool = isPositiveZerof( 5.0 );
// returns false

bool = isPositiveZerof( -1.0 );
// returns false

bool = isPositiveZerof( NaN );
// returns false

})();
</script>
</body>
</html>
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

* * *

## See Also

-   <span class="package-name">[`@stdlib/math-base/assert/is-negative-zerof`][@stdlib/math/base/assert/is-negative-zerof]</span><span class="delimiter">: </span><span class="description">test if a single-precision floating-point numeric value is negative zero.</span>
-   <span class="package-name">[`@stdlib/math-base/assert/is-positive-zero`][@stdlib/math/base/assert/is-positive-zero]</span><span class="delimiter">: </span><span class="description">test if a double-precision floating-point numeric value is positive zero.</span>

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## Copyright

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/math-base-assert-is-positive-zerof.svg
[npm-url]: https://npmjs.org/package/@stdlib/math-base-assert-is-positive-zerof

[test-image]: https://github.com/stdlib-js/math-base-assert-is-positive-zerof/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/math-base-assert-is-positive-zerof/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/math-base-assert-is-positive-zerof/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/math-base-assert-is-positive-zerof?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/math-base-assert-is-positive-zerof.svg
[dependencies-url]: https://david-dm.org/stdlib-js/math-base-assert-is-positive-zerof/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/math-base-assert-is-positive-zerof/tree/deno
[umd-url]: https://github.com/stdlib-js/math-base-assert-is-positive-zerof/tree/umd
[esm-url]: https://github.com/stdlib-js/math-base-assert-is-positive-zerof/tree/esm
[branches-url]: https://github.com/stdlib-js/math-base-assert-is-positive-zerof/blob/main/branches.md

<!-- <related-links> -->

[@stdlib/math/base/assert/is-negative-zerof]: https://github.com/stdlib-js/math-base-assert-is-negative-zerof/tree/umd

[@stdlib/math/base/assert/is-positive-zero]: https://github.com/stdlib-js/math-base-assert-is-positive-zero/tree/umd

<!-- </related-links> -->

</section>

<!-- /.links -->
