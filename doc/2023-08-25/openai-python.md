# openai/openai-python安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694776166165409792.svg)](https://www.murphysec.com/console/report/1694776165943111680/1694776166165409792)

仓库描述：The OpenAI Python library provides convenient access to the OpenAI API from applications written in the Python language.

仓库地址：[https://github.com/openai/openai-python](https://github.com/openai/openai-python)

| star：10767 | watch：180 | fork：1608 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-23 21:47:24 | 许可证：MIT |
| 最近检测时间：2023-08-25 02:18:30 | 组件总数：17 | 漏洞总数：1 |

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
|自定义许可证|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|api_requestor||间接依赖|pip|
|NUMPY_INSTRUCTIONS||间接依赖|pip|
|ListableAPIResource||间接依赖|pip|
|Tuple||间接依赖|pip|
|DeletableAPIResource||间接依赖|pip|
|openai||间接依赖|pip|
|HAS_NUMPY||间接依赖|pip|
|Any||间接依赖|pip|
|Callable||间接依赖|pip|
|error||间接依赖|pip|
|Optional||间接依赖|pip|
|UpdateableAPIResource||间接依赖|pip|
|urlsplit||间接依赖|pip|
|List||间接依赖|pip|
|setuptools|39.2.0|间接依赖|pip|
|util||间接依赖|pip|
|urlencode||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)