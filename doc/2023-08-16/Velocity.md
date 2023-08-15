# PaperMC/Velocity安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1691511136010919936.svg)](https://www.murphysec.com/console/report/1691511135968976896/1691511136010919936)

仓库描述：The modern, next-generation Minecraft server proxy.

仓库地址：[https://github.com/PaperMC/Velocity](https://github.com/PaperMC/Velocity)

| star：1407 | watch：49 | fork：421 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-15 22:38:54 | 许可证：- |
| 最近检测时间：2023-08-16 02:14:42 | 组件总数：88 | 漏洞总数：11 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|MPS-2020-17429|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|MPS-2022-12067|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|MPS-2022-5144|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|MPS-2022-56040|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|MPS-2022-56041|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|MPS-2022-56051|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
|MPS-2022-56081|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|MPS-2022-58478|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|MPS-2022-9425|输入验证不恰当|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|MPS-9u07-bna1|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|MPS-mfku-xzh3|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.yaml:snakeyaml|1.26|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|io.netty:netty-handler|4.1.90.Final|4.1.94.final|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|25.1-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:1|
|com.google.guava:guava|31.0.1-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|44|Low|
|LGPL-3.0|2|Medium|
|MIT|23|Low|
|MIT-0|1|Low|
|BSD-3-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.jline:jline-terminal|3.23.0|间接依赖|maven|
|com.typesafe:config|1.4.0|间接依赖|maven|
|com.electronwill.night-config:core|3.6.6|间接依赖|maven|
|org.fusesource.jansi:jansi|2.4.0|间接依赖|maven|
|net.kyori:adventure-platform-api|4.3.0|间接依赖|maven|
|io.netty:netty-common|4.1.90.Final|间接依赖|maven|
|org.asynchttpclient:async-http-client-netty-utils|2.12.3|间接依赖|maven|
|libcrypto.so.1.1||间接依赖||
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.60.Final|间接依赖|maven|
|net.kyori:adventure-nbt|4.14.0|直接依赖|maven|
|org.lanternpowered:lmbda|2.0.0|直接依赖|maven|
|org.checkerframework:checker-qual|3.28.0|直接依赖|maven|
|org.spongepowered:configurate-gson|3.7.3|直接依赖|maven|
|com.velocitypowered:velocity-brigadier|1.0.0-SNAPSHOT|直接依赖|maven|
|com.moandjiezana.toml:toml4j|0.7.2|直接依赖|maven|
|com.electronwill.night-config:toml|3.6.6|直接依赖|maven|
|net.kyori:adventure-text-minimessage|4.14.0|直接依赖|maven|
|::velocity-api||直接依赖|maven|
|/usr/lib/libSystem.B.dylib||间接依赖||
|io.netty:netty-transport|4.1.90.Final|间接依赖|maven|
|io.netty:netty-resolver|4.1.90.Final|间接依赖|maven|
|::velocity-native||直接依赖|maven|
|org.bstats:bstats-base|3.0.1|直接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|net.kyori:adventure-text-serializer-plain|4.14.0|直接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|libcrypto.so.3||间接依赖||
|io.netty:netty-handler|4.1.90.Final|直接依赖|maven|
|net.kyori:adventure-platform-facet|4.3.0|直接依赖|maven|
|com.typesafe.netty:netty-reactive-streams|2.0.4|间接依赖|maven|
|com.google.code.gson:gson|2.10.1|直接依赖|maven|
|net.kyori:adventure-api|4.14.0|直接依赖|maven|
|org.spongepowered:configurate-hocon|3.7.3|直接依赖|maven|
|org.ow2.asm:asm|9.5|直接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|io.netty:netty-codec-http|4.1.90.Final|直接依赖|maven|
|net.kyori:adventure-text-serializer-gson|4.14.0|直接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.90.Final|间接依赖|maven|
|io.netty:netty-codec-haproxy|4.1.90.Final|直接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.14|间接依赖|maven|
|org.checkerframework:checker-qual|3.32.0|直接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.20.0|直接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j-impl|2.20.0|直接依赖|maven|
|com.lmax:disruptor|3.4.4|直接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|libc.so.6||间接依赖||
|org.jline:jline-native|3.23.0|间接依赖|maven|
|:No dependencies||直接依赖|maven|
|com.sun.activation:jakarta.activation|1.2.2|间接依赖|maven|
|com.google.guava:guava|25.1-jre|直接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.1|间接依赖|maven|
|net.kyori:adventure-text-serializer-legacy|4.14.0|直接依赖|maven|
|io.netty:netty-buffer|4.1.90.Final|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.60.Final|间接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.60.Final|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|3.1.5|直接依赖|maven|
|jakarta.inject:jakarta.inject-api|2.0.1|间接依赖|maven|
|net.kyori:adventure-bom|4.14.0|直接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.20.0|直接依赖|maven|
|io.netty:netty-codec|4.1.90.Final|直接依赖|maven|
|org.asynchttpclient:async-http-client|2.12.3|直接依赖|maven|
|com.google.errorprone:error||直接依赖|maven|
|com.spotify:completable-futures|0.3.5|直接依赖|maven|
|com.google.guava:guava|31.0.1-jre|直接依赖|maven|
|net.kyori:adventure-key|4.14.0|间接依赖|maven|
|net.kyori:examination-api|1.3.0|间接依赖|maven|
|org.jline:jline-reader|3.20.0|间接依赖|maven|
|it.unimi.dsi:fastutil|8.5.12|直接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.90.Final|间接依赖|maven|
|net.minecrell:terminalconsoleappender|1.3.0|直接依赖|maven|
|net.kyori:examination-string|1.3.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-jul|2.20.0|直接依赖|maven|
|net.sf.jopt-simple:jopt-simple|5.0.4|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.30|直接依赖|maven|
|org.yaml:snakeyaml|1.26|间接依赖|maven|
|space.vectrix.flare:flare|2.0.1|直接依赖|maven|
|org.spongepowered:configurate-core|3.7.3|间接依赖|maven|
|org.spongepowered:configurate-yaml|3.7.3|直接依赖|maven|
|org.apache.logging.log4j:log4j-iostreams|2.20.0|直接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.90.Final|直接依赖|maven|
|com.google.inject:guice|6.0.0|直接依赖|maven|
|org.jline:jline-terminal-jansi|3.23.0|直接依赖|maven|
|net.kyori:adventure-text-serializer-json|4.14.0|间接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|space.vectrix.flare:flare-fastutil|2.0.1|直接依赖|maven|
|libcrypto.so.10||间接依赖||


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)