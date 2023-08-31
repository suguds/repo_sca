# redplanetlabs/twitter-scale-mastodon安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1697309346718183424.svg)](https://www.murphysec.com/console/report/1697309345669607424/1697309346718183424)

仓库描述：Twitter-scale Mastodon implementation in only 10k lines of code

仓库地址：[https://github.com/redplanetlabs/twitter-scale-mastodon](https://github.com/redplanetlabs/twitter-scale-mastodon)

| star：105 | watch：1 | fork：1 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-28 02:07:42 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-01 02:17:27 | 组件总数：77 | 漏洞总数：18 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|Netty <4.1.86.Final 存在 CRLF 注入漏洞||[MPS-2022-58552](https://www.oscs1024.com/hd/MPS-2022-58552)|CVE-2022-41915|中危|
|Apache Commons Text <1.10.0 远程代码执行漏洞|反序列化|[MPS-2022-59712](https://www.oscs1024.com/hd/MPS-2022-59712)|CVE-2022-42889|严重|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Security Logout实现不当|会话固定|[MPS-2022-62834](https://www.oscs1024.com/hd/MPS-2022-62834)|CVE-2023-20862|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Spring Security 路径匹配漏洞|不恰当实现的标准安全检查|[MPS-j3nx-691g](https://www.oscs1024.com/hd/MPS-j3nx-691g)|CVE-2023-34034|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.yaml:snakeyaml|1.30|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|org.springframework.security:spring-security-web|5.7.6|6.1.2|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.apache.commons:commons-text|1.8|1.10.0|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|io.netty:netty-handler|4.1.86.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-web|5.3.24|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework:spring-core|5.3.24|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|5.3.24|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|io.netty:netty-codec-http|4.1.86.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.7.7|3.0.7|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.bouncycastle:bcprov-jdk15on|1.70||直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|69|Low|
|MIT|2|Low|
|EPL-2.0|1|Low|
|自定义许可证|1|Low|
|MIT-0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|io.netty:netty-codec-dns|4.1.86.Final|间接依赖|maven|
|io.netty:netty-resolver|4.1.86.Final|间接依赖|maven|
|software.amazon.awssdk:aws-query-protocol|2.20.18|间接依赖|maven|
|software.amazon.awssdk:auth|2.20.18|间接依赖|maven|
|software.amazon.awssdk:third-party-jackson-core|2.20.18|间接依赖|maven|
|it.unimi.dsi:fastutil|7.0.6|间接依赖|maven|
|org.springframework.security:spring-security-config|5.7.6|间接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.86.Final|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-http|1.0.26|间接依赖|maven|
|org.springframework.boot:spring-boot|2.7.7|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-security|2.7.7|直接依赖|maven|
|software.amazon.awssdk:s3|2.20.18|直接依赖|maven|
|io.netty:netty-common|4.1.86.Final|间接依赖|maven|
|org.springframework.session:spring-session-core|2.7.0|直接依赖|maven|
|io.netty:netty-transport|4.1.86.Final|间接依赖|maven|
|software.amazon.awssdk:sdk-core|2.20.18|间接依赖|maven|
|org.apache.logging.log4j:log4j-jul|2.17.2|间接依赖|maven|
|software.amazon.awssdk:annotations|2.20.18|间接依赖|maven|
|software.amazon.awssdk:arns|2.20.18|间接依赖|maven|
|com.rpl:rama-helpers|0.9.0|直接依赖|maven|
|org.springframework:spring-web|5.3.24|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-reactor-netty|2.7.7|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-log4j2|2.7.7|直接依赖|maven|
|software.amazon.awssdk:netty-nio-client|2.20.18|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.86.Final|间接依赖|maven|
|org.springframework:spring-webflux|5.3.24|间接依赖|maven|
|software.amazon.awssdk:aws-xml-protocol|2.20.18|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.4|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.7|间接依赖|maven|
|software.amazon.awssdk:protocol-core|2.20.18|间接依赖|maven|
|software.amazon.awssdk:aws-core|2.20.18|间接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.86.Final|间接依赖|maven|
|software.amazon.awssdk:http-client-spi|2.20.18|间接依赖|maven|
|org.jsoup:jsoup|1.15.4|直接依赖|maven|
|com.clearspring.analytics:stream|2.9.5|直接依赖|maven|
|software.amazon.awssdk:utils|2.20.18|间接依赖|maven|
|org.springframework:spring-beans|5.3.24|间接依赖|maven|
|software.amazon.eventstream:eventstream|1.0.1|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.86.Final|间接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j-impl|2.17.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.7|直接依赖|maven|
|io.projectreactor.netty:reactor-netty-core|1.0.26|间接依赖|maven|
|org.springframework:spring-jcl|5.3.24|间接依赖|maven|
|org.springframework:spring-context|5.3.24|间接依赖|maven|
|org.springframework.security:spring-security-web|5.7.6|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|间接依赖|maven|
|software.amazon.awssdk:json-utils|2.20.18|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.7.7|间接依赖|maven|
|com.bucket4j:bucket4j_jdk8-core|8.1.0|直接依赖|maven|
|io.netty:netty-handler|4.1.86.Final|间接依赖|maven|
|software.amazon.awssdk:regions|2.20.18|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.86.Final|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.86.Final|间接依赖|maven|
|io.netty:netty-codec-http|4.1.86.Final|间接依赖|maven|
|software.amazon.awssdk:apache-client|2.20.18|间接依赖|maven|
|software.amazon.awssdk:profiles|2.20.18|间接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.17.2|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.86.Final|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.70|直接依赖|maven|
|org.apache.commons:commons-text|1.8|直接依赖|maven|
|io.netty:netty-resolver-dns|4.1.86.Final|间接依赖|maven|
|org.apache.commons:commons-lang3|3.9|间接依赖|maven|
|org.yaml:snakeyaml|1.30|间接依赖|maven|
|http-kit:http-kit|2.7.0|直接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.86.Final|间接依赖|maven|
|software.amazon.awssdk:endpoints-spi|2.20.18|间接依赖|maven|
|org.jcodec:jcodec|0.2.5|直接依赖|maven|
|software.amazon.awssdk:metrics-spi|2.20.18|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-webflux|2.7.7|直接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|io.netty:netty-codec|4.1.86.Final|间接依赖|maven|
|org.springframework:spring-core|5.3.24|间接依赖|maven|
|org.springframework:spring-aop|5.3.24|间接依赖|maven|
|org.springframework:spring-expression|5.3.24|间接依赖|maven|
|io.netty:netty-buffer|4.1.86.Final|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)