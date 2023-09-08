# apache/iceberg安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700209242715848704.svg)](https://www.murphysec.com/console/report/1691872734232858624/1700209242715848704)

仓库描述：Apache Iceberg

仓库地址：[https://github.com/apache/iceberg](https://github.com/apache/iceberg)

| star：4727 | watch：152 | fork：1767 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-08 23:51:37 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-09 02:54:42 | 组件总数：246 | 漏洞总数：7 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Netty 存在信息泄露漏洞||[MPS-2022-3790](https://www.oscs1024.com/hd/MPS-2022-3790)|CVE-2022-24823|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.fasterxml.jackson.core:jackson-databind|2.15.2||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.xerial.snappy:snappy-java|1.1.8.3|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.14.3||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.15.1||间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.14.2||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|io.netty:netty-handler|4.1.94.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.5|2.14.0-rc1|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|io.netty:netty-common|4.1.68.Final|4.1.77.Final|直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|174|Low|
|自定义许可证|13|Low|
|ISC|4|Low|
|MIT|21|Low|
|BSD-3-Clause|9|Low|
|LGPL-2.1-or-later|2|Low|
|MIT-0|1|Low|
|BSD-2-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.fasterxml.jackson.core:jackson-core|2.15.1|间接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|6.4.0|间接依赖|maven|
|com.google.auto.value:auto-value-annotations|1.10.1|直接依赖|maven|
|org.apache.arrow:arrow-format|12.0.1|间接依赖|maven|
|io.netty:netty-codec-http|4.1.94.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.5|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.14.3|直接依赖|maven|
|::iceberg-bundled-guava||直接依赖|maven|
|org.abego.treelayout:org.abego.treelayout.core|1.0.3|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.15.2|直接依赖|maven|
|jinja2|3.1.2|间接依赖|pip|
|io.netty:netty-handler|4.1.94.Final|间接依赖|maven|
|io.grpc:grpc-googleapis|1.55.1|直接依赖|maven|
|com.google.api.grpc:proto-google-iam-v1|1.16.0|直接依赖|maven|
|io.projectreactor:reactor-core|3.4.30|间接依赖|maven|
|software.amazon.awssdk:sts|2.20.131|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.15.2|间接依赖|maven|
|org.apache.arrow:arrow-vector|12.0.1|直接依赖|maven|
|io.opencensus:opencensus-contrib-http-util|0.31.1|直接依赖|maven|
|io.dropwizard.metrics:metrics-core|3.2.6|直接依赖|maven|
|io.grpc:grpc-stub|1.55.1|直接依赖|maven|
|com.google.j2objc:j2objc-annotations|2.8|直接依赖|maven|
|com.fasterxml.jackson:jackson-bom|2.13.5|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|直接依赖|maven|
|io.netty:netty-common|4.1.94.Final|间接依赖|maven|
|com.google.api-client:google-api-client|2.2.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.5|间接依赖|maven|
|software.amazon.awssdk:aws-core|2.20.131|直接依赖|maven|
|griffe|0.36.0|间接依赖|pip|
|mkdocs-material-extensions|1.1.1|间接依赖|pip|
|mkdocs|1.5.2|间接依赖|pip|
|com.fasterxml.jackson.core:jackson-databind|2.14.3|直接依赖|maven|
|software.amazon.awssdk:arns|2.20.131|间接依赖|maven|
|io.grpc:grpc-netty-shaded|1.55.1|直接依赖|maven|
|software.amazon.awssdk:apache-client|2.20.131|直接依赖|maven|
|io.netty:netty-buffer|4.1.94.Final|间接依赖|maven|
|software.amazon.awssdk:auth|2.20.131|直接依赖|maven|
|software.amazon.awssdk:protocol-core|2.20.131|直接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.94.Final|间接依赖|maven|
|org.conscrypt:conscrypt-openjdk-uber|2.5.2|直接依赖|maven|
|org.antlr:ST4|4.3.1|间接依赖|maven|
|com.google.api:gax-grpc|2.30.0|直接依赖|maven|
|::iceberg-flink:iceberg-flink-1.17||直接依赖|maven|
|com.google.auth:google-auth-library-oauth2-http|1.18.0|直接依赖|maven|
|com.azure:azure-storage-common|12.22.1|间接依赖|maven|
|io.grpc:grpc-api|1.55.1|直接依赖|maven|
|com.google.api:gax|2.30.0|直接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.9.3|直接依赖|maven|
|io.opencensus:opencensus-proto|0.2.0|直接依赖|maven|
|::iceberg-snowflake||直接依赖|maven|
|org.checkerframework:checker-qual|3.19.0|间接依赖|maven|
|com.google.api:gax-httpjson|2.30.0|直接依赖|maven|
|io.grpc:grpc-rls|1.55.1|直接依赖|maven|
|org.threeten:threeten-extra|1.7.1|直接依赖|maven|
|org.projectnessie.nessie:nessie-model|0.67.0|间接依赖|maven|
|io.opencensus:opencensus-api|0.31.1|直接依赖|maven|
|software.amazon.awssdk:bom|2.20.131|直接依赖|maven|
|org.apache.arrow:arrow-memory-core|12.0.1|间接依赖|maven|
|org.ow2.asm:asm|9.3|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|直接依赖|maven|
|com.nimbusds:oauth2-oidc-sdk|10.7.1|间接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.94.Final|间接依赖|maven|
|org.apache.parquet:parquet-hadoop|1.13.1|直接依赖|maven|
|org.glassfish:javax.json|1.0.4|间接依赖|maven|
|software.amazon.awssdk:glue|2.20.131|直接依赖|maven|
|software.amazon.awssdk:netty-nio-client|2.20.131|直接依赖|maven|
|software.amazon.awssdk:iam|2.20.131|直接依赖|maven|
|net.java.dev.jna:jna-platform|5.13.0|直接依赖|maven|
|io.grpc:grpc-core|1.55.1|直接依赖|maven|
|::iceberg-nessie||直接依赖|maven|
|io.grpc:grpc-context|1.55.1|直接依赖|maven|
|io.netty:netty-resolver|4.1.94.Final|间接依赖|maven|
|com.google.cloud:google-cloud-core-grpc|2.20.0|直接依赖|maven|
|::iceberg-core||直接依赖|maven|
|org.apache.parquet:parquet-common|1.13.1|直接依赖|maven|
|com.google.cloud:google-cloud-core-http|2.20.0|直接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.94.Final|间接依赖|maven|
|com.google.code.gson:gson|2.10.1|直接依赖|maven|
|software.amazon.awssdk:sso|2.20.131|直接依赖|maven|
|com.google.http-client:google-http-client|1.43.3|直接依赖|maven|
|io.netty:netty-resolver-dns|4.1.93.Final|间接依赖|maven|
|software.amazon.awssdk:endpoints-spi|2.20.131|直接依赖|maven|
|io.grpc:grpc-xds|1.55.1|直接依赖|maven|
|com.azure:azure-core|1.42.0|直接依赖|maven|
|org.apache.arrow:arrow-memory-netty|12.0.1|直接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.3|间接依赖|maven|
|org.apache.orc:orc-core|1.9.1|直接依赖|maven|
|org.scala-lang:scala-library|2.12.17|间接依赖|maven|
|mkdocs-material|9.2.7|间接依赖|pip|
|com.nimbusds:nimbus-jose-jwt|9.30.2|间接依赖|maven|
|org.apache.parquet:parquet-format-structures|1.13.1|间接依赖|maven|
|org.jetbrains:annotations|17.0.0|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-xml|2.13.5|间接依赖|maven|
|mkdocstrings-python|1.6.0|间接依赖|pip|
|com.fasterxml.jackson:jackson-bom|2.15.2|直接依赖|maven|
|commons-pool:commons-pool|1.6|间接依赖|maven|
|com.google.http-client:google-http-client-jackson2|1.43.3|直接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5-h2|5.2|间接依赖|maven|
|software.amazon.awssdk:aws-query-protocol|2.20.131|间接依赖|maven|
|::iceberg-spark:iceberg-spark-3.4_2.12||直接依赖|maven|
|org.slf4j:slf4j-api|2.0.7|直接依赖|maven|
|org.apache.parquet:parquet-encoding|1.13.1|间接依赖|maven|
|commons-codec:commons-codec|1.15|直接依赖|maven|
|io.netty:netty-codec|4.1.94.Final|间接依赖|maven|
|com.google.http-client:google-http-client-gson|1.43.3|直接依赖|maven|
|com.google.api:api-common|2.13.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.5|间接依赖|maven|
|::iceberg-azure||直接依赖|maven|
|org.codehaus.woodstox:stax2-api|4.2.1|间接依赖|maven|
|io.airlift:aircompressor|0.25|直接依赖|maven|
|org.apache.parquet:parquet-column|1.13.1|直接依赖|maven|
|net.minidev:json-smart||间接依赖|maven|
|::iceberg-gcp||直接依赖|maven|
|org.apache.parquet:parquet-avro|1.13.1|直接依赖|maven|
|io.grpc:grpc-alts|1.55.1|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.15.1|间接依赖|maven|
|io.grpc:grpc-grpclb|1.55.1|直接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|直接依赖|maven|
|org.antlr:antlr4-runtime|4.9.3|直接依赖|maven|
|org.antlr:antlr-runtime|3.5.2|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-http|1.0.33|间接依赖|maven|
|com.google.errorprone:error||直接依赖|maven|
|com.nimbusds:content-type|2.2|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|::iceberg-arrow||直接依赖|maven|
|mkdocs-autorefs|0.5.0|间接依赖|pip|
|com.google.android:annotations|4.1.1.4|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.15.2|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|直接依赖|maven|
|::iceberg-data||直接依赖|maven|
|org.apache.yetus:audience-annotations|0.13.0|间接依赖|maven|
|org.apache.flink:flink-metrics-dropwizard||直接依赖|maven|
|software.amazon.eventstream:eventstream|1.0.1|间接依赖|maven|
|software.amazon.awssdk:aws-xml-protocol|2.20.131|间接依赖|maven|
|io.grpc:grpc-auth|1.55.1|直接依赖|maven|
|org.eclipse.microprofile.openapi:microprofile-openapi-api|3.1.1|间接依赖|maven|
|com.google.apis:google-api-services-storage|v1-rev20230301-2.0.0|直接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.93.Final|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|直接依赖|maven|
|io.netty:netty-handler-proxy|4.1.94.Final|间接依赖|maven|
|com.azure:azure-sdk-bom|1.2.16|直接依赖|maven|
|software.amazon.awssdk:http-client-spi|2.20.131|直接依赖|maven|
|software.amazon.awssdk:sdk-core|2.20.131|直接依赖|maven|
|com.fasterxml.jackson:jackson-bom|2.14.2|直接依赖|maven|
|io.netty:netty-buffer|4.1.68.Final|直接依赖|maven|
|com.fasterxml.jackson:jackson-bom|2.15.1|间接依赖|maven|
|net.minidev:json-smart|2.4.10|间接依赖|maven|
|software.amazon.awssdk:aws-json-protocol|2.20.131|直接依赖|maven|
|com.microsoft.azure:msal4j|1.13.9|直接依赖|maven|
|io.netty:netty-common|4.1.68.Final|直接依赖|maven|
|org.apache.httpcomponents.client5:httpclient5|5.2.1|直接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.94.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.14.2|直接依赖|maven|
|software.amazon.awssdk:utils|2.20.131|直接依赖|maven|
|software.amazon.awssdk:kms|2.20.131|直接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.94.Final|间接依赖|maven|
|com.google.protobuf:protobuf-java-util|3.23.2|直接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.93.Final|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.23|直接依赖|maven|
|org.apache.parquet:parquet-jackson|1.13.1|间接依赖|maven|
|software.amazon.awssdk:s3|2.20.131|直接依赖|maven|
|com.google.cloud:google-cloud-storage|2.22.5|直接依赖|maven|
|software.amazon.awssdk:crt-core|2.20.131|间接依赖|maven|
|com.google.flatbuffers:flatbuffers-java|1.12.0|间接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|2.21.0|直接依赖|maven|
|com.google.oauth-client:google-oauth-client|1.34.1|直接依赖|maven|
|::iceberg-mr||直接依赖|maven|
|org.roaringbitmap:RoaringBitmap|0.9.47|直接依赖|maven|
|org.apache.orc:orc-shims|1.9.1|直接依赖|maven|
|software.amazon.awssdk:metrics-spi|2.20.131|直接依赖|maven|
|com.github.stephenc.jcip:jcip-annotations|1.0-1|间接依赖|maven|
|org.threeten:threetenbp|1.6.8|直接依赖|maven|
|com.google.http-client:google-http-client-apache-v2|1.43.3|直接依赖|maven|
|com.google.http-client:google-http-client-appengine|1.43.3|直接依赖|maven|
|com.google.api.grpc:gapic-google-cloud-storage-v2|2.22.5-alpha|直接依赖|maven|
|com.google.auth:google-auth-library-credentials|1.18.0|直接依赖|maven|
|::iceberg-api||直接依赖|maven|
|io.netty:netty-codec-http2|4.1.94.Final|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.13|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.23.2|直接依赖|maven|
|mkdocs-literate-nav|0.6.0|间接依赖|pip|
|::iceberg-aliyun||直接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.14.2|直接依赖|maven|
|com.azure:azure-json|1.1.0|间接依赖|maven|
|com.google.api.grpc:proto-google-cloud-storage-v2|2.22.5-alpha|直接依赖|maven|
|net.snowflake:snowflake-jdbc|3.13.30|直接依赖|maven|
|::iceberg-common||直接依赖|maven|
|io.netty:netty-tcnative-classes|2.0.61.Final|间接依赖|maven|
|com.microsoft.azure:msal4j-persistence-extension|1.2.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.15.1|间接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|com.google.re2j:re2j|1.6|直接依赖|maven|
|::iceberg-parquet||直接依赖|maven|
|org.apache.commons:commons-compress|1.21|间接依赖|maven|
|com.azure:azure-storage-internal-avro|12.8.1|间接依赖|maven|
|software.amazon.awssdk:annotations|2.20.131|直接依赖|maven|
|com.ibm.icu:icu4j|69.1|间接依赖|maven|
|com.azure:azure-storage-file-datalake|12.16.1|直接依赖|maven|
|com.google.guava:guava|32.0.1-jre|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.15.2|直接依赖|maven|
|net.minidev:accessors-smart|2.4.9|间接依赖|maven|
|org.projectnessie.nessie:nessie-client|0.67.0|直接依赖|maven|
|org.apache.avro:avro|1.11.1|直接依赖|maven|
|software.amazon.awssdk:lakeformation|2.20.131|直接依赖|maven|
|com.azure:azure-core-http-netty|1.13.6|直接依赖|maven|
|mkdocstrings|0.23.0|间接依赖|pip|
|io.netty:netty-tcnative-boringssl-static|2.0.61.Final|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-core|1.0.33|间接依赖|maven|
|com.google.cloud:libraries-bom|26.18.0|直接依赖|maven|
|org.antlr:antlr4|4.9.3|直接依赖|maven|
|::iceberg-aws||直接依赖|maven|
|io.grpc:grpc-protobuf|1.55.1|直接依赖|maven|
|com.azure:azure-identity|1.10.0|直接依赖|maven|
|software.amazon.awssdk:profiles|2.20.131|间接依赖|maven|
|org.scala-lang.modules:scala-collection-compat||直接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5|5.2|间接依赖|maven|
|com.google.api.grpc:grpc-google-cloud-storage-v2|2.22.5-alpha|直接依赖|maven|
|software.amazon.awssdk:dynamodb|2.20.131|直接依赖|maven|
|net.java.dev.jna:jna|5.13.0|间接依赖|maven|
|::iceberg-hive-metastore||直接依赖|maven|
|software.amazon.awssdk:regions|2.20.131|直接依赖|maven|
|io.netty:netty-transport|4.1.94.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.14.2|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.5|间接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.55.1|直接依赖|maven|
|com.azure:azure-storage-blob|12.23.1|间接依赖|maven|
|openapi-spec-validator|0.5.2|间接依赖|pip|
|io.netty:netty-codec-dns|4.1.93.Final|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.15.1|间接依赖|maven|
|::iceberg-orc||直接依赖|maven|
|org.roaringbitmap:shims|0.9.47|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|间接依赖|maven|
|com.nimbusds:lang-tag|1.7|间接依赖|maven|
|com.google.cloud:google-cloud-core|2.20.0|直接依赖|maven|
|com.github.luben:zstd-jni|1.5.0-1|间接依赖|maven|
|software.amazon.awssdk:third-party-jackson-core|2.20.131|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.94.Final|间接依赖|maven|
|software.amazon.awssdk:json-utils|2.20.131|直接依赖|maven|
|org.checkerframework:checker-qual|3.33.0|直接依赖|maven|
|mkdocs-gen-files|0.5.0|间接依赖|pip|
|mkdocs-section-index|0.3.5|间接依赖|pip|
|::iceberg-spark:iceberg-spark-extensions-3.4_2.12||直接依赖|maven|
|io.perfmark:perfmark-api|0.26.0|直接依赖|maven|
|io.grpc:grpc-services|1.55.1|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)