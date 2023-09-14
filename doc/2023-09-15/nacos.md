# alibaba/nacos安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1702383035748057088.svg)](https://www.murphysec.com/console/report/1691872469650792448/1702383035748057088)

仓库描述：an easy-to-use dynamic service discovery, configuration and service management platform for building cloud native applications.

仓库地址：[https://github.com/alibaba/nacos](https://github.com/alibaba/nacos)

| star：27490 | watch：912 | fork：12169 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-14 23:31:09 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-15 02:06:50 | 组件总数：197 | 漏洞总数：8 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|SOFA-Hessian 代码问题漏洞||[MPS-2019-1978](https://www.oscs1024.com/hd/MPS-2019-1978)|CVE-2019-9212|严重|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|com.alibaba.nacos:nacos-config 存在认证机制不恰当漏洞|身份验证不当|[MPS-2022-12242](https://www.oscs1024.com/hd/MPS-2022-12242)||高危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Apache Tomcat FORM 重定向漏洞|跨站重定向|[MPS-uy56-j8e4](https://www.oscs1024.com/hd/MPS-uy56-j8e4)|CVE-2023-41080|低危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.alipay.sofa:hessian|3.3.6|4.0.3|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.alibaba.nacos:nacos-config|2.3.0-SNAPSHOT||直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.12.7.1|2.14.0-rc1|直接依赖|建议修复|C:0|H:0|M:3|L:0|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.79|11.0.0-m6|直接依赖|建议修复|C:0|H:0|M:0|L:1|
|org.springframework:spring-web|5.3.29|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.google.guava:guava|31.1-android|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|106|Low|
|MIT|57|Low|
|BSD-3-Clause|4|Low|
|自定义许可证|6|Low|
|ISC|2|Low|
|EPL-2.0|2|Low|
|BSD-2-Clause|1|Low|
|EPL-1.0|2|Low|
|Python-2.0|1|Low|
|LGPL-2.1|1|Medium|
|GPL-2.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.springframework.boot:spring-boot|2.7.15|直接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|@babel/runtime|7.18.9|间接依赖|npm|
|com.alibaba.nacos:nacos-persistence|2.3.0-SNAPSHOT|直接依赖|maven|
|shallow-element-equals|1.0.1|间接依赖|npm|
|org.checkerframework:checker-qual|3.12.0|间接依赖|maven|
|qs|6.11.0|间接依赖|npm|
|com.alibaba.nacos:nacos-auth|2.3.0-SNAPSHOT|直接依赖|maven|
|com.alibaba.nacos:nacos-custom-environment-plugin|2.3.0-SNAPSHOT|直接依赖|maven|
|react-router-dom|5.3.3|间接依赖|npm|
|org.apache.logging.log4j:log4j-slf4j-impl|2.17.1|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.7.15|间接依赖|maven|
|has-symbols|1.0.3|间接依赖|npm|
|org.springframework.boot:spring-boot-autoconfigure|2.7.15|间接依赖|maven|
|bignumber.js|9.0.2|间接依赖|npm|
|com.google.protobuf:protobuf-java|3.21.11|直接依赖|maven|
|org.springframework.security:spring-security-crypto|5.7.10|间接依赖|maven|
|org.javatuples:javatuples|1.2|直接依赖|maven|
|com.alibaba.nacos:nacos-core|2.3.0-SNAPSHOT|直接依赖|maven|
|@alifd/overlay|0.2.11|间接依赖|npm|
|org.apache.derby:derby|10.14.2.0|直接依赖|maven|
|io.grpc:grpc-netty-shaded|1.50.2|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.5|间接依赖|maven|
|history|4.10.1|间接依赖|npm|
|org.apache.httpcomponents:httpcore|4.4.16|直接依赖|maven|
|org.springframework:spring-context|5.3.29|间接依赖|maven|
|io.micrometer:micrometer-registry-elastic|1.9.14|直接依赖|maven|
|io.perfmark:perfmark-api|0.25.0|间接依赖|maven|
|path-to-regexp|1.8.0|间接依赖|npm|
|javax.annotation:javax.annotation-api|1.3.2|直接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.5|直接依赖|maven|
|regenerator-runtime|0.11.1|间接依赖|npm|
|com.alipay.sofa:hessian|3.3.6|间接依赖|maven|
|has|1.0.3|间接依赖|npm|
|io.prometheus:simpleclient|0.15.0|直接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|redux|4.2.0|间接依赖|npm|
|tiny-invariant|1.2.0|间接依赖|npm|
|com.alipay.sofa:rpc-grpc-impl|1.3.12|直接依赖|maven|
|commons-codec:commons-codec|1.15|直接依赖|maven|
|com.alibaba.nacos:nacos-address|2.3.0-SNAPSHOT|直接依赖|maven|
|org.springframework.boot:spring-boot-test|2.7.15|直接依赖|maven|
|react-transition-group|2.9.0|间接依赖|npm|
|com.alibaba.nacos:nacos-istio|2.3.0-SNAPSHOT|直接依赖|maven|
|com.alibaba.nacos:nacos-sys|2.3.0-SNAPSHOT|直接依赖|maven|
|io.prometheus:simpleclient_tracer_otel_agent|0.15.0|间接依赖|maven|
|regenerator-runtime|0.13.9|间接依赖|npm|
|org.springframework.boot:spring-boot-starter-aop|2.7.15|直接依赖|maven|
|js-tokens|4.0.0|间接依赖|npm|
|org.springframework:spring-aop|5.3.29|间接依赖|maven|
|@iarna/toml|3.0.0|间接依赖|npm|
|org.springframework:spring-jdbc|5.3.29|间接依赖|maven|
|com.alibaba.nacos:nacos-client|2.3.0-SNAPSHOT|直接依赖|maven|
|org.aspectj:aspectjweaver|1.9.7|间接依赖|maven|
|io.grpc:grpc-context|1.50.2|间接依赖|maven|
|follow-redirects|1.15.1|间接依赖|npm|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|tiny-warning|1.0.3|间接依赖|npm|
|org.slf4j:jul-to-slf4j|1.7.36|直接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.36|直接依赖|maven|
|ch.qos.logback:logback-classic|1.2.9|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.79|间接依赖|maven|
|com.alibaba.nacos:nacos-auth-plugin|2.3.0-SNAPSHOT|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-security|2.7.15|直接依赖|maven|
|csstype|3.1.0|间接依赖|npm|
|io.micrometer:micrometer-registry-prometheus|1.9.14|直接依赖|maven|
|org.springframework.security:spring-security-config|5.7.10|间接依赖|maven|
|lodash.clonedeep|4.5.0|间接依赖|npm|
|prop-types|15.8.1|间接依赖|npm|
|get-intrinsic|1.1.2|间接依赖|npm|
|org.springframework:spring-jcl|5.3.29|间接依赖|maven|
|classnames|2.3.1|间接依赖|npm|
|com.alibaba.nacos:nacos-api|2.3.0-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.12.6|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator|2.7.15|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.7.15|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|react|16.14.0|间接依赖|npm|
|org.springframework:spring-tx|5.3.29|间接依赖|maven|
|object-assign|4.1.1|间接依赖|npm|
|org.codehaus.mojo:animal-sniffer-annotations|1.21|间接依赖|maven|
|commons-io:commons-io|2.7|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.79|直接依赖|maven|
|moment|2.29.4|间接依赖|npm|
|react-is|17.0.2|间接依赖|npm|
|commons-lang:commons-lang|2.6|间接依赖|maven|
|resize-observer-polyfill|1.5.1|间接依赖|npm|
|argparse|2.0.1|间接依赖|npm|
|org.springframework:spring-webmvc|5.3.29|直接依赖|maven|
|core-js|2.6.12|间接依赖|npm|
|com.alibaba.nacos:nacos-console|2.3.0-SNAPSHOT|直接依赖|maven|
|resolve-pathname|3.0.0|间接依赖|npm|
|org.apache.logging.log4j:log4j-core|2.17.1|直接依赖|maven|
|org.jctools:jctools-core|2.1.1|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.1|直接依赖|maven|
|io.envoyproxy.controlplane:api|0.1.27|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.79|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-actuator|2.7.15|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.7.15|直接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|2.7.1|直接依赖|maven|
|dayjs|1.11.4|间接依赖|npm|
|org.springframework:spring-core|5.3.29|间接依赖|maven|
|net.java.dev.jna:jna|5.5.0|间接依赖|maven|
|js-yaml|4.1.0|间接依赖|npm|
|@alifd/validate|1.2.3|间接依赖|npm|
|org.springframework.boot:spring-boot-configuration-processor|2.7.15|直接依赖|maven|
|com.google.guava:guava|31.1-android|间接依赖|maven|
|com.alibaba.nacos:nacos-config-plugin|2.3.0-SNAPSHOT|直接依赖|maven|
|org.slf4j:log4j-over-slf4j|1.7.36|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.12.7.1|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.12.6|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.7.15|直接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|io.micrometer:micrometer-core|1.9.14|直接依赖|maven|
|com.caucho:hessian|4.0.63|直接依赖|maven|
|redux-thunk|2.4.1|间接依赖|npm|
|style-equal|1.0.0|间接依赖|npm|
|io.grpc:grpc-stub|1.50.2|直接依赖|maven|
|com.alibaba.nacos:nacos-encryption-plugin|2.3.0-SNAPSHOT|直接依赖|maven|
|ch.qos.logback:logback-core|1.2.9|直接依赖|maven|
|com.alibaba.nacos:nacos-config|2.3.0-SNAPSHOT|直接依赖|maven|
|react-is|16.13.1|间接依赖|npm|
|io.grpc:grpc-protobuf-lite|1.50.2|间接依赖|maven|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|org.springframework.security:spring-security-web|5.7.10|间接依赖|maven|
|org.ow2.asm:asm|6.0|间接依赖|maven|
|com.alibaba.nacos:nacos-contrl-plugin|2.3.0-SNAPSHOT|直接依赖|maven|
|object-inspect|1.12.2|间接依赖|npm|
|com.google.code.gson:gson|2.9.0|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|io.grpc:grpc-protobuf|1.50.2|直接依赖|maven|
|call-bind|1.0.2|间接依赖|npm|
|react-router-redux|4.0.8|间接依赖|npm|
|react-lifecycles-compat|3.0.4|间接依赖|npm|
|com.alibaba.nacos:nacos-prometheus|2.3.0-SNAPSHOT|直接依赖|maven|
|org.springframework:spring-web|5.3.29|间接依赖|maven|
|com.lmax:disruptor|3.3.7|间接依赖|maven|
|com.alibaba.nacos:nacos-trace-plugin|2.3.0-SNAPSHOT|直接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.16|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.15|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.5|间接依赖|maven|
|@alifd/theme-design-pro|0.8.0|间接依赖|npm|
|isarray|0.0.1|间接依赖|npm|
|org.apache.tomcat:tomcat-annotations-api|9.0.79|间接依赖|maven|
|com.alibaba.nacos:nacos-naming|2.3.0-SNAPSHOT|直接依赖|maven|
|mysql:mysql-connector-java|8.0.28|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.14|直接依赖|maven|
|react-router|5.3.3|间接依赖|npm|
|@types/react-redux|7.1.24|间接依赖|npm|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.7.15|间接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|hoist-non-react-statics|3.3.2|间接依赖|npm|
|org.codehaus.jackson:jackson-core-asl|1.9.13|直接依赖|maven|
|org.yaml:snakeyaml|2.0|直接依赖|maven|
|@types/react|18.0.15|间接依赖|npm|
|@alifd/field|1.5.8|间接依赖|npm|
|io.prometheus:simpleclient_common|0.15.0|间接依赖|maven|
|react-redux|7.2.8|间接依赖|npm|
|scheduler|0.19.1|间接依赖|npm|
|io.dropwizard.metrics:metrics-core|4.2.19|间接依赖|maven|
|@types/hoist-non-react-statics|3.3.1|间接依赖|npm|
|org.springframework:spring-beans|5.3.29|间接依赖|maven|
|com.alibaba.nacos:nacos-plugin-default-impl|2.3.0-SNAPSHOT|直接依赖|maven|
|loose-envify|1.4.0|间接依赖|npm|
|com.alibaba.nacos:nacos-consistency|2.3.0-SNAPSHOT|直接依赖|maven|
|function-bind|1.1.1|间接依赖|npm|
|com.alibaba.nacos:nacos-common|2.3.0-SNAPSHOT|直接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.2|间接依赖|maven|
|com.zaxxer:HikariCP|3.4.2|间接依赖|maven|
|org.rocksdb:rocksdbjni|7.7.3|间接依赖|maven|
|axios|0.21.4|间接依赖|npm|
|org.springframework:spring-expression|5.3.29|间接依赖|maven|
|com.alibaba.nacos:nacos-cmdb|2.3.0-SNAPSHOT|直接依赖|maven|
|mini-create-react-context|0.4.1|间接依赖|npm|
|io.micrometer:micrometer-registry-influx|1.9.14|直接依赖|maven|
|org.springframework.ldap:spring-ldap-core|2.4.1|直接依赖|maven|
|@types/scheduler|0.16.2|间接依赖|npm|
|com.alibaba.nacos:nacos-datasource-plugin|2.3.0-SNAPSHOT|直接依赖|maven|
|io.prometheus:simpleclient_tracer_otel|0.15.0|间接依赖|maven|
|babel-runtime|6.26.0|间接依赖|npm|
|dom-helpers|3.4.0|间接依赖|npm|
|org.springframework.boot:spring-boot-starter-tomcat|2.7.15|直接依赖|maven|
|@types/prop-types|15.7.5|间接依赖|npm|
|io.grpc:grpc-core|1.50.2|间接依赖|maven|
|io.prometheus:simpleclient_tracer_common|0.15.0|间接依赖|maven|
|org.springframework:spring-test|5.3.29|直接依赖|maven|
|react-dom|16.14.0|间接依赖|npm|
|@alifd/next|1.25.48|间接依赖|npm|
|com.alipay.sofa:jraft-core|1.3.12|直接依赖|maven|
|org.springframework.security:spring-security-core|5.7.10|间接依赖|maven|
|side-channel|1.0.4|间接依赖|npm|
|io.grpc:grpc-api|1.50.2|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.26|直接依赖|maven|
|value-equal|1.0.1|间接依赖|npm|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.5|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.14.0|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)