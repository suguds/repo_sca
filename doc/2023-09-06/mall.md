# macrozheng/mall安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699121416301576192.svg)](https://www.murphysec.com/console/report/1690987019704754176/1699121416301576192)

仓库描述：mall项目是一套电商系统，包括前台商城系统及后台管理系统，基于SpringBoot+MyBatis实现，采用Docker容器化部署。 前台商城系统包含首页门户、商品推荐、商品搜索、商品展示、购物车、订单流程、会员中心、客户服务、帮助中心等模块。 后台管理系统包含商品管理、订单管理、会员管理、促销管理、运营管理、内容管理、统计报表、财务管理、权限管理、设置等模块。

仓库地址：[https://github.com/macrozheng/mall](https://github.com/macrozheng/mall)

| star：69652 | watch：2231 | fork：27507 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-04 14:48:36 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-06 02:06:23 | 组件总数：205 | 漏洞总数：47 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache Struts 远程代码执行漏洞|输入验证不恰当|[MPS-2014-2167](https://www.oscs1024.com/hd/MPS-2014-2167)|CVE-2014-0114|高危|
|多款Cisco产品Apache Commons Collections库任意代码执行漏洞|反序列化|[MPS-2015-6277](https://www.oscs1024.com/hd/MPS-2015-6277)|CVE-2015-6420|高危|
|多款Red Hat产品代码问题漏洞|反序列化|[MPS-2017-12638](https://www.oscs1024.com/hd/MPS-2017-12638)|CVE-2015-7501|严重|
|Apache Commons Beanutils 存在不可信数据的反序列化漏洞|反序列化|[MPS-2019-10233](https://www.oscs1024.com/hd/MPS-2019-10233)|CVE-2019-10086|高危|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|JDOM 存在 XXE 注入漏洞|XXE|[MPS-2021-8350](https://www.oscs1024.com/hd/MPS-2021-8350)|CVE-2021-33813|高危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|io.springfox:springfox-swagger2 存在输入验证不恰当漏洞|日志敏感信息泄露|[MPS-2022-12534](https://www.oscs1024.com/hd/MPS-2022-12534)||中危|
|Spring Security 绕过授权漏洞|权限、特权和访问控制|[MPS-2022-12722](https://www.oscs1024.com/hd/MPS-2022-12722)|CVE-2022-31692|高危|
|Apache Commons Collections 远程代码执行漏洞|反序列化|[MPS-2022-12767](https://www.oscs1024.com/hd/MPS-2022-12767)||高危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|protobuf-java 存在输入验证不当漏洞|拒绝服务|[MPS-2022-56472](https://www.oscs1024.com/hd/MPS-2022-56472)|CVE-2022-3171|中危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|Google protobuf 安全漏洞|拒绝服务|[MPS-2022-59814](https://www.oscs1024.com/hd/MPS-2022-59814)|CVE-2022-3510|高危|
|Spring Security通配符路由绕过漏洞|关键资源权限分配不当|[MPS-2022-62832](https://www.oscs1024.com/hd/MPS-2022-62832)|CVE-2023-20860|高危|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Security Logout实现不当|会话固定|[MPS-2022-62834](https://www.oscs1024.com/hd/MPS-2022-62834)|CVE-2023-20862|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot在Cloud Foundry中部署存在路由限制绕过风险|访问控制不当|[MPS-2022-62845](https://www.oscs1024.com/hd/MPS-2022-62845)|CVE-2023-20873|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|Hutool 存在拒绝服务漏洞|越界写入|[MPS-2022-64976](https://www.oscs1024.com/hd/MPS-2022-64976)|CVE-2022-45688|中危|
|Hutool 存在拒绝服务漏洞|越界写入|[MPS-2022-64977](https://www.oscs1024.com/hd/MPS-2022-64977)|CVE-2022-45689|中危|
|Hutool 存在拒绝服务漏洞|越界写入|[MPS-2022-64978](https://www.oscs1024.com/hd/MPS-2022-64978)|CVE-2022-45690|中危|
|Hutool zip 拒绝服务漏洞||[MPS-2022-68308](https://www.oscs1024.com/hd/MPS-2022-68308)|CVE-2022-4565|中危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|hutool 表达式注入漏洞|SQL注入|[MPS-2023-2459](https://www.oscs1024.com/hd/MPS-2023-2459)|CVE-2023-24163|严重|
|hutool 存在反序列化漏洞|反序列化|[MPS-2023-2460](https://www.oscs1024.com/hd/MPS-2023-2460)|CVE-2023-24162|高危|
|hutool 存在任意代码执行漏洞|代码注入|[MPS-2023-7335](https://www.oscs1024.com/hd/MPS-2023-7335)||严重|
|Hutool createTempFile函数敏感信息泄漏漏洞|未授权敏感信息泄露|[MPS-4soz-eyma](https://www.oscs1024.com/hd/MPS-4soz-eyma)|CVE-2023-33695|中危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Spring Security 路径匹配漏洞|不恰当实现的标准安全检查|[MPS-j3nx-691g](https://www.oscs1024.com/hd/MPS-j3nx-691g)|CVE-2023-34034|严重|
|hutool <=5.8.17 存在SPEL命令执行风险|代码注入|[MPS-jdrq-1ywv](https://www.oscs1024.com/hd/MPS-jdrq-1ywv)||高危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|Apache Tomcat FORM 重定向漏洞|跨站重定向|[MPS-uy56-j8e4](https://www.oscs1024.com/hd/MPS-uy56-j8e4)|CVE-2023-41080|低危|
|HuTool XML外部实体注入漏洞|XXE|[MPS-xd3s-4gev](https://www.oscs1024.com/hd/MPS-xd3s-4gev)|CVE-2023-3276|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|cn.hutool:hutool-all|5.8.9|5.8.19|直接依赖|强烈建议修复|C:1|H:2|M:1|L:0|
|commons-beanutils:commons-beanutils|1.8.0|1.9.4|间接依赖|强烈建议修复|C:0|H:2|M:0|L:0|
|com.squareup.okio:okio|2.8.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.68|11.0.0-m6|间接依赖|建议修复|C:0|H:0|M:0|L:1|
|org.springframework:spring-webmvc|5.3.23|6.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.4.2|2.14.0-rc1|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework.security:spring-security-web|5.7.4|6.1.2|间接依赖|建议修复|C:1|H:1|M:1|L:0|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.7.5|3.0.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.xerial.snappy:snappy-java|1.1.8.4|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.7.5|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.84.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|commons-collections:commons-collections|3.2.1|3.2.2|间接依赖|建议修复|C:1|H:2|M:0|L:0|
|org.springframework:spring-web|5.3.23|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.yaml:snakeyaml|1.30|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|com.google.guava:guava|30.1.1-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|5.3.23|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.jdom:jdom|1.1||间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-core|5.3.23|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.protobuf:protobuf-java|3.19.4|3.21.7|间接依赖|可选修复|C:0|H:1|M:2|L:0|
|io.springfox:springfox-swagger2|3.0.0||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.bouncycastle:bcprov-jdk15on|1.69||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|162|Low|
|MIT|10|Low|
|BSD-3-Clause|1|Low|
|自定义许可证|20|Low|
|GPL-2.0|1|Medium|
|MPL-2.0|1|Low|
|EPL-2.0|4|Low|
|LGPL-2.1-or-later|1|Low|
|MIT-0|1|Low|
|BSD-2-Clause|1|Low|
|EPL-1.0|2|Low|
|CDDL-1.1|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.apache.lucene:lucene-analyzers-common|8.11.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-mongodb|2.7.5|直接依赖|maven|
|org.mongodb:mongodb-driver-sync|4.6.1|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.3.Final|间接依赖|maven|
|com.github.pagehelper:pagehelper-spring-boot-autoconfigure|1.4.5|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.19.4|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.68|间接依赖|maven|
|org.springframework.data:spring-data-keyvalue|2.7.5|间接依赖|maven|
|com.github.pagehelper:pagehelper-spring-boot-starter|1.4.5|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.15|间接依赖|maven|
|org.springframework.boot:spring-boot|2.7.5|间接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-high-level-client|7.17.6|间接依赖|maven|
|com.github.pagehelper:pagehelper|5.3.2|直接依赖|maven|
|commons-lang:commons-lang|2.5|间接依赖|maven|
|io.netty:netty-common|4.1.84.Final|间接依赖|maven|
|net.sf.jopt-simple:jopt-simple|5.0.2|间接依赖|maven|
|com.rabbitmq:amqp-client|5.14.2|间接依赖|maven|
|org.apache.lucene:lucene-highlighter|8.11.1|间接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-starter|2.2.2|间接依赖|maven|
|com.tdunning:t-digest|3.2|间接依赖|maven|
|org.eclipse.parsson:parsson|1.0.0|间接依赖|maven|
|org.mybatis:mybatis|3.5.10|间接依赖|maven|
|org.springframework.security:spring-security-web|5.7.4|间接依赖|maven|
|com.carrotsearch.thirdparty:simple-xml-safe|2.7.1|间接依赖|maven|
|org.apache.lucene:lucene-spatial3d|8.11.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-elasticsearch|2.7.5|直接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.2.5.Final|间接依赖|maven|
|io.github.classgraph:classgraph|4.8.83|间接依赖|maven|
|org.springframework.data:spring-data-commons|2.7.5|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|2.7.5|直接依赖|maven|
|org.apache.lucene:lucene-misc|8.11.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-validation|2.7.5|直接依赖|maven|
|org.apache.lucene:lucene-core|8.11.1|间接依赖|maven|
|org.elasticsearch.plugin:mapper-extras-client|7.17.6|间接依赖|maven|
|org.aspectj:aspectjweaver|1.9.7|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-security|2.7.5|直接依赖|maven|
|org.springframework.retry:spring-retry|1.3.4|间接依赖|maven|
|io.netty:netty-codec|4.1.84.Final|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|间接依赖|maven|
|io.springfox:springfox-schema|3.0.0|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.13.4|间接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|间接依赖|maven|
|com.macro.mall:mall-common|1.0-SNAPSHOT|直接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.6.21|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.5|间接依赖|maven|
|org.apache.lucene:lucene-memory|8.11.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.7.5|直接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.5|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.7.5|间接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.15|间接依赖|maven|
|io.springfox:springfox-data-rest|3.0.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.2|间接依赖|maven|
|net.java.dev.jna:jna|5.10.0|间接依赖|maven|
|org.mongodb:bson|4.6.1|间接依赖|maven|
|io.netty:netty-handler|4.1.84.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-configuration-processor|2.7.5|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.7.5|间接依赖|maven|
|com.carrotsearch:hppc|0.8.1|间接依赖|maven|
|org.unbescape:unbescape|1.1.6.RELEASE|间接依赖|maven|
|com.macro.mall:mall-security|1.0-SNAPSHOT|直接依赖|maven|
|org.elasticsearch:elasticsearch|7.17.6|间接依赖|maven|
|org.springframework:spring-context|5.3.23|间接依赖|maven|
|org.springframework.plugin:spring-plugin-core|2.0.0.RELEASE|间接依赖|maven|
|io.swagger:swagger-models|1.6.0|间接依赖|maven|
|io.swagger.core.v3:swagger-models|2.1.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-redis|2.7.5|直接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-autoconfigure|2.2.2|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|org.thymeleaf:thymeleaf-spring5|3.0.15.RELEASE|间接依赖|maven|
|org.springframework:spring-messaging|5.3.23|间接依赖|maven|
|jakarta.json:jakarta.json-api|1.1.6|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.2|间接依赖|maven|
|io.springfox:springfox-bean-validators|3.0.0|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.4|间接依赖|maven|
|com.github.spullara.mustache.java:compiler|0.9.6|间接依赖|maven|
|commons-collections:commons-collections|3.2.1|间接依赖|maven|
|org.elasticsearch.plugin:aggs-matrix-stats-client|7.17.6|间接依赖|maven|
|io.springfox:springfox-spi|3.0.0|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|org.mybatis:mybatis-spring|2.0.7|间接依赖|maven|
|org.springframework:spring-beans|5.3.23|间接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator|2.7.5|间接依赖|maven|
|io.micrometer:micrometer-core|1.9.5|间接依赖|maven|
|org.springframework:spring-web|5.3.23|间接依赖|maven|
|org.jdom:jdom|1.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.4|间接依赖|maven|
|io.swagger:swagger-annotations|1.6.0|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.7.5|间接依赖|maven|
|org.springframework.data:spring-data-redis|2.7.5|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.68|间接依赖|maven|
|io.springfox:springfox-swagger-common|3.0.0|间接依赖|maven|
|org.springframework:spring-jdbc|5.3.23|间接依赖|maven|
|org.apache.lucene:lucene-join|8.11.1|间接依赖|maven|
|org.elasticsearch:elasticsearch-geo|7.17.6|间接依赖|maven|
|co.elastic.clients:elasticsearch-java|7.17.6|间接依赖|maven|
|org.thymeleaf.extras:thymeleaf-extras-java8time|3.0.4.RELEASE|间接依赖|maven|
|io.springfox:springfox-oas|3.0.0|间接依赖|maven|
|io.jsonwebtoken:jjwt|0.9.1|直接依赖|maven|
|org.attoparser:attoparser|2.0.5.RELEASE|间接依赖|maven|
|org.elasticsearch:elasticsearch-cli|7.17.6|间接依赖|maven|
|org.springframework.security:spring-security-config|5.7.4|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|间接依赖|maven|
|org.springframework:spring-expression|5.3.23|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.68|间接依赖|maven|
|org.apache.lucene:lucene-suggest|8.11.1|间接依赖|maven|
|org.apache.lucene:lucene-sandbox|8.11.1|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|org.elasticsearch.plugin:rank-eval-client|7.17.6|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-smile|2.13.4|间接依赖|maven|
|org.thymeleaf:thymeleaf|3.0.15.RELEASE|间接依赖|maven|
|org.apache.lucene:lucene-queries|8.11.1|间接依赖|maven|
|com.aliyun.oss:aliyun-sdk-oss|2.5.0|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.6.21|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.7.5|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.4|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-amqp|2.7.5|直接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|com.google.guava:guava|30.1.1-jre|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.4|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.5|间接依赖|maven|
|org.mapstruct:mapstruct|1.3.1.Final|间接依赖|maven|
|io.projectreactor:reactor-core|3.4.24|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-thymeleaf|2.7.5|直接依赖|maven|
|org.springframework:spring-aop|5.3.23|间接依赖|maven|
|net.logstash.logback:logstash-logback-encoder|7.2|直接依赖|maven|
|org.springframework:spring-jcl|5.3.23|间接依赖|maven|
|io.springfox:springfox-spring-webmvc|3.0.0|间接依赖|maven|
|org.springframework.security:spring-security-core|5.7.4|间接依赖|maven|
|org.mongodb:bson-record-codec|4.6.1|间接依赖|maven|
|org.elasticsearch:elasticsearch-secure-sm|7.17.6|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|io.springfox:springfox-core|3.0.0|间接依赖|maven|
|org.springframework:spring-core|5.3.23|间接依赖|maven|
|org.lz4:lz4-java|1.8.0|间接依赖|maven|
|org.apache.commons:commons-compress|1.21|间接依赖|maven|
|org.springframework.data:spring-data-elasticsearch|4.4.5|间接依赖|maven|
|org.elasticsearch.plugin:parent-join-client|7.17.6|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.84.Final|间接依赖|maven|
|mysql:mysql-connector-java|8.0.29|直接依赖|maven|
|org.springframework.data:spring-data-mongodb|3.4.5|间接依赖|maven|
|io.springfox:springfox-swagger-ui|3.0.0|间接依赖|maven|
|org.apache.lucene:lucene-queryparser|8.11.1|间接依赖|maven|
|org.elasticsearch.plugin:lang-mustache-client|7.17.6|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.4|间接依赖|maven|
|org.yaml:snakeyaml|1.30|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.5.1|间接依赖|maven|
|com.macro.mall:mall-mbg|1.0-SNAPSHOT|直接依赖|maven|
|org.projectlombok:lombok|1.18.24|直接依赖|maven|
|org.checkerframework:checker-qual|3.8.0|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.23|间接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-client|7.17.6|间接依赖|maven|
|com.github.jsqlparser:jsqlparser|4.5|间接依赖|maven|
|org.springframework:spring-context-support|5.3.23|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.4|间接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|org.apache.lucene:lucene-grouping|8.11.1|间接依赖|maven|
|io.springfox:springfox-spring-webflux|3.0.0|间接依赖|maven|
|io.lettuce:lettuce-core|6.1.10.RELEASE|间接依赖|maven|
|io.swagger.core.v3:swagger-annotations|2.1.2|间接依赖|maven|
|org.elasticsearch:elasticsearch-plugin-classloader|7.17.6|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.11|间接依赖|maven|
|joda-time:joda-time|2.10.10|间接依赖|maven|
|io.netty:netty-resolver|4.1.84.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.4.2|间接依赖|maven|
|org.springframework.plugin:spring-plugin-metadata|2.0.0.RELEASE|间接依赖|maven|
|io.netty:netty-transport|4.1.84.Final|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.69|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.7.5|间接依赖|maven|
|org.springframework:spring-oxm|5.3.23|间接依赖|maven|
|cn.hutool:hutool-all|5.8.9|直接依赖|maven|
|org.springframework.security:spring-security-crypto|5.7.4|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.13.4|间接依赖|maven|
|org.springframework:spring-tx|5.3.23|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.11|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|直接依赖|maven|
|com.squareup.okio:okio|2.8.0|间接依赖|maven|
|net.sf.ezmorph:ezmorph|1.0.6|间接依赖|maven|
|io.springfox:springfox-spring-web|3.0.0|间接依赖|maven|
|com.squareup.okhttp3:okhttp|4.9.3|间接依赖|maven|
|net.sf.json-lib:json-lib|2.4|间接依赖|maven|
|io.springfox:springfox-boot-starter|3.0.0|直接依赖|maven|
|commons-logging:commons-logging|1.1.1|间接依赖|maven|
|io.springfox:springfox-swagger2|3.0.0|间接依赖|maven|
|org.springframework.amqp:spring-amqp|2.4.7|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-actuator|2.7.5|直接依赖|maven|
|org.springframework.amqp:spring-rabbit|2.4.7|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|org.elasticsearch:elasticsearch-core|7.17.6|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|间接依赖|maven|
|io.netty:netty-buffer|4.1.84.Final|间接依赖|maven|
|org.elasticsearch:elasticsearch-x-content|7.17.6|间接依赖|maven|
|com.alibaba:druid-spring-boot-starter|1.2.14|直接依赖|maven|
|org.mongodb:mongodb-driver-core|4.6.1|间接依赖|maven|
|org.apache.lucene:lucene-backward-codecs|8.11.1|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.8.0|间接依赖|maven|
|org.mybatis.generator:mybatis-generator-core|1.4.1|直接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|org.elasticsearch:elasticsearch-lz4|7.17.6|间接依赖|maven|
|io.minio:minio|8.4.5|直接依赖|maven|
|com.alibaba:druid|1.2.14|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)