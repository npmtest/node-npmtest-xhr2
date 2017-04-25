# npmtest-xhr2

#### basic test coverage for  [xhr2 (v0.1.4)](https://github.com/pwnall/node-xhr2)  [![npm package](https://img.shields.io/npm/v/npmtest-xhr2.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-xhr2) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-xhr2.svg)](https://travis-ci.org/npmtest/node-npmtest-xhr2)

#### XMLHttpRequest emulation for node.js

[![NPM](https://nodei.co/npm/xhr2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/xhr2)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-xhr2/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-xhr2/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-xhr2/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-xhr2/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-xhr2/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-xhr2/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-xhr2/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-xhr2/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-xhr2/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-xhr2/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-xhr2/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-xhr2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-xhr2/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-xhr2/build/test-report.html](https://npmtest.github.io/node-npmtest-xhr2/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-xhr2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-xhr2/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-xhr2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-xhr2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-xhr2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-xhr2/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-xhr2/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-xhr2/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Victor Costan",
        "url": "http://www.costan.us"
    },
    "browser": "lib/browser.js",
    "bugs": {
        "url": "https://github.com/pwnall/node-xhr2/issues"
    },
    "contributors": [
        {
            "name": "Daniel Friedman"
        },
        {
            "name": "Francois-Xavier Kowalski"
        }
    ],
    "dependencies": {},
    "description": "XMLHttpRequest emulation for node.js",
    "devDependencies": {
        "async": ">= 1.4.2",
        "chai": ">= 3.2.0",
        "codo": ">= 2.0.11",
        "coffee-script": ">= 1.9.3",
        "express": ">= 4.13.3",
        "glob": ">= 5.0.14",
        "mocha": ">= 2.2.5",
        "open": ">= 0.0.5",
        "remove": ">= 0.1.5",
        "sinon": ">= 1.15.4",
        "sinon-chai": ">= 2.8.0"
    },
    "directories": {
        "doc": "doc",
        "lib": "lib",
        "src": "src",
        "test": "test"
    },
    "dist": {
        "shasum": "7f87658847716db5026323812f818cadab387a5f",
        "tarball": "https://registry.npmjs.org/xhr2/-/xhr2-0.1.4.tgz"
    },
    "engines": {
        "node": ">= 0.6"
    },
    "gitHead": "f81390c2de5db928726f3b042ffd4a56eb6c2326",
    "homepage": "https://github.com/pwnall/node-xhr2",
    "keywords": [
        "xhr",
        "xmlhttprequest",
        "ajax",
        "browser"
    ],
    "license": "MIT",
    "main": "lib/xhr2.js",
    "maintainers": [
        {
            "name": "pwnall"
        }
    ],
    "name": "xhr2",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pwnall/node-xhr2.git"
    },
    "scripts": {
        "prepublish": "node_modules/coffee-script/bin/cake build",
        "test": "node_modules/coffee-script/bin/cake test"
    },
    "version": "0.1.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
