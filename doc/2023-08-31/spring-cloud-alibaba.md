# alibaba/spring-cloud-alibaba安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696947615148367872.svg)](https://www.murphysec.com/console/report/1694048110698651648/1696947615148367872)

仓库描述：Spring Cloud Alibaba provides a one-stop solution for application development for the distributed solutions of Alibaba middleware.

仓库地址：[https://github.com/alibaba/spring-cloud-alibaba](https://github.com/alibaba/spring-cloud-alibaba)

| star：26303 | watch：980 | fork：8039 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-29 12:57:00 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-31 02:09:44 | 组件总数：528 | 漏洞总数：70 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|Netty 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2019-12064](https://www.oscs1024.com/hd/MPS-2019-12064)|CVE-2019-16869|高危|
|Apache Log4j SocketServer反序列化漏洞|反序列化|[MPS-2019-17271](https://www.oscs1024.com/hd/MPS-2019-17271)|CVE-2019-17571|严重|
|SOFA-Hessian 代码问题漏洞||[MPS-2019-1978](https://www.oscs1024.com/hd/MPS-2019-1978)|CVE-2019-9212|严重|
|Apache Zookeeper 授权问题漏洞|授权检查缺失|[MPS-2019-5668](https://www.oscs1024.com/hd/MPS-2019-5668)|CVE-2019-0201|中危|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|apollo-adminservice 缺少访问控制漏洞|访问控制不当|[MPS-2020-12720](https://www.oscs1024.com/hd/MPS-2020-12720)|CVE-2020-15170|高危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Apache Log4j2 SmtpAppender证书验证不当漏洞|证书验证不恰当|[MPS-2020-6684](https://www.oscs1024.com/hd/MPS-2020-6684)|CVE-2020-9488|低危|
|Apache Ant 临时文件不安全问题|将资源暴露给错误范围|[MPS-2020-7418](https://www.oscs1024.com/hd/MPS-2020-7418)|CVE-2020-1945|中危|
|Apache Commons Compress 安存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10550](https://www.oscs1024.com/hd/MPS-2021-10550)|CVE-2021-35517|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10551](https://www.oscs1024.com/hd/MPS-2021-10551)|CVE-2021-35516|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10564](https://www.oscs1024.com/hd/MPS-2021-10564)|CVE-2021-36090|高危|
|Apache Commons Compress 无限循环漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-10565](https://www.oscs1024.com/hd/MPS-2021-10565)|CVE-2021-35515|高危|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|com.h2database:h2 < 2.0.202 XXE漏洞|XXE|[MPS-2021-19502](https://www.oscs1024.com/hd/MPS-2021-19502)|CVE-2021-23463|严重|
|Alibaba Druid 目录遍历漏洞|路径遍历|[MPS-2021-25327](https://www.oscs1024.com/hd/MPS-2021-25327)|CVE-2021-33800|高危|
|H2数据库存在JNDI注入漏洞|反序列化|[MPS-2021-33243](https://www.oscs1024.com/hd/MPS-2021-33243)|CVE-2021-42392|严重|
|Apache Log4j JMSAppender反序列化漏洞||[MPS-2021-38359](https://www.oscs1024.com/hd/MPS-2021-38359)|CVE-2021-4104|高危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9827](https://www.oscs1024.com/hd/MPS-2021-9827)|CVE-2021-36373|中危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9847](https://www.oscs1024.com/hd/MPS-2021-9847)|CVE-2021-36374|中危|
|PostgreSQL JDBC 存在 SQL 注入漏洞|SQL注入|[MPS-2022-11227](https://www.oscs1024.com/hd/MPS-2022-11227)|CVE-2022-31197|高危|
|Fastjson < 1.2.83 任意代码执行漏洞|反序列化|[MPS-2022-11320](https://www.oscs1024.com/hd/MPS-2022-11320)|CVE-2022-25845|高危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|com.beust:jcommander 存在从非可信控制范围包含功能例程漏洞||[MPS-2022-12225](https://www.oscs1024.com/hd/MPS-2022-12225)||中危|
|Spring Security 绕过授权漏洞|权限、特权和访问控制|[MPS-2022-12722](https://www.oscs1024.com/hd/MPS-2022-12722)|CVE-2022-31692|高危|
|H2 Console 代码注入漏洞|代码注入|[MPS-2022-1435](https://www.oscs1024.com/hd/MPS-2022-1435)|CVE-2022-23221|严重|
|Apache Log4j JDBCAppender SQL注入漏洞|SQL注入|[MPS-2022-1444](https://www.oscs1024.com/hd/MPS-2022-1444)|CVE-2022-23305|严重|
|Apache Log4j Chainsaw反序列化漏洞|反序列化|[MPS-2022-1445](https://www.oscs1024.com/hd/MPS-2022-1445)|CVE-2022-23307|高危|
|Apache Log4j 反序列化漏洞|反序列化|[MPS-2022-1446](https://www.oscs1024.com/hd/MPS-2022-1446)|CVE-2022-23302|高危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|xstream project跨界内存写漏洞|越界写入|[MPS-2022-57066](https://www.oscs1024.com/hd/MPS-2022-57066)|CVE-2022-40151|高危|
|Jettison <1.5.2 拒绝服务漏洞|拒绝服务|[MPS-2022-57067](https://www.oscs1024.com/hd/MPS-2022-57067)|CVE-2022-40150|高危|
|Jettison <1.5.1 拒绝服务漏洞|越界写入|[MPS-2022-57068](https://www.oscs1024.com/hd/MPS-2022-57068)|CVE-2022-40149|高危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|Netty <4.1.86.Final 存在拒绝服务漏洞|未经控制的递归|[MPS-2022-58518](https://www.oscs1024.com/hd/MPS-2022-58518)|CVE-2022-41881|中危|
|Netty <4.1.86.Final 存在 CRLF 注入漏洞||[MPS-2022-58552](https://www.oscs1024.com/hd/MPS-2022-58552)|CVE-2022-41915|中危|
|pgjdbc <42.5.1 存在信息泄露漏洞|不安全的临时文件|[MPS-2022-58583](https://www.oscs1024.com/hd/MPS-2022-58583)|CVE-2022-41946|中危|
|XStream < 1.4.20 栈缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58603](https://www.oscs1024.com/hd/MPS-2022-58603)|CVE-2022-41966|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|Spring Security通配符路由绕过漏洞|关键资源权限分配不当|[MPS-2022-62832](https://www.oscs1024.com/hd/MPS-2022-62832)|CVE-2023-20860|高危|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot在Cloud Foundry中部署存在路由限制绕过风险|访问控制不当|[MPS-2022-62845](https://www.oscs1024.com/hd/MPS-2022-62845)|CVE-2023-20873|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|Jettison <1.5.2 拒绝服务漏洞|越界写入|[MPS-2022-64973](https://www.oscs1024.com/hd/MPS-2022-64973)|CVE-2022-45685|高危|
|Jettison <1.5.2 拒绝服务漏洞|越界写入|[MPS-2022-64981](https://www.oscs1024.com/hd/MPS-2022-64981)|CVE-2022-45693|高危|
|H2 数据库明文密码问题|未授权敏感信息泄露|[MPS-2022-65204](https://www.oscs1024.com/hd/MPS-2022-65204)|CVE-2022-45868|高危|
|Oracle MySQL 安全漏洞||[MPS-2022-68556](https://www.oscs1024.com/hd/MPS-2022-68556)|CVE-2023-21971|中危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Apache Commons FileUpload <1.5 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2023-3553](https://www.oscs1024.com/hd/MPS-2023-3553)|CVE-2023-24998|中危|
|Apache Kafka Connect 模块JNDI注入漏洞|反序列化|[MPS-2023-3834](https://www.oscs1024.com/hd/MPS-2023-3834)|CVE-2023-25194|高危|
|netplex json-smart 安全漏洞|未经控制的递归|[MPS-2023-7760](https://www.oscs1024.com/hd/MPS-2023-7760)|CVE-2023-1370|高危|
|Jettison 安全漏洞|未经控制的递归|[MPS-2023-8270](https://www.oscs1024.com/hd/MPS-2023-8270)|CVE-2023-1436|高危|
|Apache MINA SSHD SFTP路径穿越漏洞|路径遍历|[MPS-4amk-710b](https://www.oscs1024.com/hd/MPS-4amk-710b)|CVE-2023-35887|高危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Spring Security 路径匹配漏洞|不恰当实现的标准安全检查|[MPS-j3nx-691g](https://www.oscs1024.com/hd/MPS-j3nx-691g)|CVE-2023-34034|严重|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|Apache Tomcat FORM 重定向漏洞|跨站重定向|[MPS-uy56-j8e4](https://www.oscs1024.com/hd/MPS-uy56-j8e4)|CVE-2023-41080|低危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.springframework:spring-webmvc|6.0.4|6.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty|3.10.6.Final||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.mysql:mysql-connector-j|8.0.32|8.0.33|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.alibaba:druid|1.1.10|1.2.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.kafka:kafka-clients|3.0.1|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.29|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|com.thoughtworks.xstream:xstream|1.4.19|1.4.20|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.6.11|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.sshd:sshd-sftp|2.9.2|2.10|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.commons:commons-compress|1.19|1.21|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|com.ctrip.framework.apollo:apollo-core|1.5.0|1.7.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.3|2.14.0-rc1|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|com.ctrip.framework.apollo:apollo-core|1.6.0|1.7.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-web|5.3.22|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.alipay.sofa:hessian|3.3.6|4.0.3|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework.security:spring-security-web|5.6.7|6.1.2|间接依赖|建议修复|C:1|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.33|2.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|log4j:log4j|1.2.17||直接依赖|建议修复|C:2|H:3|M:0|L:1|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.65|11.0.0-m6|间接依赖|建议修复|C:0|H:0|M:0|L:1|
|org.apache.tomcat.embed:tomcat-embed-core|10.1.5|11.0.0-m6|间接依赖|建议修复|C:0|H:0|M:0|L:1|
|org.springframework:spring-webmvc|5.3.22|6.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.87.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.codehaus.jettison:jettison|1.4.0|1.5.4|间接依赖|建议修复|C:0|H:5|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|3.0.2|3.0.7|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.79.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.h2database:h2|1.4.200|2.1.210|间接依赖|建议修复|C:3|H:1|M:0|L:0|
|org.xerial.snappy:snappy-java|1.1.8.1|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.postgresql:postgresql|42.3.6|42.5.1|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.14.1||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.alibaba:fastjson|1.2.73|1.2.83|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-actuator-autoconfigure|3.0.2|3.0.6|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|commons-fileupload:commons-fileupload|1.4|1.5|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.google.protobuf:protobuf-java|3.7.1|3.21.7|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|net.minidev:json-smart|2.4.8|2.4.9|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.google.guava:guava|19.0|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|com.google.guava:guava|30.1-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|5.3.22|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-core|6.0.4|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.zookeeper:zookeeper|3.4.13|3.5.5|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|6.0.4|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.beust:jcommander|1.72|1.75|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-haproxy|4.1.79.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.bouncycastle:bcprov-jdk15on|1.69||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-http|4.1.79.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.ant:ant|1.10.6|1.10.11|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|org.springframework:spring-core|5.3.22|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|27.0.1-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:1|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|439|Low|
|自定义许可证|43|Low|
|MIT|18|Low|
|BSD-3-Clause|5|Low|
|EPL-2.0|9|Low|
|EPL-1.0|5|Low|
|LGPL-2.1|3|Medium|
|MPL-1.1|1|Low|
|MIT-0|1|Low|
|BSD-2-Clause|4|Low|
|CDDL-1.1|3|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|io.netty:netty-codec-haproxy|4.1.79.Final|间接依赖|maven|
|io.netty:netty|3.10.6.Final|间接依赖|maven|
|org.apache.dubbo.extensions:dubbo-filter-seata|1.0.2|间接依赖|maven|
|com.alibaba.cloud:spring-cloud-circuitbreaker-sentinel|2022.0.0.0|直接依赖|maven|
|com.alibaba.nacos:nacos-client|1.4.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|3.0.2|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|间接依赖|maven|
|com.alibaba:druid|1.1.10|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-config|4.0.0|直接依赖|maven|
|org.apache.commons:commons-math|2.2|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.79.Final|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.87.Final|间接依赖|maven|
|io.netty:netty-buffer|4.1.79.Final|间接依赖|maven|
|com.alibaba.csp:sentinel-parameter-flow-control|1.8.6|直接依赖|maven|
|io.netty:netty-codec-xml|4.1.87.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-validation|3.0.2|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|3.0.2|直接依赖|maven|
|com.alibaba.nacos:nacos-auth-plugin|2.2.1|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.22|间接依赖|maven|
|org.thymeleaf:thymeleaf|3.1.1.RELEASE|间接依赖|maven|
|org.springframework.cloud:spring-cloud-function-core|4.0.0|间接依赖|maven|
|io.netty:netty-codec-stomp|4.1.87.Final|间接依赖|maven|
|com.alibaba.csp:sentinel-spring-webflux-adapter|1.8.6|直接依赖|maven|
|io.prometheus:simpleclient_tracer_otel_agent|0.16.0|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-cache|3.0.2|间接依赖|maven|
|com.github.docker-java:docker-java-transport-zerodep|3.2.12|间接依赖|maven|
|com.vaadin.external.google:android-json|0.0.20131108.vaadin1|间接依赖|maven|
|org.apache.sshd:sshd-sftp|2.9.2|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.87.Final|间接依赖|maven|
|org.slf4j:slf4j-api|2.0.6|直接依赖|maven|
|commons-cli:commons-cli|1.2|间接依赖|maven|
|io.seata:seata-serializer-all|1.5.0|间接依赖|maven|
|org.springframework:spring-webflux|6.0.4|间接依赖|maven|
|com.alibaba.nacos:nacos-encryption-plugin|2.2.1|间接依赖|maven|
|io.github.openfeign:feign-slf4j|12.1|间接依赖|maven|
|com.alibaba.cloud:spring-cloud-starter-alibaba-nacos-discovery|2022.0.0.0|直接依赖|maven|
|com.caucho:hessian|4.0.63|间接依赖|maven|
|org.apache.rocketmq:rocketmq-remoting|4.9.4|间接依赖|maven|
|org.eclipse.jgit:org.eclipse.jgit.ssh.apache|6.4.0.202211300538-r|间接依赖|maven|
|com.typesafe:config|1.2.1|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.65|间接依赖|maven|
|net.logstash.logback:logstash-logback-encoder|6.5|间接依赖|maven|
|org.checkerframework:checker-qual|3.5.0|间接依赖|maven|
|io.netty:netty-all|4.1.79.Final|间接依赖|maven|
|com.thoughtworks.xstream:xstream|1.4.19|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|10.1.5|间接依赖|maven|
|org.springframework:spring-web|6.0.4|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|3.0.2|直接依赖|maven|
|io.seata:seata-metrics-registry-compact|1.5.0|间接依赖|maven|
|io.netty:netty-codec-haproxy|4.1.87.Final|间接依赖|maven|
|org.springframework.cloud:spring-cloud-function-context|4.0.0|间接依赖|maven|
|org.springframework.cloud:spring-cloud-config-client|4.0.0|直接依赖|maven|
|io.github.openfeign.form:feign-form|3.8.0|间接依赖|maven|
|io.seata:seata-discovery-custom|1.5.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|3.0.2|直接依赖|maven|
|io.seata:seata-metrics-exporter-prometheus|1.5.0|间接依赖|maven|
|io.github.openfeign:feign-core|12.1|间接依赖|maven|
|io.netty:netty-codec-xml|4.1.79.Final|间接依赖|maven|
|com.googlecode.concurrentlinkedhashmap:concurrentlinkedhashmap-lru|1.4.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-security|2.6.11|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.14|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.7.22|间接依赖|maven|
|org.projectlombok:lombok|1.18.24|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.7.22|间接依赖|maven|
|io.micrometer:micrometer-commons|1.10.3|间接依赖|maven|
|jline:jline|0.9.94|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.6.11|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.14.1|直接依赖|maven|
|com.alipay.sofa.lookout:lookout-api|1.5.2|间接依赖|maven|
|org.springframework:spring-context|5.3.22|间接依赖|maven|
|io.grpc:grpc-protobuf|1.17.1|间接依赖|maven|
|com.google.guava:guava|19.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.19.0|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-consul-discovery|4.0.0|直接依赖|maven|
|org.apache.curator:curator-recipes|5.1.0|间接依赖|maven|
|com.alibaba.csp:sentinel-core|1.8.6|直接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-loadbalancer|4.0.0|直接依赖|maven|
|org.apache.zookeeper:zookeeper|3.4.13|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.87.Final|间接依赖|maven|
|io.prometheus:simpleclient_tracer_otel|0.12.0|间接依赖|maven|
|org.apache.sshd:sshd-osgi|2.9.2|间接依赖|maven|
|com.alibaba.csp:sentinel-cluster-common-default|1.8.6|间接依赖|maven|
|com.alibaba.nacos:nacos-client|2.2.1|直接依赖|maven|
|com.alibaba.cloud:spring-cloud-starter-bus-rocketmq|2022.0.0.0|直接依赖|maven|
|net.bytebuddy:byte-buddy-agent|1.12.22|间接依赖|maven|
|mysql:mysql-connector-java|8.0.28|直接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.79.Final|间接依赖|maven|
|com.alibaba.cloud:spring-cloud-alibaba-sentinel-datasource|2022.0.0.0|直接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.16|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-thymeleaf|3.0.2|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.14.1|间接依赖|maven|
|io.grpc:grpc-grpclb|1.17.1|间接依赖|maven|
|io.netty:netty-transport|4.1.79.Final|间接依赖|maven|
|io.seata:seata-compressor-lz4|1.5.0|间接依赖|maven|
|org.springframework.cloud:spring-cloud-context|4.0.0|直接依赖|maven|
|com.google.guava:guava|30.1-jre|间接依赖|maven|
|io.micrometer:micrometer-observation|1.10.3|间接依赖|maven|
|com.alibaba.nacos:nacos-common|1.4.2|间接依赖|maven|
|org.antlr:ST4|4.3|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.65|间接依赖|maven|
|io.etcd:jetcd-resolver|0.3.0|间接依赖|maven|
|com.ecwid.consul:consul-api|1.4.5|间接依赖|maven|
|io.netty:netty-transport-sctp|4.1.87.Final|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|间接依赖|maven|
|org.springframework:spring-core|5.3.22|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|io.seata:seata-discovery-zk|1.5.0|间接依赖|maven|
|io.grpc:grpc-netty|1.17.1|间接依赖|maven|
|net.jodah:typetools|0.6.2|间接依赖|maven|
|com.esotericsoftware:minlog|1.3.0|间接依赖|maven|
|org.mockito:mockito-junit-jupiter|4.8.1|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-api|5.7.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.6.11|间接依赖|maven|
|net.minidev:accessors-smart|2.4.8|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.79.Final|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.7.1|间接依赖|maven|
|io.prometheus:simpleclient|0.16.0|间接依赖|maven|
|com.github.danielwegener:logback-kafka-appender|0.2.0-RC2|间接依赖|maven|
|com.alipay.sofa:hessian|3.3.6|间接依赖|maven|
|commons-digester:commons-digester|2.1|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.14.1|间接依赖|maven|
|commons-configuration:commons-configuration|1.10|间接依赖|maven|
|org.eclipse.jgit:org.eclipse.jgit.http.apache|6.4.0.202211300538-r|间接依赖|maven|
|org.slf4j:slf4j-reload4j|2.0.6|间接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|io.micrometer:micrometer-core|1.10.3|间接依赖|maven|
|org.springframework.cloud:spring-cloud-bus|4.0.0|直接依赖|maven|
|com.google.guava:guava|27.0.1-jre|间接依赖|maven|
|io.etcd:jetcd-core|0.3.0|间接依赖|maven|
|io.seata:seata-spring-autoconfigure-server|1.5.0|间接依赖|maven|
|log4j:log4j|1.2.17|直接依赖|maven|
|junit:junit|4.13.2|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.79.Final|间接依赖|maven|
|org.yaml:snakeyaml|1.33|间接依赖|maven|
|com.alibaba.csp:sentinel-spring-cloud-gateway-adapter|1.8.6|直接依赖|maven|
|io.seata:seata-discovery-etcd3|1.5.0|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.15|间接依赖|maven|
|com.alibaba.csp:sentinel-reactor-adapter|1.8.6|直接依赖|maven|
|org.apache.commons:commons-dbcp2|2.9.0|间接依赖|maven|
|org.springframework:spring-expression|5.3.22|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.14.1|间接依赖|maven|
|io.seata:seata-compressor-all|1.5.0|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.65|间接依赖|maven|
|org.javassist:javassist|3.21.0-GA|间接依赖|maven|
|org.tukaani:xz|1.8|间接依赖|maven|
|com.jayway.jsonpath:json-path|2.7.0|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-consul|4.0.0|间接依赖|maven|
|commons-io:commons-io|2.7|间接依赖|maven|
|com.alibaba.csp:sentinel-datasource-zookeeper|1.8.6|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.6.11|间接依赖|maven|
|org.springframework.security:spring-security-crypto|6.0.1|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.11|间接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.87.Final|间接依赖|maven|
|com.mysql:mysql-connector-j|8.0.32|直接依赖|maven|
|io.netty:netty-transport-rxtx|4.1.87.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-actuator|3.0.2|直接依赖|maven|
|io.seata:seata-spring-boot-starter|1.7.0|直接依赖|maven|
|io.netty:netty-handler-proxy|4.1.87.Final|间接依赖|maven|
|org.springframework:spring-beans|6.0.4|间接依赖|maven|
|com.googlecode.javaewah:JavaEWAH|1.1.13|间接依赖|maven|
|org.apache.ant:ant-launcher|1.10.6|间接依赖|maven|
|io.prometheus:simpleclient_tracer_otel_agent|0.12.0|间接依赖|maven|
|io.netty:netty-all|4.1.87.Final|间接依赖|maven|
|com.alibaba.fastjson2:fastjson2-extension|2.0.22|间接依赖|maven|
|org.lz4:lz4-java|1.8.0|间接依赖|maven|
|io.seata:seata-compressor-gzip|1.5.0|间接依赖|maven|
|io.seata:seata-console|1.5.0|间接依赖|maven|
|io.seata:seata-discovery-nacos|1.5.0|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator|3.0.2|直接依赖|maven|
|org.springframework:spring-test|6.0.4|间接依赖|maven|
|io.seata:seata-common|1.5.0|间接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|io.jsonwebtoken:jjwt-impl|0.10.5|间接依赖|maven|
|org.springframework.boot:spring-boot|2.6.11|间接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j-impl|2.14.1|直接依赖|maven|
|commons-fileupload:commons-fileupload|1.4|间接依赖|maven|
|io.netty:netty-codec-redis|4.1.79.Final|间接依赖|maven|
|org.lz4:lz4-java|1.7.1|间接依赖|maven|
|io.seata:seata-discovery-eureka|1.5.0|间接依赖|maven|
|io.netty:netty-handler-ssl-ocsp|4.1.87.Final|间接依赖|maven|
|io.netty:netty-buffer|4.1.87.Final|间接依赖|maven|
|org.codehaus.woodstox:stax2-api|4.2.1|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|4.0.0|间接依赖|maven|
|io.netty:netty-transport-sctp|4.1.79.Final|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|10.1.5|间接依赖|maven|
|com.alibaba.csp:sentinel-datasource-redis|1.8.6|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|3.0.2|间接依赖|maven|
|io.opencensus:opencensus-contrib-grpc-metrics|0.17.0|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.16|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-xml|2.14.1|直接依赖|maven|
|org.abego.treelayout:org.abego.treelayout.core|1.0.3|间接依赖|maven|
|org.apache.kafka:kafka-clients|3.0.1|间接依赖|maven|
|org.slf4j:jul-to-slf4j|2.0.6|间接依赖|maven|
|io.seata:seata-compressor-7z|1.5.0|间接依赖|maven|
|com.alibaba.cloud:spring-cloud-starter-alibaba-sidecar|2022.0.0.0|直接依赖|maven|
|io.seata:seata-discovery-sofa|1.5.0|间接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|1.0.0|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.79.Final|间接依赖|maven|
|org.apache.ant:ant|1.10.6|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.22|间接依赖|maven|
|io.seata:seata-metrics-core|1.5.0|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.6.11|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|3.0.2|直接依赖|maven|
|com.ctrip.framework.apollo:apollo-client|1.6.0|间接依赖|maven|
|com.alibaba:druid-spring-boot-starter|1.1.10|直接依赖|maven|
|org.mockito:mockito-core|4.6.1|直接依赖|maven|
|io.netty:netty-codec-http|4.1.87.Final|间接依赖|maven|
|org.skyscreamer:jsonassert|1.5.1|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.3|间接依赖|maven|
|io.seata:seata-config-consul|1.5.0|间接依赖|maven|
|io.seata:seata-serializer-kryo|1.5.0|间接依赖|maven|
|org.ow2.asm:asm|9.1|间接依赖|maven|
|org.springframework.retry:spring-retry|2.0.0|间接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-autoconfigure|3.0.0|间接依赖|maven|
|org.apache.curator:curator-client|5.1.0|间接依赖|maven|
|com.ecwid.consul:consul-api|1.4.2|间接依赖|maven|
|io.netty:netty-common|4.1.87.Final|间接依赖|maven|
|com.netflix.netflix-commons:netflix-infix|0.3.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.19.0|间接依赖|maven|
|org.rnorth.duct-tape:duct-tape|1.0.8|间接依赖|maven|
|com.stoyanr:evictor|1.0.0|间接依赖|maven|
|com.alibaba.csp:sentinel-datasource-nacos|1.8.6|直接依赖|maven|
|io.netty:netty-transport-udt|4.1.87.Final|间接依赖|maven|
|io.netty:netty-codec-memcache|4.1.87.Final|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|org.springframework.cloud:spring-cloud-consul-core|4.0.0|间接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.0-4|间接依赖|maven|
|org.apiguardian:apiguardian-api|1.1.0|间接依赖|maven|
|org.apache.rocketmq:rocketmq-logging|4.9.4|间接依赖|maven|
|io.seata:seata-metrics-api|1.5.0|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-bootstrap|3.1.1|直接依赖|maven|
|org.springframework.cloud:spring-cloud-openfeign-core|4.0.0|间接依赖|maven|
|io.seata:seata-config-spring-cloud|1.5.0|间接依赖|maven|
|com.netflix.netflix-commons:netflix-eventbus|0.3.0|间接依赖|maven|
|io.seata:seata-config-etcd3|1.5.0|间接依赖|maven|
|org.apache.commons:commons-compress|1.19|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.7.22|间接依赖|maven|
|org.springframework:spring-messaging|6.0.4|间接依赖|maven|
|org.springframework.security:spring-security-crypto|5.6.7|间接依赖|maven|
|org.apache.rocketmq:rocketmq-acl|4.9.4|直接依赖|maven|
|com.netflix.eureka:eureka-client|1.10.17|间接依赖|maven|
|antlr:antlr|2.7.7|间接依赖|maven|
|com.alibaba:fastjson|1.2.73|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|3.0.2|直接依赖|maven|
|org.ow2.asm:asm|4.2|间接依赖|maven|
|org.apache.httpcomponents.client5:httpclient5|5.1.4|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-reactor-netty|3.0.2|间接依赖|maven|
|org.springframework:spring-aop|5.3.22|间接依赖|maven|
|com.github.andrewoma.dexx:dexx-collections|0.2|间接依赖|maven|
|io.lettuce:lettuce-core|6.2.2.RELEASE|间接依赖|maven|
|io.github.x-stream:mxparser|1.2.2|间接依赖|maven|
|io.prometheus:simpleclient_tracer_common|0.12.0|间接依赖|maven|
|org.apache.commons:commons-compress|1.21|间接依赖|maven|
|com.h2database:h2|1.4.200|间接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.79.Final|间接依赖|maven|
|org.springframework:spring-web|5.3.22|间接依赖|maven|
|org.springframework.integration:spring-integration-core|6.0.2|间接依赖|maven|
|commons-jxpath:commons-jxpath|1.3|间接依赖|maven|
|io.seata:seata-serializer-protobuf|1.5.0|间接依赖|maven|
|com.ibm.icu:icu4j|61.1|间接依赖|maven|
|org.springframework.cloud:spring-cloud-gateway-server|4.0.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.3|间接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|6.4.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.2|间接依赖|maven|
|io.netty:netty-codec-redis|4.1.87.Final|间接依赖|maven|
|com.101tec:zkclient|0.11|间接依赖|maven|
|io.prometheus:simpleclient|0.12.0|间接依赖|maven|
|com.alibaba.csp:sentinel-spring-webmvc-6x-adapter|1.8.6|直接依赖|maven|
|com.sun.jersey:jersey-client|1.19.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.3|间接依赖|maven|
|com.alipay.sofa:registry-client-all|5.2.0|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.87.Final|间接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.4.14|间接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5-h2|5.1.5|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.17|间接依赖|maven|
|org.springframework.boot:spring-boot-test|3.0.2|间接依赖|maven|
|com.ctrip.framework.apollo:apollo-core|1.6.0|间接依赖|maven|
|io.netty:netty-transport-rxtx|4.1.79.Final|间接依赖|maven|
|org.springframework:spring-tx|6.0.4|直接依赖|maven|
|org.junit.jupiter:junit-jupiter|5.7.2|直接依赖|maven|
|com.alibaba.cloud:spring-cloud-starter-alibaba-sentinel|2022.0.0.0|直接依赖|maven|
|io.seata:seata-spring-autoconfigure-core|1.7.0|间接依赖|maven|
|com.github.docker-java:docker-java-api|3.2.12|间接依赖|maven|
|io.seata:seata-config-nacos|1.5.0|间接依赖|maven|
|io.netty:netty-codec-stomp|4.1.79.Final|间接依赖|maven|
|com.alibaba.cloud:spring-cloud-starter-alibaba-seata|2022.0.0.0|直接依赖|maven|
|org.antlr:antlr4|4.8|间接依赖|maven|
|javax.servlet:javax.servlet-api|4.0.1|间接依赖|maven|
|com.google.code.gson:gson|2.9.1|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|10.1.5|间接依赖|maven|
|com.alibaba.cloud:spring-cloud-alibaba-sentinel-gateway|2022.0.0.0|直接依赖|maven|
|com.ctrip.framework.apollo:apollo-core|1.5.0|间接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.5|间接依赖|maven|
|io.netty:netty-handler|4.1.87.Final|间接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|io.seata:seata-compressor-zip|1.5.0|间接依赖|maven|
|net.i2p.crypto:eddsa|0.3.0|间接依赖|maven|
|com.alibaba.csp:sentinel-datasource-consul|1.8.6|直接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.79.Final|间接依赖|maven|
|org.springframework:spring-jcl|6.0.4|间接依赖|maven|
|org.aspectj:aspectjweaver|1.9.19|间接依赖|maven|
|com.alibaba.fastjson2:fastjson2|2.0.22|间接依赖|maven|
|io.grpc:grpc-core|1.17.1|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.2|间接依赖|maven|
|org.springframework:spring-expression|6.0.4|间接依赖|maven|
|com.alibaba.csp:sentinel-api-gateway-adapter-common|1.8.6|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-test|3.0.2|直接依赖|maven|
|io.projectreactor.netty:reactor-netty-http|1.1.2|间接依赖|maven|
|io.seata:seata-server|1.5.0|直接依赖|maven|
|io.projectreactor.addons:reactor-extra|3.5.0|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.87.Final|间接依赖|maven|
|io.seata:seata-compressor-zstd|1.5.0|间接依赖|maven|
|org.xmlunit:xmlunit-core|2.9.1|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.19.0|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.5.0.Final|间接依赖|maven|
|io.netty:netty-codec|4.1.87.Final|间接依赖|maven|
|io.prometheus:simpleclient_tracer_common|0.16.0|间接依赖|maven|
|javax.servlet:servlet-api|2.5|间接依赖|maven|
|io.netty:netty-codec-memcache|4.1.79.Final|间接依赖|maven|
|io.seata:seata-compressor-bzip2|1.5.0|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|org.springframework.integration:spring-integration-jmx|6.0.2|间接依赖|maven|
|com.alibaba.csp:sentinel-cluster-server-default|1.8.6|直接依赖|maven|
|com.ctrip.framework.apollo:apollo-client|1.5.0|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|3.0.2|间接依赖|maven|
|org.opentest4j:opentest4j|1.2.0|间接依赖|maven|
|org.springframework.cloud:spring-cloud-loadbalancer|4.0.0|直接依赖|maven|
|com.alibaba.csp:sentinel-datasource-extension|1.8.6|直接依赖|maven|
|org.rnorth.visible-assertions:visible-assertions|2.1.2|直接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.1|间接依赖|maven|
|io.netty:netty-codec-http|4.1.79.Final|间接依赖|maven|
|io.seata:seata-metrics-all|1.5.0|间接依赖|maven|
|com.alipay.sofa.common:sofa-common-tools|1.0.12|间接依赖|maven|
|org.thymeleaf:thymeleaf-spring6|3.1.1.RELEASE|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-gateway|4.0.0|直接依赖|maven|
|io.projectreactor.netty:reactor-netty-core|1.1.2|间接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.17.1|间接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|org.apache.rocketmq:rocketmq-srvutil|4.9.4|间接依赖|maven|
|org.springframework.cloud:spring-cloud-consul-discovery|4.0.0|间接依赖|maven|
|io.seata:seata-all|1.7.0|间接依赖|maven|
|com.alipay.sofa:bolt|1.4.6|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.3|间接依赖|maven|
|org.glassfish:javax.json|1.0.4|间接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.87.Final|间接依赖|maven|
|io.seata:seata-discovery-redis|1.5.0|间接依赖|maven|
|commons-pool:commons-pool|1.6|间接依赖|maven|
|org.antlr:antlr-runtime|3.5.2|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|io.netty:netty-transport-udt|4.1.79.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.6.11|间接依赖|maven|
|org.springframework.boot:spring-boot-configuration-processor|3.0.2|直接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.1|间接依赖|maven|
|com.netflix.servo:servo-core|0.12.21|间接依赖|maven|
|com.sun.jersey:jersey-core|1.19.1|间接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-starter|3.0.0|直接依赖|maven|
|io.etcd:jetcd-common|0.3.0|间接依赖|maven|
|org.mybatis:mybatis-spring|3.0.0|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|2.1.1|直接依赖|maven|
|io.netty:netty-handler|4.1.79.Final|间接依赖|maven|
|io.netty:netty-codec-smtp|4.1.87.Final|间接依赖|maven|
|net.minidev:json-smart|2.4.8|间接依赖|maven|
|io.netty:netty-resolver|4.1.79.Final|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|8.0.0.Final|直接依赖|maven|
|org.springframework.cloud:spring-cloud-stream|4.0.0|直接依赖|maven|
|com.alibaba.spring:spring-context-support|1.0.11|直接依赖|maven|
|io.jsonwebtoken:jjwt-jackson|0.10.5|间接依赖|maven|
|com.google.inject:guice|4.1.0|间接依赖|maven|
|de.javakaffee:kryo-serializers|0.42|间接依赖|maven|
|org.apache.sshd:sshd-core|2.9.2|间接依赖|maven|
|com.alibaba.nacos:nacos-api|1.4.2|间接依赖|maven|
|org.junit.platform:junit-platform-commons|1.7.2|间接依赖|maven|
|io.prometheus:simpleclient_httpserver|0.12.0|间接依赖|maven|
|ch.qos.logback:logback-classic|1.4.5|间接依赖|maven|
|org.attoparser:attoparser|2.0.6.RELEASE|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|3.1.2|间接依赖|maven|
|org.springframework:spring-aop|6.0.4|间接依赖|maven|
|io.prometheus:simpleclient_tracer_otel|0.16.0|间接依赖|maven|
|com.alibaba:fastjson|1.2.83|间接依赖|maven|
|org.springframework:spring-webmvc|6.0.4|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.14.1|间接依赖|maven|
|io.netty:netty-common|4.1.79.Final|间接依赖|maven|
|commons-logging:commons-logging|1.1.1|间接依赖|maven|
|org.eclipse.jgit:org.eclipse.jgit|6.4.0.202211300538-r|间接依赖|maven|
|io.seata:seata-compressor-deflater|1.5.0|间接依赖|maven|
|io.projectreactor:reactor-core|3.5.2|直接依赖|maven|
|org.junit.platform:junit-platform-engine|1.7.2|间接依赖|maven|
|com.esotericsoftware:kryo|4.0.2|间接依赖|maven|
|org.testcontainers:junit-jupiter|1.16.3|直接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.69|间接依赖|maven|
|de.ruedigermoeller:fst|2.57|间接依赖|maven|
|org.springframework.boot:spring-boot-test-autoconfigure|3.0.2|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.14.1|间接依赖|maven|
|org.antlr:antlr-runtime|3.4|间接依赖|maven|
|org.springframework:spring-core|6.0.4|间接依赖|maven|
|org.apache.commons:commons-pool2|2.11.1|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.11|间接依赖|maven|
|org.mybatis:mybatis|3.5.11|间接依赖|maven|
|org.springframework:spring-beans|5.3.22|间接依赖|maven|
|commons-lang:commons-lang|2.6|间接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.79.Final|间接依赖|maven|
|com.zaxxer:HikariCP|5.0.1|间接依赖|maven|
|xmlpull:xmlpull|1.1.3.1|间接依赖|maven|
|org.codehaus.jettison:jettison|1.4.0|间接依赖|maven|
|ch.qos.logback:logback-core|1.4.5|间接依赖|maven|
|commons-validator:commons-validator|1.7|间接依赖|maven|
|com.alibaba.cloud:spring-cloud-starter-alibaba-nacos-config|2022.0.0.0|直接依赖|maven|
|org.springframework.security:spring-security-config|5.6.7|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-params|5.7.2|间接依赖|maven|
|org.apache.rocketmq:rocketmq-client|4.9.4|直接依赖|maven|
|org.antlr:stringtemplate|3.2.1|间接依赖|maven|
|org.testcontainers:testcontainers|1.16.3|直接依赖|maven|
|org.apache.curator:curator-framework|5.1.0|间接依赖|maven|
|org.antlr:antlr4-runtime|4.8|间接依赖|maven|
|io.seata:seata-config-all|1.5.0|间接依赖|maven|
|com.github.docker-java:docker-java-transport|3.2.12|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.87.Final|间接依赖|maven|
|com.alibaba.csp:sentinel-transport-common|1.8.6|间接依赖|maven|
|org.objenesis:objenesis|3.2|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.79.Final|间接依赖|maven|
|com.google.code.gson:gson|2.8.9|间接依赖|maven|
|com.alibaba.csp:sentinel-cluster-client-default|1.8.6|直接依赖|maven|
|com.github.vlsi.compactmap:compactmap|2.0|间接依赖|maven|
|org.hamcrest:hamcrest|2.2|间接依赖|maven|
|org.unbescape:unbescape|1.1.6.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator-autoconfigure|3.0.2|直接依赖|maven|
|org.springframework:spring-jcl|5.3.22|间接依赖|maven|
|io.seata:seata-spring-autoconfigure-core|1.5.0|间接依赖|maven|
|io.seata:seata-config-core|1.5.0|间接依赖|maven|
|io.seata:seata-config-apollo|1.5.0|间接依赖|maven|
|org.apache.yetus:audience-annotations|0.5.0|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.2.0|间接依赖|maven|
|io.seata:seata-spring-autoconfigure-client|1.7.0|间接依赖|maven|
|io.seata:seata-discovery-core|1.5.0|间接依赖|maven|
|net.java.dev.jna:jna|5.2.0|间接依赖|maven|
|com.netflix.archaius:archaius-core|0.7.6|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.87.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.14.1|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.3.4|间接依赖|maven|
|org.springframework.cloud:spring-cloud-config-server|4.0.0|直接依赖|maven|
|io.netty:netty-codec-smtp|4.1.79.Final|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.79.Final|间接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.87.Final|间接依赖|maven|
|org.postgresql:postgresql|42.3.6|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-webflux|3.0.2|直接依赖|maven|
|io.netty:netty-transport|4.1.87.Final|间接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.69|间接依赖|maven|
|io.netty:netty-codec-mqtt|4.1.87.Final|间接依赖|maven|
|org.springframework.security:spring-security-web|5.6.7|间接依赖|maven|
|com.beust:jcommander|1.72|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.3|间接依赖|maven|
|io.netty:netty-codec-mqtt|4.1.79.Final|间接依赖|maven|
|com.alibaba.cloud:spring-cloud-alibaba-commons|2022.0.0.0|直接依赖|maven|
|io.seata:seata-discovery-all|1.5.0|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter|4.0.0|间接依赖|maven|
|joda-time:joda-time|2.3|间接依赖|maven|
|mysql:mysql-connector-java|8.0.30|间接依赖|maven|
|io.grpc:grpc-context|1.17.1|间接依赖|maven|
|io.seata:seata-config-zk|1.5.0|间接依赖|maven|
|com.github.spotbugs:spotbugs-annotations|3.1.9|间接依赖|maven|
|com.alibaba.csp:sentinel-annotation-aspectj|1.8.6|直接依赖|maven|
|io.seata:seata-core|1.5.0|间接依赖|maven|
|org.springframework:spring-context-support|6.0.4|间接依赖|maven|
|io.github.openfeign.form:feign-form-spring|3.8.0|间接依赖|maven|
|io.opencensus:opencensus-api|0.17.0|间接依赖|maven|
|com.alibaba.csp:sentinel-datasource-apollo|1.8.6|直接依赖|maven|
|org.jetbrains:annotations|17.0.0|间接依赖|maven|
|javax.ws.rs:jsr311-api|1.1.1|间接依赖|maven|
|cglib:cglib|3.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.6.11|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|2.1.1|间接依赖|maven|
|com.alibaba.cloud:spring-cloud-starter-stream-rocketmq|2022.0.0.0|直接依赖|maven|
|io.seata:seata-serializer-seata|1.5.0|间接依赖|maven|
|com.alibaba:fastjson|1.2.83_noneautotype|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.2-2|间接依赖|maven|
|org.bouncycastle:bcutil-jdk15on|1.69|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|io.seata:seata-serializer-hessian|1.5.0|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-openfeign|4.0.0|直接依赖|maven|
|org.junit.jupiter:junit-jupiter-engine|5.7.2|间接依赖|maven|
|org.springframework.security:spring-security-core|5.6.7|间接依赖|maven|
|io.netty:netty-resolver|4.1.87.Final|间接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|com.alibaba:fastjson|2.0.22|直接依赖|maven|
|org.yaml:snakeyaml|1.29|间接依赖|maven|
|com.alibaba.cloud:integrated-common|2022.0.0.0|直接依赖|maven|
|io.seata:seata-discovery-consul|1.5.0|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|间接依赖|maven|
|org.springframework.boot:spring-boot|3.0.2|直接依赖|maven|
|com.alibaba:druid|1.2.6|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|2.0.6|间接依赖|maven|
|com.google.protobuf:protobuf-java-util|3.5.1|间接依赖|maven|
|org.apache.rocketmq:rocketmq-common|4.9.4|间接依赖|maven|
|redis.clients:jedis|3.7.1|间接依赖|maven|
|org.apache.sshd:sshd-common|2.9.2|间接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|3.0.2|间接依赖|maven|
|com.alibaba.csp:sentinel-transport-simple-http|1.8.6|直接依赖|maven|
|io.prometheus:simpleclient_common|0.12.0|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.32|直接依赖|maven|
|com.alibaba.cloud:rocketmq-example-common|2022.0.0.0|直接依赖|maven|
|io.seata:seata-serializer-fst|1.5.0|间接依赖|maven|
|org.objenesis:objenesis|2.5.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.3|间接依赖|maven|
|org.springframework.cloud:spring-cloud-commons|4.0.0|直接依赖|maven|
|org.springframework.security:spring-security-rsa|1.0.11.RELEASE|间接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.87.Final|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|org.springframework:spring-context|6.0.4|间接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5|5.1.5|间接依赖|maven|
|com.sun.jersey.contribs:jersey-apache-client4|1.19.1|间接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.15|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.7.22|间接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.79.Final|间接依赖|maven|
|org.springframework:spring-jdbc|6.0.4|间接依赖|maven|
|io.netty:netty-codec|4.1.79.Final|间接依赖|maven|
|com.esotericsoftware:reflectasm|1.11.3|间接依赖|maven|
|io.jsonwebtoken:jjwt-api|0.10.5|间接依赖|maven|
|io.grpc:grpc-stub|1.17.1|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.79.Final|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)