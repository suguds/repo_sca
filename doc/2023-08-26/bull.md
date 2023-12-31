# OptimalBits/bull安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695145001054199808.svg)](https://www.murphysec.com/console/report/1695145001016451072/1695145001054199808)

仓库描述：Premium Queue package for handling distributed jobs and messages in NodeJS.

仓库地址：[https://github.com/OptimalBits/bull](https://github.com/OptimalBits/bull)

| star：14325 | watch：113 | fork：1471 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-19 15:48:59 | 许可证：NOASSERTION |
| 最近检测时间：2023-08-26 02:44:11 | 组件总数：940 | 漏洞总数：52 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|org.webjars.npm:semver-regex ReDoS 漏洞|拒绝服务|[MPS-2015-6495](https://www.oscs1024.com/hd/MPS-2015-6495)||高危|
|Http-signature 安全漏洞|密码学签名的验证不恰当|[MPS-2018-6996](https://www.oscs1024.com/hd/MPS-2018-6996)|CVE-2017-16005|高危|
|lodash 原型污染漏洞|拒绝服务|[MPS-2019-8636](https://www.oscs1024.com/hd/MPS-2019-8636)|CVE-2019-10744|严重|
|property-expr 输入验证错误漏洞|原型污染|[MPS-2020-11771](https://www.oscs1024.com/hd/MPS-2020-11771)|CVE-2020-7707|严重|
|lodash <4.17.15 原型污染漏洞|原型污染|[MPS-2020-15679](https://www.oscs1024.com/hd/MPS-2020-15679)|CVE-2020-8203|高危|
|dot-prop 原型污染漏洞|原型污染|[MPS-2020-1734](https://www.oscs1024.com/hd/MPS-2020-1734)|CVE-2020-8116|高危|
|yargs-parser 原型污染漏洞|特权定义了不安全动作|[MPS-2020-4006](https://www.oscs1024.com/hd/MPS-2020-4006)|CVE-2020-7608|中危|
|nanoid < 3.1.31 信息泄露漏洞|不正确的类型转换|[MPS-2021-19605](https://www.oscs1024.com/hd/MPS-2021-19605)|CVE-2021-23566|中危|
|colors.js  >1.4.0 DOS漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-19606](https://www.oscs1024.com/hd/MPS-2021-19606)|CVE-2021-23567|高危|
|lodash 拒绝服务漏洞|拒绝服务|[MPS-2021-2574](https://www.oscs1024.com/hd/MPS-2021-2574)|CVE-2020-28500|中危|
|lodash 命令注入漏洞|代码注入|[MPS-2021-2638](https://www.oscs1024.com/hd/MPS-2021-2638)|CVE-2021-23337|高危|
|Npm Node-tar 后置链接漏洞||[MPS-2021-28486](https://www.oscs1024.com/hd/MPS-2021-28486)|CVE-2021-37701|高危|
|Npm Node-tar 后置链接漏洞||[MPS-2021-28488](https://www.oscs1024.com/hd/MPS-2021-28488)|CVE-2021-37712|高危|
|node-tar 路径遍历漏洞|路径遍历|[MPS-2021-28489](https://www.oscs1024.com/hd/MPS-2021-28489)|CVE-2021-37713|高危|
|arborist 后置链接漏洞|UNIX符号链接跟随|[MPS-2021-29716](https://www.oscs1024.com/hd/MPS-2021-29716)|CVE-2021-39134|高危|
|NPM @npmcli/arborist 后置链接漏洞|UNIX符号链接跟随|[MPS-2021-29717](https://www.oscs1024.com/hd/MPS-2021-29717)|CVE-2021-39135|高危|
|semver-regex 拒绝服务漏洞|ReDoS|[MPS-2021-31625](https://www.oscs1024.com/hd/MPS-2021-31625)|CVE-2021-3795|高危|
|json-schema 安全漏洞|原型污染|[MPS-2021-34478](https://www.oscs1024.com/hd/MPS-2021-34478)|CVE-2021-3918|严重|
|semver-regex 安全漏洞|ReDoS|[MPS-2021-35111](https://www.oscs1024.com/hd/MPS-2021-35111)|CVE-2021-43307|高危|
|marked 存在拒绝服务漏洞||[MPS-2021-37038](https://www.oscs1024.com/hd/MPS-2021-37038)|CVE-2022-21680|高危|
|marked 存在拒绝服务漏洞|过度严格的正则表达式|[MPS-2021-37039](https://www.oscs1024.com/hd/MPS-2021-37039)|CVE-2022-21681|高危|
|minimist 安全漏洞|原型污染|[MPS-2021-38405](https://www.oscs1024.com/hd/MPS-2021-38405)|CVE-2021-44906|严重|
|browserslist 存在正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-5473](https://www.oscs1024.com/hd/MPS-2021-5473)|CVE-2021-23364|中危|
|normalize-url 存在正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-7113](https://www.oscs1024.com/hd/MPS-2021-7113)|CVE-2021-33502|高危|
|trim-newlines 存在拒绝服务漏洞|拒绝服务|[MPS-2021-7398](https://www.oscs1024.com/hd/MPS-2021-7398)|CVE-2021-33623|高危|
|semantic-release 信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11081](https://www.oscs1024.com/hd/MPS-2022-11081)|CVE-2022-31051|高危|
|Moment.js 正则拒绝服务漏洞|拒绝服务|[MPS-2022-11159](https://www.oscs1024.com/hd/MPS-2022-11159)|CVE-2022-31129|高危|
|conventional-commits-parser < 3.2.3 存在正则表达式拒绝服务漏洞|ReDoS|[MPS-2022-13608](https://www.oscs1024.com/hd/MPS-2022-13608)||中危|
|istanbul-reports<3.1.3 反向 Tabnabbing漏洞|通过 window.opener 访问使用指向不受信任目标的 Web 链接|[MPS-2022-13797](https://www.oscs1024.com/hd/MPS-2022-13797)||中危|
|lodash<4.17.20 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13841](https://www.oscs1024.com/hd/MPS-2022-13841)||高危|
|lodash<4.17.17 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13842](https://www.oscs1024.com/hd/MPS-2022-13842)||高危|
|ramda <0.27.2 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13991](https://www.oscs1024.com/hd/MPS-2022-13991)||中危|
|semver-regex 存在拒绝服务漏洞|拒绝服务|[MPS-2022-14031](https://www.oscs1024.com/hd/MPS-2022-14031)||高危|
|semver-regex 存在ReDoS漏洞|ReDoS|[MPS-2022-14032](https://www.oscs1024.com/hd/MPS-2022-14032)||中危|
|uglify-js <3.14.3 正则表达式拒绝服务漏洞|ReDoS|[MPS-2022-14112](https://www.oscs1024.com/hd/MPS-2022-14112)||中危|
|yup 存在原型污染漏洞|原型污染|[MPS-2022-14161](https://www.oscs1024.com/hd/MPS-2022-14161)||中危|
|Moment.js 路径遍历漏洞|路径遍历|[MPS-2022-3752](https://www.oscs1024.com/hd/MPS-2022-3752)|CVE-2022-24785|中危|
|Express 中的 qs 模块存在原型污染漏洞|原型污染|[MPS-2022-3967](https://www.oscs1024.com/hd/MPS-2022-3967)|CVE-2022-24999|高危|
|simple-git-hooks安全漏洞|命令注入|[MPS-2022-5073](https://www.oscs1024.com/hd/MPS-2022-5073)|CVE-2022-24066|严重|
|simple-git-hooks 存在命令执行漏洞|命令注入|[MPS-2022-5086](https://www.oscs1024.com/hd/MPS-2022-5086)|CVE-2022-24433|严重|
|simple-git 安全漏洞|代码注入|[MPS-2022-5147](https://www.oscs1024.com/hd/MPS-2022-5147)|CVE-2022-25860|严重|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|simple-git <3.15.0 存在远程代码执行漏洞|OS命令注入|[MPS-2022-5191](https://www.oscs1024.com/hd/MPS-2022-5191)|CVE-2022-25912|高危|
|mocha ReDoS 漏洞|ReDoS|[MPS-2022-54598](https://www.oscs1024.com/hd/MPS-2022-54598)||高危|
|decode-uri-component <=0.2.0 存在输入验证不当漏洞|拒绝服务|[MPS-2022-56259](https://www.oscs1024.com/hd/MPS-2022-56259)|CVE-2022-38900|高危|
|minimatch 资源管理错误漏洞|拒绝服务|[MPS-2022-59845](https://www.oscs1024.com/hd/MPS-2022-59845)|CVE-2022-3517|高危|
|Tauri 原型污染漏洞|原型污染|[MPS-2022-65568](https://www.oscs1024.com/hd/MPS-2022-65568)|CVE-2022-46175|高危|
|Luxon 存在Redos漏洞|ReDoS|[MPS-2022-69796](https://www.oscs1024.com/hd/MPS-2022-69796)|CVE-2023-22467|中危|
|word-wrap 安全漏洞|ReDoS|[MPS-2023-5109](https://www.oscs1024.com/hd/MPS-2023-5109)|CVE-2023-26115|高危|
|tough-cookie 安全漏洞|原型污染|[MPS-2023-5130](https://www.oscs1024.com/hd/MPS-2023-5130)|CVE-2023-26136|严重|
|request SSRF防御绕过漏洞|SSRF|[MPS-2023-7722](https://www.oscs1024.com/hd/MPS-2023-7722)|CVE-2023-28155|中危|
|tough-cookie<4.1.3 存在原型污染漏洞|原型污染|[MPS-esyq-56vx](https://www.oscs1024.com/hd/MPS-esyq-56vx)||中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|simple-git|1.132.0|3.16.0|间接依赖|强烈建议修复|C:3|H:1|M:0|L:0|
|semver-regex|3.1.2|4.0.3|间接依赖|建议修复|C:0|H:4|M:1|L:0|
|minimatch|3.0.4|3.0.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|word-wrap|1.2.3|1.2.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|mocha|8.3.2||直接依赖|建议修复|C:0|H:1|M:0|L:0|
|json5|2.2.0|2.2.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tough-cookie|2.5.0|4.1.3|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|tar|6.1.6|6.1.9|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|minimist|1.2.5|1.2.6|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|normalize-url|6.0.0|6.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|property-expr|1.5.1|2.0.3|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|lodash|4.17.11|4.17.21|间接依赖|建议修复|C:1|H:4|M:1|L:0|
|json-schema|0.2.3|0.4.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|qs|6.5.2|6.10.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|semantic-release|17.4.2|19.0.3|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|http-signature|1.2.0||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|trim-newlines|3.0.0|4.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|colors|1.4.0||直接依赖|建议修复|C:0|H:1|M:0|L:0|
|decode-uri-component|0.2.0|0.2.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|trim-newlines|2.0.0|4.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|dot-prop|3.0.0|5.1.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|@npmcli/arborist|2.4.0|2.8.2|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|luxon|1.28.0|3.2.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|6.0.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|ramda|0.27.1|0.27.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|request|2.88.2||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|browserslist|4.16.4|4.16.5|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|conventional-commits-parser|2.1.7|3.2.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|uglify-js|3.13.4|3.14.3|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|5.7.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|yup|0.27.0|0.30.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|lodash.template|4.5.0||间接依赖|可选修复|C:0|H:1|M:0|L:0|
|semver|6.3.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|yargs-parser|10.1.0|18.1.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|7.3.5|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|marked|2.0.3|4.0.10|间接依赖|可选修复|C:0|H:2|M:0|L:0|
|istanbul-reports|3.0.2|3.1.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|conventional-commits-parser|3.2.1|3.2.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|nanoid|3.1.20|3.1.31|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|moment|2.29.1|2.29.4|直接依赖|可选修复|C:0|H:1|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|692|Low|
|ISC|147|Low|
|BSD-3-Clause|30|Low|
|Apache-2.0|17|Low|
|BSD-2-Clause|23|Low|
|APACHE-2.0|1|Low|
|CC-BY-4.0|1|Low|
|CC0-1.0|1|Low|
|Artistic-2.0|1|Low|
|0BSD|1|Low|
|Python-2.0|1|Low|
|Unlicense|1|Low|
|CC-BY-3.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|astral-regex|2.0.0|间接依赖|npm|
|marked-terminal|4.1.1|间接依赖|npm|
|bottleneck|2.19.5|间接依赖|npm|
|handlebars|4.7.7|间接依赖|npm|
|listr-verbose-renderer|0.5.0|间接依赖|npm|
|nopt|5.0.0|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|@npmcli/node-gyp|1.0.2|间接依赖|npm|
|@babel/core|7.13.15|间接依赖|npm|
|@npmcli/move-file|1.1.2|间接依赖|npm|
|lodash.isstring|4.0.1|间接依赖|npm|
|which-module|2.0.0|间接依赖|npm|
|is-string|1.0.5|间接依赖|npm|
|strip-bom|3.0.0|间接依赖|npm|
|is-plain-obj|1.1.0|间接依赖|npm|
|resolve|1.20.0|间接依赖|npm|
|globby|11.0.3|间接依赖|npm|
|simple-git|1.132.0|间接依赖|npm|
|end-of-stream|1.4.4|间接依赖|npm|
|lru-cache|6.0.0|间接依赖|npm|
|array-from|2.1.1|间接依赖|npm|
|sprintf-js|1.0.3|间接依赖|npm|
|uuid|3.4.0|间接依赖|npm|
|array-union|2.1.0|间接依赖|npm|
|type-check|0.3.2|间接依赖|npm|
|istanbul-lib-processinfo|2.0.2|间接依赖|npm|
|read-pkg|3.0.0|间接依赖|npm|
|chalk|1.1.3|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|@octokit/plugin-request-log|1.0.3|间接依赖|npm|
|extsprintf|1.4.0|间接依赖|npm|
|lodash.escaperegexp|4.1.2|间接依赖|npm|
|ramda|0.27.1|间接依赖|npm|
|normalize-url|6.0.0|间接依赖|npm|
|map-cache|0.2.2|间接依赖|npm|
|@eslint/eslintrc|0.4.0|间接依赖|npm|
|find-up|2.1.0|间接依赖|npm|
|mime|2.5.2|间接依赖|npm|
|@types/retry|0.12.0|间接依赖|npm|
|istanbul-lib-source-maps|4.0.0|间接依赖|npm|
|semver|7.5.2|直接依赖|npm|
|iconv-lite|0.6.2|间接依赖|npm|
|figures|2.0.0|间接依赖|npm|
|@commitlint/ensure|7.6.0|间接依赖|npm|
|get-func-name|2.0.0|间接依赖|npm|
|strip-ansi|4.0.0|间接依赖|npm|
|lolex|5.1.2|间接依赖|npm|
|@types/parse-json|4.0.0|间接依赖|npm|
|yallist|4.0.0|间接依赖|npm|
|slash|3.0.0|间接依赖|npm|
|is-glob|4.0.1|间接依赖|npm|
|ansi-styles|4.3.0|间接依赖|npm|
|split-string|3.1.0|间接依赖|npm|
|@commitlint/cli|7.6.1|直接依赖|npm|
|is-accessor-descriptor|0.1.6|间接依赖|npm|
|node-fetch|2.6.7|间接依赖|npm|
|promise-all-reject-late|1.0.1|间接依赖|npm|
|unset-value|1.0.0|间接依赖|npm|
|write-file-atomic|3.0.3|间接依赖|npm|
|har-schema|2.0.0|间接依赖|npm|
|chalk|2.3.1|间接依赖|npm|
|flat|5.0.2|间接依赖|npm|
|resolve-url|0.2.1|间接依赖|npm|
|listr-silent-renderer|1.1.1|间接依赖|npm|
|path-to-regexp|1.8.0|间接依赖|npm|
|cosmiconfig|5.2.1|间接依赖|npm|
|path-exists|3.0.0|间接依赖|npm|
|delegates|1.0.0|间接依赖|npm|
|@npmcli/ci-detect|1.3.0|间接依赖|npm|
|before-after-hook|2.2.1|间接依赖|npm|
|getpass|0.1.7|间接依赖|npm|
|libnpmhook|6.0.2|间接依赖|npm|
|snapdragon-node|2.1.1|间接依赖|npm|
|dashdash|1.14.1|间接依赖|npm|
|pify|3.0.0|间接依赖|npm|
|slice-ansi|0.0.4|间接依赖|npm|
|to-regex-range|2.1.1|间接依赖|npm|
|globals|13.8.0|间接依赖|npm|
|assertion-error|1.1.0|间接依赖|npm|
|wrap-ansi|3.0.1|间接依赖|npm|
|camelcase-keys|4.2.0|间接依赖|npm|
|functional-red-black-tree|1.0.1|间接依赖|npm|
|git-log-parser|1.2.0|间接依赖|npm|
|enquirer|2.3.6|间接依赖|npm|
|readable-stream|3.6.0|间接依赖|npm|
|abbrev|1.0.9|间接依赖|npm|
|is-path-cwd|1.0.0|间接依赖|npm|
|optionator|0.9.1|间接依赖|npm|
|uglify-js|3.13.4|直接依赖|npm|
|npm-audit-report|2.1.4|间接依赖|npm|
|ms|2.0.0|间接依赖|npm|
|string_decoder|1.1.1|间接依赖|npm|
|read-package-json|3.0.1|间接依赖|npm|
|conventional-changelog-angular|1.6.6|间接依赖|npm|
|loud-rejection|1.6.0|间接依赖|npm|
|execa|4.1.0|间接依赖|npm|
|snapdragon|0.8.2|间接依赖|npm|
|aproba|1.2.0|间接依赖|npm|
|type-check|0.4.0|间接依赖|npm|
|babel-polyfill|6.26.0|间接依赖|npm|
|nice-try|1.0.5|间接依赖|npm|
|json-schema|0.2.3|间接依赖|npm|
|to-object-path|0.3.0|间接依赖|npm|
|cli-columns|3.1.2|间接依赖|npm|
|cluster-key-slot|1.1.0|间接依赖|npm|
|@babel/helper-member-expression-to-functions|7.13.12|间接依赖|npm|
|@nodelib/fs.scandir|2.1.4|间接依赖|npm|
|growl|1.10.5|间接依赖|npm|
|extend-shallow|2.0.1|间接依赖|npm|
|tar|6.1.6|间接依赖|npm|
|process-nextick-args|2.0.1|间接依赖|npm|
|wcwidth|1.0.1|间接依赖|npm|
|js-yaml|3.14.1|间接依赖|npm|
|p-finally|1.0.0|间接依赖|npm|
|camelcase|6.2.0|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|jsonfile|6.1.0|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|is-number-object|1.0.4|间接依赖|npm|
|sinon|7.5.0|直接依赖|npm|
|p-each-series|2.2.0|间接依赖|npm|
|aggregate-error|3.1.0|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|just-diff-apply|3.0.0|间接依赖|npm|
|semver|7.3.5|间接依赖|npm|
|type-fest|0.20.2|间接依赖|npm|
|cli-truncate|0.2.1|间接依赖|npm|
|ip-regex|4.3.0|间接依赖|npm|
|assert-plus|1.0.0|间接依赖|npm|
|diff|5.0.0|间接依赖|npm|
|ansi-regex|3.0.0|间接依赖|npm|
|p-limit|2.3.0|间接依赖|npm|
|eslint|7.24.0|直接依赖|npm|
|micromatch|4.0.4|间接依赖|npm|
|temp-dir|2.0.0|间接依赖|npm|
|@octokit/auth-token|2.4.5|间接依赖|npm|
|opener|1.5.2|间接依赖|npm|
|make-fetch-happen|8.0.14|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|compare-func|2.0.0|间接依赖|npm|
|@npmcli/config|2.1.0|间接依赖|npm|
|pathval|1.1.1|间接依赖|npm|
|supports-color|8.1.1|间接依赖|npm|
|is-windows|1.0.2|间接依赖|npm|
|shebang-regex|1.0.0|间接依赖|npm|
|nanoid|3.1.20|间接依赖|npm|
|pkg-dir|5.0.0|间接依赖|npm|
|table|6.2.0|间接依赖|npm|
|release-zalgo|1.0.0|间接依赖|npm|
|promise-call-limit|1.0.1|间接依赖|npm|
|fs-extra|9.1.0|间接依赖|npm|
|into-stream|6.0.0|间接依赖|npm|
|p-filter|2.1.0|间接依赖|npm|
|p-map|1.2.0|间接依赖|npm|
|url-join|4.0.1|间接依赖|npm|
|lodash.uniqby|4.7.0|间接依赖|npm|
|through|2.3.8|间接依赖|npm|
|@babel/helper-get-function-arity|7.12.13|间接依赖|npm|
|rimraf|3.0.2|间接依赖|npm|
|prelude-ls|1.2.1|间接依赖|npm|
|read-package-json-fast|2.0.2|间接依赖|npm|
|camelcase-keys|6.2.2|间接依赖|npm|
|asynckit|0.4.0|间接依赖|npm|
|@npmcli/git|2.0.8|间接依赖|npm|
|del|6.0.0|间接依赖|npm|
|npm-package-arg|8.1.2|间接依赖|npm|
|@babel/highlight|7.13.10|间接依赖|npm|
|@sinonjs/samsam|3.3.3|间接依赖|npm|
|kind-of|5.1.0|间接依赖|npm|
|globals|12.4.0|间接依赖|npm|
|is-binary-path|2.1.0|间接依赖|npm|
|async|1.5.2|间接依赖|npm|
|path-type|4.0.0|间接依赖|npm|
|wrap-ansi|7.0.0|间接依赖|npm|
|arrify|1.0.1|间接依赖|npm|
|regenerator-runtime|0.11.1|间接依赖|npm|
|p-retry|4.5.0|间接依赖|npm|
|npm-normalize-package-bin|1.0.1|间接依赖|npm|
|are-we-there-yet|1.1.5|间接依赖|npm|
|coveralls|3.1.0|直接依赖|npm|
|@npmcli/map-workspaces|1.0.3|间接依赖|npm|
|ansi-colors|4.1.1|间接依赖|npm|
|debuglog|1.0.1|间接依赖|npm|
|use|3.1.1|间接依赖|npm|
|@octokit/rest|18.5.3|间接依赖|npm|
|@commitlint/parse|7.6.0|间接依赖|npm|
|@octokit/graphql|4.6.1|间接依赖|npm|
|which|1.3.1|间接依赖|npm|
|type-fest|0.8.1|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|typedarray-to-buffer|3.1.5|间接依赖|npm|
|shebang-regex|3.0.0|间接依赖|npm|
|istanbul-lib-report|3.0.0|间接依赖|npm|
|signale|1.4.0|间接依赖|npm|
|@babel/types|7.13.14|间接依赖|npm|
|array-uniq|1.0.3|间接依赖|npm|
|minimatch|3.0.4|间接依赖|npm|
|tempy|1.0.1|间接依赖|npm|
|callsites|2.0.0|间接依赖|npm|
|map-obj|1.0.1|间接依赖|npm|
|path-key|3.1.1|间接依赖|npm|
|yargs-unparser|2.0.0|间接依赖|npm|
|validate-npm-package-name|3.0.0|间接依赖|npm|
|binary-extensions|2.2.0|间接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|require-from-string|2.0.2|间接依赖|npm|
|v8-compile-cache|2.3.0|间接依赖|npm|
|p-reflect|1.0.0|直接依赖|npm|
|husky|4.3.8|直接依赖|npm|
|ip|1.1.5|间接依赖|npm|
|mime-db|1.47.0|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|define-property|1.0.0|间接依赖|npm|
|is-fullwidth-code-point|2.0.0|间接依赖|npm|
|json-stringify-nice|1.1.3|间接依赖|npm|
|promise-inflight|1.0.1|间接依赖|npm|
|lodash.isarguments|3.1.0|间接依赖|npm|
|npm-run-path|4.0.1|间接依赖|npm|
|isarray|1.0.0|间接依赖|npm|
|minipass-sized|1.0.3|间接依赖|npm|
|ansicolors|0.3.2|间接依赖|npm|
|lodash.defaults|4.2.0|间接依赖|npm|
|assign-symbols|1.0.0|间接依赖|npm|
|@ungap/promise-all-settled|1.1.2|间接依赖|npm|
|cacache|15.0.6|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|hosted-git-info|4.0.2|间接依赖|npm|
|unique-filename|1.1.1|间接依赖|npm|
|isobject|3.0.1|间接依赖|npm|
|array-union|1.0.2|间接依赖|npm|
|hasha|5.2.2|间接依赖|npm|
|istanbul-lib-coverage|3.0.0|间接依赖|npm|
|g-status|2.0.2|间接依赖|npm|
|socks|2.6.1|间接依赖|npm|
|array-unique|0.3.2|间接依赖|npm|
|del|3.0.0|间接依赖|npm|
|test-exclude|6.0.0|间接依赖|npm|
|eslint-utils|1.4.3|间接依赖|npm|
|meow|5.0.0|间接依赖|npm|
|from2|2.3.0|间接依赖|npm|
|socks-proxy-agent|5.0.0|间接依赖|npm|
|fragment-cache|0.2.1|间接依赖|npm|
|date-fns|1.30.1|间接依赖|npm|
|split2|2.2.0|间接依赖|npm|
|eslint-visitor-keys|2.0.0|间接依赖|npm|
|crypto-random-string|2.0.0|间接依赖|npm|
|to-fast-properties|2.0.0|间接依赖|npm|
|escape-string-regexp|4.0.0|间接依赖|npm|
|http-proxy-agent|4.0.1|间接依赖|npm|
|npm-run-path|2.0.2|间接依赖|npm|
|caller-callsite|2.0.0|间接依赖|npm|
|lodash.ismatch|4.4.0|间接依赖|npm|
|qs|6.5.2|间接依赖|npm|
|string-width|4.2.2|间接依赖|npm|
|type-fest|0.6.0|间接依赖|npm|
|indent-string|3.2.0|间接依赖|npm|
|abbrev|1.1.1|间接依赖|npm|
|strip-final-newline|2.0.0|间接依赖|npm|
|@babel/helper-replace-supers|7.13.12|间接依赖|npm|
|chalk|4.1.1|间接依赖|npm|
|eslint-visitor-keys|1.3.0|间接依赖|npm|
|fast-glob|3.2.5|间接依赖|npm|
|pinkie-promise|2.0.1|间接依赖|npm|
|@babel/helper-validator-option|7.12.17|间接依赖|npm|
|redeyed|2.1.1|间接依赖|npm|
|argparse|1.0.10|间接依赖|npm|
|libnpmversion|1.2.0|间接依赖|npm|
|object.pick|1.3.0|间接依赖|npm|
|tough-cookie|2.5.0|间接依赖|npm|
|estraverse|1.9.3|间接依赖|npm|
|readdir-scoped-modules|1.1.0|间接依赖|npm|
|eslint-utils|2.1.0|间接依赖|npm|
|p-map|2.1.0|间接依赖|npm|
|is-path-inside|3.0.3|间接依赖|npm|
|he|1.2.0|间接依赖|npm|
|import-fresh|3.3.0|间接依赖|npm|
|doctrine|3.0.0|间接依赖|npm|
|resolve-from|3.0.0|间接依赖|npm|
|mkdirp|1.0.4|间接依赖|npm|
|wordwrap|1.0.0|间接依赖|npm|
|parent-module|1.0.1|间接依赖|npm|
|retry|0.12.0|间接依赖|npm|
|npm-bundled|1.1.2|间接依赖|npm|
|human-signals|2.1.0|间接依赖|npm|
|decode-uri-component|0.2.0|间接依赖|npm|
|p-reduce|2.1.0|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|ssri|8.0.1|间接依赖|npm|
|delayed-stream|1.0.0|间接依赖|npm|
|trim-newlines|2.0.0|间接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|path-is-inside|1.0.2|间接依赖|npm|
|@babel/code-frame|7.12.13|间接依赖|npm|
|wrap-ansi|6.2.0|间接依赖|npm|
|number-is-nan|1.0.1|间接依赖|npm|
|eslint-plugin-es|1.4.1|间接依赖|npm|
|camelcase|4.1.0|间接依赖|npm|
|dargs|4.1.0|间接依赖|npm|
|@sinonjs/commons|1.8.3|间接依赖|npm|
|resolve-global|1.0.0|间接依赖|npm|
|is-number|3.0.0|间接依赖|npm|
|restore-cursor|2.0.0|间接依赖|npm|
|@semantic-release/release-notes-generator|9.0.2|直接依赖|npm|
|p-locate|5.0.0|间接依赖|npm|
|aws-sign2|0.7.0|间接依赖|npm|
|columnify|1.5.4|间接依赖|npm|
|istanbul-reports|3.0.2|间接依赖|npm|
|ignore|4.0.6|间接依赖|npm|
|slice-ansi|4.0.0|间接依赖|npm|
|yargs-parser|18.1.3|间接依赖|npm|
|dot-prop|5.3.0|间接依赖|npm|
|yaml|1.10.2|间接依赖|npm|
|punycode|2.1.1|间接依赖|npm|
|globby|6.1.0|间接依赖|npm|
|through2|2.0.5|间接依赖|npm|
|commondir|1.0.1|间接依赖|npm|
|is-directory|0.3.1|间接依赖|npm|
|human-signals|1.1.1|间接依赖|npm|
|cross-spawn|7.0.3|间接依赖|npm|
|extend-shallow|3.0.2|间接依赖|npm|
|component-emitter|1.3.0|间接依赖|npm|
|define-property|0.2.5|间接依赖|npm|
|supports-hyperlinks|2.2.0|间接依赖|npm|
|is-boolean-object|1.1.0|间接依赖|npm|
|browserslist|4.16.4|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|log-symbols|1.0.2|间接依赖|npm|
|mimic-fn|2.1.0|间接依赖|npm|
|source-map-resolve|0.5.3|间接依赖|npm|
|global-dirs|0.1.1|间接依赖|npm|
|sshpk|1.16.1|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|stringify-package|1.0.1|间接依赖|npm|
|colors|1.4.0|直接依赖|npm|
|@commitlint/load|7.6.2|间接依赖|npm|
|eslint-plugin-node|8.0.1|直接依赖|npm|
|p-limit|3.1.0|间接依赖|npm|
|caniuse-lite|1.0.30001211|间接依赖|npm|
|denque|2.1.0|间接依赖|npm|
|libnpmpack|2.0.1|间接依赖|npm|
|listr-update-renderer|0.5.0|间接依赖|npm|
|hook-std|2.0.0|间接依赖|npm|
|@babel/helper-compilation-targets|7.13.13|间接依赖|npm|
|istanbul|0.4.5|直接依赖|npm|
|@octokit/core|3.4.0|间接依赖|npm|
|minipass-fetch|1.3.3|间接依赖|npm|
|conventional-commits-parser|3.2.1|间接依赖|npm|
|@commitlint/format|7.6.1|间接依赖|npm|
|prettier|1.19.1|直接依赖|npm|
|cli-table3|0.6.0|间接依赖|npm|
|agentkeepalive|4.1.4|间接依赖|npm|
|error-ex|1.3.2|间接依赖|npm|
|locate-path|2.0.0|间接依赖|npm|
|decamelize|4.0.0|间接依赖|npm|
|npm-profile|5.0.3|间接依赖|npm|
|yargs-parser|20.2.7|间接依赖|npm|
|lodash.flattendeep|4.4.0|间接依赖|npm|
|deep-eql|3.0.1|间接依赖|npm|
|aws4|1.11.0|间接依赖|npm|
|source-map|0.5.7|间接依赖|npm|
|p-is-promise|3.0.0|间接依赖|npm|
|get-package-type|0.1.0|间接依赖|npm|
|get-own-enumerable-property-symbols|3.0.2|间接依赖|npm|
|spdx-license-ids|3.0.7|间接依赖|npm|
|@babel/helper-function-name|7.12.13|间接依赖|npm|
|arr-flatten|1.1.0|间接依赖|npm|
|dedent|0.7.0|间接依赖|npm|
|snapdragon-util|3.0.1|间接依赖|npm|
|semver-diff|3.1.1|间接依赖|npm|
|pinkie|2.0.4|间接依赖|npm|
|whatwg-url|5.0.0|间接依赖|npm|
|opencollective-postinstall|2.0.3|间接依赖|npm|
|@babel/compat-data|7.13.15|间接依赖|npm|
|colors|1.0.3|间接依赖|npm|
|has-symbols|1.0.2|间接依赖|npm|
|indent-string|4.0.0|间接依赖|npm|
|@npmcli/metavuln-calculator|1.1.1|间接依赖|npm|
|npm|7.11.0|间接依赖|npm|
|array-find-index|1.0.2|间接依赖|npm|
|extend|3.0.2|间接依赖|npm|
|moment|2.29.1|直接依赖|npm|
|fs-minipass|2.1.0|间接依赖|npm|
|tunnel-agent|0.6.0|间接依赖|npm|
|diff|3.5.0|间接依赖|npm|
|init-package-json|2.0.3|间接依赖|npm|
|read-pkg-up|7.0.1|间接依赖|npm|
|jsonparse|1.3.1|间接依赖|npm|
|debug|4.3.1|间接依赖|npm|
|please-upgrade-node|3.2.0|间接依赖|npm|
|node-emoji|1.10.0|间接依赖|npm|
|synchronous-promise|2.0.15|间接依赖|npm|
|@nodelib/fs.stat|2.0.4|间接依赖|npm|
|at-least-node|1.0.0|间接依赖|npm|
|conventional-changelog-writer|4.1.0|间接依赖|npm|
|minimist-options|4.1.0|间接依赖|npm|
|supports-color|7.2.0|间接依赖|npm|
|repeat-element|1.1.4|间接依赖|npm|
|type-fest|0.21.3|间接依赖|npm|
|form-data|2.3.3|间接依赖|npm|
|minimist|1.2.5|间接依赖|npm|
|semver|5.7.1|间接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|@babel/helpers|7.13.10|间接依赖|npm|
|y18n|4.0.3|间接依赖|npm|
|nerf-dart|1.0.0|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|@commitlint/config-conventional|7.6.0|直接依赖|npm|
|debug|4.3.4|间接依赖|npm|
|map-obj|4.2.1|间接依赖|npm|
|npm-path|2.0.4|间接依赖|npm|
|symbol-observable|1.2.0|间接依赖|npm|
|ignore-walk|3.0.3|间接依赖|npm|
|source-map|0.6.1|间接依赖|npm|
|class-utils|0.3.6|间接依赖|npm|
|urix|0.1.0|间接依赖|npm|
|cli-cursor|2.1.0|间接依赖|npm|
|delay|4.4.1|直接依赖|npm|
|@octokit/types|6.13.1|间接依赖|npm|
|currently-unhandled|0.4.1|间接依赖|npm|
|which|2.0.2|间接依赖|npm|
|lodash._reinterpolate|3.0.0|间接依赖|npm|
|spdx-correct|3.1.1|间接依赖|npm|
|@commitlint/rules|7.6.0|间接依赖|npm|
|istanbul-lib-instrument|4.0.3|间接依赖|npm|
|just-extend|4.2.1|间接依赖|npm|
|eslint-plugin-mocha|7.0.1|直接依赖|npm|
|parse-json|4.0.0|间接依赖|npm|
|nanomatch|1.2.13|间接依赖|npm|
|strip-indent|3.0.0|间接依赖|npm|
|rxjs|6.6.7|间接依赖|npm|
|@commitlint/is-ignored|7.6.0|间接依赖|npm|
|deep-extend|0.6.0|间接依赖|npm|
|jsprim|1.4.1|间接依赖|npm|
|is-text-path|1.0.1|间接依赖|npm|
|gauge|2.7.4|间接依赖|npm|
|min-indent|1.0.1|间接依赖|npm|
|word-wrap|1.2.3|间接依赖|npm|
|mime-types|2.1.30|间接依赖|npm|
|ms|2.1.3|间接依赖|npm|
|property-expr|1.5.1|间接依赖|npm|
|es6-error|4.1.1|间接依赖|npm|
|cache-base|1.0.1|间接依赖|npm|
|standard-as-callback|2.1.0|间接依赖|npm|
|ansi-regex|2.1.1|间接依赖|npm|
|ansi-escapes|3.2.0|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|tslib|1.14.1|间接依赖|npm|
|redent|2.0.0|间接依赖|npm|
|@ioredis/commands|1.2.0|间接依赖|npm|
|marked|2.0.3|间接依赖|npm|
|@types/normalize-package-data|2.4.0|间接依赖|npm|
|core-util-is|1.0.2|间接依赖|npm|
|elegant-spinner|1.0.1|间接依赖|npm|
|cardinal|2.1.1|间接依赖|npm|
|ajv|8.1.0|间接依赖|npm|
|mocha|8.3.2|直接依赖|npm|
|flatted|3.1.1|间接依赖|npm|
|acorn-jsx|5.3.1|间接依赖|npm|
|lines-and-columns|1.1.6|间接依赖|npm|
|find-up|5.0.0|间接依赖|npm|
|node-gyp-build|4.3.0|间接依赖|npm|
|libnpmsearch|3.1.1|间接依赖|npm|
|estraverse|5.2.0|间接依赖|npm|
|strip-ansi|6.0.0|间接依赖|npm|
|levn|0.3.0|间接依赖|npm|
|randombytes|2.1.0|间接依赖|npm|
|extglob|2.0.4|间接依赖|npm|
|get-value|2.0.6|间接依赖|npm|
|yargs-parser|10.1.0|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|has-flag|4.0.0|间接依赖|npm|
|stringify-object|3.3.0|间接依赖|npm|
|msgpackr-extract|1.0.16|直接依赖|npm|
|isarray|0.0.1|间接依赖|npm|
|luxon|1.28.0|间接依赖|npm|
|redis-parser|3.0.0|间接依赖|npm|
|@babel/helper-module-transforms|7.13.14|间接依赖|npm|
|yargs|15.4.1|间接依赖|npm|
|ignore|5.1.8|间接依赖|npm|
|deep-is|0.1.3|间接依赖|npm|
|@semantic-release/github|7.2.1|直接依赖|npm|
|env-paths|2.2.1|间接依赖|npm|
|log-symbols|4.0.0|间接依赖|npm|
|append-transform|2.0.0|间接依赖|npm|
|yargs-parser|20.2.4|间接依赖|npm|
|is-plain-obj|2.1.0|间接依赖|npm|
|q|1.5.1|间接依赖|npm|
|lodash.toarray|4.4.0|间接依赖|npm|
|lolex|4.2.0|间接依赖|npm|
|read-pkg|5.2.0|间接依赖|npm|
|@octokit/openapi-types|6.1.0|间接依赖|npm|
|resolve-from|5.0.0|间接依赖|npm|
|@commitlint/read|7.6.0|间接依赖|npm|
|json-schema-traverse|1.0.0|间接依赖|npm|
|lodash.clonedeep|4.5.0|间接依赖|npm|
|execa|1.0.0|间接依赖|npm|
|collection-visit|1.0.0|间接依赖|npm|
|electron-to-chromium|1.3.717|间接依赖|npm|
|npm-user-validate|1.0.1|间接依赖|npm|
|signal-exit|3.0.3|间接依赖|npm|
|which-pm-runs|1.0.0|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|import-fresh|2.0.0|间接依赖|npm|
|figures|1.7.0|间接依赖|npm|
|lodash|4.17.11|间接依赖|npm|
|type-fest|0.18.1|间接依赖|npm|
|cliui|6.0.0|间接依赖|npm|
|braces|2.3.2|间接依赖|npm|
|set-value|2.0.1|间接依赖|npm|
|repeat-string|1.6.1|间接依赖|npm|
|cliui|7.0.4|间接依赖|npm|
|atob|2.1.2|间接依赖|npm|
|regenerator-runtime|0.13.7|间接依赖|npm|
|fromentries|1.3.2|间接依赖|npm|
|json-parse-better-errors|1.0.2|间接依赖|npm|
|is-regexp|1.0.0|间接依赖|npm|
|cmd-shim|4.1.0|间接依赖|npm|
|validate-npm-package-license|3.0.4|间接依赖|npm|
|libnpmpublish|4.0.1|间接依赖|npm|
|npm-pick-manifest|6.1.1|间接依赖|npm|
|resolve-from|4.0.0|间接依赖|npm|
|msgpackr|1.5.2|直接依赖|npm|
|safe-buffer|5.2.1|间接依赖|npm|
|union-value|1.0.1|间接依赖|npm|
|read-cmd-shim|2.0.0|间接依赖|npm|
|eslint-scope|5.1.1|间接依赖|npm|
|to-regex|3.0.2|间接依赖|npm|
|npm-packlist|2.1.5|间接依赖|npm|
|chokidar|3.5.1|间接依赖|npm|
|wide-align|1.1.3|间接依赖|npm|
|gensync|1.0.0-beta.2|间接依赖|npm|
|@commitlint/to-lines|7.6.0|间接依赖|npm|
|leven|3.1.0|间接依赖|npm|
|dot-prop|3.0.0|间接依赖|npm|
|nise|1.5.3|间接依赖|npm|
|@babel/helper-validator-identifier|7.12.11|间接依赖|npm|
|@commitlint/message|7.6.0|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|@commitlint/resolve-extends|7.6.0|间接依赖|npm|
|is-stream|1.1.0|间接依赖|npm|
|libnpmfund|1.0.2|间接依赖|npm|
|get-stream|6.0.1|间接依赖|npm|
|builtins|1.0.3|间接依赖|npm|
|package-hash|4.0.0|间接依赖|npm|
|commander|2.20.3|间接依赖|npm|
|conventional-commits-filter|2.0.7|间接依赖|npm|
|walk-up-path|1.0.0|间接依赖|npm|
|code-point-at|1.1.0|间接依赖|npm|
|libnpmexec|1.0.1|间接依赖|npm|
|matcher|1.1.1|间接依赖|npm|
|is-typedarray|1.0.0|间接依赖|npm|
|is-plain-object|5.0.0|间接依赖|npm|
|lodash.truncate|4.4.2|间接依赖|npm|
|glob|7.1.6|间接依赖|npm|
|console-control-strings|1.1.0|间接依赖|npm|
|shebang-command|1.2.0|间接依赖|npm|
|json-stable-stringify-without-jsonify|1.0.1|间接依赖|npm|
|ioredis|5.3.2|直接依赖|npm|
|prelude-ls|1.1.2|间接依赖|npm|
|emoji-regex|8.0.0|间接依赖|npm|
|expand-brackets|2.1.4|间接依赖|npm|
|amdefine|1.0.1|间接依赖|npm|
|merge-stream|2.0.0|间接依赖|npm|
|http-cache-semantics|4.1.1|间接依赖|npm|
|has-value|1.0.0|间接依赖|npm|
|supports-color|2.0.0|间接依赖|npm|
|oauth-sign|0.9.0|间接依赖|npm|
|esprima|4.0.1|间接依赖|npm|
|set-blocking|2.0.0|间接依赖|npm|
|@samverschueren/stream-to-observable|0.3.1|间接依赖|npm|
|json5|2.2.0|间接依赖|npm|
|conventional-changelog-angular|5.0.12|间接依赖|npm|
|is-cidr|4.0.2|间接依赖|npm|
|text-extensions|1.9.0|间接依赖|npm|
|npmlog|4.1.2|间接依赖|npm|
|err-code|2.0.3|间接依赖|npm|
|progress|2.0.3|间接依赖|npm|
|cli-table|0.3.6|间接依赖|npm|
|neo-async|2.6.2|间接依赖|npm|
|yup|0.27.0|间接依赖|npm|
|is-arrayish|0.2.1|间接依赖|npm|
|trim-off-newlines|1.0.3|间接依赖|npm|
|is-descriptor|0.1.6|间接依赖|npm|
|merge2|1.4.1|间接依赖|npm|
|log-update|2.3.0|间接依赖|npm|
|lint-staged|8.2.1|直接依赖|npm|
|esquery|1.4.0|间接依赖|npm|
|universal-user-agent|6.0.0|间接依赖|npm|
|@octokit/request|5.4.15|间接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|ini|1.3.8|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|figures|3.2.0|间接依赖|npm|
|byte-size|7.0.1|间接依赖|npm|
|color-convert|2.0.1|间接依赖|npm|
|stream-combiner2|1.1.1|间接依赖|npm|
|is-promise|2.2.2|间接依赖|npm|
|@babel/traverse|7.13.15|间接依赖|npm|
|p-map|4.0.0|间接依赖|npm|
|split2|3.2.2|间接依赖|npm|
|supports-color|3.2.3|间接依赖|npm|
|staged-git-files|1.1.2|间接依赖|npm|
|npm-install-checks|4.0.0|间接依赖|npm|
|fsevents|2.3.2|直接依赖|npm|
|compare-versions|3.6.0|间接依赖|npm|
|string-argv|0.0.2|间接依赖|npm|
|@semantic-release/error|2.2.0|间接依赖|npm|
|imurmurhash|0.1.4|间接依赖|npm|
|read|1.0.7|间接依赖|npm|
|static-extend|0.1.2|间接依赖|npm|
|is-data-descriptor|0.1.4|间接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|dir-glob|3.0.1|间接依赖|npm|
|@babel/helper-simple-access|7.13.12|间接依赖|npm|
|@babel/code-frame|7.12.11|间接依赖|npm|
|get-stream|4.1.0|间接依赖|npm|
|cidr-regex|3.1.1|间接依赖|npm|
|npm-which|3.0.1|间接依赖|npm|
|is-fullwidth-code-point|1.0.0|间接依赖|npm|
|onetime|2.0.1|间接依赖|npm|
|process-on-spawn|1.0.0|间接依赖|npm|
|map-obj|2.0.0|间接依赖|npm|
|jsesc|2.5.2|间接依赖|npm|
|decamelize|1.2.0|间接依赖|npm|
|tiny-relative-date|1.3.0|间接依赖|npm|
|is-extendable|0.1.1|间接依赖|npm|
|find-cache-dir|3.3.1|间接依赖|npm|
|is-descriptor|1.0.2|间接依赖|npm|
|encoding|0.1.13|直接依赖|npm|
|has-ansi|2.0.0|间接依赖|npm|
|glob-parent|5.1.2|间接依赖|npm|
|listr|0.14.3|间接依赖|npm|
|@octokit/request-error|2.0.5|间接依赖|npm|
|@babel/template|7.12.13|间接依赖|npm|
|nan|2.15.0|间接依赖|npm|
|@semantic-release/npm|7.1.1|直接依赖|npm|
|strip-bom|4.0.0|间接依赖|npm|
|request|2.88.2|间接依赖|npm|
|is-number|7.0.0|间接依赖|npm|
|get-stream|5.2.0|间接依赖|npm|
|debug|2.6.9|间接依赖|npm|
|fast-levenshtein|2.0.6|间接依赖|npm|
|regexpp|2.0.1|间接依赖|npm|
|callsites|3.1.0|间接依赖|npm|
|trim-newlines|3.0.0|间接依赖|npm|
|split2|1.0.0|间接依赖|npm|
|@npmcli/run-script|1.8.5|间接依赖|npm|
|@octokit/endpoint|6.0.11|间接依赖|npm|
|expect.js|0.3.1|直接依赖|npm|
|camelcase|5.3.1|间接依赖|npm|
|call-bind|1.0.2|间接依赖|npm|
|semver|6.3.0|间接依赖|npm|
|pify|2.3.0|间接依赖|npm|
|dezalgo|1.0.3|间接依赖|npm|
|find-up|4.1.0|间接依赖|npm|
|arr-diff|4.0.0|间接依赖|npm|
|path-exists|4.0.0|间接依赖|npm|
|load-json-file|4.0.0|间接依赖|npm|
|posix-character-classes|0.1.1|间接依赖|npm|
|p-locate|4.1.0|间接依赖|npm|
|ansi-styles|2.2.1|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|base|0.11.2|间接依赖|npm|
|istanbul-lib-hook|3.0.0|间接依赖|npm|
|fill-range|4.0.0|间接依赖|npm|
|pump|3.0.0|间接依赖|npm|
|any-observable|0.3.0|间接依赖|npm|
|node-gyp|7.1.2|间接依赖|npm|
|@babel/helper-split-export-declaration|7.12.13|间接依赖|npm|
|@npmcli/installed-package-contents|1.0.7|间接依赖|npm|
|pkg-conf|2.1.0|间接依赖|npm|
|spawn-error-forwarder|1.0.0|间接依赖|npm|
|convert-source-map|1.7.0|间接依赖|npm|
|file-entry-cache|6.0.1|间接依赖|npm|
|semver-compare|1.0.0|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|strip-indent|2.0.0|间接依赖|npm|
|dateformat|3.0.3|间接依赖|npm|
|@babel/helper-optimise-call-expression|7.12.13|间接依赖|npm|
|chownr|2.0.0|间接依赖|npm|
|@istanbuljs/schema|0.1.3|间接依赖|npm|
|p-map|3.0.0|间接依赖|npm|
|lodash.flatten|4.4.0|间接依赖|npm|
|is-obj|1.0.1|间接依赖|npm|
|string-width|2.1.1|间接依赖|npm|
|is-path-inside|1.0.1|间接依赖|npm|
|kind-of|6.0.3|间接依赖|npm|
|ansistyles|0.1.3|间接依赖|npm|
|define-property|2.0.2|间接依赖|npm|
|libnpmorg|2.0.2|间接依赖|npm|
|@commitlint/top-level|7.6.0|间接依赖|npm|
|clone|1.0.4|间接依赖|npm|
|@babel/generator|7.13.9|间接依赖|npm|
|esutils|2.0.3|间接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|strip-ansi|3.0.1|间接依赖|npm|
|chai|4.3.4|直接依赖|npm|
|semantic-release|17.4.2|直接依赖|npm|
|decamelize-keys|1.1.0|间接依赖|npm|
|compare-func|1.3.4|间接依赖|npm|
|@types/minimist|1.2.1|间接依赖|npm|
|import-from|3.0.0|间接依赖|npm|
|anymatch|3.1.2|间接依赖|npm|
|shebang-command|2.0.0|间接依赖|npm|
|universalify|2.0.0|间接依赖|npm|
|ajv|6.12.6|间接依赖|npm|
|natural-compare|1.4.0|间接依赖|npm|
|estraverse|4.3.0|间接依赖|npm|
|p-locate|2.0.0|间接依赖|npm|
|lodash.template|4.5.0|间接依赖|npm|
|esprima|2.7.3|间接依赖|npm|
|chalk|4.1.0|间接依赖|npm|
|@octokit/plugin-paginate-rest|2.13.3|间接依赖|npm|
|is-plain-object|2.0.4|间接依赖|npm|
|browser-stdout|1.3.1|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|node-preload|0.2.1|间接依赖|npm|
|@semantic-release/commit-analyzer|8.0.1|直接依赖|npm|
|argparse|2.0.1|间接依赖|npm|
|strip-eof|1.0.0|间接依赖|npm|
|is-extendable|1.0.1|间接依赖|npm|
|issue-parser|6.0.0|间接依赖|npm|
|ini|2.0.0|间接依赖|npm|
|babel-runtime|6.26.0|间接依赖|npm|
|strip-json-comments|2.0.1|间接依赖|npm|
|esrecurse|4.3.0|间接依赖|npm|
|bin-links|2.2.1|间接依赖|npm|
|source-map-url|0.4.1|间接依赖|npm|
|meow|8.1.2|间接依赖|npm|
|make-dir|3.1.0|间接依赖|npm|
|cross-spawn|6.0.5|间接依赖|npm|
|promise-retry|2.0.1|间接依赖|npm|
|@nodelib/fs.walk|1.2.6|间接依赖|npm|
|proc-log|1.0.0|间接依赖|npm|
|cron-parser|4.2.1|直接依赖|npm|
|@npmcli/arborist|2.4.0|间接依赖|npm|
|smart-buffer|4.1.0|间接依赖|npm|
|normalize-package-data|2.5.0|间接依赖|npm|
|flat-cache|3.0.4|间接依赖|npm|
|acorn|7.4.1|间接依赖|npm|
|redis-errors|1.2.0|间接依赖|npm|
|regex-not|1.0.2|间接依赖|npm|
|cosmiconfig|7.0.0|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|ci-info|2.0.0|间接依赖|npm|
|uuid|8.3.2|直接依赖|npm|
|normalize-package-data|3.0.2|间接依赖|npm|
|parse-json|5.2.0|间接依赖|npm|
|minipass-flush|1.0.5|间接依赖|npm|
|colorette|1.2.2|间接依赖|npm|
|is-accessor-descriptor|1.0.0|间接依赖|npm|
|readable-stream|2.3.7|间接依赖|npm|
|find-versions|4.0.0|间接依赖|npm|
|env-ci|5.0.2|间接依赖|npm|
|aproba|2.0.0|间接依赖|npm|
|strip-json-comments|3.1.1|间接依赖|npm|
|common-ancestor-path|1.0.1|间接依赖|npm|
|picomatch|2.2.3|间接依赖|npm|
|JSONStream|1.3.5|间接依赖|npm|
|parse-conflict-json|1.1.1|间接依赖|npm|
|bcrypt-pbkdf|1.0.2|间接依赖|npm|
|redent|3.0.0|间接依赖|npm|
|semver-regex|3.1.2|间接依赖|npm|
|asn1|0.2.4|间接依赖|npm|
|quick-lru|1.1.0|间接依赖|npm|
|for-in|1.0.2|间接依赖|npm|
|ecc-jsbn|0.1.2|间接依赖|npm|
|require-main-filename|2.0.0|间接依赖|npm|
|minipass|3.1.3|间接依赖|npm|
|ansi-regex|5.0.0|间接依赖|npm|
|kind-of|3.2.2|间接依赖|npm|
|mocha-lcov-reporter|1.3.0|直接依赖|npm|
|lodash.isplainobject|4.0.6|间接依赖|npm|
|path-key|2.0.1|间接依赖|npm|
|js-yaml|4.0.0|间接依赖|npm|
|workerpool|6.1.0|间接依赖|npm|
|optionator|0.8.3|间接依赖|npm|
|ret|0.1.15|间接依赖|npm|
|@babel/parser|7.13.15|间接依赖|npm|
|escodegen|1.8.1|间接依赖|npm|
|http-signature|1.2.0|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|@npmcli/name-from-folder|1.0.1|间接依赖|npm|
|locate-path|6.0.0|间接依赖|npm|
|@npmcli/disparity-colors|1.0.1|间接依赖|npm|
|regexpp|3.1.0|间接依赖|npm|
|source-map|0.2.0|直接依赖|npm|
|libnpmaccess|4.0.2|间接依赖|npm|
|through2|4.0.2|间接依赖|npm|
|registry-auth-token|4.2.1|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|is-obj|2.0.0|间接依赖|npm|
|is-stream|2.0.0|间接依赖|npm|
|deprecation|2.3.1|间接依赖|npm|
|xtend|4.0.2|间接依赖|npm|
|asap|2.0.6|间接依赖|npm|
|get-port|5.1.1|直接依赖|npm|
|mkdirp|0.5.5|间接依赖|npm|
|text-table|0.2.0|间接依赖|npm|
|minipass-collect|1.0.2|间接依赖|npm|
|@istanbuljs/load-nyc-config|1.1.0|间接依赖|npm|
|lcov-parse|1.0.0|间接依赖|npm|
|modify-values|1.0.1|间接依赖|npm|
|java-properties|1.0.2|间接依赖|npm|
|locate-path|5.0.0|间接依赖|npm|
|is-core-module|2.2.0|间接依赖|npm|
|globals|11.12.0|间接依赖|npm|
|meow|4.0.1|间接依赖|npm|
|duplexer2|0.1.4|间接依赖|npm|
|type-fest|0.16.0|间接依赖|npm|
|string_decoder|1.3.0|间接依赖|npm|
|is-path-in-cwd|1.0.1|间接依赖|npm|
|mute-stream|0.0.8|间接依赖|npm|
|quick-lru|4.0.1|间接依赖|npm|
|@semantic-release/git|9.0.0|直接依赖|npm|
|is-data-descriptor|1.0.0|间接依赖|npm|
|qrcode-terminal|0.12.0|间接依赖|npm|
|spdx-expression-parse|3.0.1|间接依赖|npm|
|is-observable|1.1.0|间接依赖|npm|
|nyc|15.1.0|直接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|libnpmdiff|2.0.4|间接依赖|npm|
|psl|1.8.0|间接依赖|npm|
|defaults|1.0.3|间接依赖|npm|
|har-validator|5.1.5|间接依赖|npm|
|reusify|1.0.4|间接依赖|npm|
|levn|0.4.1|间接依赖|npm|
|node-releases|1.1.71|间接依赖|npm|
|serialize-javascript|5.0.1|间接依赖|npm|
|default-require-extensions|3.0.0|间接依赖|npm|
|core-js|2.6.12|间接依赖|npm|
|just-diff|3.1.1|间接依赖|npm|
|y18n|5.0.8|间接依赖|npm|
|json-stringify-safe|5.0.1|间接依赖|npm|
|lodash.capitalize|4.2.1|间接依赖|npm|
|toposort|2.0.2|间接依赖|npm|
|pascalcase|0.1.1|间接依赖|npm|
|@babel/helper-module-imports|7.13.12|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|read-pkg-up|3.0.0|间接依赖|npm|
|nopt|3.0.6|间接依赖|npm|
|resolve|1.1.7|间接依赖|npm|
|minimist-options|3.0.2|间接依赖|npm|
|@commitlint/execute-rule|7.6.0|间接依赖|npm|
|color-name|1.1.3|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|color-name|1.1.4|间接依赖|npm|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|depd|1.1.2|间接依赖|npm|
|run-parallel|1.2.0|间接依赖|npm|
|hard-rejection|2.1.0|间接依赖|npm|
|treeverse|1.0.4|间接依赖|npm|
|@sinonjs/text-encoding|0.7.1|间接依赖|npm|
|agent-base|6.0.2|间接依赖|npm|
|json-parse-even-better-errors|2.3.1|间接依赖|npm|
|minizlib|2.1.2|间接依赖|npm|
|jsbn|0.1.1|间接依赖|npm|
|fn-name|2.0.1|间接依赖|npm|
|p-try|2.2.0|间接依赖|npm|
|archy|1.0.0|间接依赖|npm|
|array-ify|1.0.0|间接依赖|npm|
|minipass-json-stream|1.0.1|间接依赖|npm|
|@octokit/plugin-rest-endpoint-methods|5.0.1|间接依赖|npm|
|rimraf|2.7.1|间接依赖|npm|
|verror|1.10.0|间接依赖|npm|
|caller-path|2.0.0|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|readdirp|3.5.0|间接依赖|npm|
|performance-now|2.1.0|间接依赖|npm|
|foreground-child|2.0.0|间接依赖|npm|
|html-escaper|2.0.2|间接依赖|npm|
|semver|6.0.0|间接依赖|npm|
|has-flag|1.0.0|间接依赖|npm|
|minipass-pipeline|1.2.4|间接依赖|npm|
|extsprintf|1.3.0|间接依赖|npm|
|is-path-cwd|2.2.0|间接依赖|npm|
|debug|3.2.7|间接依赖|npm|
|mkdirp-infer-owner|2.0.0|间接依赖|npm|
|spawn-wrap|2.0.0|间接依赖|npm|
|split|1.0.1|间接依赖|npm|
|path-type|3.0.0|间接依赖|npm|
|has-unicode|2.0.1|间接依赖|npm|
|string-width|1.0.2|间接依赖|npm|
|espree|7.3.1|间接依赖|npm|
|unique-string|2.0.0|间接依赖|npm|
|fastq|1.11.0|间接依赖|npm|
|hosted-git-info|2.8.9|间接依赖|npm|
|mixin-deep|1.3.2|间接依赖|npm|
|git-raw-commits|1.3.6|间接依赖|npm|
|@commitlint/lint|7.6.0|间接依赖|npm|
|get-intrinsic|1.1.1|间接依赖|npm|
|npm-registry-fetch|10.1.0|间接依赖|npm|
|is-lambda|1.0.1|间接依赖|npm|
|forever-agent|0.6.1|间接依赖|npm|
|@sinonjs/formatio|3.2.2|间接依赖|npm|
|arr-union|3.1.0|间接依赖|npm|
|yocto-queue|0.1.0|间接依赖|npm|
|humanize-ms|1.2.1|间接依赖|npm|
|@marionebl/sander|0.6.1|间接依赖|npm|
|lodash.templatesettings|4.2.0|间接依赖|npm|
|onetime|5.1.2|间接依赖|npm|
|conventional-commits-parser|2.1.7|间接依赖|npm|
|@tootallnate/once|1.1.2|间接依赖|npm|
|check-error|1.0.2|间接依赖|npm|
|libnpmteam|2.0.3|间接依赖|npm|
|@babel/runtime|7.13.10|间接依赖|npm|
|isstream|0.1.2|间接依赖|npm|
|combined-stream|1.0.8|间接依赖|npm|
|unique-slug|2.0.2|间接依赖|npm|
|get-stdin|7.0.0|间接依赖|npm|
|argv-formatter|1.0.0|间接依赖|npm|
|log-driver|1.2.7|间接依赖|npm|
|caching-transform|4.0.0|间接依赖|npm|
|@semantic-release/changelog|5.0.1|直接依赖|npm|
|promzard|0.3.0|间接依赖|npm|
|ansi-escapes|4.3.2|间接依赖|npm|
|tweetnacl|0.14.5|间接依赖|npm|
|rc|1.2.8|间接依赖|npm|
|yargs|16.2.0|间接依赖|npm|
|log-symbols|2.2.0|间接依赖|npm|
|execa|5.0.0|间接依赖|npm|
|micromatch|3.1.10|间接依赖|npm|
|clean-stack|2.2.0|间接依赖|npm|
|glob|5.0.15|间接依赖|npm|
|caseless|0.12.0|间接依赖|npm|
|regenerator-runtime|0.10.5|间接依赖|npm|
|spdx-exceptions|2.3.0|间接依赖|npm|
|pacote|11.3.2|间接依赖|npm|
|traverse|0.6.6|间接依赖|npm|
|infer-owner|1.0.4|间接依赖|npm|
|pkg-dir|4.2.0|间接依赖|npm|
|@npmcli/promise-spawn|1.3.2|间接依赖|npm|
|safe-regex|1.1.0|间接依赖|npm|
|graceful-fs|4.2.6|直接依赖|npm|
|https-proxy-agent|5.0.0|间接依赖|npm|
|type-detect|4.0.8|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)