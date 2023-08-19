# redisson/redisson安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692961472240181248.svg)](https://www.murphysec.com/console/report/1692961472160489472/1692961472240181248)

仓库描述：Redisson - Easy Redis Java client with features of In-Memory Data Grid. Sync/Async/RxJava/Reactive API. Over 50 Redis based Java objects and services: Set, Multimap, SortedSet, Map, List, Queue, Deque, Semaphore, Lock, AtomicLong, Map Reduce, Bloom filter, Spring Cache, Tomcat, Scheduler, JCache API, Hibernate, RPC, local cache ...

仓库地址：[https://github.com/redisson/redisson](https://github.com/redisson/redisson)

| star：21603 | watch：890 | fork：5129 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-19 00:58:22 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-20 02:27:11 | 组件总数：714 | 漏洞总数：82 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Spring Data Commons <2.0.6.RELEASE  远程代码执行漏洞|代码注入|[MPS-2018-4454](https://www.oscs1024.com/hd/MPS-2018-4454)|CVE-2018-1273|严重|
|Spring Data Commons 无限制的资源分配漏洞|不加限制或调节的资源分配|[MPS-2018-5028](https://www.oscs1024.com/hd/MPS-2018-5028)|CVE-2018-1274|高危|
|hibernate-core <5.4.24.Final 存在 SQL 注入漏洞|SQL注入|[MPS-2020-16768](https://www.oscs1024.com/hd/MPS-2020-16768)|CVE-2020-25638|高危|
|dom4j SaxReader函数存在 XXE 漏洞|XXE|[MPS-2020-6967](https://www.oscs1024.com/hd/MPS-2020-6967)|CVE-2020-10683|严重|
|Hibernate 存在 SQL 注入漏洞|SQL注入|[MPS-2020-9908](https://www.oscs1024.com/hd/MPS-2020-9908)|CVE-2019-14900|中危|
|Object Computing micronaut 路径遍历漏洞|路径遍历|[MPS-2021-10581](https://www.oscs1024.com/hd/MPS-2021-10581)|CVE-2021-32769|高危|
|Netty <4.1.59.Final 存在不安全的临时文件漏洞||[MPS-2021-1580](https://www.oscs1024.com/hd/MPS-2021-1580)|CVE-2021-21290|中危|
|jsoup <1.14.2 存在拒绝服务漏洞||[MPS-2021-17634](https://www.oscs1024.com/hd/MPS-2021-17634)|CVE-2021-37714|高危|
|Spring Framework <5.3.14 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18854](https://www.oscs1024.com/hd/MPS-2021-18854)|CVE-2021-22060|中危|
|Pivotal Spring Framework 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18890](https://www.oscs1024.com/hd/MPS-2021-18890)|CVE-2021-22096|中危|
|io.netty:netty-codec-http2 <4.1.60.Final 存在 http 请求走私漏洞|HTTP请求走私|[MPS-2021-2435](https://www.oscs1024.com/hd/MPS-2021-2435)|CVE-2021-21295|中危|
|Oracle Java SE Oracle GraalVM Enterprise Edition  输入验证错误漏洞|访问控制不当|[MPS-2021-26664](https://www.oscs1024.com/hd/MPS-2021-26664)|CVE-2021-35567|中危|
|Oracle Java SE Oracle GraalVM Enterprise Edition 输入验证错误漏洞|访问控制不当|[MPS-2021-26676](https://www.oscs1024.com/hd/MPS-2021-26676)|CVE-2021-35578|中危|
|Oracle Java SE Oracle GraalVM Enterprise Edition 输入验证错误漏洞|通过时间差异性导致的信息暴露|[MPS-2021-26703](https://www.oscs1024.com/hd/MPS-2021-26703)|CVE-2021-35603|低危|
|Netty Bzip2Decoder 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28116](https://www.oscs1024.com/hd/MPS-2021-28116)|CVE-2021-37136|高危|
|Netty 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28117](https://www.oscs1024.com/hd/MPS-2021-28117)|CVE-2021-37137|高危|
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
|Netty <4.1.71.Final 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2021-36922](https://www.oscs1024.com/hd/MPS-2021-36922)|CVE-2021-43797|中危|
|Object Computing micronaut 安全漏洞|拒绝服务|[MPS-2021-37058](https://www.oscs1024.com/hd/MPS-2021-37058)|CVE-2022-21700|中危|
|Red Hat Resteasy 跨站脚本漏洞|XSS|[MPS-2021-7858](https://www.oscs1024.com/hd/MPS-2021-7858)|CVE-2021-20293|中危|
|Vmware Spring Framework 安全漏洞|不加限制或调节的资源分配|[MPS-2022-1080](https://www.oscs1024.com/hd/MPS-2022-1080)|CVE-2022-22950|中危|
|Pivotal Spring Framework 安全限制绕过漏洞|大小写敏感处理不恰当|[MPS-2022-1098](https://www.oscs1024.com/hd/MPS-2022-1098)|CVE-2022-22968|中危|
|Spring Framework spring-beans 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1101](https://www.oscs1024.com/hd/MPS-2022-1101)|CVE-2022-22970|中危|
|io.netty:netty-codec-http <4.1.53.Final 存在拒绝服务漏洞|拒绝服务|[MPS-2022-12064](https://www.oscs1024.com/hd/MPS-2022-12064)||中危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|io.quarkus:quarkus-core 存在信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-12335](https://www.oscs1024.com/hd/MPS-2022-12335)||中危|
|FasterXML Jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2022-12500](https://www.oscs1024.com/hd/MPS-2022-12500)||中危|
|org.apache.maven.shared:maven-shared-utils 存在命令注入漏洞|命令注入|[MPS-2022-12562](https://www.oscs1024.com/hd/MPS-2022-12562)||高危|
|Netty 存在信息泄露漏洞||[MPS-2022-3790](https://www.oscs1024.com/hd/MPS-2022-3790)|CVE-2022-24823|中危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|jsoup <1.15.3 存在反射型 XSS 漏洞|XSS|[MPS-2022-51547](https://www.oscs1024.com/hd/MPS-2022-51547)|CVE-2022-36033|中危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|Netty <4.1.86.Final 存在拒绝服务漏洞|未经控制的递归|[MPS-2022-58518](https://www.oscs1024.com/hd/MPS-2022-58518)|CVE-2022-41881|中危|
|Netty <4.1.86.Final 存在 CRLF 注入漏洞||[MPS-2022-58552](https://www.oscs1024.com/hd/MPS-2022-58552)|CVE-2022-41915|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Quarkus 安全漏洞|OWASP 前十名的弱点（2017 年）|[MPS-2022-65506](https://www.oscs1024.com/hd/MPS-2022-65506)|CVE-2022-4147|高危|
|spring-beans 远程代码执行漏洞(Spring4Shell)|表达式语言注入|[MPS-2022-6820](https://www.oscs1024.com/hd/MPS-2022-6820)|CVE-2022-22965|严重|
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
|Apache Maven Shared Utils 系统命令注入漏洞|命令注入|[MPS-2022-9177](https://www.oscs1024.com/hd/MPS-2022-9177)|CVE-2022-29599|严重|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Red Hat quarkus-vertx-http 跨站脚本漏洞|XSS|[MPS-2023-0173](https://www.oscs1024.com/hd/MPS-2023-0173)|CVE-2023-0044|中危|
|Resteasy 安全漏洞|输入验证不恰当|[MPS-2023-2844](https://www.oscs1024.com/hd/MPS-2023-2844)|CVE-2023-0482|中危|
|Eclipse Vertx-web 路径遍历漏洞|路径遍历|[MPS-2023-3321](https://www.oscs1024.com/hd/MPS-2023-3321)|CVE-2023-24815|中危|
|jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2023-8438](https://www.oscs1024.com/hd/MPS-2023-8438)|CVE-2021-46877|中危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.springframework.data:spring-data-commons|1.12.11.RELEASE|2.0.6.RELEASE|间接依赖|建议修复|C:1|H:1|M:0|L:0|
|org.springframework:spring-beans|5.3.13|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework:spring-context|5.2.14.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|io.quarkus:quarkus-vertx-http|1.13.6.Final|3.2.1.final|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|org.springframework:spring-beans|5.2.13.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.yaml:snakeyaml|1.33|2.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.28|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|io.netty:netty-codec|4.1.49.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.14.2||间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.15.2||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.12.3|2.14.0-rc1|间接依赖|建议修复|C:0|H:1|M:5|L:0|
|org.springframework:spring-context|5.0.13.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|io.netty:netty-handler|4.1.94.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-context|4.2.9.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.hibernate:hibernate-core|4.3.11.Final|5.4.24.Final|直接依赖|建议修复|C:0|H:1|M:1|L:0|
|io.netty:netty-handler|4.1.49.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|org.hibernate:hibernate-core|5.2.18.Final|5.4.24.Final|直接依赖|建议修复|C:0|H:1|M:1|L:0|
|org.springframework:spring-context|5.1.19.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.dom4j:dom4j|2.1.1|2.1.2|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework:spring-context|4.1.9.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|dom4j:dom4j|1.6.1||间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.yaml:snakeyaml|1.26|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|io.netty:netty-handler|4.1.86.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-context|4.3.25.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-beans|4.1.9.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework:spring-beans|4.2.9.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework:spring-beans|5.0.13.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|io.micronaut:micronaut-core|2.5.0|3.2.7|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|org.springframework:spring-beans|4.3.25.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework:spring-beans|5.2.14.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework:spring-context|5.3.13|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.apache.maven.shared:maven-shared-utils|3.2.1|3.3.3|间接依赖|建议修复|C:1|H:1|M:0|L:0|
|org.springframework:spring-context|5.2.13.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-beans|5.1.19.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.hibernate:hibernate-core|5.1.16.Final|5.4.24.Final|直接依赖|建议修复|C:0|H:1|M:1|L:0|
|io.netty:netty-codec-haproxy|4.1.86.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|4.3.25.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.springframework:spring-core|4.2.9.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-core|5.3.24|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-http|4.1.86.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|5.0.13.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|com.google.guava:guava|30.1-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.micronaut:micronaut-http|2.5.0|3.2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.graalvm.sdk:graal-sdk|22.3.2|22.3.3|间接依赖|可选修复|C:0|H:0|M:1|L:5|
|org.springframework:spring-expression|5.2.13.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|io.netty:netty-transport-native-epoll|4.1.49.Final|4.1.59.Final|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|5.3.19|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-expression|4.1.9.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.springframework:spring-core|4.1.9.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-core|5.3.13|6.0.7|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-expression|4.2.9.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.jboss.resteasy:resteasy-core|4.5.12.Final|4.7.8.final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-expression|5.3.24|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-core|5.0.13.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-core|5.3.19|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.graalvm.sdk:graal-sdk|21.0.0|22.3.3|间接依赖|可选修复|C:0|H:1|M:20|L:10|
|org.springframework:spring-expression|5.3.13|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.jboss.resteasy:resteasy-core|4.7.7.Final|4.7.8.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.jsoup:jsoup|1.12.1|1.15.3|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.springframework:spring-expression|5.2.14.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|io.vertx:vertx-web|4.3.7|4.3.8|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-beans|5.3.19|5.3.20|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|5.1.19.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|io.netty:netty-codec-http|4.1.49.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:5|L:0|
|org.springframework:spring-core|5.1.19.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-core|4.3.25.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.graalvm.sdk:graal-sdk|22.3.0|22.3.3|间接依赖|可选修复|C:0|H:1|M:4|L:8|
|io.quarkus:quarkus-core|1.13.6.Final|2.6.0.CR1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-http2|4.1.49.Final|4.1.61.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-core|5.2.13.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|org.springframework:spring-core|5.2.14.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|io.netty:netty-common|4.1.49.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|596|Low|
|EPL-1.0|13|Low|
|BSD-3-Clause|18|Low|
|LGPL-2.1-or-later|9|Low|
|UPL-1.0|3|Low|
|CDDL-1.1|2|Low|
|MIT|14|Low|
|LGPL-2.1|2|Medium|
|BSD-2-Clause|4|Low|
|EPL-2.0|24|Low|
|GPL-2.0-with-classpath-exception|1|Medium|
|MIT-0|2|Low|
|CDDL-1.0|1|Low|
|MPL-1.1|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|io.netty:netty-codec|4.1.49.Final|间接依赖|maven|
|io.smallrye.reactive:mutiny-smallrye-context-propagation|2.3.1|间接依赖|maven|
|org.jboss.logging:jboss-logging-annotations|1.2.0.Beta1|间接依赖|maven|
|io.helidon.common:helidon-common-service-loader|3.2.1|间接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|2.3.1|间接依赖|maven|
|org.springframework:spring-aop|5.2.14.RELEASE|间接依赖|maven|
|io.quarkus:quarkus-vertx-http-dev-console-runtime-spi|1.13.6.Final|间接依赖|maven|
|org.springframework:spring-core|5.1.19.RELEASE|间接依赖|maven|
|org.springframework.data:spring-data-redis|2.1.21.RELEASE|直接依赖|maven|
|io.vertx:vertx-bridge-common|4.3.7|间接依赖|maven|
|org.springframework.data:spring-data-commons|1.12.11.RELEASE|间接依赖|maven|
|org.springframework:spring-core|5.3.24|间接依赖|maven|
|io.smallrye.common:smallrye-common-constraint|2.1.0|间接依赖|maven|
|javax.cache:cache-api|1.1.1|直接依赖|maven|
|org.springframework.data:spring-data-keyvalue|2.6.10|间接依赖|maven|
|com.aayushatharva.brotli4j:native-linux-x86_64|1.8.0|间接依赖|maven|
|io.quarkus:quarkus-resteasy-common|1.13.6.Final|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.12.3|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.18.0|间接依赖|maven|
|org.eclipse.microprofile.context-propagation:microprofile-context-propagation-api|1.2|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.12.3|间接依赖|maven|
|org.springframework.data:spring-data-keyvalue|2.0.14.RELEASE|间接依赖|maven|
|io.quarkus.security:quarkus-security|1.1.4.Final|间接依赖|maven|
|io.netty:netty-codec|4.1.94.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|3.1.1|间接依赖|maven|
|io.quarkus:quarkus-arc-deployment|3.2.0.Final|直接依赖|maven|
|org.ow2.asm:asm-tree|9.4|间接依赖|maven|
|org.springframework:spring-expression|4.2.9.RELEASE|间接依赖|maven|
|org.springframework:spring-beans|5.3.27|间接依赖|maven|
|io.helidon.config:helidon-config-object-mapping|3.2.1|间接依赖|maven|
|io.micronaut:micronaut-management|3.10.1|直接依赖|maven|
|org.fusesource.jansi:jansi|1.18|间接依赖|maven|
|io.vertx:vertx-codegen|4.3.7|间接依赖|maven|
|org.hibernate.common:hibernate-commons-annotations|5.1.2.Final|间接依赖|maven|
|org.graalvm.sdk:graal-sdk|22.3.2|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.96.Final|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.96.Final|间接依赖|maven|
|io.netty:netty-transport|4.1.49.Final|间接依赖|maven|
|org.springframework:spring-context|4.2.9.RELEASE|间接依赖|maven|
|io.micronaut:micronaut-aop|4.0.0|间接依赖|maven|
|org.ow2.asm:asm-analysis|9.4|间接依赖|maven|
|io.micronaut:micronaut-session|3.10.1|直接依赖|maven|
|org.springframework:spring-expression|6.0.9|间接依赖|maven|
|com.sun.istack:istack-commons-runtime|3.0.7|间接依赖|maven|
|org.springframework:spring-beans|5.0.13.RELEASE|间接依赖|maven|
|io.netty:netty-codec-http|4.1.86.Final|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|间接依赖|maven|
|org.mybatis:mybatis|3.5.6|直接依赖|maven|
|org.antlr:antlr4-runtime|4.10.1|间接依赖|maven|
|org.springframework:spring-core|5.2.13.RELEASE|间接依赖|maven|
|org.lz4:lz4-java|1.8.0|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.32|间接依赖|maven|
|io.quarkus:quarkus-core-deployment|1.13.6.Final|间接依赖|maven|
|io.smallrye.common:smallrye-common-function|1.13.2|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.5.0.Final|间接依赖|maven|
|org.springframework:spring-beans|5.3.24|间接依赖|maven|
|com.github.spotbugs:spotbugs-annotations|4.0.3|间接依赖|maven|
|io.netty:netty-buffer|4.1.86.Final|间接依赖|maven|
|org.springframework.data:spring-data-commons|2.2.13.RELEASE|间接依赖|maven|
|io.micronaut.cache:micronaut-cache-core|3.5.0|直接依赖|maven|
|org.springframework:spring-jcl|5.1.19.RELEASE|间接依赖|maven|
|org.springframework:spring-beans|5.2.14.RELEASE|间接依赖|maven|
|org.springframework.data:spring-data-redis|2.7.11|直接依赖|maven|
|org.jboss:jandex|2.4.2.Final|间接依赖|maven|
|io.smallrye.reactive:smallrye-mutiny-vertx-web-common|3.5.0|间接依赖|maven|
|io.quarkus:quarkus-core-deployment|2.16.4.Final|间接依赖|maven|
|io.quarkus.arc:arc-processor|3.2.0.Final|间接依赖|maven|
|io.helidon.config:helidon-config-mp|3.2.1|间接依赖|maven|
|io.smallrye:smallrye-context-propagation-storage|2.1.0|间接依赖|maven|
|io.quarkus.arc:arc|1.13.6.Final|间接依赖|maven|
|org.springframework:spring-context|5.3.13|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.9|间接依赖|maven|
|org.springframework:spring-aop|5.3.19|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.96.Final|间接依赖|maven|
|io.quarkus:quarkus-bootstrap-runner|2.16.4.Final|间接依赖|maven|
|org.springframework.data:spring-data-redis|1.7.11.RELEASE|直接依赖|maven|
|io.quarkus.arc:arc-processor|1.13.6.Final|间接依赖|maven|
|org.springframework:spring-beans|5.2.13.RELEASE|间接依赖|maven|
|org.springframework:spring-tx|5.1.19.RELEASE|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.10.1|直接依赖|maven|
|commons-io:commons-io|2.8.0|间接依赖|maven|
|org.hibernate.common:hibernate-commons-annotations|5.0.1.Final|间接依赖|maven|
|xml-apis:xml-apis|1.0.b2|间接依赖|maven|
|io.smallrye.config:smallrye-config-common|1.13.1|间接依赖|maven|
|org.springframework.data:spring-data-redis|2.0.14.RELEASE|直接依赖|maven|
|org.springframework.data:spring-data-commons|2.0.14.RELEASE|间接依赖|maven|
|org.springframework:spring-tx|5.3.24|间接依赖|maven|
|org.codehaus.plexus:plexus-component-annotations|2.1.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.14.2|间接依赖|maven|
|org.springframework:spring-beans|4.2.9.RELEASE|间接依赖|maven|
|org.glassfish.jaxb:txw2|2.3.1|间接依赖|maven|
|io.netty:netty-transport|4.1.86.Final|间接依赖|maven|
|org.jboss.resteasy:resteasy-core|4.7.7.Final|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.86.Final|间接依赖|maven|
|com.fasterxml:classmate|1.3.0|间接依赖|maven|
|org.apache.maven:maven-artifact|3.8.1|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|3.0.2|间接依赖|maven|
|io.smallrye.reactive:smallrye-mutiny-vertx-runtime|2.30.1|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.49.Final|直接依赖|maven|
|io.quarkus:quarkus-development-mode-spi|2.16.4.Final|间接依赖|maven|
|org.apache.maven.resolver:maven-resolver-api|1.6.2|间接依赖|maven|
|io.quarkus:quarkus-resteasy|1.13.6.Final|直接依赖|maven|
|io.smallrye.reactive:vertx-mutiny-generator|2.30.1|间接依赖|maven|
|org.eclipse.microprofile.config:microprofile-config-api|2.0.1|间接依赖|maven|
|io.quarkus:quarkus-smallrye-context-propagation|2.16.4.Final|间接依赖|maven|
|io.netty:netty-handler|4.1.49.Final|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.49.Final|间接依赖|maven|
|io.netty:netty-common|4.1.94.Final|间接依赖|maven|
|io.smallrye.common:smallrye-common-constraint|1.13.2|间接依赖|maven|
|org.jboss:jandex|2.2.3.Final|间接依赖|maven|
|io.quarkus:quarkus-arc|2.16.4.Final|直接依赖|maven|
|io.quarkus:quarkus-ide-launcher|2.16.4.Final|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.1.Final|间接依赖|maven|
|io.quarkus:quarkus-class-change-agent|3.2.0.Final|间接依赖|maven|
|org.hibernate.common:hibernate-commons-annotations|4.0.5.Final|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|com.google.guava:guava|30.1-jre|间接依赖|maven|
|org.checkerframework:checker-qual|3.33.0|间接依赖|maven|
|io.smallrye.config:smallrye-config|3.3.0|间接依赖|maven|
|org.yaml:snakeyaml|1.33|间接依赖|maven|
|io.micronaut.cache:micronaut-cache-core|2.4.0|直接依赖|maven|
|io.netty:netty-handler-proxy|4.1.49.Final|间接依赖|maven|
|org.jboss.logmanager:jboss-logmanager-embedded|1.1.1|间接依赖|maven|
|io.micronaut.cache:micronaut-cache-core|4.0.0|直接依赖|maven|
|org.springframework:spring-beans|6.0.9|间接依赖|maven|
|org.junit.jupiter:junit-jupiter|5.9.3|间接依赖|maven|
|io.helidon.common:helidon-common-key-util|2.5.1|间接依赖|maven|
|io.smallrye.reactive:smallrye-mutiny-vertx-auth-common|3.5.0|间接依赖|maven|
|io.helidon.config:helidon-config-mp|2.5.1|间接依赖|maven|
|org.apache.maven:maven-core|3.8.1|间接依赖|maven|
|io.netty:netty-common|4.1.96.Final|直接依赖|maven|
|com.aayushatharva.brotli4j:brotli4j|1.8.0|间接依赖|maven|
|org.hibernate.common:hibernate-commons-annotations|6.0.6.Final|间接依赖|maven|
|jakarta.persistence:jakarta.persistence-api|3.1.0|间接依赖|maven|
|io.smallrye:smallrye-fault-tolerance-vertx|5.6.0|间接依赖|maven|
|io.smallrye.reactive:smallrye-mutiny-vertx-bridge-common|2.30.1|间接依赖|maven|
|io.quarkus.security:quarkus-security|2.0.2.Final|间接依赖|maven|
|io.netty:netty-resolver|4.1.94.Final|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|org.jboss.threads:jboss-threads|3.4.3.Final|间接依赖|maven|
|io.quarkus:quarkus-arc-deployment|1.13.6.Final|直接依赖|maven|
|jakarta.activation:jakarta.activation-api|2.1.2|间接依赖|maven|
|io.smallrye.common:smallrye-common-vertx-context|1.13.2|间接依赖|maven|
|com.esotericsoftware:kryo|5.5.0|直接依赖|maven|
|io.vertx:vertx-auth-common|4.3.7|间接依赖|maven|
|io.quarkus:quarkus-core|2.16.4.Final|间接依赖|maven|
|org.springframework:spring-jcl|5.3.27|间接依赖|maven|
|org.springframework:spring-expression|5.2.13.RELEASE|间接依赖|maven|
|org.apache.maven.resolver:maven-resolver-connector-basic|1.6.2|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.94.Final|间接依赖|maven|
|io.smallrye.common:smallrye-common-io|2.1.0|间接依赖|maven|
|io.smallrye.common:smallrye-common-vertx-context|2.1.0|间接依赖|maven|
|org.springframework:spring-core|6.0.8|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.12.3|间接依赖|maven|
|io.micronaut:micronaut-core-reactive|4.0.0|间接依赖|maven|
|io.quarkus:quarkus-vertx-core|1.13.6.Final|间接依赖|maven|
|io.micronaut:micronaut-router|4.0.0|间接依赖|maven|
|org.redisson:redisson-quarkus-20|3.23.4-SNAPSHOT|直接依赖|maven|
|io.smallrye.common:smallrye-common-classloader|1.5.0|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.21|间接依赖|maven|
|com.google.inject:guice|4.2.1|间接依赖|maven|
|org.apache.maven:maven-model-builder|3.8.1|间接依赖|maven|
|io.projectreactor:reactor-core|3.4.21|间接依赖|maven|
|org.springframework:spring-oxm|4.2.9.RELEASE|间接依赖|maven|
|org.springframework:spring-expression|5.3.27|间接依赖|maven|
|org.springframework:spring-expression|5.2.14.RELEASE|间接依赖|maven|
|org.jboss.threads:jboss-threads|3.5.0.Final|间接依赖|maven|
|io.vertx:vertx-bridge-common|4.4.4|间接依赖|maven|
|io.quarkus:quarkus-class-change-agent|1.13.6.Final|间接依赖|maven|
|org.apache.maven.resolver:maven-resolver-impl|1.6.2|间接依赖|maven|
|org.springframework:spring-aop|5.3.13|间接依赖|maven|
|org.apache.maven:maven-resolver-provider|3.8.1|间接依赖|maven|
|org.sonatype.plexus:plexus-cipher|1.4|间接依赖|maven|
|org.springframework:spring-jcl|5.0.13.RELEASE|间接依赖|maven|
|io.micronaut:micronaut-inject|2.5.0|间接依赖|maven|
|jakarta.interceptor:jakarta.interceptor-api|2.1.0|间接依赖|maven|
|io.micronaut:micronaut-jackson-databind|3.5.4|间接依赖|maven|
|org.springframework:spring-aop|6.0.8|间接依赖|maven|
|io.helidon.common:helidon-common-crypto|3.2.1|间接依赖|maven|
|org.redisson:redisson|3.23.4-SNAPSHOT|直接依赖|maven|
|org.eclipse.angus:angus-activation|2.0.0|间接依赖|maven|
|io.vertx:vertx-core|4.4.4|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|3.1.5|间接依赖|maven|
|io.helidon.microprofile.config:helidon-microprofile-config|2.5.1|直接依赖|maven|
|io.smallrye.common:smallrye-common-annotation|1.13.2|间接依赖|maven|
|io.helidon.config:helidon-config-encryption|3.2.1|间接依赖|maven|
|org.dom4j:dom4j|2.1.1|间接依赖|maven|
|org.apache.maven.shared:maven-shared-utils|3.2.1|间接依赖|maven|
|io.netty:netty-handler|4.1.96.Final|直接依赖|maven|
|io.quarkus:quarkus-bootstrap-gradle-resolver|1.13.6.Final|间接依赖|maven|
|org.springframework:spring-beans|6.0.8|间接依赖|maven|
|org.ow2.asm:asm-util|9.4|间接依赖|maven|
|io.quarkus:quarkus-smallrye-context-propagation|3.2.0.Final|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.25|间接依赖|maven|
|io.micronaut:micronaut-context-propagation|4.0.0|间接依赖|maven|
|com.ibm.async:asyncutil|0.1.0|间接依赖|maven|
|org.ow2.asm:asm-commons|9.5|间接依赖|maven|
|org.glassfish.jaxb:jaxb-core|4.0.2|间接依赖|maven|
|io.smallrye.common:smallrye-common-io|1.5.0|间接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|org.apache.maven.resolver:maven-resolver-spi|1.6.2|间接依赖|maven|
|jakarta.inject:jakarta.inject-api|1.0|间接依赖|maven|
|org.jboss:jandex|2.4.3.Final|直接依赖|maven|
|org.springframework:spring-tx|4.1.9.RELEASE|间接依赖|maven|
|com.sun.xml.fastinfoset:FastInfoset|1.2.15|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|3.1.1|直接依赖|maven|
|io.quarkus:quarkus-core|1.13.6.Final|间接依赖|maven|
|io.quarkus:quarkus-vertx-latebound-mdc-provider|2.16.4.Final|间接依赖|maven|
|org.graalvm.sdk:graal-sdk|22.3.0|间接依赖|maven|
|org.springframework.data:spring-data-commons|3.1.0|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.49.Final|间接依赖|maven|
|org.jboss.threads:jboss-threads|3.2.0.Final|间接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.94.Final|直接依赖|maven|
|io.github.crac:org-crac|0.1.3|间接依赖|maven|
|org.springframework:spring-expression|5.3.24|间接依赖|maven|
|io.quarkus:quarkus-vertx-http|1.13.6.Final|间接依赖|maven|
|org.hibernate:hibernate-core|5.2.18.Final|直接依赖|maven|
|io.quarkus.arc:arc-processor|2.16.4.Final|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.21|间接依赖|maven|
|org.eclipse.angus:angus-activation|2.0.1|间接依赖|maven|
|org.springframework:spring-tx|6.0.10|间接依赖|maven|
|org.jboss.spec.javax.xml.bind:jboss-jaxb-api_2.3_spec|2.0.0.Final|间接依赖|maven|
|io.quarkus:quarkus-vertx-http-dev-ui-spi|3.2.0.Final|间接依赖|maven|
|org.springframework.data:spring-data-redis|3.0.5|直接依赖|maven|
|org.jboss.slf4j:slf4j-jboss-logmanager|1.2.0.Final|间接依赖|maven|
|org.jboss.resteasy:resteasy-core|4.5.12.Final|间接依赖|maven|
|org.springframework:spring-context|4.3.25.RELEASE|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.94.Final|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.5.1.Final|间接依赖|maven|
|org.springframework:spring-tx|5.3.19|间接依赖|maven|
|org.hibernate.javax.persistence:hibernate-jpa-2.1-api|1.0.0.Final|间接依赖|maven|
|io.quarkus:quarkus-arc-deployment|2.16.4.Final|直接依赖|maven|
|javax.validation:validation-api|2.0.1.Final|间接依赖|maven|
|io.quarkus:quarkus-credentials|2.16.4.Final|间接依赖|maven|
|org.springframework:spring-beans|5.3.13|间接依赖|maven|
|io.quarkus:quarkus-vertx-http-dev-console-spi|3.2.0.Final|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|jakarta.ws.rs:jakarta.ws.rs-api|3.1.0|间接依赖|maven|
|org.springframework:spring-tx|5.3.27|间接依赖|maven|
|org.springframework:spring-expression|5.3.19|间接依赖|maven|
|io.smallrye.config:smallrye-config|2.13.3|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.17.0|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.86.Final|间接依赖|maven|
|org.jboss.spec.javax.transaction:jboss-transaction-api_1.2_spec|1.0.0.Final|间接依赖|maven|
|org.jboss.resteasy:resteasy-core-spi|6.2.4.Final|间接依赖|maven|
|org.springframework:spring-context-support|5.1.19.RELEASE|间接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|antlr:antlr|2.7.7|间接依赖|maven|
|io.vertx:vertx-core|4.3.7|间接依赖|maven|
|org.springframework:spring-aop|6.0.9|间接依赖|maven|
|org.eclipse.microprofile.context-propagation:microprofile-context-propagation-api|1.0.1|间接依赖|maven|
|org.ow2.asm:asm-tree|9.5|间接依赖|maven|
|io.quarkus:quarkus-core|3.2.0.Final|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.14.5|直接依赖|maven|
|io.quarkus:quarkus-vertx-http|3.2.0.Final|间接依赖|maven|
|io.smallrye.common:smallrye-common-constraint|1.5.0|间接依赖|maven|
|io.smallrye.reactive:smallrye-mutiny-vertx-runtime|3.5.0|间接依赖|maven|
|io.helidon.config:helidon-config-yaml-mp|3.2.1|间接依赖|maven|
|org.springframework.data:spring-data-redis|2.5.12|直接依赖|maven|
|org.eclipse.sisu:org.eclipse.sisu.inject|0.3.4|间接依赖|maven|
|io.smallrye.reactive:mutiny|0.14.0|间接依赖|maven|
|io.vertx:vertx-web|3.9.6|间接依赖|maven|
|io.helidon.common:helidon-common|3.2.1|间接依赖|maven|
|org.springframework:spring-context|6.0.8|间接依赖|maven|
|com.sun.istack:istack-commons-runtime|4.1.1|间接依赖|maven|
|io.quarkus:quarkus-bootstrap-runner|3.2.0.Final|间接依赖|maven|
|io.micronaut:micronaut-core|3.10.1|间接依赖|maven|
|org.jboss.spec.javax.transaction:jboss-transaction-api_1.2_spec|1.1.1.Final|间接依赖|maven|
|org.springframework:spring-aop|5.3.27|间接依赖|maven|
|org.springframework.data:spring-data-keyvalue|3.1.0|间接依赖|maven|
|io.helidon.config:helidon-config-encryption|2.5.1|间接依赖|maven|
|org.springframework:spring-context|5.2.14.RELEASE|间接依赖|maven|
|io.quarkus:quarkus-bootstrap-maven-resolver|1.13.6.Final|间接依赖|maven|
|org.jboss.resteasy:resteasy-cdi|6.2.4.Final|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.3.0.Final|间接依赖|maven|
|com.sun.activation:jakarta.activation|1.2.1|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|io.smallrye.common:smallrye-common-expression|1.5.0|间接依赖|maven|
|io.smallrye:smallrye-context-propagation-storage|1.2.2|间接依赖|maven|
|io.smallrye.reactive:smallrye-mutiny-vertx-web|2.30.1|间接依赖|maven|
|io.quarkus.gizmo:gizmo|1.0.7.Final|间接依赖|maven|
|io.micronaut:micronaut-management|2.5.12|直接依赖|maven|
|org.objenesis:objenesis|3.3|间接依赖|maven|
|org.springframework:spring-core|4.3.25.RELEASE|间接依赖|maven|
|org.springframework:spring-core|5.3.27|间接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.86.Final|间接依赖|maven|
|org.springframework:spring-context-support|5.3.27|间接依赖|maven|
|org.springframework:spring-tx|6.0.8|间接依赖|maven|
|io.smallrye:smallrye-context-propagation-api|2.1.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-actuator|3.1.1|直接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|3.1.6|间接依赖|maven|
|org.redisson:redisson-quarkus-16|3.23.4-SNAPSHOT|直接依赖|maven|
|io.quarkus.gizmo:gizmo|1.6.1.Final|间接依赖|maven|
|org.springframework.data:spring-data-redis|2.4.15|直接依赖|maven|
|org.slf4j:slf4j-api|2.0.7|间接依赖|maven|
|org.jboss.marshalling:jboss-marshalling-river|2.0.11.Final|直接依赖|maven|
|io.vertx:vertx-auth-common|3.9.6|间接依赖|maven|
|io.quarkus:quarkus-security-runtime-spi|1.13.6.Final|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.94.Final|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.96.Final|直接依赖|maven|
|org.ow2.asm:asm-analysis|9.1|间接依赖|maven|
|org.springframework.data:spring-data-commons|2.3.9.RELEASE|间接依赖|maven|
|io.micronaut:micronaut-session|2.5.12|直接依赖|maven|
|org.apache.maven:maven-settings|3.8.1|间接依赖|maven|
|io.quarkus:quarkus-development-mode-spi|3.2.0.Final|间接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.86.Final|直接依赖|maven|
|io.smallrye:smallrye-fault-tolerance-vertx|6.2.4|间接依赖|maven|
|org.springframework:spring-context-support|4.3.25.RELEASE|间接依赖|maven|
|org.apache.maven.resolver:maven-resolver-transport-wagon|1.6.2|间接依赖|maven|
|io.quarkus:quarkus-resteasy|2.16.4.Final|直接依赖|maven|
|org.eclipse.sisu:org.eclipse.sisu.plexus|0.3.4|间接依赖|maven|
|org.jboss.spec.javax.ws.rs:jboss-jaxrs-api_2.1_spec|2.0.1.Final|间接依赖|maven|
|org.springframework:spring-tx|5.3.13|间接依赖|maven|
|org.apache.maven:maven-plugin-api|3.8.1|间接依赖|maven|
|org.sonatype.plexus:plexus-sec-dispatcher|1.4|间接依赖|maven|
|org.eclipse.microprofile.config:microprofile-config-api|3.0.3|直接依赖|maven|
|io.micronaut:micronaut-context|3.5.4|间接依赖|maven|
|org.springframework:spring-beans|5.1.19.RELEASE|间接依赖|maven|
|org.springframework:spring-jcl|5.2.14.RELEASE|间接依赖|maven|
|org.ow2.asm:asm-analysis|9.5|间接依赖|maven|
|io.micronaut:micronaut-jackson-core|3.5.4|间接依赖|maven|
|org.springframework:spring-oxm|6.0.9|间接依赖|maven|
|io.quarkus:quarkus-netty-deployment|3.2.0.Final|直接依赖|maven|
|org.redisson:redisson-quarkus-30|3.23.4-SNAPSHOT|直接依赖|maven|
|io.smallrye.common:smallrye-common-function|2.1.0|间接依赖|maven|
|io.vertx:vertx-core|3.9.6|间接依赖|maven|
|io.vertx:vertx-auth-common|4.4.4|间接依赖|maven|
|commons-cli:commons-cli|1.4|间接依赖|maven|
|io.micronaut:micronaut-aop|3.5.4|间接依赖|maven|
|io.netty:netty-codec-haproxy|4.1.86.Final|间接依赖|maven|
|io.helidon.common:helidon-common|2.5.1|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|org.springframework:spring-tx|4.2.9.RELEASE|间接依赖|maven|
|io.micronaut:micronaut-runtime|3.5.4|间接依赖|maven|
|org.springframework.data:spring-data-commons|3.1.1|间接依赖|maven|
|io.smallrye.common:smallrye-common-expression|2.1.0|间接依赖|maven|
|org.springframework:spring-context|5.0.13.RELEASE|间接依赖|maven|
|io.quarkus:quarkus-credentials|3.2.0.Final|间接依赖|maven|
|org.redisson:redisson-spring-data-31|3.23.4-SNAPSHOT|直接依赖|maven|
|org.springframework.data:spring-data-commons|2.4.15|间接依赖|maven|
|io.micronaut:micronaut-json-core|3.5.4|间接依赖|maven|
|org.slf4j:slf4j-api|2.0.6|间接依赖|maven|
|io.quarkus:quarkus-ide-launcher|1.13.6.Final|间接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|org.apache.maven:maven-embedder|3.8.1|间接依赖|maven|
|io.smallrye.reactive:mutiny|2.3.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.15.2|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.30|间接依赖|maven|
|io.netty.incubator:netty-incubator-transport-classes-io_uring|0.0.21.Final|间接依赖|maven|
|org.yaml:snakeyaml|1.26|间接依赖|maven|
|org.springframework:spring-core|5.2.14.RELEASE|间接依赖|maven|
|io.micronaut:micronaut-management|4.0.0|直接依赖|maven|
|javax.persistence:javax.persistence-api|2.2|间接依赖|maven|
|org.springframework.data:spring-data-redis|2.2.13.RELEASE|直接依赖|maven|
|io.netty:netty-codec-http2|4.1.94.Final|间接依赖|maven|
|io.helidon.microprofile.config:helidon-microprofile-config|3.2.1|直接依赖|maven|
|io.quarkus:quarkus-vertx-latebound-mdc-provider|3.2.0.Final|间接依赖|maven|
|jakarta.servlet:jakarta.servlet-api|6.0.0|间接依赖|maven|
|org.springframework:spring-context-support|5.2.13.RELEASE|间接依赖|maven|
|org.springframework:spring-expression|5.3.13|间接依赖|maven|
|io.netty:netty-handler|4.1.86.Final|间接依赖|maven|
|org.junit.jupiter:junit-jupiter|5.9.2|间接依赖|maven|
|io.netty:netty-codec|4.1.96.Final|直接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|2.1.1|间接依赖|maven|
|io.quarkus:quarkus-development-mode-spi|1.13.6.Final|间接依赖|maven|
|io.micronaut:micronaut-runtime|2.5.0|间接依赖|maven|
|io.netty:netty-codec-http|4.1.49.Final|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.86.Final|间接依赖|maven|
|io.netty:netty-transport|4.1.94.Final|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.94.Final|直接依赖|maven|
|io.quarkus:quarkus-netty-deployment|1.13.6.Final|直接依赖|maven|
|io.quarkus:quarkus-resteasy-server-common|3.2.0.Final|间接依赖|maven|
|io.netty:netty-codec|4.1.86.Final|间接依赖|maven|
|org.springframework.data:spring-data-commons|2.6.10|间接依赖|maven|
|org.springframework:spring-context|4.1.9.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|3.1.1|间接依赖|maven|
|org.springframework.data:spring-data-keyvalue|2.4.15|间接依赖|maven|
|org.springframework:spring-context|6.0.9|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|直接依赖|maven|
|org.apache.maven.wagon:wagon-http-shared|3.4.3|间接依赖|maven|
|io.quarkus.arc:arc|3.2.0.Final|间接依赖|maven|
|io.netty:netty-codec-haproxy|4.1.94.Final|间接依赖|maven|
|org.springframework:spring-oxm|5.3.13|间接依赖|maven|
|io.micronaut:micronaut-core-reactive|3.5.4|间接依赖|maven|
|io.quarkus:quarkus-vertx-http|2.16.4.Final|间接依赖|maven|
|io.quarkus:quarkus-class-change-agent|2.16.4.Final|间接依赖|maven|
|io.vertx:vertx-web-common|3.9.6|间接依赖|maven|
|org.apache.maven:maven-settings-builder|3.8.1|间接依赖|maven|
|org.fusesource.jansi:jansi|2.4.0|间接依赖|maven|
|org.springframework:spring-oxm|6.0.8|间接依赖|maven|
|io.quarkus:quarkus-netty|3.2.0.Final|直接依赖|maven|
|io.netty:netty-resolver|4.1.86.Final|间接依赖|maven|
|org.junit.platform:junit-platform-launcher|1.9.3|间接依赖|maven|
|io.smallrye.common:smallrye-common-function|1.5.0|间接依赖|maven|
|org.springframework:spring-tx|6.0.9|间接依赖|maven|
|io.micronaut.cache:micronaut-cache-caffeine|4.0.0|间接依赖|maven|
|org.springframework:spring-oxm|5.2.13.RELEASE|间接依赖|maven|
|org.springframework:spring-jcl|6.0.8|间接依赖|maven|
|org.springframework:spring-core|4.2.9.RELEASE|间接依赖|maven|
|io.helidon.common:helidon-common-configurable|3.2.1|间接依赖|maven|
|io.smallrye.reactive:mutiny|1.9.0|间接依赖|maven|
|io.smallrye.reactive:vertx-mutiny-generator|3.5.0|间接依赖|maven|
|io.smallrye.common:smallrye-common-classloader|2.1.0|间接依赖|maven|
|io.netty:netty-codec-http|4.1.94.Final|间接依赖|maven|
|org.springframework:spring-beans|5.3.19|间接依赖|maven|
|org.springframework:spring-core|5.3.19|间接依赖|maven|
|io.smallrye.config:smallrye-config-common|3.3.0|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|间接依赖|maven|
|org.springframework:spring-aop|5.2.13.RELEASE|间接依赖|maven|
|org.springframework:spring-context-support|6.0.10|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.20.0|间接依赖|maven|
|io.projectreactor:reactor-core|3.5.3|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.26|间接依赖|maven|
|org.springframework:spring-oxm|4.3.25.RELEASE|间接依赖|maven|
|io.quarkus:quarkus-bootstrap-runner|1.13.6.Final|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.86.Final|间接依赖|maven|
|io.quarkus:quarkus-security-runtime-spi|3.2.0.Final|间接依赖|maven|
|io.netty:netty-resolver|4.1.49.Final|间接依赖|maven|
|io.smallrye.config:smallrye-config-common|2.13.3|间接依赖|maven|
|io.quarkus:quarkus-vertx|2.16.4.Final|间接依赖|maven|
|org.jboss.slf4j:slf4j-jboss-logmanager|1.1.0.Final|间接依赖|maven|
|io.micronaut:micronaut-router|3.10.1|间接依赖|maven|
|org.eclipse.microprofile.context-propagation:microprofile-context-propagation-api|1.3|间接依赖|maven|
|org.jvnet.staxex:stax-ex|1.8|间接依赖|maven|
|io.micronaut:micronaut-discovery-core|4.0.0|间接依赖|maven|
|org.springframework:spring-context|5.2.13.RELEASE|间接依赖|maven|
|io.helidon.config:helidon-config-object-mapping|2.5.1|间接依赖|maven|
|io.netty.incubator:netty-incubator-transport-native-io_uring|0.0.21.Final|直接依赖|maven|
|org.springframework.data:spring-data-redis|3.1.1|间接依赖|maven|
|jakarta.el:jakarta.el-api|3.0.3|间接依赖|maven|
|io.micronaut:micronaut-http|3.5.4|间接依赖|maven|
|io.quarkus:quarkus-vertx-http-dev-console-runtime-spi|2.16.4.Final|间接依赖|maven|
|jakarta.transaction:jakarta.transaction-api|1.3.3|间接依赖|maven|
|io.vertx:vertx-web-common|4.3.7|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.12.3|间接依赖|maven|
|io.micrometer:micrometer-core|1.11.1|间接依赖|maven|
|io.quarkus:quarkus-arc|3.2.0.Final|直接依赖|maven|
|io.micronaut:micronaut-inject|4.0.0|直接依赖|maven|
|io.netty:netty-resolver|4.1.96.Final|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.14.2|间接依赖|maven|
|org.springframework:spring-jcl|6.0.9|间接依赖|maven|
|org.springframework:spring-context-support|5.3.19|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.86.Final|间接依赖|maven|
|io.smallrye.config:smallrye-config-core|3.3.0|间接依赖|maven|
|org.apache.geronimo.specs:geronimo-jta_1.1_spec|1.1.1|间接依赖|maven|
|io.quarkus:quarkus-mutiny|2.16.4.Final|间接依赖|maven|
|org.eclipse.sisu:org.eclipse.sisu.inject|0.3.5|间接依赖|maven|
|io.quarkus:quarkus-resteasy-server-common|1.13.6.Final|间接依赖|maven|
|org.springframework:spring-oxm|6.0.10|间接依赖|maven|
|org.springframework.data:spring-data-commons|2.5.12|间接依赖|maven|
|io.helidon.common:helidon-common-media-type|3.2.1|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.20.0|间接依赖|maven|
|io.quarkus.gizmo:gizmo|1.6.0.Final|间接依赖|maven|
|io.smallrye.reactive:smallrye-mutiny-vertx-core|3.5.0|间接依赖|maven|
|org.springframework:spring-core|5.0.13.RELEASE|间接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|io.smallrye.common:smallrye-common-annotation|2.1.0|间接依赖|maven|
|commons-codec:commons-codec|1.14|间接依赖|maven|
|io.smallrye:smallrye-context-propagation|1.2.2|间接依赖|maven|
|io.netty:netty-handler|4.1.94.Final|间接依赖|maven|
|org.apache.maven.resolver:maven-resolver-util|1.6.2|间接依赖|maven|
|org.springframework:spring-context|5.1.19.RELEASE|间接依赖|maven|
|org.ow2.asm:asm-tree|9.1|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|io.smallrye:smallrye-context-propagation|2.1.0|间接依赖|maven|
|org.aesh:aesh|2.7|间接依赖|maven|
|io.smallrye.reactive:smallrye-mutiny-vertx-uri-template|2.30.1|间接依赖|maven|
|io.vertx:vertx-uri-template|4.3.7|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.14.2|间接依赖|maven|
|io.smallrye.reactive:smallrye-mutiny-vertx-core|2.30.1|间接依赖|maven|
|org.springframework.data:spring-data-keyvalue|2.7.11|间接依赖|maven|
|org.springframework:spring-context|5.3.19|间接依赖|maven|
|io.smallrye:jandex|3.0.5|间接依赖|maven|
|org.codehaus.plexus:plexus-interpolation|1.25|间接依赖|maven|
|io.vertx:vertx-web|4.3.7|间接依赖|maven|
|org.springframework:spring-expression|4.3.25.RELEASE|间接依赖|maven|
|io.smallrye.config:smallrye-config-core|2.13.3|间接依赖|maven|
|org.springframework:spring-context-support|6.0.9|间接依赖|maven|
|jakarta.inject:jakarta.inject-api|2.0.1|间接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|org.jboss.spec.javax.transaction:jboss-transaction-api_1.2_spec|1.0.1.Final|间接依赖|maven|
|io.quarkus:quarkus-bootstrap-core|2.16.4.Final|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.3.1.Final|间接依赖|maven|
|io.netty:netty-buffer|4.1.96.Final|直接依赖|maven|
|org.springframework:spring-jcl|5.2.13.RELEASE|间接依赖|maven|
|io.quarkus:quarkus-bootstrap-core|1.13.6.Final|间接依赖|maven|
|io.smallrye.common:smallrye-common-io|1.13.2|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|org.springframework:spring-context-support|4.2.9.RELEASE|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.15.2|直接依赖|maven|
|org.springframework:spring-expression|5.1.19.RELEASE|间接依赖|maven|
|io.vertx:vertx-web|4.4.4|间接依赖|maven|
|org.springframework:spring-aop|4.1.9.RELEASE|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.18|间接依赖|maven|
|org.yaml:snakeyaml|2.0|间接依赖|maven|
|org.jboss.logging:jboss-logging-annotations|2.2.1.Final|间接依赖|maven|
|org.jodd:jodd-core|5.1.6|间接依赖|maven|
|org.ow2.asm:asm|9.1|间接依赖|maven|
|org.jboss:jandex|2.0.3.Final|间接依赖|maven|
|org.springframework:spring-oxm|5.3.24|间接依赖|maven|
|io.helidon.common:helidon-common-key-util|3.2.1|间接依赖|maven|
|org.jboss.slf4j:slf4j-jboss-logmanager|2.0.0.Final|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|org.springframework:spring-context|5.3.27|间接依赖|maven|
|io.smallrye.common:smallrye-common-expression|1.13.2|间接依赖|maven|
|org.springframework:spring-oxm|4.1.9.RELEASE|间接依赖|maven|
|io.helidon.config:helidon-config|3.2.1|间接依赖|maven|
|org.springframework:spring-context-support|6.0.8|间接依赖|maven|
|org.springframework:spring-context-support|4.1.9.RELEASE|间接依赖|maven|
|io.helidon.common:helidon-common-configurable|2.5.1|间接依赖|maven|
|org.jsoup:jsoup|1.12.1|间接依赖|maven|
|org.jboss.logmanager:jboss-logmanager-embedded|1.0.9|间接依赖|maven|
|io.quarkus:quarkus-resteasy|3.2.0.Final|直接依赖|maven|
|io.quarkus:quarkus-fs-util|0.0.9|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.25|间接依赖|maven|
|org.jboss.resteasy.microprofile:microprofile-config|2.1.1.Final|间接依赖|maven|
|org.springframework.data:spring-data-commons|1.13.23.RELEASE|间接依赖|maven|
|io.netty:netty-buffer|4.1.94.Final|间接依赖|maven|
|io.micronaut:micronaut-core|2.5.0|间接依赖|maven|
|org.glassfish.jaxb:txw2|4.0.2|间接依赖|maven|
|com.esotericsoftware:minlog|1.3.1|间接依赖|maven|
|io.quarkus:quarkus-security-runtime-spi|2.16.4.Final|间接依赖|maven|
|io.helidon.config:helidon-config-yaml|2.5.1|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.14|间接依赖|maven|
|org.aesh:readline|2.2|间接依赖|maven|
|org.ow2.asm:asm-util|9.5|间接依赖|maven|
|io.helidon.common:helidon-common-crypto|2.5.1|间接依赖|maven|
|com.aayushatharva.brotli4j:service|1.12.0|间接依赖|maven|
|io.helidon.config:helidon-config-yaml|3.2.1|间接依赖|maven|
|io.netty:netty-common|4.1.49.Final|间接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.96.Final|间接依赖|maven|
|io.smallrye.common:smallrye-common-annotation|1.5.0|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.94.Final|间接依赖|maven|
|io.quarkus:quarkus-builder|1.13.6.Final|间接依赖|maven|
|org.springframework:spring-aop|6.0.10|间接依赖|maven|
|org.hibernate.orm:hibernate-core|6.2.5.Final|直接依赖|maven|
|org.springframework.data:spring-data-redis|2.6.10|直接依赖|maven|
|org.springframework:spring-aop|5.3.24|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.3.Final|间接依赖|maven|
|io.micronaut:micronaut-aop|2.5.0|间接依赖|maven|
|org.springframework.boot:spring-boot|3.1.1|间接依赖|maven|
|dom4j:dom4j|1.6.1|间接依赖|maven|
|io.quarkus:quarkus-smallrye-context-propagation-spi|2.16.4.Final|间接依赖|maven|
|org.springframework:spring-oxm|5.1.19.RELEASE|间接依赖|maven|
|io.quarkus:quarkus-bootstrap-core|3.2.0.Final|间接依赖|maven|
|io.smallrye.reactive:smallrye-mutiny-vertx-web|3.5.0|间接依赖|maven|
|io.micronaut.session:micronaut-session|4.0.0|直接依赖|maven|
|io.quarkus.arc:arc|2.16.4.Final|间接依赖|maven|
|org.springframework.data:spring-data-keyvalue|2.1.21.RELEASE|间接依赖|maven|
|org.jboss.logging:jboss-logging-annotations|2.2.0.Final|间接依赖|maven|
|org.springframework:spring-jcl|5.3.24|间接依赖|maven|
|io.quarkus:quarkus-arc|1.13.6.Final|直接依赖|maven|
|org.springframework:spring-context-support|5.2.14.RELEASE|间接依赖|maven|
|io.quarkus:quarkus-vertx-http-dev-console-spi|2.16.4.Final|间接依赖|maven|
|io.quarkus:quarkus-netty|1.13.6.Final|直接依赖|maven|
|org.jboss.resteasy:resteasy-core|6.2.4.Final|间接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.96.Final|直接依赖|maven|
|org.ow2.asm:asm-commons|9.4|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.86.Final|间接依赖|maven|
|org.springframework.data:spring-data-commons|3.0.5|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.96.Final|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.15.2|间接依赖|maven|
|org.springframework.data:spring-data-keyvalue|1.2.23.RELEASE|间接依赖|maven|
|org.apache.maven.wagon:wagon-provider-api|3.4.3|间接依赖|maven|
|io.smallrye:jandex|3.1.2|间接依赖|maven|
|org.aesh:readline|2.4|间接依赖|maven|
|io.projectreactor:reactor-core|3.5.7|间接依赖|maven|
|io.smallrye.reactive:smallrye-mutiny-vertx-auth-common|2.30.1|间接依赖|maven|
|io.micronaut:micronaut-core-reactive|2.5.0|间接依赖|maven|
|org.jboss:jandex|1.1.0.Final|间接依赖|maven|
|org.springframework:spring-tx|5.2.14.RELEASE|间接依赖|maven|
|io.helidon.config:helidon-config|2.5.1|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.15.2|间接依赖|maven|
|org.jboss.marshalling:jboss-marshalling|2.0.11.Final|直接依赖|maven|
|io.quarkus:quarkus-vertx|3.2.0.Final|间接依赖|maven|
|io.reactivex.rxjava2:rxjava|2.2.10|间接依赖|maven|
|org.wildfly.common:wildfly-common|1.5.4.Final-format-001|间接依赖|maven|
|org.springframework:spring-oxm|5.0.13.RELEASE|间接依赖|maven|
|org.ow2.asm:asm|9.5|间接依赖|maven|
|org.jboss.resteasy:resteasy-core-spi|4.5.12.Final|间接依赖|maven|
|org.jodd:jodd-bean|5.1.6|直接依赖|maven|
|io.smallrye:smallrye-context-propagation-api|1.2.2|间接依赖|maven|
|io.quarkus:quarkus-bootstrap-app-model|1.13.6.Final|间接依赖|maven|
|io.quarkus:quarkus-bootstrap-app-model|2.16.4.Final|间接依赖|maven|
|org.springframework:spring-tx|4.3.25.RELEASE|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|4.0.0|间接依赖|maven|
|org.springframework:spring-expression|4.1.9.RELEASE|间接依赖|maven|
|org.codehaus.plexus:plexus-utils|3.2.1|间接依赖|maven|
|org.springframework:spring-oxm|5.3.27|间接依赖|maven|
|io.quarkus:quarkus-core-deployment|3.2.0.Final|间接依赖|maven|
|io.smallrye.common:smallrye-common-classloader|1.13.2|间接依赖|maven|
|io.quarkus:quarkus-resteasy-server-common|2.16.4.Final|间接依赖|maven|
|org.springframework:spring-aop|5.0.13.RELEASE|间接依赖|maven|
|io.smallrye.common:smallrye-common-os|2.1.0|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.86.Final|间接依赖|maven|
|org.apache.maven.wagon:wagon-file|3.4.3|间接依赖|maven|
|org.springframework.data:spring-data-redis|2.3.9.RELEASE|直接依赖|maven|
|io.smallrye.reactive:smallrye-mutiny-vertx-bridge-common|3.5.0|间接依赖|maven|
|org.slf4j:slf4j-api|2.0.2|间接依赖|maven|
|io.netty:netty-transport|4.1.96.Final|直接依赖|maven|
|org.jboss.resteasy:resteasy-core-spi|4.7.7.Final|间接依赖|maven|
|jakarta.transaction:jakarta.transaction-api|2.0.1|间接依赖|maven|
|io.vertx:vertx-bridge-common|3.9.6|间接依赖|maven|
|io.reactivex.rxjava3:rxjava|3.1.6|直接依赖|maven|
|io.quarkus:quarkus-builder|2.16.4.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator-autoconfigure|3.1.1|间接依赖|maven|
|io.quarkus:quarkus-builder|3.2.0.Final|间接依赖|maven|
|org.springframework:spring-oxm|5.3.19|间接依赖|maven|
|io.vertx:vertx-web-common|4.4.4|间接依赖|maven|
|org.springframework.data:spring-data-keyvalue|3.1.1|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.94.Final|间接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.49.Final|直接依赖|maven|
|io.quarkus:quarkus-netty-deployment|2.16.4.Final|直接依赖|maven|
|org.springframework:spring-oxm|5.2.14.RELEASE|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.86.Final|直接依赖|maven|
|org.springframework:spring-core|4.1.9.RELEASE|间接依赖|maven|
|org.jboss:jandex|2.3.0.Final|直接依赖|maven|
|org.hibernate:hibernate-core|5.1.16.Final|直接依赖|maven|
|io.netty:netty-resolver-dns|4.1.94.Final|间接依赖|maven|
|org.springframework:spring-core|6.0.9|间接依赖|maven|
|org.codehaus.plexus:plexus-classworlds|2.6.0|间接依赖|maven|
|jakarta.el:jakarta.el-api|5.0.1|间接依赖|maven|
|com.esotericsoftware:reflectasm|1.11.9|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.49.Final|间接依赖|maven|
|org.apache.maven:maven-model|3.8.1|间接依赖|maven|
|org.springframework:spring-aop|4.2.9.RELEASE|间接依赖|maven|
|org.springframework.data:spring-data-keyvalue|2.2.13.RELEASE|间接依赖|maven|
|io.micronaut:micronaut-http|2.5.0|间接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|4.0.2|间接依赖|maven|
|io.quarkus:quarkus-resteasy-common|3.2.0.Final|间接依赖|maven|
|org.springframework.data:spring-data-redis|1.6.6.RELEASE|直接依赖|maven|
|io.helidon.common:helidon-common-media-type|2.5.1|间接依赖|maven|
|io.micrometer:micrometer-observation|1.11.1|间接依赖|maven|
|io.quarkus:quarkus-bootstrap-app-model|3.2.0.Final|间接依赖|maven|
|org.springframework:spring-context-support|5.0.13.RELEASE|间接依赖|maven|
|io.helidon.common:helidon-common-service-loader|2.5.1|间接依赖|maven|
|io.quarkus:quarkus-smallrye-context-propagation-spi|3.2.0.Final|间接依赖|maven|
|com.aayushatharva.brotli4j:brotli4j|1.12.0|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|3.1.1|间接依赖|maven|
|jakarta.interceptor:jakarta.interceptor-api|1.2.5|间接依赖|maven|
|org.springframework.data:spring-data-keyvalue|3.0.5|间接依赖|maven|
|org.springframework.data:spring-data-commons|2.7.11|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.49.Final|间接依赖|maven|
|org.springframework.data:spring-data-commons|2.1.21.RELEASE|间接依赖|maven|
|io.micrometer:micrometer-commons|1.11.1|间接依赖|maven|
|io.vertx:vertx-uri-template|4.4.4|间接依赖|maven|
|io.quarkus:quarkus-ide-launcher|3.2.0.Final|间接依赖|maven|
|io.quarkus:quarkus-netty|2.16.4.Final|直接依赖|maven|
|io.smallrye.reactive:mutiny-smallrye-context-propagation|1.9.0|间接依赖|maven|
|io.vertx:vertx-codegen|4.4.4|间接依赖|maven|
|org.springframework:spring-jcl|5.3.19|间接依赖|maven|
|org.apache.maven:maven-builder-support|3.8.1|间接依赖|maven|
|org.springframework:spring-context-support|5.3.13|间接依赖|maven|
|org.jboss.weld:weld-api|5.0.SP2|间接依赖|maven|
|org.springframework:spring-context|5.3.24|间接依赖|maven|
|io.quarkus:quarkus-vertx-http-dev-console-runtime-spi|3.2.0.Final|间接依赖|maven|
|org.springframework.data:spring-data-redis|1.8.23.RELEASE|直接依赖|maven|
|org.apache.maven:maven-repository-metadata|3.8.1|间接依赖|maven|
|org.eclipse.microprofile.config:microprofile-config-api|1.4|直接依赖|maven|
|io.smallrye.config:smallrye-config|1.13.1|间接依赖|maven|
|org.springframework.data:spring-data-keyvalue|1.1.11.RELEASE|间接依赖|maven|
|org.springframework.data:spring-data-redis|3.1.0|直接依赖|maven|
|org.springframework.data:spring-data-keyvalue|2.5.12|间接依赖|maven|
|org.springframework.data:spring-data-keyvalue|2.3.9.RELEASE|间接依赖|maven|
|org.springframework:spring-tx|5.0.13.RELEASE|间接依赖|maven|
|org.jboss.logmanager:jboss-logmanager-embedded|1.0.11|间接依赖|maven|
|org.springframework:spring-expression|5.0.13.RELEASE|间接依赖|maven|
|io.micronaut:micronaut-context|2.5.0|间接依赖|maven|
|org.springframework:spring-jcl|5.3.13|间接依赖|maven|
|org.springframework:spring-core|5.3.13|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|2.1.0|间接依赖|maven|
|io.micronaut:micronaut-http|4.0.0|间接依赖|maven|
|jakarta.enterprise:jakarta.enterprise.lang-model|4.0.1|间接依赖|maven|
|org.springframework:spring-expression|6.0.8|间接依赖|maven|
|org.springframework:spring-aop|5.1.19.RELEASE|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.1.3.GA|间接依赖|maven|
|org.springframework:spring-aop|4.3.25.RELEASE|间接依赖|maven|
|org.yaml:snakeyaml|1.28|间接依赖|maven|
|org.javassist:javassist|3.18.1-GA|间接依赖|maven|
|io.quarkus:quarkus-vertx-http-dev-console-spi|1.13.6.Final|间接依赖|maven|
|io.smallrye.reactive:smallrye-mutiny-vertx-web-common|2.30.1|间接依赖|maven|
|org.graalvm.sdk:graal-sdk|21.0.0|间接依赖|maven|
|org.hibernate:hibernate-core|5.6.12.Final|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.15.2|直接依赖|maven|
|io.quarkus:quarkus-mutiny|3.2.0.Final|间接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.94.Final|间接依赖|maven|
|org.springframework:spring-tx|5.2.13.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.14.2|间接依赖|maven|
|io.micronaut:micronaut-router|2.5.12|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.49.Final|间接依赖|maven|
|jakarta.enterprise:jakarta.enterprise.cdi-api|2.0.2|直接依赖|maven|
|jakarta.enterprise:jakarta.enterprise.cdi-api|4.0.1|直接依赖|maven|
|org.springframework:spring-context-support|5.3.24|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.15.2|直接依赖|maven|
|io.quarkus:quarkus-resteasy-common|2.16.4.Final|间接依赖|maven|
|org.springframework:spring-beans|4.3.25.RELEASE|间接依赖|maven|
|org.apache.maven.wagon:wagon-http|3.4.3|间接依赖|maven|
|io.netty:netty-buffer|4.1.49.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator|3.1.1|间接依赖|maven|
|org.ow2.asm:asm|9.4|间接依赖|maven|
|org.junit.platform:junit-platform-launcher|1.9.2|间接依赖|maven|
|com.aayushatharva.brotli4j:native-linux-x86_64|1.12.0|间接依赖|maven|
|io.netty:netty-common|4.1.86.Final|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|间接依赖|maven|
|org.slf4j:jul-to-slf4j|2.0.7|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-redis|3.1.1|直接依赖|maven|
|org.ow2.asm:asm-util|9.1|间接依赖|maven|
|org.springframework:spring-beans|4.1.9.RELEASE|间接依赖|maven|
|io.micronaut:micronaut-core|4.0.0|间接依赖|maven|
|io.micronaut:micronaut-inject|3.10.1|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.19.1|间接依赖|maven|
|org.hibernate:hibernate-core|4.3.11.Final|直接依赖|maven|
|io.smallrye.reactive:smallrye-mutiny-vertx-uri-template|3.5.0|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)