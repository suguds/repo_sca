# alibaba/Sentinel安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699483670724526080.svg)](https://www.murphysec.com/console/report/1692235382879309824/1699483670724526080)

仓库描述：A powerful flow control component enabling reliability, resilience and monitoring for microservices. (面向云原生微服务的高可用流控防护组件)

仓库地址：[https://github.com/alibaba/Sentinel](https://github.com/alibaba/Sentinel)

| star：21375 | watch：790 | fork：7758 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-05 19:00:45 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-07 02:11:46 | 组件总数：1109 | 漏洞总数：274 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Juniper Network and Security Manager SSL会话重协商拒绝服务漏洞|权限、特权和访问控制|[MPS-2012-1902](https://www.oscs1024.com/hd/MPS-2012-1902)|CVE-2011-1473|中危|
|Apache Commons FileUpload DiskFileItem 类任意文件写入漏洞|输入验证不恰当|[MPS-2013-4267](https://www.oscs1024.com/hd/MPS-2013-4267)|CVE-2013-2186|高危|
|Apache Commons FileUpload <1.3.1 拒绝服务漏洞|权限、特权和访问控制|[MPS-2014-1540](https://www.oscs1024.com/hd/MPS-2014-1540)|CVE-2014-0050|高危|
|Apache Tomcat 拒绝服务漏洞|输入验证不恰当|[MPS-2016-3232](https://www.oscs1024.com/hd/MPS-2016-3232)|CVE-2016-3092|高危|
|Apache Commons FileUpload 访问控制错误漏洞|访问控制不当|[MPS-2016-5301](https://www.oscs1024.com/hd/MPS-2016-5301)|CVE-2016-1000031|严重|
|CVE-2016-1000227漏洞|XSS|[MPS-2016-9043](https://www.oscs1024.com/hd/MPS-2016-9043)|CVE-2016-1000227|高危|
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|Minimatch 拒绝服务漏洞|拒绝服务|[MPS-2018-6725](https://www.oscs1024.com/hd/MPS-2018-6725)|CVE-2016-10540|高危|
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
|FasterXML jackson-databind 反序列化漏洞(commons-dbcp gadget绕过)|反序列化|[MPS-2019-12479](https://www.oscs1024.com/hd/MPS-2019-12479)|CVE-2019-16942|严重|
|FasterXML jackson-databind 反序列化漏洞(p6spy gadget绕过)|反序列化|[MPS-2019-12480](https://www.oscs1024.com/hd/MPS-2019-12480)|CVE-2019-16943|严重|
|FasterXML jackson-databind 反序列化漏洞(ehcache gadget绕过)|反序列化|[MPS-2019-12676](https://www.oscs1024.com/hd/MPS-2019-12676)|CVE-2019-17267|严重|
|FasterXML jackson-databind 反序列化漏洞(apache-log4j-extras gadget绕过)|反序列化|[MPS-2019-13103](https://www.oscs1024.com/hd/MPS-2019-13103)|CVE-2019-17531|严重|
|csv-parse module for Node.js 输入验证错误漏洞|拒绝服务|[MPS-2019-13149](https://www.oscs1024.com/hd/MPS-2019-13149)|CVE-2019-17592|高危|
|AngularJS 存在输入验证错误漏洞|动态确定对象属性修改的控制不恰当|[MPS-2019-15098](https://www.oscs1024.com/hd/MPS-2019-15098)|CVE-2019-10768|高危|
|SnakeYAML <1.26 存在 Billion laughs 漏洞|拒绝服务|[MPS-2019-16129](https://www.oscs1024.com/hd/MPS-2019-16129)|CVE-2017-18640|高危|
|kind-of 存在注入漏洞|将资源暴露给错误范围|[MPS-2019-17164](https://www.oscs1024.com/hd/MPS-2019-17164)|CVE-2019-20149|高危|
|Apache Log4j SocketServer反序列化漏洞|反序列化|[MPS-2019-17271](https://www.oscs1024.com/hd/MPS-2019-17271)|CVE-2019-17571|严重|
|SOFA-Hessian 代码问题漏洞||[MPS-2019-1978](https://www.oscs1024.com/hd/MPS-2019-1978)|CVE-2019-9212|严重|
|XStream [*, 1.4.7)、[1.4.10, 1.4.11)版本存在命令注入漏洞|OS命令注入|[MPS-2019-5201](https://www.oscs1024.com/hd/MPS-2019-5201)|CVE-2013-7285|严重|
|FasterXML jackson-databind 反序列化漏洞(mysql gadget绕过)|反序列化|[MPS-2019-5442](https://www.oscs1024.com/hd/MPS-2019-5442)|CVE-2019-12086|高危|
|FasterXML jackson-databind 反序列化漏洞(jdom gadget绕过)|反序列化|[MPS-2019-6867](https://www.oscs1024.com/hd/MPS-2019-6867)|CVE-2019-12814|中危|
|FasterXML jackson-databind 反序列化漏洞(logback-classic gadget绕过)|反序列化|[MPS-2019-7047](https://www.oscs1024.com/hd/MPS-2019-7047)|CVE-2019-12384|中危|
|XStream v1.4.10 存在代码注入漏洞|代码注入|[MPS-2019-8313](https://www.oscs1024.com/hd/MPS-2019-8313)|CVE-2019-10173|严重|
|FasterXML jackson-databind 反序列化漏洞(ehcache gadget绕过)|动态确定对象属性修改的控制不恰当|[MPS-2019-8717](https://www.oscs1024.com/hd/MPS-2019-8717)|CVE-2019-14379|严重|
|FasterXML jackson-databind 信息泄露漏洞(logback gadget绕过)|反序列化|[MPS-2019-8770](https://www.oscs1024.com/hd/MPS-2019-8770)|CVE-2019-14439|高危|
|HTTP/2 拒绝服务漏洞|拒绝服务|[MPS-2019-9698](https://www.oscs1024.com/hd/MPS-2019-9698)|CVE-2019-9512|高危|
|io.netty:netty-codec-http2 <4.1.39.Final 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2019-9700](https://www.oscs1024.com/hd/MPS-2019-9700)|CVE-2019-9514|高危|
|Netty HTTP/2 存在资源管理错误漏洞|不加限制或调节的资源分配|[MPS-2019-9701](https://www.oscs1024.com/hd/MPS-2019-9701)|CVE-2019-9515|高危|
|io.netty:netty-codec-http2 <4.1.39.Final 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2019-9703](https://www.oscs1024.com/hd/MPS-2019-9703)|CVE-2019-9518|高危|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|FasterXML jackson-databind反序列化漏洞(net.sf.ehcache gadget绕过)|反序列化|[MPS-2020-0063](https://www.oscs1024.com/hd/MPS-2020-0063)|CVE-2019-20330|严重|
|FasterXML jackson-databind反序列化漏洞(Anteros-DBCP gadget绕过)|反序列化|[MPS-2020-11987](https://www.oscs1024.com/hd/MPS-2020-11987)|CVE-2020-24616|高危|
|apollo-adminservice 缺少访问控制漏洞|访问控制不当|[MPS-2020-12720](https://www.oscs1024.com/hd/MPS-2020-12720)|CVE-2020-15170|高危|
|FasterXML jackson-databind 反序列化漏洞(pastdev gadget绕过)|反序列化|[MPS-2020-13151](https://www.oscs1024.com/hd/MPS-2020-13151)|CVE-2020-24750|高危|
|Netty <=4.1.43.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1320](https://www.oscs1024.com/hd/MPS-2020-1320)|CVE-2020-7238|高危|
|Red Hat Resteasy 敏感信息泄露漏洞|通过错误消息导致的信息暴露|[MPS-2020-13308](https://www.oscs1024.com/hd/MPS-2020-13308)|CVE-2020-25633|中危|
|Eclipse Vert.x 路径遍历漏洞|路径遍历|[MPS-2020-14307](https://www.oscs1024.com/hd/MPS-2020-14307)|CVE-2019-17640|严重|
|Netty <4.1.44.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1526](https://www.oscs1024.com/hd/MPS-2020-1526)|CVE-2019-20444|严重|
|Netty <4.1.44.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-1527](https://www.oscs1024.com/hd/MPS-2020-1527)|CVE-2019-20445|严重|
|jQuery 跨站脚本漏洞|XSS|[MPS-2020-15461](https://www.oscs1024.com/hd/MPS-2020-15461)|CVE-2020-11023|中危|
|jQuery 跨站脚本漏洞|XSS|[MPS-2020-15462](https://www.oscs1024.com/hd/MPS-2020-15462)|CVE-2020-11022|中危|
|lodash <4.17.15 原型污染漏洞|原型污染|[MPS-2020-15679](https://www.oscs1024.com/hd/MPS-2020-15679)|CVE-2020-8203|高危|
|node-uuid <1.4.4 熵不足漏洞|信息熵不充分|[MPS-2020-1579](https://www.oscs1024.com/hd/MPS-2020-1579)|CVE-2015-8851|高危|
|Apache HttpClient URI解析错误漏洞|XSS|[MPS-2020-17341](https://www.oscs1024.com/hd/MPS-2020-17341)|CVE-2020-13956|中危|
|FasterXML jackson-databind 代码问题漏洞|XXE|[MPS-2020-17358](https://www.oscs1024.com/hd/MPS-2020-17358)|CVE-2020-25649|高危|
|XStream 操作系统命令注入漏洞|OS命令注入|[MPS-2020-17361](https://www.oscs1024.com/hd/MPS-2020-17361)|CVE-2020-26217|高危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Ini <1.3.6原型污染漏洞|拒绝服务|[MPS-2020-17544](https://www.oscs1024.com/hd/MPS-2020-17544)|CVE-2020-7788|高危|
|XStream < 1.4.15存在服务端请求伪造漏洞|SSRF|[MPS-2020-17591](https://www.oscs1024.com/hd/MPS-2020-17591)|CVE-2020-26258|高危|
|Xstream < 1.4.15存在删除任意文件漏洞|OS命令注入|[MPS-2020-17661](https://www.oscs1024.com/hd/MPS-2020-17661)|CVE-2020-26259|中危|
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
|minimist 原型污染漏洞|原型污染|[MPS-2020-3516](https://www.oscs1024.com/hd/MPS-2020-3516)|CVE-2020-7598|中危|
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
|Apache Log4j2 SmtpAppender证书验证不当漏洞|证书验证不恰当|[MPS-2020-6684](https://www.oscs1024.com/hd/MPS-2020-6684)|CVE-2020-9488|低危|
|Red Hat Resteasy 输入验证错误漏洞|XSS|[MPS-2020-7580](https://www.oscs1024.com/hd/MPS-2020-7580)|CVE-2020-1695|高危|
|websocket-extensions<0.1.4 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2020-8041](https://www.oscs1024.com/hd/MPS-2020-8041)|CVE-2020-7662|高危|
|websocket-extensions 拒绝服务漏洞|拒绝服务|[MPS-2020-8042](https://www.oscs1024.com/hd/MPS-2020-8042)|CVE-2020-7663|高危|
|AngularJS 跨站脚本漏洞|XSS|[MPS-2020-8326](https://www.oscs1024.com/hd/MPS-2020-8326)|CVE-2020-7676|中危|
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
|Netty <4.1.59.Final 存在不安全的临时文件漏洞||[MPS-2021-1580](https://www.oscs1024.com/hd/MPS-2021-1580)|CVE-2021-21290|中危|
|FasterXML jackson-databind 反序列化漏洞(javax.swing gadget绕过)|反序列化|[MPS-2021-1625](https://www.oscs1024.com/hd/MPS-2021-1625)|CVE-2021-20190|高危|
|jsoup <1.14.2 存在拒绝服务漏洞||[MPS-2021-17634](https://www.oscs1024.com/hd/MPS-2021-17634)|CVE-2021-37714|高危|
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
|Spring Framework <5.3.14 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18854](https://www.oscs1024.com/hd/MPS-2021-18854)|CVE-2021-22060|中危|
|Pivotal Spring Framework 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18890](https://www.oscs1024.com/hd/MPS-2021-18890)|CVE-2021-22096|中危|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|netplex json-smart-v  分布式拒绝服务攻击|对因果或异常条件的不恰当检查|[MPS-2021-2102](https://www.oscs1024.com/hd/MPS-2021-2102)|CVE-2021-27568|严重|
|io.netty:netty-codec-http2 <4.1.60.Final 存在 http 请求走私漏洞|HTTP请求走私|[MPS-2021-2435](https://www.oscs1024.com/hd/MPS-2021-2435)|CVE-2021-21295|中危|
|lodash 拒绝服务漏洞|拒绝服务|[MPS-2021-2574](https://www.oscs1024.com/hd/MPS-2021-2574)|CVE-2020-28500|中危|
|lodash 命令注入漏洞|代码注入|[MPS-2021-2638](https://www.oscs1024.com/hd/MPS-2021-2638)|CVE-2021-23337|高危|
|Oracle Java SE Oracle GraalVM Enterprise Edition  输入验证错误漏洞|访问控制不当|[MPS-2021-26664](https://www.oscs1024.com/hd/MPS-2021-26664)|CVE-2021-35567|中危|
|Oracle Java SE Oracle GraalVM Enterprise Edition 输入验证错误漏洞|访问控制不当|[MPS-2021-26676](https://www.oscs1024.com/hd/MPS-2021-26676)|CVE-2021-35578|中危|
|Oracle Java SE Oracle GraalVM Enterprise Edition 输入验证错误漏洞|通过时间差异性导致的信息暴露|[MPS-2021-26703](https://www.oscs1024.com/hd/MPS-2021-26703)|CVE-2021-35603|低危|
|Netty Bzip2Decoder 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28116](https://www.oscs1024.com/hd/MPS-2021-28116)|CVE-2021-37136|高危|
|Netty 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28117](https://www.oscs1024.com/hd/MPS-2021-28117)|CVE-2021-37137|高危|
|XStream <1.4.16存在反序列化漏洞||[MPS-2021-3119](https://www.oscs1024.com/hd/MPS-2021-3119)|CVE-2021-21342|高危|
|XStream 存在反序列化漏洞||[MPS-2021-3120](https://www.oscs1024.com/hd/MPS-2021-3120)|CVE-2021-21348|中危|
|XStream 存在反序列化漏洞||[MPS-2021-3121](https://www.oscs1024.com/hd/MPS-2021-3121)|CVE-2021-21346|高危|
|XStream 存在反序列化漏洞||[MPS-2021-3122](https://www.oscs1024.com/hd/MPS-2021-3122)|CVE-2021-21345|高危|
|XStream <1.4.16存在反序列化漏洞||[MPS-2021-3123](https://www.oscs1024.com/hd/MPS-2021-3123)|CVE-2021-21343|中危|
|XStream 存在拒绝服务漏洞||[MPS-2021-3124](https://www.oscs1024.com/hd/MPS-2021-3124)|CVE-2021-21341|中危|
|XStream 存在反序列化漏洞||[MPS-2021-3125](https://www.oscs1024.com/hd/MPS-2021-3125)|CVE-2021-21344|高危|
|XStream 存在反序列化漏洞||[MPS-2021-3127](https://www.oscs1024.com/hd/MPS-2021-3127)|CVE-2021-21349|中危|
|XStream <1.4.16存在反序列化漏洞||[MPS-2021-3128](https://www.oscs1024.com/hd/MPS-2021-3128)|CVE-2021-21350|高危|
|XStream 存在反序列化漏洞||[MPS-2021-3129](https://www.oscs1024.com/hd/MPS-2021-3129)|CVE-2021-21351|严重|
|Quality Open Software logback JNDI注入漏洞|反序列化|[MPS-2021-33911](https://www.oscs1024.com/hd/MPS-2021-33911)|CVE-2021-42550|中危|
|XStream 存在反序列化漏洞||[MPS-2021-3396](https://www.oscs1024.com/hd/MPS-2021-3396)|CVE-2021-21347|高危|
|Ruy Adorno hosted-git-info 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-3400](https://www.oscs1024.com/hd/MPS-2021-3400)|CVE-2021-23362|中危|
|Async 原型污染漏洞|原型污染|[MPS-2021-34434](https://www.oscs1024.com/hd/MPS-2021-34434)|CVE-2021-43138|高危|
| io.netty:netty-codec-http2 <4.1.61.Final 存在 http 请求走私漏洞|HTTP请求走私|[MPS-2021-3565](https://www.oscs1024.com/hd/MPS-2021-3565)|CVE-2021-21409|中危|
|Oracle Java SE 输入验证错误漏洞|反序列化|[MPS-2021-36472](https://www.oscs1024.com/hd/MPS-2021-36472)|CVE-2022-21248|低危|
|Oracle Java SE和Oracle GraalVM 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-2021-36501](https://www.oscs1024.com/hd/MPS-2021-36501)|CVE-2022-21277|中危|
|Oracle Java SE 输入验证错误漏洞|未授权敏感信息泄露|[MPS-2021-36506](https://www.oscs1024.com/hd/MPS-2021-36506)|CVE-2022-21282|中危|
|Oracle Java SE 输入验证错误漏洞|未捕获的异常|[MPS-2021-36507](https://www.oscs1024.com/hd/MPS-2021-36507)|CVE-2022-21283|中危|
|Oracle GraalVM 输入验证错误漏洞|越界写入|[MPS-2021-36515](https://www.oscs1024.com/hd/MPS-2021-36515)|CVE-2022-21291|中危|
|Oracle Java SE  输入验证错误漏洞|拒绝服务|[MPS-2021-36517](https://www.oscs1024.com/hd/MPS-2021-36517)|CVE-2022-21293|中危|
|Oracle Java SE 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-2021-36518](https://www.oscs1024.com/hd/MPS-2021-36518)|CVE-2022-21294|中危|
|Oracle Java SE  输入验证错误漏洞|未授权敏感信息泄露|[MPS-2021-36520](https://www.oscs1024.com/hd/MPS-2021-36520)|CVE-2022-21296|中危|
|Oracle Java SE   输入验证错误漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-36523](https://www.oscs1024.com/hd/MPS-2021-36523)|CVE-2022-21299|中危|
|Oracle Java SE 输入验证错误漏洞|整数溢出或环绕|[MPS-2021-36529](https://www.oscs1024.com/hd/MPS-2021-36529)|CVE-2022-21305|中危|
|Oracle Java SE 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-2021-36564](https://www.oscs1024.com/hd/MPS-2021-36564)|CVE-2022-21340|中危|
|Oracle Java SE 输入验证错误漏洞|拒绝服务|[MPS-2021-36565](https://www.oscs1024.com/hd/MPS-2021-36565)|CVE-2022-21341|中危|
|Oracle GraalVM 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-2021-36584](https://www.oscs1024.com/hd/MPS-2021-36584)|CVE-2022-21360|中危|
|Oracle Java SE和Oracle GraalVM 输入验证错误漏洞|整数溢出或环绕|[MPS-2021-36589](https://www.oscs1024.com/hd/MPS-2021-36589)|CVE-2022-21365|中危|
|Oracle GraalVM 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-2021-36590](https://www.oscs1024.com/hd/MPS-2021-36590)|CVE-2022-21366|中危|
|Oracle Java SE 和 Oracle GraalVM 输入验证错误漏洞|拒绝服务|[MPS-2021-36650](https://www.oscs1024.com/hd/MPS-2021-36650)|CVE-2022-21426|中危|
|Oracle Java SE 和 Oracle GraalVM 输入验证错误漏洞|使用外部可控制的输入来选择类或代码（不安全的反射）|[MPS-2021-36658](https://www.oscs1024.com/hd/MPS-2021-36658)|CVE-2022-21434|中危|
|Oracle Java SE 输入验证错误漏洞||[MPS-2021-36667](https://www.oscs1024.com/hd/MPS-2021-36667)|CVE-2022-21443|低危|
|Java SE 数字签名伪造漏洞|密码学签名的验证不恰当|[MPS-2021-36673](https://www.oscs1024.com/hd/MPS-2021-36673)|CVE-2022-21449|高危|
|Oracle Java SE 输入验证错误漏洞||[MPS-2021-36700](https://www.oscs1024.com/hd/MPS-2021-36700)|CVE-2022-21476|高危|
|Oracle Java SE 输入验证错误漏洞||[MPS-2021-36720](https://www.oscs1024.com/hd/MPS-2021-36720)|CVE-2022-21496|中危|
|Red Hat Resteasy 安全漏洞|通过错误消息导致的信息暴露|[MPS-2021-3679](https://www.oscs1024.com/hd/MPS-2021-3679)|CVE-2021-20289|中危|
|Netty <4.1.71.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2021-36922](https://www.oscs1024.com/hd/MPS-2021-36922)|CVE-2021-43797|中危|
|XStream < 1.4.19存在拒绝服务漏洞|拒绝服务|[MPS-2021-36984](https://www.oscs1024.com/hd/MPS-2021-36984)|CVE-2021-43859|高危|
|Apache Tomcat 条件竞争漏洞|竞争条件|[MPS-2021-37218](https://www.oscs1024.com/hd/MPS-2021-37218)|CVE-2021-43980|低危|
|Apache Log4j JMSAppender反序列化漏洞||[MPS-2021-38359](https://www.oscs1024.com/hd/MPS-2021-38359)|CVE-2021-4104|高危|
|minimist 安全漏洞|原型污染|[MPS-2021-38405](https://www.oscs1024.com/hd/MPS-2021-38405)|CVE-2021-44906|严重|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|npm path-parse 安全漏洞|拒绝服务|[MPS-2021-6165](https://www.oscs1024.com/hd/MPS-2021-6165)|CVE-2021-23343|高危|
|Bouncy Castle 私钥信息泄露漏洞|竞争条件|[MPS-2021-7064](https://www.oscs1024.com/hd/MPS-2021-7064)|CVE-2020-15522|中危|
|XStream 远程代码执行漏洞||[MPS-2021-7164](https://www.oscs1024.com/hd/MPS-2021-7164)|CVE-2021-29505|高危|
|trim-newlines 存在拒绝服务漏洞|拒绝服务|[MPS-2021-7398](https://www.oscs1024.com/hd/MPS-2021-7398)|CVE-2021-33623|高危|
|Red Hat Resteasy 资源管理错误漏洞|拒绝服务|[MPS-2021-7506](https://www.oscs1024.com/hd/MPS-2021-7506)|CVE-2020-14326|高危|
|SmallRye 安全漏洞|授权检查错误|[MPS-2021-7531](https://www.oscs1024.com/hd/MPS-2021-7531)|CVE-2020-1729|中危|
|Jakarta Expression Language <=3.0.3 存在输入验证错误漏洞|表达式语言注入|[MPS-2021-7671](https://www.oscs1024.com/hd/MPS-2021-7671)|CVE-2021-28170|中危|
|json-smart 存在拒绝服务漏洞|越界写入|[MPS-2021-7737](https://www.oscs1024.com/hd/MPS-2021-7737)|CVE-2021-31684|高危|
|Red Hat Resteasy 跨站脚本漏洞|XSS|[MPS-2021-7858](https://www.oscs1024.com/hd/MPS-2021-7858)|CVE-2021-20293|中危|
|Apache Tomcat 环境问题漏洞|HTTP请求走私|[MPS-2021-9711](https://www.oscs1024.com/hd/MPS-2021-9711)|CVE-2021-33037|中危|
|shelljs < 0.8.5 存在特权管理不恰当漏洞|权限管理不当|[MPS-2022-0508](https://www.oscs1024.com/hd/MPS-2022-0508)|CVE-2022-0144|高危|
|Vmware Spring Framework 安全漏洞|不加限制或调节的资源分配|[MPS-2022-1080](https://www.oscs1024.com/hd/MPS-2022-1080)|CVE-2022-22950|中危|
|Pivotal Spring Framework 安全限制绕过漏洞|大小写敏感处理不恰当|[MPS-2022-1098](https://www.oscs1024.com/hd/MPS-2022-1098)|CVE-2022-22968|中危|
|Spring Framework spring-beans 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1101](https://www.oscs1024.com/hd/MPS-2022-1101)|CVE-2022-22970|中危|
|Spring Framework 整数溢出漏洞|整数溢出或环绕|[MPS-2022-1106](https://www.oscs1024.com/hd/MPS-2022-1106)|CVE-2022-22976|中危|
|Moment.js 正则拒绝服务漏洞|拒绝服务|[MPS-2022-11159](https://www.oscs1024.com/hd/MPS-2022-11159)|CVE-2022-31129|高危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|io.netty:netty-codec-http <4.1.53.Final 存在拒绝服务漏洞|拒绝服务|[MPS-2022-12064](https://www.oscs1024.com/hd/MPS-2022-12064)||中危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|io.quarkus:quarkus-core 存在信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-12335](https://www.oscs1024.com/hd/MPS-2022-12335)||中危|
|Logback SSL证书校验不当漏洞|中间人攻击|[MPS-2022-12411](https://www.oscs1024.com/hd/MPS-2022-12411)||中危|
|com.fasterxml.jackson.core:jackson-databind 存在反序列化漏洞|反序列化|[MPS-2022-12433](https://www.oscs1024.com/hd/MPS-2022-12433)||高危|
|io.quarkus:quarkus-vertx-http 存在信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-12439](https://www.oscs1024.com/hd/MPS-2022-12439)||低危|
|FasterXML Jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2022-12500](https://www.oscs1024.com/hd/MPS-2022-12500)||中危|
|angular  <=1.8.3 存在ReDoS漏洞|ReDoS|[MPS-2022-12542](https://www.oscs1024.com/hd/MPS-2022-12542)|CVE-2022-25844|中危|
|org.apache.maven.shared:maven-shared-utils 存在命令注入漏洞|命令注入|[MPS-2022-12562](https://www.oscs1024.com/hd/MPS-2022-12562)||高危|
|Reactor Netty HTTP Server 敏感信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-12714](https://www.oscs1024.com/hd/MPS-2022-12714)|CVE-2022-31684|低危|
|Apache Tomcat 本地权限提升漏洞|检查时间与使用时间(TOCTOU)的竞争条件|[MPS-2022-1351](https://www.oscs1024.com/hd/MPS-2022-1351)|CVE-2022-23181|高危|
|org.json:json 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13520](https://www.oscs1024.com/hd/MPS-2022-13520)||高危|
|angular 存在跨站脚本漏洞|XSS|[MPS-2022-13544](https://www.oscs1024.com/hd/MPS-2022-13544)||高危|
|lodash<4.17.20 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13841](https://www.oscs1024.com/hd/MPS-2022-13841)||高危|
|lodash<4.17.17 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13842](https://www.oscs1024.com/hd/MPS-2022-13842)||高危|
|minimatch < 3.0.2 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13882](https://www.oscs1024.com/hd/MPS-2022-13882)||高危|
|uglify-js <3.14.3 正则表达式拒绝服务漏洞|ReDoS|[MPS-2022-14112](https://www.oscs1024.com/hd/MPS-2022-14112)||中危|
|Apache Log4j JDBCAppender SQL注入漏洞|SQL注入|[MPS-2022-1444](https://www.oscs1024.com/hd/MPS-2022-1444)|CVE-2022-23305|严重|
|Apache Log4j Chainsaw反序列化漏洞|反序列化|[MPS-2022-1445](https://www.oscs1024.com/hd/MPS-2022-1445)|CVE-2022-23307|高危|
|Apache Log4j 反序列化漏洞|反序列化|[MPS-2022-1446](https://www.oscs1024.com/hd/MPS-2022-1446)|CVE-2022-23302|高危|
|uuid<1.3.1 存在不安全的随机数漏洞|使用不充分的随机数|[MPS-2022-15362](https://www.oscs1024.com/hd/MPS-2022-15362)||中危|
|commons-fileupload:commons-fileupload 存在信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-16625](https://www.oscs1024.com/hd/MPS-2022-16625)||中危|
|Moment.js 路径遍历漏洞|路径遍历|[MPS-2022-3752](https://www.oscs1024.com/hd/MPS-2022-3752)|CVE-2022-24785|中危|
|Netty 存在信息泄露漏洞||[MPS-2022-3790](https://www.oscs1024.com/hd/MPS-2022-3790)|CVE-2022-24823|中危|
|Express 中的 qs 模块存在原型污染漏洞|原型污染|[MPS-2022-3967](https://www.oscs1024.com/hd/MPS-2022-3967)|CVE-2022-24999|高危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|Angular 存在XSS漏洞|XSS|[MPS-2022-5154](https://www.oscs1024.com/hd/MPS-2022-5154)|CVE-2022-25869|中危|
|jsoup <1.15.3 存在反射型 XSS 漏洞|XSS|[MPS-2022-51547](https://www.oscs1024.com/hd/MPS-2022-51547)|CVE-2022-36033|中危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|Bouncy Castle <1.69 认证绕过漏洞|密码学问题|[MPS-2022-54305](https://www.oscs1024.com/hd/MPS-2022-54305)||中危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|decode-uri-component <=0.2.0 存在输入验证不当漏洞|拒绝服务|[MPS-2022-56259](https://www.oscs1024.com/hd/MPS-2022-56259)|CVE-2022-38900|高危|
|xstream project跨界内存写漏洞|越界写入|[MPS-2022-57066](https://www.oscs1024.com/hd/MPS-2022-57066)|CVE-2022-40151|高危|
|Jettison <1.5.2 拒绝服务漏洞|拒绝服务|[MPS-2022-57067](https://www.oscs1024.com/hd/MPS-2022-57067)|CVE-2022-40150|高危|
|Jettison <1.5.1 拒绝服务漏洞|越界写入|[MPS-2022-57068](https://www.oscs1024.com/hd/MPS-2022-57068)|CVE-2022-40149|高危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|Netty <4.1.86.Final 存在拒绝服务漏洞|未经控制的递归|[MPS-2022-58518](https://www.oscs1024.com/hd/MPS-2022-58518)|CVE-2022-41881|中危|
|Netty <4.1.86.Final 存在 CRLF 注入漏洞||[MPS-2022-58552](https://www.oscs1024.com/hd/MPS-2022-58552)|CVE-2022-41915|中危|
|XStream < 1.4.20 栈缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58603](https://www.oscs1024.com/hd/MPS-2022-58603)|CVE-2022-41966|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|minimatch 资源管理错误漏洞|拒绝服务|[MPS-2022-59845](https://www.oscs1024.com/hd/MPS-2022-59845)|CVE-2022-3517|高危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|Spring Security通配符路由绕过漏洞|关键资源权限分配不当|[MPS-2022-62832](https://www.oscs1024.com/hd/MPS-2022-62832)|CVE-2023-20860|高危|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot在Cloud Foundry中部署存在路由限制绕过风险|访问控制不当|[MPS-2022-62845](https://www.oscs1024.com/hd/MPS-2022-62845)|CVE-2023-20873|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|Jettison <1.5.2 拒绝服务漏洞|越界写入|[MPS-2022-64973](https://www.oscs1024.com/hd/MPS-2022-64973)|CVE-2022-45685|高危|
|Jettison <1.5.2 拒绝服务漏洞|越界写入|[MPS-2022-64981](https://www.oscs1024.com/hd/MPS-2022-64981)|CVE-2022-45693|高危|
|Quarkus 安全漏洞|OWASP 前十名的弱点（2017 年）|[MPS-2022-65506](https://www.oscs1024.com/hd/MPS-2022-65506)|CVE-2022-4147|高危|
|spring-boot <2.2.11.RELEASE 存在目录劫持漏洞|将资源暴露给错误范围|[MPS-2022-6780](https://www.oscs1024.com/hd/MPS-2022-6780)|CVE-2022-27772|高危|
|spring-beans 远程代码执行漏洞(Spring4Shell)|表达式语言注入|[MPS-2022-6820](https://www.oscs1024.com/hd/MPS-2022-6820)|CVE-2022-22965|严重|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68515](https://www.oscs1024.com/hd/MPS-2022-68515)|CVE-2023-21930|高危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68522](https://www.oscs1024.com/hd/MPS-2022-68522)|CVE-2023-21937|低危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68523](https://www.oscs1024.com/hd/MPS-2022-68523)|CVE-2023-21938|低危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68524](https://www.oscs1024.com/hd/MPS-2022-68524)|CVE-2023-21939|中危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68539](https://www.oscs1024.com/hd/MPS-2022-68539)|CVE-2023-21954|中危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68552](https://www.oscs1024.com/hd/MPS-2022-68552)|CVE-2023-21967|中危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68553](https://www.oscs1024.com/hd/MPS-2022-68553)|CVE-2023-21968|低危|
|Apache Maven Shared Utils 系统命令注入漏洞|命令注入|[MPS-2022-9177](https://www.oscs1024.com/hd/MPS-2022-9177)|CVE-2022-29599|严重|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Red Hat quarkus-vertx-http 跨站脚本漏洞|XSS|[MPS-2023-0173](https://www.oscs1024.com/hd/MPS-2023-0173)|CVE-2023-0044|中危|
|Apache Dubbo 存在反序列化漏洞|反序列化|[MPS-2023-1779](https://www.oscs1024.com/hd/MPS-2023-1779)|CVE-2023-23638|中危|
|Resteasy 安全漏洞|输入验证不恰当|[MPS-2023-2844](https://www.oscs1024.com/hd/MPS-2023-2844)|CVE-2023-0482|中危|
|Apache Commons FileUpload <1.5 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2023-3553](https://www.oscs1024.com/hd/MPS-2023-3553)|CVE-2023-24998|中危|
|angular 安全漏洞|ReDoS|[MPS-2023-5110](https://www.oscs1024.com/hd/MPS-2023-5110)|CVE-2023-26117|中危|
|Angular 安全漏洞|ReDoS|[MPS-2023-5111](https://www.oscs1024.com/hd/MPS-2023-5111)|CVE-2023-26116|中危|
|Angular 安全漏洞|ReDoS|[MPS-2023-5112](https://www.oscs1024.com/hd/MPS-2023-5112)|CVE-2023-26118|中危|
|netplex json-smart 安全漏洞|未经控制的递归|[MPS-2023-7760](https://www.oscs1024.com/hd/MPS-2023-7760)|CVE-2023-1370|高危|
|Jettison 安全漏洞|未经控制的递归|[MPS-2023-8270](https://www.oscs1024.com/hd/MPS-2023-8270)|CVE-2023-1436|高危|
|jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2023-8438](https://www.oscs1024.com/hd/MPS-2023-8438)|CVE-2021-46877|中危|
|angular-ui-notification 跨站脚本漏洞|XSS|[MPS-23xm-wsgd](https://www.oscs1024.com/hd/MPS-23xm-wsgd)|CVE-2023-34840|中危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Apache Tomcat FORM 重定向漏洞|跨站重定向|[MPS-uy56-j8e4](https://www.oscs1024.com/hd/MPS-uy56-j8e4)|CVE-2023-41080|低危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.thoughtworks.xstream:xstream|1.4.10|1.4.20|间接依赖|强烈建议修复|C:3|H:24|M:7|L:0|
|commons-fileupload:commons-fileupload|1.3|1.5|间接依赖|强烈建议修复|C:1|H:3|M:2|L:0|
|org.yaml:snakeyaml|1.29|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|lodash|4.17.15|4.17.21|间接依赖|建议修复|C:0|H:4|M:1|L:0|
|minimist|0.0.10|1.2.6|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|io.netty:netty-codec|4.1.30.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.2.1|2.14.0-rc1|直接依赖|建议修复|C:0|H:0|M:3|L:0|
|io.vertx:vertx-core|3.8.5|3.9.4|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.12.6.1|2.14.0-rc1|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|io.netty:netty-codec|4.1.63.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|org.jboss.resteasy:resteasy-jaxrs|3.6.3.Final|3.11.0.Final|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.45.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|io.netty:netty-all|4.0.42.Final|4.1.44.Final|间接依赖|建议修复|C:2|H:2|M:0|L:0|
|com.google.protobuf:protobuf-java|3.5.1|3.21.7|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|io.netty:netty-handler|4.1.75.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-context|5.3.18|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec|4.1.45.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|org.springframework.security:spring-security-crypto|5.3.9.RELEASE|5.6.4|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|io.netty:netty-handler|4.1.63.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.9.8|2.14.0-rc1|间接依赖|建议修复|C:14|H:36|M:5|L:0|
|log4j:log4j|1.2.17||直接依赖|建议修复|C:2|H:3|M:0|L:1|
|com.alipay.sofa:hessian|3.3.7|4.0.3|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|io.netty:netty-all|4.1.42.Final|4.1.44.Final|间接依赖|建议修复|C:2|H:1|M:0|L:0|
|ini|1.3.5|1.3.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.3.12.RELEASE|3.0.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.20|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|qs|6.6.0|6.10.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|ch.qos.logback:logback-core|1.2.3|1.2.8|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|net.minidev:json-smart|2.3|2.4.9|间接依赖|建议修复|C:1|H:2|M:0|L:0|
|org.codehaus.jettison:jettison|1.3.7|1.5.4|间接依赖|建议修复|C:0|H:5|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.2.2|2.14.0-rc1|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|org.apache.rocketmq:rocketmq-remoting|4.2.0|4.8.0|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-beans|5.3.15|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework.boot:spring-boot|2.2.2.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.jboss.netty:netty|3.2.5.Final||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.3.12.RELEASE|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|angular-ui-notification|0.3.6||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-http|4.1.30.Final|4.1.86.final|间接依赖|建议修复|C:2|H:2|M:5|L:0|
|io.netty:netty-handler|4.1.50.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|org.springframework:spring-web|5.3.18|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.yaml:snakeyaml|1.32|2.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.28|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|io.netty:netty-codec|4.1.27.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|org.yaml:snakeyaml|1.25|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|io.netty:netty-handler|4.1.48.Final|4.1.94.final|直接依赖|建议修复|C:0|H:0|M:3|L:0|
|org.springframework:spring-beans|5.2.15.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|jquery|3.4.1|3.5.0|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|io.netty:netty-all|4.1.31.Final|4.1.44.Final|直接依赖|建议修复|C:2|H:2|M:0|L:0|
|io.quarkus:quarkus-vertx-http|1.4.1.Final|3.2.1.final|间接依赖|建议修复|C:0|H:1|M:1|L:1|
|org.springframework:spring-context|4.3.16.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.yaml:snakeyaml|1.26|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|io.netty:netty-handler|4.1.27.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.46|11.0.0-m6|间接依赖|建议修复|C:0|H:1|M:1|L:1|
|org.jboss.resteasy:resteasy-core|4.5.3.Final|4.7.8.final|间接依赖|建议修复|C:0|H:1|M:3|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.12.2|2.14.0-rc1|间接依赖|建议修复|C:0|H:1|M:5|L:0|
|node-uuid|1.4.0|1.4.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.5.12|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|websocket-extensions|0.1.3|0.1.4|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|io.netty:netty-codec-http|4.1.27.Final|4.1.86.final|间接依赖|建议修复|C:2|H:2|M:5|L:0|
|bootstrap-tagsinput|0.7.1||直接依赖|建议修复|C:0|H:1|M:0|L:0|
|trim-newlines|1.0.0|4.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.squareup.okio:okio|1.11.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-web|5.2.15.RELEASE|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.apache.dubbo:dubbo|2.7.18|3.1.6|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-webmvc|5.3.18|6.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.2.2.RELEASE|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-codec|4.1.48.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|io.netty:netty-codec|4.1.50.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|shelljs|0.3.0|0.8.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.6.6|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.graalvm.sdk:graal-sdk|19.3.1|22.3.3|间接依赖|建议修复|C:0|H:3|M:22|L:6|
|org.springframework.boot:spring-boot-autoconfigure|2.0.3.RELEASE|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|path-parse|1.0.5|1.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|csv-parse|2.5.0|4.4.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-context|5.2.15.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|io.netty:netty|3.10.6.Final||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|decode-uri-component|0.2.0|0.2.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.9.6|2.14.0-rc1|间接依赖|建议修复|C:21|H:36|M:5|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.10.3|2.14.0-rc1|间接依赖|建议修复|C:0|H:2|M:5|L:0|
|com.ctrip.framework.apollo:apollo-core|1.5.0|1.7.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.23|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|minimatch|2.0.10|3.0.5|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|org.springframework:spring-beans|4.3.16.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework.security:spring-security-crypto|5.6.1|5.6.4|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|angular|1.7.2|1.8.0|间接依赖|建议修复|C:0|H:2|M:6|L:0|
|com.google.protobuf:protobuf-java|3.14.0|3.21.7|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.google.protobuf:protobuf-java|3.10.0|3.21.7|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-context|5.2.8.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.apache.maven.shared:maven-shared-utils|3.2.1|3.3.3|间接依赖|建议修复|C:1|H:1|M:0|L:0|
|org.apache.maven.shared:maven-shared-utils|3.2.1|3.3.3|间接依赖|建议修复|C:1|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.17|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|io.netty:netty-handler|4.1.30.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|org.yaml:snakeyaml|1.17|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|io.netty:netty-handler|4.1.30.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|org.springframework:spring-core|5.2.15.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|org.springframework:spring-beans|5.3.18|5.3.20|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-core|5.1.18.RELEASE|6.0.7|直接依赖|可选修复|C:0|H:0|M:2|L:0|
|io.netty:netty-codec-http|4.1.79.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|kind-of|6.0.2|6.0.3|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.jboss.resteasy:resteasy-client|4.5.3.Final|4.5.8.SP1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|26.0-android|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:1|
|org.jboss.resteasy:resteasy-client|3.6.3.Final|4.5.8.SP1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.json:json|20090211|20180130|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|commons-codec:commons-codec|1.4|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|io.netty:netty-codec-http2|4.1.27.Final|4.1.61.Final|间接依赖|可选修复|C:0|H:4|M:2|L:0|
|com.google.code.gson:gson|2.8.0|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.code.gson:gson|2.7|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|hosted-git-info|2.7.1|3.0.8|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.bouncycastle:bcprov-jdk15on|1.61|1.69|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|io.netty:netty-common|4.1.50.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|18.0|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|com.google.guava:guava|29.0-android|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:1|
|io.netty:netty-transport-native-epoll|4.1.27.Final|4.1.59.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-haproxy|4.1.27.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.bouncycastle:bcprov-jdk15on|1.70||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.httpcomponents:httpclient|4.5.8|4.5.13|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-core|5.3.15|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.projectreactor.netty:reactor-netty-http|1.0.17|1.0.24|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.springframework:spring-core|4.3.16.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|30.1-android|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|5.2.8.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|async|2.6.1|3.2.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-core|5.3.18|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-common|4.1.27.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-expression|5.3.18|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.60|11.0.0-m6|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.springframework:spring-expression|5.2.15.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|com.google.guava:guava|25.0-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:1|
|org.glassfish:jakarta.el|3.0.3|3.0.4|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.code.gson:gson|2.8.2|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.httpcomponents:httpclient|4.5.5|4.5.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|uglify-js|3.4.9|3.14.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-haproxy|4.1.75.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|moment|2.22.2|2.29.4|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|lodash.template|3.6.2||间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.code.gson:gson|2.8.5|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|commons-io:commons-io|2.4|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-http|4.1.75.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.jboss.resteasy:resteasy-client-api|4.5.3.Final|4.5.8.SP1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-codec:commons-codec|1.11|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|io.netty:netty-codec-http|4.1.63.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|15.0|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|io.netty:netty-common|4.1.75.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-common|4.1.30.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.bouncycastle:bcprov-jdk15on|1.64|1.69|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|io.netty:netty-common|4.1.48.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|commons-codec:commons-codec|1.9|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|commons-codec:commons-codec|1.10|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.springframework:spring-expression|4.3.16.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|com.google.code.gson:gson|2.8.6|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.httpcomponents:httpclient|4.5.3|4.5.13|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-common|4.1.63.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|19.0|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|com.google.guava:guava|31.1-android|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.bouncycastle:bcprov-jdk15on|1.68|1.69|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|uuid|1.4.2|2.0.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|30.1-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.quarkus:quarkus-core|1.4.1.Final|2.6.0.CR1|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|4.3.6|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|io.netty:netty-common|4.1.45.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|20.0|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|org.apache.httpcomponents:httpclient|4.5.12|4.5.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-io:commons-io|2.6|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|27.0.1-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:1|
|org.apache.httpcomponents:httpclient|4.5.4|4.5.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-http2|4.1.45.Final|4.1.61.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|16.0.1|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|org.apache.httpcomponents:httpclient|4.5.10|4.5.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.smallrye.config:smallrye-config|1.6.1|1.6.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-io:commons-io|2.5|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.smallrye.config:smallrye-config|1.6.1|1.6.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.httpcomponents:httpclient|4.5.10|4.5.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-http2|4.1.30.Final|4.1.61.Final|间接依赖|可选修复|C:0|H:4|M:2|L:0|
|org.jsoup:jsoup|1.12.1|1.15.3|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|io.netty:netty-codec-http2|4.1.30.Final|4.1.61.Final|间接依赖|可选修复|C:0|H:4|M:2|L:0|
|io.netty:netty-codec-http|4.1.45.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:5|L:0|
|org.jsoup:jsoup|1.12.1|1.15.3|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|io.netty:netty-codec-http|4.1.45.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:5|L:0|
|commons-io:commons-io|2.5|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|619|Low|
|MIT|341|Low|
|EPL-2.0|17|Low|
|CC-BY-3.0|1|Low|
|ISC|22|Low|
|BSD-3-Clause|15|Low|
|自定义许可证|48|Low|
|CDDL-1.1|3|Low|
|BSD-2-Clause|7|Low|
|LGPL-3.0-or-later|4|Low|
|EPL-1.0|7|Low|
|BSD-like|1|Low|
|LGPL-2.1|3|Medium|
|LGPL-3.0|1|Medium|
|BSD|2|Low|
|CDDL-1.0|1|Low|
|UPL-1.0|1|Low|
|MPL-1.1|2|Low|
|CC0-1.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.netflix.ribbon:ribbon-core|2.3.0|间接依赖|maven|
|escape-string-regexp|1.0.5|间接依赖|npm|
|com.alibaba.csp:sentinel-cluster-common-default|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|org.junit.platform:junit-platform-commons|1.7.2|间接依赖|maven|
|io.netty:netty-buffer|4.1.63.Final|间接依赖|maven|
|spdx-exceptions|2.1.0|间接依赖|npm|
|globule|0.1.0|间接依赖|npm|
|com.google.api.grpc:proto-google-common-protos|2.0.1|间接依赖|maven|
|fs.realpath|1.0.0|直接依赖|npm|
|com.netflix.ribbon:ribbon-httpclient|2.3.0|间接依赖|maven|
|io.smallrye.reactive:mutiny|0.4.4|间接依赖|maven|
|com.netflix.eureka:eureka-client|1.9.4|间接依赖|maven|
|com.netflix.zuul:zuul-core|2.1.5|直接依赖|maven|
|gulp-serv|0.0.1|直接依赖|npm|
|com.alibaba.csp:sentinel-native-image-quarkus-adapter|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|org.springframework:spring-tx|5.3.17|间接依赖|maven|
|com.alibaba.csp:sentinel-motan-adapter|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|sigmund|1.0.1|直接依赖|npm|
|com.google.guava:guava|30.1-android|间接依赖|maven|
|glob-stream|3.1.18|间接依赖|npm|
|humanize|0.0.9|间接依赖|npm|
|kind-of|6.0.2|间接依赖|npm|
|io.quarkus:quarkus-vertx-core|1.4.1.Final|间接依赖|maven|
|meow|3.7.0|直接依赖|npm|
|console-browserify|1.1.0|间接依赖|npm|
|com.google.errorprone:error_prone_annotations|2.9.0|间接依赖|maven|
|com.google.code.gson:gson|2.8.5|间接依赖|maven|
|org.apache.maven.resolver:maven-resolver-transport-wagon|1.4.1|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.19|间接依赖|maven|
|is-buffer|1.1.6|直接依赖|npm|
|com.alibaba.csp:sentinel-dubbo-adapter|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|org.apache.rocketmq:rocketmq-client|4.2.0|直接依赖|maven|
|vow|0.4.4|间接依赖|npm|
|org.ow2.asm:asm-analysis|7.3.1|间接依赖|maven|
|org.apache.maven:maven-settings|3.6.3|间接依赖|maven|
|com.netflix.governator:governator|1.17.5|间接依赖|maven|
|brace-expansion|1.1.11|间接依赖|npm|
|org.apache.logging.log4j:log4j-to-slf4j|2.12.1|间接依赖|maven|
|com.alibaba.csp:sentinel-cluster-client-default|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|io.quarkus:quarkus-core|1.4.1.Final|直接依赖|maven|
|org.apache.commons:commons-math|2.2|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|间接依赖|maven|
|io.netty:netty-transport|4.1.27.Final|间接依赖|maven|
|cli|1.0.1|间接依赖|npm|
|body|5.1.0|间接依赖|npm|
|org.ow2.asm:asm|7.3.1|间接依赖|maven|
|graceful-readlink|1.0.1|直接依赖|npm|
|org.apache.httpcomponents:httpcore-nio|4.4.6|直接依赖|maven|
|trim-newlines|1.0.0|间接依赖|npm|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.60|间接依赖|maven|
|org.bouncycastle:bcutil-jdk15on|1.70|间接依赖|maven|
|ansi-gray|0.1.1|间接依赖|npm|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.2|间接依赖|maven|
|io.grpc:grpc-stub|1.34.1|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.9.6|间接依赖|maven|
|gulp-cssmin|0.2.0|直接依赖|npm|
|io.netty:netty-codec-mqtt|4.1.75.Final|间接依赖|maven|
|org.springframework:spring-context|4.3.16.RELEASE|间接依赖|maven|
|gulp-concat|2.6.1|直接依赖|npm|
|com.fasterxml.jackson.core:jackson-databind|2.13.2.1|直接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.5.12|间接依赖|maven|
|org.opentest4j:opentest4j|1.2.0|间接依赖|maven|
|pretty-hrtime|1.0.3|间接依赖|npm|
|com.sun.jersey:jersey-client|1.19.1|间接依赖|maven|
|io.netty:netty-handler|4.1.45.Final|间接依赖|maven|
|core-util-is|1.0.2|间接依赖|npm|
|io.grpc:grpc-context|1.51.0|间接依赖|maven|
|org.apache.maven.wagon:wagon-http-shared|3.3.4|间接依赖|maven|
|org.springframework:spring-aop|4.3.16.RELEASE|间接依赖|maven|
|clone-stats|0.0.1|间接依赖|npm|
|com.weibo:motan-transport-netty4|1.1.8|直接依赖|maven|
|io.opencensus:opencensus-contrib-grpc-metrics|0.17.0|间接依赖|maven|
|camelcase-keys|2.1.0|间接依赖|npm|
|io.netty:netty-transport|4.1.30.Final|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.70|间接依赖|maven|
|commons-configuration:commons-configuration|1.8|间接依赖|maven|
|ee-first|1.1.1|间接依赖|npm|
|range-parser|1.2.0|间接依赖|npm|
|connect|3.6.6|间接依赖|npm|
|org.springframework.cloud:spring-cloud-starter-config|2.0.0.RELEASE|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.6.6|间接依赖|maven|
|org.springframework:spring-context|5.2.8.RELEASE|间接依赖|maven|
|com.alibaba.csp:sentinel-annotation-cdi-interceptor|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|source-map-resolve|0.5.2|间接依赖|npm|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.46|间接依赖|maven|
|org.apache.maven:maven-builder-support|3.6.3|间接依赖|maven|
|define-property|2.0.2|间接依赖|npm|
|com.alibaba.csp:sentinel-apache-dubbo-adapter|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|javax.servlet:servlet-api|2.5|间接依赖|maven|
|path-parse|1.0.5|间接依赖|npm|
|org.jboss.spec.javax.xml.bind:jboss-jaxb-api_2.3_spec|1.0.1.Final|间接依赖|maven|
|normalize-package-data|2.4.0|间接依赖|npm|
|make-error|1.3.5|间接依赖|npm|
|jakarta.transaction:jakarta.transaction-api|1.3.3|间接依赖|maven|
|ansi-styles|2.2.1|间接依赖|npm|
|io.netty:netty-transport-native-kqueue|4.1.75.Final|间接依赖|maven|
|io.netty:netty-codec-http|4.1.45.Final|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.17|间接依赖|maven|
|org.springframework:spring-aop|5.2.15.RELEASE|间接依赖|maven|
|commons-codec:commons-codec|1.11|间接依赖|maven|
|io.reactivex:rxnetty|0.4.9|间接依赖|maven|
|com.alibaba.nacos:nacos-client|1.4.2|直接依赖|maven|
|com.google.guava:guava|29.0-android|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.60|间接依赖|maven|
|org.jboss.slf4j:slf4j-jboss-logging|1.2.0.Final|间接依赖|maven|
|vinyl-sourcemaps-apply|0.2.1|间接依赖|npm|
|io.micrometer:micrometer-core|1.5.14|间接依赖|maven|
|org.jboss.logging:commons-logging-jboss-logging|1.0.0.Final|间接依赖|maven|
|com.sun.istack:istack-commons-runtime|3.0.10|间接依赖|maven|
|org.jboss.netty:netty|3.2.5.Final|间接依赖|maven|
|commander|2.0.0|间接依赖|npm|
|gulp|3.9.1|直接依赖|npm|
|org.jboss.resteasy:resteasy-jaxrs|3.6.3.Final|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.79.Final|间接依赖|maven|
|com.netflix.hystrix:hystrix-core|1.5.18|间接依赖|maven|
|org.apache.maven:maven-model|3.6.3|间接依赖|maven|
|io.opentracing:opentracing-mock|0.22.0|间接依赖|maven|
|org.springframework:spring-expression|4.3.16.RELEASE|间接依赖|maven|
|io.netty:netty-handler|4.1.30.Final|间接依赖|maven|
|com.github.andrewoma.dexx:dexx-collections|0.2|间接依赖|maven|
|org.jboss.resteasy:resteasy-spring-boot-starter|4.5.1.Final|直接依赖|maven|
|org.springframework.cloud:spring-cloud-starter|2.2.9.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.9.6|间接依赖|maven|
|org.springframework:spring-context-support|5.3.15|直接依赖|maven|
|gulp-uglify|3.0.1|直接依赖|npm|
|io.quarkus.security:quarkus-security|1.1.0.Final|间接依赖|maven|
|map-obj|1.0.1|间接依赖|npm|
|io.grpc:grpc-protobuf-lite|1.17.1|间接依赖|maven|
|org.springframework.cloud:spring-cloud-config-client|2.0.0.RELEASE|间接依赖|maven|
|arr-flatten|1.1.0|间接依赖|npm|
|org.apache.maven:maven-embedder|3.6.3|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.12.6|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.2|间接依赖|maven|
|send|0.16.2|间接依赖|npm|
|io.netty:netty-transport-sctp|4.1.75.Final|间接依赖|maven|
|io.netty:netty-codec|4.1.45.Final|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.30|间接依赖|maven|
|com.alibaba:fastjson|1.2.83_noneautotype|直接依赖|maven|
|map-cache|0.2.2|间接依赖|npm|
|org.apache.maven:maven-core|3.6.3|间接依赖|maven|
|io.quarkus.http:quarkus-http-servlet|3.0.6.Final|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter|2.0.0.RELEASE|间接依赖|maven|
|parse-filepath|1.0.2|间接依赖|npm|
|vow-queue|0.3.1|间接依赖|npm|
|com.netflix.ribbon:ribbon|2.3.0|间接依赖|maven|
|rcfinder|0.1.9|间接依赖|npm|
|com.github.fge:msg-simple|1.1|间接依赖|maven|
|io.opensergo:opensergo-java-sdk|0.1.0|直接依赖|maven|
|org.springframework.boot:spring-boot|2.2.2.RELEASE|间接依赖|maven|
|org.springframework.security:spring-security-rsa|1.0.9.RELEASE|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.56|间接依赖|maven|
|org.checkerframework:checker-compat-qual|2.5.2|间接依赖|maven|
|sifter|0.5.3|间接依赖|npm|
|is-number|3.0.0|间接依赖|npm|
|io.netty:netty-buffer|4.1.30.Final|间接依赖|maven|
|com.alipay.sofa:hessian|3.3.7|间接依赖|maven|
|com.alipay.sofa:tracer-core|3.0.8|间接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|2.9.0|间接依赖|maven|
|lodash._basetostring|3.0.1|间接依赖|npm|
|org.springframework.boot:spring-boot-starter-tomcat|2.3.12.RELEASE|间接依赖|maven|
|org.aspectj:aspectjweaver|1.8.6|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-validation|2.6.3|间接依赖|maven|
|org.jsoup:jsoup|1.12.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.3.12.RELEASE|间接依赖|maven|
|org.slf4j:slf4j-log4j12|1.7.25|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.68|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.29|间接依赖|maven|
|io.netty:netty-common|4.1.75.Final|间接依赖|maven|
|lodash._reescape|3.0.0|间接依赖|npm|
|org.slf4j:slf4j-api|1.7.7|间接依赖|maven|
|commons-codec:commons-codec|1.9|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.11|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.2.2.RELEASE|间接依赖|maven|
|org.apache.maven.resolver:maven-resolver-util|1.4.1|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.12|间接依赖|maven|
|uuid|1.4.2|间接依赖|npm|
|org.jboss.spec.javax.xml.bind:jboss-jaxb-api_2.3_spec|2.0.0.Final|间接依赖|maven|
|redent|1.0.0|间接依赖|npm|
|process-nextick-args|2.0.0|间接依赖|npm|
|dom-serializer|0.1.1|间接依赖|npm|
|com.netflix.netflix-commons:netflix-eventbus|0.3.0|间接依赖|maven|
|com.google.guava:guava|15.0|间接依赖|maven|
|com.alibaba.csp:sentinel-cluster-server-default|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.5.12|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|redeyed|1.0.1|间接依赖|npm|
|array-each|1.0.1|间接依赖|npm|
|com.netflix.governator:governator-api|1.17.5|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.10.0|间接依赖|maven|
|commons-fileupload:commons-fileupload|1.3|间接依赖|maven|
|decode-uri-component|0.2.0|间接依赖|npm|
|com.alibaba.spring:spring-context-support|1.0.11|间接依赖|maven|
|gulplog|1.0.0|间接依赖|npm|
|ansi-cyan|0.1.1|间接依赖|npm|
|commons-lang:commons-lang|2.6|直接依赖|maven|
|io.grpc:grpc-protobuf|1.42.1|间接依赖|maven|
|io.netty:netty-buffer|4.1.48.Final|间接依赖|maven|
|org.yaml:snakeyaml|1.25|间接依赖|maven|
|tildify|1.2.0|间接依赖|npm|
|io.netty:netty-transport-native-epoll|4.1.27.Final|间接依赖|maven|
|ret|0.1.15|间接依赖|npm|
|make-error-cause|1.2.2|间接依赖|npm|
|io.netty:netty-buffer|4.1.75.Final|间接依赖|maven|
|io.netty:netty-common|4.1.63.Final|间接依赖|maven|
|glob2base|0.0.12|间接依赖|npm|
|io.netty:netty-handler|4.1.48.Final|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|batch|0.6.1|间接依赖|npm|
|org.yaml:snakeyaml|1.26|间接依赖|maven|
|org.eclipse.microprofile.config:microprofile-config-api|1.4|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.21|间接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.17.1|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|直接依赖|maven|
|com.google.guava:guava|18.0|间接依赖|maven|
|angular-ui-router|1.0.19|直接依赖|npm|
|org.apache.httpcomponents:httpcore|4.4.7|间接依赖|maven|
|org.apache.curator:curator-framework|4.0.1|间接依赖|maven|
|com.alipay.sofa:bolt|1.5.6|间接依赖|maven|
|detect-file|1.0.0|间接依赖|npm|
|io.netty:netty-resolver|4.1.75.Final|间接依赖|maven|
|com.alibaba.csp:sentinel-transport-simple-http|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|io.netty:netty-codec-dns|4.1.45.Final|间接依赖|maven|
|has-ansi|2.0.0|间接依赖|npm|
|org.apache.logging.log4j:log4j-api|2.17.1|间接依赖|maven|
|get-value|2.0.6|间接依赖|npm|
|io.quarkus:quarkus-builder|1.4.1.Final|间接依赖|maven|
|org.yaml:snakeyaml|1.20|间接依赖|maven|
|mime-db|1.38.0|间接依赖|npm|
|jakarta.el:jakarta.el-api|3.0.3|间接依赖|maven|
|ansi-colors|2.0.5|间接依赖|npm|
|io.netty:netty-codec-xml|4.1.75.Final|间接依赖|maven|
|org.apache.maven.wagon:wagon-file|3.3.4|间接依赖|maven|
|io.netty:netty-codec|4.1.75.Final|间接依赖|maven|
|org.apache.maven.wagon:wagon-http|3.3.4|间接依赖|maven|
|io.quarkus:quarkus-vertx-http|1.4.1.Final|间接依赖|maven|
|lodash._escapehtmlchar|2.4.1|直接依赖|npm|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.10.3|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.3|直接依赖|maven|
|gulp-connect|5.7.0|直接依赖|npm|
|angular-resource|1.7.2|直接依赖|npm|
|org.springframework:spring-core|5.3.15|间接依赖|maven|
|org.springframework:spring-aop|5.2.8.RELEASE|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.8|直接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.0.Final|间接依赖|maven|
|joda-time:joda-time|2.3|间接依赖|maven|
|com.alibaba.csp:sentinel-datasource-zookeeper|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|com.netflix.spectator:spectator-api|0.59.0|间接依赖|maven|
|bootstrap-tagsinput|0.7.1|直接依赖|npm|
|com.ctrip.framework.apollo:apollo-core|1.5.0|间接依赖|maven|
|com.sun.activation:jakarta.activation|1.2.1|间接依赖|maven|
|object-assign|3.0.0|间接依赖|npm|
|csscomb|3.1.8|间接依赖|npm|
|io.netty:netty-codec-smtp|4.1.75.Final|间接依赖|maven|
|io.reactivex:rxjava-reactive-streams|1.2.1|间接依赖|maven|
|io.netty:netty|3.10.6.Final|间接依赖|maven|
|find-up|1.1.2|间接依赖|npm|
|resolve-dir|1.0.1|间接依赖|npm|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|is-glob|3.1.0|间接依赖|npm|
|fill-range|4.0.0|间接依赖|npm|
|io.netty:netty-handler-proxy|4.1.63.Final|间接依赖|maven|
|org.springframework.security:spring-security-rsa|1.0.10.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.10.3|间接依赖|maven|
|io.netty:netty-handler|4.1.50.Final|间接依赖|maven|
|org.json:json|20090211|间接依赖|maven|
|load-json-file|1.1.0|间接依赖|npm|
|org.springframework.cloud:spring-cloud-context|2.0.0.RELEASE|间接依赖|maven|
|component-emitter|1.2.1|间接依赖|npm|
|com.weibo:motan-core|1.1.8|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.2|间接依赖|maven|
|org.checkerframework:checker-compat-qual|2.0.0|间接依赖|maven|
|org.jboss.spec.javax.annotation:jboss-annotations-api_1.3_spec|1.0.1.Final|间接依赖|maven|
|io.quarkus:quarkus-core-deployment|1.4.1.Final|直接依赖|maven|
|io.opentracing:opentracing-api|0.22.0|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.11|间接依赖|maven|
|org.springframework:spring-aop|5.3.17|间接依赖|maven|
|com.google.guava:guava|16.0.1|间接依赖|maven|
|org.apache.commons:commons-lang3|3.9|间接依赖|maven|
|etag|1.8.1|间接依赖|npm|
|hosted-git-info|2.7.1|间接依赖|npm|
|io.netty:netty-tcnative-boringssl-static|2.0.12.Final|间接依赖|maven|
|com.google.inject:guice|4.2.1|间接依赖|maven|
|lodash._basevalues|3.0.0|间接依赖|npm|
|io.quarkus.arc:arc-processor|1.4.1.Final|间接依赖|maven|
|node-uuid|1.4.0|间接依赖|npm|
|io.grpc:grpc-protobuf-lite|1.51.0|间接依赖|maven|
|org.jboss.resteasy:resteasy-jaxb-provider|4.5.3.Final|间接依赖|maven|
|com.alibaba.nacos:nacos-common|1.4.2|间接依赖|maven|
|encodeurl|1.0.2|间接依赖|npm|
|commons-io:commons-io|2.6|间接依赖|maven|
|wordwrap|0.0.3|间接依赖|npm|
|ch.qos.reload4j:reload4j|1.2.19|间接依赖|maven|
|com.google.guava:guava|30.1-jre|间接依赖|maven|
|tiny-lr|1.1.1|间接依赖|npm|
|javax.inject:javax.inject|1|间接依赖|maven|
|org.springframework:spring-webflux|5.3.18|间接依赖|maven|
|com.alibaba:dubbo|2.6.12|直接依赖|maven|
|which|1.3.1|间接依赖|npm|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.9.8|间接依赖|maven|
|io.projectreactor:reactor-core|3.4.16|间接依赖|maven|
|com.alibaba.csp:sentinel-zuul-adapter|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.12.6|间接依赖|maven|
|org.springframework.security:spring-security-crypto|5.6.1|间接依赖|maven|
|io.quarkus:quarkus-ide-launcher|1.4.1.Final|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.3.4|间接依赖|maven|
|org.jboss.metadata:jboss-metadata-web|11.0.0.Final|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.3.2.Final|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.79.Final|间接依赖|maven|
|entities|1.0.0|间接依赖|npm|
|org.springframework:spring-webmvc|5.3.18|间接依赖|maven|
|org.jboss.resteasy:resteasy-jackson2-provider|4.5.3.Final|间接依赖|maven|
|com.alibaba.csp:sentinel-zuul2-adapter|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|statuses|1.3.1|间接依赖|npm|
|io.opentracing:opentracing-util|0.22.0|间接依赖|maven|
|io.netty:netty-resolver|4.1.45.Final|间接依赖|maven|
|io.perfmark:perfmark-api|0.19.0|间接依赖|maven|
|org.yaml:snakeyaml|1.23|间接依赖|maven|
|org.sonatype.plexus:plexus-cipher|1.4|间接依赖|maven|
|readable-stream|1.1.14|间接依赖|npm|
|io.envoyproxy.controlplane:api|1.0.36|间接依赖|maven|
|io.netty:netty-codec-http|4.1.27.Final|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.79.Final|间接依赖|maven|
|to-regex|3.0.2|间接依赖|npm|
|temp-write|0.1.1|间接依赖|npm|
|angular-animate|1.7.2|直接依赖|npm|
|io.netty:netty-transport|4.1.50.Final|间接依赖|maven|
|array-differ|1.0.0|间接依赖|npm|
|io.netty:netty-codec-http|4.1.63.Final|间接依赖|maven|
|com.google.code.gson:gson|2.9.0|间接依赖|maven|
|io.netty:netty-all|4.1.44.Final|间接依赖|maven|
|homedir-polyfill|1.0.1|间接依赖|npm|
|com.netflix.hystrix:hystrix-javanica|1.5.18|间接依赖|maven|
|org.jboss.resteasy:resteasy-core-spi|4.5.3.Final|间接依赖|maven|
|builtin-modules|1.1.1|间接依赖|npm|
|atob|2.1.1|间接依赖|npm|
|micromatch|3.1.10|间接依赖|npm|
|org.glassfish.jaxb:jaxb-runtime|2.3.3-b02|间接依赖|maven|
|antlr:antlr|2.7.7|间接依赖|maven|
|com.github.spotbugs:spotbugs-annotations|3.1.9|间接依赖|maven|
|com.alibaba.csp:sentinel-datasource-apollo|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|rechoir|0.6.2|间接依赖|npm|
|org.apache.logging.log4j:log4j-api|2.12.1|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.4.14|直接依赖|maven|
|bytes|1.0.0|间接依赖|npm|
|org.springframework:spring-expression|5.2.8.RELEASE|间接依赖|maven|
|moment|2.22.2|间接依赖|npm|
|expand-brackets|2.1.4|间接依赖|npm|
|lodash._htmlescapes|2.4.1|间接依赖|npm|
|lodash._isnative|2.4.1|直接依赖|npm|
|com.alibaba.spring:spring-context-support|1.0.2|直接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-netflix-zuul|2.2.10.RELEASE|直接依赖|maven|
|vow-fs|0.3.2|间接依赖|npm|
|com.alibaba.csp:sentinel-datasource-extension|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.34.1|间接依赖|maven|
|io.reactivex:rxjava|1.2.1|间接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.42.1|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.30.Final|间接依赖|maven|
|org.springframework.cloud:spring-cloud-netflix-archaius|2.2.10.RELEASE|间接依赖|maven|
|com.netflix.ribbon:ribbon-core|2.2.4|间接依赖|maven|
|date-now|0.1.4|间接依赖|npm|
|lodash._basecopy|3.0.1|间接依赖|npm|
|io.etcd:jetcd-core|0.3.0|直接依赖|maven|
|domutils|1.5.1|间接依赖|npm|
|@uirouter/core|5.0.20|间接依赖|npm|
|rimraf|2.6.2|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|io.projectreactor.addons:reactor-extra|3.4.6|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.2|间接依赖|maven|
|org.ow2.asm:asm|5.0.4|间接依赖|maven|
|ng-dialog|0.6.6|直接依赖|npm|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|com.google.protobuf:protobuf-java-util|3.5.1|间接依赖|maven|
|split-string|3.1.0|间接依赖|npm|
|com.alibaba.csp:sentinel-datasource-nacos|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|io.vertx:vertx-web|3.8.5|间接依赖|maven|
|org.yaml:snakeyaml|1.28|间接依赖|maven|
|org.glassfish:javax.json|1.1.2|间接依赖|maven|
|org.springframework:spring-expression|5.3.18|间接依赖|maven|
|gaze|0.5.2|间接依赖|npm|
|com.fasterxml.jackson.core:jackson-core|2.10.3|间接依赖|maven|
|io.netty:netty-transport-udt|4.1.75.Final|间接依赖|maven|
|io.projectreactor:reactor-core|3.3.6.RELEASE|间接依赖|maven|
|semver|4.3.6|间接依赖|npm|
|org.springframework:spring-beans|5.3.15|间接依赖|maven|
|io.grpc:grpc-context|1.34.1|间接依赖|maven|
|io.smallrye.config:smallrye-config|1.6.1|间接依赖|maven|
|cache-base|1.0.1|间接依赖|npm|
|mixin-deep|1.3.2|间接依赖|npm|
|io.netty:netty-common|4.1.30.Final|间接依赖|maven|
|io.grpc:grpc-grpclb|1.17.1|间接依赖|maven|
|org.codehaus.plexus:plexus-interpolation|1.25|间接依赖|maven|
|com.github.vlsi.compactmap:compactmap|1.2.1|间接依赖|maven|
|org.jboss.threads:jboss-threads|3.1.1.Final|间接依赖|maven|
|io.etcd:jetcd-resolver|0.3.0|间接依赖|maven|
|base|0.11.2|间接依赖|npm|
|io.netty:netty-common|4.1.50.Final|间接依赖|maven|
|is-data-descriptor|0.1.4|间接依赖|npm|
|remove-trailing-separator|1.1.0|直接依赖|npm|
|io.vertx:vertx-core|3.8.5|间接依赖|maven|
|pascalcase|0.1.1|间接依赖|npm|
|lodash._root|3.0.1|间接依赖|npm|
|com.codahale.metrics:metrics-core|3.0.1|间接依赖|maven|
|lodash.isobject|2.4.1|间接依赖|npm|
|io.grpc:grpc-context|1.17.1|间接依赖|maven|
|org.springframework:spring-beans|5.3.18|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.27.Final|间接依赖|maven|
|org.springframework:spring-core|5.1.18.RELEASE|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.46|间接依赖|maven|
|org.hamcrest:hamcrest|2.2|间接依赖|maven|
|urix|0.1.0|间接依赖|npm|
|multipipe|0.1.2|间接依赖|npm|
|org.springframework:spring-test|5.3.18|间接依赖|maven|
|org.springframework:spring-jcl|5.2.15.RELEASE|间接依赖|maven|
|global-modules|1.0.0|间接依赖|npm|
|angular-cookies|1.7.2|直接依赖|npm|
|strip-bom|1.0.0|间接依赖|npm|
|org.springframework.boot:spring-boot-starter|2.2.2.RELEASE|间接依赖|maven|
|org.slf4j:slf4j-reload4j|1.7.36|直接依赖|maven|
|io.netty:netty-transport-rxtx|4.1.75.Final|间接依赖|maven|
|lodash._reunescapedhtml|2.4.1|直接依赖|npm|
|gulp-jshint|2.1.0|直接依赖|npm|
|org.eclipse.microprofile.context-propagation:microprofile-context-propagation-api|1.0.1|间接依赖|maven|
|io.perfmark:perfmark-api|0.23.0|间接依赖|maven|
|io.netty:netty-common|4.1.45.Final|间接依赖|maven|
|com.google.code.gson:gson|2.8.2|间接依赖|maven|
|path-root|0.1.1|间接依赖|npm|
|org.springframework:spring-context|5.3.18|间接依赖|maven|
|plugin-error|0.1.2|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|accepts|1.3.5|间接依赖|npm|
|org.apache.httpcomponents:httpcore|4.4.6|间接依赖|maven|
|com.sun.jersey.contribs:jersey-apache-client4|1.19.1|间接依赖|maven|
|org.bouncycastle:bcpg-jdk15on|1.61|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.11|直接依赖|maven|
|io.netty:netty-codec|4.1.50.Final|间接依赖|maven|
|lru-cache|2.7.3|直接依赖|npm|
|com.google.inject:guice|4.1.0|间接依赖|maven|
|io.reactivex:rxnetty-contexts|0.4.9|间接依赖|maven|
|org.apache.curator:curator-client|4.0.1|间接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.64|间接依赖|maven|
|org.springframework:spring-core|5.2.15.RELEASE|间接依赖|maven|
|io.vertx:vertx-auth-common|3.8.5|间接依赖|maven|
|domelementtype|1.3.1|间接依赖|npm|
|org.jboss.resteasy:resteasy-jackson2-provider|3.6.3.Final|间接依赖|maven|
|org.checkerframework:checker-qual|3.12.0|间接依赖|maven|
|com.vaadin.external.google:android-json|0.0.20131108.vaadin1|间接依赖|maven|
|com.alipay.sofa.common:sofa-common-tools|1.0.18|间接依赖|maven|
|error|7.0.2|间接依赖|npm|
|unique-stream|1.0.0|间接依赖|npm|
|com.fasterxml.jackson.core:jackson-core|2.12.2|间接依赖|maven|
|io.grpc:grpc-stub|1.42.1|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-afterburner|2.7.5|间接依赖|maven|
|org.apache.rocketmq:rocketmq-common|4.2.0|间接依赖|maven|
|org.glassfish.jaxb:txw2|2.3.3-b02|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-netflix-hystrix|2.2.10.RELEASE|间接依赖|maven|
|extend-shallow|3.0.2|间接依赖|npm|
|org.apache.curator:curator-recipes|4.0.1|直接依赖|maven|
|com.netflix.netflix-commons:netflix-statistics|0.1.1|间接依赖|maven|
|array-find-index|1.0.2|间接依赖|npm|
|org.apache.logging.log4j:log4j-api|2.13.3|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.63.Final|间接依赖|maven|
|com.google.inject.extensions:guice-grapher|4.1.0|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.2.0|间接依赖|maven|
|ordered-read-streams|0.1.0|间接依赖|npm|
|org.slf4j:slf4j-api|1.7.25|间接依赖|maven|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|lodash.template|3.6.2|间接依赖|npm|
|com.fasterxml.jackson.core:jackson-databind|2.10.3|间接依赖|maven|
|is-relative|1.0.0|间接依赖|npm|
|is-windows|1.0.2|间接依赖|npm|
|org.bouncycastle:bcpkix-jdk15on|1.70|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.5|间接依赖|maven|
|org.springframework.cloud:spring-cloud-commons|2.0.0.RELEASE|间接依赖|maven|
|filesize|2.0.4|间接依赖|npm|
|org.apache.httpcomponents:httpclient|4.5.4|间接依赖|maven|
|org.jboss.resteasy:resteasy-servlet-initializer|4.5.3.Final|间接依赖|maven|
|lodash._reinterpolate|3.0.0|间接依赖|npm|
|arr-union|3.1.0|间接依赖|npm|
|is-accessor-descriptor|0.1.6|间接依赖|npm|
|finalhandler|1.1.0|间接依赖|npm|
|array-unique|0.3.2|间接依赖|npm|
|org.jboss.spec.javax.ws.rs:jboss-jaxrs-api_2.1_spec|2.0.1.Final|间接依赖|maven|
|net.sf.jopt-simple:jopt-simple|4.6|间接依赖|maven|
|io.grpc:grpc-core|1.34.1|间接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.3|直接依赖|maven|
|safe-json-parse|1.0.1|间接依赖|npm|
|javax.activation:activation|1.1.1|间接依赖|maven|
|io.netty:netty-buffer|4.1.45.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.9.0|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.11.4|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|com.alibaba.csp:sentinel-annotation-quarkus-adapter|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|commons-io:commons-io|2.5|间接依赖|maven|
|org.springframework:spring-context-support|5.3.17|间接依赖|maven|
|io.netty:netty-buffer|4.1.27.Final|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.75.Final|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|jakarta.transaction:jakarta.transaction-api|1.3.2|间接依赖|maven|
|sparkles|1.0.1|间接依赖|npm|
|org.apache.maven.resolver:maven-resolver-api|1.4.1|间接依赖|maven|
|snapdragon-node|2.1.1|间接依赖|npm|
|arr-diff|4.0.0|间接依赖|npm|
|commons-io:commons-io|2.4|间接依赖|maven|
|io.grpc:grpc-protobuf|1.17.1|间接依赖|maven|
|org.codehaus.groovy:groovy-all|2.4.4|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.75.Final|间接依赖|maven|
|io.netty:netty-resolver|4.1.50.Final|间接依赖|maven|
|io.quarkus:quarkus-bootstrap-core|1.4.1.Final|间接依赖|maven|
|path-is-absolute|1.0.1|直接依赖|npm|
|string-template|0.2.1|间接依赖|npm|
|com.google.guava:guava|20.0|间接依赖|maven|
|regex-not|1.0.2|间接依赖|npm|
|jshint|2.10.2|直接依赖|npm|
|org.springframework.cloud:spring-cloud-commons|3.1.1|间接依赖|maven|
|org.jboss.spec.javax.ws.rs:jboss-jaxrs-api_2.1_spec|1.0.2.Final|间接依赖|maven|
|org.apache.maven:maven-model-builder|3.6.3|间接依赖|maven|
|com.caucho:hessian|4.0.38|间接依赖|maven|
|org.springframework:spring-core|4.3.16.RELEASE|间接依赖|maven|
|serve-static|1.13.2|间接依赖|npm|
|org.apache.logging.log4j:log4j-slf4j-impl|2.17.1|直接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.1.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.2.2.RELEASE|间接依赖|maven|
|commons-pool:commons-pool|1.6|间接依赖|maven|
|is-plain-object|2.0.4|间接依赖|npm|
|has-value|1.0.0|间接依赖|npm|
|fresh|0.5.2|间接依赖|npm|
|liftoff|2.5.0|间接依赖|npm|
|org.bouncycastle:bcpkix-jdk15on|1.68|间接依赖|maven|
|org.springframework.cloud:spring-cloud-netflix-ribbon|2.2.10.RELEASE|间接依赖|maven|
|org.graalvm.sdk:graal-sdk|19.3.1|间接依赖|maven|
|beeper|1.1.1|间接依赖|npm|
|commons-codec:commons-codec|1.10|间接依赖|maven|
|com.alibaba.csp:sentinel-apache-httpclient-adapter|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|isobject|3.0.1|间接依赖|npm|
|deprecated|0.0.1|间接依赖|npm|
|io.netty:netty-codec|4.1.27.Final|间接依赖|maven|
|org.javassist:javassist|3.23.1-GA|间接依赖|maven|
|decamelize|1.2.0|间接依赖|npm|
|org.springframework.boot:spring-boot-starter-web|2.5.12|直接依赖|maven|
|array-uniq|1.0.3|间接依赖|npm|
|http-parser-js|0.5.0|间接依赖|npm|
|com.google.errorprone:error_prone_annotations|2.1.3|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.12.6|间接依赖|maven|
|io.grpc:grpc-core|1.42.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-webflux|2.5.12|直接依赖|maven|
|number-is-nan|1.0.1|间接依赖|npm|
|io.opencensus:opencensus-api|0.17.0|间接依赖|maven|
|optimist|0.6.1|间接依赖|npm|
|org.apache.logging.log4j:log4j-api|2.17.2|间接依赖|maven|
|io.netty:netty-all|4.1.42.Final|间接依赖|maven|
|uglify-js|3.4.9|间接依赖|npm|
|vinyl|0.5.3|间接依赖|npm|
|io.quarkus.http:quarkus-http-http-core|3.0.6.Final|间接依赖|maven|
|io.netty:netty-resolver|4.1.48.Final|间接依赖|maven|
|io.grpc:grpc-api|1.51.0|间接依赖|maven|
|is-wsl|1.1.0|间接依赖|npm|
|io.smallrye.config:smallrye-config-common|1.6.1|间接依赖|maven|
|com.netflix.ribbon:ribbon-loadbalancer|2.2.4|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.61|间接依赖|maven|
|parse-json|2.2.0|间接依赖|npm|
|io.netty:netty-handler-proxy|4.1.30.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-test|2.5.12|直接依赖|maven|
|org.openjdk.jmh:jmh-core|1.21|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.12.2|间接依赖|maven|
|org.slf4j:slf4j-log4j12|1.7.21|直接依赖|maven|
|ansi-wrap|0.1.0|间接依赖|npm|
|assign-symbols|1.0.0|间接依赖|npm|
|io.vertx:vertx-bridge-common|3.8.5|间接依赖|maven|
|jakarta.ejb:jakarta.ejb-api|3.2.6|间接依赖|maven|
|csscomb-core|3.0.0-3.1|间接依赖|npm|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.3.12.RELEASE|间接依赖|maven|
|angular-selectize2|1.2.3|直接依赖|npm|
|fancy-log|1.3.2|间接依赖|npm|
|org.jboss.logging:jboss-logging-annotations|2.1.0.Final|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.9.8|间接依赖|maven|
|on-finished|2.3.0|间接依赖|npm|
|ng-tags-input|3.0.0|直接依赖|npm|
|io.grpc:grpc-netty|1.51.0|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.9|间接依赖|maven|
|org.junit.jupiter:junit-jupiter|5.7.2|间接依赖|maven|
|io.grpc:grpc-core|1.17.1|间接依赖|maven|
|com.alibaba.csp:sentinel-annotation-aspectj|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|com.google.inject.extensions:guice-assistedinject|4.1.0|间接依赖|maven|
|isarray|0.0.1|间接依赖|npm|
|org.springframework.cloud:spring-cloud-gateway-server|3.1.1|间接依赖|maven|
|org.apache.curator:curator-framework|5.1.0|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|source-map-url|0.4.0|间接依赖|npm|
|read-pkg-up|1.0.1|间接依赖|npm|
|com.alibaba.csp:sentinel-spring-cloud-gateway-adapter|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.12.6|间接依赖|maven|
|cardinal|1.0.0|间接依赖|npm|
|xtend|4.0.1|间接依赖|npm|
|glogg|1.0.1|间接依赖|npm|
|org.jboss.resteasy:resteasy-netty4|3.6.3.Final|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.75.Final|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.75.Final|间接依赖|maven|
|continuable-cache|0.3.1|间接依赖|npm|
|org.skyscreamer:jsonassert|1.5.0|间接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.75.Final|间接依赖|maven|
|org.checkerframework:checker-qual|3.5.0|间接依赖|maven|
|org.jboss.resteasy:resteasy-client|4.5.3.Final|间接依赖|maven|
|org.springframework:spring-webmvc|5.2.15.RELEASE|间接依赖|maven|
|extend|3.0.2|间接依赖|npm|
|org.slf4j:slf4j-api|1.7.26|间接依赖|maven|
|io.grpc:grpc-protobuf|1.34.1|直接依赖|maven|
|negotiator|0.6.1|间接依赖|npm|
|mime-types|2.1.22|间接依赖|npm|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.11.4|间接依赖|maven|
|org.mockito:mockito-junit-jupiter|3.9.0|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter|3.1.1|间接依赖|maven|
|array-slice|1.1.0|间接依赖|npm|
|org.apache.httpcomponents:httpclient|4.5.3|直接依赖|maven|
|io.prometheus:simpleclient|0.5.0|间接依赖|maven|
|is-utf8|0.2.1|间接依赖|npm|
|org.springframework.boot:spring-boot-starter-logging|2.5.12|直接依赖|maven|
|lodash._getnative|3.9.1|间接依赖|npm|
|io.netty:netty-common|4.1.48.Final|间接依赖|maven|
|clone|1.0.4|间接依赖|npm|
|org.apache.curator:curator-recipes|5.1.0|直接依赖|maven|
|safe-regex|1.1.0|间接依赖|npm|
|io.netty:netty-resolver|4.1.27.Final|间接依赖|maven|
|mkdirp|0.5.1|间接依赖|npm|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.10.3|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.12|间接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|1.0.0|间接依赖|maven|
|org.codehaus.plexus:plexus-component-annotations|2.1.0|间接依赖|maven|
|glob-watcher|0.0.6|间接依赖|npm|
|ini|1.3.5|间接依赖|npm|
|com.google.guava:guava|25.0-jre|间接依赖|maven|
|currently-unhandled|0.4.1|间接依赖|npm|
|org.junit.jupiter:junit-jupiter-engine|5.7.2|间接依赖|maven|
|org.ow2.asm:asm-util|7.3.1|间接依赖|maven|
|io.quarkus:quarkus-resteasy|1.4.1.Final|直接依赖|maven|
|flagged-respawn|1.0.1|间接依赖|npm|
|com.fasterxml.jackson.core:jackson-annotations|2.12.2|间接依赖|maven|
|class-utils|0.3.6|间接依赖|npm|
|org.springframework.cloud:spring-cloud-starter-gateway|3.1.1|直接依赖|maven|
|inherits|2.0.3|间接依赖|npm|
|com.netflix.archaius:archaius-core|0.7.7|间接依赖|maven|
|org.springframework.retry:spring-retry|1.2.4.RELEASE|直接依赖|maven|
|raw-body|1.1.7|间接依赖|npm|
|color-support|1.1.3|间接依赖|npm|
|com.alibaba.csp:sentinel-logging-slf4j|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|org.springframework.cloud:spring-cloud-netflix-zuul|2.2.10.RELEASE|间接依赖|maven|
|com.google.code.gson:gson|2.8.6|间接依赖|maven|
|qs|6.6.0|间接依赖|npm|
|gulp-rename|1.1.0|间接依赖|npm|
|org.ow2.asm:asm-tree|7.3.1|间接依赖|maven|
|union-value|1.0.1|间接依赖|npm|
|org.apache.curator:curator-client|5.1.0|间接依赖|maven|
|graceful-fs|3.0.11|间接依赖|npm|
|resolve-url|0.2.1|间接依赖|npm|
|org.springframework.cloud:spring-cloud-starter-netflix-archaius|2.2.10.RELEASE|间接依赖|maven|
|end-of-stream|0.1.5|间接依赖|npm|
|rcloader|0.2.2|间接依赖|npm|
|io.netty:netty-codec-socks|4.1.75.Final|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-core|1.0.17|间接依赖|maven|
|com.google.inject.extensions:guice-multibindings|4.1.0|间接依赖|maven|
|io.quarkus.arc:arc|1.4.1.Final|间接依赖|maven|
|com.google.guava:guava|26.0-android|间接依赖|maven|
|org.apache.maven.shared:maven-shared-utils|3.2.1|间接依赖|maven|
|validate-npm-package-license|3.0.3|间接依赖|npm|
|io.quarkus:quarkus-arc-deployment|1.4.1.Final|直接依赖|maven|
|io.netty:netty-common|4.1.27.Final|间接依赖|maven|
|io.grpc:grpc-netty|1.17.1|间接依赖|maven|
|balanced-match|1.0.0|间接依赖|npm|
|io.opentracing:opentracing-noop|0.22.0|间接依赖|maven|
|io.netty:netty-codec-stomp|4.1.75.Final|间接依赖|maven|
|io.netty:netty-all|4.0.42.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-redis|2.5.12|间接依赖|maven|
|org.springframework:spring-web|5.2.15.RELEASE|间接依赖|maven|
|lodash._objecttypes|2.4.1|间接依赖|npm|
|escape-html|1.0.3|间接依赖|npm|
|jakarta.servlet:jakarta.servlet-api|4.0.3|间接依赖|maven|
|javax.validation:validation-api|2.0.1.Final|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.0|间接依赖|maven|
|snapdragon-util|3.0.1|间接依赖|npm|
|through2|2.0.3|间接依赖|npm|
|object.defaults|1.1.0|间接依赖|npm|
|org.springframework:spring-jcl|5.3.18|间接依赖|maven|
|net.jcip:jcip-annotations|1.0|间接依赖|maven|
|indent-string|2.1.0|间接依赖|npm|
|io.netty:netty-transport-classes-epoll|4.1.75.Final|间接依赖|maven|
|org.apache.commons:commons-lang3|3.4|间接依赖|maven|
|collection-visit|1.0.0|间接依赖|npm|
|io.netty:netty-codec-http2|4.1.45.Final|间接依赖|maven|
|io.netty:netty-handler|4.1.75.Final|间接依赖|maven|
|com.google.inject.extensions:guice-throwingproviders|4.0|间接依赖|maven|
|org.wildfly.common:wildfly-common|1.5.4.Final-format-001|间接依赖|maven|
|io.grpc:grpc-netty-shaded|1.34.1|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.12.6.1|间接依赖|maven|
|path-exists|2.1.0|间接依赖|npm|
|async|2.6.1|间接依赖|npm|
|commons-codec:commons-codec|1.13|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.9.8|间接依赖|maven|
|source-map|0.7.3|间接依赖|npm|
|snapdragon|0.8.2|间接依赖|npm|
|has-gulplog|0.1.0|间接依赖|npm|
|commons-codec:commons-codec|1.4|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.63.Final|间接依赖|maven|
|io.grpc:grpc-api|1.42.1|间接依赖|maven|
|net.minidev:accessors-smart|1.2|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.6.6|间接依赖|maven|
|io.grpc:grpc-context|1.42.1|间接依赖|maven|
|io.quarkus:quarkus-resteasy-common-deployment|1.4.1.Final|间接依赖|maven|
|org.springframework:spring-aop|5.3.18|间接依赖|maven|
|org.jboss:jandex|2.1.3.Final|间接依赖|maven|
|to-object-path|0.3.0|间接依赖|npm|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|io.grpc:grpc-protobuf|1.51.0|直接依赖|maven|
|com.google.protobuf:protobuf-java-util|3.14.0|直接依赖|maven|
|org.jboss.resteasy:resteasy-client-api|4.5.3.Final|间接依赖|maven|
|open|6.3.0|直接依赖|npm|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|is-finite|1.0.2|间接依赖|npm|
|org.hibernate.validator:hibernate-validator|6.2.0.Final|间接依赖|maven|
|websocket-driver|0.7.0|间接依赖|npm|
|io.netty:netty-resolver|4.1.30.Final|间接依赖|maven|
|is-extglob|2.1.1|间接依赖|npm|
|angular-utils-pagination|0.11.1|直接依赖|npm|
|io.quarkus:quarkus-resteasy-common-spi|1.4.1.Final|间接依赖|maven|
|once|1.3.3|间接依赖|npm|
|depd|1.1.2|间接依赖|npm|
|com.google.code.gson:gson|2.8.0|间接依赖|maven|
|sequencify|0.0.7|间接依赖|npm|
|com.google.guava:guava|31.1-android|间接依赖|maven|
|exit|0.1.2|间接依赖|npm|
|com.netflix.governator:governator-archaius|1.17.5|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.11.4|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-reactor-netty|2.5.12|间接依赖|maven|
|duplexer2|0.0.2|间接依赖|npm|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|ms|2.0.0|间接依赖|npm|
|strip-json-comments|1.0.4|间接依赖|npm|
|org.springframework.boot:spring-boot-starter-webflux|2.6.6|直接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|直接依赖|maven|
|spdx-correct|3.0.0|间接依赖|npm|
|lodash.clonedeep|4.5.0|间接依赖|npm|
|org.checkerframework:checker-compat-qual|2.5.5|间接依赖|maven|
|is-descriptor|0.1.6|间接依赖|npm|
|org.apache.commons:commons-math3|3.2|间接依赖|maven|
|org.yaml:snakeyaml|1.29|间接依赖|maven|
|io.vertx:vertx-web-common|3.8.5|间接依赖|maven|
|com.netflix.servo:servo-core|0.7.2|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.30.Final|间接依赖|maven|
|org.springframework.boot:spring-boot|2.3.12.RELEASE|间接依赖|maven|
|com.netflix.hystrix:hystrix-metrics-event-stream|1.5.18|间接依赖|maven|
|lodash.defaults|2.4.1|直接依赖|npm|
|find-index|0.1.1|间接依赖|npm|
|org.apache.maven:maven-repository-metadata|3.6.3|间接依赖|maven|
|io.grpc:grpc-netty|1.42.1|间接依赖|maven|
|io.smallrye.config:smallrye-config-common|1.7.0|间接依赖|maven|
|io.netty:netty-handler|4.1.27.Final|间接依赖|maven|
|org.springframework.cloud:spring-cloud-context|3.1.1|间接依赖|maven|
|io.quarkus:quarkus-resteasy-server-common-deployment|1.4.1.Final|直接依赖|maven|
|destroy|1.0.4|间接依赖|npm|
|org.slf4j:slf4j-api|1.7.30|直接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.9.8|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.5.12|间接依赖|maven|
|object.pick|1.3.0|间接依赖|npm|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.10.3|间接依赖|maven|
|io.netty:netty-codec-haproxy|4.1.27.Final|间接依赖|maven|
|org.yaml:snakeyaml|1.17|间接依赖|maven|
|defaults|1.0.3|间接依赖|npm|
|io.envoyproxy.controlplane:api|0.1.32|直接依赖|maven|
|os-homedir|1.0.2|间接依赖|npm|
|org.springframework.boot:spring-boot-starter|2.3.12.RELEASE|间接依赖|maven|
|io.netty:netty-codec-http|4.1.30.Final|间接依赖|maven|
|com.alibaba.csp:sentinel-jax-rs-quarkus-adapter|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|org.springframework:spring-jcl|5.1.18.RELEASE|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.28|直接依赖|maven|
|parse-passwd|1.0.0|间接依赖|npm|
|extglob|2.0.4|间接依赖|npm|
|io.grpc:grpc-core|1.51.0|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.13|间接依赖|maven|
|inflight|1.0.6|间接依赖|npm|
|log4j:log4j|1.2.17|直接依赖|maven|
|xmlpull:xmlpull|1.1.3.1|间接依赖|maven|
|unset-value|1.0.0|间接依赖|npm|
|com.alibaba.csp:sentinel-reactor-adapter|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|static-extend|0.1.2|间接依赖|npm|
|org.apache.maven:maven-resolver-provider|3.6.3|间接依赖|maven|
|to-regex-range|2.1.1|间接依赖|npm|
|org.yaml:snakeyaml|1.32|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.9.8|间接依赖|maven|
|org.jboss.resteasy:resteasy-core|4.5.3.Final|间接依赖|maven|
|amdefine|1.0.1|直接依赖|npm|
|com.google.protobuf:protobuf-java|3.21.9|直接依赖|maven|
|com.google.code.findbugs:jsr305|1.3.9|间接依赖|maven|
|repeat-string|1.6.1|间接依赖|npm|
|org.springframework.boot:spring-boot-autoconfigure|2.0.3.RELEASE|间接依赖|maven|
|org.glassfish:jakarta.el|3.0.3|间接依赖|maven|
|com.alibaba.csp:sentinel-okhttp-adapter|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|org.codehaus.plexus:plexus-utils|3.2.1|间接依赖|maven|
|com.weibo:breeze-core|0.1.3|间接依赖|maven|
|org.apache.maven:maven-plugin-api|3.6.3|间接依赖|maven|
|io.grpc:grpc-api|1.34.1|间接依赖|maven|
|com.squareup:javapoet|1.8.0|间接依赖|maven|
|jakarta.inject:jakarta.inject-api|1.0|间接依赖|maven|
|com.google.guava:guava|19.0|间接依赖|maven|
|org.xmlunit:xmlunit-core|2.8.4|间接依赖|maven|
|io.netty:netty-transport|4.1.45.Final|间接依赖|maven|
|org.springframework:spring-beans|5.2.15.RELEASE|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.5.1|间接依赖|maven|
|setprototypeof|1.1.0|间接依赖|npm|
|org.slf4j:slf4j-api|1.7.6|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-http|1.0.17|间接依赖|maven|
|com.netflix.archaius:archaius-core|0.7.5|间接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.75.Final|间接依赖|maven|
|com.netflix.ribbon:ribbon-loadbalancer|2.3.0|间接依赖|maven|
|microplugin|0.0.3|间接依赖|npm|
|supports-color|2.0.0|间接依赖|npm|
|org.springframework.boot:spring-boot-starter-logging|2.6.6|间接依赖|maven|
|gonzales-pe|3.0.0-28|间接依赖|npm|
|com.fasterxml.jackson.core:jackson-databind|2.13.2.2|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.10|间接依赖|maven|
|io.quarkus:quarkus-jackson|1.4.1.Final|直接依赖|maven|
|org.springframework:spring-context|5.2.15.RELEASE|间接依赖|maven|
|org.springframework:spring-expression|5.2.15.RELEASE|间接依赖|maven|
|object.map|1.0.1|间接依赖|npm|
|org.apache.maven.resolver:maven-resolver-impl|1.4.1|间接依赖|maven|
|set-value|2.0.1|间接依赖|npm|
|javax.servlet:javax.servlet-api|3.1.0|间接依赖|maven|
|lodash.values|2.4.1|直接依赖|npm|
|parseurl|1.3.2|间接依赖|npm|
|com.alibaba.csp:sentinel-transport-spring-mvc|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|angular|1.7.2|间接依赖|npm|
|org.apache.maven:maven-artifact|3.6.3|间接依赖|maven|
|orchestrator|0.3.8|间接依赖|npm|
|nanomatch|1.2.13|间接依赖|npm|
|com.squareup.okhttp3:okhttp|3.6.0|直接依赖|maven|
|org.springframework.cloud:spring-cloud-context|2.2.9.RELEASE|间接依赖|maven|
|concat-with-sourcemaps|1.1.0|间接依赖|npm|
|io.quarkus:quarkus-netty|1.4.1.Final|间接依赖|maven|
|org.antlr:stringtemplate|3.2.1|间接依赖|maven|
|org.springframework.security:spring-security-crypto|5.3.9.RELEASE|间接依赖|maven|
|pify|2.3.0|间接依赖|npm|
|com.sun.jersey:jersey-core|1.19.1|间接依赖|maven|
|com.alibaba.nacos:nacos-api|1.4.2|间接依赖|maven|
|ansi-red|0.1.1|间接依赖|npm|
|util-deprecate|1.0.2|直接依赖|npm|
|gulp-clean|0.4.0|直接依赖|npm|
|strip-indent|1.0.1|间接依赖|npm|
|org.apache.maven.resolver:maven-resolver-spi|1.4.1|间接依赖|maven|
|com.google.code.gson:gson|2.1|间接依赖|maven|
|angular-table-resize|2.0.1|直接依赖|npm|
|io.grpc:grpc-stub|1.17.1|间接依赖|maven|
|dateformat|2.2.0|间接依赖|npm|
|for-in|1.0.2|间接依赖|npm|
|io.netty:netty-codec|4.1.48.Final|间接依赖|maven|
|htmlparser2|3.8.3|间接依赖|npm|
|angular-route|1.7.2|直接依赖|npm|
|commons-io:commons-io|2.7|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.32|间接依赖|maven|
|org.antlr:antlr-runtime|3.4|间接依赖|maven|
|ansi-regex|2.1.1|间接依赖|npm|
|is-extendable|0.1.1|间接依赖|npm|
|org.springframework.boot:spring-boot|2.5.12|间接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|resolve|1.8.1|间接依赖|npm|
|org.springframework.boot:spring-boot-test-autoconfigure|2.5.12|间接依赖|maven|
|global-prefix|1.0.2|间接依赖|npm|
|io.quarkus:quarkus-resteasy-server-common|1.4.1.Final|间接依赖|maven|
|org.springframework.data:spring-data-redis|2.5.10|间接依赖|maven|
|lodash.escape|3.2.0|间接依赖|npm|
|com.netflix.governator:governator-core|1.17.5|间接依赖|maven|
|org.aspectj:aspectjweaver|1.9.2|直接依赖|maven|
|io.netty:netty-codec|4.1.63.Final|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.14|间接依赖|maven|
|for-own|1.0.0|间接依赖|npm|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.60|间接依赖|maven|
|stream-consume|0.1.1|间接依赖|npm|
|oclazyload|1.1.0|直接依赖|npm|
|com.jayway.jsonpath:json-path|2.5.0|间接依赖|maven|
|com.netflix.hystrix:hystrix-serialization|1.5.18|间接依赖|maven|
|org.springframework.cloud:spring-cloud-commons|2.2.9.RELEASE|间接依赖|maven|
|org.springframework:spring-web|5.3.18|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.14.0|间接依赖|maven|
|io.quarkus.http:quarkus-http-core|3.0.6.Final|间接依赖|maven|
|is-absolute|1.0.0|间接依赖|npm|
|com.github.fge:json-patch|1.9|间接依赖|maven|
|lodash._shimkeys|2.4.1|直接依赖|npm|
|findup-sync|2.0.0|间接依赖|npm|
|jakarta.interceptor:jakarta.interceptor-api|1.2.5|直接依赖|maven|
|com.netflix.netflix-commons:netflix-infix|0.3.0|间接依赖|maven|
|unpipe|1.0.0|间接依赖|npm|
|ch.qos.logback:logback-core|1.2.3|直接依赖|maven|
|spdx-license-ids|3.0.0|间接依赖|npm|
|io.netty:netty-resolver-dns|4.1.75.Final|间接依赖|maven|
|csv-parse|2.5.0|间接依赖|npm|
|posix-character-classes|0.1.1|间接依赖|npm|
|com.alibaba.csp:sentinel-spring-webmvc-adapter|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|jline:jline|0.9.94|间接依赖|maven|
|angular-touch|1.7.2|直接依赖|npm|
|pinkie|2.0.4|间接依赖|npm|
|com.netflix.zuul:zuul-core|1.3.1|间接依赖|maven|
|signal-exit|3.0.2|间接依赖|npm|
|net.minidev:json-smart|2.3|间接依赖|maven|
|org.bitbucket.b_c:jose4j|0.8.0|直接依赖|maven|
|angular-ui-notification|0.3.6|直接依赖|npm|
|org.jboss.resteasy:resteasy-client|3.6.3.Final|间接依赖|maven|
|debug|2.6.9|间接依赖|npm|
|livereload-js|2.4.0|间接依赖|npm|
|com.netflix.ribbon:ribbon-httpclient|2.2.4|间接依赖|maven|
|angular-mocks|1.7.2|直接依赖|npm|
|org.springframework.boot:spring-boot-starter-web|2.3.12.RELEASE|间接依赖|maven|
|selectize|0.12.6|直接依赖|npm|
|org.springframework.boot:spring-boot-starter-data-redis-reactive|2.5.12|直接依赖|maven|
|com.alipay.sofa:sofa-rpc-all|5.6.4|直接依赖|maven|
|user-home|1.1.1|间接依赖|npm|
|braces|2.3.2|间接依赖|npm|
|io.grpc:grpc-stub|1.51.0|直接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.3.12.RELEASE|间接依赖|maven|
|domhandler|2.3.0|间接依赖|npm|
|com.google.j2objc:j2objc-annotations|1.1|间接依赖|maven|
|interpret|1.2.0|间接依赖|npm|
|path-type|1.1.0|间接依赖|npm|
|chalk|1.1.3|间接依赖|npm|
|org.javassist:javassist|3.20.0-GA|间接依赖|maven|
|angular-date-time-input|1.2.1|直接依赖|npm|
|org.apiguardian:apiguardian-api|1.1.0|间接依赖|maven|
|archy|1.0.0|间接依赖|npm|
|org.codehaus.mojo:animal-sniffer-annotations|1.21|间接依赖|maven|
|io.perfmark:perfmark-api|0.25.0|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-netflix-ribbon|2.2.10.RELEASE|间接依赖|maven|
|lodash._escapestringchar|2.4.1|直接依赖|npm|
|io.quarkus:quarkus-resteasy-server-common-spi|1.4.1.Final|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.64|间接依赖|maven|
|org.jboss.logmanager:jboss-logmanager-embedded|1.0.4|间接依赖|maven|
|io.quarkus.gizmo:gizmo|1.0.2.Final|间接依赖|maven|
|utils-merge|1.0.1|间接依赖|npm|
|angular-bootstrap|0.12.2|直接依赖|npm|
|io.netty:netty-codec|4.1.30.Final|间接依赖|maven|
|io.quarkus:quarkus-resteasy-common|1.4.1.Final|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.27.Final|间接依赖|maven|
|io.reactivex:rxjava|1.3.8|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.6.6|间接依赖|maven|
|strip-ansi|3.0.1|间接依赖|npm|
|com.fasterxml.jackson.core:jackson-annotations|2.13.2|间接依赖|maven|
|error-ex|1.3.2|间接依赖|npm|
|io.netty:netty-codec-dns|4.1.75.Final|间接依赖|maven|
|shelljs|0.3.0|间接依赖|npm|
|faye-websocket|0.10.0|间接依赖|npm|
|v8flags|2.1.1|间接依赖|npm|
|io.netty:netty-all|4.1.75.Final|直接依赖|maven|
|io.quarkus:quarkus-undertow-spi|1.4.1.Final|间接依赖|maven|
|org.springframework.boot:spring-boot|2.6.6|间接依赖|maven|
|websocket-extensions|0.1.3|间接依赖|npm|
|spdx-expression-parse|3.0.0|间接依赖|npm|
|ansicolors|0.2.1|间接依赖|npm|
|org.jboss.weld.se:weld-se-shaded|3.1.4.Final|直接依赖|maven|
|commons-cli:commons-cli|1.4|间接依赖|maven|
|minimist|0.0.10|间接依赖|npm|
|org.jboss.spec.javax.annotation:jboss-annotations-api_1.3_spec|2.0.1.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|2.3.12.RELEASE|间接依赖|maven|
|lodash.keys|3.1.2|间接依赖|npm|
|io.netty:netty-handler-proxy|4.1.45.Final|间接依赖|maven|
|io.quarkus:quarkus-arc|1.4.1.Final|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.10.3|间接依赖|maven|
|lodash.assign|4.2.0|间接依赖|npm|
|com.thoughtworks.xstream:xstream|1.4.10|间接依赖|maven|
|fined|1.2.0|间接依赖|npm|
|camelcase|2.1.1|间接依赖|npm|
|org.junit.platform:junit-platform-engine|1.7.2|间接依赖|maven|
|com.ecwid.consul:consul-api|1.4.5|直接依赖|maven|
|javax.json:javax.json-api|1.1.2|间接依赖|maven|
|com.github.fge:btf|1.2|间接依赖|maven|
|io.netty:netty-resolver|4.1.63.Final|间接依赖|maven|
|org.apache.dubbo:dubbo|2.7.18|直接依赖|maven|
|io.netty:netty-codec-redis|4.1.75.Final|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.5|直接依赖|maven|
|org.springframework:spring-beans|4.3.16.RELEASE|间接依赖|maven|
|first-chunk-stream|1.0.0|间接依赖|npm|
|http-errors|1.6.3|间接依赖|npm|
|com.alibaba.csp:sentinel-datasource-opensergo|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|org.springframework:spring-oxm|5.3.17|间接依赖|maven|
|angular-loading-bar|0.9.0|直接依赖|npm|
|io.netty:netty-codec-memcache|4.1.75.Final|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.2|间接依赖|maven|
|wrappy|1.0.2|间接依赖|npm|
|esprima|3.0.0|间接依赖|npm|
|angularjs-bootstrap-datetimepicker|1.1.4|直接依赖|npm|
|org.springframework.boot:spring-boot-starter-aop|2.5.12|直接依赖|maven|
|com.google.code.findbugs:annotations|2.0.0|间接依赖|maven|
|io.lettuce:lettuce-core|6.1.8.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-reactor-netty|2.6.6|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.9.8|间接依赖|maven|
|lodash.templatesettings|3.1.1|间接依赖|npm|
|stax:stax-api|1.0.1|间接依赖|maven|
|expand-tilde|2.0.2|间接依赖|npm|
|org.reactivestreams:reactive-streams|1.0.2|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.45.Final|间接依赖|maven|
|is-builtin-module|1.0.0|间接依赖|npm|
|io.reactivex:rxnetty-servo|0.4.9|间接依赖|maven|
|repeat-element|1.1.2|间接依赖|npm|
|org.springframework.boot:spring-boot-autoconfigure|2.5.12|间接依赖|maven|
|com.alibaba.csp:sentinel-sofa-rpc-adapter|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|lodash._isiterateecall|3.0.9|间接依赖|npm|
|replace-ext|0.0.1|间接依赖|npm|
|com.alibaba.csp:sentinel-spring-webflux-adapter|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|commons-jxpath:commons-jxpath|1.3|间接依赖|maven|
|javax.ws.rs:jsr311-api|1.1.1|间接依赖|maven|
|org.apache.maven.wagon:wagon-provider-api|3.3.4|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.13.3|间接依赖|maven|
|lodash|4.17.15|间接依赖|npm|
|org.springframework:spring-jcl|5.3.15|间接依赖|maven|
|com.netflix.ribbon:ribbon-eureka|2.2.4|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.2|间接依赖|maven|
|io.netty:netty-handler|4.1.63.Final|间接依赖|maven|
|io.smallrye.config:smallrye-config|1.7.0|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.1|间接依赖|maven|
|gulp-load-plugins|1.6.0|直接依赖|npm|
|vinyl-fs|0.3.14|间接依赖|npm|
|com.google.api.grpc:proto-google-common-protos|1.17.0|间接依赖|maven|
|org.apache.maven.resolver:maven-resolver-connector-basic|1.4.1|间接依赖|maven|
|org.apache.maven:maven-settings-builder|3.6.3|间接依赖|maven|
|bootstrap-switch|3.3.4|直接依赖|npm|
|lodash.isarguments|3.1.0|间接依赖|npm|
|io.netty:netty-codec-socks|4.1.79.Final|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.45.Final|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-params|5.7.2|间接依赖|maven|
|read-pkg|1.1.0|间接依赖|npm|
|io.quarkus:quarkus-development-mode-spi|1.4.1.Final|间接依赖|maven|
|io.netty:netty-codec-http|4.1.79.Final|间接依赖|maven|
|com.alibaba.csp:sentinel-datasource-etcd|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|com.google.code.gson:gson|2.7|间接依赖|maven|
|io.etcd:jetcd-common|0.3.0|间接依赖|maven|
|com.alipay.sofa.lookout:lookout-api|1.4.1|间接依赖|maven|
|org.codehaus.jettison:jettison|1.3.7|间接依赖|maven|
|com.alibaba.csp:sentinel-transport-common|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.18|间接依赖|maven|
|mime|1.4.1|间接依赖|npm|
|com.netflix.netflix-commons:netflix-commons-util|0.3.0|间接依赖|maven|
|com.google.inject.extensions:guice-servlet|4.0|间接依赖|maven|
|io.netty:netty-codec-http|4.1.75.Final|间接依赖|maven|
|path-root-regex|0.1.2|间接依赖|npm|
|string_decoder|0.10.31|间接依赖|npm|
|jakarta.enterprise:jakarta.enterprise.cdi-api|2.0.2|直接依赖|maven|
|com.ctrip.framework.apollo:apollo-client|1.5.0|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.12.6|间接依赖|maven|
|com.netflix.ribbon:ribbon-transport|2.3.0|间接依赖|maven|
|io.netty:netty-transport|4.1.75.Final|间接依赖|maven|
|com.alibaba.csp:sentinel-parameter-flow-control|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|com.squareup.okio:okio|1.11.0|间接依赖|maven|
|xpp3:xpp3_min|1.1.4c|间接依赖|maven|
|repeating|2.0.1|间接依赖|npm|
|lodash._reevaluate|3.0.0|间接依赖|npm|
|lodash.merge|4.6.2|间接依赖|npm|
|jquery|3.4.1|间接依赖|npm|
|org.apache.yetus:audience-annotations|0.5.0|间接依赖|maven|
|io.netty:netty-buffer|4.1.50.Final|间接依赖|maven|
|org.apache.rocketmq:rocketmq-remoting|4.2.0|间接依赖|maven|
|org.jboss.resteasy:resteasy-spring|4.5.3.Final|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.14.0|间接依赖|maven|
|natives|1.1.6|间接依赖|npm|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.10.3|间接依赖|maven|
|io.lettuce:lettuce-core|5.3.1.RELEASE|直接依赖|maven|
|com.github.fge:jackson-coreutils|1.6|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-api|5.7.2|间接依赖|maven|
|lodash.restparam|3.6.1|间接依赖|npm|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.10.3|间接依赖|maven|
|time-stamp|1.1.0|间接依赖|npm|
|connect-livereload|0.6.1|间接依赖|npm|
|com.alibaba.csp:sentinel-jax-rs-adapter|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|com.alibaba.csp:sentinel-web-servlet|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|lodash.isarray|3.0.4|间接依赖|npm|
|fragment-cache|0.2.1|间接依赖|npm|
|com.alibaba.csp:sentinel-api-gateway-adapter-common|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|gulp-util|3.0.8|间接依赖|npm|
|org.springframework.boot:spring-boot-starter-actuator|2.3.12.RELEASE|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.3|间接依赖|maven|
|org.springframework.data:spring-data-commons|2.5.10|间接依赖|maven|
|org.springframework.cloud:spring-cloud-netflix-hystrix|2.2.10.RELEASE|间接依赖|maven|
|org.sonatype.plexus:plexus-sec-dispatcher|1.4|间接依赖|maven|
|io.netty:netty-transport|4.1.63.Final|间接依赖|maven|
|org.springframework:spring-core|5.3.18|间接依赖|maven|
|get-stdin|4.0.1|间接依赖|npm|
|gulp-csscomb|3.0.8|直接依赖|npm|
|glob|4.5.3|间接依赖|npm|
|map-stream|0.1.0|间接依赖|npm|
|org.eclipse.sisu:org.eclipse.sisu.plexus|0.3.4|间接依赖|maven|
|com.google.guava:guava|27.0.1-jre|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|io.netty:netty-transport|4.1.48.Final|间接依赖|maven|
|clone-buffer|1.0.0|直接依赖|npm|
|serve-index|1.9.1|间接依赖|npm|
|org.springframework.boot:spring-boot-test|2.5.12|间接依赖|maven|
|tempfile|0.1.3|间接依赖|npm|
|cloneable-readable|1.1.2|直接依赖|npm|
|loud-rejection|1.6.0|间接依赖|npm|
|org.springframework.boot:spring-boot-starter-logging|2.3.12.RELEASE|间接依赖|maven|
|org.jboss.metadata:jboss-metadata-common|11.0.0.Final|间接依赖|maven|
|angular-clipboard|1.6.2|直接依赖|npm|
|make-iterator|1.0.1|间接依赖|npm|
|use|3.1.1|间接依赖|npm|
|io.netty:netty-all|4.1.31.Final|直接依赖|maven|
|pinkie-promise|2.0.1|间接依赖|npm|
|io.netty:netty-codec-haproxy|4.1.75.Final|间接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.75.Final|间接依赖|maven|
|minimatch|2.0.10|间接依赖|npm|
|org.springframework.boot:spring-boot-actuator|2.3.12.RELEASE|间接依赖|maven|
|com.alibaba.csp:sentinel-security-core|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|
|org.springframework.data:spring-data-keyvalue|2.5.10|间接依赖|maven|
|org.apache.commons:commons-lang3|3.1|间接依赖|maven|
|com.googlecode.concurrentlinkedhashmap:concurrentlinkedhashmap-lru|1.4.2|直接依赖|maven|
|com.alibaba.csp:sentinel-core|2.0.0-alpha2-SNAPSHOT|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)