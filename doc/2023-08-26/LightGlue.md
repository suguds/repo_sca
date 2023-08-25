# cvg/LightGlue安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695140312077725696.svg)](https://www.murphysec.com/console/report/1694776955735203840/1695140312077725696)

仓库描述：LightGlue: Local Feature Matching at Light Speed (ICCV 2023)

仓库地址：[https://github.com/cvg/LightGlue](https://github.com/cvg/LightGlue)

| star：1860 | watch：41 | fork：172 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-18 11:51:00 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-26 02:25:34 | 组件总数：3 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|PyTorch 命令注入漏洞|代码注入|[MPS-2022-65270](https://www.oscs1024.com/hd/MPS-2022-65270)|CVE-2022-45907|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|torch|1.9.1|1.13.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|1|Low|
|Apache-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|torchvision|0.3|间接依赖|pip|
|torch|1.9.1|间接依赖|pip|
|kornia|0.6.11|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)