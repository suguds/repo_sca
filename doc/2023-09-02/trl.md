# huggingface/trl安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1697676487029293056.svg)](https://www.murphysec.com/console/report/1697676486987350016/1697676487029293056)

仓库描述：Train transformer language models with reinforcement learning.

仓库地址：[https://github.com/huggingface/trl](https://github.com/huggingface/trl)

| star：5406 | watch：62 | fork：571 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-01 23:50:24 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-02 02:23:15 | 组件总数：8 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|PyTorch 命令注入漏洞|代码注入|[MPS-2022-65270](https://www.oscs1024.com/hd/MPS-2022-65270)|CVE-2022-45907|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|torch|1.4.0|1.13.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|1|Low|
|自定义许可证|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|GenerationConfig||间接依赖|pip|
|datasets|1.17.0|间接依赖|pip|
|peft|0.3.0|间接依赖|pip|
|AutoModelForCausalLM||间接依赖|pip|
|torch|1.4.0|间接依赖|pip|
|field||间接依赖|pip|
|AutoTokenizer||间接依赖|pip|
|dataclass||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)