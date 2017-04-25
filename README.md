# npmtest-npm-scripts-watcher

#### basic test coverage for  [npm-scripts-watcher (v1.0.2)](https://github.com/wehkamp/npm-scripts-watcher#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-npm-scripts-watcher.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-npm-scripts-watcher) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-npm-scripts-watcher.svg)](https://travis-ci.org/npmtest/node-npmtest-npm-scripts-watcher)

#### Globbing file watcher to automatically run npm scripts from package.json when files change, with pretty colors.

[![NPM](https://nodei.co/npm/npm-scripts-watcher.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npm-scripts-watcher)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-npm-scripts-watcher/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-scripts-watcher/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-npm-scripts-watcher/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-npm-scripts-watcher/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-npm-scripts-watcher/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-npm-scripts-watcher/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-npm-scripts-watcher/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-npm-scripts-watcher/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-npm-scripts-watcher/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-npm-scripts-watcher/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-npm-scripts-watcher/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-scripts-watcher/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-npm-scripts-watcher/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-npm-scripts-watcher/build/test-report.html](https://npmtest.github.io/node-npmtest-npm-scripts-watcher/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-npm-scripts-watcher/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-npm-scripts-watcher/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-npm-scripts-watcher/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npm-scripts-watcher/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm-scripts-watcher/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm-scripts-watcher/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-npm-scripts-watcher/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-npm-scripts-watcher/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gert Hengeveld",
        "url": "https://github.com/ghengeveld"
    },
    "bin": {
        "npm-scripts-watcher": "lib/watcher.js"
    },
    "bugs": {
        "url": "https://github.com/wehkamp/npm-scripts-watcher/issues"
    },
    "dependencies": {
        "colors": "^1.1.2",
        "debounce": "^1.0.0",
        "glob": "^6.0.1",
        "node-watch": "^0.3.4",
        "shelljs": "^0.5.3"
    },
    "description": "Globbing file watcher to automatically run npm scripts from package.json when files change, with pretty colors.",
    "devDependencies": {
        "babel-cli": "^6.2.0",
        "babel-preset-es2015": "^6.1.18"
    },
    "directories": {},
    "dist": {
        "shasum": "cb9d84a1037fb2f1e38d9813543f8eec9ec6025f",
        "tarball": "https://registry.npmjs.org/npm-scripts-watcher/-/npm-scripts-watcher-1.0.2.tgz"
    },
    "gitHead": "3bd534044acf926c4fc9ae31ef5a29d6dae1a0af",
    "homepage": "https://github.com/wehkamp/npm-scripts-watcher#readme",
    "keywords": [
        "npm",
        "scripts",
        "file",
        "watch",
        "watcher"
    ],
    "license": "Apache-2.0",
    "main": "lib/watcher.js",
    "maintainers": [
        {
            "name": "ghengeveld"
        }
    ],
    "name": "npm-scripts-watcher",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/wehkamp/npm-scripts-watcher.git"
    },
    "scripts": {
        "build": "babel -d lib src",
        "prepublish": "npm run build"
    },
    "version": "1.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
