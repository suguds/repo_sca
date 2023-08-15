# paypal/junodb安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1691512851574706176.svg)](https://www.murphysec.com/console/report/1691512851520180224/1691512851574706176)

仓库描述：JunoDB is PayPal's home-grown secure, consistent and highly available key-value store providing low, single digit millisecond, latency at any scale.

仓库地址：[https://github.com/paypal/junodb](https://github.com/paypal/junodb)

| star：2096 | watch：23 | fork：123 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-15 14:51:32 | 许可证：- |
| 最近检测时间：2023-08-16 02:13:09 | 组件总数：199 | 漏洞总数：15 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|MPS-2020-0057|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|MPS-2021-7854|使用具有密码学弱点缺陷的PRNG|[MPS-2021-7854](https://www.oscs1024.com/hd/MPS-2021-7854)|CVE-2021-3538|严重|
|MPS-2022-1098|大小写敏感处理不恰当|[MPS-2022-1098](https://www.oscs1024.com/hd/MPS-2022-1098)|CVE-2022-22968|中危|
|MPS-2022-1101|不加限制或调节的资源分配|[MPS-2022-1101](https://www.oscs1024.com/hd/MPS-2022-1101)|CVE-2022-22970|中危|
|MPS-2022-12067|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|MPS-2022-58653|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
|MPS-2022-62832|关键资源权限分配不当|[MPS-2022-62832](https://www.oscs1024.com/hd/MPS-2022-62832)|CVE-2023-20860|高危|
|MPS-2022-62835|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|MPS-2022-62855|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|MPS-2022-68556||[MPS-2022-68556](https://www.oscs1024.com/hd/MPS-2022-68556)|CVE-2023-21971|中危|
|MPS-8znw-4jmi|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|MPS-9u07-bna1|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|MPS-angp-mxl2|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|MPS-tnp7-60hk|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|MPS-z1bx-p8y2|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.mysql:mysql-connector-j|8.0.32|8.0.33|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|io.netty:netty-handler|4.1.90.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.5|2.14.0-rc1|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|github.com/satori/go.uuid|v1.2.0||直接依赖|建议修复|C:1|H:0|M:0|L:0|
|io.netty:netty-handler|4.1.82.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|io.netty:netty-handler|4.1.94.Final|4.1.94.final|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-web|5.3.26|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.7.10|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.xerial.snappy:snappy-java|1.1.9.1|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.springframework:spring-context|5.3.17|5.3.19|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-web|5.3.19|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework:spring-webmvc|5.3.19|6.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-beans|5.3.18|5.3.20|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|5.3.26|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-expression|5.3.17|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|110|Low|
|EPL-1.0|2|Low|
|MIT|9|Low|
|BSD-2-Clause|1|Low|
|CDDL-1.1|2|Low|
|GPL-3.0|1|Medium|
|LGPL-2.1-or-later|2|Low|
|EPL-2.0|4|Low|
|自定义许可证|1|Low|
|GPL-2.0-only|1|Low|
|MIT-0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.springframework.boot:spring-boot-starter-tomcat|2.7.10|间接依赖|maven|
|go.opentelemetry.io/otel/metric|v0.34.0|直接依赖|go|
|org.apache.logging.log4j:log4j-api|2.17.2|间接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|间接依赖|maven|
|go.etcd.io/etcd/client/v3|v3.5.4|直接依赖|go|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.2|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.5|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.11|直接依赖|maven|
|org.springframework:spring-beans|5.3.26|间接依赖|maven|
|github.com/golang/protobuf|v1.5.2|间接依赖|go|
|github.com/facebookgo/stack|v0.0.0-20160209184415-751773369052|间接依赖|go|
|org.slf4j:slf4j-api|1.7.36|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|ffi|1.15.5|间接依赖|bundler|
|io.prometheus:simpleclient_tracer_otel_agent|0.15.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.6.7|间接依赖|maven|
|rspec|3.12.0|间接依赖|bundler|
|language_server-protocol|3.17.0.3|间接依赖|bundler|
|io.projectreactor:reactor-core|3.4.28|间接依赖|maven|
|rspec-expectations|3.12.3|间接依赖|bundler|
|io.netty:netty-handler|4.1.94.Final|直接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.6.15|直接依赖|maven|
|org.springframework.boot:spring-boot|2.7.10|间接依赖|maven|
|org.springframework:spring-jcl|5.3.27|间接依赖|maven|
|commons-logging:commons-logging|1.1.1|间接依赖|maven|
|github.com/kr/pretty|v0.3.0|间接依赖|go|
|org.springframework:spring-expression|5.3.27|间接依赖|maven|
|org.springframework.data:spring-data-jpa|2.7.10|间接依赖|maven|
|org.yaml:snakeyaml|2.0|直接依赖|maven|
|io.netty:netty-transport|4.1.90.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-jpa|2.7.10|直接依赖|maven|
|ast|2.4.2|间接依赖|bundler|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.5|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.10|间接依赖|maven|
|javax.ws.rs:javax.ws.rs-api|2.0|直接依赖|maven|
|rainbow|3.1.1|间接依赖|bundler|
|com.paypal.juno:juno-client-impl|1.0.0|直接依赖|maven|
|org.springframework:spring-jcl|5.3.26|间接依赖|maven|
|google.golang.org/genproto|v0.0.0-20211118181313-81c1377c94b1|间接依赖|go|
|golang.org/x/exp|v0.0.0-20200331195152-e8c3332aa8e5|间接依赖|go|
|racc|1.7.1|间接依赖|bundler|
|org.springframework:spring-jdbc|5.3.26|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.2|间接依赖|maven|
|github.com/rogpeppe/go-internal|v1.6.2|间接依赖|go|
|github.com/facebookgo/ensure|v0.0.0-20200202191622-63f1cf65ac4c|直接依赖|go|
|rspec-support|3.12.1|间接依赖|bundler|
|org.springframework.boot:spring-boot-starter-logging|2.6.7|间接依赖|maven|
|io.netty:netty-buffer|4.1.90.Final|间接依赖|maven|
|org.springframework:spring-expression|5.3.26|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.7.10|间接依赖|maven|
|github.com/go-logr/logr|v1.2.3|间接依赖|go|
|go.opentelemetry.io/otel/sdk/metric|v0.34.0|直接依赖|go|
|golang.org/x/sys|v0.5.0|间接依赖|go|
|go.uber.org/atomic|v1.9.0|间接依赖|go|
|org.slf4j:slf4j-api|2.0.6|直接依赖|maven|
|org.springframework.boot:spring-boot-actuator|2.7.11|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.7.10|直接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.82.Final|间接依赖|maven|
|io.netty:netty-handler|4.1.82.Final|间接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|2.3.8|间接依赖|maven|
|org.springframework:spring-expression|5.3.17|间接依赖|maven|
|rexml|3.2.6|间接依赖|bundler|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.7.11|直接依赖|maven|
|com.sun.istack:istack-commons-runtime|3.0.12|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.2|间接依赖|maven|
|org.slf4j:slf4j-simple|2.0.6|直接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.94.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.10|间接依赖|maven|
|org.springframework:spring-aop|5.3.26|间接依赖|maven|
|github.com/spaolacci/murmur3|v1.1.0|直接依赖|go|
|org.springframework:spring-web|5.3.26|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.62|间接依赖|maven|
|org.glassfish.jaxb:txw2|2.3.8|间接依赖|maven|
|org.hibernate:hibernate-core|5.6.15.Final|间接依赖|maven|
|go.opentelemetry.io/otel/exporters/otlp/internal/retry|v1.11.2|间接依赖|go|
|github.com/facebookgo/subset|v0.0.0-20200203212716-c811ad88dec4|间接依赖|go|
|org.aspectj:aspectjweaver|1.9.7|间接依赖|maven|
|rspec-mocks|3.12.6|间接依赖|bundler|
|rspec-core|3.12.2|间接依赖|bundler|
|parallel|1.23.0|间接依赖|bundler|
|github.com/grpc-ecosystem/grpc-gateway/v2|v2.7.0|间接依赖|go|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.7.10|间接依赖|maven|
|io.projectreactor:reactor-core|3.4.23|直接依赖|maven|
|github.com/HdrHistogram/hdrhistogram-go|v1.1.2|直接依赖|go|
|org.springframework:spring-aspects|5.3.26|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.10.1|直接依赖|maven|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|io.netty:netty-buffer|4.1.82.Final|直接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.6.7|间接依赖|maven|
|go.opentelemetry.io/otel/exporters/otlp/otlpmetric|v0.34.0|间接依赖|go|
|org.springframework.boot:spring-boot-starter-aop|2.7.10|间接依赖|maven|
|io.prometheus:simpleclient_common|0.15.0|间接依赖|maven|
|github.com/coreos/go-semver|v0.3.0|间接依赖|go|
|rubocop-ast|1.29.0|间接依赖|bundler|
|io.netty:netty-transport|4.1.82.Final|直接依赖|maven|
|org.springframework.boot:spring-boot-devtools|2.7.10|直接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.90.Final|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.23|间接依赖|maven|
|org.springframework.data:spring-data-commons|2.7.10|间接依赖|maven|
|get_process_mem|0.2.7|间接依赖|bundler|
|regexp_parser|2.8.1|间接依赖|bundler|
|org.springframework:spring-aop|5.3.17|间接依赖|maven|
|org.thymeleaf:thymeleaf|3.0.15.RELEASE|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.3.Final|间接依赖|maven|
|commons-codec:commons-codec|1.15|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.7.10|间接依赖|maven|
|json|2.5.1|间接依赖|bundler|
|org.unbescape:unbescape|1.1.6.RELEASE|间接依赖|maven|
|javax.inject:javax.inject|1|直接依赖|maven|
|org.springframework.boot:spring-boot|2.6.7|直接依赖|maven|
|com.mysql:mysql-connector-j|8.0.32|直接依赖|maven|
|org.springframework:spring-orm|5.3.26|间接依赖|maven|
|org.springframework:spring-context|5.3.17|直接依赖|maven|
|go.opentelemetry.io/otel/sdk|v1.11.2|直接依赖|go|
|org.xerial.snappy:snappy-java|1.1.9.1|间接依赖|maven|
|go.uber.org/multierr|v1.6.0|间接依赖|go|
|org.springframework:spring-aop|5.3.27|间接依赖|maven|
|io.netty:netty-codec|4.1.82.Final|直接依赖|maven|
|unicode-display_width|2.4.2|间接依赖|bundler|
|io.netty:netty-resolver|4.1.82.Final|间接依赖|maven|
|github.com/cenkalti/backoff/v4|v4.2.0|间接依赖|go|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.5|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.62|间接依赖|maven|
|io.prometheus:simpleclient|0.15.0|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|parser|3.2.2.3|间接依赖|bundler|
|github.com/coreos/go-systemd/v22|v22.3.2|间接依赖|go|
|org.springframework.boot:spring-boot-starter-web|2.6.7|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.73|间接依赖|maven|
|go.uber.org/zap|v1.19.0|间接依赖|go|
|com.sun.activation:jakarta.activation|1.2.2|间接依赖|maven|
|io.netty:netty-common|4.1.82.Final|直接依赖|maven|
|org.springframework:spring-context|5.3.27|直接依赖|maven|
|io.netty:netty-handler|4.1.90.Final|间接依赖|maven|
|com.signalfx.public:micrometer-registry-signalfx|1.9.2-splunk3|直接依赖|maven|
|ruby-progressbar|1.13.0|间接依赖|bundler|
|org.springframework:spring-context|5.3.26|间接依赖|maven|
|com.paypal.juno:juno-client-api|1.0.0|直接依赖|maven|
|io.netty:netty-resolver|4.1.90.Final|间接依赖|maven|
|io.micrometer:micrometer-core|1.9.4|直接依赖|maven|
|commons-configuration:commons-configuration|1.10|直接依赖|maven|
|org.jboss:jandex|2.4.2.Final|间接依赖|maven|
|antlr:antlr|2.7.7|间接依赖|maven|
|org.attoparser:attoparser|2.0.5.RELEASE|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.26|间接依赖|maven|
|rocksdb|6.0.2|间接依赖||
|golang.org/x/net|v0.7.0|间接依赖|go|
|io.micrometer:micrometer-registry-prometheus|1.9.4|直接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|io.netty:netty-common|4.1.90.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.5|间接依赖|maven|
|org.springframework:spring-beans|5.3.27|直接依赖|maven|
|go.etcd.io/etcd/api/v3|v3.5.4|间接依赖|go|
|io.netty:netty-codec|4.1.90.Final|间接依赖|maven|
|org.springframework:spring-beans|5.3.18|直接依赖|maven|
|jakarta.persistence:jakarta.persistence-api|2.2.3|间接依赖|maven|
|google.golang.org/grpc|v1.51.0|间接依赖|go|
|io.micrometer:micrometer-core|1.9.9|间接依赖|maven|
|rubocop|1.55.0|间接依赖|bundler|
|go.opentelemetry.io/otel/trace|v1.11.2|间接依赖|go|
|org.springframework.boot:spring-boot-starter-thymeleaf|2.7.10|直接依赖|maven|
|org.thymeleaf:thymeleaf-spring5|3.0.15.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.5|间接依赖|maven|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.73|间接依赖|maven|
|commons-lang:commons-lang|2.6|间接依赖|maven|
|io.prometheus:simpleclient_tracer_common|0.15.0|间接依赖|maven|
|github.com/BurntSushi/toml|v1.1.0|直接依赖|go|
|io.reactivex:rxjava|1.3.8|直接依赖|maven|
|ipaddr|1.2.5|间接依赖|bundler|
|org.springframework:spring-web|5.3.19|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.62|间接依赖|maven|
|go.etcd.io/etcd/client/pkg/v3|v3.5.4|间接依赖|go|
|github.com/golang/snappy|v0.0.4|直接依赖|go|
|diff-lcs|1.5.0|间接依赖|bundler|
|org.springframework:spring-webmvc|5.3.19|间接依赖|maven|
|openssl|2.2.3|间接依赖|bundler|
|org.springframework:spring-core|5.3.27|直接依赖|maven|
|go.opentelemetry.io/proto/otlp|v0.19.0|直接依赖|go|
|org.thymeleaf.extras:thymeleaf-extras-java8time|3.0.4.RELEASE|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.73|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.5|间接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|gopkg.in/check.v1|v1.0.0-20201130134442-10cb98267c6c|间接依赖|go|
|org.springframework:spring-tx|5.3.26|间接依赖|maven|
|golang.org/x/text|v0.7.0|间接依赖|go|
|org.hibernate.common:hibernate-commons-annotations|5.1.2.Final|间接依赖|maven|
|go.opentelemetry.io/otel|v1.11.2|直接依赖|go|
|ch.qos.logback:logback-core|1.2.11|间接依赖|maven|
|io.prometheus:simpleclient_tracer_otel|0.15.0|间接依赖|maven|
|go.opentelemetry.io/otel/exporters/otlp/otlpmetric/otlpmetrichttp|v0.34.0|直接依赖|go|
|jakarta.transaction:jakarta.transaction-api|1.3.3|间接依赖|maven|
|google.golang.org/protobuf|v1.28.1|直接依赖|go|
|com.signalfx.public:signalfx-java|1.0.23|间接依赖|maven|
|github.com/satori/go.uuid|v1.2.0|直接依赖|go|
|org.springframework.boot:spring-boot-starter-tomcat|2.6.7|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)