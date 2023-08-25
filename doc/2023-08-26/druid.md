# alibaba/druid安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695135213633232896.svg)](https://www.murphysec.com/console/report/1684752185495937024/1695135213633232896)

仓库描述：阿里云计算平台DataWorks(https://help.aliyun.com/document_detail/137663.html) 团队出品，为监控而生的数据库连接池

仓库地址：[https://github.com/alibaba/druid](https://github.com/alibaba/druid)

| star：27149 | watch：1728 | fork：8467 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-16 23:41:56 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-26 02:57:54 | 组件总数：111 | 漏洞总数：19 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|PostgreSQL JDBC 存在 SQL 注入漏洞|SQL注入|[MPS-2022-11227](https://www.oscs1024.com/hd/MPS-2022-11227)|CVE-2022-31197|高危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|pgjdbc <42.5.1 存在信息泄露漏洞|不安全的临时文件|[MPS-2022-58583](https://www.oscs1024.com/hd/MPS-2022-58583)|CVE-2022-41946|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|Spring Security通配符路由绕过漏洞|关键资源权限分配不当|[MPS-2022-62832](https://www.oscs1024.com/hd/MPS-2022-62832)|CVE-2023-20860|高危|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot在Cloud Foundry中部署存在路由限制绕过风险|访问控制不当|[MPS-2022-62845](https://www.oscs1024.com/hd/MPS-2022-62845)|CVE-2023-20873|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|H2 数据库明文密码问题|未授权敏感信息泄露|[MPS-2022-65204](https://www.oscs1024.com/hd/MPS-2022-65204)|CVE-2022-45868|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.springframework:spring-webmvc|5.3.22|6.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.7.3|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.30|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|org.springframework.boot:spring-boot-autoconfigure|3.0.6|3.0.7|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|1.5.22.RELEASE|3.0.7|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.3|2.14.0-rc1|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.postgresql:postgresql|42.3.6|42.5.1|直接依赖|建议修复|C:0|H:1|M:1|L:0|
|org.springframework:spring-web|5.3.22|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.7.3|3.0.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-core|5.3.22|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.h2database:h2|2.1.214||直接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-expression|5.3.22|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|76|Low|
|自定义许可证|16|Low|
|BSD-2-Clause|2|Low|
|MPL-2.0|1|Low|
|EPL-1.0|3|Low|
|MIT|8|Low|
|LGPL-2.1-or-later|2|Low|
|EPL-2.0|4|Low|
|LGPL-2.1|1|Medium|
|MPL-1.1|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.springframework:spring-orm|5.3.22|间接依赖|maven|
|antlr:antlr|2.7.7|间接依赖|maven|
|org.glassfish.jaxb:txw2|2.3.6|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.1|间接依赖|maven|
|org.ehcache:ehcache|3.10.0|直接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|间接依赖|maven|
|org.springframework.boot:spring-boot|2.7.3|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.3|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.3|间接依赖|maven|
|org.springframework.data:spring-data-commons|2.7.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.7.3|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.3|间接依赖|maven|
|com.alibaba:druid|1.2.19-SNAPSHOT|直接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|com.h2database:h2|2.1.214|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|2.7.3|间接依赖|maven|
|org.jboss:jandex|2.4.2.Final|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.2|间接依赖|maven|
|com.fasterxml.jackson:jackson-bom|2.13.3|间接依赖|maven|
|org.postgresql:postgresql|42.3.6|直接依赖|maven|
|org.springframework.boot:spring-boot-actuator|2.7.3|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.2|间接依赖|maven|
|org.slf4j:slf4j-api|2.0.7|直接依赖|maven|
|org.springframework:spring-jcl|6.0.8|间接依赖|maven|
|org.hibernate:hibernate-core|5.6.10.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|3.0.6|直接依赖|maven|
|org.springframework:spring-expression|6.0.8|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.3|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.22|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.13|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.9|间接依赖|maven|
|io.micrometer:micrometer-core|1.9.3|间接依赖|maven|
|org.checkerframework:checker-qual|3.5.0|直接依赖|maven|
|org.thymeleaf:thymeleaf-spring5|3.0.15.RELEASE|间接依赖|maven|
|org.springframework:spring-context|5.3.22|间接依赖|maven|
|org.springframework:spring-context-support|5.3.22|间接依赖|maven|
|com.sun.activation:jakarta.activation|1.2.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-cache|2.7.3|直接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|2.3.6|间接依赖|maven|
|org.springframework:spring-beans|5.3.22|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.3|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.26|直接依赖|maven|
|ch.qos.logback:logback-core|1.2.11|间接依赖|maven|
|mysql:mysql-connector-java|8.0.30|直接依赖|maven|
|org.springframework:spring-core|5.3.22|间接依赖|maven|
|org.aspectj:aspectjweaver|1.9.7|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.2.4.Final|间接依赖|maven|
|javax.cache:cache-api|1.1.1|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.3|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.3|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|间接依赖|maven|
|org.hibernate.common:hibernate-commons-annotations|5.1.2.Final|间接依赖|maven|
|org.springframework:spring-aspects|5.3.22|间接依赖|maven|
|com.alibaba:druid-spring-boot-starter|1.2.19-SNAPSHOT|直接依赖|maven|
|org.springframework.boot:spring-boot|3.0.6|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.65|间接依赖|maven|
|jakarta.transaction:jakarta.transaction-api|1.3.3|间接依赖|maven|
|org.glassfish.jaxb:txw2|2.3.2|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.65|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-jpa|2.7.3|直接依赖|maven|
|org.springframework:spring-context|6.0.8|间接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime||间接依赖|maven|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.7.3|间接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|org.thymeleaf:thymeleaf|3.0.15.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.7.3|直接依赖|maven|
|org.springframework:spring-expression|5.3.22|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-validation|2.7.3|直接依赖|maven|
|org.javassist:javassist|3.20.0-GA|间接依赖|maven|
|org.springframework:spring-core|6.0.8|间接依赖|maven|
|org.springframework:spring-beans|6.0.8|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.7.3|间接依赖|maven|
|org.springframework:spring-web|5.3.22|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-actuator|2.7.3|直接依赖|maven|
|com.sun.istack:istack-commons-runtime|3.0.12|间接依赖|maven|
|org.yaml:snakeyaml|1.30|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.65|间接依赖|maven|
|org.attoparser:attoparser|2.0.5.RELEASE|间接依赖|maven|
|org.springframework:spring-jdbc|5.3.22|间接依赖|maven|
|ognl:ognl|3.1.26|间接依赖|maven|
|org.webjars.npm:font-awesome|4.7.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.3|间接依赖|maven|
|com.sun.xml.fastinfoset:FastInfoset|1.2.16|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.3.Final|间接依赖|maven|
|io.github.classgraph:classgraph|4.8.139|间接依赖|maven|
|org.webjars:webjars-locator-core|0.50|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.7.3|间接依赖|maven|
|org.springframework:spring-tx|5.3.22|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.11|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|1.5.22.RELEASE|直接依赖|maven|
|org.springframework.boot:spring-boot-devtools|2.7.3|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-thymeleaf|2.7.3|直接依赖|maven|
|org.springframework:spring-jcl|5.3.22|间接依赖|maven|
|org.jvnet.staxex:stax-ex|1.8.1|间接依赖|maven|
|org.webjars.npm:bootstrap|5.1.3|直接依赖|maven|
|com.sun.istack:istack-commons-runtime|3.0.8|间接依赖|maven|
|org.springframework:spring-aop|5.3.22|间接依赖|maven|
|org.thymeleaf.extras:thymeleaf-extras-java8time|3.0.4.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.3|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|org.springframework:spring-aop|6.0.8|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.7.3|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.1|间接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|2.3.2|直接依赖|maven|
|jakarta.persistence:jakarta.persistence-api|2.2.3|间接依赖|maven|
|org.springframework.data:spring-data-jpa|2.7.2|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|org.unbescape:unbescape|1.1.6.RELEASE|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)