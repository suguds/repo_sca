# hibernate/hibernate-orm安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696584824021409792.svg)](https://www.murphysec.com/console/report/1696584823979466752/1696584824021409792)

仓库描述：Hibernate's core Object/Relational Mapping functionality

仓库地址：[https://github.com/hibernate/hibernate-orm](https://github.com/hibernate/hibernate-orm)

| star：5531 | watch：304 | fork：3333 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-30 01:07:02 | 许可证：- |
| 最近检测时间：2023-08-30 02:18:49 | 组件总数：121 | 漏洞总数：15 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Red Hat Wildfly 授权问题漏洞|未授权敏感信息泄露|[MPS-2020-13052](https://www.oscs1024.com/hd/MPS-2020-13052)|CVE-2020-1748|高危|
|Red Hat WildFly Elytron 授权问题漏洞|会话固定|[MPS-2020-13470](https://www.oscs1024.com/hd/MPS-2020-13470)|CVE-2020-10714|高危|
|hibernate-core <5.4.24.Final 存在 SQL 注入漏洞|SQL注入|[MPS-2020-16768](https://www.oscs1024.com/hd/MPS-2020-16768)|CVE-2020-25638|高危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Hibernate 存在 SQL 注入漏洞|SQL注入|[MPS-2020-9908](https://www.oscs1024.com/hd/MPS-2020-9908)|CVE-2019-14900|中危|
|Red Hat Wildfly Elytron 安全漏洞|通过差异性导致的信息暴露|[MPS-2021-11706](https://www.oscs1024.com/hd/MPS-2021-11706)|CVE-2021-3642|中危|
|Wildfly 安全漏洞|对外部实体的文件或目录可访问|[MPS-2021-28138](https://www.oscs1024.com/hd/MPS-2021-28138)|CVE-2021-3717|高危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|David M. Lloyd jboss-remoting 资源管理错误漏洞|拒绝服务|[MPS-2021-7523](https://www.oscs1024.com/hd/MPS-2021-7523)|CVE-2020-35510|中危|
|Red Hat XNIO 资源错误分配漏洞|不加限制或调节的资源分配|[MPS-2022-0191](https://www.oscs1024.com/hd/MPS-2022-0191)|CVE-2022-0084|高危|
|org.apache.maven.shared:maven-shared-utils 存在命令注入漏洞|命令注入|[MPS-2022-12562](https://www.oscs1024.com/hd/MPS-2022-12562)||高危|
|H2 Console 代码注入漏洞|代码注入|[MPS-2022-1435](https://www.oscs1024.com/hd/MPS-2022-1435)|CVE-2022-23221|严重|
|Apache Maven Shared Utils 系统命令注入漏洞|命令注入|[MPS-2022-9177](https://www.oscs1024.com/hd/MPS-2022-9177)|CVE-2022-29599|严重|
|Red Hat wildfly-elytron 安全漏洞|通过差异性导致的信息暴露|[MPS-2023-1618](https://www.oscs1024.com/hd/MPS-2023-1618)|CVE-2022-3143|高危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.hibernate:hibernate-core|$version|5.4.24.Final|直接依赖|建议修复|C:0|H:1|M:1|L:0|
|org.wildfly.security:wildfly-elytron|1.1.0.Final|1.20.3.final|间接依赖|建议修复|C:0|H:4|M:1|L:0|
|com.h2database:h2|$h2|2.1.210|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.apache.maven.shared:maven-shared-utils|3.2.1|3.3.3|间接依赖|建议修复|C:1|H:1|M:0|L:0|
|com.google.guava:guava|25.1-android|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:1|
|org.jboss.xnio:xnio-api|3.5.1.Final|3.8.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.jboss.remoting:jboss-remoting|5.0.0.Final|5.0.20.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-io:commons-io|2.5|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|20|Low|
|Apache-2.0|60|Low|
|MIT|10|Low|
|EPL-2.0|9|Low|
|EPL-1.0|7|Low|
|LGPL-3.0|1|Medium|
|LGPL-2.1|6|Medium|
|LGPL-2.1-or-later|2|Low|
|BSD-2-Clause|1|Low|
|CDDL-1.0|1|Low|
|MPL-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.sun.istack:istack-commons-runtime|4.1.1|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.14.7|直接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|4.0.0|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.25|直接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.17.1|直接依赖|maven|
|org.codehaus.plexus:plexus-interpolation|1.25|间接依赖|maven|
|org.opentest4j:opentest4j|1.2.0|间接依赖|maven|
|jakarta.resource:jakarta.resource-api|2.0.0|间接依赖|maven|
|org.apache.maven.resolver:maven-resolver-spi|1.6.2|间接依赖|maven|
|org.apache.maven:maven-settings|3.8.1|间接依赖|maven|
|org.jboss.narayana.jta:narayana-jta|7.0.0.Final|直接依赖|maven|
|org.mockito:mockito-inline|5.2.0|直接依赖|maven|
|org.apache.maven:maven-plugin-api|3.8.1|直接依赖|maven|
|org.javamoney:moneta|1.1|直接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.1|间接依赖|maven|
|jakarta.inject:jakarta.inject-api|2.0.1|直接依赖|maven|
|io.smallrye:jandex|3.1.2|直接依赖|maven|
|org.slf4j:slf4j-simple|$slf4j|直接依赖|maven|
|org.wildfly.client:wildfly-client-config|1.0.0.Final|间接依赖|maven|
|org.apache.maven:maven-builder-support|3.8.1|间接依赖|maven|
|org.jboss:jboss-transaction-spi|8.0.0.Final|直接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|org.wildfly.common:wildfly-common|1.2.0.Final|间接依赖|maven|
|javax.cache:cache-api|1.0.0|直接依赖|maven|
|org.vibur:vibur-object-pool|25.0|直接依赖|maven|
|jakarta.persistence:jakarta.persistence-api|3.1.0|直接依赖|maven|
|org.hamcrest:hamcrest-core|1.3|间接依赖|maven|
|org.junit.jupiter:junit-jupiter-api|5.9.2|直接依赖|maven|
|javax.money:money-api|1.0.1|直接依赖|maven|
|org.eclipse.sisu:org.eclipse.sisu.plexus|0.3.4|间接依赖|maven|
|javax.enterprise:cdi-api|1.0|间接依赖|maven|
|org.wildfly:wildfly-naming-client|1.0.4.Final|间接依赖|maven|
|net.bytebuddy:byte-buddy-agent|1.14.7|间接依赖|maven|
|org.geolatte:geolatte-geom|1.8.2|直接依赖|maven|
|io.agroal:agroal-api|2.0|直接依赖|maven|
|org.jboss.byteman:byteman-submit|4.0.20|间接依赖|maven|
|org.hibernate.common:hibernate-commons-annotations|6.0.6.Final|直接依赖|maven|
|com.google.inject:guice|4.2.1|间接依赖|maven|
|org.apache.maven.resolver:maven-resolver-impl|1.6.2|间接依赖|maven|
|org.apache.logging.log4j:log4j-core||直接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.14|间接依赖|maven|
|org.jboss.byteman:byteman-bmunit|4.0.20|直接依赖|maven|
|org.sonatype.plexus:plexus-build-api|0.0.7|直接依赖|maven|
|org.apache.maven:maven-artifact|3.8.1|直接依赖|maven|
|org.slf4j:slf4j-api|1.6.1|间接依赖|maven|
|com.mchange:mchange-commons-java|0.2.19|直接依赖|maven|
|::hibernate-community-dialects||直接依赖|maven|
|io.micrometer:micrometer-core|1.10.4|直接依赖|maven|
|org.junit.jupiter:junit-jupiter-params|5.9.2|直接依赖|maven|
|junit:junit|4.13.2|直接依赖|maven|
|org.hibernate.orm.fork:jaxb2-basics-runtime|3.0.patched-SNAPSHOT|直接依赖|maven|
|org.apache.maven:maven-repository-metadata|3.8.1|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.7|直接依赖|maven|
|com.google.guava:guava|25.1-android|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.1|间接依赖|maven|
|org.wildfly.security:wildfly-elytron|1.1.0.Final|间接依赖|maven|
|org.apache.maven:maven-settings-builder|3.8.1|间接依赖|maven|
|org.locationtech.jts:jts-core||间接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|org.jboss.byteman:byteman|4.0.20|直接依赖|maven|
|::hibernate-core||直接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|直接依赖|maven|
|org.eclipse.angus:angus-activation|2.0.0|间接依赖|maven|
|jakarta.transaction:jakarta.transaction-api|2.0.1|直接依赖|maven|
|javax.annotation:jsr250-api|1.0|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|2.0.0|间接依赖|maven|
|org.mockito:mockito-core|5.2.0|直接依赖|maven|
|commons-io:commons-io|2.5|间接依赖|maven|
|org.apache.maven.plugin-tools:maven-plugin-annotations|3.2|直接依赖|maven|
|org.apache.maven:maven-resolver-provider|3.8.1|间接依赖|maven|
|org.eclipse.sisu:org.eclipse.sisu.inject|0.3.4|间接依赖|maven|
|com.mchange:c3p0|0.9.5.5|直接依赖|maven|
|org.jboss.marshalling:jboss-marshalling-river|2.0.0.Final|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|直接依赖|maven|
|org.sonatype.plexus:plexus-sec-dispatcher|1.4|间接依赖|maven|
|org.jboss.byteman:byteman-install|4.0.20|直接依赖|maven|
|org.sonatype.plexus:plexus-cipher|1.4|间接依赖|maven|
|org.codehaus.plexus:plexus-component-annotations|2.1.0|间接依赖|maven|
|org.codehaus.plexus:plexus-utils|3.2.1|直接依赖|maven|
|org.apache.maven.resolver:maven-resolver-util|1.6.2|间接依赖|maven|
|org.apache.maven:maven-model|3.8.1|间接依赖|maven|
|::hibernate-envers||直接依赖|maven|
|org.apache.commons:commons-lang3|3.8.1|间接依赖|maven|
|org.jboss.marshalling:jboss-marshalling|2.0.0.Final|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.2|间接依赖|maven|
|org.codehaus.plexus:plexus-classworlds|2.6.0|间接依赖|maven|
|io.micrometer:micrometer-commons|1.10.4|直接依赖|maven|
|org.checkerframework:checker-compat-qual|2.0.0|间接依赖|maven|
|org.antlr:antlr4-runtime|4.10.1|直接依赖|maven|
|com.google.errorprone:error||间接依赖|maven|
|org.apache.maven:maven-model-builder|3.8.1|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.30|间接依赖|maven|
|org.jboss.remoting:jboss-remoting|5.0.0.Final|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.13|直接依赖|maven|
|org.jboss.xnio:xnio-api|3.5.1.Final|间接依赖|maven|
|org.wildfly.transaction:wildfly-transaction-client-jakarta|2.0.0.Final|直接依赖|maven|
|org.hamcrest:hamcrest-all|1.3|直接依赖|maven|
|com.h2database:h2|$h2|直接依赖|maven|
|org.glassfish.jaxb:txw2|4.0.2|间接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|4.0.2|直接依赖|maven|
|com.experlog:xapool|1.5.0|直接依赖|maven|
|commons-logging:commons-logging|1.2|直接依赖|maven|
|org.apache.maven:maven-core|3.8.1|直接依赖|maven|
|org.apache.maven.resolver:maven-resolver-api|1.6.2|间接依赖|maven|
|org.objenesis:objenesis|3.3|间接依赖|maven|
|org.glassfish.jaxb:jaxb-core|4.0.2|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|直接依赖|maven|
|org.jboss.logging:jboss-logging|3.5.0.Final|直接依赖|maven|
|org.vibur:vibur-dbcp|25.0|直接依赖|maven|
|io.micrometer:micrometer-observation|1.10.4|直接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|2.1.1|间接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|直接依赖|maven|
|org.assertj:assertj-core|3.22.0|直接依赖|maven|
|com.zaxxer:HikariCP|3.2.0|直接依赖|maven|
|org.hibernate:hibernate-core|$version|直接依赖|maven|
|junit:junit|$junit|直接依赖|maven|
|org.junit:junit-bom|5.9.2|间接依赖|maven|
|org.apache.maven.shared:maven-shared-utils|3.2.1|间接依赖|maven|
|proxool:proxool|0.8.3|直接依赖|maven|
|org.junit.platform:junit-platform-commons|1.9.2|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)