# npmdoc-grunt-jscs

#### api documentation for  [grunt-jscs (v3.0.1)](https://github.com/jscs-dev/grunt-jscs)  [![npm package](https://img.shields.io/npm/v/npmdoc-grunt-jscs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-grunt-jscs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-grunt-jscs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-grunt-jscs)

#### Grunt task for checking JavaScript Code Style with jscs.

[![NPM](https://nodei.co/npm/grunt-jscs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-jscs)

- [https://npmdoc.github.io/node-npmdoc-grunt-jscs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-jscs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-jscs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-jscs/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-grunt-jscs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-grunt-jscs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "grunt-jscs",
    "description": "Grunt task for checking JavaScript Code Style with jscs.",
    "version": "3.0.1",
    "author": "Gustavo Henke <gustavo@injoin.com.br>",
    "license": "MIT",
    "homepage": "https://github.com/jscs-dev/grunt-jscs",
    "repository": {
        "type": "git",
        "url": "https://github.com/jscs-dev/grunt-jscs.git"
    },
    "bugs": {
        "url": "https://github.com/jscs-dev/grunt-jscs/issues"
    },
    "dependencies": {
        "hooker": "~0.2.3",
        "jscs": "~3.0.5",
        "lodash": "~4.6.1",
        "vow": "~0.4.1"
    },
    "devDependencies": {
        "grunt": "1.0.1",
        "grunt-contrib-jshint": "~1.0.0",
        "grunt-contrib-nodeunit": "~1.0.0",
        "load-grunt-tasks": "^3.4.0",
        "time-grunt": "~1.3.0"
    },
    "keywords": [
        "gruntplugin",
        "jscs",
        "code style",
        "checker"
    ],
    "engines": {
        "node": ">= 0.10.0"
    },
    "scripts": {
        "test": "grunt test",
        "bump": "npm version patch -m \"Release v%s\"",
        "bump-minor": "npm version minor -m \"Release v%s\"",
        "bump-major": "npm version major -m \"Release v%s\""
    },
    "files": [
        "tasks",
        "LICENSE-MIT"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
