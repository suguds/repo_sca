# adrianhajdin/project_next_13_ai_prompt_sharing安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1701667090875596800.svg)](https://www.murphysec.com/console/report/1701667090326142976/1701667090875596800)

仓库描述：Next.js recently became the official React framework as outlined in React docs. In this course, you'll learn the most important Next.js concepts and how they fit into the React ecosystem. Finally, you'll put your skills to the test by building a modern full-stack Next 13 application.

仓库地址：[https://github.com/adrianhajdin/project_next_13_ai_prompt_sharing](https://github.com/adrianhajdin/project_next_13_ai_prompt_sharing)

| star：1695 | watch：8 | fork：252 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-01 16:32:35 | 许可证：- |
| 最近检测时间：2023-09-13 02:52:04 | 组件总数：186 | 漏洞总数：3 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|MongoDB 安全漏洞|日志敏感信息泄露|[MPS-2021-24103](https://www.oscs1024.com/hd/MPS-2021-24103)|CVE-2021-32050|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|Automattic Mongoose 安全漏洞|原型污染|[MPS-rkw8-631m](https://www.oscs1024.com/hd/MPS-rkw8-631m)|CVE-2023-3696|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|mongoose|7.1.0|7.3.4|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|mongodb|5.3.0|5.8.0|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|semver|7.5.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|ISC|33|Low|
|MIT|132|Low|
|BSD-2-Clause|1|Low|
|BSD-3-Clause|2|Low|
|Apache-2.0|7|Low|
|CC-BY-4.0|1|Low|
|0BSD|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|color-support|1.1.3|间接依赖|npm|
|delegates|1.0.0|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|@jridgewell/set-array|1.1.2|间接依赖|npm|
|resolve|1.22.2|间接依赖|npm|
|@types/webidl-conversions|7.0.0|间接依赖|npm|
|mongoose|7.1.0|直接依赖|npm|
|anymatch|3.1.3|间接依赖|npm|
|@next/swc-linux-x64-musl|13.3.4|间接依赖|npm|
|pify|2.3.0|间接依赖|npm|
|npmlog|5.0.1|间接依赖|npm|
|pretty-format|3.8.0|间接依赖|npm|
|@next/swc-darwin-arm64|13.3.4|间接依赖|npm|
|@types/node|18.16.3|间接依赖|npm|
|glob-parent|6.0.2|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|postcss-value-parser|4.2.0|间接依赖|npm|
|sucrase|3.32.0|间接依赖|npm|
|sift|16.0.1|间接依赖|npm|
|thenify-all|1.6.0|间接依赖|npm|
|preact|10.13.2|间接依赖|npm|
|micromatch|4.0.5|间接依赖|npm|
|set-blocking|2.0.0|间接依赖|npm|
|webidl-conversions|7.0.0|间接依赖|npm|
|lru-cache|6.0.0|间接依赖|npm|
|@swc/helpers|0.5.1|间接依赖|npm|
|jiti|1.18.2|间接依赖|npm|
|console-control-strings|1.1.0|间接依赖|npm|
|streamsearch|1.1.0|间接依赖|npm|
|@types/whatwg-url|8.2.2|间接依赖|npm|
|postcss-load-config|4.0.1|间接依赖|npm|
|source-map-js|1.0.2|间接依赖|npm|
|openid-client|5.4.2|间接依赖|npm|
|chokidar|3.5.3|间接依赖|npm|
|tar|6.1.13|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|any-promise|1.3.0|间接依赖|npm|
|is-glob|4.0.3|间接依赖|npm|
|string-width|4.2.3|间接依赖|npm|
|bcrypt|5.1.0|直接依赖|npm|
|regenerator-runtime|0.13.11|间接依赖|npm|
|minipass|4.2.8|间接依赖|npm|
|queue-microtask|1.2.3|间接依赖|npm|
|styled-jsx|5.1.1|间接依赖|npm|
|ip|2.0.0|间接依赖|npm|
|@next/swc-linux-arm64-gnu|13.3.4|间接依赖|npm|
|ts-interface-checker|0.1.13|间接依赖|npm|
|caniuse-lite|1.0.30001482|间接依赖|npm|
|cookie|0.5.0|间接依赖|npm|
|is-number|7.0.0|间接依赖|npm|
|@alloc/quick-lru|5.2.0|间接依赖|npm|
|node-addon-api|5.1.0|间接依赖|npm|
|yallist|4.0.0|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|mongodb-connection-string-url|2.6.0|间接依赖|npm|
|@jridgewell/gen-mapping|0.3.3|间接依赖|npm|
|lines-and-columns|1.2.4|间接依赖|npm|
|arg|5.0.2|间接依赖|npm|
|tailwindcss|3.3.2|直接依赖|npm|
|readable-stream|3.6.2|间接依赖|npm|
|@next/swc-linux-x64-gnu|13.3.4|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|lilconfig|2.1.0|间接依赖|npm|
|chownr|2.0.0|间接依赖|npm|
|nopt|5.0.0|间接依赖|npm|
|@next/swc-win32-ia32-msvc|13.3.4|间接依赖|npm|
|@next/env|13.3.4|间接依赖|npm|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|@jridgewell/resolve-uri|3.1.0|间接依赖|npm|
|tr46|3.0.0|间接依赖|npm|
|saslprep|1.0.3|间接依赖|npm|
|punycode|2.3.0|间接依赖|npm|
|@mapbox/node-pre-gyp|1.0.10|间接依赖|npm|
|uuid|8.3.2|间接依赖|npm|
|picocolors|1.0.0|间接依赖|npm|
|nanoid|3.3.6|间接依赖|npm|
|client-only|0.0.1|间接依赖|npm|
|oidc-token-hash|5.0.3|间接依赖|npm|
|gauge|3.0.2|间接依赖|npm|
|signal-exit|3.0.7|间接依赖|npm|
|@babel/runtime|7.21.5|间接依赖|npm|
|@nodelib/fs.walk|1.2.8|间接依赖|npm|
|commander|4.1.1|间接依赖|npm|
|yaml|2.2.2|间接依赖|npm|
|node-releases|2.0.10|间接依赖|npm|
|@panva/hkdf|1.1.1|间接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|camelcase-css|2.0.1|间接依赖|npm|
|autoprefixer|10.4.14|直接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|preact-render-to-string|5.2.6|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|glob|7.1.6|间接依赖|npm|
|debug|4.3.4|间接依赖|npm|
|emoji-regex|8.0.0|间接依赖|npm|
|mpath|0.9.0|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|https-proxy-agent|5.0.1|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|detect-libc|2.0.1|间接依赖|npm|
|rimraf|3.0.2|间接依赖|npm|
|jose|4.14.4|间接依赖|npm|
|@next/swc-win32-x64-msvc|13.3.4|间接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|postcss-selector-parser|6.0.12|间接依赖|npm|
|@nodelib/fs.stat|2.0.5|间接依赖|npm|
|@next/swc-darwin-x64|13.3.4|间接依赖|npm|
|@jridgewell/trace-mapping|0.3.18|间接依赖|npm|
|string_decoder|1.3.0|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|abbrev|1.1.1|间接依赖|npm|
|@nodelib/fs.scandir|2.1.5|间接依赖|npm|
|update-browserslist-db|1.0.11|间接依赖|npm|
|wide-align|1.1.5|间接依赖|npm|
|strip-ansi|6.0.1|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|fast-glob|3.2.12|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.15|间接依赖|npm|
|next-auth|4.22.1|直接依赖|npm|
|postcss-nested|6.0.1|间接依赖|npm|
|read-cache|1.0.0|间接依赖|npm|
|are-we-there-yet|2.0.0|间接依赖|npm|
|mkdirp|1.0.4|间接依赖|npm|
|browserslist|4.21.5|间接依赖|npm|
|scheduler|0.23.0|间接依赖|npm|
|fs-minipass|2.1.0|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|next|13.3.4|直接依赖|npm|
|electron-to-chromium|1.4.379|间接依赖|npm|
|postcss-import|15.1.0|间接依赖|npm|
|node-fetch|2.6.9|间接依赖|npm|
|socks|2.7.1|间接依赖|npm|
|memory-pager|1.5.0|间接依赖|npm|
|make-dir|3.1.0|间接依赖|npm|
|postcss-js|4.0.1|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|tslib|2.5.0|间接依赖|npm|
|run-parallel|1.2.0|间接依赖|npm|
|kareem|2.5.1|间接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|fastq|1.15.0|间接依赖|npm|
|bson|5.2.0|间接依赖|npm|
|object-hash|3.0.0|间接依赖|npm|
|mquery|5.0.0|间接依赖|npm|
|semver|7.5.0|间接依赖|npm|
|didyoumean|1.2.2|间接依赖|npm|
|busboy|1.6.0|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|is-core-module|2.12.0|间接依赖|npm|
|supports-preserve-symlinks-flag|1.0.0|间接依赖|npm|
|has-unicode|2.0.1|间接依赖|npm|
|cssesc|3.0.0|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|react|18.2.0|直接依赖|npm|
|postcss|8.4.23|间接依赖|npm|
|minizlib|2.1.2|间接依赖|npm|
|normalize-range|0.1.2|间接依赖|npm|
|sparse-bitfield|3.0.3|间接依赖|npm|
|thenify|3.3.1|间接依赖|npm|
|@next/swc-linux-arm64-musl|13.3.4|间接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|react-dom|18.2.0|直接依赖|npm|
|loose-envify|1.4.0|间接依赖|npm|
|smart-buffer|4.2.0|间接依赖|npm|
|aproba|2.0.0|间接依赖|npm|
|@next/swc-win32-arm64-msvc|13.3.4|间接依赖|npm|
|whatwg-url|11.0.0|间接依赖|npm|
|is-binary-path|2.1.0|间接依赖|npm|
|agent-base|6.0.2|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|dlv|1.1.3|间接依赖|npm|
|pirates|4.0.5|间接依赖|npm|
|oauth|0.9.15|间接依赖|npm|
|picomatch|2.3.1|间接依赖|npm|
|binary-extensions|2.2.0|间接依赖|npm|
|fraction.js|4.2.0|间接依赖|npm|
|mongodb|5.3.0|间接依赖|npm|
|mz|2.7.0|间接依赖|npm|
|reusify|1.0.4|间接依赖|npm|
|readdirp|3.6.0|间接依赖|npm|
|fsevents|2.3.2|间接依赖|npm|
|merge2|1.4.1|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)