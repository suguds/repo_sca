# Frooodle/Stirling-PDF安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698033852445671424.svg)](https://www.murphysec.com/console/report/1691511002612256768/1698033852445671424)

仓库描述：locally hosted web application that allows you to perform various operations on PDF files

仓库地址：[https://github.com/Frooodle/Stirling-PDF](https://github.com/Frooodle/Stirling-PDF)

| star：1720 | watch：8 | fork：109 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-02 19:13:16 | 许可证：GPL-3.0 |
| 最近检测时间：2023-09-03 02:04:35 | 组件总数：13 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.bouncycastle:bcprov-jdk15on|1.70||直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-2-Clause|1|Low|
|Apache-2.0|9|Low|
|AGPL-3.0|1|High|
|自定义许可证|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.commonmark:commonmark|0.21.0|直接依赖|maven|
|commons-io:commons-io|2.13.0|直接依赖|maven|
|org.thymeleaf.extras:thymeleaf-extras-springsecurity5|3.1.2.RELEASE|直接依赖|maven|
|org.yaml:snakeyaml|2.1|直接依赖|maven|
|com.itextpdf:itext7-core|7.2.5|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-security|3.1.2|直接依赖|maven|
|com.github.vladimir-bukhtoyarov:bucket4j-core|7.6.0|直接依赖|maven|
|org.springdoc:springdoc-openapi-starter-webmvc-ui|2.1.0|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|3.1.2|直接依赖|maven|
|org.apache.pdfbox:pdfbox|2.0.29|直接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.70|直接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.70|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-thymeleaf|3.1.2|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)