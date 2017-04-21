# npmtest-preboot

#### basic test coverage for  [preboot (v4.5.2)](https://github.com/angular/preboot)  [![npm package](https://img.shields.io/npm/v/npmtest-preboot.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-preboot) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-preboot.svg)](https://travis-ci.org/npmtest/node-npmtest-preboot)

#### Record and play back browser events

[![NPM](https://nodei.co/npm/preboot.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/preboot)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-preboot/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-preboot/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-preboot/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-preboot/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-preboot/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-preboot/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-preboot/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-preboot/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-preboot/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-preboot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-preboot/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-preboot/build/test-report.html](https://npmtest.github.io/node-npmtest-preboot/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-preboot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-preboot/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-preboot/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-preboot/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-preboot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-preboot/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-preboot/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-preboot/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "preboot",
    "version": "4.5.2",
    "description": "Record and play back browser events",
    "main": "__build/src/node/preboot_node.js",
    "browser": "__dist/preboot_browser.js",
    "typings": "preboot.d.ts",
    "scripts": {
        "prepublish": "gulp dist"
    },
    "author": "Jeff Whelpley",
    "license": "MIT",
    "contributors": [
        "Tobias Bosch <tbosch@google.com>",
        "PatrickJS <github@gdi2290.com>",
        "Jeff Whelpley <jeff@gethuman.com>"
    ],
    "devDependencies": {
        "@types/es6-promise": "0.0.29",
        "@types/jasmine": "^2.2.31",
        "@types/node": "^6.0.33",
        "connect-livereload": "^0.5.4",
        "del": "^2.2.1",
        "express": "^4.14.0",
        "gulp": "^3.9.1",
        "gulp-jasmine": "^2.4.0",
        "gulp-livereload": "^3.8.1",
        "gulp-rename": "^1.2.2",
        "gulp-replace": "^0.5.4",
        "gulp-size": "^2.1.0",
        "gulp-tslint": "^6.0.2",
        "gulp-typedoc": "^2.0.0",
        "gulp-typescript": "^2.13.6",
        "gulp-uglify": "^2.0.0",
        "open": "0.0.5",
        "serve-static": "^1.11.1",
        "tslint": "^3.14.0",
        "typedoc": "^0.4.4",
        "typescript": "2.1.0-dev.20160801"
    },
    "dependencies": {},
    "repository": {
        "type": "git",
        "url": "https://github.com/angular/preboot"
    },
    "bugs": {
        "url": "https://github.com/angular/preboot/issues"
    },
    "homepage": "https://github.com/angular/preboot"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
