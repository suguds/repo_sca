# alibaba/jetcache安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694410101992353792.svg)](https://www.murphysec.com/console/report/1694046928147738624/1694410101992353792)

仓库描述：JetCache is a Java cache framework.

仓库地址：[https://github.com/alibaba/jetcache](https://github.com/alibaba/jetcache)

| star：4185 | watch：166 | fork：955 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-23 09:30:06 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-24 02:04:13 | 组件总数：120 | 漏洞总数：14 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot在Cloud Foundry中部署存在路由限制绕过风险|访问控制不当|[MPS-2022-62845](https://www.oscs1024.com/hd/MPS-2022-62845)|CVE-2023-20873|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.springframework.boot:spring-boot-autoconfigure|2.7.5|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.82.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.yaml:snakeyaml|1.33|2.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.14.0||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.7.2|3.0.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.7.5|3.0.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.30|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|io.netty:netty-handler|4.1.84.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-expression|5.3.23|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-core|5.3.23|6.0.7|直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|95|Low|
|BSD-2-Clause|3|Low|
|MIT|5|Low|
|EPL-2.0|2|Low|
|自定义许可证|8|Low|
|BSD-3-Clause|2|Low|
|EPL-1.0|3|Low|
|JSON|1|Low|
|MIT-0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.springframework:spring-jcl|5.3.23|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator|2.7.5|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-redis|2.7.2|间接依赖|maven|
|org.jodd:jodd-core|5.1.6|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.13.4|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.14.0|直接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.2|间接依赖|maven|
|org.springframework:spring-beans|5.3.23|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.82.Final|间接依赖|maven|
|org.apache.commons:commons-pool2|2.11.1|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.2|间接依赖|maven|
|org.redisson:redisson|3.18.0|直接依赖|maven|
|org.checkerframework:checker-qual|3.19.0|间接依赖|maven|
|org.aspectj:aspectjweaver|1.9.9.1|直接依赖|maven|
|org.springframework.data:spring-data-redis|2.7.2|间接依赖|maven|
|org.springframework:spring-tx|5.3.22|间接依赖|maven|
|org.jboss.marshalling:jboss-marshalling-river|2.0.11.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.4|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.84.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.7.5|间接依赖|maven|
|com.alibaba:fastjson|1.2.83|直接依赖|maven|
|org.jboss.marshalling:jboss-marshalling|2.0.11.Final|间接依赖|maven|
|org.springframework:spring-test|5.3.23|直接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|io.netty:netty-codec|4.1.82.Final|间接依赖|maven|
|io.micrometer:micrometer-core|1.9.2|间接依赖|maven|
|org.springframework:spring-expression|5.3.23|间接依赖|maven|
|net.bytebuddy:byte-buddy-agent|1.12.18|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.84.Final|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|com.alicp.jetcache:jetcache-starter-redisson|2.7.4-SNAPSHOT|直接依赖|maven|
|org.springframework.boot:spring-boot-actuator|2.7.2|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.1|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.4|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-actuator|2.7.2|间接依赖|maven|
|com.alicp.jetcache:jetcache-autoconfigure|2.7.4-SNAPSHOT|直接依赖|maven|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.7.5|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.7.2|间接依赖|maven|
|com.esotericsoftware:reflectasm|1.11.3|间接依赖|maven|
|io.netty:netty-handler|4.1.82.Final|间接依赖|maven|
|io.netty:netty-buffer|4.1.84.Final|间接依赖|maven|
|org.springframework:spring-context-support|5.3.22|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.84.Final|间接依赖|maven|
|org.springframework.data:spring-data-commons|2.7.2|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.9.3|直接依赖|maven|
|io.micrometer:micrometer-core|1.9.5|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|org.springframework:spring-context|5.3.23|直接依赖|maven|
|org.springframework:spring-core|5.3.23|直接依赖|maven|
|com.esotericsoftware:minlog|1.3.0|间接依赖|maven|
|org.redisson:redisson-spring-data-27|3.18.0|间接依赖|maven|
|org.hamcrest:hamcrest-core|2.2|间接依赖|maven|
|org.objenesis:objenesis|2.5.1|间接依赖|maven|
|com.esotericsoftware:kryo|4.0.3|直接依赖|maven|
|com.alicp.jetcache:jetcache-redis-springdata|2.7.4-SNAPSHOT|直接依赖|maven|
|org.springframework.data:spring-data-commons|2.7.5|间接依赖|maven|
|io.lettuce:lettuce-core|6.1.10.RELEASE|直接依赖|maven|
|org.springframework.boot:spring-boot|2.7.5|间接依赖|maven|
|junit:junit|4.13.2|直接依赖|maven|
|org.json:json|20220320|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.18|间接依赖|maven|
|org.jodd:jodd-bean|5.1.6|间接依赖|maven|
|com.google.code.gson:gson|2.9.1|间接依赖|maven|
|io.netty:netty-transport|4.1.82.Final|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|com.alicp.jetcache:jetcache-anno-api|2.7.4-SNAPSHOT|直接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.82.Final|间接依赖|maven|
|org.hamcrest:hamcrest|2.2|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|io.netty:netty-codec|4.1.84.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.14.0|直接依赖|maven|
|io.projectreactor:reactor-core|3.4.24|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.5|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.14.0|直接依赖|maven|
|javax.cache:cache-api|1.1.1|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.5|间接依赖|maven|
|com.alibaba.fastjson2:fastjson2|2.0.39|直接依赖|maven|
|org.springframework.data:spring-data-keyvalue|2.7.2|间接依赖|maven|
|io.reactivex.rxjava3:rxjava|3.1.5|间接依赖|maven|
|io.netty:netty-common|4.1.82.Final|间接依赖|maven|
|io.projectreactor:reactor-core|3.3.22.RELEASE|间接依赖|maven|
|redis.clients:jedis|4.3.1|直接依赖|maven|
|io.netty:netty-buffer|4.1.82.Final|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.11|直接依赖|maven|
|org.springframework:spring-context-support|5.3.23|间接依赖|maven|
|org.mockito:mockito-core|4.6.1|直接依赖|maven|
|io.netty:netty-handler|4.1.84.Final|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.13|直接依赖|maven|
|org.springframework:spring-aop|5.3.23|间接依赖|maven|
|org.redisson:redisson-spring-boot-starter|3.18.0|直接依赖|maven|
|org.springframework:spring-tx|5.3.23|间接依赖|maven|
|com.esotericsoftware.kryo:kryo5|5.5.0|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.3|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.82.Final|间接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|com.google.code.gson:gson|2.8.9|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-redis|2.7.5|直接依赖|maven|
|com.alicp.jetcache:jetcache-redisson|2.7.4-SNAPSHOT|直接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|com.alicp.jetcache:jetcache-core|2.7.4-SNAPSHOT|直接依赖|maven|
|io.netty:netty-resolver|4.1.84.Final|间接依赖|maven|
|io.netty:netty-common|4.1.84.Final|间接依赖|maven|
|org.springframework:spring-oxm|5.3.23|间接依赖|maven|
|org.ow2.asm:asm|5.0.4|间接依赖|maven|
|io.netty:netty-transport|4.1.84.Final|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.11|直接依赖|maven|
|org.yaml:snakeyaml|1.33|间接依赖|maven|
|io.netty:netty-resolver|4.1.82.Final|间接依赖|maven|
|org.springframework.data:spring-data-redis|2.7.5|直接依赖|maven|
|org.springframework:spring-oxm|5.3.22|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-actuator|2.7.5|间接依赖|maven|
|com.alicp.jetcache:jetcache-redis|2.7.4-SNAPSHOT|直接依赖|maven|
|org.mvel:mvel2|2.4.14.Final|直接依赖|maven|
|org.yaml:snakeyaml|1.30|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.4|间接依赖|maven|
|org.springframework.data:spring-data-keyvalue|2.7.5|间接依赖|maven|
|com.alicp.jetcache:jetcache-anno|2.7.4-SNAPSHOT|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.10.0|间接依赖|maven|
|com.alicp.jetcache:jetcache-redis-lettuce|2.7.4-SNAPSHOT|直接依赖|maven|
|org.objenesis:objenesis|3.2|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)