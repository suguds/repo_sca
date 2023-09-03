# ramonvc/freegpt-webui安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698401249077805056.svg)](https://www.murphysec.com/console/report/1698401248998113280/1698401249077805056)

仓库描述：GPT 3.5/4 with a Chat Web UI. No API key required.

仓库地址：[https://github.com/ramonvc/freegpt-webui](https://github.com/ramonvc/freegpt-webui)

| star：5015 | watch：48 | fork：1439 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-20 04:57:23 | 许可证：GPL-3.0 |
| 最近检测时间：2023-09-04 02:24:08 | 组件总数：12 | 漏洞总数：1 |

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
|自定义许可证|1|Low|
|Apache-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|requirements.txt||间接依赖|pip|
|sha256||间接依赖|pip|
|ModelUtils||间接依赖|pip|
|flask||间接依赖|pip|
|requests|2.27.1|间接依赖|pip|
|get_type_hints||间接依赖|pip|
|session||间接依赖|pip|
|Dict||间接依赖|pip|
|Response||间接依赖|pip|
|Model||间接依赖|pip|
|g4f||间接依赖|pip|
|request||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)