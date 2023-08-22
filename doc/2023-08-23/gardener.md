# gardener/gardener安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694050495831109632.svg)](https://www.murphysec.com/console/report/1694050495684308992/1694050495831109632)

仓库描述：Kubernetes-native system managing the full lifecycle of conformant Kubernetes clusters as a service on Alicloud, AWS, Azure, GCP, OpenStack, vSphere, KubeVirt, Hetzner, EquinixMetal, MetalStack, and OnMetal with minimal TCO.

仓库地址：[https://github.com/gardener/gardener](https://github.com/gardener/gardener)

| star：2586 | watch：73 | fork：436 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-23 00:02:20 | 许可证：NOASSERTION |
| 最近检测时间：2023-08-23 02:20:23 | 组件总数：176 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Kubernetes 授权问题漏洞|身份验证不当|[MPS-2020-10898](https://www.oscs1024.com/hd/MPS-2020-10898)|CVE-2020-8558|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|k8s.io/kube-proxy|v0.26.3|1.18.4|直接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|49|Low|
|BSD-3-Clause|40|Low|
|Apache-2.0|86|Low|
|BSD-2-Clause|5|Low|
|MPL-2.0|4|Low|
|ISC|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/Masterminds/semver|v1.5.0|直接依赖|go|
|github.com/go-task/slim-sprig|v0.0.0-20230315185526-52ccab3ef572|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|google.golang.org/grpc|v1.53.0|间接依赖|go|
|k8s.io/autoscaler/vertical-pod-autoscaler|v0.14.0|直接依赖|go|
|sigs.k8s.io/json|v0.0.0-20220713155537-f223a00ba0e2|间接依赖|go|
|golang.org/x/mod|v0.9.0|间接依赖|go|
|go.uber.org/zap|v1.24.0|直接依赖|go|
|github.com/imdario/mergo|v0.3.12|间接依赖|go|
|github.com/kubernetes-csi/external-snapshotter/client/v4|v4.2.0|直接依赖|go|
|github.com/pelletier/go-toml|v1.9.4|间接依赖|go|
|gopkg.in/ini.v1|v1.66.4|间接依赖|go|
|github.com/pierrec/lz4|v2.6.1+incompatible|间接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.5|间接依赖|go|
|k8s.io/kms|v0.26.3|间接依赖|go|
|github.com/gardener/machine-controller-manager|v0.48.1|直接依赖|go|
|github.com/ulikunitz/xz|v0.5.10|间接依赖|go|
|github.com/spf13/jwalterweatherman|v1.1.0|间接依赖|go|
|golang.org/x/net|v0.8.0|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|golang.org/x/exp|v0.0.0-20230510235704-dd950f8aeaea|直接依赖|go|
|github.com/onsi/gomega|v1.27.6|直接依赖|go|
|go.etcd.io/etcd/api/v3|v3.5.5|间接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.0|间接依赖|go|
|github.com/NYTimes/gziphandler|v1.1.1|间接依赖|go|
|github.com/mitchellh/copystructure|v1.2.0|间接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/net/http/otelhttp|v0.35.0|间接依赖|go|
|github.com/mitchellh/reflectwalk|v1.0.2|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|github.com/xi2/xz|v0.0.0-20171230120015-48954b6210f8|间接依赖|go|
|github.com/spf13/cobra|v1.6.1|直接依赖|go|
|k8s.io/klog/v2|v2.90.1|直接依赖|go|
|github.com/huandu/xstrings|v1.3.2|间接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/ghodss/yaml|v1.0.0|间接依赖|go|
|golang.org/x/sys|v0.6.0|间接依赖|go|
|github.com/subosito/gotenv|v1.2.0|间接依赖|go|
|golang.org/x/text|v0.8.0|直接依赖|go|
|github.com/gogo/protobuf|v1.3.2|直接依赖|go|
|sigs.k8s.io/apiserver-network-proxy/konnectivity-client|v0.0.36|间接依赖|go|
|k8s.io/component-helpers|v0.26.3|直接依赖|go|
|k8s.io/metrics|v0.26.3|直接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|golang.org/x/oauth2|v0.4.0|间接依赖|go|
|k8s.io/code-generator|v0.26.3|直接依赖|go|
|github.com/go-openapi/errors|v0.20.3|间接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.3|间接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.2|间接依赖|go|
|istio.io/api|v0.0.0-20230217221049-9d422bf48675|直接依赖|go|
|k8s.io/kube-aggregator|v0.26.3|直接依赖|go|
|go.uber.org/goleak|v1.2.0|直接依赖|go|
|k8s.io/apimachinery|v0.26.3|直接依赖|go|
|github.com/google/gnostic|v0.5.7-v3refs|直接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|go.etcd.io/etcd/client/pkg/v3|v3.5.5|间接依赖|go|
|golang.org/x/term|v0.6.0|间接依赖|go|
|github.com/moby/spdystream|v0.2.0|间接依赖|go|
|k8s.io/utils|v0.0.0-20221128185143-99ec85e7a448|直接依赖|go|
|github.com/golang/snappy|v0.0.4|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.12|间接依赖|go|
|github.com/evanphx/json-patch/v5|v5.6.0|间接依赖|go|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|sigs.k8s.io/controller-runtime/tools/setup-envtest|v0.0.0-20221212190805-d4f1e822ca11|直接依赖|go|
|github.com/felixge/httpsnoop|v1.0.3|间接依赖|go|
|github.com/spf13/cast|v1.4.1|间接依赖|go|
|github.com/nwaples/rardecode|v1.1.2|间接依赖|go|
|github.com/emicklei/go-restful/v3|v3.10.1|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/internal/retry|v1.10.0|间接依赖|go|
|go.uber.org/automaxprocs|v1.5.1|直接依赖|go|
|golang.org/x/sync|v0.1.0|间接依赖|go|
|github.com/gobwas/glob|v0.2.3|间接依赖|go|
|k8s.io/kubelet|v0.26.3|直接依赖|go|
|github.com/dsnet/compress|v0.0.1|间接依赖|go|
|github.com/google/cel-go|v0.12.6|间接依赖|go|
|github.com/mailru/easyjson|v0.7.6|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace/otlptracegrpc|v1.10.0|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.0.1|间接依赖|go|
|github.com/gardener/hvpa-controller/api|v0.5.0|直接依赖|go|
|golang.org/x/sys|v0.11.0|间接依赖|go|
|github.com/antlr/antlr4/runtime/Go/antlr|v1.4.10|间接依赖|go|
|k8s.io/apiserver|v0.26.3|直接依赖|go|
|github.com/mitchellh/hashstructure/v2|v2.0.2|直接依赖|go|
|k8s.io/kube-proxy|v0.26.3|直接依赖|go|
|github.com/mholt/archiver|v3.1.1+incompatible|直接依赖|go|
|github.com/hashicorp/errwrap|v1.0.0|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|github.com/evanphx/json-patch|v4.12.0+incompatible|间接依赖|go|
|sigs.k8s.io/controller-runtime|v0.14.6|直接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|go.uber.org/atomic|v1.9.0|间接依赖|go|
|go.opentelemetry.io/otel|v1.10.0|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230110181048-76db0878b65f|间接依赖|go|
|github.com/gobuffalo/flect|v0.3.0|间接依赖|go|
|github.com/onsi/ginkgo/v2|v2.9.2|直接依赖|go|
|github.com/prometheus/procfs|v0.8.0|间接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|github.com/hashicorp/go-multierror|v1.1.1|直接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/google.golang.org/grpc/otelgrpc|v0.35.0|间接依赖|go|
|golang.org/x/time|v0.3.0|直接依赖|go|
|k8s.io/cluster-bootstrap|v0.26.3|直接依赖|go|
|sigs.k8s.io/controller-tools|v0.11.3|直接依赖|go|
|github.com/go-logr/logr|v1.2.4|直接依赖|go|
|github.com/prometheus/client_model|v0.3.0|间接依赖|go|
|k8s.io/gengo|v0.0.0-20220902162205-c0856e24416d|间接依赖|go|
|github.com/Masterminds/sprig|v2.22.0+incompatible|直接依赖|go|
|github.com/elazarl/goproxy|v0.0.0-20191011121108-aa519ddbe484|间接依赖|go|
|github.com/go-logr/zapr|v1.2.3|间接依赖|go|
|go.opentelemetry.io/otel/sdk|v1.10.0|间接依赖|go|
|github.com/pelletier/go-toml/v2|v2.0.0-beta.8|间接依赖|go|
|k8s.io/helm|v2.16.1+incompatible|直接依赖|go|
|github.com/fatih/color|v1.13.0|间接依赖|go|
|gopkg.in/natefinch/lumberjack.v2|v2.0.0|间接依赖|go|
|github.com/bronze1man/yaml2json|v0.0.0-20211227013850-8972abeaea25|直接依赖|go|
|k8s.io/api|v0.26.3|直接依赖|go|
|golang.org/x/crypto|v0.6.0|直接依赖|go|
|gomodules.xyz/jsonpatch/v2|v2.2.0|直接依赖|go|
|github.com/cyphar/filepath-securejoin|v0.2.2|间接依赖|go|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/frankban/quicktest|v1.14.4|间接依赖|go|
|github.com/magiconair/properties|v1.8.6|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20221012153701-172d655c2280|直接依赖|go|
|k8s.io/apiextensions-apiserver|v0.26.3|直接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace|v1.10.0|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|github.com/spf13/afero|v1.8.2|间接依赖|go|
|k8s.io/component-base|v0.26.3|直接依赖|go|
|github.com/prometheus/client_golang|v1.14.0|直接依赖|go|
|k8s.io/pod-security-admission|v0.26.3|直接依赖|go|
|github.com/robfig/cron|v1.2.0|直接依赖|go|
|google.golang.org/protobuf|v1.28.1|直接依赖|go|
|sigs.k8s.io/yaml|v1.3.0|直接依赖|go|
|github.com/ahmetb/gen-crd-api-reference-docs|v0.3.0|直接依赖|go|
|github.com/BurntSushi/toml|v1.0.0|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|间接依赖|go|
|github.com/coreos/go-semver|v0.3.0|间接依赖|go|
|github.com/prometheus/common|v0.37.0|间接依赖|go|
|github.com/spf13/viper|v1.11.0|直接依赖|go|
|github.com/grpc-ecosystem/go-grpc-prometheus|v1.2.0|间接依赖|go|
|github.com/cenkalti/backoff/v4|v4.1.3|间接依赖|go|
|github.com/google/gofuzz|v1.1.0|间接依赖|go|
|go.uber.org/mock|v0.2.0|直接依赖|go|
|github.com/coreos/go-systemd/v22|v22.3.2|直接依赖|go|
|go.opentelemetry.io/otel/trace|v1.10.0|间接依赖|go|
|github.com/blang/semver/v4|v4.0.0|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway/v2|v2.7.0|间接依赖|go|
|github.com/gardener/etcd-druid|v0.19.2|直接依赖|go|
|github.com/mitchellh/mapstructure|v1.4.3|间接依赖|go|
|github.com/gardener/dependency-watchdog|v1.1.2|直接依赖|go|
|golang.org/x/mod|v0.12.0|间接依赖|go|
|go.opentelemetry.io/otel/metric|v0.31.0|间接依赖|go|
|k8s.io/client-go|v0.26.3|直接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|istio.io/client-go|v1.17.1|直接依赖|go|
|gonum.org/v1/gonum|v0.12.0|直接依赖|go|
|github.com/mattn/go-isatty|v0.0.14|间接依赖|go|
|k8s.io/klog|v1.0.0|间接依赖|go|
|go.uber.org/multierr|v1.7.0|间接依赖|go|
|github.com/fluent/fluent-operator/v2|v2.2.0|直接依赖|go|
|github.com/texttheater/golang-levenshtein|v1.0.1|直接依赖|go|
|github.com/google/pprof|v0.0.0-20210720184732-4bb14d4b1be1|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|golang.org/x/tools|v0.12.0|直接依赖|go|
|github.com/Masterminds/goutils|v1.1.1|间接依赖|go|
|github.com/russross/blackfriday/v2|v2.1.0|间接依赖|go|
|github.com/go-test/deep|v1.1.0|直接依赖|go|
|golang.org/x/tools|v0.7.0|直接依赖|go|
|go.opentelemetry.io/proto/otlp|v0.19.0|间接依赖|go|
|github.com/go-openapi/swag|v0.19.14|间接依赖|go|
|go.etcd.io/etcd/client/v3|v3.5.5|间接依赖|go|
|github.com/google/uuid|v1.3.0|间接依赖|go|
|github.com/stoewer/go-strcase|v1.2.0|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)