# alibaba/COLA安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1691873129792299008.svg)](https://www.murphysec.com/console/report/1691873128450121728/1691873129792299008)

仓库描述：🥤 COLA: Clean Object-oriented & Layered Architecture

仓库地址：[https://github.com/alibaba/COLA](https://github.com/alibaba/COLA)

| star：10263 | watch：337 | fork：2730 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-07-21 03:06:09 | 许可证：- |
| 最近检测时间：2023-08-17 02:03:09 | 组件总数：64 | 漏洞总数：15 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|MPS-2020-0057|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|MPS-2022-5144|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|MPS-2022-56040|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|MPS-2022-56041|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|MPS-2022-56051|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
|MPS-2022-56081|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|MPS-2022-58478|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|MPS-2022-58653|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
|MPS-2022-62832|关键资源权限分配不当|[MPS-2022-62832](https://www.oscs1024.com/hd/MPS-2022-62832)|CVE-2023-20860|高危|
|MPS-2022-62833|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|MPS-2022-62835|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|MPS-2022-62855|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|MPS-2022-68556||[MPS-2022-68556](https://www.oscs1024.com/hd/MPS-2022-68556)|CVE-2023-21971|中危|
|MPS-2022-9425|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|MPS-z1bx-p8y2|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.fasterxml.jackson.core:jackson-databind|2.13.4.2|2.14.0-rc1|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.mysql:mysql-connector-j|8.0.31|8.0.33|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.yaml:snakeyaml|1.30|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|org.springframework:spring-webmvc|5.3.23|6.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-web|5.3.23|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.7.5|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-expression|5.3.23|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-core|5.3.23|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|43|Low|
|EPL-1.0|3|Low|
|LGPL-2.1|4|Medium|
|EPL-2.0|3|Low|
|MIT|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.mybatis.spring.boot:mybatis-spring-boot-starter|2.2.2|直接依赖|maven|
|org.springframework:spring-core|5.3.23|间接依赖|maven|
|org.springframework:spring-jdbc|5.3.23|间接依赖|maven|
|com.alibaba.craftsman:craftsman-client|1.0.0-SNAPSHOT|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.68|间接依赖|maven|
|com.alibaba.craftsman:craftsman-adapter|1.0.0-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.4|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.11|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.68|间接依赖|maven|
|org.springframework:spring-web|5.3.23|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.5|间接依赖|maven|
|org.springframework:spring-context|5.3.23|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.23|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.2|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|间接依赖|maven|
|org.yaml:snakeyaml|1.30|间接依赖|maven|
|junit:junit|4.13.2|直接依赖|maven|
|com.alibaba.cola:cola-component-domain-starter|4.4.0-SNAPSHOT|直接依赖|maven|
|org.glassfish:jakarta.el|3.0.4|直接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.3.Final|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.7.5|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|2.7.5|直接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.7.5|间接依赖|maven|
|com.alibaba.craftsman:craftsman-domain|1.0.0-SNAPSHOT|直接依赖|maven|
|com.alibaba.craftsman:craftsman-infrastructure|1.0.0-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.4|间接依赖|maven|
|com.alibaba.cola:cola-component-exception|4.4.0-SNAPSHOT|直接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.5|直接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.2.5.Final|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.4|间接依赖|maven|
|org.springframework:spring-aop|5.3.23|间接依赖|maven|
|org.springframework:spring-expression|5.3.23|间接依赖|maven|
|com.alibaba.cola:cola-component-catchlog-starter|4.4.0-SNAPSHOT|直接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|org.mybatis:mybatis|3.5.9|间接依赖|maven|
|org.mybatis:mybatis-spring|2.0.7|间接依赖|maven|
|javax.validation:validation-api|2.0.1.Final|直接依赖|maven|
|org.hamcrest:hamcrest-core|2.2|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.2|间接依赖|maven|
|javax.el:javax.el-api|3.0.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.4.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.7.5|间接依赖|maven|
|com.mysql:mysql-connector-j|8.0.31|直接依赖|maven|
|org.springframework.boot:spring-boot|2.7.5|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.4|间接依赖|maven|
|org.springframework:spring-tx|5.3.23|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.7.5|直接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-autoconfigure|2.2.2|间接依赖|maven|
|org.springframework:spring-jcl|5.3.23|间接依赖|maven|
|com.alibaba:fastjson|1.2.83|直接依赖|maven|
|org.aspectj:aspectjweaver|1.9.7|间接依赖|maven|
|org.hamcrest:hamcrest|2.2|间接依赖|maven|
|com.alibaba.cola:cola-component-dto|4.4.0-SNAPSHOT|直接依赖|maven|
|com.alibaba.craftsman:craftsman-app|1.0.0-SNAPSHOT|直接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.68|间接依赖|maven|
|org.springframework:spring-beans|5.3.23|间接依赖|maven|
|commons-cli:commons-cli|1.5.0|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|ch.qos.logback:logback-classic|1.2.11|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.4|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.7.5|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)