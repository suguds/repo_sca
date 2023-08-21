# xtekky/gpt4free安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1693690089648320512.svg)](https://www.murphysec.com/console/report/1693690088511664128/1693690089648320512)

仓库描述：The official gpt4free repository | various collection of powerful language models

仓库地址：[https://github.com/xtekky/gpt4free](https://github.com/xtekky/gpt4free)

| star：44178 | watch：418 | fork：11385 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-21 03:12:52 | 许可证：GPL-3.0 |
| 最近检测时间：2023-08-22 02:22:43 | 组件总数：12 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Requests Proxy-Authorization 标头泄露漏洞|未授权敏感信息泄露|[MPS-hr61-tzey](https://www.oscs1024.com/hd/MPS-hr61-tzey)|CVE-2023-32681|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|requests|2.27.1|2.31.0|间接依赖|建议修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|1|Low|
|LGPL-3.0|1|Medium|
|Apache-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|request||间接依赖|pip|
|setup||间接依赖|pip|
|CreateResult||间接依赖|pip|
|AsyncGenerator||间接依赖|pip|
|SHA256||间接依赖|pip|
|find_packages||间接依赖|pip|
|Provider||间接依赖|pip|
|Flask||间接依赖|pip|
|models||间接依赖|pip|
|Any||间接依赖|pip|
|BaseProvider||间接依赖|pip|
|requests|2.27.1|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)