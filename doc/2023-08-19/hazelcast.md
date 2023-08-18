# hazelcast/hazelcast安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692599086934282240.svg)](https://www.murphysec.com/console/report/1692599086724567040/1692599086934282240)

仓库描述：Open-source distributed computation and storage platform. Hazelcast is a real-time stream processing platform that lets you build applications that take action on data immediately.

仓库地址：[https://github.com/hazelcast/hazelcast](https://github.com/hazelcast/hazelcast)

| star：5509 | watch：309 | fork：1779 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-19 01:27:11 | 许可证：NOASSERTION |
| 最近检测时间：2023-08-19 02:18:40 | 组件总数：289 | 漏洞总数：4 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Hazelcast<5.1 存在XXE漏洞|XXE|[MPS-2022-1589](https://www.oscs1024.com/hd/MPS-2022-1589)|CVE-2022-0265|严重|
|Hazelcast 安全漏洞|凭证保护不足|[MPS-8wc3-pyfm](https://www.oscs1024.com/hd/MPS-8wc3-pyfm)|CVE-2023-33264|中危|
|Hazelcast 安全漏洞|授权检查缺失|[MPS-p0db-hun3](https://www.oscs1024.com/hd/MPS-p0db-hun3)|CVE-2023-33265|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.hazelcast:hazelcast|5.2.1|5.3.0|直接依赖|建议修复|C:0|H:1|M:1|L:0|
|com.hazelcast:hazelcast|5.0-SNAPSHOT|5.3.0|直接依赖|建议修复|C:1|H:1|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.14.2||直接依赖|建议修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|10|Low|
|Apache-2.0|229|Low|
|EPL-2.0|4|Low|
|EPL-1.0|1|Low|
|MIT-0|1|Low|
|BSD-2-Clause|4|Low|
|BSD-3-Clause|5|Low|
|LGPL-2.1-or-later|1|Low|
|JSON|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.hazelcast.jsurfer:jsurfer-jackson-jr|0.11|直接依赖|maven|
|org.checkerframework:checker-qual|3.37.0|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.10.1|间接依赖|maven|
|com.hazelcast.jet:hazelcast-jet-hadoop-dist|5.4.0-SNAPSHOT|直接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|6.5.1|间接依赖|maven|
|com.hazelcast.jet:hazelcast-jet-protobuf|5.4.0-SNAPSHOT|直接依赖|maven|
|org.eclipse.jetty:jetty-util-ajax|9.4.51.v20230217|间接依赖|maven|
|junit:junit|4.13.2|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.14|间接依赖|maven|
|com.google.auto.value:auto-value-annotations|1.10.3|间接依赖|maven|
|com.hazelcast.jsurfer:jsurfer-core|0.11|直接依赖|maven|
|com.hazelcast.jet:hazelcast-jet-kinesis|5.4.0-SNAPSHOT|直接依赖|maven|
|com.hazelcast:hazelcast-spring|5.4.0-SNAPSHOT|直接依赖|maven|
|software.amazon.awssdk:s3|2.20.123|直接依赖|maven|
|org.apache.lucene:lucene-suggest|8.11.1|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|org.elasticsearch.plugin:lang-mustache-client|7.17.12|间接依赖|maven|
|com.hazelcast:hazelcast|5.2.1|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.14.2|直接依赖|maven|
|io.perfmark:perfmark-api|0.25.0|间接依赖|maven|
|com.hazelcast.jet:hazelcast-jet-avro|5.4.0-SNAPSHOT|直接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|com.google.cloud.bigdataoss:util-hadoop|hadoop3-2.2.4|间接依赖|maven|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|3.3.6|间接依赖|maven|
|io.grpc:grpc-grpclb|1.48.0|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.51.v20230217|间接依赖|maven|
|com.google.http-client:google-http-client-jackson2|1.43.2|间接依赖|maven|
|io.debezium:debezium-core|1.9.7.Final|直接依赖|maven|
|org.elasticsearch:elasticsearch-geo|7.17.12|间接依赖|maven|
|io.grpc:grpc-protobuf|1.48.0|直接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.4|间接依赖|maven|
|org.mongodb:bson-record-codec|4.10.2|间接依赖|maven|
|software.amazon.awssdk:arns|2.20.123|间接依赖|maven|
|commons-io:commons-io|2.13.0|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.9|间接依赖|maven|
|dnsjava:dnsjava|2.1.7|间接依赖|maven|
|com.amazonaws:aws-java-sdk-kinesis|1.12.531|直接依赖|maven|
|com.google.auth:google-auth-library-oauth2-http|1.19.0|间接依赖|maven|
|com.hazelcast:hazelcast-spring-tests|5.4.0-SNAPSHOT|直接依赖|maven|
|org.yaml:snakeyaml|2.1|间接依赖|maven|
|software.amazon.awssdk:aws-core|2.20.123|间接依赖|maven|
|com.hazelcast:hazelcast-mapstore|5.4.0-SNAPSHOT|直接依赖|maven|
|org.elasticsearch:elasticsearch-lz4|7.17.12|间接依赖|maven|
|software.amazon.awssdk:crt-core|2.20.123|间接依赖|maven|
|org.postgresql:postgresql|42.6.0|间接依赖|maven|
|com.fasterxml.jackson.jr:jackson-jr-annotation-support|2.14.2|直接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.1|间接依赖|maven|
|org.apache.avro:avro|1.11.2|直接依赖|maven|
|software.amazon.eventstream:eventstream|1.0.1|间接依赖|maven|
|org.jctools:jctools-core|4.0.1|直接依赖|maven|
|com.amazonaws:aws-java-sdk-s3|1.12.531|直接依赖|maven|
|com.google.flogger:flogger|0.7.1|间接依赖|maven|
|com.microsoft.azure:azure-storage|7.0.1|间接依赖|maven|
|io.github.classgraph:classgraph|4.8.162|直接依赖|maven|
|com.hazelcast.jet:hazelcast-jet-cdc-debezium|5.4.0-SNAPSHOT|直接依赖|maven|
|org.elasticsearch:elasticsearch-cli|7.17.12|间接依赖|maven|
|io.debezium:debezium-api|1.9.7.Final|间接依赖|maven|
|org.apache.kafka:kafka-clients|3.4.1|直接依赖|maven|
|software.amazon.awssdk:aws-query-protocol|2.20.123|间接依赖|maven|
|com.google.api.grpc:proto-google-iam-v1|1.18.0|间接依赖|maven|
|org.apache.lucene:lucene-analyzers-common|8.11.1|间接依赖|maven|
|org.mongodb:mongodb-driver-core|4.10.2|间接依赖|maven|
|org.conscrypt:conscrypt-openjdk-uber|2.5.2|间接依赖|maven|
|com.fasterxml.jackson.jr:jackson-jr-objects|2.14.2|直接依赖|maven|
|io.airlift:aircompressor|0.21|间接依赖|maven|
|org.fusesource.jansi:jansi|2.4.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.14.2|直接依赖|maven|
|com.jayway.jsonpath:json-path|2.7.0|间接依赖|maven|
|com.hazelcast.jet:hazelcast-jet-files-gcs|5.4.0-SNAPSHOT|直接依赖|maven|
|org.mongodb:bson|4.10.2|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.14.2|间接依赖|maven|
|commons-cli:commons-cli|1.2|间接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5|5.1.3|间接依赖|maven|
|io.grpc:grpc-netty-shaded|1.48.0|直接依赖|maven|
|commons-pool:commons-pool|1.6|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|3.2.4|间接依赖|maven|
|com.microsoft.azure:azure-data-lake-store-sdk|2.3.9|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.16|间接依赖|maven|
|org.jline:jline-reader|3.23.0|直接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.96.Final|间接依赖|maven|
|org.jline:jline-native|3.23.0|间接依赖|maven|
|com.hazelcast.jet:hazelcast-jet-files-s3|5.4.0-SNAPSHOT|直接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|com.hazelcast.jet:hazelcast-jet-cdc-mysql|5.4.0-SNAPSHOT|直接依赖|maven|
|software.amazon.awssdk:protocol-core|2.20.123|间接依赖|maven|
|org.assertj:assertj-core|3.24.2|直接依赖|maven|
|com.hazelcast.jet:hazelcast-jet-mongodb|5.4.0-SNAPSHOT|直接依赖|maven|
|software.amazon.awssdk:regions|2.20.123|间接依赖|maven|
|org.apache.parquet:parquet-hadoop|1.13.1|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.20.0|间接依赖|maven|
|org.apache.calcite.avatica:avatica-core|1.22.0|间接依赖|maven|
|software.amazon.awssdk:apache-client|2.20.123|间接依赖|maven|
|com.hazelcast:hazelcast-wm|4.0|直接依赖|maven|
|com.hazelcast:hazelcast-distribution|5.4.0-SNAPSHOT|直接依赖|maven|
|org.apache.lucene:lucene-queries|8.11.1|间接依赖|maven|
|software.amazon.awssdk:profiles|2.20.123|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|org.apache.lucene:lucene-backward-codecs|8.11.1|间接依赖|maven|
|org.codehaus.woodstox:stax2-api|4.2.1|间接依赖|maven|
|software.amazon.awssdk:annotations|2.20.123|间接依赖|maven|
|software.amazon.awssdk:aws-xml-protocol|2.20.123|间接依赖|maven|
|io.grpc:grpc-context|1.48.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.20.0|直接依赖|maven|
|org.elasticsearch.plugin:rank-eval-client|7.17.12|间接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|io.opencensus:opencensus-contrib-http-util|0.31.1|间接依赖|maven|
|com.microsoft.azure:azure-keyvault-core|1.0.0|间接依赖|maven|
|org.apache.avro:avro-mapred|1.11.2|直接依赖|maven|
|io.grpc:grpc-api|1.48.0|直接依赖|maven|
|com.tngtech.archunit:archunit|1.1.0|直接依赖|maven|
|com.google.cloud.bigdataoss:gcs-connector|hadoop3-2.2.4|直接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-client|7.17.12|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|间接依赖|maven|
|net.bytebuddy:byte-buddy-agent|1.14.6|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-smile|2.14.2|间接依赖|maven|
|com.hazelcast:modulepath-tests|5.4.0-SNAPSHOT|直接依赖|maven|
|org.apache.lucene:lucene-spatial3d|8.11.1|间接依赖|maven|
|com.google.protobuf:protobuf-java-util|3.23.2|间接依赖|maven|
|org.jline:jline-terminal|3.23.0|直接依赖|maven|
|com.google.guava:guava|32.1.2-jre|直接依赖|maven|
|com.hazelcast.jet:hazelcast-jet-python|5.4.0-SNAPSHOT|直接依赖|maven|
|org.apache.commons:commons-configuration2|2.8.0|间接依赖|maven|
|net.sf.jopt-simple:jopt-simple|5.0.2|间接依赖|maven|
|org.apache.lucene:lucene-queryparser|8.11.1|间接依赖|maven|
|com.google.code.gson:gson|2.10.1|直接依赖|maven|
|com.amazonaws:aws-java-sdk-core|1.12.531|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.21.1|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.23.2|直接依赖|maven|
|io.debezium:debezium-connector-postgres|1.9.7.Final|直接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5-h2|5.1.3|间接依赖|maven|
|org.apache.hadoop:hadoop-common|3.3.6|间接依赖|maven|
|org.antlr:antlr4-runtime|4.9.3|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.96.Final|间接依赖|maven|
|com.hazelcast.jet:hazelcast-jet-kafka|5.4.0-SNAPSHOT|直接依赖|maven|
|com.github.erosb:everit-json-schema|1.14.2|直接依赖|maven|
|com.google.api-client:google-api-client|1.32.2|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-csv|2.14.2|直接依赖|maven|
|info.picocli:picocli|4.7.4|直接依赖|maven|
|org.checkerframework:checker-compat-qual|2.5.3|间接依赖|maven|
|org.elasticsearch.plugin:parent-join-client|7.17.12|间接依赖|maven|
|com.hazelcast:hazelcast|5.0-SNAPSHOT|直接依赖|maven|
|org.objenesis:objenesis|3.3|直接依赖|maven|
|org.locationtech.jts:jts-core|1.19.0|间接依赖|maven|
|mysql:mysql-connector-java|8.0.28|间接依赖|maven|
|org.apache.lucene:lucene-grouping|8.11.1|间接依赖|maven|
|com.amazonaws:aws-java-sdk-dynamodb|1.12.531|直接依赖|maven|
|com.hazelcast.jet:hazelcast-jet-extensions|5.4.0-SNAPSHOT|直接依赖|maven|
|com.amazonaws:aws-java-sdk-kms|1.12.531|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.14.2|间接依赖|maven|
|org.hamcrest:hamcrest-core|1.3|间接依赖|maven|
|com.carrotsearch:hppc|0.8.1|间接依赖|maven|
|net.java.dev.jna:jna|5.13.0|间接依赖|maven|
|com.google.http-client:google-http-client-apache-v2|1.43.2|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|com.google.auth:google-auth-library-credentials|1.19.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.14.2|直接依赖|maven|
|org.apache.httpcomponents.client5:httpclient5|5.1.3|间接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j-impl|2.20.0|直接依赖|maven|
|org.apache.lucene:lucene-core|8.11.1|间接依赖|maven|
|org.apache.parquet:parquet-format-structures|1.13.1|间接依赖|maven|
|org.wildfly.openssl:wildfly-openssl|1.1.3.Final|间接依赖|maven|
|com.google.uzaygezen:uzaygezen-core|0.2|间接依赖|maven|
|org.elasticsearch.plugin:aggs-matrix-stats-client|7.17.12|间接依赖|maven|
|org.apache.lucene:lucene-highlighter|8.11.1|间接依赖|maven|
|io.opencensus:opencensus-api|0.31.1|间接依赖|maven|
|com.hazelcast:hazelcast-root|5.4.0-SNAPSHOT|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|org.lz4:lz4-java|1.8.0|间接依赖|maven|
|org.elasticsearch:elasticsearch-secure-sm|7.17.12|间接依赖|maven|
|software.amazon.awssdk:netty-nio-client|2.20.123|间接依赖|maven|
|org.apache.hadoop.thirdparty:hadoop-shaded-guava|1.1.1|间接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|直接依赖|maven|
|software.amazon.awssdk:metrics-spi|2.20.123|间接依赖|maven|
|org.apache.kafka:connect-api|3.4.1|直接依赖|maven|
|com.hazelcast:hazelcast-archunit-rules|5.4.0-SNAPSHOT|直接依赖|maven|
|org.apache.logging.log4j:log4j-layout-template-json|2.20.0|直接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|9.31|间接依赖|maven|
|com.google.http-client:google-http-client-gson|1.43.2|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|com.hazelcast:hazelcast-tpc-engine|5.4.0-SNAPSHOT|直接依赖|maven|
|org.elasticsearch:elasticsearch-core|7.17.12|间接依赖|maven|
|libc.so.6||间接依赖||
|org.apache.commons:commons-lang3|3.13.0|间接依赖|maven|
|org.codehaus.janino:commons-compiler|3.1.8|间接依赖|maven|
|software.amazon.awssdk:utils|2.20.123|间接依赖|maven|
|com.google.api.grpc:proto-google-cloud-storage-v2|2.0.1-alpha|间接依赖|maven|
|org.mongodb:mongodb-driver-sync|4.10.2|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.14.2|直接依赖|maven|
|org.apache.calcite:calcite-core|1.32.0|直接依赖|maven|
|io.netty:netty-handler|4.1.96.Final|间接依赖|maven|
|com.hazelcast.jet:hazelcast-jet-csv|5.4.0-SNAPSHOT|直接依赖|maven|
|org.elasticsearch.plugin:mapper-extras-client|7.17.12|间接依赖|maven|
|com.hazelcast:hazelcast-build-utils|5.4.0-SNAPSHOT|直接依赖|maven|
|io.debezium:debezium-connector-mysql|1.9.7.Final|直接依赖|maven|
|org.apache.parquet:parquet-avro|1.13.1|直接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-high-level-client|7.17.12|直接依赖|maven|
|software.amazon.awssdk:endpoints-spi|2.20.123|间接依赖|maven|
|io.debezium:debezium-ddl-parser|1.9.7.Final|间接依赖|maven|
|software.amazon.awssdk:third-party-jackson-core|2.20.123|间接依赖|maven|
|org.apache.parquet:parquet-encoding|1.13.1|间接依赖|maven|
|com.google.oauth-client:google-oauth-client|1.34.1|间接依赖|maven|
|com.google.re2j:re2j|1.1|间接依赖|maven|
|io.grpc:grpc-alts|1.48.0|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.14.6|直接依赖|maven|
|io.netty:netty-transport|4.1.96.Final|间接依赖|maven|
|org.elasticsearch:elasticsearch-plugin-classloader|7.17.12|间接依赖|maven|
|org.apache.hadoop:hadoop-azure|3.3.6|直接依赖|maven|
|com.zendesk:mysql-binlog-connector-java|0.27.2|间接依赖|maven|
|io.netty:netty-common|4.1.96.Final|间接依赖|maven|
|joda-time:joda-time|2.12.5|间接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.48.0|间接依赖|maven|
|com.hazelcast.jet:hazelcast-jet-hadoop|5.4.0-SNAPSHOT|直接依赖|maven|
|biz.aQute:bndlib|1.50.0|直接依赖|maven|
|org.apache.commons:commons-math3|3.1.1|间接依赖|maven|
|com.hazelcast.jet:hazelcast-jet-hadoop-core|5.4.0-SNAPSHOT|直接依赖|maven|
|com.google.flogger:flogger-system-backend|0.7.1|间接依赖|maven|
|com.hazelcast.jet:hazelcast-jet-grpc|5.4.0-SNAPSHOT|直接依赖|maven|
|com.google.http-client:google-http-client|1.43.2|间接依赖|maven|
|io.grpc:grpc-core|1.48.0|间接依赖|maven|
|org.json:json|20230227|间接依赖|maven|
|com.google.api-client:google-api-client-jackson2|1.32.2|间接依赖|maven|
|org.apache.hadoop:hadoop-hdfs-client|3.3.6|间接依赖|maven|
|com.hazelcast.jet:hazelcast-jet-s3|5.4.0-SNAPSHOT|直接依赖|maven|
|org.apache.lucene:lucene-join|8.11.1|间接依赖|maven|
|org.apache.parquet:parquet-jackson|1.13.1|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|io.grpc:grpc-stub|1.48.0|直接依赖|maven|
|org.apache.lucene:lucene-misc|8.11.1|间接依赖|maven|
|io.grpc:grpc-auth|1.48.0|间接依赖|maven|
|com.google.apis:google-api-services-iamcredentials|v1-rev20210326-1.32.1|间接依赖|maven|
|org.apache.lucene:lucene-sandbox|8.11.1|间接依赖|maven|
|org.apache.parquet:parquet-column|1.13.1|间接依赖|maven|
|software.amazon.awssdk:json-utils|2.20.123|间接依赖|maven|
|io.netty:netty-resolver|4.1.96.Final|间接依赖|maven|
|com.hazelcast:hazelcast-it|5.4.0-SNAPSHOT|直接依赖|maven|
|org.apache.hadoop.thirdparty:hadoop-shaded-protobuf_3_7|1.1.1|间接依赖|maven|
|org.elasticsearch:elasticsearch|7.17.12|间接依赖|maven|
|org.apache.lucene:lucene-memory|8.11.1|间接依赖|maven|
|javax.ws.rs:javax.ws.rs-api|2.1.1|间接依赖|maven|
|org.elasticsearch:elasticsearch-x-content|7.17.12|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.5-5|间接依赖|maven|
|com.github.spullara.mustache.java:compiler|0.9.6|间接依赖|maven|
|software.amazon.awssdk:sdk-core|2.20.123|间接依赖|maven|
|org.apache.hadoop:hadoop-auth|3.3.6|间接依赖|maven|
|com.google.flogger:google-extensions|0.7.1|间接依赖|maven|
|io.prometheus.jmx:jmx_prometheus_javaagent|0.19.0|直接依赖|maven|
|com.hazelcast:hazelcast-sql|5.4.0-SNAPSHOT|直接依赖|maven|
|com.google.cloud.bigdataoss:util|2.2.4|间接依赖|maven|
|org.apache.hadoop:hadoop-client|3.3.6|直接依赖|maven|
|org.apache.hadoop:hadoop-aws|3.3.6|直接依赖|maven|
|com.hazelcast.jet:hazelcast-jet-hadoop-all|5.4.0-SNAPSHOT|直接依赖|maven|
|org.jline:jline-terminal-jansi|3.23.0|直接依赖|maven|
|org.apache.commons:commons-compress|1.23.0|间接依赖|maven|
|software.amazon.awssdk:http-client-spi|2.20.123|间接依赖|maven|
|com.hazelcast.jet:hazelcast-jet-elasticsearch-7|5.4.0-SNAPSHOT|直接依赖|maven|
|io.netty:netty-codec-http2|4.1.96.Final|间接依赖|maven|
|software.amazon.awssdk:auth|2.20.123|间接依赖|maven|
|javax.cache:cache-api|1.1.1|直接依赖|maven|
|org.apache.kafka:connect-transforms|3.4.1|直接依赖|maven|
|io.netty:netty-codec|4.1.96.Final|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.21|间接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.12|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|2.8|间接依赖|maven|
|com.hazelcast.jet:hazelcast-jet-files-azure|5.4.0-SNAPSHOT|直接依赖|maven|
|org.apache.hadoop:hadoop-azure-datalake|3.3.6|直接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|2.23.0|间接依赖|maven|
|io.netty:netty-codec-http|4.1.96.Final|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-jobclient|3.3.6|间接依赖|maven|
|commons-net:commons-net|3.9.0|间接依赖|maven|
|io.netty:netty-buffer|4.1.96.Final|间接依赖|maven|
|com.github.stephenc.jcip:jcip-annotations|1.0-1|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-core|3.3.6|间接依赖|maven|
|com.google.api.grpc:grpc-google-cloud-storage-v2|2.0.1-alpha|间接依赖|maven|
|com.google.apis:google-api-services-storage|v1-rev20211018-1.32.1|间接依赖|maven|
|com.hazelcast:hazelcast|5.4.0-SNAPSHOT|直接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-common|3.3.6|间接依赖|maven|
|com.hazelcast.jet:hazelcast-jet-cdc-postgres|5.4.0-SNAPSHOT|直接依赖|maven|
|org.snakeyaml:snakeyaml-engine|2.6|直接依赖|maven|
|com.google.cloud.bigdataoss:gcsio|2.2.4|间接依赖|maven|
|com.tdunning:t-digest|3.2|间接依赖|maven|
|com.amazonaws:jmespath-java|1.12.531|间接依赖|maven|
|commons-codec:commons-codec|1.16.0|间接依赖|maven|
|org.apache.parquet:parquet-common|1.13.1|间接依赖|maven|
|org.apache.commons:commons-text|1.10.0|直接依赖|maven|
|software.amazon.ion:ion-java|1.0.2|间接依赖|maven|
|org.codehaus.janino:janino|3.1.8|间接依赖|maven|
|com.hazelcast.jet:hazelcast-jet-kafka-connect|5.4.0-SNAPSHOT|直接依赖|maven|
|org.apache.calcite:calcite-linq4j|1.32.0|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)