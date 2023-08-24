# chrieke/prettymapp安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694776824285261824.svg)](https://www.murphysec.com/console/report/1694776824029409280/1694776824285261824)

仓库描述：🖼️ Create beautiful maps from OpenStreetMap data in a streamlit webapp

仓库地址：[https://github.com/chrieke/prettymapp](https://github.com/chrieke/prettymapp)

| star：1391 | watch：4 | fork：60 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-24 23:18:14 | 许可证：MIT |
| 最近检测时间：2023-08-25 02:25:21 | 组件总数：13 | 漏洞总数：1 |

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
|MIT|5|Low|
|GPL-2.0-or-later|1|Low|
|BSD-3-Clause|1|Low|
|自定义许可证|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|prettymapp||间接依赖|pip|
|BytesIO||间接依赖|pip|
|GeoCodingError||间接依赖|pip|
|pylint|2.8.3|间接依赖|pip|
|get_aoi||间接依赖|pip|
|streamlit-image-select|0.6.0|间接依赖|pip|
|StringIO||间接依赖|pip|
|osmnx|1.2.3|间接依赖|pip|
|numpy|1.23.5|间接依赖|pip|
|mypy|0.902|间接依赖|pip|
|matplotlib|3.6.2|间接依赖|pip|
|streamlit|1.25.0|间接依赖|pip|
|mock||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)