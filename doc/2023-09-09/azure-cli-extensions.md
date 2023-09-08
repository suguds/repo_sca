# Azure/azure-cli-extensions安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700212731961540608.svg)](https://www.murphysec.com/console/report/1700212731835711488/1700212731961540608)

仓库描述：Public Repository for Extensions of Azure CLI.

仓库地址：[https://github.com/Azure/azure-cli-extensions](https://github.com/Azure/azure-cli-extensions)

| star：326 | watch：161 | fork：957 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-09 01:57:14 | 许可证：MIT |
| 最近检测时间：2023-09-09 02:23:15 | 组件总数：29 | 漏洞总数：8 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|jwt-go 安全漏洞|授权检查缺失|[MPS-2020-13786](https://www.oscs1024.com/hd/MPS-2020-13786)|CVE-2020-26160|高危|
|Kubernetes API Server 资源管理错误漏洞|循环内过多的平台资源消耗|[MPS-2020-44793](https://www.oscs1024.com/hd/MPS-2020-44793)|CVE-2019-11254|中危|
|gopkg.in/yaml.v2 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13505](https://www.oscs1024.com/hd/MPS-2022-13505)||中危|
|Go-Yaml 安全漏洞||[MPS-2022-52765](https://www.oscs1024.com/hd/MPS-2022-52765)|CVE-2021-4235|中危|
|Python 安全漏洞|ReDoS|[MPS-2022-57239](https://www.oscs1024.com/hd/MPS-2022-57239)|CVE-2022-40898|高危|
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58307](https://www.oscs1024.com/hd/MPS-2022-58307)|CVE-2022-41723|高危|
|Go-Yaml 资源管理错误漏洞|拒绝服务|[MPS-2022-69639](https://www.oscs1024.com/hd/MPS-2022-69639)|CVE-2022-3064|高危|
|Google Go 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2022-9049](https://www.oscs1024.com/hd/MPS-2022-9049)|CVE-2022-29526|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|gopkg.in/yaml.v2|v2.2.2|2.2.8|间接依赖|建议修复|C:0|H:1|M:3|L:0|
|golang.org/x/net|v0.0.0-20191209160850-c0dbc17a3553|0.7.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|github.com/dgrijalva/jwt-go|v3.2.0+incompatible|4.0.0-preview1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|wheel|0.31.1|0.38.0|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|golang.org/x/sys|v0.0.0-20191220220014-0732a990476f|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|9|Low|
|MIT|10|Low|
|BSD-3-Clause|8|Low|
|BSD-2-Clause|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/Azure/go-autorest/autorest/date|v0.2.0|间接依赖|go|
|github.com/Azure/go-autorest/autorest/adal|v0.8.3|间接依赖|go|
|github.com/minio/minio-go|v6.0.14+incompatible|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.0.0|间接依赖|go|
|github.com/cpuguy83/go-md2man|v1.0.10|间接依赖|go|
|golang.org/x/crypto|v0.0.0-20191206172530-e9b2fee46413|间接依赖|go|
|github.com/Azure/azure-pipeline-go|v0.2.2|间接依赖|go|
|github.com/JeffreyRichter/enum|v0.0.0-20180725232043-2567042f9cda|间接依赖|go|
|golang.org/x/net|v0.0.0-20191209160850-c0dbc17a3553|间接依赖|go|
|github.com/spf13/pflag|v1.0.2|间接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|wheel|0.31.1|间接依赖|pip|
|github.com/Azure/azure-storage-file-go|v0.8.0|间接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|github.com/google/uuid|v1.1.1|间接依赖|go|
|golang.org/x/text|v0.3.2|间接依赖|go|
|github.com/mattn/go-ieproxy|v0.0.1|间接依赖|go|
|gopkg.in/yaml.v2|v2.2.2|间接依赖|go|
|github.com/russross/blackfriday|v1.5.2|间接依赖|go|
|github.com/go-ini/ini|v1.41.0|间接依赖|go|
|github.com/danieljoos/wincred|v1.0.1|间接依赖|go|
|golang.org/x/sync|v0.0.0-20181221193216-37e7f081c4d4|间接依赖|go|
|github.com/spf13/cobra|v0.0.3|间接依赖|go|
|golang.org/x/sys|v0.0.0-20191220220014-0732a990476f|间接依赖|go|
|github.com/Azure/go-autorest/tracing|v0.5.0|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20191027212112-611e8accdfc9|间接依赖|go|
|Jinja2|3.0.3|间接依赖|pip|
|github.com/dgrijalva/jwt-go|v3.2.0+incompatible|间接依赖|go|
|github.com/Azure/azure-storage-blob-go|v0.10.0|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)