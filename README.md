# A "moar" ESLint configuration - even stricter

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/npm/v/eslint-config-node-moar.svg?style=flat-square)](https://npmjs.com/package/eslint-config-node-moar)
[![Build Status](https://github.com/ildella/eslint-config-node-moar/actions/workflows/main.yaml/badge.svg)](https://github.com/ildella/eslint-config-node-moar/actions)
[![Known Vulnerabilities](https://snyk.io/test/github/ildella/eslint-config-node-moar/badge.svg?targetFile=package.json)](https://snyk.io/test/github/ildella/eslint-config-node-moar?targetFile=package.json)

An ESLint [Shareable Config](https://eslint.org/docs/latest/developer-guide/shareable-configs) that includes:

  * extends [moar](https://github.com/ildella/eslint-config-node-moar) - a strict and complete ruleset that also extends node/reccomended, sonarjs, security and promise plugins
  * The functional programming plugin
  * The unicorn plugin

## Basic usage

Install all the dependencies:

```shell
yarn add -D eslint eslint-config-node-moar eslint eslint-config-node-moar-stricter eslint-plugin-node eslint-plugin-security eslint-plugin-sonarjs eslint-plugin-fp eslint-plugin-unicorn
```

Add it in your own `.eslintrc.js` like this:

```javascript
module.exports = {
  extends: [
    'node-moar-stricter',
  ],
}
```
