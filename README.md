# npmdoc-winston-cloudwatch

#### api documentation for  winston-cloudwatch (v1.11.3)  [![npm package](https://img.shields.io/npm/v/npmdoc-winston-cloudwatch.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-winston-cloudwatch) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-winston-cloudwatch.svg)](https://travis-ci.org/npmdoc/node-npmdoc-winston-cloudwatch)

#### Send logs to Amazon Cloudwatch using Winston.

[![NPM](https://nodei.co/npm/winston-cloudwatch.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/winston-cloudwatch)

- [https://npmdoc.github.io/node-npmdoc-winston-cloudwatch/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-winston-cloudwatch/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-winston-cloudwatch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-winston-cloudwatch/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-winston-cloudwatch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-winston-cloudwatch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "winston-cloudwatch",
    "version": "1.11.3",
    "description": "Send logs to Amazon Cloudwatch using Winston.",
    "keywords": [
        "amazon",
        "cloudwatch",
        "winston",
        "logging",
        "log"
    ],
    "main": "index.js",
    "scripts": {
        "test": "make test",
        "coveralls": "./node_modules/.bin/coveralls <./coverage/lcov.info",
        "update-dependencies": "./node_modules/.bin/npm-check-updates -ua && npm install"
    },
    "repository": "https://github.com/lazywithclass/winston-cloudwatch",
    "author": "me@lazywithclass.com",
    "license": "MIT",
    "typings": "typescript/winston-cloudwatch.d.ts",
    "peerDependencies": {
        "winston": "^2.1.1"
    },
    "dependencies": {
        "async": "^2.1.5",
        "aws-sdk": "^2.29.0",
        "chalk": "^1.1.3",
        "lodash": "^4.17.4",
        "proxy-agent": "^2.0.0"
    },
    "devDependencies": {
        "@types/node": "7.0.8",
        "@types/winston": "2.2.0",
        "clarify": "^2.0.0",
        "coveralls": "^2.12.0",
        "istanbul": "^0.4.5",
        "mocha": "^3.2.0",
        "mockery": "^2.0.0",
        "npm-check-updates": "^2.10.3",
        "should": "^11.2.1",
        "sinon": "^2.1.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
