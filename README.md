# react-webpack-boilerplate, react + webpack模版

> 包含了热重载、eslint代码检查、单元测试的webpack模版，A full-featured Webpack setup with hot-reload, lint-on-save & unit testing.

> 该模版基于react16版本和webpack4, This template is react16 compatible.

## Usage

This is a project template for react

``` bash
$ clone https://github.com/feleventh/react-webpack-template.git
$ cd react-webpack-template
$ yarn install
$ npm run dev
```

The development server will run on port 8081 by default. If that port is already in use on your machine, the next free port will be used.

## What's Included

- `npm run dev`: first-in-class development experience.
  - State preserving hot-reload
  - State preserving compilation error overlay
  - Lint-on-save with ESLint/airbnb-base
  - Source maps

- `npm run build`: Production ready build.
  - JavaScript minified with [UglifyJS v3](https://github.com/mishoo/UglifyJS2/tree/harmony).
  - HTML minified with [html-minifier](https://github.com/kangax/html-minifier).
  - CSS across all components extracted into a single file and minified with [cssnano](https://github.com/ben-eb/cssnano).
  - Static assets compiled with version hashes for efficient long-term caching, and an auto-generated production `index.html` with proper URLs to these generated assets.
  - Use `npm run build --report`to build with bundle size analytics.

- `npm run unit`: Unit tests run in [JSDOM](https://github.com/tmpvar/jsdom) with [Jest](https://facebook.github.io/jest/).
  - Supports ES2015+ in test files.
  - Easy mocking.

### Fork It And Make Your Own

该模版项目默认使用了airbnb代码风格，你也可以修改为standard或者其他js代码风格，单元测试使用了Jest框架，你也可以选择mocha+karma等其他测试框架。

欢迎fork，star本项目，并在issues提出宝贵建议。

You can fork this repo to create your own boilerplate

