# npmdoc-cssnano-cli

#### api documentation for  [cssnano-cli (v1.0.5)](https://github.com/ben-eb/cssnano-cli)  [![npm package](https://img.shields.io/npm/v/npmdoc-cssnano-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-cssnano-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-cssnano-cli.svg)](https://travis-ci.org/npmdoc/node-npmdoc-cssnano-cli)

#### A CLI for modular minifier cssnano.

[![NPM](https://nodei.co/npm/cssnano-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cssnano-cli)

- [https://npmdoc.github.io/node-npmdoc-cssnano-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cssnano-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cssnano-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cssnano-cli/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-cssnano-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-cssnano-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "cssnano-cli",
    "version": "1.0.5",
    "description": "A CLI for modular minifier cssnano.",
    "bin": {
        "cssnano": "cmd.js"
    },
    "files": [
        "cmd.js",
        "usage.txt",
        "LICENSE-MIT"
    ],
    "scripts": {
        "test": "tape test.js | tap-spec"
    },
    "keywords": [
        "cli",
        "cli-app",
        "cssnano",
        "compress",
        "minify",
        "optimise",
        "optimisation",
        "postcss"
    ],
    "license": "MIT",
    "dependencies": {
        "cssnano": "^3.0.0",
        "minimist": "^1.2.0",
        "read-file-stdin": "^0.2.0",
        "write-file-stdout": "0.0.2"
    },
    "devDependencies": {
        "tap-spec": "^4.1.0",
        "tape": "^4.2.0"
    },
    "homepage": "https://github.com/ben-eb/cssnano-cli",
    "author": {
        "name": "Ben Briggs",
        "url": "http://beneb.info"
    },
    "repository": "ben-eb/cssnano-cli"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
