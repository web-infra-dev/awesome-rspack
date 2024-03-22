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
- [Get Started](#get-started)
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

### Ecosystem

- [Rsbuild Doc](https://rsbuild.dev/): The Rspack-based build tool.
- [Rspress Doc](https://rspress.dev/): A fast Rspack-based static site generator.
- [Rsdoctor Doc](https://rsdoctor.dev/): A one-stop build analyzer for Rspack and Webpack.
- [Modern.js Doc](https://modernjs.dev/): A progressive React framework for web development.

### Starter

- [rspack-react-router-starter](https://github.com/ulivz/rspack-react-router-starter)
- [rspack for create-react-app](https://github.com/yanhaijing/rspack-cra)
- [electron-forge-rspack-template](https://github.com/noshower/electron-forge-rspack-template)
- [rsbuild_vue3_h5_template](https://github.com/DMaiGit/rsbuild_vue3_h5_template): A project template for Vue 3. It includes popular libraries such as Axios, Pinia, Vant, and Vue Router.

## Get Started

- [use Rspack](https://rspack.dev/guide/quick-start.html)
- [use Rsbuild](https://rsbuild.dev/guide/start/quick-start)
- [use Rspress](https://rspress.dev/guide/start/getting-started.html)
- [use Rsdoctor](https://rsdoctor.dev/guide/start/quick-start)

## Plugins

### Rspack Plugins

- [rspack-plugin-dotenv](https://github.com/rspack-contrib/rspack-plugins/tree/main/packages/plugin-dotenv): A secure rspack plugin that supports dotenv and other environment variables.
- [rspack-plugin-virtual-module](https://github.com/rspack-contrib/rspack-plugins/tree/main/packages/plugin-virtual-module): A plugin for rspack that allows you to create virtual modules.
- [html-rspack-plugin](https://github.com/rspack-contrib/html-rspack-plugin): Generate files to serve your Rspack bundles.
- [@aaroon/workbox-rspack-plugin](https://github.com/Clarkkkk/workbox-rspack-plugin): A plugin to use workbox in Rspack.

You can also use most of the [unplugin](https://github.com/unplugin) in Rspack or Rsbuild, such as:

- [unplugin-vue-components](https://github.com/unplugin/unplugin-vue-components): On-demand components auto importing for Vue.
- [unplugin-auto-import](https://github.com/unplugin/unplugin-auto-import): Auto import APIs on-demand.

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

### Rspress Plugins

- [@rspress/plugin-medium-zoom](https://rspress.dev/plugin/official-plugins/medium-zoom): [medium-zoom](https://github.com/francoischalifour/medium-zoom) plugin, used to zoom in images.
- [@rspress/plugin-last-updated](https://rspress.dev/plugin/official-plugins/last-updated): Support for displaying the last update time of the article.
- [@rspress/plugin-container-syntax](https://rspress.dev/plugin/official-plugins/container-syntax): Support container syntax in Markdown/MDX.
- [@rspress/plugin-typedoc](https://rspress.dev/plugin/official-plugins/typedoc): Integrate [TypeDoc](https://github.com/TypeStrong/typedoc), used to generate API documentation of TS module automatically.
- [@rspress/plugin-preview](https://rspress.dev/plugin/official-plugins/preview): Support preview of code blocks in Markdown/MDX.
- [@rspress/plugin-playground](https://rspress.dev/plugin/official-plugins/playground): Provide a real-time playground to preview the code blocks in Markdown/MDX files.
- [@rspress/plugin-shiki](https://rspress.dev/plugin/official-plugins/shiki): Integrates [Shiki](https://github.com/shikijs/shiki) for code syntax highlighting.
- [rspress-plugin-translate](https://github.com/byteHulk/rspress-plugin-translate): Automatically translate your content behind the scenes using GPT's.
- [rspress-plugin-shiki](https://github.com/hunghg255/rspress-plugin-shiki): Rspress plugin shiki with transformer.
- [rspress-plugin-remote-page](https://github.com/ulivz/rspress-plugin-remote-page): Load remote markdown file (e.g. README.md) onto your website.
- [rspress-plugin-font-open-sans](https://github.com/rspack-contrib/rspress-plugin-font-open-sans): Use Open Sans as the default font in your Rspress website.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Web Infra](https://github.com/web-infra-dev) has waived all copyright and related or neighboring rights to this work.
