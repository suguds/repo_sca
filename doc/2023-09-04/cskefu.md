# cskefu/cskefu安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698403501461864448.svg)](https://www.murphysec.com/console/report/1698403501021462528/1698403501461864448)

仓库描述：🌲 春松客服，开源客服系统

仓库地址：[https://github.com/cskefu/cskefu](https://github.com/cskefu/cskefu)

| star：2461 | watch：89 | fork：841 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-02 11:07:35 | 许可证：NOASSERTION |
| 最近检测时间：2023-09-04 02:33:20 | 组件总数：235 | 漏洞总数：104 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache Struts 远程代码执行漏洞|输入验证不恰当|[MPS-2014-2167](https://www.oscs1024.com/hd/MPS-2014-2167)|CVE-2014-0114|高危|
|Oracle MySQL Connectors组件SQL注入漏洞|SQL注入|[MPS-2015-2026](https://www.oscs1024.com/hd/MPS-2015-2026)|CVE-2015-2575|中危|
|Oracle MySQL Connectors 访问限制绕过漏洞|访问控制不当|[MPS-2017-4684](https://www.oscs1024.com/hd/MPS-2017-4684)|CVE-2017-3523|高危|
|Oracle MySQL Connectors 安全漏洞|访问控制不当|[MPS-2017-4744](https://www.oscs1024.com/hd/MPS-2017-4744)|CVE-2017-3586|中危|
|Oracle MySQL Connectors 安全漏洞|访问控制不当|[MPS-2017-4746](https://www.oscs1024.com/hd/MPS-2017-4746)|CVE-2017-3589|低危|
|Apache POI <3.17 拒绝服务漏洞|不可达退出条件的循环（无限循环）|[MPS-2018-1197](https://www.oscs1024.com/hd/MPS-2018-1197)|CVE-2017-12626|高危|
|Oracle MySQL Connectors 访问控制错误漏洞|使用候选路径或通道进行的认证绕过|[MPS-2018-13771](https://www.oscs1024.com/hd/MPS-2018-13771)|CVE-2018-3258|高危|
|Apache Commons Beanutils 存在不可信数据的反序列化漏洞|反序列化|[MPS-2019-10233](https://www.oscs1024.com/hd/MPS-2019-10233)|CVE-2019-10086|高危|
|Apache POI <4.1.1 XXE 漏洞|XXE|[MPS-2019-13682](https://www.oscs1024.com/hd/MPS-2019-13682)|CVE-2019-12415|中危|
|Oracle MySQL Connectors 输入验证错误漏洞|使用不兼容类型访问资源（类型混淆）|[MPS-2019-4430](https://www.oscs1024.com/hd/MPS-2019-4430)|CVE-2019-2692|中危|
|Terracotta Quartz Scheduler <2.3.0 存在XXE漏洞|XXE|[MPS-2019-8669](https://www.oscs1024.com/hd/MPS-2019-8669)|CVE-2019-13990|严重|
|Apache HttpClient URI解析错误漏洞|XSS|[MPS-2020-17341](https://www.oscs1024.com/hd/MPS-2020-17341)|CVE-2020-13956|中危|
|XStream 操作系统命令注入漏洞|OS命令注入|[MPS-2020-17361](https://www.oscs1024.com/hd/MPS-2020-17361)|CVE-2020-26217|高危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|XStream < 1.4.15存在服务端请求伪造漏洞|SSRF|[MPS-2020-17591](https://www.oscs1024.com/hd/MPS-2020-17591)|CVE-2020-26258|高危|
|Xstream < 1.4.15存在删除任意文件漏洞|OS命令注入|[MPS-2020-17661](https://www.oscs1024.com/hd/MPS-2020-17661)|CVE-2020-26259|中危|
|mysql:mysql-connector-java <8.0.27 存在 XXE 漏洞|XXE|[MPS-2020-38350](https://www.oscs1024.com/hd/MPS-2020-38350)|CVE-2021-2471|中危|
|Apache Ant 临时文件不安全问题|将资源暴露给错误范围|[MPS-2020-7418](https://www.oscs1024.com/hd/MPS-2020-7418)|CVE-2020-1945|中危|
|Apache XMLBeans <3.0.0 XXE 漏洞|XML实体扩展|[MPS-2021-0600](https://www.oscs1024.com/hd/MPS-2021-0600)|CVE-2021-23926|严重|
|jsoup <1.14.2 存在拒绝服务漏洞||[MPS-2021-17634](https://www.oscs1024.com/hd/MPS-2021-17634)|CVE-2021-37714|高危|
|XStream  <1.4.18 存在服务器端伪造请求漏洞||[MPS-2021-17812](https://www.oscs1024.com/hd/MPS-2021-17812)|CVE-2021-39152|高危|
|XStream < 1.4.18 存在服务器端请求伪造漏洞||[MPS-2021-17813](https://www.oscs1024.com/hd/MPS-2021-17813)|CVE-2021-39150|高危|
|XStream 存在拒绝服务漏洞||[MPS-2021-17814](https://www.oscs1024.com/hd/MPS-2021-17814)|CVE-2021-39140|中危|
|XStream < 1.4.18存在任意代码执行漏洞||[MPS-2021-17815](https://www.oscs1024.com/hd/MPS-2021-17815)|CVE-2021-39154|高危|
|XStream < 1.4.18存在任意代码执行漏洞||[MPS-2021-17816](https://www.oscs1024.com/hd/MPS-2021-17816)|CVE-2021-39153|高危|
|XStream < 1.4.18存在任意代码执行漏洞||[MPS-2021-17817](https://www.oscs1024.com/hd/MPS-2021-17817)|CVE-2021-39151|高危|
|XStream < 1.4.18存在任意代码执行漏洞||[MPS-2021-17818](https://www.oscs1024.com/hd/MPS-2021-17818)|CVE-2021-39149|高危|
|XStream <1.4.18存在任意代码执行漏洞||[MPS-2021-17819](https://www.oscs1024.com/hd/MPS-2021-17819)|CVE-2021-39148|高危|
|XStream < 1.4.18存在任意代码执行漏洞||[MPS-2021-17820](https://www.oscs1024.com/hd/MPS-2021-17820)|CVE-2021-39147|高危|
|XStream < 1.4.18 任意代码执行漏洞||[MPS-2021-17821](https://www.oscs1024.com/hd/MPS-2021-17821)|CVE-2021-39146|高危|
|XStream < 1.4.18存在任意代码执行漏洞||[MPS-2021-17822](https://www.oscs1024.com/hd/MPS-2021-17822)|CVE-2021-39145|高危|
|XStream <1.4.18存在任意代码执行漏洞||[MPS-2021-17823](https://www.oscs1024.com/hd/MPS-2021-17823)|CVE-2021-39144|高危|
|XStream < 1.4.18存在任意代码执行||[MPS-2021-17824](https://www.oscs1024.com/hd/MPS-2021-17824)|CVE-2021-39141|高危|
|XStream < 1.4.18 反序列化远程代码执行漏洞|反序列化|[MPS-2021-17825](https://www.oscs1024.com/hd/MPS-2021-17825)|CVE-2021-39139|高危|
|Oracle Java SE Oracle GraalVM Enterprise Edition  输入验证错误漏洞|访问控制不当|[MPS-2021-26664](https://www.oscs1024.com/hd/MPS-2021-26664)|CVE-2021-35567|中危|
|Oracle Java SE Oracle GraalVM Enterprise Edition 输入验证错误漏洞|访问控制不当|[MPS-2021-26676](https://www.oscs1024.com/hd/MPS-2021-26676)|CVE-2021-35578|中危|
|Oracle Java SE Oracle GraalVM Enterprise Edition 输入验证错误漏洞|通过时间差异性导致的信息暴露|[MPS-2021-26703](https://www.oscs1024.com/hd/MPS-2021-26703)|CVE-2021-35603|低危|
|XStream <1.4.16存在反序列化漏洞||[MPS-2021-3119](https://www.oscs1024.com/hd/MPS-2021-3119)|CVE-2021-21342|高危|
|XStream 存在反序列化漏洞||[MPS-2021-3120](https://www.oscs1024.com/hd/MPS-2021-3120)|CVE-2021-21348|中危|
|XStream 存在反序列化漏洞||[MPS-2021-3121](https://www.oscs1024.com/hd/MPS-2021-3121)|CVE-2021-21346|高危|
|XStream 存在反序列化漏洞||[MPS-2021-3122](https://www.oscs1024.com/hd/MPS-2021-3122)|CVE-2021-21345|高危|
|XStream <1.4.16存在反序列化漏洞||[MPS-2021-3123](https://www.oscs1024.com/hd/MPS-2021-3123)|CVE-2021-21343|中危|
|XStream 存在拒绝服务漏洞||[MPS-2021-3124](https://www.oscs1024.com/hd/MPS-2021-3124)|CVE-2021-21341|中危|
|XStream 存在反序列化漏洞||[MPS-2021-3125](https://www.oscs1024.com/hd/MPS-2021-3125)|CVE-2021-21344|高危|
|XStream 存在反序列化漏洞||[MPS-2021-3127](https://www.oscs1024.com/hd/MPS-2021-3127)|CVE-2021-21349|中危|
|XStream <1.4.16存在反序列化漏洞||[MPS-2021-3128](https://www.oscs1024.com/hd/MPS-2021-3128)|CVE-2021-21350|高危|
|XStream 存在反序列化漏洞||[MPS-2021-3129](https://www.oscs1024.com/hd/MPS-2021-3129)|CVE-2021-21351|严重|
|XStream 存在反序列化漏洞||[MPS-2021-3396](https://www.oscs1024.com/hd/MPS-2021-3396)|CVE-2021-21347|高危|
|Oracle Java SE 输入验证错误漏洞|反序列化|[MPS-2021-36472](https://www.oscs1024.com/hd/MPS-2021-36472)|CVE-2022-21248|低危|
|Oracle Java SE和Oracle GraalVM 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-2021-36501](https://www.oscs1024.com/hd/MPS-2021-36501)|CVE-2022-21277|中危|
|Oracle Java SE 输入验证错误漏洞|未授权敏感信息泄露|[MPS-2021-36506](https://www.oscs1024.com/hd/MPS-2021-36506)|CVE-2022-21282|中危|
|Oracle Java SE 输入验证错误漏洞|未捕获的异常|[MPS-2021-36507](https://www.oscs1024.com/hd/MPS-2021-36507)|CVE-2022-21283|中危|
|Oracle GraalVM 输入验证错误漏洞|越界写入|[MPS-2021-36515](https://www.oscs1024.com/hd/MPS-2021-36515)|CVE-2022-21291|中危|
|Oracle Java SE  输入验证错误漏洞|拒绝服务|[MPS-2021-36517](https://www.oscs1024.com/hd/MPS-2021-36517)|CVE-2022-21293|中危|
|Oracle Java SE 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-2021-36518](https://www.oscs1024.com/hd/MPS-2021-36518)|CVE-2022-21294|中危|
|Oracle Java SE  输入验证错误漏洞|未授权敏感信息泄露|[MPS-2021-36520](https://www.oscs1024.com/hd/MPS-2021-36520)|CVE-2022-21296|中危|
|Oracle Java SE   输入验证错误漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-36523](https://www.oscs1024.com/hd/MPS-2021-36523)|CVE-2022-21299|中危|
|Oracle Java SE 输入验证错误漏洞|整数溢出或环绕|[MPS-2021-36529](https://www.oscs1024.com/hd/MPS-2021-36529)|CVE-2022-21305|中危|
|Oracle Java SE 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-2021-36564](https://www.oscs1024.com/hd/MPS-2021-36564)|CVE-2022-21340|中危|
|Oracle Java SE 输入验证错误漏洞|拒绝服务|[MPS-2021-36565](https://www.oscs1024.com/hd/MPS-2021-36565)|CVE-2022-21341|中危|
|Oracle GraalVM 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-2021-36584](https://www.oscs1024.com/hd/MPS-2021-36584)|CVE-2022-21360|中危|
|Oracle MySQL 的 MySQL Connectors 存在授权不当漏洞|授权机制不恰当|[MPS-2021-36587](https://www.oscs1024.com/hd/MPS-2021-36587)|CVE-2022-21363|中危|
|Oracle Java SE和Oracle GraalVM 输入验证错误漏洞|整数溢出或环绕|[MPS-2021-36589](https://www.oscs1024.com/hd/MPS-2021-36589)|CVE-2022-21365|中危|
|Oracle GraalVM 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-2021-36590](https://www.oscs1024.com/hd/MPS-2021-36590)|CVE-2022-21366|中危|
|Oracle Java SE 和 Oracle GraalVM 输入验证错误漏洞|拒绝服务|[MPS-2021-36650](https://www.oscs1024.com/hd/MPS-2021-36650)|CVE-2022-21426|中危|
|Oracle Java SE 和 Oracle GraalVM 输入验证错误漏洞|使用外部可控制的输入来选择类或代码（不安全的反射）|[MPS-2021-36658](https://www.oscs1024.com/hd/MPS-2021-36658)|CVE-2022-21434|中危|
|Oracle Java SE 输入验证错误漏洞||[MPS-2021-36667](https://www.oscs1024.com/hd/MPS-2021-36667)|CVE-2022-21443|低危|
|Java SE 数字签名伪造漏洞|密码学签名的验证不恰当|[MPS-2021-36673](https://www.oscs1024.com/hd/MPS-2021-36673)|CVE-2022-21449|高危|
|Oracle Java SE 输入验证错误漏洞||[MPS-2021-36700](https://www.oscs1024.com/hd/MPS-2021-36700)|CVE-2022-21476|高危|
|Oracle Java SE 输入验证错误漏洞||[MPS-2021-36720](https://www.oscs1024.com/hd/MPS-2021-36720)|CVE-2022-21496|中危|
|XStream < 1.4.19存在拒绝服务漏洞|拒绝服务|[MPS-2021-36984](https://www.oscs1024.com/hd/MPS-2021-36984)|CVE-2021-43859|高危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|XStream 远程代码执行漏洞||[MPS-2021-7164](https://www.oscs1024.com/hd/MPS-2021-7164)|CVE-2021-29505|高危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9827](https://www.oscs1024.com/hd/MPS-2021-9827)|CVE-2021-36373|中危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9847](https://www.oscs1024.com/hd/MPS-2021-9847)|CVE-2021-36374|中危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|Apache POI <3.16-beta1 拒绝服务漏洞|拒绝服务|[MPS-2022-11862](https://www.oscs1024.com/hd/MPS-2022-11862)||中危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|Apache HttpClient URI解析错误漏洞|相对路径遍历|[MPS-2022-12292](https://www.oscs1024.com/hd/MPS-2022-12292)||中危|
|org.json:json 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13520](https://www.oscs1024.com/hd/MPS-2022-13520)||高危|
|Apache XercesJ <=2.12.1 存在XML注入漏洞|XPath盲注|[MPS-2022-1864](https://www.oscs1024.com/hd/MPS-2022-1864)|CVE-2022-23437|中危|
|jsoup <1.15.3 存在反射型 XSS 漏洞|XSS|[MPS-2022-51547](https://www.oscs1024.com/hd/MPS-2022-51547)|CVE-2022-36033|中危|
|xstream project跨界内存写漏洞|越界写入|[MPS-2022-57066](https://www.oscs1024.com/hd/MPS-2022-57066)|CVE-2022-40151|高危|
|XStream < 1.4.20 栈缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58603](https://www.oscs1024.com/hd/MPS-2022-58603)|CVE-2022-41966|中危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68515](https://www.oscs1024.com/hd/MPS-2022-68515)|CVE-2023-21930|高危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68522](https://www.oscs1024.com/hd/MPS-2022-68522)|CVE-2023-21937|低危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68523](https://www.oscs1024.com/hd/MPS-2022-68523)|CVE-2023-21938|低危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68524](https://www.oscs1024.com/hd/MPS-2022-68524)|CVE-2023-21939|中危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68539](https://www.oscs1024.com/hd/MPS-2022-68539)|CVE-2023-21954|中危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68552](https://www.oscs1024.com/hd/MPS-2022-68552)|CVE-2023-21967|中危|
|Oracle Java SE和Oracle GraalVM 安全漏洞||[MPS-2022-68553](https://www.oscs1024.com/hd/MPS-2022-68553)|CVE-2023-21968|低危|
|Oracle Java SE 安全漏洞||[MPS-2022-68591](https://www.oscs1024.com/hd/MPS-2022-68591)|CVE-2023-22006|低危|
|Oracle Java SE 安全漏洞||[MPS-2022-68621](https://www.oscs1024.com/hd/MPS-2022-68621)|CVE-2023-22036|低危|
|Oracle Java SE 安全漏洞||[MPS-2022-68626](https://www.oscs1024.com/hd/MPS-2022-68626)|CVE-2023-22041|中危|
|Oracle Java SE 安全漏洞||[MPS-2022-68630](https://www.oscs1024.com/hd/MPS-2022-68630)|CVE-2023-22045|低危|
|Oracle Java SE 安全漏洞||[MPS-2022-68634](https://www.oscs1024.com/hd/MPS-2022-68634)|CVE-2023-22049|低危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|Spring Security 路径匹配漏洞|不恰当实现的标准安全检查|[MPS-j3nx-691g](https://www.oscs1024.com/hd/MPS-j3nx-691g)|CVE-2023-34034|严重|
|Spring Security鉴权规则错误配置风险|关键资源权限分配不当|[MPS-l6z0-dktm](https://www.oscs1024.com/hd/MPS-l6z0-dktm)|CVE-2023-34035|高危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.thoughtworks.xstream:xstream|1.4.9|1.4.20|间接依赖|强烈建议修复|C:1|H:24|M:7|L:0|
|commons-beanutils:commons-beanutils|1.8.0|1.9.4|直接依赖|强烈建议修复|C:0|H:2|M:0|L:0|
|mysql:mysql-connector-java|5.1.21|8.0.28|直接依赖|建议修复|C:0|H:2|M:5|L:1|
|io.netty:netty-handler|4.1.92.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.yaml:snakeyaml|1.33|2.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.poi:poi-ooxml|3.15|4.1.1|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.15.0||间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.apache.xmlbeans:xmlbeans|2.6.0|3.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.graalvm.sdk:graal-sdk|20.0.0|22.3.3|间接依赖|建议修复|C:0|H:3|M:23|L:10|
|org.apache.poi:poi|3.15|3.17|直接依赖|建议修复|C:0|H:1|M:1|L:0|
|com.squareup.okio:okio-jvm|3.0.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.quartz-scheduler:quartz|2.3.0|2.3.2|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework.security:spring-security-config|6.1.0|6.1.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.squareup.okio:okio|1.12.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework.security:spring-security-web|6.1.0|6.1.2|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.apache.ant:ant|1.9.6|1.10.11|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|org.apache.httpcomponents:httpclient|4.5|4.5.13|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.jsoup:jsoup|1.10.2|1.15.3|直接依赖|可选修复|C:0|H:1|M:1|L:0|
|com.google.guava:guava|25.1-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:1|
|com.google.code.gson:gson|2.8.1|2.8.9|直接依赖|可选修复|C:0|H:1|M:0|L:0|
|xerces:xercesImpl|2.11.0|2.12.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.json:json|20140107|20180130|直接依赖|可选修复|C:0|H:1|M:0|L:0|
|commons-io:commons-io|2.4|2.7|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-codec:commons-codec|1.10|1.13|直接依赖|可选修复|C:0|H:0|M:0|L:1|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|33|Low|
|JSON|1|Low|
|Apache-2.0|155|Low|
|EPL-2.0|5|Low|
|MIT|11|Low|
|EPL-1.0|5|Low|
|BSD-2-Clause|12|Low|
|CDDL-1.1|1|Low|
|CDDL-1.0|1|Low|
|UPL-1.0|4|Low|
|MIT-0|1|Low|
|LGPL-2.1-or-later|2|Low|
|LGPL-2.1|2|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.thoughtworks.xstream:xstream|1.4.9|间接依赖|maven|
|org.json:json|20140107|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-security|3.1.0|直接依赖|maven|
|org.attoparser:attoparser|2.0.6.RELEASE|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator|3.1.0|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.1|间接依赖|maven|
|io.smallrye:jandex|3.0.5|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-redis|3.1.0|直接依赖|maven|
|jakarta.transaction:jakarta.transaction-api|2.0.1|间接依赖|maven|
|org.codehaus.mojo:animal-sniffer-annotations|1.14|间接依赖|maven|
|org.aspectj:aspectjrt|1.9.4|直接依赖|maven|
|stax:stax-api|1.0.1|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.8.0|直接依赖|maven|
|org.apache.commons:commons-lang3|3.11|直接依赖|maven|
|org.apache.xmlbeans:xmlbeans|2.6.0|间接依赖|maven|
|org.apache.ant:ant|1.9.6|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.8.21|间接依赖|maven|
|com.vladsch.flexmark:flexmark|0.60.2|间接依赖|maven|
|org.jasypt:jasypt|1.9.2|直接依赖|maven|
|com.aliyun:aliyun-java-sdk-core|3.3.1|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-xml|2.15.0|直接依赖|maven|
|net.jcip:jcip-annotations|1.0|间接依赖|maven|
|org.slf4j:slf4j-api|2.0.7|间接依赖|maven|
|org.springframework.security:spring-security-web|6.1.0|间接依赖|maven|
|org.springframework:spring-web|6.0.9|间接依赖|maven|
|cglib:cglib|3.2.5|直接依赖|maven|
|com.github.dadiyang:jave|1.0.2|直接依赖|maven|
|com.vladsch.flexmark:flexmark-util-builder|0.60.2|间接依赖|maven|
|com.github.virtuald:curvesapi|1.04|间接依赖|maven|
|org.apache.tomcat.embed:tomcat-embed-el|10.1.8|间接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|直接依赖|maven|
|org.slf4j:jul-to-slf4j|2.0.7|间接依赖|maven|
|com.fasterxml:classmate|1.5.1|间接依赖|maven|
|ch.qos.logback:logback-core|1.4.7|间接依赖|maven|
|javax.activation:activation|1.1.1|直接依赖|maven|
|org.springframework:spring-context|6.0.9|间接依赖|maven|
|com.zaxxer:HikariCP|5.0.1|间接依赖|maven|
|org.graalvm.truffle:truffle-api|20.0.0|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.15.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|3.1.0|间接依赖|maven|
|org.aspectj:aspectjweaver|1.9.4|直接依赖|maven|
|org.springframework.boot:spring-boot|3.1.0|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.1.3|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|3.1.0|直接依赖|maven|
|org.quartz-scheduler:quartz|2.3.0|直接依赖|maven|
|com.vladsch.flexmark:flexmark-util-dependency|0.60.2|间接依赖|maven|
|joda-time:joda-time|2.9.9|直接依赖|maven|
|org.springframework.session:spring-session-core|3.1.0|间接依赖|maven|
|org.apache.commons:commons-collections4|4.1|间接依赖|maven|
|org.springframework:spring-jdbc|6.0.9|间接依赖|maven|
|org.fusesource.hawtbuf:hawtbuf|1.11|间接依赖|maven|
|org.messaginghub:pooled-jms|3.1.0|直接依赖|maven|
|io.prometheus:simpleclient_common|0.16.0|间接依赖|maven|
|io.projectreactor:reactor-core|3.5.6|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-html|0.60.2|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.16|间接依赖|maven|
|commons-codec:commons-codec|1.10|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.15.0|间接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|org.apache.commons:commons-pool2|2.11.1|间接依赖|maven|
|com.lmax:disruptor|3.3.6|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|3.1.0|间接依赖|maven|
|org.springframework:spring-expression|6.0.9|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.8.21|间接依赖|maven|
|com.googlecode.aviator:aviator|3.3.0|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.8.21|间接依赖|maven|
|org.checkerframework:checker-qual|2.0.0|间接依赖|maven|
|org.springframework.plugin:spring-plugin-core|3.0.0|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.92.Final|间接依赖|maven|
|org.ow2.asm:asm-tree|7.1|间接依赖|maven|
|xerces:xercesImpl|2.11.0|间接依赖|maven|
|io.netty:netty-transport|4.1.92.Final|间接依赖|maven|
|org.ow2.asm:asm-util|7.1|间接依赖|maven|
|org.graalvm.sdk:graal-sdk|20.0.0|间接依赖|maven|
|org.springframework.data:spring-data-keyvalue|3.1.0|间接依赖|maven|
|org.springframework:spring-jms|6.0.9|间接依赖|maven|
|org.springframework:spring-context-support|6.0.9|直接依赖|maven|
|org.antlr:antlr4-runtime|4.10.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-thymeleaf|3.1.0|直接依赖|maven|
|io.micrometer:micrometer-registry-prometheus|1.11.1|直接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|3.1.6|间接依赖|maven|
|org.latencyutils:LatencyUtils|2.0.3|间接依赖|maven|
|org.springframework:spring-aspects|6.0.9|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-json|3.1.0|间接依赖|maven|
|org.springframework.boot:spring-boot-actuator-autoconfigure|3.1.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-data-jpa|3.1.0|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.15.0|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-data|0.60.2|间接依赖|maven|
|com.squareup.okhttp3:okhttp|4.10.0|间接依赖|maven|
|com.google.code.gson:gson|2.8.1|直接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|org.olap4j:olap4j|1.2.0|直接依赖|maven|
|org.jboss.logging:jboss-logging|3.5.0.Final|间接依赖|maven|
|org.springframework:spring-orm|6.0.9|间接依赖|maven|
|com.belerweb:pinyin4j|2.5.0|直接依赖|maven|
|org.springframework.data:spring-data-redis|3.1.0|间接依赖|maven|
|org.apache.commons:commons-text|1.10.0|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.15.0|间接依赖|maven|
|org.apache.poi:poi-ooxml-schemas|3.15|间接依赖|maven|
|org.hibernate.common:hibernate-commons-annotations|6.0.6.Final|间接依赖|maven|
|org.springframework.data:spring-data-jpa|3.1.0|间接依赖|maven|
|jakarta.servlet:jakarta.servlet-api|6.0.0|直接依赖|maven|
|io.minio:minio|5.0.0|直接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|2.1.1|间接依赖|maven|
|com.sun.istack:istack-commons-runtime|4.1.1|间接依赖|maven|
|org.springframework:spring-core|6.0.9|间接依赖|maven|
|org.glassfish.jaxb:jaxb-runtime|2.3.1|直接依赖|maven|
|org.graalvm.js:js-scriptengine|20.0.0|间接依赖|maven|
|org.springframework:spring-oxm|6.0.9|间接依赖|maven|
|commons-io:commons-io|2.4|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.8.21|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-ast|0.60.2|间接依赖|maven|
|org.springframework:spring-messaging|6.0.9|间接依赖|maven|
|io.netty:netty-common|4.1.92.Final|间接依赖|maven|
|org.freemarker:freemarker|2.3.32|间接依赖|maven|
|org.apache.activemq:activemq-client-jakarta|5.18.1|间接依赖|maven|
|io.prometheus:simpleclient|0.16.0|间接依赖|maven|
|net.coobird:thumbnailator|0.4.19|直接依赖|maven|
|org.graalvm.regex:regex|20.0.0|间接依赖|maven|
|commons-dbutils:commons-dbutils|1.6|直接依赖|maven|
|io.micrometer:micrometer-spring-legacy|1.3.20|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-validation|3.1.0|直接依赖|maven|
|com.mchange:mchange-commons-java|0.2.11|间接依赖|maven|
|javax.mail:javax.mail-api|1.5.1|直接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.15.0|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|间接依赖|maven|
|org.springframework:spring-jcl|6.0.9|间接依赖|maven|
|org.graalvm.tools:profiler|20.0.0|间接依赖|maven|
|io.netty:netty-resolver|4.1.92.Final|间接依赖|maven|
|com.corundumstudio.socketio:netty-socketio|1.7.19|直接依赖|maven|
|de.odysseus.juel:juel-impl|2.2.7|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.15.0|间接依赖|maven|
|io.netty:netty-codec|4.1.92.Final|间接依赖|maven|
|io.netty:netty-handler|4.1.92.Final|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-misc|0.60.2|间接依赖|maven|
|io.prometheus:simpleclient_tracer_common|0.16.0|间接依赖|maven|
|io.micrometer:micrometer-core|1.11.0|间接依赖|maven|
|org.apache.httpcomponents:httpmime|4.5|间接依赖|maven|
|com.googlecode.concurrentlinkedhashmap:concurrentlinkedhashmap-lru|1.4.2|间接依赖|maven|
|com.google.code.findbugs:annotations|3.0.1|间接依赖|maven|
|io.micrometer:micrometer-commons|1.11.0|间接依赖|maven|
|org.springframework:spring-beans|6.0.9|间接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.20.0|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-web|3.1.0|直接依赖|maven|
|com.chatopera.compose4j:compose4j|1.0.0|直接依赖|maven|
|io.netty:netty-buffer|4.1.92.Final|间接依赖|maven|
|org.springframework:spring-tx|6.0.9|间接依赖|maven|
|com.google.http-client:google-http-client|1.20.0|间接依赖|maven|
|org.apache.ant:ant-launcher|1.9.6|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.92.Final|间接依赖|maven|
|org.jsoup:jsoup|1.10.2|直接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.92.Final|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5|间接依赖|maven|
|ch.qos.logback:logback-classic|1.4.7|间接依赖|maven|
|com.konghq:unirest-java|3.10.00|直接依赖|maven|
|net.java.dev.jna:jna|4.1.0|直接依赖|maven|
|jakarta.inject:jakarta.inject-api|2.0.1|间接依赖|maven|
|org.thymeleaf:thymeleaf|3.1.1.RELEASE|间接依赖|maven|
|com.ibm.icu:icu4j|64.2|间接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.5|间接依赖|maven|
|com.google.http-client:google-http-client-xml|1.20.0|间接依赖|maven|
|io.lettuce:lettuce-core|6.2.4.RELEASE|间接依赖|maven|
|de.neuland-bfi:pug4j|2.0.0-alpha-4-SNAPSHOT|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-format|0.60.2|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-hateoas|3.1.0|直接依赖|maven|
|de.neuland-bfi:spring-pug4j|3.0.1c-SNAPSHOT|直接依赖|maven|
|jakarta.jms:jakarta.jms-api|3.1.0|间接依赖|maven|
|io.micrometer:micrometer-observation|1.11.0|间接依赖|maven|
|org.jvnet.staxex:stax-ex|2.1.0|间接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|3.1.0|间接依赖|maven|
|xpp3:xpp3|1.1.4c|间接依赖|maven|
|org.ow2.asm:asm-commons|7.1|间接依赖|maven|
|xmlpull:xmlpull|1.1.3.1|间接依赖|maven|
|redis.clients:jedis|4.3.2|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-dysmsapi|1.0.0|直接依赖|maven|
|com.squareup.okio:okio-jvm|3.0.0|间接依赖|maven|
|org.apache.poi:poi-ooxml|3.15|直接依赖|maven|
|org.apache.commons:commons-jexl3|3.1|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-sequence|0.60.2|间接依赖|maven|
|mysql:mysql-connector-java|5.1.21|直接依赖|maven|
|org.springframework.security:spring-security-crypto|6.1.0|间接依赖|maven|
|org.yaml:snakeyaml|1.33|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|3.0.2|间接依赖|maven|
|org.unbescape:unbescape|1.1.6.RELEASE|间接依赖|maven|
|xpp3:xpp3_min|1.1.4c|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-collection|0.60.2|间接依赖|maven|
|com.google.guava:guava|25.1-jre|直接依赖|maven|
|io.prometheus:simpleclient_tracer_otel_agent|0.16.0|间接依赖|maven|
|com.sun.mail:javax.mail|1.6.0|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-actuator|3.1.0|直接依赖|maven|
|org.springframework.security:spring-security-config|6.1.0|间接依赖|maven|
|commons-logging:commons-logging|1.1.1|间接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.16|间接依赖|maven|
|com.alibaba:fastjson|1.2.83|直接依赖|maven|
|com.fasterxml.woodstox:woodstox-core|6.5.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-activemq|3.1.0|直接依赖|maven|
|org.codehaus.woodstox:stax2-api|4.2.1|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-cache|3.1.0|直接依赖|maven|
|org.springframework:spring-webmvc|6.0.9|间接依赖|maven|
|com.github.binarywang:weixin-java-mp|2.6.0|直接依赖|maven|
|org.graalvm.tools:chromeinspector|20.0.0|间接依赖|maven|
|org.lionsoul:ip2region|1.7.2|直接依赖|maven|
|org.hibernate.orm:hibernate-core|6.2.2.Final|间接依赖|maven|
|mondrian:mondrian|3.7.0|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-freemarker|3.1.0|直接依赖|maven|
|io.prometheus:simpleclient_tracer_otel|0.16.0|间接依赖|maven|
|com.vladsch.flexmark:flexmark-util-visitor|0.60.2|间接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|com.sun.xml.fastinfoset:FastInfoset|2.1.0|间接依赖|maven|
|org.thymeleaf:thymeleaf-spring6|3.1.1.RELEASE|间接依赖|maven|
|org.ow2.asm:asm|6.0_ALPHA|间接依赖|maven|
|org.springframework.hateoas:spring-hateoas|2.1.0|间接依赖|maven|
|commons-collections:commons-collections|3.2.2|直接依赖|maven|
|org.springframework.boot:spring-boot-starter-aop|3.1.0|直接依赖|maven|
|org.springframework.session:spring-session-data-redis|3.1.0|直接依赖|maven|
|org.springframework.security:spring-security-core|6.1.0|间接依赖|maven|
|org.springframework:spring-aop|6.0.9|间接依赖|maven|
|com.oracle:ojdbc6|12.1.0.1-atlassian-hosted|直接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.20.0|间接依赖|maven|
|org:jaudiotagger|2.0.1|直接依赖|maven|
|com.github.binarywang:weixin-java-common|2.6.0|间接依赖|maven|
|org.springframework.data:spring-data-commons|3.1.0|间接依赖|maven|
|io.netty:netty-codec-http|4.1.92.Final|间接依赖|maven|
|com.squareup.okio:okio|1.12.0|间接依赖|maven|
|org.glassfish.jaxb:txw2|4.0.2|间接依赖|maven|
|xml-apis:xml-apis|1.4.01|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.20.0|间接依赖|maven|
|org.apache.logging.log4j:log4j-1.2-api|2.20.0|直接依赖|maven|
|jakarta.persistence:jakarta.persistence-api|3.1.0|间接依赖|maven|
|com.chatopera.bot:sdk|3.5.1|直接依赖|maven|
|org.graalvm.js:js|20.0.0|间接依赖|maven|
|org.hibernate.validator:hibernate-validator|8.0.0.Final|间接依赖|maven|
|org.apache.poi:poi|3.15|直接依赖|maven|
|org.ow2.asm:asm-analysis|7.1|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)