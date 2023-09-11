# evanw/esbuild安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1701298071010934784.svg)](https://www.murphysec.com/console/report/1701298070780248064/1701298071010934784)

仓库描述：An extremely fast bundler for the web

仓库地址：[https://github.com/evanw/esbuild](https://github.com/evanw/esbuild)

| star：35974 | watch：295 | fork：1048 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-11 01:41:44 | 许可证：MIT |
| 最近检测时间：2023-09-12 02:14:10 | 组件总数：297 | 漏洞总数：5 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|terser 安全漏洞|ReDoS|[MPS-2022-5145](https://www.oscs1024.com/hd/MPS-2022-5145)|CVE-2022-25858|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|Tauri 原型污染漏洞|原型污染|[MPS-2022-65568](https://www.oscs1024.com/hd/MPS-2022-65568)|CVE-2022-46175|高危|
|Google Go 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2022-9049](https://www.oscs1024.com/hd/MPS-2022-9049)|CVE-2022-29526|中危|
|Webpack 安全漏洞||[MPS-2023-7721](https://www.oscs1024.com/hd/MPS-2023-7721)|CVE-2023-28154|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|json5|2.2.1|2.2.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|terser|5.9.0|5.14.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|webpack|5.75.0|5.76.0|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|golang.org/x/sys|v0.0.0-20220715151400-c0bba94af5f8|0.1.0|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|7.3.5|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|semver|5.7.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|229|Low|
|ISC|13|Low|
|BSD-3-Clause|6|Low|
|BSD-2-Clause|17|Low|
|Apache-2.0|7|Low|
|CC0-1.0|2|Low|
|0BSD|1|Low|
|CC-BY-4.0|3|Low|
|Apache|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|node-releases|2.0.0|间接依赖|npm|
|@parcel/markdown-ansi|2.8.0|间接依赖|npm|
|msgpackr|1.8.1|间接依赖|npm|
|which|2.0.2|间接依赖|npm|
|ansi-styles|4.3.0|间接依赖|npm|
|loose-envify|1.4.0|间接依赖|npm|
|@jridgewell/gen-mapping|0.3.2|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|@parcel/transformer-js|2.8.0|间接依赖|npm|
|react-error-overlay|6.0.9|间接依赖|npm|
|@parcel/cache|2.8.0|间接依赖|npm|
|sprintf-js|1.0.3|间接依赖|npm|
|colorette|2.0.16|间接依赖|npm|
|clone|2.1.2|间接依赖|npm|
|@types/caniuse-lite|1.0.1|间接依赖|npm|
|lru-cache|6.0.0|间接依赖|npm|
|esprima|4.0.1|间接依赖|npm|
|@parcel/transformer-svg|2.8.0|间接依赖|npm|
|shebang-command|2.0.0|间接依赖|npm|
|yaml|1.10.2|间接依赖|npm|
|typescript|4.9.3|直接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|resolve|1.22.1|间接依赖|npm|
|acorn|8.8.1|间接依赖|npm|
|posthtml-parser|0.10.2|间接依赖|npm|
|mdn-data|2.0.14|间接依赖|npm|
|schema-utils|3.1.1|间接依赖|npm|
|@parcel/workers|2.8.0|间接依赖|npm|
|posthtml-render|3.0.0|间接依赖|npm|
|tslib|2.4.1|间接依赖|npm|
|merge-stream|2.0.0|间接依赖|npm|
|@parcel/logger|2.8.0|间接依赖|npm|
|enhanced-resolve|5.12.0|间接依赖|npm|
|@parcel/optimizer-image|2.8.0|间接依赖|npm|
|@types/eslint|8.4.10|间接依赖|npm|
|v8-compile-cache|2.3.0|间接依赖|npm|
|supports-color|7.2.0|间接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|cross-spawn|7.0.3|间接依赖|npm|
|@lmdb/lmdb-linux-arm|2.5.2|间接依赖|npm|
|graceful-fs|4.2.10|间接依赖|npm|
|@types/parse-json|4.0.0|间接依赖|npm|
|parse-json|5.2.0|间接依赖|npm|
|posthtml|0.16.6|间接依赖|npm|
|@webassemblyjs/ieee754|1.11.1|间接依赖|npm|
|@parcel/codeframe|2.8.0|间接依赖|npm|
|@lmdb/lmdb-linux-x64|2.5.2|间接依赖|npm|
|@parcel/runtime-service-worker|2.8.0|间接依赖|npm|
|@webpack-cli/configtest|2.0.0|间接依赖|npm|
|@parcel/reporter-dev-server|2.8.0|间接依赖|npm|
|lightningcss-darwin-arm64|1.17.1|间接依赖|npm|
|electron-to-chromium|1.3.867|间接依赖|npm|
|weak-lru-cache|1.2.2|间接依赖|npm|
|rollup|3.5.1|直接依赖|npm|
|json-parse-even-better-errors|2.3.1|间接依赖|npm|
|postcss-value-parser|4.2.0|间接依赖|npm|
|htmlnano|2.0.3|间接依赖|npm|
|serialize-javascript|6.0.0|间接依赖|npm|
|estraverse|4.3.0|间接依赖|npm|
|@parcel/runtime-js|2.8.0|间接依赖|npm|
|lightningcss|1.17.1|间接依赖|npm|
|domutils|2.8.0|间接依赖|npm|
|@webassemblyjs/wasm-gen|1.11.1|间接依赖|npm|
|abortcontroller-polyfill|1.7.5|间接依赖|npm|
|picocolors|1.0.0|间接依赖|npm|
|import-fresh|3.3.0|间接依赖|npm|
|commander|2.20.3|间接依赖|npm|
|@parcel/graph|2.8.0|间接依赖|npm|
|rechoir|0.8.0|间接依赖|npm|
|@parcel/node-resolver-core|2.8.0|间接依赖|npm|
|caniuse-lite|1.0.30001519|间接依赖|npm|
|commander|7.2.0|间接依赖|npm|
|is-number|7.0.0|间接依赖|npm|
|interpret|3.1.1|间接依赖|npm|
|shallow-clone|3.0.1|间接依赖|npm|
|caniuse-lite|1.0.30001267|间接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|@mdn/browser-compat-data|5.3.9|间接依赖|npm|
|neo-async|2.6.2|间接依赖|npm|
|path-type|4.0.0|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|@types/node|17.0.2|直接依赖|npm|
|@parcel/bundler-default|2.8.0|间接依赖|npm|
|@parcel/namer-default|2.8.0|间接依赖|npm|
|@webassemblyjs/helper-numbers|1.11.1|间接依赖|npm|
|shebang-regex|3.0.0|间接依赖|npm|
|@types/node|14.14.6|直接依赖|npm|
|@msgpackr-extract/msgpackr-extract-linux-arm|2.2.0|间接依赖|npm|
|@parcel/utils|2.8.0|间接依赖|npm|
|@webassemblyjs/helper-wasm-section|1.11.1|间接依赖|npm|
|@jridgewell/resolve-uri|3.1.0|间接依赖|npm|
|is-core-module|2.11.0|间接依赖|npm|
|get-port|4.2.0|间接依赖|npm|
|term-size|2.2.1|间接依赖|npm|
|node-gyp-build|4.5.0|间接依赖|npm|
|react-refresh|0.9.0|间接依赖|npm|
|@webassemblyjs/helper-wasm-bytecode|1.11.1|间接依赖|npm|
|p-try|2.2.0|直接依赖|npm|
|terser|5.16.0|间接依赖|npm|
|typescript|3.5.3|直接依赖|npm|
|@parcel/resolver-default|2.8.0|间接依赖|npm|
|chalk|4.1.2|间接依赖|npm|
|@parcel/packager-css|2.8.0|间接依赖|npm|
|node-releases|2.0.6|间接依赖|npm|
|watchpack|2.4.0|间接依赖|npm|
|lmdb|2.5.2|间接依赖|npm|
|@types/node|20.3.2|间接依赖|npm|
|domelementtype|2.3.0|间接依赖|npm|
|lightningcss-linux-arm64-musl|1.17.1|间接依赖|npm|
|@parcel/source-map|2.1.1|间接依赖|npm|
|kind-of|6.0.3|间接依赖|npm|
|buffer-from|1.1.2|间接依赖|npm|
|parcel|2.8.0|直接依赖|npm|
|@parcel/fs|2.8.0|间接依赖|npm|
|entities|3.0.1|间接依赖|npm|
|loader-runner|4.2.0|间接依赖|npm|
|@parcel/watcher|2.0.7|间接依赖|npm|
|micromatch|4.0.4|间接依赖|npm|
|@types/eslint-scope|3.7.4|间接依赖|npm|
|@parcel/optimizer-terser|2.8.0|间接依赖|npm|
|@parcel/fs-search|2.8.0|间接依赖|npm|
|svgo|2.8.0|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|domhandler|4.3.1|间接依赖|npm|
|@lmdb/lmdb-darwin-x64|2.5.2|间接依赖|npm|
|terser|5.9.0|间接依赖|npm|
|@parcel/packager-raw|2.8.0|间接依赖|npm|
|lightningcss-linux-x64-gnu|1.17.1|间接依赖|npm|
|browserslist|4.21.4|间接依赖|npm|
|lightningcss-win32-x64-msvc|1.17.1|间接依赖|npm|
|lightningcss-linux-arm-gnueabihf|1.17.1|间接依赖|npm|
|es-module-lexer|0.9.3|间接依赖|npm|
|chrome-trace-event|1.0.3|间接依赖|npm|
|@unicode/unicode-15.0.0|1.3.1|直接依赖|npm|
|htmlparser2|7.2.0|间接依赖|npm|
|typescript|4.5.4|直接依赖|npm|
|js-yaml|3.14.0|直接依赖|npm|
|node-addon-api|3.2.1|间接依赖|npm|
|@parcel/transformer-css|2.8.0|间接依赖|npm|
|css-tree|1.1.3|间接依赖|npm|
|@unicode/unicode-3.0.0|1.0.6|直接依赖|npm|
|events|3.3.0|间接依赖|npm|
|@lezer/lr|0.15.8|间接依赖|npm|
|@webassemblyjs/ast|1.11.1|间接依赖|npm|
|@webassemblyjs/helper-buffer|1.11.1|间接依赖|npm|
|resolve-from|5.0.0|间接依赖|npm|
|@msgpackr-extract/msgpackr-extract-darwin-arm64|2.2.0|间接依赖|npm|
|mime-db|1.50.0|间接依赖|npm|
|@parcel/diagnostic|2.8.0|间接依赖|npm|
|lightningcss-linux-x64-musl|1.17.1|间接依赖|npm|
|@parcel/runtime-react-refresh|2.8.0|间接依赖|npm|
|punycode|2.1.1|间接依赖|npm|
|@parcel/config-default|2.8.0|间接依赖|npm|
|locate-path|5.0.0|间接依赖|npm|
|@parcel/transformer-json|2.8.0|间接依赖|npm|
|react|17.0.1|直接依赖|npm|
|@parcel/plugin|2.8.0|间接依赖|npm|
|@webassemblyjs/utf8|1.11.1|间接依赖|npm|
|is-plain-object|2.0.4|间接依赖|npm|
|picomatch|2.3.0|间接依赖|npm|
|css-select|4.3.0|间接依赖|npm|
|@jridgewell/source-map|0.3.2|间接依赖|npm|
|webpack-sources|3.2.3|间接依赖|npm|
|@webpack-cli/info|2.0.0|间接依赖|npm|
|find-up|4.1.0|间接依赖|npm|
|stable|0.1.8|间接依赖|npm|
|@webassemblyjs/wasm-edit|1.11.1|间接依赖|npm|
|@swc/helpers|0.4.14|间接依赖|npm|
|color-name|1.1.4|间接依赖|npm|
|@msgpackr-extract/msgpackr-extract-darwin-x64|2.2.0|间接依赖|npm|
|@jridgewell/trace-mapping|0.3.17|间接依赖|npm|
|import-local|3.0.3|间接依赖|npm|
|@parcel/transformer-postcss|2.8.0|间接依赖|npm|
|tapable|2.2.1|间接依赖|npm|
|p-limit|3.1.0|间接依赖|npm|
|jest-worker|27.2.5|间接依赖|npm|
|@webassemblyjs/leb128|1.11.1|间接依赖|npm|
|eslint-scope|5.1.1|间接依赖|npm|
|argparse|1.0.10|间接依赖|npm|
|@lmdb/lmdb-darwin-arm64|2.5.2|间接依赖|npm|
|semver|7.3.5|间接依赖|npm|
|acorn-import-assertions|1.8.0|间接依赖|npm|
|has-flag|4.0.0|间接依赖|npm|
|yallist|4.0.0|间接依赖|npm|
|typescript|4.7.4|直接依赖|npm|
|@xtuc/long|4.2.2|间接依赖|npm|
|webpack-merge|5.8.0|间接依赖|npm|
|@parcel/optimizer-css|2.8.0|间接依赖|npm|
|@discoveryjs/json-ext|0.5.5|间接依赖|npm|
|msgpackr-extract|2.2.0|间接依赖|npm|
|browserslist|4.17.4|间接依赖|npm|
|@parcel/types|2.8.0|间接依赖|npm|
|electron-to-chromium|1.4.284|间接依赖|npm|
|source-map-support|0.5.20|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|nullthrows|1.1.1|间接依赖|npm|
|@parcel/transformer-posthtml|2.8.0|间接依赖|npm|
|xxhash-wasm|0.4.2|间接依赖|npm|
|fastest-levenshtein|1.0.12|间接依赖|npm|
|source-map|0.6.1|间接依赖|npm|
|base-x|3.0.9|间接依赖|npm|
|p-locate|4.1.0|间接依赖|npm|
|@parcel/reporter-cli|2.8.0|间接依赖|npm|
|semver|5.7.1|间接依赖|npm|
|globals|13.18.0|间接依赖|npm|
|webpack|5.75.0|直接依赖|npm|
|@lezer/common|0.15.12|间接依赖|npm|
|boolbase|1.0.0|间接依赖|npm|
|yocto-queue|0.1.0|间接依赖|npm|
|@msgpackr-extract/msgpackr-extract-win32-x64|2.2.0|间接依赖|npm|
|@lmdb/lmdb-win32-x64|2.5.2|间接依赖|npm|
|ts-loader|9.4.2|直接依赖|npm|
|path-exists|4.0.0|间接依赖|npm|
|escape-string-regexp|1.0.5|直接依赖|npm|
|csso|4.2.0|间接依赖|npm|
|@parcel/transformer-react-refresh-wrap|2.8.0|间接依赖|npm|
|@rollup/plugin-terser|0.1.0|直接依赖|npm|
|type-fest|0.20.2|间接依赖|npm|
|webpack-cli|5.0.0|直接依赖|npm|
|source-map|0.7.4|直接依赖|npm|
|@parcel/transformer-html|2.8.0|间接依赖|npm|
|@parcel/transformer-raw|2.8.0|间接依赖|npm|
|resolve-cwd|3.0.0|间接依赖|npm|
|node-gyp-build-optional-packages|5.0.3|间接依赖|npm|
|pkg-dir|4.2.0|间接依赖|npm|
|esrecurse|4.3.0|间接依赖|npm|
|terser-webpack-plugin|5.2.4|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|@webassemblyjs/wast-printer|1.11.1|间接依赖|npm|
|@webassemblyjs/wasm-opt|1.11.1|间接依赖|npm|
|@webassemblyjs/wasm-parser|1.11.1|间接依赖|npm|
|@types/json-schema|7.0.9|间接依赖|npm|
|@types/node|16.10.9|间接依赖|npm|
|path-key|3.1.1|间接依赖|npm|
|ajv|6.12.6|间接依赖|npm|
|regenerator-runtime|0.13.11|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|utility-types|3.10.0|间接依赖|npm|
|@parcel/events|2.8.0|间接依赖|npm|
|cosmiconfig|7.1.0|间接依赖|npm|
|@webassemblyjs/floating-point-hex-parser|1.11.1|间接依赖|npm|
|@parcel/packager-js|2.8.0|间接依赖|npm|
|@xtuc/ieee754|1.2.0|间接依赖|npm|
|@parcel/package-manager|2.8.0|间接依赖|npm|
|@trysound/sax|0.2.0|间接依赖|npm|
|@msgpackr-extract/msgpackr-extract-linux-x64|2.2.0|间接依赖|npm|
|caniuse-lite|1.0.30001435|间接依赖|npm|
|isobject|3.0.1|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|@webpack-cli/serve|2.0.0|间接依赖|npm|
|@parcel/transformer-image|2.8.0|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|@parcel/core|2.8.0|间接依赖|npm|
|detect-libc|1.0.3|间接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.14|间接依赖|npm|
|@mischnic/json-sourcemap|0.1.0|间接依赖|npm|
|fuse.js|3.2.0|直接依赖|npm|
|@lmdb/lmdb-linux-arm64|2.5.2|间接依赖|npm|
|json5|2.2.1|间接依赖|npm|
|source-map-support|0.5.21|间接依赖|npm|
|color-convert|2.0.1|间接依赖|npm|
|@parcel/packager-html|2.8.0|间接依赖|npm|
|randombytes|2.1.0|间接依赖|npm|
|lightningcss-darwin-x64|1.17.1|间接依赖|npm|
|@parcel/transformer-babel|2.8.0|间接依赖|npm|
|@parcel/compressor-raw|2.8.0|间接依赖|npm|
|ajv-keywords|3.5.2|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|@types/estree|0.0.51|间接依赖|npm|
|@parcel/packager-svg|2.8.0|间接依赖|npm|
|ordered-binary|1.4.0|间接依赖|npm|
|css-what|6.1.0|间接依赖|npm|
|timsort|0.3.0|间接依赖|npm|
|dotenv-expand|5.1.0|间接依赖|npm|
|mime-types|2.1.33|间接依赖|npm|
|nth-check|2.1.1|间接依赖|npm|
|lightningcss-linux-arm64-gnu|1.17.1|间接依赖|npm|
|glob-to-regexp|0.4.1|间接依赖|npm|
|fsevents|2.3.2|间接依赖|npm|
|update-browserslist-db|1.0.10|间接依赖|npm|
|@webassemblyjs/helper-api-error|1.11.1|间接依赖|npm|
|clone-deep|4.0.1|间接依赖|npm|
|@msgpackr-extract/msgpackr-extract-linux-arm64|2.2.0|间接依赖|npm|
|safe-buffer|5.2.1|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|is-json|2.0.1|间接依赖|npm|
|supports-preserve-symlinks-flag|1.0.0|间接依赖|npm|
|dotenv|7.0.0|间接依赖|npm|
|@parcel/runtime-browser-hmr|2.8.0|间接依赖|npm|
|@jridgewell/set-array|1.1.2|间接依赖|npm|
|@parcel/optimizer-svgo|2.8.0|间接依赖|npm|
|golang.org/x/sys|v0.0.0-20220715151400-c0bba94af5f8|直接依赖|go|
|@parcel/optimizer-htmlnano|2.8.0|间接依赖|npm|
|@parcel/hash|2.8.0|间接依赖|npm|
|envinfo|7.8.1|间接依赖|npm|
|wildcard|2.0.0|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)