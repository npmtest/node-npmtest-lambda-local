# npmtest-lambda-local

#### basic test coverage for  [lambda-local (v1.4.2)](https://github.com/ashiina/lambda-local#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-lambda-local.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-lambda-local) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-lambda-local.svg)](https://travis-ci.org/npmtest/node-npmtest-lambda-local)

#### Commandline tool to run Lambda functions on your local machine.

[![NPM](https://nodei.co/npm/lambda-local.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/lambda-local)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-lambda-local/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-lambda-local/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-lambda-local/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-lambda-local/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-lambda-local/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-lambda-local/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-lambda-local/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-lambda-local/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-lambda-local/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-lambda-local/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-lambda-local/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-lambda-local/build/test-report.html](https://npmtest.github.io/node-npmtest-lambda-local/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-lambda-local/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-lambda-local/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-lambda-local/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-lambda-local/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lambda-local/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lambda-local/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-lambda-local/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-lambda-local/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "ashiina"
    },
    "bin": {
        "lambda-local": "./bin/lambda-local"
    },
    "bugs": {
        "url": "https://github.com/ashiina/lambda-local/issues"
    },
    "dependencies": {
        "aws-sdk": "^2.1.6",
        "chai": "^3.5.0",
        "commander": "^2.6.0",
        "fs": "^0.0.2",
        "mute": "^2.0.6",
        "winston": "^2.2.0"
    },
    "description": "Commandline tool to run Lambda functions on your local machine.",
    "devDependencies": {
        "mocha": "^2.4.5",
        "sinon": "^1.17.6"
    },
    "directories": {},
    "dist": {
        "shasum": "e14764cc68e2c679b02556c223c056ca3d14f12b",
        "tarball": "https://registry.npmjs.org/lambda-local/-/lambda-local-1.4.2.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "c158282325783d0cfd7e4601c1c00cb2b67cd379",
    "homepage": "https://github.com/ashiina/lambda-local#readme",
    "keywords": [
        "lambda",
        "amazon",
        "aws",
        "AWS",
        "local",
        "run"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "ashiina"
        }
    ],
    "name": "lambda-local",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ashiina/lambda-local.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "version": "1.4.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
