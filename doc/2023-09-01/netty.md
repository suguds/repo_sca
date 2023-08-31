# netty/netty安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1697309082238410752.svg)](https://www.murphysec.com/console/report/1697309082192273408/1697309082238410752)

仓库描述：Netty project - an event-driven asynchronous network application framework

仓库地址：[https://github.com/netty/netty](https://github.com/netty/netty)

| star：31720 | watch：1767 | fork：15558 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-31 20:54:23 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-01 02:04:55 | 组件总数：89 | 漏洞总数：6 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google protobuf 缓冲区错误漏洞|越界写入|[MPS-2017-10841](https://www.oscs1024.com/hd/MPS-2017-10841)|CVE-2015-5237|高危|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|Quality Open Software logback JNDI注入漏洞|反序列化|[MPS-2021-33911](https://www.oscs1024.com/hd/MPS-2021-33911)|CVE-2021-42550|中危|
|Logback SSL证书校验不当漏洞|中间人攻击|[MPS-2022-12411](https://www.oscs1024.com/hd/MPS-2022-12411)||中危|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|ch.qos.logback:logback-core|1.2.3|1.2.8|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.google.protobuf:protobuf-java|2.6.1|3.21.7|直接依赖|建议修复|C:0|H:1|M:2|L:0|
|org.bouncycastle:bcprov-jdk15on|1.69||直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|15|Low|
|Apache-2.0|62|Low|
|BSD-2-Clause|1|Low|
|MIT|3|Low|
|EPL-2.0|5|Low|
|EPL-1.0|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.codehaus.woodstox:stax2-api|4.0.0|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|org.opentest4j:opentest4j|1.2.0|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|io.netty:netty-codec-socks|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|io.netty:netty-handler-ssl-ocsp|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|com.aayushatharva.brotli4j:native-osx-x86_64|1.12.0|直接依赖|maven|
|org.rxtx:rxtx|2.1.7|直接依赖|maven|
|io.netty:netty-codec-xml|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|com.sun.activation:javax.activation|1.2.0|直接依赖|maven|
|com.aayushatharva.brotli4j:native-linux-x86_64|1.12.0|直接依赖|maven|
|com.github.luben:zstd-jni|1.5.0-2|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.30|直接依赖|maven|
|org.apache.commons:commons-math3|3.2|间接依赖|maven|
|com.google.protobuf:protobuf-java|2.6.1|直接依赖|maven|
|org.bouncycastle:bctls-jdk15on|1.69|直接依赖|maven|
|io.netty:netty-jni-util|0.0.7.Final|直接依赖|maven|
|com.yammer.metrics:metrics-core|2.2.0|直接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|com.barchart.udt:barchart-udt-bundle|2.3.0|直接依赖|maven|
|com.ning:compress-lzf|1.0.3|直接依赖|maven|
|org.conscrypt:conscrypt-openjdk-uber|2.5.2|直接依赖|maven|
|commons-logging:commons-logging|1.2|直接依赖|maven|
|io.netty:netty-codec-stomp|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|com.aayushatharva.brotli4j:native-linux-aarch64|1.12.0|直接依赖|maven|
|io.netty:netty-codec-mqtt|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|libc.so.6||间接依赖||
|io.netty:netty-resolver|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|io.netty:netty-codec-redis|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|net.bytebuddy:byte-buddy-agent|1.8.5|间接依赖|maven|
|io.netty:netty-transport-udt|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|org.openjdk.jmh:jmh-core|1.36|直接依赖|maven|
|org.junit.platform:junit-platform-commons|1.9.0|间接依赖|maven|
|io.netty:netty-tcnative-boringssl-static|2.0.61.Final|直接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|com.aayushatharva.brotli4j:native-windows-x86_64|1.12.0|直接依赖|maven|
|org.junit.platform:junit-platform-engine|1.9.0|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.3|直接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|io.netty:netty-transport-rxtx|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.69|直接依赖|maven|
|io.netty:netty-handler|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|org.agrona:Agrona|0.5.1|直接依赖|maven|
|org.junit.jupiter:junit-jupiter-api|5.9.0|直接依赖|maven|
|io.netty:netty-codec-haproxy|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|io.netty:netty-buffer|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|io.netty:netty-codec-dns|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.69|直接依赖|maven|
|ch.qos.logback:logback-core|1.2.3|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|net.bytebuddy:byte-buddy|1.8.5|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|org.apiguardian:apiguardian-api|1.1.2|间接依赖|maven|
|org.bouncycastle:bcutil-jdk15on|1.69|间接依赖|maven|
|com.aayushatharva.brotli4j:native-linux-armv7|1.12.0|直接依赖|maven|
|net.jpountz.lz4:lz4|1.3.0|直接依赖|maven|
|org.tukaani:xz|1.5|直接依赖|maven|
|io.netty:netty-transport-sctp|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|org.hamcrest:hamcrest-core|1.3|间接依赖|maven|
|org.apache.felix:org.apache.felix.configadmin|1.9.14|直接依赖|maven|
|org.apache.logging.log4j:log4j-1.2-api|2.17.2|直接依赖|maven|
|org.jctools:jctools-core|3.1.0|直接依赖|maven|
|org.jboss.marshalling:jboss-marshalling|2.0.5.Final|直接依赖|maven|
|com.aayushatharva.brotli4j:service|1.12.0|间接依赖|maven|
|com.fasterxml:aalto-xml|1.0.0|直接依赖|maven|
|com.aayushatharva.brotli4j:brotli4j|1.12.0|直接依赖|maven|
|org.assertj:assertj-core|3.18.0|直接依赖|maven|
|org.objenesis:objenesis|2.6|间接依赖|maven|
|io.netty:netty-codec-http|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|org.junit.jupiter:junit-jupiter-engine|5.9.0|直接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.2|直接依赖|maven|
|io.projectreactor.tools:blockhound|1.0.6.RELEASE|直接依赖|maven|
|com.github.jponge:lzma-java|1.3|直接依赖|maven|
|com.aayushatharva.brotli4j:native-osx-aarch64|1.12.0|直接依赖|maven|
|org.junit.jupiter:junit-jupiter-params|5.9.0|直接依赖|maven|
|com.google.protobuf.nano:protobuf-javanano|3.0.0-alpha-5|直接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|net.sf.jopt-simple:jopt-simple|5.0.4|间接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|io.netty:netty-tcnative-classes|2.0.61.Final|直接依赖|maven|
|io.netty:netty-codec-smtp|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|org.hamcrest:hamcrest-library|1.3|直接依赖|maven|
|com.jcraft:jzlib|1.1.3|直接依赖|maven|
|io.netty:netty-codec|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|io.netty:netty-transport|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|org.mockito:mockito-core|2.18.3|直接依赖|maven|
|io.netty:netty-common|4.1.98.Final-SNAPSHOT|直接依赖|maven|
|io.netty:netty-codec-memcache|4.1.98.Final-SNAPSHOT|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)