# projectcalico/calico安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695138486238928896.svg)](https://www.murphysec.com/console/report/1692962266361516032/1695138486238928896)

仓库描述：Cloud native networking and network security

仓库地址：[https://github.com/projectcalico/calico](https://github.com/projectcalico/calico)

| star：4918 | watch：118 | fork：1146 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-26 00:50:12 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-26 02:18:56 | 组件总数：312 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Kubernetes 输入验证错误漏洞|访问控制不当|[MPS-2019-15838](https://www.oscs1024.com/hd/MPS-2019-15838)|CVE-2019-11255|中危|
|go.uuid 不安全的随机性漏洞|使用具有密码学弱点缺陷的PRNG|[MPS-2021-7854](https://www.oscs1024.com/hd/MPS-2021-7854)|CVE-2021-3538|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/satori/go.uuid|v1.2.0||直接依赖|建议修复|C:1|H:0|M:0|L:0|
|k8s.io/kubernetes|v1.26.5||直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|146|Low|
|MIT|84|Low|
|BSD-3-Clause|53|Low|
|MPL-2.0|4|Low|
|BSD-2-Clause|9|Low|
|LGPL-3.0|4|Medium|
|自定义许可证|3|Low|
|ISC|2|Low|
|CC-BY-SA-4.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|github.com/cpuguy83/go-md2man/v2|v2.0.2|间接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|github.com/google/netstack|v0.0.0-20191123085552-55fcc16cd0eb|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/feature/ec2/imds|v1.8.0|直接依赖|go|
|github.com/urfave/cli|v1.22.2|间接依赖|go|
|github.com/onsi/ginkgo/v2|v2.7.1|直接依赖|go|
|github.com/go-playground/universal-translator|v0.0.0-20170327191703-71201497bace|间接依赖|go|
|golang.org/x/mod|v0.8.0|间接依赖|go|
|github.com/containerd/ttrpc|v1.1.0|间接依赖|go|
|github.com/go-playground/locales|v0.12.1|间接依赖|go|
|requests|2.31.0|间接依赖|pip|
|go.opentelemetry.io/contrib/instrumentation/google.golang.org/grpc/otelgrpc|v0.35.0|间接依赖|go|
|simplejson|3.13.2|间接依赖|pip|
|github.com/Azure/azure-sdk-for-go|v55.0.0+incompatible|间接依赖|go|
|github.com/gofrs/flock|v0.8.0|直接依赖|go|
|github.com/Azure/go-autorest/tracing|v0.6.0|间接依赖|go|
|google.golang.org/protobuf|v1.28.1|间接依赖|go|
|golang.org/x/crypto|v0.1.0|间接依赖|go|
|github.com/alexflint/go-filemutex|v1.1.0|间接依赖|go|
|github.com/moby/sys/mountinfo|v0.6.2|间接依赖|go|
|go.opentelemetry.io/otel/trace|v1.10.0|间接依赖|go|
|github.com/Azure/go-autorest|v14.2.0+incompatible|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.1.2|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/vmware/govmomi|v0.20.3|间接依赖|go|
|go.opentelemetry.io/otel|v1.10.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/config|v1.10.0|直接依赖|go|
|gopkg.in/go-playground/assert.v1|v1.2.1|间接依赖|go|
|github.com/grpc-ecosystem/go-grpc-prometheus|v1.2.0|间接依赖|go|
|github.com/natefinch/atomic|v0.0.0-20150920032501-a62ce929ffcc|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sts|v1.9.0|间接依赖|go|
|github.com/onsi/ginkgo|v1.16.5|直接依赖|go|
|github.com/armon/circbuf|v0.0.0-20150827004946-bbbad097214e|间接依赖|go|
|github.com/satori/go.uuid|v1.2.0|直接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|直接依赖|go|
|github.com/NYTimes/gziphandler|v1.1.1|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|直接依赖|go|
|golang.zx2c4.com/wireguard/wgctrl|v0.0.0-20200324154536-ceff61240acf|直接依赖|go|
|modernc.org/memory|v1.5.0|直接依赖|go|
|k8s.io/kube-proxy|v0.0.0|间接依赖|go|
|github.com/buger/jsonparser|v1.1.1|直接依赖|go|
|golang.org/x/sync|v0.1.0|直接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/apparentlymart/go-cidr|v1.1.0|直接依赖|go|
|github.com/euank/go-kmsg-parser|v2.0.0+incompatible|间接依赖|go|
|github.com/spf13/cobra|v1.7.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sso|v1.6.0|间接依赖|go|
|github.com/golang/snappy|v0.0.4|直接依赖|go|
|github.com/mattn/go-runewidth|v0.0.9|间接依赖|go|
|github.com/imdario/mergo|v0.3.11|间接依赖|go|
|golang.org/x/time|v0.0.0-20220210224613-90d013bbcef8|间接依赖|go|
|google.golang.org/grpc|v1.52.0|直接依赖|go|
|github.com/StackExchange/wmi|v0.0.0-20181212234831-e0a55b97c705|间接依赖|go|
|github.com/go-errors/errors|v1.0.2-0.20180813162953-d98b870cc4e0|间接依赖|go|
|github.com/google/cadvisor|v0.46.0|间接依赖|go|
|k8s.io/component-base|v0.26.5|直接依赖|go|
|k8s.io/pod-security-admission|v0.0.0|间接依赖|go|
|k8s.io/client-go|v0.26.5|直接依赖|go|
|k8s.io/utils|v0.0.0-20230313181309-38a27ef9d749|直接依赖|go|
|github.com/nmrshll/go-cp|v0.0.0-20180115193924-61436d3b7cfa|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/configsources|v1.1.0|间接依赖|go|
|github.com/olekukonko/tablewriter|v0.0.5|直接依赖|go|
|github.com/pelletier/go-toml|v1.9.5|间接依赖|go|
|github.com/go-sql-driver/mysql|v1.4.1|间接依赖|go|
|/requirements.txt||间接依赖|pip|
|github.com/pelletier/go-toml/v2|v2.0.6|间接依赖|go|
|github.com/mxk/go-flowrate|v0.0.0-20140419014527-cca7078d478f|间接依赖|go|
|github.com/mdlayher/genetlink|v1.0.0|间接依赖|go|
|github.com/google/gofuzz|v1.2.0|间接依赖|go|
|golang.org/x/text|v0.8.0|直接依赖|go|
|github.com/google/btree|v1.1.2|直接依赖|go|
|github.com/projectcalico/go-yaml-wrapper|v0.0.0-20191112210931-090425220c54|直接依赖|go|
|github.com/go-ole/go-ole|v1.2.4|间接依赖|go|
|github.com/libopenstorage/openstorage|v1.0.0|间接依赖|go|
|k8s.io/apimachinery|v0.26.5|直接依赖|go|
|github.com/lithammer/dedent|v1.1.0|间接依赖|go|
|k8s.io/klog/v2|v2.80.1|直接依赖|go|
|sigs.k8s.io/apiserver-network-proxy/konnectivity-client|v0.0.37|间接依赖|go|
|github.com/cncf/xds/go|v0.0.0-20211011173535-cb28da3451f1|间接依赖|go|
|golang.org/x/term|v0.5.0|间接依赖|go|
|sigs.k8s.io/yaml|v1.3.0|直接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace/otlptracegrpc|v1.10.0|间接依赖|go|
|gopkg.in/gcfg.v1|v1.2.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ec2|v1.21.0|直接依赖|go|
|github.com/mrunalp/fileutils|v0.5.0|间接依赖|go|
|golang.zx2c4.com/wireguard|v0.0.20200121|间接依赖|go|
|k8s.io/apiextensions-apiserver|v0.26.5|直接依赖|go|
|gopkg.in/tomb.v1|v1.0.0-20141024135613-dd632973f1e7|间接依赖|go|
|golang.org/x/oauth2|v0.1.0|间接依赖|go|
|github.com/aws/aws-sdk-go|v1.44.122|间接依赖|go|
|RELEASE_VERSION||间接依赖|pip|
|github.com/patrickmn/go-cache|v2.1.0+incompatible|直接依赖|go|
|github.com/googleapis/enterprise-certificate-proxy|v0.2.1|间接依赖|go|
|deepdiff|3.3.0|间接依赖|pip|
|github.com/leodido/go-urn|v0.0.0-20181204092800-a67a23e1c1af|间接依赖|go|
|github.com/boombuler/barcode|v1.0.1-0.20190219062509-6c824513bacc|间接依赖|go|
|k8s.io/kms|v0.26.5|间接依赖|go|
|gopkg.in/natefinch/lumberjack.v2|v2.0.0|直接依赖|go|
|gopkg.in/ini.v1|v1.67.0|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace|v1.10.0|间接依赖|go|
|go.opencensus.io|v0.24.0|间接依赖|go|
|github.com/russross/blackfriday/v2|v2.1.0|间接依赖|go|
|github.com/juju/mutex|v0.0.0-20180619145857-d21b13acf4bf|直接依赖|go|
|gopkg.in/warnings.v0|v0.1.1|间接依赖|go|
|github.com/go-openapi/swag|v0.22.3|间接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.0|间接依赖|go|
|github.com/stoewer/go-strcase|v1.2.0|间接依赖|go|
|github.com/projectcalico/api|v0.0.0-00010101000000-000000000000|直接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|github.com/docker/distribution|v2.8.1+incompatible|间接依赖|go|
|k8s.io/csi-translation-lib|v0.26.5|间接依赖|go|
|github.com/rubiojr/go-vhd|v0.0.0-20200706105327-02e210299021|间接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/net/http/otelhttp|v0.35.0|间接依赖|go|
|github.com/containerd/cgroups|v1.0.1|间接依赖|go|
|sigs.k8s.io/json|v0.0.0-20221116044647-bc3834ca7abd|间接依赖|go|
|github.com/onsi/gomega|v1.25.0|直接依赖|go|
|RELEASE_STREAM||间接依赖|pip|
|github.com/aws/aws-sdk-go-v2/internal/ini|v1.3.0|间接依赖|go|
|github.com/nxadm/tail|v1.4.8|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/opencontainers/runc|v1.1.6|间接依赖|go|
|k8s.io/cloud-provider|v0.26.5|间接依赖|go|
|nose|1.3.7|间接依赖|pip|
|github.com/aws/aws-sdk-go-v2/credentials|v1.6.0|间接依赖|go|
|github.com/mcuadros/go-version|v0.0.0-20190308113854-92cdf37c5b75|直接依赖|go|
|github.com/googleapis/gax-go/v2|v2.7.0|间接依赖|go|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|k8s.io/kubernetes|v1.26.5|直接依赖|go|
|k8s.io/client-go|v0.26.3|直接依赖|go|
|github.com/google/uuid|v1.3.0|直接依赖|go|
|github.com/antlr/antlr4/runtime/Go/antlr|v1.4.10|间接依赖|go|
|github.com/kelseyhightower/memkv|v0.1.1|直接依赖|go|
|go.etcd.io/etcd/client/v2|v2.305.8|直接依赖|go|
|github.com/mdlayher/netlink|v1.1.0|间接依赖|go|
|github.com/evanphx/json-patch/v5|v5.2.0|间接依赖|go|
|github.com/stretchr/objx|v0.5.0|间接依赖|go|
|github.com/pkg/profile|v1.6.0|直接依赖|go|
|go.uber.org/zap|v1.21.0|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/github.com/emicklei/go-restful/otelrestful|v0.35.0|间接依赖|go|
|go.opentelemetry.io/proto/otlp|v0.19.0|间接依赖|go|
|golang.org/x/net|v0.8.0|直接依赖|go|
|google.golang.org/api|v0.107.0|间接依赖|go|
|github.com/cyphar/filepath-securejoin|v0.2.3|间接依赖|go|
|github.com/kelseyhightower/envconfig|v0.0.0-20180517194557-dd1402a4d99d|直接依赖|go|
|github.com/google/gopacket|v1.1.19|直接依赖|go|
|github.com/aws/smithy-go|v1.9.0|直接依赖|go|
|github.com/mattn/go-isatty|v0.0.14|间接依赖|go|
|golang.org/x/net|v0.7.0|间接依赖|go|
|k8s.io/gengo|v0.0.0-20220902162205-c0856e24416d|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|直接依赖|go|
|github.com/gofrs/uuid|v4.0.0+incompatible|间接依赖|go|
|github.com/containernetworking/cni|v1.0.1|直接依赖|go|
|go.opentelemetry.io/otel/metric|v0.31.0|间接依赖|go|
|FLANNEL_VERSION||间接依赖|pip|
|github.com/shirou/gopsutil|v0.0.0-20190323131628-2cbc9195c892|直接依赖|go|
|k8s.io/cri-api|v0.0.0|间接依赖|go|
|github.com/Microsoft/hcsshim|v0.8.22|直接依赖|go|
|k8s.io/api|v0.26.3|直接依赖|go|
|k8s.io/kubectl|v0.0.0|间接依赖|go|
|github.com/blang/semver/v4|v4.0.0|间接依赖|go|
|github.com/golang-jwt/jwt/v4|v4.2.0|间接依赖|go|
|github.com/godbus/dbus/v5|v5.0.6|间接依赖|go|
|golang.org/x/oauth2|v0.0.0-20220223155221-ee480838109b|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/endpoints/v2|v2.0.0|间接依赖|go|
|github.com/coreos/go-iptables|v0.6.0|间接依赖|go|
|github.com/Azure/go-autorest/autorest/adal|v0.9.20|间接依赖|go|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|github.com/Azure/go-autorest/logger|v0.2.1|间接依赖|go|
|github.com/libp2p/go-reuseport|v0.1.0|直接依赖|go|
|github.com/google/safetext|v0.0.0-20230106111101-7156a760e523|直接依赖|go|
|github.com/opencontainers/runtime-spec|v1.0.3-0.20210326190908-1c3f411f0417|间接依赖|go|
|go.uber.org/multierr|v1.8.0|间接依赖|go|
|golang.org/x/sys|v0.5.0|间接依赖|go|
|github.com/google/gnostic|v0.5.7-v3refs|间接依赖|go|
|github.com/containernetworking/plugins|v1.0.1|直接依赖|go|
|github.com/GoogleCloudPlatform/k8s-cloud-provider|v1.18.1-0.20220218231025-f11817397a1b|间接依赖|go|
|github.com/karrick/godirwalk|v1.17.0|间接依赖|go|
|k8s.io/dynamic-resource-allocation|v0.26.5|间接依赖|go|
|github.com/mistifyio/go-zfs|v2.1.2-0.20190413222219-f784269be439+incompatible|间接依赖|go|
|nose-timer|0.7.1|间接依赖|pip|
|k8s.io/apimachinery|v0.26.3|直接依赖|go|
|golang.org/x/text|v0.7.0|间接依赖|go|
|github.com/magiconair/properties|v1.8.7|间接依赖|go|
|github.com/prometheus/client_model|v0.3.0|直接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|github.com/google/cel-go|v0.12.6|间接依赖|go|
|github.com/prometheus/procfs|v0.8.0|间接依赖|go|
|github.com/spf13/jwalterweatherman|v1.1.0|间接依赖|go|
|github.com/juju/clock|v0.0.0-20190205081909-9c5c9712527c|直接依赖|go|
|github.com/mindprince/gonvml|v0.0.0-20190828220739-9ebdce4bb989|间接依赖|go|
|netaddr|0.7.19|间接依赖|pip|
|github.com/felixge/httpsnoop|v1.0.3|间接依赖|go|
|github.com/prometheus/client_golang|v1.14.0|直接依赖|go|
|github.com/sirupsen/logrus|v1.9.0|直接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20230303024457-afdc3dddf62d|直接依赖|go|
|github.com/hashicorp/errwrap|v1.0.0|间接依赖|go|
|go.etcd.io/etcd/client/pkg/v3|v3.5.8|直接依赖|go|
|github.com/JeffAshton/win_pdh|v0.0.0-20161109143554-76bb4ee9f0ab|间接依赖|go|
|github.com/envoyproxy/go-control-plane|v0.10.2-0.20220325020618-49ff273808a1|直接依赖|go|
|github.com/Azure/go-autorest/autorest/date|v0.3.0|间接依赖|go|
|nose-parameterized|0.6.0|间接依赖|pip|
|github.com/moby/ipvs|v1.0.1|间接依赖|go|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|github.com/Azure/go-autorest/autorest/mocks|v0.4.2|间接依赖|go|
|go.uber.org/atomic|v1.9.0|间接依赖|go|
|k8s.io/component-helpers|v0.26.5|间接依赖|go|
|github.com/vishvananda/netns|v0.0.0-20210104183010-2eb08e3e575f|间接依赖|go|
|github.com/ghodss/yaml|v1.0.0|间接依赖|go|
|github.com/envoyproxy/protoc-gen-validate|v0.1.0|间接依赖|go|
|github.com/Microsoft/go-winio|v0.4.17|间接依赖|go|
|github.com/mohae/deepcopy|v0.0.0-20170603005431-491d3605edfb|间接依赖|go|
|github.com/opencontainers/selinux|v1.10.0|间接依赖|go|
|github.com/spf13/afero|v1.9.3|间接依赖|go|
|github.com/subosito/gotenv|v1.4.2|间接依赖|go|
|github.com/go-ini/ini|v1.63.2|直接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/evanphx/json-patch|v4.12.0+incompatible|间接依赖|go|
|github.com/rakelkar/gonetsh|v0.3.2|直接依赖|go|
|cloud.google.com/go/compute|v1.14.0|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/presigned-url|v1.5.0|间接依赖|go|
|check_output||间接依赖|pip|
|pyyaml|4.2b1|间接依赖|pip|
|go.etcd.io/etcd/api/v3|v3.5.8|直接依赖|go|
|github.com/Azure/go-autorest/autorest/validation|v0.3.1|间接依赖|go|
|github.com/onsi/gomega|v1.23.0|直接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.2|间接依赖|go|
|github.com/juju/testing|v0.0.0-20200608005635-e4eedbc6f7aa|间接依赖|go|
|github.com/checkpoint-restore/go-criu/v5|v5.3.0|间接依赖|go|
|golang.org/x/tools|v0.6.0|间接依赖|go|
|github.com/distribution/distribution|v2.8.1+incompatible|直接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.3|间接依赖|go|
|github.com/stretchr/testify|v1.8.1|间接依赖|go|
|github.com/imdario/mergo|v0.3.8|间接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.6|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|k8s.io/code-generator|v0.26.5|直接依赖|go|
|github.com/container-storage-interface/spec|v1.7.0|直接依赖|go|
|github.com/golang-collections/collections|v0.0.0-20130729185459-604e922904d3|直接依赖|go|
|github.com/shirou/w32|v0.0.0-20160930032740-bb4de0191aa4|间接依赖|go|
|check_call||间接依赖|pip|
|k8s.io/kube-scheduler|v0.0.0|间接依赖|go|
|github.com/docker/go-units|v0.5.0|间接依赖|go|
|github.com/alessio/shellescape|v1.4.1|间接依赖|go|
|k8s.io/api|v0.26.5|直接依赖|go|
|libbpf||间接依赖||
|go.opentelemetry.io/otel/sdk|v1.10.0|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/internal/retry|v1.10.0|间接依赖|go|
|github.com/cilium/ebpf|v0.7.0|间接依赖|go|
|github.com/ishidawataru/sctp|v0.0.0-20191218070446-00ab2ac2db07|直接依赖|go|
|github.com/golang/protobuf|v1.5.2|直接依赖|go|
|go.etcd.io/etcd/client/v3|v3.5.8|直接依赖|go|
|github.com/fsnotify/fsnotify|v1.4.9|间接依赖|go|
|github.com/pquerna/otp|v1.2.0|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|直接依赖|go|
|github.com/Azure/go-autorest/autorest/to|v0.4.0|间接依赖|go|
|golang.org/x/sys|v0.6.0|直接依赖|go|
|github.com/projectcalico/go-json|v0.0.0-20161128004156-6219dc7339ba|直接依赖|go|
|github.com/seccomp/libseccomp-golang|v0.9.2-0.20220502022130-f33da4d89646|间接依赖|go|
|github.com/coreos/go-systemd/v22|v22.3.2|间接依赖|go|
|sigs.k8s.io/kind|v0.11.1|直接依赖|go|
|github.com/vishvananda/netlink|v1.2.1-beta.2.0.20230206183746-70ca0345eede|直接依赖|go|
|github.com/coreos/go-semver|v0.3.0|直接依赖|go|
|github.com/spf13/viper|v1.15.0|直接依赖|go|
|github.com/prometheus/common|v0.37.0|直接依赖|go|
|OPERATOR_VERSION||间接依赖|pip|
|github.com/Azure/go-autorest/autorest|v0.11.27|间接依赖|go|
|gopkg.in/go-playground/validator.v9|v9.27.0|直接依赖|go|
|k8s.io/kubelet|v0.26.5|间接依赖|go|
|github.com/gruntwork-io/go-commons|v0.8.0|间接依赖|go|
|github.com/mattn/go-zglob|v0.0.2-0.20190814121620-e3c945676326|间接依赖|go|
|github.com/cenkalti/backoff/v4|v4.1.3|间接依赖|go|
|github.com/juju/errors|v0.0.0-20200330140219-3fe23663418f|直接依赖|go|
|github.com/spf13/cast|v1.5.0|间接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/onsi/ginkgo|v1.16.4|直接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|直接依赖|go|
|github.com/emicklei/go-restful/v3|v3.9.0|间接依赖|go|
|cloud.google.com/go/compute/metadata|v0.2.3|间接依赖|go|
|golang.org/x/term|v0.6.0|间接依赖|go|
|k8s.io/mount-utils|v0.26.5|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/tchap/go-patricia/v2|v2.3.1|直接依赖|go|
|github.com/golang/mock|v1.6.0|间接依赖|go|
|github.com/syndtr/gocapability|v0.0.0-20200815063812-42c35b437635|间接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.1|间接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|间接依赖|go|
|k8s.io/legacy-cloud-providers|v0.0.0|间接依赖|go|
|github.com/safchain/ethtool|v0.0.0-20210803160452-9aa261dae9b1|直接依赖|go|
|github.com/BurntSushi/toml|v1.2.1|直接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|直接依赖|go|
|github.com/containerd/console|v1.0.3|间接依赖|go|
|github.com/kardianos/osext|v0.0.0-20190222173326-2bc1f35cddc0|直接依赖|go|
|github.com/moby/spdystream|v0.2.0|间接依赖|go|
|util||间接依赖|pip|
|github.com/go-logr/logr|v1.2.3|间接依赖|go|
|golang.org/x/time|v0.1.0|间接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0|间接依赖|go|
|github.com/docopt/docopt-go|v0.0.0-20180111231733-ee0de3bc6815|直接依赖|go|
|github.com/joho/godotenv|v1.4.0|直接依赖|go|
|k8s.io/utils|v0.0.0-20221107191617-1a15be271d1d|间接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway/v2|v2.7.0|间接依赖|go|
|github.com/gruntwork-io/terratest|v0.41.24|直接依赖|go|
|github.com/termie/go-shutil|v0.0.0-20140729215957-bcacb06fecae|直接依赖|go|
|github.com/mipearson/rfw|v0.0.0-20170619235010-6f0a6f3266ba|直接依赖|go|
|k8s.io/apiserver|v0.26.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2|v1.11.0|直接依赖|go|
|google.golang.org/genproto|v0.0.0-20221227171554-f9683d7f8bef|直接依赖|go|
|github.com/hashicorp/go-multierror|v1.1.0|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)