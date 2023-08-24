# apache/zookeeper安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694772491276083200.svg)](https://www.murphysec.com/console/report/1694772491229945856/1694772491276083200)

仓库描述：Apache ZooKeeper

仓库地址：[https://github.com/apache/zookeeper](https://github.com/apache/zookeeper)

| star：11500 | watch：668 | fork：7099 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-23 22:16:22 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-25 02:04:22 | 组件总数：90 | 漏洞总数：15 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|多款Cisco产品Apache Commons Collections库任意代码执行漏洞|反序列化|[MPS-2015-6277](https://www.oscs1024.com/hd/MPS-2015-6277)|CVE-2015-6420|高危|
|多款Red Hat产品代码问题漏洞|反序列化|[MPS-2017-12638](https://www.oscs1024.com/hd/MPS-2017-12638)|CVE-2015-7501|严重|
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|Junit 信息泄露漏洞|不安全的临时文件|[MPS-2020-15183](https://www.oscs1024.com/hd/MPS-2020-15183)|CVE-2020-15250|中危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Apache Commons Collections 远程代码执行漏洞|反序列化|[MPS-2022-12767](https://www.oscs1024.com/hd/MPS-2022-12767)||高危|
|Jettison <1.5.2 拒绝服务漏洞|拒绝服务|[MPS-2022-57067](https://www.oscs1024.com/hd/MPS-2022-57067)|CVE-2022-40150|高危|
|Jettison <1.5.1 拒绝服务漏洞|越界写入|[MPS-2022-57068](https://www.oscs1024.com/hd/MPS-2022-57068)|CVE-2022-40149|高危|
|Jettison <1.5.2 拒绝服务漏洞|越界写入|[MPS-2022-64973](https://www.oscs1024.com/hd/MPS-2022-64973)|CVE-2022-45685|高危|
|Eclipse Jetty 资源管理错误漏洞|拒绝服务|[MPS-2023-4997](https://www.oscs1024.com/hd/MPS-2023-4997)|CVE-2023-26048|中危|
|Eclipse Jetty 信息泄露漏洞|XSS|[MPS-2023-4998](https://www.oscs1024.com/hd/MPS-2023-4998)|CVE-2023-26049|中危|
|Jettison 安全漏洞|未经控制的递归|[MPS-2023-8270](https://www.oscs1024.com/hd/MPS-2023-8270)|CVE-2023-1436|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|io.netty:netty-handler|4.1.94.Final|4.1.94.final|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.codehaus.jettison:jettison|1.1|1.5.4|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.15.2||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.eclipse.jetty:jetty-server|9.4.51.v20230217|12.0.0.beta0|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|commons-collections:commons-collections|3.2|3.2.2|间接依赖|建议修复|C:1|H:2|M:0|L:0|
|junit:junit|4.13|4.13.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|18.0|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:2|L:1|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|49|Low|
|MIT|4|Low|
|自定义许可证|19|Low|
|EPL-1.0|10|Low|
|EPL-2.0|3|Low|
|CDDL-1.1|5|Low|
|CDDL-1.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.apache.commons:commons-math3|3.2|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|4.1.12.1|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.30|直接依赖|maven|
|android-ndk|r23b|间接依赖||
|jline:jline|2.14.6|直接依赖|maven|
|com.google.guava:guava|18.0|直接依赖|maven|
|ch.qos.logback:logback-core|1.2.10|直接依赖|maven|
|org.apache.rat:apache-rat-core|0.6|间接依赖|maven|
|com.sun.jersey:jersey-server|1.1.5.1|直接依赖|maven|
|javax.activation:activation|1.1|间接依赖|maven|
|org.junit.vintage:junit-vintage-engine|5.6.2|直接依赖|maven|
|org.apache.zookeeper:zookeeper-jute|3.10.0-SNAPSHOT|直接依赖|maven|
|net.sf.jopt-simple:jopt-simple|4.6|间接依赖|maven|
|org.apache.zookeeper:zookeeper-docs|3.10.0-SNAPSHOT|直接依赖|maven|
|junit:junit||间接依赖|maven|
|org.apiguardian:apiguardian-api|1.1.0|间接依赖|maven|
|commons-collections:commons-collections|3.2|间接依赖|maven|
|io.prometheus:simpleclient_servlet|0.9.0|直接依赖|maven|
|asm:asm|3.1|直接依赖|maven|
|ch.qos.logback:logback-classic|1.2.10|直接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.94.Final|间接依赖|maven|
|commons-cli:commons-cli|1.1|间接依赖|maven|
|org.openjdk.jmh:jmh-core|1.23|直接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.94.Final|直接依赖|maven|
|io.netty:netty-buffer|4.1.94.Final|间接依赖|maven|
|com.sun.grizzly:grizzly-servlet-webserver||间接依赖|maven|
|org.apache.zookeeper:zookeeper-client|3.10.0-SNAPSHOT|直接依赖|maven|
|com.sun.grizzly:grizzly-http-servlet|1.9.8|间接依赖|maven|
|org.codehaus.jettison:jettison|1.1|间接依赖|maven|
|io.netty:netty-tcnative-boringssl-static|2.0.61.Final|直接依赖|maven|
|com.sun.jersey:jersey-json|1.1.5.1|直接依赖|maven|
|javax.servlet:javax.servlet-api|3.1.0|间接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.51.v20230217|间接依赖|maven|
|com.sun.xml.bind:jaxb-impl|2.1.12|间接依赖|maven|
|junit:junit|4.13|间接依赖|maven|
|com.google.guava:guava||间接依赖|maven|
|javax.ws.rs:jsr311-api|1.1.1|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.10.1|直接依赖|maven|
|log4j:log4j||间接依赖|maven|
|org.slf4j:slf4j-log4j12||间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.10.0-SNAPSHOT|直接依赖|maven|
|com.sun.jersey:jersey-core|1.1.5.1|间接依赖|maven|
|io.prometheus:simpleclient_hotspot|0.9.0|直接依赖|maven|
|org.apache.zookeeper:zookeeper-prometheus-metrics|3.10.0-SNAPSHOT|直接依赖|maven|
|javax.xml.bind:jaxb-api|2.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.15.2|间接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.1.1|间接依赖|maven|
|io.netty:netty-transport|4.1.94.Final|间接依赖|maven|
|javax.servlet:servlet-api|2.5|间接依赖|maven|
|io.netty:netty-resolver|4.1.94.Final|间接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.4.51.v20230217|直接依赖|maven|
|com.sun.grizzly:grizzly-utils|1.9.8|间接依赖|maven|
|org.apache.zookeeper:zookeeper-it|3.10.0-SNAPSHOT|直接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.51.v20230217|间接依赖|maven|
|io.prometheus:simpleclient_common|0.9.0|间接依赖|maven|
|io.netty:netty-handler|4.1.94.Final|直接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.94.Final|间接依赖|maven|
|io.netty:netty-tcnative-classes|2.0.61.Final|间接依赖|maven|
|javax.xml.stream:stax-api|1.0-2|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.15.2|间接依赖|maven|
|com.sun.jersey:jersey-client||间接依赖|maven|
|org.openjdk.jmh:jmh-generator-annprocess|1.23|直接依赖|maven|
|org.opentest4j:opentest4j|1.2.0|间接依赖|maven|
|com.sun.jersey:jersey-json||间接依赖|maven|
|stax:stax-api|1.0.1|间接依赖|maven|
|io.prometheus:simpleclient|0.9.0|直接依赖|maven|
|org.apache.rat:apache-rat-tasks|0.6|直接依赖|maven|
|org.apache.rat:apache-rat-tasks||间接依赖|maven|
|com.sun.grizzly:grizzly-servlet-webserver|1.9.8|直接依赖|maven|
|org.eclipse.jetty:jetty-security|9.4.51.v20230217|间接依赖|maven|
|com.sun.grizzly:grizzly-http|1.9.8|间接依赖|maven|
|com.sun.jersey:jersey-server||间接依赖|maven|
|com.sun.grizzly:grizzly-framework|1.9.8|间接依赖|maven|
|org.apache.zookeeper:zookeeper-recipes|3.10.0-SNAPSHOT|直接依赖|maven|
|org.junit.platform:junit-platform-engine|1.6.2|间接依赖|maven|
|io.netty:netty-codec|4.1.94.Final|间接依赖|maven|
|commons-lang:commons-lang|2.1|间接依赖|maven|
|com.sun.grizzly:grizzly-rcm|1.9.8|间接依赖|maven|
|org.eclipse.jetty:jetty-server|9.4.51.v20230217|直接依赖|maven|
|asm:asm||间接依赖|maven|
|org.eclipse.jetty:jetty-util-ajax|9.4.51.v20230217|间接依赖|maven|
|org.hamcrest:hamcrest-core|1.3|间接依赖|maven|
|org.junit.platform:junit-platform-commons|1.6.2|间接依赖|maven|
|com.sun.grizzly:grizzly-portunif|1.9.8|间接依赖|maven|
|commons-io:commons-io|2.11.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.15.2|直接依赖|maven|
|org.apache.yetus:audience-annotations|0.12.0|直接依赖|maven|
|org.slf4j:slf4j-api||间接依赖|maven|
|io.netty:netty-common|4.1.94.Final|间接依赖|maven|
|commons-cli:commons-cli|1.5.0|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)