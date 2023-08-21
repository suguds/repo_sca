# tennc/webshell安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1693692209085112320.svg)](https://www.murphysec.com/console/report/1693692209047363584/1693692209085112320)

仓库描述：This is a webshell open source project

仓库地址：[https://github.com/tennc/webshell](https://github.com/tennc/webshell)

| star：9258 | watch：495 | fork：5605 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-04-09 20:31:06 | 许可证：MIT |
| 最近检测时间：2023-08-22 02:38:54 | 组件总数：53 | 漏洞总数：13 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Jetty 拒绝服务漏洞|密码学问题|[MPS-2011-4130](https://www.oscs1024.com/hd/MPS-2011-4130)|CVE-2011-4461|中危|
|Jetty 信息泄露漏洞|通过差异性导致的信息暴露|[MPS-2017-6690](https://www.oscs1024.com/hd/MPS-2017-6690)|CVE-2017-9735|高危|
|UnboundID LDAP SDK 访问控制错误漏洞|弱口令要求|[MPS-2018-3326](https://www.oscs1024.com/hd/MPS-2018-3326)|CVE-2018-1000134|严重|
|Eclipse Jetty <9.4.11.v20180605 授权绕过漏洞||[MPS-2018-8347](https://www.oscs1024.com/hd/MPS-2018-8347)|CVE-2017-7657|严重|
|Eclipse Jetty <9.4.11.v20180605 存在授权绕过漏洞|HTTP请求走私|[MPS-2018-8415](https://www.oscs1024.com/hd/MPS-2018-8415)|CVE-2017-7658|严重|
|Apache MINA <2.1.1 明文传输漏洞|敏感数据的明文传输|[MPS-2019-12494](https://www.oscs1024.com/hd/MPS-2019-12494)|CVE-2019-0231|高危|
|Eclipse Jetty 信息泄露漏洞|未授权敏感信息泄露|[MPS-2019-4270](https://www.oscs1024.com/hd/MPS-2019-4270)|CVE-2019-10247|中危|
|dom4j SaxReader函数存在 XXE 漏洞|XXE|[MPS-2020-6967](https://www.oscs1024.com/hd/MPS-2020-6967)|CVE-2020-10683|严重|
|Eclipse Jetty 资源管理错误漏洞|对异常条件的处理不恰当|[MPS-2021-3864](https://www.oscs1024.com/hd/MPS-2021-3864)|CVE-2021-28165|高危|
|Eclipse Jetty 存在信息泄露漏洞|不充分的会话过期机制|[MPS-2021-8884](https://www.oscs1024.com/hd/MPS-2021-8884)|CVE-2021-34428|低危|
|Eclipse Jetty URI注入漏洞|注入|[MPS-2022-18060](https://www.oscs1024.com/hd/MPS-2022-18060)|CVE-2022-2047|低危|
|Eclipse Jetty 资源管理错误漏洞|拒绝服务|[MPS-2023-4997](https://www.oscs1024.com/hd/MPS-2023-4997)|CVE-2023-26048|中危|
|Eclipse Jetty 信息泄露漏洞|XSS|[MPS-2023-4998](https://www.oscs1024.com/hd/MPS-2023-4998)|CVE-2023-26049|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.eclipse.jetty:jetty-util|7.5.4.v20111024|9.4.17.v20190418|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.mina:mina-core|1.1.7|2.1.1|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-server|7.5.4.v20111024|12.0.0.beta0|直接依赖|建议修复|C:0|H:0|M:4|L:1|
|dom4j:dom4j|1.6.1||直接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.eclipse.jetty:jetty-http|7.5.4.v20111024|11.0.10|直接依赖|建议修复|C:2|H:0|M:0|L:1|
|com.unboundid:unboundid-ldapsdk|3.1.1|4.0.5|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.eclipse.jetty:jetty-io|7.5.4.v20111024|11.0.10|直接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|14|Low|
|MIT|2|Low|
|GPL-2.0|1|Medium|
|LGPL-2.1-or-later|1|Low|
|自定义许可证|4|Low|
|LGPL-2.1|1|Medium|
|MPL-1.1|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.eclipse.jetty:jetty-io|7.5.4.v20111024|直接依赖|maven|
|org.eclipse.jetty:jetty-continuation|7.5.4.v20111024|直接依赖|maven|
|org.slf4j:slf4j-api|1.5.8|直接依赖|maven|
|/usr/lib/libSystem.B.dylib||间接依赖||
|org.apache.mina:mina-core|1.1.7|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.31|直接依赖|maven|
|GDI32.dll||间接依赖||
|WININET.dll||间接依赖||
|org.eclipse.jetty:jetty-http|7.5.4.v20111024|直接依赖|maven|
|com.unboundid:unboundid-ldapsdk|3.1.1|直接依赖|maven|
|libc.so.6||间接依赖||
|VERSION.dll||间接依赖||
|libpthread.so.0||间接依赖||
|libdl.so||间接依赖||
|/usr/lib/libgcc_s.1.dylib||间接依赖||
|libc.so.7||间接依赖||
|org.slf4j:slf4j-api|1.4.3|直接依赖|maven|
|QMainWindow||间接依赖|pip|
|libc.so||间接依赖||
|dom4j:dom4j|1.6.1|直接依赖|maven|
|MSVCR100D.dll||间接依赖||
|msvcrt.dll||间接依赖||
|MSVCRT.dll||间接依赖||
|org.apache.mina:mina-core||直接依赖|maven|
|liblog.so||间接依赖||
|KERNEL32.dll||间接依赖||
|ole32.dll||间接依赖||
|org.eclipse.jetty:jetty-util|7.5.4.v20111024|直接依赖|maven|
|pyqtSignal||间接依赖|pip|
|gdiplus.dll||间接依赖||
|org.eclipse.jetty:jetty-xml|7.5.4.v20111024|直接依赖|maven|
|net.jcip:jcip-annotations|1.0|直接依赖|maven|
|org.gnu.inet:libidn|1.15|直接依赖|maven|
|xml-apis:xml-apis|1.0.b2|间接依赖|maven|
|WINMM.dll||间接依赖||
|libm.so||间接依赖||
|org.eclipse.jetty:jetty-jmx|7.5.4.v20111024|直接依赖|maven|
|org.mortbay.jetty:servlet-api-2.5|6.0.1|直接依赖|maven|
|org.eclipse.jetty:jetty-servlet|7.5.4.v20111024|直接依赖|maven|
|com.googlecode.concurrentlinkedhashmap:concurrentlinkedhashmap-lru|1.0_jdk5|直接依赖|maven|
|org.eclipse.jetty:jetty-security|7.5.4.v20111024|直接依赖|maven|
|pyqtSlot||间接依赖|pip|
|QApplication||间接依赖|pip|
|javax.servlet:servlet-api|2.5|直接依赖|maven|
|USER32.dll||间接依赖||
|com.jcraft:jzlib|1.0.7|直接依赖|maven|
|org.eclipse.jetty:jetty-server|7.5.4.v20111024|直接依赖|maven|
|SHELL32.dll||间接依赖||
|mscoree.dll||间接依赖||
|COMCTL32.dll||间接依赖||
|libandroid.so||间接依赖||
|ADVAPI32.dll||间接依赖||
|org.javassist:javassist|3.22.0-GA|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)