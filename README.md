# npmtest-generator-backbone

#### basic test coverage for  [generator-backbone (v0.4.2)](https://github.com/yeoman/generator-backbone#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-generator-backbone.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-generator-backbone) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-generator-backbone.svg)](https://travis-ci.org/npmtest/node-npmtest-generator-backbone)

#### Scaffold out a Backbone.js project

[![NPM](https://nodei.co/npm/generator-backbone.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generator-backbone)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-generator-backbone/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-backbone/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-generator-backbone/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-generator-backbone/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-generator-backbone/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-generator-backbone/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-generator-backbone/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-generator-backbone/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-generator-backbone/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-generator-backbone/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-generator-backbone/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-backbone/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-generator-backbone/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-generator-backbone/build/test-report.html](https://npmtest.github.io/node-npmtest-generator-backbone/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-generator-backbone/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-generator-backbone/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-generator-backbone/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generator-backbone/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-backbone/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-backbone/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-generator-backbone/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-generator-backbone/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Yeoman"
    },
    "bugs": {
        "url": "https://github.com/yeoman/generator-backbone/issues"
    },
    "dependencies": {
        "ejs": "^2.3.0",
        "html-wiring": "^1.0.0",
        "mkdirp": "^0.5.1",
        "param-case": "^1.1.0",
        "pascal-case": "^1.1.0",
        "yeoman-generator": "^0.21.1"
    },
    "description": "Scaffold out a Backbone.js project",
    "devDependencies": {
        "mocha": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "7bc52e447d80a3c12370824656aabe334152397e",
        "tarball": "https://registry.npmjs.org/generator-backbone/-/generator-backbone-0.4.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "generators/all",
        "generators/app",
        "generators/collection",
        "generators/model",
        "generators/router",
        "generators/templates",
        "generators/view",
        "script-base.js",
        "util.js"
    ],
    "gitHead": "a3dffd4031380733f33222bc7b4bde4e5093ad1e",
    "homepage": "https://github.com/yeoman/generator-backbone#readme",
    "keywords": [
        "yeoman-generator",
        "scaffold",
        "framework",
        "mvc",
        "backbone"
    ],
    "license": "BSD",
    "main": "generators/app/index.js",
    "maintainers": [
        {
            "name": "addyosmani"
        },
        {
            "name": "arthurvr"
        },
        {
            "name": "eddiemonge"
        },
        {
            "name": "passy"
        },
        {
            "name": "paulirish"
        },
        {
            "name": "revathskumar"
        },
        {
            "name": "ruyadorno"
        },
        {
            "name": "sboudrias"
        },
        {
            "name": "sindresorhus"
        }
    ],
    "name": "generator-backbone",
    "optionalDependencies": {},
    "peerDependencies": {
        "generator-mocha": ">=0.1.3",
        "generator-backbone-mocha": ">=0.0.2"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/yeoman/generator-backbone.git"
    },
    "scripts": {
        "test": "mocha --reporter spec"
    },
    "version": "0.4.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
