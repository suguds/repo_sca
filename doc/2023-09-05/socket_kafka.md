# FRANKSTEIN11/socket_kafka安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698758890174070784.svg)](https://www.murphysec.com/console/report/1698758889062580224/1698758890174070784)

仓库描述：websocket + kafka , websocket to chat , kafka to do something you define

仓库地址：[https://github.com/FRANKSTEIN11/socket_kafka](https://github.com/FRANKSTEIN11/socket_kafka)

| star：33 | watch：7 | fork：10 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-05 00:38:43 | 许可证：MIT |
| 最近检测时间：2023-09-05 02:04:42 | 组件总数：64 | 漏洞总数：117 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
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
|FasterXML jackson-databind 代码问题漏洞|XXE|[MPS-2020-17358](https://www.oscs1024.com/hd/MPS-2020-17358)|CVE-2020-25649|高危|
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
|JetBrains Kotlin <1.4.21 不正确的默认权限漏洞|缺省权限不正确|[MPS-2021-1082](https://www.oscs1024.com/hd/MPS-2021-1082)|CVE-2020-29582|中危|
|FasterXML jackson-databind 反序列化漏洞(javax.swing gadget绕过)|反序列化|[MPS-2021-1625](https://www.oscs1024.com/hd/MPS-2021-1625)|CVE-2021-20190|高危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-1722](https://www.oscs1024.com/hd/MPS-2021-1722)|CVE-2021-24122|中危|
|Spring Framework <5.3.14 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18854](https://www.oscs1024.com/hd/MPS-2021-18854)|CVE-2021-22060|中危|
|Pivotal Spring Framework 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18890](https://www.oscs1024.com/hd/MPS-2021-18890)|CVE-2021-22096|中危|
|Apache Tomcat 信息泄露漏洞|HTTP请求走私|[MPS-2021-2309](https://www.oscs1024.com/hd/MPS-2021-2309)|CVE-2021-25122|高危|
|Apache Tomcat 远程代码执行漏洞|代码注入|[MPS-2021-2466](https://www.oscs1024.com/hd/MPS-2021-2466)|CVE-2021-25329|高危|
|Apache Tomcat 拒绝服务漏洞|拒绝服务|[MPS-2021-31848](https://www.oscs1024.com/hd/MPS-2021-31848)|CVE-2021-41079|高危|
|Quality Open Software logback JNDI注入漏洞|反序列化|[MPS-2021-33911](https://www.oscs1024.com/hd/MPS-2021-33911)|CVE-2021-42550|中危|
|Apache Tomcat 条件竞争漏洞|竞争条件|[MPS-2021-37218](https://www.oscs1024.com/hd/MPS-2021-37218)|CVE-2021-43980|低危|
|Spring Framework权限许可和访问控制问题漏洞|权限管理不当|[MPS-2021-7485](https://www.oscs1024.com/hd/MPS-2021-7485)|CVE-2021-22118|高危|
|Apache Tomcat 环境问题漏洞|HTTP请求走私|[MPS-2021-9711](https://www.oscs1024.com/hd/MPS-2021-9711)|CVE-2021-33037|中危|
|Hutool 存在中间人劫持漏洞|证书验证不恰当|[MPS-2022-1000](https://www.oscs1024.com/hd/MPS-2022-1000)|CVE-2022-22885|中危|
|Vmware Spring Framework 安全漏洞|不加限制或调节的资源分配|[MPS-2022-1080](https://www.oscs1024.com/hd/MPS-2022-1080)|CVE-2022-22950|中危|
|Pivotal Spring Framework 安全限制绕过漏洞|大小写敏感处理不恰当|[MPS-2022-1098](https://www.oscs1024.com/hd/MPS-2022-1098)|CVE-2022-22968|中危|
|Pivotal Spring Framework 拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1100](https://www.oscs1024.com/hd/MPS-2022-1100)|CVE-2022-22971|中危|
|Spring Framework spring-beans 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1101](https://www.oscs1024.com/hd/MPS-2022-1101)|CVE-2022-22970|中危|
|Logback SSL证书校验不当漏洞|中间人攻击|[MPS-2022-12411](https://www.oscs1024.com/hd/MPS-2022-12411)||中危|
|com.fasterxml.jackson.core:jackson-databind 存在反序列化漏洞|反序列化|[MPS-2022-12433](https://www.oscs1024.com/hd/MPS-2022-12433)||高危|
|JetBrains Kotlin <1.6.0 存在锁定不当漏洞|加锁机制不恰当|[MPS-2022-3233](https://www.oscs1024.com/hd/MPS-2022-3233)|CVE-2022-24329|中危|
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
|Hutool 存在拒绝服务漏洞|越界写入|[MPS-2022-64976](https://www.oscs1024.com/hd/MPS-2022-64976)|CVE-2022-45688|中危|
|Hutool 存在拒绝服务漏洞|越界写入|[MPS-2022-64977](https://www.oscs1024.com/hd/MPS-2022-64977)|CVE-2022-45689|中危|
|Hutool 存在拒绝服务漏洞|越界写入|[MPS-2022-64978](https://www.oscs1024.com/hd/MPS-2022-64978)|CVE-2022-45690|中危|
|spring-boot <2.2.11.RELEASE 存在目录劫持漏洞|将资源暴露给错误范围|[MPS-2022-6780](https://www.oscs1024.com/hd/MPS-2022-6780)|CVE-2022-27772|高危|
|spring-beans 远程代码执行漏洞(Spring4Shell)|表达式语言注入|[MPS-2022-6820](https://www.oscs1024.com/hd/MPS-2022-6820)|CVE-2022-22965|严重|
|Hutool zip 拒绝服务漏洞||[MPS-2022-68308](https://www.oscs1024.com/hd/MPS-2022-68308)|CVE-2022-4565|中危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|hutool 表达式注入漏洞|SQL注入|[MPS-2023-2459](https://www.oscs1024.com/hd/MPS-2023-2459)|CVE-2023-24163|严重|
|hutool 存在反序列化漏洞|反序列化|[MPS-2023-2460](https://www.oscs1024.com/hd/MPS-2023-2460)|CVE-2023-24162|高危|
|Apache Kafka Connect 模块JNDI注入漏洞|反序列化|[MPS-2023-3834](https://www.oscs1024.com/hd/MPS-2023-3834)|CVE-2023-25194|高危|
|【存在争议】MybatisPlus <= 3.5.3.1 TenantPlugin 组件 存在 sql 注入漏洞|SQL注入|[MPS-2023-3977](https://www.oscs1024.com/hd/MPS-2023-3977)|CVE-2023-25330|高危|
|hutool 存在任意代码执行漏洞|代码注入|[MPS-2023-7335](https://www.oscs1024.com/hd/MPS-2023-7335)||严重|
|Hutool createTempFile函数敏感信息泄漏漏洞|未授权敏感信息泄露|[MPS-4soz-eyma](https://www.oscs1024.com/hd/MPS-4soz-eyma)|CVE-2023-33695|中危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|hutool <=5.8.17 存在SPEL命令执行风险|代码注入|[MPS-jdrq-1ywv](https://www.oscs1024.com/hd/MPS-jdrq-1ywv)||高危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|Apache Tomcat FORM 重定向漏洞|跨站重定向|[MPS-uy56-j8e4](https://www.oscs1024.com/hd/MPS-uy56-j8e4)|CVE-2023-41080|低危|
|HuTool XML外部实体注入漏洞|XXE|[MPS-xd3s-4gev](https://www.oscs1024.com/hd/MPS-xd3s-4gev)|CVE-2023-3276|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.apache.tomcat.embed:tomcat-embed-core|9.0.16|11.0.0-m6|间接依赖|强烈建议修复|C:1|H:10|M:5|L:2|
|cn.hutool:hutool-all|5.7.16|5.8.20|直接依赖|强烈建议修复|C:2|H:2|M:7|L:0|
|org.springframework:spring-messaging|5.1.5.RELEASE|5.3.20|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-beans|5.1.5.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.xerial.snappy:snappy-java|1.1.8.1|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|ch.qos.logback:logback-core|1.2.3|1.2.8|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.yaml:snakeyaml|1.23|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|org.springframework.boot:spring-boot|2.1.3.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-web|5.1.5.RELEASE|6.0.0|间接依赖|建议修复|C:1|H:2|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.9.8|2.14.0-rc1|间接依赖|建议修复|C:14|H:36|M:5|L:0|
|org.apache.kafka:kafka-clients|2.8.0|3.4.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-context|5.1.5.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.baomidou:mybatis-plus-extension|3.5.2||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.1.3.RELEASE|3.0.7|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-expression|5.1.5.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.springframework:spring-core|5.1.5.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.jetbrains.kotlin:kotlin-stdlib|1.2.71|1.6.0|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.hibernate.validator:hibernate-validator|6.0.14.Final|6.1.3.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|54|Low|
|EPL-1.0|2|Low|
|MIT|4|Low|
|自定义许可证|2|Low|
|BSD-2-Clause|1|Low|
|JSON|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.yaml:snakeyaml|1.23|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.3|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.1.3.RELEASE|间接依赖|maven|
|org.projectlombok:lombok|1.18.6|直接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.11.2|间接依赖|maven|
|org.springframework:spring-tx|5.1.5.RELEASE|间接依赖|maven|
|com.baomidou:mybatis-plus-core|3.5.2|间接依赖|maven|
|cn.hutool:hutool-all|5.7.16|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.9.8|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.16|间接依赖|maven|
|com.zaxxer:HikariCP|3.2.0|间接依赖|maven|
|com.github.luben:zstd-jni|1.4.9-1|间接依赖|maven|
|org.springframework:spring-web|5.1.5.RELEASE|间接依赖|maven|
|org.springframework:spring-messaging|5.1.5.RELEASE|直接依赖|maven|
|org.springframework:spring-core|5.1.5.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.9.8|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.2.71|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.2.71|间接依赖|maven|
|com.baomidou:mybatis-plus-extension|3.5.2|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.2.71|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.3.2.Final|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.0.14.Final|间接依赖|maven|
|org.springframework.boot:spring-boot|2.1.3.RELEASE|间接依赖|maven|
|org.springframework:spring-jcl|5.1.5.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.1.3.RELEASE|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.1.3.RELEASE|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|javax.validation:validation-api|2.0.1.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.9.8|间接依赖|maven|
|org.springframework:spring-beans|5.1.5.RELEASE|间接依赖|maven|
|org.lz4:lz4-java|1.7.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.1.3.RELEASE|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.25|间接依赖|maven|
|org.mybatis:mybatis|3.5.10|间接依赖|maven|
|org.java-websocket:Java-WebSocket|1.5.2|直接依赖|maven|
|org.mybatis:mybatis-spring|2.0.7|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.1.3.RELEASE|间接依赖|maven|
|com.baomidou:mybatis-plus-boot-starter|3.5.2|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.9.8|间接依赖|maven|
|com.fasterxml:classmate|1.4.0|间接依赖|maven|
|org.springframework:spring-websocket|5.1.5.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.9.8|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.9.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-websocket|2.1.3.RELEASE|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.16|间接依赖|maven|
|org.json:json|20210307|直接依赖|maven|
|org.springframework:spring-jdbc|5.1.5.RELEASE|间接依赖|maven|
|org.springframework:spring-context|5.1.5.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.1.3.RELEASE|间接依赖|maven|
|org.springframework:spring-expression|5.1.5.RELEASE|间接依赖|maven|
|org.apache.kafka:kafka-clients|2.8.0|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.1.3.RELEASE|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.2.71|间接依赖|maven|
|com.baomidou:mybatis-plus-annotation|3.5.2|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.11.2|间接依赖|maven|
|org.springframework:spring-webmvc|5.1.5.RELEASE|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.16|间接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.25|间接依赖|maven|
|com.github.jsqlparser:jsqlparser|4.4|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.1|间接依赖|maven|
|com.baomidou:mybatis-plus|3.5.2|间接依赖|maven|
|org.springframework:spring-aop|5.1.5.RELEASE|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.3|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)