# nodejs/node安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699854276108271616.svg)](https://www.murphysec.com/console/report/1699854275198107648/1699854276108271616)

仓库描述：Node.js JavaScript runtime :sparkles::turtle::rocket::sparkles:

仓库地址：[https://github.com/nodejs/node](https://github.com/nodejs/node)

| star：97532 | watch：2889 | fork：26810 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-08 02:30:00 | 许可证：NOASSERTION |
| 最近检测时间：2023-09-08 03:00:55 | 组件总数：368 | 漏洞总数：91 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|OpenSSL 安全漏洞|不安全的缺省变量初始化|[MPS-2007-4224](https://www.oscs1024.com/hd/MPS-2007-4224)|CVE-2007-3108|低危|
|Openssl Xilinx Virtex-II Pro FPGA 'Gaisler Research LEON3'openssl FWE算法设计漏洞|密码学问题|[MPS-2010-0702](https://www.oscs1024.com/hd/MPS-2010-0702)|CVE-2010-0928|中危|
|OpenSSL密码集降级安全漏洞|不安全的缺省变量初始化|[MPS-2010-4343](https://www.oscs1024.com/hd/MPS-2010-4343)|CVE-2010-4180|中危|
|OpenSSL OpenSSL实现加密问题漏洞|密码学问题|[MPS-2010-4350](https://www.oscs1024.com/hd/MPS-2010-4350)|CVE-2008-7270|中危|
|Opera 输入验证错误漏洞|加密强度不足|[MPS-2011-2667](https://www.oscs1024.com/hd/MPS-2011-2667)|CVE-2011-3389|中危|
|OpenSSL加密问题漏洞|密码学问题|[MPS-2012-0027](https://www.oscs1024.com/hd/MPS-2012-0027)|CVE-2011-4576|中危|
|OpenSSL资源管理错误漏洞|资源管理错误|[MPS-2012-0029](https://www.oscs1024.com/hd/MPS-2012-0029)|CVE-2011-4619|中危|
|OpenSSL资源管理错误漏洞|资源管理错误|[MPS-2012-0030](https://www.oscs1024.com/hd/MPS-2012-0030)|CVE-2012-0027|中危|
|OpenSSL  mime_hdr_cmp 函数拒绝服务漏洞|拒绝服务|[MPS-2012-0657](https://www.oscs1024.com/hd/MPS-2012-0657)|CVE-2006-7250|中危|
|OpenSSL加密问题漏洞|密码学问题|[MPS-2012-0826](https://www.oscs1024.com/hd/MPS-2012-0826)|CVE-2012-0884|中危|
|OpenSSL  mime_param_cmp  拒绝服务漏洞|资源管理错误|[MPS-2012-0877](https://www.oscs1024.com/hd/MPS-2012-0877)|CVE-2012-1165|中危|
|Juniper Network and Security Manager SSL会话重协商拒绝服务漏洞|权限、特权和访问控制|[MPS-2012-1902](https://www.oscs1024.com/hd/MPS-2012-1902)|CVE-2011-1473|中危|
|多个TLS/DTLS实现加密问题漏洞|密码学问题|[MPS-2013-0546](https://www.oscs1024.com/hd/MPS-2013-0546)|CVE-2013-0169|低危|
|OpenSSL 加密问题漏洞|密码学问题|[MPS-2013-0553](https://www.oscs1024.com/hd/MPS-2013-0553)|CVE-2012-2686|中危|
|TLS/SSL协议 RC4算法加密问题漏洞|加密强度不足|[MPS-2013-1069](https://www.oscs1024.com/hd/MPS-2013-1069)|CVE-2013-2566|中危|
|Dual Elliptic Curve Deterministic Random Bit Generation 安全漏洞|密码算法不安全|[MPS-2013-3961](https://www.oscs1024.com/hd/MPS-2013-3961)|CVE-2007-6755|中危|
|OpenSSL 安全漏洞|密码学问题|[MPS-2014-0001](https://www.oscs1024.com/hd/MPS-2014-0001)|CVE-2013-6450|中危|
|OpenSSL  ssl3_take_mac  函数输入验证漏洞|空指针取消引用|[MPS-2014-0085](https://www.oscs1024.com/hd/MPS-2014-0085)|CVE-2013-4353|中危|
|OpenSSL ECDSA 加密问题漏洞|密码学问题|[MPS-2014-1446](https://www.oscs1024.com/hd/MPS-2014-1446)|CVE-2014-0076|低危|
|OpenSSL 存在DROWN攻击漏洞|密码学问题|[MPS-2014-5713](https://www.oscs1024.com/hd/MPS-2014-5713)|CVE-2014-3566|低危|
|OpenSSL ssl23_get_client_hello() 函数拒绝服务漏洞|拒绝服务|[MPS-2014-7803](https://www.oscs1024.com/hd/MPS-2014-7803)|CVE-2014-3569|中危|
|OpenSSL 拒绝服务漏洞|空指针取消引用|[MPS-2015-0148](https://www.oscs1024.com/hd/MPS-2015-0148)|CVE-2014-3571|中危|
|OpenSSL rsa_item_verify 函数拒绝服务漏洞|拒绝服务|[MPS-2015-1483](https://www.oscs1024.com/hd/MPS-2015-1483)|CVE-2015-0208|中危|
|OpenSSL ssl3_write_bytes 函数拒绝服务漏洞|已弃用：代码|[MPS-2015-1490](https://www.oscs1024.com/hd/MPS-2015-1490)|CVE-2015-0290|中危|
|OpenSSL ssl3_get_client_key_exchange 函数拒绝服务漏洞|输入验证不恰当|[MPS-2015-1494](https://www.oscs1024.com/hd/MPS-2015-1494)|CVE-2015-1787|低危|
|RC4 加密问题漏洞|密码算法不安全|[MPS-2015-1654](https://www.oscs1024.com/hd/MPS-2015-1654)|CVE-2015-2808|中危|
|OpenSSL 缓冲区错误漏洞|缓冲区溢出|[MPS-2015-2812](https://www.oscs1024.com/hd/MPS-2015-2812)|CVE-2015-1789|高危|
|OpenSSL PKCS7_dataDecode 函数拒绝服务漏洞|拒绝服务|[MPS-2015-2813](https://www.oscs1024.com/hd/MPS-2015-2813)|CVE-2015-1790|中危|
|OpenSSL 安全漏洞|未授权敏感信息泄露|[MPS-2016-1063](https://www.oscs1024.com/hd/MPS-2016-1063)|CVE-2016-0702|中危|
|OpenSSL BIO_*printf 函数安全漏洞|缓冲区溢出|[MPS-2016-1067](https://www.oscs1024.com/hd/MPS-2016-1067)|CVE-2016-0799|严重|
|OpenSSL 安全漏洞|缓冲区溢出|[MPS-2016-1068](https://www.oscs1024.com/hd/MPS-2016-1068)|CVE-2016-2842|严重|
|OpenSSL 整数溢出漏洞|整数溢出或环绕|[MPS-2016-2081](https://www.oscs1024.com/hd/MPS-2016-2081)|CVE-2016-2105|高危|
|OpenSSL 整数溢出漏洞|数字错误|[MPS-2016-2082](https://www.oscs1024.com/hd/MPS-2016-2082)|CVE-2016-2106|高危|
|OpenSSL ASN.1实现拒绝服务漏洞|缓冲区溢出|[MPS-2016-2084](https://www.oscs1024.com/hd/MPS-2016-2084)|CVE-2016-2108|严重|
|OpenSSL ASN.1 BIO实现拒绝服务漏洞|资源管理错误|[MPS-2016-2085](https://www.oscs1024.com/hd/MPS-2016-2085)|CVE-2016-2109|高危|
|OpenSSL 拒绝服务漏洞|整数溢出或环绕|[MPS-2016-3031](https://www.oscs1024.com/hd/MPS-2016-3031)|CVE-2016-2177|严重|
|OpenSSL 安全漏洞|通过差异性导致的信息暴露|[MPS-2016-3032](https://www.oscs1024.com/hd/MPS-2016-3032)|CVE-2016-2178|中危|
|OpenSSL 信息泄露漏洞|未授权敏感信息泄露|[MPS-2016-4273](https://www.oscs1024.com/hd/MPS-2016-4273)|CVE-2016-2183|高危|
|OpenSSL 安全漏洞|资源管理错误|[MPS-2016-4537](https://www.oscs1024.com/hd/MPS-2016-4537)|CVE-2016-2179|高危|
|OpenSSL 拒绝服务漏洞|数字错误|[MPS-2016-4538](https://www.oscs1024.com/hd/MPS-2016-4538)|CVE-2016-2181|高危|
|OpenSSL BN_bn2dec() 函数拒绝服务漏洞|越界写入|[MPS-2016-4539](https://www.oscs1024.com/hd/MPS-2016-4539)|CVE-2016-2182|严重|
|OpenSSL 拒绝服务漏洞|越界读取|[MPS-2016-4840](https://www.oscs1024.com/hd/MPS-2016-4840)|CVE-2016-6306|中危|
|OpenSSL 存在拒绝服务漏洞|拒绝服务|[MPS-2017-12773](https://www.oscs1024.com/hd/MPS-2017-12773)|CVE-2016-8610|高危|
|OpenSSL 缓冲区错误漏洞|缓冲区溢出|[MPS-2017-9606](https://www.oscs1024.com/hd/MPS-2017-9606)|CVE-2017-3735|中危|
|rust-base64 缓冲区错误漏洞|缓冲区溢出|[MPS-2018-0042](https://www.oscs1024.com/hd/MPS-2018-0042)|CVE-2017-1000430|严重|
|OpenSSL 加密问题漏洞|密码算法不安全|[MPS-2018-14230](https://www.oscs1024.com/hd/MPS-2018-14230)|CVE-2018-0735|中危|
|OpenSSL 加密问题漏洞|密码算法不安全|[MPS-2018-14285](https://www.oscs1024.com/hd/MPS-2018-14285)|CVE-2018-0734|中危|
|OpenSSL 信息泄露漏洞|通过差异性导致的信息暴露|[MPS-2018-14899](https://www.oscs1024.com/hd/MPS-2018-14899)|CVE-2018-5407|中危|
|OpenSSL 资源管理错误漏洞|未经控制的递归|[MPS-2018-3750](https://www.oscs1024.com/hd/MPS-2018-3750)|CVE-2018-0739|中危|
|OpenSSL 加密问题漏洞|密码算法不安全|[MPS-2018-4731](https://www.oscs1024.com/hd/MPS-2018-4731)|CVE-2018-0737|中危|
|Openssl OpenSSL 加密问题漏洞|密钥管理错误|[MPS-2018-7822](https://www.oscs1024.com/hd/MPS-2018-7822)|CVE-2018-0732|高危|
|Libgcrypt 信息泄露漏洞|通过差异性导致的信息暴露|[MPS-2018-7926](https://www.oscs1024.com/hd/MPS-2018-7926)|CVE-2018-0495|中危|
|OpenSSL 安全漏洞|服务端安全的客户端实施|[MPS-2019-11271](https://www.oscs1024.com/hd/MPS-2019-11271)|CVE-2019-1547|中危|
|OpenSSL 安全漏洞||[MPS-2019-11273](https://www.oscs1024.com/hd/MPS-2019-11273)|CVE-2019-1563|低危|
|OpenSSL 输入验证错误漏洞|整数溢出或环绕|[MPS-2019-15892](https://www.oscs1024.com/hd/MPS-2019-15892)|CVE-2019-1551|中危|
|OpenSSL 信任管理问题漏洞|证书验证不恰当|[MPS-2019-8829](https://www.oscs1024.com/hd/MPS-2019-8829)|CVE-2019-1552|低危|
|OpenSSL 加密问题漏洞|通过差异性导致的信息暴露|[MPS-2020-12634](https://www.oscs1024.com/hd/MPS-2020-12634)|CVE-2020-1968|低危|
|OpenSSL 缓冲区错误漏洞|越界读取|[MPS-2021-17869](https://www.oscs1024.com/hd/MPS-2021-17869)|CVE-2021-3712|高危|
|OpenSSL 输入验证错误漏洞|输入验证不恰当|[MPS-2021-39449](https://www.oscs1024.com/hd/MPS-2021-39449)|CVE-2021-4160|中危|
|OpenSSL 存在任意命令执行漏洞|OS命令注入|[MPS-2022-18279](https://www.oscs1024.com/hd/MPS-2022-18279)|CVE-2022-2068|严重|
|OpenSSL 存在加密信息不全漏洞|加密强度不足|[MPS-2022-19044](https://www.oscs1024.com/hd/MPS-2022-19044)|CVE-2022-2097|高危|
|Certifi 存在数据真实性验证不充分漏洞|对数据真实性的验证不充分|[MPS-2022-1918](https://www.oscs1024.com/hd/MPS-2022-1918)|CVE-2022-23491|中危|
|OpenSSL RSA 远程代码执行漏洞|堆缓冲区溢出|[MPS-2022-26380](https://www.oscs1024.com/hd/MPS-2022-26380)|CVE-2022-2274|高危|
|Express 中的 qs 模块存在原型污染漏洞|原型污染|[MPS-2022-3967](https://www.oscs1024.com/hd/MPS-2022-3967)|CVE-2022-24999|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|OpenSSL 拒绝服务漏洞|不可达退出条件的循环（无限循环）|[MPS-2022-5555](https://www.oscs1024.com/hd/MPS-2022-5555)|CVE-2022-0778|高危|
|DHCP 服务器存在整数溢出漏洞|拒绝服务|[MPS-2022-55715](https://www.oscs1024.com/hd/MPS-2022-55715)|CVE-2022-2928|中危|
|DHCP 内存泄漏|通过错误消息导致的信息暴露|[MPS-2022-55716](https://www.oscs1024.com/hd/MPS-2022-55716)|CVE-2022-2929|中危|
|OpenSSL >= 3.0 栈缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-60525](https://www.oscs1024.com/hd/MPS-2022-60525)|CVE-2022-3602|高危|
|OpenSSL 3.0.X 存在远程代码执行漏洞|代码注入|[MPS-2022-62736](https://www.oscs1024.com/hd/MPS-2022-62736)||严重|
|OpenSSL >= 3.0 缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-62757](https://www.oscs1024.com/hd/MPS-2022-62757)|CVE-2022-3786|高危|
|OpenSSL 安全漏洞|加锁机制不恰当|[MPS-2022-64591](https://www.oscs1024.com/hd/MPS-2022-64591)|CVE-2022-3996|高危|
|OpenSSL 缓冲区错误漏洞|越界读取|[MPS-2022-65756](https://www.oscs1024.com/hd/MPS-2022-65756)|CVE-2022-4203|中危|
|OpenSSL 安全漏洞|通过差异性导致的信息暴露|[MPS-2022-66954](https://www.oscs1024.com/hd/MPS-2022-66954)|CVE-2022-4304|中危|
|OpenSSL 资源管理错误漏洞|双重释放|[MPS-2022-67892](https://www.oscs1024.com/hd/MPS-2022-67892)|CVE-2022-4450|高危|
|OpenSSL 操作系统命令注入漏洞|OS命令注入|[MPS-2022-8314](https://www.oscs1024.com/hd/MPS-2022-8314)|CVE-2022-1292|严重|
|OpenSSL 信任管理问题漏洞|证书验证不恰当|[MPS-2022-8664](https://www.oscs1024.com/hd/MPS-2022-8664)|CVE-2022-1343|中危|
|OpenSSL 加密问题漏洞|密码算法不安全|[MPS-2022-9138](https://www.oscs1024.com/hd/MPS-2022-9138)|CVE-2022-1434|中危|
|OpenSSL 安全漏洞|清理环节不完整|[MPS-2022-9427](https://www.oscs1024.com/hd/MPS-2022-9427)|CVE-2022-1473|高危|
|OpenSSL 资源管理错误漏洞|UAF|[MPS-2023-1276](https://www.oscs1024.com/hd/MPS-2023-1276)|CVE-2023-0215|高危|
|OpenSSL 代码问题漏洞|空指针取消引用|[MPS-2023-1277](https://www.oscs1024.com/hd/MPS-2023-1277)|CVE-2023-0216|高危|
|OpenSSL 代码问题漏洞|空指针取消引用|[MPS-2023-1278](https://www.oscs1024.com/hd/MPS-2023-1278)|CVE-2023-0217|高危|
|OpenSSL拒绝服务漏洞(X.509 GeneralName类型混淆)|不正确的类型转换|[MPS-2023-1620](https://www.oscs1024.com/hd/MPS-2023-1620)|CVE-2023-0286|高危|
|OpenSSL 代码问题漏洞|空指针取消引用|[MPS-2023-2153](https://www.oscs1024.com/hd/MPS-2023-2153)|CVE-2023-0401|高危|
|OpenSSL 验证 X.509 策略约束存在拒绝服务漏洞|拒绝服务|[MPS-2023-2810](https://www.oscs1024.com/hd/MPS-2023-2810)|CVE-2023-0464|中危|
|OpenSSL 信任管理问题漏洞|证书验证不恰当|[MPS-2023-2811](https://www.oscs1024.com/hd/MPS-2023-2811)|CVE-2023-0465|中危|
|OpenSSL 存在证书验证不当|证书验证不恰当|[MPS-2023-2812](https://www.oscs1024.com/hd/MPS-2023-2812)|CVE-2023-0466|中危|
|OpenSSL ASN.1对象标识符转换拒绝服务漏洞|拒绝服务|[MPS-9dro-82lx](https://www.oscs1024.com/hd/MPS-9dro-82lx)|CVE-2023-2650|中危|
|Certifi 数据伪造问题漏洞|对数据真实性的验证不充分|[MPS-ck78-r6zg](https://www.oscs1024.com/hd/MPS-ck78-r6zg)|CVE-2023-37920|严重|
|Requests Proxy-Authorization 标头泄露漏洞|未授权敏感信息泄露|[MPS-hr61-tzey](https://www.oscs1024.com/hd/MPS-hr61-tzey)|CVE-2023-32681|中危|
|OpenSSL 安全漏洞|过度迭代|[MPS-n3pe-ljgc](https://www.oscs1024.com/hd/MPS-n3pe-ljgc)|CVE-2023-3817|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|base64|0.4.0|0.5.2|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|openssl|openssl-3.0.4||间接依赖|建议修复|C:5|H:12|M:40|L:8|
|openssl|openssl-3.0.5||间接依赖|建议修复|C:5|H:12|M:40|L:8|
|qs|6.10.1|6.10.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|openssl|3.0.1|3.1.2|间接依赖|建议修复|C:8|H:23|M:46|L:8|
|requests|2.28.2|2.31.0|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|certifi|2022.12.7|2023.7.22|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|semver|6.3.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|303|Low|
|ISC|16|Low|
|自定义许可证|12|Low|
|Python-2.0|1|Low|
|BSD-3-Clause|5|Low|
|BSD-2-Clause|4|Low|
|Apache-2.0|4|Low|
|BSL-1.0|1|Low|
|Zlib|1|Low|
|MPL-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|statuses|1.5.0|间接依赖|npm|
|brotli|1.0.9|间接依赖||
|remark-lint-table-pipes|4.1.2|间接依赖|npm|
|deep-extend|0.6.0|间接依赖|npm|
|table-layout|1.0.2|间接依赖|npm|
|mdast-util-to-markdown|1.5.0|间接依赖|npm|
|resolve-path|1.4.0|间接依赖|npm|
|character-entities|2.0.2|间接依赖|npm|
|koa-convert|1.2.0|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|vfile-location|4.1.0|间接依赖|npm|
|typical|6.0.1|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|koa-route|3.2.0|间接依赖|npm|
|micromark|3.2.0|间接依赖|npm|
|jinja2||间接依赖|pip|
|unist-util-position|4.0.4|间接依赖|npm|
|Carp|0|间接依赖|perl|
|json-stringify-safe|5.0.1|间接依赖|npm|
|mri|1.2.0|间接依赖|npm|
|open|7.4.2|间接依赖|npm|
|bytes|3.1.0|间接依赖|npm|
|koa-compress|3.1.0|间接依赖|npm|
|micromark-core-commonmark|1.1.0|间接依赖|npm|
|remark-lint-definition-spacing|3.1.2|间接依赖|npm|
|lodash.assignwith|4.2.0|间接依赖|npm|
|micromark-util-decode-string|1.1.0|间接依赖|npm|
|readable-stream|2.3.7|间接依赖|npm|
|fresh|0.5.2|间接依赖|npm|
|openssl||间接依赖||
|micromark-util-character|1.2.0|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|remark-message-control|7.1.1|间接依赖|npm|
|@koa/cors|3.1.0|间接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|micromark-factory-whitespace|1.1.0|间接依赖|npm|
|parseurl|1.3.3|间接依赖|npm|
|iconv-lite|0.4.24|间接依赖|npm|
|sphinxcontrib-jsmath|1.0.1|间接依赖|pip|
|koa-bodyparser|4.3.0|间接依赖|npm|
|remark-lint-no-duplicate-definitions|3.1.2|间接依赖|npm|
|openssl|openssl-3.0.5|间接依赖||
|uvu|0.5.6|间接依赖|npm|
|serve-index-75lb|2.0.1|间接依赖|npm|
|argparse|2.0.1|间接依赖|npm|
|islice||间接依赖|pip|
|remark-lint-fenced-code-flag|3.1.2|间接依赖|npm|
|koa-conditional-get|2.0.0|间接依赖|npm|
|unist-util-stringify-position|3.0.3|间接依赖|npm|
|vary|1.1.2|间接依赖|npm|
|devlop|1.1.0|间接依赖|npm|
|extend|3.0.2|间接依赖|npm|
|remark-lint-no-tabs|3.1.2|间接依赖|npm|
|snowballstemmer|2.2.0|间接依赖|pip|
|is-wsl|2.2.0|间接依赖|npm|
|co|4.6.0|间接依赖|npm|
|string_decoder|1.1.1|间接依赖|npm|
|walk-back|4.0.0|间接依赖|npm|
|@types/supports-color|8.1.1|间接依赖|npm|
|mdast-util-gfm-footnote|1.0.2|间接依赖|npm|
|Environment||间接依赖|pip|
|mime-types|2.1.31|间接依赖|npm|
|libuv||间接依赖||
|chain||间接依赖|pip|
|yallist|4.0.0|间接依赖|npm|
|kleur|4.1.5|间接依赖|npm|
|strip-ansi|7.1.0|间接依赖|npm|
|lws-range|3.0.0|间接依赖|npm|
|remark-lint-checkbox-content-indent|4.1.2|间接依赖|npm|
|mdast-util-gfm-strikethrough|1.0.3|间接依赖|npm|
|cookies|0.8.0|间接依赖|npm|
|remark-lint-hard-break-spaces|3.1.2|间接依赖|npm|
|debug|3.1.0|间接依赖|npm|
|jsonparse|1.3.1|间接依赖|npm|
|sphinxcontrib-applehelp|1.0.3|间接依赖|pip|
|koa-range|0.3.0|间接依赖|npm|
|remark-lint-no-table-indentation|4.1.2|间接依赖|npm|
|mdast-util-gfm|2.0.2|间接依赖|npm|
|encodeurl|1.0.2|间接依赖|npm|
|command-line-usage|6.1.1|间接依赖|npm|
|remark-lint-blockquote-indentation|3.1.2|间接依赖|npm|
|lws-spa|3.0.0|间接依赖|npm|
|remark-stringify|10.0.3|间接依赖|npm|
|lws-static|2.0.0|间接依赖|npm|
|openssl|3.0.1|间接依赖||
|ansi-escape-sequences|5.1.2|间接依赖|npm|
|remark-lint-code-block-style|3.1.2|间接依赖|npm|
|vfile-message|3.1.4|间接依赖|npm|
|unified|10.1.2|间接依赖|npm|
|Encode|0|间接依赖|perl|
|lws-request-monitor|2.0.0|间接依赖|npm|
|accepts|1.3.7|间接依赖|npm|
|importlib-metadata|6.0.0|间接依赖|pip|
|mdast-util-phrasing|3.0.1|间接依赖|npm|
|remark-lint-no-trailing-spaces|2.0.1|间接依赖|npm|
|vfile-reporter|8.1.0|间接依赖|npm|
|string-width|6.1.0|间接依赖|npm|
|sphinxcontrib-devhelp|1.0.2|间接依赖|pip|
|@types/ms|0.7.31|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|lws-json|2.0.0|间接依赖|npm|
|remark-lint-no-undefined-references|4.2.1|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|@types/unist|2.0.7|间接依赖|npm|
|@tootallnate/once|1.1.2|间接依赖|npm|
|side-channel|1.0.4|间接依赖|npm|
|icu||间接依赖||
|streaming-json-stringify|3.1.0|间接依赖|npm|
|koa|2.13.1|间接依赖|npm|
|remark-lint-checkbox-character-style|4.1.2|间接依赖|npm|
|imagesize|1.4.1|间接依赖|pip|
|inflation|2.0.0|间接依赖|npm|
|vfile-message|4.0.2|间接依赖|npm|
|command-line-args|5.1.1|间接依赖|npm|
|basic-auth|2.0.1|间接依赖|npm|
|path-to-regexp|6.2.0|间接依赖|npm|
|lws-log|2.0.0|间接依赖|npm|
|remark-gfm|3.0.1|间接依赖|npm|
|escape-string-regexp|5.0.0|间接依赖|npm|
|micromark-factory-title|1.1.0|间接依赖|npm|
|postject|1.0.0-alpha.6|间接依赖|npm|
|remark-lint-prohibited-strings|3.1.0|间接依赖|npm|
|unist-util-stringify-position|4.0.0|间接依赖|npm|
|diff|5.1.0|间接依赖|npm|
|remark-lint-no-file-name-consecutive-dashes|2.1.2|间接依赖|npm|
|remark-lint-ordered-list-marker-style|3.1.2|间接依赖|npm|
|vfile|6.0.1|间接依赖|npm|
|lodash.throttle|4.1.1|间接依赖|npm|
|to-vfile|8.0.0|间接依赖|npm|
|lws-index|2.0.0|间接依赖|npm|
|setprototypeof|1.1.1|间接依赖|npm|
|mdast-util-gfm-autolink-literal|1.0.3|间接依赖|npm|
|escape-html|1.0.3|间接依赖|npm|
|wrapped|1.0.1|间接依赖|npm|
|remark-lint-no-shortcut-reference-image|3.1.2|间接依赖|npm|
|remark-lint-list-item-indent|3.1.2|间接依赖|npm|
|unist-util-visit|3.1.0|间接依赖|npm|
|stream-slice|0.1.2|间接依赖|npm|
|is-core-module|2.8.1|间接依赖|npm|
|async|3.2.3|间接依赖|npm|
|cassandra-cpp-driver|2.15.3|间接依赖||
|is-buffer|2.0.5|间接依赖|npm|
|semver|6.3.0|间接依赖|npm|
|lws-blacklist|3.0.0|间接依赖|npm|
|vfile|5.3.7|间接依赖|npm|
|micromark-extension-gfm-table|1.0.7|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|remark-lint-table-cell-padding|4.1.3|间接依赖|npm|
|koa-compose|4.1.0|间接依赖|npm|
|process-nextick-args|2.0.1|间接依赖|npm|
|lws-cors|3.0.0|间接依赖|npm|
|byte-size|6.2.0|间接依赖|npm|
|requests|2.28.2|间接依赖|pip|
|mdast-util-gfm-task-list-item|1.0.2|间接依赖|npm|
|unified-message-control|4.0.0|间接依赖|npm|
|remark-lint-unordered-list-marker-style|3.1.2|间接依赖|npm|
|zipp|3.11.0|间接依赖|pip|
|batch|0.6.1|间接依赖|npm|
|etag|1.8.1|间接依赖|npm|
|remark-lint-heading-style|3.1.2|间接依赖|npm|
|@types/estree-jsx|1.0.0|间接依赖|npm|
|pytz|2022.7.1|间接依赖|pip|
|co|3.1.0|间接依赖|npm|
|cache-content-type|1.0.1|间接依赖|npm|
|mime-db|1.48.0|间接依赖|npm|
|mz|2.7.0|间接依赖|npm|
|micromark-util-normalize-identifier|1.1.0|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|reduce-flatten|3.0.1|间接依赖|npm|
|remark-parse|10.0.2|间接依赖|npm|
|lws|3.1.0|间接依赖|npm|
|any-promise|1.3.0|间接依赖|npm|
|https-proxy-agent|5.0.0|间接依赖|npm|
|perl|5.008|间接依赖|perl|
|base|0|间接依赖|perl|
|koa-json|2.0.2|间接依赖|npm|
|remark-lint-no-shell-dollars|3.1.2|间接依赖|npm|
|micromark-util-decode-numeric-character-reference|1.1.0|间接依赖|npm|
|methods|1.1.2|间接依赖|npm|
|wordwrapjs|4.0.1|间接依赖|npm|
|through|2.3.8|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|co-body|6.1.0|间接依赖|npm|
|array-back|4.0.2|间接依赖|npm|
|thenify|3.3.1|间接依赖|npm|
|remark-lint-no-heading-content-indent|4.1.2|间接依赖|npm|
|create-mixin|3.0.0|间接依赖|npm|
|koa-etag|3.0.0|间接依赖|npm|
|remark-lint-no-blockquote-without-marker|5.1.2|间接依赖|npm|
|strict|0|间接依赖|perl|
|negotiator|0.6.2|间接依赖|npm|
|mdast-util-from-markdown|1.3.1|间接依赖|npm|
|remark-lint-no-file-name-articles|2.1.2|间接依赖|npm|
|eastasianwidth|0.2.0|间接依赖|npm|
|lws-conditional-get|2.0.0|间接依赖|npm|
|micromark-extension-gfm-footnote|1.1.2|间接依赖|npm|
|ansi-regex|6.0.1|间接依赖|npm|
|mdast-comment-marker|2.1.2|间接依赖|npm|
|copy-to|2.0.1|间接依赖|npm|
|stream-via|1.0.4|间接依赖|npm|
|JSONStream|1.3.5|间接依赖|npm|
|@types/unist|3.0.0|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|clang-format|1.8.0|直接依赖|npm|
|remark-lint-first-heading-level|3.1.2|间接依赖|npm|
|lws-body-parser|2.0.0|间接依赖|npm|
|packaging|23.0|间接依赖|pip|
|delegates|1.0.0|间接依赖|npm|
|lws-mime|2.0.0|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|isarray|1.0.0|间接依赖|npm|
|remark-lint-file-extension|2.1.2|间接依赖|npm|
|warnings|0|间接依赖|perl|
|content-disposition|0.5.3|间接依赖|npm|
|debug|4.3.4|间接依赖|npm|
|micromark-util-resolve-all|1.1.0|间接依赖|npm|
|unified-lint-rule|1.0.6|间接依赖|npm|
|remark-lint-fenced-code-marker|3.1.2|间接依赖|npm|
|koa-is-json|1.0.0|间接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|remark-lint-final-newline|2.1.2|间接依赖|npm|
|alabaster|0.7.13|间接依赖|pip|
|is-plain-obj|4.1.0|间接依赖|npm|
|remark-lint-maximum-line-length|3.1.3|间接依赖|npm|
|vfile-statistics|3.0.0|间接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|sphinx|6.1.3|间接依赖|pip|
|koa-send|5.0.1|间接依赖|npm|
|tsscmp|1.0.6|间接依赖|npm|
|qrcode-terminal|0.12.0|间接依赖|npm|
|lws-rewrite|3.1.1|间接依赖|npm|
|common-log-format|1.0.0|间接依赖|npm|
|toidentifier|1.0.0|间接依赖|npm|
|micromark-util-sanitize-uri|1.2.0|间接依赖|npm|
|node-version-matches|2.0.1|间接依赖|npm|
|raw-body|2.4.1|间接依赖|npm|
|lru-cache|6.0.0|间接依赖|npm|
|thenify-all|1.6.0|间接依赖|npm|
|micromark-util-symbol|1.1.0|间接依赖|npm|
|http-errors|1.8.0|间接依赖|npm|
|remark-preset-lint-node|4.0.0|间接依赖|npm|
|mdast-util-find-and-replace|2.2.2|间接依赖|npm|
|remark-lint-strong-marker|3.1.2|间接依赖|npm|
|on-headers|1.0.2|间接依赖|npm|
|is-generator-function|1.0.9|间接依赖|npm|
|MarkupSafe|2.1.2|间接依赖|pip|
|remark-lint-no-unused-definitions|3.1.2|间接依赖|npm|
|commander|9.5.0|间接依赖|npm|
|micromark-factory-label|1.1.0|间接依赖|npm|
|on-finished|2.3.0|间接依赖|npm|
|micromark-extension-gfm-autolink-literal|1.0.5|间接依赖|npm|
|@types/estree|1.0.1|间接依赖|npm|
|Exporter|0|间接依赖|perl|
|inflight|1.0.6|间接依赖|npm|
|remark-lint-rule-style|3.1.2|间接依赖|npm|
|sphinxcontrib-serializinghtml|1.1.5|间接依赖|pip|
|idna|3.4|间接依赖|pip|
|remark-lint-no-inline-padding|4.1.2|间接依赖|npm|
|supports-color|9.4.0|间接依赖|npm|
|remark-lint-no-consecutive-blank-lines|4.1.3|间接依赖|npm|
|resolve|1.22.0|间接依赖|npm|
|sade|1.8.1|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|koa-morgan|1.0.1|间接依赖|npm|
|micromark-util-combine-extensions|1.1.0|间接依赖|npm|
|src||间接依赖|pip|
|brotli||间接依赖||
|micromark-util-types|1.1.0|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|keygrip|1.1.0|间接依赖|npm|
|core-util-is|1.0.2|间接依赖|npm|
|unpipe|1.0.0|间接依赖|npm|
|lws-basic-auth|2.0.0|间接依赖|npm|
|compressible|2.0.18|间接依赖|npm|
|lws-compress|2.0.0|间接依赖|npm|
|micromark-util-chunked|1.1.0|间接依赖|npm|
|remark-lint-final-definition|3.1.2|间接依赖|npm|
|@ungap/structured-clone|1.2.0|间接依赖|npm|
|mdast-util-to-string|3.2.0|间接依赖|npm|
|remark-lint-no-heading-indent|4.1.2|间接依赖|npm|
|ms|2.0.0|间接依赖|npm|
|dequal|2.0.3|间接依赖|npm|
|markdown-table|3.0.3|间接依赖|npm|
|js-yaml|4.1.0|间接依赖|npm|
|remark-lint-no-file-name-outer-dashes|2.1.2|间接依赖|npm|
|remark-preset-lint-recommended|6.1.3|间接依赖|npm|
|poco||间接依赖||
|mdast-util-mdx-expression|1.3.2|间接依赖|npm|
|supports-preserve-symlinks-flag|1.0.0|间接依赖|npm|
|vfile-sort|4.0.0|间接依赖|npm|
|remark-lint-no-shortcut-reference-link|3.1.2|间接依赖|npm|
|media-typer|0.3.0|间接依赖|npm|
|decode-named-character-reference|1.0.2|间接依赖|npm|
|morgan|1.10.0|间接依赖|npm|
|remark-lint-no-literal-urls|3.1.2|间接依赖|npm|
|Jinja2|3.1.2|间接依赖|pip|
|micromark-util-html-tag-name|1.2.0|间接依赖|npm|
|bail|2.0.2|间接依赖|npm|
|depd|2.0.0|间接依赖|npm|
|ccount|2.0.1|间接依赖|npm|
|emoji-regex|10.2.1|间接依赖|npm|
|@types/debug|4.1.8|间接依赖|npm|
|lodash.camelcase|4.3.0|间接依赖|npm|
|zlib||间接依赖||
|unist-util-is|5.2.1|间接依赖|npm|
|longest-streak|3.1.0|间接依赖|npm|
|remark-lint-no-multiple-toplevel-headings|3.1.2|间接依赖|npm|
|ylru|1.2.1|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|load-module|3.0.0|间接依赖|npm|
|micromark-extension-gfm-strikethrough|1.0.7|间接依赖|npm|
|charset-normalizer|3.0.1|间接依赖|pip|
|semver|7.5.4|间接依赖|npm|
|urllib3|1.26.14|间接依赖|pip|
|brace-expansion|1.1.11|间接依赖|npm|
|docutils|0.19|间接依赖|pip|
|only|0.0.2|间接依赖|npm|
|pluralize|8.0.0|间接依赖|npm|
|type-is|1.6.18|间接依赖|npm|
|openssl|openssl-3.0.4|间接依赖||
|koa-static|5.0.0|间接依赖|npm|
|remark-lint|9.1.2|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|Pygments|2.14.0|间接依赖|pip|
|deep-equal|1.0.1|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|find-replace|3.0.0|间接依赖|npm|
|sphinxcontrib-qthelp|1.0.3|间接依赖|pip|
|@types/hast|2.3.5|间接依赖|npm|
|http-proxy-agent|4.0.1|间接依赖|npm|
|@types/mdast|3.0.12|间接依赖|npm|
|local-web-server|4.2.1|直接依赖|npm|
|qs|6.10.1|间接依赖|npm|
|trough|2.1.0|间接依赖|npm|
|unified|11.0.2|间接依赖|npm|
|micromark-factory-space|1.1.0|间接依赖|npm|
|destroy|1.0.4|间接依赖|npm|
|unist-util-visit|4.1.2|间接依赖|npm|
|zwitch|2.0.4|间接依赖|npm|
|base64|0.4.0|间接依赖||
|remark-lint-list-item-bullet-indent|4.1.2|间接依赖|npm|
|mdast-util-gfm-table|1.0.7|间接依赖|npm|
|mdast-util-heading-style|2.0.1|间接依赖|npm|
|is-docker|2.2.1|间接依赖|npm|
|micromark-factory-destination|1.1.0|间接依赖|npm|
|stream-log-stats|3.0.2|间接依赖|npm|
|ee-first|1.1.1|间接依赖|npm|
|sliced|1.0.1|间接依赖|npm|
|agent-base|6.0.2|间接依赖|npm|
|unist-util-visit-parents|5.1.3|间接依赖|npm|
|Babel|2.11.0|间接依赖|pip|
|sphinxcontrib-htmlhelp|2.0.0|间接依赖|pip|
|micromark-util-subtokenize|1.1.0|间接依赖|npm|
|http-assert|1.4.1|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|glob|7.2.0|间接依赖|npm|
|content-type|1.0.4|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|select_autoescape||间接依赖|pip|
|micromark-extension-gfm-tagfilter|1.0.2|间接依赖|npm|
|certifi|2022.12.7|间接依赖|pip|
|unist-util-generated|2.0.1|间接依赖|npm|
|micromark-extension-gfm-task-list-item|1.0.5|间接依赖|npm|
|unified-lint-rule|2.1.2|间接依赖|npm|
|micromark-util-encode|1.1.0|间接依赖|npm|
|micromark-extension-gfm|2.0.3|间接依赖|npm|
|micromark-util-classify-character|1.1.0|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)