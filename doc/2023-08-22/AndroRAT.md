# karma9874/AndroRAT安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1693685598446317568.svg)](https://www.murphysec.com/console/report/1693685598412763136/1693685598446317568)

仓库描述：A Simple android remote administration tool using sockets. It uses java on the client side and python on the server side

仓库地址：[https://github.com/karma9874/AndroRAT](https://github.com/karma9874/AndroRAT)

| star：2105 | watch：121 | fork：804 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-01-23 08:41:24 | 许可证：MIT |
| 最近检测时间：2023-08-22 02:10:59 | 组件总数：46 | 漏洞总数：4 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|libpng 数字错误漏洞||[MPS-2018-9315](https://www.oscs1024.com/hd/MPS-2018-9315)|CVE-2018-13785|中危|
|libpng 安全漏洞|输入验证不恰当|[MPS-2018-9648](https://www.oscs1024.com/hd/MPS-2018-9648)|CVE-2018-14048|中危|
|libpng 缓冲区错误漏洞|越界写入|[MPS-2019-7748](https://www.oscs1024.com/hd/MPS-2019-7748)|CVE-2018-14550|高危|
|Expat 资源管理错误漏洞|数值计算不正确|[MPS-2022-0004](https://www.oscs1024.com/hd/MPS-2022-0004)|CVE-2021-45960|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|libpng|1.6.37||间接依赖|建议修复|C:0|H:1|M:2|L:0|
|libexpat|2.2.9||间接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|9|Low|
|自定义许可证|2|Low|
|MIT|4|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|commons-cli:commons-cli|1.4|直接依赖|maven|
|/usr/lib/libSystem.B.dylib||间接依赖||
|api-ms-win-crt-stdio-l1-1-0.dll||间接依赖||
|api-ms-win-crt-filesystem-l1-1-0.dll||间接依赖||
|io.homunculus:hcf-codegen||间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.2.0|直接依赖|maven|
|libpthread.so.0||间接依赖||
|libpng|1.6.37|间接依赖||
|/usr/lib/libz.1.dylib||间接依赖||
|librt.so.1||间接依赖||
|api-ms-win-crt-multibyte-l1-1-0.dll||间接依赖||
|api-ms-win-crt-utility-l1-1-0.dll||间接依赖||
|api-ms-win-crt-convert-l1-1-0.dll||间接依赖||
|ld-linux-x86-64.so.2||间接依赖||
|api-ms-win-crt-time-l1-1-0.dll||间接依赖||
|api-ms-win-crt-environment-l1-1-0.dll||间接依赖||
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|直接依赖|maven|
|@rpath/libc++.dylib||间接依赖||
|antlr:antlr|2.7.7|直接依赖|maven|
|org.checkerframework:checker-compat-qual|2.5.2|直接依赖|maven|
|at.favre.lib:bytes|1.3.0|直接依赖|maven|
|api-ms-win-crt-math-l1-1-0.dll||间接依赖||
|libwinpthread-1.dll||间接依赖||
|com.segment.analytics.android.integrations:firebase||间接依赖|maven|
|com.abubusoft:kripton-arch-integration||间接依赖|maven|
|api-ms-win-crt-runtime-l1-1-0.dll||间接依赖||
|libexpat|2.2.9|间接依赖||
|libgcc_s.so.1||间接依赖||
|at.favre.tools:uber-apk-signer-apksigner_29_0_2.jar|1.2.1|直接依赖|maven|
|KERNEL32.dll||间接依赖||
|libm.so.6||间接依赖||
|api-ms-win-crt-private-l1-1-0.dll||间接依赖||
|com.google.guava:failureaccess|1.0.1|直接依赖|maven|
|SHELL32.dll||间接依赖||
|msvcrt.dll||间接依赖||
|libdl.so.2||间接依赖||
|org.antlr:stringtemplate|3.2.1|直接依赖|maven|
|com.vorlonsoft:androidrate||间接依赖|maven|
|libc.so.6||间接依赖||
|libc++.so||间接依赖||
|api-ms-win-crt-heap-l1-1-0.dll||间接依赖||
|org.codehaus.mojo:animal-sniffer-annotations|1.17|直接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|直接依赖|maven|
|api-ms-win-crt-locale-l1-1-0.dll||间接依赖||
|com.google.j2objc:j2objc-annotations|1.1|直接依赖|maven|
|api-ms-win-crt-string-l1-1-0.dll||间接依赖||


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)