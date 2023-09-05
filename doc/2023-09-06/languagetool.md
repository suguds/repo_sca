# languagetool-org/languagetool安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699120358447775744.svg)](https://www.murphysec.com/console/report/1697308421824274432/1699120358447775744)

仓库描述：Style and Grammar Checker for 25+ Languages

仓库地址：[https://github.com/languagetool-org/languagetool](https://github.com/languagetool-org/languagetool)

| star：9892 | watch：157 | fork：1148 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-06 00:10:40 | 许可证：LGPL-2.1 |
| 最近检测时间：2023-09-06 02:07:13 | 组件总数：178 | 漏洞总数：3 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.fasterxml.jackson.core:jackson-databind|2.14.2||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|io.netty:netty-handler|4.1.79.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|95|Low|
|自定义许可证|65|Low|
|LGPL-2.1|6|Medium|
|EPL-1.0|3|Low|
|LGPL-2.1-or-later|2|Low|
|MIT|4|Low|
|BSD-3-Clause|1|Low|
|BSD-2-Clause|1|Low|
|CDDL-1.1|3|Low|
|GPL-2.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.apache.commons:commons-csv|1.9.0|直接依赖|maven|
|org.carrot2:morfologik-speller|2.1.9|直接依赖|maven|
|io.prometheus:simpleclient_tracer_otel_agent|0.12.0|间接依赖|maven|
|io.github.resilience4j:resilience4j-circuitbreaker|1.7.1|直接依赖|maven|
|javax.measure:unit-api|1.0|直接依赖|maven|
|org.tukaani:xz|1.8|直接依赖|maven|
|org.ioperm:morphology-el|1.0.0|直接依赖|maven|
|org.languagetool:languagetool-commandline|6.3-SNAPSHOT|直接依赖|maven|
|org.languagetool:language-be|6.3-SNAPSHOT|直接依赖|maven|
|xtc:rats-runtime|1.15.0|间接依赖|maven|
|org.apache.lucene:lucene-queries|5.5.5|直接依赖|maven|
|org.carrot2:morfologik-fsa-builders|2.1.9|直接依赖|maven|
|ch.qos.logback:logback-classic|1.3.6|直接依赖|maven|
|edu.washington.cs.knowitall:opennlp-chunk-models|1.5|直接依赖|maven|
|org.languagetool:language-es|6.3-SNAPSHOT|直接依赖|maven|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|de.fau.cs.osr.ptk:ptk-common|3.0.8|间接依赖|maven|
|org.languagetool:languagetool-http-client|6.3-SNAPSHOT|直接依赖|maven|
|org.jvnet.staxex:stax-ex|1.7.8|间接依赖|maven|
|io.github.resilience4j:resilience4j-core|1.7.1|间接依赖|maven|
|org.languagetool:language-ca|6.3-SNAPSHOT|直接依赖|maven|
|io.opentelemetry:opentelemetry-context|1.26.0|间接依赖|maven|
|edu.washington.cs.knowitall:opennlp-tokenize-models|1.5|直接依赖|maven|
|org.apache.lucene:lucene-core|5.5.5|直接依赖|maven|
|org.apache.lucene:lucene-sandbox|5.5.5|直接依赖|maven|
|io.github.java-diff-utils:java-diff-utils|4.12|直接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|io.grpc:grpc-protobuf|1.56.1|直接依赖|maven|
|net.java.dev.jna:jna-platform|5.12.1|间接依赖|maven|
|org.checkerframework:checker-qual|3.33.0|间接依赖|maven|
|commons-logging:commons-logging|1.2|直接依赖|maven|
|ua.net.nlp:morfologik-ukrainian-lt|6.1.5|直接依赖|maven|
|org.languagetool:portuguese-pos-dict|0.3|直接依赖|maven|
|org.jetbrains:annotations|20.1.0|直接依赖|maven|
|io.prometheus:simpleclient_httpserver|0.12.0|直接依赖|maven|
|org.apache.commons:commons-compress|1.21|直接依赖|maven|
|com.carrotsearch:hppc|0.8.2|直接依赖|maven|
|org.jetbrains.intellij.deps:trove4j|1.0.20200330|直接依赖|maven|
|jakarta-regexp:jakarta-regexp|1.4|间接依赖|maven|
|commons-io:commons-io|2.11.0|直接依赖|maven|
|io.vavr:vavr-match|0.10.2|间接依赖|maven|
|org.languagetool:language-en|6.3-SNAPSHOT|直接依赖|maven|
|io.grpc:grpc-netty-shaded|1.56.1|直接依赖|maven|
|com.intellij:annotations|12.0|间接依赖|maven|
|org.apache.commons:commons-collections4|4.4|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.18.0|间接依赖|maven|
|com.google.guava:guava|32.1.1-jre|直接依赖|maven|
|com.google.code.gson:gson|2.10.1|间接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|直接依赖|maven|
|org.languagetool:language-de-DE-x-simple-language|6.3-SNAPSHOT|直接依赖|maven|
|com.hankcs:aho-corasick-double-array-trie|1.2.2|直接依赖|maven|
|com.gitlab.dumonts:hunspell|2.1.2|直接依赖|maven|
|io.github.resilience4j:resilience4j-micrometer|1.7.1|直接依赖|maven|
|net.java.dev.jna:jna|5.12.1|间接依赖|maven|
|org.languagetool:language-fa|6.3-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.14.2|间接依赖|maven|
|io.netty:netty-resolver|4.1.79.Final|间接依赖|maven|
|org.apache.lucene:lucene-analyzers-common|5.5.5|直接依赖|maven|
|org.languagetool:language-eo|6.3-SNAPSHOT|直接依赖|maven|
|com.sun.xml.fastinfoset:FastInfoset|1.2.13|间接依赖|maven|
|org.apache.lucene:lucene-backward-codecs|5.5.5|直接依赖|maven|
|org.languagetool:language-ru|6.3-SNAPSHOT|直接依赖|maven|
|org.languagetool:language-zh|6.3-SNAPSHOT|直接依赖|maven|
|io.prometheus:simpleclient_guava|0.12.0|直接依赖|maven|
|org.languagetool:language-ast|6.3-SNAPSHOT|直接依赖|maven|
|io.netty:netty-transport|4.1.79.Final|间接依赖|maven|
|commons-cli:commons-cli|1.5.0|直接依赖|maven|
|com.ibm.icu:icu4j|70.1|直接依赖|maven|
|org.languagetool:language-br|6.3-SNAPSHOT|直接依赖|maven|
|org.languagetool:language-ro|6.3-SNAPSHOT|直接依赖|maven|
|org.languagetool:language-gl|6.3-SNAPSHOT|直接依赖|maven|
|com.hankcs:hanlp|portable-1.8.2|直接依赖|maven|
|com.google.protobuf:protobuf-java|3.22.3|间接依赖|maven|
|org.languagetool:language-fr|6.3-SNAPSHOT|直接依赖|maven|
|org.languagetool:language-km|6.3-SNAPSHOT|直接依赖|maven|
|org.languagetool:language-tl|6.3-SNAPSHOT|直接依赖|maven|
|org.carrot2:morfologik-fsa|2.1.9|直接依赖|maven|
|org.languagetool:language-nl|6.3-SNAPSHOT|直接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|直接依赖|maven|
|io.perfmark:perfmark-api|0.26.0|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|org.languagetool:french-pos-dict|0.5|直接依赖|maven|
|tech.units:indriya|1.3|直接依赖|maven|
|org.languagetool:language-ga|6.3-SNAPSHOT|直接依赖|maven|
|org.languagetool:language-ta|6.3-SNAPSHOT|直接依赖|maven|
|org.sweble.wikitext:swc-engine|3.1.9|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.14.2|直接依赖|maven|
|org.sweble.wikitext:swc-parser-lazy|3.1.9|直接依赖|maven|
|io.prometheus:simpleclient_tracer_otel|0.12.0|间接依赖|maven|
|com.sun.xml.bind:jaxb-impl|2.2.5|间接依赖|maven|
|org.apache.commons:commons-pool2|2.11.1|直接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.56.1|间接依赖|maven|
|org.languagetool:language-ja|6.3-SNAPSHOT|直接依赖|maven|
|io.grpc:grpc-context|1.56.1|间接依赖|maven|
|org.languagetool:language-sv|6.3-SNAPSHOT|直接依赖|maven|
|tech.uom.lib:uom-lib-common|1.1|间接依赖|maven|
|co.elastic.logging:logback-ecs-encoder|1.3.2|直接依赖|maven|
|org.languagetool:language-it|6.3-SNAPSHOT|直接依赖|maven|
|org.languagetool:language-da|6.3-SNAPSHOT|直接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|直接依赖|maven|
|io.netty:netty-common|4.1.79.Final|间接依赖|maven|
|org.mybatis:mybatis|3.5.9|直接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|2.3.0|直接依赖|maven|
|io.opentelemetry:opentelemetry-api|1.26.0|直接依赖|maven|
|io.projectreactor:reactor-core|3.3.22.RELEASE|间接依赖|maven|
|org.languagetool:language-el|6.3-SNAPSHOT|直接依赖|maven|
|org.mariadb.jdbc:mariadb-java-client|2.7.6|直接依赖|maven|
|org.languagetool:language-ar|6.3-SNAPSHOT|直接依赖|maven|
|edu.washington.cs.knowitall:opennlp-postag-models|1.5|直接依赖|maven|
|commons-digester:commons-digester|2.1|间接依赖|maven|
|org.apache.opennlp:opennlp-tools|1.9.4|直接依赖|maven|
|io.grpc:grpc-stub|1.56.1|直接依赖|maven|
|org.hamcrest:hamcrest-core|1.3|间接依赖|maven|
|org.languagetool:language-sk|6.3-SNAPSHOT|直接依赖|maven|
|org.languagetool:language-all|6.3-SNAPSHOT|直接依赖|maven|
|com.google.j2objc:j2objc-annotations|2.8|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|org.languagetool:languagetool-server|6.3-SNAPSHOT|直接依赖|maven|
|io.vavr:vavr|0.10.2|间接依赖|maven|
|org.languagetool:languagetool-tools|6.3-SNAPSHOT|直接依赖|maven|
|de.danielnaber:jwordsplitter|4.5|直接依赖|maven|
|org.languagetool:languagetool-wikipedia|6.3-SNAPSHOT|直接依赖|maven|
|com.optimaize.languagedetector:language-detector|0.6|直接依赖|maven|
|io.opentelemetry:opentelemetry-semconv|1.26.0-alpha|直接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.0|直接依赖|maven|
|org.languagetool:languagetool-core|6.3-SNAPSHOT|直接依赖|maven|
|org.languagetool:language-sl|6.3-SNAPSHOT|直接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|org.apache.lucene:lucene-spatial|5.5.5|间接依赖|maven|
|io.lettuce:lettuce-core|6.1.9.RELEASE|直接依赖|maven|
|at.favre.lib:bytes|0.8.0|间接依赖|maven|
|com.sun.istack:istack-commons-runtime|3.0.5|间接依赖|maven|
|io.prometheus:simpleclient_tracer_common|0.12.0|间接依赖|maven|
|com.github.lucene-gosen:lucene-gosen|6.2.1|直接依赖|maven|
|io.netty:netty-codec|4.1.79.Final|间接依赖|maven|
|org.apache.commons:commons-text|1.10.0|直接依赖|maven|
|io.netty:netty-buffer|4.1.79.Final|间接依赖|maven|
|org.glassfish.jaxb:jaxb-core|2.3.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.14.2|间接依赖|maven|
|edu.washington.cs.knowitall:openregex|1.1.1|直接依赖|maven|
|org.glassfish.jaxb:txw2|2.3.0|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|io.grpc:grpc-api|1.56.1|间接依赖|maven|
|io.prometheus:simpleclient_hotspot|0.12.0|直接依赖|maven|
|io.netty:netty-handler|4.1.79.Final|间接依赖|maven|
|io.micrometer:micrometer-core|1.7.1|间接依赖|maven|
|org.languagetool:languagetool-gui-commons|6.3-SNAPSHOT|直接依赖|maven|
|io.prometheus:simpleclient|0.12.0|直接依赖|maven|
|org.carrot2:morfologik-stemming|2.1.9|直接依赖|maven|
|org.languagetool:language-de|6.3-SNAPSHOT|直接依赖|maven|
|commons-codec:commons-codec|1.15|直接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|2.17.0|间接依赖|maven|
|io.prometheus:simpleclient_common|0.10.0|间接依赖|maven|
|de.fau.cs.osr.utils:utils|3.0.8|间接依赖|maven|
|ch.qos.logback:logback-core|1.3.6|间接依赖|maven|
|io.grpc:grpc-core|1.56.1|间接依赖|maven|
|net.loomchild:segment|2.0.1|直接依赖|maven|
|org.softcatala:spanish-pos-dict|2.0|直接依赖|maven|
|org.languagetool:language-pt|6.3-SNAPSHOT|直接依赖|maven|
|org.json:json|20230227|直接依赖|maven|
|at.favre.lib:bcrypt|0.6.0|直接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.79.Final|间接依赖|maven|
|com.beust:jcommander|1.78|间接依赖|maven|
|de.danielnaber:german-pos-dict|1.2.4|直接依赖|maven|
|org.slf4j:slf4j-api|2.0.7|直接依赖|maven|
|commons-validator:commons-validator|1.7|直接依赖|maven|
|org.softcatala:catalan-pos-dict|2.22|直接依赖|maven|
|com.vdurmont:emoji-java|5.1.1|直接依赖|maven|
|io.prometheus:simpleclient_common|0.12.0|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|org.languagetool:language-uk|6.3-SNAPSHOT|直接依赖|maven|
|org.languagetool:language-pl|6.3-SNAPSHOT|直接依赖|maven|
|junit:junit|4.13.2|直接依赖|maven|
|io.github.jimregan:languagetool-ga-dicts|0.02|直接依赖|maven|
|org.carrot2:morfologik-tools|2.1.9|直接依赖|maven|
|net.arnx:jsonic|1.2.11|间接依赖|maven|
|co.elastic.logging:ecs-logging-core|1.3.2|间接依赖|maven|
|io.micrometer:micrometer-registry-prometheus|1.7.1|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)