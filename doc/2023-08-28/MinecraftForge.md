# MinecraftForge/MinecraftForge安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695935999632039936.svg)](https://www.murphysec.com/console/report/1695860252087246848/1695935999632039936)

仓库描述：Modifications to the Minecraft base files to assist in compatibility between mods. New Discord: https://discord.minecraftforge.net/

仓库地址：[https://github.com/MinecraftForge/MinecraftForge](https://github.com/MinecraftForge/MinecraftForge)

| star：6323 | watch：351 | fork：2586 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-26 16:59:48 | 许可证：NOASSERTION |
| 最近检测时间：2023-08-28 07:35:30 | 组件总数：113 | 漏洞总数：8 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache Log4j2 SmtpAppender证书验证不当漏洞|证书验证不恰当|[MPS-2020-6684](https://www.oscs1024.com/hd/MPS-2020-6684)|CVE-2020-9488|低危|
|Apache Log4j2 远程代码执行漏洞|反序列化|[MPS-2021-38241](https://www.oscs1024.com/hd/MPS-2021-38241)|CVE-2021-44228|严重|
|Apache Log4j2 JDBC Appender远程代码执行漏洞|代码注入|[MPS-2021-38327](https://www.oscs1024.com/hd/MPS-2021-38327)|CVE-2021-44832|中危|
|Apache Log4j2 基于上下文查找的远程代码执行漏洞|反序列化|[MPS-2021-38665](https://www.oscs1024.com/hd/MPS-2021-38665)|CVE-2021-45046|严重|
|Apache Log4j2 自引用拒绝服务漏洞|未经控制的递归|[MPS-2021-38752](https://www.oscs1024.com/hd/MPS-2021-38752)|CVE-2021-45105|中危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.apache.logging.log4j:log4j-core|2.11.|2.17.1|间接依赖|强烈建议修复|C:2|H:0|M:2|L:1|
|io.netty:netty-handler|4.1.82.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|31.1-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|20|Low|
|Apache-2.0|39|Low|
|BSD-3-Clause|9|Low|
|LGPL-3.0|2|Medium|
|MIT|7|Low|
|LGPL-2.1-or-later|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|::fmlcore||直接依赖|maven|
|net.minecraftforge:coremods|5.0.1|直接依赖|maven|
|org.antlr:antlr4|4.9.1|间接依赖|maven|
|org.jline:jline-terminal|3.12.1|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.15|间接依赖|maven|
|org.ow2.asm:asm-commons|9.5|直接依赖|maven|
|it.unimi.dsi:fastutil|8.5.9|间接依赖|maven|
|com.github.oshi:oshi-core|6.2.2|间接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j2-impl|2.19.0|间接依赖|maven|
|com.mojang:patchy|2.2.10|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|间接依赖|maven|
|org.apache.maven:maven-artifact|3.8.5|直接依赖|maven|
|io.netty:netty-handler|4.1.82.Final|间接依赖|maven|
|com.electronwill.night-config:toml|3.6.4|直接依赖|maven|
|com.machinezoo.noexception:noexception|1.7.1|间接依赖|maven|
|org.glassfish:javax.json|1.0.4|间接依赖|maven|
|org.ow2.asm:asm-analysis|9.5|直接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.19.0|直接依赖|maven|
|com.mojang:datafixerupper|6.0.8|间接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|org.lwjgl:lwjgl-jemalloc|3.3.1|间接依赖|maven|
|org.openjdk.nashorn:nashorn-core|15.3|直接依赖|maven|
|org.codehaus.plexus:plexus-utils|3.2.1|间接依赖|maven|
|::lowcodelanguage||直接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.11.|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|net.sf.jopt-simple:jopt-simple|5.0.4|直接依赖|maven|
|cpw.mods:modlauncher|10.0.|间接依赖|maven|
|org.slf4j:slf4j-simple|1.7.30|间接依赖|maven|
|::fmlloader||直接依赖|maven|
|cpw.mods:securejarhandler|0.9.61|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|直接依赖|maven|
|com.ibm.icu:icu4j|71.1|间接依赖|maven|
|org.apache.maven:maven-artifact|3.8.1|间接依赖|maven|
|org.jline:jline-reader|3.12.|直接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|org.codehaus.plexus:plexus-utils|3.3.0|间接依赖|maven|
|net.minecraftforge:mergetool|1.1.5|直接依赖|maven|
|org.ow2.asm:asm-util|9.5|直接依赖|maven|
|org.abego.treelayout:org.abego.treelayout.core|1.0.3|间接依赖|maven|
|org.apache.commons:commons-compress|1.21|间接依赖|maven|
|com.mojang:text2speech|1.17.9|间接依赖|maven|
|net.minecraftforge:JarJarSelector|0.3.19|直接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.82.Final|间接依赖|maven|
|com.mojang:logging|1.1.1|直接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|com.google.errorprone:error||间接依赖|maven|
|org.slf4j:slf4j-api|1.8.0-beta4|直接依赖|maven|
|io.netty:netty-transport|4.1.82.Final|间接依赖|maven|
|com.electronwill.night-config:core|3.6.4|直接依赖|maven|
|cpw.mods:modlauncher|9.0.|间接依赖|maven|
|org.antlr:antlr-runtime|3.5.2|间接依赖|maven|
|org.ow2.asm:asm-commons|9.2|间接依赖|maven|
|org.ow2.asm:asm-analysis|9.2|间接依赖|maven|
|org.lwjgl:lwjgl-tinyfd|3.3.1|直接依赖|maven|
|org.joml:joml|1.10.5|间接依赖|maven|
|net.java.dev.jna:jna-platform|5.12.1|间接依赖|maven|
|org.lwjgl:lwjgl|3.3.1|直接依赖|maven|
|org.ow2.asm:asm|9.2|间接依赖|maven|
|io.netty:netty-common|4.1.82.Final|间接依赖|maven|
|org.lwjgl:lwjgl-opengl|3.3.1|直接依赖|maven|
|cpw.mods:modlauncher|9.0.7|间接依赖|maven|
|net.minecraft:client|1.20.1-20230612.114412|直接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.82.Final|间接依赖|maven|
|net.minecraftforge:eventbus|6.0.5|直接依赖|maven|
|io.netty:netty-resolver|4.1.82.Final|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|org.jline:jline-reader|3.12.1|间接依赖|maven|
|com.google.guava:guava|31.1-jre|直接依赖|maven|
|net.minecrell:terminalconsoleappender|1.2.0|直接依赖|maven|
|com.google.code.gson:gson|2.10|直接依赖|maven|
|net.minecraftforge:forgespi|7.0.1|直接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.82.Final|间接依赖|maven|
|cpw.mods:securejarhandler|0.9.|间接依赖|maven|
|org.jline:jline-terminal|3.12.|直接依赖|maven|
|org.ow2.asm:asm|9.5|直接依赖|maven|
|org.jetbrains:annotations|24.0.1|间接依赖|maven|
|::mclanguage||直接依赖|maven|
|ca.weblite:java-objc-bridge|1.1|间接依赖|maven|
|org.antlr:ST4|4.3|间接依赖|maven|
|org.ow2.asm:asm-tree|9.5|直接依赖|maven|
|net.minecraftforge:accesstransformers|8.0.4|直接依赖|maven|
|com.mojang:brigadier|1.1.8|间接依赖|maven|
|com.mojang:authlib|4.0.43|间接依赖|maven|
|org.ow2.asm:asm-tree|9.2|间接依赖|maven|
|net.jodah:typetools|0.6.|间接依赖|maven|
|org.slf4j:slf4j-api|2.0.1|间接依赖|maven|
|io.netty:netty-buffer|4.1.82.Final|间接依赖|maven|
|net.java.dev.jna:jna|5.12.1|间接依赖|maven|
|commons-io:commons-io|2.11.0|直接依赖|maven|
|::fmlearlydisplay||直接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.19.0|直接依赖|maven|
|org.lwjgl:lwjgl-openal|3.3.1|间接依赖|maven|
|:No dependencies||直接依赖|maven|
|com.mojang:blocklist|1.0.10|间接依赖|maven|
|net.minecraftforge:srgutils|0.4.11|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.11.|间接依赖|maven|
|org.checkerframework:checker-qual|3.12.0|间接依赖|maven|
|org.antlr:antlr4-runtime|4.9.1|直接依赖|maven|
|io.netty:netty-codec|4.1.82.Final|间接依赖|maven|
|::javafmllanguage||直接依赖|maven|
|net.jodah:typetools|0.6.3|直接依赖|maven|
|org.lwjgl:lwjgl-stb|3.3.1|直接依赖|maven|
|net.minecraftforge:forgespi|4.0.|间接依赖|maven|
|net.minecraftforge:JarJarMetadata|0.3.19|直接依赖|maven|
|net.minecraftforge:unsafe|0.2.|直接依赖|maven|
|net.minecraft:mappings||直接依赖|maven|
|cpw.mods:bootstraplauncher|1.1.2|直接依赖|maven|
|org.lwjgl:lwjgl-glfw|3.3.1|直接依赖|maven|
|cpw.mods:modlauncher|10.0.9|直接依赖|maven|
|org.spongepowered:mixin|0.8.5|直接依赖|maven|
|cpw.mods:securejarhandler|2.1.10|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)