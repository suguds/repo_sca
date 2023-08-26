# kubernetes/autoscaler安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695499389995741184.svg)](https://www.murphysec.com/console/report/1695499389907660800/1695499389995741184)

仓库描述：Autoscaling components for Kubernetes

仓库地址：[https://github.com/kubernetes/autoscaler](https://github.com/kubernetes/autoscaler)

| star：7015 | watch：144 | fork：3584 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-26 02:23:25 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-27 02:24:33 | 组件总数：295 | 漏洞总数：6 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Kubernetes 输入验证错误漏洞|访问控制不当|[MPS-2019-15838](https://www.oscs1024.com/hd/MPS-2019-15838)|CVE-2019-11255|中危|
|go.uuid 不安全的随机性漏洞|使用具有密码学弱点缺陷的PRNG|[MPS-2021-7854](https://www.oscs1024.com/hd/MPS-2021-7854)|CVE-2021-3538|严重|
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58307](https://www.oscs1024.com/hd/MPS-2022-58307)|CVE-2022-41723|高危|
|Google Go 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2022-9049](https://www.oscs1024.com/hd/MPS-2022-9049)|CVE-2022-29526|中危|
|runc 安全漏洞|使用不正确的解析名称或索引|[MPS-2023-6887](https://www.oscs1024.com/hd/MPS-2023-6887)|CVE-2023-27561|高危|
|runc <1.1.5 AppArmor限制绕过漏洞|访问控制不当|[MPS-2023-8507](https://www.oscs1024.com/hd/MPS-2023-8507)|CVE-2023-28642|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|golang.org/x/net|v0.3.1-0.20221206200815-1e63c2f08a10|0.7.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|github.com/satori/go.uuid|v1.2.0||直接依赖|建议修复|C:1|H:0|M:0|L:0|
|github.com/opencontainers/runc|v1.1.4|1.1.5|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|golang.org/x/net|v0.0.0-20220722155237-a158d28d115b|0.7.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|golang.org/x/sys|v0.0.0-20220722155257-8c9f86f7a55f|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|k8s.io/kubernetes|v1.28.0-beta.0||直接依赖|可选修复|C:0|H:0|M:1|L:0|
|k8s.io/kubernetes|v1.26.1||直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|48|Low|
|BSD-2-Clause|9|Low|
|ISC|2|Low|
|BSD-3-Clause|66|Low|
|Apache-2.0|177|Low|
|CC-BY-SA-4.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/Azure/go-autorest|v14.2.0+incompatible|间接依赖|go|
|github.com/cilium/ebpf|v0.9.1|间接依赖|go|
|gopkg.in/warnings.v0|v0.1.2|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|github.com/vishvananda/netlink|v1.1.0|间接依赖|go|
|github.com/Azure/go-autorest/autorest/validation|v0.3.1|间接依赖|go|
|github.com/google/cadvisor|v0.46.0|间接依赖|go|
|github.com/prometheus/client_model|v0.4.0|间接依赖|go|
|github.com/checkpoint-restore/go-criu/v5|v5.3.0|间接依赖|go|
|golang.org/x/oauth2|v0.8.0|直接依赖|go|
|github.com/moby/spdystream|v0.2.0|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace|v1.14.0|间接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.0|间接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|直接依赖|go|
|go.opentelemetry.io/proto/otlp|v0.19.0|间接依赖|go|
|github.com/gofrs/uuid|v4.4.0+incompatible|直接依赖|go|
|gopkg.in/natefinch/lumberjack.v2|v2.2.1|间接依赖|go|
|k8s.io/kubectl|v0.0.0|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/internal/retry|v1.14.0|间接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.2|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20230717233707-2695361300d9|间接依赖|go|
|go.opentelemetry.io/otel|v1.10.0|间接依赖|go|
|k8s.io/mount-utils|v0.25.0|间接依赖|go|
|github.com/prometheus/procfs|v0.8.0|间接依赖|go|
|github.com/PuerkitoBio/purell|v1.1.1|间接依赖|go|
|k8s.io/kubernetes|v1.26.1|直接依赖|go|
|github.com/blang/semver/v4|v4.0.0|间接依赖|go|
|k8s.io/component-base|v0.25.0|直接依赖|go|
|cloud.google.com/go|v0.97.0|间接依赖|go|
|sigs.k8s.io/json|v0.0.0-20220713155537-f223a00ba0e2|间接依赖|go|
|github.com/Microsoft/go-winio|v0.4.17|间接依赖|go|
|github.com/googleapis/gax-go/v2|v2.1.1|间接依赖|go|
|golang.org/x/sys|v0.6.0|间接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.3|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|k8s.io/csi-translation-lib|v0.26.1|间接依赖|go|
|github.com/opencontainers/runc|v1.1.4|间接依赖|go|
|github.com/containerd/ttrpc|v1.2.2|间接依赖|go|
|go.opentelemetry.io/otel/metric|v0.37.0|间接依赖|go|
|k8s.io/utils|v0.0.0-20221107191617-1a15be271d1d|直接依赖|go|
|google.golang.org/grpc|v1.54.0|直接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|github.com/Microsoft/hcsshim|v0.8.22|间接依赖|go|
|go.etcd.io/etcd/client/v3|v3.5.9|间接依赖|go|
|github.com/golang/mock|v1.6.0|直接依赖|go|
|github.com/GoogleCloudPlatform/k8s-cloud-provider|v1.18.1-0.20220218231025-f11817397a1b|间接依赖|go|
|golang.org/x/text|v0.3.7|间接依赖|go|
|go.etcd.io/etcd/api/v3|v3.5.9|间接依赖|go|
|github.com/docker/distribution|v2.8.1+incompatible|间接依赖|go|
|github.com/prometheus/common|v0.37.0|直接依赖|go|
|sigs.k8s.io/apiserver-network-proxy/konnectivity-client|v0.1.2|间接依赖|go|
|github.com/satori/go.uuid|v1.2.0|直接依赖|go|
|github.com/syndtr/gocapability|v0.0.0-20200815063812-42c35b437635|间接依赖|go|
|go.opentelemetry.io/otel/trace|v1.10.0|间接依赖|go|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|github.com/google/gofuzz|v1.1.0|间接依赖|go|
|github.com/evanphx/json-patch|v5.6.0+incompatible|间接依赖|go|
|k8s.io/apiserver|v0.28.0-beta.0|直接依赖|go|
|golang.org/x/term|v0.10.0|间接依赖|go|
|github.com/spf13/cobra|v1.6.0|间接依赖|go|
|github.com/emicklei/go-restful/v3|v3.8.0|间接依赖|go|
|sigs.k8s.io/cloud-provider-azure|v1.26.2|直接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|google.golang.org/api|v0.114.0|直接依赖|go|
|github.com/onsi/ginkgo/v2|v2.4.0|直接依赖|go|
|github.com/cyphar/filepath-securejoin|v0.2.3|间接依赖|go|
|go.opencensus.io|v0.24.0|间接依赖|go|
|github.com/containerd/cgroups|v1.1.0|间接依赖|go|
|github.com/digitalocean/godo|v1.27.0|直接依赖|go|
|k8s.io/klog/v2|v2.80.1|直接依赖|go|
|github.com/imdario/mergo|v0.3.6|间接依赖|go|
|cloud.google.com/go/compute/metadata|v0.2.3|直接依赖|go|
|k8s.io/client-go|v0.26.1|直接依赖|go|
|k8s.io/mount-utils|v0.26.0-alpha.0|间接依赖|go|
|github.com/coreos/go-semver|v0.3.1|间接依赖|go|
|github.com/mxk/go-flowrate|v0.0.0-20140419014527-cca7078d478f|间接依赖|go|
|go.etcd.io/etcd/client/pkg/v3|v3.5.9|间接依赖|go|
|github.com/moby/ipvs|v1.1.0|间接依赖|go|
|golang.org/x/text|v0.11.0|间接依赖|go|
|github.com/antlr/antlr4/runtime/Go/antlr/v4|v4.0.0-20230321174746-8dcc6526cfb1|间接依赖|go|
|golang.org/x/text|v0.8.0|间接依赖|go|
|k8s.io/cri-api|v0.0.0|间接依赖|go|
|github.com/seccomp/libseccomp-golang|v0.9.2-0.20220502022130-f33da4d89646|间接依赖|go|
|github.com/prometheus/client_model|v0.3.0|间接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|直接依赖|go|
|k8s.io/legacy-cloud-providers|v0.0.0|直接依赖|go|
|github.com/prometheus/common|v0.44.0|间接依赖|go|
|github.com/coreos/go-systemd/v22|v22.5.0|间接依赖|go|
|golang.org/x/net|v0.0.0-20220722155237-a158d28d115b|间接依赖|go|
|github.com/go-openapi/swag|v0.22.3|间接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230525234030-28d5490b6b19|间接依赖|go|
|k8s.io/cloud-provider|v0.26.1|间接依赖|go|
|github.com/NYTimes/gziphandler|v1.1.1|间接依赖|go|
|google.golang.org/grpc|v1.49.0|间接依赖|go|
|cloud.google.com/go/compute|v1.19.0|间接依赖|go|
|github.com/aws/aws-sdk-go|v1.44.116|间接依赖|go|
|k8s.io/client-go|v0.28.0-beta.0|直接依赖|go|
|k8s.io/client-go|v11.0.0+incompatible|直接依赖|go|
|go.opencensus.io|v0.23.0|间接依赖|go|
|github.com/asaskevich/govalidator|v0.0.0-20230301143203-a9d515a09cc2|间接依赖|go|
|golang.org/x/sys|v0.10.0|直接依赖|go|
|github.com/go-logr/logr|v1.2.4|间接依赖|go|
|github.com/Azure/go-autorest/autorest|v0.11.29|直接依赖|go|
|github.com/Azure/go-autorest/autorest/mocks|v0.4.2|间接依赖|go|
|k8s.io/apiextensions-apiserver|v0.0.0|间接依赖|go|
|github.com/go-openapi/swag|v0.19.14|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|直接依赖|go|
|github.com/lithammer/dedent|v1.1.0|间接依赖|go|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|gopkg.in/gcfg.v1|v1.2.3|直接依赖|go|
|golang.org/x/net|v0.3.1-0.20221206200815-1e63c2f08a10|间接依赖|go|
|github.com/google/gofuzz|v1.2.0|间接依赖|go|
|github.com/mohae/deepcopy|v0.0.0-20170603005431-491d3605edfb|间接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway/v2|v2.15.2|间接依赖|go|
|github.com/google/cadvisor|v0.47.3|间接依赖|go|
|github.com/cenkalti/backoff/v4|v4.1.3|间接依赖|go|
|k8s.io/cloud-provider-aws|v1.27.0|直接依赖|go|
|google.golang.org/genproto|v0.0.0-20220502173005-c8bf987b8c21|间接依赖|go|
|google.golang.org/protobuf|v1.30.0|直接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.2|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|golang.org/x/crypto|v0.11.0|直接依赖|go|
|github.com/Azure/azure-sdk-for-go|v68.0.0+incompatible|直接依赖|go|
|github.com/moby/sys/mountinfo|v0.6.2|间接依赖|go|
|k8s.io/csi-translation-lib|v0.27.0|间接依赖|go|
|github.com/google/go-querystring|v1.0.0|直接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/google.golang.org/grpc/otelgrpc|v0.35.0|间接依赖|go|
|github.com/stretchr/testify|v1.8.2|直接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace/otlptracegrpc|v1.10.0|间接依赖|go|
|github.com/aws/aws-sdk-go|v1.44.241|直接依赖|go|
|github.com/inconshreveable/mousetrap|v1.0.1|间接依赖|go|
|github.com/onsi/gomega|v1.23.0|直接依赖|go|
|github.com/grpc-ecosystem/go-grpc-prometheus|v1.2.0|间接依赖|go|
|go.opentelemetry.io/otel/sdk|v1.14.0|间接依赖|go|
|k8s.io/kubelet|v0.28.0-beta.0|直接依赖|go|
|golang.org/x/sync|v0.0.0-20220722155255-886fb9371eb4|间接依赖|go|
|k8s.io/pod-security-admission|v0.0.0|直接依赖|go|
|github.com/googleapis/enterprise-certificate-proxy|v0.2.3|间接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway/v2|v2.7.0|间接依赖|go|
|github.com/sirupsen/logrus|v1.8.1|间接依赖|go|
|github.com/opencontainers/runc|v1.1.7|间接依赖|go|
|k8s.io/apimachinery|v0.28.0-beta.0|直接依赖|go|
|github.com/opencontainers/selinux|v1.10.0|间接依赖|go|
|github.com/sirupsen/logrus|v1.9.0|间接依赖|go|
|github.com/opencontainers/runtime-spec|v1.0.3-0.20220909204839-494a5a6aca78|间接依赖|go|
|k8s.io/component-base|v0.26.1|直接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|k8s.io/api|v0.28.0-beta.0|直接依赖|go|
|github.com/opencontainers/runtime-spec|v1.0.3-0.20210326190908-1c3f411f0417|间接依赖|go|
|go.opentelemetry.io/otel/metric|v0.31.0|间接依赖|go|
|sigs.k8s.io/apiserver-network-proxy/konnectivity-client|v0.0.35|间接依赖|go|
|github.com/felixge/httpsnoop|v1.0.3|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|k8s.io/utils|v0.0.0-20230406110748-d93618cff8a2|直接依赖|go|
|github.com/euank/go-kmsg-parser|v2.0.0+incompatible|间接依赖|go|
|github.com/evanphx/json-patch|v4.12.0+incompatible|间接依赖|go|
|k8s.io/apimachinery|v0.25.2|直接依赖|go|
|github.com/godbus/dbus/v5|v5.0.6|间接依赖|go|
|github.com/dimchansky/utfbom|v1.1.1|间接依赖|go|
|github.com/vishvananda/netns|v0.0.4|间接依赖|go|
|github.com/cenkalti/backoff/v4|v4.2.1|直接依赖|go|
|google.golang.org/protobuf|v1.28.0|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|github.com/prometheus/procfs|v0.10.1|间接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|golang.org/x/net|v0.8.0|间接依赖|go|
|github.com/emicklei/go-restful/v3|v3.10.1|间接依赖|go|
|github.com/google/uuid|v1.3.0|直接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20220803162953-67bda5d908f1|间接依赖|go|
|github.com/golang/protobuf|v1.5.2|间接依赖|go|
|golang.org/x/tools|v0.8.0|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20221012153701-172d655c2280|间接依赖|go|
|k8s.io/component-helpers|v0.26.1|间接依赖|go|
|golang.org/x/sys|v0.0.0-20220722155257-8c9f86f7a55f|间接依赖|go|
|github.com/Azure/skewer|v0.0.14|直接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/net/http/otelhttp|v0.40.0|间接依赖|go|
|github.com/stretchr/objx|v0.5.0|间接依赖|go|
|k8s.io/cloud-provider|v0.28.0-beta.0|直接依赖|go|
|github.com/rubiojr/go-vhd|v0.0.0-20200706105327-02e210299021|间接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/google.golang.org/grpc/otelgrpc|v0.40.0|间接依赖|go|
|github.com/Azure/go-autorest/autorest/date|v0.3.0|直接依赖|go|
|golang.org/x/time|v0.3.0|间接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0|间接依赖|go|
|github.com/cilium/ebpf|v0.7.0|间接依赖|go|
|github.com/google/gnostic|v0.5.7-v3refs|间接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/net/http/otelhttp|v0.35.0|间接依赖|go|
|github.com/spf13/cobra|v1.7.0|间接依赖|go|
|github.com/Azure/go-autorest/autorest/azure/cli|v0.4.2|间接依赖|go|
|github.com/containerd/cgroups|v1.0.1|间接依赖|go|
|github.com/docker/go-units|v0.5.0|间接依赖|go|
|github.com/docker/distribution|v2.8.2+incompatible|间接依赖|go|
|golang.org/x/term|v0.3.0|间接依赖|go|
|github.com/armon/circbuf|v0.0.0-20150827004946-bbbad097214e|间接依赖|go|
|github.com/emicklei/go-restful/v3|v3.10.2|间接依赖|go|
|github.com/stoewer/go-strcase|v1.3.0|间接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.5|间接依赖|go|
|k8s.io/klog/v2|v2.70.1|直接依赖|go|
|sigs.k8s.io/json|v0.0.0-20221116044647-bc3834ca7abd|间接依赖|go|
|k8s.io/autoscaler/vertical-pod-autoscaler|v0.0.0-20200605154545-936eea18fb1d|直接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|golang.org/x/sync|v0.2.0|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/internal/retry|v1.10.0|间接依赖|go|
|github.com/mrunalp/fileutils|v0.5.0|间接依赖|go|
|golang.org/x/term|v0.6.0|间接依赖|go|
|github.com/stretchr/testify|v1.8.0|直接依赖|go|
|github.com/Azure/go-autorest/autorest/azure/auth|v0.5.8|直接依赖|go|
|k8s.io/controller-manager|v0.28.0-beta.0|间接依赖|go|
|go.opentelemetry.io/otel|v1.14.0|间接依赖|go|
|github.com/googleapis/gax-go/v2|v2.7.1|间接依赖|go|
|github.com/containerd/ttrpc|v1.1.0|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|k8s.io/utils|v0.0.0-20220823124924-e9cbc92d1a73|间接依赖|go|
|github.com/PuerkitoBio/urlesc|v0.0.0-20170810143723-de5bf2ad4578|间接依赖|go|
|github.com/Azure/go-autorest/autorest/adal|v0.9.23|直接依赖|go|
|go.opentelemetry.io/otel/sdk|v1.10.0|间接依赖|go|
|github.com/vishvananda/netns|v0.0.0-20200728191858-db3c7e526aae|间接依赖|go|
|go.uber.org/multierr|v1.11.0|间接依赖|go|
|golang.org/x/crypto|v0.1.0|间接依赖|go|
|google.golang.org/api|v0.60.0|间接依赖|go|
|golang.org/x/oauth2|v0.0.0-20220223155221-ee480838109b|间接依赖|go|
|github.com/prometheus/client_golang|v1.14.0|直接依赖|go|
|google.golang.org/genproto|v0.0.0-20230526161137-0005af68ea54|间接依赖|go|
|go.uber.org/atomic|v1.10.0|间接依赖|go|
|golang.org/x/exp|v0.0.0-20230321023759-10a507213a29|间接依赖|go|
|google.golang.org/protobuf|v1.28.1|间接依赖|go|
|gopkg.in/gcfg.v1|v1.2.0|间接依赖|go|
|github.com/Azure/go-autorest/logger|v0.2.1|间接依赖|go|
|github.com/seccomp/libseccomp-golang|v0.10.0|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace|v1.10.0|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace/otlptracegrpc|v1.14.0|间接依赖|go|
|github.com/google/cel-go|v0.16.0|间接依赖|go|
|github.com/go-logr/logr|v1.2.3|间接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|k8s.io/apimachinery|v0.26.1|直接依赖|go|
|k8s.io/component-base|v0.28.0-beta.0|直接依赖|go|
|github.com/vmware/govmomi|v0.30.0|间接依赖|go|
|github.com/Azure/go-autorest/tracing|v0.6.0|间接依赖|go|
|github.com/Microsoft/go-winio|v0.6.0|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.1.2|间接依赖|go|
|k8s.io/kube-scheduler|v0.0.0|间接依赖|go|
|github.com/Microsoft/hcsshim|v0.8.25|间接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/google/go-cmp|v0.5.8|间接依赖|go|
|github.com/container-storage-interface/spec|v1.7.0|间接依赖|go|
|go.opentelemetry.io/otel/trace|v1.14.0|间接依赖|go|
|golang.org/x/time|v0.0.0-20220210224613-90d013bbcef8|直接依赖|go|
|golang.org/x/term|v0.0.0-20210927222741-03fcf44c2211|间接依赖|go|
|github.com/mailru/easyjson|v0.7.6|间接依赖|go|
|k8s.io/apiserver|v0.26.1|间接依赖|go|
|github.com/google/uuid|v1.1.2|间接依赖|go|
|k8s.io/kubernetes|v1.28.0-beta.0|直接依赖|go|
|sigs.k8s.io/yaml|v1.3.0|直接依赖|go|
|golang.org/x/sys|v0.3.0|间接依赖|go|
|k8s.io/klog/v2|v2.100.1|直接依赖|go|
|github.com/libopenstorage/openstorage|v1.0.0|间接依赖|go|
|github.com/prometheus/client_golang|v1.16.0|直接依赖|go|
|github.com/go-openapi/jsonreference|v0.19.5|间接依赖|go|
|k8s.io/component-helpers|v0.28.0-beta.0|直接依赖|go|
|golang.org/x/oauth2|v0.0.0-20211104180415-d3ed0bb246c8|间接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|github.com/google/gnostic-models|v0.6.8|间接依赖|go|
|k8s.io/kms|v0.28.0-beta.0|间接依赖|go|
|k8s.io/api|v0.26.1|直接依赖|go|
|golang.org/x/net|v0.12.0|直接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/github.com/emicklei/go-restful/otelrestful|v0.35.0|间接依赖|go|
|google.golang.org/genproto/googleapis/api|v0.0.0-20230525234035-dd9d682886f9|间接依赖|go|
|github.com/coreos/go-systemd/v22|v22.3.2|间接依赖|go|
|go.uber.org/zap|v1.24.0|间接依赖|go|
|golang.org/x/mod|v0.10.0|间接依赖|go|
|github.com/containerd/console|v1.0.3|间接依赖|go|
|k8s.io/api|v0.25.2|直接依赖|go|
|k8s.io/kubelet|v0.26.1|间接依赖|go|
|github.com/golang-jwt/jwt/v4|v4.5.0|间接依赖|go|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|直接依赖|go|
|gopkg.in/warnings.v0|v0.1.1|间接依赖|go|
|github.com/container-storage-interface/spec|v1.8.0|间接依赖|go|
|k8s.io/metrics|v0.25.0|直接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.6|间接依赖|go|
|github.com/imdario/mergo|v0.3.15|间接依赖|go|
|k8s.io/dynamic-resource-allocation|v0.0.0|间接依赖|go|
|github.com/karrick/godirwalk|v1.17.0|间接依赖|go|
|github.com/mistifyio/go-zfs|v2.1.2-0.20190413222219-f784269be439+incompatible|间接依赖|go|
|github.com/Azure/go-autorest/autorest/to|v0.4.0|直接依赖|go|
|github.com/JeffAshton/win_pdh|v0.0.0-20161109143554-76bb4ee9f0ab|间接依赖|go|
|k8s.io/client-go|v0.25.2|直接依赖|go|
|k8s.io/cri-api|v0.28.0-beta.0|间接依赖|go|
|golang.org/x/text|v0.5.0|间接依赖|go|
|github.com/mindprince/gonvml|v0.0.0-20190828220739-9ebdce4bb989|间接依赖|go|
|github.com/stretchr/objx|v0.4.0|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)