# apache/rocketmq安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694771703212498944.svg)](https://www.murphysec.com/console/report/1694771703174750208/1694771703212498944)

仓库描述：Apache RocketMQ is a cloud native messaging and streaming platform, making it simple to build event-driven applications.

仓库地址：[https://github.com/apache/rocketmq](https://github.com/apache/rocketmq)

| star：19691 | watch：882 | fork：11332 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-24 21:32:15 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-25 02:02:21 | 组件总数：112 | 漏洞总数：19 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache Tomcat 授权问题漏洞|会话固定|[MPS-2019-16906](https://www.oscs1024.com/hd/MPS-2019-16906)|CVE-2019-17563|高危|
|Apache Tomcat HTTP请求走私漏洞|HTTP请求走私|[MPS-2020-15344](https://www.oscs1024.com/hd/MPS-2020-15344)|CVE-2020-13943|中危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2020-17486](https://www.oscs1024.com/hd/MPS-2020-17486)|CVE-2020-17527|高危|
|Apache Tomcat 权限管理不当漏洞|权限管理不当|[MPS-2020-2841](https://www.oscs1024.com/hd/MPS-2020-2841)|CVE-2020-1938|严重|
|Apache Tomcat 远程代码执行漏洞|反序列化|[MPS-2020-7626](https://www.oscs1024.com/hd/MPS-2020-7626)|CVE-2020-9484|高危|
|Apache Tomcat 拒绝服务漏洞|拒绝服务|[MPS-2020-9541](https://www.oscs1024.com/hd/MPS-2020-9541)|CVE-2020-11996|高危|
|Apache Tomcat 授权问题漏洞|身份验证不当|[MPS-2021-10264](https://www.oscs1024.com/hd/MPS-2021-10264)|CVE-2021-30640|中危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-1722](https://www.oscs1024.com/hd/MPS-2021-1722)|CVE-2021-24122|中危|
|Apache Tomcat 信息泄露漏洞|HTTP请求走私|[MPS-2021-2309](https://www.oscs1024.com/hd/MPS-2021-2309)|CVE-2021-25122|高危|
|Apache Tomcat 远程代码执行漏洞|代码注入|[MPS-2021-2466](https://www.oscs1024.com/hd/MPS-2021-2466)|CVE-2021-25329|高危|
|Apache Tomcat 拒绝服务漏洞|拒绝服务|[MPS-2021-31848](https://www.oscs1024.com/hd/MPS-2021-31848)|CVE-2021-41079|高危|
|Apache Tomcat 条件竞争漏洞|竞争条件|[MPS-2021-37218](https://www.oscs1024.com/hd/MPS-2021-37218)|CVE-2021-43980|低危|
|Apache Tomcat 环境问题漏洞|HTTP请求走私|[MPS-2021-9711](https://www.oscs1024.com/hd/MPS-2021-9711)|CVE-2021-33037|中危|
|protobuf-java 存在输入验证不当漏洞|拒绝服务|[MPS-2022-56472](https://www.oscs1024.com/hd/MPS-2022-56472)|CVE-2022-3171|中危|
|Google protobuf 安全漏洞|拒绝服务|[MPS-2022-59814](https://www.oscs1024.com/hd/MPS-2022-59814)|CVE-2022-3510|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.apache.tomcat.embed:tomcat-embed-core|8.5.46|11.0.0-m6|间接依赖|强烈建议修复|C:1|H:7|M:4|L:1|
|com.squareup.okio:okio|3.2.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.32|2.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.squareup.okio:okio-jvm|3.0.0|3.4.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.google.protobuf:protobuf-java|3.20.1|3.21.7|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|com.google.guava:guava|31.1-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.bouncycastle:bcprov-jdk15on|1.69||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|97|Low|
|MIT|4|Low|
|GPL-2.0|1|Medium|
|BSD-3-Clause|2|Low|
|LGPL-2.1|2|Medium|
|自定义许可证|5|Low|
|WTFPL|1|Low|
|BSD-2-Clause|1|Low|
|MPL-1.1|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|io.opentelemetry:opentelemetry-exporter-prometheus|1.29.0-alpha|直接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.21|间接依赖|maven|
|org.apache.rocketmq:rocketmq-namesrv|5.1.4-SNAPSHOT|直接依赖|maven|
|org.slf4j:jul-to-slf4j|2.0.6|直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-extension-autoconfigure-spi|1.29.0|间接依赖|maven|
|io.github.aliyunmq:rocketmq-rocksdb|1.0.3|直接依赖|maven|
|org.apache.rocketmq:rocketmq-proto|2.0.3|直接依赖|maven|
|io.github.aliyunmq:rocketmq-logback-classic|1.0.1|直接依赖|maven|
|org.apache.rocketmq:rocketmq-store|5.1.4-SNAPSHOT|直接依赖|maven|
|com.google.truth:truth|0.30|直接依赖|maven|
|org.apache.rocketmq:rocketmq-broker|5.1.4-SNAPSHOT|直接依赖|maven|
|org.apache.rocketmq:rocketmq-acl|5.1.4-SNAPSHOT|直接依赖|maven|
|com.google.protobuf:protobuf-java|3.20.1|间接依赖|maven|
|com.googlecode.concurrentlinkedhashmap:concurrentlinkedhashmap-lru|1.4.2|直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-trace|1.29.0|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk|1.29.0|直接依赖|maven|
|io.opentelemetry:opentelemetry-extension-incubator|1.29.0-alpha|间接依赖|maven|
|commons-codec:commons-codec|1.13|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.6.20|间接依赖|maven|
|org.apache.rocketmq:rocketmq-tools|5.1.4-SNAPSHOT|直接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.50.0|间接依赖|maven|
|io.jaegertracing:jaeger-tracerresolver|1.6.0|间接依赖|maven|
|org.apache.rocketmq:rocketmq-proxy|5.1.4-SNAPSHOT|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.14.0|间接依赖|maven|
|net.java.dev.jna:jna|4.2.2|直接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|直接依赖|maven|
|io.opentelemetry:opentelemetry-context|1.29.0|间接依赖|maven|
|org.apache.tomcat:annotations-api|6.0.53|直接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|org.apache.rocketmq:rocketmq-container|5.1.4-SNAPSHOT|直接依赖|maven|
|com.alibaba:fastjson|1.2.83|直接依赖|maven|
|org.apache.tomcat:tomcat-annotations-api|8.5.46|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-metrics|1.29.0|间接依赖|maven|
|io.grpc:grpc-core|1.50.0|间接依赖|maven|
|org.awaitility:awaitility|4.1.0|直接依赖|maven|
|org.bouncycastle:bcutil-jdk15on|1.69|间接依赖|maven|
|io.grpc:grpc-api|1.50.0|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.69|间接依赖|maven|
|commons-validator:commons-validator|1.7|直接依赖|maven|
|io.netty:netty-tcnative-boringssl-static|2.0.53.Final|直接依赖|maven|
|com.squareup.okio:okio-jvm|3.0.0|直接依赖|maven|
|io.opentracing:opentracing-util|0.33.0|间接依赖|maven|
|io.github.aliyunmq:rocketmq-grpc-netty-codec-haproxy|1.0.0|直接依赖|maven|
|com.squareup.okhttp3:okhttp|4.11.0|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|org.apache.rocketmq:rocketmq-common|5.1.4-SNAPSHOT|直接依赖|maven|
|com.conversantmedia:disruptor|1.2.10|直接依赖|maven|
|io.opentelemetry:opentelemetry-api-events|1.29.0-alpha|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|间接依赖|maven|
|io.opentracing.contrib:opentracing-tracerresolver|0.1.8|间接依赖|maven|
|org.hamcrest:hamcrest|2.1|间接依赖|maven|
|io.openmessaging:openmessaging-api|0.3.1-alpha|直接依赖|maven|
|com.google.code.gson:gson|2.9.0|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|io.grpc:grpc-context|1.50.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.6.20|间接依赖|maven|
|io.openmessaging.storage:dledger|0.3.1.2|直接依赖|maven|
|io.grpc:grpc-services|1.50.0|直接依赖|maven|
|org.apache.rocketmq:rocketmq-tiered-store|5.1.4-SNAPSHOT|直接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-logging|1.29.0|直接依赖|maven|
|org.apache.rocketmq:rocketmq-remoting|5.1.4-SNAPSHOT|直接依赖|maven|
|com.google.guava:guava|31.1-jre|直接依赖|maven|
|io.opentelemetry:opentelemetry-api|1.29.0|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.9.3|直接依赖|maven|
|commons-cli:commons-cli|1.5.0|直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-common|1.29.0|间接依赖|maven|
|org.checkerframework:checker-qual|3.12.0|间接依赖|maven|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|org.slf4j:slf4j-api|2.0.3|直接依赖|maven|
|io.grpc:grpc-stub|1.50.0|直接依赖|maven|
|io.grpc:grpc-netty-shaded|1.50.0|直接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|org.reflections:reflections|0.9.11|直接依赖|maven|
|io.grpc:grpc-protobuf|1.50.0|直接依赖|maven|
|io.jaegertracing:jaeger-core|1.6.0|直接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-sender-okhttp|1.29.0|间接依赖|maven|
|io.perfmark:perfmark-api|0.25.0|间接依赖|maven|
|com.squareup.okio:okio|3.2.0|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|8.5.46|间接依赖|maven|
|org.yaml:snakeyaml|1.32|直接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.69|直接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-common|1.29.0|间接依赖|maven|
|com.google.protobuf:protobuf-java-util|3.20.1|直接依赖|maven|
|io.github.aliyunmq:rocketmq-slf4j-api|1.0.1|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.6.20|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|io.netty:netty-tcnative-classes|2.0.53.Final|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.2-2|直接依赖|maven|
|io.github.aliyunmq:rocketmq-shaded-slf4j-api-bridge|1.0.0|直接依赖|maven|
|commons-io:commons-io|2.7|直接依赖|maven|
|org.apache.rocketmq:rocketmq-openmessaging|5.1.4-SNAPSHOT|直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-logs|1.29.0|间接依赖|maven|
|io.jaegertracing:jaeger-client|1.6.0|直接依赖|maven|
|io.jaegertracing:jaeger-thrift|1.6.0|直接依赖|maven|
|org.lz4:lz4-java|1.8.0|直接依赖|maven|
|commons-digester:commons-digester|2.1|间接依赖|maven|
|org.javassist:javassist|3.20.0-GA|直接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-otlp|1.29.0|直接依赖|maven|
|org.apache.thrift:libthrift|0.14.1|间接依赖|maven|
|org.apache.rocketmq:rocketmq-client|5.1.4-SNAPSHOT|直接依赖|maven|
|io.opentracing:opentracing-noop|0.33.0|间接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|2.9.0|间接依赖|maven|
|org.apache.rocketmq:rocketmq-filter|5.1.4-SNAPSHOT|直接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|io.opentelemetry:opentelemetry-semconv|1.29.0-alpha|间接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-otlp-common|1.29.0|间接依赖|maven|
|org.apache.rocketmq:rocketmq-controller|5.1.4-SNAPSHOT|直接依赖|maven|
|org.apache.rocketmq:rocketmq-srvutil|5.1.4-SNAPSHOT|直接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|io.netty:netty-all|4.1.65.Final|直接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.6.20|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)