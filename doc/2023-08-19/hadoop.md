# apache/hadoop安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692597903074025472.svg)](https://www.murphysec.com/console/report/1692597902939807744/1692597903074025472)

仓库描述：Apache Hadoop

仓库地址：[https://github.com/apache/hadoop](https://github.com/apache/hadoop)

| star：13761 | watch：997 | fork：8555 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-19 00:38:08 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-19 02:56:52 | 组件总数：1255 | 漏洞总数：128 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Joyent Node.js ms 资源管理错误漏洞|拒绝服务|[MPS-2017-0610](https://www.oscs1024.com/hd/MPS-2017-0610)|CVE-2015-8315|高危|
|Joyent Node.js tar 后置链接漏洞|在文件访问前对链接解析不恰当（链接跟随）|[MPS-2017-0617](https://www.oscs1024.com/hd/MPS-2017-0617)|CVE-2015-8860|高危|
|Joyent Node.js handlebar 跨站脚本漏洞|XSS|[MPS-2017-0618](https://www.oscs1024.com/hd/MPS-2017-0618)|CVE-2015-8861|中危|
|Google protobuf 缓冲区错误漏洞|越界写入|[MPS-2017-10841](https://www.oscs1024.com/hd/MPS-2017-10841)|CVE-2015-5237|高危|
|Joyent Node.js tough-cookie模块安全漏洞|拒绝服务|[MPS-2017-11145](https://www.oscs1024.com/hd/MPS-2017-11145)|CVE-2017-15010|高危|
|web framework qs模块输入验证漏洞|输入验证不恰当|[MPS-2017-7711](https://www.oscs1024.com/hd/MPS-2017-7711)|CVE-2017-1000048|高危|
|Tough-Cookie 拒绝服务漏洞|拒绝服务|[MPS-2018-11858](https://www.oscs1024.com/hd/MPS-2018-11858)|CVE-2016-1000232|中危|
|LibSass 拒绝服务漏洞|空指针取消引用|[MPS-2018-15348](https://www.oscs1024.com/hd/MPS-2018-15348)|CVE-2018-19797|中危|
|LibSass 拒绝服务漏洞|UAF|[MPS-2018-15372](https://www.oscs1024.com/hd/MPS-2018-15372)|CVE-2018-19827|高危|
|LibSass 拒绝服务漏洞|越界读取|[MPS-2018-15397](https://www.oscs1024.com/hd/MPS-2018-15397)|CVE-2018-19839|中危|
|LibSass 拒绝服务漏洞|空指针取消引用|[MPS-2018-15962](https://www.oscs1024.com/hd/MPS-2018-15962)|CVE-2018-20190|中危|
|Npm 安全漏洞|关键资源权限分配不当|[MPS-2018-2363](https://www.oscs1024.com/hd/MPS-2018-2363)|CVE-2018-7408|高危|
|Hoek 访问控制错误漏洞|MAID|[MPS-2018-3882](https://www.oscs1024.com/hd/MPS-2018-3882)|CVE-2018-3728|高危|
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|Minimatch 拒绝服务漏洞|拒绝服务|[MPS-2018-6725](https://www.oscs1024.com/hd/MPS-2018-6725)|CVE-2016-10540|高危|
|Http-signature 安全漏洞|密码学签名的验证不恰当|[MPS-2018-6996](https://www.oscs1024.com/hd/MPS-2018-6996)|CVE-2017-16005|高危|
|Request 内存泄漏漏洞|通过发送数据的信息暴露|[MPS-2018-7014](https://www.oscs1024.com/hd/MPS-2018-7014)|CVE-2017-16026|中危|
|parsejson模块安全漏洞|拒绝服务|[MPS-2018-7186](https://www.oscs1024.com/hd/MPS-2018-7186)|CVE-2017-16113|高危|
|debug 模块拒绝服务漏洞|拒绝服务|[MPS-2018-7210](https://www.oscs1024.com/hd/MPS-2018-7210)|CVE-2017-16137|中危|
|lodash node 拒绝服务漏洞|拒绝服务|[MPS-2018-7315](https://www.oscs1024.com/hd/MPS-2018-7315)|CVE-2018-3721|中危|
|LibSass 堆缓冲区错误漏洞|越界读取|[MPS-2019-0502](https://www.oscs1024.com/hd/MPS-2019-0502)|CVE-2019-6283|中危|
|LibSass 堆缓冲区错误漏洞|越界读取|[MPS-2019-0503](https://www.oscs1024.com/hd/MPS-2019-0503)|CVE-2019-6284|中危|
|LibSass 堆缓冲区错误漏洞|越界读取|[MPS-2019-0505](https://www.oscs1024.com/hd/MPS-2019-0505)|CVE-2019-6286|中危|
|lodash 存在拒绝服务漏洞|拒绝服务|[MPS-2019-1228](https://www.oscs1024.com/hd/MPS-2019-1228)|CVE-2018-16487|中危|
|LibSass < 3.6.3 缓冲区错误漏洞|越界读取|[MPS-2019-14247](https://www.oscs1024.com/hd/MPS-2019-14247)|CVE-2019-18798|中危|
|LibSass 程序崩溃漏洞|空指针取消引用|[MPS-2019-14248](https://www.oscs1024.com/hd/MPS-2019-14248)|CVE-2019-18799|中危|
|npm CLI 任意文件写入漏洞|UNIX符号链接跟随|[MPS-2019-16248](https://www.oscs1024.com/hd/MPS-2019-16248)|CVE-2019-16775|中危|
|npm CLI 路径遍历漏洞|路径遍历|[MPS-2019-16249](https://www.oscs1024.com/hd/MPS-2019-16249)|CVE-2019-16776|高危|
|npm CLI node_modules二进制文件覆盖漏洞|权限管理不当|[MPS-2019-16250](https://www.oscs1024.com/hd/MPS-2019-16250)|CVE-2019-16777|中危|
|handlebars 原型污染漏洞|原型污染|[MPS-2019-16888](https://www.oscs1024.com/hd/MPS-2019-16888)|CVE-2019-19919|严重|
|Apache Log4j SocketServer反序列化漏洞|反序列化|[MPS-2019-17271](https://www.oscs1024.com/hd/MPS-2019-17271)|CVE-2019-17571|严重|
|Select2 跨站脚本漏洞|XSS|[MPS-2019-3047](https://www.oscs1024.com/hd/MPS-2019-3047)|CVE-2016-10744|中危|
|LibSass 资源管理错误漏洞|未经控制的递归|[MPS-2019-4291](https://www.oscs1024.com/hd/MPS-2019-4291)|CVE-2018-20821|中危|
|node-sass 堆栈溢出漏洞|未经控制的递归|[MPS-2019-4292](https://www.oscs1024.com/hd/MPS-2019-4292)|CVE-2018-20822|中危|
|node-tar [, 2.2.2)、[3.0.0, 4.4.2)  任意文件覆盖漏洞|在文件访问前对链接解析不恰当（链接跟随）|[MPS-2019-4705](https://www.oscs1024.com/hd/MPS-2019-4705)|CVE-2018-20834|高危|
|lodash <4.7.11 正则表达式拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2019-8123](https://www.oscs1024.com/hd/MPS-2019-8123)|CVE-2019-1010266|中危|
|lodash 原型污染漏洞|拒绝服务|[MPS-2019-8636](https://www.oscs1024.com/hd/MPS-2019-8636)|CVE-2019-10744|严重|
|Ajv v6.12.2 输入验证错误漏洞|MAID|[MPS-2020-10525](https://www.oscs1024.com/hd/MPS-2020-10525)|CVE-2020-15366|中危|
|npm bl 内存泄露漏洞|越界读取|[MPS-2020-12199](https://www.oscs1024.com/hd/MPS-2020-12199)|CVE-2020-8244|中危|
|handlebars 代码注入漏洞|代码注入|[MPS-2020-13732](https://www.oscs1024.com/hd/MPS-2020-13732)|CVE-2019-20920|高危|
|NPM npm-user-validate 安全漏洞|拒绝服务|[MPS-2020-14933](https://www.oscs1024.com/hd/MPS-2020-14933)|CVE-2020-7754|高危|
|lodash <4.17.15 原型污染漏洞|原型污染|[MPS-2020-15679](https://www.oscs1024.com/hd/MPS-2020-15679)|CVE-2020-8203|高危|
|Mout deepFillIn 代码问题漏洞|拒绝服务|[MPS-2020-17290](https://www.oscs1024.com/hd/MPS-2020-17290)|CVE-2020-7792|高危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Ini <1.3.6原型污染漏洞|拒绝服务|[MPS-2020-17544](https://www.oscs1024.com/hd/MPS-2020-17544)|CVE-2020-7788|高危|
|minimist 原型污染漏洞|原型污染|[MPS-2020-3516](https://www.oscs1024.com/hd/MPS-2020-3516)|CVE-2020-7598|中危|
|Apache Log4j2 SmtpAppender证书验证不当漏洞|证书验证不恰当|[MPS-2020-6684](https://www.oscs1024.com/hd/MPS-2020-6684)|CVE-2020-9488|低危|
|websocket-extensions<0.1.4 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2020-8041](https://www.oscs1024.com/hd/MPS-2020-8041)|CVE-2020-7662|高危|
|websocket-extensions 拒绝服务漏洞|拒绝服务|[MPS-2020-8042](https://www.oscs1024.com/hd/MPS-2020-8042)|CVE-2020-7663|高危|
|chownr package竞争条件问题漏洞|检查时间与使用时间(TOCTOU)的竞争条件|[MPS-2020-8858](https://www.oscs1024.com/hd/MPS-2020-8858)|CVE-2017-18869|低危|
|npm CLI 日志信息泄露漏洞|日志敏感信息泄露|[MPS-2020-9965](https://www.oscs1024.com/hd/MPS-2020-9965)|CVE-2020-15095|中危|
|Socketio Engineio 资源管理错误漏洞|拒绝服务|[MPS-2021-0192](https://www.oscs1024.com/hd/MPS-2021-0192)|CVE-2020-36049|高危|
|Sass Node-sass 信任管理问题漏洞|证书验证不恰当|[MPS-2021-0364](https://www.oscs1024.com/hd/MPS-2021-0364)|CVE-2020-24025|中危|
|yeikos js.merge  < 2.1.1 原型污染漏洞|原型污染|[MPS-2021-1900](https://www.oscs1024.com/hd/MPS-2021-1900)|CVE-2020-28499|严重|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|jsonpointer <5.0.0 原型污染漏洞 |使用不兼容类型访问资源（类型混淆）|[MPS-2021-19846](https://www.oscs1024.com/hd/MPS-2021-19846)|CVE-2021-23807|严重|
|requests 代码注入漏洞|代码注入|[MPS-2021-2418](https://www.oscs1024.com/hd/MPS-2021-2418)|CVE-2020-28502|高危|
|lodash 拒绝服务漏洞|拒绝服务|[MPS-2021-2574](https://www.oscs1024.com/hd/MPS-2021-2574)|CVE-2020-28500|中危|
|lodash 命令注入漏洞|代码注入|[MPS-2021-2638](https://www.oscs1024.com/hd/MPS-2021-2638)|CVE-2021-23337|高危|
|Npm Node-tar 后置链接漏洞||[MPS-2021-28486](https://www.oscs1024.com/hd/MPS-2021-28486)|CVE-2021-37701|高危|
|Npm Node-tar 后置链接漏洞||[MPS-2021-28488](https://www.oscs1024.com/hd/MPS-2021-28488)|CVE-2021-37712|高危|
|node-tar 路径遍历漏洞|路径遍历|[MPS-2021-28489](https://www.oscs1024.com/hd/MPS-2021-28489)|CVE-2021-37713|高危|
|Worms David node-printf 安全漏洞|ReDoS|[MPS-2021-3008](https://www.oscs1024.com/hd/MPS-2021-3008)|CVE-2021-23354|高危|
|Chris Brody xmldom XXE漏洞|解释冲突|[MPS-2021-3069](https://www.oscs1024.com/hd/MPS-2021-3069)|CVE-2021-21366|中危|
|nodejs 正则表达式漏洞|拒绝服务|[MPS-2021-31423](https://www.oscs1024.com/hd/MPS-2021-31423)|CVE-2021-3777|高危|
|Ruy Adorno hosted-git-info 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-3400](https://www.oscs1024.com/hd/MPS-2021-3400)|CVE-2021-23362|中危|
|Async 原型污染漏洞|原型污染|[MPS-2021-34434](https://www.oscs1024.com/hd/MPS-2021-34434)|CVE-2021-43138|高危|
|json-schema 安全漏洞|原型污染|[MPS-2021-34478](https://www.oscs1024.com/hd/MPS-2021-34478)|CVE-2021-3918|严重|
|braces <2.3.1 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-3692](https://www.oscs1024.com/hd/MPS-2021-3692)|CVE-2018-1109|中危|
|Markdown-It 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-37028](https://www.oscs1024.com/hd/MPS-2021-37028)|CVE-2022-21670|中危|
|Apache Log4j JMSAppender反序列化漏洞||[MPS-2021-38359](https://www.oscs1024.com/hd/MPS-2021-38359)|CVE-2021-4104|高危|
|minimist 安全漏洞|原型污染|[MPS-2021-38405](https://www.oscs1024.com/hd/MPS-2021-38405)|CVE-2021-44906|严重|
|handlebars 远程代码执行 (RCE) 漏洞|代码注入|[MPS-2021-4548](https://www.oscs1024.com/hd/MPS-2021-4548)|CVE-2021-23369|严重|
|Dan DeFelippi node-XMLHttpRequest 信任管理问题漏洞|证书验证不恰当|[MPS-2021-5338](https://www.oscs1024.com/hd/MPS-2021-5338)|CVE-2021-31597|严重|
|npm path-parse 安全漏洞|拒绝服务|[MPS-2021-6165](https://www.oscs1024.com/hd/MPS-2021-6165)|CVE-2021-23343|高危|
|handlebars < 4.7.7 存在原型污染漏洞|原型污染|[MPS-2021-6180](https://www.oscs1024.com/hd/MPS-2021-6180)|CVE-2021-23383|严重|
|trim-newlines 存在拒绝服务漏洞|拒绝服务|[MPS-2021-7398](https://www.oscs1024.com/hd/MPS-2021-7398)|CVE-2021-33623|高危|
|shelljs < 0.8.5 存在特权管理不恰当漏洞|权限管理不当|[MPS-2022-0508](https://www.oscs1024.com/hd/MPS-2022-0508)|CVE-2022-0144|高危|
|Moment.js 正则拒绝服务漏洞|拒绝服务|[MPS-2022-11159](https://www.oscs1024.com/hd/MPS-2022-11159)|CVE-2022-31129|高危|
|org.ojalgo:ojalgo 存在密码学问题漏洞|密码学问题|[MPS-2022-11904](https://www.oscs1024.com/hd/MPS-2022-11904)||中危|
|clean-css < 4.1.11 存在拒绝服务漏洞||[MPS-2022-12865](https://www.oscs1024.com/hd/MPS-2022-12865)||低危|
|concat-stream 存在信息泄露漏洞|通过发送数据的信息暴露|[MPS-2022-12867](https://www.oscs1024.com/hd/MPS-2022-12867)||中危|
|handlebars 存在原型污染漏洞|MAID|[MPS-2022-13730](https://www.oscs1024.com/hd/MPS-2022-13730)||高危|
|handlebars 存在代码注入漏洞|代码注入|[MPS-2022-13733](https://www.oscs1024.com/hd/MPS-2022-13733)||高危|
|handlebars 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13734](https://www.oscs1024.com/hd/MPS-2022-13734)||严重|
|handlebars<4.6.0 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13735](https://www.oscs1024.com/hd/MPS-2022-13735)||中危|
|is-my-json-valid 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13795](https://www.oscs1024.com/hd/MPS-2022-13795)||高危|
|is-my-json-valid<2.20.3 存在代码注入漏洞|代码注入|[MPS-2022-13796](https://www.oscs1024.com/hd/MPS-2022-13796)||高危|
|jsonpointer<4.1.0 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13815](https://www.oscs1024.com/hd/MPS-2022-13815)||严重|
|lodash<4.17.20 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13841](https://www.oscs1024.com/hd/MPS-2022-13841)||高危|
|lodash<4.17.17 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13842](https://www.oscs1024.com/hd/MPS-2022-13842)||高危|
|markdown-it<10.0.0 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13854](https://www.oscs1024.com/hd/MPS-2022-13854)||中危|
|merge<2.1.0 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13875](https://www.oscs1024.com/hd/MPS-2022-13875)||高危|
|minimatch < 3.0.2 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13882](https://www.oscs1024.com/hd/MPS-2022-13882)||高危|
|uglify-js <3.14.3 正则表达式拒绝服务漏洞|ReDoS|[MPS-2022-14112](https://www.oscs1024.com/hd/MPS-2022-14112)||中危|
|Apache Log4j JDBCAppender SQL注入漏洞|SQL注入|[MPS-2022-1444](https://www.oscs1024.com/hd/MPS-2022-1444)|CVE-2022-23305|严重|
|Apache Log4j Chainsaw反序列化漏洞|反序列化|[MPS-2022-1445](https://www.oscs1024.com/hd/MPS-2022-1445)|CVE-2022-23307|高危|
|Apache Log4j 反序列化漏洞|反序列化|[MPS-2022-1446](https://www.oscs1024.com/hd/MPS-2022-1446)|CVE-2022-23302|高危|
|Eclipse Jetty URI注入漏洞|注入|[MPS-2022-18060](https://www.oscs1024.com/hd/MPS-2022-18060)|CVE-2022-2047|低危|
|follow-redirects<1.14.8 信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-3636](https://www.oscs1024.com/hd/MPS-2022-3636)|CVE-2022-0536|中危|
|Moment.js 路径遍历漏洞|路径遍历|[MPS-2022-3752](https://www.oscs1024.com/hd/MPS-2022-3752)|CVE-2022-24785|中危|
|Express 中的 qs 模块存在原型污染漏洞|原型污染|[MPS-2022-3967](https://www.oscs1024.com/hd/MPS-2022-3967)|CVE-2022-24999|高危|
|Mout 安全漏洞|原型污染|[MPS-2022-5050](https://www.oscs1024.com/hd/MPS-2022-5050)|CVE-2022-21213|高危|
|scss-tokenizer 安全漏洞|ReDoS|[MPS-2022-5119](https://www.oscs1024.com/hd/MPS-2022-5119)|CVE-2022-25758|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|XMLDOM 安全漏洞|原型污染|[MPS-2022-53529](https://www.oscs1024.com/hd/MPS-2022-53529)|CVE-2022-37616|严重|
|Bouncy Castle <1.69 认证绕过漏洞|密码学问题|[MPS-2022-54305](https://www.oscs1024.com/hd/MPS-2022-54305)||中危|
|moment-timezone 存在命令注入|命令注入|[MPS-2022-56430](https://www.oscs1024.com/hd/MPS-2022-56430)||严重|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|minimatch 资源管理错误漏洞|拒绝服务|[MPS-2022-59845](https://www.oscs1024.com/hd/MPS-2022-59845)|CVE-2022-3517|高危|
|XMLDOM 输入验证错误漏洞|输入中的一致性验证不当|[MPS-2022-62941](https://www.oscs1024.com/hd/MPS-2022-62941)|CVE-2022-39353|严重|
|Tauri 原型污染漏洞|原型污染|[MPS-2022-65568](https://www.oscs1024.com/hd/MPS-2022-65568)|CVE-2022-46175|高危|
|hawk 资源管理错误漏洞|拒绝服务|[MPS-2022-8568](https://www.oscs1024.com/hd/MPS-2022-8568)|CVE-2022-29167|高危|
|vercel ms 安全漏洞|ReDoS|[MPS-2023-0304](https://www.oscs1024.com/hd/MPS-2023-0304)|CVE-2017-20162|中危|
|debug 安全漏洞|ReDoS|[MPS-2023-0646](https://www.oscs1024.com/hd/MPS-2023-0646)|CVE-2017-20165|高危|
|Apache Kafka Connect 模块JNDI注入漏洞|反序列化|[MPS-2023-3834](https://www.oscs1024.com/hd/MPS-2023-3834)|CVE-2023-25194|高危|
|Eclipse Jetty 资源管理错误漏洞|拒绝服务|[MPS-2023-4997](https://www.oscs1024.com/hd/MPS-2023-4997)|CVE-2023-26048|中危|
|Eclipse Jetty 信息泄露漏洞|XSS|[MPS-2023-4998](https://www.oscs1024.com/hd/MPS-2023-4998)|CVE-2023-26049|中危|
|tough-cookie 安全漏洞|原型污染|[MPS-2023-5130](https://www.oscs1024.com/hd/MPS-2023-5130)|CVE-2023-26136|严重|
|request SSRF防御绕过漏洞|SSRF|[MPS-2023-7722](https://www.oscs1024.com/hd/MPS-2023-7722)|CVE-2023-28155|中危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|tough-cookie<4.1.3 存在原型污染漏洞|原型污染|[MPS-esyq-56vx](https://www.oscs1024.com/hd/MPS-esyq-56vx)||中危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|json-io 缓冲区错误漏洞|越界写入|[MPS-jtye-gw8s](https://www.oscs1024.com/hd/MPS-jtye-gw8s)|CVE-2023-34610|高危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|xmlhttprequest-ssl|1.5.1|1.6.2|间接依赖|强烈建议修复|C:1|H:1|M:0|L:0|
|qs|6.5.2|6.10.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tmpl|1.0.4|1.0.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|hawk|3.1.3|9.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|debug|1.0.2|3.1.0|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|debug|1.0.3|3.1.0|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|io.netty:netty-handler|4.1.94.Final|4.1.94.final|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|debug|1.0.4|3.1.0|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|tar|1.0.3|6.1.9|间接依赖|建议修复|C:0|H:5|M:0|L:0|
|merge|1.2.1|2.1.1|间接依赖|建议修复|C:1|H:1|M:0|L:0|
|qs|6.4.0|6.10.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|ini|1.3.5|1.3.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|minimist|1.2.5|1.2.6|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|minimatch|0.2.14|3.0.5|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|handlebars|3.0.7|4.7.7|间接依赖|建议修复|C:4|H:3|M:2|L:0|
|trim-newlines|1.0.0|4.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.12.7.1|2.14.0-rc1|直接依赖|建议修复|C:0|H:0|M:3|L:0|
|minimatch|3.0.4|3.0.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|express|4.17.1|4.17.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|json5|0.4.0|2.2.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|debug|2.1.0|3.1.0|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|lodash|2.3.0|4.17.21|间接依赖|建议修复|C:1|H:4|M:4|L:0|
|tar|2.2.2|6.1.9|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|npm-user-validate|0.1.5|1.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tough-cookie|2.5.0|4.1.3|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|http-signature|1.1.1||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|websocket-extensions|0.1.3|0.1.4|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|log4j:log4j|1.2.17||直接依赖|建议修复|C:2|H:3|M:0|L:1|
|scss-tokenizer|0.2.3|0.4.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|shelljs|0.3.0|0.8.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|minimist|1.2.0|1.2.6|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|jsonpointer|4.0.1|5.0.0|间接依赖|建议修复|C:2|H:0|M:0|L:0|
|is-my-json-valid|2.20.0|2.20.3|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|moment-timezone|0.3.1|0.5.35|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|tough-cookie|2.2.2|4.1.3|间接依赖|建议修复|C:1|H:1|M:1|L:0|
|lodash|3.10.1|4.17.21|间接依赖|建议修复|C:1|H:4|M:4|L:0|
|qs|6.2.3|6.10.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|lodash|2.4.2|4.17.21|间接依赖|建议修复|C:1|H:4|M:4|L:0|
|minimatch|2.0.10|3.0.5|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|org.eclipse.jetty:jetty-server|9.4.51.v20230217|12.0.0.beta0|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|socket.io-parser|2.2.2|4.2.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|printf|0.2.5|0.6.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|minimatch|1.0.0|3.0.5|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|minimist|0.0.8|1.2.6|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|xmldom|0.1.31|0.5.0|间接依赖|建议修复|C:2|H:0|M:1|L:0|
|ms|0.6.2|2.0.0|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|com.google.protobuf:protobuf-java|3.7.1|3.21.7|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|tough-cookie|2.3.4|4.1.3|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|http-signature|0.11.0||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.apache.kafka:kafka-clients|2.8.2|3.4.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|json-schema|0.2.3|0.4.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|hoek|2.16.3|5.0.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|qs|6.7.0|6.10.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|mout|0.9.1|1.2.4|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|debug|0.7.4|3.1.0|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|com.google.protobuf:protobuf-java|2.5.0|3.21.7|直接依赖|建议修复|C:0|H:1|M:2|L:0|
|path-parse|1.0.6|1.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|socket.io-parser|2.2.4|4.2.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|parsejson|0.0.1||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.cedarsoftware:json-io|2.5.1||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|minimist|0.0.10|1.2.6|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|node-sass|4.14.1|7.0.0|间接依赖|建议修复|C:0|H:1|M:11|L:0|
|http-signature|1.2.0||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|npm|2.14.10|6.14.6|间接依赖|建议修复|C:0|H:2|M:3|L:0|
|debug|2.2.0|3.1.0|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|request|2.65.0|2.68.0|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|qs|5.2.0|6.10.3|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|request|2.81.0||直接依赖|可选修复|C:0|H:0|M:1|L:0|
|chownr|1.0.1|1.1.0|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|bl|1.1.2|4.0.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|5.0.3|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|qs|5.2.1|6.10.3|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|lodash-es|3.10.1|4.17.21|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|clean-css|2.2.23|4.1.11|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|com.google.guava:guava|27.0-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:1|
|org.ojalgo:ojalgo|43.0|48.3.2|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|markdown-it|4.3.0|12.3.2|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|semver|5.3.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|follow-redirects|1.14.7|1.14.8|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|async|2.6.3|3.2.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|semver|5.7.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|lodash.merge|3.3.2|4.6.2|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|braces|1.8.5|2.3.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|4.3.6|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|moment|2.24.0|2.29.4|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|select2|4.0.0|4.0.8|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.bouncycastle:bcprov-jdk15on|1.68|1.69|直接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.eclipse.jetty:jetty-http|9.4.51.v20230217|11.0.10|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|markdown-it|4.4.0|12.3.2|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|hosted-git-info|2.1.5|3.0.8|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|12.0.1|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:2|L:1|
|ms|0.7.1|2.0.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|bl|1.0.3|4.0.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|request|2.74.0||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|uglify-js|2.8.29|3.14.3|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|concat-stream|1.5.0|1.5.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|qs|5.1.0|6.10.3|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|request|2.88.2||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|hosted-git-info|2.8.5|3.0.8|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|ajv|4.11.8|6.12.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|676|Low|
|Apache-2.0|274|Low|
|BSD-2-Clause|20|Low|
|ISC|136|Low|
|CDDL-1.1|11|Low|
|EPL-2.0|19|Low|
|BSD-3-Clause|34|Low|
|BSD|5|Low|
|CDDL-1.0|2|Low|
|EPL-1.0|6|Low|
|Unlicense|2|Low|
|Artistic-2.0|1|Low|
|Public Domain|1|Low|
|自定义许可证|1|Low|
|LGPL-2.1|1|Medium|
|BSD-like|1|Low|
|WTFPL|1|Low|
|CC-BY-3.0|1|Low|
|CC0-1.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|media-typer|0.3.0|间接依赖|npm|
|org.apache.httpcomponents:httpclient|4.5.13|直接依赖|maven|
|cmd-shim|2.0.2|间接依赖|npm|
|clean-base-url|1.0.0|间接依赖|npm|
|com.sun.xml.bind:jaxb-impl|2.2.3-1|间接依赖|maven|
|org.eclipse.jetty:jetty-alpn-client|9.4.44.v20210927|间接依赖|maven|
|pseudomap|1.0.2|间接依赖|npm|
|@sailshq/lodash|3.10.4|间接依赖|npm|
|hosted-git-info|2.1.5|间接依赖|npm|
|org.apache.avro:avro|1.9.2|直接依赖|maven|
|lodash.assign|3.2.0|间接依赖|npm|
|async|2.6.3|间接依赖|npm|
|ecc-jsbn|0.1.2|间接依赖|npm|
|kew|0.7.0|间接依赖|npm|
|expand-brackets|0.1.5|间接依赖|npm|
|npm-package-arg|4.0.2|间接依赖|npm|
|org.apache.kerby:kerb-util|2.0.3|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.8.0|间接依赖|maven|
|block-stream|0.0.8|间接依赖|npm|
|broccoli-merge-trees|1.2.4|间接依赖|npm|
|babel-plugin-property-literals|1.0.1|间接依赖|npm|
|xmlhttprequest-ssl|1.5.1|间接依赖|npm|
|klassy|0.1.3|间接依赖|npm|
|regexpu|1.3.0|间接依赖|npm|
|broccoli-persistent-filter|1.4.6|间接依赖|npm|
|org.glassfish.grizzly:grizzly-http|2.2.16|间接依赖|maven|
|domhandler|2.3.0|间接依赖|npm|
|org.apache.hadoop:hadoop-minicluster|3.4.0-SNAPSHOT|直接依赖|maven|
|org.apache.hadoop:hadoop-client-api|3.4.0-SNAPSHOT|直接依赖|maven|
|org.apache.hadoop:hadoop-dynamometer-blockgen|3.4.0-SNAPSHOT|直接依赖|maven|
|node-gyp|3.0.3|间接依赖|npm|
|cpr|0.4.2|间接依赖|npm|
|moment|2.24.0|间接依赖|npm|
|ansistyles|0.1.3|间接依赖|npm|
|inflection|1.12.0|间接依赖|npm|
|quick-temp|0.1.8|间接依赖|npm|
|is-posix-bracket|0.1.1|间接依赖|npm|
|xmldom|0.1.31|间接依赖|npm|
|findup|0.1.5|间接依赖|npm|
|basic-auth|2.0.1|间接依赖|npm|
|component-emitter|1.1.2|间接依赖|npm|
|mkdirp|0.5.0|间接依赖|npm|
|osenv|0.0.3|间接依赖|npm|
|org.eclipse.jetty:jetty-server|9.4.51.v20230217|直接依赖|maven|
|iconv-lite|0.4.13|间接依赖|npm|
|lodash-node|2.4.1|间接依赖|npm|
|ember-wormhole|0.3.6|间接依赖|npm|
|git-tools|0.1.4|间接依赖|npm|
|readline2|0.1.1|间接依赖|npm|
|process-relative-require|1.0.0|间接依赖|npm|
|fs-tree-diff|0.3.1|间接依赖|npm|
|iconv-lite|0.4.24|间接依赖|npm|
|broccoli-slow-trees|1.1.0|间接依赖|npm|
|tunnel-agent|0.4.3|间接依赖|npm|
|isarray|0.0.1|间接依赖|npm|
|org.codehaus.plexus:plexus-classworlds|2.4|间接依赖|maven|
|node-gyp|3.8.0|间接依赖|npm|
|broccoli-sane-watcher|1.1.5|间接依赖|npm|
|wide-align|1.1.3|间接依赖|npm|
|commander|2.2.0|间接依赖|npm|
|ms|2.1.1|间接依赖|npm|
|tryor|0.1.2|间接依赖|npm|
|org.apache.hadoop:hadoop-yarn-server-applicationhistoryservice|3.4.0-SNAPSHOT|直接依赖|maven|
|nopt|3.0.6|间接依赖|npm|
|fs-monitor-stack|1.1.1|间接依赖|npm|
|npmlog|1.2.1|间接依赖|npm|
|org.glassfish.grizzly:grizzly-http-servlet|2.2.16|间接依赖|maven|
|glob|5.0.15|间接依赖|npm|
|babel-plugin-react-constant-elements|1.0.3|间接依赖|npm|
|request|2.74.0|间接依赖|npm|
|com.jcraft:jsch|0.1.55|直接依赖|maven|
|stringmap|0.2.2|间接依赖|npm|
|es6-iterator|0.1.3|间接依赖|npm|
|graceful-fs|4.2.6|直接依赖|npm|
|io.reactivex:rxnetty|0.4.20|间接依赖|maven|
|org.eclipse.jetty.websocket:websocket-client|9.4.51.v20230217|直接依赖|maven|
|read-package-json|2.0.13|间接依赖|npm|
|is-extglob|1.0.0|间接依赖|npm|
|currently-unhandled|0.4.1|间接依赖|npm|
|com.google.inject:guice|4.0|直接依赖|maven|
|org.ow2.asm:asm-commons|9.4|间接依赖|maven|
|sha|2.0.1|间接依赖|npm|
|org.apache.hadoop:hadoop-archive-logs|3.4.0-SNAPSHOT|直接依赖|maven|
|builtins|0.0.7|间接依赖|npm|
|chalk|0.4.0|间接依赖|npm|
|resolve-package-path|1.2.7|间接依赖|npm|
|heimdalljs-logger|0.1.10|间接依赖|npm|
|jira|3.1.1|间接依赖|pip|
|bluebird|2.11.0|间接依赖|npm|
|ansi-regex|2.1.1|间接依赖|npm|
|ast-types|0.9.6|间接依赖|npm|
|org.eclipse.jetty.http2:http2-http-client-transport|9.4.44.v20210927|间接依赖|maven|
|com.github.pjfanning:jersey-json|1.20|直接依赖|maven|
|es6-symbol|3.1.3|间接依赖|npm|
|detect-indent|3.0.1|间接依赖|npm|
|normalize-path|2.1.1|间接依赖|npm|
|hasha|2.2.0|间接依赖|npm|
|merge|1.2.1|间接依赖|npm|
|combined-stream|1.0.8|间接依赖|npm|
|is-my-json-valid|2.20.0|间接依赖|npm|
|has-binary|0.1.6|间接依赖|npm|
|org.hamcrest:hamcrest-core|1.3|间接依赖|maven|
|requires-port|1.0.0|间接依赖|npm|
|normalize-git-url|3.0.2|间接依赖|npm|
|org.ojalgo:ojalgo|43.0|直接依赖|maven|
|esprima-fb|15001.1001.0-dev-harmony-fb|间接依赖|npm|
|qunitjs|1.23.1|间接依赖|npm|
|regenerator|0.8.40|间接依赖|npm|
|require-main-filename|2.0.0|间接依赖|npm|
|hawk|3.1.3|间接依赖|npm|
|minimist|1.2.0|间接依赖|npm|
|iferr|0.1.5|间接依赖|npm|
|source-map-support|0.2.10|间接依赖|npm|
|parsejson|0.0.1|间接依赖|npm|
|sprintf-js|1.1.2|间接依赖|npm|
|bower-config|0.6.1|间接依赖|npm|
|for-own|0.1.5|间接依赖|npm|
|ansi|0.3.1|间接依赖|npm|
|org.apache.hadoop:hadoop-datajoin|3.4.0-SNAPSHOT|直接依赖|maven|
|express|4.17.1|间接依赖|npm|
|org.apache.kerby:kerby-xdr|2.0.3|间接依赖|maven|
|slide|1.1.6|间接依赖|npm|
|yargs-parser|13.1.2|间接依赖|npm|
|binaryextensions|2.2.0|间接依赖|npm|
|org.apache.hadoop:hadoop-yarn-server-tests|3.4.0-SNAPSHOT|直接依赖|maven|
|org.openjdk.jmh:jmh-core|1.20|直接依赖|maven|
|com.sun.codemodel:codemodel|2.6|间接依赖|maven|
|com.fasterxml.uuid:java-uuid-generator|3.1.4|间接依赖|maven|
|pinkie|2.0.4|间接依赖|npm|
|bl|1.1.2|间接依赖|npm|
|string_decoder|0.10.31|间接依赖|npm|
|babel-plugin-eval|1.0.1|间接依赖|npm|
|eventemitter3|4.0.7|间接依赖|npm|
|testem|0.9.11|间接依赖|npm|
|scss-tokenizer|0.2.3|间接依赖|npm|
|broccoli-asset-rev|2.4.2|直接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|entities|1.1.2|间接依赖|npm|
|org.bouncycastle:bcpkix-jdk15on|1.68|直接依赖|maven|
|backo2|1.0.2|间接依赖|npm|
|lodash._cacheindexof|3.0.2|间接依赖|npm|
|org.apache.hadoop:hadoop-mapreduce-client-jobclient|3.4.0-SNAPSHOT|直接依赖|maven|
|ember-cli-version-checker|1.3.1|间接依赖|npm|
|repeat-string|1.6.1|间接依赖|npm|
|io.grpc:grpc-protobuf-lite|1.26.0|间接依赖|maven|
|io.netty:netty-codec-http|4.1.94.Final|间接依赖|maven|
|com.google.guava:guava|27.0-jre|直接依赖|maven|
|org.apache.maven:maven-core|3.0.5|直接依赖|maven|
|read-installed|4.0.3|间接依赖|npm|
|utf8|2.1.0|间接依赖|npm|
|shelljs|0.3.0|间接依赖|npm|
|object-keys|1.0.1|间接依赖|npm|
|lru-queue|0.1.0|间接依赖|npm|
|http-proxy|1.18.1|间接依赖|npm|
|fs-tree-diff|0.4.4|间接依赖|npm|
|com.microsoft.azure:azure-cosmosdb-gateway|2.4.5|间接依赖|maven|
|io.opencensus:opencensus-contrib-grpc-metrics|0.24.0|间接依赖|maven|
|org.objenesis:objenesis|2.6|间接依赖|maven|
|fresh|0.5.2|间接依赖|npm|
|signal-exit|3.0.2|间接依赖|npm|
|lodash.isarray|3.0.4|间接依赖|npm|
|arr-diff|2.0.0|间接依赖|npm|
|commons-cli:commons-cli|1.5.0|直接依赖|maven|
|retry|0.8.0|间接依赖|npm|
|lodash|3.10.1|间接依赖|npm|
|trim-newlines|1.0.0|间接依赖|npm|
|io.netty:netty-resolver-dns|4.1.94.Final|间接依赖|maven|
|source-map-url|0.3.0|间接依赖|npm|
|org.apache.hadoop:hadoop-resourceestimator|3.4.0-SNAPSHOT|直接依赖|maven|
|isarray|1.0.0|间接依赖|npm|
|string_decoder|1.1.1|间接依赖|npm|
|io.netty:netty-common|4.1.94.Final|间接依赖|maven|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|wordwrap|0.0.3|间接依赖|npm|
|output-file-sync|1.1.2|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|org.eclipse.jetty:jetty-xml|9.4.51.v20230217|间接依赖|maven|
|yargs|3.10.0|间接依赖|npm|
|promzard|0.3.0|间接依赖|npm|
|is-utf8|0.2.1|间接依赖|npm|
|broccoli-asset-rewrite|1.1.0|间接依赖|npm|
|ember-cli-babel|5.1.6|直接依赖|npm|
|org.sonatype.sisu:sisu-inject-plexus|2.3.0|间接依赖|maven|
|matcher-collection|1.1.2|间接依赖|npm|
|defs|1.1.1|间接依赖|npm|
|debug|2.1.0|间接依赖|npm|
|normalize-package-data|2.3.8|间接依赖|npm|
|lru-cache|4.1.5|间接依赖|npm|
|debug|1.0.4|间接依赖|npm|
|oauth-sign|0.9.0|间接依赖|npm|
|mkdirp|0.4.2|间接依赖|npm|
|init-package-json|1.9.6|间接依赖|npm|
|cli-color|0.3.3|间接依赖|npm|
|content-disposition|0.5.3|间接依赖|npm|
|com.google.protobuf:protobuf-java|2.5.0|直接依赖|maven|
|hash-for-dep|1.5.1|间接依赖|npm|
|content-type|1.0.4|间接依赖|npm|
|char-spinner|1.0.1|间接依赖|npm|
|node-sass|4.14.1|间接依赖|npm|
|cliui|5.0.0|间接依赖|npm|
|js-tokens|1.0.1|间接依赖|npm|
|inquirer|0.5.1|间接依赖|npm|
|org.apache.kerby:kerby-pkix|2.0.3|间接依赖|maven|
|on-finished|2.3.0|间接依赖|npm|
|org.jruby.jcodings:jcodings|1.0.13|间接依赖|maven|
|broccoli-less-single|0.6.4|间接依赖|npm|
|ember-cli-numeral|0.2.0|直接依赖|npm|
|uglify-js|2.8.29|直接依赖|npm|
|org.eclipse.jetty.websocket:websocket-servlet|9.4.51.v20230217|间接依赖|maven|
|minimist|0.0.10|间接依赖|npm|
|array-equal|1.0.0|间接依赖|npm|
|js-base64|2.6.4|间接依赖|npm|
|isbinaryfile|2.0.4|间接依赖|npm|
|recast|0.10.43|间接依赖|npm|
|org.apache.commons:commons-text|1.10.0|直接依赖|maven|
|umask|1.1.0|间接依赖|npm|
|org.apache.hadoop:hadoop-client|3.4.0-SNAPSHOT|直接依赖|maven|
|range-parser|1.2.1|间接依赖|npm|
|array-flatten|1.1.1|间接依赖|npm|
|engine.io-pure|1.5.9|间接依赖|npm|
|org.codehaus.plexus:plexus-interpolation|1.14|间接依赖|maven|
|wrappy|1.0.2|间接依赖|npm|
|imurmurhash|0.1.4|间接依赖|npm|
|npm-normalize-package-bin|1.0.1|间接依赖|npm|
|npm-package-arg|5.1.2|间接依赖|npm|
|better-assert|1.0.2|间接依赖|npm|
|http-signature|1.1.1|间接依赖|npm|
|xdg-basedir|2.0.0|间接依赖|npm|
|utils-merge|1.0.1|间接依赖|npm|
|har-validator|4.2.1|间接依赖|npm|
|es5-ext|0.10.53|间接依赖|npm|
|async|1.5.2|间接依赖|npm|
|org.jline:jline|3.9.0|直接依赖|maven|
|ember-cli-less|1.5.7|间接依赖|npm|
|org.lz4:lz4-java|1.7.1|间接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|直接依赖|maven|
|org.apache.hadoop:hadoop-hdfs|3.4.0-SNAPSHOT|直接依赖|maven|
|console-control-strings|1.1.0|间接依赖|npm|
|tar|2.2.2|间接依赖|npm|
|cliui|2.1.0|间接依赖|npm|
|growl|1.10.5|间接依赖|npm|
|indent-string|2.1.0|间接依赖|npm|
|window-size|0.1.0|间接依赖|npm|
|universalify|0.1.2|间接依赖|npm|
|timers-ext|0.1.7|间接依赖|npm|
|com.google.inject.extensions:guice-servlet|4.2.3|直接依赖|maven|
|realize-package-specifier|3.0.3|间接依赖|npm|
|org.apache.hadoop:hadoop-mapreduce-client-nativetask|3.4.0-SNAPSHOT|直接依赖|maven|
|org.sonatype.aether:aether-spi|1.13.1|间接依赖|maven|
|rimraf|2.4.5|间接依赖|npm|
|prr|1.0.1|间接依赖|npm|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.12.7|直接依赖|maven|
|camelcase|2.1.1|间接依赖|npm|
|io.netty:netty-transport-native-kqueue|4.1.94.Final|间接依赖|maven|
|org.apache.hadoop:hadoop-aliyun|3.4.0-SNAPSHOT|直接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.94.Final|直接依赖|maven|
|validate-npm-package-license|3.0.4|间接依赖|npm|
|http-errors|1.7.2|间接依赖|npm|
|recast|0.11.23|间接依赖|npm|
|qs|5.2.1|间接依赖|npm|
|broccoli-filter|0.1.14|间接依赖|npm|
|lodash-es|3.10.1|间接依赖|npm|
|defaults|1.0.3|间接依赖|npm|
|minimatch|1.0.0|间接依赖|npm|
|camelcase-keys|2.1.0|间接依赖|npm|
|rsvp|4.8.5|间接依赖|npm|
|ember-array-contains-helper|1.0.2|直接依赖|npm|
|commons-beanutils:commons-beanutils|1.9.4|直接依赖|maven|
|readable-stream|1.1.14|间接依赖|npm|
|styled_string|0.0.1|间接依赖|npm|
|abbrev|1.1.1|间接依赖|npm|
|detective|4.7.1|间接依赖|npm|
|statuses|1.5.0|间接依赖|npm|
|org.eclipse.jetty.http2:http2-common|9.4.44.v20210927|间接依赖|maven|
|less|2.7.3|间接依赖|npm|
|ember-cli-get-dependency-depth|1.0.0|间接依赖|npm|
|com.squareup.okhttp3:okhttp|4.10.0|直接依赖|maven|
|ansi-regex|1.1.1|间接依赖|npm|
|org.yaml:snakeyaml|2.0|直接依赖|maven|
|ember-spin-spinner|0.2.3|直接依赖|npm|
|hosted-git-info|2.8.5|间接依赖|npm|
|resolve|1.14.1|间接依赖|npm|
|org.apache.hadoop:hadoop-annotations|3.4.0-SNAPSHOT|直接依赖|maven|
|select2|4.0.0|直接依赖|npm|
|npmlog|4.1.2|间接依赖|npm|
|com.microsoft.azure:azure-cosmosdb-direct|2.4.5|间接依赖|maven|
|serve-static|1.14.1|间接依赖|npm|
|simple-fmt|0.1.0|间接依赖|npm|
|glob|4.3.5|间接依赖|npm|
|write-file-atomic|1.3.4|间接依赖|npm|
|lodash.keysin|3.0.8|间接依赖|npm|
|mute-stream|0.0.4|间接依赖|npm|
|com.fasterxml.jackson.core:jackson-core|2.12.7|直接依赖|maven|
|body-parser|1.14.2|间接依赖|npm|
|minimist|1.2.5|间接依赖|npm|
|lodash._baseisequal|3.0.7|间接依赖|npm|
|get-stdin|4.0.1|间接依赖|npm|
|encodeurl|1.0.2|间接依赖|npm|
|normalize-package-data|2.5.0|间接依赖|npm|
|babel-plugin-jscript|1.0.4|间接依赖|npm|
|json-stringify-safe|5.0.1|间接依赖|npm|
|extend|3.0.2|间接依赖|npm|
|com.google.guava:failureaccess|1.0|间接依赖|maven|
|minimatch|0.2.14|间接依赖|npm|
|io.netty:netty-codec-stomp|4.1.94.Final|间接依赖|maven|
|lodash._baseassign|3.2.0|间接依赖|npm|
|arraybuffer.slice|0.0.6|间接依赖|npm|
|slash|1.0.0|间接依赖|npm|
|org.eclipse.jetty.websocket:javax-websocket-server-impl|9.4.51.v20230217|直接依赖|maven|
|tough-cookie|2.2.2|间接依赖|npm|
|semver|5.7.1|间接依赖|npm|
|loud-rejection|1.6.0|间接依赖|npm|
|meow|3.7.0|间接依赖|npm|
|chalk|0.5.1|间接依赖|npm|
|form-data|2.3.3|间接依赖|npm|
|string.prototype.endswith|0.2.0|间接依赖|npm|
|validate-npm-package-name|3.0.0|间接依赖|npm|
|fs-extra|0.30.0|间接依赖|npm|
|exec-sh|0.2.2|间接依赖|npm|
|mime-db|1.47.0|间接依赖|npm|
|org.sonatype.plexus:plexus-cipher|1.4|间接依赖|maven|
|image-size|0.5.5|直接依赖|npm|
|debug|0.7.4|间接依赖|npm|
|engine.io-parser|1.2.2|间接依赖|npm|
|bytes|2.2.0|间接依赖|npm|
|org.apache.maven:maven-artifact|3.0.5|间接依赖|maven|
|broccoli-plugin|1.1.0|间接依赖|npm|
|set-blocking|2.0.0|间接依赖|npm|
|mime-types|2.1.25|间接依赖|npm|
|makeerror|1.0.11|间接依赖|npm|
|charm|1.0.2|间接依赖|npm|
|javax.websocket:javax.websocket-api|1.0|间接依赖|maven|
|repeat-element|1.1.3|间接依赖|npm|
|rimraf|2.7.1|间接依赖|npm|
|fs-tree-diff|0.5.9|间接依赖|npm|
|org.sonatype.aether:aether-impl|1.13.1|间接依赖|maven|
|esutils|2.0.3|间接依赖|npm|
|io.opencensus:opencensus-api|0.24.0|间接依赖|maven|
|fstream|1.0.12|间接依赖|npm|
|is-typedarray|1.0.0|间接依赖|npm|
|org.apache.hadoop:hadoop-mapreduce-client-core|3.4.0-SNAPSHOT|直接依赖|maven|
|babel-plugin-remove-debugger|1.0.1|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.8.0|间接依赖|maven|
|org.apache.hadoop:hadoop-client-minicluster|3.4.0-SNAPSHOT|直接依赖|maven|
|bl|1.0.3|间接依赖|npm|
|parseurl|1.3.3|间接依赖|npm|
|debug|3.2.6|间接依赖|npm|
|request|2.81.0|直接依赖|npm|
|lodash.keys|3.1.2|间接依赖|npm|
|merge-descriptors|1.0.1|间接依赖|npm|
|lodash._bindcallback|3.0.1|间接依赖|npm|
|hoek|2.16.3|间接依赖|npm|
|ws-pure|0.8.0|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|has-ansi|2.0.0|间接依赖|npm|
|fs-extra|0.16.5|间接依赖|npm|
|username-sync|1.0.2|间接依赖|npm|
|ember-test-helpers|0.5.34|间接依赖|npm|
|org.apache.kerby:kerby-config|2.0.3|间接依赖|maven|
|io.grpc:grpc-core|1.26.0|直接依赖|maven|
|is-type|0.0.1|间接依赖|npm|
|ansicolors|0.2.1|间接依赖|npm|
|org.apache.hadoop:hadoop-auth|3.4.0-SNAPSHOT|直接依赖|maven|
|com.qcloud:cos_api-bundle|5.6.69|直接依赖|maven|
|fast-sourcemap-concat|0.2.7|间接依赖|npm|
|broccoli-config-loader|1.0.1|间接依赖|npm|
|core-util-is|1.0.2|间接依赖|npm|
|linkify-it|1.2.4|间接依赖|npm|
|org.eclipse.jetty:jetty-http|9.4.51.v20230217|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-router|3.4.0-SNAPSHOT|直接依赖|maven|
|is-core-module|2.4.0|间接依赖|npm|
|com.jamesmurty.utils:java-xmlbuilder|1.2|间接依赖|maven|
|lazy-cache|1.0.4|间接依赖|npm|
|asn1|0.2.4|间接依赖|npm|
|is-glob|2.0.1|间接依赖|npm|
|org.apache.hbase:hbase-annotations|1.7.1|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-services-api|3.4.0-SNAPSHOT|直接依赖|maven|
|clean-css|2.2.23|间接依赖|npm|
|path-root|0.1.1|间接依赖|npm|
|read|1.0.7|间接依赖|npm|
|after|0.8.1|间接依赖|npm|
|fs-extra|5.0.0|间接依赖|npm|
|oauth-sign|0.8.2|间接依赖|npm|
|ember-cli-node-assets|0.1.6|间接依赖|npm|
|is-property|1.0.2|间接依赖|npm|
|org.sonatype.sisu:sisu-guava|0.9.9|间接依赖|maven|
|uc.micro|1.0.6|间接依赖|npm|
|org.openlabtesting.leveldbjni:leveldbjni-all|1.8|直接依赖|maven|
|fstream-npm|1.0.7|间接依赖|npm|
|jsbn|0.1.1|间接依赖|npm|
|net.bytebuddy:byte-buddy-agent|1.9.10|间接依赖|maven|
|forever-agent|0.6.1|间接依赖|npm|
|io.dropwizard.metrics:metrics-core|3.2.4|直接依赖|maven|
|columnify|1.5.4|间接依赖|npm|
|org.glassfish.grizzly:grizzly-http-server|2.2.16|间接依赖|maven|
|tweetnacl|0.14.5|间接依赖|npm|
|websocket-driver|0.7.3|间接依赖|npm|
|npm-user-validate|0.1.5|间接依赖|npm|
|minimatch|2.0.10|间接依赖|npm|
|com.google.errorprone:error_prone_annotations|2.3.3|间接依赖|maven|
|babel-plugin-react-display-name|1.0.3|间接依赖|npm|
|lodash.pad|4.5.1|间接依赖|npm|
|org.eclipse.jetty:jetty-webapp|9.4.51.v20230217|直接依赖|maven|
|org.apache.hadoop:hadoop-archives|3.4.0-SNAPSHOT|直接依赖|maven|
|ember-cli-preprocess-registry|1.1.0|间接依赖|npm|
|es6-weak-map|0.1.4|间接依赖|npm|
|org.apache.kerby:kerb-admin|2.0.3|间接依赖|maven|
|org.apache.hadoop:hadoop-pipes|3.4.0-SNAPSHOT|直接依赖|maven|
|arr-flatten|1.1.0|间接依赖|npm|
|uglify-to-browserify|1.0.2|直接依赖|npm|
|extsprintf|1.4.0|间接依赖|npm|
|has-ansi|0.1.0|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|read-pkg-up|1.0.1|间接依赖|npm|
|domutils|1.5.1|间接依赖|npm|
|io.netty:netty-codec-xml|4.1.94.Final|间接依赖|maven|
|ember-cli-is-package-missing|1.0.0|间接依赖|npm|
|bower|1.8.8|直接依赖|npm|
|io.perfmark:perfmark-api|0.19.0|间接依赖|maven|
|redent|1.0.0|间接依赖|npm|
|backbone|1.4.0|间接依赖|npm|
|cli|1.0.1|间接依赖|npm|
|did_it_work|0.0.6|间接依赖|npm|
|alter|0.2.0|间接依赖|npm|
|ast-types|0.8.15|间接依赖|npm|
|es6-iterator|2.0.3|间接依赖|npm|
|performance-now|0.2.0|间接依赖|npm|
|io.netty:netty-codec|4.1.94.Final|间接依赖|maven|
|bytes|3.1.0|间接依赖|npm|
|negotiator|0.6.2|间接依赖|npm|
|ultron|1.0.2|间接依赖|npm|
|tap-parser|1.3.2|间接依赖|npm|
|xtend|4.0.2|间接依赖|npm|
|extsprintf|1.3.0|间接依赖|npm|
|io.netty:netty-codec-http2|4.1.94.Final|间接依赖|maven|
|delegates|1.0.0|间接依赖|npm|
|io.netty:netty-transport-native-unix-common|4.1.94.Final|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|直接依赖|maven|
|lodash._createcache|3.1.2|间接依赖|npm|
|safe-buffer|5.2.1|间接依赖|npm|
|org.apache.kerby:kerb-common|2.0.3|间接依赖|maven|
|npm|2.14.10|间接依赖|npm|
|longest|1.0.1|间接依赖|npm|
|debug|1.0.2|间接依赖|npm|
|com.sun.jersey:jersey-grizzly2-servlet|1.19.4|间接依赖|maven|
|io.netty:netty-codec-smtp|4.1.94.Final|间接依赖|maven|
|org.apache.hbase:hbase-client|1.7.1|直接依赖|maven|
|babel-plugin-inline-environment-variables|1.0.1|间接依赖|npm|
|org.apache.hadoop.thirdparty:hadoop-shaded-guava|1.1.1|直接依赖|maven|
|ember-cli-normalize-entity-name|1.0.0|间接依赖|npm|
|is-builtin-module|1.0.0|间接依赖|npm|
|tough-cookie|2.3.4|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|org.apache.commons:commons-lang3|3.12.0|直接依赖|maven|
|uuid|2.0.3|间接依赖|npm|
|org.jetbrains.kotlin:kotlin-stdlib|1.6.20|直接依赖|maven|
|punycode|1.4.1|间接依赖|npm|
|broccoli-caching-writer|2.3.1|间接依赖|npm|
|make-array|0.1.2|间接依赖|npm|
|inherits|2.0.3|间接依赖|npm|
|debug|2.6.9|间接依赖|npm|
|mkdirp|0.3.5|间接依赖|npm|
|cardinal|0.5.0|间接依赖|npm|
|org.eclipse.jetty.websocket:websocket-api|9.4.51.v20230217|间接依赖|maven|
|uuid|3.3.3|间接依赖|npm|
|send|0.17.1|间接依赖|npm|
|lodash._getnative|3.9.1|间接依赖|npm|
|org.apache.hadoop:hadoop-common|3.4.0-SNAPSHOT|直接依赖|maven|
|quick-temp|0.1.3|间接依赖|npm|
|semver|5.3.0|间接依赖|npm|
|portfinder|0.4.0|间接依赖|npm|
|babylon|5.8.38|间接依赖|npm|
|org.apache.hadoop:hadoop-yarn-applications-catalog-webapp|3.4.0-SNAPSHOT|直接依赖|maven|
|org.apache.zookeeper:zookeeper|3.6.3|直接依赖|maven|
|org.eclipse.jetty:jetty-client|9.4.51.v20230217|间接依赖|maven|
|broccoli-jshint|1.2.0|间接依赖|npm|
|watch|0.10.0|间接依赖|npm|
|org.apache.httpcomponents:httpmime|4.5.13|间接依赖|maven|
|org.apache.hadoop:hadoop-aws|3.4.0-SNAPSHOT|直接依赖|maven|
|trim-right|1.0.1|间接依赖|npm|
|yargs|3.27.0|间接依赖|npm|
|ember-cli-babel|5.2.8|间接依赖|npm|
|node-modules-path|1.0.2|间接依赖|npm|
|lodash.uniq|3.2.2|间接依赖|npm|
|org.apache.hadoop:hadoop-yarn-server-timelineservice-hbase-common|3.4.0-SNAPSHOT|直接依赖|maven|
|underscore.string|2.3.3|间接依赖|npm|
|commons-logging:commons-logging|1.1.3|直接依赖|maven|
|strip-json-comments|1.0.4|间接依赖|npm|
|broccoli-sourcemap-concat|1.1.6|间接依赖|npm|
|ember-cli-string-utils|1.1.0|间接依赖|npm|
|ember-cli-sri|1.2.1|直接依赖|npm|
|io.opentracing:opentracing-api|0.33.0|间接依赖|maven|
|org.apache.hadoop:hadoop-registry|3.4.0-SNAPSHOT|直接依赖|maven|
|readdir-scoped-modules|1.1.0|间接依赖|npm|
|io.netty:netty-resolver-dns-classes-macos|4.1.94.Final|间接依赖|maven|
|ember-cli-content-security-policy|0.4.0|直接依赖|npm|
|find-up|3.0.0|间接依赖|npm|
|builtin-modules|1.1.1|间接依赖|npm|
|options|0.0.6|间接依赖|npm|
|ember-cli-jquery-ui|0.0.20|直接依赖|npm|
|commons-collections:commons-collections|3.2.2|直接依赖|maven|
|date-now|0.1.4|间接依赖|npm|
|ember-resolver|2.0.3|直接依赖|npm|
|can-symlink|1.0.0|间接依赖|npm|
|compression|1.7.4|间接依赖|npm|
|org.apache.hadoop:hadoop-streaming|3.4.0-SNAPSHOT|直接依赖|maven|
|faye-websocket|0.10.0|间接依赖|npm|
|async-disk-cache|1.3.5|间接依赖|npm|
|clone|1.0.4|间接依赖|npm|
|org.apache.kerby:token-provider|2.0.3|间接依赖|maven|
|vary|1.1.2|间接依赖|npm|
|com.aliyun:aliyun-java-sdk-kms|2.11.0|间接依赖|maven|
|har-validator|2.0.6|间接依赖|npm|
|ext|1.4.0|间接依赖|npm|
|com.microsoft.sqlserver:mssql-jdbc|6.2.1.jre7|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-nodemanager|3.4.0-SNAPSHOT|直接依赖|maven|
|dezalgo|1.0.3|间接依赖|npm|
|org.jdom:jdom2|2.0.6.1|间接依赖|maven|
|string-width|3.1.0|间接依赖|npm|
|org.apache.hadoop:hadoop-huaweicloud|3.4.0-SNAPSHOT|直接依赖|maven|
|strip-ansi|3.0.1|间接依赖|npm|
|broccoli-funnel|1.2.0|间接依赖|npm|
|ember-truth-helpers|1.3.0|直接依赖|npm|
|com.cenqua.clover:clover|3.0.2|直接依赖|maven|
|io.grpc:grpc-netty|1.26.0|直接依赖|maven|
|esprima|2.7.3|间接依赖|npm|
|qs|5.2.0|间接依赖|npm|
|simple-is|0.2.0|间接依赖|npm|
|org.apache.hadoop:hadoop-azure|3.4.0-SNAPSHOT|直接依赖|maven|
|socket.io-parser|2.2.4|间接依赖|npm|
|glob|7.1.7|间接依赖|npm|
|io.swagger:swagger-annotations|1.5.4|直接依赖|maven|
|lodash.padend|4.6.1|间接依赖|npm|
|strip-bom|2.0.0|间接依赖|npm|
|org.apache.hadoop:hadoop-azure-datalake|3.4.0-SNAPSHOT|直接依赖|maven|
|forwarded|0.1.2|间接依赖|npm|
|org.jruby.joni:joni|2.1.2|间接依赖|maven|
|is-buffer|1.1.6|间接依赖|npm|
|broccoli-merge-trees|1.1.1|直接依赖|npm|
|request|2.65.0|间接依赖|npm|
|javax.annotation:javax.annotation-api|1.3.2|直接依赖|maven|
|in-publish|2.0.1|间接依赖|npm|
|org.apache.hadoop:hadoop-yarn-server-globalpolicygenerator|3.4.0-SNAPSHOT|直接依赖|maven|
|org.apache.hadoop:hadoop-dynamometer-infra|3.4.0-SNAPSHOT|直接依赖|maven|
|glob|6.0.4|间接依赖|npm|
|event-emitter|0.3.5|间接依赖|npm|
|builtins|1.0.3|间接依赖|npm|
|lodash.toplainobject|3.0.0|间接依赖|npm|
|ember-cli-moment-shim|0.7.3|直接依赖|npm|
|user-home|1.1.1|间接依赖|npm|
|ini|1.3.5|间接依赖|npm|
|component-inherit|0.0.3|间接依赖|npm|
|spdx|0.4.3|间接依赖|npm|
|jsonfile|2.4.0|间接依赖|npm|
|fs-readdir-recursive|0.1.2|间接依赖|npm|
|parse-glob|3.0.4|间接依赖|npm|
|cli-table|0.3.1|间接依赖|npm|
|home-or-tmp|1.0.0|间接依赖|npm|
|colors|1.0.3|间接依赖|npm|
|github-url-from-username-repo|1.0.2|间接依赖|npm|
|chmodr|1.0.2|间接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|org.eclipse.jetty:jetty-annotations|9.4.51.v20230217|间接依赖|maven|
|jsonify|0.0.0|间接依赖|npm|
|babel-plugin-constant-folding|1.0.1|间接依赖|npm|
|lodash._isiterateecall|3.0.9|间接依赖|npm|
|ember-cli-path-utils|1.0.0|间接依赖|npm|
|ember-cli-ic-ajax|0.2.1|直接依赖|npm|
|org.apache.kerby:kerb-server|2.0.3|间接依赖|maven|
|commons-codec:commons-codec|1.15|直接依赖|maven|
|cryptiles|2.0.5|间接依赖|npm|
|org.slf4j:slf4j-log4j12|1.7.30|直接依赖|maven|
|websocket-extensions|0.1.3|间接依赖|npm|
|shebang-regex|1.0.0|间接依赖|npm|
|anymatch|1.3.2|间接依赖|npm|
|lodash.isplainobject|3.2.0|间接依赖|npm|
|textextensions|2.6.0|间接依赖|npm|
|generate-function|2.3.1|间接依赖|npm|
|com.google.android:annotations|4.1.1.4|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.13|直接依赖|maven|
|numeral|1.5.6|间接依赖|npm|
|bcrypt-pbkdf|1.0.2|间接依赖|npm|
|org.codehaus.mojo:animal-sniffer-annotations|1.17|间接依赖|maven|
|preserve|0.2.0|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|lodash._basecopy|3.0.1|间接依赖|npm|
|org.apache.hadoop:hadoop-extras|3.4.0-SNAPSHOT|直接依赖|maven|
|gaze|1.1.3|间接依赖|npm|
|org.apache.kerby:kerb-crypto|2.0.3|间接依赖|maven|
|asn1|0.1.11|间接依赖|npm|
|path-posix|1.0.0|间接依赖|npm|
|ansi-styles|2.2.1|间接依赖|npm|
|async|0.8.0|间接依赖|npm|
|setprototypeof|1.1.1|间接依赖|npm|
|d|1.0.1|间接依赖|npm|
|type-is|1.6.18|间接依赖|npm|
|jsonfile|4.0.0|间接依赖|npm|
|fs-vacuum|1.2.10|间接依赖|npm|
|io.reactivex:rxjava-string|1.1.1|间接依赖|maven|
|io.netty:netty-codec-redis|4.1.94.Final|间接依赖|maven|
|has-unicode|2.0.1|间接依赖|npm|
|commons-daemon:commons-daemon|1.0.13|直接依赖|maven|
|qs|6.7.0|间接依赖|npm|
|com.fasterxml.woodstox:woodstox-core|5.4.0|直接依赖|maven|
|hosted-git-info|2.8.9|间接依赖|npm|
|find-up|1.1.2|间接依赖|npm|
|net.java.dev.jna:jna|5.2.0|直接依赖|maven|
|io.netty:netty-transport-rxtx|4.1.94.Final|间接依赖|maven|
|js-yaml|3.13.1|间接依赖|npm|
|safe-buffer|5.2.0|间接依赖|npm|
|org.apache.hadoop:hadoop-yarn-client|3.4.0-SNAPSHOT|直接依赖|maven|
|org.apache.commons:commons-collections4|4.2|间接依赖|maven|
|uuid|3.4.0|间接依赖|npm|
|right-align|0.1.3|间接依赖|npm|
|object-assign|2.1.1|间接依赖|npm|
|findup-sync|0.2.1|间接依赖|npm|
|npm-install-checks|1.0.7|间接依赖|npm|
|is-my-ip-valid|1.0.0|间接依赖|npm|
|sntp|1.0.9|间接依赖|npm|
|org.eclipse.jetty:jetty-alpn-java-client|9.4.44.v20210927|间接依赖|maven|
|mktemp|0.3.5|间接依赖|npm|
|raw-body|2.4.0|间接依赖|npm|
|org.apache.hadoop:hadoop-mapreduce-client-common|3.4.0-SNAPSHOT|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.30|直接依赖|maven|
|supports-color|2.0.0|间接依赖|npm|
|proxy-addr|2.0.5|间接依赖|npm|
|broccoli-viz|2.0.1|间接依赖|npm|
|babel-plugin-htmlbars-inline-precompile|0.0.5|间接依赖|npm|
|http-signature|0.11.0|间接依赖|npm|
|em-helpers|0.8.0|直接依赖|npm|
|ee-first|1.1.1|间接依赖|npm|
|walker|1.0.7|间接依赖|npm|
|io.netty:netty-codec-socks|4.1.94.Final|间接依赖|maven|
|etag|1.8.1|间接依赖|npm|
|json3|3.2.6|间接依赖|npm|
|io.netty:netty-transport-sctp|4.1.94.Final|间接依赖|maven|
|regex-cache|0.4.4|间接依赖|npm|
|org.apache.maven:maven-repository-metadata|3.0.5|间接依赖|maven|
|clone|2.1.2|间接依赖|npm|
|chownr|1.1.3|间接依赖|npm|
|babel-plugin-dead-code-elimination|1.0.2|间接依赖|npm|
|org.apache.hadoop:hadoop-client-runtime|3.4.0-SNAPSHOT|直接依赖|maven|
|ember-cli-test-info|1.0.0|间接依赖|npm|
|dom-serializer|0.2.2|间接依赖|npm|
|json-parse-better-errors|1.0.2|间接依赖|npm|
|com.microsoft.azure:azure-storage|7.0.1|直接依赖|maven|
|socket.io-pure|1.3.12|间接依赖|npm|
|cross-spawn|3.0.1|间接依赖|npm|
|yallist|2.1.2|间接依赖|npm|
|parseuri|0.0.4|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|qs|6.4.0|间接依赖|npm|
|javax.servlet:javax.servlet-api|3.1.0|直接依赖|maven|
|org.apache.hadoop:hadoop-mapreduce-examples|3.4.0-SNAPSHOT|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.12.7.1|直接依赖|maven|
|org.eclipse.jetty.websocket:websocket-server|9.4.51.v20230217|间接依赖|maven|
|boom|2.10.1|间接依赖|npm|
|lodash.merge|4.6.2|间接依赖|npm|
|git-repo-info|1.4.1|间接依赖|npm|
|com.github.stephenc.findbugs:findbugs-annotations|1.3.9-1|间接依赖|maven|
|tmp|0.0.28|间接依赖|npm|
|caseless|0.12.0|间接依赖|npm|
|wordwrap|0.0.2|间接依赖|npm|
|try-resolve|1.0.1|间接依赖|npm|
|has-color|0.1.7|间接依赖|npm|
|mktemp|0.4.0|间接依赖|npm|
|string-width|1.0.2|间接依赖|npm|
|babel-core|5.8.38|间接依赖|npm|
|broccoli-kitchen-sink-helpers|0.2.9|间接依赖|npm|
|aws4|1.9.0|间接依赖|npm|
|connect|3.7.0|间接依赖|npm|
|argparse|1.0.10|间接依赖|npm|
|lodash|2.3.0|间接依赖|npm|
|commons-lang:commons-lang|2.6|间接依赖|maven|
|source-map|0.4.4|间接依赖|npm|
|bower-endpoint-parser|0.2.2|间接依赖|npm|
|org.eclipse.jetty.http2:http2-client|9.4.44.v20210927|间接依赖|maven|
|io.grpc:grpc-api|1.26.0|间接依赖|maven|
|merge-trees|1.0.1|间接依赖|npm|
|junit:junit|4.13.2|直接依赖|maven|
|mustache|2.3.2|间接依赖|npm|
|ember-d3|0.1.0|直接依赖|npm|
|body-parser|1.19.0|间接依赖|npm|
|indexof|0.0.1|间接依赖|npm|
|markdown-it|4.3.0|间接依赖|npm|
|mime-types|2.1.30|间接依赖|npm|
|through|2.3.8|间接依赖|npm|
|breakable|1.0.0|间接依赖|npm|
|text-table|0.2.0|间接依赖|npm|
|org.wildfly.openssl:wildfly-openssl|1.1.3.Final|直接依赖|maven|
|org.apache.hadoop.thirdparty:hadoop-shaded-protobuf_3_7|1.1.1|直接依赖|maven|
|unpipe|1.0.0|间接依赖|npm|
|http-parser-js|0.4.10|间接依赖|npm|
|aws4|1.11.0|间接依赖|npm|
|destroy|1.0.4|间接依赖|npm|
|esprima-fb|12001.1.0-dev-harmony-fb|间接依赖|npm|
|lodash._baseuniq|3.0.3|间接依赖|npm|
|amdefine|1.0.1|间接依赖|npm|
|com.google.guava:guava|12.0.1|直接依赖|maven|
|json5|0.4.0|间接依赖|npm|
|blank-object|1.0.2|间接依赖|npm|
|com.microsoft.azure:azure-cosmosdb|2.4.5|直接依赖|maven|
|npmlog|2.0.4|间接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|com.github.stephenc.jcip:jcip-annotations|1.0-1|间接依赖|maven|
|htmlparser2|3.8.3|间接依赖|npm|
|mime|1.6.0|间接依赖|npm|
|sigmund|1.0.1|间接依赖|npm|
|configstore|1.2.1|间接依赖|npm|
|clone|0.2.0|间接依赖|npm|
|leven|1.0.2|间接依赖|npm|
|json-stable-stringify|1.0.1|间接依赖|npm|
|io.grpc:grpc-stub|1.26.0|直接依赖|maven|
|concat-stream|1.6.2|间接依赖|npm|
|braces|1.8.5|间接依赖|npm|
|entities|1.0.0|间接依赖|npm|
|ember-cli-qunit|1.2.1|直接依赖|npm|
|follow-redirects|1.14.7|间接依赖|npm|
|broccoli-source|1.1.0|间接依赖|npm|
|y18n|4.0.3|间接依赖|npm|
|esprima|3.1.3|间接依赖|npm|
|array-unique|0.2.1|间接依赖|npm|
|org.sonatype.sisu:sisu-guice|3.1.0|间接依赖|maven|
|ansi-styles|1.0.0|间接依赖|npm|
|private|0.1.8|间接依赖|npm|
|com.github.davidmoten:rxjava-extras|0.8.0.17|间接依赖|maven|
|next-tick|1.0.0|间接依赖|npm|
|co|4.6.0|间接依赖|npm|
|io.netty:netty-resolver-dns-native-macos|4.1.94.Final|间接依赖|maven|
|commons-net:commons-net|3.9.0|直接依赖|maven|
|ms|2.1.2|间接依赖|npm|
|broccoli-funnel|2.0.2|间接依赖|npm|
|temp|0.8.1|间接依赖|npm|
|org.apache.maven:maven-aether-provider|3.0.5|间接依赖|maven|
|org.apache.hadoop:hadoop-distcp|3.4.0-SNAPSHOT|直接依赖|maven|
|readable-stream|2.3.7|间接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|com.fasterxml.jackson.core:jackson-annotations|2.12.7|直接依赖|maven|
|aws-sign2|0.6.0|间接依赖|npm|
|org.apache.hadoop:hadoop-yarn-server-timelineservice|3.4.0-SNAPSHOT|直接依赖|maven|
|es6-promise|4.0.5|间接依赖|npm|
|http-errors|1.7.3|间接依赖|npm|
|org.apache.commons:commons-configuration2|2.8.0|直接依赖|maven|
|broccoli-writer|0.1.1|间接依赖|npm|
|ensure-posix-path|1.1.1|间接依赖|npm|
|http-errors|1.3.1|间接依赖|npm|
|rsvp|3.2.1|间接依赖|npm|
|commons-io:commons-io|2.11.0|直接依赖|maven|
|broccoli-funnel|1.0.1|直接依赖|npm|
|ast-types|0.8.12|间接依赖|npm|
|lodash.istypedarray|3.0.6|间接依赖|npm|
|next-tick|0.2.2|间接依赖|npm|
|engine.io-client-pure|1.5.9|间接依赖|npm|
|broccoli-caching-writer|3.0.3|间接依赖|npm|
|ansi-regex|0.2.1|间接依赖|npm|
|babel-plugin-proto-to-assign|1.0.4|间接依赖|npm|
|ember-cli-sass|7.0.0|直接依赖|npm|
|read-package-json|2.1.1|间接依赖|npm|
|com.microsoft.azure:azure-keyvault-core|1.0.0|间接依赖|maven|
|lockfile|1.0.4|间接依赖|npm|
|jsprim|1.4.1|间接依赖|npm|
|commoner|0.10.8|间接依赖|npm|
|http-signature|1.2.0|间接依赖|npm|
|path-exists|1.0.0|间接依赖|npm|
|ember-cli-htmlbars|1.3.5|间接依赖|npm|
|fs-extra|0.22.1|间接依赖|npm|
|io.netty:netty-codec-mqtt|4.1.94.Final|间接依赖|maven|
|exists-sync|0.0.3|间接依赖|npm|
|redeyed|0.5.0|间接依赖|npm|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.12.7|直接依赖|maven|
|har-schema|1.0.5|间接依赖|npm|
|sass-graph|2.2.5|间接依赖|npm|
|tmpl|1.0.4|间接依赖|npm|
|org.apache.hadoop:hadoop-dynamometer-workload|3.4.0-SNAPSHOT|直接依赖|maven|
|org.ini4j:ini4j|0.5.4|间接依赖|maven|
|tough-cookie|2.5.0|间接依赖|npm|
|object.omit|2.0.1|间接依赖|npm|
|lodash|2.4.2|间接依赖|npm|
|ember-export-application-global|1.0.5|直接依赖|npm|
|ember-cli|1.13.14|直接依赖|npm|
|process-nextick-args|1.0.7|间接依赖|npm|
|array-index|1.0.0|间接依赖|npm|
|babel-plugin-undefined-to-void|1.1.6|间接依赖|npm|
|which|1.3.1|间接依赖|npm|
|javax.servlet.jsp:jsp-api|2.1|直接依赖|maven|
|debug|1.0.3|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|caseless|0.11.0|间接依赖|npm|
|underscore.string|3.3.5|间接依赖|npm|
|validate-npm-package-name|2.2.2|间接依赖|npm|
|org.apache.hadoop:hadoop-mapreduce-client-app|3.4.0-SNAPSHOT|直接依赖|maven|
|tar|1.0.3|间接依赖|npm|
|recast|0.10.33|间接依赖|npm|
|com.cedarsoftware:json-io|2.5.1|间接依赖|maven|
|debuglog|1.0.1|间接依赖|npm|
|mout|0.9.1|间接依赖|npm|
|loader.js|4.2.3|直接依赖|npm|
|org.glassfish.grizzly:grizzly-framework|2.2.16|间接依赖|maven|
|regjsparser|0.1.5|间接依赖|npm|
|com.nimbusds:nimbus-jose-jwt|9.31|直接依赖|maven|
|proto-list|1.2.4|间接依赖|npm|
|assert-plus|0.1.5|间接依赖|npm|
|com.microsoft.azure:azure-cosmosdb-commons|2.4.5|间接依赖|maven|
|morgan|1.9.1|间接依赖|npm|
|ember-cli-dependency-checker|1.2.0|直接依赖|npm|
|org.apache.zookeeper:zookeeper-jute|3.6.2|间接依赖|maven|
|net.sf.kosmosfs:kfs|0.3|直接依赖|maven|
|tiny-lr|0.2.0|间接依赖|npm|
|strip-ansi|0.1.1|间接依赖|npm|
|async-foreach|0.1.3|间接依赖|npm|
|to-fast-properties|1.0.3|间接依赖|npm|
|async|0.9.0|间接依赖|npm|
|raw-body|2.1.7|间接依赖|npm|
|org.apache.maven:maven-plugin-api|3.0.5|直接依赖|maven|
|babel-plugin-runtime|1.0.7|间接依赖|npm|
|findup-sync|0.3.0|间接依赖|npm|
|org.jacoco:org.jacoco.agent|0.8.5|间接依赖|maven|
|esprima|4.0.1|间接依赖|npm|
|io.netty:netty-resolver|4.1.94.Final|间接依赖|maven|
|sorted-object|1.0.0|间接依赖|npm|
|throttleit|1.0.0|间接依赖|npm|
|is-stream|1.1.0|间接依赖|npm|
|org.apache.kafka:kafka-clients|2.8.2|直接依赖|maven|
|io.netty:netty-codec-dns|4.1.94.Final|间接依赖|maven|
|is-git-url|0.2.0|间接依赖|npm|
|os-tmpdir|1.0.2|间接依赖|npm|
|ember-cli-htmlbars|0.7.6|间接依赖|npm|
|toidentifier|1.0.0|间接依赖|npm|
|to-array|0.1.3|间接依赖|npm|
|ansicolors|0.3.2|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|isstream|0.1.2|间接依赖|npm|
|camelcase|1.2.1|间接依赖|npm|
|mute-stream|0.0.8|间接依赖|npm|
|ember-qunit|0.4.24|间接依赖|npm|
|org.mockito:mockito-core|2.28.2|直接依赖|maven|
|es6-symbol|2.0.1|间接依赖|npm|
|com.sun.jersey:jersey-client|1.19.4|直接依赖|maven|
|spdx-license-ids|1.2.2|间接依赖|npm|
|broccoli-merge-trees|2.0.1|间接依赖|npm|
|dnsjava:dnsjava|3.4.0|直接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.30|直接依赖|maven|
|qs|6.5.2|间接依赖|npm|
|org.sonatype.aether:aether-api|1.13.1|间接依赖|maven|
|concat-stream|1.5.0|间接依赖|npm|
|com.googlecode.json-simple:json-simple|1.1.1|直接依赖|maven|
|commander|2.1.0|间接依赖|npm|
|path-array|1.0.1|间接依赖|npm|
|npm-package-arg|4.2.1|间接依赖|npm|
|qs|5.1.0|间接依赖|npm|
|fast-ordered-set|1.0.3|间接依赖|npm|
|com.huaweicloud:esdk-obs-java|3.20.4.2|直接依赖|maven|
|broccoli-uglify-sourcemap|1.5.2|间接依赖|npm|
|org.eclipse.jetty.websocket:websocket-common|9.4.51.v20230217|间接依赖|maven|
|com.google.api.grpc:proto-google-common-protos|1.12.0|间接依赖|maven|
|aws-sign2|0.7.0|间接依赖|npm|
|request|2.88.2|间接依赖|npm|
|bser|2.1.1|间接依赖|npm|
|asynckit|0.4.0|间接依赖|npm|
|com.google.j2objc:j2objc-annotations|1.1|间接依赖|maven|
|path-to-regexp|0.1.7|间接依赖|npm|
|livereload-js|2.4.0|间接依赖|npm|
|io.opentracing:opentracing-noop|0.33.0|间接依赖|maven|
|org.codehaus.plexus:plexus-component-annotations|1.5.5|间接依赖|maven|
|markdown-it|4.4.0|间接依赖|npm|
|org.apache.hadoop:hadoop-hdfs-client|3.4.0-SNAPSHOT|直接依赖|maven|
|babel-plugin-undeclared-variables-check|1.0.2|间接依赖|npm|
|har-validator|5.1.5|间接依赖|npm|
|broccoli-sass-source-maps|2.2.0|间接依赖|npm|
|parseuri|0.0.2|间接依赖|npm|
|commons-digester:commons-digester|1.8.1|间接依赖|maven|
|org.apache.yetus:audience-annotations|0.5.0|间接依赖|maven|
|org.eclipse.jetty:jetty-plus|9.4.51.v20230217|间接依赖|maven|
|lodash._basefor|3.0.3|间接依赖|npm|
|org.apache.geronimo.specs:geronimo-jcache_1.0_spec|1.0-alpha-1|直接依赖|maven|
|block-stream|0.0.9|间接依赖|npm|
|underscore|1.13.1|间接依赖|npm|
|lodash.isarguments|3.1.0|间接依赖|npm|
|com.github.luben:zstd-jni|1.4.9-1|间接依赖|maven|
|bower-shrinkwrap-resolver-ext|0.1.0|直接依赖|npm|
|org.apache.hadoop:hadoop-cos|3.4.0-SNAPSHOT|直接依赖|maven|
|escape-string-regexp|1.0.5|间接依赖|npm|
|ember-cli-copy-dereference|1.0.0|间接依赖|npm|
|org.eclipse.jetty:jetty-util|9.4.51.v20230217|直接依赖|maven|
|async|0.2.10|间接依赖|npm|
|pend|1.2.0|间接依赖|npm|
|jshint|2.10.3|间接依赖|npm|
|cross-spawn-async|2.2.5|间接依赖|npm|
|broccoli-config-replace|1.1.2|间接依赖|npm|
|org.sonatype.sisu:sisu-inject-bean|2.3.0|间接依赖|maven|
|istextorbinary|2.1.0|间接依赖|npm|
|core-object|0.0.2|间接依赖|npm|
|assert-plus|1.0.0|间接依赖|npm|
|promise|7.3.1|直接依赖|npm|
|io.netty:netty-buffer|4.1.94.Final|间接依赖|maven|
|glob|5.0.13|间接依赖|npm|
|org.apache.hadoop:hadoop-kafka|3.4.0-SNAPSHOT|直接依赖|maven|
|javax.ws.rs:jsr311-api|1.1.1|直接依赖|maven|
|stringset|0.2.1|间接依赖|npm|
|ipaddr.js|1.9.0|间接依赖|npm|
|glob-base|0.3.0|间接依赖|npm|
|io.reactivex:rxjava|1.3.8|直接依赖|maven|
|moment-timezone|0.3.1|间接依赖|npm|
|com.sun.jersey:jersey-core|1.19.4|直接依赖|maven|
|io.netty:netty-handler-proxy|4.1.94.Final|间接依赖|maven|
|lodash.merge|3.3.2|间接依赖|npm|
|semver|5.0.3|间接依赖|npm|
|heimdalljs|0.2.6|间接依赖|npm|
|os-homedir|1.0.2|间接依赖|npm|
|har-schema|2.0.0|间接依赖|npm|
|npm-registry-client|7.0.9|间接依赖|npm|
|socket.io-client-pure|1.3.12|间接依赖|npm|
|yam|0.0.18|间接依赖|npm|
|accepts|1.3.7|间接依赖|npm|
|broccoli-clean-css|0.2.0|间接依赖|npm|
|broccoli-unwatched-tree|0.1.3|间接依赖|npm|
|is-equal-shallow|0.1.3|间接依赖|npm|
|ic-ajax|2.0.2|间接依赖|npm|
|fb-watchman|2.0.1|间接依赖|npm|
|org.apache.hadoop:hadoop-sls|3.4.0-SNAPSHOT|直接依赖|maven|
|ember-cli-release|0.2.8|直接依赖|npm|
|repeating|1.1.3|间接依赖|npm|
|node-int64|0.4.0|间接依赖|npm|
|parseqs|0.0.2|间接依赖|npm|
|errno|0.1.7|直接依赖|npm|
|org.apache.kerby:kerby-asn1|2.0.3|间接依赖|maven|
|include-path-searcher|0.1.0|间接依赖|npm|
|ember-router-generator|1.2.3|间接依赖|npm|
|path-parse|1.0.6|间接依赖|npm|
|are-we-there-yet|1.1.5|间接依赖|npm|
|io.netty:netty-transport|4.1.94.Final|间接依赖|maven|
|mdurl|1.0.1|间接依赖|npm|
|which|1.2.14|间接依赖|npm|
|ajv|4.11.8|间接依赖|npm|
|org.apache.hadoop:hadoop-yarn-server-timeline-pluginstorage|3.4.0-SNAPSHOT|直接依赖|maven|
|util-extend|1.0.3|间接依赖|npm|
|ember-cli-app-version|1.0.0|直接依赖|npm|
|fs-write-stream-atomic|1.0.10|间接依赖|npm|
|component-bind|1.0.0|间接依赖|npm|
|javax.xml.bind:jaxb-api|2.2.11|直接依赖|maven|
|ajv|6.12.6|间接依赖|npm|
|net.bytebuddy:byte-buddy|1.9.10|间接依赖|maven|
|ctype|0.5.3|间接依赖|npm|
|sane|1.7.0|间接依赖|npm|
|org.eclipse.jetty:jetty-jndi|9.4.51.v20230217|间接依赖|maven|
|performance-now|2.1.0|间接依赖|npm|
|once|1.3.3|间接依赖|npm|
|minimatch|3.0.4|间接依赖|npm|
|ms|0.7.1|间接依赖|npm|
|org.codehaus.plexus:plexus-utils|3.1.0|间接依赖|maven|
|symlink-or-copy|1.3.1|间接依赖|npm|
|broccoli|0.16.8|间接依赖|npm|
|org.sonatype.aether:aether-util|1.13.1|间接依赖|maven|
|org.codehaus.jettison:jettison|1.5.4|直接依赖|maven|
|ember-bootstrap|0.5.1|直接依赖|npm|
|lodash._baseindexof|3.1.0|间接依赖|npm|
|map-obj|1.0.1|间接依赖|npm|
|org.apache.hbase:hbase-protocol|1.7.1|间接依赖|maven|
|jsesc|0.5.0|间接依赖|npm|
|globule|1.3.2|间接依赖|npm|
|socket.io-parser|2.2.2|间接依赖|npm|
|org.apache.hadoop:hadoop-mapreduce-client-shuffle|3.4.0-SNAPSHOT|直接依赖|maven|
|is-integer|1.0.7|间接依赖|npm|
|org.apache.curator:curator-framework|5.2.0|直接依赖|maven|
|broccoli-sourcemap-concat|2.0.2|间接依赖|npm|
|org.apache.hadoop:hadoop-mapreduce-client-hs|3.4.0-SNAPSHOT|直接依赖|maven|
|com.sun.jersey:jersey-grizzly2|1.19.4|间接依赖|maven|
|com.microsoft.azure:azure-data-lake-store-sdk|2.3.9|直接依赖|maven|
|async-promise-queue|1.0.5|间接依赖|npm|
|kind-of|3.2.2|间接依赖|npm|
|nan|2.14.2|间接依赖|npm|
|globals|6.4.1|间接依赖|npm|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.6.20|直接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|sprintf-js|1.0.3|间接依赖|npm|
|form-data|1.0.1|间接依赖|npm|
|decamelize|1.2.0|间接依赖|npm|
|merge-defaults|0.2.2|间接依赖|npm|
|gauge|1.2.7|间接依赖|npm|
|editor|1.0.0|间接依赖|npm|
|debug|2.2.0|间接依赖|npm|
|io.netty:netty-handler-ssl-ocsp|4.1.94.Final|间接依赖|maven|
|ast-traverse|0.1.1|间接依赖|npm|
|org.jsonschema2pojo:jsonschema2pojo-core|1.0.2|直接依赖|maven|
|lodash._createassigner|3.1.1|间接依赖|npm|
|is-dotfile|1.0.3|间接依赖|npm|
|broccoli-stew|1.6.0|间接依赖|npm|
|jsonpointer|4.0.1|间接依赖|npm|
|sshpk|1.16.1|间接依赖|npm|
|readable-stream|2.0.6|间接依赖|npm|
|org.apache.maven:maven-settings-builder|3.0.5|间接依赖|maven|
|read-pkg|1.1.0|间接依赖|npm|
|spdx-exceptions|2.3.0|间接依赖|npm|
|io.netty:netty-transport-classes-epoll|4.1.94.Final|间接依赖|maven|
|chalk|1.1.3|间接依赖|npm|
|org.apache.hadoop:hadoop-yarn-api|3.4.0-SNAPSHOT|直接依赖|maven|
|core-js|1.2.7|间接依赖|npm|
|org.apache.zookeeper:zookeeper-jute|3.6.3|间接依赖|maven|
|methods|1.1.2|间接依赖|npm|
|base64-arraybuffer|0.1.2|间接依赖|npm|
|lodash._basecallback|3.3.1|间接依赖|npm|
|fireworm|0.6.6|间接依赖|npm|
|source-map|0.5.7|直接依赖|npm|
|ember-cli-htmlbars-inline-precompile|0.3.1|直接依赖|npm|
|base64id|0.1.0|间接依赖|npm|
|pleasant-progress|1.1.0|间接依赖|npm|
|org.eclipse.jetty:jetty-util-ajax|9.4.51.v20230217|直接依赖|maven|
|strip-ansi|2.0.1|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|optimist|0.6.1|间接依赖|npm|
|org.apache.kerby:kerb-simplekdc|2.0.3|直接依赖|maven|
|align-text|0.1.4|间接依赖|npm|
|domelementtype|1.3.1|间接依赖|npm|
|lodash._arrayeach|3.0.0|间接依赖|npm|
|spawnback|1.0.0|间接依赖|npm|
|q|1.5.1|间接依赖|npm|
|com.google.inject:guice|4.2.3|直接依赖|maven|
|commander|2.20.3|间接依赖|npm|
|has-binary-data|0.1.3|间接依赖|npm|
|lodash.restparam|3.6.1|间接依赖|npm|
|com.fasterxml.jackson.dataformat:jackson-dataformat-yaml|2.15.2|直接依赖|maven|
|verror|1.10.0|间接依赖|npm|
|dashdash|1.14.1|间接依赖|npm|
|events-to-array|1.1.2|间接依赖|npm|
|typedarray|0.0.6|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|compressible|2.0.17|间接依赖|npm|
|org.apache.hadoop:hadoop-federation-balance|3.4.0-SNAPSHOT|直接依赖|maven|
|regjsgen|0.2.0|间接依赖|npm|
|is-finite|1.1.0|间接依赖|npm|
|org.eclipse.jetty:jetty-security|9.4.51.v20230217|间接依赖|maven|
|asap|2.0.6|间接依赖|npm|
|org.apache.htrace:htrace-core|3.1.0-incubating|间接依赖|maven|
|filename-regex|2.0.1|间接依赖|npm|
|com.google.re2j:re2j|1.1|直接依赖|maven|
|broccoli-sri-hash|1.2.2|间接依赖|npm|
|depd|1.1.2|间接依赖|npm|
|fd-slicer|1.0.1|间接依赖|npm|
|org.apache.commons:commons-csv|1.9.0|直接依赖|maven|
|klaw|1.3.1|间接依赖|npm|
|editions|1.3.4|间接依赖|npm|
|getpass|0.1.7|间接依赖|npm|
|org.eclipse.jetty:jetty-io|9.4.51.v20230217|间接依赖|maven|
|com.sun.jersey:jersey-servlet|1.19.4|直接依赖|maven|
|qs|6.2.3|间接依赖|npm|
|tunnel-agent|0.6.0|间接依赖|npm|
|de.ruedigermoeller:fst|2.50|直接依赖|maven|
|workerpool|2.3.3|间接依赖|npm|
|ember-disable-proxy-controllers|1.0.1|直接依赖|npm|
|rsvp|3.0.21|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|chownr|1.0.1|间接依赖|npm|
|strip-ansi|0.3.0|间接依赖|npm|
|stdout-stream|1.4.1|间接依赖|npm|
|mime-db|1.42.0|间接依赖|npm|
|org.openjdk.jmh:jmh-generator-annprocess|1.20|直接依赖|maven|
|broccoli-debug|0.6.5|间接依赖|npm|
|delayed-stream|1.0.0|间接依赖|npm|
|is-git-url|0.2.3|间接依赖|npm|
|org.ehcache:ehcache|3.3.1|直接依赖|maven|
|org.apache.hadoop:hadoop-rumen|3.4.0-SNAPSHOT|直接依赖|maven|
|amd-name-resolver|0.0.2|间接依赖|npm|
|io.grpc:grpc-protobuf|1.26.0|直接依赖|maven|
|com.squareup.okio:okio-jvm|3.4.0|直接依赖|maven|
|psl|1.8.0|间接依赖|npm|
|org.apache.kerby:kerby-util|2.0.3|间接依赖|maven|
|source-map|0.1.32|间接依赖|npm|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.12.7|直接依赖|maven|
|javax.websocket:javax.websocket-client-api|1.0|间接依赖|maven|
|process-nextick-args|2.0.1|间接依赖|npm|
|io.netty:netty-transport-udt|4.1.94.Final|间接依赖|maven|
|console-browserify|1.1.0|间接依赖|npm|
|io.grpc:grpc-context|1.26.0|间接依赖|maven|
|aproba|1.2.0|间接依赖|npm|
|form-data|2.1.4|间接依赖|npm|
|ms|2.0.0|间接依赖|npm|
|com.sun.jersey.contribs:jersey-guice|1.19.4|直接依赖|maven|
|broccoli-filter|1.3.0|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|org.apache.commons:commons-compress|1.21|直接依赖|maven|
|safe-buffer|5.1.2|间接依赖|npm|
|org.apache.hadoop:hadoop-fs2img|3.4.0-SNAPSHOT|直接依赖|maven|
|org.apache.hbase:hbase-common|1.7.1|直接依赖|maven|
|minimist|0.0.8|间接依赖|npm|
|org.codehaus.woodstox:stax2-api|4.2.1|直接依赖|maven|
|blob|0.0.4|间接依赖|npm|
|gauge|2.7.4|间接依赖|npm|
|color-name|1.1.3|间接依赖|npm|
|github-url-from-git|1.4.0|间接依赖|npm|
|lru-cache|2.7.3|间接依赖|npm|
|com.google.protobuf:protobuf-java|3.7.1|直接依赖|maven|
|ember-cli-inject-live-reload|1.4.0|直接依赖|npm|
|silent-error|1.1.1|间接依赖|npm|
|cookie-signature|1.0.6|间接依赖|npm|
|broccoli-babel-transpiler|5.7.4|间接依赖|npm|
|org.apache.kerby:kerb-client|2.0.3|间接依赖|maven|
|tree-sync|1.4.0|间接依赖|npm|
|which-module|2.0.0|间接依赖|npm|
|spdx-correct|3.1.1|间接依赖|npm|
|json-schema|0.2.3|间接依赖|npm|
|printf|0.2.5|间接依赖|npm|
|markdown-it-terminal|0.0.2|间接依赖|npm|
|yargs|13.3.2|间接依赖|npm|
|com.amazonaws:aws-java-sdk-bundle|1.12.499|直接依赖|maven|
|opener|1.4.3|间接依赖|npm|
|escape-html|1.0.3|间接依赖|npm|
|readable-stream|2.3.6|直接依赖|npm|
|rimraf|2.2.8|间接依赖|npm|
|has-cors|1.1.0|间接依赖|npm|
|benchmark|1.0.0|间接依赖|npm|
|org.apache.kerby:kerb-identity|2.0.3|间接依赖|maven|
|node-uuid|1.4.8|间接依赖|npm|
|org.ow2.asm:asm-tree|9.4|间接依赖|maven|
|spdx-license-ids|3.0.7|间接依赖|npm|
|lodash.defaults|3.1.2|间接依赖|npm|
|diff|1.4.0|间接依赖|npm|
|org.checkerframework:checker-qual|2.5.2|间接依赖|maven|
|wcwidth|1.0.1|间接依赖|npm|
|org.apache.kerby:kerb-core|2.0.3|直接依赖|maven|
|once|1.4.0|间接依赖|npm|
|fstream-ignore|1.0.5|间接依赖|npm|
|progress|1.1.8|间接依赖|npm|
|com.yammer.metrics:metrics-core|2.2.0|间接依赖|maven|
|log4j:log4j|1.2.17|直接依赖|maven|
|com.aliyun.oss:aliyun-sdk-oss|3.13.2|直接依赖|maven|
|lodash.padstart|4.6.1|间接依赖|npm|
|fileset|0.2.1|间接依赖|npm|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.2|间接依赖|maven|
|fast-deep-equal|3.1.3|间接依赖|npm|
|ansi-styles|1.1.0|间接依赖|npm|
|org.eclipse.jetty.http2:http2-hpack|9.4.44.v20210927|间接依赖|maven|
|org.apache.commons:commons-math3|3.6.1|直接依赖|maven|
|walk-sync|0.1.3|间接依赖|npm|
|archy|1.0.0|间接依赖|npm|
|promise-map-series|0.2.3|间接依赖|npm|
|com.sun.jersey:jersey-server|1.19.4|直接依赖|maven|
|config-chain|1.1.12|间接依赖|npm|
|npm-cache-filename|1.0.2|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|socket.io-adapter|0.3.1|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|extglob|0.3.2|间接依赖|npm|
|remove-trailing-separator|1.1.0|间接依赖|npm|
|on-headers|1.0.2|间接依赖|npm|
|convert-source-map|1.7.0|间接依赖|npm|
|exit|0.1.2|间接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|io.opentracing:opentracing-util|0.33.0|间接依赖|maven|
|lodash._arraycopy|3.0.0|间接依赖|npm|
|bytes|3.0.0|间接依赖|npm|
|com.qcloud:cos_api-bundle|5.6.19|间接依赖|maven|
|buffer-from|1.1.1|间接依赖|npm|
|com.cedarsoftware:java-util|1.9.0|间接依赖|maven|
|extract-zip|1.5.0|间接依赖|npm|
|ember-cli-htmlbars|1.0.2|直接依赖|npm|
|exists-sync|0.0.4|间接依赖|npm|
|true-case-path|1.0.3|间接依赖|npm|
|commons-validator:commons-validator|1.6|间接依赖|maven|
|finalhandler|1.1.2|间接依赖|npm|
|async-some|1.0.2|间接依赖|npm|
|org.apache.maven:maven-model|3.0.5|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-common|3.4.0-SNAPSHOT|直接依赖|maven|
|io.netty:netty-all|4.1.94.Final|直接依赖|maven|
|are-we-there-yet|1.0.6|间接依赖|npm|
|resolve|1.20.0|间接依赖|npm|
|expand-range|1.8.2|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|walk-sync|0.2.7|间接依赖|npm|
|broccoli-plugin|1.3.1|间接依赖|npm|
|write-file-atomic|1.1.4|间接依赖|npm|
|babel-plugin-member-expression-literals|1.0.1|间接依赖|npm|
|org.apache.maven:maven-settings|3.0.5|间接依赖|maven|
|colors|0.6.2|间接依赖|npm|
|leek|0.0.18|间接依赖|npm|
|strip-indent|1.0.1|间接依赖|npm|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|org.apache.hadoop:hadoop-yarn-server-web-proxy|3.4.0-SNAPSHOT|直接依赖|maven|
|punycode|2.1.1|间接依赖|npm|
|org.apache.hadoop:hadoop-yarn-server-resourcemanager|3.4.0-SNAPSHOT|直接依赖|maven|
|io.netty:netty-codec-memcache|4.1.94.Final|间接依赖|maven|
|source-map|0.1.43|间接依赖|npm|
|org.apache.curator:curator-client|5.2.0|直接依赖|maven|
|ember-cli-uglify|1.2.0|直接依赖|npm|
|mkdirp|0.5.5|间接依赖|npm|
|io.netty:netty-codec-haproxy|4.1.94.Final|间接依赖|maven|
|micromatch|2.3.11|间接依赖|npm|
|object-component|0.0.3|间接依赖|npm|
|net.sf.jopt-simple:jopt-simple|4.6|间接依赖|maven|
|org.sonatype.plexus:plexus-sec-dispatcher|1.3|间接依赖|maven|
|org.apache.solr:solr-solrj|8.11.2|直接依赖|maven|
|javax.inject:javax.inject|1|直接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.68|直接依赖|maven|
|em-table|0.12.0|直接依赖|npm|
|org.apache.hbase.thirdparty:hbase-shaded-gson|3.0.0|间接依赖|maven|
|sri-toolbox|0.2.0|间接依赖|npm|
|lodash-node|3.10.2|间接依赖|npm|
|request-progress|2.0.1|间接依赖|npm|
|rsvp|3.6.2|间接依赖|npm|
|is-extendable|0.1.1|间接依赖|npm|
|babel-plugin-remove-console|1.0.1|间接依赖|npm|
|org.eclipse.jetty.websocket:javax-websocket-client-impl|9.4.51.v20230217|间接依赖|maven|
|yauzl|2.4.1|间接依赖|npm|
|consolidate|0.13.1|间接依赖|npm|
|ember-data|2.1.0|直接依赖|npm|
|com.google.code.gson:gson|2.9.0|直接依赖|maven|
|assert-plus|0.2.0|间接依赖|npm|
|semver|4.3.6|间接依赖|npm|
|phantomjs-prebuilt|2.1.13|直接依赖|npm|
|center-align|0.1.3|间接依赖|npm|
|spdx-expression-parse|3.0.1|间接依赖|npm|
|copy-dereference|1.0.0|间接依赖|npm|
|glob|4.5.3|间接依赖|npm|
|io.netty:netty-handler|4.1.94.Final|直接依赖|maven|
|ember-lodash|0.0.10|直接依赖|npm|
|broccoli-kitchen-sink-helpers|0.3.1|间接依赖|npm|
|cookie|0.4.0|间接依赖|npm|
|org.xerial.snappy:snappy-java|1.1.10.1|直接依赖|maven|
|signal-exit|3.0.3|间接依赖|npm|
|walk-sync|0.3.4|间接依赖|npm|
|d|0.1.1|间接依赖|npm|
|supports-color|0.2.0|间接依赖|npm|
|git-repo-version|0.3.0|间接依赖|npm|
|object-assign|3.0.0|间接依赖|npm|
|lodash.pairs|3.0.1|间接依赖|npm|
|memoizee|0.3.10|间接依赖|npm|
|pinkie-promise|2.0.1|间接依赖|npm|
|abbrev|1.0.9|间接依赖|npm|
|generate-object-property|1.2.0|间接依赖|npm|
|com.sun.jersey.jersey-test-framework:jersey-test-framework-grizzly2|1.19.4|直接依赖|maven|
|readable-stream|1.1.13|间接依赖|npm|
|osenv|0.1.5|间接依赖|npm|
|uid-number|0.0.6|间接依赖|npm|
|org.slf4j:jcl-over-slf4j|1.7.30|直接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.4.51.v20230217|直接依赖|maven|
|ms|0.6.2|间接依赖|npm|
|org.apache.hadoop:hadoop-yarn-server-common|3.4.0-SNAPSHOT|直接依赖|maven|
|org.apache.hadoop:hadoop-yarn-services-core|3.4.0-SNAPSHOT|直接依赖|maven|
|org.apache.maven:maven-model-builder|3.0.5|间接依赖|maven|
|org.apache.hadoop:hadoop-gridmix|3.4.0-SNAPSHOT|直接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.94.Final|间接依赖|maven|
|org.glassfish.grizzly:grizzly-rcm|2.2.16|间接依赖|maven|
|handlebars|3.0.7|间接依赖|npm|
|chalk|1.1.0|间接依赖|npm|
|path-root-regex|0.1.2|间接依赖|npm|
|com.aliyun:aliyun-java-sdk-core|4.5.10|间接依赖|maven|
|com.aliyun:aliyun-java-sdk-ram|3.1.0|间接依赖|maven|
|stringstream|0.0.6|间接依赖|npm|
|path-is-inside|1.0.2|间接依赖|npm|
|jakarta.activation:jakarta.activation-api|1.2.1|直接依赖|maven|
|regenerate|1.4.0|间接依赖|npm|
|bytes|2.4.0|间接依赖|npm|
|org.apache.curator:curator-recipes|5.2.0|直接依赖|maven|
|fs-extra|0.24.0|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)