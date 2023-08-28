# geekan/MetaGPT安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696226485911511040.svg)](https://www.murphysec.com/console/report/1677245773728792576/1696226485911511040)

仓库描述：🌟 The Multi-Agent Framework: Given one line Requirement, return PRD, Design, Tasks, Repo

仓库地址：[https://github.com/geekan/MetaGPT](https://github.com/geekan/MetaGPT)

| star：24048 | watch：515 | fork：2709 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-29 00:25:35 | 许可证：MIT |
| 最近检测时间：2023-08-29 02:21:35 | 组件总数：28 | 漏洞总数：10 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|
|loguru 代码注入漏洞|代码注入|[MPS-2022-1393](https://www.oscs1024.com/hd/MPS-2022-1393)|CVE-2022-0329|严重|
|LangChain 注入漏洞|注入|[MPS-3udo-v1n0](https://www.oscs1024.com/hd/MPS-3udo-v1n0)|CVE-2023-36188|严重|
|langchain-0.0.194代码注入漏洞|代码注入|[MPS-84rc-nja1](https://www.oscs1024.com/hd/MPS-84rc-nja1)|CVE-2023-36095|严重|
|langchain-0.0.231代码注入漏洞|代码注入|[MPS-fv9p-y147](https://www.oscs1024.com/hd/MPS-fv9p-y147)|CVE-2023-38860|严重|
|LangChain SQL注入漏洞|SQL注入|[MPS-p829-6f3r](https://www.oscs1024.com/hd/MPS-p829-6f3r)|CVE-2023-36189|高危|
|aiohttp 环境问题漏洞|HTTP请求走私|[MPS-ptqs-e23v](https://www.oscs1024.com/hd/MPS-ptqs-e23v)|CVE-2023-37276|高危|
|LangChain 安全漏洞||[MPS-s5ul-own1](https://www.oscs1024.com/hd/MPS-s5ul-own1)|CVE-2023-36258|严重|
|langchain注入漏洞|注入|[MPS-vszg-p7q8](https://www.oscs1024.com/hd/MPS-vszg-p7q8)|CVE-2023-38896|严重|
|langchain注入漏洞|注入|[MPS-x9qb-uct8](https://www.oscs1024.com/hd/MPS-x9qb-uct8)|CVE-2023-39659|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|langchain|0.0.231|0.0.236|间接依赖|建议修复|C:6|H:1|M:0|L:0|
|aiohttp|3.8.4|3.8.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|loguru|0.6.0||间接依赖|建议修复|C:1|H:0|M:0|L:0|
|numpy|1.24.3||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|2|Low|
|Apache-2.0|2|Low|
|MIT|11|Low|
|自定义许可证|3|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|pandas|2.0.3|间接依赖|pip|
|tenacity|8.2.2|间接依赖|pip|
|beautifulsoup4|4.12.2|间接依赖|pip|
|qdrant-client|1.4.0|间接依赖|pip|
|python_docx|0.8.11|间接依赖|pip|
|tiktoken|0.3.3|间接依赖|pip|
|libcst|1.0.1|间接依赖|pip|
|web_browser_engine||间接依赖|pip|
|numpy|1.24.3|间接依赖|pip|
|PyYAML|6.0|间接依赖|pip|
|pytest|7.2.2|间接依赖|pip|
|metagpt||间接依赖|pip|
|faiss_cpu|1.7.4|间接依赖|pip|
|meilisearch|0.21.0|间接依赖|pip|
|loguru|0.6.0|间接依赖|pip|
|pydantic|1.10.8|间接依赖|pip|
|requirements.txt||间接依赖|pip|
|openai|0.27.8|间接依赖|pip|
|channels|4.0.0|间接依赖|pip|
|fire|0.4.0|间接依赖|pip|
|tqdm|4.64.0|间接依赖|pip|
|anthropic|0.3.6|间接依赖|pip|
|setuptools|65.6.3|间接依赖|pip|
|aiohttp|3.8.4|间接依赖|pip|
|typing_extensions|4.5.0|间接依赖|pip|
|WebBrowserEngineType||间接依赖|pip|
|typing-inspect|0.8.0|间接依赖|pip|
|langchain|0.0.231|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)