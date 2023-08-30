# Azure/azure-sdk-for-java安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696971367554834432.svg)](https://www.murphysec.com/console/report/1696947350118232064/1696971367554834432)

仓库描述：This repository is for active development of the Azure SDK for Java. For consumers of the SDK we recommend visiting our public developer docs at https://docs.microsoft.com/java/azure/ or our versioned developer docs at https://azure.github.io/azure-sdk-for-java. 

仓库地址：[https://github.com/Azure/azure-sdk-for-java](https://github.com/Azure/azure-sdk-for-java)

| star：1983 | watch：332 | fork：1833 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-31 02:04:08 | 许可证：MIT |
| 最近检测时间：2023-08-31 05:05:41 | 组件总数：1175 | 漏洞总数：244 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|OWASP ESAPI CBC Mode HMAC 身份验证绕过漏洞|密码学问题|[MPS-2013-3692](https://www.oscs1024.com/hd/MPS-2013-3692)|CVE-2013-5679|低危|
|OWASP ESAPI 绕过加密漏洞|密码学问题|[MPS-2013-3693](https://www.oscs1024.com/hd/MPS-2013-3693)|CVE-2013-5960|中危|
|Apache HttpClient 中间人攻击漏洞|对宿主不匹配的证书验证不恰当|[MPS-2014-4112](https://www.oscs1024.com/hd/MPS-2014-4112)|CVE-2014-3577|中危|
|Apache HttpClient 中间人攻击漏洞|输入验证不恰当|[MPS-2014-4288](https://www.oscs1024.com/hd/MPS-2014-4288)|CVE-2012-6153|中危|
|Not-Yet-Commons-SSL 证书验证安全绕过漏洞|密码学问题|[MPS-2014-6690](https://www.oscs1024.com/hd/MPS-2014-6690)|CVE-2014-3604|中危|
|Shibboleth Identity Provider和OpenSAML Java 安全漏洞|7PK - 安全功能|[MPS-2015-3260](https://www.oscs1024.com/hd/MPS-2015-3260)|CVE-2015-1796|中危|
|Apache Groovy 代码注入漏洞|注入|[MPS-2015-3848](https://www.oscs1024.com/hd/MPS-2015-3848)|CVE-2015-3253|严重|
|多款Cisco产品Apache Commons Collections库任意代码执行漏洞|反序列化|[MPS-2015-6277](https://www.oscs1024.com/hd/MPS-2015-6277)|CVE-2015-6420|高危|
|多款Red Hat产品代码问题漏洞|反序列化|[MPS-2017-12638](https://www.oscs1024.com/hd/MPS-2017-12638)|CVE-2015-7501|严重|
|QOS.ch Logback SocketServer和ServerSocketReceiver组件代码问题漏洞|反序列化|[MPS-2017-2574](https://www.oscs1024.com/hd/MPS-2017-2574)|CVE-2017-5929|严重|
|Nimbus JOSE+JWT 安全漏洞|对数据真实性的验证不充分|[MPS-2017-9387](https://www.oscs1024.com/hd/MPS-2017-9387)|CVE-2017-12972|高危|
|Nimbus JOSE+JWT 安全漏洞|完整性检查值验证不恰当|[MPS-2017-9388](https://www.oscs1024.com/hd/MPS-2017-9388)|CVE-2017-12973|低危|
|Nimbus JOSE+JWT<4.36  非法椭圆曲线攻击漏洞|密码学签名的验证不恰当|[MPS-2017-9389](https://www.oscs1024.com/hd/MPS-2017-9389)|CVE-2017-12974|高危|
|Red Hat Hibernate Validator 存在不安全反射漏洞|使用外部可控制的输入来选择类或代码（不安全的反射）|[MPS-2018-0334](https://www.oscs1024.com/hd/MPS-2018-0334)|CVE-2017-7536|高危|
|FasterXML Jackson-databind 反序列化漏洞(dbcp2 gadget绕过)|反序列化|[MPS-2018-0362](https://www.oscs1024.com/hd/MPS-2018-0362)|CVE-2017-17485|严重|
|FasterXML jackson-databind 反序列化漏洞(Hibernate/iBatis gadget绕过)||[MPS-2018-0934](https://www.oscs1024.com/hd/MPS-2018-0934)|CVE-2018-5968|高危|
|Apache Tomcat 竞争条件问题漏洞|竞争条件|[MPS-2018-10791](https://www.oscs1024.com/hd/MPS-2018-10791)|CVE-2018-8037|中危|
|Apache Tomcat 拒绝服务漏洞|不可达退出条件的循环（无限循环）|[MPS-2018-10792](https://www.oscs1024.com/hd/MPS-2018-10792)|CVE-2018-1336|高危|
|Apache Tomcat 输入验证错误漏洞|跨站重定向|[MPS-2018-13051](https://www.oscs1024.com/hd/MPS-2018-13051)|CVE-2018-11784|中危|
|Spring Framework <5.1.1.RELEASE 拒绝服务漏洞|拒绝服务|[MPS-2018-13948](https://www.oscs1024.com/hd/MPS-2018-13948)|CVE-2018-15756|高危|
|FasterXML Jackson-databind 反序列化漏洞(JdbcRowSetImpl gadget绕过)|反序列化|[MPS-2018-1438](https://www.oscs1024.com/hd/MPS-2018-1438)|CVE-2017-15095|严重|
|FasterXML Jackson-databind反序列化漏洞|反序列化|[MPS-2018-1439](https://www.oscs1024.com/hd/MPS-2018-1439)|CVE-2017-7525|严重|
|Square Retrofit 路径遍历漏洞|路径遍历|[MPS-2018-16072](https://www.oscs1024.com/hd/MPS-2018-16072)|CVE-2018-1000850|高危|
|FasterXML Jackson < 2.9.8存在拒绝服务漏洞|拒绝服务|[MPS-2018-16099](https://www.oscs1024.com/hd/MPS-2018-16099)|CVE-2018-1000873|中危|
|Apache Tomcat 访问控制错误漏洞|路径遍历|[MPS-2018-2433](https://www.oscs1024.com/hd/MPS-2018-2433)|CVE-2018-1305|中危|
|FasterXML jackson-databind 反序列化漏洞(c3p0 gadget绕过)||[MPS-2018-2477](https://www.oscs1024.com/hd/MPS-2018-2477)|CVE-2018-7489|严重|
|Apache Tomcat 安全约束绕过漏洞|访问控制不当|[MPS-2018-2590](https://www.oscs1024.com/hd/MPS-2018-2590)|CVE-2018-1304|中危|
|Pivotal Spring Framework 路径遍历漏洞|路径遍历|[MPS-2018-4351](https://www.oscs1024.com/hd/MPS-2018-4351)|CVE-2018-1271|中危|
|Pivotal Spring Framework 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2018-4352](https://www.oscs1024.com/hd/MPS-2018-4352)|CVE-2018-1272|高危|
|Spring Data Commons <2.0.6.RELEASE  远程代码执行漏洞|代码注入|[MPS-2018-4454](https://www.oscs1024.com/hd/MPS-2018-4454)|CVE-2018-1273|严重|
|Spring Data Commons 无限制的资源分配漏洞|不加限制或调节的资源分配|[MPS-2018-5028](https://www.oscs1024.com/hd/MPS-2018-5028)|CVE-2018-1274|高危|
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|Pivotal Spring Data Commons 外部实体注入漏洞|XXE|[MPS-2018-5952](https://www.oscs1024.com/hd/MPS-2018-5952)|CVE-2018-1259|高危|
|Apache Tomcat CORS Filter 不安全的默认值漏洞|资源默认不安全|[MPS-2018-6086](https://www.oscs1024.com/hd/MPS-2018-6086)|CVE-2018-8014|严重|
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
|Pivotal Spring Framework XST漏洞|访问控制不当|[MPS-2018-8290](https://www.oscs1024.com/hd/MPS-2018-8290)|CVE-2018-11039|中危|
|Pivotal Spring Framework 信息泄露漏洞|从非可信控制范围包含功能例程|[MPS-2018-8291](https://www.oscs1024.com/hd/MPS-2018-8291)|CVE-2018-11040|高危|
|FasterXML jackson-databind反序列化漏洞(slf4j-ext gadget绕过)|反序列化|[MPS-2019-0018](https://www.oscs1024.com/hd/MPS-2019-0018)|CVE-2018-14718|严重|
|FasterXML jackson-databind反序列化漏洞(blaze-ds-opt gadget绕过)|反序列化|[MPS-2019-0019](https://www.oscs1024.com/hd/MPS-2019-0019)|CVE-2018-14719|严重|
|FasterXML jackson-databind XXE漏洞(DRSHelper gadget绕过)||[MPS-2019-0020](https://www.oscs1024.com/hd/MPS-2019-0020)|CVE-2018-14720|严重|
|FasterXML Jackson-databind服务器端请求伪造漏洞(axis2-jaxws gadget绕过)|SSRF|[MPS-2019-0021](https://www.oscs1024.com/hd/MPS-2019-0021)|CVE-2018-14721|严重|
|FasterXML Jackson-databind代码问题漏洞(axis2-transport-jms gadget绕过)|反序列化|[MPS-2019-0023](https://www.oscs1024.com/hd/MPS-2019-0023)|CVE-2018-19360|严重|
|FasterXML Jackson-databind代码问题漏洞(openjpa gadget绕过)|反序列化|[MPS-2019-0024](https://www.oscs1024.com/hd/MPS-2019-0024)|CVE-2018-19361|严重|
|FasterXML Jackson-databind代码问题漏洞(jboss-common-core gadget绕过)|反序列化|[MPS-2019-0025](https://www.oscs1024.com/hd/MPS-2019-0025)|CVE-2018-19362|严重|
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
|jackson-mapper-asl <=1.9.13 XXE 注入漏洞|XXE|[MPS-2019-15048](https://www.oscs1024.com/hd/MPS-2019-15048)|CVE-2019-10172|高危|
|SnakeYAML <1.26 存在 Billion laughs 漏洞|拒绝服务|[MPS-2019-16129](https://www.oscs1024.com/hd/MPS-2019-16129)|CVE-2017-18640|高危|
|Apache Tomcat 授权问题漏洞|会话固定|[MPS-2019-16906](https://www.oscs1024.com/hd/MPS-2019-16906)|CVE-2019-17563|高危|
|FasterXML Jackson-databind反序列化漏洞（Jodd-db gadget绕过）|反序列化|[MPS-2019-2619](https://www.oscs1024.com/hd/MPS-2019-2619)|CVE-2018-12022|高危|
|FasterXML Jackson-databind反序列化漏洞(Oracle JDBC driver gadget绕过)|反序列化|[MPS-2019-2620](https://www.oscs1024.com/hd/MPS-2019-2620)|CVE-2018-12023|高危|
|Apache Tomcat拒绝服务漏洞|拒绝服务|[MPS-2019-3894](https://www.oscs1024.com/hd/MPS-2019-3894)|CVE-2019-0199|高危|
|Apache Tomcat 操作系统命令注入漏洞|OS命令注入|[MPS-2019-4006](https://www.oscs1024.com/hd/MPS-2019-4006)|CVE-2019-0232|高危|
|FasterXML jackson-databind 反序列化漏洞(mysql gadget绕过)|反序列化|[MPS-2019-5442](https://www.oscs1024.com/hd/MPS-2019-5442)|CVE-2019-12086|高危|
|Apache Tomcat 跨站脚本漏洞|XSS|[MPS-2019-5944](https://www.oscs1024.com/hd/MPS-2019-5944)|CVE-2019-0221|中危|
|FasterXML jackson-databind 反序列化漏洞(jdom gadget绕过)|反序列化|[MPS-2019-6867](https://www.oscs1024.com/hd/MPS-2019-6867)|CVE-2019-12814|中危|
|Apache Tomcat 资源管理错误漏洞|加锁机制不恰当|[MPS-2019-7027](https://www.oscs1024.com/hd/MPS-2019-7027)|CVE-2019-10072|高危|
|FasterXML jackson-databind 反序列化漏洞(logback-classic gadget绕过)|反序列化|[MPS-2019-7047](https://www.oscs1024.com/hd/MPS-2019-7047)|CVE-2019-12384|中危|
|FasterXML jackson-databind 反序列化漏洞(iBatis gadget绕过)|反序列化|[MPS-2019-7711](https://www.oscs1024.com/hd/MPS-2019-7711)|CVE-2018-11307|严重|
|FasterXML jackson-databind 反序列化漏洞(ehcache gadget绕过)|动态确定对象属性修改的控制不恰当|[MPS-2019-8717](https://www.oscs1024.com/hd/MPS-2019-8717)|CVE-2019-14379|严重|
|FasterXML jackson-databind 信息泄露漏洞(logback gadget绕过)|反序列化|[MPS-2019-8770](https://www.oscs1024.com/hd/MPS-2019-8770)|CVE-2019-14439|高危|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|FasterXML jackson-databind反序列化漏洞(net.sf.ehcache gadget绕过)|反序列化|[MPS-2020-0063](https://www.oscs1024.com/hd/MPS-2020-0063)|CVE-2019-20330|严重|
|Pivotal Spring Framework <5.2.3.RELEASE 反射文件下载 (RFD) 漏洞|下载代码缺少完整性检查|[MPS-2020-0902](https://www.oscs1024.com/hd/MPS-2020-0902)|CVE-2020-5398|高危|
|FasterXML jackson-databind反序列化漏洞(Anteros-DBCP gadget绕过)|反序列化|[MPS-2020-11987](https://www.oscs1024.com/hd/MPS-2020-11987)|CVE-2020-24616|高危|
|FasterXML jackson-databind 反序列化漏洞(pastdev gadget绕过)|反序列化|[MPS-2020-13151](https://www.oscs1024.com/hd/MPS-2020-13151)|CVE-2020-24750|高危|
|Netty <=4.1.43.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1320](https://www.oscs1024.com/hd/MPS-2020-1320)|CVE-2020-7238|高危|
|Pivotal Spring Framework 反射文件下载 (RFD) 漏洞|路径遍历|[MPS-2020-13322](https://www.oscs1024.com/hd/MPS-2020-13322)|CVE-2020-5421|中危|
|Netty <4.1.44.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1526](https://www.oscs1024.com/hd/MPS-2020-1526)|CVE-2019-20444|严重|
|Netty <4.1.44.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1527](https://www.oscs1024.com/hd/MPS-2020-1527)|CVE-2019-20445|严重|
|Apache Tomcat HTTP请求走私漏洞|HTTP请求走私|[MPS-2020-15344](https://www.oscs1024.com/hd/MPS-2020-15344)|CVE-2020-13943|中危|
|Bouncy Castle 私钥信息泄漏漏洞|通过差异性导致的信息暴露|[MPS-2020-16513](https://www.oscs1024.com/hd/MPS-2020-16513)|CVE-2020-26939|中危|
|Apache HttpClient URI解析错误漏洞|XSS|[MPS-2020-17341](https://www.oscs1024.com/hd/MPS-2020-17341)|CVE-2020-13956|中危|
|FasterXML jackson-databind 代码问题漏洞|XXE|[MPS-2020-17358](https://www.oscs1024.com/hd/MPS-2020-17358)|CVE-2020-25649|高危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2020-17486](https://www.oscs1024.com/hd/MPS-2020-17486)|CVE-2020-17527|高危|
|FasterXML jackson-databind 反序列化漏洞(commons-dbcp2 gadget绕过)|反序列化|[MPS-2020-17696](https://www.oscs1024.com/hd/MPS-2020-17696)|CVE-2020-35490|高危|
|FasterXML jackson-databind 反序列化漏洞(commons-dbcp2 gadget绕过)|反序列化|[MPS-2020-17697](https://www.oscs1024.com/hd/MPS-2020-17697)|CVE-2020-35491|高危|
|FasterXML jackson-databind 反序列化漏洞(glassfish gadget绕过)|反序列化|[MPS-2020-18089](https://www.oscs1024.com/hd/MPS-2020-18089)|CVE-2020-35728|高危|
|FasterXML jackson-databind 反序列化漏洞(xbean-reflect gadget绕过)|反序列化|[MPS-2020-2030](https://www.oscs1024.com/hd/MPS-2020-2030)|CVE-2020-8840|严重|
|FasterXML jackson-databind 反序列化漏洞(ignite-jta gadget绕过)|反序列化|[MPS-2020-24779](https://www.oscs1024.com/hd/MPS-2020-24779)|CVE-2020-10650|高危|
|Apache Tomcat 权限管理不当漏洞|权限管理不当|[MPS-2020-2841](https://www.oscs1024.com/hd/MPS-2020-2841)|CVE-2020-1938|严重|
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
|hibernate-validator 存在输入验证错误漏洞|代码注入|[MPS-2020-7077](https://www.oscs1024.com/hd/MPS-2020-7077)|CVE-2020-10693|中危|
|Apache Tomcat 远程代码执行漏洞|反序列化|[MPS-2020-7626](https://www.oscs1024.com/hd/MPS-2020-7626)|CVE-2020-9484|高危|
|FasterXML jackson-databind反序列化漏洞(oracle-aqjms gadget绕过)|反序列化|[MPS-2020-8801](https://www.oscs1024.com/hd/MPS-2020-8801)|CVE-2020-14061|高危|
|FasterXML jackson-databind反序列化漏洞(xalan2 gadget绕过)|反序列化|[MPS-2020-8802](https://www.oscs1024.com/hd/MPS-2020-8802)|CVE-2020-14062|高危|
|FasterXML jackson-databind反序列化漏洞(apache drill gadget绕过)|反序列化|[MPS-2020-8803](https://www.oscs1024.com/hd/MPS-2020-8803)|CVE-2020-14060|高危|
|FasterXML jackson-databind代码问题漏洞(jsecurity gadget绕过)|反序列化|[MPS-2020-8911](https://www.oscs1024.com/hd/MPS-2020-8911)|CVE-2020-14195|高危|
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
|Netty <4.1.59.Final 存在不安全的临时文件漏洞||[MPS-2021-1580](https://www.oscs1024.com/hd/MPS-2021-1580)|CVE-2021-21290|中危|
|FasterXML jackson-databind 反序列化漏洞(javax.swing gadget绕过)|反序列化|[MPS-2021-1625](https://www.oscs1024.com/hd/MPS-2021-1625)|CVE-2021-20190|高危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-1722](https://www.oscs1024.com/hd/MPS-2021-1722)|CVE-2021-24122|中危|
|jsoup <1.14.2 存在拒绝服务漏洞||[MPS-2021-17634](https://www.oscs1024.com/hd/MPS-2021-17634)|CVE-2021-37714|高危|
|Spring Framework <5.3.14 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18854](https://www.oscs1024.com/hd/MPS-2021-18854)|CVE-2021-22060|中危|
|Pivotal Spring Framework 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18890](https://www.oscs1024.com/hd/MPS-2021-18890)|CVE-2021-22096|中危|
|netplex json-smart-v  分布式拒绝服务攻击|对因果或异常条件的不恰当检查|[MPS-2021-2102](https://www.oscs1024.com/hd/MPS-2021-2102)|CVE-2021-27568|严重|
|Apache Tomcat 信息泄露漏洞|HTTP请求走私|[MPS-2021-2309](https://www.oscs1024.com/hd/MPS-2021-2309)|CVE-2021-25122|高危|
|io.netty:netty-codec-http2 <4.1.60.Final 存在 http 请求走私漏洞|HTTP请求走私|[MPS-2021-2435](https://www.oscs1024.com/hd/MPS-2021-2435)|CVE-2021-21295|中危|
|Apache Tomcat 远程代码执行漏洞|代码注入|[MPS-2021-2466](https://www.oscs1024.com/hd/MPS-2021-2466)|CVE-2021-25329|高危|
|Netty Bzip2Decoder 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28116](https://www.oscs1024.com/hd/MPS-2021-28116)|CVE-2021-37136|高危|
|Netty 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28117](https://www.oscs1024.com/hd/MPS-2021-28117)|CVE-2021-37137|高危|
|Apache Santuario <2.2.3 本地 XML 文件泄露漏洞|未授权敏感信息泄露|[MPS-2021-31436](https://www.oscs1024.com/hd/MPS-2021-31436)|CVE-2021-40690|高危|
|Apache Tomcat 拒绝服务漏洞|拒绝服务|[MPS-2021-31848](https://www.oscs1024.com/hd/MPS-2021-31848)|CVE-2021-41079|高危|
|Quality Open Software logback JNDI注入漏洞|反序列化|[MPS-2021-33911](https://www.oscs1024.com/hd/MPS-2021-33911)|CVE-2021-42550|中危|
|Oracle Java SE 和 Oracle GraalVM 输入验证错误漏洞|拒绝服务|[MPS-2021-36650](https://www.oscs1024.com/hd/MPS-2021-36650)|CVE-2022-21426|中危|
|Oracle Java SE 和 Oracle GraalVM 输入验证错误漏洞|使用外部可控制的输入来选择类或代码（不安全的反射）|[MPS-2021-36658](https://www.oscs1024.com/hd/MPS-2021-36658)|CVE-2022-21434|中危|
|Oracle Java SE 输入验证错误漏洞||[MPS-2021-36667](https://www.oscs1024.com/hd/MPS-2021-36667)|CVE-2022-21443|低危|
|Java SE 数字签名伪造漏洞|密码学签名的验证不恰当|[MPS-2021-36673](https://www.oscs1024.com/hd/MPS-2021-36673)|CVE-2022-21449|高危|
|Oracle Java SE 输入验证错误漏洞||[MPS-2021-36700](https://www.oscs1024.com/hd/MPS-2021-36700)|CVE-2022-21476|高危|
|Oracle Java SE 输入验证错误漏洞||[MPS-2021-36720](https://www.oscs1024.com/hd/MPS-2021-36720)|CVE-2022-21496|中危|
|Netty <4.1.71.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2021-36922](https://www.oscs1024.com/hd/MPS-2021-36922)|CVE-2021-43797|中危|
|Apache Tomcat 条件竞争漏洞|竞争条件|[MPS-2021-37218](https://www.oscs1024.com/hd/MPS-2021-37218)|CVE-2021-43980|低危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|Eclipse Jersey 本地信息泄露漏洞|将资源暴露给错误范围|[MPS-2021-5218](https://www.oscs1024.com/hd/MPS-2021-5218)|CVE-2021-28168|中危|
|Bouncy Castle 私钥信息泄露漏洞|竞争条件|[MPS-2021-7064](https://www.oscs1024.com/hd/MPS-2021-7064)|CVE-2020-15522|中危|
|Spring Framework权限许可和访问控制问题漏洞|权限管理不当|[MPS-2021-7485](https://www.oscs1024.com/hd/MPS-2021-7485)|CVE-2021-22118|高危|
|json-smart 存在拒绝服务漏洞|越界写入|[MPS-2021-7737](https://www.oscs1024.com/hd/MPS-2021-7737)|CVE-2021-31684|高危|
|OWASP ESAPI 安全漏洞|依赖于未经完整性检查的安全相关输入的混淆或加密|[MPS-2021-8695](https://www.oscs1024.com/hd/MPS-2021-8695)|CVE-2010-3300|中危|
|Apache Tomcat 环境问题漏洞|HTTP请求走私|[MPS-2021-9711](https://www.oscs1024.com/hd/MPS-2021-9711)|CVE-2021-33037|中危|
|Vmware Spring Framework 安全漏洞|不加限制或调节的资源分配|[MPS-2022-1080](https://www.oscs1024.com/hd/MPS-2022-1080)|CVE-2022-22950|中危|
|Pivotal Spring Framework 安全限制绕过漏洞|大小写敏感处理不恰当|[MPS-2022-1098](https://www.oscs1024.com/hd/MPS-2022-1098)|CVE-2022-22968|中危|
|Spring Framework spring-beans 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1101](https://www.oscs1024.com/hd/MPS-2022-1101)|CVE-2022-22970|中危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|com.fasterxml.jackson.core:jackson-core 存在资源管理错误漏洞|资源管理错误|[MPS-2022-11944](https://www.oscs1024.com/hd/MPS-2022-11944)||中危|
|com.nimbusds:nimbus-jose-jwt <4.34.2存在信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-11950](https://www.oscs1024.com/hd/MPS-2022-11950)||高危|
|io.netty:netty-codec-http <4.1.53.Final 存在拒绝服务漏洞|拒绝服务|[MPS-2022-12064](https://www.oscs1024.com/hd/MPS-2022-12064)||中危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|com.fasterxml.jackson.core:jackson-core  BigDecimal拒绝服务漏洞|资源管理错误|[MPS-2022-12166](https://www.oscs1024.com/hd/MPS-2022-12166)||中危|
|com.nimbusds:oauth2-oidc-sdk 存在XXE漏洞|XXE|[MPS-2022-12182](https://www.oscs1024.com/hd/MPS-2022-12182)||高危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|Apache HttpClient URI解析错误漏洞|相对路径遍历|[MPS-2022-12292](https://www.oscs1024.com/hd/MPS-2022-12292)||中危|
|Logback SSL证书校验不当漏洞|中间人攻击|[MPS-2022-12411](https://www.oscs1024.com/hd/MPS-2022-12411)||中危|
|com.fasterxml.jackson.core:jackson-databind 存在反序列化漏洞|反序列化|[MPS-2022-12433](https://www.oscs1024.com/hd/MPS-2022-12433)||高危|
|Apache Commons Collections 远程代码执行漏洞|反序列化|[MPS-2022-12767](https://www.oscs1024.com/hd/MPS-2022-12767)||高危|
|org.json:json 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13520](https://www.oscs1024.com/hd/MPS-2022-13520)||高危|
|Eclipse Jetty URI注入漏洞|注入|[MPS-2022-18060](https://www.oscs1024.com/hd/MPS-2022-18060)|CVE-2022-2047|低危|
|OWASP ESAPI 路径遍历漏洞|路径遍历|[MPS-2022-1884](https://www.oscs1024.com/hd/MPS-2022-1884)|CVE-2022-23457|高危|
|Netty 存在信息泄露漏洞||[MPS-2022-3790](https://www.oscs1024.com/hd/MPS-2022-3790)|CVE-2022-24823|中危|
|OWASP ESAPI 跨站脚本漏洞|XSS|[MPS-2022-3858](https://www.oscs1024.com/hd/MPS-2022-3858)|CVE-2022-24891|中危|
|Oracle Java SE输入验证错误漏洞（CNVD-2022-32662）|路径遍历|[MPS-2022-50565](https://www.oscs1024.com/hd/MPS-2022-50565)||高危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|jsoup <1.15.3 存在反射型 XSS 漏洞|XSS|[MPS-2022-51547](https://www.oscs1024.com/hd/MPS-2022-51547)|CVE-2022-36033|中危|
|woodstox-core<5.3.0 存在XXE漏洞|XXE|[MPS-2022-54303](https://www.oscs1024.com/hd/MPS-2022-54303)||中危|
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
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot在Cloud Foundry中部署存在路由限制绕过风险|访问控制不当|[MPS-2022-62845](https://www.oscs1024.com/hd/MPS-2022-62845)|CVE-2023-20873|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|Jettison <1.5.2 拒绝服务漏洞|越界写入|[MPS-2022-64973](https://www.oscs1024.com/hd/MPS-2022-64973)|CVE-2022-45685|高危|
|H2 数据库明文密码问题|未授权敏感信息泄露|[MPS-2022-65204](https://www.oscs1024.com/hd/MPS-2022-65204)|CVE-2022-45868|高危|
|spring-boot <2.2.11.RELEASE 存在目录劫持漏洞|将资源暴露给错误范围|[MPS-2022-6780](https://www.oscs1024.com/hd/MPS-2022-6780)|CVE-2022-27772|高危|
|spring-beans 远程代码执行漏洞(Spring4Shell)|表达式语言注入|[MPS-2022-6820](https://www.oscs1024.com/hd/MPS-2022-6820)|CVE-2022-22965|严重|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68515](https://www.oscs1024.com/hd/MPS-2022-68515)|CVE-2023-21930|高危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68522](https://www.oscs1024.com/hd/MPS-2022-68522)|CVE-2023-21937|低危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68523](https://www.oscs1024.com/hd/MPS-2022-68523)|CVE-2023-21938|低危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68524](https://www.oscs1024.com/hd/MPS-2022-68524)|CVE-2023-21939|中危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68539](https://www.oscs1024.com/hd/MPS-2022-68539)|CVE-2023-21954|中危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68552](https://www.oscs1024.com/hd/MPS-2022-68552)|CVE-2023-21967|中危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68553](https://www.oscs1024.com/hd/MPS-2022-68553)|CVE-2023-21968|低危|
|Oracle Java SE 安全漏洞||[MPS-2022-68591](https://www.oscs1024.com/hd/MPS-2022-68591)|CVE-2023-22006|低危|
|Oracle Java SE 安全漏洞||[MPS-2022-68621](https://www.oscs1024.com/hd/MPS-2022-68621)|CVE-2023-22036|低危|
|Oracle Java SE 安全漏洞||[MPS-2022-68626](https://www.oscs1024.com/hd/MPS-2022-68626)|CVE-2023-22041|中危|
|Oracle Java SE 安全漏洞||[MPS-2022-68629](https://www.oscs1024.com/hd/MPS-2022-68629)|CVE-2023-22044|低危|
|Oracle Java SE 安全漏洞||[MPS-2022-68630](https://www.oscs1024.com/hd/MPS-2022-68630)|CVE-2023-22045|低危|
|Oracle Java SE 安全漏洞||[MPS-2022-68634](https://www.oscs1024.com/hd/MPS-2022-68634)|CVE-2023-22049|低危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Apache Kafka Connect 模块JNDI注入漏洞|反序列化|[MPS-2023-3834](https://www.oscs1024.com/hd/MPS-2023-3834)|CVE-2023-25194|高危|
|Eclipse Jetty 资源管理错误漏洞|拒绝服务|[MPS-2023-4997](https://www.oscs1024.com/hd/MPS-2023-4997)|CVE-2023-26048|中危|
|Eclipse Jetty 信息泄露漏洞|XSS|[MPS-2023-4998](https://www.oscs1024.com/hd/MPS-2023-4998)|CVE-2023-26049|中危|
|netplex json-smart 安全漏洞|未经控制的递归|[MPS-2023-7760](https://www.oscs1024.com/hd/MPS-2023-7760)|CVE-2023-1370|高危|
|Jettison 安全漏洞|未经控制的递归|[MPS-2023-8270](https://www.oscs1024.com/hd/MPS-2023-8270)|CVE-2023-1436|高危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Spring Kafka 反序列化漏洞|反序列化|[MPS-fed8-ocuv](https://www.oscs1024.com/hd/MPS-fed8-ocuv)|CVE-2023-34040|中危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|Apache Tomcat FORM 重定向漏洞|跨站重定向|[MPS-uy56-j8e4](https://www.oscs1024.com/hd/MPS-uy56-j8e4)|CVE-2023-41080|低危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.apache.tomcat.embed:tomcat-embed-core|8.5.23|11.0.0-m6|直接依赖|强烈建议修复|C:2|H:11|M:9|L:2|
|org.apache.tomcat.embed:tomcat-embed-core|8.5.31|11.0.0-m6|间接依赖|强烈建议修复|C:2|H:11|M:7|L:2|
|org.springframework.data:spring-data-commons|1.13.8.RELEASE|2.0.6.RELEASE|直接依赖|建议修复|C:1|H:1|M:0|L:0|
|org.springframework:spring-context|5.0.7.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.squareup.retrofit2:retrofit|2.1.0|2.5.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.kafka:kafka-clients|3.1.2|3.4.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.nimbusds:oauth2-oidc-sdk|5.24.1|9.3.1|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.7.2|2.14.0-rc1|直接依赖|建议修复|C:24|H:38|M:5|L:0|
|com.squareup.okio:okio-jvm|3.2.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|net.minidev:json-smart|2.2.1|2.4.9|间接依赖|建议修复|C:1|H:2|M:0|L:0|
|io.netty:netty-handler|4.1.51.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.9.8|2.14.0-rc1|间接依赖|建议修复|C:14|H:36|M:5|L:0|
|org.yaml:snakeyaml|1.19|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|org.apache.commons:commons-compress|1.20|1.21|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|net.minidev:json-smart|1.1.1|2.4.9|直接依赖|建议修复|C:1|H:2|M:0|L:0|
|org.springframework:spring-web|5.0.7.RELEASE|6.0.0|间接依赖|建议修复|C:1|H:3|M:1|L:0|
|com.squareup.okio:okio|1.8.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.hibernate:hibernate-validator|5.3.5.Final|6.1.3.Final|直接依赖|建议修复|C:0|H:1|M:2|L:0|
|com.nimbusds:oauth2-oidc-sdk|6.5|9.3.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-codec|4.1.28.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|org.yaml:snakeyaml|1.28|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|com.fasterxml.jackson.core:jackson-databind|2.9.6|2.14.0-rc1|直接依赖|建议修复|C:21|H:36|M:5|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.5|2.14.0-rc1|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-context|4.3.12.RELEASE|5.3.19|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|net.minidev:json-smart|2.4.8|2.4.9|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.xerial.snappy:snappy-java|1.1.8.1|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|net.minidev:json-smart|2.3|2.4.9|直接依赖|建议修复|C:1|H:2|M:0|L:0|
|io.netty:netty-handler|4.1.28.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|net.minidev:json-smart|2.4.2|2.4.9|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|org.apache.kafka:kafka-clients|3.0.2|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.xmlbeam:xmlprojector|1.4.12|1.4.15|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.30|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|com.nimbusds:oauth2-oidc-sdk|5.18.1|9.3.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-beans|4.3.12.RELEASE|5.3.20|直接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework:spring-webmvc|4.3.12.RELEASE|6.0.7|直接依赖|建议修复|C:0|H:2|M:1|L:0|
|ch.qos.logback:logback-core|1.2.3|1.2.8|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.0.3.RELEASE|3.0.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.17|2.0|直接依赖|建议修复|C:0|H:3|M:4|L:1|
|net.minidev:json-smart|1.3.1|2.4.9|直接依赖|建议修复|C:1|H:2|M:0|L:0|
|com.squareup.okio:okio-jvm|3.0.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.squareup.okio:okio|1.15.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.owasp.esapi:esapi|2.0.1|2.3.0.0|间接依赖|建议修复|C:0|H:1|M:3|L:1|
|com.fasterxml.jackson.core:jackson-databind|2.8.10|2.14.0-rc1|直接依赖|建议修复|C:24|H:38|M:5|L:0|
|org.xerial.snappy:snappy-java|1.1.8.4|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|io.netty:netty-handler|4.1.48.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|io.netty:netty-codec-http|4.1.28.Final|4.1.86.final|间接依赖|建议修复|C:2|H:2|M:5|L:0|
|ch.qos.logback:logback-core|1.1.11|1.2.8|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.bouncycastle:bcprov-jdk15on|1.51|1.69|直接依赖|建议修复|C:0|H:6|M:7|L:1|
|io.netty:netty-codec|4.1.51.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|com.squareup.okio:okio|3.2.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.codehaus.jettison:jettison|1.1|1.5.4|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|io.netty:netty-handler|4.1.94.Final|4.1.94.final|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.78|11.0.0-m6|间接依赖|建议修复|C:0|H:0|M:0|L:1|
|org.codehaus.jackson:jackson-mapper-asl|1.9.2||间接依赖|建议修复|C:1|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.29|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|org.springframework:spring-web|5.3.29|6.0.0|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.graalvm.sdk:graal-sdk|22.0.0.2|22.3.3|直接依赖|建议修复|C:0|H:4|M:7|L:9|
|org.codehaus.groovy:groovy-all|2.4.0|2.4.4|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.fasterxml.woodstox:woodstox-core|5.0.3|6.4.0|间接依赖|建议修复|C:0|H:3|M:1|L:1|
|org.springframework.boot:spring-boot|1.5.8.RELEASE|2.2.11.RELEASE|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.squareup.okio:okio|1.9.0|3.4.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-web|4.3.12.RELEASE|6.0.0|直接依赖|建议修复|C:1|H:2|M:2|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.8.3|2.14.0-rc1|直接依赖|建议修复|C:26|H:38|M:5|L:0|
|ch.qos.logback:logback-classic|1.1.11|1.2.0|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.nimbusds:nimbus-jose-jwt|3.1.2|7.8.1|直接依赖|建议修复|C:0|H:3|M:1|L:1|
|org.springframework:spring-beans|5.0.7.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.apache.santuario:xmlsec|1.5.7|2.2.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|commons-collections:commons-collections|3.2.1|3.2.2|间接依赖|建议修复|C:1|H:2|M:0|L:0|
|org.springframework:spring-core|4.3.12.RELEASE|6.0.7|直接依赖|建议修复|C:0|H:1|M:2|L:0|
|org.springframework.boot:spring-boot|2.0.3.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-codec|4.1.48.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|com.squareup.okio:okio|2.8.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-server|9.4.51.v20230217|12.0.0.beta0|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.google.code.gson:gson|2.8.6|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-core|2.7.2|2.8.6|直接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.bouncycastle:bcprov-jdk15on|1.68|1.69|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.bouncycastle:bcprov-jdk15on|1.69||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.json:json|20140107|20180130|直接依赖|可选修复|C:0|H:1|M:0|L:0|
|io.netty:netty-common|4.1.28.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-core|5.3.23|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.jsoup:jsoup|1.8.3|1.15.3|直接依赖|可选修复|C:0|H:1|M:1|L:0|
|com.h2database:h2|2.1.214||直接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.guava:guava|31.0.1-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.json:json|20080701|20180130|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.hibernate.validator:hibernate-validator|6.0.10.Final|6.1.3.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|27.0.1-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:1|
|org.springframework:spring-expression|5.0.7.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.apache.httpcomponents:httpclient|4.0.1|4.5.13|间接依赖|可选修复|C:0|H:0|M:4|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.0.3.RELEASE|3.0.7|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|commons-codec:commons-codec|1.10|1.13|直接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.springframework.boot:spring-boot-autoconfigure|1.5.8.RELEASE|3.0.7|直接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.httpcomponents:httpclient|4.5.2|4.5.13|直接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|19.0|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:2|L:1|
|org.bouncycastle:bcprov-jdk15on|1.70||直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.bouncycastle:bcprov-jdk15on|1.64|1.69|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|io.netty:netty-codec-http|4.1.48.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:5|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.7.5|3.0.7|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-expression|4.3.12.RELEASE|6.0.8|直接依赖|可选修复|C:0|H:1|M:1|L:0|
|commons-codec:commons-codec|1.7|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.eclipse.jetty:jetty-http|9.4.51.v20230217|11.0.10|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.9.6|2.9.8|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-codec:commons-codec|1.11|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|com.google.guava:guava|24.1.1-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:1|
|com.google.guava:guava|20.0|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:2|L:1|
|io.netty:netty-transport-native-epoll|4.1.48.Final|4.1.59.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-codec:commons-codec|1.3|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|com.fasterxml.jackson.core:jackson-core|2.6.0|2.8.6|直接依赖|可选修复|C:0|H:0|M:2|L:0|
|io.netty:netty-common|4.1.51.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.fasterxml.jackson.core:jackson-core|2.8.3|2.8.6|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-transport-native-epoll|4.1.51.Final|4.1.59.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.glassfish.jersey.core:jersey-common|2.30.1|3.0.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.httpcomponents:httpclient|4.5.3|4.5.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|5.3.23|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework.kafka:spring-kafka|2.8.11|3.0.10|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|ca.juliusdavies:not-yet-commons-ssl|0.3.9|0.3.15|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-codec:commons-codec|1.9|1.13|直接依赖|可选修复|C:0|H:0|M:0|L:1|
|com.google.code.gson:gson|2.8.2|2.8.9|直接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.code.gson:gson|2.2.4|2.8.9|直接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.code.gson:gson|2.8.0|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|commons-io:commons-io|2.6|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-http|4.1.51.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:5|L:0|
|commons-httpclient:commons-httpclient|3.1||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.opensaml:opensaml|2.6.4|2.6.5|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-common|4.1.48.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|610|Low|
|ISC|16|Low|
|MIT|406|Low|
|自定义许可证|62|Low|
|BSD-3-Clause|9|Low|
|EPL-2.0|17|Low|
|EPL-1.0|20|Low|
|MPL-2.0|2|Low|
|BSD-2-Clause|8|Low|
|MIT-0|1|Low|
|WTFPL|2|Low|
|LGPL-2.1|8|Medium|
|UPL-1.0|2|Low|
|LGPL-2.1-or-later|2|Low|
|GPL-2.0|1|Medium|
|MPL-1.1|5|Low|
|CDDL-1.0|1|Low|
|JSON|2|Low|
|CDDL-1.1|4|Low|
|LGPL-2.1+|1|Low|
|Python-2.0|1|Low|
|LGPL-2.1-only|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.apache.kafka:kafka-clients|3.1.2|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.5|直接依赖|maven|
|org.yaml:snakeyaml|1.17|直接依赖|maven|
|once|1.4.0|间接依赖|npm|
|org.springframework.integration:spring-integration-core|5.5.12|间接依赖|maven|
|com.azure:azure-core|1.43.0-beta.1|直接依赖|maven|
|com.thetransactioncompany:jsonrpc2-base|2.0|间接依赖|maven|
|org.springframework.boot:spring-boot|1.5.8.RELEASE|直接依赖|maven|
|dot-prop|5.3.0|间接依赖|npm|
|com.azure.tools:azure-autorest-extension|1.0.0-beta.4|间接依赖|maven|
|io.netty:netty-transport|4.1.51.Final|间接依赖|maven|
|org.apache.commons:commons-collections4|4.1|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|8.5.31|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.2|间接依赖|maven|
|@cspell/dict-python|4.1.2|间接依赖|npm|
|com.azure:azure-identity|1.11.0-beta.1|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-eventhubs|2.30.0|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.21.9|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.75|间接依赖|maven|
|org.springframework.integration:spring-integration-jmx|5.5.18|间接依赖|maven|
|find-up|5.0.0|间接依赖|npm|
|io.netty:netty-transport-classes-kqueue|4.1.94.Final|间接依赖|maven|
|fill-range|7.0.1|间接依赖|npm|
|fast-equals|4.0.3|间接依赖|npm|
|io.netty:netty-handler-proxy|4.1.48.Final|间接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-otlp|1.28.0|间接依赖|maven|
|org.springframework.integration:spring-integration-core|5.5.18|直接依赖|maven|
|org.glassfish.hk2:hk2-utils|2.6.1|间接依赖|maven|
|com.google.code.findbugs:jsr305|1.3.9|直接依赖|maven|
|path-exists|4.0.0|间接依赖|npm|
|com.typesafe.netty:netty-reactive-streams|2.0.4|间接依赖|maven|
|com.azure:azure-communication-sms|1.2.0-beta.1|直接依赖|maven|
|com.azure:azure-messaging-eventgrid-cloudnative-cloudevents|1.0.0-beta.2|直接依赖|maven|
|core-util-is|1.0.3|间接依赖|npm|
|com.microsoft.azure:azure-keyvault-core|1.0.0|间接依赖|maven|
|resolve-global|1.0.0|间接依赖|npm|
|commons-io:commons-io|2.6|间接依赖|maven|
|org.springframework:spring-context|5.3.24|间接依赖|maven|
|com.azure.spring:spring-cloud-azure-starter-servicebus-jms|4.12.0-beta.1|直接依赖|maven|
|org.apache.qpid:proton-j|0.33.4|间接依赖|maven|
|lru-cache|6.0.0|间接依赖|npm|
|org.slf4j:jul-to-slf4j|1.7.25|直接依赖|maven|
|com.azure:azure-security-keyvault-secrets|4.7.0-beta.1|直接依赖|maven|
|io.dropwizard.metrics:metrics-jvm|4.1.0|直接依赖|maven|
|com.azure.spring:spring-cloud-azure-appconfiguration-config-web|4.12.0-beta.1|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.9.0|直接依赖|maven|
|com.squareup.retrofit2:retrofit|2.7.2|间接依赖|maven|
|com.github.tomakehurst:wiremock-jre8-standalone|2.35.0|直接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.64|间接依赖|maven|
|xdg-basedir|4.0.0|间接依赖|npm|
|javax.annotation:javax.annotation-api|1.2|间接依赖|maven|
|org.apache.commons:commons-dbcp2|2.9.0|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-servicebus|2.31.0-beta.1|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-containerinstance|2.31.0-beta.1|直接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-common|1.28.0|间接依赖|maven|
|@cspell/dict-cryptocurrencies|3.0.1|间接依赖|npm|
|org.threeten:threetenbp|1.3.6|直接依赖|maven|
|io.projectreactor.netty.incubator:reactor-netty-incubator-quic|0.0.23|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.5|直接依赖|maven|
|org.codehaus.janino:commons-compiler|3.0.6|间接依赖|maven|
|org.apache.commons:commons-compress|1.22|直接依赖|maven|
|com.squareup.okio:okio|1.8.0|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|2.8|间接依赖|maven|
|array-timsort|1.0.3|间接依赖|npm|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.7.14|直接依赖|maven|
|org.eclipse.jetty:jetty-server|9.4.51.v20230217|直接依赖|maven|
|com.nimbusds:oauth2-oidc-sdk|6.5|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.28.Final|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.21|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.10.3|间接依赖|maven|
|cspell-gitignore|6.31.2|间接依赖|npm|
|org.springframework.boot:spring-boot-starter-jdbc|2.7.14|间接依赖|maven|
|glob-parent|5.1.2|间接依赖|npm|
|io.projectreactor:reactor-scala-extensions_2.12|0.8.0|直接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-spring-boot|1.28.0-alpha|间接依赖|maven|
|com.azure:azure-core|1.42.0|直接依赖|maven|
|com.azure:azure-iot-deviceupdate|1.1.0-beta.1|直接依赖|maven|
|com.microsoft.azure:azure-annotations|1.5.1|直接依赖|maven|
|org.apache.maven:maven-plugin-api|3.8.6|直接依赖|maven|
|io.fabric8:kubernetes-model-discovery|5.12.3|间接依赖|maven|
|com.microsoft.azure:azure-documentdb|1.13.0|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.5|直接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.94.Final|直接依赖|maven|
|com.fasterxml:classmate|1.3.1|直接依赖|maven|
|org.apache.maven:maven-project|2.2.1|直接依赖|maven|
|io.zipkin.reporter2:zipkin-reporter|2.16.3|间接依赖|maven|
|javax.ws.rs:jsr311-api|1.1.1|间接依赖|maven|
|tr46|0.0.3|间接依赖|npm|
|org.json:json|20080701|间接依赖|maven|
|com.azure.spring:spring-cloud-azure-service|4.11.0|直接依赖|maven|
|com.azure:azure-aot-graalvm-support|1.0.0-beta.4|直接依赖|maven|
|com.microsoft.azure:azure-client-authentication|1.2.2-SNAPSHOT|直接依赖|maven|
|io.fabric8:kubernetes-model-extensions|5.12.3|间接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|9.31|直接依赖|maven|
|supports-color|7.2.0|间接依赖|npm|
|org.springframework.cloud:spring-cloud-stream-binder-kafka-core|3.2.9|间接依赖|maven|
|com.azure.spring:spring-cloud-azure-starter-keyvault-certificates|4.12.0-beta.1|直接依赖|maven|
|net.sf.saxon:Saxon-HE|10.6|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.2.0|间接依赖|maven|
|com.microsoft.azure:adal4j|1.1.2|直接依赖|maven|
|com.github.luben:zstd-jni|1.5.0-4|间接依赖|maven|
|com.azure:azure-storage-file-datalake|12.17.0-beta.2|直接依赖|maven|
|net.minidev:accessors-smart|2.4.8|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.94.Final|间接依赖|maven|
|com.azure.spring:spring-cloud-azure-trace-sleuth|4.12.0-beta.1|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.7.14|间接依赖|maven|
|org.codehaus.jettison:jettison|1.1|间接依赖|maven|
|com.microsoft.rest:client-runtime|1.7.3|间接依赖|maven|
|com.squareup.okhttp3:okhttp|3.12.12|间接依赖|maven|
|joda-time:joda-time|2.7|直接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|org.reflections:reflections|0.10.2|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.1|直接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.48.Final|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.69|间接依赖|maven|
|org.apache.tomcat:tomcat-annotations-api|8.5.23|间接依赖|maven|
|org.springframework:spring-jms|5.3.29|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-validation|2.6.15|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-core|1.0.33|间接依赖|maven|
|org.hibernate:hibernate-validator|5.3.5.Final|直接依赖|maven|
|net.java.dev.jna:jna-platform|5.6.0|直接依赖|maven|
|io.projectreactor.netty:reactor-netty-core|1.0.34|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|8.5.23|直接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|直接依赖|maven|
|org.springframework:spring-context|5.3.27|间接依赖|maven|
|io.netty:netty-common|4.1.48.Final|间接依赖|maven|
|io.fabric8:kubernetes-client|5.12.3|直接依赖|maven|
|org.apache.commons:commons-compress|1.21|间接依赖|maven|
|org.glassfish.hk2:hk2-api|2.6.1|间接依赖|maven|
|com.azure.spring:spring-cloud-azure-actuator|4.12.0-beta.1|直接依赖|maven|
|org.apache.maven:maven-model|3.8.6|间接依赖|maven|
|ansi-regex|5.0.1|间接依赖|npm|
|com.github.javaparser:javaparser-core|3.24.2|直接依赖|maven|
|cspell-lib|6.31.2|间接依赖|npm|
|org.springframework.boot:spring-boot-starter|2.0.3.RELEASE|间接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.70|直接依赖|maven|
|commons-codec:commons-codec|1.10|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-network|2.31.0-beta.1|直接依赖|maven|
|net.minidev:accessors-smart|2.4.2|间接依赖|maven|
|org.fusesource.jansi:jansi|1.9|直接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|9.30.2|间接依赖|maven|
|com.azure:azure-messaging-eventhubs-checkpointstore-blob|1.16.9|直接依赖|maven|
|org.asynchttpclient:async-http-client|2.12.1|直接依赖|maven|
|com.microsoft.azure:azure-eventhubs|3.4.0-beta.1|直接依赖|maven|
|org.springframework.data:spring-data-redis|2.7.14|直接依赖|maven|
|com.google.code.gson:gson|2.8.2|直接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.1|间接依赖|maven|
|org.springframework:spring-aop|4.3.12.RELEASE|间接依赖|maven|
|@cspell/dict-elixir|4.0.3|间接依赖|npm|
|com.azure.resourcemanager:azure-resourcemanager-eventhubs|2.31.0-beta.1|直接依赖|maven|
|com.azure:azure-core-http-netty|1.14.0-beta.2|直接依赖|maven|
|fast-glob|3.3.0|间接依赖|npm|
|org.eclipse.jetty:jetty-servlet|9.4.51.v20230217|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.8|间接依赖|maven|
|@cspell/dict-dart|2.0.2|间接依赖|npm|
|org.junit.platform:junit-platform-commons|1.9.3|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-appplatform|2.31.0-beta.1|直接依赖|maven|
|error-ex|1.3.2|间接依赖|npm|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.5.31|间接依赖|maven|
|is-extglob|2.1.1|间接依赖|npm|
|org.apache.logging.log4j:log4j-core|2.17.2|直接依赖|maven|
|net.oneandone.reflections8:reflections8|0.11.7|直接依赖|maven|
|org.springframework:spring-beans|4.3.12.RELEASE|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-containerregistry|2.30.0|直接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.14|直接依赖|maven|
|org.checkerframework:checker-qual|3.33.0|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-msi|2.30.0|间接依赖|maven|
|org.eclipse.jetty:jetty-util-ajax|9.4.51.v20230217|间接依赖|maven|
|backport-util-concurrent:backport-util-concurrent|3.1|间接依赖|maven|
|org.springframework.cloud:spring-cloud-commons|3.1.7|间接依赖|maven|
|vscode-uri|3.0.7|间接依赖|npm|
|org.awaitility:awaitility|4.2.0|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.11|间接依赖|maven|
|commons-codec:commons-codec|1.15|直接依赖|maven|
|io.projectreactor:reactor-test|3.4.30|间接依赖|maven|
|minimatch|3.1.2|间接依赖|npm|
|com.azure:azure-mixedreality-remoterendering|1.2.0-beta.1|直接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.93.Final|间接依赖|maven|
|io.netty:netty-codec|4.1.51.Final|间接依赖|maven|
|io.fabric8:kubernetes-model-storageclass|5.12.3|间接依赖|maven|
|com.google.googlejavaformat:google-java-format|1.0.0-beta.1|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-authorization|2.31.0-beta.1|直接依赖|maven|
|com.squareup.okhttp3:okhttp-urlconnection|3.4.2|直接依赖|maven|
|com.azure:azure-messaging-eventhubs-checkpointstore-jedis|1.0.0-beta.2|直接依赖|maven|
|parse-json|5.2.0|间接依赖|npm|
|org.springframework.boot:spring-boot|2.7.5|间接依赖|maven|
|io.opentelemetry:opentelemetry-context|1.28.0|间接依赖|maven|
|cspell-trie-lib|6.31.1|间接依赖|npm|
|com.azure.resourcemanager:azure-resourcemanager-containerservice|2.30.0|间接依赖|maven|
|org.jsoup:jsoup|1.8.3|直接依赖|maven|
|com.azure.spring:spring-cloud-azure-starter-data-cosmos|4.12.0-beta.1|直接依赖|maven|
|lines-and-columns|1.2.4|间接依赖|npm|
|com.azure:azure-core-tracing-opentelemetry|1.0.0-beta.38|直接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-sender-okhttp|1.28.0|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.0.1|间接依赖|maven|
|org.springframework:spring-beans|5.3.23|间接依赖|maven|
|com.azure:azure-cosmos|4.49.0|直接依赖|maven|
|@cspell/dict-bash|4.1.1|间接依赖|npm|
|org.jruby.jcodings:jcodings|1.0.46|间接依赖|maven|
|com.squareup.retrofit2:retrofit|2.1.0|直接依赖|maven|
|org.springframework:spring-core|5.3.23|间接依赖|maven|
|org.springframework.cloud:spring-cloud-stream|3.2.9|直接依赖|maven|
|org.ow2.asm:asm|8.0.1|间接依赖|maven|
|@cspell/dict-gaming-terms|1.0.4|间接依赖|npm|
|com.azure:azure-core-metrics-opentelemetry|1.0.0-beta.11|直接依赖|maven|
|com.azure:azure-core-amqp|2.9.0-beta.6|直接依赖|maven|
|com.azure:azure-security-keyvault-administration|4.4.0-beta.1|直接依赖|maven|
|com.microsoft.azure:msal4j|1.13.9|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.5|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-trafficmanager|2.31.0-beta.1|直接依赖|maven|
|com.nimbusds:oauth2-oidc-sdk|9.35|间接依赖|maven|
|io.netty:netty-codec|4.1.28.Final|间接依赖|maven|
|com.squareup.okhttp3:okhttp|4.10.0|直接依赖|maven|
|io.fabric8:kubernetes-model-core|5.12.3|间接依赖|maven|
|io.netty:netty-codec-http|4.1.28.Final|间接依赖|maven|
|com.microsoft.azure:applicationinsights-core|3.4.1|直接依赖|maven|
|net.jodah:typetools|0.6.2|间接依赖|maven|
|net.minidev:accessors-smart|2.4.9|间接依赖|maven|
|com.azure.spring:spring-cloud-azure-service|4.12.0-beta.1|直接依赖|maven|
|flat-cache|3.0.4|间接依赖|npm|
|com.microsoft.azure:azure-client-runtime|1.7.3|间接依赖|maven|
|com.azure:azure-security-keyvault-secrets|4.6.5|直接依赖|maven|
|js-yaml|4.1.0|间接依赖|npm|
|io.netty.incubator:netty-incubator-codec-classes-quic|0.0.48.Final|间接依赖|maven|
|io.fabric8:kubernetes-model-coordination|5.12.3|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.7.14|间接依赖|maven|
|org.khronos:opengl-api|gl1.1-android-2.1_r1|间接依赖|maven|
|com.microsoft.azure:azure-mgmt-resources|1.5.1|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-containerservice|2.31.0-beta.1|直接依赖|maven|
|com.microsoft.azure:azure-mgmt-resources|1.3.0|直接依赖|maven|
|com.microsoft.rest:client-runtime|1.2.1|间接依赖|maven|
|com.azure.spring:spring-cloud-azure-feature-management-web|4.12.0-beta.1|直接依赖|maven|
|org.opensaml:xmltooling|1.4.4|间接依赖|maven|
|org.springframework:spring-jdbc|5.3.29|间接依赖|maven|
|info.picocli:picocli|4.6.2|间接依赖|maven|
|io.micrometer:micrometer-core|1.0.5|间接依赖|maven|
|com.google.code.gson:gson|2.2.4|直接依赖|maven|
|has-flag|4.0.0|间接依赖|npm|
|org.jboss.logging:jboss-logging|3.4.1.Final|间接依赖|maven|
|com.squareup.okio:okio|3.2.0|间接依赖|maven|
|com.azure.spring:spring-cloud-azure-resourcemanager|4.12.0-beta.1|直接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.94.Final|间接依赖|maven|
|io.reactivex.rxjava2:rxjava|2.2.0|间接依赖|maven|
|org.cryptomator:siv-mode|1.4.4|直接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.17|间接依赖|maven|
|write-file-atomic|3.0.3|间接依赖|npm|
|org.glassfish.hk2:hk2-locator|2.6.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.8.0|直接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.0.10.Final|间接依赖|maven|
|com.squareup.retrofit2:converter-jackson|2.6.4|间接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.94.Final|直接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-bootstrap|3.1.7|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.6|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.6.21|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.6|直接依赖|maven|
|@cspell/dict-companies|3.0.17|间接依赖|npm|
|@cspell/cspell-types|6.31.1|间接依赖|npm|
|com.github.spotbugs:spotbugs-annotations|4.2.2|直接依赖|maven|
|com.microsoft.azure:azure-keyvault-core|1.3.0-beta.1|直接依赖|maven|
|org.hibernate.javax.persistence:hibernate-jpa-2.1-api|1.0.0.Final|直接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.1|间接依赖|maven|
|@cspell/dict-filetypes|3.0.1|间接依赖|npm|
|org.springframework:spring-messaging|5.3.27|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|1.5.8.RELEASE|直接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|javax.validation:validation-api|1.1.0.Final|直接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|org.eclipse.jetty:jetty-http|9.4.51.v20230217|间接依赖|maven|
|org.springframework:spring-core|5.3.27|间接依赖|maven|
|com.azure.spring:spring-cloud-azure-actuator-autoconfigure|4.12.0-beta.1|直接依赖|maven|
|com.squareup.okio:okio|2.8.0|间接依赖|maven|
|com.microsoft.azure:qpid-proton-j-extensions|1.2.4|直接依赖|maven|
|org.springframework.security:spring-security-crypto|5.7.10|间接依赖|maven|
|org.graalvm.sdk:graal-sdk|22.0.0.2|直接依赖|maven|
|com.azure:azure-cosmos|4.50.0-beta.1|直接依赖|maven|
|com.azure:azure-monitor-query|1.3.0-beta.2|直接依赖|maven|
|com.azure.spring:spring-cloud-azure-stream-binder-servicebus|4.12.0-beta.1|直接依赖|maven|
|@cspell/dict-r|2.0.1|间接依赖|npm|
|com.squareup.okhttp3:logging-interceptor|3.3.1|间接依赖|maven|
|org.springframework:spring-tx|5.3.29|直接依赖|maven|
|org.springframework:spring-expression|5.0.7.RELEASE|间接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-kafka-clients-2.6|1.28.0-alpha|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.0.12|直接依赖|maven|
|org.springframework.data:spring-data-keyvalue|2.7.14|间接依赖|maven|
|inflight|1.0.6|间接依赖|npm|
|org.postgresql:postgresql|42.3.8|直接依赖|maven|
|com.azure:azure-communication-chat|1.4.0-beta.1|直接依赖|maven|
|com.microsoft.azure:azure-client-authentication|1.7.3|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|org.bouncycastle:bcutil-jdk15on|1.70|间接依赖|maven|
|org.codehaus.janino:janino|2.7.8|直接依赖|maven|
|com.github.docker-java:docker-java|3.2.1|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-appplatform|2.30.0|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.78|间接依赖|maven|
|org.glassfish.jersey.core:jersey-client|2.30.1|间接依赖|maven|
|com.azure:azure-messaging-servicebus|7.15.0-beta.4|直接依赖|maven|
|com.azure:azure-digitaltwins-core|1.4.0-beta.1|直接依赖|maven|
|@cspell/dict-aws|3.0.0|间接依赖|npm|
|javax.mail:mail|1.4.7|直接依赖|maven|
|net.minidev:accessors-smart|1.1|直接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.6.15|间接依赖|maven|
|io.netty:netty-handler|4.1.48.Final|间接依赖|maven|
|com.azure:azure-core-experimental|1.0.0-beta.43|直接依赖|maven|
|org.springframework.cloud:spring-cloud-sleuth-api|3.1.9|直接依赖|maven|
|ch.qos.logback:logback-classic|1.1.11|直接依赖|maven|
|com.azure:azure-communication-phonenumbers|1.2.0-beta.1|直接依赖|maven|
|com.azure.spring:spring-cloud-azure-starter-storage-blob|4.12.0-beta.1|直接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.51|直接依赖|maven|
|org.springframework:spring-beans|5.0.7.RELEASE|间接依赖|maven|
|io.netty:netty-transport|4.1.28.Final|间接依赖|maven|
|com.azure:azure-core-management|1.12.0-beta.1|直接依赖|maven|
|net.java.dev.jna:jna-platform|5.13.0|间接依赖|maven|
|org.revapi:revapi-java-spi|0.23.6|直接依赖|maven|
|rimraf|3.0.2|间接依赖|npm|
|org.apache.maven:maven-repository-metadata|2.2.1|间接依赖|maven|
|org.yaml:snakeyaml|1.29|间接依赖|maven|
|com.azure:azure-json|1.1.0|直接依赖|maven|
|com.rabbitmq:amqp-client|5.5.3|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-cdn|2.31.0-beta.1|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.10.3|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk|1.28.0|直接依赖|maven|
|org.springframework:spring-messaging|5.3.20|间接依赖|maven|
|@cspell/dict-scala|5.0.0|间接依赖|npm|
|org.springframework:spring-webmvc|4.3.12.RELEASE|直接依赖|maven|
|org.graalvm.nativeimage:pointsto|22.0.0.2|间接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-instrumentation-annotations-support|1.28.0-alpha|间接依赖|maven|
|org.checkerframework:checker-qual|2.5.2|间接依赖|maven|
|org.springframework:spring-expression|5.3.23|间接依赖|maven|
|org.apache.avro:avro|1.11.0|直接依赖|maven|
|org.opensaml:opensaml|2.6.4|直接依赖|maven|
|io.projectreactor:reactor-test|3.4.31|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-network|2.30.0|间接依赖|maven|
|org.springframework:spring-expression|5.3.29|直接依赖|maven|
|com.azure:azure-analytics-synapse-spark|1.0.0-beta.6|直接依赖|maven|
|braces|3.0.2|间接依赖|npm|
|commons-logging:commons-logging|1.2|直接依赖|maven|
|org.apache.commons:commons-compress|1.20|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-http|1.0.34|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-privatedns|2.30.0|间接依赖|maven|
|escape-string-regexp|1.0.5|直接依赖|npm|
|com.github.stephenc.jcip:jcip-annotations|1.0-1|直接依赖|maven|
|org.antlr:antlr4-runtime|4.9.3|间接依赖|maven|
|com.beust:jcommander|1.78|直接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.93.Final|间接依赖|maven|
|org.springframework:spring-core|5.3.29|直接依赖|maven|
|org.revapi.classif:classif-dsl|0.1.0|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-containerinstance|2.30.0|间接依赖|maven|
|io.opentelemetry:opentelemetry-api-logs|1.26.0-alpha|直接依赖|maven|
|com.azure:azure-core-serializer-avro-apache|1.0.0-beta.39|直接依赖|maven|
|com.googlecode.javaewah:JavaEWAH|0.7.9|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.10|间接依赖|maven|
|com.azure:azure-ai-textanalytics|5.4.0-beta.1|直接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.14|直接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.48.Final|间接依赖|maven|
|@cspell/dynamic-import|6.31.1|间接依赖|npm|
|org.springframework.cloud:spring-cloud-commons|3.1.3|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.7.20-Beta|间接依赖|maven|
|io.fabric8:kubernetes-model-scheduling|5.12.3|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.30|间接依赖|maven|
|crypto-random-string|2.0.0|间接依赖|npm|
|org.springframework.boot:spring-boot-starter|2.7.5|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-joda|2.10.1|间接依赖|maven|
|org.yaml:snakeyaml|1.30|间接依赖|maven|
|com.jayway.jsonpath:json-path|2.2.0|直接依赖|maven|
|@cspell/strong-weak-map|6.31.1|间接依赖|npm|
|com.microsoft.azure:applicationinsights-core|2.6.4|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-search|2.30.0|间接依赖|maven|
|io.vavr:vavr-match|0.9.1|间接依赖|maven|
|com.microsoft.azure:azure-keyvault-webkey|1.3.0-beta.1|直接依赖|maven|
|org.springframework.cloud:spring-cloud-context|3.1.7|直接依赖|maven|
|com.azure:azure-storage-blob|12.23.1|直接依赖|maven|
|net.minidev:json-smart|2.3|直接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|直接依赖|maven|
|@cspell/dict-java|5.0.5|间接依赖|npm|
|org.ow2.asm:asm|9.3|间接依赖|maven|
|org.codehaus.janino:commons-compiler|2.7.8|间接依赖|maven|
|com.azure:perf-test-core|1.0.0-beta.1|直接依赖|maven|
|org.codehaus.plexus:plexus-interpolation|1.11|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.7.14|直接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|org.apache.maven:maven-artifact|3.8.6|间接依赖|maven|
|io.netty:netty-codec-http|4.1.48.Final|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.25|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager|2.30.0|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.7.20-Beta|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-monitor|2.30.0|间接依赖|maven|
|color-convert|2.0.1|间接依赖|npm|
|org.springframework.security:spring-security-oauth2-jose|5.7.10|直接依赖|maven|
|io.projectreactor:reactor-core|3.4.29|间接依赖|maven|
|com.azure:azure-monitor-opentelemetry-exporter|1.0.0-beta.12|直接依赖|maven|
|@cspell/dict-powershell|5.0.2|间接依赖|npm|
|org.yaml:snakeyaml|1.28|间接依赖|maven|
|com.microsoft.rest:client-runtime|1.7.14|间接依赖|maven|
|org.bouncycastle:bcutil-jdk15on|1.69|间接依赖|maven|
|io.fabric8:kubernetes-model-events|5.12.3|间接依赖|maven|
|io.netty:netty-common|4.1.94.Final|直接依赖|maven|
|org.springframework:spring-context|5.3.23|间接依赖|maven|
|org.apache.commons:commons-pool2|2.11.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.5|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.22|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.2|直接依赖|maven|
|callsites|3.1.0|间接依赖|npm|
|org.springframework.boot:spring-boot-starter-validation|2.7.14|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-cdn|2.30.0|间接依赖|maven|
|org.springframework:spring-context|5.3.29|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.6.15|间接依赖|maven|
|ansi-styles|4.3.0|间接依赖|npm|
|com.sun.mail:javax.mail|1.6.1|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|com.azure:azure-storage-queue|12.18.1|直接依赖|maven|
|io.micrometer:micrometer-core|1.9.12|间接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-logback-appender-1.0|1.28.0-alpha|直接依赖|maven|
|org.ow2.asm:asm|9.1|间接依赖|maven|
|org.springframework.security:spring-security-rsa|1.0.11.RELEASE|间接依赖|maven|
|io.fabric8:kubernetes-model-metrics|5.12.3|间接依赖|maven|
|com.azure.spring:spring-cloud-azure-starter-keyvault-secrets|4.12.0-beta.1|直接依赖|maven|
|org.springframework.security:spring-security-oauth2-core|5.7.10|间接依赖|maven|
|com.azure:azure-core-test|1.20.0-beta.1|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.3|间接依赖|maven|
|joda-time:joda-time|2.9.9|直接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.5|间接依赖|maven|
|com.microsoft.azure:azure-annotations|1.2.0|直接依赖|maven|
|org.springframework.retry:spring-retry|1.3.4|直接依赖|maven|
|com.nimbusds:lang-tag|1.6|间接依赖|maven|
|org.scala-lang:scala-library|2.11.7|直接依赖|maven|
|org.aspectj:aspectjweaver|1.9.7|间接依赖|maven|
|org.slf4j:slf4j-api|2.0.0-beta1|直接依赖|maven|
|com.azure:azure-core-http-okhttp|1.12.0-beta.1|直接依赖|maven|
|com.azure:azure-core-http-okhttp|1.11.12|直接依赖|maven|
|org.apache.maven:maven-settings|2.2.1|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.51.Final|间接依赖|maven|
|@cspell/dict-ruby|5.0.0|间接依赖|npm|
|org.apache.qpid:qpid-jms-client|0.53.0|直接依赖|maven|
|commons-codec:commons-codec|1.7|间接依赖|maven|
|io.netty:netty-codec-http|4.1.51.Final|间接依赖|maven|
|com.squareup.okio:okio-jvm|3.0.0|间接依赖|maven|
|org.springframework:spring-web|5.0.7.RELEASE|间接依赖|maven|
|com.azure:azure-analytics-synapse-accesscontrol|1.0.0-beta.5|直接依赖|maven|
|org.junit.jupiter:junit-jupiter-params|5.9.3|直接依赖|maven|
|com.azure:azure-core-experimental|1.0.0-beta.42|直接依赖|maven|
|org.springframework.security:spring-security-web|5.7.10|直接依赖|maven|
|org.apache.commons:commons-lang3|3.3.1|直接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|yallist|4.0.0|间接依赖|npm|
|make-dir|3.1.0|间接依赖|npm|
|javax.servlet:javax.servlet-api|4.0.1|直接依赖|maven|
|com.nimbusds:oauth2-oidc-sdk|5.24.1|直接依赖|maven|
|com.google.code.gson:gson|2.10|直接依赖|maven|
|io.fabric8:kubernetes-model-certificates|5.12.3|间接依赖|maven|
|com.microsoft.azure:adal4j|1.6.5|直接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-reactor-3.1|1.28.0-alpha|间接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-instrumentation-annotations|1.28.0|间接依赖|maven|
|com.azure:azure-storage-internal-avro|12.9.0-beta.2|直接依赖|maven|
|com.jcraft:jsch|0.1.55|直接依赖|maven|
|is-typedarray|1.0.0|间接依赖|npm|
|org.bouncycastle:bcpkix-jdk15on|1.68|间接依赖|maven|
|io.projectreactor:reactor-core|3.4.31|直接依赖|maven|
|org.springframework:spring-context|5.0.7.RELEASE|间接依赖|maven|
|com.azure:azure-core-amqp|2.8.8|直接依赖|maven|
|@cspell/dict-vue|3.0.0|间接依赖|npm|
|com.azure:azure-json|1.0.1|间接依赖|maven|
|com.azure:azure-communication-callingserver|1.0.0-beta.5|直接依赖|maven|
|com.azure:azure-security-keyvault-keys|4.7.0-beta.1|直接依赖|maven|
|com.nimbusds:content-type|2.2|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.10.0|间接依赖|maven|
|javax.annotation:jsr250-api|1.0|直接依赖|maven|
|@cspell/dict-php|4.0.1|间接依赖|npm|
|joda-time:joda-time|2.2|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-dns|2.30.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.8.3|间接依赖|maven|
|KERNEL32.dll||间接依赖||
|org.codehaus.mojo:animal-sniffer-annotations|1.10|直接依赖|maven|
|io.netty:netty-resolver|4.1.51.Final|间接依赖|maven|
|org.springframework.data:spring-data-jdbc|2.4.14|间接依赖|maven|
|com.squareup.retrofit2:adapter-rxjava|2.7.2|间接依赖|maven|
|io.fabric8:kubernetes-model-autoscaling|5.12.3|间接依赖|maven|
|com.mysema.commons:mysema-commons-lang|0.2.4|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.10.3|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.94.Final|直接依赖|maven|
|json-parse-even-better-errors|2.3.1|间接依赖|npm|
|io.projectreactor.netty:reactor-netty|1.0.34|直接依赖|maven|
|org.graalvm.nativeimage:objectfile|22.0.0.2|间接依赖|maven|
|com.azure:azure-storage-blob|12.24.0-beta.2|直接依赖|maven|
|org.springframework.retry:spring-retry|1.3.3|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-privatedns|2.31.0-beta.1|直接依赖|maven|
|net.minidev:json-smart|2.4.8|间接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.94.Final|间接依赖|maven|
|com.microsoft.rest:client-runtime|1.7.4|直接依赖|maven|
|org.jboss.logging:jboss-logging|3.3.2.Final|直接依赖|maven|
|org.lz4:lz4-java|1.7.1|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.18.0|间接依赖|maven|
|com.squareup.okhttp3:okhttp|4.11.0|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-common|1.28.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-jdbc|2.7.14|直接依赖|maven|
|com.azure.spring:spring-cloud-azure-core|4.11.0|间接依赖|maven|
|redis.clients:jedis|3.8.0|直接依赖|maven|
|com.nimbusds:oauth2-oidc-sdk|4.5|直接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.11|直接依赖|maven|
|com.azure.spring:spring-cloud-azure-starter-servicebus|4.12.0-beta.1|直接依赖|maven|
|com.azure:azure-sdk-template|1.2.2-beta.1|直接依赖|maven|
|com.azure:azure-sdk-template-two|1.0.0-beta.1|直接依赖|maven|
|org.checkerframework:checker-qual|3.5.0|间接依赖|maven|
|com.azure:azure-mixedreality-authentication|1.2.16|直接依赖|maven|
|com.google.guava:guava|24.1.1-jre|间接依赖|maven|
|io.vavr:vavr|0.9.1|直接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-spring-boot-starter|1.28.0-alpha|直接依赖|maven|
|com.microsoft.azure:azure-eventhubs-eph|3.3.0|直接依赖|maven|
|com.infradna.tool:bridge-method-annotation|1.13|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.94.Final|直接依赖|maven|
|com.azure:azure-core-management|1.11.4|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-compute|2.31.0-beta.1|直接依赖|maven|
|net.java.dev.jna:jna|5.13.0|间接依赖|maven|
|com.azure:azure-communication-identity|1.5.0-beta.1|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.10.5|间接依赖|maven|
|org.springframework.data:spring-data-commons|1.13.8.RELEASE|直接依赖|maven|
|org.hibernate.javax.persistence:hibernate-jpa-2.1-api|1.0.2.Final|直接依赖|maven|
|configstore|5.0.1|间接依赖|npm|
|io.projectreactor:reactor-core|3.4.30|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.10.5|间接依赖|maven|
|org.springframework:spring-expression|4.3.12.RELEASE|直接依赖|maven|
|org.xmlbeam:xmlprojector|1.4.12|直接依赖|maven|
|commons-logging:commons-logging|1.1.1|直接依赖|maven|
|io.netty:netty-resolver|4.1.94.Final|间接依赖|maven|
|net.minidev:json-smart|1.1.1|直接依赖|maven|
|io.opentelemetry:opentelemetry-api|1.28.0|直接依赖|maven|
|redis.clients:jedis|4.3.1|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.7.0|直接依赖|maven|
|fastq|1.15.0|间接依赖|npm|
|com.squareup.retrofit2:adapter-rxjava|2.6.4|间接依赖|maven|
|chalk|4.1.2|间接依赖|npm|
|com.microsoft.rest:client-runtime|1.0.0|间接依赖|maven|
|net.minidev:json-smart|1.3.1|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-resources|2.31.0-beta.1|直接依赖|maven|
|org.springframework:spring-aop|5.3.29|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-extension-autoconfigure-spi|1.28.0|直接依赖|maven|
|@cspell/dict-data-science|1.0.7|间接依赖|npm|
|org.springframework.boot:spring-boot-autoconfigure|2.0.3.RELEASE|间接依赖|maven|
|org.springframework:spring-oxm|5.3.29|间接依赖|maven|
|javax.money:money-api|1.0.1|直接依赖|maven|
|cspell-dictionary|6.31.1|间接依赖|npm|
|com.microsoft.azure:azure-servicebus|3.6.1|直接依赖|maven|
|org.springframework.cloud:spring-cloud-function-core|3.2.11|间接依赖|maven|
|org.ow2.asm:asm|5.0.4|间接依赖|maven|
|com.azure.spring:spring-integration-azure-storage-queue|4.12.0-beta.1|直接依赖|maven|
|com.fasterxml:classmate|1.3.4|直接依赖|maven|
|org.springframework.kafka:spring-kafka|2.8.11|直接依赖|maven|
|p-locate|5.0.0|间接依赖|npm|
|@cspell/dict-typescript|3.1.1|间接依赖|npm|
|com.github.docker-java:docker-java-core|3.2.1|间接依赖|maven|
|com.kohlschutter.junixsocket:junixsocket-common|2.3.2|间接依赖|maven|
|org.springframework:spring-aop|5.3.27|间接依赖|maven|
|io.netty:netty-handler|4.1.51.Final|间接依赖|maven|
|ca.juliusdavies:not-yet-commons-ssl|0.3.9|间接依赖|maven|
|org.codehaus.plexus:plexus-container-default|1.0-alpha-9-stable-1|间接依赖|maven|
|p-limit|3.1.0|间接依赖|npm|
|org.springframework.boot:spring-boot-starter-logging|2.7.5|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.7.14|间接依赖|maven|
|io.netty:netty-buffer|4.1.51.Final|间接依赖|maven|
|io.opentelemetry:opentelemetry-extension-incubator|1.28.0-alpha|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-scala_2.12|2.13.5|直接依赖|maven|
|com.azure:azure-json|1.2.0-beta.1|直接依赖|maven|
|org.springframework:spring-webmvc|5.0.7.RELEASE|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.0.1|间接依赖|maven|
|io.reactivex:rxjava|1.1.5|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.9.4|间接依赖|maven|
|ch.qos.logback:logback-core|1.1.11|直接依赖|maven|
|org.springframework:spring-expression|5.3.27|间接依赖|maven|
|com.azure:azure-ai-formrecognizer|4.2.0-beta.1|直接依赖|maven|
|com.azure:azure-identity|1.10.0|直接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|1.5.8.RELEASE|直接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.2|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-actuator|2.0.3.RELEASE|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-integration|2.7.14|直接依赖|maven|
|org.javassist:javassist|3.22.0-GA|间接依赖|maven|
|com.azure:azure-core-http-netty|1.13.6|直接依赖|maven|
|commons-collections:commons-collections|3.2.1|间接依赖|maven|
|org.asynchttpclient:async-http-client-netty-utils|2.12.1|间接依赖|maven|
|com.squareup.retrofit2:converter-jackson|2.7.2|间接依赖|maven|
|com.squareup.okhttp3:logging-interceptor|3.12.2|间接依赖|maven|
|io.cloudevents:cloudevents-api|2.2.0|直接依赖|maven|
|org.json:json|20140107|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.8.3|直接依赖|maven|
|org.springframework.boot:spring-boot-configuration-processor|2.7.14|直接依赖|maven|
|org.junit.jupiter:junit-jupiter-api|5.9.3|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.9.6|间接依赖|maven|
|@cspell/dict-html-symbol-entities|4.0.0|间接依赖|npm|
|org.apache.geronimo.specs:geronimo-jms_1.1_spec|1.0|直接依赖|maven|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.0.3.RELEASE|间接依赖|maven|
|org.springframework.security:spring-security-rsa|1.0.10.RELEASE|间接依赖|maven|
|semver|7.5.4|间接依赖|npm|
|com.azure:azure-data-tables|12.4.0-beta.1|直接依赖|maven|
|xerces:xmlParserAPIs|2.6.2|间接依赖|maven|
|@cspell/dict-k8s|1.0.1|间接依赖|npm|
|com.azure.resourcemanager:azure-resourcemanager-authorization|2.30.0|间接依赖|maven|
|cosmiconfig|8.0.0|间接依赖|npm|
|com.azure:azure-xml|1.0.0-beta.3|直接依赖|maven|
|com.github.javaparser:javaparser-symbol-solver-core|3.25.2|间接依赖|maven|
|vscode-languageserver-textdocument|1.0.8|间接依赖|npm|
|@cspell/dict-rust|4.0.1|间接依赖|npm|
|org.checkerframework:checker-compat-qual|2.0.0|间接依赖|maven|
|org.slf4j:slf4j-nop|1.7.36|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.0.3.RELEASE|间接依赖|maven|
|io.javaslang:javaslang|2.0.6|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.14|直接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.69|间接依赖|maven|
|flatted|3.2.7|间接依赖|npm|
|org.scala-lang.modules:scala-java8-compat_2.12|0.8.0|直接依赖|maven|
|com.squareup.okhttp3:logging-interceptor|3.12.12|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-storage|2.30.0|间接依赖|maven|
|commons-httpclient:commons-httpclient|3.1|间接依赖|maven|
|@cspell/dict-dotnet|5.0.0|间接依赖|npm|
|com.azure:azure-storage-blob-batch|12.20.0-beta.2|直接依赖|maven|
|com.azure:azure-communication-common|1.2.11|直接依赖|maven|
|com.squareup.retrofit2:converter-jackson|2.1.0|直接依赖|maven|
|io.netty:netty-resolver|4.1.48.Final|间接依赖|maven|
|org.slf4j:slf4j-simple|1.7.36|直接依赖|maven|
|ini|1.3.8|间接依赖|npm|
|cspell-grammar|6.31.1|间接依赖|npm|
|com.google.guava:guava|31.0.1-jre|间接依赖|maven|
|io.reactivex:rxjava|1.3.8|间接依赖|maven|
|@cspell/dict-csharp|4.0.2|间接依赖|npm|
|@cspell/dict-public-licenses|2.0.2|间接依赖|npm|
|org.springframework.cloud:spring-cloud-stream-binder-kafka|3.2.9|间接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-micrometer-1.5|1.28.0-alpha|间接依赖|maven|
|com.azure.spring:spring-cloud-azure-stream-binder-eventhubs-core|4.12.0-beta.1|直接依赖|maven|
|com.github.mifmif:generex|1.0.2|间接依赖|maven|
|com.querydsl:querydsl-core|4.1.4|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.7.2|直接依赖|maven|
|com.microsoft.azure:adal4j|1.6.7|间接依赖|maven|
|com.microsoft.azure:azure-keyvault-extensions|1.3.0-beta.1|直接依赖|maven|
|@cspell/dict-node|4.0.2|间接依赖|npm|
|org.codehaus.plexus:plexus-utils|3.3.1|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter|3.1.3|间接依赖|maven|
|webidl-conversions|3.0.1|间接依赖|npm|
|io.opentelemetry:opentelemetry-sdk-trace|1.28.0|间接依赖|maven|
|@cspell/dict-lua|4.0.1|间接依赖|npm|
|org.hdrhistogram:HdrHistogram|2.1.8|直接依赖|maven|
|commons-net:commons-net|3.9.0|直接依赖|maven|
|org.springframework.data:spring-data-relational|2.4.14|间接依赖|maven|
|net.minidev:json-smart|2.4.2|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.48.Final|间接依赖|maven|
|org.eclipse.jetty:jetty-security|9.4.51.v20230217|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-redis|2.30.0|间接依赖|maven|
|org.apache.velocity:velocity|1.7|间接依赖|maven|
|com.azure:azure-spring-data-cosmos|3.39.0-beta.1|直接依赖|maven|
|com.microsoft.azure:azure-eventhubs|3.3.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.9.6|直接依赖|maven|
|com.azure.spring:spring-cloud-azure-starter-redis|4.12.0-beta.1|直接依赖|maven|
|com.networknt:json-schema-validator|1.0.43|间接依赖|maven|
|com.nimbusds:oauth2-oidc-sdk|9.4|间接依赖|maven|
|com.google.code.gson:gson|2.8.9|间接依赖|maven|
|com.squareup.retrofit2:retrofit|2.6.4|间接依赖|maven|
|com.microsoft.azure.functions:azure-functions-java-library|1.3.0|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-xml|2.13.5|直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-extension-autoconfigure|1.28.0|直接依赖|maven|
|com.azure:azure-storage-blob-changefeed|12.0.0-beta.19|直接依赖|maven|
|com.azure.spring:spring-cloud-azure-stream-binder-eventhubs|4.12.0-beta.1|直接依赖|maven|
|org.joda:joda-convert|1.2|直接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-runtime-telemetry-java8|1.28.0-alpha|直接依赖|maven|
|com.azure:azure-storage-file-share|12.19.1|直接依赖|maven|
|io.netty:netty-codec-http|4.1.94.Final|直接依赖|maven|
|com.github.docker-java:docker-java-transport-netty|3.2.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.0.3.RELEASE|间接依赖|maven|
|@nodelib/fs.scandir|2.1.5|间接依赖|npm|
|org.apache.maven:maven-plugin-registry|2.2.1|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.6.20|间接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.51.Final|间接依赖|maven|
|@cspell/dict-html|4.0.3|间接依赖|npm|
|@cspell/dict-latex|4.0.0|间接依赖|npm|
|com.google.j2objc:j2objc-annotations|0.1|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-redis|2.31.0-beta.1|直接依赖|maven|
|io.zipkin.brave:brave|5.16.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.6.21|间接依赖|maven|
|org.springframework:spring-aop|5.0.7.RELEASE|间接依赖|maven|
|@cspell/dict-css|4.0.6|间接依赖|npm|
|org.jboss.logging:jboss-logging|3.3.0.Final|直接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.3.Final|间接依赖|maven|
|joda-time:joda-time|2.9.5|直接依赖|maven|
|javax.ejb:ejb-api|3.0|直接依赖|maven|
|com.google.code.gson:gson|2.8.6|间接依赖|maven|
|com.azure.spring:spring-cloud-azure-starter-eventhubs|4.12.0-beta.1|直接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-spring-webmvc-6.0|1.28.0-alpha|间接依赖|maven|
|com.microsoft.azure:azure-client-authentication|1.7.14|直接依赖|maven|
|io.dropwizard.metrics:metrics-core|4.2.19|间接依赖|maven|
|org.eclipse.sisu:org.eclipse.sisu.plexus|0.3.5|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.16|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|直接依赖|maven|
|com.azure:azure-security-keyvault-certificates|4.6.0-beta.1|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.78|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-compute|2.30.0|间接依赖|maven|
|commander|10.0.1|间接依赖|npm|
|jakarta.ws.rs:jakarta.ws.rs-api|2.1.6|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|8.5.23|直接依赖|maven|
|org.lz4:lz4-java|1.8.0|间接依赖|maven|
|org.json:json|20220320|间接依赖|maven|
|com.squareup.okhttp3:okhttp-urlconnection|3.12.12|间接依赖|maven|
|org.springframework:spring-web|4.3.12.RELEASE|直接依赖|maven|
|com.azure.spring:spring-cloud-azure-autoconfigure|4.11.0|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|1.5.8.RELEASE|直接依赖|maven|
|javax.mail:mail|1.4.5|直接依赖|maven|
|com.azure.spring:spring-cloud-azure-core|4.12.0-beta.1|直接依赖|maven|
|io.vertx:vertx-core|4.4.4|直接依赖|maven|
|com.azure:azure-ai-personalizer|1.0.0-beta.2|直接依赖|maven|
|org.springframework:spring-context-support|5.3.29|直接依赖|maven|
|com.azure:azure-monitor-ingestion|1.1.0-beta.1|直接依赖|maven|
|com.azure:azure-identity-extensions|1.2.0-beta.2|直接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.2|间接依赖|maven|
|org.springframework:spring-beans|5.3.27|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-logs|1.28.0|直接依赖|maven|
|org.springframework.boot:spring-boot-actuator|2.7.14|直接依赖|maven|
|com.azure:azure-analytics-synapse-artifacts|1.0.0-beta.14|直接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|com.microsoft.azure:azure-arm-client-runtime|1.7.14|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.1.3|间接依赖|maven|
|org.codehaus.janino:commons-compiler|3.1.10|间接依赖|maven|
|get-stdin|8.0.0|间接依赖|npm|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|org.codehaus.woodstox:stax2-api|3.1.4|间接依赖|maven|
|io.netty:netty-handler|4.1.94.Final|直接依赖|maven|
|com.azure.spring:spring-messaging-azure-storage-queue|4.12.0-beta.1|直接依赖|maven|
|io.netty:netty-codec-dns|4.1.93.Final|间接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.8|直接依赖|maven|
|org.glassfish.hk2.external:aopalliance-repackaged|2.6.1|间接依赖|maven|
|com.squareup.okhttp3:okhttp-urlconnection|3.12.2|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.6.20|间接依赖|maven|
|@cspell/dict-npm|5.0.7|间接依赖|npm|
|org.graalvm.compiler:compiler|22.0.0.2|间接依赖|maven|
|xpp3:xpp3|1.1.4c|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-actuator|2.7.14|直接依赖|maven|
|com.azure.spring:spring-cloud-azure-autoconfigure|4.12.0-beta.1|直接依赖|maven|
|com.azure:azure-core-http-jdk-httpclient|1.0.0-beta.6|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.5.31|间接依赖|maven|
|com.microsoft.azure:azure-core|0.9.8|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-containerregistry|2.31.0-beta.1|直接依赖|maven|
|@cspell/dict-en-common-misspellings|1.0.2|间接依赖|npm|
|com.google.guava:guava|19.0|直接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.2|间接依赖|maven|
|com.microsoft.sqlserver:mssql-jdbc|10.2.3.jre8|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.6.20|间接依赖|maven|
|org.jruby.joni:joni|2.1.31|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.5.31|间接依赖|maven|
|parent-module|2.0.0|间接依赖|npm|
|@cspell/dict-en_us|4.3.4|间接依赖|npm|
|io.micrometer:micrometer-registry-graphite|1.9.13|直接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.6.15|间接依赖|maven|
|io.opentelemetry:opentelemetry-api-events|1.28.0-alpha|间接依赖|maven|
|com.azure:azure-core-http-netty|1.13.5|间接依赖|maven|
|org.codehaus.plexus:plexus-classworlds|2.6.0|间接依赖|maven|
|@cspell/cspell-pipe|6.31.1|间接依赖|npm|
|org.apache.tomcat.embed:tomcat-embed-el|8.5.23|直接依赖|maven|
|io.fabric8:kubernetes-model-admissionregistration|5.12.3|间接依赖|maven|
|color-name|1.1.4|间接依赖|npm|
|com.azure:azure-communication-networktraversal|1.1.0-beta.3|直接依赖|maven|
|com.microsoft.azure:qpid-proton-j-extensions|1.2.3|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.0.3.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.9.6|间接依赖|maven|
|org.apiguardian:apiguardian-api|1.1.2|间接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|5.0.3|间接依赖|maven|
|com.azure:azure-core-tracing-opentelemetry|1.0.0-beta.39|直接依赖|maven|
|com.microsoft.azure:azure-storage|8.0.0|直接依赖|maven|
|ch.qos.logback:logback-classic|1.2.12|间接依赖|maven|
|com.azure:azure-core|1.41.0|间接依赖|maven|
|is-arrayish|0.2.1|间接依赖|npm|
|org.springframework.hateoas:spring-hateoas|0.23.0.RELEASE|直接依赖|maven|
|org.slf4j:log4j-over-slf4j|1.7.25|直接依赖|maven|
|to-regex-range|5.0.1|间接依赖|npm|
|io.reactivex:rxjava|1.2.4|直接依赖|maven|
|io.netty:netty-codec-dns|4.1.94.Final|间接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.64|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.6.20|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-sql|2.30.0|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-xml|2.9.6|间接依赖|maven|
|com.squareup.okhttp3:okhttp|3.4.2|直接依赖|maven|
|io.projectreactor.netty:reactor-netty-http-brave|1.0.34|间接依赖|maven|
|@nodelib/fs.walk|1.2.8|间接依赖|npm|
|org.apache.logging.log4j:log4j-api|2.11.2|间接依赖|maven|
|org.eclipse.sisu:org.eclipse.sisu.inject|0.3.5|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-metrics|1.28.0|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.78|间接依赖|maven|
|@cspell/dict-fonts|3.0.2|间接依赖|npm|
|com.sun.activation:jakarta.activation|1.2.1|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-resourcegraph|1.0.0|直接依赖|maven|
|com.azure:azure-messaging-eventhubs|5.16.0-beta.2|直接依赖|maven|
|com.google.guava:guava|32.0.1-jre|直接依赖|maven|
|io.netty:netty-tcnative-classes|2.0.61.Final|间接依赖|maven|
|com.mysql:mysql-connector-j|8.0.33|直接依赖|maven|
|org.springframework.cloud:spring-cloud-bus|3.1.2|直接依赖|maven|
|org.codehaus.groovy:groovy-all|2.4.0|直接依赖|maven|
|com.squareup.okhttp3:logging-interceptor|3.4.2|直接依赖|maven|
|@cspell/dict-ada|4.0.1|间接依赖|npm|
|io.netty.incubator:netty-incubator-codec-native-quic|0.0.48.Final|间接依赖|maven|
|is-glob|4.0.3|间接依赖|npm|
|javax.validation:validation-api|2.0.1.Final|直接依赖|maven|
|com.microsoft.azure:msal4j-persistence-extension|1.2.0|直接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-stream-kafka|3.2.9|直接依赖|maven|
|classworlds:classworlds|1.1-alpha-2|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.10.3|间接依赖|maven|
|@cspell/dict-sql|2.1.0|间接依赖|npm|
|org.springframework:spring-messaging|5.3.29|直接依赖|maven|
|io.opentelemetry:opentelemetry-semconv|1.28.0-alpha|间接依赖|maven|
|org.apache.maven.plugin-tools:maven-plugin-annotations|3.6.4|直接依赖|maven|
|global-dirs|0.1.1|间接依赖|npm|
|@cspell/cspell-service-bus|6.31.1|间接依赖|npm|
|@cspell/dict-svelte|1.0.2|间接依赖|npm|
|com.azure.resourcemanager:azure-resourcemanager-msi|2.31.0-beta.1|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager|2.31.0-beta.1|直接依赖|maven|
|com.squareup.okhttp3:okhttp|4.9.3|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.3|直接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j-impl|2.17.2|直接依赖|maven|
|merge2|1.4.1|间接依赖|npm|
|org.glassfish.jersey.connectors:jersey-apache-connector|2.30.1|间接依赖|maven|
|io.zipkin.reporter2:zipkin-reporter-brave|2.16.3|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-search|2.31.0-beta.1|直接依赖|maven|
|org.springframework:spring-jcl|5.3.29|间接依赖|maven|
|com.azure:azure-ai-textanalytics|5.3.2|直接依赖|maven|
|net.jcip:jcip-annotations|1.0|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-cosmos|2.31.0-beta.1|直接依赖|maven|
|com.azure:azure-messaging-webpubsub|1.3.0-beta.1|直接依赖|maven|
|org.glassfish.jersey.inject:jersey-hk2|2.30.1|间接依赖|maven|
|com.azure:azure-storage-common|12.22.1|间接依赖|maven|
|has-own-prop|2.0.0|间接依赖|npm|
|dk.brics.automaton:automaton|1.11-8|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter|3.1.7|间接依赖|maven|
|org.graalvm.nativeimage:svm|22.0.0.2|直接依赖|maven|
|org.opentest4j:opentest4j|1.2.0|间接依赖|maven|
|resolve-from|5.0.0|间接依赖|npm|
|com.azure.tools:azure-autorest-customization|1.0.0-beta.7|直接依赖|maven|
|com.azure:azure-cosmos-encryption|2.5.0-beta.1|直接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|间接依赖|maven|
|path-is-absolute|1.0.1|间接依赖|npm|
|org.springframework:spring-oxm|4.3.12.RELEASE|直接依赖|maven|
|org.slf4j:slf4j-simple|1.7.5|直接依赖|maven|
|com.microsoft.azure:azure-keyvault|1.3.0-beta.1|直接依赖|maven|
|io.dropwizard.metrics:metrics-core|4.1.0|直接依赖|maven|
|io.projectreactor.netty:reactor-netty-http|1.0.33|间接依赖|maven|
|net.minidev:json-smart|2.2.1|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.2.5.Final|直接依赖|maven|
|com.azure.spring:spring-cloud-azure-feature-management|4.12.0-beta.1|直接依赖|maven|
|com.github.luben:zstd-jni|1.5.0-2|间接依赖|maven|
|org.springframework:spring-tx|4.3.12.RELEASE|直接依赖|maven|
|@babel/code-frame|7.22.5|间接依赖|npm|
|io.opentelemetry.instrumentation:opentelemetry-kafka-clients-common|1.28.0-alpha|间接依赖|maven|
|is-obj|2.0.0|间接依赖|npm|
|org.springframework.boot:spring-boot-actuator|2.0.3.RELEASE|间接依赖|maven|
|org.messaginghub:pooled-jms|1.2.4|直接依赖|maven|
|org.codehaus.woodstox:stax2-api|4.2.1|间接依赖|maven|
|javax.activation:activation|1.1|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-joda|2.7.2|直接依赖|maven|
|com.azure:azure-containers-containerregistry|1.3.0-beta.1|直接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-logging|1.28.0|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|8.5.31|间接依赖|maven|
|io.fabric8:kubernetes-model-node|5.12.3|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.0.2|直接依赖|maven|
|com.squareup.okio:okio|1.9.0|直接依赖|maven|
|ch.qos.logback:logback-core|1.2.11|间接依赖|maven|
|io.netty:netty-codec|4.1.94.Final|直接依赖|maven|
|strip-ansi|6.0.1|间接依赖|npm|
|com.microsoft.azure:azure-annotations|1.10.0|间接依赖|maven|
|io.netty:netty-tcnative-boringssl-static|2.0.61.Final|直接依赖|maven|
|io.dropwizard.metrics:metrics-graphite|4.1.0|直接依赖|maven|
|org.apache.qpid:proton-j|0.33.6|间接依赖|maven|
|org.hamcrest:hamcrest|2.1|间接依赖|maven|
|com.google.code.gson:gson|2.8.0|间接依赖|maven|
|com.azure:azure-security-keyvault-keys|4.6.5|直接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.9.2|间接依赖|maven|
|com.azure:azure-storage-blob-nio|12.0.0-beta.20|直接依赖|maven|
|graceful-fs|4.2.11|间接依赖|npm|
|org.codehaus.jackson:jackson-xc|1.9.2|间接依赖|maven|
|org.yaml:snakeyaml|2.0|间接依赖|maven|
|com.azure.spring:spring-integration-azure-core|4.12.0-beta.1|直接依赖|maven|
|com.azure:azure-storage-queue|12.19.0-beta.2|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-afterburner|2.13.5|直接依赖|maven|
|com.azure.spring:spring-messaging-azure|4.12.0-beta.1|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-storage|2.31.0-beta.1|直接依赖|maven|
|@cspell/dict-fullstack|3.1.5|间接依赖|npm|
|net.minidev:json-smart|2.4.10|间接依赖|maven|
|org.apache.commons:commons-lang3|3.8.1|间接依赖|maven|
|@cspell/dict-docker|1.1.6|间接依赖|npm|
|io.fabric8:zjsonpatch|0.3.0|间接依赖|maven|
|queue-microtask|1.2.3|间接依赖|npm|
|com.kohlschutter.junixsocket:junixsocket-native-common|2.3.2|间接依赖|maven|
|com.squareup.okhttp3:okhttp-urlconnection|3.3.1|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.30|间接依赖|maven|
|com.azure:azure-core-test|1.19.0|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-keyvault|2.30.0|间接依赖|maven|
|com.github.javaparser:javaparser-core|3.25.2|间接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.51.v20230217|间接依赖|maven|
|org.apache.commons:commons-lang3|3.4|直接依赖|maven|
|org.javatuples:javatuples|1.2|直接依赖|maven|
|org.glassfish.hk2:osgi-resource-locator|1.0.3|间接依赖|maven|
|com.azure:azure-data-schemaregistry|1.4.0-beta.3|直接依赖|maven|
|com.nimbusds:lang-tag|1.7|直接依赖|maven|
|org.eclipse.jgit:org.eclipse.jgit|4.5.7.201904151645-r|直接依赖|maven|
|import-fresh|3.3.0|间接依赖|npm|
|javax.servlet:javax.servlet-api|3.1.0|直接依赖|maven|
|com.azure.spring:spring-messaging-azure-eventhubs|4.12.0-beta.1|直接依赖|maven|
|com.microsoft.azure:azure-client-runtime|1.2.1|直接依赖|maven|
|com.github.docker-java:docker-java-transport-jersey|3.2.1|间接依赖|maven|
|com.azure:azure-storage-blob-cryptography|12.23.0-beta.2|直接依赖|maven|
|locate-path|6.0.0|间接依赖|npm|
|com.google.errorprone:javac-shaded|9+181-r4173-1|间接依赖|maven|
|com.sun.jersey:jersey-core|1.19|间接依赖|maven|
|com.azure:azure-messaging-eventgrid|4.17.2|直接依赖|maven|
|com.github.docker-java:docker-java-api|3.2.1|间接依赖|maven|
|com.microsoft.rest:client-runtime|1.2.2-SNAPSHOT|直接依赖|maven|
|org.springframework:spring-web|5.3.29|直接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|file-entry-cache|6.0.1|间接依赖|npm|
|org.bouncycastle:bcprov-jdk15on|1.70|直接依赖|maven|
|run-parallel|1.2.0|间接依赖|npm|
|io.opentelemetry:opentelemetry-exporter-otlp-common|1.28.0|间接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-instrumentation-api-semconv|1.28.0-alpha|间接依赖|maven|
|io.netty:netty-buffer|4.1.28.Final|间接依赖|maven|
|org.revapi:revapi|0.14.4|直接依赖|maven|
|org.springframework:spring-tx|5.3.20|间接依赖|maven|
|com.microsoft.azure:azure-keyvault-webkey|1.0.0|直接依赖|maven|
|com.azure:azure-data-schemaregistry-apacheavro|1.2.0-beta.3|直接依赖|maven|
|org.glassfish.jersey.core:jersey-common|2.30.1|间接依赖|maven|
|io.zipkin.brave:brave-instrumentation-http|5.16.0|间接依赖|maven|
|@cspell/dict-cpp|5.0.3|间接依赖|npm|
|signal-exit|3.0.7|间接依赖|npm|
|org.springframework.boot:spring-boot-starter-aop|2.7.14|间接依赖|maven|
|org.codehaus.janino:janino|3.1.10|直接依赖|maven|
|micromatch|4.0.5|间接依赖|npm|
|com.azure.resourcemanager:azure-resourcemanager-appservice|2.30.0|间接依赖|maven|
|picomatch|2.3.1|间接依赖|npm|
|esprima|4.0.1|间接依赖|npm|
|com.microsoft.azure:azure-client-runtime|1.0.0|直接依赖|maven|
|org.apache.qpid:proton-j|0.33.8|直接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.4|间接依赖|maven|
|org.apache.maven:maven-artifact-manager|2.2.1|间接依赖|maven|
|org.springframework:spring-messaging|5.3.24|间接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-spring-webflux-5.3|1.28.0-alpha|间接依赖|maven|
|com.squareup.okio:okio-jvm|3.2.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.6.21|间接依赖|maven|
|org.codehaus.jackson:jackson-mapper-asl|1.9.2|间接依赖|maven|
|@cspell/dict-git|2.0.0|间接依赖|npm|
|io.netty:netty-transport|4.1.48.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|2.7.5|间接依赖|maven|
|com.sun.activation:javax.activation|1.2.0|间接依赖|maven|
|org.springframework:spring-jcl|5.3.23|间接依赖|maven|
|com.azure:azure-security-keyvault-jca|2.8.0-beta.1|直接依赖|maven|
|joda-time:joda-time|2.9.7|直接依赖|maven|
|org.springframework.security:spring-security-oauth2-resource-server|5.7.10|直接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|9.8.1|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.9.6|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-cosmos|2.30.0|直接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|com.azure:azure-monitor-opentelemetry-exporter|1.0.0-beta.11|直接依赖|maven|
|com.microsoft.azure:azure-client-runtime|1.2.2-SNAPSHOT|直接依赖|maven|
|unique-string|2.0.0|间接依赖|npm|
|io.zipkin.zipkin2:zipkin|2.23.2|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.29|直接依赖|maven|
|com.nimbusds:oauth2-oidc-sdk|10.7.1|间接依赖|maven|
|com.google.android:android|4.1.1.4|直接依赖|maven|
|io.fabric8:kubernetes-model-policy|5.12.3|间接依赖|maven|
|org.yaml:snakeyaml|1.19|间接依赖|maven|
|glob|7.2.3|间接依赖|npm|
|node-fetch|2.6.12|间接依赖|npm|
|commons-codec:commons-codec|1.11|间接依赖|maven|
|com.azure.spring:spring-cloud-azure-starter-monitor|1.0.0-beta.1|直接依赖|maven|
|commons-io:commons-io|2.7|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|8.5.31|间接依赖|maven|
|org.springframework.cloud:spring-cloud-function-context|3.2.11|间接依赖|maven|
|com.azure.spring:spring-cloud-azure-starter-cosmos|4.12.0-beta.1|直接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|间接依赖|maven|
|path-type|4.0.0|间接依赖|npm|
|@nodelib/fs.stat|2.0.5|间接依赖|npm|
|com.microsoft.azure:azure-storage|8.6.5|直接依赖|maven|
|DocumentDB.Spatial.Sql.dll||间接依赖||
|javax.mail:mail|1.4|直接依赖|maven|
|com.azure:azure-messaging-eventgrid|4.18.0-beta.1|直接依赖|maven|
|com.sun.xml.bind:jaxb-impl|2.2.3-1|间接依赖|maven|
|@cspell/dict-django|4.1.0|间接依赖|npm|
|io.netty:netty-common|4.1.28.Final|间接依赖|maven|
|org.javassist:javassist|3.29.2-GA|间接依赖|maven|
|org.revapi:revapi-java|0.26.1|直接依赖|maven|
|com.squareup.okhttp3:okhttp|3.3.0|直接依赖|maven|
|@cspell/dict-haskell|4.0.1|间接依赖|npm|
|io.opentelemetry.instrumentation:opentelemetry-instrumentation-api|1.28.0|间接依赖|maven|
|com.microsoft.azure:adal4j|1.6.4|间接依赖|maven|
|org.springframework:spring-aop|5.3.23|间接依赖|maven|
|com.azure:azure-storage-file-share|12.20.0-beta.2|直接依赖|maven|
|com.squareup.okhttp3:okhttp|3.3.1|间接依赖|maven|
|cspell-io|6.31.2|间接依赖|npm|
|com.microsoft.azure:adal4j|1.2.0|直接依赖|maven|
|com.nimbusds:lang-tag|1.4|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.8.10|直接依赖|maven|
|com.querydsl:querydsl-collections|4.1.4|直接依赖|maven|
|com.azure.spring:spring-cloud-azure-starter-storage-file-share|4.12.0-beta.1|直接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.48.Final|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.3.1.Final|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.3|间接依赖|maven|
|com.azure:azure-search-documents|11.6.0-beta.9|直接依赖|maven|
|repeat-string|1.6.1|间接依赖|npm|
|io.netty:netty-codec-socks|4.1.94.Final|间接依赖|maven|
|net.minidev:accessors-smart|1.2|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.25|直接依赖|maven|
|io.netty:netty-transport|4.1.94.Final|直接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.51.v20230217|间接依赖|maven|
|clear-module|4.1.2|间接依赖|npm|
|org.javassist:javassist|3.28.0-GA|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.9.6|直接依赖|maven|
|cspell|6.31.2|直接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|com.azure.resourcemanager:azure-resourcemanager-sql|2.31.0-beta.1|直接依赖|maven|
|org.springframework.boot:spring-boot|2.7.14|间接依赖|maven|
|org.glassfish.hk2.external:jakarta.inject|2.6.1|间接依赖|maven|
|org.codehaus.plexus:plexus-component-annotations|1.5.5|间接依赖|maven|
|com.azure:azure-messaging-servicebus|7.14.3|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.9.6|间接依赖|maven|
|org.springframework:spring-context|4.3.12.RELEASE|直接依赖|maven|
|javax.inject:javax.inject|1|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.0.3.RELEASE|直接依赖|maven|
|io.javaslang:javaslang-match|2.0.6|间接依赖|maven|
|io.fabric8:kubernetes-model-flowcontrol|5.12.3|间接依赖|maven|
|com.sun.jersey:jersey-json|1.19|直接依赖|maven|
|@cspell/cspell-bundled-dicts|6.31.2|间接依赖|npm|
|com.nimbusds:nimbus-jose-jwt|9.22|间接依赖|maven|
|io.netty:netty-common|4.1.51.Final|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.28.Final|间接依赖|maven|
|com.azure:azure-messaging-eventhubs|5.15.8|直接依赖|maven|
|org.codehaus.jackson:jackson-jaxrs|1.9.2|间接依赖|maven|
|org.springframework:spring-core|4.3.12.RELEASE|直接依赖|maven|
|com.azure:azure-sdk-template-three|1.0.0-beta.1|直接依赖|maven|
|io.micrometer:micrometer-core|1.9.13|直接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|com.azure.spring:spring-integration-azure-eventhubs|4.12.0-beta.1|直接依赖|maven|
|com.azure.spring:spring-cloud-azure-appconfiguration-config|4.12.0-beta.1|直接依赖|maven|
|com.puppycrawl.tools:checkstyle|9.3|直接依赖|maven|
|com.azure:azure-xml|1.0.0-beta.1|间接依赖|maven|
|@cspell/dict-en-gb|1.1.33|间接依赖|npm|
|com.fasterxml.jackson.datatype:jackson-datatype-joda|2.10.5|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.10.0|直接依赖|maven|
|ch.qos.logback:logback-core|1.2.12|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.5|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.7.2|直接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-spring-kafka-2.7|1.28.0-alpha|间接依赖|maven|
|com.azure.spring:spring-cloud-azure-starter-storage-queue|4.12.0-beta.1|直接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|3.1.2|直接依赖|maven|
|io.fabric8:kubernetes-model-networking|5.12.3|间接依赖|maven|
|com.nimbusds:content-type|2.1|间接依赖|maven|
|com.google.guava:guava|20.0|直接依赖|maven|
|com.azure:azure-ai-metricsadvisor|1.2.0-beta.1|直接依赖|maven|
|com.azure.spring:spring-messaging-azure-servicebus|4.12.0-beta.1|直接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.68|间接依赖|maven|
|io.fabric8:kubernetes-model-common|5.12.3|间接依赖|maven|
|com.azure:azure-core-serializer-json-gson|1.3.0-beta.1|直接依赖|maven|
|com.azure:azure-identity-extensions|1.1.7|直接依赖|maven|
|com.microsoft.azure:azure-annotations|1.3.0|间接依赖|maven|
|com.azure:azure-data-appconfiguration|1.4.8|直接依赖|maven|
|com.azure.spring:spring-integration-azure-servicebus|4.12.0-beta.1|直接依赖|maven|
|com.azure:azure-data-appconfiguration|1.5.0-beta.2|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.6.0|直接依赖|maven|
|cspell-glob|6.31.2|间接依赖|npm|
|com.azure:azure-core-serializer-json-jackson|1.5.0-beta.1|直接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|org.revapi.classif:classif|0.1.0|间接依赖|maven|
|joda-time:joda-time|2.4|直接依赖|maven|
|org.springframework:spring-tx|5.3.24|间接依赖|maven|
|commons-codec:commons-codec|1.3|间接依赖|maven|
|imurmurhash|0.1.4|间接依赖|npm|
|io.netty:netty-resolver-dns|4.1.93.Final|间接依赖|maven|
|whatwg-url|5.0.0|间接依赖|npm|
|gensequence|5.0.2|间接依赖|npm|
|io.fabric8:kubernetes-model-rbac|5.12.3|间接依赖|maven|
|org.mpierce.metrics.reservoir:hdrhistogram-metrics-reservoir|1.1.0|直接依赖|maven|
|org.projectlombok:lombok|1.16.18|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-test|2.0.0-beta.1|直接依赖|maven|
|@cspell/dict-software-terms|3.2.0|间接依赖|npm|
|comment-json|4.2.3|间接依赖|npm|
|com.azure.resourcemanager:azure-resourcemanager-appservice|2.31.0-beta.1|直接依赖|maven|
|@cspell/dict-swift|2.0.1|间接依赖|npm|
|commons-lang:commons-lang|2.6|间接依赖|maven|
|com.nimbusds:oauth2-oidc-sdk|5.18.1|间接依赖|maven|
|io.netty:netty-buffer|4.1.48.Final|间接依赖|maven|
|fs.realpath|1.0.0|间接依赖|npm|
|com.azure:azure-ai-formrecognizer|4.1.0|直接依赖|maven|
|io.netty:netty-buffer|4.1.94.Final|直接依赖|maven|
|com.microsoft.azure:azure-keyvault-secrets-spring-boot-starter|0.2.2-SNAPSHOT|直接依赖|maven|
|com.h2database:h2|2.1.214|直接依赖|maven|
|com.azure:azure-core-serializer-json-jackson|1.4.3|直接依赖|maven|
|io.netty:netty-resolver|4.1.28.Final|间接依赖|maven|
|import-meta-resolve|2.2.2|间接依赖|npm|
|io.netty:netty-codec|4.1.48.Final|间接依赖|maven|
|org.owasp.esapi:esapi|2.0.1|间接依赖|maven|
|org.opensaml:openws|1.5.4|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|直接依赖|maven|
|io.jsonwebtoken:jjwt|0.5.1|直接依赖|maven|
|com.microsoft.azure:azure-client-runtime|1.7.14|直接依赖|maven|
|org.springframework.security:spring-security-core|5.7.10|间接依赖|maven|
|com.azure:azure-json|1.0.0|间接依赖|maven|
|io.netty:netty-handler|4.1.28.Final|间接依赖|maven|
|org.apache.maven.wagon:wagon-provider-api|1.0-beta-6|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.5|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.13.1|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.51.Final|间接依赖|maven|
|org.apache.maven:maven-profile|2.2.1|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.6.21|间接依赖|maven|
|org.springframework.integration:spring-integration-kafka|5.5.18|间接依赖|maven|
|org.springframework:spring-beans|5.3.29|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-monitor|2.31.0-beta.1|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-resources|2.30.0|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.12|直接依赖|maven|
|io.fabric8:kubernetes-model-batch|5.12.3|间接依赖|maven|
|org.apache.geronimo.specs:geronimo-jms_2.0_spec|1.0-alpha-2|间接依赖|maven|
|org.springframework:spring-tx|5.3.27|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-keyvault|2.31.0-beta.1|直接依赖|maven|
|org.springframework.boot:spring-boot|2.0.3.RELEASE|间接依赖|maven|
|com.azure:azure-cosmos-test|1.0.0-beta.6|直接依赖|maven|
|inherits|2.0.4|间接依赖|npm|
|com.azure:azure-messaging-eventhubs-checkpointstore-blob|1.17.0-beta.2|直接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|6.4.0|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.94.Final|直接依赖|maven|
|com.microsoft.azure:azure-keyvault-cryptography|1.3.0-beta.1|直接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-jdbc|1.28.0-alpha|直接依赖|maven|
|@babel/highlight|7.22.5|间接依赖|npm|
|io.opentelemetry.instrumentation:opentelemetry-spring-webmvc-5.3|1.28.0-alpha|间接依赖|maven|
|commons-codec:commons-codec|1.9|直接依赖|maven|
|org.apache.commons:commons-lang3|3.5|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.8.10|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-servicebus|2.30.0|间接依赖|maven|
|io.fabric8:kubernetes-model-apps|5.12.3|间接依赖|maven|
|org.springframework:spring-jcl|5.3.27|间接依赖|maven|
|com.azure.spring:spring-cloud-azure-starter-appconfiguration-config|4.12.0-beta.1|直接依赖|maven|
|org.springframework.security:spring-security-config|5.7.10|直接依赖|maven|
|com.azure:azure-communication-common|2.0.0-beta.2|直接依赖|maven|
|io.micrometer:micrometer-registry-azure-monitor|1.9.13|直接依赖|maven|
|io.fabric8:kubernetes-model-apiextensions|5.12.3|间接依赖|maven|
|org.graalvm.truffle:truffle-api|22.0.0.2|间接依赖|maven|
|org.ow2.asm:asm|5.0.3|直接依赖|maven|
|com.azure.spring:spring-cloud-azure-starter-appconfiguration|4.12.0-beta.1|直接依赖|maven|
|com.azure.spring:spring-cloud-azure-starter|4.12.0-beta.1|直接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-trafficmanager|2.30.0|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.14|直接依赖|maven|
|org.graalvm.nativeimage:native-image-base|22.0.0.2|间接依赖|maven|
|com.azure:azure-ai-anomalydetector|3.0.0-beta.6|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.7.20-Beta|间接依赖|maven|
|com.squareup.okio:okio|1.15.0|间接依赖|maven|
|typedarray-to-buffer|3.1.5|间接依赖|npm|
|com.azure:azure-mixedreality-authentication|1.3.0-beta.1|直接依赖|maven|
|com.squareup.retrofit2:adapter-rxjava|2.1.0|直接依赖|maven|
|com.nimbusds:lang-tag|1.5|间接依赖|maven|
|reusify|1.0.4|间接依赖|npm|
|io.opentelemetry.instrumentation:opentelemetry-spring-web-3.1|1.28.0-alpha|间接依赖|maven|
|com.azure:azure-storage-common|12.23.0-beta.2|直接依赖|maven|
|com.squareup.okhttp3:okhttp|3.12.6|间接依赖|maven|
|org.codehaus.janino:janino|3.0.6|直接依赖|maven|
|org.apache.kafka:kafka-clients|3.0.2|间接依赖|maven|
|com.sun.jersey:jersey-client|1.19|直接依赖|maven|
|org.springframework.security:spring-security-oauth2-client|5.7.10|直接依赖|maven|
|org.springframework.security:spring-security-crypto|5.6.10|间接依赖|maven|
|com.azure.spring:spring-cloud-azure-starter-jdbc-mysql|4.12.0-beta.1|直接依赖|maven|
|org.springframework.boot:spring-boot-starter|1.5.8.RELEASE|直接依赖|maven|
|com.google.guava:guava|27.0.1-jre|间接依赖|maven|
|org.apache.santuario:xmlsec|1.5.7|间接依赖|maven|
|com.azure.resourcemanager:azure-resourcemanager-dns|2.31.0-beta.1|直接依赖|maven|
|argparse|2.0.1|间接依赖|npm|
|com.azure.spring:spring-cloud-azure-stream-binder-servicebus-core|4.12.0-beta.1|直接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.94.Final|间接依赖|maven|
|com.microsoft.azure:azure-keyvault-core|0.8.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.9.8|间接依赖|maven|
|org.javassist:javassist|3.25.0-GA|间接依赖|maven|
|org.jboss:jboss-dmr|1.5.0.Final|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.32|间接依赖|maven|
|com.azure:azure-core-amqp-experimental|1.0.0-beta.1|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.7.20-Beta|间接依赖|maven|
|@cspell/dict-lorem-ipsum|3.0.0|间接依赖|npm|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.5|直接依赖|maven|
|com.microsoft.rest.v2:client-runtime|2.1.1|直接依赖|maven|
|org.springframework.data:spring-data-commons|2.7.14|直接依赖|maven|
|com.azure:azure-storage-internal-avro|12.8.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|1.5.8.RELEASE|直接依赖|maven|
|com.azure:azure-security-keyvault-certificates|4.5.5|直接依赖|maven|
|@cspell/dict-golang|6.0.2|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)