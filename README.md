# npmtest-node-ios-device

#### basic test coverage for  node-ios-device (v1.3.1)  [![npm package](https://img.shields.io/npm/v/npmtest-node-ios-device.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-ios-device) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-ios-device.svg)](https://travis-ci.org/npmtest/node-npmtest-node-ios-device)

#### iOS device library

[![NPM](https://nodei.co/npm/node-ios-device.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-ios-device)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-ios-device/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-ios-device/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-ios-device/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-ios-device/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-ios-device/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-ios-device/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-ios-device/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-ios-device/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-ios-device/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-ios-device/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-ios-device/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-ios-device/build/test-report.html](https://npmtest.github.io/node-npmtest-node-ios-device/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-ios-device/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-ios-device/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-ios-device/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-ios-device/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-ios-device/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-ios-device/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-ios-device/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-ios-device/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-ios-device",
    "description": "iOS device library",
    "version": "1.3.1",
    "author": {
        "name": "Appcelerator, Inc."
    },
    "maintainers": [
        {
            "name": "Chris Barber"
        }
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/appcelerator/node-ios-device.git"
    },
    "keywords": [
        "appcelerator",
        "ios",
        "iphone",
        "ipad",
        "install",
        "mobiledevice",
        "mobile"
    ],
    "dependencies": {
        "debug": "^2.6.3",
        "nan": "^2.5.1",
        "node-pre-gyp": "^0.6.34",
        "node-pre-gyp-init": "^1.0.0"
    },
    "bundledDependencies": [
        "node-pre-gyp"
    ],
    "devDependencies": {
        "aws-sdk": "^2.36.0"
    },
    "scripts": {
        "install": "node-pre-gyp install --fallback-to-build",
        "build-n-publish-binding": "node-pre-gyp rebuild package publish",
        "prepublish": "./bin/build-all.sh",
        "rebuild": "node-pre-gyp rebuild",
        "rebuild-debug": "node-pre-gyp --debug rebuild",
        "xcode": "node-pre-gyp configure -- -f xcode"
    },
    "binary": {
        "module_name": "node_ios_device",
        "module_path": "./binding/{node_abi}-{platform}-{arch}/",
        "remote_path": "./{name}/v{version}",
        "host": "https://appc-node-binaries.s3.amazonaws.com"
    },
    "license": "Apache-2.0",
    "gypfile": true,
    "os": [
        "darwin"
    ],
    "main": "./ios-device",
    "engines": {
        "node": ">=0.10"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
