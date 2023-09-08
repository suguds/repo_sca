# fent/node-ytdl-core安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700216973052133376.svg)](https://www.murphysec.com/console/report/1700216972402016256/1700216973052133376)

仓库描述：YouTube video downloader in javascript.

仓库地址：[https://github.com/fent/node-ytdl-core](https://github.com/fent/node-ytdl-core)

| star：3955 | watch：95 | fork：693 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-07-19 20:16:28 | 许可证：MIT |
| 最近检测时间：2023-09-09 02:38:17 | 组件总数：386 | 漏洞总数：14 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Http-signature 安全漏洞|密码学签名的验证不恰当|[MPS-2018-6996](https://www.oscs1024.com/hd/MPS-2018-6996)|CVE-2017-16005|高危|
|Npm Node-tar 后置链接漏洞||[MPS-2021-28486](https://www.oscs1024.com/hd/MPS-2021-28486)|CVE-2021-37701|高危|
|Npm Node-tar 后置链接漏洞||[MPS-2021-28488](https://www.oscs1024.com/hd/MPS-2021-28488)|CVE-2021-37712|高危|
|node-tar 路径遍历漏洞|路径遍历|[MPS-2021-28489](https://www.oscs1024.com/hd/MPS-2021-28489)|CVE-2021-37713|高危|
|minimist 安全漏洞|原型污染|[MPS-2021-38405](https://www.oscs1024.com/hd/MPS-2021-38405)|CVE-2021-44906|严重|
|lodash.set 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13843](https://www.oscs1024.com/hd/MPS-2022-13843)||高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|mocha ReDoS 漏洞|ReDoS|[MPS-2022-54598](https://www.oscs1024.com/hd/MPS-2022-54598)||高危|
|Tauri 原型污染漏洞|原型污染|[MPS-2022-65568](https://www.oscs1024.com/hd/MPS-2022-65568)|CVE-2022-46175|高危|
|flat 原型污染漏洞|原型污染|[MPS-2022-69541](https://www.oscs1024.com/hd/MPS-2022-69541)|CVE-2020-36632|中危|
|word-wrap 安全漏洞|ReDoS|[MPS-2023-5109](https://www.oscs1024.com/hd/MPS-2023-5109)|CVE-2023-26115|高危|
|tough-cookie 安全漏洞|原型污染|[MPS-2023-5130](https://www.oscs1024.com/hd/MPS-2023-5130)|CVE-2023-26136|严重|
|request SSRF防御绕过漏洞|SSRF|[MPS-2023-7722](https://www.oscs1024.com/hd/MPS-2023-7722)|CVE-2023-28155|中危|
|tough-cookie<4.1.3 存在原型污染漏洞|原型污染|[MPS-esyq-56vx](https://www.oscs1024.com/hd/MPS-esyq-56vx)||中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|word-wrap|1.2.3|1.2.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|mocha|7.2.0||直接依赖|建议修复|C:0|H:1|M:0|L:0|
|http-signature|1.2.0||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tough-cookie|2.5.0|4.1.3|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|lodash.set|4.3.2||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tar|2.2.2|6.1.9|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|minimist|1.2.5|1.2.6|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|json5|2.2.0|2.2.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|semver|7.3.5|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|flat|4.1.1|5.0.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|request|2.88.2||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|273|Low|
|ISC|60|Low|
|Apache-2.0|16|Low|
|BSD-3-Clause|20|Low|
|BSD-2-Clause|8|Low|
|CC-BY-4.0|1|Low|
|0BSD|1|Low|
|Public Domain|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|base64-js|1.5.1|间接依赖|npm|
|number-is-nan|1.0.1|直接依赖|npm|
|strip-json-comments|2.0.1|间接依赖|npm|
|decamelize|1.2.0|间接依赖|npm|
|os-tmpdir|1.0.2|直接依赖|npm|
|write|1.0.3|间接依赖|npm|
|convert-source-map|1.8.0|间接依赖|npm|
|@istanbuljs/load-nyc-config|1.1.0|间接依赖|npm|
|@definitelytyped/typescript-versions|0.0.111|间接依赖|npm|
|shebang-regex|1.0.0|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|is-callable|1.2.4|间接依赖|npm|
|@definitelytyped/header-parser|0.0.111|间接依赖|npm|
|write-file-atomic|3.0.3|间接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|caching-transform|4.0.0|间接依赖|npm|
|lodash.flattendeep|4.4.0|间接依赖|npm|
|object-keys|1.1.1|间接依赖|npm|
|node-environment-flags|1.0.6|间接依赖|npm|
|find-cache-dir|3.3.2|间接依赖|npm|
|which-boxed-primitive|1.0.2|间接依赖|npm|
|istanbul-lib-processinfo|2.0.2|间接依赖|npm|
|tar|2.2.2|间接依赖|npm|
|cross-spawn|6.0.5|间接依赖|npm|
|which|1.3.1|间接依赖|npm|
|command-exists|1.2.9|间接依赖|npm|
|optionator|0.8.3|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|is-negative-zero|2.0.2|间接依赖|npm|
|has-symbols|1.0.3|间接依赖|npm|
|progress|2.0.3|间接依赖|npm|
|is-regex|1.1.4|间接依赖|npm|
|request|2.88.2|间接依赖|npm|
|path-exists|3.0.0|间接依赖|npm|
|esquery|1.4.0|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|run-async|2.4.1|间接依赖|npm|
|spawn-wrap|2.0.0|间接依赖|npm|
|path-key|2.0.1|间接依赖|npm|
|aproba|1.2.0|间接依赖|npm|
|combined-stream|1.0.8|间接依赖|npm|
|require-main-filename|2.0.0|间接依赖|npm|
|concat-stream|2.0.0|间接依赖|npm|
|ignore|4.0.6|间接依赖|npm|
|nise|4.1.0|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|are-we-there-yet|1.1.7|间接依赖|npm|
|@babel/template|7.16.7|间接依赖|npm|
|append-transform|2.0.0|间接依赖|npm|
|es6-error|4.1.1|间接依赖|npm|
|jsprim|1.4.2|间接依赖|npm|
|string.prototype.trimstart|1.0.4|间接依赖|npm|
|is-shared-array-buffer|1.0.1|间接依赖|npm|
|table|5.4.6|间接依赖|npm|
|@sinonjs/samsam|5.3.1|间接依赖|npm|
|safe-buffer|5.2.1|间接依赖|npm|
|caseless|0.12.0|间接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|@babel/helper-environment-visitor|7.16.7|间接依赖|npm|
|universalify|0.1.2|间接依赖|npm|
|@babel/compat-data|7.17.0|间接依赖|npm|
|istanbul-reports|3.1.4|间接依赖|npm|
|@babel/parser|7.17.3|间接依赖|npm|
|babel-code-frame|6.26.0|间接依赖|npm|
|json5|2.2.0|间接依赖|npm|
|http-signature|1.2.0|间接依赖|npm|
|@babel/helper-compilation-targets|7.16.7|间接依赖|npm|
|tslint|5.14.0|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|set-blocking|2.0.0|间接依赖|npm|
|@definitelytyped/utils|0.0.111|间接依赖|npm|
|color-name|1.1.3|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|fsevents|2.1.3|间接依赖|npm|
|call-bind|1.0.2|间接依赖|npm|
|muk-require|1.2.0|直接依赖|npm|
|external-editor|3.1.0|间接依赖|npm|
|esprima|4.0.1|间接依赖|npm|
|nice-try|1.0.5|间接依赖|npm|
|fast-levenshtein|2.0.6|间接依赖|npm|
|sinon|9.2.4|直接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|psl|1.8.0|间接依赖|npm|
|tsutils|2.29.0|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|heap|0.2.7|间接依赖|npm|
|anymatch|3.1.2|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|foreground-child|2.0.0|间接依赖|npm|
|glob|7.1.3|间接依赖|npm|
|npm-package-arg|8.1.5|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|rxjs|6.6.7|间接依赖|npm|
|release-zalgo|1.0.0|间接依赖|npm|
|@babel/helper-module-imports|7.16.7|间接依赖|npm|
|supports-preserve-symlinks-flag|1.0.0|间接依赖|npm|
|which-module|2.0.0|间接依赖|npm|
|p-map|3.0.0|间接依赖|npm|
|@babel/helper-function-name|7.16.7|间接依赖|npm|
|flat|4.1.1|间接依赖|npm|
|nock|13.2.4|直接依赖|npm|
|@babel/core|7.17.5|间接依赖|npm|
|rimraf|3.0.2|间接依赖|npm|
|@types/parsimmon|1.10.6|间接依赖|npm|
|inquirer|7.3.3|间接依赖|npm|
|is-symbol|1.0.4|间接依赖|npm|
|wordwrap|1.0.0|间接依赖|npm|
|fs-constants|1.0.0|间接依赖|npm|
|deep-is|0.1.4|间接依赖|npm|
|aws4|1.11.0|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|spdx-expression-parse|3.0.1|间接依赖|npm|
|caniuse-lite|1.0.30001313|间接依赖|npm|
|aggregate-error|3.1.0|间接依赖|npm|
|ajv|6.12.6|间接依赖|npm|
|typedarray|0.0.6|间接依赖|npm|
|es-to-primitive|1.2.1|间接依赖|npm|
|y18n|4.0.3|间接依赖|npm|
|estraverse|4.3.0|间接依赖|npm|
|isstream|0.1.2|间接依赖|npm|
|ssri|8.0.1|间接依赖|npm|
|yargs|15.4.1|间接依赖|npm|
|assert-plus|1.0.0|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|builtin-modules|1.1.1|间接依赖|npm|
|miniget|4.2.3|间接依赖|npm|
|tslib|1.14.1|间接依赖|npm|
|fs-extra|6.0.1|间接依赖|npm|
|mkdirp|0.5.5|间接依赖|npm|
|strip-bom|4.0.0|间接依赖|npm|
|tunnel-agent|0.6.0|间接依赖|npm|
|iconv-lite|0.4.24|间接依赖|npm|
|is-windows|1.0.2|间接依赖|npm|
|side-channel|1.0.4|间接依赖|npm|
|indent-string|4.0.0|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|log-symbols|3.0.0|间接依赖|npm|
|graceful-fs|4.2.9|间接依赖|npm|
|p-try|2.2.0|间接依赖|npm|
|is-glob|4.0.3|间接依赖|npm|
|resolve-from|4.0.0|间接依赖|npm|
|debug|4.3.3|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|gauge|2.7.4|间接依赖|npm|
|@jridgewell/trace-mapping|0.3.4|间接依赖|npm|
|through|2.3.8|间接依赖|npm|
|charm|1.0.2|间接依赖|npm|
|fromentries|1.3.2|间接依赖|npm|
|v8-compile-cache|2.3.0|间接依赖|npm|
|hosted-git-info|4.1.0|间接依赖|npm|
|mime-db|1.51.0|间接依赖|npm|
|globals|12.4.0|间接依赖|npm|
|istanbul-lib-source-maps|4.0.1|间接依赖|npm|
|normalize-package-data|3.0.3|间接依赖|npm|
|package-hash|4.0.0|间接依赖|npm|
|callsites|3.1.0|间接依赖|npm|
|istanbul-lib-instrument|4.0.3|间接依赖|npm|
|istanbul-lib-report|3.0.0|间接依赖|npm|
|parent-module|1.0.1|间接依赖|npm|
|growl|1.10.5|间接依赖|npm|
|source-map|0.5.7|间接依赖|npm|
|type-detect|4.0.8|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|mimic-fn|2.1.0|间接依赖|npm|
|ieee754|1.2.1|间接依赖|npm|
|@babel/helper-split-export-declaration|7.16.7|间接依赖|npm|
|esrecurse|4.3.0|间接依赖|npm|
|functional-red-black-tree|1.0.1|间接依赖|npm|
|es5-ext|0.8.2|间接依赖|npm|
|type-fest|0.8.1|间接依赖|npm|
|to-fast-properties|2.0.0|间接依赖|npm|
|glob-parent|5.1.2|间接依赖|npm|
|tough-cookie|2.5.0|间接依赖|npm|
|make-dir|3.1.0|间接依赖|npm|
|@babel/helpers|7.17.2|间接依赖|npm|
|clean-stack|2.2.0|间接依赖|npm|
|isarray|0.0.1|间接依赖|npm|
|imurmurhash|0.1.4|间接依赖|npm|
|eslint-visitor-keys|1.3.0|间接依赖|npm|
|yargs-unparser|1.6.0|间接依赖|npm|
|jsesc|2.5.2|间接依赖|npm|
|@babel/generator|7.17.3|间接依赖|npm|
|minimist|1.2.5|间接依赖|npm|
|@babel/helper-hoist-variables|7.16.7|间接依赖|npm|
|restore-cursor|3.1.0|间接依赖|npm|
|locate-path|3.0.0|间接依赖|npm|
|import-fresh|3.3.0|间接依赖|npm|
|dreamopt|0.6.0|间接依赖|npm|
|performance-now|2.1.0|间接依赖|npm|
|string.prototype.trimend|1.0.4|间接依赖|npm|
|typescript|3.9.10|直接依赖|npm|
|acorn|7.4.1|间接依赖|npm|
|@sinonjs/text-encoding|0.7.1|间接依赖|npm|
|flatted|2.0.2|间接依赖|npm|
|@types/node|13.13.52|间接依赖|npm|
|internal-slot|1.0.3|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|delegates|1.0.0|间接依赖|npm|
|extend|3.0.2|间接依赖|npm|
|is-string|1.0.7|间接依赖|npm|
|@sinonjs/commons|1.8.3|间接依赖|npm|
|lodash.set|4.3.2|间接依赖|npm|
|ansi-escapes|4.3.2|间接依赖|npm|
|object.getownpropertydescriptors|2.1.3|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|browserslist|4.19.3|间接依赖|npm|
|cli-cursor|3.1.0|间接依赖|npm|
|commondir|1.0.1|间接依赖|npm|
|json-stable-stringify-without-jsonify|1.0.1|间接依赖|npm|
|@babel/highlight|7.16.10|间接依赖|npm|
|commander|2.20.3|间接依赖|npm|
|js-yaml|3.14.1|间接依赖|npm|
|parsimmon|1.18.1|间接依赖|npm|
|espree|6.2.1|间接依赖|npm|
|assert-diff|3.0.2|直接依赖|npm|
|natural-compare|1.4.0|间接依赖|npm|
|readable-stream|3.6.0|间接依赖|npm|
|aws-sign2|0.7.0|间接依赖|npm|
|istanbul-lib-hook|3.0.0|间接依赖|npm|
|is-weakref|1.0.2|间接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|ansi-colors|3.2.3|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|@qiwi/npm-registry-client|8.9.1|间接依赖|npm|
|hasha|5.2.2|间接依赖|npm|
|sprintf-js|1.0.3|间接依赖|npm|
|mocha|7.2.0|直接依赖|npm|
|process-on-spawn|1.0.0|间接依赖|npm|
|har-validator|5.1.5|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|camelcase|5.3.1|间接依赖|npm|
|path-to-regexp|1.8.0|间接依赖|npm|
|flat-cache|2.0.1|间接依赖|npm|
|code-point-at|1.1.0|直接依赖|npm|
|node-releases|2.0.2|间接依赖|npm|
|wide-align|1.1.3|间接依赖|npm|
|propagate|2.0.1|间接依赖|npm|
|cli-width|3.0.0|间接依赖|npm|
|p-locate|3.0.0|间接依赖|npm|
|get-symbol-description|1.0.0|间接依赖|npm|
|sshpk|1.17.0|间接依赖|npm|
|minipass|3.1.6|间接依赖|npm|
|builtins|1.0.3|间接依赖|npm|
|@babel/helper-simple-access|7.16.7|间接依赖|npm|
|process-nextick-args|2.0.1|直接依赖|npm|
|dtslint|3.7.0|直接依赖|npm|
|tmp|0.2.1|间接依赖|npm|
|@istanbuljs/schema|0.1.3|间接依赖|npm|
|gensync|1.0.0-beta.2|间接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|acorn-jsx|5.3.2|间接依赖|npm|
|is-binary-path|2.1.0|间接依赖|npm|
|validate-npm-package-license|3.0.4|间接依赖|npm|
|find-up|3.0.0|间接依赖|npm|
|astral-regex|1.0.0|间接依赖|npm|
|@jridgewell/resolve-uri|3.0.5|间接依赖|npm|
|@babel/types|7.17.0|间接依赖|npm|
|@babel/traverse|7.17.3|间接依赖|npm|
|istanbul-lib-coverage|3.2.0|间接依赖|npm|
|node-preload|0.2.1|间接依赖|npm|
|end-of-stream|1.4.4|间接依赖|npm|
|chokidar|3.3.0|间接依赖|npm|
|levn|0.3.0|间接依赖|npm|
|figures|3.2.0|间接依赖|npm|
|spdx-correct|3.1.1|间接依赖|npm|
|text-table|0.2.0|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|eslint|6.8.0|直接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|he|1.2.0|间接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.11|间接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|html-escaper|2.0.2|间接依赖|npm|
|asynckit|0.4.0|间接依赖|npm|
|is-number|7.0.0|间接依赖|npm|
|object.assign|4.1.0|间接依赖|npm|
|doctrine|3.0.0|间接依赖|npm|
|m3u8stream|0.8.6|直接依赖|npm|
|p-limit|2.3.0|间接依赖|npm|
|@babel/helper-get-function-arity|7.16.7|间接依赖|npm|
|readdirp|3.2.0|间接依赖|npm|
|prelude-ls|1.1.2|间接依赖|npm|
|eslint-utils|1.4.3|间接依赖|npm|
|shebang-command|1.2.0|间接依赖|npm|
|yallist|4.0.0|间接依赖|npm|
|fstream|1.0.12|间接依赖|npm|
|har-schema|2.0.0|间接依赖|npm|
|cli-color|0.1.7|间接依赖|npm|
|nyc|15.1.0|直接依赖|npm|
|browser-stdout|1.3.1|间接依赖|npm|
|is-date-object|1.0.5|间接依赖|npm|
|form-data|2.3.3|间接依赖|npm|
|argparse|1.0.10|间接依赖|npm|
|default-require-extensions|3.0.0|间接依赖|npm|
|get-package-type|0.1.0|间接依赖|npm|
|lru-cache|6.0.0|间接依赖|npm|
|get-intrinsic|1.1.1|间接依赖|npm|
|diff|3.5.0|间接依赖|npm|
|is-core-module|2.8.1|间接依赖|npm|
|archy|1.0.0|间接依赖|npm|
|tar-stream|2.2.0|间接依赖|npm|
|mute-stream|0.0.8|间接依赖|npm|
|pkg-dir|4.2.0|间接依赖|npm|
|has-bigints|1.0.1|间接依赖|npm|
|chardet|0.7.0|间接依赖|npm|
|onetime|5.1.2|间接依赖|npm|
|dts-critic|3.3.11|间接依赖|npm|
|electron-to-chromium|1.4.75|间接依赖|npm|
|json-stringify-safe|5.0.1|间接依赖|npm|
|has-ansi|2.0.0|直接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|slide|1.1.6|间接依赖|npm|
|yargs-parser|13.1.2|间接依赖|npm|
|has-unicode|2.0.1|间接依赖|npm|
|typedarray-to-buffer|3.1.5|间接依赖|npm|
|semver|7.3.5|间接依赖|npm|
|signal-exit|3.0.7|间接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|regexpp|2.0.1|间接依赖|npm|
|qs|6.5.3|间接依赖|npm|
|wrap-ansi|6.2.0|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|bl|4.1.0|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|just-extend|4.2.1|间接依赖|npm|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|resolve|1.22.0|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|json-diff|0.5.4|间接依赖|npm|
|jsonify|0.0.0|间接依赖|npm|
|lodash.get|4.4.2|间接依赖|npm|
|console-control-strings|1.1.0|间接依赖|npm|
|jsonfile|4.0.0|间接依赖|npm|
|json-stable-stringify|1.0.1|间接依赖|npm|
|word-wrap|1.2.3|间接依赖|npm|
|es-abstract|1.19.1|间接依赖|npm|
|unbox-primitive|1.0.1|间接依赖|npm|
|is-typedarray|1.0.0|间接依赖|npm|
|define-properties|1.1.3|间接依赖|npm|
|is-stream|2.0.1|间接依赖|npm|
|type-check|0.3.2|间接依赖|npm|
|retry|0.12.0|间接依赖|npm|
|esutils|2.0.3|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|is-buffer|2.0.5|间接依赖|npm|
|@babel/helper-module-transforms|7.17.6|间接依赖|npm|
|buffer-from|1.1.2|间接依赖|npm|
|binary-extensions|2.2.0|间接依赖|npm|
|punycode|2.1.1|间接依赖|npm|
|@babel/helper-validator-identifier|7.16.7|间接依赖|npm|
|slice-ansi|2.1.0|间接依赖|npm|
|eslint-scope|5.1.1|间接依赖|npm|
|npmlog|4.1.2|间接依赖|npm|
|difflib|0.2.4|间接依赖|npm|
|picomatch|2.3.1|间接依赖|npm|
|delayed-stream|1.0.0|间接依赖|npm|
|object-inspect|1.12.0|间接依赖|npm|
|block-stream|0.0.9|间接依赖|npm|
|file-entry-cache|5.0.1|间接依赖|npm|
|sax|1.2.4|间接依赖|npm|
|cliui|6.0.0|间接依赖|npm|
|emoji-regex|8.0.0|间接依赖|npm|
|buffer|5.7.1|间接依赖|npm|
|mime-types|2.1.34|间接依赖|npm|
|has-tostringtag|1.0.0|间接依赖|npm|
|ansi-regex|4.1.0|间接依赖|npm|
|uuid|3.4.0|间接依赖|npm|
|strip-ansi|5.2.0|间接依赖|npm|
|@sinonjs/fake-timers|6.0.1|间接依赖|npm|
|string-width|4.2.3|间接依赖|npm|
|string_decoder|1.3.0|间接依赖|npm|
|forever-agent|0.6.1|间接依赖|npm|
|oauth-sign|0.9.0|间接依赖|npm|
|@babel/helper-validator-option|7.16.7|间接依赖|npm|
|test-exclude|6.0.0|间接依赖|npm|
|validate-npm-package-name|3.0.0|间接依赖|npm|
|@babel/code-frame|7.16.7|间接依赖|npm|
|stream-equal|1.1.1|直接依赖|npm|
|picocolors|1.0.0|间接依赖|npm|
|@ampproject/remapping|2.1.2|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)