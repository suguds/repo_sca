# public-apis/public-apis安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696588780675690496.svg)](https://www.murphysec.com/console/report/1696226218545147904/1696588780675690496)

仓库描述：A collective list of free APIs

仓库地址：[https://github.com/public-apis/public-apis](https://github.com/public-apis/public-apis)

| star：253419 | watch：3903 | fork：29033 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-29 21:31:17 | 许可证：MIT |
| 最近检测时间：2023-08-30 02:21:20 | 组件总数：5 | 漏洞总数：3 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Certifi 存在数据真实性验证不充分漏洞|对数据真实性的验证不充分|[MPS-2022-1918](https://www.oscs1024.com/hd/MPS-2022-1918)|CVE-2022-23491|中危|
|Certifi 数据伪造问题漏洞|对数据真实性的验证不充分|[MPS-ck78-r6zg](https://www.oscs1024.com/hd/MPS-ck78-r6zg)|CVE-2023-37920|严重|
|Requests Proxy-Authorization 标头泄露漏洞|未授权敏感信息泄露|[MPS-hr61-tzey](https://www.oscs1024.com/hd/MPS-hr61-tzey)|CVE-2023-32681|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|requests|2.27.1|2.31.0|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|certifi|2021.10.8|2023.7.22|间接依赖|建议修复|C:1|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|1|Low|
|MIT|2|Low|
|MPL-2.0|1|Low|
|自定义许可证|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|requests|2.27.1|间接依赖|pip|
|charset-normalizer|2.0.10|间接依赖|pip|
|certifi|2021.10.8|间接依赖|pip|
|idna|3.3|间接依赖|pip|
|urllib3|1.26.8|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)