# lunarphp/lunar安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1702387800020221952.svg)](https://www.murphysec.com/console/report/1702387799760175104/1702387800020221952)

仓库描述：An open-source package that brings the power of modern headless e-commerce functionality to Laravel.

仓库地址：[https://github.com/lunarphp/lunar](https://github.com/lunarphp/lunar)

| star：1612 | watch：38 | fork：222 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-14 16:45:29 | 许可证：MIT |
| 最近检测时间：2023-09-15 02:25:15 | 组件总数：16 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Laravel v9.1.8 反序列化漏洞|反序列化|[MPS-2022-10162](https://www.oscs1024.com/hd/MPS-2022-10162)|CVE-2022-30778|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|laravel/framework|^9.0|^10.0||间接依赖|强烈建议修复|C:1|H:0|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|13|Low|
|BSD-3-Clause|1|Low|
|SDK|1|Low|
|LGPL-2.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|spatie/laravel-permission|^5.10|间接依赖|composer|
|cartalyst/converter|^7.0|^8.0|间接依赖|composer|
|guzzlehttp/guzzle|^7.3|间接依赖|composer|
|laravel/framework|^9.0|^10.0|间接依赖|composer|
|spatie/laravel-activitylog|^4.4|间接依赖|composer|
|lukascivil/treewalker|0.9.1|间接依赖|composer|
|lunarphp/livewire-tables|self.version|间接依赖|composer|
|spatie/laravel-blink|^1.6|间接依赖|composer|
|spatie/laravel-medialibrary|^9.0.0|^10.0.0|间接依赖|composer|
|kalnoy/nestedset|^6.0|间接依赖|composer|
|barryvdh/laravel-dompdf|^2.0|间接依赖|composer|
|illuminate/http|^9.0|^10.0|间接依赖|composer|
|doctrine/dbal|^3.6|间接依赖|composer|
|lunarphp/licensing|self.version|间接依赖|composer|
|livewire/livewire|^2.0|间接依赖|composer|
|laravel/scout|^9.4|^10.0|间接依赖|composer|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)