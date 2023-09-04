# cloudflare/cloudflared安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698761135049457664.svg)](https://www.murphysec.com/console/report/1698035634504777728/1698761135049457664)

仓库描述：Cloudflare Tunnel client (formerly Argo Tunnel)

仓库地址：[https://github.com/cloudflare/cloudflared](https://github.com/cloudflare/cloudflared)

| star：6425 | watch：93 | fork：617 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-31 23:03:37 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-05 02:15:34 | 组件总数：109 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|CIRCL 安全漏洞|对异常条件的处理不恰当|[MPS-2023-9182](https://www.oscs1024.com/hd/MPS-2023-9182)|CVE-2023-1732|高危|
|Requests Proxy-Authorization 标头泄露漏洞|未授权敏感信息泄露|[MPS-hr61-tzey](https://www.oscs1024.com/hd/MPS-hr61-tzey)|CVE-2023-32681|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/cloudflare/circl|v1.2.1-0.20220809205628-0a9554f37a47|1.3.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|requests|2.28.2|2.31.0|间接依赖|建议修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|ISC|1|Low|
|Apache-2.0|34|Low|
|BSD-3-Clause|29|Low|
|MIT|33|Low|
|BSD-2-Clause|5|Low|
|自定义许可证|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/opentracing/opentracing-go|v1.2.0|间接依赖|go|
|github.com/go-jose/go-jose/v3|v3.0.0|直接依赖|go|
|github.com/quic-go/qtls-go1-19|v0.3.2|间接依赖|go|
|go.opentelemetry.io/proto/otlp|v0.15.0|直接依赖|go|
|github.com/kr/text|v0.2.0|间接依赖|go|
|github.com/google/gopacket|v1.1.19|直接依赖|go|
|github.com/facebookgo/stack|v0.0.0-20160209184415-751773369052|间接依赖|go|
|github.com/onsi/ginkgo/v2|v2.4.0|间接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway/v2|v2.7.0|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|直接依赖|go|
|github.com/facebookgo/freeport|v0.0.0-20150612182905-d4adf43b75b9|间接依赖|go|
|golang.org/x/net|v0.12.0|直接依赖|go|
|get_config_from_file||间接依赖|pip|
|METRICS_PORT||间接依赖|pip|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|github.com/getsentry/sentry-go|v0.16.0|直接依赖|go|
|github.com/gorilla/websocket|v1.4.2|直接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/go-chi/cors|v1.2.1|直接依赖|go|
|pyyaml|5.4.1|间接依赖|pip|
|go.opentelemetry.io/otel/trace|v1.6.3|直接依赖|go|
|go.opentelemetry.io/contrib/propagators|v0.22.0|直接依赖|go|
|github.com/quic-go/quic-go|v0.0.0-00010101000000-000000000000|直接依赖|go|
|github.com/grpc-ecosystem/grpc-opentracing|v0.0.0-20180507213350-8e809c8a8645|间接依赖|go|
|github.com/stretchr/testify|v1.8.1|直接依赖|go|
|github.com/fsnotify/fsnotify|v1.4.9|直接依赖|go|
|google.golang.org/grpc|v1.51.0|间接依赖|go|
|github.com/go-task/slim-sprig|v0.0.0-20210107165309-348f09dbbbc0|间接依赖|go|
|google.golang.org/protobuf|v1.28.1|直接依赖|go|
|github.com/prometheus/client_model|v0.2.0|直接依赖|go|
|github.com/coreos/go-oidc/v3|v3.6.0|直接依赖|go|
|cloudflare|2.8.15|间接依赖|pip|
|github.com/json-iterator/go|v1.1.12|直接依赖|go|
|github.com/flynn/go-shlex|v0.0.0-20150515145356-3f9db97f8568|间接依赖|go|
|github.com/cpuguy83/go-md2man/v2|v2.0.0|间接依赖|go|
|golang.org/x/sync|v0.1.0|直接依赖|go|
|github.com/facebookgo/grace|v0.0.0-20180706040059-75cf19382434|直接依赖|go|
|gopkg.in/check.v1|v1.0.0-20201130134442-10cb98267c6c|间接依赖|go|
|github.com/golang-collections/collections|v0.0.0-20130729185459-604e922904d3|直接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|直接依赖|go|
|github.com/prometheus/common|v0.37.0|间接依赖|go|
|github.com/urfave/cli/v2|v2.3.0|直接依赖|go|
|github.com/klauspost/compress|v1.15.11|间接依赖|go|
|golang.org/x/text|v0.11.0|间接依赖|go|
|get_tunnel_connector_id||间接依赖|pip|
|github.com/prometheus/client_golang|v1.13.0|直接依赖|go|
|github.com/cespare/xxhash/v2|v2.1.2|间接依赖|go|
|github.com/coredns/coredns|v1.10.0|直接依赖|go|
|golang.org/x/exp|v0.0.0-20221205204356-47842c84f3db|间接依赖|go|
|github.com/facebookgo/subset|v0.0.0-20150612182917-8dac2c3c4870|间接依赖|go|
|golang.org/x/tools|v0.6.0|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace|v1.6.3|直接依赖|go|
|github.com/russross/blackfriday/v2|v2.1.0|间接依赖|go|
|go.uber.org/automaxprocs|v1.4.0|直接依赖|go|
|golang.org/x/crypto|v0.11.0|直接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|github.com/kylelemons/godebug|v1.1.0|间接依赖|go|
|gopkg.in/natefinch/lumberjack.v2|v2.0.0|直接依赖|go|
|MAX_RETRIES||间接依赖|pip|
|github.com/onsi/gomega|v1.23.0|间接依赖|go|
|github.com/quic-go/qtls-go1-20|v0.2.2|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|Enum||间接依赖|pip|
|retrying|1.3.4|间接依赖|pip|
|flaky|3.7.0|间接依赖|pip|
|go.opentelemetry.io/otel/sdk|v1.6.3|直接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/miekg/dns|v1.1.50|直接依赖|go|
|requests|2.28.2|间接依赖|pip|
|golang.org/x/oauth2|v0.6.0|间接依赖|go|
|github.com/golang/protobuf|v1.5.2|间接依赖|go|
|github.com/gobwas/httphead|v0.0.0-20200921212729-da3d93bc3c58|间接依赖|go|
|github.com/google/uuid|v1.3.0|直接依赖|go|
|zombiezen.com/go/capnproto2|v2.18.0+incompatible|直接依赖|go|
|golang.org/x/sys|v0.10.0|直接依赖|go|
|github.com/go-logr/logr|v1.2.3|间接依赖|go|
|github.com/apparentlymart/go-cidr|v1.1.0|间接依赖|go|
|github.com/coredns/caddy|v1.1.1|间接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|直接依赖|go|
|github.com/prometheus/procfs|v0.8.0|间接依赖|go|
|persist_origin_cert||间接依赖|pip|
|pytest|7.3.1|间接依赖|pip|
|github.com/BurntSushi/toml|v1.2.0|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.16|间接依赖|go|
|github.com/golang/mock|v1.6.0|间接依赖|go|
|LOGGER||间接依赖|pip|
|github.com/cloudflare/circl|v1.2.1-0.20220809205628-0a9554f37a47|间接依赖|go|
|github.com/facebookgo/ensure|v0.0.0-20160127193407-b4ab57deab51|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20221202195650-67e5cbc046fd|间接依赖|go|
|golang.org/x/term|v0.10.0|直接依赖|go|
|websockets|11.0.1|间接依赖|pip|
|github.com/gobwas/pool|v0.2.1|间接依赖|go|
|util||间接依赖|pip|
|golang.org/x/mod|v0.8.0|间接依赖|go|
|github.com/cloudflare/golibs|v0.0.0-20170913112048-333127dbecfc|直接依赖|go|
|github.com/gobwas/ws|v1.0.4|直接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/coreos/go-systemd/v22|v22.5.0|直接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.1|间接依赖|go|
|github.com/go-chi/chi/v5|v5.0.8|直接依赖|go|
|go.opentelemetry.io/otel|v1.6.3|直接依赖|go|
|github.com/google/pprof|v0.0.0-20210720184732-4bb14d4b1be1|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|nhooyr.io/websocket|v1.8.7|直接依赖|go|
|github.com/rs/zerolog|v1.20.0|直接依赖|go|
|auto||间接依赖|pip|
|pytest-asyncio|0.21.0|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)