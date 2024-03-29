<!-- TITLE: Welcome to DevOps Notebook -->
<!-- SUBTITLE: DevOps notebooke is my personal notebook for cutting time searching on google -->
<a href="/home/test2">test2</a>
# Welcome to DevOps Notebook
`
blka blallbalblalbla`
```snippets
$ echo 'test'
$ rm -rf /var/log
```


```json
{
  "name": "wiki",
  "version": "1.0.117",
  "description": "A modern, lightweight and powerful wiki app built on NodeJS, Git and Markdown",
  "main": "wiki.js",
  "scripts": {
    "start": "node wiki start",
    "stop": "node wiki stop",
    "restart": "node wiki restart",
    "build": "node tools/fuse",
    "dev": "node tools/fuse -d",
    "dev-configure": "node tools/fuse -c",
    "test": "jest",
    "postinstall": "opencollective postinstall"
  },
  "bin": {
    "wiki": "wiki.js"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/Requarks/wiki.git"
  },
  "keywords": [
    "wiki",
    "wikis",
    "docs",
    "documentation",
    "markdown",
    "guides"
  ],
  "author": "Nicolas Giard",
  "license": "AGPL-3.0",
  "bugs": {
    "url": "https://github.com/Requarks/wiki/issues"
  },
  "homepage": "https://github.com/Requarks/wiki#readme",
  "engines": {
    "node": ">=6.11.1"
  },
  "dependencies": {
    "auto-load": "~3.0.0",
    "axios": "~0.16.2",
    "bcryptjs-then": "~1.0.1",
    "bluebird": "~3.5.0",
    "body-parser": "~1.17.2",
    "bunyan": "~1.8.12",
    "cheerio": "~1.0.0-rc.2",
    "child-process-promise": "~2.2.1",
    "chokidar": "~1.7.0",
    "compression": "~1.7.0",
    "connect-flash": "~0.1.1",
    "connect-mongo": "~1.3.2",
    "cookie-parser": "~1.4.3",
    "cron": "~1.2.1",
    "diff2html": "~2.3.0",
    "execa": "~0.8.0",
    "express": "~4.15.4",
    "express-brute": "1.0.1",
    "express-brute-mongoose": "~0.0.9",
    "express-session": "~1.15.5",
    "file-type": "~6.1.0",
    "filesize.js": "~1.0.2",
    "follow-redirects": "~1.2.4",
    "fs-extra": "~4.0.1",
    "git-wrapper2-promise": "~0.2.9",
    "highlight.js": "~9.12.0",
    "i18next": "~9.0.0",
    "i18next-express-middleware": "~1.0.5",
    "i18next-node-fs-backend": "~1.0.0",
    "image-size": "~0.6.0",
    "jimp": "~0.2.28",
    "js-yaml": "~3.9.1",
    "jsonwebtoken": "~7.4.3",
    "klaw": "~2.1.0",
    "levelup": "~1.3.9",
    "lodash": "~4.17.4",
    "markdown-it": "~8.4.0",
    "markdown-it-abbr": "~1.0.4",
    "markdown-it-anchor": "~4.0.0",
    "markdown-it-attrs": "~1.1.0",
    "markdown-it-emoji": "~1.4.0",
    "markdown-it-expand-tabs": "~1.0.12",
    "markdown-it-external-links": "0.0.6",
    "markdown-it-footnote": "~3.0.1",
    "markdown-it-mathjax": "~2.0.0",
    "markdown-it-task-lists": "~2.0.1",
    "mathjax-node": "~1.2.0",
    "memdown": "~1.2.4",
    "mime-types": "~2.1.16",
    "moment": "~2.18.1",
    "moment-timezone": "~0.5.13",
    "mongodb": "~2.2.31",
    "mongoose": "~4.11.9",
    "multer": "~1.3.0",
    "node-2fa": "~1.1.2",
    "node-graceful": "~0.2.3",
    "opencollective": "~1.0.3",
    "ora": "~1.3.0",
    "passport": "~0.4.0",
    "passport-azure-ad-oauth2": "0.0.4",
    "passport-facebook": "~2.1.1",
    "passport-github2": "~0.1.10",
    "@passport-next/passport-google-oauth2": "1.0.0",
    "passport-ldapauth": "~2.0.0",
    "passport-local": "~1.0.0",
    "passport-openidconnect": "~0.0.2",
    "passport-slack": "0.0.7",
    "passport-windowslive": "~1.0.2",
    "passport.socketio": "~3.7.0",
    "pm2": "~2.6.1",
    "pug": "~2.0.0-rc.3",
    "raven": "~2.4.1",
    "read-chunk": "~2.1.0",
    "remove-markdown": "~0.2.2",
    "request": "~2.81.0",
    "search-index-adder": "~0.3.9",
    "search-index-searcher": "~0.2.10",
    "semver": "~5.4.1",
    "serve-favicon": "~2.4.3",
    "simplemde": "~1.11.2",
    "socket.io": "~2.0.2",
    "stopword": "~0.1.6",
    "stream-to-promise": "~2.2.0",
    "tar": "~4.0.1",
    "through2": "~2.0.3",
    "validator": "~8.1.0",
    "validator-as-promised": "~1.0.2",
    "winston": "~2.3.1",
    "yargs": "~8.0.1"
  },
  "devDependencies": {
    "@glimpse/glimpse": "~0.22.15",
    "@panter/vue-i18next": "~0.5.0",
    "babel-cli": "~6.26.0",
    "babel-jest": "~20.0.3",
    "babel-plugin-transform-object-assign": "~6.22.0",
    "babel-preset-es2015": "~6.24.1",
    "brace": "~0.10.0",
    "colors": "~1.1.2",
    "consolidate": "~0.14.5",
    "eslint": "~4.5.0",
    "eslint-config-standard": "~10.2.1",
    "eslint-plugin-import": "~2.7.0",
    "eslint-plugin-node": "~5.1.0",
    "eslint-plugin-promise": "~3.5.0",
    "eslint-plugin-standard": "~3.0.1",
    "fuse-box": "~2.2.2",
    "i18next-xhr-backend": "~1.4.2",
    "jest": "~20.0.4",
    "jest-junit": "~3.1.0",
    "jquery": "~3.2.1",
    "jquery-contextmenu": "~2.5.0",
    "jquery-simple-upload": "~1.0.0",
    "jquery-smooth-scroll": "~2.2.0",
    "jquery-sticky": "~1.0.4",
    "lodash-cli": "~4.17.4",
    "lodash-es": "~4.17.4",
    "node-sass": "~4.5.3",
    "nodemon": "~1.11.0",
    "pug-lint": "~2.4.0",
    "twemoji-awesome": "~1.0.6",
    "typescript": "~2.5.2",
    "uglify-es": "~3.0.28",
    "vee-validate": "~2.0.0-rc.14",
    "vue": "~2.4.2",
    "vue-clipboards": "~1.1.0",
    "vue-lodash": "~1.0.3",
    "vue-resource": "~1.3.4",
    "vue-template-compiler": "~2.4.2",
    "vue-template-es2015-compiler": "~1.5.3",
    "vuex": "~2.4.0"
  },
  "jest": {
    "testResultsProcessor": "./node_modules/jest-junit",
    "collectCoverage": false,
    "testMatch": [
      "**/test/**/*.js?(x)",
      "**/?(*.)(spec|test).js?(x)"
    ],
    "verbose": true
  },
  "jest-junit": {
    "suiteName": "jest test",
    "output": "./test-results/junit.xml",
    "classNameTemplate": "{classname}-{title}",
    "titleTemplate": "{classname}-{title}"
  },
  "collective": {
    "type": "opencollective",
    "url": "https://opencollective.com/wikijs",
    "logo": "https://opencollective.com/opencollective/logo.txt"
  }
}
```
