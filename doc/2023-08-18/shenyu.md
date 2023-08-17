# apache/shenyu安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692235514563678208.svg)](https://www.murphysec.com/console/report/1692235514429460480/1692235514563678208)

仓库描述：Apache ShenYu is a Java native API Gateway for service proxy, protocol conversion and API governance.

仓库地址：[https://github.com/apache/shenyu](https://github.com/apache/shenyu)

| star：7999 | watch：294 | fork：2800 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-17 23:24:56 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-18 02:17:13 | 组件总数：663 | 漏洞总数：52 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Swagger UI @import 跨站脚本漏洞|CSRF|[MPS-2019-13043](https://www.oscs1024.com/hd/MPS-2019-13043)|CVE-2019-17495|中危|
|SOFA-Hessian 代码问题漏洞||[MPS-2019-1978](https://www.oscs1024.com/hd/MPS-2019-1978)|CVE-2019-9212|严重|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|Red Hat Resteasy 敏感信息泄露漏洞|通过错误消息导致的信息暴露|[MPS-2020-13308](https://www.oscs1024.com/hd/MPS-2020-13308)|CVE-2020-25633|中危|
|Red Hat Resteasy 输入验证错误漏洞|XSS|[MPS-2020-7580](https://www.oscs1024.com/hd/MPS-2020-7580)|CVE-2020-1695|高危|
|com.h2database:h2 < 2.0.202 XXE漏洞|XXE|[MPS-2021-19502](https://www.oscs1024.com/hd/MPS-2021-19502)|CVE-2021-23463|严重|
|H2数据库存在JNDI注入漏洞|反序列化|[MPS-2021-33243](https://www.oscs1024.com/hd/MPS-2021-33243)|CVE-2021-42392|严重|
|XStream < 1.4.19存在拒绝服务漏洞|拒绝服务|[MPS-2021-36984](https://www.oscs1024.com/hd/MPS-2021-36984)|CVE-2021-43859|高危|
|Fastjson < 1.2.83 任意代码执行漏洞|反序列化|[MPS-2022-11320](https://www.oscs1024.com/hd/MPS-2022-11320)|CVE-2022-25845|高危|
|com.nimbusds:oauth2-oidc-sdk 存在XXE漏洞|XXE|[MPS-2022-12182](https://www.oscs1024.com/hd/MPS-2022-12182)||高危|
|FasterXML Jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2022-12500](https://www.oscs1024.com/hd/MPS-2022-12500)||中危|
|H2 Console 代码注入漏洞|代码注入|[MPS-2022-1435](https://www.oscs1024.com/hd/MPS-2022-1435)|CVE-2022-23221|严重|
|Apache Shiro 权限绕过漏洞|授权检查错误|[MPS-2022-17602](https://www.oscs1024.com/hd/MPS-2022-17602)|CVE-2022-32532|中危|
|Apache Pulsar C++/Python 客户端存在中间人攻击漏洞|中间人攻击|[MPS-2022-18844](https://www.oscs1024.com/hd/MPS-2022-18844)|CVE-2022-33684|中危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|Bouncy Castle <1.69 认证绕过漏洞|密码学问题|[MPS-2022-54305](https://www.oscs1024.com/hd/MPS-2022-54305)||中危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|Apache Shiro < 1.10.0 身份认证绕过漏洞|授权检查错误|[MPS-2022-56931](https://www.oscs1024.com/hd/MPS-2022-56931)|CVE-2022-40664|严重|
|XStream 缓冲区错误漏洞|输入验证不恰当|[MPS-2022-57061](https://www.oscs1024.com/hd/MPS-2022-57061)|CVE-2022-40156|低危|
|xstream project跨界内存写漏洞|跨界内存写|[MPS-2022-57062](https://www.oscs1024.com/hd/MPS-2022-57062)|CVE-2022-40155|高危|
|xstream project跨界内存写漏洞|跨界内存写|[MPS-2022-57063](https://www.oscs1024.com/hd/MPS-2022-57063)|CVE-2022-40154|高危|
|XStream 缓冲区错误漏洞|越界写入|[MPS-2022-57065](https://www.oscs1024.com/hd/MPS-2022-57065)|CVE-2022-40152|高危|
|xstream project跨界内存写漏洞|越界写入|[MPS-2022-57066](https://www.oscs1024.com/hd/MPS-2022-57066)|CVE-2022-40151|高危|
|Jettison <1.5.2 拒绝服务漏洞|拒绝服务|[MPS-2022-57067](https://www.oscs1024.com/hd/MPS-2022-57067)|CVE-2022-40150|高危|
|Jettison <1.5.1 拒绝服务漏洞|越界写入|[MPS-2022-57068](https://www.oscs1024.com/hd/MPS-2022-57068)|CVE-2022-40149|高危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|XStream < 1.4.20 栈缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58603](https://www.oscs1024.com/hd/MPS-2022-58603)|CVE-2022-41966|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|Jettison <1.5.2 拒绝服务漏洞|越界写入|[MPS-2022-64973](https://www.oscs1024.com/hd/MPS-2022-64973)|CVE-2022-45685|高危|
|Jettison <1.5.2 拒绝服务漏洞|越界写入|[MPS-2022-64981](https://www.oscs1024.com/hd/MPS-2022-64981)|CVE-2022-45693|高危|
|H2 数据库明文密码问题|未授权敏感信息泄露|[MPS-2022-65204](https://www.oscs1024.com/hd/MPS-2022-65204)|CVE-2022-45868|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Apache Shiro <1.11.0 存在身份验证绕过漏洞|解释冲突|[MPS-2023-0169](https://www.oscs1024.com/hd/MPS-2023-0169)|CVE-2023-22602|中危|
|Apache Dubbo 存在反序列化漏洞|反序列化|[MPS-2023-1779](https://www.oscs1024.com/hd/MPS-2023-1779)|CVE-2023-23638|中危|
|Apache Kafka Connect 模块JNDI注入漏洞|反序列化|[MPS-2023-3834](https://www.oscs1024.com/hd/MPS-2023-3834)|CVE-2023-25194|高危|
|Jettison 安全漏洞|未经控制的递归|[MPS-2023-8270](https://www.oscs1024.com/hd/MPS-2023-8270)|CVE-2023-1436|高危|
|jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2023-8438](https://www.oscs1024.com/hd/MPS-2023-8438)|CVE-2021-46877|中危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Apache Shiro 身份验证绕过漏洞|身份验证不当|[MPS-i2ro-tb93](https://www.oscs1024.com/hd/MPS-i2ro-tb93)|CVE-2023-34478|高危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Spring Security 路径匹配漏洞|不恰当实现的标准安全检查|[MPS-j3nx-691g](https://www.oscs1024.com/hd/MPS-j3nx-691g)|CVE-2023-34034|严重|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.apache.kafka:kafka-clients|3.2.0|3.4.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.alipay.sofa:hessian|3.3.7|4.0.3|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.apache.dubbo:dubbo|3.1.1|3.1.6|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.xerial.snappy:snappy-java|1.1.8.4|1.1.10.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.12.3|2.14.0-rc1|直接依赖|建议修复|C:0|H:1|M:5|L:0|
|com.h2database:h2|1.4.200|2.1.210|直接依赖|建议修复|C:3|H:1|M:0|L:0|
|org.apache.kafka:kafka-clients|3.1.2|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.springfox:springfox-swagger-ui|2.9.2|2.10.0|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.apache.shiro:shiro-web|1.8.0|2.0.0-alpha-3|间接依赖|建议修复|C:1|H:1|M:1|L:0|
|com.thoughtworks.xstream:xstream|1.4.18|1.4.20|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.jboss.resteasy:resteasy-jaxrs|3.6.3.Final|3.11.0.Final|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.squareup.okio:okio|2.8.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.woodstox:woodstox-core|6.2.1|6.4.0|间接依赖|建议修复|C:0|H:3|M:0|L:1|
|org.springframework.security:spring-security-web|5.7.9|6.1.2|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|io.netty:netty-handler|4.1.94.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.apache.shiro:shiro-spring|1.8.0|1.9.1|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.codehaus.jettison:jettison|1.4.0|1.5.4|间接依赖|建议修复|C:0|H:5|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.5|2.14.0-rc1|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-web|5.3.28|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.alibaba:fastjson|1.2.71|1.2.83|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.alibaba:fastjson|1.2.76|1.2.83|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.shiro:shiro-core|1.8.0|1.9.1|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.nimbusds:oauth2-oidc-sdk|7.5|9.3.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.30|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|org.bouncycastle:bcprov-jdk18on|1.72|1.74|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|31.1-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.bouncycastle:bcprov-jdk15on|1.68|1.69|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.apache.pulsar:pulsar-client|2.10.1|2.10.2|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.bouncycastle:bcprov-jdk15on|1.69||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.h2database:h2|2.1.214||间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.jboss.resteasy:resteasy-client|3.6.3.Final|4.5.8.SP1|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|501|Low|
|CDDL-1.1|5|Low|
|BSD-3-Clause|15|Low|
|BSD-2-Clause|5|Low|
|EPL-2.0|7|Low|
|CDDL-1.0|3|Low|
|LGPL-3.0-or-later|4|Low|
|EPL-1.0|6|Low|
|MIT|10|Low|
|LGPL-2.1|2|Medium|
|MPL-1.1|2|Low|
|MPL-2.0|2|Low|
|WTFPL|1|Low|
|MIT-0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.ctrip.framework.apollo:apollo-core|2.1.0|间接依赖|maven|
|io.projectreactor.netty:reactor-netty|1.0.33|直接依赖|maven|
|io.netty:netty-codec-smtp|4.1.94.Final|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-loadbalancer|3.1.2|直接依赖|maven|
|org.apache.shenyu:shenyu-spi|2.6.1-SNAPSHOT|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.11.0|间接依赖|maven|
|io.prometheus.jmx:collector|0.15.0|直接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.2|间接依赖|maven|
|com.netflix.archaius:archaius-core|0.7.6|间接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-client|8.2.3|间接依赖|maven|
|io.github.resilience4j:resilience4j-ratelimiter|1.7.1|直接依赖|maven|
|com.netflix.ribbon:ribbon-transport|2.3.0|间接依赖|maven|
|io.github.huaweicloud:lts-sdk-java|1.0.1|直接依赖|maven|
|io.springfox:springfox-swagger-ui|2.9.2|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-sentinel|2.6.1-SNAPSHOT|直接依赖|maven|
|commons-logging:commons-logging|1.1.1|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-ratelimiter|2.6.1-SNAPSHOT|直接依赖|maven|
|com.alibaba:fastjson|1.2.83|间接依赖|maven|
|com.alibaba.nacos:nacos-client|2.0.4|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-tcp|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-resilience4j|2.6.1-SNAPSHOT|直接依赖|maven|
|io.springfox:springfox-spi|2.9.2|间接依赖|maven|
|com.sun.activation:javax.activation|1.2.0|间接依赖|maven|
|com.github.vladimir-bukhtoyarov:bucket4j-core|7.6.0|间接依赖|maven|
|net.jodah:failsafe|2.4.4|间接依赖|maven|
|com.weibo:motan-transport-netty4|1.2.1|直接依赖|maven|
|commons-validator:commons-validator|1.7|间接依赖|maven|
|com.alibaba:fastjson|1.2.76|间接依赖|maven|
|io.kubernetes:client-java-proto|17.0.2|间接依赖|maven|
|com.google.protobuf:protobuf-java-util|3.21.1|间接依赖|maven|
|joda-time:joda-time|2.3|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.6.21|间接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|commons-jxpath:commons-jxpath|1.3|间接依赖|maven|
|io.swagger:swagger-annotations|1.5.20|间接依赖|maven|
|io.prometheus:simpleclient|0.15.0|直接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.2|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-key-auth|2.6.1-SNAPSHOT|直接依赖|maven|
|io.reactivex:rxnetty-contexts|0.4.9|间接依赖|maven|
|xmlpull:xmlpull|1.1.3.1|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-modify-response|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-dubbo-common|2.6.1-SNAPSHOT|直接依赖|maven|
|io.zipkin.zipkin2:zipkin|2.9.4|间接依赖|maven|
|org.apache.shiro:shiro-config-ogdl|1.8.0|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-sync-data-etcd|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-alibaba-dubbo|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shiro:shiro-crypto-core|1.8.0|间接依赖|maven|
|net.jcip:jcip-annotations|1.0|间接依赖|maven|
|io.netty:netty-codec-stomp|4.1.94.Final|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|io.reactivex:rxjava|1.3.8|间接依赖|maven|
|io.netty:netty-handler-ssl-ocsp|4.1.94.Final|间接依赖|maven|
|org.springframework.security:spring-security-web|5.7.9|间接依赖|maven|
|io.vertx:vertx-core|4.3.2|间接依赖|maven|
|org.apache.shenyu:shenyu-sync-data-http|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-request|2.6.1-SNAPSHOT|直接依赖|maven|
|io.opentracing:opentracing-noop|0.22.0|间接依赖|maven|
|org.apache.shenyu:shenyu-register-client-server-nacos|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-springcloud|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-logging-elasticsearch|2.6.1-SNAPSHOT|直接依赖|maven|
|com.alibaba.cloud:spring-cloud-alibaba-commons|2021.0.1.0|间接依赖|maven|
|com.google.protobuf:protobuf-java-util|3.21.12|直接依赖|maven|
|javax.activation:activation|1.1.1|间接依赖|maven|
|org.apache.yetus:audience-annotations|0.5.0|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|org.apache.shenyu:shenyu-sync-data-etcd|2.6.1-SNAPSHOT|直接依赖|maven|
|com.esotericsoftware:kryo-shaded|4.0.0|直接依赖|maven|
|org.bouncycastle:bcutil-jdk18on|1.72|间接依赖|maven|
|com.github.fge:msg-simple|1.1|间接依赖|maven|
|org.springframework.data:spring-data-redis|2.7.13|直接依赖|maven|
|com.google.inject:guice|5.0.1|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.13.5|间接依赖|maven|
|com.nimbusds:lang-tag|1.4.4|间接依赖|maven|
|org.springframework:spring-web|5.3.28|间接依赖|maven|
|commons-codec:commons-codec|1.15|直接依赖|maven|
|org.springframework:spring-context-support|5.3.28|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter|3.1.2|直接依赖|maven|
|io.kubernetes:client-java-extended|17.0.2|间接依赖|maven|
|org.apache.shenyu:shenyu-sdk-spring|2.6.1-SNAPSHOT|直接依赖|maven|
|org.lz4:lz4-java|1.8.0|直接依赖|maven|
|com.ecwid.consul:consul-api|1.4.5|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-transform|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-websocket|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-sync-data-websocket|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-ratelimiter|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shiro:shiro-crypto-cipher|1.8.0|间接依赖|maven|
|com.nimbusds:oauth2-oidc-sdk|7.5|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.2-1|间接依赖|maven|
|org.springframework.ldap:spring-ldap-core|2.3.4.RELEASE|直接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-autoconfigure|2.2.2|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.3.Final|间接依赖|maven|
|org.apache.dubbo:dubbo-dependencies-zookeeper|3.1.1|直接依赖|maven|
|com.sun.jersey.contribs:jersey-apache-client4|1.19.1|间接依赖|maven|
|org.apache.shenyu:shenyu-client-api-docs-annotations|2.6.1-SNAPSHOT|直接依赖|maven|
|org.aspectj:aspectjweaver|1.9.6|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-motan|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.curator:curator-client|4.3.0|间接依赖|maven|
|io.opentracing:opentracing-util|0.22.0|间接依赖|maven|
|io.netty:netty-transport-rxtx|4.1.94.Final|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-divide|2.6.1-SNAPSHOT|直接依赖|maven|
|org.springframework:spring-context|5.3.28|直接依赖|maven|
|org.bouncycastle:bcprov-jdk18on|1.72|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-oauth2|2.6.1-SNAPSHOT|直接依赖|maven|
|io.github.resilience4j:resilience4j-core|1.7.1|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-base|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shiro:shiro-lang|1.8.0|间接依赖|maven|
|io.github.resilience4j:resilience4j-circuitbreaker|1.7.1|直接依赖|maven|
|com.alibaba.csp:sentinel-spring-webflux-adapter|1.8.3|直接依赖|maven|
|com.aliyun.openservices:aliyun-log-producer|0.3.10|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-sign|2.6.1-SNAPSHOT|直接依赖|maven|
|com.github.luben:zstd-jni|1.5.0-4|间接依赖|maven|
|org.apache.rocketmq:rocketmq-remoting|4.9.3|间接依赖|maven|
|commons-pool:commons-pool|1.6|间接依赖|maven|
|com.github.fge:jackson-coreutils|1.6|间接依赖|maven|
|org.apache.shenyu:shenyu-client-tars|2.6.1-SNAPSHOT|直接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.36|直接依赖|maven|
|org.apache.shenyu:shenyu-register-client-server-api|2.6.1-SNAPSHOT|直接依赖|maven|
|com.ctrip.framework.apollo:apollo-client|2.1.0|直接依赖|maven|
|org.apache.rocketmq:rocketmq-logging|4.9.3|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.6|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-logging-rocketmq|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.commons:commons-pool2|2.11.1|直接依赖|maven|
|io.prometheus:simpleclient_httpserver|0.15.0|直接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-logging-clickhouse|2.6.1-SNAPSHOT|直接依赖|maven|
|ch.qos.logback:logback-classic|1.2.12|间接依赖|maven|
|io.netty:netty-buffer|4.1.94.Final|直接依赖|maven|
|org.bitbucket.b_c:jose4j|0.9.2|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.94.Final|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-general-context|2.6.1-SNAPSHOT|直接依赖|maven|
|org.checkerframework:checker-qual|3.19.0|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-cache|2.6.1-SNAPSHOT|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.10.0|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-mqtt|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-hystrix|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-hystrix|2.6.1-SNAPSHOT|直接依赖|maven|
|com.weibo:motan-springsupport|1.2.1|直接依赖|maven|
|org.apache.oltu.oauth2:org.apache.oltu.oauth2.common|1.0.2|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|org.apache.shenyu:shenyu-client-springcloud|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-sync-data-zookeeper|2.6.1-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.5|直接依赖|maven|
|org.apache.shenyu:shenyu-web|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-sync-data-polaris|2.6.1-SNAPSHOT|直接依赖|maven|
|org.eclipse.parsson:parsson|1.0.0|间接依赖|maven|
|io.jsonwebtoken:jjwt-api|0.11.5|间接依赖|maven|
|org.apache.rocketmq:rocketmq-acl|4.9.3|直接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|8.14.1|间接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-mock|2.6.1-SNAPSHOT|直接依赖|maven|
|io.zipkin.reporter2:zipkin-reporter|2.7.4|间接依赖|maven|
|org.springframework.cloud:spring-cloud-netflix-ribbon|2.2.10.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-cache|2.7.13|间接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.94.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.13|直接依赖|maven|
|org.javassist:javassist|3.20.0-GA|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.14|间接依赖|maven|
|io.zipkin.zipkin2:zipkin|2.23.2|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.21|间接依赖|maven|
|javax.servlet:servlet-api|2.5|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-apache-dubbo|2.6.1-SNAPSHOT|直接依赖|maven|
|com.aliyun.openservices:aliyun-log|0.6.57|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-websocket|2.7.13|直接依赖|maven|
|io.vertx:vertx-grpc|4.3.2|间接依赖|maven|
|commons-configuration:commons-configuration|1.10|间接依赖|maven|
|org.apache.shenyu:shenyu-admin|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.zookeeper:zookeeper-jute|3.5.7|间接依赖|maven|
|io.swagger:swagger-models|1.5.18|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|间接依赖|maven|
|org.apache.shenyu:shenyu-client-core|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-sync-data-http|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-redirect|2.6.1-SNAPSHOT|直接依赖|maven|
|org.ow2.asm:asm|9.3|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.13.5|间接依赖|maven|
|io.reactivex:rxjava-reactive-streams|1.2.1|直接依赖|maven|
|org.springframework.security:spring-security-rsa|1.0.10.RELEASE|间接依赖|maven|
|org.apache.shenyu:shenyu-client-alibaba-dubbo|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-response|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-register-common|2.6.1-SNAPSHOT|直接依赖|maven|
|com.netflix.eureka:eureka-core|1.10.17|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-actuator|2.7.13|直接依赖|maven|
|io.netty:netty-handler-proxy|4.1.94.Final|间接依赖|maven|
|org.apache.curator:curator-x-discovery|4.2.0|间接依赖|maven|
|com.tencent.tars:tars-client|1.7.2|直接依赖|maven|
|org.springframework:spring-messaging|5.3.28|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-param-mapping|2.6.1-SNAPSHOT|直接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.68|间接依赖|maven|
|org.springframework:spring-tx|5.3.28|间接依赖|maven|
|org.apache.shenyu:shenyu-common|2.6.1-SNAPSHOT|直接依赖|maven|
|com.dyuproject.protostuff:protostuff-api|1.0.8|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-grpc|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-register-client-nacos|2.6.1-SNAPSHOT|直接依赖|maven|
|org.thymeleaf:thymeleaf-spring5|3.0.15.RELEASE|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.28|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-oauth2|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-sync-data-nacos|2.6.1-SNAPSHOT|直接依赖|maven|
|joda-time:joda-time|2.10.14|间接依赖|maven|
|org.apache.shiro:shiro-core|1.8.0|间接依赖|maven|
|javax.mail:javax.mail-api|1.6.2|直接依赖|maven|
|io.netty:netty-transport-sctp|4.1.94.Final|间接依赖|maven|
|io.kubernetes:client-java-api-fluent|17.0.2|间接依赖|maven|
|io.perfmark:perfmark-api|0.25.0|间接依赖|maven|
|com.netflix.hystrix:hystrix-core|1.4.3|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-sync-data-zookeeper|2.6.1-SNAPSHOT|直接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.94.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.7.13|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-logging-elasticsearch|2.6.1-SNAPSHOT|直接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|org.apache.shenyu:shenyu-plguin-transform|2.6.1-SNAPSHOT|直接依赖|maven|
|net.minidev:accessors-smart|2.4.11|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-dubbo-common|2.6.1-SNAPSHOT|直接依赖|maven|
|com.google.protobuf:protobuf-java|3.21.12|直接依赖|maven|
|com.alibaba:fastjson|1.2.71|间接依赖|maven|
|io.zipkin.brave:brave|5.16.0|间接依赖|maven|
|com.alipay.sofa:sofa-rpc-all|5.7.6|直接依赖|maven|
|ch.qos.logback:logback-core|1.2.12|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.8.4|间接依赖|maven|
|com.esotericsoftware:minlog|1.3.0|间接依赖|maven|
|com.baidu.cloud:starlight-all|2022.2.0|间接依赖|maven|
|org.apache.curator:curator-framework|4.3.0|直接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|直接依赖|maven|
|com.google.guava:guava|31.1-jre|直接依赖|maven|
|org.apache.shenyu:shenyu-sdk-okhttp|2.6.1-SNAPSHOT|直接依赖|maven|
|io.etcd:jetcd-grpc|0.7.3|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-netflix-eureka-client|3.1.2|直接依赖|maven|
|org.springframework.cloud:spring-cloud-context|3.1.2|间接依赖|maven|
|io.prometheus:simpleclient_common|0.15.0|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-cryptor|2.6.1-SNAPSHOT|直接依赖|maven|
|org.jboss.resteasy:resteasy-client|3.6.3.Final|间接依赖|maven|
|io.netty:netty-codec|4.1.94.Final|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-divide|2.6.1-SNAPSHOT|直接依赖|maven|
|javax.ws.rs:jsr311-api|1.1.1|间接依赖|maven|
|org.jboss.spec.javax.xml.bind:jboss-jaxb-api_2.3_spec|1.0.1.Final|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-http-brave|1.0.33|间接依赖|maven|
|io.micrometer:micrometer-registry-prometheus|1.9.12|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-client-common|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-logging-aliyun-sls|2.6.1-SNAPSHOT|直接依赖|maven|
|org.unbescape:unbescape|1.1.6.RELEASE|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-global|2.6.1-SNAPSHOT|直接依赖|maven|
|net.bytebuddy:byte-buddy-agent|1.12.23|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-afterburner|2.13.5|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-netflix-ribbon|2.2.10.RELEASE|间接依赖|maven|
|org.springframework:spring-oxm|5.3.28|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-logging-tencent-cls|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-registry|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.pulsar:bouncy-castle-bc|2.10.1|间接依赖|maven|
|com.alibaba.cloud:spring-cloud-starter-alibaba-nacos-discovery|2021.0.1.0|直接依赖|maven|
|com.dyuproject.protostuff:protostuff-runtime|1.0.8|直接依赖|maven|
|org.apache.shenyu:shenyu-protocol-grpc|2.6.1-SNAPSHOT|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.7.13|直接依赖|maven|
|io.netty:netty-codec-redis|4.1.94.Final|间接依赖|maven|
|org.springframework.security:spring-security-oauth2-client|5.3.10.RELEASE|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-httpclient|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-rewrite|2.6.1-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.5|直接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|org.apache.shiro:shiro-spring|1.8.0|间接依赖|maven|
|io.kubernetes:client-java-api|17.0.2|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-http|1.0.33|直接依赖|maven|
|org.apache.shiro:shiro-web|1.8.0|间接依赖|maven|
|org.apache.shenyu:shenyu-register-client-server-apollo|2.6.1-SNAPSHOT|直接依赖|maven|
|javax.servlet:javax.servlet-api|4.0.1|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-logging-tencent-cls|2.6.1-SNAPSHOT|直接依赖|maven|
|com.google.inject:guice|4.1.0|间接依赖|maven|
|com.weibo:motan-registry-zookeeper|1.2.1|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-logging-kafka|2.6.1-SNAPSHOT|直接依赖|maven|
|org.springframework.plugin:spring-plugin-core|1.2.0.RELEASE|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.6.21|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-logging-huawei-lts|2.6.1-SNAPSHOT|直接依赖|maven|
|io.netty:netty-codec-dns|4.1.94.Final|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-casdoor|2.6.1-SNAPSHOT|直接依赖|maven|
|org.springframework.boot:spring-boot|2.7.13|间接依赖|maven|
|com.clickhouse:clickhouse-http-client|0.3.2-patch11|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-resilience4j|2.6.1-SNAPSHOT|直接依赖|maven|
|com.baidu.cloud:spring-cloud-starter-baidu-starlight|2022.2.0|直接依赖|maven|
|org.apache.logging.log4j:log4j-1.2-api|2.17.2|直接依赖|maven|
|org.apache.pulsar:pulsar-client-api|2.10.1|间接依赖|maven|
|io.netty:netty-all|4.1.94.Final|直接依赖|maven|
|org.apache.commons:commons-compress|1.22|间接依赖|maven|
|io.lettuce:lettuce-core|6.1.10.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator|2.7.13|间接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.94.Final|间接依赖|maven|
|org.apache.shenyu:shenyu-discovery-zookeeper|2.6.1-SNAPSHOT|直接依赖|maven|
|org.springframework.security:spring-security-crypto|5.7.9|间接依赖|maven|
|net.bytebuddy:byte-buddy-agent|1.12.6|直接依赖|maven|
|org.objenesis:objenesis|2.2|间接依赖|maven|
|com.dyuproject.protostuff:protostuff-collectionschema|1.0.8|间接依赖|maven|
|com.tencentcloudapi.cls:tencentcloud-cls-sdk-java|1.0.14|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-tars|2.6.1-SNAPSHOT|直接依赖|maven|
|commons-cli:commons-cli|1.2|间接依赖|maven|
|io.vavr:vavr-match|0.10.2|间接依赖|maven|
|jakarta.json:jakarta.json-api|2.0.1|直接依赖|maven|
|io.netty:netty-resolver-dns|4.1.94.Final|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.76|间接依赖|maven|
|org.apache.shenyu:shenyu-client-dubbo-common|2.6.1-SNAPSHOT|直接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.53.0|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-netflix-archaius|2.2.10.RELEASE|间接依赖|maven|
|com.stoyanr:evictor|1.0.0|间接依赖|maven|
|com.github.vlsi.compactmap:compactmap|2.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.12.3|直接依赖|maven|
|org.springframework:spring-websocket|5.3.28|间接依赖|maven|
|com.beust:jcommander|1.78|间接依赖|maven|
|com.thoughtworks.xstream:xstream|1.4.18|间接依赖|maven|
|commons-logging:commons-logging|1.1.3|间接依赖|maven|
|org.springframework.data:spring-data-keyvalue|2.7.13|间接依赖|maven|
|io.netty:netty-codec-haproxy|4.1.94.Final|间接依赖|maven|
|com.sun.mail:javax.mail|1.6.2|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.7.13|直接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|com.squareup.okhttp3:okhttp|4.9.3|直接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|org.springframework:spring-beans|5.3.28|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-api|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.pulsar:pulsar-client-admin-api|2.10.1|间接依赖|maven|
|com.nimbusds:nimbus-jose-jwt|9.10|间接依赖|maven|
|org.springframework.cloud:spring-cloud-loadbalancer|3.1.2|间接依赖|maven|
|org.mybatis:mybatis|3.5.9|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-sync-data-consul|2.6.1-SNAPSHOT|直接依赖|maven|
|org.thymeleaf.extras:thymeleaf-extras-java8time|3.0.4.RELEASE|间接依赖|maven|
|io.jsonwebtoken:jjwt-jackson|0.11.5|直接依赖|maven|
|com.netflix.netflix-commons:netflix-eventbus|0.3.0|间接依赖|maven|
|com.caucho:hessian|4.0.38|直接依赖|maven|
|io.zipkin.brave:brave-instrumentation-http|5.16.0|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-uri|2.6.1-SNAPSHOT|直接依赖|maven|
|net.jpountz.lz4:lz4|1.3.0|间接依赖|maven|
|org.apache.shenyu:shenyu-registry-consul|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-sofa|2.6.1-SNAPSHOT|直接依赖|maven|
|com.ctrip.framework.apollo:apollo-openapi|2.1.0|直接依赖|maven|
|com.alipay.sofa:hessian|3.3.7|间接依赖|maven|
|org.bouncycastle:bcutil-jdk15on|1.69|间接依赖|maven|
|com.github.fge:json-patch|1.9|间接依赖|maven|
|org.springframework.cloud:spring-cloud-netflix-archaius|2.2.10.RELEASE|间接依赖|maven|
|io.zipkin.reporter2:zipkin-sender-kafka08|2.7.4|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-general-context|2.6.1-SNAPSHOT|直接依赖|maven|
|io.prometheus:simpleclient_tracer_otel|0.15.0|间接依赖|maven|
|com.squareup.okhttp3:logging-interceptor|4.9.3|间接依赖|maven|
|co.elastic.clients:elasticsearch-java|8.2.3|直接依赖|maven|
|org.jboss.resteasy:resteasy-jaxrs|3.6.3.Final|间接依赖|maven|
|io.projectreactor:reactor-core|3.4.30|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-logging-pulsar|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-client-motan|2.6.1-SNAPSHOT|直接依赖|maven|
|com.alipay.sofa.lookout:lookout-api|1.4.1|间接依赖|maven|
|com.nimbusds:content-type|2.0|间接依赖|maven|
|org.apache.dubbo:dubbo|3.1.1|直接依赖|maven|
|org.apache.shenyu:shenyu-registry-etcd|2.6.1-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.5|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.13.5|间接依赖|maven|
|com.netflix.netflix-commons:netflix-infix|0.3.0|间接依赖|maven|
|com.h2database:h2|1.4.200|直接依赖|maven|
|org.apache.shenyu:shenyu-register-client-polaris|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.rocketmq:rocketmq-client|4.9.3|直接依赖|maven|
|org.springframework:spring-jcl|5.3.28|间接依赖|maven|
|com.clickhouse:clickhouse-client|0.3.2-patch11|间接依赖|maven|
|io.jsonwebtoken:jjwt-impl|0.11.5|直接依赖|maven|
|io.netty.incubator:netty-incubator-codec-classes-quic|0.0.45.Final|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-websocket|2.6.1-SNAPSHOT|直接依赖|maven|
|org.postgresql:postgresql|42.3.8|直接依赖|maven|
|io.projectreactor.addons:reactor-extra|3.4.10|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-grpc|2.6.1-SNAPSHOT|直接依赖|maven|
|org.javatuples:javatuples|1.2|直接依赖|maven|
|org.codehaus.jettison:jettison|1.4.0|间接依赖|maven|
|org.apache.shenyu:shenyu-register-client-server-etcd|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-metrics|2.6.1-SNAPSHOT|直接依赖|maven|
|io.netty:netty-codec-mqtt|4.1.94.Final|间接依赖|maven|
|org.springframework.data:spring-data-ldap|2.7.13|直接依赖|maven|
|org.apache.shenyu:shenyu-protocol-mqtt|2.6.1-SNAPSHOT|直接依赖|maven|
|io.etcd:jetcd-api|0.7.3|间接依赖|maven|
|commons-io:commons-io|2.11.0|直接依赖|maven|
|io.springfox:springfox-spring-web|2.9.2|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-brpc|2.6.1-SNAPSHOT|直接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.69|间接依赖|maven|
|org.springframework:spring-core|5.3.28|间接依赖|maven|
|org.springframework:spring-aop|5.3.28|间接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.68|间接依赖|maven|
|com.auth0:java-jwt|3.12.0|直接依赖|maven|
|org.springframework.ldap:spring-ldap-core|2.4.1|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|com.github.stephenc.jcip:jcip-annotations|1.0-1|间接依赖|maven|
|org.springframework.data:spring-data-commons|2.7.13|间接依赖|maven|
|org.apache.shenyu:shenyu-client-spring-websocket|2.6.1-SNAPSHOT|直接依赖|maven|
|org.springframework:spring-jdbc|5.3.28|间接依赖|maven|
|org.apache.shenyu:shenyu-sync-data-api|2.6.1-SNAPSHOT|直接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.13|直接依赖|maven|
|com.codahale.metrics:metrics-core|3.0.1|间接依赖|maven|
|io.netty:netty-codec-http|4.1.94.Final|直接依赖|maven|
|io.etcd:jetcd-core|0.7.3|直接依赖|maven|
|io.zipkin.reporter2:zipkin-reporter|2.16.3|间接依赖|maven|
|io.prometheus:simpleclient_tracer_otel_agent|0.15.0|间接依赖|maven|
|io.netty:netty-common|4.1.94.Final|间接依赖|maven|
|org.apache.shiro:shiro-config-core|1.8.0|间接依赖|maven|
|com.netflix.hystrix:hystrix-metrics-event-stream|1.5.18|直接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.16|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.14.0|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-logging-huawei-lts|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-sync-data-apollo|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.5|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.5|直接依赖|maven|
|org.apache.shenyu:shenyu-sync-data-consul|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-casdoor|2.6.1-SNAPSHOT|直接依赖|maven|
|javax.validation:validation-api|2.0.1.Final|间接依赖|maven|
|com.netflix.netflix-commons:netflix-statistics|0.1.1|间接依赖|maven|
|org.apache.shenyu:shenyu-disruptor|2.6.1-SNAPSHOT|直接依赖|maven|
|org.owasp.encoder:encoder|1.2.2|间接依赖|maven|
|org.aspectj:aspectjweaver|1.9.7|间接依赖|maven|
|com.netflix.ribbon:ribbon-loadbalancer|2.3.0|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-gateway|2.6.1-SNAPSHOT|直接依赖|maven|
|com.101tec:zkclient|0.11|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-logging-console|2.6.1-SNAPSHOT|直接依赖|maven|
|com.weibo:breeze-core|0.1.4|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-param-mapping|2.6.1-SNAPSHOT|直接依赖|maven|
|io.zipkin.reporter2:zipkin-sender-kafka11|2.7.4|间接依赖|maven|
|com.flipkart.zjsonpatch:zjsonpatch|0.4.13|间接依赖|maven|
|org.attoparser:attoparser|2.0.5.RELEASE|间接依赖|maven|
|io.zipkin.reporter2:zipkin-reporter-brave|2.16.3|间接依赖|maven|
|com.alibaba.csp:sentinel-core|1.8.3|直接依赖|maven|
|io.projectreactor:reactor-test|3.4.30|直接依赖|maven|
|org.mybatis:mybatis-spring|2.0.7|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-cache-redis|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-key-auth|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-register-client-http|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-sync-data-websocket|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-sofa|2.6.1-SNAPSHOT|直接依赖|maven|
|io.kubernetes:client-java|17.0.2|间接依赖|maven|
|org.apache.shenyu:shenyu-sdk-core|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-apache-dubbo|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-register-client-api|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-client-autoconfig|2.6.1-SNAPSHOT|直接依赖|maven|
|com.github.jsqlparser:jsqlparser|4.5|间接依赖|maven|
|io.projectreactor.netty.incubator:reactor-netty-incubator-quic|0.0.22|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-request|2.6.1-SNAPSHOT|直接依赖|maven|
|io.springfox:springfox-core|2.9.2|间接依赖|maven|
|org.ow2.asm:asm-tree|9.2|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-logging-common|2.6.1-SNAPSHOT|直接依赖|maven|
|org.springframework:spring-webflux|5.3.28|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-tars|2.6.1-SNAPSHOT|直接依赖|maven|
|io.gsonfire:gson-fire|1.8.5|间接依赖|maven|
|commons-configuration:commons-configuration|1.8|间接依赖|maven|
|org.jboss.spec.javax.ws.rs:jboss-jaxrs-api_2.1_spec|1.0.2.Final|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-logging-rocketmq|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-modify-response|2.6.1-SNAPSHOT|直接依赖|maven|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|org.jboss.resteasy:resteasy-netty4|3.6.3.Final|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-redirect|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-register-client-server-consul|2.6.1-SNAPSHOT|直接依赖|maven|
|com.h2database:h2|2.1.214|间接依赖|maven|
|com.netflix.archaius:archaius-core|0.7.7|间接依赖|maven|
|org.apache.shenyu:shenyu-registry-zookeeper|2.6.1-SNAPSHOT|直接依赖|maven|
|org.antlr:stringtemplate|3.2.1|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.94.Final|间接依赖|maven|
|org.springframework.cloud:spring-cloud-commons|3.1.2|直接依赖|maven|
|org.apache.shenyu:shenyu-register-client-server-zookeeper|2.6.1-SNAPSHOT|直接依赖|maven|
|io.netty:netty-transport-udt|4.1.94.Final|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|io.swagger:swagger-core|1.5.18|间接依赖|maven|
|com.netflix.eureka:eureka-client|1.10.17|直接依赖|maven|
|io.springfox:springfox-swagger2|2.9.2|直接依赖|maven|
|io.grpc:grpc-api|1.53.0|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.76|间接依赖|maven|
|io.netty:netty-handler|4.1.94.Final|间接依赖|maven|
|com.netflix.ribbon:ribbon-httpclient|2.3.0|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.2|间接依赖|maven|
|io.vavr:vavr|0.10.2|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-waf|2.6.1-SNAPSHOT|直接依赖|maven|
|io.swagger:swagger-annotations|1.6.9|间接依赖|maven|
|com.alibaba.csp:sentinel-reactor-adapter|1.8.3|直接依赖|maven|
|org.apache.shenyu:shenyu-protocol-tcp|2.6.1-SNAPSHOT|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-webflux|2.7.13|直接依赖|maven|
|org.apache.httpcomponents:httpmime|4.5.14|间接依赖|maven|
|org.apache.shenyu:shenyu-register-client-zookeeper|2.6.1-SNAPSHOT|直接依赖|maven|
|io.swagger:swagger-annotations|1.5.18|间接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|com.alipay.sofa:tracer-core|3.0.8|间接依赖|maven|
|io.micrometer:micrometer-core|1.9.12|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-brpc|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-tcp|2.6.1-SNAPSHOT|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.6.21|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-sign|2.6.1-SNAPSHOT|直接依赖|maven|
|com.sun.jersey:jersey-core|1.19.1|间接依赖|maven|
|org.apache.shenyu:shenyu-client-brpc|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-registry-core|2.6.1-SNAPSHOT|直接依赖|maven|
|org.antlr:antlr-runtime|3.4|间接依赖|maven|
|io.grpc:grpc-stub|1.53.0|直接依赖|maven|
|commons-lang:commons-lang|2.6|间接依赖|maven|
|org.apache.shenyu:shenyu-client-grpc|2.6.1-SNAPSHOT|直接依赖|maven|
|com.sun.jersey:jersey-client|1.19.1|间接依赖|maven|
|io.prometheus:simpleclient_tracer_common|0.15.0|间接依赖|maven|
|com.tencent.tars:tars-net|1.7.2|间接依赖|maven|
|io.grpc:grpc-grpclb|1.48.0|间接依赖|maven|
|io.zipkin.reporter2:zipkin-sender-urlconnection|2.7.4|间接依赖|maven|
|org.reflections:reflections|0.9.11|直接依赖|maven|
|org.jboss.resteasy:resteasy-jackson2-provider|3.6.3.Final|间接依赖|maven|
|io.opentracing.brave:brave-opentracing|0.31.1|间接依赖|maven|
|org.apache.shiro:shiro-spring-boot-starter|1.8.0|间接依赖|maven|
|org.apache.shiro:shiro-spring-boot-web-starter|1.8.0|直接依赖|maven|
|com.alipay.sofa:bolt|1.5.6|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-global|2.6.1-SNAPSHOT|直接依赖|maven|
|com.netflix.servo:servo-core|0.12.21|间接依赖|maven|
|io.opentracing:opentracing-api|0.31.0|间接依赖|maven|
|org.springframework.security:spring-security-core|5.7.9|间接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|6.2.1|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-waf|2.6.1-SNAPSHOT|直接依赖|maven|
|javax.ws.rs:javax.ws.rs-api|2.1|间接依赖|maven|
|org.bouncycastle:bcprov-ext-jdk15on|1.69|间接依赖|maven|
|org.apache.shenyu:shenyu-client-apache-dubbo|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-logging-console|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-jwt|2.6.1-SNAPSHOT|直接依赖|maven|
|org.ow2.asm:asm|9.2|间接依赖|maven|
|org.apache.rocketmq:rocketmq-srvutil|4.9.3|间接依赖|maven|
|org.apache.shenyu:shenyu-register-client-etcd|2.6.1-SNAPSHOT|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.7.13|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-metrics|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-jwt|2.6.1-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.5|间接依赖|maven|
|com.alipay.sofa.common:sofa-common-tools|1.0.18|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.94.Final|间接依赖|maven|
|io.reactivex:rxnetty-servo|0.4.9|间接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|2.9.0|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-response|2.6.1-SNAPSHOT|直接依赖|maven|
|com.netflix.netflix-commons:netflix-commons-util|0.1.1|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-cache-spi|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-registry-apollo|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-kubernetes-controller|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-springcloud|2.6.1-SNAPSHOT|直接依赖|maven|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.7.13|间接依赖|maven|
|io.github.resilience4j:resilience4j-reactor|1.7.1|直接依赖|maven|
|com.alibaba.fastjson2:fastjson2|2.0.14|间接依赖|maven|
|org.apache.kafka:kafka-clients|3.2.0|直接依赖|maven|
|io.netty:netty-codec-xml|4.1.94.Final|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.94.Final|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.9.3|直接依赖|maven|
|io.netty:netty-transport|4.1.94.Final|间接依赖|maven|
|io.springfox:springfox-schema|2.9.2|间接依赖|maven|
|org.thymeleaf:thymeleaf|3.0.15.RELEASE|间接依赖|maven|
|net.minidev:json-smart|2.4.11|间接依赖|maven|
|com.tencent.polaris:polaris-all|1.13.0|直接依赖|maven|
|org.jboss.spec.javax.annotation:jboss-annotations-api_1.3_spec|1.0.1.Final|间接依赖|maven|
|io.github.huaweicloud:lts-sdk-common|1.0.1|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-logging-kafka|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-sentinel|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.zookeeper:zookeeper|3.5.7|间接依赖|maven|
|com.github.fge:btf|1.2|间接依赖|maven|
|com.weibo:motan-core|1.2.1|直接依赖|maven|
|org.java-websocket:Java-WebSocket|1.5.0|直接依赖|maven|
|io.etcd:jetcd-common|0.7.3|间接依赖|maven|
|com.jayway.jsonpath:json-path|2.7.0|间接依赖|maven|
|org.assertj:assertj-core|3.22.0|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-core|1.0.33|直接依赖|maven|
|org.apache.shenyu:shenyu-discovery-api|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-client-springmvc|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-sync-data-polaris|2.6.1-SNAPSHOT|直接依赖|maven|
|com.baidu.cloud:spring-cloud-baidu-thirdparty-commons|2022.2.0|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-logging-pulsar|2.6.1-SNAPSHOT|直接依赖|maven|
|com.netflix.servo:servo-internal|0.10.1|间接依赖|maven|
|org.checkerframework:checker-qual|3.12.0|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.94.Final|间接依赖|maven|
|com.alibaba.spring:spring-context-support|1.0.11|间接依赖|maven|
|org.apache.shenyu:shenyu-register-client-server-polaris|2.6.1-SNAPSHOT|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.6.21|间接依赖|maven|
|org.apache.shenyu:shenyu-sync-data-nacos|2.6.1-SNAPSHOT|直接依赖|maven|
|com.lmax:disruptor|3.4.0|直接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.69|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-uri|2.6.1-SNAPSHOT|直接依赖|maven|
|io.opentracing:opentracing-mock|0.22.0|间接依赖|maven|
|org.apache.shenyu:shenyu-sdk-httpclient|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-client-sofa|2.6.1-SNAPSHOT|直接依赖|maven|
|org.springframework:spring-expression|5.3.28|间接依赖|maven|
|io.grpc:grpc-protobuf|1.53.0|直接依赖|maven|
|io.grpc:grpc-core|1.53.0|直接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|com.github.andrewoma.dexx:dexx-collections|0.2|间接依赖|maven|
|org.codehaus.woodstox:stax2-api|4.2.1|间接依赖|maven|
|org.apache.shenyu:shenyu-sync-data-apollo|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.16|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-logging-clickhouse|2.6.1-SNAPSHOT|直接依赖|maven|
|io.lettuce:lettuce-core|6.1.2.RELEASE|直接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-context-path|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.pulsar:pulsar-client|2.10.1|直接依赖|maven|
|org.springframework.plugin:spring-plugin-metadata|1.2.0.RELEASE|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.5|间接依赖|maven|
|org.springframework.cloud:spring-cloud-netflix-eureka-client|3.1.2|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-httpclient|2.6.1-SNAPSHOT|直接依赖|maven|
|io.springfox:springfox-swagger-common|2.9.2|间接依赖|maven|
|com.google.code.gson:gson|2.9.0|直接依赖|maven|
|org.apache.shenyu:shenyu-bootstrap|2.6.1-SNAPSHOT|直接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-starter|2.2.2|直接依赖|maven|
|io.swagger:swagger-models|1.5.20|间接依赖|maven|
|io.prometheus:simpleclient_hotspot|0.15.0|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-logging-desensitize-api|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-motan|2.6.1-SNAPSHOT|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.5.1|间接依赖|maven|
|io.netty:netty-codec-memcache|4.1.94.Final|间接依赖|maven|
|com.dyuproject.protostuff:protostuff-core|1.0.8|直接依赖|maven|
|com.netflix.hystrix:hystrix-serialization|1.5.18|间接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.94.Final|间接依赖|maven|
|org.apache.curator:curator-recipes|4.3.0|直接依赖|maven|
|com.netflix.servo:servo-core|0.10.1|间接依赖|maven|
|org.apache.shiro:shiro-cache|1.8.0|间接依赖|maven|
|org.apache.kafka:kafka-clients|3.1.2|间接依赖|maven|
|io.kubernetes:client-java-spring-integration|17.0.2|直接依赖|maven|
|io.netty.incubator:netty-incubator-codec-native-quic|0.0.45.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-configuration-processor|2.7.13|直接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.3|间接依赖|maven|
|org.apache.shiro:shiro-event|1.8.0|间接依赖|maven|
|com.google.protobuf:protobuf-java-util|3.23.3|间接依赖|maven|
|com.squareup.okio:okio|2.8.0|间接依赖|maven|
|com.github.pagehelper:pagehelper|5.3.3|直接依赖|maven|
|io.github.x-stream:mxparser|1.2.2|间接依赖|maven|
|org.mapstruct:mapstruct|1.2.0.Final|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-logging-aliyun-sls|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-registry-api|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.commons:commons-collections4|4.4|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-cache-handler|2.6.1-SNAPSHOT|直接依赖|maven|
|com.netflix.hystrix:hystrix-core|1.5.18|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-reactor-netty|2.7.13|间接依赖|maven|
|org.yaml:snakeyaml|1.30|间接依赖|maven|
|org.casbin:casdoor-java-sdk|1.9.0|直接依赖|maven|
|io.netty:netty-resolver|4.1.94.Final|间接依赖|maven|
|com.tencent.tars:tars-context|1.7.2|间接依赖|maven|
|org.apache.rocketmq:rocketmq-common|4.9.3|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.13.5|间接依赖|maven|
|javax.activation:activation|1.1|间接依赖|maven|
|commons-digester:commons-digester|2.1|间接依赖|maven|
|com.squareup:javapoet|1.8.0|间接依赖|maven|
|com.jayway.jsonpath:json-path|2.4.0|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-context-path|2.6.1-SNAPSHOT|直接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|间接依赖|maven|
|org.apache.shenyu:shenyu-spring-boot-starter-plugin-cryptor|2.6.1-SNAPSHOT|直接依赖|maven|
|io.grpc:grpc-context|1.53.0|间接依赖|maven|
|org.apache.commons:commons-math|2.2|间接依赖|maven|
|io.reactivex:rxnetty|0.4.9|间接依赖|maven|
|org.springframework.security:spring-security-oauth2-core|5.7.9|间接依赖|maven|
|org.apache.oltu.oauth2:org.apache.oltu.oauth2.client|1.0.2|间接依赖|maven|
|org.apache.shenyu:shenyu-registry-nacos|2.6.1-SNAPSHOT|直接依赖|maven|
|org.checkerframework:checker-qual|3.5.0|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.76|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-mock|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-register-client-consul|2.6.1-SNAPSHOT|直接依赖|maven|
|com.netflix.ribbon:ribbon-core|2.3.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-thymeleaf|2.7.13|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.7.13|间接依赖|maven|
|org.bouncycastle:bcpkix-jdk18on|1.72|间接依赖|maven|
|org.apache.shiro:shiro-crypto-hash|1.8.0|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.9|间接依赖|maven|
|io.zipkin.brave:brave-tests|5.1.0|间接依赖|maven|
|io.grpc:grpc-netty|1.53.0|直接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.2.5.Final|间接依赖|maven|
|org.apache.shenyu:shenyu-register-client-apollo|2.6.1-SNAPSHOT|直接依赖|maven|
|org.javassist:javassist|3.21.0-GA|间接依赖|maven|
|io.zipkin.brave:brave|5.1.0|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|间接依赖|maven|
|com.netflix.archaius:archaius-core|0.4.1|间接依赖|maven|
|com.netflix.ribbon:ribbon|2.3.0|间接依赖|maven|
|org.apache.shenyu:shenyu-plugin-rewrite|2.6.1-SNAPSHOT|直接依赖|maven|
|org.apache.shenyu:shenyu-loadbalancer|2.6.1-SNAPSHOT|直接依赖|maven|
|io.github.resilience4j:resilience4j-timelimiter|1.7.1|直接依赖|maven|
|antlr:antlr|2.7.7|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-validation|2.7.13|直接依赖|maven|
|org.apache.shenyu:shenyu-plugin-cache-memory|2.6.1-SNAPSHOT|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)