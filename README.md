# npmtest-ndjson

#### basic test coverage for  [ndjson (v1.5.0)](https://github.com/maxogden/ndjson)  [![npm package](https://img.shields.io/npm/v/npmtest-ndjson.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ndjson) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ndjson.svg)](https://travis-ci.org/npmtest/node-npmtest-ndjson)

#### streaming newline delimited json parser + serializer

[![NPM](https://nodei.co/npm/ndjson.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ndjson)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ndjson/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ndjson/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ndjson/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ndjson/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ndjson/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-ndjson/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-ndjson/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ndjson/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ndjson/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ndjson/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ndjson/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ndjson/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ndjson/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ndjson/build/test-report.html](https://npmtest.github.io/node-npmtest-ndjson/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ndjson/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ndjson/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ndjson/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ndjson/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ndjson/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ndjson/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ndjson/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ndjson/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "max ogden"
    },
    "bin": {
        "ndjson": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/maxogden/ndjson/issues"
    },
    "dependencies": {
        "json-stringify-safe": "^5.0.1",
        "minimist": "^1.2.0",
        "split2": "^2.1.0",
        "through2": "^2.0.3"
    },
    "description": "streaming newline delimited json parser + serializer",
    "devDependencies": {
        "concat-stream": "^1.5.0",
        "tape": "^4.6.3"
    },
    "directories": {},
    "dist": {
        "shasum": "ae603b36b134bcec347b452422b0bf98d5832ec8",
        "tarball": "https://registry.npmjs.org/ndjson/-/ndjson-1.5.0.tgz"
    },
    "gitHead": "2bb834d45e1ff8894356e0f36e8d00dbf2c8a063",
    "homepage": "https://github.com/maxogden/ndjson",
    "keywords": [
        "ndjson",
        "ldjson"
    ],
    "license": "BSD-3-Clause",
    "main": "index.js",
    "maintainers": [
        {
            "name": "maxogden"
        },
        {
            "name": "finnpauls"
        }
    ],
    "name": "ndjson",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/maxogden/ndjson.git"
    },
    "scripts": {
        "test": "tape test.js"
    },
    "version": "1.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
