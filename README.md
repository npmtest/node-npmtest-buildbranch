# test coverage for  [buildbranch (v2.0.0)](https://github.com/nfroidure/buildbranch)  [![npm package](https://img.shields.io/npm/v/npmtest-buildbranch.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-buildbranch) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-buildbranch.svg)](https://travis-ci.org/npmtest/node-npmtest-buildbranch)
#### Publish a folder to the given build branch (like gh-pages).

[![NPM](https://nodei.co/npm/buildbranch.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/buildbranch)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-buildbranch/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-buildbranch/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-buildbranch/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-buildbranch/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-buildbranch/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-buildbranch/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-buildbranch/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-buildbranch/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-buildbranch/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-buildbranch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-buildbranch/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-buildbranch/build/test-report.html](https://npmtest.github.io/node-npmtest-buildbranch/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-buildbranch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-buildbranch/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-buildbranch/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-buildbranch/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-buildbranch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-buildbranch/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-buildbranch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-buildbranch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nicolas Froidure"
    },
    "bin": {
        "buildbranch": "./src/bin.js"
    },
    "bugs": {
        "url": "https://github.com/nfroidure/buildbranch/issues"
    },
    "dependencies": {
        "debug": "1.0.0",
        "rimraf": "^2.5.2"
    },
    "description": "Publish a folder to the given build branch (like gh-pages).",
    "devDependencies": {
        "coveralls": "2.11.15",
        "eslint": "3.4.0",
        "eslint-config-simplifield": "4.1.1",
        "istanbul": "0.4.5",
        "metapak": "0.0.15",
        "metapak-nfroidure": "^0.1.0",
        "mocha": "3.2.0",
        "mocha-lcov-reporter": "1.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "155143d5df5973b2869943a525f72665c59fc209",
        "tarball": "https://registry.npmjs.org/buildbranch/-/buildbranch-2.0.0.tgz"
    },
    "engines": {
        "node": ">=6.9.5"
    },
    "gitHead": "ba25e2bf7caa23e4ecf64fdf654ca5b21821a543",
    "homepage": "https://github.com/nfroidure/buildbranch",
    "keywords": [
        "gulpfriendly",
        "gruntfriendly",
        "ghpages",
        "gh-pages",
        "build",
        "publish",
        "git",
        "github"
    ],
    "license": "MIT",
    "main": "src/index",
    "maintainers": [
        {
            "name": "nfroidure"
        }
    ],
    "name": "buildbranch",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/nfroidure/buildbranch.git"
    },
    "scripts": {
        "cli": "env NODE_ENV=${NODE_ENV:-cli}",
        "lint": "eslint src/*.js",
        "metapak": "metapak || echo 'Please 'npm install --save-dev metapak'' && exit 0",
        "postinstall": "npm run metapak",
        "preversion": "npm t && npm run lint"
    },
    "version": "2.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
