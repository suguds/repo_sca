# oddfar/campus-imaotai安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696584561164378112.svg)](https://www.murphysec.com/console/report/1695859133184897024/1696584561164378112)

仓库描述：i茅台app自动预约，每日自动预约，支持docker一键部署

仓库地址：[https://github.com/oddfar/campus-imaotai](https://github.com/oddfar/campus-imaotai)

| star：342 | watch：5 | fork：81 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-25 11:46:07 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-30 02:04:53 | 组件总数：131 | 漏洞总数：37 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|kaptcha Random随机性不足漏洞|使用不充分的随机数|[MPS-2018-13971](https://www.oscs1024.com/hd/MPS-2018-13971)|CVE-2018-18531|严重|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|Apache Commons Compress 安存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10550](https://www.oscs1024.com/hd/MPS-2021-10550)|CVE-2021-35517|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10551](https://www.oscs1024.com/hd/MPS-2021-10551)|CVE-2021-35516|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10564](https://www.oscs1024.com/hd/MPS-2021-10564)|CVE-2021-36090|高危|
|Apache Commons Compress 无限循环漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-10565](https://www.oscs1024.com/hd/MPS-2021-10565)|CVE-2021-35515|高危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|io.springfox:springfox-swagger2 存在输入验证不恰当漏洞|日志敏感信息泄露|[MPS-2022-12534](https://www.oscs1024.com/hd/MPS-2022-12534)||中危|
|JetBrains Kotlin <1.6.0 存在锁定不当漏洞|加锁机制不恰当|[MPS-2022-3233](https://www.oscs1024.com/hd/MPS-2022-3233)|CVE-2022-24329|中危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|Spring Security通配符路由绕过漏洞|关键资源权限分配不当|[MPS-2022-62832](https://www.oscs1024.com/hd/MPS-2022-62832)|CVE-2023-20860|高危|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|Hutool 存在拒绝服务漏洞|越界写入|[MPS-2022-64976](https://www.oscs1024.com/hd/MPS-2022-64976)|CVE-2022-45688|中危|
|Hutool 存在拒绝服务漏洞|越界写入|[MPS-2022-64977](https://www.oscs1024.com/hd/MPS-2022-64977)|CVE-2022-45689|中危|
|Hutool 存在拒绝服务漏洞|越界写入|[MPS-2022-64978](https://www.oscs1024.com/hd/MPS-2022-64978)|CVE-2022-45690|中危|
|Hutool zip 拒绝服务漏洞||[MPS-2022-68308](https://www.oscs1024.com/hd/MPS-2022-68308)|CVE-2022-4565|中危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|hutool 表达式注入漏洞|SQL注入|[MPS-2023-2459](https://www.oscs1024.com/hd/MPS-2023-2459)|CVE-2023-24163|严重|
|hutool 存在反序列化漏洞|反序列化|[MPS-2023-2460](https://www.oscs1024.com/hd/MPS-2023-2460)|CVE-2023-24162|高危|
|Apache Commons FileUpload <1.5 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2023-3553](https://www.oscs1024.com/hd/MPS-2023-3553)|CVE-2023-24998|中危|
|【存在争议】MybatisPlus <= 3.5.3.1 TenantPlugin 组件 存在 sql 注入漏洞|SQL注入|[MPS-2023-3977](https://www.oscs1024.com/hd/MPS-2023-3977)|CVE-2023-25330|高危|
|hutool 存在任意代码执行漏洞|代码注入|[MPS-2023-7335](https://www.oscs1024.com/hd/MPS-2023-7335)||严重|
|Hutool createTempFile函数敏感信息泄漏漏洞|未授权敏感信息泄露|[MPS-4soz-eyma](https://www.oscs1024.com/hd/MPS-4soz-eyma)|CVE-2023-33695|中危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|hutool <=5.8.17 存在SPEL命令执行风险|代码注入|[MPS-jdrq-1ywv](https://www.oscs1024.com/hd/MPS-jdrq-1ywv)||高危|
|HuTool XML外部实体注入漏洞|XXE|[MPS-xd3s-4gev](https://www.oscs1024.com/hd/MPS-xd3s-4gev)|CVE-2023-3276|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|cn.hutool:hutool-all|5.8.8|5.8.19|直接依赖|强烈建议修复|C:1|H:2|M:1|L:0|
|com.baomidou:mybatis-plus-extension|3.5.2||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|commons-fileupload:commons-fileupload|1.4|1.5|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.yaml:snakeyaml|1.28|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|org.apache.commons:commons-compress|1.19|1.21|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.12.6.1|2.14.0-rc1|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|org.springframework:spring-webmvc|5.3.20|6.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.77.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-web|5.3.20|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|commons-io:commons-io|2.2|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.github.penggle:kaptcha|2.3.2||直接依赖|可选修复|C:1|H:0|M:0|L:0|
|org.jetbrains.kotlin:kotlin-stdlib|1.5.32|1.6.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.springfox:springfox-swagger2|3.0.0||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|5.3.20|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.5.14|3.0.7|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-core|5.3.20|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|109|Low|
|EPL-1.0|2|Low|
|MIT|7|Low|
|自定义许可证|8|Low|
|EPL-2.0|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.fasterxml.jackson.core:jackson-core|2.12.6|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.11|间接依赖|maven|
|io.netty:netty-codec|4.1.77.Final|间接依赖|maven|
|org.springframework:spring-jcl|5.3.20|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.2|间接依赖|maven|
|io.netty:netty-common|4.1.77.Final|间接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-starter|2.2.2|间接依赖|maven|
|io.swagger.core.v3:swagger-models|2.1.2|间接依赖|maven|
|org.apache.poi:poi-ooxml-schemas|4.1.2|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.12.6|间接依赖|maven|
|io.swagger.core.v3:swagger-annotations|2.1.2|间接依赖|maven|
|com.github.penggle:kaptcha|2.3.2|直接依赖|maven|
|org.mapstruct:mapstruct|1.5.3.Final|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.63|间接依赖|maven|
|io.springfox:springfox-swagger2|3.0.0|间接依赖|maven|
|org.projectlombok:lombok|1.18.24|直接依赖|maven|
|org.mybatis:mybatis|3.5.9|间接依赖|maven|
|org.springframework:spring-aop|5.3.20|间接依赖|maven|
|com.baomidou:mybatis-plus|3.5.2|间接依赖|maven|
|org.apache.poi:poi-ooxml|4.1.2|直接依赖|maven|
|com.alibaba.fastjson2:fastjson2|2.0.14|直接依赖|maven|
|javax.servlet:javax.servlet-api|4.0.1|直接依赖|maven|
|io.swagger:swagger-annotations|1.6.2|间接依赖|maven|
|com.github.jsqlparser:jsqlparser|4.2|间接依赖|maven|
|com.jhlabs:filters|2.0.235-1|间接依赖|maven|
|org.springframework.security:spring-security-core|5.5.8|间接依赖|maven|
|org.springframework:spring-tx|5.3.20|间接依赖|maven|
|commons-io:commons-io|2.2|间接依赖|maven|
|com.oddfar.campus:campus-admin|1.0.7|直接依赖|maven|
|org.springframework.data:spring-data-keyvalue|2.5.11|间接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.5.32|间接依赖|maven|
|org.springframework:spring-beans|5.3.20|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.10.22|间接依赖|maven|
|com.baomidou:mybatis-plus-boot-starter|3.5.2|直接依赖|maven|
|mysql:mysql-connector-java|8.0.29|直接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|直接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.5.14|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.5.14|直接依赖|maven|
|org.springframework.data:spring-data-commons|2.5.11|间接依赖|maven|
|javax.activation:activation|1.1|间接依赖|maven|
|com.baomidou:mybatis-plus-core|3.5.2|间接依赖|maven|
|org.springframework:spring-expression|5.3.20|间接依赖|maven|
|com.zaxxer:SparseBitSet|1.2|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.5.32|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.5.14|间接依赖|maven|
|org.springframework:spring-jdbc|5.3.20|间接依赖|maven|
|com.baomidou:mybatis-plus-annotation|3.5.2|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.20|间接依赖|maven|
|com.github.virtuald:curvesapi|1.06|间接依赖|maven|
|org.springframework:spring-web|5.3.20|间接依赖|maven|
|org.apache.commons:commons-math3|3.6.1|间接依赖|maven|
|org.apache.xmlbeans:xmlbeans|3.1.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|2.5.14|直接依赖|maven|
|io.netty:netty-buffer|4.1.77.Final|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.11|间接依赖|maven|
|io.netty:netty-transport|4.1.77.Final|间接依赖|maven|
|io.netty:netty-handler|4.1.77.Final|间接依赖|maven|
|org.springframework.security:spring-security-crypto|5.5.8|间接依赖|maven|
|io.springfox:springfox-schema|3.0.0|间接依赖|maven|
|org.apache.commons:commons-pool2|2.9.0|直接依赖|maven|
|org.springframework.data:spring-data-redis|2.5.11|间接依赖|maven|
|org.springframework:spring-context|5.3.20|间接依赖|maven|
|io.netty:netty-resolver|4.1.77.Final|间接依赖|maven|
|org.yaml:snakeyaml|1.28|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|io.springfox:springfox-spring-webflux|3.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.5.14|间接依赖|maven|
|io.springfox:springfox-spi|3.0.0|间接依赖|maven|
|org.springframework:spring-core|5.3.20|间接依赖|maven|
|org.springframework:spring-context-support|5.3.20|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.5.32|间接依赖|maven|
|io.springfox:springfox-spring-web|3.0.0|间接依赖|maven|
|io.springfox:springfox-swagger-ui|3.0.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.12.6|间接依赖|maven|
|org.springframework.security:spring-security-web|5.5.8|间接依赖|maven|
|io.springfox:springfox-bean-validators|3.0.0|间接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|eu.bitwalker:UserAgentUtils|1.21|直接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.2.3.Final|间接依赖|maven|
|org.aspectj:aspectjweaver|1.9.7|间接依赖|maven|
|io.springfox:springfox-boot-starter|3.0.0|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-security|2.5.14|直接依赖|maven|
|com.github.pagehelper:pagehelper-spring-boot-starter|1.4.3|直接依赖|maven|
|org.apache.commons:commons-compress|1.19|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.63|间接依赖|maven|
|io.swagger:swagger-models|1.6.2|直接依赖|maven|
|org.springframework.plugin:spring-plugin-core|2.0.0.RELEASE|间接依赖|maven|
|io.springfox:springfox-swagger-common|3.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-validation|2.5.14|直接依赖|maven|
|org.springframework.plugin:spring-plugin-metadata|2.0.0.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.5.14|间接依赖|maven|
|io.springfox:springfox-spring-webmvc|3.0.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.12.6.1|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|com.github.pagehelper:pagehelper|5.3.1|间接依赖|maven|
|io.springfox:springfox-core|3.0.0|间接依赖|maven|
|commons-fileupload:commons-fileupload|1.4|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.12.6|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|com.github.pagehelper:pagehelper-spring-boot-autoconfigure|1.4.3|间接依赖|maven|
|io.springfox:springfox-oas|3.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-redis|2.5.14|直接依赖|maven|
|io.github.classgraph:classgraph|4.8.83|间接依赖|maven|
|com.baomidou:mybatis-plus-extension|3.5.2|间接依赖|maven|
|org.springframework.security:spring-security-config|5.5.8|间接依赖|maven|
|org.springframework:spring-oxm|5.3.20|间接依赖|maven|
|io.projectreactor:reactor-core|3.4.18|间接依赖|maven|
|org.springframework.boot:spring-boot|2.5.14|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.3.Final|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|com.sun.mail:javax.mail|1.6.2|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|间接依赖|maven|
|io.lettuce:lettuce-core|6.1.8.RELEASE|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.2|间接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-autoconfigure|2.2.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.5.14|间接依赖|maven|
|io.jsonwebtoken:jjwt|0.9.1|直接依赖|maven|
|com.oddfar.campus:campus-framework|1.0.7|直接依赖|maven|
|org.apache.poi:poi|4.1.2|间接依赖|maven|
|com.oddfar.campus:campus-common|1.0.7|直接依赖|maven|
|org.apache.commons:commons-collections4|4.4|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.5.14|间接依赖|maven|
|cn.hutool:hutool-all|5.8.8|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.12.6|间接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.63|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.5.32|间接依赖|maven|
|org.mybatis:mybatis-spring|2.0.7|间接依赖|maven|
|io.springfox:springfox-data-rest|3.0.0|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)