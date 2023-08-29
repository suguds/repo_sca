# go-kratos/kratos安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696585618703605760.svg)](https://www.murphysec.com/console/report/1696585618368061440/1696585618703605760)

仓库描述：Your ultimate Go microservices framework for the cloud-native era.

仓库地址：[https://github.com/go-kratos/kratos](https://github.com/go-kratos/kratos)

| star：21244 | watch：446 | fork：3890 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-29 02:44:01 | 许可证：MIT |
| 最近检测时间：2023-08-30 02:08:32 | 组件总数：218 | 漏洞总数：3 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Buger Jsonparser 安全漏洞|拒绝服务|[MPS-2020-17614](https://www.oscs1024.com/hd/MPS-2020-17614)|CVE-2020-35381|高危|
|buger jsonparser Library API 安全漏洞|不可达退出条件的循环（无限循环）|[MPS-2020-4145](https://www.oscs1024.com/hd/MPS-2020-4145)|CVE-2020-10675|高危|
|Google Go 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2022-9049](https://www.oscs1024.com/hd/MPS-2022-9049)|CVE-2022-29526|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/buger/jsonparser|v0.0.0-20181115193947-bf1c66bbce23|1.1.1|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|golang.org/x/sys|v0.0.0-20220722155257-8c9f86f7a55f|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|84|Low|
|BSD-3-Clause|47|Low|
|Apache-2.0|80|Low|
|MPL-2.0|13|Low|
|BSD-2-Clause|8|Low|
|ISC|1|Low|
|EPL-1.0|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|go.uber.org/multierr|v1.5.0|间接依赖|go|
|github.com/fatih/color|v1.13.0|直接依赖|go|
|github.com/go-kratos/aegis|v0.2.0|直接依赖|go|
|github.com/philhofer/fwd|v1.1.1|间接依赖|go|
|golang.org/x/mod|v0.6.0-dev.0.20220419223038-86c51ed26bb4|直接依赖|go|
|google.golang.org/protobuf|v1.28.0|直接依赖|go|
|github.com/emicklei/go-restful|v2.9.5+incompatible|间接依赖|go|
|github.com/go-openapi/swag|v0.19.14|间接依赖|go|
|github.com/klauspost/compress|v1.15.1|间接依赖|go|
|go.uber.org/multierr|v1.8.0|间接依赖|go|
|golang.org/x/text|v0.4.0|直接依赖|go|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|go.etcd.io/etcd/client/pkg/v3|v3.5.8|间接依赖|go|
|github.com/magiconair/properties|v1.8.6|间接依赖|go|
|github.com/kballard/go-shellquote|v0.0.0-20180428030007-95032a82bc51|间接依赖|go|
|github.com/go-errors/errors|v1.0.1|间接依赖|go|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|golang.org/x/term|v0.0.0-20210927222741-03fcf44c2211|间接依赖|go|
|go.uber.org/multierr|v1.6.0|间接依赖|go|
|google.golang.org/genproto/googleapis/api|v0.0.0-20230629202037-9506855d4529|直接依赖|go|
|github.com/go-openapi/jsonreference|v0.19.5|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.0|间接依赖|go|
|k8s.io/utils|v0.0.0-20221107191617-1a15be271d1d|间接依赖|go|
|github.com/go-ole/go-ole|v1.2.6|间接依赖|go|
|github.com/hashicorp/go-rootcerts|v1.0.2|间接依赖|go|
|sigs.k8s.io/json|v0.0.0-20220713155537-f223a00ba0e2|间接依赖|go|
|k8s.io/client-go|v0.26.3|直接依赖|go|
|github.com/rs/zerolog|v1.30.0|直接依赖|go|
|gopkg.in/ini.v1|v1.42.0|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|golang.org/x/oauth2|v0.0.0-20211104180415-d3ed0bb246c8|间接依赖|go|
|k8s.io/klog/v2|v2.80.1|间接依赖|go|
|github.com/shoenig/go-m1cpu|v0.1.6|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20221012153701-172d655c2280|间接依赖|go|
|github.com/vmihailenco/msgpack/v5|v5.3.5|直接依赖|go|
|go.uber.org/zap|v1.21.0|间接依赖|go|
|github.com/pelletier/go-toml/v2|v2.0.0-beta.8|间接依赖|go|
|github.com/hashicorp/go-cleanhttp|v0.5.1|间接依赖|go|
|go.opentelemetry.io/otel/metric|v1.16.0|间接依赖|go|
|k8s.io/apimachinery|v0.26.3|直接依赖|go|
|github.com/hashicorp/go-multierror|v1.1.1|间接依赖|go|
|github.com/coreos/go-semver|v0.3.0|间接依赖|go|
|go.uber.org/zap|v1.15.0|间接依赖|go|
|golang.org/x/net|v0.7.0|间接依赖|go|
|golang.org/x/net|v0.11.0|直接依赖|go|
|github.com/PuerkitoBio/purell|v1.1.1|间接依赖|go|
|github.com/go-playground/form/v4|v4.2.0|直接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|github.com/emicklei/proto|v1.10.0|直接依赖|go|
|golang.org/x/oauth2|v0.0.0-20220223155221-ee480838109b|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|golang.org/x/text|v0.3.8|直接依赖|go|
|github.com/google/gnostic|v0.5.7-v3refs|间接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230629202037-9506855d4529|直接依赖|go|
|go.opentelemetry.io/otel/trace|v1.16.0|直接依赖|go|
|google.golang.org/protobuf|v1.31.0|直接依赖|go|
|github.com/natefinch/lumberjack|v2.0.0+incompatible|间接依赖|go|
|github.com/hashicorp/errwrap|v1.1.0|间接依赖|go|
|go.uber.org/multierr|v1.11.0|间接依赖|go|
|github.com/polarismesh/polaris-go|v1.1.0|直接依赖|go|
|go.uber.org/zap|v1.24.0|直接依赖|go|
|github.com/tinylib/msgp|v1.1.6|间接依赖|go|
|github.com/cenkalti/backoff|v2.0.0+incompatible|间接依赖|go|
|github.com/gorilla/websocket|v1.4.3-0.20210424162022-e8629af678b7|间接依赖|go|
|go.uber.org/atomic|v1.11.0|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|k8s.io/client-go|v0.24.3|直接依赖|go|
|github.com/prometheus/procfs|v0.7.3|间接依赖|go|
|go.opentelemetry.io/otel/sdk|v1.16.0|直接依赖|go|
|github.com/spf13/jwalterweatherman|v1.1.0|间接依赖|go|
|github.com/subosito/gotenv|v1.2.0|间接依赖|go|
|github.com/aliyun/aliyun-log-go-sdk|v0.1.44|直接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|k8s.io/api|v0.26.3|直接依赖|go|
|golang.org/x/term|v0.9.0|间接依赖|go|
|github.com/pierrec/lz4|v2.6.1+incompatible|间接依赖|go|
|github.com/spf13/afero|v1.8.2|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|间接依赖|go|
|github.com/google/go-cmp|v0.5.5|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.12|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.6|间接依赖|go|
|github.com/imdario/mergo|v0.3.16|直接依赖|go|
|github.com/prometheus/client_golang|v1.15.1|直接依赖|go|
|google.golang.org/genproto|v0.0.0-20230629202037-9506855d4529|间接依赖|go|
|github.com/AlecAivazis/survey/v2|v2.3.7|直接依赖|go|
|github.com/mgutz/ansi|v0.0.0-20170206155736-9520e82c474b|间接依赖|go|
|gopkg.in/check.v1|v1.0.0-20201130134442-10cb98267c6c|间接依赖|go|
|github.com/Microsoft/go-winio|v0.5.2|间接依赖|go|
|github.com/prometheus/common|v0.35.0|间接依赖|go|
|github.com/dlclark/regexp2|v1.7.0|间接依赖|go|
|github.com/sirupsen/logrus|v1.8.1|直接依赖|go|
|golang.org/x/sys|v0.10.0|间接依赖|go|
|github.com/prometheus/client_golang|v1.12.1|间接依赖|go|
|k8s.io/klog/v2|v2.60.1|间接依赖|go|
|github.com/golang-jwt/jwt/v4|v4.5.0|直接依赖|go|
|go.opentelemetry.io/otel|v1.16.0|直接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.0|间接依赖|go|
|github.com/prometheus/procfs|v0.9.0|间接依赖|go|
|github.com/pierrec/lz4|v2.6.0+incompatible|间接依赖|go|
|github.com/mitchellh/mapstructure|v1.4.1|间接依赖|go|
|github.com/yusufpapurcu/wmi|v1.2.3|间接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.1|间接依赖|go|
|github.com/spf13/viper|v1.11.0|间接依赖|go|
|go.uber.org/atomic|v1.6.0|间接依赖|go|
|github.com/polarismesh/polaris-go|v1.3.0|直接依赖|go|
|github.com/tklauser/numcpus|v0.6.1|间接依赖|go|
|go.uber.org/atomic|v1.5.0|间接依赖|go|
|github.com/PuerkitoBio/urlesc|v0.0.0-20170810143723-de5bf2ad4578|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|直接依赖|go|
|github.com/lestrrat/go-file-rotatelogs|v0.0.0-20180223000712-d3151e2a480f|间接依赖|go|
|golang.org/x/sys|v0.0.0-20220722155257-8c9f86f7a55f|间接依赖|go|
|github.com/hashicorp/golang-lru|v0.5.4|间接依赖|go|
|github.com/fluent/fluent-logger-golang|v1.9.0|直接依赖|go|
|github.com/power-devops/perfstat|v0.0.0-20221212215047-62379fc7944b|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|直接依赖|go|
|gopkg.in/natefinch/lumberjack.v2|v2.0.0|间接依赖|go|
|github.com/spf13/cobra|v1.4.0|直接依赖|go|
|github.com/gofrs/uuid|v4.2.0+incompatible|直接依赖|go|
|github.com/go-zookeeper/zk|v1.0.3|直接依赖|go|
|github.com/go-resty/resty/v2|v2.7.0|直接依赖|go|
|github.com/go-logfmt/logfmt|v0.5.0|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.12|间接依赖|go|
|github.com/prometheus/client_golang|v1.12.2|间接依赖|go|
|github.com/stretchr/testify|v1.7.0|间接依赖|go|
|k8s.io/api|v0.24.3|直接依赖|go|
|github.com/prometheus/client_model|v0.2.0|间接依赖|go|
|github.com/rogpeppe/go-internal|v1.10.0|间接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|github.com/go-kratos/kratos/v2|v2.7.0|直接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|github.com/spaolacci/murmur3|v1.1.0|间接依赖|go|
|github.com/hashicorp/consul/api|v1.20.0|直接依赖|go|
|k8s.io/utils|v0.0.0-20220210201930-3a6ce19ff2f9|间接依赖|go|
|github.com/kr/pretty|v0.3.1|间接依赖|go|
|github.com/go-chassis/foundation|v0.4.0|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|直接依赖|go|
|github.com/coreos/go-systemd/v22|v22.3.2|间接依赖|go|
|github.com/mailru/easyjson|v0.7.6|间接依赖|go|
|github.com/jmespath/go-jmespath|v0.0.0-20180206201540-c2b33e8439af|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.14|间接依赖|go|
|go.uber.org/zap|v1.17.0|间接依赖|go|
|github.com/go-kratos/kratos/v2|v2.3.1|直接依赖|go|
|golang.org/x/time|v0.0.0-20220210224613-90d013bbcef8|间接依赖|go|
|github.com/apolloconfig/agollo/v4|v4.3.1|直接依赖|go|
|github.com/hashicorp/errwrap|v1.0.0|间接依赖|go|
|github.com/prometheus/common|v0.32.1|间接依赖|go|
|github.com/toolkits/concurrent|v0.0.0-20150624120057-a4371d70e3e3|间接依赖|go|
|github.com/prometheus/common|v0.44.0|直接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.1|间接依赖|go|
|github.com/envoyproxy/go-control-plane|v0.11.2-0.20230627204322-7d0032219fcb|间接依赖|go|
|github.com/hashicorp/serf|v0.10.1|间接依赖|go|
|github.com/go-logr/logr|v1.2.4|间接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|github.com/kr/text|v0.2.0|间接依赖|go|
|github.com/DataDog/datadog-go|v4.8.3+incompatible|直接依赖|go|
|go.etcd.io/etcd/api/v3|v3.5.8|间接依赖|go|
|golang.org/x/sync|v0.3.0|直接依赖|go|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|github.com/mitchellh/mapstructure|v1.4.3|间接依赖|go|
|google.golang.org/grpc|v1.57.0|直接依赖|go|
|github.com/spf13/cast|v1.4.1|间接依赖|go|
|go.etcd.io/etcd/client/v3|v3.5.8|直接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|go.uber.org/atomic|v1.9.0|间接依赖|go|
|github.com/nacos-group/nacos-sdk-go|v1.0.9|直接依赖|go|
|k8s.io/apimachinery|v0.24.3|直接依赖|go|
|github.com/lufia/plan9stats|v0.0.0-20230326075908-cb1d2100619a|间接依赖|go|
|google.golang.org/grpc|v1.56.1|直接依赖|go|
|github.com/go-kit/kit|v0.10.0|间接依赖|go|
|github.com/ghodss/yaml|v1.0.0|间接依赖|go|
|golang.org/x/tools|v0.0.0-20210106214847-113979e3529a|间接依赖|go|
|github.com/cenkalti/backoff|v2.2.1+incompatible|间接依赖|go|
|sigs.k8s.io/yaml|v1.2.0|间接依赖|go|
|github.com/stretchr/testify|v1.8.0|间接依赖|go|
|go.uber.org/atomic|v1.7.0|间接依赖|go|
|github.com/google/gofuzz|v1.1.0|间接依赖|go|
|github.com/go-chassis/openlog|v1.1.3|间接依赖|go|
|sigs.k8s.io/json|v0.0.0-20211208200746-9f7c6b3444d2|间接依赖|go|
|github.com/hashicorp/go-msgpack|v0.5.5|间接依赖|go|
|github.com/stretchr/objx|v0.5.0|间接依赖|go|
|github.com/bmizerany/assert|v0.0.0-20160611221934-b7ed37b82869|间接依赖|go|
|sigs.k8s.io/yaml|v1.3.0|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.0.0|间接依赖|go|
|golang.org/x/text|v0.11.0|间接依赖|go|
|github.com/aliyun/alibaba-cloud-sdk-go|v1.61.18|间接依赖|go|
|github.com/buger/jsonparser|v1.1.1|间接依赖|go|
|github.com/armon/go-metrics|v0.3.10|间接依赖|go|
|github.com/tencentcloud/tencentcloud-cls-sdk-go|v1.0.2|直接依赖|go|
|github.com/fatih/color|v1.9.0|间接依赖|go|
|github.com/hashicorp/go-immutable-radix|v1.3.0|间接依赖|go|
|github.com/vmihailenco/tagparser/v2|v2.0.0|间接依赖|go|
|github.com/pelletier/go-toml|v1.9.4|间接依赖|go|
|github.com/shirou/gopsutil/v3|v3.23.6|间接依赖|go|
|gopkg.in/ini.v1|v1.66.4|间接依赖|go|
|github.com/hashicorp/go-hclog|v0.14.1|间接依赖|go|
|github.com/go-chassis/cari|v0.6.0|直接依赖|go|
|github.com/go-chassis/sc-client|v0.6.1-0.20210615014358-a45e9090c751|直接依赖|go|
|github.com/google/uuid|v1.3.0|直接依赖|go|
|github.com/modern-go/reflect2|v0.0.0-20180701023420-4b7aa43c6742|间接依赖|go|
|golang.org/x/lint|v0.0.0-20190930215403-16217165b5de|间接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.5|间接依赖|go|
|github.com/opensergo/opensergo-go|v0.0.0-20220331070310-e5b01fee4d1c|直接依赖|go|
|google.golang.org/genproto|v0.0.0-20220519153652-3a47de7e79bd|直接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|github.com/tklauser/go-sysconf|v0.3.11|间接依赖|go|
|github.com/buger/jsonparser|v0.0.0-20181115193947-bf1c66bbce23|间接依赖|go|
|github.com/json-iterator/go|v1.1.6|间接依赖|go|
|github.com/lestrrat/go-strftime|v0.0.0-20180220042222-ba3bf9c1d042|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20220328201542-3ee0da9b0b42|间接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.3|间接依赖|go|
|github.com/gorilla/mux|v1.8.0|直接依赖|go|
|github.com/prometheus/client_model|v0.4.0|间接依赖|go|
|github.com/emicklei/go-restful/v3|v3.9.0|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)