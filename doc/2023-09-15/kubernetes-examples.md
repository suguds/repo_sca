# AdminTurnedDevOps/kubernetes-examples安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1702384365761855488.svg)](https://www.murphysec.com/console/report/1702384365703135232/1702384365761855488)

仓库描述：This repo contains a bunch of Kubernetes examples

仓库地址：[https://github.com/AdminTurnedDevOps/kubernetes-examples](https://github.com/AdminTurnedDevOps/kubernetes-examples)

| star：602 | watch：34 | fork：274 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-10 02:30:18 | 许可证：- |
| 最近检测时间：2023-09-15 02:10:46 | 组件总数：165 | 漏洞总数：3 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58307](https://www.oscs1024.com/hd/MPS-2022-58307)|CVE-2022-41723|高危|
|Go-Yaml 安全漏洞|反序列化|[MPS-2022-8233](https://www.oscs1024.com/hd/MPS-2022-8233)|CVE-2022-28948|高危|
|Google Go 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2022-9049](https://www.oscs1024.com/hd/MPS-2022-9049)|CVE-2022-29526|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|golang.org/x/net|v0.0.0-20220722155237-a158d28d115b|0.7.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|gopkg.in/yaml.v3|v3.0.0-20210107192922-496545a6307b|3.0.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|golang.org/x/net|v0.0.0-20210825183410-e898025ed96a|0.7.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|golang.org/x/net|v0.0.0-20220127200216-cd36cc0744dd|0.7.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|golang.org/x/net|v0.0.0-20211209124913-491a49abca63|0.7.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|golang.org/x/sys|v0.0.0-20220209214540-3681064d5158|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|golang.org/x/sys|v0.0.0-20211029165221-6e7872819dc8|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|golang.org/x/sys|v0.0.0-20210831042530-f4d43177bf5e|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|golang.org/x/sys|v0.0.0-20220811171246-fbc7d0a398ab|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|golang.org/x/sys|v0.0.0-20220722155257-8c9f86f7a55f|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|45|Low|
|Apache-2.0|70|Low|
|BSD-3-Clause|48|Low|
|BSD-2-Clause|5|Low|
|MPL-2.0|2|Low|
|ISC|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/cespare/xxhash/v2|v2.1.1|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|github.com/golang/glog|v0.0.0-20160126235308-23def4e6c14b|间接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|github.com/google/go-cmp|v0.5.5|间接依赖|go|
|k8s.io/apiextensions-apiserver|v0.23.0|间接依赖|go|
|github.com/onsi/gomega|v1.17.0|直接依赖|go|
|k8s.io/apimachinery|v0.23.5|直接依赖|go|
|github.com/src-d/gcfg|v1.4.0|间接依赖|go|
|github.com/uber/jaeger-client-go|v2.22.1+incompatible|间接依赖|go|
|github.com/pulumi/pulumi-kubernetes/sdk/v3|v3.19.4|直接依赖|go|
|golang.org/x/sys|v0.0.0-20220209214540-3681064d5158|间接依赖|go|
|gopkg.in/check.v1|v1.0.0-20200227125254-8fa46927fb4f|间接依赖|go|
|k8s.io/klog/v2|v2.70.1|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.0-20210107192922-496545a6307b|间接依赖|go|
|github.com/opentracing/opentracing-go|v1.1.0|间接依赖|go|
|github.com/Azure/go-autorest/tracing|v0.6.0|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/rivo/uniseg|v0.2.0|间接依赖|go|
|sigs.k8s.io/yaml|v1.3.0|间接依赖|go|
|sigs.k8s.io/json|v0.0.0-20220713155537-f223a00ba0e2|间接依赖|go|
|github.com/uber/jaeger-lib|v2.2.0+incompatible|间接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.1.2|间接依赖|go|
|gopkg.in/tomb.v1|v1.0.0-20141024135613-dd632973f1e7|间接依赖|go|
|github.com/hashicorp/go-multierror|v1.0.0|间接依赖|go|
|github.com/googleapis/gnostic|v0.5.5|间接依赖|go|
|k8s.io/client-go|v0.25.0|直接依赖|go|
|github.com/golang/protobuf|v1.5.2|间接依赖|go|
|sigs.k8s.io/yaml|v1.2.0|间接依赖|go|
|golang.org/x/crypto|v0.0.0-20220214200702-86341886e292|间接依赖|go|
|github.com/prometheus/client_model|v0.2.0|间接依赖|go|
|github.com/google/gofuzz|v1.1.0|间接依赖|go|
|github.com/form3tech-oss/jwt-go|v3.2.3+incompatible|间接依赖|go|
|github.com/opentracing/basictracer-go|v1.0.0|间接依赖|go|
|golang.org/x/net|v0.0.0-20210825183410-e898025ed96a|间接依赖|go|
|github.com/pulumi/pulumi/sdk/v3|v3.35.3|直接依赖|go|
|github.com/cheggaaa/pb|v1.0.18|间接依赖|go|
|github.com/google/gnostic|v0.5.7-v3refs|间接依赖|go|
|github.com/mattn/go-runewidth|v0.0.8|间接依赖|go|
|github.com/hashicorp/errwrap|v1.0.0|间接依赖|go|
|golang.org/x/crypto|v0.0.0-20210817164053-32db794688a5|间接依赖|go|
|github.com/go-openapi/jsonreference|v0.19.5|间接依赖|go|
|github.com/blang/semver|v3.5.1+incompatible|间接依赖|go|
|golang.org/x/oauth2|v0.0.0-20211104180415-d3ed0bb246c8|间接依赖|go|
|github.com/google/go-cmp|v0.5.6|间接依赖|go|
|github.com/aws/constructs-go/constructs/v10|v10.1.144|直接依赖|go|
|google.golang.org/genproto|v0.0.0-20210402141018-6c239bbf2bb1|间接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.1|间接依赖|go|
|k8s.io/klog/v2|v2.30.0|间接依赖|go|
|k8s.io/utils|v0.0.0-20211116205334-6203023598ed|间接依赖|go|
|google.golang.org/protobuf|v1.27.1|间接依赖|go|
|k8s.io/api|v0.23.5|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.12|间接依赖|go|
|golang.org/x/mod|v0.4.2|间接依赖|go|
|sigs.k8s.io/json|v0.0.0-20211020170558-c049b76a60c6|间接依赖|go|
|golang.org/x/sys|v0.0.0-20220722155257-8c9f86f7a55f|间接依赖|go|
|k8s.io/apimachinery|v0.25.0|直接依赖|go|
|github.com/xanzy/ssh-agent|v0.2.1|间接依赖|go|
|github.com/Azure/go-autorest/autorest/date|v0.3.0|间接依赖|go|
|github.com/google/uuid|v1.1.2|间接依赖|go|
|golang.org/x/oauth2|v0.0.0-20210819190943-2bc19b11175f|间接依赖|go|
|github.com/spf13/cobra|v1.2.1|间接依赖|go|
|github.com/go-logr/logr|v1.2.0|间接依赖|go|
|github.com/niemeyer/pretty|v0.0.0-20200227124842-a10e7caefd8e|间接依赖|go|
|github.com/pkg/term|v1.1.0|间接依赖|go|
|github.com/spf13/cast|v1.3.1|间接依赖|go|
|github.com/tweekmonster/luser|v0.0.0-20161003172636-3fa38070dbd7|间接依赖|go|
|github.com/Azure/go-autorest/autorest/adal|v0.9.13|间接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.3|间接依赖|go|
|github.com/sergi/go-diff|v1.1.0|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|golang.org/x/sys|v0.0.0-20211029165221-6e7872819dc8|间接依赖|go|
|k8s.io/component-base|v0.23.5|间接依赖|go|
|github.com/evanphx/json-patch|v4.12.0+incompatible|间接依赖|go|
|github.com/kevinburke/ssh_config|v0.0.0-20190725054713-01f96b0aa0cd|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.5.1|间接依赖|go|
|github.com/go-logr/zapr|v1.2.0|间接依赖|go|
|github.com/Azure/go-autorest/autorest|v0.11.18|间接依赖|go|
|github.com/Masterminds/semver/v3|v3.1.1|间接依赖|go|
|golang.org/x/term|v0.0.0-20210615171337-6886f2dfbf5b|间接依赖|go|
|gopkg.in/src-d/go-git.v4|v4.13.1|间接依赖|go|
|golang.org/x/term|v0.0.0-20210927222741-03fcf44c2211|间接依赖|go|
|github.com/prometheus/common|v0.28.0|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/go-openapi/swag|v0.19.14|间接依赖|go|
|github.com/PuerkitoBio/purell|v1.1.1|间接依赖|go|
|github.com/rogpeppe/go-internal|v1.8.1|间接依赖|go|
|golang.org/x/text|v0.3.7|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20220803162953-67bda5d908f1|间接依赖|go|
|go.uber.org/zap|v1.19.1|间接依赖|go|
|github.com/texttheater/golang-levenshtein|v0.0.0-20191208221605-eb6844b05fc6|间接依赖|go|
|golang.org/x/net|v0.0.0-20220127200216-cd36cc0744dd|间接依赖|go|
|gopkg.in/warnings.v0|v0.1.2|间接依赖|go|
|golang.org/x/sys|v0.0.0-20220811171246-fbc7d0a398ab|间接依赖|go|
|github.com/imdario/mergo|v0.3.6|间接依赖|go|
|golang.org/x/mod|v0.6.0-dev.0.20220419223038-86c51ed26bb4|间接依赖|go|
|github.com/emicklei/go-restful/v3|v3.8.0|间接依赖|go|
|golang.org/x/sys|v0.0.0-20210831042530-f4d43177bf5e|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|gomodules.xyz/jsonpatch/v2|v2.2.0|间接依赖|go|
|github.com/nxadm/tail|v1.4.8|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/jbenet/go-context|v0.0.0-20150711004518-d14ea06fba99|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.8|间接依赖|go|
|lukechampine.com/frand|v1.4.2|间接依赖|go|
|github.com/gobuffalo/flect|v0.2.3|间接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|go.uber.org/atomic|v1.7.0|间接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.5|间接依赖|go|
|golang.org/x/time|v0.0.0-20210723032227-1f47c861a9ac|间接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|golang.org/x/net|v0.0.0-20211209124913-491a49abca63|间接依赖|go|
|k8s.io/client-go|v0.23.5|直接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|github.com/onsi/ginkgo|v1.16.5|直接依赖|go|
|github.com/gofrs/uuid|v3.3.0+incompatible|间接依赖|go|
|sourcegraph.com/sourcegraph/appdash|v0.0.0-20190731080439-ebfcffb1b5c0|间接依赖|go|
|k8s.io/utils|v0.0.0-20220728103510-ee6ede2d64ed|间接依赖|go|
|golang.org/x/tools|v0.1.12|间接依赖|go|
|github.com/mitchellh/go-ps|v1.0.0|间接依赖|go|
|k8s.io/utils|v0.0.0-20210930125809-cb0fa318a74b|间接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.2-0.20181231171920-c182affec369|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20211115234752-e816edb12b65|间接依赖|go|
|gopkg.in/src-d/go-billy.v4|v4.3.2|间接依赖|go|
|github.com/emirpasic/gods|v1.12.0|间接依赖|go|
|github.com/djherbis/times|v1.2.0|间接依赖|go|
|github.com/cdk8s-team/cdk8s-core-go/cdk8s/v2|v2.5.32|直接依赖|go|
|github.com/sabhiram/go-gitignore|v0.0.0-20180611051255-d3107576ba94|间接依赖|go|
|k8s.io/api|v0.25.0|直接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/stretchr/testify|v1.7.0|间接依赖|go|
|golang.org/x/xerrors|v0.0.0-20200804184101-5ec99f83aff1|间接依赖|go|
|github.com/Azure/go-autorest/logger|v0.2.1|间接依赖|go|
|github.com/aws/jsii-runtime-go|v1.70.0|直接依赖|go|
|go.uber.org/multierr|v1.6.0|间接依赖|go|
|github.com/mailru/easyjson|v0.7.6|间接依赖|go|
|google.golang.org/grpc|v1.36.1|间接依赖|go|
|github.com/Azure/go-autorest|v14.2.0+incompatible|间接依赖|go|
|github.com/imdario/mergo|v0.3.12|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|cloud.google.com/go|v0.81.0|间接依赖|go|
|k8s.io/apiextensions-apiserver|v0.23.5|间接依赖|go|
|golang.org/x/lint|v0.0.0-20210508222113-6edffad5e616|间接依赖|go|
|github.com/prometheus/client_golang|v1.11.0|间接依赖|go|
|golang.org/x/net|v0.0.0-20220722155237-a158d28d115b|间接依赖|go|
|github.com/spf13/cobra|v1.4.0|间接依赖|go|
|k8s.io/api|v0.23.0|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.16|间接依赖|go|
|github.com/grpc-ecosystem/grpc-opentracing|v0.0.0-20180507213350-8e809c8a8645|间接依赖|go|
|github.com/yuin/goldmark|v1.4.13|间接依赖|go|
|github.com/fatih/color|v1.12.0|间接依赖|go|
|google.golang.org/protobuf|v1.28.0|间接依赖|go|
|golang.org/x/time|v0.0.0-20220210224613-90d013bbcef8|间接依赖|go|
|github.com/go-logr/logr|v1.2.3|间接依赖|go|
|github.com/PuerkitoBio/urlesc|v0.0.0-20170810143723-de5bf2ad4578|间接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/prometheus/procfs|v0.6.0|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|golang.org/x/tools|v0.1.6-0.20210820212750-d4cc65f0b2ff|间接依赖|go|
|github.com/aead/chacha20|v0.0.0-20180709150244-8b13a72661da|间接依赖|go|
|k8s.io/apimachinery|v0.23.0|间接依赖|go|
|sigs.k8s.io/controller-runtime|v0.11.2|直接依赖|go|
|github.com/inconshreveable/mousetrap|v1.0.0|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)