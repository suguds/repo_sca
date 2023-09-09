# ethereum-optimism/optimism安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700573008883400704.svg)](https://www.murphysec.com/console/report/1700573008812097536/1700573008883400704)

仓库描述：Optimism is Ethereum, scaled.

仓库地址：[https://github.com/ethereum-optimism/optimism](https://github.com/ethereum-optimism/optimism)

| star：4450 | watch：93 | fork：2383 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-09 23:47:22 | 许可证：MIT |
| 最近检测时间：2023-09-10 02:14:53 | 组件总数：313 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|btcd 安全漏洞|缓冲区溢出|[MPS-2022-63685](https://www.oscs1024.com/hd/MPS-2022-63685)|CVE-2022-44797|严重|
|Requests Proxy-Authorization 标头泄露漏洞|未授权敏感信息泄露|[MPS-hr61-tzey](https://www.oscs1024.com/hd/MPS-hr61-tzey)|CVE-2023-32681|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/btcsuite/btcd|v0.22.0-beta|0.23.2|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|requests|2.28.1|2.31.0|间接依赖|建议修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|131|Low|
|Apache-2.0|68|Low|
|ISC|13|Low|
|Unlicense|2|Low|
|BSD-3-Clause|73|Low|
|MPL-2.0|7|Low|
|BSD-2-Clause|17|Low|
|自定义许可证|4|Low|
|LGPL-3.0|4|Medium|
|GPL-3.0|3|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/fjl/memsize|v0.0.1|间接依赖|go|
|github.com/go-ole/go-ole|v1.2.1|间接依赖|go|
|github.com/tklauser/numcpus|v0.2.2|间接依赖|go|
|github.com/felixge/fgprof|v0.9.3|间接依赖|go|
|github.com/btcsuite/btcd/chaincfg/chainhash|v1.0.1|直接依赖|go|
|github.com/jbenet/go-temp-err-catcher|v0.1.0|间接依赖|go|
|gopkg.in/natefinch/npipe.v2|v2.0.0-20160621034901-c1b8fa8bdcce|间接依赖|go|
|github.com/alicebob/gopher-json|v0.0.0-20200520072559-a9ecdc9d1d3a|间接依赖|go|
|google.golang.org/grpc|v1.56.2|间接依赖|go|
|gopkg.in/alecthomas/kingpin.v2|v2.2.6|直接依赖|go|
|github.com/tklauser/go-sysconf|v0.3.10|间接依赖|go|
|github.com/dop251/goja|v0.0.0-20230122112309-96b1610dd4f7|间接依赖|go|
|github.com/status-im/keycard-go|v0.2.0|间接依赖|go|
|gopkg.in/natefinch/lumberjack.v2|v2.0.0|间接依赖|go|
|github.com/go-logr/logr|v0.4.0|间接依赖|go|
|github.com/alecthomas/template|v0.0.0-20190718012654-fb15b899a751|间接依赖|go|
|github.com/go-sourcemap/sourcemap|v2.1.3+incompatible|间接依赖|go|
|lukechampine.com/blake3|v1.1.7|间接依赖|go|
|github.com/multiformats/go-multiaddr-fmt|v0.1.0|间接依赖|go|
|github.com/getsentry/sentry-go|v0.18.0|间接依赖|go|
|github.com/StackExchange/wmi|v0.0.0-20180116203802-5d049714c4a6|间接依赖|go|
|github.com/russross/blackfriday/v2|v2.1.0|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/xrash/smetrics|v0.0.0-20201216005158-039620a65673|间接依赖|go|
|golang.org/x/text|v0.11.0|间接依赖|go|
|github.com/BurntSushi/toml|v1.3.2|直接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.1.0|间接依赖|go|
|github.com/gomodule/redigo|v1.8.8|间接依赖|go|
|github.com/influxdata/influxdb1-client|v0.0.0-20220302092344-a9ab5670611c|间接依赖|go|
|github.com/gballet/go-libpcsclite|v0.0.0-20190607065134-2772fd86a8ff|间接依赖|go|
|github.com/quic-go/quic-go|v0.33.0|间接依赖|go|
|google.golang.org/protobuf|v1.30.0|间接依赖|go|
|github.com/kr/pretty|v0.3.1|间接依赖|go|
|k8s.io/klog/v2|v2.8.0|间接依赖|go|
|github.com/google/gofuzz|v1.1.1-0.20200604201612-c04b05f3adfa|间接依赖|go|
|idna|3.4|间接依赖|pip|
|github.com/syndtr/goleveldb|v1.0.1-0.20220614013038-64ee5596c38a|间接依赖|go|
|k8s.io/apimachinery|v0.21.2|直接依赖|go|
|github.com/googleapis/enterprise-certificate-proxy|v0.2.5|间接依赖|go|
|github.com/gorilla/websocket|v1.5.0|直接依赖|go|
|golang.org/x/term|v0.8.0|间接依赖|go|
|github.com/onsi/gomega|v1.27.10|直接依赖|go|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|github.com/supranational/blst|v0.3.11|间接依赖|go|
|github.com/prometheus/client_golang|v1.16.0|直接依赖|go|
|github.com/bits-and-blooms/bitset|v1.7.0|间接依赖|go|
|github.com/allegro/bigcache|v1.2.1|间接依赖|go|
|golang.org/x/sync|v0.1.0|直接依赖|go|
|github.com/google/pprof|v0.0.0-20230405160723-4a4c7d95572b|间接依赖|go|
|github.com/decred/dcrd/crypto/blake256|v1.0.0|间接依赖|go|
|github.com/lib/pq|v1.10.9|间接依赖|go|
|github.com/alecthomas/units|v0.0.0-20190924025748-f65c72e2690d|间接依赖|go|
|github.com/multiformats/go-base32|v0.1.0|直接依赖|go|
|github.com/libp2p/go-reuseport|v0.2.0|间接依赖|go|
|github.com/mattn/go-runewidth|v0.0.14|间接依赖|go|
|github.com/golang/mock|v1.6.0|间接依赖|go|
|github.com/fatih/color|v1.7.0|间接依赖|go|
|charset-normalizer|2.1.1|间接依赖|pip|
|github.com/jinzhu/now|v1.1.5|间接依赖|go|
|Process||间接依赖|pip|
|github.com/raulk/go-watchdog|v1.3.0|间接依赖|go|
|github.com/rivo/uniseg|v0.4.3|间接依赖|go|
|nhooyr.io/websocket|v1.8.7|间接依赖|go|
|github.com/stretchr/testify|v1.8.4|直接依赖|go|
|github.com/influxdata/influxdb-client-go/v2|v2.4.0|间接依赖|go|
|k8s.io/api|v0.21.2|间接依赖|go|
|github.com/elastic/gosigar|v0.14.2|间接依赖|go|
|github.com/prometheus/common|v0.39.0|间接依赖|go|
|github.com/naoina/go-stringutil|v0.1.0|间接依赖|go|
|golang.org/x/net|v0.12.0|间接依赖|go|
|github.com/multiformats/go-multiaddr|v0.10.1|直接依赖|go|
|github.com/multiformats/go-multiaddr-dns|v0.3.1|直接依赖|go|
|wrapt|1.14.1|间接依赖|pip|
|golang.org/x/time|v0.3.0|直接依赖|go|
|github.com/jbenet/goprocess|v0.1.4|间接依赖|go|
|github.com/coreos/go-systemd/v22|v22.5.0|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/prometheus/client_golang|v1.14.0|直接依赖|go|
|golang.org/x/text|v0.9.0|间接依赖|go|
|PyNaCl|1.5.0|间接依赖|pip|
|golang.org/x/mod|v0.11.0|间接依赖|go|
|golang.org/x/crypto|v0.12.0|直接依赖|go|
|golang.org/x/sys|v0.1.0|间接依赖|go|
|github.com/libp2p/go-flow-metrics|v0.1.0|间接依赖|go|
|github.com/VictoriaMetrics/fastcache|v1.9.0|间接依赖|go|
|github.com/huin/goupnp|v1.0.3|间接依赖|go|
|github.com/holiman/bloomfilter/v2|v2.0.3|间接依赖|go|
|github.com/jackc/pgtype|v1.14.0|直接依赖|go|
|github.com/hashicorp/errwrap|v1.1.0|间接依赖|go|
|gorm.io/gorm|v1.25.4|直接依赖|go|
|github.com/libp2p/go-msgio|v0.3.0|间接依赖|go|
|github.com/mr-tron/base58|v1.2.0|间接依赖|go|
|github.com/onsi/ginkgo/v2|v2.11.0|间接依赖|go|
|cloud.google.com/go/compute/metadata|v0.2.3|间接依赖|go|
|github.com/karalabe/usb|v0.0.2|间接依赖|go|
|github.com/koron/go-ssdp|v0.0.4|间接依赖|go|
|github.com/prometheus/client_model|v0.3.0|间接依赖|go|
|github.com/ethereum-optimism/optimism|v0.0.0|直接依赖|go|
|github.com/deckarep/golang-set/v2|v2.1.0|间接依赖|go|
|github.com/libp2p/go-libp2p-pubsub|v0.9.3|直接依赖|go|
|github.com/cpuguy83/go-md2man/v2|v2.0.2|间接依赖|go|
|github.com/yuin/gopher-lua|v0.0.0-20210529063254-f4c35e4016d9|间接依赖|go|
|github.com/jackc/pgservicefile|v0.0.0-20221227161230-091c0ba34f0a|间接依赖|go|
|github.com/cockroachdb/pebble|v0.0.0-20230209160836-829675f94811|间接依赖|go|
|github.com/ethereum-optimism/go-ethereum-hdwallet|v0.1.3|直接依赖|go|
|github.com/docker/go-units|v0.5.0|间接依赖|go|
|github.com/opencontainers/runtime-spec|v1.0.2|间接依赖|go|
|github.com/googleapis/gax-go/v2|v2.12.0|间接依赖|go|
|github.com/hashicorp/golang-lru/v2|v2.0.2|直接依赖|go|
|github.com/shirou/gopsutil|v3.21.4-0.20210419000835-c7a38de76ee5+incompatible|间接依赖|go|
|pycparser|2.21|间接依赖|pip|
|github.com/deepmap/oapi-codegen|v1.8.2|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|github.com/quic-go/qtls-go1-20|v0.2.3|间接依赖|go|
|github.com/dlclark/regexp2|v1.7.0|间接依赖|go|
|github.com/gorilla/mux|v1.8.0|直接依赖|go|
|golang.org/x/oauth2|v0.10.0|间接依赖|go|
|cloud.google.com/go/compute|v1.20.1|间接依赖|go|
|cloud.google.com/go/iam|v1.1.0|间接依赖|go|
|github.com/quic-go/qpack|v0.4.0|间接依赖|go|
|github.com/mmcloughlin/addchain|v0.4.0|间接依赖|go|
|github.com/rs/cors|v1.8.2|直接依赖|go|
|github.com/hashicorp/golang-lru|v0.5.5-0.20210104140557-80c98217689d|直接依赖|go|
|github.com/olekukonko/tablewriter|v0.0.5|直接依赖|go|
|github.com/miekg/dns|v1.1.53|间接依赖|go|
|github.com/libp2p/go-buffer-pool|v0.1.0|间接依赖|go|
|github.com/google/gopacket|v1.1.19|间接依赖|go|
|github.com/klauspost/compress|v1.16.4|间接依赖|go|
|Deprecated|1.2.13|间接依赖|pip|
|github.com/golang-jwt/jwt/v4|v4.4.2|间接依赖|go|
|github.com/libp2p/go-nat|v0.1.0|间接依赖|go|
|github.com/prometheus/procfs|v0.9.0|间接依赖|go|
|golang.org/x/term|v0.11.0|直接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|直接依赖|go|
|github.com/mattn/go-isatty|v0.0.19|直接依赖|go|
|github.com/klauspost/compress|v1.15.15|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|直接依赖|go|
|github.com/ipfs/go-log/v2|v2.5.1|间接依赖|go|
|golang.org/x/sync|v0.3.0|直接依赖|go|
|google.golang.org/genproto/googleapis/api|v0.0.0-20230706204954-ccb25ca9f130|间接依赖|go|
|github.com/marten-seemann/tcp|v0.0.0-20210406111302-dfbc87cc63fd|间接依赖|go|
|github.com/google/s2a-go|v0.1.4|间接依赖|go|
|github.com/mitchellh/pointerstructure|v1.2.1|间接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|github.com/rivo/uniseg|v0.3.4|间接依赖|go|
|github.com/tklauser/go-sysconf|v0.3.5|间接依赖|go|
|go.uber.org/zap|v1.24.0|间接依赖|go|
|urllib3|1.26.13|间接依赖|pip|
|github.com/consensys/bavard|v0.1.13|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|github.com/jedisct1/go-minisign|v0.0.0-20190909160543-45766022959e|间接依赖|go|
|github.com/hashicorp/go-multierror|v1.1.1|直接依赖|go|
|github.com/libp2p/go-libp2p-asn-util|v0.3.0|间接依赖|go|
|github.com/btcsuite/btcd|v0.22.0-beta|间接依赖|go|
|github.com/multiformats/go-base36|v0.2.0|间接依赖|go|
|github.com/DataDog/zstd|v1.5.2|间接依赖|go|
|certifi|2023.7.22|间接依赖|pip|
|github.com/holiman/uint256|v1.2.2-0.20230321075855-87b91420868c|间接依赖|go|
|github.com/libp2p/go-yamux/v4|v4.0.0|间接依赖|go|
|github.com/opentracing/opentracing-go|v1.2.0|间接依赖|go|
|golang.org/x/sys|v0.10.0|间接依赖|go|
|github.com/multiformats/go-varint|v0.0.7|间接依赖|go|
|github.com/quic-go/qtls-go1-19|v0.3.3|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|github.com/quic-go/webtransport-go|v0.5.2|间接依赖|go|
|github.com/davidlazar/go-crypto|v0.0.0-20200604182044-b73af7476f6c|间接依赖|go|
|PyGithub|1.57|间接依赖|pip|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/stretchr/testify|v1.8.1|直接依赖|go|
|github.com/decred/dcrd/dcrec/secp256k1/v4|v4.0.1|间接依赖|go|
|github.com/mikioh/tcpopt|v0.0.0-20190314235656-172688c1accc|间接依赖|go|
|github.com/benbjohnson/clock|v1.3.0|间接依赖|go|
|sigs.k8s.io/yaml|v1.2.0|间接依赖|go|
|github.com/libp2p/go-libp2p|v0.27.8|直接依赖|go|
|github.com/cockroachdb/redact|v1.1.3|间接依赖|go|
|golang.org/x/net|v0.10.0|间接依赖|go|
|github.com/ybbus/jsonrpc|v2.1.2+incompatible|直接依赖|go|
|github.com/multiformats/go-multibase|v0.2.0|间接依赖|go|
|github.com/influxdata/line-protocol|v0.0.0-20210311194329-9aa0e372d097|间接依赖|go|
|github.com/go-stack/stack|v1.8.0|间接依赖|go|
|PyJWT|2.6.0|间接依赖|pip|
|golang.org/x/crypto|v0.11.0|间接依赖|go|
|github.com/sirupsen/logrus|v1.7.0|直接依赖|go|
|github.com/mattn/go-runewidth|v0.0.9|间接依赖|go|
|github.com/btcsuite/btcd/btcec/v2|v2.2.0|间接依赖|go|
|github.com/hashicorp/go-bexpr|v0.1.11|间接依赖|go|
|github.com/go-task/slim-sprig|v0.0.0-20230315185526-52ccab3ef572|间接依赖|go|
|github.com/ethereum/go-ethereum|v1.12.0|直接依赖|go|
|github.com/google/uuid|v1.3.1|直接依赖|go|
|requests|2.28.1|间接依赖|pip|
|golang.org/x/text|v0.8.0|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|github.com/go-chi/chi/v5|v5.0.10|直接依赖|go|
|github.com/minio/sha256-simd|v1.0.0|间接依赖|go|
|github.com/kr/text|v0.2.0|间接依赖|go|
|github.com/jackc/pgpassfile|v1.0.0|间接依赖|go|
|google.golang.org/protobuf|v1.28.1|间接依赖|go|
|github.com/containerd/cgroups|v1.1.0|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/jackpal/go-nat-pmp|v1.0.2|间接依赖|go|
|github.com/tyler-smith/go-bip39|v1.1.0|间接依赖|go|
|github.com/mikioh/tcpinfo|v0.0.0-20190314235526-30a79bb1804b|间接依赖|go|
|github.com/graph-gophers/graphql-go|v1.3.0|间接依赖|go|
|github.com/btcsuite/btcd|v0.23.3|直接依赖|go|
|cffi|1.15.1|间接依赖|pip|
|github.com/francoispqt/gojay|v1.2.13|间接依赖|go|
|golang.org/x/sys|v0.7.0|间接依赖|go|
|github.com/BurntSushi/toml|v1.2.0|直接依赖|go|
|github.com/crate-crypto/go-ipa|v0.0.0-20220523130400-f11357ae11c7|间接依赖|go|
|github.com/btcsuite/btclog|v0.0.0-20170628155309-84c8d2346e9f|间接依赖|go|
|github.com/gballet/go-verkle|v0.0.0-20220902153445-097bd83b7732|间接依赖|go|
|click|8.1.3|间接依赖|pip|
|github.com/alicebob/miniredis|v2.5.0+incompatible|直接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/crate-crypto/go-kzg-4844|v0.2.0|间接依赖|go|
|golang.org/x/exp|v0.0.0-20230206171751-46f607a40771|间接依赖|go|
|github.com/flynn/noise|v1.0.0|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.1.1|间接依赖|go|
|k8s.io/client-go|v0.21.2|直接依赖|go|
|github.com/huin/goupnp|v1.1.0|间接依赖|go|
|github.com/go-redis/redis/v8|v8.11.4|直接依赖|go|
|github.com/ethereum/go-ethereum|v1.10.26|直接依赖|go|
|github.com/rivo/uniseg|v0.2.0|间接依赖|go|
|github.com/libp2p/go-cidranger|v1.1.0|间接依赖|go|
|go.opencensus.io|v0.24.0|间接依赖|go|
|github.com/golang/snappy|v0.0.4|间接依赖|go|
|github.com/urfave/cli|v1.22.9|间接依赖|go|
|golang.org/x/exp|v0.0.0-20230626212559-97b1e661b5df|直接依赖|go|
|golang.org/x/crypto|v0.1.0|间接依赖|go|
|github.com/ethereum-optimism/optimism/op-service|v0.10.14|直接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/prometheus/common|v0.42.0|间接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.0|间接依赖|go|
|golang.org/x/sys|v0.11.0|间接依赖|go|
|github.com/ipfs/go-ds-leveldb|v0.5.0|直接依赖|go|
|cloud.google.com/go/kms|v1.12.1|直接依赖|go|
|github.com/rogpeppe/go-internal|v1.9.0|间接依赖|go|
|github.com/jackc/pgx/v5|v5.4.3|直接依赖|go|
|github.com/ipfs/go-datastore|v0.6.0|直接依赖|go|
|github.com/go-ole/go-ole|v1.2.6|间接依赖|go|
|github.com/consensys/gnark-crypto|v0.10.0|间接依赖|go|
|github.com/urfave/cli/v2|v2.25.7|直接依赖|go|
|github.com/libp2p/go-netroute|v0.2.1|间接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|github.com/yusufpapurcu/wmi|v1.2.2|间接依赖|go|
|rsc.io/tmplfunc|v0.0.3|间接依赖|go|
|github.com/docker/docker|v20.10.24+incompatible|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/tklauser/numcpus|v0.4.0|间接依赖|go|
|google.golang.org/api|v0.132.0|间接依赖|go|
|github.com/syndtr/goleveldb|v1.0.1-0.20210819022825-2ae1ddf74ef7|直接依赖|go|
|github.com/rs/cors|v1.9.0|直接依赖|go|
|gorm.io/driver/postgres|v1.5.2|直接依赖|go|
|golang.org/x/text|v0.12.0|间接依赖|go|
|go.uber.org/fx|v1.19.2|间接依赖|go|
|github.com/googleapis/gnostic|v0.4.1|间接依赖|go|
|github.com/jackc/pgio|v1.0.0|间接依赖|go|
|go.uber.org/atomic|v1.10.0|间接依赖|go|
|golang.org/x/oauth2|v0.3.0|间接依赖|go|
|google.golang.org/protobuf|v1.31.0|间接依赖|go|
|github.com/dgryski/go-rendezvous|v0.0.0-20200823014737-9f7001d12a5f|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/mattn/go-runewidth|v0.0.13|间接依赖|go|
|github.com/VictoriaMetrics/fastcache|v1.6.0|间接依赖|go|
|github.com/ipfs/go-cid|v0.4.1|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/libp2p/go-libp2p-testing|v0.12.0|直接依赖|go|
|github.com/peterh/liner|v1.1.1-0.20190123174540-a2c9a5303de7|间接依赖|go|
|github.com/spaolacci/murmur3|v1.1.0|间接依赖|go|
|github.com/pkg/profile|v1.7.0|直接依赖|go|
|github.com/emirpasic/gods|v1.18.1|直接依赖|go|
|github.com/jinzhu/inflection|v1.0.0|间接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230711160842-782d3b101e98|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230706204954-ccb25ca9f130|直接依赖|go|
|github.com/prometheus/procfs|v0.10.1|间接依赖|go|
|github.com/btcsuite/btcd/btcutil|v1.1.0|间接依赖|go|
|github.com/go-stack/stack|v1.8.1|间接依赖|go|
|golang.org/x/sys|v0.9.0|间接依赖|go|
|k8s.io/utils|v0.0.0-20201110183641-67b214c5f920|间接依赖|go|
|github.com/pbnjay/memory|v0.0.0-20210728143218-7b4eea64cf58|间接依赖|go|
|github.com/naoina/toml|v0.1.2-0.20170918210437-9fafd6967416|间接依赖|go|
|github.com/decred/dcrd/dcrec/secp256k1/v4|v4.1.0|直接依赖|go|
|github.com/holiman/uint256|v1.2.3|直接依赖|go|
|github.com/google/gofuzz|v1.2.1-0.20220503160820-4a35382e8fc8|直接依赖|go|
|github.com/golang/protobuf|v1.5.2|间接依赖|go|
|github.com/shirou/gopsutil|v3.21.11+incompatible|间接依赖|go|
|github.com/cockroachdb/logtags|v0.0.0-20230118201751-21c54148d20b|间接依赖|go|
|github.com/stretchr/objx|v0.5.0|间接依赖|go|
|github.com/godbus/dbus/v5|v5.1.0|间接依赖|go|
|go.uber.org/multierr|v1.11.0|间接依赖|go|
|github.com/tklauser/numcpus|v0.5.0|间接依赖|go|
|github.com/onsi/gomega|v1.16.0|间接依赖|go|
|golang.org/x/tools|v0.9.3|间接依赖|go|
|github.com/google/uuid|v1.3.0|间接依赖|go|
|github.com/klauspost/cpuid/v2|v2.2.4|间接依赖|go|
|github.com/ethereum-optimism/superchain-registry/superchain|v0.0.0-20230817174831-5d3ca1966435|直接依赖|go|
|github.com/ethereum/c-kzg-4844|v0.2.0|间接依赖|go|
|github.com/multiformats/go-multihash|v0.2.1|间接依赖|go|
|github.com/gofrs/flock|v0.8.1|间接依赖|go|
|github.com/multiformats/go-multicodec|v0.8.1|间接依赖|go|
|github.com/prometheus/tsdb|v0.7.1|间接依赖|go|
|go.uber.org/dig|v1.16.1|间接依赖|go|
|Queue||间接依赖|pip|
|github.com/cockroachdb/errors|v1.9.1|间接依赖|go|
|github.com/ethereum/go-ethereum|v1.12.1|直接依赖|go|
|github.com/go-chi/docgen|v1.2.0|直接依赖|go|
|github.com/gballet/go-libpcsclite|v0.0.0-20191108122812-4678299bea08|间接依赖|go|
|github.com/golang/snappy|v0.0.5-0.20220116011046-fa5810519dcb|直接依赖|go|
|github.com/libp2p/go-mplex|v0.7.0|间接依赖|go|
|github.com/VictoriaMetrics/fastcache|v1.10.0|间接依赖|go|
|github.com/ethereum-optimism/optimism/op-signer|v0.1.1|直接依赖|go|
|github.com/multiformats/go-multistream|v0.4.1|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)