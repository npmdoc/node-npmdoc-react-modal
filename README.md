# npmdoc-react-modal

#### api documentation for  [react-modal (v1.7.7)](https://github.com/reactjs/react-modal)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-modal.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-modal) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-modal.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-modal)

#### Accessible modal dialog component for React.JS

[![NPM](https://nodei.co/npm/react-modal.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-modal)

- [https://npmdoc.github.io/node-npmdoc-react-modal/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-modal/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-modal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-modal/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-modal/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-modal/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-modal",
    "version": "1.7.7",
    "description": "Accessible modal dialog component for React.JS",
    "main": "./lib/index.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/reactjs/react-modal.git"
    },
    "homepage": "https://github.com/reactjs/react-modal",
    "bugs": "https://github.com/reactjs/react-modal/issues",
    "directories": {
        "example": "examples"
    },
    "scripts": {
        "test": "NODE_ENV=test karma start",
        "start": "scripts/dev-examples",
        "docs": "npm-run-all docs:*",
        "docs-dev": "npm-run-all docs:clean docs:prepare docs:build:watch",
        "docs:clean": "rimraf _book",
        "docs:prepare": "gitbook install",
        "docs:build": "gitbook build -g reactjs/react-modal",
        "docs:build:watch": "gitbook serve",
        "docs:publish": "cd _book && git init && git commit --allow-empty -m 'update book' && git checkout -b gh-pages && touch .nojekyll && git add . && git commit -am 'update book' && git push git@github.com:reactjs/react-modal gh-pages --force"
    },
    "authors": [
        "Ryan Florence"
    ],
    "license": "MIT",
    "devDependencies": {
        "babel-core": "^6.7.4",
        "babel-loader": "^6.2.4",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-react": "^6.5.0",
        "envify": "^3.4.1",
        "expect": "^1.20.2",
        "gitbook-cli": "^2.3.0",
        "karma": "^1.3.0",
        "karma-chrome-launcher": "2.0.0",
        "karma-cli": "1.0.1",
        "karma-firefox-launcher": "1.0.0",
        "karma-mocha": "^1.3.0",
        "karma-mocha-reporter": "^2.2.1",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-webpack": "^1.8.1",
        "mocha": "3.2.0",
        "npm-run-all": "^3.1.2",
        "react": "^15.0.0",
        "react-addons-test-utils": "^15.0.0",
        "react-dom": "^15.0.0",
        "rf-release": "0.4.0",
        "rimraf": "^2.5.4",
        "sinon": "next",
        "uglify-js": "2.4.24",
        "webpack": "^1.12.14",
        "webpack-dev-server": "1.11.0"
    },
    "dependencies": {
        "create-react-class": "^15.5.2",
        "element-class": "^0.2.0",
        "exenv": "1.2.0",
        "lodash.assign": "^4.2.0",
        "prop-types": "^15.5.7"
    },
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0",
        "react-dom": "^0.14.0 || ^15.0.0"
    },
    "tags": [
        "react",
        "modal",
        "dialog"
    ],
    "keywords": [
        "react",
        "react-component",
        "modal",
        "dialog"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
