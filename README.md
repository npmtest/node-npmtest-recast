# test coverage for  [recast (v0.12.3)](http://github.com/benjamn/recast)  [![npm package](https://img.shields.io/npm/v/npmtest-recast.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-recast) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-recast.svg)](https://travis-ci.org/npmtest/node-npmtest-recast)
#### JavaScript syntax tree transformer, nondestructive pretty-printer, and automatic source map generator

[![NPM](https://nodei.co/npm/recast.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/recast)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-recast/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-recast/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-recast/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-recast/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-recast/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-recast/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-recast/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-recast/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-recast/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-recast/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-recast/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-recast/build/test-report.html](https://npmtest.github.io/node-npmtest-recast/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-recast/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-recast/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-recast/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-recast/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-recast/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-recast/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-recast/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-recast/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ben Newman"
    },
    "browser": {
        "fs": false
    },
    "bugs": {
        "url": "https://github.com/benjamn/recast/issues"
    },
    "dependencies": {
        "ast-types": "0.9.11",
        "core-js": "^2.4.1",
        "esprima": "~3.1.0",
        "private": "~0.1.5",
        "source-map": "~0.5.0"
    },
    "description": "JavaScript syntax tree transformer, nondestructive pretty-printer, and automatic source map generator",
    "devDependencies": {
        "babel-core": "^6.23.1",
        "babel-preset-es2015": "^6.22.0",
        "babylon": "~6.16.1",
        "esprima-fb": "^15001.1001.0-dev-harmony-fb",
        "mocha": "~3.2.0",
        "reify": "^0.6.2",
        "semver": "^5.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "ce39d41911ea56d69701216d61e350a4d9505d4d",
        "tarball": "https://registry.npmjs.org/recast/-/recast-0.12.3.tgz"
    },
    "engines": {
        "node": ">= 0.8"
    },
    "gitHead": "5bfd3f2fb9df404c1178e74516eca2bcc691ad43",
    "homepage": "http://github.com/benjamn/recast",
    "keywords": [
        "ast",
        "rewriting",
        "refactoring",
        "codegen",
        "syntax",
        "transformation",
        "parsing",
        "pretty-printing"
    ],
    "license": "MIT",
    "main": "main.js",
    "maintainers": [
        {
            "name": "benjamn"
        }
    ],
    "name": "recast",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/benjamn/recast.git"
    },
    "scripts": {
        "debug": "node ./node_modules/mocha/bin/mocha --debug-brk --reporter spec",
        "test": "node ./node_modules/mocha/bin/mocha --reporter spec --full-trace"
    },
    "version": "0.12.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
