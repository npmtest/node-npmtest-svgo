# test coverage for  [svgo (v0.7.2)](https://github.com/svg/svgo)  [![npm package](https://img.shields.io/npm/v/npmtest-svgo.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-svgo) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-svgo.svg)](https://travis-ci.org/npmtest/node-npmtest-svgo)
#### Nodejs-based tool for optimizing SVG vector graphics files

[![NPM](https://nodei.co/npm/svgo.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/svgo)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-svgo/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-svgo/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-svgo/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-svgo/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-svgo/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-svgo/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-svgo/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-svgo/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-svgo/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-svgo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-svgo/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-svgo/build/test-report.html](https://npmtest.github.io/node-npmtest-svgo/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-svgo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-svgo/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-svgo/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-svgo/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-svgo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-svgo/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-svgo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-svgo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kir Belevich",
        "url": "https://github.com/deepsweet"
    },
    "bin": {
        "svgo": "./bin/svgo"
    },
    "bugs": {
        "url": "https://github.com/svg/svgo/issues"
    },
    "contributors": [
        {
            "name": "Sergey Belov",
            "url": "http://github.com/arikon"
        },
        {
            "name": "Lev Solntsev",
            "url": "http://github.com/GreLI"
        }
    ],
    "dependencies": {
        "coa": "~1.0.1",
        "colors": "~1.1.2",
        "csso": "~2.3.1",
        "js-yaml": "~3.7.0",
        "mkdirp": "~0.5.1",
        "sax": "~1.2.1",
        "whet.extend": "~0.9.9"
    },
    "description": "Nodejs-based tool for optimizing SVG vector graphics files",
    "devDependencies": {
        "coveralls": "~2.11.14",
        "istanbul": "~0.4.5",
        "mocha": "~3.2.0",
        "mocha-istanbul": "~0.3.0",
        "should": "11.2.0"
    },
    "directories": {
        "bin": "./bin",
        "lib": "./lib",
        "example": "./examples"
    },
    "dist": {
        "shasum": "9f5772413952135c6fefbf40afe6a4faa88b4bb5",
        "tarball": "https://registry.npmjs.org/svgo/-/svgo-0.7.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "ad053787d019e3efc0e21b7478e5b1c7816b17d6",
    "homepage": "https://github.com/svg/svgo",
    "keywords": [
        "svgo",
        "svg",
        "optimize",
        "minify"
    ],
    "license": "MIT",
    "main": "./lib/svgo.js",
    "maintainers": [
        {
            "name": "deepsweet"
        },
        {
            "name": "greli"
        }
    ],
    "name": "svgo",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/svg/svgo.git"
    },
    "scripts": {
        "jshint": "jshint --show-non-errors .",
        "test": "set NODE_ENV=test && mocha"
    },
    "version": "0.7.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
