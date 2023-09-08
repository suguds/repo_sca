# signalapp/Signal-Server安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700208185700909056.svg)](https://www.murphysec.com/console/report/1699845667514089472/1700208185700909056)

仓库描述：Server supporting the Signal Private Messenger applications on Android, Desktop, and iOS

仓库地址：[https://github.com/signalapp/Signal-Server](https://github.com/signalapp/Signal-Server)

| star：8425 | watch：398 | fork：2028 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-08 06:35:33 | 许可证：AGPL-3.0 |
| 最近检测时间：2023-09-09 02:05:06 | 组件总数：297 | 漏洞总数：12 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|Eclipse Jetty URI注入漏洞|注入|[MPS-2022-18060](https://www.oscs1024.com/hd/MPS-2022-18060)|CVE-2022-2047|低危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|Netty <4.1.86.Final 存在 CRLF 注入漏洞||[MPS-2022-58552](https://www.oscs1024.com/hd/MPS-2022-58552)|CVE-2022-41915|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Eclipse Jetty 资源管理错误漏洞|拒绝服务|[MPS-2023-4997](https://www.oscs1024.com/hd/MPS-2023-4997)|CVE-2023-26048|中危|
|Eclipse Jetty 信息泄露漏洞|XSS|[MPS-2023-4998](https://www.oscs1024.com/hd/MPS-2023-4998)|CVE-2023-26049|中危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.yaml:snakeyaml|1.31|2.0|间接依赖|建议修复|C:0|H:1|M:1|L:1|
|com.squareup.okio:okio-jvm|3.2.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.84.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.eclipse.jetty:jetty-server|9.4.51.v20230217|12.0.0.beta0|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.5|2.14.0-rc1|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|io.netty:netty-codec-http|4.1.84.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.eclipse.jetty:jetty-http|9.4.51.v20230217|11.0.10|间接依赖|可选修复|C:0|H:0|M:0|L:1|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|232|Low|
|BSD-3-Clause|11|Low|
|MIT|25|Low|
|EPL-1.0|17|Low|
|自定义许可证|27|Low|
|BSD-2-Clause|7|Low|
|EPL-2.0|18|Low|
|CDDL-1.1|2|Low|
|LGPL-2.1|2|Medium|
|MPL-1.1|2|Low|
|MIT-0|1|Low|
|AGPL-3.0|1|High|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|software.amazon.eventstream:eventstream|1.0.1|间接依赖|maven|
|com.google.cloud:google-cloud-core|2.22.0|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.85.Final|间接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|2.17.0|间接依赖|maven|
|joda-time:joda-time|2.12.5|间接依赖|maven|
|org.threeten:threetenbp|1.6.8|间接依赖|maven|
|com.google.http-client:google-http-client|1.42.2|间接依赖|maven|
|com.benasher44:uuid-jvm|0.3.1|间接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.4.51.v20230217|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.9.3|间接依赖|maven|
|io.grpc:grpc-xds|1.56.1|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-client|9.4.51.v20230217|间接依赖|maven|
|software.amazon.awssdk:appconfig|2.20.130|直接依赖|maven|
|com.google.apis:google-api-services-storage|v1-rev20220705-2.0.0|间接依赖|maven|
|com.googlecode.libphonenumber:libphonenumber|8.13.19|直接依赖|maven|
|software.amazon.awssdk:arns|2.20.130|间接依赖|maven|
|io.github.resilience4j:resilience4j-core|1.7.0|间接依赖|maven|
|org.eclipse.jetty:jetty-servlets|9.4.51.v20230217|直接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.56.1|间接依赖|maven|
|io.perfmark:perfmark-api|0.26.0|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.16|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.5|间接依赖|maven|
|com.amazonaws:dynamodb-lock-client|1.2.0|直接依赖|maven|
|io.dropwizard:dropwizard-core|2.1.7|直接依赖|maven|
|io.dropwizard.metrics:metrics-healthchecks|4.2.19|直接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|org.glassfish.jersey.ext:jersey-bean-validation|2.39.1|间接依赖|maven|
|software.amazon.awssdk:apache-client|2.20.130|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.6.20|间接依赖|maven|
|com.google.cloud:google-cloud-logging|3.15.8|直接依赖|maven|
|com.google.protobuf:protobuf-java-util|3.23.2|间接依赖|maven|
|com.sun.istack:istack-commons-runtime|3.0.7|间接依赖|maven|
|io.swagger.core.v3:swagger-integration|2.2.8|间接依赖|maven|
|io.lettuce:lettuce-core|6.2.6.RELEASE|直接依赖|maven|
|org.jvnet.staxex:stax-ex|1.8|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|io.netty:netty-handler|4.1.84.Final|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.5|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.96.Final|间接依赖|maven|
|software.amazon.awssdk:http-client-spi|2.20.130|间接依赖|maven|
|org.glassfish.hk2.external:jakarta.inject|2.6.1|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.12|直接依赖|maven|
|io.dropwizard:dropwizard-jetty|2.1.7|直接依赖|maven|
|io.vavr:vavr|0.10.4|直接依赖|maven|
|io.dropwizard:dropwizard-health|2.1.7|间接依赖|maven|
|io.projectreactor:reactor-core|3.5.9|直接依赖|maven|
|org.apache.commons:commons-collections4|4.4|间接依赖|maven|
|com.google.http-client:google-http-client-appengine|1.42.2|间接依赖|maven|
|com.braintreepayments.gateway:braintree-java|3.25.0|直接依赖|maven|
|org.glassfish.jersey.core:jersey-client|2.39.1|直接依赖|maven|
|com.stripe:stripe-java|23.1.1|直接依赖|maven|
|io.grpc:grpc-auth|1.56.1|间接依赖|maven|
|io.netty:netty-codec-http|4.1.84.Final|间接依赖|maven|
|com.google.firebase:firebase-admin|9.1.1|直接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.51.v20230217|间接依赖|maven|
|io.swagger.core.v3:swagger-jaxrs2|2.2.8|直接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet-core|2.39.1|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.9.0|直接依赖|maven|
|org.eclipse.jetty:jetty-util-ajax|9.4.51.v20230217|间接依赖|maven|
|software.amazon.awssdk:utils|2.20.130|间接依赖|maven|
|org.glassfish:jakarta.el|3.0.4|间接依赖|maven|
|com.apollographql.apollo3:apollo-api-jvm|3.8.2|直接依赖|maven|
|com.google.re2j:re2j|1.7|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet|2.39.1|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.13.5|直接依赖|maven|
|io.dropwizard:dropwizard-servlets|2.1.7|直接依赖|maven|
|io.projectreactor:reactor-core-micrometer|1.0.9|直接依赖|maven|
|org.javassist:javassist|3.29.2-GA|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-guava|2.13.5|间接依赖|maven|
|org.slf4j:log4j-over-slf4j|1.7.36|间接依赖|maven|
|org.glassfish.jaxb:txw2|2.3.1|间接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-joda|2.13.5|间接依赖|maven|
|io.dropwizard.metrics:metrics-json|4.2.19|间接依赖|maven|
|io.netty:netty-resolver|4.1.84.Final|间接依赖|maven|
|software.amazon.awssdk:s3|2.20.130|直接依赖|maven|
|ch.qos.logback:logback-core|1.2.12|直接依赖|maven|
|com.google.http-client:google-http-client-gson|1.43.3|间接依赖|maven|
|io.opencensus:opencensus-contrib-http-util|0.31.1|间接依赖|maven|
|com.google.api.grpc:proto-google-cloud-recaptchaenterprise-v1beta1|0.62.0|间接依赖|maven|
|org.apache.commons:commons-csv|1.9.0|直接依赖|maven|
|io.grpc:grpc-netty-shaded|1.56.1|直接依赖|maven|
|com.google.guava:guava|32.1.2-jre|间接依赖|maven|
|com.mattbertolini:liquibase-slf4j|5.0.0|间接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|2.3.1|直接依赖|maven|
|org.jetbrains.kotlinx:kotlinx-serialization-json-jvm|1.5.1|间接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|io.vavr:vavr-match|0.10.4|间接依赖|maven|
|io.micrometer:micrometer-observation|1.10.10|间接依赖|maven|
|com.google.auth:google-auth-library-oauth2-http|1.19.0|直接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|com.google.api:gax-grpc|2.32.0|间接依赖|maven|
|io.dropwizard.metrics:metrics-annotation|4.2.19|直接依赖|maven|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|org.conscrypt:conscrypt-openjdk-uber|2.5.2|间接依赖|maven|
|ch.qos.logback:logback-access|1.2.12|直接依赖|maven|
|com.google.api.grpc:gapic-google-cloud-storage-v2|2.14.0-alpha|间接依赖|maven|
|io.swagger.core.v3:swagger-annotations|2.2.8|间接依赖|maven|
|io.dropwizard:dropwizard-util|2.1.7|直接依赖|maven|
|io.dropwizard:dropwizard-client|2.1.7|直接依赖|maven|
|com.google.cloud:google-cloud-core-grpc|2.22.0|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.51.v20230217|间接依赖|maven|
|org.glassfish.hk2:hk2-api|2.6.1|间接依赖|maven|
|io.grpc:grpc-grpclb|1.56.1|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.9.0|间接依赖|maven|
|io.dropwizard.metrics:metrics-jetty9|4.2.19|间接依赖|maven|
|com.fasterxml.jackson.jr:jackson-jr-objects|2.11.0|间接依赖|maven|
|io.grpc:grpc-core|1.56.1|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.85.Final|间接依赖|maven|
|io.netty:netty-common|4.1.96.Final|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.85.Final|间接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|2.23.0|间接依赖|maven|
|com.salesforce.servicelibs:reactive-grpc-common|1.2.4|间接依赖|maven|
|org.glassfish.jersey.ext:jersey-metainf-services|2.39.1|间接依赖|maven|
|com.google.api-client:google-api-client-gson|2.0.0|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|2.8|间接依赖|maven|
|org.glassfish.jersey.core:jersey-common|2.39.1|直接依赖|maven|
|io.github.resilience4j:resilience4j-retry|1.7.0|直接依赖|maven|
|io.dropwizard:dropwizard-request-logging|2.1.7|间接依赖|maven|
|io.dropwizard:dropwizard-auth|2.1.7|直接依赖|maven|
|io.dropwizard.metrics:metrics-jersey2|4.2.19|间接依赖|maven|
|jakarta.servlet:jakarta.servlet-api|4.0.4|直接依赖|maven|
|com.google.auth:google-auth-library-credentials|1.19.0|间接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|org.glassfish.hk2:hk2-locator|2.6.1|间接依赖|maven|
|com.google.auto.value:auto-value-annotations|1.10.2|间接依赖|maven|
|com.vdurmont:semver4j|3.1.0|直接依赖|maven|
|org.eclipse.jetty.toolchain.setuid:jetty-setuid-java|1.0.4|间接依赖|maven|
|org.checkerframework:checker-qual|3.33.0|间接依赖|maven|
|org.apache.tomcat:tomcat-jdbc|9.0.76|间接依赖|maven|
|org.javassist:javassist|3.25.0-GA|间接依赖|maven|
|org.yaml:snakeyaml|1.31|间接依赖|maven|
|org.jetbrains:annotations|23.0.0|间接依赖|maven|
|com.google.api:api-common|2.2.1|间接依赖|maven|
|io.netty:netty-buffer|4.1.94.Final|间接依赖|maven|
|io.dropwizard:dropwizard-jersey|2.1.7|直接依赖|maven|
|org.glassfish.hk2:hk2-utils|2.6.1|间接依赖|maven|
|io.dropwizard:dropwizard-lifecycle|2.1.7|直接依赖|maven|
|software.amazon.awssdk:sts|2.20.130|直接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|io.dropwizard:dropwizard-configuration|2.1.7|间接依赖|maven|
|com.google.guava:guava|32.0.1-jre|直接依赖|maven|
|software.amazon.awssdk:netty-nio-client|2.20.130|间接依赖|maven|
|io.netty:netty-codec|4.1.84.Final|间接依赖|maven|
|io.github.classgraph:classgraph|4.8.150|间接依赖|maven|
|io.dropwizard.metrics:metrics-httpclient|4.2.19|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-servlet|9.4.51.v20230217|直接依赖|maven|
|com.google.api.grpc:proto-google-cloud-logging-v2|0.104.8|间接依赖|maven|
|net.sourceforge.argparse4j:argparse4j|0.9.0|直接依赖|maven|
|io.dropwizard.logback:logback-throttling-appender|1.1.10|间接依赖|maven|
|io.grpc:grpc-context|1.56.1|间接依赖|maven|
|com.google.api.grpc:proto-google-iam-v1|1.18.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.5|直接依赖|maven|
|io.github.resilience4j:resilience4j-reactor|1.7.0|直接依赖|maven|
|org.whispersystems.textsecure:service|JGITVER|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.18.0|间接依赖|maven|
|org.apache.commons:commons-text|1.10.0|间接依赖|maven|
|org.apache.httpcomponents:fluent-hc|4.3.6|间接依赖|maven|
|org.eclipse.jetty:jetty-security|9.4.51.v20230217|间接依赖|maven|
|com.apollographql.apollo3:apollo-annotations-jvm|3.8.2|间接依赖|maven|
|org.eclipse.jetty:jetty-server|9.4.51.v20230217|间接依赖|maven|
|io.grpc:grpc-protobuf|1.56.1|直接依赖|maven|
|org.eclipse.jetty:jetty-client|9.4.51.v20230217|间接依赖|maven|
|io.swagger.core.v3:swagger-core|2.2.8|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|com.salesforce.servicelibs:reactor-grpc-stub|1.2.4|直接依赖|maven|
|io.dropwizard:dropwizard-metrics|2.1.7|直接依赖|maven|
|io.netty:netty-transport|4.1.84.Final|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.23|间接依赖|maven|
|org.signal:libsignal-server|0.30.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.5|直接依赖|maven|
|org.liquibase:liquibase-core|4.22.0|间接依赖|maven|
|io.micrometer:micrometer-commons|1.10.10|间接依赖|maven|
|com.google.api:gax-httpjson|2.32.0|间接依赖|maven|
|org.glassfish.jersey.core:jersey-server|2.39.1|直接依赖|maven|
|io.dropwizard.metrics:metrics-core|4.2.19|直接依赖|maven|
|software.amazon.awssdk:third-party-jackson-core|2.20.130|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.13.5|间接依赖|maven|
|com.opencsv:opencsv|5.7.1|间接依赖|maven|
|com.google.code.gson:gson|2.10.1|间接依赖|maven|
|software.amazon.awssdk:profiles|2.20.130|间接依赖|maven|
|io.grpc:grpc-api|1.56.1|间接依赖|maven|
|io.opencensus:opencensus-proto|0.2.0|间接依赖|maven|
|org.whispersystems.textsecure:websocket-resources|JGITVER|直接依赖|maven|
|io.dropwizard:dropwizard-logging|2.1.7|直接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.2|间接依赖|maven|
|com.google.cloud:google-cloud-core-http|2.8.22|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.85.Final|间接依赖|maven|
|jakarta.inject:jakarta.inject-api|1.0.5|直接依赖|maven|
|com.google.auto.value:auto-value-annotations|1.10.1|间接依赖|maven|
|io.dropwizard.metrics:metrics-caffeine|4.2.19|间接依赖|maven|
|io.dropwizard:dropwizard-jackson|2.1.7|间接依赖|maven|
|software.amazon.awssdk:json-utils|2.20.130|间接依赖|maven|
|com.eatthepath:pushy-dropwizard-metrics-listener|0.15.2|直接依赖|maven|
|com.google.api:gax|2.32.0|间接依赖|maven|
|io.github.resilience4j:resilience4j-circuitbreaker|1.7.0|直接依赖|maven|
|com.google.cloud:google-cloud-storage|2.14.0|间接依赖|maven|
|org.eclipse.jetty:jetty-continuation|9.4.51.v20230217|间接依赖|maven|
|org.jetbrains.kotlinx:kotlinx-serialization-json|1.5.1|直接依赖|maven|
|software.amazon.awssdk:appconfigdata|2.20.130|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-blackbird|2.13.5|间接依赖|maven|
|com.sun.xml.fastinfoset:FastInfoset|1.2.15|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.6.20|间接依赖|maven|
|software.amazon.awssdk:metrics-spi|2.20.130|间接依赖|maven|
|com.google.oauth-client:google-oauth-client|1.34.1|间接依赖|maven|
|com.google.api.grpc:proto-google-cloud-recaptchaenterprise-v1|3.20.0|间接依赖|maven|
|com.google.http-client:google-http-client-apache-v2|1.42.1|间接依赖|maven|
|org.coursera:dropwizard-metrics-datadog|1.1.13|直接依赖|maven|
|com.google.http-client:google-http-client|1.43.3|间接依赖|maven|
|io.dropwizard.metrics:metrics-servlets|4.2.19|间接依赖|maven|
|software.amazon.awssdk:crt-core|2.20.130|间接依赖|maven|
|software.amazon.awssdk:sdk-core|2.20.130|间接依赖|maven|
|com.eatthepath:pushy|0.15.2|直接依赖|maven|
|io.grpc:grpc-googleapis|1.56.1|间接依赖|maven|
|io.dropwizard:dropwizard-migrations|2.1.7|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.13.5|间接依赖|maven|
|net.logstash.logback:logstash-logback-encoder|7.3|直接依赖|maven|
|org.eclipse.jetty.websocket:websocket-server|9.4.51.v20230217|直接依赖|maven|
|party.iroiro.luajava:lua51-platform|3.4.0|直接依赖|maven|
|io.opencensus:opencensus-contrib-grpc-util|0.31.1|间接依赖|maven|
|com.google.cloud:proto-google-cloud-firestore-bundle-v1|3.7.0|间接依赖|maven|
|com.google.cloud:google-cloud-firestore|3.7.0|间接依赖|maven|
|com.eatthepath:fast-uuid|0.2.0|间接依赖|maven|
|com.squareup.okio:okio-jvm|3.2.0|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.84.Final|间接依赖|maven|
|com.google.http-client:google-http-client-jackson2|1.42.2|间接依赖|maven|
|com.google.api:api-common|2.15.0|间接依赖|maven|
|io.netty:netty-buffer|4.1.84.Final|间接依赖|maven|
|org.glassfish.hk2:osgi-resource-locator|1.0.3|间接依赖|maven|
|software.amazon.awssdk:regions|2.20.130|间接依赖|maven|
|org.coursera:metrics-datadog|1.1.13|间接依赖|maven|
|io.netty:netty-codec|4.1.94.Final|间接依赖|maven|
|io.dropwizard.metrics:metrics-jvm|4.2.19|间接依赖|maven|
|org.whispersystems.textsecure:event-logger|JGITVER|直接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.96.Final|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|直接依赖|maven|
|org.eclipse.jetty.websocket:websocket-api|9.4.51.v20230217|直接依赖|maven|
|org.glassfish.hk2.external:aopalliance-repackaged|2.6.1|间接依赖|maven|
|software.amazon.awssdk:endpoints-spi|2.20.130|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|software.amazon.awssdk:aws-xml-protocol|2.20.130|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|software.amazon.awssdk:aws-json-protocol|2.20.130|间接依赖|maven|
|com.google.api.grpc:grpc-google-iam-v1|1.6.4|间接依赖|maven|
|org.osgi:org.osgi.core|4.2.0|间接依赖|maven|
|com.google.api-client:google-api-client|2.0.0|间接依赖|maven|
|com.google.cloud:google-cloud-recaptchaenterprise|3.20.0|直接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|直接依赖|maven|
|jakarta.ws.rs:jakarta.ws.rs-api|2.1.6|直接依赖|maven|
|io.projectreactor:reactor-test|3.5.9|直接依赖|maven|
|com.google.api.grpc:proto-google-cloud-firestore-v1|3.7.0|间接依赖|maven|
|io.grpc:grpc-alts|1.56.1|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|software.amazon.awssdk:protocol-core|2.20.130|间接依赖|maven|
|org.apache.tomcat:tomcat-juli|9.0.76|间接依赖|maven|
|io.netty:netty-resolver|4.1.94.Final|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.85.Final|间接依赖|maven|
|software.amazon.awssdk:aws-core|2.20.130|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.3|间接依赖|maven|
|com.google.api.grpc:proto-google-cloud-storage-v2|2.14.0-alpha|间接依赖|maven|
|io.dropwizard:dropwizard-db|2.1.7|直接依赖|maven|
|io.opencensus:opencensus-api|0.31.1|间接依赖|maven|
|org.jetbrains.kotlinx:kotlinx-serialization-core-jvm|1.5.1|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|直接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.1.Final|间接依赖|maven|
|io.grpc:grpc-stub|1.56.1|直接依赖|maven|
|org.eclipse.jetty:jetty-http|9.4.51.v20230217|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.5|直接依赖|maven|
|com.google.api.grpc:grpc-google-cloud-storage-v2|2.14.0-alpha|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.2.5.Final|间接依赖|maven|
|com.datadoghq:java-dogstatsd-client|2.3|间接依赖|maven|
|software.amazon.awssdk:auth|2.20.130|间接依赖|maven|
|io.dropwizard:dropwizard-validation|2.1.7|直接依赖|maven|
|io.dropwizard.metrics:metrics-jmx|4.2.19|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.1|间接依赖|maven|
|com.helger:profiler|1.1.1|间接依赖|maven|
|com.google.http-client:google-http-client-gson|1.42.3|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.23.2|直接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.13.5|直接依赖|maven|
|software.amazon.awssdk:dynamodb|2.20.130|直接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.94.Final|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|间接依赖|maven|
|io.swagger.core.v3:swagger-models|2.2.8|间接依赖|maven|
|io.dropwizard.metrics:metrics-logback|4.2.19|间接依赖|maven|
|org.glassfish.jersey.inject:jersey-hk2|2.39.1|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.14|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.36|间接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|software.amazon.awssdk:annotations|2.20.130|间接依赖|maven|
|io.micrometer:micrometer-registry-statsd|1.10.10|直接依赖|maven|
|io.grpc:grpc-services|1.56.1|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.5|直接依赖|maven|
|io.micrometer:micrometer-core|1.10.10|直接依赖|maven|
|software.amazon.awssdk:aws-query-protocol|2.20.130|间接依赖|maven|
|javax.servlet:javax.servlet-api|3.1.0|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)