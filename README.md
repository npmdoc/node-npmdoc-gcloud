# npmdoc-gcloud

#### basic api documentation for  [gcloud (v0.37.2)](https://github.com/googlecloudplatform/gcloud-node#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-gcloud.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gcloud) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gcloud.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gcloud)

#### Google Cloud APIs Client Library for Node.js

[![NPM](https://nodei.co/npm/gcloud.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gcloud)

- [https://npmdoc.github.io/node-npmdoc-gcloud/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gcloud/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gcloud/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gcloud/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gcloud/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gcloud/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Google Inc."
    },
    "bugs": {
        "url": "https://github.com/googlecloudplatform/gcloud-node/issues"
    },
    "contributors": [
        {
            "name": "Burcu Dogan"
        },
        {
            "name": "Johan Euphrosine"
        },
        {
            "name": "Patrick Costello"
        },
        {
            "name": "Ryan Seys"
        },
        {
            "name": "Silvano Luciani"
        },
        {
            "name": "Stephen Sawchuk"
        }
    ],
    "dependencies": {
        "JSONStream": "^1.0.7",
        "array-uniq": "^1.0.2",
        "arrify": "^1.0.0",
        "async": "^1.4.2",
        "concat-stream": "^1.5.0",
        "create-error-class": "^2.0.1",
        "dns-zonefile": "0.1.18",
        "dot-prop": "^2.4.0",
        "duplexify": "^3.2.0",
        "ent": "^2.2.0",
        "extend": "^3.0.0",
        "gce-images": "^0.2.0",
        "gcs-resumable-upload": "^0.7.1",
        "google-auto-auth": "^0.2.4",
        "google-proto-files": "^0.2.1",
        "grpc": "^0.14.1",
        "hash-stream-validation": "^0.2.1",
        "is": "^3.0.1",
        "lodash.flatten": "^4.2.0",
        "methmeth": "^1.0.0",
        "mime-types": "^2.0.8",
        "modelo": "^4.2.0",
        "node-int64": "^0.4.0",
        "once": "^1.3.1",
        "prop-assign": "^1.0.0",
        "propprop": "^0.3.0",
        "pumpify": "^1.3.3",
        "request": "^2.70.0",
        "retry-request": "^1.3.0",
        "rgb-hex": "^1.0.0",
        "split-array-stream": "^1.0.0",
        "stream-events": "^1.0.1",
        "string-format-obj": "^1.0.0",
        "through2": "^2.0.0"
    },
    "description": "Google Cloud APIs Client Library for Node.js",
    "devDependencies": {
        "bytebuffer": "^4.0.0",
        "coveralls": "^2.11.2",
        "deep-strict-equal": "^0.1.0",
        "dox": "0.8.1",
        "glob": "^5.0.9",
        "globby": "^3.0.1",
        "istanbul": "^0.3.5",
        "jscs": "^2.1.1",
        "jshint": "^2.9.1",
        "mitm": "^1.1.0",
        "mocha": "^2.1.0",
        "mockery-next": "^2.0.1-3",
        "multiline": "^1.0.2",
        "node-uuid": "^1.4.3",
        "normalize-newline": "^2.0.0",
        "sinon": "^1.17.4",
        "tmp": "0.0.27"
    },
    "directories": {},
    "dist": {
        "shasum": "d4a2f4ba2cc301ec86d3eefbeeb57caa9938c9a3",
        "tarball": "https://registry.npmjs.org/gcloud/-/gcloud-0.37.2.tgz"
    },
    "engines": {
        "node": ">=0.12.0"
    },
    "files": [
        "lib/",
        "AUTHORS",
        "CONTRIBUTORS",
        "COPYING"
    ],
    "gitHead": "19ea133bdb3d2fe5d585eebaf450c593dd2f6e33",
    "homepage": "https://github.com/googlecloudplatform/gcloud-node#readme",
    "keywords": [
        "google apis client",
        "google api client",
        "google apis",
        "google api",
        "google",
        "google cloud platform",
        "google cloud",
        "cloud",
        "google bigquery",
        "google big query",
        "bigquery",
        "big query",
        "google cloud datastore",
        "cloud datastore",
        "datastore",
        "google cloud dns",
        "cloud dns",
        "dns",
        "google cloud pub/sub",
        "google cloud pubsub",
        "cloud pub/sub",
        "cloud pubsub",
        "pub/sub",
        "pubsub",
        "google cloud storage",
        "cloud storage",
        "gcs",
        "google compute engine",
        "compute engine",
        "computeengine",
        "gce",
        "google app engine",
        "app engine",
        "google appengine",
        "appengine",
        "gae",
        "google prediction",
        "prediction",
        "google translate",
        "translate",
        "google cloud logging",
        "cloud logging",
        "logging",
        "google cloud resource manager",
        "cloud resource manager",
        "resource manager",
        "google cloud vision",
        "cloud vision",
        "vision"
    ],
    "license": "Apache-2.0",
    "main": "./lib/index",
    "maintainers": [
        {
            "name": "callmehiphop"
        },
        {
            "name": "jgeewax"
        },
        {
            "name": "silvolu"
        },
        {
            "name": "stephenplusplus"
        },
        {
            "name": "thejbf"
        }
    ],
    "name": "gcloud",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/googlecloudplatform/gcloud-node.git"
    },
    "scripts": {
        "coveralls": "istanbul cover _mocha --report lcovonly -- --no-timeouts --bail test/**/*.js -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "docs": "node ./scripts/docs.js",
        "lint": "jshint lib/ system-test/ test/ && jscs lib/ system-test/ test/",
        "system-test": "mocha system-test/*.js --no-timeouts --bail",
        "test": "npm run docs && mocha test/docs.js test/index.js test/*/*.js"
    },
    "version": "0.37.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
