# k3s-io/k3s安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1701660224871251968.svg)](https://www.murphysec.com/console/report/1701660224804143104/1701660224871251968)

仓库描述：Lightweight Kubernetes

仓库地址：[https://github.com/k3s-io/k3s](https://github.com/k3s-io/k3s)

| star：24400 | watch：285 | fork：2117 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-13 00:21:17 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-13 02:13:19 | 组件总数：339 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Kubernetes 输入验证错误漏洞|访问控制不当|[MPS-2019-15838](https://www.oscs1024.com/hd/MPS-2019-15838)|CVE-2019-11255|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|k8s.io/kubernetes|v1.28.1||直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|48|Low|
|Apache-2.0|199|Low|
|MIT|85|Low|
|CC-BY-SA-4.0|2|Medium|
|ISC|1|Low|
|MPL-2.0|5|Low|
|PostgreSQL|1|Low|
|BSD-2-Clause|8|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|google.golang.org/api|v0.138.0|间接依赖|go|
|golang.org/x/crypto|v0.12.0|直接依赖|go|
|github.com/coreos/go-systemd|v0.0.0-20191104093116-d3cd4ed1dbcf|直接依赖|go|
|github.com/mxk/go-flowrate|v0.0.0-20140419014527-cca7078d478f|间接依赖|go|
|k8s.io/kubectl|v0.25.0|直接依赖|go|
|github.com/xlab/treeprint|v1.2.0|间接依赖|go|
|github.com/kubernetes-sigs/cri-tools|v0.0.0-00010101000000-000000000000|直接依赖|go|
|github.com/minio/minio-go/v7|v7.0.33|直接依赖|go|
|github.com/shengdoushi/base58|v1.0.0|间接依赖|go|
|github.com/go-openapi/swag|v0.22.3|间接依赖|go|
|github.com/Rican7/retry|v0.1.0|间接依赖|go|
|github.com/docker/go-metrics|v0.0.1|间接依赖|go|
|github.com/miekg/pkcs11|v1.1.1|间接依赖|go|
|k8s.io/cloud-provider|v0.28.1|直接依赖|go|
|github.com/containerd/stargz-snapshotter|v0.14.3|直接依赖|go|
|github.com/rancher/dynamiclistener|v0.3.6-rc2|直接依赖|go|
|github.com/google/btree|v1.1.2|间接依赖|go|
|github.com/lib/pq|v1.10.2|直接依赖|go|
|k8s.io/gengo|v0.0.0-20220902162205-c0856e24416d|间接依赖|go|
|k8s.io/code-generator|v0.28.1|间接依赖|go|
|github.com/minio/highwayhash|v1.0.2|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/internal/retry|v1.14.0|间接依赖|go|
|github.com/hanwen/go-fuse/v2|v2.2.0|间接依赖|go|
|github.com/ghodss/yaml|v1.0.0|间接依赖|go|
|github.com/pierrec/lz4|v2.6.0+incompatible|间接依赖|go|
|github.com/AdamKorcz/go-118-fuzz-build|v0.0.0-20221215162035-5330a85ea652|间接依赖|go|
|github.com/cenkalti/backoff/v4|v4.2.1|间接依赖|go|
|github.com/jonboulle/clockwork|v0.3.0|间接依赖|go|
|github.com/nats-io/nats.go|v1.27.1|间接依赖|go|
|github.com/robfig/cron/v3|v3.0.1|直接依赖|go|
|github.com/containerd/console|v1.0.3|间接依赖|go|
|golang.org/x/sync|v0.3.0|直接依赖|go|
|k8s.io/legacy-cloud-providers|v0.0.0|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|google.golang.org/genproto/googleapis/api|v0.0.0-20230803162519-f966b187b2e5|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|golang.org/x/mod|v0.10.0|间接依赖|go|
|github.com/containerd/ttrpc|v1.2.2|间接依赖|go|
|github.com/Azure/go-ansiterm|v0.0.0-20210617225240-d185dfc1b5a1|间接依赖|go|
|github.com/moby/term|v0.0.0-20221205130635-1aeaba878587|间接依赖|go|
|github.com/canonical/go-dqlite|v1.5.1|间接依赖|go|
|github.com/rancher/lasso|v0.0.0-20230629200414-8a54b32e6792|直接依赖|go|
|github.com/nats-io/jwt/v2|v2.4.1|间接依赖|go|
|github.com/containerd/go-cni|v1.1.9|间接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/net/http/otelhttp|v0.35.1|间接依赖|go|
|k8s.io/client-go|v11.0.1-0.20190409021438-1a26190bd76a+incompatible|直接依赖|go|
|github.com/docker/docker|v23.0.3+incompatible|直接依赖|go|
|github.com/minio/sha256-simd|v1.0.0|间接依赖|go|
|github.com/rubiojr/go-vhd|v0.0.0-20200706105327-02e210299021|间接依赖|go|
|github.com/otiai10/copy|v1.7.0|直接依赖|go|
|github.com/hashicorp/go-retryablehttp|v0.7.2|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/moby/sys/mountinfo|v0.6.2|间接依赖|go|
|go.opentelemetry.io/proto/otlp|v0.19.0|间接依赖|go|
|go.etcd.io/etcd/client/v2|v2.305.9|间接依赖|go|
|github.com/containerd/typeurl/v2|v2.1.1|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace|v1.14.0|间接依赖|go|
|github.com/felixge/httpsnoop|v1.0.3|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.2|间接依赖|go|
|github.com/containerd/btrfs/v2|v2.0.0|间接依赖|go|
|github.com/coreos/go-oidc|v2.2.1+incompatible|间接依赖|go|
|github.com/docker/go-events|v0.0.0-20190806004212-e31b211e4f1c|间接依赖|go|
|k8s.io/apiserver|v0.28.1|直接依赖|go|
|github.com/prometheus/client_golang|v1.16.0|间接依赖|go|
|github.com/cyphar/filepath-securejoin|v0.2.3|间接依赖|go|
|k8s.io/controller-manager|v0.25.4|间接依赖|go|
|github.com/nats-io/jsm.go|v0.0.31-0.20220317133147-fe318f464eee|间接依赖|go|
|github.com/klauspost/compress|v1.16.6|直接依赖|go|
|github.com/soheilhy/cmux|v0.1.5|间接依赖|go|
|go.etcd.io/etcd/client/pkg/v3|v3.5.9|直接依赖|go|
|github.com/tmc/grpc-websocket-proxy|v0.0.0-20220101234140-673ab2c3ae75|间接依赖|go|
|github.com/mdlayher/netlink|v1.7.2|间接依赖|go|
|k8s.io/kubernetes|v1.28.1|直接依赖|go|
|github.com/armon/circbuf|v0.0.0-20150827004946-bbbad097214e|间接依赖|go|
|github.com/JeffAshton/win_pdh|v0.0.0-20161109143554-76bb4ee9f0ab|间接依赖|go|
|github.com/jackc/pgservicefile|v0.0.0-20221227161230-091c0ba34f0a|间接依赖|go|
|k8s.io/kube-controller-manager|v0.0.0|间接依赖|go|
|k8s.io/kms|v0.0.0|间接依赖|go|
|github.com/prometheus/common|v0.44.0|间接依赖|go|
|github.com/prometheus/procfs|v0.10.1|间接依赖|go|
|golang.org/x/net|v0.14.0|直接依赖|go|
|github.com/GoogleCloudPlatform/k8s-cloud-provider|v1.18.1-0.20220218231025-f11817397a1b|间接依赖|go|
|github.com/onsi/ginkgo/v2|v2.9.4|直接依赖|go|
|github.com/vishvananda/netns|v0.0.4|间接依赖|go|
|github.com/containerd/cgroups|v1.1.0|直接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/Azure/go-autorest/logger|v0.2.1|间接依赖|go|
|github.com/mdlayher/socket|v0.4.1|间接依赖|go|
|github.com/asaskevich/govalidator|v0.0.0-20190424111038-f61b66f89f4a|间接依赖|go|
|k8s.io/apimachinery|v0.28.1|直接依赖|go|
|github.com/sirupsen/logrus|v1.9.3|直接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230807174057-1744710a1577|间接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/github.com/emicklei/go-restful/otelrestful|v0.35.0|间接依赖|go|
|go.mozilla.org/pkcs7|v0.0.0-20200128120323-432b2356ecb1|间接依赖|go|
|github.com/jackc/pgerrcode|v0.0.0-20220416144525-469b46aa5efa|间接依赖|go|
|golang.org/x/text|v0.12.0|间接依赖|go|
|sigs.k8s.io/kustomize/kustomize/v5|v5.0.4-0.20230601165947-6ce0bf390ce3|间接依赖|go|
|github.com/libopenstorage/openstorage|v1.0.0|间接依赖|go|
|k8s.io/cri-api|v0.28.1|直接依赖|go|
|github.com/blang/semver/v4|v4.0.0|直接依赖|go|
|k8s.io/kubelet|v0.0.0|间接依赖|go|
|k8s.io/csi-translation-lib|v0.0.0|间接依赖|go|
|github.com/emicklei/go-restful/v3|v3.10.2|间接依赖|go|
|github.com/Azure/go-autorest/autorest/mocks|v0.4.2|间接依赖|go|
|github.com/Azure/go-autorest/autorest/date|v0.3.0|间接依赖|go|
|github.com/k3s-io/helm-controller|v0.15.4|直接依赖|go|
|github.com/fatih/camelcase|v1.0.0|间接依赖|go|
|github.com/peterbourgon/diskv|v2.0.1+incompatible|间接依赖|go|
|github.com/googleapis/enterprise-certificate-proxy|v0.2.5|间接依赖|go|
|github.com/mdlayher/genetlink|v1.3.2|间接依赖|go|
|github.com/urfave/cli/v2|v2.23.5|间接依赖|go|
|github.com/kylelemons/godebug|v1.1.0|间接依赖|go|
|k8s.io/cli-runtime|v0.22.2|间接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|github.com/google/pprof|v0.0.0-20210720184732-4bb14d4b1be1|间接依赖|go|
|k8s.io/kube-scheduler|v0.0.0|间接依赖|go|
|gopkg.in/natefinch/lumberjack.v2|v2.2.1|间接依赖|go|
|github.com/russross/blackfriday/v2|v2.1.0|间接依赖|go|
|k8s.io/cluster-bootstrap|v0.0.0|直接依赖|go|
|github.com/containerd/aufs|v1.0.0|直接依赖|go|
|github.com/intel/goresctrl|v0.3.0|间接依赖|go|
|go.uber.org/multierr|v1.11.0|间接依赖|go|
|golang.org/x/exp|v0.0.0-20230307190834-24139beb5833|间接依赖|go|
|github.com/docker/docker-credential-helpers|v0.7.0|间接依赖|go|
|github.com/Azure/go-autorest/autorest|v0.11.29|间接依赖|go|
|github.com/moby/sys/symlink|v0.2.0|间接依赖|go|
|github.com/erikdubbelboer/gspt|v0.0.0-20190125194910-e68493906b83|直接依赖|go|
|github.com/Microsoft/hcsshim|v0.10.0-rc.8|间接依赖|go|
|github.com/google/uuid|v1.3.0|直接依赖|go|
|github.com/containerd/continuity|v0.4.1|间接依赖|go|
|github.com/josharian/native|v1.1.0|间接依赖|go|
|github.com/grpc-ecosystem/go-grpc-middleware|v1.3.0|间接依赖|go|
|github.com/Azure/azure-sdk-for-go|v68.0.0+incompatible|间接依赖|go|
|github.com/jackc/pgx/v5|v5.4.2|间接依赖|go|
|github.com/containerd/stargz-snapshotter/estargz|v0.14.3|间接依赖|go|
|github.com/prometheus/client_model|v0.4.0|间接依赖|go|
|sigs.k8s.io/yaml|v1.3.0|直接依赖|go|
|github.com/k3s-io/kine|v0.10.3|直接依赖|go|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|github.com/mitchellh/go-wordwrap|v1.0.1|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|直接依赖|go|
|github.com/yl2chen/cidranger|v1.0.2|直接依赖|go|
|github.com/xrash/smetrics|v0.0.0-20201216005158-039620a65673|间接依赖|go|
|gopkg.in/ini.v1|v1.67.0|间接依赖|go|
|github.com/exponent-io/jsonpath|v0.0.0-20151013193312-d6023ce2651d|间接依赖|go|
|github.com/stefanberger/go-pkcs11uri|v0.0.0-20201008174630-78d3cae3a980|间接依赖|go|
|github.com/bronze1man/goStrongswanVici|v0.0.0-20201105010758-936f38b697fd|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace/otlptracegrpc|v1.14.0|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230815205213-6bfd019c3878|间接依赖|go|
|github.com/Azure/go-autorest/autorest/validation|v0.3.1|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|直接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/coreos/go-semver|v0.3.1|间接依赖|go|
|go.uber.org/atomic|v1.10.0|间接依赖|go|
|k8s.io/apiextensions-apiserver|v0.28.1|间接依赖|go|
|github.com/coreos/go-iptables|v0.6.0|直接依赖|go|
|github.com/google/gofuzz|v1.2.0|间接依赖|go|
|github.com/hashicorp/go-cleanhttp|v0.5.2|间接依赖|go|
|github.com/rancher/wrangler|v1.1.1|直接依赖|go|
|github.com/mistifyio/go-zfs/v3|v3.0.1|间接依赖|go|
|github.com/chai2010/gettext-go|v1.0.2|间接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|sigs.k8s.io/kustomize/kyaml|v0.14.3-0.20230601165947-6ce0bf390ce3|间接依赖|go|
|github.com/stretchr/testify|v1.8.2|直接依赖|go|
|github.com/Mirantis/cri-dockerd|v0.0.0-00010101000000-000000000000|直接依赖|go|
|github.com/containerd/cgroups/v3|v3.0.2|间接依赖|go|
|github.com/AdaLogics/go-fuzz-headers|v0.0.0-20230106234847-43070de90fa1|间接依赖|go|
|github.com/liggitt/tabwriter|v0.0.0-20181228230101-89fcab3d43de|间接依赖|go|
|github.com/minio/md5-simd|v1.1.2|间接依赖|go|
|github.com/hashicorp/errwrap|v1.1.0|间接依赖|go|
|github.com/golang-jwt/jwt/v4|v4.5.0|间接依赖|go|
|github.com/docker/go-connections|v0.4.0|间接依赖|go|
|go.etcd.io/bbolt|v1.3.7|间接依赖|go|
|golang.org/x/term|v0.10.0|间接依赖|go|
|go.starlark.net|v0.0.0-20230525235612-a134d8f9ddca|间接依赖|go|
|github.com/gofrs/flock|v0.8.1|间接依赖|go|
|go.etcd.io/etcd/etcdutl/v3|v3.5.9|直接依赖|go|
|github.com/opencontainers/runtime-tools|v0.9.1-0.20221107090550-2e043c6bd626|间接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0|间接依赖|go|
|go.opentelemetry.io/otel/trace|v1.14.0|间接依赖|go|
|github.com/opencontainers/selinux|v1.11.0|直接依赖|go|
|go.etcd.io/etcd/pkg/v3|v3.5.9|间接依赖|go|
|github.com/container-storage-interface/spec|v1.8.0|间接依赖|go|
|github.com/googleapis/gax-go/v2|v2.12.0|间接依赖|go|
|github.com/mohae/deepcopy|v0.0.0-20170929034955-c48cc78d4826|间接依赖|go|
|github.com/pquerna/cachecontrol|v0.1.0|间接依赖|go|
|github.com/cpuguy83/go-md2man/v2|v2.0.2|间接依赖|go|
|sigs.k8s.io/kustomize/api|v0.13.5-0.20230601165947-6ce0bf390ce3|间接依赖|go|
|github.com/nats-io/nuid|v1.0.1|间接依赖|go|
|github.com/tchap/go-patricia/v2|v2.3.1|间接依赖|go|
|gopkg.in/square/go-jose.v2|v2.6.0|间接依赖|go|
|github.com/spf13/cobra|v1.7.0|间接依赖|go|
|github.com/gorilla/mux|v1.8.0|直接依赖|go|
|google.golang.org/grpc|v1.57.0|直接依赖|go|
|github.com/mattn/go-sqlite3|v1.14.17|直接依赖|go|
|github.com/mrunalp/fileutils|v0.5.0|间接依赖|go|
|github.com/containerd/containerd|v1.6.18|直接依赖|go|
|go.etcd.io/etcd/raft/v3|v3.5.9|间接依赖|go|
|k8s.io/component-helpers|v0.28.1|直接依赖|go|
|github.com/go-test/deep|v1.0.7|直接依赖|go|
|github.com/onsi/gomega|v1.27.6|直接依赖|go|
|github.com/opencontainers/runc|v1.1.7|直接依赖|go|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|github.com/MakeNowJust/heredoc|v1.0.0|间接依赖|go|
|golang.org/x/time|v0.3.0|间接依赖|go|
|github.com/dustin/go-humanize|v1.0.1|间接依赖|go|
|github.com/gorilla/websocket|v1.5.0|直接依赖|go|
|github.com/google/cadvisor|v0.47.3|直接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway/v2|v2.11.3|间接依赖|go|
|github.com/vmware/govmomi|v0.30.0|间接依赖|go|
|github.com/antlr/antlr4/runtime/Go/antlr/v4|v4.0.0-20230305170008-8188dc5388df|间接依赖|go|
|github.com/moby/sys/sequential|v0.5.0|间接依赖|go|
|github.com/pelletier/go-toml|v1.9.5|间接依赖|go|
|github.com/go-logr/logr|v1.2.4|间接依赖|go|
|github.com/monochromegane/go-gitignore|v0.0.0-20200626010858-205db1a8cc00|间接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.6|间接依赖|go|
|go.etcd.io/etcd/client/v3|v3.5.9|直接依赖|go|
|github.com/hashicorp/go-multierror|v1.1.1|间接依赖|go|
|github.com/containerd/go-runc|v1.0.0|间接依赖|go|
|github.com/docker/go-units|v0.5.0|间接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.3|间接依赖|go|
|github.com/evanphx/json-patch|v5.6.0+incompatible|间接依赖|go|
|github.com/syndtr/gocapability|v0.0.0-20200815063812-42c35b437635|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|github.com/coreos/go-systemd/v22|v22.5.0|间接依赖|go|
|github.com/containerd/nri|v0.3.0|间接依赖|go|
|k8s.io/mount-utils|v0.28.1|间接依赖|go|
|github.com/opencontainers/image-spec|v1.1.0-rc3|间接依赖|go|
|github.com/containerd/imgcrypt|v1.1.7|间接依赖|go|
|github.com/google/cel-go|v0.16.0|间接依赖|go|
|github.com/Azure/go-autorest|v14.2.0+incompatible|间接依赖|go|
|github.com/go-sql-driver/mysql|v1.7.1|直接依赖|go|
|k8s.io/utils|v0.0.0-20230406110748-d93618cff8a2|直接依赖|go|
|github.com/daviddengcn/go-colortext|v1.0.0|间接依赖|go|
|github.com/containerd/fuse-overlayfs-snapshotter|v1.0.5|直接依赖|go|
|go.opentelemetry.io/otel/metric|v0.37.0|间接依赖|go|
|github.com/gofrs/uuid|v4.4.0+incompatible|间接依赖|go|
|k8s.io/component-base|v0.28.1|直接依赖|go|
|go.opentelemetry.io/otel|v1.14.0|间接依赖|go|
|github.com/docker/cli|v23.0.3+incompatible|间接依赖|go|
|go.etcd.io/etcd/server/v3|v3.5.9|直接依赖|go|
|github.com/natefinch/lumberjack|v2.0.0+incompatible|直接依赖|go|
|github.com/moby/ipvs|v1.1.0|间接依赖|go|
|github.com/containernetworking/cni|v1.1.2|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|间接依赖|go|
|github.com/rancher/remotedialer|v0.3.0|直接依赖|go|
|go.etcd.io/etcd/api/v3|v3.5.9|直接依赖|go|
|k8s.io/endpointslice|v0.0.0|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/golang/mock|v1.6.0|间接依赖|go|
|sigs.k8s.io/json|v0.0.0-20221116044647-bc3834ca7abd|间接依赖|go|
|github.com/grpc-ecosystem/go-grpc-prometheus|v1.2.0|间接依赖|go|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|github.com/go-bindata/go-bindata|v3.1.2+incompatible|直接依赖|go|
|golang.zx2c4.com/wireguard/wgctrl|v0.0.0-20230429144221-925a1e7659e6|间接依赖|go|
|github.com/Azure/go-autorest/tracing|v0.6.0|间接依赖|go|
|github.com/godbus/dbus/v5|v5.1.0|间接依赖|go|
|go.opencensus.io|v0.24.0|间接依赖|go|
|github.com/opencontainers/runtime-spec|v1.1.0-rc.1|间接依赖|go|
|inet.af/tcpproxy|v0.0.0-20200125044825-b6bb9b5b8252|直接依赖|go|
|github.com/containers/ocicrypt|v1.1.6|间接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/google.golang.org/grpc/otelgrpc|v0.40.0|间接依赖|go|
|golang.org/x/oauth2|v0.11.0|间接依赖|go|
|github.com/Microsoft/go-winio|v0.6.1|间接依赖|go|
|github.com/google/gnostic-models|v0.6.8|间接依赖|go|
|gopkg.in/gcfg.v1|v1.2.3|间接依赖|go|
|k8s.io/metrics|v0.0.0|间接依赖|go|
|github.com/docker/distribution|v2.8.2+incompatible|间接依赖|go|
|github.com/urfave/cli|v1.22.12|直接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway|v1.16.0|间接依赖|go|
|k8s.io/dynamic-resource-allocation|v0.0.0|间接依赖|go|
|gopkg.in/warnings.v0|v0.1.2|间接依赖|go|
|github.com/rootless-containers/rootlesskit|v1.0.1|直接依赖|go|
|github.com/moby/locker|v1.0.1|间接依赖|go|
|github.com/stoewer/go-strcase|v1.2.0|间接依赖|go|
|github.com/gregjones/httpcache|v0.0.0-20180305231024-9cad4c3443a7|间接依赖|go|
|github.com/rs/xid|v1.4.0|间接依赖|go|
|github.com/go-task/slim-sprig|v0.0.0-20230315185526-52ccab3ef572|间接依赖|go|
|cloud.google.com/go/compute/metadata|v0.2.3|间接依赖|go|
|golang.org/x/sys|v0.11.0|直接依赖|go|
|github.com/google/s2a-go|v0.1.5|间接依赖|go|
|sigs.k8s.io/apiserver-network-proxy/konnectivity-client|v0.1.2|间接依赖|go|
|golang.zx2c4.com/wireguard|v0.0.0-20230325221338-052af4a8072b|间接依赖|go|
|k8s.io/pod-security-admission|v0.0.0|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|间接依赖|go|
|github.com/cilium/ebpf|v0.9.1|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20230717233707-2695361300d9|间接依赖|go|
|github.com/containerd/fifo|v1.1.0|间接依赖|go|
|k8s.io/kube-aggregator|v0.28.1|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|github.com/moby/spdystream|v0.2.0|间接依赖|go|
|github.com/emicklei/go-restful|v2.16.0+incompatible|间接依赖|go|
|github.com/morikuni/aec|v1.0.0|间接依赖|go|
|golang.org/x/tools|v0.8.0|间接依赖|go|
|k8s.io/api|v0.28.1|直接依赖|go|
|github.com/container-orchestrated-devices/container-device-interface|v0.5.4|间接依赖|go|
|github.com/imdario/mergo|v0.3.13|间接依赖|go|
|google.golang.org/protobuf|v1.31.0|间接依赖|go|
|k8s.io/kube-proxy|v0.0.0|间接依赖|go|
|github.com/vbatts/tar-split|v0.11.2|间接依赖|go|
|github.com/google/go-containerregistry|v0.7.0|间接依赖|go|
|github.com/lithammer/dedent|v1.1.0|间接依赖|go|
|github.com/jackc/pgpassfile|v1.0.0|间接依赖|go|
|github.com/nats-io/nkeys|v0.4.4|间接依赖|go|
|github.com/containernetworking/plugins|v1.2.0|间接依赖|go|
|github.com/google/shlex|v0.0.0-20191202100458-e7afc7fbc510|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/karrick/godirwalk|v1.17.0|间接依赖|go|
|github.com/Azure/go-autorest/autorest/adal|v0.9.23|间接依赖|go|
|github.com/NYTimes/gziphandler|v1.1.1|间接依赖|go|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|github.com/klauspost/cpuid/v2|v2.1.0|间接依赖|go|
|k8s.io/klog/v2|v2.100.1|直接依赖|go|
|github.com/checkpoint-restore/go-criu/v5|v5.3.0|间接依赖|go|
|github.com/containerd/zfs|v1.1.0|直接依赖|go|
|github.com/mistifyio/go-zfs|v2.1.2-0.20190413222219-f784269be439+incompatible|间接依赖|go|
|github.com/moby/sys/signal|v0.7.0|间接依赖|go|
|github.com/euank/go-kmsg-parser|v2.0.0+incompatible|间接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|github.com/flannel-io/flannel|v0.22.2|直接依赖|go|
|github.com/cloudnativelabs/kube-router/v2|v2.0.0-00010101000000-000000000000|直接依赖|go|
|github.com/blang/semver|v3.5.1+incompatible|间接依赖|go|
|github.com/avast/retry-go/v4|v4.3.2|间接依赖|go|
|go.uber.org/zap|v1.24.0|直接依赖|go|
|github.com/Azure/go-autorest/autorest/to|v0.4.0|间接依赖|go|
|github.com/vishvananda/netlink|v1.2.1-beta.2|直接依赖|go|
|github.com/go-errors/errors|v1.4.2|间接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|go.opentelemetry.io/otel/sdk|v1.14.0|间接依赖|go|
|github.com/seccomp/libseccomp-golang|v0.10.0|间接依赖|go|
|github.com/xiang90/probing|v0.0.0-20221125231312-a49e3df8f510|间接依赖|go|
|github.com/rancher/wharfie|v0.5.3|直接依赖|go|
|github.com/fvbommel/sortorder|v1.1.0|间接依赖|go|
|github.com/nats-io/nats-server/v2|v2.9.18|间接依赖|go|
|github.com/containerd/typeurl|v1.0.2|间接依赖|go|
|cloud.google.com/go/compute|v1.23.0|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)