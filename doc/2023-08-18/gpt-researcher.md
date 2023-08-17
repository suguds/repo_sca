# assafelovic/gpt-researcher安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692240014699548672.svg)](https://www.murphysec.com/console/report/1691876436616302592/1692240014699548672)

仓库描述：GPT based autonomous agent that does online comprehensive research on any given topic

仓库地址：[https://github.com/assafelovic/gpt-researcher](https://github.com/assafelovic/gpt-researcher)

| star：3440 | watch：35 | fork：360 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-18 00:14:11 | 许可证：MIT |
| 最近检测时间：2023-08-18 02:20:45 | 组件总数：15 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|LangChain SQL注入漏洞|SQL注入|[MPS-p829-6f3r](https://www.oscs1024.com/hd/MPS-p829-6f3r)|CVE-2023-36189|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|langchain|0.0.263||间接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|2|Low|
|MIT|2|Low|
|Apache-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|requirements.txt||间接依赖|pip|
|config||间接依赖|pip|
|playwright|1.36.0|间接依赖|pip|
|duckduckgo_search|3.8.4|间接依赖|pip|
|webdriver-manager|4.0.0|间接依赖|pip|
|fastapi||间接依赖|pip|
|langchain|0.0.263|间接依赖|pip|
|beautifulsoup4|4.12.2|间接依赖|pip|
|md2pdf|1.0.1|间接依赖|pip|
|colorama|0.4.6|间接依赖|pip|
|Dict||间接依赖|pip|
|List||间接依赖|pip|
|pyyaml|6.0.1|间接依赖|pip|
|selenium|4.11.2|间接依赖|pip|
|asyncio|3.4.3|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)