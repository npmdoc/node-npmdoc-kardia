# npmdoc-kardia

#### api documentation for  [kardia (v0.10.0)](https://github.com/pipedrive/kardia)  [![npm package](https://img.shields.io/npm/v/npmdoc-kardia.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-kardia) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-kardia.svg)](https://travis-ci.org/npmdoc/node-npmdoc-kardia)

#### A humane process status API module to expose any operational/internal indicators of any Node.js process for status aggregation and monitoring. JSON format over HTTP protocol.

[![NPM](https://nodei.co/npm/kardia.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/kardia)

- [https://npmdoc.github.io/node-npmdoc-kardia/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-kardia/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-kardia/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-kardia/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-kardia/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-kardia/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "kardia",
    "version": "0.10.0",
    "description": "A humane process status API module to expose any operational/internal indicators of any Node.js process for status aggregation and monitoring. JSON format over HTTP protocol.",
    "main": "index.js",
    "scripts": {
        "test": "mocha test",
        "coverage": "npm run-script test-travis",
        "sonar": "npm run-script test-travis",
        "test-travis": "./node_modules/istanbul/lib/cli.js cover ./node_modules/mocha/bin/_mocha -- -R spec ./test/*"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/pipedrive/kardia.git"
    },
    "keywords": [
        "status",
        "status",
        "page",
        "process",
        "monitoring",
        "healthcheck",
        "microservices"
    ],
    "author": "Pipedrive Inc",
    "contributors": [
        "Martin Tajur",
        "Andris Reinman",
        "Timur Hassanov"
    ],
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/pipedrive/kardia/issues"
    },
    "homepage": "https://github.com/pipedrive/kardia",
    "devDependencies": {
        "async": "^1.0.0",
        "coveralls": "^2.11.4",
        "istanbul": "^0.3.22",
        "mocha": "^2.3.3",
        "proxyquire": "^1.7.4",
        "request": "^2.56.0",
        "should": "^8.3.1",
        "should-sinon": "0.0.5",
        "sinon": "^1.17.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
