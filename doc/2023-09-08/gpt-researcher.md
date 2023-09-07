# assafelovic/gpt-researcher安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699850291938902016.svg)](https://www.murphysec.com/console/report/1691876436616302592/1699850291938902016)

仓库描述：GPT based autonomous agent that does online comprehensive research on any given topic

仓库地址：[https://github.com/assafelovic/gpt-researcher](https://github.com/assafelovic/gpt-researcher)

| star：4362 | watch：47 | fork：462 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-07 20:54:21 | 许可证：MIT |
| 最近检测时间：2023-09-08 02:21:22 | 组件总数：14 | 漏洞总数：3 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|LangChain 代码注入漏洞|代码注入|[MPS-7jdv-a49n](https://www.oscs1024.com/hd/MPS-7jdv-a49n)|CVE-2023-36281|严重|
|langchain注入漏洞|注入|[MPS-x9qb-uct8](https://www.oscs1024.com/hd/MPS-x9qb-uct8)|CVE-2023-39659|严重|
|LangChain 安全漏洞|代码注入|[MPS-ze2c-1nou](https://www.oscs1024.com/hd/MPS-ze2c-1nou)|CVE-2023-39631|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|langchain|0.0.275||间接依赖|建议修复|C:3|H:0|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|2|Low|
|自定义许可证|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|Dict||间接依赖|pip|
|requirements.txt||间接依赖|pip|
|langchain|0.0.275|间接依赖|pip|
|pyyaml|6.0.1|间接依赖|pip|
|beautifulsoup4|4.12.2|间接依赖|pip|
|duckduckgo_search|3.8.5|间接依赖|pip|
|playwright|1.36.0|间接依赖|pip|
|List||间接依赖|pip|
|md2pdf|1.0.1|间接依赖|pip|
|asyncio|3.4.3|间接依赖|pip|
|colorama|0.4.6|间接依赖|pip|
|config||间接依赖|pip|
|fastapi||间接依赖|pip|
|webdriver-manager|4.0.0|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)