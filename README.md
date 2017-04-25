# npmtest-stack.io

#### basic test coverage for  stack.io (v0.2.9)  [![npm package](https://img.shields.io/npm/v/npmtest-stack.io.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-stack.io) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-stack.io.svg)](https://travis-ci.org/npmtest/node-npmtest-stack.io)

#### ZeroRPC bridge to the web

[![NPM](https://nodei.co/npm/stack.io.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/stack.io)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-stack.io/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-stack.io/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-stack.io/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-stack.io/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-stack.io/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-stack.io/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-stack.io/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-stack.io/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-stack.io/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-stack.io/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-stack.io/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-stack.io/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-stack.io/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-stack.io/build/test-report.html](https://npmtest.github.io/node-npmtest-stack.io/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-stack.io/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-stack.io/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-stack.io/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-stack.io/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-stack.io/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-stack.io/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-stack.io/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-stack.io/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "stack.io",
    "version": "0.2.9",
    "description": "ZeroRPC bridge to the web",
    "main": "./index.js",
    "keywords": [
        "message passing",
        "rpc",
        "remote",
        "communication"
    ],
    "bin": {
        "stackio": "./bin/stackio"
    },
    "dependencies": {
        "underscore": "1.3.x",
        "socket.io": "0.9.6",
        "express": "2.5.9",
        "zerorpc": "0.9.x",
        "oauth": "0.9.7",
        "sqlite-wrapper": "0.2.x",
        "optimist": "0.3.4"
    },
    "repository": {
        "type": "git",
        "url": "http://github.com/dotcloud/stack.io"
    },
    "author": "dotCloud <opensource@dotcloud.com>",
    "contributors": [
        {
            "name": "Sam Alba"
        },
        {
            "name": "Francois-Xavier Bourlet"
        },
        {
            "name": "Joffrey Fuhrer"
        },
        {
            "name": "Yusuf Simonson"
        }
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
