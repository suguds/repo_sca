# anchore/syft安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700573272391417856.svg)](https://www.murphysec.com/console/report/1700573272278171648/1700573272391417856)

仓库描述：CLI tool and library for generating a Software Bill of Materials from container images and filesystems

仓库地址：[https://github.com/anchore/syft](https://github.com/anchore/syft)

| star：4638 | watch：56 | fork：426 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-09 02:10:01 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-10 02:28:32 | 组件总数：307 | 漏洞总数：55 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|SnakeYAML <1.26 存在 Billion laughs 漏洞|拒绝服务|[MPS-2019-16129](https://www.oscs1024.com/hd/MPS-2019-16129)|CVE-2017-18640|高危|
|Apache Tomcat 授权问题漏洞|会话固定|[MPS-2019-16906](https://www.oscs1024.com/hd/MPS-2019-16906)|CVE-2019-17563|高危|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|Pivotal Spring Framework <5.2.3.RELEASE 反射文件下载 (RFD) 漏洞|下载代码缺少完整性检查|[MPS-2020-0902](https://www.oscs1024.com/hd/MPS-2020-0902)|CVE-2020-5398|高危|
|Spring Framework CSRF 漏洞|CSRF|[MPS-2020-0927](https://www.oscs1024.com/hd/MPS-2020-0927)|CVE-2020-5397|中危|
|Pivotal Spring Framework 反射文件下载 (RFD) 漏洞|路径遍历|[MPS-2020-13322](https://www.oscs1024.com/hd/MPS-2020-13322)|CVE-2020-5421|中危|
|Apache Tomcat HTTP请求走私漏洞|HTTP请求走私|[MPS-2020-15344](https://www.oscs1024.com/hd/MPS-2020-15344)|CVE-2020-13943|中危|
|FasterXML jackson-databind 代码问题漏洞|XXE|[MPS-2020-17358](https://www.oscs1024.com/hd/MPS-2020-17358)|CVE-2020-25649|高危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2020-17486](https://www.oscs1024.com/hd/MPS-2020-17486)|CVE-2020-17527|高危|
|Tomcat HTTP 请求走私漏洞|HTTP请求走私|[MPS-2020-2840](https://www.oscs1024.com/hd/MPS-2020-2840)|CVE-2020-1935|中危|
|Apache Tomcat 权限管理不当漏洞|权限管理不当|[MPS-2020-2841](https://www.oscs1024.com/hd/MPS-2020-2841)|CVE-2020-1938|严重|
|Apache Tomcat 存在 HTTP 请求走私|HTTP请求走私|[MPS-2020-2843](https://www.oscs1024.com/hd/MPS-2020-2843)|CVE-2019-17569|中危|
|minimist 原型污染漏洞|原型污染|[MPS-2020-3516](https://www.oscs1024.com/hd/MPS-2020-3516)|CVE-2020-7598|中危|
|hibernate-validator 存在输入验证错误漏洞|代码注入|[MPS-2020-7077](https://www.oscs1024.com/hd/MPS-2020-7077)|CVE-2020-10693|中危|
|Apache Tomcat 远程代码执行漏洞|反序列化|[MPS-2020-7626](https://www.oscs1024.com/hd/MPS-2020-7626)|CVE-2020-9484|高危|
|Apache Tomcat 拒绝服务漏洞|拒绝服务|[MPS-2020-9541](https://www.oscs1024.com/hd/MPS-2020-9541)|CVE-2020-11996|高危|
|Amazon Aws-sdk-js 原型污染漏洞|原型污染|[MPS-2021-0649](https://www.oscs1024.com/hd/MPS-2021-0649)|CVE-2020-28472|严重|
|Apache Tomcat 授权问题漏洞|身份验证不当|[MPS-2021-10264](https://www.oscs1024.com/hd/MPS-2021-10264)|CVE-2021-30640|中危|
|Apache Tomcat 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-1722](https://www.oscs1024.com/hd/MPS-2021-1722)|CVE-2021-24122|中危|
|Apache Tomcat 信息泄露漏洞|HTTP请求走私|[MPS-2021-2309](https://www.oscs1024.com/hd/MPS-2021-2309)|CVE-2021-25122|高危|
|Apache Tomcat 远程代码执行漏洞|代码注入|[MPS-2021-2466](https://www.oscs1024.com/hd/MPS-2021-2466)|CVE-2021-25329|高危|
|Apache Tomcat 拒绝服务漏洞|拒绝服务|[MPS-2021-31848](https://www.oscs1024.com/hd/MPS-2021-31848)|CVE-2021-41079|高危|
|Quality Open Software logback JNDI注入漏洞|反序列化|[MPS-2021-33911](https://www.oscs1024.com/hd/MPS-2021-33911)|CVE-2021-42550|中危|
|Apache Tomcat 条件竞争漏洞|竞争条件|[MPS-2021-37218](https://www.oscs1024.com/hd/MPS-2021-37218)|CVE-2021-43980|低危|
|minimist 安全漏洞|原型污染|[MPS-2021-38405](https://www.oscs1024.com/hd/MPS-2021-38405)|CVE-2021-44906|严重|
|Spring Framework权限许可和访问控制问题漏洞|权限管理不当|[MPS-2021-7485](https://www.oscs1024.com/hd/MPS-2021-7485)|CVE-2021-22118|高危|
|Apache Tomcat 环境问题漏洞|HTTP请求走私|[MPS-2021-9711](https://www.oscs1024.com/hd/MPS-2021-9711)|CVE-2021-33037|中危|
|Vmware Spring Framework 安全漏洞|不加限制或调节的资源分配|[MPS-2022-1080](https://www.oscs1024.com/hd/MPS-2022-1080)|CVE-2022-22950|中危|
|Pivotal Spring Framework 安全限制绕过漏洞|大小写敏感处理不恰当|[MPS-2022-1098](https://www.oscs1024.com/hd/MPS-2022-1098)|CVE-2022-22968|中危|
|Spring Framework spring-beans 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1101](https://www.oscs1024.com/hd/MPS-2022-1101)|CVE-2022-22970|中危|
|Logback SSL证书校验不当漏洞|中间人攻击|[MPS-2022-12411](https://www.oscs1024.com/hd/MPS-2022-12411)||中危|
|FasterXML Jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2022-12500](https://www.oscs1024.com/hd/MPS-2022-12500)||中危|
|passlib 存在弱口令要求漏洞|弱口令要求|[MPS-2022-15020](https://www.oscs1024.com/hd/MPS-2022-15020)||中危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|@actions/coret 命令注入漏洞|命令注入|[MPS-2022-51468](https://www.oscs1024.com/hd/MPS-2022-51468)|CVE-2022-35954|中危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|Python 安全漏洞|ReDoS|[MPS-2022-57238](https://www.oscs1024.com/hd/MPS-2022-57238)|CVE-2022-40897|中危|
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58307](https://www.oscs1024.com/hd/MPS-2022-58307)|CVE-2022-41723|高危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot在Cloud Foundry中部署存在路由限制绕过风险|访问控制不当|[MPS-2022-62845](https://www.oscs1024.com/hd/MPS-2022-62845)|CVE-2023-20873|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|spring-boot <2.2.11.RELEASE 存在目录劫持漏洞|将资源暴露给错误范围|[MPS-2022-6780](https://www.oscs1024.com/hd/MPS-2022-6780)|CVE-2022-27772|高危|
|spring-beans 远程代码执行漏洞(Spring4Shell)|表达式语言注入|[MPS-2022-6820](https://www.oscs1024.com/hd/MPS-2022-6820)|CVE-2022-22965|严重|
|Google Go 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2022-9049](https://www.oscs1024.com/hd/MPS-2022-9049)|CVE-2022-29526|中危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2023-8438](https://www.oscs1024.com/hd/MPS-2023-8438)|CVE-2021-46877|中危|
|Apache Tomcat FORM 重定向漏洞|跨站重定向|[MPS-uy56-j8e4](https://www.oscs1024.com/hd/MPS-uy56-j8e4)|CVE-2023-41080|低危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.apache.tomcat.embed:tomcat-embed-core|9.0.29|11.0.0-m6|间接依赖|强烈建议修复|C:1|H:7|M:6|L:2|
|aws-sdk|2.706.0|2.814.0|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework.boot:spring-boot|2.2.2.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|golang.org/x/net|v0.0.0-20211006190231-62292e806868|0.7.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-web|5.2.2.RELEASE|6.0.0|间接依赖|建议修复|C:1|H:2|M:1|L:0|
|ch.qos.logback:logback-core|1.2.3|1.2.8|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.10.1|2.14.0-rc1|间接依赖|建议修复|C:0|H:2|M:5|L:0|
|org.springframework:spring-beans|5.2.2.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.yaml:snakeyaml|1.25|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|minimist|0.0.10|1.2.6|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework:spring-context|5.2.2.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.2.2.RELEASE|3.0.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-webmvc|5.2.2.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.hibernate.validator:hibernate-validator|6.0.18.Final|6.1.3.Final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|@actions/core|1.6.0|1.9.1|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|golang.org/x/sys|v0.0.0-20211006194710-c8a6f5223071|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.2.2.RELEASE|3.0.7|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-expression|5.2.2.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|passlib|1.7.2|1.7.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|setuptools|39.2.0|65.5.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|50|Low|
|MIT|114|Low|
|Apache-2.0|90|Low|
|EPL-1.0|2|Low|
|ISC|5|Low|
|BSD-2-Clause|7|Low|
|GPL-2.0|1|Medium|
|CC-BY-4.0|1|Low|
|EPL-2.0|1|Low|
|MPL-2.0|4|Low|
|CC0-1.0|1|Low|
|自定义许可证|3|Low|
|Unlicense|1|Low|
|ICU|1|Low|
|CC-BY-SA-4.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/edsrzf/mmap-go|v1.1.0|间接依赖|go|
|github.com/muesli/reflow|v0.3.0|间接依赖|go|
|com.fasterxml.jackson.core:jackson-databind|2.10.1|间接依赖|maven|
|github.com/spf13/jwalterweatherman|v1.1.0|间接依赖|go|
|github.com/kastenhq/goversion|v0.0.0-20230811215019-93b2f8823953|直接依赖|go|
|github.com/dsnet/compress|v0.0.2-0.20210315054119-f66993602bf5|间接依赖|go|
|github.com/mitchellh/reflectwalk|v1.0.2|间接依赖|go|
|golang.org/x/text|v0.13.0|间接依赖|go|
|Texture/MapKit|3.1.0|间接依赖|cocoapods|
|github.com/charmbracelet/harmonica|v0.2.0|间接依赖|go|
|ch.qos.logback:logback-classic|1.2.3|间接依赖|maven|
|Texture/PINRemoteImage|3.1.0|间接依赖|cocoapods|
|github.com/ulikunitz/xz|v0.5.10|间接依赖|go|
|minimist|0.0.10|间接依赖|npm|
|string-width|2.1.1|间接依赖|npm|
|github.com/rogpeppe/go-internal|v1.11.0|间接依赖|go|
|insert-css|2.0.0|直接依赖|npm|
|github.com/muesli/termenv|v0.15.2|间接依赖|go|
|github.com/Masterminds/semver/v3|v3.2.0|间接依赖|go|
|github.com/deitch/magic|v0.0.0-20230404182410-1ff89d7342da|直接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|golang.org/x/exp|v0.0.0-20230817173708-d852ddb80c63|直接依赖|go|
|github.com/shopspring/decimal|v1.2.0|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.18|间接依赖|go|
|PINRemoteImage/iOS|3.0.3|间接依赖|cocoapods|
|github.com/golang/snappy|v0.0.4|间接依赖|go|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.2.2.RELEASE|间接依赖|maven|
|c0n-fab_u.laTION|7.7.7|直接依赖|npm|
|TextureSwiftSupport/Components|3.13.0|间接依赖|cocoapods|
|github.com/mitchellh/go-homedir|v1.1.0|直接依赖|go|
|mscoree.dll||间接依赖||
|github.com/muesli/ansi|v0.0.0-20211031195517-c9f0611b6c70|间接依赖|go|
|github.com/klauspost/pgzip|v1.2.5|间接依赖|go|
|github.com/aquasecurity/go-version|v0.0.0-20210121072130-637058cfe492|间接依赖|go|
|github.com/pelletier/go-toml|v1.9.5|直接依赖|go|
|golang.org/x/sync|v0.3.0|间接依赖|go|
|github.com/opencontainers/image-spec|v1.1.0-rc3|间接依赖|go|
|github.com/spf13/afero|v1.9.5|直接依赖|go|
|python-swiftclient|3.8.1|间接依赖|pip|
|github.com/wagoodman/go-progress|v0.0.0-20230301185719-21920a456ad5|直接依赖|go|
|modernc.org/libc|v1.24.1|间接依赖|go|
|Texture/AssetsLibrary|3.1.0|间接依赖|cocoapods|
|github.com/pborman/indent|v1.2.1|间接依赖|go|
|modernc.org/memory|v1.6.0|间接依赖|go|
|org.springframework:spring-webmvc|5.2.2.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.2.2.RELEASE|间接依赖|maven|
|github.com/CycloneDX/cyclonedx-go|v0.7.1|直接依赖|go|
|github.com/muesli/cancelreader|v0.2.2|间接依赖|go|
|PINOperation|1.2.1|间接依赖|cocoapods|
|github.com/klauspost/compress|v1.16.5|间接依赖|go|
|joda-time:joda-time|2.2|直接依赖|maven|
|github.com/aymanbagabas/go-osc52/v2|v2.0.1|间接依赖|go|
|modernc.org/strutil|v1.1.3|间接依赖|go|
|github.com/bmatcuk/doublestar|v1.3.1|直接依赖|go|
|aws-sdk|2.706.0|直接依赖|npm|
|pytz|2019.3|间接依赖|pip|
|github.com/anchore/go-testutils|v0.0.0-20200925183923-d5f45b0d3c04|直接依赖|go|
|github.com/gkampitakis/go-diff|v1.3.2|间接依赖|go|
|github.com/cloudflare/circl|v1.3.3|间接依赖|go|
|google.golang.org/grpc|v1.55.0|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.0|直接依赖|go|
|github.com/go-test/deep|v1.1.0|直接依赖|go|
|github.com/stretchr/testify|v1.8.4|直接依赖|go|
|flask|4.0.0|间接依赖|pip|
|@types/minimatch|3.0.3|直接依赖|npm|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|joda-time:joda-time|2.9.2|直接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.10.1|间接依赖|maven|
|github.com/anchore/stereoscope|v0.0.0-20230907152702-057dda3667e7|直接依赖|go|
|github.com/nwaples/rardecode|v1.1.0|间接依赖|go|
|TextureSwiftSupport/LayoutSpecBuilders|3.13.0|间接依赖|cocoapods|
|golang.org/x/crypto|v0.13.0|间接依赖|go|
|modernc.org/sqlite|v1.25.0|直接依赖|go|
|github.com/google/uuid|v1.3.1|直接依赖|go|
|github.com/spdx/tools-golang|v0.5.3|直接依赖|go|
|github.com/xo/terminfo|v0.0.0-20210125001918-ca9a967f8778|间接依赖|go|
|github.com/vbatts/tar-split|v0.11.3|间接依赖|go|
|github.com/Azure/go-ansiterm|v0.0.0-20210617225240-d185dfc1b5a1|间接依赖|go|
|github.com/sergi/go-diff|v1.3.1|直接依赖|go|
|github.com/dave/jennifer|v1.7.0|直接依赖|go|
|org.springframework:spring-expression|5.2.2.RELEASE|间接依赖|maven|
|github.com/scylladb/go-set|v1.0.3-0.20200225121959-cc7b2070d91e|直接依赖|go|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|strip-eof|1.0.0|间接依赖|npm|
|github.com/kevinburke/ssh_config|v1.2.0|间接依赖|go|
|github.com/charmbracelet/bubbletea|v0.24.2|直接依赖|go|
|github.com/magiconair/properties|v1.8.7|间接依赖|go|
|Texture/Video|3.1.0|间接依赖|cocoapods|
|collapse-white-space|2.0.0|直接依赖|npm|
|org.hibernate.validator:hibernate-validator|6.0.18.Final|间接依赖|maven|
|github.com/xeipuuv/gojsonpointer|v0.0.0-20190905194746-02993c407bfb|间接依赖|go|
|get-stdin|8.0.0|直接依赖|npm|
|org.hdrhistogram:HdrHistogram|2.1.11|间接依赖|maven|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|golang.org/x/term|v0.12.0|直接依赖|go|
|github.com/hashicorp/go-multierror|v1.1.1|直接依赖|go|
|TextureSwiftSupport|3.13.0|间接依赖|cocoapods|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.10.1|间接依赖|maven|
|github.com/anchore/fangs|v0.0.0-20230818131516-2186b10924fe|直接依赖|go|
|org.jenkins-ci:symbol-annotation|1.20|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.10.1|间接依赖|maven|
|github.com/rivo/uniseg|v0.2.0|间接依赖|go|
|github.com/tidwall/pretty|v1.2.1|间接依赖|go|
|org.springframework.boot:spring-boot-starter-tomcat|2.2.2.RELEASE|间接依赖|maven|
|github.com/therootcompany/xz|v1.0.1|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|间接依赖|go|
|github.com/iancoleman/orderedmap|v0.0.0-20190318233801-ac98e3ecb4b0|间接依赖|go|
|github.com/andybalholm/brotli|v1.0.4|间接依赖|go|
|github.com/imdario/mergo|v0.3.15|间接依赖|go|
|github.com/mitchellh/copystructure|v1.2.0|间接依赖|go|
|github.com/pelletier/go-toml/v2|v2.0.8|间接依赖|go|
|github.com/bmatcuk/doublestar/v4|v4.6.0|直接依赖|go|
|TextureSwiftSupport/Experiments|3.13.0|间接依赖|cocoapods|
|modernc.org/ccgo/v3|v3.16.13|间接依赖|go|
|github.com/charmbracelet/bubbles|v0.16.1|间接依赖|go|
|github.com/mattn/go-localereader|v0.0.2-0.20220822084749-2491eb6c1c75|间接依赖|go|
|github.com/docker/docker-credential-helpers|v0.7.0|间接依赖|go|
|end-of-stream|1.4.4|间接依赖|npm|
|github.com/google/pprof|v0.0.0-20221118152302-e6195bd50e26|间接依赖|go|
|org.jboss.logging:jboss-logging|3.4.1.Final|间接依赖|maven|
|gopkg.in/ini.v1|v1.67.0|间接依赖|go|
|github.com/go-restruct/restruct|v1.2.0-alpha|间接依赖|go|
|github.com/iancoleman/strcase|v0.3.0|直接依赖|go|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|github.com/docker/distribution|v2.8.2+incompatible|直接依赖|go|
|github.com/xanzy/ssh-agent|v0.3.3|间接依赖|go|
|github.com/anchore/packageurl-go|v0.1.1-0.20230104203445-02e0a6721501|直接依赖|go|
|github.com/huandu/xstrings|v1.3.3|间接依赖|go|
|github.com/Masterminds/sprig/v3|v3.2.3|直接依赖|go|
|jhipster-core|7.3.4|直接依赖|npm|
|github.com/spf13/cobra|v1.7.0|直接依赖|go|
|org.slf4j:jul-to-slf4j|1.7.29|间接依赖|maven|
|github.com/anchore/go-macholibre|v0.0.0-20220308212642-53e6d0aaf6fb|直接依赖|go|
|github.com/hashicorp/errwrap|v1.1.0|间接依赖|go|
|org.apache.logging.log4j:log4j-to-slf4j|2.12.1|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.29|间接依赖|maven|
|dario.cat/mergo|v1.0.0|间接依赖|go|
|jsonschema|2.6.0|间接依赖|pip|
|setuptools|39.2.0|间接依赖|pip|
|github.com/sirupsen/logrus|v1.9.3|间接依赖|go|
|github.com/CycloneDX/cyclonedx-go|v0.7.0|直接依赖|go|
|github.com/logrusorgru/aurora|v0.0.0-20200102142835-e9ef32dff381|间接依赖|go|
|com.joda:joda-time|2.9.2|直接依赖|maven|
|github.com/remyoudompheng/bigfft|v0.0.0-20230129092748-24d4a6f8daec|间接依赖|go|
|modernc.org/token|v1.0.1|间接依赖|go|
|PINCache|3.0.3|间接依赖|cocoapods|
|golang.org/x/tools|v0.12.1-0.20230815132531-74c255bcf846|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|org.springframework.boot:spring-boot-starter|2.2.2.RELEASE|间接依赖|maven|
|github.com/containerd/stargz-snapshotter/estargz|v0.14.3|间接依赖|go|
|github.com/sylabs/sif/v2|v2.11.5|间接依赖|go|
|asn1.js|4.10.1|直接依赖|npm|
|golang.org/x/net|v0.0.0-20211006190231-62292e806868|直接依赖|go|
|ajv|6.12.3|直接依赖|npm|
|github.com/containerd/console|v1.0.4-0.20230313162750-1ae8d489ac81|间接依赖|go|
|PINRemoteImage/Core|3.0.3|间接依赖|cocoapods|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.29|间接依赖|maven|
|github.com/Masterminds/semver|v1.5.0|直接依赖|go|
|org.apache.logging.log4j:log4j-api|2.12.1|间接依赖|maven|
|github.com/containerd/containerd|v1.7.0|间接依赖|go|
|modernc.org/opt|v0.1.3|间接依赖|go|
|github.com/tidwall/match|v1.1.1|间接依赖|go|
|github.com/anchore/go-version|v1.2.2-0.20200701162849-18adb9c92b9b|直接依赖|go|
|TextureSwiftSupport/Extensions|3.13.0|间接依赖|cocoapods|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|async|0.9.2|直接依赖|npm|
|github.com/docker/docker|v24.0.6+incompatible|直接依赖|go|
|github.com/adrg/xdg|v0.4.0|间接依赖|go|
|org.jenkins-ci.plugins:structs|1.20|直接依赖|maven|
|@babel/code-frame|7.10.4|直接依赖|npm|
|TinyConstraints|4.0.2|间接依赖|cocoapods|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|github.com/spf13/viper|v1.16.0|间接依赖|go|
|github.com/go-git/go-billy/v5|v5.4.1|直接依赖|go|
|pump|3.0.0|直接依赖|npm|
|github.com/mholt/archiver/v3|v3.5.1|直接依赖|go|
|github.com/acomagu/bufpipe|v1.0.4|间接依赖|go|
|github.com/Masterminds/goutils|v1.1.1|间接依赖|go|
|github.com/mattn/go-runewidth|v0.0.14|间接依赖|go|
|lukechampine.com/uint128|v1.2.0|间接依赖|go|
|strip-ansi|4.0.0|间接依赖|npm|
|github.com/tidwall/sjson|v1.2.5|间接依赖|go|
|github.com/DataDog/zstd|v1.4.5|间接依赖|go|
|PINCache/Arc-exception-safe|3.0.3|间接依赖|cocoapods|
|github.com/felixge/fgprof|v0.9.3|间接依赖|go|
|should-type|1.3.0|直接依赖|npm|
|github.com/wagoodman/go-partybus|v0.0.0-20230516145632-8ccac152c651|直接依赖|go|
|Texture/Photos|3.1.0|间接依赖|cocoapods|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.10.1|间接依赖|maven|
|github.com/aquasecurity/go-pep440-version|v0.0.0-20210121094942-22b2f8951d46|直接依赖|go|
|com.fasterxml.jackson.core:jackson-core|2.10.1|间接依赖|maven|
|github.com/go-git/go-git/v5|v5.8.1|直接依赖|go|
|github.com/mgutz/ansi|v0.0.0-20200706080929-d51e80ef957d|间接依赖|go|
|github.com/jinzhu/copier|v0.4.0|直接依赖|go|
|golang.org/x/net|v0.15.0|直接依赖|go|
|org.joda:joda-convert|1.2|直接依赖|maven|
|github.com/docker/go-units|v0.5.0|间接依赖|go|
|PINRemoteImage/PINCache|3.0.3|间接依赖|cocoapods|
|passlib|1.7.2|间接依赖|pip|
|@actions/core|1.6.0|直接依赖|npm|
|org.springframework.boot:spring-boot|2.2.2.RELEASE|间接依赖|maven|
|github.com/kr/text|v0.2.0|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|直接依赖|go|
|github.com/docker/cli|v24.0.0+incompatible|间接依赖|go|
|github.com/mitchellh/hashstructure/v2|v2.0.2|直接依赖|go|
|Texture/Core|3.1.0|间接依赖|cocoapods|
|github.com/skeema/knownhosts|v1.2.0|间接依赖|go|
|org.springframework.boot:spring-boot-actuator|2.2.2.RELEASE|间接依赖|maven|
|github.com/anchore/clio|v0.0.0-20230823172630-c42d666061af|直接依赖|go|
|github.com/gkampitakis/ciinfo|v0.2.5|间接依赖|go|
|github.com/gookit/color|v1.5.4|直接依赖|go|
|ansi-regex|3.0.0|间接依赖|npm|
|github.com/vbatts/go-mtree|v0.5.3|直接依赖|go|
|github.com/go-git/gcfg|v1.5.1-0.20230307220236-3a3c6141e376|间接依赖|go|
|github.com/spf13/cast|v1.5.1|间接依赖|go|
|github.com/kr/pretty|v0.3.1|间接依赖|go|
|github.com/vifraa/gopom|v1.0.0|直接依赖|go|
|github.com/docker/go-connections|v0.4.0|间接依赖|go|
|github.com/github/go-spdx/v2|v2.1.2|直接依赖|go|
|is-fullwidth-code-point|2.0.0|间接依赖|npm|
|org.springframework.boot:spring-boot-starter-logging|2.2.2.RELEASE|间接依赖|maven|
|github.com/anchore/bubbly|v0.0.0-20230801194016-acdb4981b461|直接依赖|go|
|github.com/pjbgf/sha1cd|v0.3.0|间接依赖|go|
|github.com/jbenet/go-context|v0.0.0-20150711004518-d14ea06fba99|间接依赖|go|
|get-stdin|5.0.1|间接依赖|npm|
|SwiftGen|6.5.1|间接依赖|cocoapods|
|ch.qos.logback:logback-core|1.2.3|间接依赖|maven|
|github.com/xeipuuv/gojsonreference|v0.0.0-20180127040603-bd5ef7bd5415|间接依赖|go|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.29|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-actuator|2.2.2.RELEASE|直接依赖|maven|
|github.com/invopop/jsonschema|v0.7.0|直接依赖|go|
|wordwrap|0.0.3|间接依赖|npm|
|github.com/charmbracelet/lipgloss|v0.8.0|直接依赖|go|
|golang.org/x/sys|v0.0.0-20211006194710-c8a6f5223071|间接依赖|go|
|org.springframework:spring-aop|5.2.2.RELEASE|间接依赖|maven|
|@types/qs|6.9.4|直接依赖|npm|
|Texture|3.1.0|间接依赖|cocoapods|
|org.springframework.boot:spring-boot-autoconfigure|2.2.2.RELEASE|间接依赖|maven|
|optimist|0.6.1|间接依赖|npm|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|modernc.org/mathutil|v1.5.0|间接依赖|go|
|org.springframework.boot:spring-boot-starter-validation|2.2.2.RELEASE|间接依赖|maven|
|github.com/Microsoft/go-winio|v0.6.1|间接依赖|go|
|atob|2.1.2|直接依赖|npm|
|github.com/anchore/packageurl-go|v0.1.1-0.20220428202044-a072fa3cb6d7|直接依赖|go|
|github.com/knqyf263/go-rpmdb|v0.0.0-20230301153543-ba94b245509b|直接依赖|go|
|google.golang.org/protobuf|v1.30.0|间接依赖|go|
|github.com/anchore/go-struct-converter|v0.0.0-20221118182256-c68fdcfa2092|间接依赖|go|
|org.springframework:spring-beans|5.2.2.RELEASE|间接依赖|maven|
|python-dateutil|2.8.1|间接依赖|pip|
|wrappy|1.0.2|间接依赖|npm|
|github.com/kballard/go-shellquote|v0.0.0-20180428030007-95032a82bc51|间接依赖|go|
|PINCache/Core|3.0.3|间接依赖|cocoapods|
|github.com/emirpasic/gods|v1.18.1|间接依赖|go|
|github.com/ProtonMail/go-crypto|v0.0.0-20230717121422-5aa5874ade95|间接依赖|go|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|github.com/zyedidia/generic|v1.2.2-0.20230320175451-4410d2372cb1|直接依赖|go|
|github.com/anchore/go-logger|v0.0.0-20230725134548-c21dafa1ec5a|直接依赖|go|
|github.com/tidwall/gjson|v1.16.0|间接依赖|go|
|org.springframework:spring-web|5.2.2.RELEASE|间接依赖|maven|
|github.com/saferwall/pe|v1.4.5|直接依赖|go|
|github.com/acarl005/stripansi|v0.0.0-20180116102854-5a71ef0e047d|直接依赖|go|
|github.com/xi2/xz|v0.0.0-20171230120015-48954b6210f8|间接依赖|go|
|async|3.2.3|直接依赖|npm|
|github.com/google/go-containerregistry|v0.16.1|直接依赖|go|
|github.com/olekukonko/tablewriter|v0.0.5|直接依赖|go|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|joda-time:joda-time||直接依赖|maven|
|github.com/gabriel-vasile/mimetype|v1.4.0|间接依赖|go|
|cowsay|1.4.0|直接依赖|npm|
|github.com/saintfish/chardet|v0.0.0-20230101081208-5e3ef4b5456d|直接依赖|go|
|once|1.4.0|间接依赖|npm|
|golang.org/x/mod|v0.12.0|直接依赖|go|
|github.com/sassoftware/go-rpmutils|v0.2.0|直接依赖|go|
|org.springframework:spring-context|5.2.2.RELEASE|间接依赖|maven|
|github.com/gkampitakis/go-snaps|v0.4.10|直接依赖|go|
|io.micrometer:micrometer-core|1.3.1|间接依赖|maven|
|github.com/subosito/gotenv|v1.4.2|间接依赖|go|
|github.com/pkg/profile|v1.7.0|间接依赖|go|
|github.com/pierrec/lz4/v4|v4.1.15|间接依赖|go|
|github.com/microsoft/go-rustaudit|v0.0.0-20220730194248-4b17361d90a5|直接依赖|go|
|github.com/acobaugh/osrelease|v0.1.0|直接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0|直接依赖|go|
|org.yaml:snakeyaml|1.25|间接依赖|maven|
|google.golang.org/genproto|v0.0.0-20230410155749-daa745c078e1|间接依赖|go|
|golang.org/x/sys|v0.12.0|间接依赖|go|
|go.mozilla.org/pkcs7|v0.0.0-20210826202110-33d05740a352|间接依赖|go|
|github.com/dustin/go-humanize|v1.0.1|直接依赖|go|
|golang.org/x/term|v0.0.0-20210927222741-03fcf44c2211|直接依赖|go|
|resize-observer-polyfill|1.5.2|直接依赖|npm|
|github.com/sylabs/squashfs|v0.6.1|间接依赖|go|
|github.com/lucasb-eyer/go-colorful|v1.2.0|间接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|github.com/xeipuuv/gojsonschema|v1.2.0|直接依赖|go|
|github.com/becheran/wildmatch-go|v1.0.0|间接依赖|go|
|github.com/facebookincubator/nvdtools|v0.1.5|直接依赖|go|
|gopkg.in/warnings.v0|v0.1.2|间接依赖|go|
|github.com/google/licensecheck|v0.3.1|直接依赖|go|
|merge-objects|1.0.5|直接依赖|npm|
|GlossButtonNode|3.1.2|间接依赖|cocoapods|
|org.springframework.boot:spring-boot-starter-web|2.2.2.RELEASE|直接依赖|maven|
|Reveal-SDK|33|间接依赖|cocoapods|
|golang.org/x/xerrors|v0.0.0-20220907171357-04be3eba64a2|间接依赖|go|
|modernc.org/cc/v3|v3.40.0|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)