# sigstore/cosign安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694413003603472384.svg)](https://www.murphysec.com/console/report/1694413003439894528/1694413003603472384)

仓库描述：Container Signing

仓库地址：[https://github.com/sigstore/cosign](https://github.com/sigstore/cosign)

| star：3558 | watch：51 | fork：437 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-24 01:15:24 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-24 02:15:24 | 组件总数：293 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|github.com/urfave/negroni 存在跨站重定向漏洞|跨站重定向|[MPS-2022-13490](https://www.oscs1024.com/hd/MPS-2022-13490)||中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/urfave/negroni|v1.0.0||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|146|Low|
|BSD-3-Clause|49|Low|
|MIT|84|Low|
|MPL-2.0|11|Low|
|BSD-2-Clause|7|Low|
|ISC|3|Low|
|CC-BY-SA-4.0|1|Medium|
|BSD-2-Clause-Views|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/alibabacloud-go/cr-20160607|v1.0.1|间接依赖|go|
|github.com/sigstore/rekor|v1.2.2|直接依赖|go|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|github.com/prometheus/client_model|v0.4.0|间接依赖|go|
|github.com/sigstore/sigstore/pkg/signature/kms/gcp|v1.7.2|直接依赖|go|
|github.com/google/uuid|v1.3.0|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|golang.org/x/exp|v0.0.0-20230321023759-10a507213a29|间接依赖|go|
|github.com/lestrrat-go/blackmagic|v1.0.1|间接依赖|go|
|github.com/lestrrat-go/jwx/v2|v2.0.11|间接依赖|go|
|github.com/alibabacloud-go/endpoint-util|v1.1.1|间接依赖|go|
|sigs.k8s.io/json|v0.0.0-20221116044647-bc3834ca7abd|间接依赖|go|
|github.com/hashicorp/go-secure-stdlib/strutil|v0.1.2|间接依赖|go|
|github.com/Azure/go-autorest/tracing|v0.6.0|间接依赖|go|
|github.com/xeipuuv/gojsonreference|v0.0.0-20180127040603-bd5ef7bd5415|间接依赖|go|
|github.com/Azure/go-autorest/autorest/azure/cli|v0.4.6|间接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/mpvl/unique|v0.0.0-20150818121801-cbe035fff7de|间接依赖|go|
|github.com/russross/blackfriday/v2|v2.1.0|间接依赖|go|
|github.com/cockroachdb/apd/v3|v3.2.0|间接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|间接依赖|go|
|github.com/alibabacloud-go/openapi-util|v0.0.11|间接依赖|go|
|golang.org/x/oauth2|v0.11.0|直接依赖|go|
|google.golang.org/genproto/googleapis/api|v0.0.0-20230803162519-f966b187b2e5|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|间接依赖|go|
|github.com/gobwas/glob|v0.2.3|间接依赖|go|
|github.com/common-nighthawk/go-figure|v0.0.0-20210622060536-734e95fb86be|间接依赖|go|
|github.com/oleiade/reflections|v1.0.1|间接依赖|go|
|github.com/golang/snappy|v0.0.4|间接依赖|go|
|github.com/decred/dcrd/dcrec/secp256k1/v4|v4.2.0|间接依赖|go|
|github.com/alibabacloud-go/tea-utils|v1.4.4|间接依赖|go|
|github.com/chrismellard/docker-credential-acr-env|v0.0.0-20220119192733-fe33c00cee21|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/ini|v1.3.38|间接依赖|go|
|github.com/buildkite/interpolate|v0.0.0-20200526001904-07f35b4ae251|间接依赖|go|
|github.com/goccy/go-json|v0.10.2|间接依赖|go|
|github.com/go-chi/chi|v4.1.2+incompatible|间接依赖|go|
|github.com/alibabacloud-go/cr-20181201|v1.0.10|间接依赖|go|
|github.com/cpuguy83/go-md2man/v2|v2.0.2|间接依赖|go|
|github.com/mitchellh/go-wordwrap|v1.0.1|直接依赖|go|
|github.com/urfave/negroni|v1.0.0|间接依赖|go|
|go.uber.org/atomic|v1.11.0|间接依赖|go|
|github.com/sigstore/fulcio|v1.4.0|直接依赖|go|
|github.com/go-openapi/analysis|v0.21.4|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|github.com/DataDog/datadog-go/v5|v5.3.0|间接依赖|go|
|github.com/lestrrat-go/httprc|v1.0.4|间接依赖|go|
|github.com/go-openapi/errors|v0.20.4|间接依赖|go|
|github.com/klauspost/compress|v1.16.5|间接依赖|go|
|github.com/digitorus/timestamp|v0.0.0-20230821155606-d1ad5ca9624c|直接依赖|go|
|github.com/stretchr/testify|v1.8.4|直接依赖|go|
|cloud.google.com/go/kms|v1.15.1|间接依赖|go|
|k8s.io/utils|v0.0.0-20230505201702-9f6742963106|直接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/sigstore/timestamp-authority|v1.1.2|直接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sts|v1.21.1|间接依赖|go|
|github.com/buildkite/agent/v3|v3.52.0|直接依赖|go|
|github.com/sigstore/sigstore/pkg/signature/kms/hashivault|v1.7.2|直接依赖|go|
|github.com/ebitengine/purego|v0.4.0-alpha.4.0.20230519103000-ee8dcecc618f|间接依赖|go|
|github.com/docker/go-units|v0.5.0|间接依赖|go|
|github.com/opentracing/opentracing-go|v1.2.0|间接依赖|go|
|cuelang.org/go|v0.6.0|直接依赖|go|
|github.com/vbatts/tar-split|v0.11.3|间接依赖|go|
|github.com/go-openapi/swag|v0.22.4|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/presigned-url|v1.9.31|间接依赖|go|
|github.com/spf13/afero|v1.9.5|间接依赖|go|
|github.com/mozillazg/docker-credential-acr-helper|v0.3.0|直接依赖|go|
|github.com/google/go-github/v53|v53.2.0|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/security/keyvault/azkeys|v1.0.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/config|v1.18.32|间接依赖|go|
|github.com/philhofer/fwd|v1.1.2|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/azcore|v1.7.1|间接依赖|go|
|golang.org/x/mod|v0.11.0|间接依赖|go|
|github.com/go-ini/ini|v1.67.0|间接依赖|go|
|github.com/segmentio/ksuid|v1.0.4|间接依赖|go|
|k8s.io/api|v0.27.3|直接依赖|go|
|github.com/spf13/viper|v1.16.0|直接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|github.com/AliyunContainerService/ack-ram-tool/pkg/credentials/alibabacloudsdkgo/helper|v0.2.0|间接依赖|go|
|github.com/pborman/uuid|v1.2.1|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|github.com/lestrrat-go/httpcc|v1.0.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ssooidc|v1.15.1|间接依赖|go|
|github.com/google/gofuzz|v1.2.0|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230803162519-f966b187b2e5|间接依赖|go|
|github.com/clbanning/mxj/v2|v2.5.6|间接依赖|go|
|github.com/spf13/cobra|v1.7.0|直接依赖|go|
|github.com/cenkalti/backoff/v3|v3.2.2|间接依赖|go|
|github.com/digitorus/pkcs7|v0.0.0-20230818184609-3a137a874352|间接依赖|go|
|github.com/hashicorp/go-retryablehttp|v0.7.4|间接依赖|go|
|go.mongodb.org/mongo-driver|v1.11.3|间接依赖|go|
|github.com/syndtr/goleveldb|v1.0.1-0.20220721030215-126854af5e6d|间接依赖|go|
|github.com/protocolbuffers/txtpbfmt|v0.0.0-20230328191034-3462fbc510c0|间接依赖|go|
|google.golang.org/api|v0.138.0|直接依赖|go|
|github.com/spf13/cast|v1.5.1|间接依赖|go|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|golang.org/x/net|v0.14.0|间接依赖|go|
|github.com/transparency-dev/merkle|v0.0.2|直接依赖|go|
|golang.org/x/sys|v0.11.0|间接依赖|go|
|k8s.io/klog/v2|v2.100.1|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/security/keyvault/internal|v0.8.0|间接依赖|go|
|github.com/opencontainers/image-spec|v1.1.0-rc4|间接依赖|go|
|github.com/in-toto/in-toto-golang|v0.9.0|直接依赖|go|
|github.com/tinylib/msgp|v1.1.8|间接依赖|go|
|github.com/blang/semver|v3.5.1+incompatible|间接依赖|go|
|github.com/prometheus/client_golang|v1.16.0|间接依赖|go|
|go4.org/unsafe/assume-no-moving-gc|v0.0.0-20220617031537-928513b29760|间接依赖|go|
|github.com/spiffe/go-spiffe/v2|v2.1.6|直接依赖|go|
|github.com/cyberphone/json-canonicalization|v0.0.0-20220623050100-57a0ce2678a7|直接依赖|go|
|github.com/sirupsen/logrus|v1.9.3|间接依赖|go|
|golang.org/x/time|v0.3.0|间接依赖|go|
|github.com/zeebo/errs|v1.3.0|间接依赖|go|
|github.com/hashicorp/errwrap|v1.1.0|间接依赖|go|
|github.com/alibabacloud-go/darabonba-openapi|v0.1.18|间接依赖|go|
|go.opentelemetry.io/otel/metric|v1.16.0|间接依赖|go|
|go.opentelemetry.io/otel/sdk|v1.16.0|间接依赖|go|
|github.com/asaskevich/govalidator|v0.0.0-20230301143203-a9d515a09cc2|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/endpoints/v2|v2.4.31|间接依赖|go|
|github.com/segmentio/asm|v1.2.0|间接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230807174057-1744710a1577|间接依赖|go|
|github.com/docker/cli|v24.0.0+incompatible|间接依赖|go|
|gopkg.in/ini.v1|v1.67.0|间接依赖|go|
|github.com/hashicorp/go-cleanhttp|v0.5.2|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/google/go-containerregistry|v0.16.1|直接依赖|go|
|github.com/hashicorp/go-rootcerts|v1.0.2|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sso|v1.13.1|间接依赖|go|
|github.com/sigstore/sigstore/pkg/signature/kms/azure|v1.7.2|直接依赖|go|
|github.com/go-openapi/strfmt|v0.21.7|直接依赖|go|
|golang.org/x/term|v0.11.0|直接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|filippo.io/edwards25519|v1.0.0|间接依赖|go|
|github.com/jedisct1/go-minisign|v0.0.0-20211028175153-1c139d1cc84b|间接依赖|go|
|github.com/hashicorp/go-secure-stdlib/parseutil|v0.1.7|间接依赖|go|
|github.com/shibumi/go-pathspec|v1.3.0|间接依赖|go|
|github.com/theupdateframework/go-tuf|v0.6.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/credentials|v1.13.31|间接依赖|go|
|github.com/miekg/pkcs11|v1.1.1|直接依赖|go|
|go4.org/intern|v0.0.0-20211027215823-ae77deb06f29|间接依赖|go|
|go.opentelemetry.io/otel/trace|v1.16.0|间接依赖|go|
|google.golang.org/grpc|v1.57.0|间接依赖|go|
|github.com/kylelemons/godebug|v1.1.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ecr|v1.15.0|间接依赖|go|
|github.com/docker/docker-credential-helpers|v0.7.0|间接依赖|go|
|github.com/dimchansky/utfbom|v1.1.1|间接依赖|go|
|github.com/moby/term|v0.5.0|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/azidentity|v1.3.0|间接依赖|go|
|github.com/imdario/mergo|v0.3.15|间接依赖|go|
|github.com/DataDog/datadog-agent/pkg/obfuscate|v0.45.0-rc.1|间接依赖|go|
|github.com/google/tink/go|v1.7.0|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|github.com/go-playground/validator/v10|v10.15.1|间接依赖|go|
|github.com/gabriel-vasile/mimetype|v1.4.2|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/configsources|v1.1.37|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/kms|v1.24.1|间接依赖|go|
|github.com/google/go-querystring|v1.1.0|间接依赖|go|
|github.com/aliyun/credentials-go|v1.2.3|间接依赖|go|
|github.com/Azure/azure-sdk-for-go|v68.0.0+incompatible|间接依赖|go|
|golang.org/x/crypto|v0.12.0|直接依赖|go|
|github.com/nozzle/throttler|v0.0.0-20180817012639-2ea982251481|直接依赖|go|
|go.uber.org/zap|v1.25.0|间接依赖|go|
|github.com/go-logr/logr|v1.2.4|间接依赖|go|
|go.uber.org/multierr|v1.11.0|间接依赖|go|
|github.com/ThalesIgnite/crypto11|v1.2.5|直接依赖|go|
|github.com/Azure/go-autorest/logger|v0.2.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2|v1.20.0|间接依赖|go|
|github.com/lestrrat-go/option|v1.0.1|间接依赖|go|
|github.com/Microsoft/go-winio|v0.6.1|间接依赖|go|
|k8s.io/apimachinery|v0.27.3|直接依赖|go|
|github.com/go-piv/piv-go|v1.11.0|直接依赖|go|
|github.com/DataDog/appsec-internal-go|v1.0.0|间接依赖|go|
|github.com/DataDog/datadog-agent/pkg/remoteconfig/state|v0.46.0-rc.4|间接依赖|go|
|github.com/googleapis/gax-go/v2|v2.12.0|间接依赖|go|
|github.com/manifoldco/promptui|v0.9.0|直接依赖|go|
|github.com/gorilla/mux|v1.8.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/feature/ec2/imds|v1.13.7|间接依赖|go|
|github.com/emicklei/go-restful/v3|v3.10.2|间接依赖|go|
|cloud.google.com/go/iam|v1.1.1|间接依赖|go|
|github.com/aws/smithy-go|v1.14.0|间接依赖|go|
|github.com/alibabacloud-go/debug|v0.0.0-20190504072949-9472017b5c68|间接依赖|go|
|github.com/Azure/go-autorest|v14.2.0+incompatible|间接依赖|go|
|github.com/Azure/go-autorest/autorest/azure/auth|v0.5.12|间接依赖|go|
|go.opentelemetry.io/otel|v1.16.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ecrpublic|v1.12.0|间接依赖|go|
|github.com/sassoftware/relic|v7.2.1+incompatible|间接依赖|go|
|gopkg.in/DataDog/dd-trace-go.v1|v1.53.0|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/internal|v1.3.0|间接依赖|go|
|github.com/open-policy-agent/opa|v0.55.0|直接依赖|go|
|cloud.google.com/go/compute/metadata|v0.2.3|间接依赖|go|
|github.com/ProtonMail/go-crypto|v0.0.0-20230518184743-7afd39499903|间接依赖|go|
|github.com/go-openapi/validate|v0.22.1|间接依赖|go|
|github.com/hashicorp/go-sockaddr|v1.0.2|间接依赖|go|
|github.com/Azure/go-autorest/autorest|v0.11.29|间接依赖|go|
|github.com/secure-systems-lab/go-securesystemslib|v0.7.0|直接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|github.com/containerd/stargz-snapshotter/estargz|v0.14.3|间接依赖|go|
|github.com/coreos/go-oidc/v3|v3.6.0|间接依赖|go|
|github.com/go-playground/locales|v0.14.1|间接依赖|go|
|github.com/subosito/gotenv|v1.4.2|间接依赖|go|
|github.com/pkg/browser|v0.0.0-20210911075715-681adbf594b8|间接依赖|go|
|github.com/go-openapi/loads|v0.21.2|间接依赖|go|
|github.com/yashtewari/glob-intersection|v0.2.0|间接依赖|go|
|github.com/awslabs/amazon-ecr-credential-helper/ecr-login|v0.0.0-20220228164355-396b2034c795|直接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|github.com/golang-jwt/jwt/v4|v4.5.0|间接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.3|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/DataDog/go-tuf|v0.3.0--fix-localmeta-fork|间接依赖|go|
|github.com/Azure/go-autorest/autorest/adal|v0.9.22|间接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.6|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|go.step.sm/crypto|v0.35.0|直接依赖|go|
|golang.org/x/tools|v0.9.3|间接依赖|go|
|github.com/tchap/go-patricia/v2|v2.3.1|间接依赖|go|
|github.com/chzyer/readline|v1.5.1|间接依赖|go|
|github.com/alibabacloud-go/alibabacloud-gateway-spi|v0.0.4|间接依赖|go|
|github.com/dustin/go-humanize|v1.0.1|间接依赖|go|
|github.com/agnivade/levenshtein|v1.1.1|间接依赖|go|
|github.com/docker/distribution|v2.8.2+incompatible|间接依赖|go|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|github.com/tjfoc/gmsm|v1.3.2|间接依赖|go|
|github.com/cloudflare/circl|v1.3.3|间接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0|间接依赖|go|
|github.com/rcrowley/go-metrics|v0.0.0-20201227073835-cf1acfcdf475|间接依赖|go|
|github.com/google/s2a-go|v0.1.5|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|github.com/Azure/go-autorest/autorest/date|v0.3.0|间接依赖|go|
|github.com/withfig/autocomplete-tools/integrations/cobra|v1.2.1|直接依赖|go|
|k8s.io/client-go|v0.27.3|直接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.2|间接依赖|go|
|golang.org/x/sync|v0.3.0|直接依赖|go|
|github.com/spf13/jwalterweatherman|v1.1.0|间接依赖|go|
|github.com/go-openapi/runtime|v0.26.0|直接依赖|go|
|github.com/oklog/ulid|v1.3.1|间接依赖|go|
|golang.org/x/text|v0.12.0|间接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|github.com/ryanuber/go-glob|v1.0.0|间接依赖|go|
|github.com/google/gnostic|v0.5.7-v3refs|间接依赖|go|
|github.com/skratchdot/open-golang|v0.0.0-20200116055534-eef842397966|间接依赖|go|
|github.com/leodido/go-urn|v1.2.4|间接依赖|go|
|github.com/alibabacloud-go/tea-xml|v1.1.2|间接依赖|go|
|github.com/xanzy/go-gitlab|v0.90.0|直接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|gopkg.in/square/go-jose.v2|v2.6.0|间接依赖|go|
|github.com/docker/docker|v24.0.0+incompatible|间接依赖|go|
|github.com/sigstore/sigstore|v1.7.2|直接依赖|go|
|github.com/go-playground/universal-translator|v0.18.1|间接依赖|go|
|github.com/hashicorp/go-multierror|v1.1.1|间接依赖|go|
|github.com/OneOfOne/xxhash|v1.2.8|间接依赖|go|
|github.com/hashicorp/vault/api|v1.9.2|间接依赖|go|
|github.com/pelletier/go-toml/v2|v2.0.8|间接依赖|go|
|github.com/go-jose/go-jose/v3|v3.0.0|间接依赖|go|
|github.com/rs/cors|v1.9.0|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|github.com/google/certificate-transparency-go|v1.1.6|直接依赖|go|
|github.com/go-openapi/spec|v0.20.9|间接依赖|go|
|github.com/DataDog/go-libddwaf|v1.4.1|间接依赖|go|
|github.com/jellydator/ttlcache/v3|v3.0.1|间接依赖|go|
|github.com/DataDog/sketches-go|v1.2.1|间接依赖|go|
|inet.af/netaddr|v0.0.0-20220811202034-502d2d690317|间接依赖|go|
|github.com/prometheus/common|v0.44.0|间接依赖|go|
|github.com/alibabacloud-go/tea|v1.1.18|间接依赖|go|
|github.com/prometheus/procfs|v0.10.1|间接依赖|go|
|cloud.google.com/go/compute|v1.23.0|间接依赖|go|
|github.com/depcheck-test/depcheck-test|v0.0.0-20220607135614-199033aaa936|直接依赖|go|
|github.com/ghodss/yaml|v1.0.0|间接依赖|go|
|github.com/magiconair/properties|v1.8.7|间接依赖|go|
|github.com/thales-e-security/pool|v0.0.2|间接依赖|go|
|github.com/googleapis/enterprise-certificate-proxy|v0.2.5|间接依赖|go|
|sigs.k8s.io/release-utils|v0.7.4|直接依赖|go|
|github.com/outcaste-io/ristretto|v0.2.1|间接依赖|go|
|github.com/sigstore/sigstore/pkg/signature/kms/aws|v1.7.2|直接依赖|go|
|golang.org/x/xerrors|v0.0.0-20220907171357-04be3eba64a2|间接依赖|go|
|go.opencensus.io|v0.24.0|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20230501164219-8b0f38b5fd1f|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/titanous/rocacheck|v0.0.0-20171023193734-afe73141d399|间接依赖|go|
|github.com/AzureAD/microsoft-authentication-library-for-go|v1.0.0|间接依赖|go|
|github.com/spaolacci/murmur3|v1.1.0|间接依赖|go|
|github.com/letsencrypt/boulder|v0.0.0-20221109233200-85aa52084eaf|间接依赖|go|
|github.com/puzpuzpuz/xsync/v2|v2.4.1|间接依赖|go|
|sigs.k8s.io/yaml|v1.3.0|间接依赖|go|
|github.com/Azure/go-ansiterm|v0.0.0-20210617225240-d185dfc1b5a1|间接依赖|go|
|google.golang.org/protobuf|v1.31.0|间接依赖|go|
|github.com/emicklei/proto|v1.10.0|间接依赖|go|
|github.com/aws/aws-sdk-go|v1.44.318|间接依赖|go|
|github.com/xeipuuv/gojsonpointer|v0.0.0-20190905194746-02993c407bfb|间接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.0|间接依赖|go|
|github.com/lestrrat-go/iter|v1.0.2|间接依赖|go|
|github.com/kelseyhightower/envconfig|v1.4.0|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)