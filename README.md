[![Known Vulnerabilities](https://snyk.io/test/github/web-padawan/polymer3-webpack-starter/badge.svg)](https://snyk.io/test/github/web-padawan/polymer3-webpack-starter)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![Lighthouse score: 91/100](https://lighthouse-badge.appspot.com/?score=91&compact&category=PWA)](https://github.com/ebidel/lighthouse-badge)

# Polymer 3 Webpack Starter

This is an example project demonstrating how you can build a frontend part of the JavaScript
application using [Vaadin components](https://vaadin.com/components) and [Vaadin Router](https://github.com/vaadin/vaadin-router) library, and leverage the benefits of the modern tools.

The application uses ES modules for development, and [Webpack](https://webpack.js.org) as
a module bundler. The optimizations like code splitting, minifying JavaScript and HTML
(inside of the template string literals) are used to reduce production bundle size.

## Install dependencies

```sh
npm i
```

## Start the development server

Start `webpack-dev-server` on localhost `http://127.0.0.1:3000`:

```sh
npm run dev
```

## Lint JavaScript

```sh
npm run lint
```


## Build

Run the production build:

```sh
npm run build
```

Serve the built output on localhost `http://127.0.0.1:8000`:

```sh
npm start
```

## Known Limitations

- Using `import.meta` suggested by Polymer docs is not supported, see [webpack/webpack#6719](https://github.com/webpack/webpack/issues/6719)
- `@babel/plugin-transform-classes` should be pinned to 7.0.0-beta.35, see [babel/babel#8496](https://github.com/babel/babel/issues/8496)
