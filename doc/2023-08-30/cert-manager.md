# cert-manager/cert-manager安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696586671402606592.svg)](https://www.murphysec.com/console/report/1696586671352274944/1696586671402606592)

仓库描述：Automatically provision and manage TLS certificates in Kubernetes

仓库地址：[https://github.com/cert-manager/cert-manager](https://github.com/cert-manager/cert-manager)

| star：10654 | watch：146 | fork：1922 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-29 16:48:02 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-30 02:12:47 | 组件总数：251 | 漏洞总数：3 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Moby 安全漏洞||[MPS-2023-8823](https://www.oscs1024.com/hd/MPS-2023-8823)|CVE-2023-28840|高危|
|Moby 安全漏洞||[MPS-2023-8824](https://www.oscs1024.com/hd/MPS-2023-8824)|CVE-2023-28841|中危|
|Moby 安全漏洞|对异常条件的处理不恰当|[MPS-2023-8826](https://www.oscs1024.com/hd/MPS-2023-8826)|CVE-2023-28842|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/docker/docker|v23.0.1+incompatible|23.0.3|间接依赖|建议修复|C:0|H:1|M:2|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|114|Low|
|MIT|80|Low|
|BSD-3-Clause|46|Low|
|MPL-2.0|11|Low|
|BSD-2-Clause|2|Low|
|CC-BY-SA-4.0|2|Medium|
|ISC|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|go.opentelemetry.io/otel/metric|v0.36.0|间接依赖|go|
|github.com/fatih/color|v1.15.0|间接依赖|go|
|k8s.io/cli-runtime|v0.28.1|直接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.3.0|直接依赖|go|
|go.opentelemetry.io/otel|v1.15.0|间接依赖|go|
|github.com/prometheus/procfs|v0.10.1|间接依赖|go|
|github.com/google/uuid|v1.3.0|间接依赖|go|
|github.com/cert-manager/cert-manager|v1.13.0-alpha.0.0.20230825134310-63cf4e0b1c56|直接依赖|go|
|go.opentelemetry.io/proto/otlp|v0.19.0|间接依赖|go|
|github.com/imdario/mergo|v0.3.13|间接依赖|go|
|github.com/exponent-io/jsonpath|v0.0.0-20151013193312-d6023ce2651d|间接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|间接依赖|go|
|github.com/Azure/azure-sdk-for-go|v68.0.0+incompatible|直接依赖|go|
|github.com/asaskevich/govalidator|v0.0.0-20200428143746-21a406dcc535|间接依赖|go|
|github.com/digitalocean/godo|v1.102.1|直接依赖|go|
|github.com/klauspost/compress|v1.16.0|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/gobwas/glob|v0.2.3|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|github.com/rivo/uniseg|v0.2.0|间接依赖|go|
|golang.org/x/time|v0.3.0|间接依赖|go|
|golang.org/x/crypto|v0.12.0|直接依赖|go|
|github.com/Azure/go-autorest/autorest/adal|v0.9.23|直接依赖|go|
|github.com/emicklei/go-restful/v3|v3.10.1|间接依赖|go|
|sigs.k8s.io/json|v0.0.0-20221116044647-bc3834ca7abd|间接依赖|go|
|k8s.io/apiextensions-apiserver|v0.28.1|直接依赖|go|
|golang.org/x/exp|v0.0.0-20230817173708-d852ddb80c63|直接依赖|go|
|github.com/lann/ps|v0.0.0-20150810152359-62de8c46ede0|间接依赖|go|
|github.com/prometheus/common|v0.44.0|间接依赖|go|
|cloud.google.com/go/compute|v1.23.0|间接依赖|go|
|github.com/coreos/go-semver|v0.3.1|间接依赖|go|
|helm.sh/helm/v3|v3.12.3|直接依赖|go|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.1-0.20181226105442-5d4384ee4fb2|间接依赖|go|
|github.com/go-errors/errors|v1.4.2|间接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|github.com/Azure/go-autorest/autorest/to|v0.4.0|直接依赖|go|
|github.com/Masterminds/squirrel|v1.5.4|间接依赖|go|
|golang.org/x/mod|v0.12.0|间接依赖|go|
|github.com/cloudflare/cloudflare-go|v0.58.1|直接依赖|go|
|gopkg.in/ini.v1|v1.62.0|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|间接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.2|间接依赖|go|
|golang.org/x/sys|v0.11.0|间接依赖|go|
|github.com/go-jose/go-jose/v3|v3.0.0|间接依赖|go|
|k8s.io/kms|v0.28.1|间接依赖|go|
|sigs.k8s.io/kustomize/kyaml|v0.14.3-0.20230601165947-6ce0bf390ce3|间接依赖|go|
|github.com/sirupsen/logrus|v1.9.0|间接依赖|go|
|github.com/mitchellh/go-wordwrap|v1.0.1|间接依赖|go|
|github.com/lann/builder|v0.0.0-20180802200727-47ae307949d0|间接依赖|go|
|github.com/Azure/go-ntlmssp|v0.0.0-20221128193559-754e69321358|间接依赖|go|
|github.com/mitchellh/copystructure|v1.2.0|间接依赖|go|
|github.com/jmoiron/sqlx|v1.3.5|间接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway/v2|v2.7.0|间接依赖|go|
|k8s.io/utils|v0.0.0-20230726121419-3b25d923346b|直接依赖|go|
|github.com/miekg/dns|v1.1.55|直接依赖|go|
|github.com/hashicorp/go-secure-stdlib/parseutil|v0.1.7|间接依赖|go|
|github.com/google/btree|v1.0.1|间接依赖|go|
|github.com/hashicorp/hcl|v1.0.1-vault-5|间接依赖|go|
|github.com/Azure/go-autorest|v14.2.0+incompatible|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20230816210353-14e408962443|直接依赖|go|
|github.com/russross/blackfriday/v2|v2.1.0|间接依赖|go|
|github.com/AdaLogics/go-fuzz-headers|v0.0.0-20230106234847-43070de90fa1|间接依赖|go|
|github.com/stretchr/objx|v0.5.0|间接依赖|go|
|github.com/golang-jwt/jwt/v4|v4.5.0|间接依赖|go|
|github.com/moby/spdystream|v0.2.0|间接依赖|go|
|github.com/docker/go-metrics|v0.0.1|间接依赖|go|
|github.com/hashicorp/vault/api|v1.9.2|直接依赖|go|
|sigs.k8s.io/gateway-api|v0.7.1|直接依赖|go|
|github.com/imdario/mergo|v0.3.12|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/internal/retry|v1.15.0|间接依赖|go|
|github.com/hashicorp/go-sockaddr|v1.0.2|间接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|github.com/gorilla/mux|v1.8.0|间接依赖|go|
|gopkg.in/natefinch/lumberjack.v2|v2.2.1|间接依赖|go|
|github.com/go-logr/zapr|v1.2.4|间接依赖|go|
|golang.org/x/net|v0.14.0|间接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|gomodules.xyz/jsonpatch/v2|v2.4.0|直接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|github.com/antlr/antlr4/runtime/Go/antlr/v4|v4.0.0-20230305170008-8188dc5388df|间接依赖|go|
|github.com/lib/pq|v1.10.9|间接依赖|go|
|github.com/shopspring/decimal|v1.3.1|间接依赖|go|
|github.com/go-test/deep|v1.1.0|间接依赖|go|
|github.com/google/shlex|v0.0.0-20191202100458-e7afc7fbc510|间接依赖|go|
|k8s.io/apimachinery|v0.28.1|直接依赖|go|
|github.com/docker/docker-credential-helpers|v0.7.0|间接依赖|go|
|github.com/Azure/go-autorest/autorest/date|v0.3.0|间接依赖|go|
|github.com/emicklei/go-restful/v3|v3.9.0|间接依赖|go|
|github.com/hashicorp/go-hclog|v1.4.0|间接依赖|go|
|go.uber.org/zap|v1.25.0|间接依赖|go|
|github.com/google/pprof|v0.0.0-20210720184732-4bb14d4b1be1|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|k8s.io/client-go|v0.28.1|直接依赖|go|
|github.com/mattn/go-runewidth|v0.0.13|间接依赖|go|
|sigs.k8s.io/yaml|v1.3.0|直接依赖|go|
|github.com/Venafi/vcert/v4|v4.24.1-0.20230703183014-69f417ae176d|直接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|google.golang.org/protobuf|v1.31.0|间接依赖|go|
|k8s.io/kube-aggregator|v0.28.1|直接依赖|go|
|github.com/Azure/go-ansiterm|v0.0.0-20210617225240-d185dfc1b5a1|间接依赖|go|
|github.com/stretchr/testify|v1.8.4|直接依赖|go|
|go.opentelemetry.io/otel/sdk|v1.15.0|间接依赖|go|
|github.com/BurntSushi/toml|v1.2.1|间接依赖|go|
|k8s.io/klog/v2|v2.100.1|直接依赖|go|
|google.golang.org/genproto/googleapis/api|v0.0.0-20230803162519-f966b187b2e5|间接依赖|go|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|google.golang.org/api|v0.138.0|直接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/rubenv/sql-migrate|v1.3.1|间接依赖|go|
|github.com/hashicorp/errwrap|v1.1.0|间接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.0|间接依赖|go|
|github.com/cenkalti/backoff/v4|v4.2.1|间接依赖|go|
|sigs.k8s.io/kustomize/api|v0.13.5-0.20230601165947-6ce0bf390ce3|间接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/net/http/otelhttp|v0.39.0|间接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|github.com/gosuri/uitable|v0.0.4|间接依赖|go|
|github.com/googleapis/enterprise-certificate-proxy|v0.2.5|间接依赖|go|
|golang.org/x/text|v0.12.0|间接依赖|go|
|github.com/spf13/cobra|v1.7.0|直接依赖|go|
|github.com/kr/pretty|v0.3.1|直接依赖|go|
|github.com/stoewer/go-strcase|v1.2.0|间接依赖|go|
|github.com/spf13/cast|v1.5.0|间接依赖|go|
|github.com/hashicorp/go-multierror|v1.1.1|间接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway/v2|v2.11.3|间接依赖|go|
|github.com/gregjones/httpcache|v0.0.0-20180305231024-9cad4c3443a7|间接依赖|go|
|github.com/moby/locker|v1.0.1|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230803162519-f966b187b2e5|间接依赖|go|
|go.opencensus.io|v0.24.0|间接依赖|go|
|github.com/Masterminds/semver/v3|v3.2.1|间接依赖|go|
|k8s.io/component-base|v0.28.1|直接依赖|go|
|github.com/opencontainers/image-spec|v1.1.0-rc2.0.20221005185240-3a7f492d3f1b|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace|v1.15.0|间接依赖|go|
|github.com/hashicorp/go-retryablehttp|v0.7.4|间接依赖|go|
|go.etcd.io/etcd/api/v3|v3.5.9|间接依赖|go|
|github.com/onsi/gomega|v1.27.10|直接依赖|go|
|k8s.io/gengo|v0.0.0-20220902162205-c0856e24416d|间接依赖|go|
|github.com/grpc-ecosystem/go-grpc-prometheus|v1.2.0|间接依赖|go|
|github.com/docker/docker|v23.0.1+incompatible|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.17|间接依赖|go|
|oras.land/oras-go|v1.2.3|间接依赖|go|
|github.com/docker/go-connections|v0.4.0|间接依赖|go|
|github.com/sergi/go-diff|v1.3.1|直接依赖|go|
|github.com/coreos/go-systemd/v22|v22.5.0|间接依赖|go|
|github.com/mitchellh/reflectwalk|v1.0.2|间接依赖|go|
|github.com/chai2010/gettext-go|v1.0.2|间接依赖|go|
|k8s.io/code-generator|v0.28.1|直接依赖|go|
|github.com/docker/cli|v23.0.1+incompatible|间接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|github.com/akamai/AkamaiOPEN-edgegrid-golang|v1.2.2|直接依赖|go|
|github.com/evanphx/json-patch|v5.6.0+incompatible|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace/otlptracegrpc|v1.15.0|间接依赖|go|
|github.com/pavlo-v-chernykh/keystore-go/v4|v4.4.1|直接依赖|go|
|golang.org/x/tools|v0.12.1-0.20230815132531-74c255bcf846|间接依赖|go|
|github.com/xlab/treeprint|v1.2.0|间接依赖|go|
|github.com/morikuni/aec|v1.0.0|间接依赖|go|
|github.com/hashicorp/go-rootcerts|v1.0.2|间接依赖|go|
|github.com/hashicorp/vault/sdk|v0.9.2|直接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/hashicorp/go-cleanhttp|v0.5.2|间接依赖|go|
|github.com/onsi/ginkgo/v2|v2.12.0|直接依赖|go|
|github.com/Azure/go-autorest/tracing|v0.6.0|间接依赖|go|
|github.com/google/s2a-go|v0.1.5|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|github.com/blang/semver/v4|v4.0.0|间接依赖|go|
|github.com/go-openapi/swag|v0.22.3|间接依赖|go|
|sigs.k8s.io/controller-tools|v0.13.0|直接依赖|go|
|github.com/NYTimes/gziphandler|v1.1.1|间接依赖|go|
|github.com/google/gnostic-models|v0.6.8|直接依赖|go|
|google.golang.org/grpc|v1.57.0|间接依赖|go|
|github.com/peterbourgon/diskv|v2.0.1+incompatible|间接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230807174057-1744710a1577|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|sigs.k8s.io/apiserver-network-proxy/konnectivity-client|v0.1.2|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|github.com/huandu/xstrings|v1.4.0|间接依赖|go|
|k8s.io/kubectl|v0.28.1|直接依赖|go|
|github.com/moby/term|v0.0.0-20221205130635-1aeaba878587|间接依赖|go|
|github.com/cenkalti/backoff/v3|v3.2.2|间接依赖|go|
|github.com/evanphx/json-patch/v5|v5.6.0|间接依赖|go|
|github.com/xeipuuv/gojsonreference|v0.0.0-20180127040603-bd5ef7bd5415|间接依赖|go|
|github.com/rogpeppe/go-internal|v1.11.0|间接依赖|go|
|github.com/docker/distribution|v2.8.2+incompatible|间接依赖|go|
|github.com/Azure/go-autorest/autorest|v0.11.29|直接依赖|go|
|github.com/asaskevich/govalidator|v0.0.0-20190424111038-f61b66f89f4a|间接依赖|go|
|github.com/ryanuber/go-glob|v1.0.0|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/go-logr/logr|v1.2.4|直接依赖|go|
|go.etcd.io/etcd/client/v3|v3.5.9|间接依赖|go|
|github.com/cert-manager/cert-manager|v0.0.0-00010101000000-000000000000|直接依赖|go|
|github.com/prometheus/client_model|v0.4.0|间接依赖|go|
|github.com/prometheus/client_golang|v1.16.0|直接依赖|go|
|github.com/cyphar/filepath-securejoin|v0.2.3|间接依赖|go|
|github.com/fatih/camelcase|v1.0.0|间接依赖|go|
|github.com/googleapis/gax-go/v2|v2.12.0|间接依赖|go|
|github.com/segmentio/encoding|v0.3.6|直接依赖|go|
|golang.org/x/oauth2|v0.11.0|直接依赖|go|
|github.com/cert-manager/cert-manager/cmd/ctl|v0.0.0-00010101000000-000000000000|直接依赖|go|
|k8s.io/apiserver|v0.28.1|直接依赖|go|
|github.com/golang/snappy|v0.0.4|间接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/google.golang.org/grpc/otelgrpc|v0.40.0|间接依赖|go|
|github.com/monochromegane/go-gitignore|v0.0.0-20200626010858-205db1a8cc00|间接依赖|go|
|software.sslmate.com/src/go-pkcs12|v0.2.1|直接依赖|go|
|go.opentelemetry.io/otel/trace|v1.15.0|间接依赖|go|
|golang.org/x/sync|v0.3.0|直接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.6|间接依赖|go|
|github.com/docker/go-units|v0.5.0|间接依赖|go|
|github.com/patrickmn/go-cache|v2.1.0+incompatible|间接依赖|go|
|github.com/go-asn1-ber/asn1-ber|v1.5.4|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|github.com/MakeNowJust/heredoc|v1.0.0|间接依赖|go|
|github.com/felixge/httpsnoop|v1.0.3|间接依赖|go|
|golang.org/x/term|v0.11.0|间接依赖|go|
|github.com/go-ldap/ldap/v3|v3.4.5|直接依赖|go|
|github.com/liggitt/tabwriter|v0.0.0-20181228230101-89fcab3d43de|间接依赖|go|
|github.com/google/cel-go|v0.16.0|间接依赖|go|
|k8s.io/kube-aggregator|v0.28.0|间接依赖|go|
|github.com/segmentio/asm|v1.1.3|间接依赖|go|
|github.com/hashicorp/go-secure-stdlib/strutil|v0.1.2|间接依赖|go|
|github.com/munnerz/crd-schema-fuzz|v1.0.0|直接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.2-0.20180830191138-d8f796af33cc|间接依赖|go|
|go.etcd.io/etcd/client/pkg/v3|v3.5.9|间接依赖|go|
|github.com/aws/aws-sdk-go|v1.44.331|直接依赖|go|
|github.com/Azure/go-autorest/logger|v0.2.1|间接依赖|go|
|github.com/kr/text|v0.2.0|间接依赖|go|
|github.com/Azure/go-autorest/autorest/validation|v0.3.1|间接依赖|go|
|github.com/Masterminds/sprig/v3|v3.2.3|间接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/google.golang.org/grpc/otelgrpc|v0.35.0|间接依赖|go|
|github.com/youmark/pkcs8|v0.0.0-20201027041543-1326539a0a0a|间接依赖|go|
|github.com/pierrec/lz4|v2.6.1+incompatible|间接依赖|go|
|github.com/google/go-querystring|v1.1.0|间接依赖|go|
|github.com/go-gorp/gorp/v3|v3.1.0|间接依赖|go|
|github.com/Masterminds/goutils|v1.1.1|间接依赖|go|
|go.opentelemetry.io/otel/metric|v0.37.0|间接依赖|go|
|github.com/cpu/goacmedns|v0.1.1|直接依赖|go|
|github.com/go-task/slim-sprig|v0.0.0-20230315185526-52ccab3ef572|间接依赖|go|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|github.com/xeipuuv/gojsonpointer|v0.0.0-20190905194746-02993c407bfb|间接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0|间接依赖|go|
|cloud.google.com/go/compute/metadata|v0.2.3|间接依赖|go|
|go.starlark.net|v0.0.0-20230525235612-a134d8f9ddca|间接依赖|go|
|github.com/containerd/containerd|v1.7.1|间接依赖|go|
|sigs.k8s.io/controller-runtime|v0.16.0|直接依赖|go|
|github.com/google/go-cmp|v0.5.9|间接依赖|go|
|go.uber.org/multierr|v1.11.0|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/gobuffalo/flect|v1.0.2|间接依赖|go|
|github.com/xeipuuv/gojsonschema|v1.2.0|间接依赖|go|
|github.com/google/gofuzz|v1.2.0|直接依赖|go|
|k8s.io/api|v0.28.1|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)