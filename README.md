# npmdoc-node-powershell

#### basic api documentation for  [node-powershell (v3.1.1)](http://rannn505.github.io/node-powershell/)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-powershell.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-powershell) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-powershell.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-powershell)

#### Easily run PowerShell from your NodeJS app

[![NPM](https://nodei.co/npm/node-powershell.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-powershell)

- [https://npmdoc.github.io/node-npmdoc-node-powershell/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-powershell/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-powershell/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-powershell/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-powershell/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-powershell/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ran Cohen"
    },
    "bugs": {
        "url": "https://github.com/rannn505/node-powershell/issues"
    },
    "dependencies": {
        "bluebird": "^3.4.7",
        "chalk": "^1.1.3"
    },
    "description": "Easily run PowerShell from your NodeJS app",
    "devDependencies": {
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-preset-es2015": "^6.22.0",
        "chai": "^3.5.0",
        "chai-as-promised": "^6.0.0",
        "coveralls": "^2.11.16",
        "gulp": "^3.9.1",
        "gulp-babel": "^6.1.2",
        "gulp-clean": "^0.3.2",
        "gulp-header": "^1.8.8",
        "istanbul": "^0.4.5",
        "mocha": "^3.2.0",
        "mocha-lcov-reporter": "^1.3.0"
    },
    "directories": {
        "example": "example"
    },
    "dist": {
        "shasum": "f3da688a5d3c80883dec87b2c71b3ee362cf40e2",
        "tarball": "https://registry.npmjs.org/node-powershell/-/node-powershell-3.1.1.tgz"
    },
    "files": [
        "dist",
        "example",
        "test"
    ],
    "gitHead": "65e151aa9152c3364f438e579a78808019e23414",
    "homepage": "http://rannn505.github.io/node-powershell/",
    "keywords": [
        "node-powershell",
        "ps",
        "powershell",
        "node-ps",
        "microsoft",
        "shell",
        "cmd",
        "commandline",
        "command",
        "Line",
        "windows",
        "windows powershell",
        "script",
        "spwan",
        "shells",
        "terminal",
        "linux powershell",
        "powershell github",
        "PowerShell for every system",
        "PowerShell cross-platform",
        "powershell linux",
        "powershell centos",
        "powershell rhel",
        "powershell ubuntu",
        "powershell macos",
        "powershell docker"
    ],
    "license": "MIT",
    "main": "./dist/index.js",
    "maintainers": [
        {
            "name": "rannn505"
        }
    ],
    "name": "node-powershell",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/rannn505/node-powershell.git"
    },
    "scripts": {
        "build": "gulp",
        "dev": "gulp watch",
        "patch": "npm version minor -m \"Release version %s\"",
        "postversion": "git push && git push --tags",
        "start": "cd ./example && node example.js",
        "test": "istanbul cover ./node_modules/mocha/bin/_mocha",
        "test:coveralls": "istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "version": "npm run build && git add -A"
    },
    "version": "3.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
