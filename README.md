# npmtest-codelyzer

#### basic test coverage for  [codelyzer (v2.1.1)](https://github.com/mgechev/codelyzer#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-codelyzer.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-codelyzer) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-codelyzer.svg)](https://travis-ci.org/npmtest/node-npmtest-codelyzer)

#### Linting for Angular applications, following angular.io/styleguide.

[![NPM](https://nodei.co/npm/codelyzer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/codelyzer)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-codelyzer/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-codelyzer/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-codelyzer/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-codelyzer/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-codelyzer/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-codelyzer/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-codelyzer/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-codelyzer/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-codelyzer/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-codelyzer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-codelyzer/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-codelyzer/build/test-report.html](https://npmtest.github.io/node-npmtest-codelyzer/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-codelyzer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-codelyzer/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-codelyzer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-codelyzer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-codelyzer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-codelyzer/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-codelyzer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-codelyzer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "codelyzer",
    "version": "2.1.1",
    "description": "Linting for Angular applications, following angular.io/styleguide.",
    "main": "index.js",
    "contributors": [
        "Minko Gechev <mgechev@gmail.com>",
        "Preslav Semov <preslavsemov@gmail.com>"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mgechev/codelyzer.git"
    },
    "keywords": [
        "Angular",
        "style guide",
        "styleguide",
        "nglint",
        "codelyzer",
        "lint",
        "tslint"
    ],
    "author": {
        "name": "Minko Gechev"
    },
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/mgechev/codelyzer/issues"
    },
    "homepage": "https://github.com/mgechev/codelyzer#readme",
    "peerDependencies": {
        "tslint": "^4.0.0",
        "@angular/compiler": "^2.3.1 || >=4.0.0-beta <5.0.0",
        "@angular/core": "^2.3.1 || >=4.0.0-beta <5.0.0"
    },
    "dependencies": {
        "app-root-path": "^2.0.1",
        "css-selector-tokenizer": "^0.7.0",
        "cssauron": "^1.4.0",
        "semver-dsl": "^1.0.1",
        "source-map": "^0.5.6",
        "sprintf-js": "^1.0.3"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
