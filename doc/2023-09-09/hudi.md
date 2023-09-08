# apache/hudi安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700208317238476800.svg)](https://www.murphysec.com/console/report/1700208317171367936/1700208317238476800)

仓库描述：Upserts, Deletes And Incremental Processing on Big Data.

仓库地址：[https://github.com/apache/hudi](https://github.com/apache/hudi)

| star：4477 | watch：1178 | fork：2274 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-09 02:00:40 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-09 02:56:43 | 组件总数：599 | 漏洞总数：109 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache Commons HttpClient Amazon FPS 输入验证错误漏洞|证书验证不恰当|[MPS-2012-4618](https://www.oscs1024.com/hd/MPS-2012-4618)|CVE-2012-5783|中危|
|Apache HttpClient 中间人攻击漏洞|输入验证不恰当|[MPS-2014-4288](https://www.oscs1024.com/hd/MPS-2014-4288)|CVE-2012-6153|中危|
|Apache Zookeeper 安全漏洞||[MPS-2017-11297](https://www.oscs1024.com/hd/MPS-2017-11297)|CVE-2017-5637|高危|
|Netty和Play Framework 输入验证错误漏洞|未授权敏感信息泄露|[MPS-2017-11682](https://www.oscs1024.com/hd/MPS-2017-11682)|CVE-2015-2156|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不可达退出条件的循环（无限循环）|[MPS-2018-11233](https://www.oscs1024.com/hd/MPS-2018-11233)|CVE-2018-11771|中危|
|Apache Hive HiveServer2  访问控制不恰当漏洞|访问控制不当|[MPS-2018-14541](https://www.oscs1024.com/hd/MPS-2018-14541)|CVE-2018-11777|高危|
|Apache Hive  授权机制缺失漏洞|授权检查缺失|[MPS-2018-14542](https://www.oscs1024.com/hd/MPS-2018-14542)|CVE-2018-1314|中危|
|Apache Hive JDBC驱动程序SQL注入漏洞|SQL注入|[MPS-2018-4306](https://www.oscs1024.com/hd/MPS-2018-4306)|CVE-2018-1282|严重|
|Apache Hive 任意文件读取漏洞|未授权敏感信息泄露|[MPS-2018-4307](https://www.oscs1024.com/hd/MPS-2018-4307)|CVE-2018-1284|低危|
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|Apache Zookeeper 访问控制错误漏洞|授权检查缺失|[MPS-2018-6313](https://www.oscs1024.com/hd/MPS-2018-6313)|CVE-2018-8012|高危|
|Netty 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2019-12064](https://www.oscs1024.com/hd/MPS-2019-12064)|CVE-2019-16869|高危|
|Red Hat JBoss Enterprise Application Platform 代码问题漏洞|反序列化|[MPS-2019-12470](https://www.oscs1024.com/hd/MPS-2019-12470)|CVE-2019-10202|严重|
|jackson-mapper-asl <=1.9.13 XXE 注入漏洞|XXE|[MPS-2019-15048](https://www.oscs1024.com/hd/MPS-2019-15048)|CVE-2019-10172|高危|
|Apache Tomcat 授权问题漏洞|会话固定|[MPS-2019-16906](https://www.oscs1024.com/hd/MPS-2019-16906)|CVE-2019-17563|高危|
|Apache Zookeeper 授权问题漏洞|授权检查缺失|[MPS-2019-5668](https://www.oscs1024.com/hd/MPS-2019-5668)|CVE-2019-0201|中危|
|Apache Calcite 访问控制错误漏洞|关键功能的认证机制缺失|[MPS-2020-14130](https://www.oscs1024.com/hd/MPS-2020-14130)|CVE-2020-13955|中危|
|MyBatis <3.5.6 存在反序列化漏洞|反序列化|[MPS-2020-14133](https://www.oscs1024.com/hd/MPS-2020-14133)|CVE-2020-26945|高危|
|Apache Tomcat HTTP请求走私漏洞|HTTP请求走私|[MPS-2020-15344](https://www.oscs1024.com/hd/MPS-2020-15344)|CVE-2020-13943|中危|
|Apache HttpClient URI解析错误漏洞|XSS|[MPS-2020-17341](https://www.oscs1024.com/hd/MPS-2020-17341)|CVE-2020-13956|中危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2020-17486](https://www.oscs1024.com/hd/MPS-2020-17486)|CVE-2020-17527|高危|
|Apache Tomcat 权限管理不当漏洞|权限管理不当|[MPS-2020-2841](https://www.oscs1024.com/hd/MPS-2020-2841)|CVE-2020-1938|严重|
|mysql:mysql-connector-java <8.0.27 存在 XXE 漏洞|XXE|[MPS-2020-38350](https://www.oscs1024.com/hd/MPS-2020-38350)|CVE-2021-2471|中危|
|Netty ZlibDecoders 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2020-5127](https://www.oscs1024.com/hd/MPS-2020-5127)|CVE-2020-11612|高危|
|Apache Ant 临时文件不安全问题|将资源暴露给错误范围|[MPS-2020-7418](https://www.oscs1024.com/hd/MPS-2020-7418)|CVE-2020-1945|中危|
|Apache Tomcat 远程代码执行漏洞|反序列化|[MPS-2020-7626](https://www.oscs1024.com/hd/MPS-2020-7626)|CVE-2020-9484|高危|
|Apache Tomcat 拒绝服务漏洞|拒绝服务|[MPS-2020-9541](https://www.oscs1024.com/hd/MPS-2020-9541)|CVE-2020-11996|高危|
|Apache Tomcat 授权问题漏洞|身份验证不当|[MPS-2021-10264](https://www.oscs1024.com/hd/MPS-2021-10264)|CVE-2021-30640|中危|
|Apache Commons Compress 安存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10550](https://www.oscs1024.com/hd/MPS-2021-10550)|CVE-2021-35517|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10551](https://www.oscs1024.com/hd/MPS-2021-10551)|CVE-2021-35516|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10564](https://www.oscs1024.com/hd/MPS-2021-10564)|CVE-2021-36090|高危|
|Apache Commons Compress 无限循环漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-10565](https://www.oscs1024.com/hd/MPS-2021-10565)|CVE-2021-35515|高危|
|Netty <4.1.59.Final 存在不安全的临时文件漏洞||[MPS-2021-1580](https://www.oscs1024.com/hd/MPS-2021-1580)|CVE-2021-21290|中危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-1722](https://www.oscs1024.com/hd/MPS-2021-1722)|CVE-2021-24122|中危|
|Google google-oauth-java-client 数据伪造问题漏洞|密码学签名的验证不恰当|[MPS-2021-19070](https://www.oscs1024.com/hd/MPS-2021-19070)|CVE-2021-22573|高危|
|com.h2database:h2 < 2.0.202 XXE漏洞|XXE|[MPS-2021-19502](https://www.oscs1024.com/hd/MPS-2021-19502)|CVE-2021-23463|严重|
|Apache Tomcat 信息泄露漏洞|HTTP请求走私|[MPS-2021-2309](https://www.oscs1024.com/hd/MPS-2021-2309)|CVE-2021-25122|高危|
|Apache Tomcat 远程代码执行漏洞|代码注入|[MPS-2021-2466](https://www.oscs1024.com/hd/MPS-2021-2466)|CVE-2021-25329|高危|
|Apache Hive 未授权访问 UDF 漏洞|关键功能的认证机制缺失|[MPS-2021-25837](https://www.oscs1024.com/hd/MPS-2021-25837)|CVE-2021-34538|高危|
|Netty Bzip2Decoder 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28116](https://www.oscs1024.com/hd/MPS-2021-28116)|CVE-2021-37136|高危|
|Netty 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28117](https://www.oscs1024.com/hd/MPS-2021-28117)|CVE-2021-37137|高危|
|Apache Commons Net <3.9.0 存在FTP跳转攻击漏洞|未授权敏感信息泄露|[MPS-2021-28440](https://www.oscs1024.com/hd/MPS-2021-28440)|CVE-2021-37533|中危|
|Apache Tomcat 拒绝服务漏洞|拒绝服务|[MPS-2021-31848](https://www.oscs1024.com/hd/MPS-2021-31848)|CVE-2021-41079|高危|
|Apache Parquet 输入验证错误漏洞|拒绝服务|[MPS-2021-32354](https://www.oscs1024.com/hd/MPS-2021-32354)|CVE-2021-41561|高危|
|H2数据库存在JNDI注入漏洞|反序列化|[MPS-2021-33243](https://www.oscs1024.com/hd/MPS-2021-33243)|CVE-2021-42392|严重|
|Oracle MySQL 的 MySQL Connectors 存在授权不当漏洞|授权机制不恰当|[MPS-2021-36587](https://www.oscs1024.com/hd/MPS-2021-36587)|CVE-2022-21363|中危|
|Apache Tomcat 条件竞争漏洞|竞争条件|[MPS-2021-37218](https://www.oscs1024.com/hd/MPS-2021-37218)|CVE-2021-43980|低危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|Jakarta Expression Language <=3.0.3 存在输入验证错误漏洞|表达式语言注入|[MPS-2021-7671](https://www.oscs1024.com/hd/MPS-2021-7671)|CVE-2021-28170|中危|
|JDOM 存在 XXE 注入漏洞|XXE|[MPS-2021-8350](https://www.oscs1024.com/hd/MPS-2021-8350)|CVE-2021-33813|高危|
|Apache Tomcat 环境问题漏洞|HTTP请求走私|[MPS-2021-9711](https://www.oscs1024.com/hd/MPS-2021-9711)|CVE-2021-33037|中危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9827](https://www.oscs1024.com/hd/MPS-2021-9827)|CVE-2021-36373|中危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9847](https://www.oscs1024.com/hd/MPS-2021-9847)|CVE-2021-36374|中危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|org.glassfish.jersey.media:jersey-media-jaxb <2.31 存在XXE漏洞|XML实体扩展|[MPS-2022-12234](https://www.oscs1024.com/hd/MPS-2022-12234)||高危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|Apache HttpClient URI解析错误漏洞|相对路径遍历|[MPS-2022-12292](https://www.oscs1024.com/hd/MPS-2022-12292)||中危|
|org.apache.hadoop:hadoop-hdfs < 3.3.2 存在XXE漏洞|XXE|[MPS-2022-12474](https://www.oscs1024.com/hd/MPS-2022-12474)||中危|
|org.json:json 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13520](https://www.oscs1024.com/hd/MPS-2022-13520)||高危|
|H2 Console 代码注入漏洞|代码注入|[MPS-2022-1435](https://www.oscs1024.com/hd/MPS-2022-1435)|CVE-2022-23221|严重|
|Apache XercesJ <=2.12.1 存在XML注入漏洞|XPath盲注|[MPS-2022-1864](https://www.oscs1024.com/hd/MPS-2022-1864)|CVE-2022-23437|中危|
|Apache Pulsar C++/Python 客户端存在中间人攻击漏洞|中间人攻击|[MPS-2022-18844](https://www.oscs1024.com/hd/MPS-2022-18844)|CVE-2022-33684|中危|
|JetBrains Kotlin <1.6.0 存在锁定不当漏洞|加锁机制不恰当|[MPS-2022-3233](https://www.oscs1024.com/hd/MPS-2022-3233)|CVE-2022-24329|中危|
|Netty 存在信息泄露漏洞||[MPS-2022-3790](https://www.oscs1024.com/hd/MPS-2022-3790)|CVE-2022-24823|中危|
|Apache Hadoop 存在shell命令注入漏洞|参数注入或修改|[MPS-2022-4190](https://www.oscs1024.com/hd/MPS-2022-4190)|CVE-2022-25168|严重|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|Apache Ivy <2.5.1 路径穿越漏洞|路径遍历|[MPS-2022-53784](https://www.oscs1024.com/hd/MPS-2022-53784)|CVE-2022-37865|中危|
|Apache Ivy <2.5.1 路径遍历漏洞|路径遍历|[MPS-2022-53785](https://www.oscs1024.com/hd/MPS-2022-53785)|CVE-2022-37866|中危|
|woodstox-core<5.3.0 存在XXE漏洞|XXE|[MPS-2022-54303](https://www.oscs1024.com/hd/MPS-2022-54303)||中危|
|Bouncy Castle <1.69 认证绕过漏洞|密码学问题|[MPS-2022-54305](https://www.oscs1024.com/hd/MPS-2022-54305)||中危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|Apache Calcite 存在 XXE 漏洞|XXE|[MPS-2022-56508](https://www.oscs1024.com/hd/MPS-2022-56508)|CVE-2022-39135|中危|
|XStream 缓冲区错误漏洞|输入验证不恰当|[MPS-2022-57061](https://www.oscs1024.com/hd/MPS-2022-57061)|CVE-2022-40156|低危|
|xstream project跨界内存写漏洞|跨界内存写|[MPS-2022-57062](https://www.oscs1024.com/hd/MPS-2022-57062)|CVE-2022-40155|高危|
|xstream project跨界内存写漏洞|跨界内存写|[MPS-2022-57063](https://www.oscs1024.com/hd/MPS-2022-57063)|CVE-2022-40154|高危|
|XStream 缓冲区错误漏洞|越界写入|[MPS-2022-57065](https://www.oscs1024.com/hd/MPS-2022-57065)|CVE-2022-40152|高危|
|Jettison <1.5.2 拒绝服务漏洞|拒绝服务|[MPS-2022-57067](https://www.oscs1024.com/hd/MPS-2022-57067)|CVE-2022-40150|高危|
|Jettison <1.5.1 拒绝服务漏洞|越界写入|[MPS-2022-57068](https://www.oscs1024.com/hd/MPS-2022-57068)|CVE-2022-40149|高危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|Netty <4.1.86.Final 存在 CRLF 注入漏洞||[MPS-2022-58552](https://www.oscs1024.com/hd/MPS-2022-58552)|CVE-2022-41915|中危|
|Apache Hadoop 存在路径遍历漏洞|路径遍历|[MPS-2022-5920](https://www.oscs1024.com/hd/MPS-2022-5920)|CVE-2022-26612|严重|
|Apache Commons Text <1.10.0 远程代码执行漏洞|反序列化|[MPS-2022-59712](https://www.oscs1024.com/hd/MPS-2022-59712)|CVE-2022-42889|严重|
|DataHub 数据伪造问题漏洞|密码学签名的验证不恰当|[MPS-2022-60876](https://www.oscs1024.com/hd/MPS-2022-60876)|CVE-2022-39366|严重|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|Jettison <1.5.2 拒绝服务漏洞|越界写入|[MPS-2022-64973](https://www.oscs1024.com/hd/MPS-2022-64973)|CVE-2022-45685|高危|
|H2 数据库明文密码问题|未授权敏感信息泄露|[MPS-2022-65204](https://www.oscs1024.com/hd/MPS-2022-65204)|CVE-2022-45868|高危|
|Apache Ivy<2.5.2 存在XXE漏洞|输入验证不恰当|[MPS-2022-67125](https://www.oscs1024.com/hd/MPS-2022-67125)|CVE-2022-46751|中危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Apache Kafka Connect 模块JNDI注入漏洞|反序列化|[MPS-2023-3834](https://www.oscs1024.com/hd/MPS-2023-3834)|CVE-2023-25194|高危|
|Eclipse Jetty 资源管理错误漏洞|拒绝服务|[MPS-2023-4997](https://www.oscs1024.com/hd/MPS-2023-4997)|CVE-2023-26048|中危|
|Eclipse Jetty 信息泄露漏洞|XSS|[MPS-2023-4998](https://www.oscs1024.com/hd/MPS-2023-4998)|CVE-2023-26049|中危|
|java-xmlbuilder 代码问题漏洞|XXE|[MPS-2023-5040](https://www.oscs1024.com/hd/MPS-2023-5040)|CVE-2014-125087|严重|
|Jettison 安全漏洞|未经控制的递归|[MPS-2023-8270](https://www.oscs1024.com/hd/MPS-2023-8270)|CVE-2023-1436|高危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|Apache Tomcat FORM 重定向漏洞|跨站重定向|[MPS-uy56-j8e4](https://www.oscs1024.com/hd/MPS-uy56-j8e4)|CVE-2023-41080|低危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.apache.tomcat.embed:tomcat-embed-core|8.5.46|11.0.0-m6|间接依赖|强烈建议修复|C:1|H:7|M:4|L:2|
|io.netty:netty-handler|4.1.77.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.apache.hive:hive-exec|2.3.1|3.1.3|直接依赖|建议修复|C:0|H:2|M:1|L:1|
|org.apache.zookeeper:zookeeper|3.4.6|3.5.5|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|io.netty:netty|3.7.0.Final|3.10.3.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|org.apache.commons:commons-text|1.9|1.10.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.apache.parquet:parquet-format-structures|1.11.1|1.12.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.kafka:kafka-clients|2.8.0|3.4.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.mybatis:mybatis|3.4.6|3.5.6|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.jamesmurty.utils:java-xmlbuilder|0.4|1.2|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|io.netty:netty|3.10.6.Final||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.commons:commons-compress|1.8.1|1.21|间接依赖|建议修复|C:0|H:4|M:1|L:0|
|com.squareup.okio:okio|1.6.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.h2database:h2|1.4.200|2.1.210|直接依赖|建议修复|C:3|H:1|M:0|L:0|
|org.apache.commons:commons-compress|1.19|1.21|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|mysql:mysql-connector-java|8.0.22|8.0.28|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.eclipse.jetty:jetty-server|9.4.48.v20220622|12.0.0.beta0|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.apache.hadoop:hadoop-common|2.10.1|3.3.3|直接依赖|建议修复|C:2|H:0|M:0|L:0|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13||间接依赖|建议修复|C:1|H:1|M:0|L:0|
|io.acryl:datahub-client|0.8.31|0.8.45|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.xerial.snappy:snappy-java|1.1.8.3|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|com.fasterxml.woodstox:woodstox-core|5.0.3|6.4.0|间接依赖|建议修复|C:0|H:3|M:1|L:1|
|com.google.oauth-client:google-oauth-client|1.33.1|1.33.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.45.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|org.apache.hive:hive-jdbc|2.3.1|2.3.3|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|io.netty:netty-codec|4.1.45.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|org.yaml:snakeyaml|1.30|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|org.yaml:snakeyaml|1.33|2.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.codehaus.jettison:jettison|1.1|1.5.4|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|org.glassfish.jersey.media:jersey-media-jaxb|2.17|2.31|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.14.2||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|xerces:xercesImpl|2.9.1|2.12.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-common|4.1.45.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|11.0.2|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|com.google.guava:guava|12.0.1|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:2|L:1|
|org.jetbrains.kotlin:kotlin-stdlib|1.5.32|1.6.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-httpclient:commons-httpclient|3.0.1|3.1-jenkins-2|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|31.1-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.pulsar:pulsar-client|2.8.1|2.10.2|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.calcite:calcite-core|1.10.0|1.32.0|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|commons-codec:commons-codec|1.11|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.bouncycastle:bcprov-jdk15on|1.67|1.69|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.glassfish:jakarta.el|3.0.3|3.0.4|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-codec:commons-codec|1.4|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.apache.ant:ant|1.9.1|1.10.11|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|com.google.code.gson:gson|2.2.4|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-core|5.3.22|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.ivy:ivy|2.4.0|2.5.2|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|commons-codec:commons-codec|1.9|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|commons-io:commons-io|2.4|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|5.3.22|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.guava:guava|16.0.1|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|com.google.code.gson:gson|2.6.2|2.8.9|直接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.jdom:jdom|1.1||间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.bouncycastle:bcprov-jdk15on|1.69||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.httpcomponents:httpclient|4.4.1|4.5.13|直接依赖|可选修复|C:0|H:0|M:2|L:0|
|io.netty:netty-codec-http|4.1.77.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.7.3|3.0.7|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|io.netty:netty-transport-native-epoll|4.1.45.Final|4.1.59.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-net:commons-net|3.1|3.9.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.json:json|20170516|20180130|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.hadoop:hadoop-hdfs|2.10.1|3.3.2|直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|462|Low|
|CDDL-1.1|9|Low|
|EPL-2.0|26|Low|
|BSD-3-Clause|7|Low|
|自定义许可证|71|Low|
|EPL-1.0|2|Low|
|MIT|10|Low|
|LGPL-2.1-or-later|1|Low|
|LGPL-2.1|6|Medium|
|BSD-2-Clause|2|Low|
|MPL-2.0|1|Low|
|GPL-2.0|1|Medium|
|MPL-1.1|1|Low|
|JSON|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|io.grpc:grpc-core|1.47.0|间接依赖|maven|
|org.apache.parquet:parquet-encoding|1.12.3|间接依赖|maven|
|org.apache.thrift:libthrift|0.12.0|直接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|间接依赖|maven|
|com.twitter:bijection-avro_2.12|0.9.3|直接依赖|maven|
|org.apache.parquet:parquet-common|1.12.3|间接依赖|maven|
|org.apache.commons:commons-text|1.9|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.14.2|直接依赖|maven|
|io.netty:netty-resolver|4.1.77.Final|间接依赖|maven|
|org.apache.avro:avro-mapred|1.7.7|直接依赖|maven|
|org.apache.calcite:calcite-druid|1.10.0|间接依赖|maven|
|org.apache.thrift:libfb303|0.9.3|直接依赖|maven|
|org.apache.parquet:parquet-common|1.12.2|直接依赖|maven|
|org.apache.parquet:parquet-jackson|1.12.3|间接依赖|maven|
|org.eclipse.jetty:jetty-xml|9.4.48.v20220622|间接依赖|maven|
|org.apache.hudi:hudi-spark3-common|1.0.0-SNAPSHOT|直接依赖|maven|
|org.apache.calcite.avatica:avatica-metrics|1.8.0|间接依赖|maven|
|io.grpc:grpc-alts|1.45.0|间接依赖|maven|
|com.esotericsoftware:kryo-shaded|4.0.2|直接依赖|maven|
|com.google.re2j:re2j|1.5|间接依赖|maven|
|org.apache.hbase:hbase-protocol-shaded|2.4.9|间接依赖|maven|
|io.grpc:grpc-protobuf|1.47.0|间接依赖|maven|
|org.apache.hbase:hbase-zookeeper|2.4.9|间接依赖|maven|
|org.apache.calcite:calcite-core|1.10.0|间接依赖|maven|
|io.prometheus:simpleclient_dropwizard|0.8.0|直接依赖|maven|
|org.lz4:lz4-java|1.8.0|直接依赖|maven|
|javax.servlet.jsp:jsp-api|2.1|间接依赖|maven|
|org.junit.platform:junit-platform-suite-api|1.7.2|直接依赖|maven|
|io.grpc:grpc-xds|1.47.0|间接依赖|maven|
|org.apache.parquet:parquet-encoding|1.12.2|直接依赖|maven|
|com.google.guava:guava|16.0.1|间接依赖|maven|
|org.apache.commons:commons-lang3|3.3.2|间接依赖|maven|
|com.google.apis:google-api-services-iamcredentials|v1-rev20210326-1.32.1|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.45.Final|间接依赖|maven|
|com.google.cloud:google-cloud-core-grpc|1.82.0|间接依赖|maven|
|org.apache.ant:ant-launcher|1.9.1|间接依赖|maven|
|org.apache.hudi:hudi-aws|1.0.0-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.14.2|直接依赖|maven|
|org.springframework.shell:spring-shell-autoconfigure|2.1.1|间接依赖|maven|
|com.google.api:gax-httpjson|0.98.0|间接依赖|maven|
|com.google.auto.value:auto-value-annotations|1.9|间接依赖|maven|
|org.codehaus.janino:janino|2.7.6|间接依赖|maven|
|org.jline:jline-terminal|3.21.0|间接依赖|maven|
|org.apache.hbase:hbase-http|2.4.9|间接依赖|maven|
|software.amazon.awssdk:cloudwatch|2.18.40|直接依赖|maven|
|org.apache.parquet:parquet-hadoop|1.12.3|直接依赖|maven|
|org.apache.commons:commons-math3|3.1.1|间接依赖|maven|
|io.netty:netty-handler|4.1.45.Final|间接依赖|maven|
|org.apache.parquet:parquet-jackson|1.10.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.3|间接依赖|maven|
|org.apache.parquet:parquet-column|1.10.1|间接依赖|maven|
|org.mortbay.jetty:jetty|6.1.26|间接依赖|maven|
|commons-lang:commons-lang|2.6|直接依赖|maven|
|org.slf4j:jul-to-slf4j|2.0.6|直接依赖|maven|
|org.glassfish.jersey.bundles.repackaged:jersey-guava|2.17|间接依赖|maven|
|software.amazon.awssdk:profiles|2.18.40|间接依赖|maven|
|com.jcraft:jsch|0.1.55|间接依赖|maven|
|io.perfmark:perfmark-api|0.25.0|间接依赖|maven|
|org.apache.avro:avro|1.8.2|直接依赖|maven|
|org.json4s:json4s-ast_2.12|3.7.0-M11|间接依赖|maven|
|org.apache.htrace:htrace-core|3.1.0-incubating|直接依赖|maven|
|org.apache.hive:hive-llap-tez|2.3.1|间接依赖|maven|
|org.eclipse.jetty:jetty-http|9.4.48.v20220622|直接依赖|maven|
|io.grpc:grpc-auth|1.47.0|间接依赖|maven|
|org.apache.hive:hive-vector-code-gen|2.3.1|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.1.Final|间接依赖|maven|
|org.jline:jline|3.21.0|间接依赖|maven|
|org.roaringbitmap:shims|0.9.47|间接依赖|maven|
|joda-time:joda-time|2.9.9|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.14.2|直接依赖|maven|
|com.github.davidmoten:hilbert-curve|0.2.2|直接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|com.google.guava:guava|31.1-jre|间接依赖|maven|
|software.amazon.awssdk:aws-core|2.18.40|直接依赖|maven|
|org.scalactic:scalactic_2.12|3.1.0|直接依赖|maven|
|com.twitter:bijection-avro_2.12|0.9.7|直接依赖|maven|
|com.google.api-client:google-api-client-jackson2|1.32.2|间接依赖|maven|
|net.java.dev.jna:jna|5.9.0|间接依赖|maven|
|org.apache.hudi:hudi-sync-common|1.0.0-SNAPSHOT|直接依赖|maven|
|org.apache.curator:curator-client|2.7.1|直接依赖|maven|
|org.apache.pulsar:pulsar-client-api|2.8.1|间接依赖|maven|
|commons-codec:commons-codec|1.4|间接依赖|maven|
|org.codehaus.jackson:jackson-xc|1.8.3|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-servlet|9.4.48.v20220622|间接依赖|maven|
|software.amazon.awssdk:third-party-jackson-core|2.18.40|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|io.dropwizard.metrics:metrics-json|3.1.0|间接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|io.grpc:grpc-services|1.47.0|间接依赖|maven|
|io.opencensus:opencensus-contrib-http-util|0.31.0|间接依赖|maven|
|org.apache.spark:spark-streaming_2.12|3.4.1|直接依赖|maven|
|org.apache.hudi:hudi-spark-common_2.12|1.0.0-SNAPSHOT|直接依赖|maven|
|com.google.http-client:google-http-client-apache-v2|1.41.5|间接依赖|maven|
|software.amazon.awssdk:glue|2.18.40|直接依赖|maven|
|org.eclipse.jetty:jetty-client|9.4.48.v20220622|间接依赖|maven|
|org.apache.commons:commons-compress|1.8.1|间接依赖|maven|
|org.objenesis:objenesis|2.6|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-params|5.7.2|直接依赖|maven|
|com.google.api.grpc:proto-google-iam-v1|1.2.10|间接依赖|maven|
|org.apache.hudi:hudi-cli|1.0.0-SNAPSHOT|直接依赖|maven|
|io.opencensus:opencensus-api|0.31.0|间接依赖|maven|
|io.netty:netty-transport|4.1.77.Final|间接依赖|maven|
|javax.ws.rs:javax.ws.rs-api|2.1.1|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.1|直接依赖|maven|
|net.hydromatic:eigenbase-properties|1.1.5|间接依赖|maven|
|javax.servlet:javax.servlet-api|3.1.0|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|8.5.46|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.21|间接依赖|maven|
|org.springframework.shell:spring-shell-starter|2.1.1|直接依赖|maven|
|org.apache.htrace:htrace-core4|4.1.0-incubating|间接依赖|maven|
|com.google.inject.extensions:guice-servlet|3.0|间接依赖|maven|
|org.apache.hbase:hbase-hadoop2-compat|2.4.9|间接依赖|maven|
|com.google.http-client:google-http-client-jackson2|1.41.5|间接依赖|maven|
|org.springframework.shell:spring-shell-core|2.1.1|间接依赖|maven|
|org.glassfish.hk2.external:javax.inject|2.4.0-b10|间接依赖|maven|
|org.apache.hudi:hudi-examples-common|1.0.0-SNAPSHOT|直接依赖|maven|
|org.glassfish.jersey.core:jersey-server|2.17|直接依赖|maven|
|org.objenesis:objenesis|2.1|间接依赖|maven|
|software.amazon.awssdk:utils|2.18.40|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.2.4.Final|间接依赖|maven|
|org.apache.hudi:hudi-gcp|1.0.0-SNAPSHOT|直接依赖|maven|
|io.netty:netty-transport|4.1.45.Final|间接依赖|maven|
|org.apache.parquet:parquet-common|1.10.1|间接依赖|maven|
|com.google.api:gax|2.13.0|间接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|io.grpc:grpc-netty-shaded|1.45.0|间接依赖|maven|
|org.json4s:json4s-jackson_2.12|3.7.0-M11|直接依赖|maven|
|software.amazon.awssdk:auth|2.18.40|直接依赖|maven|
|io.opencensus:opencensus-exporter-metrics-util|0.31.0|间接依赖|maven|
|com.google.cloud:google-cloud-core-http|2.5.11|间接依赖|maven|
|org.apache.commons:commons-lang3|3.4|间接依赖|maven|
|org.apache.hudi:hudi-spark3.4.x_2.12|1.0.0-SNAPSHOT|直接依赖|maven|
|jakarta.ws.rs:jakarta.ws.rs-api|2.1.6|间接依赖|maven|
|io.prometheus:simpleclient_pushgateway|0.8.0|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|2.10.1|间接依赖|maven|
|com.github.spotbugs:spotbugs-annotations|3.1.9|间接依赖|maven|
|com.tdunning:json|1.8|间接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.4.48.v20220622|间接依赖|maven|
|org.antlr:ST4|4.0.4|间接依赖|maven|
|com.google.http-client:google-http-client-gson|1.41.5|间接依赖|maven|
|org.apache.flink:flink-clients_2.12|1.13.6|直接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|org.apache.kafka:kafka-clients|2.8.0|直接依赖|maven|
|org.apache.hbase.thirdparty:hbase-shaded-netty|3.5.1|间接依赖|maven|
|io.dropwizard.metrics:metrics-jvm|3.1.0|间接依赖|maven|
|org.apache.hbase:hbase-metrics-api|2.4.9|间接依赖|maven|
|software.amazon.awssdk:aws-query-protocol|2.18.40|间接依赖|maven|
|org.checkerframework:checker-qual|3.21.3|间接依赖|maven|
|org.threeten:threeten-extra|1.7.0|间接依赖|maven|
|io.netty:netty-codec|4.1.45.Final|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|com.google.api.grpc:proto-google-cloud-pubsub-v1|1.102.0|间接依赖|maven|
|com.sun.jersey:jersey-server|1.9|间接依赖|maven|
|com.google.api.grpc:proto-google-cloud-monitoring-v3|3.2.6|间接依赖|maven|
|io.grpc:grpc-grpclb|1.45.0|间接依赖|maven|
|org.scala-lang.modules:scala-collection-compat_2.12|2.8.1|直接依赖|maven|
|org.codehaus.groovy:groovy-all|2.4.4|间接依赖|maven|
|com.google.api:api-common|2.1.5|间接依赖|maven|
|io.confluent:common-config|5.3.4|直接依赖|maven|
|org.apache.pulsar:pulsar-client-admin-api|2.8.1|间接依赖|maven|
|org.json4s:json4s-core_2.12|3.7.0-M11|间接依赖|maven|
|org.tukaani:xz|1.5|间接依赖|maven|
|io.opencensus:opencensus-contrib-exemplar-util|0.31.0|间接依赖|maven|
|com.sun.jersey:jersey-client|1.9|间接依赖|maven|
|com.google.cloud:google-cloud-monitoring|1.82.0|间接依赖|maven|
|org.apache.parquet:parquet-hadoop|1.11.1|直接依赖|maven|
|org.apache.curator:curator-recipes|2.7.1|直接依赖|maven|
|org.apache.hudi:hudi-spark3.2plus-common|1.0.0-SNAPSHOT|直接依赖|maven|
|org.threeten:threeten-extra|1.7.1|间接依赖|maven|
|com.google.oauth-client:google-oauth-client|1.33.1|间接依赖|maven|
|org.springframework:spring-expression|5.3.22|间接依赖|maven|
|org.junit.platform:junit-platform-launcher|1.7.2|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-client|9.4.48.v20220622|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-validation|2.7.3|直接依赖|maven|
|org.apache.yetus:audience-annotations|0.13.0|间接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.67|间接依赖|maven|
|org.apache.spark:spark-token-provider-kafka-0-10_2.12|3.4.1|间接依赖|maven|
|org.apache.flink:flink-metrics-dropwizard|1.13.6|直接依赖|maven|
|org.fusesource.leveldbjni:leveldbjni-all|1.8|间接依赖|maven|
|com.google.guava:guava|11.0.2|间接依赖|maven|
|org.apache.parquet:parquet-avro|1.12.2|直接依赖|maven|
|org.jetbrains:annotations|17.0.0|间接依赖|maven|
|org.glassfish.jersey.core:jersey-common|2.17|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.11.0|间接依赖|maven|
|org.apache.ant:ant|1.9.1|间接依赖|maven|
|software.amazon.awssdk:dynamodb|2.18.40|直接依赖|maven|
|org.apache.parquet:parquet-format-structures|1.11.1|间接依赖|maven|
|io.netty:netty-all|4.1.50.Final|间接依赖|maven|
|org.codehaus.woodstox:stax2-api|3.1.4|间接依赖|maven|
|com.google.auth:google-auth-library-oauth2-http|1.6.0|间接依赖|maven|
|org.apache.pulsar:bouncy-castle-bc|2.8.1|间接依赖|maven|
|org.glassfish.hk2:hk2-locator|2.4.0-b10|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-ram|3.0.0|间接依赖|maven|
|org.hamcrest:hamcrest-core|1.3|间接依赖|maven|
|org.mybatis:mybatis|3.4.6|直接依赖|maven|
|jakarta.el:jakarta.el-api|3.0.3|直接依赖|maven|
|io.netty:netty-resolver|4.1.45.Final|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.5.32|间接依赖|maven|
|org.apache.parquet:parquet-avro|1.12.3|直接依赖|maven|
|javax.ws.rs:javax.ws.rs-api|2.0.1|间接依赖|maven|
|xmlenc:xmlenc|0.52|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.0-1|间接依赖|maven|
|io.grpc:grpc-googleapis|1.47.0|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|2.10.1|间接依赖|maven|
|io.prometheus:simpleclient_common|0.8.0|间接依赖|maven|
|software.amazon.awssdk:annotations|2.18.40|直接依赖|maven|
|io.dropwizard.metrics:metrics-core|4.1.1|直接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.5|直接依赖|maven|
|org.scalatest:scalatest-compatible|3.1.0|间接依赖|maven|
|io.netty:netty-buffer|4.1.77.Final|间接依赖|maven|
|org.apache.hadoop:hadoop-hdfs|2.10.1|直接依赖|maven|
|org.apache.hbase.thirdparty:hbase-shaded-jetty|3.5.1|间接依赖|maven|
|io.grpc:grpc-auth|1.45.0|间接依赖|maven|
|org.apache.flink:flink-json|1.13.6|直接依赖|maven|
|org.apache.zookeeper:zookeeper-jute|3.5.7|间接依赖|maven|
|io.grpc:grpc-stub|1.45.0|间接依赖|maven|
|org.apache.hudi:hudi-flink|1.0.0-SNAPSHOT|直接依赖|maven|
|org.apache.hadoop:hadoop-distcp|2.10.0|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.10.5|间接依赖|maven|
|com.google.http-client:google-http-client-appengine|1.41.5|间接依赖|maven|
|org.apache.parquet:parquet-jackson|1.12.2|直接依赖|maven|
|org.eclipse.jetty.websocket:websocket-common|9.4.48.v20220622|间接依赖|maven|
|org.springframework.boot:spring-boot|2.7.3|间接依赖|maven|
|software.amazon.awssdk:sdk-core|2.18.40|直接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.69|间接依赖|maven|
|com.google.api.grpc:grpc-google-cloud-storage-v2|2.2.2-alpha|间接依赖|maven|
|org.eclipse.jetty:jetty-webapp|9.4.48.v20220622|直接依赖|maven|
|org.apache.flink:flink-annotations|1.13.6|间接依赖|maven|
|io.prometheus:simpleclient|0.8.0|直接依赖|maven|
|org.apache.parquet:parquet-jackson|1.11.1|间接依赖|maven|
|com.google.auth:google-auth-library-credentials|1.6.0|间接依赖|maven|
|org.apache.commons:commons-compress|1.19|间接依赖|maven|
|xerces:xercesImpl|2.9.1|间接依赖|maven|
|io.acryl:datahub-client|0.8.31|直接依赖|maven|
|org.apache.commons:commons-crypto|1.0.0|间接依赖|maven|
|org.apache.flink:flink-metrics-core|1.13.6|间接依赖|maven|
|io.opencensus:opencensus-exporter-stats-stackdriver|0.31.0|间接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.47.0|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|org.apache.hudi:hudi-timeline-service|1.0.0-SNAPSHOT|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.65|间接依赖|maven|
|io.trino:trino-jdbc|390|直接依赖|maven|
|org.json4s:json4s-scalap_2.12|3.7.0-M11|间接依赖|maven|
|com.google.api.grpc:proto-google-cloud-monitoring-v3|1.64.0|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|间接依赖|maven|
|com.google.flogger:flogger-system-backend|0.7.1|间接依赖|maven|
|org.scala-lang:scala-reflect|2.12.10|间接依赖|maven|
|io.opencensus:opencensus-impl|0.31.0|间接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|直接依赖|maven|
|com.google.code.gson:gson|2.8.9|间接依赖|maven|
|org.springframework:spring-jcl|5.3.22|间接依赖|maven|
|org.apache.ivy:ivy|2.4.0|间接依赖|maven|
|org.glassfish.jersey.connectors:jersey-apache-connector|2.17|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-csv|2.14.2|直接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.45.0|间接依赖|maven|
|com.google.api:gax-grpc|2.18.2|间接依赖|maven|
|org.mockito:mockito-core|3.3.3|间接依赖|maven|
|io.netty:netty|3.10.6.Final|间接依赖|maven|
|org.apache.commons:commons-compress|1.21|间接依赖|maven|
|commons-logging:commons-logging|1.1.3|间接依赖|maven|
|org.glassfish.hk2.external:aopalliance-repackaged|2.4.0-b10|间接依赖|maven|
|org.apache.hive:hive-storage-api|2.8.1|间接依赖|maven|
|commons-dbcp:commons-dbcp|1.4|直接依赖|maven|
|stax:stax-api|1.0.1|间接依赖|maven|
|com.esotericsoftware.kryo:kryo|2.24.0|间接依赖|maven|
|org.apache.hive:hive-jdbc|2.3.1|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-client|2.10.1|间接依赖|maven|
|com.h2database:h2|1.4.200|直接依赖|maven|
|org.apache.flink:flink-optimizer_2.12|1.13.6|间接依赖|maven|
|com.google.cloud.bigdataoss:util|2.2.7|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.5.32|间接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|org.apache.flink:flink-connector-kafka_2.12|1.13.6|直接依赖|maven|
|org.bouncycastle:bcprov-ext-jdk15on|1.69|间接依赖|maven|
|org.apache.hbase:hbase-hadoop-compat|2.4.9|间接依赖|maven|
|commons-codec:commons-codec|1.13|直接依赖|maven|
|software.amazon.awssdk:regions|2.18.40|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.4.1|直接依赖|maven|
|commons-daemon:commons-daemon|1.0.13|间接依赖|maven|
|com.google.guava:guava|12.0.1|直接依赖|maven|
|org.junit.platform:junit-platform-runner|1.7.2|直接依赖|maven|
|com.sun.activation:javax.activation|1.2.0|间接依赖|maven|
|org.apache.hudi:hudi-hive-sync|1.0.0-SNAPSHOT|直接依赖|maven|
|org.scala-lang:scala-library|2.12.17|直接依赖|maven|
|org.apache.hudi:hudi-utilities-bundle_2.12|1.0.0-SNAPSHOT|直接依赖|maven|
|mysql:mysql-connector-java|8.0.28|直接依赖|maven|
|io.netty:netty-codec-http2|4.1.77.Final|间接依赖|maven|
|org.apache.hive:hive-llap-common|2.3.1|间接依赖|maven|
|junit:junit|4.13.2|直接依赖|maven|
|io.netty:netty-buffer|4.1.45.Final|间接依赖|maven|
|org.apache.hadoop:hadoop-hdfs-client|2.10.1|直接依赖|maven|
|org.apache.parquet:parquet-column|1.12.2|直接依赖|maven|
|com.github.davidmoten:guava-mini|0.1.3|间接依赖|maven|
|software.amazon.awssdk:metrics-spi|2.18.40|间接依赖|maven|
|io.grpc:grpc-services|1.45.0|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|org.apache.hbase.thirdparty:hbase-shaded-miscellaneous|3.5.1|间接依赖|maven|
|net.jcip:jcip-annotations|1.0|间接依赖|maven|
|org.jamon:jamon-runtime|2.4.1|间接依赖|maven|
|org.apache.curator:curator-framework|2.7.1|直接依赖|maven|
|software.amazon.awssdk:http-client-spi|2.18.40|直接依赖|maven|
|org.apache.calcite.avatica:avatica|1.8.0|间接依赖|maven|
|org.codehaus.janino:commons-compiler|2.7.6|间接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|2.8.0|间接依赖|maven|
|org.apache.hudi:hudi-integ-test|1.0.0-SNAPSHOT|直接依赖|maven|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.5.1|间接依赖|maven|
|com.google.cloud.bigdataoss:util-hadoop|hadoop2-2.2.7|间接依赖|maven|
|org.apache.pulsar:pulsar-client|2.8.1|直接依赖|maven|
|io.netty:netty|3.7.0.Final|间接依赖|maven|
|software.amazon.eventstream:eventstream|1.0.1|间接依赖|maven|
|com.jamesmurty.utils:java-xmlbuilder|0.4|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-server|9.4.48.v20220622|间接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.69|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|2.10.0|间接依赖|maven|
|io.netty:netty-common|4.1.45.Final|间接依赖|maven|
|org.apache.flink:flink-connector-base|1.13.6|间接依赖|maven|
|org.rocksdb:rocksdbjni|6.29.4.1|直接依赖|maven|
|com.google.cloud:google-cloud-monitoring|3.2.6|间接依赖|maven|
|com.google.api.grpc:proto-google-cloud-pubsub-v1|1.98.3|间接依赖|maven|
|io.javalin:javalin|4.6.7|直接依赖|maven|
|io.grpc:grpc-grpclb|1.47.0|间接依赖|maven|
|org.glassfish.hk2:hk2-api|2.4.0-b10|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-api|5.7.2|直接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.77.Final|间接依赖|maven|
|com.google.cloud:google-cloud-core|2.5.11|间接依赖|maven|
|org.apache.parquet:parquet-hadoop|1.10.1|间接依赖|maven|
|io.grpc:grpc-context|1.45.0|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.21.7|直接依赖|maven|
|junit:junit|3.8.1|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.4.14|间接依赖|maven|
|com.google.cloud:google-cloud-pubsub|1.116.3|间接依赖|maven|
|com.sun.jersey:jersey-core|1.9|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|jline:jline|2.12|间接依赖|maven|
|org.bouncycastle:bcutil-jdk15on|1.69|间接依赖|maven|
|software.amazon.awssdk:endpoints-spi|2.18.40|间接依赖|maven|
|org.apache.hadoop:hadoop-aliyun|3.2.1|直接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.19.0|直接依赖|maven|
|org.apache.calcite:calcite-linq4j|1.10.0|间接依赖|maven|
|com.google.cloud:google-cloud-bigquery|2.10.4|直接依赖|maven|
|com.google.inject:guice|3.0|间接依赖|maven|
|com.google.api-client:google-api-client|1.33.4|间接依赖|maven|
|org.apache.hudi:hudi-spark-client|1.0.0-SNAPSHOT|直接依赖|maven|
|org.junit.jupiter:junit-jupiter-engine|5.7.2|直接依赖|maven|
|commons-net:commons-net|3.1|间接依赖|maven|
|org.glassfish:jakarta.el|3.0.3|直接依赖|maven|
|net.bytebuddy:byte-buddy-agent|1.10.5|间接依赖|maven|
|org.apache.hudi:hudi-flink1.13.x|1.0.0-SNAPSHOT|直接依赖|maven|
|com.github.joshelser:dropwizard-metrics-hadoop-metrics2-reporter|0.1.2|间接依赖|maven|
|com.google.apis:google-api-services-bigquery|v2-rev20220313-1.32.1|间接依赖|maven|
|software.amazon.awssdk:apache-client|2.18.40|间接依赖|maven|
|org.apache.parquet:parquet-format-structures|1.12.3|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|org.springframework:spring-messaging|5.3.22|间接依赖|maven|
|io.grpc:grpc-api|1.43.2|间接依赖|maven|
|org.springframework:spring-aop|5.3.22|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.3|间接依赖|maven|
|org.apache.parquet:parquet-avro|1.10.1|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|2.10.1|间接依赖|maven|
|org.codehaus.jackson:jackson-jaxrs|1.8.3|间接依赖|maven|
|org.apiguardian:apiguardian-api|1.1.0|间接依赖|maven|
|commons-pool:commons-pool|1.4|直接依赖|maven|
|org.eclipse.jetty.websocket:websocket-api|9.4.48.v20220622|间接依赖|maven|
|io.grpc:grpc-core|1.45.0|间接依赖|maven|
|org.apache.hudi:hudi-java-client|1.0.0-SNAPSHOT|直接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.9.13|间接依赖|maven|
|com.google.protobuf:protobuf-java-util|3.21.7|直接依赖|maven|
|org.glassfish.jersey.media:jersey-media-jaxb|2.17|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-core|3.7.1|直接依赖|maven|
|io.grpc:grpc-netty-shaded|1.47.0|间接依赖|maven|
|org.glassfish.web:javax.servlet.jsp|2.3.2|间接依赖|maven|
|org.apache.hudi:hudi-common|1.0.0-SNAPSHOT|直接依赖|maven|
|com.aliyun:aliyun-java-sdk-sts|3.0.0|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.77.Final|间接依赖|maven|
|com.esotericsoftware:minlog|1.3.0|间接依赖|maven|
|org.apache.hudi:hudi-metaserver-server|1.0.0-SNAPSHOT|直接依赖|maven|
|org.springframework.shell:spring-shell-standard|2.1.1|间接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.1|直接依赖|maven|
|com.esotericsoftware.minlog:minlog|1.2|间接依赖|maven|
|com.aliyun.oss:aliyun-sdk-oss|3.1.0|直接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.9.1|直接依赖|maven|
|io.airlift:aircompressor|0.21|间接依赖|maven|
|org.apache.hudi:hudi-flink-client|1.0.0-SNAPSHOT|直接依赖|maven|
|org.scala-lang.modules:scala-xml_2.12|1.2.0|间接依赖|maven|
|org.antlr:stringtemplate|4.0.2|直接依赖|maven|
|org.apache.orc:orc-shims|1.8.3|间接依赖|maven|
|org.antlr:ST4|4.3.1|间接依赖|maven|
|org.apache.flink:flink-parquet_2.12|1.13.6|直接依赖|maven|
|io.opencensus:opencensus-contrib-grpc-metrics|0.31.0|间接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.48.v20220622|间接依赖|maven|
|commons-io:commons-io|2.11.0|直接依赖|maven|
|org.apache.hive:hive-llap-client|2.3.1|间接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|5.0.3|间接依赖|maven|
|commons-configuration:commons-configuration|1.6|间接依赖|maven|
|io.grpc:grpc-xds|1.45.0|间接依赖|maven|
|javax.servlet.jsp:javax.servlet.jsp-api|2.3.1|间接依赖|maven|
|com.google.flogger:flogger|0.7.1|间接依赖|maven|
|jline:jline|0.9.94|间接依赖|maven|
|org.mockito:mockito-junit-jupiter|3.3.3|直接依赖|maven|
|org.conscrypt:conscrypt-openjdk-uber|2.5.1|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|直接依赖|maven|
|org.apache.logging.log4j:log4j-1.2-api|2.19.0|直接依赖|maven|
|software.amazon.awssdk:json-utils|2.18.40|间接依赖|maven|
|com.google.code.gson:gson|2.2.4|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-ecs|4.2.0|间接依赖|maven|
|com.google.code.gson:gson|2.6.2|直接依赖|maven|
|org.springframework:spring-core|5.3.22|间接依赖|maven|
|org.apache.tomcat:tomcat-annotations-api|8.5.46|间接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.8|间接依赖|maven|
|org.apache.parquet:parquet-hadoop|1.12.2|直接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|commons-pool:commons-pool|1.6|间接依赖|maven|
|com.twitter:bijection-core_2.12|0.9.7|间接依赖|maven|
|org.apache.commons:commons-configuration2|2.8.0|直接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j-impl|2.19.0|直接依赖|maven|
|org.apache.avro:avro-ipc|1.7.7|间接依赖|maven|
|com.github.luben:zstd-jni|1.4.9-1|间接依赖|maven|
|joda-time:joda-time|2.5|直接依赖|maven|
|org.apache.httpcomponents:fluent-hc|4.4.1|直接依赖|maven|
|org.apache.flink:flink-shaded-guava|18.0-13.0|间接依赖|maven|
|org.apache.hudi:hudi-hadoop-sparkworker-docker|1.0.0-SNAPSHOT|直接依赖|maven|
|org.apache.zookeeper:zookeeper|3.4.6|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-scala_2.12|2.14.2|直接依赖|maven|
|org.junit.vintage:junit-vintage-engine|5.7.2|直接依赖|maven|
|org.awaitility:awaitility|3.1.2|直接依赖|maven|
|commons-codec:commons-codec|1.9|间接依赖|maven|
|com.google.code.gson:gson|2.9.0|间接依赖|maven|
|org.codehaus.jackson:jackson-jaxrs|1.9.13|间接依赖|maven|
|org.mortbay.jetty:jetty-util|6.1.26|间接依赖|maven|
|org.glassfish.hk2:osgi-resource-locator|1.0.1|间接依赖|maven|
|org.eclipse.jetty:jetty-security|9.4.48.v20220622|间接依赖|maven|
|org.opentest4j:opentest4j|1.2.0|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.2|间接依赖|maven|
|io.netty:netty-handler|4.1.77.Final|间接依赖|maven|
|org.apache.parquet:parquet-encoding|1.10.1|间接依赖|maven|
|com.google.api:gax-grpc|2.13.0|间接依赖|maven|
|io.netty:netty-codec|4.1.77.Final|间接依赖|maven|
|com.google.code.findbugs:jsr305|1.3.9|间接依赖|maven|
|io.netty:netty-codec-http|4.1.77.Final|间接依赖|maven|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|org.apache.flink:force-shading|1.13.6|间接依赖|maven|
|com.google.cloud.bigdataoss:gcsio|2.2.7|间接依赖|maven|
|com.twitter:bijection-core_2.12|0.9.3|间接依赖|maven|
|io.confluent:common-utils|5.3.4|直接依赖|maven|
|commons-codec:commons-codec|1.11|间接依赖|maven|
|org.apache.flink:flink-java|1.13.6|间接依赖|maven|
|org.yaml:snakeyaml|1.30|间接依赖|maven|
|org.apache.hbase:hbase-common|2.4.9|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.14.2|直接依赖|maven|
|javax.servlet:servlet-api|2.5|间接依赖|maven|
|org.apache.flink:flink-hadoop-compatibility_2.12|1.13.6|直接依赖|maven|
|org.apache.hudi:hudi-spark3.4-bundle_2.12|1.0.0-SNAPSHOT|直接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.45.Final|间接依赖|maven|
|org.apache.hive:hive-exec|2.3.1|直接依赖|maven|
|io.opencensus:opencensus-impl-core|0.31.0|间接依赖|maven|
|org.springframework:spring-beans|5.3.22|间接依赖|maven|
|org.apache.spark:spark-streaming-kafka-0-10_2.12|3.4.1|直接依赖|maven|
|org.apache.commons:commons-math3|3.5|间接依赖|maven|
|net.java.dev.jets3t:jets3t|0.9.0|间接依赖|maven|
|org.apache.hudi:hudi-spark_2.12|1.0.0-SNAPSHOT|直接依赖|maven|
|org.apache.flink:flink-file-sink-common|1.13.6|间接依赖|maven|
|com.beust:jcommander|1.78|直接依赖|maven|
|io.grpc:grpc-census|1.43.2|间接依赖|maven|
|org.apache.hive:hive-storage-api|2.3.1|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.48.v20220622|直接依赖|maven|
|org.apache.commons:commons-math3|3.6.1|间接依赖|maven|
|org.yaml:snakeyaml|1.33|间接依赖|maven|
|org.apache.hive:hive-common|2.3.1|直接依赖|maven|
|org.glassfish.hk2.external:jakarta.inject|2.6.1|间接依赖|maven|
|org.codehaus.jackson:jackson-xc|1.9.13|间接依赖|maven|
|org.apache.hbase:hbase-protocol|2.4.9|间接依赖|maven|
|org.hamcrest:hamcrest-library|1.3|间接依赖|maven|
|org.eclipse.jetty.orbit:javax.servlet|3.0.0.v201112011016|间接依赖|maven|
|io.dropwizard.metrics:metrics-jmx|4.1.1|直接依赖|maven|
|org.apache.avro:avro|1.11.1|直接依赖|maven|
|javax.ws.rs:javax.ws.rs-api|2.1|间接依赖|maven|
|software.amazon.awssdk:netty-nio-client|2.18.40|间接依赖|maven|
|org.apache.flink:flink-streaming-java_2.12|1.13.6|直接依赖|maven|
|org.apache.zookeeper:zookeeper|3.5.7|间接依赖|maven|
|org.antlr:antlr-runtime|3.5.2|间接依赖|maven|
|org.threeten:threetenbp|1.6.0|间接依赖|maven|
|commons-digester:commons-digester|1.8|间接依赖|maven|
|com.101tec:zkclient|0.10|间接依赖|maven|
|org.apache.parquet:parquet-format|2.4.0|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|org.apache.parquet:parquet-format-structures|1.12.2|直接依赖|maven|
|org.apache.hbase:hbase-metrics|2.4.9|间接依赖|maven|
|org.apache.hudi:hudi-metaserver-client|1.0.0-SNAPSHOT|直接依赖|maven|
|org.springframework.shell:spring-shell-standard-commands|2.1.1|间接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.7|间接依赖|maven|
|io.grpc:grpc-alts|1.47.0|间接依赖|maven|
|org.apache.hive:hive-service-rpc|2.3.1|间接依赖|maven|
|org.apache.thrift:libthrift|0.14.0|直接依赖|maven|
|org.apache.hbase.thirdparty:hbase-shaded-protobuf|3.5.1|间接依赖|maven|
|org.mortbay.jetty:servlet-api|2.5-20081211|间接依赖|maven|
|org.scala-lang:scala-library|2.12.10|间接依赖|maven|
|org.apache.yetus:audience-annotations|0.5.0|间接依赖|maven|
|org.eclipse.jetty:jetty-server|9.4.48.v20220622|直接依赖|maven|
|org.apache.flink:flink-core|1.13.6|直接依赖|maven|
|com.jakewharton.fliptables:fliptables|1.0.2|直接依赖|maven|
|com.sun.jersey:jersey-json|1.9|间接依赖|maven|
|org.apache.parquet:parquet-column|1.12.3|间接依赖|maven|
|org.apache.hadoop:hadoop-common|2.10.1|直接依赖|maven|
|io.confluent:kafka-avro-serializer|5.3.4|直接依赖|maven|
|commons-cli:commons-cli|1.2|间接依赖|maven|
|com.squareup.okio:okio|1.6.0|间接依赖|maven|
|com.sun.jersey.contribs:jersey-guice|1.9|间接依赖|maven|
|io.netty:netty-common|4.1.77.Final|间接依赖|maven|
|org.glassfish.jersey.core:jersey-client|2.17|间接依赖|maven|
|org.apache.orc:orc-core|1.8.3|直接依赖|maven|
|javax.validation:validation-api|1.1.0.Final|间接依赖|maven|
|commons-io:commons-io|2.4|间接依赖|maven|
|org.openjdk.jol:jol-core|0.16|直接依赖|maven|
|io.grpc:grpc-api|1.45.0|间接依赖|maven|
|commons-cli:commons-cli|1.3.1|间接依赖|maven|
|org.apache.hbase.thirdparty:hbase-shaded-gson|3.5.1|间接依赖|maven|
|com.google.cloud.bigdataoss:gcs-connector|hadoop2-2.2.7|直接依赖|maven|
|asm:asm|3.1|间接依赖|maven|
|io.dropwizard.metrics:metrics-graphite|4.1.1|直接依赖|maven|
|software.amazon.awssdk:protocol-core|2.18.40|间接依赖|maven|
|org.checkerframework:checker-compat-qual|2.5.5|间接依赖|maven|
|com.facebook.presto:presto-jdbc|0.273|直接依赖|maven|
|org.apache.velocity:velocity|1.5|间接依赖|maven|
|org.apache.hudi:hudi-utilities_2.12|1.0.0-SNAPSHOT|直接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|间接依赖|maven|
|org.apache.hbase:hbase-client|2.4.9|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.5.32|间接依赖|maven|
|org.javassist:javassist|3.25.0-GA|间接依赖|maven|
|org.apache.hbase:hbase-server|2.4.9|直接依赖|maven|
|org.springframework.shell:spring-shell-table|2.1.1|间接依赖|maven|
|software.amazon.awssdk:sqs|2.18.40|直接依赖|maven|
|org.apache.hbase:hbase-logging|2.4.9|间接依赖|maven|
|io.perfmark:perfmark-api|0.23.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.5.32|间接依赖|maven|
|org.jdom:jdom|1.1|间接依赖|maven|
|org.apache.spark:spark-tags_2.12|3.4.1|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|直接依赖|maven|
|org.apache.hbase:hbase-replication|2.4.9|间接依赖|maven|
|com.google.http-client:google-http-client|1.41.5|间接依赖|maven|
|org.datanucleus:datanucleus-core|4.1.17|间接依赖|maven|
|org.objenesis:objenesis|2.5.1|间接依赖|maven|
|com.squareup.okhttp:okhttp|2.7.5|间接依赖|maven|
|org.apache.hbase.thirdparty:hbase-shaded-jersey|3.5.1|间接依赖|maven|
|org.mortbay.jetty:jetty-sslengine|6.1.26|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.67|间接依赖|maven|
|org.apache.flink:flink-runtime_2.12|1.13.6|间接依赖|maven|
|com.lmax:disruptor|3.4.2|直接依赖|maven|
|io.opencensus:opencensus-contrib-resource-util|0.31.0|间接依赖|maven|
|software.amazon.awssdk:aws-json-protocol|2.18.40|间接依赖|maven|
|io.grpc:grpc-stub|1.47.0|间接依赖|maven|
|com.google.flogger:google-extensions|0.7.1|间接依赖|maven|
|org.eclipse.jetty:jetty-util-ajax|9.4.48.v20220622|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet-core|2.17|直接依赖|maven|
|org.junit.platform:junit-platform-engine|1.7.2|间接依赖|maven|
|org.apache.curator:apache-curator|2.7.1|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.3|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.14.2|直接依赖|maven|
|mysql:mysql-connector-java|8.0.22|直接依赖|maven|
|org.checkerframework:checker-qual|3.10.0|间接依赖|maven|
|org.springframework:spring-context|5.3.22|间接依赖|maven|
|io.grpc:grpc-protobuf|1.45.0|间接依赖|maven|
|org.apache.hudi:hudi-datahub-sync|1.0.0-SNAPSHOT|直接依赖|maven|
|org.apache.hudi:hudi-hadoop-mr|1.0.0-SNAPSHOT|直接依赖|maven|
|io.confluent:kafka-schema-registry-client|5.3.4|直接依赖|maven|
|com.yammer.metrics:metrics-core|2.2.0|直接依赖|maven|
|org.junit.platform:junit-platform-commons|1.7.2|直接依赖|maven|
|org.codehaus.jettison:jettison|1.1|间接依赖|maven|
|commons-httpclient:commons-httpclient|3.0.1|间接依赖|maven|
|org.apache.hudi:hudi-hadoop-mr-bundle|1.0.0-SNAPSHOT|直接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|org.apache.hudi:hudi-client-common|1.0.0-SNAPSHOT|直接依赖|maven|
|com.google.apis:google-api-services-storage|v1-rev20211018-1.32.1|间接依赖|maven|
|xml-apis:xml-apis|1.3.04|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.19.0|直接依赖|maven|
|org.jruby.joni:joni|2.1.31|间接依赖|maven|
|com.google.cloud:google-cloud-pubsub|1.120.0|直接依赖|maven|
|it.unimi.dsi:fastutil|7.0.13|间接依赖|maven|
|io.opencensus:opencensus-proto|0.2.0|间接依赖|maven|
|org.apache.hbase:hbase-asyncfs|2.4.9|间接依赖|maven|
|com.amazonaws:dynamodb-lock-client|1.2.0|直接依赖|maven|
|org.roaringbitmap:RoaringBitmap|0.9.47|直接依赖|maven|
|org.jline:jline-terminal-jna|3.21.0|间接依赖|maven|
|org.jruby.jcodings:jcodings|1.0.55|间接依赖|maven|
|io.prometheus:simpleclient_httpserver|0.8.0|直接依赖|maven|
|com.sun.xml.bind:jaxb-impl|2.2.3-1|间接依赖|maven|
|org.apache.flink:flink-shaded-asm-7|7.1-13.0|间接依赖|maven|
|org.apache.hbase:hbase-procedure|2.4.9|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.13|直接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-core|2.10.1|直接依赖|maven|
|com.google.api.grpc:proto-google-cloud-storage-v2|2.2.2-alpha|间接依赖|maven|
|org.apache.yetus:audience-annotations|0.12.0|间接依赖|maven|
|org.glassfish.hk2:hk2-utils|2.4.0-b10|间接依赖|maven|
|org.scalatest:scalatest_2.12|3.1.0|直接依赖|maven|
|org.slf4j:slf4j-api|2.0.6|直接依赖|maven|
|org.apache.htrace:htrace-core4|4.2.0-incubating|间接依赖|maven|
|org.apache.hudi:hudi-kafka-connect|1.0.0-SNAPSHOT|直接依赖|maven|
|org.json:json|20170516|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)