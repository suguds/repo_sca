# Reamd7/notion-zh_CN安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695869733080752128.svg)](https://www.murphysec.com/console/report/1695869732233502720/1695869733080752128)

仓库描述：notion 中文化

仓库地址：[https://github.com/Reamd7/notion-zh_CN](https://github.com/Reamd7/notion-zh_CN)

| star：5749 | watch：39 | fork：1018 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-28 00:16:47 | 许可证：- |
| 最近检测时间：2023-08-28 02:50:06 | 组件总数：80 | 漏洞总数：8 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|follow-redirects <1.14.7 存在信息泄露漏洞|侵犯隐私|[MPS-2022-0815](https://www.oscs1024.com/hd/MPS-2022-0815)|CVE-2022-0155|中危|
|node-fetch 信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-1461](https://www.oscs1024.com/hd/MPS-2022-1461)|CVE-2022-0235|中危|
|follow-redirects<1.14.8 信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-3636](https://www.oscs1024.com/hd/MPS-2022-3636)|CVE-2022-0536|中危|
|nwsapi 拒绝服务|拒绝服务|[MPS-2022-54623](https://www.oscs1024.com/hd/MPS-2022-54623)||中危|
|cross-fetch 安全漏洞|授权检查错误|[MPS-2022-8877](https://www.oscs1024.com/hd/MPS-2022-8877)|CVE-2022-1365|中危|
|word-wrap 安全漏洞|ReDoS|[MPS-2023-5109](https://www.oscs1024.com/hd/MPS-2023-5109)|CVE-2023-26115|高危|
|tough-cookie 安全漏洞|原型污染|[MPS-2023-5130](https://www.oscs1024.com/hd/MPS-2023-5130)|CVE-2023-26136|严重|
|tough-cookie<4.1.3 存在原型污染漏洞|原型污染|[MPS-esyq-56vx](https://www.oscs1024.com/hd/MPS-esyq-56vx)||中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|word-wrap|1.2.3|1.2.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tough-cookie|4.0.0|4.1.3|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|nwsapi|2.2.0|2.2.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|follow-redirects|1.14.4|1.14.8|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|node-fetch|2.6.2|3.2.10|间接依赖|可选修复|C:0|H:0|M:2|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|64|Low|
|BSD-2-Clause|7|Low|
|ISC|3|Low|
|Apache-2.0|2|Low|
|0BSD|1|Low|
|BSD-3-Clause|3|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|psl|1.8.0|间接依赖|npm|
|acorn-globals|6.0.0|间接依赖|npm|
|symbol-tree|3.2.4|间接依赖|npm|
|whatwg-mimetype|2.3.0|间接依赖|npm|
|deep-is|0.1.4|间接依赖|npm|
|browser-process-hrtime|1.0.0|间接依赖|npm|
|saxes|5.0.1|间接依赖|npm|
|form-data|4.0.0|间接依赖|npm|
|parse5|6.0.1|间接依赖|npm|
|domexception|2.0.1|间接依赖|npm|
|nwsapi|2.2.0|间接依赖|npm|
|w3c-xmlserializer|2.0.0|间接依赖|npm|
|xml-name-validator|3.0.0|间接依赖|npm|
|tslib|1.13.0|间接依赖|npm|
|webidl-conversions|5.0.0|间接依赖|npm|
|acorn|8.5.0|间接依赖|npm|
|lodash|4.17.21|直接依赖|npm|
|whatwg-url|9.1.0|间接依赖|npm|
|estraverse|5.2.0|间接依赖|npm|
|ws|8.2.2|间接依赖|npm|
|html-encoding-sniffer|2.0.1|间接依赖|npm|
|pinyin-pro|3.3.1|直接依赖|npm|
|prettier|2.4.1|直接依赖|npm|
|source-map|0.6.1|直接依赖|npm|
|shebang-regex|3.0.0|间接依赖|npm|
|http-proxy-agent|4.0.1|间接依赖|npm|
|data-urls|3.0.0|间接依赖|npm|
|cssom|0.3.8|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|punycode|2.1.1|间接依赖|npm|
|fast-levenshtein|2.0.6|间接依赖|npm|
|follow-redirects|1.14.4|间接依赖|npm|
|form-data|3.0.1|间接依赖|npm|
|asynckit|0.4.0|间接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|@types/lodash|4.14.173|直接依赖|npm|
|node-fetch|2.6.2|间接依赖|npm|
|tencentcloud-sdk-nodejs|4.0.203|直接依赖|npm|
|acorn-walk|7.2.0|间接依赖|npm|
|cross-spawn|7.0.3|间接依赖|npm|
|cssstyle|2.3.0|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|optionator|0.8.3|间接依赖|npm|
|esprima|4.0.1|间接依赖|npm|
|cross-env|7.0.3|直接依赖|npm|
|prelude-ls|1.1.2|间接依赖|npm|
|xmlchars|2.2.0|间接依赖|npm|
|esutils|2.0.3|间接依赖|npm|
|abab|2.0.5|间接依赖|npm|
|decimal.js|10.3.1|间接依赖|npm|
|word-wrap|1.2.3|间接依赖|npm|
|is-potential-custom-element-name|1.0.1|间接依赖|npm|
|iconv-lite|0.4.24|间接依赖|npm|
|tr46|2.1.0|间接依赖|npm|
|@types/node|16.9.1|直接依赖|npm|
|@tootallnate/once|1.1.2|间接依赖|npm|
|jsdom|17.0.0|直接依赖|npm|
|mime-types|2.1.32|间接依赖|npm|
|delayed-stream|1.0.0|间接依赖|npm|
|tough-cookie|4.0.0|间接依赖|npm|
|webidl-conversions|6.1.0|间接依赖|npm|
|whatwg-encoding|1.0.5|间接依赖|npm|
|cssom|0.5.0|间接依赖|npm|
|is-stream|2.0.1|间接依赖|npm|
|shebang-command|2.0.0|间接依赖|npm|
|universalify|0.1.2|间接依赖|npm|
|combined-stream|1.0.8|间接依赖|npm|
|which|2.0.2|间接依赖|npm|
|type-check|0.3.2|间接依赖|npm|
|escodegen|2.0.0|间接依赖|npm|
|acorn|7.4.1|间接依赖|npm|
|path-key|3.1.1|间接依赖|npm|
|mime-db|1.49.0|间接依赖|npm|
|agent-base|6.0.2|间接依赖|npm|
|axios|0.21.4|直接依赖|npm|
|levn|0.3.0|间接依赖|npm|
|debug|4.3.2|间接依赖|npm|
|https-proxy-agent|5.0.0|间接依赖|npm|
|w3c-hr-time|1.0.2|间接依赖|npm|
|get-stream|6.0.1|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)