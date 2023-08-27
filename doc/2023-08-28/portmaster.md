# safing/portmaster安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695864523771506688.svg)](https://www.murphysec.com/console/report/1695864522714542080/1695864523771506688)

仓库描述：🏔 Love Freedom - ❌ Block Mass Surveillance

仓库地址：[https://github.com/safing/portmaster](https://github.com/safing/portmaster)

| star：7313 | watch：64 | fork：212 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-24 15:57:03 | 许可证：AGPL-3.0 |
| 最近检测时间：2023-08-28 02:23:25 | 组件总数：91 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|go.uuid 不安全的随机性漏洞|使用具有密码学弱点缺陷的PRNG|[MPS-2021-7854](https://www.oscs1024.com/hd/MPS-2021-7854)|CVE-2021-3538|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/satori/go.uuid|v1.2.0||间接依赖|建议修复|C:1|H:0|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|41|Low|
|Apache-2.0|11|Low|
|BSD-3-Clause|25|Low|
|ISC|3|Low|
|BSD-2-Clause|6|Low|
|GPL-3.0|5|Medium|
|MPL-2.0|3|Low|
|GPL-3.0-or-later|2|Low|
|AGPL-3.0|2|High|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/aead/ecdh|v0.2.0|间接依赖|go|
|github.com/yusufpapurcu/wmi|v1.2.3|间接依赖|go|
|gvisor.dev/gvisor|v0.0.0-20220817001344-846276b3dbc5|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|golang.org/x/sync|v0.3.0|直接依赖|go|
|modernc.org/sqlite|v1.25.0|间接依赖|go|
|zombiezen.com/go/sqlite|v0.13.1|直接依赖|go|
|github.com/armon/go-radix|v1.0.0|间接依赖|go|
|github.com/gorilla/mux|v1.8.0|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|github.com/valyala/histogram|v1.2.0|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.19|间接依赖|go|
|github.com/gorilla/websocket|v1.5.0|间接依赖|go|
|github.com/safing/portbase|v0.17.2|直接依赖|go|
|github.com/hashicorp/errwrap|v1.1.0|间接依赖|go|
|github.com/tidwall/gjson|v1.16.0|间接依赖|go|
|github.com/oschwald/maxminddb-golang|v1.12.0|直接依赖|go|
|github.com/dustin/go-humanize|v1.0.1|间接依赖|go|
|github.com/spf13/cobra|v1.7.0|直接依赖|go|
|github.com/miekg/dns|v1.1.55|直接依赖|go|
|golang.org/x/time|v0.3.0|间接依赖|go|
|github.com/tidwall/pretty|v1.2.1|间接依赖|go|
|github.com/VictoriaMetrics/metrics|v1.24.0|间接依赖|go|
|github.com/remyoudompheng/bigfft|v0.0.0-20230129092748-24d4a6f8daec|间接依赖|go|
|github.com/tidwall/match|v1.1.1|间接依赖|go|
|github.com/mitchellh/reflectwalk|v1.0.2|间接依赖|go|
|modernc.org/memory|v1.7.0|间接依赖|go|
|github.com/alessio/shellescape|v1.4.2|间接依赖|go|
|github.com/tidwall/sjson|v1.2.5|间接依赖|go|
|modernc.org/libc|v1.24.1|间接依赖|go|
|golang.org/x/tools|v0.12.1-0.20230815132531-74c255bcf846|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|间接依赖|go|
|github.com/mr-tron/base58|v1.2.0|间接依赖|go|
|github.com/shirou/gopsutil|v3.21.11+incompatible|直接依赖|go|
|golang.org/x/crypto|v0.12.0|间接依赖|go|
|github.com/vmihailenco/msgpack/v5|v5.3.5|间接依赖|go|
|github.com/florianl/go-conntrack|v0.4.0|直接依赖|go|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|github.com/mdlayher/netlink|v1.7.2|间接依赖|go|
|github.com/ghodss/yaml|v1.0.0|直接依赖|go|
|github.com/stretchr/testify|v1.8.4|直接依赖|go|
|github.com/google/shlex|v0.0.0-20191202100458-e7afc7fbc510|直接依赖|go|
|github.com/fxamacker/cbor|v1.5.1|间接依赖|go|
|github.com/coreos/go-iptables|v0.7.0|直接依赖|go|
|github.com/rot256/pblind|v0.0.0-20230622102829-4dc2c6e4b857|间接依赖|go|
|golang.org/x/exp|v0.0.0-20230817173708-d852ddb80c63|直接依赖|go|
|github.com/fxamacker/cbor/v2|v2.5.0|间接依赖|go|
|github.com/bluele/gcache|v0.0.2|间接依赖|go|
|github.com/umahmood/haversine|v0.0.0-20151105152445-808ab04add26|直接依赖|go|
|modernc.org/mathutil|v1.6.0|间接依赖|go|
|github.com/spkg/zipfs|v0.7.1|直接依赖|go|
|github.com/google/btree|v1.1.2|间接依赖|go|
|github.com/agext/levenshtein|v1.2.3|直接依赖|go|
|github.com/google/uuid|v1.3.1|间接依赖|go|
|go.etcd.io/bbolt|v1.3.7|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/hashicorp/go-version|v1.6.0|直接依赖|go|
|golang.org/x/sys|v0.11.0|直接依赖|go|
|github.com/danieljoos/wincred|v1.2.0|间接依赖|go|
|github.com/tklauser/go-sysconf|v0.3.12|间接依赖|go|
|github.com/mitchellh/copystructure|v1.2.0|间接依赖|go|
|github.com/tannerryan/ring|v1.1.2|直接依赖|go|
|github.com/tklauser/numcpus|v0.6.1|间接依赖|go|
|github.com/satori/go.uuid|v1.2.0|间接依赖|go|
|github.com/awalterschulze/gographviz|v2.0.3+incompatible|间接依赖|go|
|github.com/vmihailenco/tagparser/v2|v2.0.0|间接依赖|go|
|github.com/seehuhn/sha256d|v1.0.0|间接依赖|go|
|github.com/x448/float16|v0.8.4|间接依赖|go|
|github.com/hashicorp/go-multierror|v1.1.1|直接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/gofrs/uuid|v4.4.0+incompatible|间接依赖|go|
|github.com/godbus/dbus/v5|v5.1.0|直接依赖|go|
|github.com/safing/spn|v0.6.16|直接依赖|go|
|github.com/florianl/go-nfqueue|v1.3.1|直接依赖|go|
|github.com/safing/jess|v0.3.1|直接依赖|go|
|github.com/valyala/fastrand|v1.1.0|间接依赖|go|
|github.com/zalando/go-keyring|v0.2.3|间接依赖|go|
|github.com/seehuhn/fortuna|v1.0.1|间接依赖|go|
|golang.org/x/net|v0.14.0|直接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/jackc/puddle/v2|v2.2.1|直接依赖|go|
|github.com/tevino/abool|v1.2.0|直接依赖|go|
|github.com/google/gopacket|v1.1.19|直接依赖|go|
|github.com/cilium/ebpf|v0.11.0|直接依赖|go|
|github.com/josharian/native|v1.1.0|间接依赖|go|
|github.com/mdlayher/socket|v0.4.1|间接依赖|go|
|github.com/safing/portmaster-android/go|v0.0.0-20230605085256-6abf4c495626|直接依赖|go|
|github.com/go-ole/go-ole|v1.3.0|间接依赖|go|
|golang.org/x/mod|v0.12.0|间接依赖|go|
|github.com/aead/serpent|v0.0.0-20160714141033-fba169763ea6|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)