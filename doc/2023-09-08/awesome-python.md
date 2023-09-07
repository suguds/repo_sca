# vinta/awesome-python安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699850424038506496.svg)](https://www.murphysec.com/console/report/1693326380773433344/1699850424038506496)

仓库描述：A curated list of awesome Python frameworks, libraries, software and resources

仓库地址：[https://github.com/vinta/awesome-python](https://github.com/vinta/awesome-python)

| star：179891 | watch：5876 | fork：23791 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-06 16:27:53 | 许可证：NOASSERTION |
| 最近检测时间：2023-09-08 02:21:53 | 组件总数：2 | 漏洞总数：3 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Mkdocs 安全漏洞|路径遍历|[MPS-2021-31742](https://www.oscs1024.com/hd/MPS-2021-31742)|CVE-2021-40978|高危|
|mkdocs 存在跨站脚本漏洞|XSS|[MPS-2022-14989](https://www.oscs1024.com/hd/MPS-2022-14989)||中危|
|MkDocs 存储型XSS漏洞|XSS|[MPS-2022-6935](https://www.oscs1024.com/hd/MPS-2022-6935)||中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|mkdocs|1.0.4|1.3.0|间接依赖|建议修复|C:0|H:1|M:2|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|1|Low|
|自定义许可证|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|mkdocs-material|4.0.2|间接依赖|pip|
|mkdocs|1.0.4|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)