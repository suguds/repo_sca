# testcontainers/testcontainers-java安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696584298621919232.svg)](https://www.murphysec.com/console/report/1696584298579976192/1696584298621919232)

仓库描述：Testcontainers is a Java library that supports JUnit tests, providing lightweight, throwaway instances of common databases, Selenium web browsers, or anything else that can run in a Docker container.

仓库地址：[https://github.com/testcontainers/testcontainers-java](https://github.com/testcontainers/testcontainers-java)

| star：7284 | watch：137 | fork：1498 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-29 19:47:52 | 许可证：MIT |
| 最近检测时间：2023-08-30 02:57:47 | 组件总数：204 | 漏洞总数：86 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|FasterXML Jackson-databind 反序列化漏洞(dbcp2 gadget绕过)|反序列化|[MPS-2018-0362](https://www.oscs1024.com/hd/MPS-2018-0362)|CVE-2017-17485|严重|
|FasterXML jackson-databind 反序列化漏洞(Hibernate/iBatis gadget绕过)||[MPS-2018-0934](https://www.oscs1024.com/hd/MPS-2018-0934)|CVE-2018-5968|高危|
|FasterXML Jackson-databind 反序列化漏洞(JdbcRowSetImpl gadget绕过)|反序列化|[MPS-2018-1438](https://www.oscs1024.com/hd/MPS-2018-1438)|CVE-2017-15095|严重|
|FasterXML Jackson-databind反序列化漏洞|反序列化|[MPS-2018-1439](https://www.oscs1024.com/hd/MPS-2018-1439)|CVE-2017-7525|严重|
|FasterXML jackson-databind 反序列化漏洞(c3p0 gadget绕过)||[MPS-2018-2477](https://www.oscs1024.com/hd/MPS-2018-2477)|CVE-2018-7489|严重|
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
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
|FasterXML jackson-databind 反序列化漏洞(ehcache gadget绕过)|动态确定对象属性修改的控制不恰当|[MPS-2019-8717](https://www.oscs1024.com/hd/MPS-2019-8717)|CVE-2019-14379|严重|
|FasterXML jackson-databind 信息泄露漏洞(logback gadget绕过)|反序列化|[MPS-2019-8770](https://www.oscs1024.com/hd/MPS-2019-8770)|CVE-2019-14439|高危|
|FasterXML jackson-databind反序列化漏洞(net.sf.ehcache gadget绕过)|反序列化|[MPS-2020-0063](https://www.oscs1024.com/hd/MPS-2020-0063)|CVE-2019-20330|严重|
|FasterXML jackson-databind反序列化漏洞(Anteros-DBCP gadget绕过)|反序列化|[MPS-2020-11987](https://www.oscs1024.com/hd/MPS-2020-11987)|CVE-2020-24616|高危|
|FasterXML jackson-databind 反序列化漏洞(pastdev gadget绕过)|反序列化|[MPS-2020-13151](https://www.oscs1024.com/hd/MPS-2020-13151)|CVE-2020-24750|高危|
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
|Netty <4.1.59.Final 存在不安全的临时文件漏洞||[MPS-2021-1580](https://www.oscs1024.com/hd/MPS-2021-1580)|CVE-2021-21290|中危|
|FasterXML jackson-databind 反序列化漏洞(javax.swing gadget绕过)|反序列化|[MPS-2021-1625](https://www.oscs1024.com/hd/MPS-2021-1625)|CVE-2021-20190|高危|
|Netty Bzip2Decoder 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28116](https://www.oscs1024.com/hd/MPS-2021-28116)|CVE-2021-37136|高危|
|Netty 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28117](https://www.oscs1024.com/hd/MPS-2021-28117)|CVE-2021-37137|高危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|jnr-posix 存在UAF漏洞|UAF|[MPS-2022-11743](https://www.oscs1024.com/hd/MPS-2022-11743)||低危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|com.fasterxml.jackson.core:jackson-databind 存在反序列化漏洞|反序列化|[MPS-2022-12433](https://www.oscs1024.com/hd/MPS-2022-12433)||高危|
|FasterXML Jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2022-12500](https://www.oscs1024.com/hd/MPS-2022-12500)||中危|
|Netty 存在信息泄露漏洞||[MPS-2022-3790](https://www.oscs1024.com/hd/MPS-2022-3790)|CVE-2022-24823|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2023-8438](https://www.oscs1024.com/hd/MPS-2023-8438)|CVE-2021-46877|中危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|io.netty:netty-handler|4.0.56.Final|4.1.94.final|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|io.netty:netty-handler|4.1.92.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.squareup.okio:okio-jvm|3.2.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.10.3|2.14.0-rc1|直接依赖|建议修复|C:0|H:2|M:5|L:0|
|com.squareup.okio:okio|3.2.0|3.4.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.14.2||间接依赖|建议修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec|4.0.56.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|io.netty:netty-handler|4.1.89.Final|4.1.94.final|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.8.8|2.14.0-rc1|间接依赖|建议修复|C:26|H:38|M:5|L:0|
|org.yaml:snakeyaml|1.33|2.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|commons-codec:commons-codec|1.11|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|com.github.jnr:jnr-posix|3.0.44|3.1.8|直接依赖|可选修复|C:0|H:0|M:0|L:1|
|com.google.guava:guava|19.0|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:2|L:1|
|commons-io:commons-io|2.6|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-common|4.0.56.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|31.1-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|152|Low|
|MIT|11|Low|
|自定义许可证|19|Low|
|EPL-2.0|7|Low|
|EPL-1.0|1|Low|
|BSD-3-Clause|6|Low|
|LGPL-2.1-or-later|1|Low|
|CPL-1.0|1|Low|
|LGPL-2.1|1|Medium|
|MPL-1.1|1|Low|
|MIT-0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.squareup.okio:okio-jvm|3.2.0|间接依赖|maven|
|com.google.http-client:google-http-client-apache-v2|1.42.2|间接依赖|maven|
|org.asynchttpclient:async-http-client-netty-utils|2.12.3|间接依赖|maven|
|org.spockframework:spock-core|2.3-groovy-4.0|直接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.92.Final|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-trace|1.26.0|间接依赖|maven|
|org.vibur:vibur-object-pool|25.0|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.92.Final|间接依赖|maven|
|org.apache.groovy:groovy-bom|4.0.4|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|2.8|间接依赖|maven|
|com.googlecode.junit-toolbox:junit-toolbox|2.4|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.25|直接依赖|maven|
|com.google.auto:auto-common|1.2|间接依赖|maven|
|io.opentelemetry:opentelemetry-api|1.26.0|间接依赖|maven|
|commons-dbutils:commons-dbutils|1.7|直接依赖|maven|
|org.apache.groovy:groovy|4.0.4|直接依赖|maven|
|org.bouncycastle:bcprov-jdk18on|1.75|间接依赖|maven|
|io.opentelemetry:opentelemetry-extension-incubator|1.26.0-alpha|间接依赖|maven|
|com.github.jnr:jnr-ffi|2.1.7|直接依赖|maven|
|com.google.auto.service:auto-service-annotations|1.0.1|直接依赖|maven|
|com.github.jnr:jnr-a64asm|1.0.0|间接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|com.squareup.okio:okio|3.2.0|直接依赖|maven|
|io.opencensus:opencensus-api|0.31.1|间接依赖|maven|
|com.google.guava:guava|32.1.2-jre|直接依赖|maven|
|com.googlecode.concurrentlinkedhashmap:concurrentlinkedhashmap-lru|1.4.2|直接依赖|maven|
|com.orientechnologies:orientdb-core|3.2.21|直接依赖|maven|
|org.vibur:vibur-dbcp|25.0|直接依赖|maven|
|org.assertj:assertj-core|3.24.2|直接依赖|maven|
|org.rnorth.duct-tape:duct-tape|1.0.8|直接依赖|maven|
|com.google.auth:google-auth-library-credentials|1.10.0|间接依赖|maven|
|mkdocs-markdownextradata-plugin|0.2.5|间接依赖|pip|
|org.awaitility:awaitility|4.2.0|直接依赖|maven|
|org.checkerframework:checker-qual|3.12.0|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.89.Final|间接依赖|maven|
|com.google.guava:guava|31.1-jre|直接依赖|maven|
|commons-lang:commons-lang|2.6|直接依赖|maven|
|com.google.http-client:google-http-client|1.42.2|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-logs|1.26.0-alpha|间接依赖|maven|
|com.google.auto.value:auto-value-annotations|1.9|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-api|5.10.0|直接依赖|maven|
|org.checkerframework:checker-qual|3.33.0|间接依赖|maven|
|junit:junit|4.13.2|直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-metrics|1.26.0|间接依赖|maven|
|com.sun.activation:jakarta.activation|1.2.2|间接依赖|maven|
|io.netty:netty-handler|4.1.92.Final|间接依赖|maven|
|com.fasterxml.jackson:jackson-bom|2.14.2|间接依赖|maven|
|com.github.jnr:jnr-x86asm|1.0.2|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|com.google.code.gson:gson|2.9.0|直接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|4.0.2|间接依赖|maven|
|:No dependencies||直接依赖|maven|
|org.ow2.asm:asm-commons|5.0.3|间接依赖|maven|
|io.opentelemetry:opentelemetry-api-events|1.26.0-alpha|间接依赖|maven|
|org.opentest4j:opentest4j|1.2.0|间接依赖|maven|
|mkdocs-codeinclude-plugin|0.2.0|间接依赖|pip|
|io.netty:netty-codec|4.0.56.Final|间接依赖|maven|
|org.ow2.asm:asm-tree|9.2|间接依赖|maven|
|org.junit.platform:junit-platform-commons|1.10.0|直接依赖|maven|
|org.yaml:snakeyaml|1.33|直接依赖|maven|
|org.apache.commons:commons-lang3|3.13.0|直接依赖|maven|
|com.hivemq:hivemq-extension-sdk|4.3.0|直接依赖|maven|
|com.zaxxer:HikariCP-java6|2.3.13|直接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.92.Final|间接依赖|maven|
|net.java.dev.jna:jna|5.12.1|间接依赖|maven|
|org.hamcrest:hamcrest|2.2|直接依赖|maven|
|org.seleniumhq.selenium:selenium-json|4.10.0|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.8.8|直接依赖|maven|
|org.bouncycastle:bcutil-jdk18on|1.75|间接依赖|maven|
|io.projectreactor:reactor-core|3.4.27|直接依赖|maven|
|io.netty:netty-resolver|4.1.92.Final|间接依赖|maven|
|com.google.errorprone:error||间接依赖|maven|
|org.seleniumhq.selenium:selenium-chrome-driver|4.10.0|直接依赖|maven|
|com.google.guava:guava|19.0|直接依赖|maven|
|org.ow2.asm:asm|9.4|间接依赖|maven|
|io.netty:netty-handler|4.0.56.Final|直接依赖|maven|
|org.ow2.asm:asm-analysis|5.0.3|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.6.20|直接依赖|maven|
|io.netty:netty-transport|4.0.56.Final|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|直接依赖|maven|
|org.seleniumhq.selenium:selenium-api|4.10.0|直接依赖|maven|
|com.google.auto.service:auto-service|1.0.1|直接依赖|maven|
|io.grpc:grpc-context|1.27.2|间接依赖|maven|
|org.junit:junit-bom|5.9.0|直接依赖|maven|
|org.jetbrains:annotations|24.0.1|直接依赖|maven|
|io.netty:netty-common|4.0.56.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.10.3|直接依赖|maven|
|mkdocs|1.3.0|间接依赖|pip|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|io.opentelemetry:opentelemetry-context|1.26.0|间接依赖|maven|
|org.apache.tomcat:tomcat-juli|10.0.27|间接依赖|maven|
|org.mockito:mockito-core|1.9.5|间接依赖|maven|
|com.github.jnr:jnr-posix|3.0.44|直接依赖|maven|
|com.github.docker-java:docker-java-api|3.3.3|直接依赖|maven|
|io.netty:netty-codec-http|4.1.92.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.10.3|间接依赖|maven|
|org.zeroturnaround:zt-exec|1.12|直接依赖|maven|
|io.netty:netty-buffer|4.1.89.Final|间接依赖|maven|
|org.seleniumhq.selenium:selenium-manager|4.10.0|直接依赖|maven|
|mysql:mysql-connector-java|8.0.33|直接依赖|maven|
|org.junit.platform:junit-platform-engine|1.9.0|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.6.20|间接依赖|maven|
|org.asynchttpclient:async-http-client|2.12.3|间接依赖|maven|
|org.freemarker:freemarker|2.3.32|直接依赖|maven|
|com.github.jnr:jnr-constants|0.9.9|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-extension-autoconfigure|1.26.0-alpha|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.6.20|间接依赖|maven|
|com.datastax.cassandra:cassandra-driver-core|3.10.0|直接依赖|maven|
|com.github.docker-java:docker-java-bom|3.3.3|直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-extension-autoconfigure-spi|1.26.0|间接依赖|maven|
|org.junit.platform:junit-platform-commons|1.9.0|间接依赖|maven|
|eu.rekawek.toxiproxy:toxiproxy-java|2.1.7|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.10.3|直接依赖|maven|
|io.r2dbc:r2dbc-spi|0.9.0.RELEASE|直接依赖|maven|
|::database-commons||直接依赖|maven|
|org.javassist:javassist|3.29.2-GA|直接依赖|maven|
|org.apache.tomcat:tomcat-jdbc|10.0.27|直接依赖|maven|
|io.dropwizard.metrics:metrics-core|3.2.6|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.14.2|直接依赖|maven|
|io.netty:netty-codec-socks|4.1.60.Final|间接依赖|maven|
|org.hamcrest:hamcrest|2.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.14.2|间接依赖|maven|
|commons-codec:commons-codec|1.11|间接依赖|maven|
|org.seleniumhq.selenium:selenium-chromium-driver|4.10.0|直接依赖|maven|
|org.ow2.asm:asm-tree|5.0.3|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|org.ow2.asm:asm-commons|9.2|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.92.Final|间接依赖|maven|
|org.glassfish.main.external:trilead-ssh2-repackaged|4.1.2|直接依赖|maven|
|com.github.jnr:jffi|1.3.9|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.8.8|间接依赖|maven|
|com.github.jnr:jnr-ffi|2.2.11|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.21|间接依赖|maven|
|::jdbc||直接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|io.netty:netty-codec|4.1.92.Final|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.15|间接依赖|maven|
|io.opentelemetry:opentelemetry-semconv|1.26.0-alpha|间接依赖|maven|
|com.github.docker-java:docker-java-transport|3.3.3|间接依赖|maven|
|com.orientechnologies:orientdb-client|3.2.21|直接依赖|maven|
|org.jboss.shrinkwrap:shrinkwrap-api|1.2.6|直接依赖|maven|
|com.google.auth:google-auth-library-oauth2-http|1.10.0|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.21.9|直接依赖|maven|
|com.typesafe.netty:netty-reactive-streams|2.0.4|间接依赖|maven|
|commons-io:commons-io|2.13.0|直接依赖|maven|
|com.mysql:mysql-connector-j|8.0.33|直接依赖|maven|
|io.netty:netty-buffer|4.1.92.Final|间接依赖|maven|
|org.ow2.asm:asm-analysis|9.2|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.60.Final|间接依赖|maven|
|io.netty:netty-codec|4.1.89.Final|间接依赖|maven|
|org.hamcrest:hamcrest-library|1.3|间接依赖|maven|
|io.netty:netty-transport|4.1.92.Final|间接依赖|maven|
|org.ow2.asm:asm-util|9.2|间接依赖|maven|
|org.jboss.shrinkwrap:shrinkwrap-spi|1.2.6|间接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-logging|1.26.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.14.2|间接依赖|maven|
|org.opentest4j:opentest4j|1.3.0|直接依赖|maven|
|io.lettuce:lettuce-core|6.2.3.RELEASE|直接依赖|maven|
|org.jboss.shrinkwrap:shrinkwrap-impl-base|1.2.6|直接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|mkdocs-material|8.1.3|间接依赖|pip|
|io.netty:netty-common|4.1.89.Final|直接依赖|maven|
|org.lz4:lz4-java|1.8.0|直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-common|1.26.0|间接依赖|maven|
|org.objenesis:objenesis|1.0|间接依赖|maven|
|net.lingala.zip4j:zip4j|2.11.5|直接依赖|maven|
|net.bytebuddy:byte-buddy|1.14.4|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.8.8|间接依赖|maven|
|io.netty:netty-transport|4.1.89.Final|直接依赖|maven|
|io.netty:netty-resolver|4.1.89.Final|间接依赖|maven|
|com.github.docker-java:docker-java-core|3.3.3|直接依赖|maven|
|org.seleniumhq.selenium:selenium-http|4.10.0|间接依赖|maven|
|::testcontainers||直接依赖|maven|
|org.apache.commons:commons-compress|1.23.0|直接依赖|maven|
|org.hamcrest:hamcrest-core|1.3|间接依赖|maven|
|io.opentelemetry:opentelemetry-api-logs|1.26.0-alpha|间接依赖|maven|
|com.github.jnr:jffi|1.2.16|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.92.Final|间接依赖|maven|
|com.github.docker-java:docker-java-transport-zerodep|3.3.3|直接依赖|maven|
|org.apache.commons:commons-exec|1.3|间接依赖|maven|
|com.google.http-client:google-http-client-gson|1.42.2|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk|1.26.0|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|直接依赖|maven|
|commons-io:commons-io|2.6|间接依赖|maven|
|com.google.cloud.tools:jib-build-plan|0.4.0|间接依赖|maven|
|org.junit:junit-bom|5.10.0|直接依赖|maven|
|io.netty:netty-handler|4.1.89.Final|直接依赖|maven|
|com.squareup.okhttp3:okhttp|4.11.0|直接依赖|maven|
|io.netty:netty-buffer|4.0.56.Final|间接依赖|maven|
|com.google.guava:guava-parent|32.1.2-jre|间接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|dev.failsafe:failsafe|3.3.1|间接依赖|maven|
|org.seleniumhq.selenium:selenium-remote-driver|4.10.0|直接依赖|maven|
|com.google.cloud.tools:jib-core|0.23.0|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.6.20|直接依赖|maven|
|com.github.jnr:jnr-posix|3.1.15|直接依赖|maven|
|org.bouncycastle:bcpkix-jdk18on|1.75|间接依赖|maven|
|io.netty:netty-common|4.1.92.Final|间接依赖|maven|
|io.opencensus:opencensus-contrib-http-util|0.31.1|间接依赖|maven|
|org.ow2.asm:asm-util|5.0.3|间接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|直接依赖|maven|
|com.github.jnr:jnr-constants|0.10.3|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)