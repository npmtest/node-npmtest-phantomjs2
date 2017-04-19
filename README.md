# npmtest-phantomjs2

#### basic test coverage for  [phantomjs2 (v2.2.0)](https://github.com/zeevl/phantomjs2)  [![npm package](https://img.shields.io/npm/v/npmtest-phantomjs2.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-phantomjs2) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-phantomjs2.svg)](https://travis-ci.org/npmtest/node-npmtest-phantomjs2)

#### Headless WebKit with JS API

[![NPM](https://nodei.co/npm/phantomjs2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/phantomjs2)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-phantomjs2/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-phantomjs2/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-phantomjs2/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-phantomjs2/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-phantomjs2/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-phantomjs2/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-phantomjs2/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-phantomjs2/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-phantomjs2/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-phantomjs2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-phantomjs2/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-phantomjs2/build/test-report.html](https://npmtest.github.io/node-npmtest-phantomjs2/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-phantomjs2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-phantomjs2/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-phantomjs2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-phantomjs2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-phantomjs2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-phantomjs2/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-phantomjs2/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-phantomjs2/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Steve Lamb"
    },
    "bin": {
        "phantomjs": "./bin/phantomjs"
    },
    "bugs": {
        "url": "https://github.com/zeevl/phantomjs2/issues"
    },
    "dependencies": {
        "adm-zip": "0.4.4",
        "fs-extra": "~0.23.1",
        "glob": "^6.0.1",
        "kew": "0.4.0",
        "mkdirp": "^0.5.1",
        "npmconf": "2.1.1",
        "progress": "1.1.8",
        "request": "2.42.0",
        "request-progress": "0.3.1",
        "which": "~1.0.5"
    },
    "description": "Headless WebKit with JS API",
    "devDependencies": {
        "eslint": "1.5.1",
        "nodeunit": "0.9.0"
    },
    "directories": {},
    "dist": {
        "shasum": "75e3db02f913557a663055b0afb87998cf9160b3",
        "tarball": "https://registry.npmjs.org/phantomjs2/-/phantomjs2-2.2.0.tgz"
    },
    "gitHead": "baeef0416595fb39f147d4232c15c182f7f7526f",
    "homepage": "https://github.com/zeevl/phantomjs2",
    "keywords": [
        "phantomjs",
        "phantomjs2",
        "headless",
        "webkit"
    ],
    "license": "Apache-2.0",
    "main": "lib/phantomjs",
    "maintainers": [
        {
            "name": "zeevl"
        }
    ],
    "name": "phantomjs2",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/zeevl/phantomjs2.git"
    },
    "scripts": {
        "install": "node install.js",
        "test": "nodeunit --reporter=minimal test/tests.js && eslint install.js"
    },
    "version": "2.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
