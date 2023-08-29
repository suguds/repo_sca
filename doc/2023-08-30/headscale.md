# juanfont/headscale安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696586933772644352.svg)](https://www.murphysec.com/console/report/1678242656545431552/1696586933772644352)

仓库描述：An open source, self-hosted implementation of the Tailscale control server

仓库地址：[https://github.com/juanfont/headscale](https://github.com/juanfont/headscale)

| star：14935 | watch：117 | fork：882 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-29 23:07:32 | 许可证：BSD-3-Clause |
| 最近检测时间：2023-08-30 02:13:45 | 组件总数：143 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|runc 安全漏洞|使用不正确的解析名称或索引|[MPS-2023-6887](https://www.oscs1024.com/hd/MPS-2023-6887)|CVE-2023-27561|高危|
|runc <1.1.5 AppArmor限制绕过漏洞|访问控制不当|[MPS-2023-8507](https://www.oscs1024.com/hd/MPS-2023-8507)|CVE-2023-28642|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/opencontainers/runc|v1.1.4|1.1.5|间接依赖|建议修复|C:0|H:2|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|37|Low|
|MIT|61|Low|
|Apache-2.0|38|Low|
|ISC|1|Low|
|CC-BY-SA-4.0|1|Medium|
|MPL-2.0|2|Low|
|BSD-2-Clause|4|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/rogpeppe/go-internal|v1.10.0|间接依赖|go|
|github.com/lithammer/fuzzysearch|v1.1.5|间接依赖|go|
|golang.org/x/time|v0.3.0|间接依赖|go|
|github.com/AlecAivazis/survey/v2|v2.3.6|直接依赖|go|
|github.com/containerd/console|v1.0.3|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|直接依赖|go|
|golang.zx2c4.com/wireguard/windows|v0.5.3|间接依赖|go|
|github.com/google/uuid|v1.3.0|间接依赖|go|
|github.com/opencontainers/image-spec|v1.1.0-rc3|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|直接依赖|go|
|atomicgo.dev/keyboard|v0.2.9|间接依赖|go|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|github.com/gookit/color|v1.5.3|间接依赖|go|
|go4.org/netipx|v0.0.0-20230303233057-f1b76eb4bb35|直接依赖|go|
|github.com/oauth2-proxy/mockoidc|v0.0.0-20220308204021-b9169deeb282|直接依赖|go|
|golang.org/x/term|v0.8.0|间接依赖|go|
|github.com/jsimonetti/rtnetlink|v1.3.2|间接依赖|go|
|github.com/philip-bui/grpc-zerolog|v1.0.1|直接依赖|go|
|github.com/cenkalti/backoff/v4|v4.2.0|直接依赖|go|
|google.golang.org/protobuf|v1.30.0|直接依赖|go|
|github.com/prometheus/common|v0.42.0|直接依赖|go|
|golang.org/x/sys|v0.8.1-0.20230609144347-5059a07aa46a|间接依赖|go|
|github.com/alexbrainman/sspi|v0.0.0-20210105120005-909beea2cc74|间接依赖|go|
|github.com/sirupsen/logrus|v1.9.0|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|github.com/glebarez/sqlite|v1.7.0|直接依赖|go|
|github.com/subosito/gotenv|v1.4.2|间接依赖|go|
|golang.org/x/crypto|v0.8.0|直接依赖|go|
|filippo.io/edwards25519|v1.0.0|间接依赖|go|
|github.com/josharian/native|v1.1.1-0.20230202152459-5c7d0dd6ab86|间接依赖|go|
|github.com/pterm/pterm|v0.12.58|直接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0|间接依赖|go|
|github.com/prometheus/client_model|v0.4.0|间接依赖|go|
|github.com/mgutz/ansi|v0.0.0-20200706080929-d51e80ef957d|间接依赖|go|
|gotest.tools/v3|v3.4.0|间接依赖|go|
|github.com/kballard/go-shellquote|v0.0.0-20180428030007-95032a82bc51|间接依赖|go|
|github.com/kr/text|v0.2.0|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|github.com/lib/pq|v1.10.7|间接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway/v2|v2.15.2|直接依赖|go|
|nhooyr.io/websocket|v1.8.7|间接依赖|go|
|github.com/mdlayher/socket|v0.4.1|间接依赖|go|
|github.com/spf13/viper|v1.15.0|直接依赖|go|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|github.com/google/pprof|v0.0.0-20221118152302-e6195bd50e26|间接依赖|go|
|github.com/xeipuuv/gojsonreference|v0.0.0-20180127040603-bd5ef7bd5415|间接依赖|go|
|github.com/tcnksm/go-latest|v0.0.0-20170313132115-e3007ae9052e|直接依赖|go|
|github.com/docker/cli|v23.0.5+incompatible|间接依赖|go|
|github.com/pkg/profile|v1.7.0|直接依赖|go|
|github.com/Nvveen/Gotty|v0.0.0-20120604004816-cd527374f1e5|间接依赖|go|
|tailscale.com|v1.44.0|直接依赖|go|
|github.com/mdlayher/netlink|v1.7.2|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|github.com/prometheus/procfs|v0.9.0|间接依赖|go|
|github.com/mitchellh/go-ps|v1.0.0|间接依赖|go|
|github.com/golang-jwt/jwt|v3.2.2+incompatible|间接依赖|go|
|modernc.org/mathutil|v1.5.0|间接依赖|go|
|github.com/docker/go-units|v0.5.0|间接依赖|go|
|github.com/remyoudompheng/bigfft|v0.0.0-20230129092748-24d4a6f8daec|间接依赖|go|
|github.com/spf13/jwalterweatherman|v1.1.0|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|github.com/pelletier/go-toml/v2|v2.0.7|间接依赖|go|
|github.com/dustin/go-humanize|v1.0.1|间接依赖|go|
|github.com/rs/zerolog|v1.29.0|直接依赖|go|
|github.com/patrickmn/go-cache|v2.1.0+incompatible|直接依赖|go|
|golang.org/x/oauth2|v0.7.0|直接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|gopkg.in/check.v1|v1.0.0-20201130134442-10cb98267c6c|直接依赖|go|
|github.com/xeipuuv/gojsonpointer|v0.0.0-20190905194746-02993c407bfb|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230403163135-c38d8f061ccd|直接依赖|go|
|github.com/opencontainers/runc|v1.1.4|间接依赖|go|
|golang.org/x/mod|v0.10.0|间接依赖|go|
|github.com/moby/term|v0.0.0-20221205130635-1aeaba878587|间接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|github.com/containerd/continuity|v0.3.0|间接依赖|go|
|gorm.io/gorm|v1.24.6|直接依赖|go|
|github.com/grpc-ecosystem/go-grpc-middleware|v1.4.0|直接依赖|go|
|github.com/docker/docker|v23.0.5+incompatible|间接依赖|go|
|github.com/jackc/pgx/v5|v5.3.0|间接依赖|go|
|github.com/jackc/pgpassfile|v1.0.0|间接依赖|go|
|golang.org/x/text|v0.9.0|间接依赖|go|
|golang.org/x/exp|v0.0.0-20230425010034-47ecfdc1ba53|间接依赖|go|
|github.com/google/go-github|v17.0.0+incompatible|间接依赖|go|
|github.com/stretchr/testify|v1.8.2|直接依赖|go|
|github.com/imdario/mergo|v0.3.15|间接依赖|go|
|github.com/docker/go-connections|v0.4.0|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|间接依赖|go|
|golang.org/x/sync|v0.2.0|直接依赖|go|
|github.com/gofrs/uuid/v5|v5.0.0|直接依赖|go|
|go4.org/mem|v0.0.0-20220726221520-4f986261bf13|间接依赖|go|
|gorm.io/driver/postgres|v1.4.8|直接依赖|go|
|github.com/google/shlex|v0.0.0-20191202100458-e7afc7fbc510|间接依赖|go|
|github.com/hashicorp/go-version|v1.6.0|间接依赖|go|
|github.com/gorilla/mux|v1.8.0|直接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.0|间接依赖|go|
|github.com/Azure/go-ansiterm|v0.0.0-20230124172434-306776ec8161|间接依赖|go|
|github.com/felixge/fgprof|v0.9.3|间接依赖|go|
|github.com/xo/terminfo|v0.0.0-20220910002029-abceb7e1c41e|间接依赖|go|
|github.com/coreos/go-oidc/v3|v3.5.0|直接依赖|go|
|google.golang.org/grpc|v1.54.0|直接依赖|go|
|github.com/deckarep/golang-set/v2|v2.3.0|直接依赖|go|
|github.com/puzpuzpuz/xsync/v2|v2.4.0|直接依赖|go|
|modernc.org/libc|v1.22.2|间接依赖|go|
|modernc.org/memory|v1.5.0|间接依赖|go|
|atomicgo.dev/cursor|v0.1.1|间接依赖|go|
|github.com/x448/float16|v0.8.4|间接依赖|go|
|github.com/go-jose/go-jose/v3|v3.0.0|间接依赖|go|
|github.com/spf13/afero|v1.9.5|间接依赖|go|
|github.com/tailscale/hujson|v0.0.0-20221223112325-20486734a56a|直接依赖|go|
|modernc.org/sqlite|v1.20.3|间接依赖|go|
|github.com/prometheus/client_golang|v1.15.1|直接依赖|go|
|golang.org/x/tools|v0.9.1|间接依赖|go|
|github.com/google/go-querystring|v1.1.0|间接依赖|go|
|golang.org/x/net|v0.10.0|直接依赖|go|
|github.com/samber/lo|v1.38.1|直接依赖|go|
|github.com/jinzhu/now|v1.1.5|间接依赖|go|
|github.com/jackc/pgservicefile|v0.0.0-20221227161230-091c0ba34f0a|间接依赖|go|
|github.com/ory/dockertest/v3|v3.9.1|直接依赖|go|
|github.com/kr/pretty|v0.3.1|间接依赖|go|
|gopkg.in/square/go-jose.v2|v2.6.0|间接依赖|go|
|github.com/hdevalence/ed25519consensus|v0.1.0|间接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|github.com/glebarez/go-sqlite|v1.20.3|间接依赖|go|
|github.com/jinzhu/inflection|v1.0.0|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|github.com/efekarakus/termcolor|v1.0.1|直接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|gopkg.in/ini.v1|v1.67.0|间接依赖|go|
|github.com/akutz/memconn|v0.1.0|间接依赖|go|
|github.com/Microsoft/go-winio|v0.6.1|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/fxamacker/cbor/v2|v2.4.0|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/xeipuuv/gojsonschema|v1.2.0|间接依赖|go|
|github.com/mattn/go-runewidth|v0.0.14|间接依赖|go|
|github.com/spf13/cobra|v1.7.0|直接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.18|间接依赖|go|
|github.com/magiconair/properties|v1.8.7|间接依赖|go|
|github.com/klauspost/compress|v1.16.5|直接依赖|go|
|github.com/spf13/cast|v1.5.0|间接依赖|go|
|github.com/rivo/uniseg|v0.4.4|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)