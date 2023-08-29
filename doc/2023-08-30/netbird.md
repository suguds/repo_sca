# netbirdio/netbird安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696585487023431680.svg)](https://www.murphysec.com/console/report/1692961872141901824/1696585487023431680)

仓库描述：Connect your devices into a single secure private WireGuard®-based mesh network with SSO/MFA and simple access controls.

仓库地址：[https://github.com/netbirdio/netbird](https://github.com/netbirdio/netbird)

| star：5629 | watch：67 | fork：208 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-30 00:17:44 | 许可证：BSD-3-Clause |
| 最近检测时间：2023-08-30 02:08:08 | 组件总数：140 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|service安全漏洞|不可信的搜索路径|[MPS-2022-9155](https://www.oscs1024.com/hd/MPS-2022-9155)|CVE-2022-29583|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/kardianos/service|v1.2.1-0.20210728001519-a323c3813bc7||直接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|50|Low|
|BSD-3-Clause|35|Low|
|Apache-2.0|45|Low|
|MPL-2.0|3|Low|
|Zlib|1|Low|
|BSD-2-Clause|4|Low|
|GPL-3.0|2|Medium|
|ISC|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/pion/turn/v2|v2.1.0|间接依赖|go|
|golang.org/x/net|v0.10.0|直接依赖|go|
|github.com/gorilla/mux|v1.8.0|直接依赖|go|
|github.com/go-gl/glfw/v3.3/glfw|v0.0.0-20211024062804-40e447a793be|间接依赖|go|
|google.golang.org/grpc|v1.55.0|直接依赖|go|
|k8s.io/apimachinery|v0.23.5|间接依赖|go|
|github.com/hashicorp/go-uuid|v1.0.2|间接依赖|go|
|github.com/miekg/dns|v1.1.43|直接依赖|go|
|golang.org/x/tools|v0.6.0|间接依赖|go|
|go.opentelemetry.io/otel/sdk/metric|v0.33.0|直接依赖|go|
|github.com/pion/udp/v2|v2.0.1|间接依赖|go|
|github.com/prometheus/client_golang|v1.14.0|直接依赖|go|
|github.com/hashicorp/go-secure-stdlib/base62|v0.1.2|直接依赖|go|
|github.com/eko/gocache/v3|v3.1.1|直接依赖|go|
|gopkg.in/square/go-jose.v2|v2.6.0|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|直接依赖|go|
|github.com/sirupsen/logrus|v1.9.0|直接依赖|go|
|github.com/getlantern/ops|v0.0.0-20190325191751-d70cb0d6f85f|间接依赖|go|
|github.com/kardianos/service|v1.2.1-0.20210728001519-a323c3813bc7|直接依赖|go|
|github.com/stretchr/testify|v1.8.1|直接依赖|go|
|github.com/rs/xid|v1.3.0|直接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/pion/randutil|v0.1.0|间接依赖|go|
|github.com/googleapis/enterprise-certificate-proxy|v0.2.3|间接依赖|go|
|fyne.io/fyne/v2|v2.1.4|直接依赖|go|
|github.com/getlantern/hidden|v0.0.0-20190325191715-f02dbb02be55|间接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|go.opentelemetry.io/otel/metric|v0.33.0|直接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|golang.org/x/mod|v0.8.0|间接依赖|go|
|github.com/rs/cors|v1.8.0|直接依赖|go|
|golang.zx2c4.com/wireguard/windows|v0.5.3|直接依赖|go|
|github.com/kelseyhightower/envconfig|v1.4.0|间接依赖|go|
|github.com/XiaoMi/pegasus-go-client|v0.0.0-20210427083443-f3b6b08bc4c2|间接依赖|go|
|github.com/magiconair/properties|v1.8.5|直接依赖|go|
|github.com/yuin/goldmark|v1.4.13|间接依赖|go|
|github.com/getlantern/errors|v0.0.0-20190325191628-abdb3e3e36f7|间接依赖|go|
|github.com/anmitsu/go-shlex|v0.0.0-20200514113438-38f4b401e2be|间接依赖|go|
|github.com/prometheus/procfs|v0.8.0|间接依赖|go|
|github.com/gliderlabs/ssh|v0.3.4|直接依赖|go|
|golang.zx2c4.com/wireguard|v0.0.0-20230223181233-21636207a675|直接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|github.com/google/gopacket|v1.1.19|直接依赖|go|
|github.com/pion/mdns|v0.0.7|间接依赖|go|
|github.com/google/nftables|v0.0.0-20220808154552-2eca00135732|直接依赖|go|
|gopkg.in/tomb.v1|v1.0.0-20141024135613-dd632973f1e7|间接依赖|go|
|github.com/pion/logging|v0.2.2|直接依赖|go|
|github.com/onsi/ginkgo|v1.16.5|直接依赖|go|
|github.com/getlantern/golog|v0.0.0-20190830074920-4ef2e798c2d7|间接依赖|go|
|github.com/pion/stun|v0.4.0|直接依赖|go|
|golang.org/x/text|v0.9.0|间接依赖|go|
|github.com/nadoo/ipset|v0.5.0|直接依赖|go|
|cloud.google.com/go/compute|v1.19.3|间接依赖|go|
|golang.zx2c4.com/wireguard/wgctrl|v0.0.0-20211215182854-7a385b3431de|直接依赖|go|
|github.com/nxadm/tail|v1.4.8|间接依赖|go|
|go.opentelemetry.io/otel/exporters/prometheus|v0.33.0|直接依赖|go|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|go.opentelemetry.io/otel/sdk|v1.11.1|间接依赖|go|
|github.com/onsi/gomega|v1.18.1|直接依赖|go|
|github.com/cilium/ebpf|v0.10.0|直接依赖|go|
|github.com/mdlayher/genetlink|v1.1.0|间接依赖|go|
|github.com/srwiley/rasterx|v0.0.0-20200120212402-85cb7272f5e9|间接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230530153820-e85fd2cbaebc|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|github.com/okta/okta-sdk-golang/v2|v2.18.0|直接依赖|go|
|github.com/googleapis/gax-go/v2|v2.10.0|间接依赖|go|
|github.com/skratchdot/open-golang|v0.0.0-20200116055534-eef842397966|直接依赖|go|
|github.com/golang/protobuf|v1.5.3|直接依赖|go|
|golang.zx2c4.com/wintun|v0.0.0-20230126152724-0fa3db229ce2|间接依赖|go|
|github.com/josharian/native|v1.0.0|间接依赖|go|
|cloud.google.com/go/compute/metadata|v0.2.3|间接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|golang.org/x/image|v0.5.0|间接依赖|go|
|golang.org/x/exp|v0.0.0-20220518171630-0b5c67f07fdf|直接依赖|go|
|go.opentelemetry.io/otel/trace|v1.11.1|间接依赖|go|
|golang.org/x/mobile|v0.0.0-20190719004257-d2bd2a29d028|直接依赖|go|
|github.com/c-robinson/iplib|v1.0.3|直接依赖|go|
|github.com/golang/mock|v1.6.0|直接依赖|go|
|github.com/getlantern/hex|v0.0.0-20190417191902-c6586a6fe0b7|间接依赖|go|
|github.com/oxtoacart/bpool|v0.0.0-20190530202638-03653db5a59c|间接依赖|go|
|gopkg.in/check.v1|v1.0.0-20201130134442-10cb98267c6c|间接依赖|go|
|github.com/prometheus/common|v0.37.0|间接依赖|go|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|github.com/pion/ice/v2|v2.3.1|直接依赖|go|
|github.com/BurntSushi/toml|v1.2.1|间接依赖|go|
|golang.org/x/time|v0.0.0-20210723032227-1f47c861a9ac|间接依赖|go|
|github.com/coreos/go-iptables|v0.7.0|直接依赖|go|
|github.com/libp2p/go-netroute|v0.2.0|直接依赖|go|
|go.opencensus.io|v0.24.0|间接依赖|go|
|github.com/go-redis/redis/v8|v8.11.5|间接依赖|go|
|golang.org/x/oauth2|v0.8.0|直接依赖|go|
|github.com/spf13/cobra|v1.6.1|直接依赖|go|
|github.com/spf13/cast|v1.5.0|间接依赖|go|
|github.com/go-stack/stack|v1.8.0|间接依赖|go|
|github.com/mdlayher/socket|v0.4.0|直接依赖|go|
|github.com/mitchellh/hashstructure/v2|v2.0.2|直接依赖|go|
|gopkg.in/tomb.v2|v2.0.0-20161208151619-d5d1b5820637|间接依赖|go|
|google.golang.org/api|v0.126.0|直接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|go.opentelemetry.io/otel|v1.11.1|直接依赖|go|
|github.com/getlantern/systray|v1.2.1|直接依赖|go|
|github.com/pegasus-kv/thrift|v0.13.0|间接依赖|go|
|golang.org/x/sync|v0.2.0|直接依赖|go|
|github.com/mattn/go-sqlite3|v1.14.16|直接依赖|go|
|github.com/pion/dtls/v2|v2.2.6|间接依赖|go|
|github.com/google/s2a-go|v0.1.4|间接依赖|go|
|github.com/creack/pty|v1.1.18|直接依赖|go|
|github.com/prometheus/client_model|v0.3.0|间接依赖|go|
|github.com/go-ole/go-ole|v1.2.6|间接依赖|go|
|gopkg.in/natefinch/lumberjack.v2|v2.0.0|直接依赖|go|
|github.com/dgraph-io/ristretto|v0.1.1|间接依赖|go|
|github.com/mdlayher/netlink|v1.7.1|间接依赖|go|
|github.com/srwiley/oksvg|v0.0.0-20200311192757-870daf9aa564|间接依赖|go|
|github.com/google/uuid|v1.3.0|直接依赖|go|
|github.com/vishvananda/netlink|v1.1.0|直接依赖|go|
|github.com/golang-jwt/jwt|v3.2.2+incompatible|直接依赖|go|
|github.com/hashicorp/go-version|v1.6.0|直接依赖|go|
|github.com/dgryski/go-rendezvous|v0.0.0-20200823014737-9f7001d12a5f|间接依赖|go|
|github.com/go-gl/gl|v0.0.0-20210813123233-e4099ee2221f|间接依赖|go|
|github.com/bradfitz/gomemcache|v0.0.0-20220106215444-fb4bf637b56d|间接依赖|go|
|github.com/cenkalti/backoff/v4|v4.1.3|直接依赖|go|
|goauthentik.io/api/v3|v3.2023051.3|直接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|google.golang.org/protobuf|v1.30.0|直接依赖|go|
|golang.org/x/sys|v0.8.0|直接依赖|go|
|github.com/vishvananda/netns|v0.0.0-20211101163701-50045581ed74|间接依赖|go|
|github.com/getlantern/context|v0.0.0-20190109183933-c447772a6520|间接依赖|go|
|github.com/go-logr/logr|v1.2.3|间接依赖|go|
|github.com/yusufpapurcu/wmi|v1.2.3|直接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|间接依赖|go|
|golang.org/x/crypto|v0.9.0|直接依赖|go|
|github.com/goki/freetype|v0.0.0-20181231101311-fa8a33aabaff|间接依赖|go|
|github.com/fredbi/uri|v0.0.0-20181227131451-3dcfdacbaaf3|间接依赖|go|
|github.com/pion/transport/v2|v2.0.2|直接依赖|go|
|github.com/godbus/dbus/v5|v5.1.0|直接依赖|go|
|golang.org/x/term|v0.8.0|直接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/patrickmn/go-cache|v2.1.0+incompatible|直接依赖|go|
|honnef.co/go/tools|v0.2.2|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)