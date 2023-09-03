# sherlock-project/sherlock安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698400721791746048.svg)](https://www.murphysec.com/console/report/1698400721527504896/1698400721791746048)

仓库描述：🔎 Hunt down social media accounts by username across social networks

仓库地址：[https://github.com/sherlock-project/sherlock](https://github.com/sherlock-project/sherlock)

| star：43023 | watch：1024 | fork：5270 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-02 16:57:43 | 许可证：MIT |
| 最近检测时间：2023-09-04 02:21:04 | 组件总数：11 | 漏洞总数：3 |

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
|certifi|2019.6.16|2023.7.22|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|requests|2.22.0|2.31.0|间接依赖|建议修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|2|Low|
|MPL-2.0|1|Low|
|Apache-2.0|2|Low|
|LGPL-3.0|1|Medium|
|AGPL-3.0-or-later|1|Low|
|MIT|1|Low|
|BSD-3-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|colorama|0.4.1|间接依赖|pip|
|requirements.txt||间接依赖|pip|
|certifi|2019.6.16|间接依赖|pip|
|requests-futures|1.0.0|间接依赖|pip|
|requests|2.22.0|间接依赖|pip|
|stem|1.8.0|间接依赖|pip|
|PySocks|1.7.0|间接依赖|pip|
|exrex|0.11.0|间接依赖|pip|
|openpyxl|3.0.10|间接依赖|pip|
|pandas|1.0.0|间接依赖|pip|
|torrequest|0.1.0|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)