# apache/druid安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1697309610527776768.svg)](https://www.murphysec.com/console/report/1694047716613976064/1697309610527776768)

仓库描述：Apache Druid: a high performance real-time analytics database.

仓库地址：[https://github.com/apache/druid](https://github.com/apache/druid)

| star：12808 | watch：599 | fork：3578 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-31 22:30:11 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-01 02:45:30 | 组件总数：1896 | 漏洞总数：175 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Square OkHttp 安全漏洞|证书验证不恰当|[MPS-2017-1023](https://www.oscs1024.com/hd/MPS-2017-1023)|CVE-2016-2402|中危|
|Google protobuf 缓冲区错误漏洞|越界写入|[MPS-2017-10841](https://www.oscs1024.com/hd/MPS-2017-10841)|CVE-2015-5237|高危|
|Apache Zookeeper 安全漏洞||[MPS-2017-11297](https://www.oscs1024.com/hd/MPS-2017-11297)|CVE-2017-5637|高危|
|Netty和Play Framework 输入验证错误漏洞|未授权敏感信息泄露|[MPS-2017-11682](https://www.oscs1024.com/hd/MPS-2017-11682)|CVE-2015-2156|高危|
|plexus-utils <3.0.16 命令注入漏洞|OS命令注入|[MPS-2018-0091](https://www.oscs1024.com/hd/MPS-2018-0091)|CVE-2017-1000487|严重|
|Oracle MySQL Connectors 访问控制错误漏洞|使用候选路径或通道进行的认证绕过|[MPS-2018-13771](https://www.oscs1024.com/hd/MPS-2018-13771)|CVE-2018-3258|高危|
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|Apache Derby 权限许可和访问控制问题漏洞|访问控制不当|[MPS-2018-5754](https://www.oscs1024.com/hd/MPS-2018-5754)|CVE-2018-1313|中危|
|Apache Zookeeper 访问控制错误漏洞|授权检查缺失|[MPS-2018-6313](https://www.oscs1024.com/hd/MPS-2018-6313)|CVE-2018-8012|高危|
|Eclipse Jetty 缓存中毒漏洞|HTTP请求走私|[MPS-2018-8346](https://www.oscs1024.com/hd/MPS-2018-8346)|CVE-2017-7656|高危|
|Eclipse Jetty <9.4.11.v20180605 授权绕过漏洞|HTTP请求走私|[MPS-2018-8347](https://www.oscs1024.com/hd/MPS-2018-8347)|CVE-2017-7657|严重|
|Eclipse Jetty <9.4.11.v20180605 存在授权绕过漏洞|HTTP请求走私|[MPS-2018-8415](https://www.oscs1024.com/hd/MPS-2018-8415)|CVE-2017-7658|严重|
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
|jackson-mapper-asl <=1.9.13 XXE 注入漏洞|XXE|[MPS-2019-15048](https://www.oscs1024.com/hd/MPS-2019-15048)|CVE-2019-10172|高危|
|SnakeYAML <1.26 存在 Billion laughs 漏洞|拒绝服务|[MPS-2019-16129](https://www.oscs1024.com/hd/MPS-2019-16129)|CVE-2017-18640|高危|
|Apache Log4j SocketServer反序列化漏洞|反序列化|[MPS-2019-17271](https://www.oscs1024.com/hd/MPS-2019-17271)|CVE-2019-17571|严重|
|Oracle MySQL Connectors 输入验证错误漏洞|使用不兼容类型访问资源（类型混淆）|[MPS-2019-4430](https://www.oscs1024.com/hd/MPS-2019-4430)|CVE-2019-2692|中危|
|FasterXML jackson-databind 反序列化漏洞(mysql gadget绕过)|反序列化|[MPS-2019-5442](https://www.oscs1024.com/hd/MPS-2019-5442)|CVE-2019-12086|高危|
|Apache Zookeeper 授权问题漏洞|授权检查缺失|[MPS-2019-5668](https://www.oscs1024.com/hd/MPS-2019-5668)|CVE-2019-0201|中危|
|FasterXML jackson-databind 反序列化漏洞(jdom gadget绕过)|反序列化|[MPS-2019-6867](https://www.oscs1024.com/hd/MPS-2019-6867)|CVE-2019-12814|中危|
|FasterXML jackson-databind 反序列化漏洞(logback-classic gadget绕过)|反序列化|[MPS-2019-7047](https://www.oscs1024.com/hd/MPS-2019-7047)|CVE-2019-12384|中危|
|Apache Kafka 权限绕过漏洞|访问控制不当|[MPS-2019-7904](https://www.oscs1024.com/hd/MPS-2019-7904)|CVE-2018-17196|高危|
|FasterXML jackson-databind 反序列化漏洞(ehcache gadget绕过)|动态确定对象属性修改的控制不恰当|[MPS-2019-8717](https://www.oscs1024.com/hd/MPS-2019-8717)|CVE-2019-14379|严重|
|FasterXML jackson-databind 信息泄露漏洞(logback gadget绕过)|反序列化|[MPS-2019-8770](https://www.oscs1024.com/hd/MPS-2019-8770)|CVE-2019-14439|高危|
|FasterXML jackson-databind反序列化漏洞(net.sf.ehcache gadget绕过)|反序列化|[MPS-2020-0063](https://www.oscs1024.com/hd/MPS-2020-0063)|CVE-2019-20330|严重|
|google-oauth-java-client <1.31.0授权不当漏洞|授权检查错误|[MPS-2020-10000](https://www.oscs1024.com/hd/MPS-2020-10000)|CVE-2020-7692|严重|
|FasterXML jackson-databind反序列化漏洞(Anteros-DBCP gadget绕过)|反序列化|[MPS-2020-11987](https://www.oscs1024.com/hd/MPS-2020-11987)|CVE-2020-24616|高危|
|FasterXML jackson-databind 反序列化漏洞(pastdev gadget绕过)|反序列化|[MPS-2020-13151](https://www.oscs1024.com/hd/MPS-2020-13151)|CVE-2020-24750|高危|
|Netty <=4.1.43.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1320](https://www.oscs1024.com/hd/MPS-2020-1320)|CVE-2020-7238|高危|
|Apache Solr 存在远程代码执行漏洞|授权检查错误|[MPS-2020-15175](https://www.oscs1024.com/hd/MPS-2020-15175)|CVE-2020-13957|严重|
|Junit 信息泄露漏洞|不安全的临时文件|[MPS-2020-15183](https://www.oscs1024.com/hd/MPS-2020-15183)|CVE-2020-15250|中危|
|Netty <4.1.44.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1526](https://www.oscs1024.com/hd/MPS-2020-1526)|CVE-2019-20444|严重|
|Netty <4.1.44.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1527](https://www.oscs1024.com/hd/MPS-2020-1527)|CVE-2019-20445|严重|
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
|mysql:mysql-connector-java <8.0.27 存在 XXE 漏洞|XXE|[MPS-2020-38350](https://www.oscs1024.com/hd/MPS-2020-38350)|CVE-2021-2471|中危|
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
|JetBrains Kotlin <1.4.21 不正确的默认权限漏洞|缺省权限不正确|[MPS-2021-1082](https://www.oscs1024.com/hd/MPS-2021-1082)|CVE-2020-29582|中危|
|Netty <4.1.59.Final 存在不安全的临时文件漏洞||[MPS-2021-1580](https://www.oscs1024.com/hd/MPS-2021-1580)|CVE-2021-21290|中危|
|FasterXML jackson-databind 反序列化漏洞(javax.swing gadget绕过)|反序列化|[MPS-2021-1625](https://www.oscs1024.com/hd/MPS-2021-1625)|CVE-2021-20190|高危|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|Google google-oauth-java-client 数据伪造问题漏洞|密码学签名的验证不恰当|[MPS-2021-19070](https://www.oscs1024.com/hd/MPS-2021-19070)|CVE-2021-22573|高危|
|Apache Hadoop YARN 远程代码执行漏洞|代码注入|[MPS-2021-20833](https://www.oscs1024.com/hd/MPS-2021-20833)|CVE-2021-25642|严重|
|netplex json-smart-v  分布式拒绝服务攻击|对因果或异常条件的不恰当检查|[MPS-2021-2102](https://www.oscs1024.com/hd/MPS-2021-2102)|CVE-2021-27568|严重|
|io.netty:netty-codec-http2 <4.1.60.Final 存在 http 请求走私漏洞|HTTP请求走私|[MPS-2021-2435](https://www.oscs1024.com/hd/MPS-2021-2435)|CVE-2021-21295|中危|
|lodash 命令注入漏洞|代码注入|[MPS-2021-2638](https://www.oscs1024.com/hd/MPS-2021-2638)|CVE-2021-23337|高危|
|Apache Parquet 输入验证错误漏洞|拒绝服务|[MPS-2021-32354](https://www.oscs1024.com/hd/MPS-2021-32354)|CVE-2021-41561|高危|
|Oracle MySQL 的 MySQL Connectors 存在授权不当漏洞|授权机制不恰当|[MPS-2021-36587](https://www.oscs1024.com/hd/MPS-2021-36587)|CVE-2022-21363|中危|
|Netty <4.1.71.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2021-36922](https://www.oscs1024.com/hd/MPS-2021-36922)|CVE-2021-43797|中危|
|Apache Log4j JMSAppender反序列化漏洞||[MPS-2021-38359](https://www.oscs1024.com/hd/MPS-2021-38359)|CVE-2021-4104|高危|
|Pac4j 加密问题漏洞|密码学签名的验证不恰当|[MPS-2021-38377](https://www.oscs1024.com/hd/MPS-2021-38377)|CVE-2021-44878|高危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|Bouncy Castle 私钥信息泄露漏洞|竞争条件|[MPS-2021-7064](https://www.oscs1024.com/hd/MPS-2021-7064)|CVE-2020-15522|中危|
|json-smart 存在拒绝服务漏洞|越界写入|[MPS-2021-7737](https://www.oscs1024.com/hd/MPS-2021-7737)|CVE-2021-31684|高危|
|glob-parent < 5.1.2 存在拒绝服务漏洞|拒绝服务|[MPS-2021-7827](https://www.oscs1024.com/hd/MPS-2021-7827)|CVE-2020-28469|高危|
|JDOM 存在 XXE 注入漏洞|XXE|[MPS-2021-8350](https://www.oscs1024.com/hd/MPS-2021-8350)|CVE-2021-33813|高危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9827](https://www.oscs1024.com/hd/MPS-2021-9827)|CVE-2021-36373|中危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9847](https://www.oscs1024.com/hd/MPS-2021-9847)|CVE-2021-36374|中危|
|Digital Bazaar Forge 存在输入验证错误漏洞|跨站重定向|[MPS-2022-0421](https://www.oscs1024.com/hd/MPS-2022-0421)|CVE-2022-0122|中危|
|jnr-posix 存在UAF漏洞|UAF|[MPS-2022-11743](https://www.oscs1024.com/hd/MPS-2022-11743)||低危|
|plexus-utils <3.0.24 路径遍历漏洞|路径遍历|[MPS-2022-11760](https://www.oscs1024.com/hd/MPS-2022-11760)||中危|
|plexus-utils <3.0.24 XXE 漏洞|XPath盲注|[MPS-2022-11786](https://www.oscs1024.com/hd/MPS-2022-11786)||低危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|org.apache.commons:commons-dbcp2 存在信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-12024](https://www.oscs1024.com/hd/MPS-2022-12024)||低危|
|io.netty:netty-codec-http <4.1.53.Final 存在拒绝服务漏洞|拒绝服务|[MPS-2022-12064](https://www.oscs1024.com/hd/MPS-2022-12064)||中危|
|Apache Thrift <0.9.0 拒绝服务漏洞|数字错误|[MPS-2022-12143](https://www.oscs1024.com/hd/MPS-2022-12143)||高危|
|Apache Thrift <0.9.3 SSL DOS 和不安全协商漏洞|拒绝服务|[MPS-2022-12148](https://www.oscs1024.com/hd/MPS-2022-12148)||中危|
|com.nimbusds:oauth2-oidc-sdk 存在XXE漏洞|XXE|[MPS-2022-12182](https://www.oscs1024.com/hd/MPS-2022-12182)||高危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|Apache HttpClient URI解析错误漏洞|相对路径遍历|[MPS-2022-12292](https://www.oscs1024.com/hd/MPS-2022-12292)||中危|
|com.fasterxml.jackson.core:jackson-databind 存在反序列化漏洞|反序列化|[MPS-2022-12433](https://www.oscs1024.com/hd/MPS-2022-12433)||高危|
|FasterXML Jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2022-12500](https://www.oscs1024.com/hd/MPS-2022-12500)||中危|
|d3-color < 3.1.0 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13618](https://www.oscs1024.com/hd/MPS-2022-13618)||中危|
|node-forge <1.0.0 存在原型污染漏洞|原型污染|[MPS-2022-13920](https://www.oscs1024.com/hd/MPS-2022-13920)||中危|
|stylelint <4.0.0存在ReDoS漏洞|ReDoS|[MPS-2022-14060](https://www.oscs1024.com/hd/MPS-2022-14060)||高危|
|Apache Log4j JDBCAppender SQL注入漏洞|SQL注入|[MPS-2022-1444](https://www.oscs1024.com/hd/MPS-2022-1444)|CVE-2022-23305|严重|
|Apache Log4j Chainsaw反序列化漏洞|反序列化|[MPS-2022-1445](https://www.oscs1024.com/hd/MPS-2022-1445)|CVE-2022-23307|高危|
|Apache Log4j 反序列化漏洞|反序列化|[MPS-2022-1446](https://www.oscs1024.com/hd/MPS-2022-1446)|CVE-2022-23302|高危|
|Eclipse Jetty URI注入漏洞|注入|[MPS-2022-18060](https://www.oscs1024.com/hd/MPS-2022-18060)|CVE-2022-2047|低危|
|JetBrains Kotlin <1.6.0 存在锁定不当漏洞|加锁机制不恰当|[MPS-2022-3233](https://www.oscs1024.com/hd/MPS-2022-3233)|CVE-2022-24329|中危|
|node-forge 密码签名验证不当漏洞|密码学签名的验证不恰当|[MPS-2022-3738](https://www.oscs1024.com/hd/MPS-2022-3738)|CVE-2022-24771|高危|
|node-forge 密码签名验证不当漏洞|密码学签名的验证不恰当|[MPS-2022-3739](https://www.oscs1024.com/hd/MPS-2022-3739)|CVE-2022-24772|高危|
|node-forge 密码签名验证不当漏洞|密码学签名的验证不恰当|[MPS-2022-3740](https://www.oscs1024.com/hd/MPS-2022-3740)|CVE-2022-24773|中危|
|Netty 存在信息泄露漏洞||[MPS-2022-3790](https://www.oscs1024.com/hd/MPS-2022-3790)|CVE-2022-24823|中危|
|Express 中的 qs 模块存在原型污染漏洞|原型污染|[MPS-2022-3967](https://www.oscs1024.com/hd/MPS-2022-3967)|CVE-2022-24999|高危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|Bouncy Castle <1.69 认证绕过漏洞|密码学问题|[MPS-2022-54305](https://www.oscs1024.com/hd/MPS-2022-54305)||中危|
|nwsapi 拒绝服务|拒绝服务|[MPS-2022-54623](https://www.oscs1024.com/hd/MPS-2022-54623)||中危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|Jettison <1.5.2 拒绝服务漏洞|拒绝服务|[MPS-2022-57067](https://www.oscs1024.com/hd/MPS-2022-57067)|CVE-2022-40150|高危|
|Jettison <1.5.1 拒绝服务漏洞|越界写入|[MPS-2022-57068](https://www.oscs1024.com/hd/MPS-2022-57068)|CVE-2022-40149|高危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|Netty <4.1.86.Final 存在 CRLF 注入漏洞||[MPS-2022-58552](https://www.oscs1024.com/hd/MPS-2022-58552)|CVE-2022-41915|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|TestNG <7.7.0  存在路径遍历（Zip Slip）漏洞|路径遍历|[MPS-2022-64736](https://www.oscs1024.com/hd/MPS-2022-64736)|CVE-2022-4065|高危|
|Jettison <1.5.2 拒绝服务漏洞|越界写入|[MPS-2022-64973](https://www.oscs1024.com/hd/MPS-2022-64973)|CVE-2022-45685|高危|
|Jettison <1.5.2 拒绝服务漏洞|越界写入|[MPS-2022-64981](https://www.oscs1024.com/hd/MPS-2022-64981)|CVE-2022-45693|高危|
|Tauri 原型污染漏洞|原型污染|[MPS-2022-65568](https://www.oscs1024.com/hd/MPS-2022-65568)|CVE-2022-46175|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Eclipse Jetty 资源管理错误漏洞|拒绝服务|[MPS-2023-4997](https://www.oscs1024.com/hd/MPS-2023-4997)|CVE-2023-26048|中危|
|Eclipse Jetty 信息泄露漏洞|XSS|[MPS-2023-4998](https://www.oscs1024.com/hd/MPS-2023-4998)|CVE-2023-26049|中危|
|netplex json-smart 安全漏洞|未经控制的递归|[MPS-2023-7760](https://www.oscs1024.com/hd/MPS-2023-7760)|CVE-2023-1370|高危|
|Jettison 安全漏洞|未经控制的递归|[MPS-2023-8270](https://www.oscs1024.com/hd/MPS-2023-8270)|CVE-2023-1436|高危|
|jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2023-8438](https://www.oscs1024.com/hd/MPS-2023-8438)|CVE-2021-46877|中危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.apache.zookeeper:zookeeper|3.4.6|3.5.5|间接依赖|强烈建议修复|C:0|H:2|M:1|L:0|
|io.netty:netty|3.10.5.Final||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.codehaus.plexus:plexus-utils|3.0.15|3.0.24|间接依赖|建议修复|C:1|H:0|M:1|L:1|
|org.pac4j:pac4j-core|3.8.3|5.3.1|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.15.2||间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.9.6|2.14.0-rc1|间接依赖|建议修复|C:21|H:36|M:5|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.10.0.pr1|2.14.0-rc1|间接依赖|建议修复|C:0|H:1|M:5|L:0|
|com.google.oauth-client:google-oauth-client|1.26.0|1.33.3|间接依赖|建议修复|C:1|H:1|M:0|L:0|
|com.google.protobuf:protobuf-java|2.4.1|3.21.7|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.10.3|2.14.0-rc1|间接依赖|建议修复|C:0|H:2|M:5|L:0|
|org.eclipse.jetty:jetty-server|9.4.51.v20230217|12.0.0.beta0|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.yaml:snakeyaml|1.6|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|express|4.17.1|4.17.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.squareup.okhttp:okhttp|1.0.2|2.7.4|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.apache.solr:solr-solrj|7.7.1|8.6.3|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13||间接依赖|建议修复|C:1|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.21|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|io.netty:netty|3.10.6.Final||直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.google.protobuf:protobuf-java|2.5.0|3.21.7|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|org.pac4j:pac4j-oidc|3.8.3|5.2.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.parquet:parquet-format-structures|1.12.0|1.12.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|stylelint|13.12.0|14.0.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.xerial.snappy:snappy-java|1.0.4.1|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|io.netty:netty|3.7.0.Final|3.10.3.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|json5|1.0.1|2.2.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.xerial.snappy:snappy-java|1.1.7.1|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|com.squareup.okio:okio|2.8.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.xerial.snappy:snappy-java|1.1.8|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|node-forge|0.10.0|1.3.0|间接依赖|建议修复|C:0|H:2|M:3|L:0|
|log4j:log4j|1.2.16||间接依赖|建议修复|C:2|H:3|M:0|L:1|
|net.minidev:json-smart|2.3|2.4.9|间接依赖|建议修复|C:1|H:2|M:0|L:0|
|log4j:log4j|1.2.17||间接依赖|建议修复|C:2|H:3|M:0|L:1|
|org.xerial.snappy:snappy-java|1.1.8.2|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.12.7.1|2.14.0-rc1|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.12.7|2.14.0-rc1|直接依赖|建议修复|C:0|H:0|M:3|L:0|
|com.squareup.okio:okio|1.17.2|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.codehaus.jettison:jettison|1.3.1|1.5.4|间接依赖|建议修复|C:0|H:5|M:0|L:0|
|io.netty:netty-codec-http|4.1.29.Final|4.1.86.final|间接依赖|建议修复|C:2|H:2|M:5|L:0|
|org.codehaus.jettison:jettison|1.1|1.5.4|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|org.apache.commons:commons-compress|1.20|1.21|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|org.yaml:snakeyaml|1.27|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|glob-parent|3.1.0|6.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-http|9.3.20.v20170531|11.0.10|间接依赖|建议修复|C:2|H:1|M:0|L:1|
|com.nimbusds:oauth2-oidc-sdk|6.5|9.3.1|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.94.Final|4.1.94.final|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.google.protobuf:protobuf-java|3.14.0|3.21.7|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.google.protobuf:protobuf-java|3.11.4|3.21.7|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.apache.thrift:libthrift|0.6.1|0.12.0|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|com.squareup.okio:okio|1.15.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|commons-beanutils:commons-beanutils|1.9.3|1.9.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.zookeeper:zookeeper|3.5.3-beta|3.5.5|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|net.minidev:json-smart|2.4.7|2.4.9|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|mysql:mysql-connector-java|5.1.49|8.0.28|直接依赖|建议修复|C:0|H:1|M:3|L:0|
|org.apache.hadoop:hadoop-yarn-server-resourcemanager|3.1.0|3.3.4|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|io.netty:netty-transport-native-epoll|4.1.46.Final|4.1.59.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|19.0|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|org.apache.httpcomponents:httpclient|4.5.5|4.5.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.bouncycastle:bcprov-jdk15on|1.70||直接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.code.gson:gson|2.2.4|2.8.9|直接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.httpcomponents:httpclient|4.4.1|4.5.13|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.apache.zookeeper:zookeeper|3.4.13|3.5.5|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.bouncycastle:bcprov-jdk15on|1.64|1.69|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|nwsapi|2.2.0|2.2.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|31.1-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.ant:ant|1.10.3|1.10.11|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|org.testng:testng|7.3.0|7.7.0|直接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.httpcomponents:httpclient|4.5.3|4.5.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|5.7.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.jetbrains.kotlin:kotlin-stdlib|1.4.10|1.6.0|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|commons-io:commons-io|2.5|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.thrift:libthrift|0.9.3|0.12.0|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.guava:guava|26.0-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:1|
|org.apache.httpcomponents:httpclient|4.5.2|4.5.13|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.github.jnr:jnr-posix|3.0.61|3.1.8|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|junit:junit|4.12|4.13.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|25.1-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:1|
|org.eclipse.jetty:jetty-http|9.4.51.v20230217|11.0.10|直接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.apache.commons:commons-dbcp2|2.0.1|2.9.0|直接依赖|可选修复|C:0|H:0|M:0|L:1|
|commons-codec:commons-codec|1.11|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.jdom:jdom2|2.0.6|2.0.6.1|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.guava:guava|20.0|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|com.google.code.gson:gson|2.8.6|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.guava:guava|14.0.1|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|com.google.code.gson:gson|2.3.1|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.kafka:kafka_2.11|2.0.0|2.1.1|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|commons-codec:commons-codec|1.10|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|lodash.template|4.5.0||间接依赖|可选修复|C:0|H:1|M:0|L:0|
|commons-codec:commons-codec|1.9|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|io.netty:netty-common|4.1.17.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|io.netty:netty-transport-native-epoll|4.1.29.Final|4.1.59.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|d3-color|2.0.0|3.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.ant:ant|1.9.1|1.10.11|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|org.apache.derby:derby|10.14.1.0|10.14.2.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-io:commons-io|2.4|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.commons:commons-dbcp2|2.6.0|2.9.0|间接依赖|可选修复|C:0|H:0|M:0|L:1|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|989|Low|
|Apache-2.0|604|Low|
|自定义许可证|62|Low|
|EPL-1.0|26|Low|
|GPL-2.0|1|Medium|
|MPL-2.0|2|Low|
|ISC|56|Low|
|CC0-1.0|22|Low|
|CDDL-1.1|14|Low|
|BSD-3-Clause|53|Low|
|LGPL-2.1-or-later|2|Low|
|BSD-2-Clause|25|Low|
|LGPL-2.1|7|Medium|
|EPL-2.0|5|Low|
|0BSD|1|Low|
|WTFPL|1|Low|
|CC-BY-4.0|1|Low|
|CC-BY-3.0|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|babel-preset-current-node-syntax|1.0.1|间接依赖|npm|
|io.fabric8:kubernetes-model-flowcontrol|6.7.2|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.2|间接依赖|maven|
|io.tesla.aether:tesla-aether|0.0.5|直接依赖|maven|
|com.rabbitmq:amqp-client|5.17.0|间接依赖|maven|
|which-module|2.0.0|间接依赖|npm|
|commons-lang:commons-lang|2.4|间接依赖|maven|
|@types/d3-time|2.1.1|间接依赖|npm|
|junit:junit|4.4|间接依赖|maven|
|async|2.6.4|间接依赖|npm|
|indexes-of|1.0.1|间接依赖|npm|
|websocket-driver|0.7.4|间接依赖|npm|
|style-search|0.1.0|间接依赖|npm|
|@babel/helper-function-name|7.22.5|间接依赖|npm|
|header-case|2.0.4|间接依赖|npm|
|functions-have-names|1.2.3|间接依赖|npm|
|react-table|6.10.3|直接依赖|npm|
|com.github.ben-manes.caffeine:caffeine|2.8.0|直接依赖|maven|
|remove-trailing-separator|1.1.0|直接依赖|npm|
|yaml|1.10.2|间接依赖|npm|
|ch.qos.reload4j:reload4j|1.2.22|间接依赖|maven|
|@babel/plugin-transform-regenerator|7.13.15|间接依赖|npm|
|string-length|4.0.2|间接依赖|npm|
|css-prefers-color-scheme|3.1.1|间接依赖|npm|
|com.github.rvesse:airline|2.8.4|直接依赖|maven|
|fresh|0.5.2|间接依赖|npm|
|v8-to-istanbul|8.1.1|间接依赖|npm|
|com.google.uzaygezen:uzaygezen-core|0.2|间接依赖|maven|
|strip-final-newline|2.0.0|直接依赖|npm|
|@blueprintjs/colors|4.2.1|间接依赖|npm|
|io.kubernetes:client-java-proto|11.0.4|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|直接依赖|maven|
|@testing-library/react|14.0.0|直接依赖|npm|
|multimap|1.1.0|间接依赖|npm|
|snapdragon-node|2.1.1|间接依赖|npm|
|io.dropwizard.metrics:metrics-core|4.2.19|直接依赖|maven|
|requires-port|1.0.0|间接依赖|npm|
|reusify|1.0.4|间接依赖|npm|
|@types/unist|2.0.3|间接依赖|npm|
|@babel/plugin-transform-property-literals|7.12.13|间接依赖|npm|
|methods|1.1.2|间接依赖|npm|
|@babel/plugin-syntax-numeric-separator|7.10.4|间接依赖|npm|
|symbol-tree|3.2.4|间接依赖|npm|
|javax.xml.bind:jaxb-api|2.2.11|间接依赖|maven|
|fast-levenshtein|2.0.6|间接依赖|npm|
|webpack-cli|4.6.0|直接依赖|npm|
|rw|1.3.3|间接依赖|npm|
|d3-time-format|2.2.1|间接依赖|npm|
|org.ow2.asm:asm-tree|7.1|间接依赖|maven|
|jest-get-type|27.5.0|间接依赖|npm|
|@types/prop-types|15.7.3|间接依赖|npm|
|acorn-walk|8.2.0|间接依赖|npm|
|com.google.inject.extensions:guice-servlet|4.0|间接依赖|maven|
|org.apache.druid:druid-processing|28.0.0-SNAPSHOT|直接依赖|maven|
|path-is-inside|1.0.2|间接依赖|npm|
|osenv|0.1.5|间接依赖|npm|
|@babel/generator|7.22.10|间接依赖|npm|
|acorn|8.10.0|间接依赖|npm|
|require-from-string|2.0.2|直接依赖|npm|
|com.fasterxml.jackson.core:jackson-annotations|2.12.7|直接依赖|maven|
|ignore-walk|3.0.3|间接依赖|npm|
|com.fasterxml.jackson.core:jackson-annotations|2.15.2|间接依赖|maven|
|y18n|4.0.3|间接依赖|npm|
|natural-compare|1.4.0|间接依赖|npm|
|whatwg-mimetype|2.3.0|间接依赖|npm|
|@babel/plugin-proposal-optional-catch-binding|7.14.2|间接依赖|npm|
|emittery|0.8.1|间接依赖|npm|
|jest-regex-util|27.5.0|间接依赖|npm|
|is-plain-object|2.0.4|间接依赖|npm|
|postcss-page-break|2.0.0|间接依赖|npm|
|original|1.0.2|间接依赖|npm|
|@jest/reporters|27.5.0|间接依赖|npm|
|http-errors|1.7.2|间接依赖|npm|
|org.apache.maven:maven-aether-provider|3.1.1|间接依赖|maven|
|ini|1.3.8|间接依赖|npm|
|buffer-indexof|1.1.1|间接依赖|npm|
|com.google.code.gson:gson|2.9.0|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-registry|3.1.0|间接依赖|maven|
|bonjour|3.5.0|间接依赖|npm|
|org.antlr:antlr|3.2|间接依赖|maven|
|postcss-preset-env|6.7.0|直接依赖|npm|
|io.fabric8:kubernetes-model-certificates|6.7.2|间接依赖|maven|
|path-case|3.0.4|间接依赖|npm|
|org.apache.twill:twill-discovery-core|0.6.0-incubating|间接依赖|maven|
|callsites|3.1.0|间接依赖|npm|
|io.prometheus:simpleclient_httpserver|0.16.0|直接依赖|maven|
|prettier|2.8.4|直接依赖|npm|
|org.apache.kerby:token-provider|1.0.1|间接依赖|maven|
|org.apache.hadoop:hadoop-auth|3.3.6|直接依赖|maven|
|spdx-correct|3.1.0|间接依赖|npm|
|javax.el:javax.el-api|3.0.0|直接依赖|maven|
|@types/d3-scale|3.3.2|直接依赖|npm|
|@babel/plugin-proposal-class-static-block|7.14.3|间接依赖|npm|
|parse-json|5.2.0|间接依赖|npm|
|com.jayway.jsonpath:json-path|2.7.0|间接依赖|maven|
|pump|3.0.0|间接依赖|npm|
|merge-stream|2.0.0|间接依赖|npm|
|acorn-jsx|5.3.2|间接依赖|npm|
|com.lmax:disruptor|3.3.6|直接依赖|maven|
|prr|1.0.1|间接依赖|npm|
|@emotion/memoize|0.7.4|间接依赖|npm|
|collection-visit|1.0.0|间接依赖|npm|
|@babel/helper-remap-async-to-generator|7.13.0|间接依赖|npm|
|org.apache.hadoop:hadoop-yarn-server-resourcemanager|3.1.0|间接依赖|maven|
|@babel/helper-skip-transparent-expression-wrappers|7.12.1|间接依赖|npm|
|com.squareup.okhttp3:okhttp|3.14.9|间接依赖|maven|
|@jridgewell/set-array|1.1.2|间接依赖|npm|
|utils-merge|1.0.1|间接依赖|npm|
|io.fabric8:kubernetes-model-apiextensions|6.7.2|间接依赖|maven|
|toggle-selection|1.0.6|间接依赖|npm|
|content-type|1.0.4|间接依赖|npm|
|prelude-ls|1.2.1|间接依赖|npm|
|handle-thing|2.0.1|间接依赖|npm|
|tiny-invariant|1.0.6|间接依赖|npm|
|junit:junit|3.8.1|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.0|间接依赖|maven|
|spdx-compare|1.0.0|间接依赖|npm|
|@babel/plugin-transform-parameters|7.14.2|间接依赖|npm|
|org.mockito:mockito-core|2.28.2|间接依赖|maven|
|class-utils|0.3.6|间接依赖|npm|
|atob|2.1.2|间接依赖|npm|
|com.google.inject:guice|3.0|间接依赖|maven|
|on-finished|2.3.0|间接依赖|npm|
|nanoid|3.3.4|间接依赖|npm|
|@blueprintjs/select|4.9.22|间接依赖|npm|
|org.yaml:snakeyaml|1.27|间接依赖|maven|
|@eslint/eslintrc|2.0.1|间接依赖|npm|
|babel-plugin-syntax-jsx|6.18.0|间接依赖|npm|
|xml-name-validator|3.0.0|间接依赖|npm|
|com.nimbusds:nimbus-jose-jwt|7.9|直接依赖|maven|
|debuglog|1.0.1|间接依赖|npm|
|@babel/plugin-syntax-object-rest-spread|7.8.3|间接依赖|npm|
|log4j:log4j|1.2.16|间接依赖|maven|
|use-sync-external-store|1.2.0|间接依赖|npm|
|io.prometheus:simpleclient_tracer_otel_agent|0.16.0|间接依赖|maven|
|net.java.dev.jna:jna|5.13.0|直接依赖|maven|
|org.apache.derby:derbynet|10.14.2.0|直接依赖|maven|
|is-core-module|2.10.0|间接依赖|npm|
|wrap-ansi|5.1.0|间接依赖|npm|
|@types/babel__generator|7.6.4|间接依赖|npm|
|postcss-custom-properties|8.0.11|间接依赖|npm|
|harmony-reflect|1.6.1|间接依赖|npm|
|@types/istanbul-lib-report|1.1.1|直接依赖|npm|
|com.github.seancfoley:ipaddress|5.3.4|直接依赖|maven|
|terser|5.19.2|间接依赖|npm|
|hosted-git-info|2.8.9|间接依赖|npm|
|is-buffer|2.0.5|间接依赖|npm|
|@babel/plugin-transform-modules-systemjs|7.13.8|间接依赖|npm|
|strip-json-comments|3.1.1|间接依赖|npm|
|w3c-hr-time|1.0.2|间接依赖|npm|
|call-bind|1.0.2|间接依赖|npm|
|org.eclipse.jetty:jetty-util-ajax|9.4.51.v20230217|间接依赖|maven|
|com.datadoghq:java-dogstatsd-client|4.0.0|直接依赖|maven|
|collect-v8-coverage|1.0.1|间接依赖|npm|
|p-retry|3.0.1|间接依赖|npm|
|cssesc|3.0.0|间接依赖|npm|
|terminal-link|2.1.1|间接依赖|npm|
|com.sun.jersey:jersey-json|1.19|间接依赖|maven|
|org.scala-lang:scala-library|2.11.12|间接依赖|maven|
|jest-resolve-dependencies|27.5.0|间接依赖|npm|
|jest-runtime|27.5.0|间接依赖|npm|
|com.fasterxml.jackson.datatype:jackson-datatype-guava|2.12.7|直接依赖|maven|
|org.apache.derby:derby|10.14.2.0|直接依赖|maven|
|is-unicode-supported|0.1.0|间接依赖|npm|
|lower-case|2.0.2|间接依赖|npm|
|org.apache.parquet:parquet-avro|1.12.0|直接依赖|maven|
|@types/d3-selection|2.0.1|间接依赖|npm|
|io.fabric8:kubernetes-model-gatewayapi|6.7.2|间接依赖|maven|
|org.codehaus.plexus:plexus-utils|3.0.15|间接依赖|maven|
|@babel/helpers|7.22.11|间接依赖|npm|
|@babel/plugin-proposal-private-methods|7.13.0|间接依赖|npm|
|hoist-non-react-statics|3.3.0|间接依赖|npm|
|typedarray-to-buffer|3.1.5|间接依赖|npm|
|@babel/plugin-proposal-object-rest-spread|7.14.4|间接依赖|npm|
|com.microsoft.sqlserver:mssql-jdbc|6.2.1.jre7|间接依赖|maven|
|is-fullwidth-code-point|2.0.0|间接依赖|npm|
|org.xerial.snappy:snappy-java|1.1.8.2|间接依赖|maven|
|com.google.guava:guava|20.0|间接依赖|maven|
|update-browserslist-db|1.0.11|间接依赖|npm|
|@babel/plugin-proposal-class-properties|7.13.0|间接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|to-regex-range|2.1.1|间接依赖|npm|
|safe-regex-test|1.0.0|间接依赖|npm|
|memoize-one|5.1.1|间接依赖|npm|
|com.github.luben:zstd-jni|1.4.9-1|间接依赖|maven|
|unicode-match-property-ecmascript|1.0.4|间接依赖|npm|
|io.netty:netty-codec-dns|4.1.29.Final|间接依赖|maven|
|echarts|5.4.2|直接依赖|npm|
|postcss-logical|3.0.0|间接依赖|npm|
|io.prometheus:simpleclient_common|0.16.0|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.94.Final|间接依赖|maven|
|path-to-regexp|1.7.0|间接依赖|npm|
|org.checkerframework:checker-qual|3.12.0|间接依赖|maven|
|io.fabric8:kubernetes-model-metrics|6.7.2|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.9.0|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|diff-sequences|27.5.0|间接依赖|npm|
|@stylelint/postcss-css-in-js|0.37.2|间接依赖|npm|
|postcss-color-gray|5.0.0|间接依赖|npm|
|@types/enzyme|3.10.3|间接依赖|npm|
|@istanbuljs/schema|0.1.3|间接依赖|npm|
|net.java.dev.jna:jna|5.2.0|间接依赖|maven|
|org.apache.hive:hive-upgrade-acid|3.1.3|间接依赖|maven|
|@types/lodash.escape|4.0.6|直接依赖|npm|
|com.github.stephenc:jamm|0.2.5|间接依赖|maven|
|io.fabric8:kubernetes-model-policy|6.7.2|间接依赖|maven|
|commons-logging:commons-logging|1.1.1|间接依赖|maven|
|require-main-filename|2.0.0|间接依赖|npm|
|com.google.protobuf:protobuf-java|3.11.4|间接依赖|maven|
|lodash.debounce|4.0.8|间接依赖|npm|
|org.apache.druid.extensions:simple-client-sslcontext|28.0.0-SNAPSHOT|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.11|直接依赖|maven|
|net.java.dev.jna:jna-platform|5.2.0|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|3.3.6|直接依赖|maven|
|get-value|2.0.6|间接依赖|npm|
|@types/glob|7.1.3|间接依赖|npm|
|org.apache.logging.log4j:log4j-slf4j-impl|2.17.1|间接依赖|maven|
|pinkie|2.0.4|间接依赖|npm|
|html-tags|3.2.0|间接依赖|npm|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.4.10|间接依赖|maven|
|com.jolbox:bonecp|0.8.0.RELEASE|间接依赖|maven|
|pinkie-promise|2.0.1|间接依赖|npm|
|object-inspect|1.12.3|间接依赖|npm|
|shebang-regex|1.0.0|间接依赖|npm|
|camel-case|4.1.2|间接依赖|npm|
|esrecurse|4.3.0|间接依赖|npm|
|io.opentelemetry:opentelemetry-sdk-common|1.7.0|直接依赖|maven|
|@babel/plugin-transform-modules-umd|7.14.0|间接依赖|npm|
|org.apache.derby:derby|10.14.1.0|间接依赖|maven|
|object-is|1.1.5|间接依赖|npm|
|org.jdbi:jdbi|2.63.1|直接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.3|间接依赖|maven|
|com.squareup.okhttp3:okhttp|4.9.3|间接依赖|maven|
|io.fabric8:kubernetes-model-apps|6.7.2|间接依赖|maven|
|io.kubernetes:client-java-api|11.0.4|直接依赖|maven|
|@nodelib/fs.walk|1.2.8|间接依赖|npm|
|grapheme-splitter|1.0.4|间接依赖|npm|
|org.apache.hadoop:hadoop-yarn-server-common|3.1.0|间接依赖|maven|
|org.apache.kerby:kerb-identity|1.0.1|间接依赖|maven|
|org.ow2.asm:asm-commons|7.1|间接依赖|maven|
|watchpack|2.4.0|间接依赖|npm|
|clone-regexp|2.2.0|间接依赖|npm|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.12.7|间接依赖|maven|
|@babel/preset-env|7.14.4|直接依赖|npm|
|postcss-syntax|0.36.2|间接依赖|npm|
|builtin-modules|3.2.0|间接依赖|npm|
|@babel/plugin-transform-named-capturing-groups-regex|7.12.13|间接依赖|npm|
|org.apache.druid.extensions:druid-basic-security|28.0.0-SNAPSHOT|直接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|@typescript-eslint/utils|5.51.0|间接依赖|npm|
|component-emitter|1.3.0|间接依赖|npm|
|org.apache.kerby:kerb-crypto|1.0.1|间接依赖|maven|
|@babel/plugin-transform-modules-amd|7.14.2|间接依赖|npm|
|ansi-colors|4.1.1|间接依赖|npm|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|word-wrap|1.2.4|间接依赖|npm|
|org.apache.jclouds:jclouds-core|2.5.0|直接依赖|maven|
|ts-node|10.9.1|直接依赖|npm|
|set-value|2.0.1|间接依赖|npm|
|@webassemblyjs/wasm-gen|1.11.6|间接依赖|npm|
|@webpack-cli/serve|1.3.1|间接依赖|npm|
|jest-resolve|27.5.0|间接依赖|npm|
|@babel/plugin-transform-block-scoped-functions|7.12.13|间接依赖|npm|
|org.xerial.snappy:snappy-java|1.1.8|间接依赖|maven|
|@types/classnames|2.2.9|直接依赖|npm|
|@juggle/resize-observer|3.4.0|间接依赖|npm|
|org.codehaus.jackson:jackson-jaxrs|1.9.2|间接依赖|maven|
|domexception|2.0.1|间接依赖|npm|
|net.thisptr:jackson-jq|0.0.10|直接依赖|maven|
|org.apache.derby:derbyclient|10.14.2.0|直接依赖|maven|
|com.google.guava:guava|26.0-jre|间接依赖|maven|
|internmap|1.0.1|间接依赖|npm|
|import-fresh|3.3.0|间接依赖|npm|
|array-buffer-byte-length|1.0.0|间接依赖|npm|
|is-regexp|2.1.0|间接依赖|npm|
|emoji-regex|8.0.0|间接依赖|npm|
|org.apache.hadoop:hadoop-yarn-api|3.3.6|间接依赖|maven|
|org.apache.hive.shims:hive-shims-scheduler|3.1.3|间接依赖|maven|
|org.yaml:snakeyaml|1.6|间接依赖|maven|
|get-intrinsic|1.2.0|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|is-extendable|0.1.1|间接依赖|npm|
|fsevents|1.2.13|间接依赖|npm|
|io.opentelemetry:opentelemetry-sdk|1.7.0|直接依赖|maven|
|org.asynchttpclient:async-http-client|2.5.3|直接依赖|maven|
|@babel/helper-create-regexp-features-plugin|7.14.3|间接依赖|npm|
|@typescript-eslint/types|5.51.0|间接依赖|npm|
|jsx-ast-utils|3.2.1|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|fastest-levenshtein|1.0.16|间接依赖|npm|
|org.apache.avro:avro|1.11.1|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.30|间接依赖|maven|
|jest-matcher-utils|27.5.0|间接依赖|npm|
|fastq|1.11.0|间接依赖|npm|
|com.github.ben-manes.caffeine:caffeine|2.8.8|间接依赖|maven|
|@jridgewell/gen-mapping|0.3.3|间接依赖|npm|
|@typescript-eslint/visitor-keys|5.51.0|间接依赖|npm|
|org.mapdb:mapdb|1.0.8|直接依赖|maven|
|arrify|1.0.1|间接依赖|npm|
|@babel/plugin-syntax-nullish-coalescing-operator|7.8.3|间接依赖|npm|
|org.datanucleus:datanucleus-core|4.1.17|间接依赖|maven|
|delayed-stream|1.0.0|间接依赖|npm|
|commons-io:commons-io|2.8.0|间接依赖|maven|
|cross-spawn|6.0.5|间接依赖|npm|
|postcss-place|4.0.1|间接依赖|npm|
|@istanbuljs/load-nyc-config|1.1.0|间接依赖|npm|
|is-bigint|1.0.4|间接依赖|npm|
|babel-loader|8.2.2|直接依赖|npm|
|arr-union|3.1.0|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|com.google.errorprone:error_prone_annotations|2.4.0|间接依赖|maven|
|tapable|2.2.1|间接依赖|npm|
|expect|27.5.0|间接依赖|npm|
|https-proxy-agent|5.0.0|间接依赖|npm|
|snapdragon|0.8.2|间接依赖|npm|
|@csstools/convert-colors|1.4.0|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|yocto-queue|0.1.0|直接依赖|npm|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13|间接依赖|maven|
|org.jacoco:org.jacoco.agent|0.8.5|间接依赖|maven|
|jsdom|16.7.0|间接依赖|npm|
|@babel/helper-string-parser|7.22.5|间接依赖|npm|
|balanced-match|1.0.0|间接依赖|npm|
|regexpp|3.2.0|间接依赖|npm|
|regex-not|1.0.2|间接依赖|npm|
|tsutils|3.21.0|间接依赖|npm|
|io.fabric8:kubernetes-model-networking|6.7.2|间接依赖|maven|
|org.jvnet.staxex:stax-ex|1.8|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.21.9|间接依赖|maven|
|p-limit|2.2.0|间接依赖|npm|
|org.apache.twill:twill-core|0.6.0-incubating|间接依赖|maven|
|create-require|1.1.1|间接依赖|npm|
|faye-websocket|0.11.3|间接依赖|npm|
|@babel/template|7.22.5|间接依赖|npm|
|stylelint|13.12.0|直接依赖|npm|
|mkdirp|0.5.5|间接依赖|npm|
|org.apache.commons:commons-lang3|3.8|间接依赖|maven|
|detect-node|2.0.5|间接依赖|npm|
|postcss-scss|2.1.1|间接依赖|npm|
|side-channel|1.0.4|间接依赖|npm|
|@typescript-eslint/eslint-plugin|5.51.0|直接依赖|npm|
|org.ow2.asm:asm|7.1|间接依赖|maven|
|stop-iteration-iterator|1.0.0|间接依赖|npm|
|@babel/plugin-transform-arrow-functions|7.13.0|间接依赖|npm|
|org.ow2.asm:asm-analysis|7.1|间接依赖|maven|
|@typescript-eslint/type-utils|5.51.0|间接依赖|npm|
|is-number-object|1.0.7|间接依赖|npm|
|net.spy:spymemcached|2.12.3|直接依赖|maven|
|org.apache.kafka:kafka-clients|3.5.1|直接依赖|maven|
|signal-exit|3.0.7|间接依赖|npm|
|org.apache.httpcomponents:httpclient|4.4.1|间接依赖|maven|
|isexe|2.0.0|间接依赖|npm|
|org.locationtech.proj4j:proj4j|1.2.2|间接依赖|maven|
|org.apache.httpcomponents.client5:httpclient5|5.1.3|间接依赖|maven|
|@types/eslint-scope|3.7.4|间接依赖|npm|
|org.eclipse.jetty:jetty-server|9.4.51.v20230217|直接依赖|maven|
|resolve-url|0.2.1|间接依赖|npm|
|binary-extensions|1.13.1|间接依赖|npm|
|make-error|1.3.5|间接依赖|npm|
|portfinder|1.0.28|间接依赖|npm|
|org.apache.kerby:kerby-xdr|1.0.1|间接依赖|maven|
|org.apache.orc:orc-mapreduce|1.7.6|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-web-proxy|3.1.0|间接依赖|maven|
|org.asynchttpclient:async-http-client-netty-utils|2.5.3|间接依赖|maven|
|totalist|1.1.0|间接依赖|npm|
|org.apache.kerby:kerby-pkix|1.0.1|间接依赖|maven|
|org.eclipse.jetty:jetty-http|9.4.51.v20230217|直接依赖|maven|
|zustand|4.3.2|间接依赖|npm|
|io.fabric8:kubernetes-model-admissionregistration|6.7.2|间接依赖|maven|
|execa|1.0.0|间接依赖|npm|
|org.apache.druid.extensions:druid-histogram|28.0.0-SNAPSHOT|直接依赖|maven|
|@babel/plugin-transform-member-expression-literals|7.12.13|间接依赖|npm|
|com.thoughtworks.paranamer:paranamer|2.3|间接依赖|maven|
|io.grpc:grpc-context|1.57.2|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.15.2|间接依赖|maven|
|@babel/plugin-syntax-optional-catch-binding|7.8.3|间接依赖|npm|
|is-binary-path|1.0.1|间接依赖|npm|
|upper-case|2.0.2|间接依赖|npm|
|com.nimbusds:nimbus-jose-jwt|9.8.1|间接依赖|maven|
|react-day-picker|7.4.9|间接依赖|npm|
|io.fabric8:kubernetes-model-common|6.7.2|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.5|间接依赖|maven|
|semver|5.7.0|间接依赖|npm|
|parse-entities|2.0.0|间接依赖|npm|
|@webassemblyjs/wast-printer|1.11.6|间接依赖|npm|
|zrender|5.4.3|间接依赖|npm|
|react-splitter-layout|4.0.0|直接依赖|npm|
|css-loader|5.2.1|直接依赖|npm|
|com.squareup.okio:okio|2.8.0|间接依赖|maven|
|org.apache.kerby:kerb-server|1.0.1|间接依赖|maven|
|schema-utils|2.7.1|间接依赖|npm|
|tough-cookie|4.1.3|间接依赖|npm|
|prop-types|15.7.2|间接依赖|npm|
|org.apache.hive:hive-common|3.1.3|间接依赖|maven|
|com.google.code.gson:gson|2.2.2|间接依赖|maven|
|postcss-focus-within|3.0.0|间接依赖|npm|
|capital-case|1.0.4|间接依赖|npm|
|com.google.code.gson:gson|2.3.1|间接依赖|maven|
|@types/estree|1.0.1|间接依赖|npm|
|org.apache.commons:commons-compress|1.21|间接依赖|maven|
|get-symbol-description|1.0.0|间接依赖|npm|
|org.eclipse.jetty:jetty-util|9.4.51.v20230217|直接依赖|maven|
|org.codehaus.plexus:plexus-utils|3.1.0|间接依赖|maven|
|npm-run-path|2.0.2|间接依赖|npm|
|io.opentracing:opentracing-api|0.33.0|间接依赖|maven|
|com.github.rvesse:airline-io|2.8.4|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.5.10|直接依赖|maven|
|p-map|2.1.0|间接依赖|npm|
|duplexer|0.1.2|间接依赖|npm|
|scheduler|0.23.0|间接依赖|npm|
|@babel/helper-validator-identifier|7.22.5|间接依赖|npm|
|org.apache.hive:hive-metastore|3.1.3|直接依赖|maven|
|lines-and-columns|1.1.6|间接依赖|npm|
|es-get-iterator|1.1.3|直接依赖|npm|
|org.checkerframework:checker-qual|3.10.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.10.3|间接依赖|maven|
|@types/history|4.7.11|间接依赖|npm|
|com.squareup.okio:okio|1.15.0|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.24|间接依赖|maven|
|com.github.docker-java:docker-java-core|3.2.13|直接依赖|maven|
|postcss-replace-overflow-wrap|3.0.0|间接依赖|npm|
|org.schemarepo:schema-repo-avro|0.1.3|直接依赖|maven|
|org.apache.hive:hive-shims|3.1.3|间接依赖|maven|
|http-proxy-agent|4.0.1|间接依赖|npm|
|commons-lang:commons-lang|2.6|直接依赖|maven|
|html-entities|1.4.0|间接依赖|npm|
|com.github.docker-java:docker-java-api|3.2.13|直接依赖|maven|
|sprintf-js|1.0.3|间接依赖|npm|
|io.dropwizard.metrics:metrics-jmx|4.2.19|直接依赖|maven|
|net.minidev:accessors-smart|2.4.7|间接依赖|maven|
|org.noggit:noggit|0.8|间接依赖|maven|
|sockjs-client|1.5.1|间接依赖|npm|
|estraverse|4.3.0|间接依赖|npm|
|org.apache.curator:curator-framework|4.0.0|间接依赖|maven|
|decode-uri-component|0.2.2|间接依赖|npm|
|org.apache.parquet:parquet-format-structures|1.12.0|间接依赖|maven|
|klona|2.0.4|间接依赖|npm|
|@emotion/serialize|0.11.16|间接依赖|npm|
|@types/dom4|2.0.2|间接依赖|npm|
|com.google.oauth-client:google-oauth-client|1.26.0|间接依赖|maven|
|quick-lru|4.0.1|间接依赖|npm|
|mysql:mysql-connector-java|5.1.49|直接依赖|maven|
|io.grpc:grpc-core|1.57.2|间接依赖|maven|
|@bcoe/v8-coverage|0.2.3|间接依赖|npm|
|pirates|4.0.5|间接依赖|npm|
|jest-pnp-resolver|1.2.2|间接依赖|npm|
|org.apache.logging.log4j:log4j-1.2-api|2.17.1|间接依赖|maven|
|com.sun.activation:javax.activation|1.2.0|间接依赖|maven|
|postcss-double-position-gradients|1.0.0|间接依赖|npm|
|@types/prettier|2.4.3|间接依赖|npm|
|io.netty:netty-handler|4.1.94.Final|直接依赖|maven|
|org.apache.hadoop.thirdparty:hadoop-shaded-guava|1.1.1|间接依赖|maven|
|@jest/core|27.5.0|间接依赖|npm|
|org.apache.httpcomponents:httpclient|4.5.13|直接依赖|maven|
|unset-value|1.0.0|间接依赖|npm|
|org.datanucleus:datanucleus-api-jdo|4.2.4|间接依赖|maven|
|org.apache.druid.extensions.contrib:materialized-view-maintenance|28.0.0-SNAPSHOT|直接依赖|maven|
|d3-axis|2.1.0|直接依赖|npm|
|com.101tec:zkclient|0.10|间接依赖|maven|
|jest-config|27.5.0|间接依赖|npm|
|com.google.http-client:google-http-client|1.26.0|直接依赖|maven|
|jest-mock|27.5.0|间接依赖|npm|
|@webpack-cli/info|1.2.3|间接依赖|npm|
|react-transition-group|4.4.5|间接依赖|npm|
|it.unimi.dsi:fastutil|8.5.4|直接依赖|maven|
|com.github.jnr:jnr-constants|0.9.17|间接依赖|maven|
|is-stream|1.1.0|间接依赖|npm|
|com.github.luben:zstd-jni|1.5.2-3|直接依赖|maven|
|org.eclipse.aether:aether-connector-file|0.9.0.M2|间接依赖|maven|
|com.amazonaws:aws-java-sdk-kms|1.12.497|间接依赖|maven|
|javax.jdo:jdo-api|3.0.1|间接依赖|maven|
|jest-jasmine2|27.5.0|间接依赖|npm|
|@eslint-community/eslint-utils|4.2.0|间接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|define-properties|1.2.0|间接依赖|npm|
|@babel/core|7.22.11|间接依赖|npm|
|serve-static|1.14.1|间接依赖|npm|
|url-parse|1.5.10|间接依赖|npm|
|org.pac4j:pac4j-core|3.8.3|直接依赖|maven|
|com.google.guava:guava|32.0.1-jre|直接依赖|maven|
|@babel/helper-split-export-declaration|7.22.6|间接依赖|npm|
|resolve-from|4.0.0|间接依赖|npm|
|normalize-package-data|2.5.0|间接依赖|npm|
|p-locate|3.0.0|间接依赖|npm|
|org.codehaus.woodstox:woodstox-core-asl|4.4.1|间接依赖|maven|
|react-popper|2.3.0|间接依赖|npm|
|org.apache.commons:commons-compress|1.20|间接依赖|maven|
|org.apache.commons:commons-math3|3.6.1|直接依赖|maven|
|org.apache.ant:ant|1.9.1|间接依赖|maven|
|classnames|2.3.2|间接依赖|npm|
|org.apache.yetus:audience-annotations|0.5.0|间接依赖|maven|
|cliui|5.0.0|间接依赖|npm|
|org.apache.hive:hive-storage-api|2.7.0|间接依赖|maven|
|tmpl|1.0.5|间接依赖|npm|
|yn|3.1.1|间接依赖|npm|
|org.sonatype.sisu.inject:cglib|2.2.1-v20090111|间接依赖|maven|
|net.sf.opencsv:opencsv|2.3|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.9|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.2|间接依赖|maven|
|org.apache.commons:commons-text|1.3|间接依赖|maven|
|esprima|4.0.1|间接依赖|npm|
|node-forge|0.10.0|间接依赖|npm|
|is-descriptor|0.1.6|间接依赖|npm|
|onetime|5.1.2|直接依赖|npm|
|array-union|1.0.2|间接依赖|npm|
|mime|2.5.2|间接依赖|npm|
|org.apache.zookeeper:zookeeper|3.4.13|间接依赖|maven|
|is-wsl|1.1.0|间接依赖|npm|
|postcss-color-mod-function|3.0.3|间接依赖|npm|
|@blueprintjs/datetime2|0.9.35|直接依赖|npm|
|fill-range|4.0.0|间接依赖|npm|
|@babel/plugin-proposal-export-namespace-from|7.14.2|间接依赖|npm|
|@tsconfig/node12|1.0.11|间接依赖|npm|
|error-ex|1.3.2|间接依赖|npm|
|nanomatch|1.2.13|间接依赖|npm|
|jest-message-util|27.5.0|间接依赖|npm|
|@babel/plugin-transform-async-to-generator|7.13.0|间接依赖|npm|
|envinfo|7.8.1|间接依赖|npm|
|define-property|2.0.2|间接依赖|npm|
|util-extend|1.0.3|间接依赖|npm|
|org.apache.twill:twill-discovery-api|0.6.0-incubating|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.3|间接依赖|maven|
|@babel/plugin-proposal-logical-assignment-operators|7.14.2|间接依赖|npm|
|levn|0.4.1|间接依赖|npm|
|org.mariadb.jdbc:mariadb-java-client|2.7.3|直接依赖|maven|
|cosmiconfig|7.1.0|间接依赖|npm|
|com.amazonaws:aws-java-sdk-s3|1.12.497|直接依赖|maven|
|org.ow2.asm:asm-tree|9.3|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.77.Final|间接依赖|maven|
|org.hamcrest:hamcrest-core|1.3|间接依赖|maven|
|chrome-trace-event|1.0.3|间接依赖|npm|
|is-string|1.0.7|间接依赖|npm|
|make-dir|3.1.0|间接依赖|npm|
|org.antlr:stringtemplate|3.2|直接依赖|maven|
|net.minidev:accessors-smart|1.2|间接依赖|maven|
|org.apache.cassandra:cassandra-all|1.0.8|间接依赖|maven|
|webpack|5.88.2|直接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|vfile|4.2.1|间接依赖|npm|
|gensync|1.0.0-beta.2|间接依赖|npm|
|@types/react|18.2.8|间接依赖|npm|
|io.opentelemetry:opentelemetry-sdk-trace|1.7.0|直接依赖|maven|
|org.apache.jclouds.api:openstack-swift|2.5.0|直接依赖|maven|
|lodash.escape|4.0.1|直接依赖|npm|
|spdx-license-ids|3.0.5|间接依赖|npm|
|io.netty:netty-handler-proxy|4.1.46.Final|间接依赖|maven|
|com.github.jnr:jnr-ffi|2.1.16|间接依赖|maven|
|@types/react-splitter-layout|3.0.2|直接依赖|npm|
|mixin-deep|1.3.2|间接依赖|npm|
|@babel/plugin-syntax-dynamic-import|7.8.3|间接依赖|npm|
|json-bigint-native|1.2.0|间接依赖|npm|
|read-installed|4.0.3|间接依赖|npm|
|whatwg-url|8.7.0|间接依赖|npm|
|org.apache.curator:curator-framework|5.5.0|直接依赖|maven|
|babel-plugin-macros|2.8.0|间接依赖|npm|
|postcss-nesting|7.0.1|间接依赖|npm|
|org.eclipse.jetty:jetty-security|9.4.51.v20230217|间接依赖|maven|
|org.checkerframework:checker-qual|3.33.0|间接依赖|maven|
|com.amazonaws:aws-java-sdk-sts|1.12.497|直接依赖|maven|
|d3-dsv|2.0.0|直接依赖|npm|
|jest-util|27.5.0|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|@babel/plugin-syntax-export-namespace-from|7.8.3|间接依赖|npm|
|vary|1.1.2|间接依赖|npm|
|graceful-fs|4.2.10|间接依赖|npm|
|object.hasown|1.1.0|间接依赖|npm|
|ip|1.1.5|间接依赖|npm|
|log4j:log4j|1.2.17|间接依赖|maven|
|punycode|2.1.1|间接依赖|npm|
|eslint-import-resolver-node|0.3.6|间接依赖|npm|
|org.codehaus.mojo:animal-sniffer-annotations|1.14|间接依赖|maven|
|html-escaper|2.0.2|间接依赖|npm|
|postcss-loader|5.3.0|直接依赖|npm|
|@babel/plugin-transform-dotall-regex|7.12.13|间接依赖|npm|
|babel-preset-jest|27.5.0|间接依赖|npm|
|io.netty:netty-common|4.1.94.Final|直接依赖|maven|
|run-parallel|1.2.0|间接依赖|npm|
|clean-regexp|1.0.0|间接依赖|npm|
|yargs-parser|13.1.2|间接依赖|npm|
|emotion|10.0.27|间接依赖|npm|
|killable|1.0.1|间接依赖|npm|
|strip-eof|1.0.0|间接依赖|npm|
|com.netflix.astyanax:astyanax|1.0.1|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.1.3|间接依赖|maven|
|org.postgresql:postgresql|42.6.0|直接依赖|maven|
|ws|7.5.7|间接依赖|npm|
|org.apache.thrift:libfb303|0.9.3|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.29.Final|间接依赖|maven|
|@emotion/stylis|0.8.5|间接依赖|npm|
|es-to-primitive|1.2.1|间接依赖|npm|
|com.amazonaws:aws-java-sdk-core|1.12.497|直接依赖|maven|
|@hypnosphi/create-react-context|0.3.1|直接依赖|npm|
|stubs|3.0.0|间接依赖|npm|
|etag|1.8.1|间接依赖|npm|
|postcss-safe-parser|4.0.2|间接依赖|npm|
|com.jcraft:jsch|0.1.55|间接依赖|maven|
|file-loader|6.2.0|直接依赖|npm|
|lodash.memoize|4.1.2|间接依赖|npm|
|@types/react-router-dom|5.3.3|直接依赖|npm|
|on-headers|1.0.2|间接依赖|npm|
|com.zaxxer:HikariCP-java7|2.4.12|间接依赖|maven|
|org.apache.commons:commons-collections4|4.2|间接依赖|maven|
|junit:junit|4.12|间接依赖|maven|
|serve-index|1.9.1|间接依赖|npm|
|@jest/console|27.5.0|间接依赖|npm|
|readable-stream|3.4.0|间接依赖|npm|
|@webassemblyjs/helper-wasm-bytecode|1.11.6|间接依赖|npm|
|has-own-prop|2.0.0|直接依赖|npm|
|jest-runner|27.5.0|间接依赖|npm|
|com.github.jnr:jffi|1.2.23|间接依赖|maven|
|randombytes|2.1.0|间接依赖|npm|
|org.apache.kafka:kafka_2.11|2.0.0|间接依赖|maven|
|stack-utils|2.0.3|间接依赖|npm|
|core-js|3.10.1|直接依赖|npm|
|@discoveryjs/json-ext|0.5.2|间接依赖|npm|
|retry|0.12.0|间接依赖|npm|
|sugarss|2.0.0|间接依赖|npm|
|readdirp|2.2.1|间接依赖|npm|
|deepmerge|4.2.2|间接依赖|npm|
|postcss-color-functional-notation|2.0.1|间接依赖|npm|
|gzip-size|6.0.0|间接依赖|npm|
|os-homedir|1.0.2|间接依赖|npm|
|postcss-dir-pseudo-class|5.0.0|间接依赖|npm|
|loader-runner|4.2.0|间接依赖|npm|
|eslint-plugin-unicorn|38.0.1|直接依赖|npm|
|org.roaringbitmap:shims|0.9.0|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-smile-provider|2.12.7|直接依赖|maven|
|org.apache.cassandra.deps:avro|1.4.0-cassandra-1|间接依赖|maven|
|has-bigints|1.0.2|间接依赖|npm|
|org.apache.calcite.avatica:avatica-server|1.23.0|直接依赖|maven|
|com.google.guava:guava|31.1-jre|直接依赖|maven|
|d3-array|2.12.1|间接依赖|npm|
|org.roaringbitmap:RoaringBitmap|0.9.0|直接依赖|maven|
|jest-worker|27.5.1|间接依赖|npm|
|com.github.docker-java:docker-java|3.2.13|直接依赖|maven|
|jest|27.5.0|直接依赖|npm|
|com.google.code.gson:gson|2.8.6|间接依赖|maven|
|babel-plugin-polyfill-regenerator|0.2.2|间接依赖|npm|
|@babel/plugin-transform-for-of|7.13.0|间接依赖|npm|
|org.apache.jclouds.provider:rackspace-cloudfiles-uk|2.5.0|直接依赖|maven|
|@babel/plugin-proposal-json-strings|7.14.2|间接依赖|npm|
|is-accessor-descriptor|0.1.6|间接依赖|npm|
|javax.transaction:transaction-api|1.1|间接依赖|maven|
|org.apache.kerby:kerb-client|1.0.1|间接依赖|maven|
|commons-io:commons-io|2.11.0|直接依赖|maven|
|is-windows|1.0.2|间接依赖|npm|
|com.amazonaws:aws-java-sdk-rds|1.12.497|直接依赖|maven|
|com.google.inject.extensions:guice-multibindings|4.1.0|直接依赖|maven|
|org.apache.arrow:arrow-format|0.8.0|间接依赖|maven|
|require-directory|2.1.1|间接依赖|npm|
|bser|2.1.1|间接依赖|npm|
|io.swagger:swagger-annotations|1.6.2|间接依赖|maven|
|net.sf.jopt-simple:jopt-simple|5.0.4|间接依赖|maven|
|com.google.protobuf:protobuf-java-util|3.24.0|直接依赖|maven|
|fs-extra|8.1.0|直接依赖|npm|
|mathml-tag-names|2.1.3|间接依赖|npm|
|hard-rejection|2.1.0|间接依赖|npm|
|org.apache.druid.extensions:druid-lookups-cached-global|28.0.0-SNAPSHOT|直接依赖|maven|
|deep-is|0.1.4|间接依赖|npm|
|object.assign|4.1.4|间接依赖|npm|
|com.google.re2j:re2j|1.1|间接依赖|maven|
|net.hydromatic:aggdesigner-algorithm|6.0|间接依赖|maven|
|is-shared-array-buffer|1.0.2|间接依赖|npm|
|read-package-json|2.0.13|间接依赖|npm|
|@jest/transform|27.5.0|间接依赖|npm|
|jsonfile|4.0.0|间接依赖|npm|
|org.eclipse.jetty:jetty-client|9.4.51.v20230217|直接依赖|maven|
|@types/cheerio|0.22.12|间接依赖|npm|
|jsesc|2.5.2|间接依赖|npm|
|has-property-descriptors|1.0.0|间接依赖|npm|
|@types/react-router|5.1.2|间接依赖|npm|
|net.java.dev.jna:jna-platform|5.13.0|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-client|3.3.6|间接依赖|maven|
|com.ibm.icu:icu4j|73.2|直接依赖|maven|
|util-deprecate|1.0.2|间接依赖|npm|
|source-map-js|1.0.2|间接依赖|npm|
|array-find-index|1.0.2|间接依赖|npm|
|shallow-clone|3.0.1|间接依赖|npm|
|is-typedarray|1.0.0|间接依赖|npm|
|org.jetbrains.kotlin:kotlin-stdlib|1.4.10|间接依赖|maven|
|arg|4.1.1|间接依赖|npm|
|org.xerial.snappy:snappy-java|1.0.4.1|间接依赖|maven|
|@babel/plugin-syntax-json-strings|7.8.3|间接依赖|npm|
|org.apache.hive.shims:hive-shims-common|3.1.3|间接依赖|maven|
|org.apiguardian:apiguardian-api|1.1.2|间接依赖|maven|
|com.github.jnr:jnr-x86asm|1.0.2|间接依赖|maven|
|min-indent|1.0.1|间接依赖|npm|
|node-fetch|2.6.7|间接依赖|npm|
|org.apache.kerby:kerby-config|1.0.1|间接依赖|maven|
|com.typesafe.netty:netty-reactive-streams|2.0.0|间接依赖|maven|
|process-nextick-args|2.0.1|直接依赖|npm|
|react-dom|18.2.0|直接依赖|npm|
|@typescript-eslint/parser|5.51.0|间接依赖|npm|
|merge-descriptors|1.0.1|间接依赖|npm|
|no-case|3.0.4|间接依赖|npm|
|fb-watchman|2.0.1|间接依赖|npm|
|org.apache.hive:hive-standalone-metastore|3.1.3|间接依赖|maven|
|io.fabric8:kubernetes-model-extensions|6.7.2|间接依赖|maven|
|@jest/source-map|27.5.0|间接依赖|npm|
|walker|1.0.8|间接依赖|npm|
|color-name|1.1.3|间接依赖|npm|
|com.sun.jersey:jersey-servlet|1.19.4|直接依赖|maven|
|num2fraction|1.2.2|直接依赖|npm|
|@blueprintjs/core|4.20.1|间接依赖|npm|
|nan|2.14.0|间接依赖|npm|
|com.google.protobuf:protobuf-java|2.5.0|间接依赖|maven|
|webpack-bundle-analyzer|4.4.1|直接依赖|npm|
|io.kubernetes:client-java|11.0.4|直接依赖|maven|
|org.apache.commons:commons-pool2|2.6.1|间接依赖|maven|
|io.grpc:grpc-netty-shaded|1.57.2|直接依赖|maven|
|com.microsoft.azure:azure-storage|8.6.0|直接依赖|maven|
|com.amazonaws:jmespath-java|1.12.497|间接依赖|maven|
|org.jetbrains:annotations|17.0.0|间接依赖|maven|
|unist-util-is|4.1.0|间接依赖|npm|
|object.values|1.1.6|间接依赖|npm|
|obuf|1.1.2|间接依赖|npm|
|@babel/types|7.22.11|间接依赖|npm|
|@babel/helper-plugin-utils|7.0.0|间接依赖|npm|
|jest-watcher|27.5.0|间接依赖|npm|
|@blueprintjs/popover2|1.14.9|间接依赖|npm|
|org.antlr:antlr4-runtime|4.5.3|直接依赖|maven|
|agent-base|6.0.2|间接依赖|npm|
|@babel/plugin-proposal-optional-chaining|7.14.2|间接依赖|npm|
|javax.transaction:jta|1.1|间接依赖|maven|
|array-unique|0.3.2|间接依赖|npm|
|dezalgo|1.0.3|间接依赖|npm|
|org.apache.druid:web-console|28.0.0-SNAPSHOT|直接依赖|maven|
|big.js|5.2.2|间接依赖|npm|
|is-plain-obj|2.1.0|间接依赖|npm|
|@babel/highlight|7.22.10|间接依赖|npm|
|io.netty:netty-resolver-dns|4.1.29.Final|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.23|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.18.0|直接依赖|maven|
|globjoin|0.1.4|间接依赖|npm|
|es-abstract|1.21.2|间接依赖|npm|
|org.apache.ant:ant|1.10.3|间接依赖|maven|
|de.ruedigermoeller:fst|2.50|间接依赖|maven|
|com.google.api-client:google-api-client|1.26.0|直接依赖|maven|
|nwsapi|2.2.0|间接依赖|npm|
|org.datanucleus:javax.jdo|3.2.0-m3|间接依赖|maven|
|io.gsonfire:gson-fire|1.8.5|间接依赖|maven|
|dom4|2.1.6|间接依赖|npm|
|batch|0.6.1|间接依赖|npm|
|history|4.10.1|间接依赖|npm|
|@emotion/hash|0.8.0|间接依赖|npm|
|org.apache.druid:druid-indexing-hadoop|28.0.0-SNAPSHOT|直接依赖|maven|
|commons-codec:commons-codec|1.10|间接依赖|maven|
|org.apache.cassandra:cassandra-thrift|1.0.8|间接依赖|maven|
|org.eclipse.jetty:jetty-rewrite|9.3.20.v20170531|间接依赖|maven|
|tslib|2.5.3|间接依赖|npm|
|@types/react-table|6.8.5|直接依赖|npm|
|js-sdsl|4.3.0|间接依赖|npm|
|org.apache.druid.extensions:mysql-metadata-storage|28.0.0-SNAPSHOT|直接依赖|maven|
|com.sun.jersey:jersey-bundle|1.19.3|间接依赖|maven|
|readdir-scoped-modules|1.1.0|间接依赖|npm|
|org.glassfish.jaxb:jaxb-runtime|2.3.1|直接依赖|maven|
|exit|0.1.2|间接依赖|npm|
|kind-of|6.0.3|间接依赖|npm|
|uniq|1.0.1|间接依赖|npm|
|com.github.os72:protobuf-dynamic|0.9.3|直接依赖|maven|
|camelcase-keys|6.2.2|间接依赖|npm|
|json-stable-stringify-without-jsonify|1.0.1|间接依赖|npm|
|saxes|5.0.1|间接依赖|npm|
|jakarta.inject:jakarta.inject-api|1.0.3|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|3.3.6|间接依赖|maven|
|eslint-rule-composer|0.3.0|间接依赖|npm|
|org.apache.commons:commons-compress|1.23.0|直接依赖|maven|
|com.github.stanford-futuredata.momentsketch:momentsketch-solver|0.1.1|直接依赖|maven|
|org.apache.hadoop:hadoop-common|3.3.6|直接依赖|maven|
|commondir|1.0.1|间接依赖|npm|
|org.lz4:lz4-java|1.8.0|直接依赖|maven|
|constant-case|3.0.4|间接依赖|npm|
|@babel/plugin-syntax-class-static-block|7.12.13|间接依赖|npm|
|org.yaml:snakeyaml|1.21|间接依赖|maven|
|sisteransi|1.0.5|间接依赖|npm|
|extend-shallow|3.0.2|间接依赖|npm|
|pkg-dir|4.2.0|间接依赖|npm|
|chokidar|2.1.8|间接依赖|npm|
|io.netty:netty-transport-classes-kqueue|4.1.94.Final|间接依赖|maven|
|@babel/helper-annotate-as-pure|7.12.13|间接依赖|npm|
|node-int64|0.4.0|间接依赖|npm|
|ansi-escapes|4.3.2|间接依赖|npm|
|com.fasterxml.jackson.core:jackson-databind|2.12.7.1|间接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|@types/file-saver|2.0.1|直接依赖|npm|
|lodash.template|4.5.0|间接依赖|npm|
|com.squareup.okhttp3:okhttp|3.12.12|间接依赖|maven|
|io.fabric8:kubernetes-model-storageclass|6.7.2|间接依赖|maven|
|@babel/plugin-transform-literals|7.12.13|间接依赖|npm|
|commons-lang:commons-lang|2.5|间接依赖|maven|
|postcss-image-set-function|3.0.1|间接依赖|npm|
|posix-character-classes|0.1.1|间接依赖|npm|
|@babel/plugin-transform-shorthand-properties|7.12.13|间接依赖|npm|
|org.apache.thrift:libthrift|0.13.0|直接依赖|maven|
|org.apache.ranger:ranger-plugins-audit|2.0.0|直接依赖|maven|
|select-hose|2.0.0|间接依赖|npm|
|minimatch|3.0.5|间接依赖|npm|
|union-value|1.0.1|间接依赖|npm|
|fast-glob|3.2.12|间接依赖|npm|
|@types/babel__template|7.4.1|间接依赖|npm|
|io.fabric8:kubernetes-model-discovery|6.7.2|间接依赖|maven|
|org.eclipse.persistence:commonj.sdo|2.1.1|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.10.1|间接依赖|maven|
|org.apache.maven:maven-artifact|3.6.0|直接依赖|maven|
|d3-color|2.0.0|间接依赖|npm|
|querystring|0.2.0|间接依赖|npm|
|unicode-canonical-property-names-ecmascript|1.0.4|间接依赖|npm|
|parseurl|1.3.3|间接依赖|npm|
|@babel/plugin-transform-unicode-regex|7.12.13|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|org.apache.druid.extensions:druid-kafka-indexing-service|28.0.0-SNAPSHOT|直接依赖|maven|
|@babel/helper-define-polyfill-provider|0.2.3|间接依赖|npm|
|babel-jest|27.5.0|间接依赖|npm|
|snarkdown|2.0.0|直接依赖|npm|
|@babel/helper-simple-access|7.22.5|间接依赖|npm|
|org.apache.curator:curator-client|5.5.0|直接依赖|maven|
|zwitch|1.0.5|间接依赖|npm|
|org.apache.httpcomponents:httpmime|4.5.3|间接依赖|maven|
|@types/numeral|0.0.26|直接依赖|npm|
|write-file-atomic|3.0.3|间接依赖|npm|
|org.apache.kerby:kerby-util|1.0.1|间接依赖|maven|
|org.schemarepo:schema-repo-common|0.1.3|直接依赖|maven|
|org.apache.orc:orc-shims|1.7.6|间接依赖|maven|
|once|1.4.0|间接依赖|npm|
|minimalistic-assert|1.0.1|间接依赖|npm|
|eventemitter3|4.0.7|间接依赖|npm|
|spdx-satisfies|4.0.1|间接依赖|npm|
|org.apache.thrift:libthrift|0.6.1|间接依赖|maven|
|iconv-lite|0.4.24|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|org.eclipse.jetty:jetty-continuation|9.4.51.v20230217|间接依赖|maven|
|regexp-tree|0.1.24|间接依赖|npm|
|org.apache.hive.shims:hive-shims-0.23|3.1.3|间接依赖|maven|
|@types/parse-json|4.0.0|间接依赖|npm|
|shebang-command|1.2.0|间接依赖|npm|
|send|0.17.1|间接依赖|npm|
|com.google.protobuf:protobuf-java|3.14.0|间接依赖|maven|
|is-builtin-module|3.1.0|间接依赖|npm|
|proxy-addr|2.0.6|间接依赖|npm|
|spdy-transport|3.0.0|间接依赖|npm|
|com.opencsv:opencsv|4.6|直接依赖|maven|
|org.apache.hive:hive-classification|3.1.3|间接依赖|maven|
|stream-events|1.0.5|间接依赖|npm|
|commons-io:commons-io|2.4|间接依赖|maven|
|org.apache.calcite:calcite-linq4j|1.35.0|直接依赖|maven|
|glob-parent|3.1.0|间接依赖|npm|
|io.netty:netty-common|4.1.17.Final|间接依赖|maven|
|object.pick|1.3.0|间接依赖|npm|
|escodegen|2.0.0|间接依赖|npm|
|hjson|3.2.1|直接依赖|npm|
|org.ow2.asm:asm-commons|9.3|直接依赖|maven|
|org.apache.hadoop.thirdparty:hadoop-shaded-protobuf_3_7|1.1.1|间接依赖|maven|
|org.apache.commons:commons-dbcp2|2.6.0|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.9.10|间接依赖|maven|
|jest-circus|27.5.0|间接依赖|npm|
|diff|4.0.1|间接依赖|npm|
|glob-to-regexp|0.4.1|间接依赖|npm|
|@babel/plugin-proposal-async-generator-functions|7.14.2|间接依赖|npm|
|supports-hyperlinks|2.3.0|间接依赖|npm|
|char-regex|1.0.2|间接依赖|npm|
|com.github.vladimir-bukhtoyarov:bucket4j-core|4.10.0|间接依赖|maven|
|http-proxy|1.18.1|间接依赖|npm|
|@babel/plugin-proposal-nullish-coalescing-operator|7.14.2|间接依赖|npm|
|io.dropwizard.metrics:metrics-graphite|4.2.19|直接依赖|maven|
|acorn-globals|6.0.0|间接依赖|npm|
|org.apache.curator:curator-x-discovery|5.5.0|直接依赖|maven|
|destroy|1.0.4|间接依赖|npm|
|jest-diff|27.5.0|间接依赖|npm|
|com.github.jnr:jnr-enxio|0.30|间接依赖|maven|
|popper.js|1.16.1|间接依赖|npm|
|find-cache-dir|3.3.1|间接依赖|npm|
|com.tdunning:t-digest|3.2|直接依赖|maven|
|style-loader|2.0.0|直接依赖|npm|
|co.cask.tephra:tephra-hbase-compat-1.0|0.6.0|间接依赖|maven|
|org.eclipse.jetty:jetty-security|9.4.44.v20210927|间接依赖|maven|
|extend|3.0.2|间接依赖|npm|
|org.jline:jline|3.9.0|间接依赖|maven|
|io.airlift:aircompressor|0.21|间接依赖|maven|
|decamelize|1.2.0|间接依赖|npm|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.12.7|直接依赖|maven|
|file-entry-cache|6.0.1|间接依赖|npm|
|thunky|1.1.0|间接依赖|npm|
|makeerror|1.0.12|间接依赖|npm|
|commons-codec:commons-codec|1.11|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-extension-autoconfigure|1.7.0-alpha|直接依赖|maven|
|@typescript-eslint/scope-manager|5.51.0|间接依赖|npm|
|is-path-in-cwd|2.1.0|间接依赖|npm|
|io.netty:netty-transport-native-epoll|4.1.77.Final|间接依赖|maven|
|htmlparser2|3.10.1|间接依赖|npm|
|@types/enzyme-adapter-react-16|1.0.5|直接依赖|npm|
|org.reactivestreams:reactive-streams|1.0.2|间接依赖|maven|
|nice-try|1.0.5|间接依赖|npm|
|detect-newline|3.1.0|间接依赖|npm|
|org.apache.druid:druid-server|28.0.0-SNAPSHOT|直接依赖|maven|
|@emotion/utils|0.11.3|间接依赖|npm|
|flatten|1.0.2|间接依赖|npm|
|globalthis|1.0.3|间接依赖|npm|
|unicode-property-aliases-ecmascript|1.1.0|间接依赖|npm|
|io.opentelemetry:opentelemetry-api|1.7.0|直接依赖|maven|
|picomatch|2.3.1|间接依赖|npm|
|org.apache.kerby:kerb-util|1.0.1|间接依赖|maven|
|org.apache.kerby:kerb-core|1.0.1|间接依赖|maven|
|postcss-custom-media|7.0.8|间接依赖|npm|
|org.apache.ranger:ranger-plugins-cred|2.0.0|间接依赖|maven|
|serialize-javascript|6.0.1|间接依赖|npm|
|stylelint-scss|3.21.0|间接依赖|npm|
|eslint-visitor-keys|3.3.0|间接依赖|npm|
|@jest/fake-timers|27.5.0|间接依赖|npm|
|value-equal|1.0.1|间接依赖|npm|
|dom-serializer|0.1.1|间接依赖|npm|
|com.aliyun:aliyun-java-sdk-kms|2.11.0|间接依赖|maven|
|org.locationtech.jts.io:jts-io-common|1.19.0|间接依赖|maven|
|@babel/preset-modules|0.1.4|间接依赖|npm|
|org.apache.logging.log4j:log4j-core|2.17.1|间接依赖|maven|
|postcss-pseudo-class-any-link|6.0.0|间接依赖|npm|
|@babel/helper-builder-binary-assignment-operator-visitor|7.12.13|间接依赖|npm|
|@types/react-dom|18.2.4|间接依赖|npm|
|lodash.merge|4.6.2|间接依赖|npm|
|remark-stringify|9.0.1|间接依赖|npm|
|com.google.protobuf:protobuf-java|3.24.0|直接依赖|maven|
|org.eclipse.jetty:jetty-http|9.3.20.v20170531|间接依赖|maven|
|prompts|2.4.2|直接依赖|npm|
|org.apache.twill:twill-zookeeper|0.6.0-incubating|间接依赖|maven|
|eslint-utils|3.0.0|间接依赖|npm|
|eslint-plugin-unused-imports|2.0.0|直接依赖|npm|
|org.apache.jclouds.api:rackspace-cloudidentity|2.5.0|间接依赖|maven|
|com.github.docker-java:docker-java-transport|3.2.13|间接依赖|maven|
|com.vlkan:flatbuffers|1.2.0-3f79e055|间接依赖|maven|
|supports-color|5.5.0|间接依赖|npm|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.15.2|间接依赖|maven|
|@xtuc/ieee754|1.2.0|间接依赖|npm|
|jline:jline|0.9.94|间接依赖|maven|
|table|6.8.1|间接依赖|npm|
|@babel/plugin-syntax-top-level-await|7.12.13|间接依赖|npm|
|safe-regex|1.1.0|间接依赖|npm|
|d3-scale|3.3.0|直接依赖|npm|
|setprototypeof|1.1.1|间接依赖|npm|
|jline:jline|2.12|间接依赖|maven|
|ignore|5.2.4|间接依赖|npm|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|querystringify|2.2.0|间接依赖|npm|
|@nodelib/fs.stat|2.0.5|间接依赖|npm|
|eslint-template-visitor|2.3.2|间接依赖|npm|
|lz-string|1.5.0|间接依赖|npm|
|webpack-merge|5.7.3|间接依赖|npm|
|playwright-chromium|1.25.0|直接依赖|npm|
|org.apache.orc:orc-shims|1.5.1|间接依赖|maven|
|@babel/plugin-proposal-dynamic-import|7.14.2|间接依赖|npm|
|javax.annotation:javax.annotation-api|1.2|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-smile|2.12.7|直接依赖|maven|
|fontsource-open-sans|3.0.9|直接依赖|npm|
|org.slf4j:slf4j-api|1.7.10|间接依赖|maven|
|org.apache.jclouds.driver:jclouds-slf4j|2.5.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.10.3|间接依赖|maven|
|lodash._reinterpolate|3.0.0|间接依赖|npm|
|rimraf|2.6.3|间接依赖|npm|
|io.netty:netty-transport|4.1.46.Final|间接依赖|maven|
|io.netty:netty-buffer|4.1.17.Final|间接依赖|maven|
|stax:stax-api|1.0.1|间接依赖|maven|
|file-saver|2.0.2|直接依赖|npm|
|eslint-config-prettier|8.3.0|直接依赖|npm|
|@types/json-schema|7.0.11|间接依赖|npm|
|multicast-dns|6.2.3|间接依赖|npm|
|spdy|4.0.2|间接依赖|npm|
|commander|2.20.0|间接依赖|npm|
|io.fabric8:kubernetes-model-resource|6.7.2|间接依赖|maven|
|org.apache.druid:druid-indexing-service|28.0.0-SNAPSHOT|直接依赖|maven|
|com.tdunning:json|1.8|间接依赖|maven|
|org.hyperic:sigar|1.6.5.132|直接依赖|maven|
|events|3.3.0|间接依赖|npm|
|end-of-stream|1.4.1|间接依赖|npm|
|joda-time:joda-time|2.9.9|间接依赖|maven|
|@babel/plugin-syntax-async-generators|7.8.4|间接依赖|npm|
|org.codehaus.janino:commons-compiler|3.1.9|间接依赖|maven|
|io.netty:netty-resolver|4.1.94.Final|间接依赖|maven|
|postcss-modules-local-by-default|4.0.0|间接依赖|npm|
|@types/lodash.debounce|4.0.6|直接依赖|npm|
|which|1.3.1|间接依赖|npm|
|colorette|1.2.2|间接依赖|npm|
|com.google.code.gson:gson|2.10.1|间接依赖|maven|
|com.github.joshelser:dropwizard-metrics-hadoop-metrics2-reporter|0.1.2|间接依赖|maven|
|org.checkerframework:checker-qual|3.31.0|间接依赖|maven|
|co.cask.tephra:tephra-core|0.6.0|间接依赖|maven|
|commons-codec:commons-codec|1.9|间接依赖|maven|
|io.netty:netty-buffer|4.1.94.Final|直接依赖|maven|
|uri-js|4.2.2|间接依赖|npm|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.12.6|间接依赖|maven|
|tiny-warning|1.0.3|间接依赖|npm|
|@babel/plugin-transform-classes|7.14.4|间接依赖|npm|
|dns-equal|1.0.0|间接依赖|npm|
|org.apache.datasketches:datasketches-memory|2.2.0|直接依赖|maven|
|esutils|2.0.3|间接依赖|npm|
|enhanced-resolve|5.15.0|间接依赖|npm|
|io.netty:netty|3.7.0.Final|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.64|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|babel-plugin-istanbul|6.1.1|间接依赖|npm|
|@babel/plugin-transform-template-literals|7.13.0|间接依赖|npm|
|postcss-font-variant|4.0.0|间接依赖|npm|
|org.apache.httpcomponents:httpcore|4.4.10|间接依赖|maven|
|com.google.inject.extensions:guice-servlet|4.1.0|直接依赖|maven|
|org.apache.druid:druid-aws-common|28.0.0-SNAPSHOT|直接依赖|maven|
|io.fabric8:kubernetes-model-rbac|6.7.2|间接依赖|maven|
|org.apache.logging.log4j:log4j-web|2.17.1|间接依赖|maven|
|regenerate|1.4.2|间接依赖|npm|
|@types/graceful-fs|4.1.5|间接依赖|npm|
|org.apache.commons:commons-configuration2|2.8.0|间接依赖|maven|
|abab|2.0.5|间接依赖|npm|
|gud|1.0.0|间接依赖|npm|
|org.mozilla:rhino|1.7.14|直接依赖|maven|
|pluralize|8.0.0|间接依赖|npm|
|io.netty:netty-transport|4.1.29.Final|间接依赖|maven|
|org.apache.solr:solr-solrj|7.7.1|间接依赖|maven|
|ci-info|3.3.0|间接依赖|npm|
|org.slf4j:slf4j-api|1.7.7|间接依赖|maven|
|@babel/compat-data|7.22.9|间接依赖|npm|
|resolve-cwd|3.0.0|间接依赖|npm|
|org.apache.parquet:parquet-column|1.12.0|直接依赖|maven|
|p-try|2.2.0|间接依赖|npm|
|org.slf4j:slf4j-api|1.7.6|间接依赖|maven|
|icss-utils|5.1.0|间接依赖|npm|
|sockjs|0.3.21|间接依赖|npm|
|javax.servlet:servlet-api|2.5|间接依赖|maven|
|org.schemarepo:schema-repo-api|0.1.3|直接依赖|maven|
|ts-loader|9.4.2|直接依赖|npm|
|io.vavr:vavr-match|0.10.2|间接依赖|maven|
|io.netty:netty|3.10.5.Final|间接依赖|maven|
|javax.servlet:javax.servlet-api|3.1.0|直接依赖|maven|
|string.prototype.matchall|4.0.6|间接依赖|npm|
|com.zaxxer:HikariCP|2.6.1|间接依赖|maven|
|domhandler|2.4.2|间接依赖|npm|
|org.apache.avro:avro-ipc-jetty|1.11.1|间接依赖|maven|
|to-fast-properties|2.0.0|间接依赖|npm|
|org.antlr:antlr-runtime|3.5.2|间接依赖|maven|
|org.apache.orc:orc-core|1.5.1|间接依赖|maven|
|org.threeten:threeten-extra|1.5.0|间接依赖|maven|
|@babel/plugin-transform-exponentiation-operator|7.12.13|间接依赖|npm|
|com.fasterxml.jackson.core:jackson-databind|2.10.3|间接依赖|maven|
|org.schemarepo:schema-repo-client|0.1.3|直接依赖|maven|
|joda-time:joda-time|2.10.8|间接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5-h2|5.1.3|间接依赖|maven|
|execall|2.0.0|间接依赖|npm|
|javax.xml.bind:jaxb-api|2.3.1|直接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5|5.1.3|间接依赖|maven|
|org.apache.commons:commons-pool2|2.2|间接依赖|maven|
|com.google.protobuf:protobuf-java|2.4.1|间接依赖|maven|
|normalize-selector|0.2.0|间接依赖|npm|
|unist-util-stringify-position|2.0.3|间接依赖|npm|
|io.prometheus:simpleclient|0.16.0|直接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.4.51.v20230217|直接依赖|maven|
|@tsconfig/node10|1.0.9|间接依赖|npm|
|@humanwhocodes/module-importer|1.0.1|间接依赖|npm|
|org.apache.curator:curator-recipes|5.2.0|间接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|5.4.0|间接依赖|maven|
|is-absolute-url|3.0.3|间接依赖|npm|
|com.fasterxml.jackson.core:jackson-databind|2.10.0.pr1|间接依赖|maven|
|org.eclipse.aether:aether-api|0.9.0.M2|直接依赖|maven|
|v8-compile-cache|2.3.0|间接依赖|npm|
|use-resize-observer|9.1.0|间接依赖|npm|
|normalize.css|8.0.1|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|specificity|0.4.1|间接依赖|npm|
|org.eclipse.persistence:eclipselink|2.5.2|间接依赖|maven|
|html-encoding-sniffer|2.0.1|间接依赖|npm|
|ee-first|1.1.1|间接依赖|npm|
|@webassemblyjs/helper-numbers|1.11.6|间接依赖|npm|
|org.checkerframework:checker-qual|3.8.0|间接依赖|maven|
|tr46|2.1.0|间接依赖|npm|
|org.jdom:jdom2|2.0.6|间接依赖|maven|
|snapdragon-util|3.0.1|间接依赖|npm|
|is-arrayish|0.2.1|间接依赖|npm|
|asm:asm|3.1|间接依赖|maven|
|jest-validate|27.5.0|间接依赖|npm|
|is-glob|4.0.3|间接依赖|npm|
|gonzales-pe|4.3.0|间接依赖|npm|
|@types/mdast|3.0.3|间接依赖|npm|
|org.ow2.asm:asm|9.3|直接依赖|maven|
|org.apache.jclouds.api:openstack-keystone|2.5.0|直接依赖|maven|
|@types/aria-query|5.0.1|间接依赖|npm|
|eslint-scope|5.1.1|间接依赖|npm|
|is-symbol|1.0.4|间接依赖|npm|
|io.netty:netty|3.10.6.Final|直接依赖|maven|
|array.prototype.flatmap|1.2.5|间接依赖|npm|
|@emotion/cache|10.0.29|间接依赖|npm|
|org.slf4j:slf4j-api|1.7.25|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|org.apache.curator:curator-client|2.12.0|间接依赖|maven|
|websocket-extensions|0.1.4|间接依赖|npm|
|is-weakref|1.0.2|间接依赖|npm|
|com.github.jnr:jnr-posix|3.0.61|间接依赖|maven|
|org.eclipse.aether:aether-impl|0.9.0.M2|间接依赖|maven|
|clone-deep|4.0.1|间接依赖|npm|
|sirv|1.0.11|间接依赖|npm|
|com.google.inject:guice|4.1.0|直接依赖|maven|
|io.vavr:vavr|0.10.2|间接依赖|maven|
|org.eclipse.jetty:jetty-servlets|9.4.51.v20230217|直接依赖|maven|
|babel-plugin-emotion|10.2.2|间接依赖|npm|
|org.apache.zookeeper:zookeeper-jute|3.5.10|直接依赖|maven|
|org.jruby.joni:joni|2.1.27|间接依赖|maven|
|inflight|1.0.6|间接依赖|npm|
|anymatch|2.0.0|间接依赖|npm|
|postcss-resolve-nested-selector|0.1.1|间接依赖|npm|
|org.apache.commons:commons-collections4|4.4|间接依赖|maven|
|org.pac4j:pac4j-oidc|3.8.3|直接依赖|maven|
|date-fns-tz|1.3.8|间接依赖|npm|
|change-case|4.1.2|间接依赖|npm|
|@babel/traverse|7.22.11|间接依赖|npm|
|asap|2.0.6|间接依赖|npm|
|io.netty:netty-transport|4.1.94.Final|间接依赖|maven|
|universalify|0.1.2|间接依赖|npm|
|p-finally|1.0.0|间接依赖|npm|
|react-ace|10.1.0|直接依赖|npm|
|resolve-pathname|3.0.0|间接依赖|npm|
|org.ow2.asm:asm|9.1|间接依赖|maven|
|org.bitbucket.b_c:jose4j|0.7.3|间接依赖|maven|
|assign-symbols|1.0.0|间接依赖|npm|
|is-path-inside|2.1.0|间接依赖|npm|
|org.apache.maven:maven-settings|3.1.1|间接依赖|maven|
|espree|9.5.0|间接依赖|npm|
|lodash.get|4.4.2|间接依赖|npm|
|@webassemblyjs/wasm-edit|1.11.6|间接依赖|npm|
|unicode-match-property-value-ecmascript|1.2.0|间接依赖|npm|
|eslint|8.36.0|直接依赖|npm|
|@emotion/unitless|0.7.5|间接依赖|npm|
|@types/istanbul-lib-coverage|2.0.1|间接依赖|npm|
|repeat-string|1.6.1|间接依赖|npm|
|io.opentracing:opentracing-util|0.33.0|间接依赖|maven|
|org.apache.druid:druid-services|28.0.0-SNAPSHOT|直接依赖|maven|
|is-map|2.0.2|间接依赖|npm|
|com.google.guava:guava|25.1-jre|间接依赖|maven|
|content-disposition|0.5.3|间接依赖|npm|
|@babel/plugin-syntax-private-property-in-object|7.14.0|间接依赖|npm|
|map-obj|1.0.1|间接依赖|npm|
|cssdb|4.4.0|间接依赖|npm|
|core-js-compat|3.14.0|间接依赖|npm|
|@babel/eslint-parser|7.17.0|间接依赖|npm|
|org.tukaani:xz|1.9|直接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.70|直接依赖|maven|
|org.apache.kerby:kerb-simplekdc|1.0.1|间接依赖|maven|
|is-typed-array|1.1.10|间接依赖|npm|
|is-generator-fn|2.1.0|间接依赖|npm|
|globby|6.1.0|间接依赖|npm|
|lodash.truncate|4.4.2|间接依赖|npm|
|ip-regex|2.1.0|间接依赖|npm|
|com.beust:jcommander|1.78|间接依赖|maven|
|@babel/plugin-syntax-bigint|7.8.3|间接依赖|npm|
|replace|1.2.2|直接依赖|npm|
|istanbul-lib-instrument|5.1.0|间接依赖|npm|
|io.fabric8:kubernetes-client-api|6.7.2|直接依赖|maven|
|javax.ws.rs:jsr311-api|1.1.1|直接依赖|maven|
|it.unimi.dsi:fastutil-core|8.5.4|直接依赖|maven|
|@types/minimatch|3.0.4|间接依赖|npm|
|org.apache.parquet:parquet-jackson|1.12.0|间接依赖|maven|
|slice-ansi|4.0.0|间接依赖|npm|
|is-array-buffer|3.0.2|间接依赖|npm|
|@babel/plugin-transform-object-super|7.12.13|间接依赖|npm|
|@types/scheduler|0.16.1|间接依赖|npm|
|com.aliyun.oss:aliyun-sdk-oss|3.11.3|直接依赖|maven|
|json3|3.3.3|间接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|flatted|3.1.1|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|javax.activation:activation|1.1|间接依赖|maven|
|com.amazonaws:amazon-kinesis-producer|0.13.1|直接依赖|maven|
|camelcase|5.3.1|间接依赖|npm|
|org.apache.thrift:libthrift|0.9.3|间接依赖|maven|
|org.apache.datasketches:datasketches-java|4.1.0|直接依赖|maven|
|del|4.1.1|间接依赖|npm|
|net.minidev:json-smart|2.4.7|间接依赖|maven|
|is-potential-custom-element-name|1.0.1|间接依赖|npm|
|org.eclipse.aether:aether-spi|0.9.0.M2|间接依赖|maven|
|com.sun.mail:javax.mail|1.6.1|间接依赖|maven|
|selfsigned|1.10.14|间接依赖|npm|
|it.unimi.dsi:fastutil|6.5.6|间接依赖|maven|
|org.codehaus.jettison:jettison|1.1|间接依赖|maven|
|has-proto|1.0.1|间接依赖|npm|
|mimic-fn|2.1.0|间接依赖|npm|
|com.ning:compress-lzf|1.0.4|直接依赖|maven|
|@awesome-code-style/stylelint-config|4.0.0|直接依赖|npm|
|strip-ansi|3.0.1|间接依赖|npm|
|com.googlecode.json-simple:json-simple|1.1|间接依赖|maven|
|@jridgewell/trace-mapping|0.3.9|间接依赖|npm|
|ajv-keywords|3.5.2|间接依赖|npm|
|is-arguments|1.1.1|间接依赖|npm|
|org.bouncycastle:bcprov-ext-jdk15on|1.70|直接依赖|maven|
|regenerate-unicode-properties|8.2.0|间接依赖|npm|
|static-extend|0.1.2|间接依赖|npm|
|joda-time:joda-time|2.8.1|间接依赖|maven|
|strip-indent|3.0.0|间接依赖|npm|
|lodash.isequal|4.5.0|间接依赖|npm|
|source-map-support|0.5.21|间接依赖|npm|
|glob|7.1.4|间接依赖|npm|
|ace-builds|1.4.14|间接依赖|npm|
|file-uri-to-path|1.0.0|间接依赖|npm|
|org.eclipse.jetty:jetty-rewrite|9.4.51.v20230217|直接依赖|maven|
|@jridgewell/source-map|0.3.5|间接依赖|npm|
|d3-interpolate|2.0.1|间接依赖|npm|
|com.github.jnr:jnr-a64asm|1.0.0|间接依赖|maven|
|com.google.code.findbugs:jsr305|2.0.1|直接依赖|maven|
|@babel/plugin-syntax-import-meta|7.10.4|间接依赖|npm|
|@babel/helper-replace-supers|7.14.4|间接依赖|npm|
|postcss-modules-values|4.0.0|间接依赖|npm|
|eventsource|1.1.1|间接依赖|npm|
|natural-compare-lite|1.4.0|间接依赖|npm|
|electron-to-chromium|1.4.501|间接依赖|npm|
|regenerator-transform|0.14.5|间接依赖|npm|
|fast-json-stable-stringify|2.0.0|间接依赖|npm|
|@babel/helper-member-expression-to-functions|7.13.12|间接依赖|npm|
|@babel/helper-explode-assignable-expression|7.13.0|间接依赖|npm|
|es-module-lexer|1.3.0|间接依赖|npm|
|org.apache.ranger:ranger-plugins-common|2.0.0|直接依赖|maven|
|org.apache.zookeeper:zookeeper|3.5.3-beta|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.13|间接依赖|maven|
|org.wildfly.openssl:wildfly-openssl|1.1.3.Final|间接依赖|maven|
|org.apache.parquet:parquet-hadoop|1.12.0|直接依赖|maven|
|@babel/plugin-syntax-optional-chaining|7.8.3|间接依赖|npm|
|teeny-request|7.0.1|间接依赖|npm|
|io.netty:netty-codec-http|4.1.94.Final|直接依赖|maven|
|throat|6.0.1|间接依赖|npm|
|react-fast-compare|3.2.2|间接依赖|npm|
|react-router|5.3.4|间接依赖|npm|
|read-pkg-up|7.0.1|间接依赖|npm|
|org.ehcache:ehcache|3.3.1|间接依赖|maven|
|escape-html|1.0.3|间接依赖|npm|
|express|4.17.1|间接依赖|npm|
|is-data-descriptor|0.1.4|间接依赖|npm|
|strip-bom|3.0.0|间接依赖|npm|
|which-boxed-primitive|1.0.2|间接依赖|npm|
|known-css-properties|0.21.0|间接依赖|npm|
|is-number|3.0.0|间接依赖|npm|
|org.eclipse.persistence:javax.persistence|2.1.0|间接依赖|maven|
|@babel/plugin-syntax-class-properties|7.12.13|间接依赖|npm|
|abbrev|1.1.1|间接依赖|npm|
|@types/uuid|7.0.2|直接依赖|npm|
|babel-plugin-dynamic-import-node|2.3.3|间接依赖|npm|
|io.fabric8:zjsonpatch|0.3.0|间接依赖|maven|
|queue-microtask|1.2.3|间接依赖|npm|
|org.eclipse.jetty.websocket:websocket-client|9.4.51.v20230217|间接依赖|maven|
|@sinonjs/commons|1.8.3|间接依赖|npm|
|com.squareup.okhttp3:logging-interceptor|3.14.9|间接依赖|maven|
|trough|1.0.5|间接依赖|npm|
|@babel/helper-module-transforms|7.22.9|间接依赖|npm|
|license-checker|25.0.1|直接依赖|npm|
|@babel/plugin-transform-duplicate-keys|7.12.13|间接依赖|npm|
|string-width|4.2.3|间接依赖|npm|
|io.netty:netty-transport-native-epoll|4.1.46.Final|间接依赖|maven|
|human-signals|2.1.0|直接依赖|npm|
|to-object-path|0.3.0|间接依赖|npm|
|immutable|4.3.0|间接依赖|npm|
|node-releases|2.0.13|间接依赖|npm|
|string.prototype.trim|1.2.7|间接依赖|npm|
|is-set|2.0.2|间接依赖|npm|
|org.apache.maven:maven-model-builder|3.1.1|间接依赖|maven|
|commons-codec:commons-codec|1.13|直接依赖|maven|
|is-weakset|2.0.2|间接依赖|npm|
|create-emotion|10.0.27|间接依赖|npm|
|log-symbols|4.1.0|间接依赖|npm|
|to-regex|3.0.2|间接依赖|npm|
|@stylelint/postcss-markdown|0.36.2|间接依赖|npm|
|org.codehaus.plexus:plexus-interpolation|1.19|间接依赖|maven|
|picocolors|0.2.1|间接依赖|npm|
|org.codehaus.woodstox:stax2-api|4.2.1|间接依赖|maven|
|jest-changed-files|27.5.0|间接依赖|npm|
|com.sun.jersey:jersey-server|1.19.4|直接依赖|maven|
|argparse|1.0.10|间接依赖|npm|
|parent-module|1.0.1|间接依赖|npm|
|com.google.http-client:google-http-client-jackson2|1.26.0|直接依赖|maven|
|forwarded|0.1.2|间接依赖|npm|
|@polka/url|1.0.0-next.12|间接依赖|npm|
|@types/d3-array|2.12.3|直接依赖|npm|
|@webassemblyjs/ieee754|1.11.6|间接依赖|npm|
|io.opentelemetry:opentelemetry-semconv|1.7.0-alpha|间接依赖|maven|
|domutils|1.7.0|间接依赖|npm|
|validate-npm-package-license|3.0.4|间接依赖|npm|
|compression|1.7.4|间接依赖|npm|
|csstype|3.0.7|间接依赖|npm|
|org.objenesis:objenesis|2.6|间接依赖|maven|
|@babel/helper-hoist-variables|7.22.5|间接依赖|npm|
|@types/stack-utils|2.0.1|间接依赖|npm|
|react-router-dom|5.3.4|直接依赖|npm|
|flat-cache|3.0.4|间接依赖|npm|
|@types/babel__core|7.1.18|间接依赖|npm|
|com.microsoft.azure:azure-keyvault-core|1.0.0|间接依赖|maven|
|body-parser|1.19.0|间接依赖|npm|
|is-negative-zero|2.0.2|间接依赖|npm|
|which-collection|1.0.1|直接依赖|npm|
|com.google.errorprone:error_prone_annotations|2.18.0|间接依赖|maven|
|@webpack-cli/configtest|1.0.2|间接依赖|npm|
|default-gateway|4.2.0|间接依赖|npm|
|regenerator-runtime|0.13.11|间接依赖|npm|
|postcss-sass|0.4.4|间接依赖|npm|
|deep-equal|1.1.1|间接依赖|npm|
|org.apache.orc:orc-core|1.7.6|直接依赖|maven|
|entities|1.1.2|间接依赖|npm|
|javax.inject:javax.inject|1|间接依赖|maven|
|jest-haste-map|27.5.0|间接依赖|npm|
|remark|13.0.0|间接依赖|npm|
|esquery|1.5.0|间接依赖|npm|
|sqlline:sqlline|1.3.0|间接依赖|maven|
|@types/json5|0.0.29|间接依赖|npm|
|com.fasterxml.jackson.core:jackson-core|2.9.6|间接依赖|maven|
|org.ow2.asm:asm-analysis|9.3|间接依赖|maven|
|org.apache.geronimo.specs:geronimo-jcache_1.0_spec|1.0-alpha-1|间接依赖|maven|
|javax.ws.rs:javax.ws.rs-api|2.0.1|间接依赖|maven|
|org.apache.twill:twill-common|0.6.0-incubating|间接依赖|maven|
|com.googlecode.concurrentlinkedhashmap:concurrentlinkedhashmap-lru|1.2|间接依赖|maven|
|nopt|4.0.1|间接依赖|npm|
|org.apache.httpcomponents:httpcore|4.4.4|间接依赖|maven|
|@types/semver|7.3.13|间接依赖|npm|
|org.yaml:snakeyaml|2.0|间接依赖|maven|
|dom-accessibility-api|0.5.16|间接依赖|npm|
|cssstyle|2.3.0|间接依赖|npm|
|com.github.wnameless:json-flattener|0.1.0|直接依赖|maven|
|org.codehaus.jackson:jackson-xc|1.9.13|间接依赖|maven|
|unbox-primitive|1.0.2|间接依赖|npm|
|import-local|3.0.2|间接依赖|npm|
|axios|0.26.1|直接依赖|npm|
|@babel/helper-optimise-call-expression|7.12.13|间接依赖|npm|
|@webassemblyjs/wasm-parser|1.11.6|间接依赖|npm|
|es-set-tostringtag|2.0.1|间接依赖|npm|
|available-typed-arrays|1.0.5|间接依赖|npm|
|postcss-custom-selectors|5.1.2|间接依赖|npm|
|io.netty:netty-transport-native-kqueue|4.1.94.Final|直接依赖|maven|
|is-weakmap|2.0.1|间接依赖|npm|
|type-is|1.6.18|间接依赖|npm|
|unified|9.2.1|间接依赖|npm|
|com.sun.xml.bind:jaxb-impl|2.3.3|间接依赖|maven|
|net.minidev:json-smart|2.3|间接依赖|maven|
|io.github.resilience4j:resilience4j-bulkhead|1.3.1|直接依赖|maven|
|regexp.prototype.flags|1.5.0|间接依赖|npm|
|json-parse-even-better-errors|2.3.1|间接依赖|npm|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.12.7|间接依赖|maven|
|is-date-object|1.0.5|间接依赖|npm|
|com.nimbusds:oauth2-oidc-sdk|6.5|直接依赖|maven|
|v8-compile-cache-lib|3.0.1|间接依赖|npm|
|terser-webpack-plugin|5.3.9|间接依赖|npm|
|io.prometheus:simpleclient|0.9.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.10.0.pr1|间接依赖|maven|
|redis.clients:jedis|2.9.0|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.1|间接依赖|maven|
|@babel/plugin-transform-function-name|7.12.13|间接依赖|npm|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|org.apache.ant:ant-launcher|1.9.1|间接依赖|maven|
|org.codehaus.janino:janino|3.1.9|间接依赖|maven|
|@babel/plugin-proposal-private-property-in-object|7.14.0|间接依赖|npm|
|@blueprintjs/icons|4.16.0|间接依赖|npm|
|@babel/plugin-transform-new-target|7.12.13|间接依赖|npm|
|sass|1.59.3|直接依赖|npm|
|com.squareup.okio:okio|1.17.2|间接依赖|maven|
|istanbul-lib-source-maps|4.0.1|间接依赖|npm|
|react-is|16.8.6|间接依赖|npm|
|@xtuc/long|4.2.2|间接依赖|npm|
|regjsgen|0.5.2|间接依赖|npm|
|unpipe|1.0.0|间接依赖|npm|
|regexpu-core|4.7.1|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|com.sun.activation:jakarta.activation|1.2.2|间接依赖|maven|
|org.apache.curator:curator-framework|2.12.0|间接依赖|maven|
|com.github.jnr:jnr-unixsocket|0.36|间接依赖|maven|
|org.antlr:antlr-runtime|3.2|间接依赖|maven|
|istanbul-lib-report|3.0.0|间接依赖|npm|
|webpack-log|2.0.0|间接依赖|npm|
|com.twitter.elephantbird:elephant-bird-hadoop-compat|4.17|直接依赖|maven|
|svg-tags|1.0.0|间接依赖|npm|
|org.fusesource.leveldbjni:leveldbjni-all|1.8|间接依赖|maven|
|@types/node|12.11.7|间接依赖|npm|
|ret|0.1.15|间接依赖|npm|
|org.bouncycastle:bcpkix-jdk15on|1.69|间接依赖|maven|
|@babel/plugin-proposal-numeric-separator|7.14.2|间接依赖|npm|
|com.google.inject.extensions:guice-assistedinject|5.0.1|间接依赖|maven|
|eslint-module-utils|2.7.3|间接依赖|npm|
|@sinonjs/fake-timers|8.1.0|间接依赖|npm|
|use|3.1.1|间接依赖|npm|
|@babel/helper-module-imports|7.22.5|间接依赖|npm|
|org.bouncycastle:bcpkix-jdk15on|1.64|间接依赖|maven|
|stylelint-config-recommended|4.0.0|间接依赖|npm|
|istanbul-lib-coverage|3.2.0|间接依赖|npm|
|interpret|2.2.0|间接依赖|npm|
|co.cask.tephra:tephra-api|0.6.0|间接依赖|maven|
|@babel/plugin-bugfix-v8-spread-parameters-in-optional-chaining|7.13.12|间接依赖|npm|
|org.apache.curator:curator-recipes|5.5.0|直接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.46.Final|间接依赖|maven|
|lodash.templatesettings|4.2.0|间接依赖|npm|
|org.datanucleus:datanucleus-rdbms|4.1.19|间接依赖|maven|
|kleur|3.0.3|间接依赖|npm|
|has-value|1.0.0|间接依赖|npm|
|split-string|3.1.0|间接依赖|npm|
|org.apache.ambari:ambari-metrics-common|2.7.0.0.0|直接依赖|maven|
|wildcard|2.0.0|间接依赖|npm|
|postcss|8.4.21|间接依赖|npm|
|url|0.11.0|间接依赖|npm|
|eslint-plugin-react|7.28.0|直接依赖|npm|
|numeral|2.0.6|直接依赖|npm|
|global-prefix|3.0.0|间接依赖|npm|
|@webassemblyjs/leb128|1.11.6|间接依赖|npm|
|commons-beanutils:commons-beanutils|1.9.4|间接依赖|maven|
|@babel/plugin-transform-spread|7.13.0|间接依赖|npm|
|com.google.j2objc:j2objc-annotations|2.8|间接依赖|maven|
|@babel/plugin-syntax-logical-assignment-operators|7.10.4|间接依赖|npm|
|com.aliyun:aliyun-java-sdk-core|4.5.10|间接依赖|maven|
|eslint-plugin-react-hooks|4.3.0|直接依赖|npm|
|commons-io:commons-io|2.5|间接依赖|maven|
|date-fns|2.30.0|间接依赖|npm|
|cssom|0.4.4|间接依赖|npm|
|io.fabric8:kubernetes-model-coordination|6.7.2|间接依赖|maven|
|read-pkg|5.2.0|间接依赖|npm|
|sass-loader|13.2.0|直接依赖|npm|
|decimal.js|10.3.1|间接依赖|npm|
|domelementtype|1.3.1|间接依赖|npm|
|async-limiter|1.0.1|直接依赖|npm|
|com.amazonaws:aws-java-sdk-kinesis|1.12.497|直接依赖|maven|
|eslint-plugin-header|3.1.1|直接依赖|npm|
|async-each|1.0.3|间接依赖|npm|
|org.joda:joda-convert|2.2.1|间接依赖|maven|
|@babel/plugin-transform-typeof-symbol|7.12.13|间接依赖|npm|
|org.apache.logging.log4j:log4j-slf4j-impl|2.18.0|直接依赖|maven|
|com.google.code.gson:gson|2.2.4|直接依赖|maven|
|regjsparser|0.6.9|间接依赖|npm|
|io.timeandspace:cron-scheduler|0.1|直接依赖|maven|
|supports-preserve-symlinks-flag|1.0.0|间接依赖|npm|
|com.google.inject.extensions:guice-assistedinject|4.1.0|直接依赖|maven|
|upath|1.2.0|间接依赖|npm|
|org.apache.commons:commons-lang3|3.11|间接依赖|maven|
|arr-diff|4.0.0|间接依赖|npm|
|io.fabric8:kubernetes-httpclient-okhttp|6.7.2|间接依赖|maven|
|loader-utils|1.4.2|间接依赖|npm|
|micromatch|3.1.10|间接依赖|npm|
|@humanwhocodes/config-array|0.11.8|间接依赖|npm|
|org.apache.commons:commons-pool2|2.4.2|间接依赖|maven|
|errno|0.1.8|直接依赖|npm|
|org.apache.arrow:arrow-memory|0.8.0|间接依赖|maven|
|postcss-selector-not|4.0.0|间接依赖|npm|
|webpack-sources|3.2.3|间接依赖|npm|
|postcss-less|3.1.4|间接依赖|npm|
|caniuse-lite|1.0.30001522|间接依赖|npm|
|http-deceiver|1.2.7|间接依赖|npm|
|io.opentelemetry:opentelemetry-api-metrics|1.7.0-alpha|间接依赖|maven|
|convert-source-map|1.6.0|间接依赖|npm|
|is-callable|1.2.7|间接依赖|npm|
|@ampproject/remapping|2.2.1|间接依赖|npm|
|commons-net:commons-net|3.9.0|直接依赖|maven|
|postcss-selector-matches|4.0.0|间接依赖|npm|
|cjs-module-lexer|1.2.2|间接依赖|npm|
|typed-styles|0.0.7|直接依赖|npm|
|aria-query|5.1.3|间接依赖|npm|
|org.eclipse.jetty:jetty-webapp|9.4.51.v20230217|间接依赖|maven|
|spdx-expression-parse|3.0.0|间接依赖|npm|
|d3-time|1.1.0|间接依赖|npm|
|@babel/helper-compilation-targets|7.22.10|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|com.google.guava:guava|19.0|间接依赖|maven|
|astral-regex|2.0.0|间接依赖|npm|
|@types/yargs-parser|13.0.0|直接依赖|npm|
|string.prototype.trimend|1.0.6|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|css-has-pseudo|0.10.0|间接依赖|npm|
|org.jruby.jcodings:jcodings|1.0.43|间接依赖|maven|
|extglob|2.0.4|间接依赖|npm|
|connect-history-api-fallback|1.6.0|间接依赖|npm|
|com.google.apis:google-api-services-compute|v1-rev20190607-1.26.0|直接依赖|maven|
|com.sun.jersey:jersey-client|1.19.4|直接依赖|maven|
|@awesome-code-style/eslint-config|4.1.0|直接依赖|npm|
|org.testng:testng|7.3.0|直接依赖|maven|
|ms|2.0.0|间接依赖|npm|
|jest-environment-node|27.5.0|间接依赖|npm|
|loose-envify|1.4.0|间接依赖|npm|
|@tsconfig/node14|1.0.3|间接依赖|npm|
|dedent|0.7.0|间接依赖|npm|
|io.confluent:kafka-schema-registry-client|6.0.1|直接依赖|maven|
|org.apache.parquet:parquet-hadoop-bundle|1.10.0|间接依赖|maven|
|@babel/code-frame|7.22.10|间接依赖|npm|
|fragment-cache|0.2.1|间接依赖|npm|
|resolve|1.22.1|间接依赖|npm|
|@jest/test-sequencer|27.5.0|间接依赖|npm|
|import-lazy|4.0.0|间接依赖|npm|
|ansi-regex|4.1.1|间接依赖|npm|
|org.apache.hadoop:hadoop-mapreduce-client-core|3.3.6|直接依赖|maven|
|antlr:antlr|2.7.7|间接依赖|maven|
|opn|5.5.0|间接依赖|npm|
|net.minidev:json-smart||间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-extension-autoconfigure-spi|1.7.0|间接依赖|maven|
|upper-case-first|2.0.2|间接依赖|npm|
|multicast-dns-service-types|1.1.0|间接依赖|npm|
|commons-pool:commons-pool|1.5.4|间接依赖|maven|
|postcss-media-minmax|4.0.0|间接依赖|npm|
|codecov|3.8.2|直接依赖|npm|
|org.slf4j:slf4j-reload4j|1.7.36|间接依赖|maven|
|postcss-color-rebeccapurple|4.0.1|间接依赖|npm|
|data-urls|2.0.0|间接依赖|npm|
|com.yammer.metrics:metrics-core|2.2.0|间接依赖|maven|
|@babel/plugin-proposal-unicode-property-regex|7.12.13|间接依赖|npm|
|org.apache.ant:ant-launcher|1.10.3|间接依赖|maven|
|com.google.code.gson:gson|2.8.9|间接依赖|maven|
|identity-obj-proxy|3.0.0|直接依赖|npm|
|com.google.j2objc:j2objc-annotations|1.1|间接依赖|maven|
|com.twitter.elephantbird:elephant-bird-core|4.17|直接依赖|maven|
|imurmurhash|0.1.4|间接依赖|npm|
|for-in|1.0.2|间接依赖|npm|
|mdast-util-to-markdown|0.6.5|间接依赖|npm|
|io.opentelemetry:opentelemetry-context|1.7.0|直接依赖|maven|
|com.sun.istack:istack-commons-runtime|3.0.7|间接依赖|maven|
|org.slf4j:slf4j-log4j12|1.7.25|间接依赖|maven|
|@babel/plugin-transform-sticky-regex|7.12.13|间接依赖|npm|
|pascalcase|0.1.1|间接依赖|npm|
|org.apache.druid:druid-gcp-common|28.0.0-SNAPSHOT|直接依赖|maven|
|merge2|1.4.1|间接依赖|npm|
|com.carrotsearch:hppc|0.7.2|间接依赖|maven|
|trim-newlines|3.0.1|间接依赖|npm|
|com.fasterxml.jackson.module:jackson-module-guice|2.12.7|直接依赖|maven|
|base|0.11.2|间接依赖|npm|
|com.sun.jersey:jersey-client|1.15|间接依赖|maven|
|com.amazonaws:amazon-kinesis-client|1.14.4|直接依赖|maven|
|isobject|3.0.1|间接依赖|npm|
|spdx-ranges|2.1.0|间接依赖|npm|
|com.google.inject.extensions:guice-assistedinject|3.0|间接依赖|maven|
|leven|3.1.0|间接依赖|npm|
|remark-parse|9.0.0|间接依赖|npm|
|io.prometheus:simpleclient_pushgateway|0.16.0|直接依赖|maven|
|micromark|2.11.4|间接依赖|npm|
|treeify|1.1.0|间接依赖|npm|
|resolve.exports|1.1.0|间接依赖|npm|
|io.prometheus:simpleclient_httpserver|0.9.0|间接依赖|maven|
|lru-cache|6.0.0|间接依赖|npm|
|@webassemblyjs/helper-api-error|1.11.6|间接依赖|npm|
|postcss-color-hex-alpha|5.0.3|间接依赖|npm|
|com.github.pjfanning:jersey-json|1.20|间接依赖|maven|
|@types/d3-axis|2.1.3|直接依赖|npm|
|webidl-conversions|6.1.0|间接依赖|npm|
|repeat-element|1.1.3|间接依赖|npm|
|bail|1.0.5|间接依赖|npm|
|org.eclipse.jetty:jetty-util|9.4.44.v20210927|间接依赖|maven|
|snake-case|3.0.4|间接依赖|npm|
|org.apache.maven:maven-model|3.1.1|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|直接依赖|maven|
|@babel/helper-validator-option|7.22.5|间接依赖|npm|
|com.sun.jersey.contribs:jersey-guice|1.19.4|直接依赖|maven|
|it.unimi.dsi:fastutil-extra|8.5.4|直接依赖|maven|
|org.apache.druid:druid-sql|28.0.0-SNAPSHOT|直接依赖|maven|
|org.skife.config:config-magic|0.9|直接依赖|maven|
|internal-ip|4.3.0|间接依赖|npm|
|postcss-env-function|2.0.2|间接依赖|npm|
|range-parser|1.2.1|间接依赖|npm|
|com.sun.xml.bind:jaxb-impl|2.2.3-1|间接依赖|maven|
|cookie-signature|1.0.6|间接依赖|npm|
|rechoir|0.7.0|间接依赖|npm|
|minimist|1.2.6|间接依赖|npm|
|source-map-url|0.4.0|间接依赖|npm|
|debug|3.1.0|间接依赖|npm|
|javax.servlet.jsp:jsp-api|2.1|间接依赖|maven|
|param-case|3.0.4|间接依赖|npm|
|postcss-attribute-case-insensitive|4.0.1|间接依赖|npm|
|asynckit|0.4.0|直接依赖|npm|
|org.glassfish:jakarta.el|3.0.4|直接依赖|maven|
|accepts|1.3.7|间接依赖|npm|
|media-typer|0.3.0|间接依赖|npm|
|pify|4.0.1|间接依赖|npm|
|source-map-resolve|0.5.2|间接依赖|npm|
|org.glassfish.jaxb:txw2|2.3.1|间接依赖|maven|
|path-dirname|1.0.2|间接依赖|npm|
|ts-jest|27.1.3|直接依赖|npm|
|arr-flatten|1.1.0|间接依赖|npm|
|function.prototype.name|1.1.5|间接依赖|npm|
|postcss-overflow-shorthand|2.0.0|间接依赖|npm|
|org.hibernate:hibernate-validator|6.2.5.Final|直接依赖|maven|
|cookie|0.4.0|间接依赖|npm|
|follow-redirects|1.15.1|间接依赖|npm|
|dir-glob|3.0.1|直接依赖|npm|
|is-boolean-object|1.1.2|间接依赖|npm|
|@types/memoize-one|4.1.1|直接依赖|npm|
|org.apache.logging.log4j:log4j-core|2.18.0|直接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.36|直接依赖|maven|
|org.apache.kerby:kerb-common|1.0.1|间接依赖|maven|
|org.apache.arrow:arrow-vector|0.8.0|间接依赖|maven|
|longest-streak|2.0.4|间接依赖|npm|
|org.snakeyaml:snakeyaml-engine|2.6|间接依赖|maven|
|ipaddr.js|1.9.1|间接依赖|npm|
|io.fabric8:kubernetes-model-events|6.7.2|间接依赖|maven|
|text-table|0.2.0|间接依赖|npm|
|json5|1.0.1|间接依赖|npm|
|map-cache|0.2.2|间接依赖|npm|
|org.checkerframework:checker-qual|2.0.0|间接依赖|maven|
|normalize-range|0.1.2|间接依赖|npm|
|org.apache.calcite.avatica:avatica-core|1.23.0|直接依赖|maven|
|react-shallow-renderer|16.15.0|直接依赖|npm|
|expand-brackets|2.1.4|间接依赖|npm|
|@eslint/js|8.36.0|间接依赖|npm|
|finalhandler|1.1.2|间接依赖|npm|
|d3-format|1.4.1|间接依赖|npm|
|@webassemblyjs/utf8|1.11.6|间接依赖|npm|
|org.apache.hive:hive-service-rpc|3.1.3|间接依赖|maven|
|http-proxy-middleware|0.19.1|间接依赖|npm|
|@awesome-code-style/prettier-config|4.0.0|直接依赖|npm|
|has-tostringtag|1.0.0|间接依赖|npm|
|io.grpc:grpc-api|1.57.2|间接依赖|maven|
|@cspotcode/source-map-support|0.8.1|间接依赖|npm|
|org.apache.hadoop:hadoop-yarn-server-applicationhistoryservice|3.1.0|间接依赖|maven|
|io.fabric8:kubernetes-client|6.7.2|直接依赖|maven|
|@jest/globals|27.5.0|间接依赖|npm|
|postcss-selector-parser|6.0.11|间接依赖|npm|
|acorn-import-assertions|1.9.0|间接依赖|npm|
|find-up|3.0.0|间接依赖|npm|
|dot-case|3.0.4|间接依赖|npm|
|@typescript-eslint/typescript-estree|5.51.0|间接依赖|npm|
|org.apache.commons:commons-math3|3.1.1|间接依赖|maven|
|org.apache.maven.wagon:wagon-provider-api|2.4|间接依赖|maven|
|eslint-plugin-simple-import-sort|7.0.0|直接依赖|npm|
|@tsconfig/node16|1.0.3|间接依赖|npm|
|com.amazonaws:aws-java-sdk-ec2|1.12.497|直接依赖|maven|
|spdx-exceptions|2.2.0|间接依赖|npm|
|pretty-format|27.5.1|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|core-util-is|1.0.2|直接依赖|npm|
|io.prometheus:simpleclient_common|0.9.0|间接依赖|maven|
|org.ow2.asm:asm-util|7.1|间接依赖|maven|
|cache-base|1.0.1|间接依赖|npm|
|@babel/plugin-transform-reserved-words|7.12.13|间接依赖|npm|
|meow|9.0.0|间接依赖|npm|
|io.netty:netty-codec|4.1.94.Final|间接依赖|maven|
|path-exists|3.0.0|间接依赖|npm|
|argv|0.0.2|间接依赖|npm|
|com.eclipsesource.minimal-json:minimal-json|0.9.4|间接依赖|maven|
|test-exclude|6.0.0|间接依赖|npm|
|negotiator|0.6.2|间接依赖|npm|
|org.apache.servicemix.bundles:org.apache.servicemix.bundles.commons-csv|1.0-r706900_3|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.29.Final|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.29.Final|间接依赖|maven|
|slash|3.0.0|间接依赖|npm|
|@babel/runtime|7.21.0|间接依赖|npm|
|@babel/parser|7.22.11|间接依赖|npm|
|@humanwhocodes/object-schema|1.2.1|间接依赖|npm|
|array-uniq|1.0.3|间接依赖|npm|
|io.github.resilience4j:resilience4j-core|1.3.1|间接依赖|maven|
|commons-dbcp:commons-dbcp|1.4|间接依赖|maven|
|path-key|2.0.1|间接依赖|npm|
|postcss-modules-scope|3.0.0|间接依赖|npm|
|get-package-type|0.1.0|间接依赖|npm|
|io.dropwizard.metrics:metrics-jvm|3.1.0|间接依赖|maven|
|lodash|4.17.21|间接依赖|npm|
|for-each|0.3.3|间接依赖|npm|
|autoprefixer|10.4.14|间接依赖|npm|
|io.dropwizard.metrics:metrics-json|3.1.0|间接依赖|maven|
|babel-plugin-polyfill-corejs3|0.2.2|间接依赖|npm|
|compressible|2.0.18|间接依赖|npm|
|org.apache.curator:curator-client|4.0.0|间接依赖|maven|
|vfile-message|2.0.4|间接依赖|npm|
|css-blank-pseudo|0.1.4|间接依赖|npm|
|dns-txt|2.0.2|间接依赖|npm|
|@webassemblyjs/helper-wasm-section|1.11.6|间接依赖|npm|
|net.sf.jpam:jpam|1.1|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.33|间接依赖|maven|
|commons-cli:commons-cli|1.2|间接依赖|maven|
|statuses|1.5.0|间接依赖|npm|
|org.scala-lang:scala-reflect|2.11.12|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|org.checkerframework:checker-qual|2.5.7|直接依赖|maven|
|org.eclipse.aether:aether-util|0.9.0.M2|直接依赖|maven|
|io.fabric8:kubernetes-model-autoscaling|6.7.2|间接依赖|maven|
|tsconfig-paths|3.12.0|间接依赖|npm|
|redent|3.0.0|间接依赖|npm|
|react|18.2.0|直接依赖|npm|
|io.airlift:aircompressor|0.10|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.7.1|间接依赖|maven|
|@druid-toolkit/visuals-react|0.3.3|直接依赖|npm|
|w3c-xmlserializer|2.0.0|间接依赖|npm|
|io.netty:netty-codec-http|4.1.29.Final|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.12.7|直接依赖|maven|
|@babel/plugin-transform-computed-properties|7.13.0|间接依赖|npm|
|encodeurl|1.0.2|间接依赖|npm|
|copy-to-clipboard|3.2.0|直接依赖|npm|
|loglevel|1.7.1|间接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|@blueprintjs/datetime|4.4.36|间接依赖|npm|
|postcss-values-parser|2.0.1|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|dom-helpers|5.2.1|间接依赖|npm|
|globals|11.12.0|间接依赖|npm|
|org.locationtech.jts:jts-core|1.19.0|间接依赖|maven|
|bytes|3.0.0|间接依赖|npm|
|postcss-focus-visible|4.0.0|间接依赖|npm|
|org.apache.druid.extensions:druid-multi-stage-query|28.0.0-SNAPSHOT|直接依赖|maven|
|path-parse|1.0.7|间接依赖|npm|
|postcss-media-query-parser|0.2.3|间接依赖|npm|
|@babel/helper-environment-visitor|7.22.5|间接依赖|npm|
|array-includes|3.1.4|间接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.14|间接依赖|npm|
|org.apache.commons:commons-text|1.10.0|直接依赖|maven|
|@types/jest|27.4.0|直接依赖|npm|
|@webassemblyjs/floating-point-hex-parser|1.11.6|间接依赖|npm|
|@types/babel__traverse|7.14.2|间接依赖|npm|
|get-stream|4.1.0|间接依赖|npm|
|typescript|4.9.5|直接依赖|npm|
|is-regex|1.1.4|间接依赖|npm|
|org.apache.maven:maven-settings-builder|3.1.1|间接依赖|maven|
|@babel/helper-create-class-features-plugin|7.14.4|间接依赖|npm|
|doctrine|3.0.0|间接依赖|npm|
|@jest/test-result|27.5.0|间接依赖|npm|
|org.eclipse.jetty:jetty-io|9.4.51.v20230217|直接依赖|maven|
|jest-serializer|27.5.0|间接依赖|npm|
|org.apache.jclouds.api:rackspace-cloudfiles|2.5.0|直接依赖|maven|
|@types/minimist|1.2.1|间接依赖|npm|
|@babel/helper-wrap-function|7.13.0|间接依赖|npm|
|urlgrey|0.4.4|间接依赖|npm|
|jest-docblock|27.5.0|间接依赖|npm|
|@babel/plugin-transform-block-scoping|7.14.4|间接依赖|npm|
|com.googlecode.json-simple:json-simple|1.1.1|间接依赖|maven|
|com.flipkart.zjsonpatch:zjsonpatch|0.4.11|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|commons-logging:commons-logging|1.1.3|间接依赖|maven|
|jest-environment-jsdom|27.5.0|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|jest-snapshot|27.5.0|间接依赖|npm|
|io.opentracing:opentracing-noop|0.33.0|间接依赖|maven|
|yargs|13.3.2|间接依赖|npm|
|set-blocking|2.0.0|间接依赖|npm|
|path-type|4.0.0|间接依赖|npm|
|com.typesafe.scala-logging:scala-logging_2.11|3.9.0|间接依赖|maven|
|ansi-html-community|0.0.8|间接依赖|npm|
|is-path-cwd|2.2.0|间接依赖|npm|
|org.apache.calcite:calcite-core|1.35.0|直接依赖|maven|
|com.google.apis:google-api-services-storage|v1-rev20190523-1.26.0|直接依赖|maven|
|istanbul-reports|3.1.4|间接依赖|npm|
|babel-plugin-jest-hoist|27.5.0|间接依赖|npm|
|@types/eslint|8.44.2|间接依赖|npm|
|org.apache.calcite.avatica:avatica-metrics|1.23.0|直接依赖|maven|
|org.eclipse.jetty:jetty-proxy|9.4.51.v20230217|直接依赖|maven|
|warning|4.0.3|间接依赖|npm|
|io.tesla.aether:aether-connector-okhttp|0.0.9|间接依赖|maven|
|com.squareup.okhttp:okhttp|1.0.2|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.10.0.pr1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.9.6|间接依赖|maven|
|combined-stream|1.0.8|直接依赖|npm|
|io.prometheus:simpleclient_tracer_otel|0.16.0|间接依赖|maven|
|string.prototype.trimstart|1.0.6|间接依赖|npm|
|postcss-lab-function|2.0.1|间接依赖|npm|
|org.apache.maven:maven-repository-metadata|3.1.1|间接依赖|maven|
|@druid-toolkit/visuals-core|0.3.3|间接依赖|npm|
|os-tmpdir|1.0.2|间接依赖|npm|
|org.apache.zookeeper:zookeeper|3.4.6|间接依赖|maven|
|ajv|6.12.6|间接依赖|npm|
|mime-types|2.1.24|间接依赖|npm|
|commons-daemon:commons-daemon|1.0.13|间接依赖|maven|
|io.fabric8:kubernetes-model-node|6.7.2|间接依赖|maven|
|typed-array-length|1.0.4|间接依赖|npm|
|decamelize-keys|1.1.0|间接依赖|npm|
|wbuf|1.7.3|间接依赖|npm|
|org.apache.commons:commons-dbcp2|2.0.1|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.20.0|直接依赖|maven|
|io.perfmark:perfmark-api|0.23.0|直接依赖|maven|
|mdast-util-from-markdown|0.8.5|间接依赖|npm|
|toidentifier|1.0.0|间接依赖|npm|
|postcss-initial|3.0.1|间接依赖|npm|
|hpack.js|2.1.6|间接依赖|npm|
|org.apache.druid.extensions:druid-datasketches|28.0.0-SNAPSHOT|直接依赖|maven|
|uuid|7.0.2|间接依赖|npm|
|io.prometheus:simpleclient_tracer_common|0.16.0|间接依赖|maven|
|org.apache.hive:hive-storage-api|2.8.1|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.3|间接依赖|maven|
|d3-selection|2.0.0|直接依赖|npm|
|com.sun.xml.fastinfoset:FastInfoset|1.2.15|间接依赖|maven|
|locate-path|3.0.0|间接依赖|npm|
|unist-util-find-all-after|3.0.2|间接依赖|npm|
|object-keys|1.1.1|间接依赖|npm|
|type-check|0.4.0|间接依赖|npm|
|enquirer|2.3.6|间接依赖|npm|
|postcss-gap-properties|2.0.0|间接依赖|npm|
|org.codehaus.jackson:jackson-jaxrs|1.9.13|间接依赖|maven|
|type-fest|0.18.1|间接依赖|npm|
|co|4.6.0|间接依赖|npm|
|com.github.stephenc.eaio-uuid:uuid|3.2.0|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.1|间接依赖|maven|
|whatwg-encoding|1.0.5|间接依赖|npm|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|org.apache.kerby:kerby-asn1|1.0.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.12.7|直接依赖|maven|
|dnsjava:dnsjava|2.1.7|间接依赖|maven|
|normalize-path|3.0.0|间接依赖|npm|
|org.codehaus.woodstox:stax2-api|3.1.4|间接依赖|maven|
|emojis-list|3.0.0|间接依赖|npm|
|buffer-from|1.1.1|间接依赖|npm|
|@webassemblyjs/wasm-opt|1.11.6|间接依赖|npm|
|bindings|1.5.0|间接依赖|npm|
|@babel/plugin-transform-modules-commonjs|7.14.0|间接依赖|npm|
|pascal-case|3.1.2|间接依赖|npm|
|depd|1.1.2|间接依赖|npm|
|org.apache.hadoop:hadoop-aws|3.3.6|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.11.0|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-metrics|1.7.0-alpha|间接依赖|maven|
|com.github.docker-java:docker-java-transport-netty|3.2.13|直接依赖|maven|
|io.confluent:kafka-schema-registry-client|5.5.12|直接依赖|maven|
|org.checkerframework:checker-qual|2.5.2|间接依赖|maven|
|@babel/plugin-transform-unicode-escapes|7.12.13|间接依赖|npm|
|com.sun.jersey:jersey-core|1.19.4|直接依赖|maven|
|which-typed-array|1.1.9|间接依赖|npm|
|@jest/environment|27.5.0|间接依赖|npm|
|io.dropwizard.metrics:metrics-core|3.2.4|间接依赖|maven|
|org.apache.avro:avro|1.7.7|间接依赖|maven|
|@webassemblyjs/helper-buffer|1.11.6|间接依赖|npm|
|org.apache.kerby:kerb-admin|1.0.1|间接依赖|maven|
|fraction.js|4.2.0|间接依赖|npm|
|@druid-toolkit/query|0.21.1|间接依赖|npm|
|io.fabric8:kubernetes-model-batch|6.7.2|直接依赖|maven|
|@emotion/sheet|0.9.4|间接依赖|npm|
|react-diff-viewer|3.1.1|直接依赖|npm|
|@tootallnate/once|1.1.2|间接依赖|npm|
|dns-packet|1.3.4|间接依赖|npm|
|global-modules|2.0.0|间接依赖|npm|
|com.nimbusds:lang-tag|1.7|直接依赖|maven|
|org.apache.jclouds.provider:rackspace-cloudfiles-us|2.5.0|直接依赖|maven|
|org.apache.twill:twill-api|0.6.0-incubating|间接依赖|maven|
|has-symbols|1.0.3|间接依赖|npm|
|io.fabric8:kubernetes-model-scheduling|6.7.2|间接依赖|maven|
|@types/hjson|2.4.1|直接依赖|npm|
|org.apache.avro:avro-mapred|1.11.1|直接依赖|maven|
|optionator|0.9.1|间接依赖|npm|
|postcss-html|0.36.0|间接依赖|npm|
|jest-each|27.5.0|间接依赖|npm|
|@babel/plugin-transform-destructuring|7.14.4|间接依赖|npm|
|org.apache.kafka:kafka-clients|2.0.0|间接依赖|maven|
|@emotion/weak-memoize|0.2.5|间接依赖|npm|
|postcss-value-parser|4.2.0|间接依赖|npm|
|com.fasterxml.jackson.datatype:jackson-datatype-joda|2.12.7|直接依赖|maven|
|neo-async|2.6.2|间接依赖|npm|
|net.bytebuddy:byte-buddy-agent|1.9.10|间接依赖|maven|
|string_decoder|1.2.0|间接依赖|npm|
|@types/lodash|4.14.136|间接依赖|npm|
|jest-leak-detector|27.5.0|间接依赖|npm|
|indent-string|4.0.0|间接依赖|npm|
|array-flatten|2.1.2|间接依赖|npm|
|io.fabric8:kubernetes-model-core|6.7.2|直接依赖|maven|
|slide|1.1.6|间接依赖|npm|
|diff-match-patch|1.0.5|间接依赖|npm|
|@types/d3-dsv|2.0.3|直接依赖|npm|
|browserslist|4.21.10|间接依赖|npm|
|urix|0.1.0|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|software.amazon.ion:ion-java|1.0.2|间接依赖|maven|
|js-yaml|3.13.1|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|@popperjs/core|2.11.8|间接依赖|npm|
|com.github.stephenc.jcip:jcip-annotations|1.0-1|间接依赖|maven|
|com.kstruct:gethostname4j|0.0.2|间接依赖|maven|
|@nodelib/fs.scandir|2.1.5|间接依赖|npm|
|gopd|1.0.1|间接依赖|npm|
|com.github.oshi:oshi-core|6.4.4|直接依赖|maven|
|bs-logger|0.2.6|间接依赖|npm|
|sentence-case|3.0.4|间接依赖|npm|
|webpack-dev-server|3.11.3|直接依赖|npm|
|webpack-dev-middleware|3.7.3|间接依赖|npm|
|@webassemblyjs/ast|1.11.6|间接依赖|npm|
|babel-plugin-polyfill-corejs2|0.2.2|间接依赖|npm|
|minimist-options|4.1.0|间接依赖|npm|
|http-parser-js|0.5.3|间接依赖|npm|
|@babel/plugin-syntax-typescript|7.16.7|间接依赖|npm|
|@types/normalize-package-data|2.4.0|间接依赖|npm|
|raw-body|2.4.0|间接依赖|npm|
|org.apache.druid.extensions:druid-stats|28.0.0-SNAPSHOT|直接依赖|maven|
|mime-db|1.40.0|间接依赖|npm|
|mdast-util-to-string|2.0.0|间接依赖|npm|
|postcss-modules-extract-imports|3.0.0|间接依赖|npm|
|org.bouncycastle:bcutil-jdk15on|1.69|间接依赖|maven|
|yallist|4.0.0|间接依赖|npm|
|com.squareup.okhttp3:logging-interceptor|3.12.12|间接依赖|maven|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.15.2|间接依赖|maven|
|com.google.guava:guava|14.0.1|间接依赖|maven|
|org.eclipse.jetty:jetty-xml|9.4.51.v20230217|间接依赖|maven|
|isarray|0.0.1|间接依赖|npm|
|org.codehaus.jettison:jettison|1.3.1|间接依赖|maven|
|org.codehaus.jackson:jackson-xc|1.9.2|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.15.2|间接依赖|maven|
|javolution:javolution|5.5.1|间接依赖|maven|
|source-map|0.5.7|间接依赖|npm|
|@eslint-community/regexpp|4.4.0|间接依赖|npm|
|com.github.luben:zstd-jni|1.5.5-1|间接依赖|maven|
|org.apache.logging.log4j:log4j-jul|2.18.0|直接依赖|maven|
|braces|2.3.2|间接依赖|npm|
|json-parse-better-errors|1.0.2|间接依赖|npm|
|find-root|1.1.0|间接依赖|npm|
|internal-slot|1.0.5|间接依赖|npm|
|com.aliyun:aliyun-java-sdk-ram|3.1.0|间接依赖|maven|
|com.jayway.jsonpath:json-path|2.3.0|直接依赖|maven|
|io.kubernetes:client-java-extended|11.0.4|直接依赖|maven|
|joda-time:joda-time|2.12.5|直接依赖|maven|
|@jridgewell/resolve-uri|3.1.0|间接依赖|npm|
|org.apache.iceberg:iceberg-spark-runtime-3.3_2.12|1.0.0|直接依赖|maven|
|org.ini4j:ini4j|0.5.4|间接依赖|maven|
|@testing-library/dom|9.3.0|间接依赖|npm|
|eslint-plugin-import|2.25.4|直接依赖|npm|
|org.codehaus.jackson:jackson-core-asl|1.9.13|间接依赖|maven|
|org.apache.hive:hive-serde|3.1.3|间接依赖|maven|
|org.apache.logging.log4j:log4j-1.2-api|2.18.0|直接依赖|maven|
|org.apache.hadoop:hadoop-hdfs-client|3.3.6|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.12.7|直接依赖|maven|
|opener|1.5.2|间接依赖|npm|
|org.apache.commons:commons-lang3|3.7|间接依赖|maven|
|ajv-errors|1.0.1|直接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)