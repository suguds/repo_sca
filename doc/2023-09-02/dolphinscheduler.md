# apache/dolphinscheduler安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1697671596608372736.svg)](https://www.murphysec.com/console/report/1691872996762734592/1697671596608372736)

仓库描述：Apache DolphinScheduler is the modern data orchestration platform. Agile to create high performance workflow with low-code

仓库地址：[https://github.com/apache/dolphinscheduler](https://github.com/apache/dolphinscheduler)

| star：11009 | watch：326 | fork：4107 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-01 22:31:20 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-02 02:20:06 | 组件总数：649 | 漏洞总数：59 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache Thrift <0.12.0 绕过验证漏洞|证书验证不恰当|[MPS-2019-0104](https://www.oscs1024.com/hd/MPS-2019-0104)|CVE-2018-1320|高危|
|Red Hat JBoss Enterprise Application Platform 代码问题漏洞|反序列化|[MPS-2019-12470](https://www.oscs1024.com/hd/MPS-2019-12470)|CVE-2019-10202|严重|
|jackson-mapper-asl <=1.9.13 XXE 注入漏洞|XXE|[MPS-2019-15048](https://www.oscs1024.com/hd/MPS-2019-15048)|CVE-2019-10172|高危|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|JetBrains Kotlin <1.4.21 不正确的默认权限漏洞|缺省权限不正确|[MPS-2021-1082](https://www.oscs1024.com/hd/MPS-2021-1082)|CVE-2020-29582|中危|
|Netty <4.1.59.Final 存在不安全的临时文件漏洞||[MPS-2021-1580](https://www.oscs1024.com/hd/MPS-2021-1580)|CVE-2021-21290|中危|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|io.netty:netty-codec-http2 <4.1.60.Final 存在 http 请求走私漏洞|HTTP请求走私|[MPS-2021-2435](https://www.oscs1024.com/hd/MPS-2021-2435)|CVE-2021-21295|中危|
|Netty Bzip2Decoder 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28116](https://www.oscs1024.com/hd/MPS-2021-28116)|CVE-2021-37136|高危|
|Netty 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28117](https://www.oscs1024.com/hd/MPS-2021-28117)|CVE-2021-37137|高危|
|Apache Commons Net <3.9.0 存在FTP跳转攻击漏洞|未授权敏感信息泄露|[MPS-2021-28440](https://www.oscs1024.com/hd/MPS-2021-28440)|CVE-2021-37533|中危|
| io.netty:netty-codec-http2 <4.1.61.Final 存在 http 请求走私漏洞|HTTP请求走私|[MPS-2021-3565](https://www.oscs1024.com/hd/MPS-2021-3565)|CVE-2021-21409|中危|
|Netty <4.1.71.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2021-36922](https://www.oscs1024.com/hd/MPS-2021-36922)|CVE-2021-43797|中危|
|Jakarta Expression Language <=3.0.3 存在输入验证错误漏洞|表达式语言注入|[MPS-2021-7671](https://www.oscs1024.com/hd/MPS-2021-7671)|CVE-2021-28170|中危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|org.apache.hive:hive-service 存在跨站脚本漏洞|XSS|[MPS-2022-12394](https://www.oscs1024.com/hd/MPS-2022-12394)||中危|
|Reactor Netty HTTP Server 敏感信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-12714](https://www.oscs1024.com/hd/MPS-2022-12714)|CVE-2022-31684|低危|
|org.json:json 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13520](https://www.oscs1024.com/hd/MPS-2022-13520)||高危|
|JetBrains Kotlin <1.6.0 存在锁定不当漏洞|加锁机制不恰当|[MPS-2022-3233](https://www.oscs1024.com/hd/MPS-2022-3233)|CVE-2022-24329|中危|
|Netty 存在信息泄露漏洞||[MPS-2022-3790](https://www.oscs1024.com/hd/MPS-2022-3790)|CVE-2022-24823|中危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|Bouncy Castle <1.69 认证绕过漏洞|密码学问题|[MPS-2022-54305](https://www.oscs1024.com/hd/MPS-2022-54305)||中危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|XStream 缓冲区错误漏洞|输入验证不恰当|[MPS-2022-57061](https://www.oscs1024.com/hd/MPS-2022-57061)|CVE-2022-40156|低危|
|xstream project跨界内存写漏洞|跨界内存写|[MPS-2022-57062](https://www.oscs1024.com/hd/MPS-2022-57062)|CVE-2022-40155|高危|
|xstream project跨界内存写漏洞|跨界内存写|[MPS-2022-57063](https://www.oscs1024.com/hd/MPS-2022-57063)|CVE-2022-40154|高危|
|XStream 缓冲区错误漏洞|越界写入|[MPS-2022-57065](https://www.oscs1024.com/hd/MPS-2022-57065)|CVE-2022-40152|高危|
|Jettison <1.5.2 拒绝服务漏洞|拒绝服务|[MPS-2022-57067](https://www.oscs1024.com/hd/MPS-2022-57067)|CVE-2022-40150|高危|
|Jettison <1.5.1 拒绝服务漏洞|越界写入|[MPS-2022-57068](https://www.oscs1024.com/hd/MPS-2022-57068)|CVE-2022-40149|高危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|Netty <4.1.86.Final 存在 CRLF 注入漏洞||[MPS-2022-58552](https://www.oscs1024.com/hd/MPS-2022-58552)|CVE-2022-41915|中危|
|pgjdbc <42.5.1 存在信息泄露漏洞|不安全的临时文件|[MPS-2022-58583](https://www.oscs1024.com/hd/MPS-2022-58583)|CVE-2022-41946|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
|Apache Commons Text <1.10.0 远程代码执行漏洞|反序列化|[MPS-2022-59712](https://www.oscs1024.com/hd/MPS-2022-59712)|CVE-2022-42889|严重|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|Spring Security通配符路由绕过漏洞|关键资源权限分配不当|[MPS-2022-62832](https://www.oscs1024.com/hd/MPS-2022-62832)|CVE-2023-20860|高危|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot在Cloud Foundry中部署存在路由限制绕过风险|访问控制不当|[MPS-2022-62845](https://www.oscs1024.com/hd/MPS-2022-62845)|CVE-2023-20873|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|Apache MINA SSHD < 2.9.2 存在Java反序列化漏洞|反序列化|[MPS-2022-63954](https://www.oscs1024.com/hd/MPS-2022-63954)|CVE-2022-45047|高危|
|Jettison <1.5.2 拒绝服务漏洞|越界写入|[MPS-2022-64973](https://www.oscs1024.com/hd/MPS-2022-64973)|CVE-2022-45685|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|【存在争议】MybatisPlus <= 3.5.3.1 TenantPlugin 组件 存在 sql 注入漏洞|SQL注入|[MPS-2023-3977](https://www.oscs1024.com/hd/MPS-2023-3977)|CVE-2023-25330|高危|
|Eclipse Jetty 资源管理错误漏洞|拒绝服务|[MPS-2023-4997](https://www.oscs1024.com/hd/MPS-2023-4997)|CVE-2023-26048|中危|
|Eclipse Jetty 信息泄露漏洞|XSS|[MPS-2023-4998](https://www.oscs1024.com/hd/MPS-2023-4998)|CVE-2023-26049|中危|
|netplex json-smart 安全漏洞|未经控制的递归|[MPS-2023-7760](https://www.oscs1024.com/hd/MPS-2023-7760)|CVE-2023-1370|高危|
|Jettison 安全漏洞|未经控制的递归|[MPS-2023-8270](https://www.oscs1024.com/hd/MPS-2023-8270)|CVE-2023-1436|高危|
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
|org.springframework:spring-webmvc|5.3.22|6.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-web|5.3.22|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.codehaus.jackson:jackson-mapper-asl|1.9.2||间接依赖|建议修复|C:1|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.53.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|org.apache.sshd:sshd-sftp|2.8.0|2.10|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.google.protobuf:protobuf-java|3.17.2|3.21.7|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.yaml:snakeyaml|1.33|2.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.commons:commons-text|1.8|1.10.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.eclipse.jetty:jetty-server|9.4.48.v20220622|12.0.0.beta0|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.squareup.okio:okio|1.6.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.7.3|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-codec|4.1.53.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|net.minidev:json-smart|2.4.8|2.4.9|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.4|2.14.0-rc1|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.fasterxml.woodstox:woodstox-core|5.3.0|6.4.0|间接依赖|建议修复|C:0|H:3|M:0|L:1|
|org.apache.sshd:sshd-common|2.8.0|2.9.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|net.minidev:json-smart|2.4.7|2.4.9|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.7.3|3.0.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.codehaus.jettison:jettison|1.1|1.5.4|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|org.yaml:snakeyaml|1.30|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|com.baomidou:mybatis-plus-extension|3.5.2||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13||间接依赖|建议修复|C:1|H:1|M:0|L:0|
|io.netty:netty-codec-http2|4.1.53.Final|4.1.61.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.jetbrains.kotlin:kotlin-stdlib|1.4.10|1.6.0|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.apache.hive:hive-service|2.3.9|release-2.3.8-rc2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.thrift:libthrift|0.9.3|0.12.0|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.code.gson:gson|2.8.6|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.bouncycastle:bcprov-jdk15on|1.67|1.69|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|io.netty:netty-common|4.1.53.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-expression|5.3.22|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.guava:guava|31.1-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.json:json|20140107|20180130|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|commons-net:commons-net|3.6|3.9.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-codec:commons-codec|1.11|1.13|直接依赖|可选修复|C:0|H:0|M:0|L:1|
|io.projectreactor.netty:reactor-netty-http|1.0.22|1.0.24|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|io.netty:netty-transport-native-epoll|4.1.53.Final|4.1.59.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.postgresql:postgresql|42.4.1|42.5.1|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.bouncycastle:bcprov-jdk15on|1.69||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-http|4.1.53.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:4|L:0|
|org.glassfish:javax.el|3.0.0||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-core|5.3.22|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|485|Low|
|自定义许可证|37|Low|
|JSON|1|Low|
|MIT|51|Low|
|EPL-2.0|18|Low|
|CDDL-1.1|8|Low|
|LGPL-2.1|4|Medium|
|BSD-3-Clause|5|Low|
|EPL-1.0|3|Low|
|MPL-2.0|1|Low|
|LGPL-2.1-or-later|2|Low|
|BSD-2-Clause|3|Low|
|MIT-0|1|Low|
|MPL-1.1|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.fasterxml.jackson.core:jackson-annotations|2.13.4|直接依赖|maven|
|io.fabric8:kubernetes-model-extensions|5.10.2|间接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|org.datanucleus:datanucleus-api-jdo|4.2.4|间接依赖|maven|
|org.apache.derby:derby|10.14.2.0|间接依赖|maven|
|io.kubernetes:client-java-api|13.0.2|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-api|dev-SNAPSHOT|直接依赖|maven|
|com.sun.mail:javax.mail|1.6.2|间接依赖|maven|
|org.codehaus.jackson:jackson-mapper-asl|1.9.2|间接依赖|maven|
|io.prometheus:simpleclient_tracer_otel_agent|0.15.0|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.36|间接依赖|maven|
|io.fabric8:kubernetes-model-storageclass|6.0.0|间接依赖|maven|
|org.json:json|20140107|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-oracle|dev-SNAPSHOT|直接依赖|maven|
|com.google.http-client:google-http-client-apache-v2|1.42.3|间接依赖|maven|
|com.azure:azure-storage-common|12.20.0|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.22|间接依赖|maven|
|org.apache.xmlbeans:xmlbeans|3.1.0|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.48.v20220622|间接依赖|maven|
|org.apache.kerby:kerb-simplekdc|1.0.1|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.53.Final|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-extract-worker|dev-SNAPSHOT|直接依赖|maven|
|software.amazon.awssdk:aws-json-protocol|2.17.282|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-privatedns|2.21.0|间接依赖|maven|
|com.azure:azure-identity|1.7.1|直接依赖|maven|
|org.java-websocket:Java-WebSocket|1.5.1|直接依赖|maven|
|com.azure:azure-core|1.36.0|间接依赖|maven|
|io.kubernetes:client-java|13.0.2|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-hive|dev-SNAPSHOT|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-extract-master|dev-SNAPSHOT|直接依赖|maven|
|io.trino:trino-jdbc|402|直接依赖|maven|
|com.sun.jersey:jersey-client|1.19|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.2|间接依赖|maven|
|org.codehaus.jackson:jackson-xc|1.9.2|间接依赖|maven|
|io.netty:netty-codec|4.1.53.Final|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter|3.1.3|间接依赖|maven|
|io.fabric8:kubernetes-model-metrics|5.10.2|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-chunjun|dev-SNAPSHOT|直接依赖|maven|
|io.fabric8:kubernetes-model-scheduling|6.0.0|间接依赖|maven|
|io.fabric8:kubernetes-model-admissionregistration|5.10.2|间接依赖|maven|
|com.jayway.jsonpath:json-path|2.7.0|直接依赖|maven|
|io.fabric8:kubernetes-model-scheduling|5.10.2|间接依赖|maven|
|io.swagger.core.v3:swagger-annotations|2.2.0|间接依赖|maven|
|javolution:javolution|5.5.1|间接依赖|maven|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.13.3|间接依赖|maven|
|io.projectreactor:reactor-core|3.4.22|间接依赖|maven|
|org.apache.sshd:sshd-common|2.8.0|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|直接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|9.8.1|间接依赖|maven|
|io.fabric8:kubernetes-model-policy|6.0.0|间接依赖|maven|
|org.datanucleus:javax.jdo|3.2.0-m3|间接依赖|maven|
|com.google.cloud:google-cloud-core-grpc|2.10.0|间接依赖|maven|
|net.sf.opencsv:opencsv|2.3|间接依赖|maven|
|org.apache.hive:hive-metastore|2.3.9|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.3|直接依赖|maven|
|com.google.auth:google-auth-library-oauth2-http|1.15.0|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-db2|dev-SNAPSHOT|直接依赖|maven|
|io.grpc:grpc-auth|1.41.0|间接依赖|maven|
|org.springframework:spring-beans|5.3.22|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-trino|dev-SNAPSHOT|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-jetty|2.7.3|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-ssh|dev-SNAPSHOT|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-databend|dev-SNAPSHOT|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-flink-stream|dev-SNAPSHOT|直接依赖|maven|
|software.amazon.awssdk:profiles|2.17.282|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.7.3|直接依赖|maven|
|org.junit.jupiter:junit-jupiter-api|5.8.2|直接依赖|maven|
|com.google.api:gax|2.23.0|间接依赖|maven|
|org.threeten:threetenbp|1.6.5|间接依赖|maven|
|net.java.dev.jna:jna|5.5.0|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.3.Final|间接依赖|maven|
|org.springframework.boot:spring-boot|2.7.3|间接依赖|maven|
|io.netty:netty-codec-http|4.1.53.Final|间接依赖|maven|
|software.amazon.awssdk:auth|2.17.282|间接依赖|maven|
|com.squareup.okhttp3:logging-interceptor|3.12.12|间接依赖|maven|
|com.sun.jersey:jersey-core|1.19|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-common|3.2.4|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-registry-jdbc|dev-SNAPSHOT|直接依赖|maven|
|com.alibaba:druid|1.2.4|直接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|net.jodah:failsafe|2.4.4|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-api|9.4.48.v20220622|间接依赖|maven|
|io.fabric8:kubernetes-model-core|5.10.2|间接依赖|maven|
|software.amazon.awssdk:netty-nio-client|2.17.282|间接依赖|maven|
|org.springframework:spring-jcl|5.3.22|间接依赖|maven|
|org.springframework:spring-core|5.3.22|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-alert-all|dev-SNAPSHOT|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-alert-script|dev-SNAPSHOT|直接依赖|maven|
|software.amazon.awssdk:metrics-spi|2.17.282|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|3.2.4|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-eventhubs|2.21.0|间接依赖|maven|
|com.google.api.grpc:gapic-google-cloud-storage-v2|2.18.0-alpha|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-cache|2.7.3|直接依赖|maven|
|io.gsonfire:gson-fire|1.8.5|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-dms|dev-SNAPSHOT|直接依赖|maven|
|org.checkerframework:checker-qual|3.19.0|间接依赖|maven|
|org.apache.kerby:kerb-util|1.0.1|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-alert-http|dev-SNAPSHOT|直接依赖|maven|
|com.github.rholder:guava-retrying|2.0.0|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-alert-api|dev-SNAPSHOT|直接依赖|maven|
|software.amazon.awssdk:datasync|2.17.282|直接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|org.codehaus.janino:commons-compiler|3.1.7|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-kubeflow|dev-SNAPSHOT|直接依赖|maven|
|org.apache.logging.log4j:log4j-1.2-api|2.17.2|间接依赖|maven|
|org.zeroturnaround:zt-zip|1.15|直接依赖|maven|
|io.opentracing:opentracing-noop|0.33.0|间接依赖|maven|
|commons-logging:commons-logging|1.1.1|间接依赖|maven|
|io.grpc:grpc-netty-shaded|1.41.0|间接依赖|maven|
|io.fabric8:kubernetes-model-core|6.0.0|间接依赖|maven|
|javax.transaction:jta|1.1|间接依赖|maven|
|io.fabric8:kubernetes-model-node|5.10.2|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-authorization|2.21.0|间接依赖|maven|
|org.casbin:casdoor-spring-boot-starter|1.6.0|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-k8s|dev-SNAPSHOT|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-alert-wechat|dev-SNAPSHOT|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-dao|dev-SNAPSHOT|直接依赖|maven|
|com.amazonaws:aws-java-sdk-s3|1.12.300|直接依赖|maven|
|io.grpc:grpc-services|1.41.0|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.69|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|com.jolbox:bonecp|0.8.0.RELEASE|间接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|9.10|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-alert-webexteams|dev-SNAPSHOT|直接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.9.2|间接依赖|maven|
|com.amazonaws:jmespath-java|1.12.300|间接依赖|maven|
|io.perfmark:perfmark-api|0.23.0|间接依赖|maven|
|io.micrometer:micrometer-registry-prometheus|1.9.3|直接依赖|maven|
|com.google.http-client:google-http-client-appengine|1.42.3|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-datafactory|1.0.0-beta.19|直接依赖|maven|
|com.google.guava:guava|31.1-jre|直接依赖|maven|
|com.google.cloud:google-cloud-core-http|2.10.0|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-dinky|dev-SNAPSHOT|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-storage-gcs|dev-SNAPSHOT|直接依赖|maven|
|io.netty:netty-tcnative-boringssl-static|2.0.53.Final|间接依赖|maven|
|org.apache.commons:commons-text|1.4|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|3.2.4|间接依赖|maven|
|org.checkerframework:checker-qual|3.12.0|间接依赖|maven|
|io.grpc:grpc-core|1.41.0|间接依赖|maven|
|io.fabric8:kubernetes-model-flowcontrol|6.0.0|间接依赖|maven|
|org.webjars:webjars-locator-core|0.50|间接依赖|maven|
|com.google.api:gax-httpjson|0.108.0|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|io.swagger.core.v3:swagger-core|2.2.0|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-shell|dev-SNAPSHOT|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-api|dev-SNAPSHOT|直接依赖|maven|
|io.netty:netty-transport|4.1.53.Final|间接依赖|maven|
|com.baomidou:mybatis-plus-annotation|3.5.2|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-containerinstance|2.21.0|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.11|直接依赖|maven|
|io.fabric8:kubernetes-model-certificates|5.10.2|间接依赖|maven|
|org.apache.kerby:kerb-core|1.0.1|间接依赖|maven|
|javax.servlet.jsp:jsp-api|2.1|间接依赖|maven|
|org.apache.commons:commons-math3|3.1.1|间接依赖|maven|
|org.apache.hive:hive-service-rpc|2.3.9|间接依赖|maven|
|io.netty:netty-buffer|4.1.53.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator|2.7.3|直接依赖|maven|
|org.apache.commons:commons-collections4|4.3|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-storage-abs|dev-SNAPSHOT|直接依赖|maven|
|io.netty:netty-handler|4.1.53.Final|间接依赖|maven|
|org.quartz-scheduler:quartz|2.3.2|直接依赖|maven|
|com.sun.xml.bind:jaxb-impl|2.2.3-1|间接依赖|maven|
|io.fabric8:kubernetes-model-networking|6.0.0|间接依赖|maven|
|io.fabric8:kubernetes-model-flowcontrol|5.10.2|间接依赖|maven|
|org.yaml:snakeyaml|1.30|间接依赖|maven|
|io.opencensus:opencensus-contrib-http-util|0.31.1|间接依赖|maven|
|org.eclipse.jetty:jetty-xml|9.4.48.v20220622|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-cdn|2.21.0|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.17.2|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-alert-telegram|dev-SNAPSHOT|直接依赖|maven|
|org.eclipse.jetty:jetty-continuation|9.4.48.v20220622|间接依赖|maven|
|com.dameng:DmJdbcDriver18|8.1.2.79|直接依赖|maven|
|io.fabric8:kubernetes-model-coordination|5.10.2|间接依赖|maven|
|com.microsoft.sqlserver:mssql-jdbc|11.2.1.jre8|直接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.67|间接依赖|maven|
|org.apache.commons:commons-compress|1.21|间接依赖|maven|
|com.github.jsqlparser:jsqlparser|4.4|间接依赖|maven|
|io.fabric8:kubernetes-model-common|6.0.0|间接依赖|maven|
|org.apache.kerby:kerb-admin|1.0.1|间接依赖|maven|
|org.openjdk.jmh:jmh-core|1.21|直接依赖|maven|
|org.webjars:swagger-ui|4.11.1|间接依赖|maven|
|net.sf.jopt-simple:jopt-simple|4.6|间接依赖|maven|
|joda-time:joda-time|2.10.13|间接依赖|maven|
|com.baomidou:mybatis-plus-boot-starter|3.5.2|直接依赖|maven|
|org.eclipse.jetty:jetty-util-ajax|9.4.48.v20220622|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-hivecli|dev-SNAPSHOT|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|直接依赖|maven|
|org.ow2.asm:asm|9.1|间接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.53.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.3|间接依赖|maven|
|net.sf.py4j:py4j|0.10.9|直接依赖|maven|
|org.bouncycastle:bcutil-jdk15on|1.69|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-vertica|dev-SNAPSHOT|直接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|org.apache.hive:hive-storage-api|2.4.0|间接依赖|maven|
|org.apache.hive:hive-service|2.3.9|间接依赖|maven|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13|间接依赖|maven|
|com.databend:databend-jdbc|0.0.7|直接依赖|maven|
|org.eclipse.jetty.websocket:websocket-client|9.4.48.v20220622|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.53.Final|间接依赖|maven|
|org.apache.zeppelin:zeppelin-common|0.10.1|间接依赖|maven|
|io.fabric8:kubernetes-model-autoscaling|5.10.2|间接依赖|maven|
|com.github.vladimir-bukhtoyarov:bucket4j-core|6.2.0|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-alert-server|dev-SNAPSHOT|直接依赖|maven|
|org.apache.kerby:kerb-client|1.0.1|间接依赖|maven|
|io.fabric8:kubernetes-model-networking|5.10.2|间接依赖|maven|
|org.apache.curator:curator-test|5.3.0|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-storage-hdfs|dev-SNAPSHOT|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-tools|dev-SNAPSHOT|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.13|间接依赖|maven|
|org.apache.commons:commons-text|1.8|间接依赖|maven|
|org.apache.parquet:parquet-hadoop-bundle|1.8.1|间接依赖|maven|
|io.fabric8:kubernetes-model-rbac|5.10.2|间接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|间接依赖|maven|
|org.springframework:spring-expression|5.3.22|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.67|间接依赖|maven|
|org.springframework.cloud:spring-cloud-context|3.1.3|间接依赖|maven|
|com.azure:azure-storage-file-share|12.17.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.4.10|间接依赖|maven|
|io.netty:netty-tcnative-classes|2.0.53.Final|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|直接依赖|maven|
|io.fabric8:kubernetes-model-apps|5.10.2|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.3|间接依赖|maven|
|org.apache.kerby:kerby-pkix|1.0.1|间接依赖|maven|
|com.sun.jersey:jersey-json|1.19|间接依赖|maven|
|org.springdoc:springdoc-openapi-common|1.6.9|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-keyvault|2.21.0|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-spark|dev-SNAPSHOT|直接依赖|maven|
|com.github.virtuald:curvesapi|1.06|间接依赖|maven|
|joda-time:joda-time|2.8.1|间接依赖|maven|
|io.netty:netty-tcnative|2.0.48.Final|间接依赖|maven|
|io.kubernetes:client-java-extended|13.0.2|间接依赖|maven|
|javax.jdo:jdo-api|3.0.1|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-alert-slack|dev-SNAPSHOT|直接依赖|maven|
|io.grpc:grpc-netty|1.41.0|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.3|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-core|3.2.4|间接依赖|maven|
|org.aspectj:aspectjrt|1.9.7|直接依赖|maven|
|io.fabric8:kubernetes-model-coordination|6.0.0|间接依赖|maven|
|com.sun.jersey:jersey-servlet|1.19|间接依赖|maven|
|io.fabric8:kubernetes-model-events|5.10.2|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-storage-s3|dev-SNAPSHOT|直接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|5.3.0|间接依赖|maven|
|com.h2database:h2|2.2.220|直接依赖|maven|
|com.azure:azure-security-keyvault-secrets|4.5.4|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager|2.21.0|直接依赖|maven|
|org.apache.kerby:kerby-xdr|1.0.1|间接依赖|maven|
|org.apache.kerby:kerb-server|1.0.1|间接依赖|maven|
|org.apache.avro:avro|1.7.7|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-kyuubi|dev-SNAPSHOT|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-sqlserver|dev-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.4|直接依赖|maven|
|org.mybatis:mybatis-spring|2.0.7|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-python|dev-SNAPSHOT|直接依赖|maven|
|net.minidev:accessors-smart|2.4.7|间接依赖|maven|
|org.apache.curator:curator-framework|5.3.0|直接依赖|maven|
|org.junit.platform:junit-platform-commons|1.8.2|间接依赖|maven|
|com.azure:azure-core-http-netty|1.13.0|间接依赖|maven|
|com.amazonaws:aws-java-sdk-kms|1.12.300|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|com.amazonaws:aws-java-sdk-core|1.12.300|间接依赖|maven|
|org.conscrypt:conscrypt-openjdk-uber|2.5.2|间接依赖|maven|
|net.java.dev.jna:jna|5.10.0|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-kms|2.11.0|间接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.48.v20220622|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-jupyter|dev-SNAPSHOT|直接依赖|maven|
|org.apache.poi:poi-ooxml|4.1.2|直接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.69|间接依赖|maven|
|com.google.api:gax-grpc|2.23.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.6.21|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-appservice|2.21.0|间接依赖|maven|
|io.fabric8:kubernetes-model-admissionregistration|6.0.0|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.10.1|直接依赖|maven|
|net.snowflake:snowflake-jdbc|3.13.29|直接依赖|maven|
|io.kubernetes:client-java-api-fluent|13.0.2|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.65|间接依赖|maven|
|org.springframework.cloud:spring-cloud-kubernetes-client-autoconfig|2.1.3|间接依赖|maven|
|org.apache.oltu.oauth2:org.apache.oltu.oauth2.client|1.0.2|间接依赖|maven|
|org.apache.kerby:token-provider|1.0.1|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-core|4.5.10|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-sql|2.21.0|间接依赖|maven|
|com.cronutils:cron-utils|9.1.6|直接依赖|maven|
|com.zaxxer:SparseBitSet|1.2|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-storage-obs|dev-SNAPSHOT|直接依赖|maven|
|org.springframework.cloud:spring-cloud-commons|3.1.3|间接依赖|maven|
|io.netty:netty-common|4.1.53.Final|间接依赖|maven|
|com.sun.jersey.contribs:jersey-guice|1.19|间接依赖|maven|
|org.apache.oltu.oauth2:org.apache.oltu.oauth2.common|1.0.2|间接依赖|maven|
|commons-io:commons-io|2.11.0|直接依赖|maven|
|ch.qos.logback:logback-core|1.2.11|直接依赖|maven|
|org.codehaus.woodstox:stax2-api|4.2.1|间接依赖|maven|
|io.fabric8:kubernetes-httpclient-okhttp|6.0.0|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.9.3|直接依赖|maven|
|com.github.oshi:oshi-core|6.1.1|直接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.9.13|间接依赖|maven|
|com.google.cloud:google-cloud-core|2.10.0|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-zeppelin|dev-SNAPSHOT|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.15|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-datax|dev-SNAPSHOT|直接依赖|maven|
|io.fabric8:kubernetes-client-api|6.0.0|间接依赖|maven|
|ch.qos.reload4j:reload4j|1.2.18.3|间接依赖|maven|
|com.huaweicloud:esdk-obs-java-bundle|3.23.3|直接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|2.0.1|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-extract-base|dev-SNAPSHOT|直接依赖|maven|
|com.google.auto.value:auto-value|1.10.1|间接依赖|maven|
|org.eclipse.jetty:jetty-server|9.4.48.v20220622|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.8.0|直接依赖|maven|
|org.springframework:spring-jdbc|5.3.22|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-search|2.21.0|间接依赖|maven|
|io.opencensus:opencensus-proto|0.2.0|间接依赖|maven|
|org.glassfish:javax.el|3.0.0|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-scheduler-all|dev-SNAPSHOT|直接依赖|maven|
|io.fabric8:kubernetes-model-apiextensions|5.10.2|间接依赖|maven|
|com.google.api.grpc:proto-google-iam-v1|1.9.0|间接依赖|maven|
|io.fabric8:kubernetes-model-events|6.0.0|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-registry-zookeeper|dev-SNAPSHOT|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-registry-all|dev-SNAPSHOT|直接依赖|maven|
|org.eclipse.jetty:jetty-security|9.4.48.v20220622|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.4|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-network|2.21.0|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-java|dev-SNAPSHOT|直接依赖|maven|
|org.apache.sshd:sshd-scp|2.8.0|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-dameng|dev-SNAPSHOT|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-api|dev-SNAPSHOT|直接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|6.4.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-actuator|2.7.3|直接依赖|maven|
|org.checkerframework:checker-qual|3.5.0|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-storage-all|dev-SNAPSHOT|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-mysql|dev-SNAPSHOT|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-storage-oss|dev-SNAPSHOT|直接依赖|maven|
|net.minidev:json-smart|2.4.7|间接依赖|maven|
|io.fabric8:kubernetes-model-batch|5.10.2|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-emr|dev-SNAPSHOT|直接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-kubernetes-client-config|2.1.3|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-sql|dev-SNAPSHOT|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-doris|dev-SNAPSHOT|直接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-spi|dev-SNAPSHOT|直接依赖|maven|
|org.apache.commons:commons-email|1.5|直接依赖|maven|
|com.konghq:unirest-java|3.7.04|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.2.2.Final|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.3|间接依赖|maven|
|com.jcraft:jsch|0.1.55|间接依赖|maven|
|io.grpc:grpc-api|1.41.0|间接依赖|maven|
|io.fabric8:kubernetes-model-storageclass|5.10.2|间接依赖|maven|
|io.fabric8:kubernetes-model-common|5.10.2|间接依赖|maven|
|com.github.stephenc.jcip:jcip-annotations|1.0-1|间接依赖|maven|
|com.google.apis:google-api-services-storage|v1-rev20220705-2.0.0|间接依赖|maven|
|org.apache.curator:curator-recipes|5.3.0|直接依赖|maven|
|io.netty:netty-codec-http2|4.1.53.Final|间接依赖|maven|
|com.baomidou:mybatis-plus-core|3.5.2|间接依赖|maven|
|io.fabric8:kubernetes-model-rbac|6.0.0|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-azure-sql|dev-SNAPSHOT|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-dataquality|dev-SNAPSHOT|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-pytorch|dev-SNAPSHOT|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-containerservice|2.21.0|间接依赖|maven|
|org.apache.kyuubi:kyuubi-hive-jdbc-shaded|1.7.0|直接依赖|maven|
|io.fabric8:kubernetes-model-autoscaling|6.0.0|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-scheduler-quartz|dev-SNAPSHOT|直接依赖|maven|
|com.google.re2j:re2j|1.6|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-containerregistry|2.21.0|间接依赖|maven|
|io.fabric8:kubernetes-model-discovery|5.10.2|间接依赖|maven|
|net.minidev:accessors-smart|2.4.8|间接依赖|maven|
|org.apache.kerby:kerby-util|1.0.1|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-master|dev-SNAPSHOT|直接依赖|maven|
|org.apache.curator:curator-client|5.3.0|直接依赖|maven|
|com.google.api.grpc:proto-google-cloud-storage-v2|2.18.0-alpha|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-msi|2.21.0|间接依赖|maven|
|com.google.protobuf:protobuf-java-util|3.17.2|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-procedure|dev-SNAPSHOT|直接依赖|maven|
|io.prometheus:simpleclient|0.15.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.4.0|间接依赖|maven|
|commons-pool:commons-pool|1.6|间接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|io.netty:netty-resolver|4.1.53.Final|间接依赖|maven|
|software.amazon.awssdk:http-client-spi|2.17.282|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-seatunnel|dev-SNAPSHOT|直接依赖|maven|
|org.datanucleus:datanucleus-rdbms|4.1.19|间接依赖|maven|
|org.datanucleus:datanucleus-core|4.1.17|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-service|dev-SNAPSHOT|直接依赖|maven|
|org.springframework.cloud:spring-cloud-kubernetes-commons|2.1.3|间接依赖|maven|
|org.opentest4j:opentest4j|1.2.0|间接依赖|maven|
|org.apache.kerby:kerb-identity|1.0.1|间接依赖|maven|
|org.apache.hadoop:hadoop-auth|3.2.4|间接依赖|maven|
|io.fabric8:kubernetes-model-batch|6.0.0|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.13.3|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|4.2.11|直接依赖|maven|
|com.google.http-client:google-http-client-gson|1.42.3|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.79.Final|间接依赖|maven|
|dnsjava:dnsjava|2.1.7|间接依赖|maven|
|org.postgresql:postgresql|42.4.1|直接依赖|maven|
|io.netty:netty-all|4.1.53.Final|直接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|间接依赖|maven|
|co.cask.tephra:tephra-api|0.6.0|间接依赖|maven|
|com.nimbusds:content-type|2.2|间接依赖|maven|
|io.fabric8:kubernetes-model-certificates|6.0.0|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-data-quality|dev-SNAPSHOT|直接依赖|maven|
|io.kubernetes:client-java-proto|13.0.2|间接依赖|maven|
|org.springframework:spring-context|5.3.22|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-oceanbase|dev-SNAPSHOT|直接依赖|maven|
|io.prometheus:simpleclient_common|0.15.0|间接依赖|maven|
|stax:stax-api|1.0.1|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-datasync|dev-SNAPSHOT|直接依赖|maven|
|com.clickhouse:clickhouse-jdbc|0.4.6|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-resources|2.21.0|间接依赖|maven|
|software.amazon.awssdk:json-utils|2.17.282|间接依赖|maven|
|com.squareup.okio:okio|2.8.0|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-http|1.0.22|间接依赖|maven|
|io.grpc:grpc-context|1.41.0|间接依赖|maven|
|org.yaml:snakeyaml|1.33|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-mlflow|dev-SNAPSHOT|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.6.21|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-remoteshell|dev-SNAPSHOT|直接依赖|maven|
|org.springframework:spring-tx|5.3.22|间接依赖|maven|
|org.springframework:spring-context-support|5.3.22|间接依赖|maven|
|io.prometheus:simpleclient_httpserver|0.15.0|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-sagemaker|dev-SNAPSHOT|直接依赖|maven|
|org.apache.kerby:kerb-crypto|1.0.1|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-all|dev-SNAPSHOT|直接依赖|maven|
|software.amazon.awssdk:aws-core|2.17.282|间接依赖|maven|
|org.codehaus.jackson:jackson-jaxrs|1.9.2|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-cosmos|2.21.0|间接依赖|maven|
|org.bouncycastle:bcprov-ext-jdk15on|1.69|间接依赖|maven|
|io.grpc:grpc-stub|1.41.0|间接依赖|maven|
|org.codehaus.janino:janino|3.0.16|直接依赖|maven|
|org.springframework.security:spring-security-rsa|1.0.10.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-xml|2.13.3|间接依赖|maven|
|io.opentracing:opentracing-api|0.33.0|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-common|9.4.48.v20220622|间接依赖|maven|
|io.fabric8:kubernetes-model-policy|5.10.2|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-all|dev-SNAPSHOT|直接依赖|maven|
|software.amazon.awssdk:annotations|2.17.282|间接依赖|maven|
|org.apache.kerby:kerb-common|1.0.1|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-snowflake|dev-SNAPSHOT|直接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|jakarta.websocket:jakarta.websocket-api|1.1.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|2.7.3|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-starrocks|dev-SNAPSHOT|直接依赖|maven|
|commons-codec:commons-codec|1.11|直接依赖|maven|
|com.google.api:api-common|2.6.0|间接依赖|maven|
|org.apache.hadoop:hadoop-hdfs-client|3.2.4|间接依赖|maven|
|io.fabric8:kubernetes-model-apps|6.0.0|间接依赖|maven|
|com.amazonaws:aws-java-sdk-emr|1.12.300|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-worker|dev-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.13.3|间接依赖|maven|
|com.squareup.okhttp:okhttp|2.7.5|间接依赖|maven|
|com.baomidou:mybatis-plus-extension|3.5.2|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.6.21|间接依赖|maven|
|org.springdoc:springdoc-openapi-webmvc-core|1.6.9|间接依赖|maven|
|com.azure:azure-core-management|1.10.1|间接依赖|maven|
|org.springframework.cloud:spring-cloud-kubernetes-client-config|2.1.3|间接依赖|maven|
|org.apache.thrift:libthrift|0.9.3|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-presto|dev-SNAPSHOT|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|io.fabric8:kubernetes-model-node|6.0.0|间接依赖|maven|
|org.jamon:jamon-runtime|2.3.1|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|com.google.http-client:google-http-client-jackson2|1.42.3|间接依赖|maven|
|net.sf.jpam:jpam|1.1|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-compute|2.21.0|间接依赖|maven|
|org.casbin:casdoor-java-sdk|1.11.0|间接依赖|maven|
|io.grpc:grpc-protobuf|1.41.0|间接依赖|maven|
|io.fabric8:kubernetes-model-discovery|6.0.0|间接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.3|间接依赖|maven|
|commons-cli:commons-cli|1.2|间接依赖|maven|
|io.grpc:grpc-alts|1.41.0|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|直接依赖|maven|
|org.codehaus.jettison:jettison|1.1|间接依赖|maven|
|net.minidev:json-smart|2.4.8|间接依赖|maven|
|com.google.http-client:google-http-client|1.42.3|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-ui|dev-SNAPSHOT|直接依赖|maven|
|commons-net:commons-net|3.6|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.53.Final|间接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.53.Final|间接依赖|maven|
|com.google.cloud:google-cloud-storage|2.18.0|直接依赖|maven|
|org.apache.thrift:libfb303|0.9.3|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-scheduler-api|dev-SNAPSHOT|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-dns|2.21.0|间接依赖|maven|
|io.fabric8:kubernetes-model-apiextensions|6.0.0|间接依赖|maven|
|org.mybatis:mybatis|3.5.10|间接依赖|maven|
|io.fabric8:kubernetes-model-metrics|6.0.0|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-aop|dev-SNAPSHOT|直接依赖|maven|
|org.eclipse.jetty:jetty-http|9.4.48.v20220622|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.53.Final|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-storage|2.21.0|间接依赖|maven|
|software.amazon.awssdk:utils|2.17.282|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-redshift|dev-SNAPSHOT|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-spark|dev-SNAPSHOT|直接依赖|maven|
|javax.servlet:javax.servlet-api|3.1.0|间接依赖|maven|
|org.apache.hive:hive-jdbc|2.3.9|直接依赖|maven|
|org.springframework.ldap:spring-ldap-core|2.4.1|直接依赖|maven|
|org.apache.yetus:audience-annotations|0.12.0|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.0|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-meter|dev-SNAPSHOT|直接依赖|maven|
|software.amazon.awssdk:regions|2.17.282|间接依赖|maven|
|org.eclipse.jetty:jetty-servlets|9.4.48.v20220622|间接依赖|maven|
|javax.activation:activation|1.1|间接依赖|maven|
|javax.ws.rs:jsr311-api|1.1.1|间接依赖|maven|
|com.aliyun.oss:aliyun-sdk-oss|3.15.1|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-redis|2.21.0|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-appplatform|2.21.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.2|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-registry-etcd|dev-SNAPSHOT|直接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.5|间接依赖|maven|
|org.apache.hive:hive-serde|2.3.9|间接依赖|maven|
|com.google.code.gson:gson|2.9.1|间接依赖|maven|
|org.apache.hadoop:hadoop-client|3.2.4|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.3|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.11.0|间接依赖|maven|
|org.springframework.security:spring-security-crypto|5.7.3|间接依赖|maven|
|org.aspectj:aspectjweaver|1.9.7|直接依赖|maven|
|org.apache.kerby:kerby-asn1|1.0.1|间接依赖|maven|
|org.springframework:spring-aop|5.3.22|间接依赖|maven|
|io.etcd:jetcd-common|0.5.11|间接依赖|maven|
|com.nimbusds:oauth2-oidc-sdk|9.35|间接依赖|maven|
|io.swagger.core.v3:swagger-models|2.2.0|间接依赖|maven|
|jline:jline|2.12|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-client|3.2.4|直接依赖|maven|
|commons-dbcp:commons-dbcp|1.4|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-registry-api|dev-SNAPSHOT|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-monitor|2.21.0|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-servicebus|2.21.0|间接依赖|maven|
|com.google.code.gson:gson|2.8.6|间接依赖|maven|
|org.jdom:jdom2|2.0.6.1|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-core|1.0.22|间接依赖|maven|
|io.opencensus:opencensus-api|0.31.1|间接依赖|maven|
|org.springframework.boot:spring-boot-configuration-processor|2.6.1|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-pigeon|dev-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.12.6|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-postgresql|dev-SNAPSHOT|直接依赖|maven|
|io.netty:netty-handler-proxy|4.1.53.Final|间接依赖|maven|
|org.lz4:lz4-java|1.4.0|直接依赖|maven|
|io.prometheus:simpleclient_tracer_otel|0.15.0|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-sqoop|dev-SNAPSHOT|直接依赖|maven|
|org.apache.kerby:kerby-config|1.0.1|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.19|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-alert-feishu|dev-SNAPSHOT|直接依赖|maven|
|com.squareup.okhttp3:okhttp|4.9.3|直接依赖|maven|
|com.microsoft.azure:msal4j|1.13.3|间接依赖|maven|
|org.apache.hbase.thirdparty:hbase-noop-htrace|4.1.1|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.7.3|间接依赖|maven|
|com.google.oauth-client:google-oauth-client|1.34.1|间接依赖|maven|
|com.squareup.okio:okio|1.6.0|间接依赖|maven|
|software.amazon.awssdk:sdk-core|2.17.282|间接依赖|maven|
|com.google.inject:guice|4.0|间接依赖|maven|
|com.google.api-client:google-api-client|2.2.0|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.13.3|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-common|dev-SNAPSHOT|直接依赖|maven|
|software.amazon.awssdk:third-party-jackson-core|2.17.282|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-alert-dingtalk|dev-SNAPSHOT|直接依赖|maven|
|org.apache.zeppelin:zeppelin-client|0.10.1|直接依赖|maven|
|com.amazonaws:aws-java-sdk-sagemaker|1.12.300|直接依赖|maven|
|com.baomidou:mybatis-plus|3.5.2|直接依赖|maven|
|com.vertica.jdbc:vertica-jdbc|12.0.4-0|直接依赖|maven|
|io.grpc:grpc-googleapis|1.52.1|间接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.41.0|间接依赖|maven|
|com.google.auto.value:auto-value-annotations|1.10.1|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|io.etcd:jetcd-core|0.5.11|直接依赖|maven|
|org.apache.zookeeper:zookeeper-jute|3.8.0|间接依赖|maven|
|com.google.inject.extensions:guice-servlet|4.0|间接依赖|maven|
|io.micrometer:micrometer-core|1.9.3|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-standalone-server|dev-SNAPSHOT|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|3.2.4|间接依赖|maven|
|software.amazon.ion:ion-java|1.0.2|间接依赖|maven|
|com.google.auto.service:auto-service-annotations|1.0|间接依赖|maven|
|com.azure:azure-storage-blob|12.21.0|直接依赖|maven|
|com.azure:azure-storage-internal-avro|12.6.0|间接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|9.22|间接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.15|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.7.3|间接依赖|maven|
|com.tdunning:json|1.8|间接依赖|maven|
|org.apache.commons:commons-configuration2|2.1.1|间接依赖|maven|
|org.apache.sshd:sshd-sftp|2.8.0|直接依赖|maven|
|com.google.api.grpc:grpc-google-cloud-storage-v2|2.18.0-alpha|间接依赖|maven|
|io.github.classgraph:classgraph|4.8.147|间接依赖|maven|
|org.apache.hadoop:hadoop-common|3.2.4|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-alert-email|dev-SNAPSHOT|直接依赖|maven|
|jakarta.servlet:jakarta.servlet-api|4.0.4|间接依赖|maven|
|org.apache.sshd:sshd-core|2.8.0|间接依赖|maven|
|com.google.auth:google-auth-library-credentials|1.15.0|间接依赖|maven|
|org.springframework:spring-web|5.3.22|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-http|dev-SNAPSHOT|直接依赖|maven|
|org.eclipse.jetty:jetty-webapp|9.4.48.v20220622|间接依赖|maven|
|net.java.dev.jna:jna-platform|5.6.0|间接依赖|maven|
|org.eclipse.jetty:jetty-client|9.4.48.v20220622|间接依赖|maven|
|org.apache.httpcomponents:httpmime|4.5.13|间接依赖|maven|
|io.grpc:grpc-xds|1.41.0|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-trafficmanager|2.21.0|间接依赖|maven|
|io.prometheus:simpleclient_tracer_common|0.15.0|间接依赖|maven|
|javax.transaction:transaction-api|1.1|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.6.21|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.13.3|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-alert-pagerduty|dev-SNAPSHOT|直接依赖|maven|
|com.amazonaws:aws-java-sdk-dms|1.12.300|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-openmldb|dev-SNAPSHOT|直接依赖|maven|
|io.fabric8:kubernetes-client|6.0.0|直接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.2|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-clickhouse|dev-SNAPSHOT|直接依赖|maven|
|net.java.dev.jna:jna-platform|5.10.0|间接依赖|maven|
|org.bitbucket.b_c:jose4j|0.7.8|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-storage-api|dev-SNAPSHOT|直接依赖|maven|
|com.sun.jersey:jersey-server|1.19|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-mr|dev-SNAPSHOT|直接依赖|maven|
|org.apache.hive:hive-common|2.3.9|间接依赖|maven|
|org.checkerframework:checker-qual|3.30.0|间接依赖|maven|
|org.apache.poi:poi-ooxml-schemas|4.1.2|间接依赖|maven|
|com.flipkart.zjsonpatch:zjsonpatch|0.4.11|间接依赖|maven|
|io.kubernetes:client-java-spring-integration|13.0.2|间接依赖|maven|
|software.amazon.awssdk:protocol-core|2.17.282|间接依赖|maven|
|org.apiguardian:apiguardian-api|1.1.2|间接依赖|maven|
|com.microsoft.azure:msal4j-persistence-extension|1.1.0|间接依赖|maven|
|software.amazon.eventstream:eventstream|1.0.1|间接依赖|maven|
|io.fabric8:zjsonpatch|0.3.0|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.7.3|间接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-flink|dev-SNAPSHOT|直接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.4.48.v20220622|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.5.1|间接依赖|maven|
|com.azure:azure-security-keyvault-keys|4.5.4|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.7.3|间接依赖|maven|
|com.nimbusds:lang-tag|1.6|间接依赖|maven|
|com.google.re2j:re2j|1.1|间接依赖|maven|
|com.facebook.presto:presto-jdbc|0.238.1|直接依赖|maven|
|org.ini4j:ini4j|0.5.4|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-linkis|dev-SNAPSHOT|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-quartz|2.7.3|直接依赖|maven|
|io.fabric8:kubernetes-model-extensions|6.0.0|间接依赖|maven|
|commons-lang:commons-lang|2.6|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.53.Final|间接依赖|maven|
|io.grpc:grpc-grpclb|1.41.0|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-extract-alert|dev-SNAPSHOT|直接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-datafactory|dev-SNAPSHOT|直接依赖|maven|
|com.squareup.okhttp3:logging-interceptor|4.9.3|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-jobclient|3.2.4|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-bootstrap|3.1.3|间接依赖|maven|
|io.swagger:swagger-annotations|1.6.2|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-task-dvc|dev-SNAPSHOT|直接依赖|maven|
|org.springdoc:springdoc-openapi-ui|1.6.9|直接依赖|maven|
|com.aliyun:aliyun-java-sdk-ram|3.1.0|间接依赖|maven|
|org.apache.dolphinscheduler:dolphinscheduler-datasource-athena|dev-SNAPSHOT|直接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|io.opentracing:opentracing-util|0.33.0|间接依赖|maven|
|org.apache.poi:poi|4.1.2|直接依赖|maven|
|software.amazon.awssdk:apache-client|2.17.282|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)