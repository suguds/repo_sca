# karatelabs/karate安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696946560804745216.svg)](https://www.murphysec.com/console/report/1696946560771190784/1696946560804745216)

仓库描述：Test Automation Made Simple

仓库地址：[https://github.com/karatelabs/karate](https://github.com/karatelabs/karate)

| star：7286 | watch：223 | fork：1814 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-29 18:16:02 | 许可证：MIT |
| 最近检测时间：2023-08-31 02:06:33 | 组件总数：206 | 漏洞总数：40 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|Apache Tomcat 条件竞争漏洞|竞争条件|[MPS-2021-37218](https://www.oscs1024.com/hd/MPS-2021-37218)|CVE-2021-43980|低危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|Pivotal Spring Framework 安全限制绕过漏洞|大小写敏感处理不恰当|[MPS-2022-1098](https://www.oscs1024.com/hd/MPS-2022-1098)|CVE-2022-22968|中危|
|Pivotal Spring Framework 拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1100](https://www.oscs1024.com/hd/MPS-2022-1100)|CVE-2022-22971|中危|
|Spring Framework spring-beans 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1101](https://www.oscs1024.com/hd/MPS-2022-1101)|CVE-2022-22970|中危|
|Spring Framework 整数溢出漏洞|整数溢出或环绕|[MPS-2022-1106](https://www.oscs1024.com/hd/MPS-2022-1106)|CVE-2022-22976|中危|
|VMware Spring Security 授权问题漏洞|授权检查错误|[MPS-2022-1108](https://www.oscs1024.com/hd/MPS-2022-1108)|CVE-2022-22978|严重|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|Spring Security 绕过授权漏洞|权限、特权和访问控制|[MPS-2022-12722](https://www.oscs1024.com/hd/MPS-2022-12722)|CVE-2022-31692|高危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|Spring Security通配符路由绕过漏洞|关键资源权限分配不当|[MPS-2022-62832](https://www.oscs1024.com/hd/MPS-2022-62832)|CVE-2023-20860|高危|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|H2 数据库明文密码问题|未授权敏感信息泄露|[MPS-2022-65204](https://www.oscs1024.com/hd/MPS-2022-65204)|CVE-2022-45868|高危|
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
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Spring Security 路径匹配漏洞|不恰当实现的标准安全检查|[MPS-j3nx-691g](https://www.oscs1024.com/hd/MPS-j3nx-691g)|CVE-2023-34034|严重|
|Apache Tomcat FORM 重定向漏洞|跨站重定向|[MPS-uy56-j8e4](https://www.oscs1024.com/hd/MPS-uy56-j8e4)|CVE-2023-41080|低危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.yaml:snakeyaml|1.29|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.60|11.0.0-m6|间接依赖|建议修复|C:0|H:0|M:0|L:2|
|org.springframework.security:spring-security-web|5.6.2|6.1.2|间接依赖|建议修复|C:2|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.15.2||间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-messaging|5.3.18|5.3.20|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-context|5.3.18|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework.security:spring-security-crypto|5.6.2|5.6.4|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-webmvc|5.3.18|6.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.94.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.graalvm.sdk:graal-sdk|22.3.0|22.3.3|间接依赖|建议修复|C:0|H:1|M:4|L:8|
|org.springframework:spring-web|5.3.18|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|commons-codec:commons-codec|1.11|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.springframework:spring-beans|5.3.18|5.3.20|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-io:commons-io|2.5|2.7|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.h2database:h2|2.1.210||直接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-expression|5.3.18|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-core|5.3.18|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.bouncycastle:bcprov-jdk15on|1.70||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.6.6|3.0.7|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|154|Low|
|LGPL-3.0-or-later|6|Low|
|自定义许可证|10|Low|
|MPL-2.0|3|Low|
|EPL-1.0|5|Low|
|EPL-2.0|5|Low|
|BSD-2-Clause|3|Low|
|MIT|15|Low|
|UPL-1.0|5|Low|
|BSD-3-Clause|5|Low|
|MIT-0|1|Low|
|LGPL-2.1|3|Medium|
|MPL-1.1|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.springframework:spring-web|5.3.18|间接依赖|maven|
|com.github.fge:btf|1.2|间接依赖|maven|
|com.aayushatharva.brotli4j:native-linux-x86_64|1.12.0|间接依赖|maven|
|org.bytedeco:openblas-platform|0.3.9-1.5.3|间接依赖|maven|
|com.aayushatharva.brotli4j:native-windows-x86_64|1.6.0|间接依赖|maven|
|com.github.java-json-tools:json-schema-validator|2.2.8|直接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.70|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.94.Final|间接依赖|maven|
|org.bytedeco:leptonica-platform|1.79.0-1.5.3|间接依赖|maven|
|org.springframework.security:spring-security-config|5.6.2|间接依赖|maven|
|org.opentest4j:opentest4j|1.2.0|间接依赖|maven|
|org.bouncycastle:bcutil-jdk15on|1.70|间接依赖|maven|
|io.gatling:gatling-charts|3.7.4|间接依赖|maven|
|commons-io:commons-io|2.5|直接依赖|maven|
|com.aayushatharva.brotli4j:native-linux-aarch64|1.6.0|间接依赖|maven|
|net.debasishg:redisclient_2.13|3.42|间接依赖|maven|
|org.bytedeco:leptonica|1.79.0-1.5.3|间接依赖|maven|
|net.sf.saxon:Saxon-HE|10.6|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.10.0|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.11|间接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.94.Final|间接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.94.Final|间接依赖|maven|
|org.springframework:spring-jcl|5.3.18|间接依赖|maven|
|org.bytedeco:opencv|4.3.0-1.5.3|间接依赖|maven|
|org.springframework:spring-websocket|5.3.18|间接依赖|maven|
|io.micrometer:micrometer-commons|1.11.1|间接依赖|maven|
|com.github.fge:jackson-coreutils|1.8|间接依赖|maven|
|io.gatling:gatling-recorder|3.7.4|间接依赖|maven|
|io.netty:netty-tcnative-classes|2.0.61.Final|间接依赖|maven|
|com.typesafe:config|1.4.0|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.94.Final|间接依赖|maven|
|org.bytedeco:javacv|1.5.3|直接依赖|maven|
|io.gatling:gatling-commons-shared|3.7.4|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.15.2|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.94.Final|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.9.3|间接依赖|maven|
|org.junit.platform:junit-platform-engine|1.9.1|间接依赖|maven|
|org.jodd:jodd-util|6.0.1|间接依赖|maven|
|org.springframework:spring-jdbc|5.3.19|直接依赖|maven|
|org.bytedeco:tesseract-platform|4.1.1-1.5.3|直接依赖|maven|
|joda-time:joda-time|2.9.7|间接依赖|maven|
|io.netty:netty-codec-haproxy|4.1.94.Final|间接依赖|maven|
|io.github.t12y:resemble|1.0.2|直接依赖|maven|
|org.scala-lang.modules:scala-parser-combinators_2.13|2.1.0|间接依赖|maven|
|com.aayushatharva.brotli4j:native-osx-x86_64|1.6.0|间接依赖|maven|
|io.netty:netty-resolver|4.1.94.Final|间接依赖|maven|
|io.github.classgraph:classgraph|4.8.152|直接依赖|maven|
|org.graalvm.regex:regex|22.3.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.15.2|间接依赖|maven|
|org.yaml:snakeyaml|1.29|间接依赖|maven|
|org.springframework:spring-messaging|5.3.18|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.60|间接依赖|maven|
|io.gatling:gatling-commons|3.7.4|间接依赖|maven|
|com.linecorp.armeria:armeria|1.24.3|直接依赖|maven|
|io.micrometer:micrometer-core|1.11.1|间接依赖|maven|
|org.ow2.asm:asm|9.3|间接依赖|maven|
|org.bytedeco:javacpp-platform|1.5.3|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.6.6|间接依赖|maven|
|io.github.t12y:ssim|1.0.0|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-websocket|2.6.6|直接依赖|maven|
|com.eatthepath:fast-uuid|0.2.0|间接依赖|maven|
|javax.mail:mailapi|1.4.3|间接依赖|maven|
|org.springframework.security:spring-security-web|5.6.2|间接依赖|maven|
|org.graalvm.truffle:truffle-api|22.3.0|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.60|间接依赖|maven|
|org.bytedeco:opencv-platform|4.3.0-1.5.3|直接依赖|maven|
|io.netty:netty-tcnative-boringssl-static|2.0.61.Final|间接依赖|maven|
|com.typesafe.akka:akka-actor_2.13|2.6.18|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.2|间接依赖|maven|
|io.gatling:gatling-mqtt|3.7.4|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.18|间接依赖|maven|
|io.gatling:gatling-core|3.7.4|间接依赖|maven|
|org.openjfx:javafx-base|11|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.2|间接依赖|maven|
|org.mozilla:rhino|1.7R4|间接依赖|maven|
|org.scala-lang.modules:scala-java8-compat_2.13|1.0.0|间接依赖|maven|
|info.picocli:picocli|4.7.1|直接依赖|maven|
|de.siegmar:fastcsv|2.2.1|直接依赖|maven|
|org.scala-lang:scala-reflect|2.13.8|间接依赖|maven|
|org.springframework:spring-beans|5.3.18|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.6.6|间接依赖|maven|
|com.h2database:h2|2.1.210|直接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.94.Final|间接依赖|maven|
|javax.activation:activation|1.1|间接依赖|maven|
|org.bytedeco:javacpp|1.5.3|间接依赖|maven|
|commons-io:commons-io|2.7|直接依赖|maven|
|io.gatling:gatling-jdbc-java|3.7.4|间接依赖|maven|
|io.gatling:gatling-http-java|3.7.4|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.6.6|间接依赖|maven|
|com.intuit.karate:karate-core|1.4.0|直接依赖|maven|
|io.gatling:gatling-redis|3.7.4|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.6.6|直接依赖|maven|
|io.netty:netty-handler|4.1.94.Final|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.94.Final|间接依赖|maven|
|io.pebbletemplates:pebble|3.1.5|间接依赖|maven|
|org.springframework:spring-context|5.3.18|间接依赖|maven|
|com.softwaremill.quicklens:quicklens_2.13|1.8.2|间接依赖|maven|
|io.gatling:gatling-graphite|3.7.4|间接依赖|maven|
|org.attoparser:attoparser|2.0.5.RELEASE|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.9|直接依赖|maven|
|org.junit.jupiter:junit-jupiter-api|5.9.1|直接依赖|maven|
|org.bytedeco:tesseract|4.1.1-1.5.3|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.1|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.94.Final|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-engine|5.9.1|直接依赖|maven|
|com.aayushatharva.brotli4j:brotli4j|1.12.0|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|com.github.java-json-tools:json-schema-core|1.2.8|间接依赖|maven|
|org.bytedeco:openblas|0.3.9-1.5.3|间接依赖|maven|
|org.springframework:spring-expression|5.3.18|间接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.70|间接依赖|maven|
|com.jayway.jsonpath:json-path|2.8.0|直接依赖|maven|
|io.burt:jmespath-core|0.5.1|间接依赖|maven|
|org.jodd:jodd-lagarto|6.0.5|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.6.6|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|org.junit.platform:junit-platform-commons|1.9.1|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.2|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.2|间接依赖|maven|
|io.gatling:gatling-app|3.7.4|间接依赖|maven|
|io.gatling:gatling-netty-util|3.7.4|间接依赖|maven|
|org.springframework:spring-tx|5.3.18|间接依赖|maven|
|io.gatling:gatling-http|3.7.4|间接依赖|maven|
|io.suzaku:boopickle_2.13|1.3.3|间接依赖|maven|
|org.antlr:antlr4-runtime|4.11.1|直接依赖|maven|
|org.springframework.boot:spring-boot|2.6.6|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.60|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.15.2|间接依赖|maven|
|org.unbescape:unbescape|1.1.6.RELEASE|间接依赖|maven|
|com.aayushatharva.brotli4j:service|1.12.0|间接依赖|maven|
|net.jodah:typetools|0.6.3|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.11|间接依赖|maven|
|ognl:ognl|3.1.26|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.94.Final|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.15.2|间接依赖|maven|
|org.bytedeco:ffmpeg|4.2.2-1.5.3|间接依赖|maven|
|commons-codec:commons-codec|1.11|间接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.94.Final|间接依赖|maven|
|io.micrometer:micrometer-observation|1.11.1|间接依赖|maven|
|org.apiguardian:apiguardian-api|1.1.2|间接依赖|maven|
|net.minidev:json-smart|2.4.10|直接依赖|maven|
|org.thymeleaf:thymeleaf|3.0.14.RELEASE|直接依赖|maven|
|io.netty:netty-transport|4.1.94.Final|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.16|间接依赖|maven|
|io.gatling:gatling-core-java|3.7.4|间接依赖|maven|
|io.gatling:gatling-jsonpath|3.7.4|间接依赖|maven|
|net.java.dev.jna:jna-platform|5.5.0|直接依赖|maven|
|org.graalvm.js:js-scriptengine|22.3.0|直接依赖|maven|
|org.typelevel:spire-macros_2.13|0.17.0|间接依赖|maven|
|org.springframework:spring-core|5.3.18|间接依赖|maven|
|com.github.fge:uri-template|0.9|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.9|间接依赖|maven|
|org.springframework.security:spring-security-core|5.6.2|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.25|间接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.14|直接依赖|maven|
|com.typesafe.akka:akka-slf4j_2.13|2.6.18|间接依赖|maven|
|io.gatling.highcharts:gatling-charts-highcharts|3.7.4|直接依赖|maven|
|io.netty:netty-codec-mqtt|4.1.73.Final|间接依赖|maven|
|com.github.scopt:scopt_2.13|3.7.1|间接依赖|maven|
|io.netty:netty-common|4.1.94.Final|间接依赖|maven|
|net.java.dev.jna:jna|5.5.0|间接依赖|maven|
|javax.jms:javax.jms-api|2.0.1|间接依赖|maven|
|io.gatling:gatling-jms-java|3.7.4|间接依赖|maven|
|org.simpleflatmapper:sfm-util|8.2.3|间接依赖|maven|
|io.netty:netty-codec-http|4.1.94.Final|间接依赖|maven|
|com.googlecode.libphonenumber:libphonenumber|8.0.0|间接依赖|maven|
|org.openjfx:javafx-graphics|11|间接依赖|maven|
|io.gatling:gatling-mqtt-java|3.7.4|间接依赖|maven|
|com.typesafe.scala-logging:scala-logging_2.13|3.9.4|间接依赖|maven|
|org.simpleflatmapper:lightning-csv|8.2.3|间接依赖|maven|
|net.sf.jopt-simple:jopt-simple|5.0.3|间接依赖|maven|
|org.graalvm.sdk:graal-sdk|22.3.0|间接依赖|maven|
|io.netty:netty-codec|4.1.94.Final|间接依赖|maven|
|io.gatling:gatling-jdbc|3.7.4|间接依赖|maven|
|io.burt:jmespath-jackson|0.5.1|间接依赖|maven|
|io.netty:netty-buffer|4.1.94.Final|间接依赖|maven|
|org.scala-lang.modules:scala-swing_2.13|3.0.0|间接依赖|maven|
|org.apache.commons:commons-pool2|2.8.0|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.94.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-security|2.6.6|直接依赖|maven|
|io.netty:netty-tcnative-boringssl-static|2.0.47.Final|间接依赖|maven|
|org.javassist:javassist|3.20.0-GA|间接依赖|maven|
|org.springframework:spring-aop|5.3.18|间接依赖|maven|
|com.ibm.icu:icu4j|71.1|间接依赖|maven|
|:No dependencies||直接依赖|maven|
|io.gatling:gatling-commons-shared-unstable|3.7.4|间接依赖|maven|
|org.yaml:snakeyaml|2.0|直接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.32|直接依赖|maven|
|io.gatling:gatling-jms|3.7.4|间接依赖|maven|
|org.springframework.security:spring-security-crypto|5.6.2|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.94.Final|间接依赖|maven|
|io.gatling:gatling-http-client|3.7.4|间接依赖|maven|
|org.scala-lang:scala-library|2.13.9|直接依赖|maven|
|org.checkerframework:checker-qual|3.19.0|间接依赖|maven|
|com.tdunning:t-digest|3.1|间接依赖|maven|
|org.bytedeco:ffmpeg-platform|4.2.2-1.5.3|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.15.2|间接依赖|maven|
|io.gatling:gatling-redis-java|3.7.4|间接依赖|maven|
|net.minidev:accessors-smart|2.4.9|间接依赖|maven|
|org.graalvm.js:js|22.3.0|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.6.6|间接依赖|maven|
|com.github.fge:msg-simple|1.1|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)