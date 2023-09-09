# lecepin/WeChatVideoDownloader安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700579616891912192.svg)](https://www.murphysec.com/console/report/1699491117712146432/1700579616891912192)

仓库描述：超方便的微信视频号下载器

仓库地址：[https://github.com/lecepin/WeChatVideoDownloader](https://github.com/lecepin/WeChatVideoDownloader)

| star：2035 | watch：22 | fork：390 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-08 14:04:51 | 许可证：- |
| 最近检测时间：2023-09-10 02:39:24 | 组件总数：8 | 漏洞总数：26 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|OpenSSL 安全漏洞|缓冲区溢出|[MPS-2016-2086](https://www.oscs1024.com/hd/MPS-2016-2086)|CVE-2016-2176|高危|
|OpenSSL MDC2_Update 函数整数溢出漏洞|越界写入|[MPS-2016-4549](https://www.oscs1024.com/hd/MPS-2016-4549)|CVE-2016-6303|严重|
|OpenSSL 安全漏洞|服务端安全的客户端实施|[MPS-2019-11271](https://www.oscs1024.com/hd/MPS-2019-11271)|CVE-2019-1547|中危|
|OpenSSL 安全漏洞||[MPS-2019-11273](https://www.oscs1024.com/hd/MPS-2019-11273)|CVE-2019-1563|低危|
|OpenSSL 输入验证错误漏洞|整数溢出或环绕|[MPS-2019-15892](https://www.oscs1024.com/hd/MPS-2019-15892)|CVE-2019-1551|中危|
|OpenSSL 信息泄露漏洞|通过差异性导致的信息暴露|[MPS-2019-1990](https://www.oscs1024.com/hd/MPS-2019-1990)|CVE-2019-1559|中危|
|OpenSSL 信任管理问题漏洞|证书验证不恰当|[MPS-2019-8829](https://www.oscs1024.com/hd/MPS-2019-8829)|CVE-2019-1552|低危|
|OpenSSL 加密问题漏洞|通过差异性导致的信息暴露|[MPS-2020-12634](https://www.oscs1024.com/hd/MPS-2020-12634)|CVE-2020-1968|低危|
|OpenSSL 空指针取消引用漏洞|空指针取消引用|[MPS-2020-17574](https://www.oscs1024.com/hd/MPS-2020-17574)|CVE-2020-1971|中危|
|OpenSSL 缓冲区错误漏洞|越界读取|[MPS-2021-17869](https://www.oscs1024.com/hd/MPS-2021-17869)|CVE-2021-3712|高危|
|OpenSSL 加密问题漏洞|加密强度不足|[MPS-2021-1869](https://www.oscs1024.com/hd/MPS-2021-1869)|CVE-2021-23839|低危|
|OpenSSL 输入验证错误漏洞|整数溢出或环绕|[MPS-2021-2306](https://www.oscs1024.com/hd/MPS-2021-2306)|CVE-2021-23840|高危|
|OpenSSL 输入验证错误漏洞|空指针取消引用|[MPS-2021-2535](https://www.oscs1024.com/hd/MPS-2021-2535)|CVE-2021-23841|中危|
|Openssl 空指针取消引用漏洞|空指针取消引用|[MPS-2021-3619](https://www.oscs1024.com/hd/MPS-2021-3619)|CVE-2021-3449|中危|
|OpenSSL 输入验证错误漏洞|输入验证不恰当|[MPS-2021-39449](https://www.oscs1024.com/hd/MPS-2021-39449)|CVE-2021-4160|中危|
|OpenSSL 存在任意命令执行漏洞|OS命令注入|[MPS-2022-18279](https://www.oscs1024.com/hd/MPS-2022-18279)|CVE-2022-2068|严重|
|OpenSSL 拒绝服务漏洞|不可达退出条件的循环（无限循环）|[MPS-2022-5555](https://www.oscs1024.com/hd/MPS-2022-5555)|CVE-2022-0778|高危|
|OpenSSL 安全漏洞|通过差异性导致的信息暴露|[MPS-2022-66954](https://www.oscs1024.com/hd/MPS-2022-66954)|CVE-2022-4304|中危|
|OpenSSL 操作系统命令注入漏洞|OS命令注入|[MPS-2022-8314](https://www.oscs1024.com/hd/MPS-2022-8314)|CVE-2022-1292|严重|
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
|openssl|1.0.2q|3.1.2|间接依赖|建议修复|C:3|H:6|M:13|L:4|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|OpenSSL|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|openssl|1.0.2q|间接依赖||
|USER32.dll||间接依赖||
|CRYPTUI.dll||间接依赖||
|ADVAPI32.dll||间接依赖||
|CRYPT32.dll||间接依赖||
|KERNEL32.dll||间接依赖||
|msvcrt.dll||间接依赖||
|GDI32.dll||间接依赖||


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)