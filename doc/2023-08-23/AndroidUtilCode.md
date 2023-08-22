# Blankj/AndroidUtilCode安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694050700652011520.svg)](https://www.murphysec.com/console/report/1692598955136667648/1694050700652011520)

仓库描述：:fire: Android developers should collect the following utils(updating).

仓库地址：[https://github.com/Blankj/AndroidUtilCode](https://github.com/Blankj/AndroidUtilCode)

| star：32397 | watch：1182 | fork：10641 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-05-22 09:52:08 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-23 02:43:34 | 组件总数：2 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|commons-io:commons-io|2.6|2.7|直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|commons-io:commons-io|2.6|直接依赖|maven|
|com.blankj:base-transform|1.0|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)