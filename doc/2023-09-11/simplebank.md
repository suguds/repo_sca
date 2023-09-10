# techschool/simplebank安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700935855010267136.svg)](https://www.murphysec.com/console/report/1700572614593658880/1700935855010267136)

仓库描述：Backend master class: build a simple bank service in Go

仓库地址：[https://github.com/techschool/simplebank](https://github.com/techschool/simplebank)

| star：3167 | watch：63 | fork：732 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-05 17:55:57 | 许可证：MIT |
| 最近检测时间：2023-09-11 02:15:15 | 组件总数：68 | 漏洞总数：4 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|jwt-go 安全漏洞|授权检查缺失|[MPS-2020-13786](https://www.oscs1024.com/hd/MPS-2020-13786)|CVE-2020-26160|高危|
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58307](https://www.oscs1024.com/hd/MPS-2022-58307)|CVE-2022-41723|高危|
|Gin-Gonic Gin 输入验证错误漏洞|输入验证不恰当|[MPS-2023-5119](https://www.oscs1024.com/hd/MPS-2023-5119)|CVE-2023-26125|高危|
|Gin 安全漏洞|下载代码缺少完整性检查|[MPS-2023-9711](https://www.oscs1024.com/hd/MPS-2023-9711)|CVE-2023-29401|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|golang.org/x/net|v0.6.0|0.7.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|github.com/gin-gonic/gin|v1.7.7|1.9.1|直接依赖|建议修复|C:0|H:1|M:1|L:0|
|github.com/dgrijalva/jwt-go|v3.2.0+incompatible|4.0.0-preview1|直接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|13|Low|
|MIT|38|Low|
|MPL-2.0|3|Low|
|BSD-3-Clause|14|Low|
|BSD-2-Clause|3|Low|
|ISC|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/go-playground/locales|v0.14.0|间接依赖|go|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|google.golang.org/protobuf|v1.28.1|直接依赖|go|
|github.com/rs/zerolog|v1.28.0|直接依赖|go|
|golang.org/x/text|v0.7.0|间接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway/v2|v2.10.0|直接依赖|go|
|github.com/robfig/cron/v3|v3.0.1|间接依赖|go|
|github.com/go-redis/redis/v8|v8.11.5|直接依赖|go|
|github.com/golang-migrate/migrate/v4|v4.15.1|直接依赖|go|
|github.com/subosito/gotenv|v1.2.0|间接依赖|go|
|go.uber.org/atomic|v1.6.0|间接依赖|go|
|github.com/go-playground/validator/v10|v10.10.1|直接依赖|go|
|github.com/leodido/go-urn|v1.2.1|间接依赖|go|
|github.com/lib/pq|v1.10.5|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|google.golang.org/grpc/cmd/protoc-gen-go-grpc|v1.2.0|直接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/golang/glog|v1.0.0|间接依赖|go|
|github.com/aead/chacha20|v0.0.0-20180709150244-8b13a72661da|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|golang.org/x/sync|v0.1.0|间接依赖|go|
|github.com/gin-contrib/sse|v0.1.0|间接依赖|go|
|golang.org/x/crypto|v0.6.0|直接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|golang.org/x/time|v0.2.0|间接依赖|go|
|github.com/mitchellh/mapstructure|v1.4.3|间接依赖|go|
|github.com/aead/chacha20poly1305|v0.0.0-20201124145622-1a5aba2a8b29|直接依赖|go|
|github.com/spf13/cast|v1.5.0|间接依赖|go|
|github.com/rakyll/statik|v0.1.7|直接依赖|go|
|github.com/jordan-wright/email|v4.0.1-0.20210109023952-943e75fe5223+incompatible|直接依赖|go|
|github.com/google/uuid|v1.3.0|直接依赖|go|
|github.com/go-playground/universal-translator|v0.18.0|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/magiconair/properties|v1.8.6|间接依赖|go|
|gopkg.in/ini.v1|v1.66.4|间接依赖|go|
|github.com/jackc/pgx/v5|v5.3.1|直接依赖|go|
|github.com/hibiken/asynq|v0.23.0|直接依赖|go|
|github.com/hashicorp/go-multierror|v1.1.0|间接依赖|go|
|github.com/ugorji/go/codec|v1.2.7|间接依赖|go|
|github.com/jackc/pgpassfile|v1.0.0|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|github.com/o1egl/paseto|v1.0.0|直接依赖|go|
|github.com/gin-gonic/gin|v1.7.7|直接依赖|go|
|github.com/spf13/viper|v1.10.1|直接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20220317150908-0efb43f6373e|直接依赖|go|
|github.com/aead/poly1305|v0.0.0-20180717145839-3fee0db0b635|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.5.1|间接依赖|go|
|sigs.k8s.io/yaml|v1.3.0|间接依赖|go|
|github.com/dgryski/go-rendezvous|v0.0.0-20200823014737-9f7001d12a5f|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.16|间接依赖|go|
|github.com/stretchr/testify|v1.8.1|直接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|golang.org/x/sys|v0.5.0|间接依赖|go|
|github.com/golang/protobuf|v1.5.2|间接依赖|go|
|github.com/hashicorp/errwrap|v1.0.0|间接依赖|go|
|github.com/jackc/puddle/v2|v2.2.0|间接依赖|go|
|github.com/dgrijalva/jwt-go|v3.2.0+incompatible|直接依赖|go|
|github.com/cespare/xxhash/v2|v2.1.2|间接依赖|go|
|github.com/jackc/pgservicefile|v0.0.0-20221227161230-091c0ba34f0a|间接依赖|go|
|github.com/golang/mock|v1.6.0|直接依赖|go|
|google.golang.org/grpc|v1.45.0|直接依赖|go|
|github.com/spf13/jwalterweatherman|v1.1.0|间接依赖|go|
|github.com/pelletier/go-toml|v1.9.4|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/spf13/afero|v1.8.2|间接依赖|go|
|golang.org/x/net|v0.6.0|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)