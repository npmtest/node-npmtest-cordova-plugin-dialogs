# npmtest-cordova-plugin-dialogs

#### basic test coverage for  cordova-plugin-dialogs (v1.3.2)  [![npm package](https://img.shields.io/npm/v/npmtest-cordova-plugin-dialogs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cordova-plugin-dialogs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cordova-plugin-dialogs.svg)](https://travis-ci.org/npmtest/node-npmtest-cordova-plugin-dialogs)

#### Cordova Notification Plugin

[![NPM](https://nodei.co/npm/cordova-plugin-dialogs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cordova-plugin-dialogs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cordova-plugin-dialogs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cordova-plugin-dialogs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cordova-plugin-dialogs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cordova-plugin-dialogs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cordova-plugin-dialogs/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-cordova-plugin-dialogs/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-cordova-plugin-dialogs/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cordova-plugin-dialogs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cordova-plugin-dialogs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cordova-plugin-dialogs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cordova-plugin-dialogs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cordova-plugin-dialogs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cordova-plugin-dialogs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cordova-plugin-dialogs/build/test-report.html](https://npmtest.github.io/node-npmtest-cordova-plugin-dialogs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cordova-plugin-dialogs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cordova-plugin-dialogs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cordova-plugin-dialogs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cordova-plugin-dialogs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cordova-plugin-dialogs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cordova-plugin-dialogs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cordova-plugin-dialogs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cordova-plugin-dialogs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "cordova-plugin-dialogs",
    "version": "1.3.2",
    "description": "Cordova Notification Plugin",
    "types": "./types/index.d.ts",
    "cordova": {
        "id": "cordova-plugin-dialogs",
        "platforms": [
            "firefoxos",
            "android",
            "browser",
            "amazon-fireos",
            "ubuntu",
            "ios",
            "blackberry10",
            "wp7",
            "wp8",
            "windows8",
            "windows"
        ]
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/apache/cordova-plugin-dialogs"
    },
    "keywords": [
        "cordova",
        "notification",
        "ecosystem:cordova",
        "cordova-firefoxos",
        "cordova-android",
        "cordova-browser",
        "cordova-amazon-fireos",
        "cordova-ubuntu",
        "cordova-ios",
        "cordova-blackberry10",
        "cordova-wp7",
        "cordova-wp8",
        "cordova-windows8",
        "cordova-windows"
    ],
    "scripts": {
        "test": "npm run jshint",
        "jshint": "node node_modules/jshint/bin/jshint www && node node_modules/jshint/bin/jshint src && node node_modules/jshint/bin/jshint tests"
    },
    "author": "Apache Software Foundation",
    "license": "Apache-2.0",
    "engines": {
        "cordovaDependencies": {
            "2.0.0": {
                "cordova": ">100"
            }
        }
    },
    "devDependencies": {
        "jshint": "^2.6.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
