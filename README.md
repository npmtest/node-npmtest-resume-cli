# npmtest-resume-cli

#### test coverage for  [resume-cli (v0.4.19)](https://github.com/rolandnsharp/resume-cli#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-resume-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-resume-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-resume-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-resume-cli)

#### The JSON Resume command line interface

[![NPM](https://nodei.co/npm/resume-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/resume-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-resume-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-resume-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-resume-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-resume-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-resume-cli/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-resume-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-resume-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-resume-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-resume-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-resume-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-resume-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-resume-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-resume-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-resume-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-resume-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-resume-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-resume-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-resume-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-resume-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-resume-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-resume-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "resume": "index.js"
    },
    "bugs": {
        "url": "https://github.com/rolandnsharp/resume-cli/issues"
    },
    "dependencies": {
        "async": "^1.5.0",
        "chalk": "^1.1.1",
        "char-spinner": "^1.0.1",
        "cli-spinner": "^0.2.1",
        "colors": "^1.1.2",
        "commander": "^2.9.0",
        "dotenv": "^2.0.0",
        "html-pdf": "^2.1.0",
        "jsonlint": "^1.6.2",
        "jsonresume-theme-crisp": "^0.2.12",
        "jsonresume-theme-flat": "^0.3.7",
        "jsonresume-theme-modern": "0.0.18",
        "jspdf": "^1.3.2",
        "node-static": "~0.7.7",
        "open": "0.0.5",
        "read": "~1.0.7",
        "resume-schema": "latest",
        "resume-to-html": "latest",
        "resume-to-text": "latest",
        "should": "^11.1.0",
        "superagent": "^2.0.0",
        "terminal-menu": "^2.1.1"
    },
    "description": "The JSON Resume command line interface",
    "devDependencies": {
        "mocha": "^3.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "25f8374a844aa652021a1611a1c1077781a8bf7b",
        "tarball": "https://registry.npmjs.org/resume-cli/-/resume-cli-0.4.19.tgz"
    },
    "engines": {
        "node": "^4"
    },
    "gitHead": "6a813ea695191eea52114d031ea71ffbec05daab",
    "homepage": "https://github.com/rolandnsharp/resume-cli#readme",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "rolandnsharp"
        },
        {
            "name": "thomasdavis"
        },
        {
            "name": "erming"
        },
        {
            "name": "mchelen"
        }
    ],
    "name": "resume-cli",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/rolandnsharp/resume-cli.git"
    },
    "scripts": {
        "test": "node node_modules/mocha/bin/mocha test test/*.js"
    },
    "version": "0.4.19",
    "warnings": [
        {
            "code": "ENOTSUP",
            "required": {
                "node": "^4"
            },
            "pkgid": "resume-cli@0.4.19"
        },
        {
            "code": "ENOTSUP",
            "required": {
                "node": "^4"
            },
            "pkgid": "resume-cli@0.4.19"
        }
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
