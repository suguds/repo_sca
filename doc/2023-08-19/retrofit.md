# square/retrofit安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692598823842369536.svg)](https://www.murphysec.com/console/report/1692598823628460032/1692598823842369536)

仓库描述：A type-safe HTTP client for Android and the JVM

仓库地址：[https://github.com/square/retrofit](https://github.com/square/retrofit)

| star：41912 | watch：1587 | fork：7319 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-17 17:15:42 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-19 04:50:53 | 组件总数：48 | 漏洞总数：4 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|SimpleXML 安全漏洞|XXE|[MPS-2017-13106](https://www.oscs1024.com/hd/MPS-2017-13106)|CVE-2017-1000190|严重|
|Junit 信息泄露漏洞|不安全的临时文件|[MPS-2020-15183](https://www.oscs1024.com/hd/MPS-2020-15183)|CVE-2020-15250|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.fasterxml.jackson.core:jackson-databind|2.15.2||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.simpleframework:simple-xml|2.7.1||直接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.squareup.okio:okio|1.17.2|3.4.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.squareup.okio:okio|2.10.0|3.4.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|junit:junit|4.12|4.13.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|28|Low|
|EPL-1.0|1|Low|
|MIT-0|1|Low|
|CDDL-1.1|1|Low|
|BSD-3-Clause|1|Low|
|MIT|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.google.errorprone:error||直接依赖|maven|
|com.sun.activation:jakarta.activation|2.0.1|直接依赖|maven|
|::retrofit-converters:gson||直接依赖|maven|
|org.hamcrest:hamcrest-core|1.3|间接依赖|maven|
|com.squareup.okhttp3:mockwebserver|3.14.9|直接依赖|maven|
|com.fasterxml.jackson:jackson-bom|2.15.2|直接依赖|maven|
|xpp3:xpp3|1.1.3.3|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.8.21|直接依赖|maven|
|com.google.guava:guava-parent|32.1.2-jre|直接依赖|maven|
|org.scala-lang:scala-library|2.13.11|直接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|直接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|::retrofit||直接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|直接依赖|maven|
|junit:junit|4.12|间接依赖|maven|
|io.reactivex.rxjava2:rxjava|2.2.21|直接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|直接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.15.2|直接依赖|maven|
|com.mobidevelop.robovm:robovm-rt|2.3.14|直接依赖|maven|
|com.squareup.moshi:moshi|1.15.0|直接依赖|maven|
|com.squareup.okio:okio|1.17.2|直接依赖|maven|
|::retrofit-converters:moshi||直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.8.21|直接依赖|maven|
|stax:stax|1.2.0|直接依赖|maven|
|com.squareup.okio:okio|2.10.0|直接依赖|maven|
|com.google.guava:guava|32.1.2-jre|直接依赖|maven|
|:No dependencies||直接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.8.21|直接依赖|maven|
|com.squareup.okhttp3:okhttp|3.14.9|直接依赖|maven|
|com.google.protobuf:protobuf-java|3.24.0|直接依赖|maven|
|io.reactivex.rxjava3:rxjava|3.1.6|直接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|3.0.1|直接依赖|maven|
|com.squareup.wire:wire-runtime|2.2.0|直接依赖|maven|
|::retrofit-adapters:rxjava||直接依赖|maven|
|::retrofit-mock||直接依赖|maven|
|org.simpleframework:simple-xml|2.7.1|直接依赖|maven|
|io.reactivex:rxjava|1.3.8|直接依赖|maven|
|org.checkerframework:checker-qual|3.33.0|直接依赖|maven|
|com.google.code.gson:gson|2.10.1|直接依赖|maven|
|com.google.guava:failureaccess|1.0.1|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.15.2|直接依赖|maven|
|org.jsoup:jsoup|1.16.1|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.8.21|间接依赖|maven|
|::retrofit-converters:simplexml||直接依赖|maven|
|stax:stax-api|1.0.1|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.15.2|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)