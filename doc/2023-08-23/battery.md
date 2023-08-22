# actuallymentor/battery安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694055825533657088.svg)](https://www.murphysec.com/console/report/1694055824996786176/1694055825533657088)

仓库描述：CLI for managing the battery charging status for M1 Macs

仓库地址：[https://github.com/actuallymentor/battery](https://github.com/actuallymentor/battery)

| star：1554 | watch：22 | fork：69 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-22 22:07:04 | 许可证：MIT |
| 最近检测时间：2023-08-23 02:36:06 | 组件总数：42 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|semver|7.3.8|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MPL-2.0|13|Low|
|MIT|22|Low|
|BSD-2-Clause|2|Low|
|ISC|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|/usr/lib/libSystem.B.dylib||间接依赖||
|@resvg/resvg-js-win32-arm64-msvc|2.4.1|间接依赖|npm|
|find-up|3.0.0|间接依赖|npm|
|@resvg/resvg-js-android-arm-eabi|2.4.1|间接依赖|npm|
|conf|10.2.0|间接依赖|npm|
|github-url-to-object|4.0.6|间接依赖|npm|
|atomically|1.7.0|间接依赖|npm|
|@resvg/resvg-js|2.4.1|直接依赖|npm|
|electron-store|8.1.0|间接依赖|npm|
|@resvg/resvg-js-linux-x64-gnu|2.4.1|间接依赖|npm|
|/usr/lib/libiconv.2.dylib||间接依赖||
|is-url|1.2.4|间接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|require-from-string|2.0.2|间接依赖|npm|
|@resvg/resvg-js-linux-arm64-musl|2.4.1|间接依赖|npm|
|pkg-up|3.1.0|间接依赖|npm|
|@resvg/resvg-js-darwin-x64|2.4.1|间接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|json-schema-typed|7.0.3|间接依赖|npm|
|@resvg/resvg-js-win32-x64-msvc|2.4.1|间接依赖|npm|
|update-electron-app|2.0.1|间接依赖|npm|
|punycode|2.3.0|间接依赖|npm|
|@resvg/resvg-js-darwin-arm64|2.4.1|间接依赖|npm|
|is-obj|2.0.0|间接依赖|npm|
|electron-is-dev|0.3.0|间接依赖|npm|
|@resvg/resvg-js-android-arm64|2.4.1|间接依赖|npm|
|@resvg/resvg-js-linux-arm-gnueabihf|2.4.1|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|dot-prop|6.0.1|间接依赖|npm|
|@resvg/resvg-js-win32-ia32-msvc|2.4.1|间接依赖|npm|
|mimic-fn|3.1.0|间接依赖|npm|
|@resvg/resvg-js-linux-arm64-gnu|2.4.1|间接依赖|npm|
|ajv|8.12.0|间接依赖|npm|
|ajv-formats|2.1.1|间接依赖|npm|
|env-paths|2.2.1|间接依赖|npm|
|onetime|5.1.2|间接依赖|npm|
|@resvg/resvg-js-linux-x64-musl|2.4.1|间接依赖|npm|
|debounce-fn|4.0.0|间接依赖|npm|
|mimic-fn|2.1.0|间接依赖|npm|
|/System/Library/Frameworks/IOKit.framework/Versions/A/IOKit||间接依赖||
|semver|7.3.8|间接依赖|npm|
|type-fest|2.19.0|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)