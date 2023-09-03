# kubernetes/minikube安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698398874493566976.svg)](https://www.murphysec.com/console/report/1698398874413875200/1698398874493566976)

仓库描述：Run Kubernetes locally

仓库地址：[https://github.com/kubernetes/minikube](https://github.com/kubernetes/minikube)

| star：27158 | watch：490 | fork：4723 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-03 05:14:40 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-04 02:14:59 | 组件总数：427 | 漏洞总数：18 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|lodash <4.17.15 原型污染漏洞|原型污染|[MPS-2020-15679](https://www.oscs1024.com/hd/MPS-2020-15679)|CVE-2020-8203|高危|
|Yargs Y18n 输入原型污染漏洞|动态确定对象属性修改的控制不恰当|[MPS-2020-17543](https://www.oscs1024.com/hd/MPS-2020-17543)|CVE-2020-7774|严重|
|yargs-parser 原型污染漏洞|特权定义了不安全动作|[MPS-2020-4006](https://www.oscs1024.com/hd/MPS-2020-4006)|CVE-2020-7608|中危|
|lodash 拒绝服务漏洞|拒绝服务|[MPS-2021-2574](https://www.oscs1024.com/hd/MPS-2021-2574)|CVE-2020-28500|中危|
|lodash 命令注入漏洞|代码注入|[MPS-2021-2638](https://www.oscs1024.com/hd/MPS-2021-2638)|CVE-2021-23337|高危|
|minimist 安全漏洞|原型污染|[MPS-2021-38405](https://www.oscs1024.com/hd/MPS-2021-38405)|CVE-2021-44906|严重|
|postcss 存在正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-5409](https://www.oscs1024.com/hd/MPS-2021-5409)|CVE-2021-23382|中危|
|browserslist 存在正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-5473](https://www.oscs1024.com/hd/MPS-2021-5473)|CVE-2021-23364|中危|
|glob-parent < 5.1.2 存在拒绝服务漏洞|拒绝服务|[MPS-2021-7827](https://www.oscs1024.com/hd/MPS-2021-7827)|CVE-2020-28469|高危|
|lodash<4.17.20 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13841](https://www.oscs1024.com/hd/MPS-2022-13841)||高危|
|lodash<4.17.17 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13842](https://www.oscs1024.com/hd/MPS-2022-13842)||高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|decode-uri-component <=0.2.0 存在输入验证不当漏洞|拒绝服务|[MPS-2022-56259](https://www.oscs1024.com/hd/MPS-2022-56259)|CVE-2022-38900|高危|
|minimatch 资源管理错误漏洞|拒绝服务|[MPS-2022-59845](https://www.oscs1024.com/hd/MPS-2022-59845)|CVE-2022-3517|高危|
|Google Go 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2022-9049](https://www.oscs1024.com/hd/MPS-2022-9049)|CVE-2022-29526|中危|
|Moby 安全漏洞||[MPS-2023-8823](https://www.oscs1024.com/hd/MPS-2023-8823)|CVE-2023-28840|高危|
|Moby 安全漏洞||[MPS-2023-8824](https://www.oscs1024.com/hd/MPS-2023-8824)|CVE-2023-28841|中危|
|Moby 安全漏洞||[MPS-2023-8826](https://www.oscs1024.com/hd/MPS-2023-8826)|CVE-2023-28842|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|minimist|1.2.5|1.2.6|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|y18n|3.2.1|5.0.5|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|minimatch|3.0.4|3.0.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|glob-parent|3.1.0|6.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|lodash|4.17.15|4.17.21|间接依赖|建议修复|C:0|H:4|M:1|L:0|
|github.com/docker/docker|v1.13.1|23.0.3|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|decode-uri-component|0.2.0|0.2.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|postcss|6.0.23|8.2.13|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|5.6.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|golang.org/x/sys|v0.0.0-20200124204421-9fbb57f87de9|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|browserslist|4.4.1|4.16.5|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|yargs-parser|9.0.2|18.1.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|224|Low|
|BSD-3-Clause|54|Low|
|Apache-2.0|92|Low|
|ISC|23|Low|
|LGPL-3.0|4|Medium|
|MPL-2.0|12|Low|
|BSD-2-Clause|9|Low|
|OFL-1.1|1|Low|
|CC-BY-4.0|2|Low|
|CC-BY-SA-4.0|1|Medium|
|BSD|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/bgentry/go-netrc|v0.0.0-20140422174119-9fd32a8b3d3d|间接依赖|go|
|github.com/imdario/mergo|v0.3.12|间接依赖|go|
|contrib.go.opencensus.io/exporter/stackdriver|v0.13.14|直接依赖|go|
|github.com/cloudflare/circl|v1.3.3|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230803162519-f966b187b2e5|间接依赖|go|
|os-locale|3.1.0|间接依赖|npm|
|parse-json|2.2.0|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|github.com/google/go-github/v54|v54.0.0|直接依赖|go|
|postcss-load-plugins|2.3.0|间接依赖|npm|
|github.com/docker/go-units|v0.5.0|直接依赖|go|
|p-limit|1.3.0|间接依赖|npm|
|source-map|0.5.7|间接依赖|npm|
|github.com/juju/clock|v1.0.3|直接依赖|go|
|github.com/google/uuid|v1.3.1|直接依赖|go|
|component-emitter|1.3.0|间接依赖|npm|
|shebang-command|1.2.0|间接依赖|npm|
|ignore|3.3.10|间接依赖|npm|
|jsonfile|4.0.0|间接依赖|npm|
|array-union|1.0.2|间接依赖|npm|
|go.opencensus.io|v0.24.0|直接依赖|go|
|safe-regex|1.1.0|间接依赖|npm|
|decode-uri-component|0.2.0|间接依赖|npm|
|github.com/hooklift/iso9660|v0.0.0-20170318115843-1cf07e5970d8|间接依赖|go|
|golang.org/x/term|v0.11.0|直接依赖|go|
|github.com/go-pdf/fpdf|v0.8.0|间接依赖|go|
|esprima|4.0.1|间接依赖|npm|
|github.com/hashicorp/go-version|v1.6.0|间接依赖|go|
|js-yaml|3.13.1|间接依赖|npm|
|github.com/GoogleCloudPlatform/cloudsql-proxy|v1.33.10|直接依赖|go|
|path-exists|3.0.0|间接依赖|npm|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|lcid|2.0.0|间接依赖|npm|
|code-point-at|1.1.0|直接依赖|npm|
|github.com/containerd/stargz-snapshotter/estargz|v0.14.3|间接依赖|go|
|k8s.io/kubectl|v0.28.1|直接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|github.com/tklauser/numcpus|v0.6.0|间接依赖|go|
|object.pick|1.3.0|间接依赖|npm|
|github.com/spf13/viper|v1.16.0|直接依赖|go|
|github.com/containerd/containerd|v1.6.19|间接依赖|go|
|github.com/google/go-containerregistry|v0.16.1|直接依赖|go|
|postcss-load-options|1.2.0|间接依赖|npm|
|get-stream|4.1.0|间接依赖|npm|
|source-map-resolve|0.5.2|间接依赖|npm|
|os-homedir|1.0.2|间接依赖|npm|
|map-age-cleaner|0.1.3|间接依赖|npm|
|gopkg.in/ini.v1|v1.67.0|间接依赖|go|
|require-from-string|1.2.1|间接依赖|npm|
|github.com/moby/sys/sequential|v0.5.0|间接依赖|go|
|urix|0.1.0|间接依赖|npm|
|fs-extra|5.0.0|间接依赖|npm|
|color-name|1.1.1|间接依赖|npm|
|github.com/evanphx/json-patch|v5.6.0+incompatible|间接依赖|go|
|bindings|1.5.0|间接依赖|npm|
|github.com/juju/errors|v0.0.0-20220203013757-bd733f3c86b9|间接依赖|go|
|k8s.io/cluster-bootstrap|v0.0.0|直接依赖|go|
|libvirt-qemu.so.0||间接依赖||
|github.com/google/pprof|v0.0.0-20220318212150-b2ab0324ddda|间接依赖|go|
|path-type|3.0.0|间接依赖|npm|
|string_decoder|1.1.1|间接依赖|npm|
|read-cache|1.0.0|间接依赖|npm|
|to-regex|3.0.2|间接依赖|npm|
|github.com/felixge/fgprof|v0.9.3|间接依赖|go|
|github.com/Azure/go-ansiterm|v0.0.0-20210617225240-d185dfc1b5a1|间接依赖|go|
|github.com/google/gnostic-models|v0.6.8|间接依赖|go|
|slash|1.0.0|间接依赖|npm|
|github.com/phayes/freeport|v0.0.0-20180830031419-95f893ade6f2|直接依赖|go|
|go.opentelemetry.io/otel/trace|v1.17.0|直接依赖|go|
|signal-exit|3.0.3|间接依赖|npm|
|github.com/pkg/profile|v1.7.0|直接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|github.com/go-openapi/swag|v0.22.3|间接依赖|go|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|@mrmlnc/readdir-enhanced|2.2.1|间接依赖|npm|
|github.com/ulikunitz/xz|v0.5.10|间接依赖|go|
|snapdragon-node|2.1.1|间接依赖|npm|
|google.golang.org/grpc|v1.57.0|间接依赖|go|
|github.com/docker/machine|v0.16.2|直接依赖|go|
|github.com/santhosh-tekuri/jsonschema/v5|v5.3.1|直接依赖|go|
|github.com/fatih/color|v1.15.0|间接依赖|go|
|github.com/hashicorp/go-getter|v1.7.2|直接依赖|go|
|github.com/MakeNowJust/heredoc|v1.0.0|间接依赖|go|
|decamelize|1.2.0|间接依赖|npm|
|postcss|6.0.23|间接依赖|npm|
|pify|3.0.0|间接依赖|npm|
|argparse|1.0.10|间接依赖|npm|
|github.com/cenkalti/backoff/v4|v4.2.1|直接依赖|go|
|github.com/otiai10/copy|v1.12.0|直接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.2|间接依赖|go|
|github.com/docker/docker|v24.0.5+incompatible|直接依赖|go|
|github.com/juju/fslock|v0.0.0-20160525022230-4d5c94c67b4b|直接依赖|go|
|github.com/spf13/cobra|v1.7.0|直接依赖|go|
|cosmiconfig|2.2.2|间接依赖|npm|
|github.com/mattn/go-isatty|v0.0.19|直接依赖|go|
|cliui|4.1.0|间接依赖|npm|
|mixin-deep|1.3.2|间接依赖|npm|
|arr-flatten|1.1.0|间接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|github.com/moby/sys/mountinfo|v0.6.2|间接依赖|go|
|error-ex|1.3.2|间接依赖|npm|
|string-width|2.1.1|间接依赖|npm|
|is-directory|0.3.1|间接依赖|npm|
|github.com/mitchellh/mapstructure|v1.5.0|间接依赖|go|
|fill-range|4.0.0|间接依赖|npm|
|pump|3.0.0|间接依赖|npm|
|repeat-element|1.1.3|间接依赖|npm|
|github.com/power-devops/perfstat|v0.0.0-20210106213030-5aafc221ea8c|间接依赖|go|
|github.com/mattn/go-runewidth|v0.0.14|间接依赖|go|
|github.com/lib/pq|v1.10.9|间接依赖|go|
|github.com/spf13/cast|v1.5.1|间接依赖|go|
|github.com/hectane/go-acl|v0.0.0-20190604041725-da78bae5fc95|间接依赖|go|
|github.com/go-fonts/liberation|v0.3.1|间接依赖|go|
|ansi-styles|3.2.1|间接依赖|npm|
|github.com/machine-drivers/docker-machine-driver-vmware|v0.1.5|直接依赖|go|
|sigs.k8s.io/json|v0.0.0-20221116044647-bc3834ca7abd|间接依赖|go|
|github.com/godbus/dbus/v5|v5.0.6|间接依赖|go|
|extend-shallow|3.0.2|间接依赖|npm|
|github.com/docker/docker|v1.13.1|间接依赖|go|
|which|1.3.1|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|github.com/cheggaaa/pb/v3|v3.1.4|直接依赖|go|
|github.com/hooklift/assert|v0.0.0-20170704181755-9d1defd6d214|间接依赖|go|
|github.com/hashicorp/go-safetemp|v1.0.0|间接依赖|go|
|nanomatch|1.2.13|间接依赖|npm|
|go.opentelemetry.io/otel/metric|v1.17.0|间接依赖|go|
|github.com/spf13/jwalterweatherman|v1.1.0|间接依赖|go|
|array-uniq|1.0.3|间接依赖|npm|
|merge2|1.2.3|间接依赖|npm|
|async-each|1.0.3|间接依赖|npm|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|browserslist|4.4.1|间接依赖|npm|
|num2fraction|1.2.2|间接依赖|npm|
|universalify|0.1.2|间接依赖|npm|
|github.com/GoogleCloudPlatform/opentelemetry-operations-go/internal/resourcemapping|v0.42.0|间接依赖|go|
|github.com/blang/semver/v4|v4.0.0|直接依赖|go|
|golang.org/x/oauth2|v0.11.0|直接依赖|go|
|snapdragon-util|3.0.1|间接依赖|npm|
|github.com/lufia/plan9stats|v0.0.0-20211012122336-39d0f177ccd0|间接依赖|go|
|dependency-graph|0.7.2|间接依赖|npm|
|cache-base|1.0.1|间接依赖|npm|
|github.com/golang-collections/collections|v0.0.0-20130729185459-604e922904d3|直接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.3|间接依赖|go|
|sigs.k8s.io/sig-storage-lib-external-provisioner/v6|v6.3.0|直接依赖|go|
|golang.org/x/build|v0.0.0-20190927031335-2835ba2e683f|直接依赖|go|
|github.com/hashicorp/go-retryablehttp|v0.7.4|直接依赖|go|
|github.com/cyphar/filepath-securejoin|v0.2.3|间接依赖|go|
|github.com/google/slowjam|v1.0.1|直接依赖|go|
|get-stdin|6.0.0|间接依赖|npm|
|github.com/johanneswuerbach/nfsexports|v0.0.0-20200318065542-c48c3734757f|直接依赖|go|
|github.com/google/go-querystring|v1.1.0|间接依赖|go|
|github.com/prometheus/prometheus|v0.35.0|间接依赖|go|
|map-cache|0.2.2|间接依赖|npm|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|cloud.google.com/go/iam|v1.1.1|间接依赖|go|
|brace-expansion|1.1.11|间接依赖|npm|
|ret|0.1.15|间接依赖|npm|
|source-map-url|0.4.0|间接依赖|npm|
|github.com/kballard/go-shellquote|v0.0.0-20180428030007-95032a82bc51|直接依赖|go|
|is-descriptor|0.1.6|间接依赖|npm|
|is-number|3.0.0|间接依赖|npm|
|is-extendable|0.1.1|间接依赖|npm|
|github.com/VividCortex/ewma|v1.2.0|间接依赖|go|
|node-releases|1.1.3|间接依赖|npm|
|ansi-regex|3.0.0|间接依赖|npm|
|extglob|2.0.4|间接依赖|npm|
|github.com/magiconair/properties|v1.8.7|间接依赖|go|
|golang.org/x/sync|v0.3.0|直接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|gonum.org/v1/plot|v0.13.0|直接依赖|go|
|kind-of|6.0.3|间接依赖|npm|
|github.com/cpuguy83/go-md2man/v2|v2.0.2|间接依赖|go|
|github.com/zchee/go-vmnet|v0.0.0-20161021174912-97ebf9174097|直接依赖|go|
|p-locate|2.0.0|间接依赖|npm|
|isarray|1.0.0|间接依赖|npm|
|github.com/intel-go/cpuid|v0.0.0-20181003105527-1a4a6f06a1c6|间接依赖|go|
|cloud.google.com/go|v0.110.6|间接依赖|go|
|github.com/elazarl/goproxy|v0.0.0-20210110162100-a92cc753f88e|直接依赖|go|
|debug|2.6.9|间接依赖|npm|
|mem|4.3.0|间接依赖|npm|
|google.golang.org/api|v0.138.0|直接依赖|go|
|cloud.google.com/go/storage|v1.32.0|直接依赖|go|
|github.com/moby/patternmatcher|v0.6.0|直接依赖|go|
|file-uri-to-path|1.0.0|间接依赖|npm|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/googleapis/gax-go/v2|v2.12.0|间接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|chalk|2.4.2|间接依赖|npm|
|p-is-promise|2.1.0|间接依赖|npm|
|which-module|2.0.0|间接依赖|npm|
|github.com/subosito/gotenv|v1.4.2|间接依赖|go|
|github.com/moby/spdystream|v0.2.0|间接依赖|go|
|github.com/opencontainers/runtime-spec|v1.1.0-rc.1|间接依赖|go|
|github.com/ajstarks/svgo|v0.0.0-20211024235047-1546f124cd8b|间接依赖|go|
|is-glob|4.0.1|间接依赖|npm|
|fsevents|1.2.12|间接依赖|npm|
|github.com/samalba/dockerclient|v0.0.0-20160414174713-91d7393ff859|间接依赖|go|
|go.uber.org/zap|v1.24.0|间接依赖|go|
|github.com/mitchellh/go-ps|v0.0.0-20170309133038-4fdf99ab2936|间接依赖|go|
|util-deprecate|1.0.2|间接依赖|npm|
|braces|2.3.2|间接依赖|npm|
|github.com/pkg/browser|v0.0.0-20210911075715-681adbf594b8|直接依赖|go|
|github.com/docker/cli|v24.0.5+incompatible|直接依赖|go|
|assign-symbols|1.0.0|间接依赖|npm|
|github.com/Delta456/box-cli-maker/v2|v2.3.0|直接依赖|go|
|github.com/jmoiron/sqlx|v1.3.5|直接依赖|go|
|glob-parent|3.1.0|间接依赖|npm|
|github.com/sirupsen/logrus|v1.9.1|间接依赖|go|
|balanced-match|1.0.0|间接依赖|npm|
|golang.org/x/net|v0.14.0|间接依赖|go|
|github.com/prometheus/procfs|v0.10.1|间接依赖|go|
|github.com/Xuanwo/go-locale|v1.1.0|直接依赖|go|
|class-utils|0.3.6|间接依赖|npm|
|github.com/opencontainers/go-digest|v1.0.0|直接依赖|go|
|set-blocking|2.0.0|间接依赖|npm|
|upath|1.2.0|间接依赖|npm|
|github.com/hooklift/iso9660|v1.0.0|直接依赖|go|
|github.com/vbatts/tar-split|v0.11.3|间接依赖|go|
|call-me-maybe|1.0.1|间接依赖|npm|
|github.com/rivo/uniseg|v0.2.0|间接依赖|go|
|k8s.io/utils|v0.0.0-20230406110748-d93618cff8a2|直接依赖|go|
|postcss-cli|5.0.1|直接依赖|npm|
|github.com/briandowns/spinner|v1.11.1|直接依赖|go|
|google.golang.org/genproto/googleapis/api|v0.0.0-20230803162519-f966b187b2e5|间接依赖|go|
|k8s.io/client-go|v0.28.1|直接依赖|go|
|github.com/docker/docker-credential-helpers|v0.7.0|间接依赖|go|
|@nodelib/fs.stat|1.1.3|间接依赖|npm|
|github.com/fsnotify/fsnotify|v1.6.0|间接依赖|go|
|path-dirname|1.0.2|间接依赖|npm|
|resolve-url|0.2.1|间接依赖|npm|
|go.opentelemetry.io/otel|v1.17.0|直接依赖|go|
|supports-color|5.5.0|间接依赖|npm|
|nan|2.14.0|间接依赖|npm|
|github.com/mitchellh/go-ps|v1.0.0|直接依赖|go|
|golang.org/x/image|v0.7.0|间接依赖|go|
|arr-diff|4.0.0|间接依赖|npm|
|atob|2.1.2|间接依赖|npm|
|github.com/moby/hyperkit|v0.0.0-20210108224842-2f061e447e14|直接依赖|go|
|github.com/shirou/gopsutil/v3|v3.23.7|直接依赖|go|
|golang.org/x/tools|v0.9.1|间接依赖|go|
|github.com/golang/glog|v0.0.0-20160126235308-23def4e6c14b|间接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230807174057-1744710a1577|间接依赖|go|
|graceful-fs|4.2.0|间接依赖|npm|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|golang.org/x/text|v0.12.0|直接依赖|go|
|yargs|11.1.1|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|github.com/emicklei/go-restful/v3|v3.9.0|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|直接依赖|go|
|github.com/moby/hyperkit|v0.0.0-20171020124204-a12cd7250bcd|间接依赖|go|
|github.com/census-instrumentation/opencensus-proto|v0.4.1|间接依赖|go|
|k8s.io/apimachinery|v0.28.1|直接依赖|go|
|is-binary-path|1.0.1|间接依赖|npm|
|mimic-fn|2.1.0|间接依赖|npm|
|github.com/blang/semver|v3.5.1+incompatible|直接依赖|go|
|google.golang.org/protobuf|v1.31.0|间接依赖|go|
|go.uber.org/atomic|v1.10.0|间接依赖|go|
|pretty-hrtime|1.0.3|间接依赖|npm|
|minimatch|3.0.4|间接依赖|npm|
|strip-eof|1.0.0|间接依赖|npm|
|k8s.io/kube-openapi|v0.0.0-20230717233707-2695361300d9|间接依赖|go|
|y18n|3.2.1|间接依赖|npm|
|gopkg.in/yaml.v2|v2.4.0|直接依赖|go|
|use|3.1.1|间接依赖|npm|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|fast-glob|2.2.7|间接依赖|npm|
|execa|1.0.0|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|github.com/google/s2a-go|v0.1.5|间接依赖|go|
|github.com/ProtonMail/go-crypto|v0.0.0-20230217124315-7d5c6f04bbb8|间接依赖|go|
|golang.org/x/mod|v0.12.0|直接依赖|go|
|github.com/muesli/reflow|v0.3.0|间接依赖|go|
|repeat-string|1.6.1|间接依赖|npm|
|cloud.google.com/go/trace|v1.10.1|间接依赖|go|
|fragment-cache|0.2.1|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|github.com/mitchellh/go-wordwrap|v1.0.1|间接依赖|go|
|caniuse-lite|1.0.30000932|间接依赖|npm|
|github.com/go-openapi/jsonpointer|v0.19.6|间接依赖|go|
|golang.org/x/xerrors|v0.0.0-20220907171357-04be3eba64a2|间接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|github.com/miekg/dns|v1.1.48|间接依赖|go|
|go.uber.org/multierr|v1.11.0|间接依赖|go|
|github.com/c4milo/gotoolkit|v0.0.0-20170318115440-bcc06269efa9|间接依赖|go|
|libvirt.so.0||间接依赖||
|github.com/aws/aws-sdk-go|v1.44.122|间接依赖|go|
|k8s.io/component-base|v0.28.1|直接依赖|go|
|array-unique|0.3.2|间接依赖|npm|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|github.com/pelletier/go-toml/v2|v2.0.8|间接依赖|go|
|sprintf-js|1.0.3|间接依赖|npm|
|readable-stream|2.3.7|间接依赖|npm|
|github.com/go-ole/go-ole|v1.2.6|间接依赖|go|
|/System/Library/Frameworks/Security.framework/Versions/A/Security||间接依赖||
|github.com/docker/go-connections|v0.4.0|直接依赖|go|
|dir-glob|2.0.0|间接依赖|npm|
|github.com/opencontainers/runc|v1.1.9|直接依赖|go|
|get-caller-file|1.0.3|间接依赖|npm|
|/System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation||间接依赖||
|snapdragon|0.8.2|间接依赖|npm|
|github.com/yusufpapurcu/wmi|v1.2.3|间接依赖|go|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|electron-to-chromium|1.3.108|间接依赖|npm|
|github.com/klauspost/cpuid|v1.2.0|直接依赖|go|
|semver|5.6.0|间接依赖|npm|
|golang.org/x/sys|v0.0.0-20200124204421-9fbb57f87de9|间接依赖|go|
|glob-to-regexp|0.3.0|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|is-fullwidth-code-point|2.0.0|间接依赖|npm|
|github.com/russross/blackfriday/v2|v2.1.0|间接依赖|go|
|color-convert|1.9.2|间接依赖|npm|
|github.com/klauspost/compress|v1.16.5|间接依赖|go|
|ms|2.0.0|间接依赖|npm|
|nice-try|1.0.5|间接依赖|npm|
|github.com/spf13/afero|v1.9.5|间接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|golang.org/x/sys|v0.11.0|直接依赖|go|
|/System/Library/Frameworks/vmnet.framework/Versions/A/vmnet||间接依赖||
|strip-ansi|4.0.0|间接依赖|npm|
|find-up|2.1.0|间接依赖|npm|
|github.com/google/gofuzz|v1.2.0|间接依赖|go|
|github.com/huandu/xstrings|v1.3.2|间接依赖|go|
|inflight|1.0.6|间接依赖|npm|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|micromatch|3.1.10|间接依赖|npm|
|github.com/pborman/uuid|v1.2.1|直接依赖|go|
|invert-kv|2.0.0|间接依赖|npm|
|github.com/VividCortex/godaemon|v1.0.0|直接依赖|go|
|remove-trailing-separator|1.1.0|直接依赖|npm|
|arrify|1.0.1|间接依赖|npm|
|p-finally|1.0.0|间接依赖|npm|
|github.com/xo/terminfo|v0.0.0-20220910002029-abceb7e1c41e|间接依赖|go|
|github.com/gookit/color|v1.5.2|间接依赖|go|
|number-is-nan|1.0.1|直接依赖|npm|
|github.com/tklauser/go-sysconf|v0.3.11|间接依赖|go|
|normalize-range|0.1.2|间接依赖|npm|
|github.com/coreos/go-systemd/v22|v22.5.0|间接依赖|go|
|expand-brackets|2.1.4|间接依赖|npm|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|go.opentelemetry.io/otel/sdk|v1.17.0|直接依赖|go|
|escape-string-regexp|1.0.5|间接依赖|npm|
|postcss-load-config|1.2.0|间接依赖|npm|
|github.com/moby/term|v0.0.0-20221205130635-1aeaba878587|间接依赖|go|
|core-util-is|1.0.2|间接依赖|npm|
|github.com/hashicorp/go-cleanhttp|v0.5.2|间接依赖|go|
|/usr/lib/libSystem.B.dylib||间接依赖||
|golang.org/x/exp|v0.0.0-20230510235704-dd950f8aeaea|直接依赖|go|
|github.com/olekukonko/tablewriter|v0.0.5|直接依赖|go|
|path-key|2.0.1|间接依赖|npm|
|p-defer|1.0.0|间接依赖|npm|
|postcss-reporter|5.0.0|间接依赖|npm|
|to-regex-range|2.1.1|间接依赖|npm|
|k8s.io/api|v0.28.1|直接依赖|go|
|lodash|4.17.15|间接依赖|npm|
|golang.org/x/crypto|v0.12.0|直接依赖|go|
|github.com/fvbommel/sortorder|v1.1.0|间接依赖|go|
|inherits|2.0.4|间接依赖|npm|
|process-nextick-args|2.0.1|间接依赖|npm|
|github.com/docker/distribution|v2.8.2+incompatible|间接依赖|go|
|glob|7.1.4|间接依赖|npm|
|pascalcase|0.1.1|间接依赖|npm|
|github.com/mattbaird/jsonpatch|v0.0.0-20200820163806-098863c1fc24|直接依赖|go|
|readdirp|2.2.1|间接依赖|npm|
|chokidar|2.1.8|间接依赖|npm|
|github.com/juju/mutex/v2|v2.0.0|直接依赖|go|
|github.com/mitchellh/go-testing-interface|v1.14.1|间接依赖|go|
|cloud.google.com/go/compute|v1.23.0|间接依赖|go|
|split-string|3.1.0|间接依赖|npm|
|github.com/googleapis/enterprise-certificate-proxy|v0.2.5|间接依赖|go|
|git.sr.ht/~sbinet/gg|v0.4.1|间接依赖|go|
|wrap-ansi|2.1.0|间接依赖|npm|
|cross-spawn|6.0.5|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|postcss-value-parser|3.3.1|间接依赖|npm|
|cloud.google.com/go/monitoring|v1.15.1|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|locate-path|2.0.0|间接依赖|npm|
|cloud.google.com/go/compute/metadata|v0.2.3|间接依赖|go|
|golang.org/x/time|v0.3.0|间接依赖|go|
|minimist|1.2.5|间接依赖|npm|
|sigs.k8s.io/yaml|v1.3.0|间接依赖|go|
|path-is-absolute|1.0.1|间接依赖|npm|
|github.com/opencontainers/image-spec|v1.1.0-rc3|间接依赖|go|
|libpthread.so.0||间接依赖||
|github.com/shoenig/go-m1cpu|v0.1.6|间接依赖|go|
|log-symbols|2.2.0|间接依赖|npm|
|define-property|2.0.2|间接依赖|npm|
|npm-run-path|2.0.2|间接依赖|npm|
|github.com/jmespath/go-jmespath|v0.4.0|间接依赖|go|
|binary-extensions|1.13.1|间接依赖|npm|
|github.com/prometheus/client_model|v0.4.0|间接依赖|go|
|is-windows|1.0.2|间接依赖|npm|
|github.com/golang/freetype|v0.0.0-20170609003504-e2365dfdc4a0|间接依赖|go|
|anymatch|2.0.0|间接依赖|npm|
|golang.org/x/crypto|v0.0.0-20200302210943-78000ba7a073|间接依赖|go|
|k8s.io/klog/v2|v2.100.1|直接依赖|go|
|require-main-filename|1.0.1|间接依赖|npm|
|base|0.11.2|间接依赖|npm|
|libvirt.org/go/libvirt|v1.9002.0|直接依赖|go|
|libc.so.6||间接依赖||
|is-stream|1.1.0|间接依赖|npm|
|github.com/c4milo/gotoolkit|v0.0.0-20190525173301-67483a18c17a|间接依赖|go|
|isobject|3.0.1|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|github.com/go-latex/latex|v0.0.0-20230307184459-12ec69307ad9|间接依赖|go|
|github.com/Parallels/docker-machine-parallels/v2|v2.0.1|直接依赖|go|
|has-flag|3.0.0|间接依赖|npm|
|github.com/prometheus/client_golang|v1.16.0|间接依赖|go|
|github.com/Microsoft/go-winio|v0.6.1|间接依赖|go|
|globby|8.0.2|间接依赖|npm|
|autoprefixer|9.4.6|直接依赖|npm|
|is-buffer|1.1.6|直接依赖|npm|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|github.com/GoogleCloudPlatform/opentelemetry-operations-go/exporter/trace|v1.18.0|直接依赖|go|
|is-arrayish|0.2.1|间接依赖|npm|
|yargs-parser|9.0.2|间接依赖|npm|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/go-logr/logr|v1.2.4|间接依赖|go|
|github.com/prometheus/common|v0.44.0|间接依赖|go|
|github.com/docker/machine|v0.7.1-0.20190902101342-b170508bf44c|间接依赖|go|
|camelcase|4.1.0|间接依赖|npm|
|github.com/cloudevents/sdk-go/v2|v2.14.0|直接依赖|go|
|regex-not|1.0.2|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)