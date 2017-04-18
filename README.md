# api documentation for  [publish (v0.6.0)](https://github.com/cmanzana/node-publish)  [![npm package](https://img.shields.io/npm/v/npmdoc-publish.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-publish) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-publish.svg)](https://travis-ci.org/npmdoc/node-npmdoc-publish)
#### npm auto publishing of your modules

[![NPM](https://nodei.co/npm/publish.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/publish)

- [https://npmdoc.github.io/node-npmdoc-publish/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-publish/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-publish/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-publish/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-publish/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-publish/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "publish",
    "version": "0.6.0",
    "description": "npm auto publishing of your modules",
    "main": "index.js",
    "homepage": "https://github.com/cmanzana/node-publish",
    "bin": {
        "publish": "./bin/publish.js"
    },
    "scripts": {
        "test": "mocha --globals name"
    },
    "dependencies": {
        "npm": "2.x.x",
        "npmlog": "1.x.x",
        "semver": "4.x.x",
        "nopt": "3.x.x"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/cmanzana/node-publish.git"
    },
    "keywords": [
        "npm",
        "publish",
        "deploy",
        "CI"
    ],
    "devDependencies": {
        "mocha": "^2.4.5"
    },
    "author": {
        "name": "Carlos Manzanares"
    },
    "license": "MIT",
    "gitHead": "cffdab28fb1b813b2076fe5c8c7ff96d037be677",
    "bugs": {
        "url": "https://github.com/cmanzana/node-publish/issues"
    },
    "maintainers": [
        {
            "name": "cmanzana"
        }
    ],
    "dist": {
        "shasum": "ca124c8b9603ee1c7f739f35c12fcefbc3776f68",
        "tarball": "https://registry.npmjs.org/publish/-/publish-0.6.0.tgz"
    },
    "directories": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
