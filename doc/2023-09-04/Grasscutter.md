# Grasscutters/Grasscutter安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698397675933450240.svg)](https://www.murphysec.com/console/report/1691418686635528192/1698397675933450240)

仓库描述：A server software reimplementation for a certain anime game.

仓库地址：[https://github.com/Grasscutters/Grasscutter](https://github.com/Grasscutters/Grasscutter)

| star：14120 | watch：178 | fork：4314 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-03 21:26:10 | 许可证：AGPL-3.0 |
| 最近检测时间：2023-09-04 02:10:43 | 组件总数：316 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|Vite 安全漏洞|使用不正确的解析名称或索引|[MPS-o473-85mg](https://www.oscs1024.com/hd/MPS-o473-85mg)|CVE-2023-34092|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|vite|4.2.1|4.3.9|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|semver|6.3.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|242|Low|
|ISC|32|Low|
|CC0-1.0|5|Low|
|BSD-2-Clause|7|Low|
|Apache-2.0|6|Low|
|BSD-3-Clause|10|Low|
|BSD|1|Low|
|CC-BY-4.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|@nodelib/fs.walk|1.2.8|间接依赖|npm|
|postcss-discard-duplicates|5.1.0|间接依赖|npm|
|@babel/runtime|7.21.0|间接依赖|npm|
|at-least-node|1.0.0|间接依赖|npm|
|postcss-font-magician|3.0.0|直接依赖|npm|
|@types/react|18.0.33|间接依赖|npm|
|arg|5.0.2|间接依赖|npm|
|@babel/helper-module-imports|7.21.4|间接依赖|npm|
|postcss-nested|6.0.0|间接依赖|npm|
|jsonfile|6.1.0|间接依赖|npm|
|nth-check|2.1.1|间接依赖|npm|
|@babel/helper-module-transforms|7.21.2|间接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|prop-types|15.8.1|间接依赖|npm|
|didyoumean|1.2.2|间接依赖|npm|
|convert-source-map|1.9.0|间接依赖|npm|
|d3-shape|1.3.7|间接依赖|npm|
|is-glob|4.0.3|间接依赖|npm|
|prettier|2.8.7|直接依赖|npm|
|is-woff|1.0.3|间接依赖|npm|
|node-releases|2.0.10|间接依赖|npm|
|which|1.3.1|间接依赖|npm|
|lines-and-columns|1.2.4|间接依赖|npm|
|@trysound/sax|0.2.0|间接依赖|npm|
|patch-package|6.5.1|直接依赖|npm|
|parse-json|5.2.0|间接依赖|npm|
|universalify|2.0.0|间接依赖|npm|
|domutils|2.8.0|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|postcss-normalize-display-values|5.1.0|间接依赖|npm|
|os-tmpdir|1.0.2|间接依赖|npm|
|slash|2.0.0|间接依赖|npm|
|is-ci|2.0.0|间接依赖|npm|
|@swc/core-win32-x64-msvc|1.3.44|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|caniuse-api|3.0.0|间接依赖|npm|
|css-tree|1.1.3|间接依赖|npm|
|csso|4.2.0|间接依赖|npm|
|postcss-merge-longhand|5.1.7|间接依赖|npm|
|chain-function|1.0.1|间接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|vite-plugin-singlefile|0.13.5|直接依赖|npm|
|postcss-normalize-timing-functions|5.1.0|间接依赖|npm|
|postcss-js|4.0.1|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|queue-microtask|1.2.3|间接依赖|npm|
|d3-zoom|3.0.0|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|colord|2.9.3|间接依赖|npm|
|parent-module|1.0.1|间接依赖|npm|
|@babel/helper-validator-option|7.21.0|间接依赖|npm|
|postcss-normalize-positions|5.1.1|间接依赖|npm|
|is-woff2|1.0.0|间接依赖|npm|
|minimist|1.2.8|间接依赖|npm|
|is-wsl|2.2.0|间接依赖|npm|
|scheduler|0.23.0|间接依赖|npm|
|pify|2.3.0|间接依赖|npm|
|postcss-normalize-url|5.1.0|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|error-ex|1.3.2|间接依赖|npm|
|postcss-discard-comments|5.1.2|间接依赖|npm|
|iconv-lite|0.4.24|间接依赖|npm|
|postcss-import|14.1.0|间接依赖|npm|
|immutable|4.3.0|间接依赖|npm|
|d3-selection|3.0.0|间接依赖|npm|
|postcss-reduce-transforms|5.1.0|间接依赖|npm|
|ci-info|2.0.0|间接依赖|npm|
|cssnano|5.1.15|直接依赖|npm|
|dom-helpers|5.2.1|间接依赖|npm|
|binary-extensions|2.2.0|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|normalize-range|0.1.2|间接依赖|npm|
|@jridgewell/resolve-uri|3.1.0|间接依赖|npm|
|@babel/core|7.21.4|间接依赖|npm|
|@svgr/babel-plugin-transform-svg-component|6.5.1|间接依赖|npm|
|run-parallel|1.2.0|间接依赖|npm|
|regenerator-runtime|0.13.11|间接依赖|npm|
|commander|7.2.0|间接依赖|npm|
|lru-cache|5.1.1|间接依赖|npm|
|thenify-all|1.6.0|间接依赖|npm|
|cssesc|3.0.0|间接依赖|npm|
|@svgr/babel-plugin-transform-react-native-svg|6.5.1|间接依赖|npm|
|react-is|16.13.1|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|postcss|8.4.21|间接依赖|npm|
|tosource|2.0.0-alpha.3|间接依赖|npm|
|postcss-load-config|4.0.1|间接依赖|npm|
|fast-glob|3.2.12|间接依赖|npm|
|picomatch|2.3.1|间接依赖|npm|
|@types/parse-json|4.0.0|间接依赖|npm|
|reusify|1.0.4|间接依赖|npm|
|json-parse-even-better-errors|2.3.1|间接依赖|npm|
|postcss-ordered-values|5.1.3|间接依赖|npm|
|postcss-reduce-initial|5.1.2|间接依赖|npm|
|svg-parser|2.0.4|间接依赖|npm|
|shebang-regex|1.0.0|间接依赖|npm|
|rollup|3.20.2|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|chokidar|3.5.3|间接依赖|npm|
|gensync|1.0.0-beta.2|间接依赖|npm|
|json5|2.2.3|间接依赖|npm|
|estree-walker|2.0.2|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|loose-envify|1.4.0|间接依赖|npm|
|is-otf|0.1.2|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|@swc/core|1.3.44|间接依赖|npm|
|postcss-normalize-repeat-style|5.1.1|间接依赖|npm|
|any-promise|1.3.0|间接依赖|npm|
|@babel/helper-validator-identifier|7.19.1|间接依赖|npm|
|@babel/code-frame|7.21.4|间接依赖|npm|
|globrex|0.1.2|间接依赖|npm|
|entities|2.2.0|间接依赖|npm|
|@babel/traverse|7.21.4|间接依赖|npm|
|clsx|1.2.1|间接依赖|npm|
|@svgr/babel-plugin-remove-jsx-empty-expression|7.0.0|间接依赖|npm|
|domhandler|4.3.1|间接依赖|npm|
|is-ttf|0.2.2|间接依赖|npm|
|brotli|1.3.3|间接依赖|npm|
|cssnano-preset-default|5.2.14|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|color-name|1.1.4|间接依赖|npm|
|pirates|4.0.5|间接依赖|npm|
|vite|4.2.1|直接依赖|npm|
|is-binary-path|2.1.0|间接依赖|npm|
|d3-dsv|2.0.0|间接依赖|npm|
|@jridgewell/trace-mapping|0.3.17|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|@babel/helper-environment-visitor|7.18.9|间接依赖|npm|
|@svgr/babel-preset|6.5.1|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|dequal|2.0.3|间接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|@babel/helper-compilation-targets|7.21.4|间接依赖|npm|
|is-arrayish|0.2.1|间接依赖|npm|
|@jridgewell/set-array|1.1.2|间接依赖|npm|
|mdn-data|2.0.14|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|fraction.js|4.2.0|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|yaml|1.10.2|间接依赖|npm|
|@yarnpkg/lockfile|1.1.0|间接依赖|npm|
|@types/scheduler|0.16.3|间接依赖|npm|
|dlv|1.1.3|间接依赖|npm|
|ts-interface-checker|0.1.13|间接依赖|npm|
|d3-drag|3.0.0|间接依赖|npm|
|path-type|4.0.0|间接依赖|npm|
|d3-timer|3.0.1|间接依赖|npm|
|@svgr/hast-util-to-babel-ast|6.5.1|间接依赖|npm|
|cross-spawn|6.0.5|间接依赖|npm|
|anymatch|3.1.3|间接依赖|npm|
|vite-tsconfig-paths|4.0.8|直接依赖|npm|
|open|7.4.2|间接依赖|npm|
|cssnano-utils|3.1.0|间接依赖|npm|
|esbuild|0.17.15|间接依赖|npm|
|@babel/parser|7.21.4|间接依赖|npm|
|@rollup/plugin-dsv|3.0.2|直接依赖|npm|
|css-select|4.3.0|间接依赖|npm|
|@types/estree|1.0.0|间接依赖|npm|
|browserslist|4.21.5|间接依赖|npm|
|fastq|1.15.0|间接依赖|npm|
|@svgr/babel-plugin-svg-em-dimensions|6.5.1|间接依赖|npm|
|postcss-normalize-unicode|5.1.1|间接依赖|npm|
|@esbuild/win32-x64|0.17.15|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|debug|4.3.4|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|postcss-calc|8.2.4|间接依赖|npm|
|js-base64|2.1.9|直接依赖|npm|
|react|18.2.0|直接依赖|npm|
|thenify|3.3.1|间接依赖|npm|
|lilconfig|2.1.0|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|path-key|2.0.1|间接依赖|npm|
|postcss-discard-empty|5.1.1|间接依赖|npm|
|tailwindcss|3.3.1|直接依赖|npm|
|glob-parent|5.1.2|间接依赖|npm|
|sucrase|3.31.0|间接依赖|npm|
|rw|1.3.3|间接依赖|npm|
|@babel/helper-string-parser|7.19.4|间接依赖|npm|
|d3-dispatch|3.0.1|间接依赖|npm|
|caniuse-lite|1.0.30001473|间接依赖|npm|
|postcss-convert-values|5.1.3|间接依赖|npm|
|@types/react-dom|18.0.11|直接依赖|npm|
|events|3.3.0|直接依赖|npm|
|postcss-value-parser|4.2.0|间接依赖|npm|
|tmp|0.0.33|间接依赖|npm|
|directory-fonts-complete|1.2.0|间接依赖|npm|
|css-what|6.1.0|间接依赖|npm|
|stylehacks|5.1.1|间接依赖|npm|
|postcss-svgo|5.1.0|间接依赖|npm|
|@babel/types|7.21.4|间接依赖|npm|
|micromatch|4.0.5|间接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|cosmiconfig|7.1.0|间接依赖|npm|
|base64-js|1.5.1|间接依赖|npm|
|@babel/compat-data|7.21.4|间接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.14|间接依赖|npm|
|clone|2.1.2|间接依赖|npm|
|import-fresh|3.3.0|间接依赖|npm|
|semver|6.3.0|间接依赖|npm|
|postcss-minify-params|5.1.4|间接依赖|npm|
|mz|2.7.0|间接依赖|npm|
|amdefine|1.0.1|直接依赖|npm|
|supports-preserve-symlinks-flag|1.0.0|间接依赖|npm|
|d3-transition|3.0.1|间接依赖|npm|
|@svgr/babel-plugin-remove-jsx-attribute|7.0.0|间接依赖|npm|
|fs-extra|9.1.0|间接依赖|npm|
|nanoid|3.3.6|间接依赖|npm|
|svgo|2.8.0|间接依赖|npm|
|sass|1.60.0|直接依赖|npm|
|@types/prop-types|15.7.5|间接依赖|npm|
|camelcase|6.3.0|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|klaw-sync|6.0.0|间接依赖|npm|
|@jridgewell/gen-mapping|0.1.1|间接依赖|npm|
|@babel/highlight|7.18.6|间接依赖|npm|
|postcss-discard-overridden|5.1.0|间接依赖|npm|
|d3-ease|3.0.1|间接依赖|npm|
|@svgr/core|6.5.1|间接依赖|npm|
|lodash.uniq|4.5.0|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|tsconfck|2.1.1|间接依赖|npm|
|@ampproject/remapping|2.2.0|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|read-cache|1.0.0|间接依赖|npm|
|d3-path|1.0.9|间接依赖|npm|
|callsites|3.1.0|间接依赖|npm|
|d3-interpolate|3.0.1|间接依赖|npm|
|is-docker|2.2.1|间接依赖|npm|
|@types/react-virtualized|9.21.21|直接依赖|npm|
|postcss-minify-gradients|5.1.1|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|bootstrap-fonts-complete|1.0.0|间接依赖|npm|
|graceful-fs|4.2.11|间接依赖|npm|
|readdirp|3.6.0|间接依赖|npm|
|@babel/helper-simple-access|7.20.2|间接依赖|npm|
|postcss-normalize-whitespace|5.1.1|间接依赖|npm|
|@svgr/babel-plugin-replace-jsx-attribute-value|6.5.1|间接依赖|npm|
|@types/d3-dsv|3.0.1|间接依赖|npm|
|warning|3.0.0|间接依赖|npm|
|glob|7.1.6|间接依赖|npm|
|react-dom|18.2.0|直接依赖|npm|
|postcss-minify-font-values|5.1.0|间接依赖|npm|
|csstype|3.1.2|间接依赖|npm|
|globals|11.12.0|间接依赖|npm|
|camelcase-css|2.0.1|间接依赖|npm|
|b3b|0.0.1|间接依赖|npm|
|d3-hierarchy|1.1.9|间接依赖|npm|
|find-yarn-workspace-root|2.0.0|间接依赖|npm|
|css-declaration-sorter|6.4.0|间接依赖|npm|
|@types/node|18.15.11|直接依赖|npm|
|jsesc|2.5.2|间接依赖|npm|
|rimraf|2.7.1|间接依赖|npm|
|@babel/helper-function-name|7.21.0|间接依赖|npm|
|@types/events|3.0.0|直接依赖|npm|
|object-hash|3.0.0|间接依赖|npm|
|electron-to-chromium|1.4.349|间接依赖|npm|
|google-fonts-complete|2.1.1|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|lodash.memoize|4.1.2|间接依赖|npm|
|to-fast-properties|2.0.0|间接依赖|npm|
|typescript|4.9.5|直接依赖|npm|
|@rollup/pluginutils|5.0.2|间接依赖|npm|
|boolbase|1.0.0|间接依赖|npm|
|@types/d3-hierarchy|1.1.8|间接依赖|npm|
|@babel/template|7.20.7|间接依赖|npm|
|stable|0.1.8|间接依赖|npm|
|source-map|0.6.1|间接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|is-number|7.0.0|间接依赖|npm|
|postcss-minify-selectors|5.2.1|间接依赖|npm|
|vite-plugin-svgr|2.4.0|直接依赖|npm|
|quick-lru|5.1.1|间接依赖|npm|
|source-map-js|1.0.2|间接依赖|npm|
|@babel/generator|7.21.4|间接依赖|npm|
|react-lifecycles-compat|3.0.4|间接依赖|npm|
|react-d3-tree|3.6.1|直接依赖|npm|
|shebang-command|1.2.0|间接依赖|npm|
|merge2|1.4.1|间接依赖|npm|
|normalize-url|6.1.0|间接依赖|npm|
|is-eot|1.0.0|间接依赖|npm|
|nice-try|1.0.5|间接依赖|npm|
|@babel/helper-split-export-declaration|7.18.6|间接依赖|npm|
|react-icons|4.8.0|直接依赖|npm|
|@bkrem/react-transition-group|1.3.3|间接依赖|npm|
|resolve|1.22.1|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|uuid|8.3.2|间接依赖|npm|
|postcss-colormin|5.3.1|间接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|d3-color|3.1.0|间接依赖|npm|
|@nodelib/fs.stat|2.0.5|间接依赖|npm|
|picocolors|1.0.0|间接依赖|npm|
|postcss-selector-parser|6.0.11|间接依赖|npm|
|autoprefixer|10.4.14|直接依赖|npm|
|postcss-normalize-string|5.1.0|间接依赖|npm|
|@vitejs/plugin-react-swc|3.2.0|直接依赖|npm|
|is-core-module|2.11.0|间接依赖|npm|
|@nodelib/fs.scandir|2.1.5|间接依赖|npm|
|postcss-unique-selectors|5.1.1|间接依赖|npm|
|jiti|1.18.2|间接依赖|npm|
|resolve-from|4.0.0|间接依赖|npm|
|@babel/helper-hoist-variables|7.18.6|间接依赖|npm|
|@svgr/plugin-jsx|6.5.1|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|@svgr/babel-plugin-add-jsx-attribute|6.5.1|间接依赖|npm|
|@babel/helpers|7.21.0|间接依赖|npm|
|yallist|3.1.1|间接依赖|npm|
|postcss-normalize-charset|5.1.0|间接依赖|npm|
|es6-promise|2.3.0|直接依赖|npm|
|react-virtualized|9.22.3|直接依赖|npm|
|update-browserslist-db|1.0.10|间接依赖|npm|
|postcss-merge-rules|5.1.4|间接依赖|npm|
|@svgr/babel-plugin-svg-dynamic-title|6.5.1|间接依赖|npm|
|react-collapsible|2.10.0|直接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)