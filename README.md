# npmdoc-rstats

#### api documentation for  [rstats (v0.3.1)](https://github.com/Planeshifter/node-Rstats)  [![npm package](https://img.shields.io/npm/v/npmdoc-rstats.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-rstats) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-rstats.svg)](https://travis-ci.org/npmdoc/node-npmdoc-rstats)

#### A node.js interface for statistical programming language R

[![NPM](https://nodei.co/npm/rstats.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rstats)

- [https://npmdoc.github.io/node-npmdoc-rstats/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rstats/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rstats/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rstats/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-rstats/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-rstats/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "rstats",
    "version": "0.3.1",
    "description": "A node.js interface for statistical programming language R",
    "main": "./lib/index.js",
    "scripts": {
        "test": "node-gyp configure build && mocha test",
        "install": "node-gyp rebuild"
    },
    "dependencies": {
        "bindings": "1.2.0",
        "nan": "^1.7.0"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/Planeshifter/node-Rstats.git"
    },
    "keywords": [
        "statistics",
        "R",
        "Rcpp"
    ],
    "author": "Philipp Burckhardt",
    "license": "ISC",
    "gypfile": true,
    "bugs": {
        "url": "https://github.com/Planeshifter/node-Rstats/issues"
    },
    "homepage": "https://github.com/Planeshifter/node-Rstats",
    "devDependencies": {
        "chai": "^2.1.2",
        "mocha": "^2.2.1"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
