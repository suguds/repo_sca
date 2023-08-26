# baomidou/mybatis-plus安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695497925671940096.svg)](https://www.murphysec.com/console/report/1695497925629997056/1695497925671940096)

仓库描述：An powerful enhanced toolkit of MyBatis for simplify development

仓库地址：[https://github.com/baomidou/mybatis-plus](https://github.com/baomidou/mybatis-plus)

| star：14979 | watch：64 | fork：4081 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-23 21:41:10 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-27 02:10:33 | 组件总数：144 | 漏洞总数：38 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache Log4j SocketServer反序列化漏洞|反序列化|[MPS-2019-17271](https://www.oscs1024.com/hd/MPS-2019-17271)|CVE-2019-17571|严重|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Netty ZlibDecoders 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2020-5127](https://www.oscs1024.com/hd/MPS-2020-5127)|CVE-2020-11612|高危|
|Apache Log4j2 SmtpAppender证书验证不当漏洞|证书验证不恰当|[MPS-2020-6684](https://www.oscs1024.com/hd/MPS-2020-6684)|CVE-2020-9488|低危|
|Netty <4.1.59.Final 存在不安全的临时文件漏洞||[MPS-2021-1580](https://www.oscs1024.com/hd/MPS-2021-1580)|CVE-2021-21290|中危|
|Netty Bzip2Decoder 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28116](https://www.oscs1024.com/hd/MPS-2021-28116)|CVE-2021-37136|高危|
|Netty 存在资源穷尽漏洞|拒绝服务|[MPS-2021-28117](https://www.oscs1024.com/hd/MPS-2021-28117)|CVE-2021-37137|高危|
|Quality Open Software logback JNDI注入漏洞|反序列化|[MPS-2021-33911](https://www.oscs1024.com/hd/MPS-2021-33911)|CVE-2021-42550|中危|
|Apache Log4j JMSAppender反序列化漏洞||[MPS-2021-38359](https://www.oscs1024.com/hd/MPS-2021-38359)|CVE-2021-4104|高危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|Vmware Spring Framework 安全漏洞|不加限制或调节的资源分配|[MPS-2022-1080](https://www.oscs1024.com/hd/MPS-2022-1080)|CVE-2022-22950|中危|
|Pivotal Spring Framework 安全限制绕过漏洞|大小写敏感处理不恰当|[MPS-2022-1098](https://www.oscs1024.com/hd/MPS-2022-1098)|CVE-2022-22968|中危|
|Spring Framework spring-beans 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1101](https://www.oscs1024.com/hd/MPS-2022-1101)|CVE-2022-22970|中危|
|Spring Framework 整数溢出漏洞|整数溢出或环绕|[MPS-2022-1106](https://www.oscs1024.com/hd/MPS-2022-1106)|CVE-2022-22976|中危|
|Fastjson < 1.2.83 任意代码执行漏洞|反序列化|[MPS-2022-11320](https://www.oscs1024.com/hd/MPS-2022-11320)|CVE-2022-25845|高危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|Logback SSL证书校验不当漏洞|中间人攻击|[MPS-2022-12411](https://www.oscs1024.com/hd/MPS-2022-12411)||中危|
|Apache Log4j JDBCAppender SQL注入漏洞|SQL注入|[MPS-2022-1444](https://www.oscs1024.com/hd/MPS-2022-1444)|CVE-2022-23305|严重|
|Apache Log4j Chainsaw反序列化漏洞|反序列化|[MPS-2022-1445](https://www.oscs1024.com/hd/MPS-2022-1445)|CVE-2022-23307|高危|
|Apache Log4j 反序列化漏洞|反序列化|[MPS-2022-1446](https://www.oscs1024.com/hd/MPS-2022-1446)|CVE-2022-23302|高危|
|Netty 存在信息泄露漏洞||[MPS-2022-3790](https://www.oscs1024.com/hd/MPS-2022-3790)|CVE-2022-24823|中危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|spring-beans 远程代码执行漏洞(Spring4Shell)|表达式语言注入|[MPS-2022-6820](https://www.oscs1024.com/hd/MPS-2022-6820)|CVE-2022-22965|严重|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|netplex json-smart 安全漏洞|未经控制的递归|[MPS-2023-7760](https://www.oscs1024.com/hd/MPS-2023-7760)|CVE-2023-1370|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.springframework.boot:spring-boot-autoconfigure|2.5.3|3.0.7|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-context|5.3.15|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|io.netty:netty-handler|4.1.45.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:3|L:0|
|io.netty:netty-handler|4.1.66.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|io.netty:netty-codec|4.1.45.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|org.springframework.security:spring-security-crypto|5.6.1|5.6.4|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.yaml:snakeyaml|1.28|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|io.netty:netty-codec|4.1.66.Final|4.1.68.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|log4j:log4j|1.2.17||间接依赖|建议修复|C:2|H:3|M:0|L:1|
|com.alibaba:fastjson|1.2.70|1.2.83|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|ch.qos.logback:logback-core|1.2.4|1.2.8|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.3|2.14.0-rc1|直接依赖|建议修复|C:0|H:0|M:3|L:0|
|org.springframework:spring-beans|5.3.15|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|net.minidev:json-smart|2.4.7|2.4.9|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-common|4.1.45.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-core|5.3.15|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-transport-native-epoll|4.1.45.Final|4.1.59.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-io:commons-io|2.6|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-common|4.1.66.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|5.3.15|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|com.google.guava:guava|27.0.1-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:1|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|109|Low|
|LGPL-2.1|1|Medium|
|MPL-1.1|1|Low|
|自定义许可证|8|Low|
|MIT|10|Low|
|EPL-2.0|8|Low|
|EPL-1.0|2|Low|
|BSD-3-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|io.netty:netty-handler|4.1.45.Final|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.9.0|间接依赖|maven|
|org.apache.curator:curator-client|4.3.0|间接依赖|maven|
|io.netty:netty-handler|4.1.66.Final|间接依赖|maven|
|org.springframework:spring-beans|5.3.15|间接依赖|maven|
|com.fasterxml.jackson:jackson-bom|2.13.3|间接依赖|maven|
|org.unbescape:unbescape|1.1.6.RELEASE|间接依赖|maven|
|org.javassist:javassist|3.21.0-GA|间接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.3|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.66.Final|间接依赖|maven|
|org.mybatis.scripting:mybatis-velocity|2.1.2|直接依赖|maven|
|log4j:log4j|1.2.17|间接依赖|maven|
|org.mockito:mockito-core|3.9.0|间接依赖|maven|
|com.alibaba:fastjson|1.2.70|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.66.Final|间接依赖|maven|
|org.springframework.security:spring-security-crypto|5.6.1|直接依赖|maven|
|com.google.guava:guava|27.0.1-jre|间接依赖|maven|
|org.springframework:spring-expression|5.3.15|间接依赖|maven|
|::mybatis-plus-boot-starter||直接依赖|maven|
|org.springframework:spring-core|5.3.15|间接依赖|maven|
|org.springframework:spring-context|5.3.15|间接依赖|maven|
|com.github.jsqlparser:jsqlparser|4.6|直接依赖|maven|
|org.apiguardian:apiguardian-api|1.1.0|间接依赖|maven|
|org.springframework.boot:spring-boot|2.5.3|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|io.netty:netty-common|4.1.45.Final|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-api|5.7.2|间接依赖|maven|
|org.checkerframework:checker-qual|3.19.0|直接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.45.Final|间接依赖|maven|
|org.objenesis:objenesis|3.2|间接依赖|maven|
|io.netty:netty-common|4.1.66.Final|间接依赖|maven|
|io.netty:netty-buffer|4.1.45.Final|间接依赖|maven|
|org.mybatis:mybatis-spring|2.1.1|直接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.5.3|直接依赖|maven|
|org.assertj:assertj-core|3.19.0|间接依赖|maven|
|org.junit.platform:junit-platform-engine|1.7.2|间接依赖|maven|
|com.jayway.jsonpath:json-path|2.5.0|间接依赖|maven|
|org.skyscreamer:jsonassert|1.5.0|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.2|间接依赖|maven|
|org.springframework:spring-test|5.3.9|间接依赖|maven|
|org.apache.commons:commons-pool2|2.9.0|间接依赖|maven|
|org.springframework:spring-jcl|5.3.15|间接依赖|maven|
|org.mybatis:mybatis|3.5.13|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.3|直接依赖|maven|
|org.mockito:mockito-junit-jupiter|3.9.0|间接依赖|maven|
|org.springframework.boot:spring-boot-test|2.5.3|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-reflect|1.9.0|直接依赖|maven|
|org.attoparser:attoparser|2.0.5.RELEASE|间接依赖|maven|
|org.apache.curator:curator-framework|4.3.0|间接依赖|maven|
|com.vaadin.external.google:android-json|0.0.20131108.vaadin1|间接依赖|maven|
|org.mybatis.scripting:mybatis-thymeleaf|1.0.3|直接依赖|maven|
|io.netty:netty-transport|4.1.66.Final|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.17|间接依赖|maven|
|io.netty:netty-codec|4.1.45.Final|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-params|5.7.2|间接依赖|maven|
|org.apache.curator:curator-recipes|4.3.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.9.0|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.5.3|直接依赖|maven|
|org.antlr:antlr4-runtime|4.9.2|间接依赖|maven|
|net.sf.ehcache:ehcache|2.10.9.2|间接依赖|maven|
|io.netty:netty-transport|4.1.45.Final|间接依赖|maven|
|com.ibeetl:beetl|3.7.0.RELEASE|直接依赖|maven|
|ch.qos.logback:logback-core|1.2.4|间接依赖|maven|
|org.opentest4j:opentest4j|1.2.0|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|org.objenesis:objenesis|2.5.1|间接依赖|maven|
|com.imadcn.framework:idworker|1.5.0|直接依赖|maven|
|com.alibaba:fastjson|2.0.11|直接依赖|maven|
|org.apache.velocity:velocity-engine-core|2.3|直接依赖|maven|
|org.springframework.boot:spring-boot-dependencies|2.5.3|直接依赖|maven|
|org.apache.zookeeper:zookeeper-jute|3.5.7|间接依赖|maven|
|org.yaml:snakeyaml|1.28|间接依赖|maven|
|redis.clients:jedis|2.8.0|直接依赖|maven|
|org.ow2.asm:asm|9.1|间接依赖|maven|
|org.springframework:spring-aop|5.3.15|直接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-test|2.5.3|直接依赖|maven|
|p6spy:p6spy|3.9.1|直接依赖|maven|
|org.junit.jupiter:junit-jupiter-engine|5.7.2|间接依赖|maven|
|org.mybatis.scripting:mybatis-freemarker|1.2.3|直接依赖|maven|
|::mybatis-plus||直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.3|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.32|间接依赖|maven|
|io.netty:netty-buffer|4.1.66.Final|间接依赖|maven|
|org.xmlunit:xmlunit-core|2.8.2|间接依赖|maven|
|net.minidev:json-smart|2.4.7|间接依赖|maven|
|org.apache.yetus:audience-annotations|0.5.0|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.25|间接依赖|maven|
|org.springframework.boot:spring-boot-test-autoconfigure|2.5.3|间接依赖|maven|
|::mybatis-plus-annotation||直接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.3|间接依赖|maven|
|::mybatis-plus-core||直接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|间接依赖|maven|
|org.springframework:spring-tx|5.3.15|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.9.0|间接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|org.hamcrest:hamcrest|2.2|间接依赖|maven|
|org.mybatis.caches:mybatis-redis|1.0.0-beta2|直接依赖|maven|
|com.alibaba.fastjson2:fastjson2-extension|2.0.11|间接依赖|maven|
|org.junit.platform:junit-platform-commons|1.7.2|间接依赖|maven|
|redis.clients:jedis|3.6.3|间接依赖|maven|
|io.netty:netty-resolver|4.1.45.Final|间接依赖|maven|
|com.alibaba.fastjson2:fastjson2|2.0.11|间接依赖|maven|
|org.springframework.boot:spring-boot-configuration-processor|2.5.3|直接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.14.1|间接依赖|maven|
|org.junit:junit-bom|5.7.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.5.3|间接依赖|maven|
|com.google.code.gson:gson|2.9.1|直接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure-processor|2.5.3|直接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.5.3|间接依赖|maven|
|commons-io:commons-io|2.6|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.9.0|间接依赖|maven|
|org.junit.jupiter:junit-jupiter|5.7.2|间接依赖|maven|
|:No dependencies||直接依赖|maven|
|ognl:ognl|3.1.26|间接依赖|maven|
|org.springframework.cloud:spring-cloud-commons|3.1.1|直接依赖|maven|
|net.minidev:accessors-smart|2.4.7|间接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|间接依赖|maven|
|io.netty:netty-codec|4.1.66.Final|间接依赖|maven|
|io.netty:netty-resolver|4.1.66.Final|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|org.thymeleaf:thymeleaf|3.0.14.RELEASE|间接依赖|maven|
|com.google.errorprone:error||直接依赖|maven|
|org.freemarker:freemarker|2.3.31|直接依赖|maven|
|ch.qos.logback:logback-classic|1.2.4|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.10.22|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.1|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.45.Final|间接依赖|maven|
|org.springframework:spring-context-support|5.3.15|直接依赖|maven|
|net.bytebuddy:byte-buddy-agent|1.10.22|间接依赖|maven|
|org.springframework:spring-jdbc|5.3.15|直接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.14.1|间接依赖|maven|
|de.ruedigermoeller:fst|2.57|直接依赖|maven|
|cglib:cglib|3.3.0|直接依赖|maven|
|com.jfinal:enjoy|5.0.0|直接依赖|maven|
|org.apache.zookeeper:zookeeper|3.5.7|间接依赖|maven|
|::mybatis-plus-extension||直接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.9.3|直接依赖|maven|
|org.ow2.asm:asm|7.1|间接依赖|maven|
|org.apache.commons:commons-pool2|2.3|直接依赖|maven|
|org.checkerframework:checker-qual|2.5.2|间接依赖|maven|
|org.mybatis.caches:mybatis-ehcache|1.2.3|直接依赖|maven|
|org.apache.commons:commons-text|1.10.0|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)