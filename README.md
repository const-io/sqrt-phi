SQRT PHI
===
[![NPM version][npm-image]][npm-url] [![Build Status][build-image]][build-url] [![Coverage Status][coverage-image]][coverage-url] [![Dependencies][dependencies-image]][dependencies-url]

> Square root of the [Golden ratio][phi] (φ).


## Installation

``` bash
$ npm install compute-const-sqrt-phi
```


## Usage

``` javascript
var SQRT_PHI = require( 'compute-const-sqrt-phi' );
```

#### SQRT_PHI

Square root of the [golden ratio][phi].

``` javascript
SQRT_PHI === 1.272019649514069;
```


## Examples

``` javascript
var SQRT_PHI = require( 'compute-const-sqrt-phi' );

console.log( SQRT_PHI );
// returns 1.272019649514069
```

To run the example code from the top-level application directory,

``` bash
$ node ./examples/index.js
```


---
## Tests

### Unit

This repository uses [tape][tape] for unit tests. To run the tests, execute the following command in the top-level application directory:

``` bash
$ make test
```

All new feature development should have corresponding unit tests to validate correct functionality.


### Test Coverage

This repository uses [Istanbul][istanbul] as its code coverage tool. To generate a test coverage report, execute the following command in the top-level application directory:

``` bash
$ make test-cov
```

Istanbul creates a `./reports/coverage` directory. To access an HTML version of the report,

``` bash
$ make view-cov
```


### Browser Support

This repository uses [Testling][testling] for browser testing. To run the tests in a (headless) local web browser, execute the following command in the top-level application directory:

``` bash
$ make test-browsers
```

To view the tests in a local web browser,

``` bash
$ make view-browser-tests
```

<!-- [![browser support][browsers-image]][browsers-url] -->


---
## License

[MIT license](http://opensource.org/licenses/MIT).


## Copyright

Copyright &copy; 2015-2016. The [Compute.io][compute-io] Authors.


[npm-image]: http://img.shields.io/npm/v/compute-const-sqrt-phi.svg
[npm-url]: https://npmjs.org/package/compute-const-sqrt-phi

[build-image]: http://img.shields.io/travis/const-io/sqrt-phi/master.svg
[build-url]: https://travis-ci.org/const-io/sqrt-phi

[coverage-image]: https://img.shields.io/codecov/c/github/const-io/sqrt-phi/master.svg
[coverage-url]: https://codecov.io/github/const-io/sqrt-phi?branch=master

[dependencies-image]: http://img.shields.io/david/const-io/sqrt-phi.svg
[dependencies-url]: https://david-dm.org/const-io/sqrt-phi

[dev-dependencies-image]: http://img.shields.io/david/dev/const-io/sqrt-phi.svg
[dev-dependencies-url]: https://david-dm.org/dev/const-io/sqrt-phi

[github-issues-image]: http://img.shields.io/github/issues/const-io/sqrt-phi.svg
[github-issues-url]: https://github.com/const-io/sqrt-phi/issues

[tape]: https://github.com/substack/tape
[istanbul]: https://github.com/gotwarlost/istanbul
[testling]: https://ci.testling.com

[compute-io]: https://github.com/compute-io/

[phi]: https://github.com/const-io/phi
[sqrt-phi]: http://oeis.org/A139339
