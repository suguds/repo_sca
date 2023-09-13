# etcd-io/etcd安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1702023144936177664.svg)](https://www.murphysec.com/console/report/1695498726440525824/1702023144936177664)

仓库描述：Distributed reliable key-value store for the most critical data of a distributed system

仓库地址：[https://github.com/etcd-io/etcd](https://github.com/etcd-io/etcd)

| star：44459 | watch：1340 | fork：9480 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-13 22:10:34 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-14 02:16:00 | 组件总数：153 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|numpy|1.24.3||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|57|Low|
|BSD-3-Clause|32|Low|
|BSD-2-Clause|7|Low|
|Apache-2.0|61|Low|
|自定义许可证|1|Low|
|ISC|2|Low|
|MPL-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/anishathalye/porcupine|v0.1.4|直接依赖|go|
|github.com/goccy/go-yaml|v1.11.0|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.5.4|间接依赖|go|
|github.com/weppos/publicsuffix-go|v0.15.1-0.20220329081811-9a40b608a236|间接依赖|go|
|github.com/elliotchance/orderedmap|v1.5.0|间接依赖|go|
|github.com/gorilla/websocket|v1.4.2|间接依赖|go|
|github.com/rivo/uniseg|v0.2.0|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.17|间接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|github.com/mgechev/dots|v0.0.0-20210922191527-e955255bf517|间接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway|v1.16.0|直接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace|v1.17.0|间接依赖|go|
|github.com/coreos/go-semver|v0.3.1|直接依赖|go|
|matplotlib|3.7.1|间接依赖|pip|
|github.com/coreos/license-bill-of-materials|v0.0.0-20190913234955-13baff47494e|直接依赖|go|
|github.com/bgentry/speakeasy|v0.1.0|直接依赖|go|
|go.opentelemetry.io/otel/sdk|v1.17.0|直接依赖|go|
|github.com/google/shlex|v0.0.0-20191202100458-e7afc7fbc510|间接依赖|go|
|go.etcd.io/bbolt|v1.3.7|直接依赖|go|
|github.com/mikefarah/yq/v4|v4.35.1|直接依赖|go|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|go.etcd.io/raft/v3|v3.0.0-20221201111702-eaa6808e1f7a|直接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|honnef.co/go/tools|v0.4.5|直接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230822172742-b8732ec3820d|间接依赖|go|
|github.com/a8m/envsubst|v1.4.2|间接依赖|go|
|github.com/goccy/go-json|v0.10.2|间接依赖|go|
|github.com/stretchr/testify|v1.8.4|直接依赖|go|
|github.com/VividCortex/ewma|v1.2.0|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace/otlptracegrpc|v1.17.0|直接依赖|go|
|gopkg.in/natefinch/lumberjack.v2|v2.2.1|直接依赖|go|
|github.com/mdempsky/unconvert|v0.0.0-20200228143138-95ecdbfc0b5f|直接依赖|go|
|github.com/golang/glog|v0.0.0-20160126235308-23def4e6c14b|间接依赖|go|
|go.etcd.io/protodoc|v0.0.0-20180829002748-484ab544e116|直接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.0|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.19|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|github.com/kisielk/sqlstruct|v0.0.0-20201105191214-5f3e10d3ab46|间接依赖|go|
|github.com/mgechev/revive|v1.3.3|直接依赖|go|
|gotest.tools/v3|v3.5.0|直接依赖|go|
|github.com/alexfalkowski/gocovmerge|v1.2.0|直接依赖|go|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|github.com/prometheus/client_model|v0.4.0|直接依赖|go|
|golang.org/x/time|v0.3.0|直接依赖|go|
|github.com/dnephin/pflag|v1.0.7|间接依赖|go|
|github.com/jinzhu/copier|v0.3.5|间接依赖|go|
|go.etcd.io/etcd/tests/v3|v3.6.0-alpha.0|直接依赖|go|
|go.etcd.io/etcd/server/v3|v3.6.0-alpha.0|直接依赖|go|
|go.etcd.io/etcd/pkg/v3|v3.6.0-alpha.0|直接依赖|go|
|google.golang.org/grpc|v1.58.0|直接依赖|go|
|golang.org/x/crypto|v0.13.0|直接依赖|go|
|golang.org/x/text|v0.13.0|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|直接依赖|go|
|github.com/benbjohnson/clock|v1.3.0|间接依赖|go|
|golang.org/x/mod|v0.12.0|间接依赖|go|
|github.com/alecthomas/participle/v2|v2.0.0|间接依赖|go|
|golang.org/x/exp/typeparams|v0.0.0-20221208152030-732eee02a75a|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|go.opentelemetry.io/proto/otlp|v1.0.0|直接依赖|go|
|go.etcd.io/etcd/etcdutl/v3|v3.6.0-alpha.0|直接依赖|go|
|golang.org/x/sys|v0.12.0|直接依赖|go|
|golang.org/x/xerrors|v0.0.0-20220609144429-65e65417b02f|间接依赖|go|
|github.com/gordonklaus/ineffassign|v0.0.0-20210914165742-4cc7213b9bc8|直接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|github.com/google/btree|v1.1.2|直接依赖|go|
|github.com/olekukonko/tablewriter|v0.0.5|直接依赖|go|
|go.opentelemetry.io/otel/trace|v1.17.0|直接依赖|go|
|github.com/tmc/grpc-websocket-proxy|v0.0.0-20201229170055-e5319fda7802|直接依赖|go|
|github.com/cheggaaa/pb/v3|v3.1.4|直接依赖|go|
|github.com/mattn/go-sqlite3|v1.14.15|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20220706185917-7780775163c4|间接依赖|go|
|go.etcd.io/gofail|v0.1.0|直接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway/v2|v2.17.1|间接依赖|go|
|github.com/RageCage64/multilinediff|v0.2.0|间接依赖|go|
|golang.org/x/sync|v0.3.0|直接依赖|go|
|github.com/go-logr/logr|v1.2.4|间接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|github.com/zmap/zlint/v3|v3.4.1|间接依赖|go|
|github.com/coreos/go-systemd/v22|v22.5.0|直接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/prometheus/common|v0.43.0|直接依赖|go|
|pandas|2.0.1|间接依赖|pip|
|github.com/prometheus/client_golang|v1.16.0|直接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|直接依赖|go|
|github.com/google/certificate-transparency-go|v1.1.4|间接依赖|go|
|github.com/zmap/zcrypto|v0.0.0-20220402174210-599ec18ecbac|间接依赖|go|
|github.com/grpc-ecosystem/go-grpc-prometheus|v1.2.0|直接依赖|go|
|github.com/trustmaster/go-aspell|v0.0.0-20200701131845-c2b1f55bec8f|间接依赖|go|
|go.uber.org/multierr|v1.11.0|直接依赖|go|
|github.com/alexkohler/nakedret|v1.0.2|直接依赖|go|
|sigs.k8s.io/yaml|v1.3.0|直接依赖|go|
|golang.org/x/tools|v0.12.0|间接依赖|go|
|go.etcd.io/etcd/client/pkg/v3|v3.6.0-alpha.0|直接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|github.com/chavacava/garif|v0.0.0-20230608123814-4bd63c2919ab|间接依赖|go|
|github.com/braydonk/yaml|v0.7.0|间接依赖|go|
|github.com/google/addlicense|v1.1.1|直接依赖|go|
|github.com/lib/pq|v1.10.1|间接依赖|go|
|go.uber.org/zap|v1.25.0|直接依赖|go|
|github.com/fatih/color|v1.15.0|间接依赖|go|
|sigs.k8s.io/json|v0.0.0-20211020170558-c049b76a60c6|直接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/dustin/go-humanize|v1.0.1|直接依赖|go|
|github.com/jmhodges/clock|v1.2.0|间接依赖|go|
|github.com/xiang90/probing|v0.0.0-20190116061207-43a291ad63a2|直接依赖|go|
|k8s.io/klog/v2|v2.80.1|间接依赖|go|
|github.com/BurntSushi/toml|v1.3.2|间接依赖|go|
|gopkg.in/check.v1|v1.0.0-20201130134442-10cb98267c6c|间接依赖|go|
|github.com/chzchzchz/goword|v0.0.0-20170907005317-a9744cb52b03|直接依赖|go|
|github.com/fatih/structtag|v1.2.0|间接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/jmoiron/sqlx|v1.3.3|间接依赖|go|
|go.opentelemetry.io/otel/metric|v1.17.0|间接依赖|go|
|github.com/bmatcuk/doublestar/v4|v4.6.0|间接依赖|go|
|github.com/spf13/cobra|v1.7.0|直接依赖|go|
|golang.org/x/term|v0.12.0|间接依赖|go|
|golang.org/x/net|v0.15.0|直接依赖|go|
|gotest.tools/gotestsum|v1.10.1|直接依赖|go|
|github.com/cloudflare/cfssl|v1.6.4|直接依赖|go|
|github.com/go-sql-driver/mysql|v1.6.0|间接依赖|go|
|github.com/golang/protobuf|v1.5.3|直接依赖|go|
|github.com/mattn/go-runewidth|v0.0.15|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230803162519-f966b187b2e5|间接依赖|go|
|github.com/cenkalti/backoff/v4|v4.2.1|间接依赖|go|
|github.com/grpc-ecosystem/go-grpc-middleware|v1.3.0|直接依赖|go|
|gopkg.in/op/go-logging.v1|v1.0.0-20160211212156-b2cb9fa56473|间接依赖|go|
|github.com/go-logr/logr|v1.2.0|间接依赖|go|
|github.com/dimchansky/utfbom|v1.1.1|间接依赖|go|
|github.com/akhenakh/hunspellgo|v0.0.0-20160221122622-9db38fa26e19|间接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230803162519-f966b187b2e5|间接依赖|go|
|go.opentelemetry.io/otel|v1.17.0|直接依赖|go|
|google.golang.org/protobuf|v1.31.0|直接依赖|go|
|github.com/soheilhy/cmux|v0.1.5|直接依赖|go|
|numpy|1.24.3|间接依赖|pip|
|go.etcd.io/etcd/api/v3|v3.6.0-alpha.0|直接依赖|go|
|github.com/creack/pty|v1.1.18|直接依赖|go|
|google.golang.org/genproto/googleapis/api|v0.0.0-20230822172742-b8732ec3820d|直接依赖|go|
|github.com/sirupsen/logrus|v1.8.1|间接依赖|go|
|mvdan.cc/unparam|v0.0.0-20220316160445-06cc5682983b|直接依赖|go|
|github.com/magiconair/properties|v1.8.7|间接依赖|go|
|github.com/google/yamlfmt|v0.10.0|直接依赖|go|
|github.com/golang-jwt/jwt/v4|v4.5.0|直接依赖|go|
|go.etcd.io/etcd/client/v2|v2.306.0-alpha.0|直接依赖|go|
|github.com/ghodss/yaml|v1.0.0|间接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/google.golang.org/grpc/otelgrpc|v0.43.0|直接依赖|go|
|github.com/prometheus/procfs|v0.10.1|间接依赖|go|
|go.etcd.io/etcd/etcdctl/v3|v3.6.0-alpha.0|直接依赖|go|
|github.com/pelletier/go-toml|v1.9.3|间接依赖|go|
|go.etcd.io/etcd/client/v3|v3.6.0-alpha.0|直接依赖|go|
|github.com/pelletier/go-toml/v2|v2.0.9|间接依赖|go|
|github.com/jonboulle/clockwork|v0.4.0|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)