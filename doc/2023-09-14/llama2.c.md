# karpathy/llama2.c安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1702024471224565760.svg)](https://www.murphysec.com/console/report/1702024471014850560/1702024471224565760)

仓库描述：Inference Llama 2 in one file of pure C

仓库地址：[https://github.com/karpathy/llama2.c](https://github.com/karpathy/llama2.c)

| star：11820 | watch：137 | fork：1118 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-14 02:14:01 | 许可证：MIT |
| 最近检测时间：2023-09-14 02:20:34 | 组件总数：10 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|numpy|1.23.5||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|1|Low|
|MIT|3|Low|
|自定义许可证|1|Low|
|Apache-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|Any||间接依赖|pip|
|numpy|1.23.5|间接依赖|pip|
|wandb|0.15.5|间接依赖|pip|
|sentencepiece|0.1.99|间接依赖|pip|
|Optional||间接依赖|pip|
|tqdm|4.64.1|间接依赖|pip|
|torch|2.0.1|间接依赖|pip|
|Requests|2.31.0|间接依赖|pip|
|arrow||间接依赖||
|pytest|7.4.0|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)