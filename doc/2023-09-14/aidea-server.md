# mylxsw/aidea-server安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1702021414994624512.svg)](https://www.murphysec.com/console/report/1701297214471143424/1702021414994624512)

仓库描述：AIdea 是一款支持 GPT  以及国产大语言模型通义千问、文心一言等，支持 Stable Diffusion 文生图、图生图、 SDXL1.0、超分辨率、图片上色的全能型 APP。

仓库地址：[https://github.com/mylxsw/aidea-server](https://github.com/mylxsw/aidea-server)

| star：614 | watch：28 | fork：156 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-13 17:20:14 | 许可证：- |
| 最近检测时间：2023-09-14 02:08:35 | 组件总数：89 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|jwt-go 安全漏洞|授权检查缺失|[MPS-2020-13786](https://www.oscs1024.com/hd/MPS-2020-13786)|CVE-2020-26160|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/dgrijalva/jwt-go|v3.2.0+incompatible|4.0.0-preview1|直接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|18|Low|
|Apache-2.0|21|Low|
|MIT|34|Low|
|ISC|1|Low|
|BSD-2-Clause|6|Low|
|MPL-2.0|3|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|github.com/alibabacloud-go/openapi-util|v0.1.0|间接依赖|go|
|github.com/clbanning/mxj/v2|v2.5.5|间接依赖|go|
|gopkg.in/ini.v1|v1.56.0|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/alibabacloud-go/tea-utils|v1.3.1|间接依赖|go|
|github.com/qiniu/go-sdk/v7|v7.15.0|直接依赖|go|
|github.com/mylxsw/glacier|v1.1.4-0.20230425093359-8b073ae5b7af|直接依赖|go|
|github.com/alibabacloud-go/darabonba-openapi/v2|v2.0.4|直接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|google.golang.org/protobuf|v1.30.0|间接依赖|go|
|github.com/prometheus/client_golang|v1.11.1|直接依赖|go|
|github.com/robfig/cron/v3|v3.0.1|直接依赖|go|
|github.com/gorilla/websocket|v1.4.2|直接依赖|go|
|github.com/gorilla/securecookie|v1.1.1|间接依赖|go|
|github.com/gorilla/mux|v1.8.0|直接依赖|go|
|gopkg.in/guregu/null.v3|v3.5.0|直接依赖|go|
|github.com/buger/jsonparser|v1.1.1|间接依赖|go|
|github.com/alibabacloud-go/dysmsapi-20170525/v3|v3.0.5|直接依赖|go|
|github.com/alibabacloud-go/tea-utils/v2|v2.0.1|直接依赖|go|
|github.com/tencentcloud/tencentcloud-sdk-go/tencentcloud/sms|v1.0.671|直接依赖|go|
|github.com/tjfoc/gmsm|v1.3.2|间接依赖|go|
|gopkg.in/gomail.v2|v2.0.0-20160411212932-81ebce5c23df|直接依赖|go|
|golang.org/x/sync|v0.1.0|间接依赖|go|
|github.com/mylxsw/go-ioc|v1.1.0|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|golang.org/x/net|v0.10.0|直接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/prometheus/procfs|v0.9.0|间接依赖|go|
|github.com/dgrijalva/jwt-go|v3.2.0+incompatible|直接依赖|go|
|github.com/dgryski/go-rendezvous|v0.0.0-20200823014737-9f7001d12a5f|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|github.com/gorilla/sessions|v1.2.1|间接依赖|go|
|github.com/gorilla/context|v1.1.1|间接依赖|go|
|golang.org/x/text|v0.9.0|间接依赖|go|
|github.com/speps/go-hashids/v2|v2.0.1|直接依赖|go|
|github.com/rogpeppe/go-internal|v1.10.0|间接依赖|go|
|github.com/prometheus/client_model|v0.3.0|间接依赖|go|
|github.com/go-sql-driver/mysql|v1.7.1|直接依赖|go|
|github.com/hashicorp/go-version|v1.6.0|直接依赖|go|
|github.com/tencentcloud/tencentcloud-sdk-go/tencentcloud/common|v1.0.727|直接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/mylxsw/asteria|v1.0.1|直接依赖|go|
|github.com/urfave/cli/v2|v2.23.7|间接依赖|go|
|github.com/sashabaranov/go-openai|v1.12.0|直接依赖|go|
|golang.org/x/time|v0.0.0-20190308202827-9d24e82272b4|间接依赖|go|
|github.com/go-pay/gopay|v1.5.94|直接依赖|go|
|github.com/spf13/cast|v1.3.1|间接依赖|go|
|github.com/wagslane/go-password-validator|v0.3.0|直接依赖|go|
|github.com/alibabacloud-go/alibabacloud-gateway-spi|v0.0.4|间接依赖|go|
|github.com/tencentcloud/tencentcloud-sdk-go/tencentcloud/aiart|v1.0.727|直接依赖|go|
|github.com/aliyun/credentials-go|v1.1.2|间接依赖|go|
|gopkg.in/alexcesaro/quotedprintable.v3|v3.0.0-20150716171945-2caba252f4dc|间接依赖|go|
|github.com/google/uuid|v1.3.0|间接依赖|go|
|github.com/pkoukk/tiktoken-go|v0.1.2|直接依赖|go|
|github.com/tideland/gorest|v2.15.5+incompatible|直接依赖|go|
|github.com/Timothylock/go-signin-with-apple|v0.2.0|直接依赖|go|
|golang.org/x/crypto|v0.9.0|直接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/prometheus/common|v0.26.0|间接依赖|go|
|github.com/dlclark/regexp2|v1.8.1|间接依赖|go|
|github.com/cpuguy83/go-md2man/v2|v2.0.2|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/alibabacloud-go/tea-xml|v1.1.2|间接依赖|go|
|github.com/golang-jwt/jwt/v4|v4.5.0|间接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|github.com/iancoleman/strcase|v0.2.0|直接依赖|go|
|github.com/go-redis/redis_rate/v10|v10.0.1|直接依赖|go|
|github.com/awa/go-iap|v1.9.0|直接依赖|go|
|gopkg.in/resty.v1|v1.12.0|直接依赖|go|
|github.com/alibabacloud-go/endpoint-util|v1.1.0|间接依赖|go|
|github.com/russross/blackfriday/v2|v2.1.0|间接依赖|go|
|github.com/gorilla/schema|v1.2.0|间接依赖|go|
|golang.org/x/sys|v0.8.0|间接依赖|go|
|github.com/hashicorp/go-uuid|v1.0.3|直接依赖|go|
|github.com/hibiken/asynq|v0.24.1|直接依赖|go|
|github.com/BurntSushi/toml|v1.2.1|间接依赖|go|
|github.com/tideland/golib|v4.24.2+incompatible|间接依赖|go|
|github.com/redis/go-redis/v9|v9.0.3|直接依赖|go|
|github.com/alibabacloud-go/tea|v1.1.19|直接依赖|go|
|github.com/alibabacloud-go/green-20220302|v1.0.6|直接依赖|go|
|github.com/mylxsw/eloquent|v0.0.2-0.20230528030952-90014b5782ec|直接依赖|go|
|github.com/stretchr/testify|v1.8.2|直接依赖|go|
|github.com/tencentcloud/tencentcloud-sdk-go/tencentcloud/asr|v1.0.665|直接依赖|go|
|github.com/fvbommel/sortorder|v1.1.0|直接依赖|go|
|github.com/alibabacloud-go/debug|v0.0.0-20190504072949-9472017b5c68|间接依赖|go|
|github.com/xrash/smetrics|v0.0.0-20201216005158-039620a65673|间接依赖|go|
|github.com/mylxsw/go-utils|v1.0.3|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)