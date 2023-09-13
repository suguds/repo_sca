# modelscope/facechain安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1702023547165736960.svg)](https://www.murphysec.com/console/report/1691514706958635008/1702023547165736960)

仓库描述：FaceChain is a deep-learning toolchain for generating your Digital-Twin.

仓库地址：[https://github.com/modelscope/facechain](https://github.com/modelscope/facechain)

| star：5045 | watch：59 | fork：442 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-14 02:06:13 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-14 02:17:03 | 组件总数：4 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|NumPy 安全漏洞|不充分的比较|[MPS-2021-25631](https://www.oscs1024.com/hd/MPS-2021-25631)|CVE-2021-34141|中危|
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|numpy|1.22.0|1.22.2|间接依赖|可选修复|C:0|H:0|M:2|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|1|Low|
|BSD-3-Clause|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|controlnet_aux|0.0.6|间接依赖|pip|
|mmdet|2.26.0|间接依赖|pip|
|numpy|1.22.0|间接依赖|pip|
|protobuf|3.20.1|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)