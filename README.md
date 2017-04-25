# npmtest-jsoneditor

#### basic test coverage for  [jsoneditor (v5.6.0)](https://github.com/josdejong/jsoneditor)  [![npm package](https://img.shields.io/npm/v/npmtest-jsoneditor.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jsoneditor) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jsoneditor.svg)](https://travis-ci.org/npmtest/node-npmtest-jsoneditor)

#### A web-based tool to view, edit, format, and validate JSON

[![NPM](https://nodei.co/npm/jsoneditor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jsoneditor)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jsoneditor/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsoneditor/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jsoneditor/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jsoneditor/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jsoneditor/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-jsoneditor/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-jsoneditor/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jsoneditor/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jsoneditor/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jsoneditor/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jsoneditor/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsoneditor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jsoneditor/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jsoneditor/build/test-report.html](https://npmtest.github.io/node-npmtest-jsoneditor/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jsoneditor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jsoneditor/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jsoneditor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jsoneditor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jsoneditor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jsoneditor/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jsoneditor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jsoneditor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jos de Jong"
    },
    "bugs": {
        "url": "https://github.com/josdejong/jsoneditor/issues"
    },
    "dependencies": {
        "ajv": "4.11.6",
        "brace": "0.10.0",
        "javascript-natural-sort": "0.7.1"
    },
    "description": "A web-based tool to view, edit, format, and validate JSON",
    "devDependencies": {
        "gulp": "3.9.1",
        "gulp-clean-css": "3.0.4",
        "gulp-concat-css": "2.3.0",
        "gulp-shell": "0.6.3",
        "gulp-util": "3.0.8",
        "json-loader": "0.5.4",
        "mkdirp": "0.5.1",
        "mocha": "3.2.0",
        "uglify-js": "2.8.22",
        "webpack": "1.12.14"
    },
    "directories": {},
    "dist": {
        "shasum": "b7df2ad1289486b0b3b0368da8b551e0f0b31ed6",
        "tarball": "https://registry.npmjs.org/jsoneditor/-/jsoneditor-5.6.0.tgz"
    },
    "gitHead": "56c450bf0f440979383dfb25b0654aca5c6cee4f",
    "homepage": "https://github.com/josdejong/jsoneditor",
    "license": "Apache-2.0",
    "main": "./index",
    "maintainers": [
        {
            "name": "josdejong"
        }
    ],
    "name": "jsoneditor",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/josdejong/jsoneditor.git"
    },
    "scripts": {
        "build": "gulp",
        "test": "mocha test",
        "watch": "gulp watch"
    },
    "tags": [
        "json",
        "editor",
        "viewer",
        "formatter"
    ],
    "version": "5.6.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
