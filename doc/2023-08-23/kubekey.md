# kubesphere/kubekey安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694049837703323648.svg)](https://www.murphysec.com/console/report/1694049837619437568/1694049837703323648)

仓库描述：Install Kubernetes/K3s only, both Kubernetes/K3s and KubeSphere, and related cloud-native add-ons, it supports all-in-one, multi-node, and HA 🔥 ⎈ 🐳

仓库地址：[https://github.com/kubesphere/kubekey](https://github.com/kubesphere/kubekey)

| star：1741 | watch：41 | fork：450 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-22 14:39:58 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-23 02:12:30 | 组件总数：238 | 漏洞总数：14 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|containerd CRI stream server 存在拒绝服务漏洞|拒绝服务|[MPS-2022-1898](https://www.oscs1024.com/hd/MPS-2022-1898)|CVE-2022-23471|中危|
|Helm 资源管理错误漏洞|不加限制或调节的资源分配|[MPS-2022-1951](https://www.oscs1024.com/hd/MPS-2022-1951)|CVE-2022-23524|高危|
|Helm 代码问题漏洞|空指针取消引用|[MPS-2022-1952](https://www.oscs1024.com/hd/MPS-2022-1952)|CVE-2022-23525|高危|
|Helm 代码问题漏洞|空指针取消引用|[MPS-2022-1953](https://www.oscs1024.com/hd/MPS-2022-1953)|CVE-2022-23526|高危|
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58307](https://www.oscs1024.com/hd/MPS-2022-58307)|CVE-2022-41723|高危|
|HashiCorp go-getter 安全漏洞|拒绝服务|[MPS-2023-2834](https://www.oscs1024.com/hd/MPS-2023-2834)|CVE-2023-0475|中危|
|containerd 安全漏洞|不加限制或调节的资源分配|[MPS-2023-3769](https://www.oscs1024.com/hd/MPS-2023-3769)|CVE-2023-25153|中危|
|Helm 信息泄露漏洞|未授权敏感信息泄露|[MPS-2023-3781](https://www.oscs1024.com/hd/MPS-2023-3781)|CVE-2023-25165|中危|
|containerd容器内文件权限机制实现不当|将用户置入不正确的用户组|[MPS-2023-3789](https://www.oscs1024.com/hd/MPS-2023-3789)|CVE-2023-25173|中危|
|runc 安全漏洞|使用不正确的解析名称或索引|[MPS-2023-6887](https://www.oscs1024.com/hd/MPS-2023-6887)|CVE-2023-27561|高危|
|runc <1.1.5 AppArmor限制绕过漏洞|访问控制不当|[MPS-2023-8507](https://www.oscs1024.com/hd/MPS-2023-8507)|CVE-2023-28642|高危|
|Moby 安全漏洞||[MPS-2023-8823](https://www.oscs1024.com/hd/MPS-2023-8823)|CVE-2023-28840|高危|
|Moby 安全漏洞||[MPS-2023-8824](https://www.oscs1024.com/hd/MPS-2023-8824)|CVE-2023-28841|中危|
|Moby 安全漏洞|对异常条件的处理不恰当|[MPS-2023-8826](https://www.oscs1024.com/hd/MPS-2023-8826)|CVE-2023-28842|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/docker/docker|v20.10.18+incompatible|23.0.3|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|golang.org/x/net|v0.1.0|0.7.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|github.com/opencontainers/runc|v1.1.4|1.1.5|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|helm.sh/helm/v3|v3.9.4|3.11.1|直接依赖|可选修复|C:0|H:3|M:1|L:0|
|github.com/hashicorp/go-getter|v1.6.2|2.1.0|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|github.com/containerd/containerd|v1.6.10|1.6.18|直接依赖|可选修复|C:0|H:0|M:3|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|87|Low|
|MPL-2.0|7|Low|
|Apache-2.0|96|Low|
|BSD-3-Clause|45|Low|
|ISC|2|Low|
|CC-BY-SA-4.0|2|Medium|
|BSD-2-Clause|5|Low|
|Unlicense|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/Masterminds/squirrel|v1.5.3|间接依赖|go|
|github.com/hashicorp/go-getter|v1.6.2|直接依赖|go|
|github.com/containers/libtrust|v0.0.0-20200511145503-9c3a6c22cd9a|间接依赖|go|
|github.com/opencontainers/image-spec|v1.1.0-rc1|直接依赖|go|
|github.com/coredns/caddy|v1.1.0|间接依赖|go|
|github.com/google/go-github/v45|v45.2.0|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.14|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.0.0|间接依赖|go|
|github.com/go-errors/errors|v1.0.1|间接依赖|go|
|github.com/googleapis/go-type-adapters|v1.0.0|间接依赖|go|
|github.com/mitchellh/go-testing-interface|v1.14.1|间接依赖|go|
|github.com/sirupsen/logrus|v1.9.0|直接依赖|go|
|gopkg.in/ini.v1|v1.66.4|间接依赖|go|
|github.com/ostreedev/ostree-go|v0.0.0-20210805093236-719684c64e4f|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.1.2|间接依赖|go|
|github.com/xeipuuv/gojsonschema|v1.2.0|间接依赖|go|
|github.com/Azure/go-ansiterm|v0.0.0-20210617225240-d185dfc1b5a1|间接依赖|go|
|github.com/prometheus/client_model|v0.2.0|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|k8s.io/client-go|v0.25.4|直接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.2-0.20181231171920-c182affec369|间接依赖|go|
|go.starlark.net|v0.0.0-20200306205701-8dd3e2ee1dd5|间接依赖|go|
|github.com/deislabs/oras|v0.9.0|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/gobuffalo/flect|v0.2.5|间接依赖|go|
|github.com/evanphx/json-patch/v5|v5.6.0|间接依赖|go|
|github.com/chai2010/gettext-go|v1.0.2|间接依赖|go|
|github.com/mitchellh/reflectwalk|v1.0.2|间接依赖|go|
|sigs.k8s.io/yaml|v1.3.0|直接依赖|go|
|github.com/lestrrat-go/file-rotatelogs|v2.4.0+incompatible|直接依赖|go|
|github.com/stoewer/go-strcase|v1.2.0|间接依赖|go|
|github.com/docker/go-metrics|v0.0.1|间接依赖|go|
|github.com/spf13/viper|v1.12.0|直接依赖|go|
|github.com/klauspost/pgzip|v1.2.5|间接依赖|go|
|go.etcd.io/bbolt|v1.3.6|间接依赖|go|
|github.com/bgentry/go-netrc|v0.0.0-20140422174119-9fd32a8b3d3d|间接依赖|go|
|gopkg.in/square/go-jose.v2|v2.6.0|间接依赖|go|
|github.com/Masterminds/sprig/v3|v3.2.2|间接依赖|go|
|google.golang.org/protobuf|v1.28.1|间接依赖|go|
|github.com/jinzhu/copier|v0.3.5|直接依赖|go|
|k8s.io/cluster-bootstrap|v0.25.4|直接依赖|go|
|github.com/googleapis/enterprise-certificate-proxy|v0.1.0|间接依赖|go|
|go.opencensus.io|v0.23.0|间接依赖|go|
|github.com/Masterminds/semver/v3|v3.1.1|间接依赖|go|
|github.com/containerd/containerd|v1.6.10|直接依赖|go|
|github.com/golang/protobuf|v1.5.2|间接依赖|go|
|k8s.io/klog/v2|v2.70.1|直接依赖|go|
|github.com/google/gnostic|v0.5.7-v3refs|间接依赖|go|
|gomodules.xyz/jsonpatch/v2|v2.2.0|间接依赖|go|
|github.com/Azure/go-autorest/logger|v0.2.1|间接依赖|go|
|github.com/PuerkitoBio/purell|v1.1.1|间接依赖|go|
|github.com/containerd/stargz-snapshotter/estargz|v0.12.0|间接依赖|go|
|github.com/xlab/treeprint|v1.1.0|间接依赖|go|
|go.uber.org/atomic|v1.9.0|间接依赖|go|
|github.com/liggitt/tabwriter|v0.0.0-20181228230101-89fcab3d43de|间接依赖|go|
|github.com/Microsoft/hcsshim|v0.9.5|间接依赖|go|
|github.com/Azure/go-autorest/autorest/adal|v0.9.20|间接依赖|go|
|cloud.google.com/go/storage|v1.23.0|间接依赖|go|
|github.com/morikuni/aec|v1.0.0|间接依赖|go|
|github.com/go-openapi/swag|v0.19.14|间接依赖|go|
|k8s.io/apimachinery|v0.25.4|直接依赖|go|
|github.com/acarl005/stripansi|v0.0.0-20180116102854-5a71ef0e047d|间接依赖|go|
|github.com/modood/table|v0.0.0-20220527013332-8d47e76dad33|直接依赖|go|
|golang.org/x/sys|v0.1.0|间接依赖|go|
|github.com/Microsoft/go-winio|v0.5.2|间接依赖|go|
|gopkg.in/tomb.v1|v1.0.0-20141024135613-dd632973f1e7|间接依赖|go|
|github.com/blang/semver|v3.5.1+incompatible|直接依赖|go|
|github.com/lestrrat-go/strftime|v1.0.5|间接依赖|go|
|golang.org/x/sync|v0.0.0-20220722155255-886fb9371eb4|间接依赖|go|
|github.com/containers/image/v5|v5.21.1|直接依赖|go|
|github.com/estesp/manifest-tool/v2|v2.0.3|直接依赖|go|
|github.com/google/cel-go|v0.12.5|间接依赖|go|
|github.com/klauspost/compress|v1.15.11|间接依赖|go|
|sigs.k8s.io/controller-runtime|v0.12.3|直接依赖|go|
|github.com/prometheus/client_golang|v1.12.2|间接依赖|go|
|helm.sh/helm/v3|v3.9.4|直接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/go-gorp/gorp/v3|v3.0.2|间接依赖|go|
|github.com/gregjones/httpcache|v0.0.0-20180305231024-9cad4c3443a7|间接依赖|go|
|github.com/Azure/go-autorest/autorest|v0.11.28|间接依赖|go|
|github.com/magiconair/properties|v1.8.6|间接依赖|go|
|github.com/valyala/fastjson|v1.6.3|间接依赖|go|
|github.com/google/go-intervals|v0.0.2|间接依赖|go|
|github.com/onsi/ginkgo|v1.16.5|直接依赖|go|
|sigs.k8s.io/kind|v0.14.0|直接依赖|go|
|github.com/Masterminds/goutils|v1.1.1|间接依赖|go|
|github.com/moby/spdystream|v0.2.0|间接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.3|间接依赖|go|
|k8s.io/kubectl|v0.25.4|直接依赖|go|
|golang.org/x/xerrors|v0.0.0-20220609144429-65e65417b02f|间接依赖|go|
|github.com/stefanberger/go-pkcs11uri|v0.0.0-20201008174630-78d3cae3a980|间接依赖|go|
|github.com/ulikunitz/xz|v0.5.10|间接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0|间接依赖|go|
|github.com/go-openapi/jsonreference|v0.19.5|间接依赖|go|
|github.com/imdario/mergo|v0.3.13|直接依赖|go|
|github.com/rivo/uniseg|v0.2.0|间接依赖|go|
|github.com/vbauerster/mpb/v7|v7.5.3|间接依赖|go|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|github.com/gobwas/glob|v0.2.3|间接依赖|go|
|k8s.io/api|v0.25.4|直接依赖|go|
|github.com/spf13/cobra|v1.5.0|直接依赖|go|
|github.com/spf13/afero|v1.8.2|间接依赖|go|
|github.com/BurntSushi/toml|v1.2.0|间接依赖|go|
|github.com/subosito/gotenv|v1.3.0|间接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|间接依赖|go|
|github.com/mailru/easyjson|v0.7.6|间接依赖|go|
|github.com/tchap/go-patricia|v2.3.0+incompatible|间接依赖|go|
|sigs.k8s.io/json|v0.0.0-20220713155537-f223a00ba0e2|间接依赖|go|
|github.com/mattn/go-shellwords|v1.0.12|间接依赖|go|
|github.com/monochromegane/go-gitignore|v0.0.0-20200626010858-205db1a8cc00|间接依赖|go|
|github.com/aws/aws-sdk-go|v1.44.102|间接依赖|go|
|github.com/containerd/cgroups|v1.0.4|间接依赖|go|
|github.com/gosuri/uitable|v0.0.4|间接依赖|go|
|github.com/blang/semver/v4|v4.0.0|间接依赖|go|
|github.com/sylabs/sif/v2|v2.8.0|间接依赖|go|
|github.com/Azure/go-autorest|v14.2.0+incompatible|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.0|直接依赖|go|
|github.com/jonboulle/clockwork|v0.2.2|间接依赖|go|
|github.com/deckarep/golang-set|v1.8.0|直接依赖|go|
|github.com/moby/sys/mountinfo|v0.6.2|间接依赖|go|
|k8s.io/utils|v0.0.0-20220728103510-ee6ede2d64ed|直接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/miekg/pkcs11|v1.1.1|间接依赖|go|
|github.com/opencontainers/runtime-spec|v1.0.3-0.20210326190908-1c3f411f0417|间接依赖|go|
|github.com/docker/go-units|v0.5.0|间接依赖|go|
|github.com/pelletier/go-toml/v2|v2.0.1|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|cloud.google.com/go|v0.104.0|间接依赖|go|
|github.com/onsi/gomega|v1.20.1|直接依赖|go|
|cloud.google.com/go/iam|v0.5.0|间接依赖|go|
|github.com/containers/storage|v1.43.0|间接依赖|go|
|github.com/huandu/xstrings|v1.3.2|间接依赖|go|
|github.com/prometheus/procfs|v0.7.3|间接依赖|go|
|github.com/lann/ps|v0.0.0-20150810152359-62de8c46ede0|间接依赖|go|
|github.com/docker/docker-credential-helpers|v0.7.0|间接依赖|go|
|github.com/gorilla/mux|v1.8.0|间接依赖|go|
|github.com/mistifyio/go-zfs/v3|v3.0.0|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/prometheus/common|v0.37.0|间接依赖|go|
|github.com/nxadm/tail|v1.4.8|间接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|oras.land/oras-go|v1.2.0|间接依赖|go|
|sigs.k8s.io/kustomize/api|v0.12.1|间接依赖|go|
|github.com/Azure/go-autorest/autorest/date|v0.3.0|间接依赖|go|
|github.com/coredns/corefile-migration|v1.0.17|间接依赖|go|
|github.com/google/shlex|v0.0.0-20191202100458-e7afc7fbc510|间接依赖|go|
|k8s.io/apiextensions-apiserver|v0.25.4|直接依赖|go|
|github.com/Azure/go-autorest/tracing|v0.6.0|间接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.5|间接依赖|go|
|github.com/hashicorp/go-cleanhttp|v0.5.2|间接依赖|go|
|github.com/moby/locker|v1.0.1|间接依赖|go|
|github.com/MakeNowJust/heredoc|v1.0.0|间接依赖|go|
|github.com/PuerkitoBio/urlesc|v0.0.0-20170810143723-de5bf2ad4578|间接依赖|go|
|golang.org/x/time|v0.0.0-20220722155302-e5dcc9cfc0b9|间接依赖|go|
|github.com/hashicorp/go-version|v1.6.0|间接依赖|go|
|github.com/lann/builder|v0.0.0-20180802200727-47ae307949d0|间接依赖|go|
|google.golang.org/api|v0.97.0|间接依赖|go|
|github.com/asaskevich/govalidator|v0.0.0-20200428143746-21a406dcc535|间接依赖|go|
|google.golang.org/grpc|v1.49.0|间接依赖|go|
|github.com/google/go-querystring|v1.1.0|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|直接依赖|go|
|golang.org/x/oauth2|v0.0.0-20220909003341-f21342109be1|间接依赖|go|
|github.com/go-logr/logr|v1.2.3|直接依赖|go|
|github.com/spf13/jwalterweatherman|v1.1.0|间接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|github.com/evanphx/json-patch|v5.6.0+incompatible|直接依赖|go|
|github.com/emicklei/go-restful/v3|v3.8.0|间接依赖|go|
|github.com/vbatts/tar-split|v0.11.2|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|github.com/google/btree|v1.0.1|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.5.4|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|github.com/docker/docker|v20.10.18+incompatible|间接依赖|go|
|github.com/docker/cli|v20.10.17+incompatible|间接依赖|go|
|golang.org/x/net|v0.1.0|间接依赖|go|
|github.com/hashicorp/errwrap|v1.1.0|间接依赖|go|
|github.com/antlr/antlr4/runtime/Go/antlr|v0.0.0-20220418222510-f25a4f6275ed|间接依赖|go|
|github.com/google/gofuzz|v1.2.0|间接依赖|go|
|github.com/proglottis/gpgme|v0.1.3|间接依赖|go|
|github.com/xeipuuv/gojsonreference|v0.0.0-20180127040603-bd5ef7bd5415|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20220803162953-67bda5d908f1|间接依赖|go|
|sigs.k8s.io/cluster-api|v1.2.6|直接依赖|go|
|github.com/googleapis/gax-go/v2|v2.5.1|间接依赖|go|
|github.com/mattn/go-runewidth|v0.0.13|间接依赖|go|
|github.com/rifflock/lfshook|v0.0.0-20180920164130-b9218ef580f5|直接依赖|go|
|github.com/kr/fs|v0.1.0|间接依赖|go|
|github.com/shopspring/decimal|v1.2.0|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20220926220553-6981cbe3cfce|间接依赖|go|
|github.com/drone/envsubst/v2|v2.0.0-20210730161058-179042472c46|间接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|k8s.io/cli-runtime|v0.25.4|直接依赖|go|
|github.com/ghodss/yaml|v1.0.0|间接依赖|go|
|github.com/jmoiron/sqlx|v1.3.5|间接依赖|go|
|golang.org/x/text|v0.4.0|间接依赖|go|
|github.com/spf13/cast|v1.5.0|间接依赖|go|
|github.com/golang-jwt/jwt/v4|v4.4.2|间接依赖|go|
|github.com/cyphar/filepath-securejoin|v0.2.3|间接依赖|go|
|github.com/opencontainers/selinux|v1.10.2|间接依赖|go|
|github.com/opencontainers/runc|v1.1.4|间接依赖|go|
|github.com/fatih/color|v1.13.0|间接依赖|go|
|github.com/alessio/shellescape|v1.4.1|间接依赖|go|
|sigs.k8s.io/kustomize/kyaml|v0.13.9|间接依赖|go|
|github.com/exponent-io/jsonpath|v0.0.0-20151013193312-d6023ce2651d|间接依赖|go|
|golang.org/x/term|v0.1.0|间接依赖|go|
|github.com/hashicorp/go-safetemp|v1.0.0|间接依赖|go|
|github.com/pkg/sftp|v1.13.5|直接依赖|go|
|cloud.google.com/go/compute|v1.7.0|间接依赖|go|
|github.com/mitchellh/copystructure|v1.2.0|间接依赖|go|
|github.com/rubenv/sql-migrate|v1.1.1|间接依赖|go|
|github.com/docker/distribution|v2.8.1+incompatible|间接依赖|go|
|github.com/russross/blackfriday|v1.6.0|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.12|间接依赖|go|
|github.com/containers/ocicrypt|v1.1.5|间接依赖|go|
|github.com/peterbourgon/diskv|v2.0.1+incompatible|间接依赖|go|
|github.com/docker/go-connections|v0.4.1-0.20190612165340-fd1b1942c4d5|间接依赖|go|
|github.com/lib/pq|v1.10.6|间接依赖|go|
|github.com/fvbommel/sortorder|v1.0.1|间接依赖|go|
|github.com/xeipuuv/gojsonpointer|v0.0.0-20190905194746-02993c407bfb|间接依赖|go|
|github.com/hashicorp/go-multierror|v1.1.1|间接依赖|go|
|github.com/google/uuid|v1.3.0|间接依赖|go|
|github.com/moby/term|v0.0.0-20210619224110-3f7ff695adc6|间接依赖|go|
|github.com/smartystreets/goconvey|v1.7.2|间接依赖|go|
|github.com/syndtr/gocapability|v0.0.0-20200815063812-42c35b437635|间接依赖|go|
|github.com/pelletier/go-toml|v1.9.5|间接依赖|go|
|go.mozilla.org/pkcs7|v0.0.0-20210826202110-33d05740a352|间接依赖|go|
|github.com/VividCortex/ewma|v1.2.0|间接依赖|go|
|github.com/lithammer/dedent|v1.1.0|直接依赖|go|
|k8s.io/apiserver|v0.25.4|直接依赖|go|
|sigs.k8s.io/cluster-api/test|v1.2.6|直接依赖|go|
|k8s.io/component-base|v0.25.4|直接依赖|go|
|github.com/fatih/camelcase|v1.0.0|间接依赖|go|
|github.com/mitchellh/go-wordwrap|v1.0.0|间接依赖|go|
|golang.org/x/crypto|v0.0.0-20220919173607-35f4265a4bc0|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)