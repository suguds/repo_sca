# google/wire安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699486319700131840.svg)](https://www.murphysec.com/console/report/1692962932844810240/1699486319700131840)

仓库描述：Compile-time Dependency Injection for Go

仓库地址：[https://github.com/google/wire](https://github.com/google/wire)

| star：11217 | watch：109 | fork：612 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-05 20:49:02 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-07 02:15:07 | 组件总数：6 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google Go 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2022-9049](https://www.oscs1024.com/hd/MPS-2022-9049)|CVE-2022-29526|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|golang.org/x/sys|v0.0.0-20210216224549-f992740a1bac|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|1|Low|
|BSD-3-Clause|5|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/google/subcommands|v1.2.0|直接依赖|go|
|golang.org/x/mod|v0.4.1|间接依赖|go|
|github.com/google/go-cmp|v0.2.0|直接依赖|go|
|golang.org/x/sys|v0.0.0-20210216224549-f992740a1bac|间接依赖|go|
|golang.org/x/tools|v0.1.0|直接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)