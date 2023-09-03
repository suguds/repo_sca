# ccfos/nightingale安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698399269240487936.svg)](https://www.murphysec.com/console/report/1697673843580911616/1698399269240487936)

仓库描述：An enterprise-level cloud-native observability solution, which can be used as drop-in replacement of Prometheus for alerting and Grafana for visualization.

仓库地址：[https://github.com/ccfos/nightingale](https://github.com/ccfos/nightingale)

| star：7012 | watch：154 | fork：1159 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-01 23:15:00 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-04 02:15:35 | 组件总数：88 | 漏洞总数：1 |

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
|MIT|48|Low|
|Apache-2.0|21|Low|
|BSD-3-Clause|15|Low|
|BSD-2-Clause|2|Low|
|MPL-2.0|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|直接依赖|go|
|github.com/golang/protobuf|v1.5.2|直接依赖|go|
|golang.org/x/sys|v0.8.0|间接依赖|go|
|github.com/go-ldap/ldap/v3|v3.4.4|直接依赖|go|
|github.com/jinzhu/inflection|v1.0.0|间接依赖|go|
|github.com/jackc/chunkreader/v2|v2.0.1|间接依赖|go|
|github.com/prometheus/client_model|v0.3.0|间接依赖|go|
|github.com/fatih/structs|v1.1.0|间接依赖|go|
|github.com/BurntSushi/toml|v0.3.1|直接依赖|go|
|github.com/Azure/go-ntlmssp|v0.0.0-20220621081337-cb9428e4ac1e|间接依赖|go|
|github.com/pquerna/cachecontrol|v0.1.0|间接依赖|go|
|google.golang.org/protobuf|v1.30.0|间接依赖|go|
|github.com/prometheus/client_golang|v1.14.0|直接依赖|go|
|github.com/pelletier/go-toml/v2|v2.0.8|直接依赖|go|
|github.com/jackc/pgio|v1.0.0|间接依赖|go|
|github.com/google/uuid|v1.3.0|直接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/fatih/camelcase|v1.0.0|间接依赖|go|
|github.com/bytedance/sonic|v1.9.1|间接依赖|go|
|github.com/dgryski/go-rendezvous|v0.0.0-20200823014737-9f7001d12a5f|间接依赖|go|
|gorm.io/driver/mysql|v1.4.4|直接依赖|go|
|golang.org/x/text|v0.9.0|间接依赖|go|
|golang.org/x/oauth2|v0.4.0|直接依赖|go|
|golang.org/x/arch|v0.3.0|间接依赖|go|
|gorm.io/gorm|v1.24.2|直接依赖|go|
|github.com/golang-jwt/jwt|v3.2.2+incompatible|直接依赖|go|
|go.uber.org/automaxprocs|v1.4.0|间接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|github.com/leodido/go-urn|v1.2.4|间接依赖|go|
|github.com/redis/go-redis/v9|v9.0.2|直接依赖|go|
|github.com/mailru/easyjson|v0.7.7|直接依赖|go|
|github.com/twitchyliquid64/golang-asm|v0.15.1|间接依赖|go|
|github.com/chenzhuoyu/base64x|v0.0.0-20221115062448-fe3a3abad311|间接依赖|go|
|github.com/klauspost/cpuid/v2|v2.2.4|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|直接依赖|go|
|github.com/jackc/pgtype|v1.12.0|间接依赖|go|
|golang.org/x/image|v0.5.0|间接依赖|go|
|github.com/gin-gonic/gin|v1.9.1|直接依赖|go|
|google.golang.org/genproto|v0.0.0-20230110181048-76db0878b65f|间接依赖|go|
|github.com/jackc/pgx/v4|v4.17.2|间接依赖|go|
|github.com/rakyll/statik|v0.1.7|直接依赖|go|
|github.com/prometheus/common|v0.39.0|直接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/golang/snappy|v0.0.4|直接依赖|go|
|github.com/tidwall/match|v1.1.1|间接依赖|go|
|golang.org/x/crypto|v0.9.0|间接依赖|go|
|github.com/spaolacci/murmur3|v1.1.0|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/go-playground/validator/v10|v10.14.0|间接依赖|go|
|github.com/tidwall/pretty|v1.2.0|间接依赖|go|
|github.com/ugorji/go/codec|v1.2.11|间接依赖|go|
|github.com/go-sql-driver/mysql|v1.6.0|间接依赖|go|
|github.com/mojocn/base64Captcha|v1.3.5|直接依赖|go|
|golang.org/x/net|v0.10.0|间接依赖|go|
|gopkg.in/gomail.v2|v2.0.0-20160411212932-81ebce5c23df|直接依赖|go|
|gopkg.in/square/go-jose.v2|v2.6.0|间接依赖|go|
|github.com/jackc/pgconn|v1.13.0|间接依赖|go|
|github.com/jackc/pgproto3/v2|v2.3.1|间接依赖|go|
|github.com/goccy/go-json|v0.10.2|间接依赖|go|
|github.com/dgrijalva/jwt-go|v3.2.0+incompatible|直接依赖|go|
|github.com/mattn/go-isatty|v0.0.19|直接依赖|go|
|github.com/gin-contrib/sse|v0.1.0|间接依赖|go|
|github.com/go-playground/universal-translator|v0.18.1|间接依赖|go|
|github.com/jinzhu/now|v1.1.5|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|github.com/coreos/go-oidc|v2.2.1+incompatible|直接依赖|go|
|gorm.io/driver/postgres|v1.4.5|直接依赖|go|
|google.golang.org/grpc|v1.53.0|间接依赖|go|
|github.com/gabriel-vasile/mimetype|v1.4.2|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/jackc/pgservicefile|v0.0.0-20200714003250-2b9c44734f2b|间接依赖|go|
|github.com/hashicorp/go-version|v1.6.0|直接依赖|go|
|github.com/gin-contrib/pprof|v1.4.0|直接依赖|go|
|github.com/koding/multiconfig|v0.0.0-20171124222453-69c27309b2d7|直接依赖|go|
|github.com/jackc/pgpassfile|v1.0.0|间接依赖|go|
|github.com/tidwall/gjson|v1.14.0|直接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|github.com/go-asn1-ber/asn1-ber|v1.5.4|间接依赖|go|
|github.com/toolkits/pkg|v1.3.3|直接依赖|go|
|github.com/golang/freetype|v0.0.0-20170609003504-e2365dfdc4a0|间接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway|v1.16.0|间接依赖|go|
|github.com/prometheus/procfs|v0.8.0|间接依赖|go|
|github.com/prometheus/prometheus|v2.5.0+incompatible|直接依赖|go|
|gopkg.in/alexcesaro/quotedprintable.v3|v3.0.0-20150716171945-2caba252f4dc|间接依赖|go|
|github.com/go-playground/locales|v0.14.1|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)