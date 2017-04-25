# npmdoc-chairo

#### basic api documentation for  [chairo (v3.0.0)](https://github.com/hapijs/chairo#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-chairo.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-chairo) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-chairo.svg)](https://travis-ci.org/npmdoc/node-npmdoc-chairo)

#### Seneca micro-services plugin for hapi

[![NPM](https://nodei.co/npm/chairo.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/chairo)

- [https://npmdoc.github.io/node-npmdoc-chairo/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-chairo/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-chairo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-chairo/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-chairo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-chairo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/hapijs/chairo/issues"
    },
    "dependencies": {
        "boom": "4.x.x",
        "hoek": "4.x.x",
        "items": "2.x.x",
        "joi": "10.x.x",
        "jsonic": "0.2.x",
        "seneca": "3.x.x"
    },
    "description": "Seneca micro-services plugin for hapi",
    "devDependencies": {
        "code": "4.x.x",
        "coveralls": "2.x.x",
        "handlebars": "4.x.x",
        "hapi": "15.x.x",
        "lab": "11.x.x",
        "vision": "4.x.x"
    },
    "directories": {},
    "dist": {
        "shasum": "80cf6c1b9906236d95731100ee198775e05695dd",
        "tarball": "https://registry.npmjs.org/chairo/-/chairo-3.0.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "df6287e609e96bdcb15f162c51933f2ea54ab176",
    "homepage": "https://github.com/hapijs/chairo#readme",
    "keywords": [
        "hapi",
        "plugin",
        "microservices",
        "seneca"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "hueniverse"
        },
        {
            "name": "wyatt"
        }
    ],
    "name": "chairo",
    "optionalDependencies": {},
    "peerDependencies": {
        "hapi": ">=11.x.x"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/hapijs/chairo.git"
    },
    "scripts": {
        "cover": "lab -s -r lcov | coveralls",
        "test": "node node_modules/lab/bin/lab -a code -t 100 -L",
        "test-cov-html": "node node_modules/lab/bin/lab -a code -r html -o coverage.html"
    },
    "version": "3.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
