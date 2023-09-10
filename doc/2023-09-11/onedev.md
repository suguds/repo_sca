# theonedev/onedev安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700932557864566784.svg)](https://www.murphysec.com/console/report/1700932557822623744/1700932557864566784)

仓库描述：Self-hosted Git Server with CI/CD and Kanban

仓库地址：[https://github.com/theonedev/onedev](https://github.com/theonedev/onedev)

| star：11804 | watch：132 | fork：791 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-10 19:57:20 | 许可证：NOASSERTION |
| 最近检测时间：2023-09-11 02:14:39 | 组件总数：379 | 漏洞总数：83 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|FasterXML Jackson-databind代码问题漏洞(axis2-transport-jms gadget绕过)|反序列化|[MPS-2019-0023](https://www.oscs1024.com/hd/MPS-2019-0023)|CVE-2018-19360|严重|
|FasterXML Jackson-databind代码问题漏洞(openjpa gadget绕过)|反序列化|[MPS-2019-0024](https://www.oscs1024.com/hd/MPS-2019-0024)|CVE-2018-19361|严重|
|FasterXML Jackson-databind代码问题漏洞(jboss-common-core gadget绕过)|反序列化|[MPS-2019-0025](https://www.oscs1024.com/hd/MPS-2019-0025)|CVE-2018-19362|严重|
|FasterXML jackson-databind 反序列化漏洞(HikariCP gadget绕过)|反序列化|[MPS-2019-11529](https://www.oscs1024.com/hd/MPS-2019-11529)|CVE-2019-14540|严重|
|FasterXML jackson-databind 反序列化漏洞(HikariCP gadget绕过)|反序列化|[MPS-2019-11533](https://www.oscs1024.com/hd/MPS-2019-11533)|CVE-2019-16335|严重|
|FasterXML jackson-databind 反序列化漏洞(commons-dbcp gadget绕过)|反序列化|[MPS-2019-12479](https://www.oscs1024.com/hd/MPS-2019-12479)|CVE-2019-16942|严重|
|FasterXML jackson-databind 反序列化漏洞(p6spy gadget绕过)|反序列化|[MPS-2019-12480](https://www.oscs1024.com/hd/MPS-2019-12480)|CVE-2019-16943|严重|
|FasterXML jackson-databind 反序列化漏洞(ehcache gadget绕过)|反序列化|[MPS-2019-12676](https://www.oscs1024.com/hd/MPS-2019-12676)|CVE-2019-17267|严重|
|FasterXML jackson-databind 反序列化漏洞(apache-log4j-extras gadget绕过)|反序列化|[MPS-2019-13103](https://www.oscs1024.com/hd/MPS-2019-13103)|CVE-2019-17531|严重|
|FasterXML jackson-databind 反序列化漏洞(mysql gadget绕过)|反序列化|[MPS-2019-5442](https://www.oscs1024.com/hd/MPS-2019-5442)|CVE-2019-12086|高危|
|FasterXML jackson-databind 反序列化漏洞(jdom gadget绕过)|反序列化|[MPS-2019-6867](https://www.oscs1024.com/hd/MPS-2019-6867)|CVE-2019-12814|中危|
|FasterXML jackson-databind 反序列化漏洞(logback-classic gadget绕过)|反序列化|[MPS-2019-7047](https://www.oscs1024.com/hd/MPS-2019-7047)|CVE-2019-12384|中危|
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
|FasterXML jackson-databind 反序列化漏洞(javax.swing gadget绕过)|反序列化|[MPS-2021-1625](https://www.oscs1024.com/hd/MPS-2021-1625)|CVE-2021-20190|高危|
|netplex json-smart-v  分布式拒绝服务攻击|对因果或异常条件的不恰当检查|[MPS-2021-2102](https://www.oscs1024.com/hd/MPS-2021-2102)|CVE-2021-27568|严重|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|Jakarta Expression Language <=3.0.3 存在输入验证错误漏洞|表达式语言注入|[MPS-2021-7671](https://www.oscs1024.com/hd/MPS-2021-7671)|CVE-2021-28170|中危|
|json-smart 存在拒绝服务漏洞|越界写入|[MPS-2021-7737](https://www.oscs1024.com/hd/MPS-2021-7737)|CVE-2021-31684|高危|
|Apache Tika 拒绝服务漏洞|拒绝服务|[MPS-2022-10977](https://www.oscs1024.com/hd/MPS-2022-10977)|CVE-2022-30973|中危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|com.nimbusds:oauth2-oidc-sdk 存在XXE漏洞|XXE|[MPS-2022-12182](https://www.oscs1024.com/hd/MPS-2022-12182)||高危|
|com.beust:jcommander 存在从非可信控制范围包含功能例程漏洞||[MPS-2022-12225](https://www.oscs1024.com/hd/MPS-2022-12225)||中危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|com.fasterxml.jackson.core:jackson-databind 存在反序列化漏洞|反序列化|[MPS-2022-12433](https://www.oscs1024.com/hd/MPS-2022-12433)||高危|
|Eclipse Jetty URI注入漏洞|注入|[MPS-2022-18060](https://www.oscs1024.com/hd/MPS-2022-18060)|CVE-2022-2047|低危|
|Apache Tika 拒绝服务漏洞|拒绝服务|[MPS-2022-19059](https://www.oscs1024.com/hd/MPS-2022-19059)|CVE-2022-33879|中危|
|xstream project跨界内存写漏洞|越界写入|[MPS-2022-57066](https://www.oscs1024.com/hd/MPS-2022-57066)|CVE-2022-40151|高危|
|HSQLDB <2.7.1 存在远程代码执行漏洞|使用外部可控制的输入来选择类或代码（不安全的反射）|[MPS-2022-58477](https://www.oscs1024.com/hd/MPS-2022-58477)|CVE-2022-41853|高危|
|XStream < 1.4.20 栈缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58603](https://www.oscs1024.com/hd/MPS-2022-58603)|CVE-2022-41966|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Apache Tika 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2022-9836](https://www.oscs1024.com/hd/MPS-2022-9836)|CVE-2022-30126|中危|
|Eclipse Jetty 资源管理错误漏洞|拒绝服务|[MPS-2023-4997](https://www.oscs1024.com/hd/MPS-2023-4997)|CVE-2023-26048|中危|
|Eclipse Jetty 信息泄露漏洞|XSS|[MPS-2023-4998](https://www.oscs1024.com/hd/MPS-2023-4998)|CVE-2023-26049|中危|
|netplex json-smart 安全漏洞|未经控制的递归|[MPS-2023-7760](https://www.oscs1024.com/hd/MPS-2023-7760)|CVE-2023-1370|高危|
|Hazelcast 安全漏洞|凭证保护不足|[MPS-8wc3-pyfm](https://www.oscs1024.com/hd/MPS-8wc3-pyfm)|CVE-2023-33264|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.squareup.okio:okio|1.14.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.nimbusds:oauth2-oidc-sdk|6.5|9.3.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.14.0-rc1||间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.eclipse.jetty:jetty-server|9.4.51.v20230217|12.0.0.beta0|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|net.minidev:json-smart|2.3|2.4.9|间接依赖|建议修复|C:1|H:2|M:0|L:0|
|org.hsqldb:hsqldb|2.4.0|2.7.1|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.9.7|2.14.0-rc1|间接依赖|建议修复|C:17|H:36|M:5|L:0|
|org.yaml:snakeyaml|1.32|2.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.thoughtworks.xstream:xstream|1.4.19|1.4.20|直接依赖|建议修复|C:0|H:1|M:1|L:0|
|com.google.code.gson:gson|2.6.2|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.hazelcast:hazelcast|5.1.7|5.3.0|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.bouncycastle:bcprov-jdk15on|1.69||直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.glassfish:javax.el|3.0.0||直接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|20.0|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|com.google.code.gson:gson|2.8.0|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-http|9.4.51.v20230217|11.0.10|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|commons-io:commons-io|2.5|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.beust:jcommander|1.48|1.75|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-codec:commons-codec|1.11|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.apache.tika:tika-core|1.24.1|2.4.1|直接依赖|可选修复|C:0|H:0|M:3|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|8|Low|
|LGPL-2.1|7|Medium|
|EPL-1.0|27|Low|
|LGPL-2.1-or-later|7|Low|
|MIT|20|Low|
|BSD-2-Clause|24|Low|
|Apache-2.0|148|Low|
|自定义许可证|48|Low|
|EPL-2.0|22|Low|
|LGPL-3.0|3|Medium|
|CDDL-1.1|2|Low|
|MPL-1.1|2|Low|
|WTFPL|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.connectbot:sshlib|2.2.21|直接依赖|maven|
|com.mchange:c3p0|0.9.5.4|间接依赖|maven|
|org.hibernate:hibernate-jcache|5.4.24.Final|直接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.25|间接依赖|maven|
|com.microsoft.azure:adal4j|1.6.4|直接依赖|maven|
|org.ow2.asm:asm-analysis|9.2|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-collection|0.64.0|间接依赖|maven|
|libpthread.so.0||间接依赖||
|org.apache.commons:commons-lang3|3.5|间接依赖|maven|
|librt.so.1||间接依赖||
|org.jboss:jandex|2.1.3.Final|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.21|间接依赖|maven|
|org.jvnet.staxex:stax-ex|1.8|间接依赖|maven|
|org.glassfish.jersey.core:jersey-common|2.37|间接依赖|maven|
|com.hazelcast:hazelcast|5.1.7|直接依赖|maven|
|com.google.j2objc:j2objc-annotations|2.8|间接依赖|maven|
|net.java.dev.jna:jna|4.2.1|直接依赖|maven|
|PSAPI.DLL||间接依赖||
|org.glassfish.jersey.core:jersey-server|2.37|间接依赖|maven|
|org.ow2.asm:asm-commons|9.2|间接依赖|maven|
|CRYPT32.dll||间接依赖||
|org.sonarsource.javascript:javascript-frontend|7.4.4.15624|间接依赖|maven|
|org.owasp.encoder:encoder|1.2.3|间接依赖|maven|
|USER32.dll||间接依赖||
|libc.so.1||间接依赖||
|org.apache.httpcomponents:httpcore|4.4.13|间接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|9.31|间接依赖|maven|
|io.onedev:server-plugin-report-trx|9.1.6|直接依赖|maven|
|io.onedev:server-plugin-report-unittest|9.1.6|直接依赖|maven|
|com.nimbusds:oauth2-oidc-sdk|6.5|间接依赖|maven|
|com.zaxxer:HikariCP|2.7.9|直接依赖|maven|
|org.glassfish:javax.json|1.0.4|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.10.17|间接依赖|maven|
|io.onedev:commons-utils|2.7.22|间接依赖|maven|
|org.jetbrains.pty4j:purejavacomm|0.0.11.1|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-server|9.4.51.v20230217|直接依赖|maven|
|commons-codec:commons-codec|1.13|直接依赖|maven|
|com.vladsch.flexmark:flexmark-util|0.64.0|间接依赖|maven|
|org.jetbrains.xodus:xodus-openAPI|2.0.1|间接依赖|maven|
|org.hibernate:hibernate-core|5.4.24.Final|直接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|org.apache.shiro:shiro-event|1.12.0|间接依赖|maven|
|net.java.dev.jna:jna-platform|5.9.0|间接依赖|maven|
|org.hibernate:hibernate-hikaricp|5.4.24.Final|直接依赖|maven|
|commons-codec:commons-codec|1.11|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|间接依赖|maven|
|net.java.dev.jna:jna-platform|4.2.1|直接依赖|maven|
|com.google.inject.extensions:guice-multibindings|4.2.3|间接依赖|maven|
|KERNEL32.dll||间接依赖||
|io.onedev:server-plugin-report-pmd|9.1.6|直接依赖|maven|
|com.squareup.okhttp3:logging-interceptor|3.11.0|间接依赖|maven|
|org.apache.shiro:shiro-guice|1.12.0|直接依赖|maven|
|org.glassfish.hk2.external:jakarta.inject|2.6.1|间接依赖|maven|
|com.github.waffle:waffle-jna|1.9.0|直接依赖|maven|
|jakarta.el:jakarta.el-api|3.0.3|间接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|9.22|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.1.Final|间接依赖|maven|
|org.codehaus.groovy:groovy-templates|3.0.13|直接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.4.51.v20230217|直接依赖|maven|
|io.onedev:server-plugin-executor-serverdocker|9.1.6|直接依赖|maven|
|commons-lang:commons-lang|2.6|间接依赖|maven|
|org.ow2.asm:asm|5.0.4|间接依赖|maven|
|org.glassfish:jakarta.el|3.0.4|间接依赖|maven|
|org.jetbrains.xodus:xodus-environment|2.0.1|间接依赖|maven|
|ole32.dll||间接依赖||
|org.eclipse.jgit:org.eclipse.jgit.http.server|5.13.0.202109080827-r|直接依赖|maven|
|com.nimbusds:lang-tag|1.7|间接依赖|maven|
|commons-fileupload:commons-fileupload|1.5|直接依赖|maven|
|io.onedev:server-plugin-import-github|9.1.6|直接依赖|maven|
|io.onedev:server-plugin-buildspec-maven|9.1.6|直接依赖|maven|
|io.onedev:server-core|9.1.6|直接依赖|maven|
|MPR.dll||间接依赖||
|javax.xml.bind:jaxb-api|2.3.1|直接依赖|maven|
|org.eclipse.jetty:jetty-servlets|9.4.51.v20230217|直接依赖|maven|
|libgcc_s.so.1||间接依赖||
|org.eclipse.jgit:org.eclipse.jgit.archive|5.13.0.202109080827-r|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.13.3|间接依赖|maven|
|com.squareup.okio:okio|1.14.0|间接依赖|maven|
|javax.activation:activation|1.1|间接依赖|maven|
|org.eclipse.jgit:org.eclipse.jgit.gpg.bc|5.13.0.202109080827-r|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.14.0-rc1|间接依赖|maven|
|org.apache.lucene:lucene-backward-codecs|8.7.0|直接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|libthr.so.3||间接依赖||
|io.onedev:server-plugin-import-youtrack|9.1.6|直接依赖|maven|
|org.glassfish.hk2:hk2-locator|2.6.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.9.7|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-builder|0.64.0|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.18.0|间接依赖|maven|
|com.microsoft.azure:azure-keyvault-cryptography|1.2.1|间接依赖|maven|
|com.google.guava:guava|20.0|间接依赖|maven|
|org.eclipse.jetty:jetty-continuation|9.4.51.v20230217|间接依赖|maven|
|org.apache.wicket:wicket-devutils|7.18.0|直接依赖|maven|
|org.sonarsource.sslr-squid-bridge:sslr-squid-bridge|2.7.1.392|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-gfm-tasklist|0.64.0|直接依赖|maven|
|org.eclipse.core:org.eclipse.core.runtime|3.13.0.v20170207|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.25|直接依赖|maven|
|org.sonarsource.sslr:sslr-core|1.24.0.633|间接依赖|maven|
|com.google.zxing:javase|3.2.1|直接依赖|maven|
|ch.qos.logback:logback-core|1.2.11|间接依赖|maven|
|com.vladsch.flexmark:flexmark|0.64.0|直接依赖|maven|
|org.eclipse.jetty:jetty-util-ajax|9.4.51.v20230217|间接依赖|maven|
|io.onedev:server-plugin-sso-discord|9.1.6|直接依赖|maven|
|javax.websocket:javax.websocket-api|1.1|间接依赖|maven|
|com.ongres.stringprep:stringprep|1.1|直接依赖|maven|
|org.apache.lucene:lucene-queries|8.7.0|直接依赖|maven|
|org.abego.treelayout:org.abego.treelayout.core|1.0.3|间接依赖|maven|
|WS2_32.dll||间接依赖||
|libsocket.so.1||间接依赖||
|io.onedev:server-plugin-report-checkstyle|9.1.6|直接依赖|maven|
|io.onedev:server-plugin-executor-remotedocker|9.1.6|直接依赖|maven|
|pdh.dll||间接依赖||
|org.eclipse.core:org.eclipse.core.resources|3.9.1.v20140825|间接依赖|maven|
|org.eclipse.core:org.eclipse.core.contenttype|3.4.200.v20140207|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|io.onedev:server-plugin-executor-remoteshell|9.1.6|直接依赖|maven|
|org.slf4j:log4j-over-slf4j|1.7.36|间接依赖|maven|
|io.reactivex:rxjava|1.3.8|间接依赖|maven|
|org.ocpsoft.prettytime:prettytime|4.0.1.Final|直接依赖|maven|
|/System/Library/Frameworks/SystemConfiguration.framework/Versions/A/SystemConfiguration||间接依赖||
|com.ongres.stringprep:saslprep|1.1|直接依赖|maven|
|io.onedev:server-ee|9.1.6|直接依赖|maven|
|org.jsoup:jsoup|1.15.3|间接依赖|maven|
|org.apache.lucene:lucene-sandbox|8.7.0|间接依赖|maven|
|libm.so.2||间接依赖||
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.3|间接依赖|maven|
|org.apache.wicket:wicket-util|7.18.0|直接依赖|maven|
|io.onedev:commons-codeassist|2.7.22|直接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet-core|2.37|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-anchorlink|0.64.0|直接依赖|maven|
|libc.so.6||间接依赖||
|com.zaxxer:HikariCP-java7|2.4.13|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|org.apache.lucene:lucene-queryparser|8.7.0|直接依赖|maven|
|joda-time:joda-time|2.2|直接依赖|maven|
|org.jvnet.winp:winp|1.30|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.14.0-rc1|间接依赖|maven|
|io.onedev:server-plugin-sso-openid|9.1.6|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.14.0-rc1|间接依赖|maven|
|/System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation||间接依赖||
|io.onedev:commons-jsymbol|2.7.22|直接依赖|maven|
|com.squareup.okhttp3:okhttp|3.11.0|间接依赖|maven|
|org.yaml:snakeyaml|1.32|直接依赖|maven|
|org.eclipse.jetty:jetty-security|9.4.51.v20230217|间接依赖|maven|
|org.apache.wicket:wicket-extensions|7.18.0|直接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|io.onedev:server-plugin-report-markdown|9.1.6|直接依赖|maven|
|com.github.albfernandez:juniversalchardet|2.4.0|直接依赖|maven|
|org.json:json|20230227|直接依赖|maven|
|org.jetbrains.xodus:xodus-vfs|2.0.1|间接依赖|maven|
|org.glassfish.hk2:hk2-api|2.5.0|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.51.v20230217|间接依赖|maven|
|io.onedev:server-plugin-buildspec-node|9.1.6|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.6.10|间接依赖|maven|
|org.apache.wicket:wicket-request|7.18.0|直接依赖|maven|
|com.sun.xml.fastinfoset:FastInfoset|1.2.15|间接依赖|maven|
|commons-io:commons-io|2.7|直接依赖|maven|
|libnsl.so.1||间接依赖||
|org.glassfish.jersey.ext:jersey-entity-filtering|2.37|间接依赖|maven|
|commons-logging:commons-logging|1.1.1|间接依赖|maven|
|org.glassfish.jersey.security:oauth2-client|2.37|直接依赖|maven|
|org.apache.lucene:lucene-analyzers-common|8.7.0|直接依赖|maven|
|org.checkerframework:checker-qual|3.33.0|间接依赖|maven|
|org.apache.shiro:shiro-cache|1.12.0|间接依赖|maven|
|org.nibor.autolink:autolink|0.6.0|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.2.5.Final|直接依赖|maven|
|com.squareup.retrofit2:retrofit|2.5.0|间接依赖|maven|
|IPHLPAPI.DLL||间接依赖||
|org.apache.shiro:shiro-crypto-hash|1.12.0|间接依赖|maven|
|io.onedev:server-plugin-executor-servershell|9.1.6|直接依赖|maven|
|org.apache.ant:ant|1.10.11|间接依赖|maven|
|libc.so.7||间接依赖||
|com.microsoft.rest:client-runtime|1.6.10|直接依赖|maven|
|io.onedev:server-plugin-import-bitbucketcloud|9.1.6|直接依赖|maven|
|org.eclipse.cdt:org.eclipse.cdt.core|5.11.0|间接依赖|maven|
|io.onedev:server-plugin-notification-discord|9.1.6|直接依赖|maven|
|libm.so.1||间接依赖||
|org.quartz-scheduler:quartz|2.3.2|直接依赖|maven|
|com.sun.mail:javax.mail|1.6.1|间接依赖|maven|
|io.github.hakky54:sslcontext-kickstart-for-jetty|7.4.9|间接依赖|maven|
|WINTRUST.dll||间接依赖||
|com.fasterxml.jackson.core:jackson-core|2.9.6|间接依赖|maven|
|com.nimbusds:lang-tag|1.6|间接依赖|maven|
|org.unbescape:unbescape|1.1.2.RELEASE|直接依赖|maven|
|net.i2p.crypto:eddsa|0.3.0|直接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-toc|0.64.0|直接依赖|maven|
|net.java.dev.jna:jna|4.5.1|间接依赖|maven|
|com.squareup.retrofit2:converter-jackson|2.5.0|间接依赖|maven|
|org.glassfish.jersey.media:jersey-media-json-jackson|2.37|间接依赖|maven|
|io.onedev:server-plugin-executor-kubernetes|9.1.6|直接依赖|maven|
|io.onedev:server-plugin-report-junit|9.1.6|直接依赖|maven|
|org.eclipse.jetty.websocket:websocket-api|9.4.51.v20230217|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-autolink|0.64.0|直接依赖|maven|
|com.github.jnr:jffi|1.3.9|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|io.onedev:server-plugin-notification-slack|9.1.6|直接依赖|maven|
|org.eclipse.jgit:org.eclipse.jgit|5.13.0.202109080827-r|间接依赖|maven|
|io.github.hakky54:sslcontext-kickstart|7.4.9|间接依赖|maven|
|/usr/lib/libSystem.B.dylib||间接依赖||
|org.dom4j:dom4j|2.1.3|直接依赖|maven|
|net.minidev:json-smart||间接依赖|maven|
|com.github.jnr:jnr-a64asm|1.0.0|间接依赖|maven|
|net.minidev:accessors-smart|1.2|间接依赖|maven|
|io.onedev:server-plugin-report-spotbugs|9.1.6|直接依赖|maven|
|org.apache.shiro:shiro-config-core|1.12.0|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.11|间接依赖|maven|
|org.apache.lucene:lucene-core|8.7.0|直接依赖|maven|
|io.onedev:agent|1.9.1|直接依赖|maven|
|io.onedev:server-plugin-authenticator-ldap|9.1.6|直接依赖|maven|
|org.reflections:reflections|0.9.11|间接依赖|maven|
|io.onedev:server-plugin-import-url|9.1.6|直接依赖|maven|
|org.bouncycastle:bcpg-jdk15on|1.69|间接依赖|maven|
|NETAPI32.dll||间接依赖||
|org.ow2.asm:asm-tree|9.2|间接依赖|maven|
|net.minidev:json-smart|2.3|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-sequence|0.64.0|间接依赖|maven|
|org.jetbrains.xodus:xodus-entity-store|2.0.1|直接依赖|maven|
|net.java.dev.jna:jna-platform|4.5.1|间接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.51.v20230217|间接依赖|maven|
|com.sun.istack:istack-commons-runtime|3.0.7|间接依赖|maven|
|javax.persistence:javax.persistence-api|2.2|间接依赖|maven|
|com.mchange:mchange-commons-java|0.2.15|间接依赖|maven|
|backport-util-concurrent:backport-util-concurrent|3.1|间接依赖|maven|
|io.onedev:server-plugin-report-cpd|9.1.6|直接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|org.eclipse.equinox:org.eclipse.equinox.registry|3.5.400.v20140428|间接依赖|maven|
|com.github.waffle:waffle-jna|1.9.1|直接依赖|maven|
|com.github.jnr:jnr-posix|3.1.15|间接依赖|maven|
|org.antlr:antlr-runtime|3.5.2|间接依赖|maven|
|io.onedev:k8s-helper|2.11.1|间接依赖|maven|
|com.thoughtworks.xstream:xstream|1.4.19|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.6.10|间接依赖|maven|
|libthread.so.1||间接依赖||
|org.eclipse.core:org.eclipse.core.jobs|3.5.300.v20130429|间接依赖|maven|
|com.microsoft.azure:azure-client-runtime|1.6.4|间接依赖|maven|
|io.onedev:server-plugin-report-problem|9.1.6|直接依赖|maven|
|com.sun.mail:javax.mail|1.6.2|直接依赖|maven|
|com.github.oshi:oshi-core|5.8.2|间接依赖|maven|
|libm.so.5||间接依赖||
|com.vladsch.flexmark:flexmark-util-data|0.64.0|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.32|间接依赖|maven|
|io.onedev:server-plugin-import-gitlab|9.1.6|直接依赖|maven|
|org.apache.commons:commons-lang3|3.8.1|间接依赖|maven|
|org.objenesis:objenesis|3.2|直接依赖|maven|
|com.github.stephenc.jcip:jcip-annotations|1.0-1|间接依赖|maven|
|org.glassfish.hk2:hk2-utils|2.5.0|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet|2.37|直接依赖|maven|
|org.jboss.spec.javax.transaction:jboss-transaction-api_1.2_spec|1.1.1.Final|间接依赖|maven|
|org.glassfish.hk2:guice-bridge|2.5.0|直接依赖|maven|
|org.glassfish.hk2.external:aopalliance-repackaged|2.5.0|间接依赖|maven|
|com.microsoft.azure:azure-keyvault-webkey|1.2.1|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-tables|0.64.0|直接依赖|maven|
|com.vladsch.flexmark:flexmark-util-options|0.64.0|间接依赖|maven|
|com.google.code.gson:gson|2.6.2|间接依赖|maven|
|com.github.jnr:jnr-x86asm|1.0.2|间接依赖|maven|
|org.mnode.ical4j:ical4j|1.0.2|间接依赖|maven|
|jaxen:jaxen|1.1.6|直接依赖|maven|
|io.github.x-stream:mxparser|1.2.2|间接依赖|maven|
|org.glassfish.jaxb:txw2|2.3.1|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-format|0.64.0|间接依赖|maven|
|ld-linux-armhf.so.3||间接依赖||
|org.apache.ant:ant-launcher|1.10.11|间接依赖|maven|
|org.hibernate.common:hibernate-commons-annotations|5.1.2.Final|间接依赖|maven|
|com.nimbusds:content-type|2.2|间接依赖|maven|
|io.onedev:server-plugin-report-cobertura|9.1.6|直接依赖|maven|
|io.github.microutils:kotlin-logging|1.7.9|间接依赖|maven|
|org.apache.wicket:wicket-native-websocket-core|7.18.0|直接依赖|maven|
|SHLWAPI.dll||间接依赖||
|org.apache.shiro:shiro-crypto-cipher|1.12.0|间接依赖|maven|
|libpthread.so.1||间接依赖||
|jakarta.ws.rs:jakarta.ws.rs-api|2.1.6|间接依赖|maven|
|com.ongres.scram:client|2.1|直接依赖|maven|
|io.onedev:server-plugin-buildspec-gradle|9.1.6|直接依赖|maven|
|org.bouncycastle:bcutil-jdk15on|1.69|间接依赖|maven|
|org.jetbrains.xodus:xodus-utils|2.0.1|间接依赖|maven|
|com.github.jnr:jnr-ffi|2.2.11|间接依赖|maven|
|io.onedev:server-plugin-buildspec-dotnet|9.1.6|直接依赖|maven|
|org.javassist:javassist|3.27.0-GA|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-client|9.4.51.v20230217|间接依赖|maven|
|org.apache.shiro:shiro-crypto-core|1.12.0|间接依赖|maven|
|org.eclipse.equinox:org.eclipse.equinox.common|3.6.200.v20130402|间接依赖|maven|
|org.apache.commons:commons-collections4|4.2|间接依赖|maven|
|org.codehaus.groovy:groovy|3.0.13|间接依赖|maven|
|org.apache.shiro:shiro-lang|1.12.0|间接依赖|maven|
|org.eclipse:org.eclipse.osgi|3.12.0.v20170512|间接依赖|maven|
|org.hibernate:hibernate-entitymanager|5.4.24.Final|直接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.6.2|间接依赖|maven|
|ADVAPI32.dll||间接依赖||
|org.codehaus.groovy:groovy-xml|3.0.13|间接依赖|maven|
|org.apache.shiro:shiro-web|1.12.0|直接依赖|maven|
|org.osgi:org.osgi.core|6.0.0|间接依赖|maven|
|com.google.code.gson:gson|2.8.0|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|org.eclipse.core:org.eclipse.core.filesystem|1.7.0.v20170406|间接依赖|maven|
|org.ow2.asm:asm-util|9.2|间接依赖|maven|
|org.glassfish.hk2:osgi-resource-locator|1.0.3|间接依赖|maven|
|com.ongres.scram:common|2.1|直接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-definition|0.64.0|直接依赖|maven|
|com.microsoft.azure:azure-keyvault-core|1.2.1|间接依赖|maven|
|org.eclipse.jetty:jetty-client|9.4.51.v20230217|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|io.onedev:server-plugin-import-jiracloud|9.1.6|直接依赖|maven|
|/usr/lib/libiconv.2.dylib||间接依赖||
|org.apache.commons:commons-compress|1.21|直接依赖|maven|
|org.apache.wicket:wicket-core|7.18.0|直接依赖|maven|
|org.eclipse.jetty.websocket:websocket-servlet|9.4.51.v20230217|间接依赖|maven|
|org.jetbrains.xodus:xodus-compress|2.0.1|间接依赖|maven|
|SHELL32.dll||间接依赖||
|org.glassfish.jaxb:jaxb-runtime|2.3.1|间接依赖|maven|
|io.onedev:commons-bootstrap|2.7.22|直接依赖|maven|
|commons-io:commons-io|2.5|间接依赖|maven|
|org.eclipse.jetty:jetty-http|9.4.51.v20230217|间接依赖|maven|
|com.google.guava:guava|32.0.1-jre|直接依赖|maven|
|org.apache.sshd:sshd-core|2.9.2|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|直接依赖|maven|
|/System/Library/Frameworks/Foundation.framework/Versions/C/Foundation||间接依赖||
|xmlpull:xmlpull|1.1.3.1|间接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-visitor|0.64.0|间接依赖|maven|
|org.eclipse.jetty:jetty-server|9.4.51.v20230217|直接依赖|maven|
|org.apache.shiro:shiro-core|1.12.0|直接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.1|间接依赖|maven|
|net.java.dev.jna:jna|5.9.0|间接依赖|maven|
|com.squareup.retrofit2:adapter-rxjava|2.4.0|间接依赖|maven|
|io.onedev:server-plugin-report-jest|9.1.6|直接依赖|maven|
|de.taimos:totp|1.0|直接依赖|maven|
|org.glassfish.jersey.ext:jersey-bean-validation|2.37|直接依赖|maven|
|com.vladsch.flexmark:flexmark-util-html|0.64.0|间接依赖|maven|
|com.github.javaparser:javaparser-core|3.0.0|间接依赖|maven|
|org.antlr:ST4|4.1|间接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-ast|0.64.0|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-dependency|0.64.0|间接依赖|maven|
|com.github.jnr:jnr-constants|0.10.3|间接依赖|maven|
|io.onedev:server-plugin-import-gitea|9.1.6|直接依赖|maven|
|org.antlr:antlr4|4.7.2|间接依赖|maven|
|io.onedev:server-plugin-report-clover|9.1.6|直接依赖|maven|
|org.ow2.asm:asm|9.1|间接依赖|maven|
|VERSION.dll||间接依赖||
|io.onedev:server-plugin-report-coverage|9.1.6|直接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.69|直接依赖|maven|
|com.googlecode.javaewah:JavaEWAH|1.1.12|间接依赖|maven|
|libm.so.6||间接依赖||
|com.microsoft.azure:azure-annotations|1.7.0|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.9.2|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|间接依赖|maven|
|com.nimbusds:oauth2-oidc-sdk|9.35|直接依赖|maven|
|com.vladsch.flexmark:flexmark-util-misc|0.64.0|间接依赖|maven|
|com.google.inject:guice|4.2.3|间接依赖|maven|
|com.hazelcast:hazelcast-hibernate53|2.2.1|直接依赖|maven|
|com.squareup.okhttp3:okhttp-urlconnection|3.11.0|间接依赖|maven|
|org.glassfish:javax.el|3.0.0|直接依赖|maven|
|com.beust:jcommander|1.48|间接依赖|maven|
|org.hsqldb:hsqldb|2.4.0|直接依赖|maven|
|org.apache.commons:commons-text|1.10.0|间接依赖|maven|
|org.apache.tika:tika-core|1.24.1|直接依赖|maven|
|antlr:antlr|2.7.7|间接依赖|maven|
|org.antlr:antlr4-runtime|4.7.2|直接依赖|maven|
|commons-digester:commons-digester|1.8|间接依赖|maven|
|com.joestelmach:natty|0.13|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-joda|2.9.8|间接依赖|maven|
|io.onedev:server-plugin-report-roslynator|9.1.6|直接依赖|maven|
|io.onedev:server-plugin-report-jacoco|9.1.6|直接依赖|maven|
|commons-validator:commons-validator|1.4.0|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|间接依赖|maven|
|com.google.zxing:core|3.2.1|间接依赖|maven|
|com.ibm.icu:icu4j|59.1|间接依赖|maven|
|joda-time:joda-time|2.7|间接依赖|maven|
|javax.cache:cache-api|1.0.0|间接依赖|maven|
|org.jetbrains.pty4j:pty4j|0.12.5|间接依赖|maven|
|org.apache.commons:commons-collections4|4.1|直接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.69|间接依赖|maven|
|org.glassfish.jersey.core:jersey-client|2.37|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-gitlab|0.64.0|直接依赖|maven|
|javax.servlet:javax.servlet-api|3.1.0|间接依赖|maven|
|com.microsoft.azure:azure-keyvault|1.2.1|直接依赖|maven|
|org.glassfish.jersey.inject:jersey-hk2|2.37|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.9.6|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)