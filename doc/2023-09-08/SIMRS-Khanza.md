# mas-elkhanza/SIMRS-Khanza安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699845004565725184.svg)](https://www.murphysec.com/console/report/1699845004523782144/1699845004565725184)

仓库描述：Software untuk rumah sakit, klinik, puskesmas, dokter pribadi yang sudah digunakan di lebih dari 1000 rumah sakit di sluruh indonesia

仓库地址：[https://github.com/mas-elkhanza/SIMRS-Khanza](https://github.com/mas-elkhanza/SIMRS-Khanza)

| star：452 | watch：65 | fork：691 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-07 10:56:29 | 许可证：- |
| 最近检测时间：2023-09-08 02:06:22 | 组件总数：34 | 漏洞总数：13 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|多款Cisco产品Apache Commons Collections库任意代码执行漏洞|反序列化|[MPS-2015-6277](https://www.oscs1024.com/hd/MPS-2015-6277)|CVE-2015-6420|高危|
|多款Red Hat产品代码问题漏洞|反序列化|[MPS-2017-12638](https://www.oscs1024.com/hd/MPS-2017-12638)|CVE-2015-7501|严重|
|Apache Log4j SocketServer反序列化漏洞|反序列化|[MPS-2019-17271](https://www.oscs1024.com/hd/MPS-2019-17271)|CVE-2019-17571|严重|
|Apache HttpClient URI解析错误漏洞|XSS|[MPS-2020-17341](https://www.oscs1024.com/hd/MPS-2020-17341)|CVE-2020-13956|中危|
|Apache Log4j2 SmtpAppender证书验证不当漏洞|证书验证不恰当|[MPS-2020-6684](https://www.oscs1024.com/hd/MPS-2020-6684)|CVE-2020-9488|低危|
|Apache Log4j JMSAppender反序列化漏洞||[MPS-2021-38359](https://www.oscs1024.com/hd/MPS-2021-38359)|CVE-2021-4104|高危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|com.fasterxml.jackson.core:jackson-core 存在资源管理错误漏洞|资源管理错误|[MPS-2022-11944](https://www.oscs1024.com/hd/MPS-2022-11944)||中危|
|Apache HttpClient URI解析错误漏洞|相对路径遍历|[MPS-2022-12292](https://www.oscs1024.com/hd/MPS-2022-12292)||中危|
|Apache Commons Collections 远程代码执行漏洞|反序列化|[MPS-2022-12767](https://www.oscs1024.com/hd/MPS-2022-12767)||高危|
|Apache Log4j JDBCAppender SQL注入漏洞|SQL注入|[MPS-2022-1444](https://www.oscs1024.com/hd/MPS-2022-1444)|CVE-2022-23305|严重|
|Apache Log4j Chainsaw反序列化漏洞|反序列化|[MPS-2022-1445](https://www.oscs1024.com/hd/MPS-2022-1445)|CVE-2022-23307|高危|
|Apache Log4j 反序列化漏洞|反序列化|[MPS-2022-1446](https://www.oscs1024.com/hd/MPS-2022-1446)|CVE-2022-23302|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|log4j:log4j|1.2.17||直接依赖|建议修复|C:2|H:3|M:0|L:1|
|commons-collections:commons-collections|3.2.1|3.2.2|直接依赖|建议修复|C:1|H:2|M:0|L:0|
|org.apache.httpcomponents:httpclient|4.5.1|4.5.13|直接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.fasterxml.jackson.core:jackson-core|2.2.3|2.8.6|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-codec:commons-codec|1.4|1.13|直接依赖|可选修复|C:0|H:0|M:0|L:1|
|commons-codec:commons-codec|1.9|1.13|直接依赖|可选修复|C:0|H:0|M:0|L:1|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|3|Low|
|Apache-2.0|12|Low|
|自定义许可证|3|Low|
|LGPL-2.1|4|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.slf4j:slf4j-jcl|1.7.7|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.1|直接依赖|maven|
|libc.so.1||间接依赖||
|logkit:logkit|1.0.1|直接依赖|maven|
|commons-codec:commons-codec|1.4|直接依赖|maven|
|javax.jms:jms|1.1|直接依赖|maven|
|avalon-framework:avalon-framework|4.1.5|直接依赖|maven|
|libc.so.6||间接依赖||
|msvcrt.dll||间接依赖||
|javax.activation:activation|1.1|间接依赖|maven|
|net.java.dev.jna:jna-platform|4.1.0|直接依赖|maven|
|org.slf4j:slf4j-api|1.5.6|直接依赖|maven|
|net.java.dev.jna:jna|4.1.0|直接依赖|maven|
|commons-logging:commons-logging|1.2|直接依赖|maven|
|javax.mail:mail|1.4|直接依赖|maven|
|net.sf.ehcache:ehcache-core|2.6.9|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.3|直接依赖|maven|
|ole32.dll||间接依赖||
|org.slf4j:slf4j-api|1.6.1|间接依赖|maven|
|com.sun.jmx:jmxri|1.2.1|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.2.3|直接依赖|maven|
|KERNEL32.dll||间接依赖||
|PSAPI.DLL||间接依赖||
|MSVBVM60.DLL||间接依赖||
|com.sun.jdmk:jmxtools|1.2.1|直接依赖|maven|
|log4j:log4j|1.2.17|直接依赖|maven|
|SHELL32.dll||间接依赖||
|commons-logging:commons-logging|1.1.1|直接依赖|maven|
|USER32.dll||间接依赖||
|org.apache.httpcomponents:httpcore|4.1|直接依赖|maven|
|commons-codec:commons-codec|1.9|直接依赖|maven|
|commons-collections:commons-collections|3.2.1|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.2.3|直接依赖|maven|
|net.spy:spymemcached|2.11.4|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)