# jetlinks/jetlinks-community安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694772885368692736.svg)](https://www.murphysec.com/console/report/1694772885326749696/1694772885368692736)

仓库描述：JetLinks  基于Java8,Spring Boot 2.x ,WebFlux,Netty,Vert.x,Reactor等开发, 是一个全响应式的企业级物联网平台。支持统一物模型管理,多种设备,多种厂家,统一管理。统一设备连接管理,多协议适配(TCP,MQTT,UDP,CoAP,HTTP等),屏蔽网络编程复杂性,灵活接入不同厂家不同协议等设备。实时数据处理,设备告警,消息通知,数据转发。地理位置,数据可视化等。能帮助你快速建立物联网相关业务系统。

仓库地址：[https://github.com/jetlinks/jetlinks-community](https://github.com/jetlinks/jetlinks-community)

| star：4518 | watch：130 | fork：1471 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-24 10:07:08 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-25 02:28:58 | 组件总数：559 | 漏洞总数：40 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache Groovy 代码注入漏洞|注入|[MPS-2015-3848](https://www.oscs1024.com/hd/MPS-2015-3848)|CVE-2015-3253|严重|
|Google protobuf 缓冲区错误漏洞|越界写入|[MPS-2017-10841](https://www.oscs1024.com/hd/MPS-2017-10841)|CVE-2015-5237|高危|
|Apache Log4j SocketServer反序列化漏洞|反序列化|[MPS-2019-17271](https://www.oscs1024.com/hd/MPS-2019-17271)|CVE-2019-17571|严重|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|Apache Log4j2 SmtpAppender证书验证不当漏洞|证书验证不恰当|[MPS-2020-6684](https://www.oscs1024.com/hd/MPS-2020-6684)|CVE-2020-9488|低危|
|jsoup <1.14.2 存在拒绝服务漏洞||[MPS-2021-17634](https://www.oscs1024.com/hd/MPS-2021-17634)|CVE-2021-37714|高危|
|Spring Framework <5.3.14 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18854](https://www.oscs1024.com/hd/MPS-2021-18854)|CVE-2021-22060|中危|
|Pivotal Spring Framework 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18890](https://www.oscs1024.com/hd/MPS-2021-18890)|CVE-2021-22096|中危|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|Netty <4.1.71.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2021-36922](https://www.oscs1024.com/hd/MPS-2021-36922)|CVE-2021-43797|中危|
|Apache Log4j JMSAppender反序列化漏洞||[MPS-2021-38359](https://www.oscs1024.com/hd/MPS-2021-38359)|CVE-2021-4104|高危|
|Jakarta Expression Language <=3.0.3 存在输入验证错误漏洞|表达式语言注入|[MPS-2021-7671](https://www.oscs1024.com/hd/MPS-2021-7671)|CVE-2021-28170|中危|
|Vmware Spring Framework 安全漏洞|不加限制或调节的资源分配|[MPS-2022-1080](https://www.oscs1024.com/hd/MPS-2022-1080)|CVE-2022-22950|中危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|FasterXML Jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2022-12500](https://www.oscs1024.com/hd/MPS-2022-12500)||中危|
|Apache Log4j JDBCAppender SQL注入漏洞|SQL注入|[MPS-2022-1444](https://www.oscs1024.com/hd/MPS-2022-1444)|CVE-2022-23305|严重|
|Apache Log4j Chainsaw反序列化漏洞|反序列化|[MPS-2022-1445](https://www.oscs1024.com/hd/MPS-2022-1445)|CVE-2022-23307|高危|
|Apache Log4j 反序列化漏洞|反序列化|[MPS-2022-1446](https://www.oscs1024.com/hd/MPS-2022-1446)|CVE-2022-23302|高危|
|Netty 存在信息泄露漏洞||[MPS-2022-3790](https://www.oscs1024.com/hd/MPS-2022-3790)|CVE-2022-24823|中危|
|jsoup <1.15.3 存在反射型 XSS 漏洞|XSS|[MPS-2022-51547](https://www.oscs1024.com/hd/MPS-2022-51547)|CVE-2022-36033|中危|
|Eclipse Californium 安全漏洞|不正确的行为次序：早期放大攻击|[MPS-2022-52744](https://www.oscs1024.com/hd/MPS-2022-52744)|CVE-2022-2576|高危|
|Netty <4.1.86.Final 存在拒绝服务漏洞|未经控制的递归|[MPS-2022-58518](https://www.oscs1024.com/hd/MPS-2022-58518)|CVE-2022-41881|中危|
|Netty <4.1.86.Final 存在 CRLF 注入漏洞||[MPS-2022-58552](https://www.oscs1024.com/hd/MPS-2022-58552)|CVE-2022-41915|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Apache MINA SSHD < 2.9.2 存在Java反序列化漏洞|反序列化|[MPS-2022-63954](https://www.oscs1024.com/hd/MPS-2022-63954)|CVE-2022-45047|高危|
|Eclipse Californium 安全漏洞||[MPS-2022-64073](https://www.oscs1024.com/hd/MPS-2022-64073)|CVE-2022-39368|高危|
|H2 数据库明文密码问题|未授权敏感信息泄露|[MPS-2022-65204](https://www.oscs1024.com/hd/MPS-2022-65204)|CVE-2022-45868|高危|
|jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2023-8438](https://www.oscs1024.com/hd/MPS-2023-8438)|CVE-2021-46877|中危|
|Apache MINA SSHD SFTP路径穿越漏洞|路径遍历|[MPS-4amk-710b](https://www.oscs1024.com/hd/MPS-4amk-710b)|CVE-2023-35887|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.squareup.okio:okio|2.8.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-web|5.3.29|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework:spring-web|5.3.23|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.codehaus.groovy:groovy-all|2.1.3|2.4.4|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.4|2.14.0-rc1|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.apache.sshd:sshd-common|2.7.0|2.9.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.89.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|io.netty:netty-handler|4.1.77.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.eclipse.californium:californium-core|3.5.0|3.6.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.google.protobuf:protobuf-java|2.6.1|3.21.7|直接依赖|建议修复|C:0|H:1|M:2|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.11.4|2.14.0-rc1|间接依赖|建议修复|C:0|H:1|M:5|L:0|
|org.apache.sshd:sshd-sftp|2.7.0|2.10|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.eclipse.californium:element-connector|3.5.0|3.7.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.14.3||间接依赖|建议修复|C:0|H:0|M:1|L:0|
|io.netty:netty-handler|4.1.82.Final|4.1.94.final|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|log4j:log4j|1.2.17||直接依赖|建议修复|C:2|H:3|M:0|L:1|
|org.springframework:spring-web|5.2.22.RELEASE|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework:spring-core|5.3.23|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-core|5.2.22.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.h2database:h2|2.1.210||直接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-expression|4.0.6.RELEASE|6.0.8|直接依赖|可选修复|C:0|H:1|M:1|L:0|
|io.netty:netty-codec-http|4.1.68.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-expression|5.2.22.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.bouncycastle:bcprov-jdk15on|1.69||直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.jsoup:jsoup|1.8.3|1.15.3|直接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.springframework:spring-core|4.0.6.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.glassfish:jakarta.el|3.0.3|3.0.4|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.bouncycastle:bcprov-jdk15on|1.70||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-http|4.1.82.Final|4.1.86.final|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-common|4.1.66.Final|4.1.77.Final|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-codec:commons-codec|1.10|1.13|直接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.glassfish:javax.el|3.0.0||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-haproxy|4.1.82.Final|4.1.86.final|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|30.1.1-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|414|Low|
|自定义许可证|53|Low|
|EPL-2.0|15|Low|
|MIT|20|Low|
|LGPL-2.1|3|Medium|
|MPL-1.1|4|Low|
|LGPL-2.1-or-later|3|Low|
|BSD-2-Clause|6|Low|
|BSD-3-Clause|1|Low|
|EPL-1.0|13|Low|
|MPL-2.0|1|Low|
|CDDL-1.1|1|Low|
|MIT-0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.springframework:spring-context-indexer|5.3.29|直接依赖|maven|
|org.apache.lucene:lucene-spatial3d|8.11.1|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|直接依赖|maven|
|org.elasticsearch:elasticsearch-geo|7.17.5|间接依赖|maven|
|jakarta.persistence:jakarta.persistence-api|2.2.3|直接依赖|maven|
|com.alibaba:fastjson|1.2.83|间接依赖|maven|
|io.scalecube:scalecube-services-transport-jackson|2.10.23|间接依赖|maven|
|org.synchronoss.cloud:nio-multipart-parser|1.1.0|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|直接依赖|maven|
|com.github.freva:ascii-table|1.8.0|直接依赖|maven|
|io.projectreactor.netty:reactor-netty-http|1.0.24|间接依赖|maven|
|org.hswebframework:reactor-excel|1.0.6-SNAPSHOT|直接依赖|maven|
|org.ehcache:ehcache|3.10.8|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.4|直接依赖|maven|
|io.netty:netty-codec-socks|4.1.82.Final|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.14.3|间接依赖|maven|
|org.javassist:javassist|3.21.0-GA|间接依赖|maven|
|org.springframework:spring-aspects|5.3.29|间接依赖|maven|
|org.codehaus.janino:commons-compiler|3.0.6|间接依赖|maven|
|org.jetlinks.community:logging-manager|2.2.0-SNAPSHOT|直接依赖|maven|
|org.apache.lucene:lucene-grouping|8.11.1|间接依赖|maven|
|io.protostuff:protostuff-collectionschema|1.6.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.2|直接依赖|maven|
|org.apache.lucene:lucene-backward-codecs|8.11.1|间接依赖|maven|
|org.hswebframework.web:hsweb-system-file|4.0.17-SNAPSHOT|直接依赖|maven|
|io.r2dbc:r2dbc-pool|0.9.2.RELEASE|直接依赖|maven|
|net.java.dev.jna:jna-platform|5.12.1|间接依赖|maven|
|com.ning:compress-lzf|1.0.3|直接依赖|maven|
|javax.servlet:javax.servlet-api|3.1.0|直接依赖|maven|
|org.springframework:spring-context|5.2.22.RELEASE|间接依赖|maven|
|org.jline:jline-terminal-jansi|3.21.0|直接依赖|maven|
|io.netty:netty-transport|4.1.77.Final|间接依赖|maven|
|org.hswebframework.web:hsweb-concurrent-cache|4.0.17-SNAPSHOT|间接依赖|maven|
|org.eclipse.parsson:parsson|1.0.0|间接依赖|maven|
|com.squareup.moshi:moshi|1.8.0|间接依赖|maven|
|org.jetlinks.community:device-manager|2.2.0-SNAPSHOT|直接依赖|maven|
|org.apache.logging.log4j:log4j-1.2-api|2.17.2|直接依赖|maven|
|io.grpc:grpc-core|1.53.0|间接依赖|maven|
|org.jetlinks.community:tcp-component|2.2.0-SNAPSHOT|直接依赖|maven|
|org.apache.poi:poi-ooxml|5.2.3|间接依赖|maven|
|com.aayushatharva.brotli4j:native-linux-x86_64|1.8.0|直接依赖|maven|
|logkit:logkit|1.0.1|直接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.69|直接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.30|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.82.Final|直接依赖|maven|
|io.netty:netty-common|4.1.77.Final|间接依赖|maven|
|javassist:javassist|3.11.0.GA|间接依赖|maven|
|io.scalecube:scalecube-services-discovery|2.10.23|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.32|直接依赖|maven|
|com.taosdata.jdbc:taos-jdbcdriver|3.0.0|直接依赖|maven|
|io.netty:netty-codec-dns|4.1.77.Final|间接依赖|maven|
|org.apache.lucene:lucene-queries|8.11.1|间接依赖|maven|
|io.scalecube:scalecube-services-transport-protostuff|2.10.23|间接依赖|maven|
|org.jetlinks.community:notify-voice|2.2.0-SNAPSHOT|直接依赖|maven|
|io.vertx:vertx-core|4.3.1|直接依赖|maven|
|com.squareup.okio:okio|2.8.0|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.10.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.11.4|直接依赖|maven|
|io.projectreactor:reactor-tools|3.4.29|间接依赖|maven|
|io.netty:netty-tcnative-classes|2.0.54.Final|直接依赖|maven|
|org.jetlinks:simulator-core|2.0.0-SNAPSHOT|直接依赖|maven|
|info.picocli:picocli|4.7.0|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.11.4|直接依赖|maven|
|org.lz4:lz4-java|1.8.0|间接依赖|maven|
|org.elasticsearch.plugin:transport-netty4-client|7.17.5|直接依赖|maven|
|io.projectreactor:reactor-core|3.4.29|直接依赖|maven|
|org.hswebframework.web:hsweb-core|4.0.17-SNAPSHOT|直接依赖|maven|
|org.springframework:spring-webflux|5.3.23|直接依赖|maven|
|com.alibaba:easyexcel-support|3.1.1|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-http|1.0.31|间接依赖|maven|
|org.jboss.marshalling:jboss-marshalling|2.0.5.Final|直接依赖|maven|
|commons-collections:commons-collections|3.2.2|直接依赖|maven|
|org.jsoup:jsoup|1.8.3|直接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.70|间接依赖|maven|
|org.hswebframework.web:hsweb-system-authorization-default|4.0.17-SNAPSHOT|直接依赖|maven|
|io.zipkin.brave:brave|5.15.0|间接依赖|maven|
|org.hswebframework.web:hsweb-system-authorization-api|4.0.17-SNAPSHOT|间接依赖|maven|
|javax.mail:mail|1.4|直接依赖|maven|
|org.springframework:spring-core|5.3.29|间接依赖|maven|
|com.ongres.scram:client|2.1|间接依赖|maven|
|org.springframework:spring-expression|4.0.6.RELEASE|直接依赖|maven|
|org.jetlinks.community:notify-manager|2.2.0-SNAPSHOT|直接依赖|maven|
|org.jetlinks.community:logging-component|2.2.0-SNAPSHOT|直接依赖|maven|
|org.apache.commons:commons-pool2|2.11.1|直接依赖|maven|
|org.jetlinks.community:notify-dingtalk|2.2.0-SNAPSHOT|直接依赖|maven|
|net.sf.jopt-simple:jopt-simple|5.0.2|间接依赖|maven|
|org.jetlinks:jetlinks-core|1.2.2-SNAPSHOT|直接依赖|maven|
|com.aayushatharva.brotli4j:native-osx-x86_64|1.8.0|直接依赖|maven|
|org.slf4j:log4j-over-slf4j|1.7.36|直接依赖|maven|
|org.javassist:javassist|3.29.0-GA|直接依赖|maven|
|org.jetlinks.community:notify-core|2.2.0-SNAPSHOT|直接依赖|maven|
|org.jetlinks.community:protocol-component|2.2.0-SNAPSHOT|直接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.5|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-common|1.17.0|间接依赖|maven|
|org.msgpack:msgpack-core|0.9.0|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|直接依赖|maven|
|io.opentelemetry:opentelemetry-context|1.17.0|间接依赖|maven|
|io.projectreactor:reactor-core|3.3.8.RELEASE|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.5.1|直接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.89.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator|2.7.14|间接依赖|maven|
|org.hswebframework:hsweb-easy-orm-core|4.1.2-SNAPSHOT|直接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.82.Final|间接依赖|maven|
|org.jetlinks.community:things-component|2.2.0-SNAPSHOT|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.18.0|间接依赖|maven|
|org.apache.ant:ant-launcher|1.10.12|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-trace|1.17.0|直接依赖|maven|
|org.jetlinks.community:authentication-manager|2.2.0-SNAPSHOT|直接依赖|maven|
|org.synchronoss.cloud:nio-stream-storage|1.1.3|直接依赖|maven|
|org.apache.poi:poi-excelant|5.2.3|间接依赖|maven|
|com.google.guava:guava|30.1.1-jre|间接依赖|maven|
|com.github.whvcse:easy-captcha|1.6.2|直接依赖|maven|
|org.springframework:spring-core|5.3.23|间接依赖|maven|
|commons-lang:commons-lang|2.6|直接依赖|maven|
|org.aspectj:aspectjweaver|1.9.7|间接依赖|maven|
|org.elasticsearch:elasticsearch-lz4|7.17.5|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.11.4|间接依赖|maven|
|org.apache.lucene:lucene-memory|8.11.1|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.7.14|直接依赖|maven|
|io.netty:netty-jni-util|0.0.3.Final|直接依赖|maven|
|org.jetlinks.community:configure-component|2.2.0-SNAPSHOT|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.14.0|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.21.7|间接依赖|maven|
|org.hswebframework.web:hsweb-system-dictionary|4.0.17-SNAPSHOT|直接依赖|maven|
|io.netty:netty-tcnative|2.0.54.Final|直接依赖|maven|
|com.fasterxml:classmate|1.3.4|直接依赖|maven|
|org.springframework:spring-expression|5.2.22.RELEASE|间接依赖|maven|
|io.scalecube:scalecube-cluster-api|2.6.12|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.9|直接依赖|maven|
|org.jetlinks.community:notify-wechat|2.2.0-SNAPSHOT|直接依赖|maven|
|io.netty:netty-resolver-dns|4.1.77.Final|间接依赖|maven|
|io.r2dbc:r2dbc-h2|0.9.1.RELEASE|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-reactor-netty|2.7.14|间接依赖|maven|
|org.jetlinks.community:timeseries-component|2.2.0-SNAPSHOT|直接依赖|maven|
|io.asyncer:r2dbc-mysql|0.9.3|直接依赖|maven|
|com.ongres.stringprep:stringprep|1.1|间接依赖|maven|
|com.carrotsearch:hppc|0.8.1|间接依赖|maven|
|javax.activation:activation|1.1|间接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-client|7.17.5|间接依赖|maven|
|org.jetlinks:jetlinks-supports|1.2.2-SNAPSHOT|直接依赖|maven|
|io.projectreactor.netty:reactor-netty-http-brave|1.0.31|间接依赖|maven|
|org.codehaus.groovy:groovy-all|2.4.15|间接依赖|maven|
|com.github.jponge:lzma-java|1.3|直接依赖|maven|
|org.hswebframework.web:hsweb-starter|4.0.17-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.11.4|间接依赖|maven|
|com.squareup.okhttp3:okhttp|4.9.3|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|org.apache.sshd:sshd-common|2.7.0|间接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.89.Final|间接依赖|maven|
|org.joda:joda-convert|1.2|直接依赖|maven|
|org.springframework:spring-aop|5.3.29|间接依赖|maven|
|org.jetlinks.community:script-component|2.2.0-SNAPSHOT|直接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.23|直接依赖|maven|
|io.netty:netty-codec-http|4.1.82.Final|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.6.21|间接依赖|maven|
|org.fusesource.jansi:jansi|1.9|直接依赖|maven|
|/usr/lib/libgcc_s.1.dylib||间接依赖||
|io.netty:netty-resolver|4.1.77.Final|间接依赖|maven|
|com.google.guava:guava|32.0.0-jre|直接依赖|maven|
|org.apache.poi:poi-ooxml-full|5.2.3|间接依赖|maven|
|io.protostuff:protostuff-runtime|1.6.0|间接依赖|maven|
|org.springframework:spring-beans|5.3.29|间接依赖|maven|
|io.netty:netty-handler|4.1.89.Final|间接依赖|maven|
|org.hswebframework.web:hsweb-commons-crud|4.0.17-SNAPSHOT|直接依赖|maven|
|net.i2p.crypto:eddsa|0.3.0|间接依赖|maven|
|com.sun.istack:istack-commons-runtime|3.0.12|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.82.Final|直接依赖|maven|
|io.github.classgraph:classgraph|4.8.149|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.7.14|间接依赖|maven|
|net.java.dev.jna:jna|5.9.0|直接依赖|maven|
|com.alibaba:easyexcel-core|3.1.1|间接依赖|maven|
|info.picocli:picocli-shell-jline3|4.7.0|直接依赖|maven|
|io.scalecube:scalecube-services-transport-rsocket|2.10.23|间接依赖|maven|
|org.jetlinks.community:network-core|2.2.0-SNAPSHOT|直接依赖|maven|
|org.apache.commons:commons-text|1.10.0|直接依赖|maven|
|org.yaml:snakeyaml|2.0|间接依赖|maven|
|org.springframework.data:spring-data-elasticsearch|4.4.14|直接依赖|maven|
|org.hswebframework.web:hsweb-authorization-basic|4.0.17-SNAPSHOT|直接依赖|maven|
|/usr/lib/libSystem.B.dylib||间接依赖||
|io.netty:netty-codec-mqtt|4.1.68.Final|间接依赖|maven|
|io.scalecube:scalecube-cluster|2.6.12|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.14|直接依赖|maven|
|io.vertx:vertx-web|4.3.8|直接依赖|maven|
|org.springframework:spring-web|5.2.22.RELEASE|间接依赖|maven|
|io.netty:netty-common|4.1.89.Final|间接依赖|maven|
|io.rsocket:rsocket-transport-netty|1.0.5|间接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.82.Final|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.4|直接依赖|maven|
|joda-time:joda-time|2.10.10|间接依赖|maven|
|org.elasticsearch:elasticsearch-cli|7.17.5|间接依赖|maven|
|com.github.xiaoymin:knife4j-springdoc-ui|2.0.8|直接依赖|maven|
|org.apache.sshd:sshd-core|2.7.0|直接依赖|maven|
|io.vertx:vertx-mqtt|4.3.8|直接依赖|maven|
|org.apache.commons:commons-csv|1.10.0|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.9.3|直接依赖|maven|
|io.netty:netty-codec-socks|4.1.89.Final|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.89.Final|间接依赖|maven|
|org.hswebframework.web:hsweb-core|4.0.15-SNAPSHOT|间接依赖|maven|
|io.projectreactor:reactor-core|3.4.23|间接依赖|maven|
|org.conscrypt:conscrypt-openjdk-uber|2.5.2|直接依赖|maven|
|org.hswebframework.web:hsweb-datasource-api|4.0.17-SNAPSHOT|间接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.69|直接依赖|maven|
|commons-logging:commons-logging|1.2|直接依赖|maven|
|org.checkerframework:checker-qual|3.19.0|间接依赖|maven|
|io.grpc:grpc-netty-shaded|1.53.0|直接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.16|间接依赖|maven|
|io.netty:netty-handler|4.1.82.Final|直接依赖|maven|
|com.alibaba:easyexcel|3.1.1|直接依赖|maven|
|org.jetlinks.community:dashboard-component|2.2.0-SNAPSHOT|直接依赖|maven|
|org.fusesource.jansi:jansi|2.4.0|直接依赖|maven|
|joda-time:joda-time|2.9.7|直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-logs|1.17.0-alpha|间接依赖|maven|
|io.zipkin.brave:brave|5.14.1|间接依赖|maven|
|org.springframework:spring-aop|5.2.22.RELEASE|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.16|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.14|直接依赖|maven|
|io.netty:netty-codec|4.1.68.Final|间接依赖|maven|
|io.scalecube:scalecube-services|2.10.23|间接依赖|maven|
|io.zipkin.reporter2:zipkin-reporter|2.16.3|间接依赖|maven|
|org.hswebframework:hsweb-expands-script|3.0.2|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.14.3|间接依赖|maven|
|io.opentracing:opentracing-util|0.33.0|间接依赖|maven|
|io.micrometer:micrometer-core|1.9.13|直接依赖|maven|
|org.jetlinks.community:notify-email|2.2.0-SNAPSHOT|直接依赖|maven|
|com.github.oshi:oshi-core|6.2.2|直接依赖|maven|
|io.swagger.core.v3:swagger-annotations|2.2.8|直接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.66.Final|间接依赖|maven|
|org.apache.lucene:lucene-analyzers-common|8.11.1|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.89.Final|间接依赖|maven|
|io.grpc:grpc-netty|1.53.0|直接依赖|maven|
|org.apache.poi:poi|5.2.3|间接依赖|maven|
|io.netty.incubator:netty-incubator-codec-classes-quic|0.0.39.Final|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-http-brave|1.0.24|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-core|1.0.10|间接依赖|maven|
|io.netty:netty-common|4.1.66.Final|直接依赖|maven|
|io.netty:netty-resolver-dns|4.1.82.Final|直接依赖|maven|
|io.r2dbc:r2dbc-mssql|0.9.0.RELEASE|直接依赖|maven|
|com.fasterxml.jackson.jr:jackson-jr-objects|2.14.3|直接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.53.0|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.66.Final|间接依赖|maven|
|io.netty:netty-buffer|4.1.77.Final|间接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|2.3.8|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|直接依赖|maven|
|org.jline:jline|3.21.0|间接依赖|maven|
|org.glassfish.jaxb:txw2|2.3.8|间接依赖|maven|
|org.jline:jline-reader|3.21.0|直接依赖|maven|
|javax.cache:cache-api|1.1.1|间接依赖|maven|
|io.vertx:vertx-core|4.3.4|直接依赖|maven|
|io.vertx:vertx-auth-common|4.3.8|间接依赖|maven|
|org.springframework:spring-aspects|5.2.22.RELEASE|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.89.Final|间接依赖|maven|
|io.netty:netty-codec-mqtt|4.1.82.Final|直接依赖|maven|
|com.zaxxer:SparseBitSet|1.2|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|io.projectreactor.addons:reactor-extra|3.4.10|间接依赖|maven|
|libc.so.6||间接依赖||
|org.apache.logging.log4j:log4j-api|2.18.0|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.11|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-redis|2.7.14|直接依赖|maven|
|org.elasticsearch.plugin:aggs-matrix-stats-client|7.17.5|间接依赖|maven|
|de.ruedigermoeller:fst|2.57|直接依赖|maven|
|org.apache.poi:poi-scratchpad|5.2.3|间接依赖|maven|
|org.springdoc:springdoc-openapi-webflux-ui|1.6.11|直接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.89.Final|间接依赖|maven|
|io.r2dbc:r2dbc-spi|0.9.1.RELEASE|间接依赖|maven|
|ld-linux-x86-64.so.2||间接依赖||
|org.jetlinks.community:rule-engine-component|2.2.0-SNAPSHOT|直接依赖|maven|
|org.springframework:spring-expression|5.3.29|间接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.8|直接依赖|maven|
|io.swagger:swagger-annotations|1.5.10|间接依赖|maven|
|org.jctools:jctools-core|3.1.0|直接依赖|maven|
|com.ongres.stringprep:saslprep|1.1|间接依赖|maven|
|org.elasticsearch.plugin:rank-eval-client|7.17.5|间接依赖|maven|
|org.jetlinks:reactor-ql|1.0.16|直接依赖|maven|
|io.vertx:vertx-uri-template|4.3.8|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.9|间接依赖|maven|
|org.jctools:jctools-core|4.0.1|直接依赖|maven|
|org.webjars:swagger-ui|4.14.0|间接依赖|maven|
|org.hswebframework.web:hsweb-access-logging-api|4.0.17-SNAPSHOT|直接依赖|maven|
|org.springframework:spring-tx|5.3.29|间接依赖|maven|
|org.apache.commons:commons-collections4|4.4|间接依赖|maven|
|org.jetlinks.community:common-component|2.2.0-SNAPSHOT|直接依赖|maven|
|org.hswebframework.web:hsweb-commons-api|4.0.17-SNAPSHOT|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.89.Final|直接依赖|maven|
|io.scalecube:scalecube-transport-netty|2.6.12|间接依赖|maven|
|io.vertx:vertx-codegen|4.3.4|直接依赖|maven|
|ognl:ognl|3.1|直接依赖|maven|
|io.zipkin.brave:brave-instrumentation-http|5.13.3|间接依赖|maven|
|io.zipkin.brave:brave-instrumentation-http|5.14.1|间接依赖|maven|
|org.eclipse.californium:californium-legal|3.5.0|间接依赖|maven|
|org.hswebframework:hsweb-expands-security|3.0.2|直接依赖|maven|
|io.rsocket:rsocket-core|1.0.5|间接依赖|maven|
|io.netty:netty-buffer|4.1.89.Final|直接依赖|maven|
|com.google.protobuf.nano:protobuf-javanano|3.0.0-alpha-5|直接依赖|maven|
|org.apache.ant:ant|1.10.12|间接依赖|maven|
|org.jetlinks:rule-engine-api|1.2.2-SNAPSHOT|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.66.Final|间接依赖|maven|
|org.springframework.data:spring-data-redis|2.7.14|直接依赖|maven|
|io.netty:netty-codec-http|4.1.89.Final|间接依赖|maven|
|org.jline:jline-style|3.21.0|直接依赖|maven|
|io.rsocket:rsocket-core|1.1.3|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.3.Final|间接依赖|maven|
|org.hibernate.javax.persistence:hibernate-jpa-2.1-api|1.0.2.Final|间接依赖|maven|
|io.scalecube:scalecube-services-bytebuf-codec|2.10.23|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.18.0|间接依赖|maven|
|org.apache.lucene:lucene-join|8.11.1|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.14.3|间接依赖|maven|
|org.codehaus.groovy:groovy-all|2.1.3|直接依赖|maven|
|org.jetlinks:reactor-ql|1.0.14|直接依赖|maven|
|net.java.dev.jna:jna|5.12.1|间接依赖|maven|
|commons-io:commons-io|2.11.0|直接依赖|maven|
|com.h2database:h2|2.1.210|直接依赖|maven|
|org.apache.lucene:lucene-core|8.11.1|间接依赖|maven|
|net.bytebuddy:byte-buddy-agent|1.12.23|直接依赖|maven|
|org.jetlinks.community:rule-engine-manager|2.2.0-SNAPSHOT|直接依赖|maven|
|io.netty.incubator:netty-incubator-codec-classes-quic|0.0.33.Final|直接依赖|maven|
|org.jline:jline-builtins|3.21.0|直接依赖|maven|
|com.cronutils:cron-utils|9.2.0|直接依赖|maven|
|io.vertx:vertx-web-client|4.3.8|直接依赖|maven|
|org.springframework:spring-beans|5.3.23|间接依赖|maven|
|org.elasticsearch.plugin:parent-join-client|7.17.5|间接依赖|maven|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|org.jetlinks:rule-engine-cluster|1.2.2-SNAPSHOT|直接依赖|maven|
|io.netty:netty-codec-haproxy|4.1.82.Final|直接依赖|maven|
|org.springdoc:springdoc-openapi-webflux-core|1.6.11|直接依赖|maven|
|org.jetlinks:jetlinks-core|1.2.0-SNAPSHOT|直接依赖|maven|
|io.scalecube:scalecube-commons|1.0.18|间接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.18.0|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.6.21|间接依赖|maven|
|libgcc_s.so.1||间接依赖||
|org.springframework.boot:spring-boot-configuration-processor|2.7.14|直接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|io.lettuce:lettuce-core|6.1.10.RELEASE|直接依赖|maven|
|io.vertx:vertx-bridge-common|4.3.8|间接依赖|maven|
|org.jsoup:jsoup|1.15.3|直接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|org.apache.lucene:lucene-queryparser|8.11.1|间接依赖|maven|
|io.vertx:vertx-docgen|0.9.4|直接依赖|maven|
|org.elasticsearch:elasticsearch-x-content|7.17.5|间接依赖|maven|
|org.apache.lucene:lucene-misc|8.11.1|间接依赖|maven|
|org.jetlinks.community:mqtt-component|2.2.0-SNAPSHOT|直接依赖|maven|
|io.netty:netty-codec|4.1.82.Final|直接依赖|maven|
|org.springframework:spring-context-support|5.3.29|直接依赖|maven|
|com.squareup.okhttp3:logging-interceptor|4.9.3|间接依赖|maven|
|librt.so.1||间接依赖||
|org.eclipse.californium:element-connector|3.5.0|间接依赖|maven|
|io.protostuff:protostuff-api|1.6.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.4|间接依赖|maven|
|com.cronutils:cron-utils|9.1.6|直接依赖|maven|
|jakarta.json:jakarta.json-api|1.1.6|间接依赖|maven|
|org.hswebframework.web:hsweb-authorization-api|4.0.17-SNAPSHOT|直接依赖|maven|
|io.projectreactor.netty:reactor-netty-http-brave|1.0.10|间接依赖|maven|
|commons-codec:commons-codec|1.15|直接依赖|maven|
|com.squareup.retrofit2:converter-moshi|2.9.0|间接依赖|maven|
|org.springframework.data:spring-data-relational|2.4.14|间接依赖|maven|
|io.perfmark:perfmark-api|0.25.0|间接依赖|maven|
|com.ibm.icu:icu4j|72.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.14.3|间接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.89.Final|直接依赖|maven|
|io.zipkin.brave:brave|5.13.3|间接依赖|maven|
|org.hswebframework.web:hsweb-access-logging-aop|4.0.17-SNAPSHOT|直接依赖|maven|
|io.swagger.core.v3:swagger-core|2.2.2|间接依赖|maven|
|org.jetlinks:jetlinks-supports|1.2.0-SNAPSHOT|直接依赖|maven|
|org.springframework:spring-beans|5.2.22.RELEASE|间接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|2.9.0|间接依赖|maven|
|io.grpc:grpc-protobuf|1.53.0|直接依赖|maven|
|com.jcraft:jzlib|1.1.3|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.11.4|直接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-common|1.17.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.14.3|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.77.Final|间接依赖|maven|
|io.projectreactor.addons:reactor-pool|0.2.11|间接依赖|maven|
|com.squareup.retrofit2:retrofit|2.9.0|间接依赖|maven|
|io.opentelemetry:opentelemetry-api|1.17.0|直接依赖|maven|
|io.projectreactor.netty.incubator:reactor-netty-incubator-quic|0.0.20|间接依赖|maven|
|org.springframework:spring-oxm|5.3.29|间接依赖|maven|
|org.apache.xmlbeans:xmlbeans|5.1.1|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|间接依赖|maven|
|avalon-framework:avalon-framework|4.1.5|直接依赖|maven|
|org.springframework:spring-r2dbc|5.3.29|间接依赖|maven|
|org.hswebframework.web:hsweb-core||直接依赖|maven|
|org.apache.lucene:lucene-sandbox|8.11.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-r2dbc|2.7.14|直接依赖|maven|
|org.jetlinks.community:gateway-component|2.2.0-SNAPSHOT|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.21|直接依赖|maven|
|com.github.virtuald:curvesapi|1.07|间接依赖|maven|
|io.netty:netty-codec-http|4.1.68.Final|间接依赖|maven|
|org.ini4j:ini4j|0.5.4|间接依赖|maven|
|com.github.spullara.mustache.java:compiler|0.9.6|间接依赖|maven|
|org.jetlinks.community:tdengine-component|2.2.0-SNAPSHOT|直接依赖|maven|
|org.apache.lucene:lucene-suggest|8.11.1|间接依赖|maven|
|org.elasticsearch.plugin:lang-mustache-client|7.17.5|间接依赖|maven|
|org.elasticsearch:elasticsearch-plugin-classloader|7.17.5|间接依赖|maven|
|msvcrt.dll||间接依赖||
|com.sun.activation:jakarta.activation|1.2.2|间接依赖|maven|
|org.elasticsearch:elasticsearch-secure-sm|7.17.5|间接依赖|maven|
|javax.validation:validation-api|2.0.1.Final|间接依赖|maven|
|org.elasticsearch.plugin:mapper-extras-client|7.17.5|间接依赖|maven|
|org.springframework.data:spring-data-r2dbc|1.5.14|直接依赖|maven|
|org.jetlinks.community:http-component|2.2.0-SNAPSHOT|直接依赖|maven|
|io.opentracing:opentracing-noop|0.33.0|间接依赖|maven|
|org.javassist:javassist|3.27.0-GA|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.14|间接依赖|maven|
|io.netty.incubator:netty-incubator-codec-native-quic|0.0.39.Final|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.11|直接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.89.Final|间接依赖|maven|
|org.springframework:spring-jcl|5.3.23|间接依赖|maven|
|org.jline:jline-terminal|3.21.0|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.14.3|间接依赖|maven|
|org.checkerframework:checker-qual|3.33.0|间接依赖|maven|
|org.springframework:spring-jcl|5.3.29|间接依赖|maven|
|com.tdunning:t-digest|3.2|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.14.3|直接依赖|maven|
|org.jctools:jctools-core|2.1.2|间接依赖|maven|
|org.influxdb:influxdb-java|2.22|直接依赖|maven|
|org.glassfish:jakarta.el|3.0.4|间接依赖|maven|
|org.apache.sshd:sshd-sftp|2.7.0|直接依赖|maven|
|com.googlecode.juniversalchardet:juniversalchardet|1.0.3|直接依赖|maven|
|io.opentelemetry:opentelemetry-semconv|1.17.0-alpha|直接依赖|maven|
|org.glassfish:javax.el|3.0.0|间接依赖|maven|
|org.springframework:spring-jcl|5.2.22.RELEASE|间接依赖|maven|
|io.grpc:grpc-api|1.53.0|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|直接依赖|maven|
|org.springframework:spring-web|5.3.23|间接依赖|maven|
|io.vertx:vertx-web-common|4.3.8|间接依赖|maven|
|org.apache.sshd:sshd-scp|2.7.0|直接依赖|maven|
|com.sun.mail:jakarta.mail|1.6.7|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.12|直接依赖|maven|
|io.netty:netty-transport|4.1.89.Final|间接依赖|maven|
|com.google.protobuf:protobuf-java|2.6.1|直接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.82.Final|间接依赖|maven|
|io.projectreactor.tools:blockhound|1.0.6.RELEASE|直接依赖|maven|
|org.springframework:spring-web|5.3.29|间接依赖|maven|
|com.github.jsqlparser:jsqlparser|4.6|间接依赖|maven|
|org.jetlinks.community:io-component|2.2.0-SNAPSHOT|直接依赖|maven|
|org.elasticsearch:elasticsearch-core|7.17.5|间接依赖|maven|
|io.projectreactor.netty.incubator:reactor-netty-incubator-quic|0.0.13|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.14.3|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-metrics|1.17.0|间接依赖|maven|
|org.eclipse.californium:californium-core|3.5.0|直接依赖|maven|
|org.postgresql:r2dbc-postgresql|0.9.2.RELEASE|直接依赖|maven|
|io.vertx:vertx-core|4.3.8|直接依赖|maven|
|org.jacoco:org.jacoco.agent|0.8.5|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|2.8|间接依赖|maven|
|net.jpountz.lz4:lz4|1.3.0|直接依赖|maven|
|io.netty:netty-resolver|4.1.82.Final|直接依赖|maven|
|org.springframework:spring-context|5.3.29|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|com.belerweb:pinyin4j|2.5.0|直接依赖|maven|
|ch.qos.logback:logback-core|1.2.9|直接依赖|maven|
|io.zipkin.zipkin2:zipkin|2.23.2|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.82.Final|直接依赖|maven|
|io.vertx:vertx-mqtt|4.3.4|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.7.14|间接依赖|maven|
|com.aayushatharva.brotli4j:brotli4j|1.8.0|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|2.7.14|间接依赖|maven|
|com.google.code.gson:gson|2.9.1|间接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.30|直接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-logging|1.17.0|直接依赖|maven|
|io.scalecube:scalecube-transport-api|2.6.12|间接依赖|maven|
|org.springframework:spring-webflux|5.3.29|直接依赖|maven|
|io.swagger.core.v3:swagger-models|2.2.2|间接依赖|maven|
|org.jetlinks.community:notify-sms|2.2.0-SNAPSHOT|直接依赖|maven|
|com.aliyun:aliyun-java-sdk-dysmsapi|2.2.1|直接依赖|maven|
|org.hswebframework:hsweb-easy-orm-rdb|4.1.2-SNAPSHOT|直接依赖|maven|
|commons-logging:commons-logging|1.1.3|间接依赖|maven|
|org.jetlinks.community:relation-component|2.2.0-SNAPSHOT|直接依赖|maven|
|org.java-websocket:Java-WebSocket|1.5.2|间接依赖|maven|
|io.netty:netty-resolver|4.1.89.Final|间接依赖|maven|
|org.codehaus.janino:janino|3.0.6|直接依赖|maven|
|com.aayushatharva.brotli4j:native-windows-x86_64|1.8.0|直接依赖|maven|
|io.netty:netty-common|4.1.82.Final|直接依赖|maven|
|org.jetlinks.community:elasticsearch-component|2.2.0-SNAPSHOT|直接依赖|maven|
|co.elastic.clients:elasticsearch-java|7.17.9|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.2.5.Final|间接依赖|maven|
|io.projectreactor.netty:reactor-netty|1.0.10|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.6.21|间接依赖|maven|
|org.apache.lucene:lucene-highlighter|8.11.1|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-core|1.0.24|间接依赖|maven|
|org.springframework:spring-core|5.2.22.RELEASE|间接依赖|maven|
|org.springframework.data:spring-data-keyvalue|2.7.14|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-smile|2.14.3|间接依赖|maven|
|org.bouncycastle:bcutil-jdk15on|1.69|间接依赖|maven|
|org.codehaus.groovy:groovy|3.0.18|直接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.82.Final|直接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-high-level-client|7.17.5|直接依赖|maven|
|io.netty:netty-codec|4.1.89.Final|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.21|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-http|1.0.10|间接依赖|maven|
|io.zipkin.brave:brave-instrumentation-http|5.15.0|间接依赖|maven|
|log4j:log4j|1.2.17|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-webflux|2.7.14|直接依赖|maven|
|io.netty:netty-transport|4.1.82.Final|直接依赖|maven|
|KERNEL32.dll||间接依赖||
|org.apache.commons:commons-math3|3.6.1|间接依赖|maven|
|io.projectreactor.addons:reactor-extra|3.3.3.RELEASE|直接依赖|maven|
|javax.money:money-api|1.0.1|直接依赖|maven|
|io.seruco.encoding:base62|0.1.3|间接依赖|maven|
|org.glassfish:jakarta.el|3.0.3|间接依赖|maven|
|io.projectreactor.netty:reactor-netty|1.0.24|直接依赖|maven|
|io.netty:netty-handler-proxy|4.1.82.Final|直接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.1.7.Final|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk|1.17.0|直接依赖|maven|
|org.springframework.boot:spring-boot|2.7.14|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.77.Final|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.0-2|直接依赖|maven|
|libdl.so.2||间接依赖||
|com.aliyun:aliyun-java-sdk-core|4.5.2|直接依赖|maven|
|commons-codec:commons-codec|1.10|直接依赖|maven|
|io.swagger.core.v3:swagger-annotations|2.1.4|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.6.21|间接依赖|maven|
|commons-codec:commons-codec|1.14|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|直接依赖|maven|
|org.elasticsearch:elasticsearch|7.17.5|间接依赖|maven|
|com.github.jsqlparser:jsqlparser|4.1|直接依赖|maven|
|org.webjars:webjars-locator-core|0.50|间接依赖|maven|
|io.opentracing:opentracing-api|0.33.0|间接依赖|maven|
|org.springframework:spring-core|4.0.6.RELEASE|间接依赖|maven|
|io.netty:netty-handler|4.1.77.Final|间接依赖|maven|
|io.netty.incubator:netty-incubator-codec-native-quic|0.0.33.Final|间接依赖|maven|
|org.jetlinks.community:network-manager|2.2.0-SNAPSHOT|直接依赖|maven|
|org.hswebframework:hsweb-utils|3.0.2|直接依赖|maven|
|org.springdoc:springdoc-openapi-common|1.6.11|间接依赖|maven|
|io.rsocket:rsocket-transport-netty|1.1.3|间接依赖|maven|
|joda-time:joda-time|2.7|直接依赖|maven|
|io.scalecube:scalecube-services-api|2.10.23|间接依赖|maven|
|org.jetlinks:rule-engine-support|1.2.2-SNAPSHOT|直接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|org.objenesis:objenesis|2.5.1|间接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|直接依赖|maven|
|io.netty:netty-codec-mqtt|4.1.89.Final|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.89.Final|间接依赖|maven|
|com.github.ben-manes.caffeine:guava|2.9.3|直接依赖|maven|
|org.apache.poi:poi-ooxml-lite|5.2.3|间接依赖|maven|
|io.zipkin.reporter2:zipkin-reporter-brave|2.16.3|间接依赖|maven|
|com.ongres.scram:common|2.1|间接依赖|maven|
|io.projectreactor:reactor-tools|3.3.8.RELEASE|直接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-jaeger|1.17.0|直接依赖|maven|
|io.projectreactor.addons:reactor-extra|3.4.4|间接依赖|maven|
|io.projectreactor.netty:reactor-netty|1.0.31|直接依赖|maven|
|org.springframework.data:spring-data-commons|2.7.14|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-core|1.0.31|间接依赖|maven|
|org.checkerframework:checker-qual|3.8.0|直接依赖|maven|
|io.protostuff:protostuff-core|1.6.0|间接依赖|maven|
|io.grpc:grpc-context|1.53.0|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.82.Final|直接依赖|maven|
|io.netty:netty-jni-util|0.0.6.Final|直接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.89.Final|间接依赖|maven|
|io.netty:netty-buffer|4.1.82.Final|直接依赖|maven|
|io.netty:netty-codec-socks|4.1.77.Final|间接依赖|maven|
|org.springframework:spring-context-indexer|5.2.22.RELEASE|间接依赖|maven|
|org.jetlinks.community:notify-webhook|2.2.0-SNAPSHOT|直接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.82.Final|直接依赖|maven|
|org.jboss.logging:jboss-logging|3.3.2.Final|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)