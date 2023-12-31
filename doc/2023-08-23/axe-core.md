# dequelabs/axe-core安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694057018104307712.svg)](https://www.murphysec.com/console/report/1694057017605185536/1694057018104307712)

仓库描述：Accessibility engine for automated Web UI testing

仓库地址：[https://github.com/dequelabs/axe-core](https://github.com/dequelabs/axe-core)

| star：5253 | watch：179 | fork：755 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-23 02:37:02 | 许可证：MPL-2.0 |
| 最近检测时间：2023-08-23 02:41:06 | 组件总数：846 | 漏洞总数：7 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|socket.io 拒绝服务漏洞|拒绝服务|[MPS-15wb-xgoz](https://www.oscs1024.com/hd/MPS-15wb-xgoz)|CVE-2023-32695|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|ua-parser-js 安全漏洞|ReDoS|[MPS-2022-5202](https://www.oscs1024.com/hd/MPS-2022-5202)|CVE-2022-25927|高危|
|word-wrap 安全漏洞|ReDoS|[MPS-2023-5109](https://www.oscs1024.com/hd/MPS-2023-5109)|CVE-2023-26115|高危|
|tough-cookie 安全漏洞|原型污染|[MPS-2023-5130](https://www.oscs1024.com/hd/MPS-2023-5130)|CVE-2023-26136|严重|
|Engine.IO 存在拒绝服务漏洞||[MPS-b79p-4aco](https://www.oscs1024.com/hd/MPS-b79p-4aco)|CVE-2023-31125|中危|
|tough-cookie<4.1.3 存在原型污染漏洞|原型污染|[MPS-esyq-56vx](https://www.oscs1024.com/hd/MPS-esyq-56vx)||中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|socket.io-parser|4.2.1|4.2.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|word-wrap|1.2.3|1.2.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tough-cookie|4.1.2|4.1.3|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|engine.io|6.2.1|6.4.2|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|ua-parser-js|0.7.32|1.0.33|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|semver|6.3.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|674|Low|
|ISC|62|Low|
|BSD-2-Clause|22|Low|
|BSD-3-Clause|22|Low|
|Unlicense|1|Low|
|Apache-2.0|23|Low|
|自定义许可证|2|Low|
|CC-BY-4.0|1|Low|
|CC0-1.0|1|Low|
|Python-2.0|1|Low|
|Apache 2.0|1|Low|
|MPL-2.0|2|Low|
|BSD|1|Low|
|0BSD|1|Low|
|CC-BY-3.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|di|0.0.1|间接依赖|npm|
|aria-practices|git+ssh://git@github.com/w3c/aria-practices.git#ce0336bd82d7d3651abcbde86af644197ddbc629|直接依赖|npm|
|unicode-match-property-value-ecmascript|2.0.0|间接依赖|npm|
|whatwg-url|11.0.0|间接依赖|npm|
|homedir-polyfill|1.0.3|间接依赖|npm|
|interpret|1.1.0|间接依赖|npm|
|bytes|3.1.2|间接依赖|npm|
|grunt-known-options|2.0.0|间接依赖|npm|
|decimal.js|10.4.2|间接依赖|npm|
|deep-eql|4.1.2|间接依赖|npm|
|fast-levenshtein|2.0.6|间接依赖|npm|
|path-exists|4.0.0|间接依赖|npm|
|node-releases|2.0.6|间接依赖|npm|
|uuid|8.3.2|间接依赖|npm|
|is-weakmap|2.0.1|间接依赖|npm|
|@octokit/openapi-types|12.11.0|间接依赖|npm|
|log-update|4.0.0|间接依赖|npm|
|@babel/plugin-transform-object-super|7.18.6|间接依赖|npm|
|js-sdsl|4.1.5|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|add-stream|1.0.0|间接依赖|npm|
|colorette|2.0.19|间接依赖|npm|
|uglify-js|3.17.4|间接依赖|npm|
|arrify|1.0.1|间接依赖|npm|
|convert-source-map|1.9.0|间接依赖|npm|
|@babel/helper-compilation-targets|7.20.7|间接依赖|npm|
|nopt|3.0.6|间接依赖|npm|
|http-errors|2.0.0|间接依赖|npm|
|@tootallnate/once|2.0.0|间接依赖|npm|
|corser|2.0.1|间接依赖|npm|
|ansi-styles|4.3.0|间接依赖|npm|
|es-get-iterator|1.1.2|间接依赖|npm|
|iconv-lite|0.4.24|间接依赖|npm|
|is-typed-array|1.1.10|间接依赖|npm|
|strip-bom|3.0.0|间接依赖|npm|
|is-negative-zero|2.0.2|间接依赖|npm|
|object.map|1.0.1|间接依赖|npm|
|axios|1.3.4|间接依赖|npm|
|@babel/runtime|7.20.1|间接依赖|npm|
|hard-rejection|2.1.0|间接依赖|npm|
|@jridgewell/gen-mapping|0.1.1|间接依赖|npm|
|@octokit/plugin-rest-endpoint-methods|5.16.2|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|mkdirp|1.0.4|间接依赖|npm|
|cli-spinners|2.9.0|间接依赖|npm|
|@babel/plugin-transform-block-scoped-functions|7.18.6|间接依赖|npm|
|@babel/plugin-syntax-async-generators|7.8.4|间接依赖|npm|
|read-pkg-up|7.0.1|间接依赖|npm|
|available-typed-arrays|1.0.5|间接依赖|npm|
|@sinonjs/fake-timers|7.1.2|间接依赖|npm|
|url-join|4.0.1|间接依赖|npm|
|chardet|0.7.0|间接依赖|npm|
|markdown-it-anchor|8.6.5|间接依赖|npm|
|chalk|4.1.2|间接依赖|npm|
|formdata-polyfill|4.0.10|直接依赖|npm|
|json-parse-better-errors|1.0.2|间接依赖|npm|
|onetime|5.1.2|间接依赖|npm|
|@babel/highlight|7.18.6|间接依赖|npm|
|@types/yauzl|2.10.0|间接依赖|npm|
|markdown-it|12.3.2|间接依赖|npm|
|w3c-xmlserializer|4.0.0|间接依赖|npm|
|is-promise|2.2.2|间接依赖|npm|
|array-each|1.0.1|间接依赖|npm|
|string.prototype.trimstart|1.0.6|间接依赖|npm|
|arg|5.0.2|间接依赖|npm|
|deep-equal|2.1.0|间接依赖|npm|
|css-selector-parser|1.4.1|直接依赖|npm|
|get-stream|6.0.1|间接依赖|npm|
|is2|2.0.9|间接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|toidentifier|1.0.1|间接依赖|npm|
|type-check|0.4.0|间接依赖|npm|
|is-core-module|2.11.0|间接依赖|npm|
|buffer|5.7.1|间接依赖|npm|
|object-keys|1.1.1|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|content-disposition|0.5.2|间接依赖|npm|
|cssom|0.5.0|间接依赖|npm|
|escape-string-regexp|4.0.0|间接依赖|npm|
|doctrine|3.0.0|间接依赖|npm|
|string_decoder|1.1.1|间接依赖|npm|
|css-select|4.3.0|间接依赖|npm|
|abbrev|1.1.1|间接依赖|npm|
|regexp.prototype.flags|1.4.3|间接依赖|npm|
|es5-ext|0.10.62|间接依赖|npm|
|rimraf|3.0.2|间接依赖|npm|
|prelude-ls|1.2.1|间接依赖|npm|
|git-remote-origin-url|2.0.0|间接依赖|npm|
|es6-promise|4.2.8|直接依赖|npm|
|@hapi/topo|5.1.0|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|mocha|10.2.0|直接依赖|npm|
|@babel/plugin-bugfix-safari-id-destructuring-collision-in-function-expression|7.18.6|间接依赖|npm|
|neo-async|2.6.2|间接依赖|npm|
|picomatch|2.3.1|间接依赖|npm|
|conventional-commits-parser|3.2.4|间接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|joi|17.7.0|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|@eslint/eslintrc|1.4.1|间接依赖|npm|
|error|7.2.1|间接依赖|npm|
|@babel/helper-builder-binary-assignment-operator-visitor|7.18.9|间接依赖|npm|
|rechoir|0.7.1|间接依赖|npm|
|execa|5.1.1|间接依赖|npm|
|cookie|0.4.2|间接依赖|npm|
|esutils|2.0.3|间接依赖|npm|
|is-symbol|1.0.4|间接依赖|npm|
|type-fest|0.21.3|间接依赖|npm|
|@babel/plugin-syntax-numeric-separator|7.10.4|间接依赖|npm|
|@babel/plugin-transform-for-of|7.18.8|间接依赖|npm|
|combined-stream|1.0.8|间接依赖|npm|
|@octokit/request-error|2.1.0|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|strip-final-newline|2.0.0|间接依赖|npm|
|gzip-size|5.1.1|间接依赖|npm|
|@babel/helper-create-regexp-features-plugin|7.19.0|间接依赖|npm|
|is-map|2.0.2|间接依赖|npm|
|@sideway/pinpoint|2.0.0|间接依赖|npm|
|grunt-babel|8.0.0|直接依赖|npm|
|wait-on|6.0.1|间接依赖|npm|
|deep-is|0.1.4|间接依赖|npm|
|grunt-legacy-util|2.0.1|间接依赖|npm|
|@babel/plugin-proposal-object-rest-spread|7.20.7|间接依赖|npm|
|domexception|4.0.0|间接依赖|npm|
|ws|8.11.0|间接依赖|npm|
|@babel/helper-remap-async-to-generator|7.18.9|间接依赖|npm|
|negotiator|0.6.3|间接依赖|npm|
|listr2|5.0.6|间接依赖|npm|
|is-potential-custom-element-name|1.0.1|间接依赖|npm|
|optionator|0.9.1|间接依赖|npm|
|binary-extensions|2.2.0|间接依赖|npm|
|is-shared-array-buffer|1.0.2|间接依赖|npm|
|object-inspect|1.12.2|间接依赖|npm|
|path-is-inside|1.0.2|间接依赖|npm|
|accepts|1.3.8|间接依赖|npm|
|is-regex|1.1.4|间接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|osenv|0.1.5|直接依赖|npm|
|unbox-primitive|1.0.2|间接依赖|npm|
|@babel/plugin-proposal-optional-chaining|7.18.9|间接依赖|npm|
|meow|8.1.2|间接依赖|npm|
|astral-regex|2.0.0|直接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|@babel/plugin-transform-property-literals|7.18.6|间接依赖|npm|
|babel-plugin-polyfill-regenerator|0.4.1|间接依赖|npm|
|domhandler|4.3.1|间接依赖|npm|
|JSONStream|1.3.5|间接依赖|npm|
|os-tmpdir|1.0.2|间接依赖|npm|
|qs|6.11.0|间接依赖|npm|
|npm-run-path|4.0.1|间接依赖|npm|
|@babel/helper-replace-supers|7.19.1|间接依赖|npm|
|@babel/plugin-syntax-top-level-await|7.14.5|间接依赖|npm|
|@babel/plugin-syntax-private-property-in-object|7.14.5|间接依赖|npm|
|ee-first|1.1.1|间接依赖|npm|
|ignore|5.2.0|间接依赖|npm|
|querystringify|2.2.0|间接依赖|npm|
|merge-stream|2.0.0|间接依赖|npm|
|is-stream|2.0.1|间接依赖|npm|
|pathval|1.1.1|间接依赖|npm|
|body|5.1.0|间接依赖|npm|
|ip-regex|4.3.0|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|es6-symbol|3.1.3|间接依赖|npm|
|mime|1.6.0|间接依赖|npm|
|grunt-contrib-concat|2.1.0|直接依赖|npm|
|lint-staged|13.1.0|直接依赖|npm|
|yocto-queue|0.1.0|间接依赖|npm|
|is-bigint|1.0.4|间接依赖|npm|
|chokidar|3.5.3|间接依赖|npm|
|defaults|1.0.4|间接依赖|npm|
|domelementtype|2.3.0|间接依赖|npm|
|sinon|15.0.1|直接依赖|npm|
|mdurl|1.0.1|间接依赖|npm|
|core-util-is|1.0.3|间接依赖|npm|
|color-convert|2.0.1|间接依赖|npm|
|parseurl|1.3.3|间接依赖|npm|
|async|3.2.4|间接依赖|npm|
|diff|5.0.0|间接依赖|npm|
|@testim/chrome-version|1.1.3|间接依赖|npm|
|asynckit|0.4.0|间接依赖|npm|
|picocolors|1.0.0|间接依赖|npm|
|jsonfile|4.0.0|间接依赖|npm|
|memorystream|0.3.1|间接依赖|npm|
|@babel/plugin-syntax-optional-chaining|7.8.3|间接依赖|npm|
|@babel/template|7.20.7|间接依赖|npm|
|color-name|1.1.4|间接依赖|npm|
|@babel/plugin-transform-typeof-symbol|7.18.9|间接依赖|npm|
|check-error|1.0.2|间接依赖|npm|
|@babel/plugin-proposal-export-namespace-from|7.18.9|间接依赖|npm|
|eslint-plugin-mocha-no-only|1.1.1|直接依赖|npm|
|os-homedir|1.0.2|间接依赖|npm|
|string-width|5.1.2|间接依赖|npm|
|flatted|3.2.7|间接依赖|npm|
|@babel/plugin-transform-block-scoping|7.20.2|间接依赖|npm|
|@babel/helper-split-export-declaration|7.18.6|间接依赖|npm|
|lodash.debounce|4.0.8|间接依赖|npm|
|tr46|3.0.0|间接依赖|npm|
|estraverse|5.3.0|间接依赖|npm|
|supports-color|7.2.0|间接依赖|npm|
|supports-preserve-symlinks-flag|1.0.0|间接依赖|npm|
|serialize-javascript|6.0.0|间接依赖|npm|
|ora|5.4.1|间接依赖|npm|
|outdent|0.8.0|直接依赖|npm|
|@hutson/parse-repository-url|3.0.2|间接依赖|npm|
|git-semver-tags|4.1.1|间接依赖|npm|
|portfinder|1.0.32|间接依赖|npm|
|is-number|7.0.0|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|to-fast-properties|2.0.0|间接依赖|npm|
|electron-to-chromium|1.4.284|间接依赖|npm|
|cli-width|3.0.0|间接依赖|npm|
|@babel/generator|7.20.7|间接依赖|npm|
|make-dir|3.1.0|直接依赖|npm|
|path-key|3.1.1|间接依赖|npm|
|which-typed-array|1.1.9|间接依赖|npm|
|eslint-scope|7.1.1|间接依赖|npm|
|@nodelib/fs.scandir|2.1.5|间接依赖|npm|
|@babel/plugin-transform-unicode-escapes|7.18.10|间接依赖|npm|
|isarray|2.0.5|间接依赖|npm|
|data-urls|3.0.2|间接依赖|npm|
|regjsparser|0.9.1|间接依赖|npm|
|compare-versions|5.0.1|间接依赖|npm|
|pako|1.0.11|间接依赖|npm|
|es6-weak-map|2.0.3|间接依赖|npm|
|@babel/helper-define-polyfill-provider|0.3.3|间接依赖|npm|
|internal-slot|1.0.3|间接依赖|npm|
|@babel/plugin-proposal-numeric-separator|7.18.6|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|split|1.0.1|间接依赖|npm|
|dotenv|16.0.3|间接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|event-emitter|0.3.5|间接依赖|npm|
|is-object|1.0.2|间接依赖|npm|
|which|2.0.2|间接依赖|npm|
|@jridgewell/resolve-uri|3.1.0|间接依赖|npm|
|http-parser-js|0.5.8|间接依赖|npm|
|@octokit/request|5.6.3|间接依赖|npm|
|is-plain-obj|1.1.0|间接依赖|npm|
|side-channel|1.0.4|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|@types/cors|2.8.12|间接依赖|npm|
|html-entities|1.4.0|直接依赖|npm|
|secure-compare|3.0.1|间接依赖|npm|
|expand-tilde|2.0.2|间接依赖|npm|
|marked|4.2.2|间接依赖|npm|
|html-encoding-sniffer|3.0.0|间接依赖|npm|
|p-limit|3.1.0|间接依赖|npm|
|start-server-and-test|1.15.2|直接依赖|npm|
|stringify-package|1.0.1|间接依赖|npm|
|escape-html|1.0.3|间接依赖|npm|
|indent-string|4.0.0|间接依赖|npm|
|@jridgewell/set-array|1.1.2|间接依赖|npm|
|@humanwhocodes/object-schema|1.2.1|间接依赖|npm|
|proxyquire|2.1.3|直接依赖|npm|
|@babel/helper-optimise-call-expression|7.18.6|间接依赖|npm|
|pretty-bytes|5.6.0|间接依赖|npm|
|nice-try|1.0.5|直接依赖|npm|
|@nodelib/fs.stat|2.0.5|间接依赖|npm|
|@sinonjs/commons|1.8.5|间接依赖|npm|
|wrap-ansi|7.0.0|间接依赖|npm|
|cssstyle|2.3.0|间接依赖|npm|
|browserslist|4.21.4|间接依赖|npm|
|caniuse-lite|1.0.30001431|间接依赖|npm|
|jsesc|2.5.2|间接依赖|npm|
|levn|0.4.1|间接依赖|npm|
|engine.io|6.2.1|间接依赖|npm|
|@sinonjs/samsam|7.0.1|间接依赖|npm|
|regenerator-runtime|0.13.11|间接依赖|npm|
|validate-npm-package-license|3.0.4|间接依赖|npm|
|assertion-error|1.1.0|间接依赖|npm|
|basic-auth|2.0.1|间接依赖|npm|
|wordwrap|1.0.0|间接依赖|npm|
|conventional-changelog-eslint|3.0.9|间接依赖|npm|
|string-argv|0.3.1|间接依赖|npm|
|@octokit/types|6.41.0|间接依赖|npm|
|node-fetch|2.6.7|间接依赖|npm|
|@babel/helper-hoist-variables|7.18.6|间接依赖|npm|
|core-js-pure|3.26.1|间接依赖|npm|
|@babel/helper-plugin-utils|7.20.2|间接依赖|npm|
|cross-spawn|7.0.3|间接依赖|npm|
|memoizee|0.4.15|直接依赖|npm|
|readable-stream|2.3.7|间接依赖|npm|
|qjobs|1.2.0|间接依赖|npm|
|process-nextick-args|2.0.1|间接依赖|npm|
|p-try|1.0.0|直接依赖|npm|
|@babel/plugin-proposal-class-properties|7.18.6|间接依赖|npm|
|check-more-types|2.24.0|间接依赖|npm|
|array-slice|1.1.0|间接依赖|npm|
|liftup|3.0.1|间接依赖|npm|
|git-raw-commits|2.0.11|间接依赖|npm|
|@types/cookie|0.4.1|间接依赖|npm|
|conventional-changelog|3.1.25|间接依赖|npm|
|continuable-cache|0.3.1|间接依赖|npm|
|@colors/colors|1.5.0|间接依赖|npm|
|@sinonjs/text-encoding|0.7.2|间接依赖|npm|
|symbol-tree|3.2.4|间接依赖|npm|
|statuses|1.5.0|间接依赖|npm|
|pidtree|0.6.0|间接依赖|npm|
|@octokit/auth-token|2.5.0|间接依赖|npm|
|underscore.string|3.3.6|间接依赖|npm|
|resolve-from|4.0.0|间接依赖|npm|
|nise|5.1.2|间接依赖|npm|
|jszip|3.10.1|间接依赖|npm|
|conventional-changelog-angular|5.0.13|间接依赖|npm|
|buffer-crc32|0.2.13|间接依赖|npm|
|loupe|2.3.6|间接依赖|npm|
|requires-port|1.0.0|间接依赖|npm|
|is-binary-path|2.1.0|间接依赖|npm|
|is-boolean-object|1.1.2|间接依赖|npm|
|@babel/code-frame|7.18.6|间接依赖|npm|
|parse-json|4.0.0|间接依赖|npm|
|eastasianwidth|0.2.0|间接依赖|npm|
|yaml|2.1.3|间接依赖|npm|
|just-extend|4.2.1|间接依赖|npm|
|engine.io-parser|5.0.4|间接依赖|npm|
|@babel/plugin-transform-modules-amd|7.19.6|间接依赖|npm|
|human-signals|2.1.0|间接依赖|npm|
|@babel/plugin-transform-modules-commonjs|7.19.6|间接依赖|npm|
|grunt-legacy-log|3.0.0|间接依赖|npm|
|slash|3.0.0|间接依赖|npm|
|karma|6.4.1|直接依赖|npm|
|pump|3.0.0|直接依赖|npm|
|requireindex|1.1.0|间接依赖|npm|
|@babel/plugin-proposal-logical-assignment-operators|7.18.9|间接依赖|npm|
|run-parallel|1.2.0|间接依赖|npm|
|typescript|4.9.4|直接依赖|npm|
|gopd|1.0.1|间接依赖|npm|
|findup-sync|0.3.0|间接依赖|npm|
|spdx-license-ids|3.0.12|间接依赖|npm|
|micromatch|4.0.5|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|@babel/helper-validator-identifier|7.19.1|间接依赖|npm|
|end-of-stream|1.4.4|间接依赖|npm|
|dom-serializer|1.4.1|间接依赖|npm|
|lodash.get|4.4.2|间接依赖|npm|
|dir-glob|3.0.1|间接依赖|npm|
|conventional-changelog-preset-loader|2.3.4|间接依赖|npm|
|@babel/plugin-transform-classes|7.20.2|间接依赖|npm|
|conventional-changelog-jshint|2.0.9|间接依赖|npm|
|log4js|6.7.0|间接依赖|npm|
|is-string|1.0.7|间接依赖|npm|
|regenerator-transform|0.15.0|间接依赖|npm|
|acorn|8.8.1|间接依赖|npm|
|safe-regex-test|1.0.0|间接依赖|npm|
|nanoid|3.3.3|间接依赖|npm|
|media-typer|0.3.0|间接依赖|npm|
|locate-path|6.0.0|间接依赖|npm|
|decamelize|1.2.0|间接依赖|npm|
|@babel/helper-environment-visitor|7.18.9|间接依赖|npm|
|is-url|1.2.4|间接依赖|npm|
|natural-compare|1.4.0|间接依赖|npm|
|karma-chrome-launcher|3.1.1|直接依赖|npm|
|@types/normalize-package-data|2.4.1|直接依赖|npm|
|json-stringify-safe|5.0.1|间接依赖|npm|
|spdx-correct|3.1.1|间接依赖|npm|
|ext|1.7.0|间接依赖|npm|
|browser-stdout|1.3.1|间接依赖|npm|
|aggregate-error|3.1.0|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|array-ify|1.0.0|间接依赖|npm|
|http-server|14.1.1|直接依赖|npm|
|grunt-contrib-uglify|5.2.2|直接依赖|npm|
|grunt-legacy-log-utils|2.1.0|间接依赖|npm|
|@octokit/graphql|4.8.0|间接依赖|npm|
|universal-user-agent|6.0.0|间接依赖|npm|
|is-number-object|1.0.7|间接依赖|npm|
|reusify|1.0.4|间接依赖|npm|
|@babel/plugin-syntax-class-properties|7.12.13|间接依赖|npm|
|grunt-bytesize|0.2.0|直接依赖|npm|
|weakmap-polyfill|2.0.4|直接依赖|npm|
|regexpu-core|5.2.1|间接依赖|npm|
|uc.micro|1.0.6|间接依赖|npm|
|colors|1.1.2|间接依赖|npm|
|pend|1.2.0|间接依赖|npm|
|requizzle|0.2.3|间接依赖|npm|
|strip-json-comments|3.1.1|间接依赖|npm|
|destroy|1.2.0|间接依赖|npm|
|is-callable|1.2.7|间接依赖|npm|
|split2|3.2.2|间接依赖|npm|
|hooker|0.2.3|间接依赖|npm|
|socket.io-adapter|2.4.0|间接依赖|npm|
|@babel/plugin-proposal-optional-catch-binding|7.18.6|间接依赖|npm|
|selenium-webdriver|4.7.1|直接依赖|npm|
|path-type|4.0.0|间接依赖|npm|
|js-yaml|4.1.0|间接依赖|npm|
|@sideway/formula|3.0.1|间接依赖|npm|
|core-js-compat|3.26.1|间接依赖|npm|
|@babel/plugin-transform-member-expression-literals|7.18.6|间接依赖|npm|
|@babel/parser|7.20.7|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|exit|0.1.2|间接依赖|npm|
|source-map|0.5.7|间接依赖|npm|
|merge-descriptors|1.0.1|间接依赖|npm|
|@babel/helper-function-name|7.19.0|间接依赖|npm|
|type-is|1.6.18|间接依赖|npm|
|object.pick|1.3.0|间接依赖|npm|
|external-editor|3.1.0|间接依赖|npm|
|parse5|7.1.1|间接依赖|npm|
|repeat-string|1.6.1|间接依赖|npm|
|call-bind|1.0.2|间接依赖|npm|
|argparse|2.0.1|间接依赖|npm|
|minami|1.2.3|直接依赖|npm|
|esbuild|0.10.2|直接依赖|npm|
|@babel/plugin-syntax-class-static-block|7.14.5|间接依赖|npm|
|graceful-fs|4.2.10|间接依赖|npm|
|linkify-it|3.0.3|间接依赖|npm|
|decamelize-keys|1.1.1|间接依赖|npm|
|duplexer|0.1.2|间接依赖|npm|
|regenerate-unicode-properties|10.1.0|间接依赖|npm|
|@babel/plugin-syntax-nullish-coalescing-operator|7.8.3|间接依赖|npm|
|resolve|1.22.1|间接依赖|npm|
|@humanwhocodes/config-array|0.11.8|间接依赖|npm|
|anymatch|3.1.2|间接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|saxes|6.0.0|间接依赖|npm|
|type|1.2.0|间接依赖|npm|
|livereload-js|2.4.0|间接依赖|npm|
|@babel/plugin-transform-destructuring|7.20.2|间接依赖|npm|
|he|1.2.0|间接依赖|npm|
|revalidator|0.3.1|直接依赖|npm|
|ent|2.2.0|间接依赖|npm|
|fastq|1.13.0|间接依赖|npm|
|@babel/plugin-transform-async-to-generator|7.18.6|间接依赖|npm|
|pause-stream|0.0.11|间接依赖|npm|
|is-absolute|1.0.0|间接依赖|npm|
|markdown-table|2.0.0|直接依赖|npm|
|trim-newlines|3.0.1|间接依赖|npm|
|camelcase|5.3.1|间接依赖|npm|
|emoji-regex|10.2.1|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|is-weakset|2.0.2|间接依赖|npm|
|is-wsl|2.2.0|间接依赖|npm|
|which-boxed-primitive|1.0.2|间接依赖|npm|
|nth-check|2.1.1|间接依赖|npm|
|xmlchars|2.2.0|间接依赖|npm|
|conventional-changelog-jquery|3.0.11|间接依赖|npm|
|@octokit/core|3.6.0|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|is-path-inside|3.0.3|间接依赖|npm|
|husky|8.0.3|直接依赖|npm|
|hosted-git-info|4.1.0|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|whatwg-mimetype|3.0.0|间接依赖|npm|
|import-fresh|3.3.0|间接依赖|npm|
|es6-iterator|2.0.3|间接依赖|npm|
|kind-of|6.0.3|间接依赖|npm|
|@babel/plugin-transform-literals|7.18.9|间接依赖|npm|
|string.prototype.trimend|1.0.6|间接依赖|npm|
|is-fullwidth-code-point|4.0.0|间接依赖|npm|
|websocket-extensions|0.1.4|间接依赖|npm|
|setimmediate|1.0.5|间接依赖|npm|
|lilconfig|2.0.6|间接依赖|npm|
|strip-ansi|6.0.1|间接依赖|npm|
|workerpool|6.2.1|间接依赖|npm|
|minimist-options|4.1.0|间接依赖|npm|
|@babel/plugin-syntax-optional-catch-binding|7.8.3|间接依赖|npm|
|@babel/plugin-syntax-object-rest-spread|7.8.3|间接依赖|npm|
|data-uri-to-buffer|4.0.0|直接依赖|npm|
|eslint-config-prettier|8.6.0|直接依赖|npm|
|gensync|1.0.0-beta.2|间接依赖|npm|
|for-in|1.0.2|间接依赖|npm|
|@axe-core/webdriverjs|4.5.2|直接依赖|npm|
|extend|3.0.2|间接依赖|npm|
|klaw|3.0.0|间接依赖|npm|
|d|1.0.1|间接依赖|npm|
|dateformat|3.0.3|间接依赖|npm|
|ps-tree|1.2.0|间接依赖|npm|
|slice-ansi|5.0.0|间接依赖|npm|
|@jridgewell/trace-mapping|0.3.17|间接依赖|npm|
|agent-base|6.0.2|间接依赖|npm|
|conventional-changelog-ember|2.0.9|间接依赖|npm|
|lru-queue|0.1.0|间接依赖|npm|
|run-async|2.4.1|间接依赖|npm|
|is-weakref|1.0.2|间接依赖|npm|
|@babel/plugin-transform-shorthand-properties|7.18.6|间接依赖|npm|
|debug|4.3.4|间接依赖|npm|
|@babel/helper-module-imports|7.18.6|间接依赖|npm|
|lie|3.3.0|间接依赖|npm|
|cli-cursor|3.1.0|间接依赖|npm|
|v8flags|3.2.0|间接依赖|npm|
|standard-version|9.5.0|直接依赖|npm|
|is-unicode-supported|0.1.0|间接依赖|npm|
|esquery|1.4.0|间接依赖|npm|
|bl|4.1.0|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|cors|2.8.5|间接依赖|npm|
|is-arrayish|0.2.1|间接依赖|npm|
|maxmin|3.0.0|间接依赖|npm|
|quick-lru|4.0.1|间接依赖|npm|
|@babel/helper-module-transforms|7.20.11|间接依赖|npm|
|@babel/plugin-transform-modules-systemjs|7.19.6|间接依赖|npm|
|@babel/helper-string-parser|7.19.4|间接依赖|npm|
|sri-toolbox|0.2.0|直接依赖|npm|
|range-parser|1.2.1|间接依赖|npm|
|vary|1.1.2|间接依赖|npm|
|aria-query|5.1.3|直接依赖|npm|
|path-root|0.1.1|间接依赖|npm|
|minimist|1.2.7|间接依赖|npm|
|fined|1.2.0|间接依赖|npm|
|@babel/plugin-proposal-unicode-property-regex|7.18.6|间接依赖|npm|
|regenerate|1.4.2|间接依赖|npm|
|@babel/plugin-syntax-import-assertions|7.20.0|间接依赖|npm|
|map-stream|0.1.0|间接依赖|npm|
|raw-body|2.5.1|间接依赖|npm|
|delayed-stream|1.0.0|间接依赖|npm|
|merge2|1.4.1|间接依赖|npm|
|timers-ext|0.1.7|间接依赖|npm|
|tcp-port-used|1.0.2|间接依赖|npm|
|functions-have-names|1.2.3|间接依赖|npm|
|rfdc|1.3.0|间接依赖|npm|
|has-symbols|1.0.3|间接依赖|npm|
|text-extensions|1.9.0|间接依赖|npm|
|@sideway/address|4.1.4|间接依赖|npm|
|fast-glob|3.2.12|间接依赖|npm|
|eslint-visitor-keys|3.3.0|间接依赖|npm|
|find-up|5.0.0|间接依赖|npm|
|conventional-changelog-conventionalcommits|4.6.3|间接依赖|npm|
|tmp|0.2.1|间接依赖|npm|
|update-browserslist-db|1.0.10|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|xtend|4.0.2|直接依赖|npm|
|catharsis|0.9.0|间接依赖|npm|
|http-proxy-agent|5.0.0|间接依赖|npm|
|@babel/runtime-corejs3|7.20.7|直接依赖|npm|
|bluebird|3.7.2|间接依赖|npm|
|dom-serialize|2.2.1|间接依赖|npm|
|yargs-parser|20.2.9|间接依赖|npm|
|object.defaults|1.1.0|间接依赖|npm|
|fs-extra|8.1.0|间接依赖|npm|
|load-json-file|4.0.0|间接依赖|npm|
|@babel/helper-validator-option|7.18.6|间接依赖|npm|
|dargs|7.0.0|间接依赖|npm|
|sprintf-js|1.1.2|间接依赖|npm|
|through|2.3.8|间接依赖|npm|
|word-wrap|1.2.3|间接依赖|npm|
|through2|4.0.2|间接依赖|npm|
|grunt|1.5.3|直接依赖|npm|
|modify-values|1.0.1|间接依赖|npm|
|xmlcreate|2.0.4|间接依赖|npm|
|grunt-contrib-clean|2.0.1|直接依赖|npm|
|@babel/plugin-syntax-json-strings|7.8.3|间接依赖|npm|
|glob|7.1.7|间接依赖|npm|
|@types/minimist|1.2.2|间接依赖|npm|
|ua-parser-js|0.7.32|间接依赖|npm|
|globule|1.3.4|间接依赖|npm|
|encodeurl|1.0.2|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|@ampproject/remapping|2.2.0|间接依赖|npm|
|from|0.1.7|间接依赖|npm|
|get-symbol-description|1.0.0|间接依赖|npm|
|ini|1.3.8|间接依赖|npm|
|lodash.ismatch|4.4.0|间接依赖|npm|
|ajv|6.12.6|间接依赖|npm|
|esprima|4.0.1|间接依赖|npm|
|readdirp|3.6.0|间接依赖|npm|
|jsdoc|3.6.11|直接依赖|npm|
|randombytes|2.1.0|间接依赖|npm|
|restore-cursor|3.1.0|间接依赖|npm|
|punycode|1.4.1|间接依赖|npm|
|fill-keys|1.0.2|间接依赖|npm|
|es-to-primitive|1.2.1|间接依赖|npm|
|typedarray|0.0.7|间接依赖|npm|
|@socket.io/component-emitter|3.1.0|间接依赖|npm|
|espree|9.4.1|间接依赖|npm|
|socket.io|4.5.3|间接依赖|npm|
|detect-indent|6.1.0|间接依赖|npm|
|read-pkg|3.0.0|间接依赖|npm|
|p-locate|5.0.0|间接依赖|npm|
|conventional-changelog-express|2.0.6|间接依赖|npm|
|@babel/preset-modules|0.1.5|间接依赖|npm|
|has-tostringtag|1.0.0|间接依赖|npm|
|lazy-ass|1.6.0|间接依赖|npm|
|@babel/plugin-transform-spread|7.19.0|间接依赖|npm|
|has-bigints|1.0.2|间接依赖|npm|
|@octokit/plugin-paginate-rest|2.21.3|间接依赖|npm|
|map-cache|0.2.2|间接依赖|npm|
|dot-prop|5.3.0|间接依赖|npm|
|grunt-contrib-watch|1.1.0|直接依赖|npm|
|@babel/plugin-transform-computed-properties|7.18.9|间接依赖|npm|
|connect|3.7.0|间接依赖|npm|
|@babel/compat-data|7.20.10|间接依赖|npm|
|@babel/plugin-syntax-dynamic-import|7.8.3|间接依赖|npm|
|shellwords|0.1.1|间接依赖|npm|
|is-interactive|1.0.0|间接依赖|npm|
|@nodelib/fs.walk|1.2.8|间接依赖|npm|
|@babel/plugin-transform-template-literals|7.18.9|间接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|function.prototype.name|1.1.5|间接依赖|npm|
|custom-event|1.0.1|间接依赖|npm|
|redent|3.0.0|间接依赖|npm|
|utils-merge|1.0.1|间接依赖|npm|
|boolbase|1.0.0|间接依赖|npm|
|on-finished|2.4.1|间接依赖|npm|
|which-collection|1.0.1|间接依赖|npm|
|file-entry-cache|6.0.1|间接依赖|npm|
|get-func-name|2.0.0|间接依赖|npm|
|@babel/preset-env|7.20.2|直接依赖|npm|
|rxjs|7.5.7|间接依赖|npm|
|@babel/plugin-proposal-json-strings|7.18.6|间接依赖|npm|
|is-text-path|1.0.1|间接依赖|npm|
|@babel/plugin-proposal-class-static-block|7.18.6|间接依赖|npm|
|whatwg-encoding|2.0.0|间接依赖|npm|
|normalize-package-data|3.0.3|间接依赖|npm|
|is-glob|4.0.3|间接依赖|npm|
|@octokit/endpoint|6.0.12|间接依赖|npm|
|@humanwhocodes/module-importer|1.0.1|间接依赖|npm|
|void-elements|2.0.1|间接依赖|npm|
|uri-path|1.0.0|间接依赖|npm|
|@babel/core|7.20.12|直接依赖|npm|
|url-parse|1.5.10|间接依赖|npm|
|make-iterator|1.0.1|间接依赖|npm|
|css-what|6.1.0|间接依赖|npm|
|parse-passwd|1.0.0|间接依赖|npm|
|setprototypeof|1.2.0|间接依赖|npm|
|growly|1.3.0|间接依赖|npm|
|unpipe|1.0.0|间接依赖|npm|
|underscore|1.13.6|间接依赖|npm|
|type-detect|4.0.8|间接依赖|npm|
|signal-exit|3.0.7|间接依赖|npm|
|parent-module|1.0.1|间接依赖|npm|
|conventional-changelog-writer|5.0.1|间接依赖|npm|
|@babel/plugin-transform-new-target|7.18.6|间接依赖|npm|
|xml-name-validator|4.0.0|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|@octokit/rest|18.12.0|间接依赖|npm|
|conventional-changelog-codemirror|2.0.8|间接依赖|npm|
|@babel/plugin-transform-named-capturing-groups-regex|7.19.1|间接依赖|npm|
|karma-firefox-launcher|2.1.2|直接依赖|npm|
|is-arguments|1.1.1|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|for-own|1.0.0|间接依赖|npm|
|buffer-from|1.1.2|间接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.14|间接依赖|npm|
|yargs-unparser|2.0.0|间接依赖|npm|
|https-proxy-agent|5.0.1|间接依赖|npm|
|websocket-driver|0.7.4|间接依赖|npm|
|module-not-found-error|1.0.1|间接依赖|npm|
|path-to-regexp|2.2.1|间接依赖|npm|
|pify|4.0.1|间接依赖|npm|
|node-notifier|10.0.1|直接依赖|npm|
|proxy-from-env|1.1.0|间接依赖|npm|
|karma-sinon|1.0.5|直接依赖|npm|
|next-tick|1.1.0|间接依赖|npm|
|concat-stream|2.0.0|间接依赖|npm|
|streamroller|3.1.3|间接依赖|npm|
|browser-driver-manager|1.0.4|直接依赖|npm|
|prettier|2.8.2|直接依赖|npm|
|parse-filepath|1.0.2|间接依赖|npm|
|socket.io-parser|4.2.1|间接依赖|npm|
|@babel/plugin-transform-duplicate-keys|7.18.9|间接依赖|npm|
|base64id|2.0.0|间接依赖|npm|
|clone|2.1.2|间接依赖|npm|
|@octokit/plugin-request-log|1.0.4|间接依赖|npm|
|opener|1.5.2|间接依赖|npm|
|json-stable-stringify-without-jsonify|1.0.1|间接依赖|npm|
|conventional-changelog-atom|2.0.8|间接依赖|npm|
|faye-websocket|0.10.0|间接依赖|npm|
|json5|2.2.3|间接依赖|npm|
|acorn-globals|7.0.1|间接依赖|npm|
|object.assign|4.1.4|间接依赖|npm|
|abab|2.0.6|间接依赖|npm|
|cliui|7.0.4|间接依赖|npm|
|@babel/plugin-bugfix-v8-spread-parameters-in-optional-chaining|7.18.9|间接依赖|npm|
|unicode-canonical-property-names-ecmascript|2.0.0|间接依赖|npm|
|@babel/helper-explode-assignable-expression|7.18.6|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|define-properties|1.1.4|间接依赖|npm|
|@hapi/hoek|9.3.0|间接依赖|npm|
|mime-db|1.52.0|间接依赖|npm|
|@babel/helper-simple-access|7.20.2|间接依赖|npm|
|has-property-descriptors|1.0.0|间接依赖|npm|
|colorjs.io|0.4.3|直接依赖|npm|
|ieee754|1.2.1|间接依赖|npm|
|@babel/plugin-transform-sticky-regex|7.18.6|间接依赖|npm|
|karma-spec-reporter|0.0.36|直接依赖|npm|
|chromedriver|111.0.0|直接依赖|npm|
|q|1.5.1|间接依赖|npm|
|acorn-jsx|5.3.2|间接依赖|npm|
|queue-microtask|1.2.3|间接依赖|npm|
|depd|2.0.0|间接依赖|npm|
|conventional-changelog-config-spec|2.1.0|间接依赖|npm|
|web-streams-polyfill|3.2.1|间接依赖|npm|
|lodash.merge|4.6.2|间接依赖|npm|
|http-proxy|1.18.1|间接依赖|npm|
|@babel/plugin-syntax-export-namespace-from|7.8.3|间接依赖|npm|
|taffydb|2.6.2|间接依赖|npm|
|@babel/plugin-transform-arrow-functions|7.18.6|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|nwsapi|2.2.2|间接依赖|npm|
|wcwidth|1.0.1|间接依赖|npm|
|glob-parent|6.0.2|间接依赖|npm|
|karma-chai|0.1.0|直接依赖|npm|
|jquery|3.6.3|直接依赖|npm|
|isobject|3.0.1|间接依赖|npm|
|@babel/helper-skip-transparent-expression-wrappers|7.20.0|间接依赖|npm|
|@babel/plugin-transform-reserved-words|7.18.6|间接依赖|npm|
|escodegen|2.0.0|间接依赖|npm|
|karma-ie-launcher|1.0.0|直接依赖|npm|
|@babel/plugin-transform-function-name|7.18.9|间接依赖|npm|
|gitconfiglocal|1.0.0|间接依赖|npm|
|fd-slicer|1.1.0|间接依赖|npm|
|array-union|2.1.0|间接依赖|npm|
|yauzl|2.10.0|间接依赖|npm|
|flat-cache|3.0.4|间接依赖|npm|
|extract-zip|2.0.1|间接依赖|npm|
|@babel/plugin-transform-regenerator|7.18.6|间接依赖|npm|
|string.prototype.padend|3.1.4|间接依赖|npm|
|is-set|2.0.2|间接依赖|npm|
|map-obj|4.3.0|间接依赖|npm|
|es-abstract|1.20.4|间接依赖|npm|
|conventional-commits-filter|2.0.7|间接依赖|npm|
|eslint-utils|3.0.0|间接依赖|npm|
|safe-json-parse|1.0.1|间接依赖|npm|
|handlebars|4.7.7|间接依赖|npm|
|fsevents|2.3.2|间接依赖|npm|
|unicode-match-property-ecmascript|2.0.0|间接依赖|npm|
|error-ex|1.3.2|间接依赖|npm|
|globals|11.12.0|间接依赖|npm|
|conventional-recommended-bump|6.1.0|间接依赖|npm|
|jsdom|21.0.0|直接依赖|npm|
|@types/markdown-it|12.2.3|间接依赖|npm|
|callsites|3.1.0|间接依赖|npm|
|min-indent|1.0.1|间接依赖|npm|
|text-table|0.2.0|间接依赖|npm|
|humanize|0.0.7|间接依赖|npm|
|semver|6.3.0|间接依赖|npm|
|eslint|8.31.0|直接依赖|npm|
|fast-url-parser|1.1.3|间接依赖|npm|
|y18n|5.0.8|间接依赖|npm|
|figures|3.2.0|间接依赖|npm|
|form-data|4.0.0|间接依赖|npm|
|union|0.5.0|间接依赖|npm|
|finalhandler|1.1.2|间接依赖|npm|
|wcag-act-rules|git+ssh://git@github.com/w3c/wcag-act-rules.git#2341a1ba4d47bc4cdccd5a3b7534e67b52c59002|直接依赖|npm|
|detect-newline|3.1.0|间接依赖|npm|
|has-flag|4.0.0|间接依赖|npm|
|babel-plugin-polyfill-corejs3|0.6.0|间接依赖|npm|
|universalify|0.1.2|间接依赖|npm|
|flat|5.0.2|间接依赖|npm|
|before-after-hook|2.2.3|间接依赖|npm|
|immediate|3.0.6|间接依赖|npm|
|regexpp|3.2.0|间接依赖|npm|
|tough-cookie|4.1.2|间接依赖|npm|
|get-intrinsic|1.1.3|间接依赖|npm|
|karma-mocha|2.0.1|直接依赖|npm|
|is-obj|2.0.0|间接依赖|npm|
|base64-js|1.5.1|间接依赖|npm|
|acorn-walk|8.2.0|间接依赖|npm|
|for-each|0.3.3|间接依赖|npm|
|mime-types|2.1.35|间接依赖|npm|
|body-parser|1.20.1|间接依赖|npm|
|esrecurse|4.3.0|间接依赖|npm|
|eventemitter2|0.4.14|间接依赖|npm|
|lru-cache|6.0.0|间接依赖|npm|
|lines-and-columns|1.2.4|直接依赖|npm|
|tiny-lr|1.1.1|间接依赖|npm|
|conventional-changelog-core|4.2.4|间接依赖|npm|
|@types/node|18.11.9|间接依赖|npm|
|chai|4.3.7|直接依赖|npm|
|@babel/helper-member-expression-to-functions|7.18.9|间接依赖|npm|
|@babel/helpers|7.20.7|间接依赖|npm|
|@babel/helper-wrap-function|7.19.0|间接依赖|npm|
|npm-run-all|4.1.5|直接依赖|npm|
|stream-combiner|0.0.4|间接依赖|npm|
|serve-handler|6.1.5|直接依赖|npm|
|is-docker|2.2.1|间接依赖|npm|
|get-pkg-repo|4.2.1|间接依赖|npm|
|@types/linkify-it|3.0.2|间接依赖|npm|
|psl|1.9.0|间接依赖|npm|
|@babel/types|7.20.7|间接依赖|npm|
|@babel/plugin-proposal-async-generator-functions|7.20.1|间接依赖|npm|
|@babel/traverse|7.20.12|间接依赖|npm|
|axe-core|4.6.2|间接依赖|npm|
|jsonparse|1.3.1|间接依赖|npm|
|flagged-respawn|1.0.1|间接依赖|npm|
|p-map|4.0.0|间接依赖|npm|
|@babel/plugin-transform-unicode-regex|7.18.6|间接依赖|npm|
|@babel/plugin-transform-parameters|7.20.7|间接依赖|npm|
|@babel/plugin-syntax-logical-assignment-operators|7.10.4|间接依赖|npm|
|core-js|3.27.1|直接依赖|npm|
|json-parse-even-better-errors|2.3.1|直接依赖|npm|
|isbinaryfile|4.0.10|间接依赖|npm|
|cli-truncate|3.1.0|间接依赖|npm|
|fetch-blob|3.2.0|间接依赖|npm|
|@babel/helper-create-class-features-plugin|7.20.2|间接依赖|npm|
|grapheme-splitter|1.0.4|间接依赖|npm|
|yallist|4.0.0|间接依赖|npm|
|is-plain-object|5.0.0|间接依赖|npm|
|eventemitter3|4.0.7|间接依赖|npm|
|@babel/plugin-proposal-dynamic-import|7.18.6|间接依赖|npm|
|follow-redirects|1.15.2|间接依赖|npm|
|@types/mdurl|1.0.2|间接依赖|npm|
|node-domexception|1.0.0|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|js2xmlparser|4.0.2|间接依赖|npm|
|inquirer|8.2.5|直接依赖|npm|
|dotgitignore|2.1.0|间接依赖|npm|
|tslib|2.4.1|间接依赖|npm|
|content-type|1.0.4|间接依赖|npm|
|@babel/plugin-transform-exponentiation-operator|7.18.6|间接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|spdx-expression-parse|3.0.1|间接依赖|npm|
|shell-quote|1.7.4|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|@babel/plugin-proposal-private-property-in-object|7.18.6|间接依赖|npm|
|gaze|1.1.3|间接依赖|npm|
|domutils|2.8.0|间接依赖|npm|
|log-symbols|4.1.0|间接依赖|npm|
|date-format|4.0.14|间接依赖|npm|
|compare-func|2.0.0|间接依赖|npm|
|spdx-exceptions|2.3.0|间接依赖|npm|
|ansi-colors|4.1.1|间接依赖|npm|
|event-stream|3.3.4|间接依赖|npm|
|shebang-regex|3.0.0|间接依赖|npm|
|webidl-conversions|7.0.0|间接依赖|npm|
|object-is|1.1.5|间接依赖|npm|
|bytesize|0.2.0|间接依赖|npm|
|@babel/helper-annotate-as-pure|7.18.6|间接依赖|npm|
|@babel/plugin-transform-modules-umd|7.18.6|间接依赖|npm|
|globby|11.1.0|直接依赖|npm|
|string-template|0.2.1|间接依赖|npm|
|regjsgen|0.7.1|间接依赖|npm|
|@babel/plugin-proposal-private-methods|7.18.6|间接依赖|npm|
|is-date-object|1.0.5|间接依赖|npm|
|babel-plugin-polyfill-corejs2|0.3.3|间接依赖|npm|
|imurmurhash|0.1.4|间接依赖|npm|
|detect-file|1.0.0|直接依赖|npm|
|mimic-fn|2.1.0|间接依赖|npm|
|unicode-property-aliases-ecmascript|2.1.0|间接依赖|npm|
|deprecation|2.3.1|间接依赖|npm|
|@babel/plugin-transform-dotall-regex|7.18.6|间接依赖|npm|
|mute-stream|0.0.8|间接依赖|npm|
|entities|2.1.0|间接依赖|npm|
|ansi-escapes|4.3.2|间接依赖|npm|
|strip-indent|3.0.0|间接依赖|npm|
|@babel/plugin-proposal-nullish-coalescing-operator|7.18.6|间接依赖|npm|
|getobject|1.0.2|间接依赖|npm|
|grunt-cli|1.4.3|间接依赖|npm|
|node-html-parser|5.4.2|间接依赖|npm|
|shebang-command|2.0.0|间接依赖|npm|
|@deque/dot|1.1.5|直接依赖|npm|
|commander|9.4.1|间接依赖|npm|
|clean-stack|2.2.0|间接依赖|npm|
|yargs|16.2.0|间接依赖|npm|
|camelcase-keys|6.2.2|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)