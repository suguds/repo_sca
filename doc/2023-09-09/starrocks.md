# StarRocks/starrocks安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700208053516550144.svg)](https://www.murphysec.com/console/report/1676668594989121536/1700208053516550144)

仓库描述：StarRocks, a Linux Foundation project, is a next-generation sub-second MPP OLAP database for full analytics scenarios, including multi-dimensional analytics, real-time analytics, and ad-hoc queries.

仓库地址：[https://github.com/StarRocks/starrocks](https://github.com/StarRocks/starrocks)

| star：5341 | watch：127 | fork：1141 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-09 02:01:32 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-09 02:49:37 | 组件总数：705 | 漏洞总数：85 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache HttpClient 中间人攻击漏洞|对宿主不匹配的证书验证不恰当|[MPS-2014-4112](https://www.oscs1024.com/hd/MPS-2014-4112)|CVE-2014-3577|中危|
|Apache HttpClient 中间人攻击漏洞|输入验证不恰当|[MPS-2014-4288](https://www.oscs1024.com/hd/MPS-2014-4288)|CVE-2012-6153|中危|
|Apache Hadoop 后置链接漏洞|未授权敏感信息泄露|[MPS-2014-7381](https://www.oscs1024.com/hd/MPS-2014-7381)|CVE-2014-3627|中危|
|Eclipse Jetty 信息泄露漏洞|未授权敏感信息泄露|[MPS-2016-5010](https://www.oscs1024.com/hd/MPS-2016-5010)|CVE-2015-2080|高危|
|Google protobuf 缓冲区错误漏洞|越界写入|[MPS-2017-10841](https://www.oscs1024.com/hd/MPS-2017-10841)|CVE-2015-5237|高危|
|Apache Zookeeper 安全漏洞||[MPS-2017-11297](https://www.oscs1024.com/hd/MPS-2017-11297)|CVE-2017-5637|高危|
|Apache Tomcat SecurityManager绕过漏洞|访问控制不当|[MPS-2017-9011](https://www.oscs1024.com/hd/MPS-2017-9011)|CVE-2016-5018|严重|
|Apache Tomcat 访问限制绕过漏洞|访问控制不当|[MPS-2017-9027](https://www.oscs1024.com/hd/MPS-2017-9027)|CVE-2016-6796|高危|
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|Apache Derby 权限许可和访问控制问题漏洞|访问控制不当|[MPS-2018-5754](https://www.oscs1024.com/hd/MPS-2018-5754)|CVE-2018-1313|中危|
|Apache Zookeeper 访问控制错误漏洞|授权检查缺失|[MPS-2018-6313](https://www.oscs1024.com/hd/MPS-2018-6313)|CVE-2018-8012|高危|
|Apache Thrift <0.12.0 绕过验证漏洞|证书验证不恰当|[MPS-2019-0104](https://www.oscs1024.com/hd/MPS-2019-0104)|CVE-2018-1320|高危|
|Netty 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2019-12064](https://www.oscs1024.com/hd/MPS-2019-12064)|CVE-2019-16869|高危|
|Red Hat JBoss Enterprise Application Platform 代码问题漏洞|反序列化|[MPS-2019-12470](https://www.oscs1024.com/hd/MPS-2019-12470)|CVE-2019-10202|严重|
|jackson-mapper-asl <=1.9.13 XXE 注入漏洞|XXE|[MPS-2019-15048](https://www.oscs1024.com/hd/MPS-2019-15048)|CVE-2019-10172|高危|
|Apache Zookeeper 授权问题漏洞|授权检查缺失|[MPS-2019-5668](https://www.oscs1024.com/hd/MPS-2019-5668)|CVE-2019-0201|中危|
|Junit 信息泄露漏洞|不安全的临时文件|[MPS-2020-15183](https://www.oscs1024.com/hd/MPS-2020-15183)|CVE-2020-15250|中危|
|Apache HttpClient URI解析错误漏洞|XSS|[MPS-2020-17341](https://www.oscs1024.com/hd/MPS-2020-17341)|CVE-2020-13956|中危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Bouncy Castle 认证绕过漏洞|使用错误因素进行比较|[MPS-2020-17843](https://www.oscs1024.com/hd/MPS-2020-17843)|CVE-2020-28052|高危|
|Apache Log4j2 SmtpAppender证书验证不当漏洞|证书验证不恰当|[MPS-2020-6684](https://www.oscs1024.com/hd/MPS-2020-6684)|CVE-2020-9488|低危|
|Apache Ant 临时文件不安全问题|将资源暴露给错误范围|[MPS-2020-7418](https://www.oscs1024.com/hd/MPS-2020-7418)|CVE-2020-1945|中危|
|Elasticsearch 内存泄漏漏洞|通过错误消息导致的信息暴露|[MPS-2021-10656](https://www.oscs1024.com/hd/MPS-2021-10656)|CVE-2021-22145|中危|
|Eclipse Jetty 编码字符敏感信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-10800](https://www.oscs1024.com/hd/MPS-2021-10800)|CVE-2021-34429|中危|
|JetBrains Kotlin <1.4.21 不正确的默认权限漏洞|缺省权限不正确|[MPS-2021-1082](https://www.oscs1024.com/hd/MPS-2021-1082)|CVE-2020-29582|中危|
|Elasticsearch 资源管理错误漏洞|未经控制的递归|[MPS-2021-11043](https://www.oscs1024.com/hd/MPS-2021-11043)|CVE-2021-22144|中危|
|Netty <4.1.59.Final 存在不安全的临时文件漏洞||[MPS-2021-1580](https://www.oscs1024.com/hd/MPS-2021-1580)|CVE-2021-21290|中危|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|FasterXML jackson-dataformat-cbor 内存耗尽漏洞|不加限制或调节的资源分配|[MPS-2021-1998](https://www.oscs1024.com/hd/MPS-2021-1998)|CVE-2020-28491|高危|
|Elasticsearch 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-2736](https://www.oscs1024.com/hd/MPS-2021-2736)|CVE-2021-22134|中危|
|Apache Commons Net <3.9.0 存在FTP跳转攻击漏洞|未授权敏感信息泄露|[MPS-2021-28440](https://www.oscs1024.com/hd/MPS-2021-28440)|CVE-2021-37533|中危|
|Apache Log4j JMSAppender反序列化漏洞||[MPS-2021-38359](https://www.oscs1024.com/hd/MPS-2021-38359)|CVE-2021-4104|高危|
|Eclipse Jetty 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-55442](https://www.oscs1024.com/hd/MPS-2021-55442)|CVE-2021-34429|中危|
|Elasticsearch 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-6747](https://www.oscs1024.com/hd/MPS-2021-6747)|CVE-2021-22137|中危|
|Elasticsearch 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-6749](https://www.oscs1024.com/hd/MPS-2021-6749)|CVE-2021-22135|中危|
|Bouncy Castle 私钥信息泄露漏洞|竞争条件|[MPS-2021-7064](https://www.oscs1024.com/hd/MPS-2021-7064)|CVE-2020-15522|中危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9827](https://www.oscs1024.com/hd/MPS-2021-9827)|CVE-2021-36373|中危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9847](https://www.oscs1024.com/hd/MPS-2021-9847)|CVE-2021-36374|中危|
|Red Hat XNIO 资源错误分配漏洞|不加限制或调节的资源分配|[MPS-2022-0191](https://www.oscs1024.com/hd/MPS-2022-0191)|CVE-2022-0084|高危|
|Fastjson < 1.2.83 任意代码执行漏洞|反序列化|[MPS-2022-11320](https://www.oscs1024.com/hd/MPS-2022-11320)|CVE-2022-25845|高危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|Apache HttpClient URI解析错误漏洞|相对路径遍历|[MPS-2022-12292](https://www.oscs1024.com/hd/MPS-2022-12292)||中危|
|Apache Hadoop < 2.7.3 存在CSRF漏洞|CSRF|[MPS-2022-12308](https://www.oscs1024.com/hd/MPS-2022-12308)||中危|
|Apache Log4j JDBCAppender SQL注入漏洞|SQL注入|[MPS-2022-1444](https://www.oscs1024.com/hd/MPS-2022-1444)|CVE-2022-23305|严重|
|Apache Log4j Chainsaw反序列化漏洞|反序列化|[MPS-2022-1445](https://www.oscs1024.com/hd/MPS-2022-1445)|CVE-2022-23307|高危|
|Apache Log4j 反序列化漏洞|反序列化|[MPS-2022-1446](https://www.oscs1024.com/hd/MPS-2022-1446)|CVE-2022-23302|高危|
|Eclipse Jetty URI注入漏洞|注入|[MPS-2022-18060](https://www.oscs1024.com/hd/MPS-2022-18060)|CVE-2022-2047|低危|
|Elastic Stack Kibana 存在缺少授权漏洞|授权检查缺失|[MPS-2022-2136](https://www.oscs1024.com/hd/MPS-2022-2136)|CVE-2022-23709|中危|
|Elastic Stack Kibana 存在 XSS 漏洞|XSS|[MPS-2022-2137](https://www.oscs1024.com/hd/MPS-2022-2137)|CVE-2022-23710|中危|
|JetBrains Kotlin <1.6.0 存在锁定不当漏洞|加锁机制不恰当|[MPS-2022-3233](https://www.oscs1024.com/hd/MPS-2022-3233)|CVE-2022-24329|中危|
|Bouncy Castle <1.69 认证绕过漏洞|密码学问题|[MPS-2022-54305](https://www.oscs1024.com/hd/MPS-2022-54305)||中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|XStream 缓冲区错误漏洞|输入验证不恰当|[MPS-2022-57061](https://www.oscs1024.com/hd/MPS-2022-57061)|CVE-2022-40156|低危|
|xstream project跨界内存写漏洞|跨界内存写|[MPS-2022-57062](https://www.oscs1024.com/hd/MPS-2022-57062)|CVE-2022-40155|高危|
|xstream project跨界内存写漏洞|跨界内存写|[MPS-2022-57063](https://www.oscs1024.com/hd/MPS-2022-57063)|CVE-2022-40154|高危|
|XStream 缓冲区错误漏洞|越界写入|[MPS-2022-57065](https://www.oscs1024.com/hd/MPS-2022-57065)|CVE-2022-40152|高危|
|Jettison <1.5.2 拒绝服务漏洞|拒绝服务|[MPS-2022-57067](https://www.oscs1024.com/hd/MPS-2022-57067)|CVE-2022-40150|高危|
|Jettison <1.5.1 拒绝服务漏洞|越界写入|[MPS-2022-57068](https://www.oscs1024.com/hd/MPS-2022-57068)|CVE-2022-40149|高危|
|Python 安全漏洞|ReDoS|[MPS-2022-57238](https://www.oscs1024.com/hd/MPS-2022-57238)|CVE-2022-40897|中危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|Netty <4.1.86.Final 存在拒绝服务漏洞|未经控制的递归|[MPS-2022-58518](https://www.oscs1024.com/hd/MPS-2022-58518)|CVE-2022-41881|中危|
|Netty <4.1.86.Final 存在 CRLF 注入漏洞||[MPS-2022-58552](https://www.oscs1024.com/hd/MPS-2022-58552)|CVE-2022-41915|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|Apache Commons Text <1.10.0 远程代码执行漏洞|反序列化|[MPS-2022-59712](https://www.oscs1024.com/hd/MPS-2022-59712)|CVE-2022-42889|严重|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|Jettison <1.5.2 拒绝服务漏洞|越界写入|[MPS-2022-64973](https://www.oscs1024.com/hd/MPS-2022-64973)|CVE-2022-45685|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Apache Spark 权限提升漏洞|权限管理不当|[MPS-2023-0818](https://www.oscs1024.com/hd/MPS-2023-0818)|CVE-2023-22946|高危|
|Apache Kafka Connect 模块JNDI注入漏洞|反序列化|[MPS-2023-3834](https://www.oscs1024.com/hd/MPS-2023-3834)|CVE-2023-25194|高危|
|Eclipse Jetty 资源管理错误漏洞|拒绝服务|[MPS-2023-4997](https://www.oscs1024.com/hd/MPS-2023-4997)|CVE-2023-26048|中危|
|Eclipse Jetty 信息泄露漏洞|XSS|[MPS-2023-4998](https://www.oscs1024.com/hd/MPS-2023-4998)|CVE-2023-26049|中危|
|netplex json-smart 安全漏洞|未经控制的递归|[MPS-2023-7760](https://www.oscs1024.com/hd/MPS-2023-7760)|CVE-2023-1370|高危|
|Jettison 安全漏洞|未经控制的递归|[MPS-2023-8270](https://www.oscs1024.com/hd/MPS-2023-8270)|CVE-2023-1436|高危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|Apache Tomcat FORM 重定向漏洞|跨站重定向|[MPS-uy56-j8e4](https://www.oscs1024.com/hd/MPS-uy56-j8e4)|CVE-2023-41080|低危|
|Apache Tomcat 安全漏洞||[MPS-xd4z-oncg](https://www.oscs1024.com/hd/MPS-xd4z-oncg)|CVE-2023-34981|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.eclipse.jetty.aggregate:jetty-all|7.6.0.v20120127|9.2.9.v20150224|间接依赖|强烈建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.14.1||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.bouncycastle:bcprov-jdk15on|1.65|1.69|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|org.codehaus.jettison:jettison|1.1|1.5.4|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.4.2|2.14.0-rc1|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.apache.commons:commons-text|1.9|1.10.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.google.protobuf:protobuf-java|2.5.0|3.21.7|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|log4j:log4j|1.2.17-cloudera6||直接依赖|建议修复|C:1|H:3|M:0|L:1|
|tomcat:jasper-runtime|5.5.23||间接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.alibaba:fastjson|1.2.75|1.2.83|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.kafka:kafka-clients|2.8.1|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|commons-net:commons-net|3.6|3.9.0|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.jboss.xnio:xnio-api|3.7.9.Final|3.8.8|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-http|9.4.51.v20230217|11.0.10|间接依赖|建议修复|C:0|H:0|M:0|L:1|
|io.netty:netty-codec-http|4.1.77.Final|4.1.86.final|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|tomcat:jasper-compiler|5.5.23||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.elasticsearch:elasticsearch|7.10.2|8.2.1|间接依赖|建议修复|C:0|H:0|M:7|L:0|
|org.eclipse.jetty:jetty-server|9.4.43.v20210629|12.0.0.beta0|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13||间接依赖|建议修复|C:1|H:1|M:0|L:0|
|org.apache.ant:ant|1.9.1|1.10.11|间接依赖|建议修复|C:0|H:1|M:3|L:0|
|io.netty:netty-handler|4.1.89.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.eclipse.jetty:jetty-webapp|9.4.43.v20210629|11.0.6|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.12.7|2.14.0-rc1|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|commons-codec:commons-codec|1.9|1.13|直接依赖|建议修复|C:0|H:0|M:0|L:1|
|org.xerial.snappy:snappy-java|1.1.7.2|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.xerial.snappy:snappy-java|1.1.8.2|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|log4j:log4j|1.2.17-cloudera6||直接依赖|建议修复|C:1|H:3|M:0|L:1|
|org.eclipse.jetty:jetty-server|9.4.51.v20230217|12.0.0.beta0|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.apache.kafka:kafka-clients|2.8.1|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.42.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.yaml:snakeyaml|1.31|2.0|间接依赖|建议修复|C:0|H:1|M:1|L:1|
|org.eclipse.jetty:jetty-http|9.4.43.v20210629|11.0.10|间接依赖|建议修复|C:0|H:0|M:1|L:1|
|org.apache.spark:spark-core_2.12|3.3.1|3.4.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.14.1||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.xerial.snappy:snappy-java|1.1.8.3|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|io.netty:netty|3.10.6.Final||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.squareup.okio:okio|2.8.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-codec-haproxy|4.1.77.Final|4.1.86.final|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|setuptools|58.0.0|65.5.1|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|io.netty:netty-transport-native-epoll|4.1.42.Final|4.1.59.Final|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.apache.zookeeper:zookeeper|3.4.6|3.5.5|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|com.fasterxml.woodstox:woodstox-core|5.3.0|6.4.0|间接依赖|建议修复|C:0|H:3|M:0|L:1|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.10.4|2.12.1|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.httpcomponents:httpclient|4.2|4.5.13|间接依赖|可选修复|C:0|H:0|M:4|L:0|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.10.4|2.12.1|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|commons-codec:commons-codec|1.3|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.jetbrains.kotlin:kotlin-stdlib|1.4.10|1.6.0|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|net.minidev:json-smart|2.4.7|2.4.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.httpcomponents:httpclient|4.5.6|4.5.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|junit:junit|4.11|4.13.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.derby:derby|10.10.2.0|10.14.2.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.tomcat.embed:tomcat-embed-core|8.5.88|11.0.0-m6|直接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.thrift:libthrift|0.9.3|0.12.0|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.guava:guava|14.0.1|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|ant:ant|1.6.5|1.10.11|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.apache.hadoop:hadoop-yarn-common|2.5.1|2.7.3|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|12.0.1|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|559|Low|
|EPL-1.0|13|Low|
|自定义许可证|63|Low|
|CDDL-1.1|15|Low|
|BSD-3-Clause|14|Low|
|MIT|17|Low|
|EPL-2.0|15|Low|
|BSL-1.0|1|Low|
|BSD-2-Clause|5|Low|
|CDDL-1.0|2|Low|
|LGPL-2.1|5|Medium|
|MPL-1.1|1|Low|
|LGPL-2.1-or-later|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.apache.tomcat.embed:tomcat-embed-core|8.5.88|直接依赖|maven|
|org.apache.lucene:lucene-queries|8.4.0|间接依赖|maven|
|org.apache.lucene:lucene-analyzers-common|8.4.0|间接依赖|maven|
|org.mortbay.jetty:jetty|6.1.26|间接依赖|maven|
|com.google.protobuf:protobuf-java|2.5.0|间接依赖|maven|
|org.apache.ranger:ranger-plugins-audit|2.4.0|间接依赖|maven|
|org.eclipse.jetty.aggregate:jetty-all|7.6.0.v20120127|间接依赖|maven|
|io.dropwizard.metrics:metrics-jvm|3.1.0|间接依赖|maven|
|com.sun.jersey:jersey-json|1.19|间接依赖|maven|
|com.google.protobuf:protobuf-java-util|3.21.1|间接依赖|maven|
|com.tdunning:t-digest|3.2|间接依赖|maven|
|com.google.api:api-common|2.2.2|间接依赖|maven|
|com.starrocks:spark-dpp|1.0.0|直接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.32|间接依赖|maven|
|ch.qos.reload4j:reload4j|1.2.19|间接依赖|maven|
|org.apache.hbase:hbase-protocol|1.1.1|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|2.5.1|间接依赖|maven|
|io.dropwizard.metrics:metrics-json|3.1.0|间接依赖|maven|
|org.apache.httpcomponents:httpmime|4.5.6|间接依赖|maven|
|com.google.inject.extensions:guice-assistedinject|3.0|间接依赖|maven|
|com.github.joshelser:dropwizard-metrics-hadoop-metrics2-reporter|0.1.2|间接依赖|maven|
|org.elasticsearch:elasticsearch-secure-sm|7.10.2|间接依赖|maven|
|org.apache.groovy:groovy-groovysh|4.0.9|直接依赖|maven|
|javax.servlet.jsp:jsp-api|2.1|间接依赖|maven|
|com.google.cloud:google-cloud-monitoring|1.82.0|间接依赖|maven|
|org.apache.zookeeper:zookeeper-jute|3.5.7|间接依赖|maven|
|io.grpc:grpc-xds|1.50.2|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.32|间接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.51.v20230217|间接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.9.13|间接依赖|maven|
|List||间接依赖|pip|
|com.microsoft.azure:azure-keyvault-core|1.0.0|间接依赖|maven|
|com.squareup.okhttp3:okhttp|4.9.3|间接依赖|maven|
|javax.servlet:javax.servlet-api|3.1.0|间接依赖|maven|
|io.netty:netty-transport-rxtx|4.1.89.Final|间接依赖|maven|
|org.apache.iceberg:iceberg-common|1.2.1|直接依赖|maven|
|org.apache.geronimo.specs:geronimo-jaspic_1.0_spec|1.0|间接依赖|maven|
|org.apache.httpcomponents:fluent-hc|4.4.1|间接依赖|maven|
|org.apache.thrift:libthrift|0.13.0|直接依赖|maven|
|org.tukaani:xz|1.5|间接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j-impl|2.19.0|直接依赖|maven|
|io.netty:netty-transport-rxtx|4.1.77.Final|间接依赖|maven|
|io.delta:delta-storage|2.0.0|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|2.8|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.3.1.Final|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-scala_2.12|2.13.4|间接依赖|maven|
|com.google.http-client:google-http-client-appengine|1.42.3|间接依赖|maven|
|javax.transaction:transaction-api|1.1|间接依赖|maven|
|org.apache.commons:commons-collections4|4.4|间接依赖|maven|
|io.netty:netty-codec-smtp|4.1.77.Final|间接依赖|maven|
|log4j:log4j|1.2.17-cloudera6|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.2|间接依赖|maven|
|com.google.api.grpc:gapic-google-cloud-storage-v2|2.15.0-alpha|间接依赖|maven|
|io.airlift:log|202|间接依赖|maven|
|org.glassfish.hk2:osgi-resource-locator|1.0.3|间接依赖|maven|
|org.eclipse.jetty:jetty-xml|9.4.51.v20230217|间接依赖|maven|
|ant:ant|1.6.5|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.5.7|间接依赖|maven|
|org.jruby.jcodings:jcodings|1.0.8|间接依赖|maven|
|commons-cli:commons-cli|1.2|间接依赖|maven|
|org.jboss.threads:jboss-threads|2.3.3.Final|间接依赖|maven|
|io.perfmark:perfmark-api|0.25.0|间接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|org.glassfish.hk2:hk2-locator|2.6.1|间接依赖|maven|
|org.eclipse.jetty:jetty-util-ajax|9.4.43.v20210629|间接依赖|maven|
|org.jline:jline|3.9.0|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.1|间接依赖|maven|
|org.checkerframework:checker-qual|3.33.0|间接依赖|maven|
|commons-net:commons-net|3.6|间接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.77.Final|间接依赖|maven|
|asio||间接依赖||
|org.apache.hadoop:hadoop-client-runtime|3.3.2|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|org.apache.lucene:lucene-spatial-extras|8.4.0|间接依赖|maven|
|jakarta.ws.rs:jakarta.ws.rs-api|2.1.6|间接依赖|maven|
|io.netty:netty-codec-redis|4.1.89.Final|间接依赖|maven|
|com.twitter:chill-java|0.10.0|间接依赖|maven|
|io.netty:netty-buffer|4.1.77.Final|间接依赖|maven|
|commons-codec:commons-codec|1.3|间接依赖|maven|
|org.threeten:threeten-extra|1.7.2|直接依赖|maven|
|com.sun.jersey:jersey-client|1.19.4|间接依赖|maven|
|io.opencensus:opencensus-impl|0.31.0|间接依赖|maven|
|org.apache.hadoop:hadoop-auth|3.3.4|间接依赖|maven|
|org.json4s:json4s-scalap_2.12|3.7.0-M11|间接依赖|maven|
|io.opencensus:opencensus-impl-core|0.31.0|间接依赖|maven|
|io.netty:netty-all|4.1.61.Final|直接依赖|maven|
|io.netty:netty-transport-udt|4.1.77.Final|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|间接依赖|maven|
|net.minidev:accessors-smart|2.4.7|间接依赖|maven|
|org.apache.logging.log4j:log4j-web|2.6.2|间接依赖|maven|
|org.conscrypt:conscrypt-openjdk-uber|2.5.2|间接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.17.1|直接依赖|maven|
|com.sun.jersey:jersey-core|1.19|间接依赖|maven|
|org.eclipse.jetty:jetty-webapp|9.4.43.v20210629|间接依赖|maven|
|org.antlr:antlr-runtime|3.5.2|间接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|5.4.0|间接依赖|maven|
|asm:asm-commons|3.1|间接依赖|maven|
|org.apache.ranger:ranger-plugins-cred|2.4.0|间接依赖|maven|
|asm:asm|3.1|间接依赖|maven|
|com.zaxxer:HikariCP|2.5.1|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.3|间接依赖|maven|
|org.postgresql:postgresql|42.4.3|直接依赖|maven|
|io.grpc:grpc-netty-shaded|1.50.2|间接依赖|maven|
|org.apache.ant:ant-launcher|1.9.1|间接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-jaeger|1.14.0|直接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-core|2.5.1|间接依赖|maven|
|commons-net:commons-net|3.9.0|直接依赖|maven|
|org.apache.iceberg:iceberg-aws|1.2.1|直接依赖|maven|
|jakarta.servlet:jakarta.servlet-api|4.0.3|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.13.4|直接依赖|maven|
|com.chuusai:shapeless_2.12|2.3.4|间接依赖|maven|
|com.google.guava:guava|32.0.1-jre|直接依赖|maven|
|io.grpc:grpc-protobuf|1.44.1|间接依赖|maven|
|org.elasticsearch:elasticsearch-geo|7.10.2|间接依赖|maven|
|com.baidu:jprotobuf-rpc-common|1.9|直接依赖|maven|
|org.eclipse.jetty.orbit:javax.servlet|3.0.0.v201112011016|间接依赖|maven|
|com.google.flogger:flogger|0.7.1|间接依赖|maven|
|com.baidu:jprotobuf-rpc-core|4.2.1|直接依赖|maven|
|cup|3.2.31|间接依赖|pip|
|parallel-hashmap|1.30|间接依赖||
|io.grpc:grpc-grpclb|1.50.2|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.13.4|直接依赖|maven|
|org.apache.commons:commons-math3|3.1.1|间接依赖|maven|
|com.aliyun.datalake:shims-load|0.2.14|间接依赖|maven|
|io.opencensus:opencensus-api|0.31.1|间接依赖|maven|
|org.scala-lang:scala-library|2.12.10|间接依赖|maven|
|org.json4s:json4s-core_2.12|3.7.0-M11|间接依赖|maven|
|commons-digester:commons-digester|1.8|间接依赖|maven|
|org.eclipse.jetty:jetty-security|9.4.43.v20210629|间接依赖|maven|
|com.sun.activation:javax.activation|1.2.0|直接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.43.v20210629|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|3.3.6|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet-core|2.36|间接依赖|maven|
|com.starrocks:starcommon|3.1-rc8|间接依赖|maven|
|com.aliyun.datalake:metastore-client-common|0.2.14|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.12.7|间接依赖|maven|
|com.starrocks:starrocks-bdb-je|18.3.16|直接依赖|maven|
|org.apache.kerby:kerb-identity|1.0.1|间接依赖|maven|
|org.apache.iceberg:iceberg-bundled-guava|1.2.1|直接依赖|maven|
|com.google.oauth-client:google-oauth-client|1.34.1|间接依赖|maven|
|org.apache.thrift:libthrift|0.14.1|直接依赖|maven|
|com.google.api-client:google-api-client|2.0.1|间接依赖|maven|
|org.apache.hive:hive-storage-api|2.4.0|间接依赖|maven|
|com.google.guava:guava|12.0.1|间接依赖|maven|
|io.netty:netty-handler|4.1.89.Final|间接依赖|maven|
|com.twitter:chill_2.12|0.10.0|间接依赖|maven|
|org.elasticsearch.plugin:rank-eval-client|7.10.2|间接依赖|maven|
|com.baidu:jprotobuf-protoparser|1.0.1|间接依赖|maven|
|org.apache.commons:commons-text|1.9|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.25|间接依赖|maven|
|org.elasticsearch:elasticsearch-core|7.10.2|间接依赖|maven|
|org.apache.thrift:libthrift|0.9.3|间接依赖|maven|
|javax.transaction:jta|1.1|间接依赖|maven|
|org.codehaus.woodstox:stax2-api|4.2.1|间接依赖|maven|
|org.apache.hadoop:hadoop-azure-datalake|3.3.6|直接依赖|maven|
|org.apache.iceberg:iceberg-core|1.2.1|直接依赖|maven|
|io.grpc:grpc-auth|1.50.2|间接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.3|间接依赖|maven|
|com.facebook.presto.hive:hive-apache|3.0.0-8|直接依赖|maven|
|org.apache.lucene:lucene-spatial|8.4.0|间接依赖|maven|
|commons-dbcp:commons-dbcp|1.4|间接依赖|maven|
|io.netty:netty-codec-mqtt|4.1.89.Final|间接依赖|maven|
|io.dropwizard.metrics:metrics-graphite|4.2.7|间接依赖|maven|
|de.jflex:jflex|1.4.3|直接依赖|maven|
|org.wildfly.openssl:wildfly-openssl|1.0.7.Final|间接依赖|maven|
|com.amazonaws:aws-java-sdk|1.7.4|间接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.89.Final|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.30|直接依赖|maven|
|org.jruby.jcodings:jcodings|1.0.55|间接依赖|maven|
|co.cask.tephra:tephra-hbase-compat-1.0|0.6.0|间接依赖|maven|
|com.google.api.grpc:grpc-google-cloud-storage-v2|2.15.0-alpha|间接依赖|maven|
|dnsjava:dnsjava|2.1.7|间接依赖|maven|
|io.netty:netty-transport-sctp|4.1.89.Final|间接依赖|maven|
|io.netty:netty-codec-memcache|4.1.77.Final|间接依赖|maven|
|org.jruby.joni:joni|2.1.31|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-core|3.3.6|间接依赖|maven|
|org.apache.htrace:htrace-core|3.1.0-incubating|直接依赖|maven|
|org.elasticsearch:elasticsearch|7.10.2|间接依赖|maven|
|com.aliyun.datalake:metastore-client-hive3|0.2.14|直接依赖|maven|
|com.amazonaws:aws-java-sdk-bundle|1.12.367|间接依赖|maven|
|org.apache.groovy:groovy-swing|4.0.9|间接依赖|maven|
|org.datanucleus:datanucleus-core|4.1.17|间接依赖|maven|
|org.apache.ant:ant|1.9.1|间接依赖|maven|
|org.ow2.asm:asm|9.1|直接依赖|maven|
|org.roaringbitmap:shims|0.8.13|间接依赖|maven|
|com.opencsv:opencsv|5.7.1|直接依赖|maven|
|org.apache.logging.log4j:log4j-1.2-api|2.19.0|直接依赖|maven|
|org.datanucleus:datanucleus-api-jdo|4.2.4|间接依赖|maven|
|tomcat:jasper-compiler|5.5.23|间接依赖|maven|
|com.google.cloud.bigdataoss:gcsio|2.2.11|间接依赖|maven|
|software.amazon.awssdk:annotations|2.17.257|间接依赖|maven|
|com.squareup.okio:okio|3.4.0|直接依赖|maven|
|org.apache.lucene:lucene-join|8.4.0|间接依赖|maven|
|com.ning:compress-lzf|1.1|间接依赖|maven|
|com.google.cloud.bigdataoss:gcs-connector|hadoop3-2.2.11|直接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.89.Final|间接依赖|maven|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|com.google.code.gson:gson|2.8.9|直接依赖|maven|
|io.netty:netty-resolver|4.1.77.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.12.7|间接依赖|maven|
|commons-validator:commons-validator|1.7|直接依赖|maven|
|software.amazon.awssdk:metrics-spi|2.17.257|间接依赖|maven|
|javax.activation:activation|1.1.1|间接依赖|maven|
|org.apache.geronimo.specs:geronimo-jta_1.1_spec|1.1.1|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-common|1.14.0|间接依赖|maven|
|org.apache.kerby:kerby-pkix|1.0.1|间接依赖|maven|
|io.opencensus:opencensus-proto|0.2.0|间接依赖|maven|
|org.apache.groovy:groovy-templates|4.0.9|间接依赖|maven|
|com.sun.jersey:jersey-server|1.19|间接依赖|maven|
|org.apache.commons:commons-math3|3.6.1|间接依赖|maven|
|org.eclipse.jetty:jetty-webapp|9.4.51.v20230217|间接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.4.43.v20210629|间接依赖|maven|
|io.netty:netty-codec-xml|4.1.77.Final|间接依赖|maven|
|org.apache.hadoop:hadoop-hdfs|3.3.4|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-web-proxy|2.7.2|间接依赖|maven|
|com.facebook.presto.hadoop:hadoop-apache2|2.7.4-11|直接依赖|maven|
|com.google.auth:google-auth-library-credentials|1.12.1|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|3.1.0|间接依赖|maven|
|org.codehaus.jackson:jackson-jaxrs|1.9.13|间接依赖|maven|
|org.apache.lucene:lucene-memory|8.4.0|间接依赖|maven|
|com.google.http-client:google-http-client-apache-v2|1.42.3|间接依赖|maven|
|org.apache.kerby:kerb-simplekdc|1.0.1|间接依赖|maven|
|com.github.javaparser:javaparser-core|3.25.0|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.18.0|间接依赖|maven|
|io.netty:netty-codec-smtp|4.1.89.Final|间接依赖|maven|
|com.tdunning:json|1.8|间接依赖|maven|
|org.apache.hbase:hbase-client|1.1.1|间接依赖|maven|
|io.opencensus:opencensus-contrib-grpc-metrics|0.31.0|间接依赖|maven|
|commons-codec:commons-codec|1.13|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|间接依赖|maven|
|org.apache.orc:orc-shims|1.6.0|间接依赖|maven|
|org.apache.hive:hive-shims|2.3.9|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-common|9.4.51.v20230217|间接依赖|maven|
|com.google.http-client:google-http-client-jackson2|1.42.3|间接依赖|maven|
|commons-io:commons-io|2.8.0|间接依赖|maven|
|org.scala-lang.modules:scala-xml_2.12|1.2.0|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.77.Final|间接依赖|maven|
|org.apache.tomcat:tomcat-annotations-api|8.5.88|直接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.6|间接依赖|maven|
|org.apache.kerby:kerb-common|1.0.1|间接依赖|maven|
|org.apache.solr:solr-solrj|8.11.2|间接依赖|maven|
|org.elasticsearch:elasticsearch-x-content|7.10.2|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|com.google.inject.extensions:guice-servlet|3.0|间接依赖|maven|
|com.aliyun.datalake:shims-cdh-hive2|0.2.14|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.89.Final|间接依赖|maven|
|org.javassist:javassist|3.25.0-GA|间接依赖|maven|
|javax.servlet:servlet-api|2.4|间接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|9.8.1|间接依赖|maven|
|org.apache.commons:commons-crypto|1.1.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.19.0|直接依赖|maven|
|org.checkerframework:checker-compat-qual|2.5.3|间接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|5.3.0|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.65|间接依赖|maven|
|org.apache.avro:avro|1.8.2|间接依赖|maven|
|org.wildfly.client:wildfly-client-config|1.0.1.Final|间接依赖|maven|
|com.google.crypto.tink:tink|1.6.1|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|3.3.4|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.10.4|间接依赖|maven|
|commons-pool:commons-pool|1.5.4|间接依赖|maven|
|org.apache.xbean:xbean-asm9-shaded|4.20|间接依赖|maven|
|com.amazonaws:aws-java-sdk-bundle|1.12.262|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-smile|2.10.4|间接依赖|maven|
|software.amazon.eventstream:eventstream|1.0.1|间接依赖|maven|
|org.apache.hudi:hudi-hadoop-mr|0.12.2|直接依赖|maven|
|org.apache.hive:hive-common|2.3.9|间接依赖|maven|
|org.apache.commons:commons-configuration2|2.8.0|间接依赖|maven|
|io.opencensus:opencensus-contrib-resource-util|0.31.0|间接依赖|maven|
|org.apache.iceberg:iceberg-api|1.2.1|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.32|直接依赖|maven|
|com.sun.jersey:jersey-bundle|1.19.3|间接依赖|maven|
|org.apache.commons:commons-configuration2|2.1.1|间接依赖|maven|
|org.apache.twill:twill-zookeeper|0.6.0-incubating|间接依赖|maven|
|com.google.re2j:re2j|1.1|间接依赖|maven|
|setuptools|58.0.0|间接依赖|pip|
|javax.xml.bind:jaxb-api|2.2.2|间接依赖|maven|
|net.razorvine:pickle|1.2|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.43.v20210629|间接依赖|maven|
|org.jboss.xnio:xnio-api|3.7.9.Final|间接依赖|maven|
|org.apache.spark:spark-tags_2.12|3.3.1|间接依赖|maven|
|org.apache.hbase:hbase-common|1.1.1|间接依赖|maven|
|io.grpc:grpc-core|1.50.2|间接依赖|maven|
|org.eclipse.jetty:jetty-server|9.4.43.v20210629|间接依赖|maven|
|org.apache.curator:curator-framework|5.2.0|间接依赖|maven|
|org.eclipse.jetty:jetty-xml|9.4.43.v20210629|间接依赖|maven|
|com.starrocks:starmanager|3.1-rc8|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|3.3.6|间接依赖|maven|
|commons-lang:commons-lang|2.6|直接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5|5.2|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.89.Final|间接依赖|maven|
|net.java.dev.jna:jna-platform|5.12.1|间接依赖|maven|
|mysql:mysql-connector-java|8.0.28|直接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.89.Final|间接依赖|maven|
|commons-codec:commons-codec|1.9|直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-logs|1.14.0-alpha|间接依赖|maven|
|io.grpc:grpc-googleapis|1.50.2|间接依赖|maven|
|com.github.oshi:oshi-core|6.2.1|直接依赖|maven|
|org.threeten:threetenbp|1.6.4|间接依赖|maven|
|com.microsoft.azure:azure-storage|7.0.1|间接依赖|maven|
|commons-logging:commons-logging|1.1.3|直接依赖|maven|
|com.aliyun.datalake:shims-hive3|0.2.14|间接依赖|maven|
|org.wildfly.common:wildfly-common|1.5.2.Final|间接依赖|maven|
|io.netty:netty-codec-redis|4.1.77.Final|间接依赖|maven|
|org.apache.paimon:paimon-s3|0.4.0-incubating|直接依赖|maven|
|com.sun.xml.bind:jaxb-impl|2.2.3-1|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.89.Final|间接依赖|maven|
|com.fasterxml.jackson.jr:jackson-jr-objects|2.13.2|间接依赖|maven|
|com.google.flogger:google-extensions|0.7.1|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-applicationhistoryservice|2.7.2|间接依赖|maven|
|org.apache.hive.shims:hive-shims-0.23|2.3.9|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.4-2|直接依赖|maven|
|commons-configuration:commons-configuration|1.6|直接依赖|maven|
|org.apache.commons:commons-lang3|3.3.2|直接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.1|间接依赖|maven|
|org.ow2.asm:asm-util|9.1|直接依赖|maven|
|org.apache.hadoop:hadoop-auth|3.3.6|直接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.77.Final|间接依赖|maven|
|com.github.stephenc.jcip:jcip-annotations|1.0-1|间接依赖|maven|
|org.ow2.asm:asm|9.4|间接依赖|maven|
|org.apache.commons:commons-pool2|2.3|直接依赖|maven|
|org.json4s:json4s-jackson_2.12|3.7.0-M11|间接依赖|maven|
|org.apache.commons:commons-compress|1.21|间接依赖|maven|
|com.aliyun.datalake:shims-common|0.2.14|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.77.Final|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.89.Final|间接依赖|maven|
|org.apache.twill:twill-api|0.6.0-incubating|间接依赖|maven|
|org.apache.ranger:ranger-plugins-common|2.4.0|直接依赖|maven|
|com.google.api.grpc:grpc-google-iam-v1|1.6.7|间接依赖|maven|
|com.baidu:jprotobuf|2.4.12|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.4.10|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.4.6|间接依赖|maven|
|org.apache.orc:orc-core|1.6.0|间接依赖|maven|
|org.apache.commons:commons-lang3|3.9|直接依赖|maven|
|com.google.http-client:google-http-client-gson|1.42.3|间接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-high-level-client|7.10.2|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-client|3.3.6|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|com.starrocks:starclient|3.1-rc8|直接依赖|maven|
|org.apache.zookeeper:zookeeper-jute|3.5.6|间接依赖|maven|
|io.netty:netty-all|4.1.77.Final|间接依赖|maven|
|com.sun.jersey:jersey-server|1.19.4|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|4.2.7|间接依赖|maven|
|javax.xml.soap:javax.xml.soap-api|1.4.0|间接依赖|maven|
|javax.xml.ws:jaxws-api|2.3.0|直接依赖|maven|
|nose-progressive|1.5.2|间接依赖|pip|
|org.apache.hadoop:hadoop-hdfs-client|3.3.6|直接依赖|maven|
|org.apache.paimon:paimon-bundle|0.4.0-incubating|直接依赖|maven|
|org.apache.hive:hive-serde|2.3.9|间接依赖|maven|
|org.apache.httpcomponents.client5:httpclient5|5.2.1|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.89.Final|间接依赖|maven|
|org.apache.yetus:audience-annotations|0.5.0|间接依赖|maven|
|org.apache.kerby:kerby-asn1|1.0.1|间接依赖|maven|
|org.apache.hadoop.thirdparty:hadoop-shaded-protobuf_3_7|1.1.1|间接依赖|maven|
|com.google.api:gax-grpc|2.19.5|间接依赖|maven|
|com.github.spotbugs:spotbugs-annotations|3.1.9|间接依赖|maven|
|org.glassfish.jersey.core:jersey-common|2.36|间接依赖|maven|
|org.apache.groovy:groovy|4.0.9|间接依赖|maven|
|io.trino:trino-parser|385|直接依赖|maven|
|com.google.cloud:google-cloud-core-http|2.8.27|间接依赖|maven|
|io.netty:netty-codec-xml|4.1.89.Final|间接依赖|maven|
|org.apache.hbase:hbase-client|2.4.9|间接依赖|maven|
|ch.qos.reload4j:reload4j|1.2.22|间接依赖|maven|
|org.apache.twill:twill-discovery-core|0.6.0-incubating|间接依赖|maven|
|org.apache.lucene:lucene-backward-codecs|8.4.0|间接依赖|maven|
|io.airlift:aircompressor|0.21|间接依赖|maven|
|org.apache.avro:avro|1.7.7|间接依赖|maven|
|io.netty:netty-transport-udt|4.1.89.Final|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet|2.36|间接依赖|maven|
|io.grpc:grpc-context|1.50.2|间接依赖|maven|
|org.apache.commons:commons-text|1.4|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.51.v20230217|间接依赖|maven|
|com.google.code.gson:gson|2.9.0|间接依赖|maven|
|org.apache.lucene:lucene-sandbox|8.4.0|间接依赖|maven|
|org.apache.hadoop:hadoop-common|3.3.4|直接依赖|maven|
|com.jolbox:bonecp|0.8.0.RELEASE|间接依赖|maven|
|org.apache.avro:avro-mapred|1.11.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.8.0|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.5.6|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.16.3|直接依赖|maven|
|io.netty:netty-codec-http|4.1.77.Final|间接依赖|maven|
|com.esotericsoftware:kryo-shaded|4.0.2|直接依赖|maven|
|com.aliyun:endpoint-util|0.0.6|间接依赖|maven|
|io.netty:netty-codec-mqtt|4.1.77.Final|间接依赖|maven|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13|间接依赖|maven|
|joda-time:joda-time|2.8.1|间接依赖|maven|
|org.mortbay.jetty:jetty-util|6.1.26|间接依赖|maven|
|junit:junit|4.11|间接依赖|maven|
|datadog_checks||间接依赖|pip|
|org.apache.lucene:lucene-suggest|8.4.0|间接依赖|maven|
|io.airlift:units|1.0|间接依赖|maven|
|org.glassfish.jersey.inject:jersey-hk2|2.36|间接依赖|maven|
|com.ibm.icu:icu4j|61.1|间接依赖|maven|
|io.netty:netty-all|4.1.89.Final|间接依赖|maven|
|software.amazon.awssdk:bundle|2.17.257|直接依赖|maven|
|org.apache.twill:twill-core|0.6.0-incubating|间接依赖|maven|
|io.netty:netty-codec|4.1.89.Final|间接依赖|maven|
|org.apache.hadoop:hadoop-aws|3.3.6|直接依赖|maven|
|org.apache.spark:spark-network-common_2.12|3.3.1|间接依赖|maven|
|org.antlr:ST4|4.3|间接依赖|maven|
|io.grpc:grpc-services|1.50.2|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|3.3.6|直接依赖|maven|
|org.apache.spark:spark-network-shuffle_2.12|3.3.1|间接依赖|maven|
|org.apache.commons:commons-text|1.10.0|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.21|间接依赖|maven|
|co.cask.tephra:tephra-api|0.6.0|间接依赖|maven|
|net.java.dev.jna:jna|5.12.1|间接依赖|maven|
|javax.jdo:jdo-api|3.0.1|间接依赖|maven|
|com.github.spullara.mustache.java:compiler|0.9.6|间接依赖|maven|
|org.apache.lucene:lucene-misc|8.4.0|间接依赖|maven|
|io.delta:delta-standalone_2.12|0.5.0|直接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.12.7|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.3|间接依赖|maven|
|com.squareup.okhttp3:okhttp|4.9.1|直接依赖|maven|
|commons-logging:commons-logging|1.1.1|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|直接依赖|maven|
|javax.mail:mail|1.4.1|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-client|9.4.51.v20230217|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|3.2.4|间接依赖|maven|
|com.lmax:disruptor|3.4.2|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.2|间接依赖|maven|
|org.openjdk.jol:jol-core|0.16|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.12.7|间接依赖|maven|
|org.apache.avro:avro-ipc|1.11.0|间接依赖|maven|
|org.apache.hbase:hbase-annotations|1.1.1|间接依赖|maven|
|io.netty:netty-codec-haproxy|4.1.77.Final|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-metrics|1.14.0|间接依赖|maven|
|org.codehaus.jettison:jettison|1.1|间接依赖|maven|
|software.amazon.awssdk:url-connection-client|2.17.257|直接依赖|maven|
|com.google.inject:guice|3.0|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|直接依赖|maven|
|org.wildfly.openssl:wildfly-openssl|1.1.3.Final|间接依赖|maven|
|com.google.api-client:google-api-client-jackson2|2.0.1|间接依赖|maven|
|com.sun.jersey:jersey-core|1.19.4|间接依赖|maven|
|org.apache.spark:spark-unsafe_2.12|3.3.1|间接依赖|maven|
|org.scala-lang:scala-reflect|2.12.15|间接依赖|maven|
|org.apache.geronimo.specs:geronimo-annotation_1.0_spec|1.1.1|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.1|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-trace|1.14.0|间接依赖|maven|
|org.apache.twill:twill-common|0.6.0-incubating|间接依赖|maven|
|com.aliyun:datalake20200710|2.0.2|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.5-5|直接依赖|maven|
|org.apache.htrace:htrace-core4|4.2.0-incubating|间接依赖|maven|
|it.unimi.dsi:fastutil|6.5.6|间接依赖|maven|
|org.apache.hive:hive-service-rpc|2.3.9|间接依赖|maven|
|org.apache.hive.shims:hive-shims-scheduler|2.3.9|间接依赖|maven|
|commons-io:commons-io|2.7|直接依赖|maven|
|org.apache.iceberg:iceberg-hive-metastore|1.2.1|直接依赖|maven|
|org.jboss.xnio:xnio-nio|3.7.9.Final|直接依赖|maven|
|com.google.apis:google-api-services-iamcredentials|v1-rev20211203-2.0.0|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.2-1|间接依赖|maven|
|org.apache.curator:curator-framework|2.13.0|间接依赖|maven|
|com.starrocks:jni-connector|1.0.0|直接依赖|maven|
|io.dropwizard.metrics:metrics-jmx|4.2.7|间接依赖|maven|
|org.apache.hadoop:hadoop-hdfs|3.3.6|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.4.10|间接依赖|maven|
|org.ow2.asm:asm-analysis|9.1|间接依赖|maven|
|org.apache.kafka:kafka-clients|2.8.1|间接依赖|maven|
|org.glassfish.hk2.external:aopalliance-repackaged|2.6.1|间接依赖|maven|
|org.apache.lucene:lucene-grouping|8.4.0|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.7.2|间接依赖|maven|
|org.apache.spark:spark-kvstore_2.12|3.3.1|间接依赖|maven|
|com.alibaba:fastjson|1.2.75|直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk|1.14.0|直接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.9.2|间接依赖|maven|
|org.apache.spark:spark-launcher_2.12|3.3.1|直接依赖|maven|
|org.objenesis:objenesis|2.5.1|间接依赖|maven|
|commons-el:commons-el|1.0|间接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|2.0.1|间接依赖|maven|
|com.microsoft.azure:azure-data-lake-store-sdk|2.3.9|间接依赖|maven|
|com.starrocks:java-utils|1.0.0|直接依赖|maven|
|com.google.api.grpc:proto-google-iam-v1|1.1.7|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.14.1|直接依赖|maven|
|org.glassfish:javax.json|1.0.4|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.4|直接依赖|maven|
|com.github.stephenc.findbugs:findbugs-annotations|1.3.9-1|间接依赖|maven|
|com.google.api.grpc:proto-google-cloud-monitoring-v3|1.64.0|间接依赖|maven|
|org.antlr:antlr4-runtime|4.9.2|间接依赖|maven|
|org.apache.hive.shims:hive-shims-common|2.3.9|间接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.89.Final|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.1|直接依赖|maven|
|io.opentelemetry:opentelemetry-context|1.14.0|间接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.77.Final|间接依赖|maven|
|org.apache.lucene:lucene-highlighter|8.4.0|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-api|9.4.51.v20230217|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.77.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.12.7|间接依赖|maven|
|org.apache.lucene:lucene-core|8.4.0|间接依赖|maven|
|net.minidev:json-smart|2.4.7|间接依赖|maven|
|org.apache.kerby:kerb-admin|1.0.1|间接依赖|maven|
|org.apache.kerby:kerb-crypto|1.0.1|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|io.dropwizard.metrics:metrics-json|4.2.7|间接依赖|maven|
|org.apache.spark:spark-core_2.12|3.3.1|直接依赖|maven|
|org.codehaus.jackson:jackson-jaxrs|1.9.2|间接依赖|maven|
|org.datanucleus:datanucleus-rdbms|4.1.19|间接依赖|maven|
|io.opencensus:opencensus-contrib-exemplar-util|0.31.0|间接依赖|maven|
|io.netty:netty-transport|4.1.89.Final|间接依赖|maven|
|commons-cli:commons-cli|1.4|直接依赖|maven|
|io.airlift:concurrent|202|直接依赖|maven|
|com.jcraft:jsch|0.1.55|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-resourcemanager|2.7.2|间接依赖|maven|
|io.netty:netty-transport-sctp|4.1.77.Final|间接依赖|maven|
|com.google.cloud:google-cloud-core-grpc|2.8.27|间接依赖|maven|
|com.aliyun:openapiutil|0.1.14|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-common|2.7.2|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.89.Final|间接依赖|maven|
|org.apache.lucene:lucene-spatial3d|8.4.0|间接依赖|maven|
|com.google.cloud:google-cloud-core|2.5.4|间接依赖|maven|
|com.google.cloud.bigdataoss:util-hadoop|hadoop3-2.2.11|间接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.19.0|直接依赖|maven|
|com.carrotsearch:hppc|0.8.0|间接依赖|maven|
|commons-digester:commons-digester|2.1|间接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-client|7.10.2|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.0|间接依赖|maven|
|org.apache.curator:curator-recipes|5.2.0|间接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.8|间接依赖|maven|
|asm:asm-tree|3.1|间接依赖|maven|
|org.elasticsearch.plugin:lang-mustache-client|7.10.2|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.9.3|直接依赖|maven|
|org.apache.groovy:groovy-console|4.0.9|间接依赖|maven|
|com.zaxxer:HikariCP|3.4.5|直接依赖|maven|
|software.amazon.awssdk:http-client-spi|2.17.257|间接依赖|maven|
|org.json4s:json4s-ast_2.12|3.7.0-M11|间接依赖|maven|
|org.apache.hbase:hbase-logging|2.4.9|间接依赖|maven|
|com.google.auto.value:auto-value|1.0|间接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|org.apache.hadoop:hadoop-client-api|3.3.2|间接依赖|maven|
|io.netty:netty-codec-stomp|4.1.77.Final|间接依赖|maven|
|org.antlr:antlr4|4.9.2|直接依赖|maven|
|io.netty:netty-handler|4.1.42.Final|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.6|间接依赖|maven|
|com.esotericsoftware:minlog|1.3.0|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.89.Final|间接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.44.1|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.2|间接依赖|maven|
|io.netty:netty-codec-http|4.1.89.Final|间接依赖|maven|
|oro:oro|2.0.8|间接依赖|maven|
|org.elasticsearch.plugin:mapper-extras-client|7.10.2|间接依赖|maven|
|org.apache.curator:curator-client|4.2.0|间接依赖|maven|
|org.eclipse.jetty:jetty-http|9.4.51.v20230217|间接依赖|maven|
|io.trino.hive:hive-apache|3.1.2-13|直接依赖|maven|
|io.grpc:grpc-stub|1.44.1|间接依赖|maven|
|org.ow2.asm:asm-tree|9.4|间接依赖|maven|
|org.tukaani:xz|1.9|间接依赖|maven|
|io.grpc:grpc-census|1.50.2|间接依赖|maven|
|org.roaringbitmap:RoaringBitmap|0.8.13|直接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.77.Final|间接依赖|maven|
|org.apache.kerby:kerby-xdr|1.0.1|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.4.14|直接依赖|maven|
|io.netty:netty-codec|4.1.77.Final|间接依赖|maven|
|org.datanucleus:javax.jdo|3.2.0-m3|间接依赖|maven|
|javax.activation:activation|1.1|间接依赖|maven|
|org.apache.hadoop:hadoop-hdfs-client|3.3.4|直接依赖|maven|
|org.glassfish.hk2:hk2-api|2.6.1|间接依赖|maven|
|Optional||间接依赖|pip|
|com.squareup.okio:okio-jvm|3.4.0|间接依赖|maven|
|io.grpc:grpc-alts|1.50.2|间接依赖|maven|
|org.apache.ivy:ivy|2.5.2|直接依赖|maven|
|com.google.api.grpc:proto-google-cloud-storage-v2|2.15.0-alpha|间接依赖|maven|
|org.elasticsearch:securesm|1.2|间接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-otlp-common|1.14.0|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.77.Final|间接依赖|maven|
|org.eclipse.jetty:jetty-server|9.4.51.v20230217|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.12|间接依赖|maven|
|org.elasticsearch.plugin:parent-join-client|7.10.2|间接依赖|maven|
|org.apache.curator:curator-recipes|4.2.0|间接依赖|maven|
|org.glassfish.jersey.core:jersey-server|2.36|间接依赖|maven|
|org.apache.hadoop:hadoop-aws|2.7.4|直接依赖|maven|
|com.google.cloud:google-cloud-storage|2.15.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.4|直接依赖|maven|
|org.apache.hive:hive-metastore|2.3.9|直接依赖|maven|
|commons-lang:commons-lang|2.4|直接依赖|maven|
|com.sun.jersey:jersey-servlet|1.19|间接依赖|maven|
|org.apache.kerby:token-provider|1.0.1|间接依赖|maven|
|io.netty:netty-codec-haproxy|4.1.89.Final|间接依赖|maven|
|jline:jline|2.12|间接依赖|maven|
|io.sgr:s2-geometry-library-java|1.0.0|间接依赖|maven|
|commons-beanutils:commons-beanutils-core|1.8.0|间接依赖|maven|
|com.aliyun.datalake:shims-hive2|0.2.14|间接依赖|maven|
|org.codehaus.jackson:jackson-xc|1.9.2|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.77.Final|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.77.Final|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.77.Final|间接依赖|maven|
|org.apache.curator:curator-recipes|2.13.0|间接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|io.opentelemetry:opentelemetry-semconv|1.14.0-alpha|间接依赖|maven|
|org.apache.kerby:kerby-util|1.0.1|间接依赖|maven|
|org.yaml:snakeyaml|1.31|间接依赖|maven|
|com.google.guava:guava|14.0.1|间接依赖|maven|
|org.json:json|20230227|直接依赖|maven|
|com.baidu:jprotobuf-rpc-core-test|4.2.1|间接依赖|maven|
|io.airlift:aircompressor|0.8|间接依赖|maven|
|javolution:javolution|5.5.1|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.8.0|间接依赖|maven|
|org.spark-project.spark:unused|1.0.0|间接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5-h2|5.2|间接依赖|maven|
|io.netty:netty|3.10.6.Final|间接依赖|maven|
|org.apache.parquet:parquet-hadoop-bundle|1.8.1|间接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.7|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|间接依赖|maven|
|co.cask.tephra:tephra-core|0.6.0|间接依赖|maven|
|joda-time:joda-time|2.9.9|间接依赖|maven|
|org.ow2.asm:asm-util|9.4|间接依赖|maven|
|io.dropwizard.metrics:metrics-jvm|4.2.7|间接依赖|maven|
|org.apache.lucene:lucene-queryparser|8.4.0|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-jobclient|3.3.6|间接依赖|maven|
|io.netty:netty-common|4.1.77.Final|间接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.4.51.v20230217|间接依赖|maven|
|com.starrocks:fe-common|1.0.0|直接依赖|maven|
|io.netty:netty-common|4.1.89.Final|间接依赖|maven|
|com.squareup.okio:okio|2.8.0|间接依赖|maven|
|org.slf4j:slf4j-reload4j|1.7.36|直接依赖|maven|
|com.aliyun.datalake:metastore-client-hive-common|0.2.14|间接依赖|maven|
|javax.validation:validation-api|1.1.0.Final|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.4.2|直接依赖|maven|
|org.apache.hbase:hbase-common|2.4.9|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-common|3.3.6|间接依赖|maven|
|com.sun.jersey:jersey-client|1.9|间接依赖|maven|
|org.glassfish.hk2:hk2-utils|2.6.1|间接依赖|maven|
|io.netty:netty-buffer|4.1.89.Final|间接依赖|maven|
|org.apache.curator:curator-client|5.2.0|间接依赖|maven|
|com.google.apis:google-api-services-storage|v1-rev20220705-2.0.0|间接依赖|maven|
|org.apache.twill:twill-discovery-api|0.6.0-incubating|间接依赖|maven|
|io.netty:netty-codec-stomp|4.1.89.Final|间接依赖|maven|
|org.apache.curator:curator-framework|4.2.0|间接依赖|maven|
|io.opencensus:opencensus-exporter-metrics-util|0.31.0|间接依赖|maven|
|org.apache.hadoop:hadoop-client|3.3.6|直接依赖|maven|
|io.grpc:grpc-api|1.50.2|间接依赖|maven|
|org.lz4:lz4-java|1.8.0|间接依赖|maven|
|org.eclipse.jetty:jetty-http|9.4.43.v20210629|间接依赖|maven|
|org.apache.hadoop:hadoop-common|3.3.6|直接依赖|maven|
|jline:jline|0.9.94|间接依赖|maven|
|org.glassfish.jersey.core:jersey-client|2.36|间接依赖|maven|
|org.apache.groovy:groovy-xml|4.0.9|间接依赖|maven|
|org.apache.orc:orc-core|1.5.8|间接依赖|maven|
|org.ow2.asm:asm-analysis|9.4|间接依赖|maven|
|io.netty:netty-codec-memcache|4.1.89.Final|间接依赖|maven|
|org.apache.kerby:kerb-core|1.0.1|间接依赖|maven|
|org.scala-lang.modules:scala-collection-compat_2.12|2.4.3|间接依赖|maven|
|javax.xml.stream:stax-api|1.0-2|间接依赖|maven|
|commons-daemon:commons-daemon|1.0.13|直接依赖|maven|
|com.google.api:gax|2.19.5|间接依赖|maven|
|org.apache.thrift:libfb303|0.9.3|间接依赖|maven|
|tomcat:jasper-runtime|5.5.23|间接依赖|maven|
|org.abego.treelayout:org.abego.treelayout.core|1.0.3|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.77.Final|间接依赖|maven|
|org.apache.hudi:hudi-presto-bundle|0.12.2|直接依赖|maven|
|org.apache.ranger:ranger-plugin-classloader|2.4.0|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|间接依赖|maven|
|org.apache.hadoop:hadoop-azure|3.3.6|直接依赖|maven|
|org.elasticsearch.plugin:aggs-matrix-stats-client|7.10.2|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.89.Final|间接依赖|maven|
|org.jruby.joni:joni|2.1.2|间接依赖|maven|
|org.eclipse.jetty:jetty-util-ajax|9.4.51.v20230217|间接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|io.netty:netty-handler-ssl-ocsp|4.1.89.Final|间接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.3|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|2.7.2|间接依赖|maven|
|com.google.api:gax-httpjson|0.104.5|间接依赖|maven|
|org.eclipse.jetty:jetty-client|9.4.31.v20200723|间接依赖|maven|
|io.netty:netty-transport|4.1.77.Final|间接依赖|maven|
|com.sun.jersey.contribs:jersey-guice|1.9|间接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|org.apache.hadoop.thirdparty:hadoop-shaded-guava|1.1.1|间接依赖|maven|
|com.fasterxml.uuid:java-uuid-generator|4.0|直接依赖|maven|
|org.elasticsearch:elasticsearch-cli|7.10.2|间接依赖|maven|
|com.sun.jersey:jersey-servlet|1.19.4|间接依赖|maven|
|com.google.auto.value:auto-value-annotations|1.8.2|间接依赖|maven|
|io.netty:netty-resolver|4.1.89.Final|间接依赖|maven|
|com.github.pjfanning:jersey-json|1.20|间接依赖|maven|
|io.opencensus:opencensus-exporter-stats-stackdriver|0.31.0|间接依赖|maven|
|org.locationtech.spatial4j:spatial4j|0.7|间接依赖|maven|
|javax.servlet:jsp-api|2.0|间接依赖|maven|
|org.glassfish.hk2.external:jakarta.inject|2.6.1|间接依赖|maven|
|net.sf.py4j:py4j|0.10.9.5|间接依赖|maven|
|jline:jline|2.14.6|间接依赖|maven|
|javax.ws.rs:jsr311-api|1.1.1|间接依赖|maven|
|org.fusesource.leveldbjni:leveldbjni-all|1.8|间接依赖|maven|
|org.apache.hudi:hudi-common|0.12.2|直接依赖|maven|
|net.sf.opencsv:opencsv|2.3|间接依赖|maven|
|com.google.auth:google-auth-library-oauth2-http|1.12.1|间接依赖|maven|
|io.opentelemetry:opentelemetry-api|1.14.0|直接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.42.Final|间接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.65|间接依赖|maven|
|org.apache.hadoop:hadoop-aws|3.3.4|直接依赖|maven|
|com.google.flogger:flogger-system-backend|0.7.1|间接依赖|maven|
|org.hamcrest:hamcrest-core|1.3|间接依赖|maven|
|com.google.code.findbugs:jsr305|1.3.9|间接依赖|maven|
|org.apache.derby:derby|10.10.2.0|间接依赖|maven|
|org.ow2.asm:asm-tree|9.1|间接依赖|maven|
|com.google.http-client:google-http-client|1.42.3|间接依赖|maven|
|io.opencensus:opencensus-contrib-http-util|0.31.1|间接依赖|maven|
|flaky|3.7.0|间接依赖|pip|
|org.apache.avro:avro|1.11.1|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.9|间接依赖|maven|
|org.apache.kerby:kerby-config|1.0.1|间接依赖|maven|
|com.google.cloud.bigdataoss:util|2.2.11|间接依赖|maven|
|org.apache.kerby:kerb-server|1.0.1|间接依赖|maven|
|com.kstruct:gethostname4j|1.0.0|间接依赖|maven|
|org.apache.kerby:kerb-util|1.0.1|间接依赖|maven|
|org.apache.kerby:kerb-client|1.0.1|间接依赖|maven|
|org.apache.commons:commons-csv|1.4|直接依赖|maven|
|org.eclipse.jetty:jetty-security|9.4.51.v20230217|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)