# Awesome babel macros [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A collection of awesome [babel macros](https://github.com/kentcdodds/babel-plugin-macros) and related resources

## Contents

- [Macros](#macros)
- [Resources](#resources)
  - [General](#general)
  - [Developing macros](#developing-macros)
- [Integrations](#integrations)

---

## Macros

- [`preval.macro`](https://www.npmjs.com/package/preval.macro): Pre-evaluate code
- [`codegen.macro`](https://www.npmjs.com/package/codegen.macro): Generate code
- [`import-all.macro`](https://www.npmjs.com/package/import-all.macro): Import all files that match a glob
- [`tagged-translations`](https://www.npmjs.com/package/tagged-translations): Translate text in React applications
- [`traph.macro`](https://www.npmjs.com/package/traph.macro): Transform Objects easily, leveraging object getters and graphs
- [`param.macro`](https://www.npmjs.com/package/param.macro): Partial application syntax and lambda parameters for JavaScript, inspired by Scala's `_` and Kotlin's `it`
- [`ms.macro`](https://www.npmjs.com/package/ms.macro): Convert various time formats to milliseconds
- [`react-emotion/macro`](https://emotion.sh/docs/babel-plugin-emotion#babel-macros): Minify and optimize [emotion](https://github.com/emotion-js/emotion) styles
- [`scope.macro`](https://www.npmjs.com/package/scope.macro): Useful build time console functions
- [`graphql.macro`](https://github.com/evenchange4/graphql.macro): Compile GraphQL AST
- [`svgr.macro`](https://github.com/evenchange4/svgr.macro): Run [SVGR](https://github.com/smooth-code/svgr)
- [`glamorous.macro`](https://github.com/kentcdodds/glamorous.macro): Give your [glamorous](https://github.com/paypal/glamorous) components a nice `displayName` for React DevTools
- [`raw.macro`](https://github.com/pveyes/raw.macro): Webpack raw-loader
- [`penv.macro`](https://github.com/chengjianhua/penv.macro): Pick specified value or branch according to the build environment
- [`lqip.macro`](https://github.com/stereobooster/lqip.macro): Cretes LQIP at build time, similar to webpack [lqip-loader](https://www.npmjs.com/package/lqip-loader)
- [`dev-console.macro`](https://www.npmjs.com/package/dev-console.macro): Remove all console.log, console.warn and console.error calls from production builds
- [`data-uri.macro`](https://github.com/Andarist/data-uri.macro): Convert assets to [data URIs](https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/Data_URIs)
- [`css-to-rn.macro`](https://github.com/jhen0409/css-to-rn.macro): Convert CSS to React Native style sheet
- [`regexgen.macro`](https://github.com/Andarist/regexgen.macro): Convert set of strings to optimized RegExps
- [`tinker.macro`](https://github.com/bradlc/tinker.macro): Evaluate Laravel code
- [`@lingui/macro`](https://lingui.js.org/ref/macro.html): Macros for internationalization (i18n) in [LinguiJS](https://github.com/lingui/js-lingui/)
- [`unique-classname.macro`](https://github.com/huchenme/unique-classname.macro): Generate unique className for emotion
- [`idx.macro`](https://github.com/dralletje/idx.macro): Traverse properties on objects and arrays
- [`pipeline.macro`](https://github.com/Andarist/pipeline.macro): Macro working similarly to the pipeline operator
- [`blade.macro`](https://www.npmjs.com/package/blade.macro): Generate GraphQL query strings inline and solve the [double declaration problem](https://babel-blade.netlify.com/docs/declarationdeclaration.html)
- [`styled-jsx/macro`](https://www.npmjs.com/package/styled-jsx#using-resolve-as-a-babel-macro): Use [styled-jsx](https://www.npmjs.com/package/styled-jsx)'s `resolve` tag

## Resources

### General

- [`babel-plugin-macros` usage](https://github.com/kentcdodds/babel-plugin-macros/blob/master/other/docs/user.md)
- Search npm for [keyword:babel-plugin-macros](https://www.npmjs.com/search?q=keywords:babel-plugin-macros) to find macros
- [Difference between plugins and macros](https://github.com/kentcdodds/babel-plugin-macros#whats-the-difference-between-babel-plugins-and-macros)
- [Zero-config code transformation with babel-plugin-macros](https://babeljs.io/blog/2017/09/11/zero-config-with-babel-macros)

### Developing macros

- [`babel-plugin-macros` usage for macro authors](https://github.com/kentcdodds/babel-plugin-macros/blob/master/other/docs/author.md)
- [jamiebuilds/babel-handbook](https://github.com/jamiebuilds/babel-handbook)
- [Writing custom Babel and ESLint plugins with ASTs](https://kentcdodds.com/talks/#writing-custom-babel-and-eslint-plugins-with-asts)
- [Code Transformation and Linting](https://kentcdodds.com/workshops/#code-transformation-and-linting)

## Integrations

The following projects include `babel-plugin-macros`, so macros can be used out-of-the-box without additional configuration:

- [Gatsby](https://www.gatsbyjs.org/)
- [Create React App](https://facebook.github.io/create-react-app/)

---

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Jonas Gierer has waived all copyright and
related or neighboring rights to this work.
