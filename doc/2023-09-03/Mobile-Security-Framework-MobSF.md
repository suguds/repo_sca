# MobSF/Mobile-Security-Framework-MobSF安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698043028740636672.svg)](https://www.murphysec.com/console/report/1698043028698693632/1698043028740636672)

仓库描述：Mobile Security Framework (MobSF) is an automated, all-in-one mobile application (Android/iOS/Windows) pen-testing, malware analysis and security assessment framework capable of performing static and dynamic analysis.

仓库地址：[https://github.com/MobSF/Mobile-Security-Framework-MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF)

| star：14757 | watch：554 | fork：2984 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-01 12:59:10 | 许可证：GPL-3.0 |
| 最近检测时间：2023-09-03 02:53:43 | 组件总数：111 | 漏洞总数：106 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|PSWD.JS不安全口令哈希漏洞|使用未加Salt的单向哈希算法|[MPS-2006-1410](https://www.oscs1024.com/hd/MPS-2006-1410)|CVE-2006-1058|低危|
|OpenSSL ssl3_get_key_exchange 拒绝服务漏洞|数字错误|[MPS-2015-5992](https://www.oscs1024.com/hd/MPS-2015-5992)|CVE-2015-1794|中危|
|OpenSSL BN_mod_exp 安全漏洞|未授权敏感信息泄露|[MPS-2015-5993](https://www.oscs1024.com/hd/MPS-2015-5993)|CVE-2015-3193|高危|
|OpenSSL 拒绝服务漏洞|空指针取消引用|[MPS-2015-5994](https://www.oscs1024.com/hd/MPS-2015-5994)|CVE-2015-3194|高危|
|OpenSSL ASN1_TFLG_COMBINE 信息泄露漏洞|未授权敏感信息泄露|[MPS-2015-5995](https://www.oscs1024.com/hd/MPS-2015-5995)|CVE-2015-3195|中危|
|OpenSSL 信息泄露漏洞|未授权敏感信息泄露|[MPS-2016-0870](https://www.oscs1024.com/hd/MPS-2016-0870)|CVE-2016-0701|低危|
|OpenSSL 安全漏洞||[MPS-2016-0875](https://www.oscs1024.com/hd/MPS-2016-0875)|CVE-2015-3197|中危|
|OpenSSL 敏感信息泄露漏洞||[MPS-2016-1055](https://www.oscs1024.com/hd/MPS-2016-1055)|CVE-2016-0800|中危|
|OpenSSL 安全漏洞|未授权敏感信息泄露|[MPS-2016-1063](https://www.oscs1024.com/hd/MPS-2016-1063)|CVE-2016-0702|中危|
|OpenSSL 安全漏洞|拒绝服务|[MPS-2016-1064](https://www.oscs1024.com/hd/MPS-2016-1064)|CVE-2016-0705|严重|
|OpenSSL BN_hex2bn 函数和 BN_dec2bn 函数整数溢出漏洞|拒绝服务|[MPS-2016-1065](https://www.oscs1024.com/hd/MPS-2016-1065)|CVE-2016-0797|高危|
|OpenSSL SRP_VBASE_get_by_user 方法内存泄露漏洞|资源管理错误|[MPS-2016-1066](https://www.oscs1024.com/hd/MPS-2016-1066)|CVE-2016-0798|高危|
|OpenSSL BIO_*printf 函数安全漏洞|缓冲区溢出|[MPS-2016-1067](https://www.oscs1024.com/hd/MPS-2016-1067)|CVE-2016-0799|严重|
|OpenSSL 安全漏洞|缓冲区溢出|[MPS-2016-1068](https://www.oscs1024.com/hd/MPS-2016-1068)|CVE-2016-2842|严重|
|OpenSSL 整数溢出漏洞|整数溢出或环绕|[MPS-2016-2081](https://www.oscs1024.com/hd/MPS-2016-2081)|CVE-2016-2105|高危|
|OpenSSL 整数溢出漏洞|数字错误|[MPS-2016-2082](https://www.oscs1024.com/hd/MPS-2016-2082)|CVE-2016-2106|高危|
|OpenSSL 加密不当漏洞||[MPS-2016-2083](https://www.oscs1024.com/hd/MPS-2016-2083)|CVE-2016-2107|中危|
|OpenSSL ASN.1 BIO实现拒绝服务漏洞|资源管理错误|[MPS-2016-2085](https://www.oscs1024.com/hd/MPS-2016-2085)|CVE-2016-2109|高危|
|OpenSSL 安全漏洞|缓冲区溢出|[MPS-2016-2086](https://www.oscs1024.com/hd/MPS-2016-2086)|CVE-2016-2176|高危|
|OpenSSL 拒绝服务漏洞|整数溢出或环绕|[MPS-2016-3031](https://www.oscs1024.com/hd/MPS-2016-3031)|CVE-2016-2177|严重|
|OpenSSL 安全漏洞|通过差异性导致的信息暴露|[MPS-2016-3032](https://www.oscs1024.com/hd/MPS-2016-3032)|CVE-2016-2178|中危|
|OpenSSL 本地拒绝服务漏洞|越界读取|[MPS-2016-3871](https://www.oscs1024.com/hd/MPS-2016-3871)|CVE-2016-2180|高危|
|OpenSSL 安全漏洞|资源管理错误|[MPS-2016-4537](https://www.oscs1024.com/hd/MPS-2016-4537)|CVE-2016-2179|高危|
|OpenSSL 拒绝服务漏洞|数字错误|[MPS-2016-4538](https://www.oscs1024.com/hd/MPS-2016-4538)|CVE-2016-2181|高危|
|OpenSSL BN_bn2dec() 函数拒绝服务漏洞|越界写入|[MPS-2016-4539](https://www.oscs1024.com/hd/MPS-2016-4539)|CVE-2016-2182|严重|
|OpenSSL 拒绝服务漏洞|整数溢出或环绕|[MPS-2016-4548](https://www.oscs1024.com/hd/MPS-2016-4548)|CVE-2016-6302|高危|
|OpenSSL MDC2_Update 函数整数溢出漏洞|越界写入|[MPS-2016-4549](https://www.oscs1024.com/hd/MPS-2016-4549)|CVE-2016-6303|严重|
|OpenSSL 内存泄露漏洞|内存泄漏|[MPS-2016-4838](https://www.oscs1024.com/hd/MPS-2016-4838)|CVE-2016-6304|高危|
|OpenSSL 拒绝服务漏洞|越界读取|[MPS-2016-4840](https://www.oscs1024.com/hd/MPS-2016-4840)|CVE-2016-6306|中危|
|BusyBox 拒绝服务漏洞|资源管理错误|[MPS-2016-5978](https://www.oscs1024.com/hd/MPS-2016-5978)|CVE-2016-6301|高危|
|BusyBox 数字错误漏洞|整数溢出或环绕|[MPS-2017-12160](https://www.oscs1024.com/hd/MPS-2017-12160)|CVE-2017-15873|中危|
|BusyBox 数字错误漏洞|超界折返|[MPS-2017-12161](https://www.oscs1024.com/hd/MPS-2017-12161)|CVE-2017-15874|中危|
|OpenSSL 信息泄露漏洞|未授权敏感信息泄露|[MPS-2017-12484](https://www.oscs1024.com/hd/MPS-2017-12484)|CVE-2017-3736|中危|
|OpenSSL 存在拒绝服务漏洞|拒绝服务|[MPS-2017-12773](https://www.oscs1024.com/hd/MPS-2017-12773)|CVE-2016-8610|高危|
|BusyBox 代码注入漏洞|代码注入|[MPS-2017-13128](https://www.oscs1024.com/hd/MPS-2017-13128)|CVE-2017-16544|高危|
|OpenSSL 缓冲区错误漏洞||[MPS-2017-13708](https://www.oscs1024.com/hd/MPS-2017-13708)|CVE-2017-3737|中危|
|OpenSSL 信息泄露漏洞|未授权敏感信息泄露|[MPS-2017-13709](https://www.oscs1024.com/hd/MPS-2017-13709)|CVE-2017-3738|中危|
|BusyBox 数字错误漏洞|整数溢出或环绕|[MPS-2017-1448](https://www.oscs1024.com/hd/MPS-2017-1448)|CVE-2016-2147|高危|
|BusyBox 缓冲区错误漏洞|缓冲区溢出|[MPS-2017-1449](https://www.oscs1024.com/hd/MPS-2017-1449)|CVE-2016-2148|严重|
|BusyBox 安全漏洞|语法无效结构处理不恰当|[MPS-2017-2565](https://www.oscs1024.com/hd/MPS-2017-2565)|CVE-2014-9645|中危|
|OpenSSL 缓冲区错误漏洞|越界读取|[MPS-2017-5086](https://www.oscs1024.com/hd/MPS-2017-5086)|CVE-2017-3731|高危|
|OpenSSL 信息泄露漏洞|未授权敏感信息泄露|[MPS-2017-5087](https://www.oscs1024.com/hd/MPS-2017-5087)|CVE-2017-3732|中危|
|OpenSSL 安全漏洞|密钥管理错误|[MPS-2017-5091](https://www.oscs1024.com/hd/MPS-2017-5091)|CVE-2016-7055|中危|
|OpenSSL 缓冲区错误漏洞|缓冲区溢出|[MPS-2017-9606](https://www.oscs1024.com/hd/MPS-2017-9606)|CVE-2017-3735|中危|
|BusyBox 代码问题漏洞|空指针取消引用|[MPS-2018-10459](https://www.oscs1024.com/hd/MPS-2018-10459)|CVE-2015-9261|中危|
|OpenSSL 加密问题漏洞|密码算法不安全|[MPS-2018-14285](https://www.oscs1024.com/hd/MPS-2018-14285)|CVE-2018-0734|中危|
|OpenSSL 信息泄露漏洞|通过差异性导致的信息暴露|[MPS-2018-14899](https://www.oscs1024.com/hd/MPS-2018-14899)|CVE-2018-5407|中危|
|OpenSSL 资源管理错误漏洞|未经控制的递归|[MPS-2018-3750](https://www.oscs1024.com/hd/MPS-2018-3750)|CVE-2018-0739|中危|
|OpenSSL 加密问题漏洞|密码算法不安全|[MPS-2018-4731](https://www.oscs1024.com/hd/MPS-2018-4731)|CVE-2018-0737|中危|
|Openssl OpenSSL 加密问题漏洞|密钥管理错误|[MPS-2018-7822](https://www.oscs1024.com/hd/MPS-2018-7822)|CVE-2018-0732|高危|
|Busybox 信任管理问题漏洞|证书验证不恰当|[MPS-2018-8349](https://www.oscs1024.com/hd/MPS-2018-8349)|CVE-2018-1000500|高危|
|BusyBox wget 缓冲区错误漏洞|经典缓冲区溢出|[MPS-2018-8366](https://www.oscs1024.com/hd/MPS-2018-8366)|CVE-2018-1000517|严重|
|libpng 数字错误漏洞||[MPS-2018-9315](https://www.oscs1024.com/hd/MPS-2018-9315)|CVE-2018-13785|中危|
|libpng 安全漏洞|输入验证不恰当|[MPS-2018-9648](https://www.oscs1024.com/hd/MPS-2018-9648)|CVE-2018-14048|中危|
|BusyBox udhcp组件缓冲区错误漏洞|越界读取|[MPS-2019-0185](https://www.oscs1024.com/hd/MPS-2019-0185)|CVE-2019-5747|高危|
|BusyBox udhcp组件缓冲区错误漏洞|越界读取|[MPS-2019-0186](https://www.oscs1024.com/hd/MPS-2019-0186)|CVE-2018-20679|高危|
|OpenSSL 安全漏洞|服务端安全的客户端实施|[MPS-2019-11271](https://www.oscs1024.com/hd/MPS-2019-11271)|CVE-2019-1547|中危|
|OpenSSL 安全漏洞||[MPS-2019-11273](https://www.oscs1024.com/hd/MPS-2019-11273)|CVE-2019-1563|低危|
|OpenSSL 输入验证错误漏洞|整数溢出或环绕|[MPS-2019-15892](https://www.oscs1024.com/hd/MPS-2019-15892)|CVE-2019-1551|中危|
|OpenSSL 信息泄露漏洞|通过差异性导致的信息暴露|[MPS-2019-1990](https://www.oscs1024.com/hd/MPS-2019-1990)|CVE-2019-1559|中危|
|libpng 缓冲区错误漏洞|越界写入|[MPS-2019-7748](https://www.oscs1024.com/hd/MPS-2019-7748)|CVE-2018-14550|高危|
|OpenSSL 信任管理问题漏洞|证书验证不恰当|[MPS-2019-8829](https://www.oscs1024.com/hd/MPS-2019-8829)|CVE-2019-1552|低危|
|OpenSSL 加密问题漏洞|通过差异性导致的信息暴露|[MPS-2020-12634](https://www.oscs1024.com/hd/MPS-2020-12634)|CVE-2020-1968|低危|
|OpenSSL 空指针取消引用漏洞|空指针取消引用|[MPS-2020-17574](https://www.oscs1024.com/hd/MPS-2020-17574)|CVE-2020-1971|中危|
|OpenSSL 缓冲区错误漏洞|越界读取|[MPS-2021-17869](https://www.oscs1024.com/hd/MPS-2021-17869)|CVE-2021-3712|高危|
|OpenSSL 加密问题漏洞|加密强度不足|[MPS-2021-1869](https://www.oscs1024.com/hd/MPS-2021-1869)|CVE-2021-23839|低危|
|OpenSSL 输入验证错误漏洞|整数溢出或环绕|[MPS-2021-2306](https://www.oscs1024.com/hd/MPS-2021-2306)|CVE-2021-23840|高危|
|OpenSSL 输入验证错误漏洞|空指针取消引用|[MPS-2021-2535](https://www.oscs1024.com/hd/MPS-2021-2535)|CVE-2021-23841|中危|
|BusyBox 代码问题漏洞|空指针取消引用|[MPS-2021-33224](https://www.oscs1024.com/hd/MPS-2021-33224)|CVE-2021-42373|中危|
|BusyBox 缓冲区错误漏洞|越界读取|[MPS-2021-33225](https://www.oscs1024.com/hd/MPS-2021-33225)|CVE-2021-42374|中危|
|BusyBox 安全漏洞|输入验证不恰当|[MPS-2021-33226](https://www.oscs1024.com/hd/MPS-2021-33226)|CVE-2021-42375|中危|
|BusyBox 代码问题漏洞|空指针取消引用|[MPS-2021-33227](https://www.oscs1024.com/hd/MPS-2021-33227)|CVE-2021-42376|中危|
|Busybox 安全漏洞|对无效指针或索引的释放|[MPS-2021-33228](https://www.oscs1024.com/hd/MPS-2021-33228)|CVE-2021-42377|严重|
|BusyBox 资源管理错误漏洞|UAF|[MPS-2021-33229](https://www.oscs1024.com/hd/MPS-2021-33229)|CVE-2021-42378|高危|
|BusyBox 资源管理错误漏洞|UAF|[MPS-2021-33230](https://www.oscs1024.com/hd/MPS-2021-33230)|CVE-2021-42379|高危|
|BusyBox 资源管理错误漏洞|UAF|[MPS-2021-33231](https://www.oscs1024.com/hd/MPS-2021-33231)|CVE-2021-42380|高危|
|BusyBox 资源管理错误漏洞|UAF|[MPS-2021-33232](https://www.oscs1024.com/hd/MPS-2021-33232)|CVE-2021-42381|高危|
|BusyBox 资源管理错误漏洞|UAF|[MPS-2021-33233](https://www.oscs1024.com/hd/MPS-2021-33233)|CVE-2021-42382|高危|
|BusyBox 资源管理错误漏洞|UAF|[MPS-2021-33234](https://www.oscs1024.com/hd/MPS-2021-33234)|CVE-2021-42383|高危|
|BusyBox 资源管理错误漏洞|UAF|[MPS-2021-33235](https://www.oscs1024.com/hd/MPS-2021-33235)|CVE-2021-42384|高危|
|BusyBox 资源管理错误漏洞|UAF|[MPS-2021-33236](https://www.oscs1024.com/hd/MPS-2021-33236)|CVE-2021-42385|高危|
|BusyBox 资源管理错误漏洞|UAF|[MPS-2021-33237](https://www.oscs1024.com/hd/MPS-2021-33237)|CVE-2021-42386|高危|
|Openssl 空指针取消引用漏洞|空指针取消引用|[MPS-2021-3619](https://www.oscs1024.com/hd/MPS-2021-3619)|CVE-2021-3449|中危|
|OpenSSL 输入验证错误漏洞|输入验证不恰当|[MPS-2021-39449](https://www.oscs1024.com/hd/MPS-2021-39449)|CVE-2021-4160|中危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9827](https://www.oscs1024.com/hd/MPS-2021-9827)|CVE-2021-36373|中危|
|Apache Ant 拒绝服务漏洞|长度参数不一致性处理不恰当|[MPS-2021-9847](https://www.oscs1024.com/hd/MPS-2021-9847)|CVE-2021-36374|中危|
|Expat 资源管理错误漏洞|数值计算不正确|[MPS-2022-0004](https://www.oscs1024.com/hd/MPS-2022-0004)|CVE-2021-45960|高危|
|org.mozilla:rhino <1.7.12 存在XXE漏洞|XXE|[MPS-2022-11928](https://www.oscs1024.com/hd/MPS-2022-11928)||高危|
|OpenSSL 存在任意命令执行漏洞|OS命令注入|[MPS-2022-18279](https://www.oscs1024.com/hd/MPS-2022-18279)|CVE-2022-2068|严重|
|OpenSSL 拒绝服务漏洞|不可达退出条件的循环（无限循环）|[MPS-2022-5555](https://www.oscs1024.com/hd/MPS-2022-5555)|CVE-2022-0778|高危|
|Apache Batik visibleToScripts 信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-59716](https://www.oscs1024.com/hd/MPS-2022-59716)|CVE-2022-42890|中危|
|Apache XML Graphics Batik<1.17 存在SSRF漏洞|SSRF|[MPS-2022-63578](https://www.oscs1024.com/hd/MPS-2022-63578)|CVE-2022-44729|中危|
|Apache XML Graphics Batik 代码问题漏洞|SSRF|[MPS-2022-63579](https://www.oscs1024.com/hd/MPS-2022-63579)|CVE-2022-44730|中危|
|OpenSSL 安全漏洞|通过差异性导致的信息暴露|[MPS-2022-66954](https://www.oscs1024.com/hd/MPS-2022-66954)|CVE-2022-4304|中危|
|busybox越界写入漏洞|越界写入|[MPS-2022-69987](https://www.oscs1024.com/hd/MPS-2022-69987)|CVE-2022-48174|严重|
|BusyBox 安全漏洞|代码注入|[MPS-2022-7540](https://www.oscs1024.com/hd/MPS-2022-7540)|CVE-2022-28391|严重|
|OpenSSL 操作系统命令注入漏洞|OS命令注入|[MPS-2022-8314](https://www.oscs1024.com/hd/MPS-2022-8314)|CVE-2022-1292|严重|
|BusyBox 资源管理错误漏洞|UAF|[MPS-2022-9766](https://www.oscs1024.com/hd/MPS-2022-9766)|CVE-2022-30065|高危|
|OpenSSL 资源管理错误漏洞|UAF|[MPS-2023-1276](https://www.oscs1024.com/hd/MPS-2023-1276)|CVE-2023-0215|高危|
|OpenSSL拒绝服务漏洞(X.509 GeneralName类型混淆)|不正确的类型转换|[MPS-2023-1620](https://www.oscs1024.com/hd/MPS-2023-1620)|CVE-2023-0286|高危|
|OpenSSL 验证 X.509 策略约束存在拒绝服务漏洞|拒绝服务|[MPS-2023-2810](https://www.oscs1024.com/hd/MPS-2023-2810)|CVE-2023-0464|中危|
|OpenSSL 信任管理问题漏洞|证书验证不恰当|[MPS-2023-2811](https://www.oscs1024.com/hd/MPS-2023-2811)|CVE-2023-0465|中危|
|OpenSSL 存在证书验证不当|证书验证不恰当|[MPS-2023-2812](https://www.oscs1024.com/hd/MPS-2023-2812)|CVE-2023-0466|中危|
|OpenSSL ASN.1对象标识符转换拒绝服务漏洞|拒绝服务|[MPS-9dro-82lx](https://www.oscs1024.com/hd/MPS-9dro-82lx)|CVE-2023-2650|中危|
|OpenSSL 安全漏洞|过度迭代|[MPS-n3pe-ljgc](https://www.oscs1024.com/hd/MPS-n3pe-ljgc)|CVE-2023-3817|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.apache.xmlgraphics:batik-transcoder|1.15|1.17|直接依赖|强烈建议修复|C:0|H:0|M:1|L:0|
|org.apache.xmlgraphics:batik-bridge|1.15|1.17|直接依赖|强烈建议修复|C:0|H:0|M:1|L:0|
|busybox|1.22.1|1.35|间接依赖|强烈建议修复|C:5|H:16|M:8|L:1|
|busybox|1.21.1|1.35|间接依赖|强烈建议修复|C:5|H:16|M:8|L:1|
|libpng|1.6.40||间接依赖|建议修复|C:0|H:1|M:2|L:0|
|libexpat|2.5.0||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|openssl|1.0.2d|3.1.2|间接依赖|建议修复|C:8|H:21|M:31|L:5|
|org.mozilla:rhino|1.7.7|1.7.12|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|commons-io:commons-io|1.3.1|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.apache.ant:ant|1.10.9|1.10.11|直接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.apache.xmlgraphics:batik-script|1.15|1.17|直接依赖|可选修复|C:0|H:0|M:2|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MPL-2.0|1|Low|
|MIT|5|Low|
|自定义许可证|10|Low|
|Apache-2.0|48|Low|
|GPLv2|2|Medium|
|OpenSSL|1|Low|
|BSD-3-Clause|2|Low|
|EPL-1.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|libandroidfw.so||间接依赖||
|libpng|1.6.40|间接依赖||
|libc.so.6||间接依赖||
|liblog.so||间接依赖||
|api-ms-win-crt-filesystem-l1-1-0.dll||间接依赖||
|/System/Library/Frameworks/Foundation.framework/Versions/C/Foundation||间接依赖||
|org.mozilla:rhino|1.7.7|直接依赖|maven|
|org.checkerframework:checker-compat-qual|2.5.2|直接依赖|maven|
|org.antlr:ST4|4.0.8|直接依赖|maven|
|jawt.dll||间接依赖||
|org.checkerframework:checker-qual|3.33.0|直接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|直接依赖|maven|
|libc.so||间接依赖||
|libjawt.so||间接依赖||
|org.apache.ant:ant-launcher|1.10.9|间接依赖|maven|
|org.apache.xmlgraphics:batik-test|1.15|直接依赖|maven|
|org.fusesource.jansi:jansi|1.18|直接依赖|maven|
|com.abubusoft:kripton-arch-integration||间接依赖|maven|
|api-ms-win-crt-stdio-l1-1-0.dll||间接依赖||
|libbinder.so||间接依赖||
|api-ms-win-crt-multibyte-l1-1-0.dll||间接依赖||
|libstdc++.so||间接依赖||
|libandroid_runtime.so||间接依赖||
|org.apache.xmlgraphics:batik-css|1.15|直接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|直接依赖|maven|
|org.apache.xmlgraphics:batik-shared-resources|1.15|直接依赖|maven|
|api-ms-win-crt-environment-l1-1-0.dll||间接依赖||
|org.apache.xmlgraphics:batik-svg-dom|1.15|直接依赖|maven|
|org.apache.xmlgraphics:batik-extension|1.15|直接依赖|maven|
|antlr:antlr|2.7.7|直接依赖|maven|
|org.apache.xmlgraphics:batik-bridge|1.15|直接依赖|maven|
|api-ms-win-crt-heap-l1-1-0.dll||间接依赖||
|org.apache.xmlgraphics:xmlgraphics-commons|2.7|直接依赖|maven|
|org.apache.xmlgraphics:batik-codec|1.15|直接依赖|maven|
|javax.servlet:javax.servlet-api|4.0.1|直接依赖|maven|
|libexpat|2.5.0|间接依赖||
|busybox|1.22.1|间接依赖||
|com.google.j2objc:j2objc-annotations|1.3|直接依赖|maven|
|org.apache.xmlgraphics:batik-constants|1.15|直接依赖|maven|
|api-ms-win-crt-convert-l1-1-0.dll||间接依赖||
|org.apache.xmlgraphics:batik-svgrasterizer|1.15|直接依赖|maven|
|SHELL32.dll||间接依赖||
|com.google.j2objc:j2objc-annotations|2.8|直接依赖|maven|
|openssl|1.0.2d|间接依赖||
|commons-io:commons-io|1.3.1|间接依赖|maven|
|libcutils.so||间接依赖||
|org.apache.xmlgraphics:batik-ext|1.15|直接依赖|maven|
|org.apache.xmlgraphics:batik-util|1.15|直接依赖|maven|
|org.apache.xmlgraphics:batik-anim|1.15|直接依赖|maven|
|com.squareup.picasso:picasso||间接依赖|maven|
|org.apache.xmlgraphics:batik-dom|1.15|直接依赖|maven|
|org.apache.xmlgraphics:batik-awt-util|1.15|直接依赖|maven|
|/System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation||间接依赖||
|com.google.errorprone:error_prone_annotations|2.5.1|直接依赖|maven|
|django||间接依赖|pip|
|org.codehaus.janino:commons-compiler|3.1.8|直接依赖|maven|
|org.apache.ant:ant|1.10.9|直接依赖|maven|
|org.apache.xmlgraphics:batik-gui-util|1.15|直接依赖|maven|
|USER32.dll||间接依赖||
|xml-apis:xml-apis|1.4.01|直接依赖|maven|
|/usr/lib/libobjc.A.dylib||间接依赖||
|ADVAPI32.dll||间接依赖||
|api-ms-win-crt-private-l1-1-0.dll||间接依赖||
|org.apache.xmlgraphics:batik-transcoder|1.15|直接依赖|maven|
|api-ms-win-crt-locale-l1-1-0.dll||间接依赖||
|libdvm.so||间接依赖||
|org.python:jython|2.7.0|直接依赖|maven|
|api-ms-win-crt-time-l1-1-0.dll||间接依赖||
|api-ms-win-crt-math-l1-1-0.dll||间接依赖||
|com.sun.mail:javax.mail|1.6.2|直接依赖|maven|
|libdl.so||间接依赖||
|ch.qos.logback:logback-core|1.3.4|直接依赖|maven|
|KERNEL32.dll||间接依赖||
|com.google.j2objc:j2objc-annotations|1.1|直接依赖|maven|
|javax.mail:javax.mail-api|1.6.2|直接依赖|maven|
|com.google.guava:failureaccess|1.0.1|直接依赖|maven|
|/usr/lib/libSystem.B.dylib||间接依赖||
|org.checkerframework:checker-qual|3.8.0|直接依赖|maven|
|libstlport.so||间接依赖||
|org.codehaus.mojo:animal-sniffer-annotations|1.17|直接依赖|maven|
|org.apache.xmlgraphics:batik-svggen|1.15|直接依赖|maven|
|org.antlr:stringtemplate|3.2.1|直接依赖|maven|
|org.apache.xmlgraphics:batik-parser|1.15|直接依赖|maven|
|org.apache.xmlgraphics:batik-test-swing|1.15|直接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|直接依赖|maven|
|com.github.kedzie.supportanimator:sample||间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|直接依赖|maven|
|libutils.so||间接依赖||
|javax.activation:activation|1.1|直接依赖|maven|
|com.1gravity:android-rteditor-materialdialog||间接依赖|maven|
|org.apache.xmlgraphics:batik-script|1.15|直接依赖|maven|
|org.codehaus.janino:janino|3.1.8|直接依赖|maven|
|api-ms-win-crt-string-l1-1-0.dll||间接依赖||
|io.homunculus:hcf-codegen||间接依赖|maven|
|xml-apis:xml-apis-ext|1.3.04|直接依赖|maven|
|api-ms-win-crt-utility-l1-1-0.dll||间接依赖||
|org.apache.xmlgraphics:batik-swing|1.15|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.2.0|直接依赖|maven|
|org.slf4j:slf4j-api|2.0.1|直接依赖|maven|
|api-ms-win-crt-runtime-l1-1-0.dll||间接依赖||
|busybox|1.21.1|间接依赖||
|GDI32.dll||间接依赖||
|libm.so||间接依赖||
|org.apache.xmlgraphics:batik-xml|1.15|直接依赖|maven|
|org.apache.xmlgraphics:batik-i18n|1.15|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.18.0|直接依赖|maven|
|org.antlr:antlr-runtime|3.5.2|直接依赖|maven|
|org.apache.xmlgraphics:batik-gvt|1.15|直接依赖|maven|
|commons-logging:commons-logging|1.0.4|间接依赖|maven|
|org.apache.xmlgraphics:batik-svgbrowser|1.15|直接依赖|maven|
|/usr/lib/libcrypto.0.9.8.dylib||间接依赖||


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)