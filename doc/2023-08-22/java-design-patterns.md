# iluwatar/java-design-patterns安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1693684547102531584.svg)](https://www.murphysec.com/console/report/1693684547064782848/1693684547102531584)

仓库描述：Design patterns implemented in Java

仓库地址：[https://github.com/iluwatar/java-design-patterns](https://github.com/iluwatar/java-design-patterns)

| star：83312 | watch：3819 | fork：25408 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-21 02:23:13 | 许可证：NOASSERTION |
| 最近检测时间：2023-08-22 02:04:32 | 组件总数：183 | 漏洞总数：26 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google protobuf 缓冲区错误漏洞|越界写入|[MPS-2017-10841](https://www.oscs1024.com/hd/MPS-2017-10841)|CVE-2015-5237|高危|
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|Eclipse Jetty URI注入漏洞|注入|[MPS-2022-18060](https://www.oscs1024.com/hd/MPS-2022-18060)|CVE-2022-2047|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|ZK Framework 敏感信息泄漏漏洞|未授权敏感信息泄露|[MPS-2022-52192](https://www.oscs1024.com/hd/MPS-2022-52192)|CVE-2022-36537|中危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|Spring Security通配符路由绕过漏洞|关键资源权限分配不当|[MPS-2022-62832](https://www.oscs1024.com/hd/MPS-2022-62832)|CVE-2023-20860|高危|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|H2 数据库明文密码问题|未授权敏感信息泄露|[MPS-2022-65204](https://www.oscs1024.com/hd/MPS-2022-65204)|CVE-2022-45868|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Apache Commons FileUpload <1.5 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2023-3553](https://www.oscs1024.com/hd/MPS-2023-3553)|CVE-2023-24998|中危|
|netplex json-smart 安全漏洞|未经控制的递归|[MPS-2023-7760](https://www.oscs1024.com/hd/MPS-2023-7760)|CVE-2023-1370|高危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.zkoss.zk:zk|9.0.0|9.6.2|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.google.protobuf:protobuf-java|3.0.2|3.21.7|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|org.yaml:snakeyaml|1.30|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|org.springframework.boot:spring-boot-autoconfigure|2.7.5|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.33|2.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|3.0.2|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|commons-fileupload:commons-fileupload|1.3.3|1.5|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-web|5.3.23|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.4.2|2.14.0-rc1|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|net.minidev:json-smart|2.4.8|2.4.9|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-webmvc|5.3.23|6.0.7|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-expression|5.3.23|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.guava:guava|20.0|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|org.springframework:spring-core|5.3.23|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|6.0.4|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-http|9.4.49.v20220914|11.0.10|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|commons-io:commons-io|2.2|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.h2database:h2|2.1.214||直接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.guava:guava|30.1-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-core|6.0.4|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|EPL-1.0|6|Low|
|Apache-2.0|119|Low|
|自定义许可证|23|Low|
|EPL-2.0|12|Low|
|LGPL-3.0|6|Medium|
|MPL-2.0|2|Low|
|MIT|11|Low|
|CDDL-1.1|1|Low|
|LGPL-2.1|1|Medium|
|MPL-1.1|1|Low|
|LGPL-2.1-or-later|4|Low|
|BSD-3-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|ch.qos.logback:logback-classic|1.2.11|直接依赖|maven|
|com.google.guava:guava|30.1-jre|间接依赖|maven|
|org.springframework:spring-expression|5.3.23|间接依赖|maven|
|com.google.jsinterop:jsinterop-annotations|1.0.0|间接依赖|maven|
|net.sourceforge.htmlunit:htmlunit-cssparser|1.14.0|间接依赖|maven|
|commons-pool:commons-pool|1.6|间接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|org.eclipse.jetty:jetty-client|9.4.49.v20220914|间接依赖|maven|
|org.apache.httpcomponents:httpmime|4.5.13|间接依赖|maven|
|org.zkoss.common:zweb|9.0.0|间接依赖|maven|
|org.springframework:spring-jcl|6.0.4|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.2|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.3.4|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|jakarta.persistence:jakarta.persistence-api|3.1.0|间接依赖|maven|
|org.zkoss.zk:zkbind|9.0.0|直接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.49.v20220914|间接依赖|maven|
|org.springframework:spring-aop|5.3.23|间接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|2.3.7|直接依赖|maven|
|jakarta.transaction:jakarta.transaction-api|2.0.1|间接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|com.h2database:h2|2.1.214|直接依赖|maven|
|org.slf4j:slf4j-api|2.0.6|间接依赖|maven|
|org.hamcrest:hamcrest|2.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|3.0.2|直接依赖|maven|
|net.sourceforge.htmlunit:htmlunit|2.70.0|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.7.5|间接依赖|maven|
|net.sourceforge.htmlunit:htmlunit-xpath|2.70.0|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.15|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-test|2.7.5|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.4|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|3.0.2|间接依赖|maven|
|javax.persistence:javax.persistence-api|2.2|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.1|间接依赖|maven|
|com.google.inject:guice|5.1.0|直接依赖|maven|
|org.jboss.spec.javax.transaction:jboss-transaction-api_1.2_spec|1.1.1.Final|间接依赖|maven|
|org.mongodb:mongodb-driver-core|4.6.1|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.19.0|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-params|5.8.2|间接依赖|maven|
|args4j:args4j|2.33|间接依赖|maven|
|org.mongodb:mongodb-driver-sync|4.6.1|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-client|9.4.49.v20220914|间接依赖|maven|
|org.springframework:spring-expression|6.0.4|间接依赖|maven|
|org.springframework:spring-aop|6.0.4|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.5|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.11|直接依赖|maven|
|org.brotli:dec|0.1.2|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.4|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|直接依赖|maven|
|org.apache-extras.beanshell:bsh|2.0b6|间接依赖|maven|
|org.springframework.boot:spring-boot|3.0.2|间接依赖|maven|
|org.springframework.data:spring-data-commons|3.0.1|间接依赖|maven|
|org.javassist:javassist|3.18.2-GA|间接依赖|maven|
|com.sun.istack:istack-commons-runtime|3.0.12|间接依赖|maven|
|com.vaadin.external.google:android-json|0.0.20131108.vaadin1|间接依赖|maven|
|org.hibernate.common:hibernate-commons-annotations|6.0.2.Final|间接依赖|maven|
|org.springframework:spring-orm|6.0.4|间接依赖|maven|
|jakarta.servlet:jakarta.servlet-api|5.0.0|直接依赖|maven|
|ch.qos.logback:logback-classic|1.4.5|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|3.0.2|间接依赖|maven|
|ch.qos.logback:logback-core|1.4.5|间接依赖|maven|
|org.springframework:spring-core|6.0.4|间接依赖|maven|
|com.google.javascript:closure-compiler-externs|v20170626|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.68|间接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.68|间接依赖|maven|
|org.jboss:jandex|2.4.2.Final|间接依赖|maven|
|org.mongodb:mongodb-driver-legacy|4.6.1|直接依赖|maven|
|org.springframework:spring-beans|6.0.4|间接依赖|maven|
|org.springframework:spring-web|5.3.23|间接依赖|maven|
|org.glassfish.jaxb:txw2|2.3.7|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.19.0|间接依赖|maven|
|org.springframework.boot:spring-boot-test|2.7.5|间接依赖|maven|
|org.zkoss.zk:zul|9.0.0|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.23|直接依赖|maven|
|org.mongodb:bson|4.6.1|直接依赖|maven|
|org.objenesis:objenesis|3.2|间接依赖|maven|
|org.springframework.data:spring-data-jpa|2.7.5|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|org.springframework:spring-aspects|6.0.4|间接依赖|maven|
|net.java.dev.swing-layout:swing-layout|1.0.2|直接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|com.google.javascript:closure-compiler-unshaded|v20170626|间接依赖|maven|
|net.sourceforge.htmlunit:neko-htmlunit|2.70.0|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|直接依赖|maven|
|org.springframework.boot:spring-boot-test-autoconfigure|2.7.5|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.5|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.4|间接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|4.0.1|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|com.sun.istack:istack-commons-runtime|4.1.1|间接依赖|maven|
|commons-io:commons-io|2.10.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.7.5|间接依赖|maven|
|org.slf4j:slf4j-jdk14|1.7.36|间接依赖|maven|
|com.sun.activation:jakarta.activation|1.2.2|间接依赖|maven|
|jakarta.inject:jakarta.inject-api|2.0.0|间接依赖|maven|
|com.shapesecurity:salvation2|3.0.1|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-common|9.4.49.v20220914|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.4|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.68|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.4|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.3|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.22|间接依赖|maven|
|org.springframework.boot:spring-boot|2.7.5|间接依赖|maven|
|com.google.guava:guava|20.0|间接依赖|maven|
|com.zaxxer:HikariCP|5.0.1|间接依赖|maven|
|org.hibernate:hibernate-core|5.6.12.Final|直接依赖|maven|
|org.projectlombok:lombok|1.18.24|直接依赖|maven|
|org.zkoss.common:zcommon|9.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|3.0.2|间接依赖|maven|
|org.mockito:mockito-junit-jupiter|4.5.1|间接依赖|maven|
|org.zkoss.zk:zkwebfragment|9.0.0|间接依赖|maven|
|org.springframework.data:spring-data-jpa|3.0.1|间接依赖|maven|
|org.springframework:spring-tx|6.0.4|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|org.mockito:mockito-core|4.5.1|间接依赖|maven|
|org.assertj:assertj-core|3.22.0|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-api|9.4.49.v20220914|间接依赖|maven|
|com.google.code.gson:gson|2.10.1|直接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.3.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.7.5|间接依赖|maven|
|commons-dbcp:commons-dbcp|1.4|直接依赖|maven|
|org.ow2.asm:asm|9.1|间接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.5.0.Final|间接依赖|maven|
|commons-io:commons-io|2.2|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.2|间接依赖|maven|
|org.zkoss.common:zel|9.0.0|间接依赖|maven|
|org.springframework.data:spring-data-commons|2.7.5|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.18|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|org.springframework:spring-context|6.0.4|间接依赖|maven|
|org.aspectj:aspectjweaver|1.9.19|间接依赖|maven|
|org.springframework:spring-beans|5.3.23|间接依赖|maven|
|org.apache.commons:commons-text|1.10.0|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|org.springframework:spring-jcl|5.3.23|间接依赖|maven|
|org.springframework:spring-context|5.3.23|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.2|间接依赖|maven|
|org.yaml:snakeyaml|1.30|间接依赖|maven|
|org.zkoss.zk:zk|9.0.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.4.2|直接依赖|maven|
|com.iluwatar:model-view-controller|1.26.0-SNAPSHOT|直接依赖|maven|
|org.skyscreamer:jsonassert|1.5.1|间接依赖|maven|
|net.minidev:json-smart|2.4.8|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-jpa|3.0.2|直接依赖|maven|
|org.hibernate.orm:hibernate-core|6.1.6.Final|间接依赖|maven|
|org.glassfish.jaxb:jaxb-core|4.0.1|间接依赖|maven|
|org.antlr:antlr4-runtime|4.10.1|间接依赖|maven|
|net.bytebuddy:byte-buddy-agent|1.12.18|间接依赖|maven|
|org.junit.jupiter:junit-jupiter|5.8.2|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.49.v20220914|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|org.checkerframework:checker-qual|3.5.0|间接依赖|maven|
|org.springframework:spring-test|5.3.23|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.7.5|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|3.0.2|间接依赖|maven|
|org.springframework:spring-orm|5.3.23|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.0.18|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.0.2|间接依赖|maven|
|org.springframework:spring-jdbc|5.3.23|间接依赖|maven|
|org.mongodb:bson-record-codec|4.6.1|间接依赖|maven|
|net.minidev:accessors-smart|2.4.8|间接依赖|maven|
|commons-fileupload:commons-fileupload|1.3.3|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|间接依赖|maven|
|org.glassfish.jaxb:txw2|4.0.1|间接依赖|maven|
|com.jayway.jsonpath:json-path|2.7.0|间接依赖|maven|
|org.springframework:spring-core|5.3.23|间接依赖|maven|
|org.eclipse.jetty:jetty-http|9.4.49.v20220914|间接依赖|maven|
|commons-net:commons-net|3.9.0|间接依赖|maven|
|antlr:antlr|2.7.7|间接依赖|maven|
|org.joda:joda-money|1.0.1|直接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|2.1.1|间接依赖|maven|
|org.springframework:spring-tx|5.3.23|间接依赖|maven|
|org.xmlunit:xmlunit-core|2.9.0|间接依赖|maven|
|org.hibernate.common:hibernate-commons-annotations|5.1.2.Final|间接依赖|maven|
|org.yaml:snakeyaml|1.33|间接依赖|maven|
|org.springframework:spring-jdbc|6.0.4|间接依赖|maven|
|net.sourceforge.htmlunit:htmlunit-core-js|2.70.0|间接依赖|maven|
|org.slf4j:jul-to-slf4j|2.0.6|间接依赖|maven|
|org.eclipse.angus:angus-activation|1.0.0|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)