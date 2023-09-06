# moment/moment安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699498191779135488.svg)](https://www.murphysec.com/console/report/1692606113475612672/1699498191779135488)

仓库描述：Parse, validate, manipulate, and display dates in javascript.

仓库地址：[https://github.com/moment/moment](https://github.com/moment/moment)

| star：47529 | watch：885 | fork：7184 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-07 00:53:17 | 许可证：MIT |
| 最近检测时间：2023-09-07 03:03:19 | 组件总数：505 | 漏洞总数：38 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|socket.io 拒绝服务漏洞|拒绝服务|[MPS-15wb-xgoz](https://www.oscs1024.com/hd/MPS-15wb-xgoz)|CVE-2023-32695|高危|
|Http-signature 安全漏洞|密码学签名的验证不恰当|[MPS-2018-6996](https://www.oscs1024.com/hd/MPS-2018-6996)|CVE-2017-16005|高危|
|Ajv v6.12.2 输入验证错误漏洞|MAID|[MPS-2020-10525](https://www.oscs1024.com/hd/MPS-2020-10525)|CVE-2020-15366|中危|
|Yargs Y18n 输入原型污染漏洞|动态确定对象属性修改的控制不恰当|[MPS-2020-17543](https://www.oscs1024.com/hd/MPS-2020-17543)|CVE-2020-7774|严重|
|Cowboy Getobject 安全漏洞|原型污染|[MPS-2020-18070](https://www.oscs1024.com/hd/MPS-2020-18070)|CVE-2020-28282|严重|
|jszip 原型污染漏洞|原型污染|[MPS-2021-11050](https://www.oscs1024.com/hd/MPS-2021-11050)|CVE-2021-23413|中危|
|UIkarma 打开重定向漏洞|跨站重定向|[MPS-2021-19534](https://www.oscs1024.com/hd/MPS-2021-19534)|CVE-2021-23495|中危|
|lodash 拒绝服务漏洞|拒绝服务|[MPS-2021-2574](https://www.oscs1024.com/hd/MPS-2021-2574)|CVE-2020-28500|中危|
|lodash 命令注入漏洞|代码注入|[MPS-2021-2638](https://www.oscs1024.com/hd/MPS-2021-2638)|CVE-2021-23337|高危|
|json-schema 安全漏洞|原型污染|[MPS-2021-34478](https://www.oscs1024.com/hd/MPS-2021-34478)|CVE-2021-3918|严重|
|org.webjars.bower:underscore 代码注入漏洞|代码注入|[MPS-2021-3658](https://www.oscs1024.com/hd/MPS-2021-3658)|CVE-2021-23358|高危|
|Engine.IO 代码问题漏洞|对因果或异常条件的不恰当检查|[MPS-2021-37034](https://www.oscs1024.com/hd/MPS-2021-37034)|CVE-2022-21676|高危|
|log4js-node 存在信息泄露漏洞|缺省权限不正确|[MPS-2021-37062](https://www.oscs1024.com/hd/MPS-2021-37062)|CVE-2022-21704|中危|
|minimist 安全漏洞|原型污染|[MPS-2021-38405](https://www.oscs1024.com/hd/MPS-2021-38405)|CVE-2021-44906|严重|
|handlebars 远程代码执行 (RCE) 漏洞|代码注入|[MPS-2021-4548](https://www.oscs1024.com/hd/MPS-2021-4548)|CVE-2021-23369|严重|
|npm path-parse 安全漏洞|拒绝服务|[MPS-2021-6165](https://www.oscs1024.com/hd/MPS-2021-6165)|CVE-2021-23343|高危|
|handlebars < 4.7.7 存在原型污染漏洞|原型污染|[MPS-2021-6180](https://www.oscs1024.com/hd/MPS-2021-6180)|CVE-2021-23383|严重|
|ws 存在拒绝服务漏洞||[MPS-2021-7109](https://www.oscs1024.com/hd/MPS-2021-7109)|CVE-2021-32640|中危|
|glob-parent < 5.1.2 存在拒绝服务漏洞|拒绝服务|[MPS-2021-7827](https://www.oscs1024.com/hd/MPS-2021-7827)|CVE-2020-28469|高危|
|follow-redirects <1.14.7 存在信息泄露漏洞|侵犯隐私|[MPS-2022-0815](https://www.oscs1024.com/hd/MPS-2022-0815)|CVE-2022-0155|中危|
|adm-zip <0.5.2存在路径遍历漏洞|路径遍历|[MPS-2022-13529](https://www.oscs1024.com/hd/MPS-2022-13529)||高危|
|istanbul-reports<3.1.3 反向 Tabnabbing漏洞|通过 window.opener 访问使用指向不受信任目标的 Web 链接|[MPS-2022-13797](https://www.oscs1024.com/hd/MPS-2022-13797)||中危|
|uglify-js <3.14.3 正则表达式拒绝服务漏洞|ReDoS|[MPS-2022-14112](https://www.oscs1024.com/hd/MPS-2022-14112)||中危|
|Grunt 路径遍历漏洞|路径遍历|[MPS-2022-2996](https://www.oscs1024.com/hd/MPS-2022-2996)|CVE-2022-0436|中危|
|Karma 跨站脚本漏洞|XSS|[MPS-2022-2997](https://www.oscs1024.com/hd/MPS-2022-2997)|CVE-2022-0437|中危|
|follow-redirects<1.14.8 信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-3636](https://www.oscs1024.com/hd/MPS-2022-3636)|CVE-2022-0536|中危|
|Express 中的 qs 模块存在原型污染漏洞|原型污染|[MPS-2022-3967](https://www.oscs1024.com/hd/MPS-2022-3967)|CVE-2022-24999|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|decode-uri-component <=0.2.0 存在输入验证不当漏洞|拒绝服务|[MPS-2022-56259](https://www.oscs1024.com/hd/MPS-2022-56259)|CVE-2022-38900|高危|
|Socketio Engine.IO拒绝服务漏洞|未捕获的异常|[MPS-2022-58577](https://www.oscs1024.com/hd/MPS-2022-58577)|CVE-2022-41940|中危|
|minimatch 资源管理错误漏洞|拒绝服务|[MPS-2022-59845](https://www.oscs1024.com/hd/MPS-2022-59845)|CVE-2022-3517|高危|
|Tauri 原型污染漏洞|原型污染|[MPS-2022-65568](https://www.oscs1024.com/hd/MPS-2022-65568)|CVE-2022-46175|高危|
|Grunt 安全漏洞|检查时间与使用时间(TOCTOU)的竞争条件|[MPS-2022-9621](https://www.oscs1024.com/hd/MPS-2022-9621)|CVE-2022-1537|高危|
|JSZip目录穿越漏洞|相对路径遍历|[MPS-2023-3073](https://www.oscs1024.com/hd/MPS-2023-3073)|CVE-2022-48285|高危|
|word-wrap 安全漏洞|ReDoS|[MPS-2023-5109](https://www.oscs1024.com/hd/MPS-2023-5109)|CVE-2023-26115|高危|
|tough-cookie 安全漏洞|原型污染|[MPS-2023-5130](https://www.oscs1024.com/hd/MPS-2023-5130)|CVE-2023-26136|严重|
|request SSRF防御绕过漏洞|SSRF|[MPS-2023-7722](https://www.oscs1024.com/hd/MPS-2023-7722)|CVE-2023-28155|中危|
|tough-cookie<4.1.3 存在原型污染漏洞|原型污染|[MPS-esyq-56vx](https://www.oscs1024.com/hd/MPS-esyq-56vx)||中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|tough-cookie|2.5.0|4.1.3|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|engine.io|4.1.1|6.4.2|直接依赖|建议修复|C:0|H:1|M:1|L:0|
|jszip|3.5.0|3.8.0|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|http-signature|1.2.0||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|grunt|1.3.0|1.5.3|直接依赖|建议修复|C:0|H:1|M:1|L:0|
|minimist|1.2.5|1.2.6|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|handlebars|4.7.6|4.7.7|间接依赖|建议修复|C:2|H:0|M:0|L:0|
|word-wrap|1.2.3|1.2.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|decode-uri-component|0.2.0|0.2.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|glob-parent|5.1.1|6.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|underscore|1.11.0|1.13.0-2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|adm-zip|0.4.14|0.5.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|getobject|0.1.0|1.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|path-parse|1.0.6|1.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|minimatch|3.0.4|3.0.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|json5|2.1.3|2.2.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|y18n|4.0.0|5.0.5|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|socket.io-parser|4.0.4|4.2.3|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|json-schema|0.2.3|0.4.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|qs|6.5.2|6.10.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|karma|6.1.1|6.3.16|直接依赖|可选修复|C:0|H:0|M:2|L:0|
|follow-redirects|1.13.2|1.14.8|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|uglify-js|3.12.8|3.14.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|log4js|6.3.0|6.4.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|istanbul-reports|3.0.2|3.1.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|6.3.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|request|2.88.2||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|lodash|4.17.20|4.17.21|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|ajv|6.12.2|6.12.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|ws|7.4.3|7.4.6|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|399|Low|
|ISC|42|Low|
|Apache-2.0|15|Low|
|BSD-2-Clause|10|Low|
|BSD-3-Clause|15|Low|
|自定义许可证|1|Low|
|0BSD|1|Low|
|Unlicense|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|is-windows|1.0.2|间接依赖|npm|
|mixin-deep|1.3.2|间接依赖|npm|
|ini|1.3.8|间接依赖|npm|
|websocket-extensions|0.1.4|间接依赖|npm|
|which-module|2.0.0|间接依赖|npm|
|delayed-stream|1.0.0|间接依赖|npm|
|clean-stack|2.2.0|间接依赖|npm|
|@types/component-emitter|1.2.10|间接依赖|npm|
|lie|3.3.0|间接依赖|npm|
|assert-plus|1.0.0|间接依赖|npm|
|sshpk|1.16.1|间接依赖|npm|
|parseurl|1.3.3|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|content-type|1.0.4|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|interpret|1.1.0|间接依赖|npm|
|date-format|3.0.0|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|strip-ansi|5.2.0|间接依赖|npm|
|hasha|5.2.1|间接依赖|npm|
|type-is|1.6.18|间接依赖|npm|
|asynckit|0.4.0|间接依赖|npm|
|mkdirp|0.5.5|间接依赖|npm|
|underscore.string|3.3.5|间接依赖|npm|
|chokidar|3.5.1|间接依赖|npm|
|run-async|2.4.1|间接依赖|npm|
|toidentifier|1.0.0|间接依赖|npm|
|platform|1.3.6|间接依赖|npm|
|p-limit|2.3.0|间接依赖|npm|
|jsbn|0.1.1|间接依赖|npm|
|class-utils|0.3.6|间接依赖|npm|
|readable-stream|2.3.7|间接依赖|npm|
|bytes|1.0.0|间接依赖|npm|
|forever-agent|0.6.1|间接依赖|npm|
|grunt-contrib-uglify|5.0.0|直接依赖|npm|
|cli-width|2.2.1|间接依赖|npm|
|handlebars|4.7.6|间接依赖|npm|
|typescript|1.8.10|直接依赖|npm|
|semver|6.3.0|间接依赖|npm|
|gzip-size|3.0.0|间接依赖|npm|
|cli-table|0.3.1|间接依赖|npm|
|cliui|6.0.0|间接依赖|npm|
|isbinaryfile|4.0.6|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|grunt-karma|4.0.0|直接依赖|npm|
|map-cache|0.2.2|间接依赖|npm|
|qunit|2.10.0|间接依赖|npm|
|is-accessor-descriptor|0.1.6|间接依赖|npm|
|esrecurse|4.2.1|间接依赖|npm|
|glob-parent|5.1.1|间接依赖|npm|
|wrap-ansi|6.2.0|间接依赖|npm|
|slice-ansi|2.1.0|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|error|7.2.1|间接依赖|npm|
|oomphinc/composer-installers-extender|*|间接依赖|composer|
|shebang-command|1.2.0|间接依赖|npm|
|tiny-glob|0.2.6|直接依赖|npm|
|object-visit|1.0.1|间接依赖|npm|
|har-schema|2.0.0|间接依赖|npm|
|istanbul-lib-coverage|3.0.0|间接依赖|npm|
|duplexer|0.1.2|间接依赖|npm|
|psl|1.8.0|间接依赖|npm|
|callsites|3.1.0|间接依赖|npm|
|grunt-string-replace|1.3.1|直接依赖|npm|
|indent-string|4.0.0|间接依赖|npm|
|object.map|1.0.1|间接依赖|npm|
|extend-shallow|3.0.2|间接依赖|npm|
|safe-regex|1.1.0|间接依赖|npm|
|table|5.4.6|间接依赖|npm|
|follow-redirects|1.13.2|间接依赖|npm|
|grunt-known-options|1.1.1|间接依赖|npm|
|@istanbuljs/schema|0.1.2|间接依赖|npm|
|use|3.1.1|间接依赖|npm|
|istanbul-lib-instrument|4.0.3|间接依赖|npm|
|minimatch|3.0.4|间接依赖|npm|
|socket.io-parser|4.0.4|直接依赖|npm|
|find-cache-dir|3.3.1|间接依赖|npm|
|@babel/generator|7.11.6|间接依赖|npm|
|on-finished|2.3.0|间接依赖|npm|
|to-fast-properties|2.0.0|间接依赖|npm|
|natural-compare|1.4.0|间接依赖|npm|
|json-stable-stringify-without-jsonify|1.0.1|间接依赖|npm|
|karma|6.1.1|直接依赖|npm|
|amdefine|1.0.1|直接依赖|npm|
|mime-db|1.44.0|间接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|snapdragon-node|2.1.1|间接依赖|npm|
|is-wsl|2.2.0|间接依赖|npm|
|extglob|2.0.4|间接依赖|npm|
|json-stringify-safe|5.0.1|间接依赖|npm|
|unpipe|1.0.0|间接依赖|npm|
|binary-extensions|2.2.0|间接依赖|npm|
|is-descriptor|0.1.6|间接依赖|npm|
|strip-json-comments|3.1.0|间接依赖|npm|
|prelude-ls|1.1.2|间接依赖|npm|
|picomatch|2.2.2|间接依赖|npm|
|flagged-respawn|1.0.1|间接依赖|npm|
|esquery|1.3.1|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|har-validator|5.1.5|间接依赖|npm|
|p-map|3.0.0|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|gensync|1.0.0-beta.1|间接依赖|npm|
|string-template|0.2.1|间接依赖|npm|
|custom-event|1.0.1|间接依赖|npm|
|lcov-parse|1.0.0|间接依赖|npm|
|negotiator|0.6.2|间接依赖|npm|
|@babel/traverse|7.11.5|间接依赖|npm|
|posix-character-classes|0.1.1|间接依赖|npm|
|exit|0.1.2|间接依赖|npm|
|core-util-is|1.0.2|间接依赖|npm|
|raw-body|1.1.7|间接依赖|npm|
|minimist|1.2.5|间接依赖|npm|
|decamelize|1.2.0|间接依赖|npm|
|strip-bom|4.0.0|间接依赖|npm|
|karma-qunit|4.1.1|直接依赖|npm|
|color-name|1.1.3|间接依赖|npm|
|define-property|2.0.2|间接依赖|npm|
|hooker|0.2.3|间接依赖|npm|
|@types/cors|2.8.10|直接依赖|npm|
|base|0.11.2|间接依赖|npm|
|verror|1.10.0|间接依赖|npm|
|imurmurhash|0.1.4|间接依赖|npm|
|process-on-spawn|1.0.0|间接依赖|npm|
|is-stream|2.0.0|间接依赖|npm|
|@babel/helper-simple-access|7.10.4|间接依赖|npm|
|sauce-connect-launcher|1.3.2|间接依赖|npm|
|istanbul-reports|3.0.2|间接依赖|npm|
|regex-not|1.0.2|间接依赖|npm|
|v8-compile-cache|2.1.0|间接依赖|npm|
|aws-sign2|0.7.0|间接依赖|npm|
|js-yaml|3.13.1|间接依赖|npm|
|resolve-pkg|2.0.0|间接依赖|npm|
|grunt-contrib-copy|1.0.0|直接依赖|npm|
|acorn-jsx|5.2.0|间接依赖|npm|
|expand-brackets|2.1.4|间接依赖|npm|
|asn1|0.2.4|间接依赖|npm|
|globals|12.4.0|间接依赖|npm|
|mime|2.5.2|间接依赖|npm|
|arrify|2.0.1|间接依赖|npm|
|locate-path|5.0.0|间接依赖|npm|
|fast-deep-equal|3.1.1|间接依赖|npm|
|rechoir|0.6.2|间接依赖|npm|
|benchmark|2.1.4|间接依赖|npm|
|body-parser|1.19.0|间接依赖|npm|
|underscore|1.11.0|间接依赖|npm|
|di|0.0.1|间接依赖|npm|
|istanbul-lib-processinfo|2.0.2|间接依赖|npm|
|prettier|2.2.1|直接依赖|npm|
|grunt|1.3.0|直接依赖|npm|
|v8flags|3.1.3|间接依赖|npm|
|coveralls|3.1.0|直接依赖|npm|
|liftoff|2.5.0|间接依赖|npm|
|@babel/parser|7.11.5|间接依赖|npm|
|object.pick|1.3.0|间接依赖|npm|
|html-escaper|2.0.2|间接依赖|npm|
|@babel/code-frame|7.8.3|间接依赖|npm|
|commondir|1.0.1|间接依赖|npm|
|depd|1.1.2|间接依赖|npm|
|es6-promise|4.2.8|间接依赖|npm|
|type-fest|0.8.1|间接依赖|npm|
|require-main-filename|2.0.0|间接依赖|npm|
|jsonfile|4.0.0|间接依赖|npm|
|ee-first|1.1.1|间接依赖|npm|
|ent|2.2.0|间接依赖|npm|
|esprima|4.0.1|间接依赖|npm|
|eventemitter3|4.0.7|间接依赖|npm|
|release-zalgo|1.0.0|间接依赖|npm|
|functional-red-black-tree|1.0.1|间接依赖|npm|
|tough-cookie|2.5.0|间接依赖|npm|
|yargs|15.4.1|间接依赖|npm|
|@babel/types|7.11.5|间接依赖|npm|
|pako|1.0.11|间接依赖|npm|
|saucelabs|1.5.0|间接依赖|npm|
|array-unique|0.3.2|间接依赖|npm|
|cross-spawn|6.0.5|间接依赖|npm|
|p-locate|4.1.0|间接依赖|npm|
|ansi-regex|5.0.0|间接依赖|npm|
|astral-regex|1.0.0|间接依赖|npm|
|ws|7.4.3|间接依赖|npm|
|argsparser|0.0.7|间接依赖|npm|
|esutils|2.0.3|间接依赖|npm|
|repeat-string|1.6.1|间接依赖|npm|
|p-try|2.2.0|间接依赖|npm|
|connect|3.7.0|间接依赖|npm|
|extend|3.0.2|间接依赖|npm|
|extsprintf|1.3.0|间接依赖|npm|
|make-iterator|1.0.1|间接依赖|npm|
|isobject|3.0.1|间接依赖|npm|
|string_decoder|0.10.31|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|path-key|2.0.1|间接依赖|npm|
|to-regex-range|2.1.1|间接依赖|npm|
|typedarray-to-buffer|3.1.5|间接依赖|npm|
|combined-stream|1.0.8|间接依赖|npm|
|readdirp|3.5.0|间接依赖|npm|
|ua-parser-js|0.7.24|间接依赖|npm|
|rfdc|1.2.0|间接依赖|npm|
|is-data-descriptor|0.1.4|间接依赖|npm|
|@babel/helper-module-transforms|7.11.0|间接依赖|npm|
|streamroller|2.2.4|间接依赖|npm|
|finalhandler|1.1.2|间接依赖|npm|
|type-check|0.3.2|间接依赖|npm|
|qs|6.5.2|间接依赖|npm|
|balanced-match|1.0.0|间接依赖|npm|
|word-wrap|1.2.3|间接依赖|npm|
|is-extendable|0.1.1|间接依赖|npm|
|grunt-contrib-concat|1.0.1|直接依赖|npm|
|dateformat|3.0.3|间接依赖|npm|
|@types/node|14.14.31|直接依赖|npm|
|range-parser|1.2.1|间接依赖|npm|
|path-root|0.1.1|间接依赖|npm|
|co|4.6.0|间接依赖|npm|
|globrex|0.1.2|间接依赖|npm|
|escape-html|1.0.3|间接依赖|npm|
|write|1.0.3|间接依赖|npm|
|caseless|0.12.0|间接依赖|npm|
|http-signature|1.2.0|间接依赖|npm|
|debug|4.1.1|间接依赖|npm|
|micromatch|3.1.10|直接依赖|npm|
|parse-passwd|1.0.0|间接依赖|npm|
|nanomatch|1.2.13|间接依赖|npm|
|oauth-sign|0.9.0|间接依赖|npm|
|abbrev|1.1.1|间接依赖|npm|
|iconv-lite|0.4.24|间接依赖|npm|
|pascalcase|0.1.1|间接依赖|npm|
|anymatch|3.1.1|间接依赖|npm|
|nopt|3.0.6|间接依赖|npm|
|js-reporters|1.2.1|间接依赖|npm|
|isarray|1.0.0|间接依赖|npm|
|rxjs|6.5.5|间接依赖|npm|
|fromentries|1.2.1|间接依赖|npm|
|for-own|1.0.0|间接依赖|npm|
|argparse|1.0.10|间接依赖|npm|
|atob|2.1.2|间接依赖|npm|
|lodash|4.17.20|间接依赖|npm|
|https-proxy-agent|5.0.0|间接依赖|npm|
|form-data|2.3.3|间接依赖|npm|
|@babel/highlight|7.9.0|间接依赖|npm|
|set-value|2.0.1|间接依赖|npm|
|braces|2.3.2|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|tmp|0.0.33|间接依赖|npm|
|camelcase|5.3.1|间接依赖|npm|
|os-homedir|1.0.2|间接依赖|npm|
|dashdash|1.14.1|间接依赖|npm|
|external-editor|3.1.0|间接依赖|npm|
|pkg-up|3.1.0|间接依赖|npm|
|path-parse|1.0.6|间接依赖|npm|
|neo-async|2.6.2|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|fsevents|2.1.3|间接依赖|npm|
|@babel/core|7.11.6|间接依赖|npm|
|eslint|6.8.0|直接依赖|npm|
|adm-zip|0.4.14|间接依赖|npm|
|grunt-legacy-util|2.0.0|间接依赖|npm|
|selenium-webdriver|4.0.0-alpha.7|间接依赖|npm|
|@types/cookie|0.4.0|直接依赖|npm|
|log-driver|1.2.7|间接依赖|npm|
|mute-stream|0.0.8|间接依赖|npm|
|source-map-resolve|0.5.3|间接依赖|npm|
|tiny-lr|1.1.1|间接依赖|npm|
|osenv|0.1.5|直接依赖|npm|
|@istanbuljs/load-nyc-config|1.1.0|间接依赖|npm|
|@babel/helper-split-export-declaration|7.11.0|间接依赖|npm|
|write-file-atomic|3.0.3|间接依赖|npm|
|array-differ|3.0.0|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|urix|0.1.0|间接依赖|npm|
|maxmin|2.1.0|间接依赖|npm|
|nice-try|1.0.5|间接依赖|npm|
|package-hash|4.0.0|间接依赖|npm|
|which|1.3.1|间接依赖|npm|
|foreground-child|2.0.0|间接依赖|npm|
|yargs-parser|18.1.3|间接依赖|npm|
|@babel/helper-member-expression-to-functions|7.11.0|间接依赖|npm|
|doctrine|3.0.0|间接依赖|npm|
|to-object-path|0.3.0|间接依赖|npm|
|bcrypt-pbkdf|1.0.2|间接依赖|npm|
|aggregate-error|3.1.0|间接依赖|npm|
|faye-websocket|0.10.0|间接依赖|npm|
|livereload-js|2.4.0|间接依赖|npm|
|union-value|1.0.1|间接依赖|npm|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|aws4|1.10.1|间接依赖|npm|
|safe-json-parse|1.0.1|间接依赖|npm|
|encodeurl|1.0.2|间接依赖|npm|
|universalify|0.1.2|间接依赖|npm|
|ret|0.1.15|间接依赖|npm|
|istanbul-lib-report|3.0.0|间接依赖|npm|
|engine.io|4.1.1|直接依赖|npm|
|caching-transform|4.0.0|间接依赖|npm|
|cors|2.8.5|间接依赖|npm|
|accepts|1.3.7|间接依赖|npm|
|@babel/helper-optimise-call-expression|7.10.4|间接依赖|npm|
|has-values|1.0.0|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|y18n|4.0.0|间接依赖|npm|
|escalade|3.1.1|直接依赖|npm|
|body|5.1.0|间接依赖|npm|
|jsprim|1.4.1|间接依赖|npm|
|ignore|4.0.6|间接依赖|npm|
|istanbul-lib-source-maps|4.0.0|间接依赖|npm|
|agent-base|6.0.0|间接依赖|npm|
|is-absolute|1.0.0|间接依赖|npm|
|cli-cursor|3.1.0|间接依赖|npm|
|eslint-scope|5.0.0|间接依赖|npm|
|dom-serialize|2.2.1|间接依赖|npm|
|number-is-nan|1.0.1|间接依赖|npm|
|es6-error|4.1.1|间接依赖|npm|
|arr-diff|4.0.0|间接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|snapdragon|0.8.2|间接依赖|npm|
|file-entry-cache|5.0.1|间接依赖|npm|
|safe-buffer|5.2.1|间接依赖|npm|
|@types/minimatch|3.0.3|间接依赖|npm|
|karma-sauce-launcher|4.1.4|直接依赖|npm|
|detect-file|1.0.0|直接依赖|npm|
|object-copy|0.1.0|间接依赖|npm|
|karma-firefox-launcher|1.3.0|直接依赖|npm|
|node-watch|0.6.1|间接依赖|npm|
|jszip|3.5.0|间接依赖|npm|
|grunt-env|1.0.1|直接依赖|npm|
|findup-sync|0.3.0|间接依赖|npm|
|file-sync-cmp|0.1.1|间接依赖|npm|
|assign-symbols|1.0.0|间接依赖|npm|
|grunt-contrib-clean|2.0.0|直接依赖|npm|
|arr-union|3.1.0|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|array-slice|1.1.0|间接依赖|npm|
|find-up|4.1.0|间接依赖|npm|
|kind-of|6.0.3|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|escodegen|1.8.1|间接依赖|npm|
|for-in|1.0.2|间接依赖|npm|
|media-typer|0.3.0|间接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|pretty-bytes|3.0.1|间接依赖|npm|
|ecc-jsbn|0.1.2|间接依赖|npm|
|tslib|1.11.2|间接依赖|npm|
|estraverse|4.3.0|间接依赖|npm|
|utils-merge|1.0.1|间接依赖|npm|
|cross-env|6.0.3|直接依赖|npm|
|emoji-regex|8.0.0|间接依赖|npm|
|load-grunt-tasks|5.1.0|直接依赖|npm|
|spawn-wrap|2.0.0|间接依赖|npm|
|getpass|0.1.7|间接依赖|npm|
|array-union|2.1.0|间接依赖|npm|
|globule|1.3.2|间接依赖|npm|
|uglify-js|3.12.8|间接依赖|npm|
|eventemitter2|0.4.14|间接依赖|npm|
|@babel/helper-replace-supers|7.10.4|间接依赖|npm|
|getobject|0.1.0|间接依赖|npm|
|chardet|0.7.0|间接依赖|npm|
|grunt-cli|1.3.2|间接依赖|npm|
|node-preload|0.2.1|间接依赖|npm|
|levn|0.3.0|间接依赖|npm|
|sprintf-js|1.0.3|间接依赖|npm|
|grunt-benchmark|1.0.0|直接依赖|npm|
|grunt-exec|3.0.0|直接依赖|npm|
|@babel/helper-function-name|7.10.4|间接依赖|npm|
|component-emitter|1.3.0|间接依赖|npm|
|multimatch|4.0.0|间接依赖|npm|
|@types/color-name|1.1.1|直接依赖|npm|
|pkg-dir|4.2.0|间接依赖|npm|
|is-binary-path|2.1.0|间接依赖|npm|
|regexpp|2.0.1|间接依赖|npm|
|@babel/template|7.10.4|间接依赖|npm|
|glob|7.1.6|间接依赖|npm|
|fs-extra|8.1.0|间接依赖|npm|
|istanbul|0.4.5|间接依赖|npm|
|is-plain-object|2.0.4|间接依赖|npm|
|fragment-cache|0.2.1|间接依赖|npm|
|path-exists|4.0.0|间接依赖|npm|
|http-errors|1.7.2|间接依赖|npm|
|is-glob|4.0.1|间接依赖|npm|
|istanbul-lib-hook|3.0.0|间接依赖|npm|
|decode-uri-component|0.2.0|间接依赖|npm|
|get-value|2.0.6|间接依赖|npm|
|to-regex|3.0.2|间接依赖|npm|
|websocket-driver|0.7.4|间接依赖|npm|
|string-width|4.2.0|间接依赖|npm|
|fast-levenshtein|2.0.6|间接依赖|npm|
|os-tmpdir|1.0.2|间接依赖|npm|
|set-blocking|2.0.0|间接依赖|npm|
|is-number|3.0.0|间接依赖|npm|
|figures|3.2.0|间接依赖|npm|
|@babel/helper-validator-identifier|7.9.5|间接依赖|npm|
|shebang-regex|1.0.0|间接依赖|npm|
|source-map|0.5.7|间接依赖|npm|
|progress|2.0.3|间接依赖|npm|
|espree|6.2.1|间接依赖|npm|
|cookie|0.4.1|间接依赖|npm|
|log4js|6.3.0|间接依赖|npm|
|collection-visit|1.0.0|间接依赖|npm|
|resolve|1.17.0|间接依赖|npm|
|flat-cache|2.0.1|间接依赖|npm|
|source-map-url|0.4.0|间接依赖|npm|
|signal-exit|3.0.3|间接依赖|npm|
|map-visit|1.0.0|间接依赖|npm|
|requires-port|1.0.0|间接依赖|npm|
|mimic-fn|2.1.0|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|set-immediate-shim|1.0.1|间接依赖|npm|
|json-schema|0.2.3|间接依赖|npm|
|commander|6.0.0|间接依赖|npm|
|ansi-escapes|4.3.1|间接依赖|npm|
|text-table|0.2.0|间接依赖|npm|
|parent-module|1.0.1|间接依赖|npm|
|get-package-type|0.1.0|间接依赖|npm|
|object.defaults|1.1.0|间接依赖|npm|
|is-typedarray|1.0.0|间接依赖|npm|
|onetime|5.1.0|间接依赖|npm|
|engine.io-parser|4.0.2|间接依赖|npm|
|isstream|0.1.2|间接依赖|npm|
|typescript3|npm:typescript@3.9.7|直接依赖|npm|
|@babel/helper-module-imports|7.10.4|间接依赖|npm|
|eslint-visitor-keys|1.1.0|间接依赖|npm|
|vary|1.1.2|间接依赖|npm|
|socket.io-adapter|2.1.0|直接依赖|npm|
|nyc|15.1.0|直接依赖|npm|
|append-transform|2.0.0|间接依赖|npm|
|base64-arraybuffer|0.1.4|间接依赖|npm|
|make-dir|3.1.0|间接依赖|npm|
|tunnel-agent|0.6.0|间接依赖|npm|
|resolve-url|0.2.1|间接依赖|npm|
|acorn|7.1.1|间接依赖|npm|
|karma-chrome-launcher|3.1.0|直接依赖|npm|
|punycode|2.1.1|间接依赖|npm|
|globalyzer|0.1.4|间接依赖|npm|
|http-parser-js|0.5.2|间接依赖|npm|
|performance-now|2.1.0|间接依赖|npm|
|archy|1.0.0|间接依赖|npm|
|http-proxy|1.18.1|间接依赖|npm|
|is-docker|2.1.1|间接依赖|npm|
|has-value|1.0.0|间接依赖|npm|
|grunt-nuget|0.3.1|直接依赖|npm|
|tracejs|0.1.8|间接依赖|npm|
|qjobs|1.2.0|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|is-buffer|1.1.6|直接依赖|npm|
|colors|1.1.2|间接依赖|npm|
|arr-flatten|1.1.0|间接依赖|npm|
|gaze|1.1.3|间接依赖|npm|
|statuses|1.5.0|间接依赖|npm|
|mime-types|2.1.27|间接依赖|npm|
|expand-tilde|2.0.2|间接依赖|npm|
|graceful-fs|4.2.4|间接依赖|npm|
|grunt-contrib-watch|1.1.0|直接依赖|npm|
|has-ansi|2.0.0|直接依赖|npm|
|tweetnacl|0.14.5|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|deep-is|0.1.3|间接依赖|npm|
|convert-source-map|1.7.0|间接依赖|npm|
|snapdragon-util|3.0.1|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|setprototypeof|1.1.1|间接依赖|npm|
|ajv|6.12.2|间接依赖|npm|
|wordwrap|1.0.0|间接依赖|npm|
|resolve-from|4.0.0|间接依赖|npm|
|rimraf|2.6.3|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|@babel/helpers|7.10.4|间接依赖|npm|
|homedir-polyfill|1.0.3|间接依赖|npm|
|uri-js|4.2.2|间接依赖|npm|
|array-each|1.0.1|间接依赖|npm|
|inquirer|7.1.0|间接依赖|npm|
|unset-value|1.0.0|间接依赖|npm|
|es6-promisify|5.0.0|直接依赖|npm|
|async|1.5.2|间接依赖|npm|
|void-elements|2.0.1|间接依赖|npm|
|fined|1.2.0|间接依赖|npm|
|json5|2.1.3|间接依赖|npm|
|optionator|0.8.3|间接依赖|npm|
|fill-range|4.0.0|间接依赖|npm|
|import-fresh|3.2.1|间接依赖|npm|
|static-extend|0.1.2|间接依赖|npm|
|process-nextick-args|2.0.1|间接依赖|npm|
|uuid|3.4.0|间接依赖|npm|
|eslint-utils|1.4.3|间接依赖|npm|
|lodash.flattendeep|4.4.0|间接依赖|npm|
|through|2.3.8|间接依赖|npm|
|continuable-cache|0.3.1|间接依赖|npm|
|uri-path|1.0.0|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|parse-filepath|1.0.2|间接依赖|npm|
|restore-cursor|3.1.0|间接依赖|npm|
|grunt-legacy-log-utils|2.1.0|间接依赖|npm|
|immediate|3.0.6|间接依赖|npm|
|test-exclude|6.0.0|间接依赖|npm|
|@babel/helper-get-function-arity|7.10.4|间接依赖|npm|
|grunt-legacy-log|3.0.0|间接依赖|npm|
|jsesc|2.5.2|间接依赖|npm|
|node-qunit|2.0.0|直接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|flatted|2.0.2|间接依赖|npm|
|request|2.88.2|间接依赖|npm|
|rollup|2.17.1|直接依赖|npm|
|base64id|2.0.0|间接依赖|npm|
|default-require-extensions|3.0.0|间接依赖|npm|
|split-string|3.1.0|间接依赖|npm|
|repeat-element|1.1.3|间接依赖|npm|
|cache-base|1.0.1|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)