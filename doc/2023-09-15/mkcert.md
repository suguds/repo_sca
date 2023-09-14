# FiloSottile/mkcert安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1702384497131651072.svg)](https://www.murphysec.com/console/report/1702384497072930816/1702384497131651072)

仓库描述：A simple zero-config tool to make locally trusted development certificates with any names you'd like.

仓库地址：[https://github.com/FiloSottile/mkcert](https://github.com/FiloSottile/mkcert)

| star：42579 | watch：463 | fork：2252 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-29 16:51:00 | 许可证：BSD-3-Clause |
| 最近检测时间：2023-09-15 02:11:10 | 组件总数：5 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58307](https://www.oscs1024.com/hd/MPS-2022-58307)|CVE-2022-41723|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|golang.org/x/net|v0.0.0-20220421235706-1d1ef9303861|0.7.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|4|Low|
|BSD-2-Clause-Views|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|golang.org/x/text|v0.3.7|间接依赖|go|
|golang.org/x/crypto|v0.0.0-20220331220935-ae2d96664a29|间接依赖|go|
|howett.net/plist|v1.0.0|直接依赖|go|
|software.sslmate.com/src/go-pkcs12|v0.2.0|直接依赖|go|
|golang.org/x/net|v0.0.0-20220421235706-1d1ef9303861|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)