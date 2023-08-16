# PromtEngineer/localGPT安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1691877365407174656.svg)](https://www.murphysec.com/console/report/1691515500437065728/1691877365407174656)

仓库描述：Chat with your documents on your local device using GPT models. No data leaves your device and 100% private. 

仓库地址：[https://github.com/PromtEngineer/localGPT](https://github.com/PromtEngineer/localGPT)

| star：14969 | watch：137 | fork：1518 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-16 19:11:51 | 许可证：- |
| 最近检测时间：2023-08-17 02:19:46 | 组件总数：18 | 漏洞总数：6 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|MPS-3udo-v1n0|注入|[MPS-3udo-v1n0](https://www.oscs1024.com/hd/MPS-3udo-v1n0)|CVE-2023-36188|严重|
|MPS-6i1z-gkra||[MPS-6i1z-gkra](https://www.oscs1024.com/hd/MPS-6i1z-gkra)|CVE-2023-34540|严重|
|MPS-84rc-nja1|代码注入|[MPS-84rc-nja1](https://www.oscs1024.com/hd/MPS-84rc-nja1)|CVE-2023-36095|严重|
|MPS-c478-nvbi|命令注入|[MPS-c478-nvbi](https://www.oscs1024.com/hd/MPS-c478-nvbi)|CVE-2023-34541|高危|
|MPS-p829-6f3r|SQL注入|[MPS-p829-6f3r](https://www.oscs1024.com/hd/MPS-p829-6f3r)|CVE-2023-36189|高危|
|MPS-s5ul-own1||[MPS-s5ul-own1](https://www.oscs1024.com/hd/MPS-s5ul-own1)|CVE-2023-36258|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|langchain|0.0.191|0.0.236|间接依赖|建议修复|C:4|H:2|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|4|Low|
|自定义许可证|2|Low|
|BSD-3-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|ProcessPoolExecutor||间接依赖|pip|
|LlamaCpp||间接依赖|pip|
|urllib3|1.26.6|间接依赖|pip|
|langchain|0.0.191|间接依赖|pip|
|llama-cpp-python|0.1.66|间接依赖|pip|
|requirements.txt||间接依赖|pip|
|auto-gptq|0.2.2|间接依赖|pip|
|pdfminer.six|20221105|间接依赖|pip|
|Flask||间接依赖|pip|
|HuggingFacePipeline||间接依赖|pip|
|CHROMA_SETTINGS||间接依赖|pip|
|render_template||间接依赖|pip|
|jsonify||间接依赖|pip|
|chromadb|0.3.22|间接依赖|pip|
|PDFMinerLoader||间接依赖|pip|
|CSVLoader||间接依赖|pip|
|ThreadPoolExecutor||间接依赖|pip|
|EMBEDDING_MODEL_NAME||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)