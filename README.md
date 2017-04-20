# npmtest-googlemaps

#### basic test coverage for  googlemaps (v1.12.0)  [![npm package](https://img.shields.io/npm/v/npmtest-googlemaps.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-googlemaps) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-googlemaps.svg)](https://travis-ci.org/npmtest/node-npmtest-googlemaps)

#### A simple way to query the Google Maps API from Node.js

[![NPM](https://nodei.co/npm/googlemaps.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/googlemaps)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-googlemaps/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-googlemaps/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-googlemaps/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-googlemaps/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-googlemaps/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-googlemaps/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-googlemaps/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-googlemaps/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-googlemaps/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-googlemaps/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-googlemaps/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-googlemaps/build/test-report.html](https://npmtest.github.io/node-npmtest-googlemaps/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-googlemaps/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-googlemaps/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-googlemaps/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-googlemaps/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-googlemaps/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-googlemaps/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-googlemaps/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-googlemaps/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "googlemaps",
    "version": "1.12.0",
    "main": "lib/index",
    "description": "A simple way to query the Google Maps API from Node.js",
    "license": "MIT",
    "author": {
        "name": "Colin Kennedy",
        "url": "http://moshen.net"
    },
    "keywords": [
        "map",
        "geo",
        "google",
        "api",
        "googlemaps",
        "google maps",
        "google-maps",
        "node google maps"
    ],
    "repository": {
        "type": "git",
        "url": "http://github.com/moshen/node-googlemaps"
    },
    "devDependencies": {
        "mocha": "^2.4.5",
        "should": "^8.2.2"
    },
    "engines": {
        "node": ">=0.3.6"
    },
    "dependencies": {
        "check-types": "~1.3.2",
        "qs": "^4.0.0",
        "request": "^2.79.0",
        "waitress": ">=0.0.2"
    },
    "scripts": {
        "all-tests": "./node_modules/.bin/mocha test/unit test/integration",
        "test": "./node_modules/.bin/mocha test/unit",
        "integration-test": "./node_modules/.bin/mocha test/integration"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
