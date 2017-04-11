# test coverage for  [event-stream (v3.3.4)](http://github.com/dominictarr/event-stream)  [![npm package](https://img.shields.io/npm/v/npmtest-event-stream.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-event-stream) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-event-stream.svg)](https://travis-ci.org/npmtest/node-npmtest-event-stream)
#### construct pipes of streams of events

[![NPM](https://nodei.co/npm/event-stream.png?downloads=true)](https://www.npmjs.com/package/event-stream)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-event-stream/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-event-stream/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-event-stream/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-event-stream/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-event-stream/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-event-stream/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-event-stream/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-event-stream/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-event-stream/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-event-stream/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-event-stream%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-event-stream/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-event-stream/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-event-stream%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-event-stream/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-event-stream/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-event-stream/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dominic Tarr",
        "email": "dominic.tarr@gmail.com",
        "url": "http://bit.ly/dominictarr"
    },
    "bugs": {
        "url": "https://github.com/dominictarr/event-stream/issues"
    },
    "dependencies": {
        "duplexer": "~0.1.1",
        "from": "~0",
        "map-stream": "~0.1.0",
        "pause-stream": "0.0.11",
        "split": "0.3",
        "stream-combiner": "~0.0.4",
        "through": "~2.3.1"
    },
    "description": "construct pipes of streams of events",
    "devDependencies": {
        "asynct": "*",
        "it-is": "1",
        "stream-spec": "~0.3.5",
        "tape": "~2.3.0",
        "ubelt": "~3.2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "4ab4c9a0f5a54db9338b4c34d86bfce8f4b35571",
        "tarball": "https://registry.npmjs.org/event-stream/-/event-stream-3.3.4.tgz"
    },
    "gitHead": "0d9d45744b06ead81976b3400569160b76299a41",
    "homepage": "http://github.com/dominictarr/event-stream",
    "license": "MIT",
    "maintainers": [
        {
            "name": "dominictarr",
            "email": "dominic.tarr@gmail.com"
        }
    ],
    "name": "event-stream",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/dominictarr/event-stream.git"
    },
    "scripts": {
        "prepublish": "npm ls && npm test",
        "test": "asynct test/",
        "test_tap": "set -e; for t in test/*.js; do node $t; done"
    },
    "testling": {
        "files": "test/*.js",
        "browsers": {
            "ie": [
                8,
                9
            ],
            "firefox": [
                13
            ],
            "chrome": [
                20
            ],
            "safari": [
                5.1
            ],
            "opera": [
                12
            ]
        }
    },
    "version": "3.3.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
