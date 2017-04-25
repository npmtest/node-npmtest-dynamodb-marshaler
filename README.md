# npmtest-dynamodb-marshaler

#### basic test coverage for  [dynamodb-marshaler (v2.0.0)](https://github.com/CascadeEnergy/dynamoDb-marshaler#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-dynamodb-marshaler.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-dynamodb-marshaler) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-dynamodb-marshaler.svg)](https://travis-ci.org/npmtest/node-npmtest-dynamodb-marshaler)

#### Translates sane javascript objects (and JSON) into DynamoDb format and vice versa.

[![NPM](https://nodei.co/npm/dynamodb-marshaler.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/dynamodb-marshaler)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-dynamodb-marshaler/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-dynamodb-marshaler/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-dynamodb-marshaler/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-dynamodb-marshaler/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-dynamodb-marshaler/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-dynamodb-marshaler/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-dynamodb-marshaler/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-dynamodb-marshaler/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-dynamodb-marshaler/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-dynamodb-marshaler/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-dynamodb-marshaler/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-dynamodb-marshaler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-dynamodb-marshaler/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-dynamodb-marshaler/build/test-report.html](https://npmtest.github.io/node-npmtest-dynamodb-marshaler/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-dynamodb-marshaler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-dynamodb-marshaler/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-dynamodb-marshaler/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-dynamodb-marshaler/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dynamodb-marshaler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dynamodb-marshaler/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-dynamodb-marshaler/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-dynamodb-marshaler/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "",
    "bugs": {
        "url": "https://github.com/CascadeEnergy/dynamoDb-marshaler/issues"
    },
    "dependencies": {
        "dispatch-recursive": "^2.0.0",
        "lodash": "^4.11.2"
    },
    "deprecated": "Please use AWS SDK Doc Client - http://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/DynamoDB/DocumentClient.html",
    "description": "Translates sane javascript objects (and JSON) into DynamoDb format and vice versa.",
    "devDependencies": {
        "browserify": "^13.0.1",
        "istanbul": "^0.4.3",
        "jshint": "^2.9.2",
        "leche": "^2.1.1",
        "mocha": "^2.4.5",
        "sinon": "^1.17.4",
        "uglifyjs": "^2.4.10"
    },
    "directories": {},
    "dist": {
        "shasum": "ef0d7088be08e2b6679ef17279167e3ccd784729",
        "tarball": "https://registry.npmjs.org/dynamodb-marshaler/-/dynamodb-marshaler-2.0.0.tgz"
    },
    "engines": {
        "node": ">=0.10.33"
    },
    "gitHead": "6a2457df5f09f527ccd47c7de06477c07eb9cada",
    "homepage": "https://github.com/CascadeEnergy/dynamoDb-marshaler#readme",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jinsyaoommen"
        },
        {
            "name": "nackjicholson"
        }
    ],
    "name": "dynamodb-marshaler",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/CascadeEnergy/dynamoDb-marshaler.git"
    },
    "scripts": {
        "build:browser": "browserify index.js --standalone dynamodb-marshaler | uglifyjs -c > dist/dynamodb-marshaler.min.js",
        "cov": "istanbul cover node_modules/.bin/_mocha -- --recursive",
        "lint": "jshint .",
        "test": "mocha --recursive"
    },
    "version": "2.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
