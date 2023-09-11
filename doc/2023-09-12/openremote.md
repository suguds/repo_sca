# openremote/openremote安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1701295743183929344.svg)](https://www.murphysec.com/console/report/1701295743108431872/1701295743183929344)

仓库描述：100% open-source IoT Platform - Integrate your devices, create rules, and analyse and visualise your data

仓库地址：[https://github.com/openremote/openremote](https://github.com/openremote/openremote)

| star：850 | watch：56 | fork：222 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-11 22:45:07 | 许可证：NOASSERTION |
| 最近检测时间：2023-09-12 02:24:03 | 组件总数：490 | 漏洞总数：41 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|keycloak  安全漏洞|使用基本弱点进行的认证绕过|[MPS-2021-1761](https://www.oscs1024.com/hd/MPS-2021-1761)|CVE-2020-14359|高危|
|Red Hat Keycloak 身份验证绕过漏洞|用户管理不正确|[MPS-2021-30695](https://www.oscs1024.com/hd/MPS-2021-30695)|CVE-2021-3754|中危|
|keycloak v7.4 存在身份管理不当漏洞|使用欺骗进行的认证绕过|[MPS-2021-7518](https://www.oscs1024.com/hd/MPS-2021-7518)|CVE-2021-3424|中危|
|JDOM 存在 XXE 注入漏洞|XXE|[MPS-2021-8350](https://www.oscs1024.com/hd/MPS-2021-8350)|CVE-2021-33813|高危|
|Red Hat XNIO 资源错误分配漏洞|不加限制或调节的资源分配|[MPS-2022-0191](https://www.oscs1024.com/hd/MPS-2022-0191)|CVE-2022-0084|高危|
|org.apache.commons:commons-dbcp2 存在信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-12024](https://www.oscs1024.com/hd/MPS-2022-12024)||低危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|Red Hat Keycloak 跨站脚本漏洞|XSS|[MPS-2022-1570](https://www.oscs1024.com/hd/MPS-2022-1570)|CVE-2022-0225|中危|
|Eclipse Californium 安全漏洞|不正确的行为次序：早期放大攻击|[MPS-2022-52744](https://www.oscs1024.com/hd/MPS-2022-52744)|CVE-2022-2576|高危|
|Bouncy Castle <1.69 认证绕过漏洞|密码学问题|[MPS-2022-54305](https://www.oscs1024.com/hd/MPS-2022-54305)||中危|
|Netty <4.1.86.Final 存在 CRLF 注入漏洞||[MPS-2022-58552](https://www.oscs1024.com/hd/MPS-2022-58552)|CVE-2022-41915|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
|Eclipse Californium 安全漏洞||[MPS-2022-64073](https://www.oscs1024.com/hd/MPS-2022-64073)|CVE-2022-39368|高危|
|TestNG <7.7.0  存在路径遍历（Zip Slip）漏洞|路径遍历|[MPS-2022-64736](https://www.oscs1024.com/hd/MPS-2022-64736)|CVE-2022-4065|高危|
|Red Hat Undertow 安全漏洞|证书验证不恰当|[MPS-2022-68061](https://www.oscs1024.com/hd/MPS-2022-68061)|CVE-2022-4492|高危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68515](https://www.oscs1024.com/hd/MPS-2022-68515)|CVE-2023-21930|高危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68522](https://www.oscs1024.com/hd/MPS-2022-68522)|CVE-2023-21937|低危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68523](https://www.oscs1024.com/hd/MPS-2022-68523)|CVE-2023-21938|低危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68524](https://www.oscs1024.com/hd/MPS-2022-68524)|CVE-2023-21939|中危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68539](https://www.oscs1024.com/hd/MPS-2022-68539)|CVE-2023-21954|中危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68552](https://www.oscs1024.com/hd/MPS-2022-68552)|CVE-2023-21967|中危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68553](https://www.oscs1024.com/hd/MPS-2022-68553)|CVE-2023-21968|低危|
|Oracle Java SE 安全漏洞||[MPS-2022-68591](https://www.oscs1024.com/hd/MPS-2022-68591)|CVE-2023-22006|低危|
|Oracle Java SE 安全漏洞||[MPS-2022-68621](https://www.oscs1024.com/hd/MPS-2022-68621)|CVE-2023-22036|低危|
|Oracle Java SE 安全漏洞||[MPS-2022-68626](https://www.oscs1024.com/hd/MPS-2022-68626)|CVE-2023-22041|中危|
|Oracle Java SE 安全漏洞||[MPS-2022-68629](https://www.oscs1024.com/hd/MPS-2022-68629)|CVE-2023-22044|低危|
|Oracle Java SE 安全漏洞||[MPS-2022-68630](https://www.oscs1024.com/hd/MPS-2022-68630)|CVE-2023-22045|低危|
|Oracle Java SE 安全漏洞||[MPS-2022-68634](https://www.oscs1024.com/hd/MPS-2022-68634)|CVE-2023-22049|低危|
|Red Hat Undertow 资源管理错误漏洞|拒绝服务|[MPS-2022-7892](https://www.oscs1024.com/hd/MPS-2022-7892)|CVE-2022-1259|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Red Hat Keycloak 安全漏洞|授权检查错误|[MPS-2023-0330](https://www.oscs1024.com/hd/MPS-2023-0330)|CVE-2023-0091|低危|
|Red Hat Keycloak 授权问题漏洞|身份验证不当|[MPS-2023-0550](https://www.oscs1024.com/hd/MPS-2023-0550)|CVE-2023-0105|中危|
|Resteasy 安全漏洞|输入验证不恰当|[MPS-2023-2844](https://www.oscs1024.com/hd/MPS-2023-2844)|CVE-2023-0482|中危|
|netplex json-smart 安全漏洞|未经控制的递归|[MPS-2023-7760](https://www.oscs1024.com/hd/MPS-2023-7760)|CVE-2023-1370|高危|
|Red Hat Keycloak 信任管理问题漏洞|证书验证不恰当|[MPS-2023-8960](https://www.oscs1024.com/hd/MPS-2023-8960)|CVE-2023-1664|中危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|fasterxml jackson-dataformats-text越界写入漏洞|越界写入|[MPS-f9vd-7lu8](https://www.oscs1024.com/hd/MPS-f9vd-7lu8)|CVE-2023-3894|高危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|
|SQLite JDBC 远程代码执行漏洞|代码注入|[MPS-zprx-hdwf](https://www.oscs1024.com/hd/MPS-zprx-hdwf)|CVE-2023-32697|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.eclipse.californium:element-connector|3.5.0|3.7.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|net.minidev:json-smart|2.4.7|2.4.9|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.33|2.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.eclipse.californium:californium-core|2.1.0|3.6.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.4|2.14.0-rc1|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.keycloak:keycloak-core|18.0.2|22.0.1|直接依赖|建议修复|C:0|H:1|M:5|L:1|
|io.undertow:undertow-core|2.3.4.Final|2.3.6.final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|io.netty:netty-handler|4.1.79.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.graalvm.sdk:graal-sdk|22.3.1|22.3.3|直接依赖|建议修复|C:0|H:1|M:4|L:8|
|org.xerial:sqlite-jdbc|3.34.0|3.41.2.2|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.93.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.eclipse.californium:scandium|3.5.0|3.7.0|直接依赖|建议修复|C:0|H:2|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.14.3||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.jboss.resteasy:resteasy-core|6.2.2.Final||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.testng:testng|7.5|7.7.0|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|io.netty:netty-codec-http|4.1.79.Final|4.1.86.final|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.jdom:jdom2|2.0.6|2.0.6.1|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.dataformat:jackson-dataformat-toml|2.14.3|2.15.0|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.bouncycastle:bcprov-jdk15on|1.68|1.69|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|31.1-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.jboss.xnio:xnio-api|3.8.8.Final|3.8.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.commons:commons-dbcp2|2.7.0|2.9.0|间接依赖|可选修复|C:0|H:0|M:0|L:1|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|292|Low|
|自定义许可证|54|Low|
|MPL-2.0|1|Low|
|LGPL-2.1-or-later|4|Low|
|LGPL-2.1|4|Medium|
|EPL-1.0|3|Low|
|EPL-2.0|26|Low|
|BSD-3-Clause|11|Low|
|MIT|17|Low|
|CDDL-1.0|1|Low|
|LGPL-3.0-or-later|4|Low|
|MPL-1.1|1|Low|
|WTFPL|1|Low|
|JSON|1|Low|
|Zlib|1|Low|
|UPL-1.0|5|Low|
|CDDL-1.1|2|Low|
|BSD-2-Clause|2|Low|
|GPL-2.0-with-classpath-exception|1|Medium|
|MIT-0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.google.api.grpc:proto-google-common-protos|2.9.6|间接依赖|maven|
|org.apache.camel:camel-ref|3.20.6|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|2.1.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.14.3|间接依赖|maven|
|io.grpc:grpc-googleapis|1.50.1|间接依赖|maven|
|com.google.api.grpc:proto-google-cloud-firestore-v1|3.7.0|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.14|间接依赖|maven|
|org.wildfly.common:wildfly-common|1.5.4.Final|间接依赖|maven|
|com.google.http-client:google-http-client|1.42.2|间接依赖|maven|
|net.sf.saxon:Saxon-HE|11.3|直接依赖|maven|
|org.apache.camel:camel-rest|3.20.6|间接依赖|maven|
|org.eclipse.angus:angus-activation|2.0.0|间接依赖|maven|
|org.jboss:jandex|2.4.2.Final|间接依赖|maven|
|MaterialComponents/private/Color|124.2.0|间接依赖|cocoapods|
|org.glassfish.jaxb:jaxb-runtime|3.0.2|间接依赖|maven|
|org.apache.camel:camel-support|3.20.6|间接依赖|maven|
|com.github.calimero:calimero-core|2.4|直接依赖|maven|
|io.grpc:grpc-context|1.50.1|间接依赖|maven|
|com.fasterxml.jackson.jakarta.rs:jackson-jakarta-rs-base|2.14.3|间接依赖|maven|
|org.codehaus.groovy:groovy|3.0.10|间接依赖|maven|
|org.codehaus.groovy:groovy-test-junit5|3.0.10|间接依赖|maven|
|org.apache.camel:camel-health|3.20.6|直接依赖|maven|
|org.apache.camel:camel-jackson|3.20.6|直接依赖|maven|
|org.apache.activemq:artemis-jdbc-store|2.29.0|间接依赖|maven|
|MaterialComponents/Ripple|124.2.0|间接依赖|cocoapods|
|org.apache.camel:camel-base|3.20.6|间接依赖|maven|
|MaterialComponents/ShapeLibrary|124.2.0|间接依赖|cocoapods|
|org.apache.camel:camel-cloud|3.20.6|间接依赖|maven|
|org.apache.ant:ant-launcher|1.10.12|间接依赖|maven|
|com.fasterxml.uuid:java-uuid-generator|4.0.1|直接依赖|maven|
|::container||直接依赖|maven|
|org.apache.camel:camel-controlbus|3.20.6|间接依赖|maven|
|MaterialComponents/Typography|124.2.0|间接依赖|cocoapods|
|org.apache.httpcomponents:httpcore|4.4.16|间接依赖|maven|
|FirebaseCoreDiagnostics|8.11.0|间接依赖|cocoapods|
|MaterialComponents/Palettes|124.2.0|间接依赖|cocoapods|
|io.grpc:grpc-api|1.50.1|间接依赖|maven|
|org.apache.camel:camel-log|3.20.6|间接依赖|maven|
|org.glassfish.jaxb:codemodel|4.0.1|间接依赖|maven|
|org.hibernate.orm:hibernate-core|6.1.7.Final|直接依赖|maven|
|jakarta.validation:jakarta.validation-api|3.0.2|间接依赖|maven|
|org.apache.camel:camel-seda|3.20.6|间接依赖|maven|
|org.codehaus.groovy:groovy-sql|3.0.10|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.14.3|直接依赖|maven|
|org.codehaus.groovy:groovy-datetime|3.0.10|间接依赖|maven|
|net.sf.flexjson:flexjson|2.1|间接依赖|maven|
|commons-digester:commons-digester|2.1|间接依赖|maven|
|org.codehaus.groovy:groovy-dateutil|3.0.10|间接依赖|maven|
|io.grpc:grpc-grpclb|1.50.1|间接依赖|maven|
|org.ejml:ejml-core|0.32|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.93.Final|间接依赖|maven|
|com.mchange:mchange-commons-java|0.2.15|间接依赖|maven|
|io.opencensus:opencensus-contrib-grpc-util|0.31.1|间接依赖|maven|
|GoogleUtilities/Logger|7.7.0|间接依赖|cocoapods|
|com.google.api.grpc:gapic-google-cloud-storage-v2|2.14.0-alpha|间接依赖|maven|
|org.apache.activemq:artemis-commons|2.29.0|间接依赖|maven|
|org.apache.camel:camel-core-processor|3.20.6|间接依赖|maven|
|GoogleUtilities/MethodSwizzler|7.7.0|间接依赖|cocoapods|
|org.jetbrains.kotlin:kotlin-stdlib|1.8.10|直接依赖|maven|
|jakarta.json.bind:jakarta.json.bind-api|3.0.0|直接依赖|maven|
|javax.ws.rs:javax.ws.rs-api|2.1.1|直接依赖|maven|
|commons-validator:commons-validator|1.7|间接依赖|maven|
|org.eclipse.californium:element-connector|3.5.0|间接依赖|maven|
|org.jparsec:jparsec|3.1|间接依赖|maven|
|org.codehaus.groovy:groovy-groovysh|3.0.10|间接依赖|maven|
|org.threeten:threetenbp|1.6.3|间接依赖|maven|
|com.devskiller.friendly-id:friendly-id|1.0.1|直接依赖|maven|
|org.codehaus.groovy:groovy-xml|3.0.10|间接依赖|maven|
|org.apache.camel:camel-api|3.20.6|间接依赖|maven|
|jakarta.mail:jakarta.mail-api|2.1.1|间接依赖|maven|
|org.usb4java:usb4java|1.3.0|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|MDFTextAccessibility|2.0.1|间接依赖|cocoapods|
|javax.xml.stream:stax-api|1.0-2|间接依赖|maven|
|com.sun.xml.bind.external:relaxng-datatype|4.0.1|间接依赖|maven|
|FirebaseCrashlytics|8.11.0|间接依赖|cocoapods|
|javax.media:jai||间接依赖|maven|
|::model||直接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.18|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.4|直接依赖|maven|
|com.github.java-json-tools:json-patch|1.13|间接依赖|maven|
|org.geotools:gt-opengis|19.1|间接依赖|maven|
|org.apache.camel:camel-snmp|3.20.6|直接依赖|maven|
|org.codehaus.groovy:groovy-macro|3.0.10|间接依赖|maven|
|javax.cache:cache-api|1.1.1|间接依赖|maven|
|org.eclipse.angus:angus-mail|1.0.0|间接依赖|maven|
|MaterialComponents/Ink|124.2.0|间接依赖|cocoapods|
|org.apache.ant:ant|1.10.12|间接依赖|maven|
|org.eclipse.angus:angus-activation|1.0.0|间接依赖|maven|
|javax.json.bind:javax.json.bind-api|1.0|直接依赖|maven|
|org.codehaus.groovy:groovy-cli-picocli|3.0.10|间接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|直接依赖|maven|
|GoogleUtilities/AppDelegateSwizzler|7.7.0|间接依赖|cocoapods|
|Firebase/Crashlytics|8.11.0|间接依赖|cocoapods|
|io.micrometer:micrometer-commons|1.11.0|直接依赖|maven|
|com.google.dagger:dagger|2.27|间接依赖|maven|
|org.apache.camel:camel-vm|3.20.6|间接依赖|maven|
|org.apache.camel:camel-core|3.20.6|直接依赖|maven|
|javax.json:javax.json-api|1.1.4|直接依赖|maven|
|org.jboss.resteasy:resteasy-client-api|6.2.2.Final|间接依赖|maven|
|junit:junit|4.13.2|间接依赖|maven|
|org.jboss.xnio:xnio-nio|3.8.8.Final|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|2.1.0|间接依赖|maven|
|io.grpc:grpc-xds|1.50.1|间接依赖|maven|
|org.jgroups:jgroups|5.2.0.Final|间接依赖|maven|
|MaterialComponents/ShadowLayer|124.2.0|间接依赖|cocoapods|
|org.jctools:jctools-core|2.1.2|间接依赖|maven|
|MaterialComponents/private/Math|124.2.0|间接依赖|cocoapods|
|com.fasterxml.jackson.core:jackson-databind|2.13.4|直接依赖|maven|
|org.apache.camel:camel-language|3.20.6|间接依赖|maven|
|io.netty:netty-buffer|4.1.93.Final|间接依赖|maven|
|info.picocli:picocli|4.6.1|间接依赖|maven|
|org.glassfish:jakarta.el|4.0.2|直接依赖|maven|
|org.ow2.asm:asm-tree|7.3.1|间接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|4.0.1|直接依赖|maven|
|org.codehaus.groovy:groovy-json|3.0.10|间接依赖|maven|
|com.google.cloud:google-cloud-storage|2.14.0|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.79.Final|间接依赖|maven|
|jgridshift:jgridshift|1.0|间接依赖|maven|
|com.sun.activation:jakarta.activation|1.2.2|间接依赖|maven|
|com.sun.istack:istack-commons-tools|4.1.1|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-engine|5.8.2|间接依赖|maven|
|org.jboss.resteasy:resteasy-validator-provider|6.2.2.Final|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jakarta-xmlbind-annotations|2.14.3|直接依赖|maven|
|org.xerial:sqlite-jdbc|3.34.0|直接依赖|maven|
|io.grpc:grpc-stub|1.50.1|间接依赖|maven|
|org.apache.camel:camel-xml-jaxb|3.20.6|间接依赖|maven|
|io.swagger.core.v3:swagger-jaxrs2-jakarta|2.2.8|直接依赖|maven|
|com.hivemq:hivemq-mqtt-client|1.2.2|直接依赖|maven|
|org.glassfish.jaxb:xsom|4.0.1|间接依赖|maven|
|org.apache.camel:camel-bean|3.20.6|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|org.glassfish.jaxb:jaxb-core|4.0.1|间接依赖|maven|
|org.usb4java:usb4java-javax|1.3.0|间接依赖|maven|
|org.ejml:ejml-ddense|0.32|间接依赖|maven|
|io.netty:netty-resolver|4.1.79.Final|间接依赖|maven|
|com.vladmihalcea:hibernate-types-60|2.21.1|直接依赖|maven|
|org.keycloak:keycloak-core|18.0.2|直接依赖|maven|
|com.google.api.grpc:proto-google-cloud-storage-v2|2.14.0-alpha|间接依赖|maven|
|org.apache.camel:camel-dataset|3.20.6|间接依赖|maven|
|io.grpc:grpc-auth|1.50.1|间接依赖|maven|
|io.netty:netty-transport|4.1.93.Final|间接依赖|maven|
|org.checkerframework:checker-qual|3.31.0|间接依赖|maven|
|com.google.re2j:re2j|1.6|间接依赖|maven|
|org.apache.camel:camel-validator|3.20.6|间接依赖|maven|
|Firebase/Messaging|8.11.0|间接依赖|cocoapods|
|org.slf4j:slf4j-api|1.7.36|间接依赖|maven|
|nanopb/encode|2.30908.0|间接依赖|cocoapods|
|net.java.dev.jsr-275:jsr-275|1.0-beta-2|间接依赖|maven|
|org.glassfish.jaxb:txw2|3.0.2|间接依赖|maven|
|org.testng:testng|7.5|间接依赖|maven|
|org.shredzone.commons:commons-suncalc|3.5|直接依赖|maven|
|io.grpc:grpc-services|1.50.1|间接依赖|maven|
|com.fasterxml.jackson:jackson-bom|2.14.3|间接依赖|maven|
|MaterialComponents/AnimationTiming|124.2.0|间接依赖|cocoapods|
|org.craftercms:groovy-sandbox|4.0.0|直接依赖|maven|
|org.openremote:or-commons|0.1.0|间接依赖|maven|
|org.ow2.asm:asm-util|7.3.1|间接依赖|maven|
|io.github.classgraph:classgraph|4.8.157|直接依赖|maven|
|org.scala-lang:scala-library|2.12.10|直接依赖|maven|
|org.apache.commons:commons-dbcp2|2.7.0|间接依赖|maven|
|org.apache.commons:commons-pool2|2.7.0|间接依赖|maven|
|org.antlr:antlr4-runtime|4.10.1|间接依赖|maven|
|com.google.api-client:google-api-client-gson|2.0.0|间接依赖|maven|
|org.glassfish.jaxb:jaxb-core|3.0.2|间接依赖|maven|
|org.apache.activemq:activemq-artemis-native|2.0.0|间接依赖|maven|
|org.codehaus.groovy:groovy-templates|3.0.10|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.21.8|间接依赖|maven|
|io.github.classgraph:classgraph|4.8.149|直接依赖|maven|
|org.jeasy:easy-rules-core|4.1.0|直接依赖|maven|
|com.google.apis:google-api-services-storage|v1-rev20220705-2.0.0|间接依赖|maven|
|org.codehaus.groovy:groovy-all|3.0.10|直接依赖|maven|
|GoogleUtilities/Reachability|7.7.0|间接依赖|cocoapods|
|org.usb4java:libusb4java|1.3.0|间接依赖|maven|
|org.apache.camel:camel-http-base|3.20.6|间接依赖|maven|
|joda-time:joda-time|2.10.2|间接依赖|maven|
|org.javassist:javassist|3.26.0-GA|间接依赖|maven|
|org.geotools:gt-metadata|19.1|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.93.Final|间接依赖|maven|
|jakarta.inject:jakarta.inject-api|2.0.0|间接依赖|maven|
|org.reflections:reflections|0.9.12|直接依赖|maven|
|GoogleDataTransport|9.1.2|间接依赖|cocoapods|
|io.grpc:grpc-netty-shaded|1.50.1|间接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.68|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.93.Final|间接依赖|maven|
|GoogleAppMeasurement|8.11.0|间接依赖|cocoapods|
|io.opencensus:opencensus-contrib-http-util|0.31.1|间接依赖|maven|
|io.micrometer:micrometer-registry-prometheus|1.11.0|直接依赖|maven|
|io.undertow:undertow-websockets-jsr|2.3.4.Final|直接依赖|maven|
|org.apache.camel:camel-management|3.20.6|直接依赖|maven|
|org.codehaus.groovy:groovy-swing|3.0.10|间接依赖|maven|
|org.apache.servicemix.bundles:org.apache.servicemix.bundles.snmp4j|2.6.3|间接依赖|maven|
|org.apache.camel:camel-direct|3.20.6|间接依赖|maven|
|commons-io:commons-io|2.11.0|间接依赖|maven|
|jakarta.transaction:jakarta.transaction-api|2.0.0|间接依赖|maven|
|com.github.java-json-tools:msg-simple|1.2|间接依赖|maven|
|com.google.errorprone:error||间接依赖|maven|
|io.netty:netty-resolver|4.1.93.Final|间接依赖|maven|
|org.apache.camel:camel-saga|3.20.6|间接依赖|maven|
|io.opencensus:opencensus-proto|0.2.0|间接依赖|maven|
|jakarta.json:jakarta.json-api|2.0.1|直接依赖|maven|
|org.jboss.resteasy:resteasy-jaxb-provider|6.2.2.Final|间接依赖|maven|
|org.opentest4j:opentest4j|1.2.0|间接依赖|maven|
|org.eclipse.angus:angus-mail|2.0.1|直接依赖|maven|
|org.apache.camel:camel-dataformat|3.20.6|间接依赖|maven|
|::agent||直接依赖|maven|
|com.sun.xml.bind:jaxb-core|2.3.0|间接依赖|maven|
|com.google.api:gax-httpjson|0.104.4|间接依赖|maven|
|org.junit.platform:junit-platform-engine|1.8.2|间接依赖|maven|
|com.github.javaparser:javaparser-core|3.24.0|间接依赖|maven|
|::ui:component:model||直接依赖|maven|
|org.apache.camel:camel-attachments|3.20.6|间接依赖|maven|
|org.slf4j:log4j-over-slf4j|2.0.6|直接依赖|maven|
|com.sun.istack:istack-commons-runtime|4.1.1|间接依赖|maven|
|org.apache.camel:camel-core-model|3.20.6|间接依赖|maven|
|org.apache.camel:camel-cluster|3.20.6|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.8.10|间接依赖|maven|
|io.swagger.core.v3:swagger-annotations-jakarta|2.2.8|间接依赖|maven|
|org.codehaus.groovy:groovy-servlet|3.0.10|间接依赖|maven|
|org.codehaus.groovy:groovy-console|3.0.10|间接依赖|maven|
|org.eclipse.californium:californium-core|2.1.0|直接依赖|maven|
|io.reactivex.rxjava2:rxjava|2.2.19|间接依赖|maven|
|org.checkerframework:checker-qual|3.12.0|间接依赖|maven|
|MaterialComponents/Availability|124.2.0|间接依赖|cocoapods|
|org.slf4j:slf4j-jdk14|2.0.6|直接依赖|maven|
|xml-apis:xml-apis|1.4.01|间接依赖|maven|
|org.xmlresolver:xmlresolver|4.2.0|间接依赖|maven|
|:No dependencies||直接依赖|maven|
|org.threeten:threeten-extra|1.7.0|间接依赖|maven|
|io.netty:netty-codec-http|4.1.79.Final|直接依赖|maven|
|com.damnhandy:handy-uri-templates|2.1.8|间接依赖|maven|
|org.jboss.resteasy:resteasy-undertow|6.2.2.Final|直接依赖|maven|
|io.undertow:undertow-core|2.3.4.Final|间接依赖|maven|
|com.github.weliem:blessed-bluez|0.39|直接依赖|maven|
|org.geotools:gt-api|19.1|间接依赖|maven|
|org.keycloak:keycloak-admin-client-jakarta|18.0.2|直接依赖|maven|
|org.apache.camel:camel-util|3.20.6|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.4|直接依赖|maven|
|MaterialComponents/TextFields|124.2.0|间接依赖|cocoapods|
|io.swagger.core.v3:swagger-integration-jakarta|2.2.8|间接依赖|maven|
|org.jboss.xnio:xnio-api|3.8.8.Final|间接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|com.sun.xml.bind.external:rngom|4.0.1|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.5.0.Final|间接依赖|maven|
|org.apache.camel:camel-timer|3.20.6|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|3.0.1|间接依赖|maven|
|org.eclipse.californium:californium-legal|3.5.0|间接依赖|maven|
|io.netty:netty-handler|4.1.79.Final|间接依赖|maven|
|org.hibernate.orm:hibernate-hikaricp|6.1.7.Final|直接依赖|maven|
|org.apache.camel:camel-directvm|3.20.6|间接依赖|maven|
|org.apache.commons:commons-text|1.10.0|间接依赖|maven|
|io.prometheus:simpleclient|0.16.0|直接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|org.apache.camel:camel-xpath|3.20.6|间接依赖|maven|
|FirebaseMessaging|8.11.0|间接依赖|cocoapods|
|org.keycloak:keycloak-client-registration-api|18.0.2|直接依赖|maven|
|FirebaseAnalytics|8.11.0|间接依赖|cocoapods|
|net.minidev:accessors-smart|2.4.7|间接依赖|maven|
|org.hibernate:hibernate-core|6.1.7.Final|直接依赖|maven|
|com.google.cloud:google-cloud-firestore|3.7.0|间接依赖|maven|
|DropDown|2.3.13|间接依赖|cocoapods|
|io.grpc:grpc-alts|1.50.1|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.93.Final|间接依赖|maven|
|org.apache.ant:ant-junit|1.10.12|间接依赖|maven|
|nanopb/decode|2.30908.0|间接依赖|cocoapods|
|com.fasterxml.jackson:jackson-bom|2.13.4|间接依赖|maven|
|jakarta.websocket:jakarta.websocket-client-api|2.1.0|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.22|间接依赖|maven|
|org.ow2.asm:asm|9.1|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|org.codehaus.groovy:groovy-ant|3.0.10|间接依赖|maven|
|org.junit:junit-bom|5.8.2|间接依赖|maven|
|org.jboss.resteasy:resteasy-jackson2-provider|6.2.2.Final|直接依赖|maven|
|com.google.api:gax-grpc|2.19.4|间接依赖|maven|
|PromisesObjC|2.0.0|间接依赖|cocoapods|
|com.google.api.grpc:proto-google-iam-v1|1.6.4|间接依赖|maven|
|org.threeten:threetenbp|1.3.6|间接依赖|maven|
|com.google.guava:guava|31.1-jre|直接依赖|maven|
|org.hibernate.validator:hibernate-validator|8.0.0.Final|直接依赖|maven|
|org.ow2.asm:asm-analysis|7.3.1|间接依赖|maven|
|io.netty:netty-common|4.1.79.Final|间接依赖|maven|
|org.jboss.logging:jboss-logging-annotations|2.0.2.Final|直接依赖|maven|
|org.apache.camel:camel-core-engine|3.20.6|间接依赖|maven|
|org.keycloak:keycloak-common|18.0.2|间接依赖|maven|
|cz.habarta.typescript-generator:typescript-generator-core|3.2.1263|直接依赖|maven|
|jakarta.mail:jakarta.mail-api|2.1.0|间接依赖|maven|
|javax.usb:usb-api|1.0.2|间接依赖|maven|
|org.glassfish.jaxb:jaxb-jxc|4.0.1|间接依赖|maven|
|com.ibm.async:asyncutil|0.1.0|间接依赖|maven|
|GoogleUtilities/Network|7.7.0|间接依赖|cocoapods|
|org.jboss.resteasy:resteasy-client|6.2.2.Final|直接依赖|maven|
|org.apache.ant:ant-antlr|1.10.12|间接依赖|maven|
|org.glassfish.jaxb:txw2|4.0.1|间接依赖|maven|
|MaterialComponents/Shapes|124.2.0|间接依赖|cocoapods|
|com.zaxxer:HikariCP|5.0.1|直接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|间接依赖|maven|
|jakarta.servlet:jakarta.servlet-api|6.0.0|间接依赖|maven|
|MaterialComponents/Buttons|124.2.0|间接依赖|cocoapods|
|jakarta.xml.bind:jakarta.xml.bind-api|4.0.0|间接依赖|maven|
|org.apache.activemq:artemis-server|2.29.0|直接依赖|maven|
|org.json:json|20220320|间接依赖|maven|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|org.yaml:snakeyaml|1.33|间接依赖|maven|
|org.apache.camel:camel-mock|3.20.6|间接依赖|maven|
|jakarta.el:jakarta.el-api|5.0.1|直接依赖|maven|
|com.github.calimero:calimero-tools|2.4|直接依赖|maven|
|io.perfmark:perfmark-api|0.25.0|间接依赖|maven|
|net.sf.geographiclib:GeographicLib-Java|1.44|间接依赖|maven|
|org.openremote:or-zwave|3.4.0-SNAPSHOT|直接依赖|maven|
|io.micrometer:micrometer-observation|1.11.0|直接依赖|maven|
|org.apache.camel:camel-management-api|3.20.6|间接依赖|maven|
|org.apache.activemq:artemis-quorum-api|2.29.0|间接依赖|maven|
|net.minidev:json-smart|2.4.7|间接依赖|maven|
|io.netty:netty-codec|4.1.93.Final|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.93.Final|间接依赖|maven|
|com.google.protobuf:protobuf-java-util|3.21.8|间接依赖|maven|
|io.github.classgraph:classgraph|4.8.150|间接依赖|maven|
|com.github.java-json-tools:jackson-coreutils|2.0|间接依赖|maven|
|io.undertow:undertow-servlet|2.3.4.Final|直接依赖|maven|
|com.google.http-client:google-http-client-apache-v2|1.42.2|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.14.3|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-toml|2.14.3|间接依赖|maven|
|MaterialComponents/private/Application|124.2.0|间接依赖|cocoapods|
|jakarta.persistence:jakarta.persistence-api|3.0.0|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.14.3|间接依赖|maven|
|org.apache.camel:camel-tooling-model|3.20.6|间接依赖|maven|
|org.codehaus.groovy:groovy-astbuilder|3.0.10|间接依赖|maven|
|commons-pool:commons-pool|1.5.4|间接依赖|maven|
|io.swagger.core.v3:swagger-annotations|2.2.8|直接依赖|maven|
|org.keycloak:keycloak-adapter-core|18.0.2|直接依赖|maven|
|com.google.api-client:google-api-client|2.0.0|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.93.Final|间接依赖|maven|
|com.google.api.grpc:grpc-google-cloud-storage-v2|2.14.0-alpha|间接依赖|maven|
|::manager||直接依赖|maven|
|org.apache.activemq:artemis-selector|2.29.0|间接依赖|maven|
|nanopb|2.30908.0|间接依赖|cocoapods|
|org.bouncycastle:bcprov-jdk15on|1.68|间接依赖|maven|
|org.openjdk.nashorn:nashorn-core|15.3|直接依赖|maven|
|org.apache.activemq:artemis-mqtt-protocol|2.29.0|直接依赖|maven|
|io.grpc:grpc-core|1.50.1|间接依赖|maven|
|com.google.auth:google-auth-library-oauth2-http|1.12.1|间接依赖|maven|
|org.codehaus.groovy:groovy-jsr223|3.0.10|间接依赖|maven|
|com.google.cloud:google-cloud-core|2.8.22|间接依赖|maven|
|com.sun.activation:jakarta.activation|2.0.1|间接依赖|maven|
|Firebase/Analytics|8.11.0|间接依赖|cocoapods|
|org.codehaus.groovy:groovy-nio|3.0.10|间接依赖|maven|
|FirebaseCore|8.11.0|间接依赖|cocoapods|
|org.apache.camel:camel-undertow|3.20.6|直接依赖|maven|
|io.swagger.core.v3:swagger-models-jakarta|2.2.8|间接依赖|maven|
|org.apache.activemq:artemis-journal|2.29.0|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.3.Final|间接依赖|maven|
|org.ow2.asm:asm-commons|7.3.1|间接依赖|maven|
|org.flywaydb:flyway-core|9.15.1|直接依赖|maven|
|org.jboss.resteasy:resteasy-multipart-provider|6.2.2.Final|直接依赖|maven|
|com.zaxxer:HikariCP-java7|2.4.13|间接依赖|maven|
|org.jdom:jdom2|2.0.6|间接依赖|maven|
|FirebaseInstallations|8.11.0|间接依赖|cocoapods|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.14.3|直接依赖|maven|
|org.graalvm.sdk:graal-sdk|22.3.1|直接依赖|maven|
|io.netty:netty-codec-mqtt|4.1.79.Final|直接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|Firebase/Core|8.11.0|间接依赖|cocoapods|
|jakarta.annotation:jakarta.annotation-api|2.1.1|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-reflect|1.8.10|直接依赖|maven|
|org.apache.camel:camel-core-languages|3.20.6|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|org.jetbrains:annotations|24.0.1|直接依赖|maven|
|org.apache.james:apache-mime4j-storage|0.8.8|间接依赖|maven|
|dev.failsafe:failsafe|3.1.0|直接依赖|maven|
|io.grpc:grpc-protobuf|1.50.1|间接依赖|maven|
|com.sun.activation:javax.activation|1.2.0|间接依赖|maven|
|org.apache.camel:camel-util-json|3.20.6|间接依赖|maven|
|io.opencensus:opencensus-api|0.31.1|间接依赖|maven|
|com.vividsolutions:jts-core|1.14.0|间接依赖|maven|
|com.jayway.jsonpath:json-path|2.7.0|直接依赖|maven|
|jdom:jdom|1.0|间接依赖|maven|
|com.fasterxml.jackson.jakarta.rs:jackson-jakarta-rs-json-provider|2.14.3|间接依赖|maven|
|com.github.java-json-tools:btf|1.3|间接依赖|maven|
|io.netty:netty-codec|4.1.79.Final|直接依赖|maven|
|com.mchange:c3p0|0.9.5.4|间接依赖|maven|
|org.codehaus.groovy:groovy-docgenerator|3.0.10|间接依赖|maven|
|com.google.cloud:google-cloud-core-http|2.8.22|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|直接依赖|maven|
|com.github.richturner:mbknor-jackson-jsonschema|1.0.40-JAKARTA|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.14.3|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.4|间接依赖|maven|
|org.webjars:jquery|3.5.1|间接依赖|maven|
|io.netty:netty-handler|4.1.93.Final|间接依赖|maven|
|com.github.erosb:everit-json-schema|1.14.1|间接依赖|maven|
|org.postgresql:postgresql|42.6.0|直接依赖|maven|
|org.apache.camel:camel-base-engine|3.20.6|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|直接依赖|maven|
|com.google.firebase:firebase-admin|9.1.1|直接依赖|maven|
|org.eclipse.californium:scandium|3.5.0|直接依赖|maven|
|com.thoughtworks.qdox:qdox|1.12.1|间接依赖|maven|
|MDFInternationalization|3.0.0|间接依赖|cocoapods|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|jakarta.websocket:jakarta.websocket-api|2.1.0|间接依赖|maven|
|com.sun.istack:istack-commons-runtime|4.0.1|间接依赖|maven|
|IQKeyboardManagerSwift|6.5.9|间接依赖|cocoapods|
|com.google.code.gson:gson|2.10.1|直接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.0|间接依赖|maven|
|org.apache.camel:camel-browse|3.20.6|间接依赖|maven|
|org.slf4j:slf4j-api|2.0.6|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.14.3|直接依赖|maven|
|org.geotools:gt-referencing|19.1|间接依赖|maven|
|org.codehaus.groovy:groovy-jmx|3.0.10|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|间接依赖|maven|
|org.jboss.resteasy:resteasy-core-spi|6.2.2.Final|间接依赖|maven|
|org.apache.camel:camel-core-reifier|3.20.6|间接依赖|maven|
|org.wildfly.client:wildfly-client-config|1.0.1.Final|间接依赖|maven|
|GoogleUtilities/NSData||间接依赖|cocoapods|
|io.grpc:grpc-protobuf-lite|1.50.1|间接依赖|maven|
|org.conscrypt:conscrypt-openjdk-uber|2.5.2|间接依赖|maven|
|org.apache.james:apache-mime4j-core|0.8.8|间接依赖|maven|
|io.netty:netty-buffer|4.1.79.Final|间接依赖|maven|
|io.netty:netty-transport|4.1.79.Final|间接依赖|maven|
|jline:jline|2.14.6|间接依赖|maven|
|MaterialComponents/ShadowElevations|124.2.0|间接依赖|cocoapods|
|org.apache.camel:camel-xml-jaxp|3.20.6|间接依赖|maven|
|jakarta.ws.rs:jakarta.ws.rs-api|3.1.0|直接依赖|maven|
|org.openremote:or-controller|1.5.0-pro|间接依赖|maven|
|FirebaseAnalytics/AdIdSupport|8.11.0|间接依赖|cocoapods|
|org.apache.activemq:artemis-core-client|2.29.0|间接依赖|maven|
|GoogleAppMeasurement/AdIdSupport|8.11.0|间接依赖|cocoapods|
|com.google.api:api-common|2.2.1|间接依赖|maven|
|org.graalvm.js:js|22.3.1|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.14.3|间接依赖|maven|
|MaterialComponents/Shadow|124.2.0|间接依赖|cocoapods|
|org.apache.commons:commons-configuration2|2.8.0|间接依赖|maven|
|org.geotools:gt-main|19.1|直接依赖|maven|
|io.swagger.core.v3:swagger-core-jakarta|2.2.8|间接依赖|maven|
|org.codehaus.groovy:groovy-test|3.0.10|间接依赖|maven|
|com.google.http-client:google-http-client-appengine|1.42.2|间接依赖|maven|
|org.apache.camel:camel-xml-io-util|3.20.6|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.4|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|com.google.api:gax|2.19.4|间接依赖|maven|
|org.graalvm.js:js-scriptengine|22.3.1|直接依赖|maven|
|com.beust:jcommander|1.78|间接依赖|maven|
|com.google.auto.value:auto-value-annotations|1.10|间接依赖|maven|
|org.mnode.ical4j:ical4j|3.2.6|直接依赖|maven|
|org.glassfish.jaxb:jaxb-xjc|4.0.1|间接依赖|maven|
|org.apache.commons:commons-collections4|4.4|间接依赖|maven|
|org.graalvm.truffle:truffle-api|22.3.1|间接依赖|maven|
|GoogleUtilities/Environment|7.7.0|间接依赖|cocoapods|
|Firebase/CoreOnly|8.11.0|间接依赖|cocoapods|
|com.google.oauth-client:google-oauth-client|1.34.1|间接依赖|maven|
|com.ibm.icu:icu4j|71.1|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-api|5.8.2|间接依赖|maven|
|::setup||直接依赖|maven|
|com.google.http-client:google-http-client-jackson2|1.42.2|间接依赖|maven|
|org.apache.camel:camel-stub|3.20.6|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.4|直接依赖|maven|
|com.google.http-client:google-http-client-gson|1.42.2|间接依赖|maven|
|com.sun.xml.bind:jaxb-impl|2.3.3|间接依赖|maven|
|org.apache.camel:camel-xslt|3.20.6|间接依赖|maven|
|io.prometheus:simpleclient||直接依赖|maven|
|org.apache.james:apache-mime4j-dom|0.8.8|间接依赖|maven|
|org.codehaus.groovy:groovy-groovydoc|3.0.10|间接依赖|maven|
|com.google.cloud:proto-google-cloud-firestore-bundle-v1|3.7.0|间接依赖|maven|
|MaterialComponents/Elevation|124.2.0|间接依赖|cocoapods|
|org.jboss.threads:jboss-threads|3.5.0.Final|间接依赖|maven|
|com.google.auth:google-auth-library-credentials|1.12.1|间接依赖|maven|
|com.google.code.gson:gson|2.9.1|间接依赖|maven|
|org.jboss:jandex|2.4.3.Final|间接依赖|maven|
|org.jboss.resteasy:resteasy-core|6.2.2.Final|间接依赖|maven|
|org.junit.platform:junit-platform-commons|1.8.2|间接依赖|maven|
|GoogleAppMeasurement/WithoutAdIdSupport|8.11.0|间接依赖|cocoapods|
|org.apache.camel:camel-micrometer|3.20.6|直接依赖|maven|
|org.openremote:or-shared|3.0-M1|间接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|io.micrometer:micrometer-core|1.11.0|直接依赖|maven|
|org.graalvm.regex:regex|22.3.1|间接依赖|maven|
|org.hamcrest:hamcrest-core|1.3|间接依赖|maven|
|org.hibernate.common:hibernate-commons-annotations|6.0.6.Final|间接依赖|maven|
|org.jetbrains:annotations|16.0.3|间接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.93.Final|间接依赖|maven|
|org.apache.camel:camel-file|3.20.6|间接依赖|maven|
|org.quartz-scheduler:quartz|2.3.2|直接依赖|maven|
|com.google.cloud:google-cloud-core-grpc|2.8.22|间接依赖|maven|
|org.codehaus.groovy:groovy-testng|3.0.10|间接依赖|maven|
|org.junit.platform:junit-platform-launcher|1.8.2|间接依赖|maven|
|com.fazecast:jSerialComm|2.7.0|直接依赖|maven|
|io.netty:netty-common|4.1.93.Final|间接依赖|maven|
|org.apache.camel:camel-scheduler|3.20.6|间接依赖|maven|
|GoogleUtilities/UserDefaults|7.7.0|间接依赖|cocoapods|
|com.google.api.grpc:grpc-google-iam-v1|1.6.4|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)