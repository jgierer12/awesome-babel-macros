# Awesome babel macros [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A collection of awesome [babel macros](https://github.com/kentcdodds/babel-plugin-macros) and related resources

## Contents

- [Macros](#macros)
  - [General](#general)
  - [Object lifetime / memory management](#object-lifetime--memory-management)
  - [File loading](#file-loading)
  - [Object/Array manipulation](#objectarray-manipulation)
  - [Code generation](#code-generation)
  - [Development](#development)
  - [React](#react)
  - [CSS-in-JS](#css-in-js)
  - [GraphQL](#graphql)
- [Resources](#resources)
  - [General](#general-1)
  - [Developing macros](#developing-macros)
- [Integrations](#integrations)

---

## Macros

### General

- [`param.macro`](https://www.npmjs.com/package/param.macro): Partial application syntax and lambda parameters for JavaScript, inspired by Scala's `_` and Kotlin's `it`
- [`ms.macro`](https://www.npmjs.com/package/ms.macro): Convert various time formats to milliseconds
- [`data-uri.macro`](https://github.com/Andarist/data-uri.macro): Convert assets to [data URIs](https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/Data_URIs)
- [`regexgen.macro`](https://github.com/Andarist/regexgen.macro): Convert set of strings to optimized regular expression
- [`tinker.macro`](https://github.com/bradlc/tinker.macro): Evaluate Laravel code
- [`@lingui/macro`](https://lingui.js.org/ref/macro.html): Macro for internationalization in [LinguiJS](https://github.com/lingui/js-lingui/)
- [`pipeline.macro`](https://github.com/Andarist/pipeline.macro): Macro working similarly to the pipeline operator
- [`paths.macro`](https://www.npmjs.com/package/paths.macro): Import paths like `__dirname` and `__filename` as static values
- [`for-own.macro`](https://github.com/nicolo-ribaudo/for-own.macro): Make `for-in` only visit own properties
- [`ts-nameof.macro`](https://github.com/dsherret/ts-nameof/tree/master/packages/ts-nameof.macro): [`nameof`](https://msdn.microsoft.com/en-us/library/dn986596.aspx) in TypeScript
- [`files.macro`](https://github.com/ridermansb/files.macro): Transform directory into array of file names
- [`flavors.macro`](https://github.com/gnithin/flavors.macro): Build different flavors of an app by manipulating import headers
- [`yaml.macro`](https://www.npmjs.com/package/yaml.macro): Load YAML files as pre-parsed objects
- [`yaml-to-js.macro`](https://www.npmjs.com/package/yaml-to-js.macro): Convert yaml template strings to javascript objects at build time
- [`@ts-delight/pipe.macro`](https://www.npmjs.com/package/@ts-delight/pipe.macro): TypeScript friendly fluent pipeline API with support for async steps, additional arguments, early returns and reconciliation
- [`@ts-delight/if-expr.macro`](https://www.npmjs.com/package/@ts-delight/if-expr.macro): Expression-oriented fluent alternative to javascript's if-statement that compiles away to ternary expressions
- [`@ts-delight/switch-expr.macro`](https://www.npmjs.com/package/@ts-delight/switch-expr.macro): An expression-oriented fluent alternative to javascript's switch-statement that compiles away to ternary expressions
- [`@ts-delight/async-to-generator.macro`](https://www.npmjs.com/package/@ts-delight/async-to-generator.macro): Transform async functions to generator functions

### Object lifetime / memory management
- [`using.macro`](https://github.com/Veetaha/using.macro): Wrap your resource handles into try-finally blocks automatically similarly to C# [using declaration](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/proposals/csharp-8.0/using#using-declaration) style.

### File loading

- [`filesize.macro`](https://www.npmjs.com/package/filesize.macro): Apply webpack's [`filesize-loader`](https://github.com/zouhir/filesize-loader)
- [`lqip.macro`](https://github.com/stereobooster/lqip.macro): Create LQIP at build-time, similar to webpack's [`lqip-loader`](https://www.npmjs.com/package/lqip-loader)
- [`raw.macro`](https://github.com/pveyes/raw.macro): Apply webpack's `raw-loader`
- [`yaml.macro`](https://www.npmjs.com/package/yaml.macro): Load YAML files as pre-parsed objects
- [`json.macro`](https://github.com/ifiokjr/json.macro): Load JSON files individually or by pattern matching, with special support for package.json, version and tsconfig files.

### Object/Array manipulation

- [`traph.macro`](https://www.npmjs.com/package/traph.macro): Transform Objects easily, leveraging object getters and graphs
- [`idx.macro`](https://github.com/dralletje/idx.macro): Traverse properties on objects and arrays
- [`assign.macro`](https://www.npmjs.com/package/assign.macro): Transpile `Object.assign`-style expressions to direct assignments

### Code generation

- [`preval.macro`](https://www.npmjs.com/package/preval.macro): Pre-evaluate code<span id="backlink-1" />[<sup>1</sup>](#footnote-1)
- [`codegen.macro`](https://www.npmjs.com/package/codegen.macro): Generate code[<sup>1</sup>](#footnote-1)
- [`import-all.macro`](https://www.npmjs.com/package/import-all.macro): Import all files that match a glob

### Development

- [`scope.macro`](https://www.npmjs.com/package/scope.macro): Useful build-time console functions
- [`penv.macro`](https://github.com/chengjianhua/penv.macro): Pick specified value or branch according to the build environment
- [`dev-console.macro`](https://www.npmjs.com/package/dev-console.macro): Remove all `console.log`, `console.warn` and `console.error` calls from production builds
- [`babel-plugin-trace/macro`](https://github.com/codemix/babel-plugin-trace): Add labeled statement logging helpers with file and function name prefix
- [`inspect.macro`](https://www.npmjs.com/package/inspect.macro): Log an expression and the result of that expression to the console
- [`require-context.macro`](https://github.com/storybooks/require-context.macro): Mock webpack's `require.context()`
- [`@ts-delight/debug.macro`](https://www.npmjs.com/package/@ts-delight/debug.macro): Make usage of [visionmedia/debug](https://github.com/visionmedia/debug) more convenient through build time enhancements

### React

- [`Tersus-JSX`](https://www.npmjs.com/package/tersus-jsx.macro): Inspired by AngularJS, ng-if (use tj-if) and ng-repeat (use tj-for) for neater JSX in React
- [`tagged-translations`](https://www.npmjs.com/package/tagged-translations): Translate text in React applications
- [`svgr.macro`](https://github.com/evenchange4/svgr.macro): Apply [SVGR](https://github.com/smooth-code/svgr)
- [`css-to-rn.macro`](https://github.com/jhen0409/css-to-rn.macro): Convert CSS to React Native style sheet
- [`hooks.macro`](https://www.npmjs.com/package/hooks.macro): Automatic React Hooks memoization invalidation
- [`inline-mdx.macro`](https://www.npmjs.com/package/inline-mdx.macro): Convert MDX into inline components
- [`react-broker/macros`](https://www.npmjs.com/package/react-broker): Lazy-load React components
- [`rpi.macro`](https://www.npmjs.com/package/rpi.macro): Macro for [`react-precious-image`](https://github.com/stereobooster/react-precious-image)
- [`react-hot-reload.macro`](https://www.npmjs.com/package/react-hot-reload.macro): Zero configuration Hot Module Replacement for CRAv2
- [`mdi-norm/macro`](https://github.com/eugeneilyin/mdi-norm#with-babel-macros): Embed Material Design system SVG icons
- [`reactive.macro`](https://github.com/yesmeck/reactive.macro): Reduce React boilerplate
- [`@ts-delight/inject-display-name.macro`](https://github.com/ts-delight/inject-display-name.macro): Inject display name into dynamically constructed components
- [`@ts-delight/fluent-react.macro`](https://www.npmjs.com/package/@ts-delight/fluent-react.macro): Fluent, Terse and Type-safe alternative to JSX for React
- [`react-css-modules.macro`](https://github.com/bohdanbirdie/react-css-modules.macro): Map CSS Modules to `styleName` property

### CSS-in-JS

- [`react-emotion/macro`](https://emotion.sh/docs/babel-plugin-emotion#babel-macros): Minify and optimize [emotion](https://github.com/emotion-js/emotion) styles
- [`glamorous.macro`](https://github.com/kentcdodds/glamorous.macro): Give your [glamorous](https://github.com/paypal/glamorous) components a nice `displayName` for React DevTools
- [`styled-jsx/macro`](https://www.npmjs.com/package/styled-jsx#using-resolve-as-a-babel-macro): Use [styled-jsx](https://www.npmjs.com/package/styled-jsx)'s `resolve` tag
- [`styled-components/macro`](https://www.styled-components.com/docs/tooling#babel-macro): Improve the debugging experience and add server-side rendering support to [styled-components](https://www.styled-components.com/)
- [`styled-import/macro`](https://github.com/glortho/styled-import): Lightweight CSS parser for stealing rules from stylesheets, for use with [styled-components](https://www.styled-components.com/), React, or anywhere else you might be doing CSS in JS -- especially useful for working with global or 3rd-party stylesheets
- [`unique-classname.macro`](https://github.com/huchenme/unique-classname.macro): Generate unique className for emotion
- [`twin.macro`](https://github.com/ben-rogerson/twin.macro): Alternative and more up-to-date solution to [Tailwind](https://tailwindcss.com/) as a macro.

### GraphQL

- [`graphql.macro`](https://github.com/evenchange4/graphql.macro): Compile GraphQL AST
- [`blade.macro`](https://www.npmjs.com/package/blade.macro): Generate GraphQL query strings inline and solve the [double declaration problem](https://babel-blade.netlify.com/docs/declarationdeclaration.html)

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

The following projects include `babel-plugin-macros`, so macros can be used out of the box without additional configuration:

- [Gatsby](https://www.gatsbyjs.org/)
- [Create React App](https://facebook.github.io/create-react-app/)

---

## Footnotes

1. <span id="footnote-1" />[`preval` vs `codegen`](https://www.youtube.com/watch?v=1queadQ0048&list=PLV5CVI1eNcJgCrPH_e6d57KRUTiDZgs0u) [:leftwards_arrow_with_hook:](#backlink-1)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Jonas Gierer has waived all copyright and
related or neighboring rights to this work.
