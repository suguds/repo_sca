# google/gson安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1702021185419395072.svg)](https://www.murphysec.com/console/report/1698396370159403008/1702021185419395072)

仓库描述：A Java serialization/deserialization library to convert Java Objects into JSON and back

仓库地址：[https://github.com/google/gson](https://github.com/google/gson)

| star：22407 | watch：748 | fork：4287 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-13 06:08:33 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-14 02:07:49 | 组件总数：41 | 漏洞总数：3 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.squareup.okio:okio|1.6.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.15.2||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|30.1.1-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|27|Low|
|BSD-3-Clause|6|Low|
|自定义许可证|2|Low|
|CDDL-1.1|2|Low|
|CDDL-1.0|1|Low|
|MIT|3|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.google.j2objc:j2objc-annotations|2.8|间接依赖|maven|
|org.ow2.asm:asm-util|7.2|间接依赖|maven|
|com.google.guava:guava|30.1.1-jre|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|com.sun.jersey:jersey-core|1.19.4|间接依赖|maven|
|com.google.code.java-allocation-instrumenter:java-allocation-instrumenter|3.3.0|间接依赖|maven|
|com.sun.jersey:jersey-client|1.19.4|间接依赖|maven|
|org.ow2.asm:asm|7.2|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.15.2|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.15.2|直接依赖|maven|
|com.google.caliper:caliper|1.0-beta-3|直接依赖|maven|
|javax.annotation:jsr250-api|1.0|直接依赖|maven|
|com.google.caliper:caliper-core|1.0-beta-3|间接依赖|maven|
|com.google.dagger:dagger|2.22.1|间接依赖|maven|
|com.google.caliper:caliper-api|1.0-beta-3|间接依赖|maven|
|com.google.protobuf:protobuf-java|4.0.0-rc-2|直接依赖|maven|
|com.google.caliper:caliper-worker|1.0-beta-3|间接依赖|maven|
|org.ow2.asm:asm-tree|7.2|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|org.checkerframework:checker-qual|3.33.0|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|javax.ws.rs:jsr311-api|1.1.1|间接依赖|maven|
|org.checkerframework:checker-compat-qual|2.5.3|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.21.1|直接依赖|maven|
|com.google.caliper:caliper-util|1.0-beta-3|间接依赖|maven|
|org.ow2.asm:asm-analysis|7.2|间接依赖|maven|
|joda-time:joda-time|2.10.10|间接依赖|maven|
|com.google.caliper:caliper-worker-jvm|1.0-beta-3|间接依赖|maven|
|com.squareup.okhttp:okhttp|2.7.5|间接依赖|maven|
|com.squareup.okio:okio|1.6.0|间接依赖|maven|
|com.google.dagger:dagger-producers|2.22.1|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|com.google.auto.value:auto-value-annotations|1.8.1|间接依赖|maven|
|com.google.caliper:caliper-runner|1.0-beta-3|间接依赖|maven|
|com.google.code.gson:gson|2.10.2-SNAPSHOT|直接依赖|maven|
|org.ow2.asm:asm-commons|7.2|间接依赖|maven|
|com.google.guava:guava|32.1.2-jre|直接依赖|maven|
|org.checkerframework:checker-qual|3.8.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.15.2|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)