# unifyai/ivy安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698763376960339968.svg)](https://www.murphysec.com/console/report/1698763376926785536/1698763376960339968)

仓库描述：The Unified AI Framework

仓库地址：[https://github.com/unifyai/ivy](https://github.com/unifyai/ivy)

| star：12905 | watch：68 | fork：5321 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-05 02:17:53 | 许可证：NOASSERTION |
| 最近检测时间：2023-09-05 02:22:31 | 组件总数：37 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|redis-py 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2023-8854](https://www.oscs1024.com/hd/MPS-2023-8854)|CVE-2023-28858|中危|
|redis-py 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2023-8855](https://www.oscs1024.com/hd/MPS-2023-8855)|CVE-2023-28859|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|redis|4.3.4|4.5.3|间接依赖|可选修复|C:0|H:0|M:2|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|1|Low|
|MIT|3|Low|
|自定义许可证|3|Low|
|Apache-2.0|1|Low|
|MPL-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|h5py|3.7.0|间接依赖|pip|
|redis|4.3.4|间接依赖|pip|
|ivy||间接依赖|pip|
|Literal||间接依赖|pip|
|Optional||间接依赖|pip|
|Callable||间接依赖|pip|
|assume||间接依赖|pip|
|with_unsupported_dtypes||间接依赖|pip|
|optional_gpu.txt||间接依赖|pip|
|get_source_code||间接依赖|pip|
|FunctionType||间接依赖|pip|
|ivy_tests||间接依赖|pip|
|MetaPathFinder||间接依赖|pip|
|networkx|2.8.4|间接依赖|pip|
|Style||间接依赖|pip|
|libc.so.6||间接依赖||
|matplotlib|3.5.2|间接依赖|pip|
|module_from_spec||间接依赖|pip|
|trace_obj||间接依赖|pip|
|optional_applied.txt||间接依赖|pip|
|pymongo|4.3.3|间接依赖|pip|
|requirements.txt||间接依赖|pip|
|scipy|1.8.1|间接依赖|pip|
|hypothesis|6.55.0|间接依赖|pip|
|Union||间接依赖|pip|
|given||间接依赖|pip|
|ModuleType||间接依赖|pip|
|pytest|7.1.2|间接依赖|pip|
|/dev/stdin||间接依赖|pip|
|List||间接依赖|pip|
|tmp.txt||间接依赖|pip|
|multiversion_testing_requirements.txt||间接依赖|pip|
|Loader||间接依赖|pip|
|resolve_name||间接依赖|pip|
|with_supported_dtypes||间接依赖|pip|
|Fore||间接依赖|pip|
|Tuple||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)