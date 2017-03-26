# api documentation for  [gulp-useref (v3.1.2)](https://github.com/jonkemp/gulp-useref#readme)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-useref.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-useref)
#### Parse build blocks in HTML files to replace references to non-optimized scripts or stylesheets.

[![NPM](https://nodei.co/npm/gulp-useref.png?downloads=true)](https://www.npmjs.com/package/gulp-useref)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-useref/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-gulp-useref_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-useref/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-gulp-useref/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Kemp",
        "email": "kempdogg@gmail.com",
        "url": "http://jonkemp.com/"
    },
    "bugs": {
        "url": "https://github.com/jonkemp/gulp-useref/issues"
    },
    "dependencies": {
        "event-stream": "^3.3.1",
        "glob": "^7.0.3",
        "gulp-concat": "^2.5.2",
        "gulp-if": "^2.0.0",
        "gulp-util": "^3.0.1",
        "is-relative-url": "1.0.0",
        "through2": "^2.0.1",
        "useref": "^1.2.0",
        "vinyl-fs": "^2.2.1"
    },
    "description": "Parse build blocks in HTML files to replace references to non-optimized scripts or stylesheets.",
    "devDependencies": {
        "coveralls": "^2.11.4",
        "gulp": "^3.9.0",
        "gulp-eslint": "^3.0.1",
        "gulp-mocha": "^3.0.1",
        "gulp-rename": "^1.2.2",
        "mocha": "*",
        "mock-gulp-dest": "^0.1.1",
        "nyc": "^8.1.0",
        "should": "*"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "dec67024a96e685eeb9d9d8153c64a5d5c5e3cf6",
        "tarball": "https://registry.npmjs.org/gulp-useref/-/gulp-useref-3.1.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js",
        "lib"
    ],
    "gitHead": "1ce8e74945d0609409d08a9ead689fb178f1ed39",
    "homepage": "https://github.com/jonkemp/gulp-useref#readme",
    "keywords": [
        "gulpplugin",
        "html",
        "scripts",
        "css",
        "optimize",
        "concat"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jonkemp",
            "email": "kempdogg@gmail.com"
        }
    ],
    "name": "gulp-useref",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jonkemp/gulp-useref.git"
    },
    "scripts": {
        "coverage": "nyc npm test && nyc report",
        "coveralls": "nyc npm test && nyc report --reporter=text-lcov | coveralls",
        "lint": "gulp lint",
        "test": "mocha"
    },
    "version": "3.1.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module gulp-useref](#apidoc.module.gulp-useref)



# <a name="apidoc.module.gulp-useref"></a>[module gulp-useref](#apidoc.module.gulp-useref)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
