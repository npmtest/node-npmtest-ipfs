# npmtest-ipfs

#### basic test coverage for  [ipfs (v0.23.1)](https://github.com/ipfs/js-ipfs#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ipfs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ipfs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ipfs.svg)](https://travis-ci.org/npmtest/node-npmtest-ipfs)

#### JavaScript implementation of the IPFS specification

[![NPM](https://nodei.co/npm/ipfs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ipfs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ipfs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ipfs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ipfs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ipfs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ipfs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ipfs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ipfs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ipfs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ipfs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ipfs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ipfs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ipfs/build/test-report.html](https://npmtest.github.io/node-npmtest-ipfs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ipfs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ipfs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ipfs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ipfs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ipfs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ipfs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ipfs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ipfs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "David Dias"
    },
    "bin": {
        "jsipfs": "src/cli/bin.js"
    },
    "browser": {
        "libp2p-ipfs-nodejs": "libp2p-ipfs-browser",
        "./src/core/default-repo.js": "./src/core/default-repo-browser.js",
        "./src/core/components/init-assets.js": false,
        "./test/utils/create-repo-node.js": "./test/utils/create-repo-browser.js",
        "stream": "readable-stream"
    },
    "bugs": {
        "url": "https://github.com/ipfs/js-ipfs/issues"
    },
    "contributors": [
        {
            "name": "Andrew de Andrade"
        },
        {
            "name": "Caio Gondim"
        },
        {
            "name": "Christian Couder"
        },
        {
            "name": "Daniel J. O'Quinn"
        },
        {
            "name": "Daniela Borges Matos de Carvalho"
        },
        {
            "name": "David Dias"
        },
        {
            "name": "Felix Yan"
        },
        {
            "name": "Francisco Baio Dias"
        },
        {
            "name": "Francisco Baio Dias"
        },
        {
            "name": "Friedel Ziegelmayer"
        },
        {
            "name": "Greenkeeper"
        },
        {
            "name": "Haad"
        },
        {
            "name": "Harsh Vakharia"
        },
        {
            "name": "João Antunes"
        },
        {
            "name": "Lars Gierth"
        },
        {
            "name": "Mikeal Rogers"
        },
        {
            "name": "Mithgol"
        },
        {
            "name": "Nuno Nogueira"
        },
        {
            "name": "Oskar Nyberg"
        },
        {
            "name": "Pau Ramon Revilla"
        },
        {
            "name": "Pedro Teixeira"
        },
        {
            "name": "Richard Littauer"
        },
        {
            "name": "Sid Harder"
        },
        {
            "name": "SidHarder"
        },
        {
            "name": "Stephen Whitmore"
        },
        {
            "name": "Stephen Whitmore"
        },
        {
            "name": "Terence Pae"
        },
        {
            "name": "Xiao Liang"
        },
        {
            "name": "haad"
        },
        {
            "name": "jbenet"
        },
        {
            "name": "kumavis"
        },
        {
            "name": "nginnever"
        },
        {
            "name": "npmcdn-to-unpkg-bot"
        },
        {
            "name": "tcme"
        },
        {
            "name": "ᴠɪᴄᴛᴏʀ ʙᴊᴇʟᴋʜᴏʟᴍ"
        }
    ],
    "dependencies": {
        "async": "^2.2.0",
        "bl": "^1.2.0",
        "boom": "^4.3.0",
        "cids": "^0.4.2",
        "debug": "^2.6.3",
        "fsm-event": "^2.1.0",
        "glob": "^7.1.1",
        "hapi": "^16.1.0",
        "hapi-set-header": "^1.0.2",
        "hoek": "^4.1.0",
        "ipfs-api": "^13.0.0",
        "ipfs-bitswap": "~0.10.0",
        "ipfs-block": "~0.6.0",
        "ipfs-block-service": "~0.9.0",
        "ipfs-multipart": "~0.1.0",
        "ipfs-repo": "~0.13.0",
        "ipfs-unixfs": "~0.1.11",
        "ipfs-unixfs-engine": "~0.19.0",
        "ipld-resolver": "~0.11.0",
        "isstream": "^0.1.2",
        "joi": "^10.3.1",
        "libp2p-floodsub": "~0.7.5",
        "libp2p-ipfs-browser": "~0.20.1",
        "libp2p-ipfs-nodejs": "~0.20.1",
        "lodash.flatmap": "^4.5.0",
        "lodash.get": "^4.4.2",
        "lodash.has": "^4.5.2",
        "lodash.set": "^4.3.2",
        "lodash.sortby": "^4.7.0",
        "lodash.values": "^4.3.0",
        "mafmt": "^2.1.7",
        "mkdirp": "^0.5.1",
        "multiaddr": "^2.2.3",
        "multihashes": "~0.4.5",
        "once": "^1.4.0",
        "path-exists": "^3.0.0",
        "peer-book": "~0.3.1",
        "peer-id": "~0.8.4",
        "peer-info": "~0.8.4",
        "promisify-es6": "^1.0.2",
        "pull-file": "^1.0.0",
        "pull-paramap": "^1.2.1",
        "pull-pushable": "^2.0.1",
        "pull-sort": "^1.0.0",
        "pull-stream": "^3.5.0",
        "pull-stream-to-stream": "^1.3.4",
        "pull-zip": "^2.0.1",
        "read-pkg-up": "^2.0.0",
        "readable-stream": "1.1.14",
        "safe-buffer": "^5.0.1",
        "stream-to-pull-stream": "^1.7.2",
        "tar-stream": "^1.5.2",
        "temp": "^0.8.3",
        "through2": "^2.0.3",
        "update-notifier": "^2.1.0",
        "yargs": "7.0.2"
    },
    "description": "JavaScript implementation of the IPFS specification",
    "devDependencies": {
        "aegir": "^11.0.1",
        "buffer-loader": "0.0.1",
        "chai": "^3.5.0",
        "delay": "^2.0.0",
        "detect-node": "^2.0.3",
        "dir-compare": "^1.3.0",
        "dirty-chai": "^1.2.2",
        "eslint-plugin-react": "^6.10.3",
        "execa": "^0.6.3",
        "expose-loader": "^0.7.3",
        "form-data": "^2.1.2",
        "gulp": "^3.9.1",
        "interface-ipfs-core": "~0.26.1",
        "ipfsd-ctl": "~0.20.0",
        "left-pad": "^1.1.3",
        "lodash": "^4.17.4",
        "mocha": "^3.2.0",
        "ncp": "^2.0.0",
        "nexpect": "^0.5.0",
        "pre-commit": "^1.2.2",
        "pretty-bytes": "^4.0.2",
        "qs": "^6.4.0",
        "random-fs": "^1.0.3",
        "rimraf": "^2.6.1",
        "stream-to-promise": "^2.2.0",
        "transform-loader": "^0.2.4"
    },
    "directories": {},
    "dist": {
        "shasum": "4a5f1b8683a94414a2fbaece72bf1ab75d0b9ac5",
        "tarball": "https://registry.npmjs.org/ipfs/-/ipfs-0.23.1.tgz"
    },
    "engines": {
        "node": ">=4.0.0",
        "npm": ">=3.0.0"
    },
    "gitHead": "670662e8f81a843b10575de367d2716f2029222f",
    "go-ipfs": {
        "version": "v0.4.7"
    },
    "homepage": "https://github.com/ipfs/js-ipfs#readme",
    "keywords": [
        "IPFS"
    ],
    "license": "MIT",
    "main": "src/core/index.js",
    "maintainers": [
        {
            "name": "daviddias"
        },
        {
            "name": "jbenet"
        }
    ],
    "name": "ipfs",
    "optionalDependencies": {},
    "pre-commit": [
        "lint",
        "test"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ipfs/js-ipfs.git"
    },
    "scripts": {
        "build": "gulp build",
        "coverage": "gulp coverage",
        "coverage-publish": "aegir-coverage publish",
        "lint": "aegir-lint",
        "release": "gulp release --dom",
        "release-major": "gulp release --type major --dom",
        "release-minor": "gulp release --type minor --dom",
        "test": "gulp test --dom",
        "test:benchmark": "echo \"Error: no benchmarks yet\" && exit 1",
        "test:benchmark:browser": "echo \"Error: no benchmarks yet\" && exit 1",
        "test:benchmark:node": "echo \"Error: no benchmarks yet\" && exit 1",
        "test:benchmark:node:core": "echo \"Error: no benchmarks yet\" && exit 1",
        "test:benchmark:node:http": "echo \"Error: no benchmarks yet\" && exit 1",
        "test:browser": "npm run test:unit:browser --dom",
        "test:interop": "mocha -t 60000 test/interop",
        "test:interop:browser": "mocha test/interop/browser.js",
        "test:interop:node": "mocha -t 60000 test/interop/node.js",
        "test:node": "npm run test:unit:node",
        "test:unit:browser": "gulp test:browser --dom",
        "test:unit:node": "gulp test:node",
        "test:unit:node:cli": "TEST=cli npm run test:unit:node",
        "test:unit:node:core": "TEST=core npm run test:unit:node",
        "test:unit:node:http": "TEST=http npm run test:unit:node"
    },
    "version": "0.23.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
