# api documentation for  [gcloud (v0.37.2)](https://github.com/googlecloudplatform/gcloud-node#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-gcloud.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gcloud) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gcloud.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gcloud)
#### Google Cloud APIs Client Library for Node.js

[![NPM](https://nodei.co/npm/gcloud.png?downloads=true)](https://www.npmjs.com/package/gcloud)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gcloud/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-gcloud_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gcloud/build/apidoc.html)

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
            "name": "Burcu Dogan",
            "email": "jbd@google.com"
        },
        {
            "name": "Johan Euphrosine",
            "email": "proppy@google.com"
        },
        {
            "name": "Patrick Costello",
            "email": "pcostell@google.com"
        },
        {
            "name": "Ryan Seys",
            "email": "ryan@ryanseys.com"
        },
        {
            "name": "Silvano Luciani",
            "email": "silvano@google.com"
        },
        {
            "name": "Stephen Sawchuk",
            "email": "sawchuk@gmail.com"
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
            "name": "callmehiphop",
            "email": "callmehiphop@gmail.com"
        },
        {
            "name": "jgeewax",
            "email": "jj@geewax.org"
        },
        {
            "name": "silvolu",
            "email": "silvano.luciani@gmail.com"
        },
        {
            "name": "stephenplusplus",
            "email": "sawchuk@gmail.com"
        },
        {
            "name": "thejbf",
            "email": "burcujdogan@gmail.com"
        }
    ],
    "name": "gcloud",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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
    "version": "0.37.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module gcloud](#apidoc.module.gcloud)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>bigquery (options)](#apidoc.element.gcloud.bigquery)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>bigquery.super_ (config, options)](#apidoc.element.gcloud.bigquery.super_)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>bigtable (options)](#apidoc.element.gcloud.bigtable)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>bigtable.super_ (config, options)](#apidoc.element.gcloud.bigtable.super_)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>compute (options)](#apidoc.element.gcloud.compute)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>datastore (options)](#apidoc.element.gcloud.datastore)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>datastore.super_ ()](#apidoc.element.gcloud.datastore.super_)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>dns (options)](#apidoc.element.gcloud.dns)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>logging (options)](#apidoc.element.gcloud.logging)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>prediction (options)](#apidoc.element.gcloud.prediction)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>pubsub (options)](#apidoc.element.gcloud.pubsub)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>resource (options)](#apidoc.element.gcloud.resource)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>storage (options)](#apidoc.element.gcloud.storage)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>translate (options)](#apidoc.element.gcloud.translate)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>vision (options)](#apidoc.element.gcloud.vision)
1.  object <span class="apidocSignatureSpan">gcloud.</span>bigquery.prototype
1.  object <span class="apidocSignatureSpan">gcloud.</span>bigquery.super_.prototype
1.  object <span class="apidocSignatureSpan">gcloud.</span>bigtable.prototype
1.  object <span class="apidocSignatureSpan">gcloud.</span>bigtable.super_.prototype
1.  object <span class="apidocSignatureSpan">gcloud.</span>compute.prototype
1.  object <span class="apidocSignatureSpan">gcloud.</span>datastore.prototype
1.  object <span class="apidocSignatureSpan">gcloud.</span>datastore.super_.prototype
1.  object <span class="apidocSignatureSpan">gcloud.</span>dns.prototype
1.  object <span class="apidocSignatureSpan">gcloud.</span>logging.prototype
1.  object <span class="apidocSignatureSpan">gcloud.</span>prediction.prototype
1.  object <span class="apidocSignatureSpan">gcloud.</span>pubsub.prototype
1.  object <span class="apidocSignatureSpan">gcloud.</span>resource.prototype
1.  object <span class="apidocSignatureSpan">gcloud.</span>storage.prototype
1.  object <span class="apidocSignatureSpan">gcloud.</span>translate.prototype
1.  object <span class="apidocSignatureSpan">gcloud.</span>vision.prototype

#### [module gcloud.bigquery](#apidoc.module.gcloud.bigquery)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>bigquery (options)](#apidoc.element.gcloud.bigquery.bigquery)
1.  [function <span class="apidocSignatureSpan">gcloud.bigquery.</span>super_ (config, options)](#apidoc.element.gcloud.bigquery.super_)

#### [module gcloud.bigquery.prototype](#apidoc.module.gcloud.bigquery.prototype)
1.  [function <span class="apidocSignatureSpan">gcloud.bigquery.prototype.</span>createDataset (id, options, callback)](#apidoc.element.gcloud.bigquery.prototype.createDataset)
1.  [function <span class="apidocSignatureSpan">gcloud.bigquery.prototype.</span>dataset (id)](#apidoc.element.gcloud.bigquery.prototype.dataset)
1.  [function <span class="apidocSignatureSpan">gcloud.bigquery.prototype.</span>getDatasets ()](#apidoc.element.gcloud.bigquery.prototype.getDatasets)
1.  [function <span class="apidocSignatureSpan">gcloud.bigquery.prototype.</span>getJobs ()](#apidoc.element.gcloud.bigquery.prototype.getJobs)
1.  [function <span class="apidocSignatureSpan">gcloud.bigquery.prototype.</span>job (id)](#apidoc.element.gcloud.bigquery.prototype.job)
1.  [function <span class="apidocSignatureSpan">gcloud.bigquery.prototype.</span>query ()](#apidoc.element.gcloud.bigquery.prototype.query)
1.  [function <span class="apidocSignatureSpan">gcloud.bigquery.prototype.</span>startQuery (options, callback)](#apidoc.element.gcloud.bigquery.prototype.startQuery)

#### [module gcloud.bigquery.super_](#apidoc.module.gcloud.bigquery.super_)
1.  [function <span class="apidocSignatureSpan">gcloud.bigquery.</span>super_ (config, options)](#apidoc.element.gcloud.bigquery.super_.super_)

#### [module gcloud.bigquery.super_.prototype](#apidoc.module.gcloud.bigquery.super_.prototype)
1.  [function <span class="apidocSignatureSpan">gcloud.bigquery.super_.prototype.</span>request (reqOpts, callback)](#apidoc.element.gcloud.bigquery.super_.prototype.request)

#### [module gcloud.bigtable](#apidoc.module.gcloud.bigtable)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>bigtable (options)](#apidoc.element.gcloud.bigtable.bigtable)
1.  [function <span class="apidocSignatureSpan">gcloud.bigtable.</span>formatTableName_ (name)](#apidoc.element.gcloud.bigtable.formatTableName_)
1.  [function <span class="apidocSignatureSpan">gcloud.bigtable.</span>super_ (config, options)](#apidoc.element.gcloud.bigtable.super_)

#### [module gcloud.bigtable.prototype](#apidoc.module.gcloud.bigtable.prototype)
1.  [function <span class="apidocSignatureSpan">gcloud.bigtable.prototype.</span>createTable (name, options, callback)](#apidoc.element.gcloud.bigtable.prototype.createTable)
1.  [function <span class="apidocSignatureSpan">gcloud.bigtable.prototype.</span>getTables (callback)](#apidoc.element.gcloud.bigtable.prototype.getTables)
1.  [function <span class="apidocSignatureSpan">gcloud.bigtable.prototype.</span>table (name)](#apidoc.element.gcloud.bigtable.prototype.table)

#### [module gcloud.bigtable.super_](#apidoc.module.gcloud.bigtable.super_)
1.  [function <span class="apidocSignatureSpan">gcloud.bigtable.</span>super_ (config, options)](#apidoc.element.gcloud.bigtable.super_.super_)
1.  [function <span class="apidocSignatureSpan">gcloud.bigtable.super_.</span>createDeadline_ (timeout)](#apidoc.element.gcloud.bigtable.super_.createDeadline_)
1.  [function <span class="apidocSignatureSpan">gcloud.bigtable.super_.</span>decodeValue_ (value)](#apidoc.element.gcloud.bigtable.super_.decodeValue_)
1.  [function <span class="apidocSignatureSpan">gcloud.bigtable.super_.</span>decorateError_ (err)](#apidoc.element.gcloud.bigtable.super_.decorateError_)
1.  [function <span class="apidocSignatureSpan">gcloud.bigtable.super_.</span>decorateGrpcResponse_ (obj, response)](#apidoc.element.gcloud.bigtable.super_.decorateGrpcResponse_)
1.  [function <span class="apidocSignatureSpan">gcloud.bigtable.super_.</span>decorateStatus_ (status)](#apidoc.element.gcloud.bigtable.super_.decorateStatus_)
1.  [function <span class="apidocSignatureSpan">gcloud.bigtable.super_.</span>encodeValue_ (value, options)](#apidoc.element.gcloud.bigtable.super_.encodeValue_)
1.  [function <span class="apidocSignatureSpan">gcloud.bigtable.super_.</span>objToStruct_ (obj, options)](#apidoc.element.gcloud.bigtable.super_.objToStruct_)
1.  [function <span class="apidocSignatureSpan">gcloud.bigtable.super_.</span>shouldRetryRequest_ (response)](#apidoc.element.gcloud.bigtable.super_.shouldRetryRequest_)
1.  [function <span class="apidocSignatureSpan">gcloud.bigtable.super_.</span>structToObj_ (struct)](#apidoc.element.gcloud.bigtable.super_.structToObj_)
1.  object <span class="apidocSignatureSpan">gcloud.bigtable.super_.</span>GRPC_ERROR_CODE_TO_HTTP

#### [module gcloud.bigtable.super_.prototype](#apidoc.module.gcloud.bigtable.super_.prototype)
1.  [function <span class="apidocSignatureSpan">gcloud.bigtable.super_.prototype.</span>getGrpcCredentials_ (callback)](#apidoc.element.gcloud.bigtable.super_.prototype.getGrpcCredentials_)
1.  [function <span class="apidocSignatureSpan">gcloud.bigtable.super_.prototype.</span>getService_ (protoOpts)](#apidoc.element.gcloud.bigtable.super_.prototype.getService_)
1.  [function <span class="apidocSignatureSpan">gcloud.bigtable.super_.prototype.</span>loadProtoFile_ (protoConfig, config)](#apidoc.element.gcloud.bigtable.super_.prototype.loadProtoFile_)
1.  [function <span class="apidocSignatureSpan">gcloud.bigtable.super_.prototype.</span>request (protoOpts, reqOpts, callback)](#apidoc.element.gcloud.bigtable.super_.prototype.request)
1.  [function <span class="apidocSignatureSpan">gcloud.bigtable.super_.prototype.</span>requestStream (protoOpts, reqOpts)](#apidoc.element.gcloud.bigtable.super_.prototype.requestStream)

#### [module gcloud.compute](#apidoc.module.gcloud.compute)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>compute (options)](#apidoc.element.gcloud.compute.compute)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.</span>super_ (config, options)](#apidoc.element.gcloud.compute.super_)

#### [module gcloud.compute.prototype](#apidoc.module.gcloud.compute.prototype)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>createFirewall (name, config, callback)](#apidoc.element.gcloud.compute.prototype.createFirewall)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>createHealthCheck (name, options, callback)](#apidoc.element.gcloud.compute.prototype.createHealthCheck)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>createNetwork (name, config, callback)](#apidoc.element.gcloud.compute.prototype.createNetwork)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>createRule (name, config, callback)](#apidoc.element.gcloud.compute.prototype.createRule)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>createService (name, config, callback)](#apidoc.element.gcloud.compute.prototype.createService)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>firewall (name)](#apidoc.element.gcloud.compute.prototype.firewall)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getAddresses ()](#apidoc.element.gcloud.compute.prototype.getAddresses)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getAutoscalers ()](#apidoc.element.gcloud.compute.prototype.getAutoscalers)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getDisks ()](#apidoc.element.gcloud.compute.prototype.getDisks)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getFirewalls ()](#apidoc.element.gcloud.compute.prototype.getFirewalls)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getHealthChecks ()](#apidoc.element.gcloud.compute.prototype.getHealthChecks)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getInstanceGroups ()](#apidoc.element.gcloud.compute.prototype.getInstanceGroups)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getNetworks ()](#apidoc.element.gcloud.compute.prototype.getNetworks)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getOperations ()](#apidoc.element.gcloud.compute.prototype.getOperations)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getRegions ()](#apidoc.element.gcloud.compute.prototype.getRegions)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getRules ()](#apidoc.element.gcloud.compute.prototype.getRules)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getServices ()](#apidoc.element.gcloud.compute.prototype.getServices)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getSnapshots ()](#apidoc.element.gcloud.compute.prototype.getSnapshots)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getVMs ()](#apidoc.element.gcloud.compute.prototype.getVMs)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getZones ()](#apidoc.element.gcloud.compute.prototype.getZones)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>healthCheck (name, options)](#apidoc.element.gcloud.compute.prototype.healthCheck)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>network (name)](#apidoc.element.gcloud.compute.prototype.network)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>operation (name)](#apidoc.element.gcloud.compute.prototype.operation)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>region (name)](#apidoc.element.gcloud.compute.prototype.region)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>rule (name)](#apidoc.element.gcloud.compute.prototype.rule)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>service (name)](#apidoc.element.gcloud.compute.prototype.service)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>snapshot (name)](#apidoc.element.gcloud.compute.prototype.snapshot)
1.  [function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>zone (name)](#apidoc.element.gcloud.compute.prototype.zone)

#### [module gcloud.datastore](#apidoc.module.gcloud.datastore)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>datastore (options)](#apidoc.element.gcloud.datastore.datastore)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.</span>double (value)](#apidoc.element.gcloud.datastore.double)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.</span>extend ()](#apidoc.element.gcloud.datastore.extend)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.</span>geoPoint (coordindates)](#apidoc.element.gcloud.datastore.geoPoint)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.</span>int (value)](#apidoc.element.gcloud.datastore.int)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.</span>super_ ()](#apidoc.element.gcloud.datastore.super_)
1.  string <span class="apidocSignatureSpan">gcloud.datastore.</span>MORE_RESULTS_AFTER_CURSOR
1.  string <span class="apidocSignatureSpan">gcloud.datastore.</span>MORE_RESULTS_AFTER_LIMIT
1.  string <span class="apidocSignatureSpan">gcloud.datastore.</span>NO_MORE_RESULTS

#### [module gcloud.datastore.prototype](#apidoc.module.gcloud.datastore.prototype)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.prototype.</span>createQuery (namespace, kind)](#apidoc.element.gcloud.datastore.prototype.createQuery)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.prototype.</span>determineBaseUrl_ (customApiEndpoint)](#apidoc.element.gcloud.datastore.prototype.determineBaseUrl_)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.prototype.</span>getGrpcCredentials_ (callback)](#apidoc.element.gcloud.datastore.prototype.getGrpcCredentials_)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.prototype.</span>getService_ (protoOpts)](#apidoc.element.gcloud.datastore.prototype.getService_)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.prototype.</span>isInstance ()](#apidoc.element.gcloud.datastore.prototype.isInstance)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.prototype.</span>key (options)](#apidoc.element.gcloud.datastore.prototype.key)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.prototype.</span>loadProtoFile_ (protoConfig, config)](#apidoc.element.gcloud.datastore.prototype.loadProtoFile_)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.prototype.</span>request (protoOpts, reqOpts, callback)](#apidoc.element.gcloud.datastore.prototype.request)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.prototype.</span>requestStream (protoOpts, reqOpts)](#apidoc.element.gcloud.datastore.prototype.requestStream)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.prototype.</span>transaction ()](#apidoc.element.gcloud.datastore.prototype.transaction)

#### [module gcloud.datastore.super_](#apidoc.module.gcloud.datastore.super_)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.</span>super_ ()](#apidoc.element.gcloud.datastore.super_.super_)

#### [module gcloud.datastore.super_.prototype](#apidoc.module.gcloud.datastore.super_.prototype)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.super_.prototype.</span>allocateIds (incompleteKey, n, callback)](#apidoc.element.gcloud.datastore.super_.prototype.allocateIds)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.super_.prototype.</span>delete (keys, callback)](#apidoc.element.gcloud.datastore.super_.prototype.delete)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.super_.prototype.</span>get (keys, options, callback)](#apidoc.element.gcloud.datastore.super_.prototype.get)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.super_.prototype.</span>insert (entities, callback)](#apidoc.element.gcloud.datastore.super_.prototype.insert)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.super_.prototype.</span>request_ (protoOpts, reqOpts, callback)](#apidoc.element.gcloud.datastore.super_.prototype.request_)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.super_.prototype.</span>runQuery (query, options, callback)](#apidoc.element.gcloud.datastore.super_.prototype.runQuery)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.super_.prototype.</span>save (entities, callback)](#apidoc.element.gcloud.datastore.super_.prototype.save)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.super_.prototype.</span>update (entities, callback)](#apidoc.element.gcloud.datastore.super_.prototype.update)
1.  [function <span class="apidocSignatureSpan">gcloud.datastore.super_.prototype.</span>upsert (entities, callback)](#apidoc.element.gcloud.datastore.super_.prototype.upsert)

#### [module gcloud.dns](#apidoc.module.gcloud.dns)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>dns (options)](#apidoc.element.gcloud.dns.dns)
1.  [function <span class="apidocSignatureSpan">gcloud.dns.</span>super_ (config, options)](#apidoc.element.gcloud.dns.super_)

#### [module gcloud.dns.prototype](#apidoc.module.gcloud.dns.prototype)
1.  [function <span class="apidocSignatureSpan">gcloud.dns.prototype.</span>createZone (name, config, callback)](#apidoc.element.gcloud.dns.prototype.createZone)
1.  [function <span class="apidocSignatureSpan">gcloud.dns.prototype.</span>getZones ()](#apidoc.element.gcloud.dns.prototype.getZones)
1.  [function <span class="apidocSignatureSpan">gcloud.dns.prototype.</span>zone (name)](#apidoc.element.gcloud.dns.prototype.zone)

#### [module gcloud.logging](#apidoc.module.gcloud.logging)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>logging (options)](#apidoc.element.gcloud.logging.logging)
1.  [function <span class="apidocSignatureSpan">gcloud.logging.</span>super_ (config, options)](#apidoc.element.gcloud.logging.super_)

#### [module gcloud.logging.prototype](#apidoc.module.gcloud.logging.prototype)
1.  [function <span class="apidocSignatureSpan">gcloud.logging.prototype.</span>createSink (name, config, callback)](#apidoc.element.gcloud.logging.prototype.createSink)
1.  [function <span class="apidocSignatureSpan">gcloud.logging.prototype.</span>entry (resource, data)](#apidoc.element.gcloud.logging.prototype.entry)
1.  [function <span class="apidocSignatureSpan">gcloud.logging.prototype.</span>getEntries ()](#apidoc.element.gcloud.logging.prototype.getEntries)
1.  [function <span class="apidocSignatureSpan">gcloud.logging.prototype.</span>getSinks ()](#apidoc.element.gcloud.logging.prototype.getSinks)
1.  [function <span class="apidocSignatureSpan">gcloud.logging.prototype.</span>log (name)](#apidoc.element.gcloud.logging.prototype.log)
1.  [function <span class="apidocSignatureSpan">gcloud.logging.prototype.</span>setAclForBucket_ (name, config, callback)](#apidoc.element.gcloud.logging.prototype.setAclForBucket_)
1.  [function <span class="apidocSignatureSpan">gcloud.logging.prototype.</span>setAclForDataset_ (name, config, callback)](#apidoc.element.gcloud.logging.prototype.setAclForDataset_)
1.  [function <span class="apidocSignatureSpan">gcloud.logging.prototype.</span>setAclForTopic_ (name, config, callback)](#apidoc.element.gcloud.logging.prototype.setAclForTopic_)
1.  [function <span class="apidocSignatureSpan">gcloud.logging.prototype.</span>sink (name)](#apidoc.element.gcloud.logging.prototype.sink)

#### [module gcloud.prediction](#apidoc.module.gcloud.prediction)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>prediction (options)](#apidoc.element.gcloud.prediction.prediction)
1.  [function <span class="apidocSignatureSpan">gcloud.prediction.</span>super_ (config, options)](#apidoc.element.gcloud.prediction.super_)

#### [module gcloud.prediction.prototype](#apidoc.module.gcloud.prediction.prototype)
1.  [function <span class="apidocSignatureSpan">gcloud.prediction.prototype.</span>createModel (id, options, callback)](#apidoc.element.gcloud.prediction.prototype.createModel)
1.  [function <span class="apidocSignatureSpan">gcloud.prediction.prototype.</span>getModels ()](#apidoc.element.gcloud.prediction.prototype.getModels)
1.  [function <span class="apidocSignatureSpan">gcloud.prediction.prototype.</span>model (id)](#apidoc.element.gcloud.prediction.prototype.model)

#### [module gcloud.pubsub](#apidoc.module.gcloud.pubsub)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>pubsub (options)](#apidoc.element.gcloud.pubsub.pubsub)
1.  [function <span class="apidocSignatureSpan">gcloud.pubsub.</span>super_ (config, options)](#apidoc.element.gcloud.pubsub.super_)

#### [module gcloud.pubsub.prototype](#apidoc.module.gcloud.pubsub.prototype)
1.  [function <span class="apidocSignatureSpan">gcloud.pubsub.prototype.</span>createTopic (name, callback)](#apidoc.element.gcloud.pubsub.prototype.createTopic)
1.  [function <span class="apidocSignatureSpan">gcloud.pubsub.prototype.</span>determineBaseUrl_ ()](#apidoc.element.gcloud.pubsub.prototype.determineBaseUrl_)
1.  [function <span class="apidocSignatureSpan">gcloud.pubsub.prototype.</span>getSubscriptions ()](#apidoc.element.gcloud.pubsub.prototype.getSubscriptions)
1.  [function <span class="apidocSignatureSpan">gcloud.pubsub.prototype.</span>getTopics ()](#apidoc.element.gcloud.pubsub.prototype.getTopics)
1.  [function <span class="apidocSignatureSpan">gcloud.pubsub.prototype.</span>subscribe (topic, subName, options, callback)](#apidoc.element.gcloud.pubsub.prototype.subscribe)
1.  [function <span class="apidocSignatureSpan">gcloud.pubsub.prototype.</span>subscription (name, options)](#apidoc.element.gcloud.pubsub.prototype.subscription)
1.  [function <span class="apidocSignatureSpan">gcloud.pubsub.prototype.</span>topic (name)](#apidoc.element.gcloud.pubsub.prototype.topic)

#### [module gcloud.resource](#apidoc.module.gcloud.resource)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>resource (options)](#apidoc.element.gcloud.resource.resource)
1.  [function <span class="apidocSignatureSpan">gcloud.resource.</span>super_ (config, options)](#apidoc.element.gcloud.resource.super_)

#### [module gcloud.resource.prototype](#apidoc.module.gcloud.resource.prototype)
1.  [function <span class="apidocSignatureSpan">gcloud.resource.prototype.</span>createProject (id, options, callback)](#apidoc.element.gcloud.resource.prototype.createProject)
1.  [function <span class="apidocSignatureSpan">gcloud.resource.prototype.</span>getProjects ()](#apidoc.element.gcloud.resource.prototype.getProjects)
1.  [function <span class="apidocSignatureSpan">gcloud.resource.prototype.</span>project (id)](#apidoc.element.gcloud.resource.prototype.project)

#### [module gcloud.storage](#apidoc.module.gcloud.storage)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>storage (options)](#apidoc.element.gcloud.storage.storage)
1.  [function <span class="apidocSignatureSpan">gcloud.storage.</span>super_ (config, options)](#apidoc.element.gcloud.storage.super_)
1.  object <span class="apidocSignatureSpan">gcloud.storage.</span>acl

#### [module gcloud.storage.prototype](#apidoc.module.gcloud.storage.prototype)
1.  [function <span class="apidocSignatureSpan">gcloud.storage.prototype.</span>bucket (name)](#apidoc.element.gcloud.storage.prototype.bucket)
1.  [function <span class="apidocSignatureSpan">gcloud.storage.prototype.</span>channel (id, resourceId)](#apidoc.element.gcloud.storage.prototype.channel)
1.  [function <span class="apidocSignatureSpan">gcloud.storage.prototype.</span>createBucket (name, metadata, callback)](#apidoc.element.gcloud.storage.prototype.createBucket)
1.  [function <span class="apidocSignatureSpan">gcloud.storage.prototype.</span>getBuckets ()](#apidoc.element.gcloud.storage.prototype.getBuckets)
1.  object <span class="apidocSignatureSpan">gcloud.storage.prototype.</span>acl

#### [module gcloud.translate](#apidoc.module.gcloud.translate)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>translate (options)](#apidoc.element.gcloud.translate.translate)

#### [module gcloud.translate.prototype](#apidoc.module.gcloud.translate.prototype)
1.  [function <span class="apidocSignatureSpan">gcloud.translate.prototype.</span>detect (input, callback)](#apidoc.element.gcloud.translate.prototype.detect)
1.  [function <span class="apidocSignatureSpan">gcloud.translate.prototype.</span>getLanguages (callback)](#apidoc.element.gcloud.translate.prototype.getLanguages)
1.  [function <span class="apidocSignatureSpan">gcloud.translate.prototype.</span>request (reqOpts, callback)](#apidoc.element.gcloud.translate.prototype.request)
1.  [function <span class="apidocSignatureSpan">gcloud.translate.prototype.</span>translate (input, options, callback)](#apidoc.element.gcloud.translate.prototype.translate)

#### [module gcloud.vision](#apidoc.module.gcloud.vision)
1.  [function <span class="apidocSignatureSpan">gcloud.</span>vision (options)](#apidoc.element.gcloud.vision.vision)
1.  [function <span class="apidocSignatureSpan">gcloud.vision.</span>convertToBoolean_ (baseLikelihood, object)](#apidoc.element.gcloud.vision.convertToBoolean_)
1.  [function <span class="apidocSignatureSpan">gcloud.vision.</span>findImages_ (images, callback)](#apidoc.element.gcloud.vision.findImages_)
1.  [function <span class="apidocSignatureSpan">gcloud.vision.</span>formatEntityAnnotation_ (entityAnnotation, options)](#apidoc.element.gcloud.vision.formatEntityAnnotation_)
1.  [function <span class="apidocSignatureSpan">gcloud.vision.</span>formatError_ (err)](#apidoc.element.gcloud.vision.formatError_)
1.  [function <span class="apidocSignatureSpan">gcloud.vision.</span>formatFaceAnnotation_ (faceAnnotation)](#apidoc.element.gcloud.vision.formatFaceAnnotation_)
1.  [function <span class="apidocSignatureSpan">gcloud.vision.</span>formatImagePropertiesAnnotation_ (imageAnnotation, options)](#apidoc.element.gcloud.vision.formatImagePropertiesAnnotation_)
1.  [function <span class="apidocSignatureSpan">gcloud.vision.</span>formatSafeSearchAnnotation_ (ssAnnotation, options)](#apidoc.element.gcloud.vision.formatSafeSearchAnnotation_)
1.  [function <span class="apidocSignatureSpan">gcloud.vision.</span>super_ (config, options)](#apidoc.element.gcloud.vision.super_)
1.  object <span class="apidocSignatureSpan">gcloud.vision.</span>likelihood

#### [module gcloud.vision.prototype](#apidoc.module.gcloud.vision.prototype)
1.  [function <span class="apidocSignatureSpan">gcloud.vision.prototype.</span>annotate (requests, callback)](#apidoc.element.gcloud.vision.prototype.annotate)
1.  [function <span class="apidocSignatureSpan">gcloud.vision.prototype.</span>detect (images, options, callback)](#apidoc.element.gcloud.vision.prototype.detect)
1.  [function <span class="apidocSignatureSpan">gcloud.vision.prototype.</span>detectFaces (images, options, callback)](#apidoc.element.gcloud.vision.prototype.detectFaces)
1.  [function <span class="apidocSignatureSpan">gcloud.vision.prototype.</span>detectLabels (images, options, callback)](#apidoc.element.gcloud.vision.prototype.detectLabels)
1.  [function <span class="apidocSignatureSpan">gcloud.vision.prototype.</span>detectLandmarks (images, options, callback)](#apidoc.element.gcloud.vision.prototype.detectLandmarks)
1.  [function <span class="apidocSignatureSpan">gcloud.vision.prototype.</span>detectLogos (images, options, callback)](#apidoc.element.gcloud.vision.prototype.detectLogos)
1.  [function <span class="apidocSignatureSpan">gcloud.vision.prototype.</span>detectProperties (images, options, callback)](#apidoc.element.gcloud.vision.prototype.detectProperties)
1.  [function <span class="apidocSignatureSpan">gcloud.vision.prototype.</span>detectSafeSearch (images, options, callback)](#apidoc.element.gcloud.vision.prototype.detectSafeSearch)
1.  [function <span class="apidocSignatureSpan">gcloud.vision.prototype.</span>detectText (images, options, callback)](#apidoc.element.gcloud.vision.prototype.detectText)



# <a name="apidoc.module.gcloud"></a>[module gcloud](#apidoc.module.gcloud)

#### <a name="apidoc.element.gcloud.bigquery"></a>[function <span class="apidocSignatureSpan">gcloud.</span>bigquery (options)](#apidoc.element.gcloud.bigquery)
- description and source-code
```javascript
function BigQuery(options) {
  if (!(this instanceof BigQuery)) {
    options = util.normalizeArguments(this, options);
    return new BigQuery(options);
  }

  var config = {
    baseUrl: 'https://www.googleapis.com/bigquery/v2',
    scopes: ['https://www.googleapis.com/auth/bigquery']
  };

  Service.call(this, config, options);
}
```
- example usage
```shell
...
#### Preview

'''js
var gcloud = require('gcloud');

// Authenticating on a per-API-basis. You don't need to do this if you auth on a
// global basis (see Authentication section above).
var bigquery = gcloud.bigquery({
  projectId: 'my-project',
  keyFilename: '/path/to/keyfile.json'
});

// Access an existing dataset and table.
var schoolsDataset = bigquery.dataset('schools');
var schoolsTable = schoolsDataset.table('schoolsData');
...
```

#### <a name="apidoc.element.gcloud.bigquery.super_"></a>[function <span class="apidocSignatureSpan">gcloud.</span>bigquery.super_ (config, options)](#apidoc.element.gcloud.bigquery.super_)
- description and source-code
```javascript
function Service(config, options) {
  var reqCfg = extend({}, config, {
    credentials: options.credentials,
    keyFile: options.keyFilename,
    email: options.email
  });

  this.makeAuthenticatedRequest = util.makeAuthenticatedRequestFactory(reqCfg);

  this.authClient = this.makeAuthenticatedRequest.authClient;
  this.baseUrl = config.baseUrl;
  this.getCredentials = this.makeAuthenticatedRequest.getCredentials;
  this.globalInterceptors = arrify(options.interceptors_);
  this.interceptors = [];
  this.projectId = options.projectId;
  this.projectIdRequired = config.projectIdRequired !== false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.bigtable"></a>[function <span class="apidocSignatureSpan">gcloud.</span>bigtable (options)](#apidoc.element.gcloud.bigtable)
- description and source-code
```javascript
function Bigtable(options) {
  if (!(this instanceof Bigtable)) {
    options = util.normalizeArguments(this, options);
    return new Bigtable(options);
  }

  options = extend({}, options, {
    zone: options.zone.name || options.zone
  });

  this.clusterName = format(
    'projects/{projectId}/zones/{zone}/clusters/{cluster}',
    options
  );

  var config = {
    baseUrl: 'bigtable.googleapis.com',
    service: 'bigtable',
    apiVersion: 'v1',
    protoServices: {
      BigtableService: googleProtoFiles.bigtable.v1,
      BigtableTableService: {
        path: googleProtoFiles.bigtable.admin,
        service: 'bigtable.admin.table'
      }
    },
    scopes: [
      'https://www.googleapis.com/auth/bigtable.admin',
      'https://www.googleapis.com/auth/bigtable.data'
    ]
  };

  GrpcService.call(this, config, options);
}
```
- example usage
```shell
...
#### Preview

'''js
var gcloud = require('gcloud');

// Authenticating on a per-API-basis. You don't need to do this if you auth on a
// global basis (see Authentication section above).
var bigtable = gcloud.bigtable({
  projectId: 'my-project',
  keyFilename: '/path/to/keyfile.json',
  zone: 'my-zone',
  cluster: 'my-cluster'
});

var table = bigtable.table('prezzy');
...
```

#### <a name="apidoc.element.gcloud.bigtable.super_"></a>[function <span class="apidocSignatureSpan">gcloud.</span>bigtable.super_ (config, options)](#apidoc.element.gcloud.bigtable.super_)
- description and source-code
```javascript
function GrpcService(config, options) {
  if (global.GCLOUD_SANDBOX_ENV) {
    // gRPC has a tendency to cause our doc unit tests to fail, so we prevent
    // any calls to that library from going through.
    // Reference: https://github.com/GoogleCloudPlatform/gcloud-node/pull/1137#issuecomment-193315047
    return global.GCLOUD_SANDBOX_ENV;
  }

  Service.call(this, config, options);

  if (config.customEndpoint) {
    this.grpcCredentials = grpc.credentials.createInsecure();
  }

  this.maxRetries = options.maxRetries;

  var apiVersion = config.apiVersion;
  var service = this.service = config.service;

  this.activeServiceMap_ = new Map();
  this.protos = {};

  var protoServices = config.protoServices;

  if (!protoServices) {
    protoServices = {};
    protoServices[service] = googleProtoFiles[service][apiVersion];
  }

  for (var protoServiceName in protoServices) {
    var protoService = this.loadProtoFile_(
      protoServices[protoServiceName], config);

    this.protos[protoServiceName] = protoService;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute"></a>[function <span class="apidocSignatureSpan">gcloud.</span>compute (options)](#apidoc.element.gcloud.compute)
- description and source-code
```javascript
function Compute(options) {
  if (!(this instanceof Compute)) {
    options = util.normalizeArguments(this, options);
    return new Compute(options);
  }

  var config = {
    baseUrl: 'https://www.googleapis.com/compute/v1',
    scopes: ['https://www.googleapis.com/auth/compute']
  };

  Service.call(this, config, options);
}
```
- example usage
```shell
...

'''js
var gcloud = require('gcloud');

// Authenticating on a per-API-basis. You don't need to do this if you auth on a
// global basis (see Authentication section above).

var gce = gcloud.compute({
  projectId: 'my-project',
  keyFilename: '/path/to/keyfile.json'
});

// Create a new VM using the latest OS image of your choice.
var zone = gce.zone('us-central1-a');
var name = 'ubuntu-http';
...
```

#### <a name="apidoc.element.gcloud.datastore"></a>[function <span class="apidocSignatureSpan">gcloud.</span>datastore (options)](#apidoc.element.gcloud.datastore)
- description and source-code
```javascript
function Datastore(options) {
  if (!(this instanceof Datastore)) {
    options = util.normalizeArguments(this, options, {
      projectIdRequired: false
    });
    return new Datastore(options);
  }

  this.defaultBaseUrl_ = 'datastore.googleapis.com';
  this.determineBaseUrl_(options.apiEndpoint);

  this.namespace = options.namespace;
  this.projectId = process.env.DATASTORE_PROJECT_ID || options.projectId;

  var config = {
    projectIdRequired: false,
    baseUrl: this.baseUrl_,
    customEndpoint: this.customEndpoint_,
    service: 'datastore',
    apiVersion: 'v1beta3',
    scopes: ['https://www.googleapis.com/auth/datastore']
  };

  GrpcService.call(this, config, options);
}
```
- example usage
```shell
...

'''js
var gcloud = require('gcloud');

// Authenticating on a per-API-basis. You don't need to do this if you auth on a
// global basis (see Authentication section above).

var datastore = gcloud.datastore({
  projectId: 'my-project',
  keyFilename: '/path/to/keyfile.json'
});

var key = datastore.key(['Product', 'Computer']);

datastore.get(key, function(err, entity) {
...
```

#### <a name="apidoc.element.gcloud.datastore.super_"></a>[function <span class="apidocSignatureSpan">gcloud.</span>datastore.super_ ()](#apidoc.element.gcloud.datastore.super_)
- description and source-code
```javascript
function DatastoreRequest() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.dns"></a>[function <span class="apidocSignatureSpan">gcloud.</span>dns (options)](#apidoc.element.gcloud.dns)
- description and source-code
```javascript
function DNS(options) {
  if (!(this instanceof DNS)) {
    options = util.normalizeArguments(this, options);
    return new DNS(options);
  }

  var config = {
    baseUrl: 'https://www.googleapis.com/dns/v1',
    scopes: [
      'https://www.googleapis.com/auth/ndev.clouddns.readwrite',
      'https://www.googleapis.com/auth/cloud-platform'
    ]
  };

  Service.call(this, config, options);
}
```
- example usage
```shell
...

'''js
var gcloud = require('gcloud');

// Authenticating on a per-API-basis. You don't need to do this if you auth on a
// global basis (see Authentication section above).

var dns = gcloud.dns({
projectId: 'my-project',
keyFilename: '/path/to/keyfile.json'
});

// Create a managed zone.
dns.createZone('my-new-zone', {
dnsName: 'my-domain.com.'
...
```

#### <a name="apidoc.element.gcloud.logging"></a>[function <span class="apidocSignatureSpan">gcloud.</span>logging (options)](#apidoc.element.gcloud.logging)
- description and source-code
```javascript
function Logging(options) {
  if (!(this instanceof Logging)) {
    options = util.normalizeArguments(this, options);
    return new Logging(options);
  }

  var config = {
    baseUrl: 'logging.googleapis.com',
    service: 'logging',
    apiVersion: 'v2',
    protoServices: {
      ConfigServiceV2:
        googleProtoFiles('logging', 'v2', 'logging_config.proto'),
      LoggingServiceV2: googleProtoFiles.logging.v2
    },
    scopes: [
      'https://www.googleapis.com/auth/cloud-platform'
    ]
  };

  GrpcService.call(this, config, options);
}
```
- example usage
```shell
...
// basis (see Authentication section above).

var gcloud = require('gcloud')({
  projectId: 'my-project',
  keyFilename: '/path/to/keyfile.json'
});

var logging = gcloud.logging();

// Create a sink using a Bucket as a destination.
var gcs = gcloud.storage();

logging.createSink('my-new-sink', {
  destination: gcs.bucket('my-sink')
}, function(err, sink) {});
...
```

#### <a name="apidoc.element.gcloud.prediction"></a>[function <span class="apidocSignatureSpan">gcloud.</span>prediction (options)](#apidoc.element.gcloud.prediction)
- description and source-code
```javascript
function Prediction(options) {
  if (!(this instanceof Prediction)) {
    options = util.normalizeArguments(this, options);
    return new Prediction(options);
  }

  var config = {
    baseUrl: 'https://www.googleapis.com/prediction/v1.6',
    scopes: [
      'https://www.googleapis.com/auth/prediction',
      'https://www.googleapis.com/auth/devstorage.read_only'
    ]
  };

  Service.call(this, config, options);
}
```
- example usage
```shell
...

'''js
var gcloud = require('gcloud');

// Authenticating on a per-API-basis. You don't need to do this if you auth on a
// global basis (see Authentication section above).

var prediction = gcloud.prediction({
projectId: 'my-project',
keyFilename: '/path/to/keyfile.json'
});

// Get all of the trained models in your project.
prediction.getModels(function(err, models) {
if (!err) {
...
```

#### <a name="apidoc.element.gcloud.pubsub"></a>[function <span class="apidocSignatureSpan">gcloud.</span>pubsub (options)](#apidoc.element.gcloud.pubsub)
- description and source-code
```javascript
function PubSub(options) {
  if (!(this instanceof PubSub)) {
    options = util.normalizeArguments(this, options);
    return new PubSub(options);
  }

  this.defaultBaseUrl_ = 'pubsub.googleapis.com';
  this.determineBaseUrl_();

  var config = {
    baseUrl: this.baseUrl_,
    customEndpoint: this.customEndpoint_,
    service: 'pubsub',
    apiVersion: 'v1',
    scopes: [
      'https://www.googleapis.com/auth/pubsub',
      'https://www.googleapis.com/auth/cloud-platform'
    ]
  };

  this.options = options;

  GrpcService.call(this, config, options);
}
```
- example usage
```shell
...

'''js
var gcloud = require('gcloud');

// Authenticating on a per-API-basis. You don't need to do this if you
// auth on a global basis (see Authentication section above).

var pubsub = gcloud.pubsub({
  projectId: 'my-project',
  keyFilename: '/path/to/keyfile.json'
});

// Reference a topic that has been previously created.
var topic = pubsub.topic('my-topic');
...
```

#### <a name="apidoc.element.gcloud.resource"></a>[function <span class="apidocSignatureSpan">gcloud.</span>resource (options)](#apidoc.element.gcloud.resource)
- description and source-code
```javascript
function Resource(options) {
  if (!(this instanceof Resource)) {
    options = util.normalizeArguments(this, options, {
      projectIdRequired: false
    });
    return new Resource(options);
  }

  var config = {
    baseUrl: 'https://cloudresourcemanager.googleapis.com/v1beta1',
    scopes: ['https://www.googleapis.com/auth/cloud-platform'],
    projectIdRequired: false
  };

  Service.call(this, config, options);

  this.defaultProjectId_ = options.projectId;
}
```
- example usage
```shell
...

'''js
var gcloud = require('gcloud');

// Authorizing on a per-API-basis. You don't need to do this if you auth on a
// global basis (see Authorization section above).

var resource = gcloud.resource({
projectId: 'my-project',
keyFilename: '/path/to/keyfile.json'
});

// Get all of the projects you maintain.
resource.getProjects(function(err, projects) {
if (!err) {
...
```

#### <a name="apidoc.element.gcloud.storage"></a>[function <span class="apidocSignatureSpan">gcloud.</span>storage (options)](#apidoc.element.gcloud.storage)
- description and source-code
```javascript
function Storage(options) {
  if (!(this instanceof Storage)) {
    options = util.normalizeArguments(this, options);
    return new Storage(options);
  }

  var config = {
    baseUrl: 'https://www.googleapis.com/storage/v1',
    projectIdRequired: false,
    scopes: [
      'https://www.googleapis.com/auth/devstorage.full_control'
    ]
  };

  Service.call(this, config, options);
}
```
- example usage
```shell
...
'''js
var fs = require('fs');
var gcloud = require('gcloud');

// Authenticating on a per-API-basis. You don't need to do this if you auth on a
// global basis (see Authentication section above).

var gcs = gcloud.storage({
projectId: 'my-project',
keyFilename: '/path/to/keyfile.json'
});

// Create a new bucket.
gcs.createBucket('my-new-bucket', function(err, bucket) {
if (!err) {
...
```

#### <a name="apidoc.element.gcloud.translate"></a>[function <span class="apidocSignatureSpan">gcloud.</span>translate (options)](#apidoc.element.gcloud.translate)
- description and source-code
```javascript
function Translate(options) {
  if (!(this instanceof Translate)) {
    options = util.normalizeArguments(this, options, {
      projectIdRequired: false
    });
    return new Translate(options);
  }

  if (!options.key) {
    throw new Error('An API key is required to use the Translate API.');
  }

  this.options = options;
  this.key = options.key;
}
```
- example usage
```shell
...
#### Preview

'''js
var gcloud = require('gcloud');

// Authenticating on a per-API-basis. You don't need to do this if you auth on a
// global basis (see Authentication section above).
var translate = gcloud.translate({
key: 'API Key'
});

// Translate a string of text.
translate.translate('Hello', 'es', function(err, translation) {
if (!err) {
  // translation = 'Hola'
...
```

#### <a name="apidoc.element.gcloud.vision"></a>[function <span class="apidocSignatureSpan">gcloud.</span>vision (options)](#apidoc.element.gcloud.vision)
- description and source-code
```javascript
function Vision(options) {
  if (!(this instanceof Vision)) {
    options = util.normalizeArguments(this, options);
    return new Vision(options);
  }

  var config = {
    baseUrl: 'https://vision.googleapis.com/v1',
    projectIdRequired: false,
    scopes: [
      'https://www.googleapis.com/auth/cloud-platform'
    ]
  };

  Service.call(this, config, options);
}
```
- example usage
```shell
...

'''js
var gcloud = require('gcloud');

// Authorizing on a per-API-basis. You don't need to do this if you auth on a
// global basis (see Authorization section above).

var vision = gcloud.vision({
projectId: 'my-project',
keyFilename: '/path/to/keyfile.json'
});

// Read the text from an image.
vision.detectText('./image.jpg', function(err, text) {
// text = [
...
```



# <a name="apidoc.module.gcloud.bigquery"></a>[module gcloud.bigquery](#apidoc.module.gcloud.bigquery)

#### <a name="apidoc.element.gcloud.bigquery.bigquery"></a>[function <span class="apidocSignatureSpan">gcloud.</span>bigquery (options)](#apidoc.element.gcloud.bigquery.bigquery)
- description and source-code
```javascript
function BigQuery(options) {
  if (!(this instanceof BigQuery)) {
    options = util.normalizeArguments(this, options);
    return new BigQuery(options);
  }

  var config = {
    baseUrl: 'https://www.googleapis.com/bigquery/v2',
    scopes: ['https://www.googleapis.com/auth/bigquery']
  };

  Service.call(this, config, options);
}
```
- example usage
```shell
...
#### Preview

'''js
var gcloud = require('gcloud');

// Authenticating on a per-API-basis. You don't need to do this if you auth on a
// global basis (see Authentication section above).
var bigquery = gcloud.bigquery({
  projectId: 'my-project',
  keyFilename: '/path/to/keyfile.json'
});

// Access an existing dataset and table.
var schoolsDataset = bigquery.dataset('schools');
var schoolsTable = schoolsDataset.table('schoolsData');
...
```

#### <a name="apidoc.element.gcloud.bigquery.super_"></a>[function <span class="apidocSignatureSpan">gcloud.bigquery.</span>super_ (config, options)](#apidoc.element.gcloud.bigquery.super_)
- description and source-code
```javascript
function Service(config, options) {
  var reqCfg = extend({}, config, {
    credentials: options.credentials,
    keyFile: options.keyFilename,
    email: options.email
  });

  this.makeAuthenticatedRequest = util.makeAuthenticatedRequestFactory(reqCfg);

  this.authClient = this.makeAuthenticatedRequest.authClient;
  this.baseUrl = config.baseUrl;
  this.getCredentials = this.makeAuthenticatedRequest.getCredentials;
  this.globalInterceptors = arrify(options.interceptors_);
  this.interceptors = [];
  this.projectId = options.projectId;
  this.projectIdRequired = config.projectIdRequired !== false;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gcloud.bigquery.prototype"></a>[module gcloud.bigquery.prototype](#apidoc.module.gcloud.bigquery.prototype)

#### <a name="apidoc.element.gcloud.bigquery.prototype.createDataset"></a>[function <span class="apidocSignatureSpan">gcloud.bigquery.prototype.</span>createDataset (id, options, callback)](#apidoc.element.gcloud.bigquery.prototype.createDataset)
- description and source-code
```javascript
createDataset = function (id, options, callback) {
  var that = this;

  if (is.fn(options)) {
    callback = options;
    options = {};
  }

  this.request({
    method: 'POST',
    uri: '/datasets',
    json: extend(true, {}, options, {
      datasetReference: {
        datasetId: id
      }
    })
  }, function(err, resp) {
    if (err) {
      callback(err, null, resp);
      return;
    }

    var dataset = that.dataset(id);
    dataset.metadata = resp;

    callback(null, dataset, resp);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.bigquery.prototype.dataset"></a>[function <span class="apidocSignatureSpan">gcloud.bigquery.prototype.</span>dataset (id)](#apidoc.element.gcloud.bigquery.prototype.dataset)
- description and source-code
```javascript
dataset = function (id) {
  return new Dataset(this, id);
}
```
- example usage
```shell
...
// global basis (see Authentication section above).
var bigquery = gcloud.bigquery({
  projectId: 'my-project',
  keyFilename: '/path/to/keyfile.json'
});

// Access an existing dataset and table.
var schoolsDataset = bigquery.dataset('schools');
var schoolsTable = schoolsDataset.table('schoolsData');

// Import data into a table.
schoolsTable.import('/local/file.json', function(err, job) {});

// Get results from a query job.
var job = bigquery.job('job-id');
...
```

#### <a name="apidoc.element.gcloud.bigquery.prototype.getDatasets"></a>[function <span class="apidocSignatureSpan">gcloud.bigquery.prototype.</span>getDatasets ()](#apidoc.element.gcloud.bigquery.prototype.getDatasets)
- description and source-code
```javascript
getDatasets = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.bigquery.prototype.getJobs"></a>[function <span class="apidocSignatureSpan">gcloud.bigquery.prototype.</span>getJobs ()](#apidoc.element.gcloud.bigquery.prototype.getJobs)
- description and source-code
```javascript
getJobs = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.bigquery.prototype.job"></a>[function <span class="apidocSignatureSpan">gcloud.bigquery.prototype.</span>job (id)](#apidoc.element.gcloud.bigquery.prototype.job)
- description and source-code
```javascript
job = function (id) {
  return new Job(this, id);
}
```
- example usage
```shell
...
var schoolsDataset = bigquery.dataset('schools');
var schoolsTable = schoolsDataset.table('schoolsData');

// Import data into a table.
schoolsTable.import('/local/file.json', function(err, job) {});

// Get results from a query job.
var job = bigquery.job('job-id');

// Use a callback.
job.getQueryResults(function(err, rows) {});

// Or get the same results as a readable stream.
job.getQueryResults().on('data', function(row) {});
'''
...
```

#### <a name="apidoc.element.gcloud.bigquery.prototype.query"></a>[function <span class="apidocSignatureSpan">gcloud.bigquery.prototype.</span>query ()](#apidoc.element.gcloud.bigquery.prototype.query)
- description and source-code
```javascript
query = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
...
// Reference an existing trained model.
var model = prediction.model('my-existing-model');

// Train a model.
model.train('english', 'Hello from your friends at Google!', function(err) {});

// Query a model.
model.query('Hello', function(err, results) {
if (!err) {
  // results.winner == 'english'
  // results.scores == [
  //   {
  //     label: 'english',
  //     score: 1
  //   },
...
```

#### <a name="apidoc.element.gcloud.bigquery.prototype.startQuery"></a>[function <span class="apidocSignatureSpan">gcloud.bigquery.prototype.</span>startQuery (options, callback)](#apidoc.element.gcloud.bigquery.prototype.startQuery)
- description and source-code
```javascript
startQuery = function (options, callback) {
  var that = this;

  if (is.string(options)) {
    options = {
      query: options
    };
  }

  options = options || {};

  if (!options.query) {
    throw new Error('A SQL query string is required.');
  }

  var defaults = {};

  if (options.destination) {
    if (!(options.destination instanceof Table)) {
      throw new Error('Destination must be a Table object.');
    }
    defaults.destinationTable = {
      datasetId: options.destination.dataset.id,
      projectId: options.destination.dataset.bigQuery.projectId,
      tableId: options.destination.id
    };
    delete options.destination;
  }

  var body = {
    configuration: {
      query: extend(true, defaults, options)
    }
  };

  this.request({
    method: 'POST',
    uri: '/jobs',
    json: body
  }, function(err, resp) {
    if (err) {
      callback(err, null, resp);
      return;
    }

    var job = that.job(resp.jobReference.jobId);
    job.metadata = resp;

    callback(null, job, resp);
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gcloud.bigquery.super_"></a>[module gcloud.bigquery.super_](#apidoc.module.gcloud.bigquery.super_)

#### <a name="apidoc.element.gcloud.bigquery.super_.super_"></a>[function <span class="apidocSignatureSpan">gcloud.bigquery.</span>super_ (config, options)](#apidoc.element.gcloud.bigquery.super_.super_)
- description and source-code
```javascript
function Service(config, options) {
  var reqCfg = extend({}, config, {
    credentials: options.credentials,
    keyFile: options.keyFilename,
    email: options.email
  });

  this.makeAuthenticatedRequest = util.makeAuthenticatedRequestFactory(reqCfg);

  this.authClient = this.makeAuthenticatedRequest.authClient;
  this.baseUrl = config.baseUrl;
  this.getCredentials = this.makeAuthenticatedRequest.getCredentials;
  this.globalInterceptors = arrify(options.interceptors_);
  this.interceptors = [];
  this.projectId = options.projectId;
  this.projectIdRequired = config.projectIdRequired !== false;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gcloud.bigquery.super_.prototype"></a>[module gcloud.bigquery.super_.prototype](#apidoc.module.gcloud.bigquery.super_.prototype)

#### <a name="apidoc.element.gcloud.bigquery.super_.prototype.request"></a>[function <span class="apidocSignatureSpan">gcloud.bigquery.super_.prototype.</span>request (reqOpts, callback)](#apidoc.element.gcloud.bigquery.super_.prototype.request)
- description and source-code
```javascript
request = function (reqOpts, callback) {
  reqOpts = extend(true, {}, reqOpts);

  var isAbsoluteUrl = reqOpts.uri.indexOf('http') === 0;

  var uriComponents = [
    this.baseUrl
  ];

  if (this.projectIdRequired) {
    uriComponents.push('projects');
    uriComponents.push(this.projectId);
  }

  uriComponents.push(reqOpts.uri);

  if (isAbsoluteUrl) {
    uriComponents.splice(0, uriComponents.indexOf(reqOpts.uri));
  }

  reqOpts.uri = uriComponents
    .map(function(uriComponent) {
      var trimSlashesRegex = /^\/*|\/*$/g;
      return uriComponent.replace(trimSlashesRegex, '');
    })
    .join('/')
    // Some URIs have colon separators.
    // Bad: https://.../projects/:list
    // Good: https://.../projects:list
    .replace(/\/:/g, ':');

  // Interceptors should be called in the order they were assigned.
  var combinedInterceptors = [].slice.call(this.globalInterceptors)
    .concat(this.interceptors)
    .concat(arrify(reqOpts.interceptors_));

  var interceptor;

  while ((interceptor = combinedInterceptors.shift()) && interceptor.request) {
    reqOpts = interceptor.request(reqOpts);
  }

  delete reqOpts.interceptors_;

  return this.makeAuthenticatedRequest(reqOpts, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gcloud.bigtable"></a>[module gcloud.bigtable](#apidoc.module.gcloud.bigtable)

#### <a name="apidoc.element.gcloud.bigtable.bigtable"></a>[function <span class="apidocSignatureSpan">gcloud.</span>bigtable (options)](#apidoc.element.gcloud.bigtable.bigtable)
- description and source-code
```javascript
function Bigtable(options) {
  if (!(this instanceof Bigtable)) {
    options = util.normalizeArguments(this, options);
    return new Bigtable(options);
  }

  options = extend({}, options, {
    zone: options.zone.name || options.zone
  });

  this.clusterName = format(
    'projects/{projectId}/zones/{zone}/clusters/{cluster}',
    options
  );

  var config = {
    baseUrl: 'bigtable.googleapis.com',
    service: 'bigtable',
    apiVersion: 'v1',
    protoServices: {
      BigtableService: googleProtoFiles.bigtable.v1,
      BigtableTableService: {
        path: googleProtoFiles.bigtable.admin,
        service: 'bigtable.admin.table'
      }
    },
    scopes: [
      'https://www.googleapis.com/auth/bigtable.admin',
      'https://www.googleapis.com/auth/bigtable.data'
    ]
  };

  GrpcService.call(this, config, options);
}
```
- example usage
```shell
...
#### Preview

'''js
var gcloud = require('gcloud');

// Authenticating on a per-API-basis. You don't need to do this if you auth on a
// global basis (see Authentication section above).
var bigtable = gcloud.bigtable({
  projectId: 'my-project',
  keyFilename: '/path/to/keyfile.json',
  zone: 'my-zone',
  cluster: 'my-cluster'
});

var table = bigtable.table('prezzy');
...
```

#### <a name="apidoc.element.gcloud.bigtable.formatTableName_"></a>[function <span class="apidocSignatureSpan">gcloud.bigtable.</span>formatTableName_ (name)](#apidoc.element.gcloud.bigtable.formatTableName_)
- description and source-code
```javascript
formatTableName_ = function (name) {
  if (name.indexOf('/') === -1) {
    return name;
  }

  var parts = name.split('/');
  return parts[parts.length - 1];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.bigtable.super_"></a>[function <span class="apidocSignatureSpan">gcloud.bigtable.</span>super_ (config, options)](#apidoc.element.gcloud.bigtable.super_)
- description and source-code
```javascript
function GrpcService(config, options) {
  if (global.GCLOUD_SANDBOX_ENV) {
    // gRPC has a tendency to cause our doc unit tests to fail, so we prevent
    // any calls to that library from going through.
    // Reference: https://github.com/GoogleCloudPlatform/gcloud-node/pull/1137#issuecomment-193315047
    return global.GCLOUD_SANDBOX_ENV;
  }

  Service.call(this, config, options);

  if (config.customEndpoint) {
    this.grpcCredentials = grpc.credentials.createInsecure();
  }

  this.maxRetries = options.maxRetries;

  var apiVersion = config.apiVersion;
  var service = this.service = config.service;

  this.activeServiceMap_ = new Map();
  this.protos = {};

  var protoServices = config.protoServices;

  if (!protoServices) {
    protoServices = {};
    protoServices[service] = googleProtoFiles[service][apiVersion];
  }

  for (var protoServiceName in protoServices) {
    var protoService = this.loadProtoFile_(
      protoServices[protoServiceName], config);

    this.protos[protoServiceName] = protoService;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gcloud.bigtable.prototype"></a>[module gcloud.bigtable.prototype](#apidoc.module.gcloud.bigtable.prototype)

#### <a name="apidoc.element.gcloud.bigtable.prototype.createTable"></a>[function <span class="apidocSignatureSpan">gcloud.bigtable.prototype.</span>createTable (name, options, callback)](#apidoc.element.gcloud.bigtable.prototype.createTable)
- description and source-code
```javascript
createTable = function (name, options, callback) {
  var self = this;

  options = options || {};

  if (is.function(options)) {
    callback = options;
    options = {};
  }

  var protoOpts = {
    service: 'BigtableTableService',
    method: 'createTable'
  };

  var reqOpts = {
    name: this.clusterName,
    tableId: name,
    table: {
      // The granularity at which timestamps are stored in the table.
      // Currently only milliseconds is supported, so it's not configurable.
      granularity: 0
    }
  };

  if (options.operation) {
    reqOpts.table.currentOperation = options.operation;
  }

  if (options.splits) {
    reqOpts.initialSplitKeys = options.splits;
  }

  this.request(protoOpts, reqOpts, function(err, resp) {
    if (err) {
      callback(err, null, resp);
      return;
    }

    var table = self.table(resp.name);
    table.metadata = resp;

    callback(null, table, resp);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.bigtable.prototype.getTables"></a>[function <span class="apidocSignatureSpan">gcloud.bigtable.prototype.</span>getTables (callback)](#apidoc.element.gcloud.bigtable.prototype.getTables)
- description and source-code
```javascript
getTables = function (callback) {
  var self = this;

  var protoOpts = {
    service: 'BigtableTableService',
    method: 'listTables'
  };

  var reqOpts = {
    name: this.clusterName
  };

  this.request(protoOpts, reqOpts, function(err, resp) {
    if (err) {
      callback(err, null, resp);
      return;
    }

    var tables = resp.tables.map(function(metadata) {
      var name = Bigtable.formatTableName_(metadata.name);
      var table = self.table(name);

      table.metadata = metadata;
      return table;
    });

    callback(null, tables, resp);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.bigtable.prototype.table"></a>[function <span class="apidocSignatureSpan">gcloud.bigtable.prototype.</span>table (name)](#apidoc.element.gcloud.bigtable.prototype.table)
- description and source-code
```javascript
table = function (name) {
  return new Table(this, name);
}
```
- example usage
```shell
...
var bigquery = gcloud.bigquery({
  projectId: 'my-project',
  keyFilename: '/path/to/keyfile.json'
});

// Access an existing dataset and table.
var schoolsDataset = bigquery.dataset('schools');
var schoolsTable = schoolsDataset.table('schoolsData');

// Import data into a table.
schoolsTable.import('/local/file.json', function(err, job) {});

// Get results from a query job.
var job = bigquery.job('job-id');
...
```



# <a name="apidoc.module.gcloud.bigtable.super_"></a>[module gcloud.bigtable.super_](#apidoc.module.gcloud.bigtable.super_)

#### <a name="apidoc.element.gcloud.bigtable.super_.super_"></a>[function <span class="apidocSignatureSpan">gcloud.bigtable.</span>super_ (config, options)](#apidoc.element.gcloud.bigtable.super_.super_)
- description and source-code
```javascript
function Service(config, options) {
  var reqCfg = extend({}, config, {
    credentials: options.credentials,
    keyFile: options.keyFilename,
    email: options.email
  });

  this.makeAuthenticatedRequest = util.makeAuthenticatedRequestFactory(reqCfg);

  this.authClient = this.makeAuthenticatedRequest.authClient;
  this.baseUrl = config.baseUrl;
  this.getCredentials = this.makeAuthenticatedRequest.getCredentials;
  this.globalInterceptors = arrify(options.interceptors_);
  this.interceptors = [];
  this.projectId = options.projectId;
  this.projectIdRequired = config.projectIdRequired !== false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.bigtable.super_.createDeadline_"></a>[function <span class="apidocSignatureSpan">gcloud.bigtable.super_.</span>createDeadline_ (timeout)](#apidoc.element.gcloud.bigtable.super_.createDeadline_)
- description and source-code
```javascript
createDeadline_ = function (timeout) {
  return new Date(Date.now() + timeout);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.bigtable.super_.decodeValue_"></a>[function <span class="apidocSignatureSpan">gcloud.bigtable.super_.</span>decodeValue_ (value)](#apidoc.element.gcloud.bigtable.super_.decodeValue_)
- description and source-code
```javascript
decodeValue_ = function (value) {
  switch (value.kind) {
    case 'structValue': {
      return GrpcService.structToObj_(value.structValue);
    }

    case 'nullValue': {
      return null;
    }

    case 'listValue': {
      return value.listValue.values.map(GrpcService.decodeValue_);
    }

    default: {
      return value[value.kind];
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.bigtable.super_.decorateError_"></a>[function <span class="apidocSignatureSpan">gcloud.bigtable.super_.</span>decorateError_ (err)](#apidoc.element.gcloud.bigtable.super_.decorateError_)
- description and source-code
```javascript
decorateError_ = function (err) {
  var errorObj = is.error(err) ? new Error() : {};
  return GrpcService.decorateGrpcResponse_(errorObj, err);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.bigtable.super_.decorateGrpcResponse_"></a>[function <span class="apidocSignatureSpan">gcloud.bigtable.super_.</span>decorateGrpcResponse_ (obj, response)](#apidoc.element.gcloud.bigtable.super_.decorateGrpcResponse_)
- description and source-code
```javascript
decorateGrpcResponse_ = function (obj, response) {
  if (response && GRPC_ERROR_CODE_TO_HTTP[response.code]) {
    var defaultResponseDetails = GRPC_ERROR_CODE_TO_HTTP[response.code];

    return extend(true, obj, response, {
      code: defaultResponseDetails.code,
      message: response.message || defaultResponseDetails.message
    });
  }

  return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.bigtable.super_.decorateStatus_"></a>[function <span class="apidocSignatureSpan">gcloud.bigtable.super_.</span>decorateStatus_ (status)](#apidoc.element.gcloud.bigtable.super_.decorateStatus_)
- description and source-code
```javascript
decorateStatus_ = function (status) {
  return GrpcService.decorateGrpcResponse_({}, status);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.bigtable.super_.encodeValue_"></a>[function <span class="apidocSignatureSpan">gcloud.bigtable.super_.</span>encodeValue_ (value, options)](#apidoc.element.gcloud.bigtable.super_.encodeValue_)
- description and source-code
```javascript
encodeValue_ = function (value, options) {
  options = options || {};

  var convertedValue;

  if (is.null(value)) {
    convertedValue = {
      nullValue: 0
    };
  } else if (is.number(value)) {
    convertedValue = {
      numberValue: value
    };
  } else if (is.string(value)) {
    convertedValue = {
      stringValue: value
    };
  } else if (is.boolean(value)) {
    convertedValue = {
      boolValue: value
    };
  } else if (Buffer.isBuffer(value)) {
    convertedValue = {
      blobValue: value
    };
  } else if (is.object(value)) {
    convertedValue = {
      structValue: GrpcService.objToStruct_(value)
    };
  } else if (is.array(value)) {
    convertedValue = {
      listValue: {
        values: value.map(GrpcService.encodeValue_)
      }
    };
  } else {
    if (!options.stringify) {
      throw new Error('Value of type ' + typeof value + ' not recognized.');
    }

    convertedValue = {
      stringValue: String(value)
    };
  }

  return convertedValue;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.bigtable.super_.objToStruct_"></a>[function <span class="apidocSignatureSpan">gcloud.bigtable.super_.</span>objToStruct_ (obj, options)](#apidoc.element.gcloud.bigtable.super_.objToStruct_)
- description and source-code
```javascript
objToStruct_ = function (obj, options) {
  options = options || {};

  var convertedObject = {
    fields: {}
  };

  for (var prop in obj) {
    if (obj.hasOwnProperty(prop)) {
      var value = obj[prop];

      if (is.undefined(value)) {
        continue;
      }

      convertedObject.fields[prop] = GrpcService.encodeValue_(value, options);
    }
  }

  return convertedObject;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.bigtable.super_.shouldRetryRequest_"></a>[function <span class="apidocSignatureSpan">gcloud.bigtable.super_.</span>shouldRetryRequest_ (response)](#apidoc.element.gcloud.bigtable.super_.shouldRetryRequest_)
- description and source-code
```javascript
shouldRetryRequest_ = function (response) {
  return [429, 500, 502, 503].indexOf(response.code) > -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.bigtable.super_.structToObj_"></a>[function <span class="apidocSignatureSpan">gcloud.bigtable.super_.</span>structToObj_ (struct)](#apidoc.element.gcloud.bigtable.super_.structToObj_)
- description and source-code
```javascript
structToObj_ = function (struct) {
  var convertedObject = {};

  for (var prop in struct.fields) {
    if (struct.fields.hasOwnProperty(prop)) {
      var value = struct.fields[prop];
      convertedObject[prop] = GrpcService.decodeValue_(value);
    }
  }

  return convertedObject;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gcloud.bigtable.super_.prototype"></a>[module gcloud.bigtable.super_.prototype](#apidoc.module.gcloud.bigtable.super_.prototype)

#### <a name="apidoc.element.gcloud.bigtable.super_.prototype.getGrpcCredentials_"></a>[function <span class="apidocSignatureSpan">gcloud.bigtable.super_.prototype.</span>getGrpcCredentials_ (callback)](#apidoc.element.gcloud.bigtable.super_.prototype.getGrpcCredentials_)
- description and source-code
```javascript
getGrpcCredentials_ = function (callback) {
  this.authClient.getAuthClient(function(err, authClient) {
    if (err) {
      callback(err);
      return;
    }

    var credentials = grpc.credentials.combineChannelCredentials(
      grpc.credentials.createSsl(),
      grpc.credentials.createFromGoogleCredential(authClient)
    );

    callback(null, credentials);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.bigtable.super_.prototype.getService_"></a>[function <span class="apidocSignatureSpan">gcloud.bigtable.super_.prototype.</span>getService_ (protoOpts)](#apidoc.element.gcloud.bigtable.super_.prototype.getService_)
- description and source-code
```javascript
getService_ = function (protoOpts) {
  var proto;

  if (this.protos[protoOpts.service]) {
    proto = this.protos[protoOpts.service];
  } else {
    proto = this.protos[this.service];
  }

  var service = this.activeServiceMap_.get(protoOpts.service);

  if (!service) {
    service = new proto[protoOpts.service](
      this.baseUrl,
      this.grpcCredentials
    );

    this.activeServiceMap_.set(protoOpts.service, service);
  }

  return service;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.bigtable.super_.prototype.loadProtoFile_"></a>[function <span class="apidocSignatureSpan">gcloud.bigtable.super_.prototype.</span>loadProtoFile_ (protoConfig, config)](#apidoc.element.gcloud.bigtable.super_.prototype.loadProtoFile_)
- description and source-code
```javascript
loadProtoFile_ = function (protoConfig, config) {
  var rootDir = googleProtoFiles('..');

  var grpcOpts = {
    binaryAsBase64: true,
    convertFieldsToCamelCase: true
  };

  if (is.string(protoConfig)) {
    protoConfig = {
      path: protoConfig
    };
  }

  var services = grpc.load({
    root: rootDir,
    file: path.relative(rootDir, protoConfig.path)
  }, 'proto', grpcOpts);

  var serviceName = protoConfig.service || config.service;
  var apiVersion = protoConfig.apiVersion || config.apiVersion;
  var service = dotProp.get(services.google, serviceName);

  return service[apiVersion];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.bigtable.super_.prototype.request"></a>[function <span class="apidocSignatureSpan">gcloud.bigtable.super_.prototype.</span>request (protoOpts, reqOpts, callback)](#apidoc.element.gcloud.bigtable.super_.prototype.request)
- description and source-code
```javascript
request = function (protoOpts, reqOpts, callback) {
  if (global.GCLOUD_SANDBOX_ENV) {
    return global.GCLOUD_SANDBOX_ENV;
  }

  var self = this;

  if (!this.grpcCredentials) {
    // We must establish an authClient to give to grpc.
    this.getGrpcCredentials_(function(err, credentials) {
      if (err) {
        callback(err);
        return;
      }

      self.grpcCredentials = credentials;
      self.request(protoOpts, reqOpts, callback);
    });

    return;
  }

  // Clean up gcloud-specific options.
  delete reqOpts.autoPaginate;
  delete reqOpts.autoPaginateVal;

  var service = this.getService_(protoOpts);
  var grpcOpts = {};

  if (is.number(protoOpts.timeout)) {
    grpcOpts.deadline = GrpcService.createDeadline_(protoOpts.timeout);
  }

  // Retains a reference to an error from the response. If the final callback is
  // executed with this as the "response", we return it to the user as an error.
  var respError;

  var retryOpts = {
    retries: this.maxRetries,
    shouldRetryFn: GrpcService.shouldRetryRequest_,

    // retry-request determines if it should retry from the incoming HTTP
    // response status. gRPC always returns an error proto message. We pass that
    // "error" into retry-request to act as the HTTP response, so it can use the
    // status code to determine if it should retry.
    request: function(_, onResponse) {
      respError = null;

      service[protoOpts.method](reqOpts, grpcOpts, function(err, resp) {
        if (err) {
          respError = GrpcService.decorateError_(err);

          if (respError) {
            onResponse(null, respError);
            return;
          }

          onResponse(err, resp);
          return;
        }

        onResponse(null, resp);
      });
    }
  };

  retryRequest(null, retryOpts, function(err, resp) {
    if (!err && resp === respError) {
      err = respError;
      resp = null;
    }

    callback(err, resp);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.bigtable.super_.prototype.requestStream"></a>[function <span class="apidocSignatureSpan">gcloud.bigtable.super_.prototype.</span>requestStream (protoOpts, reqOpts)](#apidoc.element.gcloud.bigtable.super_.prototype.requestStream)
- description and source-code
```javascript
requestStream = function (protoOpts, reqOpts) {
  if (global.GCLOUD_SANDBOX_ENV) {
    return through.obj();
  }

  var self = this;

  if (!protoOpts.stream) {
    protoOpts.stream = through.obj();
  }

  var stream = protoOpts.stream;

  if (!this.grpcCredentials) {
    // We must establish an authClient to give to grpc.
    this.getGrpcCredentials_(function(err, credentials) {
      if (err) {
        stream.destroy(err);
        return;
      }

      self.grpcCredentials = credentials;
      self.requestStream(protoOpts, reqOpts);
    });

    return stream;
  }

  var objectMode = !!reqOpts.objectMode;
  delete reqOpts.objectMode;

  var service = this.getService_(protoOpts);
  var grpcOpts = {};

  if (is.number(protoOpts.timeout)) {
    grpcOpts.deadline = GrpcService.createDeadline_(protoOpts.timeout);
  }

  var retryOpts = {
    retries: this.maxRetries,
    objectMode: objectMode,
    shouldRetryFn: GrpcService.shouldRetryRequest_,

    request: function() {
      return service[protoOpts.method](reqOpts, grpcOpts)
        .on('status', function(status) {
          var grcpStatus = GrpcService.decorateStatus_(status);

          this.emit('response', grcpStatus || status);
        });
    }
  };

  return retryRequest(null, retryOpts)
    .on('error', function(err) {
      var grpcError = GrpcService.decorateError_(err);

      stream.destroy(grpcError || err);
    })
    .pipe(stream);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gcloud.compute"></a>[module gcloud.compute](#apidoc.module.gcloud.compute)

#### <a name="apidoc.element.gcloud.compute.compute"></a>[function <span class="apidocSignatureSpan">gcloud.</span>compute (options)](#apidoc.element.gcloud.compute.compute)
- description and source-code
```javascript
function Compute(options) {
  if (!(this instanceof Compute)) {
    options = util.normalizeArguments(this, options);
    return new Compute(options);
  }

  var config = {
    baseUrl: 'https://www.googleapis.com/compute/v1',
    scopes: ['https://www.googleapis.com/auth/compute']
  };

  Service.call(this, config, options);
}
```
- example usage
```shell
...

'''js
var gcloud = require('gcloud');

// Authenticating on a per-API-basis. You don't need to do this if you auth on a
// global basis (see Authentication section above).

var gce = gcloud.compute({
  projectId: 'my-project',
  keyFilename: '/path/to/keyfile.json'
});

// Create a new VM using the latest OS image of your choice.
var zone = gce.zone('us-central1-a');
var name = 'ubuntu-http';
...
```

#### <a name="apidoc.element.gcloud.compute.super_"></a>[function <span class="apidocSignatureSpan">gcloud.compute.</span>super_ (config, options)](#apidoc.element.gcloud.compute.super_)
- description and source-code
```javascript
function Service(config, options) {
  var reqCfg = extend({}, config, {
    credentials: options.credentials,
    keyFile: options.keyFilename,
    email: options.email
  });

  this.makeAuthenticatedRequest = util.makeAuthenticatedRequestFactory(reqCfg);

  this.authClient = this.makeAuthenticatedRequest.authClient;
  this.baseUrl = config.baseUrl;
  this.getCredentials = this.makeAuthenticatedRequest.getCredentials;
  this.globalInterceptors = arrify(options.interceptors_);
  this.interceptors = [];
  this.projectId = options.projectId;
  this.projectIdRequired = config.projectIdRequired !== false;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gcloud.compute.prototype"></a>[module gcloud.compute.prototype](#apidoc.module.gcloud.compute.prototype)

#### <a name="apidoc.element.gcloud.compute.prototype.createFirewall"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>createFirewall (name, config, callback)](#apidoc.element.gcloud.compute.prototype.createFirewall)
- description and source-code
```javascript
createFirewall = function (name, config, callback) {
  var self = this;

  if (!is.string(name)) {
    throw new Error('A firewall name must be provided.');
  }

  if (!is.object(config)) {
    throw new Error('A firewall configuration object must be provided.');
  }

  var body = extend({}, config, {
    name: name
  });

  if (body.protocols) {
    body.allowed = arrify(body.allowed);

    for (var protocol in body.protocols) {
      var allowedConfig = {
        IPProtocol: protocol
      };

      var ports = body.protocols[protocol];

      if (ports === false || ports.length === 0) {
        continue;
      }

      // If the port is 'true', open up all ports on this protocol.
      allowedConfig.ports = ports === true ? [] : arrify(ports);

      body.allowed.push(allowedConfig);
    }

    delete body.protocols;
  }

  if (body.ranges) {
    body.sourceRanges = arrify(body.ranges);
    delete body.ranges;
  }

  if (body.tags) {
    body.sourceTags = arrify(body.tags);
    delete body.tags;
  }

  this.request({
    method: 'POST',
    uri: '/global/firewalls',
    json: body
  }, function(err, resp) {
    if (err) {
      callback(err, null, null, resp);
      return;
    }

    var firewall = self.firewall(name);

    var operation = self.operation(resp.name);
    operation.metadata = resp;

    callback(null, firewall, operation, resp);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.createHealthCheck"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>createHealthCheck (name, options, callback)](#apidoc.element.gcloud.compute.prototype.createHealthCheck)
- description and source-code
```javascript
createHealthCheck = function (name, options, callback) {
  var self = this;

  if (is.fn(options)) {
    callback = options;
    options = {};
  }

  if (!is.string(name)) {
    throw new Error('A health check name must be provided.');
  }

  var body = extend({}, options, {
    name: name
  });

  var https = options.https;
  delete body.https;

  if (body.interval) {
    body.checkIntervalSec = body.interval;
    delete body.interval;
  }

  if (body.timeout) {
    body.timeoutSec = body.timeout;
    delete body.timeout;
  }

  this.request({
    method: 'POST',
    uri: '/global/' + (https ? 'httpsHealthChecks' : 'httpHealthChecks'),
    json: body
  }, function(err, resp) {
    if (err) {
      callback(err, null, null, resp);
      return;
    }

    var healthCheck = self.healthCheck(name, {
      https: https
    });

    var operation = self.operation(resp.name);
    operation.metadata = resp;

    callback(null, healthCheck, operation, resp);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.createNetwork"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>createNetwork (name, config, callback)](#apidoc.element.gcloud.compute.prototype.createNetwork)
- description and source-code
```javascript
createNetwork = function (name, config, callback) {
  var self = this;

  var body = extend({}, config, {
    name: name
  });

  if (body.range) {
    body.IPv4Range = body.range;
    delete body.range;
  }

  if (body.gateway) {
    body.gatewayIPv4 = body.gateway;
    delete body.gateway;
  }

  this.request({
    method: 'POST',
    uri: '/global/networks',
    json: body
  }, function(err, resp) {
    if (err) {
      callback(err, null, null, resp);
      return;
    }

    var network = self.network(name);

    var operation = self.operation(resp.name);
    operation.metadata = resp;

    callback(null, network, operation, resp);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.createRule"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>createRule (name, config, callback)](#apidoc.element.gcloud.compute.prototype.createRule)
- description and source-code
```javascript
createRule = function (name, config, callback) {
  var self = this;

  var body = extend({}, config, {
    name: name
  });

  if (body.ip) {
    body.IPAddress = body.ip;
    delete body.ip;
  }

  if (body.protocol) {
    body.IPProtocol = body.protocol;
    delete body.protocol;
  }

  if (body.range) {
    body.portRange = body.range;
    delete body.range;
  }

  this.request({
    method: 'POST',
    uri: '/global/forwardingRules',
    json: body
  }, function(err, resp) {
    if (err) {
      callback(err, null, null, resp);
      return;
    }

    var rule = self.rule(name);

    var operation = self.operation(resp.name);
    operation.metadata = resp;

    callback(null, rule, operation, resp);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.createService"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>createService (name, config, callback)](#apidoc.element.gcloud.compute.prototype.createService)
- description and source-code
```javascript
createService = function (name, config, callback) {
  var self = this;

  var body = extend({}, config, {
    name: name
  });

  this.request({
    method: 'POST',
    uri: '/global/backendServices',
    json: body
  }, function(err, resp) {
    if (err) {
      callback(err, null, null, resp);
      return;
    }

    var service = self.service(name);

    var operation = self.operation(resp.name);
    operation.metadata = resp;

    callback(null, service, operation, resp);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.firewall"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>firewall (name)](#apidoc.element.gcloud.compute.prototype.firewall)
- description and source-code
```javascript
firewall = function (name) {
  return new Firewall(this, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.getAddresses"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getAddresses ()](#apidoc.element.gcloud.compute.prototype.getAddresses)
- description and source-code
```javascript
getAddresses = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.getAutoscalers"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getAutoscalers ()](#apidoc.element.gcloud.compute.prototype.getAutoscalers)
- description and source-code
```javascript
getAutoscalers = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.getDisks"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getDisks ()](#apidoc.element.gcloud.compute.prototype.getDisks)
- description and source-code
```javascript
getDisks = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.getFirewalls"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getFirewalls ()](#apidoc.element.gcloud.compute.prototype.getFirewalls)
- description and source-code
```javascript
getFirewalls = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.getHealthChecks"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getHealthChecks ()](#apidoc.element.gcloud.compute.prototype.getHealthChecks)
- description and source-code
```javascript
getHealthChecks = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.getInstanceGroups"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getInstanceGroups ()](#apidoc.element.gcloud.compute.prototype.getInstanceGroups)
- description and source-code
```javascript
getInstanceGroups = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.getNetworks"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getNetworks ()](#apidoc.element.gcloud.compute.prototype.getNetworks)
- description and source-code
```javascript
getNetworks = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.getOperations"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getOperations ()](#apidoc.element.gcloud.compute.prototype.getOperations)
- description and source-code
```javascript
getOperations = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.getRegions"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getRegions ()](#apidoc.element.gcloud.compute.prototype.getRegions)
- description and source-code
```javascript
getRegions = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.getRules"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getRules ()](#apidoc.element.gcloud.compute.prototype.getRules)
- description and source-code
```javascript
getRules = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.getServices"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getServices ()](#apidoc.element.gcloud.compute.prototype.getServices)
- description and source-code
```javascript
getServices = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.getSnapshots"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getSnapshots ()](#apidoc.element.gcloud.compute.prototype.getSnapshots)
- description and source-code
```javascript
getSnapshots = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.getVMs"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getVMs ()](#apidoc.element.gcloud.compute.prototype.getVMs)
- description and source-code
```javascript
getVMs = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.getZones"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>getZones ()](#apidoc.element.gcloud.compute.prototype.getZones)
- description and source-code
```javascript
getZones = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.healthCheck"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>healthCheck (name, options)](#apidoc.element.gcloud.compute.prototype.healthCheck)
- description and source-code
```javascript
healthCheck = function (name, options) {
  return new HealthCheck(this, name, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.network"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>network (name)](#apidoc.element.gcloud.compute.prototype.network)
- description and source-code
```javascript
network = function (name) {
  return new Network(this, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.operation"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>operation (name)](#apidoc.element.gcloud.compute.prototype.operation)
- description and source-code
```javascript
operation = function (name) {
  return new Operation(this, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.region"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>region (name)](#apidoc.element.gcloud.compute.prototype.region)
- description and source-code
```javascript
region = function (name) {
  return new Region(this, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.rule"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>rule (name)](#apidoc.element.gcloud.compute.prototype.rule)
- description and source-code
```javascript
rule = function (name) {
  return new Rule(this, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.service"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>service (name)](#apidoc.element.gcloud.compute.prototype.service)
- description and source-code
```javascript
service = function (name) {
  return new ServiceClass(this, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.snapshot"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>snapshot (name)](#apidoc.element.gcloud.compute.prototype.snapshot)
- description and source-code
```javascript
snapshot = function (name) {
  return new Snapshot(this, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.compute.prototype.zone"></a>[function <span class="apidocSignatureSpan">gcloud.compute.prototype.</span>zone (name)](#apidoc.element.gcloud.compute.prototype.zone)
- description and source-code
```javascript
zone = function (name) {
  return new Zone(this, name);
}
```
- example usage
```shell
...

// Create a managed zone.
dns.createZone('my-new-zone', {
  dnsName: 'my-domain.com.'
}, function(err, zone) {});

// Reference an existing zone.
var zone = dns.zone('my-existing-zone');

// Create an NS record.
var nsRecord = zone.record('ns', {
  ttl: 86400,
  name: 'my-domain.com.',
  data: 'ns-cloud1.googledomains.com.'
});
...
```



# <a name="apidoc.module.gcloud.datastore"></a>[module gcloud.datastore](#apidoc.module.gcloud.datastore)

#### <a name="apidoc.element.gcloud.datastore.datastore"></a>[function <span class="apidocSignatureSpan">gcloud.</span>datastore (options)](#apidoc.element.gcloud.datastore.datastore)
- description and source-code
```javascript
function Datastore(options) {
  if (!(this instanceof Datastore)) {
    options = util.normalizeArguments(this, options, {
      projectIdRequired: false
    });
    return new Datastore(options);
  }

  this.defaultBaseUrl_ = 'datastore.googleapis.com';
  this.determineBaseUrl_(options.apiEndpoint);

  this.namespace = options.namespace;
  this.projectId = process.env.DATASTORE_PROJECT_ID || options.projectId;

  var config = {
    projectIdRequired: false,
    baseUrl: this.baseUrl_,
    customEndpoint: this.customEndpoint_,
    service: 'datastore',
    apiVersion: 'v1beta3',
    scopes: ['https://www.googleapis.com/auth/datastore']
  };

  GrpcService.call(this, config, options);
}
```
- example usage
```shell
...

'''js
var gcloud = require('gcloud');

// Authenticating on a per-API-basis. You don't need to do this if you auth on a
// global basis (see Authentication section above).

var datastore = gcloud.datastore({
  projectId: 'my-project',
  keyFilename: '/path/to/keyfile.json'
});

var key = datastore.key(['Product', 'Computer']);

datastore.get(key, function(err, entity) {
...
```

#### <a name="apidoc.element.gcloud.datastore.double"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.</span>double (value)](#apidoc.element.gcloud.datastore.double)
- description and source-code
```javascript
double = function (value) {
  return new entity.Double(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.datastore.extend"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.</span>extend ()](#apidoc.element.gcloud.datastore.extend)
- description and source-code
```javascript
extend = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.datastore.geoPoint"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.</span>geoPoint (coordindates)](#apidoc.element.gcloud.datastore.geoPoint)
- description and source-code
```javascript
geoPoint = function (coordindates) {
  return new entity.GeoPoint(coordindates);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.datastore.int"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.</span>int (value)](#apidoc.element.gcloud.datastore.int)
- description and source-code
```javascript
int = function (value) {
  return new entity.Int(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.datastore.super_"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.</span>super_ ()](#apidoc.element.gcloud.datastore.super_)
- description and source-code
```javascript
function DatastoreRequest() {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gcloud.datastore.prototype"></a>[module gcloud.datastore.prototype](#apidoc.module.gcloud.datastore.prototype)

#### <a name="apidoc.element.gcloud.datastore.prototype.createQuery"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.prototype.</span>createQuery (namespace, kind)](#apidoc.element.gcloud.datastore.prototype.createQuery)
- description and source-code
```javascript
createQuery = function (namespace, kind) {
  if (arguments.length === 1) {
    kind = arrify(namespace);
    namespace = this.namespace;
  }

  return new Query(this, namespace, arrify(kind));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.datastore.prototype.determineBaseUrl_"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.prototype.</span>determineBaseUrl_ (customApiEndpoint)](#apidoc.element.gcloud.datastore.prototype.determineBaseUrl_)
- description and source-code
```javascript
determineBaseUrl_ = function (customApiEndpoint) {
  var baseUrl = this.defaultBaseUrl_;
  var leadingProtocol = new RegExp('^https*://');
  var trailingSlashes = new RegExp('/*$');

  if (customApiEndpoint) {
    baseUrl = customApiEndpoint;
    this.customEndpoint_ = true;
  } else if (process.env.DATASTORE_EMULATOR_HOST) {
    baseUrl = process.env.DATASTORE_EMULATOR_HOST;
    this.customEndpoint_ = true;
  }

  this.baseUrl_ = baseUrl
    .replace(leadingProtocol, '')
    .replace(trailingSlashes, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.datastore.prototype.getGrpcCredentials_"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.prototype.</span>getGrpcCredentials_ (callback)](#apidoc.element.gcloud.datastore.prototype.getGrpcCredentials_)
- description and source-code
```javascript
getGrpcCredentials_ = function (callback) {
  this.authClient.getAuthClient(function(err, authClient) {
    if (err) {
      callback(err);
      return;
    }

    var credentials = grpc.credentials.combineChannelCredentials(
      grpc.credentials.createSsl(),
      grpc.credentials.createFromGoogleCredential(authClient)
    );

    callback(null, credentials);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.datastore.prototype.getService_"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.prototype.</span>getService_ (protoOpts)](#apidoc.element.gcloud.datastore.prototype.getService_)
- description and source-code
```javascript
getService_ = function (protoOpts) {
  var proto;

  if (this.protos[protoOpts.service]) {
    proto = this.protos[protoOpts.service];
  } else {
    proto = this.protos[this.service];
  }

  var service = this.activeServiceMap_.get(protoOpts.service);

  if (!service) {
    service = new proto[protoOpts.service](
      this.baseUrl,
      this.grpcCredentials
    );

    this.activeServiceMap_.set(protoOpts.service, service);
  }

  return service;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.datastore.prototype.isInstance"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.prototype.</span>isInstance ()](#apidoc.element.gcloud.datastore.prototype.isInstance)
- description and source-code
```javascript
isInstance = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.datastore.prototype.key"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.prototype.</span>key (options)](#apidoc.element.gcloud.datastore.prototype.key)
- description and source-code
```javascript
key = function (options) {
  options = is.object(options) ? options : {
    namespace: this.namespace,
    path: arrify(options)
  };

  return new entity.Key(options);
}
```
- example usage
```shell
...
// global basis (see Authentication section above).

var datastore = gcloud.datastore({
  projectId: 'my-project',
  keyFilename: '/path/to/keyfile.json'
});

var key = datastore.key(['Product', 'Computer']);

datastore.get(key, function(err, entity) {
  console.log(err || entity);
});

// Save data to Datastore.
var blogPostData = {
...
```

#### <a name="apidoc.element.gcloud.datastore.prototype.loadProtoFile_"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.prototype.</span>loadProtoFile_ (protoConfig, config)](#apidoc.element.gcloud.datastore.prototype.loadProtoFile_)
- description and source-code
```javascript
loadProtoFile_ = function (protoConfig, config) {
  var rootDir = googleProtoFiles('..');

  var grpcOpts = {
    binaryAsBase64: true,
    convertFieldsToCamelCase: true
  };

  if (is.string(protoConfig)) {
    protoConfig = {
      path: protoConfig
    };
  }

  var services = grpc.load({
    root: rootDir,
    file: path.relative(rootDir, protoConfig.path)
  }, 'proto', grpcOpts);

  var serviceName = protoConfig.service || config.service;
  var apiVersion = protoConfig.apiVersion || config.apiVersion;
  var service = dotProp.get(services.google, serviceName);

  return service[apiVersion];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.datastore.prototype.request"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.prototype.</span>request (protoOpts, reqOpts, callback)](#apidoc.element.gcloud.datastore.prototype.request)
- description and source-code
```javascript
request = function (protoOpts, reqOpts, callback) {
  if (global.GCLOUD_SANDBOX_ENV) {
    return global.GCLOUD_SANDBOX_ENV;
  }

  var self = this;

  if (!this.grpcCredentials) {
    // We must establish an authClient to give to grpc.
    this.getGrpcCredentials_(function(err, credentials) {
      if (err) {
        callback(err);
        return;
      }

      self.grpcCredentials = credentials;
      self.request(protoOpts, reqOpts, callback);
    });

    return;
  }

  // Clean up gcloud-specific options.
  delete reqOpts.autoPaginate;
  delete reqOpts.autoPaginateVal;

  var service = this.getService_(protoOpts);
  var grpcOpts = {};

  if (is.number(protoOpts.timeout)) {
    grpcOpts.deadline = GrpcService.createDeadline_(protoOpts.timeout);
  }

  // Retains a reference to an error from the response. If the final callback is
  // executed with this as the "response", we return it to the user as an error.
  var respError;

  var retryOpts = {
    retries: this.maxRetries,
    shouldRetryFn: GrpcService.shouldRetryRequest_,

    // retry-request determines if it should retry from the incoming HTTP
    // response status. gRPC always returns an error proto message. We pass that
    // "error" into retry-request to act as the HTTP response, so it can use the
    // status code to determine if it should retry.
    request: function(_, onResponse) {
      respError = null;

      service[protoOpts.method](reqOpts, grpcOpts, function(err, resp) {
        if (err) {
          respError = GrpcService.decorateError_(err);

          if (respError) {
            onResponse(null, respError);
            return;
          }

          onResponse(err, resp);
          return;
        }

        onResponse(null, resp);
      });
    }
  };

  retryRequest(null, retryOpts, function(err, resp) {
    if (!err && resp === respError) {
      err = respError;
      resp = null;
    }

    callback(err, resp);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.datastore.prototype.requestStream"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.prototype.</span>requestStream (protoOpts, reqOpts)](#apidoc.element.gcloud.datastore.prototype.requestStream)
- description and source-code
```javascript
requestStream = function (protoOpts, reqOpts) {
  if (global.GCLOUD_SANDBOX_ENV) {
    return through.obj();
  }

  var self = this;

  if (!protoOpts.stream) {
    protoOpts.stream = through.obj();
  }

  var stream = protoOpts.stream;

  if (!this.grpcCredentials) {
    // We must establish an authClient to give to grpc.
    this.getGrpcCredentials_(function(err, credentials) {
      if (err) {
        stream.destroy(err);
        return;
      }

      self.grpcCredentials = credentials;
      self.requestStream(protoOpts, reqOpts);
    });

    return stream;
  }

  var objectMode = !!reqOpts.objectMode;
  delete reqOpts.objectMode;

  var service = this.getService_(protoOpts);
  var grpcOpts = {};

  if (is.number(protoOpts.timeout)) {
    grpcOpts.deadline = GrpcService.createDeadline_(protoOpts.timeout);
  }

  var retryOpts = {
    retries: this.maxRetries,
    objectMode: objectMode,
    shouldRetryFn: GrpcService.shouldRetryRequest_,

    request: function() {
      return service[protoOpts.method](reqOpts, grpcOpts)
        .on('status', function(status) {
          var grcpStatus = GrpcService.decorateStatus_(status);

          this.emit('response', grcpStatus || status);
        });
    }
  };

  return retryRequest(null, retryOpts)
    .on('error', function(err) {
      var grpcError = GrpcService.decorateError_(err);

      stream.destroy(grpcError || err);
    })
    .pipe(stream);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.datastore.prototype.transaction"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.prototype.</span>transaction ()](#apidoc.element.gcloud.datastore.prototype.transaction)
- description and source-code
```javascript
transaction = function () {
  return new Transaction(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gcloud.datastore.super_"></a>[module gcloud.datastore.super_](#apidoc.module.gcloud.datastore.super_)

#### <a name="apidoc.element.gcloud.datastore.super_.super_"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.</span>super_ ()](#apidoc.element.gcloud.datastore.super_.super_)
- description and source-code
```javascript
function DatastoreRequest() {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gcloud.datastore.super_.prototype"></a>[module gcloud.datastore.super_.prototype](#apidoc.module.gcloud.datastore.super_.prototype)

#### <a name="apidoc.element.gcloud.datastore.super_.prototype.allocateIds"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.super_.prototype.</span>allocateIds (incompleteKey, n, callback)](#apidoc.element.gcloud.datastore.super_.prototype.allocateIds)
- description and source-code
```javascript
allocateIds = function (incompleteKey, n, callback) {
  if (entity.isKeyComplete(incompleteKey)) {
    throw new Error('An incomplete key should be provided.');
  }

  var incompleteKeys = [];
  for (var i = 0; i < n; i++) {
    incompleteKeys.push(entity.keyToKeyProto(incompleteKey));
  }

  var protoOpts = {
    service: 'Datastore',
    method: 'allocateIds'
  };

  var reqOpts = {
    keys: incompleteKeys
  };

  this.request_(protoOpts, reqOpts, function(err, resp) {
    if (err) {
      callback(err, null, resp);
      return;
    }

    var keys = (resp.keys || []).map(entity.keyFromKeyProto);

    callback(null, keys, resp);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.datastore.super_.prototype.delete"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.super_.prototype.</span>delete (keys, callback)](#apidoc.element.gcloud.datastore.super_.prototype.delete)
- description and source-code
```javascript
delete = function (keys, callback) {
  callback = callback || util.noop;

  var protoOpts = {
    service: 'Datastore',
    method: 'commit'
  };

  var reqOpts = {
    mutations: arrify(keys).map(function(key) {
      return {
        delete: entity.keyToKeyProto(key)
      };
    })
  };

  if (this.id) {
    this.requests_.push(reqOpts);
    return;
  }

  this.request_(protoOpts, reqOpts, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.datastore.super_.prototype.get"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.super_.prototype.</span>get (keys, options, callback)](#apidoc.element.gcloud.datastore.super_.prototype.get)
- description and source-code
```javascript
get = function (keys, options, callback) {
  var self = this;

  if (is.fn(options)) {
    callback = options;
    options = {};
  }

  options = options || {};

  if (is.fn(callback)) {
    // Run this method in stream mode and send the results back to the callback.
    this.get(keys, options)
      .on('error', callback)
      .pipe(concat(function(results) {
        var isSingleLookup = !is.array(keys);
        callback(null, isSingleLookup ? results[0] : results);
      }));
    return;
  }

  keys = arrify(keys).map(entity.keyToKeyProto);

  if (keys.length === 0) {
    throw new Error('At least one Key object is required.');
  }

  var limiter = util.createLimiter(makeRequest, options);
  var stream = limiter.stream;

  stream.once('reading', function() {
    limiter.makeRequest(keys);
  });

  function makeRequest(keys) {
    var protoOpts = {
      service: 'Datastore',
      method: 'lookup'
    };

    var reqOpts = {
      keys: keys
    };

    if (options.consistency) {
      var code = CONSISTENCY_PROTO_CODE[options.consistency.toLowerCase()];

      reqOpts.readOptions = {
        readConsistency: code
      };
    }

    self.request_(protoOpts, reqOpts, function(err, resp) {
      if (err) {
        stream.destroy(err);
        return;
      }

      var entities = entity.formatArray(resp.found);
      var nextKeys = (resp.deferred || []).map(entity.keyFromKeyProto);

      split(entities, stream, function(streamEnded) {
        if (streamEnded) {
          return;
        }

        if (nextKeys.length > 0) {
          limiter.makeRequest(nextKeys);
          return;
        }

        stream.push(null);
      });
    });
  }

  return stream;
}
```
- example usage
```shell
...
var row = table.row('alincoln');

row.save('follows:gwashington', 1, function(err) {
  if (err) {
// Error handling omitted.
  }

  row.get('follows:gwashington', function(err, data) {
if (err) {
  // Error handling omitted.
}

// data = {
//   follows: {
//     gwashington: [
...
```

#### <a name="apidoc.element.gcloud.datastore.super_.prototype.insert"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.super_.prototype.</span>insert (entities, callback)](#apidoc.element.gcloud.datastore.super_.prototype.insert)
- description and source-code
```javascript
insert = function (entities, callback) {
  entities = arrify(entities).map(propAssign('method', 'insert'));
  this.save(entities, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.datastore.super_.prototype.request_"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.super_.prototype.</span>request_ (protoOpts, reqOpts, callback)](#apidoc.element.gcloud.datastore.super_.prototype.request_)
- description and source-code
```javascript
request_ = function (protoOpts, reqOpts, callback) {
  if (!callback) {
    callback = reqOpts;
    reqOpts = {};
  }

  callback = callback || util.noop;

  var isTransaction = is.defined(this.id);
  var method = protoOpts.method;

  reqOpts.projectId = this.projectId;

  // Set properties to indicate if we're in a transaction or not.
  if (method === 'commit') {
    if (isTransaction) {
      reqOpts.mode = 'TRANSACTIONAL';
      reqOpts.transaction = this.id;
    } else {
      reqOpts.mode = 'NON_TRANSACTIONAL';
    }
  }

  if (method === 'rollback') {
    reqOpts.transaction = this.id;
  }

  if (isTransaction && (method === 'lookup' || method === 'runQuery')) {
    if (reqOpts.readOptions && reqOpts.readOptions.readConsistency) {
      throw new Error('Read consistency cannot be specified in a transaction.');
    }

    reqOpts.readOptions = {
      transaction: this.id
    };
  }

  this.request(protoOpts, reqOpts, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.datastore.super_.prototype.runQuery"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.super_.prototype.</span>runQuery (query, options, callback)](#apidoc.element.gcloud.datastore.super_.prototype.runQuery)
- description and source-code
```javascript
runQuery = function (query, options, callback) {
  var self = this;

  if (is.fn(options)) {
    callback = options;
    options = {};
  }

  options = options || {};

  var info;

  if (is.fn(callback)) {
    // Run this method in stream mode and send the results back to the callback.
    this.runQuery(query, options)
      .on('error', callback)
      .on('info', function(info_) {
        info = info_;
      })
      .pipe(concat(function(results) {
        callback(null, results, info);
      }));
    return;
  }

  var limiter = util.createLimiter(makeRequest, options);
  var stream = limiter.stream;

  stream.once('reading', function() {
    limiter.makeRequest(query);
  });

  function makeRequest(query) {
    var protoOpts = {
      service: 'Datastore',
      method: 'runQuery'
    };

    var reqOpts = {
      query: entity.queryToQueryProto(query)
    };

    if (options.consistency) {
      var code = CONSISTENCY_PROTO_CODE[options.consistency.toLowerCase()];
      reqOpts.readOptions = {
        readConsistency: code
      };
    }

    if (query.namespace) {
      reqOpts.partitionId = {
        namespaceId: query.namespace
      };
    }

    self.request_(protoOpts, reqOpts, onResultSet);
  }

  function onResultSet(err, resp) {
    if (err) {
      stream.destroy(err);
      return;
    }

    var info = {
      moreResults: resp.batch.moreResults
    };

    if (resp.batch.endCursor) {
      info.endCursor = resp.batch.endCursor;
    }

    var entities = [];

    if (resp.batch.entityResults) {
      entities = entity.formatArray(resp.batch.entityResults);
    }

    // Emit each result right away, then get the rest if necessary.
    split(entities, stream, function(streamEnded) {
      if (streamEnded) {
        return;
      }

      if (resp.batch.moreResults !== 'NOT_FINISHED') {
        stream.emit('info', info);
        stream.push(null);
        return;
      }

      // The query is "NOT_FINISHED". Get the rest of the results.
      var offset = query.offsetVal === -1 ? 0 : query.offsetVal;

      var continuationQuery = extend(true, new Query(), query)
        .start(info.endCursor)
        .offset(offset - resp.batch.skippedResults);

      var limit = query.limitVal;
      if (limit && limit > -1) {
        continuationQuery.limit(limit - resp.batch.entityResults.length);
      }

      limiter.makeRequest(continuationQuery);
    });
  }

  return stream;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.datastore.super_.prototype.save"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.super_.prototype.</span>save (entities, callback)](#apidoc.element.gcloud.datastore.super_.prototype.save)
- description and source-code
```javascript
save = function (entities, callback) {
  entities = arrify(entities);

  var insertIndexes = {};
  var mutations = [];
  var methods = {
    insert: true,
    update: true,
    upsert: true
  };

  // Iterate over the entity objects, build a proto from all keys and values,
  // then place in the correct mutation array (insert, update, etc).
  entities.forEach(function(entityObject, index) {
    entityObject = extend(true, {}, entityObject);

    var mutation = {};
    var entityProto = {};
    var method = 'upsert';

    if (entityObject.method) {
      if (methods[entityObject.method]) {
        method = entityObject.method;
      } else {
        throw new Error('Method ' + entityObject.method + ' not recognized.');
      }
    }

    if (!entity.isKeyComplete(entityObject.key)) {
      insertIndexes[index] = true;
    }

    if (is.array(entityObject.data)) {
      entityProto.properties = entityObject.data.reduce(function(acc, data) {
        var value = entity.encodeValue(data.value);

        if (is.boolean(data.excludeFromIndexes)) {
          var excluded = data.excludeFromIndexes;
          var values = value.arrayValue && value.arrayValue.values;

          if (values) {
            values = values.map(propAssign('excludeFromIndexes', excluded));
          } else {
            value.excludeFromIndexes = data.excludeFromIndexes;
          }
        }

        acc[data.name] = value;

        return acc;
      }, {});
    } else {
      entityProto = entity.entityToEntityProto(entityObject.data);
    }

    entityProto.key = entity.keyToKeyProto(entityObject.key);

    mutation[method] = entityProto;
    mutations.push(mutation);
  });

  var protoOpts = {
    service: 'Datastore',
    method: 'commit'
  };

  var reqOpts = {
    mutations: mutations
  };

  function onCommit(err, resp) {
    if (err || !resp) {
      callback(err, resp);
      return;
    }

    arrify(resp.mutationResults).forEach(function(result, index) {
      if (!result.key) {
        return;
      }

      if (insertIndexes[index]) {
        var id = entity.keyFromKeyProto(result.key).id;
        entities[index].key.id = id;
      }
    });

    callback(null, resp);
  }

  if (this.id) {
    this.requests_.push(reqOpts);
    this.requestCallbacks_.push(onCommit);
    return;
  }

  this.request_(protoOpts, reqOpts, onCommit);
}
```
- example usage
```shell
...
var table = bigtable.table('prezzy');

table.getRows(function(err, rows) {});

// Update a row in your table.
var row = table.row('alincoln');

row.save('follows:gwashington', 1, function(err) {
if (err) {
  // Error handling omitted.
}

row.get('follows:gwashington', function(err, data) {
  if (err) {
    // Error handling omitted.
...
```

#### <a name="apidoc.element.gcloud.datastore.super_.prototype.update"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.super_.prototype.</span>update (entities, callback)](#apidoc.element.gcloud.datastore.super_.prototype.update)
- description and source-code
```javascript
update = function (entities, callback) {
  entities = arrify(entities).map(propAssign('method', 'update'));
  this.save(entities, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.datastore.super_.prototype.upsert"></a>[function <span class="apidocSignatureSpan">gcloud.datastore.super_.prototype.</span>upsert (entities, callback)](#apidoc.element.gcloud.datastore.super_.prototype.upsert)
- description and source-code
```javascript
upsert = function (entities, callback) {
  entities = arrify(entities).map(propAssign('method', 'upsert'));
  this.save(entities, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gcloud.dns"></a>[module gcloud.dns](#apidoc.module.gcloud.dns)

#### <a name="apidoc.element.gcloud.dns.dns"></a>[function <span class="apidocSignatureSpan">gcloud.</span>dns (options)](#apidoc.element.gcloud.dns.dns)
- description and source-code
```javascript
function DNS(options) {
  if (!(this instanceof DNS)) {
    options = util.normalizeArguments(this, options);
    return new DNS(options);
  }

  var config = {
    baseUrl: 'https://www.googleapis.com/dns/v1',
    scopes: [
      'https://www.googleapis.com/auth/ndev.clouddns.readwrite',
      'https://www.googleapis.com/auth/cloud-platform'
    ]
  };

  Service.call(this, config, options);
}
```
- example usage
```shell
...

'''js
var gcloud = require('gcloud');

// Authenticating on a per-API-basis. You don't need to do this if you auth on a
// global basis (see Authentication section above).

var dns = gcloud.dns({
projectId: 'my-project',
keyFilename: '/path/to/keyfile.json'
});

// Create a managed zone.
dns.createZone('my-new-zone', {
dnsName: 'my-domain.com.'
...
```

#### <a name="apidoc.element.gcloud.dns.super_"></a>[function <span class="apidocSignatureSpan">gcloud.dns.</span>super_ (config, options)](#apidoc.element.gcloud.dns.super_)
- description and source-code
```javascript
function Service(config, options) {
  var reqCfg = extend({}, config, {
    credentials: options.credentials,
    keyFile: options.keyFilename,
    email: options.email
  });

  this.makeAuthenticatedRequest = util.makeAuthenticatedRequestFactory(reqCfg);

  this.authClient = this.makeAuthenticatedRequest.authClient;
  this.baseUrl = config.baseUrl;
  this.getCredentials = this.makeAuthenticatedRequest.getCredentials;
  this.globalInterceptors = arrify(options.interceptors_);
  this.interceptors = [];
  this.projectId = options.projectId;
  this.projectIdRequired = config.projectIdRequired !== false;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gcloud.dns.prototype"></a>[module gcloud.dns.prototype](#apidoc.module.gcloud.dns.prototype)

#### <a name="apidoc.element.gcloud.dns.prototype.createZone"></a>[function <span class="apidocSignatureSpan">gcloud.dns.prototype.</span>createZone (name, config, callback)](#apidoc.element.gcloud.dns.prototype.createZone)
- description and source-code
```javascript
createZone = function (name, config, callback) {
  var self = this;

  if (!name) {
    throw new Error('A zone name is required.');
  }

  if (!config || !config.dnsName) {
    throw new Error('A zone dnsName is required.');
  }

  config.name = name;

  // Required by the API.
  config.description = config.description || '';

  this.request({
    method: 'POST',
    uri: '/managedZones',
    json: config
  }, function(err, resp) {
    if (err) {
      callback(err, null, resp);
      return;
    }

    var zone = self.zone(resp.name);
    zone.metadata = resp;

    callback(null, zone, resp);
  });
}
```
- example usage
```shell
...

var dns = gcloud.dns({
  projectId: 'my-project',
  keyFilename: '/path/to/keyfile.json'
});

// Create a managed zone.
dns.createZone('my-new-zone', {
  dnsName: 'my-domain.com.'
}, function(err, zone) {});

// Reference an existing zone.
var zone = dns.zone('my-existing-zone');

// Create an NS record.
...
```

#### <a name="apidoc.element.gcloud.dns.prototype.getZones"></a>[function <span class="apidocSignatureSpan">gcloud.dns.prototype.</span>getZones ()](#apidoc.element.gcloud.dns.prototype.getZones)
- description and source-code
```javascript
getZones = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.dns.prototype.zone"></a>[function <span class="apidocSignatureSpan">gcloud.dns.prototype.</span>zone (name)](#apidoc.element.gcloud.dns.prototype.zone)
- description and source-code
```javascript
zone = function (name) {
  if (!name) {
    throw new Error('A zone name is required.');
  }

  return new Zone(this, name);
}
```
- example usage
```shell
...

// Create a managed zone.
dns.createZone('my-new-zone', {
  dnsName: 'my-domain.com.'
}, function(err, zone) {});

// Reference an existing zone.
var zone = dns.zone('my-existing-zone');

// Create an NS record.
var nsRecord = zone.record('ns', {
  ttl: 86400,
  name: 'my-domain.com.',
  data: 'ns-cloud1.googledomains.com.'
});
...
```



# <a name="apidoc.module.gcloud.logging"></a>[module gcloud.logging](#apidoc.module.gcloud.logging)

#### <a name="apidoc.element.gcloud.logging.logging"></a>[function <span class="apidocSignatureSpan">gcloud.</span>logging (options)](#apidoc.element.gcloud.logging.logging)
- description and source-code
```javascript
function Logging(options) {
  if (!(this instanceof Logging)) {
    options = util.normalizeArguments(this, options);
    return new Logging(options);
  }

  var config = {
    baseUrl: 'logging.googleapis.com',
    service: 'logging',
    apiVersion: 'v2',
    protoServices: {
      ConfigServiceV2:
        googleProtoFiles('logging', 'v2', 'logging_config.proto'),
      LoggingServiceV2: googleProtoFiles.logging.v2
    },
    scopes: [
      'https://www.googleapis.com/auth/cloud-platform'
    ]
  };

  GrpcService.call(this, config, options);
}
```
- example usage
```shell
...
// basis (see Authentication section above).

var gcloud = require('gcloud')({
  projectId: 'my-project',
  keyFilename: '/path/to/keyfile.json'
});

var logging = gcloud.logging();

// Create a sink using a Bucket as a destination.
var gcs = gcloud.storage();

logging.createSink('my-new-sink', {
  destination: gcs.bucket('my-sink')
}, function(err, sink) {});
...
```

#### <a name="apidoc.element.gcloud.logging.super_"></a>[function <span class="apidocSignatureSpan">gcloud.logging.</span>super_ (config, options)](#apidoc.element.gcloud.logging.super_)
- description and source-code
```javascript
function GrpcService(config, options) {
  if (global.GCLOUD_SANDBOX_ENV) {
    // gRPC has a tendency to cause our doc unit tests to fail, so we prevent
    // any calls to that library from going through.
    // Reference: https://github.com/GoogleCloudPlatform/gcloud-node/pull/1137#issuecomment-193315047
    return global.GCLOUD_SANDBOX_ENV;
  }

  Service.call(this, config, options);

  if (config.customEndpoint) {
    this.grpcCredentials = grpc.credentials.createInsecure();
  }

  this.maxRetries = options.maxRetries;

  var apiVersion = config.apiVersion;
  var service = this.service = config.service;

  this.activeServiceMap_ = new Map();
  this.protos = {};

  var protoServices = config.protoServices;

  if (!protoServices) {
    protoServices = {};
    protoServices[service] = googleProtoFiles[service][apiVersion];
  }

  for (var protoServiceName in protoServices) {
    var protoService = this.loadProtoFile_(
      protoServices[protoServiceName], config);

    this.protos[protoServiceName] = protoService;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gcloud.logging.prototype"></a>[module gcloud.logging.prototype](#apidoc.module.gcloud.logging.prototype)

#### <a name="apidoc.element.gcloud.logging.prototype.createSink"></a>[function <span class="apidocSignatureSpan">gcloud.logging.prototype.</span>createSink (name, config, callback)](#apidoc.element.gcloud.logging.prototype.createSink)
- description and source-code
```javascript
createSink = function (name, config, callback) {
  // jscs:enable maximumLineLength
  var self = this;

  if (!is.string(name)) {
    throw new Error('A sink name must be provided.');
  }

  if (!is.object(config)) {
    throw new Error('A sink configuration object must be provided.');
  }

  if (config.destination instanceof Bucket) {
    this.setAclForBucket_(name, config, callback);
    return;
  }

  if (config.destination instanceof Dataset) {
    this.setAclForDataset_(name, config, callback);
    return;
  }

  if (config.destination instanceof Topic) {
    this.setAclForTopic_(name, config, callback);
    return;
  }

  var protoOpts = {
    service: 'ConfigServiceV2',
    method: 'createSink'
  };

  var reqOpts = {
    parent: 'projects/' + this.projectId,
    sink: extend({}, config, { name: name })
  };

  this.request(protoOpts, reqOpts, function(err, resp) {
    if (err) {
      callback(err, null, resp);
      return;
    }

    var sink = self.sink(resp.name);
    sink.metadata = resp;

    callback(null, sink, resp);
  });
}
```
- example usage
```shell
...
});

var logging = gcloud.logging();

// Create a sink using a Bucket as a destination.
var gcs = gcloud.storage();

logging.createSink('my-new-sink', {
  destination: gcs.bucket('my-sink')
}, function(err, sink) {});

// Write a critical entry to a log.
var syslog = logging.log('syslog');

var resource = {
...
```

#### <a name="apidoc.element.gcloud.logging.prototype.entry"></a>[function <span class="apidocSignatureSpan">gcloud.logging.prototype.</span>entry (resource, data)](#apidoc.element.gcloud.logging.prototype.entry)
- description and source-code
```javascript
entry = function (resource, data) {
  return new Entry(resource, data);
}
```
- example usage
```shell
...
  type: 'gce_instance',
  labels: {
    zone: 'global',
    instance_id: '3'
  }
};

var entry = syslog.entry(resource, {
  delegate: process.env.user
});

syslog.critical(entry, function(err) {});

// Get all entries in your project.
logging.getEntries(function(err, entries) {
...
```

#### <a name="apidoc.element.gcloud.logging.prototype.getEntries"></a>[function <span class="apidocSignatureSpan">gcloud.logging.prototype.</span>getEntries ()](#apidoc.element.gcloud.logging.prototype.getEntries)
- description and source-code
```javascript
getEntries = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
...
var entry = syslog.entry(resource, {
  delegate: process.env.user
});

syslog.critical(entry, function(err) {});

// Get all entries in your project.
logging.getEntries(function(err, entries) {
  if (!err) {
    // 'entries' contains all of the entries from the logs in your project.
  }
});
'''
...
```

#### <a name="apidoc.element.gcloud.logging.prototype.getSinks"></a>[function <span class="apidocSignatureSpan">gcloud.logging.prototype.</span>getSinks ()](#apidoc.element.gcloud.logging.prototype.getSinks)
- description and source-code
```javascript
getSinks = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.logging.prototype.log"></a>[function <span class="apidocSignatureSpan">gcloud.logging.prototype.</span>log (name)](#apidoc.element.gcloud.logging.prototype.log)
- description and source-code
```javascript
log = function (name) {
  return new Log(this, name);
}
```
- example usage
```shell
...
projectId: 'my-project',
keyFilename: '/path/to/keyfile.json'
});

var key = datastore.key(['Product', 'Computer']);

datastore.get(key, function(err, entity) {
console.log(err || entity);
});

// Save data to Datastore.
var blogPostData = {
title: 'How to make the perfect homemade pasta',
author: 'Andrew Chilton',
isDraft: true
...
```

#### <a name="apidoc.element.gcloud.logging.prototype.setAclForBucket_"></a>[function <span class="apidocSignatureSpan">gcloud.logging.prototype.</span>setAclForBucket_ (name, config, callback)](#apidoc.element.gcloud.logging.prototype.setAclForBucket_)
- description and source-code
```javascript
setAclForBucket_ = function (name, config, callback) {
  var self = this;
  var bucket = config.destination;

  bucket.acl.owners.addGroup('cloud-logs@google.com', function(err, apiResp) {
    if (err) {
      callback(err, null, apiResp);
      return;
    }

    config.destination = 'storage.googleapis.com/' + bucket.name;

    self.createSink(name, config, callback);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.logging.prototype.setAclForDataset_"></a>[function <span class="apidocSignatureSpan">gcloud.logging.prototype.</span>setAclForDataset_ (name, config, callback)](#apidoc.element.gcloud.logging.prototype.setAclForDataset_)
- description and source-code
```javascript
setAclForDataset_ = function (name, config, callback) {
  var self = this;
  var dataset = config.destination;

  dataset.getMetadata(function(err, metadata, apiResp) {
    if (err) {
      callback(err, null, apiResp);
      return;
    }

    var access = [].slice.call(arrify(metadata.access));

    access.push({
      role: 'WRITER',
      groupByEmail: 'cloud-logs@google.com'
    });

    dataset.setMetadata({
      access: access
    }, function(err, apiResp) {
      if (err) {
        callback(err, null, apiResp);
        return;
      }

      config.destination = format('{baseUrl}/projects/{pId}/datasets/{dId}', {
        baseUrl: 'bigquery.googleapis.com',
        pId: dataset.parent.projectId,
        dId: dataset.id
      });

      self.createSink(name, config, callback);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.logging.prototype.setAclForTopic_"></a>[function <span class="apidocSignatureSpan">gcloud.logging.prototype.</span>setAclForTopic_ (name, config, callback)](#apidoc.element.gcloud.logging.prototype.setAclForTopic_)
- description and source-code
```javascript
setAclForTopic_ = function (name, config, callback) {
  var self = this;
  var topic = config.destination;

  topic.iam.getPolicy(function(err, policy, apiResp) {
    if (err) {
      callback(err, null, apiResp);
      return;
    }

    policy.bindings = arrify(policy.bindings);

    policy.bindings.push({
      role: 'roles/pubsub.publisher',
      members: [
        'serviceAccount:cloud-logs@system.gserviceaccount.com'
      ]
    });

    topic.iam.setPolicy(policy, function(err, policy, apiResp) {
      if (err) {
        callback(err, null, apiResp);
        return;
      }

      config.destination = format('{baseUrl}/{topicName}', {
        baseUrl: 'pubsub.googleapis.com',
        topicName: topic.name
      });

      self.createSink(name, config, callback);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.logging.prototype.sink"></a>[function <span class="apidocSignatureSpan">gcloud.logging.prototype.</span>sink (name)](#apidoc.element.gcloud.logging.prototype.sink)
- description and source-code
```javascript
sink = function (name) {
  return new Sink(this, name);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gcloud.prediction"></a>[module gcloud.prediction](#apidoc.module.gcloud.prediction)

#### <a name="apidoc.element.gcloud.prediction.prediction"></a>[function <span class="apidocSignatureSpan">gcloud.</span>prediction (options)](#apidoc.element.gcloud.prediction.prediction)
- description and source-code
```javascript
function Prediction(options) {
  if (!(this instanceof Prediction)) {
    options = util.normalizeArguments(this, options);
    return new Prediction(options);
  }

  var config = {
    baseUrl: 'https://www.googleapis.com/prediction/v1.6',
    scopes: [
      'https://www.googleapis.com/auth/prediction',
      'https://www.googleapis.com/auth/devstorage.read_only'
    ]
  };

  Service.call(this, config, options);
}
```
- example usage
```shell
...

'''js
var gcloud = require('gcloud');

// Authenticating on a per-API-basis. You don't need to do this if you auth on a
// global basis (see Authentication section above).

var prediction = gcloud.prediction({
projectId: 'my-project',
keyFilename: '/path/to/keyfile.json'
});

// Get all of the trained models in your project.
prediction.getModels(function(err, models) {
if (!err) {
...
```

#### <a name="apidoc.element.gcloud.prediction.super_"></a>[function <span class="apidocSignatureSpan">gcloud.prediction.</span>super_ (config, options)](#apidoc.element.gcloud.prediction.super_)
- description and source-code
```javascript
function Service(config, options) {
  var reqCfg = extend({}, config, {
    credentials: options.credentials,
    keyFile: options.keyFilename,
    email: options.email
  });

  this.makeAuthenticatedRequest = util.makeAuthenticatedRequestFactory(reqCfg);

  this.authClient = this.makeAuthenticatedRequest.authClient;
  this.baseUrl = config.baseUrl;
  this.getCredentials = this.makeAuthenticatedRequest.getCredentials;
  this.globalInterceptors = arrify(options.interceptors_);
  this.interceptors = [];
  this.projectId = options.projectId;
  this.projectIdRequired = config.projectIdRequired !== false;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gcloud.prediction.prototype"></a>[module gcloud.prediction.prototype](#apidoc.module.gcloud.prediction.prototype)

#### <a name="apidoc.element.gcloud.prediction.prototype.createModel"></a>[function <span class="apidocSignatureSpan">gcloud.prediction.prototype.</span>createModel (id, options, callback)](#apidoc.element.gcloud.prediction.prototype.createModel)
- description and source-code
```javascript
createModel = function (id, options, callback) {
  var self = this;

  if (!id) {
    throw new Error('A model ID is required.');
  }

  if (is.fn(options)) {
    callback = options;
    options = {};
  }

  var body = extend({}, options, {
    id: id
  });

  if (body.data) {
    var file = body.data;

    body.storageDataLocation = format('{bucket}/{fileName}', {
      bucket: file.parent.name,
      fileName: file.name
    });

    delete body.data;
  }

  if (body.type) {
    body.modelType = body.type.toUpperCase();
    delete body.type;
  }

  this.request({
    method: 'POST',
    uri: '/trainedmodels',
    json: body
  }, function(err, resp) {
    if (err) {
      callback(err, null, resp);
      return;
    }

    var model = self.model(resp.id);
    model.metadata = resp;

    callback(null, model, resp);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.prediction.prototype.getModels"></a>[function <span class="apidocSignatureSpan">gcloud.prediction.prototype.</span>getModels ()](#apidoc.element.gcloud.prediction.prototype.getModels)
- description and source-code
```javascript
getModels = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
...

var prediction = gcloud.prediction({
  projectId: 'my-project',
  keyFilename: '/path/to/keyfile.json'
});

// Get all of the trained models in your project.
prediction.getModels(function(err, models) {
  if (!err) {
    // 'models' is an array of Model objects.
  }
});

// Reference an existing trained model.
var model = prediction.model('my-existing-model');
...
```

#### <a name="apidoc.element.gcloud.prediction.prototype.model"></a>[function <span class="apidocSignatureSpan">gcloud.prediction.prototype.</span>model (id)](#apidoc.element.gcloud.prediction.prototype.model)
- description and source-code
```javascript
model = function (id) {
  if (!id) {
    throw new Error('A model ID is required.');
  }

  return new Model(this, id);
}
```
- example usage
```shell
...
prediction.getModels(function(err, models) {
if (!err) {
  // 'models' is an array of Model objects.
}
});

// Reference an existing trained model.
var model = prediction.model('my-existing-model');

// Train a model.
model.train('english', 'Hello from your friends at Google!', function(err) {});

// Query a model.
model.query('Hello', function(err, results) {
if (!err) {
...
```



# <a name="apidoc.module.gcloud.pubsub"></a>[module gcloud.pubsub](#apidoc.module.gcloud.pubsub)

#### <a name="apidoc.element.gcloud.pubsub.pubsub"></a>[function <span class="apidocSignatureSpan">gcloud.</span>pubsub (options)](#apidoc.element.gcloud.pubsub.pubsub)
- description and source-code
```javascript
function PubSub(options) {
  if (!(this instanceof PubSub)) {
    options = util.normalizeArguments(this, options);
    return new PubSub(options);
  }

  this.defaultBaseUrl_ = 'pubsub.googleapis.com';
  this.determineBaseUrl_();

  var config = {
    baseUrl: this.baseUrl_,
    customEndpoint: this.customEndpoint_,
    service: 'pubsub',
    apiVersion: 'v1',
    scopes: [
      'https://www.googleapis.com/auth/pubsub',
      'https://www.googleapis.com/auth/cloud-platform'
    ]
  };

  this.options = options;

  GrpcService.call(this, config, options);
}
```
- example usage
```shell
...

'''js
var gcloud = require('gcloud');

// Authenticating on a per-API-basis. You don't need to do this if you
// auth on a global basis (see Authentication section above).

var pubsub = gcloud.pubsub({
  projectId: 'my-project',
  keyFilename: '/path/to/keyfile.json'
});

// Reference a topic that has been previously created.
var topic = pubsub.topic('my-topic');
...
```

#### <a name="apidoc.element.gcloud.pubsub.super_"></a>[function <span class="apidocSignatureSpan">gcloud.pubsub.</span>super_ (config, options)](#apidoc.element.gcloud.pubsub.super_)
- description and source-code
```javascript
function GrpcService(config, options) {
  if (global.GCLOUD_SANDBOX_ENV) {
    // gRPC has a tendency to cause our doc unit tests to fail, so we prevent
    // any calls to that library from going through.
    // Reference: https://github.com/GoogleCloudPlatform/gcloud-node/pull/1137#issuecomment-193315047
    return global.GCLOUD_SANDBOX_ENV;
  }

  Service.call(this, config, options);

  if (config.customEndpoint) {
    this.grpcCredentials = grpc.credentials.createInsecure();
  }

  this.maxRetries = options.maxRetries;

  var apiVersion = config.apiVersion;
  var service = this.service = config.service;

  this.activeServiceMap_ = new Map();
  this.protos = {};

  var protoServices = config.protoServices;

  if (!protoServices) {
    protoServices = {};
    protoServices[service] = googleProtoFiles[service][apiVersion];
  }

  for (var protoServiceName in protoServices) {
    var protoService = this.loadProtoFile_(
      protoServices[protoServiceName], config);

    this.protos[protoServiceName] = protoService;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gcloud.pubsub.prototype"></a>[module gcloud.pubsub.prototype](#apidoc.module.gcloud.pubsub.prototype)

#### <a name="apidoc.element.gcloud.pubsub.prototype.createTopic"></a>[function <span class="apidocSignatureSpan">gcloud.pubsub.prototype.</span>createTopic (name, callback)](#apidoc.element.gcloud.pubsub.prototype.createTopic)
- description and source-code
```javascript
createTopic = function (name, callback) {
  var self = this;

  callback = callback || util.noop;

  var protoOpts = {
    service: 'Publisher',
    method: 'createTopic'
  };

  var reqOpts = {
    name: Topic.formatName_(this.projectId, name)
  };

  this.request(protoOpts, reqOpts, function(err, resp) {
    if (err) {
      callback(err, null, resp);
      return;
    }

    var topic = self.topic(name);
    topic.metadata = resp;

    callback(null, topic, resp);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.pubsub.prototype.determineBaseUrl_"></a>[function <span class="apidocSignatureSpan">gcloud.pubsub.prototype.</span>determineBaseUrl_ ()](#apidoc.element.gcloud.pubsub.prototype.determineBaseUrl_)
- description and source-code
```javascript
determineBaseUrl_ = function () {
  var baseUrl = this.defaultBaseUrl_;
  var leadingProtocol = new RegExp('^https*://');
  var trailingSlashes = new RegExp('/*$');

  if (process.env.PUBSUB_EMULATOR_HOST) {
    this.customEndpoint_ = true;
    baseUrl = process.env.PUBSUB_EMULATOR_HOST;
  }

  this.baseUrl_ = baseUrl
    .replace(leadingProtocol, '')
    .replace(trailingSlashes, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.pubsub.prototype.getSubscriptions"></a>[function <span class="apidocSignatureSpan">gcloud.pubsub.prototype.</span>getSubscriptions ()](#apidoc.element.gcloud.pubsub.prototype.getSubscriptions)
- description and source-code
```javascript
getSubscriptions = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.pubsub.prototype.getTopics"></a>[function <span class="apidocSignatureSpan">gcloud.pubsub.prototype.</span>getTopics ()](#apidoc.element.gcloud.pubsub.prototype.getTopics)
- description and source-code
```javascript
getTopics = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.pubsub.prototype.subscribe"></a>[function <span class="apidocSignatureSpan">gcloud.pubsub.prototype.</span>subscribe (topic, subName, options, callback)](#apidoc.element.gcloud.pubsub.prototype.subscribe)
- description and source-code
```javascript
subscribe = function (topic, subName, options, callback) {
  if (!is.string(topic) && !(topic instanceof Topic)) {
    throw new Error('A Topic is required for a new subscription.');
  }

  if (!is.string(subName)) {
    throw new Error('A subscription name is required for a new subscription.');
  }

  if (!callback) {
    callback = options;
    options = {};
  }

  options = options || {};

  if (is.string(topic)) {
    topic = this.topic(topic);
  }

  var subscription = this.subscription(subName, options);

  var protoOpts = {
    service: 'Subscriber',
    method: 'createSubscription',
    timeout: options.timeout
  };

  var reqOpts = extend(true, {}, options, {
    topic: topic.name,
    name: subscription.name
  });

  delete reqOpts.autoAck;
  delete reqOpts.encoding;
  delete reqOpts.interval;
  delete reqOpts.maxInProgress;
  delete reqOpts.reuseExisting;
  delete reqOpts.timeout;

  this.request(protoOpts, reqOpts, function(err, resp) {
    if (err && !(err.code === 409 && options.reuseExisting)) {
      callback(err, null, resp);
      return;
    }

    callback(null, subscription, resp);
  });
}
```
- example usage
```shell
...
}, function(err) {});

// Subscribe to the topic.
var options = {
reuseExisting: true
};

topic.subscribe('subscription-name', options, function(err, subscription) {
// Register listeners to start pulling for messages.
function onError(err) {}
function onMessage(message) {}
subscription.on('error', onError);
subscription.on('message', onMessage);

// Remove listeners to stop pulling for messages.
...
```

#### <a name="apidoc.element.gcloud.pubsub.prototype.subscription"></a>[function <span class="apidocSignatureSpan">gcloud.pubsub.prototype.</span>subscription (name, options)](#apidoc.element.gcloud.pubsub.prototype.subscription)
- description and source-code
```javascript
subscription = function (name, options) {
  if (!name) {
    throw new Error('The name of a subscription is required.');
  }

  options = options || {};
  options.name = name;
  return new Subscription(this, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.pubsub.prototype.topic"></a>[function <span class="apidocSignatureSpan">gcloud.pubsub.prototype.</span>topic (name)](#apidoc.element.gcloud.pubsub.prototype.topic)
- description and source-code
```javascript
topic = function (name) {
  if (!name) {
    throw new Error('A name must be specified for a new topic.');
  }

  return new Topic(this, name);
}
```
- example usage
```shell
...

var pubsub = gcloud.pubsub({
  projectId: 'my-project',
  keyFilename: '/path/to/keyfile.json'
});

// Reference a topic that has been previously created.
var topic = pubsub.topic('my-topic');

// Publish a message to the topic.
topic.publish({
  data: 'New message!'
}, function(err) {});

// Subscribe to the topic.
...
```



# <a name="apidoc.module.gcloud.resource"></a>[module gcloud.resource](#apidoc.module.gcloud.resource)

#### <a name="apidoc.element.gcloud.resource.resource"></a>[function <span class="apidocSignatureSpan">gcloud.</span>resource (options)](#apidoc.element.gcloud.resource.resource)
- description and source-code
```javascript
function Resource(options) {
  if (!(this instanceof Resource)) {
    options = util.normalizeArguments(this, options, {
      projectIdRequired: false
    });
    return new Resource(options);
  }

  var config = {
    baseUrl: 'https://cloudresourcemanager.googleapis.com/v1beta1',
    scopes: ['https://www.googleapis.com/auth/cloud-platform'],
    projectIdRequired: false
  };

  Service.call(this, config, options);

  this.defaultProjectId_ = options.projectId;
}
```
- example usage
```shell
...

'''js
var gcloud = require('gcloud');

// Authorizing on a per-API-basis. You don't need to do this if you auth on a
// global basis (see Authorization section above).

var resource = gcloud.resource({
projectId: 'my-project',
keyFilename: '/path/to/keyfile.json'
});

// Get all of the projects you maintain.
resource.getProjects(function(err, projects) {
if (!err) {
...
```

#### <a name="apidoc.element.gcloud.resource.super_"></a>[function <span class="apidocSignatureSpan">gcloud.resource.</span>super_ (config, options)](#apidoc.element.gcloud.resource.super_)
- description and source-code
```javascript
function Service(config, options) {
  var reqCfg = extend({}, config, {
    credentials: options.credentials,
    keyFile: options.keyFilename,
    email: options.email
  });

  this.makeAuthenticatedRequest = util.makeAuthenticatedRequestFactory(reqCfg);

  this.authClient = this.makeAuthenticatedRequest.authClient;
  this.baseUrl = config.baseUrl;
  this.getCredentials = this.makeAuthenticatedRequest.getCredentials;
  this.globalInterceptors = arrify(options.interceptors_);
  this.interceptors = [];
  this.projectId = options.projectId;
  this.projectIdRequired = config.projectIdRequired !== false;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gcloud.resource.prototype"></a>[module gcloud.resource.prototype](#apidoc.module.gcloud.resource.prototype)

#### <a name="apidoc.element.gcloud.resource.prototype.createProject"></a>[function <span class="apidocSignatureSpan">gcloud.resource.prototype.</span>createProject (id, options, callback)](#apidoc.element.gcloud.resource.prototype.createProject)
- description and source-code
```javascript
createProject = function (id, options, callback) {
  var self = this;

  if (is.fn(options)) {
    callback = options;
    options = {};
  }

  this.request({
    method: 'POST',
    uri: '/projects',
    json: extend({}, options, {
      projectId: id
    })
  }, function(err, resp) {
    if (err) {
      callback(err, null, resp);
      return;
    }

    var project = self.project(resp.projectId);
    project.metadata = resp;

    callback(null, project, resp);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.resource.prototype.getProjects"></a>[function <span class="apidocSignatureSpan">gcloud.resource.prototype.</span>getProjects ()](#apidoc.element.gcloud.resource.prototype.getProjects)
- description and source-code
```javascript
getProjects = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
...

var resource = gcloud.resource({
  projectId: 'my-project',
  keyFilename: '/path/to/keyfile.json'
});

// Get all of the projects you maintain.
resource.getProjects(function(err, projects) {
  if (!err) {
    // 'projects' contains all of your projects.
  }
});

// Get the metadata from your project. (defaults to 'my-project')
var project = resource.project();
...
```

#### <a name="apidoc.element.gcloud.resource.prototype.project"></a>[function <span class="apidocSignatureSpan">gcloud.resource.prototype.</span>project (id)](#apidoc.element.gcloud.resource.prototype.project)
- description and source-code
```javascript
project = function (id) {
  id = id || this.defaultProjectId_;

  if (!id) {
    throw new Error('A project ID is required.');
  }

  return new Project(this, id);
}
```
- example usage
```shell
...
resource.getProjects(function(err, projects) {
  if (!err) {
    // 'projects' contains all of your projects.
  }
});

// Get the metadata from your project. (defaults to 'my-project')
var project = resource.project();

project.getMetadata(function(err, metadata) {
  // 'metadata' describes your project.
});
'''
...
```



# <a name="apidoc.module.gcloud.storage"></a>[module gcloud.storage](#apidoc.module.gcloud.storage)

#### <a name="apidoc.element.gcloud.storage.storage"></a>[function <span class="apidocSignatureSpan">gcloud.</span>storage (options)](#apidoc.element.gcloud.storage.storage)
- description and source-code
```javascript
function Storage(options) {
  if (!(this instanceof Storage)) {
    options = util.normalizeArguments(this, options);
    return new Storage(options);
  }

  var config = {
    baseUrl: 'https://www.googleapis.com/storage/v1',
    projectIdRequired: false,
    scopes: [
      'https://www.googleapis.com/auth/devstorage.full_control'
    ]
  };

  Service.call(this, config, options);
}
```
- example usage
```shell
...
'''js
var fs = require('fs');
var gcloud = require('gcloud');

// Authenticating on a per-API-basis. You don't need to do this if you auth on a
// global basis (see Authentication section above).

var gcs = gcloud.storage({
projectId: 'my-project',
keyFilename: '/path/to/keyfile.json'
});

// Create a new bucket.
gcs.createBucket('my-new-bucket', function(err, bucket) {
if (!err) {
...
```

#### <a name="apidoc.element.gcloud.storage.super_"></a>[function <span class="apidocSignatureSpan">gcloud.storage.</span>super_ (config, options)](#apidoc.element.gcloud.storage.super_)
- description and source-code
```javascript
function Service(config, options) {
  var reqCfg = extend({}, config, {
    credentials: options.credentials,
    keyFile: options.keyFilename,
    email: options.email
  });

  this.makeAuthenticatedRequest = util.makeAuthenticatedRequestFactory(reqCfg);

  this.authClient = this.makeAuthenticatedRequest.authClient;
  this.baseUrl = config.baseUrl;
  this.getCredentials = this.makeAuthenticatedRequest.getCredentials;
  this.globalInterceptors = arrify(options.interceptors_);
  this.interceptors = [];
  this.projectId = options.projectId;
  this.projectIdRequired = config.projectIdRequired !== false;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gcloud.storage.prototype"></a>[module gcloud.storage.prototype](#apidoc.module.gcloud.storage.prototype)

#### <a name="apidoc.element.gcloud.storage.prototype.bucket"></a>[function <span class="apidocSignatureSpan">gcloud.storage.prototype.</span>bucket (name)](#apidoc.element.gcloud.storage.prototype.bucket)
- description and source-code
```javascript
bucket = function (name) {
  if (!name) {
    throw new Error('A bucket name is needed to use Google Cloud Storage.');
  }

  return new Bucket(this, name);
}
```
- example usage
```shell
...
gcs.createBucket('my-new-bucket', function(err, bucket) {
  if (!err) {
    // "my-new-bucket" was successfully created.
  }
});

// Reference an existing bucket.
var bucket = gcs.bucket('my-existing-bucket');

// Upload a local file to a new file to be created in your bucket.
bucket.upload('/photos/zoo/zebra.jpg', function(err, file) {
  if (!err) {
    // "zebra.jpg" is now in your bucket.
  }
});
...
```

#### <a name="apidoc.element.gcloud.storage.prototype.channel"></a>[function <span class="apidocSignatureSpan">gcloud.storage.prototype.</span>channel (id, resourceId)](#apidoc.element.gcloud.storage.prototype.channel)
- description and source-code
```javascript
channel = function (id, resourceId) {
  return new Channel(this, id, resourceId);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.storage.prototype.createBucket"></a>[function <span class="apidocSignatureSpan">gcloud.storage.prototype.</span>createBucket (name, metadata, callback)](#apidoc.element.gcloud.storage.prototype.createBucket)
- description and source-code
```javascript
createBucket = function (name, metadata, callback) {
  var self = this;

  if (!name) {
    throw new Error('A name is required to create a bucket.');
  }

  if (!callback) {
    callback = metadata;
    metadata = {};
  }

  var body = extend(metadata, {
    name: name
  });

  var storageClasses = {
    dra: 'DURABLE_REDUCED_AVAILABILITY',
    nearline: 'NEARLINE'
  };

  Object.keys(storageClasses).forEach(function(storageClass) {
    if (body[storageClass]) {
      body.storageClass = storageClasses[storageClass];
      delete body[storageClass];
    }
  });

  this.request({
    method: 'POST',
    uri: '/b',
    qs: {
      project: this.projectId
    },
    json: body
  }, function(err, resp) {
    if (err) {
      callback(err, null, resp);
      return;
    }

    var bucket = self.bucket(name);
    bucket.metadata = resp;

    callback(null, bucket, resp);
  });
}
```
- example usage
```shell
...

var gcs = gcloud.storage({
  projectId: 'my-project',
  keyFilename: '/path/to/keyfile.json'
});

// Create a new bucket.
gcs.createBucket('my-new-bucket', function(err, bucket) {
  if (!err) {
    // "my-new-bucket" was successfully created.
  }
});

// Reference an existing bucket.
var bucket = gcs.bucket('my-existing-bucket');
...
```

#### <a name="apidoc.element.gcloud.storage.prototype.getBuckets"></a>[function <span class="apidocSignatureSpan">gcloud.storage.prototype.</span>getBuckets ()](#apidoc.element.gcloud.storage.prototype.getBuckets)
- description and source-code
```javascript
getBuckets = function () {
  var parsedArguments = streamRouter.parseArguments_(arguments);
  return streamRouter.router_(parsedArguments, originalMethod.bind(this));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gcloud.translate"></a>[module gcloud.translate](#apidoc.module.gcloud.translate)

#### <a name="apidoc.element.gcloud.translate.translate"></a>[function <span class="apidocSignatureSpan">gcloud.</span>translate (options)](#apidoc.element.gcloud.translate.translate)
- description and source-code
```javascript
function Translate(options) {
  if (!(this instanceof Translate)) {
    options = util.normalizeArguments(this, options, {
      projectIdRequired: false
    });
    return new Translate(options);
  }

  if (!options.key) {
    throw new Error('An API key is required to use the Translate API.');
  }

  this.options = options;
  this.key = options.key;
}
```
- example usage
```shell
...
#### Preview

'''js
var gcloud = require('gcloud');

// Authenticating on a per-API-basis. You don't need to do this if you auth on a
// global basis (see Authentication section above).
var translate = gcloud.translate({
key: 'API Key'
});

// Translate a string of text.
translate.translate('Hello', 'es', function(err, translation) {
if (!err) {
  // translation = 'Hola'
...
```



# <a name="apidoc.module.gcloud.translate.prototype"></a>[module gcloud.translate.prototype](#apidoc.module.gcloud.translate.prototype)

#### <a name="apidoc.element.gcloud.translate.prototype.detect"></a>[function <span class="apidocSignatureSpan">gcloud.translate.prototype.</span>detect (input, callback)](#apidoc.element.gcloud.translate.prototype.detect)
- description and source-code
```javascript
detect = function (input, callback) {
  input = arrify(input);

  this.request({
    uri: '/detect',
    useQuerystring: true,
    qs: {
      q: input
    }
  }, function(err, resp) {
    if (err) {
      callback(err, null, resp);
      return;
    }

    var results = resp.data.detections.map(function(detection, index) {
      var result = extend({}, detection[0], {
        input: input[index]
      });

      // Deprecated.
      delete result.isReliable;

      return result;
    });

    if (input.length === 1) {
      results = results[0];
    }

    callback(null, results, resp);
  });
}
```
- example usage
```shell
...
translate.translate('Hello', 'es', function(err, translation) {
if (!err) {
  // translation = 'Hola'
}
});

// Detect a language from a string of text.
translate.detect('Hello', function(err, results) {
if (!err) {
  // results = {
  //   language: 'en',
  //   confidence: 1,
  //   input: 'Hello'
  // }
}
...
```

#### <a name="apidoc.element.gcloud.translate.prototype.getLanguages"></a>[function <span class="apidocSignatureSpan">gcloud.translate.prototype.</span>getLanguages (callback)](#apidoc.element.gcloud.translate.prototype.getLanguages)
- description and source-code
```javascript
getLanguages = function (callback) {
  this.request({
    uri: '/languages'
  }, function(err, resp) {
    if (err) {
      callback(err, null, resp);
      return;
    }

    var languages = resp.data.languages.map(prop('language'));
    callback(null, languages, resp);
  });
}
```
- example usage
```shell
...
  //   confidence: 1,
  //   input: 'Hello'
  // }
}
});

// Get a list of supported languages.
translate.getLanguages(function(err, languages) {
if (!err) {
  // languages = [
  //   'af',
  //   'ar',
  //   'az',
  //   ...
  // ]
...
```

#### <a name="apidoc.element.gcloud.translate.prototype.request"></a>[function <span class="apidocSignatureSpan">gcloud.translate.prototype.</span>request (reqOpts, callback)](#apidoc.element.gcloud.translate.prototype.request)
- description and source-code
```javascript
request = function (reqOpts, callback) {
  var BASE_URL = 'https://www.googleapis.com/language/translate/v2';

  reqOpts.uri = BASE_URL + reqOpts.uri;

  reqOpts = extend(true, {}, reqOpts, {
    qs: {
      key: this.key
    }
  });

  util.makeRequest(reqOpts, this.options, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.translate.prototype.translate"></a>[function <span class="apidocSignatureSpan">gcloud.translate.prototype.</span>translate (input, options, callback)](#apidoc.element.gcloud.translate.prototype.translate)
- description and source-code
```javascript
translate = function (input, options, callback) {
  var query = {
    q: arrify(input)
  };

  if (is.string(options)) {
    query.target = options;
  } else {
    if (options.from) {
      query.source = options.from;
    }

    if (options.to) {
      query.target = options.to;
    }
  }

  if (!query.target) {
    throw new Error('A target language is required to perform a translation.');
  }

  this.request({
    uri: '',
    useQuerystring: true,
    qs: query
  }, function(err, resp) {
    if (err) {
      callback(err, null, resp);
      return;
    }

    var translations = resp.data.translations.map(prop('translatedText'));

    if (query.q.length === 1) {
      translations = translations[0];
    }

    callback(err, translations, resp);
  });
}
```
- example usage
```shell
...
#### Preview

'''js
var gcloud = require('gcloud');

// Authenticating on a per-API-basis. You don't need to do this if you auth on a
// global basis (see Authentication section above).
var translate = gcloud.translate({
key: 'API Key'
});

// Translate a string of text.
translate.translate('Hello', 'es', function(err, translation) {
if (!err) {
  // translation = 'Hola'
...
```



# <a name="apidoc.module.gcloud.vision"></a>[module gcloud.vision](#apidoc.module.gcloud.vision)

#### <a name="apidoc.element.gcloud.vision.vision"></a>[function <span class="apidocSignatureSpan">gcloud.</span>vision (options)](#apidoc.element.gcloud.vision.vision)
- description and source-code
```javascript
function Vision(options) {
  if (!(this instanceof Vision)) {
    options = util.normalizeArguments(this, options);
    return new Vision(options);
  }

  var config = {
    baseUrl: 'https://vision.googleapis.com/v1',
    projectIdRequired: false,
    scopes: [
      'https://www.googleapis.com/auth/cloud-platform'
    ]
  };

  Service.call(this, config, options);
}
```
- example usage
```shell
...

'''js
var gcloud = require('gcloud');

// Authorizing on a per-API-basis. You don't need to do this if you auth on a
// global basis (see Authorization section above).

var vision = gcloud.vision({
projectId: 'my-project',
keyFilename: '/path/to/keyfile.json'
});

// Read the text from an image.
vision.detectText('./image.jpg', function(err, text) {
// text = [
...
```

#### <a name="apidoc.element.gcloud.vision.convertToBoolean_"></a>[function <span class="apidocSignatureSpan">gcloud.vision.</span>convertToBoolean_ (baseLikelihood, object)](#apidoc.element.gcloud.vision.convertToBoolean_)
- description and source-code
```javascript
convertToBoolean_ = function (baseLikelihood, object) {
  var convertedObject = {};

  for (var prop in object) {
    if (object.hasOwnProperty(prop)) {
      var value = Vision.likelihood[object[prop]];
      convertedObject[prop] = value >= baseLikelihood;
    }
  }

  return convertedObject;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.vision.findImages_"></a>[function <span class="apidocSignatureSpan">gcloud.vision.</span>findImages_ (images, callback)](#apidoc.element.gcloud.vision.findImages_)
- description and source-code
```javascript
findImages_ = function (images, callback) {
  var MAX_PARALLEL_LIMIT = 5;
  images = arrify(images);

  function findImage(image, callback) {
    if (image instanceof File) {
      callback(null, {
        source: {
          gcsImageUri: format('gs://{bucketName}/{fileName}', {
            bucketName: image.bucket.name,
            fileName: image.name
          })
        }
      });

      return;
    }

    // File is a URL.
    if (/^http/.test(image)) {
      request({
        method: 'GET',
        uri: image,
        encoding: 'base64'
      }, function(err, resp, body) {
        if (err) {
          callback(err);
          return;
        }

        callback(null, { content: body });
      });

      return;
    }

    // File exists on disk.
    fs.readFile(image, { encoding: 'base64' }, function(err, contents) {
      if (err) {
        callback(err);
        return;
      }

      callback(null, { content: contents });
    });
  }

  async.mapLimit(images, MAX_PARALLEL_LIMIT, findImage, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.vision.formatEntityAnnotation_"></a>[function <span class="apidocSignatureSpan">gcloud.vision.</span>formatEntityAnnotation_ (entityAnnotation, options)](#apidoc.element.gcloud.vision.formatEntityAnnotation_)
- description and source-code
```javascript
formatEntityAnnotation_ = function (entityAnnotation, options) {
  if (!options.verbose) {
    return entityAnnotation.description;
  }

  var formattedEntityAnnotation = {
    desc: entityAnnotation.description
  };

  if (entityAnnotation.mid) {
    formattedEntityAnnotation.mid = entityAnnotation.mid;
  }

  if (entityAnnotation.score) {
    formattedEntityAnnotation.score = entityAnnotation.score * 100;
  }

  if (entityAnnotation.boundingPoly) {
    formattedEntityAnnotation.bounds = entityAnnotation.boundingPoly.vertices;
  }

  if (is.defined(entityAnnotation.confidence)) {
    formattedEntityAnnotation.confidence = entityAnnotation.confidence * 100;
  }

  if (entityAnnotation.locations) {
    var locations = entityAnnotation.locations;
    formattedEntityAnnotation.locations = locations.map(prop('latLng'));
  }

  if (entityAnnotation.properties) {
    formattedEntityAnnotation.properties = entityAnnotation.properties;
  }

  return formattedEntityAnnotation;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.vision.formatError_"></a>[function <span class="apidocSignatureSpan">gcloud.vision.</span>formatError_ (err)](#apidoc.element.gcloud.vision.formatError_)
- description and source-code
```javascript
formatError_ = function (err) {
  var httpError = GrpcService.GRPC_ERROR_CODE_TO_HTTP[err.code];

  if (httpError) {
    err.code = httpError.code;
  }

  return err;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.vision.formatFaceAnnotation_"></a>[function <span class="apidocSignatureSpan">gcloud.vision.</span>formatFaceAnnotation_ (faceAnnotation)](#apidoc.element.gcloud.vision.formatFaceAnnotation_)
- description and source-code
```javascript
formatFaceAnnotation_ = function (faceAnnotation) {
  function findLandmark(type) {
    var landmarks = faceAnnotation.landmarks;

    return landmarks.filter(function(landmark) {
      return landmark.type === type;
    })[0].position;
  }

  var formattedFaceAnnotation = {
    angles: {
      pan: faceAnnotation.panAngle,
      roll: faceAnnotation.rollAngle,
      tilt: faceAnnotation.tiltAngle
    },

    bounds: {
      head: faceAnnotation.boundingPoly.vertices,
      face: faceAnnotation.fdBoundingPoly.vertices
    },

    features: {
      confidence: faceAnnotation.landmarkingConfidence * 100,
      chin: {
        center: findLandmark('CHIN_GNATHION'),
        left: findLandmark('CHIN_LEFT_GONION'),
        right: findLandmark('CHIN_RIGHT_GONION')
      },
      ears: {
        left: findLandmark('LEFT_EAR_TRAGION'),
        right: findLandmark('RIGHT_EAR_TRAGION'),
      },
      eyebrows: {
        left: {
          left: findLandmark('LEFT_OF_LEFT_EYEBROW'),
          right: findLandmark('RIGHT_OF_LEFT_EYEBROW'),
          top: findLandmark('LEFT_EYEBROW_UPPER_MIDPOINT')
        },
        right: {
          left: findLandmark('LEFT_OF_RIGHT_EYEBROW'),
          right: findLandmark('RIGHT_OF_RIGHT_EYEBROW'),
          top: findLandmark('RIGHT_EYEBROW_UPPER_MIDPOINT')
        }
      },
      eyes: {
        left: {
          bottom: findLandmark('LEFT_EYE_BOTTOM_BOUNDARY'),
          center: findLandmark('LEFT_EYE'),
          left: findLandmark('LEFT_EYE_LEFT_CORNER'),
          pupil: findLandmark('LEFT_EYE_PUPIL'),
          right: findLandmark('LEFT_EYE_RIGHT_CORNER'),
          top: findLandmark('LEFT_EYE_TOP_BOUNDARY')
        },
        right: {
          bottom: findLandmark('RIGHT_EYE_BOTTOM_BOUNDARY'),
          center: findLandmark('RIGHT_EYE'),
          left: findLandmark('RIGHT_EYE_LEFT_CORNER'),
          pupil: findLandmark('RIGHT_EYE_PUPIL'),
          right: findLandmark('RIGHT_EYE_RIGHT_CORNER'),
          top: findLandmark('RIGHT_EYE_TOP_BOUNDARY')
        }
      },
      forehead: findLandmark('FOREHEAD_GLABELLA'),
      lips: {
        bottom: findLandmark('LOWER_LIP'),
        top: findLandmark('UPPER_LIP')
      },
      mouth: {
        center: findLandmark('MOUTH_CENTER'),
        left: findLandmark('MOUTH_LEFT'),
        right: findLandmark('MOUTH_RIGHT')
      },
      nose: {
        bottom: {
          center: findLandmark('NOSE_BOTTOM_CENTER'),
          left: findLandmark('NOSE_BOTTOM_LEFT'),
          right: findLandmark('NOSE_BOTTOM_RIGHT')
        },
        tip: findLandmark('NOSE_TIP'),
        top: findLandmark('MIDPOINT_BETWEEN_EYES')
      }
    },

    confidence: faceAnnotation.detectionConfidence * 100
  };

  extend(formattedFaceAnnotation, Vision.convertToBoolean_(LIKELY, {
    blurry: faceAnnotation.blurredLikelihood,
    dark: faceAnnotation.underExposedLikelihood,
    happy: faceAnnotation.joyLikelihood,
    hat: faceAnnotation.headwearLikelihood,
    mad: faceAnnotation.angerLikelihood,
    sad: faceAnnotation.sorrowLikelihood,
    surprised: faceAnnotation.surpriseLikelihood
  }));

  return formattedFaceAnnotation;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.vision.formatImagePropertiesAnnotation_"></a>[function <span class="apidocSignatureSpan">gcloud.vision.</span>formatImagePropertiesAnnotation_ (imageAnnotation, options)](#apidoc.element.gcloud.vision.formatImagePropertiesAnnotation_)
- description and source-code
```javascript
formatImagePropertiesAnnotation_ = function (imageAnnotation, options) {
  var formattedImageAnnotation = {
    colors: imageAnnotation.dominantColors.colors
      .map(function(colorObject) {
        var red = colorObject.color.red;
        var green = colorObject.color.green;
        var blue = colorObject.color.blue;

        var hex = rgbHex(red, green, blue);

        if (!options.verbose) {
          return hex;
        }

        colorObject.hex = hex;

        colorObject.red = red;
        colorObject.green = green;
        colorObject.blue = blue;
        delete colorObject.color;

        colorObject.coverage = colorObject.pixelFraction *= 100;
        delete colorObject.pixelFraction;

        colorObject.score *= 100;

        return colorObject;
      })
  };

  return formattedImageAnnotation;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.vision.formatSafeSearchAnnotation_"></a>[function <span class="apidocSignatureSpan">gcloud.vision.</span>formatSafeSearchAnnotation_ (ssAnnotation, options)](#apidoc.element.gcloud.vision.formatSafeSearchAnnotation_)
- description and source-code
```javascript
formatSafeSearchAnnotation_ = function (ssAnnotation, options) {
  if (!options.verbose) {
    return Vision.convertToBoolean_(LIKELY, ssAnnotation);
  }

  return ssAnnotation;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.vision.super_"></a>[function <span class="apidocSignatureSpan">gcloud.vision.</span>super_ (config, options)](#apidoc.element.gcloud.vision.super_)
- description and source-code
```javascript
function Service(config, options) {
  var reqCfg = extend({}, config, {
    credentials: options.credentials,
    keyFile: options.keyFilename,
    email: options.email
  });

  this.makeAuthenticatedRequest = util.makeAuthenticatedRequestFactory(reqCfg);

  this.authClient = this.makeAuthenticatedRequest.authClient;
  this.baseUrl = config.baseUrl;
  this.getCredentials = this.makeAuthenticatedRequest.getCredentials;
  this.globalInterceptors = arrify(options.interceptors_);
  this.interceptors = [];
  this.projectId = options.projectId;
  this.projectIdRequired = config.projectIdRequired !== false;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gcloud.vision.prototype"></a>[module gcloud.vision.prototype](#apidoc.module.gcloud.vision.prototype)

#### <a name="apidoc.element.gcloud.vision.prototype.annotate"></a>[function <span class="apidocSignatureSpan">gcloud.vision.prototype.</span>annotate (requests, callback)](#apidoc.element.gcloud.vision.prototype.annotate)
- description and source-code
```javascript
annotate = function (requests, callback) {
  this.request({
    method: 'POST',
    uri: 'images:annotate',
    json: {
      requests: arrify(requests)
    }
  }, function(err, resp) {
    if (err) {
      callback(err, null, resp);
      return;
    }

    callback(null, resp.responses, resp);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.vision.prototype.detect"></a>[function <span class="apidocSignatureSpan">gcloud.vision.prototype.</span>detect (images, options, callback)](#apidoc.element.gcloud.vision.prototype.detect)
- description and source-code
```javascript
detect = function (images, options, callback) {
  var self = this;
  var isSingleImage = !is.array(images) || images.length === 1;

  if (!is.object(options)) {
    options = {
      types: options
    };
  }

  var types = arrify(options.types);

  var typeShortNameToFullName = {
    face: 'FACE_DETECTION',
    faces: 'FACE_DETECTION',

    label: 'LABEL_DETECTION',
    labels: 'LABEL_DETECTION',

    landmark: 'LANDMARK_DETECTION',
    landmarks: 'LANDMARK_DETECTION',

    logo: 'LOGO_DETECTION',
    logos: 'LOGO_DETECTION',

    properties: 'IMAGE_PROPERTIES',

    safeSearch: 'SAFE_SEARCH_DETECTION',

    text: 'TEXT_DETECTION'
  };

  var typeShortNameToRespName = {
    face: 'faceAnnotations',
    faces: 'faceAnnotations',

    label: 'labelAnnotations',
    labels: 'labelAnnotations',

    landmark: 'landmarkAnnotations',
    landmarks: 'landmarkAnnotations',

    logo: 'logoAnnotations',
    logos: 'logoAnnotations',

    properties: 'imagePropertiesAnnotation',

    safeSearch: 'safeSearchAnnotation',

    text: 'textAnnotations'
  };

  var typeRespNameToShortName = {
    errors: 'errors',
    faceAnnotations: 'faces',
    imagePropertiesAnnotation: 'properties',
    labelAnnotations: 'labels',
    landmarkAnnotations: 'landmarks',
    logoAnnotations: 'logos',
    safeSearchAnnotation: 'safeSearch',
    textAnnotations: 'text'
  };

  Vision.findImages_(images, function(err, images) {
    if (err) {
      callback(err);
      return;
    }

    var config = [];

    images.forEach(function(image) {
      types.forEach(function(type) {
        var typeName = typeShortNameToFullName[type];

        if (!typeName) {
          throw new Error('Requested detection feature not found: ' + type);
        }

        var cfg = {
          image: image,
          features: {
            type: typeName
          }
        };

        if (is.object(options.imageContext)) {
          cfg.imageContext = options.imageContext;
        }

        if (is.number(options.maxResults)) {
          cfg.features.maxResults = options.maxResults;
        }

        config.push(cfg);
      });
    });

    self.annotate(config, function(err, annotations, resp) {
      if (err) {
        callback(err, null, resp);
        return;
      }

      var originalResp = extend(true, {}, resp);

      var detections = images
        .map(groupDetectionsByImage)
        .map(assignTypeToEmptyAnnotations)
        .map(combineErrors)
        .map(flattenAnnotations)
        .map(decorateAnnotations);

      // If only a single image was given, expose it from the array.
      callback(null, isSingleImage ? detections[0] : detections, originalResp);

      function groupDetectionsByImage() {
        // detections = [
        //   // Image one:
        //   [
        //     {
        //       faceAnnotations: {},
        //       labelAnnotations: {},
        //       ...
        //     }
        //   ],
        //
        //   // Image two:
        //   [
        //     {
        //       faceAnnotations: {},
        //       labelAnnotations: {},
        //       ...
        //     }
        //   ]
        // ]
        return annotations.splice(0, types.length);
      }

      function assignTypeToEmptyAnnotations(annotations) {
        // Before:
        //   [
        //     {}, // What annotation type was attempted?
        //     { labelAnnotations: {...} }
        //   ]
        //
        // After:
        //   [
        //     { faceAnnotations: {} },
        //     { labelAnnotations: {...} }
        //   ]
        return annotations.map(function(annotation, index) {
          var detectionType = types[index];
          var typeName = typeShortNameToRespName[detectionType];

          if (is.empty(annotation) || annotation.error) {
            var isPlural = typeName.charAt(typeName.length - 1) === 's';
            annotation[typeName] = isPlural ? [] : {};
          }

          return annotation;
        });
      }

      function combineErrors(annotations) {
        // Before:
        //   [
        //     {
        //       faceAnnotations: [], ...
```
- example usage
```shell
...
translate.translate('Hello', 'es', function(err, translation) {
if (!err) {
  // translation = 'Hola'
}
});

// Detect a language from a string of text.
translate.detect('Hello', function(err, results) {
if (!err) {
  // results = {
  //   language: 'en',
  //   confidence: 1,
  //   input: 'Hello'
  // }
}
...
```

#### <a name="apidoc.element.gcloud.vision.prototype.detectFaces"></a>[function <span class="apidocSignatureSpan">gcloud.vision.prototype.</span>detectFaces (images, options, callback)](#apidoc.element.gcloud.vision.prototype.detectFaces)
- description and source-code
```javascript
detectFaces = function (images, options, callback) {
  if (is.fn(options)) {
    callback = options;
    options = {};
  }

  options = extend({}, options, {
    types: ['faces']
  });

  this.detect(images, options, callback);
}
```
- example usage
```shell
...
// text = [
//   'This was text found in the image',
//   'This was more text found in the image'
// ]
});

// Detect faces and the locations of their features in an image.
vision.detectFaces('./image.jpg', function(err, faces) {
// faces = [
//   {
//     angles: {pan,tilt,roll},
//     bounds: {
//       head: [{x,y},{x,y},{x,y},{x,y}],
//       face: [{x,y},{x,y},{x,y},{x,y}]
//     },
...
```

#### <a name="apidoc.element.gcloud.vision.prototype.detectLabels"></a>[function <span class="apidocSignatureSpan">gcloud.vision.prototype.</span>detectLabels (images, options, callback)](#apidoc.element.gcloud.vision.prototype.detectLabels)
- description and source-code
```javascript
detectLabels = function (images, options, callback) {
  if (is.fn(options)) {
    callback = options;
    options = {};
  }

  options = extend({}, options, {
    types: ['labels']
  });

  this.detect(images, options, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.vision.prototype.detectLandmarks"></a>[function <span class="apidocSignatureSpan">gcloud.vision.prototype.</span>detectLandmarks (images, options, callback)](#apidoc.element.gcloud.vision.prototype.detectLandmarks)
- description and source-code
```javascript
detectLandmarks = function (images, options, callback) {
  if (is.fn(options)) {
    callback = options;
    options = {};
  }

  options = extend({}, options, {
    types: ['landmarks']
  });

  this.detect(images, options, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.vision.prototype.detectLogos"></a>[function <span class="apidocSignatureSpan">gcloud.vision.prototype.</span>detectLogos (images, options, callback)](#apidoc.element.gcloud.vision.prototype.detectLogos)
- description and source-code
```javascript
detectLogos = function (images, options, callback) {
  if (is.fn(options)) {
    callback = options;
    options = {};
  }

  options = extend({}, options, {
    types: ['logos']
  });

  this.detect(images, options, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.vision.prototype.detectProperties"></a>[function <span class="apidocSignatureSpan">gcloud.vision.prototype.</span>detectProperties (images, options, callback)](#apidoc.element.gcloud.vision.prototype.detectProperties)
- description and source-code
```javascript
detectProperties = function (images, options, callback) {
  if (is.fn(options)) {
    callback = options;
    options = {};
  }

  options = extend({}, options, {
    types: ['properties']
  });

  this.detect(images, options, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.vision.prototype.detectSafeSearch"></a>[function <span class="apidocSignatureSpan">gcloud.vision.prototype.</span>detectSafeSearch (images, options, callback)](#apidoc.element.gcloud.vision.prototype.detectSafeSearch)
- description and source-code
```javascript
detectSafeSearch = function (images, options, callback) {
  if (is.fn(options)) {
    callback = options;
    options = {};
  }

  options = extend({}, options, {
    types: ['safeSearch']
  });

  this.detect(images, options, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gcloud.vision.prototype.detectText"></a>[function <span class="apidocSignatureSpan">gcloud.vision.prototype.</span>detectText (images, options, callback)](#apidoc.element.gcloud.vision.prototype.detectText)
- description and source-code
```javascript
detectText = function (images, options, callback) {
  if (is.fn(options)) {
    callback = options;
    options = {};
  }

  options = extend({}, options, {
    types: ['text']
  });

  this.detect(images, options, callback);
}
```
- example usage
```shell
...

var vision = gcloud.vision({
  projectId: 'my-project',
  keyFilename: '/path/to/keyfile.json'
});

// Read the text from an image.
vision.detectText('./image.jpg', function(err, text) {
  // text = [
  //   'This was text found in the image',
  //   'This was more text found in the image'
  // ]
});

// Detect faces and the locations of their features in an image.
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
