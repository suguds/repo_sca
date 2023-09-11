# v2board/v2board安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1701301522159763456.svg)](https://www.murphysec.com/console/report/1695867961410482176/1701301522159763456)

仓库描述：🚀A multiple proxy protocol manage panel application interface

仓库地址：[https://github.com/v2board/v2board](https://github.com/v2board/v2board)

| star：3364 | watch：66 | fork：1173 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-14 17:31:34 | 许可证：MIT |
| 最近检测时间：2023-09-12 02:29:42 | 组件总数：12 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Laravel v9.1.8 反序列化漏洞|反序列化|[MPS-2022-10162](https://www.oscs1024.com/hd/MPS-2022-10162)|CVE-2022-30778|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|laravel/framework|^8.0||间接依赖|强烈建议修复|C:1|H:0|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|9|Low|
|Unlicense|1|Low|
|GPL-1.0|1|Medium|
|BSD-3-Clause|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|guzzlehttp/guzzle|^7.4.3|间接依赖|composer|
|symfony/yaml|^4.3|间接依赖|composer|
|php-curl-class/php-curl-class|^8.6|间接依赖|composer|
|stripe/stripe-php|^7.36.1|间接依赖|composer|
|laravel/framework|^8.0|间接依赖|composer|
|fideloper/proxy|^4.4|间接依赖|composer|
|linfo/linfo|^4.0|间接依赖|composer|
|google/recaptcha|^1.2|间接依赖|composer|
|fruitcake/laravel-cors|^2.0|间接依赖|composer|
|laravel/horizon|^5.9.6|间接依赖|composer|
|firebase/php-jwt|^6.3|间接依赖|composer|
|laravel/tinker|^2.5|间接依赖|composer|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)