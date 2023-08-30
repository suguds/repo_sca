# iptv-org/iptv安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696954774107615232.svg)](https://www.murphysec.com/console/report/1691517624159981568/1696954774107615232)

仓库描述：Collection of publicly available IPTV channels from all over the world

仓库地址：[https://github.com/iptv-org/iptv](https://github.com/iptv-org/iptv)

| star：68016 | watch：1762 | fork：723 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-31 02:05:39 | 许可证：Unlicense |
| 最近检测时间：2023-08-31 02:35:51 | 组件总数：387 | 漏洞总数：3 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|colors.js  >1.4.0 DOS漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-19606](https://www.oscs1024.com/hd/MPS-2021-19606)|CVE-2021-23567|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|nwsapi 拒绝服务|拒绝服务|[MPS-2022-54623](https://www.oscs1024.com/hd/MPS-2022-54623)||中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|colors|1.4.0||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|nwsapi|2.2.0|2.2.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|6.3.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|319|Low|
|ISC|30|Low|
|BSD-3-Clause|15|Low|
|CC-BY-4.0|1|Low|
|Apache-2.0|8|Low|
|BSD-2-Clause|3|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|@babel/plugin-syntax-typescript|7.16.7|间接依赖|npm|
|deprecation|2.3.1|间接依赖|npm|
|babel-plugin-istanbul|6.1.1|间接依赖|npm|
|@jest/test-result|27.5.1|间接依赖|npm|
|get-stream|6.0.1|间接依赖|npm|
|resolve.exports|1.1.0|间接依赖|npm|
|jest-environment-jsdom|27.5.1|间接依赖|npm|
|m3u-linter|0.3.0|直接依赖|npm|
|jsonfile|6.1.0|间接依赖|npm|
|import-local|3.1.0|间接依赖|npm|
|@babel/plugin-syntax-numeric-separator|7.10.4|间接依赖|npm|
|caniuse-lite|1.0.30001481|间接依赖|npm|
|email-addresses|5.0.0|间接依赖|npm|
|@octokit/request-error|3.0.3|间接依赖|npm|
|pinkie|2.0.4|间接依赖|npm|
|axios-curlirize|1.3.7|间接依赖|npm|
|@jest/environment|27.5.1|间接依赖|npm|
|tr46|2.1.0|间接依赖|npm|
|shebang-command|2.0.0|间接依赖|npm|
|jest|27.5.1|直接依赖|npm|
|jest-resolve-dependencies|27.5.1|间接依赖|npm|
|callsites|3.1.0|间接依赖|npm|
|jest-util|27.5.1|间接依赖|npm|
|ci-info|3.3.0|间接依赖|npm|
|follow-redirects|1.14.8|间接依赖|npm|
|@types/istanbul-reports|3.0.1|间接依赖|npm|
|imurmurhash|0.1.4|间接依赖|npm|
|cliui|7.0.4|间接依赖|npm|
|cjs-module-lexer|1.2.2|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|jest-runner|27.5.1|间接依赖|npm|
|localforage|1.10.0|间接依赖|npm|
|@istanbuljs/schema|0.1.3|间接依赖|npm|
|signale|1.4.0|直接依赖|npm|
|stack-utils|2.0.5|间接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|chalk|4.1.2|直接依赖|npm|
|acorn|8.7.0|间接依赖|npm|
|yallist|4.0.0|间接依赖|npm|
|jest-cli|27.5.1|间接依赖|npm|
|@babel/template|7.16.7|间接依赖|npm|
|@octokit/types|9.3.0|间接依赖|npm|
|@babel/generator|7.17.0|间接依赖|npm|
|test-exclude|6.0.0|间接依赖|npm|
|@seald-io/nedb|2.2.0|间接依赖|npm|
|universalify|0.1.2|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|babel-plugin-jest-hoist|27.5.1|间接依赖|npm|
|istanbul-lib-coverage|3.2.0|间接依赖|npm|
|@types/yargs-parser|20.2.1|间接依赖|npm|
|babel-preset-jest|27.5.1|间接依赖|npm|
|@babel/plugin-syntax-object-rest-spread|7.8.3|间接依赖|npm|
|async|3.2.4|间接依赖|npm|
|w3c-xmlserializer|2.0.0|间接依赖|npm|
|resolve|1.22.0|间接依赖|npm|
|@jridgewell/trace-mapping|0.3.4|间接依赖|npm|
|emittery|0.8.1|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|@babel/code-frame|7.16.7|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|@jridgewell/resolve-uri|3.0.5|间接依赖|npm|
|@types/graceful-fs|4.1.5|间接依赖|npm|
|saxes|5.0.1|间接依赖|npm|
|@babel/helper-validator-option|7.16.7|间接依赖|npm|
|@jest/core|27.5.1|间接依赖|npm|
|co|4.6.0|间接依赖|npm|
|colors|1.4.0|间接依赖|npm|
|micromatch|4.0.4|间接依赖|npm|
|supports-color|8.1.1|间接依赖|npm|
|mimic-fn|2.1.0|间接依赖|npm|
|pkg-conf|2.1.0|间接依赖|npm|
|@babel/helper-function-name|7.16.7|间接依赖|npm|
|tough-cookie|4.1.3|间接依赖|npm|
|jest-haste-map|27.5.1|间接依赖|npm|
|jest-runtime|27.5.1|间接依赖|npm|
|terminal-link|2.1.1|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|@jest/transform|27.5.1|间接依赖|npm|
|picocolors|1.0.0|间接依赖|npm|
|jest-validate|27.5.1|间接依赖|npm|
|debug|4.3.3|间接依赖|npm|
|babel-preset-current-node-syntax|1.0.1|间接依赖|npm|
|camelcase|5.3.1|间接依赖|npm|
|istanbul-reports|3.1.4|间接依赖|npm|
|lodash|4.17.21|直接依赖|npm|
|jest-worker|27.5.1|间接依赖|npm|
|source-map|0.6.1|直接依赖|npm|
|string-width|4.2.2|间接依赖|npm|
|write-file-atomic|3.0.3|间接依赖|npm|
|globby|6.1.0|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|strip-final-newline|2.0.0|间接依赖|npm|
|electron-to-chromium|1.4.69|间接依赖|npm|
|array-union|1.0.2|间接依赖|npm|
|node-fetch|2.6.11|间接依赖|npm|
|@sinonjs/commons|1.8.3|间接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|@babel/plugin-syntax-optional-catch-binding|7.8.3|间接依赖|npm|
|glob|7.1.6|间接依赖|npm|
|@babel/plugin-syntax-class-properties|7.12.13|间接依赖|npm|
|@octokit/request|6.2.5|间接依赖|npm|
|char-regex|1.0.2|间接依赖|npm|
|type-fest|0.21.3|间接依赖|npm|
|makeerror|1.0.12|间接依赖|npm|
|diff-sequences|27.5.1|间接依赖|npm|
|istanbul-lib-report|3.0.0|间接依赖|npm|
|throat|6.0.1|间接依赖|npm|
|path-exists|3.0.0|间接依赖|npm|
|jest-message-util|27.5.1|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|command-exists|1.2.9|间接依赖|npm|
|whatwg-url|8.7.0|间接依赖|npm|
|supports-hyperlinks|2.2.0|间接依赖|npm|
|source-map|0.7.3|间接依赖|npm|
|webidl-conversions|6.1.0|间接依赖|npm|
|is-arrayish|0.2.1|间接依赖|npm|
|is-invalid-path|0.1.0|间接依赖|npm|
|find-up|2.1.0|间接依赖|npm|
|istanbul-lib-instrument|5.1.0|间接依赖|npm|
|path-key|3.1.1|间接依赖|npm|
|array-uniq|1.0.3|间接依赖|npm|
|jest-mock|27.5.1|间接依赖|npm|
|gh-pages|5.0.0|直接依赖|npm|
|node-int64|0.4.0|间接依赖|npm|
|emoji-regex|8.0.0|间接依赖|npm|
|@types/babel__core|7.1.18|间接依赖|npm|
|semver|6.3.1|间接依赖|npm|
|form-data|3.0.1|间接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|xml-name-validator|3.0.0|间接依赖|npm|
|fsevents|2.3.2|直接依赖|npm|
|@jest/reporters|27.5.1|间接依赖|npm|
|is-core-module|2.8.1|间接依赖|npm|
|fs-extra|10.0.0|直接依赖|npm|
|load-json-file|4.0.0|间接依赖|npm|
|execa|5.1.1|间接依赖|npm|
|@octokit/graphql|5.0.6|间接依赖|npm|
|jest-expect-message|1.0.2|直接依赖|npm|
|@babel/plugin-syntax-bigint|7.8.3|间接依赖|npm|
|universal-user-agent|6.0.0|间接依赖|npm|
|babel-jest|27.5.1|间接依赖|npm|
|detect-newline|3.1.0|间接依赖|npm|
|@babel/helper-module-transforms|7.16.7|间接依赖|npm|
|@jest/fake-timers|27.5.1|间接依赖|npm|
|filenamify|4.3.0|间接依赖|npm|
|exit|0.1.2|间接依赖|npm|
|camelcase|6.3.0|间接依赖|npm|
|leven|3.1.0|间接依赖|npm|
|expect|27.5.1|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|strip-json-comments|3.1.1|间接依赖|npm|
|w3c-hr-time|1.0.2|间接依赖|npm|
|markdown-include|0.4.3|直接依赖|npm|
|@types/istanbul-lib-coverage|2.0.4|间接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|@types/yargs|16.0.4|间接依赖|npm|
|kleur|3.0.3|间接依赖|npm|
|@babel/compat-data|7.17.0|间接依赖|npm|
|normalize-url|6.1.0|直接依赖|npm|
|is-extglob|1.0.0|间接依赖|npm|
|@octokit/core|4.2.1|直接依赖|npm|
|npm-run-path|4.0.1|间接依赖|npm|
|is-typedarray|1.0.0|间接依赖|npm|
|@babel/plugin-syntax-top-level-await|7.14.5|间接依赖|npm|
|trim-repeated|1.0.0|间接依赖|npm|
|has-flag|4.0.0|间接依赖|npm|
|jest-snapshot|27.5.1|间接依赖|npm|
|buffer-from|1.1.2|间接依赖|npm|
|acorn-globals|6.0.0|间接依赖|npm|
|@octokit/openapi-types|18.0.0|间接依赖|npm|
|onetime|5.1.2|间接依赖|npm|
|jest-watcher|27.5.1|间接依赖|npm|
|commander|7.2.0|间接依赖|npm|
|jest-serializer|27.5.1|间接依赖|npm|
|collect-v8-coverage|1.0.1|间接依赖|npm|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|progress|2.0.3|间接依赖|npm|
|filename-reserved-regex|2.0.0|间接依赖|npm|
|v8-to-istanbul|8.1.1|间接依赖|npm|
|@babel/plugin-syntax-async-generators|7.8.4|间接依赖|npm|
|symbol-tree|3.2.4|间接依赖|npm|
|fb-watchman|2.0.1|间接依赖|npm|
|universalify|2.0.0|间接依赖|npm|
|y18n|5.0.5|间接依赖|npm|
|@babel/plugin-syntax-nullish-coalescing-operator|7.8.3|间接依赖|npm|
|ansi-styles|5.2.0|间接依赖|npm|
|@octokit/plugin-paginate-rest|7.0.0|直接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|pretty-format|27.5.1|间接依赖|npm|
|@babel/helper-validator-identifier|7.16.7|间接依赖|npm|
|@babel/core|7.17.2|直接依赖|npm|
|pify|2.3.0|间接依赖|npm|
|cross-spawn|7.0.3|间接依赖|npm|
|convert-source-map|1.8.0|间接依赖|npm|
|is-valid-path|0.1.1|间接依赖|npm|
|jest-jasmine2|27.5.1|间接依赖|npm|
|@babel/traverse|7.17.0|间接依赖|npm|
|error-ex|1.3.2|间接依赖|npm|
|@jest/source-map|27.5.1|间接依赖|npm|
|nwsapi|2.2.0|间接依赖|npm|
|html-encoding-sniffer|2.0.1|间接依赖|npm|
|is-generator-fn|2.1.0|间接依赖|npm|
|jsdom|16.7.0|间接依赖|npm|
|jsonfile|4.0.0|间接依赖|npm|
|@babel/helper-split-export-declaration|7.16.7|间接依赖|npm|
|whatwg-encoding|1.0.5|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|ansi-escapes|4.3.2|间接依赖|npm|
|https-proxy-agent|5.0.0|间接依赖|npm|
|dedent|0.7.0|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|@types/prettier|2.4.4|间接依赖|npm|
|@types/babel__generator|7.6.4|间接依赖|npm|
|locate-path|5.0.0|间接依赖|npm|
|is-plain-object|5.0.0|间接依赖|npm|
|valid-url|1.0.9|间接依赖|npm|
|source-map-support|0.5.21|间接依赖|npm|
|@babel/helpers|7.17.2|间接依赖|npm|
|color-convert|2.0.1|间接依赖|npm|
|whatwg-mimetype|2.3.0|间接依赖|npm|
|color-name|1.1.4|间接依赖|npm|
|@jest/types|27.5.1|间接依赖|npm|
|@types/istanbul-lib-report|3.0.0|间接依赖|npm|
|ws|7.5.7|间接依赖|npm|
|@babel/helper-compilation-targets|7.16.7|间接依赖|npm|
|locate-path|2.0.0|间接依赖|npm|
|escape-string-regexp|2.0.0|间接依赖|npm|
|@babel/helper-get-function-arity|7.16.7|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|@babel/parser|7.17.0|间接依赖|npm|
|supports-color|7.2.0|间接依赖|npm|
|@seald-io/binary-search-tree|1.0.2|间接依赖|npm|
|tr46|0.0.3|间接依赖|npm|
|is-potential-custom-element-name|1.0.1|间接依赖|npm|
|cssom|0.4.4|间接依赖|npm|
|cssstyle|2.3.0|间接依赖|npm|
|anymatch|3.1.2|间接依赖|npm|
|deepmerge|4.2.2|间接依赖|npm|
|nedb-promises|5.0.2|直接依赖|npm|
|jest-circus|27.5.1|间接依赖|npm|
|@alex_neo/jest-expect-message|1.0.5|直接依赖|npm|
|bser|2.1.1|间接依赖|npm|
|semver|7.5.4|间接依赖|npm|
|@types/babel__traverse|7.14.2|间接依赖|npm|
|strip-bom|3.0.0|间接依赖|npm|
|lodash.chunk|4.2.0|间接依赖|npm|
|wrap-ansi|7.0.0|间接依赖|npm|
|fs-extra|8.1.0|间接依赖|npm|
|jest-environment-node|27.5.1|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|domexception|2.0.1|间接依赖|npm|
|parse5|6.0.1|间接依赖|npm|
|@babel/plugin-syntax-logical-assignment-operators|7.10.4|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|whatwg-url|5.0.0|间接依赖|npm|
|http-proxy-agent|4.0.1|间接依赖|npm|
|jest-regex-util|27.5.1|间接依赖|npm|
|human-signals|2.1.0|间接依赖|npm|
|browserslist|4.19.1|间接依赖|npm|
|which|2.0.2|间接依赖|npm|
|prompts|2.4.2|间接依赖|npm|
|is-stream|2.0.1|间接依赖|npm|
|@babel/helper-plugin-utils|7.16.7|间接依赖|npm|
|p-limit|1.3.0|间接依赖|npm|
|lines-and-columns|1.2.4|间接依赖|npm|
|parse-json|4.0.0|间接依赖|npm|
|before-after-hook|2.2.3|间接依赖|npm|
|jsesc|2.5.2|间接依赖|npm|
|to-fast-properties|2.0.0|间接依赖|npm|
|json-parse-even-better-errors|2.3.1|间接依赖|npm|
|data-urls|2.0.0|间接依赖|npm|
|resolve-cwd|3.0.0|间接依赖|npm|
|jest-leak-detector|27.5.1|间接依赖|npm|
|@octokit/endpoint|7.0.6|间接依赖|npm|
|@bcoe/v8-coverage|0.2.3|间接依赖|npm|
|@jest/test-sequencer|27.5.1|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|@sinonjs/fake-timers|8.1.0|间接依赖|npm|
|@babel/highlight|7.16.10|间接依赖|npm|
|parse-json|5.2.0|间接依赖|npm|
|p-limit|2.3.0|间接依赖|npm|
|picomatch|2.3.1|间接依赖|npm|
|graceful-fs|4.2.9|直接依赖|npm|
|resolve-from|5.0.0|间接依赖|npm|
|ansi-styles|4.3.0|间接依赖|npm|
|@octokit/tsconfig|1.0.2|间接依赖|npm|
|natural-compare|1.4.0|间接依赖|npm|
|iptv-checker|0.26.0|直接依赖|npm|
|commander|8.3.0|直接依赖|npm|
|@jest/console|27.5.1|间接依赖|npm|
|async|0.2.10|间接依赖|npm|
|make-dir|3.1.0|间接依赖|npm|
|jest-matcher-utils|27.5.1|间接依赖|npm|
|strip-outer|1.0.1|间接依赖|npm|
|walker|1.0.8|间接依赖|npm|
|punycode|2.1.1|间接依赖|npm|
|path-exists|4.0.0|间接依赖|npm|
|abab|2.0.5|间接依赖|npm|
|strip-bom|4.0.0|间接依赖|npm|
|is-glob|2.0.1|间接依赖|npm|
|tmpl|1.0.5|间接依赖|npm|
|@types/babel__template|7.4.1|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|jest-docblock|27.5.1|间接依赖|npm|
|signal-exit|3.0.7|间接依赖|npm|
|decimal.js|10.3.1|间接依赖|npm|
|node-releases|2.0.2|间接依赖|npm|
|pify|3.0.0|间接依赖|npm|
|find-up|4.1.0|间接依赖|npm|
|react-is|17.0.2|间接依赖|npm|
|typedarray-to-buffer|3.1.5|间接依赖|npm|
|jest-config|27.5.1|间接依赖|npm|
|@babel/types|7.17.0|间接依赖|npm|
|sisteransi|1.0.5|间接依赖|npm|
|escodegen|2.0.0|间接依赖|npm|
|@babel/plugin-syntax-json-strings|7.8.3|间接依赖|npm|
|json-parse-better-errors|1.0.2|直接依赖|npm|
|@istanbuljs/load-nyc-config|1.1.0|间接依赖|npm|
|lie|3.1.1|间接依赖|npm|
|@babel/plugin-syntax-optional-chaining|7.8.3|间接依赖|npm|
|supports-preserve-symlinks-flag|1.0.0|间接依赖|npm|
|find-cache-dir|3.3.2|间接依赖|npm|
|yargs-parser|20.2.6|间接依赖|npm|
|slash|3.0.0|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|immediate|3.0.6|间接依赖|npm|
|pinkie-promise|2.0.1|间接依赖|npm|
|strip-ansi|6.0.0|间接依赖|npm|
|jest-each|27.5.1|间接依赖|npm|
|axios|0.21.4|间接依赖|npm|
|get-stdin|7.0.0|间接依赖|npm|
|@ampproject/remapping|2.1.1|间接依赖|npm|
|@babel/helper-simple-access|7.16.7|间接依赖|npm|
|source-map|0.5.7|间接依赖|npm|
|@jest/globals|27.5.1|间接依赖|npm|
|webidl-conversions|3.0.1|间接依赖|npm|
|pkg-dir|4.2.0|间接依赖|npm|
|q|1.5.1|间接依赖|npm|
|@types/stack-utils|2.0.1|间接依赖|npm|
|rimraf|3.0.2|间接依赖|npm|
|commondir|1.0.1|间接依赖|npm|
|@octokit/auth-token|3.0.4|间接依赖|npm|
|istanbul-lib-source-maps|4.0.1|间接依赖|npm|
|jest-pnp-resolver|1.2.2|间接依赖|npm|
|js-yaml|3.14.1|间接依赖|npm|
|html-escaper|2.0.2|间接依赖|npm|
|jest-resolve|27.5.1|直接依赖|npm|
|jest-get-type|27.5.1|间接依赖|npm|
|iptv-playlist-parser|0.12.1|直接依赖|npm|
|gensync|1.0.0-beta.2|间接依赖|npm|
|@types/node|17.0.18|间接依赖|npm|
|yargs|16.2.0|间接依赖|npm|
|transliteration|2.2.0|直接依赖|npm|
|p-locate|2.0.0|间接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.11|间接依赖|npm|
|@babel/helper-hoist-variables|7.16.7|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|json5|2.2.3|间接依赖|npm|
|dateformat|3.0.3|间接依赖|npm|
|commander|2.20.3|间接依赖|npm|
|validator|13.7.0|间接依赖|npm|
|@babel/plugin-syntax-import-meta|7.10.4|间接依赖|npm|
|dayjs|1.10.7|直接依赖|npm|
|pirates|4.0.5|间接依赖|npm|
|globals|11.12.0|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|jest-diff|27.5.1|间接依赖|npm|
|figures|2.0.0|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|merge-stream|2.0.0|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|natural-orderby|2.0.3|直接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|jest-changed-files|27.5.1|间接依赖|npm|
|get-package-type|0.1.0|间接依赖|npm|
|@babel/helper-environment-visitor|7.16.7|间接依赖|npm|
|color-name|1.1.3|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|p-locate|4.1.0|间接依赖|npm|
|lru-cache|6.0.0|直接依赖|npm|
|@babel/helper-module-imports|7.16.7|间接依赖|npm|
|string-length|4.0.2|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)