# kubernetes-sigs/external-dns安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692961609697087488.svg)](https://www.murphysec.com/console/report/1692961609621590016/1692961609697087488)

仓库描述：Configure external DNS servers (AWS Route53, Google CloudDNS and others) for Kubernetes Ingresses and Services

仓库地址：[https://github.com/kubernetes-sigs/external-dns](https://github.com/kubernetes-sigs/external-dns)

| star：6571 | watch：107 | fork：2396 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-19 13:06:11 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-20 02:08:08 | 组件总数：204 | 漏洞总数：0 |

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
|MPL-2.0|7|Low|
|Apache-2.0|86|Low|
|BSD-3-Clause|38|Low|
|MIT|70|Low|
|UPL-1.0|1|Low|
|BSD-2-Clause|3|Low|
|ISC|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/hashicorp/go-cleanhttp|v0.5.2|间接依赖|go|
|github.com/jcmturner/gokrb5/v8|v8.4.3|间接依赖|go|
|k8s.io/apimachinery|v0.27.4|直接依赖|go|
|cloud.google.com/go/compute/metadata|v0.2.3|直接依赖|go|
|github.com/google/uuid|v1.3.0|直接依赖|go|
|github.com/aws/aws-sdk-go|v1.44.311|直接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|间接依赖|go|
|code.cloudfoundry.org/gofileutils|v0.0.0-20170111115228-4d0c80011a0f|间接依赖|go|
|github.com/go-openapi/errors|v0.20.3|间接依赖|go|
|github.com/oklog/ulid|v1.3.1|间接依赖|go|
|github.com/miekg/dns|v1.1.55|直接依赖|go|
|github.com/tencentcloud/tencentcloud-sdk-go/tencentcloud/privatedns|v1.0.710|直接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.1|间接依赖|go|
|github.com/transip/gotransip/v6|v6.21.0|直接依赖|go|
|sigs.k8s.io/yaml|v1.3.0|间接依赖|go|
|github.com/terra-farm/udnssdk|v1.3.5|间接依赖|go|
|github.com/digitalocean/godo|v1.100.0|直接依赖|go|
|github.com/IBM/networking-go-sdk|v0.42.2|直接依赖|go|
|github.com/ovh/go-ovh|v1.4.1|直接依赖|go|
|github.com/sony/gobreaker|v0.5.0|间接依赖|go|
|go.etcd.io/etcd/client/pkg/v3|v3.5.9|间接依赖|go|
|github.com/linki/instrumented_http|v0.3.0|直接依赖|go|
|github.com/ans-group/go-durationstring|v1.2.0|间接依赖|go|
|github.com/jcmturner/aescts/v2|v2.0.0|间接依赖|go|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|github.com/Azure/go-autorest/logger|v0.2.1|间接依赖|go|
|github.com/alecthomas/kingpin|v2.2.6+incompatible|直接依赖|go|
|github.com/ultradns/ultradns-sdk-go|v1.3.7|直接依赖|go|
|github.com/smartystreets/go-aws-auth|v0.0.0-20180515143844-0c1422d1fdb9|间接依赖|go|
|github.com/IBM-Cloud/ibm-cloud-cli-sdk|v1.1.0|直接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/tencentcloud/tencentcloud-sdk-go/tencentcloud/common|v1.0.710|直接依赖|go|
|github.com/google/gofuzz|v1.2.0|间接依赖|go|
|moul.io/http2curl|v1.0.0|间接依赖|go|
|github.com/openshift/api|v0.0.0-20230607130528-611114dca681|直接依赖|go|
|github.com/deepmap/oapi-codegen|v1.9.1|间接依赖|go|
|go.uber.org/multierr|v1.8.0|间接依赖|go|
|go.uber.org/atomic|v1.9.0|间接依赖|go|
|github.com/schollz/progressbar/v3|v3.8.6|间接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|go.uber.org/zap|v1.24.0|间接依赖|go|
|golang.org/x/mod|v0.10.0|间接依赖|go|
|github.com/nxadm/tail|v1.4.8|间接依赖|go|
|github.com/Azure/go-autorest/autorest/adal|v0.9.23|直接依赖|go|
|golang.org/x/sync|v0.3.0|直接依赖|go|
|github.com/golang-jwt/jwt/v4|v4.5.0|间接依赖|go|
|golang.org/x/text|v0.11.0|间接依赖|go|
|google.golang.org/api|v0.134.0|直接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.3|间接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|go.mongodb.org/mongo-driver|v1.11.3|间接依赖|go|
|github.com/prometheus/client_golang|v1.16.0|直接依赖|go|
|github.com/spf13/afero|v1.9.3|间接依赖|go|
|github.com/mattn/go-runewidth|v0.0.13|间接依赖|go|
|github.com/go-gandi/go-gandi|v0.6.0|直接依赖|go|
|github.com/oracle/oci-go-sdk/v65|v65.45.0|直接依赖|go|
|github.com/Masterminds/semver|v1.4.2|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20230501164219-8b0f38b5fd1f|间接依赖|go|
|golang.org/x/net|v0.12.0|直接依赖|go|
|google.golang.org/genproto/googleapis/api|v0.0.0-20230706204954-ccb25ca9f130|间接依赖|go|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|github.com/jcmturner/rpc/v2|v2.0.3|间接依赖|go|
|sigs.k8s.io/gateway-api|v0.7.1|直接依赖|go|
|github.com/patrickmn/go-cache|v2.1.0+incompatible|直接依赖|go|
|github.com/go-playground/universal-translator|v0.18.1|间接依赖|go|
|github.com/vinyldns/go-vinyldns|v0.9.16|直接依赖|go|
|gopkg.in/resty.v1|v1.12.0|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|golang.org/x/sys|v0.10.0|间接依赖|go|
|github.com/gofrs/uuid|v4.4.0+incompatible|间接依赖|go|
|github.com/Azure/azure-sdk-for-go|v68.0.0+incompatible|直接依赖|go|
|github.com/mitchellh/colorstring|v0.0.0-20190213212951-d06e56a500db|间接依赖|go|
|github.com/stretchr/objx|v0.5.0|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|间接依赖|go|
|github.com/gophercloud/gophercloud|v1.5.0|直接依赖|go|
|github.com/googleapis/enterprise-certificate-proxy|v0.2.5|间接依赖|go|
|golang.org/x/term|v0.10.0|间接依赖|go|
|github.com/fatih/structs|v1.1.0|间接依赖|go|
|github.com/go-openapi/strfmt|v0.21.5|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/googleapis/gax-go/v2|v2.12.0|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|github.com/leodido/go-urn|v1.2.3|间接依赖|go|
|github.com/subosito/gotenv|v1.4.2|间接依赖|go|
|github.com/sirupsen/logrus|v1.9.3|直接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|istio.io/client-go|v1.18.1|直接依赖|go|
|github.com/benbjohnson/clock|v1.3.0|间接依赖|go|
|github.com/hashicorp/errwrap|v1.1.0|间接依赖|go|
|google.golang.org/grpc|v1.56.2|间接依赖|go|
|github.com/stretchr/testify|v1.8.4|直接依赖|go|
|github.com/cloudflare/cloudflare-go|v0.73.0|直接依赖|go|
|k8s.io/client-go|v0.27.4|直接依赖|go|
|gopkg.in/go-playground/validator.v9|v9.31.0|间接依赖|go|
|github.com/go-resty/resty/v2|v2.7.0|间接依赖|go|
|github.com/openshift/client-go|v0.0.0-20230607134213-3cd0021bbee3|直接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|github.com/spf13/viper|v1.15.0|间接依赖|go|
|github.com/exoscale/egoscale|v0.100.3|直接依赖|go|
|go.etcd.io/etcd/api/v3|v3.5.9|直接依赖|go|
|github.com/ans-group/sdk-go|v1.16.6|直接依赖|go|
|github.com/hooklift/gowsdl|v0.5.0|直接依赖|go|
|github.com/akamai/AkamaiOPEN-edgegrid-golang|v1.2.2|直接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/nic-at/rc0go|v1.1.1|直接依赖|go|
|github.com/Azure/go-autorest/tracing|v0.6.0|间接依赖|go|
|github.com/imdario/mergo|v0.3.15|间接依赖|go|
|github.com/openshift/gssapi|v0.0.0-20161010215902-5fb4217df13b|间接依赖|go|
|github.com/spf13/jwalterweatherman|v1.1.0|间接依赖|go|
|github.com/jcmturner/gofork|v1.7.6|间接依赖|go|
|github.com/datawire/ambassador|v1.12.4|直接依赖|go|
|github.com/jcmturner/dnsutils/v2|v2.0.0|间接依赖|go|
|go.etcd.io/etcd/client/v3|v3.5.9|直接依赖|go|
|github.com/smartystreets/gunit|v1.3.4|间接依赖|go|
|github.com/maxatome/go-testdeep|v1.13.0|直接依赖|go|
|k8s.io/api|v0.27.4|直接依赖|go|
|google.golang.org/genproto|v0.0.0-20230706204954-ccb25ca9f130|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230720185612-659f7aaaa771|间接依赖|go|
|github.com/civo/civogo|v0.3.42|直接依赖|go|
|gopkg.in/tomb.v1|v1.0.0-20141024135613-dd632973f1e7|间接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|github.com/F5Networks/k8s-bigip-ctlr/v2|v2.13.1|直接依赖|go|
|github.com/alexbrainman/sspi|v0.0.0-20180613141037-e580b900e9f5|间接依赖|go|
|github.com/prometheus/client_model|v0.4.0|间接依赖|go|
|github.com/Yamashou/gqlgenc|v0.14.0|间接依赖|go|
|github.com/nesv/go-dynect|v0.6.0|直接依赖|go|
|istio.io/api|v1.19.0-alpha.1|直接依赖|go|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|github.com/opentracing/opentracing-go|v1.2.1-0.20220228012449-10b1cf09e00b|间接依赖|go|
|github.com/dnsimple/dnsimple-go|v1.2.0|直接依赖|go|
|github.com/spf13/cast|v1.5.0|间接依赖|go|
|github.com/scaleway/scaleway-sdk-go|v1.0.0-beta.20|直接依赖|go|
|github.com/denverdino/aliyungo|v0.0.0-20190125010748-a747050bb1ba|直接依赖|go|
|github.com/magiconair/properties|v1.8.7|间接依赖|go|
|github.com/Azure/go-autorest/autorest|v0.11.29|直接依赖|go|
|gopkg.in/ini.v1|v1.67.0|间接依赖|go|
|github.com/alecthomas/template|v0.0.0-20190718012654-fb15b899a751|间接依赖|go|
|github.com/hashicorp/go-uuid|v1.0.3|间接依赖|go|
|github.com/bodgit/tsig|v1.2.2|直接依赖|go|
|github.com/peterhellberg/link|v1.1.0|间接依赖|go|
|github.com/Azure/go-autorest|v14.2.0+incompatible|间接依赖|go|
|sigs.k8s.io/controller-runtime|v0.14.6|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|直接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|gopkg.in/ns1/ns1-go.v2|v2.7.8|直接依赖|go|
|github.com/ffledgling/pdns-go|v0.0.0-20180219074714-524e7daccd99|直接依赖|go|
|github.com/google/gnostic|v0.6.9|间接依赖|go|
|github.com/go-logr/logr|v1.2.4|间接依赖|go|
|github.com/vektah/gqlparser/v2|v2.5.1|间接依赖|go|
|github.com/go-openapi/swag|v0.22.3|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/prometheus/common|v0.43.0|间接依赖|go|
|github.com/coreos/go-semver|v0.3.0|间接依赖|go|
|github.com/hashicorp/go-multierror|v1.1.1|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/cloudfoundry-community/go-cfclient|v0.0.0-20190201205600-f136f9222381|直接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/alecthomas/units|v0.0.0-20211218093645-b94a6e3cc137|间接依赖|go|
|github.com/asaskevich/govalidator|v0.0.0-20230301143203-a9d515a09cc2|间接依赖|go|
|github.com/jinzhu/copier|v0.3.5|间接依赖|go|
|golang.org/x/oauth2|v0.10.0|直接依赖|go|
|k8s.io/klog/v2|v2.100.1|间接依赖|go|
|github.com/onsi/ginkgo|v1.16.5|直接依赖|go|
|github.com/jcmturner/goidentity/v6|v6.0.1|间接依赖|go|
|github.com/go-playground/validator/v10|v10.13.0|间接依赖|go|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|golang.org/x/crypto|v0.11.0|间接依赖|go|
|github.com/StackExchange/dnscontrol/v3|v3.31.6|直接依赖|go|
|github.com/prometheus/procfs|v0.10.1|间接依赖|go|
|github.com/gofrs/flock|v0.8.1|间接依赖|go|
|github.com/frankban/quicktest|v1.14.4|间接依赖|go|
|github.com/hashicorp/go-retryablehttp|v0.7.4|间接依赖|go|
|github.com/google/go-querystring|v1.1.0|间接依赖|go|
|github.com/coreos/go-systemd/v22|v22.3.3-0.20220203105225-a9a7ef127534|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/evanphx/json-patch|v5.6.0+incompatible|间接依赖|go|
|github.com/tencentcloud/tencentcloud-sdk-go/tencentcloud/dnspod|v1.0.710|直接依赖|go|
|k8s.io/utils|v0.0.0-20230505201702-9f6742963106|间接依赖|go|
|github.com/Azure/go-autorest/autorest/to|v0.4.0|直接依赖|go|
|github.com/projectcontour/contour|v1.25.2|直接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.0|间接依赖|go|
|cloud.google.com/go/compute|v1.20.1|间接依赖|go|
|github.com/go-playground/locales|v0.14.1|间接依赖|go|
|github.com/linode/linodego|v1.19.0|直接依赖|go|
|go.opencensus.io|v0.24.0|间接依赖|go|
|sigs.k8s.io/json|v0.0.0-20221116044647-bc3834ca7abd|间接依赖|go|
|golang.org/x/tools|v0.8.0|间接依赖|go|
|google.golang.org/protobuf|v1.31.0|间接依赖|go|
|github.com/vultr/govultr/v2|v2.17.2|直接依赖|go|
|github.com/emicklei/go-restful/v3|v3.10.2|间接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.6|间接依赖|go|
|github.com/pelletier/go-toml/v2|v2.0.6|间接依赖|go|
|github.com/google/s2a-go|v0.1.4|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/infobloxopen/infoblox-go-client/v2|v2.3.0|直接依赖|go|
|github.com/Azure/go-autorest/autorest/date|v0.3.0|间接依赖|go|
|golang.org/x/time|v0.3.0|直接依赖|go|
|github.com/aliyun/alibaba-cloud-sdk-go|v1.62.483|直接依赖|go|
|go.uber.org/ratelimit|v0.3.0|直接依赖|go|
|github.com/IBM/go-sdk-core/v5|v5.13.4|直接依赖|go|
|github.com/rivo/uniseg|v0.2.0|间接依赖|go|
|github.com/pluralsh/gqlclient|v1.6.0|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)