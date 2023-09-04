# ali-bouali/spring-boot-3-jwt-security安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698759285051883520.svg)](https://www.murphysec.com/console/report/1698759285005746176/1698759285051883520)

仓库描述：Sample project on how to implement JWT security based using Spring boot 3 and Spring security 6

仓库地址：[https://github.com/ali-bouali/spring-boot-3-jwt-security](https://github.com/ali-bouali/spring-boot-3-jwt-security)

| star：959 | watch：18 | fork：484 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-30 11:25:31 | 许可证：- |
| 最近检测时间：2023-09-05 02:06:40 | 组件总数：79 | 漏洞总数：8 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Spring Security Logout实现不当|会话固定|[MPS-2022-62834](https://www.oscs1024.com/hd/MPS-2022-62834)|CVE-2023-20862|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Spring Security 路径匹配漏洞|不恰当实现的标准安全检查|[MPS-j3nx-691g](https://www.oscs1024.com/hd/MPS-j3nx-691g)|CVE-2023-34034|严重|
|Spring Security鉴权规则错误配置风险|关键资源权限分配不当|[MPS-l6z0-dktm](https://www.oscs1024.com/hd/MPS-l6z0-dktm)|CVE-2023-34035|高危|
|Apache Tomcat FORM 重定向漏洞|跨站重定向|[MPS-uy56-j8e4](https://www.oscs1024.com/hd/MPS-uy56-j8e4)|CVE-2023-41080|低危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.yaml:snakeyaml|1.33|2.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.tomcat.embed:tomcat-embed-core|10.1.7|11.0.0-m6|间接依赖|建议修复|C:0|H:0|M:0|L:1|
|org.springframework.security:spring-security-web|6.0.2|6.1.2|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework.security:spring-security-config|6.0.2|6.1.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.14.2||间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework.boot:spring-boot-autoconfigure|3.0.5|3.0.7|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-expression|6.0.7|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|60|Low|
|自定义许可证|8|Low|
|MIT|4|Low|
|BSD-2-Clause|1|Low|
|LGPL-2.1-or-later|2|Low|
|EPL-2.0|4|Low|
|EPL-1.0|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|jakarta.inject:jakarta.inject-api|2.0.0|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.14.2|间接依赖|maven|
|io.micrometer:micrometer-observation|1.10.5|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.19.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|3.0.5|间接依赖|maven|
|io.jsonwebtoken:jjwt-impl|0.11.5|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|3.0.5|间接依赖|maven|
|org.springframework:spring-tx|6.0.7|间接依赖|maven|
|org.yaml:snakeyaml|1.33|间接依赖|maven|
|com.sun.istack:istack-commons-runtime|4.1.1|间接依赖|maven|
|org.springframework:spring-context|6.0.7|间接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|4.0.2|间接依赖|maven|
|org.antlr:antlr4-runtime|4.10.1|间接依赖|maven|
|org.slf4j:slf4j-api|2.0.7|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|3.0.5|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|3.0.2|间接依赖|maven|
|org.checkerframework:checker-qual|3.5.0|间接依赖|maven|
|org.eclipse.angus:angus-activation|2.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|3.0.5|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-security|3.0.5|直接依赖|maven|
|org.springframework.boot:spring-boot-starter|3.0.5|间接依赖|maven|
|io.swagger.core.v3:swagger-models-jakarta|2.2.9|间接依赖|maven|
|com.zaxxer:HikariCP|5.0.1|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.14.2|间接依赖|maven|
|org.springframework:spring-aop|6.0.7|间接依赖|maven|
|org.webjars:swagger-ui|4.18.2|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.23|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|10.1.7|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|3.0.5|直接依赖|maven|
|org.springdoc:springdoc-openapi-starter-common|2.1.0|间接依赖|maven|
|org.springframework:spring-aspects|6.0.7|间接依赖|maven|
|org.springframework:spring-jdbc|6.0.7|间接依赖|maven|
|org.slf4j:jul-to-slf4j|2.0.7|间接依赖|maven|
|org.springframework:spring-orm|6.0.7|间接依赖|maven|
|org.glassfish.jaxb:txw2|4.0.2|间接依赖|maven|
|org.postgresql:postgresql|42.5.4|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.14.2|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|8.0.0.Final|间接依赖|maven|
|org.projectlombok:lombok|1.18.26|直接依赖|maven|
|org.hibernate.common:hibernate-commons-annotations|6.0.6.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-validation|3.0.5|直接依赖|maven|
|org.jboss:jandex|2.4.2.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|3.0.5|间接依赖|maven|
|org.springdoc:springdoc-openapi-starter-webmvc-api|2.1.0|间接依赖|maven|
|org.glassfish.jaxb:jaxb-core|4.0.2|间接依赖|maven|
|jakarta.transaction:jakarta.transaction-api|2.0.1|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.19.0|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|2.1.1|间接依赖|maven|
|org.springframework:spring-beans|6.0.7|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|10.1.7|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.5.0.Final|间接依赖|maven|
|org.aspectj:aspectjweaver|1.9.19|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.14.2|间接依赖|maven|
|io.jsonwebtoken:jjwt-api|0.11.5|直接依赖|maven|
|org.springframework.security:spring-security-web|6.0.2|间接依赖|maven|
|org.springframework:spring-expression|6.0.7|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.14.2|间接依赖|maven|
|org.springframework.data:spring-data-jpa|3.0.4|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|org.springframework.security:spring-security-config|6.0.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|3.0.5|间接依赖|maven|
|org.springframework:spring-webmvc|6.0.7|间接依赖|maven|
|io.micrometer:micrometer-commons|1.10.5|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|10.1.7|间接依赖|maven|
|jakarta.persistence:jakarta.persistence-api|3.1.0|间接依赖|maven|
|org.hibernate.orm:hibernate-core|6.1.7.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-jpa|3.0.5|直接依赖|maven|
|org.springdoc:springdoc-openapi-starter-webmvc-ui|2.1.0|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.14.2|间接依赖|maven|
|org.springframework.data:spring-data-commons|3.0.4|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.14.2|间接依赖|maven|
|io.jsonwebtoken:jjwt-jackson|0.11.5|直接依赖|maven|
|ch.qos.logback:logback-core|1.4.6|间接依赖|maven|
|ch.qos.logback:logback-classic|1.4.6|间接依赖|maven|
|org.springframework:spring-web|6.0.7|间接依赖|maven|
|io.swagger.core.v3:swagger-core-jakarta|2.2.9|间接依赖|maven|
|org.springframework.boot:spring-boot|3.0.5|间接依赖|maven|
|io.swagger.core.v3:swagger-annotations-jakarta|2.2.9|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)