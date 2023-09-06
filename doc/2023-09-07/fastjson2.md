# alibaba/fastjson2安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699483141277532160.svg)](https://www.murphysec.com/console/report/1693939345974452224/1699483141277532160)

仓库描述：🚄 FASTJSON2 is a Java JSON  library with excellent performance.

仓库地址：[https://github.com/alibaba/fastjson2](https://github.com/alibaba/fastjson2)

| star：2985 | watch：31 | fork：406 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-06 22:40:19 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-07 02:15:46 | 组件总数：133 | 漏洞总数：11 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|hutool 表达式注入漏洞|SQL注入|[MPS-2023-2459](https://www.oscs1024.com/hd/MPS-2023-2459)|CVE-2023-24163|严重|
|Apache Tomcat FORM 重定向漏洞|跨站重定向|[MPS-uy56-j8e4](https://www.oscs1024.com/hd/MPS-uy56-j8e4)|CVE-2023-41080|低危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.yaml:snakeyaml|1.33|2.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.15.2||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-web|5.3.28|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|cn.hutool:hutool-all|5.8.21||直接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.yaml:snakeyaml|1.30|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|org.apache.tomcat.embed:tomcat-embed-core|10.1.10|11.0.0-m6|间接依赖|建议修复|C:0|H:0|M:0|L:1|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.76|11.0.0-m6|间接依赖|建议修复|C:0|H:0|M:0|L:1|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|109|Low|
|EPL-2.0|2|Low|
|MIT|6|Low|
|BSD-3-Clause|8|Low|
|自定义许可证|8|Low|
|EPL-1.0|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.springframework:spring-webmvc|6.0.10|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.2|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.1.Final|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|org.springframework.boot:spring-boot-devtools|2.7.13|直接依赖|maven|
|org.springframework:spring-beans|6.0.10|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|2.1.1|间接依赖|maven|
|org.checkerframework:checker-qual|3.33.0|间接依赖|maven|
|com.esotericsoftware:minlog|1.3.1|间接依赖|maven|
|org.slf4j:slf4j-api|2.0.6|间接依赖|maven|
|io.github.wycst:wast|0.0.10.2|直接依赖|maven|
|joda-time:joda-time|2.12.5|间接依赖|maven|
|com.alibaba.fastjson2:fastjson2-extension-spring6|2.0.41-SNAPSHOT|直接依赖|maven|
|com.alibaba.fastjson2:fastjson2-codegen|2.0.41-SNAPSHOT|直接依赖|maven|
|com.esotericsoftware:kryo|5.5.0|直接依赖|maven|
|org.springframework:spring-messaging|5.3.28|间接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j2-impl|2.20.0|间接依赖|maven|
|org.yaml:snakeyaml|2.0|间接依赖|maven|
|org.springframework:spring-web|5.3.28|间接依赖|maven|
|org.springframework.boot:spring-boot-devtools|3.1.1|直接依赖|maven|
|github.com/twitchyliquid64/golang-asm|v0.15.1|间接依赖|go|
|org.springframework:spring-context|6.0.10|间接依赖|maven|
|org.springframework:spring-beans|5.3.28|间接依赖|maven|
|org.springframework:spring-expression|6.0.10|间接依赖|maven|
|com.google.guava:guava|32.1.2-jre|间接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|org.springframework:spring-aop|6.0.10|间接依赖|maven|
|org.furyio:fury-core|0.1.1|直接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|com.alibaba:fastjson|1.2.83|直接依赖|maven|
|org.springframework.boot:spring-boot|3.1.1|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.15.2|间接依赖|maven|
|org.springframework:spring-context|5.3.28|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.15.2|直接依赖|maven|
|org.apache.logging.log4j:log4j-jul|2.20.0|间接依赖|maven|
|org.apache.arrow:arrow-format|13.0.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.20.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.2|间接依赖|maven|
|org.springframework.boot:spring-boot-configuration-processor|3.1.1|直接依赖|maven|
|org.msgpack:jackson-dataformat-msgpack|0.9.5|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.76|间接依赖|maven|
|org.springframework:spring-aop|5.3.28|间接依赖|maven|
|com.alibaba.fastjson2:fastjson2-extension-spring5|2.0.41-SNAPSHOT|直接依赖|maven|
|com.alibaba.fastjson2:fastjson2-incubator-vector|2.0.41-SNAPSHOT|直接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|org.yaml:snakeyaml|1.33|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.2.5.Final|间接依赖|maven|
|org.objenesis:objenesis|3.3|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|com.dslplatform:dsl-json|2.0.2|直接依赖|maven|
|commons-io:commons-io|2.13.0|直接依赖|maven|
|github.com/klauspost/cpuid/v2|v2.0.9|间接依赖|go|
|org.apache.commons:commons-math3|3.6.1|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.24.2|直接依赖|maven|
|org.springframework:spring-jcl|6.0.10|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|间接依赖|maven|
|net.minidev:accessors-smart|2.5.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.7.13|间接依赖|maven|
|org.springframework:spring-websocket|5.3.28|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-websocket|2.7.13|直接依赖|maven|
|net.sourceforge.javacsv:javacsv|2.0|直接依赖|maven|
|com.google.j2objc:j2objc-annotations|2.8|间接依赖|maven|
|com.caucho:hessian|4.0.66|直接依赖|maven|
|io.netty:netty-common|4.1.96.Final|间接依赖|maven|
|io.micrometer:micrometer-commons|1.10.8|间接依赖|maven|
|org.ow2.asm:asm|9.5|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-validation|3.1.1|直接依赖|maven|
|com.jayway.jsonpath:json-path|2.8.0|直接依赖|maven|
|org.apache.commons:commons-lang3|3.13.0|直接依赖|maven|
|golang.org/x/arch|v0.0.0-20210923205945-b76863e36670|间接依赖|go|
|org.apache.arrow:arrow-memory-core|13.0.0|间接依赖|maven|
|com.esotericsoftware:reflectasm|1.11.9|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.20.0|间接依赖|maven|
|net.minidev:json-smart|2.5.0|间接依赖|maven|
|com.damnhandy:handy-uri-templates|2.1.8|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.13|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|3.1.1|直接依赖|maven|
|org.springframework:spring-expression|5.3.28|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.15.2|间接依赖|maven|
|org.springframework:spring-core|6.0.10|间接依赖|maven|
|com.google.code.gson:gson|2.10.1|直接依赖|maven|
|org.springframework:spring-websocket|6.0.10|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.12|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.7.13|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.15.2|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|net.sf.jopt-simple:jopt-simple|5.0.4|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|10.1.10|间接依赖|maven|
|cn.hutool:hutool-all|5.8.21|直接依赖|maven|
|org.springframework:spring-webmvc|5.3.28|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.12|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-validation|2.7.13|直接依赖|maven|
|org.springframework.boot:spring-boot|2.7.13|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|8.0.0.Final|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|3.0.2|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.76|间接依赖|maven|
|github.com/bytedance/sonic|v1.7.0|直接依赖|go|
|org.apache.tomcat.embed:tomcat-embed-core|10.1.10|间接依赖|maven|
|com.networknt:json-schema-validator|1.0.86|直接依赖|maven|
|org.openjdk.jmh:jmh-core|1.37|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.7.13|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|3.1.1|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|3.1.1|间接依赖|maven|
|org.springframework:spring-messaging|6.0.10|间接依赖|maven|
|com.google.re2j:re2j|1.6|间接依赖|maven|
|org.apache.arrow:arrow-vector|13.0.0|直接依赖|maven|
|com.github.erosb:everit-json-schema|1.14.2|直接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|org.springframework:spring-web|6.0.10|间接依赖|maven|
|github.com/chenzhuoyu/base64x|v0.0.0-20221115062448-fe3a3abad311|间接依赖|go|
|org.springframework.boot:spring-boot-autoconfigure|2.7.13|间接依赖|maven|
|com.alibaba.fastjson2:fastjson2-extension|2.0.41-SNAPSHOT|直接依赖|maven|
|io.micrometer:micrometer-observation|1.10.8|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-log4j2|3.1.1|直接依赖|maven|
|commons-validator:commons-validator|1.7|间接依赖|maven|
|org.springframework.boot:spring-boot-configuration-processor|2.7.13|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.15.2|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.76|间接依赖|maven|
|com.alibaba.fastjson2:fastjson2|2.0.41-SNAPSHOT|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|3.1.1|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|10.1.10|间接依赖|maven|
|com.ethlo.time:itu|1.7.0|间接依赖|maven|
|org.yaml:snakeyaml|1.30|间接依赖|maven|
|com.google.flatbuffers:flatbuffers-java|1.12.0|间接依赖|maven|
|org.json:json|20230618|间接依赖|maven|
|com.univocity:univocity-parsers|2.9.1|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-websocket|3.1.1|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.18.0|间接依赖|maven|
|commons-digester:commons-digester|2.1|间接依赖|maven|
|org.msgpack:msgpack-core|0.9.5|直接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)