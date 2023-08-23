# apache/skywalking安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694410629593853952.svg)](https://www.murphysec.com/console/report/1694410629556105216/1694410629593853952)

仓库描述：APM, Application Performance Monitoring System

仓库地址：[https://github.com/apache/skywalking](https://github.com/apache/skywalking)

| star：22290 | watch：848 | fork：6346 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-23 07:41:27 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-24 02:12:57 | 组件总数：299 | 漏洞总数：16 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache HttpClient URI解析错误漏洞|XSS|[MPS-2020-17341](https://www.oscs1024.com/hd/MPS-2020-17341)|CVE-2020-13956|中危|
|Netty <4.1.59.Final 存在不安全的临时文件漏洞||[MPS-2021-1580](https://www.oscs1024.com/hd/MPS-2021-1580)|CVE-2021-21290|中危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|Netty <4.1.86.Final 存在拒绝服务漏洞|未经控制的递归|[MPS-2022-58518](https://www.oscs1024.com/hd/MPS-2022-58518)|CVE-2022-41881|中危|
|Netty <4.1.86.Final 存在 CRLF 注入漏洞||[MPS-2022-58552](https://www.oscs1024.com/hd/MPS-2022-58552)|CVE-2022-41915|中危|
|pgjdbc <42.5.1 存在信息泄露漏洞|不安全的临时文件|[MPS-2022-58583](https://www.oscs1024.com/hd/MPS-2022-58583)|CVE-2022-41946|中危|
|H2 数据库明文密码问题|未授权敏感信息泄露|[MPS-2022-65204](https://www.oscs1024.com/hd/MPS-2022-65204)|CVE-2022-45868|高危|
|Apache Kafka Connect 模块JNDI注入漏洞|反序列化|[MPS-2023-3834](https://www.oscs1024.com/hd/MPS-2023-3834)|CVE-2023-25194|高危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.squareup.okio:okio|2.8.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.kafka:kafka-clients|2.8.1|3.4.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.79.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.squareup.okio:okio|1.17.2|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.86.Final|4.1.94.final|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.xerial.snappy:snappy-java|1.1.8.1|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.15.2||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-http|4.1.86.Final|4.1.86.final|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-codec:commons-codec|1.11|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|io.netty:netty-codec-http|4.1.79.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.h2database:h2|2.1.212||直接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.guava:guava|31.1-android|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-haproxy|4.1.86.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.httpcomponents:httpclient|4.5.3|4.5.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-transport-native-epoll|4.1.45.Final|4.1.59.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.postgresql:postgresql|42.4.1|42.5.1|直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|267|Low|
|BSD-3-Clause|10|Low|
|自定义许可证|5|Low|
|MIT-0|1|Low|
|MIT|8|Low|
|BSD-2-Clause|4|Low|
|MPL-2.0|1|Low|
|EPL-1.0|1|Low|
|LGPL-2.1|1|Medium|
|MPL-1.1|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|io.fabric8:kubernetes-model-metrics|6.7.1|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.86.Final|直接依赖|maven|
|org.apache.skywalking:library-elasticsearch-client|9.6.0-SNAPSHOT|直接依赖|maven|
|org.apache.skywalking:meter-analyzer|9.6.0-SNAPSHOT|直接依赖|maven|
|io.prometheus:simpleclient_common|0.6.0|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.7.10|间接依赖|maven|
|org.apache.skywalking:skywalking-jvm-receiver-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|org.lz4:lz4-java|1.7.1|间接依赖|maven|
|io.fabric8:kubernetes-model-certificates|6.7.1|间接依赖|maven|
|io.netty:netty-handler|4.1.79.Final|间接依赖|maven|
|org.apache.skywalking:tool-profile-snapshot-server-mock|9.6.0-SNAPSHOT|直接依赖|maven|
|google.golang.org/genproto|v0.0.0-20221025140454-527a21cfbd71|间接依赖|go|
|org.apache.zookeeper:zookeeper-jute|3.5.7|间接依赖|maven|
|io.netty:netty-codec-http|4.1.79.Final|间接依赖|maven|
|org.apache.skywalking:mqe-grammar|9.6.0-SNAPSHOT|直接依赖|maven|
|com.google.inject:guice|4.1.0|间接依赖|maven|
|github.com/google/uuid|v1.3.0|间接依赖|go|
|io.netty:netty-codec-socks|4.1.86.Final|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.13|间接依赖|maven|
|org.apache.curator:curator-x-discovery|4.3.0|直接依赖|maven|
|io.netty:netty-codec-haproxy|4.1.94.Final|间接依赖|maven|
|io.netty:netty-codec-http|4.1.86.Final|直接依赖|maven|
|io.fabric8:kubernetes-model-apiextensions|6.7.1|间接依赖|maven|
|org.apache.skywalking:skywalking-sharing-server-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|org.apache.skywalking:configuration-etcd|9.6.0-SNAPSHOT|直接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.1|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.3|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.15.2|间接依赖|maven|
|io.etcd:jetcd-common|0.5.3|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.86.Final|间接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|org.apache.skywalking:cluster-etcd-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|org.apache.skywalking:telemetry-prometheus|9.6.0-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-guava|2.12.0|间接依赖|maven|
|github.com/golang/protobuf|v1.5.2|间接依赖|go|
|org.apache.skywalking:library-datacarrier-queue|9.6.0-SNAPSHOT|直接依赖|maven|
|io.fabric8:kubernetes-model-common|6.7.1|间接依赖|maven|
|org.apache.kafka:kafka-clients|2.8.1|直接依赖|maven|
|com.zaxxer:HikariCP|3.1.0|直接依赖|maven|
|io.micrometer:micrometer-observation|1.11.1|间接依赖|maven|
|org.apache.skywalking:agent-analyzer|9.6.0-SNAPSHOT|直接依赖|maven|
|com.squareup.retrofit2:converter-jackson|2.9.0|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.79.Final|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|org.apache.skywalking:receiver-proto|9.6.0-SNAPSHOT|直接依赖|maven|
|io.zipkin:zipkin-lens|2.24.1|直接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.13|直接依赖|maven|
|com.alibaba.nacos:nacos-api|1.4.2|间接依赖|maven|
|com.ctrip.framework.apollo:apollo-core|1.8.0|间接依赖|maven|
|org.apache.skywalking:server-starter|9.6.0-SNAPSHOT|直接依赖|maven|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|org.codehaus.groovy:groovy|3.0.8|直接依赖|maven|
|org.apache.skywalking:apm-webapp|9.6.0-SNAPSHOT|直接依赖|maven|
|org.apache.skywalking:skywalking-event-receiver-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.15.2|间接依赖|maven|
|io.prometheus:simpleclient_hotspot|0.6.0|直接依赖|maven|
|github.com/SkyAPM/go2sky|v1.5.0|间接依赖|go|
|io.netty:netty-codec|4.1.79.Final|间接依赖|maven|
|io.netty:netty-tcnative-boringssl-static|2.0.54.Final|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.30|直接依赖|maven|
|joda-time:joda-time|2.10.5|直接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.94.Final|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.79.Final|间接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.94.Final|间接依赖|maven|
|org.yaml:snakeyaml|2.0|直接依赖|maven|
|io.netty:netty-transport|4.1.86.Final|间接依赖|maven|
|io.fabric8:kubernetes-model-coordination|6.7.1|间接依赖|maven|
|com.google.code.gson:gson|2.9.0|直接依赖|maven|
|org.apache.skywalking:skywalking-log-receiver-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-reflect|1.7.10|间接依赖|maven|
|com.orbitz.consul:consul-client|1.5.3|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-kotlin|2.13.4|间接依赖|maven|
|org.apache.skywalking:cluster-zookeeper-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|com.aayushatharva.brotli4j:brotli4j|1.12.0|间接依赖|maven|
|org.apache.skywalking:server-alarm-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.6.21|间接依赖|maven|
|org.apache.yetus:audience-annotations|0.5.0|间接依赖|maven|
|io.netty:netty-tcnative-boringssl-static|2.0.52.Final|直接依赖|maven|
|org.apache.curator:curator-framework|4.3.0|间接依赖|maven|
|com.graphql-java:graphql-java|21.0|直接依赖|maven|
|com.google.re2j:re2j|1.5|间接依赖|maven|
|org.apache.skywalking:log-analyzer|9.6.0-SNAPSHOT|直接依赖|maven|
|io.netty:netty-codec-dns|4.1.86.Final|间接依赖|maven|
|org.apache.skywalking:configuration-consul|9.6.0-SNAPSHOT|直接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j-impl|2.17.1|直接依赖|maven|
|org.jetbrains.kotlinx:kotlinx-coroutines-reactive|1.6.4|间接依赖|maven|
|org.apache.skywalking:apm-network|9.6.0-SNAPSHOT|直接依赖|maven|
|org.postgresql:postgresql|42.4.1|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.11.0|直接依赖|maven|
|google.golang.org/protobuf|v1.28.1|间接依赖|go|
|org.apache.skywalking:configuration-discovery-receiver-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|io.netty:netty-buffer|4.1.79.Final|间接依赖|maven|
|io.fabric8:kubernetes-model-discovery|6.7.1|间接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.94.Final|间接依赖|maven|
|io.grpc:grpc-grpclb|1.53.0|直接依赖|maven|
|org.apache.skywalking:library-module|9.6.0-SNAPSHOT|直接依赖|maven|
|io.fabric8:istio-client|6.7.1|直接依赖|maven|
|org.apache.skywalking:cluster-standalone-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|io.micrometer:micrometer-commons|1.11.1|间接依赖|maven|
|com.squareup.okhttp3:okhttp|3.14.9|间接依赖|maven|
|org.apache.commons:commons-text|1.4|直接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|io.netty:netty-codec-haproxy|4.1.86.Final|间接依赖|maven|
|com.google.guava:guava|32.0.1-jre|直接依赖|maven|
|commons-codec:commons-codec|1.11|间接依赖|maven|
|org.apache.skywalking:configuration-nacos|9.6.0-SNAPSHOT|直接依赖|maven|
|io.grpc:grpc-core|1.53.0|直接依赖|maven|
|io.etcd:jetcd-core|0.5.3|直接依赖|maven|
|io.netty:netty-codec-http2|4.1.79.Final|间接依赖|maven|
|io.fabric8:kubernetes-model-scheduling|6.7.1|间接依赖|maven|
|org.apache.skywalking:skywalking-management-receiver-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|org.apache.skywalking:zipkin-receiver-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|org.apache.skywalking:otel-receiver-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|com.google.flatbuffers:flatbuffers-java|1.12.0|直接依赖|maven|
|google.golang.org/grpc|v1.50.1|间接依赖|go|
|commons-io:commons-io|2.7|直接依赖|maven|
|io.fabric8:kubernetes-client-api|6.7.1|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.7.10|间接依赖|maven|
|build.buf.protoc-gen-validate:protoc-gen-validate|0.6.13|间接依赖|maven|
|skywalking.apache.org/repo/goapi|v0.0.0-20221019074310-53ebda305187|间接依赖|go|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|io.netty:netty-codec|4.1.86.Final|直接依赖|maven|
|commons-net:commons-net|3.9.0|直接依赖|maven|
|com.linecorp.armeria:armeria|1.24.3|直接依赖|maven|
|com.alibaba.nacos:nacos-common|1.4.2|间接依赖|maven|
|org.apache.skywalking:skywalking-telegraf-receiver-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|org.apache.skywalking:aws-firehose-receiver|9.6.0-SNAPSHOT|直接依赖|maven|
|org.jetbrains.kotlinx:kotlinx-coroutines-core-jvm|1.6.4|间接依赖|maven|
|com.linecorp.armeria:armeria-graphql-protocol|1.24.3|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|间接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.53.0|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.86.Final|间接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.86.Final|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.94.Final|间接依赖|maven|
|io.netty:netty-transport|4.1.94.Final|间接依赖|maven|
|com.aayushatharva.brotli4j:service|1.12.0|间接依赖|maven|
|io.prometheus:simpleclient|0.6.0|直接依赖|maven|
|io.netty:netty-tcnative-boringssl-static|2.0.61.Final|间接依赖|maven|
|org.apache.skywalking:configuration-api|9.6.0-SNAPSHOT|直接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.1|间接依赖|maven|
|com.google.code.findbugs:jsr305|1.3.9|间接依赖|maven|
|org.apache.skywalking:skywalking-browser-receiver-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|io.netty:netty-resolver|4.1.86.Final|间接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.21|间接依赖|maven|
|io.fabric8:istio-model-v1beta1|6.7.1|间接依赖|maven|
|io.netty:netty-handler|4.1.86.Final|直接依赖|maven|
|org.apache.skywalking:zipkin-query-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|org.freemarker:freemarker|2.3.31|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.12.0|间接依赖|maven|
|com.squareup.retrofit2:retrofit|2.9.0|间接依赖|maven|
|org.apache.skywalking:library-util|9.6.0-SNAPSHOT|直接依赖|maven|
|build.buf.protoc-gen-validate:pgv-java-stub|0.6.13|间接依赖|maven|
|org.apache.commons:commons-lang3|3.11|间接依赖|maven|
|org.apache.skywalking:skywalking-zabbix-receiver-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|io.fabric8:kubernetes-model-flowcontrol|6.7.1|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|间接依赖|maven|
|io.zipkin.zipkin2:zipkin|2.24.1|直接依赖|maven|
|org.apache.curator:curator-recipes|4.3.0|间接依赖|maven|
|org.apache.skywalking:configuration-zookeeper|9.6.0-SNAPSHOT|直接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.86.Final|间接依赖|maven|
|io.netty:netty-buffer|4.1.86.Final|间接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.17.1|直接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.86.Final|间接依赖|maven|
|org.apache.skywalking:library-client|9.6.0-SNAPSHOT|直接依赖|maven|
|io.fabric8:kubernetes-model-apps|6.7.1|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.5.7|间接依赖|maven|
|net.jodah:failsafe|2.3.4|间接依赖|maven|
|io.fabric8:kubernetes-model-rbac|6.7.1|间接依赖|maven|
|com.h2database:h2|2.1.212|直接依赖|maven|
|org.apache.skywalking:cluster-consul-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.86.Final|间接依赖|maven|
|io.fabric8:kubernetes-model-resource|6.7.1|间接依赖|maven|
|org.apache.skywalking:grpc-configuration-sync|9.6.0-SNAPSHOT|直接依赖|maven|
|org.apache.skywalking:storage-elasticsearch-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.15.2|间接依赖|maven|
|org.apache.skywalking:server-core|9.6.0-SNAPSHOT|直接依赖|maven|
|org.apache.skywalking:server-health-checker|9.6.0-SNAPSHOT|直接依赖|maven|
|org.apache.skywalking:kafka-fetcher-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|io.fabric8:kubernetes-model-networking|6.7.1|间接依赖|maven|
|org.checkerframework:checker-qual|3.33.0|间接依赖|maven|
|golang.org/x/net|v0.7.0|间接依赖|go|
|org.apache.curator:curator-client|4.3.0|间接依赖|maven|
|io.netty:netty-transport|4.1.79.Final|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.21.7|间接依赖|maven|
|commons-validator:commons-validator|1.7|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|直接依赖|maven|
|golang.org/x/sys|v0.5.0|间接依赖|go|
|com.google.protobuf:protobuf-java-util|3.21.8|直接依赖|maven|
|io.fabric8:zjsonpatch|0.3.0|间接依赖|maven|
|org.apache.skywalking:skywalking-profile-receiver-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|io.vavr:vavr-match|0.10.3|间接依赖|maven|
|com.alibaba.nacos:nacos-client|1.4.2|直接依赖|maven|
|org.checkerframework:checker-qual|3.12.0|间接依赖|maven|
|org.apache.skywalking:ai-pipeline|9.6.0-SNAPSHOT|直接依赖|maven|
|org.jetbrains.kotlinx:kotlinx-coroutines-jdk8|1.6.4|间接依赖|maven|
|io.micrometer:micrometer-core|1.11.1|间接依赖|maven|
|org.apache.skywalking:exporter|9.6.0-SNAPSHOT|直接依赖|maven|
|org.apache.skywalking:envoy-metrics-receiver-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|com.squareup.okio:okio|2.8.0|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.30|直接依赖|maven|
|org.apache.skywalking:query-graphql-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|golang.org/x/text|v0.7.0|间接依赖|go|
|io.grpc:grpc-netty|1.53.0|直接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.86.Final|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.45.Final|间接依赖|maven|
|org.apache.skywalking:telemetry-api|9.6.0-SNAPSHOT|直接依赖|maven|
|io.fabric8:kubernetes-model-events|6.7.1|间接依赖|maven|
|io.fabric8:kubernetes-model-batch|6.7.1|间接依赖|maven|
|io.fabric8:kubernetes-model-autoscaling|6.7.1|间接依赖|maven|
|org.apache.skywalking:configuration-apollo|9.6.0-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.15.2|间接依赖|maven|
|org.apache.skywalking:server-testing|9.6.0-SNAPSHOT|直接依赖|maven|
|io.fabric8:kubernetes-httpclient-jdk|6.7.1|直接依赖|maven|
|io.grpc:grpc-api|1.53.0|间接依赖|maven|
|org.apache.skywalking:mqe-rt|9.6.0-SNAPSHOT|直接依赖|maven|
|io.fabric8:kubernetes-client|6.7.1|直接依赖|maven|
|io.netty:netty-common|4.1.86.Final|间接依赖|maven|
|io.grpc:grpc-stub|1.53.0|直接依赖|maven|
|org.apache.skywalking:skywalking-ebpf-receiver-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|org.apache.skywalking:skywalking-clr-receiver-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|io.fabric8:kubernetes-model-extensions|6.7.1|间接依赖|maven|
|io.netty:netty-tcnative-classes|2.0.61.Final|间接依赖|maven|
|io.fabric8:kubernetes-model-storageclass|6.7.1|间接依赖|maven|
|com.ctrip.framework.apollo:apollo-client|1.8.0|直接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.94.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.15.2|直接依赖|maven|
|io.perfmark:perfmark-api|0.25.0|间接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.3|间接依赖|maven|
|org.apache.skywalking:storage-banyandb-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|org.apache.skywalking:skywalking-trace-receiver-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|io.netty:netty-resolver|4.1.79.Final|间接依赖|maven|
|org.apache.skywalking:oal-grammar|9.6.0-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.4|间接依赖|maven|
|com.graphql-java-kickstart:graphql-java-tools|13.0.1|直接依赖|maven|
|org.mvel:mvel2|2.4.8.Final|直接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|2.9.0|间接依赖|maven|
|io.fabric8:kubernetes-model-gatewayapi|6.7.1|间接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.86.Final|间接依赖|maven|
|io.etcd:jetcd-resolver|0.5.3|间接依赖|maven|
|com.squareup.okio:okio|1.17.2|间接依赖|maven|
|org.apache.skywalking:library-server|9.6.0-SNAPSHOT|直接依赖|maven|
|io.netty:netty-tcnative-classes|2.0.54.Final|间接依赖|maven|
|org.apache.skywalking:oal-rt|9.6.0-SNAPSHOT|直接依赖|maven|
|io.fabric8:kubernetes-model-policy|6.7.1|间接依赖|maven|
|com.linecorp.armeria:armeria-graphql|1.24.3|直接依赖|maven|
|org.apache.skywalking:skywalking-meter-receiver-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|com.google.guava:guava|31.1-android|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.15.2|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|com.github.luben:zstd-jni|1.4.9-1|间接依赖|maven|
|io.netty:netty-common|4.1.79.Final|间接依赖|maven|
|org.snakeyaml:snakeyaml-engine|2.6|间接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.94.Final|间接依赖|maven|
|io.fabric8:istio-model-v1alpha3|6.7.1|间接依赖|maven|
|io.fabric8:kubernetes-model-core|6.7.1|间接依赖|maven|
|org.apache.skywalking:cluster-nacos-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|org.antlr:antlr4-runtime|4.11.1|直接依赖|maven|
|io.fabric8:kubernetes-model-admissionregistration|6.7.1|间接依赖|maven|
|org.apache.skywalking:library-kubernetes-support|9.6.0-SNAPSHOT|直接依赖|maven|
|org.apache.skywalking:cluster-kubernetes-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|org.apache.skywalking:logql-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|io.vavr:vavr|0.10.3|直接依赖|maven|
|com.graphql-java:graphql-java-extended-scalars|18.1|直接依赖|maven|
|com.graphql-java:java-dataloader|3.2.0|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.21.8|直接依赖|maven|
|org.apache.skywalking:tool-profile-snapshot-bootstrap|9.6.0-SNAPSHOT|直接依赖|maven|
|io.fabric8:kubernetes-model-node|6.7.1|间接依赖|maven|
|org.apache.skywalking:skywalking-mesh-receiver-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.14.0|间接依赖|maven|
|com.linecorp.armeria:armeria-protobuf|1.24.3|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.6.21|间接依赖|maven|
|io.netty:netty-tcnative-classes|2.0.52.Final|间接依赖|maven|
|com.squareup.okhttp3:okhttp|4.9.0|间接依赖|maven|
|org.slf4j:log4j-over-slf4j|1.7.30|直接依赖|maven|
|io.netty:netty-codec-dns|4.1.94.Final|间接依赖|maven|
|org.jetbrains.kotlinx:kotlinx-coroutines-core|1.6.4|间接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.94.Final|间接依赖|maven|
|org.apache.skywalking:banyandb-java-client|0.4.0|直接依赖|maven|
|io.grpc:grpc-context|1.53.0|间接依赖|maven|
|org.checkerframework:checker-qual|3.5.0|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.79.Final|间接依赖|maven|
|io.netty:netty-resolver|4.1.94.Final|间接依赖|maven|
|org.apache.skywalking:promql-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|org.apache.skywalking:event-analyzer|9.6.0-SNAPSHOT|直接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.94.Final|间接依赖|maven|
|org.javassist:javassist|3.25.0-GA|直接依赖|maven|
|org.apache.skywalking:configuration-k8s-configmap|9.6.0-SNAPSHOT|直接依赖|maven|
|org.apache.skywalking:storage-jdbc-hikaricp-plugin|9.6.0-SNAPSHOT|直接依赖|maven|
|io.grpc:grpc-protobuf|1.53.0|直接依赖|maven|
|io.netty:netty-handler-proxy|4.1.86.Final|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)