# laravel/laravel安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1693329420830138368.svg)](https://www.murphysec.com/console/report/1693329420393930752/1693329420830138368)

仓库描述：Laravel is a web application framework with expressive, elegant syntax. We’ve already laid the foundation for your next big idea — freeing you to create without sweating the small things.

仓库地址：[https://github.com/laravel/laravel](https://github.com/laravel/laravel)

| star：74412 | watch：4457 | fork：23909 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-16 10:29:00 | 许可证：- |
| 最近检测时间：2023-08-21 02:30:56 | 组件总数：4 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Laravel v9.1.8 反序列化漏洞|反序列化|[MPS-2022-10162](https://www.oscs1024.com/hd/MPS-2022-10162)|CVE-2022-30778|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|laravel/framework|^10.10||间接依赖|强烈建议修复|C:1|H:0|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|4|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|laravel/tinker|^2.8|间接依赖|composer|
|laravel/sanctum|^3.2|间接依赖|composer|
|guzzlehttp/guzzle|^7.2|间接依赖|composer|
|laravel/framework|^10.10|间接依赖|composer|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)