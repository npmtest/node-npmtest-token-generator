# npmtest-token-generator

#### basic test coverage for  [token-generator (v1.0.0)](https://github.com/findhit/token-generator)  [![npm package](https://img.shields.io/npm/v/npmtest-token-generator.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-token-generator) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-token-generator.svg)](https://travis-ci.org/npmtest/node-npmtest-token-generator)

#### offline token generator and validator

[![NPM](https://nodei.co/npm/token-generator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/token-generator)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-token-generator/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-token-generator/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-token-generator/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-token-generator/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-token-generator/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-token-generator/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-token-generator/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-token-generator/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-token-generator/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-token-generator/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-token-generator/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-token-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-token-generator/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-token-generator/build/test-report.html](https://npmtest.github.io/node-npmtest-token-generator/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-token-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-token-generator/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-token-generator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-token-generator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-token-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-token-generator/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-token-generator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-token-generator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "José Moreira"
    },
    "bugs": {
        "url": "https://github.com/findhit/token-generator/issues"
    },
    "dependencies": {
        "debug": "^2.1.3",
        "findhit-class": "^0.1.1",
        "findhit-util": "^0.2.7"
    },
    "description": "offline token generator and validator",
    "devDependencies": {
        "chai": "^2.2.0",
        "mocha": "^2.2.1"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "797da9cd67ad74c53e10530e287cecff85a5305c",
        "tarball": "https://registry.npmjs.org/token-generator/-/token-generator-1.0.0.tgz"
    },
    "gitHead": "ac58070eb4946c48e0737d351ea8b2df296243b9",
    "homepage": "https://github.com/findhit/token-generator",
    "keywords": [
        "token",
        "generator",
        "offline",
        "off-line",
        "generation",
        "hash",
        "crypto",
        "timestamp",
        "confirmation",
        "validate",
        "validation",
        "validator",
        "generater",
        "findhit"
    ],
    "license": "GPL v3",
    "main": "index.js",
    "maintainers": [
        {
            "name": "cuss"
        }
    ],
    "name": "token-generator",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/findhit/token-generator.git"
    },
    "scripts": {
        "test": "node node_modules/mocha/bin/mocha --globals setImmediate,clearImmediate --check-leaks --colors -t 10000 --reporter spec $(find test/* -name '*.test.js')"
    },
    "version": "1.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
