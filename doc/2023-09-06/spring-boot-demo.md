# xkcoding/spring-boot-demo安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699122074122764288.svg)](https://www.murphysec.com/console/report/1699122074068238336/1699122074122764288)

仓库描述：🚀一个用来深入学习并实战 Spring Boot 的项目。

仓库地址：[https://github.com/xkcoding/spring-boot-demo](https://github.com/xkcoding/spring-boot-demo)

| star：30366 | watch：1012 | fork：10413 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-04 11:46:15 | 许可证：MIT |
| 最近检测时间：2023-09-06 02:11:52 | 组件总数：486 | 漏洞总数：271 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|XXL-RPC 代码问题漏洞|反序列化|[MPS-1k9p-hmif](https://www.oscs1024.com/hd/MPS-1k9p-hmif)|CVE-2023-33496|严重|
|多款Cisco产品Apache Commons Collections库任意代码执行漏洞|反序列化|[MPS-2015-6277](https://www.oscs1024.com/hd/MPS-2015-6277)|CVE-2015-6420|高危|
|Apache Commons FileUpload 访问控制错误漏洞|访问控制不当|[MPS-2016-5301](https://www.oscs1024.com/hd/MPS-2016-5301)|CVE-2016-1000031|严重|
|Apache Zookeeper 安全漏洞||[MPS-2017-11297](https://www.oscs1024.com/hd/MPS-2017-11297)|CVE-2017-5637|高危|
|Netty和Play Framework 输入验证错误漏洞|未授权敏感信息泄露|[MPS-2017-11682](https://www.oscs1024.com/hd/MPS-2017-11682)|CVE-2015-2156|高危|
|多款Red Hat产品代码问题漏洞|反序列化|[MPS-2017-12638](https://www.oscs1024.com/hd/MPS-2017-12638)|CVE-2015-7501|严重|
|Apache Groovy 远程代码执行漏洞|反序列化|[MPS-2018-0875](https://www.oscs1024.com/hd/MPS-2018-0875)|CVE-2016-6814|严重|
|Apache POI <3.17 拒绝服务漏洞|不可达退出条件的循环（无限循环）|[MPS-2018-1197](https://www.oscs1024.com/hd/MPS-2018-1197)|CVE-2017-12626|高危|
|Undertow writevBuffer 缓冲区信息泄露漏洞|未授权敏感信息泄露|[MPS-2018-12398](https://www.oscs1024.com/hd/MPS-2018-12398)|CVE-2018-14642|中危|
|FasterXML Jackson < 2.9.8存在拒绝服务漏洞|拒绝服务|[MPS-2018-16099](https://www.oscs1024.com/hd/MPS-2018-16099)|CVE-2018-1000873|中危|
|Elasticsearch Security 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2018-16131](https://www.oscs1024.com/hd/MPS-2018-16131)|CVE-2018-17244|中危|
|Apache Zookeeper 访问控制错误漏洞|授权检查缺失|[MPS-2018-6313](https://www.oscs1024.com/hd/MPS-2018-6313)|CVE-2018-8012|高危|
|Bouncy Castle 不安全加密漏洞|密码算法不安全|[MPS-2018-7057](https://www.oscs1024.com/hd/MPS-2018-7057)|CVE-2018-1000180|高危|
|FasterXML Jackson-databind代码问题漏洞(axis2-transport-jms gadget绕过)|反序列化|[MPS-2019-0023](https://www.oscs1024.com/hd/MPS-2019-0023)|CVE-2018-19360|严重|
|FasterXML Jackson-databind代码问题漏洞(openjpa gadget绕过)|反序列化|[MPS-2019-0024](https://www.oscs1024.com/hd/MPS-2019-0024)|CVE-2018-19361|严重|
|FasterXML Jackson-databind代码问题漏洞(jboss-common-core gadget绕过)|反序列化|[MPS-2019-0025](https://www.oscs1024.com/hd/MPS-2019-0025)|CVE-2018-19362|严重|
|Apache Commons Beanutils 存在不可信数据的反序列化漏洞|反序列化|[MPS-2019-10233](https://www.oscs1024.com/hd/MPS-2019-10233)|CVE-2019-10086|高危|
|FasterXML jackson-databind 反序列化漏洞(HikariCP gadget绕过)|反序列化|[MPS-2019-11529](https://www.oscs1024.com/hd/MPS-2019-11529)|CVE-2019-14540|严重|
|FasterXML jackson-databind 反序列化漏洞(HikariCP gadget绕过)|反序列化|[MPS-2019-11533](https://www.oscs1024.com/hd/MPS-2019-11533)|CVE-2019-16335|严重|
|Netty 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2019-12064](https://www.oscs1024.com/hd/MPS-2019-12064)|CVE-2019-16869|高危|
|Red Hat JBoss Enterprise Application Platform 代码问题漏洞|反序列化|[MPS-2019-12470](https://www.oscs1024.com/hd/MPS-2019-12470)|CVE-2019-10202|严重|
|FasterXML jackson-databind 反序列化漏洞(commons-dbcp gadget绕过)|反序列化|[MPS-2019-12479](https://www.oscs1024.com/hd/MPS-2019-12479)|CVE-2019-16942|严重|
|FasterXML jackson-databind 反序列化漏洞(p6spy gadget绕过)|反序列化|[MPS-2019-12480](https://www.oscs1024.com/hd/MPS-2019-12480)|CVE-2019-16943|严重|
|Red Hat Undertow <2.0.20 日志信息泄露漏洞|日志敏感信息泄露|[MPS-2019-12513](https://www.oscs1024.com/hd/MPS-2019-12513)|CVE-2019-10212|中危|
|FasterXML jackson-databind 反序列化漏洞(ehcache gadget绕过)|反序列化|[MPS-2019-12676](https://www.oscs1024.com/hd/MPS-2019-12676)|CVE-2019-17267|严重|
|Swagger UI @import 跨站脚本漏洞|CSRF|[MPS-2019-13043](https://www.oscs1024.com/hd/MPS-2019-13043)|CVE-2019-17495|中危|
|FasterXML jackson-databind 反序列化漏洞(apache-log4j-extras gadget绕过)|反序列化|[MPS-2019-13103](https://www.oscs1024.com/hd/MPS-2019-13103)|CVE-2019-17531|严重|
|Pivotal Reactor Netty 存在凭证保护不足漏洞|凭证保护不足|[MPS-2019-13428](https://www.oscs1024.com/hd/MPS-2019-13428)|CVE-2019-11284|高危|
|Apache POI <4.1.1 XXE 漏洞|XXE|[MPS-2019-13682](https://www.oscs1024.com/hd/MPS-2019-13682)|CVE-2019-12415|中危|
|Elasticsearch 存在敏感信息泄露漏洞|未授权敏感信息泄露|[MPS-2019-13902](https://www.oscs1024.com/hd/MPS-2019-13902)|CVE-2019-7619|中危|
|​ hibernate-validator  存在跨站脚本（XSS）漏洞|XSS|[MPS-2019-14389](https://www.oscs1024.com/hd/MPS-2019-14389)|CVE-2019-10219|中危|
|jackson-mapper-asl <=1.9.13 XXE 注入漏洞|XXE|[MPS-2019-15048](https://www.oscs1024.com/hd/MPS-2019-15048)|CVE-2019-10172|高危|
|Apache Shiro 远程代码执行漏洞(Shiro-721)|密码学问题|[MPS-2019-15075](https://www.oscs1024.com/hd/MPS-2019-15075)|CVE-2019-12422|高危|
|SnakeYAML <1.26 存在 Billion laughs 漏洞|拒绝服务|[MPS-2019-16129](https://www.oscs1024.com/hd/MPS-2019-16129)|CVE-2017-18640|高危|
|Apache Tomcat 授权问题漏洞|会话固定|[MPS-2019-16906](https://www.oscs1024.com/hd/MPS-2019-16906)|CVE-2019-17563|高危|
|Apache Log4j SocketServer反序列化漏洞|反序列化|[MPS-2019-17271](https://www.oscs1024.com/hd/MPS-2019-17271)|CVE-2019-17571|严重|
|Spring Security OAuth 存在开放重定向漏洞|跨站重定向|[MPS-2019-2272](https://www.oscs1024.com/hd/MPS-2019-2272)|CVE-2019-3778|中危|
|Fastjson <= 1.2.60 版本远程代码执行漏洞|使用外部可控制的输入来选择类或代码（不安全的反射）|[MPS-2019-28847](https://www.oscs1024.com/hd/MPS-2019-28847)||严重|
|Fastjson < 1.2.60 版本拒绝服务漏洞|拒绝服务|[MPS-2019-28848](https://www.oscs1024.com/hd/MPS-2019-28848)||严重|
|Elasticsearch 权限提升漏洞|权限问题|[MPS-2019-2964](https://www.oscs1024.com/hd/MPS-2019-2964)|CVE-2019-7611|高危|
|VMware Spring Security 不安全随机值漏洞|使用不充分的随机数|[MPS-2019-3777](https://www.oscs1024.com/hd/MPS-2019-3777)|CVE-2019-3795|中危|
|Apache Tomcat拒绝服务漏洞|拒绝服务|[MPS-2019-3894](https://www.oscs1024.com/hd/MPS-2019-3894)|CVE-2019-0199|高危|
|Apache Tomcat 操作系统命令注入漏洞|OS命令注入|[MPS-2019-4006](https://www.oscs1024.com/hd/MPS-2019-4006)|CVE-2019-0232|高危|
|Spring Data JPA 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2019-4857](https://www.oscs1024.com/hd/MPS-2019-4857)|CVE-2019-3797|中危|
|FasterXML jackson-databind 反序列化漏洞(mysql gadget绕过)|反序列化|[MPS-2019-5442](https://www.oscs1024.com/hd/MPS-2019-5442)|CVE-2019-12086|高危|
|Apache Zookeeper 授权问题漏洞|授权检查缺失|[MPS-2019-5668](https://www.oscs1024.com/hd/MPS-2019-5668)|CVE-2019-0201|中危|
|Apache Tomcat 跨站脚本漏洞|XSS|[MPS-2019-5944](https://www.oscs1024.com/hd/MPS-2019-5944)|CVE-2019-0221|中危|
|Spring Data JPA 信息泄露漏洞|未授权敏感信息泄露|[MPS-2019-6072](https://www.oscs1024.com/hd/MPS-2019-6072)|CVE-2019-3802|中危|
|Undertow Web <2.0.21 存在信息泄露漏洞|日志敏感信息泄露|[MPS-2019-6626](https://www.oscs1024.com/hd/MPS-2019-6626)|CVE-2019-3888|中危|
|Spring Security OAuth 存在开放重定向漏洞|跨站重定向|[MPS-2019-6639](https://www.oscs1024.com/hd/MPS-2019-6639)|CVE-2019-11269|中危|
|FasterXML jackson-databind 反序列化漏洞(jdom gadget绕过)|反序列化|[MPS-2019-6867](https://www.oscs1024.com/hd/MPS-2019-6867)|CVE-2019-12814|中危|
|Apache Tomcat 资源管理错误漏洞|加锁机制不恰当|[MPS-2019-7027](https://www.oscs1024.com/hd/MPS-2019-7027)|CVE-2019-10072|高危|
|FasterXML jackson-databind 反序列化漏洞(logback-classic gadget绕过)|反序列化|[MPS-2019-7047](https://www.oscs1024.com/hd/MPS-2019-7047)|CVE-2019-12384|中危|
|Undertow <2.0.23.Final 存在信息泄露漏洞|授权检查缺失|[MPS-2019-8631](https://www.oscs1024.com/hd/MPS-2019-8631)|CVE-2019-10184|高危|
|Terracotta Quartz Scheduler <2.3.0 存在XXE漏洞|XXE|[MPS-2019-8669](https://www.oscs1024.com/hd/MPS-2019-8669)|CVE-2019-13990|严重|
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
|Red Hat Undertow <2.0.29.Fina 存在拒绝服务漏洞|拒绝服务|[MPS-2020-1116](https://www.oscs1024.com/hd/MPS-2020-1116)|CVE-2019-14888|高危|
|Apache Shiro <1.6.0 存在身份绕过漏洞|身份验证不当|[MPS-2020-11767](https://www.oscs1024.com/hd/MPS-2020-11767)|CVE-2020-13933|高危|
|FasterXML jackson-databind反序列化漏洞(Anteros-DBCP gadget绕过)|反序列化|[MPS-2020-11987](https://www.oscs1024.com/hd/MPS-2020-11987)|CVE-2020-24616|高危|
|FasterXML jackson-databind 反序列化漏洞(pastdev gadget绕过)|反序列化|[MPS-2020-13151](https://www.oscs1024.com/hd/MPS-2020-13151)|CVE-2020-24750|高危|
|Netty <=4.1.43.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1320](https://www.oscs1024.com/hd/MPS-2020-1320)|CVE-2020-7238|高危|
|Pivotal Spring Framework 反射文件下载 (RFD) 漏洞|路径遍历|[MPS-2020-13322](https://www.oscs1024.com/hd/MPS-2020-13322)|CVE-2020-5421|中危|
|Red Hat Undertow 存在 HTTP 请求走私|HTTP请求走私|[MPS-2020-13469](https://www.oscs1024.com/hd/MPS-2020-13469)|CVE-2020-10687|高危|
|MyBatis <3.5.6 存在反序列化漏洞|反序列化|[MPS-2020-14133](https://www.oscs1024.com/hd/MPS-2020-14133)|CVE-2020-26945|高危|
|Netty <4.1.44.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1526](https://www.oscs1024.com/hd/MPS-2020-1526)|CVE-2019-20444|严重|
|Netty <4.1.44.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1527](https://www.oscs1024.com/hd/MPS-2020-1527)|CVE-2019-20445|严重|
|Apache Tomcat HTTP请求走私漏洞|HTTP请求走私|[MPS-2020-15344](https://www.oscs1024.com/hd/MPS-2020-15344)|CVE-2020-13943|中危|
|Elasticsearch 存在权限管理不恰当漏洞|权限管理不当|[MPS-2020-15777](https://www.oscs1024.com/hd/MPS-2020-15777)|CVE-2020-7020|低危|
|Bouncy Castle 私钥信息泄漏漏洞|通过差异性导致的信息暴露|[MPS-2020-16513](https://www.oscs1024.com/hd/MPS-2020-16513)|CVE-2020-26939|中危|
|hibernate-core <5.4.24.Final 存在 SQL 注入漏洞|SQL注入|[MPS-2020-16768](https://www.oscs1024.com/hd/MPS-2020-16768)|CVE-2020-25638|高危|
|Apache HttpClient URI解析错误漏洞|XSS|[MPS-2020-17341](https://www.oscs1024.com/hd/MPS-2020-17341)|CVE-2020-13956|中危|
|FasterXML jackson-databind 代码问题漏洞|XXE|[MPS-2020-17358](https://www.oscs1024.com/hd/MPS-2020-17358)|CVE-2020-25649|高危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2020-17486](https://www.oscs1024.com/hd/MPS-2020-17486)|CVE-2020-17527|高危|
|Apache Groovy 临时目录信息泄露漏洞|缺省权限不正确|[MPS-2020-17573](https://www.oscs1024.com/hd/MPS-2020-17573)|CVE-2020-17521|中危|
|FasterXML jackson-databind 反序列化漏洞(commons-dbcp2 gadget绕过)|反序列化|[MPS-2020-17696](https://www.oscs1024.com/hd/MPS-2020-17696)|CVE-2020-35490|高危|
|FasterXML jackson-databind 反序列化漏洞(commons-dbcp2 gadget绕过)|反序列化|[MPS-2020-17697](https://www.oscs1024.com/hd/MPS-2020-17697)|CVE-2020-35491|高危|
|XXL-JOB 跨站脚本漏洞|XSS|[MPS-2020-18025](https://www.oscs1024.com/hd/MPS-2020-18025)|CVE-2020-29204|中危|
|FasterXML jackson-databind 反序列化漏洞(glassfish gadget绕过)|反序列化|[MPS-2020-18089](https://www.oscs1024.com/hd/MPS-2020-18089)|CVE-2020-35728|高危|
|FasterXML jackson-databind 反序列化漏洞(xbean-reflect gadget绕过)|反序列化|[MPS-2020-2030](https://www.oscs1024.com/hd/MPS-2020-2030)|CVE-2020-8840|严重|
|CloudBees Jenkins Git Parameter插件跨站脚本漏洞|XSS|[MPS-2020-2269](https://www.oscs1024.com/hd/MPS-2020-2269)|CVE-2020-2112|中危|
|FasterXML jackson-databind 反序列化漏洞(ignite-jta gadget绕过)|反序列化|[MPS-2020-24779](https://www.oscs1024.com/hd/MPS-2020-24779)|CVE-2020-10650|高危|
|Apache Tomcat 权限管理不当漏洞|权限管理不当|[MPS-2020-2841](https://www.oscs1024.com/hd/MPS-2020-2841)|CVE-2020-1938|严重|
|Ureport 代码注入漏洞|SSRF|[MPS-2020-30298](https://www.oscs1024.com/hd/MPS-2020-30298)|CVE-2020-21122|中危|
|Ureport 代码注入漏洞|任意文件上传|[MPS-2020-30301](https://www.oscs1024.com/hd/MPS-2020-30301)|CVE-2020-21125|严重|
|FasterXML jackson-databind 代码问题漏洞|反序列化|[MPS-2020-3040](https://www.oscs1024.com/hd/MPS-2020-3040)|CVE-2020-9546|严重|
|FasterXML jackson-databind 反序列化漏洞(JtaTransactionConfig gadget绕过)|反序列化|[MPS-2020-3041](https://www.oscs1024.com/hd/MPS-2020-3041)|CVE-2020-9547|严重|
|FasterXML jackson-databind反序列化漏洞(anteros-core gadget绕过)|反序列化|[MPS-2020-3042](https://www.oscs1024.com/hd/MPS-2020-3042)|CVE-2020-9548|严重|
|FasterXML jackson-databind 反序列化漏洞(commons-configuration gadget绕过)|反序列化|[MPS-2020-3075](https://www.oscs1024.com/hd/MPS-2020-3075)|CVE-2019-14892|严重|
|FasterXML Jackson-databind反序列化漏洞(xalan2 gadget绕过)|反序列化|[MPS-2020-3094](https://www.oscs1024.com/hd/MPS-2020-3094)|CVE-2019-14893|严重|
|io.projectreactor.netty:reactor-netty 存在凭证泄露漏洞|凭证保护不足|[MPS-2020-3108](https://www.oscs1024.com/hd/MPS-2020-3108)|CVE-2020-5404|中危|
|Pivotal Software Reactor Netty HttpServer 存在分布式拒绝服务攻击漏洞|对异常条件的处理不恰当|[MPS-2020-3109](https://www.oscs1024.com/hd/MPS-2020-3109)|CVE-2020-5403|高危|
|mysql:mysql-connector-java <8.0.27 存在 XXE 漏洞|XXE|[MPS-2020-38350](https://www.oscs1024.com/hd/MPS-2020-38350)|CVE-2021-2471|中危|
|Fastjson <=1.2.68 远程代码执行漏洞|使用外部可控制的输入来选择类或代码（不安全的反射）|[MPS-2020-39708](https://www.oscs1024.com/hd/MPS-2020-39708)||严重|
|Fastjson < 1.2.67远程命令执行漏洞|反序列化|[MPS-2020-40828](https://www.oscs1024.com/hd/MPS-2020-40828)||高危|
|FasterXML jackson-databind反序列化漏洞(aries.transaction.jms gadget绕过)|反序列化|[MPS-2020-4131](https://www.oscs1024.com/hd/MPS-2020-4131)|CVE-2020-10672|高危|
|FasterXML jackson-databind反序列化漏洞(caucho-quercus gadget绕过)|反序列化|[MPS-2020-4132](https://www.oscs1024.com/hd/MPS-2020-4132)|CVE-2020-10673|高危|
|Apache Shiro 授权问题漏洞|使用基本弱点进行的认证绕过|[MPS-2020-4560](https://www.oscs1024.com/hd/MPS-2020-4560)|CVE-2020-1957|严重|
|FasterXML jackson-databind反序列化漏洞(bus-proxy gadget绕过)|反序列化|[MPS-2020-4658](https://www.oscs1024.com/hd/MPS-2020-4658)|CVE-2020-10968|高危|
|FasterXML jackson-databind反序列化漏洞(javax.swing gadget绕过)|反序列化|[MPS-2020-4659](https://www.oscs1024.com/hd/MPS-2020-4659)|CVE-2020-10969|高危|
|FasterXML jackson-databind反序列化漏洞(activemq gadget绕过)|反序列化|[MPS-2020-4754](https://www.oscs1024.com/hd/MPS-2020-4754)|CVE-2020-11111|高危|
|FasterXML jackson-databind反序列化漏洞(commons-proxy gadget绕过)|反序列化|[MPS-2020-4755](https://www.oscs1024.com/hd/MPS-2020-4755)|CVE-2020-11112|高危|
|FasterXML jackson-databind反序列化漏洞(openjpa gadget绕过)|反序列化|[MPS-2020-4756](https://www.oscs1024.com/hd/MPS-2020-4756)|CVE-2020-11113|高危|
|Elasticsearch  API 密钥权限提升漏洞|权限管理不当|[MPS-2020-4780](https://www.oscs1024.com/hd/MPS-2020-4780)|CVE-2020-7009|高危|
|Pivotal Software Reactor Netty HttpServer 存在分布式拒绝服务攻击漏洞|拒绝服务|[MPS-2020-50265](https://www.oscs1024.com/hd/MPS-2020-50265)||中危|
|Netty ZlibDecoders 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2020-5127](https://www.oscs1024.com/hd/MPS-2020-5127)|CVE-2020-11612|高危|
|FasterXML jackson-databind 反序列化漏洞(spring-aop gadget绕过)|反序列化|[MPS-2020-5138](https://www.oscs1024.com/hd/MPS-2020-5138)|CVE-2020-11619|高危|
|FasterXML jackson-databind 反序列化漏洞(commons-jelly gadget绕过)|反序列化|[MPS-2020-5139](https://www.oscs1024.com/hd/MPS-2020-5139)|CVE-2020-11620|高危|
|Undertow 存在服务器信息泄露漏洞|未授权敏感信息泄露|[MPS-2020-6315](https://www.oscs1024.com/hd/MPS-2020-6315)|CVE-2020-1757|高危|
|Apache Log4j2 SmtpAppender证书验证不当漏洞|证书验证不恰当|[MPS-2020-6684](https://www.oscs1024.com/hd/MPS-2020-6684)|CVE-2020-9488|低危|
|Red Hat Undertow < 2.0.30 存在信息泄露漏洞|授权机制不恰当|[MPS-2020-6749](https://www.oscs1024.com/hd/MPS-2020-6749)|CVE-2020-1745|严重|
|dom4j SaxReader函数存在 XXE 漏洞|XXE|[MPS-2020-6967](https://www.oscs1024.com/hd/MPS-2020-6967)|CVE-2020-10683|严重|
|hibernate-validator 存在输入验证错误漏洞|代码注入|[MPS-2020-7077](https://www.oscs1024.com/hd/MPS-2020-7077)|CVE-2020-10693|中危|
|Spring Security Crypto 弱加密漏洞|使用不充分的随机数|[MPS-2020-7449](https://www.oscs1024.com/hd/MPS-2020-7449)|CVE-2020-5408|中危|
|Apache Tomcat 远程代码执行漏洞|反序列化|[MPS-2020-7626](https://www.oscs1024.com/hd/MPS-2020-7626)|CVE-2020-9484|高危|
|Red Hat Undertow 存在 HTTP 请求走私的攻击|HTTP请求走私|[MPS-2020-7845](https://www.oscs1024.com/hd/MPS-2020-7845)|CVE-2020-10719|中危|
|Elasticsearch 权限管理不当漏洞|权限管理不当|[MPS-2020-8144](https://www.oscs1024.com/hd/MPS-2020-8144)|CVE-2020-7014|高危|
|Red Hat Undertow 缓冲区错误导致拒绝服务 (DoS) 漏洞|不加限制或调节的资源分配|[MPS-2020-8643](https://www.oscs1024.com/hd/MPS-2020-8643)|CVE-2020-10705|高危|
|FasterXML jackson-databind反序列化漏洞(oracle-aqjms gadget绕过)|反序列化|[MPS-2020-8801](https://www.oscs1024.com/hd/MPS-2020-8801)|CVE-2020-14061|高危|
|FasterXML jackson-databind反序列化漏洞(xalan2 gadget绕过)|反序列化|[MPS-2020-8802](https://www.oscs1024.com/hd/MPS-2020-8802)|CVE-2020-14062|高危|
|FasterXML jackson-databind反序列化漏洞(apache drill gadget绕过)|反序列化|[MPS-2020-8803](https://www.oscs1024.com/hd/MPS-2020-8803)|CVE-2020-14060|高危|
|FasterXML jackson-databind代码问题漏洞(jsecurity gadget绕过)|反序列化|[MPS-2020-8911](https://www.oscs1024.com/hd/MPS-2020-8911)|CVE-2020-14195|高危|
|Apache Shiro 存在身份验证绕过漏洞|身份验证不当|[MPS-2020-9344](https://www.oscs1024.com/hd/MPS-2020-9344)|CVE-2020-11989|严重|
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
|Apache XMLBeans <3.0.0 XXE 漏洞|XML实体扩展|[MPS-2021-0600](https://www.oscs1024.com/hd/MPS-2021-0600)|CVE-2021-23926|严重|
|Apache Tomcat 授权问题漏洞|身份验证不当|[MPS-2021-10264](https://www.oscs1024.com/hd/MPS-2021-10264)|CVE-2021-30640|中危|
|Apache Shiro 访问控制错误漏洞|身份验证不当|[MPS-2021-1064](https://www.oscs1024.com/hd/MPS-2021-1064)|CVE-2020-17523|严重|
|Elasticsearch 资源管理错误漏洞|未经控制的递归|[MPS-2021-11043](https://www.oscs1024.com/hd/MPS-2021-11043)|CVE-2021-22144|中危|
|Elasticsearch 日志信息泄露漏洞|日志敏感信息泄露|[MPS-2021-1485](https://www.oscs1024.com/hd/MPS-2021-1485)|CVE-2020-7021|中危|
|Netty <4.1.59.Final 存在不安全的临时文件漏洞||[MPS-2021-1580](https://www.oscs1024.com/hd/MPS-2021-1580)|CVE-2021-21290|中危|
|FasterXML jackson-databind 反序列化漏洞(javax.swing gadget绕过)|反序列化|[MPS-2021-1625](https://www.oscs1024.com/hd/MPS-2021-1625)|CVE-2021-20190|高危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-1722](https://www.oscs1024.com/hd/MPS-2021-1722)|CVE-2021-24122|中危|
|Red Hat Undertow 存在拒绝服务漏洞|拒绝服务|[MPS-2021-1850](https://www.oscs1024.com/hd/MPS-2021-1850)|CVE-2020-27782|高危|
|Spring Framework <5.3.14 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18854](https://www.oscs1024.com/hd/MPS-2021-18854)|CVE-2021-22060|中危|
|Pivotal Spring Framework 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18890](https://www.oscs1024.com/hd/MPS-2021-18890)|CVE-2021-22096|中危|
|Spring AMQP 安全漏洞|反序列化|[MPS-2021-18891](https://www.oscs1024.com/hd/MPS-2021-18891)|CVE-2021-22097|中危|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|FasterXML jackson-dataformat-cbor 内存耗尽漏洞|不加限制或调节的资源分配|[MPS-2021-1998](https://www.oscs1024.com/hd/MPS-2021-1998)|CVE-2020-28491|高危|
|VMware Spring Security 权限许可和访问控制问题漏洞|权限、特权和访问控制|[MPS-2021-2094](https://www.oscs1024.com/hd/MPS-2021-2094)|CVE-2021-22112|高危|
|Apache Tomcat 信息泄露漏洞|HTTP请求走私|[MPS-2021-2309](https://www.oscs1024.com/hd/MPS-2021-2309)|CVE-2021-25122|高危|
|io.netty:netty-codec-http2 <4.1.60.Final 存在 http 请求走私漏洞|HTTP请求走私|[MPS-2021-2435](https://www.oscs1024.com/hd/MPS-2021-2435)|CVE-2021-21295|中危|
|Apache Tomcat 远程代码执行漏洞|代码注入|[MPS-2021-2466](https://www.oscs1024.com/hd/MPS-2021-2466)|CVE-2021-25329|高危|
|undertow HTTP2SourceChannel 存在拒绝服务漏洞|竞争条件|[MPS-2021-27073](https://www.oscs1024.com/hd/MPS-2021-27073)|CVE-2021-3597|中危|
|Undertow  存在拒绝服务漏洞|拒绝服务|[MPS-2021-27319](https://www.oscs1024.com/hd/MPS-2021-27319)|CVE-2021-3629|中危|
|Undertow 存在拒绝服务漏洞（WebSocket PONG 缓冲区泄漏）|拒绝服务|[MPS-2021-27895](https://www.oscs1024.com/hd/MPS-2021-27895)|CVE-2021-3690|高危|
|Netty Bzip2Decoder 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28116](https://www.oscs1024.com/hd/MPS-2021-28116)|CVE-2021-37136|高危|
|Netty 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28117](https://www.oscs1024.com/hd/MPS-2021-28117)|CVE-2021-37137|高危|
|Apache Tomcat 拒绝服务漏洞|拒绝服务|[MPS-2021-31848](https://www.oscs1024.com/hd/MPS-2021-31848)|CVE-2021-41079|高危|
|Apache Shiro 存在身份验证绕过|身份验证不当|[MPS-2021-32074](https://www.oscs1024.com/hd/MPS-2021-32074)|CVE-2021-41303|严重|
|io.undertow:undertow-core < 2.2.15.Final 存在拒绝服务漏洞|拒绝服务|[MPS-2021-32839](https://www.oscs1024.com/hd/MPS-2021-32839)|CVE-2021-3859|高危|
|Quality Open Software logback JNDI注入漏洞|反序列化|[MPS-2021-33911](https://www.oscs1024.com/hd/MPS-2021-33911)|CVE-2021-42550|中危|
|thymeleaf-spring5 <3.0.13 存在命令注入漏洞|代码注入|[MPS-2021-35280](https://www.oscs1024.com/hd/MPS-2021-35280)|CVE-2021-43466|严重|
| io.netty:netty-codec-http2 <4.1.61.Final 存在 http 请求走私漏洞|HTTP请求走私|[MPS-2021-3565](https://www.oscs1024.com/hd/MPS-2021-3565)|CVE-2021-21409|中危|
|Oracle MySQL 的 MySQL Connectors 存在授权不当漏洞|授权机制不恰当|[MPS-2021-36587](https://www.oscs1024.com/hd/MPS-2021-36587)|CVE-2022-21363|中危|
|Netty <4.1.71.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2021-36922](https://www.oscs1024.com/hd/MPS-2021-36922)|CVE-2021-43797|中危|
|Apache Tomcat 条件竞争漏洞|竞争条件|[MPS-2021-37218](https://www.oscs1024.com/hd/MPS-2021-37218)|CVE-2021-43980|低危|
|Apache Log4j JMSAppender反序列化漏洞||[MPS-2021-38359](https://www.oscs1024.com/hd/MPS-2021-38359)|CVE-2021-4104|高危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|Elasticsearch 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-6747](https://www.oscs1024.com/hd/MPS-2021-6747)|CVE-2021-22137|中危|
|Elasticsearch 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-6749](https://www.oscs1024.com/hd/MPS-2021-6749)|CVE-2021-22135|中危|
|Bouncy Castle 私钥信息泄露漏洞|竞争条件|[MPS-2021-7064](https://www.oscs1024.com/hd/MPS-2021-7064)|CVE-2020-15522|中危|
|Spring Framework权限许可和访问控制问题漏洞|权限管理不当|[MPS-2021-7485](https://www.oscs1024.com/hd/MPS-2021-7485)|CVE-2021-22118|高危|
|Apache Dubbo 泛化调用远程代码执行漏洞|反序列化|[MPS-2021-7664](https://www.oscs1024.com/hd/MPS-2021-7664)|CVE-2021-30179|严重|
|Jakarta Expression Language <=3.0.3 存在输入验证错误漏洞|表达式语言注入|[MPS-2021-7671](https://www.oscs1024.com/hd/MPS-2021-7671)|CVE-2021-28170|中危|
|Apache Tomcat 环境问题漏洞|HTTP请求走私|[MPS-2021-9711](https://www.oscs1024.com/hd/MPS-2021-9711)|CVE-2021-33037|中危|
|Red Hat XNIO 资源错误分配漏洞|不加限制或调节的资源分配|[MPS-2022-0191](https://www.oscs1024.com/hd/MPS-2022-0191)|CVE-2022-0084|高危|
|Hutool 存在中间人劫持漏洞|证书验证不恰当|[MPS-2022-1000](https://www.oscs1024.com/hd/MPS-2022-1000)|CVE-2022-22885|中危|
|Vmware Spring Framework 安全漏洞|不加限制或调节的资源分配|[MPS-2022-1080](https://www.oscs1024.com/hd/MPS-2022-1080)|CVE-2022-22950|中危|
|Pivotal Spring Framework 安全限制绕过漏洞|大小写敏感处理不恰当|[MPS-2022-1098](https://www.oscs1024.com/hd/MPS-2022-1098)|CVE-2022-22968|中危|
|Pivotal Spring Security OAuth 存在拒绝服务漏洞|拒绝服务|[MPS-2022-1099](https://www.oscs1024.com/hd/MPS-2022-1099)|CVE-2022-22969|中危|
|Pivotal Spring Framework 拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1100](https://www.oscs1024.com/hd/MPS-2022-1100)|CVE-2022-22971|中危|
|Spring Framework spring-beans 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1101](https://www.oscs1024.com/hd/MPS-2022-1101)|CVE-2022-22970|中危|
|VMware Spring Security 授权问题漏洞|授权检查错误|[MPS-2022-1108](https://www.oscs1024.com/hd/MPS-2022-1108)|CVE-2022-22978|严重|
|Spring Data MongoDB SpEL 表达式注入漏洞|表达式语言注入|[MPS-2022-1110](https://www.oscs1024.com/hd/MPS-2022-1110)|CVE-2022-22980|高危|
|Fastjson < 1.2.83 任意代码执行漏洞|反序列化|[MPS-2022-11320](https://www.oscs1024.com/hd/MPS-2022-11320)|CVE-2022-25845|高危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|org.apache.shiro:shiro-web 存在路径遍历漏洞|路径遍历|[MPS-2022-11870](https://www.oscs1024.com/hd/MPS-2022-11870)||中危|
|Pivotal Spring Framework CSRF 令牌泄露漏洞|通过时间差异性导致的信息暴露|[MPS-2022-11893](https://www.oscs1024.com/hd/MPS-2022-11893)||低危|
|io.netty:netty-codec-http <4.1.53.Final 存在拒绝服务漏洞|拒绝服务|[MPS-2022-12064](https://www.oscs1024.com/hd/MPS-2022-12064)||中危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|Logback SSL证书校验不当漏洞|中间人攻击|[MPS-2022-12411](https://www.oscs1024.com/hd/MPS-2022-12411)||中危|
|com.fasterxml.jackson.core:jackson-databind 存在反序列化漏洞|反序列化|[MPS-2022-12433](https://www.oscs1024.com/hd/MPS-2022-12433)||高危|
|org.freemarker:freemarker <2.3.30 存在代码注入漏洞|代码注入|[MPS-2022-12438](https://www.oscs1024.com/hd/MPS-2022-12438)||高危|
|io.undertow:undertow-servlet 存在空指针解引用漏洞|空指针取消引用|[MPS-2022-12530](https://www.oscs1024.com/hd/MPS-2022-12530)||中危|
|Apache Commons Collections 远程代码执行漏洞|反序列化|[MPS-2022-12767](https://www.oscs1024.com/hd/MPS-2022-12767)||高危|
|Apache Log4j JDBCAppender SQL注入漏洞|SQL注入|[MPS-2022-1444](https://www.oscs1024.com/hd/MPS-2022-1444)|CVE-2022-23305|严重|
|Apache Log4j Chainsaw反序列化漏洞|反序列化|[MPS-2022-1445](https://www.oscs1024.com/hd/MPS-2022-1445)|CVE-2022-23307|高危|
|Apache Log4j 反序列化漏洞|反序列化|[MPS-2022-1446](https://www.oscs1024.com/hd/MPS-2022-1446)|CVE-2022-23302|高危|
|Apache Shiro 权限绕过漏洞|授权检查错误|[MPS-2022-17602](https://www.oscs1024.com/hd/MPS-2022-17602)|CVE-2022-32532|中危|
|undertow AJP 拒绝服务漏洞|拒绝服务|[MPS-2022-18098](https://www.oscs1024.com/hd/MPS-2022-18098)|CVE-2022-2053|中危|
|Elastic Stack Kibana 存在缺少授权漏洞|授权检查缺失|[MPS-2022-2136](https://www.oscs1024.com/hd/MPS-2022-2136)|CVE-2022-23709|中危|
|Elastic Stack Kibana 存在 XSS 漏洞|XSS|[MPS-2022-2137](https://www.oscs1024.com/hd/MPS-2022-2137)|CVE-2022-23710|中危|
|Netty 存在信息泄露漏洞||[MPS-2022-3790](https://www.oscs1024.com/hd/MPS-2022-3790)|CVE-2022-24823|中危|
|UReport2-console 代码问题漏洞|反序列化|[MPS-2022-5126](https://www.oscs1024.com/hd/MPS-2022-5126)|CVE-2022-25767|严重|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|Eclipse Californium 安全漏洞|不正确的行为次序：早期放大攻击|[MPS-2022-52744](https://www.oscs1024.com/hd/MPS-2022-52744)|CVE-2022-2576|高危|
|Bouncy Castle <1.69 认证绕过漏洞|密码学问题|[MPS-2022-54305](https://www.oscs1024.com/hd/MPS-2022-54305)||中危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|Apache POI <5.2.1 拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-5663](https://www.oscs1024.com/hd/MPS-2022-5663)|CVE-2022-26336|中危|
|Apache Shiro < 1.10.0 身份认证绕过漏洞|授权检查错误|[MPS-2022-56931](https://www.oscs1024.com/hd/MPS-2022-56931)|CVE-2022-40664|严重|
|xuxueli xxl-job 存在命令注入漏洞|命令注入|[MPS-2022-57270](https://www.oscs1024.com/hd/MPS-2022-57270)|CVE-2022-40929|严重|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|Netty <4.1.86.Final 存在 CRLF 注入漏洞||[MPS-2022-58552](https://www.oscs1024.com/hd/MPS-2022-58552)|CVE-2022-41915|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|Apache Commons Text <1.10.0 远程代码执行漏洞|反序列化|[MPS-2022-59712](https://www.oscs1024.com/hd/MPS-2022-59712)|CVE-2022-42889|严重|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot在Cloud Foundry中部署存在路由限制绕过风险|访问控制不当|[MPS-2022-62845](https://www.oscs1024.com/hd/MPS-2022-62845)|CVE-2023-20873|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|Hutool 存在拒绝服务漏洞|越界写入|[MPS-2022-64976](https://www.oscs1024.com/hd/MPS-2022-64976)|CVE-2022-45688|中危|
|Hutool 存在拒绝服务漏洞|越界写入|[MPS-2022-64977](https://www.oscs1024.com/hd/MPS-2022-64977)|CVE-2022-45689|中危|
|Hutool 存在拒绝服务漏洞|越界写入|[MPS-2022-64978](https://www.oscs1024.com/hd/MPS-2022-64978)|CVE-2022-45690|中危|
|spring-boot <2.2.11.RELEASE 存在目录劫持漏洞|将资源暴露给错误范围|[MPS-2022-6780](https://www.oscs1024.com/hd/MPS-2022-6780)|CVE-2022-27772|高危|
|Red Hat Undertow 安全漏洞|证书验证不恰当|[MPS-2022-68061](https://www.oscs1024.com/hd/MPS-2022-68061)|CVE-2022-4492|高危|
|spring-beans 远程代码执行漏洞(Spring4Shell)|表达式语言注入|[MPS-2022-6820](https://www.oscs1024.com/hd/MPS-2022-6820)|CVE-2022-22965|严重|
|Hutool zip 拒绝服务漏洞||[MPS-2022-68308](https://www.oscs1024.com/hd/MPS-2022-68308)|CVE-2022-4565|中危|
|Mybatis-PageHelper SQL注入漏洞|SQL注入|[MPS-2022-7189](https://www.oscs1024.com/hd/MPS-2022-7189)|CVE-2022-28111|严重|
|Red Hat Undertow 资源管理错误漏洞|拒绝服务|[MPS-2022-7892](https://www.oscs1024.com/hd/MPS-2022-7892)|CVE-2022-1259|高危|
|undertow 存在分布式拒绝服务攻击|未加检查的返回值|[MPS-2022-8394](https://www.oscs1024.com/hd/MPS-2022-8394)|CVE-2022-1319|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Apache Shiro <1.11.0 存在身份验证绕过漏洞|解释冲突|[MPS-2023-0169](https://www.oscs1024.com/hd/MPS-2023-0169)|CVE-2023-22602|中危|
|hutool 存在反序列化漏洞|反序列化|[MPS-2023-2460](https://www.oscs1024.com/hd/MPS-2023-2460)|CVE-2023-24162|高危|
|ureport v2.2.9 代码问题漏洞|XXE|[MPS-2023-2484](https://www.oscs1024.com/hd/MPS-2023-2484)|CVE-2023-24187|高危|
|UReport 路径遍历漏洞|路径遍历|[MPS-2023-2485](https://www.oscs1024.com/hd/MPS-2023-2485)|CVE-2023-24188|严重|
|URule 代码问题漏洞|XXE|[MPS-2023-2486](https://www.oscs1024.com/hd/MPS-2023-2486)|CVE-2023-24189|严重|
|Apache Commons FileUpload <1.5 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2023-3553](https://www.oscs1024.com/hd/MPS-2023-3553)|CVE-2023-24998|中危|
|XXL-JOB 跨站请求伪造漏洞|CSRF|[MPS-2023-3818](https://www.oscs1024.com/hd/MPS-2023-3818)|CVE-2023-0674|中危|
|【存在争议】MybatisPlus <= 3.5.3.1 TenantPlugin 组件 存在 sql 注入漏洞|SQL注入|[MPS-2023-3977](https://www.oscs1024.com/hd/MPS-2023-3977)|CVE-2023-25330|高危|
|xxl-job 存在存储型XSS漏洞|XSS|[MPS-2023-5196](https://www.oscs1024.com/hd/MPS-2023-5196)||中危|
|Hutool createTempFile函数敏感信息泄漏漏洞|未授权敏感信息泄露|[MPS-4soz-eyma](https://www.oscs1024.com/hd/MPS-4soz-eyma)|CVE-2023-33695|中危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Apache Shiro 身份验证绕过漏洞|路径遍历|[MPS-i2ro-tb93](https://www.oscs1024.com/hd/MPS-i2ro-tb93)|CVE-2023-34478|严重|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|hutool <=5.8.17 存在SPEL命令执行风险|代码注入|[MPS-jdrq-1ywv](https://www.oscs1024.com/hd/MPS-jdrq-1ywv)||高危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|基于 Thymeleaf 沙箱逃逸的 Spring Boot Admin 远程代码执行漏洞|代码注入|[MPS-p6bo-i7nw](https://www.oscs1024.com/hd/MPS-p6bo-i7nw)|CVE-2023-38286|严重|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|Apache Tomcat FORM 重定向漏洞|跨站重定向|[MPS-uy56-j8e4](https://www.oscs1024.com/hd/MPS-uy56-j8e4)|CVE-2023-41080|低危|
|HuTool XML外部实体注入漏洞|XXE|[MPS-xd3s-4gev](https://www.oscs1024.com/hd/MPS-xd3s-4gev)|CVE-2023-3276|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|cn.hutool:hutool-all|5.4.5|5.8.20|直接依赖|强烈建议修复|C:0|H:2|M:7|L:0|
|cn.hutool:hutool-core|4.6.1|5.8.20|间接依赖|强烈建议修复|C:0|H:1|M:3|L:0|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.12|11.0.0-m6|间接依赖|强烈建议修复|C:1|H:10|M:5|L:2|
|de.codecentric:spring-boot-admin-server|2.1.0||间接依赖|强烈建议修复|C:1|H:0|M:0|L:0|
|cn.hutool:hutool-core|5.4.0|5.8.20|间接依赖|强烈建议修复|C:0|H:1|M:3|L:0|
|io.netty:netty-codec-http|4.1.29.Final|4.1.86.final|间接依赖|建议修复|C:2|H:2|M:5|L:0|
|io.undertow:undertow-websockets-jsr|2.0.14.Final|2.2.10.Final|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.hibernate:hibernate-core|5.3.7.Final|5.4.24.Final|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|org.apache.shiro:shiro-web|1.4.0|2.0.0-alpha-3|间接依赖|建议修复|C:5|H:1|M:2|L:0|
|org.codehaus.jackson:jackson-mapper-asl|1.9.11||间接依赖|建议修复|C:1|H:1|M:0|L:0|
|org.elasticsearch:elasticsearch|7.3.0|8.2.1|直接依赖|建议修复|C:0|H:2|M:7|L:1|
|org.mybatis:mybatis|3.5.0|3.5.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.xmlbeans:xmlbeans|2.3.0|3.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework:spring-web|5.1.2.RELEASE|6.0.0|间接依赖|建议修复|C:1|H:2|M:1|L:0|
|org.springframework.boot:spring-boot|2.1.0.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.shiro:shiro-spring|1.4.0|1.9.1|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework.security.oauth:spring-security-oauth2|2.3.4.RELEASE|2.5.2.RELEASE|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|org.apache.poi:poi-ooxml|3.16|4.1.1|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.yaml:snakeyaml|1.23|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|org.apache.poi:poi-scratchpad|3.16|5.2.1|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|com.alibaba:fastjson|1.2.50|1.2.83|间接依赖|建议修复|C:3|H:2|M:0|L:0|
|io.netty:netty-codec|4.1.29.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|com.bstek.ureport:ureport2-console|2.2.9||间接依赖|建议修复|C:3|H:1|M:2|L:0|
|org.springframework:spring-messaging|5.1.2.RELEASE|5.3.20|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.alibaba:dubbo|2.6.0|2.6.10|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|dom4j:dom4j|1.6.1||间接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.github.pagehelper:pagehelper|5.1.8|5.3.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|io.netty:netty|3.10.6.Final||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.zookeeper:zookeeper|3.4.8|3.5.5|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|commons-beanutils:commons-beanutils|1.9.3|1.9.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.freemarker:freemarker|2.3.28|2.3.30|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-all|4.1.29.Final|4.1.44.Final|间接依赖|建议修复|C:2|H:2|M:0|L:0|
|io.springfox:springfox-swagger-ui|2.9.2|2.10.0|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.jboss.netty:netty|3.2.5.Final||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.mybatis:mybatis|3.4.2|3.5.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.security:spring-security-core|5.1.1.RELEASE|5.4.4|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|org.apache.poi:poi|3.16|3.17|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.mybatis:mybatis|3.4.6|3.5.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.xuxueli:xxl-rpc-core|1.4.1||间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework.data:spring-data-mongodb|2.1.2.RELEASE|3.4.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-context|5.1.2.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|log4j:log4j|1.2.17||间接依赖|建议修复|C:2|H:3|M:0|L:1|
|log4j:log4j|1.2.16||间接依赖|建议修复|C:2|H:3|M:0|L:1|
|org.xerial.snappy:snappy-java|1.1.7.1|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|com.baomidou:mybatis-plus-extension|3.1.0||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.alibaba:fastjson|1.2.58|1.2.83|间接依赖|建议修复|C:3|H:2|M:0|L:0|
|commons-fileupload:commons-fileupload|1.3.2|1.5|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.1.0.RELEASE|3.0.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.elasticsearch:elasticsearch|6.4.2|8.2.1|间接依赖|建议修复|C:0|H:1|M:9|L:1|
|io.undertow:undertow-core|2.0.14.Final|2.3.6.final|间接依赖|建议修复|C:1|H:7|M:7|L:0|
|org.apache.commons:commons-text|1.6|1.10.0|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.xuxueli:xxl-job-core|2.1.0|2.3.0|直接依赖|建议修复|C:1|H:0|M:3|L:0|
|org.codehaus.groovy:groovy|2.4.5|4.0.0-alpha-2|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework:spring-beans|5.1.2.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|io.undertow:undertow-servlet|2.0.14.Final|2.3.7.final|间接依赖|建议修复|C:0|H:3|M:1|L:0|
|io.netty:netty-handler|4.1.29.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13||间接依赖|建议修复|C:1|H:1|M:0|L:0|
|mysql:mysql-connector-java|8.0.21|8.0.28|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.apache.shiro:shiro-crypto-cipher|1.4.0|1.4.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty|3.7.0.Final|3.10.3.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|org.apache.shiro:shiro-core|1.4.0|1.9.1|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|com.github.pagehelper:pagehelper|5.1.7|5.3.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.quartz-scheduler:quartz|2.3.0|2.3.2|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.thymeleaf:thymeleaf-spring5|3.0.11.RELEASE|3.0.13.RELEASE|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.google.protobuf:protobuf-java|3.11.4|3.21.7|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.dom4j:dom4j|2.1.1|2.1.2|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|ch.qos.logback:logback-core|1.2.3|1.2.8|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.jolokia:jolokia-core|1.6.0|1.6.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.projectreactor.netty:reactor-netty|0.8.2.RELEASE|1.0.24|间接依赖|建议修复|C:0|H:2|M:2|L:0|
|com.squareup.okio:okio|1.17.2|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.bstek.ureport:ureport2-core|2.2.9||间接依赖|建议修复|C:1|H:1|M:0|L:0|
|commons-collections:commons-collections|3.2.1|3.2.2|间接依赖|建议修复|C:1|H:2|M:0|L:0|
|org.springframework.security:spring-security-web|5.1.1.RELEASE|6.1.2|间接依赖|建议修复|C:1|H:0|M:0|L:1|
|com.fasterxml.jackson.core:jackson-databind|2.9.7|2.14.0-rc1|间接依赖|建议修复|C:17|H:36|M:5|L:0|
|commons-io:commons-io|2.4|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.1.0.RELEASE|3.0.7|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.9.7|2.12.1|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|cn.hutool:hutool-http|5.4.0|5.7.19|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.bouncycastle:bcprov-jdk15on|1.56|1.69|间接依赖|可选修复|C:0|H:1|M:4|L:0|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.9.7|2.9.8|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-transport-native-epoll|4.1.29.Final|4.1.59.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-core|5.1.2.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.apache.httpcomponents:httpclient|4.5.6|4.5.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|5.1.2.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.springframework.data:spring-data-jpa|2.1.2.RELEASE|2.1.8.RELEASE|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework.amqp:spring-amqp|2.1.0.RELEASE|2.3.12|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|cn.hutool:hutool-json|5.4.0|5.8.11|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|org.jboss.xnio:xnio-api|3.3.8.Final|3.8.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.codehaus.groovy:groovy|2.5.3|4.0.0-alpha-2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-io:commons-io|2.6|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.glassfish:javax.el|3.0.0||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-common|4.1.29.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.hibernate.validator:hibernate-validator|6.0.13.Final|6.1.3.Final|直接依赖|可选修复|C:0|H:0|M:2|L:0|
|io.netty:netty-codec-http2|4.1.29.Final|4.1.61.Final|间接依赖|可选修复|C:0|H:4|M:2|L:0|
|commons-io:commons-io|2.2|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.bouncycastle:bcprov-jdk15on|1.62|1.69|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|commons-codec:commons-codec|1.11|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|com.google.code.gson:gson|2.8.5|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.zookeeper:zookeeper|3.5.4-beta|3.5.5|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|cn.hutool:hutool-json|4.6.1|5.8.11|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|com.google.guava:guava|29.0-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:1|
|cn.hutool:hutool-http|4.6.1|5.7.19|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|380|Low|
|LGPL-2.1|7|Medium|
|MPL-1.1|4|Low|
|MIT|37|Low|
|自定义许可证|49|Low|
|EPL-1.0|5|Low|
|LGPL-2.1-or-later|2|Low|
|LGPL-3.0|1|Medium|
|WTFPL|1|Low|
|CDDL-1.1|1|Low|
|GPL-2.0|1|Medium|
|GPL-3.0|3|Medium|
|BSD-3-Clause|1|Low|
|AGPL-3.0|1|High|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|io.netty:netty-transport|4.1.29.Final|间接依赖|maven|
|org.elasticsearch:elasticsearch-x-content|7.3.0|间接依赖|maven|
|io.swagger:swagger-models|1.5.20|间接依赖|maven|
|org.apache.curator:curator-recipes|4.1.0|直接依赖|maven|
|org.jboss:jandex|2.0.5.Final|间接依赖|maven|
|org.apache.shiro:shiro-web|1.4.0|间接依赖|maven|
|org.elasticsearch.client:transport|6.4.2|间接依赖|maven|
|org.apache.velocity:velocity-engine-core|2.1|直接依赖|maven|
|io.netty:netty-resolver|4.1.29.Final|间接依赖|maven|
|xml-apis:xml-apis|1.4.01|间接依赖|maven|
|io.springfox:springfox-schema|2.9.2|间接依赖|maven|
|org.javassist:javassist|3.23.1-GA|间接依赖|maven|
|org.thymeleaf:thymeleaf-spring5|3.0.11.RELEASE|间接依赖|maven|
|org.apache.shiro:shiro-crypto-cipher|1.4.0|间接依赖|maven|
|org.springframework.plugin:spring-plugin-core|1.2.0.RELEASE|间接依赖|maven|
|org.apache.lucene:lucene-memory|7.4.0|间接依赖|maven|
|com.github.pagehelper:pagehelper-spring-boot-starter|1.2.9|直接依赖|maven|
|org.codehaus.groovy:groovy|2.4.5|间接依赖|maven|
|me.zhyd.oauth:JustAuth|1.11.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.9.7|间接依赖|maven|
|org.elasticsearch.plugin:rank-eval-client|7.3.0|间接依赖|maven|
|io.netty:netty|3.7.0.Final|间接依赖|maven|
|io.netty:netty-codec-http|4.1.29.Final|间接依赖|maven|
|org.elasticsearch:elasticsearch-secure-sm|7.3.0|间接依赖|maven|
|com.carrotsearch:hppc|0.7.1|间接依赖|maven|
|org.springframework:spring-web|5.1.2.RELEASE|间接依赖|maven|
|com.github.oshi:oshi-core|3.9.1|直接依赖|maven|
|io.springfox:springfox-spring-web|2.9.2|间接依赖|maven|
|javax.persistence:javax.persistence-api|2.2|间接依赖|maven|
|io.springfox:springfox-swagger-common|2.8.0|间接依赖|maven|
|org.activiti:activiti-api-runtime-shared-impl|7.1.0.M2|间接依赖|maven|
|com.google.code.gson:gson|2.8.5|间接依赖|maven|
|org.elasticsearch.plugin:reindex-client|6.4.2|间接依赖|maven|
|tk.mybatis:mapper-weekend|1.1.5|间接依赖|maven|
|org.activiti:activiti-spring|7.1.0.M2|间接依赖|maven|
|cn.hutool:hutool-http|4.6.1|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.9.7|间接依赖|maven|
|com.google.guava:guava|29.0-jre|直接依赖|maven|
|com.github.pagehelper:pagehelper|5.1.8|间接依赖|maven|
|com.google.zxing:javase|3.4.1|直接依赖|maven|
|io.springfox:springfox-spi|2.9.2|间接依赖|maven|
|net.sf.jopt-simple:jopt-simple|5.0.2|间接依赖|maven|
|de.siegmar:logback-gelf|2.0.0|直接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.11.1|间接依赖|maven|
|antlr:antlr|2.7.7|间接依赖|maven|
|org.activiti:activiti-bpmn-model|7.1.0.M2|间接依赖|maven|
|org.elasticsearch.plugin:lang-mustache-client|6.4.2|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.2|间接依赖|maven|
|org.apache.poi:poi|3.16|间接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.56|间接依赖|maven|
|com.baomidou:dynamic-datasource-spring-boot-starter|2.5.0|直接依赖|maven|
|io.github.lukehutch:fast-classpath-scanner|2.18.1|间接依赖|maven|
|org.apache.poi:ooxml-schemas|1.3|间接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.9.13|间接依赖|maven|
|org.antlr:antlr4-runtime|4.2|间接依赖|maven|
|org.activiti:activiti-api-process-runtime-impl|7.1.0.M2|间接依赖|maven|
|org.springframework.ldap:spring-ldap-core|2.3.2.RELEASE|间接依赖|maven|
|org.springframework:spring-orm|5.1.2.RELEASE|间接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-starter|1.3.2|直接依赖|maven|
|org.activiti.api:activiti-api-model-shared-impl|7.1.0.M2|间接依赖|maven|
|io.netty:netty-common|4.1.29.Final|间接依赖|maven|
|de.odysseus.juel:juel-spi|2.2.7|间接依赖|maven|
|org.activiti:activiti-spring-boot-starter|7.1.0.M2|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.9.7|间接依赖|maven|
|org.springframework:spring-context|5.1.2.RELEASE|间接依赖|maven|
|org.apache.commons:commons-collections4|4.1|间接依赖|maven|
|com.bstek.ureport:ureport2-font|2.0.1|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.29.Final|间接依赖|maven|
|com.zaxxer:HikariCP|3.2.0|直接依赖|maven|
|io.springfox:springfox-swagger2|2.9.2|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.9.7|间接依赖|maven|
|p6spy:p6spy|3.8.1|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.9.0|间接依赖|maven|
|com.sun.xml.bind:jaxb-core|2.3.0.1|间接依赖|maven|
|com.squareup.okhttp3:okhttp|3.14.4|间接依赖|maven|
|cn.hutool:hutool-json|4.6.1|间接依赖|maven|
|com.xkcoding:dubbo-common|1.0.0-SNAPSHOT|直接依赖|maven|
|org.elasticsearch.plugin:transport-netty4-client|6.4.2|间接依赖|maven|
|io.springfox:springfox-spring-web|2.8.0|间接依赖|maven|
|com.alibaba:fastjson|1.2.58|间接依赖|maven|
|org.apache.yetus:audience-annotations|0.5.0|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.7.1|间接依赖|maven|
|org.mybatis:mybatis|3.5.0|间接依赖|maven|
|org.elasticsearch:elasticsearch-cli|6.4.2|间接依赖|maven|
|org.activiti.core.common:activiti-spring-security-policies|7.1.0.M2|间接依赖|maven|
|org.apache.commons:commons-exec|1.3|间接依赖|maven|
|io.shardingsphere:sharding-core|3.1.0|间接依赖|maven|
|org.apache.curator:curator-framework|4.1.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.1.0.RELEASE|直接依赖|maven|
|com.baomidou:mybatis-plus-boot-starter|3.1.0|直接依赖|maven|
|org.springframework:spring-aspects|5.1.2.RELEASE|间接依赖|maven|
|tk.mybatis:mapper-extra|1.0.5|间接依赖|maven|
|tk.mybatis:mapper-spring-boot-autoconfigure|2.1.0|间接依赖|maven|
|commons-codec:commons-codec|1.11|间接依赖|maven|
|org.activiti.api:activiti-api-task-model-impl|7.1.0.M2|间接依赖|maven|
|org.activiti:activiti-engine|7.1.0.M2|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-client|6.4.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-quartz|2.1.0.RELEASE|直接依赖|maven|
|org.apache.lucene:lucene-spatial3d|8.1.0|间接依赖|maven|
|commons-fileupload:commons-fileupload|1.3.2|间接依赖|maven|
|org.aspectj:aspectjweaver|1.9.2|间接依赖|maven|
|com.corundumstudio.socketio:netty-socketio|1.7.16|直接依赖|maven|
|com.jfinal:enjoy|3.5|直接依赖|maven|
|commons-collections:commons-collections|3.2.1|间接依赖|maven|
|org.springframework:spring-context-support|5.1.2.RELEASE|间接依赖|maven|
|org.springframework.security:spring-security-web|5.1.1.RELEASE|间接依赖|maven|
|com.github.javen205:IJPay-All|2.7.0|直接依赖|maven|
|org.activiti:activiti-spring-process-extensions|7.1.0.M2|间接依赖|maven|
|com.melloware:jasypt|1.9.4|间接依赖|maven|
|org.apache.lucene:lucene-analyzers-common|8.1.0|间接依赖|maven|
|org.apache.lucene:lucene-queries|7.4.0|间接依赖|maven|
|org.thymeleaf.extras:thymeleaf-extras-java8time|3.0.1.RELEASE|间接依赖|maven|
|io.lettuce:lettuce-core|5.1.2.RELEASE|间接依赖|maven|
|org.hibernate.common:hibernate-commons-annotations|5.0.4.Final|间接依赖|maven|
|org.freemarker:freemarker|2.3.28|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|javax.persistence:persistence-api|1.0|间接依赖|maven|
|tk.mybatis:mapper-spring|1.1.5|间接依赖|maven|
|org.apache.lucene:lucene-core|8.1.0|间接依赖|maven|
|io.springfox:springfox-core|2.8.0|间接依赖|maven|
|tk.mybatis:mapper-base|1.1.0|间接依赖|maven|
|org.apache.shiro:shiro-config-core|1.4.0|间接依赖|maven|
|org.projectlombok:lombok|1.18.2|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.10|间接依赖|maven|
|com.fasterxml:classmate|1.4.0|间接依赖|maven|
|io.swagger:swagger-models|1.5.14|间接依赖|maven|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13|间接依赖|maven|
|org.apache.lucene:lucene-backward-codecs|8.1.0|间接依赖|maven|
|org.springframework.security.oauth.boot:spring-security-oauth2-autoconfigure|2.1.0.RELEASE|直接依赖|maven|
|io.swagger:swagger-annotations|1.5.14|间接依赖|maven|
|org.springframework:spring-oxm|5.1.2.RELEASE|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|org.activiti:activiti-spring-app-process|7.1.0.M2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-freemarker|2.1.0.RELEASE|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-undertow|2.1.0.RELEASE|直接依赖|maven|
|commons-lang:commons-lang|2.4|间接依赖|maven|
|eu.bitwalker:UserAgentUtils|1.20|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.9.7|间接依赖|maven|
|org.springframework.kafka:spring-kafka|2.2.0.RELEASE|直接依赖|maven|
|com.github.jsqlparser:jsqlparser|1.2|间接依赖|maven|
|cn.hutool:hutool-http|5.4.0|间接依赖|maven|
|com.baomidou:mybatis-plus-core|3.1.0|间接依赖|maven|
|org.activiti.api:activiti-api-process-model|7.1.0.M2|间接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-client|7.3.0|直接依赖|maven|
|ch.qos.logback:logback-core|1.2.3|间接依赖|maven|
|org.apache.commons:commons-email|1.5|间接依赖|maven|
|org.glassfish:javax.el|3.0.0|间接依赖|maven|
|org.apache.lucene:lucene-sandbox|8.1.0|间接依赖|maven|
|org.activiti.api:activiti-api-process-runtime|7.1.0.M2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-mail|2.1.0.RELEASE|直接依赖|maven|
|org.activiti.core.common:activiti-core-common-dependencies|7.1.0.M2|间接依赖|maven|
|javax.activation:activation|1.1|间接依赖|maven|
|org.springframework.retry:spring-retry|1.2.2.RELEASE|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.6|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.1.0.RELEASE|直接依赖|maven|
|org.activiti.core.common:activiti-spring-security|7.1.0.M2|间接依赖|maven|
|org.springframework.data:spring-data-neo4j|5.1.2.RELEASE|间接依赖|maven|
|commons-cli:commons-cli|1.2|间接依赖|maven|
|tk.mybatis:mapper-weekend|1.1.4.2|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.5.4-beta|间接依赖|maven|
|com.pig4cloud.plugin:ureport-spring-boot-starter|0.0.1|直接依赖|maven|
|commons-beanutils:commons-beanutils-core|1.8.3|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.1.0.RELEASE|直接依赖|maven|
|com.fasterxml.uuid:java-uuid-generator|3.1.4|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.3|间接依赖|maven|
|org.springframework.data:spring-data-commons|2.1.2.RELEASE|间接依赖|maven|
|com.xkcoding:justauth-spring-boot-starter|1.1.0|直接依赖|maven|
|org.antlr:antlr4-runtime|4.5.3|间接依赖|maven|
|org.apache.lucene:lucene-spatial|8.1.0|间接依赖|maven|
|io.netty:netty-all|4.1.29.Final|间接依赖|maven|
|io.springfox:springfox-swagger2|2.8.0|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|org.apache.lucene:lucene-memory|8.1.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-webflux|2.1.0.RELEASE|间接依赖|maven|
|javax.transaction:javax.transaction-api|1.3|间接依赖|maven|
|org.neo4j:neo4j-ogm-bolt-driver|3.1.4|间接依赖|maven|
|com.github.ulisesbocchio:jasypt-spring-boot-starter|2.1.1|直接依赖|maven|
|org.activiti.api:activiti-api-task-model|7.1.0.M2|间接依赖|maven|
|org.activiti.api:activiti-api-task-runtime|7.1.0.M2|间接依赖|maven|
|io.swagger:swagger-annotations|1.5.20|间接依赖|maven|
|org.apache.poi:poi-scratchpad|3.16|间接依赖|maven|
|tk.mybatis:mapper-core|1.0.5|间接依赖|maven|
|com.ibeetl:beetlsql|2.10.40|间接依赖|maven|
|com.alipay.sdk:alipay-sdk-java|4.10.159.ALL|直接依赖|maven|
|org.elasticsearch:jna|4.5.1|间接依赖|maven|
|org.activiti:activiti-api-task-runtime-impl|7.1.0.M2|间接依赖|maven|
|org.reflections:reflections|0.9.11|间接依赖|maven|
|org.elasticsearch.plugin:parent-join-client|7.3.0|间接依赖|maven|
|org.elasticsearch:elasticsearch|6.4.2|间接依赖|maven|
|com.beust:jcommander|1.78|间接依赖|maven|
|org.springframework:spring-core|5.1.2.RELEASE|间接依赖|maven|
|com.sun.mail:javax.mail|1.6.2|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.29.Final|间接依赖|maven|
|org.jboss.netty:netty|3.2.5.Final|间接依赖|maven|
|org.apache.lucene:lucene-analyzers-common|7.4.0|间接依赖|maven|
|com.battcn:swagger-spring-boot-autoconfigure|2.1.2-RELEASE|间接依赖|maven|
|org.antlr:antlr-runtime|3.5.2|间接依赖|maven|
|org.apache.lucene:lucene-highlighter|7.4.0|间接依赖|maven|
|org.activiti.core.common:activiti-connector-model|7.1.0.M2|间接依赖|maven|
|tk.mybatis:mapper-spring-boot-autoconfigure|2.0.4|间接依赖|maven|
|com.github.pagehelper:pagehelper-spring-boot-autoconfigure|1.2.9|间接依赖|maven|
|org.activiti.api:activiti-api-runtime-shared|7.1.0.M2|间接依赖|maven|
|tk.mybatis:mapper-spring|1.1.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|2.1.0.RELEASE|直接依赖|maven|
|org.abego.treelayout:org.abego.treelayout.core|1.0.3|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.29.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-ldap|2.1.0.RELEASE|直接依赖|maven|
|com.github.pagehelper:pagehelper-spring-boot-starter|1.2.10|直接依赖|maven|
|com.carrotsearch:hppc|0.8.1|间接依赖|maven|
|net.java.dev.jna:jna|4.5.2|间接依赖|maven|
|com.github.jsqlparser:jsqlparser|1.4|间接依赖|maven|
|javax.servlet:javax.servlet-api|4.0.1|间接依赖|maven|
|com.ibeetl:beetl-framework-starter|1.1.63.RELEASE|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-amqp|2.1.0.RELEASE|直接依赖|maven|
|org.activiti.core.common:activiti-spring-application|7.1.0.M2|间接依赖|maven|
|org.codehaus.jackson:jackson-mapper-asl|1.9.11|间接依赖|maven|
|org.elasticsearch.plugin:percolator-client|6.4.2|间接依赖|maven|
|io.netty:netty-handler|4.1.29.Final|间接依赖|maven|
|org.activiti.api:activiti-api-process-model-impl|7.1.0.M2|间接依赖|maven|
|de.codecentric:spring-boot-admin-client|2.1.0|间接依赖|maven|
|cn.hutool:hutool-json|5.4.0|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.9|间接依赖|maven|
|com.battcn:swagger-vue-ui|2.1.2-RELEASE|间接依赖|maven|
|org.apache.shiro:shiro-crypto-core|1.4.0|间接依赖|maven|
|org.apache.lucene:lucene-misc|7.4.0|间接依赖|maven|
|com.github.ulisesbocchio:jasypt-spring-boot|2.1.1|间接依赖|maven|
|org.springframework.amqp:spring-rabbit|2.1.0.RELEASE|间接依赖|maven|
|org.elasticsearch.plugin:aggs-matrix-stats-client|7.3.0|间接依赖|maven|
|org.jolokia:jolokia-core|1.6.0|间接依赖|maven|
|com.mchange:mchange-commons-java|0.2.11|间接依赖|maven|
|org.slf4j:slf4j-log4j12|1.7.25|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.9.7|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|org.mybatis:mybatis-spring|1.3.2|间接依赖|maven|
|io.netty:netty-buffer|4.1.29.Final|间接依赖|maven|
|org.apache.shiro:shiro-cache|1.4.0|间接依赖|maven|
|tk.mybatis:mapper-spring-boot-starter|2.1.5|直接依赖|maven|
|com.bstek.ureport:ureport2-console|2.2.9|间接依赖|maven|
|org.springframework:spring-aop|5.1.2.RELEASE|间接依赖|maven|
|org.elasticsearch.plugin:lang-mustache-client|7.3.0|间接依赖|maven|
|org.elasticsearch:elasticsearch|7.3.0|直接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.9.11|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.11.1|间接依赖|maven|
|commons-io:commons-io|2.6|间接依赖|maven|
|org.apache.shiro:shiro-spring|1.4.0|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|间接依赖|maven|
|de.codecentric:spring-boot-admin-starter-server|2.1.0|直接依赖|maven|
|org.springframework.security.oauth:spring-security-oauth2|2.3.4.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-jpa|2.1.0.RELEASE|直接依赖|maven|
|tk.mybatis:mapper-spring-boot-autoconfigure|2.1.5|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.3.4|间接依赖|maven|
|org.mongodb:mongodb-driver|3.8.2|间接依赖|maven|
|de.codecentric:spring-boot-admin-starter-client|2.1.0|直接依赖|maven|
|cn.hutool:hutool-log|4.6.1|间接依赖|maven|
|org.apache.poi:poi-ooxml|3.16|间接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.56|间接依赖|maven|
|org.elasticsearch:elasticsearch-core|7.3.0|间接依赖|maven|
|org.apache.lucene:lucene-queryparser|8.1.0|间接依赖|maven|
|org.apache.shiro:shiro-event|1.4.0|间接依赖|maven|
|org.thymeleaf:thymeleaf|3.0.11.RELEASE|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.3|间接依赖|maven|
|org.apache.lucene:lucene-spatial-extras|8.1.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-redis|2.1.0.RELEASE|直接依赖|maven|
|com.rabbitmq:amqp-client|5.4.3|间接依赖|maven|
|org.springframework.security:spring-security-config|5.1.1.RELEASE|间接依赖|maven|
|org.dom4j:dom4j|2.1.1|间接依赖|maven|
|org.mybatis:mybatis|3.4.2|间接依赖|maven|
|com.caucho:hessian|4.0.60|间接依赖|maven|
|org.apache.lucene:lucene-suggest|7.4.0|间接依赖|maven|
|org.springframework:spring-webmvc|5.1.2.RELEASE|间接依赖|maven|
|io.netty:netty|3.10.6.Final|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.9.3|间接依赖|maven|
|org.neo4j:neo4j-ogm-core|3.1.4|间接依赖|maven|
|com.ibeetl:beetlsql|2.10.34|间接依赖|maven|
|com.xuxueli:xxl-registry-client|1.0.2|间接依赖|maven|
|org.apache.lucene:lucene-highlighter|8.1.0|间接依赖|maven|
|org.mongodb:bson|3.8.2|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.25|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.0.13.Final|直接依赖|maven|
|org.apache.lucene:lucene-spatial-extras|7.4.0|间接依赖|maven|
|org.flywaydb:flyway-core|5.2.1|直接依赖|maven|
|org.springframework:spring-jcl|5.1.2.RELEASE|间接依赖|maven|
|org.jboss.spec.javax.websocket:jboss-websocket-api_1.1_spec|1.1.3.Final|间接依赖|maven|
|tk.mybatis:mapper-spring-boot-starter|2.1.0|直接依赖|maven|
|com.squareup.okio:okio|1.17.2|间接依赖|maven|
|org.springframework:spring-jdbc|5.1.2.RELEASE|间接依赖|maven|
|org.springframework.data:spring-data-redis|2.1.2.RELEASE|间接依赖|maven|
|javax.validation:validation-api|2.0.1.Final|间接依赖|maven|
|org.synchronoss.cloud:nio-multipart-parser|1.1.0|间接依赖|maven|
|org.springframework:spring-tx|5.1.2.RELEASE|间接依赖|maven|
|org.apache.lucene:lucene-spatial3d|7.4.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-reactor-netty|2.1.0.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.1.0.RELEASE|间接依赖|maven|
|org.apache.commons:commons-pool2|2.6.0|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-neo4j|2.1.0.RELEASE|直接依赖|maven|
|log4j:log4j|1.2.16|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-jdbc|2.1.0.RELEASE|直接依赖|maven|
|io.undertow:undertow-websockets-jsr|2.0.14.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-websocket|2.1.0.RELEASE|直接依赖|maven|
|org.apache.shiro:shiro-config-ogdl|1.4.0|间接依赖|maven|
|org.apache.shiro:shiro-crypto-hash|1.4.0|间接依赖|maven|
|cn.hutool:hutool-crypto|5.4.0|间接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-high-level-client|7.3.0|直接依赖|maven|
|mysql:mysql-connector-java|8.0.21|直接依赖|maven|
|com.tdunning:t-digest|3.2|间接依赖|maven|
|org.springframework:spring-messaging|5.1.2.RELEASE|间接依赖|maven|
|org.javassist:javassist|3.20.0-GA|间接依赖|maven|
|org.elasticsearch:elasticsearch-core|6.4.2|间接依赖|maven|
|org.antlr:ST4|4.0.8|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.25|间接依赖|maven|
|org.apache.shiro:shiro-core|1.4.0|间接依赖|maven|
|org.springframework.boot:spring-boot-configuration-processor|2.1.0.RELEASE|直接依赖|maven|
|org.antlr:antlr4-annotations|4.2|间接依赖|maven|
|com.baomidou:mybatis-plus-annotation|3.1.0|间接依赖|maven|
|com.github.spullara.mustache.java:compiler|0.9.3|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-thymeleaf|2.1.0.RELEASE|直接依赖|maven|
|org.apache.shiro:shiro-lang|1.4.0|间接依赖|maven|
|joda-time:joda-time|2.10.1|间接依赖|maven|
|org.apache.velocity:velocity|1.7|间接依赖|maven|
|org.mongodb:mongodb-driver-core|3.8.2|间接依赖|maven|
|com.bstek.ureport:ureport2-core|2.2.9|间接依赖|maven|
|stax:stax-api|1.0.1|间接依赖|maven|
|org.antlr:antlr4|4.7.1|间接依赖|maven|
|org.elasticsearch:elasticsearch-secure-sm|6.4.2|间接依赖|maven|
|com.alibaba:dubbo|2.6.0|间接依赖|maven|
|org.springframework.data:spring-data-elasticsearch|3.1.2.RELEASE|间接依赖|maven|
|org.apache.lucene:lucene-spatial|7.4.0|间接依赖|maven|
|com.xuxueli:xxl-job-core|2.1.0|直接依赖|maven|
|org.springframework:spring-websocket|5.1.2.RELEASE|间接依赖|maven|
|org.checkerframework:checker-qual|2.11.1|间接依赖|maven|
|org.springframework.data:spring-data-jpa|2.1.2.RELEASE|间接依赖|maven|
|com.github.jai-imageio:jai-imageio-core|1.4.0|间接依赖|maven|
|org.springframework.boot:spring-boot|2.1.0.RELEASE|间接依赖|maven|
|org.abego.treelayout:org.abego.treelayout.core|1.0.1|间接依赖|maven|
|com.github.pagehelper:pagehelper|5.1.7|间接依赖|maven|
|org.springframework.security:spring-security-core|5.1.1.RELEASE|间接依赖|maven|
|org.springframework:spring-beans|5.1.2.RELEASE|间接依赖|maven|
|org.attoparser:attoparser|2.0.5.RELEASE|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.11.4|间接依赖|maven|
|io.projectreactor.addons:reactor-extra|3.2.0.RELEASE|间接依赖|maven|
|commons-logging:commons-logging|1.1.1|间接依赖|maven|
|org.apache.curator:curator-client|4.1.0|间接依赖|maven|
|io.micrometer:micrometer-core|1.1.0|间接依赖|maven|
|com.sun.xml.bind:jaxb-impl|2.3.0.1|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.4.8|间接依赖|maven|
|io.springfox:springfox-spi|2.8.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-security|2.1.0.RELEASE|直接依赖|maven|
|org.antlr:antlr4-runtime|4.7.1|间接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.4|间接依赖|maven|
|org.activiti:activiti-bpmn-converter|7.1.0.M2|间接依赖|maven|
|org.apache.poi:poi-ooxml-schemas|3.16|间接依赖|maven|
|com.github.pagehelper:pagehelper-spring-boot-autoconfigure|1.2.10|间接依赖|maven|
|cn.hutool:hutool-core|4.6.1|间接依赖|maven|
|log4j:log4j|1.2.17|间接依赖|maven|
|io.jsonwebtoken:jjwt|0.9.1|直接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.10|间接依赖|maven|
|org.springframework.session:spring-session-core|2.1.1.RELEASE|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.12|间接依赖|maven|
|tk.mybatis:mapper-core|1.1.5|间接依赖|maven|
|tk.mybatis:mapper-weekend|1.1.4.1|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.29.Final|间接依赖|maven|
|org.neo4j:neo4j-ogm-api|3.1.4|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.1.0.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.1.0.RELEASE|间接依赖|maven|
|io.springfox:springfox-bean-validators|2.8.0|间接依赖|maven|
|io.undertow:undertow-core|2.0.14.Final|间接依赖|maven|
|org.apache.lucene:lucene-queryparser|7.4.0|间接依赖|maven|
|net.sf.ehcache:ehcache|2.10.6|直接依赖|maven|
|org.synchronoss.cloud:nio-stream-storage|1.1.3|间接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|org.mybatis:mybatis|3.4.6|间接依赖|maven|
|org.apache.lucene:lucene-join|7.4.0|间接依赖|maven|
|org.jboss.xnio:xnio-nio|3.3.8.Final|间接依赖|maven|
|org.mapstruct:mapstruct|1.2.0.Final|间接依赖|maven|
|net.java.dev.jna:jna-platform|4.5.2|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-smile|2.9.7|间接依赖|maven|
|de.odysseus.juel:juel-api|2.2.7|间接依赖|maven|
|com.xuxueli:xxl-rpc-core|1.4.1|间接依赖|maven|
|com.google.zxing:core|3.3.1|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.12|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.25|间接依赖|maven|
|org.apache.lucene:lucene-suggest|8.1.0|间接依赖|maven|
|org.elasticsearch:elasticsearch-x-content|6.4.2|间接依赖|maven|
|org.activiti.api:activiti-api-dependencies|7.1.0.M2|间接依赖|maven|
|tk.mybatis:mapper-spring-boot-starter|2.0.4|直接依赖|maven|
|de.codecentric:spring-boot-admin-server-cloud|2.1.0|间接依赖|maven|
|tk.mybatis:mapper-extra|1.1.0|间接依赖|maven|
|io.projectreactor:reactor-core|3.2.2.RELEASE|间接依赖|maven|
|org.jboss.xnio:xnio-api|3.3.8.Final|间接依赖|maven|
|io.undertow:undertow-servlet|2.0.14.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-mongodb|2.1.0.RELEASE|直接依赖|maven|
|com.baomidou:mybatis-plus-extension|3.1.0|间接依赖|maven|
|org.apache.xmlbeans:xmlbeans|2.3.0|间接依赖|maven|
|org.springframework.session:spring-session-data-redis|2.1.1.RELEASE|直接依赖|maven|
|com.googlecode.json-simple:json-simple|1.1.1|间接依赖|maven|
|com.ibeetl:beetl-framework-starter|1.1.68.RELEASE|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-cache|2.1.0.RELEASE|直接依赖|maven|
|com.github.virtuald:curvesapi|1.04|间接依赖|maven|
|org.activiti:activiti-process-validation|7.1.0.M2|间接依赖|maven|
|org.javassist:javassist|3.21.0-GA|间接依赖|maven|
|jline:jline|0.9.94|间接依赖|maven|
|io.netty:netty-codec|4.1.29.Final|间接依赖|maven|
|org.springframework:spring-webflux|5.1.2.RELEASE|间接依赖|maven|
|tk.mybatis:mapper-base|1.1.5|间接依赖|maven|
|org.mybatis:mybatis-spring|2.0.0|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.29.Final|间接依赖|maven|
|org.springframework.plugin:spring-plugin-metadata|1.2.0.RELEASE|间接依赖|maven|
|com.itextpdf:itextpdf|5.5.13|间接依赖|maven|
|org.apache.commons:commons-text|1.6|直接依赖|maven|
|commons-io:commons-io|2.4|间接依赖|maven|
|org.elasticsearch:elasticsearch-cli|7.3.0|间接依赖|maven|
|com.alibaba.spring.boot:dubbo-spring-boot-starter|2.0.0|直接依赖|maven|
|org.apache.lucene:lucene-core|7.4.0|间接依赖|maven|
|org.activiti.api:activiti-api-model-shared|7.1.0.M2|间接依赖|maven|
|org.elasticsearch.plugin:parent-join-client|6.4.2|间接依赖|maven|
|org.apache.lucene:lucene-join|8.1.0|间接依赖|maven|
|tk.mybatis:mapper-base|1.0.5|间接依赖|maven|
|org.activiti.build:activiti-parent|7.1.0.M2|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.12|间接依赖|maven|
|org.springframework.data:spring-data-keyvalue|2.1.2.RELEASE|间接依赖|maven|
|org.apache.lucene:lucene-backward-codecs|7.4.0|间接依赖|maven|
|org.springframework.data:spring-data-mongodb|2.1.2.RELEASE|间接依赖|maven|
|io.shardingsphere:sharding-jdbc-core|3.1.0|直接依赖|maven|
|io.springfox:springfox-core|2.9.2|间接依赖|maven|
|org.jboss.spec.javax.annotation:jboss-annotations-api_1.2_spec|1.0.2.Final|间接依赖|maven|
|com.qiniu:qiniu-java-sdk|7.2.29|直接依赖|maven|
|com.101tec:zkclient|0.10|直接依赖|maven|
|org.codehaus.groovy:groovy|2.5.3|间接依赖|maven|
|org.unbescape:unbescape|1.1.6.RELEASE|间接依赖|maven|
|org.apache.kafka:kafka-clients|2.0.0|间接依赖|maven|
|org.springframework.data:spring-data-jdbc|1.0.2.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-actuator|2.1.0.RELEASE|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.1.0.RELEASE|直接依赖|maven|
|org.apache.lucene:lucene-queries|8.1.0|间接依赖|maven|
|tk.mybatis:mapper-core|1.1.0|间接依赖|maven|
|org.quartz-scheduler:quartz|2.3.0|间接依赖|maven|
|org.springframework.data:spring-data-ldap|2.1.2.RELEASE|间接依赖|maven|
|tk.mybatis:mapper-spring|1.0.5|间接依赖|maven|
|org.apache.lucene:lucene-sandbox|7.4.0|间接依赖|maven|
|org.yaml:snakeyaml|1.23|间接依赖|maven|
|de.codecentric:spring-boot-admin-server-ui|2.1.0|间接依赖|maven|
|com.baomidou:mybatis-plus|3.1.0|间接依赖|maven|
|de.codecentric:spring-boot-admin-server|2.1.0|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.62|间接依赖|maven|
|io.projectreactor.netty:reactor-netty|0.8.2.RELEASE|间接依赖|maven|
|com.ibm.icu:icu4j|58.2|间接依赖|maven|
|org.elasticsearch.plugin:rank-eval-client|6.4.2|间接依赖|maven|
|dom4j:dom4j|1.6.1|间接依赖|maven|
|org.activiti.core.common:activiti-spring-connector|7.1.0.M2|间接依赖|maven|
|io.springfox:springfox-swagger-ui|2.9.2|直接依赖|maven|
|io.shardingsphere:sharding-transaction-core|3.1.0|间接依赖|maven|
|io.springfox:springfox-schema|2.8.0|间接依赖|maven|
|org.glassfish:javax.json|1.0.4|间接依赖|maven|
|org.apache.lucene:lucene-grouping|7.4.0|间接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-autoconfigure|1.3.2|间接依赖|maven|
|com.battcn:swagger-spring-boot-starter|2.1.2-RELEASE|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.9.7|间接依赖|maven|
|de.odysseus.juel:juel-impl|2.2.7|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.3.2.Final|间接依赖|maven|
|org.apache.shiro:shiro-spring-boot-starter|1.4.0|直接依赖|maven|
|org.hibernate:hibernate-core|5.3.7.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.1.0.RELEASE|间接依赖|maven|
|com.google.zxing:core|3.4.1|直接依赖|maven|
|com.ibeetl:beetl|2.9.3|间接依赖|maven|
|org.apache.lucene:lucene-misc|8.1.0|间接依赖|maven|
|org.elasticsearch:elasticsearch-geo|7.3.0|间接依赖|maven|
|org.apache.lucene:lucene-grouping|8.1.0|间接依赖|maven|
|org.apache.commons:commons-lang3|3.8.1|直接依赖|maven|
|org.springframework:spring-expression|5.1.2.RELEASE|间接依赖|maven|
|io.springfox:springfox-swagger-common|2.9.2|间接依赖|maven|
|javax.el:el-api|2.2|间接依赖|maven|
|commons-io:commons-io|2.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-elasticsearch|2.1.0.RELEASE|直接依赖|maven|
|cn.hutool:hutool-all|5.4.5|直接依赖|maven|
|cn.hutool:hutool-core|5.4.0|间接依赖|maven|
|org.springframework.security:spring-security-jwt|1.0.9.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator|2.1.0.RELEASE|间接依赖|maven|
|org.neo4j.driver:neo4j-java-driver|1.6.3|间接依赖|maven|
|org.lz4:lz4-java|1.4.1|间接依赖|maven|
|org.activiti.core.common:activiti-spring-identity|7.1.0.M2|间接依赖|maven|
|tk.mybatis:mapper-extra|1.1.5|间接依赖|maven|
|com.alibaba:fastjson|1.2.50|间接依赖|maven|
|org.springframework.amqp:spring-amqp|2.1.0.RELEASE|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)