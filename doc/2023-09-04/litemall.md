# linlinjava/litemall安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698396633317556224.svg)](https://www.murphysec.com/console/report/1698396633246253056/1698396633317556224)

仓库描述：又一个小商城。litemall = Spring Boot后端 + Vue管理员前端 + 微信小程序用户前端 + Vue用户移动端

仓库地址：[https://github.com/linlinjava/litemall](https://github.com/linlinjava/litemall)

| star：18324 | watch：729 | fork：7053 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-07-30 13:35:49 | 许可证：MIT |
| 最近检测时间：2023-09-04 02:06:11 | 组件总数：143 | 漏洞总数：135 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|多款Cisco产品Apache Commons Collections库任意代码执行漏洞|反序列化|[MPS-2015-6277](https://www.oscs1024.com/hd/MPS-2015-6277)|CVE-2015-6420|高危|
|多款Red Hat产品代码问题漏洞|反序列化|[MPS-2017-12638](https://www.oscs1024.com/hd/MPS-2017-12638)|CVE-2015-7501|严重|
|kaptcha Random随机性不足漏洞|使用不充分的随机数|[MPS-2018-13971](https://www.oscs1024.com/hd/MPS-2018-13971)|CVE-2018-18531|严重|
|FasterXML jackson-databind 反序列化漏洞(HikariCP gadget绕过)|反序列化|[MPS-2019-11529](https://www.oscs1024.com/hd/MPS-2019-11529)|CVE-2019-14540|严重|
|FasterXML jackson-databind 反序列化漏洞(HikariCP gadget绕过)|反序列化|[MPS-2019-11533](https://www.oscs1024.com/hd/MPS-2019-11533)|CVE-2019-16335|严重|
|FasterXML jackson-databind 反序列化漏洞(commons-dbcp gadget绕过)|反序列化|[MPS-2019-12479](https://www.oscs1024.com/hd/MPS-2019-12479)|CVE-2019-16942|严重|
|FasterXML jackson-databind 反序列化漏洞(p6spy gadget绕过)|反序列化|[MPS-2019-12480](https://www.oscs1024.com/hd/MPS-2019-12480)|CVE-2019-16943|严重|
|FasterXML jackson-databind 反序列化漏洞(ehcache gadget绕过)|反序列化|[MPS-2019-12676](https://www.oscs1024.com/hd/MPS-2019-12676)|CVE-2019-17267|严重|
|FasterXML jackson-databind 反序列化漏洞(apache-log4j-extras gadget绕过)|反序列化|[MPS-2019-13103](https://www.oscs1024.com/hd/MPS-2019-13103)|CVE-2019-17531|严重|
|SnakeYAML <1.26 存在 Billion laughs 漏洞|拒绝服务|[MPS-2019-16129](https://www.oscs1024.com/hd/MPS-2019-16129)|CVE-2017-18640|高危|
|Apache Tomcat 授权问题漏洞|会话固定|[MPS-2019-16906](https://www.oscs1024.com/hd/MPS-2019-16906)|CVE-2019-17563|高危|
|Apache Tomcat 特权提升漏洞|权限管理不当|[MPS-2019-16926](https://www.oscs1024.com/hd/MPS-2019-16926)|CVE-2019-12418|高危|
|FasterXML jackson-databind 反序列化漏洞(mysql gadget绕过)|反序列化|[MPS-2019-5442](https://www.oscs1024.com/hd/MPS-2019-5442)|CVE-2019-12086|高危|
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
|MyBatis <3.5.6 存在反序列化漏洞|反序列化|[MPS-2020-14133](https://www.oscs1024.com/hd/MPS-2020-14133)|CVE-2020-26945|高危|
|Apache Tomcat HTTP请求走私漏洞|HTTP请求走私|[MPS-2020-15344](https://www.oscs1024.com/hd/MPS-2020-15344)|CVE-2020-13943|中危|
|Apache Shiro 授权问题漏洞|身份验证不当|[MPS-2020-15812](https://www.oscs1024.com/hd/MPS-2020-15812)|CVE-2020-17510|严重|
|Apache HttpClient URI解析错误漏洞|XSS|[MPS-2020-17341](https://www.oscs1024.com/hd/MPS-2020-17341)|CVE-2020-13956|中危|
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
|Apache Shiro 访问控制错误漏洞|身份验证不当|[MPS-2021-1064](https://www.oscs1024.com/hd/MPS-2021-1064)|CVE-2020-17523|严重|
|FasterXML jackson-databind 反序列化漏洞(javax.swing gadget绕过)|反序列化|[MPS-2021-1625](https://www.oscs1024.com/hd/MPS-2021-1625)|CVE-2021-20190|高危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-1722](https://www.oscs1024.com/hd/MPS-2021-1722)|CVE-2021-24122|中危|
|XStream  <1.4.18 存在服务器端伪造请求漏洞||[MPS-2021-17812](https://www.oscs1024.com/hd/MPS-2021-17812)|CVE-2021-39152|高危|
|XStream < 1.4.18 存在服务器端请求伪造漏洞||[MPS-2021-17813](https://www.oscs1024.com/hd/MPS-2021-17813)|CVE-2021-39150|高危|
|XStream 存在拒绝服务漏洞||[MPS-2021-17814](https://www.oscs1024.com/hd/MPS-2021-17814)|CVE-2021-39140|中危|
|XStream < 1.4.18存在任意代码执行漏洞||[MPS-2021-17815](https://www.oscs1024.com/hd/MPS-2021-17815)|CVE-2021-39154|高危|
|XStream < 1.4.18存在任意代码执行漏洞||[MPS-2021-17816](https://www.oscs1024.com/hd/MPS-2021-17816)|CVE-2021-39153|高危|
|XStream < 1.4.18存在任意代码执行漏洞||[MPS-2021-17817](https://www.oscs1024.com/hd/MPS-2021-17817)|CVE-2021-39151|高危|
|XStream < 1.4.18存在任意代码执行漏洞||[MPS-2021-17818](https://www.oscs1024.com/hd/MPS-2021-17818)|CVE-2021-39149|高危|
|XStream <1.4.18存在任意代码执行漏洞||[MPS-2021-17819](https://www.oscs1024.com/hd/MPS-2021-17819)|CVE-2021-39148|高危|
|XStream < 1.4.18存在任意代码执行漏洞||[MPS-2021-17820](https://www.oscs1024.com/hd/MPS-2021-17820)|CVE-2021-39147|高危|
|XStream < 1.4.18 任意代码执行漏洞||[MPS-2021-17821](https://www.oscs1024.com/hd/MPS-2021-17821)|CVE-2021-39146|高危|
|XStream < 1.4.18存在任意代码执行漏洞||[MPS-2021-17822](https://www.oscs1024.com/hd/MPS-2021-17822)|CVE-2021-39145|高危|
|XStream <1.4.18存在任意代码执行漏洞||[MPS-2021-17823](https://www.oscs1024.com/hd/MPS-2021-17823)|CVE-2021-39144|高危|
|XStream < 1.4.18存在任意代码执行||[MPS-2021-17824](https://www.oscs1024.com/hd/MPS-2021-17824)|CVE-2021-39141|高危|
|XStream < 1.4.18 反序列化远程代码执行漏洞|反序列化|[MPS-2021-17825](https://www.oscs1024.com/hd/MPS-2021-17825)|CVE-2021-39139|高危|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|Apache Tomcat 信息泄露漏洞|HTTP请求走私|[MPS-2021-2309](https://www.oscs1024.com/hd/MPS-2021-2309)|CVE-2021-25122|高危|
|Apache Tomcat 远程代码执行漏洞|代码注入|[MPS-2021-2466](https://www.oscs1024.com/hd/MPS-2021-2466)|CVE-2021-25329|高危|
|Alibaba Druid 目录遍历漏洞|路径遍历|[MPS-2021-25327](https://www.oscs1024.com/hd/MPS-2021-25327)|CVE-2021-33800|高危|
|Apache Tomcat 拒绝服务漏洞|拒绝服务|[MPS-2021-31848](https://www.oscs1024.com/hd/MPS-2021-31848)|CVE-2021-41079|高危|
|Apache Shiro 存在身份验证绕过|身份验证不当|[MPS-2021-32074](https://www.oscs1024.com/hd/MPS-2021-32074)|CVE-2021-41303|严重|
|Quality Open Software logback JNDI注入漏洞|反序列化|[MPS-2021-33911](https://www.oscs1024.com/hd/MPS-2021-33911)|CVE-2021-42550|中危|
|XStream < 1.4.19存在拒绝服务漏洞|拒绝服务|[MPS-2021-36984](https://www.oscs1024.com/hd/MPS-2021-36984)|CVE-2021-43859|高危|
|Apache Tomcat 条件竞争漏洞|竞争条件|[MPS-2021-37218](https://www.oscs1024.com/hd/MPS-2021-37218)|CVE-2021-43980|低危|
|Bouncy Castle 私钥信息泄露漏洞|竞争条件|[MPS-2021-7064](https://www.oscs1024.com/hd/MPS-2021-7064)|CVE-2020-15522|中危|
|Spring Framework权限许可和访问控制问题漏洞|权限管理不当|[MPS-2021-7485](https://www.oscs1024.com/hd/MPS-2021-7485)|CVE-2021-22118|高危|
|JDOM 存在 XXE 注入漏洞|XXE|[MPS-2021-8350](https://www.oscs1024.com/hd/MPS-2021-8350)|CVE-2021-33813|高危|
|Apache Tomcat 环境问题漏洞|HTTP请求走私|[MPS-2021-9711](https://www.oscs1024.com/hd/MPS-2021-9711)|CVE-2021-33037|中危|
|Vmware Spring Framework 安全漏洞|不加限制或调节的资源分配|[MPS-2022-1080](https://www.oscs1024.com/hd/MPS-2022-1080)|CVE-2022-22950|中危|
|Pivotal Spring Framework 安全限制绕过漏洞|大小写敏感处理不恰当|[MPS-2022-1098](https://www.oscs1024.com/hd/MPS-2022-1098)|CVE-2022-22968|中危|
|Spring Framework spring-beans 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1101](https://www.oscs1024.com/hd/MPS-2022-1101)|CVE-2022-22970|中危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|Logback SSL证书校验不当漏洞|中间人攻击|[MPS-2022-12411](https://www.oscs1024.com/hd/MPS-2022-12411)||中危|
|com.fasterxml.jackson.core:jackson-databind 存在反序列化漏洞|反序列化|[MPS-2022-12433](https://www.oscs1024.com/hd/MPS-2022-12433)||高危|
|Apache Commons Collections 远程代码执行漏洞|反序列化|[MPS-2022-12767](https://www.oscs1024.com/hd/MPS-2022-12767)||高危|
|org.json:json 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13520](https://www.oscs1024.com/hd/MPS-2022-13520)||高危|
|Apache Shiro 权限绕过漏洞|授权检查错误|[MPS-2022-17602](https://www.oscs1024.com/hd/MPS-2022-17602)|CVE-2022-32532|中危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|Bouncy Castle <1.69 认证绕过漏洞|密码学问题|[MPS-2022-54305](https://www.oscs1024.com/hd/MPS-2022-54305)||中危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|Apache Shiro < 1.10.0 身份认证绕过漏洞|授权检查错误|[MPS-2022-56931](https://www.oscs1024.com/hd/MPS-2022-56931)|CVE-2022-40664|严重|
|xstream project跨界内存写漏洞|越界写入|[MPS-2022-57066](https://www.oscs1024.com/hd/MPS-2022-57066)|CVE-2022-40151|高危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|XStream < 1.4.20 栈缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58603](https://www.oscs1024.com/hd/MPS-2022-58603)|CVE-2022-41966|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|spring-boot <2.2.11.RELEASE 存在目录劫持漏洞|将资源暴露给错误范围|[MPS-2022-6780](https://www.oscs1024.com/hd/MPS-2022-6780)|CVE-2022-27772|高危|
|spring-beans 远程代码执行漏洞(Spring4Shell)|表达式语言注入|[MPS-2022-6820](https://www.oscs1024.com/hd/MPS-2022-6820)|CVE-2022-22965|严重|
|Mybatis-PageHelper SQL注入漏洞|SQL注入|[MPS-2022-7189](https://www.oscs1024.com/hd/MPS-2022-7189)|CVE-2022-28111|严重|
| jodd-http <6.2.1 存在 CRLF 注入漏洞|注入|[MPS-2022-9219](https://www.oscs1024.com/hd/MPS-2022-9219)|CVE-2022-29631|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Apache Shiro <1.11.0 存在身份验证绕过漏洞|解释冲突|[MPS-2023-0169](https://www.oscs1024.com/hd/MPS-2023-0169)|CVE-2023-22602|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|Apache Shiro 身份验证绕过漏洞|路径遍历|[MPS-i2ro-tb93](https://www.oscs1024.com/hd/MPS-i2ro-tb93)|CVE-2023-34478|严重|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Apache Tomcat FORM 重定向漏洞|跨站重定向|[MPS-uy56-j8e4](https://www.oscs1024.com/hd/MPS-uy56-j8e4)|CVE-2023-41080|低危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.apache.tomcat.embed:tomcat-embed-core|9.0.19|11.0.0-m6|间接依赖|强烈建议修复|C:1|H:9|M:4|L:2|
|com.thoughtworks.xstream:xstream|1.4.17|1.4.20|间接依赖|强烈建议修复|C:0|H:15|M:2|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.9.8|2.14.0-rc1|间接依赖|建议修复|C:14|H:36|M:5|L:0|
|org.apache.shiro:shiro-core|1.6.0|1.9.1|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|com.squareup.okio:okio|1.17.2|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.shiro:shiro-spring-boot-web-starter|1.6.0|1.7.0|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework:spring-context|5.1.7.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|ch.qos.logback:logback-core|1.2.3|1.2.8|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.yaml:snakeyaml|1.23|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|com.github.pagehelper:pagehelper|5.1.4|5.3.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.apache.shiro:shiro-spring|1.6.0|1.9.1|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.alibaba:druid|1.2.1|1.2.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.google.protobuf:protobuf-java|3.11.4|3.21.7|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-web|5.1.7.RELEASE|6.0.0|间接依赖|建议修复|C:1|H:2|M:1|L:0|
|org.mybatis:mybatis|3.4.6|3.5.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-beans|5.1.7.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework.boot:spring-boot|2.1.5.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.shiro:shiro-web|1.6.0|2.0.0-alpha-3|间接依赖|建议修复|C:3|H:0|M:1|L:0|
|commons-collections:commons-collections|3.2.1|3.2.2|间接依赖|建议修复|C:1|H:2|M:0|L:0|
|com.github.penggle:kaptcha|2.3.2||直接依赖|可选修复|C:1|H:0|M:0|L:0|
|org.jodd:jodd-http|5.2.0|6.2.1|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|commons-codec:commons-codec|1.11|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.bouncycastle:bcprov-jdk15on|1.64|1.69|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|org.jdom:jdom|1.1||间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.httpcomponents:httpclient|4.5.8|4.5.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.1.5.RELEASE|3.0.7|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-expression|5.1.7.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|com.google.code.gson:gson|2.8.5|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.json:json|20170516|20180130|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|CDDL-1.0|1|Low|
|Apache-2.0|103|Low|
|自定义许可证|13|Low|
|MIT|10|Low|
|EPL-1.0|2|Low|
|JSON|1|Low|
|CDDL-1.1|3|Low|
|LGPL-2.1|1|Medium|
|MPL-1.1|1|Low|
|BSD-3-Clause|3|Low|
|BSD-2-Clause|3|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|javax.activation:activation|1.1.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.1.5.RELEASE|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.18.0|间接依赖|maven|
|com.aliyun.oss:aliyun-sdk-oss|2.5.0|直接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|org.apache.commons:commons-lang3|3.8.1|间接依赖|maven|
|com.google.code.gson:gson|2.8.5|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|org.springframework:spring-tx|5.1.7.RELEASE|间接依赖|maven|
|com.google.guava:guava|32.0.0-jre|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.19|间接依赖|maven|
|org.apache.shiro:shiro-crypto-cipher|1.6.0|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|com.fasterxml:classmate|1.4.0|间接依赖|maven|
|org.apache.shiro:shiro-cache|1.6.0|间接依赖|maven|
|org.springframework:spring-context-support|5.1.7.RELEASE|间接依赖|maven|
|commons-collections:commons-collections|3.2.1|间接依赖|maven|
|io.springfox:springfox-spi|2.9.2|间接依赖|maven|
|org.jdom:jdom|1.1|间接依赖|maven|
|com.qiniu:qiniu-java-sdk|7.2.29|直接依赖|maven|
|org.linlinjava:litemall-admin-api|0.1.0|直接依赖|maven|
|net.bytebuddy:byte-buddy|1.9.12|间接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.68|间接依赖|maven|
|commons-codec:commons-codec|1.11|间接依赖|maven|
|org.apache.shiro:shiro-crypto-hash|1.6.0|间接依赖|maven|
|javax.activation:activation|1.1|间接依赖|maven|
|com.google.zxing:core|3.2.1|间接依赖|maven|
|org.apache.shiro:shiro-crypto-core|1.6.0|间接依赖|maven|
|mysql:mysql-connector-java|8.0.28|直接依赖|maven|
|io.swagger:swagger-models|1.5.20|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.3|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.9.8|间接依赖|maven|
|org.json:json|20170516|间接依赖|maven|
|com.github.jsqlparser:jsqlparser|1.0|间接依赖|maven|
|com.jhlabs:filters|2.0.235-1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.1.5.RELEASE|间接依赖|maven|
|org.springframework:spring-beans|5.1.7.RELEASE|间接依赖|maven|
|io.springfox:springfox-swagger-ui|2.10.0|直接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-starter|1.3.2|直接依赖|maven|
|com.github.binarywang:weixin-java-common|4.1.0|间接依赖|maven|
|org.apache.shiro:shiro-spring|1.6.0|间接依赖|maven|
|com.alibaba:druid-spring-boot-starter|1.2.1|直接依赖|maven|
|org.apache.shiro:shiro-web|1.6.0|间接依赖|maven|
|io.github.x-stream:mxparser|1.2.1|间接依赖|maven|
|com.github.pagehelper:pagehelper|5.1.4|间接依赖|maven|
|commons-io:commons-io|2.7|间接依赖|maven|
|org.apache.shiro:shiro-lang|1.6.0|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.3|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.9.8|间接依赖|maven|
|com.github.pagehelper:pagehelper-spring-boot-autoconfigure|1.2.5|间接依赖|maven|
|com.github.xiaoymin:swagger-bootstrap-ui|1.9.6|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.26|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.1.5.RELEASE|间接依赖|maven|
|com.qcloud:cos_api|5.6.24|直接依赖|maven|
|org.apache.shiro:shiro-config-core|1.6.0|间接依赖|maven|
|com.github.pagehelper:pagehelper-spring-boot-starter|1.2.5|直接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|间接依赖|maven|
|org.springframework:spring-expression|5.1.7.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot|2.1.5.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.1.5.RELEASE|间接依赖|maven|
|org.apache.shiro:shiro-event|1.6.0|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.11|间接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|joda-time:joda-time|2.10.2|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|间接依赖|maven|
|org.javassist:javassist|3.25.0-GA|间接依赖|maven|
|org.apache.httpcomponents:httpmime|4.5.8|间接依赖|maven|
|com.thoughtworks.xstream:xstream|1.4.17|间接依赖|maven|
|org.springframework:spring-webmvc|5.1.7.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.9.0|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.1.5.Final|直接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.1.5.RELEASE|间接依赖|maven|
|org.linlinjava:litemall-core|0.1.0|直接依赖|maven|
|org.springframework.boot:spring-boot-devtools|2.1.5.RELEASE|直接依赖|maven|
|org.owasp.encoder:encoder|1.2.2|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-core|4.0.3|直接依赖|maven|
|org.mapstruct:mapstruct|1.2.0.Final|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.19|间接依赖|maven|
|com.sun.xml.bind:jaxb-core|2.1.14|间接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|com.alibaba:druid|1.2.1|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.9.8|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-mail|2.1.5.RELEASE|直接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.11.2|间接依赖|maven|
|net.sf.ezmorph:ezmorph|1.0.6|间接依赖|maven|
|org.apache.shiro:shiro-spring-boot-starter|1.6.0|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.8|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.26|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.9.8|间接依赖|maven|
|org.springframework:spring-context|5.1.7.RELEASE|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.64|间接依赖|maven|
|com.github.binarywang:qrcode-utils|1.1|间接依赖|maven|
|com.sun.mail:javax.mail|1.6.2|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|2.8|间接依赖|maven|
|com.squareup.okhttp3:okhttp|3.14.4|间接依赖|maven|
|io.springfox:springfox-swagger-common|2.9.2|间接依赖|maven|
|com.squareup.okio:okio|1.17.2|间接依赖|maven|
|net.sf.json-lib:json-lib|2.4|间接依赖|maven|
|com.github.penggle:kaptcha|2.3.2|直接依赖|maven|
|com.google.protobuf:protobuf-java|3.11.4|间接依赖|maven|
|commons-logging:commons-logging|1.1.1|间接依赖|maven|
|org.apache.shiro:shiro-spring-boot-web-starter|1.6.0|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.1.5.RELEASE|直接依赖|maven|
|com.github.qcloudsms:qcloudsms|1.0.5|直接依赖|maven|
|org.mybatis:mybatis-spring|1.3.2|间接依赖|maven|
|com.zaxxer:HikariCP|3.2.0|间接依赖|maven|
|io.springfox:springfox-schema|2.9.2|间接依赖|maven|
|com.github.binarywang:weixin-java-miniapp|4.1.0|直接依赖|maven|
|org.springframework.plugin:spring-plugin-metadata|1.2.0.RELEASE|间接依赖|maven|
|org.linlinjava:litemall-db|0.1.0|直接依赖|maven|
|org.springframework.plugin:spring-plugin-core|1.2.0.RELEASE|间接依赖|maven|
|io.springfox:springfox-core|2.9.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.1.5.RELEASE|直接依赖|maven|
|org.linlinjava:litemall-wx-api|0.1.0|直接依赖|maven|
|io.swagger:swagger-annotations|1.5.20|间接依赖|maven|
|org.jodd:jodd-core|5.2.0|间接依赖|maven|
|org.yaml:snakeyaml|1.23|间接依赖|maven|
|org.jodd:jodd-http|5.2.0|间接依赖|maven|
|com.github.binarywang:weixin-java-pay|4.1.0|直接依赖|maven|
|org.springframework:spring-web|5.1.7.RELEASE|间接依赖|maven|
|io.springfox:springfox-spring-web|2.9.2|间接依赖|maven|
|org.checkerframework:checker-qual|3.33.0|间接依赖|maven|
|org.springframework:spring-aop|5.1.7.RELEASE|间接依赖|maven|
|com.auth0:java-jwt|3.4.1|直接依赖|maven|
|io.springfox:springfox-swagger2|2.9.2|直接依赖|maven|
|org.dom4j:dom4j|2.1.3|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.19|间接依赖|maven|
|com.sun.xml.bind:jaxb-impl|2.1|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|org.springframework:spring-jdbc|5.1.7.RELEASE|间接依赖|maven|
|org.apache.shiro:shiro-config-ogdl|1.6.0|间接依赖|maven|
|org.jodd:jodd-util|6.0.0|间接依赖|maven|
|org.mybatis:mybatis|3.4.6|间接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-autoconfigure|1.3.2|间接依赖|maven|
|org.apache.shiro:shiro-core|1.6.0|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.26|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.11.2|间接依赖|maven|
|xmlpull:xmlpull|1.1.3.1|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.3.2.Final|间接依赖|maven|
|javax.servlet:javax.servlet-api|4.0.1|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.9.8|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)