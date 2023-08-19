# spring-projects/spring-boot安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692961208342962176.svg)](https://www.murphysec.com/console/report/1692438692105052160/1692961208342962176)

仓库描述：Spring Boot

仓库地址：[https://github.com/spring-projects/spring-boot](https://github.com/spring-projects/spring-boot)

| star：68958 | watch：3375 | fork：39283 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-20 00:31:48 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-20 03:37:06 | 组件总数：59 | 漏洞总数：43 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Spring Framework XML外部实体注入漏洞|权限、特权和访问控制|[MPS-2014-0435](https://www.oscs1024.com/hd/MPS-2014-0435)|CVE-2013-4152|中危|
|Spring Framework <3.2.4.RELEASE XML外部实体注入漏洞|权限、特权和访问控制|[MPS-2014-0439](https://www.oscs1024.com/hd/MPS-2014-0439)|CVE-2013-7315|中危|
|Spring Framework 外部实体注入漏洞||[MPS-2014-0481](https://www.oscs1024.com/hd/MPS-2014-0481)|CVE-2013-6429|中危|
|Spring Framework XML外部实体注入漏洞|CSRF|[MPS-2014-1941](https://www.oscs1024.com/hd/MPS-2014-1941)|CVE-2014-0054|中危|
|Pivotal Software Spring Framework 目录遍历漏洞|路径遍历|[MPS-2015-1090](https://www.oscs1024.com/hd/MPS-2015-1090)|CVE-2014-3578|中危|
|Pivotal Software Spring Framework 安全漏洞|缓冲区溢出|[MPS-2016-3388](https://www.oscs1024.com/hd/MPS-2016-3388)|CVE-2015-3192|中危|
|QOS.ch Logback SocketServer和ServerSocketReceiver组件代码问题漏洞|反序列化|[MPS-2017-2574](https://www.oscs1024.com/hd/MPS-2017-2574)|CVE-2017-5929|严重|
|Pivotal Spring Framework 安全漏洞|XXE|[MPS-2017-5898](https://www.oscs1024.com/hd/MPS-2017-5898)|CVE-2014-0225|高危|
|Spring Framework 反射文件下载(RFD)漏洞|对外部实体的文件或目录可访问|[MPS-2017-5904](https://www.oscs1024.com/hd/MPS-2017-5904)|CVE-2015-5211|严重|
|SnakeYAML <1.26 存在 Billion laughs 漏洞|拒绝服务|[MPS-2019-16129](https://www.oscs1024.com/hd/MPS-2019-16129)|CVE-2017-18640|高危|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|Pivotal Spring Framework 反射文件下载 (RFD) 漏洞|路径遍历|[MPS-2020-13322](https://www.oscs1024.com/hd/MPS-2020-13322)|CVE-2020-5421|中危|
|FasterXML jackson-databind 代码问题漏洞|XXE|[MPS-2020-17358](https://www.oscs1024.com/hd/MPS-2020-17358)|CVE-2020-25649|高危|
|Spring Framework <5.3.14 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18854](https://www.oscs1024.com/hd/MPS-2021-18854)|CVE-2021-22060|中危|
|Pivotal Spring Framework 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18890](https://www.oscs1024.com/hd/MPS-2021-18890)|CVE-2021-22096|中危|
|VMware Spring Security 权限许可和访问控制问题漏洞|权限、特权和访问控制|[MPS-2021-2094](https://www.oscs1024.com/hd/MPS-2021-2094)|CVE-2021-22112|高危|
|Quality Open Software logback JNDI注入漏洞|反序列化|[MPS-2021-33911](https://www.oscs1024.com/hd/MPS-2021-33911)|CVE-2021-42550|中危|
|Spring Framework权限许可和访问控制问题漏洞|权限管理不当|[MPS-2021-7485](https://www.oscs1024.com/hd/MPS-2021-7485)|CVE-2021-22118|高危|
|Vmware Spring Framework 安全漏洞|不加限制或调节的资源分配|[MPS-2022-1080](https://www.oscs1024.com/hd/MPS-2022-1080)|CVE-2022-22950|中危|
|Pivotal Spring Framework 安全限制绕过漏洞|大小写敏感处理不恰当|[MPS-2022-1098](https://www.oscs1024.com/hd/MPS-2022-1098)|CVE-2022-22968|中危|
|Spring Framework spring-beans 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1101](https://www.oscs1024.com/hd/MPS-2022-1101)|CVE-2022-22970|中危|
|VMware Spring Security 授权问题漏洞|授权检查错误|[MPS-2022-1108](https://www.oscs1024.com/hd/MPS-2022-1108)|CVE-2022-22978|严重|
|Pivotal Spring Framework CSRF 令牌泄露漏洞|通过时间差异性导致的信息暴露|[MPS-2022-11893](https://www.oscs1024.com/hd/MPS-2022-11893)||低危|
|Logback SSL证书校验不当漏洞|中间人攻击|[MPS-2022-12411](https://www.oscs1024.com/hd/MPS-2022-12411)||中危|
|FasterXML Jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2022-12500](https://www.oscs1024.com/hd/MPS-2022-12500)||中危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|spring-boot <2.2.11.RELEASE 存在目录劫持漏洞|将资源暴露给错误范围|[MPS-2022-6780](https://www.oscs1024.com/hd/MPS-2022-6780)|CVE-2022-27772|高危|
|spring-beans 远程代码执行漏洞(Spring4Shell)|表达式语言注入|[MPS-2022-6820](https://www.oscs1024.com/hd/MPS-2022-6820)|CVE-2022-22965|严重|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2023-8438](https://www.oscs1024.com/hd/MPS-2023-8438)|CVE-2021-46877|中危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.springframework.boot:spring-boot-autoconfigure|2.2.4.RELEASE|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-web|3.2.3.RELEASE|6.0.0|间接依赖|建议修复|C:2|H:1|M:6|L:0|
|org.springframework.security:spring-security-core|3.2.0.M2|5.4.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-context|5.2.3.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.10.2|2.14.0-rc1|直接依赖|建议修复|C:0|H:2|M:5|L:0|
|org.springframework.security:spring-security-web|3.2.0.M2|6.1.2|直接依赖|建议修复|C:1|H:0|M:0|L:1|
|ch.qos.logback:logback-classic|1.0.13|1.2.0|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework:spring-beans|3.2.3.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework.boot:spring-boot|2.2.4.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-beans|5.2.3.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.yaml:snakeyaml|1.25|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|ch.qos.logback:logback-core|1.2.3|1.2.8|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-context|3.2.3.RELEASE|5.3.19|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-web|5.2.3.RELEASE|6.0.0|直接依赖|建议修复|C:1|H:1|M:1|L:0|
|ch.qos.logback:logback-core|1.0.13|1.2.8|间接依赖|建议修复|C:1|H:0|M:2|L:0|
|org.bouncycastle:bcprov-jdk18on|1.71|1.74|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|5.2.3.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.springframework:spring-core|5.2.3.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|org.springframework:spring-core|3.2.3.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|org.springframework:spring-expression|3.2.3.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|40|Low|
|EPL-1.0|4|Low|
|EPL-2.0|1|Low|
|MIT|3|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.springframework.boot:spring-boot|@project.version@|直接依赖|maven|
|org.springframework.boot.maven.it:acme-lib|0.0.1.BUILD-SNAPSHOT|直接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|ch.qos.logback:logback-classic|1.0.13|直接依赖|maven|
|org.yaml:snakeyaml|1.25|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.12.1|间接依赖|maven|
|ch.qos.logback:logback-core|1.0.13|间接依赖|maven|
|org.springframework:spring-beans|5.2.3.RELEASE|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|@log4j2.version@|直接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.12.1|间接依赖|maven|
|org.hamcrest:hamcrest|2.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.10.2|直接依赖|maven|
|org.springframework:spring-core|3.2.3.RELEASE|间接依赖|maven|
|org.springframework.security:spring-security-web|3.2.0.M2|直接依赖|maven|
|org.springframework:spring-jcl|5.2.3.RELEASE|间接依赖|maven|
|org.springframework:spring-expression|3.2.3.RELEASE|间接依赖|maven|
|org.springframework.boot.maven.it.another:acme-lib|0.0.1.BUILD-SNAPSHOT|直接依赖|maven|
|org.springframework.boot:spring-boot-starter||间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.10.2|直接依赖|maven|
|org.springframework.boot:spring-boot-loader-tools|@project.version@|直接依赖|maven|
|org.springframework:spring-tx|3.2.3.RELEASE|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-reflect|@kotlin.version@|直接依赖|maven|
|org.springframework:spring-beans|3.2.3.RELEASE|间接依赖|maven|
|org.springframework.boot.maven.it:build-image-multi-module-library|0.0.1.BUILD-SNAPSHOT|直接依赖|maven|
|org.bouncycastle:bcpg-jdk18on|1.71|直接依赖|maven|
|org.springframework:spring-aop|5.2.3.RELEASE|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|org.springframework.boot.maven.it:jar-classifier|0.0.1|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.2|直接依赖|maven|
|org.springframework.boot.maven.it:jar-release|0.0.1.RELEASE|直接依赖|maven|
|ch.qos.logback:logback-classic|1.2.3|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.2.4.RELEASE|直接依赖|maven|
|org.springframework.boot:spring-boot-loader||间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.2.4.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.10.2|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.10.2|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.10.2|直接依赖|maven|
|org.springframework.boot.maven.it:jar-snapshot|0.0.1.BUILD-SNAPSHOT|直接依赖|maven|
|org.springframework.boot:spring-boot|2.2.4.RELEASE|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|@kotlin.version@|直接依赖|maven|
|org.springframework:spring-aop|3.2.3.RELEASE|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.30|间接依赖|maven|
|org.awaitility:awaitility|4.0.2|直接依赖|maven|
|org.bouncycastle:bcprov-jdk18on|1.71|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-compiler|@kotlin.version@|直接依赖|maven|
|org.springframework:spring-context|@spring-framework.version@|直接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.2.4.RELEASE|间接依赖|maven|
|org.springframework:spring-context|3.2.3.RELEASE|直接依赖|maven|
|org.springframework:spring-context|5.2.3.RELEASE|间接依赖|maven|
|org.springframework:spring-jdbc|3.2.3.RELEASE|间接依赖|maven|
|org.springframework:spring-web|3.2.3.RELEASE|间接依赖|maven|
|org.springframework.security:spring-security-core|3.2.0.M2|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.2|直接依赖|maven|
|org.springframework:spring-core|5.2.3.RELEASE|间接依赖|maven|
|org.springframework:spring-expression|5.2.3.RELEASE|间接依赖|maven|
|org.springframework.boot.maven.it:jar|0.0.1.BUILD-SNAPSHOT|直接依赖|maven|
|ch.qos.logback:logback-core|1.2.3|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.10.2|间接依赖|maven|
|org.springframework:spring-web|5.2.3.RELEASE|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)