# npmtest-async

#### basic test coverage for  [async (2.6.1)](https://caolan.github.io/async/)  [![npm package](https://img.shields.io/npm/v/npmtest-async.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-async) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-async.svg)](https://travis-ci.org/npmtest/node-npmtest-async)

#### Higher-order functions and common patterns for asynchronous code

[![NPM](https://nodei.co/npm/async.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/async)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-async/tree/alpha)|
|--:|:--|
| coverage : | [![coverage](https://npmtest.github.io/node-npmtest-async/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-async/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-async/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-async/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-async/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-async/build/app) || build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-async/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-async/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-async/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-async/build/coverage.html/index.html)

[![coverage](https://npmtest.github.io/node-npmtest-async/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-async/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-async/build/test-report.html](https://npmtest.github.io/node-npmtest-async/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-async/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-async/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-async/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-async/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-async/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-async/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-async/build/screenshot.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-async/build/screenshot.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Caolan McMahon"
    },
    "bugs": {
        "url": "https://github.com/caolan/async/issues"
    },
    "dependencies": {
        "lodash": "^4.17.10"
    },
    "description": "Higher-order functions and common patterns for asynchronous code",
    "devDependencies": {
        "babel-cli": "^6.24.0",
        "babel-core": "^6.26.3",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-istanbul": "^2.0.1",
        "babel-plugin-transform-es2015-modules-commonjs": "^6.26.2",
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-es2017": "^6.22.0",
        "babelify": "^8.0.0",
        "benchmark": "^2.1.1",
        "bluebird": "^3.4.6",
        "browserify": "^16.2.2",
        "chai": "^4.1.2",
        "cheerio": "^0.22.0",
        "coveralls": "^3.0.1",
        "es6-promise": "^2.3.0",
        "eslint": "^2.13.1",
        "fs-extra": "^0.26.7",
        "gh-pages-deploy": "^0.5.0",
        "jsdoc": "^3.4.0",
        "karma": "^2.0.2",
        "karma-browserify": "^5.2.0",
        "karma-firefox-launcher": "^1.1.0",
        "karma-mocha": "^1.2.0",
        "karma-mocha-reporter": "^2.2.0",
        "mocha": "^5.2.0",
        "native-promise-only": "^0.8.0-a",
        "nyc": "^11.8.0",
        "rimraf": "^2.5.0",
        "rollup": "^0.36.3",
        "rollup-plugin-node-resolve": "^2.0.0",
        "rollup-plugin-npm": "^2.0.0",
        "rsvp": "^3.0.18",
        "semver": "^5.5.0",
        "uglify-js": "~2.7.3",
        "yargs": "^11.0.0"
    },
    "directories": {},
    "dist": {
        "integrity": "sha512-fNEiL2+AZt6AlAw/29Cr0UDe4sRAHCpEHh54WMz+Bb7QfNcFw4h3loofyJpLeQs4Yx7yuqu/2dLgM5hKOs6HlQ==",
        "shasum": "b245a23ca71930044ec53fa46aa00a3e87c6a610",
        "tarball": "https://registry.npmjs.org/async/-/async-2.6.1.tgz",
        "fileCount": 133,
        "unpackedSize": 540920,
        "npm-signature": "-----BEGIN PGP SIGNATURE-----\r\nVersion: OpenPGP.js v3.0.4\r\nComment: https://openpgpjs.org\r\n\r\nwsFcBAEBCAAQBQJbAkxWCRA9TVsSAnZWagAAMogQAJxPRPcF4lY8dlEv78Vm\nrE88f6xFuMnVUgJunHn43+mYg36DDYpKB5VQ3jaHjAaK1WHJYepuPzQSIRFr\ndNgRs62K6s5zC+q07rbv7KyrYOKfHpLOC+PGtpRcKEuMVTQ5lzps6cYYZu5x\njtjmYcTI3t0EuJpaTZgVygtQ8iyvXFBJyt1zzqMAsRRxQx4A8VvytLw96Arl\n97x1BirrYsaamseE0AcoCpOKnSBM5AGiO4A/SeTNFWbPx7eM8Pf2rEgV5ohz\n2z5bjj6zOWpL8jyFMPBblRE82YXeMvEp14tgaruLrb15+xE7QapfjZuk6AQZ\n+DofFTGQSdHk4PZKx7OhUZTNiWbbVvBxtLBAOeStod3BP7C+dCTsFre0R8Yu\nmgrQ+l94TGSBc1xK8uqyHtBT61UGly0v85eVfe3MXT8YsAWY0MiMEsuJVz8d\n9QCjecg21j3oyJAe6F05OMaRZe7yJdgalCO9sq/W42ZztIwqDGS+GbNTRFiu\nDfZh13rSqZIakyYoBXQTXzhaCeDrsJKblYlC+kCkbo71P9M2xBsDFnUF7byC\nLWMo4xC0xUypHFdOi2lVF+FvpLTld8OPXGZOjSlX82LI93jhciNYxeydxL1T\nbr0OJDiW09zNJR7H0ISNwcJK2tPqdmw6C8aMSzNYQnuCVX0MVhaWvhiJ7IlD\nHEkH\r\n=4QoQ\r\n-----END PGP SIGNATURE-----\r\n"
    },
    "gh-pages-deploy": {
        "staticpath": "docs"
    },
    "homepage": "https://caolan.github.io/async/",
    "keywords": [
        "async",
        "callback",
        "module",
        "utility"
    ],
    "license": "MIT",
    "main": "dist/async.js",
    "maintainers": [
        {
            "name": "aearly"
        },
        {
            "name": "beaugunderson"
        },
        {
            "name": "caolan"
        },
        {
            "name": "hargasinski"
        },
        {
            "name": "megawac"
        }
    ],
    "name": "async",
    "nyc": {
        "exclude": [
            "mocha_test"
        ]
    },
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/caolan/async.git"
    },
    "scripts": {
        "coverage": "nyc npm run mocha-node-test -- --grep @nycinvalid --invert",
        "coveralls": "npm run coverage && nyc report --reporter=text-lcov | coveralls",
        "jsdoc": "jsdoc -c ./support/jsdoc/jsdoc.json && node support/jsdoc/jsdoc-fix-html.js",
        "lint": "eslint lib/ mocha_test/ perf/memory.js perf/suites.js perf/benchmark.js support/build/ support/*.js karma.conf.js",
        "mocha-browser-test": "karma start",
        "mocha-node-test": "mocha mocha_test/ --compilers js:babel-core/register",
        "mocha-test": "npm run mocha-node-test && npm run mocha-browser-test",
        "test": "npm run lint && npm run mocha-node-test"
    },
    "version": "2.6.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
