# GoogleContainerTools/jib安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698034905942458368.svg)](https://www.murphysec.com/console/report/1698034905904709632/1698034905942458368)

仓库描述：🏗 Build container images for your Java applications.

仓库地址：[https://github.com/GoogleContainerTools/jib](https://github.com/GoogleContainerTools/jib)

| star：12975 | watch：330 | fork：1432 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-02 03:39:11 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-03 02:23:45 | 组件总数：235 | 漏洞总数：129 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache Tomcat 竞争条件问题漏洞|竞争条件|[MPS-2018-10791](https://www.oscs1024.com/hd/MPS-2018-10791)|CVE-2018-8037|中危|
|Apache Tomcat 拒绝服务漏洞|不可达退出条件的循环（无限循环）|[MPS-2018-10792](https://www.oscs1024.com/hd/MPS-2018-10792)|CVE-2018-1336|高危|
|Apache Tomcat 输入验证错误漏洞|跨站重定向|[MPS-2018-13051](https://www.oscs1024.com/hd/MPS-2018-13051)|CVE-2018-11784|中危|
|Spring Framework <5.1.1.RELEASE 拒绝服务漏洞|拒绝服务|[MPS-2018-13948](https://www.oscs1024.com/hd/MPS-2018-13948)|CVE-2018-15756|高危|
|FasterXML Jackson < 2.9.8存在拒绝服务漏洞|拒绝服务|[MPS-2018-16099](https://www.oscs1024.com/hd/MPS-2018-16099)|CVE-2018-1000873|中危|
|Apache Tomcat CORS Filter 不安全的默认值漏洞|资源默认不安全|[MPS-2018-6086](https://www.oscs1024.com/hd/MPS-2018-6086)|CVE-2018-8014|严重|
|FasterXML jackson-databind反序列化漏洞(slf4j-ext gadget绕过)|反序列化|[MPS-2019-0018](https://www.oscs1024.com/hd/MPS-2019-0018)|CVE-2018-14718|严重|
|FasterXML jackson-databind反序列化漏洞(blaze-ds-opt gadget绕过)|反序列化|[MPS-2019-0019](https://www.oscs1024.com/hd/MPS-2019-0019)|CVE-2018-14719|严重|
|FasterXML jackson-databind XXE漏洞(DRSHelper gadget绕过)||[MPS-2019-0020](https://www.oscs1024.com/hd/MPS-2019-0020)|CVE-2018-14720|严重|
|FasterXML Jackson-databind服务器端请求伪造漏洞(axis2-jaxws gadget绕过)|SSRF|[MPS-2019-0021](https://www.oscs1024.com/hd/MPS-2019-0021)|CVE-2018-14721|严重|
|FasterXML Jackson-databind代码问题漏洞(axis2-transport-jms gadget绕过)|反序列化|[MPS-2019-0023](https://www.oscs1024.com/hd/MPS-2019-0023)|CVE-2018-19360|严重|
|FasterXML Jackson-databind代码问题漏洞(openjpa gadget绕过)|反序列化|[MPS-2019-0024](https://www.oscs1024.com/hd/MPS-2019-0024)|CVE-2018-19361|严重|
|FasterXML Jackson-databind代码问题漏洞(jboss-common-core gadget绕过)|反序列化|[MPS-2019-0025](https://www.oscs1024.com/hd/MPS-2019-0025)|CVE-2018-19362|严重|
|FasterXML jackson-databind 反序列化漏洞(HikariCP gadget绕过)|反序列化|[MPS-2019-11529](https://www.oscs1024.com/hd/MPS-2019-11529)|CVE-2019-14540|严重|
|FasterXML jackson-databind 反序列化漏洞(HikariCP gadget绕过)|反序列化|[MPS-2019-11533](https://www.oscs1024.com/hd/MPS-2019-11533)|CVE-2019-16335|严重|
|FasterXML jackson-databind 反序列化漏洞(commons-dbcp gadget绕过)|反序列化|[MPS-2019-12479](https://www.oscs1024.com/hd/MPS-2019-12479)|CVE-2019-16942|严重|
|FasterXML jackson-databind 反序列化漏洞(p6spy gadget绕过)|反序列化|[MPS-2019-12480](https://www.oscs1024.com/hd/MPS-2019-12480)|CVE-2019-16943|严重|
|FasterXML jackson-databind 反序列化漏洞(ehcache gadget绕过)|反序列化|[MPS-2019-12676](https://www.oscs1024.com/hd/MPS-2019-12676)|CVE-2019-17267|严重|
|FasterXML jackson-databind 反序列化漏洞(apache-log4j-extras gadget绕过)|反序列化|[MPS-2019-13103](https://www.oscs1024.com/hd/MPS-2019-13103)|CVE-2019-17531|严重|
|​ hibernate-validator  存在跨站脚本（XSS）漏洞|XSS|[MPS-2019-14389](https://www.oscs1024.com/hd/MPS-2019-14389)|CVE-2019-10219|中危|
|SnakeYAML <1.26 存在 Billion laughs 漏洞|拒绝服务|[MPS-2019-16129](https://www.oscs1024.com/hd/MPS-2019-16129)|CVE-2017-18640|高危|
|Apache Tomcat 授权问题漏洞|会话固定|[MPS-2019-16906](https://www.oscs1024.com/hd/MPS-2019-16906)|CVE-2019-17563|高危|
|Apache Tomcat 特权提升漏洞|权限管理不当|[MPS-2019-16926](https://www.oscs1024.com/hd/MPS-2019-16926)|CVE-2019-12418|高危|
|Apache Tomcat拒绝服务漏洞|拒绝服务|[MPS-2019-3894](https://www.oscs1024.com/hd/MPS-2019-3894)|CVE-2019-0199|高危|
|Apache Tomcat 操作系统命令注入漏洞|OS命令注入|[MPS-2019-4006](https://www.oscs1024.com/hd/MPS-2019-4006)|CVE-2019-0232|高危|
|FasterXML jackson-databind 反序列化漏洞(mysql gadget绕过)|反序列化|[MPS-2019-5442](https://www.oscs1024.com/hd/MPS-2019-5442)|CVE-2019-12086|高危|
|Apache Tomcat 跨站脚本漏洞|XSS|[MPS-2019-5944](https://www.oscs1024.com/hd/MPS-2019-5944)|CVE-2019-0221|中危|
|FasterXML jackson-databind 反序列化漏洞(jdom gadget绕过)|反序列化|[MPS-2019-6867](https://www.oscs1024.com/hd/MPS-2019-6867)|CVE-2019-12814|中危|
|Apache Tomcat 资源管理错误漏洞|加锁机制不恰当|[MPS-2019-7027](https://www.oscs1024.com/hd/MPS-2019-7027)|CVE-2019-10072|高危|
|FasterXML jackson-databind 反序列化漏洞(logback-classic gadget绕过)|反序列化|[MPS-2019-7047](https://www.oscs1024.com/hd/MPS-2019-7047)|CVE-2019-12384|中危|
|FasterXML jackson-databind 反序列化漏洞(ehcache gadget绕过)|动态确定对象属性修改的控制不恰当|[MPS-2019-8717](https://www.oscs1024.com/hd/MPS-2019-8717)|CVE-2019-14379|严重|
|FasterXML jackson-databind 信息泄露漏洞(logback gadget绕过)|反序列化|[MPS-2019-8770](https://www.oscs1024.com/hd/MPS-2019-8770)|CVE-2019-14439|高危|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|FasterXML jackson-databind反序列化漏洞(net.sf.ehcache gadget绕过)|反序列化|[MPS-2020-0063](https://www.oscs1024.com/hd/MPS-2020-0063)|CVE-2019-20330|严重|
|Pivotal Spring Framework <5.2.3.RELEASE 反射文件下载 (RFD) 漏洞|下载代码缺少完整性检查|[MPS-2020-0902](https://www.oscs1024.com/hd/MPS-2020-0902)|CVE-2020-5398|高危|
|FasterXML jackson-databind反序列化漏洞(Anteros-DBCP gadget绕过)|反序列化|[MPS-2020-11987](https://www.oscs1024.com/hd/MPS-2020-11987)|CVE-2020-24616|高危|
|FasterXML jackson-databind 反序列化漏洞(pastdev gadget绕过)|反序列化|[MPS-2020-13151](https://www.oscs1024.com/hd/MPS-2020-13151)|CVE-2020-24750|高危|
|Pivotal Spring Framework 反射文件下载 (RFD) 漏洞|路径遍历|[MPS-2020-13322](https://www.oscs1024.com/hd/MPS-2020-13322)|CVE-2020-5421|中危|
|Apache Tomcat HTTP请求走私漏洞|HTTP请求走私|[MPS-2020-15344](https://www.oscs1024.com/hd/MPS-2020-15344)|CVE-2020-13943|中危|
|Eclipse Jetty 权限提升漏洞|权限、特权和访问控制|[MPS-2020-15633](https://www.oscs1024.com/hd/MPS-2020-15633)|CVE-2020-27216|高危|
|FasterXML jackson-databind 代码问题漏洞|XXE|[MPS-2020-17358](https://www.oscs1024.com/hd/MPS-2020-17358)|CVE-2020-25649|高危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2020-17486](https://www.oscs1024.com/hd/MPS-2020-17486)|CVE-2020-17527|高危|
|Eclipse Jetty HTTP 请求走私漏洞|在释放前未清除敏感信息|[MPS-2020-17594](https://www.oscs1024.com/hd/MPS-2020-17594)|CVE-2020-27218|中危|
|FasterXML jackson-databind 反序列化漏洞(commons-dbcp2 gadget绕过)|反序列化|[MPS-2020-17696](https://www.oscs1024.com/hd/MPS-2020-17696)|CVE-2020-35490|高危|
|FasterXML jackson-databind 反序列化漏洞(commons-dbcp2 gadget绕过)|反序列化|[MPS-2020-17697](https://www.oscs1024.com/hd/MPS-2020-17697)|CVE-2020-35491|高危|
|FasterXML jackson-databind 反序列化漏洞(glassfish gadget绕过)|反序列化|[MPS-2020-18089](https://www.oscs1024.com/hd/MPS-2020-18089)|CVE-2020-35728|高危|
|FasterXML jackson-databind 反序列化漏洞(xbean-reflect gadget绕过)|反序列化|[MPS-2020-2030](https://www.oscs1024.com/hd/MPS-2020-2030)|CVE-2020-8840|严重|
|FasterXML jackson-databind 反序列化漏洞(ignite-jta gadget绕过)|反序列化|[MPS-2020-24779](https://www.oscs1024.com/hd/MPS-2020-24779)|CVE-2020-10650|高危|
|Dropwizard-Validation 注入漏洞|注入|[MPS-2020-2828](https://www.oscs1024.com/hd/MPS-2020-2828)|CVE-2020-5245|高危|
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
|FasterXML jackson-databind 反序列化漏洞(spring-aop gadget绕过)|反序列化|[MPS-2020-5138](https://www.oscs1024.com/hd/MPS-2020-5138)|CVE-2020-11619|高危|
|FasterXML jackson-databind 反序列化漏洞(commons-jelly gadget绕过)|反序列化|[MPS-2020-5139](https://www.oscs1024.com/hd/MPS-2020-5139)|CVE-2020-11620|高危|
|dropwizard-validation 注入漏洞|注入|[MPS-2020-5322](https://www.oscs1024.com/hd/MPS-2020-5322)|CVE-2020-11002|高危|
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
|FasterXML jackson-databind 反序列化漏洞(javax.swing gadget绕过)|反序列化|[MPS-2021-1625](https://www.oscs1024.com/hd/MPS-2021-1625)|CVE-2021-20190|高危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-1722](https://www.oscs1024.com/hd/MPS-2021-1722)|CVE-2021-24122|中危|
|Spring Framework <5.3.14 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18854](https://www.oscs1024.com/hd/MPS-2021-18854)|CVE-2021-22060|中危|
|Pivotal Spring Framework 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18890](https://www.oscs1024.com/hd/MPS-2021-18890)|CVE-2021-22096|中危|
|Apache Tomcat 信息泄露漏洞|HTTP请求走私|[MPS-2021-2309](https://www.oscs1024.com/hd/MPS-2021-2309)|CVE-2021-25122|高危|
|Apache Tomcat 远程代码执行漏洞|代码注入|[MPS-2021-2466](https://www.oscs1024.com/hd/MPS-2021-2466)|CVE-2021-25329|高危|
|Eclipse Jetty <11.0.1 拒绝服务漏洞|拒绝服务|[MPS-2021-2571](https://www.oscs1024.com/hd/MPS-2021-2571)|CVE-2020-27223|中危|
|Apache Tomcat 拒绝服务漏洞|拒绝服务|[MPS-2021-31848](https://www.oscs1024.com/hd/MPS-2021-31848)|CVE-2021-41079|高危|
|Quality Open Software logback JNDI注入漏洞|反序列化|[MPS-2021-33911](https://www.oscs1024.com/hd/MPS-2021-33911)|CVE-2021-42550|中危|
|Apache Tomcat 条件竞争漏洞|竞争条件|[MPS-2021-37218](https://www.oscs1024.com/hd/MPS-2021-37218)|CVE-2021-43980|低危|
|Eclipse Jetty 资源管理错误漏洞|对异常条件的处理不恰当|[MPS-2021-3864](https://www.oscs1024.com/hd/MPS-2021-3864)|CVE-2021-28165|高危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|Spring Framework权限许可和访问控制问题漏洞|权限管理不当|[MPS-2021-7485](https://www.oscs1024.com/hd/MPS-2021-7485)|CVE-2021-22118|高危|
|Jakarta Expression Language <=3.0.3 存在输入验证错误漏洞|表达式语言注入|[MPS-2021-7671](https://www.oscs1024.com/hd/MPS-2021-7671)|CVE-2021-28170|中危|
|Eclipse Jetty 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-8397](https://www.oscs1024.com/hd/MPS-2021-8397)|CVE-2021-28169|中危|
|Eclipse Jetty 存在信息泄露漏洞|不充分的会话过期机制|[MPS-2021-8884](https://www.oscs1024.com/hd/MPS-2021-8884)|CVE-2021-34428|低危|
|Apache Tomcat 环境问题漏洞|HTTP请求走私|[MPS-2021-9711](https://www.oscs1024.com/hd/MPS-2021-9711)|CVE-2021-33037|中危|
|Vmware Spring Framework 安全漏洞|不加限制或调节的资源分配|[MPS-2022-1080](https://www.oscs1024.com/hd/MPS-2022-1080)|CVE-2022-22950|中危|
|Pivotal Spring Framework 安全限制绕过漏洞|大小写敏感处理不恰当|[MPS-2022-1098](https://www.oscs1024.com/hd/MPS-2022-1098)|CVE-2022-22968|中危|
|Spring Framework spring-beans 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1101](https://www.oscs1024.com/hd/MPS-2022-1101)|CVE-2022-22970|中危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|org.glassfish.jersey.media:jersey-media-jaxb <2.31 存在XXE漏洞|XML实体扩展|[MPS-2022-12234](https://www.oscs1024.com/hd/MPS-2022-12234)||高危|
|Logback SSL证书校验不当漏洞|中间人攻击|[MPS-2022-12411](https://www.oscs1024.com/hd/MPS-2022-12411)||中危|
|com.fasterxml.jackson.core:jackson-databind 存在反序列化漏洞|反序列化|[MPS-2022-12433](https://www.oscs1024.com/hd/MPS-2022-12433)||高危|
|Eclipse Jetty URI注入漏洞|注入|[MPS-2022-18060](https://www.oscs1024.com/hd/MPS-2022-18060)|CVE-2022-2047|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|spring-boot <2.2.11.RELEASE 存在目录劫持漏洞|将资源暴露给错误范围|[MPS-2022-6780](https://www.oscs1024.com/hd/MPS-2022-6780)|CVE-2022-27772|高危|
|spring-beans 远程代码执行漏洞(Spring4Shell)|表达式语言注入|[MPS-2022-6820](https://www.oscs1024.com/hd/MPS-2022-6820)|CVE-2022-22965|严重|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Eclipse Jetty 资源管理错误漏洞|拒绝服务|[MPS-2023-4997](https://www.oscs1024.com/hd/MPS-2023-4997)|CVE-2023-26048|中危|
|Eclipse Jetty 信息泄露漏洞|XSS|[MPS-2023-4998](https://www.oscs1024.com/hd/MPS-2023-4998)|CVE-2023-26049|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Apache Tomcat FORM 重定向漏洞|跨站重定向|[MPS-uy56-j8e4](https://www.oscs1024.com/hd/MPS-uy56-j8e4)|CVE-2023-41080|低危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.apache.tomcat.embed:tomcat-embed-core|8.5.31|11.0.0-m6|间接依赖|强烈建议修复|C:2|H:11|M:7|L:2|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.21|11.0.0-m6|间接依赖|强烈建议修复|C:1|H:8|M:4|L:2|
|org.springframework:spring-web|5.0.7.RELEASE|6.0.0|间接依赖|建议修复|C:1|H:3|M:1|L:0|
|org.springframework:spring-context|5.0.7.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|ch.qos.logback:logback-core|1.2.3|1.2.8|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.eclipse.jetty:jetty-io|9.4.18.v20190429|11.0.10|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.9.9|2.14.0-rc1|间接依赖|建议修复|C:14|H:35|M:5|L:0|
|org.springframework:spring-web|5.1.8.RELEASE|6.0.0|间接依赖|建议修复|C:1|H:2|M:1|L:0|
|org.springframework:spring-beans|5.1.8.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.yaml:snakeyaml|1.19|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|org.eclipse.jetty:jetty-http|9.4.18.v20190429|11.0.10|间接依赖|建议修复|C:0|H:0|M:1|L:1|
|io.dropwizard:dropwizard-validation|1.3.16|2.0.3|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|org.eclipse.jetty:jetty-webapp|9.4.18.v20190429|11.0.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.9.6|2.14.0-rc1|间接依赖|建议修复|C:21|H:36|M:5|L:0|
|org.glassfish.jersey.media:jersey-media-jaxb|2.25.1|2.31|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-server|9.4.18.v20190429|12.0.0.beta0|间接依赖|建议修复|C:0|H:0|M:3|L:1|
|com.fasterxml.jackson.core:jackson-databind|2.9.10.1|2.14.0-rc1|间接依赖|建议修复|C:7|H:33|M:3|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.15.2||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.yaml:snakeyaml|1.23|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|org.springframework:spring-beans|5.0.7.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework.boot:spring-boot|2.0.3.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot|2.1.6.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-context|5.1.8.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|24.1.1-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:1|
|org.springframework:spring-expression|5.1.8.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.springframework:spring-expression|5.0.7.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.springframework:spring-core|5.0.7.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-core|5.1.8.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|31.1-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.0.3.RELEASE|3.0.7|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|commons-io:commons-io|1.3.2|2.7|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-codec:commons-codec|1.11|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.hibernate.validator:hibernate-validator|6.0.17.Final|6.1.3.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.9.6|2.9.8|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.hibernate:hibernate-validator|5.4.3.Final|6.1.3.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.1.6.RELEASE|3.0.7|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-servlets|9.4.18.v20190429|11.0.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.glassfish:javax.el|3.0.0||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.hibernate.validator:hibernate-validator|6.0.10.Final|6.1.3.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|184|Low|
|自定义许可证|24|Low|
|MIT|11|Low|
|EPL-1.0|5|Low|
|BSD-2-Clause|1|Low|
|LGPL-2.1|1|Medium|
|MPL-1.1|1|Low|
|EPL-2.0|1|Low|
|BSD-3-Clause|1|Low|
|CDDL-1.1|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|::jib-plugins-common||直接依赖|maven|
|org.apache.commons:commons-lang3|3.8.1|间接依赖|maven|
|com.papertrail:profiler|1.0.2|间接依赖|maven|
|org.glassfish.jersey.bundles.repackaged:jersey-guava|2.25.1|间接依赖|maven|
|org.apache.maven:maven-artifact|3.9.3|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|8.5.31|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.1|间接依赖|maven|
|javax.servlet:javax.servlet-api|3.1.0|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.25|间接依赖|maven|
|com.fasterxml.jackson:jackson-bom|2.15.2|直接依赖|maven|
|org.springframework:spring-beans|5.1.8.RELEASE|间接依赖|maven|
|ch.qos.logback:logback-access|1.2.3|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.5-4|直接依赖|maven|
|net.sourceforge.argparse4j:argparse4j|0.8.1|间接依赖|maven|
|com.google.code.gson:gson|2.9.0|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.21|间接依赖|maven|
|org.glassfish.hk2.external:javax.inject|2.5.0-b32|间接依赖|maven|
|de.thomaskrille:dropwizard-template-config|1.5.0|直接依赖|maven|
|io.dropwizard:dropwizard-lifecycle|1.3.16|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.9.10.1|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.15.2|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|8.5.31|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|2.8|间接依赖|maven|
|io.dropwizard:dropwizard-jersey|1.3.16|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-client|9.4.18.v20190429|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.9.6|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet-core|2.25.1|间接依赖|maven|
|com.google.guava:guava|24.1.1-jre|间接依赖|maven|
|org.springframework:spring-context|5.0.7.RELEASE|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|8.5.31|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.0.3.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.9.10|间接依赖|maven|
|commons-io:commons-io|1.3.2|直接依赖|maven|
|io.dropwizard:dropwizard-logging|1.3.16|间接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.4.18.v20190429|间接依赖|maven|
|javax.validation:validation-api|2.0.1.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.0.3.RELEASE|间接依赖|maven|
|javax.inject:javax.inject|1|直接依赖|maven|
|org.glassfish.jersey.ext:jersey-bean-validation|2.25.1|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.21|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.9.6|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.15|间接依赖|maven|
|org.springframework:spring-jcl|5.0.7.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.9.10|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.1.6.RELEASE|间接依赖|maven|
|org.eclipse.jetty:jetty-http|9.4.18.v20190429|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-afterburner|2.9.10|间接依赖|maven|
|org.apache.maven.resolver:maven-resolver-named-locks|1.9.13|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.21|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.3.0.Final|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.14|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.26|间接依赖|maven|
|io.dropwizard:dropwizard-metrics|1.3.16|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|4.0.5|间接依赖|maven|
|org.glassfish.jersey.core:jersey-common|2.25.1|间接依赖|maven|
|org.apache.maven:maven-model-builder|3.9.3|直接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.0.3.RELEASE|间接依赖|maven|
|org.apache.maven.resolver:maven-resolver-util|1.9.13|直接依赖|maven|
|com.google.cloud.tools:jib-gradle-plugin-extension-api|0.4.0|直接依赖|maven|
|org.springframework:spring-beans|5.0.7.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.9.9|间接依赖|maven|
|org.checkerframework:checker-compat-qual|2.0.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.9.0|间接依赖|maven|
|com.google.auth:google-auth-library-credentials|1.10.0|间接依赖|maven|
|org.javassist:javassist|3.24.1-GA|间接依赖|maven|
|org.springframework:spring-aop|5.1.8.RELEASE|间接依赖|maven|
|com.google.cloud.tools:jib-maven-plugin-extension-api|0.4.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.9.9|间接依赖|maven|
|io.dropwizard.metrics:metrics-servlets|4.0.5|间接依赖|maven|
|org.apache.maven:maven-settings|3.9.3|直接依赖|maven|
|commons-codec:commons-codec|1.11|间接依赖|maven|
|org.springframework.boot:spring-boot|2.0.3.RELEASE|间接依赖|maven|
|org.eclipse.jetty.toolchain.setuid:jetty-setuid-java|1.0.3|间接依赖|maven|
|com.google.cloud.tools:jib-plugins-extension-common|0.2.0|直接依赖|maven|
|org.eclipse.jetty.websocket:websocket-servlet|9.4.18.v20190429|间接依赖|maven|
|org.springframework:spring-core|5.1.8.RELEASE|间接依赖|maven|
|io.dropwizard.metrics:metrics-jvm|4.0.5|间接依赖|maven|
|io.dropwizard:dropwizard-servlets|1.3.16|间接依赖|maven|
|com.google.guava:guava|32.0.0-jre|直接依赖|maven|
|org.glassfish.hk2:hk2-utils|2.5.0-b32|间接依赖|maven|
|org.glassfish.jersey.core:jersey-server|2.25.1|间接依赖|maven|
|org.springframework.boot:spring-boot|2.1.6.RELEASE|间接依赖|maven|
|org.springframework:spring-web|5.1.8.RELEASE|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.10.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.9.10|间接依赖|maven|
|org.glassfish.jersey.core:jersey-client|2.25.1|间接依赖|maven|
|com.google.inject:guice|5.1.0|直接依赖|maven|
|com.google.cloud.tools:tiny-test-lib|0.0.1-SNAPSHOT|直接依赖|maven|
|org.eclipse.jetty:jetty-continuation|9.4.18.v20190429|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.3|间接依赖|maven|
|com.google.http-client:google-http-client-gson|1.42.2|间接依赖|maven|
|org.checkerframework:checker-qual|3.33.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.1.6.RELEASE|间接依赖|maven|
|io.dropwizard.metrics:metrics-logback|4.0.5|间接依赖|maven|
|org.apache.maven:maven-core|3.9.3|直接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet|2.25.1|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.11.2|间接依赖|maven|
|:No dependencies||直接依赖|maven|
|com.fasterxml:classmate|1.4.0|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.9.10|间接依赖|maven|
|org.apache.maven:maven-model|3.9.3|直接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|org.apache.commons:commons-compress|1.21|直接依赖|maven|
|info.picocli:picocli|4.7.4|直接依赖|maven|
|io.dropwizard:dropwizard-jackson|1.3.16|间接依赖|maven|
|com.jib.test:lib|1.0.0.TEST-SNAPSHOT|直接依赖|maven|
|org.apache.maven:maven-plugin-api|3.9.3|直接依赖|maven|
|com.google.guava:guava|32.0.1-jre|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.18.v20190429|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.26|间接依赖|maven|
|org.codehaus.plexus:plexus-interpolation|1.26|直接依赖|maven|
|com.google.guava:guava|31.1-jre|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.9.6|间接依赖|maven|
|org.hibernate:hibernate-validator|5.4.3.Final|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.9.10|间接依赖|maven|
|org.eclipse.jetty:jetty-client|9.4.18.v20190429|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.15.2|间接依赖|maven|
|com.google.http-client:google-http-client-apache-v2|1.42.2|直接依赖|maven|
|org.codehaus.plexus:plexus-utils|3.5.1|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.9.10|间接依赖|maven|
|joda-time:joda-time|2.10.1|间接依赖|maven|
|io.dropwizard.metrics:metrics-jmx|4.0.5|间接依赖|maven|
|io.dropwizard.metrics:metrics-annotation|4.0.5|间接依赖|maven|
|org.apache.maven:maven-repository-metadata|3.9.3|直接依赖|maven|
|com.google.http-client:google-http-client|1.42.2|直接依赖|maven|
|io.dropwizard:dropwizard-request-logging|1.3.16|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.0.17.Final|间接依赖|maven|
|org.eclipse.jetty:jetty-server|9.4.18.v20190429|间接依赖|maven|
|io.dropwizard:dropwizard-jetty|1.3.16|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.1.6.RELEASE|直接依赖|maven|
|com.google.errorprone:error||间接依赖|maven|
|org.glassfish.jersey.media:jersey-media-jaxb|2.25.1|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.9.10|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.10.0|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.1|间接依赖|maven|
|org.apache.maven:maven-builder-support|3.9.3|直接依赖|maven|
|org.apache.maven:maven-resolver-provider|3.9.3|直接依赖|maven|
|org.apache.commons:commons-text|1.10.0|直接依赖|maven|
|javax.annotation:javax.annotation-api|1.2|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.15.2|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.9.9|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.9.9|间接依赖|maven|
|io.dropwizard.metrics:metrics-jetty9|4.0.5|间接依赖|maven|
|org.slf4j:log4j-over-slf4j|1.7.26|间接依赖|maven|
|org.yaml:snakeyaml|1.19|间接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|com.fasterxml:classmate|1.3.4|间接依赖|maven|
|io.dropwizard.metrics:metrics-jersey2|4.0.5|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.9.10|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.11.2|间接依赖|maven|
|com.google.cloud.tools:jib-build-plan|0.4.0|直接依赖|maven|
|org.codehaus.plexus:plexus-classworlds|2.7.0|直接依赖|maven|
|org.springframework:spring-aop|5.0.7.RELEASE|间接依赖|maven|
|org.springframework:spring-expression|5.1.8.RELEASE|间接依赖|maven|
|org.eclipse.sisu:org.eclipse.sisu.inject|0.3.5|直接依赖|maven|
|::jib-core||直接依赖|maven|
|org.glassfish.hk2:hk2-api|2.5.0-b32|间接依赖|maven|
|io.dropwizard:dropwizard-util|1.3.16|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.9.6|间接依赖|maven|
|org.codehaus.plexus:plexus-cipher|2.0|间接依赖|maven|
|org.codehaus.plexus:plexus-sec-dispatcher|2.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.1.6.RELEASE|间接依赖|maven|
|org.glassfish.hk2:osgi-resource-locator|1.0.1|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.9.9|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.0.3.RELEASE|间接依赖|maven|
|org.eclipse.jetty:jetty-security|9.4.18.v20190429|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.15.2|直接依赖|maven|
|io.dropwizard:dropwizard-configuration|1.3.16|间接依赖|maven|
|org.glassfish:javax.el|3.0.0|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-common|9.4.18.v20190429|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.0.10.Final|间接依赖|maven|
|org.apache.maven.shared:maven-shared-utils|3.3.4|直接依赖|maven|
|com.google.guava:failureaccess|1.0.1|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.9.6|间接依赖|maven|
|org.glassfish.hk2.external:aopalliance-repackaged|2.5.0-b32|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.15.2|直接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.18.v20190429|间接依赖|maven|
|org.springframework:spring-expression|5.0.7.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.0.3.RELEASE|间接依赖|maven|
|org.apache.commons:commons-text|1.2|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-joda|2.9.10|间接依赖|maven|
|javax.validation:validation-api|1.1.0.Final|间接依赖|maven|
|org.slf4j:slf4j-simple|1.7.28|直接依赖|maven|
|org.eclipse.jetty:jetty-webapp|9.4.18.v20190429|间接依赖|maven|
|com.example:shared-library|0.1.0|直接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|直接依赖|maven|
|org.springframework:spring-jcl|5.1.8.RELEASE|间接依赖|maven|
|org.springframework:spring-core|5.0.7.RELEASE|间接依赖|maven|
|org.eclipse.jetty:jetty-xml|9.4.18.v20190429|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-guava|2.9.10|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.25|间接依赖|maven|
|io.opencensus:opencensus-api|0.31.1|间接依赖|maven|
|io.dropwizard.metrics:metrics-healthchecks|4.0.5|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|org.eclipse.sisu:org.eclipse.sisu.plexus|0.3.5|直接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|2.1.0|直接依赖|maven|
|org.yaml:snakeyaml|2.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.0.3.RELEASE|直接依赖|maven|
|io.opencensus:opencensus-contrib-http-util|0.31.1|间接依赖|maven|
|org.codehaus.plexus:plexus-component-annotations|2.1.0|直接依赖|maven|
|org.springframework:spring-webmvc|5.1.8.RELEASE|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.26|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.3.2.Final|间接依赖|maven|
|com.google.auto.value:auto-value-annotations|1.9|间接依赖|maven|
|org.ow2.asm:asm|9.5|直接依赖|maven|
|org.yaml:snakeyaml|1.23|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-api|9.4.18.v20190429|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.9.10|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-server|9.4.18.v20190429|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.3|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.18.0|间接依赖|maven|
|io.dropwizard:dropwizard-core|1.3.16|直接依赖|maven|
|io.dropwizard:dropwizard-validation|1.3.16|间接依赖|maven|
|org.glassfish.jersey.ext:jersey-metainf-services|2.25.1|间接依赖|maven|
|org.glassfish.hk2:hk2-locator|2.5.0-b32|间接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.1.6.RELEASE|间接依赖|maven|
|io.dropwizard.metrics:metrics-json|4.0.5|间接依赖|maven|
|org.eclipse.jetty:jetty-servlets|9.4.18.v20190429|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.1.3|间接依赖|maven|
|com.sparkjava:spark-core|2.9.1|直接依赖|maven|
|org.apache.maven:maven-settings-builder|3.9.3|直接依赖|maven|
|org.springframework:spring-context|5.1.8.RELEASE|间接依赖|maven|
|io.grpc:grpc-context|1.27.2|间接依赖|maven|
|org.springframework:spring-webmvc|5.0.7.RELEASE|间接依赖|maven|
|com.google.auth:google-auth-library-oauth2-http|1.10.0|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.1.6.RELEASE|间接依赖|maven|
|org.apache.maven.resolver:maven-resolver-api|1.9.13|直接依赖|maven|
|org.apache.maven.resolver:maven-resolver-spi|1.9.13|直接依赖|maven|
|org.apache.maven.resolver:maven-resolver-impl|1.9.13|直接依赖|maven|
|org.springframework:spring-web|5.0.7.RELEASE|间接依赖|maven|
|javax.ws.rs:javax.ws.rs-api|2.0.1|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)