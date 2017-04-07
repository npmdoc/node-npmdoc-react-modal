# api documentation for  [react-modal (v1.7.3)](https://github.com/reactjs/react-modal)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-modal.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-modal) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-modal.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-modal)
#### Accessible modal dialog component for React.JS

[![NPM](https://nodei.co/npm/react-modal.png?downloads=true)](https://www.npmjs.com/package/react-modal)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-modal/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-react-modal_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-modal/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-modal/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-modal/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "Ryan Florence"
    ],
    "bugs": {
        "url": "https://github.com/reactjs/react-modal/issues"
    },
    "dependencies": {
        "element-class": "^0.2.0",
        "exenv": "1.2.0",
        "lodash.assign": "^4.2.0"
    },
    "description": "Accessible modal dialog component for React.JS",
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
    "directories": {
        "example": "examples"
    },
    "dist": {
        "shasum": "9745448f280c92290ab1ab05c3d34ae708ef9ab3",
        "tarball": "https://registry.npmjs.org/react-modal/-/react-modal-1.7.3.tgz"
    },
    "gitHead": "02a16ce3949d133d64b9f27c4705db6d130ed821",
    "homepage": "https://github.com/reactjs/react-modal",
    "keywords": [
        "react",
        "react-component",
        "modal",
        "dialog"
    ],
    "license": "MIT",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "claydiffrient",
            "email": "clay.diffrient@gmail.com"
        }
    ],
    "name": "react-modal",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0",
        "react-dom": "^0.14.0 || ^15.0.0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/reactjs/react-modal.git"
    },
    "scripts": {
        "docs": "npm-run-all docs:*",
        "docs-dev": "npm-run-all docs:clean docs:prepare docs:build:watch",
        "docs:build": "gitbook build -g reactjs/react-modal",
        "docs:build:watch": "gitbook serve",
        "docs:clean": "rimraf _book",
        "docs:prepare": "gitbook install",
        "docs:publish": "cd _book && git init && git commit --allow-empty -m 'update book' && git checkout -b gh-pages && touch .nojekyll && git add . && git commit -am 'update book' && git push git@github.com:reactjs/react-modal gh-pages --force",
        "start": "scripts/dev-examples",
        "test": "NODE_ENV=test karma start"
    },
    "tags": [
        "react",
        "modal",
        "dialog"
    ],
    "version": "1.7.3"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module react-modal](#apidoc.module.react-modal)
1.  [function <span class="apidocSignatureSpan">react-modal.</span>getDefaultProps ()](#apidoc.element.react-modal.getDefaultProps)
1.  [function <span class="apidocSignatureSpan">react-modal.</span>injectCSS ()](#apidoc.element.react-modal.injectCSS)
1.  [function <span class="apidocSignatureSpan">react-modal.</span>propTypes.appElement ()](#apidoc.element.react-modal.propTypes.appElement)
1.  [function <span class="apidocSignatureSpan">react-modal.</span>propTypes.ariaHideApp ()](#apidoc.element.react-modal.propTypes.ariaHideApp)
1.  [function <span class="apidocSignatureSpan">react-modal.</span>propTypes.closeTimeoutMS ()](#apidoc.element.react-modal.propTypes.closeTimeoutMS)
1.  [function <span class="apidocSignatureSpan">react-modal.</span>propTypes.onAfterOpen ()](#apidoc.element.react-modal.propTypes.onAfterOpen)
1.  [function <span class="apidocSignatureSpan">react-modal.</span>propTypes.portalClassName ()](#apidoc.element.react-modal.propTypes.portalClassName)
1.  [function <span class="apidocSignatureSpan">react-modal.</span>propTypes.style ()](#apidoc.element.react-modal.propTypes.style)
1.  [function <span class="apidocSignatureSpan">react-modal.</span>setAppElement (element)](#apidoc.element.react-modal.setAppElement)
1.  object <span class="apidocSignatureSpan">react-modal.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-modal.</span>defaultStyles
1.  object <span class="apidocSignatureSpan">react-modal.</span>propTypes
1.  string <span class="apidocSignatureSpan">react-modal.</span>displayName

#### [module react-modal.defaultProps](#apidoc.module.react-modal.defaultProps)
1.  boolean <span class="apidocSignatureSpan">react-modal.defaultProps.</span>ariaHideApp
1.  boolean <span class="apidocSignatureSpan">react-modal.defaultProps.</span>isOpen
1.  boolean <span class="apidocSignatureSpan">react-modal.defaultProps.</span>shouldCloseOnOverlayClick
1.  [function <span class="apidocSignatureSpan">react-modal.defaultProps.</span>parentSelector ()](#apidoc.element.react-modal.defaultProps.parentSelector)
1.  number <span class="apidocSignatureSpan">react-modal.defaultProps.</span>closeTimeoutMS
1.  string <span class="apidocSignatureSpan">react-modal.defaultProps.</span>portalClassName

#### [module react-modal.propTypes](#apidoc.module.react-modal.propTypes)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.</span>appElement ()](#apidoc.element.react-modal.propTypes.appElement)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.</span>ariaHideApp ()](#apidoc.element.react-modal.propTypes.ariaHideApp)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.</span>closeTimeoutMS ()](#apidoc.element.react-modal.propTypes.closeTimeoutMS)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.</span>contentLabel ()](#apidoc.element.react-modal.propTypes.contentLabel)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.</span>isOpen ()](#apidoc.element.react-modal.propTypes.isOpen)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.</span>onAfterOpen ()](#apidoc.element.react-modal.propTypes.onAfterOpen)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.</span>onRequestClose ()](#apidoc.element.react-modal.propTypes.onRequestClose)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.</span>parentSelector ()](#apidoc.element.react-modal.propTypes.parentSelector)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.</span>portalClassName ()](#apidoc.element.react-modal.propTypes.portalClassName)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.</span>role ()](#apidoc.element.react-modal.propTypes.role)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.</span>shouldCloseOnOverlayClick ()](#apidoc.element.react-modal.propTypes.shouldCloseOnOverlayClick)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.</span>style ()](#apidoc.element.react-modal.propTypes.style)

#### [module react-modal.propTypes.appElement](#apidoc.module.react-modal.propTypes.appElement)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.</span>appElement ()](#apidoc.element.react-modal.propTypes.appElement.appElement)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.appElement.</span>isRequired ()](#apidoc.element.react-modal.propTypes.appElement.isRequired)

#### [module react-modal.propTypes.ariaHideApp](#apidoc.module.react-modal.propTypes.ariaHideApp)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.</span>ariaHideApp ()](#apidoc.element.react-modal.propTypes.ariaHideApp.ariaHideApp)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.ariaHideApp.</span>isRequired ()](#apidoc.element.react-modal.propTypes.ariaHideApp.isRequired)

#### [module react-modal.propTypes.closeTimeoutMS](#apidoc.module.react-modal.propTypes.closeTimeoutMS)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.</span>closeTimeoutMS ()](#apidoc.element.react-modal.propTypes.closeTimeoutMS.closeTimeoutMS)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.closeTimeoutMS.</span>isRequired ()](#apidoc.element.react-modal.propTypes.closeTimeoutMS.isRequired)

#### [module react-modal.propTypes.onAfterOpen](#apidoc.module.react-modal.propTypes.onAfterOpen)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.</span>onAfterOpen ()](#apidoc.element.react-modal.propTypes.onAfterOpen.onAfterOpen)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.onAfterOpen.</span>isRequired ()](#apidoc.element.react-modal.propTypes.onAfterOpen.isRequired)

#### [module react-modal.propTypes.portalClassName](#apidoc.module.react-modal.propTypes.portalClassName)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.</span>portalClassName ()](#apidoc.element.react-modal.propTypes.portalClassName.portalClassName)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.portalClassName.</span>isRequired ()](#apidoc.element.react-modal.propTypes.portalClassName.isRequired)

#### [module react-modal.propTypes.style](#apidoc.module.react-modal.propTypes.style)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.</span>style ()](#apidoc.element.react-modal.propTypes.style.style)
1.  [function <span class="apidocSignatureSpan">react-modal.propTypes.style.</span>isRequired ()](#apidoc.element.react-modal.propTypes.style.isRequired)



# <a name="apidoc.module.react-modal"></a>[module react-modal](#apidoc.module.react-modal)

#### <a name="apidoc.element.react-modal.getDefaultProps"></a>[function <span class="apidocSignatureSpan">react-modal.</span>getDefaultProps ()](#apidoc.element.react-modal.getDefaultProps)
- description and source-code
```javascript
getDefaultProps = function () {
  return {
    isOpen: false,
    portalClassName: 'ReactModalPortal',
    ariaHideApp: true,
    closeTimeoutMS: 0,
    shouldCloseOnOverlayClick: true,
    parentSelector: function () { return document.body; }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.injectCSS"></a>[function <span class="apidocSignatureSpan">react-modal.</span>injectCSS ()](#apidoc.element.react-modal.injectCSS)
- description and source-code
```javascript
injectCSS = function () {
  "production" !== process.env.NODE_ENV
    && console.warn('React-Modal: injectCSS has been deprecated ' +
                    'and no longer has any effect. It will be removed in a later version');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.propTypes.appElement"></a>[function <span class="apidocSignatureSpan">react-modal.</span>propTypes.appElement ()](#apidoc.element.react-modal.propTypes.appElement)
- description and source-code
```javascript
propTypes.appElement = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.propTypes.ariaHideApp"></a>[function <span class="apidocSignatureSpan">react-modal.</span>propTypes.ariaHideApp ()](#apidoc.element.react-modal.propTypes.ariaHideApp)
- description and source-code
```javascript
propTypes.ariaHideApp = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.propTypes.closeTimeoutMS"></a>[function <span class="apidocSignatureSpan">react-modal.</span>propTypes.closeTimeoutMS ()](#apidoc.element.react-modal.propTypes.closeTimeoutMS)
- description and source-code
```javascript
propTypes.closeTimeoutMS = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.propTypes.onAfterOpen"></a>[function <span class="apidocSignatureSpan">react-modal.</span>propTypes.onAfterOpen ()](#apidoc.element.react-modal.propTypes.onAfterOpen)
- description and source-code
```javascript
propTypes.onAfterOpen = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.propTypes.portalClassName"></a>[function <span class="apidocSignatureSpan">react-modal.</span>propTypes.portalClassName ()](#apidoc.element.react-modal.propTypes.portalClassName)
- description and source-code
```javascript
propTypes.portalClassName = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.propTypes.style"></a>[function <span class="apidocSignatureSpan">react-modal.</span>propTypes.style ()](#apidoc.element.react-modal.propTypes.style)
- description and source-code
```javascript
propTypes.style = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.setAppElement"></a>[function <span class="apidocSignatureSpan">react-modal.</span>setAppElement (element)](#apidoc.element.react-modal.setAppElement)
- description and source-code
```javascript
setAppElement = function (element) {
    AppElement = ariaAppHider.setElement(element);
}
```
- example usage
```shell
...

/*
The app element allows you to specify the portion of your app that should be hidden (via aria-hidden)
to prevent assistive technologies such as screenreaders from reading content outside of the content of
your modal.  It can be specified in the following ways:

* element
Modal.setAppElement(appElement);

* query selector - uses the first element found if you pass in a class.
Modal.setAppElement('#your-app-element');

*/
var appElement = document.getElementById('your-app-element');
...
```



# <a name="apidoc.module.react-modal.defaultProps"></a>[module react-modal.defaultProps](#apidoc.module.react-modal.defaultProps)

#### <a name="apidoc.element.react-modal.defaultProps.parentSelector"></a>[function <span class="apidocSignatureSpan">react-modal.defaultProps.</span>parentSelector ()](#apidoc.element.react-modal.defaultProps.parentSelector)
- description and source-code
```javascript
parentSelector = function () { return document.body; }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-modal.propTypes"></a>[module react-modal.propTypes](#apidoc.module.react-modal.propTypes)

#### <a name="apidoc.element.react-modal.propTypes.appElement"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.</span>appElement ()](#apidoc.element.react-modal.propTypes.appElement)
- description and source-code
```javascript
appElement = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.propTypes.ariaHideApp"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.</span>ariaHideApp ()](#apidoc.element.react-modal.propTypes.ariaHideApp)
- description and source-code
```javascript
ariaHideApp = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.propTypes.closeTimeoutMS"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.</span>closeTimeoutMS ()](#apidoc.element.react-modal.propTypes.closeTimeoutMS)
- description and source-code
```javascript
closeTimeoutMS = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.propTypes.contentLabel"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.</span>contentLabel ()](#apidoc.element.react-modal.propTypes.contentLabel)
- description and source-code
```javascript
contentLabel = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.propTypes.isOpen"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.</span>isOpen ()](#apidoc.element.react-modal.propTypes.isOpen)
- description and source-code
```javascript
isOpen = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.propTypes.onAfterOpen"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.</span>onAfterOpen ()](#apidoc.element.react-modal.propTypes.onAfterOpen)
- description and source-code
```javascript
onAfterOpen = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.propTypes.onRequestClose"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.</span>onRequestClose ()](#apidoc.element.react-modal.propTypes.onRequestClose)
- description and source-code
```javascript
onRequestClose = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.propTypes.parentSelector"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.</span>parentSelector ()](#apidoc.element.react-modal.propTypes.parentSelector)
- description and source-code
```javascript
parentSelector = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.propTypes.portalClassName"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.</span>portalClassName ()](#apidoc.element.react-modal.propTypes.portalClassName)
- description and source-code
```javascript
portalClassName = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.propTypes.role"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.</span>role ()](#apidoc.element.react-modal.propTypes.role)
- description and source-code
```javascript
role = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.propTypes.shouldCloseOnOverlayClick"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.</span>shouldCloseOnOverlayClick ()](#apidoc.element.react-modal.propTypes.shouldCloseOnOverlayClick)
- description and source-code
```javascript
shouldCloseOnOverlayClick = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.propTypes.style"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.</span>style ()](#apidoc.element.react-modal.propTypes.style)
- description and source-code
```javascript
style = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-modal.propTypes.appElement"></a>[module react-modal.propTypes.appElement](#apidoc.module.react-modal.propTypes.appElement)

#### <a name="apidoc.element.react-modal.propTypes.appElement.appElement"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.</span>appElement ()](#apidoc.element.react-modal.propTypes.appElement.appElement)
- description and source-code
```javascript
appElement = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.propTypes.appElement.isRequired"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.appElement.</span>isRequired ()](#apidoc.element.react-modal.propTypes.appElement.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-modal.propTypes.ariaHideApp"></a>[module react-modal.propTypes.ariaHideApp](#apidoc.module.react-modal.propTypes.ariaHideApp)

#### <a name="apidoc.element.react-modal.propTypes.ariaHideApp.ariaHideApp"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.</span>ariaHideApp ()](#apidoc.element.react-modal.propTypes.ariaHideApp.ariaHideApp)
- description and source-code
```javascript
ariaHideApp = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.propTypes.ariaHideApp.isRequired"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.ariaHideApp.</span>isRequired ()](#apidoc.element.react-modal.propTypes.ariaHideApp.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-modal.propTypes.closeTimeoutMS"></a>[module react-modal.propTypes.closeTimeoutMS](#apidoc.module.react-modal.propTypes.closeTimeoutMS)

#### <a name="apidoc.element.react-modal.propTypes.closeTimeoutMS.closeTimeoutMS"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.</span>closeTimeoutMS ()](#apidoc.element.react-modal.propTypes.closeTimeoutMS.closeTimeoutMS)
- description and source-code
```javascript
closeTimeoutMS = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.propTypes.closeTimeoutMS.isRequired"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.closeTimeoutMS.</span>isRequired ()](#apidoc.element.react-modal.propTypes.closeTimeoutMS.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-modal.propTypes.onAfterOpen"></a>[module react-modal.propTypes.onAfterOpen](#apidoc.module.react-modal.propTypes.onAfterOpen)

#### <a name="apidoc.element.react-modal.propTypes.onAfterOpen.onAfterOpen"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.</span>onAfterOpen ()](#apidoc.element.react-modal.propTypes.onAfterOpen.onAfterOpen)
- description and source-code
```javascript
onAfterOpen = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.propTypes.onAfterOpen.isRequired"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.onAfterOpen.</span>isRequired ()](#apidoc.element.react-modal.propTypes.onAfterOpen.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-modal.propTypes.portalClassName"></a>[module react-modal.propTypes.portalClassName](#apidoc.module.react-modal.propTypes.portalClassName)

#### <a name="apidoc.element.react-modal.propTypes.portalClassName.portalClassName"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.</span>portalClassName ()](#apidoc.element.react-modal.propTypes.portalClassName.portalClassName)
- description and source-code
```javascript
portalClassName = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.propTypes.portalClassName.isRequired"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.portalClassName.</span>isRequired ()](#apidoc.element.react-modal.propTypes.portalClassName.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-modal.propTypes.style"></a>[module react-modal.propTypes.style](#apidoc.module.react-modal.propTypes.style)

#### <a name="apidoc.element.react-modal.propTypes.style.style"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.</span>style ()](#apidoc.element.react-modal.propTypes.style.style)
- description and source-code
```javascript
style = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-modal.propTypes.style.isRequired"></a>[function <span class="apidocSignatureSpan">react-modal.propTypes.style.</span>isRequired ()](#apidoc.element.react-modal.propTypes.style.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
