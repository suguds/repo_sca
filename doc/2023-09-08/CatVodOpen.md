# catvod/CatVodOpen安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699853744660594688.svg)](https://www.murphysec.com/console/report/1699853743905619968/1699853744660594688)

仓库描述：Open version of catvod.

仓库地址：[https://github.com/catvod/CatVodOpen](https://github.com/catvod/CatVodOpen)

| star：437 | watch：16 | fork：151 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-07 18:05:41 | 许可证：- |
| 最近检测时间：2023-09-08 02:34:52 | 组件总数：161 | 漏洞总数：4 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|got 存在打开重定向漏洞|跨站重定向|[MPS-2022-19247](https://www.oscs1024.com/hd/MPS-2022-19247)|CVE-2022-33987|中危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|Google Chrome 缓冲区错误漏洞|越界读取|[MPS-2023-8565](https://www.oscs1024.com/hd/MPS-2023-8565)|CVE-2023-1532|高危|
|Google Chrome 安全漏洞|越界读取|[MPS-n4l8-zc3m](https://www.oscs1024.com/hd/MPS-n4l8-zc3m)|CVE-2023-4427|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|electron|21.4.4|26.0.0-beta.13|直接依赖|建议修复|C:0|H:2|M:0|L:0|
|semver|6.3.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|got|9.6.0|12.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|125|Low|
|BSD-3-Clause|6|Low|
|ISC|13|Low|
|BSD-2-Clause|6|Low|
|Apache-2.0|3|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|get-stream|5.2.0|间接依赖|npm|
|debug|4.3.4|间接依赖|npm|
|fs-constants|1.0.0|间接依赖|npm|
|got|9.6.0|间接依赖|npm|
|global-agent|3.0.0|间接依赖|npm|
|mimic-response|1.0.1|间接依赖|npm|
|debounce-fn|4.0.0|间接依赖|npm|
|global-tunnel-ng|2.7.1|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|node-fetch|2.6.7|间接依赖|npm|
|mime-db|1.52.0|间接依赖|npm|
|electron-store|8.1.0|直接依赖|npm|
|p-cancelable|1.1.0|间接依赖|npm|
|uuid|8.3.2|间接依赖|npm|
|ajv-formats|2.1.1|间接依赖|npm|
|puppeteer-in-electron|3.0.5|直接依赖|npm|
|defer-to-connect|1.1.3|间接依赖|npm|
|@types/node|20.4.2|直接依赖|npm|
|proto-list|1.2.4|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|clone-response|1.0.3|间接依赖|npm|
|es6-error|4.1.1|间接依赖|npm|
|mime-types|2.1.35|直接依赖|npm|
|require-directory|2.1.1|直接依赖|npm|
|uri-js|4.4.1|直接依赖|npm|
|puppeteer-core|19.11.1|直接依赖|npm|
|ws|8.13.0|间接依赖|npm|
|fs-extra|8.1.0|间接依赖|npm|
|object-inspect|1.12.3|间接依赖|npm|
|safe-buffer|5.2.1|间接依赖|npm|
|has-proto|1.0.1|间接依赖|npm|
|url-parse-lax|3.0.0|间接依赖|npm|
|globalthis|1.0.3|间接依赖|npm|
|path-exists|3.0.0|间接依赖|npm|
|follow-redirects|1.15.2|间接依赖|npm|
|pend|1.2.0|间接依赖|npm|
|@types/node|16.18.38|间接依赖|npm|
|fast-deep-equal|3.1.3|直接依赖|npm|
|graceful-fs|4.2.11|间接依赖|npm|
|through|2.3.8|间接依赖|npm|
|semver|6.3.1|间接依赖|npm|
|progress|2.0.3|间接依赖|npm|
|ini|1.3.8|间接依赖|npm|
|pkg-up|3.1.0|间接依赖|npm|
|get-caller-file|2.0.5|直接依赖|npm|
|base64-js|1.5.1|间接依赖|npm|
|@puppeteer/browsers|0.5.0|间接依赖|npm|
|color-name|1.1.4|间接依赖|npm|
|tr46|0.0.3|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|roarr|2.15.4|间接依赖|npm|
|async-retry|1.3.3|间接依赖|npm|
|@types/puppeteer|1.20.10|间接依赖|npm|
|form-data|4.0.0|间接依赖|npm|
|matcher|3.0.0|间接依赖|npm|
|json-schema-typed|7.0.3|间接依赖|npm|
|color-convert|2.0.1|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|type-fest|0.13.1|间接依赖|npm|
|get-port|5.1.1|间接依赖|npm|
|responselike|1.0.2|间接依赖|npm|
|y18n|5.0.8|直接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|locate-path|3.0.0|间接依赖|npm|
|boolean|3.2.0|间接依赖|npm|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|onetime|5.1.2|间接依赖|npm|
|qs|6.11.2|直接依赖|npm|
|@types/retry|0.12.2|间接依赖|npm|
|whatwg-url|5.0.0|间接依赖|npm|
|proxy-from-env|1.1.0|间接依赖|npm|
|fd-slicer|1.1.0|间接依赖|npm|
|require-from-string|2.0.2|直接依赖|npm|
|strip-ansi|6.0.1|间接依赖|npm|
|find-up|3.0.0|间接依赖|npm|
|serialize-error|7.0.1|间接依赖|npm|
|semver-compare|1.0.0|间接依赖|npm|
|is-obj|2.0.0|间接依赖|npm|
|conf|10.2.0|间接依赖|npm|
|string_decoder|1.3.0|间接依赖|npm|
|define-properties|1.2.0|间接依赖|npm|
|@electron/get|1.14.1|间接依赖|npm|
|@types/async-retry|1.4.5|间接依赖|npm|
|decompress-response|3.3.0|间接依赖|npm|
|mkdirp-classic|0.5.3|间接依赖|npm|
|asynckit|0.4.0|直接依赖|npm|
|to-readable-stream|1.0.0|间接依赖|npm|
|http-cache-semantics|4.1.1|间接依赖|npm|
|axios|1.4.0|直接依赖|npm|
|delayed-stream|1.0.0|间接依赖|npm|
|pump|3.0.0|间接依赖|npm|
|tar-fs|2.1.1|间接依赖|npm|
|detect-node|2.1.0|间接依赖|npm|
|buffer-crc32|0.2.13|间接依赖|npm|
|combined-stream|1.0.8|直接依赖|npm|
|escape-string-regexp|4.0.0|间接依赖|npm|
|chromium-bidi|0.4.7|间接依赖|npm|
|has-symbols|1.0.3|间接依赖|npm|
|ieee754|1.2.1|间接依赖|npm|
|@types/node-fetch|2.6.4|间接依赖|npm|
|pify|3.0.0|间接依赖|npm|
|dot-prop|6.0.1|间接依赖|npm|
|lowercase-keys|1.0.1|间接依赖|npm|
|unbzip2-stream|1.4.3|间接依赖|npm|
|cliui|8.0.1|直接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|tunnel|0.0.6|间接依赖|npm|
|get-intrinsic|1.2.1|间接依赖|npm|
|@types/uuid|3.4.10|间接依赖|npm|
|env-paths|2.2.1|间接依赖|npm|
|mitt|3.0.0|间接依赖|npm|
|encodeurl|1.0.2|间接依赖|npm|
|webidl-conversions|3.0.1|间接依赖|npm|
|https-proxy-agent|5.0.1|间接依赖|npm|
|yargs-parser|21.1.1|直接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|side-channel|1.0.4|间接依赖|npm|
|bl|4.1.0|间接依赖|npm|
|buffer|5.7.1|间接依赖|npm|
|json-stringify-safe|5.0.1|间接依赖|npm|
|@types/puppeteer-core|1.20.0|间接依赖|npm|
|config-chain|1.1.13|间接依赖|npm|
|keyv|3.1.0|间接依赖|npm|
|cacheable-request|6.1.0|间接依赖|npm|
|duplexer3|0.1.5|间接依赖|npm|
|sumchecker|3.0.1|间接依赖|npm|
|readable-stream|3.6.2|间接依赖|npm|
|normalize-url|4.5.1|间接依赖|npm|
|electron|21.4.4|直接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|wrap-ansi|7.0.0|间接依赖|npm|
|yallist|4.0.0|间接依赖|npm|
|cross-fetch|3.1.5|间接依赖|npm|
|yauzl|2.10.0|间接依赖|npm|
|string-width|4.2.3|间接依赖|npm|
|npm-conf|1.1.3|间接依赖|npm|
|sprintf-js|1.1.2|间接依赖|npm|
|emoji-regex|8.0.0|间接依赖|npm|
|punycode|2.3.0|间接依赖|npm|
|lru-cache|6.0.0|直接依赖|npm|
|json-buffer|3.0.0|间接依赖|npm|
|retry|0.13.1|间接依赖|npm|
|end-of-stream|1.4.4|间接依赖|npm|
|jsonfile|4.0.0|间接依赖|npm|
|universalify|0.1.2|间接依赖|npm|
|@szmarczak/http-timer|1.1.2|间接依赖|npm|
|@types/yauzl|2.10.0|间接依赖|npm|
|@sindresorhus/is|0.14.0|间接依赖|npm|
|devtools-protocol|0.0.1107588|间接依赖|npm|
|escalade|3.1.1|直接依赖|npm|
|tar-stream|2.2.0|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|ansi-styles|4.3.0|间接依赖|npm|
|extract-zip|2.0.1|间接依赖|npm|
|agent-base|6.0.2|间接依赖|npm|
|mimic-fn|3.1.0|间接依赖|npm|
|p-locate|3.0.0|间接依赖|npm|
|call-bind|1.0.2|间接依赖|npm|
|atomically|1.7.0|间接依赖|npm|
|prepend-http|2.0.0|间接依赖|npm|
|uglify-js|3.17.4|直接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)