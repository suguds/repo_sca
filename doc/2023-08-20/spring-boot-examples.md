# ityouknow/spring-boot-examples安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692960156865679360.svg)](https://www.murphysec.com/console/report/1692960156815347712/1692960156865679360)

仓库描述：about learning Spring Boot via examples. Spring Boot 教程、技术栈示例代码，快速简单上手教程。 

仓库地址：[https://github.com/ityouknow/spring-boot-examples](https://github.com/ityouknow/spring-boot-examples)

| star：29290 | watch：1335 | fork：12350 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-07-19 04:52:05 | 许可证：- |
| 最近检测时间：2023-08-20 02:13:46 | 组件总数：796 | 漏洞总数：246 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache Groovy 代码注入漏洞|注入|[MPS-2015-3848](https://www.oscs1024.com/hd/MPS-2015-3848)|CVE-2015-3253|严重|
|Pivotal Software Spring Framework 路径遍历漏洞|路径遍历|[MPS-2016-6414](https://www.oscs1024.com/hd/MPS-2016-6414)|CVE-2016-9878|高危|
|Apache Tomcat 安全漏洞|任意文件上传|[MPS-2017-11132](https://www.oscs1024.com/hd/MPS-2017-11132)|CVE-2017-12617|高危|
|QOS.ch Logback SocketServer和ServerSocketReceiver组件代码问题漏洞|反序列化|[MPS-2017-2574](https://www.oscs1024.com/hd/MPS-2017-2574)|CVE-2017-5929|严重|
|Apache Tomcat XSS 漏洞|未授权敏感信息泄露|[MPS-2017-2995](https://www.oscs1024.com/hd/MPS-2017-2995)|CVE-2016-6816|高危|
|Apache Tomcat 安全漏洞|未授权敏感信息泄露|[MPS-2017-4307](https://www.oscs1024.com/hd/MPS-2017-4307)|CVE-2017-5647|高危|
|Apache Tomcat 安全漏洞|将资源暴露给错误范围|[MPS-2017-4308](https://www.oscs1024.com/hd/MPS-2017-4308)|CVE-2017-5648|严重|
|Apache Tomcat 安全漏洞|不恰当的资源关闭或释放|[MPS-2017-4309](https://www.oscs1024.com/hd/MPS-2017-4309)|CVE-2017-5650|高危|
|Apache Tomcat [8.5.0, 8.5.13)、[9.0.0.M1, 9.0.0.M19) 信息泄露漏洞|数据处理错误|[MPS-2017-4310](https://www.oscs1024.com/hd/MPS-2017-4310)|CVE-2017-5651|严重|
|Oracle MySQL Connectors 访问限制绕过漏洞|访问控制不当|[MPS-2017-4684](https://www.oscs1024.com/hd/MPS-2017-4684)|CVE-2017-3523|高危|
|Oracle MySQL Connectors 安全漏洞|访问控制不当|[MPS-2017-4744](https://www.oscs1024.com/hd/MPS-2017-4744)|CVE-2017-3586|中危|
|Oracle MySQL Connectors 安全漏洞|访问控制不当|[MPS-2017-4746](https://www.oscs1024.com/hd/MPS-2017-4746)|CVE-2017-3589|低危|
|Pivotal Spring Security和Spring Framework 身份验证绕过漏洞|权限、特权和访问控制|[MPS-2017-5896](https://www.oscs1024.com/hd/MPS-2017-5896)|CVE-2016-5007|高危|
|Apache Tomcat Default Servlet 访问限制绕过漏洞|对异常条件的处理不恰当|[MPS-2017-6091](https://www.oscs1024.com/hd/MPS-2017-6091)|CVE-2017-5664|高危|
|Apache Tomcat 拒绝服务漏洞|缓冲区溢出|[MPS-2017-9022](https://www.oscs1024.com/hd/MPS-2017-9022)|CVE-2016-6817|高危|
|Apache Tomcat 信息泄露漏洞|7PK - 错误|[MPS-2017-9023](https://www.oscs1024.com/hd/MPS-2017-9023)|CVE-2016-8745|高危|
|Apache Tomcat 目录遍历漏洞|路径遍历|[MPS-2017-9026](https://www.oscs1024.com/hd/MPS-2017-9026)|CVE-2017-7675|高危|
|Red Hat Hibernate Validator 存在不安全反射漏洞|使用外部可控制的输入来选择类或代码（不安全的反射）|[MPS-2018-0334](https://www.oscs1024.com/hd/MPS-2018-0334)|CVE-2017-7536|高危|
|FasterXML Jackson-databind 反序列化漏洞(dbcp2 gadget绕过)|反序列化|[MPS-2018-0362](https://www.oscs1024.com/hd/MPS-2018-0362)|CVE-2017-17485|严重|
|Apache Groovy 远程代码执行漏洞|反序列化|[MPS-2018-0875](https://www.oscs1024.com/hd/MPS-2018-0875)|CVE-2016-6814|严重|
|jQuery 存在 XSS 漏洞|XSS|[MPS-2018-0885](https://www.oscs1024.com/hd/MPS-2018-0885)|CVE-2015-9251|中危|
|FasterXML jackson-databind 反序列化漏洞(Hibernate/iBatis gadget绕过)||[MPS-2018-0934](https://www.oscs1024.com/hd/MPS-2018-0934)|CVE-2018-5968|高危|
|Apache Tomcat 竞争条件问题漏洞|竞争条件|[MPS-2018-10791](https://www.oscs1024.com/hd/MPS-2018-10791)|CVE-2018-8037|中危|
|Apache Tomcat 拒绝服务漏洞|不可达退出条件的循环（无限循环）|[MPS-2018-10792](https://www.oscs1024.com/hd/MPS-2018-10792)|CVE-2018-1336|高危|
|RabbitMQ （Spring-AMQP）存在中间人漏洞|证书验证不恰当|[MPS-2018-12304](https://www.oscs1024.com/hd/MPS-2018-12304)|CVE-2018-11087|中危|
|Apache Tomcat 输入验证错误漏洞|跨站重定向|[MPS-2018-13051](https://www.oscs1024.com/hd/MPS-2018-13051)|CVE-2018-11784|中危|
|Oracle MySQL Connectors 访问控制错误漏洞|使用候选路径或通道进行的认证绕过|[MPS-2018-13771](https://www.oscs1024.com/hd/MPS-2018-13771)|CVE-2018-3258|高危|
|Spring Framework <5.1.1.RELEASE 拒绝服务漏洞|拒绝服务|[MPS-2018-13948](https://www.oscs1024.com/hd/MPS-2018-13948)|CVE-2018-15756|高危|
|FasterXML Jackson-databind 反序列化漏洞(JdbcRowSetImpl gadget绕过)|反序列化|[MPS-2018-1438](https://www.oscs1024.com/hd/MPS-2018-1438)|CVE-2017-15095|严重|
|FasterXML Jackson-databind反序列化漏洞|反序列化|[MPS-2018-1439](https://www.oscs1024.com/hd/MPS-2018-1439)|CVE-2017-7525|严重|
|FasterXML Jackson < 2.9.8存在拒绝服务漏洞|拒绝服务|[MPS-2018-16099](https://www.oscs1024.com/hd/MPS-2018-16099)|CVE-2018-1000873|中危|
|Elasticsearch Security 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2018-16131](https://www.oscs1024.com/hd/MPS-2018-16131)|CVE-2018-17244|中危|
|jQuery跨站脚本漏洞|XSS|[MPS-2018-16619](https://www.oscs1024.com/hd/MPS-2018-16619)|CVE-2017-16012|中危|
|Apache Tomcat 访问控制错误漏洞|路径遍历|[MPS-2018-2433](https://www.oscs1024.com/hd/MPS-2018-2433)|CVE-2018-1305|中危|
|FasterXML jackson-databind 反序列化漏洞(c3p0 gadget绕过)||[MPS-2018-2477](https://www.oscs1024.com/hd/MPS-2018-2477)|CVE-2018-7489|严重|
|Apache Tomcat 安全约束绕过漏洞|访问控制不当|[MPS-2018-2590](https://www.oscs1024.com/hd/MPS-2018-2590)|CVE-2018-1304|中危|
|Jolokia agent 跨站脚本漏洞|XSS|[MPS-2018-3149](https://www.oscs1024.com/hd/MPS-2018-3149)|CVE-2018-1000129|中危|
|Jolokia agent < 1.5.0 任意代码执行漏洞|代码注入|[MPS-2018-3150](https://www.oscs1024.com/hd/MPS-2018-3150)|CVE-2018-1000130|高危|
|Pivotal Spring Framework 任意代码执行漏洞|代码注入|[MPS-2018-4350](https://www.oscs1024.com/hd/MPS-2018-4350)|CVE-2018-1270|严重|
|Pivotal Spring Framework 路径遍历漏洞|路径遍历|[MPS-2018-4351](https://www.oscs1024.com/hd/MPS-2018-4351)|CVE-2018-1271|中危|
|Pivotal Spring Framework 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2018-4352](https://www.oscs1024.com/hd/MPS-2018-4352)|CVE-2018-1272|高危|
|Spring Data Commons <2.0.6.RELEASE  远程代码执行漏洞|代码注入|[MPS-2018-4454](https://www.oscs1024.com/hd/MPS-2018-4454)|CVE-2018-1273|严重|
|Pivotal Spring Framework 代码注入漏洞|代码注入|[MPS-2018-4455](https://www.oscs1024.com/hd/MPS-2018-4455)|CVE-2018-1275|严重|
|Spring Data Commons 无限制的资源分配漏洞|不加限制或调节的资源分配|[MPS-2018-5028](https://www.oscs1024.com/hd/MPS-2018-5028)|CVE-2018-1274|高危|
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|Spring Framework <5.0.6.RELEASE 拒绝服务漏洞|拒绝服务|[MPS-2018-5950](https://www.oscs1024.com/hd/MPS-2018-5950)|CVE-2018-1257|中危|
|Apache Tomcat CORS Filter 不安全的默认值漏洞|资源默认不安全|[MPS-2018-6086](https://www.oscs1024.com/hd/MPS-2018-6086)|CVE-2018-8014|严重|
|Pivotal Spring Framework XST漏洞|访问控制不当|[MPS-2018-8290](https://www.oscs1024.com/hd/MPS-2018-8290)|CVE-2018-11039|中危|
|Pivotal Spring Framework 信息泄露漏洞|从非可信控制范围包含功能例程|[MPS-2018-8291](https://www.oscs1024.com/hd/MPS-2018-8291)|CVE-2018-11040|高危|
|Bootstrap 跨站脚本漏洞|XSS|[MPS-2018-9640](https://www.oscs1024.com/hd/MPS-2018-9640)|CVE-2018-14040|中危|
|Bootstrap 跨站脚本漏洞|XSS|[MPS-2018-9642](https://www.oscs1024.com/hd/MPS-2018-9642)|CVE-2018-14042|中危|
|FasterXML jackson-databind反序列化漏洞(slf4j-ext gadget绕过)|反序列化|[MPS-2019-0018](https://www.oscs1024.com/hd/MPS-2019-0018)|CVE-2018-14718|严重|
|FasterXML jackson-databind反序列化漏洞(blaze-ds-opt gadget绕过)|反序列化|[MPS-2019-0019](https://www.oscs1024.com/hd/MPS-2019-0019)|CVE-2018-14719|严重|
|FasterXML jackson-databind XXE漏洞(DRSHelper gadget绕过)||[MPS-2019-0020](https://www.oscs1024.com/hd/MPS-2019-0020)|CVE-2018-14720|严重|
|FasterXML Jackson-databind服务器端请求伪造漏洞(axis2-jaxws gadget绕过)|SSRF|[MPS-2019-0021](https://www.oscs1024.com/hd/MPS-2019-0021)|CVE-2018-14721|严重|
|FasterXML Jackson-databind代码问题漏洞(axis2-transport-jms gadget绕过)|反序列化|[MPS-2019-0023](https://www.oscs1024.com/hd/MPS-2019-0023)|CVE-2018-19360|严重|
|FasterXML Jackson-databind代码问题漏洞(openjpa gadget绕过)|反序列化|[MPS-2019-0024](https://www.oscs1024.com/hd/MPS-2019-0024)|CVE-2018-19361|严重|
|FasterXML Jackson-databind代码问题漏洞(jboss-common-core gadget绕过)|反序列化|[MPS-2019-0025](https://www.oscs1024.com/hd/MPS-2019-0025)|CVE-2018-19362|严重|
|Bootstrap跨站脚本漏洞|XSS|[MPS-2019-0181](https://www.oscs1024.com/hd/MPS-2019-0181)|CVE-2018-20676|中危|
|Bootstrap跨站脚本漏洞|XSS|[MPS-2019-0182](https://www.oscs1024.com/hd/MPS-2019-0182)|CVE-2018-20677|中危|
|Bootstrap 跨站脚本漏洞|XSS|[MPS-2019-0183](https://www.oscs1024.com/hd/MPS-2019-0183)|CVE-2016-10735|中危|
|FasterXML jackson-databind 反序列化漏洞(HikariCP gadget绕过)|反序列化|[MPS-2019-11529](https://www.oscs1024.com/hd/MPS-2019-11529)|CVE-2019-14540|严重|
|FasterXML jackson-databind 反序列化漏洞(HikariCP gadget绕过)|反序列化|[MPS-2019-11533](https://www.oscs1024.com/hd/MPS-2019-11533)|CVE-2019-16335|严重|
|Netty 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2019-12064](https://www.oscs1024.com/hd/MPS-2019-12064)|CVE-2019-16869|高危|
|FasterXML jackson-databind 反序列化漏洞(commons-dbcp gadget绕过)|反序列化|[MPS-2019-12479](https://www.oscs1024.com/hd/MPS-2019-12479)|CVE-2019-16942|严重|
|FasterXML jackson-databind 反序列化漏洞(p6spy gadget绕过)|反序列化|[MPS-2019-12480](https://www.oscs1024.com/hd/MPS-2019-12480)|CVE-2019-16943|严重|
|FasterXML jackson-databind 反序列化漏洞(ehcache gadget绕过)|反序列化|[MPS-2019-12676](https://www.oscs1024.com/hd/MPS-2019-12676)|CVE-2019-17267|严重|
|Swagger UI @import 跨站脚本漏洞|CSRF|[MPS-2019-13043](https://www.oscs1024.com/hd/MPS-2019-13043)|CVE-2019-17495|中危|
|FasterXML jackson-databind 反序列化漏洞(apache-log4j-extras gadget绕过)|反序列化|[MPS-2019-13103](https://www.oscs1024.com/hd/MPS-2019-13103)|CVE-2019-17531|严重|
|Pivotal Reactor Netty 存在凭证保护不足漏洞|凭证保护不足|[MPS-2019-13428](https://www.oscs1024.com/hd/MPS-2019-13428)|CVE-2019-11284|高危|
|Elasticsearch 存在敏感信息泄露漏洞|未授权敏感信息泄露|[MPS-2019-13902](https://www.oscs1024.com/hd/MPS-2019-13902)|CVE-2019-7619|中危|
|​ hibernate-validator  存在跨站脚本（XSS）漏洞|XSS|[MPS-2019-14389](https://www.oscs1024.com/hd/MPS-2019-14389)|CVE-2019-10219|中危|
|SnakeYAML <1.26 存在 Billion laughs 漏洞|拒绝服务|[MPS-2019-16129](https://www.oscs1024.com/hd/MPS-2019-16129)|CVE-2017-18640|高危|
|Apache Tomcat 授权问题漏洞|会话固定|[MPS-2019-16906](https://www.oscs1024.com/hd/MPS-2019-16906)|CVE-2019-17563|高危|
|Apache Tomcat 特权提升漏洞|权限管理不当|[MPS-2019-16926](https://www.oscs1024.com/hd/MPS-2019-16926)|CVE-2019-12418|高危|
|Bootstrap 存在跨站脚本漏洞|XSS|[MPS-2019-1791](https://www.oscs1024.com/hd/MPS-2019-1791)|CVE-2019-8331|中危|
|jQuery 原型污染漏洞|拒绝服务|[MPS-2019-18923](https://www.oscs1024.com/hd/MPS-2019-18923)|CVE-2019-5428|中危|
|FasterXML Jackson-databind反序列化漏洞（Jodd-db gadget绕过）|反序列化|[MPS-2019-2619](https://www.oscs1024.com/hd/MPS-2019-2619)|CVE-2018-12022|高危|
|FasterXML Jackson-databind反序列化漏洞(Oracle JDBC driver gadget绕过)|反序列化|[MPS-2019-2620](https://www.oscs1024.com/hd/MPS-2019-2620)|CVE-2018-12023|高危|
|Elasticsearch 权限提升漏洞|权限问题|[MPS-2019-2964](https://www.oscs1024.com/hd/MPS-2019-2964)|CVE-2019-7611|高危|
|Apache Tomcat拒绝服务漏洞|拒绝服务|[MPS-2019-3894](https://www.oscs1024.com/hd/MPS-2019-3894)|CVE-2019-0199|高危|
|Apache Tomcat 操作系统命令注入漏洞|OS命令注入|[MPS-2019-4006](https://www.oscs1024.com/hd/MPS-2019-4006)|CVE-2019-0232|高危|
|jQuery < 3.4.0 跨站脚本漏洞|原型污染|[MPS-2019-4192](https://www.oscs1024.com/hd/MPS-2019-4192)|CVE-2019-11358|中危|
|Oracle MySQL Connectors 输入验证错误漏洞|使用不兼容类型访问资源（类型混淆）|[MPS-2019-4430](https://www.oscs1024.com/hd/MPS-2019-4430)|CVE-2019-2692|中危|
|Spring Data JPA 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2019-4857](https://www.oscs1024.com/hd/MPS-2019-4857)|CVE-2019-3797|中危|
|FasterXML jackson-databind 反序列化漏洞(mysql gadget绕过)|反序列化|[MPS-2019-5442](https://www.oscs1024.com/hd/MPS-2019-5442)|CVE-2019-12086|高危|
|Apache Tomcat 跨站脚本漏洞|XSS|[MPS-2019-5944](https://www.oscs1024.com/hd/MPS-2019-5944)|CVE-2019-0221|中危|
|Spring Data JPA 信息泄露漏洞|未授权敏感信息泄露|[MPS-2019-6072](https://www.oscs1024.com/hd/MPS-2019-6072)|CVE-2019-3802|中危|
|FasterXML jackson-databind 反序列化漏洞(jdom gadget绕过)|反序列化|[MPS-2019-6867](https://www.oscs1024.com/hd/MPS-2019-6867)|CVE-2019-12814|中危|
|Apache Tomcat 资源管理错误漏洞|加锁机制不恰当|[MPS-2019-7027](https://www.oscs1024.com/hd/MPS-2019-7027)|CVE-2019-10072|高危|
|FasterXML jackson-databind 反序列化漏洞(logback-classic gadget绕过)|反序列化|[MPS-2019-7047](https://www.oscs1024.com/hd/MPS-2019-7047)|CVE-2019-12384|中危|
|FasterXML jackson-databind 反序列化漏洞(iBatis gadget绕过)|反序列化|[MPS-2019-7711](https://www.oscs1024.com/hd/MPS-2019-7711)|CVE-2018-11307|严重|
|FasterXML jackson-databind 反序列化漏洞(ehcache gadget绕过)|动态确定对象属性修改的控制不恰当|[MPS-2019-8717](https://www.oscs1024.com/hd/MPS-2019-8717)|CVE-2019-14379|严重|
|FasterXML jackson-databind 信息泄露漏洞(logback gadget绕过)|反序列化|[MPS-2019-8770](https://www.oscs1024.com/hd/MPS-2019-8770)|CVE-2019-14439|高危|
|Elasticsearch 存在竞争条件漏洞|竞争条件|[MPS-2019-8854](https://www.oscs1024.com/hd/MPS-2019-8854)|CVE-2019-7614|中危|
|Jolokia跨站请求伪造漏洞|CSRF|[MPS-2019-8951](https://www.oscs1024.com/hd/MPS-2019-8951)|CVE-2018-10899|高危|
|HTTP/2 拒绝服务漏洞|拒绝服务|[MPS-2019-9698](https://www.oscs1024.com/hd/MPS-2019-9698)|CVE-2019-9512|高危|
|io.netty:netty-codec-http2 <4.1.39.Final 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2019-9700](https://www.oscs1024.com/hd/MPS-2019-9700)|CVE-2019-9514|高危|
|Netty HTTP/2 存在资源管理错误漏洞|不加限制或调节的资源分配|[MPS-2019-9701](https://www.oscs1024.com/hd/MPS-2019-9701)|CVE-2019-9515|高危|
|io.netty:netty-codec-http2 <4.1.39.Final 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2019-9703](https://www.oscs1024.com/hd/MPS-2019-9703)|CVE-2019-9518|高危|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|FasterXML jackson-databind反序列化漏洞(net.sf.ehcache gadget绕过)|反序列化|[MPS-2020-0063](https://www.oscs1024.com/hd/MPS-2020-0063)|CVE-2019-20330|严重|
|Pivotal Spring Framework <5.2.3.RELEASE 反射文件下载 (RFD) 漏洞|下载代码缺少完整性检查|[MPS-2020-0902](https://www.oscs1024.com/hd/MPS-2020-0902)|CVE-2020-5398|高危|
|FasterXML jackson-databind反序列化漏洞(Anteros-DBCP gadget绕过)|反序列化|[MPS-2020-11987](https://www.oscs1024.com/hd/MPS-2020-11987)|CVE-2020-24616|高危|
|FasterXML jackson-databind 反序列化漏洞(pastdev gadget绕过)|反序列化|[MPS-2020-13151](https://www.oscs1024.com/hd/MPS-2020-13151)|CVE-2020-24750|高危|
|Netty <=4.1.43.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1320](https://www.oscs1024.com/hd/MPS-2020-1320)|CVE-2020-7238|高危|
|Pivotal Spring Framework 反射文件下载 (RFD) 漏洞|路径遍历|[MPS-2020-13322](https://www.oscs1024.com/hd/MPS-2020-13322)|CVE-2020-5421|中危|
|MyBatis <3.5.6 存在反序列化漏洞|反序列化|[MPS-2020-14133](https://www.oscs1024.com/hd/MPS-2020-14133)|CVE-2020-26945|高危|
|Junit 信息泄露漏洞|不安全的临时文件|[MPS-2020-15183](https://www.oscs1024.com/hd/MPS-2020-15183)|CVE-2020-15250|中危|
|Netty <4.1.44.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1526](https://www.oscs1024.com/hd/MPS-2020-1526)|CVE-2019-20444|严重|
|Netty <4.1.44.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1527](https://www.oscs1024.com/hd/MPS-2020-1527)|CVE-2019-20445|严重|
|Apache Tomcat HTTP请求走私漏洞|HTTP请求走私|[MPS-2020-15344](https://www.oscs1024.com/hd/MPS-2020-15344)|CVE-2020-13943|中危|
|jQuery 跨站脚本漏洞|XSS|[MPS-2020-15461](https://www.oscs1024.com/hd/MPS-2020-15461)|CVE-2020-11023|中危|
|jQuery 跨站脚本漏洞|XSS|[MPS-2020-15462](https://www.oscs1024.com/hd/MPS-2020-15462)|CVE-2020-11022|中危|
|Elasticsearch 存在权限管理不恰当漏洞|权限管理不当|[MPS-2020-15777](https://www.oscs1024.com/hd/MPS-2020-15777)|CVE-2020-7020|低危|
|hibernate-core <5.4.24.Final 存在 SQL 注入漏洞|SQL注入|[MPS-2020-16768](https://www.oscs1024.com/hd/MPS-2020-16768)|CVE-2020-25638|高危|
|Apache HttpClient URI解析错误漏洞|XSS|[MPS-2020-17341](https://www.oscs1024.com/hd/MPS-2020-17341)|CVE-2020-13956|中危|
|FasterXML jackson-databind 代码问题漏洞|XXE|[MPS-2020-17358](https://www.oscs1024.com/hd/MPS-2020-17358)|CVE-2020-25649|高危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2020-17486](https://www.oscs1024.com/hd/MPS-2020-17486)|CVE-2020-17527|高危|
|Apache Groovy 临时目录信息泄露漏洞|缺省权限不正确|[MPS-2020-17573](https://www.oscs1024.com/hd/MPS-2020-17573)|CVE-2020-17521|中危|
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
|io.projectreactor.netty:reactor-netty 存在凭证泄露漏洞|凭证保护不足|[MPS-2020-3108](https://www.oscs1024.com/hd/MPS-2020-3108)|CVE-2020-5404|中危|
|Pivotal Software Reactor Netty HttpServer 存在分布式拒绝服务攻击漏洞|对异常条件的处理不恰当|[MPS-2020-3109](https://www.oscs1024.com/hd/MPS-2020-3109)|CVE-2020-5403|高危|
|mysql:mysql-connector-java <8.0.27 存在 XXE 漏洞|XXE|[MPS-2020-38350](https://www.oscs1024.com/hd/MPS-2020-38350)|CVE-2021-2471|中危|
|FasterXML jackson-databind反序列化漏洞(aries.transaction.jms gadget绕过)|反序列化|[MPS-2020-4131](https://www.oscs1024.com/hd/MPS-2020-4131)|CVE-2020-10672|高危|
|FasterXML jackson-databind反序列化漏洞(caucho-quercus gadget绕过)|反序列化|[MPS-2020-4132](https://www.oscs1024.com/hd/MPS-2020-4132)|CVE-2020-10673|高危|
|FasterXML jackson-databind反序列化漏洞(bus-proxy gadget绕过)|反序列化|[MPS-2020-4658](https://www.oscs1024.com/hd/MPS-2020-4658)|CVE-2020-10968|高危|
|FasterXML jackson-databind反序列化漏洞(javax.swing gadget绕过)|反序列化|[MPS-2020-4659](https://www.oscs1024.com/hd/MPS-2020-4659)|CVE-2020-10969|高危|
|FasterXML jackson-databind反序列化漏洞(activemq gadget绕过)|反序列化|[MPS-2020-4754](https://www.oscs1024.com/hd/MPS-2020-4754)|CVE-2020-11111|高危|
|FasterXML jackson-databind反序列化漏洞(commons-proxy gadget绕过)|反序列化|[MPS-2020-4755](https://www.oscs1024.com/hd/MPS-2020-4755)|CVE-2020-11112|高危|
|FasterXML jackson-databind反序列化漏洞(openjpa gadget绕过)|反序列化|[MPS-2020-4756](https://www.oscs1024.com/hd/MPS-2020-4756)|CVE-2020-11113|高危|
|Pivotal Software Reactor Netty HttpServer 存在分布式拒绝服务攻击漏洞|拒绝服务|[MPS-2020-50265](https://www.oscs1024.com/hd/MPS-2020-50265)||中危|
|Netty ZlibDecoders 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2020-5127](https://www.oscs1024.com/hd/MPS-2020-5127)|CVE-2020-11612|高危|
|FasterXML jackson-databind 反序列化漏洞(spring-aop gadget绕过)|反序列化|[MPS-2020-5138](https://www.oscs1024.com/hd/MPS-2020-5138)|CVE-2020-11619|高危|
|FasterXML jackson-databind 反序列化漏洞(commons-jelly gadget绕过)|反序列化|[MPS-2020-5139](https://www.oscs1024.com/hd/MPS-2020-5139)|CVE-2020-11620|高危|
|dom4j SaxReader函数存在 XXE 漏洞|XXE|[MPS-2020-6967](https://www.oscs1024.com/hd/MPS-2020-6967)|CVE-2020-10683|严重|
|hibernate-validator 存在输入验证错误漏洞|代码注入|[MPS-2020-7077](https://www.oscs1024.com/hd/MPS-2020-7077)|CVE-2020-10693|中危|
|Spring Security Crypto 弱加密漏洞|使用不充分的随机数|[MPS-2020-7449](https://www.oscs1024.com/hd/MPS-2020-7449)|CVE-2020-5408|中危|
|Apache Tomcat 远程代码执行漏洞|反序列化|[MPS-2020-7626](https://www.oscs1024.com/hd/MPS-2020-7626)|CVE-2020-9484|高危|
|FasterXML jackson-databind反序列化漏洞(oracle-aqjms gadget绕过)|反序列化|[MPS-2020-8801](https://www.oscs1024.com/hd/MPS-2020-8801)|CVE-2020-14061|高危|
|FasterXML jackson-databind反序列化漏洞(xalan2 gadget绕过)|反序列化|[MPS-2020-8802](https://www.oscs1024.com/hd/MPS-2020-8802)|CVE-2020-14062|高危|
|FasterXML jackson-databind反序列化漏洞(apache drill gadget绕过)|反序列化|[MPS-2020-8803](https://www.oscs1024.com/hd/MPS-2020-8803)|CVE-2020-14060|高危|
|FasterXML jackson-databind代码问题漏洞(jsecurity gadget绕过)|反序列化|[MPS-2020-8911](https://www.oscs1024.com/hd/MPS-2020-8911)|CVE-2020-14195|高危|
|Apache Tomcat 拒绝服务漏洞|拒绝服务|[MPS-2020-9541](https://www.oscs1024.com/hd/MPS-2020-9541)|CVE-2020-11996|高危|
|Hibernate 存在 SQL 注入漏洞|SQL注入|[MPS-2020-9908](https://www.oscs1024.com/hd/MPS-2020-9908)|CVE-2019-14900|中危|
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
|Elasticsearch 资源管理错误漏洞|未经控制的递归|[MPS-2021-11043](https://www.oscs1024.com/hd/MPS-2021-11043)|CVE-2021-22144|中危|
|Elasticsearch 日志信息泄露漏洞|日志敏感信息泄露|[MPS-2021-1485](https://www.oscs1024.com/hd/MPS-2021-1485)|CVE-2020-7021|中危|
|Netty <4.1.59.Final 存在不安全的临时文件漏洞||[MPS-2021-1580](https://www.oscs1024.com/hd/MPS-2021-1580)|CVE-2021-21290|中危|
|FasterXML jackson-databind 反序列化漏洞(javax.swing gadget绕过)|反序列化|[MPS-2021-1625](https://www.oscs1024.com/hd/MPS-2021-1625)|CVE-2021-20190|高危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-1722](https://www.oscs1024.com/hd/MPS-2021-1722)|CVE-2021-24122|中危|
|Spring Framework <5.3.14 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18854](https://www.oscs1024.com/hd/MPS-2021-18854)|CVE-2021-22060|中危|
|Pivotal Spring Framework 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18890](https://www.oscs1024.com/hd/MPS-2021-18890)|CVE-2021-22096|中危|
|Spring AMQP 安全漏洞|反序列化|[MPS-2021-18891](https://www.oscs1024.com/hd/MPS-2021-18891)|CVE-2021-22097|中危|
|com.h2database:h2 < 2.0.202 XXE漏洞|XXE|[MPS-2021-19502](https://www.oscs1024.com/hd/MPS-2021-19502)|CVE-2021-23463|严重|
|FasterXML jackson-dataformat-cbor 内存耗尽漏洞|不加限制或调节的资源分配|[MPS-2021-1998](https://www.oscs1024.com/hd/MPS-2021-1998)|CVE-2020-28491|高危|
|netplex json-smart-v  分布式拒绝服务攻击|对因果或异常条件的不恰当检查|[MPS-2021-2102](https://www.oscs1024.com/hd/MPS-2021-2102)|CVE-2021-27568|严重|
|Apache Tomcat 信息泄露漏洞|HTTP请求走私|[MPS-2021-2309](https://www.oscs1024.com/hd/MPS-2021-2309)|CVE-2021-25122|高危|
|io.netty:netty-codec-http2 <4.1.60.Final 存在 http 请求走私漏洞|HTTP请求走私|[MPS-2021-2435](https://www.oscs1024.com/hd/MPS-2021-2435)|CVE-2021-21295|中危|
|Apache Tomcat 远程代码执行漏洞|代码注入|[MPS-2021-2466](https://www.oscs1024.com/hd/MPS-2021-2466)|CVE-2021-25329|高危|
|Netty Bzip2Decoder 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28116](https://www.oscs1024.com/hd/MPS-2021-28116)|CVE-2021-37136|高危|
|Netty 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28117](https://www.oscs1024.com/hd/MPS-2021-28117)|CVE-2021-37137|高危|
|Apache Tomcat 拒绝服务漏洞|拒绝服务|[MPS-2021-31848](https://www.oscs1024.com/hd/MPS-2021-31848)|CVE-2021-41079|高危|
|H2数据库存在JNDI注入漏洞|反序列化|[MPS-2021-33243](https://www.oscs1024.com/hd/MPS-2021-33243)|CVE-2021-42392|严重|
|Quality Open Software logback JNDI注入漏洞|反序列化|[MPS-2021-33911](https://www.oscs1024.com/hd/MPS-2021-33911)|CVE-2021-42550|中危|
|thymeleaf-spring5 <3.0.13 存在命令注入漏洞|代码注入|[MPS-2021-35280](https://www.oscs1024.com/hd/MPS-2021-35280)|CVE-2021-43466|严重|
| io.netty:netty-codec-http2 <4.1.61.Final 存在 http 请求走私漏洞|HTTP请求走私|[MPS-2021-3565](https://www.oscs1024.com/hd/MPS-2021-3565)|CVE-2021-21409|中危|
|Oracle MySQL 的 MySQL Connectors 存在授权不当漏洞|授权机制不恰当|[MPS-2021-36587](https://www.oscs1024.com/hd/MPS-2021-36587)|CVE-2022-21363|中危|
|Netty <4.1.71.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2021-36922](https://www.oscs1024.com/hd/MPS-2021-36922)|CVE-2021-43797|中危|
|Apache Tomcat 条件竞争漏洞|竞争条件|[MPS-2021-37218](https://www.oscs1024.com/hd/MPS-2021-37218)|CVE-2021-43980|低危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|Elasticsearch 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-6747](https://www.oscs1024.com/hd/MPS-2021-6747)|CVE-2021-22137|中危|
|Elasticsearch 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-6749](https://www.oscs1024.com/hd/MPS-2021-6749)|CVE-2021-22135|中危|
|Spring Framework权限许可和访问控制问题漏洞|权限管理不当|[MPS-2021-7485](https://www.oscs1024.com/hd/MPS-2021-7485)|CVE-2021-22118|高危|
|json-smart 存在拒绝服务漏洞|越界写入|[MPS-2021-7737](https://www.oscs1024.com/hd/MPS-2021-7737)|CVE-2021-31684|高危|
|Apache Tomcat 环境问题漏洞|HTTP请求走私|[MPS-2021-9711](https://www.oscs1024.com/hd/MPS-2021-9711)|CVE-2021-33037|中危|
|Vmware Spring Framework 安全漏洞|不加限制或调节的资源分配|[MPS-2022-1080](https://www.oscs1024.com/hd/MPS-2022-1080)|CVE-2022-22950|中危|
|Pivotal Spring Framework 安全限制绕过漏洞|大小写敏感处理不恰当|[MPS-2022-1098](https://www.oscs1024.com/hd/MPS-2022-1098)|CVE-2022-22968|中危|
|Pivotal Spring Framework 拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1100](https://www.oscs1024.com/hd/MPS-2022-1100)|CVE-2022-22971|中危|
|Spring Framework spring-beans 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1101](https://www.oscs1024.com/hd/MPS-2022-1101)|CVE-2022-22970|中危|
|Spring Framework 整数溢出漏洞|整数溢出或环绕|[MPS-2022-1106](https://www.oscs1024.com/hd/MPS-2022-1106)|CVE-2022-22976|中危|
|Spring Data MongoDB SpEL 表达式注入漏洞|表达式语言注入|[MPS-2022-1110](https://www.oscs1024.com/hd/MPS-2022-1110)|CVE-2022-22980|高危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|com.fasterxml.jackson.core:jackson-core 存在资源管理错误漏洞|资源管理错误|[MPS-2022-11944](https://www.oscs1024.com/hd/MPS-2022-11944)||中危|
|io.netty:netty-codec-http <4.1.53.Final 存在拒绝服务漏洞|拒绝服务|[MPS-2022-12064](https://www.oscs1024.com/hd/MPS-2022-12064)||中危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|com.fasterxml.jackson.core:jackson-core  BigDecimal拒绝服务漏洞|资源管理错误|[MPS-2022-12166](https://www.oscs1024.com/hd/MPS-2022-12166)||中危|
|Apache HttpClient URI解析错误漏洞|相对路径遍历|[MPS-2022-12292](https://www.oscs1024.com/hd/MPS-2022-12292)||中危|
|Logback SSL证书校验不当漏洞|中间人攻击|[MPS-2022-12411](https://www.oscs1024.com/hd/MPS-2022-12411)||中危|
|com.fasterxml.jackson.core:jackson-databind 存在反序列化漏洞|反序列化|[MPS-2022-12433](https://www.oscs1024.com/hd/MPS-2022-12433)||高危|
|H2 Console 代码注入漏洞|代码注入|[MPS-2022-1435](https://www.oscs1024.com/hd/MPS-2022-1435)|CVE-2022-23221|严重|
|Apache Shiro 权限绕过漏洞|授权检查错误|[MPS-2022-17602](https://www.oscs1024.com/hd/MPS-2022-17602)|CVE-2022-32532|中危|
|Apache XercesJ <=2.12.1 存在XML注入漏洞|XPath盲注|[MPS-2022-1864](https://www.oscs1024.com/hd/MPS-2022-1864)|CVE-2022-23437|中危|
|Elastic Stack Kibana 存在缺少授权漏洞|授权检查缺失|[MPS-2022-2136](https://www.oscs1024.com/hd/MPS-2022-2136)|CVE-2022-23709|中危|
|Elastic Stack Kibana 存在 XSS 漏洞|XSS|[MPS-2022-2137](https://www.oscs1024.com/hd/MPS-2022-2137)|CVE-2022-23710|中危|
|Netty 存在信息泄露漏洞||[MPS-2022-3790](https://www.oscs1024.com/hd/MPS-2022-3790)|CVE-2022-24823|中危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|Netty <4.1.86.Final 存在 CRLF 注入漏洞||[MPS-2022-58552](https://www.oscs1024.com/hd/MPS-2022-58552)|CVE-2022-41915|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|Spring Security通配符路由绕过漏洞|关键资源权限分配不当|[MPS-2022-62832](https://www.oscs1024.com/hd/MPS-2022-62832)|CVE-2023-20860|高危|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Session 3.0.0存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-62838](https://www.oscs1024.com/hd/MPS-2022-62838)|CVE-2023-20866|中危|
|Spring Boot在Cloud Foundry中部署存在路由限制绕过风险|访问控制不当|[MPS-2022-62845](https://www.oscs1024.com/hd/MPS-2022-62845)|CVE-2023-20873|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|H2 数据库明文密码问题|未授权敏感信息泄露|[MPS-2022-65204](https://www.oscs1024.com/hd/MPS-2022-65204)|CVE-2022-45868|高危|
|spring-boot <2.2.11.RELEASE 存在目录劫持漏洞|将资源暴露给错误范围|[MPS-2022-6780](https://www.oscs1024.com/hd/MPS-2022-6780)|CVE-2022-27772|高危|
|spring-beans 远程代码执行漏洞(Spring4Shell)|表达式语言注入|[MPS-2022-6820](https://www.oscs1024.com/hd/MPS-2022-6820)|CVE-2022-22965|严重|
|Oracle MySQL 安全漏洞||[MPS-2022-68556](https://www.oscs1024.com/hd/MPS-2022-68556)|CVE-2023-21971|中危|
|HtmlUnit 存在拒绝服务漏洞|未经控制的内存分配|[MPS-2022-7514](https://www.oscs1024.com/hd/MPS-2022-7514)|CVE-2022-28366|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|【存在争议】MybatisPlus <= 3.5.3.1 TenantPlugin 组件 存在 sql 注入漏洞|SQL注入|[MPS-2023-3977](https://www.oscs1024.com/hd/MPS-2023-3977)|CVE-2023-25330|高危|
|netplex json-smart 安全漏洞|未经控制的递归|[MPS-2023-7760](https://www.oscs1024.com/hd/MPS-2023-7760)|CVE-2023-1370|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|基于 Thymeleaf 沙箱逃逸的 Spring Boot Admin 远程代码执行漏洞|代码注入|[MPS-p6bo-i7nw](https://www.oscs1024.com/hd/MPS-p6bo-i7nw)|CVE-2023-38286|严重|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.apache.tomcat.embed:tomcat-embed-core|9.0.16|11.0.0-m6|间接依赖|强烈建议修复|C:1|H:10|M:5|L:1|
|org.apache.tomcat.embed:tomcat-embed-core|8.5.28|11.0.0-m6|间接依赖|强烈建议修复|C:2|H:11|M:7|L:1|
|de.codecentric:spring-boot-admin-server|2.1.0||间接依赖|强烈建议修复|C:1|H:0|M:0|L:0|
|org.apache.tomcat.embed:tomcat-embed-core|8.5.15|11.0.0-m6|间接依赖|强烈建议修复|C:2|H:13|M:9|L:1|
|org.apache.tomcat.embed:tomcat-embed-core|8.5.14|11.0.0-m6|间接依赖|强烈建议修复|C:2|H:14|M:9|L:1|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.12|11.0.0-m6|间接依赖|强烈建议修复|C:1|H:10|M:5|L:1|
|org.apache.tomcat.embed:tomcat-embed-core|8.5.5|11.0.0-m6|间接依赖|强烈建议修复|C:4|H:19|M:9|L:1|
|org.apache.tomcat.embed:tomcat-embed-core|8.5.16|11.0.0-m6|间接依赖|强烈建议修复|C:2|H:12|M:9|L:1|
|org.apache.tomcat.embed:tomcat-embed-core|8.5.23|11.0.0-m6|间接依赖|强烈建议修复|C:2|H:11|M:9|L:1|
|de.codecentric:spring-boot-admin-server|1.5.6||直接依赖|强烈建议修复|C:1|H:0|M:0|L:0|
|org.jolokia:jolokia-core|1.3.7|1.6.1|间接依赖|强烈建议修复|C:0|H:2|M:1|L:0|
|org.apache.tomcat.embed:tomcat-embed-core|8.5.6|11.0.0-m6|间接依赖|强烈建议修复|C:4|H:19|M:9|L:1|
|mysql:mysql-connector-java|5.1.45|8.0.28|直接依赖|建议修复|C:0|H:1|M:3|L:0|
|org.yaml:snakeyaml|1.19|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|com.fasterxml.jackson.core:jackson-databind|2.6.7|2.14.0-rc1|间接依赖|建议修复|C:26|H:39|M:5|L:0|
|mysql:mysql-connector-java|8.0.15|8.0.28|直接依赖|建议修复|C:0|H:0|M:3|L:0|
|org.springframework.boot:spring-boot-autoconfigure|1.5.9.RELEASE|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.29.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|org.apache.shiro:shiro-spring|1.7.2|1.9.1|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-web|4.3.10.RELEASE|6.0.0|间接依赖|建议修复|C:1|H:2|M:2|L:0|
|ch.qos.logback:logback-classic|1.1.11|1.2.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework.boot:spring-boot|2.1.3.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.h2database:h2|1.4.199|2.1.210|直接依赖|建议修复|C:3|H:1|M:0|L:0|
|org.mybatis:mybatis|3.5.0|3.5.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|mysql:mysql-connector-java|8.0.13|8.0.28|直接依赖|建议修复|C:0|H:0|M:3|L:0|
|org.springframework:spring-webmvc|4.3.10.RELEASE|6.0.7|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.mybatis:mybatis|3.5.1|3.5.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-web|4.3.13.RELEASE|6.0.0|间接依赖|建议修复|C:1|H:2|M:2|L:0|
|org.springframework.boot:spring-boot-autoconfigure|1.5.4.RELEASE|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-context|4.3.4.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-web|4.3.4.RELEASE|6.0.0|间接依赖|建议修复|C:1|H:2|M:2|L:0|
|org.springframework:spring-web|4.3.8.RELEASE|6.0.0|间接依赖|建议修复|C:1|H:2|M:2|L:0|
|org.springframework.boot:spring-boot|2.1.4.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.codehaus.groovy:groovy|2.4.3|4.0.0-alpha-2|间接依赖|建议修复|C:2|H:0|M:1|L:0|
|org.springframework:spring-beans|5.1.4.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|mysql:mysql-connector-java|5.1.43|8.0.28|直接依赖|建议修复|C:0|H:1|M:3|L:0|
|org.springframework.data:spring-data-mongodb|2.1.2.RELEASE|3.4.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-beans|4.3.10.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|ch.qos.logback:logback-core|1.1.11|1.2.8|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|ch.qos.logback:logback-classic|1.1.7|1.2.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.9.4|2.14.0-rc1|间接依赖|建议修复|C:23|H:38|M:5|L:0|
|org.springframework:spring-context|5.1.5.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework.boot:spring-boot|2.1.0.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-web|5.0.4.RELEASE|6.0.0|间接依赖|建议修复|C:1|H:4|M:2|L:0|
|org.springframework.boot:spring-boot-autoconfigure|1.5.3.RELEASE|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.thymeleaf:thymeleaf-spring5|3.0.11.RELEASE|3.0.13.RELEASE|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework.boot:spring-boot|1.5.9.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.mysql:mysql-connector-j|8.0.31|8.0.33|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-webmvc|4.3.8.RELEASE|6.0.7|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.springframework:spring-webmvc|5.0.4.RELEASE|6.0.7|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|net.minidev:json-smart|2.4.8|2.4.9|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.springfox:springfox-swagger-ui|2.9.2|2.10.0|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-context|5.1.6.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.0.4.RELEASE|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.23|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|mysql:mysql-connector-java|5.1.39|8.0.28|直接依赖|建议修复|C:0|H:2|M:4|L:1|
|org.springframework:spring-core|4.3.10.RELEASE|6.0.7|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|org.springframework:spring-web|5.1.5.RELEASE|6.0.0|间接依赖|建议修复|C:1|H:2|M:1|L:0|
|org.springframework:spring-context|4.3.10.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.1.2.RELEASE|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-beans|4.2.7.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework:spring-context|4.3.3.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework.data:spring-data-commons|1.13.4.RELEASE|2.0.6.RELEASE|间接依赖|建议修复|C:1|H:1|M:0|L:0|
|org.springframework.boot:spring-boot|1.5.4.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|1.4.2.RELEASE|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.1.0.RELEASE|3.0.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-beans|5.0.4.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework:spring-webmvc|4.3.4.RELEASE|6.0.7|间接依赖|建议修复|C:0|H:3|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.9.7|2.14.0-rc1|间接依赖|建议修复|C:17|H:36|M:5|L:0|
|org.springframework.boot:spring-boot|1.4.1.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-beans|4.3.4.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|io.projectreactor.netty:reactor-netty|0.8.2.RELEASE|1.0.24|间接依赖|建议修复|C:0|H:2|M:2|L:0|
|org.springframework:spring-webmvc|4.3.13.RELEASE|6.0.7|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|io.netty:netty-codec|4.1.31.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|mysql:mysql-connector-java|5.1.44|8.0.28|直接依赖|建议修复|C:0|H:1|M:3|L:0|
|org.springframework:spring-web|5.1.4.RELEASE|6.0.0|间接依赖|建议修复|C:1|H:2|M:1|L:0|
|org.springframework:spring-webmvc|4.2.7.RELEASE|6.0.7|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.springframework:spring-context|5.0.8.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-web|5.1.2.RELEASE|6.0.0|间接依赖|建议修复|C:1|H:2|M:1|L:0|
|org.springframework.boot:spring-boot|1.5.3.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.1.0.RELEASE|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-core|4.3.8.RELEASE|6.0.7|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|org.springframework:spring-webmvc|4.3.3.RELEASE|6.0.7|间接依赖|建议修复|C:0|H:3|M:1|L:0|
|org.springframework:spring-core|5.0.4.RELEASE|6.0.7|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|org.springframework.boot:spring-boot|2.1.2.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.33|2.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.85.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-messaging|5.1.2.RELEASE|5.3.20|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-core|4.3.13.RELEASE|6.0.7|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|com.baomidou:mybatis-plus-extension|3.1.1||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.14.1||间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-context|4.3.13.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework.boot:spring-boot-autoconfigure|1.3.6.RELEASE|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|ch.qos.logback:logback-core|1.1.7|1.2.8|间接依赖|建议修复|C:1|H:0|M:2|L:0|
|org.springframework:spring-context|4.3.9.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.8.9|2.14.0-rc1|间接依赖|建议修复|C:25|H:38|M:5|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.8.4|2.14.0-rc1|间接依赖|建议修复|C:26|H:38|M:5|L:0|
|org.springframework:spring-context|5.1.4.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework.boot:spring-boot|2.0.0.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-web|4.3.3.RELEASE|6.0.0|间接依赖|建议修复|C:1|H:2|M:2|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.9.8|2.14.0-rc1|间接依赖|建议修复|C:14|H:36|M:5|L:0|
|io.netty:netty-codec|4.1.29.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.0.0.RELEASE|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-messaging|4.3.4.RELEASE|5.3.20|间接依赖|建议修复|C:2|H:0|M:2|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.8.8|2.14.0-rc1|间接依赖|建议修复|C:26|H:38|M:5|L:0|
|org.springframework:spring-core|4.3.4.RELEASE|6.0.7|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|org.springframework:spring-beans|4.3.3.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework:spring-beans|5.1.6.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.webjars.bower:jquery|2.0.3|3.5.0|直接依赖|建议修复|C:0|H:0|M:6|L:0|
|org.springframework.boot:spring-boot-autoconfigure|1.4.1.RELEASE|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|ch.qos.logback:logback-core|1.2.3|1.2.8|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-context|4.2.7.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|net.minidev:json-smart|2.3|2.4.9|间接依赖|建议修复|C:1|H:2|M:0|L:0|
|org.springframework.data:spring-data-commons|2.0.5.RELEASE|2.0.6.RELEASE|间接依赖|建议修复|C:1|H:1|M:0|L:0|
|org.hibernate:hibernate-core|5.0.12.Final|5.4.24.Final|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|org.springframework:spring-beans|4.3.13.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.elasticsearch:elasticsearch|6.4.2|8.2.1|间接依赖|建议修复|C:0|H:1|M:9|L:1|
|org.springframework.data:spring-data-commons|1.13.3.RELEASE|2.0.6.RELEASE|间接依赖|建议修复|C:1|H:1|M:0|L:0|
|org.mybatis:mybatis|3.4.0|3.5.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-beans|4.3.9.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework.boot:spring-boot|2.0.4.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|1.5.6.RELEASE|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-webmvc|6.0.2|6.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|mysql:mysql-connector-java|5.1.42|8.0.28|直接依赖|建议修复|C:0|H:1|M:3|L:0|
|io.netty:netty-codec-http|4.1.29.Final|4.1.86.final|间接依赖|建议修复|C:2|H:2|M:5|L:0|
|org.springframework:spring-context|4.3.8.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.hibernate:hibernate-validator|5.2.4.Final|6.1.3.Final|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|org.jolokia:jolokia-core|1.6.0|1.6.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-context|5.0.4.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.8.3|2.14.0-rc1|间接依赖|建议修复|C:26|H:38|M:5|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.1.4.RELEASE|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.17|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|org.springframework:spring-context|5.1.2.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework.data:spring-data-mongodb|1.10.3.RELEASE|3.4.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.16|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|org.hibernate:hibernate-core|5.2.14.Final|5.4.24.Final|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|io.netty:netty-handler|4.1.31.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|org.thymeleaf:thymeleaf-spring5|3.0.9.RELEASE|3.0.13.RELEASE|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework:spring-web|4.2.7.RELEASE|6.0.0|间接依赖|建议修复|C:1|H:1|M:1|L:0|
|org.webjars.bower:bootstrap|3.0.3|4.3.1|直接依赖|建议修复|C:0|H:0|M:6|L:0|
|org.springframework.boot:spring-boot|1.3.6.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot|1.4.2.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.hibernate:hibernate-core|5.3.7.Final|5.4.24.Final|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|org.dom4j:dom4j|2.1.1|2.1.2|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework:spring-beans|5.0.8.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.8.10|2.14.0-rc1|间接依赖|建议修复|C:24|H:38|M:5|L:0|
|org.springframework:spring-core|4.3.3.RELEASE|6.0.7|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.1.3.RELEASE|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.data:spring-data-commons|1.13.6.RELEASE|2.0.6.RELEASE|间接依赖|建议修复|C:1|H:1|M:0|L:0|
|io.projectreactor.netty:reactor-netty|0.8.4.RELEASE|1.0.24|间接依赖|建议修复|C:0|H:2|M:2|L:0|
|io.netty:netty-codec-http|4.1.31.Final|4.1.86.final|间接依赖|建议修复|C:2|H:2|M:5|L:0|
|org.hibernate:hibernate-validator|5.3.5.Final|6.1.3.Final|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|org.springframework:spring-beans|4.3.8.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|dom4j:dom4j|1.6.1||间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework:spring-beans|5.1.2.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework:spring-beans|5.1.5.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework:spring-webmvc|4.3.9.RELEASE|6.0.7|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.springframework:spring-web|4.3.9.RELEASE|6.0.0|间接依赖|建议修复|C:1|H:2|M:2|L:0|
|org.springframework.boot:spring-boot|1.5.6.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|mysql:mysql-connector-java|5.1.40|8.0.28|直接依赖|建议修复|C:0|H:2|M:4|L:1|
|org.springframework.security:spring-security-crypto|4.2.3.RELEASE|5.6.4|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework.boot:spring-boot-autoconfigure|3.0.0|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-expression|4.3.4.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.springframework.session:spring-session-core|3.0.0|3.0.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-http2|4.1.31.Final|4.1.61.Final|间接依赖|可选修复|C:0|H:4|M:2|L:0|
|org.hibernate:hibernate-validator|5.3.6.Final|6.1.3.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.codehaus.groovy:groovy|2.4.12|4.0.0-alpha-2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.fasterxml.jackson.core:jackson-core|2.8.3|2.8.6|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-common|4.1.29.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-expression|4.3.9.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|com.rabbitmq:amqp-client|3.6.5|5.4.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|4.3.8.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.springframework.data:spring-data-jpa|2.1.2.RELEASE|2.1.8.RELEASE|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|20.0|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|org.springframework:spring-expression|4.2.7.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.springframework:spring-expression|5.1.2.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|io.netty:netty-common|4.1.31.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|io.netty:netty-codec-http|4.1.85.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|net.sourceforge.nekohtml:nekohtml|1.9.22||直接依赖|可选修复|C:0|H:1|M:0|L:0|
|junit:junit|4.12|4.13.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.httpcomponents:httpclient|4.5.3|4.5.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.9.7|2.12.1|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|io.netty:netty-transport-native-epoll|4.1.31.Final|4.1.59.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework.data:spring-data-jpa|1.11.6.RELEASE|2.1.8.RELEASE|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.fasterxml.jackson.core:jackson-core|2.8.4|2.8.6|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-core|4.2.7.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|io.netty:netty-transport-native-epoll|4.1.29.Final|4.1.59.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.hibernate.validator:hibernate-validator|6.0.14.Final|6.1.3.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|18.0|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|org.springframework.data:spring-data-jpa|2.1.5.RELEASE|2.1.8.RELEASE|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-core|5.1.2.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-expression|5.0.4.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|commons-io:commons-io|2.4|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.codehaus.groovy:groovy|2.4.13|4.0.0-alpha-2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.hibernate.validator:hibernate-validator|6.0.7.Final|6.1.3.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-expression|5.1.5.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.springframework.amqp:spring-amqp|2.1.0.RELEASE|2.3.12|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.fasterxml.jackson.core:jackson-core|2.6.7|2.8.6|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.hibernate.validator:hibernate-validator|6.0.13.Final|6.1.3.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.codehaus.groovy:groovy|2.4.11|4.0.0-alpha-2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-core|6.0.2|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|4.3.13.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.springframework:spring-core|5.0.8.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-expression|5.0.8.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.apache.httpcomponents:httpclient|4.5.2|4.5.13|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework.data:spring-data-jpa|1.11.4.RELEASE|2.1.8.RELEASE|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|commons-codec:commons-codec|1.11|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.springframework:spring-expression|4.3.10.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.codehaus.groovy:groovy|2.4.10|4.0.0-alpha-2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-http2|4.1.29.Final|4.1.61.Final|间接依赖|可选修复|C:0|H:4|M:2|L:0|
|org.springframework.amqp:spring-amqp|1.6.5.RELEASE|2.3.12|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.apache.httpcomponents:httpclient|4.5.6|4.5.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.9.7|2.9.8|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|5.1.6.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.9.4|2.9.8|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|xerces:xercesImpl|2.11.0|2.12.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-codec:commons-codec|1.10|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.springframework:spring-expression|4.3.3.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.codehaus.groovy:groovy|2.5.3|4.0.0-alpha-2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework.data:spring-data-jpa|2.0.5.RELEASE|2.1.8.RELEASE|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-expression|5.1.4.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.springframework:spring-expression|6.0.2|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|695|Low|
|EPL-1.0|16|Low|
|LGPL-2.1-or-later|8|Low|
|EPL-2.0|12|Low|
|BSD-2-Clause|1|Low|
|MIT|19|Low|
|LGPL-2.1|6|Medium|
|MPL-1.1|8|Low|
|CDDL-1.1|2|Low|
|BSD-3-Clause|3|Low|
|MIT-0|2|Low|
|GPL-2.0|3|Medium|
|MPL-2.0|2|Low|
|CDDL-1.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.jboss:jandex|2.0.5.Final|间接依赖|maven|
|ch.qos.logback:logback-classic|1.1.7|间接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|de.codecentric:spring-boot-admin-server|2.1.0|间接依赖|maven|
|com.rabbitmq:http-client|1.0.0.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.8.9|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|1.4.2.RELEASE|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|8.5.23|间接依赖|maven|
|org.hibernate:hibernate-core|5.3.7.Final|间接依赖|maven|
|org.springframework.data:spring-data-jpa|3.0.0|间接依赖|maven|
|org.springframework:spring-beans|6.0.2|间接依赖|maven|
|io.netty:netty-transport|4.1.31.Final|间接依赖|maven|
|org.springframework:spring-web|4.3.3.RELEASE|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.3|间接依赖|maven|
|org.springframework.data:spring-data-elasticsearch|3.1.2.RELEASE|间接依赖|maven|
|org.springframework:spring-beans|4.3.9.RELEASE|间接依赖|maven|
|org.springframework:spring-expression|6.0.2|间接依赖|maven|
|org.springframework:spring-orm|4.3.10.RELEASE|间接依赖|maven|
|org.springframework:spring-expression|5.0.4.RELEASE|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.10|间接依赖|maven|
|org.apache.tomcat:tomcat-jdbc|8.5.23|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-engine|5.9.1|间接依赖|maven|
|org.slf4j:log4j-over-slf4j|1.7.25|间接依赖|maven|
|org.elasticsearch.plugin:lang-mustache-client|6.4.2|间接依赖|maven|
|org.mybatis:mybatis-spring|1.3.0|间接依赖|maven|
|io.netty:netty-common|4.1.31.Final|间接依赖|maven|
|jakarta.persistence:jakarta.persistence-api|3.1.0|间接依赖|maven|
|io.netty:netty-codec-http|4.1.85.Final|间接依赖|maven|
|org.springframework.cloud:spring-cloud-context|1.3.1.RELEASE|间接依赖|maven|
|de.codecentric:spring-boot-admin-starter-client|1.5.6|直接依赖|maven|
|org.springframework:spring-jcl|5.0.4.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-amqp|1.4.2.RELEASE|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-thymeleaf|3.0.0|直接依赖|maven|
|de.codecentric:spring-boot-admin-server-ui|1.5.6|直接依赖|maven|
|org.springframework:spring-context|5.1.4.RELEASE|间接依赖|maven|
|org.springframework:spring-context-support|5.1.2.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|1.5.6.RELEASE|间接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-starter|1.1.1|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-mail|1.5.3.RELEASE|直接依赖|maven|
|org.springframework.data:spring-data-jpa|2.1.5.RELEASE|间接依赖|maven|
|org.springframework.amqp:spring-rabbit|1.6.5.RELEASE|间接依赖|maven|
|org.springframework:spring-aspects|5.1.2.RELEASE|间接依赖|maven|
|org.apache.tomcat:tomcat-jdbc|8.5.15|间接依赖|maven|
|xerces:xercesImpl|2.11.0|间接依赖|maven|
|org.codehaus.groovy:groovy|2.4.12|间接依赖|maven|
|org.springframework.boot:spring-boot|2.1.4.RELEASE|间接依赖|maven|
|com.fasterxml:classmate|1.3.1|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.9|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.6.7|间接依赖|maven|
|org.apache.groovy:groovy|4.0.6|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|8.5.14|间接依赖|maven|
|org.springframework.data:spring-data-jpa|1.11.6.RELEASE|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.25|间接依赖|maven|
|org.javassist:javassist|3.18.1-GA|间接依赖|maven|
|ch.qos.logback:logback-classic|1.4.5|间接依赖|maven|
|org.apache.shiro:shiro-spring|1.7.2|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.1.3.RELEASE|间接依赖|maven|
|com.sun.mail:javax.mail|RELEASE|直接依赖|maven|
|org.springframework:spring-aop|4.3.3.RELEASE|间接依赖|maven|
|org.springframework:spring-aspects|4.3.9.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|1.4.1.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|1.5.4.RELEASE|间接依赖|maven|
|org.apache.lucene:lucene-analyzers-common|7.4.0|间接依赖|maven|
|org.springframework:spring-expression|4.2.7.RELEASE|间接依赖|maven|
|org.mockito:mockito-junit-jupiter|4.8.1|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.9.7|间接依赖|maven|
|org.springframework.boot:spring-boot|2.1.3.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-webflux|2.1.0.RELEASE|间接依赖|maven|
|javax.validation:validation-api|1.1.0.Final|间接依赖|maven|
|org.springframework:spring-beans|4.3.3.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|1.4.2.RELEASE|间接依赖|maven|
|org.hibernate:hibernate-validator|5.3.6.Final|间接依赖|maven|
|io.springfox:springfox-schema|2.9.2|间接依赖|maven|
|org.mockito:mockito-core|4.8.1|间接依赖|maven|
|org.springframework:spring-jdbc|5.1.6.RELEASE|间接依赖|maven|
|org.attoparser:attoparser|2.0.4.RELEASE|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.21|间接依赖|maven|
|org.springframework:spring-aspects|5.1.5.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-devtools|1.4.1.RELEASE|直接依赖|maven|
|org.springframework:spring-context|4.3.9.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-redis|3.0.0|直接依赖|maven|
|org.opentest4j:opentest4j|1.2.0|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|4.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-thymeleaf|1.5.4.RELEASE|直接依赖|maven|
|org.springframework:spring-beans|4.2.7.RELEASE|间接依赖|maven|
|org.springframework:spring-beans|4.3.13.RELEASE|间接依赖|maven|
|org.springframework:spring-aop|4.2.7.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.9.8|间接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-autoconfigure|1.1.1|间接依赖|maven|
|commons-lang:commons-lang|2.6|间接依赖|maven|
|org.springframework.data:spring-data-commons|1.13.6.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.0.0.RELEASE|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-api|5.9.1|间接依赖|maven|
|org.springframework.data:spring-data-commons|2.1.5.RELEASE|间接依赖|maven|
|org.springframework:spring-aop|4.3.9.RELEASE|间接依赖|maven|
|org.springframework:spring-context|4.3.13.RELEASE|间接依赖|maven|
|org.slf4j:slf4j-api|2.0.4|间接依赖|maven|
|org.hibernate.common:hibernate-commons-annotations|6.0.2.Final|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|2.1.0|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.9.7|间接依赖|maven|
|org.springframework.data:spring-data-mongodb|4.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|1.5.4.RELEASE|直接依赖|maven|
|org.springframework.amqp:spring-amqp|2.1.0.RELEASE|间接依赖|maven|
|org.springframework.retry:spring-retry|1.1.4.RELEASE|间接依赖|maven|
|org.springframework:spring-expression|4.3.3.RELEASE|间接依赖|maven|
|org.thymeleaf.extras:thymeleaf-extras-java8time|3.0.1.RELEASE|间接依赖|maven|
|javax.validation:validation-api|2.0.1.Final|间接依赖|maven|
|org.springframework.amqp:spring-amqp|3.0.0|间接依赖|maven|
|net.minidev:accessors-smart|2.4.8|间接依赖|maven|
|ognl:ognl|3.3.4|间接依赖|maven|
|org.aspectj:aspectjweaver|1.8.10|间接依赖|maven|
|org.hibernate:hibernate-validator|5.2.4.Final|间接依赖|maven|
|org.springframework:spring-context|4.2.7.RELEASE|间接依赖|maven|
|org.springframework:spring-core|4.3.3.RELEASE|间接依赖|maven|
|org.springframework.data:spring-data-commons|1.13.4.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|1.5.3.RELEASE|直接依赖|maven|
|org.springframework.retry:spring-retry|2.0.0|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|10.1.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-mongodb|3.0.0|直接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.19.0|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.1|间接依赖|maven|
|org.springframework.session:spring-session-core|2.1.1.RELEASE|间接依赖|maven|
|org.mongodb:mongodb-driver|3.8.2|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|8.5.16|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|1.5.6.RELEASE|间接依赖|maven|
|org.springframework:spring-aop|4.3.13.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|1.3.6.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.9.8|间接依赖|maven|
|org.springframework.boot:spring-boot|1.5.6.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-test|3.0.0|直接依赖|maven|
|org.springframework:spring-tx|5.1.2.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-test-autoconfigure|2.1.0.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-jpa|2.1.3.RELEASE|直接依赖|maven|
|io.micrometer:micrometer-commons|1.10.2|间接依赖|maven|
|org.springframework:spring-webflux|5.1.2.RELEASE|间接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|org.springframework:spring-jdbc|5.1.2.RELEASE|间接依赖|maven|
|io.swagger:swagger-annotations|1.5.20|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.1.3.RELEASE|间接依赖|maven|
|org.springframework:spring-context|6.0.2|间接依赖|maven|
|org.elasticsearch:elasticsearch-x-content|6.4.2|间接依赖|maven|
|jakarta.inject:jakarta.inject-api|2.0.0|间接依赖|maven|
|org.jboss:jandex|2.0.3.Final|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.5|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|8.5.15|间接依赖|maven|
|nz.net.ultraq.groovy:groovy-extensions|2.0.0|间接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-starter|3.0.0|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|8.5.16|间接依赖|maven|
|ognl:ognl|3.1.12|间接依赖|maven|
|io.projectreactor.netty:reactor-netty|0.8.2.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.8.8|间接依赖|maven|
|com.sun.istack:istack-commons-runtime|4.1.1|间接依赖|maven|
|antlr:antlr|2.7.7|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|1.5.9.RELEASE|直接依赖|maven|
|org.springframework:spring-core|4.3.13.RELEASE|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.16|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-redis|2.1.0.RELEASE|直接依赖|maven|
|org.hibernate:hibernate-validator|5.3.5.Final|间接依赖|maven|
|org.elasticsearch.plugin:transport-netty4-client|6.4.2|间接依赖|maven|
|org.springframework.data:spring-data-commons|2.1.2.RELEASE|间接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-client|6.4.2|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.21|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|1.4.2.RELEASE|间接依赖|maven|
|org.thymeleaf:thymeleaf-spring5|3.0.9.RELEASE|间接依赖|maven|
|mysql:mysql-connector-java|5.1.42|直接依赖|maven|
|org.springframework.session:spring-session-data-redis|1.3.1.RELEASE|直接依赖|maven|
|org.springframework:spring-webflux|6.0.2|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.31.Final|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.29.Final|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.5.0.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|1.4.1.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-reactor-netty|3.0.0|间接依赖|maven|
|org.elasticsearch.plugin:parent-join-client|6.4.2|间接依赖|maven|
|org.springframework:spring-aop|5.1.2.RELEASE|间接依赖|maven|
|org.apache.lucene:lucene-highlighter|7.4.0|间接依赖|maven|
|org.springframework.session:spring-session-core|3.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot-devtools|1.5.3.RELEASE|直接依赖|maven|
|org.springframework:spring-core|4.2.7.RELEASE|间接依赖|maven|
|org.apache.tomcat:tomcat-jdbc|8.5.6|间接依赖|maven|
|org.hibernate:hibernate-core|5.0.12.Final|间接依赖|maven|
|org.unbescape:unbescape|1.1.0.RELEASE|间接依赖|maven|
|net.sf.jopt-simple:jopt-simple|5.0.2|间接依赖|maven|
|org.springframework.data:spring-data-commons|2.0.5.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-thymeleaf|2.1.3.RELEASE|直接依赖|maven|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.1.0.RELEASE|间接依赖|maven|
|com.netflix.hystrix:hystrix-core|1.5.12|间接依赖|maven|
|org.springframework:spring-context-support|RELEASE|直接依赖|maven|
|net.sourceforge.nekohtml:nekohtml|1.9.22|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.3|间接依赖|maven|
|org.springframework:spring-web|4.3.10.RELEASE|间接依赖|maven|
|org.springframework:spring-tx|4.3.9.RELEASE|间接依赖|maven|
|org.springframework:spring-web|5.1.4.RELEASE|间接依赖|maven|
|de.codecentric:spring-boot-admin-starter-server|2.1.0|直接依赖|maven|
|org.springframework:spring-jdbc|4.3.9.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|3.0.0|直接依赖|maven|
|com.netflix.netflix-commons:netflix-commons-util|0.1.1|间接依赖|maven|
|org.apache.tomcat:tomcat-juli|8.5.23|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|1.4.2.RELEASE|直接依赖|maven|
|org.springframework:spring-beans|4.3.8.RELEASE|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.25|间接依赖|maven|
|org.springframework.boot:spring-boot-devtools|1.5.9.RELEASE|直接依赖|maven|
|nz.net.ultraq.thymeleaf:thymeleaf-layout-dialect|1.4.0|间接依赖|maven|
|org.springframework:spring-context|4.3.10.RELEASE|间接依赖|maven|
|org.springframework:spring-webmvc|4.3.3.RELEASE|间接依赖|maven|
|io.springfox:springfox-spi|2.9.2|间接依赖|maven|
|org.springframework:spring-webmvc|5.0.4.RELEASE|间接依赖|maven|
|io.netty:netty-codec-http|4.1.29.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|1.5.9.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|3.0.0|间接依赖|maven|
|org.springframework:spring-aspects|6.0.2|间接依赖|maven|
|dom4j:dom4j|1.6.1|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.9.8|间接依赖|maven|
|org.springframework:spring-expression|5.1.4.RELEASE|间接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.10|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator|2.1.0.RELEASE|间接依赖|maven|
|org.springframework:spring-jdbc|4.3.10.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.8.3|间接依赖|maven|
|com.baomidou:mybatis-plus|3.1.1|间接依赖|maven|
|org.thymeleaf:thymeleaf|2.1.5.RELEASE|间接依赖|maven|
|com.zaxxer:HikariCP|3.2.0|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|8.5.28|间接依赖|maven|
|org.springframework:spring-tx|5.1.5.RELEASE|间接依赖|maven|
|org.springframework:spring-tx|4.3.4.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-thymeleaf|1.5.9.RELEASE|直接依赖|maven|
|io.netty:netty-codec-socks|4.1.31.Final|间接依赖|maven|
|org.ow2.asm:asm|5.0.4|间接依赖|maven|
|org.codehaus.groovy:groovy|2.4.11|间接依赖|maven|
|org.thymeleaf:thymeleaf|3.0.11.RELEASE|间接依赖|maven|
|org.springframework:spring-webmvc|4.3.8.RELEASE|间接依赖|maven|
|org.springframework:spring-oxm|5.1.2.RELEASE|间接依赖|maven|
|org.springframework:spring-webmvc|4.3.4.RELEASE|间接依赖|maven|
|org.elasticsearch.plugin:rank-eval-client|6.4.2|间接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.4|间接依赖|maven|
|org.assertj:assertj-core|3.11.1|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.9.3|间接依赖|maven|
|org.springframework.boot:spring-boot|1.3.6.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.9.7|间接依赖|maven|
|io.netty:netty-codec|4.1.31.Final|间接依赖|maven|
|org.elasticsearch.client:transport|6.4.2|间接依赖|maven|
|org.springframework:spring-tx|4.3.8.RELEASE|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.29.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|3.0.0|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.9.4|间接依赖|maven|
|org.springframework.boot:spring-boot|2.1.0.RELEASE|间接依赖|maven|
|org.glassfish.jaxb:jaxb-core|4.0.1|间接依赖|maven|
|org.mybatis:mybatis|3.4.0|间接依赖|maven|
|com.netflix.servo:servo-internal|0.10.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.1.3.RELEASE|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.10.0|间接依赖|maven|
|org.apache.lucene:lucene-queryparser|7.4.0|间接依赖|maven|
|org.apache.lucene:lucene-suggest|7.4.0|间接依赖|maven|
|org.springframework.boot:spring-boot-test|2.1.0.RELEASE|间接依赖|maven|
|io.projectreactor:reactor-core|3.2.2.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot|1.5.3.RELEASE|间接依赖|maven|
|org.springframework:spring-expression|4.3.13.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.9.0|间接依赖|maven|
|org.springframework:spring-expression|5.1.2.RELEASE|间接依赖|maven|
|org.springframework.data:spring-data-redis|3.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|1.5.6.RELEASE|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.1.0.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-thymeleaf|2.1.0.RELEASE|直接依赖|maven|
|org.jboss.logging:jboss-logging|3.3.1.Final|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.85.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.1.3.RELEASE|直接依赖|maven|
|org.springframework:spring-core|5.1.2.RELEASE|间接依赖|maven|
|mysql:mysql-connector-java|5.1.45|直接依赖|maven|
|org.springframework:spring-webmvc|4.3.9.RELEASE|间接依赖|maven|
|de.codecentric:spring-boot-admin-server|1.5.6|直接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|1.5.3.RELEASE|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.19.0|间接依赖|maven|
|com.vaadin.external.google:android-json|0.0.20131108.vaadin1|间接依赖|maven|
|io.projectreactor:reactor-core|3.2.5.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-webflux|3.0.0|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|1.5.3.RELEASE|间接依赖|maven|
|nz.net.ultraq.thymeleaf:thymeleaf-layout-dialect|3.1.0|直接依赖|maven|
|org.aspectj:aspectjweaver|1.8.13|间接依赖|maven|
|org.xmlunit:xmlunit-core|2.9.0|间接依赖|maven|
|org.springframework:spring-aspects|5.0.4.RELEASE|间接依赖|maven|
|org.springframework:spring-aspects|4.3.10.RELEASE|间接依赖|maven|
|org.springframework:spring-webmvc|4.3.10.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|RELEASE|直接依赖|maven|
|org.springframework.data:spring-data-mongodb|1.10.3.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|1.4.1.RELEASE|直接依赖|maven|
|ognl:ognl|3.0.8|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.0.7.Final|间接依赖|maven|
|net.minidev:accessors-smart|1.2|间接依赖|maven|
|org.springframework:spring-context|5.0.4.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.1.2.RELEASE|间接依赖|maven|
|org.unbescape:unbescape|1.1.6.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|1.3.6.RELEASE|直接依赖|maven|
|org.springframework:spring-messaging|4.3.4.RELEASE|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.0.14.Final|间接依赖|maven|
|org.mongodb:mongodb-driver-sync|4.8.0|间接依赖|maven|
|org.springframework.data:spring-data-jpa|2.0.5.RELEASE|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.85.Final|间接依赖|maven|
|org.springframework:spring-beans|4.3.4.RELEASE|间接依赖|maven|
|org.skyscreamer:jsonassert|1.5.0|间接依赖|maven|
|junit:junit|4.13.2|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.8|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|1.5.4.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|1.5.9.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-jpa|1.5.6.RELEASE|直接依赖|maven|
|org.springframework:spring-expression|4.3.8.RELEASE|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-http|1.1.0|间接依赖|maven|
|org.jolokia:jolokia-core|1.3.7|间接依赖|maven|
|org.apache.lucene:lucene-grouping|7.4.0|间接依赖|maven|
|org.apache.commons:commons-pool2|2.4.2|间接依赖|maven|
|org.aspectj:aspectjweaver|1.9.9.1|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.31.Final|间接依赖|maven|
|org.apache.tomcat:tomcat-juli|8.5.16|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|1.3.6.RELEASE|间接依赖|maven|
|org.webjars.bowergithub.twbs:bootstrap|5.2.3|直接依赖|maven|
|org.yaml:snakeyaml|1.33|间接依赖|maven|
|org.unbescape:unbescape|1.1.5.RELEASE|间接依赖|maven|
|org.apache.tomcat:tomcat-jdbc|8.5.16|间接依赖|maven|
|org.junit.vintage:junit-vintage-engine|5.9.1|直接依赖|maven|
|org.springframework.boot:spring-boot-starter|1.5.4.RELEASE|间接依赖|maven|
|net.spy:spymemcached|2.12.2|直接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|org.springframework.retry:spring-retry|1.2.2.RELEASE|间接依赖|maven|
|org.springframework:spring-web|4.3.9.RELEASE|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|8.5.28|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-elasticsearch|2.1.0.RELEASE|直接依赖|maven|
|org.apache.tomcat:tomcat-juli|8.5.6|间接依赖|maven|
|org.hamcrest:hamcrest|2.2|间接依赖|maven|
|de.codecentric:spring-boot-admin-starter-client|2.1.0|直接依赖|maven|
|org.thymeleaf:thymeleaf|3.1.0.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|1.4.1.RELEASE|间接依赖|maven|
|org.attoparser:attoparser|2.0.5.RELEASE|间接依赖|maven|
|nz.net.ultraq.thymeleaf:thymeleaf-expression-processor|1.1.3|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|1.5.9.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.1.0.RELEASE|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|1.3.6.RELEASE|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|8.5.6|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.1.0.RELEASE|间接依赖|maven|
|com.jayway.jsonpath:json-path|2.7.0|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|8.5.6|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.14.1|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.12|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|3.0.0|间接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|1.5.3.RELEASE|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.85.Final|间接依赖|maven|
|org.mongodb:bson|3.8.2|间接依赖|maven|
|io.springfox:springfox-core|2.9.2|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.11.2|间接依赖|maven|
|org.springframework.boot:spring-boot-devtools|1.4.2.RELEASE|直接依赖|maven|
|org.springframework:spring-web|5.1.5.RELEASE|间接依赖|maven|
|org.apache.tomcat:tomcat-annotations-api|8.5.23|间接依赖|maven|
|org.springframework:spring-beans|5.0.8.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.8.10|间接依赖|maven|
|org.codehaus.groovy:groovy|2.4.10|间接依赖|maven|
|io.netty:netty-codec|4.1.29.Final|间接依赖|maven|
|nz.net.ultraq.thymeleaf:thymeleaf-expression-processor|3.1.0|间接依赖|maven|
|org.mongodb:mongodb-driver-core|3.4.2|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.0.0.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.8.3|间接依赖|maven|
|org.springframework:spring-web|4.3.8.RELEASE|间接依赖|maven|
|de.codecentric:spring-boot-admin-client|2.1.0|间接依赖|maven|
|org.springframework.boot:spring-boot-devtools|2.1.0.RELEASE|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|8.5.14|间接依赖|maven|
|com.google.guava:guava|18.0|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.1.4.RELEASE|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-params|5.9.1|间接依赖|maven|
|com.fasterxml:classmate|1.4.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-jpa|3.0.0|直接依赖|maven|
|io.netty:netty-codec-socks|4.1.29.Final|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.3.0.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.1.2.RELEASE|间接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.85.Final|间接依赖|maven|
|org.springframework.boot:spring-boot|1.5.4.RELEASE|间接依赖|maven|
|org.springframework.cloud:spring-cloud-commons|1.3.1.RELEASE|间接依赖|maven|
|io.netty:netty-resolver|4.1.85.Final|间接依赖|maven|
|org.springframework:spring-expression|4.3.9.RELEASE|间接依赖|maven|
|org.mongodb:bson-record-codec|4.8.0|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.1.3.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.1.3.RELEASE|间接依赖|maven|
|org.springframework.session:spring-session|1.3.1.RELEASE|间接依赖|maven|
|commons-codec:commons-codec|1.10|间接依赖|maven|
|org.springframework.boot:spring-boot|2.1.2.RELEASE|间接依赖|maven|
|nz.net.ultraq.thymeleaf:thymeleaf-layout-dialect|2.3.0|直接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.2|间接依赖|maven|
|org.springframework:spring-messaging|6.0.2|间接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-starter|2.0.0|直接依赖|maven|
|org.springframework.plugin:spring-plugin-metadata|1.2.0.RELEASE|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|8.5.5|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.19|间接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-autoconfigure|2.0.0|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|8.5.16|间接依赖|maven|
|org.elasticsearch:jna|4.5.1|间接依赖|maven|
|com.fasterxml:classmate|1.1.0|间接依赖|maven|
|org.hibernate:hibernate-core|5.2.14.Final|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|8.5.23|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.31.Final|间接依赖|maven|
|xml-apis:xml-apis|1.4.01|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.0.13.Final|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.85.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|1.4.2.RELEASE|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.12|间接依赖|maven|
|org.springframework.boot:spring-boot|1.4.2.RELEASE|间接依赖|maven|
|org.springframework.data:spring-data-commons|1.13.3.RELEASE|间接依赖|maven|
|org.springframework:spring-web|6.0.2|间接依赖|maven|
|javax.transaction:javax.transaction-api|1.3|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|8.5.5|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.14.1|间接依赖|maven|
|io.netty:netty-common|4.1.85.Final|间接依赖|maven|
|org.mybatis:mybatis-spring|2.0.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.8.10|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|3.0.2|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.11.1|间接依赖|maven|
|org.mybatis:mybatis|3.5.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.1.0.RELEASE|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-test|2.1.0.RELEASE|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.9.7|间接依赖|maven|
|org.springframework:spring-context|5.1.2.RELEASE|间接依赖|maven|
|org.javassist:javassist|3.23.1-GA|间接依赖|maven|
|com.jayway.jsonpath:json-path|2.4.0|间接依赖|maven|
|io.netty:netty-buffer|4.1.85.Final|间接依赖|maven|
|org.yaml:snakeyaml|1.23|间接依赖|maven|
|org.springframework:spring-web|5.1.2.RELEASE|间接依赖|maven|
|com.rabbitmq:amqp-client|5.4.3|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.16|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-mongodb|1.5.3.RELEASE|直接依赖|maven|
|org.apiguardian:apiguardian-api|1.1.2|间接依赖|maven|
|org.springframework:spring-tx|4.3.10.RELEASE|间接依赖|maven|
|org.mongodb:mongodb-driver-core|3.8.2|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|8.5.15|间接依赖|maven|
|org.apache.lucene:lucene-misc|7.4.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|1.5.9.RELEASE|直接依赖|maven|
|org.springframework:spring-beans|5.1.4.RELEASE|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.21|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.11.1|间接依赖|maven|
|org.springframework:spring-jdbc|5.1.5.RELEASE|间接依赖|maven|
|com.h2database:h2|1.4.199|直接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.0.4.RELEASE|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|2.0.0.RELEASE|间接依赖|maven|
|org.springframework:spring-context|4.3.3.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.8.4|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|org.skyscreamer:jsonassert|1.5.1|间接依赖|maven|
|org.springframework.boot:spring-boot|1.4.1.RELEASE|间接依赖|maven|
|org.springframework:spring-webmvc|5.1.5.RELEASE|间接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|org.springframework:spring-webmvc|4.2.7.RELEASE|间接依赖|maven|
|io.netty:netty-codec-http|4.1.31.Final|间接依赖|maven|
|ch.qos.logback:logback-core|1.1.7|间接依赖|maven|
|org.dom4j:dom4j|2.1.1|间接依赖|maven|
|org.elasticsearch:elasticsearch-core|6.4.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.1.2.RELEASE|间接依赖|maven|
|org.codehaus.groovy:groovy|2.5.3|间接依赖|maven|
|org.jolokia:jolokia-core|1.6.0|间接依赖|maven|
|net.bytebuddy:byte-buddy-agent|1.9.3|间接依赖|maven|
|io.netty:netty-buffer|4.1.29.Final|间接依赖|maven|
|io.netty:netty-handler|4.1.31.Final|间接依赖|maven|
|org.thymeleaf:thymeleaf|3.0.9.RELEASE|间接依赖|maven|
|io.projectreactor.netty:reactor-netty|0.8.4.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.9.4|间接依赖|maven|
|org.mybatis:mybatis|3.5.11|间接依赖|maven|
|com.baomidou:mybatis-plus-annotation|3.1.1|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|1.5.6.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.14.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-thymeleaf|1.5.6.RELEASE|直接依赖|maven|
|org.elasticsearch.plugin:percolator-client|6.4.2|间接依赖|maven|
|com.carrotsearch:hppc|0.7.1|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.85.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-mongodb|2.1.0.RELEASE|直接依赖|maven|
|com.baomidou:mybatis-plus-boot-starter|3.1.1|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.14.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.0.0.RELEASE|直接依赖|maven|
|org.springframework:spring-core|4.3.8.RELEASE|间接依赖|maven|
|com.tdunning:t-digest|3.2|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|10.1.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-actuator|2.1.0.RELEASE|直接依赖|maven|
|org.springframework:spring-aop|5.0.4.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-webflux|2.1.2.RELEASE|直接依赖|maven|
|org.springframework.data:spring-data-keyvalue|1.1.10.RELEASE|间接依赖|maven|
|org.apache.lucene:lucene-queries|7.4.0|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|8.5.15|间接依赖|maven|
|org.springframework:spring-jdbc|4.3.4.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.8.4|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.31.Final|间接依赖|maven|
|io.netty:netty-transport|4.1.85.Final|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|8.5.6|间接依赖|maven|
|javax.transaction:javax.transaction-api|1.2|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.9.8|间接依赖|maven|
|com.zaxxer:HikariCP|2.7.8|间接依赖|maven|
|org.springframework.boot:spring-boot|3.0.0|间接依赖|maven|
|org.hibernate.common:hibernate-commons-annotations|5.0.1.Final|间接依赖|maven|
|com.mysql:mysql-connector-j|8.0.31|直接依赖|maven|
|org.springframework:spring-aop|5.0.8.RELEASE|间接依赖|maven|
|org.ow2.asm:asm|9.1|间接依赖|maven|
|com.github.spullara.mustache.java:compiler|0.9.3|间接依赖|maven|
|org.springframework:spring-jdbc|5.0.4.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|3.0.0|间接依赖|maven|
|org.springframework.amqp:spring-rabbit|3.0.0|间接依赖|maven|
|io.micrometer:micrometer-observation|1.10.2|间接依赖|maven|
|org.xmlunit:xmlunit-core|2.6.2|间接依赖|maven|
|org.hibernate.orm:hibernate-core|6.1.5.Final|间接依赖|maven|
|commons-io:commons-io|2.4|间接依赖|maven|
|org.apache.lucene:lucene-backward-codecs|7.4.0|间接依赖|maven|
|org.springframework.boot:spring-boot-test-autoconfigure|3.0.0|间接依赖|maven|
|org.springframework:spring-beans|5.1.6.RELEASE|间接依赖|maven|
|org.antlr:antlr4-runtime|4.10.1|间接依赖|maven|
|org.springframework:spring-context|5.1.5.RELEASE|间接依赖|maven|
|io.springfox:springfox-spring-web|2.9.2|间接依赖|maven|
|org.assertj:assertj-core|3.23.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.8.9|间接依赖|maven|
|org.springframework:spring-oxm|6.0.2|间接依赖|maven|
|org.junit.jupiter:junit-jupiter|5.9.1|间接依赖|maven|
|org.springframework:spring-expression|5.0.8.RELEASE|间接依赖|maven|
|org.springframework.security:spring-security-crypto|4.2.3.RELEASE|间接依赖|maven|
|io.netty:netty-resolver|4.1.29.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.1.0.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.1.2.RELEASE|间接依赖|maven|
|org.springframework:spring-core|5.0.8.RELEASE|间接依赖|maven|
|org.springframework:spring-webmvc|6.0.2|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.12|间接依赖|maven|
|org.springframework:spring-context|5.1.6.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-mail|2.1.0.RELEASE|直接依赖|maven|
|org.mongodb:mongodb-driver-core|4.8.0|间接依赖|maven|
|org.springframework:spring-web|4.2.7.RELEASE|间接依赖|maven|
|org.springframework:spring-webflux|5.1.4.RELEASE|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|redis.clients:jedis|2.8.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|1.5.3.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.8.0|间接依赖|maven|
|org.springframework:spring-oxm|4.2.9.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.9.4|间接依赖|maven|
|commons-configuration:commons-configuration|1.8|间接依赖|maven|
|org.springframework:spring-aop|5.1.5.RELEASE|间接依赖|maven|
|org.mybatis:mybatis-spring|3.0.0|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.85.Final|间接依赖|maven|
|io.lettuce:lettuce-core|6.2.1.RELEASE|间接依赖|maven|
|io.netty:netty-common|4.1.29.Final|间接依赖|maven|
|org.springframework:spring-beans|4.3.10.RELEASE|间接依赖|maven|
|org.springframework:spring-context|5.0.8.RELEASE|间接依赖|maven|
|org.elasticsearch:elasticsearch|6.4.2|间接依赖|maven|
|org.webjars.bower:jquery|2.0.3|直接依赖|maven|
|org.codehaus.groovy:groovy|2.4.3|间接依赖|maven|
|org.apache.tomcat:tomcat-juli|8.5.15|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.8.8|间接依赖|maven|
|org.springframework.boot:spring-boot|2.0.4.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.0.4.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-devtools|1.3.6.RELEASE|直接依赖|maven|
|org.objenesis:objenesis|3.2|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.8.3|间接依赖|maven|
|org.springframework.boot:spring-boot-devtools|2.1.3.RELEASE|直接依赖|maven|
|io.netty:netty-resolver|4.1.31.Final|间接依赖|maven|
|org.hamcrest:hamcrest-library|1.3|间接依赖|maven|
|net.bytebuddy:byte-buddy-agent|1.12.19|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.9.7|间接依赖|maven|
|org.springframework:spring-context|4.3.8.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-validation|1.3.6.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-reactor-netty|2.1.0.RELEASE|间接依赖|maven|
|org.springframework:spring-beans|5.1.5.RELEASE|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.29.Final|间接依赖|maven|
|org.springframework:spring-aop|5.1.6.RELEASE|间接依赖|maven|
|org.springframework:spring-tx|4.3.13.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-devtools|1.5.4.RELEASE|直接依赖|maven|
|com.fasterxml:classmate|1.3.3|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|1.4.1.RELEASE|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-jpa|2.0.0.RELEASE|直接依赖|maven|
|org.projectlombok:lombok|1.18.6|直接依赖|maven|
|org.springframework:spring-context-support|6.0.2|间接依赖|maven|
|org.springframework:spring-expression|4.3.10.RELEASE|间接依赖|maven|
|org.springframework.session:spring-session-data-redis|3.0.0|直接依赖|maven|
|org.apache.lucene:lucene-sandbox|7.4.0|间接依赖|maven|
|mysql:mysql-connector-java|8.0.15|直接依赖|maven|
|org.javassist:javassist|3.29.0-GA|间接依赖|maven|
|org.springframework:spring-core|5.0.4.RELEASE|间接依赖|maven|
|org.springframework:spring-expression|5.1.6.RELEASE|间接依赖|maven|
|org.hibernate.common:hibernate-commons-annotations|5.0.4.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.0.0.RELEASE|间接依赖|maven|
|org.springframework:spring-messaging|5.1.2.RELEASE|间接依赖|maven|
|mysql:mysql-connector-java|5.1.43|直接依赖|maven|
|io.netty:netty-codec-dns|4.1.85.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-amqp|3.0.0|直接依赖|maven|
|org.yaml:snakeyaml|1.19|间接依赖|maven|
|io.projectreactor.addons:reactor-extra|3.2.0.RELEASE|间接依赖|maven|
|org.springframework:spring-beans|5.1.2.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|3.0.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.14.1|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator|1.5.9.RELEASE|间接依赖|maven|
|org.apache.commons:commons-pool2|2.11.1|直接依赖|maven|
|org.springframework:spring-aop|4.3.4.RELEASE|间接依赖|maven|
|org.springframework:spring-orm|5.1.2.RELEASE|间接依赖|maven|
|org.mybatis:mybatis-spring|2.0.0|间接依赖|maven|
|io.lettuce:lettuce-core|5.1.2.RELEASE|间接依赖|maven|
|org.springframework:spring-context|4.3.4.RELEASE|间接依赖|maven|
|io.netty:netty-transport|4.1.29.Final|间接依赖|maven|
|org.springframework:spring-jdbc|6.0.2|间接依赖|maven|
|io.netty:netty-buffer|4.1.31.Final|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|8.5.14|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|1.5.4.RELEASE|间接依赖|maven|
|org.javassist:javassist|3.22.0-GA|间接依赖|maven|
|org.projectlombok:lombok|1.16.16|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|2.1.3.RELEASE|间接依赖|maven|
|org.springframework:spring-orm|5.1.5.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-jpa|1.5.4.RELEASE|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|8.5.23|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.1.4.RELEASE|间接依赖|maven|
|io.springfox:springfox-swagger-ui|2.9.2|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-jpa|2.1.0.RELEASE|直接依赖|maven|
|org.apache.lucene:lucene-spatial3d|7.4.0|间接依赖|maven|
|org.thymeleaf:thymeleaf-spring6|3.1.0.RELEASE|间接依赖|maven|
|org.springframework:spring-webmvc|5.1.2.RELEASE|间接依赖|maven|
|org.springframework:spring-web|4.3.4.RELEASE|间接依赖|maven|
|org.springframework:spring-orm|4.3.9.RELEASE|间接依赖|maven|
|org.thymeleaf:thymeleaf-spring5|3.0.11.RELEASE|间接依赖|maven|
|org.junit.platform:junit-platform-engine|1.9.1|间接依赖|maven|
|org.springframework:spring-expression|5.1.5.RELEASE|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.10.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-reactor-netty|2.1.2.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.9.4|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|3.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot-devtools|1.5.6.RELEASE|直接依赖|maven|
|org.thymeleaf:thymeleaf-spring4|2.1.6.RELEASE|间接依赖|maven|
|org.springframework:spring-jdbc|4.3.3.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|1.5.6.RELEASE|直接依赖|maven|
|org.springframework:spring-jcl|6.0.2|间接依赖|maven|
|javax.activation:activation|1.1|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.11.2|间接依赖|maven|
|io.netty:netty-handler|4.1.29.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|1.4.1.RELEASE|间接依赖|maven|
|org.mapstruct:mapstruct|1.2.0.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-validation|3.0.0|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-thymeleaf|2.0.0.RELEASE|直接依赖|maven|
|org.springframework:spring-tx|5.1.6.RELEASE|间接依赖|maven|
|org.apache.lucene:lucene-join|7.4.0|间接依赖|maven|
|org.aspectj:aspectjweaver|1.9.2|间接依赖|maven|
|mysql:mysql-connector-java|5.1.44|直接依赖|maven|
|org.javassist:javassist|3.21.0-GA|间接依赖|maven|
|org.springframework.boot:spring-boot|2.0.0.RELEASE|间接依赖|maven|
|org.csource:fastdfs-client-java|1.27-SNAPSHOT|直接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-autoconfigure|3.0.0|间接依赖|maven|
|org.apache.tomcat:tomcat-jdbc|8.5.5|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|3.0.0|间接依赖|maven|
|mysql:mysql-connector-java|5.1.39|直接依赖|maven|
|org.springframework.data:spring-data-jpa|1.11.4.RELEASE|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|10.1.1|间接依赖|maven|
|org.eclipse.angus:angus-activation|1.0.0|间接依赖|maven|
|org.apache.commons:commons-pool2|2.6.0|直接依赖|maven|
|org.springframework:spring-tx|6.0.2|间接依赖|maven|
|org.apache.lucene:lucene-memory|7.4.0|间接依赖|maven|
|org.springframework:spring-core|4.3.10.RELEASE|间接依赖|maven|
|junit:junit|4.12|间接依赖|maven|
|io.springfox:springfox-swagger2|2.9.2|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.0.0.RELEASE|间接依赖|maven|
|com.baomidou:mybatis-plus-extension|3.1.1|间接依赖|maven|
|joda-time:joda-time|2.10.1|间接依赖|maven|
|io.reactivex:rxjava|1.2.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|1.5.6.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.0.0.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|1.5.4.RELEASE|间接依赖|maven|
|org.thymeleaf:thymeleaf|2.1.6.RELEASE|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.3|间接依赖|maven|
|com.netflix.zuul:zuul-core|1.3.0|间接依赖|maven|
|io.swagger:swagger-models|1.5.20|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.3.2.Final|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|8.5.5|间接依赖|maven|
|org.mybatis:mybatis|3.5.1|间接依赖|maven|
|org.webjars.bower:jquery|3.6.2|直接依赖|maven|
|org.apache.lucene:lucene-spatial-extras|7.4.0|间接依赖|maven|
|org.slf4j:log4j-over-slf4j|1.7.21|间接依赖|maven|
|org.junit.platform:junit-platform-commons|1.9.1|间接依赖|maven|
|org.springframework.data:spring-data-jpa|2.1.2.RELEASE|间接依赖|maven|
|org.springframework:spring-test|6.0.2|间接依赖|maven|
|org.springframework:spring-tx|5.0.4.RELEASE|间接依赖|maven|
|org.mockito:mockito-core|2.23.0|间接依赖|maven|
|org.springframework.amqp:spring-rabbit|2.1.0.RELEASE|间接依赖|maven|
|de.codecentric:spring-boot-admin-server-cloud|2.1.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.1.0.RELEASE|间接依赖|maven|
|org.springframework.data:spring-data-redis|2.1.2.RELEASE|间接依赖|maven|
|com.google.guava:guava|20.0|间接依赖|maven|
|com.netflix.archaius:archaius-core|0.7.4|间接依赖|maven|
|org.springframework.data:spring-data-redis|1.7.10.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.0.4.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.6.7|间接依赖|maven|
|io.projectreactor:reactor-core|3.5.0|间接依赖|maven|
|org.javassist:javassist|3.20.0-GA|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.8.4|间接依赖|maven|
|org.springframework.cloud:spring-cloud-netflix-core|1.4.2.RELEASE|间接依赖|maven|
|net.minidev:json-smart|2.4.8|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-smile|2.9.7|间接依赖|maven|
|com.fasterxml:classmate|1.3.4|间接依赖|maven|
|org.springframework.data:spring-data-keyvalue|3.0.0|间接依赖|maven|
|org.synchronoss.cloud:nio-multipart-parser|1.1.0|间接依赖|maven|
|org.glassfish.jaxb:txw2|4.0.1|间接依赖|maven|
|io.springfox:springfox-swagger-common|2.9.2|间接依赖|maven|
|org.elasticsearch.plugin:reindex-client|6.4.2|间接依赖|maven|
|org.springframework.boot:spring-boot-devtools|2.1.2.RELEASE|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.2|间接依赖|maven|
|org.springframework:spring-aop|4.3.10.RELEASE|间接依赖|maven|
|jakarta.transaction:jakarta.transaction-api|2.0.1|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|间接依赖|maven|
|com.baomidou:mybatis-plus-core|3.1.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|1.5.9.RELEASE|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|2.1.1|间接依赖|maven|
|org.springframework.data:spring-data-mongodb|2.1.2.RELEASE|间接依赖|maven|
|org.apache.lucene:lucene-core|7.4.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|2.1.0.RELEASE|间接依赖|maven|
|org.hibernate:hibernate-entitymanager|5.0.12.Final|间接依赖|maven|
|io.micrometer:micrometer-core|1.1.0|间接依赖|maven|
|org.codehaus.groovy:groovy|2.4.13|间接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.85.Final|间接依赖|maven|
|org.springframework.data:spring-data-keyvalue|2.1.2.RELEASE|间接依赖|maven|
|com.zaxxer:HikariCP|5.0.1|间接依赖|maven|
|com.rabbitmq:amqp-client|3.6.5|间接依赖|maven|
|org.hamcrest:hamcrest-core|1.3|间接依赖|maven|
|org.eclipse.angus:jakarta.mail|1.0.0|间接依赖|maven|
|com.github.jsqlparser:jsqlparser|1.2|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.9.8|间接依赖|maven|
|ch.qos.logback:logback-classic|1.1.11|间接依赖|maven|
|org.mongodb:mongodb-driver|3.4.2|间接依赖|maven|
|org.springframework:spring-beans|5.0.4.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-actuator|1.5.9.RELEASE|直接依赖|maven|
|ch.qos.logback:logback-core|1.1.11|间接依赖|maven|
|org.jboss:jandex|2.4.2.Final|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.29.Final|间接依赖|maven|
|io.netty:netty-handler|4.1.85.Final|间接依赖|maven|
|net.minidev:json-smart|2.3|间接依赖|maven|
|org.yaml:snakeyaml|1.16|间接依赖|maven|
|org.springframework.plugin:spring-plugin-core|1.2.0.RELEASE|间接依赖|maven|
|mysql:mysql-connector-java|5.1.40|直接依赖|maven|
|org.attoparser:attoparser|2.0.6.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-test|3.0.0|间接依赖|maven|
|org.elasticsearch:elasticsearch-cli|6.4.2|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|8.0.0.Final|间接依赖|maven|
|org.springframework.boot:spring-boot|1.5.9.RELEASE|间接依赖|maven|
|org.springframework:spring-expression|4.3.4.RELEASE|间接依赖|maven|
|org.springframework:spring-core|6.0.2|间接依赖|maven|
|de.codecentric:spring-boot-admin-server-ui|2.1.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.0.0.RELEASE|直接依赖|maven|
|org.thymeleaf:thymeleaf-spring4|2.1.5.RELEASE|间接依赖|maven|
|io.netty:netty-codec|4.1.85.Final|间接依赖|maven|
|org.springframework:spring-orm|5.0.4.RELEASE|间接依赖|maven|
|mysql:mysql-connector-java|8.0.13|直接依赖|maven|
|org.springframework:spring-aop|4.3.8.RELEASE|间接依赖|maven|
|org.springframework:spring-webmvc|4.3.13.RELEASE|间接依赖|maven|
|org.springframework:spring-aop|6.0.2|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|8.5.28|间接依赖|maven|
|org.synchronoss.cloud:nio-stream-storage|1.1.3|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.1.3.RELEASE|间接依赖|maven|
|org.springframework.amqp:spring-amqp|1.6.5.RELEASE|间接依赖|maven|
|com.googlecode.json-simple:json-simple|1.1.1|间接依赖|maven|
|org.apache.tomcat:tomcat-juli|8.5.5|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|1.5.4.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-mail|3.0.0|直接依赖|maven|
|org.springframework.data:spring-data-commons|3.0.0|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.9.10|间接依赖|maven|
|org.springframework:spring-tx|4.3.3.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.9.7|间接依赖|maven|
|org.springframework.boot:spring-boot-devtools|3.0.0|直接依赖|maven|
|org.springframework:spring-aop|5.1.4.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|1.4.2.RELEASE|间接依赖|maven|
|org.springframework:spring-context-support|4.2.9.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.6.7|间接依赖|maven|
|org.webjars.bower:bootstrap|3.0.3|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.14.1|间接依赖|maven|
|org.mongodb:bson|4.8.0|间接依赖|maven|
|org.thymeleaf.extras:thymeleaf-extras-java8time|3.0.3.RELEASE|间接依赖|maven|
|org.springframework.session:spring-session-data-redis|2.1.1.RELEASE|直接依赖|maven|
|org.jboss:jandex|2.0.0.Final|间接依赖|maven|
|commons-codec:commons-codec|1.11|间接依赖|maven|
|javax.persistence:javax.persistence-api|2.2|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.85.Final|间接依赖|maven|
|org.apache.lucene:lucene-spatial|7.4.0|间接依赖|maven|
|org.springframework:spring-orm|6.0.2|间接依赖|maven|
|org.springframework:spring-web|5.0.4.RELEASE|间接依赖|maven|
|org.slf4j:jul-to-slf4j|2.0.4|间接依赖|maven|
|org.springframework:spring-jdbc|4.3.13.RELEASE|间接依赖|maven|
|com.netflix.servo:servo-core|0.10.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|1.5.6.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-amqp|2.1.0.RELEASE|直接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|4.0.1|间接依赖|maven|
|org.hibernate.javax.persistence:hibernate-jpa-2.1-api|1.0.0.Final|间接依赖|maven|
|org.springframework:spring-jcl|5.0.8.RELEASE|间接依赖|maven|
|org.springframework:spring-core|4.3.4.RELEASE|间接依赖|maven|
|org.springframework:spring-web|4.3.13.RELEASE|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.25|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-core|1.1.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.9.7|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.16|间接依赖|maven|
|ch.qos.logback:logback-core|1.4.5|间接依赖|maven|
|org.yaml:snakeyaml|1.17|间接依赖|maven|
|org.mongodb:bson|3.4.2|间接依赖|maven|
|com.rabbitmq:amqp-client|5.16.0|间接依赖|maven|
|org.springframework:spring-jcl|5.1.2.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-thymeleaf|1.5.3.RELEASE|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.1.0.RELEASE|间接依赖|maven|
|org.springframework:spring-test|5.1.2.RELEASE|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.6|间接依赖|maven|
|org.objenesis:objenesis|2.6|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.9.4|间接依赖|maven|
|org.elasticsearch:elasticsearch-secure-sm|6.4.2|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)