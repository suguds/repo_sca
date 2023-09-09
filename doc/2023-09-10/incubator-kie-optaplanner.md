# apache/incubator-kie-optaplanner安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700570169138266112.svg)](https://www.murphysec.com/console/report/1700570169087934464/1700570169138266112)

仓库描述：AI constraint solver in Java to optimize the vehicle routing problem, employee rostering, task assignment, maintenance scheduling, conference scheduling and other planning problems.

仓库地址：[https://github.com/apache/incubator-kie-optaplanner](https://github.com/apache/incubator-kie-optaplanner)

| star：3150 | watch：166 | fork：940 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-09 01:06:15 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-10 02:11:16 | 组件总数：351 | 漏洞总数：94 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|FasterXML Jackson-databind 反序列化漏洞(dbcp2 gadget绕过)|反序列化|[MPS-2018-0362](https://www.oscs1024.com/hd/MPS-2018-0362)|CVE-2017-17485|严重|
|FasterXML jackson-databind 反序列化漏洞(Hibernate/iBatis gadget绕过)||[MPS-2018-0934](https://www.oscs1024.com/hd/MPS-2018-0934)|CVE-2018-5968|高危|
|FasterXML Jackson-databind 反序列化漏洞(JdbcRowSetImpl gadget绕过)|反序列化|[MPS-2018-1438](https://www.oscs1024.com/hd/MPS-2018-1438)|CVE-2017-15095|严重|
|FasterXML Jackson-databind反序列化漏洞|反序列化|[MPS-2018-1439](https://www.oscs1024.com/hd/MPS-2018-1439)|CVE-2017-7525|严重|
|FasterXML jackson-databind 反序列化漏洞(c3p0 gadget绕过)||[MPS-2018-2477](https://www.oscs1024.com/hd/MPS-2018-2477)|CVE-2018-7489|严重|
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
|FasterXML Jackson-databind反序列化漏洞（Jodd-db gadget绕过）|反序列化|[MPS-2019-2619](https://www.oscs1024.com/hd/MPS-2019-2619)|CVE-2018-12022|高危|
|FasterXML Jackson-databind反序列化漏洞(Oracle JDBC driver gadget绕过)|反序列化|[MPS-2019-2620](https://www.oscs1024.com/hd/MPS-2019-2620)|CVE-2018-12023|高危|
|FasterXML jackson-databind 反序列化漏洞(mysql gadget绕过)|反序列化|[MPS-2019-5442](https://www.oscs1024.com/hd/MPS-2019-5442)|CVE-2019-12086|高危|
|FasterXML jackson-databind 反序列化漏洞(jdom gadget绕过)|反序列化|[MPS-2019-6867](https://www.oscs1024.com/hd/MPS-2019-6867)|CVE-2019-12814|中危|
|FasterXML jackson-databind 反序列化漏洞(logback-classic gadget绕过)|反序列化|[MPS-2019-7047](https://www.oscs1024.com/hd/MPS-2019-7047)|CVE-2019-12384|中危|
|FasterXML jackson-databind 反序列化漏洞(iBatis gadget绕过)|反序列化|[MPS-2019-7711](https://www.oscs1024.com/hd/MPS-2019-7711)|CVE-2018-11307|严重|
|FasterXML jackson-databind 信息泄露漏洞(logback gadget绕过)|反序列化|[MPS-2019-8770](https://www.oscs1024.com/hd/MPS-2019-8770)|CVE-2019-14439|高危|
|FasterXML jackson-databind反序列化漏洞(net.sf.ehcache gadget绕过)|反序列化|[MPS-2020-0063](https://www.oscs1024.com/hd/MPS-2020-0063)|CVE-2019-20330|严重|
|FasterXML jackson-databind反序列化漏洞(Anteros-DBCP gadget绕过)|反序列化|[MPS-2020-11987](https://www.oscs1024.com/hd/MPS-2020-11987)|CVE-2020-24616|高危|
|FasterXML jackson-databind 反序列化漏洞(pastdev gadget绕过)|反序列化|[MPS-2020-13151](https://www.oscs1024.com/hd/MPS-2020-13151)|CVE-2020-24750|高危|
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
|FasterXML jackson-databind 反序列化漏洞(spring-aop gadget绕过)|反序列化|[MPS-2020-5138](https://www.oscs1024.com/hd/MPS-2020-5138)|CVE-2020-11619|高危|
|FasterXML jackson-databind 反序列化漏洞(commons-jelly gadget绕过)|反序列化|[MPS-2020-5139](https://www.oscs1024.com/hd/MPS-2020-5139)|CVE-2020-11620|高危|
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
|FasterXML jackson-databind 反序列化漏洞(javax.swing gadget绕过)|反序列化|[MPS-2021-1625](https://www.oscs1024.com/hd/MPS-2021-1625)|CVE-2021-20190|高危|
|com.fasterxml.jackson.core:jackson-core 存在资源管理错误漏洞|资源管理错误|[MPS-2022-11944](https://www.oscs1024.com/hd/MPS-2022-11944)||中危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|com.fasterxml.jackson.core:jackson-core  BigDecimal拒绝服务漏洞|资源管理错误|[MPS-2022-12166](https://www.oscs1024.com/hd/MPS-2022-12166)||中危|
|com.fasterxml.jackson.core:jackson-databind 存在反序列化漏洞|反序列化|[MPS-2022-12433](https://www.oscs1024.com/hd/MPS-2022-12433)||高危|
|Netty <4.1.86.Final 存在拒绝服务漏洞|未经控制的递归|[MPS-2022-58518](https://www.oscs1024.com/hd/MPS-2022-58518)|CVE-2022-41881|中危|
|Netty <4.1.86.Final 存在 CRLF 注入漏洞||[MPS-2022-58552](https://www.oscs1024.com/hd/MPS-2022-58552)|CVE-2022-41915|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
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
|Resteasy 安全漏洞|输入验证不恰当|[MPS-2023-2844](https://www.oscs1024.com/hd/MPS-2023-2844)|CVE-2023-0482|中危|
|Eclipse Vertx-web 路径遍历漏洞|路径遍历|[MPS-2023-3321](https://www.oscs1024.com/hd/MPS-2023-3321)|CVE-2023-24815|中危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.yaml:snakeyaml|1.33|2.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.graalvm.sdk:graal-sdk|22.3.0|22.3.3|直接依赖|建议修复|C:0|H:1|M:4|L:8|
|org.xerial.snappy:snappy-java|1.1.8.4|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|com.squareup.okio:okio|1.15.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.3.2|2.14.0-rc1|间接依赖|建议修复|C:25|H:38|M:5|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.14.2||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|io.netty:netty-handler|4.1.86.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|io.netty:netty-handler|4.1.82.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|io.netty:netty-codec-haproxy|4.1.86.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.jboss.resteasy:resteasy-core|4.7.7.Final|4.7.8.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.fasterxml.jackson.core:jackson-core|2.3.2|2.8.6|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|io.vertx:vertx-web|4.3.7|4.3.8|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-http|4.1.82.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-http|4.1.86.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|285|Low|
|EPL-2.0|21|Low|
|BSD-3-Clause|12|Low|
|自定义许可证|23|Low|
|EPL-1.0|7|Low|
|LGPL-2.1|3|Medium|
|BSD-2-Clause|2|Low|
|MIT-0|1|Low|
|UPL-1.0|1|Low|
|MIT|3|Low|
|LGPL-2.1-or-later|4|Low|
|CDDL-1.1|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|jakarta.inject:jakarta.inject-api|1.0|直接依赖|maven|
|org.junit.jupiter:junit-jupiter-params|5.9.2|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.4|间接依赖|maven|
|org.jboss.logging:jboss-logging-annotations|2.2.1.Final|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.18|间接依赖|maven|
|org.ow2.asm:asm|9.4|直接依赖|maven|
|io.fabric8:openshift-model-installer|6.3.1|间接依赖|maven|
|io.quarkus:quarkus-vertx-http|2.16.6.Final|间接依赖|maven|
|org.apache.commons:commons-collections4|4.4|间接依赖|maven|
|io.fabric8:openshift-model-clusterautoscaling|6.3.1|间接依赖|maven|
|io.smallrye:smallrye-context-propagation-storage|1.2.2|间接依赖|maven|
|io.smallrye.common:smallrye-common-annotation|1.13.0|间接依赖|maven|
|org.antlr:antlr4|4.11.1|间接依赖|maven|
|io.quarkus:quarkus-netty|2.16.10.Final|间接依赖|maven|
|io.smallrye:smallrye-context-propagation|1.2.2|间接依赖|maven|
|io.smallrye.reactive:smallrye-mutiny-vertx-runtime|2.30.1|间接依赖|maven|
|io.smallrye.reactive:mutiny-smallrye-context-propagation|1.9.0|间接依赖|maven|
|org.springframework:spring-context|5.3.27|间接依赖|maven|
|io.micrometer:micrometer-core|1.10.2|直接依赖|maven|
|io.quarkus:quarkus-jsonb-deployment|2.16.10.Final|直接依赖|maven|
|io.quarkus:quarkus-resteasy-jackson|2.16.10.Final|直接依赖|maven|
|dk.brics.automaton:automaton|1.11-8|间接依赖|maven|
|io.fabric8:zjsonpatch|0.3.0|间接依赖|maven|
|io.fabric8:openshift-model-machine|6.3.1|间接依赖|maven|
|org.optaplanner:optaplanner-spring-boot-autoconfigure|8.45.0-SNAPSHOT|直接依赖|maven|
|org.junit.platform:junit-platform-engine|1.9.2|间接依赖|maven|
|javax.persistence:javax.persistence-api|2.2|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.82.Final|间接依赖|maven|
|io.quarkiverse.operatorsdk:quarkus-operator-sdk|5.1.4|直接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.86.Final|间接依赖|maven|
|io.netty:netty-transport|4.1.82.Final|间接依赖|maven|
|io.fabric8:kubernetes-model-common|6.3.1|间接依赖|maven|
|org.springframework:spring-jcl|5.3.27|间接依赖|maven|
|io.quarkus:quarkus-vertx-http-dev-console-runtime-spi|2.16.10.Final|间接依赖|maven|
|io.quarkus:quarkus-ide-launcher|2.16.6.Final|间接依赖|maven|
|org.eclipse.microprofile.health:microprofile-health-api|3.1|间接依赖|maven|
|io.fabric8:kubernetes-client|6.2.0|间接依赖|maven|
|io.netty:netty-codec-haproxy|4.1.94.Final|间接依赖|maven|
|org.optaplanner:optaplanner-constraint-streams-drools|8.45.0-SNAPSHOT|直接依赖|maven|
|io.quarkus:quarkus-awt|2.16.10.Final|直接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|2.3.3-b02|直接依赖|maven|
|org.wildfly.common:wildfly-common|1.5.4.Final-format-001|间接依赖|maven|
|io.netty:netty-common|4.1.86.Final|间接依赖|maven|
|io.fabric8:openshift-model-operatorhub|6.3.1|间接依赖|maven|
|io.quarkus:quarkus-vertx-http-dev-console-runtime-spi|2.16.6.Final|间接依赖|maven|
|jakarta.enterprise:jakarta.enterprise.cdi-api|2.0.2|间接依赖|maven|
|io.smallrye.common:smallrye-common-io|1.13.2|间接依赖|maven|
|org.jetbrains:annotations|24.0.1|间接依赖|maven|
|org.jboss.resteasy:resteasy-core-spi|4.7.7.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.3.2|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.3.0|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.21|间接依赖|maven|
|org.springframework:spring-aop|5.3.27|间接依赖|maven|
|io.smallrye.config:smallrye-config-core|2.13.3|间接依赖|maven|
|org.eclipse.microprofile.fault-tolerance:microprofile-fault-tolerance-api|3.0|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.14.2|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|jakarta.json.bind:jakarta.json.bind-api|1.0.2|直接依赖|maven|
|org.springframework:spring-expression|5.3.27|间接依赖|maven|
|io.smallrye:smallrye-fault-tolerance-api|5.6.0|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-api|5.9.2|直接依赖|maven|
|io.netty:netty-buffer|4.1.86.Final|间接依赖|maven|
|io.fabric8:openshift-model|6.3.1|间接依赖|maven|
|io.netty:netty-codec-http|4.1.86.Final|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.2|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|org.openrewrite:rewrite-core|7.40.3|直接依赖|maven|
|org.apache.poi:poi-ooxml-lite|5.2.3|间接依赖|maven|
|org.jboss.resteasy:resteasy-json-binding-provider|4.7.7.Final|间接依赖|maven|
|io.quarkus:quarkus-jackson|2.16.6.Final|间接依赖|maven|
|org.optaplanner:optaplanner-quarkus-jsonb|8.45.0-SNAPSHOT|直接依赖|maven|
|io.smallrye.reactive:smallrye-mutiny-vertx-bridge-common|2.30.1|间接依赖|maven|
|commons-io:commons-io|2.11.0|间接依赖|maven|
|org.apache.commons:commons-compress|1.21|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|io.smallrye.common:smallrye-common-constraint|1.13.2|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.4|间接依赖|maven|
|io.smallrye.common:smallrye-common-expression|1.13.2|间接依赖|maven|
|io.javaoperatorsdk:operator-framework-core|4.2.8|间接依赖|maven|
|io.vertx:vertx-web|4.3.7|间接依赖|maven|
|io.quarkus:quarkus-devtools-utilities|2.16.10.Final|间接依赖|maven|
|io.quarkus:quarkus-kubernetes-client-internal|2.16.6.Final|间接依赖|maven|
|com.ibm.icu:icu4j|71.1|间接依赖|maven|
|org.graalvm.sdk:graal-sdk|22.3.0|直接依赖|maven|
|xmlpull:xmlpull|1.1.3.1|间接依赖|maven|
|io.fabric8:kubernetes-model-rbac|6.3.1|间接依赖|maven|
|jakarta.persistence:jakarta.persistence-api|2.2.3|直接依赖|maven|
|io.netty:netty-codec-http2|4.1.86.Final|间接依赖|maven|
|org.eclipse.microprofile.context-propagation:microprofile-context-propagation-api|1.2|间接依赖|maven|
|io.fabric8:openshift-model-monitoring|6.3.1|间接依赖|maven|
|org.optaplanner:optaplanner-quarkus-deployment|8.45.0-SNAPSHOT|直接依赖|maven|
|io.fabric8:openshift-model-machineconfig|6.3.1|间接依赖|maven|
|io.quarkus:quarkus-development-mode-spi|2.16.10.Final|间接依赖|maven|
|io.smallrye:smallrye-health-provided-checks|3.3.1|间接依赖|maven|
|io.smallrye.reactive:vertx-mutiny-generator|2.30.1|间接依赖|maven|
|io.javaoperatorsdk:micrometer-support|4.2.8|间接依赖|maven|
|io.quarkus:quarkus-credentials|2.16.10.Final|间接依赖|maven|
|io.smallrye:smallrye-health-api|3.3.1|间接依赖|maven|
|io.quarkus.arc:arc|2.16.10.Final|间接依赖|maven|
|com.zaxxer:SparseBitSet|1.2|间接依赖|maven|
|org.openrewrite:rewrite-java-11|7.40.3|直接依赖|maven|
|org.ow2.asm:asm-tree|9.5|间接依赖|maven|
|org.antlr:antlr4-runtime|4.11.1|间接依赖|maven|
|jakarta.el:jakarta.el-api|3.0.3|间接依赖|maven|
|io.vavr:vavr-match|0.10.2|间接依赖|maven|
|io.github.classgraph:classgraph|4.8.157|间接依赖|maven|
|org.apache.poi:poi-ooxml|5.2.3|直接依赖|maven|
|org.apache.commons:commons-compress|1.22|间接依赖|maven|
|org.optaplanner:optaplanner-core-impl|8.45.0-SNAPSHOT|直接依赖|maven|
|io.micrometer:micrometer-core|1.10.4|间接依赖|maven|
|com.github.virtuald:curvesapi|1.07|间接依赖|maven|
|io.smallrye.reactive:smallrye-mutiny-vertx-web|2.30.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.14.2|直接依赖|maven|
|io.fabric8:openshift-model-operator|6.3.1|间接依赖|maven|
|io.quarkus:quarkus-vertx-latebound-mdc-provider|2.16.10.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.12|直接依赖|maven|
|org.jboss.logging:jboss-logging|3.5.0.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.14.2|直接依赖|maven|
|io.smallrye:jandex|3.0.5|间接依赖|maven|
|org.apiguardian:apiguardian-api|1.1.2|间接依赖|maven|
|com.squareup.okio:okio|1.15.0|间接依赖|maven|
|io.netty:netty-codec-http|4.1.82.Final|间接依赖|maven|
|io.quarkus:quarkus-development-mode-spi|2.16.6.Final|间接依赖|maven|
|io.fabric8:openshift-model-hive|6.3.1|间接依赖|maven|
|org.glassfish.jaxb:txw2|2.3.3-b02|间接依赖|maven|
|org.jboss.logmanager:jboss-logmanager-embedded|1.0.11|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|间接依赖|maven|
|io.netty:netty-resolver|4.1.86.Final|间接依赖|maven|
|org.optaplanner:optaplanner-quarkus-benchmark|8.45.0-SNAPSHOT|直接依赖|maven|
|org.eclipse:yasson|1.0.11|间接依赖|maven|
|io.github.crac:org-crac|0.1.3|间接依赖|maven|
|io.quarkus:quarkus-jackson|2.16.10.Final|直接依赖|maven|
|com.sun.activation:jakarta.activation|1.2.1|间接依赖|maven|
|io.netty:netty-handler|4.1.86.Final|间接依赖|maven|
|io.github.resilience4j:resilience4j-core|1.7.0|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-smile|2.14.2|间接依赖|maven|
|org.ow2.asm:asm-commons|9.4|间接依赖|maven|
|io.smallrye.reactive:smallrye-mutiny-vertx-web-common|2.30.1|间接依赖|maven|
|org.optaplanner:optaplanner-quarkus|8.45.0-SNAPSHOT|直接依赖|maven|
|org.eclipse.microprofile.config:microprofile-config-api|2.0.1|间接依赖|maven|
|org.opentest4j:opentest4j|1.2.0|间接依赖|maven|
|org.jboss.resteasy:resteasy-json-p-provider|4.7.7.Final|间接依赖|maven|
|io.quarkus:quarkus-vertx-http-dev-console-spi|2.16.10.Final|间接依赖|maven|
|io.quarkus:quarkus-jsonb|2.16.10.Final|直接依赖|maven|
|io.quarkus:quarkus-kubernetes|2.16.6.Final|间接依赖|maven|
|io.quarkus:quarkus-security-runtime-spi|2.16.6.Final|间接依赖|maven|
|io.smallrye.config:smallrye-config-source-yaml|2.13.3|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.14.2|间接依赖|maven|
|io.smallrye.common:smallrye-common-annotation|1.13.2|间接依赖|maven|
|org.ow2.asm:asm-analysis|9.4|间接依赖|maven|
|net.java.dev.jna:jna-platform|5.13.0|间接依赖|maven|
|org.apache.poi:poi|5.2.3|直接依赖|maven|
|io.netty:netty-codec-haproxy|4.1.86.Final|间接依赖|maven|
|org.aesh:readline|2.2|间接依赖|maven|
|org.optaplanner:optaplanner-benchmark|8.45.0-SNAPSHOT|直接依赖|maven|
|io.netty:netty-codec-http2|4.1.82.Final|间接依赖|maven|
|io.fabric8:kubernetes-model-core|6.3.1|间接依赖|maven|
|io.quarkus:quarkus-container-image|2.16.6.Final|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|io.fabric8:openshift-model-config|6.3.1|间接依赖|maven|
|io.quarkus:quarkus-vertx|2.16.10.Final|间接依赖|maven|
|io.smallrye:smallrye-context-propagation-api|1.2.2|间接依赖|maven|
|org.apache.commons:commons-compress|1.23.0|间接依赖|maven|
|io.netty:netty-common|4.1.82.Final|间接依赖|maven|
|org.junit.platform:junit-platform-launcher|1.9.2|间接依赖|maven|
|io.quarkus:quarkus-smallrye-context-propagation|2.16.6.Final|间接依赖|maven|
|io.quarkus.security:quarkus-security|1.1.4.Final|间接依赖|maven|
|io.micrometer:micrometer-observation|1.10.2|间接依赖|maven|
|io.quarkus:quarkus-arc|2.16.10.Final|直接依赖|maven|
|org.aesh:aesh|2.7|间接依赖|maven|
|io.quarkus:quarkus-netty|2.16.6.Final|间接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|io.quarkus:quarkus-bootstrap-runner|2.16.6.Final|间接依赖|maven|
|io.netty:netty-buffer|4.1.82.Final|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.82.Final|间接依赖|maven|
|io.quarkus:quarkus-core|2.16.10.Final|直接依赖|maven|
|org.eclipse.sisu:org.eclipse.sisu.inject|0.3.5|间接依赖|maven|
|org.optaplanner:optaplanner-constraint-drl|8.45.0-SNAPSHOT|直接依赖|maven|
|io.vertx:vertx-core|4.3.7|间接依赖|maven|
|org.optaplanner:optaplanner-persistence-jaxb|8.45.0-SNAPSHOT|直接依赖|maven|
|org.junit.jupiter:junit-jupiter|5.9.2|间接依赖|maven|
|io.quarkus:quarkus-ide-launcher|2.16.10.Final|间接依赖|maven|
|jakarta.transaction:jakarta.transaction-api|1.3.3|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.14.2|直接依赖|maven|
|io.fabric8:openshift-model-console|6.3.1|间接依赖|maven|
|io.quarkus:quarkus-bootstrap-runner|2.16.10.Final|间接依赖|maven|
|org.ow2.asm:asm-analysis|9.5|间接依赖|maven|
|org.jboss.threads:jboss-threads|3.4.3.Final|间接依赖|maven|
|org.fusesource.jansi:jansi|1.18|间接依赖|maven|
|io.micrometer:micrometer-commons|1.10.4|间接依赖|maven|
|io.smallrye.reactive:smallrye-mutiny-vertx-auth-common|2.30.1|间接依赖|maven|
|io.smallrye.common:smallrye-common-vertx-context|1.13.2|间接依赖|maven|
|antlr:antlr|2.7.7|间接依赖|maven|
|com.sun.istack:istack-commons-runtime|3.0.10|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.9.3|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.3.2|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.86.Final|间接依赖|maven|
|io.quarkus:quarkus-resteasy|2.16.10.Final|直接依赖|maven|
|org.hibernate:hibernate-core|5.6.15.Final|直接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.3|直接依赖|maven|
|io.smallrye.reactive:smallrye-mutiny-vertx-uri-template|2.30.1|间接依赖|maven|
|io.netty:netty-transport|4.1.86.Final|间接依赖|maven|
|io.micrometer:micrometer-commons|1.10.2|间接依赖|maven|
|io.vavr:vavr|0.10.2|间接依赖|maven|
|io.fabric8:openshift-model-storageversionmigrator|6.3.1|间接依赖|maven|
|org.openrewrite:rewrite-properties|7.40.3|直接依赖|maven|
|io.vertx:vertx-bridge-common|4.3.7|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.14.0|间接依赖|maven|
|org.openrewrite:rewrite-java|7.40.3|直接依赖|maven|
|io.quarkus:quarkus-fs-util|0.0.9|间接依赖|maven|
|org.openrewrite.tools:java-object-diff|1.0.1|间接依赖|maven|
|org.optaplanner:optaplanner-quarkus-jackson|8.45.0-SNAPSHOT|直接依赖|maven|
|io.github.resilience4j:resilience4j-retry|1.7.0|间接依赖|maven|
|io.smallrye.config:smallrye-config|2.13.3|间接依赖|maven|
|io.quarkus:quarkus-awt-deployment|2.16.10.Final|直接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.20.0|间接依赖|maven|
|org.optaplanner:optaplanner-persistence-common|8.45.0-SNAPSHOT|直接依赖|maven|
|io.fabric8:kubernetes-model-apps|6.3.1|间接依赖|maven|
|io.quarkus:quarkus-vertx-http|2.16.10.Final|间接依赖|maven|
|io.micrometer:micrometer-core|1.9.10|间接依赖|maven|
|org.optaplanner:optaplanner-persistence-jackson|8.45.0-SNAPSHOT|直接依赖|maven|
|io.quarkus:quarkus-jackson-deployment|2.16.10.Final|直接依赖|maven|
|io.smallrye:smallrye-health|3.3.1|间接依赖|maven|
|org.apache.xmlbeans:xmlbeans|5.1.1|间接依赖|maven|
|io.quarkus:quarkus-vertx|2.16.6.Final|间接依赖|maven|
|io.smallrye.config:smallrye-config-common|2.13.3|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.14.2|间接依赖|maven|
|org.codehaus.woodstox:stax2-api|4.2.1|间接依赖|maven|
|io.quarkus:quarkus-security-runtime-spi|2.16.10.Final|间接依赖|maven|
|org.optaplanner:optaplanner-constraint-streams-common|8.45.0-SNAPSHOT|直接依赖|maven|
|org.jboss.resteasy:resteasy-core|4.7.7.Final|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.82.Final|间接依赖|maven|
|org.jboss.spec.javax.transaction:jboss-transaction-api_1.2_spec|1.1.1.Final|间接依赖|maven|
|io.quarkus:quarkus-arc|2.16.6.Final|间接依赖|maven|
|io.netty:netty-handler|4.1.82.Final|间接依赖|maven|
|io.quarkus.gizmo:gizmo|1.6.0.Final|直接依赖|maven|
|io.fabric8:kubernetes-httpclient-okhttp|6.2.0|间接依赖|maven|
|org.jboss.spec.javax.xml.bind:jboss-jaxb-api_2.3_spec|2.0.0.Final|间接依赖|maven|
|io.quarkus:quarkus-resteasy-jsonb|2.16.10.Final|直接依赖|maven|
|org.ow2.asm:asm-util|9.5|间接依赖|maven|
|io.quarkus:quarkus-jsonp|2.16.10.Final|间接依赖|maven|
|io.quarkus:quarkus-mutiny|2.16.10.Final|间接依赖|maven|
|io.fabric8:kubernetes-model-admissionregistration|6.3.1|间接依赖|maven|
|org.optaplanner:optaplanner-persistence-jsonb|8.45.0-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-xml|2.14.2|间接依赖|maven|
|org.ow2.asm:asm|9.5|间接依赖|maven|
|io.github.x-stream:mxparser|1.2.2|间接依赖|maven|
|io.quarkus:quarkus-class-change-agent|2.16.10.Final|间接依赖|maven|
|org.optaplanner:optaplanner-persistence-xstream|8.45.0-SNAPSHOT|直接依赖|maven|
|io.quarkus:quarkus-jsonb-spi|2.16.10.Final|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.20.0|直接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|6.5.0|间接依赖|maven|
|io.quarkus:quarkus-core|2.16.6.Final|间接依赖|maven|
|com.aayushatharva.brotli4j:brotli4j|1.7.1|间接依赖|maven|
|org.ow2.asm:asm-util|9.4|间接依赖|maven|
|org.jboss.slf4j:slf4j-jboss-logmanager|1.2.0.Final|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.82.Final|间接依赖|maven|
|org.abego.treelayout:org.abego.treelayout.core|1.0.3|间接依赖|maven|
|com.squareup.okhttp3:logging-interceptor|3.12.12|间接依赖|maven|
|org.yaml:snakeyaml|1.33|间接依赖|maven|
|io.netty:netty-codec|4.1.94.Final|间接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|org.springframework:spring-core|5.3.27|间接依赖|maven|
|io.quarkus:quarkus-smallrye-health|2.16.6.Final|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.86.Final|间接依赖|maven|
|org.optaplanner:optaplanner-examples|8.45.0-SNAPSHOT|直接依赖|maven|
|io.netty:netty-codec-dns|4.1.86.Final|间接依赖|maven|
|org.jboss.spec.javax.ws.rs:jboss-jaxrs-api_2.1_spec|2.0.1.Final|间接依赖|maven|
|com.thoughtworks.xstream:xstream|1.4.20|直接依赖|maven|
|ch.qos.logback:logback-classic|1.2.9|直接依赖|maven|
|io.fabric8:openshift-model-whereabouts|6.3.1|间接依赖|maven|
|io.smallrye:smallrye-fault-tolerance-vertx|5.6.0|间接依赖|maven|
|jakarta.ejb:jakarta.ejb-api|3.2.6|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.10.0|间接依赖|maven|
|io.quarkiverse.operatorsdk:quarkus-operator-sdk-common|5.1.4|间接依赖|maven|
|io.fabric8:openshift-model-tuned|6.3.1|间接依赖|maven|
|org.hibernate.common:hibernate-commons-annotations|5.1.2.Final|间接依赖|maven|
|io.fabric8:openshift-client-api|6.3.1|间接依赖|maven|
|com.github.mifmif:generex|1.0.2|间接依赖|maven|
|jakarta.interceptor:jakarta.interceptor-api|1.2.5|间接依赖|maven|
|io.github.fastfilter:fastfilter|1.0.2|间接依赖|maven|
|org.optaplanner:optaplanner-persistence-jpa|8.45.0-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.14.2|直接依赖|maven|
|io.smallrye:smallrye-fault-tolerance-core|5.6.0|间接依赖|maven|
|org.openrewrite:rewrite-maven|7.40.3|直接依赖|maven|
|org.freemarker:freemarker|2.3.32|直接依赖|maven|
|org.apache.commons:commons-math3|3.6.1|直接依赖|maven|
|io.netty:netty-codec|4.1.86.Final|间接依赖|maven|
|io.quarkus:quarkus-smallrye-context-propagation-spi|2.16.10.Final|间接依赖|maven|
|io.fabric8:openshift-client|6.3.1|间接依赖|maven|
|net.java.dev.jna:jna|5.13.0|间接依赖|maven|
|io.netty:netty-resolver|4.1.82.Final|间接依赖|maven|
|org.checkerframework:checker-qual|3.19.0|间接依赖|maven|
|org.springframework.boot:spring-boot|2.7.12|间接依赖|maven|
|org.optaplanner:optaplanner-core|8.45.0-SNAPSHOT|直接依赖|maven|
|org.optaplanner:optaplanner-test|8.45.0-SNAPSHOT|直接依赖|maven|
|org.glassfish:javax.json|1.1.4|间接依赖|maven|
|io.quarkus:quarkus-resteasy-server-common|2.16.10.Final|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|间接依赖|maven|
|io.quarkus:quarkus-builder|2.16.10.Final|间接依赖|maven|
|io.quarkus:quarkus-jsonp-deployment|2.16.10.Final|间接依赖|maven|
|io.quarkus:quarkus-smallrye-context-propagation|2.16.10.Final|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.14.2|间接依赖|maven|
|org.yaml:snakeyaml|2.0|间接依赖|maven|
|io.smallrye.common:smallrye-common-function|1.13.2|间接依赖|maven|
|io.quarkus:quarkus-resteasy-common|2.16.10.Final|间接依赖|maven|
|io.quarkus:quarkus-credentials|2.16.6.Final|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-engine|5.9.2|间接依赖|maven|
|io.quarkus:quarkus-arc-deployment|2.16.10.Final|直接依赖|maven|
|io.smallrye.reactive:smallrye-mutiny-vertx-core|2.30.1|间接依赖|maven|
|org.openrewrite:rewrite-xml|7.40.3|直接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|间接依赖|maven|
|io.smallrye.reactive:mutiny|1.8.0|间接依赖|maven|
|org.assertj:assertj-core|3.24.2|直接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.3.Final|间接依赖|maven|
|io.quarkus:quarkus-jsonp|2.16.6.Final|间接依赖|maven|
|io.quarkus:quarkus-vertx-latebound-mdc-provider|2.16.6.Final|间接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|jakarta.json:jakarta.json-api|1.1.6|间接依赖|maven|
|io.quarkus:quarkus-core-deployment|2.16.10.Final|直接依赖|maven|
|com.squareup.okhttp3:okhttp|3.12.12|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.86.Final|间接依赖|maven|
|io.quarkus.arc:arc|2.16.6.Final|间接依赖|maven|
|org.antlr:ST4|4.3.4|间接依赖|maven|
|org.antlr:antlr-runtime|3.5.3|间接依赖|maven|
|io.vertx:vertx-auth-common|4.3.7|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.36|直接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|io.vertx:vertx-core|4.3.4|间接依赖|maven|
|org.jboss:jandex|2.4.2.Final|间接依赖|maven|
|org.springframework:spring-beans|5.3.27|间接依赖|maven|
|org.jdom:jdom2|2.0.6.1|直接依赖|maven|
|org.ow2.asm:asm-tree|9.4|间接依赖|maven|
|org.junit.platform:junit-platform-commons|1.9.2|间接依赖|maven|
|io.quarkus:quarkus-openshift-client|2.16.6.Final|间接依赖|maven|
|io.vertx:vertx-web-common|4.3.7|间接依赖|maven|
|org.jboss.resteasy:resteasy-jackson2-provider|4.7.7.Final|间接依赖|maven|
|io.quarkus:quarkus-kubernetes-client|2.16.6.Final|间接依赖|maven|
|org.glassfish:jakarta.json|1.1.6|直接依赖|maven|
|io.vertx:vertx-uri-template|4.3.6|间接依赖|maven|
|io.quarkus:quarkus-jackson-spi|2.16.10.Final|间接依赖|maven|
|io.quarkus.gizmo:gizmo|1.0.11.Final|间接依赖|maven|
|io.quarkus.arc:arc-processor|2.16.10.Final|间接依赖|maven|
|io.micrometer:micrometer-observation|1.10.4|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.82.Final|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.14.2|间接依赖|maven|
|io.fabric8:openshift-model-miscellaneous|6.3.1|间接依赖|maven|
|io.smallrye.common:smallrye-common-classloader|1.13.2|间接依赖|maven|
|org.jfree:jfreechart|1.5.4|直接依赖|maven|
|io.quarkus:quarkus-mutiny|2.16.6.Final|间接依赖|maven|
|org.apache.commons:commons-text|1.10.0|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)