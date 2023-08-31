# apache/kafka安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1697310141497303040.svg)](https://www.murphysec.com/console/report/1695134788212912128/1697310141497303040)

仓库描述：Mirror of Apache Kafka

仓库地址：[https://github.com/apache/kafka](https://github.com/apache/kafka)

| star：25718 | watch：1076 | fork：12983 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-01 01:59:47 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-01 02:21:15 | 组件总数：214 | 漏洞总数：6 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Eclipse Jetty URI注入漏洞|注入|[MPS-2022-18060](https://www.oscs1024.com/hd/MPS-2022-18060)|CVE-2022-2047|低危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
|Eclipse Jetty 资源管理错误漏洞|拒绝服务|[MPS-2023-4997](https://www.oscs1024.com/hd/MPS-2023-4997)|CVE-2023-26048|中危|
|Eclipse Jetty 信息泄露漏洞|XSS|[MPS-2023-4998](https://www.oscs1024.com/hd/MPS-2023-4998)|CVE-2023-26049|中危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.fasterxml.jackson.core:jackson-databind|2.13.5|2.14.0-rc1|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.eclipse.jetty:jetty-server|9.4.51.v20230217|12.0.0.beta0|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|io.netty:netty-handler|4.1.94.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.eclipse.jetty:jetty-http|9.4.51.v20230217|11.0.10|间接依赖|可选修复|C:0|H:0|M:0|L:1|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|115|Low|
|EPL-1.0|10|Low|
|EPL-2.0|39|Low|
|CDDL-1.0|2|Low|
|自定义许可证|24|Low|
|MIT|21|Low|
|GPL-2.0-with-classpath-exception|1|Medium|
|BSD-2-Clause|6|Low|
|LGPL-2.1|2|Medium|
|MPL-1.1|2|Low|
|WTFPL|2|Low|
|GPL-2.0|2|Medium|
|CDDL-1.1|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|commons-digester:commons-digester||直接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.51.v20230217|间接依赖|maven|
|org.glassfish.hk2.external:aopalliance-repackaged|2.6.1|间接依赖|maven|
|:+--- org.bitbucket.b_c:jose4j:0.9.3||直接依赖|maven|
|org.eclipse.jetty:jetty-servlets||直接依赖|maven|
|commons-logging:commons-logging||直接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.13.5|间接依赖|maven|
|::tools:tools-api||直接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|org.eclipse.jetty:jetty-server||直接依赖|maven|
|javax.activation:activation|1.1.1|直接依赖|maven|
|::storage:api||直接依赖|maven|
|commons-validator:commons-validator|1.7|直接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet-core||直接依赖|maven|
|::clients||直接依赖|maven|
|org.jline:jline||直接依赖|maven|
|io.netty:netty-transport-classes-epoll||直接依赖|maven|
|net.sf.jopt-simple:jopt-simple|5.0.4|直接依赖|maven|
|::connect:runtime||直接依赖|maven|
|org.eclipse.jetty:jetty-util-ajax|9.4.51.v20230217|间接依赖|maven|
|org.apache.zookeeper:zookeeper-jute|3.8.2|间接依赖|maven|
|org.apache.commons:commons-lang3||直接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|间接依赖|maven|
|::connect:json||直接依赖|maven|
|org.apache.commons:commons-math3|3.2|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|net.bytebuddy:byte-buddy-agent||直接依赖|maven|
|io.netty:netty-codec|4.1.94.Final|间接依赖|maven|
|org.glassfish.hk2.external:aopalliance-repackaged||直接依赖|maven|
|org.scala-lang:scala-library||直接依赖|maven|
|jakarta.ws.rs:jakarta.ws.rs-api||直接依赖|maven|
|::raft||直接依赖|maven|
|org.glassfish.jersey.core:jersey-client|2.39.1|间接依赖|maven|
|com.thoughtworks.paranamer:paranamer||直接依赖|maven|
|commons-cli:commons-cli||直接依赖|maven|
|org.eclipse.jetty:jetty-util-ajax||直接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.4.51.v20230217|直接依赖|maven|
|org.slf4j:slf4j-log4j12|1.7.36|直接依赖|maven|
|org.slf4j:slf4j-reload4j||直接依赖|maven|
|io.netty:netty-buffer||直接依赖|maven|
|io.swagger.core.v3:swagger-annotations|2.2.8|直接依赖|maven|
|org.lz4:lz4-java||直接依赖|maven|
|org.scala-lang:scala-library|2.13.11|直接依赖|maven|
|javax.activation:javax.activation-api||直接依赖|maven|
|org.javassist:javassist|3.29.2-GA|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations||直接依赖|maven|
|::storage||直接依赖|maven|
|io.netty:netty-common|4.1.94.Final|间接依赖|maven|
|javax.annotation:javax.annotation-api||直接依赖|maven|
|org.glassfish.hk2:hk2-utils||直接依赖|maven|
|javax.servlet:javax.servlet-api||直接依赖|maven|
|org.glassfish.hk2:osgi-resource-locator|1.0.3|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8||直接依赖|maven|
|org.glassfish.hk2:hk2-locator||直接依赖|maven|
|org.openjdk.jmh:jmh-core|1.36|直接依赖|maven|
|org.reflections:reflections||直接依赖|maven|
|org.glassfish.hk2:hk2-api||直接依赖|maven|
|com.yammer.metrics:metrics-core||直接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.3|间接依赖|maven|
|org.eclipse.jetty:jetty-security|9.4.51.v20230217|间接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.8|间接依赖|maven|
|::connect:transforms||直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind||直接依赖|maven|
|org.apache.zookeeper:zookeeper-jute||直接依赖|maven|
|org.openjdk.jmh:jmh-core||直接依赖|maven|
|io.dropwizard.metrics:metrics-core||直接依赖|maven|
|jakarta.annotation:jakarta.annotation-api||直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-scala||直接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base||直接依赖|maven|
|commons-cli:commons-cli|1.4|直接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.94.Final|间接依赖|maven|
|jakarta.validation:jakarta.validation-api||直接依赖|maven|
|org.eclipse.jetty:jetty-servlet||直接依赖|maven|
|org.eclipse.jetty:jetty-client||直接依赖|maven|
|javax.ws.rs:javax.ws.rs-api|2.1.1|直接依赖|maven|
|org.openjdk.jmh:jmh-core-benchmarks|1.36|直接依赖|maven|
|commons-validator:commons-validator||直接依赖|maven|
|org.glassfish.jersey.core:jersey-server|2.39.1|间接依赖|maven|
|net.bytebuddy:byte-buddy||直接依赖|maven|
|org.pcollections:pcollections|4.0.1|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.5|直接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.13.5|直接依赖|maven|
|com.yammer.metrics:metrics-core|2.2.0|直接依赖|maven|
|com.github.luben:zstd-jni||直接依赖|maven|
|net.sf.jopt-simple:jopt-simple||直接依赖|maven|
|net.sourceforge.argparse4j:argparse4j|0.7.0|直接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.9.3|直接依赖|maven|
|org.mockito:mockito-core||直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.5|间接依赖|maven|
|org.glassfish.hk2:osgi-resource-locator||直接依赖|maven|
|org.rocksdb:rocksdbjni||直接依赖|maven|
|ch.qos.reload4j:reload4j||直接依赖|maven|
|commons-collections:commons-collections||直接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet-core|2.39.1|间接依赖|maven|
|org.eclipse.jetty:jetty-http|9.4.51.v20230217|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.94.Final|间接依赖|maven|
|org.eclipse.jetty:jetty-security||直接依赖|maven|
|org.apache.commons:commons-math3||直接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.10.3|直接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.94.Final|间接依赖|maven|
|org.eclipse.jetty:jetty-servlets|9.4.51.v20230217|直接依赖|maven|
|:+--- org.bitbucket.b_c:jose4j:0.9.3 (*)||直接依赖|maven|
|io.netty:netty-transport-native-unix-common||直接依赖|maven|
|org.lz4:lz4-java|1.8.0|直接依赖|maven|
|commons-io:commons-io||直接依赖|maven|
|io.netty:netty-transport||直接依赖|maven|
|com.typesafe.scala-logging:scala-logging||直接依赖|maven|
|org.codehaus.plexus:plexus-utils|3.3.1|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations||直接依赖|maven|
|org.xerial.snappy:snappy-java||直接依赖|maven|
|org.scala-lang.modules:scala-java8-compat||直接依赖|maven|
|org.slf4j:slf4j-reload4j|1.7.36|间接依赖|maven|
|org.glassfish.jersey.core:jersey-common|2.39.1|间接依赖|maven|
|javax.ws.rs:javax.ws.rs-api||直接依赖|maven|
|io.netty:netty-codec||直接依赖|maven|
|io.netty:netty-resolver||直接依赖|maven|
|org.apache.yetus:audience-annotations|0.12.0|间接依赖|maven|
|org.openjdk.jmh:jmh-core-benchmarks||直接依赖|maven|
|org.javassist:javassist||直接依赖|maven|
|org.apache.yetus:audience-annotations||直接依赖|maven|
|org.checkerframework:checker-qual||直接依赖|maven|
|org.glassfish.jersey.inject:jersey-hk2|2.39.1|直接依赖|maven|
|org.eclipse.jetty:jetty-server|9.4.51.v20230217|直接依赖|maven|
|io.netty:netty-transport|4.1.94.Final|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|org.glassfish.jersey.core:jersey-common||直接依赖|maven|
|jakarta.activation:jakarta.activation-api||直接依赖|maven|
|org.eclipse.jetty:jetty-util||直接依赖|maven|
|org.apache.zookeeper:zookeeper||直接依赖|maven|
|org.glassfish.jersey.core:jersey-server||直接依赖|maven|
|org.glassfish.hk2:hk2-locator|2.6.1|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|直接依赖|maven|
|net.bytebuddy:byte-buddy-agent|1.12.19|间接依赖|maven|
|org.eclipse.jetty:jetty-client|9.4.51.v20230217|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.13.5|间接依赖|maven|
|io.netty:netty-resolver|4.1.94.Final|间接依赖|maven|
|org.checkerframework:checker-qual|3.19.0|间接依赖|maven|
|org.reflections:reflections|0.10.2|直接依赖|maven|
|::server-common||直接依赖|maven|
|org.apache.maven:maven-artifact||直接依赖|maven|
|org.glassfish.hk2:hk2-api|2.6.1|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|直接依赖|maven|
|com.google.code.findbugs:jsr305||直接依赖|maven|
|org.eclipse.jetty:jetty-continuation||直接依赖|maven|
|org.slf4j:slf4j-log4j12||直接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet||直接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.2|间接依赖|maven|
|:+--- org.bitbucket.b_c:jose4j:{strictly 0.9.3} -> 0.9.3 (c)||直接依赖|maven|
|com.google.errorprone:error||直接依赖|maven|
|commons-io:commons-io|2.11.0|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet|2.39.1|直接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|::metadata||直接依赖|maven|
|javax.activation:activation||直接依赖|maven|
|org.mockito:mockito-core|4.11.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.5|直接依赖|maven|
|org.glassfish.hk2:hk2-utils|2.6.1|间接依赖|maven|
|::connect:api||直接依赖|maven|
|io.netty:netty-transport-native-epoll||直接依赖|maven|
|javax.servlet:javax.servlet-api|3.1.0|间接依赖|maven|
|::log4j-appender||直接依赖|maven|
|org.glassfish.jersey.inject:jersey-hk2||直接依赖|maven|
|org.pcollections:pcollections||直接依赖|maven|
|com.github.luben:zstd-jni|1.5.5-1|直接依赖|maven|
|org.rocksdb:rocksdbjni|7.9.2|直接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api||直接依赖|maven|
|io.netty:netty-handler|4.1.94.Final|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine||直接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.51.v20230217|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|4.1.12.1|直接依赖|maven|
|org.glassfish.hk2.external:jakarta.inject||直接依赖|maven|
|::core||直接依赖|maven|
|ch.qos.reload4j:reload4j|1.2.25|直接依赖|maven|
|org.eclipse.jetty:jetty-continuation|9.4.51.v20230217|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.2|间接依赖|maven|
|io.netty:netty-common||直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-csv||直接依赖|maven|
|io.netty:netty-handler||直接依赖|maven|
|org.objenesis:objenesis|3.3|间接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|commons-beanutils:commons-beanutils||直接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider||直接依赖|maven|
|io.netty:netty-buffer|4.1.94.Final|间接依赖|maven|
|org.scala-lang.modules:scala-collection-compat||直接依赖|maven|
|::streams||直接依赖|maven|
|org.glassfish.jersey.core:jersey-client||直接依赖|maven|
|::group-coordinator||直接依赖|maven|
|commons-digester:commons-digester|2.1|间接依赖|maven|
|javax.xml.bind:jaxb-api||直接依赖|maven|
|org.apache.commons:commons-lang3|3.8.1|间接依赖|maven|
|org.eclipse.jetty:jetty-http||直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core||直接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|org.scala-lang:scala-reflect|2.13.11|直接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.19|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.5|直接依赖|maven|
|org.scala-lang:scala-reflect||直接依赖|maven|
|org.slf4j:slf4j-api||直接依赖|maven|
|:|    +--- org.bitbucket.b_c:jose4j:0.9.3||间接依赖|maven|
|net.sourceforge.argparse4j:argparse4j||直接依赖|maven|
|org.eclipse.jetty:jetty-io||直接依赖|maven|
|::connect:mirror-client||直接依赖|maven|
|jakarta.ws.rs:jakarta.ws.rs-api|2.1.6|间接依赖|maven|
|org.jline:jline|3.22.0|直接依赖|maven|
|:No dependencies||直接依赖|maven|
|org.apache.maven:maven-artifact|3.8.8|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-csv|2.13.5|直接依赖|maven|
|org.apache.zookeeper:zookeeper|3.8.2|直接依赖|maven|
|org.codehaus.plexus:plexus-utils||直接依赖|maven|
|com.fasterxml.jackson:jackson-bom|2.13.5|间接依赖|maven|
|com.fasterxml.jackson:jackson-bom||直接依赖|maven|
|io.swagger.core.v3:swagger-annotations||直接依赖|maven|
|org.glassfish.hk2.external:jakarta.inject|2.6.1|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)