# npmtest-mailgun-js

#### basic test coverage for  [mailgun-js (v0.10.1)](https://github.com/bojand/mailgun-js)  [![npm package](https://img.shields.io/npm/v/npmtest-mailgun-js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mailgun-js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mailgun-js.svg)](https://travis-ci.org/npmtest/node-npmtest-mailgun-js)

#### Simple Node.js helper module for Mailgun API

[![NPM](https://nodei.co/npm/mailgun-js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mailgun-js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mailgun-js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mailgun-js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mailgun-js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mailgun-js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mailgun-js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mailgun-js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mailgun-js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mailgun-js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mailgun-js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mailgun-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mailgun-js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mailgun-js/build/test-report.html](https://npmtest.github.io/node-npmtest-mailgun-js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mailgun-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mailgun-js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mailgun-js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mailgun-js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mailgun-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mailgun-js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mailgun-js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mailgun-js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Bojan Djurkovic"
    },
    "bugs": {
        "url": "http://github.com/bojand/mailgun-js/issues"
    },
    "dependencies": {
        "async": "~2.3.0",
        "debug": "~2.6.0",
        "form-data": "~2.1.1",
        "inflection": "~1.12.0",
        "is-stream": "^1.1.0",
        "path-proxy": "~1.0.0",
        "promisify-call": "^2.0.2",
        "proxy-agent": "~2.0.0",
        "tsscmp": "~1.0.0"
    },
    "description": "Simple Node.js helper module for Mailgun API",
    "devDependencies": {
        "clone": "~2.1.0",
        "mailcomposer": "~2.1.0",
        "mocha": "~3.2.0",
        "request": "^2.67.0"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "67f41e8c9cdf8f84c5603c30063f5bccb0704601",
        "tarball": "https://registry.npmjs.org/mailgun-js/-/mailgun-js-0.10.1.tgz"
    },
    "engines": {
        "node": ">=4.0"
    },
    "gitHead": "2a7c65f240ad27e35334a4a16573e40646589683",
    "homepage": "https://github.com/bojand/mailgun-js",
    "keywords": [
        "email",
        "mailgun"
    ],
    "license": "MIT",
    "main": "./lib/mailgun.js",
    "maintainers": [
        {
            "name": "bojand"
        }
    ],
    "name": "mailgun-js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/bojand/mailgun-js.git"
    },
    "scripts": {
        "docs:api": "./bin/docs",
        "docs:build": "npm run docs:api && npm run docs:prepare && npm run docs:clean && gitbook build",
        "docs:clean": "rm -rf _book",
        "docs:prepare": "gitbook install",
        "docs:publish": "npm run docs:build && cd _book && git init && git commit --allow-empty -m 'Update docs' && git checkout -b gh-pages && git add . && git commit -am 'Update docs' && git push https://github.com/bojand/mailgun-js.git gh-pages --force",
        "docs:watch": "npm run docs:api && npm run docs:prepare && gitbook serve",
        "test": "mocha"
    },
    "version": "0.10.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
