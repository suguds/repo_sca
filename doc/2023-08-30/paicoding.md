# itwanger/paicoding安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696583773171642368.svg)](https://www.murphysec.com/console/report/1696583773117116416/1696583773171642368)

仓库描述：⭐️一款好用又强大的开源社区，基于 Spring Boot、MyBatis-Plus、MySQL、Redis、ElasticSearch、MongoDB、Docker、RabbitMQ 等主流技术栈，附详细教程，包括Java、Spring、MySQL、Redis、微服务&分布式、消息队列等核心知识点。学编程，就上技术派😁。

仓库地址：[https://github.com/itwanger/paicoding](https://github.com/itwanger/paicoding)

| star：957 | watch：20 | fork：209 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-28 14:03:54 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-30 02:06:54 | 组件总数：313 | 漏洞总数：51 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Elasticsearch 存在敏感信息泄露漏洞|未授权敏感信息泄露|[MPS-2019-13902](https://www.oscs1024.com/hd/MPS-2019-13902)|CVE-2019-7619|中危|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|Elasticsearch 存在权限管理不恰当漏洞|权限管理不当|[MPS-2020-15777](https://www.oscs1024.com/hd/MPS-2020-15777)|CVE-2020-7020|低危|
|Elasticsearch  API 密钥权限提升漏洞|权限管理不当|[MPS-2020-4780](https://www.oscs1024.com/hd/MPS-2020-4780)|CVE-2020-7009|高危|
|Elasticsearch 权限管理不当漏洞|权限管理不当|[MPS-2020-8144](https://www.oscs1024.com/hd/MPS-2020-8144)|CVE-2020-7014|高危|
|Elasticsearch 资源管理错误漏洞|未经控制的递归|[MPS-2021-11043](https://www.oscs1024.com/hd/MPS-2021-11043)|CVE-2021-22144|中危|
|Elasticsearch 日志信息泄露漏洞|日志敏感信息泄露|[MPS-2021-1485](https://www.oscs1024.com/hd/MPS-2021-1485)|CVE-2020-7021|中危|
|jsoup <1.14.2 存在拒绝服务漏洞||[MPS-2021-17634](https://www.oscs1024.com/hd/MPS-2021-17634)|CVE-2021-37714|高危|
|Apache PDFBox <2.0.23 拒绝服务漏洞|过度迭代|[MPS-2021-3221](https://www.oscs1024.com/hd/MPS-2021-3221)|CVE-2021-27807|中危|
|Apache PDFBox <2.0.23 拒绝服务漏洞|未经控制的内存分配|[MPS-2021-3222](https://www.oscs1024.com/hd/MPS-2021-3222)|CVE-2021-27906|中危|
|Elasticsearch 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-6747](https://www.oscs1024.com/hd/MPS-2021-6747)|CVE-2021-22137|中危|
|Elasticsearch 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-6749](https://www.oscs1024.com/hd/MPS-2021-6749)|CVE-2021-22135|中危|
|Apache PDFBox <2.0.24 拒绝服务漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-8549](https://www.oscs1024.com/hd/MPS-2021-8549)|CVE-2021-31812|中危|
|Apache PDFBox <2.0.24 拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-8633](https://www.oscs1024.com/hd/MPS-2021-8633)|CVE-2021-31811|中危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|io.springfox:springfox-swagger2 存在输入验证不恰当漏洞|日志敏感信息泄露|[MPS-2022-12534](https://www.oscs1024.com/hd/MPS-2022-12534)||中危|
|Elastic Stack Kibana 存在缺少授权漏洞|授权检查缺失|[MPS-2022-2136](https://www.oscs1024.com/hd/MPS-2022-2136)|CVE-2022-23709|中危|
|Elastic Stack Kibana 存在 XSS 漏洞|XSS|[MPS-2022-2137](https://www.oscs1024.com/hd/MPS-2022-2137)|CVE-2022-23710|中危|
|MyBatis-Plus orderBy方法存在SQL注入漏洞|SQL注入|[MPS-2022-4629](https://www.oscs1024.com/hd/MPS-2022-4629)|CVE-2022-25517|严重|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|jsoup <1.15.3 存在反射型 XSS 漏洞|XSS|[MPS-2022-51547](https://www.oscs1024.com/hd/MPS-2022-51547)|CVE-2022-36033|中危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|XStream 缓冲区错误漏洞|输入验证不恰当|[MPS-2022-57061](https://www.oscs1024.com/hd/MPS-2022-57061)|CVE-2022-40156|低危|
|xstream project跨界内存写漏洞|跨界内存写|[MPS-2022-57062](https://www.oscs1024.com/hd/MPS-2022-57062)|CVE-2022-40155|高危|
|xstream project跨界内存写漏洞|跨界内存写|[MPS-2022-57063](https://www.oscs1024.com/hd/MPS-2022-57063)|CVE-2022-40154|高危|
|XStream 缓冲区错误漏洞|越界写入|[MPS-2022-57065](https://www.oscs1024.com/hd/MPS-2022-57065)|CVE-2022-40152|高危|
|Jettison <1.5.2 拒绝服务漏洞|拒绝服务|[MPS-2022-57067](https://www.oscs1024.com/hd/MPS-2022-57067)|CVE-2022-40150|高危|
|Jettison <1.5.1 拒绝服务漏洞|越界写入|[MPS-2022-57068](https://www.oscs1024.com/hd/MPS-2022-57068)|CVE-2022-40149|高危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|Spring Security通配符路由绕过漏洞|关键资源权限分配不当|[MPS-2022-62832](https://www.oscs1024.com/hd/MPS-2022-62832)|CVE-2023-20860|高危|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|Jettison <1.5.2 拒绝服务漏洞|越界写入|[MPS-2022-64973](https://www.oscs1024.com/hd/MPS-2022-64973)|CVE-2022-45685|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|hutool 表达式注入漏洞|SQL注入|[MPS-2023-2459](https://www.oscs1024.com/hd/MPS-2023-2459)|CVE-2023-24163|严重|
|【存在争议】MybatisPlus <= 3.5.3.1 TenantPlugin 组件 存在 sql 注入漏洞|SQL注入|[MPS-2023-3977](https://www.oscs1024.com/hd/MPS-2023-3977)|CVE-2023-25330|高危|
|hutool 存在任意代码执行漏洞|代码注入|[MPS-2023-7335](https://www.oscs1024.com/hd/MPS-2023-7335)||严重|
|Jettison 安全漏洞|未经控制的递归|[MPS-2023-8270](https://www.oscs1024.com/hd/MPS-2023-8270)|CVE-2023-1436|高危|
|Hutool createTempFile函数敏感信息泄漏漏洞|未授权敏感信息泄露|[MPS-4soz-eyma](https://www.oscs1024.com/hd/MPS-4soz-eyma)|CVE-2023-33695|中危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|hutool <=5.8.17 存在SPEL命令执行风险|代码注入|[MPS-jdrq-1ywv](https://www.oscs1024.com/hd/MPS-jdrq-1ywv)||高危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|HuTool XML外部实体注入漏洞|XXE|[MPS-xd3s-4gev](https://www.oscs1024.com/hd/MPS-xd3s-4gev)|CVE-2023-3276|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.springframework:spring-web|5.3.21|6.0.0|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.3|2.14.0-rc1|直接依赖|建议修复|C:0|H:0|M:3|L:0|
|io.netty:netty-handler|4.1.78.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.squareup.okio:okio|2.8.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.elasticsearch:elasticsearch|6.8.2|8.2.1|直接依赖|建议修复|C:0|H:2|M:7|L:1|
|com.baomidou:mybatis-plus-core|3.4.3.4||直接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.fasterxml.woodstox:woodstox-core|6.2.7|6.4.0|间接依赖|建议修复|C:0|H:3|M:0|L:1|
|cn.hutool:hutool-all|5.8.15|5.8.20|直接依赖|建议修复|C:2|H:1|M:2|L:0|
|org.springframework:spring-webmvc|5.3.21|6.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.baomidou:mybatis-plus-extension|3.5.2||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.30|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|org.codehaus.jettison:jettison|1.1|1.5.4|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|org.springframework:spring-core|5.3.21|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.7.1|3.0.7|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|io.springfox:springfox-swagger2|2.10.5||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|5.3.21|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.pdfbox:pdfbox|2.0.16|2.0.24|间接依赖|可选修复|C:0|H:0|M:4|L:0|
|org.jsoup:jsoup|1.11.3|1.15.3|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|com.google.guava:guava|31.1-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|26|Low|
|Apache-2.0|206|Low|
|BSD-2-Clause|48|Low|
|LGPL-2.1-or-later|5|Low|
|MIT|11|Low|
|GPL-2.0|2|Medium|
|MPL-2.0|1|Low|
|BSD-3-Clause|3|Low|
|LGPL-2.1|2|Medium|
|MPL-1.1|3|Low|
|CDDL-1.1|1|Low|
|EPL-2.0|4|Low|
|EPL-1.0|2|Low|
|AGPL-3.0|1|High|
|MIT-0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.codehaus.woodstox:stax2-api|4.2.1|间接依赖|maven|
|org.thymeleaf.extras:thymeleaf-extras-java8time|3.0.4.RELEASE|间接依赖|maven|
|io.swagger:swagger-models|1.6.6|间接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-client|7.17.4|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.3|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-macros|0.62.2|间接依赖|maven|
|com.openhtmltopdf:openhtmltopdf-core|1.0.0|间接依赖|maven|
|org.apache.commons:commons-exec|1.3|直接依赖|maven|
|org.springframework:spring-core|5.3.21|间接依赖|maven|
|io.opentracing:opentracing-noop|0.33.0|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.64|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-jekyll-tag|0.62.2|间接依赖|maven|
|javax.servlet:javax.servlet-api|4.0.1|直接依赖|maven|
|com.github.houbb:nlp-common|0.0.5|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-cache|2.7.1|直接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-superscript|0.62.2|间接依赖|maven|
|org.apache.lucene:lucene-highlighter|8.11.1|间接依赖|maven|
|org.springframework.data:spring-data-redis|2.7.1|间接依赖|maven|
|org.springframework:spring-expression|5.3.21|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-ast|0.62.2|间接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-high-level-client|7.17.4|间接依赖|maven|
|org.checkerframework:checker-qual|3.12.0|间接依赖|maven|
|org.elasticsearch:elasticsearch-geo|7.17.4|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-dependency|0.62.2|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.3|间接依赖|maven|
|org.apache.lucene:lucene-queryparser|7.7.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.2|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|间接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|com.vladsch.flexmark:flexmark|0.62.2|间接依赖|maven|
|org.apiguardian:apiguardian-api|1.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.7.1|间接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|org.apache.pdfbox:pdfbox|2.0.16|间接依赖|maven|
|com.baomidou:mybatis-plus-annotation|3.4.3.4|间接依赖|maven|
|com.github.houbb:heaven|0.2.7|间接依赖|maven|
|org.springframework:spring-beans|5.3.21|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.3|间接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.15|间接依赖|maven|
|com.tdunning:t-digest|3.2|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-autolink|0.62.2|间接依赖|maven|
|org.apache.lucene:lucene-memory|8.11.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-thymeleaf|2.7.1|直接依赖|maven|
|com.github.houbb:opencc4j|1.8.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-redis|2.7.1|直接依赖|maven|
|com.openhtmltopdf:openhtmltopdf-pdfbox|1.0.0|间接依赖|maven|
|org.jsoup:jsoup|1.15.3|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.7.1|间接依赖|maven|
|org.thymeleaf:thymeleaf|3.0.15.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-websocket|2.7.1|直接依赖|maven|
|com.squareup.okhttp3:okhttp-sse|4.9.3|间接依赖|maven|
|com.github.houbb:sensitive-word|0.8.0|直接依赖|maven|
|org.jetbrains:annotations|15.0|间接依赖|maven|
|org.lz4:lz4-java|1.8.0|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-visitor|0.62.2|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-smile|2.13.3|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-sequence|0.62.2|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-aside|0.62.2|间接依赖|maven|
|io.netty:netty-codec|4.1.78.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-configuration-processor|2.7.1|直接依赖|maven|
|com.rabbitmq:amqp-client|5.14.2|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-gfm-tasklist|0.62.2|间接依赖|maven|
|io.springfox:springfox-swagger2|2.10.5|间接依赖|maven|
|com.github.xiaoymin:knife4j-core|4.0.0|间接依赖|maven|
|com.github.paicoding.forum:paicoding-api|0.0.1-SNAPSHOT|直接依赖|maven|
|com.github.jai-imageio:jai-imageio-core|1.4.0|间接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|6.2.7|间接依赖|maven|
|org.springframework.data:spring-data-commons|2.7.1|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-core|4.5.10|间接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-client|6.8.2|直接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.1|间接依赖|maven|
|com.github.liuyueyi.media:qrcode-plugin|3.0.0|直接依赖|maven|
|io.netty:netty-transport|4.1.78.Final|间接依赖|maven|
|com.squareup.retrofit2:adapter-rxjava2|2.9.0|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|io.netty:netty-buffer|4.1.78.Final|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.6.21|间接依赖|maven|
|org.springframework.plugin:spring-plugin-metadata|2.0.0.RELEASE|间接依赖|maven|
|com.alibaba:fastjson|2.0.26|间接依赖|maven|
|io.springfox:springfox-swagger-common|2.10.5|间接依赖|maven|
|org.springframework:spring-jdbc|5.3.21|直接依赖|maven|
|mysql:mysql-connector-java|8.0.29|直接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.2|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.6.21|间接依赖|maven|
|net.sf.jopt-simple:jopt-simple|5.0.2|间接依赖|maven|
|com.carrotsearch:hppc|0.8.1|间接依赖|maven|
|org.apache.lucene:lucene-spatial3d|7.7.0|间接依赖|maven|
|org.jsoup:jsoup|1.11.3|间接依赖|maven|
|com.baomidou:mybatis-plus-boot-starter|3.5.2|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.64|间接依赖|maven|
|joda-time:joda-time|2.10.10|间接依赖|maven|
|de.rototor.pdfbox:graphics2d|0.24|间接依赖|maven|
|com.esotericsoftware:kryo|5.4.0|直接依赖|maven|
|org.elasticsearch:elasticsearch-x-content|6.8.2|间接依赖|maven|
|org.apache.lucene:lucene-highlighter|7.7.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-mail|2.7.1|直接依赖|maven|
|io.netty:netty-resolver|4.1.78.Final|间接依赖|maven|
|org.apache.lucene:lucene-spatial3d|8.11.1|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.9|间接依赖|maven|
|org.apache.commons:commons-collections4|4.4|直接依赖|maven|
|com.vladsch.flexmark:flexmark-util-options|0.62.2|间接依赖|maven|
|com.squareup.retrofit2:converter-jackson|2.9.0|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-ins|0.62.2|间接依赖|maven|
|org.javassist:javassist|3.25.0-GA|间接依赖|maven|
|io.netty:netty-handler|4.1.78.Final|间接依赖|maven|
|org.apache.lucene:lucene-sandbox|7.7.0|间接依赖|maven|
|org.elasticsearch.plugin:lang-mustache-client|6.8.2|间接依赖|maven|
|io.netty:netty-common|4.1.78.Final|间接依赖|maven|
|org.springframework.boot:spring-boot|2.7.1|直接依赖|maven|
|org.elasticsearch:elasticsearch-core|6.8.2|间接依赖|maven|
|org.elasticsearch:jna|4.5.1|间接依赖|maven|
|org.codehaus.jettison:jettison|1.1|间接依赖|maven|
|com.rabbitmq:amqp-client|5.5.1|直接依赖|maven|
|org.attoparser:attoparser|2.0.5.RELEASE|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|io.springfox:springfox-core|2.10.5|间接依赖|maven|
|org.springframework:spring-context|5.3.21|直接依赖|maven|
|org.apache.lucene:lucene-join|8.11.1|间接依赖|maven|
|org.springframework.data:spring-data-keyvalue|2.7.1|间接依赖|maven|
|org.apache.lucene:lucene-memory|7.7.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.6.21|间接依赖|maven|
|org.apache.pdfbox:xmpbox|2.0.16|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.9.3|直接依赖|maven|
|io.opentracing:opentracing-api|0.33.0|间接依赖|maven|
|org.elasticsearch:elasticsearch-secure-sm|6.8.2|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-builder|0.62.2|间接依赖|maven|
|com.github.xiaoymin:knife4j-openapi2-ui|4.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot-devtools|2.7.1|直接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.1|直接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|org.springframework:spring-context-support|5.3.21|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|org.elasticsearch.plugin:mapper-extras-client|7.17.4|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-abbreviation|0.62.2|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.11|间接依赖|maven|
|io.springfox:springfox-spring-web|2.10.5|间接依赖|maven|
|org.projectlombok:lombok|1.18.24|直接依赖|maven|
|com.aliyun.oss:aliyun-sdk-oss|3.15.1|直接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.5|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.11.0|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-ram|3.1.0|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-anchorlink|0.62.2|间接依赖|maven|
|com.beust:jcommander|1.82|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|org.apache.lucene:lucene-core|7.7.0|间接依赖|maven|
|org.elasticsearch.plugin:aggs-matrix-stats-client|6.8.2|间接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|直接依赖|maven|
|com.github.spullara.mustache.java:compiler|0.9.3|间接依赖|maven|
|com.esotericsoftware:minlog|1.3.1|间接依赖|maven|
|com.squareup.okhttp3:logging-interceptor|4.9.3|间接依赖|maven|
|org.elasticsearch:elasticsearch|7.17.4|间接依赖|maven|
|io.opentracing:opentracing-util|0.33.0|间接依赖|maven|
|com.squareup.okhttp3:okhttp|4.9.3|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-tables|0.62.2|间接依赖|maven|
|org.apache.lucene:lucene-queries|8.11.1|间接依赖|maven|
|stax:stax-api|1.0.1|间接依赖|maven|
|org.mapstruct:mapstruct|1.4.2.Final|直接依赖|maven|
|io.reactivex.rxjava2:rxjava|2.2.21|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-xwiki-macros|0.62.2|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.78.Final|间接依赖|maven|
|com.baomidou:mybatis-plus-core|3.4.3.4|直接依赖|maven|
|org.elasticsearch:elasticsearch-cli|6.8.2|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.11|直接依赖|maven|
|org.objenesis:objenesis|3.3|间接依赖|maven|
|org.jdom:jdom2|2.0.6.1|间接依赖|maven|
|org.thymeleaf:thymeleaf-spring5|3.0.15.RELEASE|间接依赖|maven|
|com.google.zxing:core|3.5.0|间接依赖|maven|
|org.apache.lucene:lucene-grouping|8.11.1|间接依赖|maven|
|com.baomidou:mybatis-plus-extension|3.5.2|间接依赖|maven|
|org.apache.lucene:lucene-queryparser|8.11.1|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-gfm-users|0.62.2|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.15|间接依赖|maven|
|org.springframework:spring-web|5.3.21|直接依赖|maven|
|org.elasticsearch.plugin:parent-join-client|7.17.4|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-enumerated-reference|0.62.2|间接依赖|maven|
|org.elasticsearch:elasticsearch-secure-sm|7.17.4|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.7.1|直接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-jekyll-front-matter|0.62.2|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.6.21|间接依赖|maven|
|org.apache.lucene:lucene-grouping|7.7.0|间接依赖|maven|
|org.elasticsearch:elasticsearch-plugin-classloader|7.17.4|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-xml|2.13.3|直接依赖|maven|
|com.github.liuyueyi.media:base-plugin|3.0.0|间接依赖|maven|
|org.apache.lucene:lucene-core|8.11.1|间接依赖|maven|
|io.springfox:springfox-spring-webmvc|2.10.5|间接依赖|maven|
|com.vladsch.flexmark:flexmark-youtrack-converter|0.62.2|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-yaml-front-matter|0.62.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.7.1|间接依赖|maven|
|org.apache.lucene:lucene-backward-codecs|8.11.1|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.13.3|间接依赖|maven|
|org.apache.httpcomponents:fluent-hc|4.5.13|间接依赖|maven|
|org.apache.lucene:lucene-spatial-extras|7.7.0|间接依赖|maven|
|io.springfox:springfox-bean-validators|2.10.5|间接依赖|maven|
|org.elasticsearch.plugin:lang-mustache-client|7.17.4|间接依赖|maven|
|org.apache.lucene:lucene-backward-codecs|7.7.0|间接依赖|maven|
|org.springframework:spring-tx|5.3.21|间接依赖|maven|
|org.javassist:javassist|3.24.1-GA|间接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-high-level-client|6.8.2|直接依赖|maven|
|com.github.paicoding.forum:paicoding-service|0.0.1-SNAPSHOT|直接依赖|maven|
|org.apache.lucene:lucene-misc|8.11.1|间接依赖|maven|
|com.vladsch.flexmark:flexmark-jira-converter|0.62.2|间接依赖|maven|
|com.vladsch.flexmark:flexmark-all|0.62.2|直接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-definition|0.62.2|间接依赖|maven|
|org.elasticsearch.plugin:rank-eval-client|7.17.4|间接依赖|maven|
|com.vladsch.flexmark:flexmark-profile-pegdown|0.62.2|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-html|0.62.2|间接依赖|maven|
|org.ini4j:ini4j|0.5.4|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.3|直接依赖|maven|
|com.vladsch.flexmark:flexmark-util-format|0.62.2|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.11|间接依赖|maven|
|com.itextpdf:itextpdf|5.5.13.3|直接依赖|maven|
|com.vladsch.flexmark:flexmark-html2md-converter|0.62.2|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|org.liquibase:liquibase-core|4.9.1|直接依赖|maven|
|io.swagger:swagger-annotations|1.6.6|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|com.google.guava:guava|31.1-jre|直接依赖|maven|
|com.vladsch.flexmark:flexmark-pdf-converter|0.62.2|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.21|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-footnotes|0.62.2|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.3|间接依赖|maven|
|org.apache.lucene:lucene-analyzers-common|8.11.1|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-escaped-character|0.62.2|间接依赖|maven|
|org.apache.lucene:lucene-sandbox|8.11.1|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-admonition|0.62.2|间接依赖|maven|
|org.mybatis:mybatis-spring|2.0.7|直接依赖|maven|
|com.github.paicoding.forum:paicoding-ui|0.0.1-SNAPSHOT|直接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-attributes|0.62.2|间接依赖|maven|
|org.apache.lucene:lucene-suggest|7.7.0|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-misc|0.62.2|间接依赖|maven|
|org.apache.lucene:lucene-suggest|8.11.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.7.1|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|io.github.classgraph:classgraph|4.1.7|间接依赖|maven|
|org.springframework.plugin:spring-plugin-core|2.0.0.RELEASE|间接依赖|maven|
|com.sun.activation:jakarta.activation|1.2.2|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.13.3|间接依赖|maven|
|io.springfox:springfox-schema|2.10.5|间接依赖|maven|
|org.elasticsearch.plugin:parent-join-client|6.8.2|间接依赖|maven|
|org.springframework:spring-oxm|5.3.21|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-typographic|0.62.2|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-emoji|0.62.2|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-kms|2.11.0|间接依赖|maven|
|org.unbescape:unbescape|1.1.6.RELEASE|间接依赖|maven|
|org.apache.lucene:lucene-join|7.7.0|间接依赖|maven|
|com.ibm.icu:icu4j|59.1|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-collection|0.62.2|间接依赖|maven|
|org.jacoco:org.jacoco.agent|0.8.5|间接依赖|maven|
|com.squareup.okio:okio|2.8.0|间接依赖|maven|
|org.mapstruct:mapstruct-processor|1.4.2.Final|直接依赖|maven|
|com.github.xiaoymin:knife4j-openapi2-spring-boot-starter|4.0.0|直接依赖|maven|
|ognl:ognl|3.2.11|直接依赖|maven|
|org.apache.lucene:lucene-queries|7.7.0|间接依赖|maven|
|org.lionsoul:ip2region|2.6.6|直接依赖|maven|
|com.alibaba.fastjson2:fastjson2-extension|2.0.26|间接依赖|maven|
|org.elasticsearch:elasticsearch|6.8.2|直接依赖|maven|
|com.vladsch.flexmark:flexmark-util|0.62.2|间接依赖|maven|
|org.nibor.autolink:autolink|0.6.0|间接依赖|maven|
|org.mybatis:mybatis|3.5.10|直接依赖|maven|
|com.auth0:java-jwt|4.4.0|直接依赖|maven|
|org.yaml:snakeyaml|1.30|间接依赖|maven|
|net.java.dev.jna:jna|5.10.0|间接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|com.github.plexpt:chatgpt|4.0.5|直接依赖|maven|
|com.openhtmltopdf:openhtmltopdf-rtl-support|1.0.0|间接依赖|maven|
|org.elasticsearch.plugin:rank-eval-client|6.8.2|间接依赖|maven|
|io.projectreactor:reactor-core|3.4.19|间接依赖|maven|
|org.apache.lucene:lucene-misc|7.7.0|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|直接依赖|maven|
|com.openhtmltopdf:openhtmltopdf-jsoup-dom-converter|1.0.0|间接依赖|maven|
|joda-time:joda-time|2.10.1|间接依赖|maven|
|com.sun.mail:jakarta.mail|1.6.7|间接依赖|maven|
|org.apache.lucene:lucene-spatial|7.7.0|间接依赖|maven|
|org.elasticsearch:elasticsearch-cli|7.17.4|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-data|0.62.2|间接依赖|maven|
|com.github.spullara.mustache.java:compiler|0.9.6|间接依赖|maven|
|cn.hutool:hutool-all|5.8.15|直接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-gitlab|0.62.2|间接依赖|maven|
|com.alibaba.fastjson2:fastjson2|2.0.26|间接依赖|maven|
|com.carrotsearch:hppc|0.7.1|间接依赖|maven|
|com.github.jsqlparser:jsqlparser|4.2|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-youtube-embedded|0.62.2|间接依赖|maven|
|com.baomidou:mybatis-plus|3.5.2|间接依赖|maven|
|org.apache.lucene:lucene-analyzers-common|7.7.0|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-media-tags|0.62.2|间接依赖|maven|
|org.springframework:spring-websocket|5.3.21|间接依赖|maven|
|com.google.zxing:javase|3.5.0|间接依赖|maven|
|io.springfox:springfox-spi|2.10.5|间接依赖|maven|
|org.openpnp:opencv|4.6.0-0|直接依赖|maven|
|org.elasticsearch:elasticsearch-x-content|7.17.4|间接依赖|maven|
|org.springframework:spring-aop|5.3.21|间接依赖|maven|
|org.springframework:spring-messaging|5.3.21|间接依赖|maven|
|org.springframework:spring-jcl|5.3.21|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.3|间接依赖|maven|
|org.elasticsearch:elasticsearch-lz4|7.17.4|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-gfm-strikethrough|0.62.2|间接依赖|maven|
|commons-io:commons-io|2.11.0|直接依赖|maven|
|com.google.code.gson:gson|2.9.0|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-toc|0.62.2|间接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-wikilink|0.62.2|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.64|间接依赖|maven|
|com.github.paicoding.forum:paicoding-core|0.0.1-SNAPSHOT|直接依赖|maven|
|org.apache.pdfbox:fontbox|2.0.16|间接依赖|maven|
|org.elasticsearch.plugin:aggs-matrix-stats-client|7.17.4|间接依赖|maven|
|com.belerweb:pinyin4j|2.5.1|直接依赖|maven|
|com.vladsch.flexmark:flexmark-ext-gfm-issues|0.62.2|间接依赖|maven|
|org.aspectj:aspectjweaver|1.9.7|直接依赖|maven|
|com.squareup.retrofit2:retrofit|2.9.0|间接依赖|maven|
|io.lettuce:lettuce-core|6.1.8.RELEASE|间接依赖|maven|
|com.esotericsoftware:reflectasm|1.11.9|间接依赖|maven|
|org.elasticsearch:elasticsearch-core|7.17.4|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)