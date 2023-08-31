# kubernetes-sigs/aws-load-balancer-controller安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1697311734670123008.svg)](https://www.murphysec.com/console/report/1697311734510739456/1697311734670123008)

仓库描述：A Kubernetes controller for Elastic Load Balancers

仓库地址：[https://github.com/kubernetes-sigs/aws-load-balancer-controller](https://github.com/kubernetes-sigs/aws-load-balancer-controller)

| star：3512 | watch：112 | fork：1293 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-30 08:17:56 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-01 02:14:04 | 组件总数：157 | 漏洞总数：6 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|containerd 安全漏洞|不加限制或调节的资源分配|[MPS-2023-3769](https://www.oscs1024.com/hd/MPS-2023-3769)|CVE-2023-25153|中危|
|Helm 信息泄露漏洞|未授权敏感信息泄露|[MPS-2023-3781](https://www.oscs1024.com/hd/MPS-2023-3781)|CVE-2023-25165|中危|
|containerd容器内文件权限机制实现不当|将用户置入不正确的用户组|[MPS-2023-3789](https://www.oscs1024.com/hd/MPS-2023-3789)|CVE-2023-25173|中危|
|Moby 安全漏洞||[MPS-2023-8823](https://www.oscs1024.com/hd/MPS-2023-8823)|CVE-2023-28840|高危|
|Moby 安全漏洞||[MPS-2023-8824](https://www.oscs1024.com/hd/MPS-2023-8824)|CVE-2023-28841|中危|
|Moby 安全漏洞||[MPS-2023-8826](https://www.oscs1024.com/hd/MPS-2023-8826)|CVE-2023-28842|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/docker/docker|v20.10.21+incompatible|23.0.3|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|helm.sh/helm/v3|v3.11.0|3.11.1|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|github.com/containerd/containerd|v1.6.15|1.6.18|间接依赖|可选修复|C:0|H:0|M:2|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|33|Low|
|Apache-2.0|64|Low|
|MIT|62|Low|
|BSD-2-Clause|3|Low|
|CC-BY-SA-4.0|2|Medium|
|ISC|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|golang.org/x/term|v0.8.0|间接依赖|go|
|github.com/imdario/mergo|v0.3.12|间接依赖|go|
|github.com/google/shlex|v0.0.0-20191202100458-e7afc7fbc510|间接依赖|go|
|github.com/andybalholm/brotli|v1.0.4|间接依赖|go|
|golang.org/x/net|v0.10.0|间接依赖|go|
|github.com/asaskevich/govalidator|v0.0.0-20200428143746-21a406dcc535|间接依赖|go|
|github.com/exponent-io/jsonpath|v0.0.0-20151013193312-d6023ce2651d|间接依赖|go|
|oras.land/oras-go|v1.2.2|间接依赖|go|
|github.com/mitchellh/copystructure|v1.2.0|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20221012153701-172d655c2280|间接依赖|go|
|golang.org/x/tools|v0.9.3|间接依赖|go|
|github.com/mitchellh/reflectwalk|v1.0.2|间接依赖|go|
|github.com/docker/docker|v20.10.21+incompatible|间接依赖|go|
|github.com/containerd/containerd|v1.6.15|间接依赖|go|
|github.com/monochromegane/go-gitignore|v0.0.0-20200626010858-205db1a8cc00|间接依赖|go|
|github.com/docker/go-connections|v0.4.0|间接依赖|go|
|github.com/go-task/slim-sprig|v0.0.0-20230315185526-52ccab3ef572|间接依赖|go|
|github.com/russross/blackfriday/v2|v2.1.0|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|github.com/MakeNowJust/heredoc|v1.0.0|间接依赖|go|
|github.com/xlab/treeprint|v1.1.0|间接依赖|go|
|github.com/BurntSushi/toml|v1.2.1|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|k8s.io/component-base|v0.26.1|间接依赖|go|
|github.com/mailru/easyjson|v0.7.6|间接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|go.uber.org/multierr|v1.6.0|间接依赖|go|
|github.com/ajg/form|v1.5.1|间接依赖|go|
|github.com/xeipuuv/gojsonreference|v0.0.0-20180127040603-bd5ef7bd5415|间接依赖|go|
|github.com/chai2010/gettext-go|v1.0.2|间接依赖|go|
|k8s.io/client-go|v0.26.5|直接依赖|go|
|github.com/google/pprof|v0.0.0-20210407192527-94a9f03dee38|间接依赖|go|
|github.com/valyala/fasthttp|v1.34.0|间接依赖|go|
|github.com/imkira/go-interpol|v1.1.0|间接依赖|go|
|github.com/gosuri/uitable|v0.0.4|间接依赖|go|
|k8s.io/api|v0.26.5|直接依赖|go|
|github.com/mattn/go-colorable|v0.1.2|间接依赖|go|
|github.com/spf13/cast|v1.3.1|间接依赖|go|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|github.com/gorilla/mux|v1.8.0|间接依赖|go|
|github.com/go-logr/logr|v1.2.4|直接依赖|go|
|github.com/Masterminds/squirrel|v1.5.3|间接依赖|go|
|github.com/morikuni/aec|v1.0.0|间接依赖|go|
|github.com/docker/cli|v20.10.21+incompatible|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/evanphx/json-patch|v5.6.0+incompatible|直接依赖|go|
|github.com/shopspring/decimal|v1.2.0|间接依赖|go|
|k8s.io/apimachinery|v0.26.5|直接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|go.uber.org/zap|v1.24.0|直接依赖|go|
|github.com/huandu/xstrings|v1.3.3|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|github.com/gorilla/websocket|v1.4.2|间接依赖|go|
|sigs.k8s.io/controller-runtime|v0.14.6|直接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|github.com/docker/distribution|v2.8.1+incompatible|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|golang.org/x/sys|v0.9.0|间接依赖|go|
|github.com/yudai/gojsondiff|v1.0.0|间接依赖|go|
|k8s.io/kubectl|v0.26.0|间接依赖|go|
|github.com/go-openapi/swag|v0.19.14|间接依赖|go|
|github.com/cyphar/filepath-securejoin|v0.2.3|间接依赖|go|
|helm.sh/helm/v3|v3.11.0|直接依赖|go|
|github.com/Azure/go-ansiterm|v0.0.0-20210617225240-d185dfc1b5a1|间接依赖|go|
|github.com/google/uuid|v1.2.0|间接依赖|go|
|k8s.io/apiserver|v0.26.1|间接依赖|go|
|github.com/sirupsen/logrus|v1.9.0|间接依赖|go|
|github.com/liggitt/tabwriter|v0.0.0-20181228230101-89fcab3d43de|间接依赖|go|
|github.com/onsi/gomega|v1.27.8|直接依赖|go|
|golang.org/x/sync|v0.2.0|间接依赖|go|
|google.golang.org/grpc|v1.49.0|间接依赖|go|
|sigs.k8s.io/kustomize/api|v0.12.1|间接依赖|go|
|github.com/evanphx/json-patch/v5|v5.6.0|间接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|github.com/docker/docker-credential-helpers|v0.7.0|间接依赖|go|
|github.com/lann/ps|v0.0.0-20150810152359-62de8c46ede0|间接依赖|go|
|k8s.io/cli-runtime|v0.26.3|直接依赖|go|
|github.com/xeipuuv/gojsonpointer|v0.0.0-20190905194746-02993c407bfb|间接依赖|go|
|github.com/sergi/go-diff|v1.1.0|间接依赖|go|
|golang.org/x/crypto|v0.5.0|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/docker/go-metrics|v0.0.1|间接依赖|go|
|github.com/lib/pq|v1.10.7|间接依赖|go|
|k8s.io/klog/v2|v2.80.1|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/fatih/structs|v1.1.0|间接依赖|go|
|github.com/sanity-io/litter|v1.5.5|间接依赖|go|
|gomodules.xyz/jsonpatch/v2|v2.2.0|直接依赖|go|
|google.golang.org/protobuf|v1.31.0|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20220502173005-c8bf987b8c21|间接依赖|go|
|github.com/prometheus/common|v0.37.0|间接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.5|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|间接依赖|go|
|github.com/google/gnostic|v0.5.7-v3refs|间接依赖|go|
|golang.org/x/text|v0.9.0|间接依赖|go|
|golang.org/x/oauth2|v0.0.0-20220223155221-ee480838109b|间接依赖|go|
|github.com/valyala/bytebufferpool|v1.0.0|间接依赖|go|
|github.com/mitchellh/go-wordwrap|v1.0.1|间接依赖|go|
|github.com/stretchr/testify|v1.8.1|直接依赖|go|
|github.com/aws/aws-sdk-go|v1.44.294|直接依赖|go|
|sigs.k8s.io/json|v0.0.0-20220713155537-f223a00ba0e2|间接依赖|go|
|github.com/onsi/ginkgo/v2|v2.11.0|直接依赖|go|
|k8s.io/apiextensions-apiserver|v0.26.1|间接依赖|go|
|moul.io/http2curl/v2|v2.3.0|间接依赖|go|
|github.com/fatih/color|v1.7.0|间接依赖|go|
|github.com/klauspost/compress|v1.15.0|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/gobwas/glob|v0.2.3|间接依赖|go|
|github.com/Masterminds/goutils|v1.1.1|间接依赖|go|
|github.com/go-logr/zapr|v1.2.3|间接依赖|go|
|github.com/moby/term|v0.0.0-20221205130635-1aeaba878587|间接依赖|go|
|github.com/google/go-querystring|v1.1.0|间接依赖|go|
|github.com/moby/locker|v1.0.1|间接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|间接依赖|go|
|go.uber.org/atomic|v1.7.0|间接依赖|go|
|github.com/mattn/go-runewidth|v0.0.9|间接依赖|go|
|github.com/prometheus/client_golang|v1.14.0|直接依赖|go|
|github.com/moby/spdystream|v0.2.0|间接依赖|go|
|github.com/Masterminds/sprig/v3|v3.2.3|间接依赖|go|
|github.com/google/gofuzz|v1.2.0|间接依赖|go|
|github.com/docker/go-units|v0.4.0|间接依赖|go|
|sigs.k8s.io/kustomize/kyaml|v0.13.9|间接依赖|go|
|github.com/emicklei/go-restful/v3|v3.10.0|间接依赖|go|
|github.com/yalp/jsonpath|v0.0.0-20180802001716-5cc68e5049a0|间接依赖|go|
|github.com/Masterminds/semver/v3|v3.2.0|间接依赖|go|
|github.com/go-errors/errors|v1.0.1|间接依赖|go|
|github.com/gavv/httpexpect/v2|v2.9.0|直接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.3|间接依赖|go|
|github.com/golang/mock|v1.6.0|直接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.0|间接依赖|go|
|github.com/gregjones/httpcache|v0.0.0-20180305231024-9cad4c3443a7|间接依赖|go|
|github.com/yudai/golcs|v0.0.0-20170316035057-ecda9a501e82|间接依赖|go|
|go.starlark.net|v0.0.0-20200306205701-8dd3e2ee1dd5|间接依赖|go|
|github.com/spf13/cobra|v1.6.1|间接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.0.1|间接依赖|go|
|github.com/go-gorp/gorp/v3|v3.0.2|间接依赖|go|
|github.com/xeipuuv/gojsonschema|v1.2.0|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.8|间接依赖|go|
|github.com/peterbourgon/diskv|v2.0.1+incompatible|间接依赖|go|
|sigs.k8s.io/yaml|v1.3.0|直接依赖|go|
|github.com/prometheus/client_model|v0.3.0|间接依赖|go|
|golang.org/x/time|v0.3.0|直接依赖|go|
|k8s.io/utils|v0.0.0-20221128185143-99ec85e7a448|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.1.2|间接依赖|go|
|github.com/opencontainers/image-spec|v1.1.0-rc2|间接依赖|go|
|github.com/rubenv/sql-migrate|v1.2.0|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/jmoiron/sqlx|v1.3.5|间接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/lann/builder|v0.0.0-20180802200727-47ae307949d0|间接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|github.com/google/btree|v1.0.1|间接依赖|go|
|github.com/prometheus/procfs|v0.8.0|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)