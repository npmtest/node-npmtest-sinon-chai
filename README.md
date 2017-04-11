# test coverage for  [sinon-chai (v2.9.0)](https://github.com/domenic/sinon-chai#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-sinon-chai.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sinon-chai) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sinon-chai.svg)](https://travis-ci.org/npmtest/node-npmtest-sinon-chai)
#### Extends Chai with assertions for the Sinon.JS mocking framework.

[![NPM](https://nodei.co/npm/sinon-chai.png?downloads=true)](https://www.npmjs.com/package/sinon-chai)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sinon-chai/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sinon-chai/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sinon-chai/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sinon-chai/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sinon-chai/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sinon-chai/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sinon-chai/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sinon-chai/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-sinon-chai/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-sinon-chai/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-sinon-chai%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sinon-chai/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sinon-chai/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-sinon-chai%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sinon-chai/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sinon-chai/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sinon-chai/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Domenic Denicola",
        "email": "d@domenic.me",
        "url": "https://domenic.me/"
    },
    "bugs": {
        "url": "https://github.com/domenic/sinon-chai/issues"
    },
    "dependencies": {},
    "description": "Extends Chai with assertions for the Sinon.JS mocking framework.",
    "devDependencies": {
        "chai": "^3.0.0",
        "coffee-script": "~1.8.0",
        "istanbul": "~0.3.2",
        "jshint": "^2.5.6",
        "mocha": "^1.21.4",
        "opener": "^1.4.0",
        "sinon": "^2.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "34d820042bc9661a14527130d401eb462c49bb84",
        "tarball": "https://registry.npmjs.org/sinon-chai/-/sinon-chai-2.9.0.tgz"
    },
    "files": [
        "lib"
    ],
    "gitHead": "8f8c5a0fe1225c5781ff83075b646f890399a142",
    "homepage": "https://github.com/domenic/sinon-chai#readme",
    "keywords": [
        "chai",
        "chai-plugin",
        "browser",
        "vendor",
        "mocks-and-spies",
        "sinon",
        "testing",
        "spies",
        "stubs",
        "mocks"
    ],
    "license": "(BSD-2-Clause OR WTFPL)",
    "main": "./lib/sinon-chai.js",
    "maintainers": [
        {
            "name": "domenic",
            "email": "domenic@domenicdenicola.com"
        }
    ],
    "name": "sinon-chai",
    "optionalDependencies": {},
    "peerDependencies": {
        "chai": ">=1.9.2 <4",
        "sinon": "^1.4.0 || ^2.1.0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/domenic/sinon-chai.git"
    },
    "scripts": {
        "cover": "istanbul cover node_modules/mocha/bin/_mocha && opener ./coverage/lcov-report/lib/sinon-chai.js.html",
        "lint": "jshint ./lib",
        "test": "mocha",
        "test-travis": "npm install chai@$CHAI_VERSION && npm install sinon@$SINON_VERSION && npm test"
    },
    "version": "2.9.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
