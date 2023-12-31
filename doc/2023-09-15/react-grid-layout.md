# react-grid-layout/react-grid-layout安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1702390513352359936.svg)](https://www.murphysec.com/console/report/1702390513297833984/1702390513352359936)

仓库描述：A draggable and resizable grid layout with responsive breakpoints, for React.

仓库地址：[https://github.com/react-grid-layout/react-grid-layout](https://github.com/react-grid-layout/react-grid-layout)

| star：18286 | watch：228 | fork：2458 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-15 00:10:17 | 许可证：MIT |
| 最近检测时间：2023-09-15 02:35:11 | 组件总数：953 | 漏洞总数：5 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|ejs 存在服务端模板注入漏洞|注入|[MPS-2023-10199](https://www.oscs1024.com/hd/MPS-2023-10199)|CVE-2023-29827|严重|
|word-wrap 安全漏洞|ReDoS|[MPS-2023-5109](https://www.oscs1024.com/hd/MPS-2023-5109)|CVE-2023-26115|高危|
|tough-cookie 安全漏洞|原型污染|[MPS-2023-5130](https://www.oscs1024.com/hd/MPS-2023-5130)|CVE-2023-26136|严重|
|tough-cookie<4.1.3 存在原型污染漏洞|原型污染|[MPS-esyq-56vx](https://www.oscs1024.com/hd/MPS-esyq-56vx)||中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|word-wrap|1.2.3|1.2.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|ejs|3.1.9||直接依赖|建议修复|C:1|H:0|M:0|L:0|
|tough-cookie|4.1.2|4.1.3|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|semver|5.7.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|semver|6.3.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|771|Low|
|ISC|47|Low|
|BSD-3-Clause|24|Low|
|BSD-2-Clause|25|Low|
|Apache-2.0|23|Low|
|CC0-1.0|1|Low|
|CC-BY-4.0|1|Low|
|Unlicense|2|Low|
|Python-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|scheduler|0.19.1|间接依赖|npm|
|supports-color|8.1.1|间接依赖|npm|
|ci-info|3.8.0|间接依赖|npm|
|is-number|7.0.0|间接依赖|npm|
|randombytes|2.1.0|间接依赖|npm|
|htmlparser2|8.0.1|间接依赖|npm|
|@types/eslint-scope|3.7.4|间接依赖|npm|
|is-generator-fn|2.1.0|间接依赖|npm|
|@jridgewell/gen-mapping|0.3.2|间接依赖|npm|
|fresh|0.5.2|间接依赖|npm|
|prop-types-exact|1.2.0|间接依赖|npm|
|wrap-ansi|7.0.0|间接依赖|npm|
|@babel/plugin-transform-object-super|7.22.5|间接依赖|npm|
|jest-haste-map|29.6.4|间接依赖|npm|
|p-limit|3.1.0|间接依赖|npm|
|isobject|3.0.1|间接依赖|npm|
|@babel/plugin-transform-numeric-separator|7.22.11|间接依赖|npm|
|@babel/plugin-transform-modules-umd|7.22.5|间接依赖|npm|
|postcss-selector-parser|6.0.11|间接依赖|npm|
|type-is|1.6.18|间接依赖|npm|
|fast-equals|4.0.3|直接依赖|npm|
|which-collection|1.0.1|间接依赖|npm|
|leven|3.1.0|间接依赖|npm|
|parseurl|1.3.3|间接依赖|npm|
|jest-docblock|29.6.3|间接依赖|npm|
|mime-db|1.52.0|间接依赖|npm|
|clsx|1.2.1|间接依赖|npm|
|flatted|3.2.7|间接依赖|npm|
|jest-environment-jsdom|29.6.4|直接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.15|间接依赖|npm|
|@webassemblyjs/floating-point-hex-parser|1.11.6|间接依赖|npm|
|@babel/helper-define-polyfill-provider|0.4.2|间接依赖|npm|
|resolve|2.0.0-next.4|间接依赖|npm|
|gopd|1.0.1|间接依赖|npm|
|typed-array-byte-offset|1.0.0|间接依赖|npm|
|ajv-keywords|3.5.2|间接依赖|npm|
|string-argv|0.3.2|间接依赖|npm|
|istanbul-reports|3.1.5|间接依赖|npm|
|hpack.js|2.1.6|间接依赖|npm|
|lodash.flattendeep|4.4.0|间接依赖|npm|
|path-key|4.0.0|间接依赖|npm|
|cookie-signature|1.0.6|间接依赖|npm|
|esprima|4.0.1|间接依赖|npm|
|slice-ansi|5.0.0|间接依赖|npm|
|react-dom|16.14.0|直接依赖|npm|
|convert-source-map|2.0.0|间接依赖|npm|
|body-parser|1.20.1|间接依赖|npm|
|exit|0.1.2|间接依赖|npm|
|jest-runtime|29.6.4|间接依赖|npm|
|ansi-escapes|5.0.0|间接依赖|npm|
|prettier|3.0.3|直接依赖|npm|
|symbol-tree|3.2.4|间接依赖|npm|
|object.hasown|1.1.2|间接依赖|npm|
|supports-color|7.2.0|间接依赖|npm|
|react-lifecycles-compat|3.0.4|间接依赖|npm|
|pluralize|8.0.0|间接依赖|npm|
|schema-utils|3.3.0|间接依赖|npm|
|lru-cache|5.1.1|间接依赖|npm|
|negotiator|0.6.3|间接依赖|npm|
|p-locate|4.1.0|间接依赖|npm|
|source-map|0.6.1|直接依赖|npm|
|wbuf|1.7.3|间接依赖|npm|
|domutils|3.0.1|间接依赖|npm|
|is-shared-array-buffer|1.0.2|间接依赖|npm|
|glob-parent|5.1.2|间接依赖|npm|
|jest-regex-util|29.6.3|间接依赖|npm|
|cjs-module-lexer|1.2.2|间接依赖|npm|
|http-proxy|1.18.1|间接依赖|npm|
|@webassemblyjs/helper-buffer|1.11.6|间接依赖|npm|
|convert-source-map|1.9.0|间接依赖|npm|
|@babel/plugin-proposal-class-properties|7.18.6|直接依赖|npm|
|jest-get-type|29.6.3|间接依赖|npm|
|webpack-dev-server|4.15.1|直接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|fsevents|2.3.2|直接依赖|npm|
|html-element-map|1.3.1|间接依赖|npm|
|async|3.2.4|间接依赖|npm|
|postcss-value-parser|4.2.0|间接依赖|npm|
|@babel/helper-string-parser|7.22.5|间接依赖|npm|
|@jest/console|29.6.4|间接依赖|npm|
|object.values|1.1.6|间接依赖|npm|
|minimalistic-assert|1.0.1|间接依赖|npm|
|acorn-jsx|5.3.2|间接依赖|npm|
|requires-port|1.0.0|间接依赖|npm|
|@babel/plugin-transform-async-generator-functions|7.22.15|间接依赖|npm|
|shebang-regex|3.0.0|间接依赖|npm|
|jsesc|0.5.0|间接依赖|npm|
|char-regex|1.0.2|间接依赖|npm|
|form-data|4.0.0|间接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|restore-cursor|4.0.0|间接依赖|npm|
|@bcoe/v8-coverage|0.2.3|间接依赖|npm|
|vary|1.1.2|间接依赖|npm|
|to-fast-properties|2.0.0|间接依赖|npm|
|clsx|2.0.0|直接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|cross-spawn|7.0.3|间接依赖|npm|
|@jest/expect|29.6.4|间接依赖|npm|
|@babel/plugin-transform-for-of|7.22.15|间接依赖|npm|
|object-inspect|1.12.3|间接依赖|npm|
|jest-mock|29.6.3|间接依赖|npm|
|react|16.14.0|直接依赖|npm|
|@babel/helper-replace-supers|7.22.9|间接依赖|npm|
|espree|9.6.1|间接依赖|npm|
|@webassemblyjs/helper-wasm-section|1.11.6|间接依赖|npm|
|cli-truncate|3.1.0|间接依赖|npm|
|@babel/types|7.22.17|间接依赖|npm|
|hosted-git-info|2.8.9|间接依赖|npm|
|doctrine|2.1.0|间接依赖|npm|
|iconv-lite|0.6.3|间接依赖|npm|
|find-up|5.0.0|间接依赖|npm|
|react-test-renderer|16.14.0|间接依赖|npm|
|cheerio|1.0.0-rc.12|间接依赖|npm|
|has-tostringtag|1.0.0|间接依赖|npm|
|compressible|2.0.18|间接依赖|npm|
|terser|5.19.4|间接依赖|npm|
|@babel/plugin-transform-unicode-regex|7.22.5|间接依赖|npm|
|string_decoder|1.3.0|间接依赖|npm|
|unpipe|1.0.0|间接依赖|npm|
|@babel/plugin-syntax-typescript|7.20.0|间接依赖|npm|
|is-stream|3.0.0|间接依赖|npm|
|@babel/plugin-syntax-export-namespace-from|7.8.3|间接依赖|npm|
|buffer-from|1.1.2|间接依赖|npm|
|encodeurl|1.0.2|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|escape-string-regexp|4.0.0|间接依赖|npm|
|globals|13.20.0|间接依赖|npm|
|@babel/helper-optimise-call-expression|7.22.5|间接依赖|npm|
|@babel/helper-module-imports|7.22.15|间接依赖|npm|
|@types/babel__core|7.20.0|间接依赖|npm|
|terser-webpack-plugin|5.3.9|间接依赖|npm|
|@webassemblyjs/ieee754|1.11.6|间接依赖|npm|
|@babel/preset-env|7.22.15|直接依赖|npm|
|jest-worker|27.5.1|间接依赖|npm|
|shallowequal|1.1.0|间接依赖|npm|
|enzyme-to-json|3.6.2|直接依赖|npm|
|safe-buffer|5.2.1|间接依赖|npm|
|@jest/fake-timers|29.6.4|间接依赖|npm|
|@types/json-schema|7.0.11|间接依赖|npm|
|pure-rand|6.0.3|间接依赖|npm|
|semver|5.7.1|间接依赖|npm|
|@babel/helper-function-name|7.22.5|间接依赖|npm|
|babel-plugin-polyfill-regenerator|0.5.2|间接依赖|npm|
|@babel/plugin-transform-block-scoped-functions|7.22.5|间接依赖|npm|
|is-symbol|1.0.4|间接依赖|npm|
|cssesc|3.0.0|间接依赖|npm|
|@babel/plugin-transform-class-static-block|7.22.11|间接依赖|npm|
|define-properties|1.2.0|间接依赖|npm|
|json5|2.2.3|间接依赖|npm|
|wildcard|2.0.0|间接依赖|npm|
|dns-packet|5.4.0|间接依赖|npm|
|nearley|2.20.1|间接依赖|npm|
|@tootallnate/once|2.0.0|间接依赖|npm|
|universalify|0.2.0|间接依赖|npm|
|@webpack-cli/configtest|2.1.1|间接依赖|npm|
|@types/connect-history-api-fallback|1.3.5|间接依赖|npm|
|http-proxy-middleware|2.0.6|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|setprototypeof|1.1.0|间接依赖|npm|
|arraybuffer.prototype.slice|1.0.2|间接依赖|npm|
|is-path-inside|3.0.3|间接依赖|npm|
|strip-ansi|7.0.1|间接依赖|npm|
|@babel/plugin-transform-modules-amd|7.22.5|间接依赖|npm|
|process|0.11.10|间接依赖|npm|
|global|4.4.0|间接依赖|npm|
|array-includes|3.1.6|间接依赖|npm|
|get-package-type|0.1.0|间接依赖|npm|
|is-plain-object|2.0.4|间接依赖|npm|
|array-flatten|2.1.2|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|import-fresh|3.3.0|间接依赖|npm|
|default-gateway|6.0.3|间接依赖|npm|
|jest-changed-files|29.6.3|间接依赖|npm|
|is-number-object|1.0.7|间接依赖|npm|
|webidl-conversions|7.0.0|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|stack-utils|2.0.6|间接依赖|npm|
|require-from-string|2.0.2|间接依赖|npm|
|estraverse|5.3.0|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|react-is|18.2.0|间接依赖|npm|
|parse5|7.1.2|间接依赖|npm|
|@xtuc/ieee754|1.2.0|间接依赖|npm|
|is-finalizationregistry|1.0.2|间接依赖|npm|
|update-browserslist-db|1.0.11|间接依赖|npm|
|launch-editor|2.6.0|间接依赖|npm|
|dns-equal|1.0.0|间接依赖|npm|
|is-typed-array|1.1.10|间接依赖|npm|
|@babel/plugin-transform-react-jsx|7.22.15|间接依赖|npm|
|yaml|1.10.2|间接依赖|npm|
|@humanwhocodes/config-array|0.11.11|间接依赖|npm|
|@types/yargs|17.0.22|间接依赖|npm|
|react-deep-force-update|1.1.2|间接依赖|npm|
|etag|1.8.1|间接依赖|npm|
|@babel/plugin-proposal-private-property-in-object|7.21.0-placeholder-for-preset-env.2|间接依赖|npm|
|resolve|1.22.1|间接依赖|npm|
|json-stable-stringify-without-jsonify|1.0.1|间接依赖|npm|
|file-entry-cache|6.0.1|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|chalk|5.3.0|间接依赖|npm|
|cssom|0.5.0|间接依赖|npm|
|istanbul-lib-instrument|6.0.0|间接依赖|npm|
|@aashutoshrathi/word-wrap|1.2.6|间接依赖|npm|
|webpack-sources|3.2.3|间接依赖|npm|
|nth-check|2.1.1|间接依赖|npm|
|@eslint/eslintrc|2.1.2|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|@webassemblyjs/wasm-edit|1.11.6|间接依赖|npm|
|strip-final-newline|2.0.0|间接依赖|npm|
|@jridgewell/source-map|0.3.5|间接依赖|npm|
|@xtuc/long|4.2.2|间接依赖|npm|
|open|8.4.2|间接依赖|npm|
|envinfo|7.8.1|间接依赖|npm|
|browserslist|4.21.10|间接依赖|npm|
|array.prototype.flatmap|1.3.1|间接依赖|npm|
|http-errors|1.6.3|间接依赖|npm|
|destroy|1.2.0|间接依赖|npm|
|chrome-trace-event|1.0.3|间接依赖|npm|
|cosmiconfig|7.1.0|间接依赖|npm|
|sisteransi|1.0.5|间接依赖|npm|
|@sinclair/typebox|0.27.8|间接依赖|npm|
|is-async-function|2.0.0|间接依赖|npm|
|@jest/expect-utils|29.6.4|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|typed-array-buffer|1.0.0|间接依赖|npm|
|call-bind|1.0.2|间接依赖|npm|
|nwsapi|2.2.2|间接依赖|npm|
|@babel/plugin-transform-flow-comments|7.22.10|直接依赖|npm|
|boolbase|1.0.0|间接依赖|npm|
|finalhandler|1.2.0|间接依赖|npm|
|obuf|1.1.2|间接依赖|npm|
|@babel/plugin-syntax-import-attributes|7.22.5|间接依赖|npm|
|webpack-dev-middleware|5.3.3|间接依赖|npm|
|lint-staged|14.0.1|直接依赖|npm|
|@types/mime|3.0.1|间接依赖|npm|
|@babel/helper-create-regexp-features-plugin|7.22.15|间接依赖|npm|
|whatwg-encoding|2.0.0|间接依赖|npm|
|glob-parent|6.0.2|间接依赖|npm|
|locate-path|5.0.0|间接依赖|npm|
|bser|2.1.1|间接依赖|npm|
|fb-watchman|2.0.2|间接依赖|npm|
|es-abstract|1.22.1|间接依赖|npm|
|@babel/plugin-syntax-import-meta|7.10.4|间接依赖|npm|
|iterator.prototype|1.1.1|间接依赖|npm|
|eslint-visitor-keys|2.1.0|间接依赖|npm|
|bytes|3.1.2|间接依赖|npm|
|is-binary-path|2.1.0|间接依赖|npm|
|shallow-clone|3.0.1|间接依赖|npm|
|regexpu-core|5.3.1|间接依赖|npm|
|spdy-transport|3.0.0|间接依赖|npm|
|serialize-javascript|6.0.1|间接依赖|npm|
|get-intrinsic|1.2.1|间接依赖|npm|
|array-buffer-byte-length|1.0.0|间接依赖|npm|
|find-up|3.0.0|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|react-proxy|1.1.8|间接依赖|npm|
|@types/babel__traverse|7.18.3|间接依赖|npm|
|babel-preset-jest|29.6.3|间接依赖|npm|
|find-up|4.1.0|间接依赖|npm|
|@babel/plugin-transform-modules-systemjs|7.22.11|间接依赖|npm|
|@babel/preset-react|7.22.15|直接依赖|npm|
|slash|2.0.0|间接依赖|npm|
|@jest/transform|29.6.4|间接依赖|npm|
|string.prototype.trimend|1.0.6|间接依赖|npm|
|forwarded|0.2.0|间接依赖|npm|
|@types/range-parser|1.2.4|间接依赖|npm|
|p-limit|2.3.0|间接依赖|npm|
|mime|1.6.0|间接依赖|npm|
|glob-to-regexp|0.4.1|间接依赖|npm|
|globalthis|1.0.3|间接依赖|npm|
|@babel/plugin-syntax-bigint|7.8.3|间接依赖|npm|
|is-negative-zero|2.0.2|间接依赖|npm|
|resolve-from|4.0.0|间接依赖|npm|
|@babel/plugin-transform-modules-commonjs|7.22.15|间接依赖|npm|
|@sinonjs/commons|2.0.0|间接依赖|npm|
|onetime|6.0.0|间接依赖|npm|
|rambda|7.4.0|间接依赖|npm|
|run-parallel|1.2.0|间接依赖|npm|
|chokidar|3.5.3|直接依赖|npm|
|express|4.18.2|间接依赖|npm|
|detect-newline|3.1.0|间接依赖|npm|
|@babel/plugin-syntax-logical-assignment-operators|7.10.4|间接依赖|npm|
|string_decoder|1.1.1|间接依赖|npm|
|@babel/helpers|7.22.15|间接依赖|npm|
|is-date-object|1.0.5|间接依赖|npm|
|dom-serializer|2.0.0|间接依赖|npm|
|unicode-canonical-property-names-ecmascript|2.0.0|间接依赖|npm|
|eastasianwidth|0.2.0|间接依赖|npm|
|is-glob|4.0.3|间接依赖|npm|
|tmpl|1.0.5|间接依赖|npm|
|which-boxed-primitive|1.0.2|间接依赖|npm|
|cheerio-select|2.1.0|间接依赖|npm|
|is-core-module|2.11.0|间接依赖|npm|
|railroad-diagrams|1.0.0|间接依赖|npm|
|@types/yargs-parser|21.0.0|间接依赖|npm|
|es-shim-unscopables|1.0.0|间接依赖|npm|
|builtin-modules|3.3.0|间接依赖|npm|
|@babel/plugin-syntax-class-properties|7.12.13|间接依赖|npm|
|source-map|0.7.4|间接依赖|npm|
|rimraf|3.0.2|间接依赖|npm|
|array.prototype.find|2.2.1|间接依赖|npm|
|@types/istanbul-reports|3.0.1|间接依赖|npm|
|ignore|5.2.4|间接依赖|npm|
|lilconfig|2.1.0|间接依赖|npm|
|@babel/helper-builder-binary-assignment-operator-visitor|7.22.15|间接依赖|npm|
|type-detect|4.0.8|间接依赖|npm|
|eslint-scope|7.2.2|间接依赖|npm|
|internal-slot|1.0.5|间接依赖|npm|
|is-arrayish|0.2.1|间接依赖|npm|
|@types/cheerio|0.22.31|间接依赖|npm|
|events|3.3.0|间接依赖|npm|
|micromatch|4.0.5|间接依赖|npm|
|jest-util|29.6.3|间接依赖|npm|
|color-convert|2.0.1|间接依赖|npm|
|get-symbol-description|1.0.0|间接依赖|npm|
|sockjs|0.3.24|间接依赖|npm|
|websocket-extensions|0.1.4|间接依赖|npm|
|min-document|2.19.0|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|@babel/plugin-transform-export-namespace-from|7.22.11|间接依赖|npm|
|@webassemblyjs/helper-numbers|1.11.6|间接依赖|npm|
|on-finished|2.4.1|间接依赖|npm|
|@babel/parser|7.22.16|间接依赖|npm|
|@babel/plugin-syntax-optional-catch-binding|7.8.3|间接依赖|npm|
|compression|1.7.4|间接依赖|npm|
|diff-sequences|29.6.3|间接依赖|npm|
|yargs-parser|21.1.1|间接依赖|npm|
|escodegen|2.0.0|间接依赖|npm|
|@types/connect|3.4.35|间接依赖|npm|
|camelcase|6.3.0|间接依赖|npm|
|@babel/helper-simple-access|7.22.5|间接依赖|npm|
|functions-have-names|1.2.3|间接依赖|npm|
|istanbul-lib-report|3.0.0|间接依赖|npm|
|thunky|1.1.0|间接依赖|npm|
|html-escaper|2.0.2|间接依赖|npm|
|@babel/helper-compilation-targets|7.22.15|间接依赖|npm|
|regenerator-runtime|0.13.11|间接依赖|npm|
|@types/qs|6.9.7|间接依赖|npm|
|path-to-regexp|0.1.7|间接依赖|npm|
|p-locate|6.0.0|间接依赖|npm|
|pkg-dir|3.0.0|间接依赖|npm|
|regexp.prototype.flags|1.5.0|间接依赖|npm|
|@babel/plugin-syntax-jsx|7.22.5|间接依赖|npm|
|regjsparser|0.9.1|间接依赖|npm|
|@leichtgewicht/ip-codec|2.0.4|间接依赖|npm|
|https-proxy-agent|5.0.1|间接依赖|npm|
|unicode-match-property-value-ecmascript|2.1.0|间接依赖|npm|
|process-nextick-args|2.0.1|间接依赖|npm|
|@babel/plugin-syntax-import-assertions|7.22.5|间接依赖|npm|
|resolve-from|5.0.0|间接依赖|npm|
|is-wsl|2.2.0|间接依赖|npm|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|@discoveryjs/json-ext|0.5.7|间接依赖|npm|
|p-retry|4.6.2|间接依赖|npm|
|spdx-expression-parse|3.0.1|间接依赖|npm|
|raf|3.4.1|间接依赖|npm|
|flow-bin|0.172.0|直接依赖|npm|
|binary-extensions|2.2.0|间接依赖|npm|
|domexception|4.0.0|间接依赖|npm|
|ansi-regex|6.0.1|间接依赖|npm|
|rechoir|0.8.0|间接依赖|npm|
|which-typed-array|1.1.11|间接依赖|npm|
|@eslint-community/regexpp|4.8.0|间接依赖|npm|
|watchpack|2.4.0|间接依赖|npm|
|resolve.exports|2.0.0|间接依赖|npm|
|@nodelib/fs.stat|2.0.5|间接依赖|npm|
|opener|1.5.2|直接依赖|npm|
|@jest/types|29.6.3|间接依赖|npm|
|data-urls|3.0.2|间接依赖|npm|
|readable-stream|3.6.1|间接依赖|npm|
|mime-types|2.1.35|间接依赖|npm|
|jsesc|3.0.2|间接依赖|npm|
|@babel/helper-split-export-declaration|7.22.6|间接依赖|npm|
|make-dir|2.1.0|间接依赖|npm|
|@eslint/js|8.49.0|间接依赖|npm|
|selfsigned|2.1.1|间接依赖|npm|
|abab|2.0.6|间接依赖|npm|
|find-cache-dir|2.1.0|间接依赖|npm|
|queue-microtask|1.2.3|间接依赖|npm|
|@webassemblyjs/wasm-gen|1.11.6|间接依赖|npm|
|semver|7.5.4|间接依赖|npm|
|side-channel|1.0.4|间接依赖|npm|
|ms|2.1.3|间接依赖|npm|
|@webpack-cli/info|2.0.2|间接依赖|npm|
|regjsparser|0.10.0|间接依赖|npm|
|p-locate|3.0.0|间接依赖|npm|
|interpret|3.1.1|间接依赖|npm|
|enzyme|3.11.0|直接依赖|npm|
|unbox-primitive|1.0.2|间接依赖|npm|
|path-exists|5.0.0|间接依赖|npm|
|string-width|5.1.2|间接依赖|npm|
|html-encoding-sniffer|3.0.0|间接依赖|npm|
|@babel/plugin-transform-class-properties|7.22.5|间接依赖|npm|
|array-flatten|1.1.1|间接依赖|npm|
|makeerror|1.0.12|间接依赖|npm|
|babel-plugin-preval|5.1.0|直接依赖|npm|
|strip-bom|4.0.0|间接依赖|npm|
|bonjour-service|1.1.0|间接依赖|npm|
|prompts|2.4.2|间接依赖|npm|
|react-hot-loader|4.13.1|直接依赖|npm|
|ipaddr.js|1.9.1|间接依赖|npm|
|@istanbuljs/schema|0.1.3|间接依赖|npm|
|define-lazy-prop|2.0.0|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|es-module-lexer|1.3.1|间接依赖|npm|
|shell-quote|1.8.1|间接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|has-flag|4.0.0|间接依赖|npm|
|function.prototype.name|1.1.5|间接依赖|npm|
|log-update|5.0.1|间接依赖|npm|
|ansi-escapes|4.3.2|间接依赖|npm|
|array.prototype.filter|1.0.2|间接依赖|npm|
|http-errors|2.0.0|间接依赖|npm|
|@jest/core|29.6.4|间接依赖|npm|
|react-is|16.13.1|间接依赖|npm|
|multicast-dns|7.2.5|间接依赖|npm|
|human-signals|4.3.1|间接依赖|npm|
|@webassemblyjs/helper-wasm-bytecode|1.11.6|间接依赖|npm|
|@babel/compat-data|7.22.9|间接依赖|npm|
|tough-cookie|4.1.2|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|imurmurhash|0.1.4|间接依赖|npm|
|acorn-globals|7.0.1|间接依赖|npm|
|eslint-plugin-react|7.33.2|直接依赖|npm|
|@babel/plugin-transform-exponentiation-operator|7.22.5|间接依赖|npm|
|postcss|8.4.29|间接依赖|npm|
|strip-comments|2.0.1|间接依赖|npm|
|@babel/plugin-transform-react-jsx-development|7.22.5|间接依赖|npm|
|cookie|0.5.0|间接依赖|npm|
|@types/parse-json|4.0.0|间接依赖|npm|
|unicode-property-aliases-ecmascript|2.1.0|间接依赖|npm|
|batch|0.6.1|间接依赖|npm|
|validate-npm-package-license|3.0.4|间接依赖|npm|
|performance-now|2.1.0|间接依赖|npm|
|@babel/plugin-transform-block-scoping|7.22.15|间接依赖|npm|
|iconv-lite|0.4.24|间接依赖|npm|
|fastq|1.15.0|间接依赖|npm|
|webpack-merge|5.8.0|间接依赖|npm|
|postcss-modules-scope|3.0.0|间接依赖|npm|
|psl|1.9.0|间接依赖|npm|
|jsdom|20.0.3|间接依赖|npm|
|typed-array-byte-length|1.0.0|间接依赖|npm|
|@types/estree|1.0.1|间接依赖|npm|
|@webassemblyjs/utf8|1.11.6|间接依赖|npm|
|agent-base|6.0.2|间接依赖|npm|
|hoist-non-react-statics|3.3.2|间接依赖|npm|
|strip-indent|3.0.0|间接依赖|npm|
|punycode|2.3.0|间接依赖|npm|
|escape-html|1.0.3|间接依赖|npm|
|regenerate-unicode-properties|10.1.0|间接依赖|npm|
|is-stream|2.0.1|间接依赖|npm|
|object.fromentries|2.0.6|间接依赖|npm|
|@babel/helper-environment-visitor|7.22.5|间接依赖|npm|
|detect-node|2.1.0|间接依赖|npm|
|@jest/test-sequencer|29.6.4|间接依赖|npm|
|v8-to-istanbul|9.1.0|间接依赖|npm|
|parse5-htmlparser2-tree-adapter|7.0.0|间接依赖|npm|
|on-headers|1.0.2|间接依赖|npm|
|react-resizable|3.0.5|直接依赖|npm|
|@babel/plugin-transform-private-property-in-object|7.22.11|间接依赖|npm|
|is-fullwidth-code-point|4.0.0|间接依赖|npm|
|domhandler|5.0.3|间接依赖|npm|
|write-file-atomic|4.0.2|间接依赖|npm|
|jest-config|29.6.4|间接依赖|npm|
|@webassemblyjs/ast|1.11.6|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|wrap-ansi|8.1.0|间接依赖|npm|
|listr2|6.6.1|间接依赖|npm|
|babel-plugin-jest-hoist|29.6.3|间接依赖|npm|
|@types/istanbul-lib-report|3.0.0|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|string.prototype.trim|1.2.8|间接依赖|npm|
|babel-plugin-polyfill-corejs2|0.4.5|间接依赖|npm|
|isarray|2.0.5|间接依赖|npm|
|graceful-fs|4.2.10|间接依赖|npm|
|@babel/plugin-transform-nullish-coalescing-operator|7.22.11|间接依赖|npm|
|webpack-cli|5.1.4|直接依赖|npm|
|color-name|1.1.3|间接依赖|npm|
|big.js|5.2.2|间接依赖|npm|
|ee-first|1.1.1|间接依赖|npm|
|ansi-styles|4.3.0|间接依赖|npm|
|@babel/helper-plugin-utils|7.22.5|间接依赖|npm|
|for-each|0.3.3|间接依赖|npm|
|jest-resolve-dependencies|29.6.4|间接依赖|npm|
|@babel/helper-hoist-variables|7.22.5|间接依赖|npm|
|natural-compare|1.4.0|间接依赖|npm|
|depd|1.1.2|间接依赖|npm|
|range-parser|1.2.1|间接依赖|npm|
|common-path-prefix|3.0.0|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|find-up|6.3.0|间接依赖|npm|
|eventemitter3|5.0.1|间接依赖|npm|
|fs-readdir-recursive|1.1.0|间接依赖|npm|
|@babel/plugin-transform-react-display-name|7.22.5|间接依赖|npm|
|content-type|1.0.5|间接依赖|npm|
|array.prototype.flat|1.3.1|间接依赖|npm|
|@babel/traverse|7.22.17|间接依赖|npm|
|@types/graceful-fs|4.1.6|间接依赖|npm|
|tapable|2.2.1|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|deep-is|0.1.4|间接依赖|npm|
|is-array-buffer|3.0.2|间接依赖|npm|
|@babel/plugin-transform-unicode-sets-regex|7.22.5|间接依赖|npm|
|ajv|6.12.6|间接依赖|npm|
|@babel/generator|7.22.15|间接依赖|npm|
|esrecurse|4.3.0|间接依赖|npm|
|eslint-utils|3.0.0|间接依赖|npm|
|jest-watcher|29.6.4|间接依赖|npm|
|icss-utils|5.1.0|间接依赖|npm|
|commander|11.0.0|间接依赖|npm|
|@babel/regjsgen|0.8.0|间接依赖|npm|
|source-map-support|0.5.13|间接依赖|npm|
|@babel/helper-member-expression-to-functions|7.22.15|间接依赖|npm|
|@babel/plugin-transform-flow-strip-types|7.22.5|间接依赖|npm|
|lodash.merge|4.6.2|间接依赖|npm|
|es-iterator-helpers|1.0.14|间接依赖|npm|
|is-plain-obj|3.0.0|间接依赖|npm|
|jest-matcher-utils|29.6.4|间接依赖|npm|
|commander|2.20.3|间接依赖|npm|
|is-weakref|1.0.2|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|@babel/plugin-transform-optional-catch-binding|7.22.11|间接依赖|npm|
|locate-path|7.2.0|间接依赖|npm|
|@nicolo-ribaudo/chokidar-2|2.1.8-no-fsevents.3|直接依赖|npm|
|es-array-method-boxes-properly|1.0.0|间接依赖|npm|
|@babel/plugin-transform-destructuring|7.22.15|间接依赖|npm|
|@types/eslint|8.21.1|间接依赖|npm|
|dom-walk|0.1.2|间接依赖|npm|
|@babel/highlight|7.22.13|间接依赖|npm|
|type-fest|0.21.3|间接依赖|npm|
|string-width|4.2.3|间接依赖|npm|
|@babel/plugin-transform-optional-chaining|7.22.15|间接依赖|npm|
|connect-history-api-fallback|2.0.0|间接依赖|npm|
|yocto-queue|0.1.0|间接依赖|npm|
|asynciterator.prototype|1.0.0|间接依赖|npm|
|babel-plugin-polyfill-corejs3|0.8.3|间接依赖|npm|
|@babel/plugin-transform-member-expression-literals|7.22.5|间接依赖|npm|
|ajv-keywords|5.1.0|间接依赖|npm|
|mimic-fn|2.1.0|间接依赖|npm|
|domelementtype|2.3.0|间接依赖|npm|
|@babel/helper-wrap-function|7.22.17|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|ansi-styles|5.2.0|间接依赖|npm|
|@jest/test-result|29.6.4|间接依赖|npm|
|@babel/plugin-transform-json-strings|7.22.11|间接依赖|npm|
|babel-plugin-istanbul|6.1.1|间接依赖|npm|
|eslint-visitor-keys|3.4.3|间接依赖|npm|
|type-fest|0.6.0|间接依赖|npm|
|optionator|0.8.3|间接依赖|npm|
|is-callable|1.2.7|间接依赖|npm|
|istanbul-lib-instrument|5.2.1|间接依赖|npm|
|@babel/plugin-syntax-numeric-separator|7.10.4|间接依赖|npm|
|cliui|8.0.1|间接依赖|npm|
|http-deceiver|1.2.7|间接依赖|npm|
|jest-circus|29.6.4|间接依赖|npm|
|is-regex|1.1.4|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|setprototypeof|1.2.0|间接依赖|npm|
|ansi-styles|6.2.1|间接依赖|npm|
|neo-async|2.6.2|间接依赖|npm|
|estraverse|4.3.0|间接依赖|npm|
|@types/normalize-package-data|2.4.1|间接依赖|npm|
|@babel/plugin-transform-private-methods|7.22.5|间接依赖|npm|
|@nodelib/fs.scandir|2.1.5|间接依赖|npm|
|depd|2.0.0|间接依赖|npm|
|string-length|4.0.2|间接依赖|npm|
|@jridgewell/resolve-uri|3.1.1|间接依赖|npm|
|airbnb-prop-types|2.16.0|间接依赖|npm|
|@jest/schemas|29.6.3|间接依赖|npm|
|media-typer|0.3.0|间接依赖|npm|
|@types/node|18.14.1|间接依赖|npm|
|lodash.isequal|4.5.0|间接依赖|npm|
|@babel/plugin-syntax-flow|7.22.5|间接依赖|npm|
|@istanbuljs/load-nyc-config|1.1.0|间接依赖|npm|
|@babel/plugin-syntax-async-generators|7.8.4|间接依赖|npm|
|@babel/plugin-syntax-top-level-await|7.14.5|间接依赖|npm|
|enhanced-resolve|5.15.0|间接依赖|npm|
|human-signals|2.1.0|间接依赖|npm|
|w3c-xmlserializer|4.0.0|间接依赖|npm|
|normalize-package-data|2.5.0|间接依赖|npm|
|commander|4.1.1|间接依赖|npm|
|nanoid|3.3.6|间接依赖|npm|
|lines-and-columns|1.2.4|间接依赖|npm|
|cli-cursor|4.0.0|间接依赖|npm|
|exports-loader|4.0.0|直接依赖|npm|
|is-bigint|1.0.4|间接依赖|npm|
|string-natural-compare|3.0.1|间接依赖|npm|
|@types/serve-index|1.9.1|间接依赖|npm|
|source-map-js|1.0.2|间接依赖|npm|
|css-select|5.1.0|间接依赖|npm|
|@babel/register|7.22.15|直接依赖|npm|
|pkg-dir|4.2.0|间接依赖|npm|
|@types/http-proxy|1.17.10|间接依赖|npm|
|is-builtin-module|3.2.1|间接依赖|npm|
|@humanwhocodes/object-schema|1.2.1|间接依赖|npm|
|kleur|3.0.3|间接依赖|npm|
|yallist|3.1.1|间接依赖|npm|
|statuses|1.5.0|间接依赖|npm|
|jest-each|29.6.3|间接依赖|npm|
|@babel/runtime|7.21.0|间接依赖|npm|
|@babel/plugin-transform-typeof-symbol|7.22.5|间接依赖|npm|
|@babel/plugin-transform-parameters|7.22.15|间接依赖|npm|
|rfdc|1.3.0|间接依赖|npm|
|@babel/plugin-transform-template-literals|7.22.5|间接依赖|npm|
|@types/ws|8.5.5|间接依赖|npm|
|@babel/plugin-transform-named-capturing-groups-regex|7.22.5|间接依赖|npm|
|jsesc|2.5.2|间接依赖|npm|
|postcss-modules-values|4.0.0|间接依赖|npm|
|jest-worker|29.6.4|间接依赖|npm|
|object.entries|1.1.6|间接依赖|npm|
|doctrine|3.0.0|间接依赖|npm|
|@babel/eslint-parser|7.22.15|直接依赖|npm|
|faye-websocket|0.11.4|间接依赖|npm|
|utils-merge|1.0.1|间接依赖|npm|
|@types/bonjour|3.5.10|间接依赖|npm|
|is-generator-function|1.0.10|间接依赖|npm|
|electron-to-chromium|1.4.514|间接依赖|npm|
|serve-static|1.15.0|间接依赖|npm|
|has-bigints|1.0.2|间接依赖|npm|
|eslint-plugin-unicorn|48.0.1|直接依赖|npm|
|proxy-addr|2.0.7|间接依赖|npm|
|@babel/plugin-transform-object-rest-spread|7.22.15|间接依赖|npm|
|type-fest|1.4.0|间接依赖|npm|
|follow-redirects|1.15.2|间接依赖|npm|
|p-locate|5.0.0|间接依赖|npm|
|@babel/plugin-syntax-object-rest-spread|7.8.3|间接依赖|npm|
|path-exists|3.0.0|间接依赖|npm|
|is-subset|0.1.1|间接依赖|npm|
|object.assign|4.1.4|间接依赖|npm|
|lodash.debounce|4.0.8|间接依赖|npm|
|postcss-modules-extract-imports|3.0.0|间接依赖|npm|
|send|0.18.0|间接依赖|npm|
|react-draggable|4.4.5|直接依赖|npm|
|is-potential-custom-element-name|1.0.1|间接依赖|npm|
|babel-jest|29.6.4|间接依赖|npm|
|collect-v8-coverage|1.0.1|间接依赖|npm|
|levn|0.4.1|间接依赖|npm|
|fastest-levenshtein|1.0.16|间接依赖|npm|
|@babel/plugin-syntax-optional-chaining|7.8.3|间接依赖|npm|
|ansi-html-community|0.0.8|间接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|delayed-stream|1.0.0|间接依赖|npm|
|node-int64|0.4.0|间接依赖|npm|
|@types/express-serve-static-core|4.17.33|间接依赖|npm|
|@eslint-community/eslint-utils|4.4.0|间接依赖|npm|
|css-loader|6.8.1|直接依赖|npm|
|@babel/plugin-transform-computed-properties|7.22.5|间接依赖|npm|
|xml-name-validator|4.0.0|间接依赖|npm|
|levn|0.3.0|间接依赖|npm|
|@ampproject/remapping|2.2.0|间接依赖|npm|
|clean-regexp|1.0.0|间接依赖|npm|
|debug|2.6.9|间接依赖|npm|
|cssom|0.3.8|间接依赖|npm|
|jest-cli|29.6.4|间接依赖|npm|
|websocket-driver|0.7.4|间接依赖|npm|
|@babel/helper-create-class-features-plugin|7.22.15|间接依赖|npm|
|@webpack-cli/serve|2.0.5|间接依赖|npm|
|@sinonjs/fake-timers|10.0.2|间接依赖|npm|
|ret|0.1.15|间接依赖|npm|
|@babel/plugin-transform-regenerator|7.22.10|间接依赖|npm|
|@types/istanbul-lib-coverage|2.0.4|间接依赖|npm|
|xmlchars|2.2.0|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|@babel/plugin-transform-react-pure-annotations|7.22.5|间接依赖|npm|
|source-map-support|0.5.21|间接依赖|npm|
|caniuse-lite|1.0.30001532|间接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|jest-validate|29.6.3|间接依赖|npm|
|commander|10.0.1|间接依赖|npm|
|kind-of|6.0.3|间接依赖|npm|
|unicode-match-property-ecmascript|2.0.0|间接依赖|npm|
|randexp|0.4.6|间接依赖|npm|
|has-property-descriptors|1.0.0|间接依赖|npm|
|core-js-compat|3.32.2|间接依赖|npm|
|accepts|1.3.8|间接依赖|npm|
|get-stream|6.0.1|间接依赖|npm|
|eventemitter3|4.0.7|间接依赖|npm|
|ws|8.14.1|间接依赖|npm|
|@babel/helper-validator-option|7.22.15|间接依赖|npm|
|available-typed-arrays|1.0.5|间接依赖|npm|
|cssstyle|2.3.0|间接依赖|npm|
|eslint|8.49.0|直接依赖|npm|
|@babel/helper-annotate-as-pure|7.22.5|间接依赖|npm|
|istanbul-lib-coverage|3.2.0|间接依赖|npm|
|decimal.js|10.4.3|间接依赖|npm|
|readdirp|3.6.0|间接依赖|npm|
|uuid|8.3.2|间接依赖|npm|
|@types/sockjs|0.3.33|间接依赖|npm|
|escape-string-regexp|2.0.0|间接依赖|npm|
|@types/babel__generator|7.6.4|间接依赖|npm|
|@types/express|4.17.17|间接依赖|npm|
|signal-exit|3.0.7|间接依赖|npm|
|babel-loader|9.1.3|直接依赖|npm|
|@babel/plugin-transform-dynamic-import|7.22.11|间接依赖|npm|
|esutils|2.0.3|间接依赖|npm|
|@jridgewell/gen-mapping|0.1.1|间接依赖|npm|
|timsort|0.3.0|直接依赖|npm|
|safe-array-concat|1.0.1|间接依赖|npm|
|@webassemblyjs/leb128|1.11.6|间接依赖|npm|
|@babel/plugin-transform-shorthand-properties|7.22.5|间接依赖|npm|
|statuses|2.0.1|间接依赖|npm|
|discontinuous-range|1.0.0|间接依赖|npm|
|picomatch|2.3.1|间接依赖|npm|
|which-builtin-type|1.1.3|间接依赖|npm|
|eslint-scope|5.1.1|间接依赖|npm|
|esquery|1.5.0|间接依赖|npm|
|is-boolean-object|1.1.2|间接依赖|npm|
|@babel/plugin-transform-literals|7.22.5|间接依赖|npm|
|es-to-primitive|1.2.1|间接依赖|npm|
|spdx-correct|3.1.1|间接依赖|npm|
|error-ex|1.3.2|间接依赖|npm|
|read-pkg-up|7.0.1|间接依赖|npm|
|dedent|1.5.1|间接依赖|npm|
|toidentifier|1.0.1|间接依赖|npm|
|acorn-walk|8.2.0|间接依赖|npm|
|@types/tough-cookie|4.0.2|间接依赖|npm|
|bytes|3.0.0|间接依赖|npm|
|gensync|1.0.0-beta.2|间接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|jest-pnp-resolver|1.2.3|间接依赖|npm|
|combined-stream|1.0.8|间接依赖|npm|
|js-yaml|3.14.1|间接依赖|npm|
|handle-thing|2.0.1|间接依赖|npm|
|@babel/code-frame|7.22.13|间接依赖|npm|
|semver|6.3.1|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|lru-cache|6.0.0|间接依赖|npm|
|safe-regex-test|1.0.0|间接依赖|npm|
|@babel/plugin-syntax-nullish-coalescing-operator|7.8.3|间接依赖|npm|
|resize-observer-polyfill|1.5.1|直接依赖|npm|
|path-key|3.1.1|间接依赖|npm|
|onetime|5.1.2|间接依赖|npm|
|lodash.escape|4.0.1|间接依赖|npm|
|graphemer|1.4.0|间接依赖|npm|
|jest-resolve|29.6.4|间接依赖|npm|
|word-wrap|1.2.3|间接依赖|npm|
|@babel/plugin-transform-sticky-regex|7.22.5|间接依赖|npm|
|memfs|3.4.13|间接依赖|npm|
|jest-leak-detector|29.6.3|间接依赖|npm|
|@types/babel__template|7.4.1|间接依赖|npm|
|jest-snapshot|29.6.4|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|yargs|17.7.1|间接依赖|npm|
|strip-ansi|6.0.1|间接依赖|npm|
|parse-json|5.2.0|间接依赖|npm|
|jest-runner|29.6.4|间接依赖|npm|
|methods|1.1.2|间接依赖|npm|
|type-check|0.4.0|间接依赖|npm|
|is-docker|2.2.1|间接依赖|npm|
|postcss-modules-local-by-default|4.0.3|间接依赖|npm|
|reflect.getprototypeof|1.0.4|间接依赖|npm|
|retry|0.13.1|间接依赖|npm|
|find-cache-dir|4.0.0|间接依赖|npm|
|enzyme-adapter-utils|1.14.1|间接依赖|npm|
|commondir|1.0.1|间接依赖|npm|
|@babel/plugin-bugfix-v8-spread-parameters-in-optional-chaining|7.22.15|间接依赖|npm|
|@nodelib/fs.walk|1.2.8|间接依赖|npm|
|whatwg-url|11.0.0|间接依赖|npm|
|style-loader|3.3.3|直接依赖|npm|
|make-dir|3.1.0|间接依赖|npm|
|fs-monkey|1.0.3|间接依赖|npm|
|acorn|8.10.0|间接依赖|npm|
|chalk|4.1.2|间接依赖|npm|
|@jridgewell/trace-mapping|0.3.19|间接依赖|npm|
|npm-run-path|4.0.1|间接依赖|npm|
|istanbul-lib-source-maps|4.0.1|间接依赖|npm|
|walker|1.0.8|间接依赖|npm|
|@babel/plugin-syntax-dynamic-import|7.8.3|间接依赖|npm|
|clone-deep|4.0.1|间接依赖|npm|
|http-parser-js|0.5.8|间接依赖|npm|
|@types/retry|0.12.0|间接依赖|npm|
|debug|4.3.4|间接依赖|npm|
|@babel/plugin-bugfix-safari-id-destructuring-collision-in-function-expression|7.22.15|间接依赖|npm|
|regexp-tree|0.1.27|间接依赖|npm|
|content-disposition|0.5.4|间接依赖|npm|
|globals|11.12.0|间接依赖|npm|
|pretty-format|29.6.3|间接依赖|npm|
|jest-message-util|29.6.3|间接依赖|npm|
|@babel/preset-flow|7.22.15|直接依赖|npm|
|optionator|0.9.3|间接依赖|npm|
|tr46|3.0.0|间接依赖|npm|
|es-set-tostringtag|2.0.1|间接依赖|npm|
|@babel/plugin-transform-classes|7.22.15|间接依赖|npm|
|@types/stack-utils|2.0.1|间接依赖|npm|
|read-pkg|5.2.0|间接依赖|npm|
|@babel/plugin-transform-property-literals|7.22.5|间接依赖|npm|
|flat-cache|3.0.4|间接依赖|npm|
|camelcase|5.3.1|间接依赖|npm|
|array.prototype.tosorted|1.1.1|间接依赖|npm|
|asynckit|0.4.0|间接依赖|npm|
|inherits|2.0.3|间接依赖|npm|
|type-fest|0.8.1|间接依赖|npm|
|prelude-ls|1.2.1|间接依赖|npm|
|jest-environment-node|29.6.4|间接依赖|npm|
|@jest/reporters|29.6.4|间接依赖|npm|
|supports-preserve-symlinks-flag|1.0.0|间接依赖|npm|
|slash|3.0.0|间接依赖|npm|
|entities|4.4.0|间接依赖|npm|
|is-string|1.0.7|间接依赖|npm|
|argparse|2.0.1|间接依赖|npm|
|color-name|1.1.4|间接依赖|npm|
|fast-levenshtein|2.0.6|间接依赖|npm|
|emoji-regex|8.0.0|间接依赖|npm|
|babel-preset-current-node-syntax|1.0.1|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|@babel/plugin-transform-arrow-functions|7.22.5|间接依赖|npm|
|object-is|1.1.5|间接依赖|npm|
|@babel/plugin-syntax-private-property-in-object|7.14.5|间接依赖|npm|
|regenerator-transform|0.15.2|间接依赖|npm|
|emittery|0.13.1|间接依赖|npm|
|@babel/plugin-transform-unicode-escapes|7.22.10|间接依赖|npm|
|picocolors|1.0.0|间接依赖|npm|
|prop-types|15.8.1|间接依赖|npm|
|@webassemblyjs/wasm-parser|1.11.6|间接依赖|npm|
|indent-string|4.0.0|间接依赖|npm|
|jest-diff|29.6.4|间接依赖|npm|
|json-parse-even-better-errors|2.3.1|间接依赖|npm|
|@jest/globals|29.6.4|间接依赖|npm|
|reflect.ownkeys|0.2.0|间接依赖|npm|
|@webassemblyjs/wasm-opt|1.11.6|间接依赖|npm|
|loose-envify|1.4.0|间接依赖|npm|
|node-releases|2.0.13|间接依赖|npm|
|strip-final-newline|3.0.0|间接依赖|npm|
|prelude-ls|1.1.2|间接依赖|npm|
|jest|29.6.4|直接依赖|npm|
|@babel/plugin-transform-duplicate-keys|7.22.5|间接依赖|npm|
|eslint-plugin-flowtype|8.0.3|直接依赖|npm|
|path-type|4.0.0|间接依赖|npm|
|expect|29.6.4|间接依赖|npm|
|@jest/environment|29.6.4|间接依赖|npm|
|loader-utils|2.0.4|间接依赖|npm|
|saxes|6.0.0|间接依赖|npm|
|enzyme-adapter-react-16|1.15.7|直接依赖|npm|
|spdy|4.0.2|间接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|@webassemblyjs/helper-api-error|1.11.6|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|merge-descriptors|1.0.1|间接依赖|npm|
|@babel/preset-modules|0.1.6-no-external-plugins|间接依赖|npm|
|@webassemblyjs/wast-printer|1.11.6|间接依赖|npm|
|emoji-regex|9.2.2|间接依赖|npm|
|string.prototype.trimstart|1.0.6|间接依赖|npm|
|glob|7.2.3|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|shebang-command|2.0.0|间接依赖|npm|
|resolve-cwd|3.0.0|间接依赖|npm|
|@babel/helper-skip-transparent-expression-wrappers|7.22.5|间接依赖|npm|
|emojis-list|3.0.0|间接依赖|npm|
|ms|2.0.0|间接依赖|npm|
|@babel/cli|7.22.15|直接依赖|npm|
|babel-plugin-macros|3.1.0|间接依赖|npm|
|select-hose|2.0.0|间接依赖|npm|
|filelist|1.0.4|间接依赖|npm|
|whatwg-mimetype|3.0.0|间接依赖|npm|
|@nicolo-ribaudo/eslint-scope-5-internals|5.1.1-v1|间接依赖|npm|
|rst-selector-parser|2.2.3|间接依赖|npm|
|acorn-import-assertions|1.9.0|间接依赖|npm|
|type-fest|0.20.2|间接依赖|npm|
|ajv-formats|2.1.1|间接依赖|npm|
|typed-array-length|1.0.4|间接依赖|npm|
|jake|10.8.5|间接依赖|npm|
|reusify|1.0.4|间接依赖|npm|
|@babel/plugin-transform-new-target|7.22.5|间接依赖|npm|
|which|2.0.2|间接依赖|npm|
|minimatch|5.1.6|间接依赖|npm|
|ipaddr.js|2.0.1|间接依赖|npm|
|@babel/core|7.22.17|直接依赖|npm|
|has-proto|1.0.1|间接依赖|npm|
|co|4.6.0|间接依赖|npm|
|@babel/plugin-transform-spread|7.22.5|间接依赖|npm|
|yallist|4.0.0|间接依赖|npm|
|@babel/plugin-transform-unicode-property-regex|7.22.5|间接依赖|npm|
|type-check|0.3.2|间接依赖|npm|
|url-parse|1.5.10|间接依赖|npm|
|@humanwhocodes/module-importer|1.0.1|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|@babel/plugin-transform-logical-assignment-operators|7.22.11|间接依赖|npm|
|html-entities|2.3.3|间接依赖|npm|
|colorette|2.0.20|间接依赖|npm|
|npm-run-path|5.1.0|间接依赖|npm|
|@babel/plugin-syntax-json-strings|7.8.3|间接依赖|npm|
|core-util-is|1.0.3|间接依赖|npm|
|node-forge|1.3.1|间接依赖|npm|
|string.prototype.matchall|4.0.8|间接依赖|npm|
|@types/jsdom|20.0.1|间接依赖|npm|
|locate-path|3.0.0|间接依赖|npm|
|brace-expansion|2.0.1|间接依赖|npm|
|moo|0.5.2|间接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|pidtree|0.6.0|间接依赖|npm|
|callsites|3.1.0|间接依赖|npm|
|min-indent|1.0.1|间接依赖|npm|
|@babel/plugin-transform-reserved-words|7.22.5|间接依赖|npm|
|import-local|3.1.0|间接依赖|npm|
|json-schema-traverse|1.0.0|间接依赖|npm|
|path-exists|4.0.0|间接依赖|npm|
|@babel/plugin-syntax-unicode-sets-regex|7.18.6|间接依赖|npm|
|css-what|6.1.0|间接依赖|npm|
|querystringify|2.2.0|间接依赖|npm|
|eslint-plugin-mocha|10.1.0|直接依赖|npm|
|imports-loader|4.0.1|直接依赖|npm|
|@babel/plugin-syntax-class-static-block|7.14.5|间接依赖|npm|
|merge-stream|2.0.0|间接依赖|npm|
|@babel/plugin-transform-dotall-regex|7.22.5|间接依赖|npm|
|regenerate|1.4.2|间接依赖|npm|
|execa|5.1.1|间接依赖|npm|
|anymatch|3.1.3|间接依赖|npm|
|qs|6.11.0|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|@babel/helper-validator-identifier|7.22.15|间接依赖|npm|
|y18n|5.0.8|间接依赖|npm|
|ejs|3.1.9|直接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|ajv|8.12.0|间接依赖|npm|
|strip-json-comments|3.1.1|间接依赖|npm|
|loader-runner|4.3.0|间接依赖|npm|
|enzyme-shallow-equal|1.0.5|间接依赖|npm|
|yaml|2.3.1|间接依赖|npm|
|locate-path|6.0.0|间接依赖|npm|
|react-transform-hmr|1.0.4|直接依赖|npm|
|mimic-fn|4.0.0|间接依赖|npm|
|webpack|5.88.2|直接依赖|npm|
|has-symbols|1.0.3|间接依赖|npm|
|@types/body-parser|1.19.2|间接依赖|npm|
|readable-stream|2.3.8|间接依赖|npm|
|object-keys|1.1.1|间接依赖|npm|
|@babel/template|7.22.15|间接依赖|npm|
|http-proxy-agent|5.0.0|间接依赖|npm|
|pirates|4.0.5|间接依赖|npm|
|raw-body|2.5.1|间接依赖|npm|
|isarray|1.0.0|间接依赖|npm|
|js-yaml|4.1.0|间接依赖|npm|
|pkg-dir|7.0.0|间接依赖|npm|
|jsx-ast-utils|3.3.3|间接依赖|npm|
|@babel/plugin-transform-function-name|7.22.5|间接依赖|npm|
|deepmerge|4.3.0|间接依赖|npm|
|@types/serve-static|1.15.1|间接依赖|npm|
|execa|7.2.0|间接依赖|npm|
|schema-utils|4.0.0|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|parent-module|1.0.1|间接依赖|npm|
|pify|4.0.1|间接依赖|npm|
|@babel/helper-module-transforms|7.22.17|间接依赖|npm|
|@jridgewell/set-array|1.1.2|间接依赖|npm|
|test-exclude|6.0.0|间接依赖|npm|
|@babel/plugin-transform-async-to-generator|7.22.5|间接依赖|npm|
|husky|8.0.3|直接依赖|npm|
|text-table|0.2.0|间接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|serve-index|1.9.1|间接依赖|npm|
|@babel/helper-remap-async-to-generator|7.22.17|间接依赖|npm|
|@jest/source-map|29.6.3|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)