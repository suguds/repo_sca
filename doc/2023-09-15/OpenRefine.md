# OpenRefine/OpenRefine安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1702382111235375104.svg)](https://www.murphysec.com/console/report/1702382111197626368/1702382111235375104)

仓库描述：OpenRefine is a free, open source power tool for working with messy data and improving it

仓库地址：[https://github.com/OpenRefine/OpenRefine](https://github.com/OpenRefine/OpenRefine)

| star：9666 | watch：474 | fork：1858 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-14 17:09:52 | 许可证：BSD-3-Clause |
| 最近检测时间：2023-09-15 02:05:49 | 组件总数：401 | 漏洞总数：12 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Http-signature 安全漏洞|密码学签名的验证不恰当|[MPS-2018-6996](https://www.oscs1024.com/hd/MPS-2018-6996)|CVE-2017-16005|高危|
|colors.js  >1.4.0 DOS漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-19606](https://www.oscs1024.com/hd/MPS-2021-19606)|CVE-2021-23567|高危|
|Apache Velocity 存在任意代码执行|代码注入|[MPS-2021-3061](https://www.oscs1024.com/hd/MPS-2021-3061)|CVE-2020-13936|高危|
|Eclipse Jetty URI注入漏洞|注入|[MPS-2022-18060](https://www.oscs1024.com/hd/MPS-2022-18060)|CVE-2022-2047|低危|
|Apache XercesJ <=2.12.1 存在XML注入漏洞|XPath盲注|[MPS-2022-1864](https://www.oscs1024.com/hd/MPS-2022-1864)|CVE-2022-23437|中危|
|protobuf-java 存在输入验证不当漏洞|拒绝服务|[MPS-2022-56472](https://www.oscs1024.com/hd/MPS-2022-56472)|CVE-2022-3171|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|Google protobuf 安全漏洞|拒绝服务|[MPS-2022-59814](https://www.oscs1024.com/hd/MPS-2022-59814)|CVE-2022-3510|高危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.squareup.okio:okio|3.2.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.velocity:velocity|1.6.3||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|http-signature|1.3.6||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.4|2.14.0-rc1|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.squareup.okio:okio-jvm|3.2.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|colors|1.4.0||直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-http|9.4.52.v20230823|11.0.10|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|com.google.protobuf:protobuf-java|3.19.4|3.21.7|间接依赖|可选修复|C:0|H:1|M:2|L:0|
|com.google.guava:guava|31.1-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|xerces:xercesImpl|2.12.1|2.12.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|207|Low|
|Apache-2.0|103|Low|
|BSD-2-Clause|8|Low|
|ISC|20|Low|
|BSD-3-Clause|12|Low|
|MPL-1.1|1|Low|
|EPL-2.0|11|Low|
|自定义许可证|10|Low|
|Python-2.0|1|Low|
|Apache 2.0|1|Low|
|LGPL-2.1|3|Medium|
|CDDL-1.1|1|Low|
|0BSD|1|Low|
|Unlicense|1|Low|
|EPL-1.0|3|Low|
|MPL-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|has|1.0.3|间接依赖|npm|
|onetime|5.1.2|间接依赖|npm|
|com.google.http-client:google-http-client-apache-v2|1.42.3|间接依赖|maven|
|sshpk|1.16.1|间接依赖|npm|
|se.akerfeldt:okhttp-signpost|1.1.0|间接依赖|maven|
|aws-sign2|0.7.0|间接依赖|npm|
|minimist|1.2.8|间接依赖|npm|
|com.google.code.gson:gson|2.10.1|间接依赖|maven|
|esutils|2.0.3|间接依赖|npm|
|com.google.apis:google-api-services-sheets|v4-rev20230815-2.0.0|直接依赖|maven|
|cli-table3|0.6.1|间接依赖|npm|
|com.google.guava:guava|31.1-jre|直接依赖|maven|
|org.apache.commons:commons-math3|3.6.1|间接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5|5.2|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|aggregate-error|3.1.0|间接依赖|npm|
|org.wikidata.wdtk:wdtk-util|0.14.6|直接依赖|maven|
|aws4|1.10.1|间接依赖|npm|
|jquery-migrate|3.4.1|直接依赖|npm|
|eslint-config-prettier|9.0.0|直接依赖|npm|
|org.apache.jena:jena-shaded-guava|4.8.0|间接依赖|maven|
|jsprim|2.0.2|间接依赖|npm|
|asn1|0.2.4|间接依赖|npm|
|wrap-ansi|6.2.0|间接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|untildify|4.0.0|间接依赖|npm|
|resolve-from|4.0.0|间接依赖|npm|
|ecc-jsbn|0.1.2|间接依赖|npm|
|universalify|1.0.0|间接依赖|npm|
|ini|2.0.0|间接依赖|npm|
|yocto-queue|0.1.0|间接依赖|npm|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|type-fest|0.20.2|间接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|org.apache.httpcomponents:httpclient|4.5.14|间接依赖|maven|
|process|0.11.10|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|commons-compress:commons-compress|20050911|间接依赖|maven|
|string-width|4.2.2|间接依赖|npm|
|com.squareup.okio:okio|3.2.0|间接依赖|maven|
|bcrypt-pbkdf|1.0.2|间接依赖|npm|
|strip-ansi|6.0.1|间接依赖|npm|
|@types/sizzle|2.3.2|间接依赖|npm|
|com.zaxxer:SparseBitSet|1.2|间接依赖|maven|
|io.opencensus:opencensus-contrib-http-util|0.31.1|间接依赖|maven|
|request-progress|3.0.0|间接依赖|npm|
|de.fau.cs.osr.utils:utils|3.0.8|间接依赖|maven|
|org.jsoup:jsoup|1.15.3|直接依赖|maven|
|has-proto|1.0.1|间接依赖|npm|
|ajv|6.12.6|间接依赖|npm|
|has-flag|4.0.0|间接依赖|npm|
|graceful-fs|4.2.6|直接依赖|npm|
|end-of-stream|1.4.4|间接依赖|npm|
|org.apache.velocity:velocity|1.6.3|间接依赖|maven|
|flatted|3.1.1|间接依赖|npm|
|levn|0.4.1|间接依赖|npm|
|get-intrinsic|1.2.1|间接依赖|npm|
|cross-spawn|7.0.3|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|com.github.albfernandez:juniversalchardet|2.4.0|直接依赖|maven|
|org.checkerframework:checker-qual|3.12.0|间接依赖|maven|
|@nodelib/fs.scandir|2.1.5|间接依赖|npm|
|io.grpc:grpc-context|1.27.2|间接依赖|maven|
|org.apache.httpcomponents.client5:httpclient5|5.2.1|直接依赖|maven|
|universalify|2.0.0|间接依赖|npm|
|org.apache.jena:jena-arq|4.8.0|直接依赖|maven|
|org.wikidata.wdtk:wdtk-wikibaseapi|0.14.6|直接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.52.v20230823|间接依赖|maven|
|ansi-escapes|4.3.2|间接依赖|npm|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.6.10|间接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5-h2|5.2|间接依赖|maven|
|@eslint/eslintrc|2.1.2|间接依赖|npm|
|com.google.errorprone:error_prone_annotations|2.11.0|间接依赖|maven|
|jsbn|0.1.1|间接依赖|npm|
|javax.servlet:javax.servlet-api|4.0.1|直接依赖|maven|
|org.openrefine.dependencies:butterfly|1.2.4|直接依赖|maven|
|get-stream|5.2.0|间接依赖|npm|
|org.openrefine.dependencies:vicino|1.2|直接依赖|maven|
|fast-deep-equal|3.1.3|间接依赖|npm|
|de.fau.cs.osr.ptk:ptk-common|3.0.8|间接依赖|maven|
|restore-cursor|3.1.0|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|getos|3.2.1|间接依赖|npm|
|commons-validator:commons-validator|1.7|直接依赖|maven|
|@aashutoshrathi/word-wrap|1.2.6|间接依赖|npm|
|run-parallel|1.2.0|间接依赖|npm|
|is-glob|4.0.3|间接依赖|npm|
|js-yaml|4.1.0|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|argparse|2.0.1|间接依赖|npm|
|datejs-coolite|1.0.0|直接依赖|npm|
|json-stable-stringify-without-jsonify|1.0.1|间接依赖|npm|
|ci-info|3.1.1|间接依赖|npm|
|eslint-plugin-cypress|2.14.0|直接依赖|npm|
|graphemer|1.4.0|间接依赖|npm|
|org.mariadb.jdbc:mariadb-java-client|3.0.8|直接依赖|maven|
|glob-parent|6.0.2|间接依赖|npm|
|org.apache.xmlbeans:xmlbeans|5.1.1|间接依赖|maven|
|asynckit|0.4.0|间接依赖|npm|
|side-channel|1.0.4|间接依赖|npm|
|tunnel-agent|0.6.0|间接依赖|npm|
|commons-io:commons-io|2.13.0|直接依赖|maven|
|org.apache.commons:commons-lang3|3.13.0|直接依赖|maven|
|core-util-is|1.0.2|间接依赖|npm|
|jquery|3.7.1|间接依赖|npm|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j2-impl|2.20.0|直接依赖|maven|
|acorn|8.9.0|间接依赖|npm|
|org.apache.jena:jena-core|4.8.0|直接依赖|maven|
|lodash.once|4.1.1|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|com.squareup.okhttp3:okhttp-urlconnection|4.10.0|直接依赖|maven|
|pump|3.0.0|间接依赖|npm|
|colorette|1.2.2|间接依赖|npm|
|javax.xml.bind:jaxb-api|2.3.1|直接依赖|maven|
|emoji-regex|8.0.0|间接依赖|npm|
|buffer|5.7.1|间接依赖|npm|
|com.google.oauth-client:google-oauth-client|1.34.1|间接依赖|maven|
|js-cookie|3.0.5|直接依赖|npm|
|blob-util|2.0.2|间接依赖|npm|
|ospath|1.2.2|间接依赖|npm|
|globals|13.20.0|间接依赖|npm|
|lodash.merge|4.6.2|间接依赖|npm|
|buffer-crc32|0.2.13|间接依赖|npm|
|combined-stream|1.0.8|间接依赖|npm|
|org.eclipse.jetty:jetty-server|9.4.52.v20230823|直接依赖|maven|
|org.eclipse.jetty:jetty-xml|9.4.52.v20230823|间接依赖|maven|
|check-more-types|2.24.0|间接依赖|npm|
|org.eclipse.jetty:jetty-webapp|9.4.52.v20230823|直接依赖|maven|
|rimraf|3.0.2|间接依赖|npm|
|org.apache.poi:poi|5.2.3|直接依赖|maven|
|wrappy|1.0.2|间接依赖|npm|
|lru-cache|6.0.0|间接依赖|npm|
|xtc:rats-runtime|1.15.0|间接依赖|maven|
|tslib|1.13.0|间接依赖|npm|
|ansi-styles|4.3.0|间接依赖|npm|
|oauth.signpost:signpost-core|1.2.1.2|间接依赖|maven|
|file-entry-cache|6.0.1|间接依赖|npm|
|type-fest|0.21.3|间接依赖|npm|
|log-update|4.0.0|间接依赖|npm|
|imurmurhash|0.1.4|间接依赖|npm|
|io.opencensus:opencensus-api|0.31.1|间接依赖|maven|
|pend|1.2.0|间接依赖|npm|
|colors|1.4.0|直接依赖|npm|
|org.slf4j:slf4j-api|2.0.9|直接依赖|maven|
|net.sf.jopt-simple:jopt-simple|5.0.4|间接依赖|maven|
|log-symbols|4.0.0|间接依赖|npm|
|cypress|13.2.0|直接依赖|npm|
|org.wikidata.wdtk:wdtk-datamodel|0.14.6|直接依赖|maven|
|reusify|1.0.4|间接依赖|npm|
|locate-path|6.0.0|间接依赖|npm|
|commons-cli:commons-cli|1.5.0|间接依赖|maven|
|com.squareup.okhttp3:okhttp|4.11.0|间接依赖|maven|
|com.squareup.okio:okio-jvm|3.2.0|间接依赖|maven|
|org.python:jython-standalone|2.7.3|直接依赖|maven|
|executable|4.1.1|间接依赖|npm|
|safe-buffer|5.2.1|间接依赖|npm|
|wrap-ansi|7.0.0|间接依赖|npm|
|signal-exit|3.0.3|间接依赖|npm|
|call-bind|1.0.2|间接依赖|npm|
|execa|4.1.0|间接依赖|npm|
|json-stringify-safe|5.0.1|间接依赖|npm|
|tweetnacl|0.14.5|间接依赖|npm|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|org.apache.commons:commons-collections4|4.4|间接依赖|maven|
|ansi-colors|4.1.1|间接依赖|npm|
|tablesorter|2.31.3|直接依赖|npm|
|bluebird|3.7.2|间接依赖|npm|
|color-convert|2.0.1|间接依赖|npm|
|org.checkerframework:checker-qual|3.5.0|间接依赖|maven|
|is-stream|2.0.0|间接依赖|npm|
|com.google.protobuf:protobuf-java|3.19.4|间接依赖|maven|
|supports-color|7.2.0|间接依赖|npm|
|http-signature|1.3.6|间接依赖|npm|
|org.eclipse.jetty:jetty-continuation|9.4.52.v20230823|间接依赖|maven|
|select2|4.1.0-rc.0|直接依赖|npm|
|org.apache.poi:poi-ooxml|5.2.3|直接依赖|maven|
|mime-types|2.1.27|间接依赖|npm|
|org.apache.httpcomponents:httpclient-cache|4.5.14|间接依赖|maven|
|p-map|4.0.0|间接依赖|npm|
|chalk|4.1.0|间接依赖|npm|
|mimic-fn|2.1.0|间接依赖|npm|
|@types/yauzl|2.9.1|直接依赖|npm|
|throttleit|1.0.0|间接依赖|npm|
|com.google.apis:google-api-services-drive|v3-rev20230822-2.0.0|直接依赖|maven|
|org.threeten:threeten-extra|1.7.2|间接依赖|maven|
|doctrine|3.0.0|间接依赖|npm|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|parent-module|1.0.1|间接依赖|npm|
|through|2.3.8|间接依赖|npm|
|forever-agent|0.6.1|间接依赖|npm|
|optionator|0.9.3|间接依赖|npm|
|org.jetbrains.kotlin:kotlin-stdlib|1.6.20|间接依赖|maven|
|@humanwhocodes/object-schema|1.2.1|间接依赖|npm|
|SHELL32.dll||间接依赖||
|com.fasterxml.jackson.core:jackson-annotations|2.13.4|直接依赖|maven|
|strip-final-newline|2.0.0|间接依赖|npm|
|velocity:velocity|1.5|直接依赖|maven|
|com.apicatalog:titanium-json-ld|1.3.2|间接依赖|maven|
|cachedir|2.3.0|间接依赖|npm|
|uri-js|4.4.0|间接依赖|npm|
|caseless|0.12.0|间接依赖|npm|
|object-inspect|1.12.3|间接依赖|npm|
|org.apache.httpcomponents:httpcore|4.4.16|直接依赖|maven|
|com.google.http-client:google-http-client-jackson2|1.42.2|直接依赖|maven|
|net.rootdev:java-rdfa|0.4.2|间接依赖|maven|
|glob|7.1.6|间接依赖|npm|
|eslint-visitor-keys|3.4.3|间接依赖|npm|
|moment|2.29.4|直接依赖|npm|
|@types/sinonjs__fake-timers|8.1.1|间接依赖|npm|
|org.apache.poi:poi-ooxml-lite|5.2.3|间接依赖|maven|
|espree|9.6.1|间接依赖|npm|
|com.google.http-client:google-http-client|1.42.3|间接依赖|maven|
|com.google.http-client:google-http-client-gson|1.42.3|间接依赖|maven|
|delayed-stream|1.0.0|间接依赖|npm|
|extend|3.0.2|间接依赖|npm|
|eventemitter2|6.4.7|间接依赖|npm|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|estraverse|5.2.0|间接依赖|npm|
|org.eclipse.jetty:jetty-security|9.4.52.v20230823|间接依赖|maven|
|querystringify|2.2.0|间接依赖|npm|
|indent-string|4.0.0|间接依赖|npm|
|queue-microtask|1.2.3|间接依赖|npm|
|org.clojure:spec.alpha|0.3.218|间接依赖|maven|
|org.openjdk.jmh:jmh-core|1.37|直接依赖|maven|
|tough-cookie|4.1.3|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|@eslint/js|8.49.0|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|form-data|2.3.3|间接依赖|npm|
|underscore|1.13.6|直接依赖|npm|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.6.10|间接依赖|maven|
|extsprintf|1.3.0|间接依赖|npm|
|esrecurse|4.3.0|间接依赖|npm|
|is-ci|3.0.0|间接依赖|npm|
|yauzl|2.10.0|间接依赖|npm|
|eslint-scope|7.2.2|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|commons-digester:commons-digester|2.1|间接依赖|maven|
|npm-run-path|4.0.1|间接依赖|npm|
|org.postgresql:postgresql|42.5.1|直接依赖|maven|
|mime-db|1.44.0|间接依赖|npm|
|org.apache.logging.log4j:log4j-core|2.20.0|直接依赖|maven|
|clean-stack|2.2.0|间接依赖|npm|
|@humanwhocodes/config-array|0.11.11|间接依赖|npm|
|com.optimaize.languagedetector:language-detector|0.6|直接依赖|maven|
|@wikimedia/jquery.i18n|1.0.9|直接依赖|npm|
|universalify|0.2.0|间接依赖|npm|
|org.eclipse.jetty:jetty-util-ajax|9.4.52.v20230823|间接依赖|maven|
|inflight|1.0.6|间接依赖|npm|
|org.clojure:clojure|1.11.1|直接依赖|maven|
|deep-is|0.1.3|间接依赖|npm|
|async|3.2.3|间接依赖|npm|
|color-name|1.1.4|间接依赖|npm|
|assert-plus|1.0.0|间接依赖|npm|
|@cypress/xvfb|1.2.4|间接依赖|npm|
|figures|3.2.0|间接依赖|npm|
|requires-port|1.0.0|间接依赖|npm|
|mysql:mysql-connector-java|8.0.30|直接依赖|maven|
|uuid|8.3.2|间接依赖|npm|
|slice-ansi|3.0.0|间接依赖|npm|
|com.fasterxml.jackson.core:jackson-core|2.13.4|直接依赖|maven|
|org.apache.logging.log4j:log4j-1.2-api|2.20.0|直接依赖|maven|
|rxjs|6.6.7|间接依赖|npm|
|debug|4.3.4|间接依赖|npm|
|cli-cursor|3.1.0|间接依赖|npm|
|cli-truncate|2.1.0|间接依赖|npm|
|qs|6.10.5|间接依赖|npm|
|proxy-from-env|1.0.0|间接依赖|npm|
|org.apache.thrift:libthrift|0.18.1|间接依赖|maven|
|com.metaweb:lessen|1.0|间接依赖|maven|
|org.mozilla:rhino|1.7.14|间接依赖|maven|
|escape-string-regexp|4.0.0|间接依赖|npm|
|pretty-bytes|5.6.0|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|lazy-ass|1.6.0|间接依赖|npm|
|org.apache.jena:jena-iri|4.8.0|间接依赖|maven|
|path-exists|4.0.0|间接依赖|npm|
|com.github.jsonld-java:jsonld-java|0.13.4|间接依赖|maven|
|org.glassfish:jakarta.json|2.0.1|间接依赖|maven|
|human-signals|1.1.1|间接依赖|npm|
|extsprintf|1.4.0|间接依赖|npm|
|com.fasterxml.jackson.core:jackson-databind|2.13.4|直接依赖|maven|
|com.google.api-client:google-api-client|2.2.0|间接依赖|maven|
|pify|2.3.0|间接依赖|npm|
|tmp|0.2.1|间接依赖|npm|
|yallist|4.0.0|间接依赖|npm|
|jsonfile|6.0.1|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|astral-regex|2.0.0|间接依赖|npm|
|com.github.andrewoma.dexx:collection|0.7|间接依赖|maven|
|string-width|4.2.0|间接依赖|npm|
|arch|2.2.0|间接依赖|npm|
|@eslint-community/regexpp|4.6.2|间接依赖|npm|
|org.apache.commons:commons-csv|1.10.0|间接依赖|maven|
|common-tags|1.8.0|间接依赖|npm|
|com.google.protobuf:protobuf-java|3.22.2|间接依赖|maven|
|prelude-ls|1.2.1|间接依赖|npm|
|base64-js|1.5.1|间接依赖|npm|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.15.2|间接依赖|maven|
|prettier|3.0.3|直接依赖|npm|
|ignore|5.2.0|间接依赖|npm|
|strip-json-comments|3.1.1|间接依赖|npm|
|is-path-inside|3.0.3|间接依赖|npm|
|shebang-command|2.0.0|间接依赖|npm|
|org.openrefine.dependencies:opencsv-multichar|2.4|直接依赖|maven|
|slice-ansi|4.0.0|间接依赖|npm|
|dashdash|1.14.1|间接依赖|npm|
|@humanwhocodes/module-importer|1.0.1|间接依赖|npm|
|cypress-file-upload|5.0.8|直接依赖|npm|
|p-limit|3.1.0|间接依赖|npm|
|fastq|1.13.0|间接依赖|npm|
|org.marc4j:marc4j|2.9.5|直接依赖|maven|
|org.openrefine.dependencies:arithcode|1.2|间接依赖|maven|
|dayjs|1.10.4|间接依赖|npm|
|@cypress/request|3.0.0|间接依赖|npm|
|callsites|3.1.0|间接依赖|npm|
|com.wcohen:com.wcohen.secondstring|0.1|间接依赖|maven|
|find-up|5.0.0|间接依赖|npm|
|flat-cache|3.0.4|间接依赖|npm|
|org.apache.commons:commons-compress|1.24.0|直接依赖|maven|
|com.intellij:annotations|12.0|间接依赖|maven|
|shebang-regex|3.0.0|间接依赖|npm|
|org.jvnet.localizer:localizer|1.31|直接依赖|maven|
|commons-codec:commons-codec|1.16.0|直接依赖|maven|
|semver|7.5.3|间接依赖|npm|
|getpass|0.1.7|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|import-fresh|3.3.0|间接依赖|npm|
|is-installed-globally|0.4.0|间接依赖|npm|
|org.eclipse.jetty:jetty-http|9.4.52.v20230823|间接依赖|maven|
|json-schema|0.4.0|间接依赖|npm|
|fs-extra|9.1.0|间接依赖|npm|
|org.xerial:sqlite-jdbc|3.41.2.2|直接依赖|maven|
|@types/node|18.17.15|间接依赖|npm|
|fast-levenshtein|2.0.6|间接依赖|npm|
|org.slf4j:jcl-over-slf4j|1.7.36|间接依赖|maven|
|global-dirs|3.0.0|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|text-table|0.2.0|间接依赖|npm|
|commons-collections:commons-collections|3.2.2|直接依赖|maven|
|commons-fileupload:commons-fileupload|1.5|直接依赖|maven|
|org.odftoolkit:odfdom-java|0.9.0|直接依赖|maven|
|org.owasp.encoder:encoder|1.2.3|直接依赖|maven|
|eslint|8.49.0|直接依赖|npm|
|path-key|3.1.1|间接依赖|npm|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|which|2.0.2|间接依赖|npm|
|p-locate|5.0.0|间接依赖|npm|
|commander|6.2.1|间接依赖|npm|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.6.20|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.52.v20230823|间接依赖|maven|
|org.clojure:core.specs.alpha|0.2.62|间接依赖|maven|
|enquirer|2.3.6|间接依赖|npm|
|org.eclipse.jetty:jetty-servlets|9.4.52.v20230823|直接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|esquery|1.4.2|间接依赖|npm|
|commons-beanutils:commons-beanutils|1.9.4|间接依赖|maven|
|supports-color|8.1.1|间接依赖|npm|
|acorn-jsx|5.3.2|间接依赖|npm|
|merge-stream|2.0.0|间接依赖|npm|
|balanced-match|1.0.0|间接依赖|npm|
|org.apache.commons:commons-text|1.10.0|直接依赖|maven|
|oro:oro|2.0.8|间接依赖|maven|
|isstream|0.1.2|间接依赖|npm|
|verror|1.10.0|间接依赖|npm|
|org.apache.jena:jena-base|4.8.0|间接依赖|maven|
|punycode|2.1.1|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|org.jasypt:jasypt|1.9.3|直接依赖|maven|
|at-least-node|1.0.0|间接依赖|npm|
|debug|3.2.6|间接依赖|npm|
|net.arnx:jsonic|1.2.11|间接依赖|maven|
|@nodelib/fs.walk|1.2.8|间接依赖|npm|
|org.slf4j:slf4j-api|1.7.36|间接依赖|maven|
|ansi-styles|4.2.1|间接依赖|npm|
|org.sweble.wikitext:swc-parser-lazy|3.1.9|直接依赖|maven|
|eslint-config-google|0.14.0|直接依赖|npm|
|has-symbols|1.0.3|间接依赖|npm|
|commons-lang:commons-lang|2.6|间接依赖|maven|
|@nodelib/fs.stat|2.0.5|间接依赖|npm|
|xerces:xercesImpl|2.12.1|间接依赖|maven|
|com.github.virtuald:curvesapi|1.07|间接依赖|maven|
|url-parse|1.5.10|间接依赖|npm|
|org.eclipse.jetty:jetty-servlet|9.4.52.v20230823|直接依赖|maven|
|performance-now|2.1.0|间接依赖|npm|
|ieee754|1.2.1|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|com.google.http-client:google-http-client|1.42.2|间接依赖|maven|
|KERNEL32.dll||间接依赖||
|fd-slicer|1.1.0|间接依赖|npm|
|is-typedarray|1.0.0|间接依赖|npm|
|listr2|3.10.0|间接依赖|npm|
|type-check|0.4.0|间接依赖|npm|
|natural-compare|1.4.0|间接依赖|npm|
|extract-zip|2.0.1|间接依赖|npm|
|@types/color-name|1.1.1|间接依赖|npm|
|org.apache.logging.log4j:log4j-api|2.20.0|间接依赖|maven|
|@eslint-community/eslint-utils|4.2.0|间接依赖|npm|
|psl|1.9.0|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)