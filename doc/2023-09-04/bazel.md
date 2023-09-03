# bazelbuild/bazel安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698397291626151936.svg)](https://www.murphysec.com/console/report/1698397291508711424/1698397291626151936)

仓库描述：a fast, scalable, multi-language and extensible build system

仓库地址：[https://github.com/bazelbuild/bazel](https://github.com/bazelbuild/bazel)

| star：21304 | watch：609 | fork：3852 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-03 22:10:19 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-04 02:11:09 | 组件总数：21 | 漏洞总数：4 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|protobuf-java 存在输入验证不当漏洞|拒绝服务|[MPS-2022-56472](https://www.oscs1024.com/hd/MPS-2022-56472)|CVE-2022-3171|中危|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|Google protobuf 安全漏洞|拒绝服务|[MPS-2022-59814](https://www.oscs1024.com/hd/MPS-2022-59814)|CVE-2022-3510|高危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.google.protobuf:protobuf-java|3.19.2|3.21.7|直接依赖|可选修复|C:0|H:1|M:2|L:0|
|com.google.guava:guava|31.1-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Zlib|1|Low|
|EPL-2.0|3|Low|
|Apache-2.0|7|Low|
|GPL-2.0|2|Medium|
|BSD-3-Clause|5|Low|
|MIT|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|zlib||间接依赖||
|org.jacoco:org.jacoco.core|0.8.8|直接依赖|maven|
|bazel-runfiles|0.24.0|间接依赖|pip|
|org.jacoco:org.jacoco.agent|0.8.8|直接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|net.sf.proguard:proguard-retrace|6.2.2|直接依赖|maven|
|com.google.guava:guava|31.1-jre|直接依赖|maven|
|org.ow2.asm:asm-commons|9.2|直接依赖|maven|
|org.jspecify:jspecify|0.2.0|直接依赖|maven|
|examples||间接依赖|pip|
|com.google.errorprone:error_prone_annotations|2.16|直接依赖|maven|
|org.jacoco:org.jacoco.report|0.8.8|直接依赖|maven|
|org.ow2.asm:asm-analysis|9.2|间接依赖|maven|
|org.checkerframework:checker-qual|3.12.0|间接依赖|maven|
|net.sf.proguard:proguard-base|6.2.2|直接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|org.ow2.asm:asm|9.2|直接依赖|maven|
|com.google.protobuf:protobuf-java|3.19.2|直接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|org.ow2.asm:asm-tree|9.2|直接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)