# ververica/flink-cdc-connectors安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692597376933318656.svg)](https://www.murphysec.com/console/report/1692597376736186368/1692597376933318656)

仓库描述：CDC Connectors for Apache Flink®

仓库地址：[https://github.com/ververica/flink-cdc-connectors](https://github.com/ververica/flink-cdc-connectors)

| star：4328 | watch：107 | fork：1528 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-18 18:00:36 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-19 02:03:45 | 组件总数：269 | 漏洞总数：35 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Oracle MySQL Connectors 访问控制错误漏洞|使用候选路径或通道进行的认证绕过|[MPS-2018-13771](https://www.oscs1024.com/hd/MPS-2018-13771)|CVE-2018-3258|高危|
|Oracle MySQL Connectors 输入验证错误漏洞|使用不兼容类型访问资源（类型混淆）|[MPS-2019-4430](https://www.oscs1024.com/hd/MPS-2019-4430)|CVE-2019-2692|中危|
|FasterXML jackson-databind 代码问题漏洞|XXE|[MPS-2020-17358](https://www.oscs1024.com/hd/MPS-2020-17358)|CVE-2020-25649|高危|
|mysql:mysql-connector-java <8.0.27 存在 XXE 漏洞|XXE|[MPS-2020-38350](https://www.oscs1024.com/hd/MPS-2020-38350)|CVE-2021-2471|中危|
|Netty <4.1.59.Final 存在不安全的临时文件漏洞||[MPS-2021-1580](https://www.oscs1024.com/hd/MPS-2021-1580)|CVE-2021-21290|中危|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|io.netty:netty-codec-http2 <4.1.60.Final 存在 http 请求走私漏洞|HTTP请求走私|[MPS-2021-2435](https://www.oscs1024.com/hd/MPS-2021-2435)|CVE-2021-21295|中危|
|Netty Bzip2Decoder 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28116](https://www.oscs1024.com/hd/MPS-2021-28116)|CVE-2021-37136|高危|
|Netty 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28117](https://www.oscs1024.com/hd/MPS-2021-28117)|CVE-2021-37137|高危|
| io.netty:netty-codec-http2 <4.1.61.Final 存在 http 请求走私漏洞|HTTP请求走私|[MPS-2021-3565](https://www.oscs1024.com/hd/MPS-2021-3565)|CVE-2021-21409|中危|
|Oracle MySQL 的 MySQL Connectors 存在授权不当漏洞|授权机制不恰当|[MPS-2021-36587](https://www.oscs1024.com/hd/MPS-2021-36587)|CVE-2022-21363|中危|
|Netty <4.1.71.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2021-36922](https://www.oscs1024.com/hd/MPS-2021-36922)|CVE-2021-43797|中危|
|io.netty:netty-codec-http <4.1.53.Final 存在拒绝服务漏洞|拒绝服务|[MPS-2022-12064](https://www.oscs1024.com/hd/MPS-2022-12064)||中危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|FasterXML Jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2022-12500](https://www.oscs1024.com/hd/MPS-2022-12500)||中危|
|Eclipse Jetty URI注入漏洞|注入|[MPS-2022-18060](https://www.oscs1024.com/hd/MPS-2022-18060)|CVE-2022-2047|低危|
|Netty 存在信息泄露漏洞||[MPS-2022-3790](https://www.oscs1024.com/hd/MPS-2022-3790)|CVE-2022-24823|中危|
|Netty <4.1.86.Final 存在拒绝服务漏洞|未经控制的递归|[MPS-2022-58518](https://www.oscs1024.com/hd/MPS-2022-58518)|CVE-2022-41881|中危|
|Netty <4.1.86.Final 存在 CRLF 注入漏洞||[MPS-2022-58552](https://www.oscs1024.com/hd/MPS-2022-58552)|CVE-2022-41915|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|Red Hat wildfly-elytron 安全漏洞|通过差异性导致的信息暴露|[MPS-2023-1618](https://www.oscs1024.com/hd/MPS-2023-1618)|CVE-2022-3143|高危|
|Apache Kafka Connect 模块JNDI注入漏洞|反序列化|[MPS-2023-3834](https://www.oscs1024.com/hd/MPS-2023-3834)|CVE-2023-25194|高危|
|Eclipse Jetty 资源管理错误漏洞|拒绝服务|[MPS-2023-4997](https://www.oscs1024.com/hd/MPS-2023-4997)|CVE-2023-26048|中危|
|Eclipse Jetty 信息泄露漏洞|XSS|[MPS-2023-4998](https://www.oscs1024.com/hd/MPS-2023-4998)|CVE-2023-26049|中危|
|jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2023-8438](https://www.oscs1024.com/hd/MPS-2023-8438)|CVE-2021-46877|中危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|io.netty:netty-codec|4.1.63.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|org.wildfly.security:wildfly-elytron-password-impl|1.15.1.Final|1.15.15|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.2.2|2.14.0-rc1|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.10.2|2.14.0-rc1|间接依赖|建议修复|C:0|H:2|M:5|L:0|
|io.netty:netty-handler|4.1.77.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|mysql:mysql-connector-java|5.1.47|8.0.28|直接依赖|建议修复|C:0|H:1|M:3|L:0|
|io.netty:netty-codec|4.1.48.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|org.wildfly.security:wildfly-elytron-credential|1.15.1.Final|1.15.15|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.48.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|org.wildfly.security:wildfly-elytron-x500|1.15.1.Final|1.15.15|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.xerial.snappy:snappy-java|1.1.8.3|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.eclipse.jetty:jetty-server|9.4.44.v20210927|12.0.0.beta0|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.apache.kafka:kafka-clients|3.2.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.google.protobuf:protobuf-java|3.11.4|3.21.7|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|io.netty:netty-handler|4.1.63.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|io.netty:netty-common|4.1.48.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.eclipse.jetty:jetty-http|9.4.44.v20210927|11.0.10|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|com.google.code.gson:gson|2.8.6|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|io.netty:netty-common|4.1.63.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|30.1.1-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-haproxy|4.1.77.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-http|4.1.77.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-http|4.1.51.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:5|L:0|
|io.netty:netty-codec-http2|4.1.51.Final|4.1.61.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|198|Low|
|MIT|6|Low|
|EPL-2.0|18|Low|
|BSD-3-Clause|9|Low|
|BSD-2-Clause|3|Low|
|MIT-0|1|Low|
|WTFPL|1|Low|
|CDDL-1.1|1|Low|
|EPL-1.0|1|Low|
|LGPL-2.1|2|Medium|
|MPL-1.1|1|Low|
|CDDL-1.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|io.netty:netty-codec-dns|4.1.77.Final|间接依赖|maven|
|org.apache.kafka:kafka-clients|3.2.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.2.2|间接依赖|maven|
|joda-time:joda-time|2.10|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.77.Final|间接依赖|maven|
|io.perfmark:perfmark-api|0.19.0|间接依赖|maven|
|org.apache.flink:flink-test-utils-junit|1.17.0|间接依赖|maven|
|io.grpc:grpc-api|1.33.0|间接依赖|maven|
|org.jgroups:jgroups|4.2.12.Final|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.15|直接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.12.6|间接依赖|maven|
|org.infinispan:infinispan-core|12.1.6.Final|间接依赖|maven|
|io.netty:netty-codec-redis|4.1.77.Final|间接依赖|maven|
|org.eclipse.jetty:jetty-servlets|9.4.44.v20210927|间接依赖|maven|
|com.oracle.ojdbc:osdt_core|19.3.0.0|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.63.Final|间接依赖|maven|
|org.apache.flink:flink-runtime|1.17.0|间接依赖|maven|
|org.junit.vintage:junit-vintage-engine|5.9.1|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.2|间接依赖|maven|
|org.junit.jupiter:junit-jupiter|5.9.1|间接依赖|maven|
|org.hamcrest:hamcrest|2.1|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet-core|2.34|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.11.4|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.77.Final|间接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.44.v20210927|间接依赖|maven|
|com.ververica:flink-cdc-base|2.5-SNAPSHOT|直接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet|2.34|间接依赖|maven|
|org.apache.kafka:connect-json|3.2.0|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.51.Final|间接依赖|maven|
|org.eclipse.jetty:jetty-http|9.4.44.v20210927|间接依赖|maven|
|org.wildfly.security:wildfly-elytron-sasl-scram|1.15.1.Final|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.77.Final|间接依赖|maven|
|org.apache.flink:flink-table-planner_2.12|1.17.0|直接依赖|maven|
|com.esri.geometry:esri-geometry-api|2.2.0|直接依赖|maven|
|org.apache.flink:flink-statebackend-common|1.17.0|间接依赖|maven|
|org.eclipse.jetty:jetty-client|9.4.44.v20210927|间接依赖|maven|
|org.jboss.spec.javax.transaction:jboss-transaction-api_1.2_spec|1.1.1.Final|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|org.apache.flink:flink-scala_2.12|1.17.0|间接依赖|maven|
|org.wildfly.security:wildfly-elytron-ssl|1.15.1.Final|间接依赖|maven|
|io.netty:netty-all|4.1.77.Final|间接依赖|maven|
|com.oracle.database.xml:xmlparserv2|19.3.0.0|间接依赖|maven|
|org.junit.platform:junit-platform-engine|1.9.1|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.12.6|间接依赖|maven|
|org.opentest4j:opentest4j|1.2.0|间接依赖|maven|
|org.apiguardian:apiguardian-api|1.1.2|间接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.77.Final|间接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|直接依赖|maven|
|com.google.code.gson:gson|2.8.6|间接依赖|maven|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|org.glassfish.hk2:hk2-utils|2.6.1|间接依赖|maven|
|mysql:mysql-connector-java|5.1.47|直接依赖|maven|
|org.awaitility:awaitility|4.0.1|直接依赖|maven|
|org.wildfly.security:wildfly-elytron-sasl-digest|1.15.1.Final|间接依赖|maven|
|org.infinispan.protostream:protostream-types|4.4.1.Final|间接依赖|maven|
|ch.qos.reload4j:reload4j|1.2.19|间接依赖|maven|
|io.reactivex.rxjava3:rxjava|3.0.4|间接依赖|maven|
|org.mongodb:bson-record-codec|4.9.1|间接依赖|maven|
|io.netty:netty-buffer|4.1.77.Final|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-engine|5.9.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.10.2|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.12.6|间接依赖|maven|
|org.apache.flink:flink-rpc-core|1.17.0|间接依赖|maven|
|org.codehaus.janino:janino|3.0.11|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.44.v20210927|间接依赖|maven|
|org.bitbucket.b_c:jose4j|0.7.9|间接依赖|maven|
|com.google.code.findbugs:jsr305|1.3.9|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.3|间接依赖|maven|
|io.netty:netty-codec-smtp|4.1.77.Final|间接依赖|maven|
|io.debezium:debezium-connector-vitess|1.9.7.Final|直接依赖|maven|
|com.ververica:flink-connector-postgres-cdc|2.5-SNAPSHOT|直接依赖|maven|
|io.netty:netty-handler|4.1.48.Final|间接依赖|maven|
|com.github.docker-java:docker-java-api|3.2.13|间接依赖|maven|
|org.glassfish.hk2:hk2-api|2.6.1|间接依赖|maven|
|io.grpc:grpc-context|1.33.0|间接依赖|maven|
|io.netty:netty-codec-http|4.1.77.Final|间接依赖|maven|
|org.apache.flink:flink-statebackend-changelog|1.17.0|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-params|5.9.1|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.10|间接依赖|maven|
|org.wildfly.security:wildfly-elytron-sasl-gs2|1.15.1.Final|间接依赖|maven|
|org.wildfly.security:wildfly-elytron-sasl-plain|1.15.1.Final|间接依赖|maven|
|org.apache.kafka:kafka-tools|3.2.0|间接依赖|maven|
|com.twitter:chill_2.12|0.7.6|间接依赖|maven|
|org.wildfly.security:wildfly-elytron-security-manager-action|1.15.1.Final|间接依赖|maven|
|com.ververica:flink-connector-db2-cdc|2.5-SNAPSHOT|直接依赖|maven|
|io.netty:netty-resolver|4.1.77.Final|间接依赖|maven|
|org.apache.kafka:connect-file|3.2.0|间接依赖|maven|
|com.ververica:flink-connector-mongodb-cdc|2.5-SNAPSHOT|直接依赖|maven|
|io.netty:netty-common|4.1.77.Final|间接依赖|maven|
|com.ibm.db2.jcc:db2jcc|db2jcc4|直接依赖|maven|
|io.netty:netty-transport-udt|4.1.77.Final|间接依赖|maven|
|org.immutables:value-annotations|2.8.8|间接依赖|maven|
|io.netty:netty-handler|4.1.77.Final|间接依赖|maven|
|io.netty:netty-transport-rxtx|4.1.77.Final|间接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|io.netty:netty-transport|4.1.48.Final|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.1.Final|间接依赖|maven|
|com.ververica:flink-connector-oceanbase-cdc|2.5-SNAPSHOT|直接依赖|maven|
|com.oceanbase:oblogclient-common|1.1.0|间接依赖|maven|
|org.wildfly.security:wildfly-elytron-sasl-oauth2|1.15.1.Final|间接依赖|maven|
|org.scala-lang:scala-library|2.12.7|间接依赖|maven|
|org.apache.kafka:connect-runtime|3.2.0|间接依赖|maven|
|io.netty:netty-handler|4.1.63.Final|间接依赖|maven|
|io.vitess:vitess-grpc-client|12.0.0|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.2-1|间接依赖|maven|
|io.grpc:grpc-stub|1.33.0|间接依赖|maven|
|org.glassfish.hk2.external:jakarta.inject|2.6.1|间接依赖|maven|
|io.netty:netty-buffer|4.1.48.Final|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.77.Final|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.12.6|间接依赖|maven|
|org.mongodb:mongodb-driver-core|4.9.1|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.77.Final|间接依赖|maven|
|org.wildfly.security:wildfly-elytron-auth-server|1.15.1.Final|间接依赖|maven|
|com.github.docker-java:docker-java-transport-zerodep|3.2.13|间接依赖|maven|
|io.netty:netty-transport-sctp|4.1.77.Final|间接依赖|maven|
|io.netty:netty-codec|4.1.63.Final|间接依赖|maven|
|org.checkerframework:checker-qual|3.5.0|间接依赖|maven|
|org.wildfly.security:wildfly-elytron-http|1.15.1.Final|间接依赖|maven|
|org.eclipse.jetty:jetty-security|9.4.44.v20210927|间接依赖|maven|
|org.wildfly.security:wildfly-elytron-sasl|1.15.1.Final|间接依赖|maven|
|com.github.docker-java:docker-java-transport|3.2.13|间接依赖|maven|
|io.grpc:grpc-protobuf|1.33.0|间接依赖|maven|
|org.scala-lang.modules:scala-xml_2.12|1.0.6|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|org.postgresql:postgresql|42.5.1|直接依赖|maven|
|io.netty:netty-transport|4.1.77.Final|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.63.Final|间接依赖|maven|
|io.debezium:debezium-ddl-parser|1.9.7.Final|间接依赖|maven|
|io.netty:netty-buffer|4.1.63.Final|间接依赖|maven|
|org.reflections:reflections|0.9.12|间接依赖|maven|
|jakarta.ws.rs:jakarta.ws.rs-api|2.1.6|间接依赖|maven|
|org.apache.flink:flink-rpc-akka-loader|1.17.0|间接依赖|maven|
|org.infinispan:infinispan-client-hotrod|12.1.6.Final|间接依赖|maven|
|io.debezium:debezium-api|1.9.7.Final|直接依赖|maven|
|commons-cli:commons-cli|1.5.0|间接依赖|maven|
|org.lz4:lz4-java|1.8.0|间接依赖|maven|
|org.rnorth.duct-tape:duct-tape|1.0.8|间接依赖|maven|
|org.wildfly.security:wildfly-elytron-keystore|1.15.1.Final|间接依赖|maven|
|org.apache.flink:flink-queryable-state-client-java|1.17.0|间接依赖|maven|
|io.netty:netty-codec-mqtt|4.1.77.Final|间接依赖|maven|
|org.infinispan.protostream:protostream|4.4.1.Final|间接依赖|maven|
|org.glassfish.hk2.external:aopalliance-repackaged|2.6.1|间接依赖|maven|
|org.apache.flink:flink-test-utils|1.17.0|直接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|1.17.0|间接依赖|maven|
|org.codehaus.janino:commons-compiler|3.0.11|间接依赖|maven|
|org.eclipse.jetty:jetty-server|9.4.44.v20210927|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.77.Final|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.19.6|间接依赖|maven|
|org.apache.flink:flink-shaded-guava|30.1.1-jre-16.1|直接依赖|maven|
|io.netty:netty-transport|4.1.63.Final|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.51.Final|间接依赖|maven|
|org.mongodb:bson|4.9.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.2|间接依赖|maven|
|com.ververica:flink-connector-oracle-cdc|2.5-SNAPSHOT|直接依赖|maven|
|net.sourceforge.argparse4j:argparse4j|0.7.0|间接依赖|maven|
|org.mongodb.kafka:mongo-kafka-connect|1.10.1|直接依赖|maven|
|io.debezium:debezium-connector-oracle|1.9.7.Final|直接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.0|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.8.4|间接依赖|maven|
|org.scala-lang:scala-reflect|2.12.7|间接依赖|maven|
|org.apache.flink:flink-hadoop-fs|1.17.0|间接依赖|maven|
|org.wildfly.security:wildfly-elytron-mechanism-oauth2|1.15.1.Final|间接依赖|maven|
|junit:junit|4.13.2|间接依赖|maven|
|com.zendesk:mysql-binlog-connector-java|0.27.2|间接依赖|maven|
|io.netty:netty-codec|4.1.48.Final|间接依赖|maven|
|org.codehaus.plexus:plexus-utils|3.3.0|间接依赖|maven|
|org.wildfly.security:wildfly-elytron-base|1.15.1.Final|间接依赖|maven|
|io.netty:netty-codec-stomp|4.1.77.Final|间接依赖|maven|
|com.ververica:flink-connector-debezium|2.5-SNAPSHOT|直接依赖|maven|
|org.apache.flink:flink-table-runtime|1.17.0|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.12.6|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.51.Final|间接依赖|maven|
|io.netty:netty-codec-xml|4.1.77.Final|间接依赖|maven|
|org.javassist:javassist|3.24.0-GA|间接依赖|maven|
|org.apache.flink:flink-shaded-zookeeper-3|3.7.1-16.1|间接依赖|maven|
|org.testcontainers:testcontainers|1.17.2|间接依赖|maven|
|org.apache.maven:maven-artifact|3.8.4|间接依赖|maven|
|org.scala-lang:scala-compiler|2.12.7|间接依赖|maven|
|io.debezium:debezium-connector-sqlserver|1.9.7.Final|直接依赖|maven|
|org.jboss.threads:jboss-threads|2.3.3.Final|间接依赖|maven|
|com.microsoft.sqlserver:mssql-jdbc|9.4.1.jre8|间接依赖|maven|
|io.debezium:debezium-connector-postgres|1.9.7.Final|直接依赖|maven|
|org.glassfish.jersey.inject:jersey-hk2|2.34|间接依赖|maven|
|org.wildfly.security:wildfly-elytron-password-impl|1.15.1.Final|间接依赖|maven|
|com.oceanbase:oblogclient-logproxy|1.1.0|直接依赖|maven|
|org.apache.commons:commons-lang3|3.7|直接依赖|maven|
|org.wildfly.security:wildfly-elytron-credential|1.15.1.Final|间接依赖|maven|
|org.wildfly.security:wildfly-elytron-auth|1.15.1.Final|间接依赖|maven|
|com.ververica:flink-connector-vitess-cdc|2.5-SNAPSHOT|直接依赖|maven|
|org.immutables:value|2.8.8|间接依赖|maven|
|io.grpc:grpc-core|1.33.0|间接依赖|maven|
|org.apache.commons:commons-collections4|4.2|间接依赖|maven|
|io.debezium:debezium-connector-db2|1.9.7.Final|直接依赖|maven|
|com.github.luben:zstd-jni|1.5.0-2|间接依赖|maven|
|org.apache.flink:flink-core|1.17.0|间接依赖|maven|
|org.apache.flink:flink-cep|1.17.0|间接依赖|maven|
|commons-io:commons-io|2.11.0|间接依赖|maven|
|com.oracle.ojdbc:simplefan|19.3.0.0|间接依赖|maven|
|org.wildfly.security:wildfly-elytron-x500|1.15.1.Final|间接依赖|maven|
|com.oracle.ojdbc:ons|19.3.0.0|间接依赖|maven|
|io.grpc:grpc-netty|1.33.0|间接依赖|maven|
|io.netty:netty-resolver|4.1.48.Final|间接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.77.Final|间接依赖|maven|
|javax.ws.rs:javax.ws.rs-api|2.1.1|间接依赖|maven|
|io.netty:netty-codec-http|4.1.51.Final|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.1|间接依赖|maven|
|org.apache.avro:avro|1.9.2|间接依赖|maven|
|io.netty:netty-codec-memcache|4.1.77.Final|间接依赖|maven|
|org.apache.kafka:connect-api|3.2.0|间接依赖|maven|
|io.debezium:debezium-embedded|1.9.7.Final|直接依赖|maven|
|org.eclipse.jetty:jetty-util-ajax|9.4.44.v20210927|间接依赖|maven|
|org.infinispan:infinispan-commons|12.1.6.Final|间接依赖|maven|
|io.debezium:debezium-connector-mysql|1.9.7.Final|直接依赖|maven|
|org.wildfly.security:wildfly-elytron-sasl-gssapi|1.15.1.Final|间接依赖|maven|
|org.wildfly.security:wildfly-elytron-asn1|1.15.1.Final|间接依赖|maven|
|org.wildfly.security:wildfly-elytron-mechanism|1.15.1.Final|间接依赖|maven|
|io.netty:netty-common|4.1.48.Final|间接依赖|maven|
|org.mongodb:mongodb-driver-sync|4.9.1|直接依赖|maven|
|mysql:mysql-connector-java|8.0.28|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.77.Final|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-api|5.9.1|间接依赖|maven|
|org.glassfish.hk2:hk2-locator|2.6.1|间接依赖|maven|
|org.apache.flink:flink-shaded-force-shading|16.1|间接依赖|maven|
|com.oracle.ojdbc:oraclepki|19.3.0.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.10.2|间接依赖|maven|
|org.tikv:tikv-client-java|3.2.0|直接依赖|maven|
|org.antlr:antlr4-runtime|4.8|间接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.33.0|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.2|间接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.4.44.v20210927|间接依赖|maven|
|org.wildfly.security:wildfly-elytron-util|1.15.1.Final|间接依赖|maven|
|org.jetbrains:annotations|17.0.0|间接依赖|maven|
|org.wildfly.security:wildfly-elytron-mechanism-gssapi|1.15.1.Final|间接依赖|maven|
|com.ververica:flink-connector-sqlserver-cdc|2.5-SNAPSHOT|直接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.77.Final|间接依赖|maven|
|com.ververica:flink-connector-tidb-cdc|2.5-SNAPSHOT|直接依赖|maven|
|io.netty:netty-codec|4.1.77.Final|间接依赖|maven|
|io.netty:netty-tcnative-boringssl-static|2.0.30.Final|间接依赖|maven|
|org.apache.flink:flink-optimizer|1.17.0|间接依赖|maven|
|io.netty:netty-common|4.1.63.Final|间接依赖|maven|
|javax.activation:activation|1.1.1|间接依赖|maven|
|com.oracle.database.xml:xdb|19.3.0.0|直接依赖|maven|
|org.wildfly.security:wildfly-elytron-sasl-external|1.15.1.Final|间接依赖|maven|
|org.wildfly.security:wildfly-elytron-permission|1.15.1.Final|间接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.77.Final|间接依赖|maven|
|com.google.guava:guava|30.1.1-jre|间接依赖|maven|
|com.ververica:flink-connector-mysql-cdc|2.5-SNAPSHOT|直接依赖|maven|
|net.java.dev.jna:jna|5.8.0|间接依赖|maven|
|io.vitess:vitess-client|12.0.0|间接依赖|maven|
|org.eclipse.jetty:jetty-continuation|9.4.44.v20210927|间接依赖|maven|
|com.oracle.ojdbc:ucp|19.3.0.0|间接依赖|maven|
|org.assertj:assertj-core|3.23.1|间接依赖|maven|
|org.wildfly.security:wildfly-elytron-provider-util|1.15.1.Final|间接依赖|maven|
|org.apache.flink:flink-shaded-netty|4.1.82.Final-16.1|间接依赖|maven|
|io.netty:netty-codec-haproxy|4.1.77.Final|间接依赖|maven|
|com.oracle.ojdbc:osdt_cert|19.3.0.0|间接依赖|maven|
|org.wildfly.security:wildfly-elytron-mechanism-scram|1.15.1.Final|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|org.wildfly.security:wildfly-elytron-mechanism-digest|1.15.1.Final|间接依赖|maven|
|org.hamcrest:hamcrest-core|1.3|间接依赖|maven|
|javax.servlet:javax.servlet-api|3.1.0|间接依赖|maven|
|org.apache.flink:flink-clients|1.17.0|间接依赖|maven|
|com.oracle.ojdbc:ojdbc8|19.3.0.0|直接依赖|maven|
|org.junit.platform:junit-platform-commons|1.9.1|间接依赖|maven|
|io.debezium:debezium-core|1.9.7.Final|间接依赖|maven|
|org.wildfly.common:wildfly-common|1.3.0.Final|间接依赖|maven|
|org.apache.kafka:connect-transforms|3.2.0|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|io.netty:netty-resolver|4.1.63.Final|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)