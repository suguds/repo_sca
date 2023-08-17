# jeecgboot/jeecg-boot安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692235119534563328.svg)](https://www.murphysec.com/console/report/1692235119228379136/1692235119534563328)

仓库描述：🔥「企业级低代码平台」前后端分离架构SpringBoot 2.x，SpringCloud，Ant Design&Vue，Mybatis，Shiro，JWT。强大的代码生成器让前后端代码一键生成，无需写任何代码! 引领新的开发模式OnlineCoding->代码生成->手工MERGE，帮助Java项目解决70%重复工作，让开发更关注业务，既能快速提高效率，帮助公司节省成本，同时又不失灵活性。

仓库地址：[https://github.com/jeecgboot/jeecg-boot](https://github.com/jeecgboot/jeecg-boot)

| star：35597 | watch：842 | fork：13817 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-17 16:16:37 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-18 02:06:35 | 组件总数：638 | 漏洞总数：80 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|多款Cisco产品Apache Commons Collections库任意代码执行漏洞|反序列化|[MPS-2015-6277](https://www.oscs1024.com/hd/MPS-2015-6277)|CVE-2015-6420|高危|
|多款Red Hat产品代码问题漏洞|反序列化|[MPS-2017-12638](https://www.oscs1024.com/hd/MPS-2017-12638)|CVE-2015-7501|严重|
|Apache Log4j SocketServer反序列化漏洞|反序列化|[MPS-2019-17271](https://www.oscs1024.com/hd/MPS-2019-17271)|CVE-2019-17571|严重|
|SOFA-Hessian 代码问题漏洞||[MPS-2019-1978](https://www.oscs1024.com/hd/MPS-2019-1978)|CVE-2019-9212|严重|
|Checkstyle <8.18存在 XXE 注入漏洞|XXE|[MPS-2019-2390](https://www.oscs1024.com/hd/MPS-2019-2390)|CVE-2019-9658|中危|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|MyBatis <3.5.6 存在反序列化漏洞|反序列化|[MPS-2020-14133](https://www.oscs1024.com/hd/MPS-2020-14133)|CVE-2020-26945|高危|
|checkstyle  <8.29存在XXE漏洞|XXE|[MPS-2020-1591](https://www.oscs1024.com/hd/MPS-2020-1591)|CVE-2019-10782|中危|
|Apache HttpClient URI解析错误漏洞|XSS|[MPS-2020-17341](https://www.oscs1024.com/hd/MPS-2020-17341)|CVE-2020-13956|中危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Apache Groovy 临时目录信息泄露漏洞|缺省权限不正确|[MPS-2020-17573](https://www.oscs1024.com/hd/MPS-2020-17573)|CVE-2020-17521|中危|
|XXL-JOB 跨站脚本漏洞|XSS|[MPS-2020-18025](https://www.oscs1024.com/hd/MPS-2020-18025)|CVE-2020-29204|中危|
|Apache Log4j2 SmtpAppender证书验证不当漏洞|证书验证不恰当|[MPS-2020-6684](https://www.oscs1024.com/hd/MPS-2020-6684)|CVE-2020-9488|低危|
|Apache Commons Compress 安存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10550](https://www.oscs1024.com/hd/MPS-2021-10550)|CVE-2021-35517|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10551](https://www.oscs1024.com/hd/MPS-2021-10551)|CVE-2021-35516|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10564](https://www.oscs1024.com/hd/MPS-2021-10564)|CVE-2021-36090|高危|
|Apache Commons Compress 无限循环漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-10565](https://www.oscs1024.com/hd/MPS-2021-10565)|CVE-2021-35515|高危|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|AviatorScript 存在注入漏洞|注入|[MPS-2021-32682](https://www.oscs1024.com/hd/MPS-2021-32682)|CVE-2021-41862|严重|
|Oracle MySQL 的 MySQL Connectors 存在授权不当漏洞|授权机制不恰当|[MPS-2021-36587](https://www.oscs1024.com/hd/MPS-2021-36587)|CVE-2022-21363|中危|
|Jeecg-Boot 安全漏洞|XSS|[MPS-2021-37988](https://www.oscs1024.com/hd/MPS-2021-37988)|CVE-2021-44585|中危|
|Apache Log4j JMSAppender反序列化漏洞||[MPS-2021-38359](https://www.oscs1024.com/hd/MPS-2021-38359)|CVE-2021-4104|高危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|JDOM 存在 XXE 注入漏洞|XXE|[MPS-2021-8350](https://www.oscs1024.com/hd/MPS-2021-8350)|CVE-2021-33813|高危|
|Red Hat XNIO 资源错误分配漏洞|不加限制或调节的资源分配|[MPS-2022-0191](https://www.oscs1024.com/hd/MPS-2022-0191)|CVE-2022-0084|高危|
|SpringCloudFunction 存在拒绝服务漏洞|拒绝服务|[MPS-2022-1109](https://www.oscs1024.com/hd/MPS-2022-1109)|CVE-2022-22979|中危|
|PostgreSQL JDBC 存在 SQL 注入漏洞|SQL注入|[MPS-2022-11227](https://www.oscs1024.com/hd/MPS-2022-11227)|CVE-2022-31197|高危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|com.beust:jcommander 存在从非可信控制范围包含功能例程漏洞||[MPS-2022-12225](https://www.oscs1024.com/hd/MPS-2022-12225)||中危|
|io.springfox:springfox-swagger2 存在输入验证不恰当漏洞|日志敏感信息泄露|[MPS-2022-12534](https://www.oscs1024.com/hd/MPS-2022-12534)||中危|
|Apache Commons Collections 远程代码执行漏洞|反序列化|[MPS-2022-12767](https://www.oscs1024.com/hd/MPS-2022-12767)||高危|
|Apache Log4j JDBCAppender SQL注入漏洞|SQL注入|[MPS-2022-1444](https://www.oscs1024.com/hd/MPS-2022-1444)|CVE-2022-23305|严重|
|Apache Log4j Chainsaw反序列化漏洞|反序列化|[MPS-2022-1445](https://www.oscs1024.com/hd/MPS-2022-1445)|CVE-2022-23307|高危|
|Apache Log4j 反序列化漏洞|反序列化|[MPS-2022-1446](https://www.oscs1024.com/hd/MPS-2022-1446)|CVE-2022-23302|高危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|Apache Calcite Avatica 代码注入漏洞|代码注入|[MPS-2022-51965](https://www.oscs1024.com/hd/MPS-2022-51965)|CVE-2022-36364|高危|
|jeecg 安全漏洞|任意文件上传|[MPS-2022-53229](https://www.oscs1024.com/hd/MPS-2022-53229)|CVE-2022-2647|严重|
|Bouncy Castle <1.69 认证绕过漏洞|密码学问题|[MPS-2022-54305](https://www.oscs1024.com/hd/MPS-2022-54305)||中危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|Apache Calcite 存在 XXE 漏洞|XXE|[MPS-2022-56508](https://www.oscs1024.com/hd/MPS-2022-56508)|CVE-2022-39135|中危|
|Apache POI <5.2.1 拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-5663](https://www.oscs1024.com/hd/MPS-2022-5663)|CVE-2022-26336|中危|
|Jettison <1.5.2 拒绝服务漏洞|拒绝服务|[MPS-2022-57067](https://www.oscs1024.com/hd/MPS-2022-57067)|CVE-2022-40150|高危|
|Jettison <1.5.1 拒绝服务漏洞|越界写入|[MPS-2022-57068](https://www.oscs1024.com/hd/MPS-2022-57068)|CVE-2022-40149|高危|
|xuxueli xxl-job 存在命令注入漏洞|命令注入|[MPS-2022-57270](https://www.oscs1024.com/hd/MPS-2022-57270)|CVE-2022-40929|严重|
|postgresql <42.3.3 存在代码注入漏洞|代码注入|[MPS-2022-5828](https://www.oscs1024.com/hd/MPS-2022-5828)|CVE-2022-26520|严重|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|pgjdbc <42.5.1 存在信息泄露漏洞|不安全的临时文件|[MPS-2022-58583](https://www.oscs1024.com/hd/MPS-2022-58583)|CVE-2022-41946|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|Spring Security通配符路由绕过漏洞|关键资源权限分配不当|[MPS-2022-62832](https://www.oscs1024.com/hd/MPS-2022-62832)|CVE-2023-20860|高危|
|Spring 处理 SpEL 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62833](https://www.oscs1024.com/hd/MPS-2022-62833)|CVE-2023-20861|中危|
|Spring Security Logout实现不当|会话固定|[MPS-2022-62834](https://www.oscs1024.com/hd/MPS-2022-62834)|CVE-2023-20862|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot在Cloud Foundry中部署存在路由限制绕过风险|访问控制不当|[MPS-2022-62845](https://www.oscs1024.com/hd/MPS-2022-62845)|CVE-2023-20873|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|Jettison <1.5.2 拒绝服务漏洞|越界写入|[MPS-2022-64973](https://www.oscs1024.com/hd/MPS-2022-64973)|CVE-2022-45685|高危|
|Jeecg-Boot SQL注入漏洞|SQL注入|[MPS-2022-67588](https://www.oscs1024.com/hd/MPS-2022-67588)|CVE-2022-47105|严重|
|Red Hat Undertow 安全漏洞|证书验证不恰当|[MPS-2022-68061](https://www.oscs1024.com/hd/MPS-2022-68061)|CVE-2022-4492|高危|
|Hutool zip 拒绝服务漏洞||[MPS-2022-68308](https://www.oscs1024.com/hd/MPS-2022-68308)|CVE-2022-4565|中危|
|Oracle MySQL 安全漏洞||[MPS-2022-68556](https://www.oscs1024.com/hd/MPS-2022-68556)|CVE-2023-21971|中危|
|Red Hat Undertow 资源管理错误漏洞|拒绝服务|[MPS-2022-7892](https://www.oscs1024.com/hd/MPS-2022-7892)|CVE-2022-1259|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|hutool 存在反序列化漏洞|反序列化|[MPS-2023-2460](https://www.oscs1024.com/hd/MPS-2023-2460)|CVE-2023-24162|高危|
|Apache Commons FileUpload <1.5 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2023-3553](https://www.oscs1024.com/hd/MPS-2023-3553)|CVE-2023-24998|中危|
|XXL-JOB 跨站请求伪造漏洞|CSRF|[MPS-2023-3818](https://www.oscs1024.com/hd/MPS-2023-3818)|CVE-2023-0674|中危|
|【存在争议】MybatisPlus <= 3.5.3.1 TenantPlugin 组件 存在 sql 注入漏洞|SQL注入|[MPS-2023-3977](https://www.oscs1024.com/hd/MPS-2023-3977)|CVE-2023-25330|高危|
|xxl-job 存在存储型XSS漏洞|XSS|[MPS-2023-5196](https://www.oscs1024.com/hd/MPS-2023-5196)||中危|
|Jettison 安全漏洞|未经控制的递归|[MPS-2023-8270](https://www.oscs1024.com/hd/MPS-2023-8270)|CVE-2023-1436|高危|
|Hutool createTempFile函数敏感信息泄漏漏洞|未授权敏感信息泄露|[MPS-4soz-eyma](https://www.oscs1024.com/hd/MPS-4soz-eyma)|CVE-2023-33695|中危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Spring Security 路径匹配漏洞|不恰当实现的标准安全检查|[MPS-j3nx-691g](https://www.oscs1024.com/hd/MPS-j3nx-691g)|CVE-2023-34034|严重|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|基于 Thymeleaf 沙箱逃逸的 Spring Boot Admin 远程代码执行漏洞|代码注入|[MPS-p6bo-i7nw](https://www.oscs1024.com/hd/MPS-p6bo-i7nw)|CVE-2023-38286|严重|
|HuTool XML外部实体注入漏洞|XXE|[MPS-xd3s-4gev](https://www.oscs1024.com/hd/MPS-xd3s-4gev)|CVE-2023-3276|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|cn.hutool:hutool-core|5.3.8|5.8.20|间接依赖|强烈建议修复|C:0|H:1|M:3|L:0|
|de.codecentric:spring-boot-admin-server|2.3.1||间接依赖|强烈建议修复|C:1|H:0|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.4.2|2.14.0-rc1|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.mysql:mysql-connector-j|8.0.31|8.0.33|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.7.10|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.29|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|org.mybatis:mybatis|3.5.5|3.5.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.6.14|3.0.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.postgresql:postgresql|42.2.25|42.5.1|直接依赖|建议修复|C:1|H:1|M:1|L:0|
|log4j:log4j|1.2.17||间接依赖|建议修复|C:2|H:3|M:0|L:1|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.7.10|3.0.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.30|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|commons-collections:commons-collections|3.2.1|3.2.2|间接依赖|建议修复|C:1|H:2|M:0|L:0|
|com.xuxueli:xxl-job-core|2.2.0|2.3.0|直接依赖|建议修复|C:1|H:0|M:3|L:0|
|com.squareup.okio:okio|2.4.3|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|log4j:log4j|1.2.14||间接依赖|建议修复|C:2|H:3|M:0|L:1|
|com.google.protobuf:protobuf-java|3.11.4|3.21.7|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|io.undertow:undertow-core|2.2.23.Final|2.3.6.final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|commons-fileupload:commons-fileupload|1.4|1.5|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-web|5.3.26|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|io.netty:netty-handler|4.1.90.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.13.5|2.14.0-rc1|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework.security:spring-security-web|5.7.7|6.1.2|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.apache.commons:commons-compress|1.19|1.21|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|org.springframework:spring-webmvc|5.3.24|6.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.jeecgframework.boot:jeecg-boot-base-core|3.5.3||直接依赖|建议修复|C:2|H:0|M:1|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.6.14|3.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-web|5.3.24|6.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.googlecode.aviator:aviator|5.2.6||间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.apache.calcite.avatica:avatica-core|1.18.0|1.22.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.alipay.sofa:hessian|3.3.6|4.0.3|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.codehaus.jettison:jettison|1.1|1.5.4|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|com.baomidou:mybatis-plus-extension|3.5.3||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.security:spring-security-web|5.6.9|6.1.2|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.apache.poi:poi-scratchpad|4.1.2|5.2.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework.cloud:spring-cloud-function-context|3.2.5|3.2.6|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.codehaus.groovy:groovy|2.4.19|4.0.0-alpha-2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|5.3.24|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.httpcomponents:httpclient|4.5.3|4.5.13|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-core|5.3.24|6.0.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.puppycrawl.tools:checkstyle|8.3|8.29|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|31.1-android|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.calcite:calcite-core|1.27.0|1.32.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-io:commons-io|2.6|2.7|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.beust:jcommander|1.72|1.75|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|29.0-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:1|
|com.google.guava:guava|30.1-jre|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|mysql:mysql-connector-java|8.0.27|8.0.28|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.springfox:springfox-swagger2|3.0.0||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.bouncycastle:bcprov-jdk15on|1.68|1.69|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.jdom:jdom|1.1||间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-expression|5.3.26|6.0.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.jboss.xnio:xnio-api|3.8.7.Final|3.8.8|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|527|Low|
|BSD-2-Clause|4|Low|
|BSD-3-Clause|13|Low|
|EPL-2.0|9|Low|
|CDDL-1.1|4|Low|
|LGPL-2.1-or-later|2|Low|
|EPL-1.0|6|Low|
|MIT|11|Low|
|LGPL-2.1|4|Medium|
|MPL-1.1|1|Low|
|LGPL-3.0|2|Medium|
|MIT-0|1|Low|
|MPL-2.0|3|Low|
|GPL-2.0|2|Medium|
|LGPL-2.1+|1|Low|
|GPL-3.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.apache.shardingsphere:shardingsphere-infra-parser|5.0.0|间接依赖|maven|
|com.yahoo.datasketches:memory|0.9.0|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|cn.hutool:hutool-crypto|5.3.8|间接依赖|maven|
|com.google.code.gson:gson|2.9.1|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-core|4.5.10|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-db-discovery-mgr|5.0.0|间接依赖|maven|
|javax.validation:validation-api|2.0.1.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-webflux|2.7.10|间接依赖|maven|
|com.alibaba.cloud:spring-cloud-starter-alibaba-nacos-discovery|2021.0.1.0|直接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|org.jeecgframework.jimureport:jimureport-spring-boot-starter|1.6.1|直接依赖|maven|
|com.alibaba.nacos:nacos-common|1.4.2|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-sql-parser-statement|5.0.0|间接依赖|maven|
|com.github.xiaoymin:knife4j-spring|3.0.3|间接依赖|maven|
|io.springfox:springfox-spi|3.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-reactor-netty|2.7.10|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.69|间接依赖|maven|
|io.projectreactor.addons:reactor-extra|3.4.10|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.6.14|间接依赖|maven|
|com.lmax:disruptor|3.3.7|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.69|间接依赖|maven|
|org.jeecgframework.boot:jeecg-boot-starter-rabbitmq|3.5.3|直接依赖|maven|
|org.springframework.plugin:spring-plugin-metadata|2.0.0.RELEASE|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-single-table-api|5.0.0|间接依赖|maven|
|org.apache.commons:commons-pool2|2.11.1|间接依赖|maven|
|log4j:log4j|1.2.14|间接依赖|maven|
|org.apache.poi:poi-ooxml|4.1.2|间接依赖|maven|
|de.codecentric:spring-boot-admin-server|2.3.1|间接依赖|maven|
|io.swagger.core.v3:swagger-annotations|2.1.2|间接依赖|maven|
|io.micrometer:micrometer-core|1.9.9|间接依赖|maven|
|io.opentracing:opentracing-api|0.33.0|间接依赖|maven|
|org.ow2.asm:asm|5.0.3|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-db-discovery-distsql-parser|5.0.0|间接依赖|maven|
|org.apache.zookeeper:zookeeper-jute|3.6.0|间接依赖|maven|
|org.codehaus.jettison:jettison|1.1|间接依赖|maven|
|org.glassfish:javax.json|1.0.4|间接依赖|maven|
|org.jeecgframework.jimureport:jimureport-font|1.1.0|间接依赖|maven|
|org.apache.calcite.avatica:avatica-metrics|1.18.0|间接依赖|maven|
|org.jeecgframework.nacos:nacos-plugin-default-impl|2.2.3|间接依赖|maven|
|com.google.code.gson:gson|2.8.9|间接依赖|maven|
|org.pegdown:pegdown|1.6.0|直接依赖|maven|
|org.springframework.amqp:spring-amqp|2.4.11|间接依赖|maven|
|org.apache.shardingsphere.elasticjob:elasticjob-dataflow-executor|3.0.1|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-memory-mode-core|5.0.0|间接依赖|maven|
|org.jeecgframework.boot:jeecg-boot-base-core|3.5.3|直接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-starter|2.1.3|直接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|org.springframework.cloud:spring-cloud-stream-binder-rabbit|3.2.4|间接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-system-datetime|5.0.0|间接依赖|maven|
|io.prometheus:simpleclient_tracer_otel_agent|0.15.0|间接依赖|maven|
|org.jeecgframework.boot:drag-free|1.0.2|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-redis-reactive|2.7.10|直接依赖|maven|
|org.jeecgframework.nacos:nacos-datasource-plugin|2.2.3|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-single-table-core|5.0.0|间接依赖|maven|
|org.springframework.security:spring-security-config|5.6.9|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-jdbc-core-spring-boot-starter|5.0.0|间接依赖|maven|
|antlr:antlr|2.7.7|间接依赖|maven|
|org.jeecgframework.boot:hibernate-re|3.5.3|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.3.4|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-mode-core|5.0.0|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-shadow-api|5.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-mail|2.7.10|直接依赖|maven|
|org.apache.shardingsphere:shardingsphere-infra-datetime-spi|5.0.0|间接依赖|maven|
|com.alibaba.cloud:spring-cloud-alibaba-commons|2021.0.1.0|间接依赖|maven|
|io.github.openfeign:feign-core|11.8|间接依赖|maven|
|jakarta.servlet:jakarta.servlet-api|4.0.4|间接依赖|maven|
|org.parboiled:parboiled-java|1.1.7|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.6.14|间接依赖|maven|
|com.alipay.sofa:jraft-core|1.3.12|间接依赖|maven|
|org.apache.shiro:shiro-core|1.12.0|间接依赖|maven|
|org.jeecgframework.nacos:nacos-istio|2.2.3|直接依赖|maven|
|com.yahoo.datasketches:sketches-core|0.9.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|2.7.10|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|com.caucho:hessian|4.0.63|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.10|间接依赖|maven|
|org.springframework:spring-aop|5.3.26|间接依赖|maven|
|io.undertow:undertow-websockets-jsr|2.2.23.Final|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|间接依赖|maven|
|org.unbescape:unbescape|1.1.6.RELEASE|间接依赖|maven|
|org.jeecgframework.nacos:nacos-encryption-plugin|2.2.3|间接依赖|maven|
|org.springframework.security:spring-security-web|5.7.7|间接依赖|maven|
|com.github.jai-imageio:jai-imageio-core|1.3.1|间接依赖|maven|
|io.grpc:grpc-netty-shaded|1.50.2|间接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.26|间接依赖|maven|
|com.alibaba.spring:spring-context-support|1.0.11|间接依赖|maven|
|com.github.xiaoymin:knife4j-spring-boot-starter|3.0.3|直接依赖|maven|
|org.apache.shiro:shiro-crypto-core|1.12.0|间接依赖|maven|
|com.github.xiaoymin:knife4j-annotations|3.0.3|间接依赖|maven|
|com.microsoft.sqlserver:sqljdbc4|4.0|直接依赖|maven|
|org.attoparser:attoparser|2.0.5.RELEASE|间接依赖|maven|
|org.apache.commons:commons-compress|1.19|间接依赖|maven|
|io.swagger.core.v3:swagger-models|2.1.2|间接依赖|maven|
|org.apache.derby:derby|10.14.2.0|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.68|间接依赖|maven|
|org.springframework.retry:spring-retry|1.3.4|间接依赖|maven|
|de.codecentric:spring-boot-admin-server-ui|2.3.1|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator|2.7.10|间接依赖|maven|
|org.eclipse.jdt:ecj|3.18.0|间接依赖|maven|
|com.baomidou:mybatis-plus-extension|3.5.3|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|2.7.10|直接依赖|maven|
|com.sun.xml.bind:jaxb-impl|2.3.0|间接依赖|maven|
|com.github.xiaoymin:knife4j-spring-ui|3.0.3|间接依赖|maven|
|org.springframework:spring-jcl|5.3.24|间接依赖|maven|
|com.github.xiaoymin:knife4j-spring-boot-autoconfigure|3.0.3|间接依赖|maven|
|com.alibaba.nacos:nacos-api|1.4.2|间接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|org.springframework.integration:spring-integration-jmx|5.5.17|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-shadow-distsql-statement|5.0.0|间接依赖|maven|
|com.alibaba:druid-spring-boot-starter|1.2.15|直接依赖|maven|
|org.apache.shardingsphere:shardingsphere-encrypt-spring-boot-starter|5.0.0|间接依赖|maven|
|org.apache.calcite:calcite-linq4j|1.27.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-redis|2.7.10|间接依赖|maven|
|io.grpc:grpc-protobuf|1.50.2|间接依赖|maven|
|io.grpc:grpc-core|1.50.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.7.10|间接依赖|maven|
|com.stoyanr:evictor|1.0.0|间接依赖|maven|
|org.springframework:spring-expression|5.3.26|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-standalone-mode-core|5.0.0|间接依赖|maven|
|org.hibernate:hibernate-core|5.6.7.Final|直接依赖|maven|
|org.apache.shiro:shiro-cache|1.12.0|间接依赖|maven|
|commons-collections:commons-collections|3.2.1|间接依赖|maven|
|com.alibaba.csp:sentinel-web-servlet|1.8.3|直接依赖|maven|
|org.apache.curator:curator-client|5.1.0|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-shadow-spring-boot-starter|5.0.0|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-dysmsapi|2.1.0|直接依赖|maven|
|org.freemarker:freemarker|2.3.32|间接依赖|maven|
|io.envoyproxy.controlplane:api|0.1.27|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-reflect|1.6.21|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.3|直接依赖|maven|
|org.jeecgframework.nacos:nacos-custom-environment-plugin|2.2.3|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-jasper|9.0.69|直接依赖|maven|
|org.owasp.encoder:encoder|1.2.3|间接依赖|maven|
|com.baomidou:dynamic-datasource-spring-boot-starter|3.2.0|直接依赖|maven|
|org.wildfly.common:wildfly-common|1.5.4.Final|间接依赖|maven|
|org.apache.poi:ooxml-schemas|1.4|间接依赖|maven|
|org.apache.commons:commons-dbcp2|2.9.0|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-cluster-mode-core|5.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-quartz|2.7.10|直接依赖|maven|
|org.jboss:jandex|2.4.2.Final|间接依赖|maven|
|com.google.uzaygezen:uzaygezen-core|0.2|间接依赖|maven|
|xerces:xercesImpl|2.12.2|直接依赖|maven|
|org.jeecgframework.boot:jeecg-boot-starter-cloud|3.5.3|直接依赖|maven|
|org.jboss.marshalling:jboss-marshalling-river|2.0.11.Final|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.11|间接依赖|maven|
|org.apache.tomcat:tomcat-annotations-api|9.0.69|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-loadbalancer|3.1.3|间接依赖|maven|
|org.apache.commons:commons-math3|3.6.1|间接依赖|maven|
|net.sf.ezmorph:ezmorph|1.0.6|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.4|间接依赖|maven|
|io.netty:netty-codec-stomp|4.1.90.Final|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.4|间接依赖|maven|
|io.springfox:springfox-spring-web|3.0.0|间接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.68|间接依赖|maven|
|io.perfmark:perfmark-api|0.25.0|间接依赖|maven|
|io.netty:netty-common|4.1.90.Final|间接依赖|maven|
|org.jeecgframework.cloud:sentinel-dashboard|1.8.3|直接依赖|maven|
|com.alibaba.csp:sentinel-cluster-server-default|1.8.3|间接依赖|maven|
|org.thymeleaf:thymeleaf|3.0.15.RELEASE|间接依赖|maven|
|commons-lang:commons-lang|2.6|直接依赖|maven|
|org.springframework.cloud:spring-cloud-function-core|3.2.5|间接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|间接依赖|maven|
|com.google.zxing:core|3.3.1|间接依赖|maven|
|org.jdom:jdom|1.1|间接依赖|maven|
|org.jeecgframework.nacos:nacos-auth-plugin|2.2.3|间接依赖|maven|
|org.apache.curator:curator-framework|5.1.0|间接依赖|maven|
|net.jodah:typetools|0.6.2|间接依赖|maven|
|cn.hutool:hutool-core|5.3.8|间接依赖|maven|
|org.springframework:spring-web|5.3.26|间接依赖|maven|
|org.slf4j:jcl-over-slf4j|1.7.36|间接依赖|maven|
|org.springframework.cloud:spring-cloud-loadbalancer|3.1.3|间接依赖|maven|
|io.swagger:swagger-core|1.5.22|间接依赖|maven|
|org.ow2.asm:asm|6.0|间接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.90.Final|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.15|间接依赖|maven|
|io.prometheus:simpleclient_common|0.15.0|间接依赖|maven|
|org.ini4j:ini4j|0.5.4|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.21|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-infra-binder|5.0.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.6.21|间接依赖|maven|
|org.springframework:spring-websocket|5.3.26|间接依赖|maven|
|org.springframework:spring-context|5.3.24|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-infra-common|5.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-undertow|2.7.10|直接依赖|maven|
|io.springfox:springfox-bean-validators|3.0.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.0|间接依赖|maven|
|org.mybatis:mybatis-spring|2.0.7|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.6.14|间接依赖|maven|
|org.apache.poi:poi|4.1.2|间接依赖|maven|
|xml-apis:xml-apis|1.4.01|间接依赖|maven|
|org.jeecgframework.nacos:nacos-core|2.2.3|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-ram|3.1.0|间接依赖|maven|
|io.netty:netty-codec-haproxy|4.1.90.Final|间接依赖|maven|
|org.slf4j:log4j-over-slf4j|1.7.36|间接依赖|maven|
|com.squareup.okhttp3:okhttp|4.4.1|直接依赖|maven|
|org.antlr:antlr4|4.8|间接依赖|maven|
|org.codehaus.groovy:groovy|2.4.19|间接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|间接依赖|maven|
|commons-io:commons-io|2.7|间接依赖|maven|
|io.springfox:springfox-swagger-common|3.0.0|间接依赖|maven|
|io.netty:netty-buffer|4.1.90.Final|间接依赖|maven|
|com.sun.xml.bind:jaxb-core|2.3.0|间接依赖|maven|
|io.swagger:swagger-models|1.5.22|间接依赖|maven|
|commons-pool:commons-pool|1.6|间接依赖|maven|
|org.crazycake:shiro-redis|3.1.0|直接依赖|maven|
|org.javassist:javassist|3.25.0-GA|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-sharding-distsql-parser|5.0.0|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.6.21|间接依赖|maven|
|org.springframework.cloud:spring-cloud-gateway-server|3.1.3|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|com.github.xiaoymin:knife4j-core|3.0.3|间接依赖|maven|
|org.apache.shiro:shiro-crypto-hash|1.12.0|间接依赖|maven|
|com.oracle:ojdbc6|11.2.0.3|直接依赖|maven|
|io.github.classgraph:classgraph|4.8.83|间接依赖|maven|
|org.mybatis.spring.boot:mybatis-spring-boot-autoconfigure|2.1.3|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-db-discovery-distsql-statement|5.0.0|间接依赖|maven|
|com.mysql:mysql-connector-j|8.0.31|间接依赖|maven|
|org.apache.shiro:shiro-spring|1.12.0|间接依赖|maven|
|com.alibaba.csp:sentinel-core|1.8.3|直接依赖|maven|
|org.aspectj:aspectjweaver|1.9.7|间接依赖|maven|
|io.prometheus:simpleclient_tracer_otel_agent|0.12.0|间接依赖|maven|
|org.antlr:antlr-runtime|3.5.2|间接依赖|maven|
|io.springfox:springfox-spring-webflux|3.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-amqp|2.7.10|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-thymeleaf|2.7.10|间接依赖|maven|
|org.redisson:redisson|3.16.1|间接依赖|maven|
|org.jeecgframework.nacos:nacos-api|2.2.3|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-websocket|2.7.10|直接依赖|maven|
|org.apache.shardingsphere:shardingsphere-jdbc-transaction-spring|5.0.0|间接依赖|maven|
|io.projectreactor:reactor-core|3.4.28|间接依赖|maven|
|io.micrometer:micrometer-registry-influx|1.8.12|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-infra-context|5.0.0|间接依赖|maven|
|org.springframework.data:spring-data-commons|2.7.10|间接依赖|maven|
|io.netty:netty-resolver|4.1.90.Final|间接依赖|maven|
|commons-cli:commons-cli|1.4|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-security|2.6.14|直接依赖|maven|
|org.jeecgframework.nacos:nacos-contrl-plugin|2.2.3|间接依赖|maven|
|io.prometheus:simpleclient|0.15.0|间接依赖|maven|
|io.netty:netty-codec-mqtt|4.1.90.Final|间接依赖|maven|
|com.xkcoding.justauth:justauth-spring-boot-starter|1.3.4|直接依赖|maven|
|org.codehaus.janino:commons-compiler|3.1.9|间接依赖|maven|
|org.springframework:spring-web|5.3.24|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-sql-parser-sqlserver|5.0.0|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-infra-rewrite|5.0.0|间接依赖|maven|
|org.springframework:spring-tx|5.3.24|间接依赖|maven|
|io.swagger:swagger-annotations|1.5.22|间接依赖|maven|
|com.alibaba.csp:sentinel-cluster-common-default|1.8.3|间接依赖|maven|
|io.netty:netty-codec-redis|4.1.90.Final|间接依赖|maven|
|org.apache.poi:poi-ooxml-schemas|4.1.2|间接依赖|maven|
|org.apache.shardingsphere.elasticjob:elasticjob-lite-core|3.0.1|间接依赖|maven|
|com.esri.geometry:esri-geometry-api|2.2.0|间接依赖|maven|
|com.baomidou:mybatis-plus-boot-starter|3.5.3|直接依赖|maven|
|org.apache.shardingsphere:shardingsphere-sql-parser-postgresql|5.0.0|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.90.Final|间接依赖|maven|
|com.baomidou:mybatis-plus|3.5.3|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.3.Final|间接依赖|maven|
|org.apache.shardingsphere.elasticjob:elasticjob-tracing-api|3.0.1|间接依赖|maven|
|org.springframework.integration:spring-integration-core|5.5.17|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.73|间接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|com.github.virtuald:curvesapi|1.06|间接依赖|maven|
|org.springframework.boot:spring-boot-test|2.6.14|间接依赖|maven|
|io.github.openfeign.form:feign-form-spring|3.8.0|间接依赖|maven|
|com.alipay.sofa:hessian|3.3.6|间接依赖|maven|
|org.apache.shardingsphere.elasticjob:elasticjob-registry-center|3.0.1|间接依赖|maven|
|org.springframework.data:spring-data-redis|2.7.10|间接依赖|maven|
|org.springframework.data:spring-data-keyvalue|2.7.10|间接依赖|maven|
|me.zhyd.oauth:JustAuth|1.15.7|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.21.11|间接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|org.jboss.xnio:xnio-nio|3.8.7.Final|间接依赖|maven|
|com.alibaba.cloud:spring-cloud-starter-alibaba-nacos-config|2021.0.1.0|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|9.0.69|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.90.Final|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-db-discovery-distsql-handler|5.0.0|间接依赖|maven|
|io.netty:netty-codec-xml|4.1.90.Final|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.90.Final|间接依赖|maven|
|io.netty:netty-transport-udt|4.1.90.Final|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.5|间接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|2.7.1|间接依赖|maven|
|org.springframework:spring-oxm|5.3.26|间接依赖|maven|
|com.alibaba:druid|1.2.15|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.4|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.4.2|间接依赖|maven|
|org.springframework:spring-core|5.3.24|间接依赖|maven|
|org.checkerframework:checker-qual|3.5.0|间接依赖|maven|
|org.jeecgframework.nacos:nacos-naming|2.2.3|直接依赖|maven|
|commons-logging:commons-logging|1.1.1|间接依赖|maven|
|org.apache.shardingsphere.elasticjob:elasticjob-api|3.0.1|间接依赖|maven|
|io.micrometer:micrometer-registry-prometheus|1.8.12|间接依赖|maven|
|com.carrotsearch.thirdparty:simple-xml-safe|2.7.1|间接依赖|maven|
|cglib:cglib|3.1|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-cluster-mode-repository-api|5.0.0|间接依赖|maven|
|commons-io:commons-io|2.6|直接依赖|maven|
|com.alipay.sdk:alipay-sdk-java|3.1.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|2.6.14|间接依赖|maven|
|org.springframework:spring-context-support|5.3.26|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-shadow-core|5.0.0|间接依赖|maven|
|org.jeecgframework.nacos:nacos-client|2.2.3|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-validation|2.7.10|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.14.0|间接依赖|maven|
|io.undertow:undertow-servlet|2.2.23.Final|间接依赖|maven|
|org.jeecgframework.boot:codegenerate|1.4.4|直接依赖|maven|
|org.jacoco:org.jacoco.agent|0.8.5|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.13.5|间接依赖|maven|
|io.netty:netty-resolver-dns|4.1.90.Final|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-sql-parser-spi|5.0.0|间接依赖|maven|
|com.google.zxing:javase|3.3.1|间接依赖|maven|
|com.alibaba.csp:sentinel-datasource-nacos|1.8.3|直接依赖|maven|
|io.opentracing:opentracing-util|0.33.0|间接依赖|maven|
|org.springframework.cloud:spring-cloud-stream-binder-rabbit-core|3.2.4|间接依赖|maven|
|org.jeecgframework.boot:jeecg-boot-starter-shardingsphere|3.5.3|直接依赖|maven|
|org.jeecgframework.boot:jeecg-boot-starter-seata|3.5.3|直接依赖|maven|
|org.thymeleaf:thymeleaf-spring5|3.0.15.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.6.14|间接依赖|maven|
|org.springframework.security:spring-security-web|5.6.9|间接依赖|maven|
|org.jeecgframework.boot:jeecg-boot-common|3.5.3|直接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|间接依赖|maven|
|com.baomidou:mybatis-plus-core|3.5.3|间接依赖|maven|
|stax:stax-api|1.0.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.4|间接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|org.jeecgframework:minidao-spring-boot-starter|1.9.2|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-http|1.0.30|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.6.14|间接依赖|maven|
|org.springframework.cloud:spring-cloud-function-context|3.2.5|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-readwrite-splitting-distsql-handler|5.0.0|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-sharding-api|5.0.0|间接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.3|直接依赖|maven|
|org.apache.shardingsphere:shardingsphere-readwrite-splitting-spring-boot-starter|5.0.0|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-jdbc-core|5.0.0|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.6.14|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.10.0|间接依赖|maven|
|log4j:log4j|1.2.17|间接依赖|maven|
|org.abego.treelayout:org.abego.treelayout.core|1.0.3|间接依赖|maven|
|org.apache.shardingsphere.elasticjob:elasticjob-simple-executor|3.0.1|间接依赖|maven|
|com.alibaba.csp:sentinel-transport-simple-http|1.8.3|直接依赖|maven|
|org.quartz-scheduler:quartz|2.3.2|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-sql-parser-mysql|5.0.0|间接依赖|maven|
|org.jeecgframework:autopoi|1.4.5|间接依赖|maven|
|org.jeecgframework.nacos:nacos-consistency|2.2.3|间接依赖|maven|
|org.springframework.security:spring-security-crypto|5.6.9|间接依赖|maven|
|io.netty:netty-transport|4.1.90.Final|间接依赖|maven|
|com.sun.activation:jakarta.activation|1.2.2|间接依赖|maven|
|com.alibaba.csp:sentinel-spring-webflux-adapter|1.8.3|间接依赖|maven|
|com.ibm.icu:icu4j|61.1|间接依赖|maven|
|org.apache.shardingsphere.elasticjob:elasticjob-error-handler-spi|3.0.1|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-sharding-distsql-handler|5.0.0|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|间接依赖|maven|
|io.prometheus:simpleclient_common|0.12.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.13.5|间接依赖|maven|
|io.netty:netty-codec-http|4.1.90.Final|间接依赖|maven|
|com.alibaba.cloud:spring-cloud-circuitbreaker-sentinel|2021.0.1.0|间接依赖|maven|
|org.jeecgframework.nacos:nacos-config|2.2.3|直接依赖|maven|
|com.alibaba.csp:sentinel-datasource-extension|1.8.3|间接依赖|maven|
|org.springframework.boot:spring-boot|2.6.14|间接依赖|maven|
|org.jeecgframework.boot:jeecg-module-demo|3.5.3|直接依赖|maven|
|org.apache.commons:commons-collections4|4.4|间接依赖|maven|
|com.alibaba.nacos:nacos-client|1.4.2|间接依赖|maven|
|io.lettuce:lettuce-core|6.1.10.RELEASE|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.0|间接依赖|maven|
|org.ow2.asm:asm-tree|5.0.3|间接依赖|maven|
|org.projectlombok:lombok|1.18.26|直接依赖|maven|
|io.github.openfeign:feign-slf4j|11.8|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-encrypt-core|5.0.0|间接依赖|maven|
|io.projectreactor.netty:reactor-netty-core|1.0.30|间接依赖|maven|
|com.squareup.okio:okio|2.4.3|间接依赖|maven|
|org.glassfish.jaxb:txw2|2.3.8|间接依赖|maven|
|org.jeecgframework.boot:jeecg-boot-starter-job|3.5.3|直接依赖|maven|
|org.jeecgframework.boot:jeecg-system-cloud-api|3.5.3|直接依赖|maven|
|org.apache.shardingsphere:shardingsphere-sql-parser-engine|5.0.0|间接依赖|maven|
|org.antlr:antlr4-runtime|4.7|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.9|间接依赖|maven|
|com.alibaba.csp:sentinel-transport-common|1.8.3|间接依赖|maven|
|org.mybatis:mybatis|3.5.10|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-transaction-api|5.0.0|间接依赖|maven|
|org.jeecgframework.nacos:nacos-cmdb|2.2.3|间接依赖|maven|
|com.alibaba:fastjson|1.2.83|直接依赖|maven|
|org.springframework:spring-jdbc|5.3.26|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator|2.6.14|间接依赖|maven|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|org.jboss.threads:jboss-threads|3.1.0.Final|间接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.90.Final|间接依赖|maven|
|org.springframework.security:spring-security-core|5.6.9|间接依赖|maven|
|org.apache.shardingsphere.elasticjob:elasticjob-script-executor|3.0.1|间接依赖|maven|
|org.springframework:spring-test|5.3.24|间接依赖|maven|
|org.apache.commons:commons-exec|1.3|间接依赖|maven|
|org.springframework:spring-aop|5.3.24|间接依赖|maven|
|org.springframework:spring-webmvc|5.3.24|间接依赖|maven|
|io.springfox:springfox-swagger2|3.0.0|间接依赖|maven|
|com.auth0:java-jwt|3.11.0|直接依赖|maven|
|org.springframework.cloud:spring-cloud-stream|3.2.4|间接依赖|maven|
|io.springfox:springfox-core|3.0.0|间接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.6|直接依赖|maven|
|com.google.guava:guava|30.1-jre|间接依赖|maven|
|com.google.guava:guava|29.0-jre|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-readwrite-splitting-distsql-parser|5.0.0|间接依赖|maven|
|io.grpc:grpc-api|1.50.2|间接依赖|maven|
|org.jeecgframework.boot:jeecg-system-biz|3.5.3|直接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.16|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.13.5|间接依赖|maven|
|org.wildfly.client:wildfly-client-config|1.0.1.Final|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-transaction-core|5.0.0|间接依赖|maven|
|com.beust:jcommander|1.72|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.6.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|2.7.10|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.13.5|间接依赖|maven|
|io.grpc:grpc-stub|1.50.2|间接依赖|maven|
|com.sun.istack:istack-commons-runtime|3.0.12|间接依赖|maven|
|org.yaml:snakeyaml|1.30|间接依赖|maven|
|org.mybatis:mybatis|3.5.5|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-sharding-core|5.0.0|间接依赖|maven|
|com.github.librepdf:openpdf|1.3.27|间接依赖|maven|
|org.jeecgframework.boot:jeecg-system-local-api|3.5.3|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.16|间接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.90.Final|间接依赖|maven|
|org.codehaus.janino:janino|3.1.9|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-infra-optimize|5.0.0|间接依赖|maven|
|org.jeecgframework:autopoi-web|1.4.5|直接依赖|maven|
|org.apache.shiro:shiro-lang|1.12.0|间接依赖|maven|
|io.netty:netty-handler-ssl-ocsp|4.1.90.Final|间接依赖|maven|
|io.netty:netty-transport-sctp|4.1.90.Final|间接依赖|maven|
|commons-fileupload:commons-fileupload|1.4|直接依赖|maven|
|org.jboss.xnio:xnio-api|3.8.7.Final|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.90.Final|间接依赖|maven|
|org.jodd:jodd-core|5.1.6|间接依赖|maven|
|io.undertow:undertow-core|2.2.23.Final|间接依赖|maven|
|org.springframework:spring-beans|5.3.24|间接依赖|maven|
|io.grpc:grpc-context|1.50.2|间接依赖|maven|
|org.apache.shiro:shiro-event|1.12.0|间接依赖|maven|
|javax.servlet:javax.servlet-api|4.0.1|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-actuator|2.6.14|间接依赖|maven|
|redis.clients:jedis|3.8.0|间接依赖|maven|
|com.alibaba.csp:sentinel-reactor-adapter|1.8.3|间接依赖|maven|
|org.apache.shardingsphere.elasticjob:elasticjob-infra-common|3.0.1|间接依赖|maven|
|io.netty:netty-codec-memcache|4.1.90.Final|间接依赖|maven|
|io.prometheus:simpleclient_tracer_otel|0.15.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-tomcat|2.7.10|间接依赖|maven|
|com.sun.mail:jakarta.mail|1.6.7|间接依赖|maven|
|org.rocksdb:rocksdbjni|7.7.3|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-stream-rabbit|3.2.4|间接依赖|maven|
|org.apache.calcite.avatica:avatica-core|1.18.0|间接依赖|maven|
|org.springframework.cloud:spring-cloud-context|3.1.3|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.13.5|间接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.15|间接依赖|maven|
|org.jctools:jctools-core|2.1.1|间接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.50.2|间接依赖|maven|
|org.springframework.ldap:spring-ldap-core|2.3.8.RELEASE|间接依赖|maven|
|com.alibaba.csp:sentinel-annotation-aspectj|1.8.3|间接依赖|maven|
|org.mybatis:mybatis-spring|2.0.5|间接依赖|maven|
|com.alibaba.csp:sentinel-spring-cloud-gateway-adapter|1.8.3|间接依赖|maven|
|io.prometheus:simpleclient_tracer_common|0.15.0|间接依赖|maven|
|org.springframework.amqp:spring-rabbit|2.4.11|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-readwrite-splitting-core|5.0.0|间接依赖|maven|
|org.jeecgframework.nacos:nacos-trace-plugin|2.2.3|间接依赖|maven|
|com.alipay.sofa:rpc-grpc-impl|1.3.12|间接依赖|maven|
|javax.cache:cache-api|1.1.1|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-infra-merge|5.0.0|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-sharding-distsql-statement|5.0.0|间接依赖|maven|
|io.minio:minio|8.0.3|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.13.5|间接依赖|maven|
|org.springframework.integration:spring-integration-amqp|5.5.17|间接依赖|maven|
|com.google.guava:guava|31.1-android|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-actuator|2.7.10|直接依赖|maven|
|com.puppycrawl.tools:checkstyle|8.3|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-encrypt-distsql-parser|5.0.0|间接依赖|maven|
|net.bytebuddy:byte-buddy|1.12.23|间接依赖|maven|
|org.springframework.cloud:spring-cloud-bus|3.1.2|间接依赖|maven|
|com.alibaba.cloud:spring-cloud-starter-alibaba-sentinel|2021.0.1.0|直接依赖|maven|
|org.apache.shardingsphere:shardingsphere-authority-api|5.0.0|间接依赖|maven|
|org.apache.yetus:audience-annotations|0.5.0|间接依赖|maven|
|io.netty:netty-transport-rxtx|4.1.90.Final|间接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|org.hibernate.common:hibernate-commons-annotations|5.1.2.Final|间接依赖|maven|
|org.springframework:spring-tx|5.3.26|间接依赖|maven|
|mysql:mysql-connector-java|8.0.27|直接依赖|maven|
|javax.persistence:javax.persistence-api|2.2|间接依赖|maven|
|org.jboss.marshalling:jboss-marshalling|2.0.11.Final|间接依赖|maven|
|org.apache.shardingsphere.elasticjob:elasticjob-error-handler-general|3.0.1|间接依赖|maven|
|io.springfox:springfox-spring-webmvc|3.0.0|间接依赖|maven|
|org.springframework:spring-messaging|5.3.26|间接依赖|maven|
|com.alibaba.csp:sentinel-spring-webmvc-adapter|1.8.3|间接依赖|maven|
|io.seata:seata-all|1.4.2|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-encrypt-distsql-handler|5.0.0|间接依赖|maven|
|com.mchange:mchange-commons-java|0.2.15|间接依赖|maven|
|io.github.openfeign.form:feign-form|3.8.0|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-distsql-parser-statement|5.0.0|间接依赖|maven|
|org.thymeleaf.extras:thymeleaf-extras-java8time|3.0.4.RELEASE|间接依赖|maven|
|org.springframework.security:spring-security-core|5.7.7|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-spi|5.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot|2.7.10|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-gateway|3.1.3|直接依赖|maven|
|io.netty:netty-handler|4.1.90.Final|间接依赖|maven|
|org.jeecgframework.nacos:nacos-sys|2.2.3|间接依赖|maven|
|org.postgresql:postgresql|42.2.25|直接依赖|maven|
|org.jboss.spec.javax.transaction:jboss-transaction-api_1.2_spec|1.1.1.Final|间接依赖|maven|
|org.apache.shardingsphere.elasticjob:elasticjob-http-executor|3.0.1|间接依赖|maven|
|org.springframework.plugin:spring-plugin-core|2.0.0.RELEASE|间接依赖|maven|
|io.prometheus:simpleclient_tracer_otel|0.12.0|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.11|间接依赖|maven|
|org.springframework.cloud:spring-cloud-commons|3.1.3|间接依赖|maven|
|io.netty:netty-all|4.1.90.Final|间接依赖|maven|
|io.springfox:springfox-schema|3.0.0|间接依赖|maven|
|com.rabbitmq:amqp-client|5.14.2|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-distsql-parser-engine|5.0.0|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-kotlin|2.13.5|直接依赖|maven|
|jakarta.websocket:jakarta.websocket-api|1.1.2|间接依赖|maven|
|com.xuxueli:xxl-job-core|2.2.0|直接依赖|maven|
|org.apache.shardingsphere:shardingsphere-shadow-distsql-parser|5.0.0|间接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.5|间接依赖|maven|
|org.jeecgframework.nacos:nacos-prometheus|2.2.3|间接依赖|maven|
|com.googlecode.aviator:aviator|5.2.6|间接依赖|maven|
|org.apache.calcite:calcite-core|1.27.0|间接依赖|maven|
|org.apache.poi:poi-scratchpad|4.1.2|间接依赖|maven|
|org.springframework:spring-context|5.3.26|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-db-discovery-api|5.0.0|间接依赖|maven|
|de.codecentric:spring-boot-admin-starter-server|2.3.1|直接依赖|maven|
|org.apache.shardingsphere:shardingsphere-readwrite-splitting-distsql-statement|5.0.0|间接依赖|maven|
|com.rabbitmq:http-client|2.1.0.RELEASE|间接依赖|maven|
|com.alibaba.cloud:spring-cloud-alibaba-sentinel-datasource|2021.0.1.0|间接依赖|maven|
|org.jeecgframework.nacos:nacos-common|2.2.3|间接依赖|maven|
|io.netty:netty-handler-proxy|4.1.90.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|2.7.10|直接依赖|maven|
|org.jeecgframework.boot:jeecg-boot-starter-lock|3.5.3|直接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-core|9.0.73|间接依赖|maven|
|io.springfox:springfox-data-rest|3.0.0|间接依赖|maven|
|net.sf.saxon:Saxon-HE|9.8.0-4|间接依赖|maven|
|com.zaxxer:SparseBitSet|1.2|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-infra-executor|5.0.0|间接依赖|maven|
|org.mapstruct:mapstruct|1.3.1.Final|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-openfeign|3.1.3|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.6.14|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-freemarker|2.7.10|直接依赖|maven|
|io.dropwizard.metrics:metrics-core|4.2.13|间接依赖|maven|
|ognl:ognl|3.2.21|间接依赖|maven|
|org.apache.shiro:shiro-web|1.12.0|间接依赖|maven|
|org.apache.shiro:shiro-spring-boot-starter|1.12.0|直接依赖|maven|
|org.apache.shardingsphere:shardingsphere-shadow-distsql-handler|5.0.0|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter-bus-amqp|3.1.2|间接依赖|maven|
|org.aspectj:aspectjrt|1.9.7|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-standalone-mode-repository-file|5.0.0|间接依赖|maven|
|org.springframework.cloud:spring-cloud-starter|3.1.3|间接依赖|maven|
|io.springfox:springfox-oas|3.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator-autoconfigure|2.7.10|间接依赖|maven|
|io.micrometer:micrometer-registry-elastic|1.8.12|间接依赖|maven|
|com.alibaba.csp:sentinel-cluster-client-default|1.8.3|间接依赖|maven|
|com.baomidou:mybatis-plus-annotation|3.5.3|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.5|直接依赖|maven|
|io.netty:netty-codec|4.1.90.Final|间接依赖|maven|
|org.springframework.security:spring-security-config|5.7.7|间接依赖|maven|
|org.apache.shiro:shiro-config-ogdl|1.12.0|间接依赖|maven|
|com.xkcoding.http:simple-http|1.0.2|间接依赖|maven|
|io.prometheus:simpleclient_tracer_common|0.12.0|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|6.2.5.Final|间接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.90.Final|间接依赖|maven|
|org.springframework.security:spring-security-rsa|1.0.10.RELEASE|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-sql-parser-oracle|5.0.0|间接依赖|maven|
|com.alibaba.csp:sentinel-parameter-flow-control|1.8.3|直接依赖|maven|
|net.hydromatic:aggdesigner-algorithm|6.0|间接依赖|maven|
|net.java.dev.jna:jna|5.5.0|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.11.4|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-security|2.7.10|直接依赖|maven|
|org.parboiled:parboiled-core|1.1.7|间接依赖|maven|
|io.micrometer:micrometer-core|1.8.12|间接依赖|maven|
|org.apache.shiro:shiro-config-core|1.12.0|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.14|间接依赖|maven|
|org.checkerframework:checker-qual|3.12.0|间接依赖|maven|
|com.aliyun.oss:aliyun-sdk-oss|3.11.2|直接依赖|maven|
|org.springframework.cloud:spring-cloud-openfeign-core|3.1.3|间接依赖|maven|
|net.sf.json-lib:json-lib|2.4|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-sql-parser-sql92|5.0.0|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-sharding-spring-boot-starter|5.0.0|间接依赖|maven|
|com.googlecode.concurrentlinkedhashmap:concurrentlinkedhashmap-lru|1.4.2|间接依赖|maven|
|io.netty:netty-codec-smtp|4.1.90.Final|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-db-discovery-core|5.0.0|间接依赖|maven|
|org.jodd:jodd-bean|5.1.6|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-standalone-mode-repository-api|5.0.0|间接依赖|maven|
|org.ow2.asm:asm-util|5.0.3|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-readwrite-splitting-api|5.0.0|间接依赖|maven|
|org.springframework:spring-webflux|5.3.26|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.10|间接依赖|maven|
|org.ow2.asm:asm-analysis|5.0.3|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-encrypt-distsql-statement|5.0.0|间接依赖|maven|
|org.apache.shardingsphere.elasticjob:elasticjob-executor-kernel|3.0.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.6.14|间接依赖|maven|
|org.apache.shiro:shiro-crypto-cipher|1.12.0|间接依赖|maven|
|org.codehaus.jackson:jackson-core-asl|1.9.13|间接依赖|maven|
|org.javatuples:javatuples|1.2|间接依赖|maven|
|io.reactivex.rxjava3:rxjava|3.0.12|间接依赖|maven|
|org.jeecgframework:jeewx-api|1.5.2|直接依赖|maven|
|com.github.jsqlparser:jsqlparser|4.4|间接依赖|maven|
|com.alibaba.cloud:spring-cloud-alibaba-sentinel-gateway|2021.0.1.0|直接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|io.opentracing:opentracing-noop|0.33.0|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-authority-core|5.0.0|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.90.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-cache|2.7.10|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-infra-route|5.0.0|间接依赖|maven|
|org.springframework:spring-expression|5.3.24|间接依赖|maven|
|org.apache.shardingsphere:shardingsphere-jdbc-spring-boot-starter-infra|5.0.0|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-kms|2.11.0|间接依赖|maven|
|de.codecentric:spring-boot-admin-server-cloud|2.3.1|间接依赖|maven|
|io.springfox:springfox-boot-starter|3.0.0|间接依赖|maven|
|org.codehaus.groovy:groovy|3.0.16|间接依赖|maven|
|org.springframework:spring-jdbc|5.3.24|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.90.Final|间接依赖|maven|
|org.jeecgframework:minidao-pe|1.9.2|间接依赖|maven|
|org.yaml:snakeyaml|1.29|间接依赖|maven|
|org.apache.xmlbeans:xmlbeans|3.1.0|间接依赖|maven|
|org.apache.shardingsphere.elasticjob:elasticjob-tracing-rdb|3.0.1|间接依赖|maven|
|org.jdom:jdom2|2.0.6.1|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-websocket|9.0.73|间接依赖|maven|
|io.seata:seata-spring-boot-starter|1.4.2|间接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|2.3.8|间接依赖|maven|
|org.springframework:spring-beans|5.3.26|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.9|间接依赖|maven|
|org.apache.curator:curator-recipes|5.1.0|间接依赖|maven|
|org.jeecgframework.nacos:nacos-console|2.2.3|直接依赖|maven|
|org.springframework.security:spring-security-crypto|5.7.7|间接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.9.3|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.13.4|间接依赖|maven|
|com.typesafe:config|1.2.1|间接依赖|maven|
|org.jeecgframework.nacos:nacos-auth|2.2.3|间接依赖|maven|
|io.prometheus:simpleclient|0.12.0|间接依赖|maven|
|com.alibaba.csp:sentinel-api-gateway-adapter-common|1.8.3|直接依赖|maven|
|io.micrometer:micrometer-registry-prometheus|1.9.9|直接依赖|maven|
|org.apache.shardingsphere:shardingsphere-encrypt-api|5.0.0|间接依赖|maven|
|org.antlr:ST4|4.3|间接依赖|maven|
|org.checkerframework:checker-qual|3.19.0|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)