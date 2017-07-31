# platform-is [![NPM version](https://img.shields.io/npm/v/platform-is.svg?style=flat)](https://www.npmjs.com/package/platform-is) [![NPM monthly downloads](https://img.shields.io/npm/dm/platform-is.svg?style=flat)](https://npmjs.org/package/platform-is)  [![NPM total downloads](https://img.shields.io/npm/dt/platform-is.svg?style=flat)](https://npmjs.org/package/platform-is) [![Linux Build Status](https://img.shields.io/travis/jonschlinkert/platform-is.svg?style=flat&label=Travis)](https://travis-ci.org/jonschlinkert/platform-is)

> Returns true if the platform is windows.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install --save platform-is
```

## Heads up!

As of `v0.2.0` this module always returns a function.

## Usage

```js
var isWindows = require('platform-is');
var isMac = require('platform-is').isMac;
var isLinux = require('platform-is').isLinux;
isMac();
isLinux();
isWindows();
//=> returns true if the platform is windows, same for linux, mac
```

### Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](../../issues/new).

### Building docs

_(This project's readme.md is generated by [verb](https://github.com/verbose/verb-generate-readme), please don't edit the readme directly. Any changes to the readme must be made in the [.verb.md](.verb.md) readme template.)_

To generate the readme, run the following command:

```sh
$ npm install -g verbose/verb#dev verb-generate-readme && verb
```

### Running tests

Running and reviewing unit tests is a great way to get familiarized with a library and its API. You can install dependencies and run tests with the following command:

```sh
$ npm install && npm test
```

### License

Copyright © 2017, [Dmitry Poddubniy](https://github.com/mr47).
Released under the [MIT License](LICENSE).

***

_This file was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme), v0.4.3, on April 28, 2017._