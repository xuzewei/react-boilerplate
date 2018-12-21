# react-boilerplate

A react boilerplate embrace React, Babel, Express, Jest, Webpack, etc.

## Setup

```sh
$ npm install
# mode for development
$ npm run buildDev && npm start
# mode for product
$ npm run buildProd && npm start
```

**Notes:**

> Console statements should not be shipped in production code, which is why the linter is pointing this out. To silence it, you can just add the below comment to disable linting on the offending line in *.jsi

**`// eslint-disable-line no-undef`**