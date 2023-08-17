# novicezk/midjourney-proxy安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692235251604807680.svg)](https://www.murphysec.com/console/report/1692235251311206400/1692235251604807680)

仓库描述：代理 MidJourney 的discord频道，实现api形式调用AI绘图

仓库地址：[https://github.com/novicezk/midjourney-proxy](https://github.com/novicezk/midjourney-proxy)

| star：2664 | watch：27 | fork：1444 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-01 11:54:08 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-18 02:02:43 | 组件总数：96 | 漏洞总数：22 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|io.springfox:springfox-swagger2 存在输入验证不恰当漏洞|日志敏感信息泄露|[MPS-2022-12534](https://www.oscs1024.com/hd/MPS-2022-12534)||中危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
|Spring Security通配符路由绕过漏洞|关键资源权限分配不当|[MPS-2022-62832](https://www.oscs1024.com/hd/MPS-2022-62832)|CVE-2023-20860|高危|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|hutool 表达式注入漏洞|SQL注入|[MPS-2023-2459](https://www.oscs1024.com/hd/MPS-2023-2459)|CVE-2023-24163|严重|
|Hutool createTempFile函数敏感信息泄漏漏洞|未授权敏感信息泄露|[MPS-4soz-eyma](https://www.oscs1024.com/hd/MPS-4soz-eyma)|CVE-2023-33695|中危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|hutool <=5.8.17 存在SPEL命令执行风险|代码注入|[MPS-jdrq-1ywv](https://www.oscs1024.com/hd/MPS-jdrq-1ywv)||高危|
|HuTool XML外部实体注入漏洞|XXE|[MPS-xd3s-4gev](https://www.oscs1024.com/hd/MPS-xd3s-4gev)|CVE-2023-3276|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|io.netty:netty-handler|4.1.85.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.4.2|2.14.0-rc1|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.squareup.okio:okio|1.17.2|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.29|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|org.springframework.boot:spring-boot-autoconfigure|2.6.14|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-webmvc|5.3.24|6.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|cn.hutool:hutool-all|5.8.12|5.8.19|间接依赖|建议修复|C:1|H:1|M:1|L:0|
|org.springframework:spring-web|5.3.24|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework:spring-expression|5.3.24|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|io.springfox:springfox-swagger2|2.10.5||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|cn.hutool:hutool-core|5.8.18|5.8.20|直接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-core|5.3.24|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|81|Low|
|MIT|4|Low|
|EPL-1.0|2|Low|
|LGPL-2.1|2|Medium|
|JSON|1|Low|
|MPL-1.1|1|Low|
|MIT-0|1|Low|
|EPL-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.4|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.2|间接依赖|maven|
|org.springframework.plugin:spring-plugin-metadata|2.0.0.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.6.14|间接依赖|maven|
|org.springframework.data:spring-data-commons|2.6.10|间接依赖|maven|
|com.squareup.retrofit2:retrofit|2.9.0|间接依赖|maven|
|io.springfox:springfox-core|2.10.5|间接依赖|maven|
|io.springfox:springfox-schema|2.10.5|间接依赖|maven|
|org.springframework:spring-beans|5.3.24|间接依赖|maven|
|org.springframework:spring-web|5.3.24|间接依赖|maven|
|com.unfbx:chatgpt-java|1.0.14-beta1|直接依赖|maven|
|io.springfox:springfox-swagger-common|2.10.5|间接依赖|maven|
|org.springframework.data:spring-data-keyvalue|2.6.10|间接依赖|maven|
|org.apache.commons:commons-collections4|4.4|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.24|间接依赖|maven|
|org.springframework:spring-expression|5.3.24|间接依赖|maven|
|io.netty:netty-resolver|4.1.85.Final|间接依赖|maven|
|org.projectlombok:lombok|1.18.24|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.4|间接依赖|maven|
|com.squareup.okhttp3:okhttp|3.14.9|间接依赖|maven|
|org.mapstruct:mapstruct|1.3.1.Final|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.11|间接依赖|maven|
|io.netty:netty-codec|4.1.85.Final|间接依赖|maven|
|org.springframework:spring-context|5.3.24|间接依赖|maven|
|io.springfox:springfox-bean-validators|2.10.5|间接依赖|maven|
|com.squareup.retrofit2:adapter-rxjava2|2.9.0|间接依赖|maven|
|eu.maxschuster:dataurl|2.0.0|直接依赖|maven|
|io.swagger:swagger-annotations|1.6.6|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.69|间接依赖|maven|
|cn.hutool:hutool-all|5.8.12|间接依赖|maven|
|net.sf.trove4j:trove4j|3.0.3|间接依赖|maven|
|io.netty:netty-handler|4.1.85.Final|间接依赖|maven|
|org.springframework:spring-jcl|5.3.24|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.4|间接依赖|maven|
|org.json:json|20220924|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.6.14|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.69|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.6.14|间接依赖|maven|
|io.swagger:swagger-models|1.6.6|间接依赖|maven|
|eu.bitwalker:UserAgentUtils|1.21|直接依赖|maven|
|io.reactivex.rxjava2:rxjava|2.2.21|间接依赖|maven|
|com.squareup.retrofit2:converter-jackson|2.9.0|间接依赖|maven|
|io.springfox:springfox-spi|2.10.5|间接依赖|maven|
|com.knuddels:jtokkit|0.5.0|间接依赖|maven|
|com.neovisionaries:nv-websocket-client|2.14|间接依赖|maven|
|org.springframework:spring-tx|5.3.24|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.69|间接依赖|maven|
|com.squareup.okhttp3:okhttp-sse|3.14.9|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.11|间接依赖|maven|
|org.springframework:spring-oxm|5.3.24|间接依赖|maven|
|io.netty:netty-common|4.1.85.Final|间接依赖|maven|
|com.squareup.okio:okio|1.17.2|间接依赖|maven|
|io.springfox:springfox-swagger2|2.10.5|间接依赖|maven|
|com.github.xiaoymin:knife4j-core|4.1.0|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|io.github.classgraph:classgraph|4.1.7|间接依赖|maven|
|com.squareup.okhttp3:logging-interceptor|3.14.9|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|org.yaml:snakeyaml|1.29|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.4.2|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.4|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.85.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.6.14|间接依赖|maven|
|io.projectreactor:reactor-core|3.4.25|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.11.22|间接依赖|maven|
|com.github.xiaoymin:knife4j-openapi2-ui|4.1.0|间接依赖|maven|
|org.springframework.boot:spring-boot-configuration-processor|2.6.14|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.4|间接依赖|maven|
|io.netty:netty-transport|4.1.85.Final|间接依赖|maven|
|org.jetbrains:annotations|RELEASE|间接依赖|maven|
|net.dv8tion:JDA|5.0.0-beta.9|直接依赖|maven|
|cn.hutool:hutool-cache|5.8.18|直接依赖|maven|
|io.springfox:springfox-spring-web|2.10.5|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.15|间接依赖|maven|
|org.springframework.data:spring-data-redis|2.6.10|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.6.14|间接依赖|maven|
|org.springframework.plugin:spring-plugin-core|2.0.0.RELEASE|间接依赖|maven|
|io.netty:netty-buffer|4.1.85.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-redis|2.6.14|直接依赖|maven|
|cn.hutool:hutool-core|5.8.18|直接依赖|maven|
|org.javassist:javassist|3.25.0-GA|间接依赖|maven|
|com.github.xiaoymin:knife4j-openapi2-spring-boot-starter|4.1.0|直接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|cn.hutool:hutool-crypto|5.8.18|直接依赖|maven|
|io.springfox:springfox-spring-webmvc|2.10.5|间接依赖|maven|
|org.springframework:spring-core|5.3.24|间接依赖|maven|
|org.springframework.boot:spring-boot|2.6.14|间接依赖|maven|
|org.springframework:spring-aop|5.3.24|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.14|直接依赖|maven|
|io.lettuce:lettuce-core|6.1.10.RELEASE|间接依赖|maven|
|org.springframework:spring-context-support|5.3.24|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.6.14|直接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.2|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)