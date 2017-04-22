# npmdoc-react-native-style-tachyons

#### api documentation for  [react-native-style-tachyons (v3.3.2)](https://github.com/tachyons-css/react-native-style-tachyons)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-native-style-tachyons.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-native-style-tachyons) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-native-style-tachyons.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-native-style-tachyons)

#### functional, maintainable styling for react-native

[![NPM](https://nodei.co/npm/react-native-style-tachyons.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-native-style-tachyons)

- [https://npmdoc.github.io/node-npmdoc-react-native-style-tachyons/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-native-style-tachyons/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-native-style-tachyons/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-native-style-tachyons/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-native-style-tachyons/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-native-style-tachyons/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-native-style-tachyons",
    "description": "functional, maintainable styling for react-native",
    "license": "MIT",
    "version": "3.3.2",
    "keywords": [
        "react",
        "react-native",
        "android",
        "ios",
        "StyleSheet",
        "style",
        "responsive",
        "mobile",
        "performance",
        "design",
        "css"
    ],
    "author": {
        "name": "Fabian Zeindl",
        "url": "http://github.com/fab1an"
    },
    "homepage": "https://github.com/tachyons-css/react-native-style-tachyons",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/tachyons-css/react-native-style-tachyons.git"
    },
    "bugs": {
        "url": "https://github.com/tachyons-css/react-native-style-tachyons/issues"
    },
    "main": "lib/index.js",
    "dependencies": {
        "color": "^1.0.3",
        "css-color-names": "0.0.4",
        "debug": "^2.6.3",
        "lodash": "^4.17.4"
    },
    "files": [
        "lib/"
    ],
    "devDependencies": {
        "babel-cli": "^6.24.0",
        "babel-eslint": "^7.2.1",
        "babel-preset-es2015": "^6.24.0",
        "babel-preset-react": "^6.22.0",
        "benchmark": "^2.1.3",
        "eslint": "^3.18.0",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-react": "^6.10.3",
        "eslint_d": "^4.2.4",
        "faucet": "0.0.1",
        "publish-please": "^2.3.0",
        "react": "^15.4.2",
        "tape": "^4.6.3"
    },
    "peerDependencies": {
        "react-native": "0.x"
    },
    "scripts": {
        "build": "rm -Rf lib && babel src -d lib",
        "_test": "tape -r babel-register 'test/**/*_spec.js' | faucet",
        "lint": "eslint_d --fix src test",
        "test": "npm run lint && npm run build && npm run _test",
        "publish-please": "publish-please",
        "prepublish": "publish-please guard"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
