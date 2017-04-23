# npmtest-react-native-css

#### basic test coverage for  [react-native-css (v2.0.4)](https://github.com/sabeurthabti/react-native-css)  [![npm package](https://img.shields.io/npm/v/npmtest-react-native-css.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-native-css) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-native-css.svg)](https://travis-ci.org/npmtest/node-npmtest-react-native-css)

#### Style React-Native components with css

[![NPM](https://nodei.co/npm/react-native-css.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-native-css)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-native-css/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-native-css/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-native-css/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-native-css/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-native-css/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-native-css/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-native-css/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-native-css/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-native-css/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-native-css/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-native-css/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-native-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-native-css/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-native-css/build/test-report.html](https://npmtest.github.io/node-npmtest-react-native-css/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-native-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-native-css/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-native-css/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-native-css/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-native-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-native-css/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-native-css/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-native-css/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-native-css",
    "version": "2.0.4",
    "description": "Style React-Native components with css",
    "main": "build/index.js",
    "scripts": {
        "start": "babel src --out-dir build",
        "prepublish": "npm run start",
        "test": "babel-tap test/*.test.js",
        "lint": "eslint . --ext .js",
        "lint:fix": "npm run lint -- --fix",
        "echo": "echo 'hello'"
    },
    "author": "Sabeur Thabti",
    "license": "MIT",
    "dependencies": {
        "css": "^2.2.1",
        "lodash.get": "^4.4.2",
        "lodash.set": "^4.3.2",
        "pre-commit": "^1.2.2",
        "to-camel-case": "~0.2.0"
    },
    "devDependencies": {
        "babel-cli": "^6.24.0",
        "babel-eslint": "^7.1.1",
        "babel-plugin-transform-object-rest-spread": "^6.23.0",
        "babel-preset-es2015": "^6.24.0",
        "babel-tap": "^5.0.0",
        "eslint": "^3.17.1",
        "eslint-config-airbnb": "^14.1.0",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-jsx-a11y": "^4.0.0",
        "eslint-plugin-react": "^6.10.3",
        "expect": "^1.14.0",
        "tap": "^5.7.0"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/sabeurthabti/react-native-css.git"
    },
    "keywords": [
        "react",
        "react-native",
        "react-component",
        "css",
        "styling",
        "components",
        "ios"
    ],
    "bugs": {
        "url": "https://github.com/sabeurthabti/react-native-css/issues"
    },
    "precommit": [
        "test"
    ],
    "homepage": "https://github.com/sabeurthabti/react-native-css",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
