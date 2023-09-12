# MakiNaruto/Automatic_ticket_purchase安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1701662864951607296.svg)](https://www.murphysec.com/console/report/1699850688079200256/1701662864951607296)

仓库描述：大麦网抢票脚本

仓库地址：[https://github.com/MakiNaruto/Automatic_ticket_purchase](https://github.com/MakiNaruto/Automatic_ticket_purchase)

| star：2677 | watch：17 | fork：609 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2022-05-24 16:51:42 | 许可证：MIT |
| 最近检测时间：2023-09-13 02:23:48 | 组件总数：4 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Requests Proxy-Authorization 标头泄露漏洞|未授权敏感信息泄露|[MPS-hr61-tzey](https://www.oscs1024.com/hd/MPS-hr61-tzey)|CVE-2023-32681|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|requests|2.24.0|2.31.0|间接依赖|建议修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|1|Low|
|Apache-2.0|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|beautifulsoup4|4.9.3|间接依赖|pip|
|pyexecjs|1.5.1|间接依赖|pip|
|selenium|3.141.0|间接依赖|pip|
|requests|2.24.0|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)