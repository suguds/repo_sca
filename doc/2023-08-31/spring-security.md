# spring-projects/spring-security安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696946429367840768.svg)](https://www.murphysec.com/console/report/1692961340594737152/1696946429367840768)

仓库描述：Spring Security

仓库地址：[https://github.com/spring-projects/spring-security](https://github.com/spring-projects/spring-security)

| star：7917 | watch：436 | fork：5580 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-31 01:16:37 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-31 02:05:18 | 组件总数：16 | 漏洞总数：9 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|HtmlUnit 缓冲区错误漏洞|越界写入|[MPS-7106-nyuw](https://www.oscs1024.com/hd/MPS-7106-nyuw)|CVE-2023-2798|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.yaml:snakeyaml|1.30|2.0|直接依赖|建议修复|C:0|H:2|M:4|L:1|
|net.sourceforge.htmlunit:htmlunit|2.37.0|2.70.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.google.code.gson:gson|2.8.6|2.8.9|直接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|10|Low|
|MIT|2|Low|
|LGPL-3.0|1|Medium|
|自定义许可证|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|io.spring.javaformat:spring-javaformat-gradle-plugin|0.0.15|直接依赖|maven|
|org.yaml:snakeyaml|1.30|直接依赖|maven|
|io.spring.nohttp:nohttp-gradle|0.0.11|直接依赖|maven|
|com.github.spullara.mustache.java:compiler|0.9.4|直接依赖|maven|
|com.apollographql.apollo:apollo-runtime|2.4.5|直接依赖|maven|
|io.projectreactor:reactor-core|3.6.0-M2|直接依赖|maven|
|io.github.gradle-nexus:publish-plugin|1.1.0|直接依赖|maven|
|org.sonarsource.scanner.gradle:sonarqube-gradle-plugin|2.7.1|直接依赖|maven|
|org.hidetake:gradle-ssh-plugin|2.10.1|直接依赖|maven|
|com.thaiopensource:trang|20091111|直接依赖|maven|
|net.sourceforge.htmlunit:htmlunit|2.37.0|直接依赖|maven|
|org.jfrog.buildinfo:build-info-extractor-gradle|4.29.0|直接依赖|maven|
|org.gretty:gretty|4.0.3|直接依赖|maven|
|com.google.code.gson:gson|2.8.6|直接依赖|maven|
|com.github.ben-manes:gradle-versions-plugin|0.38.0|直接依赖|maven|
|net.sourceforge.saxon:saxon|9.1.0.8|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)