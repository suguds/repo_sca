# jeremylong/DependencyCheck安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696584955436888064.svg)](https://www.murphysec.com/console/report/1696584955386556416/1696584955436888064)

仓库描述：OWASP dependency-check is a software composition analysis utility that detects publicly disclosed vulnerabilities in application dependencies.

仓库地址：[https://github.com/jeremylong/DependencyCheck](https://github.com/jeremylong/DependencyCheck)

| star：5319 | watch：167 | fork：1126 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-30 01:00:33 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-30 02:33:56 | 组件总数：1264 | 漏洞总数：251 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Opensymphony XWork ParameterInterceptor类绕过安全限制漏洞|输入验证不恰当|[MPS-2009-1510](https://www.oscs1024.com/hd/MPS-2009-1510)|CVE-2008-6504|中危|
|Spring Framework 正则表达式拒绝服务漏洞|资源管理错误|[MPS-2009-2202](https://www.oscs1024.com/hd/MPS-2009-2202)|CVE-2009-1190|中危|
|SpringSource Spring Framework 代码注入漏洞|代码注入|[MPS-2010-2396](https://www.oscs1024.com/hd/MPS-2010-2396)|CVE-2010-1622|中危|
|Apache Atlassian Fisheye Struts Xwork设计错误漏洞|代码注入|[MPS-2010-3061](https://www.oscs1024.com/hd/MPS-2010-3061)|CVE-2010-1870|中危|
|Apache Struts XWork ''错误页面跨站脚本攻击漏洞|XSS|[MPS-2011-1593](https://www.oscs1024.com/hd/MPS-2011-1593)|CVE-2011-1772|低危|
|Spring Framework  deserialize  对象权限许可和访问控制漏洞|反序列化|[MPS-2011-3048](https://www.oscs1024.com/hd/MPS-2011-3048)|CVE-2011-2894|中危|
|Jetty 拒绝服务漏洞|密码学问题|[MPS-2011-4130](https://www.oscs1024.com/hd/MPS-2011-4130)|CVE-2011-4461|中危|
|Apache Struts 输入验证漏洞|代码注入|[MPS-2012-0048](https://www.oscs1024.com/hd/MPS-2012-0048)|CVE-2012-0391|严重|
|Apache Struts  CookieInterceptor 组件权限许可和访问控制问题漏洞|权限、特权和访问控制|[MPS-2012-0049](https://www.oscs1024.com/hd/MPS-2012-0049)|CVE-2012-0392|中危|
|Apache Struts  ParameterInterceptor 组件权限许可和访问控制漏洞|权限、特权和访问控制|[MPS-2012-0050](https://www.oscs1024.com/hd/MPS-2012-0050)|CVE-2012-0393|中危|
|Apache Struts  DebuggingInterceptor 组件代码注入漏洞|代码注入|[MPS-2012-0051](https://www.oscs1024.com/hd/MPS-2012-0051)|CVE-2012-0394|中危|
|Apache Struts 权限许可和访问控制问题漏洞|权限、特权和访问控制|[MPS-2012-0052](https://www.oscs1024.com/hd/MPS-2012-0052)|CVE-2011-5057|中危|
|Apache Struts任意代码执行漏洞|输入验证不恰当|[MPS-2012-0676](https://www.oscs1024.com/hd/MPS-2012-0676)|CVE-2012-0838|严重|
|Apache Struts 令牌检查机制跨站请求伪造漏洞|CSRF|[MPS-2012-3426](https://www.oscs1024.com/hd/MPS-2012-3426)|CVE-2012-4386|中危|
|Spring Framework表达式语言JSP属性处理信息泄露漏洞|配置缺陷|[MPS-2012-5092](https://www.oscs1024.com/hd/MPS-2012-5092)|CVE-2011-2730|高危|
|Apache Commons FileUpload 权限绕过漏洞|权限、特权和访问控制|[MPS-2013-1041](https://www.oscs1024.com/hd/MPS-2013-1041)|CVE-2013-0248|低危|
|Apache Struts 代码注入漏洞|代码注入|[MPS-2013-2581](https://www.oscs1024.com/hd/MPS-2013-2581)|CVE-2013-1966|严重|
|Apache Struts  includeParams 安全绕过漏洞|代码注入|[MPS-2013-2582](https://www.oscs1024.com/hd/MPS-2013-2582)|CVE-2013-2115|高危|
|Apache Struts 任意OGNL代码执行漏洞|代码注入|[MPS-2013-2633](https://www.oscs1024.com/hd/MPS-2013-2633)|CVE-2013-2134|严重|
|Apache Struts OGNL表达式注入漏洞|代码注入|[MPS-2013-2634](https://www.oscs1024.com/hd/MPS-2013-2634)|CVE-2013-2135|严重|
|Apache Struts 多个开放重定向漏洞|跨站重定向|[MPS-2013-2748](https://www.oscs1024.com/hd/MPS-2013-2748)|CVE-2013-2248|中危|
|Apache Struts 多个输入验证错误漏洞|代码注入|[MPS-2013-2749](https://www.oscs1024.com/hd/MPS-2013-2749)|CVE-2013-2251|严重|
|Suds cache.py文件安全漏洞|在文件访问前对链接解析不恰当（链接跟随）|[MPS-2013-3621](https://www.oscs1024.com/hd/MPS-2013-3621)|CVE-2013-2217|低危|
|Apache Struts 安全绕过漏洞|权限、特权和访问控制|[MPS-2013-3705](https://www.oscs1024.com/hd/MPS-2013-3705)|CVE-2013-4310|中危|
|Apache Struts 远程代码执行漏洞||[MPS-2013-3707](https://www.oscs1024.com/hd/MPS-2013-3707)|CVE-2013-4316|严重|
|Apache Commons FileUpload DiskFileItem 类任意文件写入漏洞|输入验证不恰当|[MPS-2013-4267](https://www.oscs1024.com/hd/MPS-2013-4267)|CVE-2013-2186|高危|
|Apache Struts 安全漏洞|代码注入|[MPS-2014-1126](https://www.oscs1024.com/hd/MPS-2014-1126)|CVE-2014-0094|中危|
|Apache Commons FileUpload <1.3.1 拒绝服务漏洞|权限、特权和访问控制|[MPS-2014-1540](https://www.oscs1024.com/hd/MPS-2014-1540)|CVE-2014-0050|高危|
|Apache Struts 权限许可和访问控制问题漏洞|权限、特权和访问控制|[MPS-2014-2136](https://www.oscs1024.com/hd/MPS-2014-2136)|CVE-2014-0113|高危|
|Apache Struts 远程代码执行漏洞|输入验证不恰当|[MPS-2014-2167](https://www.oscs1024.com/hd/MPS-2014-2167)|CVE-2014-0114|高危|
|Apache Struts 权限许可和访问控制问题漏洞|权限、特权和访问控制|[MPS-2014-2294](https://www.oscs1024.com/hd/MPS-2014-2294)|CVE-2014-0116|中危|
|Hibernate Validator 认证绕过漏洞|认证绕过|[MPS-2014-5374](https://www.oscs1024.com/hd/MPS-2014-5374)|CVE-2014-3558|中危|
|Joyent Node.js qs模块拒绝服务漏洞|资源管理错误|[MPS-2014-6155](https://www.oscs1024.com/hd/MPS-2014-6155)|CVE-2014-7191|中危|
|Apache Struts 跨站请求伪造漏洞|CSRF|[MPS-2014-7470](https://www.oscs1024.com/hd/MPS-2014-7470)|CVE-2014-7809|中危|
|Pivotal Software Spring Framework 目录遍历漏洞|路径遍历|[MPS-2015-1090](https://www.oscs1024.com/hd/MPS-2015-1090)|CVE-2014-3578|中危|
|多款Cisco产品Apache Commons Collections库任意代码执行漏洞|反序列化|[MPS-2015-6277](https://www.oscs1024.com/hd/MPS-2015-6277)|CVE-2015-6420|高危|
|Joyent Node.js is-my-json-valid 拒绝服务漏洞|拒绝服务|[MPS-2016-1001](https://www.oscs1024.com/hd/MPS-2016-1001)|CVE-2016-2537|高危|
|BeanShell 任意命令执行漏洞|数据处理错误|[MPS-2016-1438](https://www.oscs1024.com/hd/MPS-2016-1438)|CVE-2016-2510|高危|
|Apache Struts Oracle JRE 跨站脚本漏洞|XSS|[MPS-2016-1580](https://www.oscs1024.com/hd/MPS-2016-1580)|CVE-2016-4003|中危|
|Hawk 拒绝服务漏洞|资源管理错误|[MPS-2016-1657](https://www.oscs1024.com/hd/MPS-2016-1657)|CVE-2016-2515|高危|
|Apache Struts 命令注入漏洞(s2-032)|命令注入|[MPS-2016-1978](https://www.oscs1024.com/hd/MPS-2016-1978)|CVE-2016-3081|高危|
|Apache Struts 2 XSLTResult 安全漏洞(S2-031)|输入验证不恰当|[MPS-2016-1979](https://www.oscs1024.com/hd/MPS-2016-1979)|CVE-2016-3082|严重|
|Apache Struts 2 输入验证错误漏洞(s2-033)|输入验证不恰当|[MPS-2016-2733](https://www.oscs1024.com/hd/MPS-2016-2733)|CVE-2016-3087|严重|
|Apache Struts 2 访问控制不当漏洞|清理环节不完整|[MPS-2016-4872](https://www.oscs1024.com/hd/MPS-2016-4872)|CVE-2016-4436|严重|
|Apache Commons FileUpload 访问控制错误漏洞|访问控制不当|[MPS-2016-5301](https://www.oscs1024.com/hd/MPS-2016-5301)|CVE-2016-1000031|严重|
|Joyent Node.js uglify-js 资源管理错误漏洞|资源管理错误|[MPS-2017-0615](https://www.oscs1024.com/hd/MPS-2017-0615)|CVE-2015-8858|高危|
|Apache Struts 代码问题漏洞|反序列化|[MPS-2017-10513](https://www.oscs1024.com/hd/MPS-2017-10513)|CVE-2017-9805|高危|
|Apache Struts 输入验证错误漏洞|反序列化|[MPS-2017-10663](https://www.oscs1024.com/hd/MPS-2017-10663)|CVE-2017-12611|严重|
|JSoup 跨站脚本漏洞|XSS|[MPS-2017-10843](https://www.oscs1024.com/hd/MPS-2017-10843)|CVE-2015-6748|中危|
|Apache Struts 2 跨站脚本漏洞|XSS|[MPS-2017-10853](https://www.oscs1024.com/hd/MPS-2017-10853)|CVE-2015-5169|中危|
|Joyent Node.js tough-cookie模块安全漏洞|拒绝服务|[MPS-2017-11145](https://www.oscs1024.com/hd/MPS-2017-11145)|CVE-2017-15010|高危|
|多款Red Hat产品代码问题漏洞|反序列化|[MPS-2017-12638](https://www.oscs1024.com/hd/MPS-2017-12638)|CVE-2015-7501|严重|
|Jetty 信息泄露漏洞|通过差异性导致的信息暴露|[MPS-2017-6690](https://www.oscs1024.com/hd/MPS-2017-6690)|CVE-2017-9735|高危|
|web framework qs模块输入验证漏洞|输入验证不恰当|[MPS-2017-7711](https://www.oscs1024.com/hd/MPS-2017-7711)|CVE-2017-1000048|高危|
|Apache Struts 访问控制不当漏洞|访问控制不当|[MPS-2017-9694](https://www.oscs1024.com/hd/MPS-2017-9694)|CVE-2015-5209|高危|
|marked data: URI解析器 XSS 漏洞|XSS|[MPS-2018-0046](https://www.oscs1024.com/hd/MPS-2018-0046)|CVE-2017-1000427|中危|
|adm-zip npm library 路径遍历漏洞|路径遍历|[MPS-2018-10409](https://www.oscs1024.com/hd/MPS-2018-10409)|CVE-2018-1002204|中危|
|Tough-Cookie 拒绝服务漏洞|拒绝服务|[MPS-2018-11858](https://www.oscs1024.com/hd/MPS-2018-11858)|CVE-2016-1000232|中危|
|Python 信任管理问题漏洞|凭证保护不足|[MPS-2018-13292](https://www.oscs1024.com/hd/MPS-2018-13292)|CVE-2018-18074|高危|
|Gitea 安全漏洞|会话固定|[MPS-2018-14413](https://www.oscs1024.com/hd/MPS-2018-14413)|CVE-2018-18926|严重|
|lxml 跨站脚本漏洞|XSS|[MPS-2018-15340](https://www.oscs1024.com/hd/MPS-2018-15340)|CVE-2018-19787|中危|
|c3p0 存在 XXE 漏洞|XXE|[MPS-2018-16252](https://www.oscs1024.com/hd/MPS-2018-16252)|CVE-2018-20433|严重|
|Infinispan Hotrod客户端安全漏洞|反序列化|[MPS-2018-1957](https://www.oscs1024.com/hd/MPS-2018-1957)|CVE-2017-15089|高危|
|Npm 安全漏洞|关键资源权限分配不当|[MPS-2018-2363](https://www.oscs1024.com/hd/MPS-2018-2363)|CVE-2018-7408|高危|
|Hoek 访问控制错误漏洞|MAID|[MPS-2018-3882](https://www.oscs1024.com/hd/MPS-2018-3882)|CVE-2018-3728|高危|
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|qs 模块拒绝服务漏洞|资源管理错误|[MPS-2018-6699](https://www.oscs1024.com/hd/MPS-2018-6699)|CVE-2014-10064|高危|
|marked XSS 漏洞|XSS|[MPS-2018-6716](https://www.oscs1024.com/hd/MPS-2018-6716)|CVE-2016-10531|中危|
|Minimatch 拒绝服务漏洞|拒绝服务|[MPS-2018-6725](https://www.oscs1024.com/hd/MPS-2018-6725)|CVE-2016-10540|高危|
|Http-signature 安全漏洞|密码学签名的验证不恰当|[MPS-2018-6996](https://www.oscs1024.com/hd/MPS-2018-6996)|CVE-2017-16005|高危|
|Request 内存泄漏漏洞|通过发送数据的信息暴露|[MPS-2018-7014](https://www.oscs1024.com/hd/MPS-2018-7014)|CVE-2017-16026|中危|
|Growl 安全漏洞|OS命令注入|[MPS-2018-7026](https://www.oscs1024.com/hd/MPS-2018-7026)|CVE-2017-16042|严重|
|marked 模块拒绝服务漏洞|拒绝服务|[MPS-2018-7187](https://www.oscs1024.com/hd/MPS-2018-7187)|CVE-2017-16114|高危|
|timespan模块安全漏洞|拒绝服务|[MPS-2018-7188](https://www.oscs1024.com/hd/MPS-2018-7188)|CVE-2017-16115|高危|
|debug 模块拒绝服务漏洞|拒绝服务|[MPS-2018-7210](https://www.oscs1024.com/hd/MPS-2018-7210)|CVE-2017-16137|中危|
|mime模块拒绝服务漏洞|拒绝服务|[MPS-2018-7211](https://www.oscs1024.com/hd/MPS-2018-7211)|CVE-2017-16138|高危|
|sshpk 安全漏洞|不正确的正则表达式|[MPS-2018-7302](https://www.oscs1024.com/hd/MPS-2018-7302)|CVE-2018-3737|高危|
|lodash node 拒绝服务漏洞|拒绝服务|[MPS-2018-7315](https://www.oscs1024.com/hd/MPS-2018-7315)|CVE-2018-3721|中危|
|Eclipse Jetty <9.4.11.v20180605 授权绕过漏洞|HTTP请求走私|[MPS-2018-8347](https://www.oscs1024.com/hd/MPS-2018-8347)|CVE-2017-7657|严重|
|Eclipse Jetty <9.4.11.v20180605 存在授权绕过漏洞|HTTP请求走私|[MPS-2018-8415](https://www.oscs1024.com/hd/MPS-2018-8415)|CVE-2017-7658|严重|
|extend module 输入验证错误漏洞|原型污染|[MPS-2018-8705](https://www.oscs1024.com/hd/MPS-2018-8705)|CVE-2018-3750|严重|
|MongoDB bson JavaScript模块安全漏洞||[MPS-2018-9473](https://www.oscs1024.com/hd/MPS-2018-9473)|CVE-2018-13863|高危|
|Apache Commons Beanutils 存在不可信数据的反序列化漏洞|反序列化|[MPS-2019-10233](https://www.oscs1024.com/hd/MPS-2019-10233)|CVE-2019-10086|高危|
|Netty 存在 HTTP 请求走私漏洞|HTTP请求走私|[MPS-2019-12064](https://www.oscs1024.com/hd/MPS-2019-12064)|CVE-2019-16869|高危|
|lodash 存在拒绝服务漏洞|拒绝服务|[MPS-2019-1228](https://www.oscs1024.com/hd/MPS-2019-1228)|CVE-2018-16487|中危|
|extend module [*, 2.0.2)、[3.0.0, 3.0.2) 原型污染漏洞|注入|[MPS-2019-1232](https://www.oscs1024.com/hd/MPS-2019-1232)|CVE-2018-16492|严重|
|Red Hat JBoss Enterprise Application Platform 代码问题漏洞|反序列化|[MPS-2019-12470](https://www.oscs1024.com/hd/MPS-2019-12470)|CVE-2019-10202|严重|
|Apache Struts 'ParameterInterceptor' Class OGNL安全绕过漏洞|关键资源权限分配不当|[MPS-2019-14018](https://www.oscs1024.com/hd/MPS-2019-14018)|CVE-2011-3923|严重|
|​ hibernate-validator  存在跨站脚本（XSS）漏洞|XSS|[MPS-2019-14389](https://www.oscs1024.com/hd/MPS-2019-14389)|CVE-2019-10219|中危|
|jackson-mapper-asl <=1.9.13 XXE 注入漏洞|XXE|[MPS-2019-15048](https://www.oscs1024.com/hd/MPS-2019-15048)|CVE-2019-10172|高危|
|Red Hat Infinispan 安全漏洞|使用外部可控制的输入来选择类或代码（不安全的反射）|[MPS-2019-15311](https://www.oscs1024.com/hd/MPS-2019-15311)|CVE-2019-10174|高危|
|Apache Struts2 代码问题漏洞|任意文件上传|[MPS-2019-15870](https://www.oscs1024.com/hd/MPS-2019-15870)|CVE-2012-1592|高危|
|SnakeYAML <1.26 存在 Billion laughs 漏洞|拒绝服务|[MPS-2019-16129](https://www.oscs1024.com/hd/MPS-2019-16129)|CVE-2017-18640|高危|
|npm CLI 任意文件写入漏洞|UNIX符号链接跟随|[MPS-2019-16248](https://www.oscs1024.com/hd/MPS-2019-16248)|CVE-2019-16775|中危|
|npm CLI 路径遍历漏洞|路径遍历|[MPS-2019-16249](https://www.oscs1024.com/hd/MPS-2019-16249)|CVE-2019-16776|高危|
|npm CLI node_modules二进制文件覆盖漏洞|权限管理不当|[MPS-2019-16250](https://www.oscs1024.com/hd/MPS-2019-16250)|CVE-2019-16777|中危|
|Apache Log4j SocketServer反序列化漏洞|反序列化|[MPS-2019-17271](https://www.oscs1024.com/hd/MPS-2019-17271)|CVE-2019-17571|严重|
|Eclipse Jetty 信息泄露漏洞|未授权敏感信息泄露|[MPS-2019-4270](https://www.oscs1024.com/hd/MPS-2019-4270)|CVE-2019-10247|中危|
|c3p0 存在拒绝服务漏洞|XML实体扩展|[MPS-2019-4274](https://www.oscs1024.com/hd/MPS-2019-4274)|CVE-2019-5427|高危|
|lodash <4.7.11 正则表达式拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2019-8123](https://www.oscs1024.com/hd/MPS-2019-8123)|CVE-2019-1010266|中危|
|Gitea 跨站脚本漏洞|XSS|[MPS-2019-8181](https://www.oscs1024.com/hd/MPS-2019-8181)|CVE-2019-1010261|中危|
|lodash 原型污染漏洞|拒绝服务|[MPS-2019-8636](https://www.oscs1024.com/hd/MPS-2019-8636)|CVE-2019-10744|严重|
|Red Hat Infinispan 授权问题漏洞|会话固定|[MPS-2020-0016](https://www.oscs1024.com/hd/MPS-2020-0016)|CVE-2019-10158|严重|
|Spring Framework <6.0.0 远程代码执行漏洞|反序列化|[MPS-2020-0057](https://www.oscs1024.com/hd/MPS-2020-0057)|CVE-2016-1000027|严重|
|npm bl 内存泄露漏洞|越界读取|[MPS-2020-12199](https://www.oscs1024.com/hd/MPS-2020-12199)|CVE-2020-8244|中危|
|grunt 代码注入漏洞|资源默认不安全|[MPS-2020-12425](https://www.oscs1024.com/hd/MPS-2020-12425)|CVE-2020-7729|高危|
|Apache Struts 存在代码执行漏洞|动态确定对象属性修改的控制不恰当|[MPS-2020-12917](https://www.oscs1024.com/hd/MPS-2020-12917)|CVE-2019-0230|严重|
|Apache Struts 存在拒绝服务漏洞|权限预留不恰当|[MPS-2020-12918](https://www.oscs1024.com/hd/MPS-2020-12918)|CVE-2019-0233|高危|
|NPM npm-user-validate 安全漏洞|拒绝服务|[MPS-2020-14933](https://www.oscs1024.com/hd/MPS-2020-14933)|CVE-2020-7754|高危|
|lodash <4.17.15 原型污染漏洞|原型污染|[MPS-2020-15679](https://www.oscs1024.com/hd/MPS-2020-15679)|CVE-2020-8203|高危|
|Mhart Stringstream < 0.0.6 缓冲区错误漏洞|越界读取|[MPS-2020-16658](https://www.oscs1024.com/hd/MPS-2020-16658)|CVE-2018-21270|中危|
|hibernate-core <5.4.24.Final 存在 SQL 注入漏洞|SQL注入|[MPS-2020-16768](https://www.oscs1024.com/hd/MPS-2020-16768)|CVE-2020-25638|高危|
|Red Hat Infinispan 访问控制错误漏洞|授权检查缺失|[MPS-2020-16840](https://www.oscs1024.com/hd/MPS-2020-16840)|CVE-2020-25711|中危|
|Apache Struts 存在代码注入漏洞|表达式语言注入|[MPS-2020-17188](https://www.oscs1024.com/hd/MPS-2020-17188)|CVE-2020-17530|严重|
|dot-prop 原型污染漏洞|原型污染|[MPS-2020-1734](https://www.oscs1024.com/hd/MPS-2020-1734)|CVE-2020-8116|高危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Ini <1.3.6原型污染漏洞|拒绝服务|[MPS-2020-17544](https://www.oscs1024.com/hd/MPS-2020-17544)|CVE-2020-7788|高危|
|Lxml 跨站脚本漏洞|XSS|[MPS-2020-17664](https://www.oscs1024.com/hd/MPS-2020-17664)|CVE-2020-27783|中危|
|Cowboy Getobject 安全漏洞|原型污染|[MPS-2020-18070](https://www.oscs1024.com/hd/MPS-2020-18070)|CVE-2020-28282|严重|
|undefsafe 注入漏洞|注入|[MPS-2020-2617](https://www.oscs1024.com/hd/MPS-2020-2617)|CVE-2019-10795|中危|
|Apache Struts 跨站脚本漏洞|XSS|[MPS-2020-2933](https://www.oscs1024.com/hd/MPS-2020-2933)|CVE-2015-2992|中危|
|minimist 原型污染漏洞|原型污染|[MPS-2020-3516](https://www.oscs1024.com/hd/MPS-2020-3516)|CVE-2020-7598|中危|
|BSON 序列化绕过漏洞|反序列化|[MPS-2020-4726](https://www.oscs1024.com/hd/MPS-2020-4726)|CVE-2020-7610|严重|
|js-bson <1.1.4  不可信数据的反序列化漏洞|反序列化|[MPS-2020-4759](https://www.oscs1024.com/hd/MPS-2020-4759)|CVE-2019-2391|中危|
|Apache Log4j2 SmtpAppender证书验证不当漏洞|证书验证不恰当|[MPS-2020-6684](https://www.oscs1024.com/hd/MPS-2020-6684)|CVE-2020-9488|低危|
|dom4j SaxReader函数存在 XXE 漏洞|XXE|[MPS-2020-6967](https://www.oscs1024.com/hd/MPS-2020-6967)|CVE-2020-10683|严重|
|hibernate-validator 存在输入验证错误漏洞|代码注入|[MPS-2020-7077](https://www.oscs1024.com/hd/MPS-2020-7077)|CVE-2020-10693|中危|
|Apache Ant 临时文件不安全问题|将资源暴露给错误范围|[MPS-2020-7418](https://www.oscs1024.com/hd/MPS-2020-7418)|CVE-2020-1945|中危|
|httplib2 注入漏洞|CRLF注入|[MPS-2020-7623](https://www.oscs1024.com/hd/MPS-2020-7623)|CVE-2020-11078|中危|
|Gitea 安全漏洞|加锁机制不恰当|[MPS-2020-7624](https://www.oscs1024.com/hd/MPS-2020-7624)|CVE-2020-13246|高危|
|node-dns-sync 代码注入漏洞|命令注入|[MPS-2020-7915](https://www.oscs1024.com/hd/MPS-2020-7915)|CVE-2020-11079|严重|
|websocket-extensions<0.1.4 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2020-8041](https://www.oscs1024.com/hd/MPS-2020-8041)|CVE-2020-7662|高危|
|websocket-extensions 拒绝服务漏洞|拒绝服务|[MPS-2020-8042](https://www.oscs1024.com/hd/MPS-2020-8042)|CVE-2020-7663|高危|
|chownr package竞争条件问题漏洞|检查时间与使用时间(TOCTOU)的竞争条件|[MPS-2020-8858](https://www.oscs1024.com/hd/MPS-2020-8858)|CVE-2017-18869|低危|
|Hibernate 存在 SQL 注入漏洞|SQL注入|[MPS-2020-9908](https://www.oscs1024.com/hd/MPS-2020-9908)|CVE-2019-14900|中危|
|npm CLI 日志信息泄露漏洞|日志敏感信息泄露|[MPS-2020-9965](https://www.oscs1024.com/hd/MPS-2020-9965)|CVE-2020-15095|中危|
|httplib2 资源管理错误漏洞|拒绝服务|[MPS-2021-10429](https://www.oscs1024.com/hd/MPS-2021-10429)|CVE-2021-21240|高危|
|jsoup <1.14.2 存在拒绝服务漏洞||[MPS-2021-17634](https://www.oscs1024.com/hd/MPS-2021-17634)|CVE-2021-37714|高危|
|Spring Framework <5.3.14 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18854](https://www.oscs1024.com/hd/MPS-2021-18854)|CVE-2021-22060|中危|
|Pivotal Spring Framework 日志注入漏洞|日志输出的转义处理不恰当|[MPS-2021-18890](https://www.oscs1024.com/hd/MPS-2021-18890)|CVE-2021-22096|中危|
|colors.js  >1.4.0 DOS漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-19606](https://www.oscs1024.com/hd/MPS-2021-19606)|CVE-2021-23567|高危|
|jsonpointer <5.0.0 原型污染漏洞 |使用不兼容类型访问资源（类型混淆）|[MPS-2021-19846](https://www.oscs1024.com/hd/MPS-2021-19846)|CVE-2021-23807|严重|
|Apache Struts 存在远程代码执行漏洞|表达式语言注入|[MPS-2021-24003](https://www.oscs1024.com/hd/MPS-2021-24003)|CVE-2021-31805|严重|
|lodash 拒绝服务漏洞|拒绝服务|[MPS-2021-2574](https://www.oscs1024.com/hd/MPS-2021-2574)|CVE-2020-28500|中危|
|lodash 命令注入漏洞|代码注入|[MPS-2021-2638](https://www.oscs1024.com/hd/MPS-2021-2638)|CVE-2021-23337|高危|
|Npm Node-tar 后置链接漏洞||[MPS-2021-28486](https://www.oscs1024.com/hd/MPS-2021-28486)|CVE-2021-37701|高危|
|Npm Node-tar 后置链接漏洞||[MPS-2021-28488](https://www.oscs1024.com/hd/MPS-2021-28488)|CVE-2021-37712|高危|
|node-tar 路径遍历漏洞|路径遍历|[MPS-2021-28489](https://www.oscs1024.com/hd/MPS-2021-28489)|CVE-2021-37713|高危|
|Apache Velocity <3.1 存在跨站脚本（XSS）漏洞|XSS|[MPS-2021-2975](https://www.oscs1024.com/hd/MPS-2021-2975)|CVE-2020-13959|中危|
|inflect 正则表达式拒绝服务漏洞|ReDoS|[MPS-2021-32311](https://www.oscs1024.com/hd/MPS-2021-32311)|CVE-2021-3820|高危|
|Lxml 跨站脚本漏洞|XSS|[MPS-2021-3272](https://www.oscs1024.com/hd/MPS-2021-3272)|CVE-2021-28957|中危|
|Ruy Adorno hosted-git-info 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-3400](https://www.oscs1024.com/hd/MPS-2021-3400)|CVE-2021-23362|中危|
|Async 原型污染漏洞|原型污染|[MPS-2021-34434](https://www.oscs1024.com/hd/MPS-2021-34434)|CVE-2021-43138|高危|
|json-schema 安全漏洞|原型污染|[MPS-2021-34478](https://www.oscs1024.com/hd/MPS-2021-34478)|CVE-2021-3918|严重|
|Npm is-my-json-valid 资源管理错误漏洞|拒绝服务|[MPS-2021-3563](https://www.oscs1024.com/hd/MPS-2021-3563)|CVE-2018-1107|中危|
|org.webjars.bower:underscore 代码注入漏洞|代码注入|[MPS-2021-3658](https://www.oscs1024.com/hd/MPS-2021-3658)|CVE-2021-23358|高危|
|braces <2.3.1 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-3692](https://www.oscs1024.com/hd/MPS-2021-3692)|CVE-2018-1109|中危|
|lxml  注入漏洞||[MPS-2021-36943](https://www.oscs1024.com/hd/MPS-2021-36943)|CVE-2021-43818|高危|
|marked 存在拒绝服务漏洞||[MPS-2021-37038](https://www.oscs1024.com/hd/MPS-2021-37038)|CVE-2022-21680|高危|
|marked 存在拒绝服务漏洞|过度严格的正则表达式|[MPS-2021-37039](https://www.oscs1024.com/hd/MPS-2021-37039)|CVE-2022-21681|高危|
|Apache Log4j JMSAppender反序列化漏洞||[MPS-2021-38359](https://www.oscs1024.com/hd/MPS-2021-38359)|CVE-2021-4104|高危|
|minimist 安全漏洞|原型污染|[MPS-2021-38405](https://www.oscs1024.com/hd/MPS-2021-38405)|CVE-2021-44906|严重|
|Eclipse Jetty 资源管理错误漏洞|对异常条件的处理不恰当|[MPS-2021-3864](https://www.oscs1024.com/hd/MPS-2021-3864)|CVE-2021-28165|高危|
|Gitea 安全漏洞|解释冲突|[MPS-2021-39086](https://www.oscs1024.com/hd/MPS-2021-39086)|CVE-2021-45327|严重|
|Gitea 跨站请求伪造漏洞|跨站重定向|[MPS-2021-39087](https://www.oscs1024.com/hd/MPS-2021-39087)|CVE-2021-45328|中危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|npm path-parse 安全漏洞|拒绝服务|[MPS-2021-6165](https://www.oscs1024.com/hd/MPS-2021-6165)|CVE-2021-23343|高危|
|ws 存在拒绝服务漏洞||[MPS-2021-7109](https://www.oscs1024.com/hd/MPS-2021-7109)|CVE-2021-32640|中危|
|trim-newlines 存在拒绝服务漏洞|拒绝服务|[MPS-2021-7398](https://www.oscs1024.com/hd/MPS-2021-7398)|CVE-2021-33623|高危|
|glob-parent < 5.1.2 存在拒绝服务漏洞|拒绝服务|[MPS-2021-7827](https://www.oscs1024.com/hd/MPS-2021-7827)|CVE-2020-28469|高危|
|Eclipse Jetty 存在信息泄露漏洞|不充分的会话过期机制|[MPS-2021-8884](https://www.oscs1024.com/hd/MPS-2021-8884)|CVE-2021-34428|低危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9827](https://www.oscs1024.com/hd/MPS-2021-9827)|CVE-2021-36373|中危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9847](https://www.oscs1024.com/hd/MPS-2021-9847)|CVE-2021-36374|中危|
|shelljs < 0.8.5 存在特权管理不恰当漏洞|权限管理不当|[MPS-2022-0508](https://www.oscs1024.com/hd/MPS-2022-0508)|CVE-2022-0144|高危|
|Pivotal Spring Framework 安全限制绕过漏洞|大小写敏感处理不恰当|[MPS-2022-1098](https://www.oscs1024.com/hd/MPS-2022-1098)|CVE-2022-22968|中危|
|Spring Framework spring-beans 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-1101](https://www.oscs1024.com/hd/MPS-2022-1101)|CVE-2022-22970|中危|
|org.testng:testng 存在不安全的依赖解析漏洞||[MPS-2022-11842](https://www.oscs1024.com/hd/MPS-2022-11842)||中危|
|org.freemarker:freemarker <2.3.30 存在代码注入漏洞|代码注入|[MPS-2022-12438](https://www.oscs1024.com/hd/MPS-2022-12438)||高危|
|Apache Commons Collections 远程代码执行漏洞|反序列化|[MPS-2022-12767](https://www.oscs1024.com/hd/MPS-2022-12767)||高危|
|marked < 0.3.9 存在跨站脚本漏洞|XSS|[MPS-2022-12984](https://www.oscs1024.com/hd/MPS-2022-12984)||高危|
|marked < 0.3.9 存在跨站脚本漏洞|XSS|[MPS-2022-12985](https://www.oscs1024.com/hd/MPS-2022-12985)||中危|
|marked < 0.3.18 存在拒绝服务漏洞||[MPS-2022-12986](https://www.oscs1024.com/hd/MPS-2022-12986)||高危|
|github.com/go-gitea/gitea 存在跨站重定向漏洞|跨站重定向|[MPS-2022-13366](https://www.oscs1024.com/hd/MPS-2022-13366)||中危|
|github.com/go-gitea/gitea 存在CSRF漏洞|CSRF|[MPS-2022-13367](https://www.oscs1024.com/hd/MPS-2022-13367)||高危|
|adm-zip <0.5.2存在路径遍历漏洞|路径遍历|[MPS-2022-13529](https://www.oscs1024.com/hd/MPS-2022-13529)||高危|
|helmet-csp 存在配置漏洞|配置缺陷|[MPS-2022-13752](https://www.oscs1024.com/hd/MPS-2022-13752)||中危|
|is-my-json-valid 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13795](https://www.oscs1024.com/hd/MPS-2022-13795)||高危|
|is-my-json-valid<2.20.3 存在代码注入漏洞|代码注入|[MPS-2022-13796](https://www.oscs1024.com/hd/MPS-2022-13796)||高危|
|istanbul-reports<3.1.3 反向 Tabnabbing漏洞|通过 window.opener 访问使用指向不受信任目标的 Web 链接|[MPS-2022-13797](https://www.oscs1024.com/hd/MPS-2022-13797)||中危|
|js-beautify<1.14.1 存在ReDoS漏洞|ReDoS|[MPS-2022-13810](https://www.oscs1024.com/hd/MPS-2022-13810)||中危|
|jsonpointer<4.1.0 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13815](https://www.oscs1024.com/hd/MPS-2022-13815)||严重|
|js-yaml 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13820](https://www.oscs1024.com/hd/MPS-2022-13820)||中危|
|js-yaml<3.13.1 存在代码注入漏洞|代码注入|[MPS-2022-13822](https://www.oscs1024.com/hd/MPS-2022-13822)||高危|
|lodash<4.17.20 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13841](https://www.oscs1024.com/hd/MPS-2022-13841)||高危|
|lodash<4.17.17 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13842](https://www.oscs1024.com/hd/MPS-2022-13842)||高危|
|marked 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13861](https://www.oscs1024.com/hd/MPS-2022-13861)||中危|
|marked<0.4.0 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13863](https://www.oscs1024.com/hd/MPS-2022-13863)||中危|
|marked<1.1.1 存在ReDoS漏洞|ReDoS|[MPS-2022-13864](https://www.oscs1024.com/hd/MPS-2022-13864)||中危|
|minimatch < 3.0.2 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13882](https://www.oscs1024.com/hd/MPS-2022-13882)||高危|
|mocha < 6.0.0 存在ReDos漏洞|不正确的正则表达式|[MPS-2022-13886](https://www.oscs1024.com/hd/MPS-2022-13886)||中危|
|mongodb 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13888](https://www.oscs1024.com/hd/MPS-2022-13888)||高危|
|uglify-js <3.14.3 正则表达式拒绝服务漏洞|ReDoS|[MPS-2022-14112](https://www.oscs1024.com/hd/MPS-2022-14112)||中危|
|Apache Log4j JDBCAppender SQL注入漏洞|SQL注入|[MPS-2022-1444](https://www.oscs1024.com/hd/MPS-2022-1444)|CVE-2022-23305|严重|
|Apache Log4j Chainsaw反序列化漏洞|反序列化|[MPS-2022-1445](https://www.oscs1024.com/hd/MPS-2022-1445)|CVE-2022-23307|高危|
|Apache Log4j 反序列化漏洞|反序列化|[MPS-2022-1446](https://www.oscs1024.com/hd/MPS-2022-1446)|CVE-2022-23302|高危|
|httplib2 存在CRLF注入漏洞|CRLF注入|[MPS-2022-14942](https://www.oscs1024.com/hd/MPS-2022-14942)||高危|
|lxml 存在路径遍历漏洞|路径遍历|[MPS-2022-14974](https://www.oscs1024.com/hd/MPS-2022-14974)||中危|
|spyne 存在ReDoS漏洞|ReDoS|[MPS-2022-15156](https://www.oscs1024.com/hd/MPS-2022-15156)||中危|
|commons-fileupload:commons-fileupload 存在信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-16625](https://www.oscs1024.com/hd/MPS-2022-16625)||中危|
|Go-Ethereum 代码问题漏洞|拒绝服务|[MPS-2022-1762](https://www.oscs1024.com/hd/MPS-2022-1762)|CVE-2022-23328|高危|
|Eclipse Jetty URI注入漏洞|注入|[MPS-2022-18060](https://www.oscs1024.com/hd/MPS-2022-18060)|CVE-2022-2047|低危|
|Certifi 存在数据真实性验证不充分漏洞|对数据真实性的验证不充分|[MPS-2022-1918](https://www.oscs1024.com/hd/MPS-2022-1918)|CVE-2022-23491|中危|
|got 存在打开重定向漏洞|跨站重定向|[MPS-2022-19247](https://www.oscs1024.com/hd/MPS-2022-19247)|CVE-2022-33987|中危|
|Grunt 路径遍历漏洞|路径遍历|[MPS-2022-2996](https://www.oscs1024.com/hd/MPS-2022-2996)|CVE-2022-0436|中危|
|Express 中的 qs 模块存在原型污染漏洞|原型污染|[MPS-2022-3967](https://www.oscs1024.com/hd/MPS-2022-3967)|CVE-2022-24999|高危|
|lxml 和 libxml2 代码问题漏洞|空指针取消引用|[MPS-2022-46661](https://www.oscs1024.com/hd/MPS-2022-46661)|CVE-2022-2309|高危|
|nconf<0.11.4 原型污染漏洞|原型污染|[MPS-2022-5061](https://www.oscs1024.com/hd/MPS-2022-5061)|CVE-2022-21803|高危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|jsoup <1.15.3 存在反射型 XSS 漏洞|XSS|[MPS-2022-51547](https://www.oscs1024.com/hd/MPS-2022-51547)|CVE-2022-36033|中危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|mocha ReDoS 漏洞|ReDoS|[MPS-2022-54598](https://www.oscs1024.com/hd/MPS-2022-54598)||高危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|Python 安全漏洞|ReDoS|[MPS-2022-57238](https://www.oscs1024.com/hd/MPS-2022-57238)|CVE-2022-40897|中危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|minimatch 资源管理错误漏洞|拒绝服务|[MPS-2022-59845](https://www.oscs1024.com/hd/MPS-2022-59845)|CVE-2022-3517|高危|
|TestNG <7.7.0  存在路径遍历（Zip Slip）漏洞|路径遍历|[MPS-2022-64736](https://www.oscs1024.com/hd/MPS-2022-64736)|CVE-2022-4065|高危|
|H2 数据库明文密码问题|未授权敏感信息泄露|[MPS-2022-65204](https://www.oscs1024.com/hd/MPS-2022-65204)|CVE-2022-45868|高危|
|Gitea 安全漏洞|跨站重定向|[MPS-2022-6779](https://www.oscs1024.com/hd/MPS-2022-6779)|CVE-2022-1058|中危|
|spring-beans 远程代码执行漏洞(Spring4Shell)|表达式语言注入|[MPS-2022-6820](https://www.oscs1024.com/hd/MPS-2022-6820)|CVE-2022-22965|严重|
|hawk 资源管理错误漏洞|拒绝服务|[MPS-2022-8568](https://www.oscs1024.com/hd/MPS-2022-8568)|CVE-2022-29167|高危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Grunt 安全漏洞|检查时间与使用时间(TOCTOU)的竞争条件|[MPS-2022-9621](https://www.oscs1024.com/hd/MPS-2022-9621)|CVE-2022-1537|高危|
|vercel ms 安全漏洞|ReDoS|[MPS-2023-0304](https://www.oscs1024.com/hd/MPS-2023-0304)|CVE-2017-20162|中危|
|debug 安全漏洞|ReDoS|[MPS-2023-0646](https://www.oscs1024.com/hd/MPS-2023-0646)|CVE-2017-20165|高危|
|Apache Commons FileUpload <1.5 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2023-3553](https://www.oscs1024.com/hd/MPS-2023-3553)|CVE-2023-24998|中危|
|swig 安全漏洞|路径遍历|[MPS-2023-3992](https://www.oscs1024.com/hd/MPS-2023-3992)|CVE-2023-25345|高危|
|xml2js 安全漏洞|原型污染|[MPS-2023-4673](https://www.oscs1024.com/hd/MPS-2023-4673)|CVE-2023-0842|中危|
|Eclipse Jetty 资源管理错误漏洞|拒绝服务|[MPS-2023-4997](https://www.oscs1024.com/hd/MPS-2023-4997)|CVE-2023-26048|中危|
|Eclipse Jetty 信息泄露漏洞|XSS|[MPS-2023-4998](https://www.oscs1024.com/hd/MPS-2023-4998)|CVE-2023-26049|中危|
|tough-cookie 安全漏洞|原型污染|[MPS-2023-5130](https://www.oscs1024.com/hd/MPS-2023-5130)|CVE-2023-26136|严重|
|request SSRF防御绕过漏洞|SSRF|[MPS-2023-7722](https://www.oscs1024.com/hd/MPS-2023-7722)|CVE-2023-28155|中危|
|Certifi 数据伪造问题漏洞|对数据真实性的验证不充分|[MPS-ck78-r6zg](https://www.oscs1024.com/hd/MPS-ck78-r6zg)|CVE-2023-37920|严重|
|tough-cookie<4.1.3 存在原型污染漏洞|原型污染|[MPS-esyq-56vx](https://www.oscs1024.com/hd/MPS-esyq-56vx)||中危|
|Requests Proxy-Authorization 标头泄露漏洞|未授权敏感信息泄露|[MPS-hr61-tzey](https://www.oscs1024.com/hd/MPS-hr61-tzey)|CVE-2023-32681|中危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|Struts 2 列表边界检查不当导致拒绝服务漏洞|不加限制或调节的资源分配|[MPS-yi5s-rzc0](https://www.oscs1024.com/hd/MPS-yi5s-rzc0)|CVE-2023-34149|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|commons-beanutils:commons-beanutils|1.8.3|1.9.4|直接依赖|强烈建议修复|C:0|H:2|M:0|L:0|
|org.apache.struts:struts2-core|2.1.2|6.1.2.1|直接依赖|强烈建议修复|C:15|H:7|M:16|L:1|
|commons-fileupload:commons-fileupload|1.2.1|1.5|直接依赖|强烈建议修复|C:1|H:2|M:2|L:1|
|growl|1.9.2|1.10.0|间接依赖|强烈建议修复|C:1|H:0|M:0|L:0|
|org.springframework:spring-core|2.0.7|6.0.7|直接依赖|建议修复|C:0|H:1|M:2|L:0|
|org.yaml:snakeyaml|1.9|2.0|直接依赖|建议修复|C:0|H:3|M:4|L:1|
|underscore|1.12.0|1.13.0-2|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-http|7.6.0.RC4|11.0.10|直接依赖|建议修复|C:2|H:0|M:0|L:1|
|qs|6.5.1|6.10.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.freemarker:freemarker|2.3.12|2.3.30|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|hawk|1.0.0|9.0.1|直接依赖|建议修复|C:0|H:2|M:0|L:0|
|grunt|1.0.1|1.5.3|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|nconf|0.6.9|0.11.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.codehaus.jackson:jackson-mapper-asl|1.7.3||间接依赖|建议修复|C:1|H:1|M:0|L:0|
|tough-cookie|2.5.0|4.1.3|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.hibernate:hibernate-core|3.6.6.Final|5.4.24.Final|直接依赖|建议修复|C:0|H:1|M:1|L:0|
|tough-cookie|2.3.4|4.1.3|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|grunt|1.3.0|1.5.3|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|http-signature|1.1.1||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|glob-parent|2.0.0|6.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|timespan|2.3.0||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|npm|3.10.10|6.14.6|间接依赖|建议修复|C:0|H:2|M:3|L:0|
|mime|1.2.11|2.0.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|dom4j:dom4j|1.6.1||直接依赖|建议修复|C:1|H:0|M:0|L:0|
|qs|6.5.2|6.10.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|js-yaml|3.5.5|3.13.1|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|qs|6.9.4|6.10.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tough-cookie|2.2.2|4.1.3|间接依赖|建议修复|C:1|H:1|M:1|L:0|
|i|0.3.6|0.3.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|express|4.16.2|4.17.3|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-web|2.0.7|6.0.0|直接依赖|建议修复|C:1|H:1|M:0|L:0|
|npm-user-validate|0.1.5|1.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|http-signature|1.2.0||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|bson|1.0.4|1.1.4|间接依赖|建议修复|C:1|H:1|M:1|L:0|
|log4j:log4j|1.2.9||间接依赖|建议修复|C:2|H:3|M:0|L:1|
|minimist|0.0.8|1.2.6|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|marked|0.3.5|4.0.10|直接依赖|建议修复|C:0|H:5|M:6|L:0|
|org.infinispan:infinispan-core|4.2.1.CR1|11.0.6.Final|直接依赖|建议修复|C:1|H:2|M:1|L:0|
|mongodb|2.2.33|3.1.13|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|suds-jurko|0.6||间接依赖|建议修复|C:0|H:0|M:0|L:1|
|debug|2.2.0|3.1.0|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|github.com/ethereum/go-ethereum|v1.8.17||直接依赖|建议修复|C:0|H:1|M:0|L:0|
|dns-sync|0.1.3|0.2.1|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|uglify-js|2.4.24|3.14.3|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|org.eclipse.jetty:jetty-server|7.6.0.RC4|12.0.0.beta0|直接依赖|建议修复|C:0|H:0|M:4|L:1|
|express|4.17.1|4.17.3|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.eclipse.jetty:jetty-util|7.6.0.RC4|9.4.17.v20190418|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|minimatch|3.0.4|3.0.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.15.2||直接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-beans|3.0.0.RELEASE|5.3.20|直接依赖|建议修复|C:1|H:0|M:1|L:0|
|requests|2.19.1|2.31.0|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|deep-extend|0.4.2|0.5.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|sshpk|1.13.1|1.14.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|certifi|2018.4.16|2023.7.22|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|tough-cookie|2.3.3|4.1.3|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|minimatch|0.3.0|3.0.5|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|log4j:log4j|1.2.16||直接依赖|建议修复|C:2|H:3|M:0|L:1|
|github.com/go-gitea/gitea|v1.5.0|1.16.5|直接依赖|建议修复|C:2|H:2|M:4|L:0|
|shelljs|0.5.3|0.8.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|colors|1.4.0||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|mongodb|2.2.36|3.1.13|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|ini|1.3.5|1.3.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|lodash|4.17.4|4.17.21|间接依赖|建议修复|C:1|H:4|M:4|L:0|
|com.opensymphony:xwork|2.1.1|2.1.2|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|websocket-extensions|0.1.3|0.1.4|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|jsonpointer|4.0.1|5.0.0|间接依赖|建议修复|C:2|H:0|M:0|L:0|
|lxml|4.2.1|4.9.1|间接依赖|建议修复|C:0|H:2|M:4|L:0|
|qs|6.7.0|6.10.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-core|3.0.0.RELEASE|6.0.7|间接依赖|建议修复|C:0|H:1|M:5|L:0|
|mocha|2.5.3|6.0.0|直接依赖|建议修复|C:0|H:1|M:1|L:0|
|org.springframework:spring-context|2.0.7|5.3.19|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|minimist|1.2.0|1.2.6|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.eclipse.jetty:jetty-io|7.6.0.RC4|11.0.10|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.beanshell:bsh|2.0b4||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|swig|1.4.2||直接依赖|建议修复|C:0|H:1|M:0|L:0|
|dot-prop|4.2.0|5.1.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|hoek|2.16.3|5.0.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tar|2.2.2|6.1.9|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|qs|6.2.3|6.10.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|http-signature|0.10.1||直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.springframework:spring-beans|2.0.7|5.3.20|直接依赖|建议修复|C:1|H:0|M:1|L:0|
|adm-zip|0.4.4|0.5.2|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|minimist|0.0.10|1.2.6|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|hoek|0.9.1|5.0.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|path-parse|1.0.6|1.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|extend|3.0.1|3.0.2|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|js-yaml|3.6.1|3.13.1|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|minimist|1.2.5|1.2.6|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|jsonpointer|4.1.0|5.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.jboss.netty:netty|3.2.4.Final||直接依赖|建议修复|C:0|H:1|M:0|L:0|
|trim-newlines|1.0.0|4.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|is-my-json-valid|2.16.1|2.20.3|间接依赖|建议修复|C:0|H:3|M:1|L:0|
|getobject|0.1.0|1.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|underscore|1.8.3|1.13.0-2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|commons-collections:commons-collections|3.1|3.2.2|直接依赖|建议修复|C:1|H:2|M:0|L:0|
|commons-collections:commons-collections|3.2.1|3.2.2|间接依赖|建议修复|C:1|H:2|M:0|L:0|
|bson|1.0.9|1.1.4|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|hawk|3.1.3|9.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|lodash|2.4.2|4.17.21|间接依赖|建议修复|C:1|H:4|M:4|L:0|
|org.codehaus.jackson:jackson-mapper-asl|1.9.3||直接依赖|建议修复|C:1|H:1|M:0|L:0|
|commons-beanutils:commons-beanutils|1.7.0|1.9.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|c3p0:c3p0|0.9.1||直接依赖|建议修复|C:1|H:1|M:0|L:0|
|httplib2|0.11.3|0.19.0|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|glob-parent|3.1.0|6.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|shelljs|0.3.0|0.8.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tough-cookie|4.0.0|4.1.3|直接依赖|建议修复|C:1|H:0|M:1|L:0|
|json-schema|0.2.3|0.4.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|log4j:log4j|1.2.12||直接依赖|建议修复|C:2|H:3|M:0|L:1|
|undefsafe|0.0.3|2.0.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|uglify-js|3.12.4|3.14.3|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|request|2.79.0||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|5.7.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|async|2.6.3|3.2.2|直接依赖|可选修复|C:0|H:1|M:0|L:0|
|async|2.6.0|3.2.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|bl|1.1.2|4.0.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.springframework:spring-aop|2.0.7|2.5.6.SEC01|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|11.0.1|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:2|L:1|
|stringstream|0.0.5|0.0.6|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.bouncycastle:bcprov-jdk18on|1.71|1.74|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|spyne|2.12.14|2.14.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.ant:ant|1.7.0|1.10.11|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|qs|5.2.1|6.10.3|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|semver|7.3.4|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|ms|0.7.1|2.0.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|request|2.88.2||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|qs|0.6.6|6.10.3|间接依赖|可选修复|C:0|H:2|M:1|L:0|
|istanbul-reports|1.5.1|3.1.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|lodash|4.17.20|4.17.21|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|setuptools|39.2.0|65.5.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|ws|1.1.5|7.4.6|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|js-beautify|1.13.0|1.14.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|commons-io:commons-io|1.3.2|2.7|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|xml2js|0.4.4|0.5.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|5.3.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.velocity:velocity-tools|1.3||直接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|5.4.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|chownr|1.0.1|1.1.0|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|js-beautify|1.7.4|1.14.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|helmet-csp|1.2.2|2.9.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|braces|1.8.5|2.3.1|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.hibernate:hibernate-validator|4.2.0.Final|6.1.3.Final|直接依赖|可选修复|C:0|H:0|M:3|L:0|
|got|6.7.1|12.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|bl|1.0.3|4.0.3|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|request|2.67.0|2.68.0|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.jsoup:jsoup|1.5.2|1.15.3|直接依赖|可选修复|C:0|H:1|M:2|L:0|
|request|2.36.0|2.68.0|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|hosted-git-info|2.8.8|3.0.8|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.testng:testng|5.1|7.7.0|直接依赖|可选修复|C:0|H:1|M:1|L:0|
|hosted-git-info|2.5.0|3.0.8|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.h2database:h2|2.1.214||直接依赖|可选修复|C:0|H:1|M:0|L:0|
|hosted-git-info|2.1.5|3.0.8|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|request|2.75.0||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|724|Low|
|自定义许可证|48|Low|
|CDDL-1.1|5|Low|
|ISC|124|Low|
|Apache-2.0|165|Low|
|BSD-3-Clause|47|Low|
|BSD-2-Clause|21|Low|
|EPL-2.0|2|Low|
|LGPL-3.0|2|Medium|
|GPL-3.0|1|Medium|
|CC-BY-3.0|1|Low|
|CC0-1.0|1|Low|
|BSD|3|Low|
|LGPL-2.1|3|Medium|
|GPL-3.0-or-later|1|Low|
|EPL-1.0|4|Low|
|Artistic-2.0|1|Low|
|MPL-2.0|2|Low|
|Public Domain|1|Low|
|Unlicense|2|Low|
|BSD-like|1|Low|
|Apache 2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.semver4j:semver4j|5.1.0|直接依赖|maven|
|org.bouncycastle:bcprov-jdk18on|1.71|间接依赖|maven|
|com.sun.jersey:jersey-server|1.11|直接依赖|maven|
|is-extglob|1.0.0|间接依赖|npm|
|grunt-legacy-log-utils|2.1.0|间接依赖|npm|
|stream-combiner|0.0.4|直接依赖|npm|
|wide-align|1.1.3|间接依赖|npm|
|ms|2.1.3|间接依赖|npm|
|tmp|0.0.24|间接依赖|npm|
|suds-jurko|0.6|间接依赖|pip|
|ajv|6.12.6|间接依赖|npm|
|kind-of|6.0.3|间接依赖|npm|
|mongodb|2.2.33|直接依赖|npm|
|es-abstract|1.17.7|间接依赖|npm|
|forever-agent|0.5.2|间接依赖|npm|
|safe-buffer|5.2.0|间接依赖|npm|
|lodash._baseassign|3.2.0|间接依赖|npm|
|braces|1.8.5|直接依赖|npm|
|lodash.isarray|3.0.4|间接依赖|npm|
|boom|0.4.2|间接依赖|npm|
|http-signature|1.1.1|间接依赖|npm|
|Flask-Cors|3.0.6|间接依赖|pip|
|nan|2.14.2|间接依赖|npm|
|org.apache.lucene:lucene-analyzers-common|8.11.2|直接依赖|maven|
|chokidar|2.1.8|间接依赖|npm|
|liftoff|2.5.0|间接依赖|npm|
|nopt|3.0.6|间接依赖|npm|
|org.apache.maven:maven-api-xml|4.0.0-alpha-7|间接依赖|maven|
|dateformat|1.0.12|间接依赖|npm|
|mime-db|1.30.0|间接依赖|npm|
|serve-static|1.14.1|间接依赖|npm|
|mime-types|2.99.1|间接依赖|bundler|
|log4j:log4j|1.2.12|直接依赖|maven|
|underscore|1.8.3|间接依赖|npm|
|normalize-package-data|2.4.0|间接依赖|npm|
|asn1|0.1.11|间接依赖|npm|
|iferr|0.1.5|间接依赖|npm|
|readable-stream|2.0.6|间接依赖|npm|
|sprockets-rails|2.3.3|间接依赖|bundler|
|content-type|1.0.4|间接依赖|npm|
|org.eclipse.packager:packager-core|0.19.0|间接依赖|maven|
|hawk|3.1.3|间接依赖|npm|
|commons-logging:commons-logging|1.0.4|直接依赖|maven|
|umask|1.1.0|间接依赖|npm|
|binary-extensions|1.13.1|间接依赖|npm|
|source-map|0.1.34|间接依赖|npm|
|form-data|1.0.1|间接依赖|npm|
|cryptiles|0.2.2|间接依赖|npm|
|path-parse|1.0.6|间接依赖|npm|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|npm-install-checks|3.0.2|间接依赖|npm|
|lodash.union|4.6.0|间接依赖|npm|
|arr-diff|4.0.0|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|org.jboss:jboss-common-core|2.2.14.GA|间接依赖|maven|
|deep-equal|0.1.2|间接依赖|npm|
|setprototypeof|1.0.3|间接依赖|npm|
|tunnel-agent|0.4.3|直接依赖|npm|
|object.defaults|1.1.0|间接依赖|npm|
|colors|1.1.2|间接依赖|npm|
|chardet|3.0.4|间接依赖|pip|
|readable-stream|2.2.7|间接依赖|npm|
|body-parser|1.18.2|间接依赖|npm|
|globule|1.2.0|间接依赖|npm|
|core-util-is|1.0.2|间接依赖|npm|
|is-ci|1.2.1|间接依赖|npm|
|map-stream|0.1.0|直接依赖|npm|
|com.yammer.metrics:metrics-log4j|2.0.0-RC0|直接依赖|maven|
|hawk|1.0.0|直接依赖|npm|
|extend-shallow|3.0.2|间接依赖|npm|
|zaproxy|0.2.0|直接依赖|npm|
|org.hibernate:hibernate-validator|4.2.0.Final|直接依赖|maven|
|oauth-sign|0.3.0|直接依赖|npm|
|lodash.isarguments|3.1.0|间接依赖|npm|
|json-parse-better-errors|1.0.1|间接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|negotiator|0.6.2|间接依赖|npm|
|unicode-length|1.0.3|间接依赖|npm|
|find-up|1.1.2|间接依赖|npm|
|file-uri-to-path|1.0.0|间接依赖|npm|
|org.apache.maven.shared:maven-shared-utils|3.4.2|间接依赖|maven|
|chokidar|1.7.0|间接依赖|npm|
|arrify|1.0.1|间接依赖|npm|
|com.yammer.metrics:metrics-annotation|2.0.0-RC0|直接依赖|maven|
|asm:asm|3.1|直接依赖|maven|
|combined-stream|1.0.5|间接依赖|npm|
|har-validator|2.0.6|间接依赖|npm|
|coffee-script|1.10.0|间接依赖|npm|
|ultron|1.0.2|间接依赖|npm|
|is-date-object|1.0.2|间接依赖|npm|
|strip-indent|1.0.1|间接依赖|npm|
|is-regex|1.1.1|间接依赖|npm|
|pad-stream|1.2.0|间接依赖|npm|
|org.hibernate:hibernate-commons-annotations|3.2.0.Final|直接依赖|maven|
|call-bind|1.0.0|间接依赖|npm|
|com.github.spullara.mustache.java:compiler|0.9.6|间接依赖|maven|
|winston|0.8.3|间接依赖|npm|
|underscore|1.12.0|直接依赖|npm|
|color-name|1.1.3|间接依赖|npm|
|uri-js|4.4.0|间接依赖|npm|
|org.jsoup:jsoup|1.16.1|直接依赖|maven|
|fill-range|4.0.0|间接依赖|npm|
|commons-digester:commons-digester|2.1|间接依赖|maven|
|safe-json-parse|1.0.1|间接依赖|npm|
|xmlbuilder|15.1.1|间接依赖|npm|
|lodash|2.4.2|间接依赖|npm|
|columnify|1.5.4|间接依赖|npm|
|extend|3.0.2|间接依赖|npm|
|org.mortbay.jetty:jetty-util|6.1.26|间接依赖|maven|
|org.anarres.jdiagnostics:jdiagnostics|1.0.7|直接依赖|maven|
|org.infinispan:infinispan-core|4.2.1.CR1|直接依赖|maven|
|us.springett:cpe-parser|2.0.2|直接依赖|maven|
|escape-string-regexp|1.0.2|间接依赖|npm|
|log-driver|1.2.5|间接依赖|npm|
|process-nextick-args|2.0.1|间接依赖|npm|
|org.apache.commons:commons-pool2|2.10.0|间接依赖|maven|
|com.yammer.dropwizard:dropwizard-core|0.1.3|直接依赖|maven|
|pause-stream|0.0.11|直接依赖|npm|
|foreground-child|1.5.6|间接依赖|npm|
|js-yaml|3.14.1|间接依赖|npm|
|uglifier|2.7.2|间接依赖|bundler|
|org.hibernate:hibernate-core|3.6.6.Final|直接依赖|maven|
|is-my-json-valid|2.20.5|间接依赖|npm|
|sinatra|1.4.4|间接依赖|bundler|
|coffee-script|2.4.1|间接依赖|bundler|
|GoogleToolboxForMac/NSData||间接依赖|cocoapods|
|org.slf4j:jul-to-slf4j|1.6.4|直接依赖|maven|
|fsevents|1.2.13|直接依赖|npm|
|hosted-git-info|2.5.0|间接依赖|npm|
|github.com/ethereum/go-ethereum|v1.8.17|直接依赖|go|
|boom|2.10.1|间接依赖|npm|
|http-signature|1.2.0|间接依赖|npm|
|org.springframework:spring-beans|2.0.7|直接依赖|maven|
|express-session|1.17.1|直接依赖|npm|
|sshpk|1.13.1|间接依赖|npm|
|lodash._isiterateecall|3.0.9|间接依赖|npm|
|unique-string|1.0.0|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|clone|1.0.4|间接依赖|npm|
|aws4|1.6.0|间接依赖|npm|
|ansicolors|0.3.2|间接依赖|npm|
|send|0.16.1|间接依赖|npm|
|express|4.17.1|直接依赖|npm|
|object-inspect|1.9.0|间接依赖|npm|
|is-set|2.0.2|间接依赖|npm|
|base|0.11.2|间接依赖|npm|
|lodash._createset|4.0.3|间接依赖|npm|
|FirebaseCore|5.0.1|间接依赖|cocoapods|
|from|0.1.7|直接依赖|npm|
|filename-regex|2.0.1|间接依赖|npm|
|proxy-addr|2.0.6|间接依赖|npm|
|content-security-policy-builder|1.0.0|间接依赖|npm|
|pytz|2018.4|间接依赖|pip|
|finalhandler|0.4.1|间接依赖|npm|
|only-shallow|1.2.0|间接依赖|npm|
|junit:junit|3.8.2|直接依赖|maven|
|istanbul-lib-report|1.1.5|间接依赖|npm|
|request|2.79.0|间接依赖|npm|
|grunt-if|https://github.com/binarymist/grunt-if/tarball/master|直接依赖|npm|
|object-keys|1.1.1|间接依赖|npm|
|jsonpointer|4.0.1|间接依赖|npm|
|side-channel|1.0.4|间接依赖|npm|
|window-size|0.1.0|间接依赖|npm|
|org.whitesource:pecoff4j|0.0.2.1|直接依赖|maven|
|pinkie-promise|2.0.1|间接依赖|npm|
|loud-rejection|1.6.0|间接依赖|npm|
|isobject|3.0.1|间接依赖|npm|
|mute-stream|0.0.8|间接依赖|npm|
|end-of-stream|1.4.4|间接依赖|npm|
|delayed-stream|0.0.5|间接依赖|npm|
|lodash.keys|3.1.2|间接依赖|npm|
|path-exists|2.1.0|间接依赖|npm|
|npm-cache-filename|1.0.2|间接依赖|npm|
|performance-now|2.1.0|间接依赖|npm|
|Bolts/AppLinks|1.9.0|间接依赖|cocoapods|
|setuptools|39.2.0|间接依赖|pip|
|dot-prop|4.2.1|间接依赖|npm|
|clone|1.0.3|间接依赖|npm|
|validate-npm-package-name|3.0.0|间接依赖|npm|
|org.apache.maven.reporting:maven-reporting-api|3.1.1|直接依赖|maven|
|aproba|1.2.0|间接依赖|npm|
|lodash._createassigner|3.1.1|间接依赖|npm|
|opensymphony:ognl|2.6.11|直接依赖|maven|
|thor|0.19.1|间接依赖|bundler|
|iconv-lite|0.4.19|间接依赖|npm|
|array-unique|0.3.2|间接依赖|npm|
|json-parse-better-errors|1.0.2|间接依赖|npm|
|grunt-contrib-clean|1.1.0|间接依赖|npm|
|test-exclude|1.1.0|间接依赖|npm|
|body-parser|1.19.0|直接依赖|npm|
|glob|7.1.6|间接依赖|npm|
|unique-filename|1.1.1|间接依赖|npm|
|es6-symbol|3.1.3|间接依赖|npm|
|negotiator|0.6.1|间接依赖|npm|
|org.testng:testng|5.1|直接依赖|maven|
|lazy|1.0.11|间接依赖|npm|
|org.freemarker:freemarker|2.3.12|直接依赖|maven|
|node-gyp|3.4.0|间接依赖|npm|
|golang.org/x/crypto|v0.0.0-20200820211705-5c72a883971a|间接依赖|go|
|commander|0.6.1|间接依赖|npm|
|org.slf4j:slf4j-simple|1.6.1|直接依赖|maven|
|http-errors|1.6.2|间接依赖|npm|
|stringstream|0.0.6|间接依赖|npm|
|metaclass|0.0.4|间接依赖|bundler|
|org.slf4j:slf4j-api|1.6.4|直接依赖|maven|
|i|0.3.6|间接依赖|npm|
|htmlparser2|3.8.3|间接依赖|npm|
|graceful-fs|4.2.4|间接依赖|npm|
|unique-slug|2.0.2|间接依赖|npm|
|cliff|0.1.10|间接依赖|npm|
|spdx-exceptions|2.3.0|间接依赖|npm|
|editorconfig|0.15.3|间接依赖|npm|
|ansi-regex|3.0.0|间接依赖|npm|
|asap|2.0.6|间接依赖|npm|
|aspectwerkz:aspectwerkz-core|0.8.1|间接依赖|maven|
|org.hibernate:hibernate-tools|3.2.0.ga|直接依赖|maven|
|bson|1.0.4|间接依赖|npm|
|asynckit|0.4.0|间接依赖|npm|
|json-stringify-safe|5.0.1|间接依赖|npm|
|org.apache.commons:commons-jcs-core|2.2.1|直接依赖|maven|
|form-data|0.1.4|直接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|npmlog|4.0.2|间接依赖|npm|
|camelcase|1.2.1|间接依赖|npm|
|meow|3.7.0|间接依赖|npm|
|process-nextick-args|1.0.7|间接依赖|npm|
|org.sonatype.plexus:plexus-sec-dispatcher|1.4|直接依赖|maven|
|/usr/lib/libc++.1.dylib||间接依赖||
|spdx-license-ids|3.0.7|间接依赖|npm|
|chalk|1.1.3|间接依赖|npm|
|org.sonatype.sisu:sisu-inject-bean|1.4.2|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|split2|1.1.1|间接依赖|npm|
|es6-promise|3.2.1|间接依赖|npm|
|is-extendable|1.0.1|间接依赖|npm|
|pumpify|1.3.5|间接依赖|npm|
|spdx-correct|1.0.2|间接依赖|npm|
|org.springframework:spring-asm|3.0.0.RELEASE|间接依赖|maven|
|accepts|1.3.7|间接依赖|npm|
|grunt-legacy-log|1.0.0|间接依赖|npm|
|com.googlecode.jtype:jtype|0.1.1|直接依赖|maven|
|q|1.5.1|间接依赖|npm|
|junit:junit|3.8.1|直接依赖|maven|
|is-typedarray|1.0.0|间接依赖|npm|
|grunt|1.3.0|间接依赖|npm|
|colors|1.4.0|间接依赖|npm|
|statuses|1.5.0|间接依赖|npm|
|com.google.j2objc:j2objc-annotations|2.8|间接依赖|maven|
|color-convert|1.9.1|直接依赖|npm|
|mime|1.6.0|间接依赖|npm|
|array-filter|1.0.0|间接依赖|npm|
|string-width|2.1.1|间接依赖|npm|
|org.sonatype.ossindex:ossindex-service-client|1.8.2|直接依赖|maven|
|read-package-tree|5.1.6|间接依赖|npm|
|diff|1.4.0|间接依赖|npm|
|qs|5.2.1|间接依赖|npm|
|org.apache.commons:commons-text|1.10.0|直接依赖|maven|
|pseudomap|1.0.2|间接依赖|npm|
|object.pick|1.3.0|间接依赖|npm|
|livereload-js|2.2.2|间接依赖|npm|
|escape-html|1.0.3|间接依赖|npm|
|Microsoft.AspNet.WebApi.Core|5.2.4|间接依赖|nuget|
|isexe|2.0.0|间接依赖|npm|
|array-each|1.0.1|间接依赖|npm|
|indent-string|2.1.0|间接依赖|npm|
|scheduler|0.20.1|间接依赖|npm|
|colors|1.0.3|间接依赖|npm|
|Werkzeug|0.14.1|间接依赖|pip|
|lodash.assign|3.2.0|间接依赖|npm|
|extend-shallow|2.0.1|间接依赖|npm|
|bl|1.0.3|直接依赖|npm|
|registry-auth-token|3.3.1|间接依赖|npm|
|async-each|1.0.1|间接依赖|npm|
|commander|2.5.1|间接依赖|npm|
|registry-auth-token|3.4.0|间接依赖|npm|
|isarray|0.0.1|间接依赖|npm|
|nodeunit|0.9.5|间接依赖|npm|
|lru-cache|2.7.3|间接依赖|npm|
|update-notifier|2.5.0|间接依赖|npm|
|is-npm|1.0.0|间接依赖|npm|
|buffer-shims|1.0.0|直接依赖|npm|
|to-iso-string|0.0.2|间接依赖|npm|
|homedir-polyfill|1.0.3|间接依赖|npm|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|velocity:velocity|1.4|间接依赖|maven|
|sorted-object|2.0.1|间接依赖|npm|
|json-schema|0.2.3|间接依赖|npm|
|bindings|1.5.0|间接依赖|npm|
|define-property|2.0.2|间接依赖|npm|
|commons-beanutils:commons-beanutils|1.9.4|直接依赖|maven|
|define-property|1.0.0|间接依赖|npm|
|lodash.defaults|3.1.2|间接依赖|npm|
|node-uuid|1.4.8|间接依赖|npm|
|global-dirs|0.1.1|间接依赖|npm|
|org.sonatype.sisu:sisu-guice|2.1.7|间接依赖|maven|
|lockfile|1.0.4|间接依赖|npm|
|com.moandjiezana.toml:toml4j|0.7.2|直接依赖|maven|
|make-dir|1.1.0|间接依赖|npm|
|websocket-extensions|0.1.3|间接依赖|npm|
|bluebird|3.7.2|间接依赖|npm|
|timespan|2.3.0|间接依赖|npm|
|debuglog|1.0.1|间接依赖|npm|
|org.checkerframework:checker-qual|3.33.0|间接依赖|maven|
|realize-package-specifier|3.0.3|间接依赖|npm|
|xtend|4.0.1|间接依赖|npm|
|lodash.restparam|3.6.1|间接依赖|npm|
|xtend|4.0.2|间接依赖|npm|
|sshpk|1.16.1|间接依赖|npm|
|org.apache.avro:avro|1.5.0|直接依赖|maven|
|coffee-script-source|1.10.0|间接依赖|bundler|
|platform|1.3.1|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|minimatch|0.3.0|间接依赖|npm|
|convert-source-map|1.7.0|间接依赖|npm|
|resumer|0.0.0|间接依赖|npm|
|is-number|2.1.0|间接依赖|npm|
|forever-monitor|1.7.2|间接依赖|npm|
|deep-equal|0.2.2|间接依赖|npm|
|retire|1.1.6|间接依赖|npm|
|caller|0.0.1|间接依赖|npm|
|find-cache-dir|0.1.1|间接依赖|npm|
|forwarded|0.1.2|间接依赖|npm|
|string-width|1.0.2|间接依赖|npm|
|grunt-legacy-log|3.0.0|间接依赖|npm|
|path-is-inside|1.0.2|间接依赖|npm|
|methods|1.1.2|间接依赖|npm|
|caseless|0.11.0|间接依赖|npm|
|ms|0.7.1|间接依赖|npm|
|verror|1.10.0|间接依赖|npm|
|sax|0.6.1|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|json|1.8.3|间接依赖|bundler|
|abbrev|1.1.1|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|utils-merge|1.0.0|间接依赖|npm|
|spyne|2.12.14|间接依赖|pip|
|rack-cache|1.5.1|间接依赖|bundler|
|boxen|1.2.2|间接依赖|npm|
|is-finite|1.0.2|间接依赖|npm|
|http-errors|1.7.3|间接依赖|npm|
|railties||间接依赖|bundler|
|nopt|1.0.10|间接依赖|npm|
|init-package-json|1.9.6|间接依赖|npm|
|nanomatch|1.2.13|间接依赖|npm|
|ini|1.3.5|间接依赖|npm|
|write-file-atomic|2.3.0|间接依赖|npm|
|resolve-from|2.0.0|间接依赖|npm|
|glob|5.0.15|间接依赖|npm|
|osenv|0.1.5|间接依赖|npm|
|decamelize|1.2.0|间接依赖|npm|
|coveralls|2.13.3|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|default-require-extensions|1.0.0|间接依赖|npm|
|tough-cookie|2.3.3|间接依赖|npm|
|make-iterator|1.0.1|间接依赖|npm|
|com.h3xstream.retirejs:retirejs-core|3.0.4|直接依赖|maven|
|nan|2.13.2|间接依赖|npm|
|utils-merge|1.0.1|间接依赖|npm|
|readdirp|2.1.0|间接依赖|npm|
|swarmcache:swarmcache|1.0RC2|直接依赖|maven|
|csurf|1.9.0|直接依赖|npm|
|itsdangerous|0.24|间接依赖|pip|
|rc|1.2.2|间接依赖|npm|
|com.fasterxml.jackson.module:jackson-module-blackbird|2.15.2|直接依赖|maven|
|write-file-atomic|1.2.0|间接依赖|npm|
|github.com/go-gitea/gitea|v1.5.0|直接依赖|go|
|validate-npm-package-name|2.2.2|间接依赖|npm|
|npm-registry-client|7.2.1|间接依赖|npm|
|execjs|2.6.0|间接依赖|bundler|
|typedarray|0.0.6|间接依赖|npm|
|jgroups:jgroups-all|2.2.8|间接依赖|maven|
|string-template|0.2.1|间接依赖|npm|
|org.eclipse.jetty:jetty-jmx|7.6.0.RC4|直接依赖|maven|
|ncp|1.0.1|间接依赖|npm|
|asm:asm-util|1.3.4|间接依赖|maven|
|semver|5.7.1|间接依赖|npm|
|w3c_validators|1.2|间接依赖|bundler|
|org.codehaus.jackson:jackson-core-asl|1.7.3|间接依赖|maven|
|range-parser|1.2.0|间接依赖|npm|
|fined|1.2.0|间接依赖|npm|
|tape|2.3.3|间接依赖|npm|
|micromatch|3.1.10|间接依赖|npm|
|com.hankcs:aho-corasick-double-array-trie|1.2.3|直接依赖|maven|
|uglify-js|2.4.24|间接依赖|npm|
|request|2.88.2|间接依赖|npm|
|async|2.6.3|直接依赖|npm|
|end-of-stream|1.4.0|间接依赖|npm|
|org.codehaus.plexus:plexus-xml|4.0.2|直接依赖|maven|
|ms|2.0.0|间接依赖|npm|
|org.eclipse.jetty:jetty-http|7.6.0.RC4|直接依赖|maven|
|grunt-contrib-watch|1.1.0|直接依赖|npm|
|nconf|0.6.9|间接依赖|npm|
|org.springframework:spring-web|2.0.7|直接依赖|maven|
|signal-exit|3.0.3|间接依赖|npm|
|es-to-primitive|1.2.1|间接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|istanbul-lib-coverage|1.2.1|间接依赖|npm|
|tap|7.1.2|间接依赖|npm|
|hosted-git-info|2.1.5|间接依赖|npm|
|org.springframework:spring|2.0.8|直接依赖|maven|
|dateformat|3.0.3|间接依赖|npm|
|commons-cli:commons-cli|1.5.0|直接依赖|maven|
|ps-tree|0.0.3|间接依赖|npm|
|avalon-framework:avalon-framework|4.1.3|直接依赖|maven|
|Flask|0.10.1|间接依赖|pip|
|aws-sign2|0.7.0|间接依赖|npm|
|actionpack||间接依赖|bundler|
|express-session|1.15.6|直接依赖|npm|
|rimraf|3.0.2|间接依赖|npm|
|spawn-wrap|1.4.3|间接依赖|npm|
|wordwrap|0.0.2|间接依赖|npm|
|pify|2.3.0|间接依赖|npm|
|set-immediate-shim|1.0.1|间接依赖|npm|
|domelementtype|1.3.1|间接依赖|npm|
|uid-safe|2.1.5|间接依赖|npm|
|opener|1.5.2|间接依赖|npm|
|javax.transaction:jta|1.1|直接依赖|maven|
|log4j:log4j|1.2.16|直接依赖|maven|
|org.apache.velocity:velocity|1.5|直接依赖|maven|
|deep-extend|0.6.0|间接依赖|npm|
|widest-line|2.0.1|间接依赖|npm|
|commons-io:commons-io|2.13.0|直接依赖|maven|
|undefsafe|0.0.3|间接依赖|npm|
|jshint|2.9.7|间接依赖|npm|
|proxool:proxool|0.8.3|直接依赖|maven|
|commons-validator:commons-validator|1.3.1|间接依赖|maven|
|undefsafe|2.0.3|间接依赖|npm|
|javax.servlet:servlet-api|2.5|直接依赖|maven|
|dom-serializer|0.1.0|间接依赖|npm|
|lxml|4.2.1|间接依赖|pip|
|global-prefix|1.0.2|间接依赖|npm|
|oro:oro|2.0.8|间接依赖|maven|
|imurmurhash|0.1.4|间接依赖|npm|
|cookie|0.3.1|间接依赖|npm|
|os-tmpdir|1.0.2|间接依赖|npm|
|shebang-regex|1.0.0|间接依赖|npm|
|delayed-stream|1.0.0|间接依赖|npm|
|com.thoughtworks.paranamer:paranamer|2.3|间接依赖|maven|
|number-is-nan|1.0.1|间接依赖|npm|
|oauth-sign|0.8.2|间接依赖|npm|
|forever-monitor|1.7.1|间接依赖|npm|
|abbrev|1.0.9|间接依赖|npm|
|pumpify|1.5.1|间接依赖|npm|
|etag|1.8.1|间接依赖|npm|
|encodeurl|1.0.1|间接依赖|npm|
|randomatic|1.1.7|间接依赖|npm|
|camelize|1.0.0|间接依赖|npm|
|/usr/lib/libSystem.B.dylib||间接依赖||
|lighter-config|1.1.0|间接依赖|npm|
|is-glob|3.1.0|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|esprima|2.7.3|间接依赖|npm|
|colors|0.6.2|间接依赖|npm|
|ansi-styles|4.3.0|间接依赖|npm|
|com.vaadin.external.google:android-json|0.0.20131108.vaadin1|间接依赖|maven|
|director|1.2.7|间接依赖|npm|
|opensymphony:oscache|2.1|直接依赖|maven|
|caching-transform|1.0.1|间接依赖|npm|
|utile|0.2.1|间接依赖|npm|
|lighter-run|1.2.1|直接依赖|npm|
|http-parser-js|0.4.9|间接依赖|npm|
|es-get-iterator|1.1.1|间接依赖|npm|
|rimraf|2.5.4|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|snapdragon-util|3.0.1|间接依赖|npm|
|org.apache.commons:commons-compress|1.23.0|直接依赖|maven|
|tsscmp|1.0.6|间接依赖|npm|
|should-format|0.3.2|间接依赖|npm|
|org.hibernate.javax.persistence:hibernate-jpa-2.0-api|1.0.1.Final|直接依赖|maven|
|resolve|1.19.0|间接依赖|npm|
|lodash._basecopy|3.0.1|间接依赖|npm|
|punycode|1.4.1|间接依赖|npm|
|redent|1.0.0|间接依赖|npm|
|shebang-command|1.2.0|直接依赖|npm|
|com.fasterxml.jackson.module:jackson-module-afterburner|2.15.2|直接依赖|maven|
|org.codehaus.plexus:plexus-utils|4.0.0|直接依赖|maven|
|asm:asm-tree|3.0|间接依赖|maven|
|jsonpointer|4.1.0|间接依赖|npm|
|org.hibernate:hibernate-testing|3.6.6.Final|直接依赖|maven|
|configstore|3.1.5|间接依赖|npm|
|ecc-jsbn|0.1.1|间接依赖|npm|
|commons-beanutils:commons-beanutils|1.8.3|直接依赖|maven|
|rimraf|2.7.1|间接依赖|npm|
|click|6.7|间接依赖|pip|
|ch.qos.logback:logback-classic|1.2.11|直接依赖|maven|
|com.yammer.metrics:metrics-servlet|2.0.0-RC0|直接依赖|maven|
|commons-lang:commons-lang|2.1|间接依赖|maven|
|lru-cache|4.1.1|间接依赖|npm|
|readable-stream|2.1.5|间接依赖|npm|
|ansi-align|2.0.0|间接依赖|npm|
|nodemon|1.19.4|间接依赖|npm|
|normalize-package-data|2.3.8|间接依赖|npm|
|array-unique|0.2.1|间接依赖|npm|
|lodash|4.17.20|间接依赖|npm|
|isexe|1.1.2|间接依赖|npm|
|widest-line|1.0.0|间接依赖|npm|
|ms|2.1.1|间接依赖|npm|
|org.slf4j:slf4j-api|1.6.1|直接依赖|maven|
|logkit:logkit|1.0.1|直接依赖|maven|
|micromatch|2.3.11|间接依赖|npm|
|hide-powered-by|1.0.0|间接依赖|npm|
|com.esotericsoftware:minlog|1.3.1|间接依赖|maven|
|hoek|0.9.1|间接依赖|npm|
|is-negative-zero|2.0.1|间接依赖|npm|
|npm-package-arg|4.2.1|间接依赖|npm|
|com.fasterxml.jackson.core:jackson-annotations|2.15.2|间接依赖|maven|
|type-is|1.6.18|间接依赖|npm|
|activesupport||间接依赖|bundler|
|minimist|0.0.10|间接依赖|npm|
|raw-body|1.1.7|间接依赖|npm|
|express|4.16.2|直接依赖|npm|
|parse-filepath|1.0.2|间接依赖|npm|
|grunt-npm-install|0.3.1|直接依赖|npm|
|shush|1.0.0|间接依赖|npm|
|org.yaml:snakeyaml|1.9|直接依赖|maven|
|gaze|1.1.2|间接依赖|npm|
|is-property|1.0.2|间接依赖|npm|
|stack-trace|0.0.10|间接依赖|npm|
|is-descriptor|1.0.2|间接依赖|npm|
|org.apache.maven.shared:maven-common-artifact-filters|3.1.0|间接依赖|maven|
|grunt-mocha-test|0.12.7|直接依赖|npm|
|read-package-json|2.0.12|间接依赖|npm|
|repeating|2.0.1|间接依赖|npm|
|should-type|0.2.0|间接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|global-modules|1.0.0|间接依赖|npm|
|turbolinks|2.5.3|间接依赖|bundler|
|code-point-at|1.1.0|直接依赖|npm|
|org.apache.commons:commons-dbcp2|2.9.0|直接依赖|maven|
|normalize-package-data|2.5.0|间接依赖|npm|
|minimatch|3.0.4|间接依赖|npm|
|lodash|4.17.4|间接依赖|npm|
|touch|3.1.0|间接依赖|npm|
|sdoc|0.4.1|间接依赖|bundler|
|net.sf.ehcache:ehcache-core|2.4.3|直接依赖|maven|
|FBSDKCoreKit|4.33.0|间接依赖|cocoapods|
|builtins|0.0.7|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|org.apache.maven:maven-xml-impl|4.0.0-alpha-7|间接依赖|maven|
|tsscmp|1.0.5|间接依赖|npm|
|argparse|1.0.10|间接依赖|npm|
|on-headers|1.0.2|间接依赖|npm|
|sntp|1.0.9|间接依赖|npm|
|destroy|1.0.4|间接依赖|npm|
|semver|7.3.4|间接依赖|npm|
|fs-write-stream-atomic|1.0.10|间接依赖|npm|
|is-glob|2.0.1|间接依赖|npm|
|defined|0.0.0|间接依赖|npm|
|is-finite|1.1.0|间接依赖|npm|
|qs|6.5.2|间接依赖|npm|
|websocket-driver|0.7.0|间接依赖|npm|
|rack|1.5.2|间接依赖|bundler|
|balanced-match|1.0.0|间接依赖|npm|
|read|1.0.7|间接依赖|npm|
|mkdirp|1.0.4|间接依赖|npm|
|path-array|1.0.1|间接依赖|npm|
|grunt-retire|0.3.12|直接依赖|npm|
|normalize-git-url|3.0.2|间接依赖|npm|
|grunt-concurrent|2.3.1|直接依赖|npm|
|generate-function|2.3.1|间接依赖|npm|
|dashify|0.2.2|间接依赖|npm|
|javax.inject:javax.inject|1|间接依赖|maven|
|jsprim|1.4.1|间接依赖|npm|
|iconv-lite|0.4.24|间接依赖|npm|
|forever|0.15.3|直接依赖|npm|
|supports-color|7.2.0|间接依赖|npm|
|mime-db|1.45.0|间接依赖|npm|
|string.prototype.trimstart|1.0.3|间接依赖|npm|
|rdoc|4.2.1|间接依赖|bundler|
|options|0.0.6|间接依赖|npm|
|commander|2.3.0|间接依赖|npm|
|validate-npm-package-license|3.0.4|间接依赖|npm|
|v8flags|3.1.3|间接依赖|npm|
|config-chain|1.1.12|间接依赖|npm|
|utile|0.3.0|间接依赖|npm|
|grunt-contrib-nodeunit|1.0.0|间接依赖|npm|
|npm|3.10.10|间接依赖|npm|
|mscoree.dll||间接依赖||
|glob|3.2.11|间接依赖|npm|
|joda-time:joda-time|1.6|直接依赖|maven|
|yargs|3.5.4|间接依赖|npm|
|winston|0.8.0|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|har-validator|5.1.5|间接依赖|npm|
|source-map|0.5.7|间接依赖|npm|
|jquery-rails|3.1.4|间接依赖|bundler|
|bcrypt-nodejs|0.0.3|直接依赖|npm|
|com.google.guava:guava|32.1.2-jre|直接依赖|maven|
|remove-trailing-separator|1.1.0|间接依赖|npm|
|builtin-modules|1.1.1|间接依赖|npm|
|snapdragon|0.8.2|间接依赖|npm|
|tar|2.2.2|间接依赖|npm|
|qs|0.6.6|间接依赖|npm|
|org.apache.ant:ant|1.10.14|直接依赖|maven|
|prettyjson|1.2.1|间接依赖|npm|
|strip-json-comments|2.0.1|间接依赖|npm|
|commons-beanutils:commons-beanutils|1.7.0|间接依赖|maven|
|safe-buffer|5.2.1|间接依赖|npm|
|buffer-from|1.1.1|间接依赖|npm|
|continuable-cache|0.3.1|间接依赖|npm|
|string_decoder|0.10.31|间接依赖|npm|
|cglib:cglib|2.2|直接依赖|maven|
|isarray|1.0.0|间接依赖|npm|
|depd|2.0.0|间接依赖|npm|
|csrf|3.1.0|间接依赖|npm|
|graceful-fs|4.1.11|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|org.apache.lucene:lucene-queries|8.11.2|间接依赖|maven|
|deep-equal|1.0.1|间接依赖|npm|
|rack|1.5.5|间接依赖|bundler|
|cglib:cglib|2.1|直接依赖|maven|
|yallist|4.0.0|间接依赖|npm|
|async-each|1.0.3|间接依赖|npm|
|which|1.2.14|间接依赖|npm|
|org.apache.lucene:lucene-sandbox|8.11.2|间接依赖|maven|
|bson|1.0.9|间接依赖|npm|
|which|1.3.1|间接依赖|npm|
|prompt|0.2.14|间接依赖|npm|
|deep-extend|0.4.2|间接依赖|npm|
|fake_submodule|file:fake_submodule|直接依赖|npm|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.15.2|直接依赖|maven|
|promzard|0.3.0|间接依赖|npm|
|org.apache.lucene:lucene-core|8.11.2|直接依赖|maven|
|mime|1.2.11|间接依赖|npm|
|org.apache.maven.shared:maven-artifact-transfer|0.13.1|直接依赖|maven|
|sprintf-js|1.1.2|间接依赖|npm|
|org.springframework:spring-aop|2.0.7|直接依赖|maven|
|ipaddr.js|1.5.2|间接依赖|npm|
|cmd-shim|2.0.2|间接依赖|npm|
|read-pkg|1.1.0|间接依赖|npm|
|delegates|1.0.0|间接依赖|npm|
|split-string|3.1.0|间接依赖|npm|
|mail|2.6.3|间接依赖|bundler|
|com.sun.jersey:jersey-core|1.11|直接依赖|maven|
|log4j:log4j|1.2.9|间接依赖|maven|
|six|1.11.0|间接依赖|pip|
|dns-sync|0.1.3|直接依赖|npm|
|gauge|2.6.0|间接依赖|npm|
|mime-types|2.1.28|间接依赖|npm|
|javax.xml.bind:jaxb-api|2.3.1|间接依赖|maven|
|object-assign|4.1.1|间接依赖|npm|
|istanbul-lib-hook|1.2.2|间接依赖|npm|
|nocache|1.0.1|间接依赖|npm|
|upath|1.2.0|间接依赖|npm|
|httplib2|0.11.3|间接依赖|pip|
|raw-body|2.3.2|间接依赖|npm|
|FBSDKLoginKit|4.33.0|间接依赖|cocoapods|
|underscore.string|3.3.5|间接依赖|npm|
|helmet-csp|1.2.2|间接依赖|npm|
|randomatic|3.1.1|间接依赖|npm|
|lodash.without|4.4.0|间接依赖|npm|
|commons-fileupload:commons-fileupload|1.2.1|直接依赖|maven|
|grunt-cli|1.3.2|直接依赖|npm|
|deep-equal|2.0.5|间接依赖|npm|
|ansi-styles|2.2.1|间接依赖|npm|
|spdx-expression-parse|3.0.1|间接依赖|npm|
|pkginfo|0.4.1|间接依赖|npm|
|console-control-strings|1.1.0|间接依赖|npm|
|org.eclipse.packager:packager-rpm|0.19.0|直接依赖|maven|
|braces|2.3.2|间接依赖|npm|
|expand-brackets|0.1.5|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|fsevents|1.1.3|间接依赖|npm|
|fstream-npm|1.2.1|间接依赖|npm|
|debug|3.2.7|间接依赖|npm|
|org.eclipse.jetty:jetty-io|7.6.0.RC4|直接依赖|maven|
|async|0.9.2|间接依赖|npm|
|connect|3.4.1|间接依赖|npm|
|rimraf|2.6.2|间接依赖|npm|
|is-boolean-object|1.1.0|间接依赖|npm|
|is-bigint|1.0.1|间接依赖|npm|
|org.slf4j:slf4j-log4j12|1.6.4|直接依赖|maven|
|amdefine|1.0.1|间接依赖|npm|
|depd|1.1.1|间接依赖|npm|
|glob-parent|2.0.0|间接依赖|npm|
|which-boxed-primitive|1.0.2|间接依赖|npm|
|object.assign|4.1.2|间接依赖|npm|
|graceful-fs|4.1.15|间接依赖|npm|
|csurf|1.11.0|直接依赖|npm|
|com.github.spotbugs:spotbugs-annotations|4.7.3|直接依赖|maven|
|toidentifier|1.0.0|间接依赖|npm|
|glob-parent|3.1.0|间接依赖|npm|
|minimist|1.2.5|间接依赖|npm|
|tough-cookie|2.5.0|间接依赖|npm|
|certifi|2018.4.16|间接依赖|pip|
|available-typed-arrays|1.0.2|间接依赖|npm|
|readable-stream|2.3.3|间接依赖|npm|
|ansistyles|0.1.3|间接依赖|npm|
|events-to-array|1.1.2|间接依赖|npm|
|ini|1.3.8|间接依赖|npm|
|color-support|1.1.3|间接依赖|npm|
|builtins|1.0.3|间接依赖|npm|
|pump|1.0.3|间接依赖|npm|
|qs|6.7.0|间接依赖|npm|
|org.bouncycastle:bcpg-jdk18on|1.71|间接依赖|maven|
|os-homedir|1.0.2|间接依赖|npm|
|com.google.code.findbugs:jsr305|1.3.9|直接依赖|maven|
|idna|2.7|间接依赖|pip|
|qs|6.2.3|间接依赖|npm|
|c3p0:c3p0|0.9.1|直接依赖|maven|
|uuid|3.1.0|间接依赖|npm|
|hosted-git-info|2.8.8|间接依赖|npm|
|mime-types|2.1.17|间接依赖|npm|
|statuses|1.4.0|间接依赖|npm|
|console-browserify|1.1.0|间接依赖|npm|
|detect-file|1.0.0|间接依赖|npm|
|assert-plus|1.0.0|间接依赖|npm|
|cross-spawn|4.0.2|间接依赖|npm|
|org.apache.ant:ant|1.7.0|间接依赖|maven|
|tmatch|2.0.1|间接依赖|npm|
|rndm|1.2.0|间接依赖|npm|
|safe-regex|1.1.0|间接依赖|npm|
|grunt-env|1.0.1|直接依赖|npm|
|strip-json-comments|1.0.4|间接依赖|npm|
|cli-boxes|1.0.0|间接依赖|npm|
|preserve|0.2.0|间接依赖|npm|
|org.apache.maven.doxia:doxia-logging-api|1.11.1|间接依赖|maven|
|read-cmd-shim|1.0.5|间接依赖|npm|
|bytes|3.1.0|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|tiny-lr|0.2.1|间接依赖|npm|
|extglob|0.3.2|间接依赖|npm|
|stream-shift|1.0.1|间接依赖|npm|
|content-disposition|0.5.2|间接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|interpret|1.1.0|间接依赖|npm|
|date-now|0.1.4|间接依赖|npm|
|error|7.2.1|间接依赖|npm|
|nodemon|1.12.1|间接依赖|npm|
|dom-serializer|0.2.2|间接依赖|npm|
|ee-first|1.1.1|间接依赖|npm|
|dont-sniff-mimetype|1.0.0|间接依赖|npm|
|is-path-inside|1.0.1|间接依赖|npm|
|path-to-regexp|0.1.7|间接依赖|npm|
|mustache|0.99.8|间接依赖|bundler|
|org.jboss.javaee:jboss-transaction-api|1.0.1.GA|间接依赖|maven|
|clean-yaml-object|0.1.0|间接依赖|npm|
|array-flatten|1.1.1|间接依赖|npm|
|punycode|2.1.1|间接依赖|npm|
|wordwrap|0.0.3|间接依赖|npm|
|isobject|2.1.0|间接依赖|npm|
|json-parse-even-better-errors|2.3.1|间接依赖|npm|
|pkg-up|1.0.0|间接依赖|npm|
|commander|2.12.1|间接依赖|npm|
|uuid|3.4.0|间接依赖|npm|
|config-chain|1.1.11|间接依赖|npm|
|has-unicode|2.0.1|间接依赖|npm|
|repeat-string|1.6.1|间接依赖|npm|
|org.sonatype.goodies:package-url-java|1.1.1|间接依赖|maven|
|Newtonsoft.Json|10.0.3|间接依赖|nuget|
|slash|1.0.0|间接依赖|npm|
|for-in|1.0.2|间接依赖|npm|
|asn1|0.2.3|间接依赖|npm|
|org.apache.velocity:velocity-tools|1.3|直接依赖|maven|
|math-random|1.0.4|间接依赖|npm|
|fill-range|2.2.3|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|dot-prop|4.2.0|间接依赖|npm|
|selenium-webdriver|2.53.3|直接依赖|npm|
|serve-static|1.13.1|间接依赖|npm|
|is-binary-path|1.0.1|间接依赖|npm|
|setprototypeof|1.1.1|间接依赖|npm|
|signal-exit|3.0.2|间接依赖|npm|
|sprockets|3.0.3|间接依赖|bundler|
|slide|1.1.6|间接依赖|npm|
|x-xss-protection|1.0.0|间接依赖|npm|
|js-yaml|3.6.1|间接依赖|npm|
|object-is|1.1.4|间接依赖|npm|
|crc|3.4.4|间接依赖|npm|
|parseurl|1.3.2|间接依赖|npm|
|extsprintf|1.3.0|间接依赖|npm|
|fstream-ignore|1.0.5|间接依赖|npm|
|dezalgo|1.0.3|间接依赖|npm|
|org.jboss.netty:netty|3.2.4.Final|直接依赖|maven|
|uglify-to-browserify|1.0.2|间接依赖|npm|
|bytes|1.0.0|间接依赖|npm|
|org.apache.velocity:velocity-engine-core|2.3|直接依赖|maven|
|ncp|0.4.2|间接依赖|npm|
|org.yaml:snakeyaml|2.0|间接依赖|maven|
|extsprintf|1.4.0|间接依赖|npm|
|term-size|1.2.0|间接依赖|npm|
|org.springframework:spring-beans|3.0.0.RELEASE|直接依赖|maven|
|read-pkg-up|1.0.1|间接依赖|npm|
|org.apache.commons:commons-collections4|4.4|直接依赖|maven|
|range-parser|1.2.1|间接依赖|npm|
|object.map|1.0.1|间接依赖|npm|
|stream-shift|1.0.0|间接依赖|npm|
|ipaddr.js|1.9.1|间接依赖|npm|
|nssocket|0.5.3|间接依赖|npm|
|org.apache.struts:struts-annotations|1.0.3|直接依赖|maven|
|async|1.5.2|间接依赖|npm|
|bluebird|3.5.1|间接依赖|npm|
|depd|1.1.0|间接依赖|npm|
|mime|1.4.1|间接依赖|npm|
|xdg-basedir|3.0.0|间接依赖|npm|
|path-dirname|1.0.2|间接依赖|npm|
|getobject|0.1.0|间接依赖|npm|
|org.mortbay.jetty:jetty|6.1.26|直接依赖|maven|
|through2|2.0.5|间接依赖|npm|
|js-yaml|3.5.5|间接依赖|npm|
|bcrypt-pbkdf|1.0.2|间接依赖|npm|
|walkdir|0.0.7|间接依赖|npm|
|org.eclipse.jetty:jetty-server|7.6.0.RC4|直接依赖|maven|
|path-root|0.1.1|间接依赖|npm|
|asm:asm|1.5.3|间接依赖|maven|
|tough-cookie|2.3.4|间接依赖|npm|
|ienoopen|1.0.0|间接依赖|npm|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|has-symbols|1.0.1|间接依赖|npm|
|should-equal|0.8.0|间接依赖|npm|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|define-property|0.2.5|间接依赖|npm|
|fragment-cache|0.2.1|间接依赖|npm|
|hoek|2.16.3|间接依赖|npm|
|foreach|2.0.5|间接依赖|npm|
|Microsoft.Owin|3.1.0|间接依赖|nuget|
|org.mortbay.jetty:servlet-api|2.5-20081211|间接依赖|maven|
|grunt-jsbeautifier|0.2.13|直接依赖|npm|
|form-data|2.3.3|间接依赖|npm|
|load-json-file|1.1.0|间接依赖|npm|
|array-index|1.0.0|间接依赖|npm|
|domhandler|2.3.0|间接依赖|npm|
|string.prototype.trimend|1.0.3|间接依赖|npm|
|jsonify|0.0.0|间接依赖|npm|
|snapdragon-node|2.1.1|间接依赖|npm|
|com.opensymphony:xwork|2.1.1|直接依赖|maven|
|editorconfig|0.13.3|间接依赖|npm|
|has-ansi|2.0.0|间接依赖|npm|
|mkdirp|0.3.0|间接依赖|npm|
|mongodb-core|2.1.17|间接依赖|npm|
|form-data|2.1.4|间接依赖|npm|
|isstream|0.1.2|间接依赖|npm|
|on-headers|1.0.1|间接依赖|npm|
|findup-sync|2.0.0|间接依赖|npm|
|PyYAML|3.12|间接依赖|pip|
|boxen|1.3.0|间接依赖|npm|
|is-number-object|1.0.4|间接依赖|npm|
|ansi-regex|2.1.1|间接依赖|npm|
|optimist|0.6.1|间接依赖|npm|
|commons-digester:commons-digester|1.8|直接依赖|maven|
|object-assign|3.0.0|间接依赖|npm|
|org.sonatype.plexus:plexus-cipher|1.4|间接依赖|maven|
|is-string|1.0.5|间接依赖|npm|
|debug|2.2.0|间接依赖|npm|
|assert-plus|0.1.5|间接依赖|npm|
|nan|2.8.0|间接依赖|npm|
|rc|1.2.8|间接依赖|npm|
|adm-zip|0.4.4|间接依赖|npm|
|marked|0.3.5|直接依赖|npm|
|tough-cookie|2.2.2|间接依赖|npm|
|use|3.1.1|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|grunt-legacy-util|1.0.0|间接依赖|npm|
|is-path-inside|1.0.0|间接依赖|npm|
|org.springframework:spring-core|2.0.7|直接依赖|maven|
|is-weakset|2.0.1|间接依赖|npm|
|referrer-policy|1.0.0|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|is-core-module|2.2.0|间接依赖|npm|
|Bolts/Tasks|1.9.0|间接依赖|cocoapods|
|is-installed-globally|0.1.0|间接依赖|npm|
|request|2.36.0|间接依赖|npm|
|lodash._root|3.0.1|间接依赖|npm|
|latest-version|3.1.0|间接依赖|npm|
|got|6.7.1|间接依赖|npm|
|map-cache|0.2.2|间接依赖|npm|
|strip-json-comments|0.1.3|间接依赖|npm|
|org.slf4j:jcl-over-slf4j|1.7.28|间接依赖|maven|
|proxy-addr|2.0.2|间接依赖|npm|
|livereload-js|2.4.0|间接依赖|npm|
|parse-passwd|1.0.0|间接依赖|npm|
|antlr:antlr|2.7.6|直接依赖|maven|
|org.apache.maven.shared:maven-dependency-tree|3.2.1|直接依赖|maven|
|yargs-parser|2.4.1|间接依赖|npm|
|request|2.67.0|间接依赖|npm|
|grunt-contrib-jshint|1.1.0|间接依赖|npm|
|path-root-regex|0.1.2|间接依赖|npm|
|is-weakmap|2.0.1|间接依赖|npm|
|caseless|0.12.0|间接依赖|npm|
|nopt|4.0.3|间接依赖|npm|
|os-homedir|1.0.1|间接依赖|npm|
|set-blocking|2.0.0|间接依赖|npm|
|array-find-index|1.0.2|间接依赖|npm|
|proto-list|1.2.4|间接依赖|npm|
|kind-of|3.2.2|间接依赖|npm|
|pify|3.0.0|间接依赖|npm|
|org.eclipse.jetty:jetty-servlet|7.6.0.RC4|直接依赖|maven|
|safe-buffer|5.1.1|间接依赖|npm|
|javassist:javassist|3.12.0.GA|直接依赖|maven|
|is-plain-object|2.0.4|间接依赖|npm|
|tiny-lr|1.1.1|间接依赖|npm|
|is-buffer|1.1.6|间接依赖|npm|
|pymongo|3.6.1|间接依赖|pip|
|isarray|2.0.5|间接依赖|npm|
|send|0.17.1|间接依赖|npm|
|get-stdin|4.0.1|间接依赖|npm|
|npmlog|3.1.2|直接依赖|npm|
|js-beautify|1.13.0|间接依赖|npm|
|minimist|1.2.0|间接依赖|npm|
|readdirp|2.2.1|间接依赖|npm|
|oauth-sign|0.9.0|间接依赖|npm|
|cryptiles|2.0.5|间接依赖|npm|
|uglify-js|3.12.4|直接依赖|npm|
|object.omit|2.0.1|间接依赖|npm|
|rack-protection|1.5.2|间接依赖|bundler|
|coffee-rails|4.0.1|间接依赖|bundler|
|lodash.reduce|4.5.0|间接依赖|npm|
|grunt-env|0.4.4|直接依赖|npm|
|org.glassfish:javax.json|1.1.4|直接依赖|maven|
|commons-cli:commons-cli|1.2|直接依赖|maven|
|uid-number|0.0.6|间接依赖|npm|
|mocha|2.5.3|直接依赖|npm|
|Bolts|1.9.0|间接依赖|cocoapods|
|org.apache.ant:ant-launcher|1.7.0|间接依赖|maven|
|minimist|0.0.8|间接依赖|npm|
|readdir-scoped-modules|1.1.0|间接依赖|npm|
|spdx-license-ids|1.2.2|间接依赖|npm|
|event-stream|0.5.3|间接依赖|npm|
|pinkie|2.0.4|间接依赖|npm|
|ecc-jsbn|0.1.2|间接依赖|npm|
|org.slf4j:slf4j-api|1.5.8|直接依赖|maven|
|cycle|1.0.3|间接依赖|npm|
|cli|1.0.1|间接依赖|npm|
|org.hibernate:jtidy|r8-20060801|间接依赖|maven|
|duplexer|0.1.1|间接依赖|npm|
|regexp.prototype.flags|1.3.0|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|content-disposition|0.5.3|间接依赖|npm|
|chalk|4.1.0|间接依赖|npm|
|make-dir|1.3.0|间接依赖|npm|
|tzinfo|1.2.2|间接依赖|bundler|
|eggtest||间接依赖|pip|
|kindlerb|0.1.1|间接依赖|bundler|
|aproba|1.0.4|间接依赖|npm|
|com.fasterxml.jackson.core:jackson-databind|2.15.2|直接依赖|maven|
|duplexify|3.7.1|间接依赖|npm|
|encodeurl|1.0.2|间接依赖|npm|
|eventemitter2|0.4.14|间接依赖|npm|
|accepts|1.3.4|间接依赖|npm|
|http-signature|0.10.1|直接依赖|npm|
|is-my-ip-valid|1.0.0|间接依赖|npm|
|universalify|0.1.2|间接依赖|npm|
|mini_portile2|2.0.0|间接依赖|bundler|
|md5-hex|1.3.0|间接依赖|npm|
|parseurl|1.3.3|间接依赖|npm|
|source-map-resolve|0.5.3|间接依赖|npm|
|is-glob|4.0.1|间接依赖|npm|
|inherits|2.0.3|间接依赖|npm|
|read-package-json|2.0.13|间接依赖|npm|
|grunt-known-options|1.1.0|间接依赖|npm|
|mongodb|2.2.36|直接依赖|npm|
|grunt-legacy-log-utils|1.0.0|间接依赖|npm|
|debug|2.6.9|间接依赖|npm|
|is-my-json-valid|2.16.1|间接依赖|npm|
|to-regex-range|2.1.1|间接依赖|npm|
|body|5.1.0|间接依赖|npm|
|form-data|2.0.0|间接依赖|npm|
|commons-logging:commons-logging|1.1.1|直接依赖|maven|
|through2|2.0.3|间接依赖|npm|
|org.beanshell:bsh|2.0b4|间接依赖|maven|
|serve-favicon|2.5.0|直接依赖|npm|
|org.owasp:dependency-check-utils|8.4.1-SNAPSHOT|直接依赖|maven|
|define-properties|1.1.3|间接依赖|npm|
|hpkp|1.2.0|间接依赖|npm|
|joda-time:joda-time|2.10.4|间接依赖|maven|
|loose-envify|1.4.0|间接依赖|npm|
|nokogiri|1.6.7.2|间接依赖|bundler|
|block-stream|0.0.9|间接依赖|npm|
|flagged-respawn|1.0.1|间接依赖|npm|
|is-callable|1.2.2|间接依赖|npm|
|aws-sign2|0.5.0|直接依赖|npm|
|serve-favicon|2.4.5|直接依赖|npm|
|ws|1.1.5|间接依赖|npm|
|read-installed|4.0.3|间接依赖|npm|
|growl|1.9.2|间接依赖|npm|
|which-collection|1.0.1|间接依赖|npm|
|bcrypt-pbkdf|1.0.1|间接依赖|npm|
|mkdirp|0.5.1|间接依赖|npm|
|argparse|1.0.9|间接依赖|npm|
|sha|2.0.1|间接依赖|npm|
|lodash._bindcallback|3.0.1|间接依赖|npm|
|vary|1.1.2|间接依赖|npm|
|unpipe|1.0.0|间接依赖|npm|
|resolve|1.1.7|间接依赖|npm|
|jshint|2.9.5|间接依赖|npm|
|broadway|0.3.6|间接依赖|npm|
|org.hibernate:hibernate-entitymanager|3.6.6.Final|直接依赖|maven|
|assert-plus|0.2.0|间接依赖|npm|
|lodash.uniq|4.5.0|间接依赖|npm|
|har-schema|2.0.0|间接依赖|npm|
|async|2.6.0|间接依赖|npm|
|com.sun.jersey:jersey-servlet|1.11|直接依赖|maven|
|semver-diff|2.1.0|间接依赖|npm|
|async|0.2.10|间接依赖|npm|
|cliff|0.1.9|间接依赖|npm|
|com.github.package-url:packageurl-java|1.4.1|直接依赖|maven|
|opener|1.4.3|间接依赖|npm|
|for-own|1.0.0|间接依赖|npm|
|supports-color|2.0.0|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|get-intrinsic|1.0.2|间接依赖|npm|
|javax.ws.rs:javax.ws.rs-api|2.0.1|间接依赖|maven|
|retry|0.10.1|间接依赖|npm|
|com.google.code.gson:gson|2.9.0|间接依赖|maven|
|commander|2.20.3|间接依赖|npm|
|yallist|2.1.2|间接依赖|npm|
|org.jetbrains:annotations|24.0.1|直接依赖|maven|
|import-lazy|2.1.0|间接依赖|npm|
|mute-stream|0.0.7|间接依赖|npm|
|websocket-driver|0.7.4|间接依赖|npm|
|update-notifier|2.3.0|间接依赖|npm|
|repeat-element|1.1.3|间接依赖|npm|
|org.codehaus.jackson:jackson-mapper-asl|1.7.3|间接依赖|maven|
|optimist|0.6.0|间接依赖|npm|
|tough-cookie|4.0.0|直接依赖|npm|
|com.h2database:h2|2.1.214|直接依赖|maven|
|faye-websocket|0.10.0|间接依赖|npm|
|lodash._baseuniq|4.6.0|间接依赖|npm|
|getpass|0.1.7|间接依赖|npm|
|xml2js|0.4.4|间接依赖|npm|
|fill-range|2.2.4|间接依赖|npm|
|asn1|0.2.4|间接依赖|npm|
|optimist|0.2.8|间接依赖|npm|
|readdir-scoped-modules|1.0.2|间接依赖|npm|
|commons-logging:commons-logging|1.1|间接依赖|maven|
|semver|5.3.0|间接依赖|npm|
|cookie-signature|1.0.6|间接依赖|npm|
|lru-cache|4.1.5|间接依赖|npm|
|binary-extensions|1.11.0|间接依赖|npm|
|which-typed-array|1.1.4|间接依赖|npm|
|org.apache.struts:struts2-core|2.1.2|直接依赖|maven|
|is-arguments|1.1.0|间接依赖|npm|
|write-file-atomic|2.4.3|间接依赖|npm|
|gaze|1.1.3|间接依赖|npm|
|bytes|3.0.0|间接依赖|npm|
|OCMock|3.4.1|间接依赖|cocoapods|
|helmet|2.3.0|直接依赖|npm|
|random-bytes|1.0.0|间接依赖|npm|
|is-windows|1.0.2|间接依赖|npm|
|istanbul-reports|1.5.1|间接依赖|npm|
|grunt-if|0.2.0|直接依赖|npm|
|tap-parser|2.2.3|间接依赖|npm|
|strip-ansi|3.0.1|间接依赖|npm|
|wcwidth|1.0.1|间接依赖|npm|
|forever-agent|0.6.1|间接依赖|npm|
|consolidate|0.14.5|直接依赖|npm|
|semver|5.4.1|间接依赖|npm|
|commons-validator:commons-validator|1.7|直接依赖|maven|
|regex-cache|0.4.4|间接依赖|npm|
|ctype|0.5.3|直接依赖|npm|
|type-is|1.6.15|间接依赖|npm|
|supports-color|1.2.0|间接依赖|npm|
|through|2.3.8|间接依赖|npm|
|extend|3.0.1|间接依赖|npm|
|istanbul-lib-instrument|1.10.2|间接依赖|npm|
|psl|1.8.0|间接依赖|npm|
|mocha|0.14.0|间接依赖|bundler|
|package-json|4.0.1|间接依赖|npm|
|camelcase|4.1.0|间接依赖|npm|
|npm-normalize-package-bin|1.0.1|间接依赖|npm|
|is-symbol|1.0.3|间接依赖|npm|
|js-beautify|1.7.4|间接依赖|npm|
|qs|6.5.1|间接依赖|npm|
|org.owasp:dependency-check-core|8.4.1-SNAPSHOT|直接依赖|maven|
|is-map|2.0.2|间接依赖|npm|
|to-regex|3.0.2|间接依赖|npm|
|path-type|1.1.0|间接依赖|npm|
|hsts|1.0.0|间接依赖|npm|
|com.fasterxml.jackson.core:jackson-core|2.15.2|间接依赖|maven|
|npm-install-checks|3.0.0|间接依赖|npm|
|assign-symbols|1.0.0|间接依赖|npm|
|editor|1.0.0|间接依赖|npm|
|duplexify|3.5.1|间接依赖|npm|
|require_optional|1.0.1|间接依赖|npm|
|expand-range|1.8.2|间接依赖|npm|
|on-finished|2.3.0|间接依赖|npm|
|npm-package-arg|5.1.2|间接依赖|npm|
|split|0.3.3|直接依赖|npm|
|sigmund|1.0.1|间接依赖|npm|
|util-extend|1.0.3|间接依赖|npm|
|depd|1.1.2|间接依赖|npm|
|react-dom|17.0.1|直接依赖|npm|
|org.eclipse.jetty:jetty-util|7.6.0.RC4|直接依赖|maven|
|should|8.4.0|直接依赖|npm|
|resolve-dir|1.0.1|间接依赖|npm|
|read-package-json|2.1.2|间接依赖|npm|
|org.apache.maven.shared:file-management|3.1.0|直接依赖|maven|
|has-color|0.1.7|间接依赖|npm|
|npm-user-validate|0.1.5|间接依赖|npm|
|fstream|1.0.12|间接依赖|npm|
|regex-not|1.0.2|间接依赖|npm|
|fresh|0.5.2|间接依赖|npm|
|jade|0.26.3|间接依赖|npm|
|expand-brackets|2.1.4|间接依赖|npm|
|generate-function|2.0.0|间接依赖|npm|
|dns-prefetch-control|0.1.0|间接依赖|npm|
|request|2.75.0|间接依赖|npm|
|combined-stream|0.0.7|间接依赖|npm|
|brace-expansion|1.1.8|间接依赖|npm|
|org.jsoup:jsoup|1.5.2|直接依赖|maven|
|deeper|2.1.0|间接依赖|npm|
|org.eclipse.jetty:jetty-continuation|7.6.0.RC4|直接依赖|maven|
|grunt-contrib-watch|1.0.0|直接依赖|npm|
|lodash._getnative|3.9.1|间接依赖|npm|
|camelcase|2.1.1|间接依赖|npm|
|defaults|1.0.3|间接依赖|npm|
|trim-newlines|1.0.0|间接依赖|npm|
|tap-mocha-reporter|2.0.1|间接依赖|npm|
|aws-sign2|0.6.0|间接依赖|npm|
|PySimpleSOAP|1.16.2|间接依赖|pip|
|unique-slug|2.0.0|直接依赖|npm|
|org.codehaus.jackson:jackson-mapper-asl|1.9.3|直接依赖|maven|
|raw-body|2.4.0|间接依赖|npm|
|dom4j:dom4j|1.6.1|直接依赖|maven|
|is-typed-array|1.1.4|间接依赖|npm|
|entities|1.0.0|间接依赖|npm|
|stack-utils|0.4.0|间接依赖|npm|
|com.yammer.metrics:metrics-jetty|2.0.0-RC0|直接依赖|maven|
|map-obj|1.0.1|间接依赖|npm|
|thread_safe|0.3.5|间接依赖|bundler|
|org.sonatype.ossindex:ossindex-service-api|1.8.2|间接依赖|maven|
|http-errors|1.7.2|间接依赖|npm|
|ignore-by-default|1.0.1|间接依赖|npm|
|execa|0.7.0|间接依赖|npm|
|string_decoder|1.1.1|间接依赖|npm|
|readable-stream|1.1.13|间接依赖|npm|
|text-table|0.2.0|间接依赖|npm|
|crypto-random-string|1.0.0|间接依赖|npm|
|freemarker:freemarker|2.3.8|间接依赖|maven|
|has-flag|2.0.0|直接依赖|npm|
|ch.qos.logback:logback-core|1.2.11|直接依赖|maven|
|uid-safe|2.1.4|间接依赖|npm|
|gauge|2.7.4|间接依赖|npm|
|archy|1.0.0|间接依赖|npm|
|sec-wall|1.2|间接依赖|pip|
|registry-url|3.1.0|间接依赖|npm|
|yargs|4.8.1|间接依赖|npm|
|anymatch|2.0.0|间接依赖|npm|
|lodash.clonedeep|4.5.0|间接依赖|npm|
|strip-ansi|4.0.0|间接依赖|npm|
|fs-vacuum|1.2.10|间接依赖|npm|
|aws4|1.11.0|间接依赖|npm|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|org.apache.lucene:lucene-queryparser|8.11.2|直接依赖|maven|
|pump|2.0.1|间接依赖|npm|
|qs|6.9.4|间接依赖|npm|
|velocity:velocity-dep|1.4|间接依赖|maven|
|ci-info|1.6.0|间接依赖|npm|
|underscore.string|3.2.3|间接依赖|npm|
|com.yammer.metrics:metrics-jersey|2.0.0-RC0|直接依赖|maven|
|csrf|3.0.6|间接依赖|npm|
|bl|1.1.2|间接依赖|npm|
|jgroups:jgroups|2.6.13.GA|间接依赖|maven|
|lru-cache|6.0.0|间接依赖|npm|
|finalhandler|1.1.0|间接依赖|npm|
|domutils|1.5.1|间接依赖|npm|
|Jinja2|2.10|间接依赖|pip|
|nopt|5.0.0|间接依赖|npm|
|Flask-Spyne|0.3.1|间接依赖|pip|
|exit|0.1.2|间接依赖|npm|
|string_decoder|1.0.3|间接依赖|npm|
|org.sonatype.sisu:sisu-inject-plexus|1.4.2|间接依赖|maven|
|is-number|3.0.0|间接依赖|npm|
|flatiron|0.4.3|间接依赖|npm|
|org.codehaus.jackson:jackson-core-asl|1.9.3|直接依赖|maven|
|http-parser-js|0.5.3|间接依赖|npm|
|arr-diff|2.0.0|间接依赖|npm|
|jsbn|0.1.1|间接依赖|npm|
|findup-sync|0.3.0|间接依赖|npm|
|org.springframework:spring-core|3.0.0.RELEASE|间接依赖|maven|
|commons-io:commons-io|1.3.2|直接依赖|maven|
|istanbul-lib-source-maps|1.2.6|间接依赖|npm|
|readable-stream|2.3.7|直接依赖|npm|
|globule|1.3.2|间接依赖|npm|
|spdx-correct|3.1.1|间接依赖|npm|
|repeat-element|1.1.2|间接依赖|npm|
|media-typer|0.3.0|间接依赖|npm|
|spdx-expression-parse|1.0.4|间接依赖|npm|
|pstree.remy|1.1.8|间接依赖|npm|
|cookie|0.4.0|间接依赖|npm|
|shelljs|0.5.3|间接依赖|npm|
|frameguard|2.0.0|间接依赖|npm|
|is-extendable|0.1.1|间接依赖|npm|
|hooker|0.2.3|间接依赖|npm|
|com.yammer.metrics:metrics-core|2.0.0-RC0|直接依赖|maven|
|com.google.guava:guava|11.0.1|直接依赖|maven|
|mkdirp|0.5.5|间接依赖|npm|
|esprima|4.0.1|间接依赖|npm|
|sslext:sslext|1.2-0|间接依赖|maven|
|anymatch|1.3.2|间接依赖|npm|
|glob|7.1.2|间接依赖|npm|
|normalize-path|2.1.1|间接依赖|npm|
|swig|1.4.2|直接依赖|npm|
|lcov-parse|0.0.10|间接依赖|npm|
|org.jboss.logging:jboss-logging-spi|2.0.5.GA|间接依赖|maven|
|org.jboss.cache:jbosscache-core|3.2.1.GA|直接依赖|maven|
|dashdash|1.14.1|间接依赖|npm|
|es-abstract|1.18.0-next.1|间接依赖|npm|
|is-fullwidth-code-point|2.0.0|间接依赖|npm|
|chownr|1.0.1|间接依赖|npm|
|is-relative|1.0.0|间接依赖|npm|
|combined-stream|1.0.8|间接依赖|npm|
|grunt|1.0.1|间接依赖|npm|
|shelljs|0.3.0|间接依赖|npm|
|mongodb-core|2.1.20|间接依赖|npm|
|revalidator|0.1.8|间接依赖|npm|
|nyc|7.1.0|间接依赖|npm|
|grunt-legacy-util|2.0.0|间接依赖|npm|
|expand-tilde|2.0.2|间接依赖|npm|
|currently-unhandled|0.4.1|间接依赖|npm|
|domelementtype|1.3.0|间接依赖|npm|
|is-fullwidth-code-point|1.0.0|间接依赖|npm|
|websocket-extensions|0.1.4|间接依赖|npm|
|are-we-there-yet|1.1.5|间接依赖|npm|
|com.google.errorprone:error_prone_annotations|2.18.0|间接依赖|maven|
|org.tukaani:xz|1.9|间接依赖|maven|
|merge-descriptors|1.0.1|间接依赖|npm|
|is-obj|1.0.1|间接依赖|npm|
|is-absolute|1.0.0|间接依赖|npm|
|stringstream|0.0.5|间接依赖|npm|
|net.sourceforge.cobertura:cobertura|1.9.4.1|直接依赖|maven|
|org.eclipse.jetty:jetty-security|7.6.0.RC4|直接依赖|maven|
|rack-test|0.6.3|间接依赖|bundler|
|concat-stream|1.6.2|间接依赖|npm|
|extglob|2.0.4|间接依赖|npm|
|is-builtin-module|1.0.0|间接依赖|npm|
|sntp|0.2.4|间接依赖|npm|
|org.apache.maven:maven-api-meta|4.0.0-alpha-7|间接依赖|maven|
|tunnel-agent|0.6.0|间接依赖|npm|
|grunt-cli|1.2.0|间接依赖|npm|
|org.springframework:spring-context|2.0.7|直接依赖|maven|
|generate-object-property|1.2.0|间接依赖|npm|
|camelcase-keys|2.1.0|间接依赖|npm|
|requests|2.19.1|间接依赖|pip|
|validate-npm-package-license|3.0.1|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|tweetnacl|0.14.5|间接依赖|npm|
|Autofac|4.6.2|间接依赖|nuget|
|org.apache.commons:commons-lang3|3.13.0|直接依赖|maven|
|javax.validation:validation-api|1.0.0.GA|直接依赖|maven|
|grunt-nodemon|0.4.2|直接依赖|npm|
|async|0.2.9|间接依赖|npm|
|finalhandler|1.1.2|间接依赖|npm|
|MarkupSafe|1.0|间接依赖|pip|
|sprintf-js|1.0.3|间接依赖|npm|
|parse-glob|3.0.4|间接依赖|npm|
|rechoir|0.6.2|间接依赖|npm|
|fsevents|1.2.8|间接依赖|npm|
|pkginfo|0.3.1|间接依赖|npm|
|array-slice|1.1.0|间接依赖|npm|
|tilt|1.4.1|间接依赖|bundler|
|arr-flatten|1.1.0|间接依赖|npm|
|configstore|3.1.1|间接依赖|npm|
|dont-sniff-mimetype|1.1.0|直接依赖|npm|
|commons-collections:commons-collections|3.1|直接依赖|maven|
|grunt-known-options|1.1.1|间接依赖|npm|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|eyes|0.1.8|间接依赖|npm|
|org.apache.velocity:velocity|1.6.4|直接依赖|maven|
|org.apache.maven.doxia:doxia-sink-api|1.11.1|间接依赖|maven|
|commons-collections:commons-collections|3.2.1|间接依赖|maven|
|xmlbuilder|9.0.4|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)