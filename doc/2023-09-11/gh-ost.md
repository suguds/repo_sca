# github/gh-ost安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700935460327129088.svg)](https://www.murphysec.com/console/report/1700935460192911360/1700935460327129088)

仓库描述：GitHub's Online Schema-migration Tool for MySQL

仓库地址：[https://github.com/github/gh-ost](https://github.com/github/gh-ost)

| star：11332 | watch：544 | fork：1307 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-06 15:02:14 | 许可证：MIT |
| 最近检测时间：2023-09-11 02:13:31 | 组件总数：18 | 漏洞总数：3 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|go.uuid 不安全的随机性漏洞|使用具有密码学弱点缺陷的PRNG|[MPS-2021-7854](https://www.oscs1024.com/hd/MPS-2021-7854)|CVE-2021-3538|严重|
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58307](https://www.oscs1024.com/hd/MPS-2022-58307)|CVE-2022-41723|高危|
|Google Go 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2022-9049](https://www.oscs1024.com/hd/MPS-2022-9049)|CVE-2022-29526|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|golang.org/x/net|v0.0.0-20210224082022-3d97a244fca7|0.7.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|github.com/satori/go.uuid|v1.2.0||直接依赖|建议修复|C:1|H:0|M:0|L:0|
|golang.org/x/sys|v0.0.0-20210615035016-665e8c7367d1|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|7|Low|
|MIT|7|Low|
|BSD-2-Clause|2|Low|
|MPL-2.0|1|Low|
|Apache-2.0|3|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|golang.org/x/sys|v0.0.0-20210615035016-665e8c7367d1|间接依赖|go|
|github.com/siddontang/go|v0.0.0-20180604090527-bdc77568d726|间接依赖|go|
|github.com/pingcap/errors|v0.11.5-0.20201126102027-b0a155152ca3|间接依赖|go|
|github.com/smartystreets/goconvey|v1.6.4|间接依赖|go|
|golang.org/x/text|v0.3.6|直接依赖|go|
|github.com/go-sql-driver/mysql|v1.6.0|直接依赖|go|
|github.com/go-ini/ini|v1.62.0|直接依赖|go|
|golang.org/x/crypto|v0.0.0-20210220033148-5ea612d1eb83|直接依赖|go|
|golang.org/x/term|v0.0.0-20220526004731-065cf7ba2467|间接依赖|go|
|go.uber.org/atomic|v1.7.0|间接依赖|go|
|gopkg.in/ini.v1|v1.62.0|间接依赖|go|
|golang.org/x/net|v0.0.0-20210224082022-3d97a244fca7|直接依赖|go|
|github.com/openark/golib|v0.0.0-20210531070646-355f37940af8|直接依赖|go|
|github.com/satori/go.uuid|v1.2.0|直接依赖|go|
|github.com/go-mysql-org/go-mysql|v1.3.0|直接依赖|go|
|github.com/shopspring/decimal|v0.0.0-20180709203117-cd690d0c9e24|间接依赖|go|
|gopkg.in/check.v1|v1.0.0-20201130134442-10cb98267c6c|间接依赖|go|
|github.com/siddontang/go-log|v0.0.0-20180807004314-8d05993dda07|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)