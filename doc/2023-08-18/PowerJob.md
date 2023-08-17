# PowerJob/PowerJob安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692236042143031296.svg)](https://www.murphysec.com/console/report/1692236041807486976/1692236042143031296)

仓库描述：Enterprise job scheduling middleware with distributed computing ability.

仓库地址：[https://github.com/PowerJob/PowerJob](https://github.com/PowerJob/PowerJob)

| star：5711 | watch：117 | fork：1015 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-16 11:13:53 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-18 02:07:13 | 组件总数：220 | 漏洞总数：44 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|Apache Commons Net <3.9.0 存在FTP跳转攻击漏洞|未授权敏感信息泄露|[MPS-2021-28440](https://www.oscs1024.com/hd/MPS-2021-28440)|CVE-2021-37533|中危|
|quarkus 远程代码执行漏洞|初始化不恰当|[MPS-2021-37082](https://www.oscs1024.com/hd/MPS-2021-37082)|CVE-2022-21724|高危|
|Bouncy Castle 私钥信息泄露漏洞|竞争条件|[MPS-2021-7064](https://www.oscs1024.com/hd/MPS-2021-7064)|CVE-2020-15522|中危|
|Jakarta Expression Language <=3.0.3 存在输入验证错误漏洞|表达式语言注入|[MPS-2021-7671](https://www.oscs1024.com/hd/MPS-2021-7671)|CVE-2021-28170|中危|
|Red Hat XNIO 资源错误分配漏洞|不加限制或调节的资源分配|[MPS-2022-0191](https://www.oscs1024.com/hd/MPS-2022-0191)|CVE-2022-0084|高危|
|PostgreSQL JDBC 存在 SQL 注入漏洞|SQL注入|[MPS-2022-11227](https://www.oscs1024.com/hd/MPS-2022-11227)|CVE-2022-31197|高危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|org.apache.maven.shared:maven-shared-utils 存在命令注入漏洞|命令注入|[MPS-2022-12562](https://www.oscs1024.com/hd/MPS-2022-12562)||高危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|org.scala-lang:scala-library 存在反序列化漏洞（Gadget chain）|反序列化|[MPS-2022-52625](https://www.oscs1024.com/hd/MPS-2022-52625)|CVE-2022-36944|严重|
|Bouncy Castle <1.69 认证绕过漏洞|密码学问题|[MPS-2022-54305](https://www.oscs1024.com/hd/MPS-2022-54305)||中危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|protobuf-java 存在输入验证不当漏洞|拒绝服务|[MPS-2022-56472](https://www.oscs1024.com/hd/MPS-2022-56472)|CVE-2022-3171|中危|
|postgresql <42.3.3 存在代码注入漏洞|代码注入|[MPS-2022-5828](https://www.oscs1024.com/hd/MPS-2022-5828)|CVE-2022-26520|严重|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|Netty <4.1.86.Final 存在 CRLF 注入漏洞||[MPS-2022-58552](https://www.oscs1024.com/hd/MPS-2022-58552)|CVE-2022-41915|中危|
|pgjdbc <42.5.1 存在信息泄露漏洞|不安全的临时文件|[MPS-2022-58583](https://www.oscs1024.com/hd/MPS-2022-58583)|CVE-2022-41946|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|Google protobuf 安全漏洞|拒绝服务|[MPS-2022-59814](https://www.oscs1024.com/hd/MPS-2022-59814)|CVE-2022-3510|高危|
|Spring Security通配符路由绕过漏洞|关键资源权限分配不当|[MPS-2022-62832](https://www.oscs1024.com/hd/MPS-2022-62832)|CVE-2023-20860|高危|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot在Cloud Foundry中部署存在路由限制绕过风险|访问控制不当|[MPS-2022-62845](https://www.oscs1024.com/hd/MPS-2022-62845)|CVE-2023-20873|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|H2 数据库明文密码问题|未授权敏感信息泄露|[MPS-2022-65204](https://www.oscs1024.com/hd/MPS-2022-65204)|CVE-2022-45868|高危|
|Red Hat Undertow 安全漏洞|证书验证不恰当|[MPS-2022-68061](https://www.oscs1024.com/hd/MPS-2022-68061)|CVE-2022-4492|高危|
|Red Hat Undertow 资源管理错误漏洞|拒绝服务|[MPS-2022-7892](https://www.oscs1024.com/hd/MPS-2022-7892)|CVE-2022-1259|高危|
|Apache Maven Shared Utils 系统命令注入漏洞|命令注入|[MPS-2022-9177](https://www.oscs1024.com/hd/MPS-2022-9177)|CVE-2022-29599|严重|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Zip4j 访问控制错误漏洞|源验证错误|[MPS-2023-0738](https://www.oscs1024.com/hd/MPS-2023-0738)|CVE-2023-22899|中危|
|Eclipse Vertx-web 路径遍历漏洞|路径遍历|[MPS-2023-3321](https://www.oscs1024.com/hd/MPS-2023-3321)|CVE-2023-24815|中危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.scala-lang:scala-library|2.13.3|2.13.9|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.google.protobuf:protobuf-java|3.11.4|3.21.7|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-web|5.3.23|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.postgresql:postgresql|42.2.14|42.5.1|直接依赖|建议修复|C:1|H:2|M:1|L:0|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.7.4|3.0.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.undertow:undertow-core|2.2.19.Final|2.3.6.final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.14.0-rc1||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.squareup.okio:okio|1.17.2|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.7.4|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-webmvc|5.3.23|6.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.86.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.apache.maven.shared:maven-shared-utils|3.2.1|3.3.3|间接依赖|建议修复|C:1|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.30|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|com.fasterxml.jackson.core:jackson-databind|2.13.4|2.14.0-rc1|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-expression|5.3.23|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.h2database:h2|2.1.214||直接依赖|可选修复|C:0|H:1|M:0|L:0|
|commons-net:commons-net|3.8.0|3.9.0|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.glassfish:javax.el|3.0.0||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|net.lingala.zip4j:zip4j|2.11.2|2.11.3|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|31.1-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-core|5.3.23|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.bouncycastle:bcprov-jdk15on|1.64|1.69|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|org.jboss.xnio:xnio-api|3.8.7.Final|3.8.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.protobuf:protobuf-java|3.19.4|3.21.7|间接依赖|可选修复|C:0|H:1|M:2|L:0|
|io.vertx:vertx-web|4.3.7|4.3.8|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.code.gson:gson|2.8.6|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.guava:guava|30.1.1-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-codec:commons-codec|1.11|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|io.netty:netty-codec-http|4.1.86.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|152|Low|
|LGPL-2.1-or-later|2|Low|
|EPL-2.0|10|Low|
|BSD-3-Clause|3|Low|
|EPL-1.0|8|Low|
|LGPL-2.1|2|Medium|
|MPL-1.1|2|Low|
|MIT|9|Low|
|CDDL-1.1|2|Low|
|MPL-2.0|1|Low|
|CDDL-1.0|1|Low|
|MIT-0|1|Low|
|BSD-2-Clause|2|Low|
|WTFPL|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|io.micrometer:micrometer-core|1.9.4|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.86.Final|间接依赖|maven|
|io.netty:netty-common|4.1.86.Final|间接依赖|maven|
|org.codehaus.groovy:groovy|3.0.10|间接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|io.opentracing:opentracing-noop|0.33.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.4|间接依赖|maven|
|antlr:antlr|2.7.7|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.7.4|间接依赖|maven|
|org.springframework:spring-orm|5.3.23|间接依赖|maven|
|org.wildfly.common:wildfly-common|1.5.4.Final|间接依赖|maven|
|com.typesafe:config|1.4.0|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.65|间接依赖|maven|
|org.jboss.xnio:xnio-nio|3.8.7.Final|间接依赖|maven|
|org.glassfish:javax.el|3.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.7.4|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.14.0-rc1|直接依赖|maven|
|org.hibernate.common:hibernate-commons-annotations|5.1.2.Final|间接依赖|maven|
|org.springframework:spring-beans|5.3.23|间接依赖|maven|
|info.picocli:picocli|4.3.2|直接依赖|maven|
|org.webjars:swagger-ui|4.15.5|间接依赖|maven|
|commons-net:commons-net|3.8.0|直接依赖|maven|
|org.springframework:spring-jcl|5.3.23|间接依赖|maven|
|org.jacoco:org.jacoco.agent|0.8.5|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.7.4|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.4|间接依赖|maven|
|tech.powerjob:powerjob-worker|4.3.5|直接依赖|maven|
|org.codehaus.groovy:groovy-jsr223|3.0.10|直接依赖|maven|
|io.netty:netty-handler-proxy|4.1.86.Final|间接依赖|maven|
|com.typesafe.akka:akka-pki_2.13|2.6.13|间接依赖|maven|
|org.jboss.xnio:xnio-api|3.8.7.Final|间接依赖|maven|
|org.springframework:spring-tx|5.3.23|间接依赖|maven|
|com.jcraft:jsch|0.1.55|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.4|间接依赖|maven|
|io.netty:netty-codec-http|4.1.86.Final|间接依赖|maven|
|org.mongodb:mongodb-driver-core|4.10.2|间接依赖|maven|
|com.esotericsoftware.kryo:kryo5|5.3.0|直接依赖|maven|
|io.netty:netty-handler|4.1.86.Final|间接依赖|maven|
|com.googlecode.javaewah:JavaEWAH|1.1.7|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-jpa|2.7.4|直接依赖|maven|
|io.vertx:vertx-bridge-common|4.3.7|间接依赖|maven|
|org.javassist:javassist|3.28.0-GA|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.4|间接依赖|maven|
|com.squareup.okhttp3:okhttp|3.14.9|直接依赖|maven|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.7.4|间接依赖|maven|
|org.springframework:spring-websocket|5.3.23|间接依赖|maven|
|jakarta.persistence:jakarta.persistence-api|2.2.3|间接依赖|maven|
|com.aliyun.oss:aliyun-sdk-oss|3.17.1|直接依赖|maven|
|org.jboss:jandex|2.4.2.Final|间接依赖|maven|
|io.swagger.core.v3:swagger-models|2.2.7|间接依赖|maven|
|org.scala-lang:scala-library|2.13.3|间接依赖|maven|
|com.cronutils:cron-utils|9.1.6|直接依赖|maven|
|org.springframework:spring-core|5.3.23|间接依赖|maven|
|org.mongodb:bson|4.10.2|间接依赖|maven|
|org.mongodb:bson-record-codec|4.10.2|间接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|com.sun.xml.fastinfoset:FastInfoset|1.2.15|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.11.4|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.2|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.86.Final|间接依赖|maven|
|org.ini4j:ini4j|0.5.4|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|com.google.guava:guava|31.1-jre|直接依赖|maven|
|org.springframework.data:spring-data-commons|2.7.3|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-actuator|2.7.4|直接依赖|maven|
|org.javassist:javassist|3.27.0-GA|间接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|直接依赖|maven|
|com.aliyun:aliyun-java-sdk-kms|2.11.0|间接依赖|maven|
|com.squareup.okio:okio|1.17.2|间接依赖|maven|
|io.undertow:undertow-core|2.2.19.Final|间接依赖|maven|
|tech.powerjob:powerjob-server-common|4.3.5|直接依赖|maven|
|io.vertx:vertx-web|4.3.7|直接依赖|maven|
|io.opentracing:opentracing-util|0.33.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.14.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-undertow|2.7.4|直接依赖|maven|
|tech.powerjob:powerjob-official-processors|4.3.5|直接依赖|maven|
|mysql:mysql-connector-java|8.0.30|直接依赖|maven|
|com.sun.istack:istack-commons-runtime|3.0.7|间接依赖|maven|
|org.codehaus.jettison:jettison|1.5.4|间接依赖|maven|
|com.h2database:h2|2.1.214|直接依赖|maven|
|io.undertow:undertow-servlet|2.2.19.Final|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.4|间接依赖|maven|
|org.aspectj:aspectjweaver|1.9.7|间接依赖|maven|
|net.lingala.zip4j:zip4j|2.11.2|直接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.4|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.5.1|间接依赖|maven|
|org.checkerframework:checker-qual|3.8.0|间接依赖|maven|
|io.netty:netty-transport|4.1.86.Final|间接依赖|maven|
|tech.powerjob:powerjob-common|4.3.5|直接依赖|maven|
|org.jvnet.staxex:stax-ex|1.8|间接依赖|maven|
|org.codehaus.plexus:plexus-component-annotations|1.7.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.14.0-rc1|直接依赖|maven|
|com.microsoft.sqlserver:mssql-jdbc|7.4.1.jre8|直接依赖|maven|
|com.google.guava:guava|30.1.1-jre|直接依赖|maven|
|commons-io:commons-io|2.11.0|直接依赖|maven|
|jakarta.transaction:jakarta.transaction-api|1.3.3|间接依赖|maven|
|org.apache.commons:commons-collections4|4.4|直接依赖|maven|
|org.agrona:agrona|1.9.0|间接依赖|maven|
|org.springdoc:springdoc-openapi-common|1.6.14|间接依赖|maven|
|io.swagger.core.v3:swagger-annotations|2.2.7|间接依赖|maven|
|io.swagger.core.v3:swagger-core|2.2.7|间接依赖|maven|
|com.typesafe.akka:akka-protobuf-v3_2.13|2.6.13|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.7.4|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-ram|3.1.0|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.86.Final|间接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|2.3.1|间接依赖|maven|
|org.checkerframework:checker-qual|3.12.0|间接依赖|maven|
|io.opentracing:opentracing-api|0.33.0|间接依赖|maven|
|org.glassfish.jaxb:txw2|2.3.1|间接依赖|maven|
|io.github.classgraph:classgraph|4.8.149|间接依赖|maven|
|org.springframework:spring-web|5.3.23|间接依赖|maven|
|org.wildfly.client:wildfly-client-config|1.0.1.Final|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|org.mongodb:mongodb-driver-sync|4.10.2|直接依赖|maven|
|org.springframework:spring-aspects|5.3.23|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|2.7.4|间接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.64|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|直接依赖|maven|
|tech.powerjob:powerjob-remote-impl-akka|4.3.5|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.32|间接依赖|maven|
|org.springframework:spring-aop|5.3.23|间接依赖|maven|
|tech.powerjob:powerjob-server-monitor|4.3.5|直接依赖|maven|
|com.alibaba:fastjson|1.2.83|直接依赖|maven|
|com.hierynomus:asn-one|0.5.0|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.3.Final|间接依赖|maven|
|org.apache.maven.shared:maven-invoker|3.0.1|直接依赖|maven|
|io.vertx:vertx-web-common|4.3.7|间接依赖|maven|
|tech.powerjob:powerjob-remote-impl-http|4.3.5|直接依赖|maven|
|com.google.protobuf:protobuf-java|3.19.4|间接依赖|maven|
|tech.powerjob:powerjob-server-persistence|4.3.5|直接依赖|maven|
|com.ibm.db2:jcc|11.5.0.0|直接依赖|maven|
|io.netty:netty-resolver|4.1.86.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator|2.7.4|间接依赖|maven|
|org.bouncycastle:bcpg-jdk15on|1.64|间接依赖|maven|
|org.webjars:webjars-locator-core|0.52|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|直接依赖|maven|
|org.scala-lang.modules:scala-java8-compat_2.13|0.9.0|间接依赖|maven|
|com.google.code.gson:gson|2.8.6|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.11.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.2|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.9|间接依赖|maven|
|org.springdoc:springdoc-openapi-ui|1.6.14|直接依赖|maven|
|io.undertow:undertow-websockets-jsr|2.2.19.Final|间接依赖|maven|
|com.sun.activation:jakarta.activation|1.2.1|间接依赖|maven|
|org.hibernate:hibernate-core|5.6.11.Final|间接依赖|maven|
|com.oracle.database.jdbc:ojdbc8|19.7.0.0|直接依赖|maven|
|com.typesafe.akka:akka-stream_2.13|2.6.13|间接依赖|maven|
|com.sun.mail:jakarta.mail|1.6.7|间接依赖|maven|
|org.scala-lang.modules:scala-parser-combinators_2.13|1.1.2|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.9|直接依赖|maven|
|com.typesafe.akka:akka-slf4j_2.13|2.6.13|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-mail|2.7.4|直接依赖|maven|
|org.reflections:reflections|0.10.2|直接依赖|maven|
|commons-codec:commons-codec|1.11|间接依赖|maven|
|commons-logging:commons-logging|1.1.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.14.0-rc1|间接依赖|maven|
|org.springframework.boot:spring-boot|2.7.4|间接依赖|maven|
|org.jdom:jdom2|2.0.6.1|间接依赖|maven|
|com.typesafe.akka:akka-actor_2.13|2.6.13|间接依赖|maven|
|org.springframework:spring-context|5.3.23|直接依赖|maven|
|io.vertx:vertx-auth-common|4.3.7|间接依赖|maven|
|jakarta.websocket:jakarta.websocket-api|1.1.2|间接依赖|maven|
|org.apache.maven.shared:maven-shared-utils|3.2.1|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.4|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.30|间接依赖|maven|
|org.postgresql:postgresql|42.2.14|直接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.1.Final|间接依赖|maven|
|org.codehaus.groovy:groovy-json|3.0.10|直接依赖|maven|
|org.springframework.data:spring-data-jpa|2.7.3|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.86.Final|间接依赖|maven|
|com.typesafe.akka:akka-remote_2.13|2.6.13|直接依赖|maven|
|tech.powerjob:powerjob-server-extension|4.3.5|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.4|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.9|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.13|间接依赖|maven|
|org.springframework:spring-expression|5.3.23|间接依赖|maven|
|org.springframework:spring-messaging|5.3.23|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-websocket|2.7.4|直接依赖|maven|
|mysql:mysql-connector-java|8.0.28|直接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|间接依赖|maven|
|org.yaml:snakeyaml|1.30|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.23|间接依赖|maven|
|org.springdoc:springdoc-openapi-webmvc-core|1.6.14|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-core|4.5.10|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.86.Final|间接依赖|maven|
|com.typesafe:ssl-config-core_2.13|0.4.2|间接依赖|maven|
|org.springframework.boot:spring-boot-configuration-processor|2.7.4|直接依赖|maven|
|com.jcraft:jzlib|1.1.1|间接依赖|maven|
|tech.powerjob:powerjob-worker-spring-boot-starter|4.3.5|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.7.4|间接依赖|maven|
|tech.powerjob:powerjob-server-migrate|4.3.5|直接依赖|maven|
|ch.qos.logback:logback-classic|1.2.11|间接依赖|maven|
|tech.powerjob:powerjob-remote-framework|4.3.5|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.14.0|间接依赖|maven|
|jakarta.servlet:jakarta.servlet-api|4.0.4|间接依赖|maven|
|tech.powerjob:powerjob-server-remote|4.3.5|直接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|io.vertx:vertx-core|4.3.7|直接依赖|maven|
|io.netty:netty-buffer|4.1.86.Final|间接依赖|maven|
|org.eclipse.jgit:org.eclipse.jgit|5.7.0.202003110725-r|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.65|间接依赖|maven|
|io.netty:netty-codec|4.1.86.Final|间接依赖|maven|
|com.oracle.database.nls:orai18n|19.7.0.0|直接依赖|maven|
|org.springframework:spring-context-support|5.3.23|间接依赖|maven|
|tech.powerjob:powerjob-server-core|4.3.5|直接依赖|maven|
|org.springframework:spring-jdbc|5.3.23|间接依赖|maven|
|org.apache.commons:commons-lang3|3.10|直接依赖|maven|
|com.aliyun:alibaba-dingtalk-service-sdk|1.0.1|直接依赖|maven|
|ch.qos.logback:logback-core|1.2.11|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.65|间接依赖|maven|
|org.jboss.threads:jboss-threads|3.1.0.Final|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.64|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)