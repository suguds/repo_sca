# provectus/kafka-ui安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1702459191096639488.svg)](https://www.murphysec.com/console/report/1697309745760071680/1702459191096639488)

仓库描述：Open-Source Web UI for Apache Kafka Management

仓库地址：[https://github.com/provectus/kafka-ui](https://github.com/provectus/kafka-ui)

| star：6787 | watch：52 | fork：853 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-14 15:37:35 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-15 07:14:49 | 组件总数：330 | 漏洞总数：7 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache HttpClient URI解析错误漏洞|XSS|[MPS-2020-17341](https://www.oscs1024.com/hd/MPS-2020-17341)|CVE-2020-13956|中危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.squareup.okio:okio-jvm|3.0.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.xerial.snappy:snappy-java|1.1.8.4|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.xerial.snappy:snappy-java|1.1.10.0|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|com.squareup.okio:okio|3.0.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.15.2||间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|30.1.1-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|31.1-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.httpcomponents:httpclient|4.5.9|4.5.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|19|Low|
|Apache-2.0|272|Low|
|自定义许可证|14|Low|
|MIT-0|1|Low|
|EPL-2.0|3|Low|
|BSD-3-Clause|3|Low|
|EPL-1.0|3|Low|
|BSD-2-Clause|3|Low|
|LGPL-2.1|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.kjetland:mbknor-jackson-jsonschema_2.13|1.0.39|间接依赖|maven|
|com.typesafe.netty:netty-reactive-streams|2.0.4|间接依赖|maven|
|org.aeonbits.owner:owner-java8|1.0.12|间接依赖|maven|
|com.github.erosb:everit-json-schema|1.14.1|间接依赖|maven|
|org.openapitools:jackson-databind-nullable|0.2.4|直接依赖|maven|
|io.swagger.core.v3:swagger-integration-jakarta|2.2.8|直接依赖|maven|
|com.github.stephenc.jcip:jcip-annotations|1.0-1|间接依赖|maven|
|org.seleniumhq.selenium:selenium-devtools-v109|4.8.3|间接依赖|maven|
|org.springframework.security:spring-security-ldap|6.1.3|直接依赖|maven|
|com.google.re2j:re2j|1.6|间接依赖|maven|
|org.slf4j:slf4j-simple|2.0.7|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-security|3.1.3|直接依赖|maven|
|org.seleniumhq.selenium:selenium-java|4.8.3|间接依赖|maven|
|com.squareup.okhttp3:okhttp|4.10.0|间接依赖|maven|
|org.springframework:spring-tx|6.0.11|间接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.97.Final|直接依赖|maven|
|io.netty:netty-handler-proxy|4.1.97.Final|间接依赖|maven|
|org.springframework.security:spring-security-web|6.1.3|间接依赖|maven|
|io.confluent:common-config|7.4.0|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-extension-autoconfigure|1.24.0-alpha|间接依赖|maven|
|com.codeborne:selenide|6.12.3|直接依赖|maven|
|javax.ws.rs:jsr311-api|1.1.1|间接依赖|maven|
|org.apache.kafka:kafka-storage|3.4.1|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-joda|2.15.2|间接依赖|maven|
|software.amazon.awssdk:aws-json-protocol|2.19.26|间接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|2.5.1|间接依赖|maven|
|dev.failsafe:failsafe|3.3.0|间接依赖|maven|
|org.springframework.boot:spring-boot-devtools|3.1.3|直接依赖|maven|
|io.opentelemetry:opentelemetry-api-events|1.25.0-alpha|间接依赖|maven|
|org.apache.commons:commons-compress|1.21|间接依赖|maven|
|io.netty:netty-resolver|4.1.97.Final|直接依赖|maven|
|software.amazon.awssdk:third-party-jackson-core|2.19.26|间接依赖|maven|
|io.opentelemetry:opentelemetry-context|1.25.0|间接依赖|maven|
|org.springframework.security:spring-security-config|6.1.3|间接依赖|maven|
|io.opentelemetry:opentelemetry-api|1.25.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-scripting-compiler-impl-embeddable|1.6.0|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|4.2.19|间接依赖|maven|
|org.apache.kafka:kafka-clients|3.5.0|直接依赖|maven|
|software.amazon.awssdk:sso|2.19.26|间接依赖|maven|
|com.squareup.okio:okio-jvm|3.0.0|间接依赖|maven|
|io.qase:qase-testng|3.0.5|直接依赖|maven|
|software.amazon.awssdk:auth|2.19.26|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.15.2|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.97.Final|间接依赖|maven|
|software.amazon.awssdk:profiles|2.19.26|间接依赖|maven|
|org.bitbucket.b_c:jose4j|0.7.9|间接依赖|maven|
|org.testng:testng|7.7.1|直接依赖|maven|
|io.swagger:swagger-annotations|1.6.8|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|io.netty:netty-handler|4.1.97.Final|直接依赖|maven|
|io.micrometer:micrometer-registry-prometheus|1.11.3|直接依赖|maven|
|software.amazon.msk:aws-msk-iam-auth|1.1.7|直接依赖|maven|
|org.seleniumhq.selenium:selenium-api|4.8.3|间接依赖|maven|
|com.google.auto:auto-common|1.2|间接依赖|maven|
|io.prometheus:simpleclient_common|0.16.0|间接依赖|maven|
|org.codehaus.groovy:groovy|3.0.13|间接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-logging|1.25.0|间接依赖|maven|
|org.asynchttpclient:async-http-client|2.12.3|间接依赖|maven|
|org.scala-lang.modules:scala-java8-compat_2.13|1.0.2|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.15.2|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.8.22|间接依赖|maven|
|org.apache.kafka:kafka-storage-api|3.4.1|间接依赖|maven|
|org.slf4j:slf4j-api|2.0.7|间接依赖|maven|
|io.confluent:logredactor|1.0.11|间接依赖|maven|
|io.confluent:kafka-json-serializer|7.4.0|间接依赖|maven|
|software.amazon.awssdk:annotations|2.19.26|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.97.Final|直接依赖|maven|
|org.aspectj:aspectjrt|1.9.9.1|直接依赖|maven|
|com.google.protobuf:protobuf-java-util|3.19.6|间接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.97.Final|间接依赖|maven|
|io.netty:netty-buffer|4.1.97.Final|直接依赖|maven|
|software.amazon.awssdk:utils|2.19.26|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.20.0|间接依赖|maven|
|org.seleniumhq.selenium:selenium-json|4.8.3|间接依赖|maven|
|com.codeborne:selenide-core|6.12.3|间接依赖|maven|
|org.aeonbits.owner:owner|1.0.12|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.14.6|间接依赖|maven|
|io.prometheus:simpleclient_tracer_common|0.16.0|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-extension-autoconfigure-spi|1.25.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-reactor-netty|3.1.3|间接依赖|maven|
|org.apache.kafka:kafka-server-common|3.4.1|间接依赖|maven|
|org.springframework.security:spring-security-oauth2-client|6.1.3|间接依赖|maven|
|io.projectreactor.addons:reactor-extra|3.5.1|直接依赖|maven|
|io.projectreactor.netty:reactor-netty-core|1.1.10|间接依赖|maven|
|commons-digester:commons-digester|2.1|间接依赖|maven|
|com.amazonaws:jmespath-java|1.12.395|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|2.1.2|间接依赖|maven|
|org.springframework:spring-beans|6.0.11|间接依赖|maven|
|org.seleniumhq.selenium:selenium-support|4.8.3|间接依赖|maven|
|software.amazon.awssdk:regions|2.19.26|间接依赖|maven|
|io.opentelemetry:opentelemetry-api-logs|1.25.0-alpha|间接依赖|maven|
|software.amazon.ion:ion-java|1.0.2|间接依赖|maven|
|com.google.guava:guava|30.1.1-jre|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.15.2|间接依赖|maven|
|com.github.docker-java:docker-java-transport|3.2.13|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|10.1.12|间接依赖|maven|
|ch.qos.logback:logback-core|1.4.11|间接依赖|maven|
|com.konghq:unirest-java|3.4.00|间接依赖|maven|
|io.qameta.allure:allure-java-commons|2.23.0|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-guava|2.15.2|间接依赖|maven|
|org.seleniumhq.selenium:selenium-devtools-v110|4.8.3|间接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5|5.2.1|直接依赖|maven|
|org.springframework.security:spring-security-core|6.1.3|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.8.22|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.97.Final|直接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.5-1|间接依赖|maven|
|software.amazon.awssdk:sts|2.19.26|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.6.3|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|3.0.2|间接依赖|maven|
|org.seleniumhq.selenium:selenium-chrome-driver|4.8.3|间接依赖|maven|
|com.google.guava:guava|31.1-jre|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.97.Final|间接依赖|maven|
|org.springframework.security:spring-security-crypto|6.1.3|间接依赖|maven|
|org.apache.yetus:audience-annotations|0.5.0|间接依赖|maven|
|com.google.auto.service:auto-service-annotations|1.0.1|间接依赖|maven|
|javax.validation:validation-api|2.0.1.Final|间接依赖|maven|
|com.google.code.gson:gson|2.10.1|间接依赖|maven|
|org.mapstruct:mapstruct|1.5.5.Final|直接依赖|maven|
|commons-validator:commons-validator|1.7|间接依赖|maven|
|com.squareup.wire:wire-schema-jvm|4.4.3|间接依赖|maven|
|org.apache.kafka:kafka-raft|3.4.1|间接依赖|maven|
|io.confluent:kafka-protobuf-types|7.4.0|间接依赖|maven|
|com.amazonaws:aws-java-sdk-sts|1.12.395|间接依赖|maven|
|org.rnorth.duct-tape:duct-tape|1.0.8|间接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.4|间接依赖|maven|
|org.seleniumhq.selenium:selenium-devtools-v111|4.8.3|间接依赖|maven|
|org.seleniumhq.selenium:selenium-edge-driver|4.8.3|间接依赖|maven|
|io.confluent:kafka-protobuf-serializer|7.4.0|直接依赖|maven|
|org.opendatadiscovery:ingestion-contract-client|0.1.26|直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-trace|1.25.0|间接依赖|maven|
|com.squareup:javapoet|1.13.0|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.97.Final|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-http|1.1.10|间接依赖|maven|
|io.qameta.allure:allure-model|2.23.0|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.9|间接依赖|maven|
|org.seleniumhq.selenium:selenium-ie-driver|4.8.3|间接依赖|maven|
|io.swagger:swagger-annotations|1.5.23|间接依赖|maven|
|org.apache.commons:commons-exec|1.3|间接依赖|maven|
|org.hamcrest:hamcrest-core|2.2|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-metrics|1.25.0|间接依赖|maven|
|com.sun.activation:jakarta.activation|1.2.2|间接依赖|maven|
|io.confluent:common-utils|7.4.0|间接依赖|maven|
|io.confluent:kafka-schema-serializer|7.4.0|间接依赖|maven|
|net.java.dev.jna:jna|5.8.0|间接依赖|maven|
|io.netty:netty-common|4.1.97.Final|直接依赖|maven|
|io.confluent:logredactor-metrics|1.0.11|间接依赖|maven|
|io.confluent:kafka-protobuf-provider|7.4.0|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|4.0.0|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.2-1|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|8.0.1.Final|间接依赖|maven|
|org.apache.kafka:kafka_2.13|3.3.1|直接依赖|maven|
|com.google.protobuf:protobuf-java|3.23.3|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.15.2|间接依赖|maven|
|org.springframework:spring-context|6.0.11|间接依赖|maven|
|io.confluent:kafka-avro-serializer|7.4.0|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-csv|2.15.2|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-reflect|1.8.22|间接依赖|maven|
|io.netty:netty-codec-http|4.1.97.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-oauth2-client|3.1.3|直接依赖|maven|
|io.ous:jtoml|2.0.0|间接依赖|maven|
|io.micrometer:micrometer-observation|1.11.3|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.15.2|间接依赖|maven|
|javax.ws.rs:javax.ws.rs-api|2.1.1|间接依赖|maven|
|software.amazon.eventstream:eventstream|1.0.1|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.5.1|间接依赖|maven|
|com.beust:jcommander|1.82|间接依赖|maven|
|io.gsonfire:gson-fire|1.8.5|间接依赖|maven|
|software.amazon.awssdk:apache-client|2.19.26|间接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|io.prometheus:simpleclient|0.16.0|间接依赖|maven|
|org.seleniumhq.selenium:selenium-http|4.8.1|直接依赖|maven|
|io.qameta.allure:allure-selenide|2.23.0|直接依赖|maven|
|org.jetbrains:annotations|17.0.0|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.15.2|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-scala_2.13|2.15.2|间接依赖|maven|
|org.apache.commons:commons-pool2|2.11.1|直接依赖|maven|
|org.apache.avro:avro|1.11.1|直接依赖|maven|
|ch.qos.logback:logback-classic|1.4.11|间接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5-h2|5.2.2|间接依赖|maven|
|software.amazon.awssdk:protocol-core|2.19.26|间接依赖|maven|
|software.amazon.awssdk:metrics-spi|2.19.26|间接依赖|maven|
|io.prometheus:simpleclient_tracer_otel|0.16.0|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-common|1.25.0|间接依赖|maven|
|com.provectus:kafka-ui-serde-api|1.0.0|直接依赖|maven|
|org.springframework.security:spring-security-oauth2-core|6.1.3|间接依赖|maven|
|org.apache.datasketches:datasketches-java|3.1.0|直接依赖|maven|
|com.google.auto.service:auto-service|1.0.1|间接依赖|maven|
|org.apache.zookeeper:zookeeper-jute|3.6.3|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|直接依赖|maven|
|com.squareup.wire:wire-runtime-jvm|4.4.3|间接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.97.Final|间接依赖|maven|
|io.confluent:kafka-schema-registry-client|7.4.0|直接依赖|maven|
|org.webjars:jquery|3.6.1|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|3.1.3|间接依赖|maven|
|org.scala-lang.modules:scala-collection-compat_2.13|2.6.0|间接依赖|maven|
|com.typesafe.scala-logging:scala-logging_2.13|3.9.4|间接依赖|maven|
|org.scala-lang:scala-library|2.13.9|间接依赖|maven|
|org.opendatadiscovery:oddrn-generator-java|0.1.17|直接依赖|maven|
|io.netty:netty-codec-http2|4.1.97.Final|间接依赖|maven|
|org.json:json|20230227|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.15.2|间接依赖|maven|
|org.scala-lang:scala-reflect|2.13.8|间接依赖|maven|
|io.micrometer:micrometer-core|1.11.3|间接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.97.Final|间接依赖|maven|
|org.hamcrest:hamcrest|2.2|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|间接依赖|maven|
|com.squareup.okio:okio|3.0.0|间接依赖|maven|
|org.springframework.ldap:spring-ldap-core|3.1.1|间接依赖|maven|
|io.github.bonigarcia:webdrivermanager|5.3.2|间接依赖|maven|
|software.amazon.awssdk:json-utils|2.19.26|间接依赖|maven|
|org.testcontainers:testcontainers|1.17.6|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.8.22|间接依赖|maven|
|io.swagger.core.v3:swagger-models-jakarta|2.2.8|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-logs|1.25.0-alpha|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|2.1.1|直接依赖|maven|
|io.projectreactor:reactor-core|3.5.9|间接依赖|maven|
|software.amazon.awssdk:aws-query-protocol|2.19.26|间接依赖|maven|
|org.springframework.security:spring-security-oauth2-jose|6.1.3|间接依赖|maven|
|org.seleniumhq.selenium:selenium-firefox-driver|4.8.3|间接依赖|maven|
|com.nimbusds:lang-tag|1.7|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-scripting-common|1.8.22|间接依赖|maven|
|org.apache.datasketches:datasketches-memory|2.0.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-scripting-compiler-embeddable|1.6.0|间接依赖|maven|
|org.checkerframework:checker-qual|3.12.0|间接依赖|maven|
|com.nimbusds:oauth2-oidc-sdk|9.43.3|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.15.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|3.1.3|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.16|间接依赖|maven|
|com.amazonaws:aws-java-sdk-core|1.12.395|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.8.22|间接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|9.31|间接依赖|maven|
|io.qameta.allure:allure-test-filter|2.23.0|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.97.Final|间接依赖|maven|
|io.github.classgraph:classgraph|4.8.150|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-webflux|3.1.3|直接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|org.apache.kafka:kafka-metadata|3.4.1|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.15.2|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator|3.1.3|直接依赖|maven|
|org.springframework.boot:spring-boot|3.1.3|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator-autoconfigure|3.1.3|间接依赖|maven|
|org.apache.httpcomponents:httpmime|4.5.9|间接依赖|maven|
|org.springframework:spring-web|6.0.11|间接依赖|maven|
|com.damnhandy:handy-uri-templates|2.1.8|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|org.apache.kafka:kafka-clients|3.4.1|间接依赖|maven|
|org.seleniumhq.selenium:selenium-safari-driver|4.8.3|间接依赖|maven|
|commons-logging:commons-logging|1.1.3|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|org.springframework:spring-webflux|6.0.11|间接依赖|maven|
|org.opentest4j:opentest4j|1.2.0|间接依赖|maven|
|org.slf4j:jul-to-slf4j|2.0.7|间接依赖|maven|
|io.swagger.core.v3:swagger-annotations|2.1.10|间接依赖|maven|
|org.checkerframework:checker-qual|3.8.0|间接依赖|maven|
|io.micrometer:micrometer-commons|1.11.3|间接依赖|maven|
|net.sourceforge.argparse4j:argparse4j|0.7.0|间接依赖|maven|
|com.github.docker-java:docker-java-transport-zerodep|3.2.13|间接依赖|maven|
|software.amazon.awssdk:netty-nio-client|2.19.26|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-validation|3.1.3|直接依赖|maven|
|org.springframework:spring-expression|6.0.11|间接依赖|maven|
|com.squareup:kotlinpoet|1.12.0|间接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|io.swagger.core.v3:swagger-annotations-jakarta|2.2.8|间接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.5|间接依赖|maven|
|org.projectlombok:lombok|1.18.24|直接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.10.0|间接依赖|maven|
|org.springframework:spring-aop|6.0.11|间接依赖|maven|
|com.github.docker-java:docker-java-api|3.2.13|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.5.3.Final|间接依赖|maven|
|io.netty:netty-transport|4.1.97.Final|直接依赖|maven|
|org.apache.httpcomponents.client5:httpclient5|5.2.1|直接依赖|maven|
|commons-cli:commons-cli|1.4|间接依赖|maven|
|software.amazon.awssdk:sdk-core|2.19.26|间接依赖|maven|
|io.confluent:kafka-json-schema-provider|7.4.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.20.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-script-runtime|1.8.22|间接依赖|maven|
|org.springframework:spring-core|6.0.11|间接依赖|maven|
|org.seleniumhq.selenium:selenium-manager|4.8.3|间接依赖|maven|
|org.seleniumhq.selenium:selenium-chromium-driver|4.8.3|间接依赖|maven|
|io.swagger.core.v3:swagger-core-jakarta|2.2.8|间接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.16|间接依赖|maven|
|org.lz4:lz4-java|1.8.0|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.15.2|间接依赖|maven|
|software.amazon.awssdk:aws-core|2.19.26|间接依赖|maven|
|commons-io:commons-io|2.11.0|间接依赖|maven|
|org.springframework:spring-jcl|6.0.11|间接依赖|maven|
|net.sf.jopt-simple:jopt-simple|5.0.4|间接依赖|maven|
|com.eclipsesource.minimal-json:minimal-json|0.9.5|间接依赖|maven|
|com.nimbusds:content-type|2.2|间接依赖|maven|
|io.prometheus:simpleclient_tracer_otel_agent|0.16.0|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|直接依赖|maven|
|org.apache.commons:commons-compress|1.22|间接依赖|maven|
|com.squareup.okhttp3:logging-interceptor|4.10.0|间接依赖|maven|
|org.seleniumhq.selenium:selenium-http-jdk-client|4.8.1|直接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|software.amazon.awssdk:http-client-spi|2.19.26|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|3.1.3|间接依赖|maven|
|org.asynchttpclient:async-http-client-netty-utils|2.12.3|间接依赖|maven|
|software.amazon.awssdk:endpoints-spi|2.19.26|间接依赖|maven|
|org.brotli:dec|0.1.2|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-scripting-jvm|1.8.22|间接依赖|maven|
|com.yammer.metrics:metrics-core|2.2.0|间接依赖|maven|
|org.seleniumhq.selenium:selenium-devtools-v85|4.8.3|间接依赖|maven|
|com.provectus:kafka-ui-contract|0.0.1-SNAPSHOT|直接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|org.codehaus.groovy:groovy-jsr223|3.0.13|直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk|1.25.0|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.15.2|间接依赖|maven|
|org.antlr:antlr4-runtime|4.12.0|直接依赖|maven|
|io.qameta.allure:allure-testng|2.23.0|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-actuator|3.1.3|直接依赖|maven|
|io.opentelemetry:opentelemetry-semconv|1.24.0-alpha|间接依赖|maven|
|io.netty:netty-codec|4.1.97.Final|直接依赖|maven|
|com.google.inject:guice|5.1.0|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.11.0|间接依赖|maven|
|org.codehaus.groovy:groovy-json|3.0.13|直接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|3.1.3|间接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.8|间接依赖|maven|
|org.yaml:snakeyaml|2.0|间接依赖|maven|
|io.confluent:kafka-json-schema-serializer|7.4.0|直接依赖|maven|
|org.assertj:assertj-core|3.24.2|直接依赖|maven|
|org.testcontainers:selenium|1.17.6|直接依赖|maven|
|io.qase:qase-api|3.0.5|直接依赖|maven|
|junit:junit|4.13.2|间接依赖|maven|
|org.seleniumhq.selenium:selenium-remote-driver|4.8.3|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)