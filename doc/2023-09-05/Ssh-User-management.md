# HamedAp/Ssh-User-management安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698764961563328512.svg)](https://www.murphysec.com/console/report/1691516694516490240/1698764961563328512)

仓库描述：SSH User Management With Add/Delete Users - Online Users - Limit Users 

仓库地址：[https://github.com/HamedAp/Ssh-User-management](https://github.com/HamedAp/Ssh-User-management)

| star：658 | watch：10 | fork：72 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-04 14:13:39 | 许可证：MIT |
| 最近检测时间：2023-09-05 02:29:37 | 组件总数：36 | 漏洞总数：25 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|OpenSSL 输入验证错误漏洞|整数溢出或环绕|[MPS-2019-15892](https://www.oscs1024.com/hd/MPS-2019-15892)|CVE-2019-1551|中危|
|OpenSSL 空指针取消引用漏洞|空指针取消引用|[MPS-2020-17574](https://www.oscs1024.com/hd/MPS-2020-17574)|CVE-2020-1971|中危|
|OpenSSL 空指针取消引用漏洞|空指针取消引用|[MPS-2020-6290](https://www.oscs1024.com/hd/MPS-2020-6290)|CVE-2020-1967|高危|
|OpenSSL 缓冲区错误漏洞|越界读取|[MPS-2021-17869](https://www.oscs1024.com/hd/MPS-2021-17869)|CVE-2021-3712|高危|
|OpenSSL 缓冲区错误漏洞|经典缓冲区溢出|[MPS-2021-17870](https://www.oscs1024.com/hd/MPS-2021-17870)|CVE-2021-3711|严重|
|OpenSSL 加密问题漏洞|加密强度不足|[MPS-2021-1869](https://www.oscs1024.com/hd/MPS-2021-1869)|CVE-2021-23839|低危|
|OpenSSL 输入验证错误漏洞|整数溢出或环绕|[MPS-2021-2306](https://www.oscs1024.com/hd/MPS-2021-2306)|CVE-2021-23840|高危|
|OpenSSL 输入验证错误漏洞|空指针取消引用|[MPS-2021-2535](https://www.oscs1024.com/hd/MPS-2021-2535)|CVE-2021-23841|中危|
|Openssl 空指针取消引用漏洞|空指针取消引用|[MPS-2021-3619](https://www.oscs1024.com/hd/MPS-2021-3619)|CVE-2021-3449|中危|
|OpenSSL 输入验证错误漏洞|输入验证不恰当|[MPS-2021-39449](https://www.oscs1024.com/hd/MPS-2021-39449)|CVE-2021-4160|中危|
|OpenSSL 存在任意命令执行漏洞|OS命令注入|[MPS-2022-18279](https://www.oscs1024.com/hd/MPS-2022-18279)|CVE-2022-2068|严重|
|OpenSSL 存在加密信息不全漏洞|加密强度不足|[MPS-2022-19044](https://www.oscs1024.com/hd/MPS-2022-19044)|CVE-2022-2097|高危|
|OpenSSL 拒绝服务漏洞|不可达退出条件的循环（无限循环）|[MPS-2022-5555](https://www.oscs1024.com/hd/MPS-2022-5555)|CVE-2022-0778|高危|
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58307](https://www.oscs1024.com/hd/MPS-2022-58307)|CVE-2022-41723|高危|
|OpenSSL 安全漏洞|通过差异性导致的信息暴露|[MPS-2022-66954](https://www.oscs1024.com/hd/MPS-2022-66954)|CVE-2022-4304|中危|
|OpenSSL 资源管理错误漏洞|双重释放|[MPS-2022-67892](https://www.oscs1024.com/hd/MPS-2022-67892)|CVE-2022-4450|高危|
|OpenSSL 操作系统命令注入漏洞|OS命令注入|[MPS-2022-8314](https://www.oscs1024.com/hd/MPS-2022-8314)|CVE-2022-1292|严重|
|Google Go 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2022-9049](https://www.oscs1024.com/hd/MPS-2022-9049)|CVE-2022-29526|中危|
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
|golang.org/x/net|v0.0.0-20210226172049-e18ecbb05110|0.7.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|openssl|1.1.1d|3.1.2|间接依赖|建议修复|C:3|H:8|M:11|L:1|
|golang.org/x/sys|v0.0.0-20201119102817-f84b799fce68|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|LGPL-3.0|1|Medium|
|Apache-2.0|8|Low|
|MIT|9|Low|
|BSD-3-Clause|8|Low|
|BSD-2-Clause|1|Low|
|OpenSSL|1|Low|
|MPL-2.0|1|Low|
|自定义许可证|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|libm.so||间接依赖||
|libz.so||间接依赖||
|ru.curs:celesta-unit||间接依赖|maven|
|com.github.bumptech.glide:glide||间接依赖|maven|
|io.segment.android:analytics|1.2.0|间接依赖|maven|
|golang.org/x/net|v0.0.0-20210226172049-e18ecbb05110|间接依赖|go|
|github.com/xtaci/smux|v1.5.15|间接依赖|go|
|github.com/klauspost/cpuid|v1.3.1|间接依赖|go|
|org.connectbot:sshlib||间接依赖|maven|
|libc.so||间接依赖||
|io.teecube.t3:t3-common||间接依赖|maven|
|io.coodoo:s3Upload||间接依赖|maven|
|io.xream.x7:spring-boot-starter-x7||间接依赖|maven|
|com.google.firebase:firebase-admin||间接依赖|maven|
|com.segment.analytics.android.integrations:firebase||间接依赖|maven|
|com.abubusoft:kripton-arch-integration||间接依赖|maven|
|liblog.so||间接依赖||
|github.com/templexxx/cpu|v0.0.7|间接依赖|go|
|golang.org/x/crypto|v0.0.0-20210322153248-0c34fe9e7dc2|间接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|com.google.crypto.tink:tink-android||间接依赖|maven|
|openssl|1.1.1d|间接依赖||
|libstdc++.so||间接依赖||
|github.com/tjfoc/gmsm|v1.3.2|间接依赖|go|
|com.lotame:cc-android-sdk|2.3.0.4|间接依赖|maven|
|github.com/flynn/noise|v1.0.0|间接依赖|go|
|libdl.so||间接依赖||
|golang.org/x/text|v0.3.3|间接依赖|go|
|golang.org/x/sys|v0.0.0-20201119102817-f84b799fce68|间接依赖|go|
|io.homunculus:hcf-codegen||间接依赖|maven|
|github.com/refraction-networking/utls|v1.0.0|间接依赖|go|
|github.com/klauspost/reedsolomon|v1.9.9|间接依赖|go|
|me.laoyuyu.keepassa:KPAFrame||间接依赖|maven|
|com.groupdocs:groupdocs-conversion|1.3.0|间接依赖|maven|
|github.com/templexxx/xorsimd|v0.4.1|间接依赖|go|
|github.com/xtaci/kcp-go/v5|v5.6.1|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)