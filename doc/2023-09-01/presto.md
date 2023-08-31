# prestodb/presto安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1697310009988640768.svg)](https://www.murphysec.com/console/report/1696947483128000512/1697310009988640768)

仓库描述：The official home of the Presto distributed SQL query engine for big data

仓库地址：[https://github.com/prestodb/presto](https://github.com/prestodb/presto)

| star：15008 | watch：875 | fork：5108 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-01 02:03:12 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-01 02:32:22 | 组件总数：1382 | 漏洞总数：179 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache HttpClient 中间人攻击漏洞|输入验证不恰当|[MPS-2014-4288](https://www.oscs1024.com/hd/MPS-2014-4288)|CVE-2012-6153|中危|
|async-http-client 安全漏洞|对数据真实性的验证不充分|[MPS-2015-3021](https://www.oscs1024.com/hd/MPS-2015-3021)|CVE-2013-7397|中危|
|Async Http Client 加密问题漏洞|对数据真实性的验证不充分|[MPS-2015-3022](https://www.oscs1024.com/hd/MPS-2015-3022)|CVE-2013-7398|中危|
|Pivotal Software Spring Framework 安全漏洞|缓冲区溢出|[MPS-2016-3388](https://www.oscs1024.com/hd/MPS-2016-3388)|CVE-2015-3192|中危|
|JCraft JSch 路径遍历漏洞|路径遍历|[MPS-2017-0498](https://www.oscs1024.com/hd/MPS-2017-0498)|CVE-2016-5725|中危|
|Apache Solr 存在 XXE 注入漏洞|XXE|[MPS-2017-11558](https://www.oscs1024.com/hd/MPS-2017-11558)|CVE-2017-12629|严重|
|Netty和Play Framework 输入验证错误漏洞|未授权敏感信息泄露|[MPS-2017-11682](https://www.oscs1024.com/hd/MPS-2017-11682)|CVE-2015-2156|高危|
|Spring Framework 反射文件下载(RFD)漏洞|对外部实体的文件或目录可访问|[MPS-2017-5904](https://www.oscs1024.com/hd/MPS-2017-5904)|CVE-2015-5211|严重|
|plexus-utils <3.0.16 命令注入漏洞|OS命令注入|[MPS-2018-0091](https://www.oscs1024.com/hd/MPS-2018-0091)|CVE-2017-1000487|严重|
|Apache Commons Compress 存在拒绝服务漏洞|不可达退出条件的循环（无限循环）|[MPS-2018-11233](https://www.oscs1024.com/hd/MPS-2018-11233)|CVE-2018-11771|中危|
|PostgreSQL JDBC <42.2.5 存在证书验证不当漏洞|对宿主不匹配的证书验证不恰当|[MPS-2018-11656](https://www.oscs1024.com/hd/MPS-2018-11656)|CVE-2018-10936|高危|
|Elasticsearch 存在信息泄漏漏洞|敏感信息泄露|[MPS-2018-12513](https://www.oscs1024.com/hd/MPS-2018-12513)|CVE-2018-3826|中危|
|Elasticsearch repository-azure 插件存在信息泄露漏洞|日志敏感信息泄露|[MPS-2018-12514](https://www.oscs1024.com/hd/MPS-2018-12514)|CVE-2018-3827|高危|
|Elasticsearch Alerting and Monitoring 模块存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2018-12518](https://www.oscs1024.com/hd/MPS-2018-12518)|CVE-2018-3831|高危|
|Oracle MySQL Connectors 访问控制错误漏洞|使用候选路径或通道进行的认证绕过|[MPS-2018-13771](https://www.oscs1024.com/hd/MPS-2018-13771)|CVE-2018-3258|高危|
|React XSS 漏洞|XSS|[MPS-2018-16483](https://www.oscs1024.com/hd/MPS-2018-16483)|CVE-2018-6341|中危|
|Apache Thrift <0.12.0 绕过验证漏洞|证书验证不恰当|[MPS-2019-0104](https://www.oscs1024.com/hd/MPS-2019-0104)|CVE-2018-1320|高危|
|Apache Commons Beanutils 存在不可信数据的反序列化漏洞|反序列化|[MPS-2019-10233](https://www.oscs1024.com/hd/MPS-2019-10233)|CVE-2019-10086|高危|
|mixin-deep 参数注入漏洞|参数注入或修改|[MPS-2019-10507](https://www.oscs1024.com/hd/MPS-2019-10507)|CVE-2019-10746|严重|
|set-value 存在拒绝服务漏洞|拒绝服务|[MPS-2019-10508](https://www.oscs1024.com/hd/MPS-2019-10508)|CVE-2019-10747|中危|
|Apache Commons Compress 资源管理错误漏洞|不可达退出条件的循环（无限循环）|[MPS-2019-10880](https://www.oscs1024.com/hd/MPS-2019-10880)|CVE-2019-12402|高危|
|Netty 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2019-12064](https://www.oscs1024.com/hd/MPS-2019-12064)|CVE-2019-16869|高危|
|lodash 存在拒绝服务漏洞|拒绝服务|[MPS-2019-1228](https://www.oscs1024.com/hd/MPS-2019-1228)|CVE-2018-16487|中危|
|Red Hat JBoss Enterprise Application Platform 代码问题漏洞|反序列化|[MPS-2019-12470](https://www.oscs1024.com/hd/MPS-2019-12470)|CVE-2019-10202|严重|
|Elasticsearch 存在敏感信息泄露漏洞|未授权敏感信息泄露|[MPS-2019-13902](https://www.oscs1024.com/hd/MPS-2019-13902)|CVE-2019-7619|中危|
|​ hibernate-validator  存在跨站脚本（XSS）漏洞|XSS|[MPS-2019-14389](https://www.oscs1024.com/hd/MPS-2019-14389)|CVE-2019-10219|中危|
|jackson-mapper-asl <=1.9.13 XXE 注入漏洞|XXE|[MPS-2019-15048](https://www.oscs1024.com/hd/MPS-2019-15048)|CVE-2019-10172|高危|
|serialize-javascript < 2.1.2 跨站脚本漏洞|XSS|[MPS-2019-15864](https://www.oscs1024.com/hd/MPS-2019-15864)|CVE-2019-16769|中危|
|SnakeYAML <1.26 存在 Billion laughs 漏洞|拒绝服务|[MPS-2019-16129](https://www.oscs1024.com/hd/MPS-2019-16129)|CVE-2017-18640|高危|
|kind-of 存在注入漏洞|将资源暴露给错误范围|[MPS-2019-17164](https://www.oscs1024.com/hd/MPS-2019-17164)|CVE-2019-20149|高危|
|Elasticsearch 权限提升漏洞|权限问题|[MPS-2019-2964](https://www.oscs1024.com/hd/MPS-2019-2964)|CVE-2019-7611|高危|
|Eclipse Jetty 信息泄露漏洞|未授权敏感信息泄露|[MPS-2019-4270](https://www.oscs1024.com/hd/MPS-2019-4270)|CVE-2019-10247|中危|
|Oracle MySQL Connectors 输入验证错误漏洞|使用不兼容类型访问资源（类型混淆）|[MPS-2019-4430](https://www.oscs1024.com/hd/MPS-2019-4430)|CVE-2019-2692|中危|
|lodash <4.7.11 正则表达式拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2019-8123](https://www.oscs1024.com/hd/MPS-2019-8123)|CVE-2019-1010266|中危|
|lodash 原型污染漏洞|拒绝服务|[MPS-2019-8636](https://www.oscs1024.com/hd/MPS-2019-8636)|CVE-2019-10744|严重|
|Elasticsearch 存在竞争条件漏洞|竞争条件|[MPS-2019-8854](https://www.oscs1024.com/hd/MPS-2019-8854)|CVE-2019-7614|中危|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|google-oauth-java-client <1.31.0授权不当漏洞|授权检查错误|[MPS-2020-10000](https://www.oscs1024.com/hd/MPS-2020-10000)|CVE-2020-7692|严重|
|Ajv v6.12.2 输入验证错误漏洞|MAID|[MPS-2020-10525](https://www.oscs1024.com/hd/MPS-2020-10525)|CVE-2020-15366|中危|
|npm node-fetch 不加限制的资源分配漏洞|不加限制或调节的资源分配|[MPS-2020-12719](https://www.oscs1024.com/hd/MPS-2020-12719)|CVE-2020-15168|中危|
|ua-parser-js <0.7.22 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2020-13044](https://www.oscs1024.com/hd/MPS-2020-13044)|CVE-2020-7733|高危|
|Pivotal Spring Framework 反射文件下载 (RFD) 漏洞|路径遍历|[MPS-2020-13322](https://www.oscs1024.com/hd/MPS-2020-13322)|CVE-2020-5421|中危|
|lodash <4.17.15 原型污染漏洞|原型污染|[MPS-2020-15679](https://www.oscs1024.com/hd/MPS-2020-15679)|CVE-2020-8203|高危|
|Elasticsearch 存在权限管理不恰当漏洞|权限管理不当|[MPS-2020-15777](https://www.oscs1024.com/hd/MPS-2020-15777)|CVE-2020-7020|低危|
|dot-prop 原型污染漏洞|原型污染|[MPS-2020-1734](https://www.oscs1024.com/hd/MPS-2020-1734)|CVE-2020-8116|高危|
|Apache HttpClient URI解析错误漏洞|XSS|[MPS-2020-17341](https://www.oscs1024.com/hd/MPS-2020-17341)|CVE-2020-13956|中危|
|FasterXML jackson-databind 代码问题漏洞|XXE|[MPS-2020-17358](https://www.oscs1024.com/hd/MPS-2020-17358)|CVE-2020-25649|高危|
|ua-parser-js DOS漏洞|拒绝服务|[MPS-2020-17428](https://www.oscs1024.com/hd/MPS-2020-17428)|CVE-2020-7793|高危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Yargs Y18n 输入原型污染漏洞|动态确定对象属性修改的控制不恰当|[MPS-2020-17543](https://www.oscs1024.com/hd/MPS-2020-17543)|CVE-2020-7774|严重|
|Ini <1.3.6原型污染漏洞|拒绝服务|[MPS-2020-17544](https://www.oscs1024.com/hd/MPS-2020-17544)|CVE-2020-7788|高危|
|Eclipse Jetty HTTP 请求走私漏洞|在释放前未清除敏感信息|[MPS-2020-17594](https://www.oscs1024.com/hd/MPS-2020-17594)|CVE-2020-27218|中危|
|Apache Accumulo 安全漏洞|关键资源权限分配不当|[MPS-2020-18052](https://www.oscs1024.com/hd/MPS-2020-18052)|CVE-2020-17533|高危|
|minimist 原型污染漏洞|原型污染|[MPS-2020-3516](https://www.oscs1024.com/hd/MPS-2020-3516)|CVE-2020-7598|中危|
|mysql:mysql-connector-java <8.0.27 存在 XXE 漏洞|XXE|[MPS-2020-38350](https://www.oscs1024.com/hd/MPS-2020-38350)|CVE-2021-2471|中危|
|yargs-parser 原型污染漏洞|特权定义了不安全动作|[MPS-2020-4006](https://www.oscs1024.com/hd/MPS-2020-4006)|CVE-2020-7608|中危|
|hibernate-validator 存在输入验证错误漏洞|代码注入|[MPS-2020-7077](https://www.oscs1024.com/hd/MPS-2020-7077)|CVE-2020-10693|中危|
|serialize-javascript <3.1.0 任意代码执行漏洞|反序列化|[MPS-2020-7976](https://www.oscs1024.com/hd/MPS-2020-7976)|CVE-2020-7660|高危|
|Elliptic package 签名伪造漏洞|整数溢出或环绕|[MPS-2020-8202](https://www.oscs1024.com/hd/MPS-2020-8202)|CVE-2020-13822|高危|
|PgJDBC <42.2.13 存在 XXE 漏洞|XXE|[MPS-2020-8204](https://www.oscs1024.com/hd/MPS-2020-8204)|CVE-2020-13692|高危|
|chownr package竞争条件问题漏洞|检查时间与使用时间(TOCTOU)的竞争条件|[MPS-2020-8858](https://www.oscs1024.com/hd/MPS-2020-8858)|CVE-2017-18869|低危|
|Apache Druid <0.20.0任意代码执行漏洞|代码注入|[MPS-2021-1023](https://www.oscs1024.com/hd/MPS-2021-1023)|CVE-2021-25646|高危|
|Apache Commons Compress 安存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10550](https://www.oscs1024.com/hd/MPS-2021-10550)|CVE-2021-35517|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10551](https://www.oscs1024.com/hd/MPS-2021-10551)|CVE-2021-35516|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10564](https://www.oscs1024.com/hd/MPS-2021-10564)|CVE-2021-36090|高危|
|Apache Commons Compress 无限循环漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-10565](https://www.oscs1024.com/hd/MPS-2021-10565)|CVE-2021-35515|高危|
|Elasticsearch 资源管理错误漏洞|未经控制的递归|[MPS-2021-11043](https://www.oscs1024.com/hd/MPS-2021-11043)|CVE-2021-22144|中危|
|node-tar 路径遍历漏洞|路径遍历|[MPS-2021-11547](https://www.oscs1024.com/hd/MPS-2021-11547)|CVE-2021-32804|高危|
|node-tar 路径遍历漏洞|在文件访问前对链接解析不恰当（链接跟随）|[MPS-2021-11548](https://www.oscs1024.com/hd/MPS-2021-11548)|CVE-2021-32803|高危|
|Indutny Elliptic 加密问题漏洞|密码算法不安全|[MPS-2021-1176](https://www.oscs1024.com/hd/MPS-2021-1176)|CVE-2020-28498|中危|
|Elasticsearch 日志信息泄露漏洞|日志敏感信息泄露|[MPS-2021-1485](https://www.oscs1024.com/hd/MPS-2021-1485)|CVE-2020-7021|中危|
|Spring Framework <5.3.14 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18854](https://www.oscs1024.com/hd/MPS-2021-18854)|CVE-2021-22060|中危|
|Pivotal Spring Framework 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18890](https://www.oscs1024.com/hd/MPS-2021-18890)|CVE-2021-22096|中危|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|Google google-oauth-java-client 数据伪造问题漏洞|密码学签名的验证不恰当|[MPS-2021-19070](https://www.oscs1024.com/hd/MPS-2021-19070)|CVE-2021-22573|高危|
|set-value 原型污染漏洞|使用不兼容类型访问资源（类型混淆）|[MPS-2021-19479](https://www.oscs1024.com/hd/MPS-2021-19479)|CVE-2021-23440|严重|
|com.h2database:h2 < 2.0.202 XXE漏洞|XXE|[MPS-2021-19502](https://www.oscs1024.com/hd/MPS-2021-19502)|CVE-2021-23463|严重|
|FasterXML jackson-dataformat-cbor 内存耗尽漏洞|不加限制或调节的资源分配|[MPS-2021-1998](https://www.oscs1024.com/hd/MPS-2021-1998)|CVE-2020-28491|高危|
|Eclipse Jetty <11.0.1 拒绝服务漏洞|拒绝服务|[MPS-2021-2571](https://www.oscs1024.com/hd/MPS-2021-2571)|CVE-2020-27223|中危|
|lodash 拒绝服务漏洞|拒绝服务|[MPS-2021-2574](https://www.oscs1024.com/hd/MPS-2021-2574)|CVE-2020-28500|中危|
|lodash 命令注入漏洞|代码注入|[MPS-2021-2638](https://www.oscs1024.com/hd/MPS-2021-2638)|CVE-2021-23337|高危|
|Apache Druid <0.22.0授权错误漏洞|授权检查错误|[MPS-2021-27767](https://www.oscs1024.com/hd/MPS-2021-27767)|CVE-2021-36749|中危|
|Apache Commons Net <3.9.0 存在FTP跳转攻击漏洞|未授权敏感信息泄露|[MPS-2021-28440](https://www.oscs1024.com/hd/MPS-2021-28440)|CVE-2021-37533|中危|
|Npm Node-tar 后置链接漏洞||[MPS-2021-28486](https://www.oscs1024.com/hd/MPS-2021-28486)|CVE-2021-37701|高危|
|Npm Node-tar 后置链接漏洞||[MPS-2021-28488](https://www.oscs1024.com/hd/MPS-2021-28488)|CVE-2021-37712|高危|
|node-tar 路径遍历漏洞|路径遍历|[MPS-2021-28489](https://www.oscs1024.com/hd/MPS-2021-28489)|CVE-2021-37713|高危|
|ssri 拒绝服务漏洞|拒绝服务|[MPS-2021-3030](https://www.oscs1024.com/hd/MPS-2021-3030)|CVE-2021-27290|高危|
|ua-parser-js 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-3199](https://www.oscs1024.com/hd/MPS-2021-3199)|CVE-2021-27292|高危|
|Apache Parquet 输入验证错误漏洞|拒绝服务|[MPS-2021-32354](https://www.oscs1024.com/hd/MPS-2021-32354)|CVE-2021-41561|高危|
|H2数据库存在JNDI注入漏洞|反序列化|[MPS-2021-33243](https://www.oscs1024.com/hd/MPS-2021-33243)|CVE-2021-42392|严重|
|Quality Open Software logback JNDI注入漏洞|反序列化|[MPS-2021-33911](https://www.oscs1024.com/hd/MPS-2021-33911)|CVE-2021-42550|中危|
|Ruy Adorno hosted-git-info 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-3400](https://www.oscs1024.com/hd/MPS-2021-3400)|CVE-2021-23362|中危|
|Oracle MySQL 的 MySQL Connectors 存在授权不当漏洞|授权机制不恰当|[MPS-2021-36587](https://www.oscs1024.com/hd/MPS-2021-36587)|CVE-2022-21363|中危|
|Apache Druid 远程代码执行漏洞|代码注入|[MPS-2021-3711](https://www.oscs1024.com/hd/MPS-2021-3711)|CVE-2021-26919|高危|
|Apache Druid 跨站脚本漏洞|XSS|[MPS-2021-38253](https://www.oscs1024.com/hd/MPS-2021-38253)|CVE-2021-44791|中危|
|minimist 安全漏洞|原型污染|[MPS-2021-38405](https://www.oscs1024.com/hd/MPS-2021-38405)|CVE-2021-44906|严重|
|Eclipse Jetty 资源管理错误漏洞|对异常条件的处理不恰当|[MPS-2021-3864](https://www.oscs1024.com/hd/MPS-2021-3864)|CVE-2021-28165|高危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|npm path-parse 安全漏洞|拒绝服务|[MPS-2021-6165](https://www.oscs1024.com/hd/MPS-2021-6165)|CVE-2021-23343|高危|
|Elasticsearch 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-6747](https://www.oscs1024.com/hd/MPS-2021-6747)|CVE-2021-22137|中危|
|Elasticsearch 信息泄露漏洞|未授权敏感信息泄露|[MPS-2021-6749](https://www.oscs1024.com/hd/MPS-2021-6749)|CVE-2021-22135|中危|
|trim-newlines 存在拒绝服务漏洞|拒绝服务|[MPS-2021-7398](https://www.oscs1024.com/hd/MPS-2021-7398)|CVE-2021-33623|高危|
|glob-parent < 5.1.2 存在拒绝服务漏洞|拒绝服务|[MPS-2021-7827](https://www.oscs1024.com/hd/MPS-2021-7827)|CVE-2020-28469|高危|
|Eclipse Jetty 存在信息泄露漏洞|不充分的会话过期机制|[MPS-2021-8884](https://www.oscs1024.com/hd/MPS-2021-8884)|CVE-2021-34428|低危|
|Apache Druid权限许可和访问控制问题漏洞|资源在另一范围的外部可控制索引|[MPS-2021-9406](https://www.oscs1024.com/hd/MPS-2021-9406)|CVE-2021-26920|中危|
|Vmware Spring Framework 安全漏洞|不加限制或调节的资源分配|[MPS-2022-1080](https://www.oscs1024.com/hd/MPS-2022-1080)|CVE-2022-22950|中危|
|Pivotal Spring Framework 安全限制绕过漏洞|大小写敏感处理不恰当|[MPS-2022-1098](https://www.oscs1024.com/hd/MPS-2022-1098)|CVE-2022-22968|中危|
|Spring Framework spring-beans 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1101](https://www.oscs1024.com/hd/MPS-2022-1101)|CVE-2022-22970|中危|
|plexus-utils <3.0.24 路径遍历漏洞|路径遍历|[MPS-2022-11760](https://www.oscs1024.com/hd/MPS-2022-11760)||中危|
|plexus-utils <3.0.24 XXE 漏洞|XPath盲注|[MPS-2022-11786](https://www.oscs1024.com/hd/MPS-2022-11786)||低危|
|org.mozilla:rhino <1.7.12 存在XXE漏洞|XXE|[MPS-2022-11928](https://www.oscs1024.com/hd/MPS-2022-11928)||高危|
|org.apache.commons:commons-dbcp2 存在信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-12024](https://www.oscs1024.com/hd/MPS-2022-12024)||低危|
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|org.glassfish.jersey.media:jersey-media-jaxb <2.31 存在XXE漏洞|XML实体扩展|[MPS-2022-12234](https://www.oscs1024.com/hd/MPS-2022-12234)||高危|
|org.webjars:swagger-ui 存在不安全的缺省变量初始化漏洞|不安全的缺省变量初始化|[MPS-2022-12253](https://www.oscs1024.com/hd/MPS-2022-12253)||中危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|Apache HttpClient URI解析错误漏洞|相对路径遍历|[MPS-2022-12292](https://www.oscs1024.com/hd/MPS-2022-12292)||中危|
|Logback SSL证书校验不当漏洞|中间人攻击|[MPS-2022-12411](https://www.oscs1024.com/hd/MPS-2022-12411)||中危|
|org.freemarker:freemarker <2.3.30 存在代码注入漏洞|代码注入|[MPS-2022-12438](https://www.oscs1024.com/hd/MPS-2022-12438)||高危|
|org.springframework:spring-context 存在拒绝服务漏洞|拒绝服务|[MPS-2022-12464](https://www.oscs1024.com/hd/MPS-2022-12464)||低危|
|FasterXML Jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2022-12500](https://www.oscs1024.com/hd/MPS-2022-12500)||中危|
|org.webjars:swagger-ui 存在关键信息的UI错误表达漏洞|关键信息的UI错误表达|[MPS-2022-12573](https://www.oscs1024.com/hd/MPS-2022-12573)||中危|
|acorn 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13525](https://www.oscs1024.com/hd/MPS-2022-13525)||高危|
|d3-color < 3.1.0 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13618](https://www.oscs1024.com/hd/MPS-2022-13618)||中危|
|elliptic<6.5.2 存在定时攻击漏洞|竞争条件|[MPS-2022-13653](https://www.oscs1024.com/hd/MPS-2022-13653)||中危|
|js-yaml 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13820](https://www.oscs1024.com/hd/MPS-2022-13820)||中危|
|js-yaml<3.13.1 存在代码注入漏洞|代码注入|[MPS-2022-13822](https://www.oscs1024.com/hd/MPS-2022-13822)||高危|
|lodash<4.17.20 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13841](https://www.oscs1024.com/hd/MPS-2022-13841)||高危|
|lodash<4.17.17 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13842](https://www.oscs1024.com/hd/MPS-2022-13842)||高危|
|tar 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2022-14081](https://www.oscs1024.com/hd/MPS-2022-14081)||低危|
|H2 Console 代码注入漏洞|代码注入|[MPS-2022-1435](https://www.oscs1024.com/hd/MPS-2022-1435)|CVE-2022-23221|严重|
|node-fetch 信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-1461](https://www.oscs1024.com/hd/MPS-2022-1461)|CVE-2022-0235|中危|
|Pivotal Spring Framework simpleMatch 方法存在拒绝服务漏洞|拒绝服务|[MPS-2022-16617](https://www.oscs1024.com/hd/MPS-2022-16617)||低危|
|Eclipse Jetty URI注入漏洞|注入|[MPS-2022-18060](https://www.oscs1024.com/hd/MPS-2022-18060)|CVE-2022-2047|低危|
|Eclipse Jetty 拒绝服务漏洞|在生命周期中对资源的控制不恰当|[MPS-2022-18061](https://www.oscs1024.com/hd/MPS-2022-18061)|CVE-2022-2048|高危|
|got 存在打开重定向漏洞|跨站重定向|[MPS-2022-19247](https://www.oscs1024.com/hd/MPS-2022-19247)|CVE-2022-33987|中危|
|Elastic Stack Kibana 存在缺少授权漏洞|授权检查缺失|[MPS-2022-2136](https://www.oscs1024.com/hd/MPS-2022-2136)|CVE-2022-23709|中危|
|Elastic Stack Kibana 存在 XSS 漏洞|XSS|[MPS-2022-2137](https://www.oscs1024.com/hd/MPS-2022-2137)|CVE-2022-23710|中危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|loader-utils 安全漏洞|不正确的正则表达式|[MPS-2022-53512](https://www.oscs1024.com/hd/MPS-2022-53512)|CVE-2022-37599|高危|
|loader-utils 安全漏洞|不正确的正则表达式|[MPS-2022-53516](https://www.oscs1024.com/hd/MPS-2022-53516)|CVE-2022-37603|高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|decode-uri-component <=0.2.0 存在输入验证不当漏洞|拒绝服务|[MPS-2022-56259](https://www.oscs1024.com/hd/MPS-2022-56259)|CVE-2022-38900|高危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|minimatch 资源管理错误漏洞|拒绝服务|[MPS-2022-59845](https://www.oscs1024.com/hd/MPS-2022-59845)|CVE-2022-3517|高危|
|Swagger UI URL注入漏洞|注入|[MPS-2022-6241](https://www.oscs1024.com/hd/MPS-2022-6241)|CVE-2018-25031|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|swagger-ui-dist 安全漏洞|渲染 UI 层或帧的不当限制|[MPS-2022-6243](https://www.oscs1024.com/hd/MPS-2022-6243)|CVE-2021-46708|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|TestNG <7.7.0  存在路径遍历（Zip Slip）漏洞|路径遍历|[MPS-2022-64736](https://www.oscs1024.com/hd/MPS-2022-64736)|CVE-2022-4065|高危|
|H2 数据库明文密码问题|未授权敏感信息泄露|[MPS-2022-65204](https://www.oscs1024.com/hd/MPS-2022-65204)|CVE-2022-45868|高危|
|Tauri 原型污染漏洞|原型污染|[MPS-2022-65568](https://www.oscs1024.com/hd/MPS-2022-65568)|CVE-2022-46175|高危|
|spring-boot <2.2.11.RELEASE 存在目录劫持漏洞|将资源暴露给错误范围|[MPS-2022-6780](https://www.oscs1024.com/hd/MPS-2022-6780)|CVE-2022-27772|高危|
|spring-beans 远程代码执行漏洞(Spring4Shell)|表达式语言注入|[MPS-2022-6820](https://www.oscs1024.com/hd/MPS-2022-6820)|CVE-2022-22965|严重|
|needle 存在Authorization请求头泄露漏洞|未授权敏感信息泄露|[MPS-2022-7866](https://www.oscs1024.com/hd/MPS-2022-7866)||中危|
|cross-fetch 安全漏洞|授权检查错误|[MPS-2022-8877](https://www.oscs1024.com/hd/MPS-2022-8877)|CVE-2022-1365|中危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Apache Kafka Connect 模块JNDI注入漏洞|反序列化|[MPS-2023-3834](https://www.oscs1024.com/hd/MPS-2023-3834)|CVE-2023-25194|高危|
|Eclipse Jetty 资源管理错误漏洞|拒绝服务|[MPS-2023-4997](https://www.oscs1024.com/hd/MPS-2023-4997)|CVE-2023-26048|中危|
|Eclipse Jetty 信息泄露漏洞|XSS|[MPS-2023-4998](https://www.oscs1024.com/hd/MPS-2023-4998)|CVE-2023-26049|中危|
|Apache Druid中Kafka配置远程代码执行漏洞|注入|[MPS-2023-6623](https://www.oscs1024.com/hd/MPS-2023-6623)||高危|
|netplex json-smart 安全漏洞|未经控制的递归|[MPS-2023-7760](https://www.oscs1024.com/hd/MPS-2023-7760)|CVE-2023-1370|高危|
|jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2023-8438](https://www.oscs1024.com/hd/MPS-2023-8438)|CVE-2021-46877|中危|
|snappy-java 输入验证错误漏洞|整数溢出或环绕|[MPS-8znw-4jmi](https://www.oscs1024.com/hd/MPS-8znw-4jmi)|CVE-2023-34453|高危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|Okio 安全漏洞|数值类型间的不正确转换|[MPS-a2tx-d4fb](https://www.oscs1024.com/hd/MPS-a2tx-d4fb)|CVE-2023-3635|高危|
|snappy-java 的 compress 方法整数溢出漏洞导致拒绝服务|整数溢出或环绕|[MPS-angp-mxl2](https://www.oscs1024.com/hd/MPS-angp-mxl2)|CVE-2023-34454|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Snappy 输入验证错误漏洞|不加限制或调节的资源分配|[MPS-tnp7-60hk](https://www.oscs1024.com/hd/MPS-tnp7-60hk)|CVE-2023-34455|高危|
|Apache Helix <1.3.0 远程代码执行漏洞|代码注入|[MPS-up1v-5gme](https://www.oscs1024.com/hd/MPS-up1v-5gme)|CVE-2023-38647|高危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|io.netty:netty|3.10.6.Final||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.91.Final|4.1.94.final|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.eclipse.jetty:jetty-io|9.4.14.v20181114|11.0.10|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|elliptic|6.4.0|6.5.4|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13||间接依赖|建议修复|C:1|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-http|9.4.14.v20181114|11.0.10|间接依赖|建议修复|C:0|H:0|M:1|L:1|
|org.eclipse.jetty.http2:http2-server|9.4.14.v20181114|11.0.10|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.lucene:lucene-queryparser|7.0.1|7.1.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.xerial.snappy:snappy-java|1.1.7.1|1.1.10.1|直接依赖|建议修复|C:0|H:2|M:1|L:0|
|org.yaml:snakeyaml|1.14|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|io.netty:netty|3.6.2.Final|3.10.3.Final|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|com.h2database:h2|1.4.199|2.1.210|直接依赖|建议修复|C:3|H:1|M:0|L:0|
|org.apache.accumulo:accumulo-core|1.7.4|2.1.1|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|set-value|2.0.0|4.0.1|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.springframework:spring-context|4.1.6.RELEASE|5.3.19|间接依赖|建议修复|C:0|H:0|M:1|L:1|
|org.apache.kafka:kafka-clients|2.3.1|3.4.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.webjars:swagger-ui|3.23.11|4.1.3|间接依赖|建议修复|C:0|H:0|M:4|L:0|
|org.springframework.boot:spring-boot|1.2.3.RELEASE|2.2.11.RELEASE|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|commons-beanutils:commons-beanutils|1.9.3|1.9.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|minimatch|3.0.4|3.0.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.google.oauth-client:google-oauth-client|1.31.2|1.33.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.15|2.0|间接依赖|建议修复|C:0|H:3|M:4|L:1|
|mixin-deep|1.3.1|2.0.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.apache.druid:druid-core|0.19.0|0.23.0|直接依赖|建议修复|C:0|H:3|M:3|L:0|
|minimist|1.2.0|1.2.6|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|path-parse|1.0.5|1.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.10.0|2.14.0-rc1|直接依赖|建议修复|C:0|H:2|M:5|L:0|
|minimist|0.0.8|1.2.6|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|ch.qos.logback:logback-core|1.2.3|1.2.8|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.elasticsearch:elasticsearch|6.0.0|8.2.1|直接依赖|建议修复|C:0|H:3|M:9|L:1|
|lodash|4.17.11|4.17.21|间接依赖|建议修复|C:1|H:4|M:1|L:0|
|com.squareup.okio:okio|1.13.0|3.4.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.commons:commons-compress|1.8.1|1.21|间接依赖|建议修复|C:0|H:4|M:1|L:0|
|org.eclipse.jetty:jetty-server|9.4.14.v20181114|12.0.0.beta0|间接依赖|建议修复|C:0|H:0|M:4|L:1|
|js-yaml|3.12.0|3.13.1|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|commons-beanutils:commons-beanutils|1.7.0|1.9.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.helix:helix-core|1.0.4|1.3.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|y18n|4.0.0|5.0.5|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.xerial.snappy:snappy-java|1.1.1.7|1.1.10.1|直接依赖|建议修复|C:0|H:2|M:1|L:0|
|trim-newlines|2.0.0|4.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|ssri|5.3.0|8.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.xerial.snappy:snappy-java|1.1.2.6|1.1.10.1|直接依赖|建议修复|C:0|H:2|M:1|L:0|
|mysql:mysql-connector-java|5.1.48|8.0.28|直接依赖|建议修复|C:0|H:1|M:3|L:0|
|org.glassfish.jersey.media:jersey-media-jaxb|2.26|2.31|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.mozilla:rhino|1.7.11|1.7.12|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|ini|1.3.5|1.3.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|ua-parser-js|0.7.18|1.0.33|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|com.google.protobuf:protobuf-java|3.14.0|3.21.7|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|org.springframework:spring-web|4.1.6.RELEASE|6.0.0|间接依赖|建议修复|C:2|H:0|M:2|L:0|
|net.minidev:json-smart|2.4.7|2.4.9|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|glob-parent|3.1.0|6.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.yaml:snakeyaml|1.30|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|com.jcraft:jsch|0.1.52|0.1.54|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.10.2|2.14.0-rc1|直接依赖|建议修复|C:0|H:2|M:5|L:0|
|org.apache.parquet:parquet-format-structures|1.12.0|1.12.2|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.google.oauth-client:google-oauth-client|1.27.0|1.33.3|间接依赖|建议修复|C:1|H:1|M:0|L:0|
|io.netty:netty-handler|4.1.92.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|json5|0.5.1|2.2.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tar|4.4.4|6.1.9|间接依赖|建议修复|C:0|H:5|M:0|L:1|
|acorn|5.7.1|7.1.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|serialize-javascript|1.5.0|3.1.0|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|decode-uri-component|0.2.0|0.2.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.postgresql:postgresql|9.3-1102-jdbc41|42.5.1|直接依赖|建议修复|C:0|H:2|M:0|L:0|
|lodash|4.17.10|4.17.21|间接依赖|建议修复|C:1|H:4|M:3|L:0|
|org.freemarker:freemarker|2.3.22|2.3.30|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-beans|4.1.6.RELEASE|5.3.20|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|dot-prop|4.2.0|5.1.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.commons:commons-compress|1.19|1.21|直接依赖|建议修复|C:0|H:4|M:0|L:0|
|org.codehaus.plexus:plexus-utils|2.0.6|3.0.24|间接依赖|建议修复|C:1|H:0|M:1|L:1|
|loader-utils|1.1.0|3.2.1|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|org.apache.commons:commons-compress|1.18|1.21|间接依赖|建议修复|C:0|H:5|M:0|L:0|
|needle|2.2.1|3.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-expression|4.1.6.RELEASE|6.0.8|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|org.apache.httpcomponents:httpclient|4.5.5|4.5.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|chownr|1.0.1|1.1.0|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|d3-color|1.0.3|3.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|ajv|6.5.2|6.12.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|d3-color|1.2.3|3.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.ning:async-http-client|1.6.5|1.9.0|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.springframework.boot:spring-boot-autoconfigure|1.2.3.RELEASE|3.0.7|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.testng:testng|7.5|7.7.0|直接依赖|可选修复|C:0|H:1|M:0|L:0|
|hosted-git-info|2.7.1|3.0.8|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|react-dom|16.4.1|16.4.2|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.hibernate:hibernate-validator|5.1.3.Final|6.1.3.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|commons-net:commons-net|3.6|3.9.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-io:commons-io|2.4|2.7|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|kind-of|6.0.2|6.0.3|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.hibernate:hibernate-validator|5.2.5.Final|6.1.3.Final|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.code.gson:gson|2.8.6|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|node-fetch|1.7.3|3.2.10|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|yargs-parser|10.1.0|18.1.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.commons:commons-dbcp2|2.6.0|2.9.0|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|got|6.7.1|12.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.thrift:libthrift|0.9.3|0.12.0|直接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.httpcomponents:httpclient|4.5.2|4.5.13|直接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.apache.commons:commons-dbcp2|2.1|2.9.0|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|commons-httpclient:commons-httpclient|3.1||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|26.0-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:1|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.8.6|2.12.1|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|semver|5.5.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-core|4.1.6.RELEASE|6.0.7|间接依赖|可选修复|C:0|H:0|M:2|L:1|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|515|Low|
|Apache-2.0|589|Low|
|ISC|64|Low|
|自定义许可证|59|Low|
|BSD-3-Clause|86|Low|
|CDDL-1.1|10|Low|
|EPL-1.0|12|Low|
|LGPL-2.1|4|Medium|
|CC-BY-4.0|1|Low|
|BSD-2-Clause|14|Low|
|EPL-2.0|9|Low|
|CC0-1.0|1|Low|
|CC-BY-3.0|1|Low|
|LGPL-2.1-or-later|1|Low|
|WTFPL|1|Low|
|BSD|2|Low|
|MIT-0|1|Low|
|MPL-2.0|1|Low|
|JSON|1|Low|
|MPL-1.1|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|base|0.11.2|间接依赖|npm|
|org.iq80.snappy:snappy|0.2|间接依赖|maven|
|inherits|2.0.1|间接依赖|npm|
|com.google.api:gax-httpjson|0.77.1|间接依赖|maven|
|d3-fetch|1.1.2|间接依赖|npm|
|babel-plugin-syntax-jsx|6.18.0|间接依赖|npm|
|org.codehaus.plexus:plexus-container-default|1.5.5|间接依赖|maven|
|com.facebook.airlift:jmx-http|0.207|直接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.10.0|直接依赖|maven|
|minimist-options|3.0.2|间接依赖|npm|
|com.google.protobuf:protobuf-java|3.21.7|直接依赖|maven|
|com.google.api.grpc:proto-google-cloud-bigquerystorage-v1|1.8.0|间接依赖|maven|
|@webassemblyjs/wasm-gen|1.5.13|间接依赖|npm|
|com.sun.xml.fastinfoset:FastInfoset|1.2.15|间接依赖|maven|
|nan|2.10.0|间接依赖|npm|
|org.apache.calcite:calcite-linq4j|1.32.0|间接依赖|maven|
|ch.qos.reload4j:reload4j|1.2.18.3|直接依赖|maven|
|org.apache.lucene:lucene-queryparser|7.0.1|间接依赖|maven|
|org.sonatype.plexus:plexus-cipher|1.7|间接依赖|maven|
|org.glassfish.jersey.core:jersey-common|2.26|间接依赖|maven|
|org.apache.lucene:lucene-queries|8.2.0|间接依赖|maven|
|com.google.http-client:google-http-client-gson|1.41.7|间接依赖|maven|
|remove-trailing-separator|1.1.0|间接依赖|npm|
|com.google.errorprone:error_prone_annotations|2.11.0|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.14.v20181114|间接依赖|maven|
|onetime|2.0.1|间接依赖|npm|
|org.apache.httpcomponents.client5:httpclient5|5.2.1|间接依赖|maven|
|ajv-keywords|3.2.0|间接依赖|npm|
|org.apache.logging.log4j:log4j-api|2.17.1|直接依赖|maven|
|package-json|4.0.1|间接依赖|npm|
|io.netty:netty-transport-native-unix-common|4.1.91.Final|间接依赖|maven|
|org.apache.lucene:lucene-spatial3d|7.0.1|间接依赖|maven|
|events|1.1.1|间接依赖|npm|
|regjsgen|0.2.0|间接依赖|npm|
|minipass|2.3.3|间接依赖|npm|
|org.apache.commons:commons-text|1.10.0|直接依赖|maven|
|decode-uri-component|0.2.0|间接依赖|npm|
|d3-transition|1.1.3|间接依赖|npm|
|node-fetch|1.7.3|间接依赖|npm|
|d3-time-format|2.1.3|间接依赖|npm|
|arr-diff|4.0.0|间接依赖|npm|
|strip-bom|3.0.0|间接依赖|npm|
|org.apache.httpcomponents:httpcore|4.4.14|间接依赖|maven|
|detect-libc|1.0.3|间接依赖|npm|
|is-directory|0.3.1|间接依赖|npm|
|org.apache.httpcomponents:httpmime|4.5.2|间接依赖|maven|
|org.apache.calcite.avatica:avatica-core|1.22.0|间接依赖|maven|
|des.js|1.0.0|间接依赖|npm|
|com.facebook.presto:presto-i18n-functions|0.284-SNAPSHOT|直接依赖|maven|
|net.sf.jopt-simple:jopt-simple|4.6|间接依赖|maven|
|d3-voronoi|1.1.2|间接依赖|npm|
|net.sf.jopt-simple:jopt-simple|5.0.2|间接依赖|maven|
|org.sonatype.aether:aether-connector-file|1.13.1|间接依赖|maven|
|com.mchange:c3p0|0.9.5.4|间接依赖|maven|
|d3-polygon|1.0.5|间接依赖|npm|
|debug|3.1.0|间接依赖|npm|
|through2|2.0.3|间接依赖|npm|
|regex-not|1.0.2|间接依赖|npm|
|io.opentelemetry:opentelemetry-exporter-otlp|1.19.0|直接依赖|maven|
|com.facebook.presto:presto-analyzer|0.284-SNAPSHOT|直接依赖|maven|
|flush-write-stream|1.0.3|间接依赖|npm|
|babel-helper-builder-binary-assignment-operator-visitor|6.24.1|间接依赖|npm|
|sha.js|2.4.11|间接依赖|npm|
|org.apache.commons:commons-dbcp2|2.6.0|间接依赖|maven|
|com.esri.geometry:esri-geometry-api|2.2.4|直接依赖|maven|
|org.checkerframework:checker-qual|3.37.0|间接依赖|maven|
|util|0.10.4|间接依赖|npm|
|d3-random|1.1.2|间接依赖|npm|
|org.springframework.boot:spring-boot-starter|1.2.3.RELEASE|间接依赖|maven|
|babel-plugin-transform-es2015-sticky-regex|6.24.1|间接依赖|npm|
|rw|1.3.3|间接依赖|npm|
|org.apache.logging.log4j:log4j-slf4j-impl|2.17.1|间接依赖|maven|
|atob|2.1.1|间接依赖|npm|
|source-map|0.5.7|间接依赖|npm|
|tty-browserify|0.0.0|间接依赖|npm|
|is-extendable|0.1.1|间接依赖|npm|
|com.fasterxml:classmate|1.0.0|间接依赖|maven|
|d3-dispatch|1.0.3|间接依赖|npm|
|babel-plugin-transform-es2015-computed-properties|6.24.1|间接依赖|npm|
|com.google.oauth-client:google-oauth-client|1.27.0|间接依赖|maven|
|io.netty:netty-handler|4.1.92.Final|间接依赖|maven|
|defaults|1.0.3|间接依赖|npm|
|binary-extensions|1.11.0|间接依赖|npm|
|org.elasticsearch.plugin:parent-join-client|6.0.0|间接依赖|maven|
|babel-helper-get-function-arity|6.24.1|间接依赖|npm|
|org.apache.maven:maven-compat|3.0.4|间接依赖|maven|
|is-descriptor|0.1.6|间接依赖|npm|
|org.apache.kudu:kudu-client|1.12.0|直接依赖|maven|
|com.google.inject.extensions:guice-multibindings|4.2.2|间接依赖|maven|
|cache-base|1.0.1|间接依赖|npm|
|org.eclipse.jetty.http2:http2-hpack|9.4.14.v20181114|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.4.0|间接依赖|maven|
|decamelize|2.0.0|间接依赖|npm|
|error-ex|1.3.2|间接依赖|npm|
|org.apache.hudi:hudi-presto-bundle|0.13.1|直接依赖|maven|
|duplexify|3.6.0|间接依赖|npm|
|org.codehaus.mojo:animal-sniffer-annotations|1.14|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jsr310|2.10.0|直接依赖|maven|
|d3-hierarchy|1.1.5|间接依赖|npm|
|d3-shape|1.2.2|间接依赖|npm|
|evp_bytestokey|1.0.3|间接依赖|npm|
|indexof|0.0.1|间接依赖|npm|
|com.fasterxml:classmate|1.1.0|间接依赖|maven|
|next-tick|1.0.0|间接依赖|npm|
|org.hamcrest:hamcrest-core|1.3|间接依赖|maven|
|org.testcontainers:testcontainers|1.18.3|直接依赖|maven|
|caniuse-lite|1.0.30000865|间接依赖|npm|
|babel-plugin-transform-es2015-literals|6.22.0|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|org.conscrypt:conscrypt-openjdk-uber|2.5.1|间接依赖|maven|
|unzip-response|2.0.1|间接依赖|npm|
|org.apache.maven:maven-settings|3.0.4|间接依赖|maven|
|d|1.0.0|间接依赖|npm|
|globals|9.18.0|间接依赖|npm|
|io.opentelemetry:opentelemetry-sdk-metrics|1.19.0|间接依赖|maven|
|url-parse-lax|1.0.0|间接依赖|npm|
|org.mongodb:mongo-java-driver|3.6.0|直接依赖|maven|
|io.airlift:airline|0.8|直接依赖|maven|
|org.xerial.larray:larray-buffer|0.4.1|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-guava|2.10.0|间接依赖|maven|
|d3-timer|1.0.7|间接依赖|npm|
|org.apache.kafka:kafka_2.12|2.3.1|直接依赖|maven|
|path-exists|3.0.0|间接依赖|npm|
|com.facebook.presto:presto-matching|0.284-SNAPSHOT|直接依赖|maven|
|babel-plugin-transform-react-jsx-self|6.22.0|间接依赖|npm|
|org.scala-lang:scala-reflect|2.12.8|间接依赖|maven|
|constants-browserify|1.0.0|间接依赖|npm|
|org.apache.commons:commons-math|2.1|间接依赖|maven|
|cross-spawn|5.1.0|间接依赖|npm|
|org.apache.commons:commons-compress|1.19|直接依赖|maven|
|org.hyperic:sigar|1.6.5.132|间接依赖|maven|
|imurmurhash|0.1.4|间接依赖|npm|
|d3-hierarchy|1.1.8|间接依赖|npm|
|randombytes|2.0.6|间接依赖|npm|
|io.grpc:grpc-grpclb|1.34.1|间接依赖|maven|
|d3-queue|3.0.7|间接依赖|npm|
|randomfill|1.0.4|间接依赖|npm|
|com.facebook.presto:presto-password-authenticators|0.284-SNAPSHOT|直接依赖|maven|
|commons-configuration:commons-configuration|1.10|间接依赖|maven|
|currently-unhandled|0.4.1|间接依赖|npm|
|com.facebook.thirdparty:libsvm|3.18.1|直接依赖|maven|
|org.apache.lucene:lucene-spatial|7.0.1|间接依赖|maven|
|io.grpc:grpc-alts|1.35.0|间接依赖|maven|
|org.eclipse.jetty.http2:http2-http-client-transport|9.4.14.v20181114|间接依赖|maven|
|assign-symbols|1.0.0|间接依赖|npm|
|browserify-cipher|1.0.1|间接依赖|npm|
|builtin-status-codes|3.0.0|间接依赖|npm|
|io.netty:netty-transport|4.1.91.Final|直接依赖|maven|
|core-js|1.2.7|间接依赖|npm|
|commons-digester:commons-digester|1.8|间接依赖|maven|
|com.facebook.presto:presto-benchmark-driver|0.284-SNAPSHOT|直接依赖|maven|
|org.apache.commons:commons-pool2|2.0|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.1.3|间接依赖|maven|
|pako|1.0.6|间接依赖|npm|
|org.apache.logging.log4j:log4j-core|2.17.1|直接依赖|maven|
|org.fusesource.jansi:jansi|1.18|直接依赖|maven|
|org.apache.ratis:ratis-proto|2.2.0|间接依赖|maven|
|browserify-des|1.0.2|间接依赖|npm|
|@webassemblyjs/helper-code-frame|1.5.13|间接依赖|npm|
|map-cache|0.2.2|间接依赖|npm|
|d3-polygon|1.0.3|间接依赖|npm|
|org.elasticsearch:securesm|1.1|间接依赖|maven|
|stream-browserify|2.0.1|间接依赖|npm|
|get-stream|3.0.0|间接依赖|npm|
|supports-color|2.0.0|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|fast-json-stable-stringify|2.0.0|间接依赖|npm|
|collection-visit|1.0.0|间接依赖|npm|
|cli-cursor|2.1.0|间接依赖|npm|
|org.tukaani:xz|1.8|间接依赖|maven|
|d3-shape|1.2.0|间接依赖|npm|
|io.airlift:aircompressor|0.15|直接依赖|maven|
|array-unique|0.3.2|间接依赖|npm|
|osenv|0.1.5|间接依赖|npm|
|setimmediate|1.0.5|间接依赖|npm|
|d3-selection|1.3.0|间接依赖|npm|
|org.scala-lang:scala-library|2.12.2|直接依赖|maven|
|org.checkerframework:checker-compat-qual|2.5.5|间接依赖|maven|
|com.github.luben:zstd-jni|1.5.2-2|直接依赖|maven|
|org.eclipse.jetty:jetty-alpn-client|9.4.14.v20181114|间接依赖|maven|
|is-obj|1.0.1|间接依赖|npm|
|component-emitter|1.2.1|间接依赖|npm|
|babel-plugin-syntax-flow|6.18.0|间接依赖|npm|
|com.squareup.okhttp3:okhttp-urlconnection|3.9.0|直接依赖|maven|
|pseudomap|1.0.2|间接依赖|npm|
|spdx-expression-parse|3.0.0|间接依赖|npm|
|uri-js|4.2.2|间接依赖|npm|
|com.fasterxml.jackson.core:jackson-core|2.10.2|直接依赖|maven|
|org.apache.bval:bval-jsr|2.0.0|间接依赖|maven|
|got|6.7.1|间接依赖|npm|
|net.hydromatic:aggdesigner-algorithm|6.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.10.2|直接依赖|maven|
|javax.el:javax.el-api|3.0.0|间接依赖|maven|
|chrome-trace-event|1.0.0|间接依赖|npm|
|io.opentelemetry:opentelemetry-extension-trace-propagators|1.19.0|直接依赖|maven|
|io.prestodb.tempto:tempto-kafka|1.53|直接依赖|maven|
|org.codehaus.plexus:plexus-utils|2.0.6|间接依赖|maven|
|org.apache.commons:commons-lang3|3.3.2|间接依赖|maven|
|util-deprecate|1.0.2|间接依赖|npm|
|merge-options|1.0.1|间接依赖|npm|
|org.freemarker:freemarker|2.3.22|间接依赖|maven|
|domain-browser|1.2.0|间接依赖|npm|
|org.glassfish.jaxb:jaxb-runtime|2.3.1|直接依赖|maven|
|emojis-list|2.1.0|间接依赖|npm|
|com.fasterxml.jackson.module:jackson-module-afterburner|2.10.0|直接依赖|maven|
|ansi-regex|3.0.0|间接依赖|npm|
|com.google.oauth-client:google-oauth-client|1.33.3|直接依赖|maven|
|is-stream|1.1.0|间接依赖|npm|
|slash|1.0.0|间接依赖|npm|
|com.facebook.presto:presto-function-namespace-managers|0.284-SNAPSHOT|直接依赖|maven|
|loglevelnext|1.0.5|间接依赖|npm|
|org.slf4j:slf4j-jdk14|1.7.32|间接依赖|maven|
|xregexp|4.0.0|间接依赖|npm|
|org.ehcache:sizeof|0.4.3|直接依赖|maven|
|minipass|2.9.0|间接依赖|npm|
|com.facebook.presto:presto-jdbc|0.284-SNAPSHOT|直接依赖|maven|
|org.apache.commons:commons-compress|1.21|间接依赖|maven|
|d3-scale|2.1.2|间接依赖|npm|
|org.apache.helix:helix-common|1.0.4|间接依赖|maven|
|arrow|1.0.0|间接依赖||
|net.sf.opencsv:opencsv|2.3|直接依赖|maven|
|org.springframework:spring-jdbc|4.1.6.RELEASE|间接依赖|maven|
|jline:jline|2.14.6|直接依赖|maven|
|com.facebook.presto:presto-parser|0.284-SNAPSHOT|直接依赖|maven|
|org.apache.helix:metadata-store-directory-common|1.0.4|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.3|间接依赖|maven|
|org.glassfish.hk2:hk2-locator|2.6.1|间接依赖|maven|
|com.tdunning:t-digest|3.0|间接依赖|maven|
|is-arrayish|0.2.1|间接依赖|npm|
|com.google.auto.value:auto-value-annotations|1.6.3|间接依赖|maven|
|ms|2.0.0|间接依赖|npm|
|is-windows|1.0.2|间接依赖|npm|
|org.eclipse.jetty.http2:http2-client|9.4.14.v20181114|间接依赖|maven|
|com.facebook.presto:presto-rcfile|0.284-SNAPSHOT|直接依赖|maven|
|babel-plugin-transform-es2015-function-name|6.24.1|间接依赖|npm|
|isobject|3.0.1|间接依赖|npm|
|net.bytebuddy:byte-buddy|0.7-rc2|间接依赖|maven|
|babel-traverse|6.26.0|间接依赖|npm|
|com.google.api.grpc:proto-google-iam-v1|1.0.3|间接依赖|maven|
|org.apache.lucene:lucene-sandbox|8.2.0|间接依赖|maven|
|has-symbols|1.0.0|间接依赖|npm|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|acorn-dynamic-import|3.0.0|间接依赖|npm|
|com.facebook.presto:presto-thrift-connector|0.284-SNAPSHOT|直接依赖|maven|
|org.glassfish.hk2:hk2-api|2.6.1|间接依赖|maven|
|com.oracle.ojdbc:oraclepki|19.3.0.0|间接依赖|maven|
|com.amazonaws:aws-java-sdk-core|1.12.261|直接依赖|maven|
|babel-generator|6.26.1|间接依赖|npm|
|is-wsl|1.1.0|间接依赖|npm|
|com.google.http-client:google-http-client-apache-v2|1.38.0|间接依赖|maven|
|org.eclipse.jetty:jetty-alpn-java-client|9.4.14.v20181114|间接依赖|maven|
|com.microsoft.sqlserver:mssql-jdbc|7.0.0.jre8|直接依赖|maven|
|repeating|2.0.1|间接依赖|npm|
|com.amazonaws:aws-java-sdk-kms|1.12.261|间接依赖|maven|
|npm-bundled|1.0.3|间接依赖|npm|
|d3-format|1.2.2|间接依赖|npm|
|com.google.http-client:google-http-client-appengine|1.38.1|间接依赖|maven|
|com.facebook.airlift:event|0.207|直接依赖|maven|
|resolve-cwd|2.0.0|间接依赖|npm|
|read-pkg|3.0.0|间接依赖|npm|
|querystring-es3|0.2.1|间接依赖|npm|
|org.apache.ratis:ratis-server-api|2.2.0|直接依赖|maven|
|com.facebook.presto:presto-testing-docker|0.284-SNAPSHOT|直接依赖|maven|
|object.values|1.0.4|间接依赖|npm|
|io.delta:delta-standalone_2.12|0.6.0|直接依赖|maven|
|source-map-resolve|0.5.2|间接依赖|npm|
|import-lazy|2.1.0|间接依赖|npm|
|com.esotericsoftware:kryo-shaded|4.0.2|间接依赖|maven|
|org.sonatype.aether:aether-api|1.13.1|直接依赖|maven|
|errno|0.1.7|间接依赖|npm|
|io.jsonwebtoken:jjwt|0.9.0|直接依赖|maven|
|@webassemblyjs/floating-point-hex-parser|1.5.13|间接依赖|npm|
|@webassemblyjs/utf8|1.5.13|间接依赖|npm|
|org.apache.commons:commons-math3|3.6.1|直接依赖|maven|
|io.airlift.resolver:resolver|1.4|直接依赖|maven|
|com.facebook.presto:presto-node-ttl-fetchers|0.284-SNAPSHOT|直接依赖|maven|
|latest-version|3.1.0|间接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|commons-cli:commons-cli|1.2|间接依赖|maven|
|net.jodah:failsafe|2.0.1|直接依赖|maven|
|worker-farm|1.6.0|间接依赖|npm|
|org.apache.lucene:lucene-join|7.0.1|间接依赖|maven|
|meant|1.0.1|间接依赖|npm|
|arrify|1.0.1|间接依赖|npm|
|com.ibm.icu:icu4j|55.1|间接依赖|maven|
|d3-brush|1.0.4|间接依赖|npm|
|uuid|3.3.2|间接依赖|npm|
|com.facebook.presto:presto-iceberg|0.284-SNAPSHOT|直接依赖|maven|
|org.apache.curator:curator-client|2.12.0|直接依赖|maven|
|snapdragon-util|3.0.1|间接依赖|npm|
|org.eclipse.jetty:jetty-http|9.4.14.v20181114|间接依赖|maven|
|org.apache.calcite.avatica:avatica-metrics|1.22.0|间接依赖|maven|
|babel-plugin-transform-es2015-parameters|6.24.1|间接依赖|npm|
|ora|2.1.0|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|com.jcraft:jsch|0.1.52|间接依赖|maven|
|is-extglob|2.1.1|间接依赖|npm|
|org.javolution:javolution|5.2.3|间接依赖|maven|
|com.google.oauth-client:google-oauth-client|1.31.2|间接依赖|maven|
|resolve-url|0.2.1|间接依赖|npm|
|com.google.uzaygezen:uzaygezen-core|0.2|间接依赖|maven|
|spdx-license-ids|3.0.0|间接依赖|npm|
|com.facebook.presto.hive:hive-apache|3.0.0-8|直接依赖|maven|
|delegates|1.0.0|间接依赖|npm|
|safe-buffer|5.2.1|间接依赖|npm|
|@webassemblyjs/ast|1.5.13|间接依赖|npm|
|is-data-descriptor|1.0.0|间接依赖|npm|
|com.google.j2objc:j2objc-annotations|1.1|间接依赖|maven|
|d3-dsv|1.0.10|间接依赖|npm|
|org.roaringbitmap:shims|0.9.3|间接依赖|maven|
|browserify-zlib|0.2.0|间接依赖|npm|
|org.xerial.snappy:snappy-java|1.1.7.1|直接依赖|maven|
|once|1.4.0|间接依赖|npm|
|balanced-match|1.0.0|间接依赖|npm|
|io.netty:netty-transport|4.1.92.Final|间接依赖|maven|
|com.google.http-client:google-http-client-apache-v2|1.38.1|间接依赖|maven|
|org.openjdk.jol:jol-core|0.2|直接依赖|maven|
|source-list-map|2.0.0|间接依赖|npm|
|color-name|1.1.1|间接依赖|npm|
|minizlib|1.3.3|间接依赖|npm|
|com.fasterxml.jackson.dataformat:jackson-dataformat-csv|2.10.0|间接依赖|maven|
|tslib|1.9.3|间接依赖|npm|
|org.apache.maven:maven-settings-builder|3.0.4|间接依赖|maven|
|to-fast-properties|1.0.3|间接依赖|npm|
|com.facebook.presto:presto-proxy|0.284-SNAPSHOT|直接依赖|maven|
|schema-utils|0.4.5|间接依赖|npm|
|es6-iterator|2.0.3|间接依赖|npm|
|crypto-random-string|1.0.0|间接依赖|npm|
|wcwidth|1.0.1|间接依赖|npm|
|widest-line|2.0.0|间接依赖|npm|
|is-regex|1.0.4|间接依赖|npm|
|net.minidev:json-smart|2.4.7|间接依赖|maven|
|org.apache.lucene:lucene-queries|7.0.1|间接依赖|maven|
|babel-helper-function-name|6.24.1|间接依赖|npm|
|com.google.api.grpc:proto-google-cloud-bigquerystorage-v1beta1|0.108.0|直接依赖|maven|
|https-browserify|1.0.0|间接依赖|npm|
|com.yammer.metrics:metrics-core|2.2.0|间接依赖|maven|
|d3-interpolate|1.3.2|间接依赖|npm|
|source-map|0.6.1|间接依赖|npm|
|d3-array|1.2.1|间接依赖|npm|
|io.opencensus:opencensus-contrib-http-util|0.24.0|间接依赖|maven|
|minimist|0.0.8|间接依赖|npm|
|clone|1.0.4|间接依赖|npm|
|com.facebook.drift:drift-transport-netty|1.36|直接依赖|maven|
|org.apache.lucene:lucene-suggest|7.0.1|间接依赖|maven|
|com.facebook.presto:presto-spark-base|0.284-SNAPSHOT|直接依赖|maven|
|d3|4.13.0|间接依赖|npm|
|minimist|1.2.6|间接依赖|npm|
|org.yaml:snakeyaml|1.30|间接依赖|maven|
|com.facebook.airlift:configuration|0.207|直接依赖|maven|
|regexpu-core|2.0.0|间接依赖|npm|
|org.apache.parquet:parquet-column|1.12.0|直接依赖|maven|
|com.facebook.presto:presto-mongodb|0.284-SNAPSHOT|直接依赖|maven|
|node-pre-gyp|0.10.3|间接依赖|npm|
|abbrev|1.1.1|间接依赖|npm|
|com.facebook.presto.hadoop:hadoop-apache2|2.7.4-9|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.8.6|间接依赖|maven|
|create-hmac|1.1.7|间接依赖|npm|
|org.apache.pinot:pinot-segment-local-jdk8|0.11.0|间接依赖|maven|
|@webassemblyjs/ieee754|1.5.13|间接依赖|npm|
|babel-helper-call-delegate|6.24.1|间接依赖|npm|
|is-fullwidth-code-point|1.0.0|间接依赖|npm|
|com.google.api:gax-httpjson|0.77.0|间接依赖|maven|
|is-path-inside|1.0.1|间接依赖|npm|
|com.chuusai:shapeless_2.12|2.3.4|间接依赖|maven|
|com.zaxxer:HikariCP-java7|2.4.13|间接依赖|maven|
|opn|5.3.0|间接依赖|npm|
|org.elasticsearch.client:elasticsearch-rest-client|6.0.0|直接依赖|maven|
|has-value|1.0.0|间接依赖|npm|
|execa|0.7.0|间接依赖|npm|
|is-date-object|1.0.1|间接依赖|npm|
|com.squareup.okhttp3:okhttp|3.9.0|直接依赖|maven|
|d3-time|1.0.10|间接依赖|npm|
|org.codehaus.jackson:jackson-mapper-asl|1.9.13|间接依赖|maven|
|io.netty:netty-codec-http|4.1.92.Final|间接依赖|maven|
|io.grpc:grpc-protobuf|1.35.0|直接依赖|maven|
|dagre-d3|0.6.1|直接依赖|npm|
|uglify-es|3.3.9|间接依赖|npm|
|semver|5.5.0|间接依赖|npm|
|com.facebook.presto:presto-jmx|0.284-SNAPSHOT|直接依赖|maven|
|com.facebook.presto:presto-hive-function-namespace|0.284-SNAPSHOT|直接依赖|maven|
|org.apache.pinot:pinot-common-jdk8|0.11.0|间接依赖|maven|
|create-ecdh|4.0.3|间接依赖|npm|
|io.netty:netty-common|4.1.92.Final|间接依赖|maven|
|cli-boxes|1.0.0|间接依赖|npm|
|supports-color|5.4.0|间接依赖|npm|
|chownr|1.1.4|间接依赖|npm|
|com.facebook.airlift.discovery:discovery-server|1.33|直接依赖|maven|
|software.amazon.ion:ion-java|1.0.2|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|4.1.14|间接依赖|maven|
|org.apache.httpcomponents:httpcore-nio|4.4.5|直接依赖|maven|
|org.apache.helix:metrics-common|1.0.4|间接依赖|maven|
|split-string|3.1.0|间接依赖|npm|
|extglob|2.0.4|间接依赖|npm|
|d3-random|1.1.0|间接依赖|npm|
|org.eclipse.jetty:jetty-jmx|9.4.14.v20181114|间接依赖|maven|
|babel-loader|7.1.5|直接依赖|npm|
|io.opentelemetry:opentelemetry-sdk|1.19.0|直接依赖|maven|
|org.elasticsearch.plugin:aggs-matrix-stats-client|6.0.0|间接依赖|maven|
|es5-ext|0.10.45|间接依赖|npm|
|com.facebook.presto:presto-bigquery|0.284-SNAPSHOT|直接依赖|maven|
|commons-configuration:commons-configuration|1.6|间接依赖|maven|
|braces|2.3.2|间接依赖|npm|
|com.facebook.presto:presto-tpch|0.284-SNAPSHOT|直接依赖|maven|
|org.apache.datasketches:datasketches-memory|1.2.0-incubating|间接依赖|maven|
|d3-format|1.3.2|间接依赖|npm|
|babel-plugin-transform-es2015-typeof-symbol|6.23.0|间接依赖|npm|
|org.ow2.asm:asm-tree|9.0|直接依赖|maven|
|org.apache.parquet:parquet-format-structures|1.12.0|直接依赖|maven|
|org.antlr:antlr-runtime|3.4|间接依赖|maven|
|sphinx|4.4.0|间接依赖|pip|
|extend-shallow|2.0.1|间接依赖|npm|
|snapdragon|0.8.2|间接依赖|npm|
|unset-value|1.0.0|间接依赖|npm|
|base64-js|1.3.0|间接依赖|npm|
|com.facebook.presto:presto-spi|0.284-SNAPSHOT|直接依赖|maven|
|npm-run-path|2.0.2|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|com.facebook.presto.cassandra:cassandra-driver|3.6.0-1|直接依赖|maven|
|org.apache.yetus:audience-annotations|0.5.0|间接依赖|maven|
|com.google.flogger:flogger|0.3.1|间接依赖|maven|
|org.apache.tomcat:tomcat-juli|8.0.20|间接依赖|maven|
|babel-plugin-transform-es2015-destructuring|6.23.0|间接依赖|npm|
|org.apache.helix:zookeeper-api|1.0.4|间接依赖|maven|
|y18n|4.0.0|间接依赖|npm|
|babel-plugin-transform-es2015-modules-amd|6.24.1|间接依赖|npm|
|timed-out|4.0.1|间接依赖|npm|
|com.facebook.presto:presto-blackhole|0.284-SNAPSHOT|直接依赖|maven|
|process|0.11.10|间接依赖|npm|
|mamacro|0.0.3|间接依赖|npm|
|com.facebook.airlift:jmx-http-rpc|0.198|间接依赖|maven|
|invariant|2.2.4|间接依赖|npm|
|fill-range|4.0.0|间接依赖|npm|
|babel-helper-regex|6.26.0|间接依赖|npm|
|org.glassfish.jersey.containers:jersey-container-grizzly2-http|2.35|间接依赖|maven|
|org.postgresql:postgresql|9.3-1102-jdbc41|直接依赖|maven|
|find-up|2.1.0|间接依赖|npm|
|punycode|2.1.1|间接依赖|npm|
|javax.xml.bind:jaxb-api|2.3.1|直接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.92.Final|间接依赖|maven|
|org.projectnessie.nessie:nessie-client|0.59.0|直接依赖|maven|
|js-tokens|3.0.2|间接依赖|npm|
|com.uber:h3|4.0.0|间接依赖|maven|
|io.prestodb.tempto:tempto-ldap|1.53|直接依赖|maven|
|pbkdf2|3.0.16|间接依赖|npm|
|com.facebook.airlift:http-server|0.207|直接依赖|maven|
|text-table|0.2.0|间接依赖|npm|
|commons-io:commons-io|2.11.0|间接依赖|maven|
|path-dirname|1.0.2|间接依赖|npm|
|@webassemblyjs/helper-wasm-bytecode|1.5.13|间接依赖|npm|
|fs-write-stream-atomic|1.0.10|间接依赖|npm|
|com.starburstdata:starburst-spotify-docker-client|8.11.7-0.6|直接依赖|maven|
|expand-brackets|2.1.4|间接依赖|npm|
|com.facebook.presto:presto-spark-launcher|0.284-SNAPSHOT|直接依赖|maven|
|com.ning:compress-lzf|1.0.4|间接依赖|maven|
|javax.validation:validation-api|2.0.1.Final|直接依赖|maven|
|com.facebook.presto:presto-ml|0.284-SNAPSHOT|直接依赖|maven|
|org.eclipse.jetty:jetty-security|9.4.14.v20181114|间接依赖|maven|
|browserify-sign|4.0.4|间接依赖|npm|
|com.squareup.okio:okio|1.13.0|间接依赖|maven|
|d3-geo|1.11.1|间接依赖|npm|
|com.facebook.presto:presto-redis|0.284-SNAPSHOT|直接依赖|maven|
|spdx-exceptions|2.1.0|间接依赖|npm|
|org.glassfish.jersey.core:jersey-server|2.26|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet-core|2.26|间接依赖|maven|
|static-extend|0.1.2|间接依赖|npm|
|nanomatch|1.2.13|间接依赖|npm|
|com.facebook.presto:presto-hive-common|0.284-SNAPSHOT|直接依赖|maven|
|ajv|6.12.6|间接依赖|npm|
|com.oracle.ojdbc:ucp|19.3.0.0|间接依赖|maven|
|org.springframework.boot:spring-boot|1.2.3.RELEASE|间接依赖|maven|
|org.aspectj:aspectjweaver|1.8.6|间接依赖|maven|
|com.google.api-client:google-api-client|1.27.0|直接依赖|maven|
|com.facebook.airlift:jaxrs|0.207|直接依赖|maven|
|is-callable|1.1.4|间接依赖|npm|
|normalize-path|2.1.1|间接依赖|npm|
|es6-symbol|3.1.1|间接依赖|npm|
|babel-helper-hoist-variables|6.24.1|间接依赖|npm|
|browserslist|3.2.8|间接依赖|npm|
|yallist|3.0.2|间接依赖|npm|
|mississippi|2.0.0|间接依赖|npm|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|d3-chord|1.0.4|间接依赖|npm|
|estraverse|4.2.0|间接依赖|npm|
|org.apache.maven:maven-model|3.0.4|间接依赖|maven|
|repeat-string|1.6.1|间接依赖|npm|
|com.facebook.airlift:http-client|0.207|直接依赖|maven|
|org.jvnet.staxex:stax-ex|1.8|间接依赖|maven|
|set-immediate-shim|1.0.1|间接依赖|npm|
|minizlib|1.1.0|间接依赖|npm|
|path-is-inside|1.0.2|间接依赖|npm|
|org.apache.parquet:parquet-encoding|1.12.0|间接依赖|maven|
|org.apache.maven.wagon:wagon-provider-api|2.2|间接依赖|maven|
|esutils|2.0.2|间接依赖|npm|
|d3-transition|1.1.1|间接依赖|npm|
|console-browserify|1.1.0|间接依赖|npm|
|pify|3.0.0|间接依赖|npm|
|org.apache.commons:commons-lang3|3.12.0|间接依赖|maven|
|babel-core|6.26.3|直接依赖|npm|
|org.apache.commons:commons-compress|1.8.1|间接依赖|maven|
|com.facebook.presto:presto-teradata-functions|0.284-SNAPSHOT|直接依赖|maven|
|promise-inflight|1.0.1|间接依赖|npm|
|to-object-path|0.3.0|间接依赖|npm|
|babel-plugin-transform-es2015-for-of|6.23.0|间接依赖|npm|
|titleize|1.0.1|间接依赖|npm|
|org.lz4:lz4-java|1.8.0|间接依赖|maven|
|org.apache.httpcomponents:httpasyncclient|4.1.2|直接依赖|maven|
|org.apache.lucene:lucene-backward-codecs|7.0.1|间接依赖|maven|
|org.projectnessie.nessie:nessie-model|0.59.0|直接依赖|maven|
|is-extendable|1.0.1|间接依赖|npm|
|com.fasterxml.jackson.datatype:jackson-datatype-joda|2.10.0|间接依赖|maven|
|com.facebook.airlift:log|0.207|直接依赖|maven|
|babel-plugin-transform-flow-strip-types|6.22.0|间接依赖|npm|
|org.codehaus.jackson:jackson-core-asl|1.9.13|间接依赖|maven|
|com.larksuite.oapi:larksuite-oapi|1.0.18-rc4|直接依赖|maven|
|import-local|1.0.0|间接依赖|npm|
|tapable|1.0.0|间接依赖|npm|
|org.hibernate:hibernate-validator|5.2.5.Final|间接依赖|maven|
|yallist|2.1.2|间接依赖|npm|
|com.facebook.presto:presto-tests|0.284-SNAPSHOT|直接依赖|maven|
|babel-plugin-transform-es2015-block-scoped-functions|6.22.0|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|d3-brush|1.0.6|间接依赖|npm|
|io.grpc:grpc-api|1.41.0|直接依赖|maven|
|unique-string|1.0.0|间接依赖|npm|
|object.pick|1.3.0|间接依赖|npm|
|org.apache.xbean:xbean-reflect|3.4|间接依赖|maven|
|com.facebook.presto:presto-tpcds|0.284-SNAPSHOT|直接依赖|maven|
|mysql:mysql-connector-java|5.1.48|直接依赖|maven|
|create-hash|1.2.0|间接依赖|npm|
|antlr:antlr|2.7.7|间接依赖|maven|
|punycode|1.3.2|间接依赖|npm|
|cyclist|0.2.2|间接依赖|npm|
|buffer-from|1.1.0|间接依赖|npm|
|org.threeten:threetenbp|1.5.0|间接依赖|maven|
|commons-codec:commons-codec|1.13|间接依赖|maven|
|normalize-package-data|2.4.0|间接依赖|npm|
|core-util-is|1.0.2|间接依赖|npm|
|@webassemblyjs/helper-fsm|1.5.13|间接依赖|npm|
|org.gridkit.lab:jvm-attach-api|1.5|间接依赖|maven|
|io.netty:netty-codec-socks|4.1.92.Final|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|直接依赖|maven|
|org.springframework:spring-context|4.1.6.RELEASE|间接依赖|maven|
|org.eclipse.jetty:jetty-client|9.4.14.v20181114|间接依赖|maven|
|parse-json|4.0.0|间接依赖|npm|
|com.facebook.presto:presto-resource-group-managers|0.284-SNAPSHOT|直接依赖|maven|
|get-value|2.0.6|间接依赖|npm|
|com.oracle.ojdbc:simplefan|19.3.0.0|间接依赖|maven|
|org.jscience:jscience|4.3.1|间接依赖|maven|
|trim-right|1.0.1|间接依赖|npm|
|d3-geo|1.9.1|间接依赖|npm|
|safe-regex|1.1.0|间接依赖|npm|
|com.github.docker-java:docker-java-transport-zerodep|3.3.0|间接依赖|maven|
|org.ow2.asm:asm|9.0|直接依赖|maven|
|class-utils|0.3.6|间接依赖|npm|
|org.apache.iceberg:iceberg-api|1.3.1|直接依赖|maven|
|org.apache.ratis:ratis-client|2.2.0|直接依赖|maven|
|has|1.0.3|间接依赖|npm|
|glob-parent|3.1.0|间接依赖|npm|
|net.jodah:expiringmap|0.5.6|间接依赖|maven|
|prop-types|15.6.2|间接依赖|npm|
|public-encrypt|4.0.2|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|com.facebook.airlift:stats|0.207|直接依赖|maven|
|d3-collection|1.0.4|间接依赖|npm|
|org.apache.avro:avro|1.9.0|直接依赖|maven|
|com.google.cloud:google-cloud-bigquery|1.126.3|直接依赖|maven|
|browserify-rsa|4.0.1|间接依赖|npm|
|com.yahoo.datasketches:sketches-core|0.9.0|间接依赖|maven|
|util|0.10.3|间接依赖|npm|
|strip-json-comments|2.0.1|间接依赖|npm|
|serialize-javascript|1.5.0|间接依赖|npm|
|anymatch|2.0.0|间接依赖|npm|
|global-dirs|0.1.1|间接依赖|npm|
|commondir|1.0.1|间接依赖|npm|
|core-js|2.5.7|间接依赖|npm|
|babel-plugin-check-es2015-constants|6.22.0|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|com.facebook.airlift:bootstrap|0.207|直接依赖|maven|
|org.jdbi:jdbi3-core|3.4.0|直接依赖|maven|
|strip-eof|1.0.0|间接依赖|npm|
|com.facebook.presto:presto-geospatial-toolkit|0.284-SNAPSHOT|直接依赖|maven|
|os-browserify|0.3.0|间接依赖|npm|
|rc|1.2.8|间接依赖|npm|
|org.hdrhistogram:HdrHistogram|2.1.9|间接依赖|maven|
|io.perfmark:perfmark-api|0.23.0|直接依赖|maven|
|is-symbol|1.0.1|间接依赖|npm|
|io.opentelemetry:opentelemetry-api-logs|1.19.0-alpha|间接依赖|maven|
|babel-helpers|6.24.1|间接依赖|npm|
|babel-plugin-transform-es2015-classes|6.24.1|间接依赖|npm|
|org.codehaus.groovy:groovy-all|2.4.21|间接依赖|maven|
|org.apache.datasketches:datasketches-java|1.3.0-incubating|间接依赖|maven|
|chokidar|2.0.4|间接依赖|npm|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|com.google.guava:guava|26.0-jre|直接依赖|maven|
|asn1.js|4.10.1|间接依赖|npm|
|io.netty:netty-buffer|4.1.91.Final|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-jdbc|1.2.3.RELEASE|间接依赖|maven|
|kind-of|3.2.2|间接依赖|npm|
|com.stumbleupon:async|1.4.1|间接依赖|maven|
|com.facebook.presto:presto-parquet|0.284-SNAPSHOT|直接依赖|maven|
|org.apache.iceberg:iceberg-common|1.3.1|间接依赖|maven|
|babel-runtime|6.26.0|间接依赖|npm|
|date-now|0.1.4|间接依赖|npm|
|org.quartz-scheduler:quartz|2.3.2|间接依赖|maven|
|com.google.api:gax-grpc|1.60.1|直接依赖|maven|
|d3-collection|1.0.7|间接依赖|npm|
|io.dropwizard.metrics:metrics-core|3.2.5|间接依赖|maven|
|org.springframework:spring-aop|4.1.6.RELEASE|间接依赖|maven|
|registry-url|3.1.0|间接依赖|npm|
|babel-plugin-transform-strict-mode|6.24.1|间接依赖|npm|
|com.facebook.presto:presto-thrift-spec|0.284-SNAPSHOT|直接依赖|maven|
|org.asynchttpclient:async-http-client-netty-utils|2.5.3|间接依赖|maven|
|org.eclipse.microprofile.openapi:microprofile-openapi-api|3.1|间接依赖|maven|
|com.facebook.presto:presto-benchto-benchmarks|0.284-SNAPSHOT|直接依赖|maven|
|object-keys|1.0.12|间接依赖|npm|
|com.google.code.gson:gson|2.8.6|间接依赖|maven|
|org.apache.pinot:presto-pinot-driver|0.11.0|直接依赖|maven|
|com.yahoo.datasketches:memory|0.9.0|间接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.10.0|间接依赖|maven|
|@webassemblyjs/helper-wasm-section|1.5.13|间接依赖|npm|
|com.google.auth:google-auth-library-credentials|0.22.2|直接依赖|maven|
|com.facebook.presto:presto-elasticsearch|0.284-SNAPSHOT|直接依赖|maven|
|diffie-hellman|5.0.3|间接依赖|npm|
|org.apache.httpcomponents.client5:httpclient5|5.1.3|间接依赖|maven|
|com.google.http-client:google-http-client-jackson2|1.27.0|直接依赖|maven|
|com.google.api.grpc:grpc-google-cloud-bigquerystorage-v1beta1|0.108.0|间接依赖|maven|
|wide-align|1.1.3|间接依赖|npm|
|resolve|1.8.1|间接依赖|npm|
|io.grpc:grpc-context|1.35.0|间接依赖|maven|
|fs-minipass|1.2.5|间接依赖|npm|
|com.facebook.presto:presto-server|0.284-SNAPSHOT|直接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.14.v20181114|间接依赖|maven|
|io.grpc:grpc-core|1.41.0|间接依赖|maven|
|dagre|0.8.2|间接依赖|npm|
|stream-shift|1.0.0|间接依赖|npm|
|io.netty:netty-handler-proxy|4.1.92.Final|间接依赖|maven|
|com.oracle.ojdbc:osdt_core|19.3.0.0|间接依赖|maven|
|resolve-from|3.0.0|间接依赖|npm|
|com.facebook.drift:drift-codec|1.36|直接依赖|maven|
|org.glassfish.jersey.core:jersey-client|2.26|间接依赖|maven|
|punycode|1.4.1|间接依赖|npm|
|babel-plugin-transform-es2015-object-super|6.24.1|间接依赖|npm|
|ret|0.1.15|间接依赖|npm|
|run-queue|1.0.3|间接依赖|npm|
|com.facebook.presto.orc:orc-protobuf|13|直接依赖|maven|
|deep-extend|0.6.0|间接依赖|npm|
|com.facebook.presto:presto-bytecode|0.284-SNAPSHOT|直接依赖|maven|
|d3-path|1.0.5|间接依赖|npm|
|io.opentelemetry:opentelemetry-api|1.19.0|直接依赖|maven|
|d3-dsv|1.0.8|间接依赖|npm|
|org.apache.commons:commons-compress|1.23.0|间接依赖|maven|
|fs-minipass|1.2.7|间接依赖|npm|
|acorn|5.7.1|间接依赖|npm|
|com.google.http-client:google-http-client-appengine|1.38.0|间接依赖|maven|
|pretty-bytes|5.1.0|间接依赖|npm|
|loose-envify|1.4.0|间接依赖|npm|
|com.google.auth:google-auth-library-credentials|0.12.0|间接依赖|maven|
|babylon|6.18.0|间接依赖|npm|
|whatwg-fetch|2.0.4|间接依赖|npm|
|detect-indent|4.0.0|间接依赖|npm|
|convert-source-map|1.5.1|间接依赖|npm|
|decamelize-keys|1.1.0|间接依赖|npm|
|org.apache.kafka:kafka-clients|2.3.1|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-parameter-names|2.10.0|间接依赖|maven|
|org.apache.commons:commons-lang3|3.1|间接依赖|maven|
|org.apache.druid:druid-hll|0.19.0|间接依赖|maven|
|builtin-modules|1.1.1|间接依赖|npm|
|urix|0.1.0|间接依赖|npm|
|org.apache.lucene:lucene-misc|7.0.1|间接依赖|maven|
|webpack-log|1.2.0|间接依赖|npm|
|javax.servlet:javax.servlet-api|3.1.0|直接依赖|maven|
|repeat-element|1.1.2|间接依赖|npm|
|@webassemblyjs/wast-printer|1.5.13|间接依赖|npm|
|use|3.1.1|间接依赖|npm|
|upath|1.1.0|间接依赖|npm|
|locate-path|2.0.0|间接依赖|npm|
|to-regex|3.0.2|间接依赖|npm|
|com.google.apis:google-api-services-bigquery|v2-rev20201030-1.31.0|间接依赖|maven|
|d3-dispatch|1.0.5|间接依赖|npm|
|net.java.dev.jna:jna|5.12.1|间接依赖|maven|
|org.apache.maven:maven-model-builder|3.0.4|间接依赖|maven|
|org.glassfish.grizzly:grizzly-http|2.4.4|间接依赖|maven|
|xdg-basedir|3.0.0|间接依赖|npm|
|@webassemblyjs/wasm-parser|1.5.13|间接依赖|npm|
|org.apache.iceberg:iceberg-nessie|1.3.1|直接依赖|maven|
|com.facebook.presto:presto-testing-server-launcher|0.284-SNAPSHOT|直接依赖|maven|
|regenerator-runtime|0.11.1|间接依赖|npm|
|com.facebook.presto:presto-kudu|0.284-SNAPSHOT|直接依赖|maven|
|@webassemblyjs/helper-buffer|1.5.13|间接依赖|npm|
|javax.ws.rs:javax.ws.rs-api|2.1|直接依赖|maven|
|babel-plugin-transform-react-jsx|6.24.1|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|io.airlift:units|1.3|直接依赖|maven|
|is-data-descriptor|0.1.4|间接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|org.apache.pinot:pinot-core-jdk8|0.11.0|间接依赖|maven|
|com.google.cloud:google-cloud-core|1.94.0|直接依赖|maven|
|ansi-align|2.0.0|间接依赖|npm|
|com.facebook.presto:presto-hive-metastore|0.284-SNAPSHOT|直接依赖|maven|
|nopt|4.0.1|间接依赖|npm|
|org.apache.iceberg:iceberg-parquet|1.3.1|直接依赖|maven|
|javax.inject:javax.inject|1|直接依赖|maven|
|com.google.api.grpc:proto-google-cloud-bigquerystorage-v1beta2|0.108.0|间接依赖|maven|
|com.google.cloud.bigdataoss:gcs-connector|hadoop2-1.9.17|直接依赖|maven|
|object.assign|4.1.0|间接依赖|npm|
|org.jgrapht:jgrapht-core|1.3.1|直接依赖|maven|
|io.netty:netty-resolver|4.1.92.Final|间接依赖|maven|
|at.favre.lib:bcrypt|0.9.0|直接依赖|maven|
|org.apiguardian:apiguardian-api|1.1.2|间接依赖|maven|
|minimalistic-crypto-utils|1.0.1|间接依赖|npm|
|string-width|2.1.1|间接依赖|npm|
|d3-drag|1.2.3|间接依赖|npm|
|io.grpc:grpc-auth|1.35.0|间接依赖|maven|
|org.scala-lang:scala-library|2.12.11|直接依赖|maven|
|com.google.auto.value:auto-value-annotations|1.7.4|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.3|间接依赖|maven|
|org.yaml:snakeyaml|2.0|直接依赖|maven|
|has-flag|3.0.0|间接依赖|npm|
|org.xerial.snappy:snappy-java|1.1.1.7|直接依赖|maven|
|org.glassfish.jaxb:txw2|2.3.1|间接依赖|maven|
|org.antlr:stringtemplate|3.2.1|间接依赖|maven|
|org.springframework:spring-core|4.1.6.RELEASE|间接依赖|maven|
|com.facebook.presto:presto-thrift-testing-server|0.284-SNAPSHOT|直接依赖|maven|
|com.h2database:h2|1.4.199|直接依赖|maven|
|webpack-sources|1.1.0|间接依赖|npm|
|com.facebook.presto:presto-prometheus|0.284-SNAPSHOT|直接依赖|maven|
|code-point-at|1.1.0|间接依赖|npm|
|source-map-support|0.4.18|间接依赖|npm|
|is-npm|1.0.0|间接依赖|npm|
|io.netty:netty-resolver|4.1.91.Final|间接依赖|maven|
|org.webjars:jquery|3.5.1|间接依赖|maven|
|kind-of|6.0.2|间接依赖|npm|
|commons-beanutils:commons-beanutils|1.7.0|间接依赖|maven|
|org.reflections:reflections|0.9.9|直接依赖|maven|
|com.amazonaws:aws-java-sdk-sts|1.12.261|直接依赖|maven|
|at.favre.lib:bytes|1.3.0|间接依赖|maven|
|com.carrotsearch:hppc|0.7.1|间接依赖|maven|
|io.netty:netty-buffer|4.1.92.Final|间接依赖|maven|
|org.testng:testng|7.5|直接依赖|maven|
|regenerator-transform|0.10.1|间接依赖|npm|
|ch.qos.logback:logback-classic|1.2.3|间接依赖|maven|
|com.facebook.airlift:testing|0.207|直接依赖|maven|
|es-abstract|1.12.0|间接依赖|npm|
|load-json-file|4.0.0|间接依赖|npm|
|com.opencsv:opencsv|4.6|间接依赖|maven|
|electron-to-chromium|1.3.52|间接依赖|npm|
|lodash|4.17.10|间接依赖|npm|
|org.glassfish.jersey.inject:jersey-hk2|2.26|间接依赖|maven|
|com.google.flogger:flogger-log4j-backend|0.3.1|间接依赖|maven|
|cglib:cglib-nodep|3.2.5|间接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|直接依赖|maven|
|map-obj|2.0.0|间接依赖|npm|
|node-libs-browser|2.1.0|间接依赖|npm|
|configstore|3.1.2|间接依赖|npm|
|com.facebook.presto:presto-thrift-api|0.284-SNAPSHOT|直接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.9.3|间接依赖|maven|
|org.apache.commons:commons-collections4|4.2|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.92.Final|间接依赖|maven|
|com.facebook.presto:presto-delta|0.284-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-smile|2.10.0|间接依赖|maven|
|org.apache.iceberg:iceberg-core|1.3.1|直接依赖|maven|
|path-type|3.0.0|间接依赖|npm|
|ci-info|1.1.3|间接依赖|npm|
|redis.clients:jedis|2.6.2|直接依赖|maven|
|babel-helper-optimise-call-expression|6.24.1|间接依赖|npm|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|is-retry-allowed|1.1.0|间接依赖|npm|
|pascalcase|0.1.1|间接依赖|npm|
|lodash|4.17.11|间接依赖|npm|
|org.lz4:lz4-java|1.6.0|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-common|1.19.0|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-scala_2.12|2.10.0|间接依赖|maven|
|end-of-stream|1.4.1|间接依赖|npm|
|org.apache.lucene:lucene-spatial-extras|7.0.1|间接依赖|maven|
|iferr|0.1.5|间接依赖|npm|
|boxen|1.3.0|间接依赖|npm|
|org.mindrot:jbcrypt|0.4|间接依赖|maven|
|babel-plugin-syntax-exponentiation-operator|6.13.0|间接依赖|npm|
|react-dom|16.4.1|直接依赖|npm|
|fbjs|0.8.17|间接依赖|npm|
|chalk|2.4.1|间接依赖|npm|
|com.google.apis:google-api-services-sheets|v4-rev516-1.23.0|直接依赖|maven|
|it.unimi.dsi:fastutil|8.5.2|直接依赖|maven|
|jsesc|0.5.0|间接依赖|npm|
|org.apache.ratis:ratis-thirdparty-misc|0.7.0|间接依赖|maven|
|org.jetbrains:annotations|19.0.0|直接依赖|maven|
|is-plain-object|2.0.4|间接依赖|npm|
|parse-asn1|5.1.1|间接依赖|npm|
|home-or-tmp|2.0.0|间接依赖|npm|
|glob|7.1.2|间接依赖|npm|
|babel-helper-replace-supers|6.24.1|间接依赖|npm|
|org.apache.helix:helix-core|1.0.4|间接依赖|maven|
|string-width|1.0.2|间接依赖|npm|
|asap|2.0.6|间接依赖|npm|
|org.apache.commons:commons-lang3|3.8|间接依赖|maven|
|d3-interpolate|1.1.6|间接依赖|npm|
|org.apache.logging.log4j:log4j-jul|2.17.1|直接依赖|maven|
|lowercase-keys|1.0.1|间接依赖|npm|
|io.netty:netty-tcnative-boringssl-static|2.0.53.Final|间接依赖|maven|
|number-is-nan|1.0.1|间接依赖|npm|
|arr-union|3.1.0|间接依赖|npm|
|commons-httpclient:commons-httpclient|3.1|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.9|间接依赖|maven|
|io.airlift:joni|2.1.5.3|直接依赖|maven|
|readdirp|2.1.0|间接依赖|npm|
|com.facebook.airlift:http-utils|0.207|间接依赖|maven|
|com.facebook.airlift:security|0.207|直接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.35.0|间接依赖|maven|
|d3-zoom|1.7.1|间接依赖|npm|
|org.jdbi:jdbi3-sqlobject|3.4.0|直接依赖|maven|
|babel-plugin-transform-es2015-modules-systemjs|6.24.1|间接依赖|npm|
|d3-scale-chromatic|1.3.3|间接依赖|npm|
|org.locationtech.proj4j:proj4j|1.1.5|间接依赖|maven|
|long|3.2.0|间接依赖|npm|
|io.prestodb.tempto:tempto-runner|1.53|直接依赖|maven|
|com.google.api.grpc:proto-google-cloud-bigquerystorage-v1alpha2|0.108.0|间接依赖|maven|
|net.thisptr:jackson-jq|0.0.10|间接依赖|maven|
|com.google.protobuf:protobuf-java-util|3.14.0|间接依赖|maven|
|is-ci|1.1.0|间接依赖|npm|
|io.opencensus:opencensus-api|0.24.0|间接依赖|maven|
|org.apache.zookeeper:zookeeper|3.4.14|直接依赖|maven|
|com.google.http-client:google-http-client-jackson2|1.38.1|间接依赖|maven|
|com.facebook.presto:presto-google-sheets|0.284-SNAPSHOT|直接依赖|maven|
|com.google.api:api-common|1.10.1|间接依赖|maven|
|com.facebook.presto:presto-expressions|0.284-SNAPSHOT|直接依赖|maven|
|babel-plugin-transform-es2015-block-scoping|6.26.0|间接依赖|npm|
|ieee754|1.1.12|间接依赖|npm|
|com.teradata.benchto:benchto-driver|0.4|直接依赖|maven|
|buffer-xor|1.0.3|间接依赖|npm|
|to-arraybuffer|1.0.1|间接依赖|npm|
|com.facebook.drift:drift-protocol|1.36|直接依赖|maven|
|io.grpc:grpc-netty-shaded|1.41.0|直接依赖|maven|
|com.facebook.presto:presto-spark-classloader-interface|0.284-SNAPSHOT|直接依赖|maven|
|sax|1.2.4|间接依赖|npm|
|micromatch|3.1.10|间接依赖|npm|
|watchpack|1.6.0|间接依赖|npm|
|commons-io:commons-io|2.4|直接依赖|maven|
|@webassemblyjs/leb128|1.5.13|间接依赖|npm|
|org.assertj:assertj-core|3.8.0|直接依赖|maven|
|com.facebook.presto:presto-client|0.284-SNAPSHOT|直接依赖|maven|
|com.google.apis:google-api-services-storage|v1-rev20181109-1.27.0|间接依赖|maven|
|long|4.0.0|间接依赖|npm|
|com.fasterxml.jackson.core:jackson-annotations|2.10.0|直接依赖|maven|
|d3-time|1.0.8|间接依赖|npm|
|d3-zoom|1.7.3|间接依赖|npm|
|org.reactivestreams:reactive-streams|1.0.4|间接依赖|maven|
|com.facebook.drift:drift-client|1.36|直接依赖|maven|
|wordwrap|1.0.0|间接依赖|npm|
|org.eclipse.jetty:jetty-servlet|9.4.14.v20181114|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.2|直接依赖|maven|
|d3-axis|1.0.8|间接依赖|npm|
|posix-character-classes|0.1.1|间接依赖|npm|
|com.facebook.presto:presto-verifier|0.284-SNAPSHOT|直接依赖|maven|
|org.hibernate:hibernate-validator|5.1.3.Final|间接依赖|maven|
|com.facebook.presto:presto-spark|0.284-SNAPSHOT|直接依赖|maven|
|md5.js|1.3.4|间接依赖|npm|
|tar|4.4.19|间接依赖|npm|
|irregular-plurals|2.0.0|间接依赖|npm|
|spdx-correct|3.0.0|间接依赖|npm|
|org.mozilla:rhino|1.7.11|间接依赖|maven|
|io.netty:netty-codec|4.1.92.Final|间接依赖|maven|
|cosmiconfig|5.0.5|间接依赖|npm|
|com.facebook.drift:drift-server|1.36|直接依赖|maven|
|miller-rabin|4.0.1|间接依赖|npm|
|rimraf|2.6.2|间接依赖|npm|
|@webassemblyjs/helper-api-error|1.5.13|间接依赖|npm|
|org.eclipse.jetty.http2:http2-common|9.4.14.v20181114|间接依赖|maven|
|org.json:json|20200518|间接依赖|maven|
|com.amazonaws:aws-java-sdk-s3|1.12.261|直接依赖|maven|
|com.google.flogger:flogger-system-backend|0.3.1|间接依赖|maven|
|d3-force|1.1.0|间接依赖|npm|
|unique-filename|1.1.0|间接依赖|npm|
|org.slf4j:jul-to-slf4j|1.7.32|间接依赖|maven|
|com.facebook.presto:presto-cli|0.284-SNAPSHOT|直接依赖|maven|
|log-symbols|2.2.0|间接依赖|npm|
|com.facebook.presto:presto-memory|0.284-SNAPSHOT|直接依赖|maven|
|extend-shallow|3.0.2|间接依赖|npm|
|update-notifier|2.5.0|间接依赖|npm|
|com.facebook.presto.hive:hive-apache-jdbc|0.13.1-5|直接依赖|maven|
|mimic-fn|1.2.0|间接依赖|npm|
|mkdirp|0.5.1|间接依赖|npm|
|babel-preset-flow|6.23.0|间接依赖|npm|
|babel-helper-builder-react-jsx|6.26.0|间接依赖|npm|
|d3-color|1.2.3|间接依赖|npm|
|copy-concurrently|1.0.5|间接依赖|npm|
|com.amazonaws:jmespath-java|1.12.261|间接依赖|maven|
|commons-io:commons-io|2.8.0|直接依赖|maven|
|json-schema-traverse|0.4.1|间接依赖|npm|
|org.apache.accumulo:accumulo-core|1.7.4|直接依赖|maven|
|org.apache.lucene:lucene-core|7.0.1|间接依赖|maven|
|hash-base|3.0.4|间接依赖|npm|
|sprintf-js|1.0.3|间接依赖|npm|
|has-ansi|2.0.0|间接依赖|npm|
|com.facebook.presto:presto-orc|0.284-SNAPSHOT|直接依赖|maven|
|fsevents|1.2.4|直接依赖|npm|
|io.grpc:grpc-grpclb|1.35.0|间接依赖|maven|
|trim-newlines|2.0.0|间接依赖|npm|
|inherits|2.0.3|间接依赖|npm|
|org.apache.maven:maven-artifact|3.0.4|间接依赖|maven|
|is-glob|4.0.0|间接依赖|npm|
|arr-flatten|1.1.0|间接依赖|npm|
|webpack|4.16.3|直接依赖|npm|
|process-nextick-args|2.0.0|间接依赖|npm|
|mixin-deep|1.3.1|间接依赖|npm|
|needle|2.2.1|间接依赖|npm|
|com.facebook.presto:presto-thrift-testing-udf-server|0.284-SNAPSHOT|直接依赖|maven|
|org.apache.tomcat:tomcat-jdbc|8.0.20|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.5|间接依赖|maven|
|com.oracle.ojdbc:ojdbc8|19.3.0.0|直接依赖|maven|
|com.google.code.gson:gson|2.9.0|间接依赖|maven|
|typedarray|0.0.6|间接依赖|npm|
|org.rnorth.duct-tape:duct-tape|1.0.8|间接依赖|maven|
|loud-rejection|1.6.0|间接依赖|npm|
|org.alluxio:alluxio-shaded-client|2.8.1|直接依赖|maven|
|ansi-regex|2.1.1|间接依赖|npm|
|d3-selection|1.3.2|间接依赖|npm|
|hmac-drbg|1.0.1|间接依赖|npm|
|com.typesafe.scala-logging:scala-logging_2.12|3.9.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|1.2.3.RELEASE|间接依赖|maven|
|io.grpc:grpc-core|1.35.0|间接依赖|maven|
|babel-types|6.26.0|间接依赖|npm|
|crypto-browserify|3.12.0|间接依赖|npm|
|array-find-index|1.0.2|间接依赖|npm|
|os-tmpdir|1.0.2|间接依赖|npm|
|lru-cache|4.1.3|间接依赖|npm|
|graphlib|2.1.5|间接依赖|npm|
|io.airlift.tpch:tpch|0.10|直接依赖|maven|
|org.apache.iceberg:iceberg-bundled-guava|1.3.1|直接依赖|maven|
|org.apache.lucene:lucene-sandbox|7.0.1|间接依赖|maven|
|react|16.4.1|直接依赖|npm|
|com.facebook.presto:presto-sqlserver|0.284-SNAPSHOT|直接依赖|maven|
|iconv-lite|0.4.23|间接依赖|npm|
|yargs-parser|10.1.0|间接依赖|npm|
|fast-deep-equal|2.0.1|间接依赖|npm|
|brorand|1.1.0|间接依赖|npm|
|concat-stream|1.6.2|间接依赖|npm|
|string_decoder|1.1.1|间接依赖|npm|
|create-error-class|3.0.2|间接依赖|npm|
|org.tukaani:xz|1.5|间接依赖|maven|
|com.amazonaws:aws-java-sdk-glue|1.12.261|直接依赖|maven|
|set-value|2.0.0|间接依赖|npm|
|org.apache.commons:commons-pool2|2.6.1|间接依赖|maven|
|esprima|4.0.1|间接依赖|npm|
|eslint-scope|4.0.0|间接依赖|npm|
|flow-bin|0.85.0|直接依赖|npm|
|com.github.docker-java:docker-java-api|3.3.0|直接依赖|maven|
|io.netty:netty-common|4.1.91.Final|直接依赖|maven|
|com.google.http-client:google-http-client|1.27.0|直接依赖|maven|
|io.grpc:grpc-protobuf-lite|1.41.0|间接依赖|maven|
|term-size|1.2.0|间接依赖|npm|
|org.lz4:lz4-java|1.7.1|间接依赖|maven|
|com.google.cloud.bigdataoss:util|1.9.17|直接依赖|maven|
|isarray|1.0.0|间接依赖|npm|
|elliptic|6.4.0|间接依赖|npm|
|mkdirp|0.5.6|间接依赖|npm|
|io.netty:netty|3.10.6.Final|间接依赖|maven|
|io.netty:netty-handler|4.1.91.Final|直接依赖|maven|
|com.ning:async-http-client|1.6.5|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet|2.26|间接依赖|maven|
|json-parse-better-errors|1.0.2|间接依赖|npm|
|io.grpc:grpc-api|1.35.0|直接依赖|maven|
|org.ow2.asm:asm-analysis|9.0|直接依赖|maven|
|io.netty:netty-codec|4.1.91.Final|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.5|直接依赖|maven|
|snapdragon-node|2.1.1|间接依赖|npm|
|org.apache.hive:hive-llap-common|2.3.4|直接依赖|maven|
|commander|2.19.0|间接依赖|npm|
|com.sun.istack:istack-commons-runtime|3.0.7|间接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5|5.2|间接依赖|maven|
|pumpify|1.5.1|间接依赖|npm|
|com.lmax:disruptor|3.3.6|间接依赖|maven|
|commons-codec:commons-codec|1.15|直接依赖|maven|
|memory-fs|0.4.1|间接依赖|npm|
|d3-timer|1.0.9|间接依赖|npm|
|are-we-there-yet|1.1.5|间接依赖|npm|
|net.jpountz.lz4:lz4|1.3.0|间接依赖|maven|
|d3-quadtree|1.0.3|间接依赖|npm|
|io.grpc:grpc-alts|1.32.2|间接依赖|maven|
|org.glassfish.grizzly:grizzly-http-server|2.4.4|间接依赖|maven|
|ripemd160|2.0.2|间接依赖|npm|
|babel-code-frame|6.26.0|间接依赖|npm|
|meow|5.0.0|间接依赖|npm|
|yallist|3.1.1|间接依赖|npm|
|querystring|0.2.0|间接依赖|npm|
|timers-browserify|2.0.10|间接依赖|npm|
|org.slf4j:jcl-over-slf4j|1.7.32|间接依赖|maven|
|org.iq80.leveldb:leveldb|0.10|间接依赖|maven|
|org.springframework.retry:spring-retry|1.1.2.RELEASE|间接依赖|maven|
|org.scala-lang.modules:scala-collection-compat_2.12|2.4.3|间接依赖|maven|
|make-dir|1.3.0|间接依赖|npm|
|babel-plugin-transform-react-display-name|6.25.0|间接依赖|npm|
|io.opentelemetry:opentelemetry-sdk-trace|1.19.0|直接依赖|maven|
|commons-net:commons-net|3.6|间接依赖|maven|
|read-pkg-up|3.0.0|间接依赖|npm|
|org.glassfish.hk2:hk2-locator|2.5.0-b42|间接依赖|maven|
|org.glassfish.grizzly:grizzly-framework|2.4.4|间接依赖|maven|
|com.facebook.drift:drift-codec-utils|1.36|直接依赖|maven|
|com.101tec:zkclient|0.10|直接依赖|maven|
|fast-deep-equal|3.1.3|间接依赖|npm|
|ignore-walk|3.0.1|间接依赖|npm|
|uglifyjs-webpack-plugin|1.2.7|间接依赖|npm|
|jsesc|1.3.0|间接依赖|npm|
|js-yaml|3.12.0|间接依赖|npm|
|es-to-primitive|1.1.1|间接依赖|npm|
|com.google.cloud.bigdataoss:util-hadoop|hadoop2-1.9.17|直接依赖|maven|
|graceful-fs|4.1.11|间接依赖|npm|
|restore-cursor|2.0.0|间接依赖|npm|
|unique-slug|2.0.0|间接依赖|npm|
|org.apache.maven:maven-plugin-api|3.0.4|间接依赖|maven|
|d3-quadtree|1.0.5|间接依赖|npm|
|org.jruby.joni:joni|2.1.27|间接依赖|maven|
|org.apache.lucene:lucene-memory|7.0.1|间接依赖|maven|
|kind-of|5.1.0|间接依赖|npm|
|org.webjars:swagger-ui|3.23.11|间接依赖|maven|
|com.facebook.presto:presto-plugin-toolkit|0.284-SNAPSHOT|直接依赖|maven|
|com.beust:jcommander|1.78|间接依赖|maven|
|org.sonatype.aether:aether-connector-asynchttpclient|1.13.1|间接依赖|maven|
|d3-contour|1.3.2|间接依赖|npm|
|quick-lru|1.1.0|间接依赖|npm|
|d3-drag|1.2.1|间接依赖|npm|
|io.airlift:parameternames|1.3|间接依赖|maven|
|d3-ease|1.0.5|间接依赖|npm|
|is-accessor-descriptor|0.1.6|间接依赖|npm|
|com.google.api.grpc:grpc-google-cloud-bigquerystorage-v1beta2|0.108.0|间接依赖|maven|
|com.facebook.airlift:trace-token|0.207|直接依赖|maven|
|decamelize|1.2.0|间接依赖|npm|
|sphinx-material|0.0.35|间接依赖|pip|
|com.facebook.airlift:launcher|0.207|直接依赖|maven|
|com.oracle.ojdbc:osdt_cert|19.3.0.0|间接依赖|maven|
|org.apache.lucene:lucene-analyzers-common|7.2.1|直接依赖|maven|
|org.locationtech.jts:jts-core|1.19.0|直接依赖|maven|
|babel-helper-define-map|6.26.0|间接依赖|npm|
|move-concurrently|1.0.1|间接依赖|npm|
|io.opentelemetry:opentelemetry-exporter-common|1.19.0|间接依赖|maven|
|argparse|1.0.10|间接依赖|npm|
|lodash.debounce|4.0.8|间接依赖|npm|
|org.codehaus.plexus:plexus-interpolation|1.14|间接依赖|maven|
|define-property|2.0.2|间接依赖|npm|
|cli-spinners|1.3.1|间接依赖|npm|
|babel-plugin-syntax-trailing-function-commas|6.22.0|间接依赖|npm|
|@webassemblyjs/helper-module-context|1.5.13|间接依赖|npm|
|org.apache.avro:avro|1.9.2|直接依赖|maven|
|d3-request|1.0.6|间接依赖|npm|
|babel-plugin-transform-es2015-template-literals|6.22.0|间接依赖|npm|
|ru.yandex.clickhouse:clickhouse-jdbc|0.2.4|直接依赖|maven|
|org.elasticsearch.client:elasticsearch-rest-high-level-client|6.0.0|直接依赖|maven|
|pump|2.0.1|间接依赖|npm|
|@webassemblyjs/wast-parser|1.5.13|间接依赖|npm|
|tar|4.4.4|间接依赖|npm|
|commons-lang:commons-lang|2.4|直接依赖|maven|
|strip-ansi|4.0.0|间接依赖|npm|
|com.googlecode.json-simple:json-simple|1.1.1|间接依赖|maven|
|camelcase|4.1.0|间接依赖|npm|
|union-value|1.0.0|间接依赖|npm|
|babel-plugin-transform-es2015-unicode-regex|6.24.1|间接依赖|npm|
|org.yaml:snakeyaml|1.14|间接依赖|maven|
|com.github.docker-java:docker-java-transport|3.3.0|间接依赖|maven|
|io.grpc:grpc-protobuf|1.41.0|直接依赖|maven|
|concat-map|0.0.1|间接依赖|npm|
|org.apache.commons:commons-lang3|3.4|直接依赖|maven|
|com.facebook.presto:presto-hive-hadoop2|0.284-SNAPSHOT|直接依赖|maven|
|org.apache.pinot:pinot-spi-jdk8|0.11.0|间接依赖|maven|
|url|0.11.0|间接依赖|npm|
|com.facebook.airlift:concurrent|0.207|直接依赖|maven|
|io.grpc:grpc-auth|1.32.2|间接依赖|maven|
|org.apache.thrift:libthrift|0.9.3|直接依赖|maven|
|path-browserify|0.0.0|间接依赖|npm|
|org.weakref:jmxutils|1.19|直接依赖|maven|
|com.facebook.airlift:jmx|0.207|直接依赖|maven|
|minimist|1.2.0|间接依赖|npm|
|org.threeten:threetenbp|1.5.1|间接依赖|maven|
|org.apache.maven:maven-aether-provider|3.0.4|间接依赖|maven|
|com.facebook.airlift:discovery|0.207|直接依赖|maven|
|org.apache.commons:commons-lang3|3.11|间接依赖|maven|
|com.github.spotbugs:spotbugs-annotations|3.1.10|间接依赖|maven|
|org.codehaus.janino:janino|3.1.8|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.10.0|直接依赖|maven|
|hosted-git-info|2.7.1|间接依赖|npm|
|org.glassfish.web:javax.el|2.2.4|间接依赖|maven|
|io.perfmark:perfmark-api|0.19.0|间接依赖|maven|
|private|0.1.8|间接依赖|npm|
|loader-runner|2.3.0|间接依赖|npm|
|prr|1.0.1|间接依赖|npm|
|org.locationtech.jts.io:jts-io-common|1.19.0|直接依赖|maven|
|io.lettuce:lettuce-core|6.2.4.RELEASE|直接依赖|maven|
|p-finally|1.0.0|间接依赖|npm|
|commander|2.13.0|间接依赖|npm|
|com.google.cloud.bigdataoss:gcsio|1.9.17|直接依赖|maven|
|d3-chord|1.0.6|间接依赖|npm|
|org.apache.druid:druid-core|0.19.0|直接依赖|maven|
|babel-plugin-transform-es2015-duplicate-keys|6.24.1|间接依赖|npm|
|d3-time-format|2.1.1|间接依赖|npm|
|org.springframework:spring-beans|4.1.6.RELEASE|间接依赖|maven|
|io.grpc:grpc-netty-shaded|1.35.0|直接依赖|maven|
|d3-color|1.0.3|间接依赖|npm|
|babel-preset-react|6.24.1|直接依赖|npm|
|ansi-styles|2.2.1|间接依赖|npm|
|com.google.cloud:google-cloud-core-http|1.94.0|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-paranamer|2.10.0|间接依赖|maven|
|babel-plugin-transform-regenerator|6.26.0|间接依赖|npm|
|npmlog|4.1.2|间接依赖|npm|
|to-regex-range|2.1.1|间接依赖|npm|
|has-unicode|2.0.1|间接依赖|npm|
|com.facebook.presto:presto-main|0.284-SNAPSHOT|直接依赖|maven|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|org.springframework:spring-context-support|4.1.6.RELEASE|间接依赖|maven|
|com.facebook.presto:presto-testng-services|0.284-SNAPSHOT|直接依赖|maven|
|org.apache.httpcomponents:httpmime|4.5.13|间接依赖|maven|
|big.js|3.2.0|间接依赖|npm|
|org.apache.ratis:ratis-metrics|2.2.0|间接依赖|maven|
|org.eclipse.jetty:jetty-server|9.4.14.v20181114|间接依赖|maven|
|babel-plugin-transform-es2015-modules-commonjs|6.26.2|间接依赖|npm|
|org.apache.yetus:audience-annotations|0.13.0|间接依赖|maven|
|org.sonatype.aether:aether-util|1.13.1|间接依赖|maven|
|stream-each|1.2.2|间接依赖|npm|
|org.glassfish.jersey.media:jersey-media-jaxb|2.26|间接依赖|maven|
|browserify-aes|1.2.0|间接依赖|npm|
|define-properties|1.1.2|间接依赖|npm|
|com.facebook.presto:presto-base-jdbc|0.284-SNAPSHOT|直接依赖|maven|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|gauge|2.7.4|间接依赖|npm|
|source-map-url|0.4.0|间接依赖|npm|
|org.apache.accumulo:accumulo-fate|1.7.4|间接依赖|maven|
|com.facebook.presto:presto-oracle|0.284-SNAPSHOT|直接依赖|maven|
|dot-prop|4.2.0|间接依赖|npm|
|define-property|0.2.5|间接依赖|npm|
|ajv|6.5.2|间接依赖|npm|
|babel-plugin-transform-react-jsx-source|6.22.0|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|com.facebook.presto:presto-kafka|0.284-SNAPSHOT|直接依赖|maven|
|io.netty:netty-tcnative-classes|2.0.53.Final|间接依赖|maven|
|com.facebook.presto:presto-pinot-toolkit|0.284-SNAPSHOT|直接依赖|maven|
|com.esotericsoftware:minlog|1.3.0|间接依赖|maven|
|io.netty:netty|3.6.2.Final|间接依赖|maven|
|indent-string|3.2.0|间接依赖|npm|
|map-obj|1.0.1|间接依赖|npm|
|npm-packlist|1.1.11|间接依赖|npm|
|org.sonatype.plexus:plexus-sec-dispatcher|1.3|间接依赖|maven|
|com.google.api:gax|1.60.1|直接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5-h2|5.2|间接依赖|maven|
|brace-expansion|1.1.11|间接依赖|npm|
|org.asynchttpclient:async-http-client|2.5.3|间接依赖|maven|
|define-property|1.0.0|间接依赖|npm|
|p-locate|2.0.0|间接依赖|npm|
|org.glassfish.hk2:osgi-resource-locator|1.0.1|间接依赖|maven|
|camelcase-keys|4.2.0|间接依赖|npm|
|for-in|1.0.2|间接依赖|npm|
|registry-auth-token|3.3.2|间接依赖|npm|
|@webpack-contrib/config-loader|1.2.1|间接依赖|npm|
|commons-lang:commons-lang|2.6|间接依赖|maven|
|babel-helper-explode-assignable-expression|6.24.1|间接依赖|npm|
|d3-voronoi|1.1.4|间接依赖|npm|
|org.glassfish.hk2:hk2-utils|2.5.0-b42|间接依赖|maven|
|is-binary-path|1.0.1|间接依赖|npm|
|org.glassfish.hk2:hk2-api|2.5.0-b42|间接依赖|maven|
|com.lmax:disruptor|3.3.4|间接依赖|maven|
|fs.realpath|1.0.0|间接依赖|npm|
|org.apache.calcite:calcite-babel|1.29.0|直接依赖|maven|
|babel-preset-env|1.7.0|直接依赖|npm|
|io.opentelemetry:opentelemetry-exporter-otlp-common|1.19.0|间接依赖|maven|
|ansi-styles|3.2.1|间接依赖|npm|
|semver-diff|2.1.0|间接依赖|npm|
|io.opencensus:opencensus-api|0.28.0|间接依赖|maven|
|parallel-transform|1.1.0|间接依赖|npm|
|com.facebook.presto:presto-accumulo|0.284-SNAPSHOT|直接依赖|maven|
|is-glob|3.1.0|间接依赖|npm|
|com.google.flogger:google-extensions|0.3.1|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|3.2.2|间接依赖|maven|
|stream-http|2.8.3|间接依赖|npm|
|d3-force|1.1.2|间接依赖|npm|
|com.teradata.tpcds:tpcds|1.2|直接依赖|maven|
|org.apache.avro:avro|1.8.1|直接依赖|maven|
|org.apache.calcite:calcite-core|1.32.0|直接依赖|maven|
|com.facebook.airlift:bytecode|1.3|间接依赖|maven|
|strip-ansi|3.0.1|间接依赖|npm|
|com.facebook.airlift:log-manager|0.207|直接依赖|maven|
|is-descriptor|1.0.2|间接依赖|npm|
|set-blocking|2.0.0|间接依赖|npm|
|org.skife.config:config-magic|0.9|间接依赖|maven|
|com.sun.activation:javax.activation|1.2.0|间接依赖|maven|
|from2|2.3.0|间接依赖|npm|
|org.reactivestreams:reactive-streams|1.0.2|间接依赖|maven|
|io.delta:delta-storage|2.2.0|间接依赖|maven|
|com.google.auth:google-auth-library-oauth2-http|0.12.0|直接依赖|maven|
|is-fullwidth-code-point|2.0.0|间接依赖|npm|
|com.facebook.presto:presto-grpc-api|0.284-SNAPSHOT|直接依赖|maven|
|regenerate|1.4.0|间接依赖|npm|
|commons-cli:commons-cli|1.3.1|间接依赖|maven|
|io.prestodb.tempto:tempto-core|1.53|直接依赖|maven|
|org.apache.pinot:pinot-segment-spi-jdk8|0.11.0|间接依赖|maven|
|org.springframework:spring-tx|4.1.6.RELEASE|间接依赖|maven|
|com.google.protobuf:protobuf-java-util|3.13.0|间接依赖|maven|
|com.facebook.presto:presto-local-file|0.284-SNAPSHOT|直接依赖|maven|
|com.oracle.ojdbc:ons|19.3.0.0|间接依赖|maven|
|org.postgresql:postgresql|42.6.0|直接依赖|maven|
|net.minidev:accessors-smart|2.4.7|间接依赖|maven|
|org.javassist:javassist|3.22.0-GA|间接依赖|maven|
|org.apache.ratis:ratis-common|2.2.0|直接依赖|maven|
|io.grpc:grpc-stub|1.41.0|直接依赖|maven|
|com.google.api-client:google-api-client-jackson2|1.27.0|间接依赖|maven|
|d3-path|1.0.7|间接依赖|npm|
|babel-plugin-transform-es2015-shorthand-properties|6.24.1|间接依赖|npm|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.12.6|间接依赖|maven|
|babel-plugin-transform-es2015-arrow-functions|6.22.0|间接依赖|npm|
|org.sonatype.aether:aether-spi|1.13.1|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.10.0|直接依赖|maven|
|babel-register|6.26.0|间接依赖|npm|
|hash.js|1.1.5|间接依赖|npm|
|org.apache.ratis:ratis-grpc|2.2.0|直接依赖|maven|
|com.google.myanmartools:myanmar-tools|1.1.3|直接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.7|间接依赖|maven|
|org.apache.lucene:lucene-highlighter|7.0.1|间接依赖|maven|
|io.opentelemetry:opentelemetry-context|1.19.0|直接依赖|maven|
|aproba|1.2.0|间接依赖|npm|
|duplexer3|0.1.4|间接依赖|npm|
|io.projectreactor:reactor-core|3.4.29|间接依赖|maven|
|xmlhttprequest|1.8.0|间接依赖|npm|
|is-finite|1.0.2|间接依赖|npm|
|com.facebook.presto:presto-example-http|0.284-SNAPSHOT|直接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.2.6|直接依赖|maven|
|com.facebook.presto.ranger:ranger-apache|2.1.0-3|直接依赖|maven|
|io.airlift:slice|0.38|直接依赖|maven|
|loader-utils|1.1.0|间接依赖|npm|
|org.jboss.logging:jboss-logging|3.2.1.Final|间接依赖|maven|
|plur|3.0.1|间接依赖|npm|
|isomorphic-fetch|2.2.1|间接依赖|npm|
|org.slf4j:log4j-over-slf4j|1.7.32|间接依赖|maven|
|org.apache.maven:maven-repository-metadata|3.0.4|间接依赖|maven|
|io.grpc:grpc-stub|1.35.0|直接依赖|maven|
|reactable|1.0.2|直接依赖|npm|
|find-cache-dir|1.0.0|间接依赖|npm|
|com.google.inject:guice|4.2.2|直接依赖|maven|
|org.sonatype.aether:aether-impl|1.13.1|间接依赖|maven|
|com.google.api.grpc:proto-google-iam-v1|1.0.7|间接依赖|maven|
|com.facebook.presto:presto-mysql|0.284-SNAPSHOT|直接依赖|maven|
|com.typesafe.netty:netty-reactive-streams|2.0.0|间接依赖|maven|
|console-control-strings|1.1.0|间接依赖|npm|
|webpack-command|0.4.1|直接依赖|npm|
|color-convert|1.9.2|间接依赖|npm|
|esrecurse|4.2.1|间接依赖|npm|
|ua-parser-js|0.7.18|间接依赖|npm|
|enhanced-resolve|4.1.0|间接依赖|npm|
|d3-array|1.2.4|间接依赖|npm|
|babel-helper-remap-async-to-generator|6.24.1|间接依赖|npm|
|is-builtin-module|1.0.0|间接依赖|npm|
|com.facebook.airlift:json|0.207|直接依赖|maven|
|com.facebook.airlift:node|0.207|直接依赖|maven|
|joda-time:joda-time|2.12.2|直接依赖|maven|
|org.apache.commons:commons-pool2|2.3|间接依赖|maven|
|is-number|3.0.0|间接依赖|npm|
|org.iq80.leveldb:leveldb-api|0.10|间接依赖|maven|
|org.pcollections:pcollections|2.1.2|直接依赖|maven|
|org.jheaps:jheaps|0.10|间接依赖|maven|
|is-redirect|1.0.0|间接依赖|npm|
|org.codehaus.mojo:animal-sniffer-annotations|1.19|间接依赖|maven|
|org.jboss.logging:jboss-logging|3.1.3.GA|间接依赖|maven|
|org.apache.lucene:lucene-core|8.2.0|间接依赖|maven|
|com.facebook.drift:drift-api|1.36|直接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|org.apache.commons:commons-vfs2|2.2|间接依赖|maven|
|org.codehaus.plexus:plexus-component-annotations|1.5.5|间接依赖|maven|
|@webassemblyjs/wasm-edit|1.5.13|间接依赖|npm|
|org.antlr:antlr4-runtime|4.7.1|直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-logs|1.19.0-alpha|间接依赖|maven|
|org.roaringbitmap:RoaringBitmap|0.9.3|直接依赖|maven|
|org.apache.lucene:lucene-queryparser|8.2.0|间接依赖|maven|
|signal-exit|3.0.2|间接依赖|npm|
|org.codehaus.janino:commons-compiler|3.1.8|间接依赖|maven|
|xtend|4.0.1|间接依赖|npm|
|com.google.cloud:google-cloud-bigquerystorage|1.8.0|直接依赖|maven|
|@webpack-contrib/schema-utils|1.0.0-beta.0|间接依赖|npm|
|org.apache.httpcomponents.core5:httpcore5|5.1.3|间接依赖|maven|
|org.ow2.asm:asm-util|9.0|直接依赖|maven|
|os-homedir|1.0.2|间接依赖|npm|
|com.facebook.presto:presto-atop|0.284-SNAPSHOT|直接依赖|maven|
|is-installed-globally|0.1.0|间接依赖|npm|
|assert|1.4.1|间接依赖|npm|
|babel-plugin-transform-exponentiation-operator|6.24.1|间接依赖|npm|
|org.apache.ratis:ratis-server|2.2.0|直接依赖|maven|
|path-parse|1.0.5|间接依赖|npm|
|com.facebook.presto:presto-druid|0.284-SNAPSHOT|直接依赖|maven|
|chownr|1.0.1|间接依赖|npm|
|org.springframework.boot:spring-boot-autoconfigure|1.2.3.RELEASE|间接依赖|maven|
|org.apache.commons:commons-compress|1.18|间接依赖|maven|
|net.sf.jopt-simple:jopt-simple|5.0.4|间接依赖|maven|
|bn.js|4.11.8|间接依赖|npm|
|babel-messages|6.23.0|间接依赖|npm|
|ini|1.3.5|间接依赖|npm|
|babel-template|6.26.0|间接依赖|npm|
|junit:junit|4.13.2|间接依赖|maven|
|redent|2.0.0|间接依赖|npm|
|com.google.auth:google-auth-library-oauth2-http|0.22.2|直接依赖|maven|
|io.opentelemetry:opentelemetry-semconv|1.19.0-alpha|直接依赖|maven|
|d3|5.7.0|直接依赖|npm|
|cipher-base|1.0.4|间接依赖|npm|
|vm-browserify|0.0.4|间接依赖|npm|
|babel-plugin-transform-es2015-modules-umd|6.24.1|间接依赖|npm|
|encoding|0.1.12|间接依赖|npm|
|promise|7.3.1|间接依赖|npm|
|com.jayway.jsonpath:json-path|2.6.0|直接依赖|maven|
|org.apache.druid:extendedset|0.19.0|间接依赖|maven|
|iconv-lite|0.4.24|间接依赖|npm|
|com.google.oauth-client:google-oauth-client-java6|1.27.0|间接依赖|maven|
|bluebird|3.5.1|间接依赖|npm|
|org.elasticsearch:elasticsearch|6.0.0|直接依赖|maven|
|com.google.api-client:google-api-client|1.31.1|间接依赖|maven|
|com.google.api-client:google-api-client-java6|1.27.0|间接依赖|maven|
|org.yaml:snakeyaml|1.15|间接依赖|maven|
|com.facebook.presto:presto-memory-context|0.284-SNAPSHOT|直接依赖|maven|
|io.grpc:grpc-context|1.41.0|间接依赖|maven|
|path-parse|1.0.7|间接依赖|npm|
|com.teradata:re2j-td|1.4|直接依赖|maven|
|org.apache.druid:druid-processing|0.19.0|直接依赖|maven|
|fragment-cache|0.2.1|间接依赖|npm|
|com.facebook.presto:presto-redshift|0.284-SNAPSHOT|直接依赖|maven|
|org.eclipse.jetty.http2:http2-server|9.4.14.v20181114|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.92.Final|间接依赖|maven|
|org.apache.curator:curator-framework|2.12.0|直接依赖|maven|
|org.apache.accumulo:accumulo-start|1.7.4|间接依赖|maven|
|async-each|1.0.1|间接依赖|npm|
|com.google.api.grpc:proto-google-common-protos|2.0.1|间接依赖|maven|
|com.facebook.drift:drift-transport-spi|1.36|直接依赖|maven|
|d3-scale|1.0.7|间接依赖|npm|
|com.facebook.presto:presto-spark-common|0.284-SNAPSHOT|直接依赖|maven|
|com.facebook.presto:presto-record-decoder|0.284-SNAPSHOT|直接依赖|maven|
|camelcase|5.0.0|间接依赖|npm|
|is-accessor-descriptor|1.0.0|间接依赖|npm|
|validate-npm-package-license|3.0.3|间接依赖|npm|
|ssri|5.3.0|间接依赖|npm|
|org.jdbi:jdbi|2.78|间接依赖|maven|
|com.facebook.presto:presto-session-property-managers|0.284-SNAPSHOT|直接依赖|maven|
|org.codehaus.plexus:plexus-classworlds|2.4|间接依赖|maven|
|pkg-dir|2.0.0|间接依赖|npm|
|neo-async|2.5.1|间接依赖|npm|
|babel-plugin-transform-async-to-generator|6.24.1|间接依赖|npm|
|buffer|4.9.1|间接依赖|npm|
|com.facebook.presto:presto-hive|0.284-SNAPSHOT|直接依赖|maven|
|org.apache.httpcomponents.core5:httpcore5-h2|5.1.3|间接依赖|maven|
|debug|2.6.9|间接依赖|npm|
|readable-stream|2.3.6|间接依赖|npm|
|v8-compile-cache|2.0.0|间接依赖|npm|
|d3-ease|1.0.3|间接依赖|npm|
|com.facebook.presto:presto-cache|0.284-SNAPSHOT|直接依赖|maven|
|d3-axis|1.0.12|间接依赖|npm|
|com.facebook.presto:presto-cluster-ttl-providers|0.284-SNAPSHOT|直接依赖|maven|
|foreach|2.0.5|间接依赖|npm|
|is-plain-obj|1.1.0|间接依赖|npm|
|com.facebook.presto:presto-common|0.284-SNAPSHOT|直接依赖|maven|
|sphinx-copybutton|0.5.0|间接依赖|pip|
|chalk|1.1.3|间接依赖|npm|
|regjsparser|0.1.5|间接依赖|npm|
|babel-plugin-syntax-async-functions|6.13.0|间接依赖|npm|
|com.facebook.presto:presto-pinot|0.284-SNAPSHOT|直接依赖|maven|
|minimatch|3.0.4|间接依赖|npm|
|strip-indent|2.0.0|间接依赖|npm|
|org.springframework:spring-web|4.1.6.RELEASE|间接依赖|maven|
|org.apache.maven:maven-embedder|3.0.4|间接依赖|maven|
|org.springframework:spring-expression|4.1.6.RELEASE|间接依赖|maven|
|org.apache.commons:commons-dbcp2|2.1|间接依赖|maven|
|babel-plugin-transform-es2015-spread|6.22.0|间接依赖|npm|
|com.google.api.grpc:grpc-google-cloud-bigquerystorage-v1|1.8.0|间接依赖|maven|
|write-file-atomic|2.3.0|间接依赖|npm|
|@webassemblyjs/wasm-opt|1.5.13|间接依赖|npm|
|javax.el:javax.el-api|2.2.4|间接依赖|maven|
|com.facebook.presto:presto-postgresql|0.284-SNAPSHOT|直接依赖|maven|
|json5|0.5.1|间接依赖|npm|
|cacache|10.0.4|间接依赖|npm|
|com.google.j2objc:j2objc-annotations|1.3|间接依赖|maven|
|org.apache.maven:maven-core|3.0.4|间接依赖|maven|
|com.mchange:mchange-commons-java|0.2.15|间接依赖|maven|
|minimalistic-assert|1.0.1|间接依赖|npm|
|com.google.http-client:google-http-client|1.38.1|直接依赖|maven|
|org.xerial.larray:larray-mmap|0.4.1|间接依赖|maven|
|org.apache.parquet:parquet-common|1.12.0|直接依赖|maven|
|org.apache.iceberg:iceberg-hive-metastore|1.3.1|直接依赖|maven|
|org.glassfish.hk2:hk2-utils|2.6.1|间接依赖|maven|
|com.facebook.hive:hive-dwrf|0.8.5|直接依赖|maven|
|org.apache.lucene:lucene-grouping|7.0.1|间接依赖|maven|
|com.google.protobuf:protobuf-java|3.14.0|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.32|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)