# npmdoc-mach

#### api documentation for  mach (v1.3.8)  [![npm package](https://img.shields.io/npm/v/npmdoc-mach.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mach) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mach.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mach)

#### HTTP for JavaScript

[![NPM](https://nodei.co/npm/mach.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mach)

- [https://npmdoc.github.io/node-npmdoc-mach/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mach/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mach/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mach/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mach/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mach/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "mach",
    "version": "1.3.8",
    "description": "HTTP for JavaScript",
    "main": "lib",
    "scripts": {
        "build": "scripts/build.sh",
        "test": "jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'",
        "test-browser": "karma start",
        "release": "scripts/release.sh"
    },
    "dependencies": {
        "bodec": "^1.1.0",
        "bufferedstream": "^3.1.1",
        "describe-property": "^1.0.0",
        "object-assign": "^2.0.0",
        "qs": "^2.3.3",
        "strftime": "^0.9.0",
        "when": "^3.6.4"
    },
    "optionalDependencies": {
        "redis": "~0.11.0"
    },
    "devDependencies": {
        "babel": "^4.5.5",
        "babel-core": "^4.5.5",
        "babel-loader": "^4.0.0",
        "expect": "^1.3.0",
        "jshint": "^2.5.10",
        "karma": "^0.12.28",
        "karma-chrome-launcher": "^0.1.7",
        "karma-cli": "0.0.4",
        "karma-mocha": "^0.1.10",
        "karma-sourcemap-loader": "^0.3.2",
        "karma-webpack": "^1.3.1",
        "mocha": "^2.0.1",
        "webpack": "^1.4.15",
        "webpack-dev-server": "^1.6.6"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/mjackson/mach"
    },
    "keywords": [
        "web",
        "server",
        "http",
        "strata",
        "jsgi",
        "then",
        "promise",
        "promises"
    ],
    "engines": {
        "node": "0.10.x"
    },
    "author": "Michael Jackson",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/mjackson/mach/issues"
    },
    "browser": {
        "./modules/extensions/default.js": "./modules/extensions/default-browser.js",
        "./modules/utils/File.js": "./modules/utils/File-browser.js",
        "./modules/utils/parseURL.js": "./modules/utils/parseURL-browser.js",
        "./modules/utils/readFile.js": "./modules/utils/readFile-browser.js",
        "./modules/utils/sendRequest.js": "./modules/utils/sendRequest-browser.js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
