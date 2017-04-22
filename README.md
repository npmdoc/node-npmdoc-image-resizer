# npmdoc-image-resizer

#### api documentation for  image-resizer (v1.3.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-image-resizer.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-image-resizer) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-image-resizer.svg)](https://travis-ci.org/npmdoc/node-npmdoc-image-resizer)

#### On-the-fly image resizing and optimization using node and sharp (libvips). Heroku ready!

[![NPM](https://nodei.co/npm/image-resizer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/image-resizer)

- [https://npmdoc.github.io/node-npmdoc-image-resizer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-image-resizer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-image-resizer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-image-resizer/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-image-resizer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-image-resizer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "image-resizer",
    "version": "1.3.0",
    "description": "On-the-fly image resizing and optimization using node and sharp (libvips). Heroku ready!",
    "main": "index.js",
    "scripts": {
        "test": "gulp test"
    },
    "keywords": [
        "image",
        "resize",
        "node",
        "sharp",
        "libvips",
        "heroku",
        "optimization"
    ],
    "author": "James Nicol <james.andrew.nicol@gmail.com> (https://github.com/jimmynicol)",
    "license": "MIT",
    "repository": "git://github.com/jimmynicol/image-resizer",
    "bin": {
        "image-resizer": "./bin/image_resizer.js"
    },
    "engines": {
        "node": "0.12.x"
    },
    "dependencies": {
        "aws-sdk": "~2.0.0-rc9",
        "chalk": "~1.0.0",
        "commander": "^2.2.0",
        "concat-stream": "~1.4.5",
        "errorhandler": "^1.0.1",
        "express": "^4.9.7",
        "glob": "~3.2.9",
        "image-type": "^2.0.2",
        "lodash": "~2.4.1",
        "map-stream": "~0.1.0",
        "mkdirp": "^0.5.0",
        "morgan": "^1.0.1",
        "request": "~2.34.0",
        "sharp": "^0.11.3",
        "twit": "~1.1.15"
    },
    "devDependencies": {
        "chai": "~1.9.0",
        "connect-livereload": "~0.3.2",
        "dotenv": "~0.2.8",
        "ejs": "~1.0.0",
        "gulp": "^3.8.10",
        "gulp-bump": "^0.1.8",
        "gulp-jshint": "~1.4.2",
        "gulp-mocha": "~0.4.1",
        "gulp-nodemon": "~1.0.0",
        "gulp-util": "~2.2.14",
        "jshint-stylish": "~0.1.5",
        "sandboxed-module": "^1.0.0",
        "sinon": "~1.8.2",
        "sinon-chai": "~2.5.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
