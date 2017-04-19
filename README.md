# npmdoc-thenify

#### api documentation for  [thenify (v3.2.1)](https://github.com/thenables/thenify#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-thenify.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-thenify) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-thenify.svg)](https://travis-ci.org/npmdoc/node-npmdoc-thenify)

#### Promisify a callback-based function

[![NPM](https://nodei.co/npm/thenify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/thenify)

- [https://npmdoc.github.io/node-npmdoc-thenify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-thenify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-thenify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-thenify/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-thenify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-thenify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Ong",
        "url": "http://jongleberry.com"
    },
    "bugs": {
        "url": "https://github.com/thenables/thenify/issues"
    },
    "dependencies": {
        "any-promise": "^1.0.0"
    },
    "description": "Promisify a callback-based function",
    "devDependencies": {
        "bluebird": "^3.1.1",
        "istanbul": "^0.4.0",
        "mocha": "^3.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "251fd1c80aff6e5cf57cb179ab1fcb724269bd11",
        "tarball": "https://registry.npmjs.org/thenify/-/thenify-3.2.1.tgz"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "42e93a084347eed9ad34cd3f77728e7fe9b2c1c5",
    "homepage": "https://github.com/thenables/thenify#readme",
    "keywords": [
        "promisify",
        "promise",
        "thenify",
        "then",
        "es6"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "jongleberry"
        },
        {
            "name": "dead-horse"
        },
        {
            "name": "dead_horse"
        }
    ],
    "name": "thenify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/thenables/thenify.git"
    },
    "scripts": {
        "test": "mocha --reporter spec",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter dot"
    },
    "version": "3.2.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
