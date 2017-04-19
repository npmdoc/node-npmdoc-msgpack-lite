# npmdoc-msgpack-lite

#### api documentation for  [msgpack-lite (v0.1.26)](https://github.com/kawanet/msgpack-lite)  [![npm package](https://img.shields.io/npm/v/npmdoc-msgpack-lite.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-msgpack-lite) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-msgpack-lite.svg)](https://travis-ci.org/npmdoc/node-npmdoc-msgpack-lite)

#### Fast Pure JavaScript MessagePack Encoder and Decoder

[![NPM](https://nodei.co/npm/msgpack-lite.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/msgpack-lite)

- [https://npmdoc.github.io/node-npmdoc-msgpack-lite/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-msgpack-lite/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-msgpack-lite/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-msgpack-lite/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-msgpack-lite/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-msgpack-lite/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "@kawanet"
    },
    "bin": {
        "msgpack": "./bin/msgpack"
    },
    "browser": "lib/browser.js",
    "bugs": {
        "url": "https://github.com/kawanet/msgpack-lite/issues"
    },
    "contributors": [
        {
            "name": "Christopher Vermilion"
        },
        {
            "name": "Frederik Dudzik"
        },
        {
            "name": "Garrett Serack"
        },
        {
            "name": "Jesse Armand"
        },
        {
            "name": "Joshua Wise"
        },
        {
            "name": "Maciej Hirsz"
        }
    ],
    "dependencies": {
        "event-lite": "^0.1.1",
        "ieee754": "^1.1.8",
        "int64-buffer": "^0.1.9",
        "isarray": "^1.0.0"
    },
    "description": "Fast Pure JavaScript MessagePack Encoder and Decoder",
    "devDependencies": {
        "async": "^2.1.1",
        "browserify": "^13.1.0",
        "concat-stream": "^1.5.2",
        "jshint": "^2.9.3",
        "mocha": "^3.1.2",
        "msgpack.codec": "git+https://github.com/kawanet/msgpack-javascript.git#msgpack.codec",
        "uglify-js": "^2.7.3",
        "zuul": "^3.11.1"
    },
    "directories": {},
    "dist": {
        "shasum": "dd3c50b26f059f25e7edee3644418358e2a9ad89",
        "tarball": "https://registry.npmjs.org/msgpack-lite/-/msgpack-lite-0.1.26.tgz"
    },
    "gitHead": "5b71d82cad4b96289a466a6403d2faaa3e254167",
    "homepage": "https://github.com/kawanet/msgpack-lite",
    "jshintConfig": {
        "es3": true,
        "globals": {
            "JSON": true,
            "Symbol": true,
            "Map": true,
            "window": true
        },
        "mocha": true,
        "node": true,
        "undef": true
    },
    "keywords": [
        "arraybuffer",
        "buffer",
        "fluentd",
        "messagepack",
        "msgpack",
        "serialize",
        "stream",
        "typedarray",
        "uint8array"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "kawanet"
        }
    ],
    "name": "msgpack-lite",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kawanet/msgpack-lite.git"
    },
    "scripts": {
        "benchmark": "./lib/benchmark.js",
        "benchmark-lite": "./lib/benchmark.js msgpack-lite",
        "benchmark-stream": "./lib/benchmark-stream.js",
        "fixpack": "fixpack",
        "make": "make",
        "size": "make clean dist/msgpack.min.js && gzip -9fkv dist/msgpack.min.js && ls -l dist",
        "test": "make test",
        "test-browser-local": "make test-browser-local"
    },
    "version": "0.1.26"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
