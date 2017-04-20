# npmtest-benchmark

#### basic test coverage for  [benchmark (v2.1.4)](https://benchmarkjs.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-benchmark.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-benchmark) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-benchmark.svg)](https://travis-ci.org/npmtest/node-npmtest-benchmark)

#### A benchmarking library that supports high-resolution timers & returns statistically significant results.

[![NPM](https://nodei.co/npm/benchmark.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/benchmark)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-benchmark/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-benchmark/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-benchmark/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-benchmark/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-benchmark/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-benchmark/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-benchmark/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-benchmark/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-benchmark/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-benchmark/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-benchmark/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-benchmark/build/test-report.html](https://npmtest.github.io/node-npmtest-benchmark/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-benchmark/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-benchmark/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-benchmark/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-benchmark/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-benchmark/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-benchmark/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-benchmark/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-benchmark/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mathias Bynens",
        "url": "https://mathiasbynens.be/"
    },
    "bugs": {
        "url": "https://github.com/bestiejs/benchmark.js/issues"
    },
    "contributors": [
        {
            "name": "Mathias Bynens",
            "url": "https://mathiasbynens.be/"
        },
        {
            "name": "John-David Dalton",
            "url": "http://allyoucanleet.com/"
        },
        {
            "name": "Kit Cambridge",
            "url": "http://kitcambridge.be/"
        }
    ],
    "dependencies": {
        "lodash": "^4.17.4",
        "platform": "^1.3.3"
    },
    "description": "A benchmarking library that supports high-resolution timers & returns statistically significant results.",
    "devDependencies": {
        "coveralls": "^2.12.0",
        "docdown": "~0.7.2",
        "istanbul": "0.4.5",
        "qunit-extras": "^3.0.0",
        "qunitjs": "^2.2.1",
        "requirejs": "^2.3.3"
    },
    "directories": {},
    "dist": {
        "shasum": "09f3de31c916425d498cc2ee565a0ebf3c2a5629",
        "tarball": "https://registry.npmjs.org/benchmark/-/benchmark-2.1.4.tgz"
    },
    "files": [
        "benchmark.js"
    ],
    "homepage": "https://benchmarkjs.com/",
    "keywords": [
        "benchmark",
        "performance",
        "speed"
    ],
    "license": "MIT",
    "main": "benchmark.js",
    "maintainers": [
        {
            "name": "jdalton"
        },
        {
            "name": "mathias"
        }
    ],
    "name": "benchmark",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/bestiejs/benchmark.js.git"
    },
    "scripts": {
        "doc": "docdown benchmark.js doc/README.md style=github title=\"<a href=\\\"https://benchmarkjs.com/\\\">Benchmark.js</a> <span>v${npm_package_version}</span>\" toc=categories url=https://github.com/bestiejs/benchmark.js/blob/${npm_package_version}/benchmark.js",
        "test": "node test/test"
    },
    "version": "2.1.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
