# MiuLab/Taiwan-LLaMa安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1691515235948449792.svg)](https://www.murphysec.com/console/report/1691515235680014336/1691515235948449792)

仓库描述：Traditional Mandarin LLMs for Taiwan

仓库地址：[https://github.com/MiuLab/Taiwan-LLaMa](https://github.com/MiuLab/Taiwan-LLaMa)

| star：370 | watch：6 | fork：28 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-15 08:51:07 | 许可证：- |
| 最近检测时间：2023-08-16 02:20:37 | 组件总数：5 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|MPS-p829-6f3r|SQL注入|[MPS-p829-6f3r](https://www.oscs1024.com/hd/MPS-p829-6f3r)|CVE-2023-36189|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|langchain|0.0.260||间接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|2|Low|
|自定义许可证|1|Low|
|MIT|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|transformers|4.31.0|间接依赖|pip|
|openai|0.27.8|间接依赖|pip|
|text-generation|0.6.0|间接依赖|pip|
|langchain|0.0.260|间接依赖|pip|
|vllm|0.1.3|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)