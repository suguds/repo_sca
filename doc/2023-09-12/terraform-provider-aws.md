# hashicorp/terraform-provider-aws安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1701309070370979840.svg)](https://www.murphysec.com/console/report/1701296950972383232/1701309070370979840)

仓库描述：Terraform AWS provider

仓库地址：[https://github.com/hashicorp/terraform-provider-aws](https://github.com/hashicorp/terraform-provider-aws)

| star：8858 | watch：453 | fork：8316 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-12 01:17:22 | 许可证：MPL-2.0 |
| 最近检测时间：2023-09-12 03:31:11 | 组件总数：327 | 漏洞总数：157 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|OpenSSL dtls1_listen 函数拒绝服务漏洞|拒绝服务|[MPS-2015-1482](https://www.oscs1024.com/hd/MPS-2015-1482)|CVE-2015-0207|中危|
|OpenSSL rsa_item_verify 函数拒绝服务漏洞|拒绝服务|[MPS-2015-1483](https://www.oscs1024.com/hd/MPS-2015-1483)|CVE-2015-0208|中危|
|OpenSSL ssl3_write_bytes 函数拒绝服务漏洞|已弃用：代码|[MPS-2015-1490](https://www.oscs1024.com/hd/MPS-2015-1490)|CVE-2015-0290|中危|
|OpenSSL sigalgs 拒绝服务漏洞|拒绝服务|[MPS-2015-1491](https://www.oscs1024.com/hd/MPS-2015-1491)|CVE-2015-0291|中危|
|OpenSSL ssl3_get_client_key_exchange 函数拒绝服务漏洞|输入验证不恰当|[MPS-2015-1494](https://www.oscs1024.com/hd/MPS-2015-1494)|CVE-2015-1787|低危|
|OpenSSL BN_GF2m_mod_inv 函数资源管理错误漏洞|资源管理错误|[MPS-2015-2811](https://www.oscs1024.com/hd/MPS-2015-2811)|CVE-2015-1788|中危|
|OpenSSL 缓冲区错误漏洞|缓冲区溢出|[MPS-2015-2812](https://www.oscs1024.com/hd/MPS-2015-2812)|CVE-2015-1789|高危|
|OpenSSL PKCS7_dataDecode 函数拒绝服务漏洞|拒绝服务|[MPS-2015-2813](https://www.oscs1024.com/hd/MPS-2015-2813)|CVE-2015-1790|中危|
|OpenSSL ssl3_get_new_session_ticket 函数竞争条件漏洞|竞争条件|[MPS-2015-2814](https://www.oscs1024.com/hd/MPS-2015-2814)|CVE-2015-1791|中危|
|OpenSSL 资源管理错误漏洞|资源管理错误|[MPS-2015-2815](https://www.oscs1024.com/hd/MPS-2015-2815)|CVE-2015-1792|中危|
|OpenSSL 安全漏洞|7PK - 安全功能|[MPS-2015-3308](https://www.oscs1024.com/hd/MPS-2015-3308)|CVE-2015-1793|中危|
|OpenSSL ssl3_get_key_exchange 拒绝服务漏洞|数字错误|[MPS-2015-5992](https://www.oscs1024.com/hd/MPS-2015-5992)|CVE-2015-1794|中危|
|OpenSSL BN_mod_exp 安全漏洞|未授权敏感信息泄露|[MPS-2015-5993](https://www.oscs1024.com/hd/MPS-2015-5993)|CVE-2015-3193|高危|
|OpenSSL 拒绝服务漏洞|空指针取消引用|[MPS-2015-5994](https://www.oscs1024.com/hd/MPS-2015-5994)|CVE-2015-3194|高危|
|OpenSSL ASN1_TFLG_COMBINE 信息泄露漏洞|未授权敏感信息泄露|[MPS-2015-5995](https://www.oscs1024.com/hd/MPS-2015-5995)|CVE-2015-3195|中危|
|OpenSSL 拒绝服务漏洞|竞争条件|[MPS-2015-5996](https://www.oscs1024.com/hd/MPS-2015-5996)|CVE-2015-3196|中危|
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
|OpenSSL ASN.1实现拒绝服务漏洞|缓冲区溢出|[MPS-2016-2084](https://www.oscs1024.com/hd/MPS-2016-2084)|CVE-2016-2108|严重|
|OpenSSL ASN.1 BIO实现拒绝服务漏洞|资源管理错误|[MPS-2016-2085](https://www.oscs1024.com/hd/MPS-2016-2085)|CVE-2016-2109|高危|
|OpenSSL 安全漏洞|缓冲区溢出|[MPS-2016-2086](https://www.oscs1024.com/hd/MPS-2016-2086)|CVE-2016-2176|高危|
|OpenSSL 拒绝服务漏洞|整数溢出或环绕|[MPS-2016-3031](https://www.oscs1024.com/hd/MPS-2016-3031)|CVE-2016-2177|严重|
|OpenSSL 安全漏洞|通过差异性导致的信息暴露|[MPS-2016-3032](https://www.oscs1024.com/hd/MPS-2016-3032)|CVE-2016-2178|中危|
|OpenSSL 本地拒绝服务漏洞|越界读取|[MPS-2016-3871](https://www.oscs1024.com/hd/MPS-2016-3871)|CVE-2016-2180|高危|
|OpenSSL 信息泄露漏洞|未授权敏感信息泄露|[MPS-2016-4273](https://www.oscs1024.com/hd/MPS-2016-4273)|CVE-2016-2183|高危|
|OpenSSL 安全漏洞|资源管理错误|[MPS-2016-4537](https://www.oscs1024.com/hd/MPS-2016-4537)|CVE-2016-2179|高危|
|OpenSSL 拒绝服务漏洞|数字错误|[MPS-2016-4538](https://www.oscs1024.com/hd/MPS-2016-4538)|CVE-2016-2181|高危|
|OpenSSL BN_bn2dec() 函数拒绝服务漏洞|越界写入|[MPS-2016-4539](https://www.oscs1024.com/hd/MPS-2016-4539)|CVE-2016-2182|严重|
|OpenSSL 拒绝服务漏洞|整数溢出或环绕|[MPS-2016-4548](https://www.oscs1024.com/hd/MPS-2016-4548)|CVE-2016-6302|高危|
|OpenSSL MDC2_Update 函数整数溢出漏洞|越界写入|[MPS-2016-4549](https://www.oscs1024.com/hd/MPS-2016-4549)|CVE-2016-6303|严重|
|OpenSSL 内存泄露漏洞|内存泄漏|[MPS-2016-4838](https://www.oscs1024.com/hd/MPS-2016-4838)|CVE-2016-6304|高危|
|OpenSSL 拒绝服务漏洞|越界读取|[MPS-2016-4840](https://www.oscs1024.com/hd/MPS-2016-4840)|CVE-2016-6306|中危|
|Google protobuf 缓冲区错误漏洞|越界写入|[MPS-2017-10841](https://www.oscs1024.com/hd/MPS-2017-10841)|CVE-2015-5237|高危|
|OpenSSL 信息泄露漏洞|未授权敏感信息泄露|[MPS-2017-12484](https://www.oscs1024.com/hd/MPS-2017-12484)|CVE-2017-3736|中危|
|OpenSSL 存在拒绝服务漏洞|拒绝服务|[MPS-2017-12773](https://www.oscs1024.com/hd/MPS-2017-12773)|CVE-2016-8610|高危|
|OpenSSL 缓冲区错误漏洞||[MPS-2017-13708](https://www.oscs1024.com/hd/MPS-2017-13708)|CVE-2017-3737|中危|
|OpenSSL 信息泄露漏洞|未授权敏感信息泄露|[MPS-2017-13709](https://www.oscs1024.com/hd/MPS-2017-13709)|CVE-2017-3738|中危|
|OpenSSL 缓冲区错误漏洞|越界读取|[MPS-2017-5086](https://www.oscs1024.com/hd/MPS-2017-5086)|CVE-2017-3731|高危|
|OpenSSL 信息泄露漏洞|未授权敏感信息泄露|[MPS-2017-5087](https://www.oscs1024.com/hd/MPS-2017-5087)|CVE-2017-3732|中危|
|OpenSSL 缓冲区错误漏洞|缓冲区溢出|[MPS-2017-9606](https://www.oscs1024.com/hd/MPS-2017-9606)|CVE-2017-3735|中危|
|FasterXML Jackson-databind 反序列化漏洞(dbcp2 gadget绕过)|反序列化|[MPS-2018-0362](https://www.oscs1024.com/hd/MPS-2018-0362)|CVE-2017-17485|严重|
|FasterXML jackson-databind 反序列化漏洞(Hibernate/iBatis gadget绕过)||[MPS-2018-0934](https://www.oscs1024.com/hd/MPS-2018-0934)|CVE-2018-5968|高危|
|OpenSSL 加密问题漏洞|隐蔽时间通道|[MPS-2018-12058](https://www.oscs1024.com/hd/MPS-2018-12058)|CVE-2016-7056|中危|
|FasterXML jackson-databind 反序列化漏洞(c3p0 gadget绕过)||[MPS-2018-2477](https://www.oscs1024.com/hd/MPS-2018-2477)|CVE-2018-7489|严重|
|OpenSSL 资源管理错误漏洞|未经控制的递归|[MPS-2018-3750](https://www.oscs1024.com/hd/MPS-2018-3750)|CVE-2018-0739|中危|
|OpenSSL 加密问题漏洞|密码算法不安全|[MPS-2018-4731](https://www.oscs1024.com/hd/MPS-2018-4731)|CVE-2018-0737|中危|
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|Openssl OpenSSL 加密问题漏洞|密钥管理错误|[MPS-2018-7822](https://www.oscs1024.com/hd/MPS-2018-7822)|CVE-2018-0732|高危|
|FasterXML jackson-databind反序列化漏洞(slf4j-ext gadget绕过)|反序列化|[MPS-2019-0018](https://www.oscs1024.com/hd/MPS-2019-0018)|CVE-2018-14718|严重|
|FasterXML jackson-databind反序列化漏洞(blaze-ds-opt gadget绕过)|反序列化|[MPS-2019-0019](https://www.oscs1024.com/hd/MPS-2019-0019)|CVE-2018-14719|严重|
|FasterXML jackson-databind XXE漏洞(DRSHelper gadget绕过)||[MPS-2019-0020](https://www.oscs1024.com/hd/MPS-2019-0020)|CVE-2018-14720|严重|
|FasterXML Jackson-databind服务器端请求伪造漏洞(axis2-jaxws gadget绕过)|SSRF|[MPS-2019-0021](https://www.oscs1024.com/hd/MPS-2019-0021)|CVE-2018-14721|严重|
|FasterXML Jackson-databind代码问题漏洞(axis2-transport-jms gadget绕过)|反序列化|[MPS-2019-0023](https://www.oscs1024.com/hd/MPS-2019-0023)|CVE-2018-19360|严重|
|FasterXML Jackson-databind代码问题漏洞(openjpa gadget绕过)|反序列化|[MPS-2019-0024](https://www.oscs1024.com/hd/MPS-2019-0024)|CVE-2018-19361|严重|
|FasterXML Jackson-databind代码问题漏洞(jboss-common-core gadget绕过)|反序列化|[MPS-2019-0025](https://www.oscs1024.com/hd/MPS-2019-0025)|CVE-2018-19362|严重|
|FasterXML jackson-databind 反序列化漏洞(HikariCP gadget绕过)|反序列化|[MPS-2019-11529](https://www.oscs1024.com/hd/MPS-2019-11529)|CVE-2019-14540|严重|
|FasterXML jackson-databind 反序列化漏洞(HikariCP gadget绕过)|反序列化|[MPS-2019-11533](https://www.oscs1024.com/hd/MPS-2019-11533)|CVE-2019-16335|严重|
|FasterXML jackson-databind 反序列化漏洞(commons-dbcp gadget绕过)|反序列化|[MPS-2019-12479](https://www.oscs1024.com/hd/MPS-2019-12479)|CVE-2019-16942|严重|
|FasterXML jackson-databind 反序列化漏洞(p6spy gadget绕过)|反序列化|[MPS-2019-12480](https://www.oscs1024.com/hd/MPS-2019-12480)|CVE-2019-16943|严重|
|FasterXML jackson-databind 反序列化漏洞(ehcache gadget绕过)|反序列化|[MPS-2019-12676](https://www.oscs1024.com/hd/MPS-2019-12676)|CVE-2019-17267|严重|
|FasterXML jackson-databind 反序列化漏洞(apache-log4j-extras gadget绕过)|反序列化|[MPS-2019-13103](https://www.oscs1024.com/hd/MPS-2019-13103)|CVE-2019-17531|严重|
|Apache Log4j SocketServer反序列化漏洞|反序列化|[MPS-2019-17271](https://www.oscs1024.com/hd/MPS-2019-17271)|CVE-2019-17571|严重|
|FasterXML Jackson-databind反序列化漏洞（Jodd-db gadget绕过）|反序列化|[MPS-2019-2619](https://www.oscs1024.com/hd/MPS-2019-2619)|CVE-2018-12022|高危|
|FasterXML Jackson-databind反序列化漏洞(Oracle JDBC driver gadget绕过)|反序列化|[MPS-2019-2620](https://www.oscs1024.com/hd/MPS-2019-2620)|CVE-2018-12023|高危|
|FasterXML jackson-databind 反序列化漏洞(mysql gadget绕过)|反序列化|[MPS-2019-5442](https://www.oscs1024.com/hd/MPS-2019-5442)|CVE-2019-12086|高危|
|FasterXML jackson-databind 反序列化漏洞(jdom gadget绕过)|反序列化|[MPS-2019-6867](https://www.oscs1024.com/hd/MPS-2019-6867)|CVE-2019-12814|中危|
|FasterXML jackson-databind 反序列化漏洞(logback-classic gadget绕过)|反序列化|[MPS-2019-7047](https://www.oscs1024.com/hd/MPS-2019-7047)|CVE-2019-12384|中危|
|FasterXML jackson-databind 反序列化漏洞(iBatis gadget绕过)|反序列化|[MPS-2019-7711](https://www.oscs1024.com/hd/MPS-2019-7711)|CVE-2018-11307|严重|
|FasterXML jackson-databind 反序列化漏洞(ehcache gadget绕过)|动态确定对象属性修改的控制不恰当|[MPS-2019-8717](https://www.oscs1024.com/hd/MPS-2019-8717)|CVE-2019-14379|严重|
|FasterXML jackson-databind 信息泄露漏洞(logback gadget绕过)|反序列化|[MPS-2019-8770](https://www.oscs1024.com/hd/MPS-2019-8770)|CVE-2019-14439|高危|
|OpenSSL 信任管理问题漏洞|证书验证不恰当|[MPS-2019-8829](https://www.oscs1024.com/hd/MPS-2019-8829)|CVE-2019-1552|低危|
|FasterXML jackson-databind反序列化漏洞(net.sf.ehcache gadget绕过)|反序列化|[MPS-2020-0063](https://www.oscs1024.com/hd/MPS-2020-0063)|CVE-2019-20330|严重|
|FasterXML jackson-databind反序列化漏洞(Anteros-DBCP gadget绕过)|反序列化|[MPS-2020-11987](https://www.oscs1024.com/hd/MPS-2020-11987)|CVE-2020-24616|高危|
|OpenSSL 加密问题漏洞|通过差异性导致的信息暴露|[MPS-2020-12634](https://www.oscs1024.com/hd/MPS-2020-12634)|CVE-2020-1968|低危|
|FasterXML jackson-databind 反序列化漏洞(pastdev gadget绕过)|反序列化|[MPS-2020-13151](https://www.oscs1024.com/hd/MPS-2020-13151)|CVE-2020-24750|高危|
|Apache HttpClient URI解析错误漏洞|XSS|[MPS-2020-17341](https://www.oscs1024.com/hd/MPS-2020-17341)|CVE-2020-13956|中危|
|FasterXML jackson-databind 代码问题漏洞|XXE|[MPS-2020-17358](https://www.oscs1024.com/hd/MPS-2020-17358)|CVE-2020-25649|高危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|OpenSSL 空指针取消引用漏洞|空指针取消引用|[MPS-2020-17574](https://www.oscs1024.com/hd/MPS-2020-17574)|CVE-2020-1971|中危|
|FasterXML jackson-databind 反序列化漏洞(commons-dbcp2 gadget绕过)|反序列化|[MPS-2020-17696](https://www.oscs1024.com/hd/MPS-2020-17696)|CVE-2020-35490|高危|
|FasterXML jackson-databind 反序列化漏洞(commons-dbcp2 gadget绕过)|反序列化|[MPS-2020-17697](https://www.oscs1024.com/hd/MPS-2020-17697)|CVE-2020-35491|高危|
|FasterXML jackson-databind 反序列化漏洞(glassfish gadget绕过)|反序列化|[MPS-2020-18089](https://www.oscs1024.com/hd/MPS-2020-18089)|CVE-2020-35728|高危|
|FasterXML jackson-databind 反序列化漏洞(xbean-reflect gadget绕过)|反序列化|[MPS-2020-2030](https://www.oscs1024.com/hd/MPS-2020-2030)|CVE-2020-8840|严重|
|FasterXML jackson-databind 反序列化漏洞(ignite-jta gadget绕过)|反序列化|[MPS-2020-24779](https://www.oscs1024.com/hd/MPS-2020-24779)|CVE-2020-10650|高危|
|FasterXML jackson-databind 代码问题漏洞|反序列化|[MPS-2020-3040](https://www.oscs1024.com/hd/MPS-2020-3040)|CVE-2020-9546|严重|
|FasterXML jackson-databind 反序列化漏洞(JtaTransactionConfig gadget绕过)|反序列化|[MPS-2020-3041](https://www.oscs1024.com/hd/MPS-2020-3041)|CVE-2020-9547|严重|
|FasterXML jackson-databind反序列化漏洞(anteros-core gadget绕过)|反序列化|[MPS-2020-3042](https://www.oscs1024.com/hd/MPS-2020-3042)|CVE-2020-9548|严重|
|FasterXML jackson-databind 反序列化漏洞(commons-configuration gadget绕过)|反序列化|[MPS-2020-3075](https://www.oscs1024.com/hd/MPS-2020-3075)|CVE-2019-14892|严重|
|FasterXML Jackson-databind反序列化漏洞(xalan2 gadget绕过)|反序列化|[MPS-2020-3094](https://www.oscs1024.com/hd/MPS-2020-3094)|CVE-2019-14893|严重|
|FasterXML jackson-databind反序列化漏洞(aries.transaction.jms gadget绕过)|反序列化|[MPS-2020-4131](https://www.oscs1024.com/hd/MPS-2020-4131)|CVE-2020-10672|高危|
|FasterXML jackson-databind反序列化漏洞(caucho-quercus gadget绕过)|反序列化|[MPS-2020-4132](https://www.oscs1024.com/hd/MPS-2020-4132)|CVE-2020-10673|高危|
|FasterXML jackson-databind反序列化漏洞(bus-proxy gadget绕过)|反序列化|[MPS-2020-4658](https://www.oscs1024.com/hd/MPS-2020-4658)|CVE-2020-10968|高危|
|FasterXML jackson-databind反序列化漏洞(javax.swing gadget绕过)|反序列化|[MPS-2020-4659](https://www.oscs1024.com/hd/MPS-2020-4659)|CVE-2020-10969|高危|
|FasterXML jackson-databind反序列化漏洞(activemq gadget绕过)|反序列化|[MPS-2020-4754](https://www.oscs1024.com/hd/MPS-2020-4754)|CVE-2020-11111|高危|
|FasterXML jackson-databind反序列化漏洞(commons-proxy gadget绕过)|反序列化|[MPS-2020-4755](https://www.oscs1024.com/hd/MPS-2020-4755)|CVE-2020-11112|高危|
|FasterXML jackson-databind反序列化漏洞(openjpa gadget绕过)|反序列化|[MPS-2020-4756](https://www.oscs1024.com/hd/MPS-2020-4756)|CVE-2020-11113|高危|
|FasterXML jackson-databind 反序列化漏洞(spring-aop gadget绕过)|反序列化|[MPS-2020-5138](https://www.oscs1024.com/hd/MPS-2020-5138)|CVE-2020-11619|高危|
|FasterXML jackson-databind 反序列化漏洞(commons-jelly gadget绕过)|反序列化|[MPS-2020-5139](https://www.oscs1024.com/hd/MPS-2020-5139)|CVE-2020-11620|高危|
|Apache Log4j2 SmtpAppender证书验证不当漏洞|证书验证不恰当|[MPS-2020-6684](https://www.oscs1024.com/hd/MPS-2020-6684)|CVE-2020-9488|低危|
|dom4j SaxReader函数存在 XXE 漏洞|XXE|[MPS-2020-6967](https://www.oscs1024.com/hd/MPS-2020-6967)|CVE-2020-10683|严重|
|FasterXML jackson-databind反序列化漏洞(oracle-aqjms gadget绕过)|反序列化|[MPS-2020-8801](https://www.oscs1024.com/hd/MPS-2020-8801)|CVE-2020-14061|高危|
|FasterXML jackson-databind反序列化漏洞(xalan2 gadget绕过)|反序列化|[MPS-2020-8802](https://www.oscs1024.com/hd/MPS-2020-8802)|CVE-2020-14062|高危|
|FasterXML jackson-databind反序列化漏洞(apache drill gadget绕过)|反序列化|[MPS-2020-8803](https://www.oscs1024.com/hd/MPS-2020-8803)|CVE-2020-14060|高危|
|FasterXML jackson-databind代码问题漏洞(jsecurity gadget绕过)|反序列化|[MPS-2020-8911](https://www.oscs1024.com/hd/MPS-2020-8911)|CVE-2020-14195|高危|
|FasterXML jackson-databind 反序列化漏洞(DBCP gadget绕过)|反序列化|[MPS-2021-0202](https://www.oscs1024.com/hd/MPS-2021-0202)|CVE-2020-36179|高危|
|FasterXML jackson-databind 反序列化漏洞(DBCP gadget绕过)|反序列化|[MPS-2021-0203](https://www.oscs1024.com/hd/MPS-2021-0203)|CVE-2020-36181|高危|
|FasterXML jackson-databind 反序列化漏洞(DBCP gadget绕过)|反序列化|[MPS-2021-0204](https://www.oscs1024.com/hd/MPS-2021-0204)|CVE-2020-36180|高危|
|FasterXML jackson-databind 反序列化漏洞(tomcat-dbcp gadget绕过)|反序列化|[MPS-2021-0205](https://www.oscs1024.com/hd/MPS-2021-0205)|CVE-2020-36182|高危|
|FasterXML jackson-databind 反序列化漏洞(docx4j gadget绕过)|反序列化|[MPS-2021-0206](https://www.oscs1024.com/hd/MPS-2021-0206)|CVE-2020-36183|高危|
|FasterXML jackson-databind 反序列化漏洞(tomcat-dbcp gadget绕过)|反序列化|[MPS-2021-0207](https://www.oscs1024.com/hd/MPS-2021-0207)|CVE-2020-36184|高危|
|FasterXML jackson-databind 反序列化漏洞(tomcat-dbcp gadget绕过)|反序列化|[MPS-2021-0208](https://www.oscs1024.com/hd/MPS-2021-0208)|CVE-2020-36185|高危|
|FasterXML jackson-databind 反序列化漏洞(naming-factory-dbcp gadget绕过)|反序列化|[MPS-2021-0209](https://www.oscs1024.com/hd/MPS-2021-0209)|CVE-2020-36186|高危|
|FasterXML jackson-databind 反序列化漏洞(naming-factory-dbcp gadget绕过)|反序列化|[MPS-2021-0210](https://www.oscs1024.com/hd/MPS-2021-0210)|CVE-2020-36187|高危|
|FasterXML jackson-databind 反序列化漏洞(newrelic-agent gadget绕过)|反序列化|[MPS-2021-0211](https://www.oscs1024.com/hd/MPS-2021-0211)|CVE-2020-36188|高危|
|FasterXML jackson-databind 反序列化漏洞(newrelic-agent gadget绕过)|反序列化|[MPS-2021-0212](https://www.oscs1024.com/hd/MPS-2021-0212)|CVE-2020-36189|高危|
|FasterXML jackson-databind 反序列化漏洞(javax.swing gadget绕过)|反序列化|[MPS-2021-1625](https://www.oscs1024.com/hd/MPS-2021-1625)|CVE-2021-20190|高危|
|OpenSSL 缓冲区错误漏洞|越界读取|[MPS-2021-17869](https://www.oscs1024.com/hd/MPS-2021-17869)|CVE-2021-3712|高危|
|OpenSSL 加密问题漏洞|加密强度不足|[MPS-2021-1869](https://www.oscs1024.com/hd/MPS-2021-1869)|CVE-2021-23839|低危|
|Google protobuf DOS漏洞|不正确的行为次序|[MPS-2021-19066](https://www.oscs1024.com/hd/MPS-2021-19066)|CVE-2021-22569|中危|
|FasterXML jackson-dataformat-cbor 内存耗尽漏洞|不加限制或调节的资源分配|[MPS-2021-1998](https://www.oscs1024.com/hd/MPS-2021-1998)|CVE-2020-28491|高危|
|OpenSSL 输入验证错误漏洞|整数溢出或环绕|[MPS-2021-2306](https://www.oscs1024.com/hd/MPS-2021-2306)|CVE-2021-23840|高危|
|OpenSSL 输入验证错误漏洞|空指针取消引用|[MPS-2021-2535](https://www.oscs1024.com/hd/MPS-2021-2535)|CVE-2021-23841|中危|
|Openssl 空指针取消引用漏洞|空指针取消引用|[MPS-2021-3619](https://www.oscs1024.com/hd/MPS-2021-3619)|CVE-2021-3449|中危|
|Apache Log4j JMSAppender反序列化漏洞||[MPS-2021-38359](https://www.oscs1024.com/hd/MPS-2021-38359)|CVE-2021-4104|高危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|AWS SDK for Java 路径遍历漏洞|路径遍历|[MPS-2022-11189](https://www.oscs1024.com/hd/MPS-2022-11189)|CVE-2022-31159|高危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|com.fasterxml.jackson.core:jackson-core 存在资源管理错误漏洞|资源管理错误|[MPS-2022-11944](https://www.oscs1024.com/hd/MPS-2022-11944)||中危|
|com.fasterxml.jackson.core:jackson-core  BigDecimal拒绝服务漏洞|资源管理错误|[MPS-2022-12166](https://www.oscs1024.com/hd/MPS-2022-12166)||中危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|com.fasterxml.jackson.core:jackson-databind 存在反序列化漏洞|反序列化|[MPS-2022-12433](https://www.oscs1024.com/hd/MPS-2022-12433)||高危|
|org.freemarker:freemarker <2.3.30 存在代码注入漏洞|代码注入|[MPS-2022-12438](https://www.oscs1024.com/hd/MPS-2022-12438)||高危|
|FasterXML Jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2022-12500](https://www.oscs1024.com/hd/MPS-2022-12500)||中危|
|Apache Log4j JDBCAppender SQL注入漏洞|SQL注入|[MPS-2022-1444](https://www.oscs1024.com/hd/MPS-2022-1444)|CVE-2022-23305|严重|
|Apache Log4j Chainsaw反序列化漏洞|反序列化|[MPS-2022-1445](https://www.oscs1024.com/hd/MPS-2022-1445)|CVE-2022-23307|高危|
|Apache Log4j 反序列化漏洞|反序列化|[MPS-2022-1446](https://www.oscs1024.com/hd/MPS-2022-1446)|CVE-2022-23302|高危|
|FasterXML jackson-databind 小于2.14.0-rc1拒绝服务漏洞|拒绝服务|[MPS-2022-58653](https://www.oscs1024.com/hd/MPS-2022-58653)|CVE-2022-42003|中危|
| FasterXML jackson-databind 小于2.13.4拒绝服务漏洞|拒绝服务|[MPS-2022-58654](https://www.oscs1024.com/hd/MPS-2022-58654)|CVE-2022-42004|中危|
|IBM WebSphere Application Server Liberty 存在拒绝服务漏洞|对因果或异常条件的不恰当检查|[MPS-2022-59813](https://www.oscs1024.com/hd/MPS-2022-59813)|CVE-2022-3509|中危|
|FasterXML jackson-databind 拒绝服务漏洞|越界写入|[MPS-2022-6242](https://www.oscs1024.com/hd/MPS-2022-6242)|CVE-2020-36518|高危|
|OpenSSL 安全漏洞|通过差异性导致的信息暴露|[MPS-2022-66954](https://www.oscs1024.com/hd/MPS-2022-66954)|CVE-2022-4304|中危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|OpenSSL 资源管理错误漏洞|UAF|[MPS-2023-1276](https://www.oscs1024.com/hd/MPS-2023-1276)|CVE-2023-0215|高危|
|jackson-databind 拒绝服务漏洞|拒绝服务|[MPS-2023-8438](https://www.oscs1024.com/hd/MPS-2023-8438)|CVE-2021-46877|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|OpenSSL 安全漏洞|过度迭代|[MPS-n3pe-ljgc](https://www.oscs1024.com/hd/MPS-n3pe-ljgc)|CVE-2023-3817|中危|
|【存在争议】FasterXML jackson-databind 代码问题漏洞|不加限制或调节的资源分配|[MPS-z1bx-p8y2](https://www.oscs1024.com/hd/MPS-z1bx-p8y2)|CVE-2023-35116|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.freemarker:freemarker|2.3.28|2.3.30|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|openssl|1.0.1m|3.1.3|间接依赖|建议修复|C:7|H:21|M:31|L:5|
|com.google.protobuf:protobuf-java|2.6.1|3.21.7|直接依赖|建议修复|C:0|H:1|M:2|L:0|
|com.amazonaws:aws-java-sdk-s3|1.11.603|1.12.261|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.6.7.2|2.14.0-rc1|间接依赖|建议修复|C:24|H:39|M:5|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.6.7.4|2.14.0-rc1|间接依赖|建议修复|C:5|H:19|M:5|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.6.7.1|2.14.0-rc1|间接依赖|建议修复|C:24|H:39|M:5|L:0|
|org.yaml:snakeyaml|2.0-SNAPSHOT|2.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|com.fasterxml.jackson.core:jackson-databind|2.10.1|2.14.0-rc1|间接依赖|建议修复|C:0|H:2|M:5|L:0|
|log4j:log4j|1.2.17||直接依赖|建议修复|C:2|H:3|M:0|L:1|
|com.fasterxml.jackson.core:jackson-databind|2.6.7.3|2.14.0-rc1|直接依赖|建议修复|C:9|H:35|M:5|L:0|
|dom4j:dom4j|1.6.1||直接依赖|建议修复|C:1|H:0|M:0|L:0|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.10.1|2.12.1|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|commons-codec:commons-codec|1.10|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|com.google.code.gson:gson|2.8.0|2.8.9|直接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.apache.httpcomponents:httpclient|4.5.5|4.5.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|26.0-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:1|
|commons-io:commons-io|2.4|2.7|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|20.0|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:2|L:1|
|com.fasterxml.jackson.core:jackson-core|2.6.7|2.8.6|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|com.google.guava:guava|18.0|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:2|L:1|
|org.apache.httpcomponents:httpclient|4.5.9|4.5.13|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|27.1-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:1|
|commons-codec:commons-codec|1.11|1.13|直接依赖|可选修复|C:0|H:0|M:0|L:1|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.6.7|2.12.1|直接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|202|Low|
|BSD-3-Clause|24|Low|
|MIT|38|Low|
|MPL-2.0|41|Low|
|自定义许可证|2|Low|
|BSD-2-Clause|6|Low|
|LGPL-2.1|1|Medium|
|MPL-1.1|1|Low|
|WTFPL|1|Low|
|OpenSSL|1|Low|
|Unicode-DFS-2016|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|go.opentelemetry.io/otel|v1.16.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ec2|v1.114.0|间接依赖|go|
|github.com/imdario/mergo|v0.3.15|间接依赖|go|
|github.com/spf13/cast|v1.5.1|间接依赖|go|
|github.com/agext/levenshtein|v1.2.3|间接依赖|go|
|org.checkerframework:checker-qual|2.5.2|直接依赖|maven|
|github.com/hashicorp/go-multierror|v1.1.1|直接依赖|go|
|github.com/hashicorp/hc-install|v0.6.0|间接依赖|go|
|com.amazonaws:dynamodb-streams-kinesis-adapter|1.5.0|直接依赖|maven|
|logkit:logkit|1.0.1|直接依赖|maven|
|github.com/hashicorp/go-checkpoint|v0.5.0|间接依赖|go|
|github.com/hashicorp/terraform-plugin-log|v0.9.0|直接依赖|go|
|dom4j:dom4j|1.6.1|直接依赖|maven|
|com.amazonaws:aws-java-sdk-kinesis|1.11.803|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/mediapackage|v1.23.3|直接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|直接依赖|go|
|joda-time:joda-time|2.5|间接依赖|maven|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230807174057-1744710a1577|间接依赖|go|
|github.com/Microsoft/go-winio|v0.6.1|间接依赖|go|
|libdl.so.2||间接依赖||
|github.com/evanphx/json-patch|v0.5.2|间接依赖|go|
|github.com/hashicorp/yamux|v0.1.1|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|com.amazonaws:jmespath-java|1.11.603|直接依赖|maven|
|com.google.protobuf:protobuf-java|2.6.1|直接依赖|maven|
|com.amazonaws:amazon-kinesis-client|1.11.2|直接依赖|maven|
|github.com/vmihailenco/msgpack|v4.0.4+incompatible|间接依赖|go|
|com.google.guava:guava|27.1-jre|直接依赖|maven|
|github.com/mitchellh/mapstructure|v1.5.0|直接依赖|go|
|org.slf4j:slf4j-api|1.7.24|直接依赖|maven|
|org.iban4j:iban4j|2.1.1|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/computeoptimizer|v1.27.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/oam|v1.2.5|直接依赖|go|
|com.amazonaws:aws-java-sdk-sts|1.11.803|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/feature/ec2/imds|v1.13.11|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/securitylake|v1.7.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/keyspaces|v1.4.5|直接依赖|go|
|github.com/aws/smithy-go|v1.14.2|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ssooidc|v1.15.5|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/cloudwatchlogs|v1.23.5|直接依赖|go|
|com.google.guava:failureaccess|1.0.1|直接依赖|maven|
|github.com/posener/complete|v1.2.3|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/appconfig|v1.18.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/codecatalyst|v1.5.5|直接依赖|go|
|org.freemarker:freemarker|2.3.28|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/docdbelastic|v1.2.5|直接依赖|go|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|com.fasterxml.jackson.core:jackson-core|2.10.0.pr1|直接依赖|maven|
|com.amazonaws:aws-java-sdk-cloudwatch|1.11.603|直接依赖|maven|
|github.com/hashicorp/go-hclog|v1.5.0|间接依赖|go|
|org.apache.commons:commons-lang3|3.3.2|间接依赖|maven|
|github.com/pquerna/otp|v1.4.0|直接依赖|go|
|github.com/hashicorp/terraform-plugin-go|v0.18.0|间接依赖|go|
|github.com/hashicorp/terraform-plugin-mux|v0.11.2|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/kafka|v1.22.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/comprehend|v1.25.5|直接依赖|go|
|github.com/boombuler/barcode|v1.0.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/fis|v1.15.5|直接依赖|go|
|xml-apis:xml-apis|1.0.b2|间接依赖|maven|
|github.com/YakDriver/regexache|v0.23.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/identitystore|v1.18.2|直接依赖|go|
|com.amazonaws:aws-java-sdk-kinesis|1.11.603|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/vpclattice|v1.1.7|间接依赖|go|
|org.apache.httpcomponents:httpcore|4.4.9|间接依赖|maven|
|com.amazonaws:aws-java-sdk-s3|1.11.603|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/internal/s3shared|v1.15.4|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/lightsail|v1.28.5|直接依赖|go|
|gopkg.in/dnaeon/go-vcr.v3|v3.1.2|直接依赖|go|
|github.com/hashicorp/terraform-provider-aws|v1.60.1-0.20220322001452-8f7a597d0c24|直接依赖|go|
|github.com/armon/go-radix|v1.0.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/checksum|v1.1.36|间接依赖|go|
|github.com/hashicorp/go-cleanhttp|v0.5.2|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/vpclattice|v1.2.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/endpoints/v2|v2.4.35|间接依赖|go|
|commons-lang:commons-lang|2.6|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/internal/v4a|v1.1.4|间接依赖|go|
|com.google.inject.extensions:guice-assistedinject|4.0|间接依赖|maven|
|github.com/hashicorp/terraform-plugin-framework-validators|v0.11.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/rds|v1.54.0|直接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|github.com/xeipuuv/gojsonpointer|v0.0.0-20190905194746-02993c407bfb|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/medialive|v1.34.4|间接依赖|go|
|github.com/beevik/etree|v1.2.0|直接依赖|go|
|com.google.errorprone:error_prone_annotations|2.1.3|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/emrserverless|v1.10.5|直接依赖|go|
|org.javassist:javassist|3.21.0-GA|直接依赖|maven|
|github.com/hashicorp/terraform-plugin-sdk/v2|v2.29.0|直接依赖|go|
|com.amazonaws:aws-java-sdk-kms|1.11.603|直接依赖|maven|
|github.com/Masterminds/sprig/v3|v3.2.3|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/iam|v1.22.5|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/redshiftdata|v1.20.5|直接依赖|go|
|github.com/hashicorp/terraform-plugin-framework-validators|v0.12.0|直接依赖|go|
|github.com/mitchellh/cli|v1.1.5|直接依赖|go|
|librt.so.1||间接依赖||
|github.com/spf13/cobra|v1.7.0|直接依赖|go|
|com.amazonaws:jmespath-java|1.11.754|直接依赖|maven|
|org.apache.commons:commons-lang3|3.7|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.5|间接依赖|maven|
|github.com/sergi/go-diff|v1.3.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/presigned-url|v1.9.35|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/verifiedpermissions|v1.1.5|间接依赖|go|
|com.google.guava:guava|18.0|直接依赖|maven|
|org.joda:joda-convert|1.2|直接依赖|maven|
|github.com/cloudflare/circl|v1.3.3|间接依赖|go|
|com.fasterxml.jackson.core:jackson-databind|2.6.7.3|直接依赖|maven|
|/usr/lib/libc++.1.dylib||间接依赖||
|libcurl|7.47.0|间接依赖||
|github.com/aws/aws-sdk-go|v1.45.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/pipes|v1.3.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/acm|v1.18.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sesv2|v1.19.5|间接依赖|go|
|com.google.j2objc:j2objc-annotations|1.1|直接依赖|maven|
|golang.org/x/tools|v0.12.1-0.20230815132531-74c255bcf846|直接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|直接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/imdario/mergo|v0.3.13|间接依赖|go|
|com.amazonaws:aws-java-sdk-core|1.11.754|直接依赖|maven|
|com.google.inject:guice|4.0|间接依赖|maven|
|github.com/hashicorp/hcl/v2|v2.17.0|间接依赖|go|
|github.com/hashicorp/logutils|v1.0.0|间接依赖|go|
|software.amazon.ion:ion-java|1.0.2|直接依赖|maven|
|github.com/hashicorp/terraform-exec|v0.18.1|间接依赖|go|
|github.com/hashicorp/aws-sdk-go-base/v2|v2.0.0-beta.34|间接依赖|go|
|github.com/bufbuild/protocompile|v0.6.0|间接依赖|go|
|golang.org/x/crypto|v0.12.0|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/hashicorp/terraform-plugin-go|v0.19.0|直接依赖|go|
|commons-codec:commons-codec|1.11|直接依赖|maven|
|com.google.guava:guava|26.0-jre|直接依赖|maven|
|github.com/mitchellh/go-wordwrap|v1.0.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ec2|v1.117.0|直接依赖|go|
|/System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation||间接依赖||
|github.com/hashicorp/go-version|v1.6.0|直接依赖|go|
|github.com/mattbaird/jsonpatch|v0.0.0-20230413205102-771768614e91|直接依赖|go|
|com.google.guava:guava|20.0|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/pricing|v1.21.6|直接依赖|go|
|com.amazonaws:aws-java-sdk-iam|1.11.803|间接依赖|maven|
|com.amazonaws:aws-java-sdk-dynamodb|1.11.603|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/internetmonitor|v1.5.4|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/s3|v1.38.5|直接依赖|go|
|github.com/hashicorp/terraform-plugin-framework|v1.4.0|直接依赖|go|
|github.com/skeema/knownhosts|v1.2.0|间接依赖|go|
|github.com/hashicorp/go-plugin|v1.4.10|间接依赖|go|
|com.amazonaws:aws-java-sdk-core|1.11.603|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.6.7.2|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.10.1|直接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|直接依赖|maven|
|org.reflections:reflections|0.9.11|直接依赖|maven|
|com.amazonaws:aws-java-sdk-kinesis|1.11.754|直接依赖|maven|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|github.com/mitchellh/go-testing-interface|v1.14.1|直接依赖|go|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|golang.org/x/text|v0.12.0|间接依赖|go|
|github.com/hashicorp/aws-sdk-go-base/v2/awsv1shim/v2|v2.0.0-beta.35|间接依赖|go|
|github.com/xeipuuv/gojsonreference|v0.0.0-20180127040603-bd5ef7bd5415|间接依赖|go|
|github.com/aws/aws-sdk-go|v1.44.328|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/rolesanywhere|v1.3.5|直接依赖|go|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.6.7|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.10.1|直接依赖|maven|
|github.com/hashicorp/terraform-svchost|v0.1.1|间接依赖|go|
|github.com/hashicorp/terraform-plugin-testing|v1.4.0|间接依赖|go|
|org.codehaus.mojo:animal-sniffer-annotations|1.14|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/internal/endpoint-discovery|v1.7.35|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/computeoptimizer|v1.25.5|间接依赖|go|
|golang.org/x/mod|v0.12.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/auditmanager|v1.26.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/rds|v1.51.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/workspaces|v1.30.0|直接依赖|go|
|github.com/shopspring/decimal|v1.3.1|直接依赖|go|
|org.apache.httpcomponents:httpcore|4.4.6|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/medialive|v1.36.0|直接依赖|go|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.10.1|间接依赖|maven|
|github.com/frankban/quicktest|v1.14.6|间接依赖|go|
|google.golang.org/protobuf|v1.31.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/config|v1.18.33|间接依赖|go|
|github.com/google/uuid|v1.3.0|间接依赖|go|
|openssl|1.0.1m|间接依赖||
|commons-codec:commons-codec|1.10|间接依赖|maven|
|gopkg.in/check.v1|v1.0.0-20201130134442-10cb98267c6c|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/xray|v1.17.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/signer|v1.16.5|直接依赖|go|
|github.com/hashicorp/go-cty|v1.4.1-0.20200414143053-d3edf31b6320|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/finspace|v1.12.0|直接依赖|go|
|github.com/hashicorp/terraform-plugin-sdk/v2|v2.27.0|直接依赖|go|
|github.com/oklog/run|v1.1.0|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|直接依赖|go|
|github.com/bgentry/speakeasy|v0.1.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/lexmodelsv2|v1.32.5|直接依赖|go|
|com.fasterxml.jackson.core:jackson-databind|2.6.7.4|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/qldb|v1.16.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/opensearchserverless|v1.4.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/kendra|v1.42.5|直接依赖|go|
|github.com/fatih/color|v1.15.0|间接依赖|go|
|com.amazonaws:jmespath-java|1.11.903|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/timestreamwrite|v1.18.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/swf|v1.17.3|直接依赖|go|
|github.com/hashicorp/aws-cloudformation-resource-schema-sdk-go|v0.21.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internetmonitor|v1.5.5|直接依赖|go|
|github.com/huandu/xstrings|v1.4.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/inspector2|v1.16.6|直接依赖|go|
|joda-time:joda-time|2.8.1|直接依赖|maven|
|com.amazonaws:aws-kinesisanalytics-flink|2.0.0|直接依赖|maven|
|com.amazonaws:aws-java-sdk-sts|1.11.754|直接依赖|maven|
|commons-logging:commons-logging|1.1.3|直接依赖|maven|
|com.github.jcustenborder.kafka.connect:connect-utils|0.4.164|直接依赖|maven|
|github.com/zclconf/go-cty|v1.13.2|间接依赖|go|
|joda-time:joda-time|2.3|间接依赖|maven|
|github.com/rogpeppe/go-internal|v1.11.0|间接依赖|go|
|log4j:log4j|1.2.17|直接依赖|maven|
|golang.org/x/sys|v0.12.0|间接依赖|go|
|github.com/mitchellh/reflectwalk|v1.0.2|间接依赖|go|
|github.com/vmihailenco/msgpack/v5|v5.3.5|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/rbin|v1.9.5|直接依赖|go|
|org.slf4j:slf4j-api|1.7.7|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/cleanrooms|v1.3.5|间接依赖|go|
|com.google.code.findbugs:jsr305|1.3.9|直接依赖|maven|
|golang.org/x/text|v0.13.0|间接依赖|go|
|org.apache.flink:flink-connector-kinesis_2.12||直接依赖|maven|
|io.codearte.jfairy:jfairy|0.5.3|直接依赖|maven|
|go.opentelemetry.io/otel/trace|v1.16.0|间接依赖|go|
|org.codehaus.mojo:animal-sniffer-annotations|1.17|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/ivschat|v1.5.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/accessanalyzer|v1.20.5|直接依赖|go|
|github.com/mattn/go-isatty|v0.0.19|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/verifiedpermissions|v1.2.1|直接依赖|go|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|com.fasterxml.jackson.core:jackson-core|2.6.7|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/sso|v1.13.5|间接依赖|go|
|github.com/hashicorp/awspolicyequivalence|v1.6.0|直接依赖|go|
|ld-linux-x86-64.so.2||间接依赖||
|google.golang.org/grpc|v1.57.0|间接依赖|go|
|avalon-framework:avalon-framework|4.1.5|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/sesv2|v1.20.0|直接依赖|go|
|com.amazonaws:aws-java-sdk-core|1.11.312|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/identitystore|v1.17.6|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/route53domains|v1.17.3|直接依赖|go|
|com.amazonaws:amazon-kinesis-producer|0.14.0|直接依赖|maven|
|github.com/apparentlymart/go-textseg/v15|v15.0.0|间接依赖|go|
|org.slf4j:slf4j-simple|1.7.24|直接依赖|maven|
|github.com/ProtonMail/go-crypto|v0.0.0-20230717121422-5aa5874ade95|直接依赖|go|
|org.apache.flink:force-shading|1.11.1|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/workspaces|v1.29.5|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sts|v1.21.5|间接依赖|go|
|github.com/hashicorp/terraform-registry-address|v0.2.2|间接依赖|go|
|syreclabs.com/go/faker|v1.2.3|直接依赖|go|
|dario.cat/mergo|v1.0.0|间接依赖|go|
|github.com/hashicorp/go-uuid|v1.0.3|直接依赖|go|
|libgcc_s.so.1||间接依赖||
|golang.org/x/exp|v0.0.0-20230811145659-89c5cff77bcb|直接依赖|go|
|github.com/hashicorp/hc-install|v0.5.2|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ssm|v1.37.5|直接依赖|go|
|com.fasterxml.jackson.core:jackson-annotations|2.10.0.pr1|直接依赖|maven|
|github.com/Masterminds/semver/v3|v3.2.1|间接依赖|go|
|com.google.code.gson:gson|2.8.0|直接依赖|maven|
|org.yaml:snakeyaml|2.0-SNAPSHOT|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.6.0|间接依赖|maven|
|javax.inject:javax.inject|1|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/internal/configsources|v1.1.41|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/codestarconnections|v1.15.5|直接依赖|go|
|org.apache.httpcomponents:httpcore|4.4.11|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/internal/accept-encoding|v1.9.14|间接依赖|go|
|com.fasterxml.jackson.core:jackson-databind|3.0.0-SNAPSHOT|直接依赖|maven|
|golang.org/x/exp|v0.0.0-20230817173708-d852ddb80c63|直接依赖|go|
|github.com/hashicorp/aws-sdk-go-base/v2|v2.0.0-beta.35|直接依赖|go|
|github.com/hashicorp/terraform-plugin-framework-timeouts|v0.4.1|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/transcribe|v1.28.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/credentials|v1.13.32|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/healthlake|v1.17.5|直接依赖|go|
|org.apache.httpcomponents:httpclient|4.5.9|直接依赖|maven|
|com.amazonaws:aws-java-sdk-core|1.11.903|直接依赖|maven|
|github.com/zclconf/go-cty|v1.14.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2|v1.21.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/cloudcontrol|v1.12.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/glacier|v1.15.5|直接依赖|go|
|github.com/Masterminds/goutils|v1.1.1|间接依赖|go|
|org.slf4j:slf4j-api|1.7.25|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.6.7.1|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/kafka|v1.22.5|间接依赖|go|
|com.google.code.findbugs:jsr305|3.0.2|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/securitylake|v1.6.5|间接依赖|go|
|github.com/xeipuuv/gojsonschema|v1.2.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ssmincidents|v1.22.5|直接依赖|go|
|github.com/hashicorp/aws-sdk-go-base/v2/awsv1shim/v2|v2.0.0-beta.36|直接依赖|go|
|com.amazonaws:aws-kinesisanalytics-runtime|1.2.0|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/cleanrooms|v1.4.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/s3control|v1.32.5|间接依赖|go|
|/usr/lib/libSystem.B.dylib||间接依赖||
|github.com/hashicorp/terraform-plugin-testing|v1.5.1|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/resourceexplorer2|v1.3.5|直接依赖|go|
|libm.so.6||间接依赖||
|github.com/mitchellh/copystructure|v1.2.0|直接依赖|go|
|github.com/hashicorp/terraform-exec|v0.19.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/codestarnotifications|v1.15.5|直接依赖|go|
|golang.org/x/crypto|v0.13.0|直接依赖|go|
|github.com/hashicorp/hcl/v2|v2.18.0|直接依赖|go|
|com.fasterxml.jackson.core:jackson-databind|2.10.1|间接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.2.0|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/directoryservice|v1.18.5|直接依赖|go|
|github.com/go-test/deep|v1.1.0|间接依赖|go|
|github.com/hashicorp/go-plugin|v1.5.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/ini|v1.3.39|间接依赖|go|
|commons-io:commons-io|2.4|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/lambda|v1.39.5|直接依赖|go|
|commons-logging:commons-logging|1.2|直接依赖|maven|
|libpthread.so.0||间接依赖||
|github.com/hashicorp/errwrap|v1.1.0|间接依赖|go|
|libc.so.6||间接依赖||
|org.apache.httpcomponents:httpcore|4.4.13|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/scheduler|v1.2.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/account|v1.11.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ssmcontacts|v1.16.5|直接依赖|go|
|golang.org/x/sys|v0.11.0|间接依赖|go|
|github.com/hashicorp/terraform-plugin-mux|v0.12.0|直接依赖|go|
|github.com/hashicorp/terraform-plugin-framework|v1.3.5|间接依赖|go|
|github.com/google/uuid|v1.3.1|间接依赖|go|
|github.com/vmihailenco/tagparser/v2|v2.0.0|间接依赖|go|
|github.com/YakDriver/regexache|v0.7.0|间接依赖|go|
|github.com/hashicorp/terraform-json|v0.17.1|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|golang.org/x/net|v0.14.0|间接依赖|go|
|github.com/aws-cloudformation/cloudformation-cli-go-plugin|v1.0.3|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/feature/ec2/imds|v1.13.10|间接依赖|go|
|github.com/apparentlymart/go-textseg/v13|v13.0.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/s3control|v1.33.0|直接依赖|go|
|com.amazonaws:aws-java-sdk-logs|1.11.903|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/aws/protocol/eventstream|v1.4.13|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)