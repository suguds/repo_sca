# alibaba/canal安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699483274195894272.svg)](https://www.murphysec.com/console/report/1692597243265044480/1699483274195894272)

仓库描述：阿里巴巴 MySQL binlog 增量订阅&消费组件 

仓库地址：[https://github.com/alibaba/canal](https://github.com/alibaba/canal)

| star：26619 | watch：1200 | fork：7406 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-04 19:34:14 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-07 02:04:26 | 组件总数：454 | 漏洞总数：137 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache HttpClient 中间人攻击漏洞|输入验证不恰当|[MPS-2014-4288](https://www.oscs1024.com/hd/MPS-2014-4288)|CVE-2012-6153|中危|
|OpenSSL 安全漏洞|缓冲区溢出|[MPS-2016-2086](https://www.oscs1024.com/hd/MPS-2016-2086)|CVE-2016-2176|高危|
|OpenSSL MDC2_Update 函数整数溢出漏洞|越界写入|[MPS-2016-4549](https://www.oscs1024.com/hd/MPS-2016-4549)|CVE-2016-6303|严重|
|Google protobuf 缓冲区错误漏洞|越界写入|[MPS-2017-10841](https://www.oscs1024.com/hd/MPS-2017-10841)|CVE-2015-5237|高危|
|Netty和Play Framework 输入验证错误漏洞|未授权敏感信息泄露|[MPS-2017-11682](https://www.oscs1024.com/hd/MPS-2017-11682)|CVE-2015-2156|高危|
|Apache Tomcat SecurityManager绕过漏洞|访问控制不当|[MPS-2017-9011](https://www.oscs1024.com/hd/MPS-2017-9011)|CVE-2016-5018|严重|
|Apache Tomcat 访问限制绕过漏洞|访问控制不当|[MPS-2017-9027](https://www.oscs1024.com/hd/MPS-2017-9027)|CVE-2016-6796|高危|
|Apache Hadoop 信息泄漏漏洞|未授权敏感信息泄露|[MPS-2018-0896](https://www.oscs1024.com/hd/MPS-2018-0896)|CVE-2017-15713|中危|
|Oracle MySQL Connectors 访问控制错误漏洞|使用候选路径或通道进行的认证绕过|[MPS-2018-13771](https://www.oscs1024.com/hd/MPS-2018-13771)|CVE-2018-3258|高危|
|OpenSSL 加密问题漏洞|密码算法不安全|[MPS-2018-14285](https://www.oscs1024.com/hd/MPS-2018-14285)|CVE-2018-0734|中危|
|Apache Hadoop 路径遍历漏洞|路径遍历|[MPS-2018-14698](https://www.oscs1024.com/hd/MPS-2018-14698)|CVE-2018-8009|高危|
|OpenSSL 信息泄露漏洞|通过差异性导致的信息暴露|[MPS-2018-14899](https://www.oscs1024.com/hd/MPS-2018-14899)|CVE-2018-5407|中危|
|OpenSSL 加密问题漏洞|密码算法不安全|[MPS-2018-4731](https://www.oscs1024.com/hd/MPS-2018-4731)|CVE-2018-0737|中危|
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|Openssl OpenSSL 加密问题漏洞|密钥管理错误|[MPS-2018-7822](https://www.oscs1024.com/hd/MPS-2018-7822)|CVE-2018-0732|高危|
|Apache Thrift <0.12.0 绕过验证漏洞|证书验证不恰当|[MPS-2019-0104](https://www.oscs1024.com/hd/MPS-2019-0104)|CVE-2018-1320|高危|
|OpenSSL 安全漏洞|服务端安全的客户端实施|[MPS-2019-11271](https://www.oscs1024.com/hd/MPS-2019-11271)|CVE-2019-1547|中危|
|OpenSSL 安全漏洞||[MPS-2019-11273](https://www.oscs1024.com/hd/MPS-2019-11273)|CVE-2019-1563|低危|
|Netty 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2019-12064](https://www.oscs1024.com/hd/MPS-2019-12064)|CVE-2019-16869|高危|
|Red Hat JBoss Enterprise Application Platform 代码问题漏洞|反序列化|[MPS-2019-12470](https://www.oscs1024.com/hd/MPS-2019-12470)|CVE-2019-10202|严重|
|Elasticsearch 存在敏感信息泄露漏洞|未授权敏感信息泄露|[MPS-2019-13902](https://www.oscs1024.com/hd/MPS-2019-13902)|CVE-2019-7619|中危|
|Apache Hadoop 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2019-1459](https://www.oscs1024.com/hd/MPS-2019-1459)|CVE-2018-1296|高危|
|jackson-mapper-asl <=1.9.13 XXE 注入漏洞|XXE|[MPS-2019-15048](https://www.oscs1024.com/hd/MPS-2019-15048)|CVE-2019-10172|高危|
|OpenSSL 输入验证错误漏洞|整数溢出或环绕|[MPS-2019-15892](https://www.oscs1024.com/hd/MPS-2019-15892)|CVE-2019-1551|中危|
|SnakeYAML <1.26 存在 Billion laughs 漏洞|拒绝服务|[MPS-2019-16129](https://www.oscs1024.com/hd/MPS-2019-16129)|CVE-2017-18640|高危|
|Apache Log4j SocketServer反序列化漏洞|反序列化|[MPS-2019-17271](https://www.oscs1024.com/hd/MPS-2019-17271)|CVE-2019-17571|严重|
|OpenSSL 信息泄露漏洞|通过差异性导致的信息暴露|[MPS-2019-1990](https://www.oscs1024.com/hd/MPS-2019-1990)|CVE-2019-1559|中危|
|Oracle MySQL Connectors 输入验证错误漏洞|使用不兼容类型访问资源（类型混淆）|[MPS-2019-4430](https://www.oscs1024.com/hd/MPS-2019-4430)|CVE-2019-2692|中危|
|OpenSSL 信任管理问题漏洞|证书验证不恰当|[MPS-2019-8829](https://www.oscs1024.com/hd/MPS-2019-8829)|CVE-2019-1552|低危|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|OpenSSL 加密问题漏洞|通过差异性导致的信息暴露|[MPS-2020-12634](https://www.oscs1024.com/hd/MPS-2020-12634)|CVE-2020-1968|低危|
|Netty <=4.1.43.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1320](https://www.oscs1024.com/hd/MPS-2020-1320)|CVE-2020-7238|高危|
|Netty <4.1.44.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1526](https://www.oscs1024.com/hd/MPS-2020-1526)|CVE-2019-20444|严重|
|Netty <4.1.44.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1527](https://www.oscs1024.com/hd/MPS-2020-1527)|CVE-2019-20445|严重|
|Elasticsearch 存在权限管理不恰当漏洞|权限管理不当|[MPS-2020-15777](https://www.oscs1024.com/hd/MPS-2020-15777)|CVE-2020-7020|低危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|OpenSSL 空指针取消引用漏洞|空指针取消引用|[MPS-2020-17574](https://www.oscs1024.com/hd/MPS-2020-17574)|CVE-2020-1971|中危|
|mysql:mysql-connector-java <8.0.27 存在 XXE 漏洞|XXE|[MPS-2020-38350](https://www.oscs1024.com/hd/MPS-2020-38350)|CVE-2021-2471|中危|
|Elasticsearch  API 密钥权限提升漏洞|权限管理不当|[MPS-2020-4780](https://www.oscs1024.com/hd/MPS-2020-4780)|CVE-2020-7009|高危|
|Netty ZlibDecoders 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2020-5127](https://www.oscs1024.com/hd/MPS-2020-5127)|CVE-2020-11612|高危|
|Apache Log4j2 SmtpAppender证书验证不当漏洞|证书验证不恰当|[MPS-2020-6684](https://www.oscs1024.com/hd/MPS-2020-6684)|CVE-2020-9488|低危|
|Elasticsearch 权限管理不当漏洞|权限管理不当|[MPS-2020-8144](https://www.oscs1024.com/hd/MPS-2020-8144)|CVE-2020-7014|高危|
|Elasticsearch 资源管理错误漏洞|未经控制的递归|[MPS-2021-11043](https://www.oscs1024.com/hd/MPS-2021-11043)|CVE-2021-22144|中危|
|Elasticsearch 日志信息泄露漏洞|日志敏感信息泄露|[MPS-2021-1485](https://www.oscs1024.com/hd/MPS-2021-1485)|CVE-2020-7021|中危|
|Netty <4.1.59.Final 存在不安全的临时文件漏洞||[MPS-2021-1580](https://www.oscs1024.com/hd/MPS-2021-1580)|CVE-2021-21290|中危|
|OpenSSL 缓冲区错误漏洞|越界读取|[MPS-2021-17869](https://www.oscs1024.com/hd/MPS-2021-17869)|CVE-2021-3712|高危|
|OpenSSL 加密问题漏洞|加密强度不足|[MPS-2021-1869](https://www.oscs1024.com/hd/MPS-2021-1869)|CVE-2021-23839|低危|
|Spring Framework <5.3.14 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18854](https://www.oscs1024.com/hd/MPS-2021-18854)|CVE-2021-22060|中危|
|Pivotal Spring Framework 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18890](https://www.oscs1024.com/hd/MPS-2021-18890)|CVE-2021-22096|中危|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|FasterXML jackson-dataformat-cbor 内存耗尽漏洞|不加限制或调节的资源分配|[MPS-2021-1998](https://www.oscs1024.com/hd/MPS-2021-1998)|CVE-2020-28491|高危|
|OpenSSL 输入验证错误漏洞|整数溢出或环绕|[MPS-2021-2306](https://www.oscs1024.com/hd/MPS-2021-2306)|CVE-2021-23840|高危|
|io.netty:netty-codec-http2 <4.1.60.Final 存在 http 请求走私漏洞|HTTP请求走私|[MPS-2021-2435](https://www.oscs1024.com/hd/MPS-2021-2435)|CVE-2021-21295|中危|
|OpenSSL 输入验证错误漏洞|空指针取消引用|[MPS-2021-2535](https://www.oscs1024.com/hd/MPS-2021-2535)|CVE-2021-23841|中危|
|Netty Bzip2Decoder 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28116](https://www.oscs1024.com/hd/MPS-2021-28116)|CVE-2021-37136|高危|
|Netty 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28117](https://www.oscs1024.com/hd/MPS-2021-28117)|CVE-2021-37137|高危|
|Apache Commons Net <3.9.0 存在FTP跳转攻击漏洞|未授权敏感信息泄露|[MPS-2021-28440](https://www.oscs1024.com/hd/MPS-2021-28440)|CVE-2021-37533|中危|
|Openssl 空指针取消引用漏洞|空指针取消引用|[MPS-2021-3619](https://www.oscs1024.com/hd/MPS-2021-3619)|CVE-2021-3449|中危|
|Oracle MySQL 的 MySQL Connectors 存在授权不当漏洞|授权机制不恰当|[MPS-2021-36587](https://www.oscs1024.com/hd/MPS-2021-36587)|CVE-2022-21363|中危|
|Netty <4.1.71.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2021-36922](https://www.oscs1024.com/hd/MPS-2021-36922)|CVE-2021-43797|中危|
|Apache Tomcat 条件竞争漏洞|竞争条件|[MPS-2021-37218](https://www.oscs1024.com/hd/MPS-2021-37218)|CVE-2021-43980|低危|
|Apache Log4j JMSAppender反序列化漏洞||[MPS-2021-38359](https://www.oscs1024.com/hd/MPS-2021-38359)|CVE-2021-4104|高危|
|OpenSSL 输入验证错误漏洞|输入验证不恰当|[MPS-2021-39449](https://www.oscs1024.com/hd/MPS-2021-39449)|CVE-2021-4160|中危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|Elasticsearch 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-6747](https://www.oscs1024.com/hd/MPS-2021-6747)|CVE-2021-22137|中危|
|Elasticsearch 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-6749](https://www.oscs1024.com/hd/MPS-2021-6749)|CVE-2021-22135|中危|
|Vmware Spring Framework 安全漏洞|不加限制或调节的资源分配|[MPS-2022-1080](https://www.oscs1024.com/hd/MPS-2022-1080)|CVE-2022-22950|中危|
|Pivotal Spring Framework 安全限制绕过漏洞|大小写敏感处理不恰当|[MPS-2022-1098](https://www.oscs1024.com/hd/MPS-2022-1098)|CVE-2022-22968|中危|
|Spring Framework spring-beans 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1101](https://www.oscs1024.com/hd/MPS-2022-1101)|CVE-2022-22970|中危|
|Spring Framework 整数溢出漏洞|整数溢出或环绕|[MPS-2022-1106](https://www.oscs1024.com/hd/MPS-2022-1106)|CVE-2022-22976|中危|
|PostgreSQL JDBC 存在 SQL 注入漏洞|SQL注入|[MPS-2022-11227](https://www.oscs1024.com/hd/MPS-2022-11227)|CVE-2022-31197|高危|
|Fastjson < 1.2.83 任意代码执行漏洞|反序列化|[MPS-2022-11320](https://www.oscs1024.com/hd/MPS-2022-11320)|CVE-2022-25845|高危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|io.netty:netty-codec-http <4.1.53.Final 存在拒绝服务漏洞|拒绝服务|[MPS-2022-12064](https://www.oscs1024.com/hd/MPS-2022-12064)||中危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|Apache Thrift <0.9.3 SSL DOS 和不安全协商漏洞|拒绝服务|[MPS-2022-12148](https://www.oscs1024.com/hd/MPS-2022-12148)||中危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|org.apache.hadoop:hadoop-hdfs < 3.3.2 存在XXE漏洞|XXE|[MPS-2022-12474](https://www.oscs1024.com/hd/MPS-2022-12474)||中危|
|FasterXML Jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2022-12500](https://www.oscs1024.com/hd/MPS-2022-12500)||中危|
|Apache Tomcat 本地权限提升漏洞|检查时间与使用时间(TOCTOU)的竞争条件|[MPS-2022-1351](https://www.oscs1024.com/hd/MPS-2022-1351)|CVE-2022-23181|高危|
|Apache Log4j JDBCAppender SQL注入漏洞|SQL注入|[MPS-2022-1444](https://www.oscs1024.com/hd/MPS-2022-1444)|CVE-2022-23305|严重|
|Apache Log4j Chainsaw反序列化漏洞|反序列化|[MPS-2022-1445](https://www.oscs1024.com/hd/MPS-2022-1445)|CVE-2022-23307|高危|
|Apache Log4j 反序列化漏洞|反序列化|[MPS-2022-1446](https://www.oscs1024.com/hd/MPS-2022-1446)|CVE-2022-23302|高危|
|OpenSSL 存在任意命令执行漏洞|OS命令注入|[MPS-2022-18279](https://www.oscs1024.com/hd/MPS-2022-18279)|CVE-2022-2068|严重|
|Apache Pulsar C++/Python 客户端存在中间人攻击漏洞|中间人攻击|[MPS-2022-18844](https://www.oscs1024.com/hd/MPS-2022-18844)|CVE-2022-33684|中危|
|Elastic Stack Kibana 存在缺少授权漏洞|授权检查缺失|[MPS-2022-2136](https://www.oscs1024.com/hd/MPS-2022-2136)|CVE-2022-23709|中危|
|Elastic Stack Kibana 存在 XSS 漏洞|XSS|[MPS-2022-2137](https://www.oscs1024.com/hd/MPS-2022-2137)|CVE-2022-23710|中危|
|Netty 存在信息泄露漏洞||[MPS-2022-3790](https://www.oscs1024.com/hd/MPS-2022-3790)|CVE-2022-24823|中危|
|Apache Hadoop 存在shell命令注入漏洞|参数注入或修改|[MPS-2022-4190](https://www.oscs1024.com/hd/MPS-2022-4190)|CVE-2022-25168|严重|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|OpenSSL 拒绝服务漏洞|不可达退出条件的循环（无限循环）|[MPS-2022-5555](https://www.oscs1024.com/hd/MPS-2022-5555)|CVE-2022-0778|高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|Jettison <1.5.2 拒绝服务漏洞|拒绝服务|[MPS-2022-57067](https://www.oscs1024.com/hd/MPS-2022-57067)|CVE-2022-40150|高危|
|Jettison <1.5.1 拒绝服务漏洞|越界写入|[MPS-2022-57068](https://www.oscs1024.com/hd/MPS-2022-57068)|CVE-2022-40149|高危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|Netty <4.1.86.Final 存在 CRLF 注入漏洞||[MPS-2022-58552](https://www.oscs1024.com/hd/MPS-2022-58552)|CVE-2022-41915|中危|
|pgjdbc <42.5.1 存在信息泄露漏洞|不安全的临时文件|[MPS-2022-58583](https://www.oscs1024.com/hd/MPS-2022-58583)|CVE-2022-41946|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|Apache Hadoop 存在路径遍历漏洞|路径遍历|[MPS-2022-5920](https://www.oscs1024.com/hd/MPS-2022-5920)|CVE-2022-26612|严重|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|Spring Security通配符路由绕过漏洞|关键资源权限分配不当|[MPS-2022-62832](https://www.oscs1024.com/hd/MPS-2022-62832)|CVE-2023-20860|高危|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|Jettison <1.5.2 拒绝服务漏洞|越界写入|[MPS-2022-64973](https://www.oscs1024.com/hd/MPS-2022-64973)|CVE-2022-45685|高危|
|H2 数据库明文密码问题|未授权敏感信息泄露|[MPS-2022-65204](https://www.oscs1024.com/hd/MPS-2022-65204)|CVE-2022-45868|高危|
|OpenSSL 安全漏洞|通过差异性导致的信息暴露|[MPS-2022-66954](https://www.oscs1024.com/hd/MPS-2022-66954)|CVE-2022-4304|中危|
|spring-beans 远程代码执行漏洞(Spring4Shell)|表达式语言注入|[MPS-2022-6820](https://www.oscs1024.com/hd/MPS-2022-6820)|CVE-2022-22965|严重|
|OpenSSL 操作系统命令注入漏洞|OS命令注入|[MPS-2022-8314](https://www.oscs1024.com/hd/MPS-2022-8314)|CVE-2022-1292|严重|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|OpenSSL 资源管理错误漏洞|UAF|[MPS-2023-1276](https://www.oscs1024.com/hd/MPS-2023-1276)|CVE-2023-0215|高危|
|OpenSSL拒绝服务漏洞(X.509 GeneralName类型混淆)|不正确的类型转换|[MPS-2023-1620](https://www.oscs1024.com/hd/MPS-2023-1620)|CVE-2023-0286|高危|
|Node.js 安全漏洞|拒绝服务|[MPS-2023-2179](https://www.oscs1024.com/hd/MPS-2023-2179)|CVE-2023-23919|高危|
|Node.js 代码问题漏洞|不可信的搜索路径|[MPS-2023-2180](https://www.oscs1024.com/hd/MPS-2023-2180)|CVE-2023-23920|中危|
|OpenSSL 验证 X.509 策略约束存在拒绝服务漏洞|拒绝服务|[MPS-2023-2810](https://www.oscs1024.com/hd/MPS-2023-2810)|CVE-2023-0464|中危|
|OpenSSL 信任管理问题漏洞|证书验证不恰当|[MPS-2023-2811](https://www.oscs1024.com/hd/MPS-2023-2811)|CVE-2023-0465|中危|
|OpenSSL 存在证书验证不当|证书验证不恰当|[MPS-2023-2812](https://www.oscs1024.com/hd/MPS-2023-2812)|CVE-2023-0466|中危|
|Apache Kafka Connect 模块JNDI注入漏洞|反序列化|[MPS-2023-3834](https://www.oscs1024.com/hd/MPS-2023-3834)|CVE-2023-25194|高危|
|java-xmlbuilder 代码问题漏洞|XXE|[MPS-2023-5040](https://www.oscs1024.com/hd/MPS-2023-5040)|CVE-2014-125087|严重|
|netplex json-smart 安全漏洞|未经控制的递归|[MPS-2023-7760](https://www.oscs1024.com/hd/MPS-2023-7760)|CVE-2023-1370|高危|
|Jettison 安全漏洞|未经控制的递归|[MPS-2023-8270](https://www.oscs1024.com/hd/MPS-2023-8270)|CVE-2023-1436|高危|
|jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2023-8438](https://www.oscs1024.com/hd/MPS-2023-8438)|CVE-2021-46877|中危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|OpenSSL ASN.1对象标识符转换拒绝服务漏洞|拒绝服务|[MPS-9dro-82lx](https://www.oscs1024.com/hd/MPS-9dro-82lx)|CVE-2023-2650|中危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|OpenSSL 安全漏洞|过度迭代|[MPS-n3pe-ljgc](https://www.oscs1024.com/hd/MPS-n3pe-ljgc)|CVE-2023-3817|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|Apache Tomcat FORM 重定向漏洞|跨站重定向|[MPS-uy56-j8e4](https://www.oscs1024.com/hd/MPS-uy56-j8e4)|CVE-2023-41080|低危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.yaml:snakeyaml|1.29|2.0|直接依赖|建议修复|C:0|H:2|M:4|L:1|
|log4j:log4j|1.2.17||间接依赖|建议修复|C:2|H:3|M:0|L:1|
|tomcat:jasper-runtime|5.5.23||间接依赖|建议修复|C:1|H:0|M:0|L:0|
|io.netty:netty-handler|4.1.36.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|com.google.protobuf:protobuf-java|2.5.0|3.21.7|直接依赖|建议修复|C:0|H:1|M:2|L:0|
|node.js|9.11.1|19.6.1|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|io.netty:netty|3.6.2.Final|3.10.3.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|org.apache.hadoop:hadoop-common|2.7.5|3.3.3|间接依赖|建议修复|C:2|H:1|M:1|L:0|
|org.codehaus.jettison:jettison|1.1|1.5.4|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|org.springframework:spring-beans|5.3.9|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework:spring-context|5.3.9|5.3.19|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.jboss.netty:netty|3.2.10.Final||直接依赖|建议修复|C:0|H:1|M:0|L:0|
|openssl|1.0.2o|3.1.2|间接依赖|建议修复|C:3|H:7|M:16|L:4|
|org.yaml:snakeyaml|1.28|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.52|11.0.0-m6|间接依赖|建议修复|C:0|H:1|M:0|L:2|
|com.fasterxml.jackson.core:jackson-databind|2.12.4|2.14.0-rc1|间接依赖|建议修复|C:0|H:1|M:5|L:0|
|org.postgresql:postgresql|42.3.3|42.5.1|直接依赖|建议修复|C:0|H:1|M:1|L:0|
|net.minidev:json-smart|2.4.7|2.4.9|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-webmvc|5.3.9|6.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-web|5.3.9|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework.security:spring-security-crypto|5.5.2|5.6.4|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.xerial.snappy:snappy-java|1.1.7.3|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.apache.kafka:kafka-clients|2.4.0|3.4.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-codec|4.1.32.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|com.alibaba:fastjson|1.2.69|1.2.83|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-codec|4.1.36.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|com.google.protobuf:protobuf-java|3.6.1|3.21.7|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.jamesmurty.utils:java-xmlbuilder|0.4|1.2|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.apache.hadoop:hadoop-hdfs|2.7.4|3.3.2|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|tomcat:jasper-compiler|5.5.23||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-codec-http|4.1.36.Final|4.1.86.final|间接依赖|建议修复|C:2|H:2|M:5|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.12.2|2.14.0-rc1|间接依赖|建议修复|C:0|H:1|M:5|L:0|
|org.elasticsearch:elasticsearch|7.3.0|8.2.1|直接依赖|建议修复|C:0|H:2|M:7|L:1|
|org.xerial.snappy:snappy-java|1.0.5|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.yaml:snakeyaml|1.19|2.0|直接依赖|建议修复|C:0|H:3|M:4|L:1|
|org.codehaus.jackson:jackson-mapper-asl|1.9.2||间接依赖|建议修复|C:1|H:1|M:0|L:0|
|mysql:mysql-connector-java|5.1.48|8.0.28|直接依赖|建议修复|C:0|H:1|M:3|L:0|
|io.netty:netty-codec-http|4.1.32.Final|4.1.86.final|间接依赖|建议修复|C:2|H:2|M:5|L:0|
|io.netty:netty-handler|4.1.32.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.5.4|3.0.7|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.guava:guava|18.0|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:2|L:1|
|org.springframework:spring-core|5.3.9|6.0.7|直接依赖|可选修复|C:0|H:0|M:3|L:0|
|com.h2database:h2|2.1.210||直接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-expression|5.3.9|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|commons-io:commons-io|2.4|2.7|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-net:commons-net|3.1|3.9.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.code.gson:gson|2.8.6|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|commons-httpclient:commons-httpclient|3.1||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|22.0|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:2|L:1|
|org.elasticsearch:elasticsearch|6.8.22|8.2.1|直接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.bouncycastle:bcprov-jdk15on|1.69||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.code.gson:gson|2.8.5|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|commons-codec:commons-codec|1.9|1.13|直接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.apache.thrift:libthrift|0.9.0|0.12.0|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|com.google.code.gson:gson|2.2.4|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.8.11|2.12.1|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|io.netty:netty-common|4.1.32.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|io.netty:netty-common|4.1.36.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.apache.pulsar:pulsar-client|2.8.1|2.10.2|直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|346|Low|
|自定义许可证|51|Low|
|MPL-2.0|2|Low|
|EPL-1.0|5|Low|
|MIT|13|Low|
|CDDL-1.1|9|Low|
|BSD-3-Clause|4|Low|
|CDDL-1.0|3|Low|
|LGPL-2.1|2|Medium|
|EPL-2.0|10|Low|
|LGPL-2.1-or-later|1|Low|
|BSD-2-Clause|2|Low|
|GPL-2.0|1|Medium|
|MPL-1.1|1|Low|
|OpenSSL|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.apache.lucene:lucene-core|8.11.1|间接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-client|6.8.22|直接依赖|maven|
|node.js|9.11.1|间接依赖||
|org.elasticsearch:elasticsearch-secure-sm|7.3.0|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-client|2.7.4|间接依赖|maven|
|org.apache.directory.server:apacheds-i18n|2.0.0-M15|间接依赖|maven|
|org.apache.lucene:lucene-backward-codecs|8.1.0|间接依赖|maven|
|org.apache.hbase:hbase-annotations|1.4.0|间接依赖|maven|
|org.apache.tephra:tephra-hbase-compat-1.4|0.14.0-incubating|间接依赖|maven|
|org.bouncycastle:bcutil-jdk15on|1.69|间接依赖|maven|
|com.ibm.icu:icu4j-localespi|60.2|间接依赖|maven|
|com.h2database:h2|2.1.210|直接依赖|maven|
|org.apache.phoenix:phoenix-core|4.14.1-HBase-1.4|直接依赖|maven|
|org.springframework:spring-aop|5.3.9|直接依赖|maven|
|org.checkerframework:checker-qual|3.5.0|间接依赖|maven|
|org.elasticsearch:elasticsearch-x-content|7.3.0|间接依赖|maven|
|org.yaml:snakeyaml|1.29|直接依赖|maven|
|org.apache.kudu:kudu-client|1.6.0|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.12.4|间接依赖|maven|
|com.clearspring.analytics:stream|2.9.5|间接依赖|maven|
|org.elasticsearch.plugin:aggs-matrix-stats-client|6.8.22|间接依赖|maven|
|org.apache.twill:twill-core|0.8.0|间接依赖|maven|
|commons-io:commons-io|2.4|直接依赖|maven|
|org.springframework:spring-tx|5.3.9|间接依赖|maven|
|net.minidev:accessors-smart|2.4.7|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.5.4|间接依赖|maven|
|org.apache.lucene:lucene-queryparser|7.7.3|间接依赖|maven|
|org.avaje:avaje-classpath-scanner-api|2.2|间接依赖|maven|
|com.alibaba:druid|1.2.17|直接依赖|maven|
|com.sun.jersey:jersey-server|1.9|间接依赖|maven|
|org.apache.pulsar:pulsar-client-admin-api|2.8.1|间接依赖|maven|
|com.google.guava:guava|18.0|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.14.2|间接依赖|maven|
|commons-digester:commons-digester|1.8.1|间接依赖|maven|
|org.elasticsearch:jna|4.5.1|间接依赖|maven|
|io.airlift:aircompressor|0.20|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.0.5|间接依赖|maven|
|io.ebean:ebean-datasource|4.5.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-test|2.5.4|直接依赖|maven|
|commons-httpclient:commons-httpclient|3.1|间接依赖|maven|
|io.netty:netty-codec-http|4.1.32.Final|间接依赖|maven|
|org.apache.lucene:lucene-memory|7.7.3|间接依赖|maven|
|commons-configuration:commons-configuration|1.6|间接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.14.2|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.2|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.12|直接依赖|maven|
|org.mortbay.jetty:jetty|6.1.26|间接依赖|maven|
|org.apache.rocketmq:rocketmq-logging|4.8.0|间接依赖|maven|
|org.apache.lucene:lucene-spatial3d|7.7.3|间接依赖|maven|
|org.apache.kafka:kafka-clients|2.4.0|直接依赖|maven|
|log4j:log4j|1.2.17|间接依赖|maven|
|org.elasticsearch:elasticsearch-core|6.8.22|间接依赖|maven|
|org.fusesource.leveldbjni:leveldbjni-all|1.8|间接依赖|maven|
|org.elasticsearch:elasticsearch-geo|7.3.0|间接依赖|maven|
|org.mortbay.jetty:jetty-sslengine|6.1.26|间接依赖|maven|
|io.ebean:ebean-migration|11.16.2|间接依赖|maven|
|org.elasticsearch.plugin:percolator-client|6.8.22|间接依赖|maven|
|com.lmax:disruptor|3.4.2|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.12.4|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.52|间接依赖|maven|
|net.java.dev.jets3t:jets3t|0.9.0|间接依赖|maven|
|org.jboss.netty:netty|3.2.10.Final|直接依赖|maven|
|ch.qos.logback:logback-core|1.2.8|直接依赖|maven|
|com.alibaba.otter:canal.parse.dbsync|1.1.7-SNAPSHOT|直接依赖|maven|
|com.vaadin.external.google:android-json|0.0.20131108.vaadin1|间接依赖|maven|
|com.oracle.database.ha:ons|21.1.0.0|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.1|间接依赖|maven|
|org.apache.lucene:lucene-queryparser|8.1.0|间接依赖|maven|
|commons-beanutils:commons-beanutils-core|1.8.0|间接依赖|maven|
|org.elasticsearch:jna|5.5.0|间接依赖|maven|
|javax.servlet:servlet-api|2.5|间接依赖|maven|
|org.elasticsearch.plugin:parent-join-client|6.8.22|间接依赖|maven|
|org.apache.rocketmq:rocketmq-acl|4.8.0|直接依赖|maven|
|org.lz4:lz4-java|1.8.0|间接依赖|maven|
|com.alibaba.otter:canal.parse.driver|1.1.7-SNAPSHOT|直接依赖|maven|
|org.apache.tephra:tephra-api|0.14.0-incubating|间接依赖|maven|
|org.apache.lucene:lucene-spatial3d|8.1.0|间接依赖|maven|
|org.apache.curator:curator-recipes|2.10.0|直接依赖|maven|
|org.apache.lucene:lucene-spatial-extras|8.1.0|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|间接依赖|maven|
|io.netty:netty-common|4.1.36.Final|间接依赖|maven|
|asm:asm|3.1|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.0.18|间接依赖|maven|
|org.apache.lucene:lucene-sandbox|8.1.0|间接依赖|maven|
|org.springframework:spring-core|5.3.9|直接依赖|maven|
|org.codehaus.jackson:jackson-mapper-asl|1.9.2|间接依赖|maven|
|com.carrotsearch:hppc|0.8.1|间接依赖|maven|
|com.jayway.jsonpath:json-path|2.5.0|间接依赖|maven|
|com.yammer.metrics:metrics-core|2.2.0|间接依赖|maven|
|org.apache.lucene:lucene-highlighter|7.7.3|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.3|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|直接依赖|maven|
|io.netty:netty-resolver|4.1.36.Final|间接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.13|间接依赖|maven|
|org.elasticsearch.plugin:rank-eval-client|6.8.22|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.52|间接依赖|maven|
|org.elasticsearch:elasticsearch-cli|7.17.9|间接依赖|maven|
|com.aliyun.openservices:tablestore|5.10.3|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.13|间接依赖|maven|
|io.prometheus:simpleclient_hotspot|0.4.0|直接依赖|maven|
|javax.activation:activation|1.1|间接依赖|maven|
|org.mortbay.jetty:jsp-2.1|6.1.14|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|2.7.5|间接依赖|maven|
|org.apache.lucene:lucene-grouping|7.7.3|间接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-high-level-client|7.17.9|直接依赖|maven|
|org.springframework:spring-beans|5.3.9|间接依赖|maven|
|tomcat:jasper-runtime|5.5.23|间接依赖|maven|
|org.apache.directory.api:api-asn1-api|1.0.0-M20|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.14.2|间接依赖|maven|
|io.netty:netty-all|4.1.68.Final|直接依赖|maven|
|io.netty:netty-buffer|4.1.36.Final|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.25|间接依赖|maven|
|org.apache.commons:commons-lang3|3.7|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.5.4|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.6.2|直接依赖|maven|
|com.google.code.gson:gson|2.8.5|间接依赖|maven|
|io.prometheus:simpleclient_common|0.4.0|间接依赖|maven|
|org.opentest4j:opentest4j|1.2.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.0|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.8.11|间接依赖|maven|
|org.elasticsearch:elasticsearch-core|7.3.0|间接依赖|maven|
|org.lz4:lz4-java|1.6.0|间接依赖|maven|
|sqlline:sqlline|1.2.0|间接依赖|maven|
|commons-logging:commons-logging|1.1.3|间接依赖|maven|
|com.alibaba.otter:canal.prometheus|1.1.7-SNAPSHOT|直接依赖|maven|
|org.elasticsearch:elasticsearch-plugin-classloader|7.17.9|间接依赖|maven|
|org.elasticsearch:elasticsearch|7.3.0|直接依赖|maven|
|com.alibaba.otter:canal.instance.spring|1.1.7-SNAPSHOT|直接依赖|maven|
|org.mybatis:mybatis-spring|2.0.4|直接依赖|maven|
|io.ebean:persistence-api|2.2.2|间接依赖|maven|
|org.codehaus.jackson:jackson-jaxrs|1.9.13|间接依赖|maven|
|org.elasticsearch.client:transport|6.8.22|直接依赖|maven|
|org.elasticsearch.plugin:aggs-matrix-stats-client|7.17.9|间接依赖|maven|
|com.github.spullara.mustache.java:compiler|0.9.6|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-jobclient|2.7.4|间接依赖|maven|
|io.netty:netty-buffer|4.1.32.Final|间接依赖|maven|
|org.elasticsearch:elasticsearch-ssl-config|6.8.22|间接依赖|maven|
|org.eclipse.parsson:parsson|1.0.0|间接依赖|maven|
|org.apache.yetus:audience-annotations|0.5.0|间接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|org.apache.yetus:audience-annotations|0.4.0|间接依赖|maven|
|org.apache.pulsar:pulsar-client|2.8.1|直接依赖|maven|
|com.alibaba.mq-amqp:mq-amqp-client|1.0.3|直接依赖|maven|
|org.apache.commons:commons-csv|1.0|间接依赖|maven|
|io.netty:netty-handler|4.1.36.Final|间接依赖|maven|
|org.apache.lucene:lucene-grouping|8.11.1|间接依赖|maven|
|jakarta.json:jakarta.json-api|2.0.1|间接依赖|maven|
|org.apache.hadoop:hadoop-auth|2.7.4|间接依赖|maven|
|org.apache.twill:twill-common|0.8.0|间接依赖|maven|
|org.avaje:avaje-classpath-scanner|3.1.1|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.7.3|间接依赖|maven|
|org.elasticsearch:elasticsearch-core|7.17.9|间接依赖|maven|
|org.elasticsearch:elasticsearch-geo|7.17.9|间接依赖|maven|
|org.yaml:snakeyaml|1.28|间接依赖|maven|
|com.oracle.database.ha:simplefan|21.1.0.0|间接依赖|maven|
|net.java.dev.jna:jna|5.10.0|间接依赖|maven|
|org.codehaus.jackson:jackson-xc|1.8.3|间接依赖|maven|
|io.netty:netty-codec|4.1.32.Final|间接依赖|maven|
|org.apache.avro:avro-protobuf|1.10.2|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.6.1|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.5.4|间接依赖|maven|
|com.google.inject.extensions:guice-assistedinject|3.0|间接依赖|maven|
|org.springframework:spring-orm|5.3.9|直接依赖|maven|
|com.google.guava:guava|22.0|直接依赖|maven|
|io.ebean:ebean|11.41.1|直接依赖|maven|
|org.elasticsearch.plugin:lang-mustache-client|7.17.9|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.2.2|间接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.2|间接依赖|maven|
|org.apache.curator:curator-client|2.10.0|间接依赖|maven|
|com.google.protobuf:protobuf-java|2.5.0|直接依赖|maven|
|org.apache.lucene:lucene-memory|8.1.0|间接依赖|maven|
|com.google.inject.extensions:guice-servlet|3.0|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.12|直接依赖|maven|
|commons-net:commons-net|3.1|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-core|2.7.5|间接依赖|maven|
|com.google.inject:guice|3.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.12.4|间接依赖|maven|
|org.apiguardian:apiguardian-api|1.1.0|间接依赖|maven|
|org.apache.tephra:tephra-core|0.14.0-incubating|间接依赖|maven|
|io.prometheus:simpleclient_pushgateway|0.4.0|直接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.0|间接依赖|maven|
|io.netty:netty-resolver|4.1.32.Final|间接依赖|maven|
|org.apache.hbase:hbase-prefix-tree|1.4.0|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.8|直接依赖|maven|
|joda-time:joda-time|2.9.4|直接依赖|maven|
|org.apache.lucene:lucene-grouping|8.1.0|间接依赖|maven|
|org.objenesis:objenesis|3.2|间接依赖|maven|
|org.elasticsearch.client:transport|7.3.0|直接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.69|间接依赖|maven|
|org.elasticsearch.plugin:parent-join-client|7.3.0|间接依赖|maven|
|org.apache.curator:curator-framework|2.7.1|间接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-client|7.3.0|直接依赖|maven|
|org.jctools:jctools-core|2.1.2|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.8.11|间接依赖|maven|
|org.apache.hbase:hbase-shaded-client|1.1.2|直接依赖|maven|
|com.github.spullara.mustache.java:compiler|0.9.3|间接依赖|maven|
|javax.servlet.jsp:jsp-api|2.1|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.2-5|直接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.32|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.9|间接依赖|maven|
|org.apache.lucene:lucene-join|8.1.0|间接依赖|maven|
|/usr/lib/libSystem.B.dylib||间接依赖||
|org.springframework.security:spring-security-crypto|5.5.2|间接依赖|maven|
|com.alibaba:fastjson|1.2.69|间接依赖|maven|
|com.oracle.database.security:osdt_cert|21.1.0.0|间接依赖|maven|
|io.ebean:ebean-annotation|4.11|间接依赖|maven|
|commons-codec:commons-codec|1.9|直接依赖|maven|
|org.elasticsearch:elasticsearch-x-content|7.17.9|间接依赖|maven|
|org.apache.hbase:hbase-hadoop2-compat|1.4.0|间接依赖|maven|
|com.github.stephenc.findbugs:findbugs-annotations|1.3.9-1|间接依赖|maven|
|net.minidev:json-smart|2.4.7|间接依赖|maven|
|com.sun.jersey.contribs:jersey-guice|1.9|间接依赖|maven|
|org.apache.lucene:lucene-highlighter|8.11.1|间接依赖|maven|
|org.elasticsearch.plugin:transport-netty4-client|7.3.0|间接依赖|maven|
|org.springframework.boot:spring-boot-test|2.5.4|间接依赖|maven|
|io.ebean:ebean-datasource-api|4.5|间接依赖|maven|
|com.stumbleupon:async|1.4.1|间接依赖|maven|
|org.apache.lucene:lucene-join|7.7.3|间接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.5|间接依赖|maven|
|org.apache.lucene:lucene-spatial|8.1.0|间接依赖|maven|
|net.sf.jopt-simple:jopt-simple|5.0.2|间接依赖|maven|
|org.jamon:jamon-runtime|2.4.1|间接依赖|maven|
|org.apache.twill:twill-zookeeper|0.8.0|间接依赖|maven|
|/usr/lib/libc++.1.dylib||间接依赖||
|com.sun.jersey:jersey-json|1.9|间接依赖|maven|
|org.apache.lucene:lucene-highlighter|8.1.0|间接依赖|maven|
|com.alibaba.otter:canal.filter|1.1.7-SNAPSHOT|直接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.4|间接依赖|maven|
|org.elasticsearch.plugin:lang-mustache-client|7.3.0|间接依赖|maven|
|com.alibaba.otter:canal.store|1.1.7-SNAPSHOT|直接依赖|maven|
|org.apache.lucene:lucene-backward-codecs|7.7.3|间接依赖|maven|
|io.prometheus:simpleclient|0.4.0|直接依赖|maven|
|org.elasticsearch:elasticsearch-lz4|7.17.9|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.10.22|间接依赖|maven|
|org.apache.lucene:lucene-suggest|7.7.3|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.5.4|直接依赖|maven|
|io.netty:netty-handler|4.1.32.Final|间接依赖|maven|
|org.elasticsearch:elasticsearch-cli|7.3.0|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|直接依赖|maven|
|org.apache.rocketmq:rocketmq-srvutil|4.8.0|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|2.7.4|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.52|间接依赖|maven|
|org.jruby.joni:joni|2.1.2|间接依赖|maven|
|org.elasticsearch:elasticsearch|7.17.9|间接依赖|maven|
|com.googlecode.aviator:aviator|2.2.1|直接依赖|maven|
|org.mortbay.jetty:servlet-api-2.5|6.1.14|间接依赖|maven|
|org.apache.lucene:lucene-memory|8.11.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.12.4|间接依赖|maven|
|org.apache.lucene:lucene-queries|8.1.0|间接依赖|maven|
|io.netty:netty-transport|4.1.36.Final|间接依赖|maven|
|org.apache.twill:twill-discovery-api|0.8.0|间接依赖|maven|
|org.antlr:antlr-runtime|3.5.2|间接依赖|maven|
|commons-el:commons-el|1.0|间接依赖|maven|
|com.alibaba.otter:canal.meta|1.1.7-SNAPSHOT|直接依赖|maven|
|org.mockito:mockito-core|3.9.0|间接依赖|maven|
|org.mortbay.jetty:jetty-util|6.1.26|间接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-high-level-client|7.3.0|直接依赖|maven|
|net.bytebuddy:byte-buddy-agent|1.10.22|间接依赖|maven|
|org.apache.hbase:hbase-metrics-api|1.4.0|间接依赖|maven|
|org.apache.lucene:lucene-core|7.7.3|间接依赖|maven|
|org.springframework.boot:spring-boot|2.5.4|直接依赖|maven|
|commons-lang:commons-lang|2.6|直接依赖|maven|
|co.elastic.clients:elasticsearch-java|8.6.2|直接依赖|maven|
|com.salesforce.i18n:i18n-util|1.0.4|间接依赖|maven|
|org.bouncycastle:bcprov-ext-jdk15on|1.69|间接依赖|maven|
|org.hamcrest:hamcrest|2.2|间接依赖|maven|
|org.apache.lucene:lucene-misc|7.7.3|间接依赖|maven|
|org.elasticsearch.plugin:rank-eval-client|7.3.0|间接依赖|maven|
|mysql:mysql-connector-java|5.1.48|直接依赖|maven|
|com.alibaba.otter:canal.client|1.1.7-SNAPSHOT|直接依赖|maven|
|org.apache.pulsar:pulsar-transaction-common|2.8.1|间接依赖|maven|
|org.mybatis:mybatis|3.5.6|直接依赖|maven|
|org.elasticsearch:elasticsearch-cli|6.8.22|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.12.2|间接依赖|maven|
|commons-digester:commons-digester|1.8|间接依赖|maven|
|net.jcip:jcip-annotations|1.0|间接依赖|maven|
|org.apache.thrift:libthrift|0.9.0|间接依赖|maven|
|org.apache.commons:commons-compress|1.22|直接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-common|2.7.4|间接依赖|maven|
|commons-daemon:commons-daemon|1.0.13|间接依赖|maven|
|org.apache.zookeeper:zookeeper-jute|3.5.6|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-shuffle|2.7.4|间接依赖|maven|
|org.apache.lucene:lucene-spatial-extras|7.7.3|间接依赖|maven|
|org.springframework.cloud:spring-cloud-context|3.0.6|直接依赖|maven|
|org.apache.avro:avro|1.10.2|间接依赖|maven|
|com.alibaba.otter:client-adapter.common|1.1.7-SNAPSHOT|直接依赖|maven|
|org.assertj:assertj-core|3.19.0|间接依赖|maven|
|org.apache.curator:curator-client|2.7.1|间接依赖|maven|
|com.alibaba.fastjson2:fastjson2|2.0.31|直接依赖|maven|
|org.xmlunit:xmlunit-core|2.8.2|间接依赖|maven|
|org.apache.lucene:lucene-core|8.1.0|间接依赖|maven|
|org.springframework:spring-jdbc|5.3.9|直接依赖|maven|
|org.elasticsearch:elasticsearch-ssl-config|7.3.0|间接依赖|maven|
|javax.validation:validation-api|1.1.0.Final|间接依赖|maven|
|org.mockito:mockito-junit-jupiter|3.9.0|间接依赖|maven|
|org.apache.twill:twill-discovery-core|0.8.0|间接依赖|maven|
|org.apache.pulsar:bouncy-castle-bc|2.8.1|间接依赖|maven|
|org.elasticsearch.plugin:rank-eval-client|7.17.9|间接依赖|maven|
|org.apache.hadoop:hadoop-client|2.7.4|间接依赖|maven|
|com.alibaba.otter:canal.common|1.1.7-SNAPSHOT|直接依赖|maven|
|io.dropwizard.metrics:metrics-core|3.1.0|间接依赖|maven|
|org.apache.hbase:hbase-server|1.4.0|间接依赖|maven|
|org.apache.rocketmq:rocketmq-remoting|4.8.0|间接依赖|maven|
|com.rabbitmq:amqp-client|5.5.0|直接依赖|maven|
|org.elasticsearch.plugin:percolator-client|7.3.0|间接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-high-level-client|6.8.22|直接依赖|maven|
|com.ibm.icu:icu4j-charset|60.2|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.5.4|间接依赖|maven|
|org.elasticsearch.plugin:reindex-client|7.3.0|间接依赖|maven|
|org.apache.commons:commons-math3|3.1.1|间接依赖|maven|
|org.ow2.asm:asm-all|5.0.2|间接依赖|maven|
|openssl|1.0.2o|间接依赖||
|org.elasticsearch.plugin:reindex-client|6.8.22|间接依赖|maven|
|org.elasticsearch:elasticsearch|6.8.22|直接依赖|maven|
|org.apache.lucene:lucene-analyzers-common|8.11.1|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.5|间接依赖|maven|
|org.apache.lucene:lucene-analyzers-common|8.1.0|间接依赖|maven|
|io.netty:netty|3.6.2.Final|间接依赖|maven|
|org.apache.hbase:hbase-client|1.4.8|直接依赖|maven|
|org.apache.htrace:htrace-core|3.1.0-incubating|间接依赖|maven|
|org.apache.lucene:lucene-analyzers-common|7.7.3|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.12.4|间接依赖|maven|
|com.alibaba.otter:canal.parse|1.1.7-SNAPSHOT|直接依赖|maven|
|org.apache.lucene:lucene-sandbox|7.7.3|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-smile|2.8.11|间接依赖|maven|
|commons-validator:commons-validator|1.6|间接依赖|maven|
|org.springframework:spring-jcl|5.3.9|间接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-client|8.6.2|间接依赖|maven|
|org.junit.platform:junit-platform-engine|1.7.2|间接依赖|maven|
|com.alibaba.otter:connector.core|1.1.7-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.12.2|间接依赖|maven|
|org.yaml:snakeyaml|1.19|间接依赖|maven|
|org.apache.hadoop:hadoop-common|2.7.5|间接依赖|maven|
|org.antlr:antlr4-runtime|4.7.2|间接依赖|maven|
|org.apache.lucene:lucene-queries|8.11.1|间接依赖|maven|
|org.elasticsearch.plugin:parent-join-client|7.17.9|间接依赖|maven|
|org.elasticsearch.plugin:mapper-extras-client|7.17.9|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|直接依赖|maven|
|org.apache.lucene:lucene-misc|8.11.1|间接依赖|maven|
|io.netty:netty-tcnative-boringssl-static|1.1.33.Fork26|间接依赖|maven|
|com.github.stephenc.jcip:jcip-annotations|1.0-1|间接依赖|maven|
|com.101tec:zkclient|0.10|直接依赖|maven|
|org.apache.pulsar:pulsar-client-api|2.8.1|间接依赖|maven|
|com.jcraft:jsch|0.1.54|间接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.3|间接依赖|maven|
|org.mortbay.jetty:jsp-api-2.1|6.1.14|间接依赖|maven|
|org.apache.lucene:lucene-suggest|8.11.1|间接依赖|maven|
|org.elasticsearch.plugin:aggs-matrix-stats-client|7.3.0|间接依赖|maven|
|org.apache.directory.api:api-util|1.0.0-M20|间接依赖|maven|
|oro:oro|2.0.8|直接依赖|maven|
|org.apache.commons:commons-math|2.2|间接依赖|maven|
|org.postgresql:postgresql|42.3.3|直接依赖|maven|
|org.ow2.asm:asm|9.1|间接依赖|maven|
|io.netty:netty-codec-http|4.1.36.Final|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.14|间接依赖|maven|
|com.oracle.database.jdbc:ucp|21.1.0.0|间接依赖|maven|
|com.oracle.database.security:oraclepki|21.1.0.0|间接依赖|maven|
|io.netty:netty-transport|4.1.32.Final|间接依赖|maven|
|org.apache.lucene:lucene-suggest|8.1.0|间接依赖|maven|
|org.apache.hbase:hbase-procedure|1.4.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.12.2|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|org.apache.rocketmq:rocketmq-common|4.8.0|间接依赖|maven|
|com.sun.jersey:jersey-client|1.9|间接依赖|maven|
|org.apache.hadoop:hadoop-hdfs|2.7.4|间接依赖|maven|
|com.google.code.gson:gson|2.2.4|间接依赖|maven|
|io.netty:netty-codec|4.1.36.Final|间接依赖|maven|
|jline:jline|2.11|间接依赖|maven|
|com.alibaba.otter:client-adapter.escore|1.1.7-SNAPSHOT|直接依赖|maven|
|xmlenc:xmlenc|0.52|间接依赖|maven|
|org.springframework:spring-context|5.3.9|直接依赖|maven|
|org.apache.lucene:lucene-queryparser|8.11.1|间接依赖|maven|
|org.codehaus.jettison:jettison|1.1|间接依赖|maven|
|com.google.code.gson:gson|2.8.6|间接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.11|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.11|间接依赖|maven|
|io.prometheus:simpleclient_httpserver|0.4.0|直接依赖|maven|
|org.junit.jupiter:junit-jupiter-params|5.7.2|间接依赖|maven|
|org.apache.lucene:lucene-backward-codecs|8.11.1|间接依赖|maven|
|io.ebean:ebean-types|1.3|间接依赖|maven|
|com.oracle.database.security:osdt_core|21.1.0.0|间接依赖|maven|
|com.ibm.icu:icu4j|60.2|间接依赖|maven|
|com.alibaba.otter:canal.instance.core|1.1.7-SNAPSHOT|直接依赖|maven|
|org.apache.pulsar:pulsar-package-core|2.8.1|间接依赖|maven|
|com.alibaba.otter:canal.instance.manager|1.1.7-SNAPSHOT|直接依赖|maven|
|org.elasticsearch:elasticsearch-secure-sm|6.8.22|间接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.5|间接依赖|maven|
|org.apache.lucene:lucene-spatial|7.7.3|间接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.9.2|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.12.4|间接依赖|maven|
|javax.xml.stream:stax-api|1.0-2|间接依赖|maven|
|org.apache.hbase:hbase-metrics|1.4.0|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|2.7.5|间接依赖|maven|
|org.apache.avro:avro|1.7.7|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.9|间接依赖|maven|
|com.microsoft.sqlserver:mssql-jdbc|7.0.0.jre8|直接依赖|maven|
|org.junit.platform:junit-platform-commons|1.7.2|间接依赖|maven|
|org.springframework.boot:spring-boot-test-autoconfigure|2.5.4|间接依赖|maven|
|org.elasticsearch.plugin:lang-mustache-client|6.8.22|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.5.4|直接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.5.4|间接依赖|maven|
|org.springframework:spring-web|5.3.9|间接依赖|maven|
|com.alibaba.otter:canal.sink|1.1.7-SNAPSHOT|直接依赖|maven|
|org.apache.twill:twill-api|0.8.0|间接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-api|5.7.2|间接依赖|maven|
|commons-cli:commons-cli|1.2|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.69|间接依赖|maven|
|org.apache.curator:curator-framework|2.10.0|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|直接依赖|maven|
|org.apache.lucene:lucene-queries|7.7.3|间接依赖|maven|
|tomcat:jasper-compiler|5.5.23|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-smile|2.14.2|间接依赖|maven|
|com.sun.xml.bind:jaxb-impl|2.2.3-1|间接依赖|maven|
|org.apache.pulsar:pulsar-client-admin|2.8.1|直接依赖|maven|
|org.apache.lucene:lucene-sandbox|8.11.1|间接依赖|maven|
|io.netty:netty-common|4.1.32.Final|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.8.11|间接依赖|maven|
|org.apache.hbase:hbase-protocol|1.4.0|间接依赖|maven|
|org.springframework:spring-expression|5.3.9|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-common|2.7.4|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-engine|5.7.2|间接依赖|maven|
|org.apache.directory.server:apacheds-kerberos-codec|2.0.0-M15|间接依赖|maven|
|org.elasticsearch:elasticsearch-x-content|6.8.22|间接依赖|maven|
|org.elasticsearch:elasticsearch-secure-sm|7.17.9|间接依赖|maven|
|com.alibaba.otter:canal.server|1.1.7-SNAPSHOT|直接依赖|maven|
|com.oracle.database.jdbc:ojdbc6|11.2.0.4|直接依赖|maven|
|org.elasticsearch.plugin:transport-netty4-client|6.8.22|间接依赖|maven|
|org.skyscreamer:jsonassert|1.5.0|间接依赖|maven|
|com.alibaba.otter:canal.protocol|1.1.7-SNAPSHOT|直接依赖|maven|
|com.carrotsearch:hppc|0.7.1|间接依赖|maven|
|javax.ws.rs:javax.ws.rs-api|2.1|间接依赖|maven|
|/System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation||间接依赖||
|org.jruby.jcodings:jcodings|1.0.8|间接依赖|maven|
|org.junit.jupiter:junit-jupiter|5.7.2|间接依赖|maven|
|org.apache.rocketmq:rocketmq-client|4.8.0|直接依赖|maven|
|org.slf4j:slf4j-log4j12|1.7.10|间接依赖|maven|
|org.apache.lucene:lucene-misc|8.1.0|间接依赖|maven|
|it.unimi.dsi:fastutil|6.5.6|间接依赖|maven|
|org.apache.lucene:lucene-join|8.11.1|间接依赖|maven|
|com.jamesmurty.utils:java-xmlbuilder|0.4|间接依赖|maven|
|jakarta.ws.rs:jakarta.ws.rs-api|2.1.6|间接依赖|maven|
|org.iq80.snappy:snappy|0.3|间接依赖|maven|
|org.apache.hbase:hbase-common|1.4.0|间接依赖|maven|
|com.sun.jersey:jersey-core|1.9|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-app|2.7.4|间接依赖|maven|
|org.apache.hbase:hbase-hadoop-compat|1.4.0|间接依赖|maven|
|com.sun.activation:javax.activation|1.2.0|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.5.6|直接依赖|maven|
|org.apache.lucene:lucene-spatial3d|8.11.1|间接依赖|maven|
|com.tdunning:t-digest|3.2|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)