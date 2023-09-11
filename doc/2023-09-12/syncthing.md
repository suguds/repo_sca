# syncthing/syncthing安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1701298600431894528.svg)](https://www.murphysec.com/console/report/1693688105847840768/1701298600431894528)

仓库描述：Open Source Continuous File Synchronization

仓库地址：[https://github.com/syncthing/syncthing](https://github.com/syncthing/syncthing)

| star：54195 | watch：994 | fork：3868 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-12 00:42:32 | 许可证：MPL-2.0 |
| 最近检测时间：2023-09-12 02:16:37 | 组件总数：1123 | 漏洞总数：106 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Joyent Node.js qs模块拒绝服务漏洞|资源管理错误|[MPS-2014-6155](https://www.oscs1024.com/hd/MPS-2014-6155)|CVE-2014-7191|中危|
|Joyent Node.js semver 资源管理错误漏洞|资源管理错误|[MPS-2017-0612](https://www.oscs1024.com/hd/MPS-2017-0612)|CVE-2015-8855|高危|
|Joyent Node.js tar 后置链接漏洞|在文件访问前对链接解析不恰当（链接跟随）|[MPS-2017-0617](https://www.oscs1024.com/hd/MPS-2017-0617)|CVE-2015-8860|高危|
|web framework qs模块输入验证漏洞|输入验证不恰当|[MPS-2017-7711](https://www.oscs1024.com/hd/MPS-2017-7711)|CVE-2017-1000048|高危|
|https-proxy-agent 安全漏洞|资源管理错误|[MPS-2018-16541](https://www.oscs1024.com/hd/MPS-2018-16541)|CVE-2018-3736|高危|
|qs 模块拒绝服务漏洞|资源管理错误|[MPS-2018-6699](https://www.oscs1024.com/hd/MPS-2018-6699)|CVE-2014-10064|高危|
|Minimatch 拒绝服务漏洞|拒绝服务|[MPS-2018-6725](https://www.oscs1024.com/hd/MPS-2018-6725)|CVE-2016-10540|高危|
|Http-signature 安全漏洞|密码学签名的验证不恰当|[MPS-2018-6996](https://www.oscs1024.com/hd/MPS-2018-6996)|CVE-2017-16005|高危|
|superagent 安全漏洞|拒绝服务|[MPS-2018-7202](https://www.oscs1024.com/hd/MPS-2018-7202)|CVE-2017-16129|中危|
|mime模块拒绝服务漏洞|拒绝服务|[MPS-2018-7211](https://www.oscs1024.com/hd/MPS-2018-7211)|CVE-2017-16138|高危|
|https-proxy-agent 安全漏洞|越界读取|[MPS-2018-7304](https://www.oscs1024.com/hd/MPS-2018-7304)|CVE-2018-3739|严重|
|node-tar [, 2.2.2)、[3.0.0, 4.4.2)  任意文件覆盖漏洞|在文件访问前对链接解析不恰当（链接跟随）|[MPS-2019-4705](https://www.oscs1024.com/hd/MPS-2019-4705)|CVE-2018-20834|高危|
|fstream <1.0.12 链接解析错误漏洞|在文件访问前对链接解析不恰当（链接跟随）|[MPS-2019-7423](https://www.oscs1024.com/hd/MPS-2019-7423)|CVE-2019-13173|高危|
|SockJS <0.3.20 异常处理不当漏洞|对异常条件的处理不恰当|[MPS-2020-10001](https://www.oscs1024.com/hd/MPS-2020-10001)|CVE-2020-7693|中危|
|Ajv v6.12.2 输入验证错误漏洞|MAID|[MPS-2020-10525](https://www.oscs1024.com/hd/MPS-2020-10525)|CVE-2020-15366|中危|
|node-forge <0.10.0 对象属性的不当控制修改漏洞|动态确定对象属性修改的控制不恰当|[MPS-2020-12281](https://www.oscs1024.com/hd/MPS-2020-12281)|CVE-2020-7720|高危|
|chart.js 输入验证错误漏洞|原型污染|[MPS-2020-15331](https://www.oscs1024.com/hd/MPS-2020-15331)|CVE-2020-7746|严重|
|lodash <4.17.15 原型污染漏洞|原型污染|[MPS-2020-15679](https://www.oscs1024.com/hd/MPS-2020-15679)|CVE-2020-8203|高危|
|Yargs Y18n 输入原型污染漏洞|动态确定对象属性修改的控制不恰当|[MPS-2020-17543](https://www.oscs1024.com/hd/MPS-2020-17543)|CVE-2020-7774|严重|
|Ini <1.3.6原型污染漏洞|拒绝服务|[MPS-2020-17544](https://www.oscs1024.com/hd/MPS-2020-17544)|CVE-2020-7788|高危|
|component-flatten 注入漏洞|注入|[MPS-2020-2616](https://www.oscs1024.com/hd/MPS-2020-2616)|CVE-2019-10794|中危|
|yargs-parser 原型污染漏洞|特权定义了不安全动作|[MPS-2020-4006](https://www.oscs1024.com/hd/MPS-2020-4006)|CVE-2020-7608|中危|
|decompress package 路径遍历漏洞|路径遍历|[MPS-2020-6640](https://www.oscs1024.com/hd/MPS-2020-6640)|CVE-2020-12265|严重|
|serialize-javascript <3.1.0 任意代码执行漏洞|反序列化|[MPS-2020-7976](https://www.oscs1024.com/hd/MPS-2020-7976)|CVE-2020-7660|高危|
|websocket-extensions<0.1.4 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2020-8041](https://www.oscs1024.com/hd/MPS-2020-8041)|CVE-2020-7662|高危|
|websocket-extensions 拒绝服务漏洞|拒绝服务|[MPS-2020-8042](https://www.oscs1024.com/hd/MPS-2020-8042)|CVE-2020-7663|高危|
|Elliptic package 签名伪造漏洞|整数溢出或环绕|[MPS-2020-8202](https://www.oscs1024.com/hd/MPS-2020-8202)|CVE-2020-13822|高危|
|Socketio Engineio 资源管理错误漏洞|拒绝服务|[MPS-2021-0191](https://www.oscs1024.com/hd/MPS-2021-0191)|CVE-2020-36048|高危|
|Socketio Engineio 资源管理错误漏洞|拒绝服务|[MPS-2021-0192](https://www.oscs1024.com/hd/MPS-2021-0192)|CVE-2020-36049|高危|
|Socketio Socket.io CORS漏洞|源验证错误|[MPS-2021-0652](https://www.oscs1024.com/hd/MPS-2021-0652)|CVE-2020-28481|中危|
|jszip 原型污染漏洞|原型污染|[MPS-2021-11050](https://www.oscs1024.com/hd/MPS-2021-11050)|CVE-2021-23413|中危|
|url-parse <1.5.2 开放重定向漏洞|跨站重定向|[MPS-2021-11194](https://www.oscs1024.com/hd/MPS-2021-11194)|CVE-2021-3664|中危|
|Indutny Elliptic 加密问题漏洞|密码算法不安全|[MPS-2021-1176](https://www.oscs1024.com/hd/MPS-2021-1176)|CVE-2020-28498|中危|
|ansi-html <0.0.8 DoS 漏洞|拒绝服务|[MPS-2021-17628](https://www.oscs1024.com/hd/MPS-2021-17628)|CVE-2021-23424|高危|
|pac-resolver <5.0.0 RCE漏洞|代码注入|[MPS-2021-17857](https://www.oscs1024.com/hd/MPS-2021-17857)|CVE-2021-23406|严重|
|UIkarma 打开重定向漏洞|跨站重定向|[MPS-2021-19534](https://www.oscs1024.com/hd/MPS-2021-19534)|CVE-2021-23495|中危|
|url-parse  < 1.5.0 输入验证不当漏洞|相对路径遍历|[MPS-2021-2265](https://www.oscs1024.com/hd/MPS-2021-2265)|CVE-2021-27515|中危|
|requests 代码注入漏洞|代码注入|[MPS-2021-2418](https://www.oscs1024.com/hd/MPS-2021-2418)|CVE-2020-28502|高危|
|lodash 拒绝服务漏洞|拒绝服务|[MPS-2021-2574](https://www.oscs1024.com/hd/MPS-2021-2574)|CVE-2020-28500|中危|
|lodash 命令注入漏洞|代码注入|[MPS-2021-2638](https://www.oscs1024.com/hd/MPS-2021-2638)|CVE-2021-23337|高危|
|Nathan Rajlich node-http-proxy-agent 内存泄漏漏洞|初始化不恰当|[MPS-2021-2813](https://www.oscs1024.com/hd/MPS-2021-2813)|CVE-2019-10196|严重|
|Npm Node-tar 后置链接漏洞||[MPS-2021-28486](https://www.oscs1024.com/hd/MPS-2021-28486)|CVE-2021-37701|高危|
|Npm Node-tar 后置链接漏洞||[MPS-2021-28488](https://www.oscs1024.com/hd/MPS-2021-28488)|CVE-2021-37712|高危|
|node-tar 路径遍历漏洞|路径遍历|[MPS-2021-28489](https://www.oscs1024.com/hd/MPS-2021-28489)|CVE-2021-37713|高危|
|ssri 拒绝服务漏洞|拒绝服务|[MPS-2021-3030](https://www.oscs1024.com/hd/MPS-2021-3030)|CVE-2021-27290|高危|
|Sindre Sorhus is-svg 拒绝服务漏洞|拒绝服务|[MPS-2021-3031](https://www.oscs1024.com/hd/MPS-2021-3031)|CVE-2021-28092|高危|
|nodejs 正则表达式漏洞|拒绝服务|[MPS-2021-31423](https://www.oscs1024.com/hd/MPS-2021-31423)|CVE-2021-3777|高危|
|Ruy Adorno hosted-git-info 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-3400](https://www.oscs1024.com/hd/MPS-2021-3400)|CVE-2021-23362|中危|
|Async 原型污染漏洞|原型污染|[MPS-2021-34434](https://www.oscs1024.com/hd/MPS-2021-34434)|CVE-2021-43138|高危|
|json-schema 安全漏洞|原型污染|[MPS-2021-34478](https://www.oscs1024.com/hd/MPS-2021-34478)|CVE-2021-3918|严重|
|log4js-node 存在信息泄露漏洞|缺省权限不正确|[MPS-2021-37062](https://www.oscs1024.com/hd/MPS-2021-37062)|CVE-2022-21704|中危|
|minimist 安全漏洞|原型污染|[MPS-2021-38405](https://www.oscs1024.com/hd/MPS-2021-38405)|CVE-2021-44906|严重|
|Dan DeFelippi node-XMLHttpRequest 信任管理问题漏洞|证书验证不恰当|[MPS-2021-5338](https://www.oscs1024.com/hd/MPS-2021-5338)|CVE-2021-31597|严重|
|postcss 存在正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-5409](https://www.oscs1024.com/hd/MPS-2021-5409)|CVE-2021-23382|中危|
|browserslist 存在正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-5473](https://www.oscs1024.com/hd/MPS-2021-5473)|CVE-2021-23364|中危|
|npm path-parse 安全漏洞|拒绝服务|[MPS-2021-6165](https://www.oscs1024.com/hd/MPS-2021-6165)|CVE-2021-23343|高危|
|dns-packet 存在信息泄露漏洞|资源初始化缺失|[MPS-2021-7013](https://www.oscs1024.com/hd/MPS-2021-7013)|CVE-2021-23386|中危|
|ws 存在拒绝服务漏洞||[MPS-2021-7109](https://www.oscs1024.com/hd/MPS-2021-7109)|CVE-2021-32640|中危|
|glob-parent < 5.1.2 存在拒绝服务漏洞|拒绝服务|[MPS-2021-7827](https://www.oscs1024.com/hd/MPS-2021-7827)|CVE-2020-28469|高危|
|Color-String < 1.5.5 存在正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-8683](https://www.oscs1024.com/hd/MPS-2021-8683)|CVE-2021-29060|中危|
|is-svg 存在正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-8684](https://www.oscs1024.com/hd/MPS-2021-8684)|CVE-2021-29059|高危|
|Digital Bazaar Forge 存在输入验证错误漏洞|跨站重定向|[MPS-2022-0421](https://www.oscs1024.com/hd/MPS-2022-0421)|CVE-2022-0122|中危|
|follow-redirects <1.14.7 存在信息泄露漏洞|侵犯隐私|[MPS-2022-0815](https://www.oscs1024.com/hd/MPS-2022-0815)|CVE-2022-0155|中危|
|EventSource 信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-10212](https://www.oscs1024.com/hd/MPS-2022-10212)|CVE-2022-1650|严重|
|Moment.js 正则拒绝服务漏洞|拒绝服务|[MPS-2022-11159](https://www.oscs1024.com/hd/MPS-2022-11159)|CVE-2022-31129|高危|
|Angular 跨站脚本漏洞|XSS|[MPS-2022-12764](https://www.oscs1024.com/hd/MPS-2022-12764)|CVE-2021-4231|中危|
|superagent < 3.8.1 存在信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-13104](https://www.oscs1024.com/hd/MPS-2022-13104)||中危|
|adm-zip <0.5.2存在路径遍历漏洞|路径遍历|[MPS-2022-13529](https://www.oscs1024.com/hd/MPS-2022-13529)||高危|
|@angular/core 存在跨站脚本漏洞|XSS|[MPS-2022-13545](https://www.oscs1024.com/hd/MPS-2022-13545)||低危|
|http-proxy<1.18.1 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13767](https://www.oscs1024.com/hd/MPS-2022-13767)||中危|
|https-proxy-agent 存在中间人攻击漏洞|中间人攻击|[MPS-2022-13770](https://www.oscs1024.com/hd/MPS-2022-13770)||中危|
|istanbul-reports<3.1.3 反向 Tabnabbing漏洞|通过 window.opener 访问使用指向不受信任目标的 Web 链接|[MPS-2022-13797](https://www.oscs1024.com/hd/MPS-2022-13797)||中危|
|lodash<4.17.20 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13841](https://www.oscs1024.com/hd/MPS-2022-13841)||高危|
|lodash<4.17.17 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13842](https://www.oscs1024.com/hd/MPS-2022-13842)||高危|
|minimatch < 3.0.2 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13882](https://www.oscs1024.com/hd/MPS-2022-13882)||高危|
|node-forge <1.0.0 存在原型污染漏洞|原型污染|[MPS-2022-13920](https://www.oscs1024.com/hd/MPS-2022-13920)||中危|
|@npmcli/git <2.0.8 存在命令注入漏洞|OS命令注入|[MPS-2022-13935](https://www.oscs1024.com/hd/MPS-2022-13935)||中危|
|npm-registry-fetch 存在日志敏感信息泄露漏洞|日志敏感信息泄露|[MPS-2022-13937](https://www.oscs1024.com/hd/MPS-2022-13937)||中危|
|uuid<1.3.1 存在不安全的随机数漏洞|使用不充分的随机数|[MPS-2022-15362](https://www.oscs1024.com/hd/MPS-2022-15362)||中危|
|Karma 跨站脚本漏洞|XSS|[MPS-2022-2997](https://www.oscs1024.com/hd/MPS-2022-2997)|CVE-2022-0437|中危|
|url-parse 存在访问限制绕过漏洞|通过用户控制密钥绕过授权机制|[MPS-2022-3327](https://www.oscs1024.com/hd/MPS-2022-3327)|CVE-2022-0512|中危|
|follow-redirects<1.14.8 信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-3636](https://www.oscs1024.com/hd/MPS-2022-3636)|CVE-2022-0536|中危|
|node-forge 密码签名验证不当漏洞|密码学签名的验证不恰当|[MPS-2022-3738](https://www.oscs1024.com/hd/MPS-2022-3738)|CVE-2022-24771|高危|
|node-forge 密码签名验证不当漏洞|密码学签名的验证不恰当|[MPS-2022-3739](https://www.oscs1024.com/hd/MPS-2022-3739)|CVE-2022-24772|高危|
|node-forge 密码签名验证不当漏洞|密码学签名的验证不恰当|[MPS-2022-3740](https://www.oscs1024.com/hd/MPS-2022-3740)|CVE-2022-24773|中危|
|Moment.js 路径遍历漏洞|路径遍历|[MPS-2022-3752](https://www.oscs1024.com/hd/MPS-2022-3752)|CVE-2022-24785|中危|
|Express 中的 qs 模块存在原型污染漏洞|原型污染|[MPS-2022-3967](https://www.oscs1024.com/hd/MPS-2022-3967)|CVE-2022-24999|高危|
|url-parse <1.5.7 存在密钥授权绕过漏洞|通过用户控制密钥绕过授权机制|[MPS-2022-4297](https://www.oscs1024.com/hd/MPS-2022-4297)|CVE-2022-0639|中危|
|NPM url-parse授权绕过漏洞||[MPS-2022-4464](https://www.oscs1024.com/hd/MPS-2022-4464)|CVE-2022-0686|严重|
|Url-parse <1.5.9 存在输入验证不当漏洞||[MPS-2022-4474](https://www.oscs1024.com/hd/MPS-2022-4474)|CVE-2022-0691|严重|
|terser 安全漏洞|ReDoS|[MPS-2022-5145](https://www.oscs1024.com/hd/MPS-2022-5145)|CVE-2022-25858|高危|
|http-cache-semantics 安全漏洞|ReDoS|[MPS-2022-5164](https://www.oscs1024.com/hd/MPS-2022-5164)|CVE-2022-25881|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|CookieJar <2.1.4正则表达式拒绝服务漏洞|ReDoS|[MPS-2022-5182](https://www.oscs1024.com/hd/MPS-2022-5182)|CVE-2022-25901|高危|
|loader-utils 安全漏洞|不正确的正则表达式|[MPS-2022-53512](https://www.oscs1024.com/hd/MPS-2022-53512)|CVE-2022-37599|高危|
|loader-utils v2.0.0 原型污染漏洞|动态确定对象属性修改的控制不恰当|[MPS-2022-53514](https://www.oscs1024.com/hd/MPS-2022-53514)|CVE-2022-37601|中危|
|loader-utils 安全漏洞|不正确的正则表达式|[MPS-2022-53516](https://www.oscs1024.com/hd/MPS-2022-53516)|CVE-2022-37603|高危|
|decode-uri-component <=0.2.0 存在输入验证不当漏洞|拒绝服务|[MPS-2022-56259](https://www.oscs1024.com/hd/MPS-2022-56259)|CVE-2022-38900|高危|
|Socketio Engine.IO拒绝服务漏洞|未捕获的异常|[MPS-2022-58577](https://www.oscs1024.com/hd/MPS-2022-58577)|CVE-2022-41940|中危|
|minimatch 资源管理错误漏洞|拒绝服务|[MPS-2022-59845](https://www.oscs1024.com/hd/MPS-2022-59845)|CVE-2022-3517|高危|
|Tauri 原型污染漏洞|原型污染|[MPS-2022-65568](https://www.oscs1024.com/hd/MPS-2022-65568)|CVE-2022-46175|高危|
|JSZip目录穿越漏洞|相对路径遍历|[MPS-2023-3073](https://www.oscs1024.com/hd/MPS-2023-3073)|CVE-2022-48285|高危|
|xml2js 安全漏洞|原型污染|[MPS-2023-4673](https://www.oscs1024.com/hd/MPS-2023-4673)|CVE-2023-0842|中危|
|tough-cookie 安全漏洞|原型污染|[MPS-2023-5130](https://www.oscs1024.com/hd/MPS-2023-5130)|CVE-2023-26136|严重|
|request SSRF防御绕过漏洞|SSRF|[MPS-2023-7722](https://www.oscs1024.com/hd/MPS-2023-7722)|CVE-2023-28155|中危|
|tough-cookie<4.1.3 存在原型污染漏洞|原型污染|[MPS-esyq-56vx](https://www.oscs1024.com/hd/MPS-esyq-56vx)||中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|xmlhttprequest-ssl|1.5.5|1.6.2|间接依赖|强烈建议修复|C:1|H:1|M:0|L:0|
|eventsource|1.0.7|2.0.2|间接依赖|强烈建议修复|C:1|H:0|M:0|L:0|
|tough-cookie|2.5.0|4.1.3|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|y18n|3.2.1|5.0.5|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|minimist|1.2.5|1.2.6|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|loader-utils|2.0.0|3.2.1|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|socket.io-parser|3.2.0|4.2.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|http-proxy-agent|0.2.7|2.1.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|is-svg|3.0.0|4.3.0|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|ssri|8.0.0|8.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|https-proxy-agent|0.3.6|2.2.3|间接依赖|建议修复|C:1|H:1|M:1|L:0|
|minimatch|0.2.14|3.0.5|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|decompress|0.2.5|4.2.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|jszip|3.3.0|3.8.0|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|json-schema|0.2.3|0.4.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|chart.js|2.9.3|2.9.4|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|sockjs|0.3.19|0.3.20|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|node-forge|0.9.0|1.3.0|间接依赖|建议修复|C:0|H:3|M:3|L:0|
|url-parse|1.4.7|1.5.9|间接依赖|建议修复|C:2|H:0|M:4|L:0|
|fstream|0.1.31|1.0.12|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|express|4.17.1|4.17.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|lodash|4.17.15|4.17.21|间接依赖|建议修复|C:0|H:4|M:1|L:0|
|ini|1.3.5|1.3.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|websocket-extensions|0.1.3|0.1.4|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|glob-parent|3.1.0|6.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|decode-uri-component|0.2.0|0.2.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|engine.io|3.2.1|6.4.2|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|terser|4.6.7|5.14.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|adm-zip|0.4.14|0.5.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|semver|2.3.2|7.5.2|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|http-signature|1.2.0||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tar|0.1.20|6.1.9|间接依赖|建议修复|C:0|H:5|M:0|L:0|
|pac-resolver|1.2.6|5.0.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|serialize-javascript|2.1.2|3.1.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tmpl|1.0.4|1.0.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|ansi-html|0.0.7|0.0.8|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|path-parse|1.0.6|1.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|mime|1.2.5|2.0.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|json5|2.1.2|2.2.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|elliptic|6.5.2|6.5.4|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|ws|6.2.1|7.4.6|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|browserslist|4.11.1|4.16.5|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|color-string|1.5.3|1.5.5|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|istanbul-reports|2.2.7|3.1.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|xml2js|0.4.23|0.5.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|dns-packet|1.3.1|5.2.4|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|qs|0.6.5|6.10.3|间接依赖|可选修复|C:0|H:2|M:1|L:0|
|http-proxy|1.18.0|1.18.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|uuid|1.4.2|2.0.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|cookiejar|1.3.0|2.1.4|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|postcss|2.2.6|8.2.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|ajv|6.12.0|6.12.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|async|2.6.3|3.2.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|@npmcli/git|2.0.1|2.0.8|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|component-flatten|1.0.1||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|request|2.88.2||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|hosted-git-info|3.0.4|3.0.8|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|yargs-parser|11.1.1|18.1.1|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|@angular/core|9.1.0|11.1.0-next.3|直接依赖|可选修复|C:0|H:0|M:1|L:1|
|superagent|0.17.0|3.8.1|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|log4js|4.5.1|6.4.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|http-cache-semantics|4.1.0|4.1.1|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|moment|2.24.0|2.29.4|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|npm-registry-fetch|8.0.0|8.1.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|karma|4.3.0|6.3.16|直接依赖|可选修复|C:0|H:0|M:2|L:0|
|socket.io|2.1.1|2.4.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|follow-redirects|1.11.0|1.14.8|间接依赖|可选修复|C:0|H:0|M:2|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|44|Low|
|MIT|888|Low|
|BSD-3-Clause|38|Low|
|ISC|88|Low|
|BSD-2-Clause|18|Low|
|BSD|7|Low|
|MPL-2.0|3|Low|
|BSD-2-Clause-Views|1|Low|
|CC-BY-4.0|2|Low|
|Unlicense|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|worker-plugin|4.0.2|间接依赖|npm|
|has-cors|1.1.0|间接依赖|npm|
|p-defer|1.0.0|间接依赖|npm|
|loader-utils|2.0.0|间接依赖|npm|
|@istanbuljs/schema|0.1.2|间接依赖|npm|
|@xtuc/ieee754|1.2.0|间接依赖|npm|
|pac-resolver|1.2.6|间接依赖|npm|
|mime-types|2.1.26|间接依赖|npm|
|buffer|4.9.2|间接依赖|npm|
|github.com/lib/pq|v1.10.9|直接依赖|go|
|@types/events|3.0.0|间接依赖|npm|
|jsesc|2.5.2|间接依赖|npm|
|karma-jasmine-html-reporter|1.5.3|直接依赖|npm|
|minimatch|0.2.14|间接依赖|npm|
|http-parser-js|0.4.10|间接依赖|npm|
|@npmcli/promise-spawn|1.1.0|间接依赖|npm|
|promise|7.3.1|间接依赖|npm|
|atob|2.1.2|间接依赖|npm|
|q|1.5.1|间接依赖|npm|
|github.com/calmh/incontainer|v0.0.0-20221224152218-b3e71b103d7a|直接依赖|go|
|dot-prop|5.2.0|直接依赖|npm|
|github.com/russross/blackfriday/v2|v2.1.0|间接依赖|go|
|util-deprecate|1.0.2|间接依赖|npm|
|exit|0.1.2|间接依赖|npm|
|debuglog|1.0.1|间接依赖|npm|
|less-loader|5.0.0|间接依赖|npm|
|asynckit|0.4.0|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|immediate|3.0.6|间接依赖|npm|
|indexes-of|1.0.1|间接依赖|npm|
|p-retry|3.0.1|间接依赖|npm|
|snapdragon-util|3.0.1|间接依赖|npm|
|socks-proxy-agent|1.0.2|间接依赖|npm|
|regenerate|1.4.0|间接依赖|npm|
|universal-analytics|0.4.20|间接依赖|npm|
|sprintf-js|1.0.3|间接依赖|npm|
|faye-websocket|0.4.4|间接依赖|npm|
|@babel/highlight|7.9.0|间接依赖|npm|
|github.com/yusufpapurcu/wmi|v1.2.3|间接依赖|go|
|@angular-devkit/schematics|9.1.0|间接依赖|npm|
|github.com/vitrun/qart|v0.0.0-20160531060029-bf64b92db6b0|直接依赖|go|
|constants-browserify|1.0.0|间接依赖|npm|
|uri-js|4.2.2|间接依赖|npm|
|tapable|1.1.3|间接依赖|npm|
|encodeurl|1.0.2|间接依赖|npm|
|p-map|3.0.0|间接依赖|npm|
|@webassemblyjs/helper-fsm|1.8.5|间接依赖|npm|
|evp_bytestokey|1.0.3|间接依赖|npm|
|component-updater|1.0.5|间接依赖|npm|
|pkg-dir|3.0.0|间接依赖|npm|
|karma-jasmine|2.0.1|直接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|nopt|2.2.1|间接依赖|npm|
|async-limiter|1.0.1|间接依赖|npm|
|raw-loader|4.0.0|间接依赖|npm|
|postcss-merge-rules|4.0.3|间接依赖|npm|
|@babel/helper-explode-assignable-expression|7.8.3|间接依赖|npm|
|tmp|0.0.33|间接依赖|npm|
|align-text|0.1.4|间接依赖|npm|
|github.com/go-ole/go-ole|v1.3.0|间接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|karma-coverage-istanbul-reporter|2.1.1|直接依赖|npm|
|component-bind|1.0.0|间接依赖|npm|
|bcrypt-pbkdf|1.0.2|间接依赖|npm|
|asn1|0.2.4|间接依赖|npm|
|anymatch|3.1.1|间接依赖|npm|
|string.prototype.trimleft|2.1.2|间接依赖|npm|
|netrc|0.1.4|间接依赖|npm|
|arrify|1.0.1|直接依赖|npm|
|ssri|8.0.0|间接依赖|npm|
|etag|1.8.1|间接依赖|npm|
|noptify|0.0.3|间接依赖|npm|
|makeerror|1.0.11|间接依赖|npm|
|is-plain-obj|1.1.0|间接依赖|npm|
|agentkeepalive|4.1.0|间接依赖|npm|
|fast-deep-equal|3.1.1|间接依赖|npm|
|has-symbols|1.0.1|间接依赖|npm|
|arg|4.1.3|间接依赖|npm|
|wordwrap|0.0.2|间接依赖|npm|
|@tootallnate/once|1.0.0|直接依赖|npm|
|@babel/plugin-transform-for-of|7.9.0|间接依赖|npm|
|make-error|1.3.6|间接依赖|npm|
|expand-brackets|2.1.4|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|@babel/plugin-proposal-nullish-coalescing-operator|7.8.3|间接依赖|npm|
|obuf|1.1.2|间接依赖|npm|
|postcss-normalize-positions|4.0.2|间接依赖|npm|
|querystring-es3|0.2.1|间接依赖|npm|
|stream-each|1.2.3|间接依赖|npm|
|after|0.8.2|间接依赖|npm|
|run-queue|1.0.3|间接依赖|npm|
|svgo|1.3.2|间接依赖|npm|
|regenerator-transform|0.14.4|间接依赖|npm|
|@babel/helper-create-regexp-features-plugin|7.8.8|间接依赖|npm|
|is-svg|3.0.0|间接依赖|npm|
|generator-supported|0.0.1|间接依赖|npm|
|forever-agent|0.6.1|间接依赖|npm|
|os-browserify|0.3.0|间接依赖|npm|
|execa|1.0.0|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|path-exists|3.0.0|间接依赖|npm|
|github.com/klauspost/cpuid/v2|v2.2.5|间接依赖|go|
|slash|1.0.0|间接依赖|npm|
|@babel/helper-regex|7.8.3|间接依赖|npm|
|chokidar|3.3.1|间接依赖|npm|
|rgba-regex|1.0.0|间接依赖|npm|
|component|1.1.0|直接依赖|npm|
|golang.org/x/exp|v0.0.0-20230817173708-d852ddb80c63|直接依赖|go|
|diff|4.0.2|间接依赖|npm|
|jasmine|2.8.0|间接依赖|npm|
|wbuf|1.7.3|间接依赖|npm|
|css-select|2.1.0|间接依赖|npm|
|component-manifest|1.0.0|间接依赖|npm|
|@babel/compat-data|7.9.0|间接依赖|npm|
|source-map-url|0.4.0|间接依赖|npm|
|type-fest|0.11.0|间接依赖|npm|
|caniuse-api|3.0.0|间接依赖|npm|
|mkdirp|0.3.5|间接依赖|npm|
|es6-promisify|5.0.0|直接依赖|npm|
|cache-base|1.0.1|间接依赖|npm|
|thunky|1.1.0|间接依赖|npm|
|aws-sign2|0.7.0|间接依赖|npm|
|p-finally|1.0.0|间接依赖|npm|
|extend|3.0.2|间接依赖|npm|
|pseudomap|1.0.2|直接依赖|npm|
|path-type|3.0.0|间接依赖|npm|
|browserify-sign|4.0.4|间接依赖|npm|
|base|0.11.2|间接依赖|npm|
|di|0.0.1|间接依赖|npm|
|qjobs|1.2.0|间接依赖|npm|
|open|7.0.3|间接依赖|npm|
|istanbul-lib-hook|2.0.7|间接依赖|npm|
|url|0.11.0|间接依赖|npm|
|content-type|1.0.4|间接依赖|npm|
|builtin-status-codes|3.0.0|间接依赖|npm|
|@babel/plugin-transform-classes|7.9.2|间接依赖|npm|
|ansi-regex|2.1.1|间接依赖|npm|
|source-list-map|2.0.1|间接依赖|npm|
|postcss-normalize-display-values|4.0.2|间接依赖|npm|
|circular-dependency-plugin|5.2.0|间接依赖|npm|
|archy|0.0.2|间接依赖|npm|
|@babel/plugin-transform-property-literals|7.8.3|间接依赖|npm|
|dezalgo|1.0.3|间接依赖|npm|
|schema-utils|2.6.5|间接依赖|npm|
|regexp.prototype.flags|1.3.0|间接依赖|npm|
|cookiejar|1.3.0|间接依赖|npm|
|@babel/code-frame|7.8.3|间接依赖|npm|
|invariant|2.2.4|间接依赖|npm|
|string_decoder|0.10.31|间接依赖|npm|
|parallel-transform|1.2.0|间接依赖|npm|
|github.com/miscreant/miscreant.go|v0.0.0-20200214223636-26d376326b75|直接依赖|go|
|is-data-descriptor|0.1.4|间接依赖|npm|
|minipass-fetch|1.2.1|间接依赖|npm|
|object-is|1.0.2|间接依赖|npm|
|minipass|3.1.1|间接依赖|npm|
|terser|4.6.7|间接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|optimist|0.6.1|间接依赖|npm|
|connect-history-api-fallback|1.6.0|间接依赖|npm|
|run-async|2.4.0|间接依赖|npm|
|tunnel-agent|0.6.0|间接依赖|npm|
|timers-browserify|2.0.11|间接依赖|npm|
|source-map-loader|0.2.4|间接依赖|npm|
|graceful-fs|2.0.3|间接依赖|npm|
|encoding|0.1.12|间接依赖|npm|
|builder-es6-module-to-cjs|1.1.0|间接依赖|npm|
|sshpk|1.16.1|间接依赖|npm|
|@angular/router|9.1.0|直接依赖|npm|
|is-stream|1.1.0|间接依赖|npm|
|num2fraction|1.2.2|间接依赖|npm|
|fragment-cache|0.2.1|间接依赖|npm|
|postcss-calc|7.0.2|间接依赖|npm|
|colors|1.1.2|间接依赖|npm|
|http-signature|1.2.0|间接依赖|npm|
|node-libs-browser|2.2.1|间接依赖|npm|
|errno|0.1.7|间接依赖|npm|
|read-cache|1.0.0|间接依赖|npm|
|esrecurse|4.2.1|间接依赖|npm|
|js-yaml|3.13.1|间接依赖|npm|
|npm-run-path|2.0.2|间接依赖|npm|
|miller-rabin|4.0.1|间接依赖|npm|
|eventsource|1.0.7|间接依赖|npm|
|@babel/plugin-transform-function-name|7.8.3|间接依赖|npm|
|@webassemblyjs/wasm-parser|1.8.5|间接依赖|npm|
|isstream|0.1.2|间接依赖|npm|
|express|4.17.1|间接依赖|npm|
|postcss-normalize-url|4.0.1|间接依赖|npm|
|fresh|0.5.2|间接依赖|npm|
|detect-node|2.0.4|间接依赖|npm|
|pako|1.0.11|间接依赖|npm|
|is-resolvable|1.1.0|间接依赖|npm|
|make-dir|2.1.0|间接依赖|npm|
|depd|1.1.2|间接依赖|npm|
|chartjs-color|2.4.1|间接依赖|npm|
|prr|1.0.1|间接依赖|npm|
|repeat-string|1.6.1|间接依赖|npm|
|map-age-cleaner|0.1.3|间接依赖|npm|
|terser-webpack-plugin|2.3.5|间接依赖|npm|
|github.com/golang/mock|v1.6.0|间接依赖|go|
|merge-stream|2.0.0|间接依赖|npm|
|@babel/helper-plugin-utils|7.8.3|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|ret|0.1.15|间接依赖|npm|
|license-webpack-plugin|2.1.4|间接依赖|npm|
|binary-extensions|2.0.0|间接依赖|npm|
|postcss-normalize-whitespace|4.0.2|间接依赖|npm|
|webdriver-js-extender|2.1.0|间接依赖|npm|
|flush-write-stream|1.1.1|间接依赖|npm|
|browserstack|1.5.3|间接依赖|npm|
|file-uri-to-path|0.0.2|间接依赖|npm|
|moment|2.24.0|间接依赖|npm|
|github.com/minio/sha256-simd|v1.0.1|直接依赖|go|
|js-base64|2.1.9|间接依赖|npm|
|dethroy|1.0.2|间接依赖|npm|
|stream-combiner|0.0.4|间接依赖|npm|
|spdx-correct|3.1.0|间接依赖|npm|
|is-arrayish|0.2.1|间接依赖|npm|
|@babel/plugin-transform-sticky-regex|7.8.3|间接依赖|npm|
|component-emitter|1.3.0|间接依赖|npm|
|yargs|3.27.0|间接依赖|npm|
|github.com/Azure/go-ntlmssp|v0.0.0-20221128193559-754e69321358|间接依赖|go|
|right-align|0.1.3|间接依赖|npm|
|pbkdf2|3.0.17|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|selenium-webdriver|3.6.0|间接依赖|npm|
|browserify-des|1.0.2|间接依赖|npm|
|public-encrypt|4.0.3|间接依赖|npm|
|is-promise|2.1.0|间接依赖|npm|
|code-point-at|1.1.0|直接依赖|npm|
|component-resolver|1.3.0|间接依赖|npm|
|hosted-git-info|3.0.4|间接依赖|npm|
|ripemd160|2.0.2|间接依赖|npm|
|cookie|0.4.0|间接依赖|npm|
|agent-base|1.0.2|间接依赖|npm|
|domain-browser|1.2.0|间接依赖|npm|
|class-utils|0.3.6|间接依赖|npm|
|jasmine-spec-reporter|4.2.1|直接依赖|npm|
|flatted|2.0.2|间接依赖|npm|
|to-descriptor|1.0.1|间接依赖|npm|
|p-locate|2.0.0|间接依赖|npm|
|csso|4.0.3|间接依赖|npm|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|tmpl|1.0.4|间接依赖|npm|
|style-loader|1.1.3|间接依赖|npm|
|@webassemblyjs/helper-wasm-section|1.8.5|间接依赖|npm|
|cssnano-util-get-arguments|4.0.0|间接依赖|npm|
|cssnano-util-raw-cache|4.0.1|间接依赖|npm|
|karma-chrome-launcher|3.1.0|直接依赖|npm|
|@babel/preset-env|7.9.0|间接依赖|npm|
|magic-string|0.25.7|间接依赖|npm|
|@babel/plugin-transform-arrow-functions|7.8.3|间接依赖|npm|
|@angular-devkit/architect|0.901.0|间接依赖|npm|
|golang.org/x/sys|v0.12.0|直接依赖|go|
|regex-not|1.0.2|间接依赖|npm|
|is-windows|1.0.2|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|rxjs|6.5.5|间接依赖|npm|
|buffer-fill|1.0.0|间接依赖|npm|
|clone-deep|4.0.1|间接依赖|npm|
|@babel/plugin-transform-spread|7.8.3|间接依赖|npm|
|saucelabs|1.5.0|间接依赖|npm|
|arr-diff|4.0.0|间接依赖|npm|
|@webassemblyjs/leb128|1.8.5|间接依赖|npm|
|minimalistic-assert|1.0.1|间接依赖|npm|
|core-js-compat|3.6.4|间接依赖|npm|
|minimist|1.2.5|间接依赖|npm|
|eventemitter3|4.0.0|间接依赖|npm|
|tiny-lr-fork|0.0.5|间接依赖|npm|
|websocket-extensions|0.1.3|间接依赖|npm|
|aggregate-error|3.0.1|间接依赖|npm|
|universalify|0.1.2|间接依赖|npm|
|postcss-load-config|2.1.0|间接依赖|npm|
|cogent|git+ssh://git@github.com/timaschew/cogent.git#2246bd071392f5053a3a110024fd608a40a593ba|间接依赖|npm|
|array-uniq|1.0.3|间接依赖|npm|
|watchpack|1.6.1|间接依赖|npm|
|postcss-value-parser|4.0.3|间接依赖|npm|
|chart.js|2.9.3|直接依赖|npm|
|postcss-merge-longhand|4.0.11|间接依赖|npm|
|object.getownpropertydescriptors|2.1.0|间接依赖|npm|
|fs-minipass|2.1.0|间接依赖|npm|
|@npmcli/git|2.0.1|间接依赖|npm|
|copy-webpack-plugin|5.1.1|间接依赖|npm|
|@babel/plugin-transform-computed-properties|7.8.3|间接依赖|npm|
|decode-uri-component|0.2.0|间接依赖|npm|
|killable|1.0.1|间接依赖|npm|
|bytes|1.0.0|间接依赖|npm|
|sass|1.26.3|间接依赖|npm|
|@babel/plugin-proposal-async-generator-functions|7.8.3|间接依赖|npm|
|electron-to-chromium|1.3.395|间接依赖|npm|
|convert-source-map|1.7.0|间接依赖|npm|
|acorn|7.1.1|间接依赖|npm|
|err-code|1.1.2|间接依赖|npm|
|pkg-up|2.0.0|间接依赖|npm|
|@babel/plugin-syntax-top-level-await|7.8.3|间接依赖|npm|
|istanbul-lib-report|2.0.8|间接依赖|npm|
|@babel/plugin-transform-shorthand-properties|7.8.3|间接依赖|npm|
|define-property|2.0.2|间接依赖|npm|
|regenerator-runtime|0.9.6|间接依赖|npm|
|color-name|1.1.4|间接依赖|npm|
|create-hmac|1.1.7|间接依赖|npm|
|@babel/plugin-transform-modules-amd|7.9.0|间接依赖|npm|
|minipass-pipeline|1.2.2|间接依赖|npm|
|tough-cookie|2.5.0|间接依赖|npm|
|github.com/flynn-archive/go-shlex|v0.0.0-20150515145356-3f9db97f8568|直接依赖|go|
|karma|4.3.0|直接依赖|npm|
|syntax-error|1.4.0|间接依赖|npm|
|@babel/plugin-proposal-optional-chaining|7.9.0|间接依赖|npm|
|is-wsl|2.1.1|间接依赖|npm|
|@babel/plugin-proposal-object-rest-spread|7.9.0|间接依赖|npm|
|postcss-discard-empty|4.0.1|间接依赖|npm|
|@babel/helper-get-function-arity|7.8.3|间接依赖|npm|
|callsite|1.0.0|间接依赖|npm|
|lru-cache|2.7.3|间接依赖|npm|
|import-cwd|2.1.0|间接依赖|npm|
|component-flatten|1.0.1|间接依赖|npm|
|commander|2.20.3|间接依赖|npm|
|@angular-devkit/build-optimizer|0.901.0|间接依赖|npm|
|github.com/gobwas/glob|v0.2.3|直接依赖|go|
|color|3.1.2|间接依赖|npm|
|sha.js|2.4.11|间接依赖|npm|
|github.com/prometheus/common|v0.44.0|间接依赖|go|
|uniq|1.0.1|间接依赖|npm|
|methods|0.0.1|间接依赖|npm|
|dashdash|1.14.1|间接依赖|npm|
|@webassemblyjs/wasm-opt|1.8.5|间接依赖|npm|
|tree-kill|1.2.2|间接依赖|npm|
|center-align|0.1.3|间接依赖|npm|
|co|3.1.0|间接依赖|npm|
|levenary|1.1.1|间接依赖|npm|
|arr-flatten|1.1.0|直接依赖|npm|
|@babel/helper-compilation-targets|7.8.7|间接依赖|npm|
|postcss-svgo|4.0.2|间接依赖|npm|
|forwarded|0.1.2|间接依赖|npm|
|xml2js|0.4.23|间接依赖|npm|
|vary|1.1.2|间接依赖|npm|
|multicast-dns-service-types|1.1.0|间接依赖|npm|
|minipass-json-stream|1.0.1|间接依赖|npm|
|npm-registry-fetch|8.0.0|间接依赖|npm|
|shallow-clone|3.0.1|间接依赖|npm|
|angular-in-memory-web-api|0.10.0|直接依赖|npm|
|babel-plugin-dynamic-import-node|2.3.0|间接依赖|npm|
|promise-inflight|1.0.1|间接依赖|npm|
|string.prototype.trimright|2.1.2|间接依赖|npm|
|form-data|2.3.3|间接依赖|npm|
|accepts|1.3.7|间接依赖|npm|
|event-stream|3.3.5|间接依赖|npm|
|esprima-fb|3001.1.0-dev-harmony-fb|间接依赖|npm|
|micromatch|3.1.10|间接依赖|npm|
|window-size|0.1.4|间接依赖|npm|
|github.com/certifi/gocertifi|v0.0.0-20210507211836-431795d63e8d|间接依赖|go|
|http-errors|1.7.2|间接依赖|npm|
|browserify-cipher|1.0.1|间接依赖|npm|
|readdirp|3.3.0|间接依赖|npm|
|@angular/core|9.1.0|直接依赖|npm|
|strip-eof|1.0.0|间接依赖|npm|
|proxy-addr|2.0.6|间接依赖|npm|
|webpack-log|2.0.0|间接依赖|npm|
|is-docker|2.0.0|间接依赖|npm|
|array-unique|0.3.2|间接依赖|npm|
|strip-ansi|3.0.1|间接依赖|npm|
|path-is-absolute|1.0.1|直接依赖|npm|
|opn|5.5.0|间接依赖|npm|
|pinkie|2.0.4|间接依赖|npm|
|@babel/core|7.9.0|间接依赖|npm|
|app-root-path|2.2.1|间接依赖|npm|
|destroy|1.0.4|间接依赖|npm|
|@webassemblyjs/wast-printer|1.8.5|间接依赖|npm|
|ansi-colors|3.2.4|间接依赖|npm|
|@types/jasmine|3.5.10|间接依赖|npm|
|get-uri|0.1.4|间接依赖|npm|
|content-disposition|0.5.3|间接依赖|npm|
|mem|4.3.0|直接依赖|npm|
|unicode-canonical-property-names-ecmascript|1.0.4|间接依赖|npm|
|dns-equal|1.0.0|间接依赖|npm|
|path-dirname|1.0.2|间接依赖|npm|
|css-selector-tokenizer|0.7.2|间接依赖|npm|
|debug|4.1.1|间接依赖|npm|
|@babel/helper-builder-binary-assignment-operator-visitor|7.8.3|间接依赖|npm|
|brace-expansion|1.1.11|直接依赖|npm|
|is-path-cwd|2.2.0|间接依赖|npm|
|webpack-merge|4.2.2|间接依赖|npm|
|win-fork|1.1.1|间接依赖|npm|
|retry|0.12.0|间接依赖|npm|
|css-tree|1.0.0-alpha.37|间接依赖|npm|
|concat-stream|1.6.2|间接依赖|npm|
|readdir-scoped-modules|1.1.0|间接依赖|npm|
|component-build|1.2.2|间接依赖|npm|
|@babel/plugin-syntax-json-strings|7.8.3|间接依赖|npm|
|rfdc|1.1.4|间接依赖|npm|
|postcss-discard-comments|4.0.2|间接依赖|npm|
|github.com/alecthomas/kong|v0.8.0|直接依赖|go|
|@schematics/update|0.901.0|间接依赖|npm|
|path-browserify|0.0.1|间接依赖|npm|
|unpipe|1.0.0|间接依赖|npm|
|is-arguments|1.0.4|间接依赖|npm|
|http-proxy-agent|0.2.7|间接依赖|npm|
|ee-first|1.1.1|间接依赖|npm|
|querystring|0.2.0|间接依赖|npm|
|qs|0.6.5|间接依赖|npm|
|less|3.11.1|间接依赖|npm|
|github.com/rcrowley/go-metrics|v0.0.0-20201227073835-cf1acfcdf475|直接依赖|go|
|lcid|1.0.0|间接依赖|npm|
|@webassemblyjs/helper-module-context|1.8.5|间接依赖|npm|
|estraverse|4.3.0|间接依赖|npm|
|is-callable|1.1.5|间接依赖|npm|
|pause-stream|0.0.11|间接依赖|npm|
|isbinaryfile|3.0.3|间接依赖|npm|
|serve-static|1.14.1|间接依赖|npm|
|is-interactive|1.0.0|间接依赖|npm|
|github.com/prometheus/client_golang|v1.16.0|直接依赖|go|
|github.com/jackpal/go-nat-pmp|v1.0.2|直接依赖|go|
|source-map-resolve|0.5.3|间接依赖|npm|
|batch|0.6.1|间接依赖|npm|
|nanomatch|1.2.13|间接依赖|npm|
|stylus|0.54.7|间接依赖|npm|
|github.com/ccding/go-stun|v0.1.4|直接依赖|go|
|github.com/d4l3k/messagediff|v1.2.1|直接依赖|go|
|protractor|5.4.3|直接依赖|npm|
|autoprefixer-core|3.1.2|间接依赖|npm|
|@babel/plugin-proposal-dynamic-import|7.8.3|间接依赖|npm|
|socket.io-parser|3.2.0|间接依赖|npm|
|emitter-component|1.0.0|间接依赖|npm|
|private|0.1.8|间接依赖|npm|
|ora|4.0.3|间接依赖|npm|
|postcss-normalize-timing-functions|4.0.2|间接依赖|npm|
|natives|1.1.6|直接依赖|npm|
|tslint|5.18.0|直接依赖|npm|
|browserify-aes|1.2.0|间接依赖|npm|
|parse-asn1|5.1.5|间接依赖|npm|
|is-number|7.0.0|间接依赖|npm|
|websocket-driver|0.7.3|直接依赖|npm|
|@babel/plugin-syntax-optional-catch-binding|7.8.3|间接依赖|npm|
|@babel/helper-optimise-call-expression|7.8.3|间接依赖|npm|
|@babel/helper-function-name|7.8.3|间接依赖|npm|
|require-directory|2.1.1|直接依赖|npm|
|send|0.17.1|间接依赖|npm|
|is-module|1.0.0|间接依赖|npm|
|@angular/animations|9.1.0|直接依赖|npm|
|tempfile|0.1.3|间接依赖|npm|
|setprototypeof|1.1.1|间接依赖|npm|
|decamelize|1.2.0|间接依赖|npm|
|query-string|4.3.4|直接依赖|npm|
|ent|2.2.0|间接依赖|npm|
|nan|2.14.0|直接依赖|npm|
|aria-query|3.0.0|间接依赖|npm|
|jsonfile|4.0.0|间接依赖|npm|
|rgb-regex|1.0.1|间接依赖|npm|
|source-map|0.1.43|间接依赖|npm|
|yallist|4.0.0|间接依赖|npm|
|coa|2.0.2|间接依赖|npm|
|postcss-minify-params|4.0.2|间接依赖|npm|
|github.com/maxbrunsfeld/counterfeiter/v6|v6.5.0|直接依赖|go|
|@babel/plugin-transform-template-literals|7.8.3|间接依赖|npm|
|stream-browserify|2.0.2|间接依赖|npm|
|@angular-devkit/build-angular|0.901.0|直接依赖|npm|
|component-require2|1.1.1|间接依赖|npm|
|map-cache|0.2.2|间接依赖|npm|
|strip-bom|3.0.0|间接依赖|npm|
|make-fetch-happen|8.0.4|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|jsbn|0.1.1|间接依赖|npm|
|is-binary-path|2.1.0|间接依赖|npm|
|default-require-extensions|2.0.0|间接依赖|npm|
|ajv-keywords|3.4.1|间接依赖|npm|
|to-fast-properties|2.0.0|间接依赖|npm|
|@webassemblyjs/wast-parser|1.8.5|间接依赖|npm|
|https-proxy-agent|0.3.6|间接依赖|npm|
|globby|7.1.1|间接依赖|npm|
|create-ecdh|4.0.3|间接依赖|npm|
|safe-regex|1.1.0|间接依赖|npm|
|pumpify|1.5.1|间接依赖|npm|
|ajv-errors|1.0.1|直接依赖|npm|
|ip|1.1.5|间接依赖|npm|
|wcwidth|1.0.1|间接依赖|npm|
|github.com/maruel/panicparse/v2|v2.3.1|直接依赖|go|
|invert-kv|1.0.0|间接依赖|npm|
|globals|11.12.0|间接依赖|npm|
|uniqs|2.0.0|间接依赖|npm|
|component-builder|1.2.1|间接依赖|npm|
|elliptic|6.5.2|间接依赖|npm|
|block-stream|0.0.9|间接依赖|npm|
|y18n|3.2.1|间接依赖|npm|
|ignore-walk|3.0.3|间接依赖|npm|
|snapdragon|0.8.2|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|JSONStream|0.8.4|间接依赖|npm|
|performance-now|2.1.0|间接依赖|npm|
|unglob|0.1.2|间接依赖|npm|
|minipass-sized|1.0.3|间接依赖|npm|
|postcss-minify-font-values|4.0.2|间接依赖|npm|
|typescript|3.7.5|间接依赖|npm|
|use|3.1.1|间接依赖|npm|
|@types/selenium-webdriver|3.0.17|间接依赖|npm|
|jszip|3.3.0|间接依赖|npm|
|@webassemblyjs/helper-api-error|1.8.5|间接依赖|npm|
|number-is-nan|1.0.1|直接依赖|npm|
|pump|3.0.0|间接依赖|npm|
|selfsigned|1.10.7|间接依赖|npm|
|caniuse-lite|1.0.30001038|间接依赖|npm|
|decompress|0.2.5|间接依赖|npm|
|abbrev|1.1.1|间接依赖|npm|
|external-editor|3.1.0|间接依赖|npm|
|set-blocking|2.0.0|直接依赖|npm|
|buffer-from|1.1.1|间接依赖|npm|
|@babel/plugin-transform-object-super|7.8.3|间接依赖|npm|
|figgy-pudding|3.5.2|直接依赖|npm|
|console-browserify|1.2.0|间接依赖|npm|
|google.golang.org/protobuf|v1.31.0|直接依赖|go|
|semver|2.3.2|间接依赖|npm|
|@babel/plugin-transform-named-capturing-groups-regex|7.8.3|间接依赖|npm|
|json3|3.3.3|间接依赖|npm|
|md5.js|1.3.5|间接依赖|npm|
|path-parse|1.0.6|间接依赖|npm|
|@angular/cdk|9.2.0|直接依赖|npm|
|async|2.6.3|间接依赖|npm|
|canonical-path|1.0.0|间接依赖|npm|
|ieee754|1.1.13|间接依赖|npm|
|@angular-devkit/core|9.1.0|间接依赖|npm|
|@babel/plugin-transform-member-expression-literals|7.8.3|间接依赖|npm|
|lodash|4.17.15|间接依赖|npm|
|unicode-match-property-value-ecmascript|1.2.0|间接依赖|npm|
|npm-packlist|2.1.1|间接依赖|npm|
|del|4.1.1|间接依赖|npm|
|log4js|4.5.1|间接依赖|npm|
|pascalcase|0.1.1|间接依赖|npm|
|node-releases|1.1.53|间接依赖|npm|
|duplexify|3.7.1|间接依赖|npm|
|enhanced-resolve|4.1.1|间接依赖|npm|
|urix|0.1.0|间接依赖|npm|
|minizlib|2.1.0|间接依赖|npm|
|webpack-dev-middleware|3.7.2|间接依赖|npm|
|@webassemblyjs/ast|1.8.5|间接依赖|npm|
|vm-browserify|1.1.2|间接依赖|npm|
|loose-envify|1.4.0|间接依赖|npm|
|validate-npm-package-license|3.0.4|间接依赖|npm|
|@types/jasminewd2|2.0.8|直接依赖|npm|
|golang.org/x/net|v0.14.0|直接依赖|go|
|regexpu-core|4.7.0|间接依赖|npm|
|signal-exit|3.0.3|间接依赖|npm|
|@babel/preset-modules|0.1.3|间接依赖|npm|
|events|3.1.0|间接依赖|npm|
|inflight|1.0.6|直接依赖|npm|
|@webassemblyjs/floating-point-hex-parser|1.8.5|间接依赖|npm|
|ts-node|8.3.0|直接依赖|npm|
|buffer-indexof|1.1.1|间接依赖|npm|
|mississippi|3.0.0|直接依赖|npm|
|infer-owner|1.0.4|间接依赖|npm|
|is-date-object|1.0.2|间接依赖|npm|
|loader-runner|2.4.0|间接依赖|npm|
|acorn-walk|7.1.1|间接依赖|npm|
|github.com/go-ldap/ldap/v3|v3.4.5|直接依赖|go|
|merge-source-map|1.1.0|间接依赖|npm|
|cli-spinners|2.2.0|间接依赖|npm|
|@angular/platform-browser|9.1.0|直接依赖|npm|
|@babel/plugin-transform-literals|7.8.3|间接依赖|npm|
|getpass|0.1.7|间接依赖|npm|
|which-module|2.0.0|直接依赖|npm|
|postcss-unique-selectors|4.0.1|间接依赖|npm|
|original|1.0.2|间接依赖|npm|
|is-color-stop|1.1.0|间接依赖|npm|
|unique-slug|2.0.2|间接依赖|npm|
|end-of-stream|1.4.4|间接依赖|npm|
|@babel/helper-member-expression-to-functions|7.8.3|间接依赖|npm|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|@babel/plugin-transform-modules-commonjs|7.9.0|间接依赖|npm|
|es-abstract|1.17.5|间接依赖|npm|
|@types/webpack-sources|0.1.7|间接依赖|npm|
|date-format|2.1.0|间接依赖|npm|
|@babel/plugin-transform-typeof-symbol|7.8.4|间接依赖|npm|
|component-search2|1.1.1|间接依赖|npm|
|useragent|2.3.0|间接依赖|npm|
|@angular/language-service|9.1.0|直接依赖|npm|
|@webassemblyjs/helper-buffer|1.8.5|间接依赖|npm|
|custom-event|1.0.1|间接依赖|npm|
|@babel/plugin-transform-async-to-generator|7.8.3|间接依赖|npm|
|cyclist|1.0.1|间接依赖|npm|
|get-stream|4.1.0|间接依赖|npm|
|snapdragon-node|2.1.1|直接依赖|npm|
|loglevel|1.6.7|间接依赖|npm|
|http-proxy-middleware|0.19.1|间接依赖|npm|
|path-to-regexp|0.1.7|间接依赖|npm|
|default-gateway|4.2.0|间接依赖|npm|
|extsprintf|1.3.0|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|fastparse|1.1.2|间接依赖|npm|
|ext-name|1.0.1|间接依赖|npm|
|regenerate-unicode-properties|8.2.0|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|tsutils|2.29.0|间接依赖|npm|
|resolve-from|3.0.0|间接依赖|npm|
|handle-thing|2.0.1|间接依赖|npm|
|is-descriptor|0.1.6|间接依赖|npm|
|postcss-ordered-values|4.1.2|间接依赖|npm|
|github.com/greatroar/blobloom|v0.7.2|直接依赖|go|
|cssauron|1.4.0|间接依赖|npm|
|proxy-agent|1.1.1|间接依赖|npm|
|oauth-sign|0.9.0|间接依赖|npm|
|@babel/plugin-proposal-json-strings|7.8.3|间接依赖|npm|
|@babel/helper-remap-async-to-generator|7.8.3|间接依赖|npm|
|image-size|0.5.5|间接依赖|npm|
|is-obj|2.0.0|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|component-inherit|0.0.3|间接依赖|npm|
|through|2.3.8|间接依赖|npm|
|cssesc|3.0.0|间接依赖|npm|
|find-cache-dir|3.3.1|间接依赖|npm|
|engine.io-parser|2.1.3|间接依赖|npm|
|@types/glob|7.1.1|间接依赖|npm|
|sockjs|0.3.19|间接依赖|npm|
|@webassemblyjs/wasm-gen|1.8.5|间接依赖|npm|
|delayed-stream|1.0.0|间接依赖|npm|
|negotiator|0.6.2|间接依赖|npm|
|strict-uri-encode|1.1.0|间接依赖|npm|
|http-cache-semantics|4.1.0|间接依赖|npm|
|punycode|2.1.1|间接依赖|npm|
|is-accessor-descriptor|0.1.6|间接依赖|npm|
|internal-ip|4.3.0|间接依赖|npm|
|path-is-inside|1.0.2|间接依赖|npm|
|deep-equal|1.1.1|间接依赖|npm|
|resolve-url|0.2.1|间接依赖|npm|
|http-deceiver|1.2.7|间接依赖|npm|
|split|1.0.1|间接依赖|npm|
|parseuri|0.0.5|间接依赖|npm|
|sockjs-client|1.4.0|间接依赖|npm|
|yargs-parser|11.1.1|直接依赖|npm|
|dependency-graph|0.7.2|间接依赖|npm|
|@babel/plugin-transform-new-target|7.8.3|间接依赖|npm|
|extend-shallow|3.0.2|间接依赖|npm|
|acorn-node|1.8.2|间接依赖|npm|
|verror|1.10.0|间接依赖|npm|
|socks|1.1.10|间接依赖|npm|
|postcss-discard-duplicates|4.0.2|间接依赖|npm|
|p-is-promise|2.1.0|间接依赖|npm|
|github.com/sasha-s/go-deadlock|v0.3.1|直接依赖|go|
|npm-bundled|1.1.1|间接依赖|npm|
|stream-http|2.8.3|间接依赖|npm|
|postcss-reduce-initial|4.0.3|间接依赖|npm|
|object-assign|0.3.1|间接依赖|npm|
|@babel/traverse|7.9.0|间接依赖|npm|
|async-each|1.0.3|直接依赖|npm|
|fileset|2.0.3|间接依赖|npm|
|typedarray|0.0.6|间接依赖|npm|
|cipher-base|1.0.4|间接依赖|npm|
|@babel/plugin-syntax-async-generators|7.8.4|间接依赖|npm|
|statuses|1.5.0|间接依赖|npm|
|blob|0.0.5|间接依赖|npm|
|@xtuc/long|4.2.2|间接依赖|npm|
|github.com/prometheus/procfs|v0.11.1|间接依赖|go|
|caseless|0.12.0|间接依赖|npm|
|@babel/plugin-transform-modules-systemjs|7.9.0|间接依赖|npm|
|hsla-regex|1.0.0|间接依赖|npm|
|npm-package-arg|8.0.1|间接依赖|npm|
|@babel/helper-split-export-declaration|7.8.3|间接依赖|npm|
|resolve|1.15.1|间接依赖|npm|
|@babel/generator|7.9.3|间接依赖|npm|
|semver-intersect|1.4.0|间接依赖|npm|
|@babel/helper-hoist-variables|7.8.3|间接依赖|npm|
|@babel/helper-module-transforms|7.9.0|间接依赖|npm|
|@babel/helper-define-map|7.8.3|间接依赖|npm|
|longest|1.0.1|间接依赖|npm|
|parse5|5.1.1|间接依赖|npm|
|find-up|2.1.0|间接依赖|npm|
|prepend-http|1.0.4|直接依赖|npm|
|@babel/helper-simple-access|7.8.3|间接依赖|npm|
|spdy-transport|3.0.0|间接依赖|npm|
|import-from|2.1.0|间接依赖|npm|
|wrap-ansi|2.1.0|直接依赖|npm|
|lodash.clonedeep|4.5.0|间接依赖|npm|
|source-map-support|0.5.16|间接依赖|npm|
|select-hose|2.0.0|间接依赖|npm|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|portfinder|1.0.25|间接依赖|npm|
|postcss-normalize-unicode|4.0.1|间接依赖|npm|
|void-elements|2.0.1|间接依赖|npm|
|defaults|1.0.3|间接依赖|npm|
|github.com/cpuguy83/go-md2man/v2|v2.0.2|间接依赖|go|
|@babel/plugin-transform-parameters|7.9.3|间接依赖|npm|
|range-parser|1.2.1|间接依赖|npm|
|mamacro|0.0.3|间接依赖|npm|
|npm-pick-manifest|6.0.0|间接依赖|npm|
|array-flatten|2.1.2|间接依赖|npm|
|postcss-reduce-transforms|4.0.2|间接依赖|npm|
|argparse|1.0.10|间接依赖|npm|
|uuid|1.4.2|间接依赖|npm|
|chardet|0.7.0|间接依赖|npm|
|eslint-scope|4.0.3|间接依赖|npm|
|@babel/plugin-transform-block-scoping|7.8.3|间接依赖|npm|
|util-promisify|2.1.0|间接依赖|npm|
|aproba|1.2.0|间接依赖|npm|
|webpack|4.42.0|间接依赖|npm|
|is-directory|0.3.1|间接依赖|npm|
|html-entities|1.2.1|间接依赖|npm|
|cli-width|2.2.0|间接依赖|npm|
|is-typedarray|1.0.0|间接依赖|npm|
|camelcase|1.2.1|间接依赖|npm|
|html-escaper|2.0.2|间接依赖|npm|
|toidentifier|1.0.0|间接依赖|npm|
|yn|3.1.1|间接依赖|npm|
|jstransform|3.0.0|间接依赖|npm|
|sigmund|1.0.1|间接依赖|npm|
|unquote|1.1.1|间接依赖|npm|
|duplexer|0.1.1|间接依赖|npm|
|@babel/plugin-transform-duplicate-keys|7.8.3|间接依赖|npm|
|is-extendable|0.1.1|间接依赖|npm|
|normalize-package-data|2.5.0|间接依赖|npm|
|es6-module-jstransform|0.1.4|间接依赖|npm|
|browserify-zlib|0.2.0|间接依赖|npm|
|sane|0.8.1|间接依赖|npm|
|symbol-observable|1.2.0|间接依赖|npm|
|parseqs|0.0.5|间接依赖|npm|
|minipass-flush|1.0.5|间接依赖|npm|
|has-ansi|2.0.0|直接依赖|npm|
|mimic-fn|2.1.0|间接依赖|npm|
|component-consoler|2.0.0|间接依赖|npm|
|core-js|3.6.4|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|stable|0.1.8|间接依赖|npm|
|locate-path|2.0.0|间接依赖|npm|
|type-is|1.6.18|间接依赖|npm|
|imurmurhash|0.1.4|间接依赖|npm|
|@babel/parser|7.9.4|间接依赖|npm|
|alphanum-sort|1.0.2|间接依赖|npm|
|speed-measure-webpack-plugin|1.3.1|间接依赖|npm|
|@babel/helper-module-imports|7.8.3|间接依赖|npm|
|to-arraybuffer|1.0.1|间接依赖|npm|
|is-path-inside|2.1.0|间接依赖|npm|
|ansi-html|0.0.7|间接依赖|npm|
|clean-stack|2.2.0|间接依赖|npm|
|github.com/petermattis/goid|v0.0.0-20230904192822-1876fd5063bc|间接依赖|go|
|p-try|1.0.0|间接依赖|npm|
|@ngtools/webpack|9.1.0|间接依赖|npm|
|istanbul-lib-coverage|3.0.0|间接依赖|npm|
|builtin-modules|1.1.1|间接依赖|npm|
|formidable|1.0.14|间接依赖|npm|
|normalize-range|0.1.2|间接依赖|npm|
|cosmiconfig|5.2.1|间接依赖|npm|
|cssnano-preset-default|4.0.7|间接依赖|npm|
|browserslist|4.11.1|间接依赖|npm|
|underscore.string|2.3.3|间接依赖|npm|
|socket.io|2.1.1|间接依赖|npm|
|get-stdin|0.1.0|间接依赖|npm|
|object-inspect|1.7.0|间接依赖|npm|
|bonjour|3.5.0|间接依赖|npm|
|istanbul-api|2.1.6|间接依赖|npm|
|is-plain-object|2.0.4|间接依赖|npm|
|babel-loader|8.0.6|间接依赖|npm|
|chownr|1.1.4|间接依赖|npm|
|@babel/plugin-transform-unicode-regex|7.8.3|间接依赖|npm|
|jsonparse|0.0.5|间接依赖|npm|
|hsl-regex|1.0.0|间接依赖|npm|
|@babel/types|7.9.0|间接依赖|npm|
|when|3.6.4|间接依赖|npm|
|array-union|1.0.2|间接依赖|npm|
|postcss-selector-parser|6.0.2|间接依赖|npm|
|axobject-query|2.0.2|间接依赖|npm|
|@types/source-list-map|0.1.2|间接依赖|npm|
|import-fresh|2.0.0|间接依赖|npm|
|ecc-jsbn|0.1.2|间接依赖|npm|
|read-package-tree|5.3.1|间接依赖|npm|
|object.assign|4.1.0|间接依赖|npm|
|validate-npm-package-name|3.0.0|间接依赖|npm|
|cssnano-util-same-parent|4.0.1|间接依赖|npm|
|@types/q|1.5.2|间接依赖|npm|
|istanbul-lib-source-maps|3.0.6|间接依赖|npm|
|remove-trailing-separator|1.1.0|直接依赖|npm|
|superagent|0.17.0|间接依赖|npm|
|ast-types-flow|0.0.7|间接依赖|npm|
|from|0.1.7|间接依赖|npm|
|cp|0.1.1|间接依赖|npm|
|p-limit|1.3.0|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|is-lambda|1.0.1|间接依赖|npm|
|zone.js|0.10.3|直接依赖|npm|
|humanize-ms|1.2.1|间接依赖|npm|
|base64-js|1.3.1|间接依赖|npm|
|har-schema|2.0.0|间接依赖|npm|
|rimraf|2.7.1|间接依赖|npm|
|ignore|3.3.10|间接依赖|npm|
|commondir|1.0.1|间接依赖|npm|
|string-width|2.1.1|间接依赖|npm|
|postcss-loader|3.0.0|间接依赖|npm|
|compression|1.7.4|间接依赖|npm|
|object.pick|1.3.0|间接依赖|npm|
|combined-stream|1.0.8|间接依赖|npm|
|jest-worker|25.1.0|间接依赖|npm|
|golang.org/x/crypto|v0.12.0|直接依赖|go|
|http-proxy|1.18.0|间接依赖|npm|
|es-to-primitive|1.2.1|间接依赖|npm|
|json-schema|0.2.3|间接依赖|npm|
|glob|3.2.11|间接依赖|npm|
|multicast-dns|6.2.3|间接依赖|npm|
|golang.org/x/text|v0.13.0|直接依赖|go|
|npm-install-checks|4.0.0|间接依赖|npm|
|dns-packet|1.3.1|间接依赖|npm|
|is-glob|4.0.1|间接依赖|npm|
|bluebird|3.7.2|间接依赖|npm|
|@babel/helpers|7.9.2|间接依赖|npm|
|css-color-names|0.0.4|间接依赖|npm|
|@babel/runtime|7.9.2|间接依赖|npm|
|pinkie-promise|2.0.1|直接依赖|npm|
|github.com/google/pprof|v0.0.0-20230901174712-0191c66da455|间接依赖|go|
|leven|3.1.0|间接依赖|npm|
|codelyzer|5.2.2|直接依赖|npm|
|@babel/plugin-syntax-object-rest-spread|7.8.3|间接依赖|npm|
|sort-keys|1.1.2|直接依赖|npm|
|@babel/plugin-proposal-numeric-separator|7.8.3|间接依赖|npm|
|github.com/power-devops/perfstat|v0.0.0-20221212215047-62379fc7944b|间接依赖|go|
|to-array|0.1.4|间接依赖|npm|
|jsprim|1.4.1|间接依赖|npm|
|postcss-normalize-string|4.0.2|间接依赖|npm|
|spdy|4.0.1|间接依赖|npm|
|raw-body|1.3.4|间接依赖|npm|
|@types/color-name|1.1.1|直接依赖|npm|
|watch|0.10.0|间接依赖|npm|
|emojis-list|3.0.0|间接依赖|npm|
|figures|3.2.0|间接依赖|npm|
|cssnano-util-get-match|4.0.0|间接依赖|npm|
|buffer-alloc-unsafe|1.1.0|间接依赖|npm|
|github.com/AudriusButkevicius/recli|v0.0.7-0.20220911121932-d000ce8fbf0f|直接依赖|go|
|github.com/prometheus/client_model|v0.4.0|间接依赖|go|
|@yarnpkg/lockfile|1.1.0|间接依赖|npm|
|pac-proxy-agent|0.2.0|间接依赖|npm|
|connect|3.7.0|间接依赖|npm|
|github.com/gogo/protobuf|v1.3.2|直接依赖|go|
|hex-color-regex|1.1.0|间接依赖|npm|
|define-properties|1.1.3|间接依赖|npm|
|on-headers|1.0.2|间接依赖|npm|
|is-path-in-cwd|2.1.0|间接依赖|npm|
|@schematics/angular|9.1.0|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|randomfill|1.0.4|间接依赖|npm|
|github.com/onsi/ginkgo/v2|v2.12.0|间接依赖|go|
|@angular/common|9.1.0|直接依赖|npm|
|json-parse-even-better-errors|2.2.0|间接依赖|npm|
|read-package-json|2.1.1|间接依赖|npm|
|cookie-signature|1.0.6|间接依赖|npm|
|base64id|1.0.0|间接依赖|npm|
|util.promisify|1.0.1|间接依赖|npm|
|autoprefixer|9.7.4|间接依赖|npm|
|postcss-normalize-charset|4.0.1|间接依赖|npm|
|on-finished|2.3.0|间接依赖|npm|
|setimmediate|1.0.5|间接依赖|npm|
|@babel/plugin-proposal-unicode-property-regex|7.8.8|间接依赖|npm|
|asap|2.0.6|间接依赖|npm|
|cssnano|4.1.10|间接依赖|npm|
|@babel/plugin-transform-destructuring|7.8.8|间接依赖|npm|
|tty-browserify|0.0.0|间接依赖|npm|
|github.com/chmduquesne/rollinghash|v4.0.0+incompatible|直接依赖|go|
|@babel/plugin-syntax-optional-chaining|7.8.3|间接依赖|npm|
|postcss-minify-selectors|4.0.2|间接依赖|npm|
|mini-css-extract-plugin|0.9.0|间接依赖|npm|
|unicode-match-property-ecmascript|1.0.4|间接依赖|npm|
|lodash.uniq|4.5.0|间接依赖|npm|
|@babel/plugin-transform-reserved-words|7.8.3|间接依赖|npm|
|write-to|1.1.1|间接依赖|npm|
|xmlbuilder|11.0.1|间接依赖|npm|
|color-string|1.5.3|间接依赖|npm|
|@angular/cli|9.1.0|直接依赖|npm|
|mixin-deep|1.3.2|间接依赖|npm|
|parseurl|1.3.3|间接依赖|npm|
|stylehacks|4.0.3|间接依赖|npm|
|component-validator|1.1.1|间接依赖|npm|
|sourcemap-codec|1.4.8|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|rollup|2.1.0|间接依赖|npm|
|sax|1.2.4|间接依赖|npm|
|github.com/syndtr/goleveldb|v1.0.1-0.20220721030215-126854af5e6d|直接依赖|go|
|socket.io-client|2.1.1|间接依赖|npm|
|isobject|3.0.1|间接依赖|npm|
|webpack-subresource-integrity|1.4.0|间接依赖|npm|
|assert-plus|1.0.0|间接依赖|npm|
|dir-glob|2.2.2|间接依赖|npm|
|@npmcli/installed-package-contents|1.0.5|间接依赖|npm|
|pify|4.0.1|间接依赖|npm|
|iconv-lite|0.4.24|间接依赖|npm|
|dom-serialize|2.2.1|间接依赖|npm|
|walker|1.0.7|间接依赖|npm|
|caller-callsite|2.0.0|间接依赖|npm|
|ext-list|0.2.0|间接依赖|npm|
|@types/node|12.12.34|间接依赖|npm|
|postcss-normalize-repeat-style|4.0.2|间接依赖|npm|
|fsevents|2.1.2|间接依赖|npm|
|diffie-hellman|5.0.3|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|create-hash|1.2.0|间接依赖|npm|
|read-package-json-fast|1.1.3|间接依赖|npm|
|@webassemblyjs/ieee754|1.8.5|间接依赖|npm|
|aws4|1.9.1|间接依赖|npm|
|tweetnacl|0.14.5|间接依赖|npm|
|component-watcher|1.0.3|间接依赖|npm|
|github.com/oschwald/maxminddb-golang|v1.12.0|间接依赖|go|
|url-parse|1.4.7|间接依赖|npm|
|reflect-metadata|0.1.13|间接依赖|npm|
|querystringify|2.1.1|间接依赖|npm|
|resolve-cwd|2.0.0|间接依赖|npm|
|upath|1.2.0|直接依赖|npm|
|requires|1.0.2|间接依赖|npm|
|npm-normalize-package-bin|1.0.1|间接依赖|npm|
|@angular/material|9.2.0|直接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|onetime|5.1.0|间接依赖|npm|
|psl|1.8.0|间接依赖|npm|
|glob-parent|3.1.0|间接依赖|npm|
|css-select-base-adapter|0.1.1|间接依赖|npm|
|@types/minimatch|3.0.3|间接依赖|npm|
|core-util-is|1.0.2|间接依赖|npm|
|@webassemblyjs/helper-code-frame|1.8.5|间接依赖|npm|
|cliui|2.1.0|间接依赖|npm|
|repeat-element|1.1.3|直接依赖|npm|
|crypto-browserify|3.12.0|间接依赖|npm|
|require-main-filename|1.0.1|直接依赖|npm|
|@babel/helper-annotate-as-pure|7.8.3|间接依赖|npm|
|process|0.11.10|间接依赖|npm|
|stream-to-array|1.0.0|间接依赖|npm|
|process-nextick-args|2.0.1|间接依赖|npm|
|spdx-expression-parse|3.0.0|间接依赖|npm|
|set-immediate-shim|1.0.1|间接依赖|npm|
|@babel/plugin-syntax-dynamic-import|7.8.3|间接依赖|npm|
|fstream|0.1.31|间接依赖|npm|
|postcss-import|12.0.1|间接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|regjsgen|0.5.1|间接依赖|npm|
|mime|1.2.5|间接依赖|npm|
|builder-autoprefixer|1.0.4|间接依赖|npm|
|@webassemblyjs/utf8|1.8.5|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|github.com/oschwald/geoip2-golang|v1.9.0|直接依赖|go|
|github.com/hashicorp/golang-lru/v2|v2.0.6|直接依赖|go|
|xtend|4.0.2|间接依赖|npm|
|builtins|1.0.3|间接依赖|npm|
|object-component|0.0.3|间接依赖|npm|
|component-remotes|1.2.0|间接依赖|npm|
|karma-source-map-support|1.4.0|间接依赖|npm|
|unique-filename|1.1.1|间接依赖|npm|
|component-downloader|1.2.0|间接依赖|npm|
|amdefine|1.0.1|间接依赖|npm|
|@babel/plugin-transform-exponentiation-operator|7.8.3|间接依赖|npm|
|picomatch|2.2.2|间接依赖|npm|
|@npmcli/ci-detect|1.2.0|间接依赖|npm|
|ansi-escapes|4.3.1|间接依赖|npm|
|fs-extra|4.0.2|间接依赖|npm|
|body-parser|1.19.0|间接依赖|npm|
|ws|6.2.1|间接依赖|npm|
|fs-write-stream-atomic|1.0.10|间接依赖|npm|
|github.com/shirou/gopsutil/v3|v3.23.8|直接依赖|go|
|assert|1.5.0|间接依赖|npm|
|socket.io-adapter|1.1.2|间接依赖|npm|
|ipaddr.js|1.9.1|间接依赖|npm|
|github.com/syncthing/notify|v0.0.0-20210616190510-c6b7342338d2|直接依赖|go|
|neo-async|2.6.1|间接依赖|npm|
|minipass-collect|1.0.2|间接依赖|npm|
|clone|2.1.2|间接依赖|npm|
|json-stringify-safe|5.0.1|间接依赖|npm|
|file-loader|6.0.0|间接依赖|npm|
|github.com/quic-go/quic-go|v0.38.1|直接依赖|go|
|assign-symbols|1.0.0|间接依赖|npm|
|webpack-dev-server|3.10.3|间接依赖|npm|
|restore-cursor|3.1.0|间接依赖|npm|
|chanel|2.2.0|间接依赖|npm|
|@webassemblyjs/helper-wasm-bytecode|1.8.5|间接依赖|npm|
|@angular-devkit/build-webpack|0.901.0|间接依赖|npm|
|has-binary2|1.0.3|间接依赖|npm|
|pacote|11.1.4|间接依赖|npm|
|ajv|6.12.0|间接依赖|npm|
|emoji-regex|8.0.0|直接依赖|npm|
|util|0.11.1|间接依赖|npm|
|esutils|2.0.3|间接依赖|npm|
|github.com/golang/snappy|v0.0.4|间接依赖|go|
|chalk|2.4.2|间接依赖|npm|
|stylus-loader|3.0.2|间接依赖|npm|
|request|2.88.2|间接依赖|npm|
|copy-concurrently|1.0.5|间接依赖|npm|
|readable-stream|2.3.7|间接依赖|npm|
|github.com/thejerf/suture/v4|v4.0.2|直接依赖|go|
|@angular/forms|9.1.0|直接依赖|npm|
|@babel/helper-replace-supers|7.8.6|间接依赖|npm|
|postcss-colormin|4.0.3|间接依赖|npm|
|json-parse-better-errors|1.0.2|间接依赖|npm|
|randombytes|2.1.0|间接依赖|npm|
|arraybuffer.slice|0.0.7|间接依赖|npm|
|normalize-url|3.3.0|间接依赖|npm|
|reduce-component|1.0.1|间接依赖|npm|
|base64-arraybuffer|0.1.5|间接依赖|npm|
|backo2|1.0.2|间接依赖|npm|
|bn.js|4.11.8|间接依赖|npm|
|gensync|1.0.0-beta.1|间接依赖|npm|
|@babel/plugin-proposal-optional-catch-binding|7.8.3|间接依赖|npm|
|cli-cursor|3.1.0|间接依赖|npm|
|lazy-cache|1.0.4|间接依赖|npm|
|@babel/helper-wrap-function|7.8.3|间接依赖|npm|
|big.js|5.2.2|间接依赖|npm|
|istanbul-reports|2.2.7|间接依赖|npm|
|caniuse-db|1.0.30001038|间接依赖|npm|
|@jsdevtools/coverage-istanbul-loader|3.0.3|间接依赖|npm|
|@babel/plugin-transform-regenerator|7.8.7|间接依赖|npm|
|is-regex|1.0.5|间接依赖|npm|
|@babel/template|7.8.6|间接依赖|npm|
|@webassemblyjs/wasm-edit|1.8.5|间接依赖|npm|
|dns-txt|2.0.2|间接依赖|npm|
|memory-fs|0.5.0|间接依赖|npm|
|fs.realpath|1.0.0|直接依赖|npm|
|component-pin|1.0.5|间接依赖|npm|
|tar|0.1.20|间接依赖|npm|
|@babel/plugin-syntax-nullish-coalescing-operator|7.8.3|间接依赖|npm|
|semver-dsl|1.0.1|间接依赖|npm|
|engine.io|3.2.1|间接依赖|npm|
|move-concurrently|1.0.1|间接依赖|npm|
|https-browserify|1.0.0|间接依赖|npm|
|is-buffer|1.1.6|间接依赖|npm|
|follow-redirects|1.11.0|间接依赖|npm|
|@babel/plugin-transform-modules-umd|7.9.0|间接依赖|npm|
|unicode-property-aliases-ecmascript|1.1.0|间接依赖|npm|
|extglob|2.0.4|间接依赖|npm|
|yeast|0.1.2|间接依赖|npm|
|@babel/plugin-transform-block-scoped-functions|7.8.3|间接依赖|npm|
|compressible|2.0.18|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|which|1.3.1|间接依赖|npm|
|escape-html|1.0.3|间接依赖|npm|
|mime-db|1.43.0|间接依赖|npm|
|iferr|0.1.5|间接依赖|npm|
|serialize-javascript|2.1.2|间接依赖|npm|
|github.com/jackpal/gateway|v1.0.10|直接依赖|go|
|html-comment-regex|1.1.2|间接依赖|npm|
|golang.org/x/mod|v0.12.0|间接依赖|go|
|merge-descriptors|1.0.1|间接依赖|npm|
|chartjs-color-string|0.6.0|间接依赖|npm|
|blocking-proxy|1.0.1|间接依赖|npm|
|css-parse|2.0.0|间接依赖|npm|
|golang.org/x/tools|v0.12.1-0.20230815132531-74c255bcf846|直接依赖|go|
|@babel/helper-validator-identifier|7.9.0|间接依赖|npm|
|get-caller-file|1.0.3|直接依赖|npm|
|github.com/getsentry/raven-go|v0.2.0|直接依赖|go|
|isarray|0.0.1|间接依赖|npm|
|compare-versions|3.6.0|间接依赖|npm|
|component-outdated2|1.0.5|间接依赖|npm|
|@babel/plugin-transform-dotall-regex|7.8.3|间接依赖|npm|
|import-local|2.0.0|间接依赖|npm|
|postcss-discard-overridden|4.0.1|间接依赖|npm|
|engine.io-client|3.2.1|间接依赖|npm|
|tslib|1.11.1|间接依赖|npm|
|@angular/compiler-cli|9.1.0|直接依赖|npm|
|har-validator|5.1.3|间接依赖|npm|
|promise-retry|1.1.1|间接依赖|npm|
|ini|1.3.5|间接依赖|npm|
|to-regex|3.0.2|间接依赖|npm|
|xmlhttprequest-ssl|1.5.5|间接依赖|npm|
|css-declaration-sorter|4.0.1|间接依赖|npm|
|node-forge|0.9.0|间接依赖|npm|
|postcss|2.2.6|间接依赖|npm|
|balanced-match|1.0.0|间接依赖|npm|
|log-symbols|3.0.0|间接依赖|npm|
|github.com/go-task/slim-sprig|v0.0.0-20230315185526-52ccab3ef572|间接依赖|go|
|better-assert|1.0.2|间接依赖|npm|
|browserify-rsa|4.0.1|间接依赖|npm|
|cross-spawn|6.0.5|间接依赖|npm|
|hpack.js|2.1.6|间接依赖|npm|
|caller-path|2.0.0|间接依赖|npm|
|from2|2.3.0|间接依赖|npm|
|es6-promise|4.2.8|间接依赖|npm|
|indexof|0.0.1|间接依赖|npm|
|os-tmpdir|1.0.2|间接依赖|npm|
|kind-of|3.2.2|间接依赖|npm|
|css|2.2.4|间接依赖|npm|
|@angular/flex-layout|9.0.0-beta.29|直接依赖|npm|
|github.com/go-asn1-ber/asn1-ber|v1.5.4|间接依赖|go|
|error-ex|1.3.2|间接依赖|npm|
|is-fullwidth-code-point|2.0.0|间接依赖|npm|
|github.com/urfave/cli|v1.22.14|直接依赖|go|
|postcss-minify-gradients|4.0.2|间接依赖|npm|
|is-absolute-url|2.1.0|间接依赖|npm|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/pierrec/lz4/v4|v4.1.18|直接依赖|go|
|ultron|1.1.1|直接依赖|npm|
|istanbul-lib-instrument|4.0.1|间接依赖|npm|
|vendors|1.0.4|间接依赖|npm|
|stream-shift|1.0.1|间接依赖|npm|
|os-locale|1.4.0|间接依赖|npm|
|@angular/compiler|9.1.0|直接依赖|npm|
|@angular/platform-browser-dynamic|9.1.0|直接依赖|npm|
|damerau-levenshtein|1.0.6|间接依赖|npm|
|webpack-sources|1.4.3|间接依赖|npm|
|requires-port|1.0.0|间接依赖|npm|
|object-keys|1.1.1|间接依赖|npm|
|@babel/plugin-syntax-numeric-separator|7.8.3|间接依赖|npm|
|lodash.memoize|4.1.2|间接依赖|npm|
|buffer-alloc|1.2.0|间接依赖|npm|
|cacache|15.0.0|间接依赖|npm|
|json5|2.1.2|间接依赖|npm|
|github.com/kballard/go-shellquote|v0.0.0-20180428030007-95032a82bc51|直接依赖|go|
|base62|0.1.1|间接依赖|npm|
|mute-stream|0.0.8|间接依赖|npm|
|indent-string|4.0.0|间接依赖|npm|
|regjsparser|0.6.4|间接依赖|npm|
|timsort|0.3.0|间接依赖|npm|
|through2|2.0.5|间接依赖|npm|
|github.com/calmh/xdr|v1.1.0|直接依赖|go|
|utils-merge|1.0.1|间接依赖|npm|
|bindings|1.5.0|直接依赖|npm|
|golang.org/x/time|v0.3.0|直接依赖|go|
|inquirer|7.1.0|间接依赖|npm|
|jasmine-core|3.5.0|间接依赖|npm|
|parse-json|4.0.0|间接依赖|npm|
|lie|3.3.0|间接依赖|npm|
|github.com/quic-go/qtls-go1-20|v0.3.3|间接依赖|go|
|component-ls|2.1.0|间接依赖|npm|
|worker-farm|1.7.0|直接依赖|npm|
|github.com/julienschmidt/httprouter|v1.3.0|直接依赖|go|
|ip-regex|2.1.0|间接依赖|npm|
|media-typer|0.3.0|间接依赖|npm|
|postcss-convert-values|4.0.1|间接依赖|npm|
|object.values|1.1.1|间接依赖|npm|
|chrome-trace-event|1.0.2|间接依赖|npm|
|posix-character-classes|0.1.1|间接依赖|npm|
|finalhandler|1.1.2|间接依赖|npm|
|streamroller|1.0.6|间接依赖|npm|
|map-stream|0.0.7|间接依赖|npm|
|jasminewd2|2.2.0|间接依赖|npm|
|serve-index|1.9.1|间接依赖|npm|
|sass-loader|8.0.2|间接依赖|npm|
|adm-zip|0.4.14|间接依赖|npm|
|append-transform|1.0.0|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)