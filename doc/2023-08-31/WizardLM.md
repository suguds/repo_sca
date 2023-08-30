# nlpxucan/WizardLM安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696950393228390400.svg)](https://www.murphysec.com/console/report/1695865449173381120/1696950393228390400)

仓库描述：Family of instruction-following LLMs powered by Evol-Instruct: WizardLM, WizardCoder and WizardMath

仓库地址：[https://github.com/nlpxucan/WizardLM](https://github.com/nlpxucan/WizardLM)

| star：6501 | watch：98 | fork：475 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-30 14:13:04 | 许可证：- |
| 最近检测时间：2023-08-31 02:19:49 | 组件总数：11 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Gradio 信任管理问题漏洞|使用硬编码的凭证|[MPS-2023-4699](https://www.oscs1024.com/hd/MPS-2023-4699)|CVE-2023-25823|严重|
|Gradio 输入验证错误漏洞||[MPS-f8mu-5xwo](https://www.oscs1024.com/hd/MPS-f8mu-5xwo)|CVE-2023-34239|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|gradio|3.9|3.34.0|间接依赖|建议修复|C:2|H:0|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|1|Low|
|Apache-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|deepspeed|0.9.2|间接依赖|pip|
|SamplingParams||间接依赖|pip|
|LlamaTokenizer||间接依赖|pip|
|gradio|3.9|间接依赖|pip|
|AutoModelForCausalLM||间接依赖|pip|
|LLM||间接依赖|pip|
|LlamaForCausalLM||间接依赖|pip|
|AutoTokenizer||间接依赖|pip|
|Optional||间接依赖|pip|
|human_eval||间接依赖|pip|
|Sequence||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)