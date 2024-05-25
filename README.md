# String.prototype.padEnd <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ES2017 spec-compliant `String.prototype.padEnd` shim. Invoke its "shim" method to shim `String.prototype.padEnd` if it is unavailable.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://github.com/tc39/ecma262/pull/581).

Most common usage:
```js
var padEnd = require('@kollorg/labore-quidem');

assert(padEnd('foo', 5, 'bar') === 'fooba');

padEnd.shim();

assert(padEnd('foo', 2) === 'foo'.padEnd(2));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.com/package/@kollorg/labore-quidem
[npm-version-svg]: http://versionbadg.es/kollorg/labore-quidem.svg
[travis-svg]: https://travis-ci.org/kollorg/labore-quidem.svg
[travis-url]: https://travis-ci.org/kollorg/labore-quidem
[deps-svg]: https://david-dm.org/kollorg/labore-quidem.svg
[deps-url]: https://david-dm.org/kollorg/labore-quidem
[dev-deps-svg]: https://david-dm.org/kollorg/labore-quidem/dev-status.svg
[dev-deps-url]: https://david-dm.org/kollorg/labore-quidem#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@kollorg/labore-quidem.png?downloads=true&stars=true
[license-image]: http://img.shields.io/npm/l/@kollorg/labore-quidem.svg
[license-url]: LICENSE
[downloads-image]: http://img.shields.io/npm/dm/@kollorg/labore-quidem.svg
[downloads-url]: http://npm-stat.com/charts.html?package=@kollorg/labore-quidem
[codecov-image]: https://codecov.io/gh/kollorg/labore-quidem/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/kollorg/labore-quidem/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/kollorg/labore-quidem
[actions-url]: https://github.com/kollorg/labore-quidem/actions
