# cachethq/cachet安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692603988649594880.svg)](https://www.murphysec.com/console/report/1692242135145537536/1692603988649594880)

仓库描述：The open-source status page system 🚦

仓库地址：[https://github.com/cachethq/cachet](https://github.com/cachethq/cachet)

| star：13285 | watch：288 | fork：1568 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-19 00:04:20 | 许可证：BSD-3-Clause |
| 最近检测时间：2023-08-19 02:27:18 | 组件总数：998 | 漏洞总数：125 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|webpack-dev-server 信息泄露漏洞|未授权敏感信息泄露|[MPS-2018-12609](https://www.oscs1024.com/hd/MPS-2018-12609)|CVE-2018-14732|高危|
|LibSass 拒绝服务漏洞|空指针取消引用|[MPS-2018-15348](https://www.oscs1024.com/hd/MPS-2018-15348)|CVE-2018-19797|中危|
|LibSass 拒绝服务漏洞|UAF|[MPS-2018-15372](https://www.oscs1024.com/hd/MPS-2018-15372)|CVE-2018-19827|高危|
|LibSass 拒绝服务漏洞|越界读取|[MPS-2018-15397](https://www.oscs1024.com/hd/MPS-2018-15397)|CVE-2018-19839|中危|
|LibSass 拒绝服务漏洞|空指针取消引用|[MPS-2018-15962](https://www.oscs1024.com/hd/MPS-2018-15962)|CVE-2018-20190|中危|
|LibSass 拒绝服务漏洞|UAF|[MPS-2018-6523](https://www.oscs1024.com/hd/MPS-2018-6523)|CVE-2018-11499|严重|
|LibSass 拒绝服务漏洞|空指针取消引用|[MPS-2018-6915](https://www.oscs1024.com/hd/MPS-2018-6915)|CVE-2018-11694|高危|
|LibSass 拒绝服务漏洞|越界读取|[MPS-2018-6918](https://www.oscs1024.com/hd/MPS-2018-6918)|CVE-2018-11697|高危|
|LibSass 拒绝服务漏洞|越界读取|[MPS-2018-6919](https://www.oscs1024.com/hd/MPS-2018-6919)|CVE-2018-11698|高危|
|Http-signature 安全漏洞|密码学签名的验证不恰当|[MPS-2018-6996](https://www.oscs1024.com/hd/MPS-2018-6996)|CVE-2017-16005|高危|
|LibSass 堆缓冲区错误漏洞|越界读取|[MPS-2019-0502](https://www.oscs1024.com/hd/MPS-2019-0502)|CVE-2019-6283|中危|
|LibSass 堆缓冲区错误漏洞|越界读取|[MPS-2019-0503](https://www.oscs1024.com/hd/MPS-2019-0503)|CVE-2019-6284|中危|
|LibSass 堆缓冲区错误漏洞|越界读取|[MPS-2019-0505](https://www.oscs1024.com/hd/MPS-2019-0505)|CVE-2019-6286|中危|
|mixin-deep 参数注入漏洞|参数注入或修改|[MPS-2019-10507](https://www.oscs1024.com/hd/MPS-2019-10507)|CVE-2019-10746|严重|
|LibSass DOS漏洞|未经控制的递归|[MPS-2019-14246](https://www.oscs1024.com/hd/MPS-2019-14246)|CVE-2019-18797|中危|
|LibSass < 3.6.3 缓冲区错误漏洞|越界读取|[MPS-2019-14247](https://www.oscs1024.com/hd/MPS-2019-14247)|CVE-2019-18798|中危|
|LibSass 程序崩溃漏洞|空指针取消引用|[MPS-2019-14248](https://www.oscs1024.com/hd/MPS-2019-14248)|CVE-2019-18799|中危|
|serialize-javascript < 2.1.2 跨站脚本漏洞|XSS|[MPS-2019-15864](https://www.oscs1024.com/hd/MPS-2019-15864)|CVE-2019-16769|中危|
|kind-of 存在注入漏洞|将资源暴露给错误范围|[MPS-2019-17164](https://www.oscs1024.com/hd/MPS-2019-17164)|CVE-2019-20149|高危|
|Laravel Framework 安全漏洞|代码注入|[MPS-2019-1897](https://www.oscs1024.com/hd/MPS-2019-1897)|CVE-2019-9081|严重|
|LibSass 资源管理错误漏洞|未经控制的递归|[MPS-2019-4291](https://www.oscs1024.com/hd/MPS-2019-4291)|CVE-2018-20821|中危|
|node-sass 堆栈溢出漏洞|未经控制的递归|[MPS-2019-4292](https://www.oscs1024.com/hd/MPS-2019-4292)|CVE-2018-20822|中危|
|SockJS <0.3.20 异常处理不当漏洞|对异常条件的处理不恰当|[MPS-2020-10001](https://www.oscs1024.com/hd/MPS-2020-10001)|CVE-2020-7693|中危|
|Ajv v6.12.2 输入验证错误漏洞|MAID|[MPS-2020-10525](https://www.oscs1024.com/hd/MPS-2020-10525)|CVE-2020-15366|中危|
|node-forge <0.10.0 对象属性的不当控制修改漏洞|动态确定对象属性修改的控制不恰当|[MPS-2020-12281](https://www.oscs1024.com/hd/MPS-2020-12281)|CVE-2020-7720|高危|
|object-path 安全漏洞|MAID|[MPS-2020-14597](https://www.oscs1024.com/hd/MPS-2020-14597)|CVE-2020-15256|严重|
|chart.js 输入验证错误漏洞|原型污染|[MPS-2020-15331](https://www.oscs1024.com/hd/MPS-2020-15331)|CVE-2020-7746|严重|
|jQuery 跨站脚本漏洞|XSS|[MPS-2020-15461](https://www.oscs1024.com/hd/MPS-2020-15461)|CVE-2020-11023|中危|
|jQuery 跨站脚本漏洞|XSS|[MPS-2020-15462](https://www.oscs1024.com/hd/MPS-2020-15462)|CVE-2020-11022|中危|
|lodash <4.17.15 原型污染漏洞|原型污染|[MPS-2020-15679](https://www.oscs1024.com/hd/MPS-2020-15679)|CVE-2020-8203|高危|
|Axios 服务器端请求伪造漏洞|SSRF|[MPS-2020-16365](https://www.oscs1024.com/hd/MPS-2020-16365)|CVE-2020-28168|中危|
|Yargs Y18n 输入原型污染漏洞|动态确定对象属性修改的控制不恰当|[MPS-2020-17543](https://www.oscs1024.com/hd/MPS-2020-17543)|CVE-2020-7774|严重|
|Ini <1.3.6原型污染漏洞|拒绝服务|[MPS-2020-17544](https://www.oscs1024.com/hd/MPS-2020-17544)|CVE-2020-7788|高危|
|Mikaelbr Node-notifier 操作系统命令注入漏洞|OS命令注入|[MPS-2020-17637](https://www.oscs1024.com/hd/MPS-2020-17637)|CVE-2020-7789|中危|
|Laravel Framework 安全漏洞|OS命令注入|[MPS-2020-28712](https://www.oscs1024.com/hd/MPS-2020-28712)|CVE-2020-19316|高危|
|minimist 原型污染漏洞|原型污染|[MPS-2020-3516](https://www.oscs1024.com/hd/MPS-2020-3516)|CVE-2020-7598|中危|
|yargs-parser 原型污染漏洞|特权定义了不安全动作|[MPS-2020-4006](https://www.oscs1024.com/hd/MPS-2020-4006)|CVE-2020-7608|中危|
|serialize-javascript <3.1.0 任意代码执行漏洞|反序列化|[MPS-2020-7976](https://www.oscs1024.com/hd/MPS-2020-7976)|CVE-2020-7660|高危|
|websocket-extensions<0.1.4 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2020-8041](https://www.oscs1024.com/hd/MPS-2020-8041)|CVE-2020-7662|高危|
|websocket-extensions 拒绝服务漏洞|拒绝服务|[MPS-2020-8042](https://www.oscs1024.com/hd/MPS-2020-8042)|CVE-2020-7663|高危|
|Elliptic package 签名伪造漏洞|整数溢出或环绕|[MPS-2020-8202](https://www.oscs1024.com/hd/MPS-2020-8202)|CVE-2020-13822|高危|
|Sass Node-sass 信任管理问题漏洞|证书验证不恰当|[MPS-2021-0364](https://www.oscs1024.com/hd/MPS-2021-0364)|CVE-2020-24025|中危|
|url-parse <1.5.2 开放重定向漏洞|跨站重定向|[MPS-2021-11194](https://www.oscs1024.com/hd/MPS-2021-11194)|CVE-2021-3664|中危|
|node-tar 路径遍历漏洞|路径遍历|[MPS-2021-11547](https://www.oscs1024.com/hd/MPS-2021-11547)|CVE-2021-32804|高危|
|node-tar 路径遍历漏洞|在文件访问前对链接解析不恰当（链接跟随）|[MPS-2021-11548](https://www.oscs1024.com/hd/MPS-2021-11548)|CVE-2021-32803|高危|
|Indutny Elliptic 加密问题漏洞|密码算法不安全|[MPS-2021-1176](https://www.oscs1024.com/hd/MPS-2021-1176)|CVE-2020-28498|中危|
|ansi-html <0.0.8 DoS 漏洞|拒绝服务|[MPS-2021-17628](https://www.oscs1024.com/hd/MPS-2021-17628)|CVE-2021-23424|高危|
|object-path 原型污染漏洞|使用不兼容类型访问资源（类型混淆）|[MPS-2021-18322](https://www.oscs1024.com/hd/MPS-2021-18322)|CVE-2021-23434|高危|
|url-parse  < 1.5.0 输入验证不当漏洞|相对路径遍历|[MPS-2021-2265](https://www.oscs1024.com/hd/MPS-2021-2265)|CVE-2021-27515|中危|
|lodash 拒绝服务漏洞|拒绝服务|[MPS-2021-2574](https://www.oscs1024.com/hd/MPS-2021-2574)|CVE-2020-28500|中危|
|lodash 命令注入漏洞|代码注入|[MPS-2021-2638](https://www.oscs1024.com/hd/MPS-2021-2638)|CVE-2021-23337|高危|
|Npm Node-tar 后置链接漏洞||[MPS-2021-28486](https://www.oscs1024.com/hd/MPS-2021-28486)|CVE-2021-37701|高危|
|Npm Node-tar 后置链接漏洞||[MPS-2021-28488](https://www.oscs1024.com/hd/MPS-2021-28488)|CVE-2021-37712|高危|
|node-tar 路径遍历漏洞|路径遍历|[MPS-2021-28489](https://www.oscs1024.com/hd/MPS-2021-28489)|CVE-2021-37713|高危|
|ssri 拒绝服务漏洞|拒绝服务|[MPS-2021-3030](https://www.oscs1024.com/hd/MPS-2021-3030)|CVE-2021-27290|高危|
|Sindre Sorhus is-svg 拒绝服务漏洞|拒绝服务|[MPS-2021-3031](https://www.oscs1024.com/hd/MPS-2021-3031)|CVE-2021-28092|高危|
|Axios 拒绝服务漏洞|拒绝服务|[MPS-2021-30688](https://www.oscs1024.com/hd/MPS-2021-30688)|CVE-2021-3749|高危|
|Lcobucci jwt 数据伪造问题漏洞|对数据真实性的验证不充分|[MPS-2021-31875](https://www.oscs1024.com/hd/MPS-2021-31875)|CVE-2021-41106|低危|
|Ruy Adorno hosted-git-info 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-3400](https://www.oscs1024.com/hd/MPS-2021-3400)|CVE-2021-23362|中危|
|Async 原型污染漏洞|原型污染|[MPS-2021-34434](https://www.oscs1024.com/hd/MPS-2021-34434)|CVE-2021-43138|高危|
|json-schema 安全漏洞|原型污染|[MPS-2021-34478](https://www.oscs1024.com/hd/MPS-2021-34478)|CVE-2021-3918|严重|
|Laravel Framework  安全漏洞|任意文件上传|[MPS-2021-36323](https://www.oscs1024.com/hd/MPS-2021-36323)|CVE-2021-43617|严重|
|Laravel Framework 跨站脚本漏洞|密码算法不安全|[MPS-2021-36933](https://www.oscs1024.com/hd/MPS-2021-36933)|CVE-2021-43808|中危|
|minimist 安全漏洞|原型污染|[MPS-2021-38405](https://www.oscs1024.com/hd/MPS-2021-38405)|CVE-2021-44906|严重|
|Andrey Sitnik postcss 拒绝服务漏洞|拒绝服务|[MPS-2021-4549](https://www.oscs1024.com/hd/MPS-2021-4549)|CVE-2021-23368|中危|
|postcss 存在正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-5409](https://www.oscs1024.com/hd/MPS-2021-5409)|CVE-2021-23382|中危|
|npm path-parse 安全漏洞|拒绝服务|[MPS-2021-6165](https://www.oscs1024.com/hd/MPS-2021-6165)|CVE-2021-23343|高危|
|dns-packet 存在信息泄露漏洞|资源初始化缺失|[MPS-2021-7013](https://www.oscs1024.com/hd/MPS-2021-7013)|CVE-2021-23386|中危|
|trim-newlines 存在拒绝服务漏洞|拒绝服务|[MPS-2021-7398](https://www.oscs1024.com/hd/MPS-2021-7398)|CVE-2021-33623|高危|
|glob-parent < 5.1.2 存在拒绝服务漏洞|拒绝服务|[MPS-2021-7827](https://www.oscs1024.com/hd/MPS-2021-7827)|CVE-2020-28469|高危|
|is-svg 存在正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-8684](https://www.oscs1024.com/hd/MPS-2021-8684)|CVE-2021-29059|高危|
|thephpleague flysystem 代码注入漏洞||[MPS-2021-8765](https://www.oscs1024.com/hd/MPS-2021-8765)|CVE-2021-32708|高危|
|Digital Bazaar Forge 存在输入验证错误漏洞|跨站重定向|[MPS-2022-0421](https://www.oscs1024.com/hd/MPS-2022-0421)|CVE-2022-0122|中危|
|follow-redirects <1.14.7 存在信息泄露漏洞|侵犯隐私|[MPS-2022-0815](https://www.oscs1024.com/hd/MPS-2022-0815)|CVE-2022-0155|中危|
|Laravel v9.1.8 反序列化漏洞|反序列化|[MPS-2022-10162](https://www.oscs1024.com/hd/MPS-2022-10162)|CVE-2022-30778|严重|
|EventSource 信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-10212](https://www.oscs1024.com/hd/MPS-2022-10212)|CVE-2022-1650|严重|
|Guzzle 信息泄露漏洞|敏感数据的不恰当跨边界移除|[MPS-2022-11072](https://www.oscs1024.com/hd/MPS-2022-11072)|CVE-2022-31042|高危|
|Guzzle 信息泄露漏洞|敏感数据的不恰当跨边界移除|[MPS-2022-11073](https://www.oscs1024.com/hd/MPS-2022-11073)|CVE-2022-31043|高危|
|Guzzle 信息泄露漏洞|敏感数据的不恰当跨边界移除|[MPS-2022-11120](https://www.oscs1024.com/hd/MPS-2022-11120)|CVE-2022-31090|高危|
|Guzzle 信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11121](https://www.oscs1024.com/hd/MPS-2022-11121)|CVE-2022-31091|高危|
|Moment.js 正则拒绝服务漏洞|拒绝服务|[MPS-2022-11159](https://www.oscs1024.com/hd/MPS-2022-11159)|CVE-2022-31129|高危|
|mem  < 4.0.0 存在拒绝服务漏洞|拒绝服务|[MPS-2022-12990](https://www.oscs1024.com/hd/MPS-2022-12990)||中危|
|acorn 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13525](https://www.oscs1024.com/hd/MPS-2022-13525)||高危|
|elliptic<6.5.2 存在定时攻击漏洞|竞争条件|[MPS-2022-13653](https://www.oscs1024.com/hd/MPS-2022-13653)||中危|
|http-proxy<1.18.1 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13767](https://www.oscs1024.com/hd/MPS-2022-13767)||中危|
|js-yaml 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13820](https://www.oscs1024.com/hd/MPS-2022-13820)||中危|
|js-yaml<3.13.1 存在代码注入漏洞|代码注入|[MPS-2022-13822](https://www.oscs1024.com/hd/MPS-2022-13822)||高危|
|lodash<4.17.20 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13841](https://www.oscs1024.com/hd/MPS-2022-13841)||高危|
|lodash<4.17.17 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13842](https://www.oscs1024.com/hd/MPS-2022-13842)||高危|
|node-forge <1.0.0 存在原型污染漏洞|原型污染|[MPS-2022-13920](https://www.oscs1024.com/hd/MPS-2022-13920)||中危|
|node-sass 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13927](https://www.oscs1024.com/hd/MPS-2022-13927)||中危|
|tar 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2022-14081](https://www.oscs1024.com/hd/MPS-2022-14081)||低危|
|uglify-js <3.14.3 正则表达式拒绝服务漏洞|ReDoS|[MPS-2022-14112](https://www.oscs1024.com/hd/MPS-2022-14112)||中危|
|laravel/framework 存在动态确定对象属性修改的控制不恰当漏洞||[MPS-2022-14284](https://www.oscs1024.com/hd/MPS-2022-14284)||中危|
|laravel/framework 存在SQL注入漏洞|SQL注入|[MPS-2022-14285](https://www.oscs1024.com/hd/MPS-2022-14285)||高危|
|laravel/framework 存在密码学问题漏洞|密码学问题|[MPS-2022-14287](https://www.oscs1024.com/hd/MPS-2022-14287)||中危|
|laravel/framework 存在输入验证不恰当漏洞|输入验证不恰当|[MPS-2022-14288](https://www.oscs1024.com/hd/MPS-2022-14288)||高危|
|Sensio Labs Twig 代码代码注入漏洞|代码注入|[MPS-2022-2041](https://www.oscs1024.com/hd/MPS-2022-2041)|CVE-2022-23614|严重|
|url-parse 存在访问限制绕过漏洞|通过用户控制密钥绕过授权机制|[MPS-2022-3327](https://www.oscs1024.com/hd/MPS-2022-3327)|CVE-2022-0512|中危|
|follow-redirects<1.14.8 信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-3636](https://www.oscs1024.com/hd/MPS-2022-3636)|CVE-2022-0536|中危|
|node-forge 密码签名验证不当漏洞|密码学签名的验证不恰当|[MPS-2022-3738](https://www.oscs1024.com/hd/MPS-2022-3738)|CVE-2022-24771|高危|
|node-forge 密码签名验证不当漏洞|密码学签名的验证不恰当|[MPS-2022-3739](https://www.oscs1024.com/hd/MPS-2022-3739)|CVE-2022-24772|高危|
|node-forge 密码签名验证不当漏洞|密码学签名的验证不恰当|[MPS-2022-3740](https://www.oscs1024.com/hd/MPS-2022-3740)|CVE-2022-24773|中危|
|PSR-7 Message Implementation 输入验证错误漏洞|输入验证不恰当|[MPS-2022-3742](https://www.oscs1024.com/hd/MPS-2022-3742)|CVE-2022-24775|高危|
|Moment.js 路径遍历漏洞|路径遍历|[MPS-2022-3752](https://www.oscs1024.com/hd/MPS-2022-3752)|CVE-2022-24785|中危|
|Sensio Labs Symfony 授权问题漏洞|授权机制不恰当|[MPS-2022-3861](https://www.oscs1024.com/hd/MPS-2022-3861)|CVE-2022-24894|高危|
|Express 中的 qs 模块存在原型污染漏洞|原型污染|[MPS-2022-3967](https://www.oscs1024.com/hd/MPS-2022-3967)|CVE-2022-24999|高危|
|url-parse <1.5.7 存在密钥授权绕过漏洞|通过用户控制密钥绕过授权机制|[MPS-2022-4297](https://www.oscs1024.com/hd/MPS-2022-4297)|CVE-2022-0639|中危|
|NPM url-parse授权绕过漏洞||[MPS-2022-4464](https://www.oscs1024.com/hd/MPS-2022-4464)|CVE-2022-0686|严重|
|Url-parse <1.5.9 存在输入验证不当漏洞||[MPS-2022-4474](https://www.oscs1024.com/hd/MPS-2022-4474)|CVE-2022-0691|严重|
|scss-tokenizer 安全漏洞|ReDoS|[MPS-2022-5119](https://www.oscs1024.com/hd/MPS-2022-5119)|CVE-2022-25758|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|loader-utils 安全漏洞|不正确的正则表达式|[MPS-2022-53512](https://www.oscs1024.com/hd/MPS-2022-53512)|CVE-2022-37599|高危|
|loader-utils 安全漏洞|不正确的正则表达式|[MPS-2022-53516](https://www.oscs1024.com/hd/MPS-2022-53516)|CVE-2022-37603|高危|
|decode-uri-component <=0.2.0 存在输入验证不当漏洞|拒绝服务|[MPS-2022-56259](https://www.oscs1024.com/hd/MPS-2022-56259)|CVE-2022-38900|高危|
|Sensio Labs Twig路径遍历漏洞|路径遍历|[MPS-2022-58285](https://www.oscs1024.com/hd/MPS-2022-58285)|CVE-2022-39261|高危|
|minimatch 资源管理错误漏洞|拒绝服务|[MPS-2022-59845](https://www.oscs1024.com/hd/MPS-2022-59845)|CVE-2022-3517|高危|
|Tauri 原型污染漏洞|原型污染|[MPS-2022-65568](https://www.oscs1024.com/hd/MPS-2022-65568)|CVE-2022-46175|高危|
|needle 存在Authorization请求头泄露漏洞|未授权敏感信息泄露|[MPS-2022-7866](https://www.oscs1024.com/hd/MPS-2022-7866)||中危|
|Guzzle 信息泄露漏洞|在信任Cookie未进行验证与完整性检查|[MPS-2022-8649](https://www.oscs1024.com/hd/MPS-2022-8649)|CVE-2022-29248|高危|
|tough-cookie 安全漏洞|原型污染|[MPS-2023-5130](https://www.oscs1024.com/hd/MPS-2023-5130)|CVE-2023-26136|严重|
|request SSRF防御绕过漏洞|SSRF|[MPS-2023-7722](https://www.oscs1024.com/hd/MPS-2023-7722)|CVE-2023-28155|中危|
|PSR-7 Message Implementation 安全漏洞|解释冲突|[MPS-2023-9403](https://www.oscs1024.com/hd/MPS-2023-9403)|CVE-2023-29197|高危|
|Laminas Project diactoros 输入验证错误漏洞|输入验证不恰当|[MPS-2023-9897](https://www.oscs1024.com/hd/MPS-2023-9897)|CVE-2023-29530|中危|
|tough-cookie<4.1.3 存在原型污染漏洞|原型污染|[MPS-esyq-56vx](https://www.oscs1024.com/hd/MPS-esyq-56vx)||中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|twig/twig|v2.13.1|3.4.3|间接依赖|强烈建议修复|C:1|H:1|M:0|L:0|
|laravel/framework|v5.7.29|8.83.24|间接依赖|强烈建议修复|C:3|H:3|M:3|L:0|
|eventsource|0.1.6|2.0.2|间接依赖|强烈建议修复|C:1|H:0|M:0|L:0|
|tough-cookie|2.4.3|4.1.3|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|path-parse|1.0.6|1.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|json5|1.0.1|2.2.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|url-parse|1.4.7|1.5.9|间接依赖|建议修复|C:2|H:0|M:4|L:0|
|decode-uri-component|0.2.0|0.2.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|node-forge|0.7.5|1.3.0|间接依赖|建议修复|C:0|H:3|M:3|L:0|
|webpack-dev-server|2.11.5|3.1.11|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|minimatch|3.0.4|3.0.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|serialize-javascript|1.7.0|3.1.0|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|y18n|4.0.0|5.0.5|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|glob-parent|3.1.0|6.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|acorn|5.7.3|7.1.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|ssri|5.3.0|8.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|y18n|3.2.1|5.0.5|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|trim-newlines|1.0.0|4.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|object-path|0.9.2|0.11.8|间接依赖|建议修复|C:1|H:1|M:0|L:0|
|is-svg|2.1.0|4.3.0|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|league/flysystem|1.0.70|2.1.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|elliptic|6.4.1|6.5.4|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|minimist|0.0.8|1.2.6|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|guzzlehttp/psr7|1.8.1|2.4.5|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|jquery|3.4.1|3.5.0|直接依赖|建议修复|C:0|H:0|M:2|L:0|
|chart.js|2.9.3|2.9.4|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|websocket-extensions|0.1.3|0.1.4|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|qs|6.5.2|6.10.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tar|2.2.2|6.1.9|间接依赖|建议修复|C:0|H:3|M:0|L:0|
|minimist|0.1.0|1.2.6|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|axios|0.19.0|0.21.3|直接依赖|建议修复|C:0|H:1|M:1|L:0|
|tar|4.4.8|6.1.9|间接依赖|建议修复|C:0|H:5|M:0|L:1|
|json5|0.5.1|2.2.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|mixin-deep|1.3.1|2.0.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|ansi-html|0.0.7|0.0.8|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|http-signature|1.2.0||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|lodash|4.17.13|4.17.21|直接依赖|建议修复|C:0|H:4|M:1|L:0|
|scss-tokenizer|0.2.3|0.4.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|node-sass|4.12.0|7.0.0|间接依赖|建议修复|C:1|H:4|M:13|L:0|
|sockjs|0.3.19|0.3.20|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|minimist|1.2.0|1.2.6|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|loader-utils|1.2.3|3.2.1|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|ini|1.3.5|1.3.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|js-yaml|3.7.0|3.13.1|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|json-schema|0.2.3|0.4.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|express|4.16.4|4.17.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|guzzlehttp/guzzle|6.5.5|7.4.5|间接依赖|建议修复|C:0|H:5|M:0|L:0|
|semver|5.7.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|async|2.6.2|3.2.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|lcobucci/jwt|3.4.5|4.1.5|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|follow-redirects|1.7.0|1.14.8|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|symfony/http-kernel|v4.4.21|6.2.6|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|yargs-parser|5.0.0|18.1.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|postcss|6.0.23|8.2.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|postcss|5.2.18|8.2.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|node-notifier|5.4.0|9.0.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|moment|2.24.0|2.29.4|直接依赖|可选修复|C:0|H:1|M:1|L:0|
|kind-of|6.0.2|6.0.3|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|postcss|7.0.16|8.2.13|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|mem|1.1.0|4.0.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|uglify-js|3.4.10|3.14.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|uglify-js|2.8.29|3.14.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|needle|2.3.1|3.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|hosted-git-info|2.7.1|3.0.8|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|yargs-parser|13.1.0|18.1.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|request|2.88.0||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|dns-packet|1.3.1|5.2.4|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|5.3.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|ajv|6.10.0|6.12.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|follow-redirects|1.5.10|1.14.8|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|yargs-parser|7.0.0|18.1.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|ajv|5.5.2|6.12.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|http-proxy|1.17.0|1.18.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|ISC|87|Low|
|MIT|838|Low|
|BSD|2|Low|
|BSD-3-Clause|22|Low|
|CC-BY-4.0|2|Low|
|BSD-2-Clause|16|Low|
|Apache-2.0|17|Low|
|BSD-4-Clause|4|Low|
|Unlicense|1|Low|
|LGPL-2.0|2|Medium|
|Apache 2|1|Low|
|自定义许可证|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|webpack-notifier|1.7.0|间接依赖|npm|
|nan|2.13.2|间接依赖|npm|
|resolve-cwd|2.0.0|间接依赖|npm|
|uglifyjs-webpack-plugin|0.4.6|间接依赖|npm|
|symfony/polyfill-intl-idn|v1.22.1|间接依赖|composer|
|nanomatch|1.2.13|间接依赖|npm|
|find-up|1.1.2|间接依赖|npm|
|opn|5.5.0|间接依赖|npm|
|is-descriptor|0.1.6|间接依赖|npm|
|bugsnag/bugsnag|v3.26.0|间接依赖|composer|
|mime|1.4.1|间接依赖|npm|
|wide-align|1.1.3|间接依赖|npm|
|randomfill|1.0.4|间接依赖|npm|
|ipaddr.js|1.9.0|间接依赖|npm|
|loud-rejection|1.6.0|间接依赖|npm|
|compression|1.7.4|间接依赖|npm|
|npm-run-path|2.0.2|间接依赖|npm|
|chartjs-color-string|0.6.0|间接依赖|npm|
|sshpk|1.16.1|间接依赖|npm|
|graham-campbell/exceptions|v11.3.0|间接依赖|composer|
|aws4|1.8.0|间接依赖|npm|
|ip|1.1.5|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|illuminate/pipeline||间接依赖|composer|
|ansi-styles|2.2.1|间接依赖|npm|
|sort-keys|1.1.2|间接依赖|npm|
|symfony/event-dispatcher|v4.4.20|间接依赖|composer|
|composer/ca-bundle|1.2.9|间接依赖|composer|
|which-module|2.0.0|间接依赖|npm|
|strip-ansi|4.0.0|间接依赖|npm|
|regenerator-transform|0.10.1|间接依赖|npm|
|adjust-sourcemap-loader|1.2.0|间接依赖|npm|
|querystringify|2.1.1|间接依赖|npm|
|babel-loader|7.1.5|间接依赖|npm|
|chart.js|2.9.3|直接依赖|npm|
|on-finished|2.3.0|间接依赖|npm|
|align-text|0.1.4|间接依赖|npm|
|strip-ansi|5.2.0|间接依赖|npm|
|normalize-range|0.1.2|间接依赖|npm|
|bootstrap-sass|3.4.1|直接依赖|npm|
|mem|4.3.0|间接依赖|npm|
|commander|2.13.0|间接依赖|npm|
|bcrypt-pbkdf|1.0.2|间接依赖|npm|
|graham-campbell/security-core|v1.0.3|间接依赖|composer|
|yargs|8.0.2|间接依赖|npm|
|cacache|10.0.4|间接依赖|npm|
|babel-plugin-syntax-trailing-function-commas|6.22.0|间接依赖|npm|
|lodash.assign|3.2.0|间接依赖|npm|
|parse-asn1|5.1.4|间接依赖|npm|
|asap|2.0.6|间接依赖|npm|
|babel-code-frame|6.26.0|间接依赖|npm|
|dns-txt|2.0.2|间接依赖|npm|
|symfony/http-client-contracts|v1.1.10|间接依赖|composer|
|moment|2.24.0|直接依赖|npm|
|path-exists|2.1.0|间接依赖|npm|
|chownr|1.1.1|间接依赖|npm|
|node-gyp|3.8.0|间接依赖|npm|
|path-is-inside|1.0.2|间接依赖|npm|
|babel-plugin-transform-es2015-computed-properties|6.24.1|间接依赖|npm|
|color-name|1.1.4|间接依赖|npm|
|strip-json-comments|2.0.1|间接依赖|npm|
|snapdragon-util|3.0.1|间接依赖|npm|
|has-flag|1.0.0|间接依赖|npm|
|http-parser-js|0.5.0|间接依赖|npm|
|are-we-there-yet|1.1.5|间接依赖|npm|
|barryvdh/laravel-cors|v0.11.4|间接依赖|composer|
|core-util-is|1.0.2|间接依赖|npm|
|prepend-http|1.0.4|间接依赖|npm|
|encodeurl|1.0.2|间接依赖|npm|
|convert-source-map|1.6.0|间接依赖|npm|
|kind-of|6.0.2|间接依赖|npm|
|lodash.uniq|4.5.0|间接依赖|npm|
|psr/container|1.0.0|间接依赖|composer|
|camelcase|1.2.1|间接依赖|npm|
|sass-graph|2.2.4|间接依赖|npm|
|yargs-parser|13.1.0|间接依赖|npm|
|jsprim|1.4.1|间接依赖|npm|
|fs-minipass|1.2.5|间接依赖|npm|
|uniq|1.0.1|间接依赖|npm|
|for-own|1.0.0|间接依赖|npm|
|chillerlan/php-qrcode|2.0.8|间接依赖|composer|
|form-data|2.3.3|间接依赖|npm|
|del|3.0.0|间接依赖|npm|
|multicast-dns-service-types|1.1.0|间接依赖|npm|
|babel-plugin-transform-async-to-generator|6.24.1|间接依赖|npm|
|concat-stream|1.6.2|间接依赖|npm|
|execa|1.0.0|间接依赖|npm|
|caniuse-db|1.0.30000967|间接依赖|npm|
|purgecss|1.3.0|间接依赖|npm|
|jenssegers/date|v3.5.0|间接依赖|composer|
|extglob|2.0.4|间接依赖|npm|
|universalify|0.1.2|间接依赖|npm|
|block-stream|0.0.9|间接依赖|npm|
|mime|1.6.0|间接依赖|npm|
|predis/predis|v1.1.6|间接依赖|composer|
|doctrine/lexer|1.0.2|间接依赖|composer|
|schema-utils|0.3.0|间接依赖|npm|
|watchpack|1.6.0|间接依赖|npm|
|spdx-expression-parse|3.0.0|间接依赖|npm|
|es6-map|0.1.5|间接依赖|npm|
|setimmediate|1.0.5|间接依赖|npm|
|babel-plugin-transform-es2015-modules-umd|6.24.1|间接依赖|npm|
|get-stdin|4.0.1|间接依赖|npm|
|url-parse|1.4.7|间接依赖|npm|
|object-path|0.9.2|间接依赖|npm|
|y18n|4.0.0|间接依赖|npm|
|trim-newlines|1.0.0|间接依赖|npm|
|extend-shallow|2.0.1|间接依赖|npm|
|json-parse-better-errors|1.0.2|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|babel-template|6.26.0|间接依赖|npm|
|illuminate/events||间接依赖|composer|
|send|0.16.2|间接依赖|npm|
|neo-async|2.6.0|间接依赖|npm|
|minimatch|3.0.4|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|time-stamp|2.2.0|间接依赖|npm|
|path-browserify|0.0.0|间接依赖|npm|
|fastparse|1.1.2|间接依赖|npm|
|laravel/framework|v5.7.29|间接依赖|composer|
|path-is-absolute|1.0.1|间接依赖|npm|
|use|3.1.1|间接依赖|npm|
|nopt|4.0.1|间接依赖|npm|
|inherits|2.0.1|间接依赖|npm|
|stdout-stream|1.4.1|间接依赖|npm|
|eventemitter3|3.1.2|间接依赖|npm|
|path-parse|1.0.6|间接依赖|npm|
|source-map-resolve|0.5.2|间接依赖|npm|
|animate-sass|0.8.2|直接依赖|npm|
|strip-eof|1.0.0|间接依赖|npm|
|next-tick|1.0.0|间接依赖|npm|
|browserify-cipher|1.0.1|间接依赖|npm|
|fideloper/proxy|4.4.1|间接依赖|composer|
|vue-hot-reload-api|2.3.3|间接依赖|npm|
|negotiator|0.6.2|间接依赖|npm|
|symfony/http-foundation|v4.4.20|间接依赖|composer|
|psr/simple-cache|1.0.1|间接依赖|composer|
|osenv|0.1.5|间接依赖|npm|
|es-to-primitive|1.2.0|间接依赖|npm|
|is-extendable|0.1.1|间接依赖|npm|
|babel-plugin-syntax-object-rest-spread|6.13.0|间接依赖|npm|
|browserslist|1.7.7|间接依赖|npm|
|fs-write-stream-atomic|1.0.10|间接依赖|npm|
|stream-browserify|2.0.2|间接依赖|npm|
|babel-helper-remap-async-to-generator|6.24.1|间接依赖|npm|
|postcss-merge-rules|2.1.2|间接依赖|npm|
|mime-db|1.40.0|间接依赖|npm|
|lcid|1.0.0|间接依赖|npm|
|get-stream|3.0.0|间接依赖|npm|
|csso|2.3.2|间接依赖|npm|
|php-http/promise|1.1.0|间接依赖|composer|
|http-proxy|1.17.0|间接依赖|npm|
|browserify-rsa|4.0.1|间接依赖|npm|
|yargs|13.2.2|间接依赖|npm|
|clone-deep|2.0.2|间接依赖|npm|
|end-of-stream|1.4.1|间接依赖|npm|
|is-typedarray|1.0.0|间接依赖|npm|
|uglify-es|3.3.9|间接依赖|npm|
|from2|2.3.0|间接依赖|npm|
|rework-visit|1.0.0|间接依赖|npm|
|request|2.88.0|间接依赖|npm|
|fast-json-stable-stringify|2.0.0|间接依赖|npm|
|babel-plugin-transform-es2015-classes|6.24.1|间接依赖|npm|
|lodash.defaults|4.2.0|间接依赖|npm|
|right-align|0.1.3|间接依赖|npm|
|postcss-normalize-charset|1.1.1|间接依赖|npm|
|laravel/tinker|v1.0.10|间接依赖|composer|
|is-path-cwd|1.0.0|间接依赖|npm|
|friendly-errors-webpack-plugin|1.7.0|间接依赖|npm|
|debug|2.6.9|间接依赖|npm|
|pascalcase|0.1.1|间接依赖|npm|
|load-json-file|2.0.0|间接依赖|npm|
|readable-stream|3.3.0|间接依赖|npm|
|commander|2.19.0|间接依赖|npm|
|postcss-load-config|1.2.0|间接依赖|npm|
|symfony/debug|v4.4.20|间接依赖|composer|
|pseudomap|1.0.2|间接依赖|npm|
|browserslist|3.2.8|间接依赖|npm|
|babel-plugin-transform-exponentiation-operator|6.24.1|间接依赖|npm|
|es6-weak-map|2.0.2|间接依赖|npm|
|is-regex|1.0.4|间接依赖|npm|
|statuses|1.4.0|间接依赖|npm|
|ieee754|1.1.13|间接依赖|npm|
|hpack.js|2.1.6|间接依赖|npm|
|es6-iterator|2.0.3|间接依赖|npm|
|babel-helper-hoist-variables|6.24.1|间接依赖|npm|
|yargs-parser|7.0.0|间接依赖|npm|
|dns-packet|1.3.1|间接依赖|npm|
|browserify-aes|1.2.0|间接依赖|npm|
|lodash._createassigner|3.1.1|间接依赖|npm|
|commondir|1.0.1|间接依赖|npm|
|performance-now|2.1.0|间接依赖|npm|
|jquery-minicolors|2.1.10|直接依赖|npm|
|jakub-onderka/php-console-color|v0.2|间接依赖|composer|
|url|0.11.0|间接依赖|npm|
|sax|1.2.4|间接依赖|npm|
|setprototypeof|1.1.0|间接依赖|npm|
|debug|3.2.6|间接依赖|npm|
|define-property|1.0.0|间接依赖|npm|
|urix|0.1.0|间接依赖|npm|
|postcss-reduce-initial|1.0.1|间接依赖|npm|
|mtdowling/jmespath.php|2.6.0|间接依赖|composer|
|loader-runner|2.4.0|间接依赖|npm|
|fill-range|4.0.0|间接依赖|npm|
|split-string|3.1.0|间接依赖|npm|
|mixin-object|2.0.1|间接依赖|npm|
|to-regex|3.0.2|间接依赖|npm|
|pbkdf2|3.0.17|间接依赖|npm|
|babel-plugin-syntax-async-functions|6.13.0|间接依赖|npm|
|faye-websocket|0.11.1|间接依赖|npm|
|accepts|1.3.7|间接依赖|npm|
|is-symbol|1.0.2|间接依赖|npm|
|pify|2.3.0|间接依赖|npm|
|uglifyjs-webpack-plugin|1.3.0|间接依赖|npm|
|fragment-cache|0.2.1|间接依赖|npm|
|require-main-filename|2.0.0|间接依赖|npm|
|dashdash|1.14.1|间接依赖|npm|
|deep-equal|1.0.1|间接依赖|npm|
|slash|1.0.0|间接依赖|npm|
|source-map|0.5.7|间接依赖|npm|
|which|1.3.1|间接依赖|npm|
|builtin-status-codes|3.0.0|间接依赖|npm|
|media-typer|0.3.0|间接依赖|npm|
|babel-plugin-transform-es2015-destructuring|6.23.0|间接依赖|npm|
|binary-extensions|1.13.1|间接依赖|npm|
|invariant|2.2.4|间接依赖|npm|
|css|2.2.4|间接依赖|npm|
|globule|1.2.1|间接依赖|npm|
|flatten|1.0.2|间接依赖|npm|
|electron-to-chromium|1.3.133|间接依赖|npm|
|which-module|1.0.0|间接依赖|npm|
|killable|1.0.1|间接依赖|npm|
|laravel-mix|2.1.14|直接依赖|npm|
|fstream|1.0.12|间接依赖|npm|
|process|0.11.10|间接依赖|npm|
|class-utils|0.3.6|间接依赖|npm|
|symfony/http-kernel|v4.4.21|间接依赖|composer|
|growly|1.3.0|间接依赖|npm|
|array-unique|0.3.2|间接依赖|npm|
|uglify-js|3.4.10|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|getpass|0.1.7|间接依赖|npm|
|sockjs-client|1.1.5|间接依赖|npm|
|isarray|1.0.0|间接依赖|npm|
|postcss-ordered-values|2.2.3|间接依赖|npm|
|parse-json|4.0.0|间接依赖|npm|
|bluebird|3.5.4|间接依赖|npm|
|argparse|1.0.10|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|selfsigned|1.10.4|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|import-from|2.1.0|间接依赖|npm|
|p-map|1.2.0|间接依赖|npm|
|graham-campbell/binput|v6.2.0|间接依赖|composer|
|yargs|7.1.0|间接依赖|npm|
|ini|1.3.5|间接依赖|npm|
|camel-case|3.0.0|间接依赖|npm|
|etag|1.8.1|间接依赖|npm|
|pragmarx/google2fa|v5.0.0|间接依赖|composer|
|miller-rabin|4.0.1|间接依赖|npm|
|npm-packlist|1.4.1|间接依赖|npm|
|is-stream|1.1.0|间接依赖|npm|
|babel-types|6.26.0|间接依赖|npm|
|acorn|5.7.3|间接依赖|npm|
|doctrine/event-manager|1.1.1|间接依赖|composer|
|cross-spawn|6.0.5|间接依赖|npm|
|xtend|4.0.1|间接依赖|npm|
|remove-trailing-separator|1.1.0|间接依赖|npm|
|yallist|2.1.2|间接依赖|npm|
|graham-campbell/guzzle-factory|v3.0.4|间接依赖|composer|
|concat-map|0.0.1|间接依赖|npm|
|postcss-discard-duplicates|2.1.0|间接依赖|npm|
|postcss-discard-overridden|0.1.1|间接依赖|npm|
|vue-template-es2015-compiler|1.9.1|间接依赖|npm|
|illuminate/http||间接依赖|composer|
|async|1.5.2|间接依赖|npm|
|locate-path|3.0.0|间接依赖|npm|
|league/commonmark|1.5.8|间接依赖|composer|
|json-schema|0.2.3|间接依赖|npm|
|process-nextick-args|2.0.0|间接依赖|npm|
|string-width|1.0.2|间接依赖|npm|
|vary|1.1.2|间接依赖|npm|
|laravel-mix-purgecss|3.0.0|直接依赖|npm|
|bytes|3.0.0|间接依赖|npm|
|punycode|1.3.2|间接依赖|npm|
|babel-helper-replace-supers|6.24.1|间接依赖|npm|
|unique-filename|1.1.1|间接依赖|npm|
|mississippi|2.0.0|间接依赖|npm|
|nesbot/carbon|1.39.1|间接依赖|composer|
|original|1.0.2|间接依赖|npm|
|evp_bytestokey|1.0.3|间接依赖|npm|
|promise|7.3.1|直接依赖|npm|
|babel-plugin-transform-es2015-shorthand-properties|6.24.1|间接依赖|npm|
|babel-plugin-transform-es2015-block-scoped-functions|6.22.0|间接依赖|npm|
|bugsnag/bugsnag-psr-logger|v1.4.3|间接依赖|composer|
|num2fraction|1.2.2|间接依赖|npm|
|har-schema|2.0.0|间接依赖|npm|
|is-glob|4.0.1|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|ssri|5.3.0|间接依赖|npm|
|illuminate/view||间接依赖|composer|
|postcss-svgo|2.1.6|间接依赖|npm|
|symfony/css-selector|v4.4.20|间接依赖|composer|
|validate-npm-package-license|3.0.4|间接依赖|npm|
|pumpify|1.5.1|间接依赖|npm|
|html-loader|0.4.5|间接依赖|npm|
|mime-types|2.1.24|间接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|content-disposition|0.5.2|间接依赖|npm|
|select-hose|2.0.0|间接依赖|npm|
|domain-browser|1.2.0|间接依赖|npm|
|merge-descriptors|1.0.1|间接依赖|npm|
|babel-plugin-transform-strict-mode|6.24.1|间接依赖|npm|
|prettier|1.17.0|间接依赖|npm|
|colors|1.1.2|间接依赖|npm|
|globs|0.1.4|间接依赖|npm|
|kind-of|3.2.2|间接依赖|npm|
|read-pkg-up|1.0.1|间接依赖|npm|
|batch|0.6.1|间接依赖|npm|
|wbuf|1.7.3|间接依赖|npm|
|ionicons|2.0.1|直接依赖|npm|
|shebang-command|1.2.0|间接依赖|npm|
|whet.extend|0.9.9|间接依赖|npm|
|postcss-merge-idents|2.1.7|间接依赖|npm|
|tijsverkoyen/css-to-inline-styles|2.2.3|间接依赖|composer|
|brace-expansion|1.1.11|间接依赖|npm|
|asn1|0.2.4|间接依赖|npm|
|console-control-strings|1.1.0|间接依赖|npm|
|querystring-es3|0.2.1|间接依赖|npm|
|postcss-modules-local-by-default|1.2.0|间接依赖|npm|
|y18n|3.2.1|间接依赖|npm|
|true-case-path|1.0.3|间接依赖|npm|
|ansi-regex|3.0.0|间接依赖|npm|
|node-libs-browser|2.2.0|间接依赖|npm|
|extract-text-webpack-plugin|3.0.2|间接依赖|npm|
|resolve-from|3.0.0|间接依赖|npm|
|babel-register|6.26.0|间接依赖|npm|
|erusev/parsedown|1.7.4|间接依赖|composer|
|serve-index|1.9.1|间接依赖|npm|
|for-in|0.1.8|间接依赖|npm|
|yargs|6.6.0|间接依赖|npm|
|normalize-package-data|2.5.0|间接依赖|npm|
|debug|4.1.1|间接依赖|npm|
|compressible|2.0.17|间接依赖|npm|
|jakub-onderka/php-console-highlighter|v0.4|间接依赖|composer|
|snapdragon-node|2.1.1|间接依赖|npm|
|source-list-map|2.0.1|间接依赖|npm|
|postcss-convert-values|2.6.1|间接依赖|npm|
|babel-helper-regex|6.26.0|间接依赖|npm|
|pump|2.0.1|间接依赖|npm|
|babel-helper-optimise-call-expression|6.24.1|间接依赖|npm|
|shallow-clone|1.0.0|间接依赖|npm|
|p-locate|2.0.0|间接依赖|npm|
|es5-ext|0.10.50|间接依赖|npm|
|os-locale|2.1.0|间接依赖|npm|
|browserify-des|1.0.2|间接依赖|npm|
|globals|9.18.0|间接依赖|npm|
|fs-extra|3.0.1|间接依赖|npm|
|color|0.11.4|间接依赖|npm|
|uri-js|4.2.2|间接依赖|npm|
|stream-shift|1.0.0|间接依赖|npm|
|stream-each|1.2.3|间接依赖|npm|
|tweetnacl|0.14.5|间接依赖|npm|
|define-property|2.0.2|间接依赖|npm|
|jquery-sparkline|2.4.0|直接依赖|npm|
|relateurl|0.2.7|间接依赖|npm|
|fast-deep-equal|2.0.1|间接依赖|npm|
|yargs|1.2.6|间接依赖|npm|
|portfinder|1.0.20|间接依赖|npm|
|is-absolute-url|2.1.0|间接依赖|npm|
|core-js|2.6.5|间接依赖|npm|
|window-size|0.1.0|间接依赖|npm|
|eventsource|0.1.6|间接依赖|npm|
|kind-of|5.1.0|间接依赖|npm|
|babel-preset-env|1.7.0|间接依赖|npm|
|parallel-transform|1.1.0|间接依赖|npm|
|array-includes|3.0.3|间接依赖|npm|
|serialize-javascript|1.7.0|间接依赖|npm|
|clean-css|4.2.1|间接依赖|npm|
|postcss-load-plugins|2.3.0|间接依赖|npm|
|reduce-css-calc|1.3.0|间接依赖|npm|
|spdy|4.0.0|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|source-map|0.4.4|间接依赖|npm|
|punycode|1.4.1|间接依赖|npm|
|caseless|0.12.0|间接依赖|npm|
|path-exists|3.0.0|间接依赖|npm|
|doctrine/inflector|1.3.1|间接依赖|composer|
|symfony/polyfill-mbstring||间接依赖|composer|
|minizlib|1.2.1|间接依赖|npm|
|assert|1.5.0|间接依赖|npm|
|fsevents|1.2.9|直接依赖|npm|
|base64-js|1.3.0|间接依赖|npm|
|symfony/polyfill-php72|v1.22.1|间接依赖|composer|
|array-flatten|2.1.2|间接依赖|npm|
|cachethq/twitter|v3.0.0|间接依赖|composer|
|css-selector-tokenizer|0.7.1|间接依赖|npm|
|shebang-regex|1.0.0|间接依赖|npm|
|interpret|1.2.0|间接依赖|npm|
|vue-loader|13.7.3|间接依赖|npm|
|loose-envify|1.4.0|间接依赖|npm|
|babel-plugin-transform-es2015-unicode-regex|6.24.1|间接依赖|npm|
|normalize-path|2.1.1|间接依赖|npm|
|svgo|0.7.2|间接依赖|npm|
|to-fast-properties|1.0.3|间接依赖|npm|
|find-cache-dir|1.0.0|间接依赖|npm|
|mem|1.1.0|间接依赖|npm|
|hash-sum|1.0.2|间接依赖|npm|
|lcobucci/jwt|3.4.5|间接依赖|composer|
|camelcase-keys|2.1.0|间接依赖|npm|
|micromatch|3.1.10|间接依赖|npm|
|monolog/monolog|1.26.0|间接依赖|composer|
|ast-types|0.9.6|间接依赖|npm|
|cookie-signature|1.0.6|间接依赖|npm|
|query-string|4.3.4|间接依赖|npm|
|chillerlan/php-traits|1.1.13|间接依赖|composer|
|node-sass|4.12.0|间接依赖|npm|
|aws/aws-sdk-php|3.176.2|间接依赖|composer|
|yallist|3.0.3|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|stackframe|1.0.4|间接依赖|npm|
|globby|6.1.0|间接依赖|npm|
|imurmurhash|0.1.4|间接依赖|npm|
|home-or-tmp|2.0.0|间接依赖|npm|
|emoji-regex|7.0.3|间接依赖|npm|
|webpack-chunk-hash|0.4.0|间接依赖|npm|
|es5-shim|4.5.14|直接依赖|npm|
|websocket-driver|0.7.0|间接依赖|npm|
|iferr|0.1.5|间接依赖|npm|
|array-uniq|1.0.3|间接依赖|npm|
|serve-static|1.13.2|间接依赖|npm|
|cachethq/badger|v2.0.0|间接依赖|composer|
|symfony/polyfill-php56|v1.20.0|间接依赖|composer|
|tar|2.2.2|间接依赖|npm|
|symfony/translation-contracts|v1.1.10|间接依赖|composer|
|autoprefixer|7.2.6|间接依赖|npm|
|errno|0.1.7|间接依赖|npm|
|psr/log|1.1.3|间接依赖|composer|
|psy/psysh|v0.9.12|间接依赖|composer|
|pify|3.0.0|间接依赖|npm|
|set-blocking|2.0.0|间接依赖|npm|
|asm89/stack-cors|1.3.0|间接依赖|composer|
|braces|2.3.2|间接依赖|npm|
|is-path-inside|1.0.1|间接依赖|npm|
|camelcase|2.1.1|间接依赖|npm|
|get-caller-file|1.0.3|间接依赖|npm|
|require-from-string|1.2.1|间接依赖|npm|
|cross-spawn|5.1.0|间接依赖|npm|
|mimic-fn|1.2.0|间接依赖|npm|
|redent|1.0.0|间接依赖|npm|
|php-http/client-implementation||间接依赖|composer|
|consolidate|0.14.5|间接依赖|npm|
|is-fullwidth-code-point|2.0.0|间接依赖|npm|
|vue-template-compiler|2.6.10|直接依赖|npm|
|symfony/event-dispatcher-contracts|v1.1.9|间接依赖|composer|
|string_decoder|1.1.1|间接依赖|npm|
|camelcase|4.1.0|间接依赖|npm|
|assert-plus|1.0.0|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|upper-case|1.1.3|间接依赖|npm|
|deep-extend|0.6.0|间接依赖|npm|
|js-yaml|3.13.1|间接依赖|npm|
|flush-write-stream|1.1.1|间接依赖|npm|
|crypt|0.0.2|间接依赖|npm|
|postcss-modules-values|1.3.0|间接依赖|npm|
|chalk|1.1.3|间接依赖|npm|
|ecc-jsbn|0.1.2|间接依赖|npm|
|babel-plugin-transform-es2015-literals|6.22.0|间接依赖|npm|
|is-path-in-cwd|1.0.1|间接依赖|npm|
|make-dir|1.3.0|间接依赖|npm|
|postcss-minify-gradients|1.0.5|间接依赖|npm|
|cosmiconfig|2.2.2|间接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|faye-websocket|0.10.0|间接依赖|npm|
|ripemd160|2.0.2|间接依赖|npm|
|postcss-minify-font-values|1.0.5|间接依赖|npm|
|psl|1.1.31|间接依赖|npm|
|os-homedir|1.0.2|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|mixin-deep|1.3.1|间接依赖|npm|
|pkg-dir|2.0.0|间接依赖|npm|
|async-foreach|0.1.3|间接依赖|npm|
|cross-spawn|3.0.1|间接依赖|npm|
|multicast-dns|6.2.3|间接依赖|npm|
|caniuse-lite|1.0.30000967|间接依赖|npm|
|babel-core|6.26.3|间接依赖|npm|
|verror|1.10.0|间接依赖|npm|
|memory-fs|0.4.1|间接依赖|npm|
|center-align|0.1.3|间接依赖|npm|
|assign-symbols|1.0.0|间接依赖|npm|
|babel-helper-explode-assignable-expression|6.24.1|间接依赖|npm|
|follow-redirects|1.7.0|间接依赖|npm|
|alphanum-sort|1.0.2|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|psr/http-message|1.0.1|间接依赖|composer|
|pako|1.0.10|间接依赖|npm|
|paragonie/random_compat||间接依赖|composer|
|postcss-message-helpers|2.0.0|间接依赖|npm|
|source-map-support|0.4.18|间接依赖|npm|
|unpipe|1.0.0|间接依赖|npm|
|arr-diff|4.0.0|间接依赖|npm|
|symfony/polyfill-php80|v1.22.1|间接依赖|composer|
|babel-plugin-transform-es2015-for-of|6.23.0|间接依赖|npm|
|illuminate/bus||间接依赖|composer|
|symfony/polyfill-php73|v1.22.1|间接依赖|composer|
|cssnano|3.10.0|间接依赖|npm|
|is-glob|3.1.0|间接依赖|npm|
|path-to-regexp|0.1.7|间接依赖|npm|
|babel-plugin-transform-es2015-modules-commonjs|6.26.2|间接依赖|npm|
|postcss-load-options|1.2.0|间接依赖|npm|
|json5|0.5.1|间接依赖|npm|
|babel-helper-define-map|6.26.0|间接依赖|npm|
|babel-plugin-transform-es2015-spread|6.22.0|间接依赖|npm|
|handle-thing|2.0.0|间接依赖|npm|
|find-up|3.0.0|间接依赖|npm|
|balanced-match|0.4.2|间接依赖|npm|
|create-ecdh|4.0.3|间接依赖|npm|
|safe-regex|1.1.0|间接依赖|npm|
|ansi-html|0.0.7|间接依赖|npm|
|date-now|0.1.4|间接依赖|npm|
|require-from-string|2.0.2|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|dotenv|4.0.0|间接依赖|npm|
|source-map-url|0.4.0|间接依赖|npm|
|readdirp|2.2.1|间接依赖|npm|
|html-comment-regex|1.1.2|间接依赖|npm|
|npm-bundled|1.0.6|间接依赖|npm|
|atob|2.1.2|间接依赖|npm|
|through|2.3.8|间接依赖|npm|
|postcss-discard-empty|2.1.0|间接依赖|npm|
|babel-helper-call-delegate|6.24.1|间接依赖|npm|
|es6-set|0.1.5|间接依赖|npm|
|symfony/translation|v4.4.21|间接依赖|composer|
|http-errors|1.6.3|间接依赖|npm|
|postcss-discard-comments|2.0.4|间接依赖|npm|
|postcss-normalize-url|3.0.8|间接依赖|npm|
|js-tokens|3.0.2|间接依赖|npm|
|babel-messages|6.23.0|间接依赖|npm|
|asynckit|0.4.0|间接依赖|npm|
|co|4.6.0|间接依赖|npm|
|forever-agent|0.6.1|间接依赖|npm|
|node-pre-gyp|0.12.0|间接依赖|npm|
|delegates|1.0.0|间接依赖|npm|
|wordwrap|0.0.2|间接依赖|npm|
|upath|1.1.2|间接依赖|npm|
|object.pick|1.3.0|间接依赖|npm|
|param-case|2.1.1|间接依赖|npm|
|tunnel-agent|0.6.0|间接依赖|npm|
|guzzlehttp/guzzle|6.5.5|间接依赖|composer|
|alt-three/validator|v4.5.0|间接依赖|composer|
|async|2.6.2|间接依赖|npm|
|postcss-zindex|2.2.0|间接依赖|npm|
|parse-json|2.2.0|间接依赖|npm|
|regenerator-runtime|0.11.1|间接依赖|npm|
|gauge|2.7.4|间接依赖|npm|
|create-hmac|1.1.7|间接依赖|npm|
|mccool/laravel-auto-presenter|7.5.0|间接依赖|composer|
|css-color-names|0.0.4|间接依赖|npm|
|shellwords|0.1.1|间接依赖|npm|
|html-entities|1.2.1|间接依赖|npm|
|postcss-merge-longhand|2.0.2|间接依赖|npm|
|os-locale|1.4.0|间接依赖|npm|
|babel-plugin-transform-es2015-template-literals|6.22.0|间接依赖|npm|
|timers-browserify|2.0.10|间接依赖|npm|
|follow-redirects|1.5.10|间接依赖|npm|
|webpack-dev-server|2.11.5|间接依赖|npm|
|import-local|1.0.0|间接依赖|npm|
|esutils|2.0.2|间接依赖|npm|
|forwarded|0.1.2|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|read-pkg|1.1.0|间接依赖|npm|
|schema-utils|0.4.7|间接依赖|npm|
|postcss-unique-selectors|2.0.2|间接依赖|npm|
|tapable|0.2.9|间接依赖|npm|
|dnoegel/php-xdg-base-dir|v0.1.1|间接依赖|composer|
|uglify-to-browserify|1.0.2|直接依赖|npm|
|regexpu-core|1.0.0|间接依赖|npm|
|minimist|0.0.8|间接依赖|npm|
|lower-case|1.1.4|间接依赖|npm|
|league/flysystem|1.0.70|间接依赖|composer|
|define-properties|1.1.3|间接依赖|npm|
|symfony/polyfill-ctype|v1.22.1|间接依赖|composer|
|is-callable|1.1.4|间接依赖|npm|
|extend|3.0.2|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|json3|3.3.2|间接依赖|npm|
|os-browserify|0.3.0|间接依赖|npm|
|sweetalert2|6.11.5|直接依赖|npm|
|postcss-colormin|2.2.2|间接依赖|npm|
|acorn|4.0.13|间接依赖|npm|
|symfony/process|v4.4.20|间接依赖|composer|
|browserify-sign|4.0.4|间接依赖|npm|
|lodash.camelcase|4.3.0|间接依赖|npm|
|resolve|1.10.1|间接依赖|npm|
|estraverse|4.2.0|间接依赖|npm|
|livestamp|2.0.0|直接依赖|npm|
|path-key|2.0.1|间接依赖|npm|
|string_decoder|1.2.0|间接依赖|npm|
|aproba|1.2.0|间接依赖|npm|
|md5|2.2.1|间接依赖|npm|
|is-svg|2.1.0|间接依赖|npm|
|repeat-string|1.6.1|间接依赖|npm|
|console-browserify|1.1.0|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|img-loader|3.0.1|间接依赖|npm|
|find-up|2.1.0|间接依赖|npm|
|import-cwd|2.1.0|间接依赖|npm|
|glob|7.1.4|间接依赖|npm|
|babel-plugin-transform-es2015-modules-amd|6.24.1|间接依赖|npm|
|jsesc|1.3.0|间接依赖|npm|
|rework|1.0.1|间接依赖|npm|
|constants-browserify|1.0.0|间接依赖|npm|
|ms|2.1.1|间接依赖|npm|
|json-stringify-safe|5.0.1|间接依赖|npm|
|babel-plugin-transform-es2015-object-super|6.24.1|间接依赖|npm|
|json5|1.0.1|间接依赖|npm|
|swiftmailer/swiftmailer|v6.2.7|间接依赖|composer|
|symfony/polyfill-iconv|v1.22.1|间接依赖|composer|
|is-wsl|1.1.0|间接依赖|npm|
|postcss-value-parser|3.3.1|间接依赖|npm|
|postcss|6.0.23|间接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|cross-env|5.2.0|直接依赖|npm|
|defined|1.0.0|间接依赖|npm|
|json-loader|0.5.7|间接依赖|npm|
|lru-cache|4.1.5|间接依赖|npm|
|chokidar|2.1.5|间接依赖|npm|
|jsesc|0.5.0|间接依赖|npm|
|path-dirname|1.0.2|间接依赖|npm|
|elliptic|6.4.1|间接依赖|npm|
|async-each|1.0.3|间接依赖|npm|
|path-type|2.0.0|间接依赖|npm|
|supports-color|4.5.0|间接依赖|npm|
|babel-plugin-transform-es2015-block-scoping|6.26.0|间接依赖|npm|
|postcss-modules-scope|1.1.0|间接依赖|npm|
|yargs-parser|5.0.0|间接依赖|npm|
|extsprintf|1.3.0|间接依赖|npm|
|cookie|0.3.1|间接依赖|npm|
|webpack-dev-middleware|1.12.2|间接依赖|npm|
|inherits|2.0.3|间接依赖|npm|
|illuminate/support||间接依赖|composer|
|color-convert|0.5.3|间接依赖|npm|
|methods|1.1.2|间接依赖|npm|
|symfony/polyfill-intl-normalizer|v1.22.1|间接依赖|composer|
|obuf|1.1.2|间接依赖|npm|
|caniuse-api|1.6.1|间接依赖|npm|
|postcss-load-config|2.0.0|间接依赖|npm|
|object-keys|1.1.1|间接依赖|npm|
|nexmo/client-core|1.8.1|间接依赖|composer|
|npmlog|4.1.2|间接依赖|npm|
|charenc|0.0.2|间接依赖|npm|
|crypto-browserify|3.12.0|间接依赖|npm|
|cipher-base|1.0.4|间接依赖|npm|
|autoprefixer|6.7.7|间接依赖|npm|
|jquery|3.4.1|直接依赖|npm|
|scss-tokenizer|0.2.3|间接依赖|npm|
|read-pkg|2.0.0|间接依赖|npm|
|lodash.defaults|3.1.2|间接依赖|npm|
|glob-all|3.1.0|间接依赖|npm|
|symfony/mime|v4.4.21|间接依赖|composer|
|cyclist|0.2.2|间接依赖|npm|
|node-notifier|5.4.0|间接依赖|npm|
|babel-plugin-transform-runtime|6.23.0|间接依赖|npm|
|event-emitter|0.3.5|间接依赖|npm|
|string-width|2.1.1|间接依赖|npm|
|stream-http|2.8.3|间接依赖|npm|
|through2|2.0.5|间接依赖|npm|
|he|1.2.0|间接依赖|npm|
|promise-inflight|1.0.1|间接依赖|npm|
|range-parser|1.2.1|间接依赖|npm|
|buffer|4.9.1|间接依赖|npm|
|babel-plugin-transform-object-rest-spread|6.26.0|间接依赖|npm|
|cliui|3.2.0|间接依赖|npm|
|babel-plugin-transform-es2015-modules-systemjs|6.24.1|间接依赖|npm|
|camelcase|5.3.1|间接依赖|npm|
|os-tmpdir|1.0.2|间接依赖|npm|
|js-base64|2.5.1|间接依赖|npm|
|combined-stream|1.0.8|间接依赖|npm|
|graceful-fs|4.1.15|直接依赖|npm|
|cachethq/emoji|v3.0.0|间接依赖|composer|
|source-map|0.6.1|间接依赖|npm|
|css-loader|0.28.11|间接依赖|npm|
|statuses|1.5.0|间接依赖|npm|
|laravel/nexmo-notification-channel|v1.0.1|间接依赖|composer|
|content-type|1.0.4|间接依赖|npm|
|duplexify|3.7.1|间接依赖|npm|
|illuminate/contracts||间接依赖|composer|
|querystring|0.2.0|间接依赖|npm|
|indexof|0.0.1|间接依赖|npm|
|twig/twig|v2.13.1|间接依赖|composer|
|gaze|1.1.3|间接依赖|npm|
|raw-body|2.3.3|间接依赖|npm|
|esrecurse|4.2.1|间接依赖|npm|
|has-unicode|2.0.1|间接依赖|npm|
|guzzlehttp/promises|1.4.1|间接依赖|composer|
|kylekatarnls/update-helper|1.2.1|间接依赖|composer|
|postcss-selector-parser|2.2.3|间接依赖|npm|
|lodash|4.17.13|直接依赖|npm|
|esprima|3.1.3|间接依赖|npm|
|cliui|4.1.0|间接依赖|npm|
|alt-three/bus|v4.5.0|间接依赖|composer|
|babel-plugin-transform-es2015-parameters|6.24.1|间接依赖|npm|
|vlucas/phpdotenv|v2.6.7|间接依赖|composer|
|array-union|1.0.2|间接依赖|npm|
|postcss-discard-unused|2.2.3|间接依赖|npm|
|number-is-nan|1.0.1|间接依赖|npm|
|babel-runtime|6.26.0|间接依赖|npm|
|move-concurrently|1.0.1|间接依赖|npm|
|anymatch|2.0.0|间接依赖|npm|
|has-ansi|2.0.0|间接依赖|npm|
|events|3.0.0|间接依赖|npm|
|repeating|2.0.1|间接依赖|npm|
|jsonfile|3.0.1|间接依赖|npm|
|finalhandler|1.1.1|间接依赖|npm|
|minimalistic-assert|1.0.1|间接依赖|npm|
|coa|1.0.4|间接依赖|npm|
|depd|1.1.2|间接依赖|npm|
|parseurl|1.3.3|间接依赖|npm|
|amdefine|1.0.1|间接依赖|npm|
|indent-string|2.1.0|间接依赖|npm|
|icss-utils|2.1.0|间接依赖|npm|
|nice-try|1.0.5|间接依赖|npm|
|cosmiconfig|4.0.0|间接依赖|npm|
|error-ex|1.3.2|间接依赖|npm|
|public-encrypt|4.0.3|间接依赖|npm|
|yargs|3.10.0|间接依赖|npm|
|chartjs-color|2.3.0|间接依赖|npm|
|bugsnag/bugsnag-laravel|v2.22.0|间接依赖|composer|
|has-flag|2.0.0|间接依赖|npm|
|http-proxy-middleware|0.19.1|间接依赖|npm|
|opis/closure|3.6.1|间接依赖|composer|
|bonjour|3.5.0|间接依赖|npm|
|babel-plugin-check-es2015-constants|6.22.0|间接依赖|npm|
|is-fullwidth-code-point|1.0.0|间接依赖|npm|
|load-json-file|1.1.0|间接依赖|npm|
|meow|3.7.0|间接依赖|npm|
|unique-slug|2.0.1|间接依赖|npm|
|read-pkg-up|2.0.0|间接依赖|npm|
|path-type|1.1.0|间接依赖|npm|
|is-plain-object|2.0.4|间接依赖|npm|
|vue|2.6.10|直接依赖|npm|
|postcss-reduce-transforms|1.0.4|间接依赖|npm|
|concatenate|0.0.2|间接依赖|npm|
|resolve-url|0.2.1|间接依赖|npm|
|create-hash|1.2.0|间接依赖|npm|
|type-is|1.6.18|间接依赖|npm|
|es6-templates|0.2.3|间接依赖|npm|
|browserslist|2.11.3|间接依赖|npm|
|babel-traverse|6.26.0|间接依赖|npm|
|camelcase|3.0.0|间接依赖|npm|
|is-date-object|1.0.1|间接依赖|npm|
|dragonmantank/cron-expression|v2.3.1|间接依赖|composer|
|tty-browserify|0.0.0|间接依赖|npm|
|decamelize|1.2.0|间接依赖|npm|
|yargs-parser|4.2.1|间接依赖|npm|
|paragonie/constant_time_encoding|v2.4.0|间接依赖|composer|
|lodash._baseassign|3.2.0|间接依赖|npm|
|copy-concurrently|1.0.5|间接依赖|npm|
|error-stack-parser|2.0.2|间接依赖|npm|
|isstream|0.1.2|间接依赖|npm|
|node-forge|0.7.5|间接依赖|npm|
|graham-campbell/markdown|v11.2.1|间接依赖|composer|
|postcss|7.0.16|间接依赖|npm|
|symfony/error-handler|v4.4.21|间接依赖|composer|
|util|0.11.1|间接依赖|npm|
|detect-libc|1.0.3|间接依赖|npm|
|iconv-lite|0.4.24|间接依赖|npm|
|es-abstract|1.13.0|间接依赖|npm|
|supports-color|6.1.0|间接依赖|npm|
|is-buffer|2.0.3|间接依赖|npm|
|proxy-addr|2.0.5|间接依赖|npm|
|sha.js|2.4.11|间接依赖|npm|
|composer-plugin-api||间接依赖|composer|
|vm-browserify|0.0.4|间接依赖|npm|
|reduce-function-call|1.0.2|间接依赖|npm|
|bn.js|4.11.8|间接依赖|npm|
|in-publish|2.0.0|间接依赖|npm|
|postcss-minify-params|1.2.2|间接依赖|npm|
|cache-base|1.0.1|间接依赖|npm|
|strip-bom|3.0.0|间接依赖|npm|
|postcss-calc|5.3.1|间接依赖|npm|
|browserify-zlib|0.2.0|间接依赖|npm|
|private|0.1.8|间接依赖|npm|
|requires-port|1.0.0|间接依赖|npm|
|mkdirp|0.5.1|间接依赖|npm|
|locate-path|2.0.0|间接依赖|npm|
|jquery-serializeobject|1.0.0|直接依赖|npm|
|lodash.memoize|4.1.2|间接依赖|npm|
|nikic/php-parser|v4.10.4|间接依赖|composer|
|guzzlehttp/psr7|1.8.1|间接依赖|composer|
|babel-plugin-syntax-exponentiation-operator|6.13.0|间接依赖|npm|
|ee-first|1.1.1|间接依赖|npm|
|sass-loader|6.0.7|间接依赖|npm|
|babel-helper-builder-binary-assignment-operator-visitor|6.24.1|间接依赖|npm|
|php-http/httplug|v1.1.0|间接依赖|composer|
|uuid|3.3.2|间接依赖|npm|
|ignore-walk|3.0.1|间接依赖|npm|
|http-signature|1.2.0|间接依赖|npm|
|postcss-selector-parser|6.0.2|间接依赖|npm|
|array-find-index|1.0.2|间接依赖|npm|
|semver|5.3.0|间接依赖|npm|
|lodash.tail|4.1.1|间接依赖|npm|
|map-cache|0.2.2|间接依赖|npm|
|strip-indent|1.0.1|间接依赖|npm|
|spdx-correct|3.1.0|间接依赖|npm|
|aws-sign2|0.7.0|间接依赖|npm|
|resolve-url-loader|2.3.2|间接依赖|npm|
|tar|4.4.8|间接依赖|npm|
|is-binary-path|1.0.1|间接依赖|npm|
|de-indent|1.0.2|间接依赖|npm|
|expand-brackets|2.1.4|间接依赖|npm|
|lodash.restparam|3.6.1|间接依赖|npm|
|ansi-regex|2.1.1|间接依赖|npm|
|thunky|1.0.3|间接依赖|npm|
|file-loader|0.11.2|间接依赖|npm|
|websocket-extensions|0.1.3|间接依赖|npm|
|escope|3.6.0|间接依赖|npm|
|for-in|1.0.2|间接依赖|npm|
|rimraf|2.6.3|间接依赖|npm|
|egulias/email-validator|2.1.25|间接依赖|composer|
|isexe|2.0.0|间接依赖|npm|
|emojis-list|2.1.0|间接依赖|npm|
|postcss-reduce-idents|2.4.0|间接依赖|npm|
|html-minifier|3.5.21|间接依赖|npm|
|component-emitter|1.3.0|间接依赖|npm|
|sockjs|0.3.19|间接依赖|npm|
|execa|0.7.0|间接依赖|npm|
|axios|0.19.0|直接依赖|npm|
|dotenv-expand|4.2.0|间接依赖|npm|
|uglify-js|2.8.29|间接依赖|npm|
|regjsgen|0.2.0|间接依赖|npm|
|ret|0.1.15|间接依赖|npm|
|balanced-match|1.0.0|间接依赖|npm|
|body-parser|1.18.3|间接依赖|npm|
|strip-ansi|3.0.1|间接依赖|npm|
|tough-cookie|2.4.3|间接依赖|npm|
|uniqs|2.0.0|间接依赖|npm|
|require-main-filename|1.0.1|间接依赖|npm|
|detect-node|2.0.4|间接依赖|npm|
|buffer-indexof|1.1.1|间接依赖|npm|
|zendframework/zend-diactoros|2.2.1|间接依赖|composer|
|pinkie|2.0.4|间接依赖|npm|
|randombytes|2.1.0|间接依赖|npm|
|to-regex-range|2.1.1|间接依赖|npm|
|is-windows|1.0.2|间接依赖|npm|
|minipass|2.3.5|间接依赖|npm|
|acorn-dynamic-import|2.0.2|间接依赖|npm|
|decode-uri-component|0.2.0|间接依赖|npm|
|utils-merge|1.0.1|间接依赖|npm|
|oauth-sign|0.9.0|间接依赖|npm|
|style-loader|0.18.2|间接依赖|npm|
|run-queue|1.0.3|间接依赖|npm|
|string-width|3.1.0|间接依赖|npm|
|minimist|0.1.0|间接依赖|npm|
|is-number|3.0.0|间接依赖|npm|
|babel-helpers|6.24.1|间接依赖|npm|
|array-flatten|1.1.1|间接依赖|npm|
|enhanced-resolve|3.4.1|间接依赖|npm|
|postcss-modules-extract-imports|1.2.1|间接依赖|npm|
|regenerate|1.4.0|间接依赖|npm|
|destroy|1.0.4|间接依赖|npm|
|delayed-stream|1.0.0|间接依赖|npm|
|vue-style-loader|3.1.2|间接依赖|npm|
|lazy-cache|1.0.4|间接依赖|npm|
|opencollective-postinstall|2.0.2|直接依赖|npm|
|postcss-loader|2.1.6|间接依赖|npm|
|debug|3.1.0|间接依赖|npm|
|symfony/console|v4.4.21|间接依赖|composer|
|map-obj|1.0.1|间接依赖|npm|
|base|0.11.2|间接依赖|npm|
|postcss-minify-selectors|2.1.1|间接依赖|npm|
|punycode|2.1.1|间接依赖|npm|
|no-case|2.3.2|间接依赖|npm|
|ajv-keywords|3.4.0|间接依赖|npm|
|php-http/guzzle6-adapter|v1.1.1|间接依赖|composer|
|https-browserify|1.0.0|间接依赖|npm|
|is-buffer|1.1.6|间接依赖|npm|
|arr-flatten|1.1.0|间接依赖|npm|
|define-property|0.2.5|间接依赖|npm|
|ralouphie/getallheaders|3.0.3|间接依赖|composer|
|ajv|6.10.0|间接依赖|npm|
|is-directory|0.3.1|间接依赖|npm|
|fresh|0.5.2|间接依赖|npm|
|js-yaml|3.7.0|间接依赖|npm|
|math-expression-evaluator|1.2.17|间接依赖|npm|
|nexmo/client|1.9.1|间接依赖|composer|
|prr|1.0.1|间接依赖|npm|
|to-arraybuffer|1.0.1|间接依赖|npm|
|ramsey/uuid|3.9.3|间接依赖|composer|
|regjsparser|0.1.5|间接依赖|npm|
|babel-plugin-transform-es2015-duplicate-keys|6.24.1|间接依赖|npm|
|repeat-element|1.1.3|间接依赖|npm|
|webpack-merge|4.2.1|间接依赖|npm|
|signal-exit|3.0.2|间接依赖|npm|
|escape-html|1.0.3|间接依赖|npm|
|is-finite|1.0.2|间接依赖|npm|
|express|4.16.4|间接依赖|npm|
|github-markdown-css|2.10.0|直接依赖|npm|
|jsbn|0.1.1|间接依赖|npm|
|messenger|1.5.0|直接依赖|npm|
|recast|0.11.23|间接依赖|npm|
|cssesc|0.1.0|间接依赖|npm|
|illuminate/container||间接依赖|composer|
|har-validator|5.1.3|间接依赖|npm|
|babel-plugin-transform-regenerator|6.26.0|间接依赖|npm|
|babel-plugin-transform-es2015-function-name|6.24.1|间接依赖|npm|
|postcss-filter-plugins|2.0.3|间接依赖|npm|
|dns-equal|1.0.0|间接依赖|npm|
|lodash.keys|3.1.2|间接依赖|npm|
|icss-replace-symbols|1.1.0|间接依赖|npm|
|rc|1.2.8|间接依赖|npm|
|laravel/slack-notification-channel|v1.0.3|间接依赖|composer|
|symfony/var-dumper|v4.4.21|间接依赖|composer|
|snapdragon|0.8.2|间接依赖|npm|
|loglevel|1.6.1|间接依赖|npm|
|sortablejs|1.9.0|直接依赖|npm|
|semver|5.7.0|间接依赖|npm|
|d|1.0.0|间接依赖|npm|
|symfony/service-contracts|v1.1.9|间接依赖|composer|
|supports-color|3.2.3|间接依赖|npm|
|normalize-url|1.9.1|间接依赖|npm|
|symfony/finder|v4.4.20|间接依赖|composer|
|qs|6.5.2|间接依赖|npm|
|md5.js|1.3.5|间接依赖|npm|
|readable-stream|2.3.6|间接依赖|npm|
|webpack|3.12.0|间接依赖|npm|
|connect-history-api-fallback|1.6.0|间接依赖|npm|
|minimist|1.2.0|间接依赖|npm|
|p-finally|1.0.0|间接依赖|npm|
|es6-symbol|3.1.1|间接依赖|npm|
|invert-kv|1.0.0|间接依赖|npm|
|needle|2.3.1|间接依赖|npm|
|fast-deep-equal|1.1.0|间接依赖|npm|
|babel-helper-function-name|6.24.1|间接依赖|npm|
|extend-shallow|3.0.2|间接依赖|npm|
|currently-unhandled|0.4.1|间接依赖|npm|
|hosted-git-info|2.7.1|间接依赖|npm|
|glob-parent|3.1.0|间接依赖|npm|
|webpack-sources|1.3.0|间接依赖|npm|
|flatpickr|4.5.7|直接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|babel-plugin-transform-es2015-typeof-symbol|6.23.0|间接依赖|npm|
|on-headers|1.0.2|间接依赖|npm|
|http-deceiver|1.2.7|间接依赖|npm|
|illuminate/console||间接依赖|composer|
|loader-utils|1.2.3|间接依赖|npm|
|lodash.assign|4.2.0|间接依赖|npm|
|pinkie-promise|2.0.1|间接依赖|npm|
|isobject|3.0.1|间接依赖|npm|
|detect-indent|4.0.0|间接依赖|npm|
|doctrine/cache|1.10.2|间接依赖|composer|
|function-bind|1.1.1|间接依赖|npm|
|iconv-lite|0.4.23|间接依赖|npm|
|commander|2.17.1|间接依赖|npm|
|ajv|5.5.2|间接依赖|npm|
|lcid|2.0.0|间接依赖|npm|
|regex-parser|2.2.10|间接依赖|npm|
|babel-generator|6.26.1|间接依赖|npm|
|worker-farm|1.7.0|间接依赖|npm|
|esprima|4.0.1|间接依赖|npm|
|buffer-from|1.1.1|间接依赖|npm|
|regex-not|1.0.2|间接依赖|npm|
|trim-right|1.0.1|间接依赖|npm|
|babel-plugin-transform-es2015-arrow-functions|6.22.0|间接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|indexes-of|1.0.1|间接依赖|npm|
|ms|2.0.0|间接依赖|npm|
|symfony/routing|v4.4.20|间接依赖|composer|
|util|0.10.3|间接依赖|npm|
|colormin|1.1.2|间接依赖|npm|
|typedarray|0.0.6|间接依赖|npm|
|regexpu-core|2.0.0|间接依赖|npm|
|cliui|2.1.0|间接依赖|npm|
|abbrev|1.1.1|间接依赖|npm|
|wrap-ansi|2.1.0|间接依赖|npm|
|babel-plugin-transform-es2015-sticky-regex|6.24.1|间接依赖|npm|
|supports-color|2.0.0|间接依赖|npm|
|cssesc|3.0.0|间接依赖|npm|
|graham-campbell/security|v6.2.0|间接依赖|composer|
|internal-ip|1.2.0|间接依赖|npm|
|diffie-hellman|5.0.3|间接依赖|npm|
|is-extendable|1.0.1|间接依赖|npm|
|postcss|5.2.18|间接依赖|npm|
|code-point-at|1.1.0|间接依赖|npm|
|psr/http-factory|1.0.1|间接依赖|composer|
|json-schema-traverse|0.3.1|间接依赖|npm|
|is-descriptor|1.0.2|间接依赖|npm|
|babel-helper-get-function-arity|6.24.1|间接依赖|npm|
|purgecss-webpack-plugin|1.5.0|间接依赖|npm|
|doctrine/dbal|v2.9.3|间接依赖|composer|
|convert-source-map|0.3.5|间接依赖|npm|
|big.js|5.2.2|间接依赖|npm|
|os-locale|3.1.0|间接依赖|npm|
|vendors|1.0.3|间接依赖|npm|
|babylon|6.18.0|间接依赖|npm|
|illuminate/pagination||间接依赖|composer|
|nopt|3.0.6|间接依赖|npm|
|spdy-transport|3.0.0|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)