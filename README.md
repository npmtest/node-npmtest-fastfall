# npmtest-fastfall

#### basic test coverage for  [fastfall (v1.5.1)](https://github.com/mcollina/fastfall#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-fastfall.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-fastfall) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-fastfall.svg)](https://travis-ci.org/npmtest/node-npmtest-fastfall)

#### call your callbacks in a waterfall, at speed

[![NPM](https://nodei.co/npm/fastfall.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fastfall)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-fastfall/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-fastfall/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-fastfall/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-fastfall/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-fastfall/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-fastfall/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-fastfall/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-fastfall/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-fastfall/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-fastfall/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-fastfall/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-fastfall/build/test-report.html](https://npmtest.github.io/node-npmtest-fastfall/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-fastfall/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-fastfall/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-fastfall/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fastfall/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fastfall/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fastfall/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-fastfall/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-fastfall/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matteo Collina"
    },
    "bugs": {
        "url": "https://github.com/mcollina/fastfall/issues"
    },
    "dependencies": {
        "reusify": "^1.0.0"
    },
    "description": "call your callbacks in a waterfall, at speed",
    "devDependencies": {
        "async": "^1.0.0",
        "coveralls": "^2.11.6",
        "fastbench": "^1.0.0",
        "faucet": "0.0.1",
        "insync": "^2.1.1",
        "istanbul": "^0.4.1",
        "neo-async": "^1.7.0",
        "pre-commit": "^1.0.10",
        "run-waterfall": "^1.1.1",
        "standard": "^5.0.0",
        "tap-spec": "^4.1.1",
        "tape": "^4.0.0",
        "waterfallize": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "3fee03331a49d1d39b3cdf7a5e9cd66f475e7b94",
        "tarball": "https://registry.npmjs.org/fastfall/-/fastfall-1.5.1.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "c3aba5dd8c48dc4333c3cfc5fb859b55d910a1ba",
    "homepage": "https://github.com/mcollina/fastfall#readme",
    "keywords": [
        "async",
        "waterfall",
        "fall",
        "fast",
        "callback"
    ],
    "license": "MIT",
    "main": "fall.js",
    "maintainers": [
        {
            "name": "matteo.collina"
        }
    ],
    "name": "fastfall",
    "optionalDependencies": {},
    "precommit": [
        "lint",
        "test"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mcollina/fastfall.git"
    },
    "scripts": {
        "coverage": "istanbul cover tape test.js | tap-spec",
        "coveralls": "npm run coverage ; cat ./coverage/lcov.info | coveralls",
        "lint": "standard",
        "test": "tape test.js | faucet"
    },
    "version": "1.5.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
