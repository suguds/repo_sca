# barryvdh/laravel-dompdf安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692966506017349632.svg)](https://www.murphysec.com/console/report/1692966505467895808/1692966506017349632)

仓库描述：A DOMPDF Wrapper for Laravel

仓库地址：[https://github.com/barryvdh/laravel-dompdf](https://github.com/barryvdh/laravel-dompdf)

| star：6047 | watch：109 | fork：924 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-07-26 03:58:55 | 许可证：MIT |
| 最近检测时间：2023-08-20 02:29:47 | 组件总数：2 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|dompdf/dompdf 存在代码注入漏洞|代码注入|[MPS-2022-14193](https://www.oscs1024.com/hd/MPS-2022-14193)||高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|dompdf/dompdf|^2.0.1||间接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|1|Low|
|LGPL-3.0|1|Medium|
|LGPL-2.0|1|Medium|
|LGPL-2.1|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|illuminate/support|^6|^7|^8|^9|^10|间接依赖|composer|
|dompdf/dompdf|^2.0.1|间接依赖|composer|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)