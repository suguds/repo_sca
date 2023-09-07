# ClickHouse/clickhouse-go安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699848834623782912.svg)](https://www.murphysec.com/console/report/1699848834422456320/1699848834623782912)

仓库描述：Golang driver for ClickHouse

仓库地址：[https://github.com/ClickHouse/clickhouse-go](https://github.com/ClickHouse/clickhouse-go)

| star：2528 | watch：54 | fork：521 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-08 01:32:12 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-08 02:15:24 | 组件总数：57 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|go.uuid 不安全的随机性漏洞|使用具有密码学弱点缺陷的PRNG|[MPS-2021-7854](https://www.oscs1024.com/hd/MPS-2021-7854)|CVE-2021-3538|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/satori/go.uuid|v1.2.0||直接依赖|建议修复|C:1|H:0|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|17|Low|
|Apache-2.0|19|Low|
|MIT|20|Low|
|BSD-2-Clause|3|Low|
|CC-BY-SA-4.0|1|Medium|
|ISC|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/cloudflare/golz4|v0.0.0-20150217214814-ef862a3cdc58|间接依赖|go|
|go.opentelemetry.io/otel|v1.17.0|间接依赖|go|
|github.com/docker/docker|v24.0.5+incompatible|直接依赖|go|
|github.com/yusufpapurcu/wmi|v1.2.2|间接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230525234030-28d5490b6b19|间接依赖|go|
|github.com/moby/sys/sequential|v0.5.0|间接依赖|go|
|github.com/containerd/containerd|v1.7.3|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|google.golang.org/grpc|v1.57.0|间接依赖|go|
|github.com/tklauser/numcpus|v0.4.0|间接依赖|go|
|github.com/google/uuid|v1.3.1|直接依赖|go|
|github.com/mkevac/debugcharts|v0.0.0-20191222103121-ae1c48aa8615|直接依赖|go|
|github.com/segmentio/asm|v1.2.0|间接依赖|go|
|github.com/tklauser/go-sysconf|v0.3.10|间接依赖|go|
|github.com/opencontainers/image-spec|v1.1.0-rc4|间接依赖|go|
|github.com/moby/term|v0.5.0|间接依赖|go|
|github.com/Microsoft/go-winio|v0.6.1|间接依赖|go|
|golang.org/x/exp|v0.0.0-20230510235704-dd950f8aeaea|间接依赖|go|
|github.com/shopspring/decimal|v1.3.1|直接依赖|go|
|golang.org/x/sys|v0.11.0|间接依赖|go|
|github.com/go-faster/city|v1.0.1|间接依赖|go|
|github.com/docker/distribution|v2.8.2+incompatible|间接依赖|go|
|github.com/klauspost/compress|v1.16.7|间接依赖|go|
|github.com/stretchr/testify|v1.8.4|直接依赖|go|
|github.com/docker/go-units|v0.5.0|直接依赖|go|
|github.com/Azure/go-ansiterm|v0.0.0-20210617225240-d185dfc1b5a1|间接依赖|go|
|github.com/paulmach/orb|v0.10.0|直接依赖|go|
|golang.org/x/net|v0.9.0|间接依赖|go|
|github.com/shirou/gopsutil|v3.21.11+incompatible|间接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|google.golang.org/protobuf|v1.30.0|间接依赖|go|
|github.com/gorilla/websocket|v1.4.2|间接依赖|go|
|github.com/opencontainers/runc|v1.1.5|间接依赖|go|
|github.com/satori/go.uuid|v1.2.0|直接依赖|go|
|github.com/testcontainers/testcontainers-go|v0.23.0|直接依赖|go|
|go.opentelemetry.io/otel/trace|v1.17.0|直接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|直接依赖|go|
|github.com/ClickHouse/ch-go|v0.58.2|直接依赖|go|
|dario.cat/mergo|v1.0.0|间接依赖|go|
|golang.org/x/tools|v0.7.0|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/cpuguy83/dockercfg|v0.3.1|间接依赖|go|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|github.com/moby/patternmatcher|v0.5.0|间接依赖|go|
|github.com/docker/go-connections|v0.4.0|直接依赖|go|
|github.com/morikuni/aec|v1.0.0|间接依赖|go|
|github.com/cenkalti/backoff/v4|v4.2.1|间接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/magiconair/properties|v1.8.7|间接依赖|go|
|github.com/pierrec/lz4/v4|v4.1.18|间接依赖|go|
|github.com/sirupsen/logrus|v1.9.0|间接依赖|go|
|golang.org/x/mod|v0.9.0|间接依赖|go|
|github.com/go-faster/errors|v0.6.1|间接依赖|go|
|github.com/andybalholm/brotli|v1.0.5|直接依赖|go|
|github.com/go-ole/go-ole|v1.2.6|间接依赖|go|
|github.com/ClickHouse/clickhouse-go|v1.5.4|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)