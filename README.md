<p align="center">
    <img width="300" src="./logo.png" alt="logo of rspack-awesome repository"><br>
    A curated list of awesome things related to <a href='https://github.com/web-infra-dev/rspack'>Rspack</a> and its ecology
</p>

<br><br>

<h1>Awesome Rspack</h1>

- [Resources](#resources)
  - [Official Resources](#official-resources)
  - [Ecosystem](#ecosystem)
- [Starter](#starter)
  - [Rspack Starter](#rspack-starter)
  - [Rsbuild Starter](#rsbuild-starter)
- [Plugins](#plugins)
  - [Rspack Plugins](#rspack-plugins)
  - [Rsbuild Plugins](#rsbuild-plugins)
  - [Rspress Plugins](#rspress-plugins)
- [Deployment](#deployment)
- [Libraries](#libraries)
- [Blogs](#blogs)
- [License](#license)

## Resources

### Official Resources

- [Rspack Doc](https://rspack.dev/)
- [Rspack GitHub Repo](https://github.com/web-infra-dev/rspack)
- [Rspack Release Notes](https://github.com/web-infra-dev/rspack/releases)
- [Rspack Examples](https://github.com/rspack-contrib/rspack-examples): Examples for Rspack, Rsbuild, Rspress and Rsdoctor.
- [Rsfamily Design Resources](https://github.com/rspack-contrib/rsfamily-desgin-resources): Design resources for Rspack, Rsbuild, Rspress and Rsdoctor.

### Ecosystem

Upper-level frameworks or libraries that are powered by Rspack or connected to Rspack:

- [Rsbuild](https://rsbuild.dev/): The Rspack-based build tool.
- [Rspress](https://rspress.dev/): A fast Rspack-based static site generator.
- [Rsdoctor](https://rsdoctor.dev/): A one-stop build analyzer for Rspack and webpack.
- [Rslib](https://github.com/web-infra-dev/rslib): The library build tool powered by Rsbuild.
- [Modern.js](https://modernjs.dev/): A progressive React framework for web development.
- [storybook-rsbuild](https://github.com/rspack-contrib/storybook-rsbuild): Storybook builder powered by Rsbuild.
- [@nx/rspack](https://nx.dev/nx-api/rspack): The Nx plugin for Rspack.
- [Docusaurus](https://docusaurus.io/blog/releases/3.6#docusaurus-faster): Help you ship a beautiful documentation site in no time.
- [Nuxt](https://nuxt.com/): An intuitive Vue framework for creating web applications and websites with Vue.js. Install [@nuxt/rspack-builder](https://www.npmjs.com/package/@nuxt/rspack-builder) to use Rspack as the bundler for Nuxt.
- [EMP 3.0](https://empjs.dev/): A high-performance enterprise-level front-end build system built on the Rust ecosystem.
- [pareto](https://github.com/childrentime/pareto): A lightweight SSR framework centered on stream rendering.
- [cypress-rspack-dev-server](https://www.npmjs.com/package/cypress-rspack-dev-server): Cypress Component-testing with Rust-based web bundler Rspack's dev server.
- [serverless-rspack](https://github.com/kitchenshelf/serverless-rspack): A Serverless framework plugin for zero-config JavaScript and TypeScript code bundling using the high performance Rust-based JavaScript bundler rspack.
- [AUmi](https://github.com/atom-yang/aumi): Use Rsbuild as Umi's bundler instead of Webpack, get high performance of Rsbuild and all Umi ecosystem.

## Starter

### Rspack Starter

- [nuxt-rspack-starter](https://github.com/danielroe/nuxt-rspack-starter): Nuxt starter with Rspack.
- [rspack-react-router-starter](https://github.com/ulivz/rspack-react-router-starter)
- [rspack for create-react-app](https://github.com/yanhaijing/rspack-cra)
- [electron-forge-rspack-template](https://github.com/noshower/electron-forge-rspack-template)
- [shark](https://github.com/h7ml/shark): A React project with Rspack, Ant Design, Ant Design Pro Components, Antd@5 React@18 AntV G2Plot, ahooks, react-use, Axios, i18next, localforage, Mock.js, NProgress, and more.
- [electron-react-rspack](https://github.com/RyanProMax/electron-react-rspack): An Electron boilerplate including TypeScript, React, Rspack and ESLint.
- [ng-rspack](https://github.com/edbzn/ng-rspack): Angular + Rspack + Nx + Module Federation 2.0.

### Rsbuild Starter

- [react-tailwind-rsbuild-boilerplate](https://github.com/alonronin/react-tailwind-rsbuild-boilerplate): React + React Router + Tailwind CSS with Rsbuild boilerplate.
- [rsbuild_vue3_h5_template](https://github.com/DMaiGit/rsbuild_vue3_h5_template): A project template for Vue 3. It includes popular libraries such as Axios, Pinia, Vant, and Vue Router.
- [rsbuild-chrome-extension-boilerplate-react](https://github.com/filc-dev/rsbuild-chrome-extension-boilerplate-react): Chrome extension boilerplate for Rsbuild.
- [rsbuild-plugin-template](https://github.com/rspack-contrib/rsbuild-plugin-template): Use this template to create your own Rsbuild plugin.
- [react-antd-admin-pro](https://github.com/cl1107/react-antd-admin-pro): An admin project template for React. It's built with Rsbuild, React 18, TypeScript 5, antd 5, and React Router.
- [umi-rsbuild](https://github.com/atom-yang/aumi-example): `Umi` + `Rsbuild`, A `Umi` project integrated with `Rsbuild`, you can use `Umi` and its plugins with the same experiences as `Umi` + `Webpack` are.
- [rsbuild-react-chakra-starter](https://github.com/sozonome/rsbuild-react-chakra-starter): initialize react app with rsbuild, Chakra UI and TypeScript setup. Configured with awesome toolings: Biome, Husky + Lint-Staged, Commitlint, and Turbo.
- [template-rsbuild-react-ts-tailwind](https://github.com/RoyRao2333/template-rsbuild-react-ts-tailwind): Rsbuild starter template with React + Typescript + TailwindCSS + Biome.
- [rsbuild-turborepo-react-module-federation](https://github.com/nguyenbatranvan/rspack-turbo-module-federation): Rsbuild + Turborepo + Biome + Zustand + React for module federation.

## Plugins

### Rspack Plugins

- [@rspack/plugin-react-refresh](https://github.com/rspack-contrib/rspack-plugin-react-refresh): Support React Fast Refresh.
- [@rspack/plugin-preact-refresh](https://github.com/rspack-contrib/rspack-plugin-preact-refresh): Support Preact Refresh.
- [rspack-manifest-plugin](https://github.com/rspack-contrib/rspack-manifest-plugin): An Rspack plugin for generating an asset manifest.
- [rspack-plugin-virtual-module](https://github.com/rspack-contrib/rspack-plugin-virtual-module): An Rspack plugin that allows you to create virtual modules.
- [html-rspack-plugin](https://github.com/rspack-contrib/html-rspack-plugin): Generate files to serve your Rspack bundles.
- [@aaroon/workbox-rspack-plugin](https://github.com/Clarkkkk/workbox-rspack-plugin): A plugin to use workbox in Rspack.
- [inject-manifest-plugin](https://github.com/tobua/inject-manifest-plugin): Injects a Workbox PWA manifest into a Service Worker.
- [code-inspector-plugin](https://github.com/zh-lx/code-inspector): Click an element on the page, it can automatically open the editor and position the cursor to the source code of the element.
- [rspack-plugin-mock](https://github.com/pengzhanbo/rspack-plugin-mock): Rspack and Rsbuild plugin for API mock dev server.
- [react-cosmos-plugin-rspack](https://github.com/birchill/react-cosmos-plugin-rspack/): Allows building / running React Cosmos using Rspack.
- [rspack-plugin-cli-copy](https://github.com/rspack-contrib/rspack-plugin-cli-copy): Start the project and automatically copy the network URL of the terminal.
- [rtlcss-rspack-plugin](https://github.com/cbbfcd/rtlcss-rspack-plugin): Rspack plugin to create a second css bundle, processed to be rtl.
- [html-inline-css-rspack-plugin](https://github.com/cbbfcd/html-inline-css-rspack-plugin) A Rspack plugin to convert external stylesheets into embedded stylesheets.
- [html-rspack-skip-assets-plugin](https://github.com/cbbfcd/html-rspack-skip-assets-plugin) Adapt html-webpack-skip-assets-plugin to Rspack

Rspack and Rsbuild support most of the webpack plugins, such as:

- [case-sensitive-paths-webpack-plugin](https://github.com/Urthen/case-sensitive-paths-webpack-plugin): Enforces case sensitive paths of all required modules.
- [clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin): Remove your build folder before building.
- [compression-webpack-plugin](https://github.com/webpack-contrib/compression-webpack-plugin): Prepare compressed versions of assets to serve them with Content-Encoding.
- [css-minimizer-webpack-plugin](https://github.com/webpack-contrib/css-minimizer-webpack-plugin): Uses cssnano to optimize and minify your CSS.
- [dotenv-webpack](https://github.com/mrsteele/dotenv-webpack): A secure plugin that supports dotenv and other environment variables.
- [eslint-webpack-plugin](https://github.com/webpack-contrib/eslint-webpack-plugin): Uses eslint to find and fix problems in your JavaScript code.
- [fork-ts-checker-webpack-plugin](https://github.com/TypeStrong/fork-ts-checker-webpack-plugin): Runs TypeScript type checker on a separate process.
- [html-webpack-plugin](https://github.com/jantimon/html-webpack-plugin): Simplifies creation of HTML files to serve your bundles.
- [webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer): Visualize size of webpack output files with an interactive zoomable treemap.
- [@vanilla-extract/webpack-plugin](https://github.com/vanilla-extract-css/vanilla-extract): Integrating vanilla-extract with webpack / Rspack.
- [@sentry/webpack-plugin](https://github.com/getsentry/sentry-javascript-bundler-plugins): Provides source map and release management support for Sentry.
- [@serwist/webpack-plugin](https://github.com/serwist/serwist): generate a manifest of local files for progressive web apps.
- [sonda](https://github.com/filipsobol/sonda): Visualizer and analyzer for JavaScript and CSS bundles.

Rspack and Rsbuild support most of the webpack loaders, such as:

- [babel-loader](https://github.com/babel/babel-loader): Transpiling JavaScript files using Babel.
- [css-loader](https://github.com/webpack-contrib/css-loader): Interprets @import and url() in CSS files and resolve them.
- [sass-loader](https://github.com/webpack-contrib/sass-loader): Compiles Sass/SCSS files to CSS.
- [less-loader](https://github.com/webpack-contrib/less-loader): Compiles Less to CSS.
- [stylus-loader](https://github.com/webpack-contrib/stylus-loader): Compiles Stylus to CSS.
- [postcss-loader](https://github.com/webpack-contrib/postcss-loader): Loader to process CSS with PostCSS.
- [style-loader](https://github.com/webpack-contrib/style-loader): Inject CSS into the DOM.
- [html-loader](https://www.npmjs.com/package/html-loader): Exports HTML as string.
- [vue-loader](https://github.com/vuejs/vue-loader): Loader for Vue Single-File Components.
- [svelte-loader](https://github.com/sveltejs/svelte-loader): Loader for svelte components.
- [imports-loader](https://www.npmjs.com/package/imports-loader): Use modules that depend on specific global variables.
- [source-map-loader](https://github.com/webpack-contrib/source-map-loader): Extracts source maps from existing source files.
- [svg-react-loader](https://github.com/jhamlet/svg-react-loader): Turn SVGs into React Components.
- [svgo-loader](https://github.com/svg/svgo-loader): Loader for SVGO.
- [coffee-loader](https://www.npmjs.com/package/coffee-loader): Compile CoffeeScript to JavaScript.
- [node-loader](https://www.npmjs.com/package/node-loader): Allows to connect native node modules with .node extension.
- [@mdx-js/loader](https://github.com/mdx-js/mdx/tree/main/packages/loader): Loader for MDX.
- [@svgr/webpack](https://github.com/gregberge/svgr/tree/main/packages/webpack): Loader for SVGR.
- [yaml-loader](https://github.com/eemeli/yaml-loader): Allows importing YAML files as JS objects.
- [react-compiler-webpack](https://github.com/SukkaW/react-compiler-webpack): The webpack / Rspack loader for React Compiler.
- [worker-rspack-loader](https://github.com/rspack-contrib/worker-rspack-loader): An Rspack loader that registers a script as a Web Worker.

Rspack and Rsbuild support most of the [unplugin](https://github.com/unplugin), such as:

- [unplugin-vue-components](https://github.com/unplugin/unplugin-vue-components): On-demand components auto importing for Vue.
- [unplugin-auto-import](https://github.com/unplugin/unplugin-auto-import): Auto import APIs on-demand.
- [unplugin-stylex](https://github.com/eryue0220/unplugin-stylex): StyleX integration for Rspack.
- [@arco-plugins/unplugin-react](https://www.npmjs.com/package/@arco-plugins/unplugin-react): A plugin to help you use Arco Design React.
- [@tanstack/router-plugin](https://www.npmjs.com/package/@tanstack/router-plugin): Automatically generate configuration for TanStack Router.
- [unplugin-build-info](https://github.com/renzp94/unplugin-build-info): Print the build information on the console.
- [unplugin-vue-macros](https://github.com/vue-macros/vue-macros): Explore more macros and syntax sugar to Vue.
- [unplugin-inject-preload](https://github.com/Applelo/unplugin-inject-preload): Inject `<link rel="preload">` to your index.html based on your build assets. Need to be used with HTMLWebpackPlugin or HTMLRspackPlugin.

### Rsbuild Plugins

#### For React

- [@rsbuild/plugin-react](https://rsbuild.dev/plugins/list/plugin-react): Provides support for React.
- [@rsbuild/plugin-svgr](https://rsbuild.dev/plugins/list/plugin-svgr): Support convert SVG to React components.
- [@rsbuild/plugin-styled-components](https://github.com/rspack-contrib/rsbuild-plugin-styled-components): Provides compile-time support for styled-components.
- [rsbuild-plugin-react-inspector](https://github.com/hunghg255/rsbuild-plugin-react-inspector): Allows automatic jumping to the local IDE when clicking on a browser element.

#### For Vue

- [@rsbuild/plugin-vue](https://rsbuild.dev/plugins/list/plugin-vue): Provides support for Vue 3 SFC (Single File Components).
- [@rsbuild/plugin-vue-jsx](https://github.com/rspack-contrib/rsbuild-plugin-vue-jsx): Provides support for Vue 3 JSX / TSX syntax.
- [@rsbuild/plugin-vue2](https://github.com/rspack-contrib/rsbuild-plugin-vue2): Provides support for Vue 2 SFC (Single File Components).
- [@rsbuild/plugin-vue2-jsx](https://github.com/rspack-contrib/rsbuild-plugin-vue2-jsx): Provides support for Vue 2 JSX / TSX syntax.
- [rsbuild-plugin-vue-inspector](https://github.com/hunghg255/rsbuild-plugin-vue-inspector): Allows automatic jumping to the local IDE when clicking on a browser element.
- [rsbuild-plugin-vue-legacy](https://github.com/skymoonya/rsbuild-plugin-vue-legacy): Support for Vue versions below 2.7 by setting an alias for `vue`.
- [rspack-plugin-svg](https://github.com/fuxichen/rspack-plugin-svg): Rsbuild plugin to load SVG files as Vue components, using SVGO for optimization.

#### For Preact

- [@rsbuild/plugin-preact](https://rsbuild.dev/plugins/list/plugin-preact): Provides support for Preact.

#### For Svelte

- [@rsbuild/plugin-svelte](https://rsbuild.dev/plugins/list/plugin-svelte): Provides support for Svelte components (`.svelte` files).
- [rsbuild-plugin-svelte-inspector](https://github.com/hunghg255/rsbuild-plugin-svelte-inspector): Allows automatic jumping to the local IDE when clicking on a browser element.

#### For Solid

- [@rsbuild/plugin-solid](https://rsbuild.dev/plugins/list/plugin-solid): Provides support for Solid.

#### Common

- [@rsbuild/plugin-assets-retry](https://rsbuild.dev/plugins/list/plugin-assets-retry): Used to automatically resend requests when static assets fail to load.
- [@rsbuild/plugin-babel](https://rsbuild.dev/plugins/list/plugin-babel): Provides support for Babel transpilation capabilities.
- [@rsbuild/plugin-basic-ssl](https://github.com/rspack-contrib/rsbuild-plugin-basic-ssl): Generate an untrusted, self-signed certificate for the HTTPS server.
- [@rsbuild/plugin-eslint](https://github.com/rspack-contrib/rsbuild-plugin-eslint): Used to run ESLint checks during the compilation.
- [@rsbuild/plugin-type-check](https://github.com/rspack-contrib/rsbuild-plugin-type-check): Used to run TypeScript type checker on a separate process.
- [@rsbuild/plugin-image-compress](https://github.com/rspack-contrib/rsbuild-plugin-image-compress): Compress the image assets.
- [@rsbuild/plugin-mdx](https://github.com/rspack-contrib/rsbuild-plugin-mdx): Provide support for MDX.
- [@rsbuild/plugin-node-polyfill](https://github.com/rspack-contrib/rsbuild-plugin-node-polyfill): Used to inject polyfills of Node core modules in the browser side.
- [@rsbuild/plugin-source-build](https://github.com/rspack-contrib/rsbuild-plugin-source-build): This plugin is designed for the monorepo scenario. It supports referencing source code from other subdirectories and performs build and hot update.
- [@rsbuild/plugin-stylus](https://rsbuild.dev/plugins/list/plugin-stylus): Use Stylus as the CSS preprocessor.
- [@rsbuild/plugin-check-syntax](https://github.com/rspack-contrib/rsbuild-plugin-check-syntax): Used to analyze the syntax compatibility of artifacts, to see if there are any advanced syntaxes that may cause compatibility issues.
- [@rsbuild/plugin-css-minimizer](https://github.com/rspack-contrib/rsbuild-plugin-css-minimizer): Used to customize CSS minimizer, switch to [cssnano](https://cssnano.co/) or other tools for CSS compression.
- [@rsbuild/plugin-typed-css-modules](https://github.com/rspack-contrib/rsbuild-plugin-typed-css-modules): Generate TypeScript declaration files for CSS Modules.
- [@rsbuild/plugin-pug](https://github.com/rspack-contrib/rsbuild-plugin-pug): Provides support for the Pug template engine.
- [@rsbuild/plugin-rem](https://github.com/rspack-contrib/rsbuild-plugin-rem): Implements the rem adaptive layout for mobile pages.
- [@rsbuild/plugin-umd](https://github.com/rspack-contrib/rsbuild-plugin-umd): Used to build outputs in UMD format.
- [@rsbuild/plugin-yaml](https://github.com/rspack-contrib/rsbuild-plugin-yaml): Used to import YAML files and convert them into JavaScript objects.
- [@rsbuild/plugin-toml](https://github.com/rspack-contrib/rsbuild-plugin-toml): Used to import TOML files and convert them into JavaScript objects.
- [rsbuild-plugin-dts](https://github.com/web-infra-dev/rslib/tree/main/packages/plugin-dts): Generate TypeScript declaration files.
- [rsbuild-plugin-ejs](https://github.com/rspack-contrib/rsbuild-plugin-ejs): Provide support for the EJS template engine.
- [rsbuild-plugin-print](https://github.com/hunghg255/rsbuild-plugin-print): Print text, show host with qrcode.
- [rsbuild-plugin-console-debug](https://github.com/hunghg255/rsbuild-plugin-console-debug): Output debug information in the console.
- [rsbuild-plugin-generate-file](https://github.com/sumy7/rsbuild-plugin-generate-file): Generate static file and write them to dist folder after packaging.
- [rsbuild-plugin-google-analytics](https://github.com/rspack-contrib/rsbuild-plugin-google-analytics): Setup Google Analytics in your website.
- [rsbuild-plugin-web-extension](https://github.com/filc-dev/rsbuild-plugin-web-extension): Rsbuild plugin for Chrome/web extension.
- [rsbuild-plugin-open-graph](https://github.com/rspack-contrib/rsbuild-plugin-open-graph): Generate Open Graph meta tags.
- [rsbuild-plugin-posthog](https://github.com/m1911star/rsbuild-plugin-posthog): Rsbuild plugin for PostHog.
- [@webx-kit/rsbuild-plugin](https://github.com/tmkx/webx-kit): Rsbuild plugin for Web eXtension development.
- [plugin-sails-content](https://github.com/sailscastshq/sails-content/packages/plugin-sails-content): Rsbuild plugin for [Sails Content](https://docs.sailscasts.com/content/).
- [rsbuild-plugin-html-minifier-terser](https://github.com/rspack-contrib/rsbuild-plugin-html-minifier-terser): An Rsbuild plugin to use `html-minifier-terser` to minify the HTML outputs.
- [rsbuild-plugin-glsl](https://github.com/sakitam-fdd/rsbuild-plugin-glsl): An Rsbuild plugin to import inline (and compress) GLSL shader.
- [rsbuild-plugin-marko](https://github.com/ipseonet/rsbuild-plugin-marko): An Rsbuild plugin to provide support for the Marko template engine.
- [rsbuild-plugin-monaco-editor-nls](https://github.com/zackshen/rsbuild-plugin-monaco-editor-nls): An Rsbuild plugin to localize monaco-editor.
- [rsbuild-plugin-auto-alias](https://github.com/jwyGithub/rsbuild-plugin-auto-alias): Automatically generate alias based on path. 

### Rspress Plugins

- [@rspress/plugin-medium-zoom](https://rspress.dev/plugin/official-plugins/medium-zoom): [medium-zoom](https://github.com/francoischalifour/medium-zoom) plugin, used to zoom in images.
- [@rspress/plugin-last-updated](https://rspress.dev/plugin/official-plugins/last-updated): Support for displaying the last update time of the article.
- [@rspress/plugin-container-syntax](https://rspress.dev/plugin/official-plugins/container-syntax): Support container syntax in Markdown/MDX.
- [@rspress/plugin-typedoc](https://rspress.dev/plugin/official-plugins/typedoc): Integrate [TypeDoc](https://github.com/TypeStrong/typedoc), used to generate API documentation of TS module automatically.
- [@rspress/plugin-preview](https://rspress.dev/plugin/official-plugins/preview): Support preview of code blocks in Markdown/MDX.
- [@rspress/plugin-playground](https://rspress.dev/plugin/official-plugins/playground): Provide a real-time playground to preview the code blocks in Markdown/MDX files.
- [@rspress/plugin-shiki](https://rspress.dev/plugin/official-plugins/shiki): Integrates [Shiki](https://github.com/shikijs/shiki) for code syntax highlighting.
- [@rspress/plugin-rss](https://rspress.dev/plugin/official-plugins/rss): Generates RSS files for specific document pages with [feed](https://github.com/jpmonette/feed).
- [rspress-plugin-translate](https://github.com/byteHulk/rspress-plugin-translate): Automatically translate your content behind the scenes using GPT's.
- [rspress-plugin-shiki](https://github.com/hunghg255/rspress-plugin-shiki): Rspress plugin shiki with transformer.
- [rspress-plugin-remote-page](https://github.com/ulivz/rspress-plugin-remote-page): Load remote markdown file (e.g. README.md) onto your website.
- [rspress-plugin-font-open-sans](https://github.com/rspack-contrib/rspress-plugin-font-open-sans): Use Open Sans as the default font in your Rspress website.
- [rspress-plugin-align-image](https://github.com/linbudu599/rspress-plugins/tree/main/packages/rspress-plugin-align-image): Rspress plugin to align images in markdown.
- [rspress-plugin-directives](https://github.com/linbudu599/rspress-plugins/tree/main/packages/rspress-plugin-directives): Rspress plugin for custom directives support.
- [rspress-plugin-file-tree](https://github.com/linbudu599/rspress-plugins/tree/main/packages/rspress-plugin-file-tree): Rspress plugin that add tree view for file structure display.
- [rspress-plugin-gh-pages](https://github.com/linbudu599/rspress-plugins/tree/main/packages/rspress-plugin-gh-pages): Rspress plugin to add support for automatic deployment to GitHub Pages.
- [rspress-plugin-google-analytics](https://github.com/linbudu599/rspress-plugins/tree/main/packages/rspress-plugin-google-analytics): Rspress plugin for Google Analytics integration.
- [rspress-plugin-vercel-analytics](https://github.com/linbudu599/rspress-plugins/tree/main/packages/rspress-plugin-vercel-analytics): Rspress plugin for Vercel Analytics integration.
- [rspress-plugin-katex](https://github.com/linbudu599/rspress-plugins/tree/main/packages/rspress-plugin-katex): Rspress plugin to add support for rendering math equations using [KaTeX](https://katex.org/).
- [rspress-plugin-live2d](https://github.com/linbudu599/rspress-plugins/tree/main/packages/rspress-plugin-live2d): Rspress plugin for live2d, powered by [on-my-live2d](https://oml2d.com/).
- [rspress-plugin-mermaid](https://github.com/linbudu599/rspress-plugins/tree/main/packages/rspress-plugin-mermaid): Rspress plugin to render [Mermaid](https://mermaid.js.org/#/) diagrams in markdown files.
- [rspress-plugin-reading-time](https://github.com/linbudu599/rspress-plugins/tree/main/packages/rspress-plugin-reading-time): Rspress plugin to display reading time for your document pages.
- [rspress-plugin-supersub](https://github.com/linbudu599/rspress-plugins/tree/main/packages/rspress-plugin-supersub): Rspress plugin to add superscript(`<super></super>`) and subscript(`<sub></sub>`) support.
- [rspress-plugin-toc](https://github.com/linbudu599/rspress-plugins/tree/main/packages/rspress-plugin-toc): Rspress plugin that injects a table of contents into the page.
- [rspress-plugin-clarity](https://github.com/jl917/rspress-plugin-clarity): Rspress plugin for [Clarity](https://clarity.microsoft.com/) integration.
- [rspress-plugin-sitemap](https://github.com/jl917/rspress-plugin-sitemap): Automatically generate SEO-related sitemaps.
- [rspress-plugin-mention-github](https://github.com/hunghg255/rspress-plugin-mention-github): Rspress plugin mention github user, or any link.
- [rspress-plugin-changelog](https://github.com/baranwang/rspress-plugin-changelog): Generates changelog pages, fetching release information from GitHub and GitLab repositories.
- [rspress-plugin-annotation-words](https://github.com/2heal1/rspress-plugin-annotation-words): An Rspress plugin to support annotation words.

## Deployment

- [Zephyr Cloud](https://zephyr-cloud.io): A cloud-agnostic deployment platform offering sub-seconds `deploy from one command` experience.

## Libraries

- [@rspack/dev-server](https://github.com/web-infra-dev/rspack-dev-server): Dev server for Rspack, provides the same API as webpack-dev-server.
- [@rspack/lite-tapable](https://github.com/rspack-contrib/rspack-lite-tapable): Lite weight tapable for Rspack.
- [rspack-chain](https://github.com/rspack-contrib/rspack-chain): A chaining API to generate and simplify the modification of Rspack configurations.
- [Sails Shipwright](https://github.com/sailshq/sails-hook-shipwright) - The modern asset pipeline for [Sails](https://sailsjs.com) powered by Rsbuild.
- [rspackify](https://github.com/SyMind/rspackify): Experience lightning-fast builds by instantly switching from webpack to Rspack.
- [Spinpack](https://github.com/denniscual/spinpack): A CLI tool that turbocharges the developer server experience for CRA projects with Rspack.

## Blogs

Blogs from the Rspack team:

- [rspack.dev/blog/](https://rspack.dev/blog/)
- [web-infra-dev/discussions](https://github.com/orgs/web-infra-dev/discussions)

Blogs from the community:

- [2024-09] [A bundler story: migrating from Webpack to Rspack](https://medium.com/alan/a-bundler-story-migrating-from-webpack-to-rspack-f548c62f757d)
- [2024-08] [Lessons learned switching to Rspack](https://birtles.blog/2024/08/14/lessons-learned-switching-to-rspack/)
- [2024-08] [Why Moving to Rspack and How to Use It with Bazel](https://medium.com/@yanirmanor/why-moving-to-rspack-and-how-to-use-it-with-bazel-9f66139fe493)
- [2024-08] [Module Federation users now have a clear upgrade path](https://medium.com/@gfox1984/module-federation-users-now-have-a-clear-upgrade-path-1701de23f58e)
- [2024-08] [Optimizing SPA load times with async chunks preloading (use Rsbuild)](https://mmazzarolo.com/blog/2024-08-13-async-chunk-preloading-on-load/)
- [2024-06] [Micro Frontend Setup with Nx, Rspack, Module Federation 2.0 and React](https://medium.com/@soumyanildas/micro-frontend-setup-with-nx-rspack-module-federation-2-0-and-react-698674edb09f)
- [2024-06] [From Webpack to Rspack: Slashing Build Times Effectively](https://medium.com/panorays-r-d-blog/from-webpack-to-rspack-slashing-build-times-effectively-0674fd3cc284)
- [2024-02] [Why I'm Bullish on Rspack](https://www.raygesualdo.com/posts/bullish-on-rspack/)
- [2024-02] [Rsdoctor: A Bundle Analysis Solution](https://scriptedalchemy.medium.com/rsdoctor-a-bundle-analysis-solution-ee3f720e0347)
- [2024-02] [Microfrontends with Module Federation and Rspack — Simple example](https://medium.com/@alexefimenko/microfrontends-with-module-federation-and-rspack-simple-example-730f4e6308a7)
- [2024-02] [Bun, Biome/OXC, AI Tools and Rsbuild](https://onwebfocus.com/bun)
- [2024-01] [How I migrated from CRA to Rsbuild](https://dev.to/verthon/how-i-migrated-from-cra-to-rsbuild-4ia8)
- [2024-01] [Module Federation gets upgraded, and Rspack supports it](https://scriptedalchemy.medium.com/emodule-federation-gets-upgraded-and-rspack-supports-it-5ddb0d1e9546)
- [2023-10] [Why you should migrate to Rspack from webpack](https://blog.logrocket.com/migrate-rspack-webpack/)
- [2023-08] [Rust Port of Webpack? Rspack, the New Kid on the Block](https://blog.stackademic.com/rust-port-of-webpack-rspack-the-new-kid-on-the-block-c3a3de569bfb)
- [2023-04] [What is Rspack? And how does it compare to Webpack in under 5 minutes?](https://www.hamzak.xyz/blog-posts/what-is-rspack-and-how-does-it-compare-to-webpack)
- [2023-03] [Rspack — Getting up to speed with Nx](https://blog.nrwl.io/rspack-getting-up-to-speed-with-nx-4c34540bccf2)

社区的中文博客：

- [2024-10] [我把大型团队项目从 Vite 前端迁移到了 Rsbuild，收益如何？](https://juejin.cn/post/7425804396292325414)
- [2024-09] [[译] 一个关于打包工具的故事：从 webpack 迁移到 Rspack](https://juejin.cn/post/7425598941859676170)
- [2024-08] [开发体验的彻底提升，从 Vite 迁移到 Rspack](https://moonvy.com/blog/post/2024/migrate-vite-to-rsbuild/)
- [2024-08] [译：前 Firefox 工程师迁移到 Rspack 的经验教训](https://juejin.cn/post/7402554147276980224)
- [2024-07] [基于 Rspack 实现大仓应用构建提效实践](https://juejin.cn/post/7389925302020014118)

## Videos

- [2024-07]: [The First Real Webpack Alternative (Written in Rust!)](https://www.youtube.com/watch?v=Vn2Rq2uktLE&t=37s)
- [2024-07]: [Microfrontends with Module Federation, Rspack, React and Bit](https://www.youtube.com/watch?v=4CQEPBLxU_g&t=13s)
- [2024-06]: [Rsbuild is 3x faster than Vite](https://www.youtube.com/watch?v=w8mL_HiN9Qo&t=3s)
- [2024-02]: [Mastering Micro-Frontends With Rspack and Module Federation](https://www.youtube.com/watch?v=32_EikGKESk)
- [2024-01]: [Micro Frontends - Rspack and Module Federation v1.5](https://www.youtube.com/watch?v=_HWWaPk1vRE&t=4s)
- [2023-03]: [Rspack! The Successor of Webpack?](https://www.youtube.com/watch?v=jGTE7xAcg24)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Web Infra](https://github.com/web-infra-dev) has waived all copyright and related or neighboring rights to this work.
