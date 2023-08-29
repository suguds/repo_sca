# apache/doris安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696608424648142848.svg)](https://www.murphysec.com/console/report/1691873524820238336/1696608424648142848)

仓库描述：Apache Doris is an easy-to-use, high performance and unified analytics database.

仓库地址：[https://github.com/apache/doris](https://github.com/apache/doris)

| star：9262 | watch：269 | fork：2649 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-30 01:29:56 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-30 04:57:23 | 组件总数：1952 | 漏洞总数：339 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Mort Bay Jetty目录遍历漏洞|路径遍历|[MPS-2009-2320](https://www.oscs1024.com/hd/MPS-2009-2320)|CVE-2009-1523|中危|
|Mort Bay Jetty 输入验证错误漏洞|输入验证不恰当|[MPS-2010-0147](https://www.oscs1024.com/hd/MPS-2010-0147)|CVE-2009-4611|高危|
|Apache Hadoop 信息泄露漏洞|密码学问题|[MPS-2012-2233](https://www.oscs1024.com/hd/MPS-2012-2233)|CVE-2012-3376|高危|
|Apache Commons HttpClient Amazon FPS 输入验证错误漏洞|证书验证不恰当|[MPS-2012-4618](https://www.oscs1024.com/hd/MPS-2012-4618)|CVE-2012-5783|中危|
|Apache HttpClient 中间人攻击漏洞|输入验证不恰当|[MPS-2014-4288](https://www.oscs1024.com/hd/MPS-2014-4288)|CVE-2012-6153|中危|
|Hibernate Validator 认证绕过漏洞|认证绕过|[MPS-2014-5374](https://www.oscs1024.com/hd/MPS-2014-5374)|CVE-2014-3558|中危|
|Oracle MySQL Connectors组件SQL注入漏洞|SQL注入|[MPS-2015-2026](https://www.oscs1024.com/hd/MPS-2015-2026)|CVE-2015-2575|中危|
|Libcontainer和Docker Engine 权限许可和访问控制漏洞|在文件访问前对链接解析不恰当（链接跟随）|[MPS-2015-2409](https://www.oscs1024.com/hd/MPS-2015-2409)|CVE-2015-3627|高危|
|Docker Engine 权限许可和访问控制漏洞|权限、特权和访问控制|[MPS-2015-2412](https://www.oscs1024.com/hd/MPS-2015-2412)|CVE-2015-3631|低危|
|多款Cisco产品Apache Commons Collections库任意代码执行漏洞|反序列化|[MPS-2015-6277](https://www.oscs1024.com/hd/MPS-2015-6277)|CVE-2015-6420|高危|
|Apache Hadoop 信息泄露漏洞|未授权敏感信息泄露|[MPS-2016-1783](https://www.oscs1024.com/hd/MPS-2016-1783)|CVE-2015-1776|中危|
|Eclipse Jetty 信息泄露漏洞|未授权敏感信息泄露|[MPS-2016-5010](https://www.oscs1024.com/hd/MPS-2016-5010)|CVE-2015-2080|高危|
|Apache Hadoop 权限提升漏洞|访问控制不当|[MPS-2016-5884](https://www.oscs1024.com/hd/MPS-2016-5884)|CVE-2016-5393|高危|
|JCraft JSch 路径遍历漏洞|路径遍历|[MPS-2017-0498](https://www.oscs1024.com/hd/MPS-2017-0498)|CVE-2016-5725|中危|
|Square OkHttp 安全漏洞|证书验证不恰当|[MPS-2017-1023](https://www.oscs1024.com/hd/MPS-2017-1023)|CVE-2016-2402|中危|
|Google protobuf 缓冲区错误漏洞|越界写入|[MPS-2017-10841](https://www.oscs1024.com/hd/MPS-2017-10841)|CVE-2015-5237|高危|
|Apache Zookeeper 安全漏洞||[MPS-2017-11297](https://www.oscs1024.com/hd/MPS-2017-11297)|CVE-2017-5637|高危|
|Netty和Play Framework 输入验证错误漏洞|未授权敏感信息泄露|[MPS-2017-11682](https://www.oscs1024.com/hd/MPS-2017-11682)|CVE-2015-2156|高危|
|多款Red Hat产品代码问题漏洞|反序列化|[MPS-2017-12638](https://www.oscs1024.com/hd/MPS-2017-12638)|CVE-2015-7501|严重|
|Scala compilation daemon 安全漏洞|关键资源权限分配不当|[MPS-2017-12883](https://www.oscs1024.com/hd/MPS-2017-12883)|CVE-2017-15288|高危|
|GNU Libiberty 安全漏洞|输入验证不恰当|[MPS-2017-1331](https://www.oscs1024.com/hd/MPS-2017-1331)|CVE-2016-6131|高危|
|libiberty 数字错误漏洞||[MPS-2017-2066](https://www.oscs1024.com/hd/MPS-2017-2066)|CVE-2016-2226|高危|
|libiberty 安全漏洞|UAF|[MPS-2017-2070](https://www.oscs1024.com/hd/MPS-2017-2070)|CVE-2016-4487|中危|
|libiberty 安全漏洞|UAF|[MPS-2017-2071](https://www.oscs1024.com/hd/MPS-2017-2071)|CVE-2016-4488|中危|
|libiberty 数字错误漏洞|整数溢出或环绕|[MPS-2017-2072](https://www.oscs1024.com/hd/MPS-2017-2072)|CVE-2016-4489|中危|
|libiberty 数字错误漏洞|整数溢出或环绕|[MPS-2017-2073](https://www.oscs1024.com/hd/MPS-2017-2073)|CVE-2016-4490|中危|
|libiberty 安全漏洞|缓冲区溢出|[MPS-2017-2074](https://www.oscs1024.com/hd/MPS-2017-2074)|CVE-2016-4491|中危|
|libiberty 缓冲区错误漏洞|缓冲区溢出|[MPS-2017-2075](https://www.oscs1024.com/hd/MPS-2017-2075)|CVE-2016-4492|中危|
|libiberty 安全漏洞|越界读取|[MPS-2017-2076](https://www.oscs1024.com/hd/MPS-2017-2076)|CVE-2016-4493|中危|
|Apache Log4j 代码问题漏洞|反序列化|[MPS-2017-4319](https://www.oscs1024.com/hd/MPS-2017-4319)|CVE-2017-5645|严重|
|Oracle MySQL Connectors 访问限制绕过漏洞|访问控制不当|[MPS-2017-4684](https://www.oscs1024.com/hd/MPS-2017-4684)|CVE-2017-3523|高危|
|Oracle MySQL Connectors 安全漏洞|访问控制不当|[MPS-2017-4744](https://www.oscs1024.com/hd/MPS-2017-4744)|CVE-2017-3586|中危|
|Oracle MySQL Connectors 安全漏洞|访问控制不当|[MPS-2017-4746](https://www.oscs1024.com/hd/MPS-2017-4746)|CVE-2017-3589|低危|
|Apache Hadoop 跨站脚本漏洞|XSS|[MPS-2017-4858](https://www.oscs1024.com/hd/MPS-2017-4858)|CVE-2017-3161|中危|
|Apache Hadoop 输入验证错误漏洞|输入验证不恰当|[MPS-2017-4859](https://www.oscs1024.com/hd/MPS-2017-4859)|CVE-2017-3162|高危|
|Apache Hadoop 权限提升漏洞|特权问题|[MPS-2017-6059](https://www.oscs1024.com/hd/MPS-2017-6059)|CVE-2017-7669|高危|
|Jetty 信息泄露漏洞|通过差异性导致的信息暴露|[MPS-2017-6690](https://www.oscs1024.com/hd/MPS-2017-6690)|CVE-2017-9735|高危|
|Apache Tomcat SecurityManager绕过漏洞|访问控制不当|[MPS-2017-9011](https://www.oscs1024.com/hd/MPS-2017-9011)|CVE-2016-5018|严重|
|Apache Tomcat 访问限制绕过漏洞|访问控制不当|[MPS-2017-9027](https://www.oscs1024.com/hd/MPS-2017-9027)|CVE-2016-6796|高危|
|Nimbus JOSE+JWT 安全漏洞|对数据真实性的验证不充分|[MPS-2017-9387](https://www.oscs1024.com/hd/MPS-2017-9387)|CVE-2017-12972|高危|
|Nimbus JOSE+JWT 安全漏洞|完整性检查值验证不恰当|[MPS-2017-9388](https://www.oscs1024.com/hd/MPS-2017-9388)|CVE-2017-12973|低危|
|Nimbus JOSE+JWT<4.36  非法椭圆曲线攻击漏洞|密码学签名的验证不恰当|[MPS-2017-9389](https://www.oscs1024.com/hd/MPS-2017-9389)|CVE-2017-12974|高危|
|Apache Hadoop 信息泄露漏洞|未授权敏感信息泄露|[MPS-2017-9901](https://www.oscs1024.com/hd/MPS-2017-9901)|CVE-2016-3086|严重|
|FasterXML Jackson-databind 反序列化漏洞(dbcp2 gadget绕过)|反序列化|[MPS-2018-0362](https://www.oscs1024.com/hd/MPS-2018-0362)|CVE-2017-17485|严重|
|Apache Hadoop 信息泄漏漏洞|未授权敏感信息泄露|[MPS-2018-0896](https://www.oscs1024.com/hd/MPS-2018-0896)|CVE-2017-15713|中危|
|FasterXML jackson-databind 反序列化漏洞(Hibernate/iBatis gadget绕过)||[MPS-2018-0934](https://www.oscs1024.com/hd/MPS-2018-0934)|CVE-2018-5968|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不可达退出条件的循环（无限循环）|[MPS-2018-11233](https://www.oscs1024.com/hd/MPS-2018-11233)|CVE-2018-11771|中危|
|Oracle MySQL Connectors 访问控制错误漏洞|使用候选路径或通道进行的认证绕过|[MPS-2018-13771](https://www.oscs1024.com/hd/MPS-2018-13771)|CVE-2018-3258|高危|
|Apache Spark 输入验证错误漏洞|未授权敏感信息泄露|[MPS-2018-14084](https://www.oscs1024.com/hd/MPS-2018-14084)|CVE-2018-11804|高危|
|GNU Binutils 安全漏洞|不可达退出条件的循环（无限循环）|[MPS-2018-14162](https://www.oscs1024.com/hd/MPS-2018-14162)|CVE-2018-18700|中危|
|FasterXML Jackson-databind 反序列化漏洞(JdbcRowSetImpl gadget绕过)|反序列化|[MPS-2018-1438](https://www.oscs1024.com/hd/MPS-2018-1438)|CVE-2017-15095|严重|
|FasterXML Jackson-databind反序列化漏洞|反序列化|[MPS-2018-1439](https://www.oscs1024.com/hd/MPS-2018-1439)|CVE-2017-7525|严重|
|Apache Hadoop 路径遍历漏洞|路径遍历|[MPS-2018-14698](https://www.oscs1024.com/hd/MPS-2018-14698)|CVE-2018-8009|高危|
|Apache Spark 授权问题漏洞|代码注入|[MPS-2018-14969](https://www.oscs1024.com/hd/MPS-2018-14969)|CVE-2018-17190|严重|
|FasterXML jackson-databind 反序列化漏洞(c3p0 gadget绕过)||[MPS-2018-2477](https://www.oscs1024.com/hd/MPS-2018-2477)|CVE-2018-7489|严重|
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|Pivotal Spring Framework 5.0.5 未授权访问漏洞|授权检查错误|[MPS-2018-5951](https://www.oscs1024.com/hd/MPS-2018-5951)|CVE-2018-1258|高危|
|Apache Zookeeper 访问控制错误漏洞|授权检查缺失|[MPS-2018-6313](https://www.oscs1024.com/hd/MPS-2018-6313)|CVE-2018-8012|高危|
|Bouncy Castle 数据伪造问题漏洞|密码学签名的验证不恰当|[MPS-2018-6849](https://www.oscs1024.com/hd/MPS-2018-6849)|CVE-2016-1000338|高危|
|Bouncy Castle AES 密钥信息泄露漏洞|密码学问题|[MPS-2018-6922](https://www.oscs1024.com/hd/MPS-2018-6922)|CVE-2016-1000339|中危|
|Bouncy Castle 不安全加密漏洞|数据处理错误|[MPS-2018-6923](https://www.oscs1024.com/hd/MPS-2018-6923)|CVE-2016-1000340|高危|
|Bouncy Castle 签名信息泄露漏洞|7PK - 时间和状态|[MPS-2018-6924](https://www.oscs1024.com/hd/MPS-2018-6924)|CVE-2016-1000341|中危|
|Bouncy Castle <1.56 签名验证不当漏洞|密码学签名的验证不恰当|[MPS-2018-6925](https://www.oscs1024.com/hd/MPS-2018-6925)|CVE-2016-1000342|高危|
|Bouncy Castle 弱私钥漏洞|密码学问题|[MPS-2018-6926](https://www.oscs1024.com/hd/MPS-2018-6926)|CVE-2016-1000343|高危|
|Bouncy Castle 不安全加密漏洞|密码学问题|[MPS-2018-7042](https://www.oscs1024.com/hd/MPS-2018-7042)|CVE-2016-1000344|高危|
|Bouncy Castle 服务异常漏洞|7PK - 时间和状态|[MPS-2018-7043](https://www.oscs1024.com/hd/MPS-2018-7043)|CVE-2016-1000345|中危|
|Bouncy Castle 私钥信息泄露漏洞|密钥管理错误|[MPS-2018-7044](https://www.oscs1024.com/hd/MPS-2018-7044)|CVE-2016-1000346|低危|
|Bouncy Castle 不安全加密漏洞|密码学问题|[MPS-2018-7045](https://www.oscs1024.com/hd/MPS-2018-7045)|CVE-2016-1000352|高危|
|GNU Binutils GNU libiberty 安全漏洞|拒绝服务|[MPS-2018-8266](https://www.oscs1024.com/hd/MPS-2018-8266)|CVE-2018-12698|高危|
|Eclipse Jetty 缓存中毒漏洞|HTTP请求走私|[MPS-2018-8346](https://www.oscs1024.com/hd/MPS-2018-8346)|CVE-2017-7656|高危|
|Eclipse Jetty <9.4.11.v20180605 授权绕过漏洞|HTTP请求走私|[MPS-2018-8347](https://www.oscs1024.com/hd/MPS-2018-8347)|CVE-2017-7657|严重|
|Eclipse Jetty <9.4.11.v20180605 存在授权绕过漏洞|HTTP请求走私|[MPS-2018-8415](https://www.oscs1024.com/hd/MPS-2018-8415)|CVE-2017-7658|严重|
|Eclipse Jetty Server 系统路径泄露漏洞|未授权敏感信息泄露|[MPS-2018-8456](https://www.oscs1024.com/hd/MPS-2018-8456)|CVE-2018-12536|中危|
|FasterXML jackson-databind反序列化漏洞(slf4j-ext gadget绕过)|反序列化|[MPS-2019-0018](https://www.oscs1024.com/hd/MPS-2019-0018)|CVE-2018-14718|严重|
|FasterXML jackson-databind反序列化漏洞(blaze-ds-opt gadget绕过)|反序列化|[MPS-2019-0019](https://www.oscs1024.com/hd/MPS-2019-0019)|CVE-2018-14719|严重|
|FasterXML jackson-databind XXE漏洞(DRSHelper gadget绕过)||[MPS-2019-0020](https://www.oscs1024.com/hd/MPS-2019-0020)|CVE-2018-14720|严重|
|FasterXML Jackson-databind服务器端请求伪造漏洞(axis2-jaxws gadget绕过)|SSRF|[MPS-2019-0021](https://www.oscs1024.com/hd/MPS-2019-0021)|CVE-2018-14721|严重|
|FasterXML Jackson-databind代码问题漏洞(axis2-transport-jms gadget绕过)|反序列化|[MPS-2019-0023](https://www.oscs1024.com/hd/MPS-2019-0023)|CVE-2018-19360|严重|
|FasterXML Jackson-databind代码问题漏洞(openjpa gadget绕过)|反序列化|[MPS-2019-0024](https://www.oscs1024.com/hd/MPS-2019-0024)|CVE-2018-19361|严重|
|FasterXML Jackson-databind代码问题漏洞(jboss-common-core gadget绕过)|反序列化|[MPS-2019-0025](https://www.oscs1024.com/hd/MPS-2019-0025)|CVE-2018-19362|严重|
|Apache Thrift <0.12.0 绕过验证漏洞|证书验证不恰当|[MPS-2019-0104](https://www.oscs1024.com/hd/MPS-2019-0104)|CVE-2018-1320|高危|
|Apache Commons Beanutils 存在不可信数据的反序列化漏洞|反序列化|[MPS-2019-10233](https://www.oscs1024.com/hd/MPS-2019-10233)|CVE-2019-10086|高危|
|FasterXML jackson-databind 反序列化漏洞(HikariCP gadget绕过)|反序列化|[MPS-2019-11529](https://www.oscs1024.com/hd/MPS-2019-11529)|CVE-2019-14540|严重|
|FasterXML jackson-databind 反序列化漏洞(HikariCP gadget绕过)|反序列化|[MPS-2019-11533](https://www.oscs1024.com/hd/MPS-2019-11533)|CVE-2019-16335|严重|
|Netty 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2019-12064](https://www.oscs1024.com/hd/MPS-2019-12064)|CVE-2019-16869|高危|
|Red Hat JBoss Enterprise Application Platform 代码问题漏洞|反序列化|[MPS-2019-12470](https://www.oscs1024.com/hd/MPS-2019-12470)|CVE-2019-10202|严重|
|FasterXML jackson-databind 反序列化漏洞(commons-dbcp gadget绕过)|反序列化|[MPS-2019-12479](https://www.oscs1024.com/hd/MPS-2019-12479)|CVE-2019-16942|严重|
|FasterXML jackson-databind 反序列化漏洞(p6spy gadget绕过)|反序列化|[MPS-2019-12480](https://www.oscs1024.com/hd/MPS-2019-12480)|CVE-2019-16943|严重|
|FasterXML jackson-databind 反序列化漏洞(ehcache gadget绕过)|反序列化|[MPS-2019-12676](https://www.oscs1024.com/hd/MPS-2019-12676)|CVE-2019-17267|严重|
|FasterXML jackson-databind 反序列化漏洞(apache-log4j-extras gadget绕过)|反序列化|[MPS-2019-13103](https://www.oscs1024.com/hd/MPS-2019-13103)|CVE-2019-17531|严重|
|Connect2id Nimbus JOSE+JWT 存在对异常或异常情况的不当检查漏洞|对异常条件的处理不恰当|[MPS-2019-13154](https://www.oscs1024.com/hd/MPS-2019-13154)|CVE-2019-17195|中危|
|​ hibernate-validator  存在跨站脚本（XSS）漏洞|XSS|[MPS-2019-14389](https://www.oscs1024.com/hd/MPS-2019-14389)|CVE-2019-10219|中危|
|Apache Hadoop 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2019-1459](https://www.oscs1024.com/hd/MPS-2019-1459)|CVE-2018-1296|高危|
|jackson-mapper-asl <=1.9.13 XXE 注入漏洞|XXE|[MPS-2019-15048](https://www.oscs1024.com/hd/MPS-2019-15048)|CVE-2019-10172|高危|
|SnakeYAML <1.26 存在 Billion laughs 漏洞|拒绝服务|[MPS-2019-16129](https://www.oscs1024.com/hd/MPS-2019-16129)|CVE-2017-18640|高危|
|Apache Tomcat 授权问题漏洞|会话固定|[MPS-2019-16906](https://www.oscs1024.com/hd/MPS-2019-16906)|CVE-2019-17563|高危|
|Apache Tomcat 特权提升漏洞|权限管理不当|[MPS-2019-16926](https://www.oscs1024.com/hd/MPS-2019-16926)|CVE-2019-12418|高危|
|Apache Log4j SocketServer反序列化漏洞|反序列化|[MPS-2019-17271](https://www.oscs1024.com/hd/MPS-2019-17271)|CVE-2019-17571|严重|
|GNU Binutils 缓冲区错误漏洞|越界读取|[MPS-2019-1889](https://www.oscs1024.com/hd/MPS-2019-1889)|CVE-2019-9070|高危|
|FasterXML Jackson-databind反序列化漏洞（Jodd-db gadget绕过）|反序列化|[MPS-2019-2619](https://www.oscs1024.com/hd/MPS-2019-2619)|CVE-2018-12022|高危|
|FasterXML Jackson-databind反序列化漏洞(Oracle JDBC driver gadget绕过)|反序列化|[MPS-2019-2620](https://www.oscs1024.com/hd/MPS-2019-2620)|CVE-2018-12023|高危|
|Eclipse Jetty 跨站脚本漏洞|XSS|[MPS-2019-4268](https://www.oscs1024.com/hd/MPS-2019-4268)|CVE-2019-10241|中危|
|Eclipse Jetty 信息泄露漏洞|未授权敏感信息泄露|[MPS-2019-4270](https://www.oscs1024.com/hd/MPS-2019-4270)|CVE-2019-10247|中危|
|Oracle MySQL Connectors 输入验证错误漏洞|使用不兼容类型访问资源（类型混淆）|[MPS-2019-4430](https://www.oscs1024.com/hd/MPS-2019-4430)|CVE-2019-2692|中危|
|FasterXML jackson-databind 反序列化漏洞(mysql gadget绕过)|反序列化|[MPS-2019-5442](https://www.oscs1024.com/hd/MPS-2019-5442)|CVE-2019-12086|高危|
|Apache Zookeeper 授权问题漏洞|授权检查缺失|[MPS-2019-5668](https://www.oscs1024.com/hd/MPS-2019-5668)|CVE-2019-0201|中危|
|FasterXML jackson-databind 反序列化漏洞(jdom gadget绕过)|反序列化|[MPS-2019-6867](https://www.oscs1024.com/hd/MPS-2019-6867)|CVE-2019-12814|中危|
|FasterXML jackson-databind 反序列化漏洞(logback-classic gadget绕过)|反序列化|[MPS-2019-7047](https://www.oscs1024.com/hd/MPS-2019-7047)|CVE-2019-12384|中危|
|FasterXML jackson-databind 反序列化漏洞(iBatis gadget绕过)|反序列化|[MPS-2019-7711](https://www.oscs1024.com/hd/MPS-2019-7711)|CVE-2018-11307|严重|
|FasterXML jackson-databind 反序列化漏洞(ehcache gadget绕过)|动态确定对象属性修改的控制不恰当|[MPS-2019-8717](https://www.oscs1024.com/hd/MPS-2019-8717)|CVE-2019-14379|严重|
|FasterXML jackson-databind 信息泄露漏洞(logback gadget绕过)|反序列化|[MPS-2019-8770](https://www.oscs1024.com/hd/MPS-2019-8770)|CVE-2019-14439|高危|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|FasterXML jackson-databind反序列化漏洞(net.sf.ehcache gadget绕过)|反序列化|[MPS-2020-0063](https://www.oscs1024.com/hd/MPS-2020-0063)|CVE-2019-20330|严重|
|Pivotal Spring Framework <5.2.3.RELEASE 反射文件下载 (RFD) 漏洞|下载代码缺少完整性检查|[MPS-2020-0902](https://www.oscs1024.com/hd/MPS-2020-0902)|CVE-2020-5398|高危|
|Spring Framework CSRF 漏洞|CSRF|[MPS-2020-0927](https://www.oscs1024.com/hd/MPS-2020-0927)|CVE-2020-5397|中危|
|FasterXML jackson-databind反序列化漏洞(Anteros-DBCP gadget绕过)|反序列化|[MPS-2020-11987](https://www.oscs1024.com/hd/MPS-2020-11987)|CVE-2020-24616|高危|
|FasterXML jackson-databind 反序列化漏洞(pastdev gadget绕过)|反序列化|[MPS-2020-13151](https://www.oscs1024.com/hd/MPS-2020-13151)|CVE-2020-24750|高危|
|Netty <=4.1.43.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1320](https://www.oscs1024.com/hd/MPS-2020-1320)|CVE-2020-7238|高危|
|Pivotal Spring Framework 反射文件下载 (RFD) 漏洞|路径遍历|[MPS-2020-13322](https://www.oscs1024.com/hd/MPS-2020-13322)|CVE-2020-5421|中危|
|Apache Hadoop授权问题漏洞|身份验证不当|[MPS-2020-13793](https://www.oscs1024.com/hd/MPS-2020-13793)|CVE-2018-11765|中危|
|Apache Calcite 访问控制错误漏洞|关键功能的认证机制缺失|[MPS-2020-14130](https://www.oscs1024.com/hd/MPS-2020-14130)|CVE-2020-13955|中危|
|MyBatis <3.5.6 存在反序列化漏洞|反序列化|[MPS-2020-14133](https://www.oscs1024.com/hd/MPS-2020-14133)|CVE-2020-26945|高危|
|Junit 信息泄露漏洞|不安全的临时文件|[MPS-2020-15183](https://www.oscs1024.com/hd/MPS-2020-15183)|CVE-2020-15250|中危|
|Netty <4.1.44.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1526](https://www.oscs1024.com/hd/MPS-2020-1526)|CVE-2019-20444|严重|
|Netty <4.1.44.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1527](https://www.oscs1024.com/hd/MPS-2020-1527)|CVE-2019-20445|严重|
|Apache Tomcat HTTP请求走私漏洞|HTTP请求走私|[MPS-2020-15344](https://www.oscs1024.com/hd/MPS-2020-15344)|CVE-2020-13943|中危|
|Eclipse Jetty 权限提升漏洞|权限、特权和访问控制|[MPS-2020-15633](https://www.oscs1024.com/hd/MPS-2020-15633)|CVE-2020-27216|高危|
|Elasticsearch 存在权限管理不恰当漏洞|权限管理不当|[MPS-2020-15777](https://www.oscs1024.com/hd/MPS-2020-15777)|CVE-2020-7020|低危|
|Bouncy Castle 私钥信息泄漏漏洞|通过差异性导致的信息暴露|[MPS-2020-16513](https://www.oscs1024.com/hd/MPS-2020-16513)|CVE-2020-26939|中危|
|Apache HttpClient URI解析错误漏洞|XSS|[MPS-2020-17341](https://www.oscs1024.com/hd/MPS-2020-17341)|CVE-2020-13956|中危|
|FasterXML jackson-databind 代码问题漏洞|XXE|[MPS-2020-17358](https://www.oscs1024.com/hd/MPS-2020-17358)|CVE-2020-25649|高危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2020-17486](https://www.oscs1024.com/hd/MPS-2020-17486)|CVE-2020-17527|高危|
|Eclipse Jetty HTTP 请求走私漏洞|在释放前未清除敏感信息|[MPS-2020-17594](https://www.oscs1024.com/hd/MPS-2020-17594)|CVE-2020-27218|中危|
|FasterXML jackson-databind 反序列化漏洞(commons-dbcp2 gadget绕过)|反序列化|[MPS-2020-17696](https://www.oscs1024.com/hd/MPS-2020-17696)|CVE-2020-35490|高危|
|FasterXML jackson-databind 反序列化漏洞(commons-dbcp2 gadget绕过)|反序列化|[MPS-2020-17697](https://www.oscs1024.com/hd/MPS-2020-17697)|CVE-2020-35491|高危|
|Bouncy Castle 认证绕过漏洞|使用错误因素进行比较|[MPS-2020-17843](https://www.oscs1024.com/hd/MPS-2020-17843)|CVE-2020-28052|高危|
|FasterXML jackson-databind 反序列化漏洞(glassfish gadget绕过)|反序列化|[MPS-2020-18089](https://www.oscs1024.com/hd/MPS-2020-18089)|CVE-2020-35728|高危|
|FasterXML jackson-databind 反序列化漏洞(xbean-reflect gadget绕过)|反序列化|[MPS-2020-2030](https://www.oscs1024.com/hd/MPS-2020-2030)|CVE-2020-8840|严重|
|FasterXML jackson-databind 反序列化漏洞(ignite-jta gadget绕过)|反序列化|[MPS-2020-24779](https://www.oscs1024.com/hd/MPS-2020-24779)|CVE-2020-10650|高危|
|Apache Tomcat 权限管理不当漏洞|权限管理不当|[MPS-2020-2841](https://www.oscs1024.com/hd/MPS-2020-2841)|CVE-2020-1938|严重|
|FasterXML jackson-databind 代码问题漏洞|反序列化|[MPS-2020-3040](https://www.oscs1024.com/hd/MPS-2020-3040)|CVE-2020-9546|严重|
|FasterXML jackson-databind 反序列化漏洞(JtaTransactionConfig gadget绕过)|反序列化|[MPS-2020-3041](https://www.oscs1024.com/hd/MPS-2020-3041)|CVE-2020-9547|严重|
|FasterXML jackson-databind反序列化漏洞(anteros-core gadget绕过)|反序列化|[MPS-2020-3042](https://www.oscs1024.com/hd/MPS-2020-3042)|CVE-2020-9548|严重|
|FasterXML jackson-databind 反序列化漏洞(commons-configuration gadget绕过)|反序列化|[MPS-2020-3075](https://www.oscs1024.com/hd/MPS-2020-3075)|CVE-2019-14892|严重|
|FasterXML Jackson-databind反序列化漏洞(xalan2 gadget绕过)|反序列化|[MPS-2020-3094](https://www.oscs1024.com/hd/MPS-2020-3094)|CVE-2019-14893|严重|
|mysql:mysql-connector-java <8.0.27 存在 XXE 漏洞|XXE|[MPS-2020-38350](https://www.oscs1024.com/hd/MPS-2020-38350)|CVE-2021-2471|中危|
|Fastjson <=1.2.68 远程代码执行漏洞|使用外部可控制的输入来选择类或代码（不安全的反射）|[MPS-2020-39708](https://www.oscs1024.com/hd/MPS-2020-39708)||严重|
|Fastjson < 1.2.67远程命令执行漏洞|反序列化|[MPS-2020-40828](https://www.oscs1024.com/hd/MPS-2020-40828)||高危|
|FasterXML jackson-databind反序列化漏洞(aries.transaction.jms gadget绕过)|反序列化|[MPS-2020-4131](https://www.oscs1024.com/hd/MPS-2020-4131)|CVE-2020-10672|高危|
|FasterXML jackson-databind反序列化漏洞(caucho-quercus gadget绕过)|反序列化|[MPS-2020-4132](https://www.oscs1024.com/hd/MPS-2020-4132)|CVE-2020-10673|高危|
|FasterXML jackson-databind反序列化漏洞(bus-proxy gadget绕过)|反序列化|[MPS-2020-4658](https://www.oscs1024.com/hd/MPS-2020-4658)|CVE-2020-10968|高危|
|FasterXML jackson-databind反序列化漏洞(javax.swing gadget绕过)|反序列化|[MPS-2020-4659](https://www.oscs1024.com/hd/MPS-2020-4659)|CVE-2020-10969|高危|
|FasterXML jackson-databind反序列化漏洞(activemq gadget绕过)|反序列化|[MPS-2020-4754](https://www.oscs1024.com/hd/MPS-2020-4754)|CVE-2020-11111|高危|
|FasterXML jackson-databind反序列化漏洞(commons-proxy gadget绕过)|反序列化|[MPS-2020-4755](https://www.oscs1024.com/hd/MPS-2020-4755)|CVE-2020-11112|高危|
|FasterXML jackson-databind反序列化漏洞(openjpa gadget绕过)|反序列化|[MPS-2020-4756](https://www.oscs1024.com/hd/MPS-2020-4756)|CVE-2020-11113|高危|
|Elasticsearch  API 密钥权限提升漏洞|权限管理不当|[MPS-2020-4780](https://www.oscs1024.com/hd/MPS-2020-4780)|CVE-2020-7009|高危|
|Netty ZlibDecoders 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2020-5127](https://www.oscs1024.com/hd/MPS-2020-5127)|CVE-2020-11612|高危|
|FasterXML jackson-databind 反序列化漏洞(spring-aop gadget绕过)|反序列化|[MPS-2020-5138](https://www.oscs1024.com/hd/MPS-2020-5138)|CVE-2020-11619|高危|
|FasterXML jackson-databind 反序列化漏洞(commons-jelly gadget绕过)|反序列化|[MPS-2020-5139](https://www.oscs1024.com/hd/MPS-2020-5139)|CVE-2020-11620|高危|
|Apache Log4j2 SmtpAppender证书验证不当漏洞|证书验证不恰当|[MPS-2020-6684](https://www.oscs1024.com/hd/MPS-2020-6684)|CVE-2020-9488|低危|
|hibernate-validator 存在输入验证错误漏洞|代码注入|[MPS-2020-7077](https://www.oscs1024.com/hd/MPS-2020-7077)|CVE-2020-10693|中危|
|Apache Ant 临时文件不安全问题|将资源暴露给错误范围|[MPS-2020-7418](https://www.oscs1024.com/hd/MPS-2020-7418)|CVE-2020-1945|中危|
|Apache Tomcat 远程代码执行漏洞|反序列化|[MPS-2020-7626](https://www.oscs1024.com/hd/MPS-2020-7626)|CVE-2020-9484|高危|
|Elasticsearch 权限管理不当漏洞|权限管理不当|[MPS-2020-8144](https://www.oscs1024.com/hd/MPS-2020-8144)|CVE-2020-7014|高危|
|FasterXML jackson-databind反序列化漏洞(oracle-aqjms gadget绕过)|反序列化|[MPS-2020-8801](https://www.oscs1024.com/hd/MPS-2020-8801)|CVE-2020-14061|高危|
|FasterXML jackson-databind反序列化漏洞(xalan2 gadget绕过)|反序列化|[MPS-2020-8802](https://www.oscs1024.com/hd/MPS-2020-8802)|CVE-2020-14062|高危|
|FasterXML jackson-databind反序列化漏洞(apache drill gadget绕过)|反序列化|[MPS-2020-8803](https://www.oscs1024.com/hd/MPS-2020-8803)|CVE-2020-14060|高危|
|FasterXML jackson-databind代码问题漏洞(jsecurity gadget绕过)|反序列化|[MPS-2020-8911](https://www.oscs1024.com/hd/MPS-2020-8911)|CVE-2020-14195|高危|
|Apache Spark 授权问题漏洞|关键功能的认证机制缺失|[MPS-2020-9387](https://www.oscs1024.com/hd/MPS-2020-9387)|CVE-2020-9480|严重|
|Apache Tomcat 拒绝服务漏洞|拒绝服务|[MPS-2020-9541](https://www.oscs1024.com/hd/MPS-2020-9541)|CVE-2020-11996|高危|
|FasterXML jackson-databind 反序列化漏洞(DBCP gadget绕过)|反序列化|[MPS-2021-0202](https://www.oscs1024.com/hd/MPS-2021-0202)|CVE-2020-36179|高危|
|FasterXML jackson-databind 反序列化漏洞(DBCP gadget绕过)|反序列化|[MPS-2021-0203](https://www.oscs1024.com/hd/MPS-2021-0203)|CVE-2020-36181|高危|
|FasterXML jackson-databind 反序列化漏洞(DBCP gadget绕过)|反序列化|[MPS-2021-0204](https://www.oscs1024.com/hd/MPS-2021-0204)|CVE-2020-36180|高危|
|FasterXML jackson-databind 反序列化漏洞(tomcat-dbcp gadget绕过)|反序列化|[MPS-2021-0205](https://www.oscs1024.com/hd/MPS-2021-0205)|CVE-2020-36182|高危|
|FasterXML jackson-databind 反序列化漏洞(docx4j gadget绕过)|反序列化|[MPS-2021-0206](https://www.oscs1024.com/hd/MPS-2021-0206)|CVE-2020-36183|高危|
|FasterXML jackson-databind 反序列化漏洞(tomcat-dbcp gadget绕过)|反序列化|[MPS-2021-0207](https://www.oscs1024.com/hd/MPS-2021-0207)|CVE-2020-36184|高危|
|FasterXML jackson-databind 反序列化漏洞(tomcat-dbcp gadget绕过)|反序列化|[MPS-2021-0208](https://www.oscs1024.com/hd/MPS-2021-0208)|CVE-2020-36185|高危|
|FasterXML jackson-databind 反序列化漏洞(naming-factory-dbcp gadget绕过)|反序列化|[MPS-2021-0209](https://www.oscs1024.com/hd/MPS-2021-0209)|CVE-2020-36186|高危|
|FasterXML jackson-databind 反序列化漏洞(naming-factory-dbcp gadget绕过)|反序列化|[MPS-2021-0210](https://www.oscs1024.com/hd/MPS-2021-0210)|CVE-2020-36187|高危|
|FasterXML jackson-databind 反序列化漏洞(newrelic-agent gadget绕过)|反序列化|[MPS-2021-0211](https://www.oscs1024.com/hd/MPS-2021-0211)|CVE-2020-36188|高危|
|FasterXML jackson-databind 反序列化漏洞(newrelic-agent gadget绕过)|反序列化|[MPS-2021-0212](https://www.oscs1024.com/hd/MPS-2021-0212)|CVE-2020-36189|高危|
|Apache Tomcat 授权问题漏洞|身份验证不当|[MPS-2021-10264](https://www.oscs1024.com/hd/MPS-2021-10264)|CVE-2021-30640|中危|
|Apache Commons Compress 安存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10550](https://www.oscs1024.com/hd/MPS-2021-10550)|CVE-2021-35517|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10551](https://www.oscs1024.com/hd/MPS-2021-10551)|CVE-2021-35516|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10564](https://www.oscs1024.com/hd/MPS-2021-10564)|CVE-2021-36090|高危|
|Apache Commons Compress 无限循环漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-10565](https://www.oscs1024.com/hd/MPS-2021-10565)|CVE-2021-35515|高危|
|Eclipse Jetty 编码字符敏感信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-10800](https://www.oscs1024.com/hd/MPS-2021-10800)|CVE-2021-34429|中危|
|JetBrains Kotlin <1.4.21 不正确的默认权限漏洞|缺省权限不正确|[MPS-2021-1082](https://www.oscs1024.com/hd/MPS-2021-1082)|CVE-2020-29582|中危|
|Elasticsearch 资源管理错误漏洞|未经控制的递归|[MPS-2021-11043](https://www.oscs1024.com/hd/MPS-2021-11043)|CVE-2021-22144|中危|
|Elasticsearch 日志信息泄露漏洞|日志敏感信息泄露|[MPS-2021-1485](https://www.oscs1024.com/hd/MPS-2021-1485)|CVE-2020-7021|中危|
|Netty <4.1.59.Final 存在不安全的临时文件漏洞||[MPS-2021-1580](https://www.oscs1024.com/hd/MPS-2021-1580)|CVE-2021-21290|中危|
|FasterXML jackson-databind 反序列化漏洞(javax.swing gadget绕过)|反序列化|[MPS-2021-1625](https://www.oscs1024.com/hd/MPS-2021-1625)|CVE-2021-20190|高危|
|Apache Hadoop 权限管理不当漏洞|授权检查错误|[MPS-2021-1705](https://www.oscs1024.com/hd/MPS-2021-1705)|CVE-2020-9492|高危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-1722](https://www.oscs1024.com/hd/MPS-2021-1722)|CVE-2021-24122|中危|
|Spring Framework <5.3.14 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18854](https://www.oscs1024.com/hd/MPS-2021-18854)|CVE-2021-22060|中危|
|Pivotal Spring Framework 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18890](https://www.oscs1024.com/hd/MPS-2021-18890)|CVE-2021-22096|中危|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|FasterXML jackson-dataformat-cbor 内存耗尽漏洞|不加限制或调节的资源分配|[MPS-2021-1998](https://www.oscs1024.com/hd/MPS-2021-1998)|CVE-2020-28491|高危|
|Apache Hadoop YARN 远程代码执行漏洞|代码注入|[MPS-2021-20833](https://www.oscs1024.com/hd/MPS-2021-20833)|CVE-2021-25642|严重|
|netplex json-smart-v  分布式拒绝服务攻击|对因果或异常条件的不恰当检查|[MPS-2021-2102](https://www.oscs1024.com/hd/MPS-2021-2102)|CVE-2021-27568|严重|
|Apache Tomcat 信息泄露漏洞|HTTP请求走私|[MPS-2021-2309](https://www.oscs1024.com/hd/MPS-2021-2309)|CVE-2021-25122|高危|
|io.netty:netty-codec-http2 <4.1.60.Final 存在 http 请求走私漏洞|HTTP请求走私|[MPS-2021-2435](https://www.oscs1024.com/hd/MPS-2021-2435)|CVE-2021-21295|中危|
|Apache Tomcat 远程代码执行漏洞|代码注入|[MPS-2021-2466](https://www.oscs1024.com/hd/MPS-2021-2466)|CVE-2021-25329|高危|
|Alibaba Druid 目录遍历漏洞|路径遍历|[MPS-2021-25327](https://www.oscs1024.com/hd/MPS-2021-25327)|CVE-2021-33800|高危|
|Eclipse Jetty <11.0.1 拒绝服务漏洞|拒绝服务|[MPS-2021-2571](https://www.oscs1024.com/hd/MPS-2021-2571)|CVE-2020-27223|中危|
|Apache Hive 未授权访问 UDF 漏洞|关键功能的认证机制缺失|[MPS-2021-25837](https://www.oscs1024.com/hd/MPS-2021-25837)|CVE-2021-34538|高危|
|Netty Bzip2Decoder 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28116](https://www.oscs1024.com/hd/MPS-2021-28116)|CVE-2021-37136|高危|
|Netty 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28117](https://www.oscs1024.com/hd/MPS-2021-28117)|CVE-2021-37137|高危|
|Apache Commons Net <3.9.0 存在FTP跳转攻击漏洞|未授权敏感信息泄露|[MPS-2021-28440](https://www.oscs1024.com/hd/MPS-2021-28440)|CVE-2021-37533|中危|
|Apache Kafka 存在时序攻击漏洞|通过差异性导致的信息暴露|[MPS-2021-28892](https://www.oscs1024.com/hd/MPS-2021-28892)|CVE-2021-38153|中危|
|Apache Spark <3.1.3 存在信息泄漏漏洞|使用捕获-重放进行的认证绕过|[MPS-2021-28996](https://www.oscs1024.com/hd/MPS-2021-28996)|CVE-2021-38296|高危|
|Apache Tomcat 拒绝服务漏洞|拒绝服务|[MPS-2021-31848](https://www.oscs1024.com/hd/MPS-2021-31848)|CVE-2021-41079|高危|
|GNU libiberty 缓冲区错误漏洞|缓冲区溢出|[MPS-2021-32366](https://www.oscs1024.com/hd/MPS-2021-32366)|CVE-2021-3826|高危|
|Quality Open Software logback JNDI注入漏洞|反序列化|[MPS-2021-33911](https://www.oscs1024.com/hd/MPS-2021-33911)|CVE-2021-42550|中危|
| io.netty:netty-codec-http2 <4.1.61.Final 存在 http 请求走私漏洞|HTTP请求走私|[MPS-2021-3565](https://www.oscs1024.com/hd/MPS-2021-3565)|CVE-2021-21409|中危|
|Oracle MySQL 的 MySQL Connectors 存在授权不当漏洞|授权机制不恰当|[MPS-2021-36587](https://www.oscs1024.com/hd/MPS-2021-36587)|CVE-2022-21363|中危|
|Netty <4.1.71.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2021-36922](https://www.oscs1024.com/hd/MPS-2021-36922)|CVE-2021-43797|中危|
|Apache Tomcat 条件竞争漏洞|竞争条件|[MPS-2021-37218](https://www.oscs1024.com/hd/MPS-2021-37218)|CVE-2021-43980|低危|
|Apache Log4j2 远程代码执行漏洞|反序列化|[MPS-2021-38241](https://www.oscs1024.com/hd/MPS-2021-38241)|CVE-2021-44228|严重|
|Apache Log4j2 JDBC Appender远程代码执行漏洞|代码注入|[MPS-2021-38327](https://www.oscs1024.com/hd/MPS-2021-38327)|CVE-2021-44832|中危|
|Apache Log4j JMSAppender反序列化漏洞||[MPS-2021-38359](https://www.oscs1024.com/hd/MPS-2021-38359)|CVE-2021-4104|高危|
|Eclipse Jetty 资源管理错误漏洞|对异常条件的处理不恰当|[MPS-2021-3864](https://www.oscs1024.com/hd/MPS-2021-3864)|CVE-2021-28165|高危|
|Apache Log4j2 基于上下文查找的远程代码执行漏洞|反序列化|[MPS-2021-38665](https://www.oscs1024.com/hd/MPS-2021-38665)|CVE-2021-45046|严重|
|Apache Log4j2 自引用拒绝服务漏洞|未经控制的递归|[MPS-2021-38752](https://www.oscs1024.com/hd/MPS-2021-38752)|CVE-2021-45105|中危|
|Eclipse Jetty <9.4.39.v20210325 权限绕过漏洞|授权检查错误|[MPS-2021-3877](https://www.oscs1024.com/hd/MPS-2021-3877)|CVE-2021-28164|中危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|Elasticsearch 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-6747](https://www.oscs1024.com/hd/MPS-2021-6747)|CVE-2021-22137|中危|
|Elasticsearch 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-6749](https://www.oscs1024.com/hd/MPS-2021-6749)|CVE-2021-22135|中危|
|Bouncy Castle 私钥信息泄露漏洞|竞争条件|[MPS-2021-7064](https://www.oscs1024.com/hd/MPS-2021-7064)|CVE-2020-15522|中危|
|Spring Framework权限许可和访问控制问题漏洞|权限管理不当|[MPS-2021-7485](https://www.oscs1024.com/hd/MPS-2021-7485)|CVE-2021-22118|高危|
|Jakarta Expression Language <=3.0.3 存在输入验证错误漏洞|表达式语言注入|[MPS-2021-7671](https://www.oscs1024.com/hd/MPS-2021-7671)|CVE-2021-28170|中危|
|json-smart 存在拒绝服务漏洞|越界写入|[MPS-2021-7737](https://www.oscs1024.com/hd/MPS-2021-7737)|CVE-2021-31684|高危|
|JDOM 存在 XXE 注入漏洞|XXE|[MPS-2021-8350](https://www.oscs1024.com/hd/MPS-2021-8350)|CVE-2021-33813|高危|
|Eclipse Jetty 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-8397](https://www.oscs1024.com/hd/MPS-2021-8397)|CVE-2021-28169|中危|
|Eclipse Jetty 存在信息泄露漏洞|不充分的会话过期机制|[MPS-2021-8884](https://www.oscs1024.com/hd/MPS-2021-8884)|CVE-2021-34428|低危|
|Apache Tomcat 环境问题漏洞|HTTP请求走私|[MPS-2021-9711](https://www.oscs1024.com/hd/MPS-2021-9711)|CVE-2021-33037|中危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9827](https://www.oscs1024.com/hd/MPS-2021-9827)|CVE-2021-36373|中危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9847](https://www.oscs1024.com/hd/MPS-2021-9847)|CVE-2021-36374|中危|
|Red Hat XNIO 资源错误分配漏洞|不加限制或调节的资源分配|[MPS-2022-0191](https://www.oscs1024.com/hd/MPS-2022-0191)|CVE-2022-0084|高危|
|Vmware Spring Framework 安全漏洞|不加限制或调节的资源分配|[MPS-2022-1080](https://www.oscs1024.com/hd/MPS-2022-1080)|CVE-2022-22950|中危|
|Pivotal Spring Framework 安全限制绕过漏洞|大小写敏感处理不恰当|[MPS-2022-1098](https://www.oscs1024.com/hd/MPS-2022-1098)|CVE-2022-22968|中危|
|Spring Framework spring-beans 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1101](https://www.oscs1024.com/hd/MPS-2022-1101)|CVE-2022-22970|中危|
|AWS SDK for Java 路径遍历漏洞|路径遍历|[MPS-2022-11189](https://www.oscs1024.com/hd/MPS-2022-11189)|CVE-2022-31159|高危|
|Fastjson < 1.2.83 任意代码执行漏洞|反序列化|[MPS-2022-11320](https://www.oscs1024.com/hd/MPS-2022-11320)|CVE-2022-25845|高危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|com.fasterxml.jackson.core:jackson-core 存在资源管理错误漏洞|资源管理错误|[MPS-2022-11944](https://www.oscs1024.com/hd/MPS-2022-11944)||中危|
|com.nimbusds:nimbus-jose-jwt <4.34.2存在信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-11950](https://www.oscs1024.com/hd/MPS-2022-11950)||高危|
|org.apache.commons:commons-dbcp2 存在信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-12024](https://www.oscs1024.com/hd/MPS-2022-12024)||低危|
|io.netty:netty-codec-http <4.1.53.Final 存在拒绝服务漏洞|拒绝服务|[MPS-2022-12064](https://www.oscs1024.com/hd/MPS-2022-12064)||中危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|com.fasterxml.jackson.core:jackson-core  BigDecimal拒绝服务漏洞|资源管理错误|[MPS-2022-12166](https://www.oscs1024.com/hd/MPS-2022-12166)||中危|
|gRPC-Java 缓冲区泄露漏洞|通过发送数据的信息暴露|[MPS-2022-12216](https://www.oscs1024.com/hd/MPS-2022-12216)||中危|
|org.glassfish.jersey.media:jersey-media-jaxb <2.31 存在XXE漏洞|XML实体扩展|[MPS-2022-12234](https://www.oscs1024.com/hd/MPS-2022-12234)||高危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|Apache HttpClient URI解析错误漏洞|相对路径遍历|[MPS-2022-12292](https://www.oscs1024.com/hd/MPS-2022-12292)||中危|
|Apache Hadoop < 2.7.3 存在CSRF漏洞|CSRF|[MPS-2022-12308](https://www.oscs1024.com/hd/MPS-2022-12308)||中危|
|Logback SSL证书校验不当漏洞|中间人攻击|[MPS-2022-12411](https://www.oscs1024.com/hd/MPS-2022-12411)||中危|
|com.fasterxml.jackson.core:jackson-databind 存在反序列化漏洞|反序列化|[MPS-2022-12433](https://www.oscs1024.com/hd/MPS-2022-12433)||高危|
|org.apache.hadoop:hadoop-hdfs < 3.3.2 存在XXE漏洞|XXE|[MPS-2022-12474](https://www.oscs1024.com/hd/MPS-2022-12474)||中危|
|org.apache.hadoop:hadoop-hdfs 存在信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-12484](https://www.oscs1024.com/hd/MPS-2022-12484)||高危|
|FasterXML Jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2022-12500](https://www.oscs1024.com/hd/MPS-2022-12500)||中危|
|org.apache.maven.shared:maven-shared-utils 存在命令注入漏洞|命令注入|[MPS-2022-12562](https://www.oscs1024.com/hd/MPS-2022-12562)||高危|
|Apache Commons Collections 远程代码执行漏洞|反序列化|[MPS-2022-12767](https://www.oscs1024.com/hd/MPS-2022-12767)||高危|
|org.apache.spark:spark-core_2.12 存在命令注入漏洞|命令注入|[MPS-2022-13519](https://www.oscs1024.com/hd/MPS-2022-13519)||高危|
|Apache Log4j JDBCAppender SQL注入漏洞|SQL注入|[MPS-2022-1444](https://www.oscs1024.com/hd/MPS-2022-1444)|CVE-2022-23305|严重|
|Apache Log4j Chainsaw反序列化漏洞|反序列化|[MPS-2022-1445](https://www.oscs1024.com/hd/MPS-2022-1445)|CVE-2022-23307|高危|
|Apache Log4j 反序列化漏洞|反序列化|[MPS-2022-1446](https://www.oscs1024.com/hd/MPS-2022-1446)|CVE-2022-23302|高危|
|Apache Spark XSS 漏洞|XSS|[MPS-2022-16687](https://www.oscs1024.com/hd/MPS-2022-16687)|CVE-2022-31777|中危|
|Eclipse Jetty URI注入漏洞|注入|[MPS-2022-18060](https://www.oscs1024.com/hd/MPS-2022-18060)|CVE-2022-2047|低危|
|Apache XercesJ <=2.12.1 存在XML注入漏洞|XPath盲注|[MPS-2022-1864](https://www.oscs1024.com/hd/MPS-2022-1864)|CVE-2022-23437|中危|
|containerd CRI stream server 存在拒绝服务漏洞|拒绝服务|[MPS-2022-1898](https://www.oscs1024.com/hd/MPS-2022-1898)|CVE-2022-23471|中危|
|Apache Spark UI shell 命令注入漏洞|命令注入|[MPS-2022-19085](https://www.oscs1024.com/hd/MPS-2022-19085)|CVE-2022-33891|高危|
|Elastic Stack Kibana 存在缺少授权漏洞|授权检查缺失|[MPS-2022-2136](https://www.oscs1024.com/hd/MPS-2022-2136)|CVE-2022-23709|中危|
|Elastic Stack Kibana 存在 XSS 漏洞|XSS|[MPS-2022-2137](https://www.oscs1024.com/hd/MPS-2022-2137)|CVE-2022-23710|中危|
|JetBrains Kotlin <1.6.0 存在锁定不当漏洞|加锁机制不恰当|[MPS-2022-3233](https://www.oscs1024.com/hd/MPS-2022-3233)|CVE-2022-24329|中危|
|Netty 存在信息泄露漏洞||[MPS-2022-3790](https://www.oscs1024.com/hd/MPS-2022-3790)|CVE-2022-24823|中危|
|Apache Hadoop 存在shell命令注入漏洞|参数注入或修改|[MPS-2022-4190](https://www.oscs1024.com/hd/MPS-2022-4190)|CVE-2022-25168|严重|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|Apache Calcite Avatica 代码注入漏洞|代码注入|[MPS-2022-51965](https://www.oscs1024.com/hd/MPS-2022-51965)|CVE-2022-36364|高危|
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
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58307](https://www.oscs1024.com/hd/MPS-2022-58307)|CVE-2022-41723|高危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|Netty <4.1.86.Final 存在 CRLF 注入漏洞||[MPS-2022-58552](https://www.oscs1024.com/hd/MPS-2022-58552)|CVE-2022-41915|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|Apache Hadoop 存在路径遍历漏洞|路径遍历|[MPS-2022-5920](https://www.oscs1024.com/hd/MPS-2022-5920)|CVE-2022-26612|严重|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|Spring Security通配符路由绕过漏洞|关键资源权限分配不当|[MPS-2022-62832](https://www.oscs1024.com/hd/MPS-2022-62832)|CVE-2023-20860|高危|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|TestNG <7.7.0  存在路径遍历（Zip Slip）漏洞|路径遍历|[MPS-2022-64736](https://www.oscs1024.com/hd/MPS-2022-64736)|CVE-2022-4065|高危|
|Jettison <1.5.2 拒绝服务漏洞|越界写入|[MPS-2022-64973](https://www.oscs1024.com/hd/MPS-2022-64973)|CVE-2022-45685|高危|
|Apache Ivy<2.5.2 存在XXE漏洞|输入验证不恰当|[MPS-2022-67125](https://www.oscs1024.com/hd/MPS-2022-67125)|CVE-2022-46751|中危|
|spring-boot <2.2.11.RELEASE 存在目录劫持漏洞|将资源暴露给错误范围|[MPS-2022-6780](https://www.oscs1024.com/hd/MPS-2022-6780)|CVE-2022-27772|高危|
|Spark 存在shell命令注入漏洞|OS命令注入|[MPS-2022-6786](https://www.oscs1024.com/hd/MPS-2022-6786)||严重|
|spring-beans 远程代码执行漏洞(Spring4Shell)|表达式语言注入|[MPS-2022-6820](https://www.oscs1024.com/hd/MPS-2022-6820)|CVE-2022-22965|严重|
|Go-Yaml 安全漏洞|反序列化|[MPS-2022-8233](https://www.oscs1024.com/hd/MPS-2022-8233)|CVE-2022-28948|高危|
|Google Go 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2022-9049](https://www.oscs1024.com/hd/MPS-2022-9049)|CVE-2022-29526|中危|
|Apache Maven Shared Utils 系统命令注入漏洞|命令注入|[MPS-2022-9177](https://www.oscs1024.com/hd/MPS-2022-9177)|CVE-2022-29599|严重|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Apache Spark 权限提升漏洞|权限管理不当|[MPS-2023-0818](https://www.oscs1024.com/hd/MPS-2023-0818)|CVE-2023-22946|高危|
|Apache Commons FileUpload <1.5 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2023-3553](https://www.oscs1024.com/hd/MPS-2023-3553)|CVE-2023-24998|中危|
|containerd 安全漏洞|不加限制或调节的资源分配|[MPS-2023-3769](https://www.oscs1024.com/hd/MPS-2023-3769)|CVE-2023-25153|中危|
|containerd容器内文件权限机制实现不当|将用户置入不正确的用户组|[MPS-2023-3789](https://www.oscs1024.com/hd/MPS-2023-3789)|CVE-2023-25173|中危|
|Apache Kafka Connect 模块JNDI注入漏洞|反序列化|[MPS-2023-3834](https://www.oscs1024.com/hd/MPS-2023-3834)|CVE-2023-25194|高危|
|Eclipse Jetty 资源管理错误漏洞|拒绝服务|[MPS-2023-4997](https://www.oscs1024.com/hd/MPS-2023-4997)|CVE-2023-26048|中危|
|Eclipse Jetty 信息泄露漏洞|XSS|[MPS-2023-4998](https://www.oscs1024.com/hd/MPS-2023-4998)|CVE-2023-26049|中危|
|java-xmlbuilder 代码问题漏洞|XXE|[MPS-2023-5040](https://www.oscs1024.com/hd/MPS-2023-5040)|CVE-2014-125087|严重|
|netplex json-smart 安全漏洞|未经控制的递归|[MPS-2023-7760](https://www.oscs1024.com/hd/MPS-2023-7760)|CVE-2023-1370|高危|
|Jettison 安全漏洞|未经控制的递归|[MPS-2023-8270](https://www.oscs1024.com/hd/MPS-2023-8270)|CVE-2023-1436|高危|
|jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2023-8438](https://www.oscs1024.com/hd/MPS-2023-8438)|CVE-2021-46877|中危|
|Plexis Archiver 安全漏洞||[MPS-365g-oapn](https://www.oscs1024.com/hd/MPS-365g-oapn)|CVE-2023-37460|严重|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Apache Spark UI shell 命令注入漏洞|OS命令注入|[MPS-je1w-3xtr](https://www.oscs1024.com/hd/MPS-je1w-3xtr)|CVE-2023-32007|高危|
|json-io 缓冲区错误漏洞|越界写入|[MPS-jtye-gw8s](https://www.oscs1024.com/hd/MPS-jtye-gw8s)|CVE-2023-34610|高危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.apache.zookeeper:zookeeper|3.4.6|3.5.5|间接依赖|强烈建议修复|C:0|H:2|M:1|L:0|
|org.eclipse.jetty.aggregate:jetty-all|7.6.0.v20120127|9.2.9.v20150224|间接依赖|强烈建议修复|C:0|H:1|M:0|L:0|
|org.apache.logging.log4j:log4j-core|2.6.2|2.17.1|间接依赖|强烈建议修复|C:3|H:0|M:2|L:1|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.27|11.0.0-m6|间接依赖|强烈建议修复|C:1|H:8|M:4|L:1|
|org.apache.spark:spark-network-common_2.11|2.3.4|2.4.6|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.xerial.snappy:snappy-java|1.0.5|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|com.alibaba:druid|1.1.14|1.2.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|gopkg.in/yaml.v3|v3.0.0-20210107192922-496545a6307b|3.0.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.14.1||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|golang.org/x/net|v0.0.0-20211020060615-d418f374d309|0.7.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-util|9.3.19.v20170502|9.4.17.v20190418|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|io.netty:netty-handler|4.1.17.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|io.netty:netty|3.7.0.Final|3.10.3.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|org.eclipse.jetty:jetty-server|9.4.48.v20220622|12.0.0.beta0|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.eclipse.jetty:jetty-io|9.4.38.v20210224|11.0.10|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.bouncycastle:bcprov-jdk15on|1.65|1.69|间接依赖|建议修复|C:0|H:1|M:3|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.2.0.RELEASE|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.alibaba:fastjson|1.2.70|1.2.83|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|mysql:mysql-connector-java|5.1.41|8.0.28|直接依赖|建议修复|C:0|H:1|M:4|L:1|
|com.jcraft:jsch|0.1.51|0.1.54|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-beans|5.2.0.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework:spring-beans|5.0.5.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|com.cedarsoftware:json-io|2.5.1||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.hadoop:hadoop-hdfs|2.6.5|3.3.2|间接依赖|建议修复|C:0|H:4|M:2|L:0|
|com.squareup.okio:okio|1.4.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-http|9.4.38.v20210224|11.0.10|间接依赖|建议修复|C:0|H:0|M:1|L:1|
|mysql:mysql-connector-java|8.0.12|8.0.28|直接依赖|建议修复|C:0|H:1|M:3|L:0|
|org.scala-lang:scala-compiler|2.11.0|2.12.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.hadoop:hadoop-common|2.6.5|3.3.3|间接依赖|建议修复|C:2|H:0|M:1|L:0|
|org.springframework:spring-web|5.2.0.RELEASE|6.0.0|间接依赖|建议修复|C:1|H:2|M:1|L:0|
|org.apache.hadoop:hadoop-common|2.10.2|3.3.3|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.eclipse.jetty:jetty-io|9.4.33.v20201020|11.0.10|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.alibaba:fastjson|1.2.78|1.2.83|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.google.protobuf:protobuf-java|3.0.0-beta-1|3.21.7|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|org.eclipse.jetty:jetty-server|9.4.33.v20201020|12.0.0.beta0|间接依赖|建议修复|C:0|H:0|M:3|L:1|
|commons-beanutils:commons-beanutils|1.7.0|1.9.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.xerial.snappy:snappy-java|1.1.4|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.mortbay.jetty:jetty|6.1.14|6.1.22|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|com.jcraft:jsch|0.1.42|0.1.54|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.google.protobuf:protobuf-java|2.5.0|3.21.7|直接依赖|建议修复|C:0|H:1|M:2|L:0|
|org.xerial.snappy:snappy-java|1.1.1.3|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|com.jamesmurty.utils:java-xmlbuilder|0.4|1.2|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|io.netty:netty-handler|4.1.94.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.mybatis:mybatis|3.4.6|3.5.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-core|5.0.5.RELEASE|6.0.7|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|com.google.protobuf:protobuf-java|2.6.0|3.21.7|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|commons-collections:commons-collections|3.2.1|3.2.2|间接依赖|建议修复|C:1|H:2|M:0|L:0|
|org.springframework:spring-context|5.2.0.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.15.2||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|io.netty:netty|3.10.6.Final||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-server|9.3.20.v20170531|12.0.0.beta0|间接依赖|建议修复|C:0|H:0|M:4|L:1|
|net.minidev:json-smart|2.3|2.4.9|间接依赖|建议修复|C:1|H:2|M:0|L:0|
|org.apache.hadoop:hadoop-common|2.8.3|3.3.3|间接依赖|建议修复|C:2|H:1|M:1|L:0|
|org.apache.maven.shared:maven-shared-utils|3.1.0|3.3.3|间接依赖|建议修复|C:1|H:1|M:0|L:0|
|mysql:mysql-connector-java|8.0.15|8.0.28|直接依赖|建议修复|C:0|H:0|M:3|L:0|
|com.squareup.okhttp:okhttp|2.4.0|2.7.4|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|commons-beanutils:commons-beanutils|1.9.3|1.9.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tomcat:jasper-compiler|5.5.23||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|net.minidev:json-smart|2.4.7|2.4.9|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.10.5|2.14.0-rc1|间接依赖|建议修复|C:0|H:2|M:5|L:0|
|org.eclipse.jetty:jetty-http|9.4.33.v20201020|11.0.10|间接依赖|建议修复|C:0|H:0|M:1|L:1|
|org.apache.hadoop:hadoop-hdfs-client|2.8.0|3.2.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tomcat:jasper-runtime|5.5.23||间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.apache.hadoop:hadoop-common|2.8.0|3.3.3|直接依赖|建议修复|C:2|H:2|M:2|L:0|
|io.netty:netty-all|4.0.23.Final|4.1.44.Final|间接依赖|建议修复|C:2|H:3|M:0|L:0|
|org.yaml:snakeyaml|1.25|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|org.apache.hive:hive-exec|2.3.5|3.1.3|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-webapp|9.3.20.v20170531|11.0.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-all|4.1.17.Final|4.1.44.Final|间接依赖|建议修复|C:2|H:2|M:0|L:0|
|org.apache.commons:commons-compress|1.9|1.21|间接依赖|建议修复|C:0|H:4|M:1|L:0|
|org.apache.hadoop:hadoop-hdfs-client|2.8.3|3.2.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot|2.2.0.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|github.com/docker/docker|v1.4.2-0.20190924003213-a8608b5b67c7|23.0.3|间接依赖|建议修复|C:0|H:1|M:0|L:1|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13||间接依赖|建议修复|C:1|H:1|M:0|L:0|
|org.xerial.snappy:snappy-java|1.1.7.2|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.apache.kafka:kafka-clients|2.8.1|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.kafka:kafka-clients|2.4.1|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.squareup.okio:okio|1.14.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-codec-http|4.1.17.Final|4.1.86.final|间接依赖|建议修复|C:2|H:2|M:5|L:0|
|mysql:mysql-connector-java|8.0.23|8.0.28|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.6.5|2.14.0-rc1|间接依赖|建议修复|C:26|H:39|M:5|L:0|
|com.nimbusds:nimbus-jose-jwt|4.41.1|7.8.1|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.apache.calcite.avatica:avatica-core|1.17.0|1.22.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.google.protobuf:protobuf-java|3.15.0|3.21.7|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|log4j:log4j|1.2.16||间接依赖|建议修复|C:2|H:3|M:0|L:1|
|org.yaml:snakeyaml|1.33|2.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|commons-fileupload:commons-fileupload|1.3.3|1.5|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.eclipse.jetty:jetty-io|9.3.20.v20170531|11.0.10|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.codehaus.plexus:plexus-archiver|4.2.1|4.8.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.xerial.snappy:snappy-java|1.1.2.6|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|com.squareup.okio:okio|2.6.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.hadoop:hadoop-yarn-server-resourcemanager|3.1.0|3.3.4|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework:spring-web|5.3.22|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.apache.spark:spark-core_2.12|2.4.6|3.4.0|间接依赖|建议修复|C:0|H:3|M:1|L:0|
|org.apache.commons:commons-compress|1.20|1.21|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|ch.qos.logback:logback-core|1.2.3|1.2.8|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.apache.spark:spark-network-common_2.12|2.4.6|3.1.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.xerial.snappy:snappy-java|1.0.4.1|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|com.nimbusds:nimbus-jose-jwt|3.9|7.8.1|间接依赖|建议修复|C:0|H:3|M:1|L:1|
|org.springframework:spring-web|5.3.28|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.yaml:snakeyaml|1.17|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|net.minidev:json-smart|1.1.1|2.4.9|间接依赖|建议修复|C:1|H:2|M:0|L:0|
|org.xerial.snappy:snappy-java|1.1.8.3|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.apache.hadoop:hadoop-hdfs|2.8.0|3.3.2|直接依赖|建议修复|C:0|H:1|M:1|L:0|
|org.glassfish.jersey.media:jersey-media-jaxb|2.22.2|2.31|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.bouncycastle:bcprov-jdk15on|1.52|1.69|间接依赖|建议修复|C:0|H:6|M:7|L:1|
|io.netty:netty|3.6.2.Final|3.10.3.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|com.fasterxml.woodstox:woodstox-core|5.0.3|6.4.0|间接依赖|建议修复|C:0|H:3|M:1|L:1|
|com.fasterxml.jackson.core:jackson-databind|2.10.0|2.14.0-rc1|直接依赖|建议修复|C:0|H:2|M:5|L:0|
|org.springframework:spring-webmvc|5.3.22|6.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty|3.9.9.Final|3.10.3.Final|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.7.3|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-server|9.4.51.v20230217|12.0.0.beta0|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.alibaba:fastjson|1.2.62|1.2.83|直接依赖|建议修复|C:1|H:2|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.10.5.1|2.14.0-rc1|间接依赖|建议修复|C:0|H:1|M:5|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.3|2.14.0-rc1|直接依赖|建议修复|C:0|H:0|M:3|L:0|
|org.yaml:snakeyaml|1.15|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|com.fasterxml.jackson.core:jackson-databind|2.12.0|2.14.0-rc1|间接依赖|建议修复|C:0|H:1|M:5|L:0|
|org.apache.spark:spark-core_2.11|2.3.4|2.4.0|直接依赖|建议修复|C:1|H:2|M:1|L:0|
|org.eclipse.jetty:jetty-server|9.4.38.v20210224|12.0.0.beta0|间接依赖|建议修复|C:0|H:0|M:3|L:1|
|org.codehaus.jettison:jettison|1.1|1.5.4|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|com.fasterxml.woodstox:woodstox-core|5.3.0|6.4.0|间接依赖|建议修复|C:0|H:3|M:0|L:1|
|com.amazonaws:aws-java-sdk-s3|1.11.95|1.12.261|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|log4j:log4j|1.2.17||直接依赖|建议修复|C:2|H:3|M:0|L:1|
|org.elasticsearch:elasticsearch|7.5.1|8.2.1|间接依赖|建议修复|C:0|H:2|M:6|L:1|
|mysql:mysql-connector-java|5.1.26|8.0.28|直接依赖|建议修复|C:0|H:2|M:5|L:1|
|org.apache.hadoop:hadoop-common|3.1.0|3.3.3|间接依赖|建议修复|C:2|H:1|M:0|L:0|
|org.apache.commons:commons-compress|1.8.1|1.21|间接依赖|建议修复|C:0|H:4|M:1|L:0|
|org.apache.hadoop:hadoop-common|2.6.0|3.3.3|间接依赖|建议修复|C:3|H:1|M:1|L:0|
|org.apache.commons:commons-compress|1.19|1.21|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|org.eclipse.jetty:jetty-http|9.3.20.v20170531|11.0.10|间接依赖|建议修复|C:2|H:1|M:0|L:1|
|com.jamesmurty.utils:java-xmlbuilder|1.1|1.2|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|io.netty:netty-handler|4.1.53.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|com.google.protobuf:protobuf-java|3.11.4|3.21.7|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|libiberty|9.1.0|20220713-1|间接依赖|建议修复|C:0|H:5|M:8|L:0|
|org.springframework:spring-context|5.0.5.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec|4.1.53.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|io.netty:netty-codec|4.1.17.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|org.apache.spark:spark-core_2.12|3.2.0|3.4.0|直接依赖|建议修复|C:1|H:4|M:1|L:0|
|org.apache.commons:commons-dbcp2|2.6.0|2.9.0|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|io.netty:netty-transport-native-epoll|4.1.53.Final|4.1.59.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.hibernate:hibernate-validator|5.1.0.Final|6.1.3.Final|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|org.bouncycastle:bcprov-jdk15on|1.70||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|14.0.1|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|golang.org/x/sys|v0.0.0-20211102192858-4dd72447c267|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.jetbrains.kotlin:kotlin-stdlib|1.3.71|1.6.0|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|11.0.2|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|commons-io:commons-io|2.5|2.7|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|19.0|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|io.netty:netty-common|4.1.17.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.apache.calcite:calcite-core|1.10.0|1.32.0|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|commons-codec:commons-codec|1.6|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.eclipse.jetty:jetty-http|9.4.51.v20230217|11.0.10|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|xerces:xercesImpl|2.9.1|2.12.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.6.6|2.12.1|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-core|5.2.0.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|com.fasterxml.jackson.core:jackson-core|2.6.5|2.8.6|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|commons-codec:commons-codec|1.4|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|com.google.code.gson:gson|2.2.4|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|commons-net:commons-net|3.6|3.9.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|xerces:xercesImpl|2.12.0|2.12.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-io:commons-io|2.6|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|github.com/containerd/containerd|v1.5.7|1.6.18|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|org.eclipse.jetty:jetty-servlets|9.4.33.v20201020|11.0.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|junit:junit|4.12|4.13.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|mysql:mysql-connector-java|8.0.27|8.0.28|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.hadoop:hadoop-hdfs|2.10.2|3.3.2|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.ant:ant|1.10.9|1.10.11|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|31.0.1-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.httpcomponents:httpclient|4.4.1|4.5.13|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|io.netty:netty-codec-http2|4.1.53.Final|4.1.61.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.apache.httpcomponents:httpclient|4.5.2|4.5.13|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.apache.commons:commons-compress|1.4.1|1.21|间接依赖|可选修复|C:0|H:2|M:1|L:0|
|com.google.guava:guava|29.0-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:1|
|org.apache.ant:ant|1.9.1|1.10.11|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|commons-net:commons-net|3.1|3.9.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|30.0-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.kafka:connect-runtime|2.7.0|2.8.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.thrift:libthrift|0.9.3|0.12.0|直接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.jboss.xnio:xnio-api|3.8.8.Final|3.8.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|commons-httpclient:commons-httpclient|3.1||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-io:commons-io|2.4|2.7|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|15.0|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:2|L:1|
|org.springframework:spring-webmvc|5.2.0.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.jdom:jdom|1.1||间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-servlets|9.4.38.v20210224|11.0.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.jboss.xnio:xnio-api|3.6.5.Final|3.8.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.testng:testng|7.3.0|7.7.0|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.calcite:calcite-core|1.16.0|1.32.0|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.hibernate.validator:hibernate-validator|6.0.17.Final|6.1.3.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|commons-codec:commons-codec|1.11|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.apache.ivy:ivy|2.4.0|2.5.1|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.apache.kafka:connect-runtime|2.7.1|2.8.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-common|4.1.53.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.glassfish:javax.el|3.0.1-b12||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-httpclient:commons-httpclient|3.0.1|3.1-jenkins-2|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.apache.hadoop:hadoop-yarn-common|2.7.2|2.7.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.8.11|2.12.1|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|io.grpc:grpc-core|1.30.0|1.33.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-http|4.1.53.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:4|L:0|
|org.apache.hadoop:hadoop-yarn-common|2.6.5|2.7.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-net:commons-net|2.2|3.9.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.ivy:ivy|2.5.0|2.5.1|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.code.gson:gson|2.8.6|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.hadoop:hadoop-mapreduce-client-app|2.6.5|2.7.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|5.0.5.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|com.google.guava:guava|16.0.1|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|org.springframework:spring-expression|5.2.0.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|1499|Low|
|MIT|96|Low|
|EPL-1.0|30|Low|
|BSD-3-Clause|76|Low|
|LGPL-2.1|16|Medium|
|自定义许可证|152|Low|
|EPL-2.0|44|Low|
|CDDL-1.0|2|Low|
|CDDL-1.1|24|Low|
|BSD-2-Clause|14|Low|
|BSD-2-Clause-Views|2|Low|
|GPL-2.0|4|Medium|
|MPL-2.0|7|Low|
|ISC|3|Low|
|MIT-0|1|Low|
|MPL-1.1|4|Low|
|CC-BY-SA-4.0|1|Medium|
|WTFPL|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|commons-io:commons-io|2.11.0|直接依赖|maven|
|org.apache.maven:maven-core|3.0|间接依赖|maven|
|com.zendesk:mysql-binlog-connector-java|0.25.3|间接依赖|maven|
|github.com/sirupsen/logrus|v1.8.1|间接依赖|go|
|io.fabric8:kubernetes-model-scheduling|6.7.2|间接依赖|maven|
|org.apache.kafka:connect-api|2.7.0|间接依赖|maven|
|org.apache.lucene:lucene-sandbox|8.4.0|间接依赖|maven|
|org.springframework:spring-jcl|5.2.0.RELEASE|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-logs|1.14.0-alpha|间接依赖|maven|
|org.apache.flink:flink-shaded-asm-7|7.1-12.0|间接依赖|maven|
|com.github.joshelser:dropwizard-metrics-hadoop-metrics2-reporter|0.1.2|间接依赖|maven|
|github.com/json-iterator/go|v1.1.11|间接依赖|go|
|github.com/eclipse/paho.mqtt.golang|v1.2.1-0.20200121105743-0d940dd29fd2|间接依赖|go|
|golang.org/x/time|v0.0.0-20210723032227-1f47c861a9ac|间接依赖|go|
|io.opentelemetry:opentelemetry-exporter-otlp-common|1.26.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.6.21|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.13.5|间接依赖|maven|
|org.apache.hive:hive-llap-tez|3.1.3|间接依赖|maven|
|org.codehaus.jackson:jackson-jaxrs|1.9.2|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.3|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.7.13|直接依赖|maven|
|k8s.io/api|v0.21.1|间接依赖|go|
|org.elasticsearch.plugin:rank-eval-client|7.10.2|间接依赖|maven|
|com.google.inject:guice|3.0|间接依赖|maven|
|software.amazon.awssdk:http-client-spi|2.15.45|间接依赖|maven|
|org.apache.hbase:hbase-annotations|1.2.3|间接依赖|maven|
|commons-daemon:commons-daemon|1.0.13|直接依赖|maven|
|log4j:log4j|1.2.17|直接依赖|maven|
|com.thoughtworks.qdox:qdox|2.0.1|间接依赖|maven|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|commons-net:commons-net|2.2|间接依赖|maven|
|commons-net:commons-net|3.9.0|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|org.openjdk.jol:jol-core|0.2|间接依赖|maven|
|go.elastic.co/ecszap|v0.3.0|间接依赖|go|
|net.minidev:accessors-smart|2.4.7|间接依赖|maven|
|io.debezium:debezium-embedded|1.5.4.Final|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.12.1|间接依赖|maven|
|io.opentelemetry:opentelemetry-context|1.14.0|间接依赖|maven|
|io.zipkin.reporter2:zipkin-sender-okhttp3|2.16.3|间接依赖|maven|
|org.jacoco:org.jacoco.agent|0.8.5|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.2|间接依赖|maven|
|github.com/googleapis/gnostic|v0.4.1|间接依赖|go|
|org.springframework.data:spring-data-commons|2.7.2|间接依赖|maven|
|org.apache.hbase:hbase-logging|2.4.9|间接依赖|maven|
|org.apache.calcite:calcite-linq4j|1.32.0|间接依赖|maven|
|org.apache.flink:flink-rpc-core|1.15.3|间接依赖|maven|
|org.apache.kerby:kerb-common|2.0.3|间接依赖|maven|
|org.apache.paimon:paimon-core|0.4.0-incubating|直接依赖|maven|
|go.etcd.io/bbolt|v1.3.6|间接依赖|go|
|com.facebook.presto.hive:hive-apache|3.0.0-8|直接依赖|maven|
|org.mortbay.jetty:servlet-api|2.5-20081211|间接依赖|maven|
|org.apache.lucene:lucene-sandbox|8.3.0|间接依赖|maven|
|org.glassfish.hk2:osgi-resource-locator|1.0.3|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.1|间接依赖|maven|
|org.apache.flink:flink-connector-base|1.15.3|间接依赖|maven|
|org.eclipse.jetty:jetty-security|9.3.20.v20170531|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-core|2.8.3|间接依赖|maven|
|org.apache.hudi:hudi-hive-sync|0.13.1|间接依赖|maven|
|github.com/elastic/go-sysinfo|v1.7.1|间接依赖|go|
|gotest.tools|v2.2.0+incompatible|直接依赖|go|
|org.eclipse.jetty:jetty-server|9.3.20.v20170531|间接依赖|maven|
|org.apache.orc:orc-core|1.8.4|间接依赖|maven|
|org.elasticsearch.plugin:parent-join-client|7.5.1|间接依赖|maven|
|org.jboss.xnio:xnio-api|3.8.9.Final|间接依赖|maven|
|io.fabric8:openshift-model|5.12.2|间接依赖|maven|
|io.fabric8:openshift-model-config|6.7.2|间接依赖|maven|
|org.sonatype.plexus:plexus-build-api|0.0.7|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-trace|1.26.0|间接依赖|maven|
|org.mariadb.jdbc:mariadb-java-client|3.0.4|直接依赖|maven|
|com.aliyun.oss:aliyun-sdk-oss|3.4.1|间接依赖|maven|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|commons-cli:commons-cli|1.3.1|间接依赖|maven|
|org.eclipse.jetty:jetty-servlets|9.4.51.v20230217|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|2.7.2|间接依赖|maven|
|org.apache.kafka:connect-api|2.7.1|间接依赖|maven|
|software.amazon.awssdk:sts|2.17.257|直接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.1|间接依赖|maven|
|io.prometheus:simpleclient|0.15.0|间接依赖|maven|
|info.picocli:picocli|4.5.2|间接依赖|maven|
|javax.xml.stream:stax-api|1.0-2|间接依赖|maven|
|io.fabric8:kubernetes-model-discovery|5.12.2|间接依赖|maven|
|com.aliyun:openapiutil|0.1.14|间接依赖|maven|
|org.yaml:snakeyaml|1.25|间接依赖|maven|
|org.json4s:json4s-ast_2.12|3.7.0-M11|间接依赖|maven|
|com.alibaba:fastjson|1.2.62|直接依赖|maven|
|io.dropwizard.metrics:metrics-json|3.1.0|间接依赖|maven|
|org.codehaus.jackson:jackson-xc|1.8.3|间接依赖|maven|
|github.com/digitalocean/go-libvirt|v0.0.0-20180301200012-6075ea3c39a1|间接依赖|go|
|org.apache.httpcomponents:httpmime|4.5.14|间接依赖|maven|
|org.eclipse.jetty:jetty-webapp|9.3.20.v20170531|间接依赖|maven|
|org.codehaus.jackson:jackson-jaxrs|1.9.13|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.3|直接依赖|maven|
|io.zipkin.zipkin2:zipkin|2.23.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.7.13|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.0|间接依赖|maven|
|org.apache.lucene:lucene-highlighter|8.3.0|间接依赖|maven|
|com.sun.jersey:jersey-core|1.19|间接依赖|maven|
|org.apache.curator:curator-recipes|2.7.1|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.10.0|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-csv|2.13.5|间接依赖|maven|
|org.apache.lucene:lucene-misc|8.3.0|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|2.6.5|间接依赖|maven|
|commons-codec:commons-codec|1.4|间接依赖|maven|
|github.com/eapache/queue|v1.1.0|间接依赖|go|
|github.com/gofrs/flock|v0.7.2-0.20190320160742-5135e617513b|间接依赖|go|
|javax.resource:connector|1.0|间接依赖|maven|
|org.elasticsearch.plugin:lang-mustache-client|7.10.2|间接依赖|maven|
|org.springframework:spring-orm|5.0.5.RELEASE|间接依赖|maven|
|org.apache.lucene:lucene-spatial-extras|8.4.0|间接依赖|maven|
|org.apache.flink:flink-clients|1.15.3|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.65|间接依赖|maven|
|org.apache.arrow:arrow-vector|9.0.0|直接依赖|maven|
|org.eclipse.jetty.websocket:javax-websocket-server-impl|9.4.48.v20220622|间接依赖|maven|
|io.perfmark:perfmark-api|0.19.0|间接依赖|maven|
|github.com/Microsoft/go-winio|v0.5.1|间接依赖|go|
|org.apache.kerby:kerb-admin|1.0.1|间接依赖|maven|
|org.apache.flink:flink-runtime-web|1.15.3|直接依赖|maven|
|com.typesafe:ssl-config-core_2.12|0.3.7|间接依赖|maven|
|io.netty:netty-handler|4.1.17.Final|间接依赖|maven|
|io.netty:netty-codec-haproxy|4.1.94.Final|间接依赖|maven|
|org.apache.ivy:ivy|2.4.0|间接依赖|maven|
|commons-io:commons-io|2.4|直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-trace|1.14.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.14.1|间接依赖|maven|
|io.netty:netty-transport|4.1.53.Final|间接依赖|maven|
|org.apache.kafka:kafka-tools|2.7.1|间接依赖|maven|
|org.eclipse.jetty:jetty-util-ajax|9.3.19.v20170502|间接依赖|maven|
|libiberty|9.1.0|间接依赖||
|com.fasterxml.jackson.core:jackson-core|2.15.2|直接依赖|maven|
|org.glassfish.hk2:hk2-api|2.4.0-b34|间接依赖|maven|
|org.eclipse.jetty.orbit:javax.servlet|3.0.0.v201112011016|间接依赖|maven|
|io.debezium:debezium-core|1.6.4.Final|间接依赖|maven|
|org.springframework:spring-tx|5.0.5.RELEASE|间接依赖|maven|
|gopkg.in/mgo.v2|v2.0.0-20160818020120-3f83fa500528|间接依赖|go|
|org.junit.platform:junit-platform-engine|1.7.0|间接依赖|maven|
|org.apache.parquet:parquet-hadoop|1.13.1|直接依赖|maven|
|github.com/vmware/govmomi|v0.0.0-20170802214208-2cad15190b41|间接依赖|go|
|javax.servlet.jsp:jsp-api|2.1|间接依赖|maven|
|org.antlr:antlr4|4.11.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.13|直接依赖|maven|
|com.google.inject.extensions:guice-servlet|3.0|间接依赖|maven|
|github.com/tsg/gopacket|v0.0.0-20200626092518-2ab8e397a786|间接依赖|go|
|github.com/santhosh-tekuri/jsonschema|v1.2.4|间接依赖|go|
|org.apache.lucene:lucene-grouping|8.4.0|间接依赖|maven|
|org.apache.hadoop:hadoop-aliyun|3.3.6|直接依赖|maven|
|net.java.dev.jets3t:jets3t|0.9.0|间接依赖|maven|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|org.apache.httpcomponents:httpcore-nio|4.4.12|间接依赖|maven|
|org.glassfish.jersey.core:jersey-common|2.35|间接依赖|maven|
|org.antlr:antlr-runtime|3.5.3|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.6.21|间接依赖|maven|
|github.com/rcrowley/go-metrics|v0.0.0-20201227073835-cf1acfcdf475|间接依赖|go|
|org.apache.hive:hive-common|2.3.5|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.7.8|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.10.5|间接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|9.8.1|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|2.8.0|间接依赖|maven|
|org.apache.doris:java-common|1.2-SNAPSHOT|直接依赖|maven|
|org.apache.flink:flink-core|1.15.3|间接依赖|maven|
|commons-net:commons-net|3.6|间接依赖|maven|
|javax.ws.rs:jsr311-api|1.1.1|间接依赖|maven|
|dk.brics.automaton:automaton|1.11-8|直接依赖|maven|
|net.sf.py4j:py4j|0.10.9.2|间接依赖|maven|
|software.amazon.awssdk:profiles|2.15.45|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.3|间接依赖|maven|
|org.apache.curator:curator-framework|5.2.0|间接依赖|maven|
|org.apache.flink:flink-table-runtime|1.15.3|间接依赖|maven|
|io.dropwizard.metrics:metrics-jvm|3.1.0|间接依赖|maven|
|org.apache.calcite:calcite-druid|1.16.0|间接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|org.apache.httpcomponents:fluent-hc|4.5.14|间接依赖|maven|
|org.apache.lucene:lucene-join|8.4.0|间接依赖|maven|
|org.apache.geronimo.specs:geronimo-jcache_1.0_spec|1.0-alpha-1|间接依赖|maven|
|org.slf4j:slf4j-log4j12|1.7.5|间接依赖|maven|
|org.clapper:grizzled-slf4j_2.11|1.3.2|间接依赖|maven|
|org.apache.hadoop.thirdparty:hadoop-shaded-guava|1.1.1|间接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|4.41.1|间接依赖|maven|
|org.apache.orc:orc-core|1.4.4|间接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.4|间接依赖|maven|
|github.com/h2non/filetype|v1.1.1|间接依赖|go|
|org.apache.commons:commons-compress|1.9|间接依赖|maven|
|org.apache.ant:ant|1.10.12|间接依赖|maven|
|org.springframework.boot:spring-boot-configuration-processor|2.7.13|直接依赖|maven|
|github.com/godbus/dbus/v5|v5.0.5|间接依赖|go|
|github.com/containerd/containerd|v1.5.7|间接依赖|go|
|org.apache.logging.log4j:log4j-1.2-api|2.18.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.14.1|直接依赖|maven|
|github.com/prometheus/procfs|v0.6.0|间接依赖|go|
|org.apache.doris:je|18.3.14-doris-SNAPSHOT|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.2.0.RELEASE|间接依赖|maven|
|org.apache.lucene:lucene-spatial3d|8.4.0|间接依赖|maven|
|org.springframework:spring-jdbc|5.2.0.RELEASE|间接依赖|maven|
|kernel.org/pub/linux/libs/security/libcap/psx|v1.2.57|间接依赖|go|
|org.bouncycastle:bcprov-jdk15on|1.65|间接依赖|maven|
|com.esri.geometry:esri-geometry-api|2.2.0|间接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.38.v20210224|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|间接依赖|maven|
|org.springframework:spring-tx|5.3.28|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-server|9.4.51.v20230217|间接依赖|maven|
|org.apache.spark:spark-network-common_2.11|2.3.4|间接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|间接依赖|maven|
|com.oracle.ojdbc:oraclepki|19.3.0.0|间接依赖|maven|
|org.apache.hive:hive-exec|2.3.5|直接依赖|maven|
|org.antlr:antlr4-runtime|4.7|间接依赖|maven|
|org.apache.hive.shims:hive-shims-common|3.1.3|间接依赖|maven|
|xerces:xercesImpl|2.9.1|间接依赖|maven|
|org.elasticsearch:elasticsearch-x-content|7.5.1|间接依赖|maven|
|org.apache.kafka:connect-json|2.7.1|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.10.5|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-client|2.8.3|间接依赖|maven|
|github.com/mitchellh/mapstructure|v1.3.3|间接依赖|go|
|org.jruby.jcodings:jcodings|1.0.55|间接依赖|maven|
|io.netty:netty|3.10.6.Final|间接依赖|maven|
|com.esotericsoftware.kryo:kryo|2.24.0|间接依赖|maven|
|github.com/google/gofuzz|v1.1.0|间接依赖|go|
|org.eclipse.jetty:jetty-xml|9.3.20.v20170531|间接依赖|maven|
|com.google.cloud.bigdataoss:util-hadoop|hadoop2-2.2.15|间接依赖|maven|
|org.apache.hudi:hudi-hadoop-mr|0.13.1|直接依赖|maven|
|org.apache.maven:maven-plugin-api|3.0|间接依赖|maven|
|org.codehaus.woodstox:stax2-api|4.2.1|间接依赖|maven|
|io.opentracing:opentracing-api|0.33.0|间接依赖|maven|
|org.eclipse.jetty:jetty-annotations|9.4.51.v20230217|间接依赖|maven|
|github.com/prometheus/common|v0.10.0|间接依赖|go|
|io.netty:netty-codec-http2|4.1.53.Final|间接依赖|maven|
|io.opencensus:opencensus-contrib-http-util|0.31.1|间接依赖|maven|
|com.oracle.database.jdbc:ojdbc8|12.2.0.1|直接依赖|maven|
|dnsjava:dnsjava|2.1.7|间接依赖|maven|
|org.elasticsearch.plugin:parent-join-client|7.10.2|间接依赖|maven|
|software.amazon.awssdk:aws-xml-protocol|2.17.257|间接依赖|maven|
|kernel.org/pub/linux/libs/security/libcap/cap|v1.2.57|间接依赖|go|
|github.com/fatih/color|v1.9.0|间接依赖|go|
|org.glassfish.hk2:hk2-locator|2.6.1|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-common|2.7.2|间接依赖|maven|
|org.apache.parquet:parquet-common|1.8.3|间接依赖|maven|
|org.eclipse.jetty:jetty-client|9.4.38.v20210224|间接依赖|maven|
|github.com/docker/docker|v1.4.2-0.20190924003213-a8608b5b67c7|间接依赖|go|
|com.huaweicloud:esdk-obs-java-optimised|3.21.8.2|间接依赖|maven|
|org.apache.lucene:lucene-core|8.4.0|间接依赖|maven|
|org.apache.hive.shims:hive-shims-0.23|2.3.5|间接依赖|maven|
|software.amazon.awssdk:json-utils|2.17.257|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-common|3.1.0|间接依赖|maven|
|org.apache.iceberg:iceberg-bundled-guava|1.1.0|间接依赖|maven|
|github.com/xdg/scram|v1.0.3|间接依赖|go|
|org.apache.hadoop:hadoop-yarn-server-web-proxy|2.7.2|间接依赖|maven|
|javax.activation:activation|1.1.1|间接依赖|maven|
|com.typesafe:ssl-config-core_2.11|0.3.7|间接依赖|maven|
|org.apache.paimon:paimon-format|0.4.0-incubating|直接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-starter|1.3.2|直接依赖|maven|
|golang.org/x/term|v0.0.0-20210220032956-6a3ed077a48d|间接依赖|go|
|net.minidev:json-smart|2.3|间接依赖|maven|
|mysql:mysql-connector-java|8.0.27|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|2.8.3|间接依赖|maven|
|howett.net/plist|v0.0.0-20181124034731-591f970eefbb|间接依赖|go|
|org.apache.htrace:htrace-core|3.1.0-incubating|直接依赖|maven|
|org.apache.maven.shared:maven-shared-io|3.0.0|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-common|2.6.5|间接依赖|maven|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|org.sonatype.aether:aether-api|1.7|间接依赖|maven|
|com.oracle.ojdbc:osdt_core|19.3.0.0|间接依赖|maven|
|org.apache.hive:hive-common|3.1.3|间接依赖|maven|
|io.opentelemetry:opentelemetry-api|1.26.0|直接依赖|maven|
|com.oracle.database.jdbc:ucp|21.5.0.0|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.5|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.15.2|直接依赖|maven|
|io.fabric8:kubernetes-model-discovery|6.7.2|间接依赖|maven|
|org.apache.kafka:connect-transforms|2.7.0|间接依赖|maven|
|org.apache.spark:spark-launcher_2.11|2.3.4|间接依赖|maven|
|com.aliyun.datalake:shims-hive3|0.2.14|间接依赖|maven|
|org.glassfish:javax.el|3.0.1-b12|间接依赖|maven|
|javax.ws.rs:javax.ws.rs-api|2.1.1|间接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.6.2|间接依赖|maven|
|org.apache.flink:flink-file-sink-common|1.12.2|间接依赖|maven|
|org.codehaus.plexus:plexus-utils|3.4.1|间接依赖|maven|
|org.apache.curator:curator-framework|2.7.1|间接依赖|maven|
|ch.qos.reload4j:reload4j|1.2.18.3|间接依赖|maven|
|gopkg.in/jcmturner/goidentity.v3|v3.0.0|间接依赖|go|
|org.apache.hive:hive-llap-tez|2.3.5|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-server|9.4.48.v20220622|间接依赖|maven|
|org.sonatype.sisu:sisu-inject-bean|1.4.2|间接依赖|maven|
|org.eclipse.jetty.websocket:javax-websocket-server-impl|9.4.51.v20230217|间接依赖|maven|
|org.apache.commons:commons-compress|1.4.1|间接依赖|maven|
|net.hydromatic:eigenbase-properties|1.1.5|间接依赖|maven|
|org.eclipse.jetty:jetty-continuation|9.4.48.v20220622|间接依赖|maven|
|github.com/gorhill/cronexpr|v0.0.0-20180427100037-88b0669f7d75|间接依赖|go|
|github.com/docker/distribution|v2.8.0+incompatible|间接依赖|go|
|com.univocity:univocity-parsers|2.9.1|间接依赖|maven|
|org.wildfly.common:wildfly-common|1.5.4.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.2.0.RELEASE|间接依赖|maven|
|org.apache.iceberg:iceberg-api|1.1.0|间接依赖|maven|
|software.amazon.awssdk:auth|2.17.257|间接依赖|maven|
|commons-el:commons-el|1.0|间接依赖|maven|
|org.apache.calcite:calcite-core|1.10.0|间接依赖|maven|
|org.apache.lucene:lucene-core|8.3.0|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.10.0|间接依赖|maven|
|org.springframework:spring-jdbc|5.0.5.RELEASE|间接依赖|maven|
|com.squareup.okio:okio|3.4.0|直接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.18|间接依赖|maven|
|org.apache.spark:spark-unsafe_2.11|2.3.4|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.10.5|间接依赖|maven|
|org.jruby.joni:joni|2.1.2|间接依赖|maven|
|com.google.code.findbugs:jsr305|1.3.9|间接依赖|maven|
|org.apache.commons:commons-crypto|1.1.0|间接依赖|maven|
|com.google.http-client:google-http-client-apache-v2|1.42.3|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-client|9.4.48.v20220622|间接依赖|maven|
|org.jdom:jdom2|2.0.6.1|间接依赖|maven|
|com.google.flatbuffers:flatbuffers-java|1.9.0|间接依赖|maven|
|org.apache.ant:ant|1.10.9|间接依赖|maven|
|org.apache.commons:commons-configuration2|2.8.0|间接依赖|maven|
|org.scala-lang:scala-compiler|2.11.0|间接依赖|maven|
|com.typesafe.akka:akka-actor_2.12|2.5.21|间接依赖|maven|
|org.springframework:spring-web|5.2.0.RELEASE|间接依赖|maven|
|org.apache.flink:flink-shaded-force-shading|15.0|间接依赖|maven|
|io.fabric8:kubernetes-model-coordination|6.7.2|间接依赖|maven|
|com.oracle.database.ha:simplefan|21.5.0.0|间接依赖|maven|
|com.google.code.gson:gson|2.10.1|直接依赖|maven|
|com.google.http-client:google-http-client|1.42.3|间接依赖|maven|
|org.eclipse.jetty.aggregate:jetty-all|7.6.0.v20120127|间接依赖|maven|
|javax.mail:mail|1.4.7|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-sts|3.0.0|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.2|间接依赖|maven|
|org.roaringbitmap:shims|0.8.13|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.18.0|直接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.0|间接依赖|maven|
|com.google.http-client:google-http-client-gson|1.42.3|间接依赖|maven|
|org.json4s:json4s-core_2.12|3.5.3|间接依赖|maven|
|github.com/elastic/go-windows|v1.0.1|间接依赖|go|
|com.aliyun:aliyun-java-sdk-kms|2.11.0|间接依赖|maven|
|io.netty:netty-codec-stomp|4.1.94.Final|间接依赖|maven|
|com.alibaba.otter:canal.common|1.1.6|间接依赖|maven|
|software.amazon.awssdk:sdk-core|2.17.257|间接依赖|maven|
|org.apache.hudi:hudi-hadoop-mr|0.10.0|间接依赖|maven|
|io.netty:netty-codec|4.1.53.Final|间接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.18.0|直接依赖|maven|
|io.prometheus:simpleclient_dropwizard|0.15.0|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet|2.22.2|间接依赖|maven|
|github.com/gocarina/gocsv|v0.0.0-20170324095351-ffef3ffc77be|间接依赖|go|
|org.checkerframework:checker-qual|2.11.1|间接依赖|maven|
|util-deprecate|1.0.2|间接依赖|npm|
|io.fabric8:kubernetes-model-admissionregistration|5.12.2|间接依赖|maven|
|org.wildfly.openssl:wildfly-openssl|1.1.3.Final|间接依赖|maven|
|org.ow2.asm:asm|9.4|间接依赖|maven|
|software.amazon.awssdk:profiles|2.17.257|间接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.33.v20201020|间接依赖|maven|
|com.alibaba:fastjson|1.2.70|直接依赖|maven|
|org.apache.lucene:lucene-suggest|8.3.0|间接依赖|maven|
|io.opentelemetry:opentelemetry-semconv|1.26.0-alpha|间接依赖|maven|
|org.eclipse.jetty:jetty-security|9.4.38.v20210224|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-scala_2.12|2.15.2|直接依赖|maven|
|sqlstring|2.3.1|间接依赖|npm|
|org.apache.parquet:parquet-hadoop-bundle|1.10.0|间接依赖|maven|
|com.google.cloud.bigdataoss:gcs-connector|hadoop2-2.2.15|直接依赖|maven|
|org.sonatype.plexus:plexus-sec-dispatcher|1.3|间接依赖|maven|
|org.apache.ranger:ranger-plugin-classloader|2.4.0|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.94.Final|间接依赖|maven|
|io.fabric8:kubernetes-model-core|6.7.2|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.53.Final|间接依赖|maven|
|com.google.guava:guava|29.0-jre|间接依赖|maven|
|org.apache.curator:curator-client|5.2.0|间接依赖|maven|
|org.apache.hadoop:hadoop-client|3.3.6|直接依赖|maven|
|com.sun.jersey:jersey-json|1.19|间接依赖|maven|
|io.grpc:grpc-api|1.55.1|间接依赖|maven|
|com.alibaba.otter:canal.protocol|1.1.6|直接依赖|maven|
|net.java.dev.jna:jna|5.5.0|直接依赖|maven|
|io.fabric8:kubernetes-model-autoscaling|5.12.2|间接依赖|maven|
|org.apache.maven:maven-settings-builder|3.0|间接依赖|maven|
|org.antlr:antlr4-runtime|4.9.3|直接依赖|maven|
|org.apache.hudi:hudi-spark-common_2.12|0.13.1|直接依赖|maven|
|org.sonatype.aether:aether-util|1.7|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.28|间接依赖|maven|
|com.google.cloud.bigdataoss:gcs-connector|hadoop2-2.2.8|直接依赖|maven|
|org.apache.hbase:hbase-prefix-tree|1.2.3|间接依赖|maven|
|junit:junit|4.13.1|间接依赖|maven|
|org.springframework.data:spring-data-commons|2.7.13|间接依赖|maven|
|org.json4s:json4s-jackson_2.12|3.7.0-M11|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.48.v20220622|间接依赖|maven|
|org.springframework.boot:spring-boot|2.7.13|间接依赖|maven|
|org.apache.orc:orc-shims|1.6.0|间接依赖|maven|
|io.netty:netty-handler|4.1.53.Final|间接依赖|maven|
|org.rocksdb:rocksdbjni|6.20.3|间接依赖|maven|
|org.apache.flink:flink-table-api-java|1.15.3|间接依赖|maven|
|org.apache.calcite:calcite-druid|1.32.0|间接依赖|maven|
|org.apache.maven:maven-archiver|3.5.0|间接依赖|maven|
|xml-apis:xml-apis|1.3.04|间接依赖|maven|
|org.glassfish.hk2.external:javax.inject|2.4.0-b34|间接依赖|maven|
|org.apache.hudi:hudi-common|0.13.1|直接依赖|maven|
|k8s.io/klog/v2|v2.8.0|间接依赖|go|
|org.ow2.asm:asm|5.0.4|间接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.8|间接依赖|maven|
|org.elasticsearch:elasticsearch-x-content|7.10.2|间接依赖|maven|
|com.google.flogger:flogger-system-backend|0.7.1|间接依赖|maven|
|org.elasticsearch:elasticsearch-core|7.10.2|间接依赖|maven|
|org.apache.parquet:parquet-hadoop-bundle|1.8.1|间接依赖|maven|
|io.prometheus:simpleclient_pushgateway|0.15.0|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.7.0|间接依赖|maven|
|com.google.cloud.bigdataoss:util|2.2.15|间接依赖|maven|
|com.oracle.ojdbc:orai18n|19.3.0.0|直接依赖|maven|
|com.jcraft:jsch|0.1.54|间接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5-h2|5.1.3|间接依赖|maven|
|org.apache.doris:spark-doris-connector-2.3_2.11|1.0.1|直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk|1.26.0|直接依赖|maven|
|software.amazon.awssdk:netty-nio-client|2.15.45|间接依赖|maven|
|org.apache.spark:spark-network-shuffle_2.11|2.3.4|间接依赖|maven|
|github.com/modern-go/reflect2|v1.0.1|间接依赖|go|
|org.apache.commons:commons-lang3|3.5|间接依赖|maven|
|org.apache.kafka:connect-transforms|2.7.1|间接依赖|maven|
|org.apache.avro:avro-ipc|1.7.7|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.2|间接依赖|maven|
|com.aliyun.oss:aliyun-sdk-oss|3.13.0|间接依赖|maven|
|xml-apis:xml-apis|1.4.01|间接依赖|maven|
|org.apache.kerby:kerby-asn1|2.0.3|间接依赖|maven|
|io.netty:netty-all|4.1.94.Final|直接依赖|maven|
|commons-fileupload:commons-fileupload|1.5|直接依赖|maven|
|org.codehaus.janino:janino|3.1.8|间接依赖|maven|
|joda-time:joda-time|2.8.1|直接依赖|maven|
|org.scala-lang:scala-reflect|2.12.15|间接依赖|maven|
|org.apache.kafka:connect-file|2.7.1|间接依赖|maven|
|com.vesoft:client|3.0.0|直接依赖|maven|
|com.huawei.storage:esdk-obs-java|3.0.1|间接依赖|maven|
|commons-pool:commons-pool|1.5.1|直接依赖|maven|
|com.google.protobuf:protobuf-java|3.0.0-beta-1|间接依赖|maven|
|gopkg.in/jcmturner/dnsutils.v1|v1.0.1|间接依赖|go|
|software.amazon.awssdk:url-connection-client|2.17.257|直接依赖|maven|
|github.com/cespare/xxhash/v2|v2.1.1|间接依赖|go|
|com.google.errorprone:error_prone_annotations|2.7.1|间接依赖|maven|
|org.apache.avro:avro|1.11.1|直接依赖|maven|
|org.spark-project.spark:unused|1.0.0|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.6.6|间接依赖|maven|
|org.apache.orc:orc-mapreduce|1.6.11|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-jobclient|3.3.6|间接依赖|maven|
|org.springframework:spring-aop|5.0.5.RELEASE|间接依赖|maven|
|com.sun.jersey.contribs:jersey-guice|1.19|间接依赖|maven|
|joda-time:joda-time|2.9.4|间接依赖|maven|
|com.aliyun.odps:odps-sdk-core|0.43.3-public|直接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-zipkin|1.14.0|间接依赖|maven|
|com.esotericsoftware.minlog:minlog|1.2|间接依赖|maven|
|org.scala-lang:scala-reflect|2.12.1|间接依赖|maven|
|org.scala-lang.modules:scala-parser-combinators_2.12|1.1.1|间接依赖|maven|
|com.sun.jersey:jersey-client|1.19.4|间接依赖|maven|
|org.apache.kerby:kerb-server|1.0.1|间接依赖|maven|
|io.netty:netty-transport-rxtx|4.1.94.Final|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-api|5.8.2|直接依赖|maven|
|io.opentelemetry:opentelemetry-context|1.26.0|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.0.5|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-smile|2.13.5|间接依赖|maven|
|org.apache.paimon:paimon-oss|0.4.0-incubating|直接依赖|maven|
|org.roaringbitmap:shims|0.7.45|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet-core|2.31|间接依赖|maven|
|org.apache.hudi:hudi-client-common|0.13.1|间接依赖|maven|
|com.google.uzaygezen:uzaygezen-core|0.2|间接依赖|maven|
|org.projectlombok:lombok|1.18.20|直接依赖|maven|
|software.amazon.awssdk:protocol-core|2.17.257|直接依赖|maven|
|org.eclipse.jetty.websocket:javax-websocket-client-impl|9.4.48.v20220622|间接依赖|maven|
|org.hamcrest:hamcrest|2.1|间接依赖|maven|
|jline:jline|0.9.94|间接依赖|maven|
|github.com/PaesslerAG/jsonpath|v0.1.1|间接依赖|go|
|software.amazon.awssdk:aws-json-protocol|2.17.257|直接依赖|maven|
|com.jcraft:jsch|0.1.55|间接依赖|maven|
|org.apache.spark:spark-sketch_2.12|3.2.0|间接依赖|maven|
|org.apache.flink:flink-file-sink-common|1.15.3|间接依赖|maven|
|bignumber.js|9.0.0|间接依赖|npm|
|org.apache.ant:ant-junit|1.10.9|间接依赖|maven|
|junit:junit|3.8.1|间接依赖|maven|
|org.apache.solr:solr-solrj|8.11.2|间接依赖|maven|
|github.com/elastic/go-lumber|v0.1.0|间接依赖|go|
|org.apache.parquet:parquet-hadoop|1.8.3|间接依赖|maven|
|org.codehaus.janino:commons-compiler|3.1.6|间接依赖|maven|
|io.fabric8:kubernetes-model|6.7.2|直接依赖|maven|
|com.squareup.okhttp3:logging-interceptor|4.7.2|直接依赖|maven|
|com.mchange:mchange-commons-java|0.2.15|间接依赖|maven|
|org.apache.hadoop:hadoop-hdfs-client|2.10.2|间接依赖|maven|
|org.antlr:antlr4-runtime|4.8|间接依赖|maven|
|com.qcloud:cos_api-bundle|5.6.69|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|2.8.0|间接依赖|maven|
|io.airlift:aircompressor|0.8|间接依赖|maven|
|io.netty:netty-transport|4.1.94.Final|间接依赖|maven|
|org.apache.flink:flink-table-api-scala_2.12|1.15.3|间接依赖|maven|
|org.apache.hadoop:hadoop-common|3.1.0|间接依赖|maven|
|org.apache.hadoop:hadoop-common|2.8.3|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.4.1|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.10.5|间接依赖|maven|
|commons-io:commons-io|2.7|直接依赖|maven|
|org.apache.avro:avro-mapred|1.7.7|间接依赖|maven|
|org.apache.hbase:hbase-common|1.2.3|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.8.11|间接依赖|maven|
|org.apache.hadoop:hadoop-auth|2.6.5|间接依赖|maven|
|org.apache.flink:flink-connector-jdbc_2.11|1.12.2|直接依赖|maven|
|com.amazonaws:aws-java-sdk-core|1.11.95|间接依赖|maven|
|org.eclipse.jetty:jetty-servlets|9.4.33.v20201020|间接依赖|maven|
|org.wildfly.client:wildfly-client-config|1.0.1.Final|间接依赖|maven|
|asm:asm-tree|3.1|间接依赖|maven|
|org.apache.spark:spark-launcher_2.12|2.4.6|间接依赖|maven|
|com.clickhouse:clickhouse-jdbc|0.4.6|直接依赖|maven|
|org.apache.ranger:ranger-plugins-cred|2.4.0|间接依赖|maven|
|github.com/hashicorp/errwrap|v1.0.0|间接依赖|go|
|com.thoughtworks.qdox:qdox|1.12.1|间接依赖|maven|
|org.apache.kerby:kerb-client|1.0.1|间接依赖|maven|
|org.elasticsearch:elasticsearch-lz4|7.17.10|间接依赖|maven|
|commons-fileupload:commons-fileupload|1.3.3|间接依赖|maven|
|org.codehaus.woodstox:stax2-api|3.1.4|间接依赖|maven|
|org.apache.paimon:paimon-shade-guava-30|30.1.1-jre-0.4.0-incubating|间接依赖|maven|
|commons-io:commons-io|2.5|直接依赖|maven|
|io.netty:netty-common|4.1.94.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-devtools|2.7.3|间接依赖|maven|
|github.com/eapache/go-resiliency|v1.2.0|间接依赖|go|
|com.github.scopt:scopt_2.12|3.5.0|间接依赖|maven|
|org.apache.kafka:connect-runtime|2.7.0|间接依赖|maven|
|io.dropwizard.metrics:metrics-jmx|4.2.19|间接依赖|maven|
|org.springframework:spring-aop|5.2.0.RELEASE|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.18.0|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-common|2.8.3|间接依赖|maven|
|com.github.scopt:scopt_2.11|3.5.0|间接依赖|maven|
|org.apache.flink:flink-scala_2.12|1.12.2|间接依赖|maven|
|org.apache.hive:hive-serde|3.1.3|直接依赖|maven|
|org.elasticsearch:elasticsearch-secure-sm|7.5.1|间接依赖|maven|
|github.com/go-logr/logr|v0.4.0|间接依赖|go|
|github.com/google/flatbuffers|v1.12.1|间接依赖|go|
|org.apache.lucene:lucene-spatial-extras|8.3.0|间接依赖|maven|
|org.codehaus.jackson:jackson-xc|1.9.13|间接依赖|maven|
|org.scala-lang.modules:scala-parser-combinators_2.11|1.1.1|间接依赖|maven|
|github.com/dop251/goja_nodejs|v0.0.0-20171011081505-adff31b136e6|间接依赖|go|
|github.com/go-sourcemap/sourcemap|v2.1.2+incompatible|间接依赖|go|
|go.elastic.co/apm/module/apmelasticsearch|v1.7.2|间接依赖|go|
|org.codehaus.groovy:groovy-testng|3.0.7|间接依赖|maven|
|org.apache.hadoop:hadoop-common|3.3.6|直接依赖|maven|
|com.clearspring.analytics:stream|2.7.0|间接依赖|maven|
|org.apache.ant:ant-antlr|1.10.9|间接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.30.0|间接依赖|maven|
|org.glassfish.jersey.core:jersey-client|2.22.2|间接依赖|maven|
|org.slf4j:slf4j-log4j12|1.7.30|直接依赖|maven|
|org.apache.ant:ant-launcher|1.10.12|间接依赖|maven|
|org.apache.hadoop:hadoop-common|2.8.0|直接依赖|maven|
|org.apache.hbase:hbase-procedure|1.2.3|间接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-otlp|1.26.0|直接依赖|maven|
|com.twitter:chill-java|0.9.3|间接依赖|maven|
|org.scala-lang:scala-library|2.11.12|直接依赖|maven|
|org.apache.kafka:connect-file|2.7.0|间接依赖|maven|
|org.codehaus.plexus:plexus-io|3.2.0|间接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|3.9|间接依赖|maven|
|org.apache.hbase.thirdparty:hbase-shaded-protobuf|3.5.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.10.0|直接依赖|maven|
|org.apache.hadoop:hadoop-client|2.8.3|直接依赖|maven|
|org.eclipse.jetty:jetty-continuation|9.4.51.v20230217|间接依赖|maven|
|com.aliyun.datalake:shims-hive2|0.2.14|间接依赖|maven|
|org.apache.hbase:hbase-hadoop2-compat|1.2.3|间接依赖|maven|
|org.jodd:jodd-util|6.0.0|间接依赖|maven|
|org.apache.flink:flink-hadoop-fs|1.12.2|间接依赖|maven|
|tox|3.13|间接依赖|pip|
|github.com/golang/snappy|v0.0.4|间接依赖|go|
|org.slf4j:slf4j-log4j12|1.7.16|间接依赖|maven|
|io.fabric8:kubernetes-model-events|5.12.2|间接依赖|maven|
|org.scala-lang.modules:scala-java8-compat_2.11|0.7.0|间接依赖|maven|
|org.ow2.asm:asm-tree|9.4|间接依赖|maven|
|org.lz4:lz4-java|1.6.0|间接依赖|maven|
|org.apache.hadoop:hadoop-hdfs|2.10.2|直接依赖|maven|
|io.fabric8:kubernetes-client|5.12.2|间接依赖|maven|
|org.codehaus.groovy:groovy-templates|3.0.7|间接依赖|maven|
|io.netty:netty-codec-mqtt|4.1.94.Final|间接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.4.38.v20210224|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.10.0|间接依赖|maven|
|org.apache.hbase.thirdparty:hbase-shaded-gson|3.5.1|间接依赖|maven|
|org.apache.hive:hive-shims|3.1.3|间接依赖|maven|
|com.jcraft:jsch|0.1.51|间接依赖|maven|
|org.glassfish.jersey.bundles.repackaged:jersey-guava|2.22.2|间接依赖|maven|
|org.springframework:spring-context|5.2.0.RELEASE|间接依赖|maven|
|org.apache.commons:commons-csv|1.9.0|直接依赖|maven|
|com.alibaba.ververica:flink-connector-mysql-cdc|1.3.0|直接依赖|maven|
|com.alibaba.datax:plugin-rdbms-util||直接依赖|maven|
|io.prometheus:simpleclient_tracer_otel_agent|0.15.0|间接依赖|maven|
|io.fabric8:kubernetes-client|6.7.2|直接依赖|maven|
|github.com/grpc-ecosystem/grpc-gateway|v1.16.0|间接依赖|go|
|github.com/jcmturner/gofork|v1.0.0|间接依赖|go|
|github.com/yuin/gopher-lua|v0.0.0-20170403160031-b402f3114ec7|间接依赖|go|
|org.springframework.boot:spring-boot-starter-data-ldap|2.7.3|间接依赖|maven|
|asm:asm-commons|3.1|间接依赖|maven|
|org.apache.curator:curator-framework|2.6.0|间接依赖|maven|
|github.com/elastic/go-txfile|v0.0.7|间接依赖|go|
|org.elasticsearch:elasticsearch-plugin-classloader|7.17.10|间接依赖|maven|
|io.netty:netty-codec-http|4.1.17.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.10.5|间接依赖|maven|
|org.apache.lucene:lucene-queries|8.3.0|间接依赖|maven|
|sigs.k8s.io/yaml|v1.2.0|间接依赖|go|
|com.esotericsoftware:kryo-shaded|3.0.3|间接依赖|maven|
|org.apache.spark:spark-unsafe_2.12|3.2.0|间接依赖|maven|
|io.dropwizard.metrics:metrics-graphite|3.1.5|间接依赖|maven|
|org.apache.flink:flink-connector-jdbc|1.15.3|直接依赖|maven|
|org.codehaus.jettison:jettison|1.5.4|间接依赖|maven|
|org.codehaus.plexus:plexus-compiler-manager|2.11.1|间接依赖|maven|
|javax.activation:activation|1.1|间接依赖|maven|
|org.apache.kerby:kerby-config|2.0.3|间接依赖|maven|
|net.java.dev.jets3t:jets3t|0.9.4|间接依赖|maven|
|github.com/prometheus/client_model|v0.2.0|间接依赖|go|
|org.codehaus.plexus:plexus-utils|3.3.0|间接依赖|maven|
|software.amazon.awssdk:protocol-core|2.15.45|间接依赖|maven|
|io.fabric8:openshift-model|6.7.2|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.28|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.52|间接依赖|maven|
|org.json4s:json4s-scalap_2.12|3.7.0-M11|间接依赖|maven|
|org.springframework:spring-web|5.3.22|间接依赖|maven|
|org.json4s:json4s-core_2.11|3.2.11|间接依赖|maven|
|com.github.oshi:oshi-core|4.0.0|直接依赖|maven|
|org.apache.hadoop:hadoop-hdfs|3.3.6|直接依赖|maven|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|io.opentelemetry:opentelemetry-sdk-common|1.26.0|间接依赖|maven|
|github.com/PaesslerAG/gval|v1.0.0|间接依赖|go|
|org.apache.arrow:arrow-memory-unsafe|9.0.0|直接依赖|maven|
|org.apache.kerby:kerb-simplekdc|1.0.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.6.0|间接依赖|maven|
|com.aliyun.datalake:metastore-client-hive2|0.2.14|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.94.Final|间接依赖|maven|
|github.com/hashicorp/go-uuid|v1.0.2|间接依赖|go|
|org.apache.kafka:kafka-clients|0.10.1.1|间接依赖|maven|
|org.apache.calcite.avatica:avatica-metrics|1.22.0|间接依赖|maven|
|io.airlift:aircompressor|0.10|间接依赖|maven|
|io.grpc:grpc-protobuf|1.30.0|直接依赖|maven|
|com.oracle.ojdbc:ojdbc8|19.3.0.0|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.2.11|间接依赖|maven|
|org.apache.lucene:lucene-analyzers-common|8.3.0|间接依赖|maven|
|org.apache.hadoop:hadoop-aliyun|2.10.2|直接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.7.2|间接依赖|maven|
|org.elasticsearch:elasticsearch-secure-sm|7.10.2|间接依赖|maven|
|io.fabric8:kubernetes-model-apps|5.12.2|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-ram|3.0.0|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.10.0|间接依赖|maven|
|io.netty:netty|3.7.0.Final|间接依赖|maven|
|org.apache.commons:commons-math|2.2|间接依赖|maven|
|org.elasticsearch:elasticsearch-geo|7.5.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.6.5|间接依赖|maven|
|org.apache.kerby:kerb-core|1.0.1|间接依赖|maven|
|io.fabric8:kubernetes-model-admissionregistration|6.7.2|间接依赖|maven|
|github.com/mattn/go-colorable|v0.1.6|间接依赖|go|
|io.fabric8:kubernetes-model-node|6.7.2|间接依赖|maven|
|org.apache.avro:avro-ipc|1.8.2|间接依赖|maven|
|golang.org/x/mod|v0.4.2|间接依赖|go|
|org.springframework.boot:spring-boot-starter-logging|2.7.13|间接依赖|maven|
|org.apache.kerby:kerby-util|1.0.1|间接依赖|maven|
|org.apache.calcite:calcite-core|1.32.0|间接依赖|maven|
|org.apache.flink:flink-shaded-netty|4.1.70.Final-15.0|间接依赖|maven|
|org.apache.commons:commons-lang3|3.3.2|直接依赖|maven|
|joda-time:joda-time|2.10.3|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.2.0.RELEASE|间接依赖|maven|
|com.google.code.gson:gson|2.8.6|间接依赖|maven|
|gopkg.in/jcmturner/gokrb5.v7|v7.5.0|间接依赖|go|
|org.springframework:spring-jcl|5.3.28|间接依赖|maven|
|org.checkerframework:checker-util|3.32.0|间接依赖|maven|
|com.carrotsearch:hppc|0.7.2|间接依赖|maven|
|org.apache.maven.shared:maven-shared-incremental|1.1|间接依赖|maven|
|com.aliyun:datalake20200710|2.0.2|间接依赖|maven|
|org.apache.htrace:htrace-core4|4.0.1-incubating|间接依赖|maven|
|org.apache.flink:flink-shaded-guava|18.0-12.0|间接依赖|maven|
|org.apache.orc:orc-shims|1.8.4|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.70|间接依赖|maven|
|io.opentelemetry:opentelemetry-api-events|1.26.0-alpha|间接依赖|maven|
|org.apache.hadoop:hadoop-auth|2.5.1|间接依赖|maven|
|org.apache.paimon:paimon-hive-connector-2.3|0.4.0-incubating|直接依赖|maven|
|net.sourceforge.argparse4j:argparse4j|0.7.0|间接依赖|maven|
|com.aliyun.datalake:metastore-client-common|0.2.14|间接依赖|maven|
|org.apache.parquet:parquet-jackson|1.8.3|间接依赖|maven|
|commons-cli:commons-cli|1.5.0|直接依赖|maven|
|com.typesafe.netty:netty-reactive-streams|2.0.4|间接依赖|maven|
|io.prometheus:simpleclient_httpserver|0.15.0|间接依赖|maven|
|org.lz4:lz4-pure-java|1.8.0|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.10|间接依赖|maven|
|net.sf.py4j:py4j|0.10.7|间接依赖|maven|
|com.google.inject.extensions:guice-servlet|4.0|间接依赖|maven|
|org.jboss.xnio:xnio-api|3.8.8.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.6.5|间接依赖|maven|
|jline:jline|2.14.6|间接依赖|maven|
|org.codehaus.plexus:plexus-classworlds|2.2.3|间接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.94.Final|间接依赖|maven|
|org.apache.flink:flink-connector-kafka_2.12|1.12.2|直接依赖|maven|
|mypy|0.782|间接依赖|pip|
|org.elasticsearch.client:elasticsearch-rest-client|7.5.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.2.0.RELEASE|直接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.3|间接依赖|maven|
|com.oracle.ojdbc:simplefan|19.3.0.0|间接依赖|maven|
|github.com/joeshaw/multierror|v0.0.0-20140124173710-69b34d4ec901|间接依赖|go|
|com.squareup.okhttp:okhttp|2.4.0|间接依赖|maven|
|org.codehaus.janino:janino|2.7.6|间接依赖|maven|
|org.springframework:spring-core|5.2.0.RELEASE|间接依赖|maven|
|org.apache.hbase.thirdparty:hbase-shaded-jersey|3.5.1|间接依赖|maven|
|org.apache.curator:apache-curator|2.12.0|间接依赖|maven|
|org.elasticsearch:elasticsearch-core|7.5.1|间接依赖|maven|
|github.com/stretchr/testify|v1.7.0|间接依赖|go|
|github.com/dlclark/regexp2|v1.1.7-0.20171009020623-7632a260cbaf|间接依赖|go|
|org.springframework.boot:spring-boot-starter-web|2.2.0.RELEASE|直接依赖|maven|
|javax.servlet.jsp:javax.servlet.jsp-api|2.3.1|间接依赖|maven|
|github.com/eapache/go-xerial-snappy|v0.0.0-20180814174437-776d5712da21|间接依赖|go|
|io.netty:netty-transport-native-unix-common|4.1.94.Final|间接依赖|maven|
|github.com/google/go-cmp|v0.5.6|间接依赖|go|
|org.apache.thrift:libthrift|0.16.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.10.0|间接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.65|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|2.7.2|间接依赖|maven|
|org.json4s:json4s-scalap_2.12|3.5.3|间接依赖|maven|
|it.unimi.dsi:fastutil|7.0.13|间接依赖|maven|
|de.ruedigermoeller:fst|2.50|间接依赖|maven|
|ch.qos.reload4j:reload4j|1.2.22|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.53.Final|间接依赖|maven|
|org.codehaus.janino:janino|3.0.8|间接依赖|maven|
|org.apache.flink:flink-runtime_2.11|1.12.2|间接依赖|maven|
|org.apache.hive:hive-vector-code-gen|3.1.3|间接依赖|maven|
|isarray|1.0.0|间接依赖|npm|
|org.apache.flink:flink-shaded-netty|4.1.49.Final-12.0|间接依赖|maven|
|org.apache.arrow:arrow-memory|0.8.0|间接依赖|maven|
|org.apache.hive:hive-service-rpc|3.1.3|间接依赖|maven|
|io.fabric8:kubernetes-model-common|6.7.2|间接依赖|maven|
|org.eclipse.jetty:jetty-http|9.4.51.v20230217|间接依赖|maven|
|io.fabric8:kubernetes-model-policy|6.7.2|间接依赖|maven|
|org.apache.spark:spark-network-shuffle_2.12|2.4.6|间接依赖|maven|
|org.lz4:lz4-java|1.8.0|间接依赖|maven|
|io.netty:netty-codec-http|4.1.94.Final|间接依赖|maven|
|safe-buffer|5.1.2|间接依赖|npm|
|com.jamesmurty.utils:java-xmlbuilder|1.1|间接依赖|maven|
|org.apache.maven:maven-artifact|3.0|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-metrics|1.14.0|间接依赖|maven|
|org.slf4j:slf4j-log4j12|1.7.25|间接依赖|maven|
|com.alibaba.otter:canal.client|1.1.6|直接依赖|maven|
|io.fabric8:kubernetes-model-apiextensions|6.7.2|间接依赖|maven|
|software.amazon.awssdk:sdk-core|2.15.45|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-ldap|2.7.13|直接依赖|maven|
|github.com/jcmturner/dnsutils/v2|v2.0.0|间接依赖|go|
|com.fasterxml.jackson.core:jackson-core|2.12.0|间接依赖|maven|
|org.codehaus.jettison:jettison|1.1|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-servlet|9.4.51.v20230217|间接依赖|maven|
|com.typesafe:config|1.3.3|间接依赖|maven|
|com.ververica:flink-connector-oracle-cdc|2.1.1|直接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.9.13|间接依赖|maven|
|org.apache.directory.server:apacheds-i18n|2.0.0-M15|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.2.0.RELEASE|直接依赖|maven|
|org.opentest4j:opentest4j|1.2.0|间接依赖|maven|
|software.amazon.awssdk:aws-core|2.15.45|间接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j-impl|2.17.1|间接依赖|maven|
|golang.org/x/lint|v0.0.0-20210508222113-6edffad5e616|间接依赖|go|
|org.codehaus.plexus:plexus-component-annotations|1.5.5|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|3.3.6|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|2.6.5|间接依赖|maven|
|go.uber.org/tools|v0.0.0-20190618225709-2cfd321de3ee|间接依赖|go|
|org.locationtech.jts:jts-core|1.16.1|间接依赖|maven|
|org.codehaus.janino:janino|3.0.16|直接依赖|maven|
|asm:asm|3.1|间接依赖|maven|
|github.com/mitchellh/hashstructure|v0.0.0-20170116052023-ab25296c0f51|间接依赖|go|
|com.typesafe.akka:akka-stream_2.11|2.5.21|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|3.1.0|间接依赖|maven|
|github.com/miekg/dns|v1.1.25|间接依赖|go|
|org.apache.kerby:kerb-core|2.0.3|间接依赖|maven|
|com.google.guava:guava|30.0-jre|间接依赖|maven|
|org.eclipse.jetty:jetty-client|9.4.51.v20230217|间接依赖|maven|
|org.apache.commons:commons-math3|3.6.1|间接依赖|maven|
|org.apache.kerby:kerby-xdr|1.0.1|间接依赖|maven|
|org.apache.lucene:lucene-grouping|8.3.0|间接依赖|maven|
|org.apache.kafka:kafka-clients|2.8.1|间接依赖|maven|
|org.aspectj:aspectjweaver|1.9.7|直接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.1|间接依赖|maven|
|com.carrotsearch:hppc|0.8.1|间接依赖|maven|
|com.google.protobuf:protobuf-java|2.6.0|间接依赖|maven|
|org.codehaus.groovy:groovy-all|2.4.11|间接依赖|maven|
|org.objenesis:objenesis|2.1|直接依赖|maven|
|net.java.dev.jna:jna-platform|5.5.0|直接依赖|maven|
|org.checkerframework:checker-compat-qual|2.5.3|间接依赖|maven|
|org.apache.flink:flink-core|1.12.2|间接依赖|maven|
|github.com/bits-and-blooms/bitset|v1.2.0|间接依赖|go|
|com.aliyun.datalake:shims-load|0.2.14|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jetty|2.7.13|直接依赖|maven|
|com.google.inject:guice|4.0|间接依赖|maven|
|com.amazonaws:jmespath-java|1.12.519|间接依赖|maven|
|jakarta.ws.rs:jakarta.ws.rs-api|2.1.6|间接依赖|maven|
|mysql:mysql-connector-java|8.0.23|直接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|org.wildfly.client:wildfly-client-config|1.0.0.Final|间接依赖|maven|
|org.apache.flink:flink-runtime_2.12|1.12.2|间接依赖|maven|
|org.yaml:snakeyaml|1.17|间接依赖|maven|
|org.apache.orc:orc-core|1.6.0|间接依赖|maven|
|com.cedarsoftware:json-io|2.5.1|间接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|github.com/jonboulle/clockwork|v0.2.2|间接依赖|go|
|org.scala-lang.modules:scala-parser-combinators_2.11|1.0.4|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.2.6|间接依赖|maven|
|io.fabric8:kubernetes-model-flowcontrol|6.7.2|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.25|直接依赖|maven|
|org.apache.hudi:hudi-spark3.2plus-common|0.13.1|间接依赖|maven|
|org.antlr:antlr-runtime|3.5.2|间接依赖|maven|
|com.ververica:flink-connector-debezium|2.3.0|间接依赖|maven|
|net.sourceforge.javacsv:javacsv|2.0|间接依赖|maven|
|org.apache.flink:flink-queryable-state-client-java|1.15.3|间接依赖|maven|
|com.carrotsearch:hppc|0.8.0|间接依赖|maven|
|org.codehaus.groovy:groovy-astbuilder|3.0.7|间接依赖|maven|
|org.apache.paimon:paimon-s3|0.4.0-incubating|直接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-high-level-client|7.5.1|间接依赖|maven|
|org.apache.htrace:htrace-core4|4.2.0-incubating|间接依赖|maven|
|com.squareup.okio:okio|1.14.0|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-extension-autoconfigure-spi|1.26.0|间接依赖|maven|
|io.fabric8:kubernetes-model-certificates|5.12.2|间接依赖|maven|
|org.apache.ant:ant|1.9.1|间接依赖|maven|
|org.apache.flink:flink-connector-elasticsearch-base_2.12|1.12.2|间接依赖|maven|
|org.apache.flink:flink-streaming-java_2.12|1.12.2|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.4|间接依赖|maven|
|org.apache.kafka:kafka-clients|2.4.1|间接依赖|maven|
|org.htrace:htrace-core|3.0.4|间接依赖|maven|
|github.com/urso/diag|v0.0.0-20200210123136-21b3cc8eb797|间接依赖|go|
|org.apache.hadoop:hadoop-mapreduce-client-core|2.6.5|间接依赖|maven|
|github.com/jcmturner/aescts/v2|v2.0.0|间接依赖|go|
|commons-collections:commons-collections|3.2.1|间接依赖|maven|
|org.apache.hbase:hbase-protocol|2.4.9|间接依赖|maven|
|org.apache.kerby:kerby-asn1|1.0.1|间接依赖|maven|
|com.google.re2j:re2j|1.1|间接依赖|maven|
|io.netty:netty-handler|4.1.94.Final|间接依赖|maven|
|org.json4s:json4s-core_2.12|3.7.0-M11|间接依赖|maven|
|org.apache.curator:curator-client|2.7.1|间接依赖|maven|
|org.apache.flink:flink-table-common|1.12.2|间接依赖|maven|
|org.apache.curator:curator-framework|2.12.0|间接依赖|maven|
|org.apache.hadoop:hadoop-hdfs-client|2.8.0|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.22|间接依赖|maven|
|com.amazonaws:aws-java-sdk-kms|1.11.95|间接依赖|maven|
|org.apache.maven:maven-settings|3.0|间接依赖|maven|
|org.elasticsearch:jna|4.5.1|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|3.1.5|间接依赖|maven|
|org.javassist:javassist|3.24.0-GA|间接依赖|maven|
|org.apache.maven:maven-repository-metadata|3.0|间接依赖|maven|
|software.amazon.awssdk:netty-nio-client|2.17.257|间接依赖|maven|
|org.clapper:grizzled-slf4j_2.12|1.3.2|间接依赖|maven|
|com.esotericsoftware:kryo-shaded|4.0.2|直接依赖|maven|
|com.esotericsoftware:reflectasm|1.11.9|直接依赖|maven|
|org.eclipse.jetty:jetty-continuation|9.4.38.v20210224|间接依赖|maven|
|github.com/BurntSushi/toml|v0.3.1|间接依赖|go|
|org.scala-lang.modules:scala-collection-compat_2.11|2.8.1|间接依赖|maven|
|org.apache.calcite:calcite-core|1.16.0|间接依赖|maven|
|com.alibaba.fastjson2:fastjson2|2.0.4|间接依赖|maven|
|com.twitter:chill_2.11|0.8.4|间接依赖|maven|
|org.apache.hadoop:hadoop-common|2.10.2|直接依赖|maven|
|org.apache.hadoop:hadoop-huaweicloud|2.8.3|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-web-proxy|3.1.0|间接依赖|maven|
|org.apiguardian:apiguardian-api|1.1.2|间接依赖|maven|
|org.apache.logging.log4j:log4j-web|2.17.1|间接依赖|maven|
|com.alibaba:fastjson|1.2.78|直接依赖|maven|
|org.apache.flink:flink-cep|1.15.3|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.1.3|间接依赖|maven|
|com.sun.jersey:jersey-core|1.9|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.10.5|间接依赖|maven|
|org.apache.arrow:arrow-memory-netty|2.0.0|间接依赖|maven|
|org.codehaus.janino:commons-compiler|2.7.6|间接依赖|maven|
|io.opentracing:opentracing-noop|0.33.0|间接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|1.17.0|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.4.6|间接依赖|maven|
|com.sun.jersey:jersey-server|1.19|间接依赖|maven|
|io.delta:delta-standalone_2.12|3.0.0rc1|直接依赖|maven|
|org.apache.curator:curator-client|2.6.0|间接依赖|maven|
|github.com/lib/pq|v1.1.2-0.20190507191818-2ff3cb3adc01|间接依赖|go|
|com.sun.jersey.contribs:jersey-guice|1.19.4|间接依赖|maven|
|org.apache.flink:flink-shaded-asm-9|9.2-15.0|间接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.51.v20230217|间接依赖|maven|
|github.com/urso/sderr|v0.0.0-20210525210834-52b04e8f5c71|间接依赖|go|
|org.springframework.boot:spring-boot-configuration-processor|2.7.3|间接依赖|maven|
|org.eclipse.jetty:jetty-server|9.4.33.v20201020|间接依赖|maven|
|github.com/gofrs/uuid|v3.3.0+incompatible|间接依赖|go|
|github.com/elastic/ecs|v1.12.0|间接依赖|go|
|org.scala-lang:scala-library|2.12.10|直接依赖|maven|
|io.opentracing:opentracing-util|0.33.0|间接依赖|maven|
|org.apache.kafka:connect-runtime|2.7.1|间接依赖|maven|
|org.apache.hadoop:hadoop-auth|2.10.2|直接依赖|maven|
|javax.servlet:servlet-api|2.5|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.16|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk|1.14.0|间接依赖|maven|
|org.apache.arrow:arrow-vector|2.0.0|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.94.Final|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.35|间接依赖|maven|
|com.twitter:chill-java|0.8.4|间接依赖|maven|
|github.com/jcmturner/gokrb5/v8|v8.4.2|间接依赖|go|
|org.apache.hbase:hbase-zookeeper|2.4.9|间接依赖|maven|
|org.json4s:json4s-ast_2.12|3.5.3|间接依赖|maven|
|org.glassfish.hk2:hk2-locator|2.4.0-b34|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-scala_2.12|2.6.7.1|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-servlet|9.4.48.v20220622|间接依赖|maven|
|io.fabric8:kubernetes-model-metrics|5.12.2|间接依赖|maven|
|org.scala-lang:scalap|2.11.0|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|org.scala-lang.modules:scala-xml_2.11|1.0.1|间接依赖|maven|
|org.apache.commons:commons-lang3|3.1|间接依赖|maven|
|org.apache.ant:ant-launcher|1.9.1|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.21.12|直接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.16|间接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5|5.1.5|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-api|9.4.48.v20220622|间接依赖|maven|
|io.netty:netty-buffer|4.1.17.Final|间接依赖|maven|
|org.codehaus.plexus:plexus-interpolation|1.25|间接依赖|maven|
|org.codehaus.groovy:groovy-docgenerator|3.0.7|间接依赖|maven|
|com.google.flogger:google-extensions|0.7.1|间接依赖|maven|
|github.com/dop251/goja|v0.0.0-20200831102558-9af81ddcf0e1|间接依赖|go|
|org.apache.lucene:lucene-analyzers-common|8.4.0|间接依赖|maven|
|com.oracle.database.security:osdt_core|21.5.0.0|间接依赖|maven|
|com.aliyun:endpoint-util|0.0.6|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.12.0|间接依赖|maven|
|com.yammer.metrics:metrics-core|2.2.0|间接依赖|maven|
|org.codehaus.groovy:groovy-test-junit5|3.0.7|间接依赖|maven|
|org.apache.paimon:paimon-shade-caffeine-2|2.9.3-0.4.0-incubating|间接依赖|maven|
|org.apache.kerby:kerb-admin|2.0.3|间接依赖|maven|
|org.apache.curator:curator-client|2.12.0|间接依赖|maven|
|com.tdunning:t-digest|3.2|间接依赖|maven|
|org.apache.kerby:kerb-crypto|1.0.1|间接依赖|maven|
|org.apache.directory.api:api-util|1.0.0-M20|间接依赖|maven|
|org.apache.hadoop:hadoop-hdfs-client|3.3.6|间接依赖|maven|
|com.squareup:protoparser|3.1.5|直接依赖|maven|
|io.dropwizard.metrics:metrics-json|3.1.5|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.51.v20230217|间接依赖|maven|
|org.jdom:jdom|1.1|间接依赖|maven|
|go.uber.org/atomic|v1.5.0|间接依赖|go|
|org.codehaus.groovy:groovy-all|2.4.4|间接依赖|maven|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|org.slf4j:slf4j-api|1.7.10|间接依赖|maven|
|org.elasticsearch.plugin:lang-mustache-client|7.5.1|间接依赖|maven|
|org.apache.calcite.avatica:avatica|1.11.0|间接依赖|maven|
|org.mortbay.jetty:jetty-sslengine|6.1.26|间接依赖|maven|
|org.tukaani:xz|1.5|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.13|间接依赖|maven|
|org.apache.maven:maven-model-builder|3.0|间接依赖|maven|
|org.ow2.asm:asm-commons|9.3|间接依赖|maven|
|org.eclipse.jetty:jetty-http|9.4.33.v20201020|间接依赖|maven|
|org.apache.kerby:kerby-xdr|2.0.3|间接依赖|maven|
|org.apache.flink:flink-table-api-scala-bridge_2.12|1.15.3|直接依赖|maven|
|org.apache.commons:commons-math3|3.1.1|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-common|9.4.48.v20220622|间接依赖|maven|
|io.debezium:debezium-api|1.6.4.Final|间接依赖|maven|
|org.apache.commons:commons-configuration2|2.1.1|间接依赖|maven|
|com.twitter:chill-java|0.7.6|间接依赖|maven|
|org.checkerframework:checker-util|3.22.2|间接依赖|maven|
|org.sonatype.sisu:sisu-inject-plexus|1.4.2|间接依赖|maven|
|com.oracle.ojdbc:ons|19.3.0.0|间接依赖|maven|
|org.slf4j:slf4j-log4j12|1.7.15|间接依赖|maven|
|com.typesafe.akka:akka-slf4j_2.11|2.5.21|间接依赖|maven|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|io.netty:netty-resolver|4.1.94.Final|间接依赖|maven|
|org.codehaus.groovy:groovy-datetime|3.0.7|间接依赖|maven|
|org.scala-lang.modules:scala-parser-combinators_2.12|1.1.2|间接依赖|maven|
|org.apache.paimon:paimon-codegen-loader|0.4.0-incubating|间接依赖|maven|
|k8s.io/utils|v0.0.0-20201110183641-67b214c5f920|间接依赖|go|
|org.apache.flink:flink-shaded-hadoop-2-uber|2.6.5-10.0|直接依赖|maven|
|com.ververica:flink-connector-mysql-cdc|2.3.0|直接依赖|maven|
|de.jflex:jflex|1.4.3|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.14.1|间接依赖|maven|
|org.apache.orc:orc-core|1.5.8|间接依赖|maven|
|org.eclipse.jetty:jetty-rewrite|9.3.20.v20170531|间接依赖|maven|
|org.apache.orc:orc-shims|1.5.8|间接依赖|maven|
|org.apache.parquet:parquet-jackson|1.13.1|间接依赖|maven|
|commons-cli:commons-cli|1.4|直接依赖|maven|
|org.apache.calcite:calcite-linq4j|1.10.0|间接依赖|maven|
|org.springframework:spring-expression|5.0.5.RELEASE|间接依赖|maven|
|com.univocity:univocity-parsers|2.5.9|间接依赖|maven|
|com.typesafe.akka:akka-protobuf_2.12|2.5.21|间接依赖|maven|
|org.apache.flink:flink-connector-kafka|1.15.3|直接依赖|maven|
|com.google.guava:guava|14.0.1|间接依赖|maven|
|org.apache.ant:ant-launcher|1.10.9|间接依赖|maven|
|org.eclipse.jetty:jetty-http|9.4.38.v20210224|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|2.7.2|间接依赖|maven|
|com.google.guava:guava|15.0|直接依赖|maven|
|com.lmax:disruptor|3.3.0|间接依赖|maven|
|org.apache.geronimo.specs:geronimo-jaspic_1.0_spec|1.0|间接依赖|maven|
|org.apache.kerby:kerb-common|1.0.1|间接依赖|maven|
|io.fabric8:kubernetes-model-rbac|5.12.2|间接依赖|maven|
|org.apache.spark:spark-tags_2.11|2.3.4|间接依赖|maven|
|org.apache.hive:hive-storage-api|2.7.2|间接依赖|maven|
|org.apache.kafka:connect-json|2.7.0|间接依赖|maven|
|org.apache.avro:avro-ipc|1.10.2|间接依赖|maven|
|com.sun.jersey:jersey-client|1.19|间接依赖|maven|
|org.apache.hive:hive-exec|3.1.3|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.3|直接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|5.3.0|间接依赖|maven|
|com.sun.jersey:jersey-server|1.9|间接依赖|maven|
|javax.xml.soap:javax.xml.soap-api|1.4.0|间接依赖|maven|
|com.squareup.okio:okio-jvm|3.4.0|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.30|直接依赖|maven|
|org.apache.commons:commons-text|1.10.0|直接依赖|maven|
|com.sun.jersey:jersey-server|1.19.4|间接依赖|maven|
|golang.org/x/sys|v0.0.0-20211102192858-4dd72447c267|间接依赖|go|
|io.opentelemetry:opentelemetry-sdk-metrics|1.26.0|间接依赖|maven|
|github.com/gomodule/redigo|v1.8.3|间接依赖|go|
|net.jpountz.lz4:lz4|1.3.0|间接依赖|maven|
|org.slf4j:slf4j-simple|1.7.25|直接依赖|maven|
|org.apache.htrace:htrace-core4|4.1.0-incubating|间接依赖|maven|
|org.springframework:spring-context|5.3.28|间接依赖|maven|
|org.codehaus.groovy:groovy-groovydoc|3.0.7|间接依赖|maven|
|org.apache.commons:commons-dbcp2|2.6.0|间接依赖|maven|
|io.debezium:debezium-connector-mysql|1.6.4.Final|间接依赖|maven|
|io.netty:netty-transport-sctp|4.1.94.Final|间接依赖|maven|
|software.amazon.eventstream:eventstream|1.0.1|间接依赖|maven|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|org.apache.lucene:lucene-memory|8.4.0|间接依赖|maven|
|commons-pool:commons-pool|1.5.4|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-logs|1.26.0-alpha|间接依赖|maven|
|org.aspectj:aspectjrt|1.9.7|直接依赖|maven|
|org.eclipse.jetty:jetty-http|9.4.48.v20220622|间接依赖|maven|
|com.alibaba:druid|1.1.14|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.38.v20210224|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.94.Final|间接依赖|maven|
|commons-digester:commons-digester|1.8|间接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.5|间接依赖|maven|
|com.alibaba:druid|1.2.5|直接依赖|maven|
|io.grpc:grpc-stub|1.30.0|直接依赖|maven|
|org.springframework:spring-expression|5.2.0.RELEASE|间接依赖|maven|
|io.grpc:grpc-context|1.30.0|间接依赖|maven|
|github.com/imdario/mergo|v0.3.12|间接依赖|go|
|org.jboss.xnio:xnio-nio|3.8.9.Final|直接依赖|maven|
|org.iq80.snappy:snappy|0.4|间接依赖|maven|
|org.testng:testng|7.3.0|间接依赖|maven|
|org.apache.doris:thrift-service|1.0.0|直接依赖|maven|
|com.oracle.database.security:osdt_cert|21.5.0.0|间接依赖|maven|
|commons-logging:commons-logging|1.0.3|间接依赖|maven|
|github.com/opencontainers/go-digest|v1.0.0|间接依赖|go|
|github.com/davecgh/go-xdr|v0.0.0-20161123171359-e6a2ba005892|间接依赖|go|
|org.apache.hive:hive-llap-common|3.1.3|间接依赖|maven|
|org.apache.flink:flink-connector-files|1.12.2|间接依赖|maven|
|com.oracle.database.security:oraclepki|21.5.0.0|间接依赖|maven|
|org.apache.commons:commons-compress|1.20|间接依赖|maven|
|commons-lang:commons-lang|2.6|直接依赖|maven|
|org.apache.hadoop:hadoop-hdfs|2.6.5|间接依赖|maven|
|org.ow2.asm:asm|9.2|间接依赖|maven|
|io.grpc:grpc-core|1.30.0|间接依赖|maven|
|commons-codec:commons-codec|1.6|间接依赖|maven|
|com.clearspring.analytics:stream|2.9.6|间接依赖|maven|
|org.eclipse.jetty:jetty-continuation|9.4.33.v20201020|间接依赖|maven|
|org.apache.maven.plugins:maven-compiler-plugin|3.10.1|间接依赖|maven|
|commons-configuration:commons-configuration|1.6|直接依赖|maven|
|net.iharder:base64|2.3.8|间接依赖|maven|
|org.apache.flink:flink-clients_2.11|1.12.2|直接依赖|maven|
|io.prometheus:simpleclient_tracer_otel|0.15.0|间接依赖|maven|
|io.netty:netty-transport|4.1.17.Final|间接依赖|maven|
|org.apache.lucene:lucene-highlighter|8.4.0|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-client|9.4.51.v20230217|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.1.Final|间接依赖|maven|
|org.apache.hbase:hbase-metrics-api|2.4.9|间接依赖|maven|
|org.codehaus.groovy:groovy-swing|3.0.7|间接依赖|maven|
|com.google.flogger:flogger|0.7.1|间接依赖|maven|
|org.scala-lang:scala-compiler|2.12.7|间接依赖|maven|
|com.amazonaws:aws-java-sdk-dynamodb|1.12.519|直接依赖|maven|
|org.eclipse.jetty:jetty-plus|9.4.51.v20230217|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.13.5|间接依赖|maven|
|org.json4s:json4s-jackson_2.11|3.2.11|间接依赖|maven|
|software.amazon.awssdk:aws-query-protocol|2.17.257|间接依赖|maven|
|org.apache.spark:spark-sql_2.11|2.3.4|直接依赖|maven|
|org.apache.arrow:arrow-vector|0.8.0|间接依赖|maven|
|org.snakeyaml:snakeyaml-engine|2.6|间接依赖|maven|
|com.sun.jersey:jersey-servlet|1.19|间接依赖|maven|
|org.apache.hbase:hbase-protocol|1.2.3|间接依赖|maven|
|org.apache.doris:fe-core|1.2-SNAPSHOT|直接依赖|maven|
|io.dropwizard.metrics:metrics-graphite|4.2.19|间接依赖|maven|
|gopkg.in/jcmturner/rpc.v1|v1.1.0|间接依赖|go|
|io.fabric8:kubernetes-client-api|6.7.2|间接依赖|maven|
|github.com/go-sql-driver/mysql|v1.7.0|直接依赖|go|
|org.mortbay.jetty:jetty-util|6.1.26|间接依赖|maven|
|xpp3:xpp3|1.1.3.3|间接依赖|maven|
|org.apache.flink:flink-shaded-zookeeper-3|3.5.9-15.0|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-common|9.4.51.v20230217|间接依赖|maven|
|io.fabric8:kubernetes-model-extensions|5.12.2|间接依赖|maven|
|com.qcloud:chdfs_hadoop_plugin_network|2.7|间接依赖|maven|
|github.com/Shopify/sarama|v0.0.0-00010101000000-000000000000|间接依赖|go|
|com.google.guava:guava|16.0.1|间接依赖|maven|
|org.openjdk.jol:jol-core|0.16|间接依赖|maven|
|github.com/shirou/gopsutil|v3.20.12+incompatible|间接依赖|go|
|io.netty:netty-codec-redis|4.1.94.Final|间接依赖|maven|
|org.apache.commons:commons-math3|3.4.1|间接依赖|maven|
|commons-codec:commons-codec|1.11|间接依赖|maven|
|golang.org/x/sync|v0.0.0-20210220032951-036812b2e83c|间接依赖|go|
|org.apache.avro:avro|1.7.4|间接依赖|maven|
|com.google.guava:guava|19.0|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-resourcemanager|3.1.0|间接依赖|maven|
|net.sf.jopt-simple:jopt-simple|5.0.2|间接依赖|maven|
|freezegun|0.3.12|间接依赖|pip|
|github.com/mattn/go-isatty|v0.0.12|间接依赖|go|
|commons-collections:commons-collections|3.2.2|直接依赖|maven|
|github.com/elastic/go-concert|v0.2.0|间接依赖|go|
|org.apache.logging.log4j:log4j-slf4j-impl|2.6.2|间接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-otlp-http-trace|1.14.0|间接依赖|maven|
|org.eclipse.jetty:jetty-servlets|9.4.38.v20210224|间接依赖|maven|
|golang.org/x/oauth2|v0.0.0-20211005180243-6b3c2da341f1|间接依赖|go|
|org.apache.hadoop:hadoop-client|2.6.5|间接依赖|maven|
|junit:junit|4.12|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.27|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.10.5.1|间接依赖|maven|
|org.apache.flink:flink-annotations|1.12.2|间接依赖|maven|
|com.aliyun.datalake:metastore-client-hive3|0.2.14|直接依赖|maven|
|core-util-is|1.0.2|间接依赖|npm|
|org.apache.hbase:hbase-metrics|2.4.9|间接依赖|maven|
|org.apache.parquet:parquet-format|2.4.0|间接依赖|maven|
|org.slf4j:slf4j-reload4j|1.7.36|间接依赖|maven|
|com.typesafe.netty:netty-reactive-streams-http|2.0.4|间接依赖|maven|
|org.codehaus.plexus:plexus-compiler-api|2.11.1|间接依赖|maven|
|org.sonatype.aether:aether-impl|1.7|间接依赖|maven|
|io.debezium:debezium-api|1.5.4.Final|间接依赖|maven|
|inherits|2.0.4|间接依赖|npm|
|com.fasterxml.jackson.core:jackson-annotations|2.12.1|间接依赖|maven|
|org.eclipse.jetty:jetty-io|9.3.20.v20170531|间接依赖|maven|
|com.alibaba:fastjson|1.2.83|直接依赖|maven|
|commons-httpclient:commons-httpclient|3.0.1|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.4.14|间接依赖|maven|
|jakarta.websocket:jakarta.websocket-api|1.1.2|间接依赖|maven|
|xerces:xercesImpl|2.12.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.7.3|间接依赖|maven|
|org.codehaus.plexus:plexus-utils|3.2.1|间接依赖|maven|
|org.apache.kerby:kerby-pkix|2.0.3|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.76|间接依赖|maven|
|org.apache.flink:flink-optimizer_2.11|1.12.2|间接依赖|maven|
|net.jcip:jcip-annotations|1.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.6.2|间接依赖|maven|
|golang.org/x/xerrors|v0.0.0-20200804184101-5ec99f83aff1|间接依赖|go|
|org.apache.doris:flink-doris-connector-1.15|1.2.1|直接依赖|maven|
|org.apache.hive:hive-llap-client|2.3.5|间接依赖|maven|
|org.apache.logging.log4j:log4j-1.2-api|2.17.1|间接依赖|maven|
|org.apache.calcite.avatica:avatica-core|1.17.0|间接依赖|maven|
|org.apache.avro:avro-mapred|1.10.2|间接依赖|maven|
|org.elasticsearch:elasticsearch|7.17.10|间接依赖|maven|
|io.fabric8:kubernetes-model-common|5.12.2|间接依赖|maven|
|org.apache.flink:flink-metrics-core|1.12.2|间接依赖|maven|
|org.glassfish.jersey.core:jersey-server|2.35|间接依赖|maven|
|org.apache.lucene:lucene-spatial|8.3.0|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|2.8.3|间接依赖|maven|
|org.apache.flink:force-shading|1.12.2|间接依赖|maven|
|org.apache.hbase:hbase-hadoop2-compat|2.4.9|间接依赖|maven|
|org.apache.hadoop:hadoop-auth|2.6.0|间接依赖|maven|
|com.googlecode.json-simple:json-simple|1.1.1|直接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.4.33.v20201020|间接依赖|maven|
|org.antlr:antlr4-runtime|4.7.2|间接依赖|maven|
|com.qcloud.cos:hadoop-cos|2.8.5-8.1.8|直接依赖|maven|
|com.google.api-client:google-api-client-jackson2|2.0.1|间接依赖|maven|
|org.glassfish.web:javax.servlet.jsp|2.3.2|间接依赖|maven|
|org.apache.hudi:hudi-spark3.2.x_2.12|0.13.1|直接依赖|maven|
|com.oracle.ojdbc:ucp|19.3.0.0|间接依赖|maven|
|go.elastic.co/apm|v1.11.0|间接依赖|go|
|org.eclipse.jetty:jetty-util-ajax|9.4.38.v20210224|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.16|间接依赖|maven|
|org.apache.flink:flink-connector-elasticsearch7_2.12|1.12.2|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|2.6.5|间接依赖|maven|
|org.apache.hive:hive-upgrade-acid|3.1.3|间接依赖|maven|
|com.amazonaws:aws-java-sdk-glue|1.12.519|直接依赖|maven|
|org.apache.commons:commons-pool2|2.7.0|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|间接依赖|maven|
|io.fabric8:kubernetes-model-storageclass|5.12.2|间接依赖|maven|
|io.fabric8:kubernetes-model-networking|5.12.2|间接依赖|maven|
|com.microsoft.sqlserver:mssql-jdbc|6.2.1.jre7|间接依赖|maven|
|com.google.apis:google-api-services-iamcredentials|v1-rev20211203-2.0.0|间接依赖|maven|
|com.github.javaparser:javaparser-core|3.17.0|间接依赖|maven|
|org.apache.avro:avro|1.8.2|间接依赖|maven|
|org.apache.kerby:kerb-client|2.0.3|间接依赖|maven|
|org.glassfish.jersey.inject:jersey-hk2|2.35|间接依赖|maven|
|com.google.flatbuffers:flatbuffers-java|1.12.0|间接依赖|maven|
|io.fabric8:kubernetes-model-extensions|6.7.2|间接依赖|maven|
|cglib:cglib|2.2|直接依赖|maven|
|org.codehaus.jackson:jackson-xc|1.9.2|间接依赖|maven|
|google.golang.org/protobuf|v1.27.1|间接依赖|go|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.5|间接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.69|间接依赖|maven|
|org.bouncycastle:bcutil-jdk15on|1.69|间接依赖|maven|
|org.codehaus.groovy:groovy-sql|3.0.7|间接依赖|maven|
|software.amazon.ion:ion-java|1.0.2|间接依赖|maven|
|org.springframework:spring-jcl|5.0.5.RELEASE|间接依赖|maven|
|io.fabric8:kubernetes-model-apps|6.7.2|间接依赖|maven|
|org.eclipse.jetty:jetty-plus|9.4.48.v20220622|间接依赖|maven|
|org.jamon:jamon-runtime|2.4.1|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-client|2.6.5|间接依赖|maven|
|org.awaitility:awaitility|4.0.3|直接依赖|maven|
|org.apache.spark:spark-catalyst_2.11|2.3.4|间接依赖|maven|
|org.ow2.asm:asm-analysis|9.3|间接依赖|maven|
|org.apache.kerby:token-provider|1.0.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.2.0.RELEASE|间接依赖|maven|
|com.aliyun.odps:odps-sdk-commons|0.43.3-public|间接依赖|maven|
|org.apache.flink:flink-rpc-akka-loader|1.15.3|间接依赖|maven|
|org.apache.kerby:kerby-util|2.0.3|间接依赖|maven|
|io.netty:netty-codec-xml|4.1.94.Final|间接依赖|maven|
|org.jruby.joni:joni|2.1.31|间接依赖|maven|
|org.springframework.boot:spring-boot|2.2.0.RELEASE|间接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-zipkin|1.26.0|直接依赖|maven|
|org.reflections:reflections|0.9.10|间接依赖|maven|
|org.slf4j:slf4j-api|1.6.4|直接依赖|maven|
|io.opentelemetry:opentelemetry-semconv|1.14.0-alpha|间接依赖|maven|
|com.github.spullara.mustache.java:compiler|0.9.6|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.3|间接依赖|maven|
|com.github.stephenc.findbugs:findbugs-annotations|1.3.9-1|间接依赖|maven|
|com.google.crypto.tink:tink|1.6.0|间接依赖|maven|
|github.com/godbus/dbus|v0.0.0-20190422162347-ade71ed3457e|间接依赖|go|
|org.apache.hadoop:hadoop-mapreduce-client-jobclient|2.8.3|间接依赖|maven|
|com.huaweicloud:esdk-obs-java-bundle|3.21.8|直接依赖|maven|
|mysql|2.18.1|直接依赖|npm|
|org.apache.thrift:libthrift|0.13.0|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.94.Final|间接依赖|maven|
|org.apache.spark:spark-sketch_2.11|2.3.4|间接依赖|maven|
|org.apache.hive.shims:hive-shims-scheduler|2.3.5|间接依赖|maven|
|org.antlr:ST4|4.0.4|间接依赖|maven|
|com.vlkan:flatbuffers|1.2.0-3f79e055|间接依赖|maven|
|javolution:javolution|5.5.1|间接依赖|maven|
|io.netty:netty-codec-memcache|4.1.94.Final|间接依赖|maven|
|software.amazon.awssdk:arns|2.15.45|间接依赖|maven|
|org.scala-lang.modules:scala-xml_2.12|1.0.6|间接依赖|maven|
|org.springframework:spring-beans|5.0.5.RELEASE|间接依赖|maven|
|org.apache.maven:maven-model|3.0|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.11.4|间接依赖|maven|
|org.springframework:spring-webmvc|5.2.0.RELEASE|间接依赖|maven|
|org.apache.calcite:calcite-druid|1.10.0|间接依赖|maven|
|com.sun.xml.bind:jaxb-impl|2.2.3-1|间接依赖|maven|
|net.razorvine:pyrolite|4.30|间接依赖|maven|
|org.eclipse.jetty:jetty-http|9.3.20.v20170531|间接依赖|maven|
|software.amazon.awssdk:aws-xml-protocol|2.15.45|间接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5-h2|5.1.5|间接依赖|maven|
|org.apache.parquet:parquet-encoding|1.8.3|间接依赖|maven|
|com.yahoo.datasketches:memory|0.9.0|间接依赖|maven|
|org.apache.kafka:kafka-tools|2.7.0|间接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|io.grpc:grpc-api|1.30.0|间接依赖|maven|
|org.apache.lucene:lucene-suggest|8.4.0|间接依赖|maven|
|org.apache.arrow:arrow-memory-netty|5.0.0|直接依赖|maven|
|org.apache.hive.shims:hive-shims-common|2.3.5|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-applicationhistoryservice|2.7.2|间接依赖|maven|
|org.codehaus.groovy:groovy-jsr223|3.0.7|间接依赖|maven|
|org.mybatis:mybatis-spring|1.3.2|间接依赖|maven|
|io.fabric8:kubernetes-model-autoscaling|6.7.2|间接依赖|maven|
|org.apache.yetus:audience-annotations|0.13.0|间接依赖|maven|
|org.apache.hudi:hudi-timeline-service|0.13.1|间接依赖|maven|
|org.apache.hadoop:hadoop-auth|3.3.6|直接依赖|maven|
|software.amazon.awssdk:aws-core|2.17.257|间接依赖|maven|
|org.apache.commons:commons-lang3|3.9|直接依赖|maven|
|org.eclipse.jetty:jetty-client|9.4.33.v20201020|间接依赖|maven|
|org.apache.doris:hive-catalog-shade|1.0.1|直接依赖|maven|
|github.com/hashicorp/golang-lru|v0.5.4|间接依赖|go|
|com.google.protobuf:protobuf-java|2.5.0|直接依赖|maven|
|com.google.code.gson:gson|2.2.4|间接依赖|maven|
|com.lmax:disruptor|3.4.4|间接依赖|maven|
|org.apache.maven.wagon:wagon-provider-api|2.10|间接依赖|maven|
|org.springframework:spring-tx|5.2.0.RELEASE|间接依赖|maven|
|golang.org/x/text|v0.3.7|间接依赖|go|
|org.apache.curator:curator-recipes|2.12.0|间接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.4.51.v20230217|间接依赖|maven|
|org.scala-lang.modules:scala-java8-compat_2.12|0.8.0|间接依赖|maven|
|tomcat:jasper-compiler|5.5.23|间接依赖|maven|
|org.springframework.boot:spring-boot|2.7.3|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-app|2.8.3|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-registry|3.1.0|间接依赖|maven|
|io.fabric8:kubernetes-httpclient-okhttp|6.7.2|间接依赖|maven|
|com.alibaba.datax:datax-common||直接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.7.3|间接依赖|maven|
|org.apache.kerby:kerb-identity|1.0.1|间接依赖|maven|
|commons-codec:commons-codec|1.13|直接依赖|maven|
|org.elasticsearch:elasticsearch-cli|7.5.1|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.12.1|间接依赖|maven|
|org.codehaus.groovy:groovy-jmx|3.0.7|间接依赖|maven|
|golang.org/x/crypto|v0.0.0-20210616213533-5ff15b29337e|间接依赖|go|
|org.elasticsearch.plugin:mapper-extras-client|7.5.1|间接依赖|maven|
|org.apache.directory.server:apacheds-kerberos-codec|2.0.0-M15|间接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.4.48.v20220622|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|2.10.2|直接依赖|maven|
|github.com/urso/go-bin|v0.0.0-20180220135811-781c575c9f0e|间接依赖|go|
|github.com/elastic/go-seccomp-bpf|v1.2.0|间接依赖|go|
|com.twitter:chill_2.12|0.9.3|间接依赖|maven|
|org.apache.ranger:ranger-plugins-audit|2.4.0|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.5|间接依赖|maven|
|org.elasticsearch.plugin:rank-eval-client|7.5.1|间接依赖|maven|
|org.apache.parquet:parquet-column|1.8.3|间接依赖|maven|
|org.apache.spark:spark-core_2.12|2.4.6|间接依赖|maven|
|org.apache.lucene:lucene-queries|8.4.0|间接依赖|maven|
|org.springframework:spring-orm|5.3.28|间接依赖|maven|
|commons-digester:commons-digester|2.1|间接依赖|maven|
|org.apache.hadoop.thirdparty:hadoop-shaded-protobuf_3_7|1.1.1|间接依赖|maven|
|org.mortbay.jetty:jetty|6.1.26|间接依赖|maven|
|org.eclipse.jetty:jetty-xml|9.4.48.v20220622|间接依赖|maven|
|org.glassfish.hk2:hk2-utils|2.6.1|间接依赖|maven|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.33.v20201020|间接依赖|maven|
|org.eclipse.jetty:jetty-security|9.4.48.v20220622|间接依赖|maven|
|commons-validator:commons-validator|1.7|直接依赖|maven|
|org.apache.flink:flink-table-runtime-blink_2.12|1.12.2|间接依赖|maven|
|io.javalin:javalin|4.6.7|间接依赖|maven|
|org.springframework:spring-beans|5.2.0.RELEASE|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.5|间接依赖|maven|
|io.netty:netty-all|4.0.23.Final|间接依赖|maven|
|org.apache.paimon:paimon-shade-jackson-2|2.14.2-0.4.0-incubating|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-jobclient|2.6.5|间接依赖|maven|
|com.google.auth:google-auth-library-credentials|1.12.1|间接依赖|maven|
|org.apache.calcite.avatica:avatica|1.8.0|间接依赖|maven|
|org.apache.commons:commons-pool2|2.2|直接依赖|maven|
|com.twitter:chill_2.11|0.7.6|间接依赖|maven|
|org.apache.kerby:token-provider|2.0.3|间接依赖|maven|
|org.apache.spark:spark-kvstore_2.12|3.2.0|间接依赖|maven|
|org.apache.spark:spark-catalyst_2.12|3.2.0|直接依赖|maven|
|org.apache.parquet:parquet-avro|1.13.1|直接依赖|maven|
|org.apache.flink:flink-table-api-java-bridge|1.15.3|间接依赖|maven|
|org.apache.flink:flink-scala_2.12|1.15.3|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-core|4.5.10|间接依赖|maven|
|org.apache.hbase.thirdparty:hbase-shaded-jetty|3.5.1|间接依赖|maven|
|org.apache.hudi:hudi-spark3-common|0.13.1|直接依赖|maven|
|software.amazon.awssdk:http-client-spi|2.17.257|间接依赖|maven|
|com.typesafe.akka:akka-slf4j_2.12|2.5.21|间接依赖|maven|
|net.sourceforge.czt.dev:java-cup-runtime|0.11-a-czt01-cdh|间接依赖|maven|
|org.codehaus.jackson:jackson-jaxrs|1.8.3|间接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.17.1|间接依赖|maven|
|org.apache.doris:fe-common|1.2-SNAPSHOT|直接依赖|maven|
|org.apache.flink:flink-table-common|1.15.3|间接依赖|maven|
|org.apache.flink:flink-table-planner_2.12|1.15.3|直接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-core|3.3.6|间接依赖|maven|
|org.apache.curator:curator-framework|2.13.0|间接依赖|maven|
|com.google.oauth-client:google-oauth-client|1.34.1|间接依赖|maven|
|io.zipkin.reporter2:zipkin-reporter|2.16.3|间接依赖|maven|
|org.glassfish.hk2.external:aopalliance-repackaged|2.4.0-b34|间接依赖|maven|
|com.sun.activation:javax.activation|1.2.0|直接依赖|maven|
|org.jboss.xnio:xnio-api|3.6.5.Final|间接依赖|maven|
|io.delta:delta-storage|3.0.0rc1|间接依赖|maven|
|org.elasticsearch.plugin:aggs-matrix-stats-client|7.10.2|间接依赖|maven|
|stax:stax-api|1.0.1|间接依赖|maven|
|org.rocksdb:rocksdbjni|5.17.2|间接依赖|maven|
|com.typesafe.akka:akka-stream_2.12|2.5.21|间接依赖|maven|
|org.codehaus.groovy:groovy-nio|3.0.7|间接依赖|maven|
|io.debezium:debezium-ddl-parser|1.6.4.Final|间接依赖|maven|
|org.apache.hbase.thirdparty:hbase-shaded-miscellaneous|3.5.1|间接依赖|maven|
|github.com/urso/magetools|v0.0.0-20190919040553-290c89e0c230|间接依赖|go|
|org.eclipse.jetty:jetty-security|9.4.33.v20201020|间接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|7.9|间接依赖|maven|
|org.apache.maven:maven-aether-provider|3.0|间接依赖|maven|
|org.apache.flink:flink-table-api-bridge-base|1.15.3|间接依赖|maven|
|com.github.luben:zstd-jni|1.4.3-1|间接依赖|maven|
|org.scala-lang:scala-library|2.12.7|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.10.5|间接依赖|maven|
|org.apache.hive:hive-serde|2.3.5|间接依赖|maven|
|org.checkerframework:checker|3.22.2|间接依赖|maven|
|org.apache.httpcomponents:fluent-hc|4.4.1|间接依赖|maven|
|commons-httpclient:commons-httpclient|3.1|间接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|3.1.0|间接依赖|maven|
|org.roaringbitmap:RoaringBitmap|0.8.13|直接依赖|maven|
|org.apache.hudi:hudi-spark-client|0.13.1|直接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-core|2.8.0|直接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-autoconfigure|1.3.2|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-ram|3.1.0|间接依赖|maven|
|org.javassist:javassist|3.18.1-GA|间接依赖|maven|
|org.jboss.threads:jboss-threads|2.3.6.Final|间接依赖|maven|
|org.scala-lang:scala-reflect|2.12.7|间接依赖|maven|
|io.sgr:s2-geometry-library-java|1.0.0|间接依赖|maven|
|org.apache.hive.shims:hive-shims-scheduler|3.1.3|间接依赖|maven|
|k8s.io/client-go|v0.21.1|间接依赖|go|
|org.apache.doris:je|18.3.13-doris-SNAPSHOT|间接依赖|maven|
|org.apache.kafka:kafka-clients|3.4.0|直接依赖|maven|
|software.amazon.awssdk:annotations|2.15.45|间接依赖|maven|
|io.netty:netty-buffer|4.1.48.Final|间接依赖|maven|
|org.apache.paimon:paimon-common|0.4.0-incubating|直接依赖|maven|
|com.google.http-client:google-http-client-jackson2|1.42.3|间接依赖|maven|
|io.netty:netty-codec|4.1.94.Final|间接依赖|maven|
|org.apache.spark:spark-core_2.12|3.2.0|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.12|直接依赖|maven|
|org.apache.hadoop:hadoop-hdfs|2.8.0|直接依赖|maven|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|io.netty:netty-codec-smtp|4.1.94.Final|间接依赖|maven|
|org.apache.curator:curator-recipes|2.6.0|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.0.17.Final|间接依赖|maven|
|org.springframework:springloaded|1.2.6.RELEASE|间接依赖|maven|
|io.fabric8:kubernetes-model-batch|6.7.2|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.15.2|直接依赖|maven|
|com.sun.jersey:jersey-client|1.9|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.10.1|直接依赖|maven|
|org.eclipse.jetty:jetty-server|9.4.38.v20210224|间接依赖|maven|
|github.com/magefile/mage|v1.11.0|间接依赖|go|
|org.codehaus.plexus:plexus-java|1.1.1|间接依赖|maven|
|org.apache.hbase:hbase-asyncfs|2.4.9|间接依赖|maven|
|org.awaitility:awaitility|4.0.1|间接依赖|maven|
|sigs.k8s.io/structured-merge-diff/v4|v4.1.0|间接依赖|go|
|org.apache.maven.shared:maven-shared-utils|3.1.0|间接依赖|maven|
|org.apache.hbase:hbase-replication|2.4.9|间接依赖|maven|
|github.com/fsnotify/fsevents|v0.1.1|间接依赖|go|
|readable-stream|2.3.7|间接依赖|npm|
|org.apache.hadoop:hadoop-auth|2.8.3|间接依赖|maven|
|org.codehaus.plexus:plexus-archiver|4.2.1|间接依赖|maven|
|org.apache.hive:hive-storage-api|2.7.0|间接依赖|maven|
|org.eclipse.jetty:jetty-client|9.4.48.v20220622|间接依赖|maven|
|org.apache.flink:flink-shaded-jackson|2.10.1-12.0|间接依赖|maven|
|com.squareup.okhttp3:okhttp|4.9.3|直接依赖|maven|
|io.fabric8:kubernetes-model-events|6.7.2|间接依赖|maven|
|org.apache.lucene:lucene-backward-codecs|8.3.0|间接依赖|maven|
|org.apache.paimon:paimon-bundle|0.4.0-incubating|直接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet|2.31|间接依赖|maven|
|org.apache.spark:spark-unsafe_2.12|2.4.6|间接依赖|maven|
|org.apache.arrow:arrow-format|9.0.0|间接依赖|maven|
|org.apache.hudi:hudi-sync-common|0.13.1|间接依赖|maven|
|io.dropwizard.metrics:metrics-json|4.2.19|间接依赖|maven|
|org.eclipse.jetty:jetty-util-ajax|9.4.51.v20230217|间接依赖|maven|
|org.apache.commons:commons-compress|1.19|间接依赖|maven|
|org.sonatype.aether:aether-spi|1.7|间接依赖|maven|
|org.apache.hbase:hbase-procedure|2.4.9|间接依赖|maven|
|org.apache.maven.shared:maven-common-artifact-filters|3.1.0|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.3.Final|间接依赖|maven|
|org.apache.iceberg:iceberg-common|1.1.0|间接依赖|maven|
|org.apache.hadoop:hadoop-common|2.6.5|间接依赖|maven|
|org.apache.calcite.avatica:avatica-metrics|1.8.0|间接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-client|7.17.10|间接依赖|maven|
|org.apache.directory.api:api-asn1-api|1.0.0-M20|间接依赖|maven|
|org.apache.hive:hive-storage-api|2.6.0|间接依赖|maven|
|org.apache.calcite:calcite-linq4j|1.16.0|间接依赖|maven|
|org.apache.parquet:parquet-column|1.13.1|直接依赖|maven|
|org.lz4:lz4-java|1.4.0|间接依赖|maven|
|org.glassfish.jersey.core:jersey-client|2.35|间接依赖|maven|
|io.fabric8:kubernetes-model-flowcontrol|5.12.2|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|间接依赖|maven|
|org.apache.iceberg:iceberg-core|1.1.0|直接依赖|maven|
|org.apache.lucene:lucene-queryparser|8.4.0|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.7.8|间接依赖|maven|
|org.apache.lucene:lucene-backward-codecs|8.4.0|间接依赖|maven|
|org.javassist:javassist|3.19.0-GA|间接依赖|maven|
|org.apache.kerby:kerb-util|2.0.3|间接依赖|maven|
|org.apache.yetus:audience-annotations|0.5.0|间接依赖|maven|
|org.scala-lang.modules:scala-xml_2.12|1.2.0|间接依赖|maven|
|org.threeten:threeten-extra|1.7.1|间接依赖|maven|
|io.fabric8:kubernetes-model-rbac|6.7.2|间接依赖|maven|
|org.apache.hadoop:hadoop-aws|3.3.6|直接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.3.20.v20170531|间接依赖|maven|
|org.apache.maven.plugins:maven-assembly-plugin|3.3.0|直接依赖|maven|
|github.com/jcmturner/rpc/v2|v2.0.3|间接依赖|go|
|org.apache.arrow:arrow-format|2.0.0|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.94.Final|间接依赖|maven|
|org.codehaus.groovy:groovy-test|3.0.7|间接依赖|maven|
|org.locationtech.proj4j:proj4j|1.1.5|间接依赖|maven|
|com.ibm.icu:icu4j|71.1|间接依赖|maven|
|org.codehaus.groovy:groovy-console|3.0.7|间接依赖|maven|
|org.codehaus.janino:commons-compiler|3.0.11|间接依赖|maven|
|com.squareup.okio:okio|1.4.0|间接依赖|maven|
|google.golang.org/genproto|v0.0.0-20211021150943-2b146023228c|间接依赖|go|
|org.junit.platform:junit-platform-commons|1.8.2|间接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|5.0.3|间接依赖|maven|
|io.fabric8:kubernetes-model-metrics|6.7.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.7.3|间接依赖|maven|
|io.prometheus:simpleclient_common|0.15.0|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.9.3|间接依赖|maven|
|com.amazonaws:aws-java-sdk-bundle|1.12.519|间接依赖|maven|
|com.oracle.database.ha:ons|21.5.0.0|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.16|间接依赖|maven|
|org.glassfish.hk2:hk2-utils|2.4.0-b34|间接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|6.5.1|间接依赖|maven|
|org.codehaus.janino:commons-compiler|3.0.8|间接依赖|maven|
|org.apache.maven.shared:maven-artifact-transfer|0.11.0|间接依赖|maven|
|github.com/inconshreveable/mousetrap|v1.0.0|间接依赖|go|
|github.com/xdg/stringprep|v1.0.3|间接依赖|go|
|software.amazon.awssdk:metrics-spi|2.15.45|间接依赖|maven|
|string_decoder|1.1.1|间接依赖|npm|
|org.quartz-scheduler:quartz|2.3.2|直接依赖|maven|
|org.glassfish.jersey.media:jersey-media-jaxb|2.22.2|间接依赖|maven|
|org.locationtech.jts:jts-core|1.19.0|间接依赖|maven|
|github.com/samuel/go-thrift|v0.0.0-20140522043831-2187045faa54|间接依赖|go|
|io.netty:netty-buffer|4.1.53.Final|间接依赖|maven|
|org.eclipse.jetty:jetty-webapp|9.4.48.v20220622|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.3|直接依赖|maven|
|stax:stax|1.2.0|间接依赖|maven|
|org.elasticsearch.plugin:aggs-matrix-stats-client|7.5.1|间接依赖|maven|
|org.apache.arrow:arrow-vector|5.0.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.10.5|间接依赖|maven|
|org.wildfly.common:wildfly-common|1.3.0.Final|间接依赖|maven|
|org.apache.orc:orc-core|1.3.4|间接依赖|maven|
|org.checkerframework:checker-qual|3.33.0|间接依赖|maven|
|org.apache.avro:avro|1.7.7|间接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.16|间接依赖|maven|
|com.github.davidmoten:hilbert-curve|0.2.2|间接依赖|maven|
|org.apache.hudi:hudi-spark-common_2.11|0.13.1|间接依赖|maven|
|hu.webarticum:tree-printer|1.2|直接依赖|maven|
|org.eclipse.jetty:jetty-server|9.4.51.v20230217|间接依赖|maven|
|org.springframework.ldap:spring-ldap-core|2.4.1|间接依赖|maven|
|org.reflections:reflections|0.9.12|间接依赖|maven|
|com.twitter:chill_2.12|0.7.6|间接依赖|maven|
|com.typesafe.akka:akka-protobuf_2.11|2.5.21|间接依赖|maven|
|org.apache.doris:spark-dpp|1.2-SNAPSHOT|间接依赖|maven|
|org.apache.lucene:lucene-memory|8.3.0|间接依赖|maven|
|software.amazon.awssdk:regions|2.15.45|间接依赖|maven|
|javax.xml.ws:jaxws-api|2.3.0|直接依赖|maven|
|com.zaxxer:HikariCP|3.4.1|间接依赖|maven|
|org.mortbay.jetty:jetty-util|6.1.14|间接依赖|maven|
|org.mortbay.jetty:jetty|6.1.14|间接依赖|maven|
|org.springframework:spring-context-support|5.2.0.RELEASE|直接依赖|maven|
|io.fabric8:kubernetes-model-batch|5.12.2|间接依赖|maven|
|org.checkerframework:checker-qual|3.12.0|间接依赖|maven|
|com.yahoo.datasketches:sketches-core|0.9.0|间接依赖|maven|
|org.tukaani:xz|1.0|间接依赖|maven|
|com.ning:compress-lzf|1.0.3|间接依赖|maven|
|com.esri.geometry:esri-geometry-api|2.0.0|间接依赖|maven|
|org.sonatype.plexus:plexus-cipher|1.4|间接依赖|maven|
|org.apache.flink:flink-shaded-jackson|2.12.4-15.0|间接依赖|maven|
|org.apache.lucene:lucene-spatial3d|8.3.0|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.13.5|间接依赖|maven|
|org.codehaus.groovy:groovy-all|3.0.7|直接依赖|maven|
|commons-cli:commons-cli|1.2|间接依赖|maven|
|org.apache.hbase:hbase-http|2.4.9|间接依赖|maven|
|github.com/go-sql-driver/mysql|v1.5.0|直接依赖|go|
|org.apache.hive:hive-storage-api|2.4.0|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.1|间接依赖|maven|
|org.eclipse.jetty:jetty-annotations|9.4.48.v20220622|间接依赖|maven|
|com.google.code.gson:gson|2.8.9|直接依赖|maven|
|com.aliyun.datalake:metastore-client-hive-common|0.2.14|间接依赖|maven|
|github.com/docker/go-connections|v0.4.0|间接依赖|go|
|org.apache.lucene:lucene-spatial|8.4.0|间接依赖|maven|
|org.eclipse.jetty:jetty-security|9.4.51.v20230217|间接依赖|maven|
|org.apache.kerby:kerby-config|1.0.1|间接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5|5.1.3|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|mysql:mysql-connector-java|8.0.12|直接依赖|maven|
|com.aliyun.datalake:shims-common|0.2.14|间接依赖|maven|
|org.apache.hive:hive-llap-common|2.3.5|间接依赖|maven|
|software.amazon.awssdk:utils|2.15.45|间接依赖|maven|
|com.qcloud:cos_api-bundle|5.6.100|间接依赖|maven|
|org.json4s:json4s-ast_2.11|3.2.11|间接依赖|maven|
|org.apache.spark:spark-core_2.11|2.3.4|直接依赖|maven|
|io.fabric8:kubernetes-model-policy|5.12.2|间接依赖|maven|
|com.amazonaws:jmespath-java|1.11.95|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.10.0|间接依赖|maven|
|github.com/matttproud/golang_protobuf_extensions|v1.0.2-0.20181231171920-c182affec369|间接依赖|go|
|org.mybatis:mybatis|3.4.6|间接依赖|maven|
|org.ehcache:ehcache|3.3.1|间接依赖|maven|
|io.dropwizard.metrics:metrics-jvm|3.1.5|间接依赖|maven|
|org.junit.platform:junit-platform-launcher|1.7.0|间接依赖|maven|
|org.apache.hive:hive-service-rpc|2.3.5|间接依赖|maven|
|com.beust:jcommander|1.78|间接依赖|maven|
|org.apache.flink:flink-java|1.15.3|间接依赖|maven|
|org.tukaani:xz|1.8|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.0-4|间接依赖|maven|
|software.amazon.awssdk:s3|2.15.45|间接依赖|maven|
|com.oracle.ojdbc:osdt_cert|19.3.0.0|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-resourcemanager|2.7.2|间接依赖|maven|
|org.apache.commons:commons-compress|1.21|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-shuffle|2.8.3|间接依赖|maven|
|org.apache.hadoop:hadoop-auth|3.1.0|间接依赖|maven|
|com.amazonaws:aws-java-sdk-bundle|1.11.271|间接依赖|maven|
|org.eclipse.jetty.websocket:javax-websocket-client-impl|9.4.51.v20230217|间接依赖|maven|
|org.springframework:spring-jdbc|5.3.28|间接依赖|maven|
|org.apache.calcite.avatica:avatica|1.22.0|间接依赖|maven|
|org.eclipse.jetty:jetty-server|9.4.48.v20220622|间接依赖|maven|
|org.apache.parquet:parquet-encoding|1.13.1|间接依赖|maven|
|com.google.guava:guava|31.0.1-jre|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.3.70|间接依赖|maven|
|software.amazon.awssdk:annotations|2.17.257|间接依赖|maven|
|org.apache.logging.log4j:log4j-web|2.6.2|间接依赖|maven|
|com.esotericsoftware:minlog|1.3.0|间接依赖|maven|
|mysql:mysql-connector-java||直接依赖|maven|
|org.glassfish.hk2:hk2-api|2.6.1|间接依赖|maven|
|io.fabric8:kubernetes-model-gatewayapi|6.7.2|间接依赖|maven|
|org.elasticsearch:elasticsearch-geo|7.17.10|间接依赖|maven|
|org.sonatype.sisu:sisu-guice|2.1.7|间接依赖|maven|
|oro:oro|2.0.8|间接依赖|maven|
|org.springframework:spring-context|5.0.5.RELEASE|间接依赖|maven|
|github.com/insomniacslk/dhcp|v0.0.0-20180716145214-633285ba52b2|间接依赖|go|
|org.codehaus.groovy:groovy-ant|3.0.7|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|3.3.6|间接依赖|maven|
|org.apache.flink:flink-hadoop-compatibility_2.11|1.12.2|直接依赖|maven|
|org.apache.arrow:arrow-format|0.8.0|间接依赖|maven|
|io.opencensus:opencensus-api|0.31.1|间接依赖|maven|
|go.elastic.co/apm/module/apmhttp|v1.7.2|间接依赖|go|
|org.codehaus.janino:commons-compiler|3.1.8|间接依赖|maven|
|org.apache.commons:commons-compress|1.8.1|间接依赖|maven|
|github.com/spf13/cobra|v1.0.0|间接依赖|go|
|org.codehaus.janino:janino|3.0.11|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|3.3.6|间接依赖|maven|
|github.com/spf13/cast|v1.5.0|直接依赖|go|
|github.com/klauspost/compress|v1.13.6|间接依赖|go|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.8.11|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|3.1.0|间接依赖|maven|
|org.apache.flink:flink-streaming-java_2.11|1.12.2|间接依赖|maven|
|io.netty:netty-common|4.1.53.Final|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-api|9.4.51.v20230217|间接依赖|maven|
|com.sun.jersey:jersey-bundle|1.19.3|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.10|直接依赖|maven|
|net.minidev:json-smart|1.1.1|间接依赖|maven|
|com.squareup.okhttp3:okhttp-ws|3.4.2|间接依赖|maven|
|com.github.jsqlparser:jsqlparser|2.1|间接依赖|maven|
|org.apache.doris:flink-doris-connector-1.14_2.12|1.0.3|直接依赖|maven|
|org.awaitility:awaitility|4.2.0|直接依赖|maven|
|org.apache.flink:flink-table-api-java-bridge_2.12|1.12.2|间接依赖|maven|
|tomcat:jasper-runtime|5.5.23|间接依赖|maven|
|org.apache.flink:flink-optimizer|1.15.3|间接依赖|maven|
|com.101tec:zkclient|0.10|间接依赖|maven|
|mysql:mysql-connector-java|8.0.28|直接依赖|maven|
|software.amazon.awssdk:utils|2.17.257|间接依赖|maven|
|org.apache.flink:flink-table-api-java|1.12.2|间接依赖|maven|
|commons-net:commons-net|3.1|间接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.3|间接依赖|maven|
|org.apache.kerby:kerb-server|2.0.3|间接依赖|maven|
|org.apache.commons:commons-math3|3.5|间接依赖|maven|
|commons-beanutils:commons-beanutils-core|1.8.0|间接依赖|maven|
|com.ververica:flink-connector-debezium|2.1.1|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.1|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|2.8.3|间接依赖|maven|
|honnef.co/go/tools|v0.0.1-2020.1.4|间接依赖|go|
|org.codehaus.plexus:plexus-compiler-javac|2.11.1|间接依赖|maven|
|org.eclipse.jetty:jetty-util-ajax|9.4.48.v20220622|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.4|间接依赖|maven|
|org.yaml:snakeyaml|1.33|直接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.94.Final|间接依赖|maven|
|org.codehaus.groovy:groovy-macro|3.0.7|间接依赖|maven|
|org.locationtech.jts.io:jts-io-common|1.19.0|间接依赖|maven|
|com.amazonaws:aws-java-sdk-s3|1.12.519|直接依赖|maven|
|org.apache.hadoop:hadoop-distcp|2.10.0|间接依赖|maven|
|com.huaweicloud:hadoop-huaweicloud|3.1.1-hw-46|直接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|org.apache.flink:flink-java|1.12.2|间接依赖|maven|
|com.amazonaws:aws-java-sdk-s3|1.11.95|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet-core|2.22.2|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.0.4.1|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.3.19.v20170502|间接依赖|maven|
|com.amazonaws:aws-java-sdk-core|1.12.519|间接依赖|maven|
|io.netty:netty-buffer|4.1.94.Final|间接依赖|maven|
|io.grpc:grpc-netty-shaded|1.30.0|直接依赖|maven|
|github.com/samuel/go-parser|v0.0.0-20130731160455-ca8abbf65d0e|间接依赖|go|
|com.twitter:chill-java|0.10.0|间接依赖|maven|
|org.apache.ivy:ivy|2.5.0|间接依赖|maven|
|com.google.auto.value:auto-value-annotations|1.10.1|间接依赖|maven|
|io.netty:netty-transport-udt|4.1.94.Final|间接依赖|maven|
|org.apache.hadoop:hadoop-auth|2.8.0|间接依赖|maven|
|org.apache.kerby:kerb-simplekdc|2.0.3|间接依赖|maven|
|io.fabric8:kubernetes-model-certificates|6.7.2|间接依赖|maven|
|org.apache.kerby:kerby-pkix|1.0.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.12.0|间接依赖|maven|
|matplotlib|3.7.0|间接依赖|pip|
|com.jayway.jsonpath:json-path|2.7.0|间接依赖|maven|
|org.apache.spark:spark-sql_2.12|3.2.0|直接依赖|maven|
|javax.mail:mail|1.4.1|间接依赖|maven|
|github.com/hashicorp/go-multierror|v1.1.0|间接依赖|go|
|org.json4s:json4s-jackson_2.12|3.5.3|间接依赖|maven|
|org.glassfish.jersey.inject:jersey-hk2|2.31|间接依赖|maven|
|org.apache.geronimo.specs:geronimo-annotation_1.0_spec|1.1.1|间接依赖|maven|
|golang.org/x/tools|v0.1.7|间接依赖|go|
|org.apache.hbase:hbase-client|1.2.3|间接依赖|maven|
|org.apache.flink:flink-metrics-core|1.15.3|间接依赖|maven|
|go.uber.org/multierr|v1.3.0|间接依赖|go|
|io.opentelemetry:opentelemetry-exporter-common|1.26.0|间接依赖|maven|
|org.jboss.threads:jboss-threads|2.3.0.Beta2|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.7.8|间接依赖|maven|
|github.com/coreos/go-systemd/v22|v22.3.2|间接依赖|go|
|org.apache.flink:flink-connector-base|1.12.2|间接依赖|maven|
|net.sf.opencsv:opencsv|2.3|间接依赖|maven|
|com.zaxxer:HikariCP|3.4.5|间接依赖|maven|
|mysql:mysql-connector-java|8.0.15|直接依赖|maven|
|net.sourceforge.czt.dev:java-cup|0.11-a-czt02-cdh|直接依赖|maven|
|org.apache.logging.log4j:log4j-1.2-api|2.6.2|间接依赖|maven|
|io.fabric8:kubernetes-model-scheduling|5.12.2|间接依赖|maven|
|org.apache.spark:spark-kvstore_2.11|2.3.4|间接依赖|maven|
|io.fabric8:kubernetes-model-storageclass|6.7.2|间接依赖|maven|
|org.antlr:ST4|4.3.4|间接依赖|maven|
|github.com/opencontainers/image-spec|v1.0.2-0.20190823105129-775207bd45b6|间接依赖|go|
|xmlenc:xmlenc|0.52|间接依赖|maven|
|google.golang.org/grpc|v1.41.0|间接依赖|go|
|com.thoughtworks.paranamer:paranamer|2.7|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.2|间接依赖|maven|
|com.squareup.okhttp:okhttp|2.7.5|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-engine|5.7.0|间接依赖|maven|
|org.apache.xbean:xbean-asm5-shaded|4.4|间接依赖|maven|
|github.com/docker/go-units|v0.4.0|间接依赖|go|
|io.fabric8:kubernetes-model-node|5.12.2|间接依赖|maven|
|net.razorvine:pyrolite|4.13|间接依赖|maven|
|io.netty:netty-codec-http|4.1.53.Final|间接依赖|maven|
|org.glassfish.hk2.external:aopalliance-repackaged|2.6.1|间接依赖|maven|
|io.grpc:grpc-context|1.55.1|间接依赖|maven|
|net.minidev:json-smart|2.4.7|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-client|3.3.6|间接依赖|maven|
|com.github.mifmif:generex|1.0.1|直接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.94.Final|间接依赖|maven|
|gopkg.in/jcmturner/aescts.v1|v1.0.1|间接依赖|go|
|org.fusesource.leveldbjni:leveldbjni-all|1.8|间接依赖|maven|
|org.apache.hive.shims:hive-shims-0.23|3.1.3|间接依赖|maven|
|org.hibernate:hibernate-validator|5.1.0.Final|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.3.71|间接依赖|maven|
|javax.validation:validation-api|1.1.0.Final|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-validation|2.2.0.RELEASE|间接依赖|maven|
|org.apache.httpcomponents.client5:httpclient5|5.1.3|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.15|直接依赖|maven|
|software.amazon.awssdk:aws-query-protocol|2.15.45|间接依赖|maven|
|org.springframework.boot:spring-boot-devtools|2.7.13|直接依赖|maven|
|org.apache.flink:flink-annotations|1.15.3|间接依赖|maven|
|org.apache.flink:flink-shaded-zookeeper-3|3.4.14-12.0|间接依赖|maven|
|com.jcraft:jsch|0.1.42|间接依赖|maven|
|org.checkerframework:checker|3.32.0|间接依赖|maven|
|org.jboss.xnio:xnio-nio|3.6.5.Final|间接依赖|maven|
|org.apache.arrow:arrow-format|5.0.0|间接依赖|maven|
|org.codehaus.groovy:groovy-xml|3.0.7|间接依赖|maven|
|com.zaxxer:HikariCP-java7|2.4.12|间接依赖|maven|
|org.codehaus.janino:janino|3.1.6|直接依赖|maven|
|org.slf4j:slf4j-log4j12|1.7.10|间接依赖|maven|
|org.eclipse.jetty:jetty-client|9.3.20.v20170531|间接依赖|maven|
|org.apache.maven:maven-artifact|3.6.3|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.2.2|间接依赖|maven|
|org.apache.hudi:hudi-common|0.10.0|间接依赖|maven|
|org.antlr:antlr4-runtime|4.11.1|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-paranamer|2.7.9|间接依赖|maven|
|org.javassist:javassist|3.18.2-GA|直接依赖|maven|
|com.typesafe.akka:akka-actor_2.11|2.5.21|间接依赖|maven|
|org.codehaus.janino:commons-compiler|3.0.16|直接依赖|maven|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/aerospike/aerospike-client-go|v1.27.1-0.20170612174108-0f3b54da6bdc|间接依赖|go|
|org.glassfish.jersey.containers:jersey-container-servlet-core|2.35|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-smile|2.8.11|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|直接依赖|maven|
|org.apache.avro:avro-mapred|1.8.2|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.28|间接依赖|maven|
|org.apache.calcite.avatica:avatica-core|1.22.0|间接依赖|maven|
|github.com/elastic/go-libaudit/v2|v2.2.0|间接依赖|go|
|github.com/elastic/gosigar|v0.14.2|间接依赖|go|
|org.apache.xbean:xbean-asm6-shaded|4.8|间接依赖|maven|
|github.com/StackExchange/wmi|v0.0.0-20170221213301-9f32b5905fd6|间接依赖|go|
|org.apache.hbase:hbase-server|2.4.9|间接依赖|maven|
|org.apache.hbase:hbase-client|2.4.9|间接依赖|maven|
|io.netty:netty-resolver|4.1.17.Final|间接依赖|maven|
|org.apache.paimon:paimon-oss-impl|0.4.0-incubating|直接依赖|maven|
|io.dropwizard.metrics:metrics-core|4.0.2|直接依赖|maven|
|org.apache.curator:apache-curator|2.7.1|间接依赖|maven|
|org.apache.parquet:parquet-avro|1.10.1|直接依赖|maven|
|io.debezium:debezium-ddl-parser|1.5.4.Final|间接依赖|maven|
|org.apache.maven.shared:maven-filtering|3.1.1|间接依赖|maven|
|commons-logging:commons-logging|1.1.3|直接依赖|maven|
|org.apache.flink:flink-hadoop-fs|1.15.3|间接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j-impl|2.18.0|直接依赖|maven|
|org.datanucleus:datanucleus-core|4.1.17|间接依赖|maven|
|io.netty:netty-common|4.1.77.Final|直接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.48.v20220622|间接依赖|maven|
|org.apache.hadoop:hadoop-common|2.6.0|间接依赖|maven|
|org.jruby.jcodings:jcodings|1.0.8|间接依赖|maven|
|org.springframework.data:spring-data-ldap|2.7.2|间接依赖|maven|
|joda-time:joda-time|2.9.9|间接依赖|maven|
|com.squareup.okio:okio|2.6.0|间接依赖|maven|
|com.jamesmurty.utils:java-xmlbuilder|0.4|间接依赖|maven|
|org.codehaus.groovy:groovy-groovysh|3.0.7|间接依赖|maven|
|com.github.davidmoten:guava-mini|0.1.3|间接依赖|maven|
|org.roaringbitmap:RoaringBitmap|0.7.45|间接依赖|maven|
|org.elasticsearch:securesm|1.2|间接依赖|maven|
|javax.ws.rs:javax.ws.rs-api|2.0.1|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-app|2.6.5|间接依赖|maven|
|com.google.guava:guava|32.1.2-jre|直接依赖|maven|
|org.hamcrest:hamcrest-core|1.3|间接依赖|maven|
|software.amazon.awssdk:regions|2.17.257|间接依赖|maven|
|org.apache.hive:hive-shims|2.3.5|间接依赖|maven|
|org.apache.ranger:ranger-plugins-common|2.4.0|直接依赖|maven|
|org.apache.commons:commons-crypto|1.0.0|间接依赖|maven|
|org.glassfish.hk2:osgi-resource-locator|1.0.1|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-shuffle|2.6.5|间接依赖|maven|
|org.springframework:spring-web|5.3.28|间接依赖|maven|
|github.com/mschoch/smat|v0.2.0|间接依赖|go|
|software.amazon.awssdk:s3|2.17.257|直接依赖|maven|
|io.airlift:aircompressor|0.15|间接依赖|maven|
|org.apache.flink:flink-runtime|1.15.3|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.3|间接依赖|maven|
|org.apache.spark:spark-launcher_2.12|3.2.0|直接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.2|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-common|2.8.3|间接依赖|maven|
|mysql:mysql-connector-java|5.1.41|直接依赖|maven|
|org.apache.spark:spark-network-common_2.12|3.2.0|间接依赖|maven|
|com.google.api-client:google-api-client|2.0.1|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-common|1.14.0|间接依赖|maven|
|io.netty:netty|3.6.2.Final|间接依赖|maven|
|github.com/RoaringBitmap/roaring|v1.2.1|直接依赖|go|
|jakarta.servlet:jakarta.servlet-api|4.0.4|间接依赖|maven|
|org.apache.maven.shared:maven-shared-utils|3.3.4|间接依赖|maven|
|com.github.stephenc.jcip:jcip-annotations|1.0-1|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.2-1|间接依赖|maven|
|org.apache.hbase:hbase-hadoop-compat|2.4.9|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.6.21|间接依赖|maven|
|github.com/dustin/go-humanize|v1.0.0|间接依赖|go|
|org.springframework.boot:spring-boot-starter|2.7.3|间接依赖|maven|
|org.apache.maven:maven-compat|3.0|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.13|间接依赖|maven|
|org.apache.curator:curator-client|2.13.0|间接依赖|maven|
|org.jline:jline|3.9.0|间接依赖|maven|
|org.apache.flink:flink-shaded-guava|30.1.1-jre-15.0|间接依赖|maven|
|software.amazon.awssdk:third-party-jackson-core|2.17.257|间接依赖|maven|
|org.apache.hadoop:hadoop-cos|3.3.5|直接依赖|maven|
|io.prometheus:simpleclient_tracer_common|0.15.0|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|间接依赖|maven|
|net.minidev:accessors-smart|1.2|间接依赖|maven|
|go.uber.org/zap|v1.14.0|间接依赖|go|
|org.apache.hbase.thirdparty:hbase-shaded-netty|3.5.1|间接依赖|maven|
|com.github.luben:zstd-jni|1.3.2-2|间接依赖|maven|
|org.apache.thrift:libfb303|0.9.3|间接依赖|maven|
|com.github.luben:zstd-jni|1.4.9-1|间接依赖|maven|
|io.opentelemetry:opentelemetry-api-logs|1.26.0-alpha|间接依赖|maven|
|io.opentelemetry:opentelemetry-extension-incubator|1.26.0-alpha|间接依赖|maven|
|com.github.spotbugs:spotbugs-annotations|3.1.9|间接依赖|maven|
|org.apache.kerby:kerb-identity|2.0.3|间接依赖|maven|
|org.apache.flink:flink-queryable-state-client-java|1.12.2|间接依赖|maven|
|org.codehaus.groovy:groovy-servlet|3.0.7|间接依赖|maven|
|github.com/pierrec/lz4|v2.6.0+incompatible|间接依赖|go|
|golang.org/x/net|v0.0.0-20211020060615-d418f374d309|间接依赖|go|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.27|间接依赖|maven|
|com.kstruct:gethostname4j|1.0.0|间接依赖|maven|
|com.cedarsoftware:java-util|1.9.0|间接依赖|maven|
|io.fabric8:kubernetes-model-coordination|5.12.2|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|com.fasterxml:classmate|1.5.0|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-ecs|4.2.0|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.1.3.GA|间接依赖|maven|
|com.squareup.okhttp3:okhttp|3.10.0|间接依赖|maven|
|github.com/prometheus/prometheus|v2.5.0+incompatible|间接依赖|go|
|org.glassfish.jersey.core:jersey-common|2.22.2|间接依赖|maven|
|org.apache.httpcomponents.client5:httpclient5|5.1.4|间接依赖|maven|
|org.ow2.asm:asm-tree|9.3|间接依赖|maven|
|javax.servlet:javax.servlet-api|3.1.0|直接依赖|maven|
|gopkg.in/yaml.v3|v3.0.0-20210107192922-496545a6307b|间接依赖|go|
|org.springframework:spring-beans|5.3.28|间接依赖|maven|
|com.sun.jersey:jersey-core|1.19.4|间接依赖|maven|
|org.apache.iceberg:iceberg-aws|1.1.0|直接依赖|maven|
|mysql:mysql-connector-java|5.1.26|直接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-otlp-common|1.14.0|间接依赖|maven|
|github.com/armon/go-radix|v1.0.0|间接依赖|go|
|org.apache.hbase:hbase-server|1.2.3|间接依赖|maven|
|software.amazon.awssdk:metrics-spi|2.17.257|间接依赖|maven|
|org.apache.arrow:arrow-memory-core|5.0.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.12.1|间接依赖|maven|
|io.netty:netty-resolver|4.1.53.Final|间接依赖|maven|
|com.tdunning:json|1.8|间接依赖|maven|
|org.apache.velocity:velocity|1.5|间接依赖|maven|
|org.slf4j:slf4j-log4j12|1.7.9|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.3|间接依赖|maven|
|org.scala-lang:scala-reflect|2.11.8|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.3.4|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|org.apache.hbase:hbase-common|2.4.9|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.6.21|间接依赖|maven|
|io.airlift:slice|0.29|间接依赖|maven|
|org.springframework:spring-core|5.3.28|间接依赖|maven|
|commons-dbcp:commons-dbcp|1.4|间接依赖|maven|
|com.aliyun.datalake:shims-cdh-hive2|0.2.14|间接依赖|maven|
|com.alibaba:druid-spring-boot-starter|1.1.14|直接依赖|maven|
|org.springframework:spring-core|5.0.5.RELEASE|间接依赖|maven|
|org.eclipse.jetty:jetty-webapp|9.4.51.v20230217|间接依赖|maven|
|com.google.auth:google-auth-library-oauth2-http|1.12.1|间接依赖|maven|
|org.springframework.data:spring-data-ldap|2.7.13|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jetty|2.7.3|间接依赖|maven|
|org.locationtech.spatial4j:spatial4j|0.7|间接依赖|maven|
|net.hydromatic:aggdesigner-algorithm|6.0|间接依赖|maven|
|github.com/elastic/go-structform|v0.0.9|间接依赖|go|
|com.fasterxml.jackson.core:jackson-databind|2.15.2|直接依赖|maven|
|org.apache.hbase:hbase-hadoop-compat|1.2.3|间接依赖|maven|
|org.apache.parquet:parquet-format-structures|1.13.1|间接依赖|maven|
|org.apache.flink:flink-streaming-java|1.15.3|间接依赖|maven|
|net.minidev:json-smart||间接依赖|maven|
|com.aliyun:aliyun-java-sdk-core|3.4.0|间接依赖|maven|
|commons-io:commons-io|2.6|间接依赖|maven|
|org.apache.parquet:parquet-common|1.13.1|直接依赖|maven|
|org.elasticsearch:elasticsearch-cli|7.17.10|间接依赖|maven|
|com.twitter:chill_2.12|0.10.0|间接依赖|maven|
|org.jline:jline|3.22.0|间接依赖|maven|
|com.fasterxml:classmate|1.0.0|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|间接依赖|maven|
|org.apache.hbase:hbase-protocol-shaded|2.4.9|间接依赖|maven|
|com.sun.jersey:jersey-json|1.9|间接依赖|maven|
|io.fabric8:zjsonpatch|0.3.0|间接依赖|maven|
|io.debezium:debezium-core|1.5.4.Final|间接依赖|maven|
|com.google.apis:google-api-services-storage|v1-rev20220705-2.0.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.11.1|间接依赖|maven|
|org.eclipse.jetty:jetty-xml|9.4.51.v20230217|间接依赖|maven|
|org.codehaus.groovy:groovy-json|3.0.7|间接依赖|maven|
|org.apache.arrow:arrow-memory-core|9.0.0|间接依赖|maven|
|org.apache.lucene:lucene-misc|8.4.0|间接依赖|maven|
|github.com/golang/protobuf|v1.5.2|间接依赖|go|
|software.amazon.awssdk:auth|2.15.45|间接依赖|maven|
|org.apache.orc:orc-mapreduce|1.4.4|间接依赖|maven|
|org.glassfish.jersey.core:jersey-server|2.22.2|间接依赖|maven|
|org.apache.kerby:kerb-util|1.0.1|间接依赖|maven|
|org.ow2.asm:asm-commons|9.4|间接依赖|maven|
|io.fabric8:kubernetes-model-apiextensions|5.12.2|间接依赖|maven|
|org.yaml:snakeyaml|1.15|间接依赖|maven|
|io.debezium:debezium-embedded|1.6.4.Final|间接依赖|maven|
|github.com/fsnotify/fsnotify|v1.5.1|间接依赖|go|
|org.apache.flink:flink-streaming-scala_2.12|1.12.2|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.27|间接依赖|maven|
|log4j:log4j|1.2.16|间接依赖|maven|
|org.glassfish:javax.json|1.1.4|间接依赖|maven|
|org.apache.lucene:lucene-join|8.3.0|间接依赖|maven|
|black|22.3.0|间接依赖|pip|
|org.apache.hadoop:hadoop-aws|2.10.2|直接依赖|maven|
|com.squareup.okhttp3:okhttp|4.7.2|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.9|间接依赖|maven|
|io.fabric8:kubernetes-model-networking|6.7.2|间接依赖|maven|
|org.apache.curator:curator-recipes|2.13.0|间接依赖|maven|
|org.codehaus.groovy:groovy-cli-picocli|3.0.7|间接依赖|maven|
|org.apache.curator:curator-recipes|5.2.0|间接依赖|maven|
|org.jetbrains:annotations|17.0.0|间接依赖|maven|
|org.apache.maven.shared:file-management|3.0.0|间接依赖|maven|
|org.apache.flink:flink-streaming-scala_2.12|1.15.3|直接依赖|maven|
|org.apache.hive:hive-llap-client|3.1.3|间接依赖|maven|
|org.apache.flink:flink-table-planner-blink_2.12|1.12.2|直接依赖|maven|
|io.netty:netty-codec-http2|4.1.94.Final|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|2.0.6|间接依赖|maven|
|org.scala-lang.modules:scala-collection-compat_2.12|2.4.3|间接依赖|maven|
|org.apache.lucene:lucene-queryparser|8.3.0|间接依赖|maven|
|io.airlift:aircompressor|0.21|间接依赖|maven|
|org.apache.commons:commons-compress|1.22|间接依赖|maven|
|io.debezium:debezium-connector-oracle|1.5.4.Final|间接依赖|maven|
|org.apache.logging.log4j:log4j-web|2.18.0|直接依赖|maven|
|org.apache.parquet:parquet-format|2.3.1|间接依赖|maven|
|github.com/go-ole/go-ole|v1.2.5-0.20190920104607-14974a1cf647|间接依赖|go|
|org.apache.hive:hive-classification|3.1.3|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|2.8|间接依赖|maven|
|process-nextick-args|2.0.1|间接依赖|npm|
|org.lz4:lz4-java|1.7.1|间接依赖|maven|
|io.netty:netty-handler-ssl-ocsp|4.1.94.Final|间接依赖|maven|
|org.apache.kerby:kerb-crypto|2.0.3|间接依赖|maven|
|org.abego.treelayout:org.abego.treelayout.core|1.0.3|间接依赖|maven|
|mysql_connector_repackaged|0.3.1|间接依赖|pip|
|io.opentelemetry:opentelemetry-api|1.14.0|间接依赖|maven|
|org.apache.spark:spark-network-shuffle_2.12|3.2.0|间接依赖|maven|
|com.sun.jersey.contribs:jersey-guice|1.9|间接依赖|maven|
|net.sf.jpam:jpam|1.1|间接依赖|maven|
|software.amazon.awssdk:arns|2.17.257|间接依赖|maven|
|go.elastic.co/fastjson|v1.1.0|间接依赖|go|
|k8s.io/apimachinery|v0.21.1|间接依赖|go|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.3|间接依赖|maven|
|software.amazon.awssdk:glue|2.17.257|直接依赖|maven|
|io.netty:netty-all|4.1.65.Final|直接依赖|maven|
|github.com/gorilla/websocket|v1.4.2|间接依赖|go|
|com.sun.jersey:jersey-servlet|1.19.4|间接依赖|maven|
|org.apache.thrift:libthrift|0.9.3|直接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet|2.35|间接依赖|maven|
|org.glassfish.hk2.external:jakarta.inject|2.6.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.15.2|直接依赖|maven|
|io.netty:netty-all|4.1.17.Final|间接依赖|maven|
|org.apache.spark:spark-tags_2.12|2.4.6|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|直接依赖|maven|
|org.springframework:spring-aop|5.3.28|间接依赖|maven|
|org.apache.velocity:velocity-engine-core|2.3|直接依赖|maven|
|org.apache.spark:spark-kvstore_2.12|2.4.6|间接依赖|maven|
|org.apache.hadoop:hadoop-hdfs-client|2.8.3|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.3|间接依赖|maven|
|org.elasticsearch:elasticsearch|7.5.1|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-common|3.3.6|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-scala_2.11|2.6.7.1|间接依赖|maven|
|io.netty:netty|3.9.9.Final|间接依赖|maven|
|com.chuusai:shapeless_2.12|2.3.4|间接依赖|maven|
|org.apache.spark:spark-network-common_2.12|2.4.6|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-applicationhistoryservice|3.1.0|间接依赖|maven|
|io.fabric8:kubernetes-model-core|5.12.2|间接依赖|maven|
|org.apache.flink:flink-table-api-scala-bridge_2.12|1.12.2|直接依赖|maven|
|github.com/elastic/go-ucfg|v0.8.3|间接依赖|go|
|io.fabric8:kubernetes-model-resource|6.7.2|间接依赖|maven|
|com.amazonaws:aws-java-sdk-kms|1.12.519|间接依赖|maven|
|org.apache.hive:hive-vector-code-gen|2.3.5|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.12.1|间接依赖|maven|
|github.com/elastic/elastic-agent-client/v7|v7.0.0-20210727140539-f0905d9377f6|间接依赖|go|
|software.amazon.awssdk:apache-client|2.15.45|间接依赖|maven|
|com.ibm.icu:icu4j|67.1|间接依赖|maven|
|io.netty:netty-codec|4.1.17.Final|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-common|2.6.5|间接依赖|maven|
|org.apache.xbean:xbean-asm9-shaded|4.20|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|3.1.0|间接依赖|maven|
|github.com/elastic/beats/v7|v7.17.5|直接依赖|go|
|io.dropwizard.metrics:metrics-jvm|4.2.19|间接依赖|maven|
|io.netty:netty-common|4.1.17.Final|间接依赖|maven|
|org.apache.flink:flink-table-api-scala_2.12|1.12.2|间接依赖|maven|
|org.springframework:spring-expression|5.3.28|间接依赖|maven|
|com.google.guava:guava|11.0.2|间接依赖|maven|
|org.jodd:jodd-core|5.3.0|直接依赖|maven|
|org.eclipse.jetty:jetty-servlets|9.4.48.v20220622|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|2.8.0|间接依赖|maven|
|io.fabric8:kubernetes-model|5.12.2|间接依赖|maven|
|org.codehaus.groovy:groovy|3.0.7|间接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.94.Final|间接依赖|maven|
|com.github.pjfanning:jersey-json|1.20|间接依赖|maven|
|org.apache.geronimo.specs:geronimo-jta_1.1_spec|1.1.1|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.15.0|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)