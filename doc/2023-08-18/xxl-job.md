# xuxueli/xxl-job安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692236437516079104.svg)](https://www.murphysec.com/console/report/1692236437373472768/1692236437516079104)

仓库描述：A distributed task scheduling framework.（分布式任务调度平台XXL-JOB）

仓库地址：[https://github.com/xuxueli/xxl-job](https://github.com/xuxueli/xxl-job)

| star：24993 | watch：948 | fork：10325 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-16 17:23:34 | 许可证：GPL-3.0 |
| 最近检测时间：2023-08-18 02:06:49 | 组件总数：73 | 漏洞总数：18 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
|Spring Security通配符路由绕过漏洞|关键资源权限分配不当|[MPS-2022-62832](https://www.oscs1024.com/hd/MPS-2022-62832)|CVE-2023-20860|高危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot在Cloud Foundry中部署存在路由限制绕过风险|访问控制不当|[MPS-2022-62845](https://www.oscs1024.com/hd/MPS-2022-62845)|CVE-2023-20873|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|Oracle MySQL 安全漏洞||[MPS-2022-68556](https://www.oscs1024.com/hd/MPS-2022-68556)|CVE-2023-21971|中危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|XXL-JOB 跨站请求伪造漏洞|CSRF|[MPS-2023-3818](https://www.oscs1024.com/hd/MPS-2023-3818)|CVE-2023-0674|中危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.springframework.boot:spring-boot-autoconfigure|2.7.9|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.mysql:mysql-connector-j|8.0.32|8.0.33|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|io.netty:netty-handler|4.1.90.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-webmvc|5.3.25|6.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.7.9|3.0.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.30|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|com.fasterxml.jackson.core:jackson-databind|2.13.5|2.14.0-rc1|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|io.netty:netty-handler|4.1.89.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-web|5.3.25|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework:spring-expression|5.3.25|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.xuxueli:xxl-job-core|2.4.1-SNAPSHOT||直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|61|Low|
|EPL-2.0|2|Low|
|EPL-1.0|2|Low|
|MIT|3|Low|
|BSD-2-Clause|1|Low|
|GPL-3.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.google.code.gson:gson|2.9.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-mail|2.7.9|直接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.9|间接依赖|maven|
|io.netty:netty-codec|4.1.89.Final|间接依赖|maven|
|io.netty:netty-resolver|4.1.90.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.7.9|间接依赖|maven|
|io.netty:netty-handler|4.1.90.Final|间接依赖|maven|
|com.sun.activation:jakarta.activation|1.2.2|间接依赖|maven|
|io.netty:netty-resolver|4.1.89.Final|间接依赖|maven|
|io.micrometer:micrometer-core|1.9.8|间接依赖|maven|
|org.mybatis:mybatis|3.5.11|间接依赖|maven|
|io.netty:netty-buffer|4.1.89.Final|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.11|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.71|间接依赖|maven|
|io.netty:netty-common|4.1.89.Final|间接依赖|maven|
|org.springframework:spring-jdbc|5.3.25|间接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.2|间接依赖|maven|
|org.springframework:spring-web|5.3.25|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator|2.7.9|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.11|间接依赖|maven|
|org.freemarker:freemarker|2.3.32|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.5|间接依赖|maven|
|io.netty:netty-codec|4.1.90.Final|间接依赖|maven|
|org.springframework:spring-context|5.3.25|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.5|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.7.9|间接依赖|maven|
|io.netty:netty-common|4.1.90.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-actuator|2.7.9|直接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|org.apache.groovy:groovy|4.0.10|直接依赖|maven|
|org.springframework.boot:spring-boot|2.7.9|间接依赖|maven|
|com.sun.mail:jakarta.mail|1.6.7|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.7.9|直接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.9|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.89.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.5|间接依赖|maven|
|org.slf4j:slf4j-reload4j|1.7.36|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.5|间接依赖|maven|
|org.springframework:spring-context-support|5.3.25|间接依赖|maven|
|org.springframework:spring-tx|5.3.25|间接依赖|maven|
|io.netty:netty-transport|4.1.89.Final|间接依赖|maven|
|ch.qos.reload4j:reload4j|1.2.19|间接依赖|maven|
|org.mybatis:mybatis-spring|2.1.0|间接依赖|maven|
|org.yaml:snakeyaml|1.30|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.5|间接依赖|maven|
|io.netty:netty-codec-http|4.1.90.Final|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-freemarker|2.7.9|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.7.9|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.25|间接依赖|maven|
|io.netty:netty-transport|4.1.90.Final|间接依赖|maven|
|com.xuxueli:xxl-job-core|2.4.1-SNAPSHOT|直接依赖|maven|
|org.springframework:spring-beans|5.3.25|间接依赖|maven|
|com.google.code.gson:gson|2.10.1|直接依赖|maven|
|com.mysql:mysql-connector-j|8.0.32|直接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.90.Final|间接依赖|maven|
|io.netty:netty-buffer|4.1.90.Final|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.2|间接依赖|maven|
|org.springframework:spring-expression|5.3.25|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.71|间接依赖|maven|
|io.netty:netty-handler|4.1.89.Final|间接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.7.9|间接依赖|maven|
|org.springframework:spring-aop|5.3.25|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.71|间接依赖|maven|
|io.netty:netty-codec-http|4.1.89.Final|间接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-starter|2.3.0|直接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-autoconfigure|2.3.0|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.5|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.7.9|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)