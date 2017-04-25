# npmtest-mz

#### basic test coverage for  [mz (v2.6.0)](https://github.com/normalize/mz#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-mz.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mz) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mz.svg)](https://travis-ci.org/npmtest/node-npmtest-mz)

#### modernize node.js to current ECMAScript standards

[![NPM](https://nodei.co/npm/mz.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mz)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mz/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mz/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mz/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mz/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mz/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-mz/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-mz/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mz/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mz/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mz/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mz/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mz/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mz/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mz/build/test-report.html](https://npmtest.github.io/node-npmtest-mz/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mz/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mz/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mz/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mz/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mz/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mz/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mz/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mz/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Ong",
        "url": "http://jongleberry.com"
    },
    "bugs": {
        "url": "https://github.com/normalize/mz/issues"
    },
    "dependencies": {
        "any-promise": "^1.0.0",
        "object-assign": "^4.0.1",
        "thenify-all": "^1.0.0"
    },
    "description": "modernize node.js to current ECMAScript standards",
    "devDependencies": {
        "bluebird": "^3.0.0",
        "istanbul": "^0.4.0",
        "mocha": "^3.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "c8b8521d958df0a4f2768025db69c719ee4ef1ce",
        "tarball": "https://registry.npmjs.org/mz/-/mz-2.6.0.tgz"
    },
    "files": [
        "index.js",
        "child_process.js",
        "crypto.js",
        "dns.js",
        "fs.js",
        "readline.js",
        "zlib.js"
    ],
    "gitHead": "10bc91f7f0bb861cc940a078037be64cc166c144",
    "homepage": "https://github.com/normalize/mz#readme",
    "keywords": [
        "promisify",
        "promise",
        "thenify",
        "then",
        "es6"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "coderhaoxin"
        },
        {
            "name": "dead-horse"
        },
        {
            "name": "dead_horse"
        },
        {
            "name": "evancarroll"
        },
        {
            "name": "jongleberry"
        },
        {
            "name": "linusu"
        },
        {
            "name": "rstacruz"
        },
        {
            "name": "swatinem"
        }
    ],
    "name": "mz",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/normalize/mz.git"
    },
    "scripts": {
        "test": "mocha --reporter spec",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter dot"
    },
    "version": "2.6.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
