# npmtest-ember-fetch

#### basic test coverage for  ember-fetch (v1.4.2)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-fetch.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-fetch) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-fetch.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-fetch)

#### HTML5 Fetch polyfill (as an ember-addon)

[![NPM](https://nodei.co/npm/ember-fetch.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-fetch)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-fetch/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-fetch/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-fetch/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-fetch/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-fetch/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-fetch/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-fetch/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-fetch/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-fetch/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-fetch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-fetch/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-fetch/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-fetch/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-fetch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-fetch/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-fetch/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-fetch/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-fetch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-fetch/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-fetch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-fetch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ember-fetch",
    "version": "1.4.2",
    "description": "HTML5 Fetch polyfill (as an ember-addon)",
    "keywords": [
        "ember-addon"
    ],
    "license": "MIT",
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "repository": "https://github.com/stefanpenner/ember-fetch",
    "scripts": {
        "build": "ember build",
        "start": "ember server",
        "test": "ember try:each"
    },
    "dependencies": {
        "broccoli-funnel": "^1.0.7",
        "broccoli-stew": "^1.2.0",
        "broccoli-templater": "^1.0.0",
        "ember-cli-babel": "^6.0.0-beta.4",
        "node-fetch": "^2.0.0-alpha.3",
        "whatwg-fetch": "^2.0.3"
    },
    "devDependencies": {
        "broccoli-asset-rev": "^2.4.5",
        "ember-cli": "^2.12.1",
        "ember-cli-app-version": "^2.0.0",
        "ember-cli-dependency-checker": "^1.3.0",
        "ember-cli-eslint": "^3.0.2",
        "ember-cli-htmlbars": "^1.2.0",
        "ember-cli-inject-live-reload": "^1.4.1",
        "ember-cli-pretender": "^0.7.0",
        "ember-cli-qunit": "^3.1.0",
        "ember-cli-release": "^0.2.9",
        "ember-cli-shims": "^1.1.0",
        "ember-cli-test-loader": "^2.0.0",
        "ember-cli-uglify": "^1.2.0",
        "ember-load-initializers": "^0.6.0",
        "ember-resolver": "^2.0.3",
        "ember-source": "~2.12.0",
        "loader.js": "^4.2.3"
    },
    "engines": {
        "node": ">= 4"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config",
        "fastbootDependencies": [
            "node-fetch"
        ]
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
