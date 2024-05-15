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
- [License](#license)

## Resources

### Official Resources

- [Rspack Doc](https://rspack.dev/)
- [Rspack GitHub Repo](https://github.com/web-infra-dev/rspack)
- [Rspack Release Notes](https://github.com/web-infra-dev/rspack/releases)
- [Rspack Examples](https://github.com/rspack-contrib/rspack-examples): Examples for Rspack, Rsbuild, Rspress and Rsdoctor.
- [Rsfamily Design Resources](https://github.com/rspack-contrib/rsfamily-desgin-resources): Design resources for Rspack, Rsbuild, Rspress and Rsdoctor.

### Ecosystem

- [Rsbuild Doc](https://rsbuild.dev/): The Rspack-based build tool.
- [Rspress Doc](https://rspress.dev/): A fast Rspack-based static site generator.
- [Rsdoctor Doc](https://rsdoctor.dev/): A one-stop build analyzer for Rspack and Webpack.
- [Modern.js Doc](https://modernjs.dev/): A progressive React framework for web development.

## Starter

### Rspack Starter

- [rspack-react-router-starter](https://github.com/ulivz/rspack-react-router-starter)
- [rspack for create-react-app](https://github.com/yanhaijing/rspack-cra)
- [electron-forge-rspack-template](https://github.com/noshower/electron-forge-rspack-template)
- [shark](https://github.com/h7ml/shark): A React project with Rspack, Ant Design, Ant Design Pro Components, Antd@5 React@18 AntV G2Plot, ahooks, react-use, Axios, i18next, localforage, Mock.js, NProgress, and more.

### Rsbuild Starter

- [rsbuild_vue3_h5_template](https://github.com/DMaiGit/rsbuild_vue3_h5_template): A project template for Vue 3. It includes popular libraries such as Axios, Pinia, Vant, and Vue Router.
- [rsbuild-chrome-extension-boilerplate-react](https://github.com/filc-dev/rsbuild-chrome-extension-boilerplate-react): Chrome extension boilerplate for Rsbuild.
- [rsbuild-plugin-template](https://github.com/rspack-contrib/rsbuild-plugin-template): Use this template to create your own Rsbuild plugin.

## Plugins

### Rspack Plugins

- [rspack-manifest-plugin](https://github.com/rspack-contrib/rspack-manifest-plugin): A Rspack plugin for generating an asset manifest.
- [rspack-plugin-dotenv](https://github.com/rspack-contrib/rspack-plugins/tree/main/packages/plugin-dotenv): A secure rspack plugin that supports dotenv and other environment variables.
- [rspack-plugin-virtual-module](https://github.com/rspack-contrib/rspack-plugins/tree/main/packages/plugin-virtual-module): A plugin for rspack that allows you to create virtual modules.
- [html-rspack-plugin](https://github.com/rspack-contrib/html-rspack-plugin): Generate files to serve your Rspack bundles.
- [@aaroon/workbox-rspack-plugin](https://github.com/Clarkkkk/workbox-rspack-plugin): A plugin to use workbox in Rspack.
- [inject-manifest-plugin](https://github.com/tobua/inject-manifest-plugin): Injects a Workbox PWA manifest into a Service Worker.

You can also use most of the webpack plugins in Rspack or Rsbuild, such as:

- [case-sensitive-paths-webpack-plugin](https://github.com/Urthen/case-sensitive-paths-webpack-plugin): Enforces case sensitive paths of all required modules.
- [clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin): Remove your build folder before building.
- [compression-webpack-plugin](https://github.com/webpack-contrib/compression-webpack-plugin): Prepare compressed versions of assets to serve them with Content-Encoding.
- [css-minimizer-webpack-plugin](https://github.com/webpack-contrib/css-minimizer-webpack-plugin): Uses cssnano to optimize and minify your CSS.
- [eslint-webpack-plugin](https://github.com/webpack-contrib/eslint-webpack-plugin): Uses eslint to find and fix problems in your JavaScript code.
- [fork-ts-checker-webpack-plugin](https://github.com/TypeStrong/fork-ts-checker-webpack-plugin): Runs TypeScript type checker on a separate process.
- [html-webpack-plugin](https://github.com/jantimon/html-webpack-plugin): Simplifies creation of HTML files to serve your bundles.
- [webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer): Visualize size of webpack output files with an interactive zoomable treemap.
- [@vanilla-extract/webpack-plugin](https://github.com/vanilla-extract-css/vanilla-extract): Integrating vanilla-extract with webpack / Rspack.
- [@sentry/webpack-plugin](https://github.com/getsentry/sentry-javascript-bundler-plugins): Provides source map and release management support for Sentry.

You can also use most of the [unplugin](https://github.com/unplugin) in Rspack or Rsbuild, such as:

- [unplugin-vue-components](https://github.com/unplugin/unplugin-vue-components): On-demand components auto importing for Vue.
- [unplugin-auto-import](https://github.com/unplugin/unplugin-auto-import): Auto import APIs on-demand.
- [unplugin-stylex](https://github.com/eryue0220/unplugin-stylex): StyleX integration for Rspack.
- [@arco-plugins/unplugin-react](https://www.npmjs.com/package/@arco-plugins/unplugin-react): A plugin to help you use Arco Design React.

### Rsbuild Plugins

- [@rsbuild/plugin-react](https://rsbuild.dev/plugins/list/plugin-react): Provides support for React.
- [@rsbuild/plugin-svgr](https://rsbuild.dev/plugins/list/plugin-svgr): Support convert SVG to React components.
- [@rsbuild/plugin-styled-components](https://rsbuild.dev/plugins/list/plugin-styled-components): Provides compile-time support for styled-components.
- [@rsbuild/plugin-vue](https://rsbuild.dev/plugins/list/plugin-vue): Provides support for Vue 3 SFC (Single File Components).
- [@rsbuild/plugin-vue-jsx](https://rsbuild.dev/plugins/list/plugin-vue-jsx): Provides support for Vue 3 JSX / TSX syntax.
- [@rsbuild/plugin-vue2](https://rsbuild.dev/plugins/list/plugin-vue2): Provides support for Vue 2 SFC (Single File Components).
- [@rsbuild/plugin-vue2-jsx](https://rsbuild.dev/plugins/list/plugin-vue2-jsx): Provides support for Vue 2 JSX / TSX syntax.
- [@rsbuild/plugin-preact](https://rsbuild.dev/plugins/list/plugin-preact): Provides support for Preact.
- [@rsbuild/plugin-svelte](https://rsbuild.dev/plugins/list/plugin-svelte): Provides support for Svelte components (`.svelte` files).
- [@rsbuild/plugin-assets-retry](https://rsbuild.dev/plugins/list/plugin-assets-retry): Used to automatically resend requests when static assets fail to load.
- [@rsbuild/plugin-babel](https://rsbuild.dev/plugins/list/plugin-babel): Provides support for Babel transpilation capabilities.
- [@rsbuild/plugin-basic-ssl](https://rsbuild.dev/plugins/list/plugin-basic-ssl): Generate an untrusted, self-signed certificate for the HTTPS server.
- [@rsbuild/plugin-eslint](https://rsbuild.dev/plugins/list/plugin-eslint): Used to run ESLint checks during the compilation.
- [@rsbuild/plugin-type-check](https://rsbuild.dev/plugins/list/plugin-type-check): Used to run TypeScript type checker on a separate process.
- [@rsbuild/plugin-image-compress](https://rsbuild.dev/plugins/list/plugin-image-compress): Compress the image resources used in the project.
- [@rsbuild/plugin-mdx](https://rsbuild.dev/plugins/list/plugin-mdx): Provide support for MDX.
- [@rsbuild/plugin-node-polyfill](https://rsbuild.dev/plugins/list/plugin-node-polyfill): Used to inject polyfills of Node core modules in the browser side.
- [@rsbuild/plugin-lightningcss](https://rsbuild.dev/plugins/list/plugin-lightningcss): Used to use LightningCSS as CSS transformer and minimizer.
- [@rsbuild/plugin-source-build](https://rsbuild.dev/plugins/list/plugin-source-build): This plugin is designed for the monorepo scenario. It supports referencing source code from other subdirectories and performs build and hot update.
- [@rsbuild/plugin-stylus](https://rsbuild.dev/plugins/list/plugin-stylus): Use Stylus as the CSS preprocessor.
- [@rsbuild/plugin-check-syntax](https://rsbuild.dev/plugins/list/plugin-check-syntax): Used to analyze the syntax compatibility of artifacts, to see if there are any advanced syntaxes that may cause compatibility issues.
- [@rsbuild/plugin-css-minimizer](https://rsbuild.dev/plugins/list/plugin-css-minimizer): Used to customize CSS minimizer, switch to [cssnano](https://cssnano.co/) or other tools for CSS compression.
- [@rsbuild/plugin-pug](https://rsbuild.dev/plugins/list/plugin-pug): Provides support for the Pug template engine.
- [@rsbuild/plugin-rem](https://rsbuild.dev/plugins/list/plugin-rem): Implements the rem adaptive layout for mobile pages.
- [@rsbuild/plugin-umd](https://rsbuild.dev/plugins/list/plugin-umd): Used to build outputs in UMD format.
- [@rsbuild/plugin-yaml](https://rsbuild.dev/plugins/list/plugin-yaml): Used to import YAML files and convert them into JavaScript objects.
- [@rsbuild/plugin-toml](https://rsbuild.dev/plugins/list/plugin-toml): Used to import TOML files and convert them into JavaScript objects.
- [@rsbuild/plugin-solid](https://rsbuild.dev/plugins/list/plugin-solid): Provides support for Solid.
- [rsbuild-plugin-react-inspector](https://github.com/hunghg255/rsbuild-plugin-react-inspector): Allows automatic jumping to the local IDE when clicking on a browser element.
- [rsbuild-plugin-svelte-inspector](https://github.com/hunghg255/rsbuild-plugin-svelte-inspector): Allows automatic jumping to the local IDE when clicking on a browser element.
- [rsbuild-plugin-vue-inspector](https://github.com/hunghg255/rsbuild-plugin-vue-inspector): Allows automatic jumping to the local IDE when clicking on a browser element.
- [rsbuild-plugin-print](https://github.com/hunghg255/rsbuild-plugin-print): Print text, show host with qrcode.
- [rsbuild-plugin-console-debug](https://github.com/hunghg255/rsbuild-plugin-console-debug): Output debug information in the console.
- [rsbuild-plugin-generate-file](https://github.com/sumy7/rsbuild-plugin-generate-file): Generate static file and write them to dist folder after packaging.
- [rsbuild-plugin-google-analytics](https://github.com/rspack-contrib/rsbuild-plugin-google-analytics): Setup Google Analytics in your website.
- [rsbuild-plugin-web-extension](https://github.com/filc-dev/rsbuild-plugin-web-extension): Rsbuild plugin for Chrome/web extension.
- [rsbuild-plugin-open-graph](https://github.com/rspack-contrib/rsbuild-plugin-open-graph): Generate Open Graph meta tags.
- [rsbuild-plugin-posthog](https://github.com/m1911star/rsbuild-plugin-posthog): Rsbuild plugin for PostHog.
- [rsbuild-plugin-vue-legacy](https://github.com/skymoonya/rsbuild-plugin-vue-legacy): Support for Vue versions below 2.7 by setting an alias for `vue`.
- [@webx-kit/rsbuild-plugin](https://github.com/tmkx/webx-kit): Rsbuild plugin for Web eXtension development.

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

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Web Infra](https://github.com/web-infra-dev) has waived all copyright and related or neighboring rights to this work.
