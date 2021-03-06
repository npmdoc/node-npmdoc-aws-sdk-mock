# npmdoc-aws-sdk-mock

#### basic api documentation for  [aws-sdk-mock (v1.7.0)](https://github.com/dwyl/aws-sdk-mock#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-aws-sdk-mock.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-aws-sdk-mock) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-aws-sdk-mock.svg)](https://travis-ci.org/npmdoc/node-npmdoc-aws-sdk-mock)

#### Functions to mock the JavaScript aws-sdk

[![NPM](https://nodei.co/npm/aws-sdk-mock.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/aws-sdk-mock)

- [https://npmdoc.github.io/node-npmdoc-aws-sdk-mock/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-aws-sdk-mock/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-aws-sdk-mock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-aws-sdk-mock/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-aws-sdk-mock/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-aws-sdk-mock/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nikhila Ravi & Jimmy Ruts"
    },
    "bugs": {
        "url": "https://github.com/dwyl/aws-sdk-mock/issues"
    },
    "dependencies": {
        "aws-sdk": "^2.3.0",
        "sinon": "^1.17.3",
        "traverse": "^0.6.6"
    },
    "description": "Functions to mock the JavaScript aws-sdk ",
    "devDependencies": {
        "concat-stream": "^1.5.1",
        "is-node-stream": "^1.0.0",
        "istanbul": "^0.4.2",
        "tape": "^4.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7698b3ba82f493f71ff060ae2123cd0806ad8676",
        "tarball": "https://registry.npmjs.org/aws-sdk-mock/-/aws-sdk-mock-1.7.0.tgz"
    },
    "gitHead": "b2863e782b3a8ce791209f51caa2a8250536b61b",
    "homepage": "https://github.com/dwyl/aws-sdk-mock#readme",
    "keywords": [
        "aws-sdk",
        "aws",
        "Amazon",
        "Lambda",
        "API-Gateway",
        "S3",
        "DynamoDB",
        "SNS",
        "test",
        "mock",
        "Node.js"
    ],
    "license": "Apache-2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jruts"
        },
        {
            "name": "nelsonic"
        },
        {
            "name": "nikhilaravi"
        }
    ],
    "name": "aws-sdk-mock",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/dwyl/aws-sdk-mock.git"
    },
    "scripts": {
        "coverage": "istanbul cover ./node_modules/tape/bin/tape ./test/*.js && istanbul check-coverage --statements 100 --functions 100 --lines 100 --branches 100 --report html",
        "nocov": "tape test/*.js",
        "test": "istanbul cover ./node_modules/tape/bin/tape ./test/*.js"
    },
    "version": "1.7.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
