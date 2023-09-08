# modelscope/modelscope-agent安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700212863876595712.svg)](https://www.murphysec.com/console/report/1700212863759155200/1700212863876595712)

仓库描述：ModelScope-Agent: An agent framework connecting models in ModelScope with the world

仓库地址：[https://github.com/modelscope/modelscope-agent](https://github.com/modelscope/modelscope-agent)

| star：208 | watch：9 | fork：17 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-08 10:46:35 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-09 02:21:58 | 组件总数：18 | 漏洞总数：1 |

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
|MIT|1|Low|
|Apache-2.0|3|Low|
|自定义许可证|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|dataclass||间接依赖|pip|
|pydantic|1.10.8|间接依赖|pip|
|modelscope|1.7.0|间接依赖|pip|
|Any||间接依赖|pip|
|modelscope_agent||间接依赖|pip|
|setuptools|39.2.0|间接依赖|pip|
|Optional||间接依赖|pip|
|transformers|4.29.0|间接依赖|pip|
|Dict||间接依赖|pip|
|display||间接依赖|pip|
|AutoModelForCausalLM||间接依赖|pip|
|datasets|2.8.0|间接依赖|pip|
|AutoTokenizer||间接依赖|pip|
|Pretty||间接依赖|pip|
|Tuple||间接依赖|pip|
|List||间接依赖|pip|
|Iterable||间接依赖|pip|
|field||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)