# Narasimha1997/fake-sms安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695499258303438848.svg)](https://www.murphysec.com/console/report/1695499257963700224/1695499258303438848)

仓库描述：A simple command line tool using which you can skip phone number based SMS verification by using a temporary phone number that acts like a proxy.

仓库地址：[https://github.com/Narasimha1997/fake-sms](https://github.com/Narasimha1997/fake-sms)

| star：2030 | watch：28 | fork：149 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-01 23:34:41 | 许可证：GPL-2.0 |
| 最近检测时间：2023-08-27 02:11:49 | 组件总数：15 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58307](https://www.oscs1024.com/hd/MPS-2022-58307)|CVE-2022-41723|高危|
|Google Go 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2022-9049](https://www.oscs1024.com/hd/MPS-2022-9049)|CVE-2022-29526|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|golang.org/x/net|v0.0.0-20200114155413-6afb5195e5aa|0.7.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|golang.org/x/sys|v0.0.0-20181122145206-62eef0e2fa9b|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|LGPL-3.0|1|Medium|
|MIT|8|Low|
|BSD-3-Clause|4|Low|
|BSD-2-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/juju/ansiterm|v0.0.0-20180109212912-720a0952cc2a|直接依赖|go|
|github.com/lunixbochs/vtclean|v0.0.0-20180621232353-2d01aacdc34a|间接依赖|go|
|github.com/manifoldco/promptui|v0.8.0|直接依赖|go|
|github.com/kr/pretty|v0.1.0|间接依赖|go|
|gopkg.in/check.v1|v1.0.0-20180628173108-788fd7840127|间接依赖|go|
|github.com/chzyer/logex|v1.1.10|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.4|间接依赖|go|
|github.com/mattn/go-colorable|v0.0.9|间接依赖|go|
|golang.org/x/sys|v0.0.0-20181122145206-62eef0e2fa9b|间接依赖|go|
|github.com/chzyer/readline|v0.0.0-20180603132655-2972be24d48e|直接依赖|go|
|golang.org/x/net|v0.0.0-20200114155413-6afb5195e5aa|直接依赖|go|
|github.com/anaskhan96/soup|v1.2.4|直接依赖|go|
|github.com/chzyer/test|v0.0.0-20180213035817-a1ea475d72b1|间接依赖|go|
|golang.org/x/text|v0.3.0|间接依赖|go|
|github.com/stretchr/testify|v1.6.1|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)