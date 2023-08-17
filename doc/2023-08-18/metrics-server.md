# kubernetes-sigs/metrics-server安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692238554052976640.svg)](https://www.murphysec.com/console/report/1684752160088211456/1692238554052976640)

仓库描述：Scalable and efficient source of container resource metrics for Kubernetes built-in autoscaling pipelines.

仓库地址：[https://github.com/kubernetes-sigs/metrics-server](https://github.com/kubernetes-sigs/metrics-server)

| star：4877 | watch：90 | fork：1750 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-17 21:28:11 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-18 02:14:49 | 组件总数：114 | 漏洞总数：0 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |





## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |





## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|29|Low|
|BSD-2-Clause|3|Low|
|Apache-2.0|61|Low|
|MIT|25|Low|
|ISC|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|golang.org/x/oauth2|v0.4.0|间接依赖|go|
|github.com/mmarkdown/mmark|v2.0.40+incompatible|间接依赖|go|
|github.com/moby/spdystream|v0.2.0|间接依赖|go|
|go.uber.org/multierr|v1.6.0|间接依赖|go|
|google.golang.org/grpc|v1.53.0|间接依赖|go|
|github.com/antlr/antlr4/runtime/Go/antlr|v1.4.10|间接依赖|go|
|github.com/felixge/httpsnoop|v1.0.3|间接依赖|go|
|github.com/blang/semver/v4|v4.0.0|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.0.1|间接依赖|go|
|github.com/bmatcuk/doublestar/v4|v4.0.2|间接依赖|go|
|go.opentelemetry.io/otel/trace|v1.10.0|间接依赖|go|
|google.golang.org/protobuf|v1.28.1|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|间接依赖|go|
|golang.org/x/exp|v0.0.0-20210220032938-85be41e4509f|间接依赖|go|
|k8s.io/klog/v2|v2.90.1|直接依赖|go|
|github.com/prometheus/client_model|v0.3.0|间接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|k8s.io/component-base|v0.27.2|直接依赖|go|
|github.com/asaskevich/govalidator|v0.0.0-20200907205600-7a23bdc65eef|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway/v2|v2.7.0|间接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.6|间接依赖|go|
|github.com/grpc-ecosystem/go-grpc-prometheus|v1.2.0|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/prometheus/prometheus|v0.0.0-20220129212040-344a13d96087|直接依赖|go|
|github.com/google/gnostic|v0.5.7-v3refs|间接依赖|go|
|github.com/go-logr/logr|v1.2.3|间接依赖|go|
|gopkg.in/natefinch/lumberjack.v2|v2.0.0|间接依赖|go|
|golang.org/x/tools|v0.7.0|间接依赖|go|
|go.opentelemetry.io/otel/metric|v0.31.0|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230110181048-76db0878b65f|间接依赖|go|
|k8s.io/apiserver|v0.27.2|直接依赖|go|
|sigs.k8s.io/json|v0.0.0-20221116044647-bc3834ca7abd|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace/otlptracegrpc|v1.10.0|间接依赖|go|
|golang.org/x/time|v0.0.0-20220210224613-90d013bbcef8|间接依赖|go|
|golang.org/x/sync|v0.1.0|间接依赖|go|
|github.com/onsi/ginkgo|v1.14.0|直接依赖|go|
|github.com/emicklei/go-restful/v3|v3.9.0|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20230501164219-8b0f38b5fd1f|直接依赖|go|
|golang.org/x/net|v0.8.0|间接依赖|go|
|golang.org/x/mod|v0.9.0|间接依赖|go|
|go.etcd.io/etcd/client/v3|v3.5.7|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/internal/retry|v1.10.0|间接依赖|go|
|github.com/coreos/go-systemd/v22|v22.4.0|间接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.3|间接依赖|go|
|github.com/go-logr/zapr|v1.2.3|间接依赖|go|
|k8s.io/kms|v0.27.2|间接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.1|间接依赖|go|
|k8s.io/gengo|v0.0.0-20220902162205-c0856e24416d|间接依赖|go|
|github.com/stoewer/go-strcase|v1.2.0|间接依赖|go|
|k8s.io/client-go|v0.27.2|直接依赖|go|
|golang.org/x/sys|v0.6.0|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|github.com/google/gofuzz|v1.1.0|间接依赖|go|
|k8s.io/api|v0.27.2|直接依赖|go|
|github.com/spf13/cobra|v1.6.0|直接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.2|间接依赖|go|
|golang.org/x/crypto|v0.1.0|间接依赖|go|
|github.com/google/cel-go|v0.12.6|间接依赖|go|
|k8s.io/utils|v0.0.0-20230209194617-a36077c30491|间接依赖|go|
|github.com/cenkalti/backoff/v4|v4.1.3|间接依赖|go|
|go.uber.org/atomic|v1.9.0|间接依赖|go|
|github.com/moby/term|v0.0.0-20221205130635-1aeaba878587|间接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|github.com/imdario/mergo|v0.3.12|间接依赖|go|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|github.com/coreos/go-semver|v0.3.0|间接依赖|go|
|golang.org/x/perf|v0.0.0-20210220033136-40a54f11e909|直接依赖|go|
|github.com/NYTimes/gziphandler|v1.1.1|间接依赖|go|
|github.com/mitchellh/mapstructure|v1.4.1|间接依赖|go|
|go.uber.org/zap|v1.19.0|间接依赖|go|
|go.opentelemetry.io/proto/otlp|v0.19.0|间接依赖|go|
|go.opentelemetry.io/otel|v1.10.0|间接依赖|go|
|github.com/nxadm/tail|v1.4.4|间接依赖|go|
|k8s.io/metrics|v0.27.2|直接依赖|go|
|go.etcd.io/etcd/client/pkg/v3|v3.5.7|间接依赖|go|
|github.com/google/uuid|v1.3.0|间接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/google.golang.org/grpc/otelgrpc|v0.35.0|间接依赖|go|
|sigs.k8s.io/apiserver-network-proxy/konnectivity-client|v0.1.2|间接依赖|go|
|github.com/google/addlicense|v1.0.0|直接依赖|go|
|go.etcd.io/etcd/api/v3|v3.5.7|间接依赖|go|
|golang.org/x/term|v0.6.0|间接依赖|go|
|github.com/prometheus/procfs|v0.8.0|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|github.com/gomarkdown/markdown|v0.0.0-20200824053859-8c8b3816f167|间接依赖|go|
|github.com/Azure/go-ansiterm|v0.0.0-20210617225240-d185dfc1b5a1|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|sigs.k8s.io/logtools|v0.4.1|直接依赖|go|
|github.com/evanphx/json-patch|v4.12.0+incompatible|间接依赖|go|
|k8s.io/apimachinery|v0.27.2|直接依赖|go|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/onsi/gomega|v1.27.4|直接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace|v1.10.0|间接依赖|go|
|sigs.k8s.io/yaml|v1.3.0|间接依赖|go|
|github.com/prometheus/client_golang|v1.14.0|间接依赖|go|
|github.com/BurntSushi/toml|v0.3.1|间接依赖|go|
|sigs.k8s.io/mdtoc|v1.0.1|直接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|go.opentelemetry.io/otel/sdk|v1.10.0|间接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/net/http/otelhttp|v0.35.1|间接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|github.com/prometheus/common|v0.37.0|直接依赖|go|
|github.com/go-openapi/swag|v0.22.3|间接依赖|go|
|gopkg.in/tomb.v1|v1.0.0-20141024135613-dd632973f1e7|间接依赖|go|
|golang.org/x/text|v0.8.0|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)