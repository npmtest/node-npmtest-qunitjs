# npmtest-qunitjs

#### basic test coverage for  [qunitjs (v2.3.2)](https://qunitjs.com)  [![npm package](https://img.shields.io/npm/v/npmtest-qunitjs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-qunitjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-qunitjs.svg)](https://travis-ci.org/npmtest/node-npmtest-qunitjs)

#### An easy-to-use JavaScript Unit Testing framework.

[![NPM](https://nodei.co/npm/qunitjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/qunitjs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-qunitjs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-qunitjs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-qunitjs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-qunitjs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-qunitjs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-qunitjs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-qunitjs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-qunitjs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-qunitjs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-qunitjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-qunitjs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-qunitjs/build/test-report.html](https://npmtest.github.io/node-npmtest-qunitjs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-qunitjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-qunitjs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-qunitjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-qunitjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-qunitjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-qunitjs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-qunitjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-qunitjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "jQuery Foundation and other contributors",
        "url": "https://github.com/qunitjs/qunit/blob/2.3.2/AUTHORS.txt"
    },
    "bin": {
        "qunit": "bin/qunit"
    },
    "bugs": {
        "url": "https://github.com/qunitjs/qunit/issues"
    },
    "commitplease": {
        "components": [
            "All",
            "Assert",
            "Build",
            "CLI",
            "CSS",
            "Core",
            "Docs",
            "Dump",
            "HTML Reporter",
            "Readme",
            "Test",
            "Tests"
        ]
    },
    "dependencies": {
        "chokidar": "1.6.1",
        "commander": "2.9.0",
        "exists-stat": "1.0.0",
        "findup-sync": "^0.4.3",
        "js-reporters": "1.2.0",
        "walk-sync": "0.3.1"
    },
    "description": "An easy-to-use JavaScript Unit Testing framework.",
    "devDependencies": {
        "async": "2.1.4",
        "babel-plugin-external-helpers": "6.18.0",
        "babel-preset-es2015": "6.18.0",
        "browserstack-runner": "0.4.4",
        "co": "4.6.0",
        "commitplease": "2.7.6",
        "eslint-config-jquery": "1.0.0",
        "eslint-plugin-html": "1.7.0",
        "eslint-plugin-qunit": "2.3.0",
        "execa": "0.6.1",
        "fixturify": "0.3.3",
        "fs-extra": "1.0.0",
        "grunt": "1.0.1",
        "grunt-cli": "1.2.0",
        "grunt-concurrent": "2.3.1",
        "grunt-contrib-connect": "1.0.2",
        "grunt-contrib-copy": "1.0.0",
        "grunt-contrib-qunit": "1.3.0",
        "grunt-contrib-watch": "1.0.0",
        "grunt-coveralls": "1.0.1",
        "grunt-eslint": "19.0.0",
        "grunt-git-authors": "3.2.0",
        "grunt-istanbul": "0.7.2",
        "grunt-rollup": "1.0.1",
        "grunt-search": "0.1.8",
        "load-grunt-tasks": "3.5.2",
        "npm-reporter": "file:./test/cli/fixtures/npm-reporter",
        "requirejs": "2.3.2",
        "rollup-plugin-babel": "2.6.1"
    },
    "directories": {},
    "dist": {
        "shasum": "938ce24250aa3717b90b47598f1429b10343d85a",
        "tarball": "https://registry.npmjs.org/qunitjs/-/qunitjs-2.3.2.tgz"
    },
    "engines": {
        "node": "4.* || 6.* || 7.*"
    },
    "files": [
        "bin/",
        "qunit/qunit.js",
        "qunit/qunit.css",
        "LICENSE.txt"
    ],
    "gitHead": "63ce0bd6cee173345173a2aa928ea29b89df2a09",
    "homepage": "https://qunitjs.com",
    "keywords": [
        "testing",
        "unit",
        "jquery"
    ],
    "license": "MIT",
    "main": "qunit/qunit.js",
    "maintainers": [
        {
            "name": "gibson042"
        },
        {
            "name": "jzaefferer"
        },
        {
            "name": "leobalter"
        },
        {
            "name": "trentmwillis"
        }
    ],
    "name": "qunitjs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/qunitjs/qunit.git"
    },
    "scripts": {
        "browserstack": "grunt build && sh build/run-browserstack.sh",
        "build": "grunt build",
        "coverage": "grunt coverage",
        "test": "grunt",
        "test:cli": "grunt build && npm link && qunit test/cli/*.js"
    },
    "title": "QUnit",
    "version": "2.3.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
