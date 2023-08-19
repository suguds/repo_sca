# remoteintech/remote-jobs安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692969151293579264.svg)](https://www.murphysec.com/console/report/1692969150672822272/1692969151293579264)

仓库描述：A list of semi to fully remote-friendly companies (jobs) in tech.

仓库地址：[https://github.com/remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs)

| star：25272 | watch：905 | fork：2704 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-02 18:25:20 | 许可证：CC0-1.0 |
| 最近检测时间：2023-08-20 02:38:04 | 组件总数：150 | 漏洞总数：7 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|colors.js  >1.4.0 DOS漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-19606](https://www.oscs1024.com/hd/MPS-2021-19606)|CVE-2021-23567|高危|
|minimist 安全漏洞|原型污染|[MPS-2021-38405](https://www.oscs1024.com/hd/MPS-2021-38405)|CVE-2021-44906|严重|
|uglify-js <3.14.3 正则表达式拒绝服务漏洞|ReDoS|[MPS-2022-14112](https://www.oscs1024.com/hd/MPS-2022-14112)||中危|
|Express 中的 qs 模块存在原型污染漏洞|原型污染|[MPS-2022-3967](https://www.oscs1024.com/hd/MPS-2022-3967)|CVE-2022-24999|高危|
|mocha ReDoS 漏洞|ReDoS|[MPS-2022-54598](https://www.oscs1024.com/hd/MPS-2022-54598)||高危|
|minimatch 资源管理错误漏洞|拒绝服务|[MPS-2022-59845](https://www.oscs1024.com/hd/MPS-2022-59845)|CVE-2022-3517|高危|
|swig 安全漏洞|路径遍历|[MPS-2023-3992](https://www.oscs1024.com/hd/MPS-2023-3992)|CVE-2023-25345|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|swig-templates|2.0.3||直接依赖|建议修复|C:0|H:1|M:0|L:0|
|qs|6.10.1|6.10.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|minimatch|3.0.4|3.0.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|mocha|9.2.2||直接依赖|建议修复|C:0|H:1|M:0|L:0|
|minimist|1.2.5|1.2.6|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|colors|1.4.0||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|uglify-js|2.6.0|3.14.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|112|Low|
|ISC|19|Low|
|BSD-2-Clause|9|Low|
|Python-2.0|1|Low|
|Apache-2.0|1|Low|
|BSD-3-Clause|5|Low|
|0BSD|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|concat-map|0.0.1|间接依赖|npm|
|locate-path|6.0.0|间接依赖|npm|
|window-size|0.1.0|直接依赖|npm|
|check-error|1.0.2|间接依赖|npm|
|wrap-ansi|7.0.0|间接依赖|npm|
|parse5-htmlparser2-tree-adapter|6.0.1|间接依赖|npm|
|yargs-parser|20.2.4|间接依赖|npm|
|object-inspect|1.11.0|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|iconv-lite|0.6.3|间接依赖|npm|
|p-limit|3.1.0|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|chokidar|3.5.3|间接依赖|npm|
|call-bind|1.0.2|间接依赖|npm|
|domelementtype|2.2.0|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|has-symbols|1.0.2|间接依赖|npm|
|async|2.6.4|间接依赖|npm|
|cheerio-select|1.5.0|间接依赖|npm|
|ansi-styles|4.3.0|间接依赖|npm|
|http-proxy|1.18.1|间接依赖|npm|
|argparse|2.0.1|间接依赖|npm|
|is-binary-path|2.1.0|间接依赖|npm|
|y18n|5.0.8|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|camelcase|6.2.0|间接依赖|npm|
|is-plain-obj|2.1.0|间接依赖|npm|
|type-detect|4.0.8|间接依赖|npm|
|minimist|1.2.5|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|domhandler|4.2.2|间接依赖|npm|
|emoji-regex|8.0.0|间接依赖|npm|
|basic-auth|2.0.1|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|requires-port|1.0.0|间接依赖|npm|
|find-up|5.0.0|间接依赖|npm|
|mime|1.6.0|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|get-func-name|2.0.0|间接依赖|npm|
|glob|7.2.0|间接依赖|npm|
|yargs|16.2.0|间接依赖|npm|
|boolbase|1.0.0|间接依赖|npm|
|is-number|7.0.0|间接依赖|npm|
|workerpool|6.2.0|间接依赖|npm|
|js-yaml|4.1.0|间接依赖|npm|
|rimraf|3.0.2|直接依赖|npm|
|nth-check|2.0.1|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|uglify-js|2.6.0|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|source-map|0.5.7|间接依赖|npm|
|union|0.5.0|间接依赖|npm|
|minimatch|3.0.4|间接依赖|npm|
|side-channel|1.0.4|间接依赖|npm|
|is-buffer|1.1.6|间接依赖|npm|
|dom-serializer|1.3.2|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|secure-compare|3.0.1|间接依赖|npm|
|get-intrinsic|1.1.1|间接依赖|npm|
|path-exists|4.0.0|间接依赖|npm|
|align-text|0.1.4|间接依赖|npm|
|mkdirp|0.5.5|间接依赖|npm|
|colors|1.4.0|间接依赖|npm|
|browser-stdout|1.3.1|间接依赖|npm|
|mocha|9.2.2|直接依赖|npm|
|ansi-colors|4.1.1|间接依赖|npm|
|growl|1.10.5|间接依赖|npm|
|lazy-cache|1.0.4|间接依赖|npm|
|strip-json-comments|3.1.1|间接依赖|npm|
|chalk|4.1.2|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|debug|4.3.3|间接依赖|npm|
|supports-color|8.1.1|间接依赖|npm|
|opener|1.5.2|间接依赖|npm|
|yargs-unparser|2.0.0|间接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|cheerio|1.0.0-rc.10|直接依赖|npm|
|eventemitter3|4.0.7|间接依赖|npm|
|nanoid|3.3.1|间接依赖|npm|
|ms|2.1.3|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|lunr|2.3.7|直接依赖|npm|
|binary-extensions|2.2.0|间接依赖|npm|
|cliui|7.0.4|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|tslib|2.3.1|间接依赖|npm|
|yocto-queue|0.1.0|间接依赖|npm|
|strip-ansi|6.0.1|间接依赖|npm|
|html-encoding-sniffer|3.0.0|间接依赖|npm|
|follow-redirects|1.14.8|间接依赖|npm|
|chai|4.3.4|直接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|right-align|0.1.3|直接依赖|npm|
|color-convert|2.0.1|间接依赖|npm|
|domutils|2.8.0|间接依赖|npm|
|anymatch|3.1.2|间接依赖|npm|
|phin|3.6.0|直接依赖|npm|
|entities|2.2.0|间接依赖|npm|
|is-unicode-supported|0.1.0|间接依赖|npm|
|diff|5.0.0|间接依赖|npm|
|corser|2.0.1|间接依赖|npm|
|fsevents|2.3.2|间接依赖|npm|
|repeat-string|1.6.1|间接依赖|npm|
|center-align|0.1.3|直接依赖|npm|
|decamelize|4.0.0|间接依赖|npm|
|assertion-error|1.1.0|间接依赖|npm|
|picomatch|2.3.1|间接依赖|npm|
|wordwrap|0.0.3|间接依赖|npm|
|uglify-to-browserify|1.0.2|间接依赖|npm|
|@ungap/promise-all-settled|1.1.2|间接依赖|npm|
|htmlparser2|6.1.0|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|portfinder|1.0.28|间接依赖|npm|
|which|2.0.2|间接依赖|npm|
|url-join|4.0.1|间接依赖|npm|
|http-server|14.0.0|直接依赖|npm|
|serialize-javascript|6.0.0|间接依赖|npm|
|longest|1.0.1|间接依赖|npm|
|log-symbols|4.1.0|间接依赖|npm|
|pathval|1.1.1|间接依赖|npm|
|escape-string-regexp|4.0.0|间接依赖|npm|
|string-width|4.2.3|间接依赖|npm|
|glob-parent|5.1.2|间接依赖|npm|
|color-name|1.1.4|间接依赖|npm|
|marked|4.0.10|直接依赖|npm|
|parse5|6.0.1|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|kind-of|3.2.2|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|readdirp|3.6.0|间接依赖|npm|
|css-what|5.1.0|间接依赖|npm|
|swig-templates|2.0.3|直接依赖|npm|
|deep-eql|3.0.1|间接依赖|npm|
|centra|2.5.0|间接依赖|npm|
|randombytes|2.1.0|间接依赖|npm|
|has-flag|4.0.0|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|p-locate|5.0.0|间接依赖|npm|
|whatwg-encoding|2.0.0|间接依赖|npm|
|optimist|0.6.1|间接依赖|npm|
|he|1.2.0|间接依赖|npm|
|css-select|4.1.3|间接依赖|npm|
|qs|6.10.1|间接依赖|npm|
|flat|5.0.2|间接依赖|npm|
|is-glob|4.0.3|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)