# Grt1228/chatgpt-java安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694410366682750976.svg)](https://www.murphysec.com/console/report/1694410366640807936/1694410366682750976)

仓库描述：ChatGPT Java SDK支持流式输出、Gpt插件、联网。支持OpenAI官方所有接口。ChatGPT的Java客户端。OpenAI GPT-3.5-Turb GPT-4  Api Client for Java

仓库地址：[https://github.com/Grt1228/chatgpt-java](https://github.com/Grt1228/chatgpt-java)

| star：2280 | watch：31 | fork：610 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-22 13:52:36 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-24 02:05:00 | 组件总数：17 | 漏洞总数：7 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|hutool 表达式注入漏洞|SQL注入|[MPS-2023-2459](https://www.oscs1024.com/hd/MPS-2023-2459)|CVE-2023-24163|严重|
|Hutool createTempFile函数敏感信息泄漏漏洞|未授权敏感信息泄露|[MPS-4soz-eyma](https://www.oscs1024.com/hd/MPS-4soz-eyma)|CVE-2023-33695|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|hutool <=5.8.17 存在SPEL命令执行风险|代码注入|[MPS-jdrq-1ywv](https://www.oscs1024.com/hd/MPS-jdrq-1ywv)||高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|cn.hutool:hutool-all|5.8.12|5.8.19|直接依赖|建议修复|C:1|H:1|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.3|2.14.0-rc1|直接依赖|建议修复|C:0|H:0|M:3|L:0|
|com.squareup.okio:okio|1.17.2|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|2|Low|
|Apache-2.0|12|Low|
|MIT|3|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|cn.hutool:hutool-all|5.8.12|直接依赖|maven|
|com.squareup.retrofit2:retrofit|2.9.0|直接依赖|maven|
|com.squareup.okhttp3:okhttp|3.14.9|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.3|间接依赖|maven|
|com.knuddels:jtokkit|0.5.0|直接依赖|maven|
|org.slf4j:slf4j-api|2.0.6|直接依赖|maven|
|com.squareup.retrofit2:adapter-rxjava2|2.9.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.3|间接依赖|maven|
|com.squareup.retrofit2:converter-jackson|2.9.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.3|直接依赖|maven|
|org.projectlombok:lombok|1.18.24|直接依赖|maven|
|com.squareup.okhttp3:logging-interceptor|3.14.9|直接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|io.reactivex.rxjava2:rxjava|2.0.0|间接依赖|maven|
|com.squareup.okio:okio|1.17.2|间接依赖|maven|
|com.squareup.okhttp3:okhttp-sse|3.14.9|直接依赖|maven|
|org.jetbrains:annotations|RELEASE|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)