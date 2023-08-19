# grafana/loki安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692963458760200192.svg)](https://www.murphysec.com/console/report/1692963458605010944/1692963458760200192)

仓库描述：Like Prometheus, but for logs.

仓库地址：[https://github.com/grafana/loki](https://github.com/grafana/loki)

| star：19823 | watch：356 | fork：2877 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-20 00:18:37 | 许可证：AGPL-3.0 |
| 最近检测时间：2023-08-20 02:19:48 | 组件总数：414 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Grafana 路径遍历漏洞|路径遍历|[MPS-2021-11505](https://www.oscs1024.com/hd/MPS-2021-11505)|CVE-2021-36156|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/grafana/loki|v1.6.2-0.20230403212622-90888a0cc737|2.3.0|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|github.com/grafana/loki|v1.6.2-0.20230216091802-4e4359e67c6c|2.3.0|直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|113|Low|
|MPL-2.0|13|Low|
|Apache-2.0|193|Low|
|BSD-3-Clause|85|Low|
|MIT-0|1|Low|
|ISC|3|Low|
|BSD-2-Clause|7|Low|
|CC-BY-SA-4.0|2|Medium|
|AGPL-3.0|3|High|
|Unlicense|1|Low|
|BSD-2-Clause-Views|1|Low|
|LGPL-3.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/fatih/color|v1.15.0|直接依赖|go|
|github.com/hashicorp/go-retryablehttp|v0.7.2|间接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230530153820-e85fd2cbaebc|间接依赖|go|
|github.com/spf13/afero|v1.9.5|直接依赖|go|
|sigs.k8s.io/controller-runtime|v0.14.5|直接依赖|go|
|go.uber.org/multierr|v1.8.0|间接依赖|go|
|github.com/hashicorp/go-sockaddr|v1.0.2|间接依赖|go|
|github.com/armon/go-metrics|v0.4.1|间接依赖|go|
|github.com/klauspost/compress|v1.16.7|直接依赖|go|
|github.com/xdg-go/pbkdf2|v1.0.0|间接依赖|go|
|github.com/hashicorp/go-hclog|v1.4.0|间接依赖|go|
|github.com/hailocab/go-hostpool|v0.0.0-20160125115350-e80d13ce29ed|间接依赖|go|
|github.com/docker/go-plugins-helpers|v0.0.0-20181025120712-1e6269c305b8|直接依赖|go|
|github.com/aliyun/aliyun-oss-go-sdk|v2.2.7+incompatible|直接依赖|go|
|github.com/census-instrumentation/opencensus-proto|v0.4.1|间接依赖|go|
|github.com/go-openapi/validate|v0.22.1|间接依赖|go|
|github.com/soheilhy/cmux|v0.1.5|间接依赖|go|
|github.com/minio/md5-simd|v1.1.2|间接依赖|go|
|github.com/axiomhq/hyperloglog|v0.0.0-20230201085229-3ddf4bad03dc|直接依赖|go|
|github.com/prometheus/common|v0.42.0|直接依赖|go|
|github.com/sercand/kuberesolver|v2.4.0+incompatible|间接依赖|go|
|go4.org/netipx|v0.0.0-20230125063823-8449b0a6169f|直接依赖|go|
|github.com/uber/jaeger-client-go|v2.30.0+incompatible|直接依赖|go|
|github.com/prometheus/alertmanager|v0.25.0|直接依赖|go|
|github.com/klauspost/pgzip|v1.2.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sso|v1.11.1|间接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.2|间接依赖|go|
|github.com/hashicorp/memberlist|v0.5.0|间接依赖|go|
|github.com/aws/aws-lambda-go|v1.26.0|直接依赖|go|
|go.uber.org/goleak|v1.2.0|间接依赖|go|
|github.com/go-playground/locales|v0.14.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/config|v1.15.1|直接依赖|go|
|github.com/Azure/go-autorest/autorest/azure/cli|v0.4.5|间接依赖|go|
|github.com/coreos/go-systemd/v22|v22.5.0|间接依赖|go|
|github.com/oschwald/maxminddb-golang|v1.11.0|间接依赖|go|
|k8s.io/apimachinery|v0.26.2|直接依赖|go|
|github.com/dgryski/go-rendezvous|v0.0.0-20200823014737-9f7001d12a5f|间接依赖|go|
|github.com/grafana/regexp|v0.0.0-20221122212121-6b5c0a4cb7fd|直接依赖|go|
|cloud.google.com/go/compute|v1.20.1|间接依赖|go|
|github.com/eapache/queue|v1.1.0|间接依赖|go|
|github.com/stretchr/objx|v0.5.0|间接依赖|go|
|github.com/grafana/gomemcache|v0.0.0-20230316202710-a081dae0aba9|直接依赖|go|
|golang.org/x/mod|v0.9.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/ini|v1.3.8|间接依赖|go|
|k8s.io/klog|v1.0.0|直接依赖|go|
|github.com/spf13/cast|v1.3.1|间接依赖|go|
|go.uber.org/zap|v1.24.0|间接依赖|go|
|go.mongodb.org/mongo-driver|v1.11.2|间接依赖|go|
|github.com/envoyproxy/go-control-plane|v0.11.0|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.17|间接依赖|go|
|go.opentelemetry.io/otel/trace|v1.14.0|间接依赖|go|
|github.com/digitalocean/godo|v1.98.0|间接依赖|go|
|github.com/hashicorp/go-hclog|v1.2.0|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|直接依赖|go|
|github.com/hashicorp/consul/api|v1.20.0|直接依赖|go|
|golang.org/x/sys|v0.6.0|间接依赖|go|
|github.com/willf/bloom|v2.0.3+incompatible|直接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20230303024457-afdc3dddf62d|间接依赖|go|
|pytz|2019.1|间接依赖|pip|
|cloud.google.com/go/storage|v1.29.0|直接依赖|go|
|github.com/Azure/go-autorest/autorest/adal|v0.9.23|直接依赖|go|
|github.com/grafana/tail|v0.0.0-20230510142333-77b18831edf0|直接依赖|go|
|github.com/sirupsen/logrus|v1.9.3|间接依赖|go|
|k8s.io/utils|v0.0.0-20230308161112-d77c459e9343|间接依赖|go|
|github.com/Azure/azure-sdk-for-go|v65.0.0+incompatible|间接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/net/http/otelhttp|v0.40.0|间接依赖|go|
|github.com/docker/go-metrics|v0.0.1|间接依赖|go|
|k8s.io/apiserver|v0.26.2|直接依赖|go|
|github.com/cncf/udpa/go|v0.0.0-20220112060539-c52dc94e7fbe|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/presigned-url|v1.9.1|间接依赖|go|
|google.golang.org/protobuf|v1.31.0|直接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|github.com/go-logfmt/logfmt|v0.6.0|直接依赖|go|
|github.com/weaveworks/promrus|v1.2.0|间接依赖|go|
|github.com/google/btree|v1.1.2|间接依赖|go|
|github.com/Azure/azure-pipeline-go|v0.2.3|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/feature/ec2/imds|v1.12.1|间接依赖|go|
|github.com/envoyproxy/protoc-gen-validate|v0.9.1|间接依赖|go|
|github.com/prometheus/prometheus|v0.41.0|间接依赖|go|
|github.com/frankban/quicktest|v1.7.2|间接依赖|go|
|github.com/mitchellh/copystructure|v1.0.0|间接依赖|go|
|github.com/tonistiigi/fifo|v0.0.0-20190226154929-a9fb20d87448|直接依赖|go|
|github.com/gorilla/websocket|v1.5.0|直接依赖|go|
|github.com/aws/aws-sdk-go|v1.44.321|直接依赖|go|
|github.com/grpc-ecosystem/go-grpc-middleware|v1.3.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2|v1.16.0|直接依赖|go|
|github.com/felixge/httpsnoop|v1.0.3|间接依赖|go|
|github.com/evanphx/json-patch/v5|v5.6.0|间接依赖|go|
|github.com/DmitriyVTitov/size|v1.5.0|直接依赖|go|
|github.com/leodido/ragel-machinery|v0.0.0-20181214104525-299bdde78165|间接依赖|go|
|go.uber.org/atomic|v1.11.0|直接依赖|go|
|github.com/mitchellh/go-wordwrap|v1.0.1|直接依赖|go|
|go.etcd.io/etcd/client/pkg/v3|v3.5.5|间接依赖|go|
|github.com/gofrs/flock|v0.8.1|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|直接依赖|go|
|github.com/go-openapi/errors|v0.20.3|间接依赖|go|
|github.com/ugorji/go/codec|v1.1.7|间接依赖|go|
|go.etcd.io/etcd/client/v3|v3.5.5|间接依赖|go|
|github.com/prometheus-operator/prometheus-operator/pkg/apis/monitoring|v0.48.0|直接依赖|go|
|requirements.txt||间接依赖|pip|
|github.com/jcmturner/dnsutils/v2|v2.0.0|间接依赖|go|
|go.etcd.io/bbolt|v1.3.6|直接依赖|go|
|github.com/golang/snappy|v0.0.1|直接依赖|go|
|golang.org/x/exp|v0.0.0-20230321023759-10a507213a29|直接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|github.com/gorilla/mux|v1.8.0|直接依赖|go|
|golang.org/x/mod|v0.7.0|间接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|直接依赖|go|
|github.com/golang-jwt/jwt/v4|v4.5.0|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|直接依赖|go|
|golang.org/x/tools|v0.5.0|间接依赖|go|
|golang.org/x/oauth2|v0.4.0|间接依赖|go|
|github.com/grafana/loki|v1.6.2-0.20230216091802-4e4359e67c6c|直接依赖|go|
|github.com/prometheus/client_model|v0.3.0|间接依赖|go|
|github.com/Microsoft/go-winio|v0.6.0|间接依赖|go|
|github.com/Masterminds/sprig/v3|v3.2.3|直接依赖|go|
|github.com/grafana/dskit|v0.0.0-20230201083518-528d8a7d52f2|直接依赖|go|
|github.com/alecthomas/units|v0.0.0-20211218093645-b94a6e3cc137|间接依赖|go|
|github.com/cristalhq/hedgedhttp|v0.7.2|直接依赖|go|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|github.com/edsrzf/mmap-go|v1.1.0|间接依赖|go|
|github.com/alicebob/gopher-json|v0.0.0-20200520072559-a9ecdc9d1d3a|间接依赖|go|
|k8s.io/api|v0.26.2|间接依赖|go|
|github.com/docker/go-units|v0.5.0|间接依赖|go|
|golang.org/x/net|v0.8.0|间接依赖|go|
|k8s.io/apiextensions-apiserver|v0.26.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sts|v1.16.1|间接依赖|go|
|google.golang.org/protobuf|v1.30.0|间接依赖|go|
|github.com/hashicorp/go-rootcerts|v1.0.2|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|golang.org/x/sys|v0.10.0|直接依赖|go|
|github.com/jcmturner/rpc/v2|v2.0.3|间接依赖|go|
|github.com/google/renameio/v2|v2.0.0|直接依赖|go|
|github.com/ncw/swift|v1.0.53|直接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|直接依赖|go|
|google.golang.org/protobuf|v1.28.1|间接依赖|go|
|github.com/openshift/api|v0.0.0-20230228142948-d170fcdc0fa6|直接依赖|go|
|sigs.k8s.io/json|v0.0.0-20220713155537-f223a00ba0e2|间接依赖|go|
|github.com/gogo/status|v1.1.1|直接依赖|go|
|golang.org/x/sync|v0.3.0|直接依赖|go|
|gopkg.in/fsnotify/fsnotify.v1|v1.4.7|间接依赖|go|
|golang.org/x/text|v0.11.0|直接依赖|go|
|golang.org/x/term|v0.10.0|间接依赖|go|
|github.com/leodido/go-urn|v1.2.1|间接依赖|go|
|github.com/jcmturner/gokrb5/v8|v8.4.3|间接依赖|go|
|github.com/xdg-go/scram|v1.1.2|直接依赖|go|
|github.com/gophercloud/gophercloud|v1.2.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/configsources|v1.1.7|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230306155012-7f2fa6fef1f4|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/s3shared|v1.9.2|间接依赖|go|
|github.com/google/gnostic|v0.5.7-v3refs|间接依赖|go|
|github.com/NYTimes/gziphandler|v1.1.1|直接依赖|go|
|github.com/go-openapi/loads|v0.21.2|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/aws/protocol/eventstream|v1.0.0|间接依赖|go|
|github.com/googleapis/gax-go/v2|v2.11.0|间接依赖|go|
|github.com/coreos/go-systemd|v0.0.0-20191104093116-d3cd4ed1dbcf|直接依赖|go|
|github.com/prometheus/client_model|v0.4.0|直接依赖|go|
|github.com/prometheus/prometheus|v0.42.0|直接依赖|go|
|github.com/oschwald/geoip2-golang|v1.9.0|直接依赖|go|
|github.com/bmatcuk/doublestar|v1.3.4|直接依赖|go|
|github.com/Shopify/sarama|v1.38.1|直接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/Masterminds/semver/v3|v3.2.0|间接依赖|go|
|golang.org/x/sync|v0.1.0|间接依赖|go|
|github.com/go-openapi/spec|v0.20.8|间接依赖|go|
|github.com/Azure/go-autorest/tracing|v0.6.0|间接依赖|go|
|github.com/imdario/mergo|v0.3.13|直接依赖|go|
|k8s.io/apimachinery|v0.26.3|直接依赖|go|
|github.com/google/uuid|v1.3.0|直接依赖|go|
|google.golang.org/grpc|v1.52.3|间接依赖|go|
|go.uber.org/goleak|v1.2.1|直接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/dustin/go-humanize|v1.0.1|直接依赖|go|
|github.com/go-openapi/analysis|v0.21.4|间接依赖|go|
|github.com/docker/go-connections|v0.4.0|间接依赖|go|
|golang.org/x/xerrors|v0.0.0-20220907171357-04be3eba64a2|间接依赖|go|
|github.com/prometheus/common|v0.44.0|直接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.3|间接依赖|go|
|github.com/fluent/fluent-bit-go|v0.0.0-20190925192703-ea13c021720c|直接依赖|go|
|github.com/influxdata/go-syslog/v3|v3.0.1-0.20201128200927-a1889d947b48|直接依赖|go|
|gopkg.in/ini.v1|v1.67.0|间接依赖|go|
|github.com/go-openapi/strfmt|v0.21.3|间接依赖|go|
|github.com/mitchellh/reflectwalk|v1.0.1|间接依赖|go|
|github.com/golang/protobuf|v1.5.3|直接依赖|go|
|golang.org/x/time|v0.3.0|直接依赖|go|
|github.com/willf/bitset|v1.1.11|间接依赖|go|
|github.com/hashicorp/go-multierror|v1.1.1|间接依赖|go|
|github.com/prometheus/client_golang|v1.14.0|间接依赖|go|
|github.com/spaolacci/murmur3|v1.1.0|间接依赖|go|
|github.com/eapache/go-resiliency|v1.3.0|间接依赖|go|
|golang.org/x/crypto|v0.5.0|间接依赖|go|
|github.com/stretchr/testify|v1.8.1|直接依赖|go|
|google.golang.org/genproto/googleapis/api|v0.0.0-20230530153820-e85fd2cbaebc|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/storage/azblob|v0.5.1|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|github.com/huandu/xstrings|v1.3.3|间接依赖|go|
|github.com/google/gofuzz|v1.2.0|间接依赖|go|
|golang.org/x/oauth2|v0.10.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/endpoints/v2|v2.4.1|间接依赖|go|
|golang.org/x/text|v0.7.0|间接依赖|go|
|gomodules.xyz/jsonpatch/v2|v2.2.0|间接依赖|go|
|github.com/prometheus/prometheus|v0.43.1-0.20230419161410-69155c6ba1e9|直接依赖|go|
|github.com/maxbrunsfeld/counterfeiter/v6|v6.3.0|直接依赖|go|
|github.com/AzureAD/microsoft-authentication-library-for-go|v0.7.0|间接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.0|间接依赖|go|
|github.com/sirupsen/logrus|v1.8.1|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/azidentity|v1.2.0|间接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0|间接依赖|go|
|github.com/gogo/googleapis|v1.4.0|间接依赖|go|
|github.com/yuin/gopher-lua|v1.1.0|间接依赖|go|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|gopkg.in/alecthomas/kingpin.v2|v2.2.6|直接依赖|go|
|github.com/armon/go-metrics|v0.4.0|间接依赖|go|
|github.com/grafana/cloudflare-go|v0.0.0-20230110200409-c627cf6792f2|直接依赖|go|
|cloud.google.com/go/bigtable|v1.18.1|直接依赖|go|
|github.com/Azure/go-ansiterm|v0.0.0-20210617225240-d185dfc1b5a1|间接依赖|go|
|github.com/segmentio/fasthash|v1.0.3|直接依赖|go|
|github.com/oklog/run|v1.1.0|直接依赖|go|
|github.com/miekg/dns|v1.1.53|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|github.com/grafana/dskit|v0.0.0-20230814145153-042a71bd637e|直接依赖|go|
|github.com/cespare/xxhash|v1.1.0|直接依赖|go|
|github.com/influxdata/telegraf|v1.16.3|直接依赖|go|
|github.com/sirupsen/logrus|v1.9.0|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/azcore|v1.2.0|间接依赖|go|
|github.com/mattn/go-ieproxy|v0.0.1|直接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|直接依赖|go|
|golang.org/x/tools|v0.4.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/s3|v1.22.0|直接依赖|go|
|github.com/go-redis/redis/v8|v8.11.5|直接依赖|go|
|sigs.k8s.io/json|v0.0.0-20221116044647-bc3834ca7abd|间接依赖|go|
|timedelta||间接依赖|pip|
|github.com/opentracing-contrib/go-grpc|v0.0.0-20210225150812-73cb765af46e|直接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|直接依赖|go|
|k8s.io/component-base|v0.26.2|间接依赖|go|
|k8s.io/utils|v0.0.0-20230313181309-38a27ef9d749|直接依赖|go|
|github.com/baidubce/bce-sdk-go|v0.9.141|直接依赖|go|
|golang.org/x/oauth2|v0.5.0|间接依赖|go|
|github.com/minio/sha256-simd|v1.0.1|间接依赖|go|
|github.com/go-playground/universal-translator|v0.18.1|间接依赖|go|
|github.com/klauspost/cpuid/v2|v2.2.5|间接依赖|go|
|golang.org/x/exp|v0.0.0-20221212164502-fae10dda9338|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|k8s.io/klog/v2|v2.80.1|间接依赖|go|
|github.com/hashicorp/go-msgpack|v0.5.5|间接依赖|go|
|github.com/prometheus/exporter-toolkit|v0.10.1-0.20230714054209-2f4150c63f97|间接依赖|go|
|github.com/kr/text|v0.2.0|间接依赖|go|
|google.golang.org/protobuf|v1.29.1|间接依赖|go|
|github.com/minio/minio-go/v7|v7.0.61|直接依赖|go|
|github.com/felixge/fgprof|v0.9.3|直接依赖|go|
|github.com/Azure/go-autorest/autorest/azure/auth|v0.5.12|直接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.6|间接依赖|go|
|k8s.io/api|v0.26.3|直接依赖|go|
|github.com/go-openapi/swag|v0.22.3|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/internal|v1.1.1|间接依赖|go|
|github.com/Azure/go-autorest/autorest|v0.11.29|直接依赖|go|
|k8s.io/klog/v2|v2.90.1|间接依赖|go|
|github.com/ViaQ/logerr/v2|v2.1.0|直接依赖|go|
|go.uber.org/zap|v1.21.0|间接依赖|go|
|github.com/Workiva/go-datastructures|v1.1.0|直接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.5|间接依赖|go|
|github.com/asaskevich/govalidator|v0.0.0-20230301143203-a9d515a09cc2|间接依赖|go|
|github.com/grafana/loki/pkg/push|v0.0.0-20230127102416-571f88bc5765|直接依赖|go|
|github.com/containerd/fifo|v1.0.0|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|github.com/miekg/dns|v1.1.50|间接依赖|go|
|github.com/efficientgo/core|v1.0.0-rc.2|间接依赖|go|
|github.com/Azure/go-autorest/autorest/validation|v0.3.1|间接依赖|go|
|github.com/pierrec/lz4/v4|v4.1.18|直接依赖|go|
|github.com/coreos/go-semver|v0.3.0|间接依赖|go|
|github.com/go-kit/log|v0.2.1|直接依赖|go|
|github.com/dustin/go-humanize|v1.0.0|间接依赖|go|
|github.com/sercand/kuberesolver/v4|v4.0.0|间接依赖|go|
|github.com/eapache/go-xerial-snappy|v0.0.0-20230111030713-bf00bc1b83b6|间接依赖|go|
|github.com/hashicorp/golang-lru|v0.6.0|直接依赖|go|
|gopkg.in/check.v1|v1.0.0-20201130134442-10cb98267c6c|间接依赖|go|
|github.com/grafana/loki/operator/apis/loki|v0.0.0-00010101000000-000000000000|直接依赖|go|
|github.com/dgryski/go-metro|v0.0.0-20180109044635-280f6062b5bc|间接依赖|go|
|github.com/fatih/color|v1.14.1|间接依赖|go|
|github.com/prometheus/procfs|v0.8.0|间接依赖|go|
|github.com/joncrlsn/dque|v2.2.1-0.20200515025108-956d14155fa2+incompatible|直接依赖|go|
|github.com/go-zookeeper/zk|v1.0.3|间接依赖|go|
|github.com/pierrec/lz4|v2.3.0+incompatible|直接依赖|go|
|golang.org/x/sys|v0.8.0|间接依赖|go|
|github.com/docker/distribution|v2.8.2+incompatible|间接依赖|go|
|github.com/imdario/mergo|v0.3.15|直接依赖|go|
|github.com/julienschmidt/httprouter|v1.3.0|间接依赖|go|
|go.uber.org/atomic|v1.10.0|间接依赖|go|
|cloud.google.com/go/compute/metadata|v0.2.3|间接依赖|go|
|github.com/dimchansky/utfbom|v1.1.1|间接依赖|go|
|k8s.io/client-go|v0.26.2|直接依赖|go|
|github.com/emicklei/go-restful/v3|v3.9.0|间接依赖|go|
|google.golang.org/grpc|v1.55.0|直接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.0|直接依赖|go|
|github.com/hashicorp/go-uuid|v1.0.3|间接依赖|go|
|github.com/prometheus/common|v0.39.0|直接依赖|go|
|go.etcd.io/etcd/api/v3|v3.5.5|间接依赖|go|
|google.golang.org/api|v0.126.0|直接依赖|go|
|github.com/kylelemons/godebug|v1.1.0|间接依赖|go|
|github.com/jpillora/backoff|v1.0.0|间接依赖|go|
|golang.org/x/term|v0.5.0|间接依赖|go|
|github.com/dennwc/varint|v1.0.0|间接依赖|go|
|github.com/docker/docker|v23.0.3+incompatible|直接依赖|go|
|github.com/golang/protobuf|v1.5.2|间接依赖|go|
|github.com/rs/xid|v1.5.0|间接依赖|go|
|golang.org/x/tools|v0.7.0|间接依赖|go|
|github.com/xdg-go/stringprep|v1.0.4|间接依赖|go|
|cloud.google.com/go/iam|v0.13.0|间接依赖|go|
|github.com/morikuni/aec|v1.0.0|间接依赖|go|
|github.com/openshift/library-go|v0.0.0-20230302173334-c5e706838384|直接依赖|go|
|github.com/prometheus/client_golang|v1.16.0|直接依赖|go|
|github.com/grafana/loki|v1.6.2-0.20230403212622-90888a0cc737|直接依赖|go|
|github.com/pkg/browser|v0.0.0-20210911075715-681adbf594b8|间接依赖|go|
|go.etcd.io/etcd/client/v3|v3.5.4|间接依赖|go|
|github.com/Azure/go-autorest/autorest/to|v0.4.0|间接依赖|go|
|github.com/googleapis/enterprise-certificate-proxy|v0.2.3|间接依赖|go|
|github.com/stretchr/testify|v1.8.2|直接依赖|go|
|go.etcd.io/etcd/api/v3|v3.5.4|间接依赖|go|
|github.com/IBM/go-sdk-core/v5|v5.13.1|直接依赖|go|
|github.com/rootless-containers/rootlesskit|v1.1.0|间接依赖|go|
|github.com/hashicorp/go-cleanhttp|v0.5.2|间接依赖|go|
|github.com/hashicorp/consul/api|v1.18.0|间接依赖|go|
|github.com/google/s2a-go|v0.1.4|间接依赖|go|
|github.com/google/pprof|v0.0.0-20230228050547-1710fef4ab10|间接依赖|go|
|github.com/cncf/xds/go|v0.0.0-20230112175826-46e39c7b9b43|间接依赖|go|
|github.com/mwitkow/go-conntrack|v0.0.0-20190716064945-2f068394615f|直接依赖|go|
|github.com/hashicorp/errwrap|v1.1.0|间接依赖|go|
|go.opentelemetry.io/otel/trace|v1.11.2|间接依赖|go|
|golang.org/x/net|v0.7.0|间接依赖|go|
|github.com/prometheus/procfs|v0.10.1|间接依赖|go|
|github.com/Azure/go-autorest/autorest/date|v0.3.0|间接依赖|go|
|github.com/opentracing/opentracing-go|v1.2.0|直接依赖|go|
|github.com/IBM/ibm-cos-sdk-go|v1.10.0|直接依赖|go|
|github.com/moby/term|v0.0.0-20210619224110-3f7ff695adc6|间接依赖|go|
|github.com/drone/envsubst|v1.0.3|直接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|cloud.google.com/go/pubsub|v1.30.0|直接依赖|go|
|github.com/Azure/go-autorest/logger|v0.2.1|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|直接依赖|go|
|github.com/emicklei/go-restful/v3|v3.10.1|间接依赖|go|
|github.com/go-playground/validator/v10|v10.11.2|间接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|github.com/aws/aws-sdk-go|v1.44.187|间接依赖|go|
|github.com/alicebob/miniredis/v2|v2.30.4|直接依赖|go|
|github.com/gocql/gocql|v0.0.0-20200526081602-cd04bd7f22a7|直接依赖|go|
|github.com/prometheus/common/sigv4|v0.1.0|直接依赖|go|
|github.com/pmezard/go-difflib|v1.0.1-0.20181226105442-5d4384ee4fb2|间接依赖|go|
|github.com/thanos-io/objstore|v0.0.0-20230201072718-11ffbc490204|直接依赖|go|
|cloud.google.com/go|v0.110.2|间接依赖|go|
|github.com/shurcooL/vfsgen|v0.0.0-20200824052919-0d455de96546|直接依赖|go|
|gopkg.in/tomb.v1|v1.0.0-20141024135613-dd632973f1e7|间接依赖|go|
|github.com/fsouza/fake-gcs-server|v1.7.0|直接依赖|go|
|github.com/rcrowley/go-metrics|v0.0.0-20201227073835-cf1acfcdf475|间接依赖|go|
|google.golang.org/grpc|v1.53.0|直接依赖|go|
|github.com/facette/natsort|v0.0.0-20181210072756-2cd4dd1e2dcb|直接依赖|go|
|github.com/opencontainers/image-spec|v1.0.2|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/credentials|v1.11.0|间接依赖|go|
|github.com/go-logr/logr|v1.2.3|直接依赖|go|
|github.com/google/gnostic|v0.6.9|间接依赖|go|
|github.com/buger/jsonparser|v1.1.1|直接依赖|go|
|go.etcd.io/etcd/client/pkg/v3|v3.5.4|间接依赖|go|
|github.com/shurcooL/httpfs|v0.0.0-20190707220628-8d4bc4ba7749|直接依赖|go|
|github.com/heroku/x|v0.0.61|直接依赖|go|
|github.com/jcmturner/aescts/v2|v2.0.0|间接依赖|go|
|cloud.google.com/go/longrunning|v0.4.1|间接依赖|go|
|github.com/jcmturner/gofork|v1.7.6|间接依赖|go|
|github.com/golang/snappy|v0.0.4|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/accept-encoding|v1.5.0|间接依赖|go|
|golang.org/x/crypto|v0.11.0|直接依赖|go|
|github.com/HdrHistogram/hdrhistogram-go|v1.1.2|间接依赖|go|
|github.com/shopspring/decimal|v1.2.0|间接依赖|go|
|go.opentelemetry.io/otel|v1.14.0|间接依赖|go|
|golang.org/x/sys|v0.5.0|间接依赖|go|
|github.com/grpc-ecosystem/grpc-opentracing|v0.0.0-20180507213350-8e809c8a8645|直接依赖|go|
|github.com/aws/smithy-go|v1.11.1|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230110181048-76db0878b65f|间接依赖|go|
|go.opencensus.io|v0.24.0|间接依赖|go|
|github.com/hashicorp/serf|v0.10.1|间接依赖|go|
|github.com/go-kit/kit|v0.12.0|间接依赖|go|
|golang.org/x/exp|v0.0.0-20230124195608-d38c7dcee874|间接依赖|go|
|github.com/sean-/seed|v0.0.0-20170313163322-e2103e2c3529|间接依赖|go|
|github.com/Masterminds/goutils|v1.1.1|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230124163310-31e0e69b6fc2|间接依赖|go|
|github.com/coreos/go-systemd/v22|v22.4.0|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/stretchr/testify|v1.8.4|直接依赖|go|
|github.com/alecthomas/template|v0.0.0-20190718012654-fb15b899a751|间接依赖|go|
|go.opentelemetry.io/otel|v1.11.2|间接依赖|go|
|golang.org/x/text|v0.8.0|间接依赖|go|
|github.com/uber/jaeger-lib|v2.4.1+incompatible|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230530153820-e85fd2cbaebc|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20221207184640-f3cff1453715|间接依赖|go|
|github.com/klauspost/compress|v1.11.7|直接依赖|go|
|github.com/opentracing-contrib/go-stdlib|v1.0.0|直接依赖|go|
|github.com/prometheus/exporter-toolkit|v0.8.2|间接依赖|go|
|golang.org/x/sync|v0.2.0|间接依赖|go|
|github.com/hashicorp/go-immutable-radix|v1.3.1|间接依赖|go|
|github.com/google/gofuzz|v1.1.0|间接依赖|go|
|github.com/weaveworks/common|v0.0.0-20221201103051-7c2720a9024d|间接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|github.com/Azure/azure-storage-blob-go|v0.14.0|直接依赖|go|
|github.com/sony/gobreaker|v0.5.0|直接依赖|go|
|rsc.io/binaryregexp|v0.2.0|间接依赖|go|
|github.com/grafana/go-gelf/v2|v2.0.1|直接依赖|go|
|sigs.k8s.io/yaml|v1.3.0|直接依赖|go|
|github.com/Azure/go-autorest|v14.2.0+incompatible|间接依赖|go|
|github.com/c2h5oh/datasize|v0.0.0-20200112174442-28bbd4740fee|直接依赖|go|
|go.opentelemetry.io/otel/metric|v0.37.0|间接依赖|go|
|golang.org/x/net|v0.12.0|直接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|直接依赖|go|
|github.com/google/go-querystring|v1.1.0|间接依赖|go|
|github.com/richardartoul/molecule|v1.0.0|直接依赖|go|
|github.com/oklog/ulid|v1.3.1|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)