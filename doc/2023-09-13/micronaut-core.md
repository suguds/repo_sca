# micronaut-projects/micronaut-core安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1701735077453103104.svg)](https://www.murphysec.com/console/report/1701658256794763264/1701735077453103104)

仓库描述：Micronaut Application Framework

仓库地址：[https://github.com/micronaut-projects/micronaut-core](https://github.com/micronaut-projects/micronaut-core)

| star：5805 | watch：179 | fork：996 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-13 01:01:45 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-13 07:12:02 | 组件总数：7 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.squareup.okio:okio|3.3.0|3.4.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|3|Low|
|MIT|1|Low|
|自定义许可证|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|io.micronaut.build.internal:micronaut-gradle-plugins|6.5.6|直接依赖|maven|
|org.aim42:htmlSanityCheck|1.1.6|直接依赖|maven|
|org.tomlj:tomlj|1.1.0|直接依赖|maven|
|io.github.classgraph:classgraph|4.8.149|直接依赖|maven|
|org.graalvm.buildtools.native:org.graalvm.buildtools.native.gradle.plugin|0.9.26|直接依赖|maven|
|com.squareup.okio:okio|3.3.0|直接依赖|maven|
|me.champeau.gradle:japicmp-gradle-plugin|0.4.2|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)