# linkedin/coral安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700571090769461248.svg)](https://www.murphysec.com/console/report/1700571090719129600/1700571090769461248)

仓库描述：Coral is a translation, analysis, and query rewrite engine for SQL and other relational languages.

仓库地址：[https://github.com/linkedin/coral](https://github.com/linkedin/coral)

| star：625 | watch：27 | fork：165 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-09 05:26:16 | 许可证：BSD-2-Clause |
| 最近检测时间：2023-09-10 03:18:40 | 组件总数：215 | 漏洞总数：104 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache HttpClient 中间人攻击漏洞|输入验证不恰当|[MPS-2014-4288](https://www.oscs1024.com/hd/MPS-2014-4288)|CVE-2012-6153|中危|
|Apache Groovy 代码注入漏洞|注入|[MPS-2015-3848](https://www.oscs1024.com/hd/MPS-2015-3848)|CVE-2015-3253|严重|
|多款Cisco产品Apache Commons Collections库任意代码执行漏洞|反序列化|[MPS-2015-6277](https://www.oscs1024.com/hd/MPS-2015-6277)|CVE-2015-6420|高危|
|Apache Hadoop 权限提升漏洞|访问控制不当|[MPS-2016-5884](https://www.oscs1024.com/hd/MPS-2016-5884)|CVE-2016-5393|高危|
|JCraft JSch 路径遍历漏洞|路径遍历|[MPS-2017-0498](https://www.oscs1024.com/hd/MPS-2017-0498)|CVE-2016-5725|中危|
|Apache Zookeeper 安全漏洞||[MPS-2017-11297](https://www.oscs1024.com/hd/MPS-2017-11297)|CVE-2017-5637|高危|
|Netty和Play Framework 输入验证错误漏洞|未授权敏感信息泄露|[MPS-2017-11682](https://www.oscs1024.com/hd/MPS-2017-11682)|CVE-2015-2156|高危|
|多款Red Hat产品代码问题漏洞|反序列化|[MPS-2017-12638](https://www.oscs1024.com/hd/MPS-2017-12638)|CVE-2015-7501|严重|
|Apache Hadoop 信息泄露漏洞|未授权敏感信息泄露|[MPS-2017-9901](https://www.oscs1024.com/hd/MPS-2017-9901)|CVE-2016-3086|严重|
|Apache Hadoop 信息泄漏漏洞|未授权敏感信息泄露|[MPS-2018-0896](https://www.oscs1024.com/hd/MPS-2018-0896)|CVE-2017-15713|中危|
|Apache Commons Compress 存在拒绝服务漏洞|不可达退出条件的循环（无限循环）|[MPS-2018-11233](https://www.oscs1024.com/hd/MPS-2018-11233)|CVE-2018-11771|中危|
|Apache Hive HiveServer2  访问控制不恰当漏洞|访问控制不当|[MPS-2018-14541](https://www.oscs1024.com/hd/MPS-2018-14541)|CVE-2018-11777|高危|
|Apache Hive  授权机制缺失漏洞|授权检查缺失|[MPS-2018-14542](https://www.oscs1024.com/hd/MPS-2018-14542)|CVE-2018-1314|中危|
|Apache Hadoop 路径遍历漏洞|路径遍历|[MPS-2018-14698](https://www.oscs1024.com/hd/MPS-2018-14698)|CVE-2018-8009|高危|
|Apache Hive 任意文件读取漏洞|未授权敏感信息泄露|[MPS-2018-4307](https://www.oscs1024.com/hd/MPS-2018-4307)|CVE-2018-1284|低危|
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|Apache Derby 权限许可和访问控制问题漏洞|访问控制不当|[MPS-2018-5754](https://www.oscs1024.com/hd/MPS-2018-5754)|CVE-2018-1313|中危|
|Apache Zookeeper 访问控制错误漏洞|授权检查缺失|[MPS-2018-6313](https://www.oscs1024.com/hd/MPS-2018-6313)|CVE-2018-8012|高危|
|Apache Thrift <0.12.0 绕过验证漏洞|证书验证不恰当|[MPS-2019-0104](https://www.oscs1024.com/hd/MPS-2019-0104)|CVE-2018-1320|高危|
|Apache Commons Beanutils 存在不可信数据的反序列化漏洞|反序列化|[MPS-2019-10233](https://www.oscs1024.com/hd/MPS-2019-10233)|CVE-2019-10086|高危|
|Netty 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2019-12064](https://www.oscs1024.com/hd/MPS-2019-12064)|CVE-2019-16869|高危|
|Red Hat JBoss Enterprise Application Platform 代码问题漏洞|反序列化|[MPS-2019-12470](https://www.oscs1024.com/hd/MPS-2019-12470)|CVE-2019-10202|严重|
|jackson-mapper-asl <=1.9.13 XXE 注入漏洞|XXE|[MPS-2019-15048](https://www.oscs1024.com/hd/MPS-2019-15048)|CVE-2019-10172|高危|
|Apache Log4j SocketServer反序列化漏洞|反序列化|[MPS-2019-17271](https://www.oscs1024.com/hd/MPS-2019-17271)|CVE-2019-17571|严重|
|Apache Zookeeper 授权问题漏洞|授权检查缺失|[MPS-2019-5668](https://www.oscs1024.com/hd/MPS-2019-5668)|CVE-2019-0201|中危|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|Apache HttpClient URI解析错误漏洞|XSS|[MPS-2020-17341](https://www.oscs1024.com/hd/MPS-2020-17341)|CVE-2020-13956|中危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2020-17486](https://www.oscs1024.com/hd/MPS-2020-17486)|CVE-2020-17527|高危|
|Apache Log4j2 SmtpAppender证书验证不当漏洞|证书验证不恰当|[MPS-2020-6684](https://www.oscs1024.com/hd/MPS-2020-6684)|CVE-2020-9488|低危|
|Apache Ant 临时文件不安全问题|将资源暴露给错误范围|[MPS-2020-7418](https://www.oscs1024.com/hd/MPS-2020-7418)|CVE-2020-1945|中危|
|Apache Tomcat 授权问题漏洞|身份验证不当|[MPS-2021-10264](https://www.oscs1024.com/hd/MPS-2021-10264)|CVE-2021-30640|中危|
|Apache Commons Compress 安存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10550](https://www.oscs1024.com/hd/MPS-2021-10550)|CVE-2021-35517|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10551](https://www.oscs1024.com/hd/MPS-2021-10551)|CVE-2021-35516|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10564](https://www.oscs1024.com/hd/MPS-2021-10564)|CVE-2021-36090|高危|
|Apache Commons Compress 无限循环漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-10565](https://www.oscs1024.com/hd/MPS-2021-10565)|CVE-2021-35515|高危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-1722](https://www.oscs1024.com/hd/MPS-2021-1722)|CVE-2021-24122|中危|
|Spring Framework <5.3.14 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18854](https://www.oscs1024.com/hd/MPS-2021-18854)|CVE-2021-22060|中危|
|Pivotal Spring Framework 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18890](https://www.oscs1024.com/hd/MPS-2021-18890)|CVE-2021-22096|中危|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|Apache Tomcat 信息泄露漏洞|HTTP请求走私|[MPS-2021-2309](https://www.oscs1024.com/hd/MPS-2021-2309)|CVE-2021-25122|高危|
|Apache Tomcat 远程代码执行漏洞|代码注入|[MPS-2021-2466](https://www.oscs1024.com/hd/MPS-2021-2466)|CVE-2021-25329|高危|
|Apache Hive 未授权访问 UDF 漏洞|关键功能的认证机制缺失|[MPS-2021-25837](https://www.oscs1024.com/hd/MPS-2021-25837)|CVE-2021-34538|高危|
|Apache Commons Net <3.9.0 存在FTP跳转攻击漏洞|未授权敏感信息泄露|[MPS-2021-28440](https://www.oscs1024.com/hd/MPS-2021-28440)|CVE-2021-37533|中危|
|Apache Tomcat 拒绝服务漏洞|拒绝服务|[MPS-2021-31848](https://www.oscs1024.com/hd/MPS-2021-31848)|CVE-2021-41079|高危|
|Quality Open Software logback JNDI注入漏洞|反序列化|[MPS-2021-33911](https://www.oscs1024.com/hd/MPS-2021-33911)|CVE-2021-42550|中危|
|thymeleaf-spring5 <3.0.13 存在命令注入漏洞|代码注入|[MPS-2021-35280](https://www.oscs1024.com/hd/MPS-2021-35280)|CVE-2021-43466|严重|
|Apache Tomcat 条件竞争漏洞|竞争条件|[MPS-2021-37218](https://www.oscs1024.com/hd/MPS-2021-37218)|CVE-2021-43980|低危|
|Apache Log4j JMSAppender反序列化漏洞||[MPS-2021-38359](https://www.oscs1024.com/hd/MPS-2021-38359)|CVE-2021-4104|高危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|Spring Framework权限许可和访问控制问题漏洞|权限管理不当|[MPS-2021-7485](https://www.oscs1024.com/hd/MPS-2021-7485)|CVE-2021-22118|高危|
|Jakarta Expression Language <=3.0.3 存在输入验证错误漏洞|表达式语言注入|[MPS-2021-7671](https://www.oscs1024.com/hd/MPS-2021-7671)|CVE-2021-28170|中危|
|Apache Tomcat 环境问题漏洞|HTTP请求走私|[MPS-2021-9711](https://www.oscs1024.com/hd/MPS-2021-9711)|CVE-2021-33037|中危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9827](https://www.oscs1024.com/hd/MPS-2021-9827)|CVE-2021-36373|中危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9847](https://www.oscs1024.com/hd/MPS-2021-9847)|CVE-2021-36374|中危|
|Vmware Spring Framework 安全漏洞|不加限制或调节的资源分配|[MPS-2022-1080](https://www.oscs1024.com/hd/MPS-2022-1080)|CVE-2022-22950|中危|
|Pivotal Spring Framework 安全限制绕过漏洞|大小写敏感处理不恰当|[MPS-2022-1098](https://www.oscs1024.com/hd/MPS-2022-1098)|CVE-2022-22968|中危|
|Spring Framework spring-beans 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1101](https://www.oscs1024.com/hd/MPS-2022-1101)|CVE-2022-22970|中危|
|org.apache.hive:hive-common 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11849](https://www.oscs1024.com/hd/MPS-2022-11849)||中危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|org.apache.commons:commons-dbcp2 存在信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-12024](https://www.oscs1024.com/hd/MPS-2022-12024)||低危|
|Apache Thrift <0.9.3 SSL DOS 和不安全协商漏洞|拒绝服务|[MPS-2022-12148](https://www.oscs1024.com/hd/MPS-2022-12148)||中危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|Apache Hadoop < 2.7.3 存在CSRF漏洞|CSRF|[MPS-2022-12308](https://www.oscs1024.com/hd/MPS-2022-12308)||中危|
|Logback SSL证书校验不当漏洞|中间人攻击|[MPS-2022-12411](https://www.oscs1024.com/hd/MPS-2022-12411)||中危|
|FasterXML Jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2022-12500](https://www.oscs1024.com/hd/MPS-2022-12500)||中危|
|Apache Commons Collections 远程代码执行漏洞|反序列化|[MPS-2022-12767](https://www.oscs1024.com/hd/MPS-2022-12767)||高危|
|Apache Tomcat 本地权限提升漏洞|检查时间与使用时间(TOCTOU)的竞争条件|[MPS-2022-1351](https://www.oscs1024.com/hd/MPS-2022-1351)|CVE-2022-23181|高危|
|org.json:json 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13520](https://www.oscs1024.com/hd/MPS-2022-13520)||高危|
|Apache Log4j JDBCAppender SQL注入漏洞|SQL注入|[MPS-2022-1444](https://www.oscs1024.com/hd/MPS-2022-1444)|CVE-2022-23305|严重|
|Apache Log4j Chainsaw反序列化漏洞|反序列化|[MPS-2022-1445](https://www.oscs1024.com/hd/MPS-2022-1445)|CVE-2022-23307|高危|
|Apache Log4j 反序列化漏洞|反序列化|[MPS-2022-1446](https://www.oscs1024.com/hd/MPS-2022-1446)|CVE-2022-23302|高危|
|Apache Hadoop 存在shell命令注入漏洞|参数注入或修改|[MPS-2022-4190](https://www.oscs1024.com/hd/MPS-2022-4190)|CVE-2022-25168|严重|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|Apache Calcite Avatica 代码注入漏洞|代码注入|[MPS-2022-51965](https://www.oscs1024.com/hd/MPS-2022-51965)|CVE-2022-36364|高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|Jettison <1.5.2 拒绝服务漏洞|拒绝服务|[MPS-2022-57067](https://www.oscs1024.com/hd/MPS-2022-57067)|CVE-2022-40150|高危|
|Jettison <1.5.1 拒绝服务漏洞|越界写入|[MPS-2022-57068](https://www.oscs1024.com/hd/MPS-2022-57068)|CVE-2022-40149|高危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
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
|Apache Ivy<2.5.2 存在XXE漏洞|输入验证不恰当|[MPS-2022-67125](https://www.oscs1024.com/hd/MPS-2022-67125)|CVE-2022-46751|中危|
|spring-beans 远程代码执行漏洞(Spring4Shell)|表达式语言注入|[MPS-2022-6820](https://www.oscs1024.com/hd/MPS-2022-6820)|CVE-2022-22965|严重|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|java-xmlbuilder 代码问题漏洞|XXE|[MPS-2023-5040](https://www.oscs1024.com/hd/MPS-2023-5040)|CVE-2014-125087|严重|
|Jettison 安全漏洞|未经控制的递归|[MPS-2023-8270](https://www.oscs1024.com/hd/MPS-2023-8270)|CVE-2023-1436|高危|
|jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2023-8438](https://www.oscs1024.com/hd/MPS-2023-8438)|CVE-2021-46877|中危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|Apache Tomcat FORM 重定向漏洞|跨站重定向|[MPS-uy56-j8e4](https://www.oscs1024.com/hd/MPS-uy56-j8e4)|CVE-2023-41080|低危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.apache.tomcat.embed:tomcat-embed-core|9.0.39|11.0.0-m6|间接依赖|强烈建议修复|C:0|H:5|M:3|L:2|
|com.google.protobuf:protobuf-java|3.6.1|3.21.7|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|commons-beanutils:commons-beanutils|1.7.0|1.9.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.hive:hive-exec|1.2.2|3.1.3|直接依赖|建议修复|C:0|H:2|M:1|L:1|
|org.codehaus.jettison:jettison|1.1|1.5.4|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|org.apache.commons:commons-compress|1.20|1.21|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|org.apache.zookeeper:zookeeper|3.4.6|3.5.5|直接依赖|建议修复|C:0|H:2|M:1|L:0|
|commons-collections:commons-collections|3.2.1|3.2.2|直接依赖|建议修复|C:1|H:2|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.14.1||间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13||直接依赖|建议修复|C:1|H:1|M:0|L:0|
|org.springframework:spring-webmvc|5.3.1|6.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-beans|5.3.1|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.thymeleaf:thymeleaf-spring5|3.0.11.RELEASE|3.0.13.RELEASE|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|log4j:log4j|1.2.17||直接依赖|建议修复|C:2|H:3|M:0|L:1|
|org.codehaus.groovy:groovy-all|2.1.6|2.4.4|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|io.netty:netty|3.7.0.Final|3.10.3.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|ch.qos.logback:logback-core|1.2.3|1.2.8|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.apache.calcite.avatica:avatica-core|1.15.0|1.22.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.27|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|com.jcraft:jsch|0.1.42|0.1.54|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.jamesmurty.utils:java-xmlbuilder|0.4|1.2|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.xerial.snappy:snappy-java|1.0.5|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.11.3|2.14.0-rc1|间接依赖|建议修复|C:0|H:1|M:5|L:0|
|org.yaml:snakeyaml|1.33|2.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-web|5.3.1|6.0.0|间接依赖|建议修复|C:1|H:1|M:0|L:0|
|org.apache.hadoop:hadoop-common|2.7.0|3.3.3|直接依赖|建议修复|C:3|H:2|M:1|L:0|
|org.springframework:spring-context|5.3.1|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|5.3.1|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.apache.derby:derby|10.10.2.0|10.14.2.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.commons:commons-dbcp2|2.8.0|2.9.0|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.springframework:spring-core|5.3.1|6.0.7|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|org.apache.thrift:libthrift|0.9.2|0.12.0|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.glassfish:jakarta.el|3.0.3|3.0.4|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.commons:commons-dbcp2|2.6.0|2.9.0|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.apache.hive:hive-common|1.2.2|2.2.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-net:commons-net|3.1|3.9.0|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.commons:commons-compress|1.4.1|1.21|直接依赖|可选修复|C:0|H:2|M:1|L:0|
|org.apache.hadoop:hadoop-yarn-common|2.6.0|2.7.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.code.gson:gson|2.2.4|2.8.9|直接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.hadoop:hadoop-yarn-common|2.7.0|2.7.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.json:json|20090211|20180130|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|commons-codec:commons-codec|1.12|1.13|直接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.springframework.boot:spring-boot-autoconfigure|2.4.0|3.0.7|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.guava:guava|19.0|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:2|L:1|
|org.apache.httpcomponents:httpclient|4.5.6|4.5.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.ant:ant|1.9.1|1.10.11|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|commons-io:commons-io|2.4|2.7|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-httpclient:commons-httpclient|3.1||直接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.code.gson:gson|2.8.6|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.ivy:ivy|2.5.1|2.5.2|直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|156|Low|
|自定义许可证|25|Low|
|LGPL-2.1|2|Medium|
|MIT|6|Low|
|EPL-1.0|3|Low|
|CDDL-1.1|8|Low|
|BSD-3-Clause|2|Low|
|EPL-2.0|2|Low|
|CDDL-1.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.apache.avro:avro|1.7.5|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.14.1|间接依赖|maven|
|org.apache.hive.shims:hive-shims-common|1.2.2|间接依赖|maven|
|org.tukaani:xz|1.0|间接依赖|maven|
|org.json:json|20090211|间接依赖|maven|
|commons-io:commons-io|2.4|直接依赖|maven|
|org.apache.directory.server:apacheds-i18n|2.0.0-M15|间接依赖|maven|
|org.unbescape:unbescape|1.1.6.RELEASE|间接依赖|maven|
|com.google.code.gson:gson|2.9.0|直接依赖|maven|
|org.apache.ant:ant|1.9.1|间接依赖|maven|
|org.datanucleus:datanucleus-rdbms|3.2.9|间接依赖|maven|
|org.codehaus.janino:janino|3.0.11|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.0.5|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|2.7.0|间接依赖|maven|
|jline:jline|0.9.94|间接依赖|maven|
|org.codehaus.jackson:jackson-xc|1.9.13|间接依赖|maven|
|org.apache.curator:curator-client|2.7.1|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.30|间接依赖|maven|
|org.apache.avro:avro|1.10.2|间接依赖|maven|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13|直接依赖|maven|
|commons-digester:commons-digester|1.8|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|jline:jline|2.12|间接依赖|maven|
|commons-dbcp:commons-dbcp|1.4|间接依赖|maven|
|org.springframework:spring-beans|5.3.1|间接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|log4j:apache-log4j-extras|1.2.17|间接依赖|maven|
|commons-httpclient:commons-httpclient|3.1|直接依赖|maven|
|commons-logging:commons-logging|1.2|直接依赖|maven|
|org.codehaus.janino:commons-compiler|3.1.2|间接依赖|maven|
|::coral-hive||直接依赖|maven|
|org.apache.ivy:ivy|2.5.1|直接依赖|maven|
|org.mortbay.jetty:jetty|6.1.26|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|2.6.0|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.39|间接依赖|maven|
|com.sun.jersey:jersey-server|1.9|直接依赖|maven|
|org.codehaus.janino:commons-compiler|3.0.11|间接依赖|maven|
|org.apache.hive.shims:hive-shims-0.20S|1.2.2|间接依赖|maven|
|org.apache.ant:ant-launcher|1.9.1|间接依赖|maven|
|org.apache.calcite.avatica:avatica-metrics|1.15.0|间接依赖|maven|
|com.yahoo.datasketches:sketches-core|0.9.0|间接依赖|maven|
|org.antlr:stringtemplate|3.2.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.11.3|间接依赖|maven|
|com.sun.jersey:jersey-client|1.9|间接依赖|maven|
|org.apache.hive.shims:hive-shims-0.23|1.2.2|间接依赖|maven|
|stax:stax-api|1.0.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.11.3|间接依赖|maven|
|org.apache.commons:commons-lang3|3.11|间接依赖|maven|
|com.linkedin.calcite:calcite-core|1.21.0.259|直接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.13.3|间接依赖|maven|
|commons-lang:commons-lang|2.6|直接依赖|maven|
|com.google.code.gson:gson|2.2.4|直接依赖|maven|
|org.apache.commons:commons-lang3|3.8|间接依赖|maven|
|org.apache.commons:commons-math3|3.1.1|直接依赖|maven|
|org.webjars.npm:viz.js-graphviz-java|2.1.3|间接依赖|maven|
|com.fasterxml.jackson:jackson-bom|2.14.1|间接依赖|maven|
|net.hydromatic:aggdesigner-algorithm|6.0|间接依赖|maven|
|::coral-trino||直接依赖|maven|
|org.apache.commons:commons-compress|1.4.1|直接依赖|maven|
|::shading:coral-trino-parser||直接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.30|间接依赖|maven|
|::coral-common||直接依赖|maven|
|com.google.protobuf:protobuf-java|3.6.1|直接依赖|maven|
|org.springframework.boot:spring-boot|2.4.0|间接依赖|maven|
|com.esotericsoftware.kryo:kryo|2.22|直接依赖|maven|
|org.springframework:spring-web|5.3.1|间接依赖|maven|
|com.google.inject:guice|3.0|间接依赖|maven|
|com.twitter:parquet-hadoop-bundle|1.6.0|间接依赖|maven|
|org.apache.derby:derby|10.14.2.0|间接依赖|maven|
|javax.transaction:jta|1.1|间接依赖|maven|
|org.fusesource.leveldbjni:leveldbjni-all|1.8|间接依赖|maven|
|org.yaml:snakeyaml|1.33|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.11.3|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.11.3|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.4.0|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-web-proxy|2.6.0|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.39|间接依赖|maven|
|org.apache.hive:hive-exec|1.2.2|直接依赖|maven|
|org.springframework:spring-jcl|5.3.1|间接依赖|maven|
|org.codehaus.janino:janino|3.1.2|间接依赖|maven|
|commons-beanutils:commons-beanutils-core|1.8.0|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|2.7.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.13.3|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|commons-pool:commons-pool|1.6|间接依赖|maven|
|:No dependencies||直接依赖|maven|
|org.apache.thrift:libthrift|0.9.2|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.10|间接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|xmlenc:xmlenc|0.52|直接依赖|maven|
|org.apache.calcite:calcite-avatica|1.2.0-incubating|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.14.1|间接依赖|maven|
|org.apache.commons:commons-dbcp2|2.6.0|间接依赖|maven|
|org.antlr:ST4|4.0.4|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|间接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.3|间接依赖|maven|
|org.apache.hive:hive-common|1.2.2|间接依赖|maven|
|com.google.guava:guava|19.0|直接依赖|maven|
|com.jcraft:jsch|0.1.42|直接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.9.13|直接依赖|maven|
|commons-net:commons-net|3.1|直接依赖|maven|
|org.apache.hive:hive-metastore|1.2.2|直接依赖|maven|
|org.datanucleus:datanucleus-core|3.2.10|间接依赖|maven|
|com.jolbox:bonecp|0.8.0.RELEASE|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.7.0|间接依赖|maven|
|org.apache.directory.api:api-util|1.0.0-M20|间接依赖|maven|
|javax.activation:activation|1.1|间接依赖|maven|
|org.antlr:antlr-runtime|3.4|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.4.0|直接依赖|maven|
|::coral-schema||直接依赖|maven|
|com.sun.xml.bind:jaxb-impl|2.2.3-1|间接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|org.apache.htrace:htrace-core|3.1.0-incubating|直接依赖|maven|
|org.codehaus.jettison:jettison|1.1|间接依赖|maven|
|org.apache.hive:hive-serde|1.2.2|间接依赖|maven|
|oro:oro|2.0.8|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.3|间接依赖|maven|
|org.apache.commons:commons-dbcp2|2.8.0|间接依赖|maven|
|::coral-incremental||直接依赖|maven|
|org.apache.curator:curator-framework|2.7.1|间接依赖|maven|
|net.sf.opencsv:opencsv|2.3|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.11.3|间接依赖|maven|
|com.jayway.jsonpath:json-path|2.4.0|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-applicationhistoryservice|2.6.0|间接依赖|maven|
|joda-time:joda-time|2.5|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.30|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.0|直接依赖|maven|
|org.apache.commons:commons-pool2|2.6.1|间接依赖|maven|
|org.antlr:antlr|3.4|直接依赖|maven|
|org.springframework:spring-expression|5.3.1|间接依赖|maven|
|com.jamesmurty.utils:java-xmlbuilder|0.4|间接依赖|maven|
|io.netty:netty|3.7.0.Final|间接依赖|maven|
|org.apache.commons:commons-compress|1.20|间接依赖|maven|
|com.linkedin.avroutil1:helper-all|0.2.117|直接依赖|maven|
|org.apache.directory.server:apacheds-kerberos-codec|2.0.0-M15|间接依赖|maven|
|org.slf4j:slf4j-log4j12|1.7.10|直接依赖|maven|
|commons-pool:commons-pool|1.5.4|间接依赖|maven|
|com.sun.jersey:jersey-json|1.9|直接依赖|maven|
|org.codehaus.jackson:jackson-jaxrs|1.9.13|间接依赖|maven|
|org.springframework:spring-aop|5.3.1|间接依赖|maven|
|org.springframework:spring-core|5.3.1|间接依赖|maven|
|com.esri.geometry:esri-geometry-api|2.2.0|间接依赖|maven|
|com.sun.jersey:jersey-core|1.9|直接依赖|maven|
|org.thymeleaf.extras:thymeleaf-extras-java8time|3.0.4.RELEASE|间接依赖|maven|
|javax.servlet:servlet-api|2.5|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-thymeleaf|2.4.0|直接依赖|maven|
|asm:asm|3.1|间接依赖|maven|
|com.sun.jersey.contribs:jersey-guice|1.9|间接依赖|maven|
|com.google.inject.extensions:guice-servlet|3.0|间接依赖|maven|
|net.java.dev.jets3t:jets3t|0.9.0|直接依赖|maven|
|org.apache.commons:commons-pool2|2.9.0|间接依赖|maven|
|org.apache.derby:derby|10.10.2.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.14.1|间接依赖|maven|
|org.springframework:spring-context|5.3.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.14.1|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.6|间接依赖|maven|
|commons-configuration:commons-configuration|1.6|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.11.3|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.3|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-common|2.6.0|间接依赖|maven|
|com.linkedin.calcite:calcite-linq4j|1.21.0.259|间接依赖|maven|
|org.yaml:snakeyaml|1.27|间接依赖|maven|
|org.glassfish:jakarta.el|3.0.3|间接依赖|maven|
|javax.xml.stream:stax-api|1.0-2|间接依赖|maven|
|guru.nidi.com.eclipsesource.j2v8:j2v8||间接依赖|maven|
|log4j:log4j|1.2.17|直接依赖|maven|
|org.apache.hive:hive-shims|1.2.2|间接依赖|maven|
|org.apache.thrift:libfb303|0.9.2|间接依赖|maven|
|org.thymeleaf:thymeleaf-spring5|3.0.11.RELEASE|间接依赖|maven|
|::coral-spark||直接依赖|maven|
|org.apache.hive:hive-ant|1.2.2|间接依赖|maven|
|org.apache.commons:commons-exec|1.3|间接依赖|maven|
|org.mortbay.jetty:jetty-util|6.1.26|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.25|直接依赖|maven|
|org.attoparser:attoparser|2.0.5.RELEASE|间接依赖|maven|
|guru.nidi:graphviz-java-all-j2v8|0.18.1|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-resourcemanager|2.6.0|间接依赖|maven|
|commons-codec:commons-codec|1.12|直接依赖|maven|
|org.apache.calcite.avatica:avatica-core|1.15.0|间接依赖|maven|
|javax.jdo:jdo-api|3.0.1|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|间接依赖|maven|
|com.yahoo.datasketches:memory|0.9.0|间接依赖|maven|
|org.apache.velocity:velocity|1.5|间接依赖|maven|
|org.apache.hadoop:hadoop-auth|2.7.0|直接依赖|maven|
|guru.nidi.com.kitfox:svgSalamander|1.1.3|间接依赖|maven|
|org.apache.curator:curator-recipes|2.7.1|直接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-core|2.7.0|直接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.4.0|间接依赖|maven|
|org.codehaus.groovy:groovy-all|2.1.6|间接依赖|maven|
|javax.servlet.jsp:jsp-api|2.1|直接依赖|maven|
|org.apache.hadoop:hadoop-annotations|2.7.0|直接依赖|maven|
|org.thymeleaf:thymeleaf|3.0.11.RELEASE|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.4.6|直接依赖|maven|
|org.apache.curator:apache-curator|2.6.0|间接依赖|maven|
|org.apache.hadoop:hadoop-common|2.7.0|直接依赖|maven|
|antlr:antlr|2.7.7|间接依赖|maven|
|com.google.code.gson:gson|2.8.6|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.4.0|间接依赖|maven|
|guru.nidi:graphviz-java|0.18.1|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.4.0|间接依赖|maven|
|commons-collections:commons-collections|3.2.1|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.4.0|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.11.3|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.13|间接依赖|maven|
|org.datanucleus:datanucleus-api-jdo|3.2.6|间接依赖|maven|
|commons-cli:commons-cli|1.2|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|2.6.0|间接依赖|maven|
|net.arnx:nashorn-promise|0.1.1|间接依赖|maven|
|org.sonatype.sisu.inject:cglib|2.2.1-v20090111|间接依赖|maven|
|org.apache.directory.api:api-asn1-api|1.0.0-M20|间接依赖|maven|
|org.apache.hive.shims:hive-shims-scheduler|1.2.2|间接依赖|maven|
|junit:junit|3.8.1|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.2.2|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)