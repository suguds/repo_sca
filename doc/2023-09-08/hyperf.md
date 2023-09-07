# hyperf/hyperf安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699851883460034560.svg)](https://www.murphysec.com/console/report/1699851883082547200/1699851883460034560)

仓库描述：🚀 A coroutine framework that focuses on hyperspeed and flexibility. Building microservice or middleware with ease.

仓库地址：[https://github.com/hyperf/hyperf](https://github.com/hyperf/hyperf)

| star：5470 | watch：122 | fork：1112 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-07 14:50:57 | 许可证：MIT |
| 最近检测时间：2023-09-08 02:29:25 | 组件总数：124 | 漏洞总数：18 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|grpc<1.24.4 原型污染漏洞|注入|[MPS-2020-15701](https://www.oscs1024.com/hd/MPS-2020-15701)|CVE-2020-7768|高危|
|Yargs Y18n 输入原型污染漏洞|动态确定对象属性修改的控制不恰当|[MPS-2020-17543](https://www.oscs1024.com/hd/MPS-2020-17543)|CVE-2020-7774|严重|
|Ini <1.3.6原型污染漏洞|拒绝服务|[MPS-2020-17544](https://www.oscs1024.com/hd/MPS-2020-17544)|CVE-2020-7788|高危|
|node-tar 路径遍历漏洞|路径遍历|[MPS-2021-11547](https://www.oscs1024.com/hd/MPS-2021-11547)|CVE-2021-32804|高危|
|node-tar 路径遍历漏洞|在文件访问前对链接解析不恰当（链接跟随）|[MPS-2021-11548](https://www.oscs1024.com/hd/MPS-2021-11548)|CVE-2021-32803|高危|
|lodash 拒绝服务漏洞|拒绝服务|[MPS-2021-2574](https://www.oscs1024.com/hd/MPS-2021-2574)|CVE-2020-28500|中危|
|lodash 命令注入漏洞|代码注入|[MPS-2021-2638](https://www.oscs1024.com/hd/MPS-2021-2638)|CVE-2021-23337|高危|
|Npm Node-tar 后置链接漏洞||[MPS-2021-28486](https://www.oscs1024.com/hd/MPS-2021-28486)|CVE-2021-37701|高危|
|Npm Node-tar 后置链接漏洞||[MPS-2021-28488](https://www.oscs1024.com/hd/MPS-2021-28488)|CVE-2021-37712|高危|
|node-tar 路径遍历漏洞|路径遍历|[MPS-2021-28489](https://www.oscs1024.com/hd/MPS-2021-28489)|CVE-2021-37713|高危|
|minimist 安全漏洞|原型污染|[MPS-2021-38405](https://www.oscs1024.com/hd/MPS-2021-38405)|CVE-2021-44906|严重|
|tar 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2022-14081](https://www.oscs1024.com/hd/MPS-2022-14081)||低危|
|protobuf.js 安全漏洞|原型污染|[MPS-2022-5162](https://www.oscs1024.com/hd/MPS-2022-5162)|CVE-2022-25878|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58307](https://www.oscs1024.com/hd/MPS-2022-58307)|CVE-2022-41723|高危|
|minimatch 资源管理错误漏洞|拒绝服务|[MPS-2022-59845](https://www.oscs1024.com/hd/MPS-2022-59845)|CVE-2022-3517|高危|
|needle 存在Authorization请求头泄露漏洞|未授权敏感信息泄露|[MPS-2022-7866](https://www.oscs1024.com/hd/MPS-2022-7866)||中危|
|Google Go 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2022-9049](https://www.oscs1024.com/hd/MPS-2022-9049)|CVE-2022-29526|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|grpc|1.24.3|1.24.4|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|y18n|3.2.1|5.0.5|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|protobufjs|5.0.3|7.2.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|ini|1.3.5|1.3.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|minimatch|3.0.4|3.0.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|golang.org/x/net|v0.0.0-20220812174116-3211cb980234|0.7.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tar|4.4.13|6.1.9|间接依赖|建议修复|C:0|H:5|M:0|L:1|
|minimist|1.2.5|1.2.6|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|lodash|4.17.20|4.17.21|直接依赖|可选修复|C:0|H:1|M:1|L:0|
|golang.org/x/sys|v0.0.0-20220818161305-2296e01440c6|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|needle|2.5.2|3.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|5.7.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|9|Low|
|MIT|57|Low|
|ISC|34|Low|
|BSD-3-Clause|16|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|/System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation||间接依赖||
|google.golang.org/grpc|v1.48.0|间接依赖|go|
|lodash|4.17.20|直接依赖|npm|
|wide-align|1.1.3|间接依赖|npm|
|signal-exit|3.0.3|间接依赖|npm|
|@protobufjs/codegen|2.0.4|直接依赖|npm|
|psr/simple-cache|^1.0|^2.0|^3.0|间接依赖|composer|
|process-nextick-args|2.0.1|间接依赖|npm|
|path|0.12.7|直接依赖|npm|
|tar|4.4.13|间接依赖|npm|
|npm-bundled|1.1.1|间接依赖|npm|
|google.golang.org/genproto|v0.0.0-20220819174105-e9f053255caa|间接依赖|go|
|delegates|1.0.0|间接依赖|npm|
|gauge|2.7.4|间接依赖|npm|
|rc|1.2.8|间接依赖|npm|
|inherits|2.0.3|间接依赖|npm|
|strip-json-comments|2.0.1|间接依赖|npm|
|protobufjs|5.0.3|间接依赖|npm|
|number-is-nan|1.0.1|间接依赖|npm|
|psr/http-message|^1.0|^2.0|间接依赖|composer|
|inflight|1.0.6|间接依赖|npm|
|deep-extend|0.6.0|间接依赖|npm|
|psr/log|^1.0|^2.0|^3.0|间接依赖|composer|
|fs.realpath|1.0.0|间接依赖|npm|
|has-unicode|2.0.1|间接依赖|npm|
|code-point-at|1.1.0|间接依赖|npm|
|libpthread.so.0||间接依赖||
|set-blocking|2.0.0|间接依赖|npm|
|librt.so.1||间接依赖||
|minipass|2.9.0|间接依赖|npm|
|minizlib|1.3.3|间接依赖|npm|
|process|0.11.10|间接依赖|npm|
|isarray|1.0.0|间接依赖|npm|
|wrap-ansi|2.1.0|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|iconv-lite|0.4.24|间接依赖|npm|
|are-we-there-yet|1.1.5|间接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|ansi-regex|2.1.1|间接依赖|npm|
|colour|0.7.1|间接依赖|npm|
|rimraf|2.7.1|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|y18n|3.2.1|间接依赖|npm|
|yallist|3.1.1|间接依赖|npm|
|glob|7.1.6|间接依赖|npm|
|node-pre-gyp|0.15.0|间接依赖|npm|
|@types/node|14.10.1|间接依赖|npm|
|@protobufjs/path|1.1.2|直接依赖|npm|
|libgit2|0.25.0|间接依赖||
|golang.org/x/text|v0.3.7|间接依赖|go|
|once|1.4.0|间接依赖|npm|
|fs-minipass|1.2.7|间接依赖|npm|
|decamelize|1.2.0|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|yargs|3.32.0|间接依赖|npm|
|console-control-strings|1.1.0|间接依赖|npm|
|@protobufjs/pool|1.1.0|直接依赖|npm|
|camelcase|2.1.1|间接依赖|npm|
|invert-kv|1.0.0|间接依赖|npm|
|ignore-walk|3.0.3|间接依赖|npm|
|os-locale|1.4.0|间接依赖|npm|
|mkdirp|0.5.5|间接依赖|npm|
|needle|2.5.2|间接依赖|npm|
|nan|2.14.1|间接依赖|npm|
|bytebuffer|5.0.1|间接依赖|npm|
|@protobufjs/utf8|1.1.0|直接依赖|npm|
|psr/event-dispatcher|^1.0|间接依赖|composer|
|long|3.2.0|间接依赖|npm|
|lodash.clone|4.5.0|间接依赖|npm|
|os-tmpdir|1.0.2|间接依赖|npm|
|psr/http-server-middleware|^1.0|间接依赖|composer|
|@protobufjs/base64|1.1.2|直接依赖|npm|
|string-width|1.0.2|间接依赖|npm|
|npm-normalize-package-bin|1.0.1|间接依赖|npm|
|golang.org/x/net|v0.0.0-20220812174116-3211cb980234|间接依赖|go|
|@protobufjs/eventemitter|1.1.0|直接依赖|npm|
|github.com/golang/protobuf|v1.5.2|间接依赖|go|
|aproba|1.2.0|间接依赖|npm|
|grpc|1.24.3|直接依赖|npm|
|google.golang.org/protobuf|v1.28.1|间接依赖|go|
|sax|1.2.4|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|minimatch|3.0.4|间接依赖|npm|
|osenv|0.1.5|间接依赖|npm|
|@types/bytebuffer|5.0.41|间接依赖|npm|
|string_decoder|1.1.1|间接依赖|npm|
|readable-stream|2.3.7|间接依赖|npm|
|npmlog|4.1.2|间接依赖|npm|
|ini|1.3.5|间接依赖|npm|
|semver|5.7.1|间接依赖|npm|
|golang.org/x/sys|v0.0.0-20220818161305-2296e01440c6|间接依赖|go|
|core-util-is|1.0.2|间接依赖|npm|
|nopt|4.0.3|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|balanced-match|1.0.0|间接依赖|npm|
|chownr|1.1.4|间接依赖|npm|
|minimist|1.2.5|间接依赖|npm|
|npm-packlist|1.4.8|间接依赖|npm|
|/usr/lib/libSystem.B.dylib||间接依赖||
|cliui|3.2.0|间接依赖|npm|
|ascli|1.0.1|间接依赖|npm|
|optjs|3.2.2|间接依赖|npm|
|@protobufjs/inquire|1.1.0|间接依赖|npm|
|util|0.10.4|间接依赖|npm|
|@grpc/proto-loader|0.5.5|直接依赖|npm|
|@protobufjs/float|1.0.2|直接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|os-homedir|1.0.2|间接依赖|npm|
|strip-ansi|3.0.1|间接依赖|npm|
|debug|3.2.6|间接依赖|npm|
|@protobufjs/fetch|1.1.0|直接依赖|npm|
|@protobufjs/aspromise|1.1.2|间接依赖|npm|
|detect-libc|1.0.3|间接依赖|npm|
|libc.so.6||间接依赖||
|window-size|0.1.4|间接依赖|npm|
|abbrev|1.1.1|间接依赖|npm|
|lcid|1.0.0|间接依赖|npm|
|/System/Library/Frameworks/Security.framework/Versions/A/Security||间接依赖||
|psr/container|^1.0|^2.0|间接依赖|composer|
|@types/long|4.0.1|间接依赖|npm|
|lodash.camelcase|4.3.0|间接依赖|npm|
|is-fullwidth-code-point|1.0.0|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)