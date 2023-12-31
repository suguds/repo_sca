# naptha/tesseract.js安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1691880432097710080.svg)](https://www.murphysec.com/console/report/1691880431640530944/1691880432097710080)

仓库描述：Pure Javascript OCR for more than 100 Languages 📖🎉🖥

仓库地址：[https://github.com/naptha/tesseract.js](https://github.com/naptha/tesseract.js)

| star：31241 | watch：480 | fork：2093 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-04 04:06:54 | 许可证：- |
| 最近检测时间：2023-08-17 02:37:01 | 组件总数：605 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|MPS-2022-13797|通过 window.opener 访问使用指向不受信任目标的 Web 链接|[MPS-2022-13797](https://www.oscs1024.com/hd/MPS-2022-13797)||中危|
|MPS-2022-5166|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|istanbul-reports|3.0.2|3.1.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|5.6.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|489|Low|
|BSD-2-Clause|13|Low|
|Apache-2.0|15|Low|
|BSD-3-Clause|23|Low|
|ISC|40|Low|
|CC0-1.0|1|Low|
|CC-BY-4.0|1|Low|
|Apache License 2.0|1|Low|
|CC-BY-3.0|1|Low|
|Unlicense|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|shallow-clone|3.0.1|间接依赖|npm|
|is-number|7.0.0|间接依赖|npm|
|@babel/plugin-proposal-private-methods|7.18.6|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|extract-zip|2.0.1|间接依赖|npm|
|type-is|1.6.18|间接依赖|npm|
|@babel/plugin-proposal-export-namespace-from|7.18.9|间接依赖|npm|
|is-regex|1.1.4|间接依赖|npm|
|string.prototype.trimend|1.0.6|间接依赖|npm|
|normalize-package-data|2.4.0|间接依赖|npm|
|@ampproject/remapping|2.2.0|间接依赖|npm|
|minimist|1.2.8|间接依赖|npm|
|istanbul-lib-hook|3.0.0|间接依赖|npm|
|has-symbols|1.0.3|间接依赖|npm|
|resolve-cwd|3.0.0|间接依赖|npm|
|p-limit|2.3.0|直接依赖|npm|
|neo-async|2.6.2|间接依赖|npm|
|string-width|4.2.3|间接依赖|npm|
|wait-on|7.0.1|直接依赖|npm|
|package-hash|4.0.0|间接依赖|npm|
|regexpp|3.2.0|间接依赖|npm|
|methods|1.1.2|间接依赖|npm|
|@eslint/eslintrc|0.4.3|间接依赖|npm|
|@babel/plugin-proposal-unicode-property-regex|7.18.6|间接依赖|npm|
|error-ex|1.3.2|间接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|rxjs|7.8.0|间接依赖|npm|
|decode-uri-component|0.2.2|间接依赖|npm|
|es-to-primitive|1.2.1|间接依赖|npm|
|is-typed-array|1.1.10|间接依赖|npm|
|string.prototype.trim|1.2.7|间接依赖|npm|
|convert-source-map|1.7.0|间接依赖|npm|
|@xtuc/long|4.2.2|间接依赖|npm|
|binary-extensions|2.2.0|间接依赖|npm|
|gzip-size|6.0.0|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|yauzl|2.10.0|间接依赖|npm|
|@polka/url|1.0.0-next.21|间接依赖|npm|
|is-shared-array-buffer|1.0.2|间接依赖|npm|
|cross-fetch|3.1.5|间接依赖|npm|
|jsesc|2.5.2|间接依赖|npm|
|esutils|2.0.3|间接依赖|npm|
|hasha|5.2.2|间接依赖|npm|
|which-boxed-primitive|1.0.2|间接依赖|npm|
|@babel/plugin-proposal-dynamic-import|7.18.6|间接依赖|npm|
|natural-compare|1.4.0|间接依赖|npm|
|es-abstract|1.21.2|间接依赖|npm|
|uri-js|4.2.2|间接依赖|npm|
|mri|1.1.4|间接依赖|npm|
|@babel/plugin-transform-duplicate-keys|7.18.9|间接依赖|npm|
|p-try|2.2.0|间接依赖|npm|
|events|3.3.0|间接依赖|npm|
|caching-transform|4.0.0|间接依赖|npm|
|clone-deep|4.0.1|间接依赖|npm|
|@webassemblyjs/leb128|1.11.1|间接依赖|npm|
|readdirp|3.6.0|间接依赖|npm|
|cookie-signature|1.0.6|间接依赖|npm|
|object.values|1.1.6|间接依赖|npm|
|delayed-stream|1.0.0|间接依赖|npm|
|kind-of|6.0.3|间接依赖|npm|
|semver|5.6.0|间接依赖|npm|
|content-type|1.0.5|间接依赖|npm|
|mkdirp-classic|0.5.3|间接依赖|npm|
|forwarded|0.2.0|间接依赖|npm|
|slice-ansi|4.0.0|间接依赖|npm|
|bytes|3.1.2|间接依赖|npm|
|spdx-license-ids|3.0.2|间接依赖|npm|
|encodeurl|1.0.2|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|through|2.3.8|间接依赖|npm|
|pify|3.0.0|间接依赖|npm|
|end-of-stream|1.4.4|间接依赖|npm|
|decamelize|1.2.0|间接依赖|npm|
|parseurl|1.3.3|间接依赖|npm|
|camelcase|5.0.0|间接依赖|npm|
|webpack-dev-middleware|6.1.0|直接依赖|npm|
|regenerate|1.4.2|间接依赖|npm|
|@babel/plugin-transform-reserved-words|7.18.6|间接依赖|npm|
|atob|2.1.2|间接依赖|npm|
|test-exclude|6.0.0|间接依赖|npm|
|validate-npm-package-license|3.0.4|间接依赖|npm|
|on-finished|2.4.1|间接依赖|npm|
|resolve|1.22.1|间接依赖|npm|
|@babel/plugin-syntax-class-static-block|7.14.5|间接依赖|npm|
|@babel/plugin-transform-block-scoped-functions|7.18.6|间接依赖|npm|
|doctrine|3.0.0|间接依赖|npm|
|color-name|1.1.3|间接依赖|npm|
|depd|2.0.0|间接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|@babel/helper-annotate-as-pure|7.18.6|间接依赖|npm|
|is-string|1.0.7|间接依赖|npm|
|get-package-type|0.1.0|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|typedarray-to-buffer|3.1.5|间接依赖|npm|
|@babel/plugin-transform-classes|7.21.0|间接依赖|npm|
|chokidar|3.5.3|间接依赖|npm|
|@babel/plugin-proposal-optional-catch-binding|7.18.6|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|browserslist|4.21.5|间接依赖|npm|
|rimraf|5.0.0|间接依赖|npm|
|accepts|1.3.8|间接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|http-errors|2.0.0|间接依赖|npm|
|@sideway/formula|3.0.1|间接依赖|npm|
|@babel/plugin-transform-parameters|7.21.3|间接依赖|npm|
|diff|5.0.0|间接依赖|npm|
|devtools-protocol|0.0.981744|间接依赖|npm|
|@babel/helper-validator-option|7.21.0|间接依赖|npm|
|v8-compile-cache|2.3.0|间接依赖|npm|
|pend|1.2.0|间接依赖|npm|
|object.entries|1.1.5|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|@hapi/hoek|9.3.0|间接依赖|npm|
|estree-walker|2.0.2|间接依赖|npm|
|commondir|1.0.1|间接依赖|npm|
|json-parse-better-errors|1.0.2|间接依赖|npm|
|has-tostringtag|1.0.0|间接依赖|npm|
|@babel/plugin-transform-function-name|7.18.9|间接依赖|npm|
|eslint-module-utils|2.7.4|间接依赖|npm|
|@babel/plugin-transform-literals|7.18.9|间接依赖|npm|
|is-symbol|1.0.4|间接依赖|npm|
|negotiator|0.6.3|间接依赖|npm|
|optionator|0.9.1|间接依赖|npm|
|require-main-filename|2.0.0|直接依赖|npm|
|isobject|3.0.1|间接依赖|npm|
|@babel/helper-wrap-function|7.20.5|间接依赖|npm|
|eslint|7.32.0|直接依赖|npm|
|@babel/plugin-syntax-dynamic-import|7.8.3|间接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|is-negative-zero|2.0.2|间接依赖|npm|
|base64-js|1.5.1|间接依赖|npm|
|regjsparser|0.9.1|间接依赖|npm|
|process-on-spawn|1.0.0|间接依赖|npm|
|text-table|0.2.0|间接依赖|npm|
|idb-keyval|6.2.0|直接依赖|npm|
|eslint-config-airbnb-base|14.2.1|直接依赖|npm|
|webpack-bundle-analyzer|4.8.0|直接依赖|npm|
|setprototypeof|1.2.0|间接依赖|npm|
|pidtree|0.3.0|间接依赖|npm|
|@babel/plugin-syntax-class-properties|7.12.13|间接依赖|npm|
|@discoveryjs/json-ext|0.5.7|间接依赖|npm|
|@types/eslint|8.4.6|间接依赖|npm|
|totalist|1.1.0|间接依赖|npm|
|magic-string|0.27.0|间接依赖|npm|
|toidentifier|1.0.1|间接依赖|npm|
|body-parser|1.20.1|间接依赖|npm|
|@babel/plugin-syntax-import-assertions|7.20.0|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|caniuse-lite|1.0.30001480|间接依赖|npm|
|@babel/helper-simple-access|7.20.2|间接依赖|npm|
|wildcard|2.0.0|间接依赖|npm|
|@babel/plugin-transform-spread|7.20.7|间接依赖|npm|
|@babel/plugin-transform-sticky-regex|7.18.6|间接依赖|npm|
|@babel/plugin-transform-for-of|7.21.0|间接依赖|npm|
|release-zalgo|1.0.0|间接依赖|npm|
|log-symbols|4.1.0|间接依赖|npm|
|@babel/helper-validator-identifier|7.19.1|间接依赖|npm|
|@humanwhocodes/config-array|0.5.0|间接依赖|npm|
|is-callable|1.2.7|间接依赖|npm|
|which-typed-array|1.1.9|间接依赖|npm|
|loader-runner|4.3.0|间接依赖|npm|
|side-channel|1.0.4|间接依赖|npm|
|import-fresh|3.3.0|间接依赖|npm|
|is-boolean-object|1.1.2|间接依赖|npm|
|array-includes|3.1.6|间接依赖|npm|
|@babel/plugin-transform-named-capturing-groups-regex|7.20.5|间接依赖|npm|
|@babel/parser|7.21.4|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|node-releases|2.0.10|间接依赖|npm|
|@webpack-cli/serve|2.0.1|间接依赖|npm|
|babel-plugin-polyfill-corejs3|0.6.0|间接依赖|npm|
|vary|1.1.2|间接依赖|npm|
|array-flatten|1.1.1|间接依赖|npm|
|nyc|15.1.0|直接依赖|npm|
|@webassemblyjs/helper-numbers|1.11.1|间接依赖|npm|
|https-proxy-agent|5.0.1|间接依赖|npm|
|node-preload|0.2.1|间接依赖|npm|
|@types/node|18.7.7|间接依赖|npm|
|enquirer|2.3.6|间接依赖|npm|
|archy|1.0.0|间接依赖|npm|
|mrmime|1.0.1|间接依赖|npm|
|axios|0.27.2|间接依赖|npm|
|fsevents|2.3.2|间接依赖|npm|
|@sideway/pinpoint|2.0.0|间接依赖|npm|
|colorette|2.0.19|间接依赖|npm|
|@jridgewell/gen-mapping|0.1.1|间接依赖|npm|
|electron-to-chromium|1.4.365|间接依赖|npm|
|flat|5.0.2|间接依赖|npm|
|es-module-lexer|1.2.1|间接依赖|npm|
|istanbul-lib-source-maps|4.0.0|间接依赖|npm|
|@babel/compat-data|7.21.4|间接依赖|npm|
|@types/eslint-scope|3.7.4|间接依赖|npm|
|prelude-ls|1.2.1|间接依赖|npm|
|tesseract.js-core|4.0.4|直接依赖|npm|
|buffer-from|1.1.2|间接依赖|npm|
|import-local|3.1.0|间接依赖|npm|
|mkdirp|1.0.4|间接依赖|npm|
|foreground-child|2.0.0|间接依赖|npm|
|webpack|5.79.0|直接依赖|npm|
|is-unicode-supported|0.1.0|间接依赖|npm|
|es6-error|4.1.1|间接依赖|npm|
|@webassemblyjs/ieee754|1.11.1|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|@babel/helper-function-name|7.21.0|间接依赖|npm|
|@istanbuljs/schema|0.1.2|间接依赖|npm|
|@babel/plugin-syntax-numeric-separator|7.10.4|间接依赖|npm|
|make-dir|3.1.0|间接依赖|npm|
|yargs-unparser|2.0.0|间接依赖|npm|
|@jridgewell/source-map|0.3.3|间接依赖|npm|
|astral-regex|2.0.0|间接依赖|npm|
|@babel/helper-remap-async-to-generator|7.18.9|间接依赖|npm|
|@webassemblyjs/utf8|1.11.1|间接依赖|npm|
|@babel/plugin-bugfix-v8-spread-parameters-in-optional-chaining|7.20.7|间接依赖|npm|
|table|6.8.0|间接依赖|npm|
|word-wrap|1.2.4|间接依赖|npm|
|indent-string|4.0.0|间接依赖|npm|
|watchpack|2.4.0|间接依赖|npm|
|@babel/plugin-transform-new-target|7.18.6|间接依赖|npm|
|has-bigints|1.0.2|间接依赖|npm|
|glob-parent|5.1.2|间接依赖|npm|
|@babel/plugin-syntax-optional-chaining|7.8.3|间接依赖|npm|
|call-bind|1.0.2|间接依赖|npm|
|eslint-scope|5.1.1|间接依赖|npm|
|is-core-module|2.12.0|间接依赖|npm|
|parent-module|1.0.1|间接依赖|npm|
|@babel/core|7.21.4|间接依赖|npm|
|@babel/helper-replace-supers|7.20.7|间接依赖|npm|
|@babel/regjsgen|0.8.0|间接依赖|npm|
|@babel/plugin-transform-shorthand-properties|7.18.6|间接依赖|npm|
|picocolors|1.0.0|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|puppeteer|13.7.0|间接依赖|npm|
|@babel/preset-env|7.21.4|直接依赖|npm|
|babel-plugin-polyfill-regenerator|0.4.1|间接依赖|npm|
|pump|3.0.0|间接依赖|npm|
|object-inspect|1.12.3|间接依赖|npm|
|minipass|5.0.0|间接依赖|npm|
|@nicolo-ribaudo/eslint-scope-5-internals|5.1.1-v1|间接依赖|npm|
|@babel/preset-modules|0.1.5|间接依赖|npm|
|default-require-extensions|3.0.0|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.14|间接依赖|npm|
|p-map|3.0.0|间接依赖|npm|
|@webassemblyjs/helper-buffer|1.11.1|间接依赖|npm|
|@babel/plugin-transform-arrow-functions|7.20.7|间接依赖|npm|
|yallist|3.1.1|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|eslint-utils|2.1.0|间接依赖|npm|
|@types/json-schema|7.0.11|间接依赖|npm|
|progress|2.0.3|间接依赖|npm|
|esprima|4.0.1|间接依赖|npm|
|sirv|1.0.19|间接依赖|npm|
|pkg-dir|4.2.0|间接依赖|npm|
|glob|7.2.0|间接依赖|npm|
|spdx-exceptions|2.2.0|间接依赖|npm|
|@babel/helper-builder-binary-assignment-operator-visitor|7.18.9|间接依赖|npm|
|es-set-tostringtag|2.0.1|间接依赖|npm|
|regenerate-unicode-properties|10.1.0|间接依赖|npm|
|@babel/traverse|7.21.4|间接依赖|npm|
|istanbul-reports|3.0.2|间接依赖|npm|
|update-browserslist-db|1.0.11|间接依赖|npm|
|functional-red-black-tree|1.0.1|间接依赖|npm|
|proxy-from-env|1.1.0|间接依赖|npm|
|@babel/plugin-transform-modules-commonjs|7.21.2|间接依赖|npm|
|@babel/plugin-proposal-json-strings|7.18.6|间接依赖|npm|
|spawn-wrap|2.0.0|间接依赖|npm|
|tar-stream|2.2.0|间接依赖|npm|
|path-to-regexp|0.1.7|间接依赖|npm|
|@istanbuljs/load-nyc-config|1.1.0|间接依赖|npm|
|sprintf-js|1.0.3|间接依赖|npm|
|estraverse|4.3.0|间接依赖|npm|
|statuses|2.0.1|间接依赖|npm|
|media-typer|0.3.0|间接依赖|npm|
|ws|8.5.0|间接依赖|npm|
|args|5.0.1|间接依赖|npm|
|nice-try|1.0.5|间接依赖|npm|
|regexpu-core|5.3.2|间接依赖|npm|
|@babel/plugin-proposal-nullish-coalescing-operator|7.18.6|间接依赖|npm|
|unicode-canonical-property-names-ecmascript|2.0.0|间接依赖|npm|
|eslint-import-resolver-node|0.3.7|间接依赖|npm|
|path-key|2.0.1|间接依赖|npm|
|utils-merge|1.0.1|间接依赖|npm|
|@babel/helper-string-parser|7.19.4|间接依赖|npm|
|file-entry-cache|6.0.1|间接依赖|npm|
|iconv-lite|0.4.24|间接依赖|npm|
|shell-quote|1.8.1|间接依赖|npm|
|ajv-formats|2.1.1|间接依赖|npm|
|esquery|1.4.0|间接依赖|npm|
|get-intrinsic|1.2.0|间接依赖|npm|
|ee-first|1.1.1|间接依赖|npm|
|@babel/helper-member-expression-to-functions|7.21.0|间接依赖|npm|
|strip-ansi|6.0.1|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|@babel/helper-hoist-variables|7.18.6|间接依赖|npm|
|@webassemblyjs/helper-api-error|1.11.1|间接依赖|npm|
|to-fast-properties|2.0.0|间接依赖|npm|
|fs-monkey|1.0.3|间接依赖|npm|
|duplexer|0.1.2|间接依赖|npm|
|webpack-sources|3.2.3|间接依赖|npm|
|yargs|16.2.0|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|wasm-feature-detect|1.2.11|直接依赖|npm|
|json5|1.0.2|间接依赖|npm|
|unbox-primitive|1.0.2|间接依赖|npm|
|@babel/plugin-transform-destructuring|7.21.3|间接依赖|npm|
|rollup|3.20.7|直接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|@babel/plugin-transform-async-to-generator|7.20.7|间接依赖|npm|
|buffer|6.0.3|间接依赖|npm|
|imurmurhash|0.1.4|间接依赖|npm|
|is-glob|4.0.3|间接依赖|npm|
|@babel/plugin-transform-exponentiation-operator|7.18.6|间接依赖|npm|
|type-fest|0.8.1|间接依赖|npm|
|which-module|2.0.0|直接依赖|npm|
|@webpack-cli/info|2.0.1|间接依赖|npm|
|merge-descriptors|1.0.1|间接依赖|npm|
|@babel/helper-split-export-declaration|7.18.6|间接依赖|npm|
|hosted-git-info|2.8.9|间接依赖|npm|
|mime-db|1.52.0|间接依赖|npm|
|resolve-from|4.0.0|间接依赖|npm|
|@babel/plugin-transform-block-scoping|7.21.0|间接依赖|npm|
|qs|6.11.0|间接依赖|npm|
|regenerator-transform|0.15.1|间接依赖|npm|
|is-bigint|1.0.4|间接依赖|npm|
|@babel/helper-compilation-targets|7.21.4|间接依赖|npm|
|etag|1.8.1|间接依赖|npm|
|source-map-resolve|0.6.0|间接依赖|npm|
|@babel/plugin-transform-template-literals|7.18.9|间接依赖|npm|
|follow-redirects|1.15.2|间接依赖|npm|
|eslint-visitor-keys|2.1.0|间接依赖|npm|
|form-data|4.0.0|间接依赖|npm|
|istanbul-lib-instrument|4.0.3|间接依赖|npm|
|unicode-match-property-value-ecmascript|2.1.0|间接依赖|npm|
|serve-static|1.15.0|间接依赖|npm|
|express|4.18.2|直接依赖|npm|
|@webassemblyjs/helper-wasm-section|1.11.1|间接依赖|npm|
|serialize-javascript|6.0.0|间接依赖|npm|
|parse-json|4.0.0|间接依赖|npm|
|has-property-descriptors|1.0.0|间接依赖|npm|
|terser|5.16.9|间接依赖|npm|
|babel-plugin-polyfill-corejs2|0.3.3|间接依赖|npm|
|@babel/plugin-syntax-async-generators|7.8.4|间接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|@sideway/address|4.1.4|间接依赖|npm|
|clean-stack|2.2.0|间接依赖|npm|
|levn|0.4.1|间接依赖|npm|
|@babel/helper-define-polyfill-provider|0.3.3|间接依赖|npm|
|@babel/helper-explode-assignable-expression|7.18.6|间接依赖|npm|
|cors|2.8.5|直接依赖|npm|
|brace-expansion|1.1.8|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|@babel/plugin-transform-computed-properties|7.20.7|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|string_decoder|1.3.0|间接依赖|npm|
|flat-cache|3.0.4|间接依赖|npm|
|@babel/eslint-parser|7.21.3|直接依赖|npm|
|jest-worker|27.5.1|间接依赖|npm|
|@babel/plugin-proposal-async-generator-functions|7.20.7|间接依赖|npm|
|@webpack-cli/configtest|2.0.1|间接依赖|npm|
|@babel/plugin-syntax-nullish-coalescing-operator|7.8.3|间接依赖|npm|
|nanoid|3.3.3|间接依赖|npm|
|picomatch|2.3.1|间接依赖|npm|
|@humanwhocodes/object-schema|1.2.1|间接依赖|npm|
|path-type|3.0.0|间接依赖|npm|
|source-map|0.6.1|间接依赖|npm|
|istanbul-lib-report|3.0.0|间接依赖|npm|
|randombytes|2.1.0|间接依赖|npm|
|chrome-trace-event|1.0.2|间接依赖|npm|
|cross-spawn|6.0.5|间接依赖|npm|
|expect.js|0.3.1|直接依赖|npm|
|acorn|8.8.2|间接依赖|npm|
|has-proto|1.0.1|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|@babel/plugin-transform-modules-umd|7.18.6|间接依赖|npm|
|ms|2.0.0|间接依赖|npm|
|is-windows|1.0.2|间接依赖|npm|
|@babel/plugin-transform-dotall-regex|7.18.6|间接依赖|npm|
|supports-color|5.4.0|间接依赖|npm|
|@babel/helper-plugin-utils|7.20.2|间接依赖|npm|
|@types/json5|0.0.29|间接依赖|npm|
|eslint-plugin-import|2.27.5|直接依赖|npm|
|which|1.3.1|间接依赖|npm|
|agent-base|6.0.2|间接依赖|npm|
|rollup-plugin-sourcemaps|0.6.3|直接依赖|npm|
|@babel/helper-create-regexp-features-plugin|7.21.4|间接依赖|npm|
|@babel/runtime|7.21.0|间接依赖|npm|
|@babel/helper-skip-transparent-expression-wrappers|7.20.0|间接依赖|npm|
|memorystream|0.3.1|间接依赖|npm|
|is-date-object|1.0.5|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|@babel/generator|7.21.4|间接依赖|npm|
|find-cache-dir|3.3.2|间接依赖|npm|
|@babel/helper-create-class-features-plugin|7.21.4|间接依赖|npm|
|es-shim-unscopables|1.0.0|间接依赖|npm|
|ignore|4.0.6|间接依赖|npm|
|@babel/plugin-syntax-object-rest-spread|7.8.3|间接依赖|npm|
|tar-fs|2.1.1|间接依赖|npm|
|uuid|3.3.3|间接依赖|npm|
|load-json-file|4.0.0|间接依赖|npm|
|builtin-modules|1.1.1|间接依赖|npm|
|globals|11.12.0|间接依赖|npm|
|gensync|1.0.0-beta.2|间接依赖|npm|
|proxy-addr|2.0.7|间接依赖|npm|
|@babel/template|7.20.7|间接依赖|npm|
|asynckit|0.4.0|间接依赖|npm|
|ajv|6.12.6|间接依赖|npm|
|@babel/plugin-proposal-numeric-separator|7.18.6|间接依赖|npm|
|fromentries|1.2.1|间接依赖|npm|
|debug|3.2.7|间接依赖|npm|
|bl|4.1.0|间接依赖|npm|
|@babel/plugin-transform-unicode-regex|7.18.6|间接依赖|npm|
|typed-array-length|1.0.4|间接依赖|npm|
|terser-webpack-plugin|5.3.7|间接依赖|npm|
|@babel/plugin-bugfix-safari-id-destructuring-collision-in-function-expression|7.18.6|间接依赖|npm|
|bmp-js|0.1.0|直接依赖|npm|
|content-disposition|0.5.4|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|for-each|0.3.3|间接依赖|npm|
|esrecurse|4.3.0|间接依赖|npm|
|mocha-headless-chrome|4.0.0|直接依赖|npm|
|callsites|3.1.0|间接依赖|npm|
|is-electron|2.2.2|直接依赖|npm|
|@jridgewell/trace-mapping|0.3.18|间接依赖|npm|
|is-typedarray|1.0.0|间接依赖|npm|
|memfs|3.5.1|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|@babel/code-frame|7.21.4|间接依赖|npm|
|anymatch|3.1.2|间接依赖|npm|
|safe-regex-test|1.0.0|间接依赖|npm|
|string.prototype.trimstart|1.0.6|间接依赖|npm|
|aggregate-error|3.1.0|间接依赖|npm|
|opener|1.5.2|间接依赖|npm|
|confusing-browser-globals|1.0.11|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|finalhandler|1.2.0|间接依赖|npm|
|available-typed-arrays|1.0.5|间接依赖|npm|
|safari-14-idb-fix|3.0.0|间接依赖|npm|
|@babel/plugin-transform-modules-amd|7.20.11|间接依赖|npm|
|@babel/helper-environment-visitor|7.18.9|间接依赖|npm|
|@webassemblyjs/helper-wasm-bytecode|1.11.1|间接依赖|npm|
|unpipe|1.0.0|间接依赖|npm|
|json-stable-stringify-without-jsonify|1.0.1|间接依赖|npm|
|get-symbol-description|1.0.0|间接依赖|npm|
|read-pkg|3.0.0|间接依赖|npm|
|is-builtin-module|1.0.0|间接依赖|npm|
|zlibjs|0.3.1|直接依赖|npm|
|@rollup/plugin-commonjs|24.1.0|直接依赖|npm|
|@babel/plugin-transform-unicode-escapes|7.18.10|间接依赖|npm|
|wrap-ansi|7.0.0|间接依赖|npm|
|ajv-keywords|3.5.2|间接依赖|npm|
|is-plain-obj|2.1.0|间接依赖|npm|
|@webassemblyjs/wasm-opt|1.11.1|间接依赖|npm|
|@xtuc/ieee754|1.2.0|间接依赖|npm|
|strip-bom|3.0.0|间接依赖|npm|
|@babel/plugin-transform-regenerator|7.20.5|间接依赖|npm|
|escape-html|1.0.3|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|@webassemblyjs/floating-point-hex-parser|1.11.1|间接依赖|npm|
|istanbul-lib-coverage|3.0.0|间接依赖|npm|
|rechoir|0.8.0|间接依赖|npm|
|set-blocking|2.0.0|直接依赖|npm|
|opencollective-postinstall|2.0.3|直接依赖|npm|
|@webassemblyjs/wast-printer|1.11.1|间接依赖|npm|
|graceful-fs|4.2.10|间接依赖|npm|
|is-arrayish|0.2.1|间接依赖|npm|
|ieee754|1.2.1|间接依赖|npm|
|whatwg-url|5.0.0|间接依赖|npm|
|destroy|1.2.0|间接依赖|npm|
|fresh|0.5.2|间接依赖|npm|
|unicode-match-property-ecmascript|2.0.0|间接依赖|npm|
|ipaddr.js|1.9.1|间接依赖|npm|
|babel-loader|9.1.2|直接依赖|npm|
|yargs-parser|18.1.3|间接依赖|npm|
|@babel/helper-module-transforms|7.21.2|间接依赖|npm|
|@babel/plugin-proposal-optional-chaining|7.21.0|间接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|globalthis|1.0.3|间接依赖|npm|
|tsconfig-paths|3.14.1|间接依赖|npm|
|@babel/helper-optimise-call-expression|7.18.6|间接依赖|npm|
|@babel/plugin-proposal-object-rest-spread|7.20.7|间接依赖|npm|
|functions-have-names|1.2.3|间接依赖|npm|
|fd-slicer|1.1.0|间接依赖|npm|
|envinfo|7.8.1|间接依赖|npm|
|@babel/helpers|7.21.0|间接依赖|npm|
|unicode-property-aliases-ecmascript|2.1.0|间接依赖|npm|
|@babel/plugin-transform-member-expression-literals|7.18.6|间接依赖|npm|
|@babel/plugin-syntax-private-property-in-object|7.14.5|间接依赖|npm|
|range-parser|1.2.1|间接依赖|npm|
|type-check|0.4.0|间接依赖|npm|
|regexp.prototype.flags|1.4.3|间接依赖|npm|
|define-properties|1.1.4|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|interpret|3.1.1|间接依赖|npm|
|webidl-conversions|3.0.1|间接依赖|npm|
|array.prototype.flat|1.3.1|间接依赖|npm|
|html-escaper|2.0.2|间接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|raw-body|2.5.1|间接依赖|npm|
|string.prototype.padend|3.0.0|间接依赖|npm|
|@webassemblyjs/wasm-gen|1.11.1|间接依赖|npm|
|@rollup/pluginutils|5.0.2|间接依赖|npm|
|write-file-atomic|3.0.3|间接依赖|npm|
|tr46|0.0.3|间接依赖|npm|
|gopd|1.0.1|间接依赖|npm|
|lodash.merge|4.6.2|间接依赖|npm|
|is-binary-path|2.1.0|间接依赖|npm|
|array.prototype.flatmap|1.3.1|间接依赖|npm|
|cookie|0.5.0|间接依赖|npm|
|@webassemblyjs/ast|1.11.1|间接依赖|npm|
|append-transform|2.0.0|间接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|commander|2.20.3|间接依赖|npm|
|@babel/plugin-transform-typeof-symbol|7.18.9|间接依赖|npm|
|workerpool|6.2.1|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|@webassemblyjs/wasm-parser|1.11.1|间接依赖|npm|
|is-plain-object|2.0.4|间接依赖|npm|
|js-yaml|3.13.1|间接依赖|npm|
|signal-exit|3.0.2|间接依赖|npm|
|internal-slot|1.0.5|间接依赖|npm|
|mime-types|2.1.35|间接依赖|npm|
|deep-is|0.1.3|间接依赖|npm|
|mocha|10.2.0|直接依赖|npm|
|schema-utils|4.0.1|间接依赖|npm|
|@babel/plugin-proposal-class-static-block|7.21.0|间接依赖|npm|
|object-keys|1.1.1|间接依赖|npm|
|webpack-merge|5.8.0|间接依赖|npm|
|get-stream|5.2.0|间接依赖|npm|
|tslib|1.10.0|间接依赖|npm|
|regenerator-runtime|0.13.11|间接依赖|npm|
|node-fetch|2.6.9|间接依赖|npm|
|@jridgewell/resolve-uri|3.1.0|间接依赖|npm|
|@babel/plugin-proposal-class-properties|7.18.6|间接依赖|npm|
|browser-stdout|1.3.1|间接依赖|npm|
|@babel/types|7.21.4|间接依赖|npm|
|lodash.debounce|4.0.8|间接依赖|npm|
|fastest-levenshtein|1.0.16|间接依赖|npm|
|@babel/plugin-proposal-logical-assignment-operators|7.20.7|间接依赖|npm|
|require-from-string|2.0.2|直接依赖|npm|
|punycode|2.1.1|间接依赖|npm|
|enhanced-resolve|5.10.0|间接依赖|npm|
|@babel/helper-module-imports|7.18.6|间接依赖|npm|
|@babel/plugin-syntax-json-strings|7.8.3|间接依赖|npm|
|core-js-compat|3.30.1|间接依赖|npm|
|argparse|1.0.10|间接依赖|npm|
|@babel/plugin-syntax-export-namespace-from|7.8.3|间接依赖|npm|
|@babel/plugin-transform-object-super|7.18.6|间接依赖|npm|
|he|1.2.0|间接依赖|npm|
|tapable|2.2.1|间接依赖|npm|
|is-url|1.2.4|直接依赖|npm|
|@webassemblyjs/wasm-edit|1.11.1|间接依赖|npm|
|buffer-crc32|0.2.13|间接依赖|npm|
|y18n|4.0.3|间接依赖|npm|
|@hapi/topo|5.1.0|间接依赖|npm|
|is-reference|1.2.1|间接依赖|npm|
|@babel/plugin-proposal-private-property-in-object|7.21.0|间接依赖|npm|
|json-parse-even-better-errors|2.3.1|间接依赖|npm|
|array-buffer-byte-length|1.0.0|间接依赖|npm|
|npm-run-all|4.1.5|直接依赖|npm|
|lodash.truncate|4.4.2|间接依赖|npm|
|cliui|7.0.4|间接依赖|npm|
|@types/estree|1.0.0|间接依赖|npm|
|joi|17.9.1|间接依赖|npm|
|fs-constants|1.0.0|间接依赖|npm|
|shebang-regex|1.0.0|间接依赖|npm|
|path-scurry|1.7.0|直接依赖|npm|
|acorn-walk|8.2.0|间接依赖|npm|
|@babel/highlight|7.18.6|间接依赖|npm|
|acorn-jsx|5.3.2|间接依赖|npm|
|@types/yauzl|2.10.0|间接依赖|npm|
|mime|1.6.0|间接依赖|npm|
|readable-stream|3.6.0|间接依赖|npm|
|is-number-object|1.0.7|间接依赖|npm|
|@babel/plugin-transform-property-literals|7.18.6|间接依赖|npm|
|function.prototype.name|1.1.5|间接依赖|npm|
|fast-levenshtein|2.0.6|间接依赖|npm|
|@babel/plugin-syntax-logical-assignment-operators|7.10.4|间接依赖|npm|
|lodash.flattendeep|4.4.0|间接依赖|npm|
|espree|7.3.1|间接依赖|npm|
|strip-json-comments|3.1.1|间接依赖|npm|
|is-weakref|1.0.2|间接依赖|npm|
|unbzip2-stream|1.4.3|间接依赖|npm|
|@jridgewell/set-array|1.1.2|间接依赖|npm|
|leven|2.1.0|间接依赖|npm|
|is-array-buffer|3.0.2|间接依赖|npm|
|glob-to-regexp|0.4.1|间接依赖|npm|
|@babel/plugin-transform-modules-systemjs|7.20.11|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|lru-cache|5.1.1|间接依赖|npm|
|istanbul-lib-processinfo|2.0.2|间接依赖|npm|
|spdx-correct|3.0.2|间接依赖|npm|
|balanced-match|1.0.0|间接依赖|npm|
|combined-stream|1.0.8|间接依赖|npm|
|source-map-support|0.5.21|间接依赖|npm|
|shebang-command|1.2.0|间接依赖|npm|
|spdx-expression-parse|3.0.0|间接依赖|npm|
|send|0.18.0|间接依赖|npm|
|webpack-cli|5.0.1|直接依赖|npm|
|chownr|1.1.4|间接依赖|npm|
|@babel/plugin-syntax-optional-catch-binding|7.8.3|间接依赖|npm|
|flatted|3.2.6|间接依赖|npm|
|merge-stream|2.0.0|间接依赖|npm|
|supports-preserve-symlinks-flag|1.0.0|间接依赖|npm|
|@babel/plugin-syntax-top-level-await|7.14.5|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)