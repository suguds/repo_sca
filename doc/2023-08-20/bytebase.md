# bytebase/bytebase安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692962135230795776.svg)](https://www.murphysec.com/console/report/1692962135163686912/1692962135230795776)

仓库描述：Database DevOps and CI/CD for Developer, DBA and Platform Engineering team. https://www.bytebase.com

仓库地址：[https://github.com/bytebase/bytebase](https://github.com/bytebase/bytebase)

| star：6597 | watch：65 | fork：422 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-20 00:48:10 | 许可证：NOASSERTION |
| 最近检测时间：2023-08-20 02:21:30 | 组件总数：282 | 漏洞总数：7 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|go.uuid 不安全的随机性漏洞|使用具有密码学弱点缺陷的PRNG|[MPS-2021-7854](https://www.oscs1024.com/hd/MPS-2021-7854)|CVE-2021-3538|严重|
|PingCAP TiDB 格式化字符串错误漏洞|使用外部控制的格式字符串|[MPS-2022-56135](https://www.oscs1024.com/hd/MPS-2022-56135)|CVE-2022-3023|严重|
|OpenSSL 验证 X.509 策略约束存在拒绝服务漏洞|拒绝服务|[MPS-2023-2810](https://www.oscs1024.com/hd/MPS-2023-2810)|CVE-2023-0464|中危|
|OpenSSL 信任管理问题漏洞|证书验证不恰当|[MPS-2023-2811](https://www.oscs1024.com/hd/MPS-2023-2811)|CVE-2023-0465|中危|
|OpenSSL 存在证书验证不当|证书验证不恰当|[MPS-2023-2812](https://www.oscs1024.com/hd/MPS-2023-2812)|CVE-2023-0466|中危|
|OpenSSL ASN.1对象标识符转换拒绝服务漏洞|拒绝服务|[MPS-9dro-82lx](https://www.oscs1024.com/hd/MPS-9dro-82lx)|CVE-2023-2650|中危|
|OpenSSL 安全漏洞|过度迭代|[MPS-n3pe-ljgc](https://www.oscs1024.com/hd/MPS-n3pe-ljgc)|CVE-2023-3817|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|openssl|1.1.1t|3.1.2|间接依赖|建议修复|C:0|H:0|M:5|L:0|
|github.com/satori/go.uuid|v1.2.0||间接依赖|建议修复|C:1|H:0|M:0|L:0|
|github.com/pingcap/tidb|v1.1.0-beta.0.20220825063022-5263a0abda61|6.2.0|直接依赖|建议修复|C:1|H:0|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|46|Low|
|MIT|93|Low|
|MPL-2.0|3|Low|
|Apache-2.0|108|Low|
|ISC|2|Low|
|OpenSSL|2|Low|
|BSD-2-Clause|8|Low|
|GPL-2.0|2|Medium|
|PostgreSQL|1|Low|
|BSL-1.0|1|Low|
|NCSA|1|Low|
|CC-BY-3.0|1|Low|
|HPND|1|Low|
|Zlib|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/desertbit/timer|v0.0.0-20180107155436-c41aec40b27f|间接依赖|go|
|github.com/gosimple/slug|v1.13.1|直接依赖|go|
|github.com/gosimple/unidecode|v1.0.1|间接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230731190214-cbb8c96f2d6d|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/v4a|v1.0.26|间接依赖|go|
|github.com/microsoft/go-mssqldb|v1.1.0|直接依赖|go|
|github.com/benbjohnson/clock|v1.3.0|间接依赖|go|
|libdl.so.2||间接依赖||
|/usr/lib/libc++.1.dylib||间接依赖||
|github.com/labstack/gommon|v0.4.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/presigned-url|v1.9.28|间接依赖|go|
|github.com/antlr/antlr4/runtime/Go/antlr/v4|v4.0.0-20230305170008-8188dc5388df|间接依赖|go|
|github.com/dgryski/go-rendezvous|v0.0.0-20200823014737-9f7001d12a5f|间接依赖|go|
|github.com/prometheus/client_model|v0.4.0|间接依赖|go|
|github.com/go-faster/city|v1.0.1|间接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|间接依赖|go|
|github.com/casbin/casbin/v2|v2.71.1|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/credentials|v1.13.26|直接依赖|go|
|golang.org/x/xerrors|v0.0.0-20220907171357-04be3eba64a2|间接依赖|go|
|github.com/andybalholm/brotli|v1.0.5|间接依赖|go|
|github.com/jackc/pgconn|v1.13.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ssooidc|v1.14.12|间接依赖|go|
|github.com/segmentio/asm|v1.2.0|间接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.2|间接依赖|go|
|github.com/pingcap/kvproto|v0.0.0-20221101075641-65d0ae8fa853|间接依赖|go|
|go.opentelemetry.io/otel|v1.16.0|间接依赖|go|
|github.com/xtgo/uuid|v0.0.0-20140804021211-a0b114877d4c|间接依赖|go|
|go.mongodb.org/mongo-driver|v1.12.0|直接依赖|go|
|github.com/KyleBanks/depth|v1.2.1|间接依赖|go|
|github.com/go-openapi/swag|v0.22.4|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sts|v1.19.2|间接依赖|go|
|go.uber.org/multierr|v1.11.0|直接依赖|go|
|github.com/lestrrat-go/iter|v1.0.2|间接依赖|go|
|github.com/xuri/excelize/v2|v2.7.1|直接依赖|go|
|github.com/lestrrat-go/option|v1.0.1|间接依赖|go|
|github.com/xuri/efp|v0.0.0-20220603152613-6918739fd470|间接依赖|go|
|github.com/golang-jwt/jwt|v3.2.2+incompatible|直接依赖|go|
|golang.org/x/crypto|v0.10.0|直接依赖|go|
|github.com/jackc/chunkreader/v2|v2.0.1|间接依赖|go|
|go.uber.org/atomic|v1.11.0|间接依赖|go|
|google.golang.org/api|v0.128.0|直接依赖|go|
|github.com/jackc/pgservicefile|v0.0.0-20221227161230-091c0ba34f0a|间接依赖|go|
|github.com/golang/glog|v1.1.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2|v1.18.1|直接依赖|go|
|github.com/coreos/go-oidc|v2.2.1+incompatible|直接依赖|go|
|github.com/danieljoos/wincred|v1.2.0|间接依赖|go|
|github.com/labstack/echo-contrib|v0.15.0|直接依赖|go|
|github.com/jcmturner/rpc/v2|v2.0.3|间接依赖|go|
|github.com/nyaruka/phonenumbers|v1.1.7|直接依赖|go|
|github.com/lestrrat-go/jwx/v2|v2.0.11|直接依赖|go|
|github.com/go-mysql-org/go-mysql|v1.6.0|间接依赖|go|
|golang.org/x/exp|v0.0.0-20230626212559-97b1e661b5df|直接依赖|go|
|github.com/decred/dcrd/dcrec/secp256k1/v4|v4.2.0|间接依赖|go|
|github.com/opentracing/opentracing-go|v1.2.0|间接依赖|go|
|cloud.google.com/go/spanner|v1.47.0|直接依赖|go|
|github.com/xo/dburl|v0.13.1|直接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|golang.org/x/time|v0.3.0|间接依赖|go|
|github.com/youmark/pkcs8|v0.0.0-20181117223130-1be2e3e5546d|间接依赖|go|
|github.com/jackc/pgtype|v1.14.0|直接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|openssl|1.1.1t|间接依赖||
|github.com/jcmturner/gofork|v1.7.6|间接依赖|go|
|github.com/bytebase/snowsql-parser|v0.0.0-20230706111031-cafd8faa2dc9|直接依赖|go|
|github.com/segmentio/backo-go|v1.0.1|间接依赖|go|
|libpthread.so.0||间接依赖||
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/ClickHouse/ch-go|v0.57.0|间接依赖|go|
|github.com/golang-jwt/jwt/v4|v4.5.0|直接依赖|go|
|@loader_path/libcrypto.1.1.dylib||间接依赖||
|github.com/tmc/grpc-websocket-proxy|v0.0.0-20220101234140-673ab2c3ae75|直接依赖|go|
|github.com/pierrec/lz4/v4|v4.1.18|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|libcrypto.so.1.1||间接依赖||
|github.com/google/uuid|v1.3.0|直接依赖|go|
|github.com/zeebo/xxh3|v1.0.2|间接依赖|go|
|github.com/power-devops/perfstat|v0.0.0-20220216144756-c35f1ee13d7c|间接依赖|go|
|github.com/pquerna/otp|v1.4.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/config|v1.18.27|直接依赖|go|
|github.com/xdg-go/stringprep|v1.0.4|间接依赖|go|
|github.com/lor00x/goldap|v0.0.0-20180618054307-a546dffdd1a3|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/configsources|v1.1.34|间接依赖|go|
|github.com/spf13/cobra|v1.7.0|直接依赖|go|
|github.com/pingcap/tidb|v1.1.0-beta.0.20220825063022-5263a0abda61|直接依赖|go|
|github.com/go-faster/errors|v0.6.1|间接依赖|go|
|github.com/satori/go.uuid|v1.2.0|间接依赖|go|
|github.com/form3tech-oss/jwt-go|v3.2.5+incompatible|间接依赖|go|
|github.com/99designs/keyring|v1.2.2|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/azcore|v1.6.1|间接依赖|go|
|github.com/bytebase/tsql-parser|v0.0.0-20230717060948-f266bf0280e2|直接依赖|go|
|github.com/google/jsonapi|v1.0.0|直接依赖|go|
|github.com/googleapis/gax-go/v2|v2.11.0|间接依赖|go|
|github.com/minio/asm2plan9s|v0.0.0-20200509001527-cdd76441f9d8|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|@loader_path/../lib/libcrypto.1.1.dylib||间接依赖||
|github.com/openark/golib|v0.0.0-20210531070646-355f37940af8|间接依赖|go|
|github.com/google/cel-go|v0.16.0|直接依赖|go|
|golang.org/x/sync|v0.3.0|间接依赖|go|
|github.com/jackc/pgx/v4|v4.12.1-0.20210724153913-640aa07df17c|直接依赖|go|
|github.com/montanaflynn/stats|v0.7.0|间接依赖|go|
|/usr/lib/libresolv.9.dylib||间接依赖||
|github.com/Azure/azure-sdk-for-go/sdk/internal|v1.3.0|间接依赖|go|
|github.com/gorilla/websocket|v1.4.2|间接依赖|go|
|libc.so.6||间接依赖||
|github.com/pganalyze/pg_query_go/v4|v4.0.0-00010101000000-000000000000|直接依赖|go|
|github.com/envoyproxy/go-control-plane|v0.11.1|间接依赖|go|
|github.com/xuri/nfp|v0.0.0-20220409054826-5e722a1d9e22|间接依赖|go|
|github.com/Azure/go-ntlmssp|v0.0.0-20221128193559-754e69321358|间接依赖|go|
|github.com/cenkalti/backoff/v4|v4.2.1|直接依赖|go|
|github.com/go-sql-driver/mysql|v1.7.1|直接依赖|go|
|ld-linux-aarch64.so.1||间接依赖||
|cloud.google.com/go|v0.110.6|间接依赖|go|
|github.com/jcmturner/goidentity/v6|v6.0.1|间接依赖|go|
|github.com/BurntSushi/toml|v1.2.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/aws/protocol/eventstream|v1.4.10|间接依赖|go|
|github.com/pkg/browser|v0.0.0-20210911075715-681adbf594b8|间接依赖|go|
|github.com/minio/c2goasm|v0.0.0-20190812172519-36a3d3bbc4f3|间接依赖|go|
|cloud.google.com/go/compute/metadata|v0.2.3|间接依赖|go|
|golang.org/x/sys|v0.9.0|直接依赖|go|
|google.golang.org/protobuf|v1.31.0|直接依赖|go|
|github.com/valyala/bytebufferpool|v1.0.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/endpoints/v2|v2.4.28|间接依赖|go|
|google.golang.org/genproto/googleapis/api|v0.0.0-20230731193218-e0aa005b6bdf|直接依赖|go|
|github.com/improbable-eng/grpc-web|v0.15.0|直接依赖|go|
|golang.org/x/mod|v0.11.0|间接依赖|go|
|gitee.com/chunanyong/dm|v1.8.12|直接依赖|go|
|github.com/lestrrat-go/blackmagic|v1.0.1|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230731193218-e0aa005b6bdf|直接依赖|go|
|github.com/uber/jaeger-lib|v2.4.1+incompatible|间接依赖|go|
|github.com/swaggo/files/v2|v2.0.0|间接依赖|go|
|go.uber.org/zap|v1.24.0|直接依赖|go|
|github.com/labstack/echo/v4|v4.10.2|直接依赖|go|
|github.com/jackc/pgpassfile|v1.0.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/feature/s3/manager|v1.11.70|直接依赖|go|
|github.com/tikv/pd/client|v0.0.0-20221101140400-25982e60b78a|间接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway/v2|v2.16.0|直接依赖|go|
|github.com/aws/smithy-go|v1.13.5|间接依赖|go|
|github.com/klauspost/compress|v1.16.6|间接依赖|go|
|github.com/dvsekhvalnov/jose2go|v1.5.0|间接依赖|go|
|github.com/danjacques/gofslock|v0.0.0-20220131014315-6e321f4509c8|间接依赖|go|
|github.com/go-asn1-ber/asn1-ber|v1.5.4|间接依赖|go|
|github.com/sirupsen/logrus|v1.9.3|间接依赖|go|
|github.com/google/flatbuffers|v23.5.26+incompatible|间接依赖|go|
|github.com/envoyproxy/protoc-gen-validate|v1.0.1|间接依赖|go|
|github.com/klauspost/cpuid/v2|v2.2.5|间接依赖|go|
|github.com/hashicorp/go-uuid|v1.0.3|间接依赖|go|
|github.com/jackc/pgproto3/v2|v2.3.1|间接依赖|go|
|github.com/redis/go-redis/v9|v9.0.5|直接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|github.com/pquerna/cachecontrol|v0.2.0|间接依赖|go|
|github.com/golang-sql/civil|v0.0.0-20220223132316-b832511892a9|间接依赖|go|
|github.com/bytebase/plsql-parser|v0.0.0-20230706061841-c93470b91bee|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/s3shared|v1.14.3|间接依赖|go|
|github.com/pingcap/failpoint|v0.0.0-20220801062533-2eaa32854a6c|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/ini|v1.3.35|间接依赖|go|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|github.com/google/s2a-go|v0.1.4|间接依赖|go|
|github.com/sashabaranov/go-openai|v1.9.0|直接依赖|go|
|github.com/golang/snappy|v0.0.4|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/accept-encoding|v1.9.11|间接依赖|go|
|cloud.google.com/go/compute|v1.23.0|间接依赖|go|
|github.com/gabriel-vasile/mimetype|v1.4.2|间接依赖|go|
|github.com/jcmturner/dnsutils/v2|v2.0.0|间接依赖|go|
|libstdc++.so.6||间接依赖||
|github.com/stoewer/go-strcase|v1.2.0|间接依赖|go|
|github.com/opentracing/basictracer-go|v1.1.0|间接依赖|go|
|github.com/richardlehane/mscfb|v1.0.4|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/storage/azblob|v1.0.0|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|cloud.google.com/go/iam|v1.1.1|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|github.com/lib/pq|v1.10.7|直接依赖|go|
|github.com/jcmturner/aescts/v2|v2.0.0|间接依赖|go|
|github.com/qiangmzsx/string-adapter/v2|v2.2.0|直接依赖|go|
|libm.so.6||间接依赖||
|github.com/snowflakedb/gosnowflake|v1.6.22|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/s3|v1.35.0|直接依赖|go|
|golang.org/x/oauth2|v0.9.0|直接依赖|go|
|gopkg.in/natefinch/lumberjack.v2|v2.0.0|间接依赖|go|
|github.com/go-ini/ini|v1.67.0|间接依赖|go|
|github.com/shopspring/decimal|v1.3.1|直接依赖|go|
|github.com/sijms/go-ora/v2|v2.7.8|直接依赖|go|
|github.com/xdg-go/scram|v1.1.2|间接依赖|go|
|github.com/xi2/xz|v0.0.0-20171230120015-48954b6210f8|直接依赖|go|
|github.com/grpc-ecosystem/go-grpc-middleware/v2|v2.0.0-rc.5|直接依赖|go|
|github.com/richardlehane/msoleps|v1.0.3|间接依赖|go|
|github.com/blang/semver/v4|v4.0.0|直接依赖|go|
|github.com/antlr4-go/antlr/v4|v4.13.0|直接依赖|go|
|github.com/shirou/gopsutil/v3|v3.22.10|间接依赖|go|
|github.com/gsterjov/go-libsecret|v0.0.0-20161001094733-a6f4afe4910c|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/jordan-wright/email|v4.0.1-0.20210109023952-943e75fe5223+incompatible|直接依赖|go|
|github.com/boombuler/barcode|v1.0.1-0.20190219062509-6c824513bacc|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|gopkg.in/square/go-jose.v2|v2.6.0|间接依赖|go|
|github.com/paulmach/orb|v0.9.2|直接依赖|go|
|github.com/go-ole/go-ole|v1.2.6|间接依赖|go|
|github.com/siddontang/go-log|v0.0.0-20190221022429-1e957dd83bed|间接依赖|go|
|github.com/dustin/go-humanize|v1.0.1|间接依赖|go|
|libgcc_s.so.1||间接依赖||
|github.com/JohnCGriffin/overflow|v0.0.0-20211019200055-46fa312c352c|间接依赖|go|
|github.com/census-instrumentation/opencensus-proto|v0.4.1|间接依赖|go|
|github.com/klauspost/asmfmt|v1.3.2|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/ClickHouse/clickhouse-go/v2|v2.10.1|直接依赖|go|
|cloud.google.com/go/longrunning|v0.5.1|间接依赖|go|
|github.com/go-openapi/spec|v0.20.9|间接依赖|go|
|github.com/mattn/go-sqlite3|v1.14.16|直接依赖|go|
|libresolv.so.2||间接依赖||
|github.com/pingcap/tidb/parser|v0.0.0-20221101143359-5b0be9af540e|直接依赖|go|
|github.com/mattn/go-isatty|v0.0.19|间接依赖|go|
|github.com/stretchr/testify|v1.8.4|直接依赖|go|
|github.com/tikv/client-go/v2|v2.0.1-0.20220725090834-0cdc7c1d0fb9|间接依赖|go|
|github.com/apache/thrift|v0.18.1|间接依赖|go|
|/usr/lib/libncurses.5.4.dylib||间接依赖||
|github.com/golang-sql/sqlexp|v0.1.0|间接依赖|go|
|go.opencensus.io|v0.24.0|间接依赖|go|
|github.com/99designs/go-keychain|v0.0.0-20191008050251-8e49817e8af4|间接依赖|go|
|github.com/jcmturner/gokrb5/v8|v8.4.4|间接依赖|go|
|github.com/vjeantet/ldapserver|v1.0.1|直接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|golang.org/x/term|v0.9.0|间接依赖|go|
|nhooyr.io/websocket|v1.8.7|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|直接依赖|go|
|github.com/mtibben/percent|v0.2.1|间接依赖|go|
|github.com/cncf/udpa/go|v0.0.0-20220112060539-c52dc94e7fbe|间接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.6|间接依赖|go|
|github.com/uber/jaeger-client-go|v2.30.0+incompatible|间接依赖|go|
|github.com/jackc/pgio|v1.0.0|间接依赖|go|
|@loader_path/../lib/libssl.1.1.dylib||间接依赖||
|github.com/bmizerany/assert|v0.0.0-20160611221934-b7ed37b82869|间接依赖|go|
|github.com/goccy/go-json|v0.10.2|间接依赖|go|
|libssl.so.1.1||间接依赖||
|github.com/github/gh-ost|v1.1.5|直接依赖|go|
|github.com/apache/arrow/go/v12|v12.0.1|间接依赖|go|
|github.com/cncf/xds/go|v0.0.0-20230607035331-e9ce68804cb4|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|libtinfo.so.5||间接依赖||
|github.com/lufia/plan9stats|v0.0.0-20220913051719-115f729f3c8c|间接依赖|go|
|github.com/dgraph-io/ristretto|v0.1.1-0.20220403145359-8e850b710d6d|直接依赖|go|
|librt.so.1||间接依赖||
|github.com/segmentio/analytics-go|v3.1.0+incompatible|直接依赖|go|
|github.com/godbus/dbus|v0.0.0-20190726142602-4481cbc300e2|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/feature/ec2/imds|v1.13.4|间接依赖|go|
|github.com/bytebase/mysql-parser|v0.0.0-20230612050356-4592d9ba30da|直接依赖|go|
|github.com/pingcap/errors|v0.11.5-0.20211224045212-9687c2b0f87c|间接依赖|go|
|golang.org/x/text|v0.10.0|直接依赖|go|
|github.com/bytebase/mongo-parser|v0.0.0-20230726155532-29863b4ce95d|直接依赖|go|
|github.com/grpc-ecosystem/go-grpc-middleware|v1.4.0|间接依赖|go|
|github.com/go-ldap/ldap/v3|v3.4.5|直接依赖|go|
|github.com/lestrrat-go/httpcc|v1.0.1|间接依赖|go|
|go.opentelemetry.io/otel/trace|v1.16.0|间接依赖|go|
|golang.org/x/net|v0.11.0|间接依赖|go|
|github.com/valyala/fasttemplate|v1.2.2|间接依赖|go|
|github.com/Knetic/govaluate|v3.0.1-0.20171022003610-9aa49832a739+incompatible|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sso|v1.12.12|间接依赖|go|
|google.golang.org/grpc|v1.57.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/checksum|v1.1.29|间接依赖|go|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|github.com/siddontang/go|v0.0.0-20180604090527-bdc77568d726|间接依赖|go|
|github.com/swaggo/swag|v1.16.1|直接依赖|go|
|github.com/prometheus/client_golang|v1.14.0|间接依赖|go|
|github.com/pingcap/log|v1.1.1-0.20221015072633-39906604fb81|间接依赖|go|
|github.com/mohae/deepcopy|v0.0.0-20170929034955-c48cc78d4826|间接依赖|go|
|github.com/prometheus/common|v0.40.0|间接依赖|go|
|github.com/lestrrat-go/httprc|v1.0.4|间接依赖|go|
|libncurses.so.5||间接依赖||
|golang.org/x/tools|v0.10.0|间接依赖|go|
|github.com/rs/cors|v1.7.0|间接依赖|go|
|github.com/cznic/mathutil|v0.0.0-20181122101859-297441e03548|间接依赖|go|
|github.com/googleapis/enterprise-certificate-proxy|v0.2.5|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|github.com/xdg-go/pbkdf2|v1.0.0|间接依赖|go|
|github.com/prometheus/procfs|v0.9.0|间接依赖|go|
|github.com/yusufpapurcu/wmi|v1.2.2|间接依赖|go|
|github.com/remyoudompheng/bigfft|v0.0.0-20230129092748-24d4a6f8daec|间接依赖|go|
|github.com/swaggo/echo-swagger|v1.4.0|直接依赖|go|
|/usr/lib/libSystem.B.dylib||间接依赖||
|github.com/pingcap/tipb|v0.0.0-20221020071514-cd933387bcb5|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)