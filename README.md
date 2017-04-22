# npmtest-aurelia-cli

#### basic test coverage for  [aurelia-cli (v0.28.0)](http://aurelia.io)  [![npm package](https://img.shields.io/npm/v/npmtest-aurelia-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-aurelia-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-aurelia-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-aurelia-cli)

#### The command line tooling for Aurelia.

[![NPM](https://nodei.co/npm/aurelia-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/aurelia-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-aurelia-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-aurelia-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-aurelia-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-aurelia-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-aurelia-cli/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-aurelia-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-aurelia-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-aurelia-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-aurelia-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-aurelia-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-aurelia-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-aurelia-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-aurelia-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-aurelia-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-aurelia-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-aurelia-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-aurelia-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-aurelia-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-aurelia-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-aurelia-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-aurelia-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rob Eisenberg",
        "url": "http://robeisenberg.com/"
    },
    "bin": {
        "aurelia": "bin/aurelia-cli.js",
        "au": "bin/aurelia-cli.js"
    },
    "bugs": {
        "url": "https://github.com/aurelia/cli/issues"
    },
    "dependencies": {
        "aurelia-dependency-injection": "^1.0.0",
        "aurelia-logging": "^1.2.0",
        "aurelia-polyfills": "^1.0.0",
        "esprima": "^3.1.3",
        "glob": "^7.1.1",
        "npm": "^3.10.8",
        "rfc6902": "^1.2.2",
        "semver": "^5.3.0"
    },
    "description": "The command line tooling for Aurelia.",
    "devDependencies": {
        "aurelia-tools": "^0.2.4",
        "babel-eslint": "^7.1.1",
        "gulp": "^3.9.1",
        "gulp-bump": "^2.7.0",
        "gulp-conventional-changelog": "^1.1.3",
        "gulp-eslint": "^3.0.1",
        "jasmine": "^2.5.2",
        "mock-fs": "^4.2.0",
        "nodemon": "^1.11.0",
        "require-dir": "^0.3.1",
        "run-sequence": "^1.2.2",
        "yargs": "^7.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "0dc8554c9bed09634796861543f0343a522d6103",
        "tarball": "https://registry.npmjs.org/aurelia-cli/-/aurelia-cli-0.28.0.tgz"
    },
    "gitHead": "55e487db207a2b3aa8e85c4d44f4f7c8ba238330",
    "homepage": "http://aurelia.io",
    "keywords": [
        "aurelia",
        "cli",
        "bundle",
        "scaffold"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "ahmedshuhel"
        },
        {
            "name": "aureliaeffect"
        }
    ],
    "name": "aurelia-cli",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/aurelia/cli.git"
    },
    "scripts": {
        "test": "jasmine",
        "test:watch": "nodemon -x 'npm test'"
    },
    "version": "0.28.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
