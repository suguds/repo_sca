# argoproj-labs/argocd-autopilot安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694775239920480256.svg)](https://www.murphysec.com/console/report/1694775239777873920/1694775239920480256)

仓库描述：Argo-CD Autopilot

仓库地址：[https://github.com/argoproj-labs/argocd-autopilot](https://github.com/argoproj-labs/argocd-autopilot)

| star：681 | watch：11 | fork：107 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-07-26 00:01:26 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-25 02:14:44 | 组件总数：226 | 漏洞总数：3 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Kubernetes 输入验证错误漏洞|访问控制不当|[MPS-2019-15838](https://www.oscs1024.com/hd/MPS-2019-15838)|CVE-2019-11255|中危|
|Matthäus G. Chajdas pygments 代码问题漏洞|任意文件上传|[MPS-2022-57237](https://www.oscs1024.com/hd/MPS-2022-57237)|CVE-2022-40896|中危|
|Argo CD存在信息泄露漏洞|访问控制不当|[MPS-2022-57849](https://www.oscs1024.com/hd/MPS-2022-57849)|CVE-2022-41354|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|pygments|2.7.4|2.15.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|github.com/argoproj/argo-cd/v2|v2.5.9|2.6.7|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|k8s.io/kubernetes|v1.24.15||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|93|Low|
|MIT|75|Low|
|BSD-3-Clause|36|Low|
|BSD-2-Clause|13|Low|
|MPL-2.0|5|Low|
|Unlicense|2|Low|
|ISC|2|Low|
|CC-BY-SA-4.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/soheilhy/cmux|v0.1.5|间接依赖|go|
|cloud.google.com/go/compute|v1.19.0|间接依赖|go|
|github.com/emicklei/go-restful/v3|v3.8.0|间接依赖|go|
|github.com/go-git/go-git/v5|v5.4.2|直接依赖|go|
|github.com/valyala/fasttemplate|v1.2.1|间接依赖|go|
|github.com/Microsoft/go-winio|v0.4.17|间接依赖|go|
|github.com/PagerDuty/go-pagerduty|v1.5.0|间接依赖|go|
|github.com/pquerna/cachecontrol|v0.1.0|间接依赖|go|
|github.com/spf13/cobra|v1.5.0|直接依赖|go|
|gopkg.in/gomail.v2|v2.0.0-20160411212932-81ebce5c23df|间接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.5|间接依赖|go|
|github.com/google/gnostic|v0.5.7-v3refs|间接依赖|go|
|github.com/Masterminds/semver|v1.5.0|间接依赖|go|
|github.com/grpc-ecosystem/go-grpc-prometheus|v1.2.0|间接依赖|go|
|github.com/Azure/go-autorest/autorest|v0.11.18|间接依赖|go|
|github.com/Masterminds/sprig|v2.22.0+incompatible|间接依赖|go|
|github.com/vmihailenco/msgpack/v5|v5.3.4|间接依赖|go|
|github.com/moby/spdystream|v0.2.0|间接依赖|go|
|k8s.io/apiserver|v0.24.15|间接依赖|go|
|github.com/ProtonMail/go-crypto|v0.0.0-20210428141323-04723f9f07d7|间接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|gomodules.xyz/envconfig|v1.3.1-0.20190308184047-426f31af0d45|间接依赖|go|
|github.com/coreos/go-oidc|v2.2.1+incompatible|间接依赖|go|
|github.com/peterbourgon/diskv|v2.0.1+incompatible|间接依赖|go|
|golang.org/x/sys|v0.8.0|间接依赖|go|
|github.com/fvbommel/sortorder|v1.0.1|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|k8s.io/apimachinery|v0.24.15|直接依赖|go|
|github.com/mitchellh/go-wordwrap|v1.0.0|间接依赖|go|
|github.com/spf13/viper|v1.16.0|直接依赖|go|
|github.com/monochromegane/go-gitignore|v0.0.0-20200626010858-205db1a8cc00|间接依赖|go|
|github.com/Azure/go-autorest/tracing|v0.6.0|间接依赖|go|
|github.com/kballard/go-shellquote|v0.0.0-20180428030007-95032a82bc51|间接依赖|go|
|github.com/r3labs/diff|v1.1.0|间接依赖|go|
|github.com/go-git/go-billy/v5|v5.3.1|直接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|github.com/golang-jwt/jwt/v4|v4.2.0|间接依赖|go|
|github.com/itchyny/timefmt-go|v0.1.2|间接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|github.com/klauspost/compress|v1.13.5|间接依赖|go|
|github.com/google/shlex|v0.0.0-20191202100458-e7afc7fbc510|间接依赖|go|
|k8s.io/client-go|v0.24.15|直接依赖|go|
|github.com/mailru/easyjson|v0.7.6|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|github.com/gregdel/pushover|v1.1.0|间接依赖|go|
|github.com/google/go-querystring|v1.1.0|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.0.0|间接依赖|go|
|github.com/vmihailenco/go-tinylfu|v0.2.1|间接依赖|go|
|google.golang.org/grpc|v1.55.0|间接依赖|go|
|golang.org/x/oauth2|v0.7.0|间接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway|v1.16.0|间接依赖|go|
|github.com/gobwas/glob|v0.2.3|间接依赖|go|
|github.com/TomOnTime/utfutil|v0.0.0-20180511104225-09c41003ee1d|间接依赖|go|
|github.com/Azure/go-autorest/autorest/date|v0.3.0|间接依赖|go|
|github.com/fatih/color|v1.13.0|间接依赖|go|
|github.com/google/go-github/v43|v43.0.0|直接依赖|go|
|github.com/form3tech-oss/jwt-go|v3.2.3+incompatible|间接依赖|go|
|github.com/MakeNowJust/heredoc|v0.0.0-20170808103936-bb23615498cd|间接依赖|go|
|github.com/felixge/httpsnoop|v1.0.1|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.12|间接依赖|go|
|github.com/huandu/xstrings|v1.3.0|间接依赖|go|
|github.com/google/gofuzz|v1.1.0|间接依赖|go|
|github.com/go-redis/redis/v8|v8.11.3|间接依赖|go|
|github.com/go-openapi/runtime|v0.19.4|间接依赖|go|
|go.opentelemetry.io/otel/trace|v1.6.3|间接依赖|go|
|k8s.io/kube-aggregator|v0.24.2|间接依赖|go|
|github.com/spf13/afero|v1.9.5|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.14|间接依赖|go|
|k8s.io/component-base|v0.24.15|间接依赖|go|
|github.com/Azure/go-autorest/autorest/adal|v0.9.13|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|github.com/magiconair/properties|v1.8.7|间接依赖|go|
|github.com/pelletier/go-toml/v2|v2.0.8|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230410155749-daa745c078e1|间接依赖|go|
|golang.org/x/net|v0.10.0|间接依赖|go|
|github.com/ktrysmt/go-bitbucket|v0.9.55|直接依赖|go|
|github.com/gogits/go-gogs-client|v0.0.0-20190616193657-5a05380e4bc2|间接依赖|go|
|golang.org/x/text|v0.9.0|间接依赖|go|
|gopkg.in/go-playground/webhooks.v5|v5.11.0|间接依赖|go|
|pygments|2.7.4|间接依赖|pip|
|github.com/go-openapi/analysis|v0.19.5|间接依赖|go|
|github.com/hashicorp/go-retryablehttp|v0.7.2|间接依赖|go|
|github.com/google/go-github/v41|v41.0.0|间接依赖|go|
|k8s.io/cli-runtime|v0.24.15|直接依赖|go|
|go.mongodb.org/mongo-driver|v1.5.1|间接依赖|go|
|github.com/argoproj/notifications-engine|v0.3.1-0.20220812180936-4d8552b0775f|间接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.2-0.20181231171920-c182affec369|间接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|layeh.com/gopher-json|v0.0.0-20190114024228-97fed8db8427|间接依赖|go|
|github.com/russross/blackfriday/v2|v2.1.0|间接依赖|go|
|github.com/briandowns/spinner|v1.18.1|直接依赖|go|
|github.com/slack-go/slack|v0.10.1|间接依赖|go|
|github.com/go-openapi/swag|v0.19.14|间接依赖|go|
|github.com/google/btree|v1.0.1|间接依赖|go|
|k8s.io/kubectl|v0.24.15|直接依赖|go|
|github.com/bradleyfalzon/ghinstallation/v2|v2.0.4|间接依赖|go|
|github.com/opsgenie/opsgenie-go-sdk-v2|v1.0.5|间接依赖|go|
|github.com/liggitt/tabwriter|v0.0.0-20181228230101-89fcab3d43de|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|间接依赖|go|
|github.com/argoproj/gitops-engine|v0.7.1-0.20221004132320-98ccd3d43fd9|间接依赖|go|
|github.com/go-openapi/strfmt|v0.19.5|间接依赖|go|
|sigs.k8s.io/json|v0.0.0-20211208200746-9f7c6b3444d2|间接依赖|go|
|github.com/spf13/cast|v1.5.1|间接依赖|go|
|github.com/kevinburke/ssh_config|v0.0.0-20201106050909-4977a11b4351|间接依赖|go|
|github.com/prometheus/common|v0.32.1|间接依赖|go|
|github.com/xanzy/ssh-agent|v0.3.0|间接依赖|go|
|github.com/go-openapi/errors|v0.19.2|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/vmihailenco/tagparser/v2|v2.0.0|间接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0|间接依赖|go|
|github.com/PuerkitoBio/purell|v1.1.1|间接依赖|go|
|go.opentelemetry.io/otel|v1.6.3|间接依赖|go|
|github.com/go-openapi/spec|v0.19.5|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|golang.org/x/sync|v0.1.0|间接依赖|go|
|gopkg.in/ini.v1|v1.67.0|间接依赖|go|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|sigs.k8s.io/controller-runtime|v0.11.0|间接依赖|go|
|github.com/cpuguy83/go-md2man/v2|v2.0.2|间接依赖|go|
|sigs.k8s.io/yaml|v1.3.0|间接依赖|go|
|github.com/prometheus/client_golang|v1.12.1|间接依赖|go|
|sigs.k8s.io/kustomize/kyaml|v0.13.6|直接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.0|间接依赖|go|
|github.com/spf13/jwalterweatherman|v1.1.0|间接依赖|go|
|github.com/fatih/camelcase|v1.0.0|间接依赖|go|
|github.com/xlab/treeprint|v0.0.0-20181112141820-a009c3971eca|间接依赖|go|
|github.com/acomagu/bufpipe|v1.0.3|间接依赖|go|
|github.com/sirupsen/logrus|v1.8.1|直接依赖|go|
|github.com/mitchellh/reflectwalk|v1.0.0|间接依赖|go|
|github.com/go-errors/errors|v1.0.1|间接依赖|go|
|k8s.io/kubernetes|v1.24.15|间接依赖|go|
|github.com/RocketChat/Rocket.Chat.Go.SDK|v0.0.0-20210112200207-10ab4d695d60|间接依赖|go|
|gopkg.in/square/go-jose.v2|v2.6.0|间接依赖|go|
|github.com/patrickmn/go-cache|v2.1.0+incompatible|间接依赖|go|
|go.starlark.net|v0.0.0-20200306205701-8dd3e2ee1dd5|间接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/google.golang.org/grpc/otelgrpc|v0.31.0|间接依赖|go|
|github.com/casbin/casbin/v2|v2.39.1|间接依赖|go|
|golang.org/x/crypto|v0.9.0|间接依赖|go|
|github.com/microsoft/azure-devops-go-api/azuredevops|v1.0.0-b5|直接依赖|go|
|golang.org/x/exp|v0.0.0-20210901193431-a062eea981d2|间接依赖|go|
|github.com/go-openapi/validate|v0.19.8|间接依赖|go|
|github.com/itchyny/gojq|v0.12.3|间接依赖|go|
|github.com/grpc-ecosystem/go-grpc-middleware|v1.3.0|间接依赖|go|
|code.gitea.io/sdk/gitea|v0.15.1|直接依赖|go|
|github.com/valyala/bytebufferpool|v1.0.0|间接依赖|go|
|k8s.io/api|v0.24.15|直接依赖|go|
|github.com/go-telegram-bot-api/telegram-bot-api/v5|v5.4.0|间接依赖|go|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|github.com/argoproj/argo-cd/v2|v2.5.9|直接依赖|go|
|github.com/Azure/go-autorest/logger|v0.2.1|间接依赖|go|
|gopkg.in/warnings.v0|v0.1.2|间接依赖|go|
|sigs.k8s.io/kustomize/api|v0.11.4|直接依赖|go|
|github.com/go-git/gcfg|v1.5.0|间接依赖|go|
|github.com/go-logr/logr|v1.2.3|间接依赖|go|
|github.com/gorilla/handlers|v1.5.1|间接依赖|go|
|github.com/robfig/cron|v1.2.0|间接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.3|间接依赖|go|
|github.com/bombsimon/logrusr/v2|v2.0.1|间接依赖|go|
|github.com/antonmedv/expr|v1.8.9|间接依赖|go|
|github.com/Azure/go-ansiterm|v0.0.0-20210617225240-d185dfc1b5a1|间接依赖|go|
|github.com/mitchellh/copystructure|v1.0.0|间接依赖|go|
|github.com/alicebob/miniredis/v2|v2.14.2|间接依赖|go|
|github.com/moby/term|v0.0.0-20210619224110-3f7ff695adc6|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/chai2010/gettext-go|v0.0.0-20170215093142-bf70f2a70fb1|间接依赖|go|
|github.com/hashicorp/go-cleanhttp|v0.5.2|间接依赖|go|
|github.com/ghodss/yaml|v1.0.0|直接依赖|go|
|k8s.io/klog/v2|v2.70.1|间接依赖|go|
|github.com/whilp/git-urls|v0.0.0-20191001220047-6db9661140c0|间接依赖|go|
|github.com/jonboulle/clockwork|v0.2.2|间接依赖|go|
|github.com/gregjones/httpcache|v0.0.0-20190611155906-901d90724c79|间接依赖|go|
|github.com/stretchr/testify|v1.8.4|直接依赖|go|
|github.com/argoproj/pkg|v0.11.1-0.20211203175135-36c59d8fafe0|间接依赖|go|
|k8s.io/component-helpers|v0.24.15|间接依赖|go|
|k8s.io/utils|v0.0.0-20220210201930-3a6ce19ff2f9|间接依赖|go|
|github.com/sergi/go-diff|v1.1.0|间接依赖|go|
|github.com/google/go-jsonnet|v0.18.0|间接依赖|go|
|google.golang.org/protobuf|v1.30.0|间接依赖|go|
|github.com/Masterminds/semver/v3|v3.1.1|间接依赖|go|
|github.com/PuerkitoBio/urlesc|v0.0.0-20170810143723-de5bf2ad4578|间接依赖|go|
|gomodules.xyz/notify|v0.1.0|间接依赖|go|
|github.com/docker/distribution|v2.8.1+incompatible|间接依赖|go|
|github.com/go-openapi/jsonreference|v0.19.5|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|github.com/jbenet/go-context|v0.0.0-20150711004518-d14ea06fba99|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20220627174259-011e075b9cb8|间接依赖|go|
|github.com/rs/cors|v1.8.0|间接依赖|go|
|cloud.google.com/go/compute/metadata|v0.2.3|间接依赖|go|
|github.com/Azure/go-autorest|v14.2.0+incompatible|间接依赖|go|
|github.com/go-redis/cache/v8|v8.4.2|间接依赖|go|
|github.com/asaskevich/govalidator|v0.0.0-20190424111038-f61b66f89f4a|间接依赖|go|
|github.com/imdario/mergo|v0.3.12|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|间接依赖|go|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|github.com/russross/blackfriday|v1.5.2|间接依赖|go|
|github.com/alicebob/gopher-json|v0.0.0-20200520072559-a9ecdc9d1d3a|间接依赖|go|
|k8s.io/apiextensions-apiserver|v0.24.2|间接依赖|go|
|github.com/go-openapi/loads|v0.19.4|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/prometheus/client_model|v0.2.0|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/emirpasic/gods|v1.12.0|间接依赖|go|
|github.com/Knetic/govaluate|v3.0.1-0.20171022003610-9aa49832a739+incompatible|间接依赖|go|
|github.com/dustin/go-humanize|v1.0.0|间接依赖|go|
|github.com/Masterminds/goutils|v1.1.1|间接依赖|go|
|github.com/subosito/gotenv|v1.4.2|间接依赖|go|
|golang.org/x/term|v0.8.0|间接依赖|go|
|github.com/skratchdot/open-golang|v0.0.0-20160302144031-75fb7ed4208c|间接依赖|go|
|github.com/prometheus/procfs|v0.7.3|间接依赖|go|
|github.com/exponent-io/jsonpath|v0.0.0-20151013193312-d6023ce2651d|间接依赖|go|
|github.com/evanphx/json-patch|v4.12.0+incompatible|间接依赖|go|
|golang.org/x/time|v0.3.0|间接依赖|go|
|github.com/go-stack/stack|v1.8.1|间接依赖|go|
|github.com/hashicorp/go-version|v1.2.1|间接依赖|go|
|github.com/improbable-eng/grpc-web|v0.0.0-20181111100011-16092bd1d58a|间接依赖|go|
|github.com/xanzy/go-gitlab|v0.86.0|直接依赖|go|
|github.com/dgryski/go-rendezvous|v0.0.0-20200823014737-9f7001d12a5f|间接依赖|go|
|github.com/gorilla/websocket|v1.4.2|间接依赖|go|
|github.com/golang/mock|v1.6.0|直接依赖|go|
|github.com/yuin/gopher-lua|v0.0.0-20200816102855-ee81675732da|间接依赖|go|
|gopkg.in/alexcesaro/quotedprintable.v3|v3.0.0-20150716171945-2caba252f4dc|间接依赖|go|
|github.com/google/uuid|v1.3.0|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)