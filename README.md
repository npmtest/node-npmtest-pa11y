# npmtest-pa11y

#### basic test coverage for  [pa11y (v4.10.0)](https://github.com/pa11y/pa11y)  [![npm package](https://img.shields.io/npm/v/npmtest-pa11y.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pa11y) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pa11y.svg)](https://travis-ci.org/npmtest/node-npmtest-pa11y)

#### Pa11y is your automated accessibility testing pal

[![NPM](https://nodei.co/npm/pa11y.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pa11y)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pa11y/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pa11y/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pa11y/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pa11y/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pa11y/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pa11y/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pa11y/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pa11y/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pa11y/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pa11y/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pa11y/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pa11y/build/test-report.html](https://npmtest.github.io/node-npmtest-pa11y/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pa11y/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pa11y/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pa11y/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pa11y/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pa11y/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pa11y/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pa11y/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pa11y/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Team Pa11y"
    },
    "bin": {
        "pa11y": "./bin/pa11y.js"
    },
    "bugs": {
        "url": "https://github.com/pa11y/pa11y/issues"
    },
    "contributors": [
        {
            "name": "Rowan Manning",
            "url": "http://rowanmanning.com/"
        },
        {
            "name": "Whymarrh Whitby",
            "url": "http://whymarrh.com/"
        },
        {
            "name": "Stephen Mathieson",
            "url": "http://www.stephenmathieson.com/"
        },
        {
            "name": "Alex Soble",
            "url": "http://www.alexsoble.com/"
        },
        {
            "name": "Charlie Brown",
            "url": "http://www.carbonatethis.com/"
        },
        {
            "name": "Hollie Kay",
            "url": "http://www.hollsk.co.uk/"
        },
        {
            "name": "Adam Tavener",
            "url": "http://www.tavvy.co.uk/"
        },
        {
            "name": "Glynn Phillips",
            "url": "http://www.glynnphillips.co.uk/"
        }
    ],
    "dependencies": {
        "async": "^2.2.0",
        "bfj": "^2.1.2",
        "chalk": "^1.1.3",
        "commander": "^2.9.0",
        "lower-case": "^1.1.4",
        "node.extend": "^1.1.6",
        "once": "^1.4.0",
        "phantomjs-prebuilt": "^2.1.12",
        "truffler": "^3.0.1"
    },
    "description": "Pa11y is your automated accessibility testing pal",
    "devDependencies": {
        "eslint": "^3.18.0",
        "mocha": "^3.2.0",
        "mockery": "^2.0.0",
        "nyc": "^10.1.2",
        "pa11y-lint-config": "^1.0.0",
        "proclaim": "^3.4.4",
        "sinon": "^2.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "1610e813a01fdda5cc854cc81a722996390d2dc9",
        "tarball": "https://registry.npmjs.org/pa11y/-/pa11y-4.10.0.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "6cf27711d2ce7f27cbe081214abfc7e2c49891ed",
    "homepage": "https://github.com/pa11y/pa11y",
    "keywords": [
        "accessibility",
        "analysis",
        "cli",
        "report"
    ],
    "license": "LGPL-3.0",
    "main": "./lib/pa11y.js",
    "maintainers": [
        {
            "name": "andrewmee"
        },
        {
            "name": "dotcode"
        },
        {
            "name": "glynnphillips"
        },
        {
            "name": "hollsk"
        },
        {
            "name": "joseluisbolos"
        },
        {
            "name": "rowanmanning"
        }
    ],
    "name": "pa11y",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pa11y/pa11y.git"
    },
    "scripts": {
        "test": "make ci"
    },
    "version": "4.10.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
