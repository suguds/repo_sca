# apache/incubator-paimon安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1697672256154288128.svg)](https://www.murphysec.com/console/report/1694047191298371584/1697672256154288128)

仓库描述：Apache Paimon(incubating) is a streaming data lake platform that supports high-speed data ingestion, change data tracking and efficient real-time analytics.

仓库地址：[https://github.com/apache/incubator-paimon](https://github.com/apache/incubator-paimon)

| star：1262 | watch：65 | fork：479 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-01 21:48:28 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-02 02:14:19 | 组件总数：675 | 漏洞总数：83 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache Hadoop 信息泄露漏洞|密码学问题|[MPS-2012-2233](https://www.oscs1024.com/hd/MPS-2012-2233)|CVE-2012-3376|高危|
|Apache Hadoop 后置链接漏洞|未授权敏感信息泄露|[MPS-2014-7381](https://www.oscs1024.com/hd/MPS-2014-7381)|CVE-2014-3627|中危|
|Apache Hadoop 信息泄露漏洞|未授权敏感信息泄露|[MPS-2016-1783](https://www.oscs1024.com/hd/MPS-2016-1783)|CVE-2015-1776|中危|
|Eclipse Jetty 信息泄露漏洞|未授权敏感信息泄露|[MPS-2016-5010](https://www.oscs1024.com/hd/MPS-2016-5010)|CVE-2015-2080|高危|
|Square OkHttp 安全漏洞|证书验证不恰当|[MPS-2017-1023](https://www.oscs1024.com/hd/MPS-2017-1023)|CVE-2016-2402|中危|
|Google protobuf 缓冲区错误漏洞|越界写入|[MPS-2017-10841](https://www.oscs1024.com/hd/MPS-2017-10841)|CVE-2015-5237|高危|
|Apache Zookeeper 安全漏洞||[MPS-2017-11297](https://www.oscs1024.com/hd/MPS-2017-11297)|CVE-2017-5637|高危|
|Netty和Play Framework 输入验证错误漏洞|未授权敏感信息泄露|[MPS-2017-11682](https://www.oscs1024.com/hd/MPS-2017-11682)|CVE-2015-2156|高危|
|Apache Hadoop 跨站脚本漏洞|XSS|[MPS-2017-4858](https://www.oscs1024.com/hd/MPS-2017-4858)|CVE-2017-3161|中危|
|Apache Hadoop 输入验证错误漏洞|输入验证不恰当|[MPS-2017-4859](https://www.oscs1024.com/hd/MPS-2017-4859)|CVE-2017-3162|高危|
|Apache Tomcat SecurityManager绕过漏洞|访问控制不当|[MPS-2017-9011](https://www.oscs1024.com/hd/MPS-2017-9011)|CVE-2016-5018|严重|
|Apache Tomcat 访问限制绕过漏洞|访问控制不当|[MPS-2017-9027](https://www.oscs1024.com/hd/MPS-2017-9027)|CVE-2016-6796|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不可达退出条件的循环（无限循环）|[MPS-2018-11233](https://www.oscs1024.com/hd/MPS-2018-11233)|CVE-2018-11771|中危|
|Apache Spark 授权问题漏洞|代码注入|[MPS-2018-14969](https://www.oscs1024.com/hd/MPS-2018-14969)|CVE-2018-17190|严重|
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|Apache Derby 权限许可和访问控制问题漏洞|访问控制不当|[MPS-2018-5754](https://www.oscs1024.com/hd/MPS-2018-5754)|CVE-2018-1313|中危|
|Apache Zookeeper 访问控制错误漏洞|授权检查缺失|[MPS-2018-6313](https://www.oscs1024.com/hd/MPS-2018-6313)|CVE-2018-8012|高危|
|Apache Thrift <0.12.0 绕过验证漏洞|证书验证不恰当|[MPS-2019-0104](https://www.oscs1024.com/hd/MPS-2019-0104)|CVE-2018-1320|高危|
|Apache Commons Beanutils 存在不可信数据的反序列化漏洞|反序列化|[MPS-2019-10233](https://www.oscs1024.com/hd/MPS-2019-10233)|CVE-2019-10086|高危|
|Netty 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2019-12064](https://www.oscs1024.com/hd/MPS-2019-12064)|CVE-2019-16869|高危|
|Red Hat JBoss Enterprise Application Platform 代码问题漏洞|反序列化|[MPS-2019-12470](https://www.oscs1024.com/hd/MPS-2019-12470)|CVE-2019-10202|严重|
|Connect2id Nimbus JOSE+JWT 存在对异常或异常情况的不当检查漏洞|对异常条件的处理不恰当|[MPS-2019-13154](https://www.oscs1024.com/hd/MPS-2019-13154)|CVE-2019-17195|中危|
|Apache Hadoop 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2019-1459](https://www.oscs1024.com/hd/MPS-2019-1459)|CVE-2018-1296|高危|
|jackson-mapper-asl <=1.9.13 XXE 注入漏洞|XXE|[MPS-2019-15048](https://www.oscs1024.com/hd/MPS-2019-15048)|CVE-2019-10172|高危|
|Apache Zookeeper 授权问题漏洞|授权检查缺失|[MPS-2019-5668](https://www.oscs1024.com/hd/MPS-2019-5668)|CVE-2019-0201|中危|
|Apache Hadoop授权问题漏洞|身份验证不当|[MPS-2020-13793](https://www.oscs1024.com/hd/MPS-2020-13793)|CVE-2018-11765|中危|
|Apache HttpClient URI解析错误漏洞|XSS|[MPS-2020-17341](https://www.oscs1024.com/hd/MPS-2020-17341)|CVE-2020-13956|中危|
|FasterXML jackson-databind 代码问题漏洞|XXE|[MPS-2020-17358](https://www.oscs1024.com/hd/MPS-2020-17358)|CVE-2020-25649|高危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Apache Commons Compress 安存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10550](https://www.oscs1024.com/hd/MPS-2021-10550)|CVE-2021-35517|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10564](https://www.oscs1024.com/hd/MPS-2021-10564)|CVE-2021-36090|高危|
|Apache Hadoop 权限管理不当漏洞|授权检查错误|[MPS-2021-1705](https://www.oscs1024.com/hd/MPS-2021-1705)|CVE-2020-9492|高危|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|Apache Commons Net <3.9.0 存在FTP跳转攻击漏洞|未授权敏感信息泄露|[MPS-2021-28440](https://www.oscs1024.com/hd/MPS-2021-28440)|CVE-2021-37533|中危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|Eclipse Jersey 本地信息泄露漏洞|将资源暴露给错误范围|[MPS-2021-5218](https://www.oscs1024.com/hd/MPS-2021-5218)|CVE-2021-28168|中危|
|JDOM 存在 XXE 注入漏洞|XXE|[MPS-2021-8350](https://www.oscs1024.com/hd/MPS-2021-8350)|CVE-2021-33813|高危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9827](https://www.oscs1024.com/hd/MPS-2021-9827)|CVE-2021-36373|中危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9847](https://www.oscs1024.com/hd/MPS-2021-9847)|CVE-2021-36374|中危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|org.glassfish.jersey.media:jersey-media-jaxb <2.31 存在XXE漏洞|XML实体扩展|[MPS-2022-12234](https://www.oscs1024.com/hd/MPS-2022-12234)||高危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|Apache HttpClient URI解析错误漏洞|相对路径遍历|[MPS-2022-12292](https://www.oscs1024.com/hd/MPS-2022-12292)||中危|
|Apache Hadoop < 2.7.3 存在CSRF漏洞|CSRF|[MPS-2022-12308](https://www.oscs1024.com/hd/MPS-2022-12308)||中危|
|org.apache.hadoop:hadoop-hdfs < 3.3.2 存在XXE漏洞|XXE|[MPS-2022-12474](https://www.oscs1024.com/hd/MPS-2022-12474)||中危|
|org.apache.hadoop:hadoop-hdfs 存在信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-12484](https://www.oscs1024.com/hd/MPS-2022-12484)||高危|
|FasterXML Jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2022-12500](https://www.oscs1024.com/hd/MPS-2022-12500)||中危|
|org.apache.spark:spark-core_2.12 存在命令注入漏洞|命令注入|[MPS-2022-13519](https://www.oscs1024.com/hd/MPS-2022-13519)||高危|
|Apache Spark XSS 漏洞|XSS|[MPS-2022-16687](https://www.oscs1024.com/hd/MPS-2022-16687)|CVE-2022-31777|中危|
|Apache XercesJ <=2.12.1 存在XML注入漏洞|XPath盲注|[MPS-2022-1864](https://www.oscs1024.com/hd/MPS-2022-1864)|CVE-2022-23437|中危|
|Netty 存在信息泄露漏洞||[MPS-2022-3790](https://www.oscs1024.com/hd/MPS-2022-3790)|CVE-2022-24823|中危|
|Apache Hadoop 存在shell命令注入漏洞|参数注入或修改|[MPS-2022-4190](https://www.oscs1024.com/hd/MPS-2022-4190)|CVE-2022-25168|严重|
|Apache Ivy <2.5.1 路径穿越漏洞|路径遍历|[MPS-2022-53784](https://www.oscs1024.com/hd/MPS-2022-53784)|CVE-2022-37865|中危|
|Apache Ivy <2.5.1 路径遍历漏洞|路径遍历|[MPS-2022-53785](https://www.oscs1024.com/hd/MPS-2022-53785)|CVE-2022-37866|中危|
|XStream 缓冲区错误漏洞|输入验证不恰当|[MPS-2022-57061](https://www.oscs1024.com/hd/MPS-2022-57061)|CVE-2022-40156|低危|
|xstream project跨界内存写漏洞|跨界内存写|[MPS-2022-57062](https://www.oscs1024.com/hd/MPS-2022-57062)|CVE-2022-40155|高危|
|xstream project跨界内存写漏洞|跨界内存写|[MPS-2022-57063](https://www.oscs1024.com/hd/MPS-2022-57063)|CVE-2022-40154|高危|
|XStream 缓冲区错误漏洞|越界写入|[MPS-2022-57065](https://www.oscs1024.com/hd/MPS-2022-57065)|CVE-2022-40152|高危|
|Jettison <1.5.2 拒绝服务漏洞|拒绝服务|[MPS-2022-57067](https://www.oscs1024.com/hd/MPS-2022-57067)|CVE-2022-40150|高危|
|Jettison <1.5.1 拒绝服务漏洞|越界写入|[MPS-2022-57068](https://www.oscs1024.com/hd/MPS-2022-57068)|CVE-2022-40149|高危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|Apache Hadoop 存在路径遍历漏洞|路径遍历|[MPS-2022-5920](https://www.oscs1024.com/hd/MPS-2022-5920)|CVE-2022-26612|严重|
|Apache Commons Text <1.10.0 远程代码执行漏洞|反序列化|[MPS-2022-59712](https://www.oscs1024.com/hd/MPS-2022-59712)|CVE-2022-42889|严重|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|Jettison <1.5.2 拒绝服务漏洞|越界写入|[MPS-2022-64973](https://www.oscs1024.com/hd/MPS-2022-64973)|CVE-2022-45685|高危|
|Apache Ivy<2.5.2 存在XXE漏洞|输入验证不恰当|[MPS-2022-67125](https://www.oscs1024.com/hd/MPS-2022-67125)|CVE-2022-46751|中危|
|Spark 存在shell命令注入漏洞|OS命令注入|[MPS-2022-6786](https://www.oscs1024.com/hd/MPS-2022-6786)||严重|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Apache Spark 权限提升漏洞|权限管理不当|[MPS-2023-0818](https://www.oscs1024.com/hd/MPS-2023-0818)|CVE-2023-22946|高危|
|java-xmlbuilder 代码问题漏洞|XXE|[MPS-2023-5040](https://www.oscs1024.com/hd/MPS-2023-5040)|CVE-2014-125087|严重|
|Jettison 安全漏洞|未经控制的递归|[MPS-2023-8270](https://www.oscs1024.com/hd/MPS-2023-8270)|CVE-2023-1436|高危|
|jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2023-8438](https://www.oscs1024.com/hd/MPS-2023-8438)|CVE-2021-46877|中危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Apache Spark UI shell 命令注入漏洞|OS命令注入|[MPS-je1w-3xtr](https://www.oscs1024.com/hd/MPS-je1w-3xtr)|CVE-2023-32007|高危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.eclipse.jetty.aggregate:jetty-all|7.6.0.v20120127|9.2.9.v20150224|间接依赖|强烈建议修复|C:0|H:1|M:0|L:0|
|org.apache.zookeeper:zookeeper|3.4.6|3.5.5|间接依赖|强烈建议修复|C:0|H:2|M:1|L:0|
|commons-beanutils:commons-beanutils|1.7.0|1.9.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.12.7|2.14.0-rc1|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|tomcat:jasper-runtime|5.5.23||间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.apache.commons:commons-text|1.6|1.10.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.codehaus.jettison:jettison|1.1|1.5.4|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|io.netty:netty|3.9.9.Final|3.10.3.Final|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.74.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.glassfish.jersey.media:jersey-media-jaxb|2.30|2.31|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13||间接依赖|建议修复|C:1|H:1|M:0|L:0|
|org.apache.spark:spark-core_2.11|2.4.8||间接依赖|建议修复|C:1|H:1|M:1|L:0|
|org.xerial.snappy:snappy-java|1.1.8.2|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|com.squareup.okio:okio|1.6.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.hadoop:hadoop-hdfs-client|3.2.0|3.2.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.hadoop:hadoop-common|2.8.5|3.3.3|直接依赖|建议修复|C:2|H:0|M:1|L:0|
|com.squareup.okhttp:okhttp|2.4.0|2.7.4|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.fasterxml.woodstox:woodstox-core|5.3.0|6.4.0|间接依赖|建议修复|C:0|H:3|M:0|L:1|
|com.jamesmurty.utils:java-xmlbuilder|0.4|1.2|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.google.protobuf:protobuf-java|2.5.0|3.21.7|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.10.0|2.14.0-rc1|间接依赖|建议修复|C:0|H:2|M:5|L:0|
|com.nimbusds:nimbus-jose-jwt|4.41.1|7.8.1|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|io.netty:netty|3.7.0.Final|3.10.3.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.4.2|2.14.0-rc1|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.12.3|2.14.0-rc1|间接依赖|建议修复|C:0|H:1|M:5|L:0|
|org.apache.hadoop:hadoop-hdfs-client|2.8.5|3.2.2|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.glassfish.jersey.media:jersey-media-jaxb|2.22.2|2.31|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.spark:spark-core_2.12|3.1.3|3.4.0|间接依赖|建议修复|C:1|H:2|M:1|L:0|
|org.apache.spark:spark-core_2.12|3.2.2|3.4.0|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|org.apache.spark:spark-core_2.12|3.3.2|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty|3.6.2.Final|3.10.3.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|io.netty:netty-handler|4.1.87.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.14.2||间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.squareup.okio:okio|1.4.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.hadoop:hadoop-hdfs|2.6.5|3.3.2|间接依赖|建议修复|C:0|H:4|M:2|L:0|
|org.yaml:snakeyaml|1.33|2.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.xerial.snappy:snappy-java|1.1.8.3|1.1.10.1|直接依赖|建议修复|C:0|H:2|M:1|L:0|
|tomcat:jasper-compiler|5.5.23||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.google.guava:guava|11.0.2|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|commons-net:commons-net|3.1|3.9.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.jdom:jdom2|2.0.6|2.0.6.1|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.guava:guava|30.1.1-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.httpcomponents:httpclient|4.4.1|4.5.13|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|xerces:xercesImpl|2.9.1|2.12.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-common|4.1.74.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|14.0.1|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|org.apache.thrift:libthrift|0.9.3|0.12.0|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.hadoop:hadoop-yarn-common|2.5.1|2.7.3|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.apache.commons:commons-compress|1.4.1|1.21|间接依赖|可选修复|C:0|H:2|M:1|L:0|
|org.glassfish.jersey.core:jersey-common|2.30|3.0.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.hadoop:hadoop-mapreduce-client-app|2.6.5|2.7.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.hadoop:hadoop-yarn-common|2.6.5|2.7.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.code.gson:gson|2.2.4|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.guava:guava|27.0-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:1|
|org.apache.ivy:ivy|2.4.0|2.5.2|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|commons-codec:commons-codec|1.11|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|ant:ant|1.6.5|1.10.11|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.code.gson:gson|2.8.6|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.ivy:ivy|2.5.0|2.5.2|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|commons-io:commons-io|2.4|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-codec:commons-codec|1.9|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.apache.httpcomponents:httpclient|4.5.2|4.5.13|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.apache.ivy:ivy|2.5.1|2.5.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.derby:derby|10.10.2.0|10.14.2.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-codec:commons-codec|1.4|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|18|Low|
|BSD-2-Clause|7|Low|
|Apache-2.0|533|Low|
|LGPL-2.1|5|Medium|
|EPL-1.0|2|Low|
|CDDL-1.0|2|Low|
|CDDL-1.1|9|Low|
|自定义许可证|51|Low|
|BSD-3-Clause|12|Low|
|EPL-2.0|36|Low|
|MPL-1.1|2|Low|
|GPL-2.0|2|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.checkerframework:checker-qual|3.19.0|间接依赖|maven|
|dnsjava:dnsjava|2.1.7|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-common|3.2.0|间接依赖|maven|
|org.apache.hadoop:hadoop-client|3.2.0|间接依赖|maven|
|org.codehaus.jackson:jackson-jaxrs|1.8.3|间接依赖|maven|
|org.wildfly.openssl:wildfly-openssl|1.0.7.Final|间接依赖|maven|
|org.apache.kerby:kerb-core|1.0.1|间接依赖|maven|
|junit:junit|4.13.2|间接依赖|maven|
|com.ning:compress-lzf|1.1|间接依赖|maven|
|com.google.guava:guava|27.0-jre|间接依赖|maven|
|javax.activation:activation|1.1.1|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.2.11|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.4.14|间接依赖|maven|
|io.netty:netty-all|4.1.87.Final|间接依赖|maven|
|org.tukaani:xz|1.9|间接依赖|maven|
|org.apache.hadoop:hadoop-common|2.8.5|直接依赖|maven|
|javax.transaction:jta|1.1|间接依赖|maven|
|org.apache.hadoop:hadoop-hdfs|2.6.5|间接依赖|maven|
|org.apache.yetus:audience-annotations|0.5.0|间接依赖|maven|
|org.apache.commons:commons-compress|1.22|间接依赖|maven|
|com.squareup.okio:okio|1.6.0|间接依赖|maven|
|com.ververica:frocksdbjni|6.20.3-ververica-2.0|直接依赖|maven|
|io.netty:netty-codec-socks|4.1.87.Final|间接依赖|maven|
|com.amazonaws:aws-java-sdk-kms|1.12.319|直接依赖|maven|
|org.apache.hive.shims:hive-shims-0.23|2.3.9|间接依赖|maven|
|org.apache.avro:avro|1.10.2|间接依赖|maven|
|org.datanucleus:datanucleus-rdbms|4.1.19|间接依赖|maven|
|org.glassfish.hk2:hk2-api|2.4.0-b34|间接依赖|maven|
|org.apache.hadoop:hadoop-aws|3.3.4|直接依赖|maven|
|org.apache.orc:orc-mapreduce|1.6.14|间接依赖|maven|
|com.tdunning:json|1.8|间接依赖|maven|
|org.apache.avro:avro-mapred|1.11.1|间接依赖|maven|
|org.apache.hive:hive-storage-api|2.7.2|间接依赖|maven|
|org.apache.parquet:parquet-common|1.12.3|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-scala_2.12|2.12.3|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-core|2.8.5|直接依赖|maven|
|org.apache.paimon:paimon-bundle|0.5-SNAPSHOT|直接依赖|maven|
|org.apache.parquet:parquet-column|1.12.2|间接依赖|maven|
|org.apache.spark:spark-launcher_2.12|3.3.2|间接依赖|maven|
|net.razorvine:pyrolite|4.30|间接依赖|maven|
|org.apache.xbean:xbean-asm9-shaded|4.22|间接依赖|maven|
|org.apache.spark:spark-kvstore_2.12|3.1.3|间接依赖|maven|
|net.minidev:accessors-smart|2.4.9|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-scala_2.12|2.10.0|间接依赖|maven|
|org.apache.hive:hive-metastore|2.3.9|直接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.3|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.4|间接依赖|maven|
|com.twitter:chill-java|0.10.0|间接依赖|maven|
|com.zaxxer:HikariCP|2.5.1|间接依赖|maven|
|org.tukaani:xz|1.8|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.12.7|间接依赖|maven|
|com.google.inject:guice|3.0|间接依赖|maven|
|org.opentest4j:opentest4j|1.2.0|间接依赖|maven|
|org.apache.arrow:arrow-memory-core|11.0.0|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|org.roaringbitmap:shims|0.9.38|间接依赖|maven|
|org.scala-lang:scala-reflect|2.11.12|间接依赖|maven|
|org.apache.curator:curator-framework|2.13.0|间接依赖|maven|
|com.amazonaws:aws-java-sdk-core|1.12.319|直接依赖|maven|
|org.apache.orc:orc-shims|1.5.13|间接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.87.Final|间接依赖|maven|
|com.google.crypto.tink:tink|1.6.0|间接依赖|maven|
|io.dropwizard.metrics:metrics-jvm|4.2.15|间接依赖|maven|
|org.codehaus.janino:commons-compiler|3.0.16|间接依赖|maven|
|org.roaringbitmap:RoaringBitmap|0.7.45|间接依赖|maven|
|org.apache.arrow:arrow-vector|2.0.0|间接依赖|maven|
|org.glassfish.hk2:hk2-api|2.6.1|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|2.8.5|间接依赖|maven|
|io.airlift:aircompressor|0.21|间接依赖|maven|
|org.apache.avro:avro-ipc|1.11.0|间接依赖|maven|
|org.apache.paimon:paimon-hive-catalog|0.5-SNAPSHOT|直接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.87.Final|间接依赖|maven|
|org.apache.spark:spark-kvstore_2.12|3.4.0|间接依赖|maven|
|org.jruby.joni:joni|2.1.2|间接依赖|maven|
|org.glassfish.hk2:hk2-locator|2.6.1|间接依赖|maven|
|commons-io:commons-io|2.7|直接依赖|maven|
|org.glassfish.jersey.core:jersey-common|2.30|间接依赖|maven|
|org.apache.paimon:paimon-codegen|0.5-SNAPSHOT|直接依赖|maven|
|org.roaringbitmap:shims|0.9.0|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-paranamer|2.10.0|间接依赖|maven|
|io.dropwizard.metrics:metrics-jmx|4.2.7|间接依赖|maven|
|org.checkerframework:checker-qual|3.8.0|间接依赖|maven|
|net.minidev:json-smart|2.4.9|间接依赖|maven|
|org.roaringbitmap:shims|0.9.25|间接依赖|maven|
|org.mortbay.jetty:jetty-util|6.1.26|间接依赖|maven|
|org.ini4j:ini4j|0.5.4|间接依赖|maven|
|org.apache.spark:spark-core_2.12|3.3.2|间接依赖|maven|
|com.google.code.gson:gson|2.8.6|间接依赖|maven|
|asm:asm-tree|3.1|间接依赖|maven|
|net.sf.py4j:py4j|0.10.9|间接依赖|maven|
|org.apache.zookeeper:zookeeper-jute|3.6.2|间接依赖|maven|
|org.antlr:antlr4-runtime|4.8|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.1|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-client|3.2.0|间接依赖|maven|
|commons-io:commons-io|2.4|间接依赖|maven|
|org.apache.xbean:xbean-asm6-shaded|4.10|直接依赖|maven|
|org.apache.spark:spark-core_2.12|3.2.2|间接依赖|maven|
|org.glassfish.jersey.bundles.repackaged:jersey-guava|2.22.2|间接依赖|maven|
|org.glassfish.jersey.inject:jersey-hk2|2.34|间接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|org.apache.parquet:parquet-common|1.10.1|间接依赖|maven|
|org.apache.paimon:paimon-shade-jackson-2|2.14.2-0.4.0-incubating|直接依赖|maven|
|org.apache.hadoop:hadoop-client-runtime|3.3.4|间接依赖|maven|
|commons-digester:commons-digester|1.8|间接依赖|maven|
|io.dropwizard.metrics:metrics-graphite|4.2.7|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.13|间接依赖|maven|
|org.apache.commons:commons-compress|1.4.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.14.2|间接依赖|maven|
|com.amazonaws:jmespath-java|1.12.319|间接依赖|maven|
|net.sf.py4j:py4j|0.10.9.7|间接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|4.41.1|间接依赖|maven|
|org.apache.parquet:parquet-hadoop|1.12.3|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.5.1|间接依赖|maven|
|software.amazon.ion:ion-java|1.0.2|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-core|2.6.5|间接依赖|maven|
|org.apache.spark:spark-tags_2.12|3.4.0|间接依赖|maven|
|org.apache.orc:orc-mapreduce|1.7.8|间接依赖|maven|
|org.apache.spark:spark-core_2.12|3.4.0|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.16|间接依赖|maven|
|com.github.joshelser:dropwizard-metrics-hadoop-metrics2-reporter|0.1.2|间接依赖|maven|
|org.slf4j:jul-to-slf4j|2.0.6|间接依赖|maven|
|org.apache.hadoop.thirdparty:hadoop-shaded-protobuf_3_7|1.1.1|间接依赖|maven|
|net.razorvine:pickle|1.3|间接依赖|maven|
|io.netty:netty-buffer|4.1.74.Final|间接依赖|maven|
|org.apache.orc:orc-core|1.7.8|间接依赖|maven|
|org.datanucleus:javax.jdo|3.2.0-m3|间接依赖|maven|
|org.apache.hadoop:hadoop-hdfs-client|3.2.0|间接依赖|maven|
|commons-cli:commons-cli|1.2|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.10|间接依赖|maven|
|com.github.luben:zstd-jni|1.4.4-3|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|2.0.6|间接依赖|maven|
|it.unimi.dsi:fastutil|8.5.12|直接依赖|maven|
|stax:stax-api|1.0.1|间接依赖|maven|
|org.javassist:javassist|3.18.1-GA|间接依赖|maven|
|commons-logging:commons-logging|1.1.3|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|4.2.15|间接依赖|maven|
|org.apache.twill:twill-zookeeper|0.6.0-incubating|间接依赖|maven|
|org.apache.paimon:paimon-s3-impl|0.5-SNAPSHOT|直接依赖|maven|
|jline:jline|2.12|间接依赖|maven|
|commons-dbcp:commons-dbcp|1.4|间接依赖|maven|
|org.roaringbitmap:RoaringBitmap|0.9.38|间接依赖|maven|
|org.apache.spark:spark-network-common_2.11|2.4.8|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.4.2|间接依赖|maven|
|com.twitter:chill_2.12|0.10.0|间接依赖|maven|
|com.amazonaws:aws-java-sdk-dynamodb|1.12.319|直接依赖|maven|
|org.codehaus.woodstox:stax2-api|4.2.1|间接依赖|maven|
|org.codehaus.janino:commons-compiler|3.1.9|间接依赖|maven|
|org.apache.hadoop:hadoop-client|2.6.5|间接依赖|maven|
|org.apache.spark:spark-network-shuffle_2.11|2.4.8|间接依赖|maven|
|org.apache.spark:spark-launcher_2.11|2.4.8|间接依赖|maven|
|com.carrotsearch:hppc|0.7.2|间接依赖|maven|
|org.json4s:json4s-scalap_2.12|3.7.0-M11|间接依赖|maven|
|org.apache.geronimo.specs:geronimo-annotation_1.0_spec|1.1.1|间接依赖|maven|
|org.apache.twill:twill-core|0.6.0-incubating|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-resourcemanager|2.7.2|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-app|2.6.5|间接依赖|maven|
|org.apache.spark:spark-network-common_2.12|3.4.0|间接依赖|maven|
|org.apache.arrow:arrow-format|2.0.0|间接依赖|maven|
|com.ning:compress-lzf|1.1.2|间接依赖|maven|
|org.apache.spark:spark-network-shuffle_2.12|3.4.0|间接依赖|maven|
|net.sf.py4j:py4j|0.10.9.5|间接依赖|maven|
|org.apache.hadoop:hadoop-auth|2.8.5|间接依赖|maven|
|org.apache.directory.api:api-asn1-api|1.0.0-M20|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-web-proxy|2.7.2|间接依赖|maven|
|org.apache.parquet:parquet-column|1.10.1|间接依赖|maven|
|com.twitter:chill_2.11|0.9.3|间接依赖|maven|
|org.apache.hadoop:hadoop-aliyun|3.3.4|直接依赖|maven|
|com.aliyun:aliyun-java-sdk-core|4.5.10|间接依赖|maven|
|io.netty:netty-transport|4.1.87.Final|间接依赖|maven|
|org.scala-lang.modules:scala-parser-combinators_2.11|1.1.0|间接依赖|maven|
|io.netty:netty-buffer|4.1.87.Final|间接依赖|maven|
|org.apache.curator:curator-framework|2.6.0|间接依赖|maven|
|org.apache.curator:curator-recipes|2.7.1|间接依赖|maven|
|com.github.docker-java:docker-java-transport|3.2.13|间接依赖|maven|
|org.apache.paimon:paimon-common|0.5-SNAPSHOT|直接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.17|间接依赖|maven|
|org.json4s:json4s-ast_2.12|3.7.0-M5|间接依赖|maven|
|org.apache.orc:orc-core|1.5.6|直接依赖|maven|
|org.apache.parquet:parquet-column|1.12.3|直接依赖|maven|
|org.apache.parquet:parquet-hadoop|1.10.1|间接依赖|maven|
|org.apache.spark:spark-unsafe_2.11|2.4.8|间接依赖|maven|
|commons-lang:commons-lang|2.6|间接依赖|maven|
|io.netty:netty-codec|4.1.74.Final|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|2.6.5|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|间接依赖|maven|
|org.apache.spark:spark-tags_2.12|3.3.2|间接依赖|maven|
|org.apache.spark:spark-network-shuffle_2.12|3.1.3|间接依赖|maven|
|org.glassfish.jersey.core:jersey-server|2.34|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.30|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|2.8.5|间接依赖|maven|
|org.apache.hive:hive-common|2.3.9|间接依赖|maven|
|com.squareup.okio:okio|1.4.0|间接依赖|maven|
|net.razorvine:pickle|1.2|间接依赖|maven|
|org.apache.parquet:parquet-avro|1.12.3|直接依赖|maven|
|com.squareup.okhttp:okhttp|2.7.5|间接依赖|maven|
|io.dropwizard.metrics:metrics-json|4.2.15|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.9.5|间接依赖|maven|
|org.apache.avro:avro-mapred|1.8.2|间接依赖|maven|
|org.apache.paimon:paimon-shade-caffeine-2|2.9.3-0.4.0-incubating|直接依赖|maven|
|com.github.docker-java:docker-java-api|3.2.13|间接依赖|maven|
|org.apache.spark:spark-unsafe_2.12|3.1.3|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.0-4|间接依赖|maven|
|com.esotericsoftware:minlog|1.3.0|间接依赖|maven|
|org.antlr:antlr-runtime|3.5.2|间接依赖|maven|
|com.twitter:chill-java|0.9.3|间接依赖|maven|
|org.jacoco:org.jacoco.agent|0.8.5|间接依赖|maven|
|org.apache.curator:curator-recipes|2.13.0|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.2|间接依赖|maven|
|org.apache.spark:spark-sketch_2.12|3.4.0|间接依赖|maven|
|org.apache.paimon:paimon-hive-connector-common|0.5-SNAPSHOT|直接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet-core|2.34|间接依赖|maven|
|io.netty:netty-common|4.1.74.Final|间接依赖|maven|
|org.apache.kerby:kerby-asn1|1.0.1|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.74.Final|间接依赖|maven|
|org.apache.paimon:paimon-oss-impl|0.5-SNAPSHOT|直接依赖|maven|
|com.twitter:chill_2.12|0.9.5|间接依赖|maven|
|org.apache.arrow:arrow-memory-netty|2.0.0|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.2-5|间接依赖|maven|
|org.apache.directory.server:apacheds-i18n|2.0.0-M15|间接依赖|maven|
|xmlenc:xmlenc|0.52|间接依赖|maven|
|io.opentracing:opentracing-util|0.33.0|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|2.8.5|间接依赖|maven|
|org.apache.spark:spark-core_2.12|3.1.3|间接依赖|maven|
|org.scala-lang.modules:scala-xml_2.11|1.0.6|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet|2.30|间接依赖|maven|
|org.apache.spark:spark-network-common_2.12|3.3.2|间接依赖|maven|
|org.apache.orc:orc-shims|1.7.8|间接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|org.json4s:json4s-core_2.12|3.7.0-M5|间接依赖|maven|
|org.apache.spark:spark-tags_2.12|3.2.2|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|3.1.0|间接依赖|maven|
|org.apache.hbase:hbase-annotations|1.1.1|间接依赖|maven|
|org.scala-lang.modules:scala-parser-combinators_2.12|2.1.1|间接依赖|maven|
|io.dropwizard.metrics:metrics-json|3.1.5|间接依赖|maven|
|org.apache.hive.shims:hive-shims-scheduler|2.3.9|间接依赖|maven|
|io.dropwizard.metrics:metrics-jmx|4.2.0|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.1|间接依赖|maven|
|io.dropwizard.metrics:metrics-graphite|4.1.1|间接依赖|maven|
|io.netty:netty-codec-http|4.1.87.Final|间接依赖|maven|
|org.apache.commons:commons-text|1.10.0|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-scala_2.12|2.13.4|间接依赖|maven|
|org.apache.commons:commons-text|1.4|间接依赖|maven|
|org.apache.kerby:kerby-util|1.0.1|间接依赖|maven|
|org.glassfish.jersey.media:jersey-media-jaxb|2.30|间接依赖|maven|
|io.dropwizard.metrics:metrics-jvm|4.1.1|间接依赖|maven|
|org.apache.thrift:libfb303|0.9.3|间接依赖|maven|
|org.apache.parquet:parquet-format|2.4.0|间接依赖|maven|
|org.glassfish.jersey.core:jersey-client|2.36|间接依赖|maven|
|org.apache.spark:spark-tags_2.11|2.4.8|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.14.2|间接依赖|maven|
|com.github.stephenc.jcip:jcip-annotations|1.0-1|间接依赖|maven|
|org.apache.spark:spark-sql_2.12|3.1.3|直接依赖|maven|
|org.apache.arrow:arrow-vector|7.0.0|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.87.Final|间接依赖|maven|
|org.apache.orc:orc-shims|1.5.6|间接依赖|maven|
|io.dropwizard.metrics:metrics-jvm|4.2.7|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet-core|2.22.2|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-jobclient|2.6.5|间接依赖|maven|
|org.glassfish.jersey.core:jersey-server|2.30|间接依赖|maven|
|org.apache.twill:twill-discovery-core|0.6.0-incubating|间接依赖|maven|
|org.antlr:antlr4-runtime|4.8-1|间接依赖|maven|
|com.squareup.okhttp:okhttp|2.4.0|间接依赖|maven|
|commons-codec:commons-codec|1.11|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.87.Final|间接依赖|maven|
|org.apache.spark:spark-unsafe_2.12|3.2.2|间接依赖|maven|
|org.yaml:snakeyaml|1.33|间接依赖|maven|
|org.apache.hadoop:hadoop-client-api|3.3.1|间接依赖|maven|
|org.apache.zookeeper:zookeeper-jute|3.6.3|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.12.6|间接依赖|maven|
|org.roaringbitmap:shims|0.7.45|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.0-1|间接依赖|maven|
|org.eclipse.jetty.aggregate:jetty-all|7.6.0.v20120127|间接依赖|maven|
|com.univocity:univocity-parsers|2.7.3|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|2.6.5|间接依赖|maven|
|com.google.guava:failureaccess|1.0|间接依赖|maven|
|org.apache.paimon:paimon-spark-common|0.5-SNAPSHOT|直接依赖|maven|
|org.apache.commons:commons-configuration2|2.1.1|间接依赖|maven|
|org.apache.hadoop:hadoop-client-api|3.3.4|间接依赖|maven|
|javax.servlet:servlet-api|2.5|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.4|间接依赖|maven|
|org.apache.orc:orc-mapreduce|1.5.13|间接依赖|maven|
|io.netty:netty-all|4.1.74.Final|间接依赖|maven|
|com.jolbox:bonecp|0.8.0.RELEASE|间接依赖|maven|
|javolution:javolution|5.5.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.14.2|间接依赖|maven|
|org.antlr:antlr4-runtime|4.9.3|间接依赖|maven|
|org.apache.parquet:parquet-hadoop|1.12.2|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-common|2.6.5|间接依赖|maven|
|io.dropwizard.metrics:metrics-graphite|4.2.0|间接依赖|maven|
|org.apache.hive.shims:hive-shims-common|2.3.9|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|org.apache.spark:spark-sketch_2.12|3.2.2|间接依赖|maven|
|io.opentracing:opentracing-noop|0.33.0|间接依赖|maven|
|org.apache.arrow:arrow-vector|0.10.0|间接依赖|maven|
|org.apache.spark:spark-kvstore_2.11|2.4.8|间接依赖|maven|
|org.jetbrains:annotations|17.0.0|间接依赖|maven|
|org.scala-lang.modules:scala-parser-combinators_2.12|1.1.2|间接依赖|maven|
|org.apache.hadoop:hadoop-client-api|3.3.2|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.32|间接依赖|maven|
|org.apache.commons:commons-crypto|1.0.0|间接依赖|maven|
|org.apache.paimon:paimon-shade-guava-30|30.1.1-jre-0.4.0-incubating|直接依赖|maven|
|org.apache.arrow:arrow-memory-netty|11.0.0|间接依赖|maven|
|com.github.stephenc.findbugs:findbugs-annotations|1.3.9-1|间接依赖|maven|
|org.lz4:lz4-java|1.8.0|直接依赖|maven|
|org.threeten:threeten-extra|1.5.0|间接依赖|maven|
|io.netty:netty-resolver|4.1.87.Final|间接依赖|maven|
|org.apache.commons:commons-crypto|1.1.0|间接依赖|maven|
|io.opentracing:opentracing-api|0.33.0|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|3.3.4|间接依赖|maven|
|org.codehaus.jackson:jackson-xc|1.8.3|间接依赖|maven|
|org.objenesis:objenesis|2.5.1|间接依赖|maven|
|io.dropwizard.metrics:metrics-json|4.2.0|间接依赖|maven|
|commons-configuration:commons-configuration|1.6|间接依赖|maven|
|org.ow2.asm:asm|9.3|间接依赖|maven|
|org.glassfish.hk2:osgi-resource-locator|1.0.3|间接依赖|maven|
|org.apache.hadoop:hadoop-hdfs-client|2.8.5|直接依赖|maven|
|org.mortbay.jetty:jetty|6.1.26|间接依赖|maven|
|org.apache.spark:spark-core_2.11|2.4.8|间接依赖|maven|
|org.apache.hadoop:hadoop-annotations|2.6.5|间接依赖|maven|
|org.apache.htrace:htrace-core4|4.0.1-incubating|间接依赖|maven|
|org.apache.parquet:parquet-encoding|1.12.3|直接依赖|maven|
|com.google.flatbuffers:flatbuffers-java|1.9.0|间接依赖|maven|
|org.apache.twill:twill-common|0.6.0-incubating|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.87.Final|间接依赖|maven|
|org.json4s:json4s-ast_2.12|3.7.0-M11|间接依赖|maven|
|org.apiguardian:apiguardian-api|1.1.2|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.6.2|间接依赖|maven|
|com.univocity:univocity-parsers|2.9.1|间接依赖|maven|
|com.jamesmurty.utils:java-xmlbuilder|0.4|间接依赖|maven|
|org.apache.hadoop:hadoop-client-runtime|3.3.2|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.4.1|间接依赖|maven|
|org.apache.hbase:hbase-client|1.1.1|间接依赖|maven|
|org.apache.spark:spark-launcher_2.12|3.2.2|间接依赖|maven|
|org.glassfish.jersey.core:jersey-client|2.30|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.10.0|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|4.1.1|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|2.7.2|间接依赖|maven|
|org.apache.paimon:paimon-codegen-loader|0.5-SNAPSHOT|直接依赖|maven|
|org.datanucleus:datanucleus-api-jdo|4.2.4|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.2-1|间接依赖|maven|
|org.htrace:htrace-core|3.0.4|间接依赖|maven|
|tomcat:jasper-runtime|5.5.23|间接依赖|maven|
|io.dropwizard.metrics:metrics-graphite|3.1.5|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-scala_2.12|2.14.2|间接依赖|maven|
|io.dropwizard.metrics:metrics-jvm|3.1.5|间接依赖|maven|
|org.glassfish.hk2.external:javax.inject|2.4.0-b34|间接依赖|maven|
|org.apache.paimon:paimon-flink-action|0.5-SNAPSHOT|直接依赖|maven|
|io.netty:netty-all|4.1.68.Final|间接依赖|maven|
|org.codehaus.janino:janino|3.1.9|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet|2.34|间接依赖|maven|
|org.apache.spark:spark-network-common_2.12|3.1.3|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.32|间接依赖|maven|
|org.apache.commons:commons-lang3|3.5|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.9.5|间接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.17.1|直接依赖|maven|
|commons-pool:commons-pool|1.6|直接依赖|maven|
|commons-codec:commons-codec|1.4|间接依赖|maven|
|com.google.protobuf:protobuf-java|2.5.0|间接依赖|maven|
|io.netty:netty-transport|4.1.74.Final|间接依赖|maven|
|org.apache.parquet:parquet-jackson|1.10.1|间接依赖|maven|
|org.apache.logging.log4j:log4j-1.2-api|2.17.1|直接依赖|maven|
|org.apache.spark:spark-catalyst_2.12|3.4.0|间接依赖|maven|
|org.glassfish.jersey.inject:jersey-hk2|2.36|间接依赖|maven|
|org.apache.spark:spark-catalyst_2.12|3.2.2|间接依赖|maven|
|org.codehaus.janino:janino|3.0.11|直接依赖|maven|
|org.apache.hadoop:hadoop-annotations|3.2.0|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.9.3|间接依赖|maven|
|org.glassfish.hk2:hk2-utils|2.4.0-b34|间接依赖|maven|
|org.apache.avro:avro-mapred|1.10.2|间接依赖|maven|
|org.apache.hbase:hbase-protocol|1.1.1|间接依赖|maven|
|javax.transaction:transaction-api|1.1|间接依赖|maven|
|org.apache.parquet:parquet-encoding|1.10.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.10.0|间接依赖|maven|
|javax.servlet.jsp:jsp-api|2.1|间接依赖|maven|
|org.apache.spark:spark-catalyst_2.11|2.4.8|间接依赖|maven|
|org.apache.spark:spark-kvstore_2.12|3.2.2|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.1|直接依赖|maven|
|org.apache.parquet:parquet-encoding|1.12.2|间接依赖|maven|
|org.codehaus.jettison:jettison|1.1|间接依赖|maven|
|com.google.flatbuffers:flatbuffers-java|1.12.0|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet|2.36|间接依赖|maven|
|com.github.docker-java:docker-java-transport-zerodep|3.2.13|间接依赖|maven|
|org.apache.commons:commons-text|1.6|间接依赖|maven|
|org.apache.spark:spark-network-common_2.12|3.2.2|间接依赖|maven|
|org.hamcrest:hamcrest-core|1.3|间接依赖|maven|
|org.apache.hadoop:hadoop-common|3.3.4|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.1|间接依赖|maven|
|org.apache.parquet:parquet-jackson|1.12.2|间接依赖|maven|
|org.apache.derby:derby|10.10.2.0|间接依赖|maven|
|org.apache.hadoop:hadoop-client-runtime|3.3.1|间接依赖|maven|
|org.glassfish.jersey.core:jersey-common|2.22.2|间接依赖|maven|
|org.apache.hive:hive-serde|2.3.9|间接依赖|maven|
|com.sun.jersey:jersey-json|1.9|间接依赖|maven|
|org.rocksdb:rocksdbjni|7.9.2|间接依赖|maven|
|com.jayway.jsonpath:json-path|2.8.0|直接依赖|maven|
|org.apache.hive:hive-shims|2.3.9|间接依赖|maven|
|io.netty:netty-resolver|4.1.74.Final|间接依赖|maven|
|org.apache.spark:spark-sketch_2.12|3.3.2|间接依赖|maven|
|org.apache.kerby:kerby-pkix|1.0.1|间接依赖|maven|
|org.glassfish.hk2.external:aopalliance-repackaged|2.6.1|间接依赖|maven|
|net.java.dev.jets3t:jets3t|0.9.0|间接依赖|maven|
|org.apache.commons:commons-math3|3.4.1|间接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|asm:asm|3.1|间接依赖|maven|
|io.netty:netty|3.9.9.Final|间接依赖|maven|
|org.apache.paimon:paimon-hadoop-shaded|0.5-SNAPSHOT|直接依赖|maven|
|org.apache.avro:avro-ipc|1.8.2|间接依赖|maven|
|io.netty:netty-handler|4.1.87.Final|间接依赖|maven|
|org.apache.spark:spark-launcher_2.12|3.4.0|间接依赖|maven|
|com.google.code.gson:gson|2.2.4|间接依赖|maven|
|org.apache.orc:orc-shims|1.8.3|间接依赖|maven|
|commons-beanutils:commons-beanutils-core|1.8.0|间接依赖|maven|
|com.sun.xml.bind:jaxb-impl|2.2.3-1|间接依赖|maven|
|org.apache.commons:commons-math3|3.1.1|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|2.5.1|间接依赖|maven|
|org.datanucleus:datanucleus-core|4.1.17|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.12.3|间接依赖|maven|
|org.apache.spark:spark-unsafe_2.12|3.4.0|间接依赖|maven|
|org.roaringbitmap:RoaringBitmap|0.9.0|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-csv|2.14.2|间接依赖|maven|
|io.netty:netty-handler|4.1.74.Final|间接依赖|maven|
|com.sun.jersey:jersey-server|1.9|间接依赖|maven|
|org.codehaus.janino:commons-compiler|3.0.11|直接依赖|maven|
|org.apache.spark:spark-tags_2.12|3.1.3|间接依赖|maven|
|org.glassfish.jersey.core:jersey-common|2.36|间接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.74.Final|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.30|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-api|5.8.1|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet|2.22.2|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.2.2|间接依赖|maven|
|io.dropwizard.metrics:metrics-jmx|4.2.15|间接依赖|maven|
|commons-cli:commons-cli|1.3.1|直接依赖|maven|
|org.glassfish.jersey.core:jersey-server|2.22.2|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.7.0|间接依赖|maven|
|org.apache.avro:avro|1.11.0|间接依赖|maven|
|io.netty:netty|3.6.2.Final|间接依赖|maven|
|com.google.guava:guava|11.0.2|间接依赖|maven|
|com.ning:compress-lzf|1.0.3|间接依赖|maven|
|org.apache.arrow:arrow-memory-core|7.0.0|间接依赖|maven|
|org.apache.spark:spark-catalyst_2.12|3.1.3|间接依赖|maven|
|jakarta.ws.rs:jakarta.ws.rs-api|2.1.6|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|3.1.5|间接依赖|maven|
|org.glassfish.jersey.media:jersey-media-jaxb|2.22.2|间接依赖|maven|
|org.apache.arrow:arrow-format|7.0.0|间接依赖|maven|
|javax.xml.stream:stax-api|1.0-2|间接依赖|maven|
|org.apache.curator:curator-client|2.7.1|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|4.2.7|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.10.0|间接依赖|maven|
|org.scala-lang:scala-reflect|2.12.15|直接依赖|maven|
|com.aliyun:aliyun-java-sdk-ram|3.1.0|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-applicationhistoryservice|2.7.2|间接依赖|maven|
|commons-pool:commons-pool|1.5.4|间接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.8|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.21.12|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.87.Final|间接依赖|maven|
|io.dropwizard.metrics:metrics-jvm|4.2.0|间接依赖|maven|
|org.glassfish.jersey.core:jersey-client|2.34|间接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j2-impl|2.19.0|间接依赖|maven|
|org.checkerframework:checker-qual|2.5.2|间接依赖|maven|
|com.google.crypto.tink:tink|1.6.1|间接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j-impl|2.17.1|直接依赖|maven|
|org.apache.logging.log4j:log4j-web|2.6.2|间接依赖|maven|
|org.apache.thrift:libthrift|0.9.3|间接依赖|maven|
|org.apache.avro:avro-ipc|1.10.2|间接依赖|maven|
|com.vlkan:flatbuffers|1.2.0-3f79e055|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-api|3.2.0|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.4|间接依赖|maven|
|org.apache.commons:commons-collections4|4.4|间接依赖|maven|
|org.apache.paimon:paimon-core|0.5-SNAPSHOT|直接依赖|maven|
|io.dropwizard.metrics:metrics-json|4.1.1|间接依赖|maven|
|io.dropwizard.metrics:metrics-jvm|3.1.0|间接依赖|maven|
|ant:ant|1.6.5|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-engine|5.8.1|间接依赖|maven|
|org.apache.spark:spark-sketch_2.11|2.4.8|间接依赖|maven|
|com.sun.jersey.contribs:jersey-guice|1.9|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.6.3|间接依赖|maven|
|org.glassfish.jersey.core:jersey-client|2.22.2|间接依赖|maven|
|javax.ws.rs:javax.ws.rs-api|2.0.1|间接依赖|maven|
|org.apache.htrace:htrace-core|3.1.0-incubating|间接依赖|maven|
|org.apache.spark:spark-sql_2.12|3.2.2|直接依赖|maven|
|org.apache.spark:spark-unsafe_2.12|3.3.2|间接依赖|maven|
|com.google.guava:guava|14.0.1|间接依赖|maven|
|io.airlift:aircompressor|0.10|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|3.2.0|间接依赖|maven|
|org.javassist:javassist|3.25.0-GA|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-kms|2.11.0|间接依赖|maven|
|org.apache.orc:orc-shims|1.6.14|间接依赖|maven|
|org.apache.spark:spark-catalyst_2.12|3.3.2|间接依赖|maven|
|org.glassfish.jersey.core:jersey-server|2.36|间接依赖|maven|
|org.json4s:json4s-scalap_2.11|3.5.3|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.12.7|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-core|3.2.0|间接依赖|maven|
|co.cask.tephra:tephra-core|0.6.0|间接依赖|maven|
|org.apache.orc:orc-core|1.8.3|间接依赖|maven|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.12.3|间接依赖|maven|
|org.apache.spark:spark-sql_2.11|2.4.8|直接依赖|maven|
|org.fusesource.leveldbjni:leveldbjni-all|1.8|间接依赖|maven|
|com.sun.jersey:jersey-core|1.9|间接依赖|maven|
|io.dropwizard.metrics:metrics-jmx|4.1.1|间接依赖|maven|
|org.apache.spark:spark-network-shuffle_2.12|3.3.2|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|org.json4s:json4s-jackson_2.12|3.7.0-M5|间接依赖|maven|
|xerces:xercesImpl|2.9.1|间接依赖|maven|
|org.mortbay.jetty:jetty-sslengine|6.1.26|间接依赖|maven|
|joda-time:joda-time|2.8.1|间接依赖|maven|
|org.codehaus.janino:janino|3.0.16|间接依赖|maven|
|org.assertj:assertj-core|3.23.1|直接依赖|maven|
|org.apache.paimon:paimon-hive-common|0.5-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.14.2|间接依赖|maven|
|com.google.code.findbugs:jsr305|1.3.9|直接依赖|maven|
|org.glassfish.jersey.inject:jersey-hk2|2.30|间接依赖|maven|
|org.apache.yetus:audience-annotations|0.13.0|间接依赖|maven|
|javax.activation:activation|1.1|间接依赖|maven|
|io.dropwizard.metrics:metrics-json|4.2.7|间接依赖|maven|
|net.java.dev.jna:jna|5.8.0|间接依赖|maven|
|org.apache.arrow:arrow-memory|0.10.0|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-common|2.7.2|间接依赖|maven|
|org.tukaani:xz|1.0|间接依赖|maven|
|tomcat:jasper-compiler|5.5.23|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.16|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.9.5|间接依赖|maven|
|com.sun.jersey:jersey-client|1.9|间接依赖|maven|
|org.apache.paimon:paimon-spark-3.2|0.5-SNAPSHOT|直接依赖|maven|
|co.cask.tephra:tephra-hbase-compat-1.0|0.6.0|间接依赖|maven|
|xml-apis:xml-apis|1.3.04|间接依赖|maven|
|org.json4s:json4s-scalap_2.12|3.7.0-M5|间接依赖|maven|
|org.apache.parquet:parquet-jackson|1.12.3|直接依赖|maven|
|org.apache.ivy:ivy|2.5.1|间接依赖|maven|
|commons-net:commons-net|3.1|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.2|间接依赖|maven|
|com.aliyun.oss:aliyun-sdk-oss|3.13.2|直接依赖|maven|
|net.sf.py4j:py4j|0.10.7|间接依赖|maven|
|org.apache.twill:twill-api|0.6.0-incubating|间接依赖|maven|
|org.threeten:threeten-extra|1.7.1|间接依赖|maven|
|org.apache.paimon:paimon-flink-common|0.5-SNAPSHOT|直接依赖|maven|
|org.apache.spark:spark-sql_2.12|3.3.2|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-common|2.6.5|间接依赖|maven|
|org.apache.arrow:arrow-memory-netty|7.0.0|间接依赖|maven|
|io.netty:netty-all|4.1.47.Final|间接依赖|maven|
|commons-io:commons-io|2.11.0|间接依赖|maven|
|org.apache.paimon:paimon-flink-1.17|0.5-SNAPSHOT|直接依赖|maven|
|com.github.luben:zstd-jni|1.4.8-1|间接依赖|maven|
|org.apache.commons:commons-lang3|3.10|间接依赖|maven|
|javax.servlet:javax.servlet-api|3.1.0|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.74.Final|间接依赖|maven|
|org.glassfish.hk2:hk2-utils|2.6.1|间接依赖|maven|
|org.apache.parquet:parquet-hadoop-bundle|1.8.1|间接依赖|maven|
|org.apache.directory.server:apacheds-kerberos-codec|2.0.0-M15|间接依赖|maven|
|org.junit.platform:junit-platform-engine|1.8.1|间接依赖|maven|
|com.amazonaws:aws-java-sdk-s3|1.12.319|直接依赖|maven|
|org.apache.zookeeper:zookeeper|3.4.6|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-client|2.6.5|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet-core|2.36|间接依赖|maven|
|com.google.crypto.tink:tink|1.7.0|间接依赖|maven|
|org.scala-lang:scala-library|2.12.15|直接依赖|maven|
|org.apache.xbean:xbean-asm9-shaded|4.20|间接依赖|maven|
|com.amazonaws:aws-java-sdk-sts|1.12.319|直接依赖|maven|
|org.apache.avro:avro-ipc|1.11.1|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.74.Final|间接依赖|maven|
|org.apache.xbean:xbean-asm7-shaded|4.15|间接依赖|maven|
|org.testcontainers:testcontainers|1.17.2|直接依赖|maven|
|org.apache.hive:hive-storage-api|2.8.1|间接依赖|maven|
|org.apache.hadoop.thirdparty:hadoop-shaded-guava|1.1.1|间接依赖|maven|
|javax.mail:mail|1.4.1|间接依赖|maven|
|org.apache.hive:hive-service-rpc|2.3.9|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|com.jcraft:jsch|0.1.54|间接依赖|maven|
|org.apache.parquet:parquet-common|1.12.2|间接依赖|maven|
|org.apache.spark:spark-network-shuffle_2.12|3.2.2|间接依赖|maven|
|org.apache.twill:twill-discovery-api|0.6.0-incubating|间接依赖|maven|
|org.scala-lang:scala-compiler|2.12.15|直接依赖|maven|
|com.clearspring.analytics:stream|2.7.0|间接依赖|maven|
|org.eclipse.jetty.orbit:javax.servlet|3.0.0.v201112011016|间接依赖|maven|
|org.apache.paimon:paimon-format|0.5-SNAPSHOT|直接依赖|maven|
|org.apache.avro:avro|1.11.1|直接依赖|maven|
|org.apache.spark:spark-sketch_2.12|3.1.3|间接依赖|maven|
|co.cask.tephra:tephra-api|0.6.0|间接依赖|maven|
|io.netty:netty-codec|4.1.87.Final|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-params|5.8.1|间接依赖|maven|
|asm:asm-commons|3.1|间接依赖|maven|
|org.rnorth.duct-tape:duct-tape|1.0.8|间接依赖|maven|
|commons-io:commons-io|2.8.0|间接依赖|maven|
|org.apache.parquet:parquet-format-structures|1.12.2|间接依赖|maven|
|javax.servlet:jsp-api|2.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.12.3|间接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|org.json4s:json4s-ast_2.11|3.5.3|间接依赖|maven|
|com.google.guava:guava|30.1.1-jre|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|io.netty:netty-tcnative-classes|2.0.48.Final|间接依赖|maven|
|org.glassfish.hk2.external:jakarta.inject|2.6.1|间接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|5.3.0|间接依赖|maven|
|org.glassfish.hk2:hk2-locator|2.4.0-b34|间接依赖|maven|
|org.apache.orc:orc-core|1.5.5|间接依赖|maven|
|org.apache.parquet:parquet-format-structures|1.12.3|直接依赖|maven|
|com.clearspring.analytics:stream|2.9.6|间接依赖|maven|
|org.json4s:json4s-jackson_2.11|3.5.3|间接依赖|maven|
|commons-el:commons-el|1.0|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.14.2|间接依赖|maven|
|org.roaringbitmap:RoaringBitmap|0.9.25|间接依赖|maven|
|org.junit.jupiter:junit-jupiter|5.8.1|直接依赖|maven|
|io.dropwizard.metrics:metrics-core|4.2.0|间接依赖|maven|
|org.apache.arrow:arrow-memory-core|2.0.0|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.74.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.10.3|间接依赖|maven|
|com.google.re2j:re2j|1.1|间接依赖|maven|
|javax.jdo:jdo-api|3.0.1|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.32|直接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-core|2.5.1|间接依赖|maven|
|org.apache.orc:orc-core|1.6.14|间接依赖|maven|
|io.dropwizard.metrics:metrics-json|3.1.0|间接依赖|maven|
|org.apache.avro:avro-mapred|1.11.0|间接依赖|maven|
|org.jdom:jdom2|2.0.6|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.87.Final|间接依赖|maven|
|org.json4s:json4s-core_2.12|3.7.0-M11|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet-core|2.30|间接依赖|maven|
|org.apache.hbase:hbase-common|1.1.1|间接依赖|maven|
|org.apache.htrace:htrace-core4|4.1.0-incubating|间接依赖|maven|
|org.glassfish.hk2.external:aopalliance-repackaged|2.4.0-b34|间接依赖|maven|
|org.jruby.jcodings:jcodings|1.0.8|间接依赖|maven|
|org.apache.orc:orc-core|1.5.13|间接依赖|maven|
|com.google.inject.extensions:guice-assistedinject|3.0|间接依赖|maven|
|org.json4s:json4s-core_2.11|3.5.3|间接依赖|maven|
|net.razorvine:pyrolite|4.13|间接依赖|maven|
|org.apache.ivy:ivy|2.4.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.12.7|间接依赖|maven|
|org.apache.commons:commons-math3|3.6.1|直接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-jobclient|3.2.0|间接依赖|maven|
|org.apache.orc:orc-mapreduce|1.8.3|间接依赖|maven|
|org.apache.ivy:ivy|2.5.0|间接依赖|maven|
|commons-codec:commons-codec|1.9|间接依赖|maven|
|org.spark-project.spark:unused|1.0.0|间接依赖|maven|
|oro:oro|2.0.8|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|直接依赖|maven|
|org.apache.arrow:arrow-format|0.10.0|间接依赖|maven|
|io.dropwizard.metrics:metrics-graphite|4.2.15|间接依赖|maven|
|org.apache.spark:spark-launcher_2.12|3.1.3|间接依赖|maven|
|org.antlr:antlr4-runtime|4.7|直接依赖|maven|
|org.apache.directory.api:api-util|1.0.0-M20|间接依赖|maven|
|io.netty:netty|3.7.0.Final|间接依赖|maven|
|org.apache.spark:spark-sql_2.12|3.4.0|直接依赖|maven|
|org.apache.arrow:arrow-vector|11.0.0|间接依赖|maven|
|org.apache.curator:curator-recipes|2.6.0|间接依赖|maven|
|org.apache.hive:hive-storage-api|2.6.0|间接依赖|maven|
|org.apache.geronimo.specs:geronimo-jta_1.1_spec|1.1.1|间接依赖|maven|
|org.glassfish.hk2:osgi-resource-locator|1.0.1|间接依赖|maven|
|org.apache.orc:orc-mapreduce|1.5.5|间接依赖|maven|
|org.junit.vintage:junit-vintage-engine|5.8.1|直接依赖|maven|
|org.junit.platform:junit-platform-commons|1.8.1|间接依赖|maven|
|org.rocksdb:rocksdbjni|6.20.3|间接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-client-shuffle|2.6.5|间接依赖|maven|
|io.netty:netty-all|4.1.51.Final|间接依赖|maven|
|javax.validation:validation-api|1.1.0.Final|间接依赖|maven|
|jakarta.servlet:jakarta.servlet-api|4.0.3|间接依赖|maven|
|org.apache.geronimo.specs:geronimo-jaspic_1.0_spec|1.0|间接依赖|maven|
|org.apache.commons:commons-compress|1.21|间接依赖|maven|
|org.apache.arrow:arrow-format|11.0.0|间接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.9.13|间接依赖|maven|
|net.sf.opencsv:opencsv|2.3|间接依赖|maven|
|com.google.inject.extensions:guice-servlet|3.0|间接依赖|maven|
|org.apache.spark:spark-kvstore_2.12|3.3.2|间接依赖|maven|
|io.netty:netty-common|4.1.87.Final|间接依赖|maven|
|org.json4s:json4s-jackson_2.12|3.7.0-M11|间接依赖|maven|
|org.glassfish.jersey.core:jersey-common|2.34|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.14.2|间接依赖|maven|
|org.scala-lang.modules:scala-xml_2.12|1.0.6|间接依赖|maven|
|com.esotericsoftware:kryo-shaded|4.0.2|间接依赖|maven|
|org.apache.curator:curator-framework|2.7.1|间接依赖|maven|
|com.twitter:chill-java|0.9.5|间接依赖|maven|
|org.apache.orc:orc-shims|1.5.5|间接依赖|maven|
|org.apache.hadoop:hadoop-auth|3.3.4|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)