# npmtest-web-ext

#### test coverage for  [web-ext (v1.8.1)](https://github.com/mozilla/web-ext)  [![npm package](https://img.shields.io/npm/v/npmtest-web-ext.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-web-ext) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-web-ext.svg)](https://travis-ci.org/npmtest/node-npmtest-web-ext)

#### A command line tool to help build, run, and test web extensions

[![NPM](https://nodei.co/npm/web-ext.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/web-ext)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-web-ext/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-web-ext/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-web-ext/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-web-ext/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-web-ext/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-web-ext/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-web-ext/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-web-ext/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-web-ext/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-web-ext/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-web-ext/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-web-ext/build/test-report.html](https://npmtest.github.io/node-npmtest-web-ext/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-web-ext/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-web-ext/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-web-ext/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-web-ext/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-web-ext/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-web-ext/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-web-ext/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-web-ext/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kumar McMillan"
    },
    "bin": {
        "web-ext": "bin/web-ext"
    },
    "bugs": {
        "url": "http://github.com/mozilla/web-ext/issues"
    },
    "dependencies": {
        "addons-linter": "0.15.15",
        "babel-polyfill": "6.20.0",
        "babel-runtime": "6.20.0",
        "bunyan": "1.8.5",
        "camelcase": "4.0.0",
        "debounce": "1.0.0",
        "decamelize": "1.2.0",
        "es6-error": "4.0.2",
        "es6-promisify": "5.0.0",
        "event-to-promise": "0.7.0",
        "firefox-profile": "0.4.8",
        "fx-runner": "1.0.6",
        "git-rev-sync": "1.8.0",
        "minimatch": "3.0.3",
        "mkdirp": "0.5.1",
        "mz": "2.6.0",
        "node-firefox-connect": "1.2.0",
        "node-notifier": "5.0.2",
        "parse-json": "2.2.0",
        "regenerator-runtime": "0.10.1",
        "require-uncached": "1.0.3",
        "sign-addon": "0.2.1",
        "source-map-support": "0.4.11",
        "stream-to-promise": "2.2.0",
        "tmp": "0.0.30",
        "update-notifier": "1.0.3",
        "watchpack": "1.2.0",
        "yargs": "6.6.0",
        "zip-dir": "1.0.2"
    },
    "description": "A command line tool to help build, run, and test web extensions",
    "devDependencies": {
        "babel-core": "6.22.1",
        "babel-eslint": "7.1.0",
        "babel-istanbul": "0.12.0",
        "babel-istanbul-loader": "0.1.0",
        "babel-loader": "6.2.10",
        "babel-plugin-transform-class-properties": "6.18.0",
        "babel-plugin-transform-es2015-modules-commonjs": "6.18.0",
        "babel-plugin-transform-flow-strip-types": "6.22.0",
        "babel-plugin-transform-runtime": "6.15.0",
        "babel-preset-es2015": "6.18.0",
        "babel-preset-stage-2": "6.18.0",
        "chai": "3.5.0",
        "conventional-changelog-cli": "1.2.0",
        "conventional-changelog-lint": "1.1.0",
        "copy-dir": "0.3.0",
        "coveralls": "2.11.16",
        "deepcopy": "0.6.3",
        "eslint-plugin-async-await": "0.0.0",
        "eslint-plugin-flowtype": "2.30.0",
        "eslint-plugin-import": "2.2.0",
        "firefox-client": "0.3.0",
        "flow-bin": "0.38.0",
        "grunt": "1.0.1",
        "grunt-contrib-clean": "1.0.0",
        "grunt-contrib-copy": "1.0.0",
        "grunt-contrib-watch": "1.0.0",
        "grunt-coveralls": "1.0.1",
        "grunt-eslint": "19.0.0",
        "grunt-flowbin": "0.1.7",
        "grunt-mocha-test": "0.13.2",
        "grunt-newer": "1.2.0",
        "grunt-webpack": "1.0.18",
        "load-grunt-configs": "1.0.0",
        "load-grunt-tasks": "3.5.2",
        "mocha": "3.2.0",
        "mocha-multi": "0.10.0",
        "nsp": "2.6.2",
        "object.entries": "1.0.4",
        "object.values": "1.0.4",
        "prettyjson": "1.2.1",
        "sinon": "1.17.7",
        "webpack": "1.14.0",
        "webpack-dev-server": "1.16.2",
        "yauzl": "2.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "fcf1d72b6b1b1c4ba4311a988cb4c5ac598f3b2a",
        "tarball": "https://registry.npmjs.org/web-ext/-/web-ext-1.8.1.tgz"
    },
    "engine-strict": true,
    "engines": {
        "node": ">=4.0.0",
        "npm": ">=3.0.0"
    },
    "gitHead": "d37cb13039e2667aa3bf01c86b357a6c6d80993f",
    "homepage": "https://github.com/mozilla/web-ext",
    "keywords": [
        "web",
        "extensions",
        "web extensions",
        "browser extensions",
        "firefox",
        "mozilla",
        "add-ons",
        "google",
        "chrome",
        "opera"
    ],
    "license": "MPL-2.0",
    "main": "dist/web-ext.js",
    "maintainers": [
        {
            "name": "addons-robot"
        },
        {
            "name": "kumar303"
        }
    ],
    "name": "web-ext",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/mozilla/web-ext.git"
    },
    "scripts": {
        "build": "grunt build",
        "changelog": "conventional-changelog -p angular -u",
        "changelog-lint": "conventional-changelog-lint --from master",
        "changelog-lint-from-stdin": "conventional-changelog-lint",
        "flow-check": "grunt flowbin:check",
        "lint": "grunt lint",
        "nsp-check": "nsp check -o summary",
        "publish-coverage": "grunt coveralls",
        "start": "grunt develop",
        "test": "grunt test",
        "travis-pr-title-lint": "grunt travis-pr-title-lint"
    },
    "version": "1.8.1",
    "yargs": {
        "boolean-negation": false
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
