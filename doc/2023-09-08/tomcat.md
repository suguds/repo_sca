# apache/tomcat安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699846456398888960.svg)](https://www.murphysec.com/console/report/1696221660754374656/1699846456398888960)

仓库描述：Apache Tomcat

仓库地址：[https://github.com/apache/tomcat](https://github.com/apache/tomcat)

| star：6901 | watch：484 | fork：4695 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-07 23:39:52 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-08 02:09:45 | 组件总数：52 | 漏洞总数：6 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|XStream 缓冲区错误漏洞|输入验证不恰当|[MPS-2022-57061](https://www.oscs1024.com/hd/MPS-2022-57061)|CVE-2022-40156|低危|
|xstream project跨界内存写漏洞|跨界内存写|[MPS-2022-57062](https://www.oscs1024.com/hd/MPS-2022-57062)|CVE-2022-40155|高危|
|xstream project跨界内存写漏洞|跨界内存写|[MPS-2022-57063](https://www.oscs1024.com/hd/MPS-2022-57063)|CVE-2022-40154|高危|
|XStream 缓冲区错误漏洞|越界写入|[MPS-2022-57065](https://www.oscs1024.com/hd/MPS-2022-57065)|CVE-2022-40152|高危|
| Apache CXF <3.5.5 存在远程目录列出漏洞|未授权敏感信息泄露|[MPS-2022-66587](https://www.oscs1024.com/hd/MPS-2022-66587)|CVE-2022-46363|高危|
|Apache CXF <3.5.5 SSRF 漏洞|SSRF|[MPS-2022-66588](https://www.oscs1024.com/hd/MPS-2022-66588)|CVE-2022-46364|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.fasterxml.woodstox:woodstox-core|6.2.8|6.4.0|间接依赖|建议修复|C:0|H:3|M:0|L:1|
|org.apache.cxf:cxf-core|3.5.3|3.5.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.cxf:cxf-rt-transports-http|3.5.3|3.5.5|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|14|Low|
|Apache-2.0|32|Low|
|EPL-2.0|6|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.sun.activation:jakarta.activation|1.2.2|间接依赖|maven|
|org.apache.geronimo.specs:geronimo-interceptor_1.2_spec|1.2|直接依赖|maven|
|com.sun.xml.messaging.saaj:saaj-impl|1.5.3|间接依赖|maven|
|org.apache.ws.xmlschema:xmlschema-core|2.3.0|间接依赖|maven|
|jakarta.xml.ws:jakarta.xml.ws-api|2.3.3|间接依赖|maven|
|jakarta.xml.soap:jakarta.xml.soap-api|1.4.2|间接依赖|maven|
|org.apache.xbean:xbean-asm9-shaded|4.21|间接依赖|maven|
|jakarta.el:jakarta.el-api|3.0.3|间接依赖|maven|
|org.apache.tomcat:tomcat-websocket|11.0.0-SNAPSHOT|直接依赖|maven|
|org.apache.johnzon:johnzon-mapper|1.2.18|间接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|6.2.8|间接依赖|maven|
|jakarta.ejb:jakarta.ejb-api|3.2.6|间接依赖|maven|
|org.apache.tomcat:tomcat-jasper|11.0.0-SNAPSHOT|直接依赖|maven|
|org.apache.tomcat:tomcat-storeconfig|11.0.0-SNAPSHOT|直接依赖|maven|
|org.apache.openwebbeans:openwebbeans-web|2.0.27|直接依赖|maven|
|jakarta.jws:jakarta.jws-api|2.1.0|间接依赖|maven|
|jakarta.ws.rs:jakarta.ws.rs-api|2.1.6|间接依赖|maven|
|org.apache.openwebbeans:openwebbeans-el22|2.0.27|间接依赖|maven|
|org.apache.xbean:xbean-finder-shaded|4.21|间接依赖|maven|
|org.apache.openwebbeans:openwebbeans-spi|2.0.27|直接依赖|maven|
|org.apache.cxf:cxf-integration-cdi|3.5.3|直接依赖|maven|
|org.apache.cxf:cxf-rt-rs-extension-providers|3.5.3|直接依赖|maven|
|org.apache.cxf:cxf-rt-rs-client|3.5.3|直接依赖|maven|
|org.apache.cxf:cxf-rt-security|3.5.3|间接依赖|maven|
|org.jvnet.staxex:stax-ex|1.8.3|间接依赖|maven|
|javax.json.bind:javax.json.bind-api|1.0|直接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.3|间接依赖|maven|
|org.apache.tomcat:tomcat-catalina|11.0.0-SNAPSHOT|直接依赖|maven|
|org.apache.tomcat:tomcat-dbcp|11.0.0-SNAPSHOT|直接依赖|maven|
|org.apache.tomcat:tomcat-catalina-ha|11.0.0-SNAPSHOT|直接依赖|maven|
|org.apache.cxf:cxf-rt-rs-json-basic|3.5.3|直接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|2.3.5|间接依赖|maven|
|jakarta.transaction:jakarta.transaction-api|1.3.2|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.2|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|org.apache.tomcat:tomcat-juli|11.0.0-SNAPSHOT|直接依赖|maven|
|jakarta.inject:jakarta.inject-api|1.0.3|间接依赖|maven|
|org.apache.cxf:cxf-rt-frontend-jaxrs|3.5.3|直接依赖|maven|
|org.apache.cxf:cxf-rt-transports-http|3.5.3|间接依赖|maven|
|org.apache.johnzon:johnzon-core|1.2.18|间接依赖|maven|
|org.codehaus.woodstox:stax2-api|4.2.1|间接依赖|maven|
|org.apache.geronimo.specs:geronimo-atinject_1.0_spec|1.2|直接依赖|maven|
|com.sun.istack:istack-commons-runtime|3.0.12|间接依赖|maven|
|org.apache.geronimo.specs:geronimo-jcdi_2.0_spec|1.3|直接依赖|maven|
|org.apache.geronimo.specs:geronimo-jta_1.1_spec|1.1.1|间接依赖|maven|
|org.glassfish.jaxb:txw2|2.3.5|间接依赖|maven|
|org.apache.openwebbeans:openwebbeans-impl|2.0.27|直接依赖|maven|
|javax.json:javax.json-api|1.1.4|直接依赖|maven|
|org.apache.johnzon:johnzon-jsonb|1.2.18|直接依赖|maven|
|org.apache.cxf:cxf-core|3.5.3|间接依赖|maven|
|jakarta.enterprise:jakarta.enterprise.cdi-api|2.0.2|间接依赖|maven|
|jakarta.interceptor:jakarta.interceptor-api|1.2.5|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)