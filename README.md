# npmdoc-find-rss

#### api documentation for  find-rss (v1.6.4)  [![npm package](https://img.shields.io/npm/v/npmdoc-find-rss.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-find-rss) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-find-rss.svg)](https://travis-ci.org/npmdoc/node-npmdoc-find-rss)

#### Find RSS/ATOM feed by HTML/URL

[![NPM](https://nodei.co/npm/find-rss.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/find-rss)

- [https://npmdoc.github.io/node-npmdoc-find-rss/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-find-rss/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-find-rss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-find-rss/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-find-rss/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-find-rss/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "find-rss",
    "description": "Find RSS/ATOM feed by HTML/URL",
    "version": "1.6.4",
    "author": "nikezono",
    "dependencies": {
        "async": "^2.1.4",
        "feedparser": "^2.1.0",
        "htmlparser2": "^3.9.2",
        "iconv-lite": "^0.4.15",
        "jschardet": "^1.4.1",
        "request": "^2.79.0"
    },
    "devDependencies": {
        "codeclimate-test-reporter": "*",
        "coffee-errors": "*",
        "coffee-script": "*",
        "coffeelint": "^1.16.0",
        "grunt": "*",
        "grunt-coffeelint": "*",
        "grunt-contrib-clean": "*",
        "grunt-contrib-coffee": "*",
        "grunt-contrib-copy": "*",
        "grunt-contrib-watch": "*",
        "grunt-istanbul": "*",
        "grunt-mocha-test": "*",
        "grunt-notify": "*",
        "istanbul": "*",
        "mocha": "*",
        "nock": "^9.0.5",
        "underscore": "*"
    },
    "keywords": [
        "rss",
        "atom",
        "find",
        "feed"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/nikezono/node-find-rss"
    },
    "main": "lib/find-rss.js",
    "scripts": {
        "test": "grunt test",
        "prepublish": "grunt coffee"
    },
    "engines": {
        "node": "*"
    },
    "directories": {
        "test": "test"
    },
    "license": "BSD"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
