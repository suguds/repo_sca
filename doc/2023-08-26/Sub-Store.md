# sub-store-org/Sub-Store安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695145528860766208.svg)](https://www.murphysec.com/console/report/1694417175631523840/1695145528860766208)

仓库描述：Advanced Subscription Manager for QX, Loon, Surge, Stash and ShadowRocket!

仓库地址：[https://github.com/sub-store-org/Sub-Store](https://github.com/sub-store-org/Sub-Store)

| star：2922 | watch：78 | fork：334 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-25 22:48:06 | 许可证：AGPL-3.0 |
| 最近检测时间：2023-08-26 02:46:22 | 组件总数：5 | 漏洞总数：6 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Axios 服务器端请求伪造漏洞|SSRF|[MPS-2020-16365](https://www.oscs1024.com/hd/MPS-2020-16365)|CVE-2020-28168|中危|
|lodash 拒绝服务漏洞|拒绝服务|[MPS-2021-2574](https://www.oscs1024.com/hd/MPS-2021-2574)|CVE-2020-28500|中危|
|lodash 命令注入漏洞|代码注入|[MPS-2021-2638](https://www.oscs1024.com/hd/MPS-2021-2638)|CVE-2021-23337|高危|
|Axios 拒绝服务漏洞|拒绝服务|[MPS-2021-30688](https://www.oscs1024.com/hd/MPS-2021-30688)|CVE-2021-3749|高危|
|follow-redirects <1.14.7 存在信息泄露漏洞|侵犯隐私|[MPS-2022-0815](https://www.oscs1024.com/hd/MPS-2022-0815)|CVE-2022-0155|中危|
|follow-redirects<1.14.8 信息暴露漏洞|未授权敏感信息泄露|[MPS-2022-3636](https://www.oscs1024.com/hd/MPS-2022-3636)|CVE-2022-0536|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|axios|0.19.2|0.21.3|直接依赖|建议修复|C:0|H:1|M:1|L:0|
|follow-redirects|1.5.10|1.14.8|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|lodash|4.17.20|4.17.21|直接依赖|可选修复|C:0|H:1|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|5|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|ms|2.0.0|间接依赖|npm|
|follow-redirects|1.5.10|间接依赖|npm|
|axios|0.19.2|直接依赖|npm|
|debug|3.1.0|间接依赖|npm|
|lodash|4.17.20|直接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)