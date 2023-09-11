# JabRef/jabref安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1701295611436646400.svg)](https://www.murphysec.com/console/report/1701295611373731840/1701295611436646400)

仓库描述：Graphical Java application for managing BibTeX and biblatex (.bib) databases

仓库地址：[https://github.com/JabRef/jabref](https://github.com/JabRef/jabref)

| star：3107 | watch：111 | fork：2161 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-12 02:04:03 | 许可证：MIT |
| 最近检测时间：2023-09-12 02:13:31 | 组件总数：152 | 漏洞总数：3 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|org.scala-lang:scala-library 存在反序列化漏洞（Gadget chain）|反序列化|[MPS-2022-52625](https://www.oscs1024.com/hd/MPS-2022-52625)|CVE-2022-36944|严重|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.scala-lang:scala-library|2.13.8|2.13.9|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.squareup.okio:okio|1.15.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.15.2||间接依赖|建议修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|74|Low|
|BSD-2-Clause|22|Low|
|EPL-2.0|15|Low|
|MIT|14|Low|
|BSD-3-Clause|5|Low|
|GPL-2.0-with-classpath-exception|1|Medium|
|自定义许可证|31|Low|
|MPL-2.0|3|Low|
|LGPL-2.1|2|Medium|
|MPL-1.1|1|Low|
|EPL-1.0|1|Low|
|LGPL-2.1-or-later|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.tinylog:tinylog-impl|2.6.2|直接依赖|maven|
|org.kordamp.ikonli:ikonli-core|12.3.1|间接依赖|maven|
|org.postgresql:postgresql|42.6.0|直接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|com.dlsc.unitfx:unitfx|1.0.10|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|2.1.1|直接依赖|maven|
|org.glassfish.hk2:osgi-resource-locator|1.0.3|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.15.2|间接依赖|maven|
|com.github.hypfvieh:dbus-java-core|4.2.1|间接依赖|maven|
|org.slf4j:slf4j-api|2.0.9|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.15.2|间接依赖|maven|
|org.kordamp.ikonli:ikonli-material-pack|12.3.1|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|3.0.2|间接依赖|maven|
|org.controlsfx:controlsfx|11.1.2|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.15.2|间接依赖|maven|
|org.tinylog:slf4j-tinylog|2.6.2|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.15.2|直接依赖|maven|
|org.glassfish.grizzly:grizzly-http-server|4.0.0|间接依赖|maven|
|org.apache.lucene:lucene-analysis-common|9.7.0|直接依赖|maven|
|jakarta.ws.rs:jakarta.ws.rs-api|3.1.0|直接依赖|maven|
|net.jodah:typetools|0.6.1|间接依赖|maven|
|org.reactfx:reactfx|2.0-M5|间接依赖|maven|
|org.openjfx:javafx-fxml|20|直接依赖|maven|
|org.glassfish.grizzly:grizzly-http|4.0.0|间接依赖|maven|
|org.eclipse.jgit:org.eclipse.jgit|6.7.0.202309050840-r|直接依赖|maven|
|commons-validator:commons-validator|1.7|间接依赖|maven|
|de.undercouch:citeproc-java|3.0.0-beta.2|直接依赖|maven|
|org.kordamp.ikonli:ikonli-materialdesign-pack|12.3.1|间接依赖|maven|
|com.google.code.gson:gson|2.10|间接依赖|maven|
|com.fasterxml.jackson:jackson-bom|2.15.2|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-dependency|0.64.8|间接依赖|maven|
|at.favre.lib:hkdf|1.1.0|间接依赖|maven|
|org.glassfish.hk2.external:aopalliance-repackaged|3.0.4|间接依赖|maven|
|org.libreoffice:libreoffice|7.6.0|直接依赖|maven|
|org.fxmisc.richtext:richtextfx|0.11.1|直接依赖|maven|
|org.mariadb.jdbc:mariadb-java-client|2.7.9|直接依赖|maven|
|org.fxmisc.wellbehaved:wellbehavedfx|0.3.3|间接依赖|maven|
|org.glassfish.jersey.core:jersey-common|3.1.3|间接依赖|maven|
|org.kordamp.ikonli:ikonli-javafx|12.3.1|直接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|间接依赖|maven|
|org.bouncycastle:bcprov-jdk18on|1.76|直接依赖|maven|
|org.glassfish.jersey.core:jersey-client|3.1.3|间接依赖|maven|
|tech.uom.lib:uom-lib-common|2.1|间接依赖|maven|
|org.jooq:jool|0.9.15|直接依赖|maven|
|com.vladsch.flexmark:flexmark-util-misc|0.64.8|间接依赖|maven|
|org.apache.commons:commons-csv|1.10.0|直接依赖|maven|
|com.dlsc.gemsfx:gemsfx|1.77.0|直接依赖|maven|
|de.swiesend:secret-service|1.8.1-jdk17|间接依赖|maven|
|info.debatty:java-string-similarity|2.0.0|直接依赖|maven|
|net.harawata:appdirs|1.2.2|直接依赖|maven|
|org.apache.lucene:lucene-highlighter|9.7.0|直接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|org.glassfish.hk2:hk2-api|3.0.4|直接依赖|maven|
|org.checkerframework:checker-qual|3.33.0|间接依赖|maven|
|org.yaml:snakeyaml|2.0|间接依赖|maven|
|org.javassist:javassist|3.29.2-GA|间接依赖|maven|
|com.sun.istack:istack-commons-runtime|4.0.1|间接依赖|maven|
|com.github.tomtung:latex2unicode||直接依赖|maven|
|org.jabref:afterburner.fx|2.0.0-SNAPSHOT|直接依赖|maven|
|org.scala-lang:scala-library|2.13.8|间接依赖|maven|
|org.fxmisc.undo:undofx|2.1.1|间接依赖|maven|
|commons-digester:commons-digester|2.1|间接依赖|maven|
|commons-cli:commons-cli|1.5.0|直接依赖|maven|
|tech.units:indriya|2.1.2|间接依赖|maven|
|io.github.java-diff-utils:java-diff-utils|4.12|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|间接依赖|maven|
|org.openjfx:javafx-graphics|20|间接依赖|maven|
|net.jcip:jcip-annotations|1.0|间接依赖|maven|
|org.openjfx:javafx-media|20|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-visitor|0.64.8|间接依赖|maven|
|org.slf4j:jul-to-slf4j|2.0.9|直接依赖|maven|
|org.apache.lucene:lucene-core|9.7.0|直接依赖|maven|
|org.apache.lucene:lucene-sandbox|9.7.0|间接依赖|maven|
|com.squareup.okhttp3:okhttp|3.12.0|间接依赖|maven|
|org.glassfish.jersey.core:jersey-server|3.1.3|直接依赖|maven|
|org.openjfx:javafx-base|20|间接依赖|maven|
|org.fxmisc.flowless:flowless|0.7.1|直接依赖|maven|
|com.oracle.ojdbc:ons|19.3.0.0|间接依赖|maven|
|com.h2database:h2-mvstore|2.2.222|直接依赖|maven|
|org.apache.lucene:lucene-memory|9.7.0|间接依赖|maven|
|org.glassfish.hk2:hk2-utils|3.0.4|间接依赖|maven|
|org.openjfx:javafx-swing|20|直接依赖|maven|
|commons-codec:commons-codec|1.16.0|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.15.2|直接依赖|maven|
|eu.lestard:doc-annotations|0.2|间接依赖|maven|
|com.konghq:unirest-java|3.14.5|直接依赖|maven|
|com.googlecode.javaewah:JavaEWAH|1.2.3|间接依赖|maven|
|com.github.javakeyring:java-keyring|1.0.4|直接依赖|maven|
|com.oracle.ojdbc:ucp|19.3.0.0|间接依赖|maven|
|one.jpro.jproutils:tree-showing|0.2.2|间接依赖|maven|
|org.kordamp.ikonli:ikonli-bootstrapicons-pack|12.3.1|间接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|com.squareup.okio:okio|1.15.0|间接依赖|maven|
|net.java.dev.jna:jna|5.13.0|间接依赖|maven|
|org.openjfx:javafx-controls|20|直接依赖|maven|
|org.tinylog:tinylog-api|2.6.2|直接依赖|maven|
|org.glassfish.jersey.inject:jersey-hk2|3.1.3|直接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|3.0.2|直接依赖|maven|
|org.kordamp.ikonli:ikonli-materialdesign2-pack|12.3.1|直接依赖|maven|
|com.vladsch.flexmark:flexmark-util-ast|0.64.8|间接依赖|maven|
|org.apache.lucene:lucene-queries|9.7.0|直接依赖|maven|
|com.oracle.ojdbc:osdt||间接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.5|间接依赖|maven|
|org.apache.commons:commons-lang3|3.13.0|直接依赖|maven|
|org.glassfish.jaxb:txw2|3.0.2|间接依赖|maven|
|jakarta.inject:jakarta.inject-api|2.0.1|直接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.13|间接依赖|maven|
|com.oracle.ojdbc:ojdbc10|19.3.0.0|直接依赖|maven|
|com.oracle.ojdbc:simplefan|19.3.0.0|间接依赖|maven|
|org.jetbrains:annotations|24.0.1|间接依赖|maven|
|net.java.dev.jna:jna-platform|5.13.0|间接依赖|maven|
|org.apache.pdfbox:pdfbox|3.0.0|直接依赖|maven|
|com.google.guava:guava|32.1.2-jre|直接依赖|maven|
|pt.davidafsilva.apple:jkeychain|1.1.0|间接依赖|maven|
|org.apache.pdfbox:fontbox|3.0.0|直接依赖|maven|
|com.vladsch.flexmark:flexmark-util-collection|0.64.8|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-html|0.64.8|间接依赖|maven|
|org.openjfx:javafx-web|20|直接依赖|maven|
|org.apache.commons:commons-text|1.10.0|间接依赖|maven|
|org.glassfish.hk2:hk2-locator|3.0.4|间接依赖|maven|
|org.glassfish.jaxb:jaxb-core|3.0.2|间接依赖|maven|
|javax.measure:unit-api|2.1.2|间接依赖|maven|
|com.google.guava:guava-parent|32.1.2-jre|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-data|0.64.8|间接依赖|maven|
|org.glassfish.grizzly:grizzly-framework|4.0.0|间接依赖|maven|
|org.libreoffice:unoloader|7.6.0|直接依赖|maven|
|com.squareup.retrofit2:retrofit|2.6.1|间接依赖|maven|
|com.dlsc.pickerfx:pickerfx|1.2.0|间接依赖|maven|
|org.apache.pdfbox:pdfbox-io|3.0.0|间接依赖|maven|
|com.microsoft.azure:applicationinsights-core|2.4.1|直接依赖|maven|
|org.apache.httpcomponents:httpmime|4.5.13|间接依赖|maven|
|org.apache.pdfbox:xmpbox|3.0.0|直接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-grizzly2-http|3.1.3|直接依赖|maven|
|de.sandec:JMemoryBuddy|0.5.1|间接依赖|maven|
|com.tobiasdiez:easybind|2.2.1-SNAPSHOT|直接依赖|maven|
|org.antlr:antlr4-runtime|4.13.0|直接依赖|maven|
|com.github.hypfvieh:dbus-java-transport-native-unixsocket|4.2.1|间接依赖|maven|
|com.sun.activation:jakarta.activation|2.0.1|间接依赖|maven|
|org.jsoup:jsoup|1.16.1|直接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|3.0.1|直接依赖|maven|
|com.microsoft.azure:applicationinsights-logging-log4j2|2.4.1|直接依赖|maven|
|org.apache.lucene:lucene-queryparser|9.7.0|直接依赖|maven|
|com.vladsch.flexmark:flexmark|0.64.8|直接依赖|maven|
|com.google.errorprone:error||间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-format|0.64.8|间接依赖|maven|
|com.github.sialcasa.mvvmFX:mvvmfx-validation|f195849ca9|直接依赖|maven|
|org.jbibtex:jbibtex|1.0.20|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-sequence|0.64.8|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.13|间接依赖|maven|
|de.saxsys:mvvmfx|1.8.0|直接依赖|maven|
|com.vladsch.flexmark:flexmark-util-builder|0.64.8|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)