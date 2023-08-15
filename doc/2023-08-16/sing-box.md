# SagerNet/sing-box安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1691511931003494400.svg)](https://www.murphysec.com/console/report/1691511930957357056/1691511931003494400)

仓库描述：The universal proxy platform

仓库地址：[https://github.com/SagerNet/sing-box](https://github.com/SagerNet/sing-box)

| star：4267 | watch：60 | fork：527 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-15 19:50:01 | 许可证：- |
| 最近检测时间：2023-08-16 02:08:00 | 组件总数：102 | 漏洞总数：4 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|MPS-2023-8823||[MPS-2023-8823](https://www.oscs1024.com/hd/MPS-2023-8823)|CVE-2023-28840|高危|
|MPS-2023-8824||[MPS-2023-8824](https://www.oscs1024.com/hd/MPS-2023-8824)|CVE-2023-28841|中危|
|MPS-2023-8826|对异常条件的处理不恰当|[MPS-2023-8826](https://www.oscs1024.com/hd/MPS-2023-8826)|CVE-2023-28842|中危|
|MPS-2023-9182|对异常条件的处理不恰当|[MPS-2023-9182](https://www.oscs1024.com/hd/MPS-2023-9182)|CVE-2023-1732|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/cloudflare/circl|v1.2.1-0.20221019164342-6ab4dfed8f3c|1.3.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|github.com/docker/docker|v20.10.18+incompatible|23.0.3|直接依赖|建议修复|C:0|H:1|M:2|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|16|Low|
|CC0-1.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/scjalliance/comshim|v0.0.0-20230315213746-5e51f40bd3b9|间接依赖|go|
|github.com/pierrec/lz4/v4|v4.1.14|间接依赖|go|
|github.com/mholt/acmez|v1.2.0|直接依赖|go|
|github.com/moby/term|v0.0.0-20221205130635-1aeaba878587|间接依赖|go|
|github.com/cloudflare/circl|v1.2.1-0.20221019164342-6ab4dfed8f3c|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|github.com/spyzhov/ajson|v0.7.1|直接依赖|go|
|github.com/sagernet/utls|v0.0.0-20230309024959-6732c2ab36f2|直接依赖|go|
|github.com/docker/go-connections|v0.4.0|直接依赖|go|
|go4.org/netipx|v0.0.0-20230728184502-ec4c8b891b28|直接依赖|go|
|github.com/sagernet/sing-tun|v0.1.12-0.20230812113806-10d98f26797a|直接依赖|go|
|github.com/go-task/slim-sprig|v0.0.0-20230315185526-52ccab3ef572|间接依赖|go|
|github.com/klauspost/compress|v1.15.15|间接依赖|go|
|berty.tech/go-libtor|v1.0.385|直接依赖|go|
|github.com/go-chi/chi/v5|v5.0.10|直接依赖|go|
|golang.org/x/tools|v0.10.0|间接依赖|go|
|golang.org/x/crypto|v0.12.0|直接依赖|go|
|github.com/docker/distribution|v2.8.1+incompatible|间接依赖|go|
|github.com/onsi/ginkgo/v2|v2.9.5|间接依赖|go|
|github.com/sagernet/quic-go|v0.0.0-20230811130919-d6f54a117913|直接依赖|go|
|github.com/morikuni/aec|v1.0.0|间接依赖|go|
|go.etcd.io/bbolt|v1.3.7|直接依赖|go|
|github.com/sagernet/go-tun2socks|v1.16.12-0.20220818015926-16cb67876a61|间接依赖|go|
|github.com/docker/go-units|v0.4.0|间接依赖|go|
|github.com/sagernet/netlink|v0.0.0-20220905062125-8043b4a9aa97|间接依赖|go|
|gopkg.in/check.v1|v1.0.0-20200227125254-8fa46927fb4f|间接依赖|go|
|google.golang.org/protobuf|v1.31.0|直接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230525234030-28d5490b6b19|间接依赖|go|
|github.com/niemeyer/pretty|v0.0.0-20200227124842-a10e7caefd8e|间接依赖|go|
|github.com/quic-go/qtls-go1-20|v0.3.1|间接依赖|go|
|github.com/sagernet/sing-dns|v0.1.9-0.20230731012726-ad50da89b659|直接依赖|go|
|github.com/sagernet/wireguard-go|v0.0.0-20230807125731-5d4a7ef2dc5f|直接依赖|go|
|github.com/pires/go-proxyproto|v0.7.0|直接依赖|go|
|lukechampine.com/blake3|v1.2.1|间接依赖|go|
|go.uber.org/goleak|v1.2.0|直接依赖|go|
|github.com/opencontainers/image-spec|v1.0.2|间接依赖|go|
|go.uber.org/zap|v1.25.0|直接依赖|go|
|github.com/vishvananda/netns|v0.0.0-20211101163701-50045581ed74|间接依赖|go|
|github.com/sirupsen/logrus|v1.9.3|间接依赖|go|
|github.com/gofrs/uuid/v5|v5.0.0|直接依赖|go|
|golang.zx2c4.com/wireguard/wgctrl|v0.0.0-20230429144221-925a1e7659e6|直接依赖|go|
|github.com/dustin/go-humanize|v1.0.1|直接依赖|go|
|github.com/sagernet/gvisor|v0.0.0-20230627031050-1ab0276e0dd2|直接依赖|go|
|golang.org/x/exp|v0.0.0-20230626212559-97b1e661b5df|直接依赖|go|
|github.com/andybalholm/brotli|v1.0.5|间接依赖|go|
|github.com/sagernet/sing-mux|v0.1.3-0.20230811111955-dc1639b5204c|直接依赖|go|
|github.com/docker/docker|v20.10.18+incompatible|直接依赖|go|
|github.com/libdns/libdns|v0.2.1|间接依赖|go|
|github.com/Dreamacro/protobytes|v0.0.0-20230617041236-6500a9f4f158|间接依赖|go|
|github.com/sagernet/sing-shadowsocks2|v0.1.3|直接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/logrusorgru/aurora|v2.0.3+incompatible|直接依赖|go|
|github.com/zeebo/blake3|v0.2.3|间接依赖|go|
|golang.org/x/mod|v0.11.0|间接依赖|go|
|github.com/miekg/dns|v1.1.55|直接依赖|go|
|github.com/sagernet/sing|v0.2.10-0.20230807080248-4db0062caa0a|直接依赖|go|
|github.com/sagernet/tfo-go|v0.0.0-20230303015439-ffcfd8c41cf9|直接依赖|go|
|github.com/insomniacslk/dhcp|v0.0.0-20230731140434-0f9eb93a696c|直接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|github.com/go-chi/render|v1.0.3|直接依赖|go|
|github.com/Dreamacro/clash|v1.17.0|直接依赖|go|
|github.com/sagernet/sing-shadowsocks|v0.2.4|直接依赖|go|
|github.com/sagernet/sing-vmess|v0.1.7|直接依赖|go|
|google.golang.org/grpc|v1.57.0|直接依赖|go|
|github.com/golang/mock|v1.6.0|间接依赖|go|
|golang.org/x/text|v0.12.0|间接依赖|go|
|github.com/hashicorp/yamux|v0.1.1|间接依赖|go|
|github.com/ooni/go-libtor|v1.1.8|直接依赖|go|
|github.com/josharian/native|v1.1.0|间接依赖|go|
|golang.org/x/sys|v0.11.0|直接依赖|go|
|golang.org/x/time|v0.3.0|间接依赖|go|
|golang.org/x/net|v0.14.0|直接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|直接依赖|go|
|github.com/google/btree|v1.1.2|间接依赖|go|
|github.com/go-ole/go-ole|v1.2.6|间接依赖|go|
|github.com/sagernet/reality|v0.0.0-20230406110435-ee17307e7691|直接依赖|go|
|github.com/ajg/form|v1.5.1|间接依赖|go|
|github.com/sagernet/sing-shadowtls|v0.1.4|直接依赖|go|
|github.com/quic-go/qpack|v0.4.0|间接依赖|go|
|github.com/oschwald/maxminddb-golang|v1.12.0|直接依赖|go|
|go.uber.org/multierr|v1.11.0|间接依赖|go|
|github.com/spf13/cobra|v1.7.0|直接依赖|go|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|github.com/sagernet/cloudflare-tls|v0.0.0-20221031050923-d70792f4c3a0|直接依赖|go|
|github.com/cretz/bine|v0.2.0|直接依赖|go|
|github.com/stretchr/testify|v1.8.4|直接依赖|go|
|github.com/sagernet/sing-box|v0.0.0|直接依赖|go|
|github.com/sagernet/websocket|v0.0.0-20220913015213-615516348b4e|直接依赖|go|
|github.com/u-root/uio|v0.0.0-20230220225925-ffce2a382923|间接依赖|go|
|github.com/go-chi/cors|v1.2.1|直接依赖|go|
|github.com/caddyserver/certmagic|v0.19.1|直接依赖|go|
|github.com/sagernet/gomobile|v0.0.0-20230728014906-3de089147f59|直接依赖|go|
|github.com/sagernet/smux|v0.0.0-20230312102458-337ec2a5af37|直接依赖|go|
|gotest.tools/v3|v3.4.0|间接依赖|go|
|github.com/klauspost/cpuid/v2|v2.2.5|间接依赖|go|
|github.com/Microsoft/go-winio|v0.6.0|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/google/pprof|v0.0.0-20210407192527-94a9f03dee38|间接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)