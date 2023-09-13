# apache/hive安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1702097406048993280.svg)](https://www.murphysec.com/console/report/1702019988767686656/1702097406048993280)

仓库描述：Apache Hive

仓库地址：[https://github.com/apache/hive](https://github.com/apache/hive)

| star：5064 | watch：334 | fork：4518 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-14 00:53:22 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-14 07:53:59 | 组件总数：803 | 漏洞总数：112 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache Xalan-Java 权限绕过漏洞|权限、特权和访问控制|[MPS-2014-1792](https://www.oscs1024.com/hd/MPS-2014-1792)|CVE-2014-0107|高危|
|Apache HttpClient 中间人攻击漏洞|输入验证不恰当|[MPS-2014-4288](https://www.oscs1024.com/hd/MPS-2014-4288)|CVE-2012-6153|中危|
|Square OkHttp 安全漏洞|证书验证不恰当|[MPS-2017-1023](https://www.oscs1024.com/hd/MPS-2017-1023)|CVE-2016-2402|中危|
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|Apache Commons Beanutils 存在不可信数据的反序列化漏洞|反序列化|[MPS-2019-10233](https://www.oscs1024.com/hd/MPS-2019-10233)|CVE-2019-10086|高危|
|Netty 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2019-12064](https://www.oscs1024.com/hd/MPS-2019-12064)|CVE-2019-16869|高危|
|Red Hat JBoss Enterprise Application Platform 代码问题漏洞|反序列化|[MPS-2019-12470](https://www.oscs1024.com/hd/MPS-2019-12470)|CVE-2019-10202|严重|
|​ hibernate-validator  存在跨站脚本（XSS）漏洞|XSS|[MPS-2019-14389](https://www.oscs1024.com/hd/MPS-2019-14389)|CVE-2019-10219|中危|
|jackson-mapper-asl <=1.9.13 XXE 注入漏洞|XXE|[MPS-2019-15048](https://www.oscs1024.com/hd/MPS-2019-15048)|CVE-2019-10172|高危|
|Apache Log4j SocketServer反序列化漏洞|反序列化|[MPS-2019-17271](https://www.oscs1024.com/hd/MPS-2019-17271)|CVE-2019-17571|严重|
|google-oauth-java-client <1.31.0授权不当漏洞|授权检查错误|[MPS-2020-10000](https://www.oscs1024.com/hd/MPS-2020-10000)|CVE-2020-7692|严重|
|Netty <=4.1.43.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1320](https://www.oscs1024.com/hd/MPS-2020-1320)|CVE-2020-7238|高危|
|Apache Calcite 访问控制错误漏洞|关键功能的认证机制缺失|[MPS-2020-14130](https://www.oscs1024.com/hd/MPS-2020-14130)|CVE-2020-13955|中危|
|Netty <4.1.44.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1526](https://www.oscs1024.com/hd/MPS-2020-1526)|CVE-2019-20444|严重|
|Netty <4.1.44.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1527](https://www.oscs1024.com/hd/MPS-2020-1527)|CVE-2019-20445|严重|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Netty ZlibDecoders 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2020-5127](https://www.oscs1024.com/hd/MPS-2020-5127)|CVE-2020-11612|高危|
|Apache Log4j2 SmtpAppender证书验证不当漏洞|证书验证不恰当|[MPS-2020-6684](https://www.oscs1024.com/hd/MPS-2020-6684)|CVE-2020-9488|低危|
|hibernate-validator 存在输入验证错误漏洞|代码注入|[MPS-2020-7077](https://www.oscs1024.com/hd/MPS-2020-7077)|CVE-2020-10693|中危|
|Apache Druid <0.20.0任意代码执行漏洞|代码注入|[MPS-2021-1023](https://www.oscs1024.com/hd/MPS-2021-1023)|CVE-2021-25646|高危|
|Apache Commons Compress 安存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10550](https://www.oscs1024.com/hd/MPS-2021-10550)|CVE-2021-35517|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10551](https://www.oscs1024.com/hd/MPS-2021-10551)|CVE-2021-35516|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10564](https://www.oscs1024.com/hd/MPS-2021-10564)|CVE-2021-36090|高危|
|Apache Commons Compress 无限循环漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-10565](https://www.oscs1024.com/hd/MPS-2021-10565)|CVE-2021-35515|高危|
|Eclipse Jetty 编码字符敏感信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-10800](https://www.oscs1024.com/hd/MPS-2021-10800)|CVE-2021-34429|中危|
|Netty <4.1.59.Final 存在不安全的临时文件漏洞||[MPS-2021-1580](https://www.oscs1024.com/hd/MPS-2021-1580)|CVE-2021-21290|中危|
|Apache Hadoop 权限管理不当漏洞|授权检查错误|[MPS-2021-1705](https://www.oscs1024.com/hd/MPS-2021-1705)|CVE-2020-9492|高危|
|Spring Framework <5.3.14 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18854](https://www.oscs1024.com/hd/MPS-2021-18854)|CVE-2021-22060|中危|
|Pivotal Spring Framework 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18890](https://www.oscs1024.com/hd/MPS-2021-18890)|CVE-2021-22096|中危|
|Google google-oauth-java-client 数据伪造问题漏洞|密码学签名的验证不恰当|[MPS-2021-19070](https://www.oscs1024.com/hd/MPS-2021-19070)|CVE-2021-22573|高危|
|Apache Hadoop YARN 远程代码执行漏洞|代码注入|[MPS-2021-20833](https://www.oscs1024.com/hd/MPS-2021-20833)|CVE-2021-25642|严重|
|io.netty:netty-codec-http2 <4.1.60.Final 存在 http 请求走私漏洞|HTTP请求走私|[MPS-2021-2435](https://www.oscs1024.com/hd/MPS-2021-2435)|CVE-2021-21295|中危|
|Apache Druid <0.22.0授权错误漏洞|授权检查错误|[MPS-2021-27767](https://www.oscs1024.com/hd/MPS-2021-27767)|CVE-2021-36749|中危|
|Netty Bzip2Decoder 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28116](https://www.oscs1024.com/hd/MPS-2021-28116)|CVE-2021-37136|高危|
|Netty 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28117](https://www.oscs1024.com/hd/MPS-2021-28117)|CVE-2021-37137|高危|
|Apache Commons Net <3.9.0 存在FTP跳转攻击漏洞|未授权敏感信息泄露|[MPS-2021-28440](https://www.oscs1024.com/hd/MPS-2021-28440)|CVE-2021-37533|中危|
|Apache Velocity 存在任意代码执行|代码注入|[MPS-2021-3061](https://www.oscs1024.com/hd/MPS-2021-3061)|CVE-2020-13936|高危|
|Netty <4.1.71.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2021-36922](https://www.oscs1024.com/hd/MPS-2021-36922)|CVE-2021-43797|中危|
|Apache Druid 远程代码执行漏洞|代码注入|[MPS-2021-3711](https://www.oscs1024.com/hd/MPS-2021-3711)|CVE-2021-26919|高危|
|Apache Druid 跨站脚本漏洞|XSS|[MPS-2021-38253](https://www.oscs1024.com/hd/MPS-2021-38253)|CVE-2021-44791|中危|
|Apache Log4j JMSAppender反序列化漏洞||[MPS-2021-38359](https://www.oscs1024.com/hd/MPS-2021-38359)|CVE-2021-4104|高危|
|Eclipse Jetty 资源管理错误漏洞|对异常条件的处理不恰当|[MPS-2021-3864](https://www.oscs1024.com/hd/MPS-2021-3864)|CVE-2021-28165|高危|
|Eclipse Jetty 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-55442](https://www.oscs1024.com/hd/MPS-2021-55442)|CVE-2021-34429|中危|
|Bouncy Castle 私钥信息泄露漏洞|竞争条件|[MPS-2021-7064](https://www.oscs1024.com/hd/MPS-2021-7064)|CVE-2020-15522|中危|
|Jakarta Expression Language <=3.0.3 存在输入验证错误漏洞|表达式语言注入|[MPS-2021-7671](https://www.oscs1024.com/hd/MPS-2021-7671)|CVE-2021-28170|中危|
|json-smart 存在拒绝服务漏洞|越界写入|[MPS-2021-7737](https://www.oscs1024.com/hd/MPS-2021-7737)|CVE-2021-31684|高危|
|Eclipse Jetty 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-8397](https://www.oscs1024.com/hd/MPS-2021-8397)|CVE-2021-28169|中危|
|Eclipse Jetty 存在信息泄露漏洞|不充分的会话过期机制|[MPS-2021-8884](https://www.oscs1024.com/hd/MPS-2021-8884)|CVE-2021-34428|低危|
|Apache Druid权限许可和访问控制问题漏洞|资源在另一范围的外部可控制索引|[MPS-2021-9406](https://www.oscs1024.com/hd/MPS-2021-9406)|CVE-2021-26920|中危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9827](https://www.oscs1024.com/hd/MPS-2021-9827)|CVE-2021-36373|中危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9847](https://www.oscs1024.com/hd/MPS-2021-9847)|CVE-2021-36374|中危|
|Vmware Spring Framework 安全漏洞|不加限制或调节的资源分配|[MPS-2022-1080](https://www.oscs1024.com/hd/MPS-2022-1080)|CVE-2022-22950|中危|
|Pivotal Spring Framework 安全限制绕过漏洞|大小写敏感处理不恰当|[MPS-2022-1098](https://www.oscs1024.com/hd/MPS-2022-1098)|CVE-2022-22968|中危|
|Spring Framework spring-beans 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1101](https://www.oscs1024.com/hd/MPS-2022-1101)|CVE-2022-22970|中危|
|AWS SDK for Java 路径遍历漏洞|路径遍历|[MPS-2022-11189](https://www.oscs1024.com/hd/MPS-2022-11189)|CVE-2022-31159|高危|
|org.apache.pig:pig 存在信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-11732](https://www.oscs1024.com/hd/MPS-2022-11732)||中危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|org.mozilla:rhino <1.7.12 存在XXE漏洞|XXE|[MPS-2022-11928](https://www.oscs1024.com/hd/MPS-2022-11928)||高危|
|io.netty:netty-codec-http <4.1.53.Final 存在拒绝服务漏洞|拒绝服务|[MPS-2022-12064](https://www.oscs1024.com/hd/MPS-2022-12064)||中危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|com.beust:jcommander 存在从非可信控制范围包含功能例程漏洞||[MPS-2022-12225](https://www.oscs1024.com/hd/MPS-2022-12225)||中危|
|org.glassfish.jersey.media:jersey-media-jaxb <2.31 存在XXE漏洞|XML实体扩展|[MPS-2022-12234](https://www.oscs1024.com/hd/MPS-2022-12234)||高危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|org.apache.hive:hive-service 存在跨站脚本漏洞|XSS|[MPS-2022-12394](https://www.oscs1024.com/hd/MPS-2022-12394)||中危|
|org.apache.hadoop:hadoop-hdfs < 3.3.2 存在XXE漏洞|XXE|[MPS-2022-12474](https://www.oscs1024.com/hd/MPS-2022-12474)||中危|
|org.apache.maven.shared:maven-shared-utils 存在命令注入漏洞|命令注入|[MPS-2022-12562](https://www.oscs1024.com/hd/MPS-2022-12562)||高危|
|Apache Log4j JDBCAppender SQL注入漏洞|SQL注入|[MPS-2022-1444](https://www.oscs1024.com/hd/MPS-2022-1444)|CVE-2022-23305|严重|
|Apache Log4j Chainsaw反序列化漏洞|反序列化|[MPS-2022-1445](https://www.oscs1024.com/hd/MPS-2022-1445)|CVE-2022-23307|高危|
|Apache Log4j 反序列化漏洞|反序列化|[MPS-2022-1446](https://www.oscs1024.com/hd/MPS-2022-1446)|CVE-2022-23302|高危|
|Eclipse Jetty URI注入漏洞|注入|[MPS-2022-18060](https://www.oscs1024.com/hd/MPS-2022-18060)|CVE-2022-2047|低危|
|Apache XercesJ <=2.12.1 存在XML注入漏洞|XPath盲注|[MPS-2022-1864](https://www.oscs1024.com/hd/MPS-2022-1864)|CVE-2022-23437|中危|
|Apache Xalan 存在整数截断漏洞|数值截断错误|[MPS-2022-19461](https://www.oscs1024.com/hd/MPS-2022-19461)|CVE-2022-34169|中危|
|Netty 存在信息泄露漏洞||[MPS-2022-3790](https://www.oscs1024.com/hd/MPS-2022-3790)|CVE-2022-24823|中危|
|Apache Hadoop 存在shell命令注入漏洞|参数注入或修改|[MPS-2022-4190](https://www.oscs1024.com/hd/MPS-2022-4190)|CVE-2022-25168|严重|
|Apache Calcite Avatica 代码注入漏洞|代码注入|[MPS-2022-51965](https://www.oscs1024.com/hd/MPS-2022-51965)|CVE-2022-36364|高危|
|Bouncy Castle <1.69 认证绕过漏洞|密码学问题|[MPS-2022-54305](https://www.oscs1024.com/hd/MPS-2022-54305)||中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|Apache Calcite 存在 XXE 漏洞|XXE|[MPS-2022-56508](https://www.oscs1024.com/hd/MPS-2022-56508)|CVE-2022-39135|中危|
|XStream 缓冲区错误漏洞|输入验证不恰当|[MPS-2022-57061](https://www.oscs1024.com/hd/MPS-2022-57061)|CVE-2022-40156|低危|
|xstream project跨界内存写漏洞|跨界内存写|[MPS-2022-57062](https://www.oscs1024.com/hd/MPS-2022-57062)|CVE-2022-40155|高危|
|xstream project跨界内存写漏洞|跨界内存写|[MPS-2022-57063](https://www.oscs1024.com/hd/MPS-2022-57063)|CVE-2022-40154|高危|
|XStream 缓冲区错误漏洞|越界写入|[MPS-2022-57065](https://www.oscs1024.com/hd/MPS-2022-57065)|CVE-2022-40152|高危|
|Jettison <1.5.2 拒绝服务漏洞|拒绝服务|[MPS-2022-57067](https://www.oscs1024.com/hd/MPS-2022-57067)|CVE-2022-40150|高危|
|Jettison <1.5.1 拒绝服务漏洞|越界写入|[MPS-2022-57068](https://www.oscs1024.com/hd/MPS-2022-57068)|CVE-2022-40149|高危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|Netty <4.1.86.Final 存在拒绝服务漏洞|未经控制的递归|[MPS-2022-58518](https://www.oscs1024.com/hd/MPS-2022-58518)|CVE-2022-41881|中危|
|Netty <4.1.86.Final 存在 CRLF 注入漏洞||[MPS-2022-58552](https://www.oscs1024.com/hd/MPS-2022-58552)|CVE-2022-41915|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
|Apache Hadoop 存在路径遍历漏洞|路径遍历|[MPS-2022-5920](https://www.oscs1024.com/hd/MPS-2022-5920)|CVE-2022-26612|严重|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Jettison <1.5.2 拒绝服务漏洞|越界写入|[MPS-2022-64973](https://www.oscs1024.com/hd/MPS-2022-64973)|CVE-2022-45685|高危|
|Apache Ivy<2.5.2 存在XXE漏洞|输入验证不恰当|[MPS-2022-67125](https://www.oscs1024.com/hd/MPS-2022-67125)|CVE-2022-46751|中危|
|spring-beans 远程代码执行漏洞(Spring4Shell)|表达式语言注入|[MPS-2022-6820](https://www.oscs1024.com/hd/MPS-2022-6820)|CVE-2022-22965|严重|
|Oracle MySQL 安全漏洞||[MPS-2022-68556](https://www.oscs1024.com/hd/MPS-2022-68556)|CVE-2023-21971|中危|
|Apache Druid 点击劫持漏洞|渲染 UI 层或帧的不当限制|[MPS-2022-8141](https://www.oscs1024.com/hd/MPS-2022-8141)|CVE-2022-28889|中危|
|Apache Maven Shared Utils 系统命令注入漏洞|命令注入|[MPS-2022-9177](https://www.oscs1024.com/hd/MPS-2022-9177)|CVE-2022-29599|严重|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Apache Kafka Connect 模块JNDI注入漏洞|反序列化|[MPS-2023-3834](https://www.oscs1024.com/hd/MPS-2023-3834)|CVE-2023-25194|高危|
|Eclipse Jetty 资源管理错误漏洞|拒绝服务|[MPS-2023-4997](https://www.oscs1024.com/hd/MPS-2023-4997)|CVE-2023-26048|中危|
|Eclipse Jetty 信息泄露漏洞|XSS|[MPS-2023-4998](https://www.oscs1024.com/hd/MPS-2023-4998)|CVE-2023-26049|中危|
|Apache Druid中Kafka配置远程代码执行漏洞|注入|[MPS-2023-6623](https://www.oscs1024.com/hd/MPS-2023-6623)||高危|
|netplex json-smart 安全漏洞|未经控制的递归|[MPS-2023-7760](https://www.oscs1024.com/hd/MPS-2023-7760)|CVE-2023-1370|高危|
|Jettison 安全漏洞|未经控制的递归|[MPS-2023-8270](https://www.oscs1024.com/hd/MPS-2023-8270)|CVE-2023-1436|高危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|json-io 缓冲区错误漏洞|越界写入|[MPS-jtye-gw8s](https://www.oscs1024.com/hd/MPS-jtye-gw8s)|CVE-2023-34610|高危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.apache.commons:commons-compress|1.19|1.21|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|org.eclipse.jetty:jetty-server|9.4.40.v20210413|12.0.0.beta0|直接依赖|建议修复|C:0|H:0|M:2|L:1|
|org.apache.hadoop:hadoop-yarn-server-resourcemanager|3.3.1|3.3.4|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.apache.hadoop:hadoop-hdfs-client|2.8.5|3.2.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|commons-beanutils:commons-beanutils|1.9.3|1.9.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.google.guava:guava|16.0.1|32.0.0-jre|直接依赖|建议修复|C:0|H:0|M:2|L:1|
|org.yaml:snakeyaml|1.31|2.0|间接依赖|建议修复|C:0|H:1|M:1|L:1|
|org.glassfish.jersey.media:jersey-media-jaxb|2.25.1|2.31|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.woodstox:woodstox-core|5.3.0|6.4.0|间接依赖|建议修复|C:0|H:3|M:0|L:1|
|org.xerial.snappy:snappy-java|1.1.8.2|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.springframework:spring-context|4.3.20.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec|4.1.42.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|org.apache.calcite.avatica:avatica-core|1.12.0|1.22.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.maven.shared:maven-shared-utils|0.6|3.3.3|间接依赖|建议修复|C:1|H:1|M:0|L:0|
|io.netty:netty-codec-http|4.1.42.Final|4.1.86.final|间接依赖|建议修复|C:2|H:1|M:5|L:0|
|org.apache.druid:druid-core|0.17.1|0.23.0|间接依赖|建议修复|C:0|H:3|M:3|L:0|
|org.eclipse.jetty:jetty-io|9.4.12.v20180830|11.0.10|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.squareup.okhttp:okhttp|2.4.0|2.7.4|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|io.netty:netty-handler|4.1.77.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|net.minidev:json-smart|2.4.2|2.4.9|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|org.apache.druid.extensions:druid-hdfs-storage|0.17.1|0.22.0|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|log4j:log4j|1.2.17||间接依赖|建议修复|C:2|H:3|M:0|L:1|
|org.apache.kafka:kafka-clients|2.5.0|3.4.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.42.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|org.springframework:spring-beans|4.3.20.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.mozilla:rhino|1.7.11|1.7.12|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.codehaus.jackson:jackson-mapper-asl|1.9.2||间接依赖|建议修复|C:1|H:1|M:0|L:0|
|org.codehaus.jettison:jettison|1.1|1.5.4|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|com.cedarsoftware:json-io|2.5.1||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.amazonaws:aws-java-sdk-s3|1.11.199|1.12.261|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-io|9.2.26.v20180806|11.0.10|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.squareup.okio:okio|1.6.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.hadoop:hadoop-common|3.3.1|3.3.3|直接依赖|建议修复|C:2|H:0|M:0|L:0|
|io.netty:netty|3.10.6.Final||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.codehaus.jackson:jackson-mapper-asl|1.8.8||间接依赖|建议修复|C:1|H:1|M:0|L:0|
|io.netty:netty|3.10.5.Final||直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.velocity:velocity|1.5||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.mysql:mysql-connector-j|8.0.31|8.0.33|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.apache.druid:druid-server|0.17.1|0.22.0|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.google.oauth-client:google-oauth-client|1.22.0|1.33.3|间接依赖|建议修复|C:1|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.5|2.14.0-rc1|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.eclipse.jetty:jetty-webapp|9.4.40.v20210413|11.0.6|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13||间接依赖|建议修复|C:1|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-http|9.4.40.v20210413|11.0.10|直接依赖|建议修复|C:0|H:0|M:1|L:1|
|com.squareup.okio:okio|1.4.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.76.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|22.0|32.0.0-jre|直接依赖|建议修复|C:0|H:0|M:2|L:1|
|xalan:xalan|2.7.0|2.7.2|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|org.apache.druid:druid-console|0.17.1|0.23.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.hibernate:hibernate-validator|5.2.5.Final|6.1.3.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.bouncycastle:bcprov-jdk15on|1.64|1.69|直接依赖|可选修复|C:0|H:0|M:3|L:0|
|org.eclipse.jetty:jetty-servlets|9.4.12.v20180830|11.0.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.hive:hive-service|4.0.0-beta-2-SNAPSHOT|release-2.3.8-rc2|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-core|4.3.20.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.glassfish:javax.el|3.0.0||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.calcite:calcite-core|1.25.0|1.32.0|直接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-expression|4.3.20.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|commons-httpclient:commons-httpclient|3.1||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.ivy:ivy|2.5.1|2.5.2|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-codec:commons-codec|1.11|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|io.netty:netty-codec-haproxy|4.1.77.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.eclipse.jetty:jetty-servlets|9.4.40.v20210413|11.0.3|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-common|4.1.76.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-net:commons-net|3.6|3.9.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.pig:pig|0.16.0||直接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-common|4.1.42.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.code.gson:gson|2.2.4|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|xerces:xercesImpl|2.9.1|2.12.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.hadoop:hadoop-hdfs|3.3.1|3.3.2|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-http|4.1.77.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.beust:jcommander|1.48|1.75|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|ant:ant|1.6.5|1.10.11|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|io.netty:netty-transport-native-epoll|4.1.29.Final|4.1.59.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|CDDL-1.1|18|Low|
|Apache-2.0|631|Low|
|BSD-2-Clause|7|Low|
|自定义许可证|84|Low|
|CDDL-1.0|3|Low|
|LGPL-2.1|8|Medium|
|BSD-3-Clause|13|Low|
|EPL-1.0|10|Low|
|MIT|22|Low|
|MPL-2.0|2|Low|
|EPL-2.0|3|Low|
|MPL-1.1|2|Low|
|WTFPL|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.sun.xml.bind:jaxb-impl|2.2.3-1|间接依赖|maven|
|com.beust:jcommander|1.78|间接依赖|maven|
|com.github.luben:zstd-jni|1.3.3-1|间接依赖|maven|
|org.apache.derby:derbyclient|10.14.2.0|间接依赖|maven|
|org.eclipse.jetty:jetty-util-ajax|9.4.40.v20210413|间接依赖|maven|
|org.apache.curator:curator-recipes|5.2.0|直接依赖|maven|
|io.netty:netty-handler|4.1.42.Final|间接依赖|maven|
|com.squareup.okhttp:okhttp|2.4.0|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.77.Final|间接依赖|maven|
|org.apache.hbase:hbase-procedure|2.0.0-alpha4|间接依赖|maven|
|ant:ant|1.6.5|间接依赖|maven|
|io.airlift:airline|0.7|间接依赖|maven|
|org.datanucleus:datanucleus-api-jdo|5.2.8|直接依赖|maven|
|org.apache.tez:tez-examples|0.10.2|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.7.1|直接依赖|maven|
|net.sf.kosmosfs:kfs|0.3|间接依赖|maven|
|org.apache.hive.hcatalog:hive-hcatalog-server-extensions|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|io.jsonwebtoken:jjwt-impl|0.10.5|直接依赖|maven|
|org.apache.kudu:kudu-client|1.12.0|直接依赖|maven|
|org.eclipse.jetty:jetty-servlets|9.4.40.v20210413|直接依赖|maven|
|de.ruedigermoeller:fst|2.50|间接依赖|maven|
|commons-daemon:commons-daemon|1.0.13|间接依赖|maven|
|org.codehaus.woodstox:stax2-api|4.2.1|间接依赖|maven|
|com.google.inject.extensions:guice-servlet|4.1.0|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-api|9.4.40.v20210413|间接依赖|maven|
|org.apache.druid.extensions:druid-avro-extensions|0.17.1|直接依赖|maven|
|org.powermock:powermock-module-junit4|2.0.2|直接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.8.8|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.13.5|直接依赖|maven|
|org.apache.calcite:calcite-core|1.25.0|直接依赖|maven|
|org.asynchttpclient:async-http-client-netty-utils|2.5.3|间接依赖|maven|
|org.wildfly.openssl:wildfly-openssl|1.0.7.Final|间接依赖|maven|
|org.glassfish.hk2.external:aopalliance-repackaged|2.5.0-b32|间接依赖|maven|
|org.mortbay.jetty:servlet-api-2.5|6.1.14|间接依赖|maven|
|org.mariadb.jdbc:mariadb-java-client|2.5.0|直接依赖|maven|
|org.apache.hive.shims:hive-shims-0.23|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.apache.tez:tez-tests|0.10.2|直接依赖|maven|
|com.esri.geometry:esri-geometry-api|2.2.0|间接依赖|maven|
|org.openjdk.jmh:jmh-core|1.21|直接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.1|间接依赖|maven|
|org.apache.iceberg:iceberg-common|1.3.0|直接依赖|maven|
|org.apache.hive:hive-parser|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.antlr:antlr-runtime|3.5.2|直接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.64|直接依赖|maven|
|org.opensaml:opensaml-messaging-impl|3.4.5|间接依赖|maven|
|org.opensaml:opensaml-security-impl|3.4.5|间接依赖|maven|
|io.netty:netty-codec-stomp|4.1.77.Final|间接依赖|maven|
|io.netty:netty-all|4.1.77.Final|直接依赖|maven|
|io.netty:netty-resolver-dns|4.1.29.Final|间接依赖|maven|
|org.apache.tez:tez-runtime-library|0.10.2|直接依赖|maven|
|org.springframework:spring-expression|4.3.20.RELEASE|间接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.9.13|间接依赖|maven|
|org.apache.druid:druid-server|0.17.1|直接依赖|maven|
|org.ow2.asm:asm-tree|9.0|间接依赖|maven|
|io.netty:netty-common|4.1.77.Final|间接依赖|maven|
|javax.websocket:javax.websocket-client-api|1.0|间接依赖|maven|
|com.google.re2j:re2j|1.2|直接依赖|maven|
|org.mortbay.jetty:servlet-api|2.5-20081211|间接依赖|maven|
|org.eclipse.aether:aether-connector-file|0.9.0.M2|间接依赖|maven|
|com.opencsv:opencsv|5.6|间接依赖|maven|
|org.postgresql:postgresql|42.5.1|直接依赖|maven|
|org.apache.thrift:libthrift|0.16.0|直接依赖|maven|
|com.amazonaws:aws-java-sdk-ec2|1.11.199|间接依赖|maven|
|org.apache.hive:hive-exec|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.antlr:antlr4-runtime|4.5.1|间接依赖|maven|
|org.jruby.joni:joni|2.1.27|间接依赖|maven|
|org.opensaml:opensaml-saml-api|3.4.5|间接依赖|maven|
|org.eclipse.jetty:jetty-io|9.2.26.v20180806|间接依赖|maven|
|com.google.guava:guava|16.0.1|直接依赖|maven|
|io.airlift:aircompressor|0.21|间接依赖|maven|
|org.apache.maven:maven-artifact|3.6.0|间接依赖|maven|
|com.google.inject:guice|4.1.0|直接依赖|maven|
|commons-digester:commons-digester|1.8.1|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-resourcemanager|3.3.1|直接依赖|maven|
|org.glassfish.jersey.core:jersey-common|2.25.1|间接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.77.Final|间接依赖|maven|
|org.mozilla:rhino|1.7.11|间接依赖|maven|
|org.apache.hive:hive-llap-tez|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.apache.datasketches:datasketches-java|1.3.0-incubating|间接依赖|maven|
|org.opensaml:opensaml-messaging-api|3.4.5|间接依赖|maven|
|org.checkerframework:checker-qual|2.5.7|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-scala_2.12|2.13.5|间接依赖|maven|
|com.squareup.okio:okio|1.6.0|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.2.2|间接依赖|maven|
|org.apache.atlas:atlas-client-common|2.1.0|直接依赖|maven|
|org.eclipse.jetty:jetty-continuation|9.4.12.v20180830|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.13.5|间接依赖|maven|
|org.eclipse.jetty:apache-jsp|9.4.40.v20210413|间接依赖|maven|
|javax.transaction:javax.transaction-api|1.3|间接依赖|maven|
|org.objenesis:objenesis|3.3|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.14.0|间接依赖|maven|
|com.lmax:disruptor|3.3.7|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.5|直接依赖|maven|
|org.apache.commons:commons-crypto|1.0.0|间接依赖|maven|
|org.apache.tez:tez-mapreduce|0.10.2|直接依赖|maven|
|com.sun.jersey:jersey-server|1.19|间接依赖|maven|
|org.jvnet.mimepull:mimepull|1.9.3|间接依赖|maven|
|org.apache.velocity:velocity|1.5|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.76.Final|间接依赖|maven|
|commons-codec:commons-codec|1.11|间接依赖|maven|
|org.apache.maven:maven-settings|3.1.1|间接依赖|maven|
|org.glassfish.jersey.bundles.repackaged:jersey-guava|2.25.1|间接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5|5.2|间接依赖|maven|
|org.jline:jline-terminal|3.12.1|间接依赖|maven|
|org.codehaus.jettison:jettison|1.5.4|直接依赖|maven|
|com.cedarsoftware:json-io|2.5.1|间接依赖|maven|
|org.apache.kerby:kerb-core|1.0.1|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-servlet|9.4.40.v20210413|间接依赖|maven|
|org.codehaus.jackson:jackson-mapper-asl|1.8.8|间接依赖|maven|
|org.apache.hive:patched-iceberg-api|patched-1.3.0-4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.apache.accumulo:accumulo-master|1.10.1|间接依赖|maven|
|org.apache.kerby:kerb-server|1.0.1|间接依赖|maven|
|org.codehaus.plexus:plexus-utils|3.0.24|间接依赖|maven|
|org.opensaml:opensaml-security-api|3.4.5|间接依赖|maven|
|org.apache.calcite:calcite-druid|1.25.0|直接依赖|maven|
|org.apache.hive:hive-llap-common|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.apache.hive:patched-iceberg-core|patched-1.3.0-4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|commons-cli:commons-cli|1.2|间接依赖|maven|
|org.junit.platform:junit-platform-commons|1.6.2|间接依赖|maven|
|org.opensaml:opensaml-soap-impl|3.4.5|间接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.51.0|间接依赖|maven|
|org.asynchttpclient:async-http-client-netty-utils|2.12.3|间接依赖|maven|
|org.apache.hive:hive-hbase-handler|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.eclipse.jetty:jetty-proxy|9.4.12.v20180830|间接依赖|maven|
|org.codehaus.plexus:plexus-velocity|1.1.7|间接依赖|maven|
|org.apache.maven.doxia:doxia-core|1.2|间接依赖|maven|
|dk.brics.automaton:automaton|1.11-8|间接依赖|maven|
|net.minidev:json-smart|2.4.10|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.0-1|间接依赖|maven|
|org.apache.datasketches:datasketches-java|1.1.0-incubating|间接依赖|maven|
|org.apache.htrace:htrace-core|3.1.0-incubating|间接依赖|maven|
|org.fusesource.leveldbjni:leveldbjni-all|1.8|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.76.Final|间接依赖|maven|
|org.apache.commons:commons-text|1.4|间接依赖|maven|
|commons-logging:commons-logging|1.1.3|直接依赖|maven|
|org.roaringbitmap:shims|0.9.22|间接依赖|maven|
|org.apache.maven.doxia:doxia-logging-api|1.4|间接依赖|maven|
|org.tukaani:xz|1.8|间接依赖|maven|
|org.apache.avro:avro|1.11.1|直接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|org.apache.hbase.thirdparty:hbase-shaded-protobuf|1.0.1|间接依赖|maven|
|com.amazonaws:aws-java-sdk-bundle|1.12.132|间接依赖|maven|
|org.lz4:lz4-java|1.7.1|间接依赖|maven|
|org.apache.druid.extensions:druid-kafka-indexing-service|0.17.1|直接依赖|maven|
|org.apache.commons:commons-jexl3|3.3|直接依赖|maven|
|org.jruby.joni:joni|2.1.11|间接依赖|maven|
|com.beust:jcommander|1.48|间接依赖|maven|
|org.openjdk.jmh:jmh-generator-annprocess|1.23|直接依赖|maven|
|net.minidev:json-smart|2.4.2|间接依赖|maven|
|log4j:log4j|1.2.17|间接依赖|maven|
|org.jetbrains:annotations|16.0.2|直接依赖|maven|
|org.jline:jline-terminal-jansi|3.12.1|间接依赖|maven|
|io.netty:netty-transport|4.1.77.Final|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.13|直接依赖|maven|
|org.jline:jline-style|3.12.1|间接依赖|maven|
|org.apache.hive:hive-cli|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|xerces:xercesImpl|2.12.2|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-common|9.4.40.v20210413|间接依赖|maven|
|org.opensaml:opensaml-storage-api|3.4.5|间接依赖|maven|
|org.apache.ant:ant-launcher|1.10.13|间接依赖|maven|
|org.apache.hive:hive-jdbc-handler|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.apache.curator:curator-framework|4.0.0|直接依赖|maven|
|org.checkerframework:checker-qual|3.19.0|间接依赖|maven|
|org.apache.derby:derbynet|10.14.2.0|间接依赖|maven|
|org.datanucleus:datanucleus-rdbms|5.2.10|直接依赖|maven|
|org.apache.commons:commons-csv|1.0|间接依赖|maven|
|javax.servlet.jsp:jsp-api|2.1|间接依赖|maven|
|org.apache.maven:maven-project|2.2.1|间接依赖|maven|
|com.squareup.okio:okio|1.4.0|间接依赖|maven|
|sqlline:sqlline|1.9.0|直接依赖|maven|
|org.roaringbitmap:RoaringBitmap|0.8.11|间接依赖|maven|
|org.apache.commons:commons-text|1.10.0|直接依赖|maven|
|org.objenesis:objenesis|2.5.1|间接依赖|maven|
|com.microsoft.sqlserver:mssql-jdbc|6.2.1.jre8|直接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|9.8.1|间接依赖|maven|
|org.apache.hive:hive-contrib|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|io.netty:netty-codec-memcache|4.1.77.Final|间接依赖|maven|
|javax.json:javax.json-api|1.0|间接依赖|maven|
|org.slf4j:slf4j-log4j12|1.7.30|直接依赖|maven|
|com.zaxxer:HikariCP-java7|2.4.12|间接依赖|maven|
|org.roaringbitmap:shims|0.7.45|间接依赖|maven|
|com.google.re2j:re2j|1.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.5|直接依赖|maven|
|org.apache.pig:pig|0.16.0|直接依赖|maven|
|org.eclipse.jdt:core|3.1.1|间接依赖|maven|
|org.opensaml:opensaml-core|3.4.5|间接依赖|maven|
|io.netty:netty-resolver|4.1.76.Final|间接依赖|maven|
|io.netty:netty-codec-http|4.1.42.Final|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.30|直接依赖|maven|
|org.apache.yetus:audience-annotations|0.12.0|间接依赖|maven|
|org.jamon:jamon-runtime|2.4.1|直接依赖|maven|
|org.jruby.jcodings:jcodings|1.0.18|间接依赖|maven|
|org.antlr:stringtemplate|3.2.1|间接依赖|maven|
|org.apache.maven.wagon:wagon-provider-api|1.0|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|直接依赖|maven|
|org.eclipse.jetty.toolchain:jetty-schemas|3.1.2|间接依赖|maven|
|org.apache.maven.doxia:doxia-module-xhtml|1.4|间接依赖|maven|
|org.apache.druid.extensions:druid-bloom-filter|0.17.1|直接依赖|maven|
|com.carrotsearch:hppc|0.7.2|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.3.2|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|3.2.4|间接依赖|maven|
|com.sun.istack:istack-commons-runtime|3.0.7|间接依赖|maven|
|net.minidev:accessors-smart|2.4.2|间接依赖|maven|
|org.opensaml:opensaml-profile-api|3.4.5|间接依赖|maven|
|org.apache.maven.plugins:maven-jxr-plugin|2.5|直接依赖|maven|
|io.netty:netty-resolver|4.1.77.Final|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-client|3.3.1|直接依赖|maven|
|org.eclipse.jetty:jetty-plus|9.4.40.v20210413|间接依赖|maven|
|commons-net:commons-net|3.6|间接依赖|maven|
|org.apache.kerby:kerby-asn1|1.0.1|间接依赖|maven|
|org.schemarepo:schema-repo-client|0.1.3|间接依赖|maven|
|org.eclipse.jetty:jetty-jaas|9.4.40.v20210413|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.2-3|间接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|5.3.0|间接依赖|maven|
|io.netty:netty-buffer|4.1.76.Final|间接依赖|maven|
|asm:asm|3.3.1|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|3.3.1|直接依赖|maven|
|org.opensaml:opensaml-xmlsec-impl|3.4.5|间接依赖|maven|
|io.grpc:grpc-api|1.51.0|间接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.60|间接依赖|maven|
|com.google.inject:guice|4.0|间接依赖|maven|
|commons-codec:commons-codec|1.15|直接依赖|maven|
|org.eclipse.jetty:jetty-servlets|9.4.12.v20180830|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.21.7|直接依赖|maven|
|org.apache.hadoop:hadoop-client|3.3.1|直接依赖|maven|
|org.springframework:spring-beans|4.3.20.RELEASE|间接依赖|maven|
|org.apache.druid.extensions:druid-hdfs-storage|0.17.1|直接依赖|maven|
|org.apache.hadoop:hadoop-hdfs-client|3.3.1|直接依赖|maven|
|net.bytebuddy:byte-buddy|1.10.13|间接依赖|maven|
|org.ehcache:ehcache|3.3.1|间接依赖|maven|
|net.java.dev.jna:jna|4.5.1|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.29.Final|间接依赖|maven|
|io.grpc:grpc-core|1.51.0|间接依赖|maven|
|org.apache.arrow:arrow-memory-netty|12.0.0|直接依赖|maven|
|org.apache.kerby:kerb-client|1.0.1|间接依赖|maven|
|org.apache.hive:hive-llap-client|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|io.grpc:grpc-context|1.51.0|间接依赖|maven|
|org.eclipse.jetty:jetty-runner|9.4.40.v20210413|直接依赖|maven|
|io.netty:netty-buffer|4.1.77.Final|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-smile-provider|2.13.5|间接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|2.9.0|间接依赖|maven|
|org.eclipse.aether:aether-api|0.9.0.M2|间接依赖|maven|
|com.google.api-client:google-api-client|1.22.0|间接依赖|maven|
|com.esotericsoftware:reflectasm|1.11.9|直接依赖|maven|
|org.apache.accumulo:accumulo-shell|1.10.1|间接依赖|maven|
|org.javassist:javassist|3.27.0-GA|间接依赖|maven|
|org.apache.iceberg:iceberg-api|1.3.0|直接依赖|maven|
|org.apache.tez:tez-runtime-internals|0.10.2|直接依赖|maven|
|com.sun.jersey:jersey-servlet|1.19|直接依赖|maven|
|io.dropwizard.metrics:metrics-jvm|3.1.0|直接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.8.0|间接依赖|maven|
|org.apache.hadoop:hadoop-common|3.3.1|直接依赖|maven|
|io.netty:netty|3.10.5.Final|直接依赖|maven|
|org.apache.druid.extensions:postgresql-metadata-storage|0.17.1|直接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.77.Final|间接依赖|maven|
|org.apache.orc:orc-tools|1.8.3|直接依赖|maven|
|org.roaringbitmap:RoaringBitmap|0.7.45|间接依赖|maven|
|org.apache.datasketches:datasketches-hive|1.1.0-incubating|直接依赖|maven|
|org.apache.kerby:kerb-identity|1.0.1|间接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5-h2|5.2|间接依赖|maven|
|org.apache.iceberg:iceberg-data|1.3.0|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-registry|3.3.1|直接依赖|maven|
|com.google.code.gson:gson|2.9.0|直接依赖|maven|
|org.apache.htrace:htrace-core|3.2.0-incubating|间接依赖|maven|
|javax.el:javax.el-api|3.0.0|间接依赖|maven|
|com.sun.jersey:jersey-bundle|1.19.3|直接依赖|maven|
|com.jayway.jsonpath:json-path|2.8.0|直接依赖|maven|
|org.schemarepo:schema-repo-api|0.1.3|间接依赖|maven|
|javax.ws.rs:javax.ws.rs-api|2.0.1|直接依赖|maven|
|org.apache.hive:kafka-handler|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.antlr:ST4|4.0.4|直接依赖|maven|
|com.typesafe.scala-logging:scala-logging_2.12|3.9.2|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.76.Final|间接依赖|maven|
|org.apache.hbase:hbase-replication|2.0.0-alpha4|间接依赖|maven|
|org.apache.hive:hive-beeline|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.77.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.5|直接依赖|maven|
|io.netty:netty-resolver-dns|4.1.77.Final|间接依赖|maven|
|org.apache.htrace:htrace-core4|4.1.0-incubating|间接依赖|maven|
|org.eclipse.jetty:jetty-http|9.4.40.v20210413|直接依赖|maven|
|javax.xml.stream:stax-api|1.0-2|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.77.Final|间接依赖|maven|
|org.eclipse.jetty:jetty-client|9.4.40.v20210413|间接依赖|maven|
|org.glassfish.jersey.core:jersey-server|2.25.1|间接依赖|maven|
|io.netty:netty-transport|4.1.76.Final|间接依赖|maven|
|org.eclipse.jetty:jetty-server|9.4.40.v20210413|直接依赖|maven|
|com.sun.xml.fastinfoset:FastInfoset|1.2.15|间接依赖|maven|
|io.netty:netty-codec-xml|4.1.77.Final|间接依赖|maven|
|net.bytebuddy:byte-buddy-agent|1.10.13|间接依赖|maven|
|org.ow2.asm:asm-tree|7.1|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.2.11|间接依赖|maven|
|org.apache.accumulo:accumulo-start|1.10.1|直接依赖|maven|
|com.esotericsoftware:minlog|1.3.1|间接依赖|maven|
|org.apache.iceberg:iceberg-bundled-guava|1.3.0|直接依赖|maven|
|com.cronutils:cron-utils|9.1.6|直接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.77.Final|间接依赖|maven|
|oro:oro|2.0.8|间接依赖|maven|
|org.glassfish.hk2:hk2-locator|2.5.0-b32|间接依赖|maven|
|org.apache.commons:commons-configuration2|2.1.1|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-csv|2.13.5|间接依赖|maven|
|org.apache.parquet:parquet-avro|1.13.1|间接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.40.v20210413|间接依赖|maven|
|net.spy:spymemcached|2.12.3|间接依赖|maven|
|com.sun.activation:jakarta.activation|1.2.2|间接依赖|maven|
|org.openjdk.jmh:jmh-core|1.23|直接依赖|maven|
|io.netty:netty-codec|4.1.76.Final|间接依赖|maven|
|org.apache.commons:commons-lang3|3.7|间接依赖|maven|
|org.asynchttpclient:async-http-client|2.12.3|间接依赖|maven|
|org.glassfish:javax.el|3.0.0|间接依赖|maven|
|io.netty:netty-codec|4.1.42.Final|间接依赖|maven|
|io.confluent:kafka-schema-registry-client|3.0.1|间接依赖|maven|
|org.apache.logging.log4j:log4j-web|2.18.0|直接依赖|maven|
|com.sun.jersey:jersey-client|1.15|间接依赖|maven|
|commons-lang:commons-lang|2.1|间接依赖|maven|
|org.cryptacular:cryptacular|1.2.4|间接依赖|maven|
|org.apache.commons:commons-compress|1.23.0|直接依赖|maven|
|com.google.code.gson:gson|2.2.4|间接依赖|maven|
|org.opensaml:opensaml-profile-impl|3.4.5|间接依赖|maven|
|org.apache.geronimo.specs:geronimo-jcache_1.0_spec|1.0-alpha-1|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.77.Final|间接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.18.0|直接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.21|间接依赖|maven|
|org.apache.maven:maven-repository-metadata|2.2.1|间接依赖|maven|
|org.javassist:javassist|3.28.0-GA|间接依赖|maven|
|org.apache.hive:hive-storage-api|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|io.netty:netty-transport-rxtx|4.1.77.Final|间接依赖|maven|
|org.glassfish.hk2:osgi-resource-locator|1.0.1|间接依赖|maven|
|org.apache.druid:druid-services|0.17.1|直接依赖|maven|
|org.roaringbitmap:RoaringBitmap|0.9.44|间接依赖|maven|
|org.apache.hive:hive-testutils|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.eclipse.jetty.websocket:javax-websocket-server-impl|9.4.40.v20210413|间接依赖|maven|
|org.opensaml:opensaml-storage-impl|3.4.5|间接依赖|maven|
|com.google.http-client:google-http-client-jackson2|1.22.0|间接依赖|maven|
|org.glassfish.corba:glassfish-corba-omgapi|4.2.2|间接依赖|maven|
|commons-validator:commons-validator|1.6|间接依赖|maven|
|org.apache.kerby:token-provider|1.0.1|间接依赖|maven|
|org.jdbi:jdbi|2.63.1|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.8.4|直接依赖|maven|
|net.java.dev.jna:jna|5.2.0|间接依赖|maven|
|info.picocli:picocli|3.1.0|直接依赖|maven|
|org.mortbay.jetty:jetty|6.1.26|间接依赖|maven|
|org.mortbay.jetty:jsp-api-2.1|6.1.14|间接依赖|maven|
|org.codehaus.janino:janino|3.0.11|直接依赖|maven|
|net.sf.jopt-simple:jopt-simple|4.6|间接依赖|maven|
|org.apache.curator:apache-curator|5.2.0|直接依赖|maven|
|org.eclipse.aether:aether-util|0.9.0.M2|间接依赖|maven|
|org.apache.parquet:parquet-common|1.13.1|间接依赖|maven|
|org.glassfish:javax.json|1.0.4|间接依赖|maven|
|org.powermock:powermock-core|2.0.2|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-joda|2.13.5|间接依赖|maven|
|org.apache.maven:maven-profile|2.2.1|间接依赖|maven|
|org.apache.commons:commons-pool2|2.10.0|间接依赖|maven|
|org.apache.druid:extendedset|0.17.1|间接依赖|maven|
|org.apache.kerby:kerb-common|1.0.1|间接依赖|maven|
|org.apache.accumulo:accumulo-trace|1.10.1|直接依赖|maven|
|jakarta.jms:jakarta.jms-api|2.0.2|直接依赖|maven|
|org.antlr:antlr-runtime|3.3|间接依赖|maven|
|commons-configuration:commons-configuration|1.6|间接依赖|maven|
|org.apache.hive:hive-iceberg-shading|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.apache.yetus:audience-annotations|0.13.0|间接依赖|maven|
|org.apache.maven:maven-settings|2.2.1|间接依赖|maven|
|io.grpc:grpc-stub|1.51.0|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-services-core|3.3.1|直接依赖|maven|
|org.apache.hive.hcatalog:hive-hcatalog-pig-adapter|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|net.hydromatic:aggdesigner-algorithm|6.0|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.10.1|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet-core|2.25.1|间接依赖|maven|
|org.apache.curator:curator-recipes|4.0.0|直接依赖|maven|
|org.apache.avro:avro-ipc-jetty|1.11.1|间接依赖|maven|
|org.scala-lang:scala-reflect|2.12.10|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.10.0|间接依赖|maven|
|org.apache.hbase.thirdparty:hbase-shaded-miscellaneous|1.0.1|间接依赖|maven|
|com.opencsv:opencsv|4.6|间接依赖|maven|
|org.threeten:threeten-extra|1.7.1|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.13.5|间接依赖|maven|
|org.apache.druid:druid-indexing-service|0.17.1|间接依赖|maven|
|io.netty:netty-handler|4.1.76.Final|间接依赖|maven|
|org.apache.httpcomponents.client5:httpclient5|5.2.1|间接依赖|maven|
|org.jline:jline|3.9.0|间接依赖|maven|
|com.stumbleupon:async|1.4.1|间接依赖|maven|
|jline:jline|2.14.6|直接依赖|maven|
|org.apache.hbase:hbase-prefix-tree|2.0.0-alpha4|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|3.3.1|直接依赖|maven|
|org.apache.yetus:audience-annotations|0.5.0|间接依赖|maven|
|org.apache.maven:maven-plugin-api|2.2.1|间接依赖|maven|
|org.apache.hive:hive-it-druid|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.codehaus.plexus:plexus-component-annotations|1.5.5|间接依赖|maven|
|org.apache.hive:hive-llap-server|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.apache.kerby:kerby-util|1.0.1|间接依赖|maven|
|org.apache.calcite.avatica:avatica-server|1.12.0|直接依赖|maven|
|com.esotericsoftware:kryo|5.5.0|直接依赖|maven|
|com.amazonaws.secretsmanager:aws-secretsmanager-caching-java|1.0.1|直接依赖|maven|
|org.apache.hive:hive-hplsql|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|io.netty:netty-codec-http|4.1.77.Final|间接依赖|maven|
|org.eclipse.jetty:jetty-continuation|9.4.40.v20210413|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-server|9.4.40.v20210413|间接依赖|maven|
|org.eclipse.jetty:jetty-security|9.4.40.v20210413|直接依赖|maven|
|org.apache.commons:commons-compress|1.19|间接依赖|maven|
|org.eclipse.jetty:jetty-client|9.4.12.v20180830|间接依赖|maven|
|com.amazonaws:aws-java-sdk-s3|1.11.199|间接依赖|maven|
|org.eclipse.jetty:jetty-webapp|9.4.40.v20210413|直接依赖|maven|
|org.glassfish.jersey.core:jersey-client|2.25.1|间接依赖|maven|
|org.apache.zookeeper:zookeeper-jute|3.7.1|间接依赖|maven|
|org.apache.thrift:libfb303|0.9.3|直接依赖|maven|
|classworlds:classworlds|1.1-alpha-2|间接依赖|maven|
|org.apache.hive:hive-shims|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.apache.hive.hcatalog:hive-webhcat|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.eclipse.aether:aether-spi|0.9.0.M2|间接依赖|maven|
|org.mockito:mockito-core|3.4.4|直接依赖|maven|
|org.apache.maven.shared:maven-shared-utils|0.6|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.30|直接依赖|maven|
|org.codehaus.groovy:groovy-all|2.4.21|直接依赖|maven|
|net.sf.jpam:jpam|1.1|直接依赖|maven|
|io.dropwizard.metrics:metrics-json|3.1.0|直接依赖|maven|
|org.apache.maven:maven-model-builder|3.1.1|间接依赖|maven|
|commons-httpclient:commons-httpclient|3.1|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|4.0.0|间接依赖|maven|
|org.roaringbitmap:RoaringBitmap|0.9.22|直接依赖|maven|
|org.jline:jline-terminal-jna|3.12.1|间接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|直接依赖|maven|
|org.ow2.asm:asm|8.0.1|间接依赖|maven|
|org.apache.arrow:arrow-memory-core|12.0.0|间接依赖|maven|
|org.apache.iceberg:iceberg-orc|1.3.0|直接依赖|maven|
|io.netty:netty-all|4.1.61.Final|间接依赖|maven|
|org.apache.maven.doxia:doxia-decoration-model|1.4|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-applicationhistoryservice|3.3.1|间接依赖|maven|
|com.google.flatbuffers:flatbuffers-java|1.12.0|直接依赖|maven|
|org.junit.jupiter:junit-jupiter-api|5.6.2|直接依赖|maven|
|commons-cli:commons-cli|1.5.0|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-timelineservice|3.3.1|间接依赖|maven|
|io.netty:netty-common|4.1.76.Final|间接依赖|maven|
|org.glassfish.jaxb:txw2|2.3.1|间接依赖|maven|
|org.apache.maven:maven-plugin-registry|2.2.1|间接依赖|maven|
|com.lmax:disruptor|3.3.6|间接依赖|maven|
|com.sun.jersey:jersey-client|1.19|间接依赖|maven|
|net.minidev:accessors-smart|2.4.9|间接依赖|maven|
|org.apache.ivy:ivy|2.5.1|直接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|直接依赖|maven|
|org.hibernate:hibernate-validator|5.2.5.Final|间接依赖|maven|
|org.mortbay.jetty:jsp-2.1|6.1.14|间接依赖|maven|
|org.apache.tez:tez-common|0.10.2|直接依赖|maven|
|io.airlift:aircompressor|0.24|间接依赖|maven|
|org.glassfish.hk2:hk2-api|2.5.0-b32|间接依赖|maven|
|org.apache.commons:commons-lang3|3.8.1|间接依赖|maven|
|org.datanucleus:javax.jdo|3.2.0-release|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.5|间接依赖|maven|
|org.apache.kerby:kerby-xdr|1.0.1|间接依赖|maven|
|com.oracle.database.jdbc:ojdbc8|21.3.0.0|直接依赖|maven|
|org.apache.taglibs:taglibs-standard-impl|1.2.5|间接依赖|maven|
|org.apache.hive:hive-classification|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.codehaus.plexus:plexus-i18n|1.0-beta-7|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|com.fasterxml:classmate|1.1.0|间接依赖|maven|
|org.apache.druid:druid-console|0.17.1|间接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|org.eclipse.jetty:jetty-rewrite|9.4.40.v20210413|直接依赖|maven|
|org.apache.maven:maven-model|3.1.1|间接依赖|maven|
|backport-util-concurrent:backport-util-concurrent|3.1|间接依赖|maven|
|org.apache.kerby:kerb-crypto|1.0.1|间接依赖|maven|
|io.netty:netty-codec-mqtt|4.1.77.Final|间接依赖|maven|
|org.apache.maven.doxia:doxia-site-renderer|1.4|间接依赖|maven|
|commons-pool:commons-pool|1.6|间接依赖|maven|
|org.roaringbitmap:shims|0.9.44|间接依赖|maven|
|dnsjava:dnsjava|2.1.7|间接依赖|maven|
|org.glassfish.hk2:hk2-utils|2.5.0-b32|间接依赖|maven|
|org.apache.tez:tez-api|0.10.2|直接依赖|maven|
|org.skife.config:config-magic|0.9|间接依赖|maven|
|org.eclipse.jetty:jetty-annotations|9.4.40.v20210413|间接依赖|maven|
|org.scala-lang:scala-library|2.12.10|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.13.5|间接依赖|maven|
|org.hyperic:sigar|1.6.5.132|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.3|间接依赖|maven|
|io.tesla.aether:tesla-aether|0.0.5|间接依赖|maven|
|org.apache.druid:druid-hll|0.17.1|间接依赖|maven|
|org.apache.hadoop:hadoop-aws|3.3.1|直接依赖|maven|
|org.jvnet.staxex:stax-ex|1.8|间接依赖|maven|
|io.netty:netty-codec-haproxy|4.1.77.Final|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|io.netty:netty-transport|4.1.42.Final|间接依赖|maven|
|com.google.oauth-client:google-oauth-client|1.22.0|间接依赖|maven|
|io.netty:netty-handler|4.1.77.Final|间接依赖|maven|
|org.apache.curator:curator-x-discovery|4.1.0|间接依赖|maven|
|org.yaml:snakeyaml|1.31|间接依赖|maven|
|com.sun.jersey.contribs:jersey-guice|1.19|间接依赖|maven|
|org.ow2.asm:asm-commons|9.0|间接依赖|maven|
|org.objenesis:objenesis|2.6|间接依赖|maven|
|org.apache.druid:druid-aws-common|0.17.1|间接依赖|maven|
|org.apache.parquet:parquet-format-structures|1.13.1|间接依赖|maven|
|net.sf.opencsv:opencsv|2.3|直接依赖|maven|
|com.sun.jersey:jersey-json|1.19|直接依赖|maven|
|org.apache.hadoop.thirdparty:hadoop-shaded-guava|1.1.1|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-nodemanager|3.3.1|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-common|3.3.1|直接依赖|maven|
|org.eclipse.jetty:apache-jstl|9.4.40.v20210413|间接依赖|maven|
|commons-digester:commons-digester|1.8|间接依赖|maven|
|ch.qos.reload4j:reload4j|1.2.19|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-guava|2.13.5|间接依赖|maven|
|org.apache.hbase:hbase-hadoop2-compat|2.0.0-alpha4|间接依赖|maven|
|org.apache.avro:avro-ipc|1.11.1|间接依赖|maven|
|org.apache.hbase.thirdparty:hbase-shaded-netty|1.0.1|间接依赖|maven|
|org.apache.commons:commons-vfs2|2.3|间接依赖|maven|
|commons-configuration:commons-configuration|1.10|直接依赖|maven|
|io.grpc:grpc-netty-shaded|1.51.0|直接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j-impl|2.18.0|直接依赖|maven|
|io.netty:netty-codec-socks|4.1.29.Final|间接依赖|maven|
|org.codehaus.jackson:jackson-mapper-asl|1.9.2|间接依赖|maven|
|org.apache.velocity:velocity-engine-core|2.3|间接依赖|maven|
|net.shibboleth.tool:xmlsectool|2.0.0|间接依赖|maven|
|org.apache.kerby:kerby-pkix|1.0.1|间接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.8|间接依赖|maven|
|org.ow2.asm:asm|7.1|间接依赖|maven|
|com.ning:compress-lzf|1.0.4|间接依赖|maven|
|io.netty:netty-codec-redis|4.1.77.Final|间接依赖|maven|
|com.amazonaws:aws-java-sdk-kms|1.11.199|间接依赖|maven|
|net.sf.supercsv:super-csv|2.2.0|直接依赖|maven|
|org.apache.atlas:atlas-intg|2.1.0|直接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.14|间接依赖|maven|
|org.apache.arrow:arrow-vector|12.0.0|直接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|直接依赖|maven|
|org.jline:jline-reader|3.12.1|间接依赖|maven|
|org.apache.santuario:xmlsec|2.3.0|直接依赖|maven|
|com.sun.jersey.contribs:jersey-guice|1.19.3|间接依赖|maven|
|org.apache.maven.doxia:doxia-sink-api|1.4|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.29.Final|间接依赖|maven|
|xml-apis:xml-apis|1.4.01|间接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.12.v20180830|间接依赖|maven|
|org.apache.kerby:kerb-simplekdc|1.0.1|间接依赖|maven|
|xalan:xalan|2.7.0|间接依赖|maven|
|org.apache.hadoop:hadoop-archives|3.3.1|直接依赖|maven|
|org.jruby.jcodings:jcodings|1.0.43|间接依赖|maven|
|org.apache.hive:hive-standalone-metastore-server|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|io.netty:netty-common|4.1.42.Final|间接依赖|maven|
|org.opensaml:opensaml-xmlsec-api|3.4.5|间接依赖|maven|
|com.github.stephenc.jcip:jcip-annotations|1.0-1|间接依赖|maven|
|commons-el:commons-el|1.0|间接依赖|maven|
|org.ow2.asm:asm-commons|7.1|间接依赖|maven|
|org.apache.kafka:kafka_2.12|2.5.0|直接依赖|maven|
|org.ow2.asm:asm|9.3|间接依赖|maven|
|net.java.dev.jets3t:jets3t|0.7.1|间接依赖|maven|
|org.apache.hive:hive-streaming|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.eclipse.jetty:jetty-jndi|9.4.40.v20210413|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.40.v20210413|直接依赖|maven|
|org.codehaus.plexus:plexus-interpolation|1.11|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.18.0|直接依赖|maven|
|net.sf.jopt-simple:jopt-simple|5.0.4|间接依赖|maven|
|org.apache.accumulo:accumulo-gc|1.10.1|间接依赖|maven|
|org.checkerframework:checker-qual|3.4.0|间接依赖|maven|
|org.apache.hadoop:hadoop-hdfs-client|2.8.5|间接依赖|maven|
|org.datanucleus:datanucleus-core|5.2.10|直接依赖|maven|
|org.codehaus.plexus:plexus-container-default|1.0-alpha-9-stable-1|间接依赖|maven|
|com.sun.jersey.contribs:wadl-resourcedoc-doclet|1.4|直接依赖|maven|
|org.apiguardian:apiguardian-api|1.1.0|间接依赖|maven|
|org.apache.curator:curator-client|5.2.0|直接依赖|maven|
|org.hamcrest:hamcrest|2.2|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-client|9.4.40.v20210413|间接依赖|maven|
|org.apache.parquet:parquet-encoding|1.13.1|间接依赖|maven|
|org.eclipse.jetty:jetty-proxy|9.4.40.v20210413|直接依赖|maven|
|org.apache.curator:curator-x-discovery|4.0.0|直接依赖|maven|
|com.sun.jersey.contribs:jersey-multipart|1.19|直接依赖|maven|
|org.apache.hive:hive-it-util|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|io.netty:netty-transport-udt|4.1.77.Final|间接依赖|maven|
|joda-time:joda-time|2.9.9|直接依赖|maven|
|org.apache.hive:hive-vector-code-gen|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.apache.calcite:calcite-linq4j|1.25.0|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.1|间接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.3|间接依赖|maven|
|org.apache.druid.extensions:mysql-metadata-storage|0.17.1|直接依赖|maven|
|org.eclipse.jetty.websocket:javax-websocket-client-impl|9.4.40.v20210413|间接依赖|maven|
|org.apache.druid:druid-processing|0.17.1|直接依赖|maven|
|org.springframework:spring-core|4.3.20.RELEASE|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|3.3.1|直接依赖|maven|
|org.apache.accumulo:accumulo-server-base|1.10.1|间接依赖|maven|
|org.apache.commons:commons-dbcp2|2.9.0|直接依赖|maven|
|org.apache.maven.doxia:doxia-module-fml|1.4|间接依赖|maven|
|org.scala-lang.modules:scala-java8-compat_2.12|0.9.0|间接依赖|maven|
|com.mysql:mysql-connector-j|8.0.31|直接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|间接依赖|maven|
|org.apache.accumulo:accumulo-fate|1.10.1|直接依赖|maven|
|com.amazonaws:aws-java-sdk-core|1.11.199|间接依赖|maven|
|org.apache.maven:maven-repository-metadata|3.1.1|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.77.Final|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.12|间接依赖|maven|
|net.java.dev.jna:jna|5.3.1|间接依赖|maven|
|org.apache.taglibs:taglibs-standard-spec|1.2.5|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.77.Final|间接依赖|maven|
|org.apache.hive:hive-metastore|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.apache.druid:druid-core|0.17.1|间接依赖|maven|
|org.pac4j:pac4j-core|4.5.5|直接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|2.3.1|间接依赖|maven|
|io.netty:netty-transport-sctp|4.1.77.Final|间接依赖|maven|
|com.sun.activation:javax.activation|1.2.0|间接依赖|maven|
|org.apache.hive.shims:hive-shims-common|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.4.40.v20210413|直接依赖|maven|
|com.google.code.findbugs:jsr305|1.3.9|间接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.9.2|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-jobclient|3.3.1|直接依赖|maven|
|javax.validation:validation-api|1.1.0.Final|直接依赖|maven|
|org.mortbay.jetty:jetty-util|6.1.26|间接依赖|maven|
|org.apache.commons:commons-pool2|2.11.1|直接依赖|maven|
|org.checkerframework:checker-qual|3.5.0|间接依赖|maven|
|commons-logging:commons-logging|1.1.1|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.2.1.Final|间接依赖|maven|
|org.apache.hbase:hbase-mapreduce|2.0.0-alpha4|直接依赖|maven|
|stax:stax-api|1.0.1|直接依赖|maven|
|org.apache.maven:maven-settings-builder|3.1.1|间接依赖|maven|
|org.apache.logging.log4j:log4j-1.2-api|2.18.0|直接依赖|maven|
|org.apache.hbase:hbase-hadoop-compat|2.0.0-alpha4|间接依赖|maven|
|io.tesla.aether:aether-connector-okhttp|0.0.9|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.0.18|间接依赖|maven|
|org.apache.hbase:hbase-client|2.0.0-alpha4|直接依赖|maven|
|org.apache.hbase:hbase-metrics-api|2.0.0-alpha4|间接依赖|maven|
|org.springframework:spring-aop|4.3.20.RELEASE|间接依赖|maven|
|org.apache.hive:hive-jdbc|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-web-proxy|3.3.1|间接依赖|maven|
|org.ow2.asm:asm-analysis|9.0|间接依赖|maven|
|javax.websocket:javax.websocket-api|1.0|间接依赖|maven|
|org.apache.hbase:hbase-server|2.0.0-alpha4|直接依赖|maven|
|org.apache.atlas:atlas-client-v2|2.1.0|直接依赖|maven|
|org.apache.parquet:parquet-column|1.13.1|间接依赖|maven|
|org.apache.hive.hcatalog:hive-webhcat-java-client|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.apache.kerby:kerb-util|1.0.1|间接依赖|maven|
|com.yahoo.datasketches:memory|0.9.0|间接依赖|maven|
|io.grpc:grpc-protobuf|1.51.0|直接依赖|maven|
|org.apache.hive:hive-service|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.opentest4j:opentest4j|1.2.0|间接依赖|maven|
|org.apache.calcite.avatica:avatica-core|1.12.0|直接依赖|maven|
|org.apache.avro:avro|1.7.7|间接依赖|maven|
|org.apache.hbase:hbase-protocol-shaded|2.0.0-alpha4|间接依赖|maven|
|org.slf4j:slf4j-simple|1.7.36|间接依赖|maven|
|org.apache.avro:avro-mapred|1.11.1|直接依赖|maven|
|org.apache.hadoop:hadoop-registry|3.3.1|间接依赖|maven|
|org.apache.hive:metastore-tools-common|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.5|间接依赖|maven|
|org.ow2.asm:asm-analysis|7.1|间接依赖|maven|
|org.apache.hbase:hbase-protocol|2.0.0-alpha4|间接依赖|maven|
|org.tukaani:xz|1.9|间接依赖|maven|
|com.esri.geometry:esri-geometry-api|2.2.4|直接依赖|maven|
|org.codehaus.jackson:jackson-jaxrs|1.9.2|间接依赖|maven|
|com.google.inject.extensions:guice-multibindings|4.1.0|间接依赖|maven|
|org.roaringbitmap:shims|0.8.11|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-tests|3.3.1|直接依赖|maven|
|org.powermock:powermock-api-support|2.0.2|间接依赖|maven|
|io.netty:netty|3.10.6.Final|间接依赖|maven|
|cglib:cglib|2.2.2|间接依赖|maven|
|org.codehaus.jackson:jackson-xc|1.9.2|间接依赖|maven|
|org.apache.hadoop:hadoop-auth|3.3.1|直接依赖|maven|
|org.apache.hadoop:hadoop-distcp|3.3.1|直接依赖|maven|
|org.apache.curator:curator-framework|5.2.0|直接依赖|maven|
|org.antlr:antlr4-runtime|4.9.3|直接依赖|maven|
|org.apache.hive:hive-kudu-handler|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.apache.accumulo:accumulo-tserver|1.10.1|间接依赖|maven|
|org.apache.hadoop:hadoop-hdfs|3.3.1|直接依赖|maven|
|org.apache.calcite.avatica:avatica-metrics|1.12.0|直接依赖|maven|
|org.apache.maven.reporting:maven-reporting-impl|2.3|间接依赖|maven|
|org.reflections:reflections|0.10.2|直接依赖|maven|
|org.apache.ant:ant|1.10.13|直接依赖|maven|
|io.dropwizard.metrics:metrics-core|3.1.0|直接依赖|maven|
|org.apache.kudu:kudu-test-utils|1.12.0|直接依赖|maven|
|org.apache.maven:maven-aether-provider|3.1.1|间接依赖|maven|
|org.eclipse.jetty:jetty-xml|9.4.40.v20210413|间接依赖|maven|
|com.github.joshelser:dropwizard-metrics-hadoop-metrics2-reporter|0.1.2|直接依赖|maven|
|org.apache.iceberg:iceberg-core|1.3.0|直接依赖|maven|
|org.checkerframework:checker-qual|2.10.0|间接依赖|maven|
|com.typesafe.netty:netty-reactive-streams|2.0.4|间接依赖|maven|
|org.fusesource.jansi:jansi|2.3.4|直接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.2|间接依赖|maven|
|org.schemarepo:schema-repo-common|0.1.3|间接依赖|maven|
|net.shibboleth.utilities:java-support|7.5.1|间接依赖|maven|
|com.sun.jersey:jersey-core|1.19|直接依赖|maven|
|org.apache.orc:orc-shims|1.8.3|间接依赖|maven|
|org.apache.hive:hive-udf|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|com.google.inject.extensions:guice-servlet|4.0|间接依赖|maven|
|org.codehaus.janino:commons-compiler|3.0.11|直接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.3|间接依赖|maven|
|org.eclipse.aether:aether-impl|0.9.0.M2|间接依赖|maven|
|org.apache.maven.wagon:wagon-provider-api|2.4|间接依赖|maven|
|io.netty:netty-codec-smtp|4.1.77.Final|间接依赖|maven|
|org.glassfish.hk2.external:javax.inject|2.5.0-b32|间接依赖|maven|
|org.apache.hbase:hbase-metrics|2.0.0-alpha4|间接依赖|maven|
|javax.activation:activation|1.1|间接依赖|maven|
|org.apache.kerby:kerb-admin|1.0.1|间接依赖|maven|
|com.github.stephenc.findbugs:findbugs-annotations|1.3.9-1|间接依赖|maven|
|org.apache.accumulo:accumulo-tracer|1.10.1|间接依赖|maven|
|org.apache.maven:maven-jxr|2.5|间接依赖|maven|
|org.apache.tez:hadoop-shim|0.10.2|间接依赖|maven|
|com.github.luben:zstd-jni|1.4.4-7|间接依赖|maven|
|org.apache.maven:maven-artifact|2.2.1|间接依赖|maven|
|com.cedarsoftware:java-util|1.9.0|间接依赖|maven|
|com.typesafe.netty:netty-reactive-streams|2.0.0|间接依赖|maven|
|org.jline:jline-builtins|3.12.1|间接依赖|maven|
|org.apache.parquet:parquet-hadoop-bundle|1.13.0|直接依赖|maven|
|org.apache.iceberg:iceberg-parquet|1.3.0|直接依赖|maven|
|javax.servlet:javax.servlet-api|3.1.0|直接依赖|maven|
|javolution:javolution|5.5.1|直接依赖|maven|
|org.lz4:lz4-java|1.6.0|间接依赖|maven|
|org.apache.accumulo:accumulo-core|1.10.1|直接依赖|maven|
|org.codehaus.jettison:jettison|1.1|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.13.5|间接依赖|maven|
|io.jsonwebtoken:jjwt-jackson|0.10.5|直接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|直接依赖|maven|
|org.apache.druid:druid-indexing-hadoop|0.17.1|间接依赖|maven|
|it.unimi.dsi:fastutil|8.2.3|间接依赖|maven|
|com.yahoo.datasketches:sketches-core|0.9.0|间接依赖|maven|
|org.apache.maven:maven-artifact-manager|2.2.1|间接依赖|maven|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13|间接依赖|maven|
|xmlenc:xmlenc|0.52|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.0|直接依赖|maven|
|io.netty:netty-buffer|4.1.42.Final|间接依赖|maven|
|com.squareup.okhttp:okhttp|2.7.5|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.2|间接依赖|maven|
|org.apache.hive:hive-service-rpc|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|io.netty:netty-codec|4.1.77.Final|间接依赖|maven|
|org.apache.hbase:hbase-http|2.0.0-alpha4|间接依赖|maven|
|org.ow2.asm:asm|9.0|间接依赖|maven|
|org.apache.arrow:arrow-format|12.0.0|间接依赖|maven|
|org.schemarepo:schema-repo-avro|0.1.3|间接依赖|maven|
|org.apache.hive:hive-druid-handler|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|io.netty:netty-resolver|4.1.29.Final|间接依赖|maven|
|commons-lang:commons-lang|2.6|间接依赖|maven|
|org.apache.kerby:kerby-config|1.0.1|间接依赖|maven|
|org.apache.tez:tez-dag|0.10.2|直接依赖|maven|
|org.apache.maven:maven-model|2.2.1|间接依赖|maven|
|org.pac4j:pac4j-saml-opensamlv3|4.5.5|直接依赖|maven|
|com.tdunning:json|1.8|直接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|org.apache.kafka:kafka-clients|2.5.0|直接依赖|maven|
|commons-io:commons-io|2.12.0|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-guice|2.13.5|间接依赖|maven|
|org.apache.hive.hive-it-custom-udfs:udf-classloader-util|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|9.31|直接依赖|maven|
|org.apache.hadoop:hadoop-hdfs-client|2.10.2|间接依赖|maven|
|org.apache.druid:druid-sql|0.17.1|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-smile|2.13.5|直接依赖|maven|
|org.mockito:mockito-inline|3.4.4|直接依赖|maven|
|antlr:antlr|2.7.7|间接依赖|maven|
|io.perfmark:perfmark-api|0.25.0|间接依赖|maven|
|org.hamcrest:hamcrest-core|1.3|间接依赖|maven|
|org.apache.hive:hive-llap-ext-client|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|commons-io:commons-io|2.8.0|间接依赖|maven|
|org.slf4j:slf4j-reload4j|1.7.36|间接依赖|maven|
|org.apache.parquet:parquet-jackson|1.13.1|间接依赖|maven|
|xerces:xercesImpl|2.9.1|间接依赖|maven|
|org.springframework:spring-context|4.3.20.RELEASE|间接依赖|maven|
|com.jcraft:jsch|0.1.55|间接依赖|maven|
|org.apache.hive:hive-iceberg-catalog|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.apache.hadoop.thirdparty:hadoop-shaded-protobuf_3_7|1.1.1|间接依赖|maven|
|org.gridkit.lab:jvm-attach-api|1.5|间接依赖|maven|
|org.powermock:powermock-reflect|2.0.2|间接依赖|maven|
|org.apache.hive:hive-iceberg-handler|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.77.Final|间接依赖|maven|
|org.apache.curator:curator-client|4.0.0|直接依赖|maven|
|io.netty:netty-handler-proxy|4.1.29.Final|间接依赖|maven|
|org.apache.hive:hive-common|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.apache.hive.hcatalog:hive-hcatalog-core|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-core|3.3.1|直接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.77.Final|间接依赖|maven|
|com.google.code.findbugs:jsr305|2.0.1|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-common|3.3.1|间接依赖|maven|
|net.thisptr:jackson-jq|0.0.10|间接依赖|maven|
|org.ldaptive:ldaptive|1.0.13|间接依赖|maven|
|org.apache.hbase:hbase-common|2.0.0-alpha4|直接依赖|maven|
|io.swagger:swagger-annotations|1.5.4|间接依赖|maven|
|org.asynchttpclient:async-http-client|2.5.3|间接依赖|maven|
|org.jodd:jodd-util|6.0.0|直接依赖|maven|
|org.apache.parquet:parquet-hadoop|1.13.1|间接依赖|maven|
|javax.ws.rs:jsr311-api|1.1.1|间接依赖|maven|
|xml-apis:xml-apis|1.0.b2|间接依赖|maven|
|org.apache.hive:hive-standalone-metastore-common|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.apache.maven.reporting:maven-reporting-api|3.0|间接依赖|maven|
|org.jetbrains:annotations|17.0.0|间接依赖|maven|
|org.apache.hive:hive-serde|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.apache.datasketches:datasketches-memory|1.2.0-incubating|间接依赖|maven|
|org.apache.commons:commons-math3|3.1.1|间接依赖|maven|
|com.amazonaws:jmespath-java|1.11.199|间接依赖|maven|
|org.powermock:powermock-module-junit4-common|2.0.2|间接依赖|maven|
|io.jsonwebtoken:jjwt-api|0.10.5|直接依赖|maven|
|org.apache.accumulo:accumulo-monitor|1.10.1|间接依赖|maven|
|org.apache.accumulo:accumulo-minicluster|1.10.1|直接依赖|maven|
|org.opensaml:opensaml-saml-impl|3.4.5|间接依赖|maven|
|org.apache.calcite.avatica:avatica|1.12.0|直接依赖|maven|
|org.apache.commons:commons-collections4|4.1|直接依赖|maven|
|com.google.http-client:google-http-client|1.22.0|间接依赖|maven|
|org.apache.derby:derby|10.14.2.0|直接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|org.apache.commons:commons-math3|3.6.1|直接依赖|maven|
|org.opensaml:opensaml-soap-api|3.4.5|间接依赖|maven|
|org.apache.orc:orc-core|1.8.3|直接依赖|maven|
|org.apache.druid:druid-gcp-common|0.17.1|间接依赖|maven|
|org.apache.logging.log4j:log4j-jul|2.8.2|间接依赖|maven|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|org.codehaus.plexus:plexus-interpolation|1.19|间接依赖|maven|
|com.google.guava:guava|22.0|直接依赖|maven|
|org.apache.hive:hive-accumulo-handler|4.0.0-beta-2-SNAPSHOT|直接依赖|maven|
|org.scala-lang.modules:scala-collection-compat_2.12|2.1.3|间接依赖|maven|
|org.glassfish.jersey.media:jersey-media-jaxb|2.25.1|间接依赖|maven|
|org.apache.commons:commons-exec|1.1|直接依赖|maven|
|com.yammer.metrics:metrics-core|2.2.0|间接依赖|maven|
|org.powermock:powermock-api-mockito2|2.0.2|直接依赖|maven|
|software.amazon.ion:ion-java|1.0.2|间接依赖|maven|
|junit:junit|4.13.2|直接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.9.3|间接依赖|maven|
|com.ibm.icu:icu4j|55.1|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)