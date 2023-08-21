# runelite/runelite安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1693684941748789248.svg)](https://www.murphysec.com/console/report/1693684941715234816/1693684941748789248)

仓库描述：Open source Old School RuneScape client

仓库地址：[https://github.com/runelite/runelite](https://github.com/runelite/runelite)

| star：4254 | watch：98 | fork：4939 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-21 23:20:14 | 许可证：BSD-2-Clause |
| 最近检测时间：2023-08-22 02:03:55 | 组件总数：50 | 漏洞总数：13 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|plexus-utils <3.0.16 命令注入漏洞|OS命令注入|[MPS-2018-0091](https://www.oscs1024.com/hd/MPS-2018-0091)|CVE-2017-1000487|严重|
|Apache Commons Compress 存在拒绝服务漏洞|不可达退出条件的循环（无限循环）|[MPS-2018-11233](https://www.oscs1024.com/hd/MPS-2018-11233)|CVE-2018-11771|中危|
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Apache Commons Compress 安存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10550](https://www.oscs1024.com/hd/MPS-2021-10550)|CVE-2021-35517|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10551](https://www.oscs1024.com/hd/MPS-2021-10551)|CVE-2021-35516|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10564](https://www.oscs1024.com/hd/MPS-2021-10564)|CVE-2021-36090|高危|
|Apache Commons Compress 无限循环漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-10565](https://www.oscs1024.com/hd/MPS-2021-10565)|CVE-2021-35515|高危|
|plexus-utils <3.0.24 路径遍历漏洞|路径遍历|[MPS-2022-11760](https://www.oscs1024.com/hd/MPS-2022-11760)||中危|
|plexus-utils <3.0.24 XXE 漏洞|XPath盲注|[MPS-2022-11786](https://www.oscs1024.com/hd/MPS-2022-11786)||低危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.squareup.okio:okio|1.17.2|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.commons:commons-compress|1.10|1.21|直接依赖|建议修复|C:0|H:4|M:1|L:0|
|org.codehaus.plexus:plexus-utils|2.0.6|3.0.24|间接依赖|建议修复|C:1|H:0|M:1|L:1|
|com.google.guava:guava|23.2-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:2|L:1|
|com.google.code.gson:gson|2.8.5|2.8.9|直接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|4|Low|
|Apache-2.0|25|Low|
|BSD-3-Clause|6|Low|
|LGPL-2.1-or-later|2|Low|
|EPL-1.0|3|Low|
|自定义许可证|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.codehaus.mojo:animal-sniffer-annotations|1.14|间接依赖|maven|
|net.sf.jopt-simple:jopt-simple|5.0.1|直接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|com.fifesoft:rsyntaxtextarea|3.1.2|直接依赖|maven|
|com.google.protobuf:protobuf-javalite|3.21.12|直接依赖|maven|
|com.google.guava:guava|23.2-jre|直接依赖|maven|
|net.runelite:runelite-api|1.10.11-SNAPSHOT|直接依赖|maven|
|net.runelite:discord|1.4|直接依赖|maven|
|net.java.dev.jna:jna-platform|5.9.0|直接依赖|maven|
|com.squareup.okhttp3:okhttp|3.14.9|间接依赖|maven|
|net.runelite.pushingpixels:substance|8.0.02|直接依赖|maven|
|ch.qos.logback:logback-core|1.2.9|间接依赖|maven|
|org.apache.maven.plugin-tools:maven-plugin-annotations|3.4|直接依赖|maven|
|org.apache.maven:maven-model|3.0.5|间接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|org.lwjgl:lwjgl-opengl|3.3.2|直接依赖|maven|
|org.lwjgl:lwjgl-opencl|3.3.2|直接依赖|maven|
|ch.qos.logback:logback-classic|1.2.9|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.25|直接依赖|maven|
|net.runelite:jshell|1.10.11-SNAPSHOT|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.0.18|间接依赖|maven|
|org.sonatype.sisu:sisu-inject-plexus|2.3.0|间接依赖|maven|
|org.sonatype.sisu:sisu-guice|3.1.0|间接依赖|maven|
|org.lwjgl:lwjgl|3.3.2|直接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|直接依赖|maven|
|org.sonatype.sisu:sisu-guava|0.9.9|间接依赖|maven|
|net.runelite:cache|1.10.11-SNAPSHOT|直接依赖|maven|
|com.google.inject:guice|4.1.0|直接依赖|maven|
|com.squareup.okio:okio|1.17.2|间接依赖|maven|
|org.sonatype.sisu:sisu-inject-bean|2.3.0|间接依赖|maven|
|net.runelite.archive-patcher:archive-patcher-applier|1.2|直接依赖|maven|
|org.apache.commons:commons-compress|1.10|直接依赖|maven|
|com.google.code.gson:gson|2.8.5|直接依赖|maven|
|net.runelite:rlawt|1.4|直接依赖|maven|
|com.fifesoft:autocomplete|3.1.1|直接依赖|maven|
|org.codehaus.plexus:plexus-classworlds|2.4|间接依赖|maven|
|net.runelite.pushingpixels:trident|1.5.00|直接依赖|maven|
|org.antlr:antlr4-runtime|4.6|直接依赖|maven|
|org.codehaus.plexus:plexus-utils|2.0.6|间接依赖|maven|
|commons-cli:commons-cli|1.3.1|直接依赖|maven|
|net.runelite:client-patch|1.10.11-SNAPSHOT|直接依赖|maven|
|org.slf4j:slf4j-simple|1.7.25|直接依赖|maven|
|org.apache.commons:commons-text|1.2|直接依赖|maven|
|org.apache.maven:maven-plugin-api|3.0.5|直接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.1|间接依赖|maven|
|net.java.dev.jna:jna|5.9.0|直接依赖|maven|
|org.codehaus.plexus:plexus-component-annotations|1.5.5|间接依赖|maven|
|net.runelite.arn:http-api|1.2.12|直接依赖|maven|
|org.apache.commons:commons-lang3|3.7|间接依赖|maven|
|org.apache.maven:maven-artifact|3.0.5|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)