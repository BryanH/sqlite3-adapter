[![Yarn Version][yarn-image]][npm-url]
[![NPM Downloads][downloads-image]][downloads-url]
[![Build status][build-status]][build-url]
[![Test Coverage][coveralls-image]][coveralls-url]
[![Dependency Status][dependencies-image]][dependencies-url]

## JugglingDB-SQLite3

SQLite3 adapter for jugglingdb based on [mapbox/node-sqlite3](https://github.com/mapbox/node-sqlite3) sqlite3 bindings.

## Installation & Usage

To use it you need `jugglingdb@0.2.x` and `Node` >= 6.14.0.

1. Setup dependencies in `package.json`:

    ```json
    {
      ...
      "dependencies": {
        "jugglingdb": "0.2.x",
        "jugglingdb-sqlite3": "latest"
      },
      ...
    }
    ```

2. Use:

    ```javascript
    var Schema = require('jugglingdb').Schema;
    var schema = new Schema('sqlite3', {
        database: ':memory:'
    });
    ```

## Running tests

    yarn test

## MIT License

    Copyright 2012 by Anatoliy Chakkaev
    Copyright 2018 by Bryan Hanks

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.

[coveralls-url]: https://coveralls.io/github/BryanH/sqlite3-adapter
[coveralls-image]: https://coveralls.io/repos/github/BryanH/sqlite3-adapter/badge.svg
[build-status]: https://travis-ci.org/BryanH/sqlite3-adapter.svg?branch=master
[build-url]: https://travis-ci.org/BryanH/sqlite3-adapter
[yarn-image]: https://img.shields.io/badge/yarn-v1.10.1%20%20-blue.svg
[npm-url]: https://npmjs.org/package/jugglingdb-sqlite3
[downloads-image]: https://img.shields.io/npm/dm/jugglingdb-sqlite3.svg
[downloads-url]: https://npmjs.org/package/jugglingdb-sqlite3
[dependencies-image]: https://david-dm.org/BryanH/sqlite3-adapter.svg
[dependencies-url]: https://david-dm.org/BryanH/sqlite3-adapter

