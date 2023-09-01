# langchain4j/langchain4j安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1697671728117448704.svg)](https://www.murphysec.com/console/report/1696947218140717056/1697671728117448704)

仓库描述：Java version of LangChain

仓库地址：[https://github.com/langchain4j/langchain4j](https://github.com/langchain4j/langchain4j)

| star：361 | watch：14 | fork：55 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-01 19:29:33 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-02 02:04:56 | 组件总数：180 | 漏洞总数：20 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Fastjson < 1.2.83 任意代码执行漏洞|反序列化|[MPS-2022-11320](https://www.oscs1024.com/hd/MPS-2022-11320)|CVE-2022-25845|高危|
|plexus-utils <3.0.24 路径遍历漏洞|路径遍历|[MPS-2022-11760](https://www.oscs1024.com/hd/MPS-2022-11760)||中危|
|plexus-utils <3.0.24 XXE 漏洞|XPath盲注|[MPS-2022-11786](https://www.oscs1024.com/hd/MPS-2022-11786)||低危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|Netty <4.1.86.Final 存在 CRLF 注入漏洞||[MPS-2022-58552](https://www.oscs1024.com/hd/MPS-2022-58552)|CVE-2022-41915|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|Apache Commons Text <1.10.0 远程代码执行漏洞|反序列化|[MPS-2022-59712](https://www.oscs1024.com/hd/MPS-2022-59712)|CVE-2022-42889|严重|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.fasterxml.jackson.core:jackson-databind|2.12.7.1|2.14.0-rc1|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|com.squareup.okio:okio-jvm|3.0.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.squareup.okio:okio|3.2.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.79.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.squareup.okio:okio|2.8.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.commons:commons-text|1.6|1.10.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.yaml:snakeyaml|1.30|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|com.squareup.okio:okio-jvm|3.2.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.alibaba:fastjson|1.2.76|1.2.83|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.codehaus.plexus:plexus-utils|3.0.20|3.0.24|间接依赖|可选修复|C:0|H:0|M:1|L:1|
|com.google.guava:guava|31.0.1-android|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-codec:commons-codec|1.11|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|com.google.guava:guava|31.1-android|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-http|4.1.79.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|148|Low|
|EPL-1.0|2|Low|
|自定义许可证|10|Low|
|MIT|12|Low|
|BSD-3-Clause|9|Low|
|EPL-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.apache.commons:commons-lang3|3.12.0|间接依赖|maven|
|io.grpc:grpc-alts|1.56.1|间接依赖|maven|
|io.netty:netty-transport|4.1.94.Final|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.79.Final|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.6.10|间接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j-impl|2.17.1|间接依赖|maven|
|com.alibaba:dashscope-sdk-java|2.2.0|直接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.18.0|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|dev.langchain4j:langchain4j-core|0.22.0|直接依赖|maven|
|org.apache.poi:poi-ooxml-lite|5.2.3|间接依赖|maven|
|com.squareup.okhttp3:okhttp-sse|4.11.0|间接依赖|maven|
|io.opencensus:opencensus-api|0.31.1|间接依赖|maven|
|com.squareup.okhttp3:okhttp-sse|4.10.0|间接依赖|maven|
|io.grpc:grpc-core|1.46.0|间接依赖|maven|
|org.apache.poi:poi-ooxml|5.2.3|直接依赖|maven|
|ch.qos.logback:logback-classic|1.2.12|间接依赖|maven|
|org.springframework:spring-context|5.3.29|间接依赖|maven|
|com.squareup.okhttp3:okhttp|4.11.0|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|com.github.stephenc.jcip:jcip-annotations|1.0-1|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.6.0|间接依赖|maven|
|io.grpc:grpc-core|1.53.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.12.7|间接依赖|maven|
|com.knuddels:jtokkit|0.6.1|直接依赖|maven|
|org.projectlombok:lombok|1.18.28|间接依赖|maven|
|io.netty:netty-common|4.1.94.Final|间接依赖|maven|
|org.checkerframework:checker-qual|3.33.0|间接依赖|maven|
|io.grpc:grpc-stub|1.56.1|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.46.0|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.16|间接依赖|maven|
|io.pinecone:pinecone-client|0.2.3|直接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|2.23.0|间接依赖|maven|
|org.threeten:threetenbp|1.6.8|间接依赖|maven|
|org.apache.xmlbeans:xmlbeans|5.1.1|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.21.7|间接依赖|maven|
|org.apache.poi:poi|5.2.3|直接依赖|maven|
|io.grpc:grpc-protobuf|1.46.0|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|io.grpc:grpc-api|1.56.1|间接依赖|maven|
|org.apache.poi:poi-scratchpad|5.2.3|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.18.0|间接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|2.0.1|间接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.17.1|间接依赖|maven|
|com.google.code.gson:gson|2.10.1|直接依赖|maven|
|org.apache.commons:commons-collections4|4.4|间接依赖|maven|
|com.squareup.retrofit2:retrofit|2.9.0|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.14.0|间接依赖|maven|
|com.squareup.okhttp3:okhttp|4.10.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.5.31|间接依赖|maven|
|commons-io:commons-io|2.11.0|间接依赖|maven|
|io.grpc:grpc-stub|1.46.0|间接依赖|maven|
|io.grpc:grpc-context|1.56.1|间接依赖|maven|
|org.springframework:spring-expression|5.3.29|间接依赖|maven|
|io.grpc:grpc-api|1.53.0|间接依赖|maven|
|org.springframework:spring-jcl|5.3.29|间接依赖|maven|
|org.apache.commons:commons-math3|3.6.1|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.6.20|间接依赖|maven|
|org.apache.pdfbox:pdfbox|2.0.29|直接依赖|maven|
|io.grpc:grpc-stub|1.53.0|间接依赖|maven|
|org.ow2.asm:asm|9.3|间接依赖|maven|
|io.netty:netty-codec|4.1.94.Final|直接依赖|maven|
|commons-codec:commons-codec|1.11|间接依赖|maven|
|org.checkerframework:checker-qual|3.12.0|间接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.56.1|间接依赖|maven|
|io.grpc:grpc-core|1.56.1|间接依赖|maven|
|com.google.guava:guava|32.1.2-jre|间接依赖|maven|
|org.apache.commons:commons-text|1.6|间接依赖|maven|
|com.squareup.retrofit2:converter-gson|2.9.0|间接依赖|maven|
|io.grpc:grpc-context|1.46.0|间接依赖|maven|
|org.codehaus.plexus:plexus-utils|3.0.20|间接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|com.google.protobuf:protobuf-java-util|3.23.2|间接依赖|maven|
|io.grpc:grpc-grpclb|1.56.1|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|2.8|间接依赖|maven|
|net.minidev:accessors-smart|2.4.9|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.7.14|间接依赖|maven|
|org.slf4j:slf4j-api|2.0.7|直接依赖|maven|
|dev.langchain4j:langchain4j|0.22.0|直接依赖|maven|
|com.google.api.grpc:proto-google-cloud-aiplatform-v1beta1|0.40.0|间接依赖|maven|
|io.netty:netty-buffer|4.1.94.Final|间接依赖|maven|
|io.grpc:grpc-netty-shaded|1.46.0|间接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|io.opencensus:opencensus-proto|0.2.0|间接依赖|maven|
|org.apache.opennlp:opennlp-tools|1.9.4|直接依赖|maven|
|io.netty:netty-codec-socks|4.1.79.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.12.7|间接依赖|maven|
|io.grpc:grpc-netty|1.53.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.6.10|间接依赖|maven|
|org.slf4j:slf4j-simple|2.0.7|间接依赖|maven|
|com.squareup.okio:okio|3.2.0|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.23|间接依赖|maven|
|dev.ai4j:openai4j|0.9.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.12.7.1|间接依赖|maven|
|com.google.api:gax-grpc|2.32.0|间接依赖|maven|
|org.apache.commons:commons-compress|1.21|间接依赖|maven|
|org.springframework:spring-aop|5.3.29|间接依赖|maven|
|com.google.api.grpc:proto-google-cloud-aiplatform-v1|3.24.0|间接依赖|maven|
|org.jsoup:jsoup|1.16.1|直接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|com.google.guava:guava|31.1-android|间接依赖|maven|
|org.apache.commons:commons-collections4|4.3|间接依赖|maven|
|com.google.auth:google-auth-library-oauth2-http|1.19.0|间接依赖|maven|
|com.google.guava:guava|32.1.1-jre|间接依赖|maven|
|com.google.re2j:re2j|1.7|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|com.zaxxer:SparseBitSet|1.2|间接依赖|maven|
|com.google.api.grpc:grpc-google-common-protos|2.23.0|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.2|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.19|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.12|间接依赖|maven|
|net.minidev:json-smart|2.4.10|间接依赖|maven|
|com.google.cloud:google-cloud-aiplatform|3.24.0|直接依赖|maven|
|io.grpc:grpc-protobuf|1.56.1|间接依赖|maven|
|com.squareup.okio:okio|2.8.0|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.79.Final|间接依赖|maven|
|com.squareup.okio:okio-jvm|3.2.0|间接依赖|maven|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|io.perfmark:perfmark-api|0.26.0|间接依赖|maven|
|io.grpc:grpc-xds|1.56.1|间接依赖|maven|
|com.google.http-client:google-http-client-gson|1.43.3|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.6.0|间接依赖|maven|
|com.github.spullara.mustache.java:compiler|0.9.10|直接依赖|maven|
|com.google.api.grpc:grpc-google-iam-v1|1.18.0|间接依赖|maven|
|io.weaviate:client|4.2.1|直接依赖|maven|
|io.netty:netty-codec-http2|4.1.79.Final|间接依赖|maven|
|org.conscrypt:conscrypt-openjdk-uber|2.5.2|间接依赖|maven|
|io.grpc:grpc-services|1.56.1|间接依赖|maven|
|io.netty:netty-tcnative-classes|2.0.59.Final|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.21|间接依赖|maven|
|com.squareup.okio:okio-jvm|3.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.14|间接依赖|maven|
|com.google.guava:guava|31.0.1-android|间接依赖|maven|
|org.apache.pdfbox:fontbox|2.0.29|间接依赖|maven|
|com.squareup.okhttp3:okhttp|4.9.2|间接依赖|maven|
|org.springframework:spring-core|5.3.29|间接依赖|maven|
|com.alibaba:fastjson|1.2.76|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.10.0|间接依赖|maven|
|io.reactivex.rxjava2:rxjava|2.2.21|间接依赖|maven|
|com.google.api.grpc:proto-google-iam-v1|1.18.0|间接依赖|maven|
|io.netty:netty-tcnative-boringssl-static|2.0.59.Final|间接依赖|maven|
|io.milvus:milvus-sdk-java|2.2.9|直接依赖|maven|
|io.grpc:grpc-auth|1.56.1|间接依赖|maven|
|org.yaml:snakeyaml|1.30|间接依赖|maven|
|org.springframework.boot:spring-boot|2.7.14|间接依赖|maven|
|com.nimbusds:lang-tag|1.7|间接依赖|maven|
|org.checkerframework:checker-compat-qual|2.5.5|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|2.14.3|间接依赖|maven|
|com.google.api:api-common|2.15.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.6.20|间接依赖|maven|
|org.springframework:spring-beans|5.3.29|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.14|间接依赖|maven|
|io.grpc:grpc-googleapis|1.56.1|间接依赖|maven|
|io.opencensus:opencensus-contrib-http-util|0.31.1|间接依赖|maven|
|com.google.api:gax|2.32.0|间接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.53.0|间接依赖|maven|
|io.perfmark:perfmark-api|0.25.0|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.23.2|间接依赖|maven|
|com.nimbusds:oauth2-oidc-sdk|10.11|间接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|9.30.2|间接依赖|maven|
|io.netty:netty-handler|4.1.79.Final|间接依赖|maven|
|com.nimbusds:content-type|2.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.14|直接依赖|maven|
|com.squareup.okhttp3:logging-interceptor|4.11.0|间接依赖|maven|
|io.grpc:grpc-context|1.53.0|间接依赖|maven|
|io.grpc:grpc-api|1.46.0|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.19.6|间接依赖|maven|
|org.apache.commons:commons-lang3|3.8.1|间接依赖|maven|
|com.google.auto.value:auto-value-annotations|1.10.2|间接依赖|maven|
|com.github.virtuald:curvesapi|1.07|间接依赖|maven|
|io.grpc:grpc-netty-shaded|1.56.1|间接依赖|maven|
|io.grpc:grpc-protobuf|1.53.0|间接依赖|maven|
|io.netty:netty-resolver|4.1.94.Final|间接依赖|maven|
|io.netty:netty-codec-http|4.1.79.Final|间接依赖|maven|
|com.google.http-client:google-http-client|1.43.3|间接依赖|maven|
|com.google.auth:google-auth-library-credentials|1.19.0|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)