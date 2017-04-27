# npmtest-mock-fs

#### basic test coverage for  [mock-fs (v4.2.0)](https://github.com/tschaub/mock-fs)  [![npm package](https://img.shields.io/npm/v/npmtest-mock-fs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mock-fs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mock-fs.svg)](https://travis-ci.org/npmtest/node-npmtest-mock-fs)

#### A configurable mock file system.  You know, for testing.

[![NPM](https://nodei.co/npm/mock-fs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mock-fs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mock-fs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mock-fs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mock-fs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mock-fs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mock-fs/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-mock-fs/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-mock-fs/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mock-fs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mock-fs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mock-fs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mock-fs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mock-fs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mock-fs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mock-fs/build/test-report.html](https://npmtest.github.io/node-npmtest-mock-fs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mock-fs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mock-fs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mock-fs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mock-fs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mock-fs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mock-fs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mock-fs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mock-fs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tim Schaub",
        "url": "http://tschaub.net/"
    },
    "bugs": {
        "url": "https://github.com/tschaub/mock-fs/issues"
    },
    "dependencies": {},
    "description": "A configurable mock file system.  You know, for testing.",
    "devDependencies": {
        "bench-it": "0.4.0",
        "chai": "3.5.0",
        "eslint": "^3.11.1",
        "eslint-config-tschaub": "^6.0.0",
        "mocha": "3.1.2",
        "rimraf": "2.5.4"
    },
    "directories": {},
    "dist": {
        "shasum": "ef53ae17b77e64f67816dd0467f29208a3b26e19",
        "tarball": "https://registry.npmjs.org/mock-fs/-/mock-fs-4.2.0.tgz"
    },
    "gitHead": "d7532caa28638a01784921e6f980cf8b79f3d54e",
    "homepage": "https://github.com/tschaub/mock-fs",
    "keywords": [
        "mock",
        "fs",
        "test",
        "fixtures",
        "file system",
        "memory"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "tschaub"
        }
    ],
    "name": "mock-fs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/tschaub/mock-fs.git"
    },
    "scripts": {
        "bench": "bench benchmarks",
        "pretest": "eslint benchmarks lib test",
        "test": "mocha --recursive test"
    },
    "version": "4.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
