# serverless/serverless安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696954908266622976.svg)](https://www.murphysec.com/console/report/1696954906853142528/1696954908266622976)

仓库描述：⚡ Serverless Framework – Build web, mobile and IoT applications with serverless architectures using AWS Lambda, Azure Functions, Google CloudFunctions & more! – 

仓库地址：[https://github.com/serverless/serverless](https://github.com/serverless/serverless)

| star：45099 | watch：959 | fork：5678 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-30 20:32:32 | 许可证：MIT |
| 最近检测时间：2023-08-31 02:36:12 | 组件总数：9 | 漏洞总数：6 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|FasterXML Jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2022-12500](https://www.oscs1024.com/hd/MPS-2022-12500)||中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2023-8438](https://www.oscs1024.com/hd/MPS-2023-8438)|CVE-2021-46877|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.fasterxml.jackson.core:jackson-databind|2.11.0|2.14.0-rc1|直接依赖|建议修复|C:0|H:1|M:5|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|8|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.amazonaws:aws-lambda-java-core|1.2.1|直接依赖|maven|
|com.google.code.gson:gson|2.8.9|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-joda|2.11.0|直接依赖|maven|
|com.amazonaws:aws-lambda-java-events|3.1.1|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.11.0|直接依赖|maven|
|strftime||间接依赖|pip|
|com.fasterxml.jackson.core:jackson-core|2.11.0|直接依赖|maven|
|joda-time:joda-time|2.6|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.11.0|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)