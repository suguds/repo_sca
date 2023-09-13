# apache/seatunnel安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1702020653594230784.svg)](https://www.murphysec.com/console/report/1695134512223514624/1702020653594230784)

仓库描述：SeaTunnel is a next-generation super high-performance, distributed, massive data integration tool.

仓库地址：[https://github.com/apache/seatunnel](https://github.com/apache/seatunnel)

| star：6374 | watch：168 | fork：1286 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-13 21:19:07 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-14 02:20:29 | 组件总数：861 | 漏洞总数：192 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache Hadoop 信息泄露漏洞|密码学问题|[MPS-2012-2233](https://www.oscs1024.com/hd/MPS-2012-2233)|CVE-2012-3376|高危|
|Apache HttpClient 中间人攻击漏洞|输入验证不恰当|[MPS-2014-4288](https://www.oscs1024.com/hd/MPS-2014-4288)|CVE-2012-6153|中危|
|Apache HttpClient 资源管理错误漏洞|资源管理错误|[MPS-2015-5494](https://www.oscs1024.com/hd/MPS-2015-5494)|CVE-2015-5262|中危|
|Apache Hadoop 信息泄露漏洞|未授权敏感信息泄露|[MPS-2016-1783](https://www.oscs1024.com/hd/MPS-2016-1783)|CVE-2015-1776|中危|
|Google protobuf 缓冲区错误漏洞|越界写入|[MPS-2017-10841](https://www.oscs1024.com/hd/MPS-2017-10841)|CVE-2015-5237|高危|
|Apache Zookeeper 安全漏洞||[MPS-2017-11297](https://www.oscs1024.com/hd/MPS-2017-11297)|CVE-2017-5637|高危|
|Apache Hadoop 跨站脚本漏洞|XSS|[MPS-2017-4858](https://www.oscs1024.com/hd/MPS-2017-4858)|CVE-2017-3161|中危|
|Apache Hadoop 输入验证错误漏洞|输入验证不恰当|[MPS-2017-4859](https://www.oscs1024.com/hd/MPS-2017-4859)|CVE-2017-3162|高危|
|FasterXML Jackson-databind 反序列化漏洞(dbcp2 gadget绕过)|反序列化|[MPS-2018-0362](https://www.oscs1024.com/hd/MPS-2018-0362)|CVE-2017-17485|严重|
|Apache Hadoop 信息泄漏漏洞|未授权敏感信息泄露|[MPS-2018-0896](https://www.oscs1024.com/hd/MPS-2018-0896)|CVE-2017-15713|中危|
|FasterXML jackson-databind 反序列化漏洞(Hibernate/iBatis gadget绕过)||[MPS-2018-0934](https://www.oscs1024.com/hd/MPS-2018-0934)|CVE-2018-5968|高危|
|FasterXML Jackson-databind 反序列化漏洞(JdbcRowSetImpl gadget绕过)|反序列化|[MPS-2018-1438](https://www.oscs1024.com/hd/MPS-2018-1438)|CVE-2017-15095|严重|
|FasterXML Jackson-databind反序列化漏洞|反序列化|[MPS-2018-1439](https://www.oscs1024.com/hd/MPS-2018-1439)|CVE-2017-7525|严重|
|Apache Spark 授权问题漏洞|代码注入|[MPS-2018-14969](https://www.oscs1024.com/hd/MPS-2018-14969)|CVE-2018-17190|严重|
|FasterXML jackson-databind 反序列化漏洞(c3p0 gadget绕过)||[MPS-2018-2477](https://www.oscs1024.com/hd/MPS-2018-2477)|CVE-2018-7489|严重|
|Apache Derby 权限许可和访问控制问题漏洞|访问控制不当|[MPS-2018-5754](https://www.oscs1024.com/hd/MPS-2018-5754)|CVE-2018-1313|中危|
|Apache Zookeeper 访问控制错误漏洞|授权检查缺失|[MPS-2018-6313](https://www.oscs1024.com/hd/MPS-2018-6313)|CVE-2018-8012|高危|
|Bouncy Castle 数据伪造问题漏洞|密码学签名的验证不恰当|[MPS-2018-6849](https://www.oscs1024.com/hd/MPS-2018-6849)|CVE-2016-1000338|高危|
|Bouncy Castle AES 密钥信息泄露漏洞|密码学问题|[MPS-2018-6922](https://www.oscs1024.com/hd/MPS-2018-6922)|CVE-2016-1000339|中危|
|Bouncy Castle 签名信息泄露漏洞|7PK - 时间和状态|[MPS-2018-6924](https://www.oscs1024.com/hd/MPS-2018-6924)|CVE-2016-1000341|中危|
|Bouncy Castle <1.56 签名验证不当漏洞|密码学签名的验证不恰当|[MPS-2018-6925](https://www.oscs1024.com/hd/MPS-2018-6925)|CVE-2016-1000342|高危|
|Bouncy Castle 弱私钥漏洞|密码学问题|[MPS-2018-6926](https://www.oscs1024.com/hd/MPS-2018-6926)|CVE-2016-1000343|高危|
|Bouncy Castle 不安全加密漏洞|密码学问题|[MPS-2018-7042](https://www.oscs1024.com/hd/MPS-2018-7042)|CVE-2016-1000344|高危|
|Bouncy Castle 服务异常漏洞|7PK - 时间和状态|[MPS-2018-7043](https://www.oscs1024.com/hd/MPS-2018-7043)|CVE-2016-1000345|中危|
|Bouncy Castle 私钥信息泄露漏洞|密钥管理错误|[MPS-2018-7044](https://www.oscs1024.com/hd/MPS-2018-7044)|CVE-2016-1000346|低危|
|Bouncy Castle 不安全加密漏洞|密码学问题|[MPS-2018-7045](https://www.oscs1024.com/hd/MPS-2018-7045)|CVE-2016-1000352|高危|
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
|Apache Thrift <0.13.0 拒绝服务漏洞|不可达退出条件的循环（无限循环）|[MPS-2019-13876](https://www.oscs1024.com/hd/MPS-2019-13876)|CVE-2019-0205|高危|
|Apache Hadoop 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2019-1459](https://www.oscs1024.com/hd/MPS-2019-1459)|CVE-2018-1296|高危|
|jackson-mapper-asl <=1.9.13 XXE 注入漏洞|XXE|[MPS-2019-15048](https://www.oscs1024.com/hd/MPS-2019-15048)|CVE-2019-10172|高危|
|FasterXML Jackson-databind反序列化漏洞（Jodd-db gadget绕过）|反序列化|[MPS-2019-2619](https://www.oscs1024.com/hd/MPS-2019-2619)|CVE-2018-12022|高危|
|FasterXML Jackson-databind反序列化漏洞(Oracle JDBC driver gadget绕过)|反序列化|[MPS-2019-2620](https://www.oscs1024.com/hd/MPS-2019-2620)|CVE-2018-12023|高危|
|FasterXML jackson-databind 反序列化漏洞(mysql gadget绕过)|反序列化|[MPS-2019-5442](https://www.oscs1024.com/hd/MPS-2019-5442)|CVE-2019-12086|高危|
|Apache Zookeeper 授权问题漏洞|授权检查缺失|[MPS-2019-5668](https://www.oscs1024.com/hd/MPS-2019-5668)|CVE-2019-0201|中危|
|FasterXML jackson-databind 反序列化漏洞(jdom gadget绕过)|反序列化|[MPS-2019-6867](https://www.oscs1024.com/hd/MPS-2019-6867)|CVE-2019-12814|中危|
|FasterXML jackson-databind 反序列化漏洞(logback-classic gadget绕过)|反序列化|[MPS-2019-7047](https://www.oscs1024.com/hd/MPS-2019-7047)|CVE-2019-12384|中危|
|FasterXML jackson-databind 反序列化漏洞(iBatis gadget绕过)|反序列化|[MPS-2019-7711](https://www.oscs1024.com/hd/MPS-2019-7711)|CVE-2018-11307|严重|
|FasterXML jackson-databind 反序列化漏洞(ehcache gadget绕过)|动态确定对象属性修改的控制不恰当|[MPS-2019-8717](https://www.oscs1024.com/hd/MPS-2019-8717)|CVE-2019-14379|严重|
|FasterXML jackson-databind 信息泄露漏洞(logback gadget绕过)|反序列化|[MPS-2019-8770](https://www.oscs1024.com/hd/MPS-2019-8770)|CVE-2019-14439|高危|
|FasterXML jackson-databind反序列化漏洞(net.sf.ehcache gadget绕过)|反序列化|[MPS-2020-0063](https://www.oscs1024.com/hd/MPS-2020-0063)|CVE-2019-20330|严重|
|google-oauth-java-client <1.31.0授权不当漏洞|授权检查错误|[MPS-2020-10000](https://www.oscs1024.com/hd/MPS-2020-10000)|CVE-2020-7692|严重|
|FasterXML jackson-databind反序列化漏洞(Anteros-DBCP gadget绕过)|反序列化|[MPS-2020-11987](https://www.oscs1024.com/hd/MPS-2020-11987)|CVE-2020-24616|高危|
|FasterXML jackson-databind 反序列化漏洞(pastdev gadget绕过)|反序列化|[MPS-2020-13151](https://www.oscs1024.com/hd/MPS-2020-13151)|CVE-2020-24750|高危|
|Netty <=4.1.43.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1320](https://www.oscs1024.com/hd/MPS-2020-1320)|CVE-2020-7238|高危|
|Apache Hadoop授权问题漏洞|身份验证不当|[MPS-2020-13793](https://www.oscs1024.com/hd/MPS-2020-13793)|CVE-2018-11765|中危|
|Apache Calcite 访问控制错误漏洞|关键功能的认证机制缺失|[MPS-2020-14130](https://www.oscs1024.com/hd/MPS-2020-14130)|CVE-2020-13955|中危|
|Junit 信息泄露漏洞|不安全的临时文件|[MPS-2020-15183](https://www.oscs1024.com/hd/MPS-2020-15183)|CVE-2020-15250|中危|
|Netty <4.1.44.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1526](https://www.oscs1024.com/hd/MPS-2020-1526)|CVE-2019-20444|严重|
|Netty <4.1.44.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1527](https://www.oscs1024.com/hd/MPS-2020-1527)|CVE-2019-20445|严重|
|Eclipse Jetty 权限提升漏洞|权限、特权和访问控制|[MPS-2020-15633](https://www.oscs1024.com/hd/MPS-2020-15633)|CVE-2020-27216|高危|
|Bouncy Castle 私钥信息泄漏漏洞|通过差异性导致的信息暴露|[MPS-2020-16513](https://www.oscs1024.com/hd/MPS-2020-16513)|CVE-2020-26939|中危|
|Apache HttpClient URI解析错误漏洞|XSS|[MPS-2020-17341](https://www.oscs1024.com/hd/MPS-2020-17341)|CVE-2020-13956|中危|
|FasterXML jackson-databind 代码问题漏洞|XXE|[MPS-2020-17358](https://www.oscs1024.com/hd/MPS-2020-17358)|CVE-2020-25649|高危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
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
|FasterXML jackson-databind反序列化漏洞(aries.transaction.jms gadget绕过)|反序列化|[MPS-2020-4131](https://www.oscs1024.com/hd/MPS-2020-4131)|CVE-2020-10672|高危|
|FasterXML jackson-databind反序列化漏洞(caucho-quercus gadget绕过)|反序列化|[MPS-2020-4132](https://www.oscs1024.com/hd/MPS-2020-4132)|CVE-2020-10673|高危|
|FasterXML jackson-databind反序列化漏洞(bus-proxy gadget绕过)|反序列化|[MPS-2020-4658](https://www.oscs1024.com/hd/MPS-2020-4658)|CVE-2020-10968|高危|
|FasterXML jackson-databind反序列化漏洞(javax.swing gadget绕过)|反序列化|[MPS-2020-4659](https://www.oscs1024.com/hd/MPS-2020-4659)|CVE-2020-10969|高危|
|FasterXML jackson-databind反序列化漏洞(activemq gadget绕过)|反序列化|[MPS-2020-4754](https://www.oscs1024.com/hd/MPS-2020-4754)|CVE-2020-11111|高危|
|FasterXML jackson-databind反序列化漏洞(commons-proxy gadget绕过)|反序列化|[MPS-2020-4755](https://www.oscs1024.com/hd/MPS-2020-4755)|CVE-2020-11112|高危|
|FasterXML jackson-databind反序列化漏洞(openjpa gadget绕过)|反序列化|[MPS-2020-4756](https://www.oscs1024.com/hd/MPS-2020-4756)|CVE-2020-11113|高危|
|Netty ZlibDecoders 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2020-5127](https://www.oscs1024.com/hd/MPS-2020-5127)|CVE-2020-11612|高危|
|FasterXML jackson-databind 反序列化漏洞(spring-aop gadget绕过)|反序列化|[MPS-2020-5138](https://www.oscs1024.com/hd/MPS-2020-5138)|CVE-2020-11619|高危|
|FasterXML jackson-databind 反序列化漏洞(commons-jelly gadget绕过)|反序列化|[MPS-2020-5139](https://www.oscs1024.com/hd/MPS-2020-5139)|CVE-2020-11620|高危|
|FasterXML jackson-databind反序列化漏洞(oracle-aqjms gadget绕过)|反序列化|[MPS-2020-8801](https://www.oscs1024.com/hd/MPS-2020-8801)|CVE-2020-14061|高危|
|FasterXML jackson-databind反序列化漏洞(xalan2 gadget绕过)|反序列化|[MPS-2020-8802](https://www.oscs1024.com/hd/MPS-2020-8802)|CVE-2020-14062|高危|
|FasterXML jackson-databind反序列化漏洞(apache drill gadget绕过)|反序列化|[MPS-2020-8803](https://www.oscs1024.com/hd/MPS-2020-8803)|CVE-2020-14060|高危|
|FasterXML jackson-databind代码问题漏洞(jsecurity gadget绕过)|反序列化|[MPS-2020-8911](https://www.oscs1024.com/hd/MPS-2020-8911)|CVE-2020-14195|高危|
|Apache Spark 授权问题漏洞|关键功能的认证机制缺失|[MPS-2020-9387](https://www.oscs1024.com/hd/MPS-2020-9387)|CVE-2020-9480|严重|
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
|Eclipse Jetty 编码字符敏感信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-10800](https://www.oscs1024.com/hd/MPS-2021-10800)|CVE-2021-34429|中危|
|JetBrains Kotlin <1.4.21 不正确的默认权限漏洞|缺省权限不正确|[MPS-2021-1082](https://www.oscs1024.com/hd/MPS-2021-1082)|CVE-2020-29582|中危|
|Netty <4.1.59.Final 存在不安全的临时文件漏洞||[MPS-2021-1580](https://www.oscs1024.com/hd/MPS-2021-1580)|CVE-2021-21290|中危|
|Apache Thrift 资源管理错误漏洞|拒绝服务|[MPS-2021-1609](https://www.oscs1024.com/hd/MPS-2021-1609)|CVE-2020-13949|高危|
|FasterXML jackson-databind 反序列化漏洞(javax.swing gadget绕过)|反序列化|[MPS-2021-1625](https://www.oscs1024.com/hd/MPS-2021-1625)|CVE-2021-20190|高危|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|Google google-oauth-java-client 数据伪造问题漏洞|密码学签名的验证不恰当|[MPS-2021-19070](https://www.oscs1024.com/hd/MPS-2021-19070)|CVE-2021-22573|高危|
|netplex json-smart-v  分布式拒绝服务攻击|对因果或异常条件的不恰当检查|[MPS-2021-2102](https://www.oscs1024.com/hd/MPS-2021-2102)|CVE-2021-27568|严重|
|Netty Bzip2Decoder 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28116](https://www.oscs1024.com/hd/MPS-2021-28116)|CVE-2021-37136|高危|
|Netty 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28117](https://www.oscs1024.com/hd/MPS-2021-28117)|CVE-2021-37137|高危|
|Apache Commons Net <3.9.0 存在FTP跳转攻击漏洞|未授权敏感信息泄露|[MPS-2021-28440](https://www.oscs1024.com/hd/MPS-2021-28440)|CVE-2021-37533|中危|
|Apache Kafka 存在时序攻击漏洞|通过差异性导致的信息暴露|[MPS-2021-28892](https://www.oscs1024.com/hd/MPS-2021-28892)|CVE-2021-38153|中危|
|Eclipse Jetty 资源管理错误漏洞|对异常条件的处理不恰当|[MPS-2021-3864](https://www.oscs1024.com/hd/MPS-2021-3864)|CVE-2021-28165|高危|
|Eclipse Jetty <9.4.39.v20210325 权限绕过漏洞|授权检查错误|[MPS-2021-3877](https://www.oscs1024.com/hd/MPS-2021-3877)|CVE-2021-28164|中危|
|Bouncy Castle 私钥信息泄露漏洞|竞争条件|[MPS-2021-7064](https://www.oscs1024.com/hd/MPS-2021-7064)|CVE-2020-15522|中危|
|json-smart 存在拒绝服务漏洞|越界写入|[MPS-2021-7737](https://www.oscs1024.com/hd/MPS-2021-7737)|CVE-2021-31684|高危|
|JDOM 存在 XXE 注入漏洞|XXE|[MPS-2021-8350](https://www.oscs1024.com/hd/MPS-2021-8350)|CVE-2021-33813|高危|
|Eclipse Jetty 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-8397](https://www.oscs1024.com/hd/MPS-2021-8397)|CVE-2021-28169|中危|
|Eclipse Jetty 存在信息泄露漏洞|不充分的会话过期机制|[MPS-2021-8884](https://www.oscs1024.com/hd/MPS-2021-8884)|CVE-2021-34428|低危|
|jnr-posix 存在UAF漏洞|UAF|[MPS-2022-11743](https://www.oscs1024.com/hd/MPS-2022-11743)||低危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|org.glassfish.jersey.media:jersey-media-jaxb <2.31 存在XXE漏洞|XML实体扩展|[MPS-2022-12234](https://www.oscs1024.com/hd/MPS-2022-12234)||高危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|Apache HttpClient URI解析错误漏洞|相对路径遍历|[MPS-2022-12292](https://www.oscs1024.com/hd/MPS-2022-12292)||中危|
|Apache Hadoop < 2.7.3 存在CSRF漏洞|CSRF|[MPS-2022-12308](https://www.oscs1024.com/hd/MPS-2022-12308)||中危|
|com.fasterxml.jackson.core:jackson-databind 存在反序列化漏洞|反序列化|[MPS-2022-12433](https://www.oscs1024.com/hd/MPS-2022-12433)||高危|
|org.apache.hadoop:hadoop-hdfs < 3.3.2 存在XXE漏洞|XXE|[MPS-2022-12474](https://www.oscs1024.com/hd/MPS-2022-12474)||中危|
|org.apache.hadoop:hadoop-hdfs 存在信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-12484](https://www.oscs1024.com/hd/MPS-2022-12484)||高危|
|org.json:json 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13520](https://www.oscs1024.com/hd/MPS-2022-13520)||高危|
|Apache Spark XSS 漏洞|XSS|[MPS-2022-16687](https://www.oscs1024.com/hd/MPS-2022-16687)|CVE-2022-31777|中危|
|Eclipse Jetty URI注入漏洞|注入|[MPS-2022-18060](https://www.oscs1024.com/hd/MPS-2022-18060)|CVE-2022-2047|低危|
|Apache XercesJ <=2.12.1 存在XML注入漏洞|XPath盲注|[MPS-2022-1864](https://www.oscs1024.com/hd/MPS-2022-1864)|CVE-2022-23437|中危|
|JetBrains Kotlin <1.6.0 存在锁定不当漏洞|加锁机制不恰当|[MPS-2022-3233](https://www.oscs1024.com/hd/MPS-2022-3233)|CVE-2022-24329|中危|
|Netty 存在信息泄露漏洞||[MPS-2022-3790](https://www.oscs1024.com/hd/MPS-2022-3790)|CVE-2022-24823|中危|
|Apache Hadoop 存在shell命令注入漏洞|参数注入或修改|[MPS-2022-4190](https://www.oscs1024.com/hd/MPS-2022-4190)|CVE-2022-25168|严重|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|Apache Calcite Avatica 代码注入漏洞|代码注入|[MPS-2022-51965](https://www.oscs1024.com/hd/MPS-2022-51965)|CVE-2022-36364|高危|
|hazelcast 存在身份验证不当漏洞|身份验证不当|[MPS-2022-52086](https://www.oscs1024.com/hd/MPS-2022-52086)|CVE-2022-36437|高危|
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
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|Apache Hadoop 存在路径遍历漏洞|路径遍历|[MPS-2022-5920](https://www.oscs1024.com/hd/MPS-2022-5920)|CVE-2022-26612|严重|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|Apache IoTDB ReDos 漏洞|拒绝服务|[MPS-2022-60823](https://www.oscs1024.com/hd/MPS-2022-60823)|CVE-2022-43766|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|Apache MINA SSHD < 2.9.2 存在Java反序列化漏洞|反序列化|[MPS-2022-63954](https://www.oscs1024.com/hd/MPS-2022-63954)|CVE-2022-45047|高危|
|Jettison <1.5.2 拒绝服务漏洞|越界写入|[MPS-2022-64973](https://www.oscs1024.com/hd/MPS-2022-64973)|CVE-2022-45685|高危|
|Apache Ivy<2.5.2 存在XXE漏洞|输入验证不恰当|[MPS-2022-67125](https://www.oscs1024.com/hd/MPS-2022-67125)|CVE-2022-46751|中危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Apache Spark 权限提升漏洞|权限管理不当|[MPS-2023-0818](https://www.oscs1024.com/hd/MPS-2023-0818)|CVE-2023-22946|高危|
|Apache Kafka Connect 模块JNDI注入漏洞|反序列化|[MPS-2023-3834](https://www.oscs1024.com/hd/MPS-2023-3834)|CVE-2023-25194|高危|
|Eclipse Jetty 资源管理错误漏洞|拒绝服务|[MPS-2023-4997](https://www.oscs1024.com/hd/MPS-2023-4997)|CVE-2023-26048|中危|
|Eclipse Jetty 信息泄露漏洞|XSS|[MPS-2023-4998](https://www.oscs1024.com/hd/MPS-2023-4998)|CVE-2023-26049|中危|
|netplex json-smart 安全漏洞|未经控制的递归|[MPS-2023-7760](https://www.oscs1024.com/hd/MPS-2023-7760)|CVE-2023-1370|高危|
|Jettison 安全漏洞|未经控制的递归|[MPS-2023-8270](https://www.oscs1024.com/hd/MPS-2023-8270)|CVE-2023-1436|高危|
|Hazelcast 安全漏洞|凭证保护不足|[MPS-8wc3-pyfm](https://www.oscs1024.com/hd/MPS-8wc3-pyfm)|CVE-2023-33264|中危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|fasterxml jackson-dataformats-text越界写入漏洞|越界写入|[MPS-f9vd-7lu8](https://www.oscs1024.com/hd/MPS-f9vd-7lu8)|CVE-2023-3894|高危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.fasterxml.woodstox:woodstox-core|5.0.3|6.4.0|间接依赖|建议修复|C:0|H:3|M:1|L:1|
|org.apache.hadoop:hadoop-common|2.6.5|3.3.3|间接依赖|建议修复|C:2|H:0|M:1|L:0|
|org.xerial.snappy:snappy-java|1.1.7.1|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.xerial.snappy:snappy-java|1.1.7.7|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.apache.sshd:sshd-common|2.7.0|2.9.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.spark:spark-network-common_2.11|2.4.0|2.4.6|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.xerial.snappy:snappy-java|1.0.5|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.apache.calcite.avatica:avatica-core|1.17.0|1.22.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-codec|4.1.45.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|io.netty:netty|3.10.6.Final||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-all|4.1.17.Final|4.1.44.Final|间接依赖|建议修复|C:2|H:2|M:0|L:0|
|io.netty:netty-codec|4.1.60.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|net.minidev:json-smart|2.3|2.4.9|间接依赖|建议修复|C:1|H:2|M:0|L:0|
|net.minidev:json-smart|2.4.7|2.4.9|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|commons-beanutils:commons-beanutils|1.7.0|1.9.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-server|9.4.38.v20210224|12.0.0.beta0|间接依赖|建议修复|C:0|H:0|M:3|L:1|
|org.xerial.snappy:snappy-java|1.1.8.3|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|com.squareup.okio:okio|2.8.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.squareup.okio:okio|1.11.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-io|9.4.38.v20210224|11.0.10|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.60.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.xerial.snappy:snappy-java|1.1.1.3|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.apache.spark:spark-core_2.11|2.4.0||直接依赖|建议修复|C:1|H:1|M:1|L:0|
|org.eclipse.jetty:jetty-http|9.4.38.v20210224|11.0.10|间接依赖|建议修复|C:0|H:0|M:1|L:1|
|org.apache.commons:commons-compress|1.20|1.21|直接依赖|建议修复|C:0|H:4|M:0|L:0|
|org.apache.hadoop:hadoop-hdfs|2.6.5|3.3.2|间接依赖|建议修复|C:0|H:4|M:2|L:0|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13||间接依赖|建议修复|C:1|H:1|M:0|L:0|
|io.netty:netty|3.9.9.Final|3.10.3.Final|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.77.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|27.0-jre|32.0.0-jre|直接依赖|建议修复|C:0|H:0|M:1|L:1|
|org.apache.hadoop:hadoop-common|3.1.4|3.3.3|间接依赖|建议修复|C:2|H:0|M:0|L:0|
|com.google.protobuf:protobuf-java|2.4.1|3.21.7|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|com.squareup.okio:okio-jvm|3.0.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.squareup.okio:okio|1.6.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.6.7|2.14.0-rc1|直接依赖|建议修复|C:26|H:39|M:5|L:0|
|com.google.protobuf:protobuf-java|2.6.1|3.21.7|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|org.xerial.snappy:snappy-java|1.1.8.4|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.apache.hadoop:hadoop-common|2.9.2|3.3.3|间接依赖|建议修复|C:2|H:0|M:1|L:0|
|org.apache.kafka:kafka-clients|3.2.0|3.4.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.xerial.snappy:snappy-java|1.1.1.6|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.apache.hadoop:hadoop-common|2.10.0|3.3.3|间接依赖|建议修复|C:2|H:0|M:0|L:0|
|org.apache.zookeeper:zookeeper|3.4.6|3.5.5|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.glassfish.jersey.media:jersey-media-jaxb|2.22.2|2.31|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.30|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|com.hazelcast:hazelcast|5.1|5.3.0|直接依赖|建议修复|C:0|H:1|M:1|L:0|
|com.nimbusds:nimbus-jose-jwt|4.41.1|7.8.1|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.apache.kafka:kafka-clients|2.7.1|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.google.oauth-client:google-oauth-client|1.25.0|1.33.3|间接依赖|建议修复|C:1|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-webapp|9.4.20.v20190813|11.0.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.12.6|2.14.0-rc1|间接依赖|建议修复|C:0|H:1|M:3|L:0|
|com.google.protobuf:protobuf-java|2.5.0|3.21.7|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|io.netty:netty-handler|4.1.45.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|org.bouncycastle:bcprov-jdk15on|1.50|1.69|间接依赖|建议修复|C:0|H:5|M:7|L:1|
|org.codehaus.jettison:jettison|1.1|1.5.4|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|com.squareup.okio:okio|1.17.2|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.bouncycastle:bcprov-jdk15on|1.69||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.eclipse.jetty:jetty-servlets|9.4.38.v20210224|11.0.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.kafka:connect-runtime|2.7.1|2.8.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-httpclient:commons-httpclient|3.1||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.ivy:ivy|2.4.0|2.5.2|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|org.apache.thrift:libthrift|0.9.3|0.12.0|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|xerces:xercesImpl|2.9.1|2.12.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-http|4.1.77.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.httpcomponents:httpclient|4.5.6|4.5.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.github.jnr:jnr-posix|3.1.5|3.1.8|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.apache.httpcomponents:httpclient|4.3.5|4.5.13|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|com.fasterxml.jackson.dataformat:jackson-dataformat-properties|2.12.6|2.15.0|直接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.httpcomponents:httpclient|4.4.1|4.5.13|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.apache.httpcomponents:httpclient|4.5.2|4.5.13|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|io.netty:netty-transport-native-epoll|4.1.45.Final|4.1.59.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-net:commons-net|3.6|3.9.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|31.1-android|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-common|4.1.48.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.apache.httpcomponents:httpclient|4.5.10|4.5.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.derby:derby|10.12.1.1|10.14.2.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.code.gson:gson|2.2.4|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|junit:junit|4.12|4.13.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.code.gson:gson|2.8.8|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.hadoop:hadoop-mapreduce-client-app|2.6.5|2.7.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-common|4.1.60.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.jetbrains.kotlin:kotlin-stdlib|1.4.10|1.6.0|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.code.gson:gson|2.8.5|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|io.netty:netty-common|4.1.45.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|31.1-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.iotdb:tsfile|0.13.1|0.13.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.hadoop:hadoop-yarn-common|2.6.5|2.7.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.json:json|20170516|20180130|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|commons-net:commons-net|3.1|3.9.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.calcite:calcite-core|1.2.0-incubating|1.32.0|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.jdom:jdom|1.1||间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|678|Low|
|GPL-2.0|2|Medium|
|MPL-1.1|4|Low|
|自定义许可证|86|Low|
|BSD-3-Clause|21|Low|
|EPL-2.0|12|Low|
|MIT|21|Low|
|CDDL-1.1|18|Low|
|LGPL-2.1|8|Medium|
|EPL-1.0|3|Low|
|CDDL-1.0|2|Low|
|BSD-2-Clause|6|Low|
|WTFPL|1|Low|
|JSON|2|Low|
|MPL-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.amazon.redshift:redshift-jdbc42|2.1.0.9|直接依赖|maven|
|org.apache.hbase:hbase-procedure|2.4.9|间接依赖|maven|
|org.apache.commons:commons-configuration2|2.1.1|间接依赖|maven|
|org.apache.rocketmq:rocketmq-srvutil|4.9.4|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-common|3.1.4|间接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.9.13|间接依赖|maven|
|com.rabbitmq:amqp-client|5.9.0|直接依赖|maven|
|org.apache.parquet:parquet-column|1.10.1|间接依赖|maven|
|org.apache.hbase:hbase-logging|2.4.9|间接依赖|maven|
|org.codehaus.woodstox:stax2-api|3.1.4|间接依赖|maven|
|io.netty:netty-resolver|4.1.60.Final|间接依赖|maven|
|org.apache.parquet:parquet-common|1.12.3|间接依赖|maven|
|org.apache.thrift:libthrift|0.14.1|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|org.threeten:threetenbp|1.6.5|间接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.3.2|间接依赖|maven|
|org.apache.seatunnel:imap-storage-api|2.3.3-SNAPSHOT|直接依赖|maven|
|org.apache.curator:curator-framework|2.7.1|间接依赖|maven|
|org.apache.hbase:hbase-replication|2.4.9|间接依赖|maven|
|org.apache.hbase:hbase-client|2.4.10|直接依赖|maven|
|org.apache.calcite:calcite-linq4j|1.2.0-incubating|间接依赖|maven|
|org.apache.hbase:hbase-metrics-api|2.4.10|间接依赖|maven|
|org.apache.seatunnel:seatunnel-api|2.3.3-SNAPSHOT|直接依赖|maven|
|io.grpc:grpc-services|1.52.1|间接依赖|maven|
|org.apache.seatunnel:seatunnel-starter|2.3.3-SNAPSHOT|直接依赖|maven|
|org.apache.seatunnel:connector-http-base|2.3.3-SNAPSHOT|直接依赖|maven|
|org.apache.seatunnel:imap-storage-file|2.3.3-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.9.10|间接依赖|maven|
|org.glassfish.hk2.external:aopalliance-repackaged|2.6.1|间接依赖|maven|
|org.apache.spark:spark-kvstore_2.11|2.4.0|间接依赖|maven|
|com.github.jnr:jnr-x86asm|1.0.2|间接依赖|maven|
|org.apache.seatunnel:connector-file-base-hadoop|2.3.3-SNAPSHOT|直接依赖|maven|
|org.apache.hbase:hbase-asyncfs|2.4.9|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|2.10.0|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|org.jruby.joni:joni|2.1.31|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.1|间接依赖|maven|
|com.squareup.retrofit2:retrofit|2.9.0|间接依赖|maven|
|org.testcontainers:jdbc|1.17.6|间接依赖|maven|
|org.glassfish.hk2:hk2-api|2.4.0-b34|间接依赖|maven|
|com.sun.jersey:jersey-core|1.19|间接依赖|maven|
|io.netty:netty|3.9.9.Final|间接依赖|maven|
|com.google.guava:guava|31.1-jre|直接依赖|maven|
|org.apache.derby:derby|10.12.1.1|间接依赖|maven|
|commons-beanutils:commons-beanutils-core|1.8.0|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-jobclient|2.6.5|间接依赖|maven|
|org.apache.curator:curator-client|2.6.0|间接依赖|maven|
|io.netty:netty-common|4.1.48.Final|间接依赖|maven|
|com.google.guava:guava|31.1-android|直接依赖|maven|
|org.apache.parquet:parquet-column|1.10.0|间接依赖|maven|
|org.fusesource.leveldbjni:leveldbjni-all|1.8|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.13|间接依赖|maven|
|org.ow2.asm:asm-tree|9.1|间接依赖|maven|
|javax.servlet.jsp:jsp-api|2.1|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.5.31|间接依赖|maven|
|io.opencensus:opencensus-contrib-http-util|0.31.1|间接依赖|maven|
|org.apache.zookeeper:zookeeper-jute|3.5.7|间接依赖|maven|
|com.clickhouse:clickhouse-http-client|0.3.2-patch11|直接依赖|maven|
|org.apache.seatunnel:seatunnel-plugin-discovery|2.3.3-SNAPSHOT|直接依赖|maven|
|org.apache.orc:orc-core|1.6.0|间接依赖|maven|
|org.apache.flink:flink-table-api-java-bridge_2.11|1.13.6|间接依赖|maven|
|io.sentry:sentry|5.0.1|间接依赖|maven|
|org.apache.curator:curator-recipes|2.6.0|间接依赖|maven|
|com.google.http-client:google-http-client|1.40.1|间接依赖|maven|
|org.apache.parquet:parquet-encoding|1.10.0|间接依赖|maven|
|io.grpc:grpc-context|1.52.1|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|2.10.0|间接依赖|maven|
|commons-codec:commons-codec|1.13|直接依赖|maven|
|org.apache.seatunnel:checkpoint-storage-api|2.3.3-SNAPSHOT|直接依赖|maven|
|org.apache.kerby:kerb-common|1.0.1|间接依赖|maven|
|org.javassist:javassist|3.24.0-GA|间接依赖|maven|
|xerces:xercesImpl|2.9.1|间接依赖|maven|
|com.google.http-client:google-http-client-gson|1.42.3|间接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5-h2|5.1.1|间接依赖|maven|
|io.netty:netty-buffer|4.1.77.Final|间接依赖|maven|
|org.roaringbitmap:shims|0.9.22|间接依赖|maven|
|org.apache.htrace:htrace-core4|4.1.0-incubating|间接依赖|maven|
|org.apache.iceberg:iceberg-common|0.14.0|间接依赖|maven|
|org.glassfish.hk2:hk2-locator|2.4.0-b34|间接依赖|maven|
|io.netty:netty-all|4.1.17.Final|间接依赖|maven|
|org.apache.rocketmq:rocketmq-logging|4.9.4|间接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|3.0.2|间接依赖|maven|
|com.sun.jersey:jersey-server|1.9|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.1|直接依赖|maven|
|org.apache.kafka:kafka-clients|2.7.1|间接依赖|maven|
|com.4paradigm.openmldb:openmldb-jdbc|0.6.3|直接依赖|maven|
|com.aliyun:aliyun-java-sdk-core|3.4.0|间接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.4.20.v20190813|间接依赖|maven|
|org.apache.flink:flink-table-planner-blink_2.11|1.13.6|直接依赖|maven|
|io.grpc:grpc-netty-shaded|1.52.1|间接依赖|maven|
|com.twitter:chill_2.11|0.7.6|间接依赖|maven|
|software.amazon.awssdk:metrics-spi|2.18.1|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.4|间接依赖|maven|
|org.glassfish.hk2.external:javax.inject|2.4.0-b34|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-client|2.6.5|间接依赖|maven|
|com.github.rholder:guava-retrying|2.0.0|直接依赖|maven|
|org.json4s:json4s-scalap_2.11|3.5.3|间接依赖|maven|
|org.apache.seatunnel:seatunnel-engine-client|2.3.3-SNAPSHOT|直接依赖|maven|
|org.antlr:ST4|4.0.4|间接依赖|maven|
|org.apache.flink:flink-table-common|1.13.6|间接依赖|maven|
|org.apache.hadoop:hadoop-common|2.6.5|间接依赖|maven|
|org.apache.flink:flink-connector-base|1.13.6|间接依赖|maven|
|com.sun.xml.bind:jaxb-core|2.2.7|间接依赖|maven|
|org.apache.arrow:arrow-memory-netty|5.0.0|直接依赖|maven|
|org.apache.htrace:htrace-core4|4.2.0-incubating|间接依赖|maven|
|org.apache.hbase.thirdparty:hbase-shaded-protobuf|3.5.1|间接依赖|maven|
|io.netty:netty-transport|4.1.77.Final|间接依赖|maven|
|io.netty:netty-handler|4.1.45.Final|间接依赖|maven|
|org.apache.hbase:hbase-server|2.4.9|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.1|间接依赖|maven|
|com.github.jnr:jnr-a64asm|1.0.0|间接依赖|maven|
|org.apache.orc:orc-shims|1.7.5|间接依赖|maven|
|org.codehaus.plexus:plexus-utils|3.2.1|间接依赖|maven|
|com.typesafe:ssl-config-core_2.11|0.3.7|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.2|间接依赖|maven|
|org.apache.hbase.thirdparty:hbase-shaded-jetty|3.5.1|间接依赖|maven|
|com.squareup.moshi:moshi|1.8.0|间接依赖|maven|
|org.codehaus.jackson:jackson-jaxrs|1.8.3|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.10.5|间接依赖|maven|
|org.apache.arrow:arrow-vector|5.0.0|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.4|直接依赖|maven|
|org.apache.hudi:hudi-common|0.11.1|间接依赖|maven|
|com.github.jnr:jnr-ffi|2.2.2|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.0|间接依赖|maven|
|com.aliyun.oss:aliyun-sdk-oss|3.0.0|间接依赖|maven|
|javax.ws.rs:jsr311-api|1.1.1|间接依赖|maven|
|org.scala-lang.modules:scala-parser-combinators_2.11|1.0.4|间接依赖|maven|
|com.datastax.oss:java-driver-shaded-guava|25.1-jre-graal-sub-1|间接依赖|maven|
|javax.ws.rs:javax.ws.rs-api|2.0.1|间接依赖|maven|
|org.codehaus.jackson:jackson-xc|1.9.13|间接依赖|maven|
|org.apache.pulsar:bouncy-castle-bc|2.11.0|间接依赖|maven|
|com.clickhouse:clickhouse-client|0.3.2-patch11|间接依赖|maven|
|org.apache.seatunnel:seatunnel-config-shade|2.3.3-SNAPSHOT|直接依赖|maven|
|org.apache.pulsar:pulsar-client-admin-api|2.11.0|间接依赖|maven|
|org.apache.hbase:hbase-metrics|2.4.10|间接依赖|maven|
|org.apache.calcite:calcite-avatica|1.2.0-incubating|间接依赖|maven|
|org.apache.parquet:parquet-jackson|1.12.3|间接依赖|maven|
|org.apache.seatunnel:serializer-protobuf|2.3.3-SNAPSHOT|直接依赖|maven|
|org.apache.hbase:hbase-metrics-api|2.4.9|间接依赖|maven|
|org.apache.spark:spark-catalyst_2.11|2.4.0|间接依赖|maven|
|org.codehaus.jackson:jackson-xc|1.8.3|间接依赖|maven|
|io.airlift:security|206|直接依赖|maven|
|org.apache.kerby:kerb-client|1.0.1|间接依赖|maven|
|commons-validator:commons-validator|1.7|间接依赖|maven|
|org.apache.sshd:sshd-core|2.7.0|间接依赖|maven|
|org.apache.poi:poi-ooxml|4.1.2|直接依赖|maven|
|org.apache.orc:orc-mapreduce|1.5.2|间接依赖|maven|
|org.apache.seatunnel:connector-assert|2.3.3-SNAPSHOT|直接依赖|maven|
|org.apache.hbase:hbase-hadoop2-compat|2.4.9|间接依赖|maven|
|io.grpc:grpc-core|1.52.1|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|com.google.api:api-common|2.6.0|间接依赖|maven|
|org.codehaus.jettison:jettison|1.1|间接依赖|maven|
|org.apache.hadoop:hadoop-auth|3.1.4|间接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|org.apache.kafka:connect-runtime|2.7.1|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.2|间接依赖|maven|
|com.squareup.okio:okio|1.11.0|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-common|2.6.5|间接依赖|maven|
|org.apache.xmlbeans:xmlbeans|3.1.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.5.31|间接依赖|maven|
|org.mongodb:mongodb-driver-core|4.7.1|直接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|net.sf.opencsv:opencsv|2.3|间接依赖|maven|
|org.apache.parquet:parquet-format-structures|1.12.3|间接依赖|maven|
|com.squareup.okhttp3:logging-interceptor|4.9.0|间接依赖|maven|
|io.sentry:sentry-logback|5.0.1|直接依赖|maven|
|org.apache.seatunnel:seatunnel-flink-starter-common|2.3.3-SNAPSHOT|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.14|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|2.6.5|间接依赖|maven|
|com.google.auth:google-auth-library-oauth2-http|1.15.0|间接依赖|maven|
|org.apache.parquet:parquet-encoding|1.12.3|间接依赖|maven|
|net.minidev:accessors-smart|1.2|间接依赖|maven|
|org.apache.kafka:connect-json|3.2.0|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.4.0|间接依赖|maven|
|org.datanucleus:datanucleus-rdbms|3.2.9|间接依赖|maven|
|org.apache.hbase:hbase-logging|2.4.10|间接依赖|maven|
|org.apache.flink:flink-scala_2.11|1.13.6|间接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.4.38.v20210224|间接依赖|maven|
|org.java-websocket:Java-WebSocket|1.5.2|间接依赖|maven|
|com.jcraft:jsch|0.1.54|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.17|间接依赖|maven|
|org.lz4:lz4-java|1.6.0|间接依赖|maven|
|org.apache.flink:flink-table-api-java|1.13.6|间接依赖|maven|
|com.google.inject:guice|3.0|间接依赖|maven|
|org.apache.flink:flink-table-api-scala-bridge_2.11|1.13.6|间接依赖|maven|
|net.minidev:json-smart|2.4.7|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-core|2.10.0|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.10.5|间接依赖|maven|
|org.apache.hadoop:hadoop-client|2.6.5|间接依赖|maven|
|org.glassfish.hk2.external:aopalliance-repackaged|2.4.0-b34|间接依赖|maven|
|org.eclipse.jetty:jetty-util-ajax|9.4.38.v20210224|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|3.1.5|间接依赖|maven|
|org.apache.kerby:kerby-config|1.0.1|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.16.3|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.10|间接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|4.41.1|间接依赖|maven|
|org.apache.seatunnel:seatunnel-engine-core|2.3.3-SNAPSHOT|直接依赖|maven|
|org.apache.flink:flink-runtime_2.11|1.13.6|间接依赖|maven|
|org.eclipse.jetty:jetty-client|9.4.38.v20210224|间接依赖|maven|
|com.google.api:gax-grpc|2.23.0|间接依赖|maven|
|commons-net:commons-net|3.1|间接依赖|maven|
|com.squareup.okhttp3:okhttp|4.10.0|间接依赖|maven|
|org.apache.seatunnel:seatunnel-format-compatible-debezium-json|2.3.3-SNAPSHOT|直接依赖|maven|
|org.antlr:antlr4-runtime|4.7|间接依赖|maven|
|org.apache.hbase:hbase-hadoop-compat|2.4.9|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.12.6|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.4.10|间接依赖|maven|
|org.apache.hbase:hbase-common|2.4.10|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet-core|2.31|间接依赖|maven|
|software.amazon.awssdk:endpoints-spi|2.18.1|间接依赖|maven|
|commons-configuration:commons-configuration|1.6|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-ecs|4.2.0|间接依赖|maven|
|org.apache.iceberg:iceberg-data|0.14.0|直接依赖|maven|
|org.apache.seatunnel:seatunnel-translation-flink-13|2.3.3-SNAPSHOT|直接依赖|maven|
|org.apache.commons:commons-math3|3.6.1|间接依赖|maven|
|org.aspectj:aspectjrt|1.8.2|间接依赖|maven|
|com.beust:jcommander|1.81|直接依赖|maven|
|org.bouncycastle:bcutil-jdk15on|1.69|间接依赖|maven|
|com.aliyun.datahub:aliyun-sdk-datahub|2.19.0-public|直接依赖|maven|
|org.apache.kerby:kerby-asn1|1.0.1|间接依赖|maven|
|antlr:antlr|2.7.7|间接依赖|maven|
|org.datanucleus:datanucleus-api-jdo|3.2.6|间接依赖|maven|
|org.apache.kafka:kafka-clients|3.2.0|直接依赖|maven|
|org.apache.parquet:parquet-hadoop-bundle|1.10.1|间接依赖|maven|
|io.debezium:debezium-core|1.6.4.Final|间接依赖|maven|
|org.antlr:antlr4-runtime|4.8|间接依赖|maven|
|org.mongodb:bson|4.7.1|直接依赖|maven|
|io.netty:netty-handler|4.1.77.Final|间接依赖|maven|
|org.apache.flink:flink-streaming-java_2.11|1.13.6|直接依赖|maven|
|org.apache.iceberg:iceberg-parquet|0.14.0|直接依赖|maven|
|com.aliyun:aliyun-java-sdk-sts|3.0.0|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.2|间接依赖|maven|
|org.apache.kerby:token-provider|1.0.1|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.9.3|间接依赖|maven|
|com.google.http-client:google-http-client-jackson2|1.25.0|间接依赖|maven|
|org.apache.flink:flink-connector-files|1.13.6|间接依赖|maven|
|org.glassfish.hk2:hk2-api|2.6.1|间接依赖|maven|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13|间接依赖|maven|
|com.sun.jersey:jersey-client|1.19|间接依赖|maven|
|com.google.inject.extensions:guice-servlet|3.0|间接依赖|maven|
|org.scala-lang:scala-compiler|2.11.12|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-common|2.6.5|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.69|间接依赖|maven|
|org.apache.spark:spark-streaming_2.11|2.4.0|直接依赖|maven|
|joda-time:joda-time|2.9.3|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|间接依赖|maven|
|org.scala-lang:scala-reflect|2.11.8|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.6|间接依赖|maven|
|io.netty:netty-codec|4.1.77.Final|间接依赖|maven|
|org.mortbay.jetty:jetty-sslengine|6.1.26|间接依赖|maven|
|io.airlift:aircompressor|0.15|间接依赖|maven|
|org.datanucleus:datanucleus-core|3.2.10|间接依赖|maven|
|io.netty:netty-resolver|4.1.45.Final|间接依赖|maven|
|org.apache.hbase.thirdparty:hbase-shaded-miscellaneous|3.5.1|间接依赖|maven|
|org.apache.kerby:kerb-admin|1.0.1|间接依赖|maven|
|com.hazelcast:hazelcast|5.1|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.12.6|间接依赖|maven|
|org.apache.seatunnel:seatunnel-guava|2.3.3-SNAPSHOT|直接依赖|maven|
|org.glassfish.jersey.inject:jersey-hk2|2.31|间接依赖|maven|
|org.apache.arrow:arrow-memory|0.10.0|间接依赖|maven|
|org.apache.parquet:parquet-jackson|1.10.0|间接依赖|maven|
|org.apache.rocketmq:rocketmq-common|4.9.4|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|org.apache.flink:flink-shaded-asm-7|7.1-13.0|间接依赖|maven|
|io.protostuff:protostuff-core|1.8.0|直接依赖|maven|
|io.netty:netty-buffer|4.1.60.Final|间接依赖|maven|
|org.apache.seatunnel:connector-fake|2.3.3-SNAPSHOT|直接依赖|maven|
|org.apache.seatunnel:checkpoint-storage-hdfs|2.3.3-SNAPSHOT|直接依赖|maven|
|org.javassist:javassist|3.18.1-GA|间接依赖|maven|
|org.spark-project.hive:hive-exec|1.2.1.spark2|间接依赖|maven|
|org.apache.seatunnel:seatunnel-core-starter|2.3.3-SNAPSHOT|直接依赖|maven|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|org.apache.sshd:sshd-scp|2.7.0|直接依赖|maven|
|io.netty:netty-codec|4.1.60.Final|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.3.5|间接依赖|maven|
|org.apache.kafka:kafka-tools|2.7.1|间接依赖|maven|
|org.apache.flink:flink-java|1.13.6|直接依赖|maven|
|com.twitter:chill-java|0.7.6|间接依赖|maven|
|com.github.spotbugs:spotbugs-annotations|3.1.12|间接依赖|maven|
|org.apache.flink:flink-annotations|1.13.6|间接依赖|maven|
|io.debezium:debezium-connector-mysql|1.6.4.Final|直接依赖|maven|
|org.clapper:grizzled-slf4j_2.11|1.3.2|间接依赖|maven|
|org.apache.commons:commons-math3|3.1.1|间接依赖|maven|
|com.google.code.gson:gson|2.9.1|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.4.0-b180830.0359|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet|2.22.2|间接依赖|maven|
|org.eclipse.jetty:jetty-webapp|9.4.20.v20190813|间接依赖|maven|
|org.apache.iotdb:tsfile|0.13.1|间接依赖|maven|
|org.testcontainers:mysql|1.17.6|直接依赖|maven|
|com.google.code.findbugs:jsr305|1.3.9|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.2.7|间接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j-impl|2.17.1|直接依赖|maven|
|org.apache.kudu:kudu-client|1.11.1|直接依赖|maven|
|org.scala-lang:scala-library|2.11.12|直接依赖|maven|
|org.apache.rocketmq:rocketmq-client|4.9.4|直接依赖|maven|
|org.apache.commons:commons-crypto|1.0.0|间接依赖|maven|
|software.amazon.awssdk:aws-core|2.18.1|间接依赖|maven|
|commons-httpclient:commons-httpclient|3.1|间接依赖|maven|
|org.iq80.snappy:snappy|0.2|间接依赖|maven|
|org.apache.hudi:hudi-hadoop-mr-bundle|0.11.1|直接依赖|maven|
|com.google.auto.value:auto-value-annotations|1.8.2|间接依赖|maven|
|software.amazon.awssdk:third-party-jackson-core|2.18.1|间接依赖|maven|
|io.netty:netty-buffer|4.1.48.Final|间接依赖|maven|
|org.apache.directory.api:api-util|1.0.0-M20|间接依赖|maven|
|org.apache.flink:flink-core|1.13.6|间接依赖|maven|
|org.apache.yetus:audience-annotations|0.13.0|间接依赖|maven|
|org.apache.seatunnel:seatunnel-flink-13-starter|2.3.3-SNAPSHOT|直接依赖|maven|
|software.amazon.awssdk:regions|2.18.1|间接依赖|maven|
|net.minidev:accessors-smart|2.4.7|间接依赖|maven|
|software.amazon.eventstream:eventstream|1.0.1|间接依赖|maven|
|org.apache.flink:flink-runtime-web_2.11|1.13.6|直接依赖|maven|
|com.google.re2j:re2j|1.1|间接依赖|maven|
|org.apache.hadoop:hadoop-aliyun|2.9.2|直接依赖|maven|
|org.apache.pulsar:pulsar-client-api|2.11.0|间接依赖|maven|
|com.github.stephenc.jcip:jcip-annotations|1.0-1|间接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.4|间接依赖|maven|
|org.apache.seatunnel:connector-console|2.3.3-SNAPSHOT|直接依赖|maven|
|com.typesafe.akka:akka-protobuf_2.11|2.5.21|间接依赖|maven|
|org.eclipse.jetty:jetty-security|9.4.38.v20210224|间接依赖|maven|
|com.google.api:gax|2.23.0|间接依赖|maven|
|org.apache.seatunnel:seatunnel-format-json|2.3.3-SNAPSHOT|直接依赖|maven|
|org.glassfish.hk2:hk2-utils|2.6.1|间接依赖|maven|
|org.apache.seatunnel:seatunnel-spark-starter-common|2.3.3-SNAPSHOT|直接依赖|maven|
|org.apache.kerby:kerby-pkix|1.0.1|间接依赖|maven|
|org.apache.kafka:connect-api|3.2.0|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.0.5|间接依赖|maven|
|org.scala-lang.modules:scala-parser-combinators_2.11|1.1.0|间接依赖|maven|
|org.apache.kafka:connect-api|2.7.1|间接依赖|maven|
|com.google.code.gson:gson|2.2.4|间接依赖|maven|
|com.alibaba:fastjson|1.2.83|间接依赖|maven|
|io.protostuff:protostuff-runtime|1.8.0|直接依赖|maven|
|org.glassfish.jersey.core:jersey-client|2.22.2|间接依赖|maven|
|org.apache.curator:curator-recipes|2.13.0|间接依赖|maven|
|com.datastax.oss:java-driver-core|4.14.0|直接依赖|maven|
|com.squareup.okhttp3:mockwebserver|3.6.0|直接依赖|maven|
|com.google.protobuf:protobuf-java|2.6.1|间接依赖|maven|
|org.apache.spark:spark-core_2.11|2.4.0|直接依赖|maven|
|org.apache.seatunnel:connector-file-ftp|2.3.3-SNAPSHOT|直接依赖|maven|
|com.google.api-client:google-api-client|1.25.0|间接依赖|maven|
|software.amazon.awssdk:http-client-spi|2.18.1|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|3.2.6|间接依赖|maven|
|org.apache.directory.server:apacheds-i18n|2.0.0-M15|间接依赖|maven|
|org.apache.spark:spark-sql_2.11|2.4.0|直接依赖|maven|
|com.ning:compress-lzf|1.0.3|间接依赖|maven|
|com.google.http-client:google-http-client|1.42.3|间接依赖|maven|
|software.amazon.awssdk:sdk-core|2.18.1|间接依赖|maven|
|com.github.jnr:jnr-constants|0.10.1|间接依赖|maven|
|com.esotericsoftware.minlog:minlog|1.2|间接依赖|maven|
|software.amazon.awssdk:profiles|2.18.1|间接依赖|maven|
|org.apache.seatunnel:seatunnel-format-compatible-connect-json|2.3.3-SNAPSHOT|直接依赖|maven|
|org.apache.seatunnel:seatunnel-translation-base|2.3.3-SNAPSHOT|直接依赖|maven|
|com.google.re2j:re2j|1.6|间接依赖|maven|
|javax.ws.rs:javax.ws.rs-api|2.1.1|间接依赖|maven|
|org.hamcrest:hamcrest-core|1.3|间接依赖|maven|
|org.apache.parquet:parquet-hadoop|1.12.3|间接依赖|maven|
|org.apache.arrow:arrow-memory-core|5.0.0|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-scala_2.11|2.6.7.1|间接依赖|maven|
|com.slack.api:slack-api-model|1.25.0|间接依赖|maven|
|org.json4s:json4s-ast_2.11|3.5.3|间接依赖|maven|
|org.conscrypt:conscrypt-openjdk-uber|2.5.2|间接依赖|maven|
|net.sourceforge.argparse4j:argparse4j|0.7.0|间接依赖|maven|
|com.aliyun.openservices:tablestore|5.13.9|直接依赖|maven|
|org.apache.flink:flink-table-runtime-blink_2.11|1.13.6|间接依赖|maven|
|org.apache.spark:spark-network-shuffle_2.11|2.4.0|间接依赖|maven|
|org.apache.avro:avro|1.7.7|间接依赖|maven|
|net.jpountz.lz4:lz4|1.3.0|直接依赖|maven|
|org.apache.parquet:parquet-column|1.12.3|间接依赖|maven|
|io.netty:netty-transport|4.1.60.Final|间接依赖|maven|
|org.apache.maven:maven-artifact|3.6.3|间接依赖|maven|
|org.apache.hadoop:hadoop-auth|2.6.5|间接依赖|maven|
|io.netty:netty|3.10.6.Final|间接依赖|maven|
|org.apache.hbase:hbase-hadoop-compat|2.4.10|间接依赖|maven|
|org.apache.hbase:hbase-protocol|2.4.9|间接依赖|maven|
|org.apache.hbase:hbase-protocol|2.4.10|间接依赖|maven|
|org.apache.commons:commons-collections4|4.4|直接依赖|maven|
|com.sun.jersey:jersey-core|1.9|间接依赖|maven|
|org.apache.parquet:parquet-common|1.10.1|间接依赖|maven|
|com.google.code.gson:gson|2.8.8|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.77.Final|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.7.0|间接依赖|maven|
|javax.servlet:javax.servlet-api|3.1.0|间接依赖|maven|
|oro:oro|2.0.8|间接依赖|maven|
|org.apache.spark:spark-network-common_2.11|2.4.0|间接依赖|maven|
|org.apache.flink:flink-queryable-state-client-java|1.13.6|间接依赖|maven|
|io.grpc:grpc-googleapis|1.52.1|间接依赖|maven|
|com.twitter:parquet-hadoop-bundle|1.6.0|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.9.1|间接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-client|7.5.1|直接依赖|maven|
|org.influxdb:influxdb-java|2.21|直接依赖|maven|
|org.apache.seatunnel:seatunnel-translation-spark-3.3|2.3.3-SNAPSHOT|直接依赖|maven|
|org.apache.seatunnel:serializer-api|2.3.3-SNAPSHOT|直接依赖|maven|
|org.apache.seatunnel:connector-common|2.3.3-SNAPSHOT|直接依赖|maven|
|io.debezium:debezium-api|1.6.4.Final|直接依赖|maven|
|com.stumbleupon:async|1.4.1|间接依赖|maven|
|com.squareup.retrofit2:converter-moshi|2.9.0|间接依赖|maven|
|org.glassfish.web:javax.servlet.jsp|2.3.2|间接依赖|maven|
|org.apache.spark:spark-unsafe_2.11|2.4.0|间接依赖|maven|
|software.amazon.awssdk:dynamodb|2.18.1|直接依赖|maven|
|org.apache.curator:curator-client|2.7.1|间接依赖|maven|
|com.google.auth:google-auth-library-credentials|1.15.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.12.6|间接依赖|maven|
|org.lz4:lz4-java|1.4.0|间接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.12|间接依赖|maven|
|org.apache.seatunnel:connector-cdc-base|2.3.3-SNAPSHOT|直接依赖|maven|
|org.apache.parquet:parquet-hadoop|1.10.0|间接依赖|maven|
|org.apache.pulsar:pulsar-client-all|2.11.0|直接依赖|maven|
|org.apache.avro:avro|1.10.2|直接依赖|maven|
|org.apache.hadoop:hadoop-auth|2.10.0|间接依赖|maven|
|org.apache.hive:hive-storage-api|2.6.0|间接依赖|maven|
|org.apache.commons:commons-math3|3.5|间接依赖|maven|
|commons-pool:commons-pool|1.5.4|间接依赖|maven|
|org.apache.seatunnel:seatunnel-jackson|2.3.3-SNAPSHOT|直接依赖|maven|
|com.4paradigm.openmldb:openmldb-native|0.6.3|直接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.25|直接依赖|maven|
|com.google.code.gson:gson|2.8.5|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.5.7|间接依赖|maven|
|io.grpc:grpc-alts|1.52.1|间接依赖|maven|
|com.sun.istack:istack-commons-runtime|4.0.1|间接依赖|maven|
|com.sun.activation:jakarta.activation|2.0.1|间接依赖|maven|
|commons-net:commons-net|3.6|间接依赖|maven|
|org.roaringbitmap:RoaringBitmap|0.9.22|间接依赖|maven|
|org.scala-lang.modules:scala-java8-compat_2.11|0.7.0|间接依赖|maven|
|org.apache.paimon:paimon-bundle|0.4.0-incubating|直接依赖|maven|
|org.apache.hbase:hbase-metrics|2.4.9|间接依赖|maven|
|io.netty:netty-all|4.1.65.Final|间接依赖|maven|
|javax.xml.stream:stax-api|1.0-2|间接依赖|maven|
|software.amazon.awssdk:json-utils|2.18.1|间接依赖|maven|
|org.apache.hadoop:hadoop-client|3.1.4|直接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.38.v20210224|间接依赖|maven|
|net.sourceforge.javacsv:javacsv|2.0|间接依赖|maven|
|com.google.code.gson:gson|2.8.9|间接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|com.univocity:univocity-parsers|2.7.3|间接依赖|maven|
|commons-digester:commons-digester|2.1|间接依赖|maven|
|com.google.api.grpc:proto-google-cloud-firestore-v1|3.7.10|间接依赖|maven|
|org.mongodb:bson-record-codec|4.7.1|间接依赖|maven|
|org.apache.kerby:kerby-xdr|1.0.1|间接依赖|maven|
|org.glassfish.hk2:hk2-locator|2.6.1|间接依赖|maven|
|org.apache.seatunnel:seatunnel-translation-flink-15|2.3.3-SNAPSHOT|直接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-jobclient|3.1.4|间接依赖|maven|
|commons-lang:commons-lang|2.6|间接依赖|maven|
|com.sun.istack:istack-commons-runtime|2.16|间接依赖|maven|
|org.apache.parquet:parquet-jackson|1.10.1|间接依赖|maven|
|org.apache.hadoop:hadoop-common|2.10.0|间接依赖|maven|
|io.dropwizard.metrics:metrics-graphite|3.1.5|间接依赖|maven|
|org.eclipse.jetty:jetty-security|9.4.20.v20190813|间接依赖|maven|
|org.apache.hive:hive-storage-api|2.8.1|间接依赖|maven|
|org.spark-project.spark:unused|1.0.0|间接依赖|maven|
|com.jayway.jsonpath:json-path|2.7.0|直接依赖|maven|
|com.carrotsearch:hppc|0.7.2|间接依赖|maven|
|com.google.code.gson:gson|2.9.0|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|4.1.18|间接依赖|maven|
|org.mortbay.jetty:jetty-util|6.1.26|间接依赖|maven|
|org.apache.spark:spark-hive_2.11|2.4.0|直接依赖|maven|
|org.apache.flink:flink-metrics-core|1.13.6|间接依赖|maven|
|net.hydromatic:eigenbase-properties|1.1.5|间接依赖|maven|
|org.apache.spark:spark-tags_2.11|2.4.0|间接依赖|maven|
|com.typesafe.akka:akka-actor_2.11|2.5.21|间接依赖|maven|
|org.apache.curator:curator-framework|2.6.0|间接依赖|maven|
|org.apache.flink:flink-shaded-zookeeper-3|3.4.14-13.0|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.0-1|间接依赖|maven|
|org.apache.poi:poi|4.1.2|直接依赖|maven|
|io.opencensus:opencensus-contrib-http-util|0.28.0|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.25|直接依赖|maven|
|io.grpc:grpc-context|1.27.2|间接依赖|maven|
|org.eclipse.jetty:jetty-http|9.4.38.v20210224|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.2|间接依赖|maven|
|org.apache.seatunnel:seatunnel-config-base|2.3.3-SNAPSHOT|直接依赖|maven|
|org.codehaus.janino:commons-compiler|3.0.11|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-ram|3.0.0|间接依赖|maven|
|commons-dbcp:commons-dbcp|1.4|间接依赖|maven|
|com.sun.jersey:jersey-json|1.9|间接依赖|maven|
|org.glassfish.jersey.media:jersey-media-jaxb|2.22.2|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-client|3.1.4|间接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|5.0.3|间接依赖|maven|
|org.apache.flink:flink-table-planner_2.11|1.13.6|直接依赖|maven|
|software.amazon.awssdk:auth|2.18.1|间接依赖|maven|
|javax.activation:activation|1.1|间接依赖|maven|
|org.apache.orc:orc-shims|1.6.0|间接依赖|maven|
|org.apache.flink:flink-file-sink-common|1.13.6|间接依赖|maven|
|org.jdom:jdom|1.1|间接依赖|maven|
|org.apache.hadoop:hadoop-auth|2.9.2|间接依赖|maven|
|org.apache.flink:flink-optimizer_2.11|1.13.6|间接依赖|maven|
|org.eclipse.jetty:jetty-server|9.4.38.v20210224|间接依赖|maven|
|org.glassfish.hk2:osgi-resource-locator|1.0.1|间接依赖|maven|
|com.sun.xml.bind:jaxb-impl|2.2.7|间接依赖|maven|
|com.datastax.oss:native-protocol|1.5.1|间接依赖|maven|
|org.apache.orc:orc-shims|1.5.2|间接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.52.1|间接依赖|maven|
|io.grpc:grpc-stub|1.52.1|间接依赖|maven|
|com.sun.xml.bind:jaxb-impl|2.2.3-1|间接依赖|maven|
|com.squareup.okhttp3:okhttp|4.9.0|间接依赖|maven|
|io.grpc:grpc-auth|1.52.1|间接依赖|maven|
|org.lz4:lz4-java|1.8.0|间接依赖|maven|
|com.google.cloud:google-cloud-core|2.10.0|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.10.0|间接依赖|maven|
|com.aliyun.jindodata:jindo-core|4.6.1|直接依赖|maven|
|org.apache.poi:poi-ooxml-schemas|4.1.2|间接依赖|maven|
|org.codehaus.janino:janino|3.0.9|间接依赖|maven|
|org.apache.calcite:calcite-core|1.2.0-incubating|间接依赖|maven|
|software.amazon.awssdk:apache-client|2.18.1|间接依赖|maven|
|net.java.dev.jets3t:jets3t|0.9.0|间接依赖|maven|
|org.apache.kerby:kerby-util|1.0.1|间接依赖|maven|
|com.sun.jersey:jersey-servlet|1.19|间接依赖|maven|
|org.apache.hudi:hudi-hadoop-mr|0.11.1|间接依赖|maven|
|org.apache.spark:spark-launcher_2.11|2.4.0|间接依赖|maven|
|io.netty:netty-codec|4.1.45.Final|间接依赖|maven|
|org.apache.kerby:kerb-simplekdc|1.0.1|间接依赖|maven|
|org.apache.seatunnel:seatunnel-translation-spark-common|2.3.3-SNAPSHOT|直接依赖|maven|
|org.neo4j.driver:neo4j-java-driver|4.4.9|直接依赖|maven|
|org.apache.parquet:parquet-hadoop|1.10.1|间接依赖|maven|
|javax.jdo:jdo-api|3.0.1|间接依赖|maven|
|org.ow2.asm:asm-analysis|9.1|间接依赖|maven|
|javax.transaction:jta|1.1|间接依赖|maven|
|com.jolbox:bonecp|0.8.0.RELEASE|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-client|2.10.0|间接依赖|maven|
|org.apache.directory.api:api-asn1-api|1.0.0-M20|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.9.10|间接依赖|maven|
|io.debezium:debezium-embedded|1.6.4.Final|直接依赖|maven|
|com.google.guava:guava|27.0-jre|直接依赖|maven|
|org.apache.hadoop:hadoop-distcp|2.10.0|间接依赖|maven|
|org.apache.curator:curator-recipes|2.7.1|间接依赖|maven|
|org.mortbay.jetty:jetty|6.1.26|间接依赖|maven|
|org.glassfish.jersey.core:jersey-server|2.22.2|间接依赖|maven|
|org.apache.seatunnel:connector-file-base|2.3.3-SNAPSHOT|直接依赖|maven|
|software.amazon.awssdk:utils|2.18.1|间接依赖|maven|
|com.zaxxer:SparseBitSet|1.2|间接依赖|maven|
|org.apache.yetus:audience-annotations|0.5.0|间接依赖|maven|
|org.apache.hadoop:hadoop-hdfs-client|3.1.4|间接依赖|maven|
|org.apache.hbase.thirdparty:hbase-shaded-jersey|3.5.1|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.50|间接依赖|maven|
|org.apache.hadoop:hadoop-hdfs|2.6.5|间接依赖|maven|
|software.amazon.awssdk:protocol-core|2.18.1|间接依赖|maven|
|org.apache.flink:flink-shaded-jackson|2.12.1-13.0|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.4.1|间接依赖|maven|
|org.apache.avro:avro|1.8.2|间接依赖|maven|
|org.bouncycastle:bcprov-ext-jdk15on|1.69|间接依赖|maven|
|com.google.api:gax-httpjson|0.108.0|间接依赖|maven|
|software.amazon.awssdk:aws-json-protocol|2.18.1|间接依赖|maven|
|org.tukaani:xz|1.5|间接依赖|maven|
|net.razorvine:pyrolite|4.13|间接依赖|maven|
|org.glassfish.jaxb:jaxb-core|3.0.2|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.45.Final|间接依赖|maven|
|io.grpc:grpc-protobuf|1.52.1|间接依赖|maven|
|org.apache.hbase:hbase-hadoop2-compat|2.4.10|间接依赖|maven|
|io.grpc:grpc-xds|1.52.1|间接依赖|maven|
|org.apache.xbean:xbean-asm6-shaded|4.8|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|2.6.5|间接依赖|maven|
|io.perfmark:perfmark-api|0.26.0|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-core|3.1.4|间接依赖|maven|
|org.apache.seatunnel:seatunnel-translation-spark-2.4|2.3.3-SNAPSHOT|直接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.7|间接依赖|maven|
|com.squareup.retrofit2:retrofit|2.6.0|间接依赖|maven|
|com.lmax:disruptor|3.4.4|直接依赖|maven|
|com.google.protobuf:protobuf-java-util|3.21.12|间接依赖|maven|
|javolution:javolution|5.5.1|间接依赖|maven|
|org.scala-lang:scala-reflect|2.11.12|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.7.1|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.10.5|间接依赖|maven|
|org.apache.kerby:kerb-crypto|1.0.1|间接依赖|maven|
|com.google.cloud:google-cloud-core-grpc|2.10.0|间接依赖|maven|
|org.apache.commons:commons-lang3|3.4|直接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.16|间接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|com.twitter:chill-java|0.9.3|间接依赖|maven|
|org.apache.avro:avro-ipc|1.8.2|间接依赖|maven|
|com.clearspring.analytics:stream|2.7.0|间接依赖|maven|
|com.squareup.okio:okio|1.17.2|间接依赖|maven|
|io.debezium:debezium-connector-sqlserver|1.6.4.Final|直接依赖|maven|
|com.google.http-client:google-http-client-gson|1.40.1|间接依赖|maven|
|org.json4s:json4s-core_2.11|3.5.3|间接依赖|maven|
|io.netty:netty-handler|4.1.60.Final|间接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|2.14.0|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.22|间接依赖|maven|
|org.apache.hbase.thirdparty:hbase-shaded-gson|3.5.1|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.7.1|间接依赖|maven|
|com.jcraft:jsch|0.1.55|直接依赖|maven|
|net.minidev:json-smart|2.3|间接依赖|maven|
|io.grpc:grpc-api|1.52.1|间接依赖|maven|
|com.github.jnr:jnr-posix|3.1.5|间接依赖|maven|
|org.jetbrains:annotations|17.0.0|间接依赖|maven|
|org.apache.curator:curator-client|2.13.0|间接依赖|maven|
|commons-cli:commons-cli|1.2|间接依赖|maven|
|org.codehaus.janino:janino|3.0.11|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.38.v20210224|间接依赖|maven|
|org.glassfish.hk2.external:jakarta.inject|2.6.1|间接依赖|maven|
|org.apache.seatunnel:seatunnel-translation-flink-common|2.3.3-SNAPSHOT|直接依赖|maven|
|com.github.virtuald:curvesapi|1.06|间接依赖|maven|
|org.objenesis:objenesis|2.5.1|间接依赖|maven|
|org.glassfish.jaxb:txw2|3.0.2|间接依赖|maven|
|commons-digester:commons-digester|1.8|间接依赖|maven|
|org.apache.iceberg:iceberg-core|0.14.0|直接依赖|maven|
|com.squareup.okhttp3:okhttp|3.6.0|间接依赖|maven|
|org.apache.kerby:kerb-util|1.0.1|间接依赖|maven|
|org.apache.flink:flink-shaded-guava|18.0-13.0|间接依赖|maven|
|com.zendesk:mysql-binlog-connector-java|0.25.3|间接依赖|maven|
|com.twitter:chill_2.11|0.9.3|间接依赖|maven|
|org.apache.kerby:kerb-server|1.0.1|间接依赖|maven|
|com.clickhouse:clickhouse-grpc-client|0.3.2-patch11|间接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.0.2|间接依赖|maven|
|com.clickhouse:clickhouse-jdbc|0.3.2-patch11|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.10.5|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-paranamer|2.7.9|间接依赖|maven|
|com.squareup.retrofit2:converter-jackson|2.6.0|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.77.Final|间接依赖|maven|
|org.apache.iceberg:iceberg-hive-metastore|0.14.0|直接依赖|maven|
|org.apache.logging.log4j:log4j-1.2-api|2.17.1|直接依赖|maven|
|com.google.guava:failureaccess|1.0|间接依赖|maven|
|org.apache.thrift:libthrift|0.9.3|间接依赖|maven|
|org.apache.spark:spark-sketch_2.11|2.4.0|间接依赖|maven|
|io.opencensus:opencensus-api|0.31.1|间接依赖|maven|
|org.antlr:stringtemplate|3.2.1|间接依赖|maven|
|org.apache.flink:flink-shaded-netty|4.1.49.Final-13.0|间接依赖|maven|
|redis.clients:jedis|4.2.2|直接依赖|maven|
|io.netty:netty-common|4.1.60.Final|间接依赖|maven|
|com.sun.jersey.contribs:jersey-guice|1.9|间接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.17.1|直接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|org.rocksdb:rocksdbjni|5.17.2|间接依赖|maven|
|org.yaml:snakeyaml|1.30|间接依赖|maven|
|com.sun.xml.fastinfoset:FastInfoset|1.2.12|间接依赖|maven|
|org.apache.seatunnel:connector-file-s3|2.3.3-SNAPSHOT|直接依赖|maven|
|org.apache.hbase:hbase-protocol-shaded|2.4.10|间接依赖|maven|
|com.squareup.okio:okio|1.6.0|间接依赖|maven|
|jakarta.ws.rs:jakarta.ws.rs-api|2.1.6|间接依赖|maven|
|com.typesafe.akka:akka-slf4j_2.11|2.5.21|间接依赖|maven|
|asm:asm|3.1|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|间接依赖|maven|
|io.grpc:grpc-grpclb|1.52.1|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.1.3|间接依赖|maven|
|org.mongodb.kafka:mongo-kafka-connect|1.10.1|直接依赖|maven|
|com.squareup.okhttp3:okhttp|3.14.2|间接依赖|maven|
|com.squareup.okio:okio-jvm|3.0.0|间接依赖|maven|
|com.google.protobuf:protobuf-java|2.5.0|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|org.apache.iceberg:iceberg-orc|0.14.0|直接依赖|maven|
|com.sun.mail:javax.mail|1.5.6|直接依赖|maven|
|com.vlkan:flatbuffers|1.2.0-3f79e055|间接依赖|maven|
|io.protostuff:protostuff-api|1.8.0|间接依赖|maven|
|org.apache.seatunnel:connector-jdbc|2.3.3-SNAPSHOT|直接依赖|maven|
|com.slack.api:slack-api-client|1.25.0|直接依赖|maven|
|javax.servlet.jsp:javax.servlet.jsp-api|2.3.1|间接依赖|maven|
|org.apache.arrow:arrow-format|0.10.0|间接依赖|maven|
|org.apache.arrow:arrow-vector|0.10.0|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.2-1|间接依赖|maven|
|com.esotericsoftware:minlog|1.3.0|间接依赖|maven|
|org.codehaus.jackson:jackson-jaxrs|1.9.13|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.11.0|间接依赖|maven|
|org.apache.hbase:hbase-http|2.4.9|间接依赖|maven|
|org.apache.rocketmq:rocketmq-remoting|4.9.4|间接依赖|maven|
|com.github.scopt:scopt_2.11|3.5.0|间接依赖|maven|
|com.google.api.grpc:proto-google-iam-v1|1.9.0|间接依赖|maven|
|org.apache.seatunnel:seatunnel-spark-2-starter|2.3.3-SNAPSHOT|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.4.10|间接依赖|maven|
|org.apache.iceberg:iceberg-bundled-guava|0.14.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.6.7|直接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.3|间接依赖|maven|
|org.apache.orc:orc-shims|1.5.6|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|2.10.0|间接依赖|maven|
|org.eclipse.jetty:jetty-xml|9.4.20.v20190813|间接依赖|maven|
|org.apache.iotdb:iotdb-session|0.13.1|直接依赖|maven|
|com.google.protobuf:protobuf-java|3.21.12|间接依赖|maven|
|io.debezium:debezium-ddl-parser|1.6.4.Final|间接依赖|maven|
|com.google.flatbuffers:flatbuffers-java|1.12.0|间接依赖|maven|
|org.apache.hbase:hbase-zookeeper|2.4.9|间接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5|5.1.1|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|3.1.4|间接依赖|maven|
|com.esotericsoftware:kryo-shaded|4.0.2|间接依赖|maven|
|stax:stax-api|1.0.1|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.14|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.12|间接依赖|maven|
|org.apache.calcite.avatica:avatica-core|1.17.0|间接依赖|maven|
|net.sf.py4j:py4j|0.10.7|间接依赖|maven|
|com.aliyun:alibaba-dingtalk-service-sdk|2.0.0|直接依赖|maven|
|org.json4s:json4s-jackson_2.11|3.5.3|间接依赖|maven|
|org.apache.sshd:sshd-common|2.7.0|间接依赖|maven|
|io.netty:netty-common|4.1.45.Final|间接依赖|maven|
|com.squareup.okio:okio|2.8.0|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet-core|2.22.2|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.4.10|间接依赖|maven|
|software.amazon.awssdk:dynamodb-enhanced|2.18.1|直接依赖|maven|
|com.aliyun.odps:odps-sdk-core|0.31.3-public|直接依赖|maven|
|xml-apis:xml-apis|1.3.04|间接依赖|maven|
|com.github.stephenc.findbugs:findbugs-annotations|1.3.9-1|间接依赖|maven|
|org.apache.hbase.thirdparty:hbase-shaded-netty|3.5.1|间接依赖|maven|
|org.apache.flink:flink-hadoop-fs|1.13.6|间接依赖|maven|
|com.alibaba:fastjson|1.2.69_noneautotype|间接依赖|maven|
|org.apache.ivy:ivy|2.4.0|间接依赖|maven|
|com.github.luben:zstd-jni|1.3.2-2|间接依赖|maven|
|org.htrace:htrace-core|3.0.4|间接依赖|maven|
|com.github.luben:zstd-jni|1.4.5-6|间接依赖|maven|
|io.netty:netty-common|4.1.77.Final|间接依赖|maven|
|org.apache.httpcomponents.client5:httpclient5|5.1|间接依赖|maven|
|org.apache.hbase:hbase-common|2.4.9|间接依赖|maven|
|io.netty:netty-buffer|4.1.45.Final|间接依赖|maven|
|it.unimi.dsi:fastutil|7.0.13|间接依赖|maven|
|org.apache.thrift:libfb303|0.9.3|间接依赖|maven|
|com.google.auth:google-auth-library-credentials|1.3.0|间接依赖|maven|
|org.antlr:antlr-runtime|3.4|间接依赖|maven|
|org.apache.parquet:parquet-avro|1.12.3|直接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|7.9|间接依赖|maven|
|com.google.apis:google-api-services-sheets|v4-rev612-1.25.0|直接依赖|maven|
|org.codehaus.janino:commons-compiler|3.0.9|间接依赖|maven|
|org.mongodb:mongodb-driver-sync|4.7.1|直接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-core|2.6.5|间接依赖|maven|
|com.typesafe:config|1.3.3|直接依赖|maven|
|org.apache.flink:flink-table-api-scala_2.11|1.13.6|间接依赖|maven|
|com.aliyun.odps:odps-sdk-commons|0.31.3-public|间接依赖|maven|
|org.msgpack:msgpack-core|0.8.21|间接依赖|maven|
|io.opencensus:opencensus-proto|0.2.0|间接依赖|maven|
|org.apache.seatunnel:connector-paimon|2.3.3-SNAPSHOT|直接依赖|maven|
|org.apache.orc:orc-core|1.5.2|间接依赖|maven|
|javax.xml.bind:jsr173_api|1.0|间接依赖|maven|
|org.lz4:lz4-java|1.7.1|间接依赖|maven|
|io.netty:netty-codec-http|4.1.77.Final|间接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.69|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|com.google.flatbuffers:flatbuffers-java|1.11.0|间接依赖|maven|
|io.opencensus:opencensus-api|0.28.0|间接依赖|maven|
|org.apache.iotdb:influxdb-thrift|0.13.1|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.16|间接依赖|maven|
|org.apache.kafka:connect-json|2.7.1|间接依赖|maven|
|org.ow2.asm:asm|5.0.4|间接依赖|maven|
|org.apache.parquet:parquet-encoding|1.10.1|间接依赖|maven|
|xmlenc:xmlenc|0.52|间接依赖|maven|
|commons-io:commons-io|2.11.0|直接依赖|maven|
|com.google.oauth-client:google-oauth-client|1.25.0|间接依赖|maven|
|org.objenesis:objenesis|2.1|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.9.10|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.2.11|间接依赖|maven|
|org.apache.iotdb:iotdb-thrift|0.13.1|间接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|直接依赖|maven|
|org.apache.flink:flink-streaming-scala_2.11|1.13.6|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.3.2|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.4.6|间接依赖|maven|
|org.jodd:jodd-core|3.5.2|间接依赖|maven|
|org.glassfish.hk2:hk2-utils|2.4.0-b34|间接依赖|maven|
|org.apache.hbase:hbase-protocol-shaded|2.4.9|间接依赖|maven|
|org.apache.hadoop:hadoop-common|2.9.2|间接依赖|maven|
|com.google.cloud:proto-google-cloud-firestore-bundle-v1|3.7.10|间接依赖|maven|
|org.apache.seatunnel:seatunnel-format-text|2.3.3-SNAPSHOT|直接依赖|maven|
|org.scala-lang.modules:scala-xml_2.11|1.0.6|间接依赖|maven|
|org.apache.seatunnel:seatunnel-common|2.3.3-SNAPSHOT|直接依赖|maven|
|com.clickhouse:clickhouse-cli-client|0.3.2-patch11|间接依赖|maven|
|org.spark-project.hive:hive-metastore|1.2.1.spark2|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.2.0|间接依赖|maven|
|org.glassfish.jersey.core:jersey-common|2.22.2|间接依赖|maven|
|org.apache.seatunnel:checkpoint-storage-local-file|2.3.3-SNAPSHOT|直接依赖|maven|
|com.google.cloud:google-cloud-firestore|3.7.10|直接依赖|maven|
|javax.xml.bind:jaxb-api|2.2.2|间接依赖|maven|
|org.apache.arrow:arrow-format|5.0.0|间接依赖|maven|
|io.protostuff:protostuff-collectionschema|1.8.0|间接依赖|maven|
|io.airlift:aircompressor|0.10|间接依赖|maven|
|commons-pool:commons-pool|1.6|间接依赖|maven|
|com.github.jnr:jffi|1.3.1|间接依赖|maven|
|org.testcontainers:database-commons|1.17.6|间接依赖|maven|
|org.apache.parquet:parquet-format|2.4.0|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-app|2.6.5|间接依赖|maven|
|com.google.auto.value:auto-value-annotations|1.10.1|间接依赖|maven|
|org.apache.kerby:kerb-core|1.0.1|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.7.7|间接依赖|maven|
|org.eclipse.jetty:jetty-continuation|9.4.38.v20210224|间接依赖|maven|
|org.roaringbitmap:RoaringBitmap|0.5.11|间接依赖|maven|
|com.google.auth:google-auth-library-oauth2-http|1.3.0|直接依赖|maven|
|org.apache.parquet:parquet-avro|1.10.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.12.6|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.20.v20190813|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.1|间接依赖|maven|
|org.threeten:threeten-extra|1.5.0|间接依赖|maven|
|org.reflections:reflections|0.9.12|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.77.Final|间接依赖|maven|
|io.debezium:debezium-connector-mongodb|1.6.4.Final|直接依赖|maven|
|com.aliyun.jindodata:jindosdk|4.6.1|直接依赖|maven|
|org.apache.rocketmq:rocketmq-tools|4.9.4|直接依赖|maven|
|com.squareup.okhttp3:logging-interceptor|3.14.2|间接依赖|maven|
|org.glassfish.jersey.bundles.repackaged:jersey-guava|2.22.2|间接依赖|maven|
|io.opencensus:opencensus-contrib-grpc-util|0.31.1|间接依赖|maven|
|org.apache.orc:orc-core|1.5.6|直接依赖|maven|
|org.checkerframework:checker-qual|3.10.0|间接依赖|maven|
|log4j:apache-log4j-extras|1.2.17|间接依赖|maven|
|org.apache.avro:avro|1.11.1|直接依赖|maven|
|org.apache.parquet:parquet-common|1.10.0|间接依赖|maven|
|com.typesafe.akka:akka-stream_2.11|2.5.21|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.3|间接依赖|maven|
|io.dropwizard.metrics:metrics-jvm|3.1.5|间接依赖|maven|
|com.taosdata.jdbc:taos-jdbcdriver|3.0.3|直接依赖|maven|
|org.apache.orc:orc-core|1.7.5|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|2.6.5|间接依赖|maven|
|org.json:json|20211205|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|org.apache.curator:curator-framework|2.13.0|间接依赖|maven|
|org.ow2.asm:asm-util|9.1|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-shuffle|2.6.5|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.10.5|间接依赖|maven|
|com.starrocks:starrocks-thrift-sdk|1.0.1|直接依赖|maven|
|org.apache.commons:commons-pool2|2.11.1|间接依赖|maven|
|commons-cli:commons-cli|1.3.1|间接依赖|maven|
|org.jruby.jcodings:jcodings|1.0.55|间接依赖|maven|
|com.squareup.okhttp:okhttp|2.7.5|间接依赖|maven|
|org.apache.commons:commons-compress|1.20|直接依赖|maven|
|org.apache.commons:commons-math3|3.4.1|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|2.9.2|间接依赖|maven|
|org.apache.kafka:connect-file|2.7.1|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.10|间接依赖|maven|
|org.apache.flink:flink-clients_2.11|1.13.6|直接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.45.Final|间接依赖|maven|
|io.dropwizard.metrics:metrics-json|3.1.5|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.0|间接依赖|maven|
|org.apache.seatunnel:seatunnel-engine-server|2.3.3-SNAPSHOT|直接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|3.0.1|间接依赖|maven|
|org.apache.kerby:kerb-identity|1.0.1|间接依赖|maven|
|org.apache.httpcomponents:fluent-hc|4.4.1|间接依赖|maven|
|javax.activation:activation|1.1.1|间接依赖|maven|
|org.apache.httpcomponents:httpmime|4.5.13|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-properties|2.12.6|直接依赖|maven|
|org.eclipse.jetty:jetty-servlets|9.4.38.v20210224|间接依赖|maven|
|org.apache.hbase:hbase-client|2.4.9|间接依赖|maven|
|org.apache.rocketmq:rocketmq-acl|4.9.4|间接依赖|maven|
|io.netty:netty-resolver|4.1.77.Final|间接依赖|maven|
|org.ow2.asm:asm|9.1|间接依赖|maven|
|javax.validation:validation-api|1.1.0.Final|间接依赖|maven|
|org.jamon:jamon-runtime|2.4.1|间接依赖|maven|
|joda-time:joda-time|2.9.1|间接依赖|maven|
|software.amazon.awssdk:netty-nio-client|2.18.1|间接依赖|maven|
|com.google.code.findbugs:jsr305|2.0.2|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet|2.31|间接依赖|maven|
|com.github.jsqlparser:jsqlparser|4.5|直接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.3|间接依赖|maven|
|org.scala-lang.modules:scala-xml_2.11|1.0.5|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.18.0|间接依赖|maven|
|javax.mail:mail|1.4.7|间接依赖|maven|
|org.apache.flink:force-shading|1.13.6|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|3.1.4|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|3.1.4|间接依赖|maven|
|junit:junit|4.12|间接依赖|maven|
|org.apache.directory.server:apacheds-kerberos-codec|2.0.0-M15|间接依赖|maven|
|net.jcip:jcip-annotations|1.0|间接依赖|maven|
|org.apache.hadoop:hadoop-common|3.1.4|间接依赖|maven|
|org.apache.iceberg:iceberg-api|0.14.0|直接依赖|maven|
|com.google.code.gson:gson|2.10.1|间接依赖|maven|
|org.apache.seatunnel:seatunnel-transforms-v2|2.3.3-SNAPSHOT|直接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.1.6|间接依赖|maven|
|io.netty:netty-transport|4.1.45.Final|间接依赖|maven|
|org.ow2.asm:asm-commons|9.1|间接依赖|maven|
|org.json:json|20170516|间接依赖|maven|
|org.apache.avro:avro-mapred|1.8.2|间接依赖|maven|
|org.javassist:javassist|3.25.0-GA|间接依赖|maven|
|com.googlecode.javaewah:JavaEWAH|0.3.2|间接依赖|maven|
|org.apache.kafka:connect-transforms|2.7.1|间接依赖|maven|
|com.google.auto.value:auto-value|1.10.1|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|直接依赖|maven|
|com.google.protobuf:protobuf-java|2.4.1|间接依赖|maven|
|org.apache.iotdb:service-rpc|0.13.1|间接依赖|maven|
|com.sun.jersey:jersey-client|1.9|间接依赖|maven|
|com.esotericsoftware.kryo:kryo|2.24.0|间接依赖|maven|
|software.amazon.awssdk:annotations|2.18.1|间接依赖|maven|
|io.airlift:aircompressor|0.21|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.2-2|间接依赖|maven|
|org.apache.seatunnel:seatunnel-engine-common|2.3.3-SNAPSHOT|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)