# ethereumbook/ethereumbook安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1693331408335818752.svg)](https://www.murphysec.com/console/report/1693331407442432000/1693331408335818752)

仓库描述：Mastering Ethereum, by Andreas M. Antonopoulos, Gavin Wood

仓库地址：[https://github.com/ethereumbook/ethereumbook](https://github.com/ethereumbook/ethereumbook)

| star：18264 | watch：581 | fork：4714 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-19 14:54:40 | 许可证：NOASSERTION |
| 最近检测时间：2023-08-21 02:38:43 | 组件总数：954 | 漏洞总数：114 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|crypto-js<3.2.1 存在不安全的随机性漏洞|使用具有密码学弱点缺陷的PRNG|[MPS-1z0k-uh5s](https://www.oscs1024.com/hd/MPS-1z0k-uh5s)|CVE-2020-36732|高危|
|url-parse 安全漏洞||[MPS-2018-11050](https://www.oscs1024.com/hd/MPS-2018-11050)|CVE-2018-3774|严重|
|webpack-dev-server 信息泄露漏洞|未授权敏感信息泄露|[MPS-2018-12609](https://www.oscs1024.com/hd/MPS-2018-12609)|CVE-2018-14732|高危|
|ethereumjs-vm 安全漏洞|缓冲区溢出|[MPS-2018-14622](https://www.oscs1024.com/hd/MPS-2018-14622)|CVE-2018-19183|高危|
|React XSS 漏洞|XSS|[MPS-2018-16483](https://www.oscs1024.com/hd/MPS-2018-16483)|CVE-2018-6341|中危|
|Joyent Joyent Node.js ssri 模块拒绝服务漏洞|拒绝服务|[MPS-2018-2692](https://www.oscs1024.com/hd/MPS-2018-2692)|CVE-2018-7651|中危|
|Hoek 访问控制错误漏洞|MAID|[MPS-2018-3882](https://www.oscs1024.com/hd/MPS-2018-3882)|CVE-2018-3728|高危|
|Http-signature 安全漏洞|密码学签名的验证不恰当|[MPS-2018-6996](https://www.oscs1024.com/hd/MPS-2018-6996)|CVE-2017-16005|高危|
|sshpk 安全漏洞|不正确的正则表达式|[MPS-2018-7302](https://www.oscs1024.com/hd/MPS-2018-7302)|CVE-2018-3737|高危|
|lodash node 拒绝服务漏洞|拒绝服务|[MPS-2018-7315](https://www.oscs1024.com/hd/MPS-2018-7315)|CVE-2018-3721|中危|
|Eran Hammer cryptiles  不安全的随机性漏洞|信息熵不充分|[MPS-2018-9401](https://www.oscs1024.com/hd/MPS-2018-9401)|CVE-2018-1000620|严重|
|Joyent Node.js macaddress模块命令注入漏洞|OS命令注入|[MPS-2018-9416](https://www.oscs1024.com/hd/MPS-2018-9416)|CVE-2018-13797|严重|
|lodash 存在拒绝服务漏洞|拒绝服务|[MPS-2019-1228](https://www.oscs1024.com/hd/MPS-2019-1228)|CVE-2018-16487|中危|
|extend module [*, 2.0.2)、[3.0.0, 3.0.2) 原型污染漏洞|注入|[MPS-2019-1232](https://www.oscs1024.com/hd/MPS-2019-1232)|CVE-2018-16492|严重|
|serialize-javascript < 2.1.2 跨站脚本漏洞|XSS|[MPS-2019-15864](https://www.oscs1024.com/hd/MPS-2019-15864)|CVE-2019-16769|中危|
|node-tar [, 2.2.2)、[3.0.0, 4.4.2)  任意文件覆盖漏洞|在文件访问前对链接解析不恰当（链接跟随）|[MPS-2019-4705](https://www.oscs1024.com/hd/MPS-2019-4705)|CVE-2018-20834|高危|
|fstream <1.0.12 链接解析错误漏洞|在文件访问前对链接解析不恰当（链接跟随）|[MPS-2019-7423](https://www.oscs1024.com/hd/MPS-2019-7423)|CVE-2019-13173|高危|
|lodash <4.7.11 正则表达式拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2019-8123](https://www.oscs1024.com/hd/MPS-2019-8123)|CVE-2019-1010266|中危|
|lodash 原型污染漏洞|拒绝服务|[MPS-2019-8636](https://www.oscs1024.com/hd/MPS-2019-8636)|CVE-2019-10744|严重|
|SockJS <0.3.20 异常处理不当漏洞|对异常条件的处理不恰当|[MPS-2020-10001](https://www.oscs1024.com/hd/MPS-2020-10001)|CVE-2020-7693|中危|
|Ajv v6.12.2 输入验证错误漏洞|MAID|[MPS-2020-10525](https://www.oscs1024.com/hd/MPS-2020-10525)|CVE-2020-15366|中危|
|node-forge <0.10.0 对象属性的不当控制修改漏洞|动态确定对象属性修改的控制不恰当|[MPS-2020-12281](https://www.oscs1024.com/hd/MPS-2020-12281)|CVE-2020-7720|高危|
|npm node-fetch 不加限制的资源分配漏洞|不加限制或调节的资源分配|[MPS-2020-12719](https://www.oscs1024.com/hd/MPS-2020-12719)|CVE-2020-15168|中危|
|trim <0.0.3 存在正则表达式拒绝服务漏洞|拒绝服务|[MPS-2020-14926](https://www.oscs1024.com/hd/MPS-2020-14926)|CVE-2020-7753|高危|
|lodash <4.17.15 原型污染漏洞|原型污染|[MPS-2020-15679](https://www.oscs1024.com/hd/MPS-2020-15679)|CVE-2020-8203|高危|
|Mhart Stringstream < 0.0.6 缓冲区错误漏洞|越界读取|[MPS-2020-16658](https://www.oscs1024.com/hd/MPS-2020-16658)|CVE-2018-21270|中危|
|Mout deepFillIn 代码问题漏洞|拒绝服务|[MPS-2020-17290](https://www.oscs1024.com/hd/MPS-2020-17290)|CVE-2020-7792|高危|
|npm url-parse 输入验证错误漏洞|对数据真实性的验证不充分|[MPS-2020-1742](https://www.oscs1024.com/hd/MPS-2020-1742)|CVE-2020-8124|中危|
|Yargs Y18n 输入原型污染漏洞|动态确定对象属性修改的控制不恰当|[MPS-2020-17543](https://www.oscs1024.com/hd/MPS-2020-17543)|CVE-2020-7774|严重|
|Mikaelbr Node-notifier 操作系统命令注入漏洞|OS命令注入|[MPS-2020-17637](https://www.oscs1024.com/hd/MPS-2020-17637)|CVE-2020-7789|中危|
|minimist 原型污染漏洞|原型污染|[MPS-2020-3516](https://www.oscs1024.com/hd/MPS-2020-3516)|CVE-2020-7598|中危|
|thenify 小于3.3.1 版本任意代码执行漏洞|OS命令注入|[MPS-2020-36505](https://www.oscs1024.com/hd/MPS-2020-36505)|CVE-2020-7677|严重|
|yargs-parser 原型污染漏洞|特权定义了不安全动作|[MPS-2020-4006](https://www.oscs1024.com/hd/MPS-2020-4006)|CVE-2020-7608|中危|
|decompress package 路径遍历漏洞|路径遍历|[MPS-2020-6640](https://www.oscs1024.com/hd/MPS-2020-6640)|CVE-2020-12265|严重|
|serialize-javascript <3.1.0 任意代码执行漏洞|反序列化|[MPS-2020-7976](https://www.oscs1024.com/hd/MPS-2020-7976)|CVE-2020-7660|高危|
|websocket-extensions<0.1.4 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2020-8041](https://www.oscs1024.com/hd/MPS-2020-8041)|CVE-2020-7662|高危|
|websocket-extensions 拒绝服务漏洞|拒绝服务|[MPS-2020-8042](https://www.oscs1024.com/hd/MPS-2020-8042)|CVE-2020-7663|高危|
|Elliptic package 签名伪造漏洞|整数溢出或环绕|[MPS-2020-8202](https://www.oscs1024.com/hd/MPS-2020-8202)|CVE-2020-13822|高危|
|chownr package竞争条件问题漏洞|检查时间与使用时间(TOCTOU)的竞争条件|[MPS-2020-8858](https://www.oscs1024.com/hd/MPS-2020-8858)|CVE-2017-18869|低危|
|url-parse <1.5.2 开放重定向漏洞|跨站重定向|[MPS-2021-11194](https://www.oscs1024.com/hd/MPS-2021-11194)|CVE-2021-3664|中危|
|Indutny Elliptic 加密问题漏洞|密码算法不安全|[MPS-2021-1176](https://www.oscs1024.com/hd/MPS-2021-1176)|CVE-2020-28498|中危|
|ansi-html <0.0.8 DoS 漏洞|拒绝服务|[MPS-2021-17628](https://www.oscs1024.com/hd/MPS-2021-17628)|CVE-2021-23424|高危|
|url-parse  < 1.5.0 输入验证不当漏洞|相对路径遍历|[MPS-2021-2265](https://www.oscs1024.com/hd/MPS-2021-2265)|CVE-2021-27515|中危|
|lodash 拒绝服务漏洞|拒绝服务|[MPS-2021-2574](https://www.oscs1024.com/hd/MPS-2021-2574)|CVE-2020-28500|中危|
|lodash 命令注入漏洞|代码注入|[MPS-2021-2638](https://www.oscs1024.com/hd/MPS-2021-2638)|CVE-2021-23337|高危|
|Npm Node-tar 后置链接漏洞||[MPS-2021-28486](https://www.oscs1024.com/hd/MPS-2021-28486)|CVE-2021-37701|高危|
|Npm Node-tar 后置链接漏洞||[MPS-2021-28488](https://www.oscs1024.com/hd/MPS-2021-28488)|CVE-2021-37712|高危|
|node-tar 路径遍历漏洞|路径遍历|[MPS-2021-28489](https://www.oscs1024.com/hd/MPS-2021-28489)|CVE-2021-37713|高危|
|Sindre Sorhus is-svg 拒绝服务漏洞|拒绝服务|[MPS-2021-3031](https://www.oscs1024.com/hd/MPS-2021-3031)|CVE-2021-28092|高危|
|nth-check 正则表达式拒绝服务漏洞|ReDoS|[MPS-2021-31847](https://www.oscs1024.com/hd/MPS-2021-31847)|CVE-2021-3803|高危|
|Ruy Adorno hosted-git-info 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-3400](https://www.oscs1024.com/hd/MPS-2021-3400)|CVE-2021-23362|中危|
|Async 原型污染漏洞|原型污染|[MPS-2021-34434](https://www.oscs1024.com/hd/MPS-2021-34434)|CVE-2021-43138|高危|
|json-schema 安全漏洞|原型污染|[MPS-2021-34478](https://www.oscs1024.com/hd/MPS-2021-34478)|CVE-2021-3918|严重|
|org.webjars.bower:underscore 代码注入漏洞|代码注入|[MPS-2021-3658](https://www.oscs1024.com/hd/MPS-2021-3658)|CVE-2021-23358|高危|
|braces <2.3.1 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-3692](https://www.oscs1024.com/hd/MPS-2021-3692)|CVE-2018-1109|中危|
|minimist 安全漏洞|原型污染|[MPS-2021-38405](https://www.oscs1024.com/hd/MPS-2021-38405)|CVE-2021-44906|严重|
|postcss 存在正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-5409](https://www.oscs1024.com/hd/MPS-2021-5409)|CVE-2021-23382|中危|
|npm path-parse 安全漏洞|拒绝服务|[MPS-2021-6165](https://www.oscs1024.com/hd/MPS-2021-6165)|CVE-2021-23343|高危|
|dns-packet 存在信息泄露漏洞|资源初始化缺失|[MPS-2021-7013](https://www.oscs1024.com/hd/MPS-2021-7013)|CVE-2021-23386|中危|
|ws 存在拒绝服务漏洞||[MPS-2021-7109](https://www.oscs1024.com/hd/MPS-2021-7109)|CVE-2021-32640|中危|
|trim-newlines 存在拒绝服务漏洞|拒绝服务|[MPS-2021-7398](https://www.oscs1024.com/hd/MPS-2021-7398)|CVE-2021-33623|高危|
|glob-parent < 5.1.2 存在拒绝服务漏洞|拒绝服务|[MPS-2021-7827](https://www.oscs1024.com/hd/MPS-2021-7827)|CVE-2020-28469|高危|
|Color-String < 1.5.5 存在正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-8683](https://www.oscs1024.com/hd/MPS-2021-8683)|CVE-2021-29060|中危|
|is-svg 存在正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-8684](https://www.oscs1024.com/hd/MPS-2021-8684)|CVE-2021-29059|高危|
|Digital Bazaar Forge 存在输入验证错误漏洞|跨站重定向|[MPS-2022-0421](https://www.oscs1024.com/hd/MPS-2022-0421)|CVE-2022-0122|中危|
|shelljs < 0.8.5 存在特权管理不恰当漏洞|权限管理不当|[MPS-2022-0508](https://www.oscs1024.com/hd/MPS-2022-0508)|CVE-2022-0144|高危|
|EventSource 信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-10212](https://www.oscs1024.com/hd/MPS-2022-10212)|CVE-2022-1650|严重|
|Moment.js 正则拒绝服务漏洞|拒绝服务|[MPS-2022-11159](https://www.oscs1024.com/hd/MPS-2022-11159)|CVE-2022-31129|高危|
|clean-css < 4.1.11 存在拒绝服务漏洞||[MPS-2022-12865](https://www.oscs1024.com/hd/MPS-2022-12865)||低危|
|mem  < 4.0.0 存在拒绝服务漏洞|拒绝服务|[MPS-2022-12990](https://www.oscs1024.com/hd/MPS-2022-12990)||中危|
|node-forge < 0.7.4 存在拒绝服务漏洞||[MPS-2022-13022](https://www.oscs1024.com/hd/MPS-2022-13022)||中危|
|querystringify < 2.0.0 存在输入验证不恰当漏洞|输入验证不恰当|[MPS-2022-13057](https://www.oscs1024.com/hd/MPS-2022-13057)||高危|
|crypto-js 存在信息熵不充分漏洞|信息熵不充分|[MPS-2022-13612](https://www.oscs1024.com/hd/MPS-2022-13612)||高危|
|ejs < 3.1.6 存在代码注入漏洞|代码注入|[MPS-2022-13642](https://www.oscs1024.com/hd/MPS-2022-13642)||中危|
|elliptic<6.5.2 存在定时攻击漏洞|竞争条件|[MPS-2022-13653](https://www.oscs1024.com/hd/MPS-2022-13653)||中危|
|http-proxy<1.18.1 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13767](https://www.oscs1024.com/hd/MPS-2022-13767)||中危|
|js-yaml 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13820](https://www.oscs1024.com/hd/MPS-2022-13820)||中危|
|js-yaml<3.13.1 存在代码注入漏洞|代码注入|[MPS-2022-13822](https://www.oscs1024.com/hd/MPS-2022-13822)||高危|
|lodash<4.17.20 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13841](https://www.oscs1024.com/hd/MPS-2022-13841)||高危|
|lodash<4.17.17 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13842](https://www.oscs1024.com/hd/MPS-2022-13842)||高危|
|macaddress<0.4.3 存在路径遍历漏洞|路径遍历|[MPS-2022-13851](https://www.oscs1024.com/hd/MPS-2022-13851)||中危|
|node-forge <1.0.0 存在原型污染漏洞|原型污染|[MPS-2022-13920](https://www.oscs1024.com/hd/MPS-2022-13920)||中危|
|uglify-js <3.14.3 正则表达式拒绝服务漏洞|ReDoS|[MPS-2022-14112](https://www.oscs1024.com/hd/MPS-2022-14112)||中危|
|vuetify 存在跨站脚本漏洞|XSS|[MPS-2022-14144](https://www.oscs1024.com/hd/MPS-2022-14144)||中危|
|webpack-bundle-analyzer<3.3.2 跨站脚本漏洞|XSS|[MPS-2022-14149](https://www.oscs1024.com/hd/MPS-2022-14149)||中危|
|node-fetch 信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-1461](https://www.oscs1024.com/hd/MPS-2022-1461)|CVE-2022-0235|中危|
|got 存在打开重定向漏洞|跨站重定向|[MPS-2022-19247](https://www.oscs1024.com/hd/MPS-2022-19247)|CVE-2022-33987|中危|
|simple-get 信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-2533](https://www.oscs1024.com/hd/MPS-2022-2533)|CVE-2022-0355|高危|
|url-parse 存在访问限制绕过漏洞|通过用户控制密钥绕过授权机制|[MPS-2022-3327](https://www.oscs1024.com/hd/MPS-2022-3327)|CVE-2022-0512|中危|
|node-forge 密码签名验证不当漏洞|密码学签名的验证不恰当|[MPS-2022-3738](https://www.oscs1024.com/hd/MPS-2022-3738)|CVE-2022-24771|高危|
|node-forge 密码签名验证不当漏洞|密码学签名的验证不恰当|[MPS-2022-3739](https://www.oscs1024.com/hd/MPS-2022-3739)|CVE-2022-24772|高危|
|node-forge 密码签名验证不当漏洞|密码学签名的验证不恰当|[MPS-2022-3740](https://www.oscs1024.com/hd/MPS-2022-3740)|CVE-2022-24773|中危|
|Moment.js 路径遍历漏洞|路径遍历|[MPS-2022-3752](https://www.oscs1024.com/hd/MPS-2022-3752)|CVE-2022-24785|中危|
|Express 中的 qs 模块存在原型污染漏洞|原型污染|[MPS-2022-3967](https://www.oscs1024.com/hd/MPS-2022-3967)|CVE-2022-24999|高危|
|url-parse <1.5.7 存在密钥授权绕过漏洞|通过用户控制密钥绕过授权机制|[MPS-2022-4297](https://www.oscs1024.com/hd/MPS-2022-4297)|CVE-2022-0639|中危|
|NPM url-parse授权绕过漏洞||[MPS-2022-4464](https://www.oscs1024.com/hd/MPS-2022-4464)|CVE-2022-0686|严重|
|Url-parse <1.5.9 存在输入验证不当漏洞||[MPS-2022-4474](https://www.oscs1024.com/hd/MPS-2022-4474)|CVE-2022-0691|严重|
|Mout 安全漏洞|原型污染|[MPS-2022-5050](https://www.oscs1024.com/hd/MPS-2022-5050)|CVE-2022-21213|高危|
|css-what 资源管理错误漏洞|ReDoS|[MPS-2022-5052](https://www.oscs1024.com/hd/MPS-2022-5052)|CVE-2022-21222|高危|
|http-cache-semantics 安全漏洞|ReDoS|[MPS-2022-5164](https://www.oscs1024.com/hd/MPS-2022-5164)|CVE-2022-25881|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|loader-utils 安全漏洞|不正确的正则表达式|[MPS-2022-53512](https://www.oscs1024.com/hd/MPS-2022-53512)|CVE-2022-37599|高危|
|loader-utils 安全漏洞|不正确的正则表达式|[MPS-2022-53516](https://www.oscs1024.com/hd/MPS-2022-53516)|CVE-2022-37603|高危|
|decode-uri-component <=0.2.0 存在输入验证不当漏洞|拒绝服务|[MPS-2022-56259](https://www.oscs1024.com/hd/MPS-2022-56259)|CVE-2022-38900|高危|
|vuetify中VCalendar存在XSS漏洞|XSS|[MPS-2022-56950](https://www.oscs1024.com/hd/MPS-2022-56950)||中危|
|minimatch 资源管理错误漏洞|拒绝服务|[MPS-2022-59845](https://www.oscs1024.com/hd/MPS-2022-59845)|CVE-2022-3517|高危|
|Tauri 原型污染漏洞|原型污染|[MPS-2022-65568](https://www.oscs1024.com/hd/MPS-2022-65568)|CVE-2022-46175|高危|
|Github ejs 安全漏洞|注入|[MPS-2022-8391](https://www.oscs1024.com/hd/MPS-2022-8391)|CVE-2022-29078|严重|
|hawk 资源管理错误漏洞|拒绝服务|[MPS-2022-8568](https://www.oscs1024.com/hd/MPS-2022-8568)|CVE-2022-29167|高危|
|cross-fetch 安全漏洞|授权检查错误|[MPS-2022-8877](https://www.oscs1024.com/hd/MPS-2022-8877)|CVE-2022-1365|中危|
|ejs 存在服务端模板注入漏洞|注入|[MPS-2023-10199](https://www.oscs1024.com/hd/MPS-2023-10199)|CVE-2023-29827|严重|
|tough-cookie 安全漏洞|原型污染|[MPS-2023-5130](https://www.oscs1024.com/hd/MPS-2023-5130)|CVE-2023-26136|严重|
|request SSRF防御绕过漏洞|SSRF|[MPS-2023-7722](https://www.oscs1024.com/hd/MPS-2023-7722)|CVE-2023-28155|中危|
|tough-cookie<4.1.3 存在原型污染漏洞|原型污染|[MPS-esyq-56vx](https://www.oscs1024.com/hd/MPS-esyq-56vx)||中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|eventsource|0.1.6|2.0.2|间接依赖|强烈建议修复|C:1|H:0|M:0|L:0|
|crypto-js|3.1.8|4.0.0|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|lodash|4.17.5|4.17.21|间接依赖|建议修复|C:1|H:4|M:3|L:0|
|ethereumjs-vm|2.3.5||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|sshpk|1.13.1|1.14.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|is-svg|2.1.0|4.3.0|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|node-forge|0.6.33|1.3.0|间接依赖|建议修复|C:0|H:3|M:4|L:0|
|ethereumjs-vm|2.3.3||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|minimatch|3.0.4|3.0.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|decompress|4.2.0|4.2.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|js-yaml|3.7.0|3.13.1|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|underscore|1.8.3|1.13.0-2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|ansi-html|0.0.7|0.0.8|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|decode-uri-component|0.2.0|0.2.1|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|glob-parent|2.0.0|6.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|css-what|2.1.0|5.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|nth-check|1.0.1|2.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tough-cookie|2.3.4|4.1.3|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|lodash|4.17.10|4.17.21|间接依赖|建议修复|C:1|H:4|M:3|L:0|
|json5|0.5.1|2.2.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|querystringify|0.0.4|2.0.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|decompress-tar|4.1.1||间接依赖|建议修复|C:1|H:0|M:0|L:0|
|loader-utils|1.1.0|3.2.1|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|qs|6.5.1|6.10.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|mout|0.11.1|1.2.4|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|http-signature|1.2.0||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|webpack-dev-server|2.9.7|3.1.11|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|ejs|2.5.7|3.1.7|间接依赖|建议修复|C:2|H:0|M:1|L:0|
|trim|0.0.1|0.0.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|fstream|1.0.11|1.0.12|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|elliptic|6.4.0|6.5.4|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|shelljs|0.7.8|0.8.5|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|hoek|4.2.0|5.0.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|express|4.16.2|4.17.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|serialize-javascript|1.4.0|3.1.0|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|hawk|6.0.2|9.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|websocket-extensions|0.1.3|0.1.4|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|url-parse|1.2.0|1.5.9|间接依赖|建议修复|C:3|H:0|M:5|L:0|
|tar|2.2.1|6.1.9|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|json-schema|0.2.3|0.4.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|simple-get|2.7.0|4.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|minimist|1.2.0|1.2.6|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|y18n|3.2.1|5.0.5|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|cryptiles|3.1.2|4.1.2|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|minimist|0.0.8|1.2.6|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|lodash|4.17.4|4.17.21|间接依赖|建议修复|C:1|H:4|M:4|L:0|
|path-parse|1.0.5|1.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|sockjs|0.3.18|0.3.20|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|trim-newlines|1.0.0|4.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tough-cookie|2.3.3|4.1.3|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|thenify|3.3.0|3.3.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|macaddress|0.2.8|0.4.3|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|extend|3.0.1|3.0.2|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|webpack-bundle-analyzer|2.9.1|3.3.2|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|yargs-parser|7.0.0|18.1.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|vuetify|0.17.6|2.6.10|直接依赖|可选修复|C:0|H:0|M:2|L:0|
|http-cache-semantics|3.8.1|4.1.1|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|color-string|0.3.0|1.5.5|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|5.4.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|ws|3.3.3|7.4.6|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|request|2.83.0||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|uglify-js|3.3.4|3.14.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|http-proxy|1.16.2|1.18.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|request|2.85.0||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|stringstream|0.0.5|0.0.6|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|ssri|5.0.0|8.0.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|braces|1.8.5|2.3.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|postcss|6.0.15|8.2.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|vue|2.5.13|2.5.17|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|node-fetch|1.7.3|3.2.10|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|mem|1.1.0|4.0.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|async|2.6.0|3.2.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|node-notifier|5.1.2|9.0.1|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|chownr|1.0.1|1.1.0|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|dns-packet|1.2.2|5.2.4|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|moment|2.22.0|2.29.4|直接依赖|可选修复|C:0|H:1|M:1|L:0|
|clean-css|4.1.9|4.1.11|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|got|7.1.0|12.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|ajv|5.5.2|6.12.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|hosted-git-info|2.5.0|3.0.8|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|ISC|68|Low|
|MIT|780|Low|
|LGPL-3.0|21|Medium|
|BSD-2-Clause|14|Low|
|BSD|4|Low|
|Apache-2.0|13|Low|
|MPL-2.0|12|Low|
|BSD-3-Clause|19|Low|
|自定义许可证|2|Low|
|BSD-like|2|Low|
|CC-BY-4.0|2|Low|
|Unlicense|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|sax|1.2.4|间接依赖|npm|
|graceful-fs|4.1.11|间接依赖|npm|
|fs-extra|0.30.0|间接依赖|npm|
|web3-net|1.0.0-beta.31|间接依赖|npm|
|dns-packet|1.2.2|间接依赖|npm|
|del|3.0.0|间接依赖|npm|
|babel-code-frame|6.26.0|间接依赖|npm|
|invert-kv|1.0.0|间接依赖|npm|
|get-caller-file|1.0.2|间接依赖|npm|
|mississippi|1.3.0|间接依赖|npm|
|array-find-index|1.0.2|间接依赖|npm|
|querystringify|0.0.4|间接依赖|npm|
|websocket-driver|0.7.0|间接依赖|npm|
|destroy|1.0.4|间接依赖|npm|
|brorand|1.1.0|间接依赖|npm|
|regjsparser|0.1.5|间接依赖|npm|
|big.js|3.2.0|间接依赖|npm|
|is-hex-prefixed|1.0.0|间接依赖|npm|
|http-https|1.0.0|间接依赖|npm|
|bonjour|3.5.0|间接依赖|npm|
|postcss-minify-font-values|1.0.5|间接依赖|npm|
|lru-cache|4.1.1|间接依赖|npm|
|camelcase-keys|2.1.0|间接依赖|npm|
|strip-hex-prefix|1.0.0|间接依赖|npm|
|p-map|1.2.0|间接依赖|npm|
|yargs|4.8.1|间接依赖|npm|
|resolve-from|3.0.0|间接依赖|npm|
|ejs|2.5.7|间接依赖|npm|
|babel-plugin-syntax-async-generators|6.13.0|间接依赖|npm|
|co|4.6.0|间接依赖|npm|
|pinkie-promise|2.0.1|直接依赖|npm|
|ethereumjs-util|4.5.0|间接依赖|npm|
|currently-unhandled|0.4.1|间接依赖|npm|
|postcss|6.0.15|间接依赖|npm|
|boom|4.3.1|间接依赖|npm|
|trim-newlines|1.0.0|间接依赖|npm|
|babel-helper-explode-assignable-expression|6.24.1|间接依赖|npm|
|babel-plugin-transform-async-to-generator|6.24.1|间接依赖|npm|
|typedarray|0.0.6|间接依赖|npm|
|esutils|2.0.2|间接依赖|npm|
|babel-plugin-transform-es2015-arrow-functions|6.22.0|间接依赖|npm|
|util|0.10.3|间接依赖|npm|
|os-locale|2.1.0|间接依赖|npm|
|postcss-discard-overridden|0.1.1|间接依赖|npm|
|hoek|4.2.1|间接依赖|npm|
|thunky|0.1.0|间接依赖|npm|
|babel-plugin-transform-es2015-modules-systemjs|6.24.1|间接依赖|npm|
|ethjs-abi|0.2.1|间接依赖|npm|
|babel-plugin-transform-es2015-modules-commonjs|6.26.0|间接依赖|npm|
|cacache|10.0.1|间接依赖|npm|
|postcss-svgo|2.1.6|间接依赖|npm|
|extsprintf|1.3.0|间接依赖|npm|
|babel-helper-call-delegate|6.24.1|间接依赖|npm|
|lodash|4.17.5|间接依赖|npm|
|imurmurhash|0.1.4|间接依赖|npm|
|path-is-inside|1.0.2|间接依赖|npm|
|has-flag|2.0.0|间接依赖|npm|
|pako|1.0.6|间接依赖|npm|
|ip|1.1.5|间接依赖|npm|
|babel-plugin-transform-strict-mode|6.24.1|间接依赖|npm|
|xmlhttprequest|1.8.0|间接依赖|npm|
|sshpk|1.13.1|间接依赖|npm|
|private|0.1.8|间接依赖|npm|
|loud-rejection|1.6.0|间接依赖|npm|
|tar-stream|1.5.5|间接依赖|npm|
|postcss-discard-comments|2.0.4|间接依赖|npm|
|babel-template|6.26.0|间接依赖|npm|
|arr-flatten|1.1.0|间接依赖|npm|
|cosmiconfig|2.2.2|间接依赖|npm|
|resumer|0.0.0|间接依赖|npm|
|node-libs-browser|2.1.0|间接依赖|npm|
|multicast-dns|6.2.1|间接依赖|npm|
|http-parser-js|0.4.9|间接依赖|npm|
|scrypt|6.0.3|间接依赖|npm|
|tape|4.8.0|间接依赖|npm|
|autoprefixer|7.2.4|间接依赖|npm|
|crypto-browserify|3.12.0|间接依赖|npm|
|web3|0.18.4|间接依赖|npm|
|ethereumjs-tx|1.3.4|间接依赖|npm|
|fstream|1.0.11|间接依赖|npm|
|onetime|2.0.1|间接依赖|npm|
|sockjs|0.3.18|间接依赖|npm|
|randomhex|0.1.5|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|hmac-drbg|1.0.1|间接依赖|npm|
|prettier|1.9.2|间接依赖|npm|
|arrify|1.0.1|间接依赖|npm|
|babel-plugin-transform-es2015-modules-amd|6.24.1|间接依赖|npm|
|hosted-git-info|2.5.0|间接依赖|npm|
|css-select|1.2.0|间接依赖|npm|
|is-directory|0.3.1|间接依赖|npm|
|which-module|2.0.0|间接依赖|npm|
|time-stamp|2.0.0|间接依赖|npm|
|ieee754|1.1.8|间接依赖|npm|
|stream-each|1.2.2|间接依赖|npm|
|extend|3.0.1|间接依赖|npm|
|dom-converter|0.1.4|间接依赖|npm|
|for-in|1.0.2|间接依赖|npm|
|globby|7.1.1|间接依赖|npm|
|loglevel|1.6.0|间接依赖|npm|
|postcss-modules-local-by-default|1.2.0|间接依赖|npm|
|ethereumjs-vm|2.3.3|间接依赖|npm|
|dashdash|1.14.1|间接依赖|npm|
|tough-cookie|2.3.4|间接依赖|npm|
|ansi-regex|2.1.1|间接依赖|npm|
|p-is-promise|1.1.0|间接依赖|npm|
|flatten|1.0.2|间接依赖|npm|
|uuid|2.0.3|间接依赖|npm|
|vue-router|3.0.1|直接依赖|npm|
|web3-core-helpers|1.0.0-beta.31|间接依赖|npm|
|stringstream|0.0.5|间接依赖|npm|
|normalize-path|2.1.1|间接依赖|npm|
|source-list-map|2.0.0|间接依赖|npm|
|js-base64|2.4.0|直接依赖|npm|
|mime-db|1.30.0|间接依赖|npm|
|postcss-merge-rules|2.1.2|间接依赖|npm|
|klaw|1.3.1|间接依赖|npm|
|base64-js|1.2.1|间接依赖|npm|
|solc|0.4.19|间接依赖|npm|
|npm-run-path|2.0.2|间接依赖|npm|
|domutils|1.5.1|间接依赖|npm|
|is-wsl|1.1.0|间接依赖|npm|
|babel-plugin-transform-es2015-classes|6.24.1|间接依赖|npm|
|cssesc|0.1.0|间接依赖|npm|
|ultron|1.1.1|间接依赖|npm|
|mout|0.11.1|间接依赖|npm|
|range-parser|1.2.0|间接依赖|npm|
|map-obj|1.0.1|间接依赖|npm|
|renderkid|2.0.1|间接依赖|npm|
|create-hmac|1.1.6|间接依赖|npm|
|js-sha3|0.5.5|间接依赖|npm|
|clone-response|1.0.2|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|depd|1.1.1|间接依赖|npm|
|babel-plugin-transform-es2015-spread|6.22.0|间接依赖|npm|
|optimize-css-assets-webpack-plugin|3.2.0|直接依赖|npm|
|select-hose|2.0.0|间接依赖|npm|
|scryptsy|1.2.1|间接依赖|npm|
|jsonfile|2.4.0|间接依赖|npm|
|es6-symbol|3.1.1|间接依赖|npm|
|binary-extensions|1.11.0|间接依赖|npm|
|array-includes|3.0.3|间接依赖|npm|
|whet.extend|0.9.9|间接依赖|npm|
|mimic-fn|1.1.0|间接依赖|npm|
|reduce-css-calc|1.3.0|间接依赖|npm|
|is-natural-number|4.0.1|间接依赖|npm|
|json5|0.5.1|间接依赖|npm|
|sshpk|1.14.1|间接依赖|npm|
|worker-farm|1.5.2|间接依赖|npm|
|lodash|4.17.10|间接依赖|npm|
|event-emitter|0.3.5|间接依赖|npm|
|babel-plugin-syntax-class-properties|6.13.0|间接依赖|npm|
|for-own|0.1.5|间接依赖|npm|
|find-up|1.1.2|间接依赖|npm|
|last-call-webpack-plugin|2.1.2|间接依赖|npm|
|uniqid|4.1.1|间接依赖|npm|
|cliui|2.1.0|间接依赖|npm|
|path-type|3.0.0|间接依赖|npm|
|repeating|2.0.1|间接依赖|npm|
|csso|2.3.2|间接依赖|npm|
|string_decoder|0.10.31|间接依赖|npm|
|html-webpack-plugin|2.30.1|直接依赖|npm|
|macaddress|0.2.8|间接依赖|npm|
|babel-plugin-syntax-decorators|6.13.0|间接依赖|npm|
|evp_bytestokey|1.0.3|间接依赖|npm|
|level-iterator-stream|1.3.1|间接依赖|npm|
|cookie-signature|1.0.6|间接依赖|npm|
|debug|2.6.9|间接依赖|npm|
|web3-core-subscriptions|1.0.0-beta.31|间接依赖|npm|
|babel-plugin-transform-es2015-computed-properties|6.24.1|间接依赖|npm|
|webpack-dev-middleware|1.12.2|间接依赖|npm|
|browserify-aes|1.1.1|间接依赖|npm|
|lower-case|1.1.4|间接依赖|npm|
|eventemitter3|1.2.0|间接依赖|npm|
|aproba|1.2.0|间接依赖|npm|
|q|1.5.1|间接依赖|npm|
|spdx-expression-parse|1.0.4|间接依赖|npm|
|postcss-convert-values|2.6.1|间接依赖|npm|
|postcss-import|11.0.0|直接依赖|npm|
|sockjs-client|1.1.4|间接依赖|npm|
|domhandler|2.1.0|间接依赖|npm|
|web3-core|1.0.0-beta.31|间接依赖|npm|
|object-inspect|1.5.0|间接依赖|npm|
|aws4|1.7.0|间接依赖|npm|
|is-object|1.0.1|间接依赖|npm|
|parse-glob|3.0.4|间接依赖|npm|
|tar.gz|1.0.7|间接依赖|npm|
|vendors|1.0.1|间接依赖|npm|
|xhr-request|1.1.0|间接依赖|npm|
|is-fullwidth-code-point|1.0.0|间接依赖|npm|
|brace-expansion|1.1.8|间接依赖|npm|
|web3-shh|1.0.0-beta.31|间接依赖|npm|
|jsprim|1.4.1|间接依赖|npm|
|keccak|1.4.0|直接依赖|npm|
|checkpoint-store|1.1.0|间接依赖|npm|
|randombytes|2.0.5|间接依赖|npm|
|drbg.js|1.0.1|间接依赖|npm|
|http-cache-semantics|3.8.1|间接依赖|npm|
|babel-plugin-transform-runtime|6.23.0|直接依赖|npm|
|babel-traverse|6.26.0|间接依赖|npm|
|abstract-leveldown|2.6.3|间接依赖|npm|
|anymatch|1.3.2|间接依赖|npm|
|tough-cookie|2.3.3|间接依赖|npm|
|create-ecdh|4.0.0|间接依赖|npm|
|vary|1.1.2|间接依赖|npm|
|resolve|1.4.0|间接依赖|npm|
|consolidate|0.14.5|间接依赖|npm|
|crypto-js|3.1.8|间接依赖|npm|
|babel-loader|7.1.2|直接依赖|npm|
|nan|2.9.2|间接依赖|npm|
|http-errors|1.6.2|间接依赖|npm|
|ethereumjs-block|1.7.0|间接依赖|npm|
|require-from-string|1.2.1|间接依赖|npm|
|decompress-targz|4.1.1|间接依赖|npm|
|serve-static|1.13.1|间接依赖|npm|
|nan|2.10.0|间接依赖|npm|
|for-each|0.3.2|间接依赖|npm|
|os-homedir|1.0.2|间接依赖|npm|
|center-align|0.1.3|间接依赖|npm|
|trim|0.0.1|间接依赖|npm|
|watchpack|1.4.0|间接依赖|npm|
|invariant|2.2.2|间接依赖|npm|
|dom-walk|0.1.1|间接依赖|npm|
|xml-char-classes|1.0.0|间接依赖|npm|
|babel-plugin-syntax-async-functions|6.13.0|间接依赖|npm|
|file-loader|1.1.6|直接依赖|npm|
|gzip-size|3.0.0|间接依赖|npm|
|md5.js|1.3.4|间接依赖|npm|
|process|0.11.10|间接依赖|npm|
|nano-json-stream-parser|0.1.2|间接依赖|npm|
|babel-plugin-transform-es2015-duplicate-keys|6.24.1|间接依赖|npm|
|css-what|2.1.0|间接依赖|npm|
|align-text|0.1.4|间接依赖|npm|
|base-x|1.1.0|间接依赖|npm|
|json-buffer|3.0.0|间接依赖|npm|
|url-parse-lax|1.0.0|间接依赖|npm|
|isarray|1.0.0|间接依赖|npm|
|date-now|0.1.4|间接依赖|npm|
|sha.js|2.4.11|间接依赖|npm|
|repeat-element|1.1.2|间接依赖|npm|
|mkdirp-promise|5.0.1|间接依赖|npm|
|has-symbol-support-x|1.4.2|间接依赖|npm|
|icss-replace-symbols|1.1.0|间接依赖|npm|
|create-hmac|1.1.7|间接依赖|npm|
|is-equal-shallow|0.1.3|间接依赖|npm|
|body-parser|1.18.2|间接依赖|npm|
|iconv-lite|0.4.19|间接依赖|npm|
|object-keys|1.0.11|间接依赖|npm|
|servify|0.1.12|间接依赖|npm|
|hdkey|0.7.1|间接依赖|npm|
|normalize-url|1.9.1|间接依赖|npm|
|strip-eof|1.0.0|间接依赖|npm|
|tunnel-agent|0.6.0|间接依赖|npm|
|keccakjs|0.2.1|间接依赖|npm|
|web3-providers-ws|1.0.0-beta.31|间接依赖|npm|
|defined|1.0.0|间接依赖|npm|
|find-up|2.1.0|间接依赖|npm|
|commander|2.12.2|间接依赖|npm|
|flush-write-stream|1.0.2|间接依赖|npm|
|media-typer|0.3.0|间接依赖|npm|
|glob|7.1.2|间接依赖|npm|
|killable|1.0.0|间接依赖|npm|
|babel-plugin-transform-regenerator|6.26.0|间接依赖|npm|
|process|0.5.2|间接依赖|npm|
|timers-browserify|2.0.4|间接依赖|npm|
|finalhandler|1.1.0|间接依赖|npm|
|randomfill|1.0.3|间接依赖|npm|
|safe-buffer|5.1.1|间接依赖|npm|
|cryptiles|3.1.2|间接依赖|npm|
|alphanum-sort|1.0.2|间接依赖|npm|
|commondir|1.0.1|间接依赖|npm|
|babel-messages|6.23.0|间接依赖|npm|
|cors|2.8.4|间接依赖|npm|
|is-path-cwd|1.0.0|间接依赖|npm|
|tape|4.9.0|间接依赖|npm|
|web3-eth-contract|1.0.0-beta.31|间接依赖|npm|
|argparse|1.0.9|间接依赖|npm|
|has|1.0.1|间接依赖|npm|
|create-hash|1.2.0|间接依赖|npm|
|browserify-zlib|0.2.0|间接依赖|npm|
|error-ex|1.3.1|间接依赖|npm|
|babel-helper-vue-jsx-merge-props|2.0.3|直接依赖|npm|
|underscore|1.8.3|间接依赖|npm|
|rustbn.js|0.1.1|间接依赖|npm|
|is-function|1.0.1|间接依赖|npm|
|mem|1.1.0|间接依赖|npm|
|yauzl|2.9.1|间接依赖|npm|
|expand-brackets|0.1.5|间接依赖|npm|
|ethereum-common|0.0.18|间接依赖|npm|
|eth-lib|0.1.27|间接依赖|npm|
|meow|3.7.0|间接依赖|npm|
|web3-providers-ipc|1.0.0-beta.31|间接依赖|npm|
|ignore|3.3.7|间接依赖|npm|
|hpack.js|2.1.6|间接依赖|npm|
|isurl|1.0.0|间接依赖|npm|
|read-pkg|2.0.0|间接依赖|npm|
|readable-stream|2.3.6|间接依赖|npm|
|pbkdf2|3.0.16|间接依赖|npm|
|number-to-bn|1.7.0|间接依赖|npm|
|pumpify|1.3.5|间接依赖|npm|
|babel-plugin-transform-es2015-function-name|6.24.1|间接依赖|npm|
|accepts|1.3.4|间接依赖|npm|
|tty-browserify|0.0.0|间接依赖|npm|
|on-headers|1.0.1|间接依赖|npm|
|ansi-html|0.0.7|间接依赖|npm|
|pseudomap|1.0.2|间接依赖|npm|
|mkdirp|0.5.1|间接依赖|npm|
|getpass|0.1.7|间接依赖|npm|
|bindings|1.3.0|间接依赖|npm|
|minimalistic-assert|1.0.1|间接依赖|npm|
|through2|2.0.3|间接依赖|npm|
|lodash|4.17.4|间接依赖|npm|
|combined-stream|1.0.6|间接依赖|npm|
|swarm-js|0.1.37|间接依赖|npm|
|asn1|0.2.3|间接依赖|npm|
|no-case|2.3.2|间接依赖|npm|
|parallel-transform|1.1.0|间接依赖|npm|
|whatwg-fetch|2.0.3|间接依赖|npm|
|regenerate|1.3.3|间接依赖|npm|
|isstream|0.1.2|间接依赖|npm|
|cli-cursor|2.1.0|间接依赖|npm|
|clean-css|4.1.9|间接依赖|npm|
|upper-case|1.1.3|间接依赖|npm|
|websocket|git://github.com/frozeman/WebSocket-Node.git#7004c39c42ac98875ab61126e5b4a925430f592c|间接依赖|npm|
|caniuse-lite|1.0.30000787|间接依赖|npm|
|to-arraybuffer|1.0.1|间接依赖|npm|
|querystring|0.2.0|间接依赖|npm|
|ltgt|2.2.1|间接依赖|npm|
|caniuse-api|1.6.1|间接依赖|npm|
|assert-plus|1.0.0|间接依赖|npm|
|into-stream|3.1.0|直接依赖|npm|
|core-js|2.5.3|间接依赖|npm|
|colors|1.1.2|间接依赖|npm|
|level-errors|1.0.5|间接依赖|npm|
|micromatch|2.3.11|间接依赖|npm|
|mime-db|1.33.0|间接依赖|npm|
|sha3|1.2.0|间接依赖|npm|
|pbkdf2|3.0.14|间接依赖|npm|
|p-limit|1.2.0|间接依赖|npm|
|window-size|0.2.0|间接依赖|npm|
|ee-first|1.1.1|间接依赖|npm|
|regjsgen|0.2.0|间接依赖|npm|
|babel-plugin-transform-es2015-typeof-symbol|6.23.0|间接依赖|npm|
|ethereumjs-vm|2.3.5|间接依赖|npm|
|ethjs-unit|0.1.6|间接依赖|npm|
|d|1.0.0|间接依赖|npm|
|pkg-dir|2.0.0|间接依赖|npm|
|ws|3.3.3|间接依赖|npm|
|reduce-function-call|1.0.2|间接依赖|npm|
|is-arrayish|0.2.1|间接依赖|npm|
|setprototypeof|1.1.0|间接依赖|npm|
|color-name|1.1.3|间接依赖|npm|
|indexof|0.0.1|间接依赖|npm|
|babel-runtime|6.26.0|间接依赖|npm|
|dotenv|5.0.0|直接依赖|npm|
|camelcase|1.2.1|间接依赖|npm|
|type-is|1.6.15|间接依赖|npm|
|string.prototype.trim|1.1.2|间接依赖|npm|
|get-stdin|4.0.1|间接依赖|npm|
|duplexer|0.1.1|间接依赖|npm|
|asn1.js|4.9.2|间接依赖|npm|
|openzeppelin-solidity|1.6.0|直接依赖|npm|
|compressible|2.0.12|间接依赖|npm|
|resolve|1.5.0|间接依赖|npm|
|ora|1.3.0|直接依赖|npm|
|json-stringify-safe|5.0.1|间接依赖|npm|
|babel-helper-replace-supers|6.24.1|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|concat-stream|1.6.0|间接依赖|npm|
|fast-deep-equal|1.1.0|间接依赖|npm|
|babel-plugin-transform-es2015-sticky-regex|6.24.1|间接依赖|npm|
|postcss-minify-params|1.2.2|间接依赖|npm|
|builtin-status-codes|3.0.0|间接依赖|npm|
|functional-red-black-tree|1.0.1|间接依赖|npm|
|postcss-ordered-values|2.2.3|间接依赖|npm|
|regex-cache|0.4.4|间接依赖|npm|
|thenify-all|1.6.0|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|ipaddr.js|1.5.2|间接依赖|npm|
|merkle-patricia-tree|2.3.0|间接依赖|npm|
|string-width|2.1.1|间接依赖|npm|
|dom-serializer|0.1.0|间接依赖|npm|
|htmlparser2|3.3.0|间接依赖|npm|
|performance-now|2.1.0|间接依赖|npm|
|pump|1.0.3|间接依赖|npm|
|babel-helper-get-function-arity|6.24.1|间接依赖|npm|
|loader-utils|1.1.0|间接依赖|npm|
|selfsigned|1.10.1|间接依赖|npm|
|lowercase-keys|1.0.0|间接依赖|npm|
|browserify-aes|1.2.0|间接依赖|npm|
|parseurl|1.3.2|间接依赖|npm|
|postcss-modules-values|1.3.0|间接依赖|npm|
|node-notifier|5.1.2|直接依赖|npm|
|hoek|4.2.0|间接依赖|npm|
|clone|1.0.3|间接依赖|npm|
|is-date-object|1.0.1|间接依赖|npm|
|wrap-ansi|2.1.0|直接依赖|npm|
|p-finally|1.0.0|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|timed-out|4.0.1|间接依赖|npm|
|cookie|0.3.1|间接依赖|npm|
|babel-helper-optimise-call-expression|6.24.1|间接依赖|npm|
|qs|6.5.1|间接依赖|npm|
|acorn-dynamic-import|2.0.2|间接依赖|npm|
|array-union|1.0.2|间接依赖|npm|
|memdown|1.4.1|间接依赖|npm|
|global|4.3.2|间接依赖|npm|
|regenerator-runtime|0.11.1|间接依赖|npm|
|which|1.3.0|间接依赖|npm|
|asynckit|0.4.0|间接依赖|npm|
|path-to-regexp|0.1.7|间接依赖|npm|
|node-forge|0.6.33|间接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|array-flatten|1.1.1|间接依赖|npm|
|postcss-reduce-initial|1.0.1|间接依赖|npm|
|code-point-at|1.1.0|直接依赖|npm|
|loader-runner|2.3.0|间接依赖|npm|
|shelljs|0.7.8|直接依赖|npm|
|utila|0.4.0|间接依赖|npm|
|repeat-string|1.6.1|间接依赖|npm|
|strip-bom|3.0.0|间接依赖|npm|
|expand-range|1.8.2|间接依赖|npm|
|querystring-es3|0.2.1|间接依赖|npm|
|web3-eth-abi|1.0.0-beta.31|间接依赖|npm|
|object-keys|0.4.0|间接依赖|npm|
|is-dotfile|1.0.3|间接依赖|npm|
|encodeurl|1.0.1|间接依赖|npm|
|combined-stream|1.0.5|间接依赖|npm|
|cuint|0.2.2|间接依赖|npm|
|batch|0.6.1|间接依赖|npm|
|arr-diff|2.0.0|间接依赖|npm|
|growly|1.3.0|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|seek-bzip|1.0.5|间接依赖|npm|
|level-ws|0.0.0|间接依赖|npm|
|icss-utils|2.1.0|间接依赖|npm|
|shebang-command|1.2.0|间接依赖|npm|
|babel-helper-builder-binary-assignment-operator-visitor|6.24.1|间接依赖|npm|
|handle-thing|1.2.5|间接依赖|npm|
|minimist|0.0.8|间接依赖|npm|
|param-case|2.1.1|间接依赖|npm|
|web3|1.0.0-beta.31|直接依赖|npm|
|har-schema|2.0.0|间接依赖|npm|
|babel-helper-bindify-decorators|6.24.1|间接依赖|npm|
|verror|1.10.0|间接依赖|npm|
|require-main-filename|1.0.1|间接依赖|npm|
|make-dir|1.1.0|间接依赖|npm|
|json-schema|0.2.3|间接依赖|npm|
|http-proxy|1.16.2|间接依赖|npm|
|clap|1.2.3|间接依赖|npm|
|postcss-load-plugins|2.3.0|间接依赖|npm|
|any-promise|1.3.0|间接依赖|npm|
|color-string|0.3.0|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|unique-filename|1.1.0|间接依赖|npm|
|postcss-modules-extract-imports|1.1.0|间接依赖|npm|
|babel-plugin-transform-es2015-literals|6.22.0|间接依赖|npm|
|cipher-base|1.0.4|间接依赖|npm|
|balanced-match|1.0.0|间接依赖|npm|
|original|1.0.0|间接依赖|npm|
|des.js|1.0.0|间接依赖|npm|
|vuetify|0.17.6|直接依赖|npm|
|path-parse|1.0.5|间接依赖|npm|
|html-entities|1.2.1|间接依赖|npm|
|babel-preset-env|1.6.1|直接依赖|npm|
|error-stack-parser|2.0.1|间接依赖|npm|
|negotiator|0.6.1|间接依赖|npm|
|lcid|1.0.0|间接依赖|npm|
|readable-stream|2.3.4|间接依赖|npm|
|ethereum-common|0.2.0|间接依赖|npm|
|decompress-unzip|4.0.1|间接依赖|npm|
|jsesc|1.3.0|间接依赖|npm|
|get-stream|3.0.0|间接依赖|npm|
|http-signature|1.2.0|间接依赖|npm|
|builtin-modules|1.1.1|间接依赖|npm|
|hash-base|3.0.4|间接依赖|npm|
|css-loader|0.28.7|直接依赖|npm|
|babel-types|6.26.0|间接依赖|npm|
|whatwg-fetch|2.0.4|间接依赖|npm|
|postcss-filter-plugins|2.0.2|间接依赖|npm|
|http-proxy-middleware|0.17.4|间接依赖|npm|
|faye-websocket|0.10.0|间接依赖|npm|
|mime-types|2.1.17|间接依赖|npm|
|is-utf8|0.2.1|直接依赖|npm|
|serialize-javascript|1.4.0|间接依赖|npm|
|yargs-parser|7.0.0|间接依赖|npm|
|is-posix-bracket|0.1.1|间接依赖|npm|
|slash|1.0.0|间接依赖|npm|
|isarray|0.0.1|间接依赖|npm|
|postcss-reduce-idents|2.4.0|间接依赖|npm|
|web3-providers-http|1.0.0-beta.31|间接依赖|npm|
|strict-uri-encode|1.1.0|间接依赖|npm|
|foreach|2.0.5|间接依赖|npm|
|promise-inflight|1.0.1|间接依赖|npm|
|os-locale|1.4.0|间接依赖|npm|
|regexpu-core|2.0.0|间接依赖|npm|
|ajv-keywords|2.1.1|间接依赖|npm|
|loose-envify|1.3.1|间接依赖|npm|
|strip-dirs|2.1.0|间接依赖|npm|
|color|0.11.4|间接依赖|npm|
|locate-path|2.0.0|间接依赖|npm|
|forever-agent|0.6.1|间接依赖|npm|
|browserslist|2.11.0|间接依赖|npm|
|babel-plugin-transform-decorators|6.24.1|间接依赖|npm|
|emojis-list|2.1.0|间接依赖|npm|
|browserify-cipher|1.0.0|间接依赖|npm|
|internal-ip|1.2.0|间接依赖|npm|
|cssnano|3.10.0|间接依赖|npm|
|console-browserify|1.1.0|间接依赖|npm|
|ethereumjs-tx|1.3.3|直接依赖|npm|
|buffer-to-arraybuffer|0.0.5|间接依赖|npm|
|encoding|0.1.12|间接依赖|npm|
|rlp|2.0.0|间接依赖|npm|
|glob-base|0.3.0|间接依赖|npm|
|detect-node|2.0.3|间接依赖|npm|
|postcss-calc|5.3.1|间接依赖|npm|
|ncname|1.0.0|间接依赖|npm|
|is-svg|2.1.0|间接依赖|npm|
|etag|1.8.1|间接依赖|npm|
|indexes-of|1.0.1|间接依赖|npm|
|webpack-merge|4.1.1|直接依赖|npm|
|aes-js|0.2.4|间接依赖|npm|
|json-loader|0.5.7|间接依赖|npm|
|bluebird|3.5.1|间接依赖|npm|
|semaphore|1.1.0|间接依赖|npm|
|shellwords|0.1.1|间接依赖|npm|
|is-binary-path|1.0.1|间接依赖|npm|
|tapable|0.2.8|间接依赖|npm|
|serve-index|1.9.1|间接依赖|npm|
|url-to-options|1.0.1|间接依赖|npm|
|url|0.11.0|间接依赖|npm|
|web3-eth|1.0.0-beta.31|间接依赖|npm|
|opn|5.1.0|间接依赖|npm|
|postcss-loader|2.0.10|直接依赖|npm|
|delayed-stream|1.0.0|间接依赖|npm|
|miller-rabin|4.0.1|间接依赖|npm|
|math-expression-evaluator|1.2.17|间接依赖|npm|
|lodash.assign|4.2.0|间接依赖|npm|
|babel-plugin-transform-es2015-modules-umd|6.24.1|间接依赖|npm|
|minimalistic-crypto-utils|1.0.1|间接依赖|npm|
|json3|3.3.2|间接依赖|npm|
|diffie-hellman|5.0.2|间接依赖|npm|
|fs-write-stream-atomic|1.0.10|间接依赖|npm|
|levelup|1.3.9|间接依赖|npm|
|browserify-des|1.0.0|间接依赖|npm|
|es6-weak-map|2.0.2|间接依赖|npm|
|ajv|5.5.2|间接依赖|npm|
|prepend-http|1.0.4|间接依赖|npm|
|postcss-value-parser|3.3.0|间接依赖|npm|
|webpack-dev-server|2.9.7|直接依赖|npm|
|file-type|5.2.0|间接依赖|npm|
|babel-plugin-transform-es2015-parameters|6.24.1|间接依赖|npm|
|bip66|1.1.5|间接依赖|npm|
|coinstring|2.3.0|间接依赖|npm|
|extglob|0.3.2|间接依赖|npm|
|buffer-indexof|1.1.1|间接依赖|npm|
|es5-ext|0.10.37|间接依赖|npm|
|through|2.3.8|间接依赖|npm|
|camelcase|3.0.0|间接依赖|npm|
|process-nextick-args|2.0.0|间接依赖|npm|
|color-convert|1.9.1|间接依赖|npm|
|coa|1.0.4|间接依赖|npm|
|yargs|8.0.2|间接依赖|npm|
|p-locate|2.0.0|间接依赖|npm|
|babel-helper-hoist-variables|6.24.1|间接依赖|npm|
|cross-spawn|5.1.0|间接依赖|npm|
|ecc-jsbn|0.1.1|间接依赖|npm|
|web3-core-method|1.0.0-beta.31|间接依赖|npm|
|babel-helper-explode-class|6.24.1|间接依赖|npm|
|truffle-wallet-provider|0.0.5|直接依赖|npm|
|create-hash|1.1.3|间接依赖|npm|
|is-glob|4.0.0|间接依赖|npm|
|postcss-url|7.3.0|直接依赖|npm|
|sha3|1.2.1|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|inherits|2.0.3|间接依赖|npm|
|babel-plugin-syntax-exponentiation-operator|6.13.0|间接依赖|npm|
|decompress-tarbz2|4.1.1|间接依赖|npm|
|process-nextick-args|1.0.7|间接依赖|npm|
|import-local|0.1.1|间接依赖|npm|
|core-util-is|1.0.2|间接依赖|npm|
|readdirp|2.1.0|间接依赖|npm|
|fill-range|2.2.3|间接依赖|npm|
|relateurl|0.2.7|间接依赖|npm|
|y18n|3.2.1|间接依赖|npm|
|unbzip2-stream|1.2.5|间接依赖|npm|
|web3-eth-accounts|1.0.0-beta.31|间接依赖|npm|
|request|2.83.0|间接依赖|npm|
|send|0.16.1|间接依赖|npm|
|dir-glob|2.0.0|间接依赖|npm|
|postcss-discard-duplicates|2.1.0|间接依赖|npm|
|electron-to-chromium|1.3.30|间接依赖|npm|
|move-concurrently|1.0.1|间接依赖|npm|
|filesize|3.5.11|间接依赖|npm|
|hawk|6.0.2|间接依赖|npm|
|globals|9.18.0|间接依赖|npm|
|form-data|2.3.2|间接依赖|npm|
|path-exists|3.0.0|间接依赖|npm|
|set-blocking|2.0.0|间接依赖|npm|
|babel-plugin-transform-es2015-template-literals|6.22.0|间接依赖|npm|
|uglify-to-browserify|1.0.2|直接依赖|npm|
|babylon|6.18.0|间接依赖|npm|
|json-schema-traverse|0.3.1|间接依赖|npm|
|filename-regex|2.0.1|间接依赖|npm|
|ethereumjs-account|2.0.4|间接依赖|npm|
|p-timeout|1.2.1|间接依赖|npm|
|from2|2.3.0|间接依赖|npm|
|normalize-range|0.1.2|间接依赖|npm|
|kind-of|3.2.2|间接依赖|npm|
|tar|2.2.1|间接依赖|npm|
|browserify-rsa|4.0.1|间接依赖|npm|
|estraverse|4.2.0|间接依赖|npm|
|errno|0.1.6|间接依赖|npm|
|is-primitive|2.0.0|间接依赖|npm|
|p-cancelable|0.3.0|间接依赖|npm|
|window-size|0.1.0|直接依赖|npm|
|webpack-sources|1.1.0|间接依赖|npm|
|postcss-minify-selectors|2.1.1|间接依赖|npm|
|url-parse|1.2.0|间接依赖|npm|
|fast-json-stable-stringify|2.0.0|间接依赖|npm|
|number-is-nan|1.0.1|间接依赖|npm|
|os-browserify|0.3.0|间接依赖|npm|
|unique-slug|2.0.0|间接依赖|npm|
|web3-provider-engine|8.6.1|间接依赖|npm|
|babel-plugin-syntax-dynamic-import|6.18.0|间接依赖|npm|
|preserve|0.2.0|间接依赖|npm|
|babel-plugin-transform-es2015-block-scoped-functions|6.22.0|间接依赖|npm|
|read-pkg-up|1.0.1|间接依赖|npm|
|public-encrypt|4.0.0|间接依赖|npm|
|bn.js|4.11.6|间接依赖|npm|
|browserify-sign|4.0.4|间接依赖|npm|
|sntp|2.1.0|间接依赖|npm|
|electron-releases|2.1.0|间接依赖|npm|
|requires-port|1.0.0|间接依赖|npm|
|webpack-bundle-analyzer|2.9.1|直接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|block-stream|0.0.9|间接依赖|npm|
|has-to-string-tag-x|1.4.1|间接依赖|npm|
|obuf|1.1.1|间接依赖|npm|
|node-fetch|1.7.3|间接依赖|npm|
|form-data|2.3.1|间接依赖|npm|
|memorystream|0.3.1|间接依赖|npm|
|ltgt|2.2.0|间接依赖|npm|
|find-cache-dir|1.0.0|间接依赖|npm|
|escope|3.6.0|间接依赖|npm|
|hash.js|1.1.3|间接依赖|npm|
|is-stream|1.1.0|间接依赖|npm|
|statuses|1.3.1|间接依赖|npm|
|es-abstract|1.10.0|间接依赖|npm|
|tweetnacl|0.14.5|间接依赖|npm|
|minimalistic-assert|1.0.0|间接依赖|npm|
|spdy|3.4.7|间接依赖|npm|
|babel-plugin-transform-es2015-destructuring|6.23.0|间接依赖|npm|
|babel-helper-regex|6.26.0|间接依赖|npm|
|query-string|4.3.4|间接依赖|npm|
|indent-string|2.1.0|间接依赖|npm|
|postcss-colormin|2.2.2|间接依赖|npm|
|parse-headers|2.0.1|间接依赖|npm|
|longest|1.0.1|间接依赖|npm|
|is-retry-allowed|1.1.0|间接依赖|npm|
|friendly-errors-webpack-plugin|1.6.1|直接依赖|npm|
|interpret|1.1.0|间接依赖|npm|
|stream-http|2.7.2|间接依赖|npm|
|array-unique|0.2.1|间接依赖|npm|
|colormin|1.1.2|间接依赖|npm|
|pinkie|2.0.4|间接依赖|npm|
|constants-browserify|1.0.0|间接依赖|npm|
|merge-descriptors|1.0.1|间接依赖|npm|
|minimatch|3.0.4|间接依赖|npm|
|path-key|2.0.1|间接依赖|npm|
|remove-trailing-separator|1.1.0|间接依赖|npm|
|vue-hot-reload-api|2.2.4|间接依赖|npm|
|ethjs-util|0.1.4|直接依赖|npm|
|babel-helper-remap-async-to-generator|6.24.1|间接依赖|npm|
|sprintf-js|1.0.3|间接依赖|npm|
|babel-plugin-transform-class-properties|6.24.1|间接依赖|npm|
|run-queue|1.0.3|间接依赖|npm|
|xhr2|0.1.4|间接依赖|npm|
|mime|1.6.0|间接依赖|npm|
|esprima|2.7.3|间接依赖|npm|
|uniqs|2.0.0|间接依赖|npm|
|duplexer3|0.1.4|间接依赖|npm|
|level-codec|7.0.1|间接依赖|npm|
|nan|2.8.0|间接依赖|npm|
|deferred-leveldown|1.2.2|间接依赖|npm|
|fastparse|1.1.1|间接依赖|npm|
|postcss-discard-empty|2.1.0|间接依赖|npm|
|async|2.6.0|间接依赖|npm|
|which-module|1.0.0|间接依赖|npm|
|mz|2.7.0|间接依赖|npm|
|raw-body|2.3.2|间接依赖|npm|
|es-to-primitive|1.1.1|间接依赖|npm|
|babel-plugin-syntax-object-rest-spread|6.13.0|间接依赖|npm|
|strip-ansi|3.0.1|间接依赖|npm|
|has-ansi|2.0.0|直接依赖|npm|
|decode-uri-component|0.2.0|直接依赖|npm|
|glob-parent|2.0.0|间接依赖|npm|
|execa|0.7.0|间接依赖|npm|
|is-absolute-url|2.1.0|间接依赖|npm|
|utils-merge|1.0.1|间接依赖|npm|
|deep-equal|1.0.1|间接依赖|npm|
|postcss-selector-parser|2.2.3|间接依赖|npm|
|right-align|0.1.3|间接依赖|npm|
|uniq|1.0.1|间接依赖|npm|
|es6-set|0.1.5|间接依赖|npm|
|vue-loader|13.6.2|直接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|web3-eth-iban|1.0.0-beta.31|间接依赖|npm|
|decompress-tar|4.1.1|间接依赖|npm|
|ssri|5.0.0|间接依赖|npm|
|url-set-query|1.0.0|间接依赖|npm|
|moment|2.22.0|直接依赖|npm|
|html-comment-regex|1.1.1|间接依赖|npm|
|is-regex|1.0.4|间接依赖|npm|
|restore-cursor|2.0.0|间接依赖|npm|
|chownr|1.0.1|间接依赖|npm|
|min-document|2.19.0|间接依赖|npm|
|copy-webpack-plugin|4.3.1|直接依赖|npm|
|async-limiter|1.0.0|间接依赖|npm|
|methods|1.1.2|间接依赖|npm|
|read-cache|1.0.0|间接依赖|npm|
|string-length|1.0.1|间接依赖|npm|
|isomorphic-fetch|2.2.1|间接依赖|npm|
|css-color-names|0.0.4|间接依赖|npm|
|keyv|3.0.0|间接依赖|npm|
|string_decoder|1.0.3|间接依赖|npm|
|aws-sign2|0.7.0|间接依赖|npm|
|babel-plugin-transform-object-rest-spread|6.26.0|间接依赖|npm|
|pify|3.0.0|间接依赖|npm|
|is-symbol|1.0.1|间接依赖|npm|
|es6-iterator|2.0.3|间接依赖|npm|
|bignumber.js|git+https://github.com/debris/bignumber.js.git#94d7146671b9719e00a09c29b01a691bc85048c2|间接依赖|npm|
|spdy-transport|2.0.20|间接依赖|npm|
|memory-fs|0.4.1|间接依赖|npm|
|postcss-normalize-charset|1.1.1|间接依赖|npm|
|xhr|2.4.1|间接依赖|npm|
|signal-exit|3.0.2|间接依赖|npm|
|toposort|1.0.6|间接依赖|npm|
|babel-plugin-check-es2015-constants|6.22.0|间接依赖|npm|
|es-abstract|1.11.0|间接依赖|npm|
|url-loader|0.5.9|直接依赖|npm|
|resolve-cwd|2.0.0|间接依赖|npm|
|extract-text-webpack-plugin|3.0.2|直接依赖|npm|
|immediate|3.2.3|间接依赖|npm|
|is-extendable|0.1.1|间接依赖|npm|
|postcss-minify-gradients|1.0.5|间接依赖|npm|
|define-properties|1.1.2|间接依赖|npm|
|ethereumjs-util|5.1.5|直接依赖|npm|
|log-symbols|1.0.2|间接依赖|npm|
|solc|0.4.23|间接依赖|npm|
|cli-spinners|1.1.0|间接依赖|npm|
|copy-concurrently|1.0.5|间接依赖|npm|
|mime-types|2.1.18|间接依赖|npm|
|bn.js|4.11.8|间接依赖|npm|
|readable-stream|2.3.3|间接依赖|npm|
|rechoir|0.6.2|间接依赖|npm|
|supports-color|5.1.0|间接依赖|npm|
|uglify-js|3.3.4|间接依赖|npm|
|vue-resource|1.5.0|直接依赖|npm|
|ms|2.0.0|间接依赖|npm|
|ripemd160|2.0.2|间接依赖|npm|
|web3-bzz|1.0.0-beta.31|间接依赖|npm|
|async-each|1.0.1|间接依赖|npm|
|babel-preset-stage-3|6.24.1|间接依赖|npm|
|typedarray-to-buffer|3.1.5|间接依赖|npm|
|object.omit|2.0.1|间接依赖|npm|
|is-builtin-module|1.0.0|间接依赖|npm|
|lodash.camelcase|4.3.0|间接依赖|npm|
|got|7.1.0|间接依赖|npm|
|postcss-merge-idents|2.1.7|间接依赖|npm|
|proxy-addr|2.0.2|间接依赖|npm|
|responselike|1.0.2|间接依赖|npm|
|cyclist|0.2.2|间接依赖|npm|
|xhr-request-promise|0.1.2|间接依赖|npm|
|wordwrap|0.0.2|间接依赖|npm|
|babel-plugin-transform-exponentiation-operator|6.24.1|间接依赖|npm|
|string-width|1.0.2|间接依赖|npm|
|is-path-in-cwd|1.0.0|间接依赖|npm|
|fake-merkle-patricia-tree|1.0.1|间接依赖|npm|
|vm-browserify|0.0.4|间接依赖|npm|
|array-uniq|1.0.3|间接依赖|npm|
|hash-sum|1.0.2|间接依赖|npm|
|ethereumjs-wallet|0.6.0|间接依赖|npm|
|yaeti|0.0.6|间接依赖|npm|
|fsevents|1.1.3|间接依赖|npm|
|bs58|3.1.0|间接依赖|npm|
|babel-plugin-transform-async-generator-functions|6.24.1|间接依赖|npm|
|js-yaml|3.7.0|间接依赖|npm|
|connect-history-api-fallback|1.5.0|间接依赖|npm|
|postcss-reduce-transforms|1.0.4|间接依赖|npm|
|load-json-file|2.0.0|间接依赖|npm|
|sort-keys|1.1.2|间接依赖|npm|
|decamelize|1.2.0|间接依赖|npm|
|yallist|2.1.2|间接依赖|npm|
|escape-html|1.0.3|间接依赖|npm|
|fs-extra|2.1.2|间接依赖|npm|
|compression|1.7.1|间接依赖|npm|
|object-inspect|1.3.0|间接依赖|npm|
|eventsource|0.1.6|间接依赖|npm|
|js-tokens|3.0.2|间接依赖|npm|
|web3-core-requestmanager|1.0.0-beta.31|间接依赖|npm|
|browserify-sha3|0.0.1|间接依赖|npm|
|iconv-lite|0.4.21|间接依赖|npm|
|lodash.memoize|4.1.2|间接依赖|npm|
|enhanced-resolve|3.4.1|间接依赖|npm|
|to-fast-properties|1.0.3|间接依赖|npm|
|rustbn.js|0.1.2|间接依赖|npm|
|vue|2.5.13|直接依赖|npm|
|he|1.1.1|间接依赖|npm|
|parse-json|2.2.0|间接依赖|npm|
|bytes|3.0.0|间接依赖|npm|
|buffer|4.9.1|间接依赖|npm|
|decompress|4.2.0|间接依赖|npm|
|fast-deep-equal|1.0.0|间接依赖|npm|
|spdx-correct|1.0.2|间接依赖|npm|
|camel-case|3.0.0|间接依赖|npm|
|vue-template-compiler|2.5.13|直接依赖|npm|
|babel-plugin-transform-es2015-for-of|6.23.0|间接依赖|npm|
|postcss-load-config|1.2.0|间接依赖|npm|
|ethereumjs-block|1.7.1|间接依赖|npm|
|path-browserify|0.0.0|间接依赖|npm|
|xtend|4.0.1|间接依赖|npm|
|redent|1.0.0|间接依赖|npm|
|webpack|3.10.0|直接依赖|npm|
|html-minifier|3.5.8|间接依赖|npm|
|svgo|0.7.2|间接依赖|npm|
|de-indent|1.0.2|间接依赖|npm|
|dotenv|5.0.1|直接依赖|npm|
|rimraf|2.6.2|间接依赖|npm|
|request|2.85.0|间接依赖|npm|
|bcrypt-pbkdf|1.0.1|间接依赖|npm|
|ansi-styles|3.2.0|间接依赖|npm|
|domelementtype|1.3.0|间接依赖|npm|
|uglifyjs-webpack-plugin|1.1.5|间接依赖|npm|
|babel-plugin-syntax-trailing-function-commas|6.22.0|间接依赖|npm|
|postcss-normalize-url|3.0.8|间接依赖|npm|
|babel-helper-function-name|6.24.1|间接依赖|npm|
|yargs-parser|2.4.1|间接依赖|npm|
|bs58check|1.3.4|间接依赖|npm|
|@sindresorhus/is|0.7.0|直接依赖|npm|
|is-buffer|1.1.6|间接依赖|npm|
|dns-txt|2.0.2|间接依赖|npm|
|babel-plugin-transform-vue-jsx|3.5.0|直接依赖|npm|
|p-try|1.0.0|间接依赖|npm|
|parse-asn1|5.1.0|间接依赖|npm|
|lazy-cache|1.0.4|间接依赖|npm|
|xxhashjs|0.2.1|间接依赖|npm|
|thenify|3.3.0|间接依赖|npm|
|domain-browser|1.1.7|间接依赖|npm|
|dns-equal|1.0.0|间接依赖|npm|
|babel-plugin-transform-es2015-unicode-regex|6.24.1|间接依赖|npm|
|fs-promise|2.0.3|间接依赖|npm|
|mock-fs|4.4.2|间接依赖|npm|
|jsbn|0.1.1|间接依赖|npm|
|content-disposition|0.5.2|间接依赖|npm|
|clone|2.1.1|间接依赖|npm|
|on-finished|2.3.0|间接依赖|npm|
|express|4.16.2|间接依赖|npm|
|minimist|1.2.0|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|chokidar|1.7.0|间接依赖|npm|
|css-selector-tokenizer|0.7.0|间接依赖|npm|
|scrypt.js|0.2.0|间接依赖|npm|
|websocket-extensions|0.1.3|间接依赖|npm|
|prr|1.0.1|间接依赖|npm|
|async-eventemitter|0.2.4|间接依赖|npm|
|setimmediate|1.0.5|间接依赖|npm|
|babel-plugin-transform-es2015-shorthand-properties|6.24.1|间接依赖|npm|
|babel-plugin-syntax-jsx|6.18.0|直接依赖|npm|
|web3-core-promievent|1.0.0-beta.31|间接依赖|npm|
|punycode|1.4.1|间接依赖|npm|
|babel-helper-define-map|6.26.0|间接依赖|npm|
|babel-preset-stage-2|6.24.1|直接依赖|npm|
|js-sha3|0.3.1|间接依赖|npm|
|normalize-package-data|2.4.0|间接依赖|npm|
|opener|1.4.3|间接依赖|npm|
|is-plain-obj|1.1.0|间接依赖|npm|
|sha.js|2.4.9|间接依赖|npm|
|elliptic|6.4.0|间接依赖|npm|
|events|1.1.1|间接依赖|npm|
|decompress-response|3.3.0|间接依赖|npm|
|unpipe|1.0.0|间接依赖|npm|
|end-of-stream|1.4.0|间接依赖|npm|
|http-deceiver|1.2.7|间接依赖|npm|
|babel-plugin-transform-es2015-block-scoping|6.26.0|间接依赖|npm|
|hash-base|2.0.2|间接依赖|npm|
|buffer-xor|1.0.3|间接依赖|npm|
|oauth-sign|0.8.2|间接依赖|npm|
|caniuse-db|1.0.30000787|间接依赖|npm|
|vue-template-es2015-compiler|1.6.0|间接依赖|npm|
|postcss-unique-selectors|2.0.2|间接依赖|npm|
|strip-indent|1.0.1|间接依赖|npm|
|source-map|0.6.1|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|num2fraction|1.2.2|间接依赖|npm|
|esrecurse|4.2.0|间接依赖|npm|
|fresh|0.5.2|间接依赖|npm|
|stream-browserify|2.0.1|间接依赖|npm|
|duplexify|3.5.1|间接依赖|npm|
|web3-utils|1.0.0-beta.31|间接依赖|npm|
|mimic-response|1.0.0|间接依赖|npm|
|postcss-discard-unused|2.2.3|间接依赖|npm|
|boolbase|1.0.0|间接依赖|npm|
|braces|1.8.5|间接依赖|npm|
|postcss-modules-scope|1.1.0|间接依赖|npm|
|read-pkg|1.1.0|间接依赖|npm|
|postcss-message-helpers|2.0.0|间接依赖|npm|
|schema-utils|0.3.0|间接依赖|npm|
|aws4|1.6.0|间接依赖|npm|
|stream-shift|1.0.0|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|chalk|2.3.0|间接依赖|npm|
|lodash.uniq|4.5.0|间接依赖|npm|
|multicast-dns-service-types|1.1.0|间接依赖|npm|
|postcss-load-options|1.2.0|间接依赖|npm|
|wbuf|1.7.2|间接依赖|npm|
|validate-npm-package-license|3.0.1|间接依赖|npm|
|is-typedarray|1.0.0|间接依赖|npm|
|semver|5.4.1|间接依赖|npm|
|cacheable-request|2.1.4|直接依赖|npm|
|vue-style-loader|3.0.3|间接依赖|npm|
|solc|0.4.20|间接依赖|npm|
|is-callable|1.1.3|间接依赖|npm|
|har-validator|5.0.3|间接依赖|npm|
|https-browserify|1.0.0|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|utf8|2.1.2|间接依赖|npm|
|simple-get|2.7.0|间接依赖|npm|
|cliui|3.2.0|间接依赖|npm|
|is-path-inside|1.0.1|间接依赖|npm|
|stackframe|1.0.4|间接依赖|npm|
|set-immediate-shim|1.0.1|间接依赖|npm|
|forwarded|0.1.2|间接依赖|npm|
|nth-check|1.0.1|间接依赖|npm|
|babel-plugin-transform-es2015-object-super|6.24.1|间接依赖|npm|
|es6-map|0.1.5|间接依赖|npm|
|postcss-zindex|2.2.0|间接依赖|npm|
|sha.js|2.4.10|间接依赖|npm|
|ripemd160|2.0.1|间接依赖|npm|
|portfinder|1.0.13|间接依赖|npm|
|merkle-patricia-tree|2.3.1|间接依赖|npm|
|regenerator-transform|0.10.1|间接依赖|npm|
|secp256k1|3.5.0|间接依赖|npm|
|caseless|0.12.0|间接依赖|npm|
|oboe|2.1.3|间接依赖|npm|
|acorn|5.3.0|间接依赖|npm|
|iferr|0.1.5|间接依赖|npm|
|web3-eth-personal|1.0.0-beta.31|间接依赖|npm|
|pretty-error|2.1.1|间接依赖|npm|
|read-pkg-up|2.0.0|间接依赖|npm|
|content-type|1.0.4|间接依赖|npm|
|postcss-merge-longhand|2.0.2|间接依赖|npm|
|assert|1.4.1|间接依赖|npm|
|graceful-readlink|1.0.1|直接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)