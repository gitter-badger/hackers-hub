WDIO Concise Reporter
=====================

> A WebdriverIO plugin to report in concise style.

## Installation

The easiest way is to keep `@wdio/concise-reporter` as a devDependency in your `package.json`, via:

```sh
npm install @wdio/concise-reporter --save-dev
```

Instructions on how to install `WebdriverIO` can be found [here](https://webdriver.io/docs/gettingstarted).

## Configuration

The following code shows the default wdio test runner configuration. Just add `'concise'` as a reporter
to the array.

```js
// wdio.conf.js
module.exports = {
  // ...
  reporters: ['dot', 'concise'],
  // ...
};
```
