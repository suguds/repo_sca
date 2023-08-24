# DataDog/dd-trace-java安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694772360195694592.svg)](https://www.murphysec.com/console/report/1694772360157945856/1694772360195694592)

仓库描述：Datadog APM client for Java

仓库地址：[https://github.com/DataDog/dd-trace-java](https://github.com/DataDog/dd-trace-java)

| star：472 | watch：540 | fork：261 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-25 00:49:31 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-25 03:39:32 | 组件总数：198 | 漏洞总数：74 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|SnakeYAML <1.26 存在 Billion laughs 漏洞|拒绝服务|[MPS-2019-16129](https://www.oscs1024.com/hd/MPS-2019-16129)|CVE-2017-18640|高危|
|Apache Log4j SocketServer反序列化漏洞|反序列化|[MPS-2019-17271](https://www.oscs1024.com/hd/MPS-2019-17271)|CVE-2019-17571|严重|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|Pivotal Spring Framework 反射文件下载 (RFD) 漏洞|路径遍历|[MPS-2020-13322](https://www.oscs1024.com/hd/MPS-2020-13322)|CVE-2020-5421|中危|
|Apache Tomcat HTTP请求走私漏洞|HTTP请求走私|[MPS-2020-15344](https://www.oscs1024.com/hd/MPS-2020-15344)|CVE-2020-13943|中危|
|FasterXML jackson-databind 代码问题漏洞|XXE|[MPS-2020-17358](https://www.oscs1024.com/hd/MPS-2020-17358)|CVE-2020-25649|高危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2020-17486](https://www.oscs1024.com/hd/MPS-2020-17486)|CVE-2020-17527|高危|
|Apache Log4j2 SmtpAppender证书验证不当漏洞|证书验证不恰当|[MPS-2020-6684](https://www.oscs1024.com/hd/MPS-2020-6684)|CVE-2020-9488|低危|
|Apache Tomcat 远程代码执行漏洞|反序列化|[MPS-2020-7626](https://www.oscs1024.com/hd/MPS-2020-7626)|CVE-2020-9484|高危|
|Apache Tomcat 拒绝服务漏洞|拒绝服务|[MPS-2020-9541](https://www.oscs1024.com/hd/MPS-2020-9541)|CVE-2020-11996|高危|
|Apache Tomcat 授权问题漏洞|身份验证不当|[MPS-2021-10264](https://www.oscs1024.com/hd/MPS-2021-10264)|CVE-2021-30640|中危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-1722](https://www.oscs1024.com/hd/MPS-2021-1722)|CVE-2021-24122|中危|
|Spring Framework <5.3.14 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18854](https://www.oscs1024.com/hd/MPS-2021-18854)|CVE-2021-22060|中危|
|Pivotal Spring Framework 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18890](https://www.oscs1024.com/hd/MPS-2021-18890)|CVE-2021-22096|中危|
|Apache Tomcat 信息泄露漏洞|HTTP请求走私|[MPS-2021-2309](https://www.oscs1024.com/hd/MPS-2021-2309)|CVE-2021-25122|高危|
|Apache Tomcat 远程代码执行漏洞|代码注入|[MPS-2021-2466](https://www.oscs1024.com/hd/MPS-2021-2466)|CVE-2021-25329|高危|
|Apache Tomcat 拒绝服务漏洞|拒绝服务|[MPS-2021-31848](https://www.oscs1024.com/hd/MPS-2021-31848)|CVE-2021-41079|高危|
|io.undertow:undertow-core < 2.2.15.Final 存在拒绝服务漏洞|拒绝服务|[MPS-2021-32839](https://www.oscs1024.com/hd/MPS-2021-32839)|CVE-2021-3859|高危|
|Quality Open Software logback JNDI注入漏洞|反序列化|[MPS-2021-33911](https://www.oscs1024.com/hd/MPS-2021-33911)|CVE-2021-42550|中危|
|Apache Tomcat 条件竞争漏洞|竞争条件|[MPS-2021-37218](https://www.oscs1024.com/hd/MPS-2021-37218)|CVE-2021-43980|低危|
|Apache Log4j JMSAppender反序列化漏洞||[MPS-2021-38359](https://www.oscs1024.com/hd/MPS-2021-38359)|CVE-2021-4104|高危|
|Spring Framework权限许可和访问控制问题漏洞|权限管理不当|[MPS-2021-7485](https://www.oscs1024.com/hd/MPS-2021-7485)|CVE-2021-22118|高危|
|Apache Tomcat 环境问题漏洞|HTTP请求走私|[MPS-2021-9711](https://www.oscs1024.com/hd/MPS-2021-9711)|CVE-2021-33037|中危|
|Red Hat XNIO 资源错误分配漏洞|不加限制或调节的资源分配|[MPS-2022-0191](https://www.oscs1024.com/hd/MPS-2022-0191)|CVE-2022-0084|高危|
|Vmware Spring Framework 安全漏洞|不加限制或调节的资源分配|[MPS-2022-1080](https://www.oscs1024.com/hd/MPS-2022-1080)|CVE-2022-22950|中危|
|Pivotal Spring Framework 安全限制绕过漏洞|大小写敏感处理不恰当|[MPS-2022-1098](https://www.oscs1024.com/hd/MPS-2022-1098)|CVE-2022-22968|中危|
|Spring Framework spring-beans 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1101](https://www.oscs1024.com/hd/MPS-2022-1101)|CVE-2022-22970|中危|
|PostgreSQL JDBC 存在 SQL 注入漏洞|SQL注入|[MPS-2022-11227](https://www.oscs1024.com/hd/MPS-2022-11227)|CVE-2022-31197|高危|
|jnr-posix 存在UAF漏洞|UAF|[MPS-2022-11743](https://www.oscs1024.com/hd/MPS-2022-11743)||低危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|Logback SSL证书校验不当漏洞|中间人攻击|[MPS-2022-12411](https://www.oscs1024.com/hd/MPS-2022-12411)||中危|
|FasterXML Jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2022-12500](https://www.oscs1024.com/hd/MPS-2022-12500)||中危|
|org.json:json 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13520](https://www.oscs1024.com/hd/MPS-2022-13520)||高危|
|Apache Log4j JDBCAppender SQL注入漏洞|SQL注入|[MPS-2022-1444](https://www.oscs1024.com/hd/MPS-2022-1444)|CVE-2022-23305|严重|
|Apache Log4j Chainsaw反序列化漏洞|反序列化|[MPS-2022-1445](https://www.oscs1024.com/hd/MPS-2022-1445)|CVE-2022-23307|高危|
|Apache Log4j 反序列化漏洞|反序列化|[MPS-2022-1446](https://www.oscs1024.com/hd/MPS-2022-1446)|CVE-2022-23302|高危|
|Eclipse Jetty URI注入漏洞|注入|[MPS-2022-18060](https://www.oscs1024.com/hd/MPS-2022-18060)|CVE-2022-2047|低危|
|undertow AJP 拒绝服务漏洞|拒绝服务|[MPS-2022-18098](https://www.oscs1024.com/hd/MPS-2022-18098)|CVE-2022-2053|中危|
|Netty 存在信息泄露漏洞||[MPS-2022-3790](https://www.oscs1024.com/hd/MPS-2022-3790)|CVE-2022-24823|中危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|XStream 缓冲区错误漏洞|输入验证不恰当|[MPS-2022-57061](https://www.oscs1024.com/hd/MPS-2022-57061)|CVE-2022-40156|低危|
|xstream project跨界内存写漏洞|跨界内存写|[MPS-2022-57062](https://www.oscs1024.com/hd/MPS-2022-57062)|CVE-2022-40155|高危|
|xstream project跨界内存写漏洞|跨界内存写|[MPS-2022-57063](https://www.oscs1024.com/hd/MPS-2022-57063)|CVE-2022-40154|高危|
|XStream 缓冲区错误漏洞|越界写入|[MPS-2022-57065](https://www.oscs1024.com/hd/MPS-2022-57065)|CVE-2022-40152|高危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|pgjdbc <42.5.1 存在信息泄露漏洞|不安全的临时文件|[MPS-2022-58583](https://www.oscs1024.com/hd/MPS-2022-58583)|CVE-2022-41946|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|Apache Commons Text <1.10.0 远程代码执行漏洞|反序列化|[MPS-2022-59712](https://www.oscs1024.com/hd/MPS-2022-59712)|CVE-2022-42889|严重|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|Spring Security通配符路由绕过漏洞|关键资源权限分配不当|[MPS-2022-62832](https://www.oscs1024.com/hd/MPS-2022-62832)|CVE-2023-20860|高危|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot在Cloud Foundry中部署存在路由限制绕过风险|访问控制不当|[MPS-2022-62845](https://www.oscs1024.com/hd/MPS-2022-62845)|CVE-2023-20873|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|H2 数据库明文密码问题|未授权敏感信息泄露|[MPS-2022-65204](https://www.oscs1024.com/hd/MPS-2022-65204)|CVE-2022-45868|高危|
|spring-boot <2.2.11.RELEASE 存在目录劫持漏洞|将资源暴露给错误范围|[MPS-2022-6780](https://www.oscs1024.com/hd/MPS-2022-6780)|CVE-2022-27772|高危|
|Red Hat Undertow 安全漏洞|证书验证不恰当|[MPS-2022-68061](https://www.oscs1024.com/hd/MPS-2022-68061)|CVE-2022-4492|高危|
|spring-beans 远程代码执行漏洞(Spring4Shell)|表达式语言注入|[MPS-2022-6820](https://www.oscs1024.com/hd/MPS-2022-6820)|CVE-2022-22965|严重|
|Red Hat Undertow 资源管理错误漏洞|拒绝服务|[MPS-2022-7892](https://www.oscs1024.com/hd/MPS-2022-7892)|CVE-2022-1259|高危|
|undertow 存在分布式拒绝服务攻击|未加检查的返回值|[MPS-2022-8394](https://www.oscs1024.com/hd/MPS-2022-8394)|CVE-2022-1319|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Eclipse Jetty 资源管理错误漏洞|拒绝服务|[MPS-2023-4997](https://www.oscs1024.com/hd/MPS-2023-4997)|CVE-2023-26048|中危|
|Eclipse Jetty 信息泄露漏洞|XSS|[MPS-2023-4998](https://www.oscs1024.com/hd/MPS-2023-4998)|CVE-2023-26049|中危|
|jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2023-8438](https://www.oscs1024.com/hd/MPS-2023-8438)|CVE-2021-46877|中危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.apache.tomcat.embed:tomcat-embed-core|9.0.34|11.0.0-m6|间接依赖|强烈建议修复|C:0|H:6|M:4|L:1|
|com.fasterxml.woodstox:woodstox-core|6.2.6|6.4.0|间接依赖|建议修复|C:0|H:3|M:0|L:1|
|org.springframework.boot:spring-boot|2.2.7.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.2.7.RELEASE|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.5.0|3.0.7|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-webmvc|5.3.13|6.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.xerial.snappy:snappy-java|1.1.8.4|1.1.10.1|直接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.springframework:spring-context|5.2.6.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-web|5.2.6.RELEASE|6.0.0|间接依赖|建议修复|C:1|H:1|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.0|2.14.0-rc1|间接依赖|建议修复|C:0|H:1|M:4|L:0|
|org.eclipse.jetty:jetty-server|9.4.44.v20210927|12.0.0.beta0|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-context|5.3.13|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.6.0|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-web|5.3.13|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|log4j:log4j|1.2.17||直接依赖|建议修复|C:2|H:3|M:0|L:1|
|org.yaml:snakeyaml|1.25|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|org.springframework:spring-beans|5.2.6.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.yaml:snakeyaml|1.29|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|org.postgresql:postgresql|42.3.3|42.5.1|直接依赖|建议修复|C:0|H:1|M:1|L:0|
|ch.qos.logback:logback-core|1.2.3|1.2.8|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-beans|5.3.13|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.2.7.RELEASE|3.0.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.commons:commons-text|1.8|1.10.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|ch.qos.logback:logback-core|1.2.7|1.2.8|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|io.netty:netty-handler|4.1.70.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|io.undertow:undertow-core|2.2.12.Final|2.3.6.final|间接依赖|建议修复|C:0|H:4|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.10.4|2.14.0-rc1|间接依赖|建议修复|C:0|H:2|M:5|L:0|
|org.eclipse.jetty:jetty-http|9.4.44.v20210927|11.0.10|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|com.h2database:h2|2.1.212||直接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.json:json|20090211|20180130|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.github.jnr:jnr-posix|3.0.53|3.1.8|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|io.netty:netty-common|4.1.70.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.jboss.xnio:xnio-api|3.8.4.Final|3.8.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-core|5.3.13|6.0.7|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-expression|5.3.13|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|com.github.jnr:jnr-posix|3.1.5|3.1.8|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.springframework:spring-core|5.3.0|6.0.7|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|org.springframework:spring-expression|5.2.6.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|154|Low|
|MIT|6|Low|
|自定义许可证|11|Low|
|BSD-3-Clause|5|Low|
|LGPL-2.1|2|Medium|
|EPL-1.0|5|Low|
|EPL-2.0|6|Low|
|BSD-2-Clause|3|Low|
|MPL-1.1|1|Low|
|CPAL-1.0|2|Low|
|MPL-2.0|1|Low|
|CDDL-1.1|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.apache.logging.log4j:log4j-api|2.12.1|间接依赖|maven|
|org.thymeleaf.extras:thymeleaf-extras-springsecurity5|3.1.1.RELEASE|直接依赖|maven|
|commons-io:commons-io|2.7|间接依赖|maven|
|com.esri.geometry:esri-geometry-api|1.2.1|间接依赖|maven|
|com.typesafe:config|1.4.1|间接依赖|maven|
|org.springframework.boot:spring-boot|2.2.7.RELEASE|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.32|间接依赖|maven|
|com.github.jnr:jnr-x86asm|1.0.2|间接依赖|maven|
|com.github.jnr:jnr-ffi|2.1.12|间接依赖|maven|
|org.springframework:spring-jcl|5.3.13|间接依赖|maven|
|org.springframework:spring-jcl|5.3.0|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-server|9.4.44.v20210927|间接依赖|maven|
|org.springframework:spring-aop|5.3.13|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.14.1|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.30|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-client|9.4.44.v20210927|间接依赖|maven|
|io.grpc:grpc-netty-shaded|1.42.2|直接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|org.ow2.asm:asm-tree|9.1|间接依赖|maven|
|io.grpc:grpc-stub|1.42.2|直接依赖|maven|
|org.springframework:spring-beans|5.3.13|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.10.4|间接依赖|maven|
|org.wildfly.client:wildfly-client-config|1.0.1.Final|间接依赖|maven|
|org.mongodb:mongo-java-driver|3.12.10|直接依赖|maven|
|io.undertow:undertow-servlet|2.2.12.Final|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.34|间接依赖|maven|
|com.github.jnr:jnr-constants|0.9.15|间接依赖|maven|
|com.github.jnr:jnr-ffi|2.2.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.2.7.RELEASE|直接依赖|maven|
|com.github.jnr:jnr-enxio|0.25|间接依赖|maven|
|com.google.inject.extensions:guice-assistedinject|5.1.0|直接依赖|maven|
|org.eclipse.jetty:jetty-webapp|9.4.44.v20210927|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|org.apache.commons:commons-text|1.8|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.0|间接依赖|maven|
|org.apache.commons:commons-math3|3.6.1|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.34|间接依赖|maven|
|org.eclipse.jetty.websocket:javax-websocket-client-impl|9.4.44.v20210927|间接依赖|maven|
|org.jboss.xnio:xnio-api|3.8.4.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.10.4|间接依赖|maven|
|org.eclipse.jetty:jetty-continuation|9.4.44.v20210927|间接依赖|maven|
|org.springframework:spring-core|5.3.0|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.2|直接依赖|maven|
|info.picocli:picocli|4.0.4|直接依赖|maven|
|com.github.stephenc.jcip:jcip-annotations|1.0-1|间接依赖|maven|
|org.ow2.asm:asm|9.1|间接依赖|maven|
|org.eclipse.jetty:jetty-util-ajax|9.4.44.v20210927|间接依赖|maven|
|com.github.jnr:jnr-a64asm|1.0.0|间接依赖|maven|
|com.codahale.metrics:metrics-core|3.0.2|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.2.7.RELEASE|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.0.19.Final|间接依赖|maven|
|com.datastax.oss:native-protocol|1.5.0|间接依赖|maven|
|org.apache.commons:commons-lang3|3.11|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.1.Final|间接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|io.netty:netty-codec|4.1.70.Final|间接依赖|maven|
|io.opentracing:opentracing-util|LATEST|直接依赖|maven|
|com.datastax.oss:java-driver-shaded-guava|25.1-jre-graal-sub-1|间接依赖|maven|
|com.github.spotbugs:spotbugs-annotations|3.1.12|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.5.0|直接依赖|maven|
|org.jboss.resteasy:resteasy-vertx|4.5.8.Final|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-validation|2.2.7.RELEASE|间接依赖|maven|
|org.springframework:spring-web|5.2.6.RELEASE|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.3|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-actuator|2.2.7.RELEASE|直接依赖|maven|
|com.github.jnr:jffi|1.2.23|间接依赖|maven|
|org.eclipse.jetty:jetty-plus|9.4.44.v20210927|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.2.7.RELEASE|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|4.2.4|间接依赖|maven|
|org.apache.tomcat:annotations-api|6.0.53|直接依赖|maven|
|org.checkerframework:checker-qual|3.5.0|间接依赖|maven|
|com.datadoghq:dd-trace-api|LATEST|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.55|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-security|2.5.0|直接依赖|maven|
|org.mule.modules:mule-module-cors-kernel|1.1.2|间接依赖|maven|
|ognl:ognl|3.3.2|直接依赖|maven|
|ch.qos.logback:logback-core|1.2.7|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.5.0|直接依赖|maven|
|org.springframework:spring-core|5.3.13|间接依赖|maven|
|org.ow2.asm:asm-analysis|7.1|间接依赖|maven|
|jakarta.servlet:jakarta.servlet-api|4.0.4|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-common|9.4.44.v20210927|间接依赖|maven|
|org.postgresql:postgresql|42.3.3|直接依赖|maven|
|com.google.cloud:google-cloud-spanner|1.61.0|直接依赖|maven|
|org.ow2.asm:asm-commons|9.1|间接依赖|maven|
|org.ow2.asm:asm|7.1|间接依赖|maven|
|io.opentracing:opentracing-api|LATEST|直接依赖|maven|
|org.ow2.asm:asm-util|9.1|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-xml|2.13.0|直接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.0|间接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.4.44.v20210927|间接依赖|maven|
|logkit:logkit|1.0.1|直接依赖|maven|
|io.undertow:undertow-core|2.2.12.Final|间接依赖|maven|
|org.eclipse.jetty:jetty-servlets|9.4.44.v20210927|间接依赖|maven|
|org.javassist:javassist|3.28.0-GA|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.12.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jetty|2.6.0|直接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.11|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-thymeleaf|2.5.0|直接依赖|maven|
|org.json:json|20090211|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.34|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.10.4|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.5.0|直接依赖|maven|
|jakarta.websocket:jakarta.websocket-api|1.1.2|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.44.v20210927|间接依赖|maven|
|io.netty:netty-resolver|4.1.70.Final|间接依赖|maven|
|org.eclipse.jetty:jetty-annotations|9.4.44.v20210927|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.2.7.RELEASE|间接依赖|maven|
|org.springframework:spring-context|5.3.13|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.0|间接依赖|maven|
|io.micrometer:micrometer-core|1.3.8|间接依赖|maven|
|org.junit.platform:junit-platform-runner|1.9.0|直接依赖|maven|
|org.wildfly.common:wildfly-common|1.5.2.Final|间接依赖|maven|
|org.mule.connectors:mule-http-connector|1.5.23|直接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.6.0|间接依赖|maven|
|org.eclipse.jetty:jetty-http|9.4.44.v20210927|间接依赖|maven|
|com.datadoghq:dd-trace-api|0.68.0|直接依赖|maven|
|com.datadoghq:dd-trace-api|0.110.0|直接依赖|maven|
|io.netty:netty-handler|4.1.70.Final|间接依赖|maven|
|io.netty:netty-buffer|4.1.70.Final|间接依赖|maven|
|org.springframework:spring-expression|5.2.6.RELEASE|间接依赖|maven|
|org.mule.module:mule-java-module|1.2.7|直接依赖|maven|
|org.eclipse.jetty:jetty-xml|9.4.44.v20210927|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator|2.2.7.RELEASE|间接依赖|maven|
|org.codehaus.woodstox:stax2-api|4.2.1|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.4|直接依赖|maven|
|org.mule.connectors:mule-sockets-connector|1.2.0|直接依赖|maven|
|org.yaml:snakeyaml|1.25|间接依赖|maven|
|org.eclipse.jetty:jetty-client|9.4.44.v20210927|间接依赖|maven|
|org.eclipse.jetty.websocket:javax-websocket-server-impl|9.4.44.v20210927|间接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.44.v20210927|间接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.9.12|间接依赖|maven|
|log4j:log4j|1.2.17|直接依赖|maven|
|org.springframework:spring-aop|5.2.6.RELEASE|间接依赖|maven|
|org.springframework:spring-context|5.2.6.RELEASE|间接依赖|maven|
|com.github.jnr:jnr-unixsocket|0.27|间接依赖|maven|
|org.springframework:spring-web|5.3.13|间接依赖|maven|
|io.opentracing:opentracing-noop|0.33.0|直接依赖|maven|
|org.eclipse.jetty.websocket:websocket-api|9.4.44.v20210927|间接依赖|maven|
|com.datastax.oss:java-driver-core|4.13.0|直接依赖|maven|
|io.netty:netty-transport|4.1.70.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.6.0|直接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.14.1|间接依赖|maven|
|org.springframework.boot:spring-boot|2.6.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.6.0|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.10.4|间接依赖|maven|
|org.yaml:snakeyaml|1.29|间接依赖|maven|
|org.ow2.asm:asm-analysis|9.1|间接依赖|maven|
|com.github.jnr:jffi|1.3.1|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.32|间接依赖|maven|
|org.jboss.xnio:xnio-nio|3.8.4.Final|间接依赖|maven|
|com.datadoghq:dd-trace-api|1.2.0|直接依赖|maven|
|com.datadoghq:java-dogstatsd-client|2.11.0|直接依赖|maven|
|com.github.jnr:jnr-posix|3.1.5|间接依赖|maven|
|avalon-framework:avalon-framework|4.1.5|直接依赖|maven|
|io.undertow:undertow-websockets-jsr|2.2.12.Final|间接依赖|maven|
|org.ow2.asm:asm-commons|7.1|间接依赖|maven|
|com.h2database:h2|2.1.212|直接依赖|maven|
|ch.qos.logback:logback-core|1.2.3|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.6.0|间接依赖|maven|
|io.opentracing:opentracing-api|0.33.0|直接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.2.7.RELEASE|间接依赖|maven|
|org.lz4:lz4-java|1.8.0|直接依赖|maven|
|org.eclipse.jetty:jetty-server|9.4.44.v20210927|间接依赖|maven|
|org.springframework:spring-beans|5.2.6.RELEASE|间接依赖|maven|
|org.springframework:spring-webmvc|5.2.6.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.10.4|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.6.0|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|直接依赖|maven|
|javax.inject:javax.inject|1|直接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.2.Final|间接依赖|maven|
|org.ow2.asm:asm-tree|7.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-undertow|2.6.0|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.2.7.RELEASE|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|com.github.jnr:jnr-posix|3.0.53|间接依赖|maven|
|org.ow2.asm:asm-util|7.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.0|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.7|间接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|2.3.2|直接依赖|maven|
|com.github.jnr:jnr-constants|0.10.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|1.5.18.RELEASE|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.0|间接依赖|maven|
|org.eclipse.jetty:jetty-security|9.4.44.v20210927|间接依赖|maven|
|com.google.inject:guice|5.1.0|直接依赖|maven|
|org.jboss.threads:jboss-threads|3.1.0.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.2.7.RELEASE|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.13|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-servlet|9.4.44.v20210927|间接依赖|maven|
|org.springframework:spring-expression|5.3.13|间接依赖|maven|
|io.netty:netty-common|4.1.70.Final|间接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|6.2.6|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.10.4|间接依赖|maven|
|io.grpc:grpc-protobuf|1.42.2|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)