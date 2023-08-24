# spring-projects-experimental/spring-ai安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694772622607675392.svg)](https://www.murphysec.com/console/report/1694772622553149440/1694772622607675392)

仓库描述：The Spring AI project aims to streamline the development of applications that incorporate artificial intelligence functionality without unnecessary complexity.

仓库地址：[https://github.com/spring-projects-experimental/spring-ai](https://github.com/spring-projects-experimental/spring-ai)

| star：79 | watch：10 | fork：10 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-24 03:59:23 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-25 02:06:40 | 组件总数：85 | 漏洞总数：4 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|io.netty:netty-handler|4.1.94.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.squareup.okio:okio-jvm|3.0.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.33|2.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.15.2||间接依赖|建议修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|64|Low|
|EPL-1.0|2|Low|
|自定义许可证|4|Low|
|MIT|11|Low|
|MIT-0|1|Low|
|EPL-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|org.springframework.experimental.ai:spring-ai-core|0.2.0-SNAPSHOT|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|3.1.2|直接依赖|maven|
|com.squareup.retrofit2:adapter-rxjava2|2.9.0|间接依赖|maven|
|ch.qos.logback:logback-core|1.4.8|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|3.1.2|直接依赖|maven|
|io.netty:netty-resolver-dns|4.1.94.Final|间接依赖|maven|
|com.knuddels:jtokkit|0.6.1|直接依赖|maven|
|org.yaml:snakeyaml|1.33|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.8.22|间接依赖|maven|
|io.netty:netty-common|4.1.94.Final|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.8.22|间接依赖|maven|
|com.theokanning.openai-gpt3-java:api|0.12.0|间接依赖|maven|
|com.theokanning.openai-gpt3-java:service|0.12.0|直接依赖|maven|
|com.github.victools:jsonschema-generator|4.31.1|直接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.94.Final|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.8.22|间接依赖|maven|
|com.azure:azure-core-http-netty|1.13.5|间接依赖|maven|
|org.slf4j:jul-to-slf4j|2.0.7|间接依赖|maven|
|org.springframework:spring-jcl|6.0.11|间接依赖|maven|
|io.netty:netty-codec|4.1.94.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-configuration-processor|3.1.2|直接依赖|maven|
|com.azure:azure-ai-openai|1.0.0-beta.3|直接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.20.0|间接依赖|maven|
|io.netty:netty-tcnative-classes|2.0.61.Final|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.94.Final|间接依赖|maven|
|io.netty:netty-tcnative-boringssl-static|2.0.61.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.15.2|间接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.94.Final|间接依赖|maven|
|io.netty:netty-handler|4.1.94.Final|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|io.reactivex.rxjava2:rxjava|2.0.0|间接依赖|maven|
|io.micrometer:micrometer-observation|1.11.2|间接依赖|maven|
|org.slf4j:slf4j-api|2.0.7|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.20.0|间接依赖|maven|
|org.springframework.boot:spring-boot|3.1.2|间接依赖|maven|
|com.squareup.okhttp3:okhttp|4.10.0|间接依赖|maven|
|org.springframework:spring-expression|6.0.11|间接依赖|maven|
|io.netty:netty-buffer|4.1.94.Final|间接依赖|maven|
|org.springframework:spring-core|6.0.11|间接依赖|maven|
|io.micrometer:micrometer-commons|1.11.2|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.94.Final|间接依赖|maven|
|org.springframework.experimental.ai:spring-ai-openai|0.2.0-SNAPSHOT|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.8.22|间接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|2.1.1|间接依赖|maven|
|ch.qos.logback:logback-classic|1.4.8|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|3.1.2|直接依赖|maven|
|org.springframework:spring-beans|6.0.11|间接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.94.Final|间接依赖|maven|
|com.squareup.okio:okio-jvm|3.0.0|间接依赖|maven|
|com.azure:azure-json|1.0.1|间接依赖|maven|
|com.squareup.retrofit2:retrofit|2.9.0|间接依赖|maven|
|org.antlr:antlr-runtime|3.3|间接依赖|maven|
|io.netty:netty-resolver|4.1.94.Final|间接依赖|maven|
|com.squareup.retrofit2:converter-jackson|2.9.0|间接依赖|maven|
|com.theokanning.openai-gpt3-java:client|0.12.0|间接依赖|maven|
|com.github.victools:jsonschema-module-jackson|4.31.1|直接依赖|maven|
|org.springframework:spring-aop|6.0.11|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|3.1.2|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.94.Final|间接依赖|maven|
|org.springframework:spring-web|6.0.11|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.15.2|间接依赖|maven|
|com.azure:azure-core|1.41.0|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.15.2|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.15.2|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-http|1.1.9|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.94.Final|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.15.2|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-core|1.1.9|间接依赖|maven|
|org.springframework:spring-messaging|6.0.11|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.15.2|间接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.94.Final|间接依赖|maven|
|io.netty:netty-codec-http|4.1.94.Final|间接依赖|maven|
|io.projectreactor:reactor-core|3.5.8|间接依赖|maven|
|org.springframework:spring-context-support|6.0.11|直接依赖|maven|
|io.netty:netty-codec-dns|4.1.94.Final|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.94.Final|间接依赖|maven|
|com.azure:azure-core-experimental|1.0.0-beta.41|间接依赖|maven|
|org.springframework.experimental.ai:spring-ai-azure-openai|0.2.0-SNAPSHOT|直接依赖|maven|
|org.springframework:spring-context|6.0.11|间接依赖|maven|
|org.antlr:stringtemplate|4.0.2|直接依赖|maven|
|org.springframework.experimental.ai:spring-ai-spring-boot-autoconfigure|0.2.0-SNAPSHOT|直接依赖|maven|
|io.netty:netty-transport|4.1.94.Final|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.94.Final|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)