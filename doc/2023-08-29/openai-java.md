# TheoKanning/openai-java安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696221928057368576.svg)](https://www.murphysec.com/console/report/1696221928015425536/1696221928057368576)

仓库描述：OpenAI Api Client in Java

仓库地址：[https://github.com/TheoKanning/openai-java](https://github.com/TheoKanning/openai-java)

| star：3604 | watch：74 | fork：909 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-26 00:07:49 | 许可证：MIT |
| 最近检测时间：2023-08-29 02:04:56 | 组件总数：20 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.squareup.okio:okio|1.17.2|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.14.2||直接依赖|建议修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|12|Low|
|MIT|3|Low|
|自定义许可证|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.fasterxml.jackson.core:jackson-core|2.14.2|间接依赖|maven|
|com.knuddels:jtokkit|0.5.1|直接依赖|maven|
|::service||直接依赖|maven|
|com.squareup.retrofit2:converter-jackson|2.9.0|直接依赖|maven|
|javax.validation:validation-api|2.0.1.Final|直接依赖|maven|
|com.squareup.retrofit2:adapter-rxjava2|2.9.0|直接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.26|直接依赖|maven|
|com.kjetland:mbknor-jackson-jsonschema||直接依赖|maven|
|com.squareup.retrofit2:retrofit|2.9.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.14.2|直接依赖|maven|
|::client||直接依赖|maven|
|com.fasterxml.jackson:jackson-bom|2.14.2|间接依赖|maven|
|com.squareup.okhttp3:okhttp|3.14.9|间接依赖|maven|
|org.scala-lang:scala-library|2.12.8|直接依赖|maven|
|io.reactivex.rxjava2:rxjava|2.0.0|间接依赖|maven|
|::api||直接依赖|maven|
|io.github.classgraph:classgraph|4.8.21|直接依赖|maven|
|com.squareup.okio:okio|1.17.2|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.14.2|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)