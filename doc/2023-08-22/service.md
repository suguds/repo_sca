# kardianos/service安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1693687711649918976.svg)](https://www.murphysec.com/console/report/1693687711545061376/1693687711649918976)

仓库描述：Run go programs as a service on major platforms.

仓库地址：[https://github.com/kardianos/service](https://github.com/kardianos/service)

| star：4034 | watch：103 | fork：643 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-06-27 19:50:35 | 许可证：Zlib |
| 最近检测时间：2023-08-22 02:13:15 | 组件总数：1 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google Go 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2022-9049](https://www.oscs1024.com/hd/MPS-2022-9049)|CVE-2022-29526|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|golang.org/x/sys|v0.0.0-20201015000850-e3ed0017c211|0.1.0|直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|golang.org/x/sys|v0.0.0-20201015000850-e3ed0017c211|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)