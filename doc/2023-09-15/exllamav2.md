# turboderp/exllamav2安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1702385948373417984.svg)](https://www.murphysec.com/console/report/1702385948193062912/1702385948373417984)

仓库描述：A fast inference library for running LLMs locally on modern consumer-class GPUs

仓库地址：[https://github.com/turboderp/exllamav2](https://github.com/turboderp/exllamav2)

| star：882 | watch：16 | fork：42 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-14 23:53:34 | 许可证：MIT |
| 最近检测时间：2023-09-15 02:17:00 | 组件总数：12 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Python 安全漏洞|ReDoS|[MPS-2022-57238](https://www.oscs1024.com/hd/MPS-2022-57238)|CVE-2022-40897|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|setuptools|39.2.0|65.5.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|2|Low|
|Apache-2.0|2|Low|
|BSD-3-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|sentencepiece|0.1.97|间接依赖|pip|
|list_live_tensors||间接依赖|pip|
|print_vram_usage||间接依赖|pip|
|setuptools|39.2.0|间接依赖|pip|
|safetensors|0.3.2|间接依赖|pip|
|ExLlamaV2MLP||间接依赖|pip|
|pandas||间接依赖|pip|
|fastparquet||间接依赖|pip|
|exllamav2||间接依赖|pip|
|set_snapshot||间接依赖|pip|
|ExLlamaV2Attention||间接依赖|pip|
|torch|2.0.1|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)