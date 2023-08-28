# yuantuo666/baiduwp-php安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696227696987430912.svg)](https://www.murphysec.com/console/report/1696227696937099264/1696227696987430912)

仓库描述：A tool to get the download link of the Baidu netdisk / 一个获取百度网盘分享链接下载地址的工具

仓库地址：[https://github.com/yuantuo666/baiduwp-php](https://github.com/yuantuo666/baiduwp-php)

| star：5096 | watch：61 | fork：1277 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-16 14:52:01 | 许可证：MIT |
| 最近检测时间：2023-08-29 02:26:21 | 组件总数：14 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|libssh2 输入验证错误漏洞|整数溢出或环绕|[MPS-2019-13574](https://www.oscs1024.com/hd/MPS-2019-13574)|CVE-2019-17498|高危|
|Expat 资源管理错误漏洞|数值计算不正确|[MPS-2022-0004](https://www.oscs1024.com/hd/MPS-2022-0004)|CVE-2021-45960|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|libexpat|2.2.7||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|libssh2|1.9.0|1.10.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|libssh2|1.9.0|间接依赖||
|IPHLPAPI.DLL||间接依赖||
|CRYPT32.dll||间接依赖||
|WSOCK32.dll||间接依赖||
|Secur32.dll||间接依赖||
|WSOCK32.DLL||间接依赖||
|ADVAPI32.dll||间接依赖||
|WS2_32.dll||间接依赖||
|KERNEL32.dll||间接依赖||
|msvcrt.dll||间接依赖||
|libexpat|2.2.7|间接依赖||
|SHELL32.dll||间接依赖||
|bcrypt.dll||间接依赖||
|USER32.dll||间接依赖||


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)