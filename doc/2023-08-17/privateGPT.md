# imartinez/privateGPT安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1691876964532375552.svg)](https://www.murphysec.com/console/report/1691513914738495488/1691876964532375552)

仓库描述：Interact privately with your documents using the power of GPT, 100% privately, no data leaks

仓库地址：[https://github.com/imartinez/privateGPT](https://github.com/imartinez/privateGPT)

| star：36150 | watch：350 | fork：4597 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-15 02:17:51 | 许可证：- |
| 最近检测时间：2023-08-17 02:18:09 | 组件总数：13 | 漏洞总数：4 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|MPS-3udo-v1n0|注入|[MPS-3udo-v1n0](https://www.oscs1024.com/hd/MPS-3udo-v1n0)|CVE-2023-36188|严重|
|MPS-84rc-nja1|代码注入|[MPS-84rc-nja1](https://www.oscs1024.com/hd/MPS-84rc-nja1)|CVE-2023-36095|严重|
|MPS-p829-6f3r|SQL注入|[MPS-p829-6f3r](https://www.oscs1024.com/hd/MPS-p829-6f3r)|CVE-2023-36189|高危|
|MPS-s5ul-own1||[MPS-s5ul-own1](https://www.oscs1024.com/hd/MPS-s5ul-own1)|CVE-2023-36258|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|langchain|0.0.228|0.0.236|间接依赖|建议修复|C:3|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|7|Low|
|Apache-2.0|1|Low|
|自定义许可证|2|Low|
|BSD-3-Clause|1|Low|
|GPL-3.0-or-later|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|urllib3|2.0.3|间接依赖|pip|
|tabulate|0.9.0|间接依赖|pip|
|chromadb|0.3.26|间接依赖|pip|
|unstructured|0.8.0|间接依赖|pip|
|tqdm|4.65.0|间接依赖|pip|
|pypandoc|1.11|间接依赖|pip|
|extract-msg|0.41.5|间接依赖|pip|
|langchain|0.0.228|间接依赖|pip|
|python-dotenv|1.0.0|间接依赖|pip|
|llama-cpp-python|0.1.68|间接依赖|pip|
|pandoc|2.3|间接依赖|pip|
|gpt4all|1.0.3|间接依赖|pip|
|PyMuPDF|1.22.5|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)