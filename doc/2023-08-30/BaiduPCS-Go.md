# qjfoidnh/BaiduPCS-Go安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696587196403183616.svg)](https://www.murphysec.com/console/report/1696587196231217153/1696587196403183616)

仓库描述：iikira/BaiduPCS-Go原版基础上集成了分享链接/秒传链接转存功能

仓库地址：[https://github.com/qjfoidnh/BaiduPCS-Go](https://github.com/qjfoidnh/BaiduPCS-Go)

| star：2229 | watch：23 | fork：377 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-26 10:50:23 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-30 02:14:58 | 组件总数：31 | 漏洞总数：6 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|jwt-go 安全漏洞|授权检查缺失|[MPS-2020-13786](https://www.oscs1024.com/hd/MPS-2020-13786)|CVE-2020-26160|高危|
|GJSON 安全漏洞|拒绝服务|[MPS-2021-34246](https://www.oscs1024.com/hd/MPS-2021-34246)|CVE-2021-42836|高危|
|Gjson 安全漏洞|ReDoS|[MPS-2021-40195](https://www.oscs1024.com/hd/MPS-2021-40195)|CVE-2021-42248|高危|
|Tidwall Gjson 安全漏洞|拒绝服务|[MPS-2021-5980](https://www.oscs1024.com/hd/MPS-2021-5980)|CVE-2020-36066|高危|
|Tidwall Gjson 输入验证错误漏洞|对数组索引的验证不恰当|[MPS-2021-5981](https://www.oscs1024.com/hd/MPS-2021-5981)|CVE-2020-36067|高危|
|Google Go 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2022-9049](https://www.oscs1024.com/hd/MPS-2022-9049)|CVE-2022-29526|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/dgrijalva/jwt-go|v3.2.0+incompatible|4.0.0-preview1|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|github.com/tidwall/match|v1.0.1|1.0.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|github.com/tidwall/gjson|v1.6.4|1.9.3|直接依赖|建议修复|C:0|H:4|M:0|L:0|
|golang.org/x/sys|v0.0.0-20200615200032-f1bc736245b1|0.1.0|直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|17|Low|
|GPL-3.0|2|Medium|
|GPL-3.0-or-later|2|Low|
|BSD-3-Clause|5|Low|
|Apache-2.0|3|Low|
|BSD-2-Clause|3|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/tidwall/gjson|v1.6.4|直接依赖|go|
|github.com/mattn/go-colorable|v0.1.8|间接依赖|go|
|github.com/qjfoidnh/Baidu-Login|v1.4.0|直接依赖|go|
|github.com/urfave/cli|v1.22.5|直接依赖|go|
|github.com/fatih/color|v1.10.0|直接依赖|go|
|github.com/bmizerany/assert|v0.0.0-20160611221934-b7ed37b82869|间接依赖|go|
|github.com/kardianos/osext|v0.0.0-20190222173326-2bc1f35cddc0|直接依赖|go|
|github.com/oleiade/lane|v1.0.1|直接依赖|go|
|github.com/mattn/go-runewidth|v0.0.9|直接依赖|go|
|github.com/astaxie/beego|v1.12.3|间接依赖|go|
|github.com/shurcooL/sanitized_anchor_name|v1.0.0|间接依赖|go|
|golang.org/x/sys|v0.0.0-20200615200032-f1bc736245b1|直接依赖|go|
|github.com/tidwall/pretty|v1.0.2|间接依赖|go|
|github.com/json-iterator/go|v1.1.10|直接依赖|go|
|github.com/olekukonko/tablewriter|v0.0.4|直接依赖|go|
|github.com/mattn/go-isatty|v0.0.12|间接依赖|go|
|google.golang.org/protobuf|v1.23.0|间接依赖|go|
|github.com/golang/protobuf|v1.4.3|直接依赖|go|
|golang.org/x/crypto|v0.0.0-20191011191535-87dc89f01550|直接依赖|go|
|github.com/bitly/go-simplejson|v0.5.0|间接依赖|go|
|github.com/qjfoidnh/baidu-tools|v1.2.0|直接依赖|go|
|github.com/daaku/go.zipexe|v1.0.2|间接依赖|go|
|github.com/dgrijalva/jwt-go|v3.2.0+incompatible|直接依赖|go|
|github.com/russross/blackfriday/v2|v2.0.1|间接依赖|go|
|github.com/cpuguy83/go-md2man/v2|v2.0.0-20190314233015-f79a8a8ca69d|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.1|间接依赖|go|
|github.com/GeertJohan/go.incremental|v1.0.0|直接依赖|go|
|github.com/GeertJohan/go.rice|v1.0.2|间接依赖|go|
|github.com/peterh/liner|v1.2.1|直接依赖|go|
|github.com/tidwall/match|v1.0.1|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)