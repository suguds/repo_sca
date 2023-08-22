# microsoft/Bringing-Old-Photos-Back-to-Life安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694051556453605376.svg)](https://www.murphysec.com/console/report/1693326644776685568/1694051556453605376)

仓库描述：Bringing Old Photo Back to Life (CVPR 2020 oral)

仓库地址：[https://github.com/microsoft/Bringing-Old-Photos-Back-to-Life](https://github.com/microsoft/Bringing-Old-Photos-Back-to-Life)

| star：13261 | watch：279 | fork：1737 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-06-07 12:43:28 | 许可证：MIT |
| 最近检测时间：2023-08-23 02:19:52 | 组件总数：3 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|PyTorch 命令注入漏洞|代码注入|[MPS-2022-65270](https://www.oscs1024.com/hd/MPS-2022-65270)|CVE-2022-45907|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|torch|1.0.0|1.13.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|LGPL-3.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|torch|1.0.0|间接依赖|pip|
|dominate|2.3.1|间接依赖|pip|
|requirements.txt||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)