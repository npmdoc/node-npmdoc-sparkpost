# npmdoc-sparkpost

#### api documentation for  [sparkpost (v2.1.2)](https://github.com/SparkPost/node-sparkpost)  [![npm package](https://img.shields.io/npm/v/npmdoc-sparkpost.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-sparkpost) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sparkpost.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sparkpost)

#### A Node.js wrapper for interfacing with your favorite SparkPost APIs

[![NPM](https://nodei.co/npm/sparkpost.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sparkpost)

- [https://npmdoc.github.io/node-npmdoc-sparkpost/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sparkpost/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sparkpost/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sparkpost/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-sparkpost/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-sparkpost/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "sparkpost",
    "version": "2.1.2",
    "description": "A Node.js wrapper for interfacing with your favorite SparkPost APIs",
    "main": "./lib/sparkpost.js",
    "scripts": {
        "coveralls": "cat ./test/reports/lcov.info | coveralls",
        "pretest": "eslint lib/**",
        "test": "istanbul cover --report lcov --dir test/reports/ _mocha --recursive ./test/spec --grep ./test/**/*.spec.js -- --colors --reporter spec",
        "postversion": "git push upstream && git push --tags upstream"
    },
    "keywords": [
        "email",
        "messaging"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/SparkPost/node-sparkpost"
    },
    "author": "Message Systems, Inc.",
    "license": "Apache-2.0",
    "bugs": {
        "url": "https://github.com/SparkPost/node-sparkpost/issues"
    },
    "homepage": "https://github.com/SparkPost/node-sparkpost",
    "devDependencies": {
        "chai": "^3.5.0",
        "chai-as-promised": "^6.0.0",
        "coveralls": "^2.11.15",
        "eslint": "^3.12.2",
        "eslint-config-sparkpost": "^1.3.1",
        "istanbul": "^0.4.5",
        "mocha": "^3.2.0",
        "nock": "^9.0.0",
        "sinon": "^1.17.5",
        "sinon-as-promised": "^4.0.2",
        "sinon-chai": "^2.8.0"
    },
    "dependencies": {
        "lodash": "^4.17.2",
        "request": "^2.79.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
