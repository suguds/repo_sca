# sirupsen/logrus安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700572220207448064.svg)](https://www.murphysec.com/console/report/1692600014088200192/1700572220207448064)

仓库描述：Structured, pluggable logging for Go.

仓库地址：[https://github.com/sirupsen/logrus](https://github.com/sirupsen/logrus)

| star：23195 | watch：317 | fork：2277 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-06 22:00:32 | 许可证：MIT |
| 最近检测时间：2023-09-10 02:09:58 | 组件总数：4 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google Go 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2022-9049](https://www.oscs1024.com/hd/MPS-2022-9049)|CVE-2022-29526|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|golang.org/x/sys|v0.0.0-20220715151400-c0bba94af5f8|0.1.0|直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|1|Low|
|ISC|1|Low|
|BSD-3-Clause|1|Low|
|MIT|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/magefile/mage|v1.11.0|直接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|golang.org/x/sys|v0.0.0-20220715151400-c0bba94af5f8|直接依赖|go|
|github.com/stretchr/testify|v1.7.0|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)