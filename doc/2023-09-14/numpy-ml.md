# ddbourgin/numpy-ml安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1702025131525455872.svg)](https://www.murphysec.com/console/report/1695140161531572224/1702025131525455872)

仓库描述：Machine learning, in numpy

仓库地址：[https://github.com/ddbourgin/numpy-ml](https://github.com/ddbourgin/numpy-ml)

| star：12865 | watch：451 | fork：3402 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-26 07:07:50 | 许可证：GPL-3.0 |
| 最近检测时间：2023-09-14 02:23:22 | 组件总数：11 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|numba 存在拒绝服务漏洞|拒绝服务|[MPS-2022-15007](https://www.oscs1024.com/hd/MPS-2022-15007)||中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|numba|0.45.0|0.49.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|ISC|1|Low|
|自定义许可证|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|MSELoss||间接依赖|pip|
|numba|0.45.0|间接依赖|pip|
|slogdet||间接依赖|pip|
|librosa|0.7.2|间接依赖|pip|
|CrossEntropyLoss||间接依赖|pip|
|inv||间接依赖|pip|
|abstractmethod||间接依赖|pip|
|polygamma||间接依赖|pip|
|ABC||间接依赖|pip|
|llvmlite|0.32.1|间接依赖|pip|
|digamma||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)