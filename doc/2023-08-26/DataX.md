# alibaba/DataX安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695141174380490752.svg)](https://www.murphysec.com/console/report/1692598297309241344/1695141174380490752)

仓库描述：DataX是阿里云DataWorks数据集成的开源版本。

仓库地址：[https://github.com/alibaba/DataX](https://github.com/alibaba/DataX)

| star：14032 | watch：450 | fork：4993 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-24 20:10:47 | 许可证：NOASSERTION |
| 最近检测时间：2023-08-26 02:32:54 | 组件总数：537 | 漏洞总数：211 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache Hadoop 信息泄露漏洞|密码学问题|[MPS-2012-2233](https://www.oscs1024.com/hd/MPS-2012-2233)|CVE-2012-3376|高危|
|Apache Hadoop RPC Authentication 安全绕过漏洞|身份验证不当|[MPS-2014-0455](https://www.oscs1024.com/hd/MPS-2014-0455)|CVE-2013-2192|低危|
|Apache Struts 远程代码执行漏洞|输入验证不恰当|[MPS-2014-2167](https://www.oscs1024.com/hd/MPS-2014-2167)|CVE-2014-0114|高危|
|Apache HttpClient 中间人攻击漏洞|对宿主不匹配的证书验证不恰当|[MPS-2014-4112](https://www.oscs1024.com/hd/MPS-2014-4112)|CVE-2014-3577|中危|
|Apache HttpClient 中间人攻击漏洞|输入验证不恰当|[MPS-2014-4288](https://www.oscs1024.com/hd/MPS-2014-4288)|CVE-2012-6153|中危|
|Apache Hadoop 后置链接漏洞|未授权敏感信息泄露|[MPS-2014-7381](https://www.oscs1024.com/hd/MPS-2014-7381)|CVE-2014-3627|中危|
|Oracle MySQL Connectors组件SQL注入漏洞|SQL注入|[MPS-2015-2026](https://www.oscs1024.com/hd/MPS-2015-2026)|CVE-2015-2575|中危|
|Apache Groovy 代码注入漏洞|注入|[MPS-2015-3848](https://www.oscs1024.com/hd/MPS-2015-3848)|CVE-2015-3253|严重|
|Apache HttpClient 资源管理错误漏洞|资源管理错误|[MPS-2015-5494](https://www.oscs1024.com/hd/MPS-2015-5494)|CVE-2015-5262|中危|
|多款Cisco产品Apache Commons Collections库任意代码执行漏洞|反序列化|[MPS-2015-6277](https://www.oscs1024.com/hd/MPS-2015-6277)|CVE-2015-6420|高危|
|Apache Hive authorization框架安全漏洞|身份验证不当|[MPS-2016-0636](https://www.oscs1024.com/hd/MPS-2016-0636)|CVE-2015-7521|高危|
|Apache Derby XXE 漏洞||[MPS-2016-4913](https://www.oscs1024.com/hd/MPS-2016-4913)|CVE-2015-1832|严重|
|Eclipse Jetty 信息泄露漏洞|未授权敏感信息泄露|[MPS-2016-5010](https://www.oscs1024.com/hd/MPS-2016-5010)|CVE-2015-2080|高危|
|Apache Hadoop 权限提升漏洞|访问控制不当|[MPS-2016-5884](https://www.oscs1024.com/hd/MPS-2016-5884)|CVE-2016-5393|高危|
|JCraft JSch 路径遍历漏洞|路径遍历|[MPS-2017-0498](https://www.oscs1024.com/hd/MPS-2017-0498)|CVE-2016-5725|中危|
|Google protobuf 缓冲区错误漏洞|越界写入|[MPS-2017-10841](https://www.oscs1024.com/hd/MPS-2017-10841)|CVE-2015-5237|高危|
|Apache Zookeeper 安全漏洞||[MPS-2017-11297](https://www.oscs1024.com/hd/MPS-2017-11297)|CVE-2017-5637|高危|
|Netty和Play Framework 输入验证错误漏洞|未授权敏感信息泄露|[MPS-2017-11682](https://www.oscs1024.com/hd/MPS-2017-11682)|CVE-2015-2156|高危|
|多款Red Hat产品代码问题漏洞|反序列化|[MPS-2017-12638](https://www.oscs1024.com/hd/MPS-2017-12638)|CVE-2015-7501|严重|
|QOS.ch Logback SocketServer和ServerSocketReceiver组件代码问题漏洞|反序列化|[MPS-2017-2574](https://www.oscs1024.com/hd/MPS-2017-2574)|CVE-2017-5929|严重|
|Oracle MySQL Connectors 访问限制绕过漏洞|访问控制不当|[MPS-2017-4684](https://www.oscs1024.com/hd/MPS-2017-4684)|CVE-2017-3523|高危|
|Oracle MySQL Connectors 安全漏洞|访问控制不当|[MPS-2017-4744](https://www.oscs1024.com/hd/MPS-2017-4744)|CVE-2017-3586|中危|
|Oracle MySQL Connectors 安全漏洞|访问控制不当|[MPS-2017-4746](https://www.oscs1024.com/hd/MPS-2017-4746)|CVE-2017-3589|低危|
|Apache Hadoop 跨站脚本漏洞|XSS|[MPS-2017-4858](https://www.oscs1024.com/hd/MPS-2017-4858)|CVE-2017-3161|中危|
|Apache Hadoop 输入验证错误漏洞|输入验证不恰当|[MPS-2017-4859](https://www.oscs1024.com/hd/MPS-2017-4859)|CVE-2017-3162|高危|
|Apache Hive 安全漏洞|证书验证不恰当|[MPS-2017-5977](https://www.oscs1024.com/hd/MPS-2017-5977)|CVE-2016-3083|高危|
|Apache Tomcat SecurityManager绕过漏洞|访问控制不当|[MPS-2017-9011](https://www.oscs1024.com/hd/MPS-2017-9011)|CVE-2016-5018|严重|
|Apache Tomcat 访问限制绕过漏洞|访问控制不当|[MPS-2017-9027](https://www.oscs1024.com/hd/MPS-2017-9027)|CVE-2016-6796|高危|
|Apache Hadoop 信息泄露漏洞|未授权敏感信息泄露|[MPS-2017-9780](https://www.oscs1024.com/hd/MPS-2017-9780)|CVE-2016-5001|中危|
|Apache Hadoop 信息泄露漏洞|未授权敏感信息泄露|[MPS-2017-9901](https://www.oscs1024.com/hd/MPS-2017-9901)|CVE-2016-3086|严重|
|FasterXML Jackson-databind 反序列化漏洞(dbcp2 gadget绕过)|反序列化|[MPS-2018-0362](https://www.oscs1024.com/hd/MPS-2018-0362)|CVE-2017-17485|严重|
|Apache Hadoop 信息泄漏漏洞|未授权敏感信息泄露|[MPS-2018-0896](https://www.oscs1024.com/hd/MPS-2018-0896)|CVE-2017-15713|中危|
|FasterXML jackson-databind 反序列化漏洞(Hibernate/iBatis gadget绕过)||[MPS-2018-0934](https://www.oscs1024.com/hd/MPS-2018-0934)|CVE-2018-5968|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不可达退出条件的循环（无限循环）|[MPS-2018-11233](https://www.oscs1024.com/hd/MPS-2018-11233)|CVE-2018-11771|中危|
|Oracle MySQL Connectors 访问控制错误漏洞|使用候选路径或通道进行的认证绕过|[MPS-2018-13771](https://www.oscs1024.com/hd/MPS-2018-13771)|CVE-2018-3258|高危|
|Fastjson < 1.2.25版本远程代码执行漏洞|代码注入|[MPS-2018-14062](https://www.oscs1024.com/hd/MPS-2018-14062)|CVE-2017-18349|严重|
|FasterXML Jackson-databind 反序列化漏洞(JdbcRowSetImpl gadget绕过)|反序列化|[MPS-2018-1438](https://www.oscs1024.com/hd/MPS-2018-1438)|CVE-2017-15095|严重|
|FasterXML Jackson-databind反序列化漏洞|反序列化|[MPS-2018-1439](https://www.oscs1024.com/hd/MPS-2018-1439)|CVE-2017-7525|严重|
|Apache Hive HiveServer2  访问控制不恰当漏洞|访问控制不当|[MPS-2018-14541](https://www.oscs1024.com/hd/MPS-2018-14541)|CVE-2018-11777|高危|
|Apache Hive  授权机制缺失漏洞|授权检查缺失|[MPS-2018-14542](https://www.oscs1024.com/hd/MPS-2018-14542)|CVE-2018-1314|中危|
|Apache Hadoop 路径遍历漏洞|路径遍历|[MPS-2018-14698](https://www.oscs1024.com/hd/MPS-2018-14698)|CVE-2018-8009|高危|
|FasterXML jackson-databind 反序列化漏洞(c3p0 gadget绕过)||[MPS-2018-2477](https://www.oscs1024.com/hd/MPS-2018-2477)|CVE-2018-7489|严重|
|Apache Hive 任意文件读取漏洞|未授权敏感信息泄露|[MPS-2018-4307](https://www.oscs1024.com/hd/MPS-2018-4307)|CVE-2018-1284|低危|
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|Apache Derby 权限许可和访问控制问题漏洞|访问控制不当|[MPS-2018-5754](https://www.oscs1024.com/hd/MPS-2018-5754)|CVE-2018-1313|中危|
|Apache Zookeeper 访问控制错误漏洞|授权检查缺失|[MPS-2018-6313](https://www.oscs1024.com/hd/MPS-2018-6313)|CVE-2018-8012|高危|
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
|Apache Hadoop 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2019-1459](https://www.oscs1024.com/hd/MPS-2019-1459)|CVE-2018-1296|高危|
|jackson-mapper-asl <=1.9.13 XXE 注入漏洞|XXE|[MPS-2019-15048](https://www.oscs1024.com/hd/MPS-2019-15048)|CVE-2019-10172|高危|
|SnakeYAML <1.26 存在 Billion laughs 漏洞|拒绝服务|[MPS-2019-16129](https://www.oscs1024.com/hd/MPS-2019-16129)|CVE-2017-18640|高危|
|Apache Log4j SocketServer反序列化漏洞|反序列化|[MPS-2019-17271](https://www.oscs1024.com/hd/MPS-2019-17271)|CVE-2019-17571|严重|
|FasterXML Jackson-databind反序列化漏洞（Jodd-db gadget绕过）|反序列化|[MPS-2019-2619](https://www.oscs1024.com/hd/MPS-2019-2619)|CVE-2018-12022|高危|
|FasterXML Jackson-databind反序列化漏洞(Oracle JDBC driver gadget绕过)|反序列化|[MPS-2019-2620](https://www.oscs1024.com/hd/MPS-2019-2620)|CVE-2018-12023|高危|
|Fastjson <= 1.2.60 版本远程代码执行漏洞|使用外部可控制的输入来选择类或代码（不安全的反射）|[MPS-2019-28847](https://www.oscs1024.com/hd/MPS-2019-28847)||严重|
|Fastjson < 1.2.60 版本拒绝服务漏洞|拒绝服务|[MPS-2019-28848](https://www.oscs1024.com/hd/MPS-2019-28848)||严重|
|Oracle MySQL Connectors 输入验证错误漏洞|使用不兼容类型访问资源（类型混淆）|[MPS-2019-4430](https://www.oscs1024.com/hd/MPS-2019-4430)|CVE-2019-2692|中危|
|FasterXML jackson-databind 反序列化漏洞(mysql gadget绕过)|反序列化|[MPS-2019-5442](https://www.oscs1024.com/hd/MPS-2019-5442)|CVE-2019-12086|高危|
|Apache Zookeeper 授权问题漏洞|授权检查缺失|[MPS-2019-5668](https://www.oscs1024.com/hd/MPS-2019-5668)|CVE-2019-0201|中危|
|FasterXML jackson-databind 反序列化漏洞(jdom gadget绕过)|反序列化|[MPS-2019-6867](https://www.oscs1024.com/hd/MPS-2019-6867)|CVE-2019-12814|中危|
|FasterXML jackson-databind 反序列化漏洞(logback-classic gadget绕过)|反序列化|[MPS-2019-7047](https://www.oscs1024.com/hd/MPS-2019-7047)|CVE-2019-12384|中危|
|FasterXML jackson-databind 反序列化漏洞(iBatis gadget绕过)|反序列化|[MPS-2019-7711](https://www.oscs1024.com/hd/MPS-2019-7711)|CVE-2018-11307|严重|
|FasterXML jackson-databind 反序列化漏洞(ehcache gadget绕过)|动态确定对象属性修改的控制不恰当|[MPS-2019-8717](https://www.oscs1024.com/hd/MPS-2019-8717)|CVE-2019-14379|严重|
|FasterXML jackson-databind 信息泄露漏洞(logback gadget绕过)|反序列化|[MPS-2019-8770](https://www.oscs1024.com/hd/MPS-2019-8770)|CVE-2019-14439|高危|
|FasterXML jackson-databind反序列化漏洞(net.sf.ehcache gadget绕过)|反序列化|[MPS-2020-0063](https://www.oscs1024.com/hd/MPS-2020-0063)|CVE-2019-20330|严重|
|FasterXML jackson-databind反序列化漏洞(Anteros-DBCP gadget绕过)|反序列化|[MPS-2020-11987](https://www.oscs1024.com/hd/MPS-2020-11987)|CVE-2020-24616|高危|
|FasterXML jackson-databind 反序列化漏洞(pastdev gadget绕过)|反序列化|[MPS-2020-13151](https://www.oscs1024.com/hd/MPS-2020-13151)|CVE-2020-24750|高危|
|Netty <=4.1.43.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1320](https://www.oscs1024.com/hd/MPS-2020-1320)|CVE-2020-7238|高危|
|Apache Calcite 访问控制错误漏洞|关键功能的认证机制缺失|[MPS-2020-14130](https://www.oscs1024.com/hd/MPS-2020-14130)|CVE-2020-13955|中危|
|Netty <4.1.44.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1526](https://www.oscs1024.com/hd/MPS-2020-1526)|CVE-2019-20444|严重|
|Netty <4.1.44.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1527](https://www.oscs1024.com/hd/MPS-2020-1527)|CVE-2019-20445|严重|
|Apache HttpClient URI解析错误漏洞|XSS|[MPS-2020-17341](https://www.oscs1024.com/hd/MPS-2020-17341)|CVE-2020-13956|中危|
|FasterXML jackson-databind 代码问题漏洞|XXE|[MPS-2020-17358](https://www.oscs1024.com/hd/MPS-2020-17358)|CVE-2020-25649|高危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Apache Groovy 临时目录信息泄露漏洞|缺省权限不正确|[MPS-2020-17573](https://www.oscs1024.com/hd/MPS-2020-17573)|CVE-2020-17521|中危|
|OpenTSDB 存在命令注入漏洞|命令注入|[MPS-2020-17624](https://www.oscs1024.com/hd/MPS-2020-17624)|CVE-2020-35476|严重|
|FasterXML jackson-databind 反序列化漏洞(commons-dbcp2 gadget绕过)|反序列化|[MPS-2020-17696](https://www.oscs1024.com/hd/MPS-2020-17696)|CVE-2020-35490|高危|
|FasterXML jackson-databind 反序列化漏洞(commons-dbcp2 gadget绕过)|反序列化|[MPS-2020-17697](https://www.oscs1024.com/hd/MPS-2020-17697)|CVE-2020-35491|高危|
|FasterXML jackson-databind 反序列化漏洞(glassfish gadget绕过)|反序列化|[MPS-2020-18089](https://www.oscs1024.com/hd/MPS-2020-18089)|CVE-2020-35728|高危|
|FasterXML jackson-databind 反序列化漏洞(xbean-reflect gadget绕过)|反序列化|[MPS-2020-2030](https://www.oscs1024.com/hd/MPS-2020-2030)|CVE-2020-8840|严重|
|FasterXML jackson-databind 反序列化漏洞(ignite-jta gadget绕过)|反序列化|[MPS-2020-24779](https://www.oscs1024.com/hd/MPS-2020-24779)|CVE-2020-10650|高危|
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
|FasterXML jackson-databind 反序列化漏洞(spring-aop gadget绕过)|反序列化|[MPS-2020-5138](https://www.oscs1024.com/hd/MPS-2020-5138)|CVE-2020-11619|高危|
|FasterXML jackson-databind 反序列化漏洞(commons-jelly gadget绕过)|反序列化|[MPS-2020-5139](https://www.oscs1024.com/hd/MPS-2020-5139)|CVE-2020-11620|高危|
|Apache Log4j2 SmtpAppender证书验证不当漏洞|证书验证不恰当|[MPS-2020-6684](https://www.oscs1024.com/hd/MPS-2020-6684)|CVE-2020-9488|低危|
|Apache Ant 临时文件不安全问题|将资源暴露给错误范围|[MPS-2020-7418](https://www.oscs1024.com/hd/MPS-2020-7418)|CVE-2020-1945|中危|
|PgJDBC <42.2.13 存在 XXE 漏洞|XXE|[MPS-2020-8204](https://www.oscs1024.com/hd/MPS-2020-8204)|CVE-2020-13692|高危|
|FasterXML jackson-databind反序列化漏洞(oracle-aqjms gadget绕过)|反序列化|[MPS-2020-8801](https://www.oscs1024.com/hd/MPS-2020-8801)|CVE-2020-14061|高危|
|FasterXML jackson-databind反序列化漏洞(xalan2 gadget绕过)|反序列化|[MPS-2020-8802](https://www.oscs1024.com/hd/MPS-2020-8802)|CVE-2020-14062|高危|
|FasterXML jackson-databind反序列化漏洞(apache drill gadget绕过)|反序列化|[MPS-2020-8803](https://www.oscs1024.com/hd/MPS-2020-8803)|CVE-2020-14060|高危|
|FasterXML jackson-databind代码问题漏洞(jsecurity gadget绕过)|反序列化|[MPS-2020-8911](https://www.oscs1024.com/hd/MPS-2020-8911)|CVE-2020-14195|高危|
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
|Apache Commons Compress 安存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10550](https://www.oscs1024.com/hd/MPS-2021-10550)|CVE-2021-35517|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10551](https://www.oscs1024.com/hd/MPS-2021-10551)|CVE-2021-35516|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10564](https://www.oscs1024.com/hd/MPS-2021-10564)|CVE-2021-36090|高危|
|Apache Commons Compress 无限循环漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-10565](https://www.oscs1024.com/hd/MPS-2021-10565)|CVE-2021-35515|高危|
|Netty <4.1.59.Final 存在不安全的临时文件漏洞||[MPS-2021-1580](https://www.oscs1024.com/hd/MPS-2021-1580)|CVE-2021-21290|中危|
|FasterXML jackson-databind 反序列化漏洞(javax.swing gadget绕过)|反序列化|[MPS-2021-1625](https://www.oscs1024.com/hd/MPS-2021-1625)|CVE-2021-20190|高危|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|Alibaba Druid 目录遍历漏洞|路径遍历|[MPS-2021-25327](https://www.oscs1024.com/hd/MPS-2021-25327)|CVE-2021-33800|高危|
|Apache Hive 未授权访问 UDF 漏洞|关键功能的认证机制缺失|[MPS-2021-25837](https://www.oscs1024.com/hd/MPS-2021-25837)|CVE-2021-34538|高危|
|Netty Bzip2Decoder 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28116](https://www.oscs1024.com/hd/MPS-2021-28116)|CVE-2021-37136|高危|
|Netty 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28117](https://www.oscs1024.com/hd/MPS-2021-28117)|CVE-2021-37137|高危|
|Apache Commons Net <3.9.0 存在FTP跳转攻击漏洞|未授权敏感信息泄露|[MPS-2021-28440](https://www.oscs1024.com/hd/MPS-2021-28440)|CVE-2021-37533|中危|
|Apache Hive 存在计时攻击漏洞|通过差异性导致的信息暴露|[MPS-2021-3109](https://www.oscs1024.com/hd/MPS-2021-3109)|CVE-2020-1926|中危|
|Quality Open Software logback JNDI注入漏洞|反序列化|[MPS-2021-33911](https://www.oscs1024.com/hd/MPS-2021-33911)|CVE-2021-42550|中危|
|Oracle MySQL 的 MySQL Connectors 存在授权不当漏洞|授权机制不恰当|[MPS-2021-36587](https://www.oscs1024.com/hd/MPS-2021-36587)|CVE-2022-21363|中危|
|quarkus 远程代码执行漏洞|初始化不恰当|[MPS-2021-37082](https://www.oscs1024.com/hd/MPS-2021-37082)|CVE-2022-21724|高危|
|Apache Log4j JMSAppender反序列化漏洞||[MPS-2021-38359](https://www.oscs1024.com/hd/MPS-2021-38359)|CVE-2021-4104|高危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|JDOM 存在 XXE 注入漏洞|XXE|[MPS-2021-8350](https://www.oscs1024.com/hd/MPS-2021-8350)|CVE-2021-33813|高危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9827](https://www.oscs1024.com/hd/MPS-2021-9827)|CVE-2021-36373|中危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9847](https://www.oscs1024.com/hd/MPS-2021-9847)|CVE-2021-36374|中危|
|PostgreSQL JDBC 存在 SQL 注入漏洞|SQL注入|[MPS-2022-11227](https://www.oscs1024.com/hd/MPS-2022-11227)|CVE-2022-31197|高危|
|Fastjson < 1.2.83 任意代码执行漏洞|反序列化|[MPS-2022-11320](https://www.oscs1024.com/hd/MPS-2022-11320)|CVE-2022-25845|高危|
|jnr-posix 存在UAF漏洞|UAF|[MPS-2022-11743](https://www.oscs1024.com/hd/MPS-2022-11743)||低危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|com.fasterxml.jackson.core:jackson-core 存在资源管理错误漏洞|资源管理错误|[MPS-2022-11944](https://www.oscs1024.com/hd/MPS-2022-11944)||中危|
|org.apache.tinkerpop:gremlin-core 存在XXE漏洞|XXE|[MPS-2022-12129](https://www.oscs1024.com/hd/MPS-2022-12129)||高危|
|Apache Thrift <0.9.0 拒绝服务漏洞|数字错误|[MPS-2022-12143](https://www.oscs1024.com/hd/MPS-2022-12143)||高危|
|Apache Thrift <0.9.3 SSL DOS 和不安全协商漏洞|拒绝服务|[MPS-2022-12148](https://www.oscs1024.com/hd/MPS-2022-12148)||中危|
|com.fasterxml.jackson.core:jackson-core  BigDecimal拒绝服务漏洞|资源管理错误|[MPS-2022-12166](https://www.oscs1024.com/hd/MPS-2022-12166)||中危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|Apache HttpClient URI解析错误漏洞|相对路径遍历|[MPS-2022-12292](https://www.oscs1024.com/hd/MPS-2022-12292)||中危|
|Apache Hadoop < 2.7.3 存在CSRF漏洞|CSRF|[MPS-2022-12308](https://www.oscs1024.com/hd/MPS-2022-12308)||中危|
|org.apache.hive:hive-service 存在跨站脚本漏洞|XSS|[MPS-2022-12394](https://www.oscs1024.com/hd/MPS-2022-12394)||中危|
|Logback SSL证书校验不当漏洞|中间人攻击|[MPS-2022-12411](https://www.oscs1024.com/hd/MPS-2022-12411)||中危|
|com.fasterxml.jackson.core:jackson-databind 存在反序列化漏洞|反序列化|[MPS-2022-12433](https://www.oscs1024.com/hd/MPS-2022-12433)||高危|
|org.apache.hadoop:hadoop-hdfs < 3.3.2 存在XXE漏洞|XXE|[MPS-2022-12474](https://www.oscs1024.com/hd/MPS-2022-12474)||中危|
|org.apache.hadoop:hadoop-hdfs 存在信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-12484](https://www.oscs1024.com/hd/MPS-2022-12484)||高危|
|FasterXML Jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2022-12500](https://www.oscs1024.com/hd/MPS-2022-12500)||中危|
|Apache Commons Collections 远程代码执行漏洞|反序列化|[MPS-2022-12767](https://www.oscs1024.com/hd/MPS-2022-12767)||高危|
|org.json:json 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13520](https://www.oscs1024.com/hd/MPS-2022-13520)||高危|
|Apache Log4j JDBCAppender SQL注入漏洞|SQL注入|[MPS-2022-1444](https://www.oscs1024.com/hd/MPS-2022-1444)|CVE-2022-23305|严重|
|Apache Log4j Chainsaw反序列化漏洞|反序列化|[MPS-2022-1445](https://www.oscs1024.com/hd/MPS-2022-1445)|CVE-2022-23307|高危|
|Apache Log4j 反序列化漏洞|反序列化|[MPS-2022-1446](https://www.oscs1024.com/hd/MPS-2022-1446)|CVE-2022-23302|高危|
|Apache XercesJ <=2.12.1 存在XML注入漏洞|XPath盲注|[MPS-2022-1864](https://www.oscs1024.com/hd/MPS-2022-1864)|CVE-2022-23437|中危|
|Netty 存在信息泄露漏洞||[MPS-2022-3790](https://www.oscs1024.com/hd/MPS-2022-3790)|CVE-2022-24823|中危|
|Apache Hadoop 存在shell命令注入漏洞|参数注入或修改|[MPS-2022-4190](https://www.oscs1024.com/hd/MPS-2022-4190)|CVE-2022-25168|严重|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|Apache Calcite Avatica 代码注入漏洞|代码注入|[MPS-2022-51965](https://www.oscs1024.com/hd/MPS-2022-51965)|CVE-2022-36364|高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|Apache Calcite 存在 XXE 漏洞|XXE|[MPS-2022-56508](https://www.oscs1024.com/hd/MPS-2022-56508)|CVE-2022-39135|中危|
|Jettison <1.5.2 拒绝服务漏洞|拒绝服务|[MPS-2022-57067](https://www.oscs1024.com/hd/MPS-2022-57067)|CVE-2022-40150|高危|
|Jettison <1.5.1 拒绝服务漏洞|越界写入|[MPS-2022-57068](https://www.oscs1024.com/hd/MPS-2022-57068)|CVE-2022-40149|高危|
|postgresql <42.3.3 存在代码注入漏洞|代码注入|[MPS-2022-5828](https://www.oscs1024.com/hd/MPS-2022-5828)|CVE-2022-26520|严重|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|pgjdbc <42.5.1 存在信息泄露漏洞|不安全的临时文件|[MPS-2022-58583](https://www.oscs1024.com/hd/MPS-2022-58583)|CVE-2022-41946|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|Apache Hadoop 存在路径遍历漏洞|路径遍历|[MPS-2022-5920](https://www.oscs1024.com/hd/MPS-2022-5920)|CVE-2022-26612|严重|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|Jettison <1.5.2 拒绝服务漏洞|越界写入|[MPS-2022-64973](https://www.oscs1024.com/hd/MPS-2022-64973)|CVE-2022-45685|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|OpenTSDB 安全漏洞|OS命令注入|[MPS-2023-4702](https://www.oscs1024.com/hd/MPS-2023-4702)|CVE-2023-25826|严重|
|OpenTSDB 安全漏洞|XSS|[MPS-2023-4703](https://www.oscs1024.com/hd/MPS-2023-4703)|CVE-2023-25827|中危|
|java-xmlbuilder 代码问题漏洞|XXE|[MPS-2023-5040](https://www.oscs1024.com/hd/MPS-2023-5040)|CVE-2014-125087|严重|
|Jettison 安全漏洞|未经控制的递归|[MPS-2023-8270](https://www.oscs1024.com/hd/MPS-2023-8270)|CVE-2023-1436|高危|
|jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2023-8438](https://www.oscs1024.com/hd/MPS-2023-8438)|CVE-2021-46877|中危|
|OpenTSDB 注入漏洞|注入|[MPS-2lxz-wmyc](https://www.oscs1024.com/hd/MPS-2lxz-wmyc)|CVE-2023-36812|严重|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|
|SQLite JDBC 远程代码执行漏洞|代码注入|[MPS-zprx-hdwf](https://www.oscs1024.com/hd/MPS-zprx-hdwf)|CVE-2023-32697|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.jboss.netty:netty|3.2.4.Final||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.google.protobuf:protobuf-java|2.6.1|3.21.7|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|org.apache.tinkerpop:gremlin-core|3.4.1|3.5.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-all|4.0.23.Final|4.1.44.Final|间接依赖|建议修复|C:2|H:3|M:0|L:0|
|commons-net:commons-net|3.1|3.9.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.httpcomponents:httpclient|4.5.3|4.5.13|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|19.0|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|org.codehaus.groovy:groovy|2.5.6|4.0.0-alpha-2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|18.0|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:2|L:1|
|org.apache.httpcomponents:httpclient|4.5|4.5.13|直接依赖|可选修复|C:0|H:0|M:2|L:0|
|io.netty:netty-common|4.1.48.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|392|Low|
|CDDL-1.1|12|Low|
|LGPL-2.1-or-later|2|Low|
|自定义许可证|67|Low|
|MIT|19|Low|
|EPL-1.0|8|Low|
|LGPL-2.1|8|Medium|
|BSD-2-Clause|2|Low|
|MPL-1.1|1|Low|
|JSON|1|Low|
|CPL-1.0|2|Low|
|CDDL-1.0|3|Low|
|GPL-2.0|1|Medium|
|AGPL-3.0|1|High|
|BSD-3-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.fasterxml.jackson.core:jackson-annotations|2.7.0|间接依赖|maven|
|com.microsoft.sqlserver:sqljdbc4|4.0|直接依赖|maven|
|com.aliyun.openservices:tablestore-streamclient|1.0.0|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.6|直接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.0|间接依赖|maven|
|org.apache.hive:hive-common|1.1.1|直接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.1.6|间接依赖|maven|
|commons-codec:commons-codec|1.9|直接依赖|maven|
|org.apache.directory.api:api-util|1.0.0-M20|间接依赖|maven|
|net.opentsdb:opentsdb_gwt_theme|1.0.0|间接依赖|maven|
|com.google.guava:guava|13.0.1|间接依赖|maven|
|com.alibaba:fastjson|1.2.9|间接依赖|maven|
|com.alipay.oceanbase:oceanbase-client|1.1.0|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.3.5|间接依赖|maven|
|org.apache.phoenix:phoenix-queryserver-client|4.11.0-HBase-1.1|直接依赖|maven|
|org.antlr:antlr-runtime|3.5.2|间接依赖|maven|
|org.apache.calcite:calcite-core|1.0.0-incubating|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.3|直接依赖|maven|
|org.checkerframework:checker-qual|3.5.0|间接依赖|maven|
|commons-dbcp:commons-dbcp|1.4|间接依赖|maven|
|net.objecthunter:exp4j|0.4.8|间接依赖|maven|
|com.carrotsearch:hppc|0.7.1|间接依赖|maven|
|com.alibaba:fastjson|1.2.83_noneautotype|直接依赖|maven|
|junit:junit|4.13.1|间接依赖|maven|
|com.google.guava:guava|18.0|直接依赖|maven|
|org.slf4j:slf4j-log4j12|1.7.12|间接依赖|maven|
|org.anarres.lzo:lzo-core|1.0.5|直接依赖|maven|
|com.opencsv:opencsv|4.4|间接依赖|maven|
|org.apache.tephra:tephra-core|0.13.0-incubating|间接依赖|maven|
|org.apache.tephra:tephra-core|0.12.0-incubating|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|org.apache.hive.hcatalog:hive-hcatalog-core|1.1.1|直接依赖|maven|
|org.apache.directory.server:apacheds-kerberos-codec|2.0.0-M15|间接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.9.2|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.9.8|间接依赖|maven|
|mysql:mysql-connector-java|5.1.31|直接依赖|maven|
|org.apache.hadoop:hadoop-core|0.20.205.0|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.1.3|间接依赖|maven|
|com.google.gwt:gwt-user|2.6.0|间接依赖|maven|
|stax:stax|1.2.0|间接依赖|maven|
|com.aliyun.odps:odps-sdk-commons|0.38.4-public|间接依赖|maven|
|commons-el:commons-el|1.0|间接依赖|maven|
|commons-daemon:commons-daemon|1.0.13|间接依赖|maven|
|com.alibaba.datax:hdfswriter|0.0.1-SNAPSHOT|直接依赖|maven|
|com.aliyun.hbase:alihbase-common|1.1.3|间接依赖|maven|
|org.apache.hadoop:hadoop-auth|2.5.1|间接依赖|maven|
|org.apache.commons:commons-compress|1.9|直接依赖|maven|
|org.apache.hive:hive-shims|1.1.1|间接依赖|maven|
|ch.qos.logback:logback-classic|1.0.13|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.13|间接依赖|maven|
|log4j:log4j|1.2.16|直接依赖|maven|
|mysql:mysql-connector-java|5.1.47|直接依赖|maven|
|antlr:antlr|2.7.7|间接依赖|maven|
|org.codehaus.jackson:jackson-xc|1.9.13|间接依赖|maven|
|org.apache.hive:hive-serde|1.1.1|直接依赖|maven|
|org.neo4j.driver:neo4j-java-driver|4.4.9|直接依赖|maven|
|org.apache.twill:twill-core|0.8.0|间接依赖|maven|
|org.ow2.asm:asm-tree|5.0.3|间接依赖|maven|
|org.hamcrest:hamcrest-core|1.3|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.1.2|间接依赖|maven|
|org.antlr:ST4|4.0.4|间接依赖|maven|
|io.netty:netty-all|4.0.23.Final|间接依赖|maven|
|com.alibaba.fastjson2:fastjson2|2.0.23|直接依赖|maven|
|org.codehaus.jackson:jackson-jaxrs|1.9.13|间接依赖|maven|
|org.apache.httpcomponents:httpmime|4.5.2|间接依赖|maven|
|com.google.flatbuffers:flatbuffers-java|1.9.0|间接依赖|maven|
|org.slf4j:slf4j-log4j12|1.7.24|间接依赖|maven|
|com.google.protobuf:protobuf-java|2.4.0a|间接依赖|maven|
|org.slf4j:slf4j-log4j12|1.6.1|间接依赖|maven|
|org.apache.thrift:libthrift|0.12.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.9.8|间接依赖|maven|
|com.alibaba.datax:hdfsreader|0.0.1-SNAPSHOT|直接依赖|maven|
|com.aliyun.phoenix:ali-phoenix-core|4.12.0-AliHBase-1.1-0.5|直接依赖|maven|
|org.apache.arrow:arrow-vector|1.0.0|间接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|org.apache.hive.shims:hive-shims-0.20S|1.1.1|间接依赖|maven|
|com.alibaba.datax:streamreader|0.0.1-SNAPSHOT|直接依赖|maven|
|com.aliyun.hbase:alihbase-client|1.1.3|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-common|2.6.0|间接依赖|maven|
|com.oracle:ojdbc6|11.2.0.3|直接依赖|maven|
|com.squareup.retrofit2:converter-jackson|2.6.0|间接依赖|maven|
|com.alibaba.datax:streamwriter|0.0.1-SNAPSHOT|直接依赖|maven|
|commons-validator:commons-validator|1.4.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.7.3|间接依赖|maven|
|org.apache.hive:hive-ant|1.1.1|间接依赖|maven|
|org.apache.hbase:hbase-common|1.1.3|直接依赖|maven|
|com.google.protobuf:protobuf-java|2.4.1|间接依赖|maven|
|com.databend:databend-jdbc|0.1.0|直接依赖|maven|
|com.aliyun:hitsdb-client|0.3.7|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.9.5|间接依赖|maven|
|org.lz4:lz4-java|1.4.0|间接依赖|maven|
|org.apache.ant:ant-launcher|1.9.1|间接依赖|maven|
|org.postgresql:postgresql|42.2.5|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|org.apache.geronimo.specs:geronimo-annotation_1.0_spec|1.1.1|间接依赖|maven|
|org.apache.tephra:tephra-hbase-compat-1.1|0.13.0-incubating|间接依赖|maven|
|org.slf4j:slf4j-log4j12|1.7.10|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.9.8|间接依赖|maven|
|org.apache.hive:hive-cli|1.1.1|间接依赖|maven|
|com.google.code.simple-spring-memcached:spymemcached|2.8.1|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|直接依赖|maven|
|org.apache.hive:hive-metastore|1.1.1|间接依赖|maven|
|org.jamon:jamon-runtime|2.3.1|间接依赖|maven|
|org.tukaani:xz|1.0|间接依赖|maven|
|org.apache.twill:twill-zookeeper|0.8.0|间接依赖|maven|
|org.apache.tephra:tephra-hbase-compat-1.1|0.12.0-incubating|间接依赖|maven|
|commons-codec:commons-codec|1.4|间接依赖|maven|
|com.google.code.gson:gson|2.8.0|间接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.8.8|间接依赖|maven|
|com.google.guava:guava|30.1.1-jre|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.2|间接依赖|maven|
|org.datanucleus:datanucleus-core|3.2.10|间接依赖|maven|
|org.ow2.asm:asm-all|5.0.2|间接依赖|maven|
|log4j:apache-log4j-extras|1.2.17|间接依赖|maven|
|org.json:json|20160810|直接依赖|maven|
|org.xerial.snappy:snappy-java|1.0.4.1|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|3.2.2|间接依赖|maven|
|net.opentsdb:opentsdb|2.3.2|直接依赖|maven|
|com.jamesmurty.utils:java-xmlbuilder|0.4|间接依赖|maven|
|net.sf.ezmorph:ezmorph|1.0.6|间接依赖|maven|
|com.github.jnr:jffi|1.2.16|间接依赖|maven|
|net.sourceforge.javacsv:javacsv|2.0|直接依赖|maven|
|net.java.dev.jna:jna|5.8.0|间接依赖|maven|
|com.aliyun.odps:odps-sdk-core|0.38.4-public|直接依赖|maven|
|joda-time:joda-time|2.9.7|直接依赖|maven|
|org.apache.thrift:libthrift|0.9.2|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.4|间接依赖|maven|
|io.netty:netty-common|4.1.48.Final|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.3|间接依赖|maven|
|org.java-websocket:Java-WebSocket|1.5.2|间接依赖|maven|
|org.mortbay.jetty:jetty-util|6.1.26|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.1.2|间接依赖|maven|
|joda-time:joda-time|1.6|间接依赖|maven|
|com.github.docker-java:docker-java-api|3.2.13|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.10.0|间接依赖|maven|
|commons-pool:commons-pool|1.5.4|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.3|直接依赖|maven|
|commons-codec:commons-codec|1.8|直接依赖|maven|
|org.codehaus.jettison:jettison|1.1|间接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.3|间接依赖|maven|
|com.sun.xml.bind:jaxb-impl|2.2.3-1|间接依赖|maven|
|com.squareup.okhttp3:okhttp|3.14.2|间接依赖|maven|
|com.google.guava:guava|12.0.1|直接依赖|maven|
|org.apache.commons:commons-collections4|4.2|间接依赖|maven|
|org.ow2.asm:asm-util|5.0.3|间接依赖|maven|
|com.google.inject.extensions:guice-assistedinject|3.0|间接依赖|maven|
|org.slf4j:log4j-over-slf4j|1.7.7|间接依赖|maven|
|javax.validation:validation-api|1.0.0.GA|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.9.5|间接依赖|maven|
|com.sun.jersey:jersey-core|1.8|间接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j-impl|2.0.2|间接依赖|maven|
|org.aspectj:aspectjrt|1.8.9|间接依赖|maven|
|commons-logging:commons-logging|1.1.1|直接依赖|maven|
|commons-configuration:commons-configuration|1.6|间接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.9.11|间接依赖|maven|
|org.apache.velocity:velocity|1.5|间接依赖|maven|
|org.jgrapht:jgrapht-core|0.9.1|间接依赖|maven|
|com.google.code.findbugs:jsr305|1.3.9|直接依赖|maven|
|org.antlr:stringtemplate|3.2.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.6.3|间接依赖|maven|
|org.apache.geronimo.specs:geronimo-jta_1.1_spec|1.1.1|间接依赖|maven|
|io.netty:netty-handler|4.0.56.Final|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.1|间接依赖|maven|
|net.java.dev.jets3t:jets3t|0.7.1|间接依赖|maven|
|org.hbase:asynchbase|1.8.2|间接依赖|maven|
|jline:jline|2.12|间接依赖|maven|
|com.jcraft:jsch|0.1.54|直接依赖|maven|
|org.apache.parquet:parquet-format|2.3.1|直接依赖|maven|
|com.github.jnr:jnr-posix|3.0.44|间接依赖|maven|
|com.google.flatbuffers:flatbuffers-java|1.11.0|间接依赖|maven|
|org.pentaho:pentaho-aggdesigner-algorithm|5.1.5-jhyde|间接依赖|maven|
|org.apache.hbase:hbase-annotations|1.1.9|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.1|间接依赖|maven|
|com.aliyun.odps:odps-sdk-core|0.26.2-public|间接依赖|maven|
|com.alibaba:fastjson|1.2.83|间接依赖|maven|
|net.sf.kosmosfs:kfs|0.3|间接依赖|maven|
|com.jcabi:jcabi-manifests|1.1|间接依赖|maven|
|commons-httpclient:commons-httpclient|3.1|直接依赖|maven|
|org.mortbay.jetty:servlet-api-2.5|6.1.14|间接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.6|间接依赖|maven|
|com.lmax:disruptor|3.3.0|间接依赖|maven|
|commons-io:commons-io|2.4|直接依赖|maven|
|com.alibaba.datax:plugin-rdbms-util|0.0.1-SNAPSHOT|直接依赖|maven|
|oro:oro|2.0.8|间接依赖|maven|
|commons-logging:commons-logging|1.0.4|间接依赖|maven|
|org.checkerframework:checker-qual|3.8.0|间接依赖|maven|
|org.apache.hadoop:hadoop-hdfs|2.5.0|直接依赖|maven|
|com.twitter:parquet-hadoop-bundle|1.6.0|直接依赖|maven|
|ru.yandex.clickhouse:clickhouse-jdbc|0.2.4|直接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.9.13|间接依赖|maven|
|it.unimi.dsi:fastutil|6.5.6|间接依赖|maven|
|org.apache.thrift:libthrift|0.9.0|间接依赖|maven|
|com.yammer.metrics:metrics-core|2.2.0|间接依赖|maven|
|javax.servlet:servlet-api|2.5|间接依赖|maven|
|org.apache.twill:twill-api|0.8.0|间接依赖|maven|
|com.google.guava:guava|19.0|间接依赖|maven|
|org.apache.parquet:parquet-column|1.8.1|直接依赖|maven|
|asm:asm-tree|3.1|间接依赖|maven|
|javax.jdo:jdo-api|3.0.1|间接依赖|maven|
|io.airlift:aircompressor|0.3|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.3|直接依赖|maven|
|org.jruby:jruby-complete|1.6.5|间接依赖|maven|
|com.alibaba.datax:datax-transformer|0.0.1-SNAPSHOT|直接依赖|maven|
|net.java.dev.jets3t:jets3t|0.9.0|间接依赖|maven|
|com.google.guava:guava|r05|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.2.0|间接依赖|maven|
|commons-lang:commons-lang|2.6|间接依赖|maven|
|commons-lang:commons-lang|2.3|直接依赖|maven|
|com.aliyun.oss:aliyun-sdk-oss|3.4.2|直接依赖|maven|
|commons-beanutils:commons-beanutils-core|1.8.0|间接依赖|maven|
|org.apache.parquet:parquet-common|1.8.1|直接依赖|maven|
|org.apache.hadoop:hadoop-client|2.5.1|间接依赖|maven|
|com.alibaba.datax:plugin-unstructured-storage-util|0.0.1-SNAPSHOT|直接依赖|maven|
|org.apache.htrace:htrace-core|3.1.0-incubating|间接依赖|maven|
|org.apache.hbase:hbase-client|1.1.9|间接依赖|maven|
|org.apache.calcite.avatica:avatica-metrics|1.10.0|间接依赖|maven|
|com.jcabi:jcabi-log|0.15|间接依赖|maven|
|com.yammer.metrics:metrics-core|2.1.2|间接依赖|maven|
|com.alibaba:fastjson|1.2.8|间接依赖|maven|
|jline:jline|0.9.94|间接依赖|maven|
|io.netty:netty|3.6.2.Final|间接依赖|maven|
|io.netty:netty-all|4.1.25.Final|间接依赖|maven|
|org.mongodb:mongo-java-driver|3.2.2|直接依赖|maven|
|com.google.protobuf:protobuf-java|3.2.0|直接依赖|maven|
|com.sun.jersey:jersey-server|1.8|间接依赖|maven|
|org.json:json|20090211|间接依赖|maven|
|org.apache.hadoop:hadoop-common|2.7.1|直接依赖|maven|
|org.testcontainers:testcontainers|1.17.6|直接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-jobclient|2.5.1|间接依赖|maven|
|com.aliyun.odps:odps-sdk-commons|0.26.2-public|间接依赖|maven|
|com.google.guava:guava|11.0.2|间接依赖|maven|
|com.github.docker-java:docker-java-transport|3.2.13|间接依赖|maven|
|org.apache.tinkerpop:gremlin-driver|3.4.1|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.0.1|间接依赖|maven|
|io.netty:netty-common|4.0.56.Final|间接依赖|maven|
|org.xerial:sqlite-jdbc|3.34.0|直接依赖|maven|
|com.google.code.findbugs:annotations|2.0.3|间接依赖|maven|
|org.apache.avro:avro|1.7.6|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-core|2.5.1|间接依赖|maven|
|com.aliyun.hbase:alihbase-hadoop-compat|1.1.3|间接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.0.2|间接依赖|maven|
|javax.servlet.jsp:jsp-api|2.1|间接依赖|maven|
|commons-collections:commons-collections|3.2.1|间接依赖|maven|
|org.codehaus.groovy:groovy-all|2.1.9|直接依赖|maven|
|org.apache.geronimo.specs:geronimo-jaspic_1.0_spec|1.0|间接依赖|maven|
|org.aspectj:aspectjrt|1.8.2|间接依赖|maven|
|io.netty:netty|3.10.6.Final|间接依赖|maven|
|io.netty:netty-codec|4.0.56.Final|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.25|间接依赖|maven|
|com.twitter:parquet-hadoop-bundle|1.6.0rc3|间接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.17.1|直接依赖|maven|
|com.clearspring.analytics:stream|2.9.5|间接依赖|maven|
|com.stumbleupon:async|1.4.0|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-app|2.5.1|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-common|2.5.1|间接依赖|maven|
|com.google.code.findbugs:jsr305|2.0.1|间接依赖|maven|
|org.slf4j:slf4j-log4j12|1.4.3|间接依赖|maven|
|org.apache.commons:commons-math|2.1|间接依赖|maven|
|org.apache.kudu:kudu-client|1.11.1|直接依赖|maven|
|commons-codec:commons-codec|1.11|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|3.2.6|间接依赖|maven|
|org.apache.arrow:arrow-format|1.0.0|间接依赖|maven|
|org.apache.calcite:calcite-avatica|1.0.0-incubating|间接依赖|maven|
|commons-net:commons-net|1.4.1|间接依赖|maven|
|org.apache.hbase:hbase-protocol|1.1.9|间接依赖|maven|
|tomcat:jasper-runtime|5.5.23|间接依赖|maven|
|org.projectlombok:lombok|1.18.8|直接依赖|maven|
|org.apache.calcite.avatica:avatica-core|1.10.0|间接依赖|maven|
|com.jcabi:jcabi-log|0.14|间接依赖|maven|
|com.alibaba.datax.tdenginewriter:tdenginewriter|0.0.1-SNAPSHOT|直接依赖|maven|
|io.searchbox:jest-common|6.3.1|直接依赖|maven|
|com.github.stephenc.jcip:jcip-annotations|1.0-1|间接依赖|maven|
|log4j:log4j|1.2.17|间接依赖|maven|
|com.solidfire.code.gson:gson|2.6.2|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.0.1|间接依赖|maven|
|com.alibaba.datax:datax-core|0.0.1-SNAPSHOT|直接依赖|maven|
|org.apache.tephra:tephra-api|0.13.0-incubating|间接依赖|maven|
|io.searchbox:jest|6.3.1|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.1|间接依赖|maven|
|org.apache.commons:commons-lang3|3.3.2|直接依赖|maven|
|commons-codec:commons-codec|1.6|间接依赖|maven|
|io.netty:netty-buffer|4.0.56.Final|间接依赖|maven|
|com.alibaba.cloud.analyticdb:adbclient|1.0.2|直接依赖|maven|
|org.apache.commons:commons-compress|1.4.1|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.3.2|间接依赖|maven|
|org.jdom:jdom|1.1|间接依赖|maven|
|com.alibaba.datax:datax-example-core|0.0.1-SNAPSHOT|直接依赖|maven|
|mysql:mysql-connector-java|5.1.46|直接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.0|间接依赖|maven|
|com.alibaba.datax:datax-common|0.0.1-SNAPSHOT|直接依赖|maven|
|io.netty:netty-transport|4.0.56.Final|间接依赖|maven|
|com.aliyun.hbase:alihbase-prefix-tree|1.1.3|间接依赖|maven|
|org.apache.tinkerpop:gremlin-core|3.4.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.3|直接依赖|maven|
|mysql:mysql-connector-java|5.1.40|直接依赖|maven|
|org.eclipse.jetty.aggregate:jetty-all|7.6.0.v20120127|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.6.3|间接依赖|maven|
|org.codehaus.jackson:jackson-xc|1.8.8|间接依赖|maven|
|com.dameng:Dm7JdbcDriver17|7.6.0.142|直接依赖|maven|
|org.apache.directory.api:api-asn1-api|1.0.0-M20|间接依赖|maven|
|com.alibaba:fastjson|1.2.62|间接依赖|maven|
|com.alibaba.datax:datax-example-streamreader|0.0.1-SNAPSHOT|直接依赖|maven|
|org.apache.twill:twill-common|0.8.0|间接依赖|maven|
|org.rnorth.duct-tape:duct-tape|1.0.8|间接依赖|maven|
|eigenbase:eigenbase-properties|1.1.4|间接依赖|maven|
|com.aliyun.odps:odps-sdk-mapred|0.26.2-public|间接依赖|maven|
|com.aliyun.hbase:alihbase-hadoop2-compat|1.1.3|间接依赖|maven|
|org.apache.hive.shims:hive-shims-common|1.1.1|间接依赖|maven|
|org.apache.commons:commons-exec|1.3|直接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|com.sun.jersey:jersey-json|1.8|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.2|直接依赖|maven|
|jline:jline|2.11|间接依赖|maven|
|javax.xml.stream:stax-api|1.0-2|间接依赖|maven|
|com.stumbleupon:async|1.4.1|间接依赖|maven|
|org.apache.twill:twill-discovery-api|0.8.0|间接依赖|maven|
|org.apache.commons:commons-math3|3.4.1|间接依赖|maven|
|com.taosdata.jdbc:taos-jdbcdriver|2.0.39|直接依赖|maven|
|com.aliyun.hbase:alihbase-protocol|1.1.3|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|org.apache.hbase:hbase-client|1.1.3|直接依赖|maven|
|javax.mail:mail|1.4.1|间接依赖|maven|
|org.ow2.asm:asm-commons|5.0.3|间接依赖|maven|
|org.apache.curator:curator-client|2.7.1|间接依赖|maven|
|com.jcabi:jcabi-aspects|0.20.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.10.0|间接依赖|maven|
|org.javatuples:javatuples|1.2|间接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|org.apache.hive:hive-service|1.1.1|直接依赖|maven|
|org.fusesource.leveldbjni:leveldbjni-all|1.8|间接依赖|maven|
|org.apache.ant:ant|1.9.1|间接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.3|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.17|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-resourcemanager|2.6.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.10.0|间接依赖|maven|
|org.jruby.joni:joni|2.1.2|间接依赖|maven|
|org.apache.commons:commons-math|2.2|间接依赖|maven|
|org.datanucleus:datanucleus-rdbms|3.2.9|间接依赖|maven|
|org.apache.curator:apache-curator|2.6.0|间接依赖|maven|
|com.google.code.gson:gson|2.2.4|直接依赖|maven|
|org.codehaus.jackson:jackson-mapper-asl|1.8.8|间接依赖|maven|
|org.apache.hbase:hbase-procedure|1.1.9|间接依赖|maven|
|org.codehaus.jackson:jackson-jaxrs|1.8.8|间接依赖|maven|
|com.sun.jersey:jersey-client|1.9|间接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.3.2|间接依赖|maven|
|org.eclipse.jdt:core|3.1.1|间接依赖|maven|
|com.alibaba:druid|1.1.17|直接依赖|maven|
|org.mortbay.jetty:jsp-2.1|6.1.14|间接依赖|maven|
|org.datanucleus:datanucleus-api-jdo|3.2.6|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.10|直接依赖|maven|
|org.apache.curator:curator-recipes|2.7.1|间接依赖|maven|
|com.alibaba:druid|1.1.12|直接依赖|maven|
|org.mortbay.jetty:jsp-api-2.1|6.1.14|间接依赖|maven|
|com.google.guava:guava|15.0|间接依赖|maven|
|org.ow2.asm:asm-analysis|5.0.3|间接依赖|maven|
|org.codehaus.jackson:jackson-xc|1.8.3|间接依赖|maven|
|joda-time:joda-time|2.9.9|直接依赖|maven|
|com.aliyun.oss:hadoop-aliyun|2.7.2|直接依赖|maven|
|hsqldb:hsqldb|1.8.0.10|间接依赖|maven|
|org.apache.calcite:calcite-linq4j|1.0.0-incubating|间接依赖|maven|
|org.apache.hbase:hbase-annotations|1.1.3|间接依赖|maven|
|org.apache.parquet:parquet-avro|1.8.1|直接依赖|maven|
|org.apache.hive:hive-exec|1.1.1|直接依赖|maven|
|com.alibaba.datax:odpswriter|0.0.1-SNAPSHOT|直接依赖|maven|
|org.postgresql:postgresql|42.3.3|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-applicationhistoryservice|2.6.0|间接依赖|maven|
|org.aspectj:aspectjweaver|1.8.10|直接依赖|maven|
|org.checkerframework:checker-qual|2.5.2|间接依赖|maven|
|com.aliyun.openservices:aliyun-log|0.6.12|直接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|直接依赖|maven|
|org.xerial.snappy:snappy-java|1.0.3.2|间接依赖|maven|
|com.ibm.db2.jcc:db2jcc|db2jcc4|直接依赖|maven|
|com.alibaba.hbase:alihbase-connector|1.0.4|直接依赖|maven|
|com.lmax:disruptor|3.0.1|间接依赖|maven|
|net.sf.opencsv:opencsv|2.3|间接依赖|maven|
|org.mortbay.jetty:jetty|6.1.26|间接依赖|maven|
|xpp3:xpp3|1.1.3.3|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-common|2.5.1|间接依赖|maven|
|com.google.guava:guava|21.0|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|2.5.1|间接依赖|maven|
|it.unimi.dsi:fastutil|6.5.7|间接依赖|maven|
|org.apache.avro:avro-ipc|1.5.3|间接依赖|maven|
|com.aliyun.openservices:ots-public|2.2.6|直接依赖|maven|
|com.aliyun.openservices:tablestore|5.13.10|直接依赖|maven|
|com.aliyun.hbase:alihbase-annotations|1.1.3|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-ecs|4.2.0|间接依赖|maven|
|com.github.jnr:jnr-constants|0.9.9|间接依赖|maven|
|com.github.jnr:jnr-x86asm|1.0.2|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.1|直接依赖|maven|
|com.github.stephenc.findbugs:findbugs-annotations|1.3.9-1|间接依赖|maven|
|com.lmax:disruptor|3.4.4|间接依赖|maven|
|joda-time:joda-time|2.9.1|间接依赖|maven|
|com.csicit.thirdparty:oscar|1.0.1|直接依赖|maven|
|org.apache.commons:commons-text|1.3|间接依赖|maven|
|org.jruby.jcodings:jcodings|1.0.8|间接依赖|maven|
|org.apache.hbase:hbase-hadoop-compat|1.1.9|间接依赖|maven|
|com.datastax.cassandra:cassandra-driver-core|3.7.2|直接依赖|maven|
|com.aliyun:aliyun-java-sdk-core|3.4.0|间接依赖|maven|
|com.sun.jersey.contribs:jersey-guice|1.9|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-web-proxy|2.6.0|间接依赖|maven|
|org.jetbrains:annotations|17.0.0|间接依赖|maven|
|org.codehaus.jackson:jackson-jaxrs|1.8.3|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|3.1.0|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.4.1|直接依赖|maven|
|org.jboss.netty:netty|3.2.4.Final|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.3.2|直接依赖|maven|
|commons-collections:commons-collections|3.0|直接依赖|maven|
|com.google.inject.extensions:guice-servlet|3.0|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|org.apache.tephra:tephra-api|0.12.0-incubating|间接依赖|maven|
|commons-logging:commons-logging|1.1.3|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.2.2|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.1|间接依赖|maven|
|org.apache.hive.shims:hive-shims-0.23|1.1.1|间接依赖|maven|
|ch.qos.logback:logback-core|1.0.13|间接依赖|maven|
|com.jcraft:jsch|0.1.42|间接依赖|maven|
|com.github.docker-java:docker-java-transport-zerodep|3.2.13|间接依赖|maven|
|org.apache.commons:commons-jexl|2.1.1|间接依赖|maven|
|org.apache.commons:commons-math3|3.1.1|直接依赖|maven|
|com.alibaba:druid|1.0.15|直接依赖|maven|
|javax.transaction:jta|1.1|间接依赖|maven|
|tomcat:jasper-compiler|5.5.23|间接依赖|maven|
|com.alibaba.datax:neo4jwriter|0.0.1-SNAPSHOT|直接依赖|maven|
|com.squareup.retrofit2:retrofit|2.6.0|间接依赖|maven|
|com.aliyun.oss:aliyun-sdk-oss|2.2.3|直接依赖|maven|
|org.apache.directory.server:apacheds-i18n|2.0.0-M15|间接依赖|maven|
|xmlenc:xmlenc|0.52|间接依赖|maven|
|com.google.inject:guice|3.0|间接依赖|maven|
|org.apache.commons:commons-compress|1.22|间接依赖|maven|
|javax.mail:mail|1.4.7|间接依赖|maven|
|com.aliyun.datahub:aliyun-sdk-datahub|2.21.6-public|直接依赖|maven|
|org.apache.hadoop:hadoop-hdfs|2.7.1|直接依赖|maven|
|commons-configuration:commons-configuration|1.10|直接依赖|maven|
|org.codehaus.janino:janino|2.7.6|间接依赖|maven|
|commons-net:commons-net|3.1|间接依赖|maven|
|com.sun.jersey:jersey-json|1.9|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.7.3|间接依赖|maven|
|org.apache.thrift:libfb303|0.9.2|间接依赖|maven|
|org.apache.curator:curator-framework|2.6.0|间接依赖|maven|
|javax.activation:activation|1.1|间接依赖|maven|
|com.aliyun.openservices:tablestore|5.13.13|直接依赖|maven|
|com.alibaba.hologres:holo-client|2.1.0|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-client|2.5.1|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.4.6|间接依赖|maven|
|com.google.protobuf:protobuf-java|2.5.0|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.5.1|间接依赖|maven|
|com.aliyun.openservices:ots-public|2.2.4|直接依赖|maven|
|commons-beanutils:commons-beanutils|1.8.0|间接依赖|maven|
|commons-net:commons-net|3.3|直接依赖|maven|
|io.netty:netty|3.7.0.Final|间接依赖|maven|
|com.alibaba.datax:datax-example|0.0.1-SNAPSHOT|直接依赖|maven|
|org.apache.hbase:hbase-common|1.1.9|间接依赖|maven|
|xerces:xercesImpl|2.9.1|间接依赖|maven|
|org.codehaus.jackson:jackson-mapper-asl|1.9.11|间接依赖|maven|
|org.apache.httpcomponents:fluent-hc|4.5|直接依赖|maven|
|org.ow2.asm:asm|5.0.3|间接依赖|maven|
|xml-apis:xml-apis|1.3.04|间接依赖|maven|
|org.apache.commons:commons-csv|1.0|间接依赖|maven|
|org.codehaus.jackson:jackson-mapper-asl|1.9.2|间接依赖|maven|
|org.apache.arrow:arrow-memory-core|1.0.0|间接依赖|maven|
|org.iq80.snappy:snappy|0.3|间接依赖|maven|
|org.apache.twill:twill-discovery-core|0.8.0|间接依赖|maven|
|org.yaml:snakeyaml|1.15|间接依赖|maven|
|org.apache.derby:derby|10.11.1.1|间接依赖|maven|
|com.aliyun.hbase:alihbase-procedure|1.1.3|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-shuffle|2.5.1|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|org.apache.hbase:hbase-protocol|1.1.3|间接依赖|maven|
|commons-digester:commons-digester|1.8|间接依赖|maven|
|org.codehaus.groovy:groovy-json|2.5.6|间接依赖|maven|
|commons-lang:commons-lang|2.5|间接依赖|maven|
|javax.validation:validation-api|1.1.0.Final|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5|直接依赖|maven|
|asm:asm-commons|3.1|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-sts|3.0.0|间接依赖|maven|
|org.apache.thrift:libthrift|0.8.0|间接依赖|maven|
|com.squareup.okio:okio|1.17.2|间接依赖|maven|
|com.aliyun.phoenix:ali-phoenix-shaded-thin-client|5.2.5-HBase-2.x|直接依赖|maven|
|org.apache.avro:avro|1.5.3|间接依赖|maven|
|sqlline:sqlline|1.2.0|间接依赖|maven|
|org.apache.hbase:hbase|0.94.27|直接依赖|maven|
|com.jolbox:bonecp|0.8.0.RELEASE|间接依赖|maven|
|commons-codec:commons-codec|1.5|间接依赖|maven|
|org.apache.parquet:parquet-hadoop|1.8.1|直接依赖|maven|
|org.apache.hadoop:hadoop-hdfs|2.5.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.6.3|间接依赖|maven|
|org.apache.hive.shims:hive-shims-scheduler|1.1.1|间接依赖|maven|
|org.codehaus.groovy:groovy|2.5.6|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.10.3|间接依赖|maven|
|commons-cli:commons-cli|1.2|直接依赖|maven|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|2.5.1|间接依赖|maven|
|org.codehaus.janino:janino|2.5.16|直接依赖|maven|
|org.codehaus.janino:commons-compiler|2.7.6|间接依赖|maven|
|commons-codec:commons-codec|1.7|间接依赖|maven|
|net.jpountz.lz4:lz4|1.3.0|间接依赖|maven|
|com.github.stephenc.high-scale-lib:high-scale-lib|1.1.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.9.5|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-core|2.7.1|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|2.7.1|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|2.7.1|直接依赖|maven|
|com.google.protobuf:protobuf-java|2.6.1|间接依赖|maven|
|org.apache.curator:curator-framework|2.7.1|间接依赖|maven|
|net.sf.jpam:jpam|1.1|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.4.0|直接依赖|maven|
|com.aliyun.hbase:alihbase-server|1.1.3|间接依赖|maven|
|org.apache.phoenix:phoenix-core|4.11.0-HBase-1.1|直接依赖|maven|
|com.github.jnr:jnr-ffi|2.1.7|间接依赖|maven|
|com.aliyun.openservices:aliyun-log|0.6.22|直接依赖|maven|
|org.apache.hadoop:hadoop-auth|2.7.1|间接依赖|maven|
|com.google.guava:guava|16.0.1|直接依赖|maven|
|org.apache.hbase:hbase-prefix-tree|1.1.9|间接依赖|maven|
|org.apache.parquet:parquet-encoding|1.8.1|直接依赖|maven|
|org.apache.hadoop:hadoop-annotations|2.5.1|间接依赖|maven|
|com.squareup.okhttp3:logging-interceptor|3.14.2|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|2.7.1|间接依赖|maven|
|com.sun.jersey:jersey-core|1.9|间接依赖|maven|
|org.apache.hadoop:hadoop-common|2.5.1|间接依赖|maven|
|org.apache.hbase:hbase-hadoop2-compat|1.1.9|间接依赖|maven|
|org.apache.parquet:parquet-jackson|1.8.1|直接依赖|maven|
|com.google.guava:guava|27.0.1-jre|间接依赖|maven|
|com.squareup:javapoet|1.8.0|间接依赖|maven|
|net.sf.json-lib:json-lib|2.4|间接依赖|maven|
|org.antlr:antlr-runtime|3.4|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-ram|3.0.0|间接依赖|maven|
|org.apache.tinkerpop:gremlin-shaded|3.4.1|间接依赖|maven|
|stax:stax-api|1.0.1|间接依赖|maven|
|org.apache.hbase:hbase-server|1.1.9|间接依赖|maven|
|com.sun.jersey:jersey-server|1.9|间接依赖|maven|
|org.mortbay.jetty:jetty-sslengine|6.1.26|间接依赖|maven|
|asm:asm|3.1|间接依赖|maven|
|com.aliyun.openservices:tablestore|5.13.12|直接依赖|maven|
|org.apache.velocity:velocity|1.7|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|org.codehaus.groovy:groovy-all|2.1.6|间接依赖|maven|
|com.alibaba.cloud.analyticdb:adb4pgclient|1.0.0|直接依赖|maven|
|org.apache.avro:avro|1.7.4|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)