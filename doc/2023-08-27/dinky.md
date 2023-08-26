# DataLinkDC/dinky安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695572814118416384.svg)](https://www.murphysec.com/console/report/1695496478650097664/1695572814118416384)

仓库描述：Dinky is an out of the box one-stop real-time computing platform dedicated to the construction and practice of Unified  Streaming & Batch and Unified Data Lake & Data Warehouse. Based on Apache Flink, Dinky provides the ability to connect many big data frameworks including OLAP and Data Lake.

仓库地址：[https://github.com/DataLinkDC/dinky](https://github.com/DataLinkDC/dinky)

| star：2340 | watch：35 | fork：842 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-25 15:57:30 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-27 07:15:29 | 组件总数：798 | 漏洞总数：100 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache HttpClient 中间人攻击漏洞|对宿主不匹配的证书验证不恰当|[MPS-2014-4112](https://www.oscs1024.com/hd/MPS-2014-4112)|CVE-2014-3577|中危|
|Apache HttpClient 中间人攻击漏洞|输入验证不恰当|[MPS-2014-4288](https://www.oscs1024.com/hd/MPS-2014-4288)|CVE-2012-6153|中危|
|Google protobuf 缓冲区错误漏洞|越界写入|[MPS-2017-10841](https://www.oscs1024.com/hd/MPS-2017-10841)|CVE-2015-5237|高危|
|Apache Zookeeper 安全漏洞||[MPS-2017-11297](https://www.oscs1024.com/hd/MPS-2017-11297)|CVE-2017-5637|高危|
|Netty和Play Framework 输入验证错误漏洞|未授权敏感信息泄露|[MPS-2017-11682](https://www.oscs1024.com/hd/MPS-2017-11682)|CVE-2015-2156|高危|
|Apache Tomcat SecurityManager绕过漏洞|访问控制不当|[MPS-2017-9011](https://www.oscs1024.com/hd/MPS-2017-9011)|CVE-2016-5018|严重|
|Apache Tomcat 访问限制绕过漏洞|访问控制不当|[MPS-2017-9027](https://www.oscs1024.com/hd/MPS-2017-9027)|CVE-2016-6796|高危|
|Apache Hadoop 信息泄漏漏洞|未授权敏感信息泄露|[MPS-2018-0896](https://www.oscs1024.com/hd/MPS-2018-0896)|CVE-2017-15713|中危|
|Apache Commons Compress 存在拒绝服务漏洞|不可达退出条件的循环（无限循环）|[MPS-2018-11233](https://www.oscs1024.com/hd/MPS-2018-11233)|CVE-2018-11771|中危|
|Apache Hadoop 路径遍历漏洞|路径遍历|[MPS-2018-14698](https://www.oscs1024.com/hd/MPS-2018-14698)|CVE-2018-8009|高危|
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|Apache Zookeeper 访问控制错误漏洞|授权检查缺失|[MPS-2018-6313](https://www.oscs1024.com/hd/MPS-2018-6313)|CVE-2018-8012|高危|
|Apache Commons Beanutils 存在不可信数据的反序列化漏洞|反序列化|[MPS-2019-10233](https://www.oscs1024.com/hd/MPS-2019-10233)|CVE-2019-10086|高危|
|Netty 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2019-12064](https://www.oscs1024.com/hd/MPS-2019-12064)|CVE-2019-16869|高危|
|Red Hat JBoss Enterprise Application Platform 代码问题漏洞|反序列化|[MPS-2019-12470](https://www.oscs1024.com/hd/MPS-2019-12470)|CVE-2019-10202|严重|
|jackson-mapper-asl <=1.9.13 XXE 注入漏洞|XXE|[MPS-2019-15048](https://www.oscs1024.com/hd/MPS-2019-15048)|CVE-2019-10172|高危|
|Apache Log4j SocketServer反序列化漏洞|反序列化|[MPS-2019-17271](https://www.oscs1024.com/hd/MPS-2019-17271)|CVE-2019-17571|严重|
|Apache Zookeeper 授权问题漏洞|授权检查缺失|[MPS-2019-5668](https://www.oscs1024.com/hd/MPS-2019-5668)|CVE-2019-0201|中危|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|Netty <=4.1.43.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1320](https://www.oscs1024.com/hd/MPS-2020-1320)|CVE-2020-7238|高危|
|Junit 信息泄露漏洞|不安全的临时文件|[MPS-2020-15183](https://www.oscs1024.com/hd/MPS-2020-15183)|CVE-2020-15250|中危|
|Netty <4.1.44.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1526](https://www.oscs1024.com/hd/MPS-2020-1526)|CVE-2019-20444|严重|
|Netty <4.1.44.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1527](https://www.oscs1024.com/hd/MPS-2020-1527)|CVE-2019-20445|严重|
|Apache HttpClient URI解析错误漏洞|XSS|[MPS-2020-17341](https://www.oscs1024.com/hd/MPS-2020-17341)|CVE-2020-13956|中危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Apache Log4j2 SmtpAppender证书验证不当漏洞|证书验证不恰当|[MPS-2020-6684](https://www.oscs1024.com/hd/MPS-2020-6684)|CVE-2020-9488|低危|
|Apache Commons Compress 安存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10550](https://www.oscs1024.com/hd/MPS-2021-10550)|CVE-2021-35517|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10551](https://www.oscs1024.com/hd/MPS-2021-10551)|CVE-2021-35516|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10564](https://www.oscs1024.com/hd/MPS-2021-10564)|CVE-2021-36090|高危|
|Apache Commons Compress 无限循环漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-10565](https://www.oscs1024.com/hd/MPS-2021-10565)|CVE-2021-35515|高危|
|Eclipse Jetty 编码字符敏感信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-10800](https://www.oscs1024.com/hd/MPS-2021-10800)|CVE-2021-34429|中危|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|Apache Commons Net <3.9.0 存在FTP跳转攻击漏洞|未授权敏感信息泄露|[MPS-2021-28440](https://www.oscs1024.com/hd/MPS-2021-28440)|CVE-2021-37533|中危|
|Apache Kafka 存在时序攻击漏洞|通过差异性导致的信息暴露|[MPS-2021-28892](https://www.oscs1024.com/hd/MPS-2021-28892)|CVE-2021-38153|中危|
|Apache Parquet 输入验证错误漏洞|拒绝服务|[MPS-2021-32354](https://www.oscs1024.com/hd/MPS-2021-32354)|CVE-2021-41561|高危|
|Oracle MySQL 的 MySQL Connectors 存在授权不当漏洞|授权机制不恰当|[MPS-2021-36587](https://www.oscs1024.com/hd/MPS-2021-36587)|CVE-2022-21363|中危|
|Apache Log4j JMSAppender反序列化漏洞||[MPS-2021-38359](https://www.oscs1024.com/hd/MPS-2021-38359)|CVE-2021-4104|高危|
|Eclipse Jetty 资源管理错误漏洞|对异常条件的处理不恰当|[MPS-2021-3864](https://www.oscs1024.com/hd/MPS-2021-3864)|CVE-2021-28165|高危|
|Eclipse Jetty <9.4.39.v20210325 权限绕过漏洞|授权检查错误|[MPS-2021-3877](https://www.oscs1024.com/hd/MPS-2021-3877)|CVE-2021-28164|中危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|Eclipse Jersey 本地信息泄露漏洞|将资源暴露给错误范围|[MPS-2021-5218](https://www.oscs1024.com/hd/MPS-2021-5218)|CVE-2021-28168|中危|
|Eclipse Jetty 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-55442](https://www.oscs1024.com/hd/MPS-2021-55442)|CVE-2021-34429|中危|
|Eclipse Jetty 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-8397](https://www.oscs1024.com/hd/MPS-2021-8397)|CVE-2021-28169|中危|
|Eclipse Jetty 存在信息泄露漏洞|不充分的会话过期机制|[MPS-2021-8884](https://www.oscs1024.com/hd/MPS-2021-8884)|CVE-2021-34428|低危|
|Fastjson < 1.2.83 任意代码执行漏洞|反序列化|[MPS-2022-11320](https://www.oscs1024.com/hd/MPS-2022-11320)|CVE-2022-25845|高危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|com.beust:jcommander 存在从非可信控制范围包含功能例程漏洞||[MPS-2022-12225](https://www.oscs1024.com/hd/MPS-2022-12225)||中危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|Apache HttpClient URI解析错误漏洞|相对路径遍历|[MPS-2022-12292](https://www.oscs1024.com/hd/MPS-2022-12292)||中危|
|FasterXML Jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2022-12500](https://www.oscs1024.com/hd/MPS-2022-12500)||中危|
|io.springfox:springfox-swagger2 存在输入验证不恰当漏洞|日志敏感信息泄露|[MPS-2022-12534](https://www.oscs1024.com/hd/MPS-2022-12534)||中危|
|Apache Log4j JDBCAppender SQL注入漏洞|SQL注入|[MPS-2022-1444](https://www.oscs1024.com/hd/MPS-2022-1444)|CVE-2022-23305|严重|
|Apache Log4j Chainsaw反序列化漏洞|反序列化|[MPS-2022-1445](https://www.oscs1024.com/hd/MPS-2022-1445)|CVE-2022-23307|高危|
|Apache Log4j 反序列化漏洞|反序列化|[MPS-2022-1446](https://www.oscs1024.com/hd/MPS-2022-1446)|CVE-2022-23302|高危|
|Eclipse Jetty URI注入漏洞|注入|[MPS-2022-18060](https://www.oscs1024.com/hd/MPS-2022-18060)|CVE-2022-2047|低危|
|Apache Hadoop 存在shell命令注入漏洞|参数注入或修改|[MPS-2022-4190](https://www.oscs1024.com/hd/MPS-2022-4190)|CVE-2022-25168|严重|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|Apache Calcite Avatica 代码注入漏洞|代码注入|[MPS-2022-51965](https://www.oscs1024.com/hd/MPS-2022-51965)|CVE-2022-36364|高危|
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
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|Apache Hadoop 存在路径遍历漏洞|路径遍历|[MPS-2022-5920](https://www.oscs1024.com/hd/MPS-2022-5920)|CVE-2022-26612|严重|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|Jettison <1.5.2 拒绝服务漏洞|越界写入|[MPS-2022-64973](https://www.oscs1024.com/hd/MPS-2022-64973)|CVE-2022-45685|高危|
|H2 数据库明文密码问题|未授权敏感信息泄露|[MPS-2022-65204](https://www.oscs1024.com/hd/MPS-2022-65204)|CVE-2022-45868|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|hutool 表达式注入漏洞|SQL注入|[MPS-2023-2459](https://www.oscs1024.com/hd/MPS-2023-2459)|CVE-2023-24163|严重|
|hutool 存在反序列化漏洞|反序列化|[MPS-2023-2460](https://www.oscs1024.com/hd/MPS-2023-2460)|CVE-2023-24162|高危|
|Apache Kafka Connect 模块JNDI注入漏洞|反序列化|[MPS-2023-3834](https://www.oscs1024.com/hd/MPS-2023-3834)|CVE-2023-25194|高危|
|【存在争议】MybatisPlus <= 3.5.3.1 TenantPlugin 组件 存在 sql 注入漏洞|SQL注入|[MPS-2023-3977](https://www.oscs1024.com/hd/MPS-2023-3977)|CVE-2023-25330|高危|
|Eclipse Jetty 资源管理错误漏洞|拒绝服务|[MPS-2023-4997](https://www.oscs1024.com/hd/MPS-2023-4997)|CVE-2023-26048|中危|
|Eclipse Jetty 信息泄露漏洞|XSS|[MPS-2023-4998](https://www.oscs1024.com/hd/MPS-2023-4998)|CVE-2023-26049|中危|
|java-xmlbuilder 代码问题漏洞|XXE|[MPS-2023-5040](https://www.oscs1024.com/hd/MPS-2023-5040)|CVE-2014-125087|严重|
|netplex json-smart 安全漏洞|未经控制的递归|[MPS-2023-7760](https://www.oscs1024.com/hd/MPS-2023-7760)|CVE-2023-1370|高危|
|Jettison 安全漏洞|未经控制的递归|[MPS-2023-8270](https://www.oscs1024.com/hd/MPS-2023-8270)|CVE-2023-1436|高危|
|jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2023-8438](https://www.oscs1024.com/hd/MPS-2023-8438)|CVE-2021-46877|中危|
|Hutool createTempFile函数敏感信息泄漏漏洞|未授权敏感信息泄露|[MPS-4soz-eyma](https://www.oscs1024.com/hd/MPS-4soz-eyma)|CVE-2023-33695|中危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|hutool <=5.8.17 存在SPEL命令执行风险|代码注入|[MPS-jdrq-1ywv](https://www.oscs1024.com/hd/MPS-jdrq-1ywv)||高危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|Apache Tomcat 安全漏洞||[MPS-xd4z-oncg](https://www.oscs1024.com/hd/MPS-xd4z-oncg)|CVE-2023-34981|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.apache.zookeeper:zookeeper|3.4.6|3.5.5|间接依赖|强烈建议修复|C:0|H:2|M:1|L:0|
|cn.hutool:hutool-all|5.8.11|5.8.19|直接依赖|强烈建议修复|C:1|H:2|M:1|L:0|
|org.apache.kafka:kafka-clients|3.2.3|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.baomidou:mybatis-plus-extension|3.5.3.1||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.kafka:kafka-clients|2.8.1|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-webapp|9.4.43.v20210629|11.0.6|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.xerial.snappy:snappy-java|1.1.7.3|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.14.1||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.11.0|2.14.0-rc1|间接依赖|建议修复|C:0|H:1|M:5|L:0|
|log4j:log4j|1.2.17||间接依赖|建议修复|C:2|H:3|M:0|L:1|
|com.jamesmurty.utils:java-xmlbuilder|0.4|1.2|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.google.protobuf:protobuf-java|2.5.0|3.21.7|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|org.apache.commons:commons-compress|1.20|1.21|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|org.yaml:snakeyaml|1.30|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|org.codehaus.jettison:jettison|1.1|1.5.4|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|org.apache.hadoop:hadoop-common|3.3.2|3.3.3|直接依赖|建议修复|C:2|H:0|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.5|2.14.0-rc1|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.xerial.snappy:snappy-java|1.1.8.4|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|com.squareup.okio:okio|1.6.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.7.11|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.xerial.snappy:snappy-java|1.1.8.1|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.xerial.snappy:snappy-java|1.0.4.1|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|cn.hutool:hutool-all|5.8.18|5.8.19|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|tomcat:jasper-runtime|5.5.23||间接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.1|2.14.0-rc1|间接依赖|建议修复|C:0|H:1|M:3|L:0|
|org.yaml:snakeyaml|1.33|2.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.28|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|com.squareup.okio:okio|1.15.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.calcite.avatica:avatica-core|1.17.0|1.22.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.xerial.snappy:snappy-java|1.1.8.2|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.eclipse.jetty:jetty-io|9.4.38.v20210224|11.0.10|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.hadoop:hadoop-common|2.7.5|3.3.3|间接依赖|建议修复|C:2|H:1|M:1|L:0|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.74|11.0.0-m6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.google.protobuf:protobuf-java|3.11.4|3.21.7|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|io.netty:netty|3.6.2.Final|3.10.3.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|org.eclipse.jetty:jetty-server|9.4.43.v20210629|12.0.0.beta0|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.eclipse.jetty:jetty-http|9.4.43.v20210629|11.0.10|间接依赖|建议修复|C:0|H:0|M:1|L:1|
|org.eclipse.jetty:jetty-http|9.4.38.v20210224|11.0.10|间接依赖|建议修复|C:0|H:0|M:1|L:1|
|org.springframework.boot:spring-boot-autoconfigure|1.5.12.RELEASE|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.0|2.14.0-rc1|间接依赖|建议修复|C:0|H:1|M:4|L:0|
|commons-beanutils:commons-beanutils|1.7.0|1.9.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-web|5.3.27|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.eclipse.jetty:jetty-server|9.4.38.v20210224|12.0.0.beta0|间接依赖|建议修复|C:0|H:0|M:3|L:1|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13||间接依赖|建议修复|C:1|H:1|M:0|L:0|
|com.fasterxml.woodstox:woodstox-core|5.3.0|6.4.0|间接依赖|建议修复|C:0|H:3|M:0|L:1|
|tomcat:jasper-compiler|5.5.23||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.xerial.snappy:snappy-java|1.1.8.3|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.codehaus.jackson:jackson-mapper-asl|1.9.2||间接依赖|建议修复|C:1|H:1|M:0|L:0|
|net.minidev:json-smart|2.4.7|2.4.9|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.kafka:kafka-clients|2.4.1|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-all|4.0.23.Final|4.1.44.Final|间接依赖|建议修复|C:2|H:3|M:0|L:0|
|org.apache.parquet:parquet-format-structures|1.11.1|1.12.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.squareup.okio:okio|1.17.2|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.alibaba:fastjson|1.2.69|1.2.83|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty|3.10.6.Final||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.82.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.apache.httpcomponents:httpclient|4.0.1|4.5.13|间接依赖|可选修复|C:0|H:0|M:4|L:0|
|org.apache.commons:commons-compress|1.4.1|1.21|间接依赖|可选修复|C:0|H:2|M:1|L:0|
|commons-codec:commons-codec|1.4|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|com.google.code.gson:gson|2.2.4|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|commons-codec:commons-codec|1.11|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.apache.httpcomponents:httpclient|4.4.1|4.5.13|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.bouncycastle:bcprov-jdk15on|1.69||直接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.springfox:springfox-swagger2|2.10.5||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|27.0-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:1|
|junit:junit|4.12|4.13.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|19.0|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|com.google.guava:guava|11.0.2|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|commons-codec:commons-codec|1.7|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|commons-httpclient:commons-httpclient|3.1||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.glassfish.jersey.core:jersey-common|2.31|3.0.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-net:commons-net|3.6|3.9.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.h2database:h2|2.1.210||间接依赖|可选修复|C:0|H:1|M:0|L:0|
|commons-net:commons-net|3.1|3.9.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.kafka:connect-runtime|2.7.1|2.8.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|31.1-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-io:commons-io|2.4|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.beust:jcommander|1.72|1.75|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.eclipse.jetty:jetty-servlets|9.4.38.v20210224|11.0.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|13.0.1|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|mysql:mysql-connector-java|8.0.27|8.0.28|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|LGPL-2.1|8|Medium|
|Apache-2.0|621|Low|
|MIT|22|Low|
|自定义许可证|73|Low|
|EPL-2.0|17|Low|
|BSD-3-Clause|9|Low|
|EPL-1.0|5|Low|
|WTFPL|2|Low|
|CDDL-1.1|16|Low|
|LGPL-2.1-or-later|3|Low|
|MPL-2.0|2|Low|
|GPL-2.0|1|Medium|
|MPL-1.1|2|Low|
|CDDL-1.0|4|Low|
|BSD-2-Clause|5|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.codehaus.jackson:jackson-xc|1.9.2|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.17|间接依赖|maven|
|org.apache.curator:curator-client|4.2.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j-impl|2.17.2|间接依赖|maven|
|com.squareup.okhttp:okhttp|2.7.5|间接依赖|maven|
|com.jcraft:jzlib|1.1.1|间接依赖|maven|
|org.mybatis:mybatis-spring|2.0.7|间接依赖|maven|
|org.eclipse.jgit:org.eclipse.jgit.archive|5.13.1.202206130422-r|直接依赖|maven|
|org.apache.commons:commons-email|1.5|直接依赖|maven|
|org.apache.flink:flink-shaded-asm-9|9.3-16.1|间接依赖|maven|
|org.codehaus.jackson:jackson-xc|1.8.3|间接依赖|maven|
|com.baomidou:mybatis-plus-boot-starter|3.5.3.1|直接依赖|maven|
|org.apache.flink:flink-table-api-scala-bridge_2.12|1.13.6|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-client|3.3.2|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.14.1|间接依赖|maven|
|org.dromara.sms4j:sms4j-spring-boot-starter|2.1.0|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.13.0|间接依赖|maven|
|org.glassfish.hk2.external:jakarta.inject|2.6.1|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.5|间接依赖|maven|
|org.apache.flink:flink-shaded-jackson|2.13.4-16.1|间接依赖|maven|
|org.scala-lang:scala-library|2.12.7|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.82.Final|间接依赖|maven|
|com.jdcloud.sdk:core|1.2.3|间接依赖|maven|
|io.fabric8:kubernetes-model-certificates|5.12.4|间接依赖|maven|
|org.scala-lang.modules:scala-xml_2.12|1.0.6|间接依赖|maven|
|org.apache.commons:commons-math|2.2|间接依赖|maven|
|org.eclipse.jetty:jetty-client|9.4.38.v20210224|间接依赖|maven|
|io.fabric8:zjsonpatch|0.3.0|间接依赖|maven|
|org.apache.hadoop:hadoop-auth|3.3.2|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.28|直接依赖|maven|
|com.ververica:flink-sql-connector-oracle-cdc|2.3.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.5|间接依赖|maven|
|commons-httpclient:commons-httpclient|3.1|间接依赖|maven|
|org.apache.flink:flink-shaded-guava|30.1.1-jre-14.0|直接依赖|maven|
|org.mortbay.jetty:jetty-sslengine|6.1.26|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.11.0|间接依赖|maven|
|org.dinky:dinky-flink-1.16|1.0.0-SNAPSHOT|直接依赖|maven|
|org.apache.flink:flink-annotations|1.14.6|间接依赖|maven|
|org.mortbay.jetty:jetty|6.1.26|间接依赖|maven|
|org.apache.kerby:kerb-server|1.0.1|间接依赖|maven|
|io.prometheus:simpleclient_tracer_otel|0.15.0|间接依赖|maven|
|org.springframework.boot:spring-boot|2.7.11|间接依赖|maven|
|com.google.re2j:re2j|1.1|间接依赖|maven|
|org.apache.tephra:tephra-hbase-compat-1.4|0.14.0-incubating|间接依赖|maven|
|cn.hutool:hutool-all|5.8.11|直接依赖|maven|
|org.apache.xmlbeans:xmlbeans|5.1.1|间接依赖|maven|
|org.apache.pulsar:pulsar-client|2.10.2|直接依赖|maven|
|javax.validation:validation-api|1.1.0.Final|间接依赖|maven|
|org.apache.flink:flink-kubernetes_2.12|1.13.6|直接依赖|maven|
|org.apache.kafka:kafka-clients|3.2.3|间接依赖|maven|
|org.apache.parquet:parquet-column|1.11.1|间接依赖|maven|
|org.apache.hive:hive-storage-api|2.6.0|间接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.69|直接依赖|maven|
|org.springframework:spring-core|5.3.27|间接依赖|maven|
|org.jline:jline|3.9.0|间接依赖|maven|
|org.mortbay.jetty:jsp-api-2.1|6.1.14|间接依赖|maven|
|org.apache.flink:flink-table-api-java|1.17.0|间接依赖|maven|
|org.apache.flink:flink-java|1.17.0|间接依赖|maven|
|org.apache.flink:flink-python_2.12|1.13.6|直接依赖|maven|
|org.lz4:lz4-java|1.8.0|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.3|间接依赖|maven|
|org.apache.hbase:hbase-server|1.2.3|间接依赖|maven|
|org.springframework:spring-oxm|5.3.27|间接依赖|maven|
|org.springframework:spring-web|5.3.27|间接依赖|maven|
|cn.hutool:hutool-core|5.8.20|间接依赖|maven|
|com.fasterxml:classmate|1.4.0|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|2.7.3|间接依赖|maven|
|org.apache.flink:flink-file-sink-common|1.17.0|间接依赖|maven|
|org.apache.flink:flink-annotations|1.15.2|间接依赖|maven|
|org.reflections:reflections|0.10.2|直接依赖|maven|
|org.apache.httpcomponents:httpmime|4.5.13|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|2.7.5|间接依赖|maven|
|org.lz4:lz4-java|1.7.1|间接依赖|maven|
|com.github.docker-java:docker-java-transport|3.2.14|间接依赖|maven|
|com.esotericsoftware.kryo:kryo|2.24.0|间接依赖|maven|
|org.dinky:dinky-client-1.13|1.0.0-SNAPSHOT|直接依赖|maven|
|org.objenesis:objenesis|2.1|间接依赖|maven|
|org.apache.commons:commons-compress|1.21|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.7.12|间接依赖|maven|
|org.apache.flink:flink-table-planner_2.12|1.17.0|直接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|com.starrocks:flink-connector-starrocks|1.2.3_flink-1.13_2.12|直接依赖|maven|
|org.apache.kerby:kerb-common|1.0.1|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|2.7.5|间接依赖|maven|
|com.ververica:flink-connector-mysql-cdc|2.3.0|直接依赖|maven|
|com.github.docker-java:docker-java-api|3.2.14|间接依赖|maven|
|org.apache.hadoop:hadoop-common|3.3.2|直接依赖|maven|
|cn.hutool:hutool-json|5.8.20|间接依赖|maven|
|org.apache.flink:flink-connector-kafka_2.11|1.13.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.6.7|间接依赖|maven|
|org.dinky:dinky-executor|1.0.0-SNAPSHOT|直接依赖|maven|
|io.debezium:debezium-ddl-parser|1.6.4.Final|间接依赖|maven|
|org.apache.commons:commons-math3|3.5|间接依赖|maven|
|org.dinky:dinky-app-base|1.0.0-SNAPSHOT|直接依赖|maven|
|org.apache.flink:flink-table-api-scala_2.12|1.13.6|间接依赖|maven|
|org.apache.flink:flink-runtime-web_2.12|1.13.6|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.5|间接依赖|maven|
|com.google.code.gson:gson|2.8.9|间接依赖|maven|
|com.dtflys.forest:forest-core|1.5.30|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|直接依赖|maven|
|org.apache.flink:flink-shaded-force-shading|15.0|间接依赖|maven|
|io.fabric8:kubernetes-model-rbac|5.12.4|间接依赖|maven|
|com.twitter:bijection-avro_2.11|0.9.7|间接依赖|maven|
|org.apache.hudi:hudi-common|0.10.1|间接依赖|maven|
|com.esotericsoftware.minlog:minlog|1.2|间接依赖|maven|
|io.fabric8:kubernetes-model-apiextensions|5.12.4|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.30|间接依赖|maven|
|com.amazonaws:jmespath-java|1.12.481|间接依赖|maven|
|org.apache.flink:flink-optimizer_2.11|1.13.1|间接依赖|maven|
|org.tukaani:xz|1.0|间接依赖|maven|
|javax.activation:activation|1.1|间接依赖|maven|
|org.springframework.data:spring-data-keyvalue|2.7.11|间接依赖|maven|
|org.slf4j:slf4j-api|1.6.1|间接依赖|maven|
|org.springframework.ldap:spring-ldap-core|3.1.0|间接依赖|maven|
|cn.dev33:sa-token-jwt|1.35.0.RC|直接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|io.prometheus:simpleclient_common|0.15.0|间接依赖|maven|
|org.apache.flink:flink-streaming-scala_2.12|1.17.0|间接依赖|maven|
|org.apache.flink:flink-streaming-scala_2.12|1.16.0|间接依赖|maven|
|org.apache.kerby:token-provider|1.0.1|间接依赖|maven|
|org.apache.avro:avro|1.10.0|间接依赖|maven|
|org.apache.pulsar:pulsar-client-all|2.9.1|间接依赖|maven|
|commons-pool:commons-pool|1.6|间接依赖|maven|
|org.eclipse.jetty:jetty-util-ajax|9.4.43.v20210629|间接依赖|maven|
|commons-cli:commons-cli|1.3.1|直接依赖|maven|
|org.apache.commons:commons-collections4|4.4|间接依赖|maven|
|commons-digester:commons-digester|1.8|间接依赖|maven|
|io.debezium:debezium-connector-mysql|1.6.4.Final|间接依赖|maven|
|io.fabric8:kubernetes-model-coordination|5.12.4|间接依赖|maven|
|org.apache.flink:flink-shaded-guava|30.1.1-jre-15.0|直接依赖|maven|
|org.apache.commons:commons-lang3|3.4|直接依赖|maven|
|org.scala-lang:scala-reflect|2.12.7|间接依赖|maven|
|com.squareup.okhttp3:okhttp|3.12.12|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|间接依赖|maven|
|org.apache.flink:flink-table-api-bridge-base|1.17.0|间接依赖|maven|
|org.apache.flink:flink-shaded-jackson|2.12.1-13.0|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|2.7.5|间接依赖|maven|
|com.sun.xml.bind:jaxb-impl|2.3.0|直接依赖|maven|
|org.hamcrest:hamcrest-core|1.3|间接依赖|maven|
|com.oracle.database.xml:xmlparserv2|19.3.0.0|间接依赖|maven|
|io.netty:netty-resolver|4.1.82.Final|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.0.1|间接依赖|maven|
|org.apache.httpcomponents:fluent-hc|4.4.1|间接依赖|maven|
|org.apache.flink:flink-python_2.12|1.15.2|直接依赖|maven|
|org.apache.flink:flink-table-api-bridge-base|1.15.2|间接依赖|maven|
|com.sun.jersey:jersey-client|1.19|间接依赖|maven|
|org.eclipse.jetty:jetty-webapp|9.4.43.v20210629|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.11|直接依赖|maven|
|org.apache.curator:curator-client|2.7.1|间接依赖|maven|
|org.apache.curator:curator-recipes|2.7.1|间接依赖|maven|
|org.apache.flink:flink-table-runtime_2.12|1.14.6|直接依赖|maven|
|commons-net:commons-net|3.6|间接依赖|maven|
|commons-cli:commons-cli|1.2|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.3|间接依赖|maven|
|org.apache.flink:flink-shaded-guava|18.0-13.0|直接依赖|maven|
|com.googlecode.javaewah:JavaEWAH|1.1.13|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.9.10|间接依赖|maven|
|org.apache.hbase:hbase-annotations|1.4.6|间接依赖|maven|
|org.apache.kerby:kerby-config|1.0.1|间接依赖|maven|
|com.sun.mail:javax.mail|1.6.2|直接依赖|maven|
|commons-net:commons-net|3.1|间接依赖|maven|
|io.projectreactor:reactor-core|3.3.22.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|1.5.12.RELEASE|间接依赖|maven|
|net.java.dev.jna:jna|5.12.1|间接依赖|maven|
|org.scala-lang:scala-compiler|2.12.7|间接依赖|maven|
|io.springfox:springfox-spi|2.10.5|间接依赖|maven|
|org.jamon:jamon-runtime|2.4.1|间接依赖|maven|
|org.yaml:snakeyaml|1.30|间接依赖|maven|
|org.apache.flink:flink-core|1.17.0|间接依赖|maven|
|org.rocksdb:rocksdbjni|5.17.2|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.74|间接依赖|maven|
|org.apache.flink:flink-shaded-netty|4.1.65.Final-14.0|间接依赖|maven|
|org.apache.flink:flink-shaded-hadoop-3-uber|3.1.1.7.2.9.0-173-9.0|直接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.1|间接依赖|maven|
|org.eclipse.jetty:jetty-security|9.4.43.v20210629|间接依赖|maven|
|org.apache.commons:commons-csv|1.0|间接依赖|maven|
|org.dromara.sms4j:sms4j-api|2.1.0|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|com.jcraft:jsch|0.1.54|间接依赖|maven|
|org.javassist:javassist|3.28.0-GA|间接依赖|maven|
|org.codehaus.groovy:groovy|3.0.9|直接依赖|maven|
|com.baomidou:mybatis-plus-extension|3.5.3.1|间接依赖|maven|
|org.immutables:value|2.8.8|间接依赖|maven|
|commons-codec:commons-codec|1.13|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet-core|2.31|间接依赖|maven|
|com.google.http-client:google-http-client-gson|1.24.1|间接依赖|maven|
|org.apache.flink:flink-yarn_2.12|1.14.6|直接依赖|maven|
|com.oracle.ojdbc:ons|19.3.0.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.5|间接依赖|maven|
|com.amazonaws:aws-java-sdk-s3|1.12.481|直接依赖|maven|
|org.apache.hadoop:hadoop-hdfs-client|3.3.2|间接依赖|maven|
|org.dinky:dinky-flink-1.15|1.0.0-SNAPSHOT|直接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|org.apache.flink:flink-streaming-scala_2.12|1.15.2|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.4|间接依赖|maven|
|org.apache.flink:flink-python|1.16.0|直接依赖|maven|
|org.apache.flink:flink-table-planner_2.12|1.16.0|直接依赖|maven|
|org.dinky:dinky-scheduler|1.0.0-SNAPSHOT|直接依赖|maven|
|org.apache.flink:flink-connector-kafka_2.12|1.14.6|直接依赖|maven|
|org.apache.yetus:audience-annotations|0.11.0|间接依赖|maven|
|org.mortbay.jetty:servlet-api-2.5|6.1.14|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.74|间接依赖|maven|
|org.apache.flink:flink-table-api-scala_2.12|1.14.6|间接依赖|maven|
|org.apache.flink:flink-table-api-scala_2.12|1.17.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.17.2|间接依赖|maven|
|org.apache.flink:flink-table-common|1.16.0|直接依赖|maven|
|org.checkerframework:checker-qual|2.5.2|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.1|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.13.0|间接依赖|maven|
|org.apache.tephra:tephra-api|0.14.0-incubating|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|org.freemarker:freemarker|2.3.32|直接依赖|maven|
|jakarta.ws.rs:jakarta.ws.rs-api|2.1.6|间接依赖|maven|
|org.eclipse.jetty:jetty-http|9.4.43.v20210629|间接依赖|maven|
|org.apache.poi:poi-ooxml|5.2.3|直接依赖|maven|
|com.github.stephenc.jcip:jcip-annotations|1.0-1|间接依赖|maven|
|org.apache.orc:orc-shims|1.6.0|间接依赖|maven|
|com.esotericsoftware:minlog|1.3.0|间接依赖|maven|
|org.apache.yetus:audience-annotations|0.5.0|间接依赖|maven|
|io.fabric8:kubernetes-model-storageclass|5.12.4|间接依赖|maven|
|org.apache.kerby:kerb-simplekdc|1.0.1|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet|2.31|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.25|间接依赖|maven|
|org.apache.hadoop:hadoop-common|2.7.5|间接依赖|maven|
|org.apache.flink:flink-core|1.14.6|间接依赖|maven|
|org.apache.flink:flink-python|1.17.0|直接依赖|maven|
|org.apache.flink:flink-table-runtime|1.15.2|直接依赖|maven|
|com.github.virtuald:curvesapi|1.07|间接依赖|maven|
|org.dromara.sms4j:sms4j-provider|2.1.0|间接依赖|maven|
|org.apache.flink:flink-table-api-scala_2.12|1.16.0|间接依赖|maven|
|org.apache.doris:flink-doris-connector-1.13_2.12|1.0.3|直接依赖|maven|
|com.google.protobuf:protobuf-java|3.11.4|间接依赖|maven|
|com.lmax:disruptor|3.3.0|间接依赖|maven|
|io.springfox:springfox-swagger-common|2.10.5|间接依赖|maven|
|org.apache.curator:curator-framework|2.7.1|间接依赖|maven|
|com.ibm.icu:icu4j|60.2|间接依赖|maven|
|org.apache.flink:flink-scala_2.12|1.13.6|间接依赖|maven|
|sqlline:sqlline|1.2.0|间接依赖|maven|
|org.apache.kafka:connect-transforms|2.7.1|间接依赖|maven|
|javax.servlet:javax.servlet-api|3.1.0|间接依赖|maven|
|org.apache.kafka:connect-runtime|2.7.1|间接依赖|maven|
|org.slf4j:slf4j-nop|1.6.1|直接依赖|maven|
|commons-io:commons-io|2.8.0|间接依赖|maven|
|org.apache.flink:flink-streaming-java_2.11|1.13.1|间接依赖|maven|
|com.google.code.gson:gson|2.1|间接依赖|maven|
|com.oracle.ojdbc:ucp|19.3.0.0|间接依赖|maven|
|com.github.stephenc.findbugs:findbugs-annotations|1.3.9-1|间接依赖|maven|
|org.glassfish.hk2:osgi-resource-locator|1.0.3|间接依赖|maven|
|org.springframework:spring-context-support|5.3.27|直接依赖|maven|
|org.apache.flink:flink-metrics-core|1.16.0|间接依赖|maven|
|org.apache.avro:avro|1.7.4|间接依赖|maven|
|com.github.xiaoymin:knife4j-openapi2-spring-boot-starter|4.1.0|直接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.2|间接依赖|maven|
|org.apache.kafka:kafka-clients|2.4.1|间接依赖|maven|
|log4j:log4j|1.2.17|间接依赖|maven|
|org.apache.flink:flink-file-sink-common|1.15.2|间接依赖|maven|
|com.oracle.ojdbc:ojdbc8|19.3.0.0|间接依赖|maven|
|org.apache.flink:flink-cep|1.15.2|间接依赖|maven|
|org.jasypt:jasypt|1.9.3|直接依赖|maven|
|com.google.guava:guava|11.0.2|间接依赖|maven|
|org.jruby.jcodings:jcodings|1.0.8|间接依赖|maven|
|mysql:mysql-connector-java|8.0.27|间接依赖|maven|
|com.amazonaws:aws-java-sdk-kms|1.12.481|间接依赖|maven|
|com.amazonaws:aws-java-sdk-core|1.12.481|间接依赖|maven|
|tomcat:jasper-compiler|5.5.23|间接依赖|maven|
|io.prometheus:simpleclient_tracer_otel_agent|0.15.0|间接依赖|maven|
|io.fabric8:kubernetes-model-policy|5.12.4|间接依赖|maven|
|org.apache.flink:flink-table-api-scala-bridge_2.12|1.16.0|直接依赖|maven|
|org.slf4j:slf4j-log4j12|1.6.1|间接依赖|maven|
|io.prometheus.jmx:jmx_prometheus_javaagent|0.16.1|直接依赖|maven|
|org.apache.flink:flink-table-api-scala_2.12|1.15.2|间接依赖|maven|
|asm:asm|3.1|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.0.4.1|间接依赖|maven|
|org.mortbay.jetty:jetty-util|6.1.26|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.2|间接依赖|maven|
|org.apache.paimon:paimon-bundle|0.4.0-incubating|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.1|间接依赖|maven|
|io.netty:netty-transport|4.1.82.Final|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.69|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|3.3.2|间接依赖|maven|
|cn.dev33:sa-token-spring-boot-autoconfig|1.35.0.RC|间接依赖|maven|
|org.slf4j:slf4j-api|1.6.4|间接依赖|maven|
|org.eclipse.jetty:jetty-client|9.4.43.v20210629|间接依赖|maven|
|javax.activation:activation|1.1.1|直接依赖|maven|
|org.apache.hbase:hbase-protocol|1.2.3|间接依赖|maven|
|org.apache.commons:commons-lang3|3.3.2|直接依赖|maven|
|org.apache.parquet:parquet-common|1.11.1|间接依赖|maven|
|org.apache.kerby:kerb-client|1.0.1|间接依赖|maven|
|io.debezium:debezium-api|1.6.4.Final|间接依赖|maven|
|org.apache.flink:flink-streaming-java_2.12|1.14.6|直接依赖|maven|
|org.springframework:spring-jdbc|5.3.9|间接依赖|maven|
|org.apache.flink:flink-clients_2.12|1.14.6|直接依赖|maven|
|com.alibaba:druid|1.2.8|间接依赖|maven|
|io.swagger:swagger-models|1.6.6|间接依赖|maven|
|io.springfox:springfox-spring-web|2.10.5|间接依赖|maven|
|commons-logging:commons-logging|1.1.1|间接依赖|maven|
|org.springframework.data:spring-data-redis|2.7.11|间接依赖|maven|
|org.apache.parquet:parquet-hadoop|1.11.1|间接依赖|maven|
|org.glassfish.hk2:hk2-api|2.6.1|间接依赖|maven|
|io.netty:netty-handler|4.1.82.Final|间接依赖|maven|
|org.apache.flink:flink-json|1.14.6|直接依赖|maven|
|org.dinky:dinky-flink-1.14|1.0.0-SNAPSHOT|直接依赖|maven|
|org.glassfish.jersey.core:jersey-client|2.31|间接依赖|maven|
|commons-el:commons-el|1.0|间接依赖|maven|
|org.awaitility:awaitility|4.0.1|间接依赖|maven|
|org.apache.flink:flink-yarn|1.15.2|直接依赖|maven|
|org.apache.flink:flink-scala_2.12|1.16.0|间接依赖|maven|
|com.google.guava:guava|27.0-jre|间接依赖|maven|
|com.squareup.okhttp3:okhttp|3.14.9|间接依赖|maven|
|cn.dev33:sa-token-spring-boot-starter|1.35.0.RC|直接依赖|maven|
|org.dinky:dinky-process|1.0.0-SNAPSHOT|直接依赖|maven|
|org.springframework:spring-jcl|5.3.27|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|2.7.12|间接依赖|maven|
|org.dromara.sms4j:sms4j-comm|2.1.0|间接依赖|maven|
|cn.hutool:hutool-crypto|5.8.20|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.10.5|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-log4j2|2.7.11|直接依赖|maven|
|org.apache.hudi:hudi-hive-sync|0.10.1|间接依赖|maven|
|net.minidev:json-smart|2.4.7|间接依赖|maven|
|dnsjava:dnsjava|2.1.7|间接依赖|maven|
|org.apache.flink:flink-shaded-asm-7|7.1-13.0|间接依赖|maven|
|io.fabric8:kubernetes-model-extensions|5.12.4|间接依赖|maven|
|org.bouncycastle:bcutil-jdk15on|1.69|间接依赖|maven|
|org.apache.flink:flink-table-planner_2.12|1.15.2|直接依赖|maven|
|io.airlift:aircompressor|0.15|间接依赖|maven|
|com.ververica:flink-connector-debezium|2.3.0|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-jobclient|3.3.2|间接依赖|maven|
|net.java.dev.jets3t:jets3t|0.9.0|间接依赖|maven|
|net.minidev:accessors-smart|2.4.7|间接依赖|maven|
|org.dinky:dinky-client-1.15|1.0.0-SNAPSHOT|直接依赖|maven|
|com.google.code.gson:gson|2.2.4|间接依赖|maven|
|org.apache.flink:flink-runtime-web_2.12|1.14.6|直接依赖|maven|
|org.codehaus.janino:commons-compiler|3.0.11|间接依赖|maven|
|com.starrocks:flink-connector-starrocks|1.2.6_flink-1.15|直接依赖|maven|
|org.apache.flink:flink-core|1.15.2|直接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|org.apache.flink:flink-metrics-core|1.14.6|间接依赖|maven|
|org.apache.maven:maven-artifact|3.6.3|间接依赖|maven|
|com.sun.jersey.contribs:jersey-guice|1.19|间接依赖|maven|
|org.apache.commons:commons-configuration2|2.1.1|间接依赖|maven|
|com.ververica:flink-sql-connector-sqlserver-cdc|2.3.0|直接依赖|maven|
|org.dinky:dinky-flink-1.17|1.0.0-SNAPSHOT|直接依赖|maven|
|io.swagger:swagger-annotations|1.6.6|间接依赖|maven|
|org.apache.flink:flink-table-api-java|1.14.6|间接依赖|maven|
|org.apache.kerby:kerby-xdr|1.0.1|间接依赖|maven|
|com.esotericsoftware:kryo-shaded|4.0.2|间接依赖|maven|
|commons-logging:commons-logging|1.1.3|间接依赖|maven|
|com.google.code.findbugs:jsr305|1.3.9|间接依赖|maven|
|net.sourceforge.argparse4j:argparse4j|0.8.1|间接依赖|maven|
|org.apache.flink:flink-connector-kafka|1.16.0|直接依赖|maven|
|org.apache.kerby:kerb-util|1.0.1|间接依赖|maven|
|org.apache.flink:flink-kubernetes|1.17.0|直接依赖|maven|
|org.eclipse.jetty:jetty-xml|9.4.43.v20210629|间接依赖|maven|
|org.mortbay.jetty:jsp-2.1|6.1.14|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.1|间接依赖|maven|
|com.sun.jersey.contribs:jersey-guice|1.9|间接依赖|maven|
|org.apache.flink:flink-clients_2.12|1.13.6|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.5.3|间接依赖|maven|
|io.fabric8:kubernetes-model-scheduling|5.12.4|间接依赖|maven|
|org.apache.flink:flink-shaded-force-shading|14.0|间接依赖|maven|
|com.squareup.okio:okio|1.15.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.7.11|间接依赖|maven|
|org.eclipse.jgit:org.eclipse.jgit|5.13.1.202206130422-r|间接依赖|maven|
|org.apache.flink:flink-scala_2.12|1.17.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.7.11|间接依赖|maven|
|com.sun.activation:javax.activation|1.2.0|间接依赖|maven|
|com.baomidou:mybatis-plus|3.5.3.1|间接依赖|maven|
|org.apache.kafka:kafka-clients|2.8.1|间接依赖|maven|
|org.apache.flink:flink-clients_2.11|1.13.1|间接依赖|maven|
|org.apache.avro:avro|1.7.7|间接依赖|maven|
|org.apache.flink:flink-connector-jdbc|1.16.0|直接依赖|maven|
|org.dinky:dinky-flink-1.13|1.0.0-SNAPSHOT|直接依赖|maven|
|org.springframework:spring-messaging|5.3.27|间接依赖|maven|
|joda-time:joda-time|1.6|间接依赖|maven|
|com.github.oshi:oshi-core|6.4.2|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-redis|2.7.11|直接依赖|maven|
|cn.dev33:sa-token-core|1.35.0.RC|间接依赖|maven|
|it.unimi.dsi:fastutil|7.0.6|间接依赖|maven|
|net.java.dev.jna:jna-platform|5.13.0|间接依赖|maven|
|org.iq80.snappy:snappy|0.3|间接依赖|maven|
|com.yammer.metrics:metrics-core|2.2.0|间接依赖|maven|
|org.apache.flink:flink-streaming-java|1.17.0|间接依赖|maven|
|com.esri.geometry:esri-geometry-api|2.2.0|间接依赖|maven|
|org.apache.commons:commons-math3|3.6.1|间接依赖|maven|
|org.mortbay.jetty:servlet-api|2.5-20081211|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.0|间接依赖|maven|
|com.github.jsqlparser:jsqlparser|4.0|间接依赖|maven|
|junit:junit|4.12|间接依赖|maven|
|org.ow2.asm:asm|9.1|间接依赖|maven|
|software.amazon.ion:ion-java|1.0.2|间接依赖|maven|
|org.apache.hudi:hudi-flink_2.12|0.10.1|直接依赖|maven|
|org.apache.flink:flink-table-planner_2.12|1.13.6|直接依赖|maven|
|org.apache.curator:curator-framework|4.2.0|间接依赖|maven|
|org.apache.commons:commons-compress|1.4.1|间接依赖|maven|
|io.debezium:debezium-connector-oracle|1.6.4.Final|间接依赖|maven|
|org.apache.flink:flink-table-common|1.15.2|直接依赖|maven|
|org.codehaus.janino:janino|3.0.11|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-core|2.7.5|间接依赖|maven|
|org.antlr:antlr4-runtime|4.8|间接依赖|maven|
|com.h2database:h2|2.1.210|间接依赖|maven|
|org.apache.flink:flink-shaded-netty|4.1.49.Final-13.0|间接依赖|maven|
|org.apache.pulsar:pulsar-client-api|2.10.2|直接依赖|maven|
|com.oracle.ojdbc:oraclepki|19.3.0.0|间接依赖|maven|
|org.apache.flink:flink-streaming-java|1.15.2|间接依赖|maven|
|org.dinky:dinky-gateway|1.0.0-SNAPSHOT|直接依赖|maven|
|org.apache.flink:force-shading|1.13.6|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.12|间接依赖|maven|
|org.apache.flink:flink-table-api-java-bridge_2.12|1.13.6|间接依赖|maven|
|org.apache.logging.log4j:log4j-jul|2.17.2|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.0|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.5.6|间接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5|5.0.2|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.1|间接依赖|maven|
|org.immutables:value-annotations|2.8.8|间接依赖|maven|
|com.clearspring.analytics:stream|2.9.5|间接依赖|maven|
|org.apache.flink:flink-java|1.15.2|间接依赖|maven|
|org.apache.flink:flink-table-common|1.17.0|直接依赖|maven|
|org.apache.httpcomponents.client5:httpclient5|5.0.3|间接依赖|maven|
|org.antlr:antlr-runtime|3.5.2|间接依赖|maven|
|com.sun.jersey:jersey-core|1.9|间接依赖|maven|
|io.fabric8:kubernetes-model-discovery|5.12.4|间接依赖|maven|
|org.dromara.sms4j:sms4j-autoimmit|2.1.0|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.11|间接依赖|maven|
|com.alibaba:druid-spring-boot-starter|1.2.8|直接依赖|maven|
|org.apache.flink:flink-connector-pulsar_2.12|1.14.6|直接依赖|maven|
|org.apache.flink:flink-table-api-java-bridge|1.17.0|间接依赖|maven|
|com.google.protobuf:protobuf-java|2.5.0|间接依赖|maven|
|com.google.code.findbugs:jsr305|2.0.1|间接依赖|maven|
|org.apache.doris:flink-doris-connector-1.16|1.3.0|直接依赖|maven|
|org.dinky:dinky-function|1.0.0-SNAPSHOT|直接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.7.3|间接依赖|maven|
|com.beust:jcommander|1.72|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.0|间接依赖|maven|
|org.dinky:dinky-cdc-core|1.0.0-SNAPSHOT|直接依赖|maven|
|org.apache.flink:flink-annotations|1.13.6|间接依赖|maven|
|io.micrometer:micrometer-core|1.9.10|间接依赖|maven|
|joda-time:joda-time|2.5|间接依赖|maven|
|org.apache.flink:flink-annotations|1.17.0|间接依赖|maven|
|org.springframework:spring-context|5.3.27|间接依赖|maven|
|org.apache.parquet:parquet-jackson|1.11.1|间接依赖|maven|
|org.apache.flink:flink-shaded-jackson|2.12.4-15.0|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.7.11|间接依赖|maven|
|org.apache.flink:flink-metrics-core|1.17.0|间接依赖|maven|
|org.apache.hbase:hbase-prefix-tree|1.2.3|间接依赖|maven|
|com.sun.jersey:jersey-server|1.19|间接依赖|maven|
|io.netty:netty|3.10.6.Final|间接依赖|maven|
|com.squareup.okio:okio|1.6.0|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.10.5|间接依赖|maven|
|io.netty:netty-all|4.1.68.Final|间接依赖|maven|
|org.apache.flink:flink-metrics-core|1.15.2|间接依赖|maven|
|org.checkerframework:checker-qual|3.12.0|间接依赖|maven|
|org.glassfish.jersey.inject:jersey-hk2|2.31|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.0.1|间接依赖|maven|
|org.bouncycastle:bcprov-ext-jdk15on|1.69|直接依赖|maven|
|com.ververica:flink-sql-connector-mysql-cdc|2.3.0|直接依赖|maven|
|io.prometheus:simpleclient|0.15.0|间接依赖|maven|
|com.google.guava:guava|19.0|间接依赖|maven|
|javax.validation:validation-api|2.0.1.Final|直接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-core|3.3.2|直接依赖|maven|
|com.squareup.okio:okio|1.17.2|间接依赖|maven|
|org.apache.hudi:hudi-sync-common|0.10.1|间接依赖|maven|
|org.apache.flink:flink-connector-base|1.15.2|间接依赖|maven|
|javax.ws.rs:javax.ws.rs-api|2.1.1|间接依赖|maven|
|io.springfox:springfox-core|2.10.5|间接依赖|maven|
|joda-time:joda-time|2.9.3|间接依赖|maven|
|org.apache.hadoop.thirdparty:hadoop-shaded-guava|1.1.1|间接依赖|maven|
|org.apache.parquet:parquet-format-structures|1.11.1|间接依赖|maven|
|org.apache.flink:flink-clients|1.16.0|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-core|2.7.3|间接依赖|maven|
|com.sun.xml.bind:jaxb-core|2.3.0|直接依赖|maven|
|com.google.inject:guice|4.0|间接依赖|maven|
|org.eclipse.jetty:jetty-continuation|9.4.38.v20210224|间接依赖|maven|
|org.apache.hadoop:hadoop-client|3.3.2|直接依赖|maven|
|org.apache.flink:flink-core|1.16.0|间接依赖|maven|
|org.apache.flink:flink-table-api-scala-bridge_2.12|1.15.2|直接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.1|间接依赖|maven|
|org.apache.doris:flink-doris-connector-1.14_2.12|1.1.1|直接依赖|maven|
|org.codehaus.jackson:jackson-jaxrs|1.9.13|间接依赖|maven|
|org.apache.commons:commons-math3|3.1.1|间接依赖|maven|
|org.apache.flink:flink-annotations|1.16.0|间接依赖|maven|
|org.dinky:dinky-common|1.0.0-SNAPSHOT|直接依赖|maven|
|org.apache.flink:flink-connector-kafka|1.15.2|直接依赖|maven|
|org.codehaus.jackson:jackson-jaxrs|1.9.2|间接依赖|maven|
|io.springfox:springfox-spring-webmvc|2.10.5|间接依赖|maven|
|org.apache.kerby:kerb-identity|1.0.1|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.5|直接依赖|maven|
|org.glassfish.hk2:hk2-utils|2.6.1|间接依赖|maven|
|org.jruby.joni:joni|2.1.2|间接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.9.2|间接依赖|maven|
|com.oracle.database.xml:xdb|19.3.0.0|间接依赖|maven|
|io.debezium:debezium-embedded|1.6.4.Final|间接依赖|maven|
|io.fabric8:kubernetes-model-node|5.12.4|间接依赖|maven|
|org.glassfish.jersey.media:jersey-media-jaxb|2.31|间接依赖|maven|
|org.apiguardian:apiguardian-api|1.1.2|间接依赖|maven|
|org.apache.flink:flink-connector-jdbc|3.1.0-1.17|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|2.7.11|直接依赖|maven|
|com.github.luben:zstd-jni|1.5.2-1|间接依赖|maven|
|org.sonatype.sisu.inject:cglib|2.2.1-v20090111|间接依赖|maven|
|org.javassist:javassist|3.25.0-GA|间接依赖|maven|
|com.sun.jersey:jersey-servlet|1.19|间接依赖|maven|
|xmlenc:xmlenc|0.52|间接依赖|maven|
|com.baomidou:mybatis-plus-core|3.5.3.1|间接依赖|maven|
|org.mapstruct:mapstruct|1.3.1.Final|间接依赖|maven|
|tomcat:jasper-runtime|5.5.23|间接依赖|maven|
|com.squareup.okhttp3:logging-interceptor|3.12.12|间接依赖|maven|
|com.sun.jersey:jersey-core|1.19|间接依赖|maven|
|org.apache.zookeeper:zookeeper-jute|3.5.6|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.14.1|直接依赖|maven|
|org.slf4j:slf4j-log4j12|1.7.30|间接依赖|maven|
|org.apache.hudi:hudi-hadoop-mr|0.10.1|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.27|间接依赖|maven|
|com.github.xiaoymin:knife4j-openapi2-ui|4.1.0|间接依赖|maven|
|org.aspectj:aspectjweaver|1.9.7|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.2.2|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|2.7.3|间接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|间接依赖|maven|
|com.oracle.ojdbc:osdt_cert|19.3.0.0|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.13.1|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|com.twitter:bijection-core_2.11|0.9.7|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.4.1|间接依赖|maven|
|io.fabric8:kubernetes-model-metrics|5.12.4|间接依赖|maven|
|org.projectlombok:lombok|1.18.24|直接依赖|maven|
|io.fabric8:kubernetes-model-batch|5.12.4|间接依赖|maven|
|io.fabric8:kubernetes-model-networking|5.12.4|间接依赖|maven|
|org.apache.kerby:kerb-core|1.0.1|间接依赖|maven|
|commons-configuration:commons-configuration|1.6|间接依赖|maven|
|org.springframework:spring-aop|5.3.27|间接依赖|maven|
|io.netty:netty-buffer|4.1.82.Final|间接依赖|maven|
|org.dinky:dinky-metadata-base|1.0.0-SNAPSHOT|直接依赖|maven|
|org.eclipse.jetty:jetty-server|9.4.43.v20210629|间接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.3|间接依赖|maven|
|com.zendesk:mysql-binlog-connector-java|0.25.3|间接依赖|maven|
|org.apache.flink:flink-table-api-scala-bridge_2.12|1.17.0|直接依赖|maven|
|org.eclipse.jetty:jetty-server|9.4.38.v20210224|间接依赖|maven|
|javax.servlet.jsp:jsp-api|2.1|间接依赖|maven|
|com.google.guava:failureaccess|1.0|间接依赖|maven|
|com.github.xiaoymin:knife4j-core|4.1.0|间接依赖|maven|
|com.alibaba:fastjson|1.2.69|间接依赖|maven|
|cn.hutool:hutool-all|5.8.18|间接依赖|maven|
|commons-io:commons-io|2.4|间接依赖|maven|
|org.apache.pulsar:bouncy-castle-bc|2.10.2|间接依赖|maven|
|org.apache.flink:flink-yarn_2.12|1.13.6|直接依赖|maven|
|com.google.http-client:google-http-client|1.24.1|间接依赖|maven|
|org.eclipse.jetty:jetty-http|9.4.38.v20210224|间接依赖|maven|
|com.lmax:disruptor|3.3.6|间接依赖|maven|
|org.apache.flink:flink-optimizer_2.12|1.13.6|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.14.1|直接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.18.0|间接依赖|maven|
|org.eclipse.jetty:jetty-servlets|9.4.38.v20210224|间接依赖|maven|
|org.glassfish.jersey.core:jersey-server|2.31|间接依赖|maven|
|org.apache.flink:flink-scala_2.12|1.14.6|间接依赖|maven|
|org.apache.flink:flink-optimizer|1.14.6|间接依赖|maven|
|org.apache.kerby:kerby-asn1|1.0.1|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.4.6|间接依赖|maven|
|org.springframework.data:spring-data-ldap|3.1.0|间接依赖|maven|
|net.jcip:jcip-annotations|1.0|间接依赖|maven|
|org.apache.flink:flink-java|1.13.6|间接依赖|maven|
|io.fabric8:kubernetes-model-admissionregistration|5.12.4|间接依赖|maven|
|org.apache.flink:flink-clients|1.17.0|间接依赖|maven|
|org.apache.calcite.avatica:avatica-core|1.17.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.7.11|间接依赖|maven|
|com.github.luben:zstd-jni|1.4.3-1|间接依赖|maven|
|commons-beanutils:commons-beanutils-core|1.8.0|间接依赖|maven|
|org.springframework.plugin:spring-plugin-metadata|2.0.0.RELEASE|间接依赖|maven|
|commons-lang:commons-lang|2.6|间接依赖|maven|
|org.apache.httpcomponents:httpclient-cache|4.5.13|间接依赖|maven|
|com.twitter:chill-java|0.7.6|间接依赖|maven|
|commons-daemon:commons-daemon|1.0.13|间接依赖|maven|
|org.dinky:dinky-daemon|1.0.0-SNAPSHOT|直接依赖|maven|
|io.lettuce:lettuce-core|6.1.10.RELEASE|间接依赖|maven|
|org.hibernate:hibernate-validator|6.2.0.Final|直接依赖|maven|
|org.apache.flink:flink-connector-base|1.16.0|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|org.apache.hbase:hbase-protocol|1.4.6|间接依赖|maven|
|net.sourceforge.argparse4j:argparse4j|0.7.0|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.1|间接依赖|maven|
|org.apache.flink:flink-table-api-bridge-base|1.16.0|间接依赖|maven|
|org.apache.hbase:hbase-annotations|1.2.3|间接依赖|maven|
|com.oracle.ojdbc:osdt_core|19.3.0.0|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|2.7.3|间接依赖|maven|
|io.fabric8:kubernetes-model-common|5.12.4|间接依赖|maven|
|org.apache.flink:flink-shaded-netty|4.1.70.Final-15.0|间接依赖|maven|
|org.apache.orc:orc-core|1.6.0|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.10.5|间接依赖|maven|
|org.apache.flink:flink-connector-jdbc_2.12|1.13.6|直接依赖|maven|
|com.sun.xml.bind:jaxb-impl|2.2.3-1|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-common|3.3.2|间接依赖|maven|
|io.fabric8:kubernetes-model-core|5.12.4|间接依赖|maven|
|io.springfox:springfox-swagger2|2.10.5|间接依赖|maven|
|commons-codec:commons-codec|1.7|间接依赖|maven|
|org.apache.flink:flink-metrics-core|1.13.6|间接依赖|maven|
|org.dinky:dinky-alert-base|1.0.0-SNAPSHOT|直接依赖|maven|
|org.codehaus.plexus:plexus-utils|3.2.1|间接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|9.8.1|间接依赖|maven|
|com.github.docker-java:docker-java-transport-httpclient5|3.2.14|直接依赖|maven|
|org.apache.flink:flink-file-sink-common|1.14.6|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.0|直接依赖|maven|
|org.osgi:org.osgi.core|4.3.1|间接依赖|maven|
|org.apache.doris:flink-doris-connector-1.15|1.2.1|直接依赖|maven|
|org.apache.kerby:kerb-admin|1.0.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-websocket|2.7.11|直接依赖|maven|
|org.apache.flink:flink-optimizer|1.17.0|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.13|间接依赖|maven|
|org.apache.commons:commons-text|1.10.0|间接依赖|maven|
|org.apache.kafka:kafka-tools|2.7.1|间接依赖|maven|
|com.beust:jcommander|1.78|间接依赖|maven|
|org.fusesource.leveldbjni:leveldbjni-all|1.8|间接依赖|maven|
|io.springfox:springfox-bean-validators|2.10.5|间接依赖|maven|
|org.glassfish.hk2.external:aopalliance-repackaged|2.6.1|间接依赖|maven|
|org.eclipse.jgit:org.eclipse.jgit.ssh.jsch|5.13.1.202206130422-r|直接依赖|maven|
|org.apache.flink:flink-runtime-web|1.15.2|直接依赖|maven|
|com.github.docker-java:docker-java-core|3.2.14|直接依赖|maven|
|javax.ws.rs:jsr311-api|1.1.1|间接依赖|maven|
|javax.ws.rs:javax.ws.rs-api|2.1|间接依赖|maven|
|com.google.guava:guava|13.0.1|间接依赖|maven|
|org.codehaus.jackson:jackson-mapper-asl|1.9.2|间接依赖|maven|
|org.jetbrains:annotations|17.0.0|间接依赖|maven|
|org.apache.flink:flink-optimizer|1.15.2|间接依赖|maven|
|org.apache.flink:flink-file-sink-common|1.13.6|间接依赖|maven|
|junit:junit|4.13.2|直接依赖|maven|
|org.apache.flink:flink-python_2.12|1.14.6|直接依赖|maven|
|org.apache.flink:flink-connector-jdbc|1.15.2|直接依赖|maven|
|org.apache.hadoop:hadoop-annotations|3.3.2|间接依赖|maven|
|com.baomidou:mybatis-plus-annotation|3.5.3.1|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.2.11|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator|2.7.11|间接依赖|maven|
|org.apache.flink:flink-optimizer|1.16.0|间接依赖|maven|
|io.netty:netty-all|4.0.23.Final|间接依赖|maven|
|io.github.classgraph:classgraph|4.1.7|间接依赖|maven|
|org.apache.flink:flink-shaded-jackson|2.12.4-14.0|间接依赖|maven|
|org.eclipse.jetty:jetty-util-ajax|9.4.38.v20210224|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|间接依赖|maven|
|io.fabric8:kubernetes-model-events|5.12.4|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-actuator|2.7.11|直接依赖|maven|
|com.jcraft:jsch|0.1.55|间接依赖|maven|
|com.ibm.icu:icu4j-localespi|60.2|间接依赖|maven|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13|间接依赖|maven|
|com.github.jsqlparser:jsqlparser|4.4|直接依赖|maven|
|org.codehaus.jackson:jackson-jaxrs|1.8.3|间接依赖|maven|
|javax.xml.stream:stax-api|1.0-2|间接依赖|maven|
|org.apache.flink:flink-kubernetes|1.16.0|直接依赖|maven|
|org.slf4j:slf4j-log4j12|1.7.10|间接依赖|maven|
|org.codehaus.jackson:jackson-xc|1.9.13|间接依赖|maven|
|org.apache.flink:flink-shaded-force-shading|16.1|间接依赖|maven|
|io.fabric8:kubernetes-model-autoscaling|5.12.4|间接依赖|maven|
|com.ibm.icu:icu4j-charset|60.2|间接依赖|maven|
|org.apache.kerby:kerby-util|1.0.1|间接依赖|maven|
|org.apache.flink:flink-connector-base|1.17.0|间接依赖|maven|
|org.eclipse.jetty:jetty-security|9.4.38.v20210224|间接依赖|maven|
|com.starrocks:flink-connector-starrocks|1.2.3_flink-1.14_2.12|直接依赖|maven|
|org.springframework:spring-expression|5.3.27|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.12|间接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.4.38.v20210224|间接依赖|maven|
|io.micrometer:micrometer-registry-prometheus|1.9.10|直接依赖|maven|
|org.apache.flink:flink-connector-base|1.13.6|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.1|间接依赖|maven|
|commons-codec:commons-codec|1.4|间接依赖|maven|
|org.apache.flink:flink-streaming-java_2.12|1.13.6|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.43.v20210629|间接依赖|maven|
|org.apache.flink:flink-table-api-java|1.15.2|直接依赖|maven|
|org.apache.poi:poi-ooxml-lite|5.2.3|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.11.0|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.10.5|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.2|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|io.netty:netty|3.6.2.Final|间接依赖|maven|
|org.apache.commons:commons-text|1.4|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.2.0|间接依赖|maven|
|com.google.guava:guava|31.1-jre|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.5|间接依赖|maven|
|org.apache.flink:flink-streaming-scala_2.12|1.13.6|间接依赖|maven|
|com.google.inject.extensions:guice-servlet|4.0|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|org.apache.flink:flink-kubernetes_2.12|1.14.6|直接依赖|maven|
|org.reflections:reflections|0.9.12|间接依赖|maven|
|org.apache.kafka:connect-file|2.7.1|间接依赖|maven|
|org.apache.flink:flink-table-api-scala-bridge_2.12|1.14.6|间接依赖|maven|
|javax.servlet:servlet-api|2.5|间接依赖|maven|
|com.twitter:chill_2.12|0.7.6|间接依赖|maven|
|io.fabric8:kubernetes-client|5.12.4|直接依赖|maven|
|com.ververica:flink-sql-connector-postgres-cdc|2.3.0|直接依赖|maven|
|com.ververica:flink-connector-oracle-cdc|2.3.0|直接依赖|maven|
|org.apache.flink:flink-table-planner_2.12|1.14.6|直接依赖|maven|
|com.github.mifmif:generex|1.0.2|间接依赖|maven|
|com.sun.jersey:jersey-json|1.9|间接依赖|maven|
|com.jamesmurty.utils:java-xmlbuilder|0.4|间接依赖|maven|
|com.ibm.icu:icu4j|67.1|间接依赖|maven|
|org.dinky:dinky-core|1.0.0-SNAPSHOT|直接依赖|maven|
|net.java.dev.jna:jna|5.13.0|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.25|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-ldap|3.1.0|直接依赖|maven|
|mysql:mysql-connector-java|8.0.28|直接依赖|maven|
|org.apache.curator:curator-recipes|4.2.0|间接依赖|maven|
|org.apache.flink:flink-hadoop-compatibility_2.11|1.13.1|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-client|9.4.43.v20210629|间接依赖|maven|
|org.apache.pulsar:pulsar-client-admin-api|2.10.2|间接依赖|maven|
|org.apache.flink:flink-core|1.13.6|间接依赖|maven|
|org.yaml:snakeyaml|1.28|间接依赖|maven|
|org.springframework.plugin:spring-plugin-core|2.0.0.RELEASE|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.33|间接依赖|maven|
|org.apache.flink:flink-table-api-java-bridge|1.15.2|直接依赖|maven|
|org.apache.kerby:kerby-pkix|1.0.1|间接依赖|maven|
|org.apache.flink:flink-table-planner-blink_2.12|1.13.6|直接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.38.v20210224|间接依赖|maven|
|org.springframework.data:spring-data-commons|3.1.0|间接依赖|maven|
|org.apache.flink:flink-connector-jdbc_2.12|1.14.6|直接依赖|maven|
|io.netty:netty-common|4.1.82.Final|间接依赖|maven|
|org.apache.flink:flink-java|1.16.0|间接依赖|maven|
|com.zaxxer:SparseBitSet|1.2|间接依赖|maven|
|org.apache.commons:commons-compress|1.20|间接依赖|maven|
|io.fabric8:kubernetes-model-apps|5.12.4|间接依赖|maven|
|org.glassfish.hk2:hk2-locator|2.6.1|间接依赖|maven|
|org.apache.flink:flink-shaded-asm-7|7.1-14.0|间接依赖|maven|
|io.netty:netty-codec|4.1.82.Final|间接依赖|maven|
|org.apache.flink:flink-java|1.14.6|间接依赖|maven|
|org.mybatis:mybatis|3.5.10|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.1|间接依赖|maven|
|com.salesforce.i18n:i18n-util|1.0.4|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.38.v20210224|间接依赖|maven|
|org.apache.flink:flink-kubernetes|1.15.2|直接依赖|maven|
|org.dinky:dinky-client-base|1.0.0-SNAPSHOT|直接依赖|maven|
|org.apache.flink:flink-streaming-scala_2.12|1.14.6|间接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.4.43.v20210629|间接依赖|maven|
|org.apache.flink:flink-connector-kafka|1.17.0|直接依赖|maven|
|org.apache.flink:flink-scala_2.12|1.15.2|间接依赖|maven|
|org.apache.flink:flink-table-api-java-bridge|1.16.0|间接依赖|maven|
|com.sun.jersey:jersey-server|1.9|间接依赖|maven|
|org.codehaus.jettison:jettison|1.1|间接依赖|maven|
|org.apache.flink:flink-yarn|1.17.0|直接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.2|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.12.6|间接依赖|maven|
|org.apache.flink:flink-table-api-java|1.16.0|间接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|5.3.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.7.11|直接依赖|maven|
|io.prometheus:simpleclient_tracer_common|0.15.0|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|直接依赖|maven|
|org.apache.poi:poi|5.2.3|直接依赖|maven|
|com.google.inject.extensions:guice-servlet|3.0|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.7.0|间接依赖|maven|
|org.glassfish.jersey.core:jersey-common|2.31|间接依赖|maven|
|cn.hutool:hutool-jwt|5.8.20|间接依赖|maven|
|org.apache.htrace:htrace-core|3.1.0-incubating|间接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.43.v20210629|间接依赖|maven|
|org.apache.flink:flink-file-sink-common|1.16.0|间接依赖|maven|
|org.springframework:spring-tx|5.3.27|间接依赖|maven|
|org.apache.hbase:hbase-client|1.2.3|间接依赖|maven|
|org.apache.kafka:connect-json|2.7.1|间接依赖|maven|
|org.yaml:snakeyaml|1.33|直接依赖|maven|
|com.google.inject:guice|3.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.11.0|间接依赖|maven|
|org.apache.kerby:kerb-crypto|1.0.1|间接依赖|maven|
|org.hamcrest:hamcrest|2.1|间接依赖|maven|
|org.dinky:dinky-client-1.14|1.0.0-SNAPSHOT|直接依赖|maven|
|org.apache.flink:flink-shaded-guava|30.1.1-jre-16.0|直接依赖|maven|
|com.jdcloud.sdk:sms|1.3.3|间接依赖|maven|
|org.codehaus.woodstox:stax2-api|4.2.1|间接依赖|maven|
|jline:jline|2.11|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.12|间接依赖|maven|
|dk.brics.automaton:automaton|1.11-8|间接依赖|maven|
|com.oracle.ojdbc:simplefan|19.3.0.0|间接依赖|maven|
|org.apache.phoenix:phoenix-core|4.14.2-HBase-1.4|直接依赖|maven|
|org.apache.flink:flink-table-api-java-bridge_2.12|1.14.6|间接依赖|maven|
|io.fabric8:kubernetes-model-flowcontrol|5.12.4|间接依赖|maven|
|org.apache.flink:flink-shaded-asm-9|9.2-15.0|间接依赖|maven|
|org.springframework.boot:spring-boot|2.7.12|间接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|org.dromara.sms4j:sms4j-core|2.1.0|间接依赖|maven|
|com.googlecode.juniversalchardet:juniversalchardet|1.0.3|间接依赖|maven|
|org.apache.flink:flink-connector-kafka_2.12|1.13.6|直接依赖|maven|
|org.apache.flink:flink-connector-base|1.14.6|间接依赖|maven|
|org.apache.flink:flink-table-code-splitter|1.14.6|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.13.0|间接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.9.13|间接依赖|maven|
|com.sun.jersey:jersey-json|1.19|间接依赖|maven|
|cn.dev33:sa-token-servlet|1.35.0.RC|间接依赖|maven|
|io.springfox:springfox-schema|2.10.5|间接依赖|maven|
|org.apache.kafka:connect-api|2.7.1|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.74|间接依赖|maven|
|org.lz4:lz4-java|1.6.0|间接依赖|maven|
|com.sun.jersey:jersey-client|1.9|间接依赖|maven|
|commons-codec:commons-codec|1.11|间接依赖|maven|
|org.springframework:spring-websocket|5.3.27|间接依赖|maven|
|joda-time:joda-time|2.8.1|间接依赖|maven|
|org.apache.flink:flink-clients|1.15.2|直接依赖|maven|
|com.github.luben:zstd-jni|1.4.9-1|间接依赖|maven|
|org.apache.flink:flink-yarn|1.16.0|直接依赖|maven|
|com.ververica:flink-cdc-base|2.3.0|间接依赖|maven|
|org.springframework:spring-beans|5.3.27|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|3.3.2|直接依赖|maven|
|org.apache.hadoop.thirdparty:hadoop-shaded-protobuf_3_7|1.1.1|间接依赖|maven|
|org.apache.flink:flink-streaming-java|1.16.0|间接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|org.apache.hadoop:hadoop-hdfs|3.3.2|直接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|间接依赖|maven|
|commons-io:commons-io|2.11.0|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)