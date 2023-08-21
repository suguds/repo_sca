# go-gost/gost安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1693687843070046208.svg)](https://www.murphysec.com/console/report/1693687842935828480/1693687843070046208)

仓库描述：GO Simple Tunnel - a simple tunnel written in golang

仓库地址：[https://github.com/go-gost/gost](https://github.com/go-gost/gost)

| star：1682 | watch：24 | fork：221 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-06-13 22:51:45 | 许可证：MIT |
| 最近检测时间：2023-08-22 02:13:47 | 组件总数：109 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Gin 安全漏洞|下载代码缺少完整性检查|[MPS-2023-9711](https://www.oscs1024.com/hd/MPS-2023-9711)|CVE-2023-29401|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/gin-gonic/gin|v1.9.0|1.9.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|26|Low|
|BSD-3-Clause|24|Low|
|MIT|56|Low|
|BSD-2-Clause|4|Low|
|MPL-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/chenzhuoyu/base64x|v0.0.0-20221115062448-fe3a3abad311|间接依赖|go|
|github.com/google/uuid|v1.3.0|间接依赖|go|
|github.com/golang/protobuf|v1.5.2|间接依赖|go|
|github.com/spf13/viper|v1.14.0|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/quic-go/qtls-go1-20|v0.1.0|间接依赖|go|
|github.com/prometheus/client_model|v0.3.0|间接依赖|go|
|github.com/pion/dtls/v2|v2.2.6|间接依赖|go|
|github.com/pelletier/go-toml|v1.9.5|间接依赖|go|
|github.com/quic-go/qpack|v0.4.0|间接依赖|go|
|github.com/rs/xid|v1.3.0|间接依赖|go|
|github.com/gorilla/websocket|v1.5.0|间接依赖|go|
|github.com/ugorji/go/codec|v1.2.9|间接依赖|go|
|github.com/go-gost/plugin|v0.0.0-20230418123101-d221a4ec9a98|间接依赖|go|
|github.com/quic-go/quic-go|v0.32.0|间接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.1|间接依赖|go|
|github.com/google/gopacket|v1.1.19|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/gin-contrib/sse|v0.1.0|间接依赖|go|
|github.com/quic-go/qtls-go1-18|v0.2.0|间接依赖|go|
|golang.org/x/time|v0.3.0|间接依赖|go|
|github.com/tjfoc/gmsm|v1.3.2|间接依赖|go|
|golang.org/x/tools|v0.6.0|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|github.com/pelletier/go-toml/v2|v2.0.6|间接依赖|go|
|golang.org/x/mod|v0.8.0|间接依赖|go|
|golang.org/x/crypto|v0.6.0|间接依赖|go|
|github.com/xtaci/smux|v1.5.16|间接依赖|go|
|github.com/prometheus/client_golang|v1.14.0|间接依赖|go|
|github.com/riobard/go-bloom|v0.0.0-20200614022211-cdc8013cb5b3|间接依赖|go|
|github.com/aead/chacha20|v0.0.0-20180709150244-8b13a72661da|间接依赖|go|
|github.com/dgryski/go-rendezvous|v0.0.0-20200823014737-9f7001d12a5f|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|间接依赖|go|
|github.com/coreos/go-iptables|v0.5.0|间接依赖|go|
|github.com/pion/transport/v2|v2.0.2|间接依赖|go|
|github.com/spf13/afero|v1.9.3|间接依赖|go|
|golang.org/x/text|v0.8.0|间接依赖|go|
|github.com/gin-gonic/gin|v1.9.0|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|github.com/go-task/slim-sprig|v0.0.0-20210107165309-348f09dbbbc0|间接依赖|go|
|github.com/alecthomas/units|v0.0.0-20211218093645-b94a6e3cc137|间接依赖|go|
|github.com/pion/udp/v2|v2.0.1|间接依赖|go|
|github.com/onsi/ginkgo/v2|v2.6.1|间接依赖|go|
|github.com/go-gost/x|v0.0.0-20230521074751-46db8480faa9|直接依赖|go|
|github.com/yl2chen/cidranger|v1.0.2|间接依赖|go|
|golang.zx2c4.com/wintun|v0.0.0-20211104114900-415007cec224|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230110181048-76db0878b65f|间接依赖|go|
|github.com/gin-contrib/cors|v1.3.1|间接依赖|go|
|github.com/templexxx/cpu|v0.0.7|间接依赖|go|
|github.com/spf13/jwalterweatherman|v1.1.0|间接依赖|go|
|github.com/golang/snappy|v0.0.4|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/patrickmn/go-cache|v2.1.0+incompatible|间接依赖|go|
|golang.org/x/sys|v0.6.0|间接依赖|go|
|gopkg.in/natefinch/lumberjack.v2|v2.0.0|直接依赖|go|
|github.com/shadowsocks/go-shadowsocks2|v0.1.5|间接依赖|go|
|golang.org/x/net|v0.8.0|间接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|github.com/gobwas/glob|v0.2.3|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/go-playground/universal-translator|v0.18.1|间接依赖|go|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|github.com/go-gost/gosocks4|v0.0.1|间接依赖|go|
|golang.org/x/arch|v0.0.0-20210923205945-b76863e36670|间接依赖|go|
|github.com/goccy/go-json|v0.10.0|间接依赖|go|
|google.golang.org/protobuf|v1.30.0|间接依赖|go|
|github.com/mmcloughlin/avo|v0.0.0-20200803215136-443f81d77104|间接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/pires/go-proxyproto|v0.6.2|间接依赖|go|
|github.com/klauspost/reedsolomon|v1.9.9|间接依赖|go|
|github.com/asaskevich/govalidator|v0.0.0-20210307081110-f21760c49a8d|间接依赖|go|
|github.com/songgao/water|v0.0.0-20200317203138-2b4b6d7c09d8|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.17|间接依赖|go|
|golang.org/x/exp|v0.0.0-20221217163422-3c43f8badb15|间接依赖|go|
|github.com/quic-go/qtls-go1-19|v0.2.0|间接依赖|go|
|github.com/judwhite/go-svc|v1.2.1|直接依赖|go|
|github.com/klauspost/cpuid/v2|v2.0.9|间接依赖|go|
|github.com/go-gost/relay|v0.4.0|间接依赖|go|
|github.com/magiconair/properties|v1.8.7|间接依赖|go|
|github.com/leodido/go-urn|v1.2.1|间接依赖|go|
|github.com/miekg/dns|v1.1.50|间接依赖|go|
|github.com/vishvananda/netlink|v1.1.0|间接依赖|go|
|golang.zx2c4.com/wireguard|v0.0.0-20220703234212-c31a7b1ab478|间接依赖|go|
|github.com/subosito/gotenv|v1.4.1|间接依赖|go|
|github.com/twitchyliquid64/golang-asm|v0.15.1|间接依赖|go|
|github.com/bytedance/sonic|v1.8.0|间接依赖|go|
|github.com/sirupsen/logrus|v1.8.1|间接依赖|go|
|github.com/go-redis/redis/v8|v8.11.5|间接依赖|go|
|github.com/shadowsocks/shadowsocks-go|v0.0.0-20200409064450-3e585ff90601|间接依赖|go|
|github.com/go-playground/locales|v0.14.1|间接依赖|go|
|github.com/klauspost/cpuid|v1.3.1|间接依赖|go|
|github.com/vishvananda/netns|v0.0.0-20191106174202-0a2b9b5464df|间接依赖|go|
|github.com/spf13/cast|v1.5.0|间接依赖|go|
|github.com/prometheus/procfs|v0.8.0|间接依赖|go|
|github.com/templexxx/xorsimd|v0.4.1|间接依赖|go|
|github.com/pion/logging|v0.2.2|间接依赖|go|
|github.com/xtaci/tcpraw|v1.2.25|间接依赖|go|
|github.com/xtaci/kcp-go/v5|v5.6.1|间接依赖|go|
|github.com/go-playground/validator/v10|v10.11.2|间接依赖|go|
|github.com/go-gost/tls-dissector|v0.0.2-0.20220408131628-aac992c27451|间接依赖|go|
|gopkg.in/ini.v1|v1.67.0|间接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.0|间接依赖|go|
|github.com/go-gost/gosocks5|v0.3.1-0.20211109033403-d894d75b7f09|间接依赖|go|
|google.golang.org/grpc|v1.54.0|间接依赖|go|
|github.com/prometheus/common|v0.37.0|间接依赖|go|
|github.com/google/pprof|v0.0.0-20221219190121-3cb0bae90811|间接依赖|go|
|github.com/golang/mock|v1.6.0|间接依赖|go|
|github.com/go-gost/core|v0.0.0-20230418124644-a2115a3d3876|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)