# test coverage for  [mz (v2.6.0)](https://github.com/normalize/mz#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-mz.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mz) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mz.svg)](https://travis-ci.org/npmtest/node-npmtest-mz)
#### modernize node.js to current ECMAScript standards

[![NPM](https://nodei.co/npm/mz.png?downloads=true)](https://www.npmjs.com/package/mz)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mz/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mz/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mz/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mz/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mz/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mz/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mz/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mz/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-mz/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-mz/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-mz%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mz/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mz/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-mz%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mz/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mz/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mz/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Ong",
        "email": "me@jongleberry.com",
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
            "name": "coderhaoxin",
            "email": "coderhaoxin@outlook.com"
        },
        {
            "name": "dead-horse",
            "email": "dead_horse@qq.com"
        },
        {
            "name": "dead_horse",
            "email": "dead_horse@qq.com"
        },
        {
            "name": "evancarroll",
            "email": "me@evancarroll.com"
        },
        {
            "name": "jongleberry",
            "email": "jonathanrichardong@gmail.com"
        },
        {
            "name": "linusu",
            "email": "linus@folkdatorn.se"
        },
        {
            "name": "rstacruz",
            "email": "dropbox@ricostacruz.com"
        },
        {
            "name": "swatinem",
            "email": "arpad.borsos@googlemail.com"
        }
    ],
    "name": "mz",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/normalize/mz.git"
    },
    "scripts": {
        "test": "mocha --reporter spec",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter dot"
    },
    "version": "2.6.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
