# npmtest-db-migrate

#### test coverage for  [db-migrate (v0.9.26)](https://github.com/kunklejr/node-db-migrate#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-db-migrate.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-db-migrate) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-db-migrate.svg)](https://travis-ci.org/npmtest/node-npmtest-db-migrate)

#### Database migration framework for node.js

[![NPM](https://nodei.co/npm/db-migrate.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/db-migrate)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-db-migrate/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-db-migrate/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-db-migrate/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-db-migrate/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-db-migrate/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-db-migrate/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-db-migrate/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-db-migrate/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-db-migrate/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-db-migrate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-db-migrate/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-db-migrate/build/test-report.html](https://npmtest.github.io/node-npmtest-db-migrate/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-db-migrate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-db-migrate/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-db-migrate/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-db-migrate/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-db-migrate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-db-migrate/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-db-migrate/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-db-migrate/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jeff Kunkle"
    },
    "bin": {
        "db-migrate": "./bin/db-migrate"
    },
    "bugs": {
        "url": "https://github.com/kunklejr/node-db-migrate/issues"
    },
    "dependencies": {
        "async": "~0.9.0",
        "dotenv": "~0.5.1",
        "final-fs": "^1.6.0",
        "mkdirp": "~0.5.0",
        "moment": "~2.9.0",
        "mongodb": "^1.4.30",
        "mysql": "^2.10.2",
        "optimist": "~0.6.1",
        "parse-database-url": "~0.2.2",
        "pg": "^4.5.5",
        "pkginfo": "~0.3.0",
        "semver": "~4.3.3",
        "sqlite3": "^3.1.4"
    },
    "description": "Database migration framework for node.js",
    "devDependencies": {
        "code": "^1.3.0",
        "db-meta": "~0.4.1",
        "lab": "^5.2.1",
        "rimraf": "~2.2.8",
        "vows": "0.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f523e1e6d3a168587e2fddec74b0e41ea3f9794b",
        "tarball": "https://registry.npmjs.org/db-migrate/-/db-migrate-0.9.26.tgz"
    },
    "engines": {
        "node": ">=0.6.0"
    },
    "gitHead": "f34f43d515c804a5412e364fad6820a5851e8a88",
    "homepage": "https://github.com/kunklejr/node-db-migrate#readme",
    "keywords": [
        "database",
        "db",
        "migrate",
        "migration",
        "sqlite",
        "mysql"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "kunklejr"
        },
        {
            "name": "wzrdtales"
        }
    ],
    "name": "db-migrate",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kunklejr/node-db-migrate.git"
    },
    "scripts": {
        "test": "node node_modules/.bin/vows"
    },
    "version": "0.9.26"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
