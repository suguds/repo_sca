# NationalSecurityAgency/ghidra安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692960551078748160.svg)](https://www.murphysec.com/console/report/1692960551032610816/1692960551078748160)

仓库描述：Ghidra is a software reverse engineering (SRE) framework

仓库地址：[https://github.com/NationalSecurityAgency/ghidra](https://github.com/NationalSecurityAgency/ghidra)

| star：41820 | watch：974 | fork：5075 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-19 01:32:24 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-20 02:08:25 | 组件总数：16 | 漏洞总数：13 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|GNU Libiberty 安全漏洞|输入验证不恰当|[MPS-2017-1331](https://www.oscs1024.com/hd/MPS-2017-1331)|CVE-2016-6131|高危|
|libiberty 数字错误漏洞||[MPS-2017-2066](https://www.oscs1024.com/hd/MPS-2017-2066)|CVE-2016-2226|高危|
|libiberty 安全漏洞|UAF|[MPS-2017-2070](https://www.oscs1024.com/hd/MPS-2017-2070)|CVE-2016-4487|中危|
|libiberty 安全漏洞|UAF|[MPS-2017-2071](https://www.oscs1024.com/hd/MPS-2017-2071)|CVE-2016-4488|中危|
|libiberty 数字错误漏洞|整数溢出或环绕|[MPS-2017-2072](https://www.oscs1024.com/hd/MPS-2017-2072)|CVE-2016-4489|中危|
|libiberty 数字错误漏洞|整数溢出或环绕|[MPS-2017-2073](https://www.oscs1024.com/hd/MPS-2017-2073)|CVE-2016-4490|中危|
|libiberty 安全漏洞|缓冲区溢出|[MPS-2017-2074](https://www.oscs1024.com/hd/MPS-2017-2074)|CVE-2016-4491|中危|
|libiberty 缓冲区错误漏洞|缓冲区溢出|[MPS-2017-2075](https://www.oscs1024.com/hd/MPS-2017-2075)|CVE-2016-4492|中危|
|libiberty 安全漏洞|越界读取|[MPS-2017-2076](https://www.oscs1024.com/hd/MPS-2017-2076)|CVE-2016-4493|中危|
|GNU Binutils 安全漏洞|不可达退出条件的循环（无限循环）|[MPS-2018-14162](https://www.oscs1024.com/hd/MPS-2018-14162)|CVE-2018-18700|中危|
|GNU Binutils GNU libiberty 安全漏洞|拒绝服务|[MPS-2018-8266](https://www.oscs1024.com/hd/MPS-2018-8266)|CVE-2018-12698|高危|
|GNU Binutils 缓冲区错误漏洞|越界读取|[MPS-2019-1889](https://www.oscs1024.com/hd/MPS-2019-1889)|CVE-2019-9070|高危|
|GNU libiberty 缓冲区错误漏洞|缓冲区溢出|[MPS-2021-32366](https://www.oscs1024.com/hd/MPS-2021-32366)|CVE-2021-3826|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|libiberty|9.1.0|20220713-1|间接依赖|建议修复|C:0|H:5|M:8|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|1|Low|
|MIT|1|Low|
|LGPL-2.1|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|libgcc_s.so.1||间接依赖||
|GDI32.dll||间接依赖||
|msv:relaxngDatatype|20050913|直接依赖|maven|
|org.jheaps:jheaps|0.13|直接依赖|maven|
|org.slf4j:slf4j-nop|1.7.25|直接依赖|maven|
|libm.so.6||间接依赖||
|libiberty|9.1.0|间接依赖||
|MSVCR100D.dll||间接依赖||
|ADVAPI32.DLL||间接依赖||
|KERNEL32.dll||间接依赖||
|msvcrt.dll||间接依赖||
|USER32.dll||间接依赖||
|libc.so.6||间接依赖||
|net.sf.sevenzipjbinding:sevenzipjbinding-all-platforms|16.02-2.01|直接依赖|maven|
|libstdc++.so.6||间接依赖||
|SHELL32.DLL||间接依赖||


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)