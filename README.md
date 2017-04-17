# api documentation for  [element-ui (v1.2.8)](http://element.eleme.io)  [![npm package](https://img.shields.io/npm/v/npmdoc-element-ui.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-element-ui) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-element-ui.svg)](https://travis-ci.org/npmdoc/node-npmdoc-element-ui)
#### A Component Library for Vue.js.

[![NPM](https://nodei.co/npm/element-ui.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/element-ui)

- [https://npmdoc.github.io/node-npmdoc-element-ui/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-element-ui/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-element-ui/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-element-ui/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-element-ui/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-element-ui/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/ElemeFE/element/issues"
    },
    "dependencies": {
        "async-validator": "^1.6.6",
        "babel-helper-vue-jsx-merge-props": "^2.0.0",
        "deepmerge": "^1.2.0",
        "throttle-debounce": "^1.0.1"
    },
    "description": "A Component Library for Vue.js.",
    "devDependencies": {
        "babel-cli": "^6.14.0",
        "babel-core": "^6.14.0",
        "babel-loader": "^6.2.5",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-module-resolver": "^2.2.0",
        "babel-plugin-syntax-jsx": "^6.8.0",
        "babel-plugin-transform-vue-jsx": "^3.3.0",
        "babel-preset-es2015": "^6.14.0",
        "chai": "^3.5.0",
        "cheerio": "^0.18.0",
        "cooking": "^1.2.0",
        "cooking-lint": "^0.1.3",
        "cooking-vue2": "^0.3.0",
        "copy-webpack-plugin": "^4.0.1",
        "coveralls": "^2.11.14",
        "cp-cli": "^1.0.2",
        "cross-env": "^3.1.3",
        "css-loader": "^0.24.0",
        "es6-promise": "^4.0.5",
        "eslint": "^3.10.2",
        "extract-text-webpack-plugin": "^1.0.1",
        "file-loader": "^0.9.0",
        "file-save": "^0.2.0",
        "gh-pages": "^0.11.0",
        "gulp": "^3.9.1",
        "gulp-cssmin": "^0.1.7",
        "gulp-postcss": "^6.1.1",
        "highlight.js": "^9.3.0",
        "html-loader": "^0.4.3",
        "html-webpack-plugin": "^2.22.0",
        "inject-loader": "^3.0.0-beta2",
        "isparta-loader": "^2.0.0",
        "json-loader": "^0.5.4",
        "json-templater": "^1.0.4",
        "karma": "^1.3.0",
        "karma-coverage": "^1.1.1",
        "karma-mocha": "^1.2.0",
        "karma-phantomjs-launcher": "^1.0.2",
        "karma-sinon-chai": "^1.2.4",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-spec-reporter": "0.0.26",
        "karma-webpack": "^1.8.0",
        "lerna": "^2.0.0-beta.32",
        "lolex": "^1.5.1",
        "markdown-it": "^6.1.1",
        "markdown-it-anchor": "^2.5.0",
        "markdown-it-container": "^2.0.0",
        "mocha": "^3.1.1",
        "phantomjs-prebuilt": "^2.1.13",
        "postcss": "^5.1.2",
        "postcss-loader": "^0.11.1",
        "postcss-salad": "^1.0.8",
        "rimraf": "^2.5.4",
        "sinon": "^1.17.6",
        "sinon-chai": "^2.8.0",
        "style-loader": "^0.13.1",
        "theaterjs": "^3.0.0",
        "transliteration": "^1.1.11",
        "uppercamelcase": "^1.1.0",
        "url-loader": "^0.5.7",
        "vue": "^2.1.8",
        "vue-loader": "^10.3.0",
        "vue-markdown-loader": "^0.5.1",
        "vue-router": "^2.0.0",
        "vue-template-compiler": "^2.1.8",
        "vue-template-es2015-compiler": "^1.4.2",
        "webpack": "^1.13.2",
        "webpack-dev-server": "^1.15.1",
        "webpack-node-externals": "^1.5.4"
    },
    "directories": {},
    "dist": {
        "shasum": "aa95bde8ad550d17b23b2a73ae84cfa1f0c2635d",
        "tarball": "https://registry.npmjs.org/element-ui/-/element-ui-1.2.8.tgz"
    },
    "files": [
        "lib",
        "src",
        "packages"
    ],
    "gitHead": "9f52a202851779a9b3e9873cd78311669c54338f",
    "homepage": "http://element.eleme.io",
    "keywords": [
        "eleme",
        "vue",
        "components"
    ],
    "license": "MIT",
    "main": "lib/element-ui.common.js",
    "maintainers": [
        {
            "name": "baiyaaaaa"
        },
        {
            "name": "qingwei.li"
        },
        {
            "name": "yi.yang"
        }
    ],
    "name": "element-ui",
    "optionalDependencies": {},
    "peerDependencies": {
        "vue": "^2.1.6"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/ElemeFE/element.git"
    },
    "scripts": {
        "bootstrap": "yarn || npm i",
        "build:file": "node build/bin/iconInit.js & node build/bin/build-entry.js & node build/bin/i18n.js & node build/bin/version.js",
        "build:theme": "node build/bin/gen-cssfile && gulp build --gulpfile packages/theme-default/gulpfile.js && cp-cli packages/theme-default/lib lib/theme-default",
        "build:umd": "node build/bin/build-locale.js",
        "build:utils": "cross-env BABEL_ENV=utils babel src --out-dir lib --ignore src/index.js",
        "clean": "rimraf lib && rimraf packages/*/lib && rimraf test/**/coverage && lerna clean --yes",
        "deploy": "npm run deploy:build && gh-pages -d examples/element-ui --remote eleme && del examples/element-ui",
        "deploy:build": "npm run build:file && cooking build -c build/cooking.demo.js -p && echo element.eleme.io>>examples/element-ui/CNAME",
        "dev": "npm run bootstrap && npm run build:file && cooking watch -c build/cooking.demo.js -p",
        "dev:play": "npm run build:file && cross-env PLAY_ENV=true cooking watch -c build/cooking.demo.js -p",
        "dist": "npm run clean && npm run build:file && npm run lint && cooking build -c build/cooking.conf.js,build/cooking.common.js,build/cooking.component.js -p && npm run build:utils && npm run build:umd && npm run build:theme",
        "dist:all": "node build/bin/build-all.js && npm run build:theme",
        "i18n": "node build/bin/i18n.js",
        "lint": "eslint src/**/* test/**/* packages/**/*.{js,vue} build/**/* --quiet",
        "pub": "npm run bootstrap && sh build/git-release.sh && sh build/release.sh",
        "pub:all": "npm run dist:all && lerna publish --skip-git && git commit -am 'publish independent packages' && git push eleme dev",
        "test": "npm run lint && cross-env CI_ENV=/dev/ karma start test/unit/karma.conf.js --single-run",
        "test:watch": "karma start test/unit/karma.conf.js"
    },
    "style": "lib/theme-default/index.css",
    "unpkg": "lib/index.js",
    "version": "1.2.8"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
