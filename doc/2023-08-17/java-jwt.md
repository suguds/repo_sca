# auth0/java-jwt安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1691874054279815168.svg)](https://www.murphysec.com/console/report/1691874053956853760/1691874054279815168)

仓库描述：Java implementation of JSON Web Token (JWT)

仓库地址：[https://github.com/auth0/java-jwt](https://github.com/auth0/java-jwt)

| star：5360 | watch：217 | fork：909 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-16 10:50:55 | 许可证：- |
| 最近检测时间：2023-08-17 02:07:52 | 组件总数：4 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|MPS-z1bx-p8y2|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.fasterxml.jackson.core:jackson-databind|2.14.2||直接依赖|建议修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|4|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.fasterxml.jackson.core:jackson-core|2.14.2|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.14.2|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.14.2|直接依赖|maven|
|com.fasterxml.jackson:jackson-bom|2.14.2|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)