# elunez/eladmin安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692960944869367808.svg)](https://www.murphysec.com/console/report/1692960944802258944/1692960944869367808)

仓库描述：eladmin jpa 版本：项目基于 Spring Boot 2.6.4、 Jpa、 Spring Security、Redis、Vue的前后端分离的后台管理系统，项目采用分模块开发方式， 权限控制采用 RBAC，支持数据字典与数据权限管理，支持一键生成前后端代码，支持动态路由

仓库地址：[https://github.com/elunez/eladmin](https://github.com/elunez/eladmin)

| star：20074 | watch：543 | fork：7170 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-12 18:49:08 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-20 02:06:57 | 组件总数：172 | 漏洞总数：37 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|dom4j SaxReader函数存在 XXE 漏洞|XXE|[MPS-2020-6967](https://www.oscs1024.com/hd/MPS-2020-6967)|CVE-2020-10683|严重|
|Apache Tomcat 条件竞争漏洞|竞争条件|[MPS-2021-37218](https://www.oscs1024.com/hd/MPS-2021-37218)|CVE-2021-43980|低危|
|Bouncy Castle 私钥信息泄露漏洞|竞争条件|[MPS-2021-7064](https://www.oscs1024.com/hd/MPS-2021-7064)|CVE-2020-15522|中危|
|Pivotal Spring Framework 安全限制绕过漏洞|大小写敏感处理不恰当|[MPS-2022-1098](https://www.oscs1024.com/hd/MPS-2022-1098)|CVE-2022-22968|中危|
|Pivotal Spring Framework 拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1100](https://www.oscs1024.com/hd/MPS-2022-1100)|CVE-2022-22971|中危|
|Spring Framework spring-beans 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1101](https://www.oscs1024.com/hd/MPS-2022-1101)|CVE-2022-22970|中危|
|Spring Framework 整数溢出漏洞|整数溢出或环绕|[MPS-2022-1106](https://www.oscs1024.com/hd/MPS-2022-1106)|CVE-2022-22976|中危|
|VMware Spring Security 授权问题漏洞|授权检查错误|[MPS-2022-1108](https://www.oscs1024.com/hd/MPS-2022-1108)|CVE-2022-22978|严重|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|io.springfox:springfox-swagger2 存在输入验证不恰当漏洞|日志敏感信息泄露|[MPS-2022-12534](https://www.oscs1024.com/hd/MPS-2022-12534)||中危|
|Spring Security 绕过授权漏洞|权限、特权和访问控制|[MPS-2022-12722](https://www.oscs1024.com/hd/MPS-2022-12722)|CVE-2022-31692|高危|
|Netty 存在信息泄露漏洞||[MPS-2022-3790](https://www.oscs1024.com/hd/MPS-2022-3790)|CVE-2022-24823|中危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|Bouncy Castle <1.69 认证绕过漏洞|密码学问题|[MPS-2022-54305](https://www.oscs1024.com/hd/MPS-2022-54305)||中危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|Spring Security通配符路由绕过漏洞|关键资源权限分配不当|[MPS-2022-62832](https://www.oscs1024.com/hd/MPS-2022-62832)|CVE-2023-20860|高危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|spring-beans 远程代码执行漏洞(Spring4Shell)|表达式语言注入|[MPS-2022-6820](https://www.oscs1024.com/hd/MPS-2022-6820)|CVE-2022-22965|严重|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|hutool 表达式注入漏洞|SQL注入|[MPS-2023-2459](https://www.oscs1024.com/hd/MPS-2023-2459)|CVE-2023-24163|严重|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|Dream Technology mica 跨站脚本漏洞|XSS|[MPS-gaco-839r](https://www.oscs1024.com/hd/MPS-gaco-839r)|CVE-2023-2220|中危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Spring Security 路径匹配漏洞|不恰当实现的标准安全检查|[MPS-j3nx-691g](https://www.oscs1024.com/hd/MPS-j3nx-691g)|CVE-2023-34034|严重|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.springframework:spring-context|5.3.16|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.6.4|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.squareup.okio:okio|1.17.2|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-messaging|5.3.16|5.3.20|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|dom4j:dom4j|1.6.1||间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework:spring-webmvc|5.3.16|6.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.security:spring-security-crypto|5.6.2|5.6.4|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.1|2.14.0-rc1|间接依赖|建议修复|C:0|H:1|M:3|L:0|
|org.springframework.security:spring-security-web|5.6.2|6.1.2|间接依赖|建议修复|C:2|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.74.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|cn.hutool:hutool-all|5.8.20||直接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework:spring-web|5.3.16|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.yaml:snakeyaml|1.29|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|org.springframework:spring-beans|5.3.16|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.bouncycastle:bcprov-jdk15on|1.62|1.69|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|net.dreamlu:mica-core|2.7.12||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|5.3.16|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|io.netty:netty-common|4.1.74.Final|4.1.77.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.springfox:springfox-swagger2|3.0.0||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.58|11.0.0-m6|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|com.google.guava:guava|27.0.1-android|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:1|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|134|Low|
|LGPL-2.1-or-later|4|Low|
|MIT|8|Low|
|CDDL-1.1|1|Low|
|EPL-2.0|4|Low|
|LGPL-2.1|2|Medium|
|MPL-1.1|1|Low|
|EPL-1.0|3|Low|
|MIT-0|1|Low|
|CDDL-1.0|1|Low|
|BSD-3-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.springframework.data:spring-data-commons|2.6.2|间接依赖|maven|
|org.mapstruct:mapstruct|1.4.2.Final|直接依赖|maven|
|org.springframework:spring-aop|5.3.16|间接依赖|maven|
|io.springfox:springfox-swagger2|3.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-cache|2.6.4|直接依赖|maven|
|javax.mail:mail|1.4.7|直接依赖|maven|
|xerces:xercesImpl|2.12.2|直接依赖|maven|
|org.springframework:spring-messaging|5.3.16|间接依赖|maven|
|org.springframework:spring-jdbc|5.3.16|间接依赖|maven|
|org.yaml:snakeyaml|1.29|间接依赖|maven|
|org.apache.poi:poi-ooxml-lite|5.2.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.1|间接依赖|maven|
|org.hibernate.common:hibernate-commons-annotations|5.1.2.Final|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.17|间接依赖|maven|
|com.sun.istack:istack-commons-runtime|3.0.12|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.62|间接依赖|maven|
|com.google.code.gson:gson|2.8.9|间接依赖|maven|
|io.github.classgraph:classgraph|4.8.83|间接依赖|maven|
|me.zhengjie:eladmin-common|2.7|直接依赖|maven|
|io.springfox:springfox-spring-web|3.0.0|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|com.alibaba:druid-spring-boot-starter|1.2.8|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.13.1|间接依赖|maven|
|org.springframework:spring-oxm|5.3.16|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|commons-configuration:commons-configuration|1.10|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-redis|2.6.4|直接依赖|maven|
|com.qiniu:qiniu-java-sdk|7.9.3|直接依赖|maven|
|io.jsonwebtoken:jjwt-jackson|0.11.5|直接依赖|maven|
|org.springframework.data:spring-data-keyvalue|2.6.2|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.6.4|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.58|间接依赖|maven|
|org.springframework:spring-websocket|5.3.16|间接依赖|maven|
|org.javassist:javassist|3.25.0-GA|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.0|间接依赖|maven|
|io.lettuce:lettuce-core|6.1.6.RELEASE|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.3.Final|间接依赖|maven|
|com.github.virtuald:curvesapi|1.06|间接依赖|maven|
|org.springframework.security:spring-security-crypto|5.6.2|间接依赖|maven|
|io.swagger:swagger-models|1.5.22|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-websocket|2.6.4|直接依赖|maven|
|com.github.whvcse:easy-captcha|1.6.2|直接依赖|maven|
|org.springframework.security:spring-security-config|5.6.2|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.6.4|间接依赖|maven|
|org.bgee.log4jdbc-log4j2:log4jdbc-log4j2-jdbc4.1|1.16|直接依赖|maven|
|net.dreamlu:mica-ip2region|2.7.12|直接依赖|maven|
|dom4j:dom4j|1.6.1|间接依赖|maven|
|org.springframework.data:spring-data-redis|2.6.2|间接依赖|maven|
|org.springframework:spring-orm|5.3.16|间接依赖|maven|
|com.github.oshi:oshi-core|6.1.4|直接依赖|maven|
|ch.qos.logback:logback-core|1.2.9|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|2.6.4|间接依赖|maven|
|io.springfox:springfox-bean-validators|3.0.0|间接依赖|maven|
|com.github.xiaoymin:knife4j-spring-boot-autoconfigure|3.0.3|间接依赖|maven|
|org.springframework.plugin:spring-plugin-core|2.0.0.RELEASE|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.11.22|间接依赖|maven|
|xml-apis:xml-apis|1.4.01|间接依赖|maven|
|io.swagger.core.v3:swagger-models|2.1.2|间接依赖|maven|
|me.zhengjie:eladmin-logging|2.7|直接依赖|maven|
|org.springframework.plugin:spring-plugin-metadata|2.0.0.RELEASE|间接依赖|maven|
|org.springframework:spring-beans|5.3.16|间接依赖|maven|
|org.projectlombok:lombok|1.18.22|直接依赖|maven|
|io.swagger:swagger-core|1.5.22|间接依赖|maven|
|org.aspectj:aspectjweaver|1.9.7|间接依赖|maven|
|org.apache.commons:commons-text|1.10.0|直接依赖|maven|
|cn.hutool:hutool-all|5.8.20|直接依赖|maven|
|jakarta.persistence:jakarta.persistence-api|2.2.3|间接依赖|maven|
|io.netty:netty-buffer|4.1.74.Final|间接依赖|maven|
|org.springframework.data:spring-data-jpa|2.6.2|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|间接依赖|maven|
|org.springframework:spring-expression|5.3.16|间接依赖|maven|
|io.swagger.core.v3:swagger-annotations|2.1.2|间接依赖|maven|
|com.github.xiaoymin:knife4j-spring-ui|3.0.3|间接依赖|maven|
|com.sun.activation:jakarta.activation|1.2.2|间接依赖|maven|
|org.hibernate:hibernate-core|5.6.5.Final|间接依赖|maven|
|com.jcraft:jsch|0.1.55|直接依赖|maven|
|com.mchange:mchange-commons-java|0.2.15|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.6.4|间接依赖|maven|
|org.quartz-scheduler:quartz|2.3.2|直接依赖|maven|
|com.squareup.okio:okio|1.17.2|间接依赖|maven|
|commons-io:commons-io|2.11.0|间接依赖|maven|
|io.jsonwebtoken:jjwt-api|0.11.5|直接依赖|maven|
|io.springfox:springfox-data-rest|3.0.0|间接依赖|maven|
|javax.inject:javax.inject|1|直接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.9|间接依赖|maven|
|com.alibaba:druid|1.2.8|间接依赖|maven|
|net.java.dev.jna:jna-platform|5.10.0|间接依赖|maven|
|me.zhengjie:eladmin-tools|2.7|直接依赖|maven|
|io.springfox:springfox-oas|3.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot|2.6.4|间接依赖|maven|
|io.springfox:springfox-spring-webmvc|3.0.0|间接依赖|maven|
|net.dreamlu:mica-core|2.7.12|间接依赖|maven|
|org.jboss:jandex|2.4.2.Final|间接依赖|maven|
|com.zaxxer:SparseBitSet|1.2|间接依赖|maven|
|io.netty:netty-common|4.1.74.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-freemarker|2.6.4|直接依赖|maven|
|org.springframework:spring-context-support|5.3.16|间接依赖|maven|
|io.netty:netty-handler|4.1.74.Final|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.1|间接依赖|maven|
|org.apache.xmlbeans:xmlbeans|5.0.3|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.1|间接依赖|maven|
|org.apache.poi:poi|5.2.0|直接依赖|maven|
|io.springfox:springfox-swagger-common|3.0.0|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|org.springframework.security:spring-security-core|5.6.2|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.58|间接依赖|maven|
|org.apache.commons:commons-compress|1.21|间接依赖|maven|
|com.alipay.sdk:alipay-sdk-java|4.22.57.ALL|直接依赖|maven|
|org.apache.commons:commons-math3|3.6.1|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.1|间接依赖|maven|
|org.apache.commons:commons-collections4|4.4|间接依赖|maven|
|com.github.xiaoymin:knife4j-core|3.0.3|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-security|2.6.4|直接依赖|maven|
|commons-logging:commons-logging|1.1.1|间接依赖|maven|
|org.freemarker:freemarker|2.3.31|间接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|2.3.6|间接依赖|maven|
|jakarta.transaction:jakarta.transaction-api|1.3.3|间接依赖|maven|
|io.netty:netty-codec|4.1.74.Final|间接依赖|maven|
|com.google.guava:guava|27.0.1-android|间接依赖|maven|
|commons-lang:commons-lang|2.6|间接依赖|maven|
|io.springfox:springfox-schema|3.0.0|间接依赖|maven|
|org.springframework:spring-context|5.3.16|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.2.0|间接依赖|maven|
|org.glassfish.jaxb:txw2|2.3.6|间接依赖|maven|
|com.squareup.okhttp3:okhttp|3.14.9|间接依赖|maven|
|io.projectreactor:reactor-core|3.4.15|间接依赖|maven|
|com.alibaba:fastjson|1.2.83|直接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.1|间接依赖|maven|
|javax.activation:activation|1.1|间接依赖|maven|
|org.springframework.security:spring-security-web|5.6.2|间接依赖|maven|
|io.jsonwebtoken:jjwt-impl|0.11.5|直接依赖|maven|
|io.springfox:springfox-core|3.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-jpa|2.6.4|直接依赖|maven|
|io.springfox:springfox-spi|3.0.0|间接依赖|maven|
|ch.ethz.ganymed:ganymed-ssh2|build210|直接依赖|maven|
|org.apache.commons:commons-pool2|2.11.1|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.1|间接依赖|maven|
|io.netty:netty-transport|4.1.74.Final|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|org.springframework:spring-tx|5.3.16|间接依赖|maven|
|me.zhengjie:eladmin-generator|2.7|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.58|间接依赖|maven|
|org.apache.poi:poi-ooxml|5.2.0|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.6.4|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.1|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.16|间接依赖|maven|
|com.github.xiaoymin:knife4j-annotations|3.0.3|间接依赖|maven|
|org.springframework:spring-aspects|5.3.16|间接依赖|maven|
|net.java.dev.jna:jna|5.10.0|间接依赖|maven|
|io.springfox:springfox-spring-webflux|3.0.0|间接依赖|maven|
|com.github.xiaoymin:knife4j-spring|3.0.3|间接依赖|maven|
|io.netty:netty-resolver|4.1.74.Final|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|com.github.xiaoymin:knife4j-spring-boot-starter|3.0.3|直接依赖|maven|
|org.checkerframework:checker-compat-qual|2.5.2|间接依赖|maven|
|io.netty:netty-tcnative-classes|2.0.48.Final|间接依赖|maven|
|org.springframework:spring-web|5.3.16|间接依赖|maven|
|io.swagger:swagger-annotations|1.5.22|间接依赖|maven|
|io.springfox:springfox-boot-starter|3.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.6.4|直接依赖|maven|
|antlr:antlr|2.7.7|间接依赖|maven|
|mysql:mysql-connector-java|8.0.28|直接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.6.4|间接依赖|maven|
|javax.validation:validation-api|2.0.1.Final|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.6.4|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)