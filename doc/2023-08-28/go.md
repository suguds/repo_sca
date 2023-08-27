# golang/go安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695863571886796800.svg)](https://www.murphysec.com/console/report/1695863569617678336/1695863571886796800)

仓库描述：The Go programming language

仓库地址：[https://github.com/golang/go](https://github.com/golang/go)

| star：113886 | watch：3466 | fork：17045 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-27 16:27:50 | 许可证：BSD-3-Clause |
| 最近检测时间：2023-08-28 02:25:45 | 组件总数：140 | 漏洞总数：17 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|GNU Libiberty 安全漏洞|输入验证不恰当|[MPS-2017-1331](https://www.oscs1024.com/hd/MPS-2017-1331)|CVE-2016-6131|高危|
|libiberty 数字错误漏洞||[MPS-2017-2066](https://www.oscs1024.com/hd/MPS-2017-2066)|CVE-2016-2226|高危|
|libiberty 安全漏洞|UAF|[MPS-2017-2070](https://www.oscs1024.com/hd/MPS-2017-2070)|CVE-2016-4487|中危|
|libiberty 安全漏洞|UAF|[MPS-2017-2071](https://www.oscs1024.com/hd/MPS-2017-2071)|CVE-2016-4488|中危|
|libiberty 数字错误漏洞|整数溢出或环绕|[MPS-2017-2072](https://www.oscs1024.com/hd/MPS-2017-2072)|CVE-2016-4489|中危|
|libiberty 数字错误漏洞|整数溢出或环绕|[MPS-2017-2073](https://www.oscs1024.com/hd/MPS-2017-2073)|CVE-2016-4490|中危|
|libiberty 安全漏洞|缓冲区溢出|[MPS-2017-2074](https://www.oscs1024.com/hd/MPS-2017-2074)|CVE-2016-4491|中危|
|libiberty 缓冲区错误漏洞|缓冲区溢出|[MPS-2017-2075](https://www.oscs1024.com/hd/MPS-2017-2075)|CVE-2016-4492|中危|
|libiberty 安全漏洞|越界读取|[MPS-2017-2076](https://www.oscs1024.com/hd/MPS-2017-2076)|CVE-2016-4493|中危|
|GNU Binutils 安全漏洞|不可达退出条件的循环（无限循环）|[MPS-2018-14162](https://www.oscs1024.com/hd/MPS-2018-14162)|CVE-2018-18700|中危|
|GNU Binutils GNU libiberty 安全漏洞|拒绝服务|[MPS-2018-8266](https://www.oscs1024.com/hd/MPS-2018-8266)|CVE-2018-12698|高危|
|GNU Binutils 缓冲区错误漏洞|越界读取|[MPS-2019-1889](https://www.oscs1024.com/hd/MPS-2019-1889)|CVE-2019-9070|高危|
|GNU libiberty 缓冲区错误漏洞|缓冲区溢出|[MPS-2021-32366](https://www.oscs1024.com/hd/MPS-2021-32366)|CVE-2021-3826|高危|
|d3-color < 3.1.0 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13618](https://www.oscs1024.com/hd/MPS-2022-13618)||中危|
|terser 安全漏洞|ReDoS|[MPS-2022-5145](https://www.oscs1024.com/hd/MPS-2022-5145)|CVE-2022-25858|高危|
|Google Go 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2022-9049](https://www.oscs1024.com/hd/MPS-2022-9049)|CVE-2022-29526|中危|
|Webpack 安全漏洞||[MPS-2023-7721](https://www.oscs1024.com/hd/MPS-2023-7721)|CVE-2023-28154|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|libiberty|9.1.0|20220713-1|间接依赖|建议修复|C:0|H:5|M:8|L:0|
|terser|5.10.0|5.14.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|webpack|5.64.4|5.76.0|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|golang.org/x/sys|v0.0.0-20211030160813-b3129d9d1021|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|d3-color|1.4.1|3.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|23|Low|
|MIT|94|Low|
|ISC|8|Low|
|Apache-2.0|5|Low|
|BSD-2-Clause|6|Low|
|LGPL-2.1|1|Medium|
|CC-BY-4.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|golang.org/x/sys|v0.11.1-0.20230809150802-ee578879d89c|直接依赖|go|
|clone-deep|4.0.1|间接依赖|npm|
|fastest-levenshtein|1.0.12|间接依赖|npm|
|acorn|8.6.0|间接依赖|npm|
|ajv-keywords|3.5.2|间接依赖|npm|
|@webassemblyjs/wasm-parser|1.11.1|间接依赖|npm|
|@webassemblyjs/helper-numbers|1.11.1|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|pkg-dir|4.2.0|间接依赖|npm|
|locate-path|5.0.0|间接依赖|npm|
|internmap|2.0.3|直接依赖|npm|
|loader-runner|4.2.0|间接依赖|npm|
|@webassemblyjs/leb128|1.11.1|间接依赖|npm|
|merge-stream|2.0.0|间接依赖|npm|
|human-signals|2.1.0|间接依赖|npm|
|github.com/google/pprof|v0.0.0-20230811205829-9131a7e9cc17|直接依赖|go|
|isexe|2.0.0|间接依赖|npm|
|path-exists|4.0.0|间接依赖|npm|
|golang.org/x/xerrors|v0.0.0-20200804184101-5ec99f83aff1|间接依赖|go|
|path-parse|1.0.7|间接依赖|npm|
|rechoir|0.7.1|间接依赖|npm|
|strip-final-newline|2.0.0|间接依赖|npm|
|mimic-fn|2.1.0|间接依赖|npm|
|estraverse|4.3.0|间接依赖|npm|
|libiberty|9.1.0|间接依赖||
|serialize-javascript|6.0.0|间接依赖|npm|
|@xtuc/long|4.2.2|间接依赖|npm|
|d3-color|1.4.1|间接依赖|npm|
|shebang-command|2.0.0|间接依赖|npm|
|envinfo|7.8.1|间接依赖|npm|
|@webassemblyjs/floating-point-hex-parser|1.11.1|间接依赖|npm|
|d3-flame-graph|4.1.3|直接依赖|npm|
|@webassemblyjs/utf8|1.11.1|间接依赖|npm|
|colorette|2.0.16|间接依赖|npm|
|is-core-module|2.8.0|间接依赖|npm|
|buffer-from|1.1.2|间接依赖|npm|
|@webassemblyjs/helper-buffer|1.11.1|间接依赖|npm|
|resolve-cwd|3.0.0|间接依赖|npm|
|golang.org/x/net|v0.14.1-0.20230809150940-1e23797619c9|直接依赖|go|
|golang.org/x/text|v0.12.0|间接依赖|go|
|@types/eslint|8.2.1|间接依赖|npm|
|webpack-merge|5.8.0|间接依赖|npm|
|github.com/ianlancetaylor/demangle|v0.0.0-20230524184225-eabc099b10ab|间接依赖|go|
|function-bind|1.1.1|间接依赖|npm|
|node-releases|2.0.1|间接依赖|npm|
|d3-selection|3.0.0|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|randombytes|2.1.0|间接依赖|npm|
|@webassemblyjs/wasm-opt|1.11.1|间接依赖|npm|
|@webpack-cli/configtest|1.1.0|间接依赖|npm|
|has-flag|4.0.0|间接依赖|npm|
|@webassemblyjs/ast|1.11.1|间接依赖|npm|
|@webassemblyjs/helper-wasm-bytecode|1.11.1|间接依赖|npm|
|mime-db|1.51.0|间接依赖|npm|
|graceful-fs|4.2.8|间接依赖|npm|
|acorn-import-assertions|1.8.0|间接依赖|npm|
|npm-run-path|4.0.1|间接依赖|npm|
|eslint-scope|5.1.1|间接依赖|npm|
|path-key|3.1.1|间接依赖|npm|
|webpack|5.64.4|直接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|@webassemblyjs/ieee754|1.11.1|间接依赖|npm|
|safe-buffer|5.2.1|间接依赖|npm|
|signal-exit|3.0.6|间接依赖|npm|
|schema-utils|3.1.1|间接依赖|npm|
|d3-interpolate|1.4.0|直接依赖|npm|
|@webpack-cli/serve|1.6.0|间接依赖|npm|
|import-local|3.0.3|间接依赖|npm|
|d3-time|1.1.0|间接依赖|npm|
|shallow-clone|3.0.1|间接依赖|npm|
|mime-types|2.1.34|间接依赖|npm|
|golang.org/x/tools|v0.1.7|间接依赖|go|
|@types/json-schema|7.0.9|间接依赖|npm|
|picocolors|1.0.0|间接依赖|npm|
|punycode|2.1.1|间接依赖|npm|
|terser-webpack-plugin|5.2.5|间接依赖|npm|
|golang.org/x/sync|v0.3.0|直接依赖|go|
|get-stream|6.0.1|间接依赖|npm|
|shebang-regex|3.0.0|间接依赖|npm|
|es-module-lexer|0.9.3|间接依赖|npm|
|@webassemblyjs/helper-wasm-section|1.11.1|间接依赖|npm|
|terser|5.10.0|间接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|golang.org/x/arch|v0.4.0|直接依赖|go|
|isobject|3.0.1|间接依赖|npm|
|golang.org/x/mod|v0.4.2|间接依赖|go|
|golang.org/x/crypto|v0.12.0|直接依赖|go|
|webpack-sources|3.2.2|间接依赖|npm|
|resolve|1.20.0|间接依赖|npm|
|jest-worker|27.4.2|间接依赖|npm|
|golang.org/x/sys|v0.0.0-20211030160813-b3129d9d1021|间接依赖|go|
|enhanced-resolve|5.8.3|间接依赖|npm|
|onetime|5.1.2|间接依赖|npm|
|tapable|2.2.1|间接依赖|npm|
|@webassemblyjs/wasm-edit|1.11.1|间接依赖|npm|
|d3-timer|1.0.10|直接依赖|npm|
|d3-time-format|2.3.0|直接依赖|npm|
|esrecurse|4.3.0|间接依赖|npm|
|@webassemblyjs/wast-printer|1.11.1|间接依赖|npm|
|cross-spawn|7.0.3|间接依赖|npm|
|is-plain-object|2.0.4|间接依赖|npm|
|interpret|2.2.0|间接依赖|npm|
|@types/eslint-scope|3.7.1|间接依赖|npm|
|caniuse-lite|1.0.30001284|间接依赖|npm|
|@webassemblyjs/wasm-gen|1.11.1|间接依赖|npm|
|electron-to-chromium|1.4.11|间接依赖|npm|
|golang.org/x/tools|v0.12.1-0.20230815132531-74c255bcf846|直接依赖|go|
|supports-color|8.1.1|间接依赖|npm|
|watchpack|2.3.0|间接依赖|npm|
|execa|5.1.1|间接依赖|npm|
|json-parse-better-errors|1.0.2|间接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|golang.org/x/term|v0.11.0|直接依赖|go|
|resolve-from|5.0.0|间接依赖|npm|
|@xtuc/ieee754|1.2.0|间接依赖|npm|
|wildcard|2.0.0|间接依赖|npm|
|source-map|0.6.1|间接依赖|npm|
|events|3.3.0|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|neo-async|2.6.2|间接依赖|npm|
|chrome-trace-event|1.0.3|间接依赖|npm|
|commander|2.20.3|间接依赖|npm|
|which|2.0.2|间接依赖|npm|
|find-up|4.1.0|间接依赖|npm|
|kind-of|6.0.3|间接依赖|npm|
|webpack-cli|4.9.1|直接依赖|npm|
|@webassemblyjs/helper-api-error|1.11.1|间接依赖|npm|
|@discoveryjs/json-ext|0.5.6|间接依赖|npm|
|@types/estree|0.0.50|间接依赖|npm|
|browserslist|4.18.1|间接依赖|npm|
|golang.org/x/mod|v0.12.0|直接依赖|go|
|source-map-support|0.5.21|间接依赖|npm|
|@types/node|16.11.11|间接依赖|npm|
|libc.so.6||间接依赖||
|@webpack-cli/info|1.4.0|间接依赖|npm|
|is-stream|2.0.1|间接依赖|npm|
|p-locate|4.1.0|间接依赖|npm|
|ajv|6.12.6|间接依赖|npm|
|glob-to-regexp|0.4.1|间接依赖|npm|
|github.com/mmcloughlin/avo|v0.4.0|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)