# test coverage for  [amazon-reviews (v0.0.4)](https://github.com/xissy/node-amazon-reviews)  [![npm package](https://img.shields.io/npm/v/npmtest-amazon-reviews.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-amazon-reviews) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-amazon-reviews.svg)](https://travis-ci.org/npmtest/node-npmtest-amazon-reviews)
#### A node.js module to crawl product reviews from Amazon.

[![NPM](https://nodei.co/npm/amazon-reviews.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/amazon-reviews)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-amazon-reviews/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-amazon-reviews/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-amazon-reviews/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-amazon-reviews/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-amazon-reviews/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-amazon-reviews/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-amazon-reviews/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-amazon-reviews/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-amazon-reviews/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-amazon-reviews/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-amazon-reviews/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-amazon-reviews/build/test-report.html](https://npmtest.github.io/node-npmtest-amazon-reviews/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-amazon-reviews/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-amazon-reviews/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-amazon-reviews/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-amazon-reviews/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-amazon-reviews/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-amazon-reviews/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-amazon-reviews/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-amazon-reviews/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Taeho Kim"
    },
    "bugs": {
        "url": "https://github.com/xissy/node-amazon-reviews/issues"
    },
    "dependencies": {
        "async": "~0.2.10",
        "cheerio": "~0.14.0",
        "coffee-script": "~1.7.1",
        "request": "~2.34.0"
    },
    "description": "A node.js module to crawl product reviews from Amazon.",
    "devDependencies": {
        "mocha": "~1.3.0",
        "should": "~1.0.0"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "cfca38876871be38b8a58e1b003252f007b1e074",
        "tarball": "https://registry.npmjs.org/amazon-reviews/-/amazon-reviews-0.0.4.tgz"
    },
    "homepage": "https://github.com/xissy/node-amazon-reviews",
    "keywords": [
        "amazon",
        "product",
        "review",
        "crawl"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "xissy"
        }
    ],
    "name": "amazon-reviews",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/xissy/node-amazon-reviews.git"
    },
    "scripts": {
        "test": "mocha --compilers coffee:coffee-script --require coffee-script/register --globals lw --recursive ./test -t 50000"
    },
    "version": "0.0.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
