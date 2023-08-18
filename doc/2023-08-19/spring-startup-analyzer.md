# linyimin0812/spring-startup-analyzer安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692598034512105472.svg)](https://www.murphysec.com/console/report/1692598034310778880/1692598034512105472)

仓库描述：Spring Startup Analyzer generates an interactive Spring application startup report that lets you understand what contributes to the application startup time and helps to optimize it.🚀

仓库地址：[https://github.com/linyimin0812/spring-startup-analyzer](https://github.com/linyimin0812/spring-startup-analyzer)

| star：830 | watch：11 | fork：53 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-16 02:43:23 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-19 02:04:52 | 组件总数：40 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.squareup.okio:okio-jvm|3.0.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|20|Low|
|MIT|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.alibaba.fastjson2:fastjson2|2.0.33|间接依赖|maven|
|org.springframework.boot:spring-boot-configuration-processor|2.1.7.RELEASE|直接依赖|maven|
|org.checkerframework:checker-qual|3.33.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.5.31|间接依赖|maven|
|org.kohsuke.metainf-services:metainf-services|1.9|直接依赖|maven|
|com.alibaba.fastjson2:fastjson2-extension|2.0.33|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.5.31|间接依赖|maven|
|com.squareup.okhttp3:okhttp|4.10.0|直接依赖|maven|
|com.google.guava:guava|32.1.1-jre|间接依赖|maven|
|com.alibaba:repackage-asm|0.0.13|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|librt.so.1||间接依赖||
|io.github.linyimin0812:spring-profiler-extension|2.0.10|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.5.31|间接依赖|maven|
|com.squareup.okio:okio-jvm|3.0.0|间接依赖|maven|
|libc.so.6||间接依赖||
|io.github.linyimin0812:spring-profiler-common|2.0.10|直接依赖|maven|
|com.alibaba:fastjson|2.0.33|间接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|io.github.linyimin0812:spring-async-bean-core|2.0.10|直接依赖|maven|
|org.apache.commons:commons-lang3|3.7|直接依赖|maven|
|io.github.linyimin0812:spring-profiler-core|2.0.10|直接依赖|maven|
|libc.musl-x86_64.so.1||间接依赖||
|libdl.so.2||间接依赖||
|libc.musl-aarch64.so.1||间接依赖||
|libpthread.so.0||间接依赖||
|libgcc_s.so.1||间接依赖||
|com.squareup.okio:okio|3.4.0|直接依赖|maven|
|com.google.j2objc:j2objc-annotations|2.8|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.6.20|间接依赖|maven|
|org.picocontainer:picocontainer|2.15|直接依赖|maven|
|com.alibaba:bytekit-instrument-api|0.0.8|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.18.0|间接依赖|maven|
|io.github.linyimin0812:spring-profiler-agent|2.0.10|直接依赖|maven|
|com.alibaba:bytekit-core|0.0.8|直接依赖|maven|
|libm.so.6||间接依赖||
|libstdc++.so.6||间接依赖||


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)