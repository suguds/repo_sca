# is-a-dev/register安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696593009088225280.svg)](https://www.murphysec.com/console/report/1696593009046282240/1696593009088225280)

仓库描述：Grab your own sweet-looking '.is-a.dev' subdomain

仓库地址：[https://github.com/is-a-dev/register](https://github.com/is-a-dev/register)

| star：2246 | watch：14 | fork：4412 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-30 02:10:25 | 许可证：GPL-3.0 |
| 最近检测时间：2023-08-30 02:38:20 | 组件总数：379 | 漏洞总数：23 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Yargs Y18n 输入原型污染漏洞|动态确定对象属性修改的控制不恰当|[MPS-2020-17543](https://www.oscs1024.com/hd/MPS-2020-17543)|CVE-2020-7774|严重|
|Mikaelbr Node-notifier 操作系统命令注入漏洞|OS命令注入|[MPS-2020-17637](https://www.oscs1024.com/hd/MPS-2020-17637)|CVE-2020-7789|中危|
|lodash 拒绝服务漏洞|拒绝服务|[MPS-2021-2574](https://www.oscs1024.com/hd/MPS-2021-2574)|CVE-2020-28500|中危|
|lodash 命令注入漏洞|代码注入|[MPS-2021-2638](https://www.oscs1024.com/hd/MPS-2021-2638)|CVE-2021-23337|高危|
|nodejs 正则表达式漏洞|拒绝服务|[MPS-2021-31423](https://www.oscs1024.com/hd/MPS-2021-31423)|CVE-2021-3777|高危|
|prompts 正则表达式拒绝服务漏洞|ReDoS|[MPS-2021-32909](https://www.oscs1024.com/hd/MPS-2021-32909)||中危|
|minimist 安全漏洞|原型污染|[MPS-2021-38405](https://www.oscs1024.com/hd/MPS-2021-38405)|CVE-2021-44906|严重|
|npm path-parse 安全漏洞|拒绝服务|[MPS-2021-6165](https://www.oscs1024.com/hd/MPS-2021-6165)|CVE-2021-23343|高危|
|ws 存在拒绝服务漏洞||[MPS-2021-7109](https://www.oscs1024.com/hd/MPS-2021-7109)|CVE-2021-32640|中危|
|glob-parent < 5.1.2 存在拒绝服务漏洞|拒绝服务|[MPS-2021-7827](https://www.oscs1024.com/hd/MPS-2021-7827)|CVE-2020-28469|高危|
|istanbul-reports<3.1.3 反向 Tabnabbing漏洞|通过 window.opener 访问使用指向不受信任目标的 Web 链接|[MPS-2022-13797](https://www.oscs1024.com/hd/MPS-2022-13797)||中危|
|ramda <0.27.2 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13991](https://www.oscs1024.com/hd/MPS-2022-13991)||中危|
|node-fetch 信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-1461](https://www.oscs1024.com/hd/MPS-2022-1461)|CVE-2022-0235|中危|
|Express 中的 qs 模块存在原型污染漏洞|原型污染|[MPS-2022-3967](https://www.oscs1024.com/hd/MPS-2022-3967)|CVE-2022-24999|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|nwsapi 拒绝服务|拒绝服务|[MPS-2022-54623](https://www.oscs1024.com/hd/MPS-2022-54623)||中危|
|minimatch 资源管理错误漏洞|拒绝服务|[MPS-2022-59845](https://www.oscs1024.com/hd/MPS-2022-59845)|CVE-2022-3517|高危|
|Tauri 原型污染漏洞|原型污染|[MPS-2022-65568](https://www.oscs1024.com/hd/MPS-2022-65568)|CVE-2022-46175|高危|
|cross-fetch 安全漏洞|授权检查错误|[MPS-2022-8877](https://www.oscs1024.com/hd/MPS-2022-8877)|CVE-2022-1365|中危|
|word-wrap 安全漏洞|ReDoS|[MPS-2023-5109](https://www.oscs1024.com/hd/MPS-2023-5109)|CVE-2023-26115|高危|
|tough-cookie 安全漏洞|原型污染|[MPS-2023-5130](https://www.oscs1024.com/hd/MPS-2023-5130)|CVE-2023-26136|严重|
|request SSRF防御绕过漏洞|SSRF|[MPS-2023-7722](https://www.oscs1024.com/hd/MPS-2023-7722)|CVE-2023-28155|中危|
|tough-cookie<4.1.3 存在原型污染漏洞|原型污染|[MPS-esyq-56vx](https://www.oscs1024.com/hd/MPS-esyq-56vx)||中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|word-wrap|1.2.3|1.2.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tmpl|1.0.4|1.0.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|qs|6.9.4|6.10.3|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|y18n|4.0.0|5.0.5|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|glob-parent|5.1.1|6.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|path-parse|1.0.6|1.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|minimist|1.2.5|1.2.6|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|json5|2.1.3|2.2.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|minimatch|3.0.4|3.0.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tough-cookie|3.0.1|4.1.3|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|semver|6.3.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|ws|7.4.0|7.4.6|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|prompts|2.4.0|2.4.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|request|2.88.2||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|5.7.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|semver|7.3.2|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|node-fetch|2.6.1|3.2.10|直接依赖|可选修复|C:0|H:0|M:2|L:0|
|nwsapi|2.2.0|2.2.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|node-notifier|8.0.0|9.0.1|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|ramda|0.27.1|0.27.2|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|lodash|4.17.20|4.17.21|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|istanbul-reports|3.0.2|3.1.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|298|Low|
|BSD-2-Clause|12|Low|
|ISC|34|Low|
|Apache-2.0|10|Low|
|BSD-3-Clause|19|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|braces|2.3.2|间接依赖|npm|
|uri-js|4.4.0|间接依赖|npm|
|emittery|0.7.2|间接依赖|npm|
|resolve|1.19.0|间接依赖|npm|
|write-file-atomic|3.0.3|间接依赖|npm|
|ramda|0.27.1|直接依赖|npm|
|babel-preset-jest|26.6.2|间接依赖|npm|
|eslint-plugin-es|3.0.1|间接依赖|npm|
|write|1.0.3|间接依赖|npm|
|deep-is|0.1.3|间接依赖|npm|
|@babel/helper-function-name|7.10.4|间接依赖|npm|
|read-pkg-up|7.0.1|间接依赖|npm|
|@babel/highlight|7.10.4|间接依赖|npm|
|punycode|2.1.1|间接依赖|npm|
|strip-ansi|5.2.0|间接依赖|npm|
|yargs-parser|18.1.3|间接依赖|npm|
|mimic-fn|2.1.0|间接依赖|npm|
|exit|0.1.2|间接依赖|npm|
|supports-hyperlinks|2.1.0|间接依赖|npm|
|slice-ansi|2.1.0|间接依赖|npm|
|word-wrap|1.2.3|间接依赖|npm|
|convert-source-map|1.7.0|间接依赖|npm|
|extglob|2.0.4|间接依赖|npm|
|path-exists|4.0.0|间接依赖|npm|
|eslint-visitor-keys|1.3.0|间接依赖|npm|
|request-promise-native|1.0.9|间接依赖|npm|
|lodash|4.17.20|间接依赖|npm|
|@types/stack-utils|2.0.0|间接依赖|npm|
|parse-json|5.1.0|间接依赖|npm|
|@types/istanbul-lib-report|3.0.0|间接依赖|npm|
|esutils|2.0.3|间接依赖|npm|
|ignore|4.0.6|间接依赖|npm|
|glob-parent|5.1.1|间接依赖|npm|
|color-name|1.1.4|间接依赖|npm|
|fb-watchman|2.0.1|间接依赖|npm|
|@babel/helpers|7.12.5|间接依赖|npm|
|bser|2.1.1|间接依赖|npm|
|extend-shallow|3.0.2|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|cliui|6.0.0|间接依赖|npm|
|resolve-from|4.0.0|间接依赖|npm|
|is-generator-fn|2.1.0|间接依赖|npm|
|@jest/test-sequencer|26.6.3|间接依赖|npm|
|webidl-conversions|6.1.0|间接依赖|npm|
|imurmurhash|0.1.4|间接依赖|npm|
|pretty-format|26.6.2|间接依赖|npm|
|type-check|0.4.0|间接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|execa|1.0.0|间接依赖|npm|
|jest-config|26.6.3|间接依赖|npm|
|@jest/console|26.6.2|间接依赖|npm|
|whatwg-url|8.4.0|间接依赖|npm|
|exec-sh|0.3.4|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|table|5.4.6|间接依赖|npm|
|doctrine|3.0.0|间接依赖|npm|
|v8-compile-cache|2.2.0|间接依赖|npm|
|cjs-module-lexer|0.6.0|间接依赖|npm|
|camelcase|6.2.0|间接依赖|npm|
|@sinonjs/fake-timers|6.0.1|间接依赖|npm|
|babel-preset-current-node-syntax|1.0.0|间接依赖|npm|
|@babel/helper-module-transforms|7.12.1|间接依赖|npm|
|fast-levenshtein|2.0.6|间接依赖|npm|
|whatwg-mimetype|2.3.0|间接依赖|npm|
|jsonc-parser|2.3.1|间接依赖|npm|
|@jest/source-map|26.6.2|间接依赖|npm|
|collect-v8-coverage|1.0.1|间接依赖|npm|
|natural-compare|1.4.0|间接依赖|npm|
|cssstyle|2.3.0|间接依赖|npm|
|ansi-styles|4.3.0|间接依赖|npm|
|which|2.0.2|间接依赖|npm|
|jest|26.6.3|直接依赖|npm|
|arr-diff|4.0.0|间接依赖|npm|
|@babel/helper-module-imports|7.12.5|间接依赖|npm|
|@jest/core|26.6.3|间接依赖|npm|
|@jest/fake-timers|26.6.2|间接依赖|npm|
|ws|7.4.0|间接依赖|npm|
|pump|3.0.0|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|pirates|4.0.1|间接依赖|npm|
|source-map|0.5.7|间接依赖|npm|
|chalk|4.1.0|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|p-finally|1.0.0|间接依赖|npm|
|astral-regex|1.0.0|间接依赖|npm|
|flatted|2.0.2|间接依赖|npm|
|tmpl|1.0.4|间接依赖|npm|
|argparse|1.0.10|间接依赖|npm|
|espree|7.3.0|间接依赖|npm|
|jest-changed-files|26.6.2|间接依赖|npm|
|is-potential-custom-element-name|1.0.0|间接依赖|npm|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|globals|11.12.0|间接依赖|npm|
|parent-module|1.0.1|间接依赖|npm|
|find-up|4.1.0|间接依赖|npm|
|tough-cookie|3.0.1|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|@babel/template|7.10.4|间接依赖|npm|
|acorn-globals|6.0.0|间接依赖|npm|
|uuid|8.3.1|间接依赖|npm|
|node-notifier|8.0.0|直接依赖|npm|
|node-int64|0.4.0|间接依赖|npm|
|@babel/helper-plugin-utils|7.10.4|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|@babel/helper-split-export-declaration|7.11.0|间接依赖|npm|
|@sinonjs/commons|1.8.1|间接依赖|npm|
|normalize-path|2.1.1|间接依赖|npm|
|emoji-regex|7.0.3|间接依赖|npm|
|import-local|3.0.2|间接依赖|npm|
|is-typedarray|1.0.0|间接依赖|npm|
|istanbul-lib-source-maps|4.0.0|间接依赖|npm|
|jest-regex-util|26.0.0|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|micromatch|4.0.2|间接依赖|npm|
|jest-message-util|26.6.2|间接依赖|npm|
|resolve-from|5.0.0|间接依赖|npm|
|istanbul-lib-coverage|3.0.0|间接依赖|npm|
|regexpp|3.1.0|间接依赖|npm|
|@istanbuljs/load-nyc-config|1.1.0|间接依赖|npm|
|terminal-link|2.1.1|间接依赖|npm|
|qs|6.9.4|直接依赖|npm|
|is-stream|2.0.0|间接依赖|npm|
|@jest/transform|26.6.2|间接依赖|npm|
|prompts|2.4.0|间接依赖|npm|
|jest-resolve-dependencies|26.6.3|间接依赖|npm|
|ansi-regex|5.0.0|间接依赖|npm|
|eslint|7.13.0|直接依赖|npm|
|import-fresh|3.2.2|间接依赖|npm|
|istanbul-lib-instrument|4.0.3|间接依赖|npm|
|saxes|5.0.1|间接依赖|npm|
|ajv|6.12.6|间接依赖|npm|
|read-pkg|5.2.0|间接依赖|npm|
|normalize-package-data|2.5.0|间接依赖|npm|
|@babel/types|7.12.6|间接依赖|npm|
|semver|7.3.2|间接依赖|npm|
|sprintf-js|1.0.3|间接依赖|npm|
|balanced-match|1.0.0|间接依赖|npm|
|shebang-regex|3.0.0|间接依赖|npm|
|string-width|3.1.0|间接依赖|npm|
|is-core-module|2.1.0|间接依赖|npm|
|nwsapi|2.2.0|间接依赖|npm|
|type-fest|0.6.0|间接依赖|npm|
|whatwg-encoding|1.0.5|间接依赖|npm|
|eslint-plugin-json|2.1.2|直接依赖|npm|
|jest-worker|26.6.2|间接依赖|npm|
|escodegen|1.14.3|间接依赖|npm|
|prelude-ls|1.2.1|间接依赖|npm|
|v8-to-istanbul|7.0.0|间接依赖|npm|
|detect-newline|3.1.0|间接依赖|npm|
|@types/prettier|2.1.5|间接依赖|npm|
|char-regex|1.0.2|间接依赖|npm|
|data-urls|2.0.0|间接依赖|npm|
|parse5|5.1.1|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|onetime|5.1.2|间接依赖|npm|
|strip-json-comments|3.1.1|间接依赖|npm|
|pkg-dir|4.2.0|间接依赖|npm|
|capture-exit|2.0.0|间接依赖|npm|
|jest-environment-jsdom|26.6.2|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|diff-sequences|26.6.2|间接依赖|npm|
|signal-exit|3.0.3|间接依赖|npm|
|@babel/code-frame|7.10.4|间接依赖|npm|
|istanbul-reports|3.0.2|间接依赖|npm|
|make-dir|3.1.0|间接依赖|npm|
|define-property|2.0.2|间接依赖|npm|
|dotenv|8.2.0|直接依赖|npm|
|rimraf|2.6.3|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|decamelize|1.2.0|间接依赖|npm|
|enquirer|2.3.6|间接依赖|npm|
|yargs|15.4.1|间接依赖|npm|
|@jest/types|26.6.2|间接依赖|npm|
|deepmerge|4.2.2|间接依赖|npm|
|test-exclude|6.0.0|间接依赖|npm|
|@jest/test-result|26.6.2|间接依赖|npm|
|strip-bom|4.0.0|间接依赖|npm|
|@eslint/eslintrc|0.2.1|间接依赖|npm|
|jest-diff|26.6.2|间接依赖|npm|
|throat|5.0.0|间接依赖|npm|
|gensync|1.0.0-beta.2|间接依赖|npm|
|flat-cache|2.0.1|间接依赖|npm|
|json-stable-stringify-without-jsonify|1.0.1|间接依赖|npm|
|camelcase|5.3.1|间接依赖|npm|
|jest-resolve|26.6.2|间接依赖|npm|
|html-escaper|2.0.2|间接依赖|npm|
|stack-utils|2.0.3|间接依赖|npm|
|graceful-fs|4.2.4|间接依赖|npm|
|snapdragon|0.8.2|间接依赖|npm|
|html-encoding-sniffer|2.0.1|间接依赖|npm|
|jest-each|26.6.2|间接依赖|npm|
|@types/babel__generator|7.6.2|间接依赖|npm|
|w3c-hr-time|1.0.2|间接依赖|npm|
|jest-jasmine2|26.6.3|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|escape-string-regexp|2.0.0|间接依赖|npm|
|@babel/parser|7.12.5|间接依赖|npm|
|@babel/helper-validator-identifier|7.10.4|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|progress|2.0.3|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|path-key|3.1.1|间接依赖|npm|
|optionator|0.9.1|间接依赖|npm|
|mkdirp|0.5.5|间接依赖|npm|
|js-yaml|3.14.0|间接依赖|npm|
|text-table|0.2.0|间接依赖|npm|
|cross-spawn|6.0.5|间接依赖|npm|
|sisteransi|1.0.5|间接依赖|npm|
|has-flag|4.0.0|间接依赖|npm|
|strip-eof|1.0.0|间接依赖|npm|
|fragment-cache|0.2.1|间接依赖|npm|
|file-entry-cache|5.0.1|间接依赖|npm|
|sane|4.1.0|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|react-is|17.0.1|间接依赖|npm|
|ansi-colors|4.1.1|间接依赖|npm|
|functional-red-black-tree|1.0.1|间接依赖|npm|
|jest-snapshot|26.6.2|间接依赖|npm|
|jest-runtime|26.6.3|间接依赖|npm|
|is-stream|1.1.0|间接依赖|npm|
|@babel/generator|7.12.5|间接依赖|npm|
|regex-not|1.0.2|间接依赖|npm|
|jest-pnp-resolver|1.2.2|间接依赖|npm|
|array-unique|0.3.2|间接依赖|npm|
|istanbul-lib-report|3.0.0|间接依赖|npm|
|esrecurse|4.3.0|间接依赖|npm|
|get-package-type|0.1.0|间接依赖|npm|
|@types/normalize-package-data|2.4.0|间接依赖|npm|
|babel-plugin-istanbul|6.0.0|间接依赖|npm|
|symbol-tree|3.2.4|间接依赖|npm|
|ignore|5.1.8|间接依赖|npm|
|source-map|0.6.1|直接依赖|npm|
|typedarray-to-buffer|3.1.5|间接依赖|npm|
|strip-ansi|6.0.0|间接依赖|npm|
|esprima|4.0.1|间接依赖|npm|
|cross-spawn|7.0.3|间接依赖|npm|
|@types/babel__traverse|7.0.15|间接依赖|npm|
|jest-runner|26.6.3|间接依赖|npm|
|leven|3.1.0|间接依赖|npm|
|y18n|4.0.0|间接依赖|npm|
|color-name|1.1.3|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|@jest/globals|26.6.2|间接依赖|npm|
|w3c-xmlserializer|2.0.0|间接依赖|npm|
|@bcoe/v8-coverage|0.2.3|间接依赖|npm|
|resolve-cwd|3.0.0|间接依赖|npm|
|jest-haste-map|26.6.2|间接依赖|npm|
|@types/istanbul-lib-coverage|2.0.3|间接依赖|npm|
|eslint-plugin-node|11.1.0|直接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|wrap-ansi|6.2.0|间接依赖|npm|
|npm-run-path|2.0.2|间接依赖|npm|
|string-width|4.2.0|间接依赖|npm|
|xml-name-validator|3.0.0|间接依赖|npm|
|domexception|2.0.1|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|source-map-support|0.5.19|间接依赖|npm|
|ansi-escapes|4.3.1|间接依赖|npm|
|vscode-json-languageservice|3.10.0|间接依赖|npm|
|@istanbuljs/schema|0.1.2|间接依赖|npm|
|p-each-series|2.1.0|间接依赖|npm|
|picomatch|2.2.2|间接依赖|npm|
|globals|12.4.0|间接依赖|npm|
|string-length|4.0.1|间接依赖|npm|
|@types/babel__core|7.1.12|间接依赖|npm|
|jest-serializer|26.6.2|间接依赖|npm|
|decimal.js|10.2.1|间接依赖|npm|
|color-convert|2.0.1|间接依赖|npm|
|expect|26.6.2|间接依赖|npm|
|abab|2.0.5|间接依赖|npm|
|slash|3.0.0|间接依赖|npm|
|shellwords|0.1.1|间接依赖|npm|
|get-stream|4.1.0|间接依赖|npm|
|ci-info|2.0.0|间接依赖|npm|
|jest-environment-node|26.6.2|间接依赖|npm|
|makeerror|1.0.11|间接依赖|npm|
|walker|1.0.7|间接依赖|npm|
|jest-validate|26.6.2|间接依赖|npm|
|jest-matcher-utils|26.6.2|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|object.pick|1.3.0|间接依赖|npm|
|glob|7.1.6|间接依赖|npm|
|vscode-uri|2.1.2|间接依赖|npm|
|kleur|3.0.3|间接依赖|npm|
|to-regex|3.0.2|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|jest-watcher|26.6.2|间接依赖|npm|
|emoji-regex|8.0.0|间接依赖|npm|
|semver|6.3.0|间接依赖|npm|
|kind-of|6.0.3|间接依赖|npm|
|ansi-regex|4.1.0|间接依赖|npm|
|jest-mock|26.6.2|间接依赖|npm|
|@types/node|14.14.7|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|vscode-languageserver-types|3.16.0-next.2|间接依赖|npm|
|@types/babel__template|7.4.0|间接依赖|npm|
|jest-util|26.6.2|间接依赖|npm|
|request|2.88.2|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|acorn|7.4.1|间接依赖|npm|
|to-fast-properties|2.0.0|间接依赖|npm|
|rimraf|3.0.2|间接依赖|npm|
|p-locate|4.1.0|间接依赖|npm|
|micromatch|3.1.10|间接依赖|npm|
|estraverse|4.3.0|间接依赖|npm|
|@types/yargs|15.0.9|间接依赖|npm|
|jsesc|2.5.2|间接依赖|npm|
|vscode-languageserver-textdocument|1.0.1|间接依赖|npm|
|jest-get-type|26.3.0|间接依赖|npm|
|estraverse|5.2.0|间接依赖|npm|
|require-main-filename|2.0.0|间接依赖|npm|
|jest-leak-detector|26.6.2|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|@types/istanbul-reports|3.0.0|间接依赖|npm|
|locate-path|5.0.0|间接依赖|npm|
|@cnakazawa/watch|1.0.4|间接依赖|npm|
|growly|1.3.0|间接依赖|npm|
|strip-final-newline|2.0.0|间接依赖|npm|
|which-module|2.0.0|间接依赖|npm|
|rsvp|4.8.5|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|type-fest|0.8.1|间接依赖|npm|
|jsdom|16.4.0|间接依赖|npm|
|@babel/helper-simple-access|7.12.1|间接依赖|npm|
|callsites|3.1.0|间接依赖|npm|
|human-signals|1.1.1|间接依赖|npm|
|node-fetch|2.6.1|直接依赖|npm|
|path-parse|1.0.6|间接依赖|npm|
|set-blocking|2.0.0|间接依赖|npm|
|json5|2.1.3|间接依赖|npm|
|@babel/helper-replace-supers|7.12.5|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|buffer-from|1.1.1|间接依赖|npm|
|co|4.6.0|间接依赖|npm|
|source-map|0.7.3|间接依赖|npm|
|node-modules-regexp|1.0.0|间接依赖|npm|
|jest-docblock|26.0.0|间接依赖|npm|
|semver|5.7.1|间接依赖|npm|
|is-glob|4.0.1|间接依赖|npm|
|merge-stream|2.0.0|间接依赖|npm|
|cssom|0.4.4|间接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|@types/graceful-fs|4.1.4|间接依赖|npm|
|nanomatch|1.2.13|间接依赖|npm|
|@jest/reporters|26.6.2|间接依赖|npm|
|is-ci|2.0.0|间接依赖|npm|
|debug|4.2.0|间接依赖|npm|
|eslint-utils|2.1.0|间接依赖|npm|
|vscode-nls|5.0.0|间接依赖|npm|
|babel-jest|26.6.3|间接依赖|npm|
|shebang-command|2.0.0|间接依赖|npm|
|eslint-scope|5.1.1|间接依赖|npm|
|babel-plugin-jest-hoist|26.6.2|间接依赖|npm|
|get-stream|5.2.0|间接依赖|npm|
|jest-cli|26.6.3|间接依赖|npm|
|esquery|1.3.1|间接依赖|npm|
|minimist|1.2.5|间接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|is-docker|2.1.1|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|is-wsl|2.2.0|间接依赖|npm|
|levn|0.4.1|间接依赖|npm|
|@babel/traverse|7.12.5|间接依赖|npm|
|@jest/environment|26.6.2|间接依赖|npm|
|execa|4.1.0|间接依赖|npm|
|eslint-visitor-keys|2.0.0|间接依赖|npm|
|@types/yargs-parser|15.0.0|间接依赖|npm|
|acorn-jsx|5.3.1|间接依赖|npm|
|anymatch|3.1.1|间接依赖|npm|
|@babel/core|7.12.3|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|anymatch|2.0.0|间接依赖|npm|
|npm-run-path|4.0.1|间接依赖|npm|
|supports-color|7.2.0|间接依赖|npm|
|fsevents|2.2.1|直接依赖|npm|
|type-fest|0.11.0|间接依赖|npm|
|is-fullwidth-code-point|2.0.0|间接依赖|npm|
|minimatch|3.0.4|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)