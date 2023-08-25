# alibaba/easyexcel安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695136858404380672.svg)](https://www.murphysec.com/console/report/1692235910114729984/1695136858404380672)

仓库描述：快速、简洁、解决大文件内存溢出的java处理Excel工具

仓库地址：[https://github.com/alibaba/easyexcel](https://github.com/alibaba/easyexcel)

| star：28813 | watch：589 | fork：7192 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-24 01:29:08 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-26 02:13:33 | 组件总数：79 | 漏洞总数：17 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|Apache Commons Compress 安存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10550](https://www.oscs1024.com/hd/MPS-2021-10550)|CVE-2021-35517|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10551](https://www.oscs1024.com/hd/MPS-2021-10551)|CVE-2021-35516|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10564](https://www.oscs1024.com/hd/MPS-2021-10564)|CVE-2021-36090|高危|
|Apache Commons Compress 无限循环漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-10565](https://www.oscs1024.com/hd/MPS-2021-10565)|CVE-2021-35515|高危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|netplex json-smart 安全漏洞|未经控制的递归|[MPS-2023-7760](https://www.oscs1024.com/hd/MPS-2023-7760)|CVE-2023-1370|高危|
|Apache Tomcat 安全漏洞||[MPS-xd4z-oncg](https://www.oscs1024.com/hd/MPS-xd4z-oncg)|CVE-2023-34981|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.apache.commons:commons-compress|1.19|1.21|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.7.11|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.5|2.14.0-rc1|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.74|11.0.0-m6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.30|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|net.minidev:json-smart|2.4.7|2.4.9|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-web|5.3.27|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|59|Low|
|EPL-2.0|7|Low|
|EPL-1.0|2|Low|
|自定义许可证|7|Low|
|MIT|5|Low|
|BSD-3-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.alibaba.fastjson2:fastjson2|2.0.29|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.5|间接依赖|maven|
|org.springframework:spring-context|5.3.27|间接依赖|maven|
|org.yaml:snakeyaml|1.30|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.36|直接依赖|maven|
|com.alibaba:easyexcel-support|3.3.2|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.7.11|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.74|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.7.11|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.7.11|直接依赖|maven|
|org.junit.platform:junit-platform-engine|1.8.2|间接依赖|maven|
|com.vaadin.external.google:android-json|0.0.20131108.vaadin1|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-api|5.8.2|间接依赖|maven|
|net.minidev:json-smart|2.4.7|间接依赖|maven|
|org.springframework:spring-expression|5.3.27|间接依赖|maven|
|org.springframework.boot:spring-boot|2.7.11|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.5|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.2|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.2|间接依赖|maven|
|ch.qos.logback:logback-classic|1.4.7|直接依赖|maven|
|org.opentest4j:opentest4j|1.2.0|间接依赖|maven|
|org.junit.jupiter:junit-jupiter|5.8.2|间接依赖|maven|
|com.jayway.jsonpath:json-path|2.7.0|间接依赖|maven|
|org.springframework:spring-test|5.3.27|间接依赖|maven|
|org.slf4j:slf4j-simple|1.7.36|直接依赖|maven|
|org.assertj:assertj-core|3.22.0|间接依赖|maven|
|com.alibaba:easyexcel-core|3.3.2|直接依赖|maven|
|org.mockito:mockito-core|4.5.1|间接依赖|maven|
|org.apache.poi:poi-ooxml-schemas|4.1.2|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.74|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.5|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-engine|5.8.2|间接依赖|maven|
|org.springframework:spring-web|5.3.27|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.5|间接依赖|maven|
|org.skyscreamer:jsonassert|1.5.1|间接依赖|maven|
|com.zaxxer:SparseBitSet|1.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.11|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.5|间接依赖|maven|
|org.objenesis:objenesis|3.2|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.3|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.11|间接依赖|maven|
|org.apache.commons:commons-collections4|4.4|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.2|间接依赖|maven|
|ch.qos.logback:logback-core|1.4.7|间接依赖|maven|
|org.springframework:spring-aop|5.3.27|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|org.springframework.boot:spring-boot-test-autoconfigure|2.7.11|间接依赖|maven|
|org.springframework:spring-jcl|5.3.27|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.5|间接依赖|maven|
|net.minidev:accessors-smart|2.4.7|间接依赖|maven|
|com.github.virtuald:curvesapi|1.06|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.27|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.74|间接依赖|maven|
|org.apache.commons:commons-compress|1.19|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.7.11|间接依赖|maven|
|net.bytebuddy:byte-buddy-agent|1.12.9|间接依赖|maven|
|commons-codec:commons-codec|1.13|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|org.mockito:mockito-junit-jupiter|4.5.1|间接依赖|maven|
|org.junit.platform:junit-platform-commons|1.8.2|间接依赖|maven|
|org.slf4j:log4j-over-slf4j|1.7.36|直接依赖|maven|
|org.springframework:spring-core|5.3.27|直接依赖|maven|
|commons-io:commons-io|2.11.0|直接依赖|maven|
|org.apache.xmlbeans:xmlbeans|3.1.0|间接依赖|maven|
|org.apache.commons:commons-csv|1.8|直接依赖|maven|
|org.apache.commons:commons-math3|3.6.1|间接依赖|maven|
|org.hamcrest:hamcrest|2.2|间接依赖|maven|
|org.ehcache:ehcache|3.9.9|直接依赖|maven|
|org.apache.poi:poi-ooxml|4.1.2|直接依赖|maven|
|org.springframework:spring-beans|5.3.27|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.32|直接依赖|maven|
|org.ow2.asm:asm|9.1|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-params|5.8.2|间接依赖|maven|
|org.apiguardian:apiguardian-api|1.1.2|间接依赖|maven|
|org.xmlunit:xmlunit-core|2.9.1|间接依赖|maven|
|org.apache.poi:poi|4.1.2|直接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.9|间接依赖|maven|
|org.springframework.boot:spring-boot-test|2.7.11|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-test|2.7.11|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)