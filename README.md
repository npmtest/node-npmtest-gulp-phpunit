# npmtest-gulp-phpunit

#### test coverage for  [gulp-phpunit (v0.22.2)](https://github.com/mikeerickson/gulp-phpunit#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-phpunit.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-phpunit) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-phpunit.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-phpunit)

#### PHPUnit plugin for Gulp

[![NPM](https://nodei.co/npm/gulp-phpunit.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-phpunit)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-phpunit/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-phpunit/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-phpunit/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-phpunit/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-phpunit/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-phpunit/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-phpunit/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-phpunit/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-phpunit/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-phpunit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-phpunit/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-phpunit/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-phpunit/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-phpunit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-phpunit/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-phpunit/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-phpunit/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-phpunit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-phpunit/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-phpunit/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-phpunit/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "codedungeon"
    },
    "bugs": {
        "url": "https://github.com/mikeerickson/gulp-phpunit/issues"
    },
    "dependencies": {
        "chalk": "1.1.3",
        "gulp-messenger": "0.26.0",
        "gulp-notify": "3.0.0",
        "gulp-util": "3.0.8",
        "lodash": "^4.15.0",
        "map-stream": "~0.0.4",
        "node-notifier": "5.0.2",
        "shelljs": "0.7.6"
    },
    "description": "PHPUnit plugin for Gulp",
    "devDependencies": {
        "chai": "3.5.0",
        "eslint": "3.14.1",
        "esprima": "3.1.3",
        "gulp": "3.9.1",
        "gulp-mocha": "3.0.1",
        "gulp-shell": "0.5.2",
        "lint-staged": "3.2.8",
        "mocha": "3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "cd147deaf4a60991673e0e48d79d80aa6a69df48",
        "tarball": "https://registry.npmjs.org/gulp-phpunit/-/gulp-phpunit-0.22.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "1b2655dc6af81699ff11adfcb6aecc900e9256c8",
    "homepage": "https://github.com/mikeerickson/gulp-phpunit#readme",
    "keywords": [
        "gulpplugin",
        "phpunit",
        "gulp",
        "gulp-phpunit"
    ],
    "license": "MIT",
    "lint-staged": {
        "*.js": "eslint"
    },
    "main": "index.js",
    "maintainers": [
        {
            "name": "codedungeon"
        }
    ],
    "name": "gulp-phpunit",
    "optionalDependencies": {},
    "pre-commit": "lint-staged",
    "repository": {
        "type": "git",
        "url": "git://github.com/mikeerickson/gulp-phpunit.git"
    },
    "reveal": true,
    "scripts": {
        "eslint": "eslint \"./**/*.js\"",
        "lint-staged": "lint-staged",
        "test": "mocha --reporter spec"
    },
    "version": "0.22.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
