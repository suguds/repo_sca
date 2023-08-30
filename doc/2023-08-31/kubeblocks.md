# apecloud/kubeblocks安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696948147916795904.svg)](https://www.murphysec.com/console/report/1696948147862269952/1696948147916795904)

仓库描述：KubeBlocks helps developers and platform engineers manage database workloads (MySQL, PostgresSQL,  Redis, MongoDB, Kafka and vector databases) on K8s inside your own cloud account. It supports multiple clouds, including AWS, Azure, GCP, and Alibaba Cloud.

仓库地址：[https://github.com/apecloud/kubeblocks](https://github.com/apecloud/kubeblocks)

| star：698 | watch：11 | fork：51 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-31 01:21:54 | 许可证：AGPL-3.0 |
| 最近检测时间：2023-08-31 02:09:41 | 组件总数：433 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Dapr 授权问题漏洞|身份验证不当|[MPS-rdo6-f1cq](https://www.oscs1024.com/hd/MPS-rdo6-f1cq)|CVE-2023-37918|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/dapr/dapr|v1.9.5|1.11.2|直接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|152|Low|
|BSD-3-Clause|70|Low|
|Apache-2.0|182|Low|
|MPL-2.0|15|Low|
|BSD-2-Clause|14|Low|
|BSD-2-Clause-Views|1|Low|
|ISC|3|Low|
|CC-BY-SA-4.0|2|Medium|
|Unlicense|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/dustin/go-humanize|v1.0.1|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|golang.org/x/net|v0.14.0|直接依赖|go|
|github.com/jackc/pgx/v5|v5.4.3|直接依赖|go|
|github.com/replicatedhq/troubleshoot|v0.57.0|直接依赖|go|
|github.com/moby/locker|v1.0.1|间接依赖|go|
|sigs.k8s.io/kustomize/kustomize/v4|v4.5.7|间接依赖|go|
|google.golang.org/api|v0.122.0|间接依赖|go|
|google.golang.org/grpc|v1.56.2|直接依赖|go|
|github.com/go-logr/logr|v1.2.4|直接依赖|go|
|go.uber.org/automaxprocs|v1.5.2|直接依赖|go|
|github.com/gobwas/glob|v0.2.3|间接依赖|go|
|github.com/hashicorp/go-getter|v1.7.0|间接依赖|go|
|github.com/sigstore/fulcio|v1.0.0|间接依赖|go|
|github.com/daviddengcn/go-colortext|v1.0.0|间接依赖|go|
|github.com/deckarep/golang-set|v1.8.0|间接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/google.golang.org/grpc/otelgrpc|v0.35.0|间接依赖|go|
|k8s.io/kubelet|v0.26.1|直接依赖|go|
|github.com/go-openapi/validate|v0.22.1|间接依赖|go|
|github.com/docker/distribution|v2.8.2+incompatible|间接依赖|go|
|github.com/gsterjov/go-libsecret|v0.0.0-20161001094733-a6f4afe4910c|间接依赖|go|
|github.com/hashicorp/go-safetemp|v1.0.0|间接依赖|go|
|github.com/grandcat/zeroconf|v1.0.0|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|直接依赖|go|
|github.com/letsencrypt/boulder|v0.0.0-20221109233200-85aa52084eaf|间接依赖|go|
|github.com/briandowns/spinner|v1.23.0|直接依赖|go|
|github.com/docker/go|v1.5.1-1.0.20160303222718-d30aec9fd63c|间接依赖|go|
|github.com/mtibben/percent|v0.2.1|间接依赖|go|
|github.com/golang/mock|v1.6.0|直接依赖|go|
|github.com/grpc-ecosystem/go-grpc-prometheus|v1.2.0|间接依赖|go|
|github.com/mattn/go-shellwords|v1.0.12|间接依赖|go|
|cloud.google.com/go/compute/metadata|v0.2.3|间接依赖|go|
|github.com/shopspring/decimal|v1.2.0|间接依赖|go|
|github.com/moby/sys/mountinfo|v0.6.2|间接依赖|go|
|github.com/dapr/dapr|v1.9.5|直接依赖|go|
|github.com/lann/builder|v0.0.0-20180802200727-47ae307949d0|间接依赖|go|
|github.com/DATA-DOG/go-sqlmock|v1.5.0|直接依赖|go|
|github.com/containerd/containerd|v1.6.18|间接依赖|go|
|go.mozilla.org/pkcs7|v0.0.0-20210826202110-33d05740a352|间接依赖|go|
|github.com/stoewer/go-strcase|v1.2.0|直接依赖|go|
|github.com/cyphar/filepath-securejoin|v0.2.3|间接依赖|go|
|github.com/theupdateframework/go-tuf|v0.5.2|间接依赖|go|
|github.com/go-errors/errors|v1.4.0|间接依赖|go|
|github.com/dapr/go-sdk|v1.7.0|直接依赖|go|
|github.com/golang/snappy|v0.0.4|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace/otlptracehttp|v1.11.2|间接依赖|go|
|github.com/xdg-go/scram|v1.1.2|直接依赖|go|
|github.com/jcmturner/rpc/v2|v2.0.3|间接依赖|go|
|github.com/cyberphone/json-canonicalization|v0.0.0-20220623050100-57a0ce2678a7|间接依赖|go|
|gopkg.in/ini.v1|v1.67.0|间接依赖|go|
|github.com/prometheus/procfs|v0.9.0|间接依赖|go|
|golang.org/x/text|v0.12.0|直接依赖|go|
|k8s.io/cri-api|v0.27.1|直接依赖|go|
|github.com/danieljoos/wincred|v1.1.2|间接依赖|go|
|go.etcd.io/etcd/client/v2|v2.305.8|间接依赖|go|
|github.com/lithammer/dedent|v1.1.0|间接依赖|go|
|k8s.io/component-base|v0.26.3|直接依赖|go|
|github.com/lann/ps|v0.0.0-20150810152359-62de8c46ede0|间接依赖|go|
|github.com/coreos/go-semver|v0.3.0|间接依赖|go|
|github.com/go-ole/go-ole|v1.2.6|间接依赖|go|
|github.com/PuerkitoBio/purell|v1.2.0|间接依赖|go|
|k8s.io/api|v0.26.3|直接依赖|go|
|github.com/nsf/termbox-go|v0.0.0-20190121233118-02980233997d|间接依赖|go|
|github.com/replicatedhq/termui/v3|v3.1.1-0.20200811145416-f40076d26851|直接依赖|go|
|github.com/distribution/distribution/v3|v3.0.0-20221208165359-362910506bc2|间接依赖|go|
|k8s.io/apiserver|v0.26.3|间接依赖|go|
|k8s.io/klog/v2|v2.100.1|直接依赖|go|
|github.com/k3d-io/k3d/v5|v5.4.4|直接依赖|go|
|github.com/Shopify/sarama|v1.37.2|直接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|github.com/russross/blackfriday/v2|v2.1.0|直接依赖|go|
|github.com/longhorn/go-iscsi-helper|v0.0.0-20210330030558-49a327fb024e|间接依赖|go|
|github.com/opencontainers/runtime-spec|v1.0.3-0.20210326190908-1c3f411f0417|间接依赖|go|
|github.com/oklog/ulid|v1.3.1|间接依赖|go|
|github.com/kevinburke/ssh_config|v1.2.0|间接依赖|go|
|github.com/acomagu/bufpipe|v1.0.4|间接依赖|go|
|github.com/Masterminds/semver/v3|v3.2.1|直接依赖|go|
|periph.io/x/host/v3|v3.8.0|间接依赖|go|
|github.com/jmoiron/sqlx|v1.3.5|间接依赖|go|
|github.com/spf13/viper|v1.16.0|直接依赖|go|
|sigs.k8s.io/kustomize/api|v0.12.1|间接依赖|go|
|github.com/gorilla/handlers|v1.5.1|间接依赖|go|
|github.com/hashicorp/errwrap|v1.1.0|间接依赖|go|
|github.com/jcmturner/dnsutils/v2|v2.0.0|间接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|github.com/rivo/uniseg|v0.4.3|间接依赖|go|
|github.com/google/go-containerregistry|v0.14.0|间接依赖|go|
|go.opentelemetry.io/otel|v1.14.0|间接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.6|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|github.com/vbatts/tar-split|v0.11.2|间接依赖|go|
|github.com/sony/gobreaker|v0.5.0|间接依赖|go|
|github.com/go-git/go-git/v5|v5.6.1|直接依赖|go|
|github.com/jcmturner/gofork|v1.7.6|间接依赖|go|
|github.com/docker/go-units|v0.5.0|间接依赖|go|
|github.com/sergi/go-diff|v1.2.0|间接依赖|go|
|github.com/google/gnostic|v0.6.9|间接依赖|go|
|github.com/go-test/deep|v1.1.0|间接依赖|go|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|k8s.io/gengo|v0.0.0-20220913193501-391367153a38|直接依赖|go|
|github.com/rubenv/sql-migrate|v1.2.0|间接依赖|go|
|github.com/googleapis/gax-go/v2|v2.8.0|间接依赖|go|
|go4.org/unsafe/assume-no-moving-gc|v0.0.0-20230221090011-e4bae7ad2296|间接依赖|go|
|github.com/fatih/color|v1.15.0|直接依赖|go|
|github.com/docker/docker|v24.0.2+incompatible|直接依赖|go|
|go.opentelemetry.io/otel/sdk|v1.14.0|间接依赖|go|
|github.com/godbus/dbus|v0.0.0-20190726142602-4481cbc300e2|间接依赖|go|
|github.com/dgryski/go-rendezvous|v0.0.0-20200823014737-9f7001d12a5f|间接依赖|go|
|github.com/hashicorp/golang-lru|v0.5.4|间接依赖|go|
|golang.org/x/tools|v0.9.3|间接依赖|go|
|github.com/dapr/components-contrib|v1.9.6|直接依赖|go|
|github.com/evanphx/json-patch/v5|v5.6.0|间接依赖|go|
|github.com/bhmj/xpression|v0.9.1|间接依赖|go|
|github.com/containers/common|v0.49.1|直接依赖|go|
|github.com/leaanthony/debme|v1.2.1|直接依赖|go|
|github.com/gosuri/uitable|v0.0.4|间接依赖|go|
|github.com/theupdateframework/notary|v0.7.0|间接依赖|go|
|github.com/spf13/afero|v1.9.5|直接依赖|go|
|github.com/BurntSushi/toml|v1.2.1|间接依赖|go|
|github.com/pierrec/lz4/v4|v4.1.17|间接依赖|go|
|go.etcd.io/etcd/server/v3|v3.5.6|直接依赖|go|
|github.com/sahilm/fuzzy|v0.1.0|直接依赖|go|
|github.com/valyala/bytebufferpool|v1.0.0|间接依赖|go|
|github.com/mxk/go-flowrate|v0.0.0-20140419014527-cca7078d478f|间接依赖|go|
|github.com/rcrowley/go-metrics|v0.0.0-20201227073835-cf1acfcdf475|间接依赖|go|
|go.uber.org/multierr|v1.9.0|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|go.opencensus.io|v0.24.0|间接依赖|go|
|github.com/kubernetes-csi/external-snapshotter/client/v6|v6.2.0|直接依赖|go|
|github.com/99designs/go-keychain|v0.0.0-20191008050251-8e49817e8af4|间接依赖|go|
|github.com/miekg/dns|v1.1.50|间接依赖|go|
|github.com/google/pprof|v0.0.0-20221103000818-d260c55eee4c|间接依赖|go|
|github.com/cenkalti/backoff/v4|v4.2.1|直接依赖|go|
|github.com/googleapis/enterprise-certificate-proxy|v0.2.3|间接依赖|go|
|github.com/lestrrat-go/file-rotatelogs|v2.4.0+incompatible|间接依赖|go|
|github.com/sigstore/rekor|v1.2.0|间接依赖|go|
|github.com/yusufpapurcu/wmi|v1.2.3|间接依赖|go|
|github.com/golang/glog|v1.0.0|间接依赖|go|
|github.com/youmark/pkcs8|v0.0.0-20181117223130-1be2e3e5546d|间接依赖|go|
|github.com/go-logr/zapr|v1.2.4|直接依赖|go|
|go.etcd.io/etcd/v3|v3.5.6|间接依赖|go|
|github.com/pashagolub/pgxmock/v2|v2.11.0|直接依赖|go|
|github.com/Microsoft/hcsshim|v0.9.6|间接依赖|go|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|github.com/estesp/manifest-tool/v2|v2.0.3|间接依赖|go|
|golang.org/x/time|v0.3.0|间接依赖|go|
|github.com/imdario/mergo|v0.3.13|间接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|github.com/jonboulle/clockwork|v0.3.0|间接依赖|go|
|github.com/robfig/cron/v3|v3.0.1|间接依赖|go|
|github.com/klauspost/pgzip|v1.2.6-0.20220930104621-17e8dac29df8|间接依赖|go|
|github.com/syndtr/gocapability|v0.0.0-20200815063812-42c35b437635|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|直接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|github.com/prometheus/common|v0.42.0|间接依赖|go|
|github.com/ProtonMail/go-crypto|v0.0.0-20230217124315-7d5c6f04bbb8|间接依赖|go|
|github.com/google/btree|v1.1.2|间接依赖|go|
|github.com/go-git/go-billy/v5|v5.4.1|间接依赖|go|
|github.com/sirupsen/logrus|v1.9.3|直接依赖|go|
|github.com/manifoldco/promptui|v0.9.0|直接依赖|go|
|github.com/cockroachdb/apd/v2|v2.0.1|间接依赖|go|
|github.com/AdhityaRamadhanus/fasthttpcors|v0.0.0-20170121111917-d4c07198763a|间接依赖|go|
|github.com/jcmturner/aescts/v2|v2.0.0|间接依赖|go|
|k8s.io/kubectl|v0.26.0|直接依赖|go|
|google.golang.org/protobuf|v1.31.0|直接依赖|go|
|github.com/ahmetalpbalkan/go-cursor|v0.0.0-20131010032410-8136607ea412|间接依赖|go|
|github.com/jbenet/go-context|v0.0.0-20150711004518-d14ea06fba99|间接依赖|go|
|golang.org/x/xerrors|v0.0.0-20220907171357-04be3eba64a2|间接依赖|go|
|github.com/Azure/go-ansiterm|v0.0.0-20210617225240-d185dfc1b5a1|间接依赖|go|
|github.com/onsi/ginkgo/v2|v2.11.0|直接依赖|go|
|github.com/xeipuuv/gojsonschema|v1.2.0|直接依赖|go|
|github.com/gorilla/websocket|v1.5.0|间接依赖|go|
|github.com/montanaflynn/stats|v0.6.6|间接依赖|go|
|github.com/pelletier/go-toml/v2|v2.0.8|间接依赖|go|
|github.com/jackc/pgservicefile|v0.0.0-20221227161230-091c0ba34f0a|间接依赖|go|
|github.com/pjbgf/sha1cd|v0.3.0|间接依赖|go|
|github.com/docker/go-connections|v0.4.1-0.20190612165340-fd1b1942c4d5|直接依赖|go|
|github.com/jedib0t/go-pretty/v6|v6.4.6|直接依赖|go|
|github.com/go-redis/redis/v7|v7.4.1|间接依赖|go|
|cloud.google.com/go/compute|v1.19.0|间接依赖|go|
|github.com/google/gofuzz|v1.2.0|间接依赖|go|
|github.com/subosito/gotenv|v1.4.2|间接依赖|go|
|github.com/dlclark/regexp2|v1.10.0|直接依赖|go|
|go.etcd.io/etcd/api/v3|v3.5.9|间接依赖|go|
|go.etcd.io/etcd/raft/v3|v3.5.8|间接依赖|go|
|github.com/eapache/go-xerial-snappy|v0.0.0-20230111030713-bf00bc1b83b6|间接依赖|go|
|golang.org/x/exp|v0.0.0-20230711153332-06a737ee72cb|直接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|直接依赖|go|
|github.com/sethvargo/go-password|v0.2.0|直接依赖|go|
|github.com/containers/libtrust|v0.0.0-20230121012942-c1716e8a8d01|间接依赖|go|
|github.com/dvsekhvalnov/jose2go|v1.5.0|间接依赖|go|
|github.com/mattn/go-runewidth|v0.0.14|间接依赖|go|
|github.com/fullstorydev/grpcurl|v1.8.7|间接依赖|go|
|github.com/pkg/sftp|v1.13.5|间接依赖|go|
|github.com/asaskevich/govalidator|v0.0.0-20230301143203-a9d515a09cc2|间接依赖|go|
|github.com/go-openapi/loads|v0.21.2|间接依赖|go|
|github.com/aws/aws-sdk-go|v1.44.257|直接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/internal/retry|v1.11.2|间接依赖|go|
|github.com/opencontainers/image-spec|v1.1.0-rc2|直接依赖|go|
|github.com/deckarep/golang-set/v2|v2.3.1|直接依赖|go|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|github.com/jackc/puddle/v2|v2.2.1|间接依赖|go|
|sigs.k8s.io/kustomize/kyaml|v0.13.9|直接依赖|go|
|github.com/mitchellh/copystructure|v1.2.0|间接依赖|go|
|golang.org/x/sync|v0.3.0|直接依赖|go|
|github.com/godbus/dbus/v5|v5.1.0|间接依赖|go|
|github.com/bgentry/go-netrc|v0.0.0-20140422174119-9fd32a8b3d3d|间接依赖|go|
|github.com/sigstore/sigstore|v1.6.4|间接依赖|go|
|k8s.io/apimachinery|v0.26.3|直接依赖|go|
|github.com/savsgio/gotils|v0.0.0-20220530130905-52f3993e8d6d|间接依赖|go|
|github.com/google/s2a-go|v0.1.3|间接依赖|go|
|github.com/stretchr/testify|v1.8.4|直接依赖|go|
|github.com/hashicorp/go-cleanhttp|v0.5.2|直接依赖|go|
|github.com/cloudflare/circl|v1.3.3|间接依赖|go|
|go.opentelemetry.io/otel/exporters/zipkin|v1.11.2|间接依赖|go|
|github.com/emirpasic/gods|v1.18.1|间接依赖|go|
|github.com/go-openapi/spec|v0.20.9|间接依赖|go|
|github.com/cenkalti/backoff|v2.2.1+incompatible|间接依赖|go|
|github.com/coreos/go-systemd/v22|v22.3.2|间接依赖|go|
|github.com/redis/go-redis/v9|v9.0.5|直接依赖|go|
|github.com/monochromegane/go-gitignore|v0.0.0-20200626010858-205db1a8cc00|间接依赖|go|
|github.com/Microsoft/go-winio|v0.6.0|间接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.3|间接依赖|go|
|github.com/dapr/kit|v0.11.3|直接依赖|go|
|github.com/tklauser/go-sysconf|v0.3.11|间接依赖|go|
|golang.org/x/oauth2|v0.9.0|直接依赖|go|
|github.com/fasthttp/router|v1.4.15|间接依赖|go|
|github.com/lib/pq|v1.10.9|间接依赖|go|
|github.com/cpuguy83/go-md2man/v2|v2.0.2|间接依赖|go|
|github.com/go-openapi/analysis|v0.21.4|间接依赖|go|
|github.com/containers/storage|v1.45.3|间接依赖|go|
|github.com/sykesm/zap-logfmt|v0.0.4|直接依赖|go|
|github.com/VividCortex/ewma|v1.2.0|间接依赖|go|
|go.etcd.io/etcd/client/pkg/v3|v3.5.9|间接依赖|go|
|github.com/segmentio/ksuid|v1.0.4|间接依赖|go|
|github.com/xdg-go/pbkdf2|v1.0.0|间接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0|间接依赖|go|
|k8s.io/utils|v0.0.0-20230406110748-d93618cff8a2|直接依赖|go|
|github.com/protocolbuffers/txtpbfmt|v0.0.0-20201118171849-f6a6b3f636fc|间接依赖|go|
|github.com/chzyer/readline|v1.5.1|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.19|直接依赖|go|
|contrib.go.opencensus.io/exporter/prometheus|v0.4.2|间接依赖|go|
|github.com/acarl005/stripansi|v0.0.0-20180116102854-5a71ef0e047d|间接依赖|go|
|github.com/jcmturner/gokrb5/v8|v8.4.3|间接依赖|go|
|github.com/prometheus/client_model|v0.4.0|间接依赖|go|
|cloud.google.com/go/iam|v0.13.0|间接依赖|go|
|github.com/tchap/go-patricia|v2.3.0+incompatible|间接依赖|go|
|github.com/kopia/kopia|v0.10.7|间接依赖|go|
|github.com/openzipkin/zipkin-go|v0.4.1|间接依赖|go|
|github.com/magiconair/properties|v1.8.7|直接依赖|go|
|github.com/authzed/controller-idioms|v0.7.0|直接依赖|go|
|github.com/eapache/go-resiliency|v1.3.0|间接依赖|go|
|github.com/dimchansky/utfbom|v1.1.1|间接依赖|go|
|github.com/spf13/cobra|v1.7.0|直接依赖|go|
|github.com/onsi/gomega|v1.27.8|直接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20230308215209-15aac26d736a|直接依赖|go|
|github.com/modood/table|v0.0.0-20220527013332-8d47e76dad33|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/google/cel-go|v0.13.0|间接依赖|go|
|github.com/go-git/gcfg|v1.5.0|间接依赖|go|
|github.com/hashicorp/go-uuid|v1.0.3|间接依赖|go|
|github.com/clbanning/mxj/v2|v2.5.7|直接依赖|go|
|sigs.k8s.io/json|v0.0.0-20221116044647-bc3834ca7abd|间接依赖|go|
|github.com/containers/ocicrypt|v1.1.7|间接依赖|go|
|github.com/titanous/rocacheck|v0.0.0-20171023193734-afe73141d399|间接依赖|go|
|github.com/moby/term|v0.0.0-20221205130635-1aeaba878587|间接依赖|go|
|github.com/c9s/goprocinfo|v0.0.0-20170724085704-0010a05ce49f|间接依赖|go|
|github.com/stretchr/objx|v0.5.0|间接依赖|go|
|go.etcd.io/etcd/client/v3|v3.5.9|直接依赖|go|
|github.com/benbjohnson/clock|v1.3.5|直接依赖|go|
|github.com/exponent-io/jsonpath|v0.0.0-20151013193312-d6023ce2651d|间接依赖|go|
|cloud.google.com/go|v0.110.0|间接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway/v2|v2.11.3|间接依赖|go|
|github.com/shoenig/go-m1cpu|v0.1.6|间接依赖|go|
|github.com/morikuni/aec|v1.0.0|间接依赖|go|
|oras.land/oras-go|v1.2.2|间接依赖|go|
|github.com/prometheus-community/pro-bing|v0.3.0|直接依赖|go|
|github.com/mitchellh/go-testing-interface|v1.14.1|间接依赖|go|
|gopkg.in/warnings.v0|v0.1.2|间接依赖|go|
|github.com/ghodss/yaml|v1.0.0|直接依赖|go|
|github.com/lufia/plan9stats|v0.0.0-20211012122336-39d0f177ccd0|间接依赖|go|
|github.com/fvbommel/sortorder|v1.0.2|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/lestrrat-go/strftime|v1.0.5|间接依赖|go|
|go.etcd.io/etcd/pkg/v3|v3.5.8|间接依赖|go|
|github.com/apecloud/kubebench|v0.0.0-20230807061913-16124b86637f|直接依赖|go|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|github.com/liggitt/tabwriter|v0.0.0-20181228230101-89fcab3d43de|间接依赖|go|
|github.com/jhump/protoreflect|v1.14.1|间接依赖|go|
|github.com/opencontainers/runc|v1.1.5|间接依赖|go|
|github.com/gorilla/mux|v1.8.0|间接依赖|go|
|github.com/go-openapi/strfmt|v0.21.7|间接依赖|go|
|github.com/grpc-ecosystem/go-grpc-middleware|v1.4.0|间接依赖|go|
|github.com/evanphx/json-patch|v5.6.0+incompatible|直接依赖|go|
|github.com/Masterminds/goutils|v1.1.1|间接依赖|go|
|github.com/moby/sys/mount|v0.3.0|间接依赖|go|
|sigs.k8s.io/yaml|v1.3.0|直接依赖|go|
|github.com/huandu/xstrings|v1.3.3|间接依赖|go|
|github.com/tmc/grpc-websocket-proxy|v0.0.0-20201229170055-e5319fda7802|间接依赖|go|
|go.opentelemetry.io/proto/otlp|v0.19.0|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/soheilhy/cmux|v0.1.5|间接依赖|go|
|k8s.io/client-go|v0.26.3|直接依赖|go|
|github.com/vmware-tanzu/velero|v1.10.1|直接依赖|go|
|github.com/hashicorp/terraform-exec|v0.18.0|直接依赖|go|
|k8s.io/apiextensions-apiserver|v0.26.3|直接依赖|go|
|golang.org/x/sys|v0.11.0|间接依赖|go|
|github.com/smartystreets/assertions|v1.0.0|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|github.com/gregjones/httpcache|v0.0.0-20180305231024-9cad4c3443a7|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/sylabs/sif/v2|v2.9.0|间接依赖|go|
|github.com/spf13/cast|v1.5.1|直接依赖|go|
|github.com/moby/spdystream|v0.2.0|间接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/rifflock/lfshook|v0.0.0-20180920164130-b9218ef580f5|间接依赖|go|
|github.com/prometheus/client_golang|v1.15.1|间接依赖|go|
|github.com/kubernetes-csi/external-snapshotter/client/v4|v4.2.0|间接依赖|go|
|github.com/deislabs/oras|v0.9.0|间接依赖|go|
|go.mongodb.org/mongo-driver|v1.11.6|直接依赖|go|
|github.com/go-openapi/runtime|v0.26.0|间接依赖|go|
|github.com/golang-jwt/jwt/v4|v4.5.0|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230410155749-daa745c078e1|间接依赖|go|
|github.com/hashicorp/hc-install|v0.5.2|直接依赖|go|
|github.com/go-task/slim-sprig|v0.0.0-20230315185526-52ccab3ef572|直接依赖|go|
|github.com/Masterminds/squirrel|v1.5.3|间接依赖|go|
|gopkg.in/square/go-jose.v2|v2.6.0|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|直接依赖|go|
|github.com/jackc/pgpassfile|v1.0.0|间接依赖|go|
|github.com/mitchellh/reflectwalk|v1.0.2|间接依赖|go|
|k8s.io/code-generator|v0.26.3|直接依赖|go|
|github.com/zclconf/go-cty|v1.12.1|间接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway|v1.16.0|间接依赖|go|
|github.com/docker/cli|v23.0.1+incompatible|间接依赖|go|
|github.com/miekg/pkcs11|v1.1.1|间接依赖|go|
|github.com/bhmj/jsonslice|v1.1.2|直接依赖|go|
|gopkg.in/inf.v0|v0.9.1|直接依赖|go|
|github.com/mitchellh/go-wordwrap|v1.0.1|间接依赖|go|
|github.com/docker/go-metrics|v0.0.1|间接依赖|go|
|github.com/tklauser/numcpus|v0.6.0|间接依赖|go|
|github.com/fatih/camelcase|v1.0.0|间接依赖|go|
|github.com/xanzy/ssh-agent|v0.3.3|间接依赖|go|
|github.com/blang/semver/v4|v4.0.0|间接依赖|go|
|github.com/xlab/treeprint|v1.1.0|间接依赖|go|
|github.com/google/go-intervals|v0.0.2|间接依赖|go|
|github.com/mistifyio/go-zfs/v3|v3.0.0|间接依赖|go|
|github.com/mpvl/unique|v0.0.0-20150818121801-cbe035fff7de|间接依赖|go|
|github.com/hashicorp/terraform-json|v0.15.0|间接依赖|go|
|github.com/kr/fs|v0.1.0|间接依赖|go|
|github.com/go-kit/log|v0.2.1|间接依赖|go|
|go.starlark.net|v0.0.0-20201006213952-227f4aabceb5|间接依赖|go|
|github.com/valyala/fasthttp|v1.47.0|直接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/vbauerster/mpb/v7|v7.5.3|间接依赖|go|
|github.com/felixge/httpsnoop|v1.0.3|间接依赖|go|
|go.etcd.io/etcd/etcdctl/v3|v3.5.6|间接依赖|go|
|github.com/google/shlex|v0.0.0-20191202100458-e7afc7fbc510|间接依赖|go|
|github.com/go-openapi/errors|v0.20.3|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|github.com/MakeNowJust/heredoc|v1.0.0|间接依赖|go|
|github.com/chaos-mesh/chaos-mesh/api|v0.0.0-20230423031423-0b31a519b502|直接依赖|go|
|github.com/go-redis/redismock/v9|v9.0.3|直接依赖|go|
|go.opentelemetry.io/otel/trace|v1.14.0|间接依赖|go|
|github.com/alecthomas/units|v0.0.0-20211218093645-b94a6e3cc137|间接依赖|go|
|github.com/google/uuid|v1.3.0|直接依赖|go|
|github.com/antlr/antlr4/runtime/Go/antlr|v1.4.10|间接依赖|go|
|k8s.io/component-helpers|v0.26.0|间接依赖|go|
|github.com/emicklei/proto|v1.6.15|间接依赖|go|
|github.com/eapache/queue|v1.1.0|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|go4.org/intern|v0.0.0-20211027215823-ae77deb06f29|间接依赖|go|
|golang.org/x/mod|v0.11.0|间接依赖|go|
|github.com/goodhosts/hostsfile|v0.1.1|间接依赖|go|
|cloud.google.com/go/storage|v1.29.0|间接依赖|go|
|github.com/minio/blake2b-simd|v0.0.0-20160723061019-3f5f724cb5b1|间接依赖|go|
|github.com/klauspost/compress|v1.16.3|间接依赖|go|
|github.com/andybalholm/brotli|v1.0.5|间接依赖|go|
|github.com/shirou/gopsutil/v3|v3.23.6|直接依赖|go|
|github.com/xiang90/probing|v0.0.0-20190116061207-43a291ad63a2|间接依赖|go|
|go.etcd.io/bbolt|v1.3.7|间接依赖|go|
|github.com/kubernetes-csi/external-snapshotter/client/v3|v3.0.0|直接依赖|go|
|sigs.k8s.io/controller-runtime|v0.14.6|直接依赖|go|
|go.uber.org/zap|v1.24.0|直接依赖|go|
|gomodules.xyz/jsonpatch/v2|v2.2.0|间接依赖|go|
|github.com/containers/image/v5|v5.24.0|间接依赖|go|
|github.com/xeipuuv/gojsonpointer|v0.0.0-20190905194746-02993c407bfb|间接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.1-0.20220423185008-bf980b35cac4|直接依赖|go|
|github.com/xeipuuv/gojsonreference|v0.0.0-20180127040603-bd5ef7bd5415|间接依赖|go|
|github.com/stefanberger/go-pkcs11uri|v0.0.0-20201008174630-78d3cae3a980|间接依赖|go|
|github.com/go-openapi/swag|v0.22.3|间接依赖|go|
|github.com/kubesphere/kubekey/v3|v3.0.7|直接依赖|go|
|github.com/spf13/jwalterweatherman|v1.1.0|间接依赖|go|
|github.com/mattn/go-sqlite3|v2.0.3+incompatible|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace|v1.11.2|间接依赖|go|
|github.com/power-devops/perfstat|v0.0.0-20210106213030-5aafc221ea8c|间接依赖|go|
|github.com/go-logfmt/logfmt|v0.5.1|间接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|间接依赖|go|
|github.com/ulikunitz/xz|v0.5.11|间接依赖|go|
|helm.sh/helm/v3|v3.11.1|直接依赖|go|
|github.com/skeema/knownhosts|v1.1.0|间接依赖|go|
|golang.org/x/crypto|v0.12.0|直接依赖|go|
|github.com/emicklei/go-restful/v3|v3.10.2|间接依赖|go|
|k8s.io/klog|v1.0.0|直接依赖|go|
|github.com/go-gorp/gorp/v3|v3.0.2|间接依赖|go|
|k8s.io/cli-runtime|v0.26.3|直接依赖|go|
|github.com/hashicorp/go-multierror|v1.1.1|间接依赖|go|
|github.com/containerd/stargz-snapshotter/estargz|v0.14.3|直接依赖|go|
|inet.af/netaddr|v0.0.0-20220617031823-097006376321|间接依赖|go|
|go.uber.org/atomic|v1.10.0|间接依赖|go|
|gopkg.in/natefinch/lumberjack.v2|v2.0.0|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|github.com/StudioSol/set|v1.0.0|直接依赖|go|
|golang.org/x/term|v0.11.0|间接依赖|go|
|github.com/golang-jwt/jwt|v3.2.2+incompatible|直接依赖|go|
|github.com/prometheus/statsd_exporter|v0.22.7|间接依赖|go|
|github.com/go-sql-driver/mysql|v1.7.1|直接依赖|go|
|cuelang.org/go|v0.4.3|直接依赖|go|
|github.com/99designs/keyring|v1.2.2|直接依赖|go|
|github.com/opencontainers/selinux|v1.10.2|间接依赖|go|
|github.com/ostreedev/ostree-go|v0.0.0-20210805093236-719684c64e4f|间接依赖|go|
|github.com/containerd/cgroups|v1.0.4|间接依赖|go|
|github.com/docker/docker-credential-helpers|v0.7.0|间接依赖|go|
|github.com/xdg-go/stringprep|v1.0.4|间接依赖|go|
|github.com/hashicorp/go-version|v1.6.0|直接依赖|go|
|github.com/chai2010/gettext-go|v1.0.2|间接依赖|go|
|github.com/Masterminds/sprig/v3|v3.2.3|直接依赖|go|
|k8s.io/metrics|v0.26.3|直接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.1|间接依赖|go|
|github.com/peterbourgon/diskv|v2.0.1+incompatible|间接依赖|go|
|github.com/proglottis/gpgme|v0.1.3|间接依赖|go|
|github.com/tj/go-spin|v1.1.0|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace/otlptracegrpc|v1.11.2|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)