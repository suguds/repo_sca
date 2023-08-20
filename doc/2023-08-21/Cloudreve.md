# cloudreve/Cloudreve安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1693324533158531072.svg)](https://www.murphysec.com/console/report/1693324533083033600/1693324533158531072)

仓库描述：🌩支持多家云存储的云盘系统 (Self-hosted file management and sharing system, supports multiple storage providers)

仓库地址：[https://github.com/cloudreve/Cloudreve](https://github.com/cloudreve/Cloudreve)

| star：18719 | watch：230 | fork：3110 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-15 01:29:51 | 许可证：GPL-3.0 |
| 最近检测时间：2023-08-21 02:10:09 | 组件总数：165 | 漏洞总数：5 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|go.uuid 不安全的随机性漏洞|使用具有密码学弱点缺陷的PRNG|[MPS-2021-7854](https://www.oscs1024.com/hd/MPS-2021-7854)|CVE-2021-3538|严重|
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58307](https://www.oscs1024.com/hd/MPS-2022-58307)|CVE-2022-41723|高危|
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58311](https://www.oscs1024.com/hd/MPS-2022-58311)|CVE-2022-41727|中危|
|Gin-Gonic Gin 输入验证错误漏洞|输入验证不恰当|[MPS-2023-5119](https://www.oscs1024.com/hd/MPS-2023-5119)|CVE-2023-26125|高危|
|Gin 安全漏洞|下载代码缺少完整性检查|[MPS-2023-9711](https://www.oscs1024.com/hd/MPS-2023-9711)|CVE-2023-29401|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/satori/go.uuid|v1.2.0||间接依赖|建议修复|C:1|H:0|M:0|L:0|
|golang.org/x/net|v0.0.0-20220630215102-69896b714898|0.7.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|github.com/gin-gonic/gin|v1.8.1|1.9.1|直接依赖|建议修复|C:0|H:1|M:1|L:0|
|golang.org/x/image|v0.0.0-20211028202545-6944b10bf410|0.5.0|直接依赖|建议修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|48|Low|
|MIT|64|Low|
|BSD-3-Clause|43|Low|
|BSD-2-Clause|5|Low|
|MPL-2.0|2|Low|
|CC0-1.0|1|Low|
|GPL-2.0|1|Medium|
|ISC|1|Low|
|LGPL-3.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/fatih/color|v1.9.0|直接依赖|go|
|golang.org/x/sys|v0.4.0|间接依赖|go|
|github.com/googleapis/gax-go/v2|v2.0.5|间接依赖|go|
|golang.org/x/tools|v0.1.8-0.20211029000441-d6a9af8af023|间接依赖|go|
|github.com/prometheus/client_model|v0.2.0|间接依赖|go|
|github.com/tencentyun/cos-go-sdk-v5|v0.0.0-20200120023323-87ff3bc489ac|直接依赖|go|
|github.com/go-ini/ini|v1.50.0|直接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.1|间接依赖|go|
|github.com/mozillazg/go-httpheader|v0.2.1|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/dsnet/compress|v0.0.1|间接依赖|go|
|github.com/samber/lo|v1.38.1|直接依赖|go|
|github.com/golang/freetype|v0.0.0-20170609003504-e2365dfdc4a0|间接依赖|go|
|github.com/mholt/archiver/v4|v4.0.0-alpha.6|直接依赖|go|
|github.com/gorilla/securecookie|v1.1.1|直接依赖|go|
|github.com/sirupsen/logrus|v1.8.1|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.0.0|间接依赖|go|
|github.com/gin-gonic/gin|v1.8.1|直接依赖|go|
|gopkg.in/cheggaaa/pb.v1|v1.0.28|间接依赖|go|
|github.com/mitchellh/mapstructure|v1.1.2|间接依赖|go|
|golang.org/x/xerrors|v0.0.0-20200804184101-5ec99f83aff1|间接依赖|go|
|github.com/gorilla/sessions|v1.2.1|直接依赖|go|
|github.com/pierrec/lz4/v4|v4.1.14|间接依赖|go|
|github.com/cloudflare/cfssl|v1.6.1|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|间接依赖|go|
|google.golang.org/protobuf|v1.28.0|间接依赖|go|
|github.com/lib/pq|v1.10.3|间接依赖|go|
|go.etcd.io/etcd/v3|v3.5.0-alpha.0|间接依赖|go|
|github.com/census-instrumentation/opencensus-proto|v0.3.0|间接依赖|go|
|github.com/go-sql-driver/mysql|v1.6.0|间接依赖|go|
|github.com/form3tech-oss/jwt-go|v3.2.3+incompatible|间接依赖|go|
|github.com/gomodule/redigo|v2.0.0+incompatible|直接依赖|go|
|golang.org/x/sync|v0.0.0-20210220032951-036812b2e83c|间接依赖|go|
|github.com/gin-contrib/sessions|v0.0.5|直接依赖|go|
|github.com/cpuguy83/go-md2man/v2|v2.0.0|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.17|间接依赖|go|
|github.com/therootcompany/xz|v1.0.1|间接依赖|go|
|github.com/coreos/go-semver|v0.3.0|间接依赖|go|
|github.com/jonboulle/clockwork|v0.2.2|间接依赖|go|
|golang.org/x/image|v0.0.0-20211028202545-6944b10bf410|直接依赖|go|
|github.com/golang/snappy|v0.0.4|间接依赖|go|
|go.etcd.io/etcd/tests/v3|v3.5.0-alpha.0|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|github.com/gin-contrib/gzip|v0.0.2-0.20200226035851-25bef2ef21e8|直接依赖|go|
|github.com/tencentcloud/tencentcloud-sdk-go/tencentcloud/captcha|v1.0.393|直接依赖|go|
|github.com/xiang90/probing|v0.0.0-20190116061207-43a291ad63a2|间接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|github.com/google/btree|v1.0.1|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20210510173355-fb37daa5cd7a|间接依赖|go|
|github.com/remyoudompheng/bigfft|v0.0.0-20230126093431-47fa9a501578|间接依赖|go|
|github.com/coreos/go-systemd/v22|v22.3.2|间接依赖|go|
|github.com/stretchr/objx|v0.2.0|间接依赖|go|
|github.com/x448/float16|v0.8.4|间接依赖|go|
|github.com/google/certificate-transparency-go|v1.1.2-0.20210511102531-373a877eec92|间接依赖|go|
|go.etcd.io/etcd/etcdctl/v3|v3.5.0-alpha.0|间接依赖|go|
|github.com/prometheus/procfs|v0.6.0|间接依赖|go|
|github.com/upyun/go-sdk|v2.1.0+incompatible|直接依赖|go|
|github.com/go-playground/validator/v10|v10.11.0|直接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway|v1.16.0|间接依赖|go|
|sigs.k8s.io/yaml|v1.2.0|间接依赖|go|
|github.com/duo-labs/webauthn|v0.0.0-20220330035159-03696f3d4499|直接依赖|go|
|github.com/google/go-querystring|v1.0.0|直接依赖|go|
|github.com/golang/protobuf|v1.5.2|间接依赖|go|
|github.com/robfig/cron/v3|v3.0.1|直接依赖|go|
|github.com/jinzhu/gorm|v1.9.11|直接依赖|go|
|github.com/ugorji/go/codec|v1.2.7|间接依赖|go|
|github.com/golang-jwt/jwt/v4|v4.1.0|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|github.com/nwaples/rardecode/v2|v2.0.0-beta.2|间接依赖|go|
|github.com/dustin/go-humanize|v1.0.1|间接依赖|go|
|github.com/russross/blackfriday/v2|v2.1.0|间接依赖|go|
|github.com/envoyproxy/protoc-gen-validate|v0.6.1|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.1.1|间接依赖|go|
|golang.org/x/mod|v0.6.0-dev.0.20211013180041-c96bc1413d57|间接依赖|go|
|github.com/mojocn/base64Captcha|v0.0.0-20190801020520-752b1cd608b2|直接依赖|go|
|github.com/qiniu/go-sdk/v7|v7.11.1|直接依赖|go|
|github.com/jinzhu/inflection|v1.0.0|间接依赖|go|
|github.com/prometheus/client_golang|v1.10.0|间接依赖|go|
|golang.org/x/crypto|v0.0.0-20220622213112-05595931fe9d|间接依赖|go|
|go.etcd.io/etcd/pkg/v3|v3.5.0-alpha.0|间接依赖|go|
|github.com/soheilhy/cmux|v0.1.5|间接依赖|go|
|github.com/klauspost/compress|v1.15.1|间接依赖|go|
|github.com/goccy/go-json|v0.9.8|间接依赖|go|
|github.com/ulikunitz/xz|v0.5.10|间接依赖|go|
|gopkg.in/mail.v2|v2.3.1|间接依赖|go|
|github.com/stretchr/testify|v1.7.2|直接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/boombuler/barcode|v1.0.1-0.20190219062509-6c824513bacc|间接依赖|go|
|github.com/pelletier/go-toml/v2|v2.0.2|间接依赖|go|
|cloud.google.com/go|v0.81.0|间接依赖|go|
|github.com/mattn/go-runewidth|v0.0.12|间接依赖|go|
|go.etcd.io/etcd/api/v3|v3.5.0-alpha.0|间接依赖|go|
|go.etcd.io/etcd/server/v3|v3.5.0-alpha.0|间接依赖|go|
|google.golang.org/api|v0.45.0|直接依赖|go|
|github.com/gin-contrib/cors|v1.3.0|直接依赖|go|
|github.com/klauspost/pgzip|v1.2.5|间接依赖|go|
|github.com/urfave/cli|v1.22.5|间接依赖|go|
|github.com/golang/mock|v1.5.0|间接依赖|go|
|github.com/rafaeljusto/redigomock|v0.0.0-20191117212112-00b2509252a1|直接依赖|go|
|github.com/mattn/go-colorable|v0.1.4|间接依赖|go|
|github.com/glebarez/go-sqlite|v1.20.3|直接依赖|go|
|github.com/go-playground/locales|v0.14.0|间接依赖|go|
|github.com/hashicorp/go-version|v1.3.0|直接依赖|go|
|github.com/denisenkom/go-mssqldb|v0.0.0-20190515213511-eb9f6a1743f3|间接依赖|go|
|github.com/gin-contrib/sse|v0.1.0|间接依赖|go|
|github.com/gin-contrib/static|v0.0.0-20191128031702-f81c604d8ac2|直接依赖|go|
|github.com/HFO4/aliyun-oss-go-sdk|v2.2.3+incompatible|直接依赖|go|
|github.com/baiyubin/aliyun-sts-go-sdk|v0.0.0-20180326062324-cfa1a18b161f|间接依赖|go|
|github.com/gofrs/uuid|v4.0.0+incompatible|直接依赖|go|
|github.com/gorilla/context|v1.1.1|间接依赖|go|
|golang.org/x/time|v0.0.0-20210220033141-f8bda1e9f3ba|直接依赖|go|
|github.com/go-mail/mail|v2.3.1+incompatible|直接依赖|go|
|github.com/spf13/cobra|v1.1.3|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|google.golang.org/grpc|v1.37.0|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/andybalholm/brotli|v1.0.4|间接依赖|go|
|github.com/olekukonko/tablewriter|v0.0.5|间接依赖|go|
|go.opencensus.io|v0.23.0|间接依赖|go|
|github.com/fullstorydev/grpcurl|v1.8.1|间接依赖|go|
|gopkg.in/alexcesaro/quotedprintable.v3|v3.0.0-20150716171945-2caba252f4dc|间接依赖|go|
|go.etcd.io/etcd/client/v2|v2.305.0-alpha.0|间接依赖|go|
|github.com/envoyproxy/go-control-plane|v0.9.9-0.20210217033140-668b12f5399d|间接依赖|go|
|go.etcd.io/etcd/raft/v3|v3.5.0-alpha.0|间接依赖|go|
|github.com/cncf/udpa/go|v0.0.0-20210322005330-6414d713912e|间接依赖|go|
|go.uber.org/zap|v1.16.0|间接依赖|go|
|github.com/jmespath/go-jmespath|v0.3.0|间接依赖|go|
|github.com/bgentry/speakeasy|v0.1.0|间接依赖|go|
|modernc.org/sqlite|v1.20.3|间接依赖|go|
|go.uber.org/multierr|v1.7.0|间接依赖|go|
|github.com/grpc-ecosystem/go-grpc-prometheus|v1.2.0|间接依赖|go|
|go.etcd.io/bbolt|v1.3.5|间接依赖|go|
|github.com/rivo/uniseg|v0.2.0|间接依赖|go|
|github.com/prometheus/common|v0.24.0|间接依赖|go|
|github.com/juju/ratelimit|v1.0.1|直接依赖|go|
|github.com/pquerna/otp|v1.2.0|直接依赖|go|
|go.uber.org/atomic|v1.7.0|间接依赖|go|
|golang.org/x/exp|v0.0.0-20220303212507-bbda1eaf7a17|间接依赖|go|
|github.com/grpc-ecosystem/go-grpc-middleware|v1.3.0|间接依赖|go|
|github.com/DATA-DOG/go-sqlmock|v1.3.3|直接依赖|go|
|go.etcd.io/etcd/client/v3|v3.5.0-alpha.0|间接依赖|go|
|modernc.org/memory|v1.5.0|间接依赖|go|
|github.com/satori/go.uuid|v1.2.0|间接依赖|go|
|github.com/go-playground/universal-translator|v0.18.0|间接依赖|go|
|golang.org/x/text|v0.3.7|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/tencentcloud/tencentcloud-sdk-go/tencentcloud/common|v1.0.393|直接依赖|go|
|modernc.org/mathutil|v1.5.0|间接依赖|go|
|golang.org/x/net|v0.0.0-20220630215102-69896b714898|间接依赖|go|
|github.com/tmc/grpc-websocket-proxy|v0.0.0-20201229170055-e5319fda7802|间接依赖|go|
|github.com/leodido/go-urn|v1.2.1|间接依赖|go|
|github.com/tencentcloud/tencentcloud-sdk-go/tencentcloud/scf|v1.0.393|直接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|golang.org/x/oauth2|v0.0.0-20210427180440-81ed05c6b58c|间接依赖|go|
|modernc.org/libc|v1.22.2|间接依赖|go|
|github.com/jhump/protoreflect|v1.8.2|间接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/aws/aws-sdk-go|v1.31.5|直接依赖|go|
|github.com/fxamacker/cbor/v2|v2.4.0|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/speps/go-hashids|v2.0.0+incompatible|直接依赖|go|
|github.com/gorilla/websocket|v1.4.2|直接依赖|go|
|github.com/google/uuid|v1.3.0|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)