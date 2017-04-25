# npmtest-highland

#### basic test coverage for  [highland (v2.10.5)](http://highlandjs.org/)  [![npm package](https://img.shields.io/npm/v/npmtest-highland.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-highland) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-highland.svg)](https://travis-ci.org/npmtest/node-npmtest-highland)

#### The high-level streams library

[![NPM](https://nodei.co/npm/highland.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/highland)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-highland/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-highland/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-highland/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-highland/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-highland/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-highland/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-highland/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-highland/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-highland/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-highland/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-highland/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-highland/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-highland/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-highland/build/test-report.html](https://npmtest.github.io/node-npmtest-highland/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-highland/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-highland/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-highland/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-highland/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-highland/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-highland/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-highland/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-highland/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/caolan/highland/issues"
    },
    "dependencies": {
        "util-deprecate": "^1.0.2"
    },
    "description": "The high-level streams library",
    "devDependencies": {
        "bluebird": "^3.3.5",
        "browserify": "^13.0.0",
        "browserify-shim": "^3.8.11",
        "concat-stream": "~1.4.1",
        "eslint": "^2.10.0",
        "grunt": "~1.0.1",
        "grunt-browserify": "^5.0.0",
        "grunt-bump": "0.8.0",
        "grunt-contrib-nodeunit": "~1.0.0",
        "grunt-contrib-uglify": "^2.0.0",
        "grunt-contrib-watch": "~1.0.0",
        "grunt-eslint": "^18.0.0",
        "grunt-gh-pages": "~2.0.0",
        "grunt-npm": "0.0.2",
        "handlebars": "~4.0.5",
        "nodeunit": "~0.10.0",
        "rsvp": "~3.2.0",
        "scrawl": "0.0.5",
        "sinon": "~1.17.3",
        "stream-array": "~1.1.2",
        "through": "~2.3.4",
        "transducers-js": "~0.4.174",
        "uglify-js": "^2.6.1"
    },
    "directories": {},
    "dist": {
        "shasum": "6007fd24f4838d9117ba41bdcc98ec3b54bfde18",
        "tarball": "https://registry.npmjs.org/highland/-/highland-2.10.5.tgz"
    },
    "files": [
        "dist",
        "lib"
    ],
    "gitHead": "fa104f5f958e39892c13bcd316128b3a6ceedf47",
    "homepage": "http://highlandjs.org/",
    "license": "Apache-2.0",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "caolan"
        },
        {
            "name": "jeromew"
        },
        {
            "name": "vqvu"
        }
    ],
    "name": "highland",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/caolan/highland.git"
    },
    "scripts": {
        "test": "eslint Gruntfile.js lib test/test.js && nodeunit test/test.js"
    },
    "version": "2.10.5",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
