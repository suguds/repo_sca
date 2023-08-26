# OWASP/wrongsecrets安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695496610015244288.svg)](https://www.murphysec.com/console/report/1695496609952329728/1695496610015244288)

仓库描述：Vulnerable app with examples showing how to not use secrets

仓库地址：[https://github.com/OWASP/wrongsecrets](https://github.com/OWASP/wrongsecrets)

| star：719 | watch：15 | fork：144 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-25 05:58:48 | 许可证：AGPL-3.0 |
| 最近检测时间：2023-08-27 02:08:14 | 组件总数：424 | 漏洞总数：8 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|SimpleXML 安全漏洞|XXE|[MPS-2017-13106](https://www.oscs1024.com/hd/MPS-2017-13106)|CVE-2017-1000190|严重|
|org.apache.maven.shared:maven-shared-utils 存在命令注入漏洞|命令注入|[MPS-2022-12562](https://www.oscs1024.com/hd/MPS-2022-12562)||高危|
|H2 数据库明文密码问题|未授权敏感信息泄露|[MPS-2022-65204](https://www.oscs1024.com/hd/MPS-2022-65204)|CVE-2022-45868|高危|
|Apache Maven Shared Utils 系统命令注入漏洞|命令注入|[MPS-2022-9177](https://www.oscs1024.com/hd/MPS-2022-9177)|CVE-2022-29599|严重|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.fasterxml.jackson.core:jackson-databind|2.15.2||间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.yaml:snakeyaml|1.33|2.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.94.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.simpleframework:simple-xml|2.7.1||间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.apache.maven.shared:maven-shared-utils|3.1.0|3.3.3|间接依赖|建议修复|C:1|H:1|M:0|L:0|
|com.h2database:h2|2.1.214||间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.bouncycastle:bcprov-jdk18on|1.73|1.74|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|253|Low|
|BSD-3-Clause|18|Low|
|自定义许可证|25|Low|
|MIT|88|Low|
|EPL-1.0|5|Low|
|EPL-2.0|8|Low|
|MPL-2.0|2|Low|
|GPL-2.0|5|Medium|
|LGPL-2.1|8|Medium|
|CDDL-1.1|2|Low|
|MPL-1.1|1|Low|
|MIT-0|1|Low|
|BSD-2-Clause|3|Low|
|LGPL-2.1-or-later|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.springframework.cloud:spring-cloud-context|4.0.4|间接依赖|maven|
|com.esotericsoftware:minlog|1.3.1|间接依赖|maven|
|org.apache.lucene:lucene-core|8.11.2|间接依赖|maven|
|com.google.auth:google-auth-library-credentials|1.19.0|间接依赖|maven|
|nz.net.ultraq.thymeleaf:thymeleaf-expression-processor|3.1.1|间接依赖|maven|
|org.bouncycastle:bcpkix-jdk18on|1.73|间接依赖|maven|
|com.github.jnr:jffi|1.3.10|间接依赖|maven|
|org.springframework.security:spring-security-config|6.1.2|直接依赖|maven|
|stax:stax-api|1.0.1|间接依赖|maven|
|org.apache.maven:maven-aether-provider|3.0|间接依赖|maven|
|org.webjars:swagger-ui|4.18.2|间接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|2.22.1|间接依赖|maven|
|regexp.prototype.flags|1.5.0|间接依赖|npm|
|io.grpc:grpc-googleapis|1.56.1|间接依赖|maven|
|software.amazon.awssdk:aws-core|2.20.116|间接依赖|maven|
|com.google.re2j:re2j|1.7|间接依赖|maven|
|org.eclipse.aether:aether-util|1.0.0.v20140518|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-vault-config|4.0.1|直接依赖|maven|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|org.ow2.asm:asm-tree|9.2|间接依赖|maven|
|org.apache.maven:maven-settings|3.0|间接依赖|maven|
|bcrypt.dll||间接依赖||
|org.linguafranca.pwdb:KeePassJava2-simple|2.1.4|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|2.8|间接依赖|maven|
|ognl:ognl|3.3.4|间接依赖|maven|
|com.azure:azure-core-management|1.11.2|间接依赖|maven|
|org.apache.commons:commons-dbcp2|2.9.0|间接依赖|maven|
|com.google.http-client:google-http-client-gson|1.43.3|间接依赖|maven|
|is-typed-array|1.1.10|间接依赖|npm|
|io.netty:netty-resolver-dns-classes-macos|4.1.94.Final|间接依赖|maven|
|com.google.auto.value:auto-value-annotations|1.10.2|间接依赖|maven|
|ieee754|1.2.1|间接依赖|npm|
|org.unbescape:unbescape|1.1.6.RELEASE|间接依赖|maven|
|libdl.so.2||间接依赖||
|com.github.jnr:jnr-enxio|0.32.14|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|2.1.1|间接依赖|maven|
|readable-stream|4.4.0|间接依赖|npm|
|com.azure.spring:spring-cloud-azure-autoconfigure|5.3.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-thymeleaf|3.1.2|直接依赖|maven|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|com.google.http-client:google-http-client|1.43.3|间接依赖|maven|
|com.azure.spring:spring-cloud-azure-core|5.3.0|间接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|io.netty:netty-common|4.1.94.Final|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.15.2|间接依赖|maven|
|io.netty:netty-handler|4.1.94.Final|间接依赖|maven|
|org.apache.httpcomponents.client5:httpclient5|5.2.1|间接依赖|maven|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|ADVAPI32.dll||间接依赖||
|com.microsoft.azure:msal4j-persistence-extension|1.2.0|间接依赖|maven|
|github.com/pelletier/go-toml/v2|v2.0.8|间接依赖|go|
|is-string|1.0.7|间接依赖|npm|
|com.fasterxml.jackson.dataformat:jackson-dataformat-xml|2.15.2|间接依赖|maven|
|/usr/lib/libc++.1.dylib||间接依赖||
|USERENV.dll||间接依赖||
|io.netty:netty-tcnative-classes|2.0.61.Final|间接依赖|maven|
|function-bind|1.1.1|间接依赖|npm|
|libpthread.so.0||间接依赖||
|org.linguafranca.pwdb:KeePassJava2-dom|2.1.4|间接依赖|maven|
|io.grpc:grpc-netty-shaded|1.56.1|间接依赖|maven|
|org.jruby:jruby|9.4.2.0|间接依赖|maven|
|org.apache.maven:maven-artifact|3.0|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.16|间接依赖|maven|
|org.codehaus.plexus:plexus-utils|3.5.1|间接依赖|maven|
|is-array-buffer|3.0.2|间接依赖|npm|
|buffer|6.0.3|间接依赖|npm|
|io.swagger.core.v3:swagger-annotations-jakarta|2.2.9|间接依赖|maven|
|org.whitesource:pecoff4j|0.0.2.1|间接依赖|maven|
|io.micrometer:micrometer-commons|1.11.2|间接依赖|maven|
|github.com/spf13/jwalterweatherman|v1.1.0|间接依赖|go|
|org.linguafranca.pwdb:database|2.1.4|间接依赖|maven|
|string.prototype.trimend|1.0.6|间接依赖|npm|
|com.github.spullara.mustache.java:compiler|0.9.6|间接依赖|maven|
|io.micrometer:micrometer-core|1.11.2|间接依赖|maven|
|string.prototype.trimstart|1.0.6|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|org.springframework.boot:spring-boot-actuator|3.1.2|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.14|间接依赖|maven|
|io.micrometer:micrometer-observation|1.11.2|间接依赖|maven|
|software.amazon.awssdk:aws-query-protocol|2.20.116|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|10.1.11|间接依赖|maven|
|libstdc++.so.6||间接依赖||
|org.linguafranca.pwdb:KeePassJava2|2.1.4|直接依赖|maven|
|com.azure:azure-core-amqp|2.8.6|间接依赖|maven|
|software.amazon.awssdk:netty-nio-client|2.20.116|间接依赖|maven|
|org.springframework.security:spring-security-crypto|6.1.2|间接依赖|maven|
|javax.ws.rs:javax.ws.rs-api|2.0.1|间接依赖|maven|
|org.apache.lucene:lucene-sandbox|8.11.2|间接依赖|maven|
|is-bigint|1.0.4|间接依赖|npm|
|io.projectreactor.netty:reactor-netty-http|1.1.9|间接依赖|maven|
|org.springframework.security:spring-security-core|6.1.2|间接依赖|maven|
|com.azure.spring:spring-cloud-azure-service|5.3.0|间接依赖|maven|
|com.google.api:gax-httpjson|2.31.1|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|10.1.11|间接依赖|maven|
|com.google.auth:google-auth-library-oauth2-http|1.19.0|间接依赖|maven|
|org.codehaus.plexus:plexus-classworlds|2.2.3|间接依赖|maven|
|is-number-object|1.0.7|间接依赖|npm|
|org.sonatype.aether:aether-impl|1.7|间接依赖|maven|
|org.eclipse.aether:aether-api|1.0.0.v20140518|间接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.94.Final|间接依赖|maven|
|org.apache.maven:maven-model|3.0|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.15.2|间接依赖|maven|
|com.google.api.grpc:proto-google-cloud-secretmanager-v1beta1|2.22.0|间接依赖|maven|
|com.headius:backport9|1.12|间接依赖|maven|
|io.netty:netty-codec-http|4.1.94.Final|间接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.94.Final|间接依赖|maven|
|is-callable|1.2.7|间接依赖|npm|
|org.springframework.cloud:spring-cloud-starter|4.0.4|间接依赖|maven|
|io.opencensus:opencensus-contrib-http-util|0.31.1|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-afterburner|2.15.2|间接依赖|maven|
|software.amazon.awssdk:apache-client|2.20.116|间接依赖|maven|
|unbox-primitive|1.0.2|间接依赖|npm|
|io.netty:netty-handler-proxy|4.1.94.Final|间接依赖|maven|
|ch.qos.logback:logback-classic|1.4.8|间接依赖|maven|
|org.springframework.security:spring-security-web|6.1.2|直接依赖|maven|
|software.amazon.awssdk:endpoints-spi|2.20.116|间接依赖|maven|
|com.google.guava:guava|32.1.1-jre|间接依赖|maven|
|com.headius:options|1.6|间接依赖|maven|
|org.apache.maven:maven-plugin-api|3.0|间接依赖|maven|
|org.apache.lucene:lucene-queries|8.11.2|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.15.2|间接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.94.Final|间接依赖|maven|
|org.springdoc:springdoc-openapi-starter-common|2.1.0|间接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|org.apache.lucene:lucene-analyzers-common|8.11.2|间接依赖|maven|
|me.qmx.jitescript:jitescript|0.4.1|间接依赖|maven|
|org.apache.maven:maven-model-builder|3.0|间接依赖|maven|
|org.sonatype.ossindex:ossindex-service-api|1.8.2|间接依赖|maven|
|com.azure.spring:spring-cloud-azure-starter-keyvault-secrets|5.3.0|直接依赖|maven|
|org.thymeleaf:thymeleaf|3.1.1.RELEASE|间接依赖|maven|
|org.sonatype.goodies:package-url-java|1.1.1|间接依赖|maven|
|com.nimbusds:lang-tag|1.7|间接依赖|maven|
|com.moandjiezana.toml:toml4j|0.7.2|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator-autoconfigure|3.1.2|间接依赖|maven|
|org.springframework:spring-beans|6.0.11|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|3.1.2|间接依赖|maven|
|org.springframework.cloud:spring-cloud-vault-config|4.0.1|直接依赖|maven|
|github.com/spf13/cast|v1.5.1|间接依赖|go|
|get-intrinsic|1.2.1|间接依赖|npm|
|io.swagger.core.v3:swagger-models-jakarta|2.2.9|间接依赖|maven|
|org.apache.maven:maven-settings-builder|3.0|间接依赖|maven|
|software.amazon.eventstream:eventstream|1.0.1|间接依赖|maven|
|com.github.package-url:packageurl-java|1.4.1|间接依赖|maven|
|com.microsoft.azure:qpid-proton-j-extensions|1.2.4|间接依赖|maven|
|io.opencensus:opencensus-proto|0.2.0|间接依赖|maven|
|org.apache.maven.reporting:maven-reporting-api|3.1.1|间接依赖|maven|
|call-bind|1.0.2|间接依赖|npm|
|org.slf4j:jcl-over-slf4j|2.0.7|间接依赖|maven|
|has-property-descriptors|1.0.0|间接依赖|npm|
|com.azure.spring:spring-cloud-azure-starter|5.3.0|间接依赖|maven|
|github.com/spf13/afero|v1.9.5|间接依赖|go|
|io.netty:netty-codec-socks|4.1.94.Final|间接依赖|maven|
|org.codehaus.plexus:plexus-component-annotations|2.0.0|间接依赖|maven|
|org.sonatype.plexus:plexus-cipher|1.4|间接依赖|maven|
|org.apache.groovy:groovy|4.0.13|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|3.1.2|直接依赖|maven|
|com.jcraft:jzlib|1.1.3|间接依赖|maven|
|com.google.api.grpc:proto-google-iam-v1|1.17.1|间接依赖|maven|
|org.sonatype.sisu:sisu-guice|2.1.7|间接依赖|maven|
|is-symbol|1.0.4|间接依赖|npm|
|org.semver4j:semver4j|4.3.0|间接依赖|maven|
|org.sonatype.sisu:sisu-inject-bean|1.4.2|间接依赖|maven|
|event-target-shim|5.0.1|间接依赖|npm|
|org.apache.maven:maven-repository-metadata|3.0|间接依赖|maven|
|org.codehaus.plexus:plexus-interpolation|1.14|间接依赖|maven|
|KERNEL32.dll||间接依赖||
|org.codehaus.mojo:animal-sniffer-annotations|1.23|间接依赖|maven|
|golang.org/x/text|v0.9.0|间接依赖|go|
|com.hankcs:aho-corasick-double-array-trie|1.2.3|间接依赖|maven|
|org.apache.lucene:lucene-queryparser|8.11.2|间接依赖|maven|
|org.springframework:spring-web|6.0.11|间接依赖|maven|
|com.networknt:json-schema-validator|1.0.77|间接依赖|maven|
|org.asciidoctor:asciidoctorj-api|2.5.10|直接依赖|maven|
|io.projectreactor.netty:reactor-netty-core|1.1.9|间接依赖|maven|
|org.ow2.asm:asm-commons|9.2|间接依赖|maven|
|org.springframework:spring-jcl|6.0.11|间接依赖|maven|
|io.grpc:grpc-grpclb|1.56.1|间接依赖|maven|
|org.anarres.jdiagnostics:jdiagnostics|1.0.7|间接依赖|maven|
|software.amazon.awssdk:annotations|2.20.116|间接依赖|maven|
|org.owasp:dependency-check-utils|8.2.1|间接依赖|maven|
|io.grpc:grpc-services|1.56.1|间接依赖|maven|
|com.headius:invokebinder|1.12|间接依赖|maven|
|internal-slot|1.0.5|间接依赖|npm|
|side-channel|1.0.4|间接依赖|npm|
|commons-beanutils:commons-beanutils|1.9.4|间接依赖|maven|
|org.apache.maven.shared:maven-dependency-tree|3.2.1|间接依赖|maven|
|org.simpleframework:simple-xml|2.7.1|间接依赖|maven|
|org.javassist:javassist|3.29.0-GA|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.94.Final|间接依赖|maven|
|com.h2database:h2|2.1.214|间接依赖|maven|
|org.linguafranca.pwdb:KeePassJava2-kdbx|2.1.4|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.15.2|间接依赖|maven|
|base64-js|1.5.1|间接依赖|npm|
|available-typed-arrays|1.0.5|间接依赖|npm|
|com.google.protobuf:protobuf-java|3.23.2|间接依赖|maven|
|function.prototype.name|1.1.5|间接依赖|npm|
|software.amazon.awssdk:sts|2.20.116|直接依赖|maven|
|org.sonatype.aether:aether-api|1.7|间接依赖|maven|
|nz.net.ultraq.groovy:groovy-extensions|2.1.0|间接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5|5.2.2|间接依赖|maven|
|abort-controller|3.0.0|间接依赖|npm|
|commons-validator:commons-validator|1.7|间接依赖|maven|
|com.github.jnr:jnr-ffi|2.2.13|间接依赖|maven|
|nz.net.ultraq.thymeleaf:thymeleaf-layout-dialect|3.2.1|直接依赖|maven|
|com.azure:azure-json|1.0.1|间接依赖|maven|
|com.google.protobuf:protobuf-java-util|3.23.2|间接依赖|maven|
|librt.so.1||间接依赖||
|io.netty:netty-buffer|4.1.94.Final|间接依赖|maven|
|has-symbols|1.0.3|间接依赖|npm|
|for-each|0.3.3|间接依赖|npm|
|software.amazon.awssdk:http-client-spi|2.20.116|间接依赖|maven|
|msvcrt.dll||间接依赖||
|org.springframework.boot:spring-boot-starter-actuator|3.1.2|直接依赖|maven|
|is-weakref|1.0.2|间接依赖|npm|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|org.jruby:jruby-base|9.4.2.0|间接依赖|maven|
|org.jruby:jruby-stdlib|9.4.2.0|间接依赖|maven|
|io.grpc:grpc-stub|1.56.1|间接依赖|maven|
|github.com/subosito/gotenv|v1.4.2|间接依赖|go|
|io.grpc:grpc-alts|1.56.1|间接依赖|maven|
|com.azure:azure-identity|1.9.1|间接依赖|maven|
|safe-regex-test|1.0.0|间接依赖|npm|
|com.microsoft.azure:msal4j|1.13.8|间接依赖|maven|
|com.github.jnr:jnr-netdb|1.2.0|间接依赖|maven|
|org.linguafranca.pwdb:KeePassJava2-jaxb|2.1.4|间接依赖|maven|
|org.apache.maven.doxia:doxia-logging-api|1.11.1|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|10.1.11|间接依赖|maven|
|is-shared-array-buffer|1.0.2|间接依赖|npm|
|org.bouncycastle:bcutil-jdk18on|1.73|间接依赖|maven|
|org.slf4j:slf4j-api|2.0.7|间接依赖|maven|
|org.webjars.npm:github-buttons|2.14.1|直接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.94.Final|间接依赖|maven|
|org.sonatype.ossindex:ossindex-service-client|1.8.2|间接依赖|maven|
|org.jruby:dirgra|0.3|间接依赖|maven|
|org.codehaus.woodstox:stax2-api|4.2.1|间接依赖|maven|
|has-tostringtag|1.0.0|间接依赖|npm|
|org.glassfish:javax.json|1.1.4|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-blackbird|2.15.2|间接依赖|maven|
|com.google.api.grpc:proto-google-cloud-secretmanager-v1|2.22.0|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|io.opencensus:opencensus-api|0.31.1|间接依赖|maven|
|org.apache.commons:commons-collections4|4.4|间接依赖|maven|
|org.jetbrains:annotations|15.0|间接依赖|maven|
|org.asciidoctor:asciidoctorj|2.5.10|直接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|com.github.jnr:jnr-posix|3.1.16|间接依赖|maven|
|com.ethlo.time:itu|1.7.0|间接依赖|maven|
|com.github.jnr:jnr-unixsocket|0.38.19|间接依赖|maven|
|io.grpc:grpc-context|1.56.1|间接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|6.5.1|间接依赖|maven|
|github.com/spf13/cobra|v1.7.0|间接依赖|go|
|software.amazon.awssdk:ssm|2.20.116|直接依赖|maven|
|io.swagger.core.v3:swagger-core-jakarta|2.2.9|间接依赖|maven|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|org.apache.commons:commons-jcs-core|2.2.1|间接依赖|maven|
|github.com/fsnotify/fsnotify|v1.6.0|间接依赖|go|
|com.beust:jcommander|1.82|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.20.0|间接依赖|maven|
|es-to-primitive|1.2.1|间接依赖|npm|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.15.2|间接依赖|maven|
|is-boolean-object|1.1.2|间接依赖|npm|
|stax:stax|1.2.0|间接依赖|maven|
|events|3.3.0|间接依赖|npm|
|github.com/magiconair/properties|v1.8.7|间接依赖|go|
|org.bouncycastle:bcprov-jdk18on|1.73|间接依赖|maven|
|org.eclipse.packager:packager-rpm|0.19.0|间接依赖|maven|
|org.eclipse.packager:packager-core|0.19.0|间接依赖|maven|
|com.google.code.gson:gson|2.10.1|间接依赖|maven|
|com.github.stephenc.jcip:jcip-annotations|1.0-1|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.15.2|间接依赖|maven|
|org.apache.velocity:velocity-engine-core|2.3|间接依赖|maven|
|org.webjars:jquery|3.7.0|直接依赖|maven|
|joda-time:joda-time|2.10.10|间接依赖|maven|
|array-buffer-byte-length|1.0.0|间接依赖|npm|
|org.sonatype.aether:aether-util|1.7|间接依赖|maven|
|gopd|1.0.1|间接依赖|npm|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5-h2|5.2.2|间接依赖|maven|
|io.grpc:grpc-xds|1.56.1|间接依赖|maven|
|software.amazon.awssdk:auth|2.20.116|间接依赖|maven|
|libc.so.6||间接依赖||
|jakarta.validation:jakarta.validation-api|3.0.2|间接依赖|maven|
|commons-digester:commons-digester|2.1|间接依赖|maven|
|string.prototype.replaceall|1.0.7|间接依赖|npm|
|com.nimbusds:oauth2-oidc-sdk|10.7.1|间接依赖|maven|
|org.springframework.security:spring-security-rsa|1.0.12.RELEASE|间接依赖|maven|
|functions-have-names|1.2.3|间接依赖|npm|
|io.projectreactor:reactor-core|3.5.8|间接依赖|maven|
|org.springdoc:springdoc-openapi-starter-webmvc-ui|2.1.0|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.18.0|间接依赖|maven|
|org.apache.commons:commons-compress|1.23.0|间接依赖|maven|
|org.threeten:threetenbp|1.6.8|间接依赖|maven|
|us.springett:cpe-parser|2.0.2|间接依赖|maven|
|test|3.3.0|间接依赖|npm|
|string.prototype.trim|1.2.7|间接依赖|npm|
|org.thymeleaf.extras:thymeleaf-extras-springsecurity6|3.1.2.RELEASE|直接依赖|maven|
|org.springframework:spring-core|6.0.11|间接依赖|maven|
|object-keys|1.1.1|间接依赖|npm|
|org.bouncycastle:bcpg-jdk18on|1.71|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|间接依赖|maven|
|io.grpc:grpc-api|1.56.1|间接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|github.com/mitchellh/mapstructure|v1.5.0|间接依赖|go|
|com.fasterxml:aalto-xml|1.0.0|间接依赖|maven|
|software.amazon.awssdk:aws-json-protocol|2.20.116|间接依赖|maven|
|io.grpc:grpc-core|1.56.1|间接依赖|maven|
|software.amazon.awssdk:metrics-spi|2.20.116|间接依赖|maven|
|com.nimbusds:content-type|2.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|3.1.2|直接依赖|maven|
|org.ow2.asm:asm-analysis|9.2|间接依赖|maven|
|org.thymeleaf:thymeleaf-spring6|3.1.1.RELEASE|间接依赖|maven|
|ld-linux-x86-64.so.2||间接依赖||
|typed-array-length|1.0.4|间接依赖|npm|
|com.h3xstream.retirejs:retirejs-core|3.0.4|间接依赖|maven|
|org.jsoup:jsoup|1.15.4|间接依赖|maven|
|org.springframework.cloud:spring-cloud-commons|4.0.4|间接依赖|maven|
|process|0.11.10|间接依赖|npm|
|org.ow2.asm:asm-util|9.2|间接依赖|maven|
|org.ow2.asm:asm|9.2|间接依赖|maven|
|software.amazon.awssdk:regions|2.20.116|间接依赖|maven|
|globalthis|1.0.3|间接依赖|npm|
|ch.qos.logback:logback-core|1.4.8|间接依赖|maven|
|org.springframework.vault:spring-vault-core|3.0.2|间接依赖|maven|
|org.apache.maven.shared:maven-artifact-transfer|0.13.1|间接依赖|maven|
|software.amazon.awssdk:utils|2.20.116|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|io.netty:netty-codec|4.1.94.Final|间接依赖|maven|
|es-abstract|1.21.2|间接依赖|npm|
|org.slf4j:jul-to-slf4j|2.0.7|间接依赖|maven|
|org.springframework:spring-aop|6.0.11|间接依赖|maven|
|org.owasp:dependency-check-core|8.2.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.15.2|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|org.apache.commons:commons-pool2|2.11.1|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|间接依赖|maven|
|org.sonatype.sisu:sisu-inject-plexus|1.4.2|间接依赖|maven|
|is-date-object|1.0.5|间接依赖|npm|
|com.google.api:api-common|2.14.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|3.1.2|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.94.Final|间接依赖|maven|
|is-regex|1.1.4|间接依赖|npm|
|org.conscrypt:conscrypt-openjdk-uber|2.5.2|间接依赖|maven|
|org.apache.maven.shared:maven-shared-utils|3.1.0|间接依赖|maven|
|org.webjars:datatables|1.13.5|直接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.56.1|间接依赖|maven|
|com.github.jnr:jnr-x86asm|1.0.2|间接依赖|maven|
|get-symbol-description|1.0.0|间接依赖|npm|
|software.amazon.awssdk:third-party-jackson-core|2.20.116|间接依赖|maven|
|org.apache.commons:commons-text|1.10.0|间接依赖|maven|
|WS2_32.dll||间接依赖||
|org.checkerframework:checker-qual|3.33.0|间接依赖|maven|
|org.linguafranca.pwdb:KeePassJava2-kdb|2.1.4|间接依赖|maven|
|org.apache.qpid:proton-j|0.33.8|间接依赖|maven|
|net.java.dev.jna:jna|5.13.0|间接依赖|maven|
|org.springframework:spring-expression|6.0.11|间接依赖|maven|
|org.springdoc:springdoc-openapi-starter-webmvc-api|2.1.0|间接依赖|maven|
|com.github.jnr:jnr-constants|0.10.4|间接依赖|maven|
|libc.so||间接依赖||
|io.perfmark:perfmark-api|0.26.0|间接依赖|maven|
|which-typed-array|1.1.9|间接依赖|npm|
|org.springframework:spring-context|6.0.11|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.20.0|间接依赖|maven|
|software.amazon.awssdk:json-utils|2.20.116|间接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|9.30.2|间接依赖|maven|
|com.google.cloud:google-cloud-secretmanager|2.22.0|直接依赖|maven|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|gopkg.in/ini.v1|v1.67.0|间接依赖|go|
|org.jruby.jcodings:jcodings|1.0.58|间接依赖|maven|
|io.netty:netty-resolver|4.1.94.Final|间接依赖|maven|
|xpp3:xpp3|1.1.3.3|间接依赖|maven|
|/usr/lib/libSystem.B.dylib||间接依赖||
|software.amazon.awssdk:protocol-core|2.20.116|间接依赖|maven|
|com.azure:azure-security-keyvault-secrets|4.6.3|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.94.Final|间接依赖|maven|
|io.grpc:grpc-protobuf|1.56.1|间接依赖|maven|
|com.google.api:gax|2.31.1|间接依赖|maven|
|es-set-tostringtag|2.0.1|间接依赖|npm|
|com.github.jnr:jnr-a64asm|1.0.0|间接依赖|maven|
|net.java.dev.jna:jna-platform|5.6.0|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.94.Final|间接依赖|maven|
|org.apache.maven.shared:file-management|3.1.0|间接依赖|maven|
|org.yaml:snakeyaml|1.33|间接依赖|maven|
|org.sonatype.plexus:plexus-sec-dispatcher|1.4|间接依赖|maven|
|com.azure:azure-core-http-netty|1.13.4|间接依赖|maven|
|com.azure:azure-core|1.40.0|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.94.Final|间接依赖|maven|
|libgcc_s.so.1||间接依赖||
|org.webjars:bootstrap|5.3.1|直接依赖|maven|
|org.attoparser:attoparser|2.0.6.RELEASE|间接依赖|maven|
|org.sonatype.aether:aether-spi|1.7|间接依赖|maven|
|com.google.api:gax-grpc|2.31.1|间接依赖|maven|
|org.apache.maven:maven-core|3.0|间接依赖|maven|
|org.jruby.joni:joni|2.1.48|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|3.1.2|间接依赖|maven|
|org.apache.maven.shared:maven-common-artifact-filters|3.1.0|间接依赖|maven|
|com.github.spotbugs:spotbugs-annotations|4.7.3|直接依赖|maven|
|org.tukaani:xz|1.9|间接依赖|maven|
|com.madgag.spongycastle:core|1.54.0.0|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|minimist|1.2.8|间接依赖|npm|
|object.assign|4.1.4|间接依赖|npm|
|org.springframework.boot:spring-boot-starter-logging|3.1.2|间接依赖|maven|
|org.jruby:jruby-complete|9.4.3.0|直接依赖|maven|
|github.com/spf13/viper|v1.16.0|间接依赖|go|
|software.amazon.awssdk:sdk-core|2.20.116|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|org.springframework:spring-webmvc|6.0.11|间接依赖|maven|
|define-properties|1.2.0|间接依赖|npm|
|which-boxed-primitive|1.0.2|间接依赖|npm|
|object-inspect|1.12.3|间接依赖|npm|
|software.amazon.awssdk:profiles|2.20.116|间接依赖|maven|
|org.owasp:dependency-check-maven|8.2.1|直接依赖|maven|
|io.netty:netty-transport|4.1.94.Final|间接依赖|maven|
|org.apache.maven.doxia:doxia-sink-api|1.11.1|间接依赖|maven|
|commons-io:commons-io|2.11.0|间接依赖|maven|
|is-negative-zero|2.0.2|间接依赖|npm|
|golang.org/x/sys|v0.8.0|间接依赖|go|
|org.springframework.boot:spring-boot|3.1.2|间接依赖|maven|
|has-bigints|1.0.2|间接依赖|npm|
|org.cyclonedx:cyclonedx-core-java|7.3.2|直接依赖|maven|
|io.grpc:grpc-auth|1.56.1|间接依赖|maven|
|io.netty:netty-tcnative-boringssl-static|2.0.61.Final|间接依赖|maven|
|has-proto|1.0.1|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)