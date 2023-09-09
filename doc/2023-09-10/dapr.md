# dapr/dapr安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700571902237261824.svg)](https://www.murphysec.com/console/report/1700210873867223040/1700571902237261824)

仓库描述：Dapr is a portable, event-driven, runtime for building distributed applications across cloud and edge.

仓库地址：[https://github.com/dapr/dapr](https://github.com/dapr/dapr)

| star：22090 | watch：428 | fork：1733 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-09 11:54:44 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-10 02:14:44 | 组件总数：594 | 漏洞总数：54 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|plexus-utils <3.0.16 命令注入漏洞|OS命令注入|[MPS-2018-0091](https://www.oscs1024.com/hd/MPS-2018-0091)|CVE-2017-1000487|严重|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|Pivotal Spring Framework 反射文件下载 (RFD) 漏洞|路径遍历|[MPS-2020-13322](https://www.oscs1024.com/hd/MPS-2020-13322)|CVE-2020-5421|中危|
|Junit 信息泄露漏洞|不安全的临时文件|[MPS-2020-15183](https://www.oscs1024.com/hd/MPS-2020-15183)|CVE-2020-15250|中危|
|Apache Tomcat HTTP请求走私漏洞|HTTP请求走私|[MPS-2020-15344](https://www.oscs1024.com/hd/MPS-2020-15344)|CVE-2020-13943|中危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2020-17486](https://www.oscs1024.com/hd/MPS-2020-17486)|CVE-2020-17527|高危|
|Apache Tomcat 拒绝服务漏洞|拒绝服务|[MPS-2020-9541](https://www.oscs1024.com/hd/MPS-2020-9541)|CVE-2020-11996|高危|
|Apache Tomcat 授权问题漏洞|身份验证不当|[MPS-2021-10264](https://www.oscs1024.com/hd/MPS-2021-10264)|CVE-2021-30640|中危|
|JetBrains Kotlin <1.4.21 不正确的默认权限漏洞|缺省权限不正确|[MPS-2021-1082](https://www.oscs1024.com/hd/MPS-2021-1082)|CVE-2020-29582|中危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-1722](https://www.oscs1024.com/hd/MPS-2021-1722)|CVE-2021-24122|中危|
|Spring Framework <5.3.14 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18854](https://www.oscs1024.com/hd/MPS-2021-18854)|CVE-2021-22060|中危|
|Pivotal Spring Framework 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18890](https://www.oscs1024.com/hd/MPS-2021-18890)|CVE-2021-22096|中危|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|Apache Tomcat 信息泄露漏洞|HTTP请求走私|[MPS-2021-2309](https://www.oscs1024.com/hd/MPS-2021-2309)|CVE-2021-25122|高危|
|Apache Tomcat 远程代码执行漏洞|代码注入|[MPS-2021-2466](https://www.oscs1024.com/hd/MPS-2021-2466)|CVE-2021-25329|高危|
|Apache Tomcat 拒绝服务漏洞|拒绝服务|[MPS-2021-31848](https://www.oscs1024.com/hd/MPS-2021-31848)|CVE-2021-41079|高危|
|Quality Open Software logback JNDI注入漏洞|反序列化|[MPS-2021-33911](https://www.oscs1024.com/hd/MPS-2021-33911)|CVE-2021-42550|中危|
|Apache Tomcat 条件竞争漏洞|竞争条件|[MPS-2021-37218](https://www.oscs1024.com/hd/MPS-2021-37218)|CVE-2021-43980|低危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|Spring Framework权限许可和访问控制问题漏洞|权限管理不当|[MPS-2021-7485](https://www.oscs1024.com/hd/MPS-2021-7485)|CVE-2021-22118|高危|
|Jakarta Expression Language <=3.0.3 存在输入验证错误漏洞|表达式语言注入|[MPS-2021-7671](https://www.oscs1024.com/hd/MPS-2021-7671)|CVE-2021-28170|中危|
|Apache Tomcat 环境问题漏洞|HTTP请求走私|[MPS-2021-9711](https://www.oscs1024.com/hd/MPS-2021-9711)|CVE-2021-33037|中危|
|Vmware Spring Framework 安全漏洞|不加限制或调节的资源分配|[MPS-2022-1080](https://www.oscs1024.com/hd/MPS-2022-1080)|CVE-2022-22950|中危|
|Pivotal Spring Framework 安全限制绕过漏洞|大小写敏感处理不恰当|[MPS-2022-1098](https://www.oscs1024.com/hd/MPS-2022-1098)|CVE-2022-22968|中危|
|Spring Framework spring-beans 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1101](https://www.oscs1024.com/hd/MPS-2022-1101)|CVE-2022-22970|中危|
|plexus-utils <3.0.24 路径遍历漏洞|路径遍历|[MPS-2022-11760](https://www.oscs1024.com/hd/MPS-2022-11760)||中危|
|plexus-utils <3.0.24 XXE 漏洞|XPath盲注|[MPS-2022-11786](https://www.oscs1024.com/hd/MPS-2022-11786)||低危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|Logback SSL证书校验不当漏洞|中间人攻击|[MPS-2022-12411](https://www.oscs1024.com/hd/MPS-2022-12411)||中危|
|FasterXML Jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2022-12500](https://www.oscs1024.com/hd/MPS-2022-12500)||中危|
|Apache Tomcat 本地权限提升漏洞|检查时间与使用时间(TOCTOU)的竞争条件|[MPS-2022-1351](https://www.oscs1024.com/hd/MPS-2022-1351)|CVE-2022-23181|高危|
|JetBrains Kotlin <1.6.0 存在锁定不当漏洞|加锁机制不恰当|[MPS-2022-3233](https://www.oscs1024.com/hd/MPS-2022-3233)|CVE-2022-24329|中危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|spring-beans 远程代码执行漏洞(Spring4Shell)|表达式语言注入|[MPS-2022-6820](https://www.oscs1024.com/hd/MPS-2022-6820)|CVE-2022-22965|严重|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2023-8438](https://www.oscs1024.com/hd/MPS-2023-8438)|CVE-2021-46877|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Dapr 授权问题漏洞|身份验证不当|[MPS-rdo6-f1cq](https://www.oscs1024.com/hd/MPS-rdo6-f1cq)|CVE-2023-37918|高危|
|Apache Tomcat FORM 重定向漏洞|跨站重定向|[MPS-uy56-j8e4](https://www.oscs1024.com/hd/MPS-uy56-j8e4)|CVE-2023-41080|低危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.apache.tomcat.embed:tomcat-embed-core|9.0.35|11.0.0-m6|间接依赖|强烈建议修复|C:0|H:6|M:4|L:2|
|org.yaml:snakeyaml|1.26|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|org.springframework:spring-beans|5.2.6.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|com.squareup.okio:okio|2.2.2|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.11.0|2.14.0-rc1|直接依赖|建议修复|C:0|H:1|M:5|L:0|
|github.com/dapr/dapr|v1.9.4-0.20221212235750-ac9256f214e0|1.11.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.codehaus.plexus:plexus-utils|3.0|3.0.24|间接依赖|建议修复|C:1|H:0|M:1|L:1|
|org.springframework:spring-context|5.2.6.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|github.com/dapr/dapr|v0.0.0|1.11.2|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|ch.qos.logback:logback-core|1.2.3|1.2.8|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|github.com/dapr/dapr|v0.0.0-00010101000000-000000000000|1.11.2|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.google.protobuf:protobuf-java|3.12.0|3.21.7|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-web|5.2.6.RELEASE|6.0.0|间接依赖|建议修复|C:1|H:1|M:1|L:0|
|github.com/dapr/dapr|v1.7.4|1.11.2|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|commons-io:commons-io|2.2|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.glassfish:jakarta.el|3.0.3|3.0.4|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|5.2.6.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|com.google.guava:guava|29.0-android|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:1|
|org.springframework:spring-core|5.2.6.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.3.0.RELEASE|3.0.7|直接依赖|可选修复|C:0|H:1|M:0|L:0|
|junit:junit|4.13|4.13.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.jetbrains.kotlin:kotlin-stdlib|1.3.72|1.6.0|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.code.gson:gson|2.8.6|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|273|Low|
|MIT|194|Low|
|自定义许可证|5|Low|
|MPL-2.0|13|Low|
|BSD-3-Clause|91|Low|
|EPL-2.0|3|Low|
|BSD-2-Clause|10|Low|
|LGPL-2.0|1|Medium|
|ISC|5|Low|
|EPL-1.0|3|Low|
|UPL-1.0|1|Low|
|GPL-2.0|2|Medium|
|GPL-3.0|2|Medium|
|BSD-2-Clause-Views|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|go.opentelemetry.io/otel/metric|v0.30.0|直接依赖|go|
|github.com/sirupsen/logrus|v1.9.3|间接依赖|go|
|org.springframework:spring-jcl|5.2.6.RELEASE|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|org.codehaus.plexus:plexus-utils|3.0|间接依赖|maven|
|github.com/alibabacloud-go/oos-20190601|v1.0.4|间接依赖|go|
|github.com/hashicorp/consul/api|v1.24.0|间接依赖|go|
|github.com/jackc/puddle/v2|v2.2.1|间接依赖|go|
|io.grpc:grpc-api|1.33.1|间接依赖|maven|
|k8s.io/metrics|v0.26.3|直接依赖|go|
|github.com/lestrrat-go/httpcc|v1.0.1|间接依赖|go|
|github.com/knadh/koanf|v1.4.1|间接依赖|go|
|golang.org/x/exp|v0.0.0-20230817173708-d852ddb80c63|直接依赖|go|
|github.com/99designs/go-keychain|v0.0.0-20191008050251-8e49817e8af4|间接依赖|go|
|github.com/vmware/vmware-go-kcl|v1.5.1|间接依赖|go|
|github.com/tchap/go-patricia/v2|v2.3.1|间接依赖|go|
|go.uber.org/zap|v1.24.0|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/messaging/azservicebus|v1.4.0|间接依赖|go|
|github.com/k0kubun/pp|v3.0.1+incompatible|间接依赖|go|
|github.com/bytedance/gopkg|v0.0.0-20220817015305-b879a72dc90f|间接依赖|go|
|github.com/go-playground/universal-translator|v0.18.0|间接依赖|go|
|github.com/kelseyhightower/envconfig|v1.4.0|直接依赖|go|
|golang.org/x/text|v0.12.0|间接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|github.com/sony/gobreaker|v0.5.0|直接依赖|go|
|golang.org/x/sync|v0.3.0|直接依赖|go|
|github.com/go-pkgz/expirable-cache|v0.1.0|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20221012153701-172d655c2280|间接依赖|go|
|github.com/eclipse/paho.mqtt.golang|v1.4.3|间接依赖|go|
|github.com/dapr/kit|v0.0.4-0.20221211173611-bcf6ee09314e|直接依赖|go|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|k8s.io/klog/v2|v2.90.1|间接依赖|go|
|github.com/mtibben/percent|v0.2.1|间接依赖|go|
|org.apache.maven:maven-model|2.0.9|间接依赖|maven|
|github.com/go-redis/redis/v8|v8.11.5|间接依赖|go|
|org.springframework:spring-web|5.2.6.RELEASE|间接依赖|maven|
|sigs.k8s.io/json|v0.0.0-20220713155537-f223a00ba0e2|间接依赖|go|
|org.springframework:spring-context|5.2.6.RELEASE|间接依赖|maven|
|github.com/dvsekhvalnov/jose2go|v1.5.0|间接依赖|go|
|modernc.org/token|v1.1.0|间接依赖|go|
|github.com/bsm/redislock|v0.8.2|直接依赖|go|
|github.com/magiconair/properties|v1.8.6|间接依赖|go|
|golang.org/x/tools|v0.12.1-0.20230815132531-74c255bcf846|间接依赖|go|
|flask-dapr|1.9.0|间接依赖|pip|
|golang.org/x/term|v0.11.0|间接依赖|go|
|nyholm/psr7-server|1.0.1|间接依赖|composer|
|github.com/hailocab/go-hostpool|v0.0.0-20160125115350-e80d13ce29ed|间接依赖|go|
|github.com/lestrrat-go/blackmagic|v1.0.1|间接依赖|go|
|org.apache.logging.log4j:log4j-to-slf4j|2.13.2|间接依赖|maven|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|github.com/dustin/go-humanize|v1.0.1|间接依赖|go|
|cloud.google.com/go/pubsub|v1.33.0|间接依赖|go|
|github.com/ghodss/yaml|v1.0.1-0.20190212211648-25d852aebe32|间接依赖|go|
|github.com/creasty/defaults|v1.5.2|间接依赖|go|
|github.com/stretchr/testify|v1.8.4|直接依赖|go|
|github.com/shirou/gopsutil/v3|v3.22.2|间接依赖|go|
|github.com/kr/pretty|v0.3.1|间接依赖|go|
|com.fasterxml.jackson.core:jackson-databind|2.11.0|直接依赖|maven|
|github.com/dapr/components-contrib|v1.9.1-0.20221213185150-c5c985a68514|直接依赖|go|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|modernc.org/ccgo/v3|v3.16.14|间接依赖|go|
|go.uber.org/automaxprocs|v1.5.3|直接依赖|go|
|github.com/prometheus/client_model|v0.4.0|直接依赖|go|
|github.com/goccy/go-json|v0.10.2|间接依赖|go|
|github.com/jinzhu/copier|v0.3.5|间接依赖|go|
|laminas/laminas-zendframework-bridge|1.2.x-dev|间接依赖|composer|
|k8s.io/cli-runtime|v0.26.3|直接依赖|go|
|gopkg.in/gomail.v2|v2.0.0-20160411212932-81ebce5c23df|间接依赖|go|
|golang.org/x/text|v0.11.0|间接依赖|go|
|k8s.io/code-generator|v0.26.3|直接依赖|go|
|github.com/huaweicloud/huaweicloud-sdk-go-obs|v3.23.4+incompatible|间接依赖|go|
|k8s.io/component-base|v0.26.3|间接依赖|go|
|com.google.guava:guava|29.0-android|间接依赖|maven|
|modernc.org/memory|v1.6.0|间接依赖|go|
|contrib.go.opencensus.io/exporter/prometheus|v0.4.2|直接依赖|go|
|github.com/kubemq-io/kubemq-go|v1.7.9|间接依赖|go|
|github.com/cenkalti/backoff/v4|v4.2.0|间接依赖|go|
|github.com/phayes/freeport|v0.0.0-20220201140144-74d24b5ae9f5|直接依赖|go|
|org.springframework.boot:spring-boot|2.3.0.RELEASE|间接依赖|maven|
|modernc.org/opt|v0.1.3|间接依赖|go|
|k8s.io/utils|v0.0.0-20230726121419-3b25d923346b|直接依赖|go|
|github.com/hashicorp/raft-boltdb|v0.0.0-20230125174641-2a8082862702|直接依赖|go|
|github.com/go-chi/chi/v5|v5.0.8|直接依赖|go|
|go.opentelemetry.io/otel/sdk|v1.16.0|直接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|github.com/camunda/zeebe/clients/go/v8|v8.2.12|间接依赖|go|
|github.com/stoewer/go-strcase|v1.2.0|间接依赖|go|
|github.com/Azure/azure-sdk-for-go|v68.0.0+incompatible|间接依赖|go|
|php-http/message-factory|dev-master|间接依赖|composer|
|github.com/alibabacloud-go/debug|v0.0.0-20190504072949-9472017b5c68|间接依赖|go|
|github.com/eapache/go-resiliency|v1.4.0|间接依赖|go|
|github.com/go-ole/go-ole|v1.2.6|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20221207170731-23e4bf6bdc37|间接依赖|go|
|laminas/laminas-httphandlerrunner|1.4.x-dev|间接依赖|composer|
|io.grpc:grpc-context|1.33.1|间接依赖|maven|
|google.golang.org/grpc|v1.57.0|直接依赖|go|
|github.com/bufbuild/protocompile|v0.4.0|间接依赖|go|
|github.com/Workiva/go-datastructures|v1.0.53|间接依赖|go|
|github.com/hashicorp/go-immutable-radix|v1.3.1|间接依赖|go|
|github.com/lestrrat-go/httprc|v1.0.4|间接依赖|go|
|php-di/invoker|2.3.0|间接依赖|composer|
|go.opentelemetry.io/otel/trace|v1.7.0|间接依赖|go|
|github.com/klauspost/compress|v1.15.12|间接依赖|go|
|org.apache.maven:maven-artifact|2.0.9|间接依赖|maven|
|k8s.io/klog|v1.0.0|直接依赖|go|
|github.com/googleapis/enterprise-certificate-proxy|v0.2.5|间接依赖|go|
|github.com/nats-io/nuid|v1.0.1|间接依赖|go|
|opis/closure|dev-master|间接依赖|composer|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|io.grpc:grpc-context|1.27.2|间接依赖|maven|
|com.github.os72:protoc-jar-maven-plugin|3.11.4|间接依赖|maven|
|github.com/open-policy-agent/opa|v0.55.0|间接依赖|go|
|google.golang.org/api|v0.138.0|间接依赖|go|
|google.golang.org/genproto/googleapis/api|v0.0.0-20230803162519-f966b187b2e5|直接依赖|go|
|com.google.errorprone:error_prone_annotations|2.3.4|间接依赖|maven|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|io.dapr:dapr-sdk-actors|1.0.0-rc-2|直接依赖|maven|
|github.com/go-openapi/swag|v0.21.1|间接依赖|go|
|io.dapr:dapr-sdk-actors|1.0.0-rc-6|直接依赖|maven|
|github.com/go-chi/cors|v1.2.1|直接依赖|go|
|github.com/go-logfmt/logfmt|v0.5.1|间接依赖|go|
|gopkg.in/couchbase/gocb.v1|v1.6.7|间接依赖|go|
|github.com/go-zookeeper/zk|v1.0.3|间接依赖|go|
|github.com/go-errors/errors|v1.4.2|间接依赖|go|
|github.com/go-playground/locales|v0.14.0|间接依赖|go|
|github.com/lufia/plan9stats|v0.0.0-20211012122336-39d0f177ccd0|间接依赖|go|
|github.com/andybalholm/brotli|v1.0.5|间接依赖|go|
|github.com/dapr/dapr|v0.0.0|直接依赖|go|
|github.com/agnivade/levenshtein|v1.1.1|间接依赖|go|
|io.opencensus:opencensus-api|0.28.2|间接依赖|maven|
|github.com/aerospike/aerospike-client-go/v6|v6.12.0|间接依赖|go|
|github.com/google/shlex|v0.0.0-20191202100458-e7afc7fbc510|间接依赖|go|
|github.com/supplyon/gremcos|v0.1.40|间接依赖|go|
|dubbo.apache.org/dubbo-go/v3|v3.0.3-0.20230118042253-4f159a2b38f3|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230821184602-ccc8af3d0e93|间接依赖|go|
|github.com/gobwas/glob|v0.2.3|间接依赖|go|
|github.com/eapache/go-xerial-snappy|v0.0.0-20230731223053-c322873962e3|间接依赖|go|
|github.com/prometheus/client_model|v0.2.0|间接依赖|go|
|github.com/prometheus/procfs|v0.7.3|间接依赖|go|
|php-di/php-di|6.3.0|间接依赖|composer|
|github.com/Azure/azure-sdk-for-go/sdk/storage/azqueue|v1.0.0|间接依赖|go|
|modernc.org/cc/v3|v3.41.0|间接依赖|go|
|github.com/yashtewari/glob-intersection|v0.2.0|间接依赖|go|
|com.google.api.grpc:proto-google-common-protos|1.17.0|间接依赖|maven|
|github.com/apache/dubbo-getty|v1.4.9-0.20220610060150-8af010f3f3dc|间接依赖|go|
|go.uber.org/atomic|v1.10.0|间接依赖|go|
|org.sonatype.plexus:plexus-build-api|0.0.7|间接依赖|maven|
|go.opentelemetry.io/otel/trace|v1.16.0|直接依赖|go|
|github.com/google/pprof|v0.0.0-20221118152302-e6195bd50e26|间接依赖|go|
|github.com/dapr/dapr|v0.0.0-00010101000000-000000000000|直接依赖|go|
|go.opencensus.io|v0.24.0|直接依赖|go|
|com.github.os72:protoc-jar|3.11.4|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.3.0.RELEASE|直接依赖|maven|
|cloud.google.com/go/compute|v1.23.0|间接依赖|go|
|github.com/rs/zerolog|v1.28.0|间接依赖|go|
|github.com/segmentio/asm|v1.2.0|间接依赖|go|
|google.golang.org/protobuf|v1.26.0|间接依赖|go|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|cloud.google.com/go/iam|v1.1.1|间接依赖|go|
|io.dapr:dapr-sdk-springboot|1.0.0-rc-2|直接依赖|maven|
|github.com/mitchellh/copystructure|v1.2.0|间接依赖|go|
|gopkg.in/couchbaselabs/gocbconnstr.v1|v1.0.4|间接依赖|go|
|gopkg.in/couchbaselabs/jsonx.v1|v1.0.1|间接依赖|go|
|org.jetbrains.kotlin:kotlin-stdlib|1.3.72|间接依赖|maven|
|google.golang.org/grpc/examples|v0.0.0-20220818173707-97cb7b1653d7|直接依赖|go|
|gomodules.xyz/jsonpatch/v2|v2.2.0|间接依赖|go|
|github.com/Shopify/sarama|v1.37.2|间接依赖|go|
|github.com/gorilla/websocket|v1.5.0|直接依赖|go|
|github.com/pierrec/lz4/v4|v4.1.17|间接依赖|go|
|github.com/dapr/components-contrib|v1.11.3-0.20230905221417-0c2ce324b2bf|直接依赖|go|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|github.com/mattn/go-isatty|v0.0.19|间接依赖|go|
|github.com/alibaba/sentinel-golang|v1.0.4|间接依赖|go|
|github.com/marusama/semaphore/v2|v2.5.0|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|间接依赖|go|
|github.com/influxdata/line-protocol|v0.0.0-20210922203350-b1ad95c89adf|间接依赖|go|
|github.com/jackc/pgpassfile|v1.0.0|间接依赖|go|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.35|间接依赖|maven|
|github.com/Azure/azure-sdk-for-go/sdk/azidentity|v1.3.1|间接依赖|go|
|github.com/armon/go-metrics|v0.4.1|间接依赖|go|
|github.com/nats-io/nats.go|v1.28.0|间接依赖|go|
|github.com/google/flatbuffers|v2.0.8+incompatible|间接依赖|go|
|github.com/montanaflynn/stats|v0.7.0|间接依赖|go|
|github.com/lestrrat-go/iter|v1.0.2|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/hashicorp/errwrap|v1.1.0|间接依赖|go|
|psr/http-message|dev-master|间接依赖|composer|
|github.com/grafana/k6-operator|v0.0.8|直接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace/otlptracegrpc|v1.16.0|直接依赖|go|
|github.com/golang-jwt/jwt/v5|v5.0.0|间接依赖|go|
|github.com/dubbogo/triple|v1.1.8|间接依赖|go|
|github.com/99designs/keyring|v1.2.1|间接依赖|go|
|github.com/hamba/avro/v2|v2.15.0|间接依赖|go|
|github.com/klauspost/compress|v1.16.7|间接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.3|间接依赖|go|
|github.com/bits-and-blooms/bitset|v1.4.0|间接依赖|go|
|github.com/microsoft/go-mssqldb|v1.5.0|间接依赖|go|
|io.dapr:dapr-sdk-springboot|1.0.0-rc-6|直接依赖|maven|
|github.com/panjf2000/ants/v2|v2.8.1|间接依赖|go|
|github.com/hashicorp/serf|v0.10.1|间接依赖|go|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.11.0|间接依赖|maven|
|github.com/Azure/azure-sdk-for-go/sdk/azcore|v1.7.1|间接依赖|go|
|github.com/dapr/kit|v0.11.4-0.20230907165049-f08dc3ff1671|直接依赖|go|
|gopkg.in/alexcesaro/quotedprintable.v3|v3.0.0-20150716171945-2caba252f4dc|间接依赖|go|
|github.com/cloudevents/sdk-go/v2|v2.14.0|直接依赖|go|
|cloud.google.com/go/compute/metadata|v0.2.3|间接依赖|go|
|github.com/xdg-go/stringprep|v1.0.4|间接依赖|go|
|github.com/google/btree|v1.1.2|间接依赖|go|
|github.com/valyala/bytebufferpool|v1.0.0|间接依赖|go|
|github.com/go-redis/redis/v9|v9.0.0-rc.1|直接依赖|go|
|org.slf4j:jul-to-slf4j|1.7.30|间接依赖|maven|
|github.com/Azure/go-amqp|v1.0.1|间接依赖|go|
|org.projectlombok:lombok|1.18.12|直接依赖|maven|
|com.google.protobuf:protobuf-java|3.12.0|间接依赖|maven|
|golang.org/x/mod|v0.12.0|间接依赖|go|
|github.com/alibabacloud-go/alibabacloud-gateway-spi|v0.0.4|间接依赖|go|
|github.com/huaweicloud/huaweicloud-sdk-go-v3|v0.1.56|间接依赖|go|
|go.uber.org/multierr|v1.11.0|间接依赖|go|
|github.com/prometheus/common|v0.32.1|间接依赖|go|
|github.com/clbanning/mxj/v2|v2.5.6|间接依赖|go|
|github.com/alibabacloud-go/tea|v1.2.1|间接依赖|go|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230410155749-daa745c078e1|间接依赖|go|
|github.com/aymerick/douceur|v0.2.0|间接依赖|go|
|github.com/mitchellh/reflectwalk|v1.0.2|间接依赖|go|
|org.apache.maven:maven-plugin-registry|2.0.9|间接依赖|maven|
|github.com/sendgrid/sendgrid-go|v3.13.0+incompatible|间接依赖|go|
|github.com/apache/rocketmq-client-go/v2|v2.1.2-0.20230412142645-25003f6f083d|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/data/aztables|v1.0.2|间接依赖|go|
|github.com/jackc/pgservicefile|v0.0.0-20221227161230-091c0ba34f0a|间接依赖|go|
|github.com/linkedin/goavro/v2|v2.9.8|间接依赖|go|
|org.apache.maven:maven-artifact-manager|2.0.9|间接依赖|maven|
|org.apache.maven:maven-profile|2.0.9|间接依赖|maven|
|dapr/php-sdk|v1.0.0-rc.4|间接依赖|composer|
|github.com/hashicorp/go-cleanhttp|v0.5.2|间接依赖|go|
|go.opentelemetry.io/otel/sdk/metric|v0.30.0|直接依赖|go|
|go.opentelemetry.io/proto/otlp|v0.19.0|间接依赖|go|
|org.springframework.boot:spring-boot-starter-json|2.3.0.RELEASE|间接依赖|maven|
|github.com/pkg/browser|v0.0.0-20210911075715-681adbf594b8|间接依赖|go|
|org.apache.commons:commons-lang3|3.10|直接依赖|maven|
|github.com/fasthttp-contrib/sessions|v0.0.0-20160905201309-74f6ac73d5d5|间接依赖|go|
|github.com/decred/dcrd/dcrec/secp256k1/v4|v4.2.0|间接依赖|go|
|org.codehaus.mojo:animal-sniffer-annotations|1.18|间接依赖|maven|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/godbus/dbus|v0.0.0-20190726142602-4481cbc300e2|间接依赖|go|
|github.com/kubemq-io/protobuf|v1.3.1|间接依赖|go|
|sigs.k8s.io/kustomize/api|v0.12.1|间接依赖|go|
|github.com/spiffe/go-spiffe/v2|v2.1.6|直接依赖|go|
|github.com/tidwall/gjson|v1.13.0|间接依赖|go|
|github.com/leodido/go-urn|v1.2.1|间接依赖|go|
|github.com/dgryski/go-rendezvous|v0.0.0-20200823014737-9f7001d12a5f|间接依赖|go|
|github.com/AzureAD/microsoft-authentication-library-for-go|v1.1.1|间接依赖|go|
|github.com/sendgrid/rest|v2.6.9+incompatible|间接依赖|go|
|modernc.org/mathutil|v1.6.0|间接依赖|go|
|github.com/golang/protobuf|v1.5.3|直接依赖|go|
|commons-io:commons-io|2.2|间接依赖|maven|
|golang.org/x/oauth2|v0.10.0|间接依赖|go|
|go.mongodb.org/mongo-driver|v1.12.1|直接依赖|go|
|github.com/hazelcast/hazelcast-go-client|v0.0.0-20190530123621-6cf767c2f31a|间接依赖|go|
|github.com/kballard/go-shellquote|v0.0.0-20180428030007-95032a82bc51|间接依赖|go|
|github.com/imdario/mergo|v0.3.13|间接依赖|go|
|github.com/cyphar/filepath-securejoin|v0.2.3|间接依赖|go|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|github.com/mschoch/smat|v0.2.0|间接依赖|go|
|io.opentelemetry:opentelemetry-api|0.10.0|间接依赖|maven|
|github.com/jcmturner/rpc/v2|v2.0.3|间接依赖|go|
|google.golang.org/grpc|v1.54.0|直接依赖|go|
|github.com/apache/thrift|v0.13.0|间接依赖|go|
|github.com/DataDog/zstd|v1.5.2|间接依赖|go|
|org.springframework.boot:spring-boot-autoconfigure|2.3.0.RELEASE|直接依赖|maven|
|github.com/golang/snappy|v0.0.4|间接依赖|go|
|golang.org/x/xerrors|v0.0.0-20220907171357-04be3eba64a2|间接依赖|go|
|github.com/PaesslerAG/jsonpath|v0.1.1|直接依赖|go|
|github.com/alibabacloud-go/tea-utils|v1.4.5|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|github.com/tidwall/transform|v0.0.0-20201103190739-32f242e2dbde|直接依赖|go|
|github.com/antlr/antlr4/runtime/Go/antlr|v1.4.10|间接依赖|go|
|nikic/fast-route|v1.x-dev|间接依赖|composer|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|github.com/pierrec/lz4|v2.6.1+incompatible|间接依赖|go|
|github.com/aliyun/aliyun-log-go-sdk|v0.1.54|间接依赖|go|
|github.com/prometheus/client_golang|v1.12.1|间接依赖|go|
|github.com/eapache/go-resiliency|v1.3.0|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|直接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway/v2|v2.15.2|间接依赖|go|
|google.golang.org/grpc|v1.55.0|间接依赖|go|
|github.com/oleiade/lane|v1.0.1|间接依赖|go|
|github.com/kylelemons/godebug|v1.1.0|间接依赖|go|
|golang.org/x/sys|v0.10.0|间接依赖|go|
|gopkg.in/natefinch/lumberjack.v2|v2.0.0|间接依赖|go|
|github.com/deepmap/oapi-codegen|v1.11.0|间接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|github.com/prometheus/client_golang|v1.16.0|直接依赖|go|
|github.com/hashicorp/go-hclog|v1.5.0|直接依赖|go|
|nyholm/psr7|dev-master|间接依赖|composer|
|org.springframework:spring-webmvc|5.2.6.RELEASE|间接依赖|maven|
|github.com/machinebox/graphql|v0.2.2|间接依赖|go|
|org.springframework:spring-expression|5.2.6.RELEASE|间接依赖|maven|
|github.com/matoous/go-nanoid/v2|v2.0.0|间接依赖|go|
|org.glassfish:jakarta.el|3.0.3|间接依赖|maven|
|golang.org/x/sys|v0.11.0|间接依赖|go|
|php-di/phpdoc-reader|2.2.1|间接依赖|composer|
|ch.qos.logback:logback-classic|1.2.3|间接依赖|maven|
|github.com/Azure/azure-sdk-for-go/sdk/security/keyvault/azkeys|v1.0.1|间接依赖|go|
|github.com/go-resty/resty/v2|v2.7.0|间接依赖|go|
|golang.org/x/net|v0.12.0|间接依赖|go|
|go.opentelemetry.io/otel/exporters/prometheus|v0.30.0|直接依赖|go|
|github.com/google/uuid|v1.3.1|直接依赖|go|
|github.com/xdg-go/scram|v1.1.2|间接依赖|go|
|google.golang.org/grpc/examples|v0.0.0-20210610163306-6351a55c3895|直接依赖|go|
|fortio.org/fortio|v1.6.8|直接依赖|go|
|google.golang.org/protobuf|v1.30.0|间接依赖|go|
|org.springframework.boot:spring-boot-starter-tomcat|2.3.0.RELEASE|间接依赖|maven|
|github.com/patrickmn/go-cache|v2.1.0+incompatible|间接依赖|go|
|github.com/go-ini/ini|v1.67.0|间接依赖|go|
|org.apache.maven:maven-project|2.0.9|间接依赖|maven|
|github.com/google/s2a-go|v0.1.5|间接依赖|go|
|io.dapr:dapr-sdk|1.0.0-rc-6|直接依赖|maven|
|github.com/tetratelabs/wazero|v1.5.0|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/storage/azblob|v1.1.0|间接依赖|go|
|github.com/go-logr/logr|v1.2.4|直接依赖|go|
|github.com/boltdb/bolt|v1.3.1|间接依赖|go|
|github.com/chenzhuoyu/iasm|v0.0.0-20230222070914-0b1b64b0e762|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|golang.org/x/arch|v0.3.0|间接依赖|go|
|github.com/jcmturner/gokrb5/v8|v8.4.4|间接依赖|go|
|github.com/aliyun/aliyun-tablestore-go-sdk|v1.7.10|间接依赖|go|
|github.com/golang-sql/sqlexp|v0.1.0|间接依赖|go|
|go.starlark.net|v0.0.0-20200306205701-8dd3e2ee1dd5|间接依赖|go|
|github.com/ardielle/ardielle-go|v1.5.2|间接依赖|go|
|github.com/argoproj/argo-rollouts|v1.4.1|直接依赖|go|
|github.com/cloudevents/sdk-go/binding/format/protobuf/v2|v2.14.0|间接依赖|go|
|github.com/jcmturner/aescts/v2|v2.0.0|间接依赖|go|
|github.com/cenkalti/backoff|v2.2.1+incompatible|间接依赖|go|
|psr/http-server-handler|dev-master|间接依赖|composer|
|lukechampine.com/uint128|v1.3.0|间接依赖|go|
|github.com/xeipuuv/gojsonreference|v0.0.0-20180127040603-bd5ef7bd5415|间接依赖|go|
|github.com/youmark/pkcs8|v0.0.0-20181117223130-1be2e3e5546d|间接依赖|go|
|github.com/hashicorp/go-uuid|v1.0.3|间接依赖|go|
|github.com/cloudwego/netpoll|v0.3.2|间接依赖|go|
|github.com/aws/aws-sdk-go|v1.44.333|间接依赖|go|
|cloud.google.com/go/storage|v1.32.0|间接依赖|go|
|monolog/monolog|dev-main|间接依赖|composer|
|github.com/benbjohnson/clock|v1.3.5|间接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230626202813-9b080da550b3|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.1-0.20181226105442-5d4384ee4fb2|间接依赖|go|
|io.opentelemetry:opentelemetry-context|0.10.0|间接依赖|maven|
|github.com/tidwall/pretty|v1.2.1|间接依赖|go|
|github.com/tidwall/match|v1.1.1|间接依赖|go|
|github.com/apache/dubbo-go-hessian2|v1.11.5|间接依赖|go|
|gopkg.in/gorethink/gorethink.v4|v4.1.0|间接依赖|go|
|go.etcd.io/etcd/client/v3|v3.5.9|间接依赖|go|
|github.com/go-playground/validator/v10|v10.11.0|间接依赖|go|
|github.com/PuerkitoBio/purell|v1.2.0|直接依赖|go|
|github.com/spf13/cobra|v1.7.0|间接依赖|go|
|github.com/RoaringBitmap/roaring|v1.1.0|间接依赖|go|
|github.com/google/gnostic|v0.6.9|间接依赖|go|
|psr/log|dev-master|间接依赖|composer|
|github.com/hashicorp/golang-lru/v2|v2.0.6|直接依赖|go|
|go.etcd.io/etcd/api/v3|v3.5.9|间接依赖|go|
|github.com/labd/commercetools-go-sdk|v1.3.1|间接依赖|go|
|github.com/tencentcloud/tencentcloud-sdk-go/tencentcloud/ssm|v1.0.732|间接依赖|go|
|github.com/gsterjov/go-libsecret|v0.0.0-20161001094733-a6f4afe4910c|间接依赖|go|
|github.com/nats-io/nkeys|v0.4.4|间接依赖|go|
|org.springframework:spring-core|5.2.6.RELEASE|间接依赖|maven|
|github.com/hashicorp/raft|v1.4.0|直接依赖|go|
|github.com/google/cel-go|v0.13.0|直接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/data/azappconfig|v0.5.0|间接依赖|go|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.35|间接依赖|maven|
|github.com/danieljoos/wincred|v1.1.2|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|com.google.code.gson:gson|2.8.6|间接依赖|maven|
|github.com/gofrs/uuid|v3.3.0+incompatible|间接依赖|go|
|github.com/tklauser/go-sysconf|v0.3.10|间接依赖|go|
|org.slf4j:slf4j-api|1.7.30|间接依赖|maven|
|github.com/prometheus/statsd_exporter|v0.22.7|间接依赖|go|
|github.com/yusufpapurcu/wmi|v1.2.2|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/xeipuuv/gojsonpointer|v0.0.0-20190905194746-02993c407bfb|间接依赖|go|
|github.com/alibabacloud-go/openapi-util|v0.0.11|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/ai/azopenai|v0.1.1|间接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.0|间接依赖|go|
|github.com/evanphx/json-patch|v5.6.0+incompatible|间接依赖|go|
|github.com/AthenZ/athenz|v1.10.39|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/xdg-go/stringprep|v1.0.3|间接依赖|go|
|go.etcd.io/etcd/client/pkg/v3|v3.5.9|间接依赖|go|
|github.com/grandcat/zeroconf|v1.0.0|间接依赖|go|
|com.squareup.okhttp3:okhttp|4.2.1|直接依赖|maven|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace|v1.16.0|直接依赖|go|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.11.0|间接依赖|maven|
|org.hamcrest:hamcrest-core|2.2|间接依赖|maven|
|github.com/dapr-sandbox/components-go-sdk|v0.0.0-20221213200551-bd485eb929ff|直接依赖|go|
|github.com/zeebo/errs|v1.3.0|间接依赖|go|
|k8s.io/client-go|v0.26.3|直接依赖|go|
|org.yaml:snakeyaml|1.26|间接依赖|maven|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230807174057-1744710a1577|直接依赖|go|
|io.dapr:dapr-sdk-autogen|1.0.0-rc-6|间接依赖|maven|
|github.com/dapr/dapr|v1.7.4|直接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/internal/retry|v1.16.0|间接依赖|go|
|io.grpc:grpc-stub|1.33.1|间接依赖|maven|
|org.codehaus.plexus:plexus-container-default|1.0-alpha-9-stable-1|间接依赖|maven|
|cloud.google.com/go/secretmanager|v1.11.1|间接依赖|go|
|github.com/go-chi/chi/v5|v5.0.10|直接依赖|go|
|modernc.org/strutil|v1.1.3|间接依赖|go|
|org.springframework:spring-beans|5.2.6.RELEASE|间接依赖|maven|
|io.dapr:dapr-sdk|1.0.0-rc-2|直接依赖|maven|
|github.com/googleapis/gax-go/v2|v2.12.0|间接依赖|go|
|github.com/mrz1836/postmark|v1.6.1|间接依赖|go|
|github.com/remyoudompheng/bigfft|v0.0.0-20230129092748-24d4a6f8daec|间接依赖|go|
|psr/container|dev-master|间接依赖|composer|
|github.com/openzipkin/zipkin-go|v0.4.1|间接依赖|go|
|github.com/bradfitz/gomemcache|v0.0.0-20230611145640-acc696258285|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/security/keyvault/internal|v1.0.0|间接依赖|go|
|github.com/sourcegraph/conc|v0.3.0|间接依赖|go|
|github.com/cenkalti/backoff/v4|v4.2.1|直接依赖|go|
|github.com/grpc-ecosystem/go-grpc-middleware|v1.4.0|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/security/keyvault/azsecrets|v1.0.1|间接依赖|go|
|github.com/natefinch/lumberjack|v2.0.0+incompatible|间接依赖|go|
|github.com/cloudwego/fastpb|v0.0.4-0.20230131074846-6fc453d58b96|间接依赖|go|
|github.com/coreos/go-systemd/v22|v22.5.0|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/resourcemanager/eventhub/armeventhub|v1.1.1|间接依赖|go|
|github.com/opentracing/opentracing-go|v1.2.0|间接依赖|go|
|github.com/tencentcloud/tencentcloud-sdk-go/tencentcloud/common|v1.0.732|间接依赖|go|
|k8s.io/apiextensions-apiserver|v0.26.3|直接依赖|go|
|github.com/alibabacloud-go/endpoint-util|v1.1.0|间接依赖|go|
|github.com/microsoft/durabletask-go|v0.3.1|直接依赖|go|
|com.fasterxml.jackson.module:jackson-module-kotlin|2.11.0|直接依赖|maven|
|github.com/dapr/go-sdk|v1.8.0|直接依赖|go|
|io.grpc:grpc-netty-shaded|1.33.1|间接依赖|maven|
|github.com/miekg/dns|v1.1.43|间接依赖|go|
|github.com/gorilla/css|v1.0.0|间接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|间接依赖|go|
|github.com/cloudwego/frugal|v0.1.6|间接依赖|go|
|org.springframework.boot:spring-boot-starter|2.3.0.RELEASE|间接依赖|maven|
|github.com/asaskevich/govalidator|v0.0.0-20200108200545-475eaeb16496|间接依赖|go|
|github.com/dubbogo/gost|v1.13.1|间接依赖|go|
|sigs.k8s.io/controller-runtime|v0.14.6|直接依赖|go|
|github.com/go-sql-driver/mysql|v1.7.1|间接依赖|go|
|github.com/redis/go-redis/v9|v9.1.0|直接依赖|go|
|github.com/hashicorp/go-rootcerts|v1.0.2|间接依赖|go|
|github.com/xdg-go/scram|v1.1.1|间接依赖|go|
|github.com/monochromegane/go-gitignore|v0.0.0-20200626010858-205db1a8cc00|间接依赖|go|
|github.com/stretchr/objx|v0.5.0|间接依赖|go|
|github.com/rabbitmq/amqp091-go|v1.8.1|间接依赖|go|
|github.com/golang/protobuf|v1.5.2|间接依赖|go|
|github.com/spf13/cast|v1.5.1|直接依赖|go|
|github.com/golang-jwt/jwt|v3.2.2+incompatible|间接依赖|go|
|cloud.google.com/go/datastore|v1.14.0|间接依赖|go|
|github.com/prometheus/procfs|v0.11.0|间接依赖|go|
|github.com/jcmturner/gofork|v1.7.6|间接依赖|go|
|org.checkerframework:checker-compat-qual|2.5.5|间接依赖|maven|
|modernc.org/sqlite|v1.25.0|间接依赖|go|
|golang.org/x/oauth2|v0.11.0|间接依赖|go|
|gopkg.in/fatih/pool.v2|v2.0.0|间接依赖|go|
|github.com/emicklei/go-restful/v3|v3.10.2|间接依赖|go|
|github.com/fatih/color|v1.15.0|间接依赖|go|
|org.apache.logging.log4j:log4j-api|2.13.2|间接依赖|maven|
|org.apache.maven:maven-settings|2.0.9|间接依赖|maven|
|github.com/lestrrat-go/option|v1.0.1|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/data/azcosmos|v0.3.6|间接依赖|go|
|classworlds:classworlds|1.1-alpha-2|间接依赖|maven|
|io.grpc:grpc-core|1.33.1|间接依赖|maven|
|github.com/tklauser/numcpus|v0.4.0|间接依赖|go|
|github.com/power-devops/perfstat|v0.0.0-20210106213030-5aafc221ea8c|间接依赖|go|
|k8s.io/api|v0.26.3|直接依赖|go|
|github.com/go-kit/log|v0.2.1|间接依赖|go|
|k8s.io/apimachinery|v0.26.3|直接依赖|go|
|org.springframework:spring-aop|5.2.6.RELEASE|间接依赖|maven|
|org.apache.maven.wagon:wagon-provider-api|1.0-beta-2|间接依赖|maven|
|github.com/yuin/gopher-lua|v1.1.0|间接依赖|go|
|github.com/hashicorp/go-multierror|v1.1.1|间接依赖|go|
|github.com/nats-io/stan.go|v0.10.4|间接依赖|go|
|golang.org/x/time|v0.3.0|间接依赖|go|
|github.com/liggitt/tabwriter|v0.0.0-20181228230101-89fcab3d43de|间接依赖|go|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.3.72|间接依赖|maven|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/alibabacloud-go/tea-xml|v1.1.2|间接依赖|go|
|github.com/jcmturner/dnsutils/v2|v2.0.0|间接依赖|go|
|github.com/oracle/oci-go-sdk/v54|v54.0.0|间接依赖|go|
|github.com/lestrrat-go/jwx/v2|v2.0.12|直接依赖|go|
|org.apache.maven:maven-plugin-api|2.0.9|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.11.0|直接依赖|maven|
|golang.org/x/crypto|v0.11.0|间接依赖|go|
|com.squareup.okio:okio|2.2.2|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.11.0|间接依赖|maven|
|io.grpc:grpc-protobuf|1.33.1|间接依赖|maven|
|org.hamcrest:hamcrest|2.2|间接依赖|maven|
|github.com/sijms/go-ora/v2|v2.7.17|间接依赖|go|
|org.apache.maven:maven-repository-metadata|2.0.9|间接依赖|maven|
|github.com/sirupsen/logrus|v1.9.0|间接依赖|go|
|github.com/pelletier/go-toml|v1.9.5|间接依赖|go|
|go.opentelemetry.io/otel/metric|v1.16.0|间接依赖|go|
|go.opentelemetry.io/otel|v1.16.0|直接依赖|go|
|io.dapr:dapr-sdk-autogen|1.0.0-rc-2|间接依赖|maven|
|github.com/Azure/azure-sdk-for-go/sdk/resourcemanager/eventgrid/armeventgrid/v2|v2.1.1|间接依赖|go|
|github.com/dapr/dapr|v1.9.4-0.20221212235750-ac9256f214e0|间接依赖|go|
|github.com/IBM/sarama|v1.41.1|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/messaging/azeventhubs|v1.0.1|间接依赖|go|
|github.com/evanphx/json-patch/v5|v5.6.0|直接依赖|go|
|cloud.google.com/go|v0.110.7|间接依赖|go|
|github.com/google/uuid|v1.2.0|直接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|github.com/hashicorp/golang-lru|v0.5.4|间接依赖|go|
|github.com/gregjones/httpcache|v0.0.0-20190611155906-901d90724c79|间接依赖|go|
|junit:junit|4.13|间接依赖|maven|
|github.com/google/gofuzz|v1.2.0|直接依赖|go|
|github.com/aliyun/credentials-go|v1.1.2|间接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.1-0.20220423185008-bf980b35cac4|直接依赖|go|
|gopkg.in/couchbase/gocbcore.v7|v7.1.18|间接依赖|go|
|github.com/PaesslerAG/gval|v1.0.0|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/internal|v1.3.0|间接依赖|go|
|github.com/valyala/fasthttp|v1.49.0|直接依赖|go|
|github.com/xdg-go/pbkdf2|v1.0.0|间接依赖|go|
|github.com/influxdata/influxdb-client-go|v1.4.0|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.1.2|间接依赖|go|
|github.com/hashicorp/go-msgpack/v2|v2.1.0|直接依赖|go|
|requirements.txt||间接依赖|pip|
|github.com/xlab/treeprint|v1.1.0|间接依赖|go|
|io.projectreactor:reactor-core|3.3.5.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.3.0.RELEASE|间接依赖|maven|
|github.com/matttproud/golang_protobuf_extensions|v1.0.1|间接依赖|go|
|github.com/peterbourgon/diskv|v2.0.1+incompatible|间接依赖|go|
|github.com/aliyun/aliyun-oss-go-sdk|v2.2.9+incompatible|间接依赖|go|
|github.com/pierrec/lz4/v4|v4.1.18|间接依赖|go|
|github.com/golang/mock|v1.6.0|直接依赖|go|
|github.com/dancannon/gorethink|v4.0.0+incompatible|间接依赖|go|
|github.com/eapache/queue|v1.1.0|间接依赖|go|
|github.com/jhump/protoreflect|v1.15.1|直接依赖|go|
|github.com/alibabacloud-go/darabonba-openapi|v0.2.1|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.2-0.20180830191138-d8f796af33cc|间接依赖|go|
|psr/http-factory|dev-master|间接依赖|composer|
|k8s.io/gengo|v0.0.0-20220902162205-c0856e24416d|间接依赖|go|
|github.com/tjfoc/gmsm|v1.3.2|间接依赖|go|
|github.com/go-kit/kit|v0.10.0|间接依赖|go|
|github.com/gocql/gocql|v1.5.2|间接依赖|go|
|go.uber.org/ratelimit|v0.3.0|直接依赖|go|
|github.com/OneOfOne/xxhash|v1.2.8|间接依赖|go|
|github.com/awslabs/kinesis-aggregation/go|v0.0.0-20210630091500-54e17340d32f|间接依赖|go|
|stathat.com/c/consistent|v1.0.0|间接依赖|go|
|github.com/afex/hystrix-go|v0.0.0-20180502004556-fa1af6a1f4f5|间接依赖|go|
|go.opentelemetry.io/otel/sdk|v1.7.0|间接依赖|go|
|github.com/didip/tollbooth/v7|v7.0.1|间接依赖|go|
|sigs.k8s.io/kustomize/kyaml|v0.13.9|间接依赖|go|
|github.com/cloudwego/kitex|v0.5.0|间接依赖|go|
|nette/utils|dev-master|间接依赖|composer|
|psr/http-message-implementation||间接依赖|composer|
|nette/php-generator|dev-master|间接依赖|composer|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|github.com/stealthrocket/wasi-go|v0.7.6-0.20230718231108-c3d30af59057|间接依赖|go|
|google.golang.org/protobuf|v1.28.1|间接依赖|go|
|go.opentelemetry.io/otel/exporters/zipkin|v1.16.0|直接依赖|go|
|com.fasterxml.jackson.core:jackson-core|2.11.0|间接依赖|maven|
|github.com/jcmturner/gokrb5/v8|v8.4.3|间接依赖|go|
|gopkg.in/ini.v1|v1.67.0|间接依赖|go|
|golang.org/x/crypto|v0.12.0|直接依赖|go|
|golang.org/x/net|v0.14.0|直接依赖|go|
|github.com/hashicorp/go-msgpack|v0.5.5|间接依赖|go|
|github.com/jackc/pgx/v5|v5.4.3|直接依赖|go|
|go.opentelemetry.io/otel|v1.7.0|直接依赖|go|
|github.com/google/uuid|v1.3.0|间接依赖|go|
|io.perfmark:perfmark-api|0.19.0|间接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.33.1|间接依赖|maven|
|github.com/http-wasm/http-wasm-host-go|v0.5.1|间接依赖|go|
|github.com/golang-sql/civil|v0.0.0-20220223132316-b832511892a9|间接依赖|go|
|github.com/gorilla/mux|v1.8.0|直接依赖|go|
|github.com/spaolacci/murmur3|v1.1.0|间接依赖|go|
|org.jetbrains.kotlin:kotlin-reflect|1.3.72|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.3|间接依赖|maven|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace/otlptracehttp|v1.16.0|直接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.5|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/apache/pulsar-client-go|v0.11.0|间接依赖|go|
|github.com/go-ozzo/ozzo-validation/v4|v4.3.0|间接依赖|go|
|github.com/eapache/go-xerial-snappy|v0.0.0-20180814174437-776d5712da21|间接依赖|go|
|github.com/prometheus/common|v0.44.0|直接依赖|go|
|google.golang.org/grpc|v1.51.0|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|github.com/moby/spdystream|v0.2.0|间接依赖|go|
|sigs.k8s.io/yaml|v1.3.0|直接依赖|go|
|google.golang.org/protobuf|v1.31.0|直接依赖|go|
|modernc.org/libc|v1.24.1|间接依赖|go|
|github.com/choleraehyq/pid|v0.0.17|间接依赖|go|
|io.opencensus:opencensus-impl-core|0.28.2|间接依赖|maven|
|github.com/coreos/go-semver|v0.3.0|间接依赖|go|
|github.com/cloudwego/thriftgo|v0.3.0|间接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|github.com/go-logr/logr|v1.2.3|间接依赖|go|
|github.com/rcrowley/go-metrics|v0.0.0-20201227073835-cf1acfcdf475|间接依赖|go|
|github.com/emirpasic/gods|v1.12.0|间接依赖|go|
|github.com/chebyrash/promise|v0.0.0-20230709133807-42ec49ba1459|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)