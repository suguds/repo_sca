# MoKee/android_packages_apps_WarpShare安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1693322285913362432.svg)](https://www.murphysec.com/console/report/1693322285871419392/1693322285913362432)

仓库描述：None

仓库地址：[https://github.com/MoKee/android_packages_apps_WarpShare](https://github.com/MoKee/android_packages_apps_WarpShare)

| star：343 | watch：8 | fork：29 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2022-06-10 13:15:32 | 许可证：- |
| 最近检测时间：2023-08-21 02:04:59 | 组件总数：14 | 漏洞总数：15 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|OpenSSL 加密问题漏洞|密码算法不安全|[MPS-2018-14230](https://www.oscs1024.com/hd/MPS-2018-14230)|CVE-2018-0735|中危|
|OpenSSL 加密问题漏洞|密码算法不安全|[MPS-2018-14285](https://www.oscs1024.com/hd/MPS-2018-14285)|CVE-2018-0734|中危|
|OpenSSL 信息泄露漏洞|通过差异性导致的信息暴露|[MPS-2018-14899](https://www.oscs1024.com/hd/MPS-2018-14899)|CVE-2018-5407|中危|
|OpenSSL 加密问题漏洞|密码算法不安全|[MPS-2018-4731](https://www.oscs1024.com/hd/MPS-2018-4731)|CVE-2018-0737|中危|
|Openssl OpenSSL 加密问题漏洞|密钥管理错误|[MPS-2018-7822](https://www.oscs1024.com/hd/MPS-2018-7822)|CVE-2018-0732|高危|
|OpenSSL 安全漏洞|服务端安全的客户端实施|[MPS-2019-11271](https://www.oscs1024.com/hd/MPS-2019-11271)|CVE-2019-1547|中危|
|OpenSSL 安全漏洞||[MPS-2019-11273](https://www.oscs1024.com/hd/MPS-2019-11273)|CVE-2019-1563|低危|
|OpenSSL 安全特征问题漏洞||[MPS-2019-2244](https://www.oscs1024.com/hd/MPS-2019-2244)|CVE-2019-1543|高危|
|OpenSSL 信任管理问题漏洞|证书验证不恰当|[MPS-2019-8829](https://www.oscs1024.com/hd/MPS-2019-8829)|CVE-2019-1552|低危|
|OpenSSL 空指针取消引用漏洞|空指针取消引用|[MPS-2020-17574](https://www.oscs1024.com/hd/MPS-2020-17574)|CVE-2020-1971|中危|
|OpenSSL 缓冲区错误漏洞|越界读取|[MPS-2021-17869](https://www.oscs1024.com/hd/MPS-2021-17869)|CVE-2021-3712|高危|
|OpenSSL 加密问题漏洞|加密强度不足|[MPS-2021-1869](https://www.oscs1024.com/hd/MPS-2021-1869)|CVE-2021-23839|低危|
|Openssl 空指针取消引用漏洞|空指针取消引用|[MPS-2021-3619](https://www.oscs1024.com/hd/MPS-2021-3619)|CVE-2021-3449|中危|
|Expat 资源管理错误漏洞|数值计算不正确|[MPS-2022-0004](https://www.oscs1024.com/hd/MPS-2022-0004)|CVE-2021-45960|高危|
|OpenSSL 安全漏洞|过度迭代|[MPS-n3pe-ljgc](https://www.oscs1024.com/hd/MPS-n3pe-ljgc)|CVE-2023-3817|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|libexpat|2.2.0||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|openssl|1.1.0h|3.1.2|间接依赖|建议修复|C:0|H:3|M:8|L:3|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|2|Low|
|Apache-2.0|1|Low|
|BSD-2-Clause|1|Low|
|OpenSSL|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.tukaani:xz|1.8|直接依赖|maven|
|org.brotli:dec|0.1.2|直接依赖|maven|
|libc++_shared.so||间接依赖||
|libdl.so||间接依赖||
|libc.so||间接依赖||
|libm.so||间接依赖||
|androidx.annotation:annotation|1.0.1|直接依赖|maven|
|com.jakewharton:butterknife|9.0.0-rc1|直接依赖|maven|
|com.github.luben:zstd-jni|1.4.0-1|直接依赖|maven|
|liblog.so||间接依赖||
|org.slf4j:slf4j-api|1.7.16|直接依赖|maven|
|libexpat|2.2.0|间接依赖||
|androidx.appcompat:appcompat|1.0.2|直接依赖|maven|
|openssl|1.1.0h|间接依赖||


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)