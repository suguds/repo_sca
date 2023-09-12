# aws/aws-sdk-go安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1701659429308252160.svg)](https://www.murphysec.com/console/report/1701659429228560384/1701659429308252160)

仓库描述：AWS SDK for the Go programming language.

仓库地址：[https://github.com/aws/aws-sdk-go](https://github.com/aws/aws-sdk-go)

| star：8405 | watch：254 | fork：2115 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-12 23:04:44 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-13 02:11:13 | 组件总数：3 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58307](https://www.oscs1024.com/hd/MPS-2022-58307)|CVE-2022-41723|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|golang.org/x/net|v0.1.0|0.7.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|1|Low|
|Apache-2.0|1|Low|
|BSD-2-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|golang.org/x/net|v0.1.0|直接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|直接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)