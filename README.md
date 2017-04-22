# npmtest-hyperterm-paste

#### basic test coverage for  [hyperterm-paste (v1.1.0)](https://github.com/krzkaczor/hyperterm-paste#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-hyperterm-paste.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hyperterm-paste) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hyperterm-paste.svg)](https://travis-ci.org/npmtest/node-npmtest-hyperterm-paste)

#### Makes pasting into hyperterm safe

[![NPM](https://nodei.co/npm/hyperterm-paste.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hyperterm-paste)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hyperterm-paste/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hyperterm-paste/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hyperterm-paste/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hyperterm-paste/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hyperterm-paste/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hyperterm-paste/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hyperterm-paste/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hyperterm-paste/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hyperterm-paste/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hyperterm-paste/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hyperterm-paste/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hyperterm-paste/build/test-report.html](https://npmtest.github.io/node-npmtest-hyperterm-paste/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hyperterm-paste/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hyperterm-paste/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hyperterm-paste/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hyperterm-paste/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hyperterm-paste/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hyperterm-paste/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hyperterm-paste/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hyperterm-paste/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "hyperterm-paste",
    "version": "1.1.0",
    "description": "Makes pasting into hyperterm safe",
    "main": "src/index.js",
    "scripts": {
        "test": "standard && mocha",
        "prepublish": "npm test"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/krzkaczor/hyperterm-paste.git"
    },
    "keywords": [
        "hyperterm",
        "paste"
    ],
    "author": "Krzysztof Kaczor",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/krzkaczor/hyperterm-paste/issues"
    },
    "homepage": "https://github.com/krzkaczor/hyperterm-paste#readme",
    "devDependencies": {
        "chai": "3.5.0",
        "mocha": "3.0.0"
    },
    "standard": {
        "env": [
            "mocha"
        ]
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
