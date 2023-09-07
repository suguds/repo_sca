# tinode/chat安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699848571092336640.svg)](https://www.murphysec.com/console/report/1699848570962313216/1699848571092336640)

仓库描述：Instant messaging platform. Backend in Go. Clients: Swift iOS, Java Android, JS webapp, scriptable command line; chatbots

仓库地址：[https://github.com/tinode/chat](https://github.com/tinode/chat)

| star：10678 | watch：296 | fork：1742 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-06 21:57:17 | 许可证：GPL-3.0 |
| 最近检测时间：2023-09-08 02:14:23 | 组件总数：79 | 漏洞总数：3 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|grpc不加限制或调节的资源分配漏洞||[MPS-7ht6-lm4j](https://www.oscs1024.com/hd/MPS-7ht6-lm4j)|CVE-2023-33953|高危|
|Requests Proxy-Authorization 标头泄露漏洞|未授权敏感信息泄露|[MPS-hr61-tzey](https://www.oscs1024.com/hd/MPS-hr61-tzey)|CVE-2023-32681|中危|
|Flask 安全漏洞|通过持久性Cookie导致的信息暴露|[MPS-y7qk-6aom](https://www.oscs1024.com/hd/MPS-y7qk-6aom)|CVE-2023-30861|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|requests|2.21.0|2.31.0|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|flask|1.1.0|2.3.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|grpcio|1.40.0|1.56.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|22|Low|
|Apache-2.0|34|Low|
|BSD-3-Clause|16|Low|
|BSD-2-Clause|3|Low|
|MPL-2.0|1|Low|
|HPND|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/jmoiron/sqlx|v1.3.5|直接依赖|go|
|Popen||间接依赖|pip|
|gopkg.in/cenkalti/backoff.v2|v2.2.1|间接依赖|go|
|tinode-grpc|0.20.0b3|间接依赖|pip|
|go.mongodb.org/mongo-driver|v1.11.2|直接依赖|go|
|github.com/prometheus/procfs|v0.9.0|间接依赖|go|
|golang.org/x/sys|v0.5.0|间接依赖|go|
|github.com/jackc/pgproto3/v2|v2.3.2|间接依赖|go|
|cloud.google.com/go/firestore|v1.9.0|间接依赖|go|
|cloud.google.com/go/compute|v1.18.0|间接依赖|go|
|github.com/prometheus/client_golang|v1.14.0|直接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/googleapis/gax-go/v2|v2.7.0|间接依赖|go|
|github.com/youmark/pkcs8|v0.0.0-20201027041543-1326539a0a0a|间接依赖|go|
|github.com/prometheus/client_model|v0.3.0|间接依赖|go|
|github.com/jackc/chunkreader/v2|v2.0.1|间接依赖|go|
|github.com/jackc/pgconn|v1.14.0|直接依赖|go|
|firebase.google.com/go|v3.13.0+incompatible|直接依赖|go|
|github.com/golang/protobuf|v1.5.2|间接依赖|go|
|PIPE||间接依赖|pip|
|flask|1.1.0|间接依赖|pip|
|github.com/xdg-go/pbkdf2|v1.0.0|间接依赖|go|
|cloud.google.com/go/storage|v1.29.0|间接依赖|go|
|github.com/klauspost/compress|v1.15.15|间接依赖|go|
|github.com/kr/pretty|v0.3.1|间接依赖|go|
|github.com/aws/aws-sdk-go|v1.44.204|直接依赖|go|
|github.com/google/uuid|v1.3.0|间接依赖|go|
|requests|2.21.0|间接依赖|pip|
|github.com/tinode/snowflake|v1.0.0|直接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230216225411-c8e22ba71e44|间接依赖|go|
|prompt_toolkit|2.0.10|间接依赖|pip|
|cloud.google.com/go/iam|v0.12.0|间接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|cloud.google.com/go|v0.110.0|间接依赖|go|
|google.golang.org/grpc|v1.53.0|直接依赖|go|
|github.com/go-sql-driver/mysql|v1.7.0|直接依赖|go|
|golang.org/x/text|v0.7.0|直接依赖|go|
|golang.org/x/xerrors|v0.0.0-20220907171357-04be3eba64a2|间接依赖|go|
|grpcio|1.40.0|间接依赖|pip|
|github.com/sirupsen/logrus|v1.9.0|间接依赖|go|
|github.com/felixge/httpsnoop|v1.0.3|间接依赖|go|
|golang.org/x/net|v0.7.0|间接依赖|go|
|tinode-grpc|0.18.0|间接依赖|pip|
|github.com/xdg-go/scram|v1.1.2|间接依赖|go|
|github.com/prometheus/common|v0.39.0|直接依赖|go|
|go.opencensus.io|v0.24.0|间接依赖|go|
|google.golang.org/api|v0.110.0|直接依赖|go|
|github.com/jackc/pgx/v4|v4.18.1|直接依赖|go|
|github.com/golang/snappy|v0.0.4|间接依赖|go|
|github.com/jackc/pgservicefile|v0.0.0-20221227161230-091c0ba34f0a|间接依赖|go|
|golang.org/x/crypto|v0.6.0|直接依赖|go|
|cloud.google.com/go/compute/metadata|v0.2.3|间接依赖|go|
|github.com/jackc/pgio|v1.0.0|间接依赖|go|
|golang.org/x/time|v0.3.0|间接依赖|go|
|Pillow|5.4.1|间接依赖|pip|
|github.com/googleapis/enterprise-certificate-proxy|v0.2.3|间接依赖|go|
|github.com/hailocab/go-hostpool|v0.0.0-20160125115350-e80d13ce29ed|间接依赖|go|
|gopkg.in/rethinkdb/rethinkdb-go.v6|v6.2.2|直接依赖|go|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|cloud.google.com/go/longrunning|v0.4.1|间接依赖|go|
|github.com/gorilla/handlers|v1.5.1|直接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|间接依赖|go|
|google.golang.org/protobuf|v1.28.1|直接依赖|go|
|github.com/opentracing/opentracing-go|v1.2.0|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/tinode/jsonco|v1.0.0|直接依赖|go|
|github.com/jackc/puddle|v1.3.0|间接依赖|go|
|github.com/jackc/pgpassfile|v1.0.0|间接依赖|go|
|github.com/nyaruka/phonenumbers|v1.1.6|直接依赖|go|
|golang.org/x/sync|v0.1.0|间接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/xdg-go/stringprep|v1.0.4|间接依赖|go|
|golang.org/x/oauth2|v0.5.0|直接依赖|go|
|github.com/gorilla/websocket|v1.5.0|直接依赖|go|
|github.com/jackc/pgtype|v1.14.0|间接依赖|go|
|github.com/montanaflynn/stats|v0.7.0|间接依赖|go|
|github.com/golang/mock|v1.6.0|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)