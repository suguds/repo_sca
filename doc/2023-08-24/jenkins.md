# jenkinsci/jenkins安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694409576940990464.svg)](https://www.murphysec.com/console/report/1694409576903241728/1694409576940990464)

仓库描述：Jenkins automation server

仓库地址：[https://github.com/jenkinsci/jenkins](https://github.com/jenkinsci/jenkins)

| star：21288 | watch：861 | fork：8242 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-24 01:39:36 | 许可证：MIT |
| 最近检测时间：2023-08-24 02:29:42 | 组件总数：106 | 漏洞总数：6 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|CloudBees Jenkins 路径遍历漏洞|路径遍历|[MPS-2019-17328](https://www.oscs1024.com/hd/MPS-2019-17328)||中危|
|CloudBees Jenkins 信息泄露漏洞|权限管理不当|[MPS-2019-17329](https://www.oscs1024.com/hd/MPS-2019-17329)||中危|
|CloudBees Jenkins 路径遍历漏洞|路径遍历|[MPS-2019-8100](https://www.oscs1024.com/hd/MPS-2019-8100)|CVE-2019-10352|中危|
|CloudBees Jenkins 信息泄露漏洞|使用候选路径或通道进行的认证绕过|[MPS-2019-8102](https://www.oscs1024.com/hd/MPS-2019-8102)|CVE-2019-10354|中危|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|Jenkins 代码问题漏洞|反序列化|[MPS-2022-3642](https://www.oscs1024.com/hd/MPS-2022-3642)|CVE-2022-0538|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.jenkins-ci.main:jenkins-core|2.421-SNAPSHOT||直接依赖|建议修复|C:0|H:1|M:4|L:0|
|org.springframework:spring-web|5.3.29|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|17|Low|
|Apache-2.0|35|Low|
|BSD-3-Clause|7|Low|
|LGPL-2.1|3|Medium|
|MIT|15|Low|
|EPL-2.0|4|Low|
|Plexus|1|Low|
|BSD-2-Clause|3|Low|
|LGPL-2.1-or-later|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|org.jenkins-ci.main:remoting|3142.vcfca_0cd92128|直接依赖|maven|
|commons-io:commons-io|2.13.0|直接依赖|maven|
|org.jenkins-ci.main:cli|2.421-SNAPSHOT|直接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|org.jenkins-ci:commons-jexl|1.1-jenkins-20111212|直接依赖|maven|
|org.antlr:antlr4-runtime|4.13.0|直接依赖|maven|
|commons-lang:commons-lang|2.6|直接依赖|maven|
|org.samba.jcifs:jcifs|1.2.19|间接依赖|maven|
|org.jenkins-ci.main:websocket-spi|2.421-SNAPSHOT|直接依赖|maven|
|org.springframework:spring-core|5.3.29|间接依赖|maven|
|commons-discovery:commons-discovery|0.5|间接依赖|maven|
|org.slf4j:slf4j-api|2.0.7|间接依赖|maven|
|org.springframework:spring-aop|5.3.29|间接依赖|maven|
|net.sf.ezmorph:ezmorph|1.0.6|间接依赖|maven|
|org.jenkins-ci:annotation-indexer|1.17|直接依赖|maven|
|org.jenkins-ci:commons-jelly|1.1-jenkins-20230124|间接依赖|maven|
|org.ow2.asm:asm-commons|9.5|直接依赖|maven|
|org.samba.jcifs:jcifs|1.3.18-kohsuke-1|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|直接依赖|maven|
|org.apache.ant:ant-launcher|1.10.14|间接依赖|maven|
|org.glassfish.tyrus.bundles:tyrus-standalone-client-jdk|2.1.3|直接依赖|maven|
|net.java.sezpoz:sezpoz|1.13|直接依赖|maven|
|net.jcip:jcip-annotations|1.0|直接依赖|maven|
|org.jenkins-ci.main:websocket-jetty10|2.421-SNAPSHOT|直接依赖|maven|
|org.dom4j:dom4j|2.1.4|间接依赖|maven|
|org.kohsuke.stapler:stapler-adjunct-timeline|1.5|直接依赖|maven|
|jakarta.inject:jakarta.inject-api|2.0.1|间接依赖|maven|
|net.i2p.crypto:eddsa|0.3.0|直接依赖|maven|
|junit:junit|4.3.1|直接依赖|maven|
|commons-codec:commons-codec|1.16.0|直接依赖|maven|
|jaxen:jaxen|2.0.0|直接依赖|maven|
|org.kohsuke.stapler:stapler-groovy|1802.v9e2750160d01|直接依赖|maven|
|jakarta.servlet:jakarta.servlet-api|4.0.4|直接依赖|maven|
|org.springframework:spring-expression|5.3.29|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|2.1.1|间接依赖|maven|
|org.jvnet:tiger-types|2.2|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|org.jenkins-ci:crypto-util|1.9|直接依赖|maven|
|org.jenkins-ci.main:jenkins-core|2.421-SNAPSHOT|直接依赖|maven|
|com.jcraft:jzlib|1.1.3-kohsuke-1|直接依赖|maven|
|org.jenkins-ci:winstone|6.12|直接依赖|maven|
|org.jfree:jcommon|1.0.23|间接依赖|maven|
|org.apache.commons:commons-compress|1.23.0|直接依赖|maven|
|commons-fileupload:commons-fileupload|1.5|直接依赖|maven|
|org.kohsuke.jinterop:j-interop|2.0.8-kohsuke-1|直接依赖|maven|
|org.springframework.security:spring-security-core|5.8.6|间接依赖|maven|
|org.kohsuke.jinterop:j-interopdeps|2.0.8-kohsuke-1|间接依赖|maven|
|com.infradna.tool:bridge-method-annotation|1.28|直接依赖|maven|
|org.kohsuke.stapler:stapler|1802.v9e2750160d01|直接依赖|maven|
|org.jenkins-ci:symbol-annotation|1.24|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.25|直接依赖|maven|
|org.springframework:spring-beans|5.3.29|间接依赖|maven|
|org.kohsuke.stapler:json-lib|2.4-jenkins-3|直接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.1|间接依赖|maven|
|commons-jelly:commons-jelly-tags-fmt|1.0|直接依赖|maven|
|commons-collections:commons-collections|3.2.2|直接依赖|maven|
|org.springframework.security:spring-security-web|5.8.6|直接依赖|maven|
|args4j:args4j|2.33|直接依赖|maven|
|relaxngDatatype:relaxngDatatype|20020414|间接依赖|maven|
|com.thoughtworks.xstream:xstream|1.4.20|直接依赖|maven|
|org.jfree:jfreechart|1.0.19|直接依赖|maven|
|org.slf4j:log4j-over-slf4j|2.0.7|直接依赖|maven|
|org.jvnet.localizer:localizer|1.31|直接依赖|maven|
|org.kohsuke.stapler:stapler-jelly|1802.v9e2750160d01|间接依赖|maven|
|com.google.guava:guava|32.1.2-jre|直接依赖|maven|
|org.jvnet.winp:winp|1.30|直接依赖|maven|
|org.springframework:spring-web|5.3.29|间接依赖|maven|
|org.ow2.asm:asm-analysis|9.5|直接依赖|maven|
|net.java.dev.jna:jna|5.13.0|直接依赖|maven|
|org.springframework:spring-context|5.3.29|间接依赖|maven|
|io.github.x-stream:mxparser|1.2.2|间接依赖|maven|
|com.sun.xml.txw2:txw2|20110809|直接依赖|maven|
|org.slf4j:jcl-over-slf4j|2.0.7|直接依赖|maven|
|io.jenkins.stapler:jenkins-stapler-support|1.1|直接依赖|maven|
|org.codehaus.groovy:groovy-all|2.4.21|直接依赖|maven|
|org.ow2.asm:asm|9.5|直接依赖|maven|
|org.ow2.asm:asm-util|9.5|直接依赖|maven|
|org.apache.ant:ant|1.10.14|直接依赖|maven|
|org.jenkins-ci:version-number|1.11|直接依赖|maven|
|org.jvnet.hudson:commons-jelly-tags-define|1.1-jenkins-20230713|直接依赖|maven|
|org.fusesource.jansi:jansi|1.11|直接依赖|maven|
|com.sun.solaris:embedded_su4j|1.1|直接依赖|maven|
|org.apache.sshd:sshd-common|2.10.0|直接依赖|maven|
|com.github.spotbugs:spotbugs-annotations|4.7.3|直接依赖|maven|
|com.google.inject:guice|6.0.0|直接依赖|maven|
|org.jenkins-ci:task-reactor|1.8|直接依赖|maven|
|org.ow2.asm:asm-tree|9.5|直接依赖|maven|
|org.slf4j:slf4j-jdk14|2.0.7|直接依赖|maven|
|io.jenkins.stapler:jenkins-stapler-support|1.0|直接依赖|maven|
|org.springframework.security:spring-security-crypto|5.8.6|间接依赖|maven|
|org.kohsuke.stapler:stapler-adjunct-codemirror|1.3|直接依赖|maven|
|net.sf.kxml:kxml2|2.3.0|直接依赖|maven|
|org.apache.sshd:sshd-core|2.10.0|直接依赖|maven|
|org.jenkins-ci:memory-monitor|1.12|直接依赖|maven|
|xpp3:xpp3|1.1.4c|直接依赖|maven|
|org.jvnet.robust-http-client:robust-http-client|1.2|直接依赖|maven|
|org.kohsuke.metainf-services:metainf-services|1.11|直接依赖|maven|
|jakarta.servlet.jsp.jstl:jakarta.servlet.jsp.jstl-api|1.2.7|直接依赖|maven|
|jline:jline|2.14.6|直接依赖|maven|
|org.connectbot.jbcrypt:jbcrypt|1.0.0|直接依赖|maven|
|org.kohsuke:access-modifier-annotation|1.32|直接依赖|maven|
|commons-jelly:commons-jelly-tags-xml|1.1|直接依赖|maven|
|org.kohsuke:windows-package-checker|1.2|直接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)