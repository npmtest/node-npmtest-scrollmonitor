# npmtest-scrollmonitor

#### basic test coverage for  [scrollmonitor (v1.2.3)](https://github.com/stutrek/scrollMonitor#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-scrollmonitor.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-scrollmonitor) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-scrollmonitor.svg)](https://travis-ci.org/npmtest/node-npmtest-scrollmonitor)

#### A simple and fast API to monitor DOM elements as you scroll

[![NPM](https://nodei.co/npm/scrollmonitor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/scrollmonitor)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-scrollmonitor/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-scrollmonitor/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-scrollmonitor/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-scrollmonitor/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-scrollmonitor/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-scrollmonitor/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-scrollmonitor/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-scrollmonitor/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-scrollmonitor/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-scrollmonitor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-scrollmonitor/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-scrollmonitor/build/test-report.html](https://npmtest.github.io/node-npmtest-scrollmonitor/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-scrollmonitor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-scrollmonitor/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-scrollmonitor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-scrollmonitor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-scrollmonitor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-scrollmonitor/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-scrollmonitor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-scrollmonitor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Stu Kabakoff"
    },
    "bugs": {
        "url": "https://github.com/stutrek/scrollMonitor/issues"
    },
    "contributors": [
        {
            "name": "Stu Kabakoff"
        },
        {
            "name": "Terrence Lee"
        },
        {
            "name": "Roman Kalyakin"
        }
    ],
    "dependencies": {},
    "description": "A simple and fast API to monitor DOM elements as you scroll",
    "devDependencies": {
        "babel-core": "^6.2.1",
        "babel-loader": "^6.2.0",
        "babel-plugin-transform-es3-member-expression-literals": "^6.8.0",
        "babel-plugin-transform-es3-property-literals": "^6.8.0",
        "babel-plugin-transform-object-assign": "^6.8.0",
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-stage-0": "^6.5.0",
        "sinon": "^1.17.6",
        "testem": "github:stutrek/testem",
        "webpack": "^1.13.1"
    },
    "directories": {},
    "dist": {
        "shasum": "87bf912ca28da64796f529e8129fa4a9b106fb74",
        "tarball": "https://registry.npmjs.org/scrollmonitor/-/scrollmonitor-1.2.3.tgz"
    },
    "gitHead": "46993cd5eb48fc4bafa1d20d77c958dd09d11d35",
    "homepage": "https://github.com/stutrek/scrollMonitor#readme",
    "keywords": [
        "scroll",
        "dom"
    ],
    "license": "MIT",
    "main": "./scrollMonitor.js",
    "maintainers": [
        {
            "name": "sakabako"
        }
    ],
    "name": "scrollmonitor",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/stutrek/scrollMonitor.git"
    },
    "scripts": {
        "start": "webpack; testem",
        "test": "webpack; testem ci"
    },
    "spm": {
        "main": "scrollMonitor.js"
    },
    "version": "1.2.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
