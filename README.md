# @dramaorg/est-vel-libero <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple list of possible Typed Array names.

## Example

```js
const assert = require('assert');

const names = require('@dramaorg/est-vel-libero');

assert(Array.isArray(names));
assert(names.every(name => (
    typeof name === 'string'
    && typeof globalThis[name] === 'function'
    && globalThis[name].name === name
)));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@dramaorg/est-vel-libero
[npm-version-svg]: https://versionbadg.es/ljharb/@dramaorg/est-vel-libero.svg
[deps-svg]: https://david-dm.org/ljharb/@dramaorg/est-vel-libero.svg
[deps-url]: https://david-dm.org/ljharb/@dramaorg/est-vel-libero
[dev-deps-svg]: https://david-dm.org/ljharb/@dramaorg/est-vel-libero/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@dramaorg/est-vel-libero#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@dramaorg/est-vel-libero.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@dramaorg/est-vel-libero.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@dramaorg/est-vel-libero.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@dramaorg/est-vel-libero
[codecov-image]: https://codecov.io/gh/ljharb/@dramaorg/est-vel-libero/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@dramaorg/est-vel-libero/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@dramaorg/est-vel-libero
[actions-url]: https://github.com/dramaorg/est-vel-libero/actions
