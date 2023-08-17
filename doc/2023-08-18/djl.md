# deepjavalibrary/djl安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692235778783858688.svg)](https://www.murphysec.com/console/report/1692235778641252352/1692235778783858688)

仓库描述：An Engine-Agnostic Deep Learning Framework in Java

仓库地址：[https://github.com/deepjavalibrary/djl](https://github.com/deepjavalibrary/djl)

| star：3421 | watch：95 | fork：565 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-17 08:56:26 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-18 02:29:36 | 组件总数：334 | 漏洞总数：17 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google protobuf 缓冲区错误漏洞|越界写入|[MPS-2017-10841](https://www.oscs1024.com/hd/MPS-2017-10841)|CVE-2015-5237|高危|
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|Netty 存在信息泄露漏洞||[MPS-2022-3790](https://www.oscs1024.com/hd/MPS-2022-3790)|CVE-2022-24823|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|PyTorch 命令注入漏洞|代码注入|[MPS-2022-65270](https://www.oscs1024.com/hd/MPS-2022-65270)|CVE-2022-45907|严重|
|netplex json-smart 安全漏洞|未经控制的递归|[MPS-2023-7760](https://www.oscs1024.com/hd/MPS-2023-7760)|CVE-2023-1370|高危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.xerial.snappy:snappy-java|1.1.8.2|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|io.netty:netty-handler|4.1.94.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.xerial.snappy:snappy-java|1.1.8.4|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|com.google.protobuf:protobuf-java|3.14.0|3.21.7|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|io.netty:netty-handler|4.1.74.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|net.minidev:json-smart|2.4.7|2.4.9|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.google.protobuf:protobuf-java|2.5.0|3.21.7|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|torch|1.11.0|1.13.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.4.2|2.14.0-rc1|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.12.7.1|2.14.0-rc1|直接依赖|建议修复|C:0|H:0|M:3|L:0|
|com.google.guava:guava|16.0.1|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|io.netty:netty-common|4.1.74.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|30.0-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|27.0-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:1|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|203|Low|
|BSD-2-Clause|4|Low|
|MIT|14|Low|
|BSD-3-Clause|15|Low|
|LGPL-2.1|1|Medium|
|MPL-1.1|1|Low|
|EPL-2.0|15|Low|
|CDDL-1.0|1|Low|
|LGPL-2.1-or-later|1|Low|
|GPL-2.0|1|Medium|
|CDDL-1.1|1|Low|
|MIT-0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.apache.hadoop:hadoop-client-runtime|3.3.2|间接依赖|maven|
|software.amazon.awssdk:profiles|2.20.121|间接依赖|maven|
|org.bytedeco:ffmpeg|6.0-1.5.9|直接依赖|maven|
|::engines:pytorch:pytorch-engine||直接依赖|maven|
|io.airlift:aircompressor|0.21|间接依赖|maven|
|io.netty:netty-common|4.1.94.Final|间接依赖|maven|
|org.apache.arrow:arrow-vector|7.0.0|间接依赖|maven|
|org.glassfish:javax.json|1.1.4|间接依赖|maven|
|dnsjava:dnsjava|2.1.7|间接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.74.Final|间接依赖|maven|
|org.apache.commons:commons-configuration2|2.8.0|间接依赖|maven|
|io.netty:netty-tcnative-classes|2.0.48.Final|间接依赖|maven|
|org.apache.yetus:audience-annotations|0.12.0|间接依赖|maven|
|dev.ludovic.netlib:arpack|2.2.1|直接依赖|maven|
|org.apache.kerby:kerb-common|1.0.1|间接依赖|maven|
|org.apache.spark:spark-network-shuffle||间接依赖|maven|
|org.apache.spark:spark-streaming||直接依赖|maven|
|io.netty:netty-resolver|4.1.74.Final|间接依赖|maven|
|org.apache.xbean:xbean-asm9-shaded|4.20|间接依赖|maven|
|io.dropwizard.metrics:metrics-jvm|4.2.7|间接依赖|maven|
|com.google.code.gson:gson|2.10.1|直接依赖|maven|
|org.apache.avro:avro-ipc|1.11.0|间接依赖|maven|
|software.amazon.awssdk:aws-query-protocol|2.20.121|间接依赖|maven|
|org.apache.curator:curator-client|2.13.0|间接依赖|maven|
|org.apache.kerby:kerby-xdr|1.0.1|间接依赖|maven|
|org.antlr:antlr4-runtime|4.8|间接依赖|maven|
|org.json4s:json4s-scalap||间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.3.4|间接依赖|maven|
|torch|1.11.0|间接依赖|pip|
|org.apache.curator:curator-framework|2.13.0|间接依赖|maven|
|org.javassist:javassist|3.25.0-GA|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.2|间接依赖|maven|
|com.fasterxml.jackson:jackson-bom|2.13.4|间接依赖|maven|
|com.microsoft.onnxruntime:onnxruntime|1.15.1|直接依赖|maven|
|org.scalanlp:breeze||直接依赖|maven|
|com.google.errorprone:error||间接依赖|maven|
|org.apache.arrow:arrow-memory-core|7.0.0|间接依赖|maven|
|com.google.guava:guava|30.0-jre|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.12.7|间接依赖|maven|
|::engines:pytorch:pytorch-jni||直接依赖|maven|
|org.checkerframework:checker-qual|3.5.0|间接依赖|maven|
|software.amazon.awssdk:regions|2.20.121|间接依赖|maven|
|org.json4s:json4s-jackson||间接依赖|maven|
|org.apache.arrow:arrow-memory-netty|7.0.0|间接依赖|maven|
|org.apache.kerby:kerby-util|1.0.1|间接依赖|maven|
|org.typelevel:spire-macros||间接依赖|maven|
|org.glassfish.hk2:hk2-api|2.6.1|间接依赖|maven|
|com.ibm.icu:icu4j|65.1|直接依赖|maven|
|com.microsoft.ml.lightgbm:lightgbmlib|3.2.110|直接依赖|maven|
|ai.djl:api|0.24.0-SNAPSHOT|直接依赖|maven|
|org.apache.curator:curator-framework|4.2.0|间接依赖|maven|
|org.apache.orc:orc-core|1.7.8|间接依赖|maven|
|::engines:tensorflow:tensorflow-engine||直接依赖|maven|
|org.apache.hadoop:hadoop-client-api|3.3.2|间接依赖|maven|
|org.typelevel:macro-compat||间接依赖|maven|
|software.amazon.awssdk:json-utils|2.20.121|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.17|间接依赖|maven|
|org.apache.arrow:arrow-format|7.0.0|间接依赖|maven|
|commons-lang:commons-lang|2.6|间接依赖|maven|
|commons-cli:commons-cli|1.2|间接依赖|maven|
|org.apache.commons:commons-math3|3.6.1|直接依赖|maven|
|org.apache.hadoop:hadoop-annotations|3.3.5|间接依赖|maven|
|org.apache.spark:spark-mllib||直接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.2|间接依赖|maven|
|software.amazon.awssdk:bom|2.20.121|直接依赖|maven|
|org.apache.parquet:parquet-jackson|1.12.2|间接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j-impl|2.20.0|直接依赖|maven|
|net.razorvine:pickle|1.2|间接依赖|maven|
|org.apache.parquet:parquet-column|1.12.2|间接依赖|maven|
|::extensions:tokenizers||直接依赖|maven|
|com.univocity:univocity-parsers|2.8.4|直接依赖|maven|
|org.apache.commons:commons-math3|3.1.1|间接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.8|间接依赖|maven|
|org.openpnp:opencv|4.7.0-0|直接依赖|maven|
|io.dropwizard.metrics:metrics-core|4.2.7|间接依赖|maven|
|org.apache.hadoop:hadoop-client|3.3.5|直接依赖|maven|
|software.amazon.awssdk:metrics-spi|2.20.121|间接依赖|maven|
|commons-net:commons-net|3.9.0|间接依赖|maven|
|org.apache.parquet:parquet-hadoop|1.12.2|间接依赖|maven|
|::extensions:audio||直接依赖|maven|
|io.dropwizard.metrics:metrics-json|4.2.7|间接依赖|maven|
|oro:oro|2.0.8|间接依赖|maven|
|ai.djl.huggingface:tokenizers|0.24.0-SNAPSHOT|直接依赖|maven|
|software.amazon.awssdk:utils|2.20.121|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.2-1|间接依赖|maven|
|com.google.re2j:re2j|1.1|间接依赖|maven|
|org.typelevel:algebra||间接依赖|maven|
|org.apache.orc:orc-shims|1.7.8|间接依赖|maven|
|net.sf.py4j:py4j|0.10.9.5|间接依赖|maven|
|ai.djl:model-zoo|0.24.0-SNAPSHOT|直接依赖|maven|
|commons-io:commons-io|2.11.0|间接依赖|maven|
|software.amazon.awssdk:s3|2.20.121|直接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.1|间接依赖|maven|
|org.jetbrains:annotations|17.0.0|间接依赖|maven|
|com.microsoft.onnxruntime:onnxruntime-android|1.15.1|直接依赖|maven|
|software.amazon.awssdk:apache-client|2.20.121|间接依赖|maven|
|software.amazon.awssdk:annotations|2.20.121|间接依赖|maven|
|org.apache.spark:spark-kvstore||间接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j-impl|2.17.2|间接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|2.3.2|直接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|5.4.0|间接依赖|maven|
|io.netty:netty-buffer|4.1.74.Final|间接依赖|maven|
|org.apache.kerby:kerb-core|1.0.1|间接依赖|maven|
|io.github.classgraph:classgraph|4.8.60|直接依赖|maven|
|org.glassfish.hk2:hk2-locator|2.6.1|间接依赖|maven|
|org.checkerframework:checker-qual|2.5.2|间接依赖|maven|
|org.apache.avro:avro-mapred|1.11.0|间接依赖|maven|
|commons-logging:commons-logging|1.2|直接依赖|maven|
|net.minidev:json-smart|2.4.7|间接依赖|maven|
|org.codehaus.janino:commons-compiler|3.0.16|间接依赖|maven|
|org.objenesis:objenesis|2.5.1|间接依赖|maven|
|::basicdataset||直接依赖|maven|
|io.dropwizard.metrics:metrics-jmx|4.2.7|间接依赖|maven|
|io.netty:netty-buffer|4.1.94.Final|间接依赖|maven|
|software.amazon.awssdk:http-client-spi|2.20.121|间接依赖|maven|
|org.apache.spark:spark-mllib-local||直接依赖|maven|
|org.scala-lang.modules:scala-parser-combinators||直接依赖|maven|
|com.github.stephenc.jcip:jcip-annotations|1.0-1|间接依赖|maven|
|org.typelevel:spire-util||间接依赖|maven|
|ai.djl.mxnet:mxnet-engine|0.24.0-SNAPSHOT|间接依赖|maven|
|com.google.flatbuffers:flatbuffers-java|1.12.0|间接依赖|maven|
|pl.edu.icm:JLargeArrays|1.5|间接依赖|maven|
|org.tensorflow:ndarray|0.4.0|直接依赖|maven|
|javax.activation:activation|1.1.1|间接依赖|maven|
|org.glassfish.hk2:hk2-utils|2.6.1|间接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j-impl|2.18.0|直接依赖|maven|
|dev.ludovic.netlib:blas|2.2.1|直接依赖|maven|
|org.bytedeco:javacpp|1.5.9|直接依赖|maven|
|org.roaringbitmap:shims|0.9.25|间接依赖|maven|
|org.json4s:json4s-core||间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.4|间接依赖|maven|
|software.amazon.awssdk:arns|2.20.121|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.25|直接依赖|maven|
|org.glassfish.jersey.core:jersey-server|2.36|间接依赖|maven|
|org.scalanlp:breeze-macros||间接依赖|maven|
|org.fusesource.leveldbjni:leveldbjni-all|1.8|间接依赖|maven|
|org.antlr:antlr4-runtime|4.11.1|直接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.18.0|间接依赖|maven|
|org.tukaani:xz|1.9|间接依赖|maven|
|tech.tablesaw:tablesaw-core|0.43.1|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.12.7.1|直接依赖|maven|
|com.google.protobuf:protobuf-java|3.14.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.18.0|间接依赖|maven|
|org.openjfx:javafx-base|11|间接依赖|maven|
|net.java.dev.jna:jna|5.13.0|直接依赖|maven|
|software.amazon.awssdk:third-party-jackson-core|2.20.121|间接依赖|maven|
|com.google.guava:failureaccess|1.0|间接依赖|maven|
|::engines:tensorflow:tensorflow-model-zoo||直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.12.7|间接依赖|maven|
|org.apache.kerby:kerby-asn1|1.0.1|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.74.Final|间接依赖|maven|
|org.apache.commons:commons-crypto|1.1.0|间接依赖|maven|
|org.apache.curator:curator-client|4.2.0|间接依赖|maven|
|org.apache.commons:commons-csv|1.10.0|直接依赖|maven|
|::engines:tensorflow:tensorflow-api||直接依赖|maven|
|software.amazon.awssdk:sdk-core|2.20.121|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.94.Final|间接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.20.0|直接依赖|maven|
|org.apache.kerby:kerb-admin|1.0.1|间接依赖|maven|
|org.apache.orc:orc-mapreduce|1.7.8|间接依赖|maven|
|org.scala-lang.modules:scala-collection-compat||间接依赖|maven|
|io.netty:netty-handler|4.1.94.Final|间接依赖|maven|
|jakarta.servlet:jakarta.servlet-api|4.0.3|间接依赖|maven|
|org.apache.spark:spark-sql||直接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|org.apache.kerby:kerb-server|1.0.1|间接依赖|maven|
|commons-logging:commons-logging|1.1.3|间接依赖|maven|
|org.apache.zookeeper:zookeeper-jute|3.6.2|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|间接依赖|maven|
|com.fasterxml.jackson:jackson-bom|2.12.7|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.74.Final|间接依赖|maven|
|software.amazon.awssdk:endpoints-spi|2.20.121|间接依赖|maven|
|org.json4s:json4s-ast||间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|io.netty:netty-codec-http|4.1.94.Final|间接依赖|maven|
|com.github.wendykierp:JTransforms|3.1|直接依赖|maven|
|org.rocksdb:rocksdbjni|6.20.3|间接依赖|maven|
|net.sf.opencsv:opencsv|2.3|间接依赖|maven|
|ai.djl.mxnet:mxnet-model-zoo|0.24.0-SNAPSHOT|直接依赖|maven|
|org.apache.spark:spark-tags||直接依赖|maven|
|org.glassfish.hk2:osgi-resource-locator|1.0.3|间接依赖|maven|
|::engines:onnxruntime:onnxruntime-engine||直接依赖|maven|
|software.amazon.eventstream:eventstream|1.0.1|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.32|间接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|org.apache.spark:spark-launcher||间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet-core|2.36|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.4|间接依赖|maven|
|org.testng:testng|7.8.0|直接依赖|maven|
|io.netty:netty-all|4.1.74.Final|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.74.Final|间接依赖|maven|
|org.apache.commons:commons-compress|1.23.0|直接依赖|maven|
|io.netty:netty-common|4.1.74.Final|间接依赖|maven|
|org.apache.kerby:token-provider|1.0.1|间接依赖|maven|
|org.scala-lang:scala-reflect|2.12.15|间接依赖|maven|
|com.google.guava:guava|16.0.1|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.94.Final|间接依赖|maven|
|org.antlr:antlr4|4.11.1|直接依赖|maven|
|org.apache.spark:spark-network-common||间接依赖|maven|
|com.google.protobuf:protobuf-java|2.5.0|间接依赖|maven|
|org.apache.hadoop:hadoop-auth|3.3.5|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.32|间接依赖|maven|
|org.apache.ivy:ivy|2.5.1|间接依赖|maven|
|com.twitter:chill-java|0.10.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.20.0|直接依赖|maven|
|org.glassfish.jersey.core:jersey-common|2.36|间接依赖|maven|
|org.roaringbitmap:RoaringBitmap|0.9.25|直接依赖|maven|
|org.apache.spark:spark-catalyst||间接依赖|maven|
|::extensions:timeseries||直接依赖|maven|
|org.typelevel:spire-platform||间接依赖|maven|
|org.spark-project.spark:unused|1.0.0|直接依赖|maven|
|org.apache.kerby:kerby-pkix|1.0.1|间接依赖|maven|
|io.netty:netty-codec|4.1.94.Final|间接依赖|maven|
|software.amazon.awssdk:protocol-core|2.20.121|间接依赖|maven|
|org.apache.parquet:parquet-format-structures|1.12.2|间接依赖|maven|
|org.apache.kerby:kerb-simplekdc|1.0.1|间接依赖|maven|
|com.github.fommil.netlib:core|1.1.2|间接依赖|maven|
|org.apache.commons:commons-math3|3.5|间接依赖|maven|
|org.apache.parquet:parquet-common|1.12.2|间接依赖|maven|
|org.scala-lang.modules:scala-xml||间接依赖|maven|
|ai.djl.pytorch:pytorch-engine|0.24.0-SNAPSHOT|间接依赖|maven|
|io.netty:netty-transport|4.1.94.Final|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.23.3|直接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet|2.36|间接依赖|maven|
|org.lz4:lz4-java|1.8.0|间接依赖|maven|
|com.clearspring.analytics:stream|2.9.6|间接依赖|maven|
|org.apache.hive:hive-storage-api|2.7.2|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|::api||直接依赖|maven|
|software.amazon.awssdk:aws-core|2.20.121|间接依赖|maven|
|io.netty:netty-resolver|4.1.94.Final|间接依赖|maven|
|org.apache.logging.log4j:log4j-1.2-api|2.17.2|间接依赖|maven|
|dev.ludovic.netlib:lapack|2.2.1|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|间接依赖|maven|
|software.amazon.awssdk:netty-nio-client|2.20.121|间接依赖|maven|
|software.amazon.awssdk:crt-core|2.20.121|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-scala||间接依赖|maven|
|:No dependencies||直接依赖|maven|
|org.apache.spark:spark-unsafe||间接依赖|maven|
|ai.djl.audio:audio|0.24.0-SNAPSHOT|直接依赖|maven|
|com.ning:compress-lzf|1.1|间接依赖|maven|
|com.sun.istack:istack-commons-runtime|3.0.8|间接依赖|maven|
|org.antlr:ST4|4.3.4|间接依赖|maven|
|org.codehaus.woodstox:stax2-api|4.2.1|间接依赖|maven|
|com.google.crypto.tink:tink|1.6.1|间接依赖|maven|
|jakarta.ws.rs:jakarta.ws.rs-api|2.1.6|间接依赖|maven|
|org.apache.curator:curator-recipes|4.2.0|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.4|间接依赖|maven|
|com.twitter:chill||间接依赖|maven|
|org.abego.treelayout:org.abego.treelayout.core|1.0.3|间接依赖|maven|
|com.ibm.icu:icu4j|71.1|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|::engines:mxnet:mxnet-engine||直接依赖|maven|
|com.beust:jcommander|1.82|直接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.1|间接依赖|maven|
|org.webjars:jquery|3.6.1|直接依赖|maven|
|::engines:ml:xgboost||直接依赖|maven|
|org.glassfish.jersey.core:jersey-client|2.36|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|间接依赖|maven|
|io.netty:netty-codec|4.1.74.Final|间接依赖|maven|
|commons-io:commons-io|2.8.0|间接依赖|maven|
|ai.djl.pytorch:pytorch-model-zoo|0.24.0-SNAPSHOT|直接依赖|maven|
|org.apache.hadoop.thirdparty:hadoop-shaded-protobuf||间接依赖|maven|
|org.apache.parquet:parquet-encoding|1.12.2|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.13|间接依赖|maven|
|org.apache.commons:commons-text|1.10.0|间接依赖|maven|
|org.codehaus.janino:janino|3.0.16|间接依赖|maven|
|io.netty:netty-transport|4.1.74.Final|间接依赖|maven|
|protobuf|3.20.2|间接依赖|pip|
|ai.djl:basicdataset|0.24.0-SNAPSHOT|直接依赖|maven|
|com.univocity:univocity-parsers|2.9.1|间接依赖|maven|
|com.esotericsoftware:minlog|1.3.0|间接依赖|maven|
|org.apache.kerby:kerby-config|1.0.1|间接依赖|maven|
|org.apache.hadoop:hadoop-common|3.3.5|间接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|9.8.1|间接依赖|maven|
|org.glassfish.jersey.inject:jersey-hk2|2.36|间接依赖|maven|
|it.unimi.dsi:fastutil|8.3.0|直接依赖|maven|
|org.apache.kerby:kerb-crypto|1.0.1|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|::engines:paddlepaddle:paddlepaddle-engine||直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.4.2|间接依赖|maven|
|org.antlr:antlr-runtime|3.5.3|间接依赖|maven|
|ai.djl.onnxruntime:onnxruntime-engine|0.24.0-SNAPSHOT|直接依赖|maven|
|org.apache.avro:avro|1.11.0|间接依赖|maven|
|org.bytedeco:javacv|1.5.9|直接依赖|maven|
|org.apache.spark:spark-sketch||间接依赖|maven|
|io.dropwizard.metrics:metrics-graphite|4.2.7|间接依赖|maven|
|::testing||直接依赖|maven|
|::engines:ml:lightgbm||直接依赖|maven|
|com.esotericsoftware:kryo-shaded|4.0.2|间接依赖|maven|
|io.netty:netty-handler|4.1.74.Final|间接依赖|maven|
|org.tensorflow:tensorflow-core-api|0.5.0|直接依赖|maven|
|org.ow2.asm:asm|9.1|间接依赖|maven|
|org.scala-lang:scala-library|2.12.15|间接依赖|maven|
|org.typelevel:spire||间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|org.apache.spark:spark-graphx||直接依赖|maven|
|org.apache.spark:spark-core||直接依赖|maven|
|org.apache.curator:curator-recipes|2.13.0|间接依赖|maven|
|org.threeten:threeten-extra|1.5.0|间接依赖|maven|
|ai.djl.timeseries:timeseries|0.24.0-SNAPSHOT|直接依赖|maven|
|org.glassfish.hk2.external:aopalliance-repackaged|2.6.1|间接依赖|maven|
|org.apache.hadoop:hadoop-hdfs-client|3.3.5|间接依赖|maven|
|software.amazon.awssdk:aws-xml-protocol|2.20.121|间接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.74.Final|间接依赖|maven|
|net.sourceforge.f2j:arpack||间接依赖|maven|
|org.apache.commons:commons-collections4|4.4|间接依赖|maven|
|org.apache.kerby:kerb-client|1.0.1|间接依赖|maven|
|ml.dmlc:xgboost4j||直接依赖|maven|
|software.amazon.awssdk:auth|2.20.121|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.2|间接依赖|maven|
|ai.djl.tensorflow:tensorflow-api|0.24.0-SNAPSHOT|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.6.2|间接依赖|maven|
|org.apache.kerby:kerb-identity|1.0.1|间接依赖|maven|
|::engines:pytorch:pytorch-model-zoo||直接依赖|maven|
|commons-cli:commons-cli|1.5.0|直接依赖|maven|
|::model-zoo||直接依赖|maven|
|org.apache.hadoop.thirdparty:hadoop-shaded-guava|1.1.1|间接依赖|maven|
|com.google.guava:guava|27.0-jre|间接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.17.2|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.94.Final|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|com.chuusai:shapeless||间接依赖|maven|
|ai.djl.tensorflow:tensorflow-model-zoo|0.24.0-SNAPSHOT|直接依赖|maven|
|net.minidev:accessors-smart|2.4.7|间接依赖|maven|
|org.glassfish.hk2.external:jakarta.inject|2.6.1|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|ai.djl.tensorflow:tensorflow-engine|0.24.0-SNAPSHOT|间接依赖|maven|
|org.apache.kerby:kerb-util|1.0.1|间接依赖|maven|
|org.openjfx:javafx-graphics|11|间接依赖|maven|
|::engines:mxnet:mxnet-model-zoo||直接依赖|maven|
|org.typelevel:cats-kernel||间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)