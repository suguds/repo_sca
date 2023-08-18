# PlayEdu/PlayEdu安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692597639844876288.svg)](https://www.murphysec.com/console/report/1691055706286739456/1692597639844876288)

仓库描述：PlayEdu 是一款适用于搭建内部培训平台的开源系统，旨在为企业/机构打造自己品牌的内部培训平台。

仓库地址：[https://github.com/PlayEdu/PlayEdu](https://github.com/PlayEdu/PlayEdu)

| star：1680 | watch：15 | fork：265 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-07 08:49:53 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-19 02:02:05 | 组件总数：122 | 漏洞总数：13 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|【存在争议】MybatisPlus <= 3.5.3.1 TenantPlugin 组件 存在 sql 注入漏洞|SQL注入|[MPS-2023-3977](https://www.oscs1024.com/hd/MPS-2023-3977)|CVE-2023-25330|高危|
|hutool <5.8.17 存在反序列化漏洞|反序列化|[MPS-2023-9241](https://www.oscs1024.com/hd/MPS-2023-9241)||高危|
|Hutool createTempFile函数敏感信息泄漏漏洞|未授权敏感信息泄露|[MPS-4soz-eyma](https://www.oscs1024.com/hd/MPS-4soz-eyma)|CVE-2023-33695|中危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|HuTool XML外部实体注入漏洞|XXE|[MPS-xd3s-4gev](https://www.oscs1024.com/hd/MPS-xd3s-4gev)|CVE-2023-3276|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.xerial.snappy:snappy-java|1.1.8.4|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|cn.hutool:hutool-core|5.8.16|5.8.20|直接依赖|建议修复|C:0|H:1|M:2|L:0|
|com.baomidou:mybatis-plus-extension|3.5.3||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.15.2||间接依赖|建议修复|C:0|H:0|M:1|L:0|
|io.netty:netty-handler|4.1.94.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.squareup.okio:okio-jvm|3.0.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.33|2.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.bouncycastle:bcprov-jdk15on|1.69||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|30.1.1-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|99|Low|
|EPL-2.0|3|Low|
|MIT|6|Low|
|MIT-0|1|Low|
|EPL-1.0|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|io.lettuce:lettuce-core|6.2.4.RELEASE|间接依赖|maven|
|com.baomidou:mybatis-plus|3.5.3|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-validation|3.1.1|直接依赖|maven|
|org.mybatis:mybatis|3.5.11|间接依赖|maven|
|io.jsonwebtoken:jjwt-gson|0.11.5|直接依赖|maven|
|org.springframework:spring-beans|6.0.10|间接依赖|maven|
|cn.hutool:hutool-http|5.8.16|直接依赖|maven|
|org.springframework:spring-context-support|6.0.10|间接依赖|maven|
|org.springframework:spring-context|6.0.10|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.15.2|间接依赖|maven|
|com.google.guava:guava|30.1.1-jre|间接依赖|maven|
|org.mybatis:mybatis-spring|3.0.1|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|3.0.2|间接依赖|maven|
|org.springdoc:springdoc-openapi-starter-webmvc-api|2.0.4|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.8.22|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.4|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|2.1.1|间接依赖|maven|
|io.jsonwebtoken:jjwt-impl|0.11.5|直接依赖|maven|
|io.micrometer:micrometer-commons|1.11.1|间接依赖|maven|
|org.webjars:swagger-ui|4.18.1|间接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|org.springframework.data:spring-data-redis|3.1.1|间接依赖|maven|
|org.springframework:spring-webmvc|6.0.10|间接依赖|maven|
|com.carrotsearch.thirdparty:simple-xml-safe|2.7.1|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|10.1.10|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.15.2|间接依赖|maven|
|org.springframework:spring-messaging|6.0.10|间接依赖|maven|
|io.netty:netty-transport|4.1.94.Final|间接依赖|maven|
|io.swagger.core.v3:swagger-models-jakarta|2.2.8|间接依赖|maven|
|org.springframework.data:spring-data-commons|3.1.1|间接依赖|maven|
|cn.dev33:sa-token-spring-boot3-starter|1.34.0|直接依赖|maven|
|org.projectlombok:lombok|1.18.28|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|3.1.1|直接依赖|maven|
|io.swagger.core.v3:swagger-core-jakarta|2.2.8|间接依赖|maven|
|com.baomidou:mybatis-plus-core|3.5.3|间接依赖|maven|
|jakarta.servlet:jakarta.servlet-api|6.0.0|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.69|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.8.22|间接依赖|maven|
|io.netty:netty-resolver|4.1.94.Final|间接依赖|maven|
|org.aspectj:aspectjweaver|1.9.19|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.94.Final|间接依赖|maven|
|com.squareup.okio:okio-jvm|3.0.0|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|3.1.1|间接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-autoconfigure|3.0.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|3.1.1|间接依赖|maven|
|org.springdoc:springdoc-openapi-starter-webmvc-ui|2.0.4|直接依赖|maven|
|cn.dev33:sa-token-jwt|1.34.0|直接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|com.baomidou:mybatis-plus-boot-starter|3.5.3|直接依赖|maven|
|io.netty:netty-codec|4.1.94.Final|间接依赖|maven|
|org.slf4j:slf4j-api|2.0.7|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.15.2|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|直接依赖|maven|
|io.swagger.core.v3:swagger-annotations-jakarta|2.2.8|间接依赖|maven|
|cn.hutool:hutool-crypto|5.8.9|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.15.2|间接依赖|maven|
|com.baomidou:mybatis-plus-annotation|3.5.3|间接依赖|maven|
|org.springframework:spring-web|6.0.10|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|10.1.10|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.15.2|间接依赖|maven|
|com.squareup.okhttp3:okhttp|4.10.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|3.1.1|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|3.1.1|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.20.0|间接依赖|maven|
|cn.hutool:hutool-jwt|5.8.9|间接依赖|maven|
|org.springframework:spring-aop|6.0.10|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|8.0.0.Final|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.15.2|间接依赖|maven|
|cn.dev33:sa-token-spring-boot-autoconfig|1.34.0|间接依赖|maven|
|org.webjars:webjars-locator-core|0.52|间接依赖|maven|
|io.micrometer:micrometer-observation|1.11.1|间接依赖|maven|
|org.yaml:snakeyaml|1.33|间接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-starter|3.0.1|直接依赖|maven|
|org.springframework:spring-tx|6.0.10|间接依赖|maven|
|io.jsonwebtoken:jjwt-api|0.11.5|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|3.1.1|间接依赖|maven|
|org.springframework.boot:spring-boot-devtools|3.1.1|直接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|io.projectreactor:reactor-core|3.5.7|间接依赖|maven|
|cn.dev33:sa-token-dao-redis-jackson|1.34.0|直接依赖|maven|
|io.netty:netty-buffer|4.1.94.Final|间接依赖|maven|
|io.netty:netty-handler|4.1.94.Final|间接依赖|maven|
|org.checkerframework:checker-qual|3.8.0|间接依赖|maven|
|cn.hutool:hutool-json|5.8.16|直接依赖|maven|
|org.springframework.data:spring-data-keyvalue|3.1.1|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.20.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.8.22|间接依赖|maven|
|ch.qos.logback:logback-classic|1.4.8|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|3.1.1|直接依赖|maven|
|org.springframework:spring-expression|6.0.10|间接依赖|maven|
|com.github.jsqlparser:jsqlparser|4.4|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-redis|3.1.1|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.15.2|间接依赖|maven|
|org.springframework:spring-websocket|6.0.10|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|cn.dev33:sa-token-core|1.34.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.8.22|间接依赖|maven|
|com.zaxxer:HikariCP|5.0.1|间接依赖|maven|
|org.springframework:spring-jdbc|6.0.10|间接依赖|maven|
|org.slf4j:jul-to-slf4j|2.0.7|间接依赖|maven|
|org.springframework.boot:spring-boot|3.1.1|间接依赖|maven|
|org.springdoc:springdoc-openapi-starter-common|2.0.4|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.5.1|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.5.1.Final|间接依赖|maven|
|com.mysql:mysql-connector-j|8.0.33|直接依赖|maven|
|org.apache.commons:commons-compress|1.21|间接依赖|maven|
|ch.qos.logback:logback-core|1.4.8|间接依赖|maven|
|cn.hutool:hutool-core|5.8.16|直接依赖|maven|
|com.baomidou:mybatis-plus-extension|3.5.3|间接依赖|maven|
|io.netty:netty-common|4.1.94.Final|间接依赖|maven|
|com.google.code.gson:gson|2.10.1|直接依赖|maven|
|io.minio:minio|8.5.2|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|10.1.10|间接依赖|maven|
|org.apache.commons:commons-collections4|4.4|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-websocket|3.1.1|直接依赖|maven|
|cn.dev33:sa-token-jakarta-servlet|1.34.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|3.1.1|间接依赖|maven|
|org.springframework:spring-oxm|6.0.10|间接依赖|maven|
|io.github.classgraph:classgraph|4.8.149|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)