# npmtest-grunt-update-json

#### basic test coverage for  [grunt-update-json (v0.2.2)](https://github.com/andreaspizsa/grunt-update-json)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-update-json.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-update-json) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-update-json.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-update-json)

#### Merge parts from one or more JSON files together. I use `grunt-update-json` to keep my `Bower.json` and `component.json` in sync with `package.json`.

[![NPM](https://nodei.co/npm/grunt-update-json.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-update-json)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-update-json/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-update-json/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-update-json/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-update-json/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-update-json/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-update-json/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-update-json/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-update-json/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-update-json/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-update-json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-update-json/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-update-json/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-update-json/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-update-json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-update-json/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-update-json/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-update-json/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-update-json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-update-json/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-update-json/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-update-json/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "grunt-update-json",
    "description": "Merge parts from one or more JSON files together. I use 'grunt-update-json' to keep my 'Bower.json' and 'component.json' in sync with 'package.json'.",
    "version": "0.2.2",
    "homepage": "https://github.com/andreaspizsa/grunt-update-json",
    "author": "Andreas Pizsa (http://github.com/AndreasPizsa)",
    "contributors": [
        "bollwyvl (https://github.com/bollwyvl)",
        "Vasyl Zuzyak (https://github.com/ZuBB)",
        "Andrew Dryga (https://github.com/AndrewDryga)"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/AndreasPizsa/grunt-update-json.git"
    },
    "bugs": {
        "url": "https://github.com/AndreasPizsa/grunt-update-json/issues"
    },
    "license": "MIT",
    "main": "Gruntfile.js",
    "engines": {
        "node": ">= 0.8.0"
    },
    "scripts": {
        "test": "grunt"
    },
    "devDependencies": {
        "blanket": "~1.1.6",
        "chai": "~1.9.1",
        "grunt": "~0.4.2",
        "grunt-contrib-clean": "~0.4.0",
        "grunt-contrib-copy": "~0.5.0",
        "grunt-contrib-jshint": "~0.6.0",
        "grunt-contrib-watch": "~0.6.1",
        "grunt-mocha-cov": "~0.2.1",
        "load-grunt-tasks": "~0.4.0",
        "mocha-term-cov-reporter": "~0.2.0",
        "should": "~3.3.1"
    },
    "peerDependencies": {
        "grunt": "~0.4.2"
    },
    "keywords": [
        "gruntplugin",
        "json",
        "json pointer",
        "merge",
        "update",
        "sync",
        "bower.json",
        "component.json",
        "composer.json"
    ],
    "dependencies": {
        "JSONPath": "~0.10.0",
        "json-pointer": "~0.1.0",
        "json-stable-stringify": "^1.0.0",
        "lodash": "~2.4.1"
    },
    "config": {
        "blanket": {
            "pattern": [
                "grunt-update-json/tasks"
            ]
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
