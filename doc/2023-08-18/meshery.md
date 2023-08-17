# meshery/meshery安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692237497068572672.svg)](https://www.murphysec.com/console/report/1691512587965718528/1692237497068572672)

仓库描述：Meshery, the cloud native manager

仓库地址：[https://github.com/meshery/meshery](https://github.com/meshery/meshery)

| star：2843 | watch：40 | fork：1123 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-18 02:07:37 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-18 02:13:53 | 组件总数：464 | 漏洞总数：5 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Go-Yaml 安全漏洞|反序列化|[MPS-2022-8233](https://www.oscs1024.com/hd/MPS-2022-8233)|CVE-2022-28948|高危|
|Google Go 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2022-9049](https://www.oscs1024.com/hd/MPS-2022-9049)|CVE-2022-29526|中危|
|Moby 安全漏洞||[MPS-2023-8823](https://www.oscs1024.com/hd/MPS-2023-8823)|CVE-2023-28840|高危|
|Moby 安全漏洞||[MPS-2023-8824](https://www.oscs1024.com/hd/MPS-2023-8824)|CVE-2023-28841|中危|
|Moby 安全漏洞|对异常条件的处理不恰当|[MPS-2023-8826](https://www.oscs1024.com/hd/MPS-2023-8826)|CVE-2023-28842|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|gopkg.in/yaml.v3|v3.0.0-20210107192922-496545a6307b|3.0.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|github.com/docker/docker|v20.10.23+incompatible|23.0.3|直接依赖|建议修复|C:0|H:1|M:2|L:0|
|golang.org/x/sys|v0.0.0-20220722155257-8c9f86f7a55f|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|60|Low|
|BSD-2-Clause|15|Low|
|Apache-2.0|141|Low|
|自定义许可证|6|Low|
|MIT|124|Low|
|CC-BY-SA-4.0|2|Medium|
|ISC|3|Low|
|MPL-2.0|4|Low|
|BSD-2-Clause-Views|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/docker/go|v1.5.1-1.0.20160303222718-d30aec9fd63c|间接依赖|go|
|github.com/go-redis/redis/v8|v8.11.5|间接依赖|go|
|jekyll-theme-leap-day|0.2.0|间接依赖|bundler|
|github.com/layer5io/nighthawk-go|v1.0.6|直接依赖|go|
|jekyll-theme-primer|0.6.0|间接依赖|bundler|
|jekyll-default-layout|0.1.4|间接依赖|bundler|
|execjs|2.8.1|间接依赖|bundler|
|minima|2.5.1|间接依赖|bundler|
|github.com/gosuri/uitable|v0.0.4|间接依赖|go|
|github.com/docker/go-metrics|v0.0.1|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/sirupsen/logrus|v1.8.1|直接依赖|go|
|jekyll-redirect-from|0.16.0|间接依赖|bundler|
|github.com/stretchr/objx|v0.5.0|间接依赖|go|
|jekyll-theme-modernist|0.2.0|间接依赖|bundler|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|github.com/flynn/go-shlex|v0.0.0-20150515145356-3f9db97f8568|间接依赖|go|
|github.com/sergi/go-diff|v1.2.0|间接依赖|go|
|github.com/containerd/containerd|v1.6.19|间接依赖|go|
|github.com/jackc/pgx/v5|v5.2.0|间接依赖|go|
|google.golang.org/grpc|v1.56.1|间接依赖|go|
|gopkg.in/warnings.v0|v0.1.2|间接依赖|go|
|github.com/gobwas/glob|v0.2.3|间接依赖|go|
|github.com/asaskevich/govalidator|v0.0.0-20200907205600-7a23bdc65eef|直接依赖|go|
|jekyll-watch|2.2.1|间接依赖|bundler|
|activemodel|7.0.5|间接依赖|bundler|
|racc|1.7.1|间接依赖|bundler|
|github.com/vmihailenco/tagparser/v2|v2.0.0|间接依赖|go|
|github.com/prometheus/client_golang|v1.15.0|间接依赖|go|
|github.com/subosito/gotenv|v1.4.2|间接依赖|go|
|jekyll-readme-index|0.3.0|间接依赖|bundler|
|github.com/olekukonko/tablewriter|v0.0.5|直接依赖|go|
|gorm.io/gorm|v1.23.7|间接依赖|go|
|dnsruby|1.70.0|间接依赖|bundler|
|github.com/stretchr/testify|v1.7.0|间接依赖|go|
|golang.org/x/sys|v0.10.0|间接依赖|go|
|websocket-extensions|0.1.5|间接依赖|bundler|
|github.com/emirpasic/gods|v1.18.1|间接依赖|go|
|helm.sh/helm/v3|v3.11.1|间接依赖|go|
|github.com/buger/jsonparser|v1.1.1|间接依赖|go|
|fortio.org/log|v1.10.0|间接依赖|go|
|jekyll-relative-links|0.6.1|间接依赖|bundler|
|jekyll-theme-time-machine|0.2.0|间接依赖|bundler|
|jekyll-sass-converter|1.5.2|间接依赖|bundler|
|github.com/hashicorp/golang-lru|v0.5.4|间接依赖|go|
|github.com/vmihailenco/taskq/v3|v3.2.9|直接依赖|go|
|github.com/docker/docker|v20.10.23+incompatible|直接依赖|go|
|rouge|3.26.0|间接依赖|bundler|
|github.com/mitchellh/reflectwalk|v1.0.2|间接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|github.com/layer5io/meshkit|v0.6.52|直接依赖|go|
|ruby2_keywords|0.0.5|间接依赖|bundler|
|websocket-driver|0.7.5|间接依赖|bundler|
|github.com/fsouza/go-dockerclient|v1.9.3|间接依赖|go|
|github.com/prometheus/client_model|v0.4.0|间接依赖|go|
|jekyll-include-cache|0.2.1|间接依赖|bundler|
|github.com/bsm/redislock|v0.7.2|间接依赖|go|
|github.com/google/btree|v1.0.1|间接依赖|go|
|github.com/nats-io/nkeys|v0.3.0|间接依赖|go|
|golang.org/x/term|v0.9.0|间接依赖|go|
|unicode-display_width|1.8.0|间接依赖|bundler|
|mail|2.8.1|间接依赖|bundler|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|github.com/moby/term|v0.0.0-20221205130635-1aeaba878587|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|golang.org/x/time|v0.3.0|间接依赖|go|
|github.com/fatih/camelcase|v1.0.0|间接依赖|go|
|github.com/theupdateframework/notary|v0.7.0|间接依赖|go|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|github.com/go-openapi/swag|v0.19.14|间接依赖|go|
|github.com/rubenv/sql-migrate|v1.2.0|间接依赖|go|
|github.com/spf13/cast|v1.5.1|间接依赖|go|
|github.com/fatih/structs|v1.1.0|间接依赖|go|
|github.com/ghodss/yaml|v1.0.0|直接依赖|go|
|octokit|4.25.1|间接依赖|bundler|
|github.com/mattn/go-isatty|v0.0.14|间接依赖|go|
|github.com/vektah/gqlparser/v2|v2.5.1|直接依赖|go|
|github.com/onsi/ginkgo/v2|v2.11.0|直接依赖|go|
|liquid|4.0.4|间接依赖|bundler|
|jekyll-theme-tactile|0.2.0|间接依赖|bundler|
|gorm.io/driver/sqlite|v1.3.1|间接依赖|go|
|github.com/go-stack/stack|v1.8.0|间接依赖|go|
|github.com/go-openapi/loads|v0.19.5|间接依赖|go|
|html-pipeline|2.14.3|间接依赖|bundler|
|github.com/jackc/pgservicefile|v0.0.0-20200714003250-2b9c44734f2b|间接依赖|go|
|github.com/layer5io/meshkit|v0.6.55|直接依赖|go|
|rails-dom-testing|2.0.3|间接依赖|bundler|
|github.com/xeipuuv/gojsonreference|v0.0.0-20180127040603-bd5ef7bd5415|间接依赖|go|
|terminal-table|1.8.0|间接依赖|bundler|
|github.com/opencontainers/image-spec|v1.1.0-rc2|间接依赖|go|
|gemoji|3.0.1|间接依赖|bundler|
|k8s.io/api|v0.26.0|间接依赖|go|
|golang.org/x/net|v0.11.0|间接依赖|go|
|method_source|1.0.0|间接依赖|bundler|
|gopkg.in/yaml.v3|v3.0.1|直接依赖|go|
|github.com/morikuni/aec|v1.0.0|间接依赖|go|
|github.com/go-openapi/errors|v0.19.8|间接依赖|go|
|k8s.io/component-base|v0.26.0|间接依赖|go|
|jekyll-commonmark-ghpages|0.4.0|间接依赖|bundler|
|golang.org/x/sys|v0.9.0|间接依赖|go|
|github.com/go-redis/redis_rate/v9|v9.1.2|间接依赖|go|
|github.com/mitchellh/copystructure|v1.2.0|间接依赖|go|
|listen|3.8.0|间接依赖|bundler|
|github.com/go-errors/errors|v1.0.1|间接依赖|go|
|github.com/Masterminds/sprig/v3|v3.2.3|间接依赖|go|
|github.com/go-openapi/analysis|v0.19.10|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|直接依赖|go|
|github.com/Masterminds/squirrel|v1.5.3|间接依赖|go|
|jekyll-theme-midnight|0.2.0|间接依赖|bundler|
|builder|3.2.4|间接依赖|bundler|
|github.com/Masterminds/goutils|v1.1.1|间接依赖|go|
|github.com/jinzhu/now|v1.1.4|间接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|sawyer|0.9.2|间接依赖|bundler|
|github.com/layer5io/gowrk2|v0.6.1|直接依赖|go|
|google.golang.org/api|v0.128.0|直接依赖|go|
|tzinfo|2.0.6|间接依赖|bundler|
|rails|7.0.5|间接依赖|bundler|
|go.mongodb.org/mongo-driver|v1.5.1|间接依赖|go|
|jekyll-theme-hacker|0.2.0|间接依赖|bundler|
|dartsass|1.49.8|间接依赖|bundler|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/BurntSushi/toml|v1.2.1|间接依赖|go|
|github.com/onsi/gomega|v1.27.8|直接依赖|go|
|github.com/mattn/go-colorable|v0.1.12|间接依赖|go|
|github.com/layer5io/service-mesh-performance|v0.6.1|直接依赖|go|
|jekyll-theme-dinky|0.2.0|间接依赖|bundler|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230530153820-e85fd2cbaebc|间接依赖|go|
|github.com/spf13/afero|v1.9.5|间接依赖|go|
|pathutil|0.16.2|间接依赖|bundler|
|github.com/prometheus/common|v0.42.0|间接依赖|go|
|github.com/docker/go-connections|v0.4.0|直接依赖|go|
|github.com/hashicorp/golang-lru/v2|v2.0.1|间接依赖|go|
|date|3.3.3|间接依赖|bundler|
|github.com/docker/go-units|v0.5.0|间接依赖|go|
|github.com/manifoldco/promptui|v0.9.0|直接依赖|go|
|github.com/google/shlex|v0.0.0-20191202100458-e7afc7fbc510|间接依赖|go|
|github.com/ProtonMail/go-crypto|v0.0.0-20210428141323-04723f9f07d7|间接依赖|go|
|github.com/deckarep/golang-set|v1.8.0|间接依赖|go|
|github.com/xeipuuv/gojsonpointer|v0.0.0-20190905194746-02993c407bfb|间接依赖|go|
|github.com/gregjones/httpcache|v0.0.0-20180305231024-9cad4c3443a7|间接依赖|go|
|golang.org/x/net|v0.13.0|间接依赖|go|
|k8s.io/apiextensions-apiserver|v0.26.0|间接依赖|go|
|github.com/jackc/pgpassfile|v1.0.0|间接依赖|go|
|github-pages|228|间接依赖|bundler|
|cuelang.org/go|v0.5.0|直接依赖|go|
|github.com/lann/ps|v0.0.0-20150810152359-62de8c46ede0|间接依赖|go|
|gorm.io/driver/postgres|v1.3.10|间接依赖|go|
|github.com/asaskevich/govalidator|v0.0.0-20200428143746-21a406dcc535|间接依赖|go|
|github.com/vmihailenco/msgpack/v5|v5.3.5|间接依赖|go|
|globalid|1.1.0|间接依赖|bundler|
|github.com/zmap/zcrypto|v0.0.0-20230422215203-9a665e1e9968|间接依赖|go|
|sigs.k8s.io/yaml|v1.3.0|间接依赖|go|
|github.com/pkg/browser|v0.0.0-20210706143420-7d21f8c997e2|直接依赖|go|
|github.com/cncf/xds/go|v0.0.0-20230607035331-e9ce68804cb4|间接依赖|go|
|rubyzip|2.3.2|间接依赖|bundler|
|em-websocket|0.5.3|间接依赖|bundler|
|github.com/googleapis/gax-go/v2|v2.10.0|间接依赖|go|
|golang.org/x/oauth2|v0.10.0|直接依赖|go|
|jekyll-mentions|1.6.0|间接依赖|bundler|
|github.com/jackc/pgx/v4|v4.17.2|间接依赖|go|
|github.com/go-gorp/gorp/v3|v3.0.2|间接依赖|go|
|golang.org/x/text|v0.10.0|间接依赖|go|
|tilt|2.2.0|间接依赖|bundler|
|jekyll-gist|1.5.0|间接依赖|bundler|
|gonum.org/v1/gonum|v0.12.0|直接依赖|go|
|github.com/evanphx/json-patch|v5.6.0+incompatible|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|gorm.io/driver/postgres|v1.4.6|间接依赖|go|
|escape_utils|1.3.0|间接依赖|bundler|
|github.com/jackc/pgservicefile|v0.0.0-20221227161230-091c0ba34f0a|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230110181048-76db0878b65f|间接依赖|go|
|erubi|1.12.0|间接依赖|bundler|
|ffi|1.15.5|间接依赖|bundler|
|github.com/google/pprof|v0.0.0-20210720184732-4bb14d4b1be1|间接依赖|go|
|github.com/containerd/cgroups|v1.1.0|间接依赖|go|
|github.com/Microsoft/hcsshim|v0.9.7|间接依赖|go|
|github.com/gorilla/websocket|v1.5.0|直接依赖|go|
|fortio.org/sets|v1.0.3|间接依赖|go|
|github.com/nats-io/nats.go|v1.22.1|间接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|golang.org/x/mod|v0.11.0|间接依赖|go|
|github.com/sirupsen/logrus|v1.9.3|直接依赖|go|
|http_parser.rb|0.8.0|间接依赖|bundler|
|github.com/prometheus/client_golang|v1.16.0|直接依赖|go|
|github.com/MakeNowJust/heredoc|v1.0.0|间接依赖|go|
|github.com/go-openapi/runtime|v0.19.15|直接依赖|go|
|k8s.io/api|v0.26.1|直接依赖|go|
|github.com/go-openapi/validate|v0.19.10|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|github.com/Azure/go-ansiterm|v0.0.0-20230124172434-306776ec8161|间接依赖|go|
|github.com/klauspost/compress|v1.15.11|间接依赖|go|
|github.com/xeipuuv/gojsonschema|v1.2.0|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.17|间接依赖|go|
|github.com/jackc/pgtype|v1.12.0|间接依赖|go|
|github.com/Microsoft/go-winio|v0.6.0|直接依赖|go|
|faraday-net_http|3.0.2|间接依赖|bundler|
|github.com/go-git/go-git/v5|v5.4.2|间接依赖|go|
|k8s.io/utils|v0.0.0-20221128185143-99ec85e7a448|间接依赖|go|
|public_suffix|4.0.7|间接依赖|bundler|
|jekyll-theme-architect|0.2.0|间接依赖|bundler|
|github.com/pelletier/go-toml/v2|v2.0.8|间接依赖|go|
|rb-fsevent|0.11.2|间接依赖|bundler|
|golang.org/x/tools|v0.1.12|间接依赖|go|
|github.com/chai2010/gettext-go|v1.0.2|间接依赖|go|
|golang.org/x/crypto|v0.11.0|间接依赖|go|
|nokogiri|1.15.2-x86_64-linux|间接依赖|bundler|
|github.com/cyphar/filepath-securejoin|v0.2.3|间接依赖|go|
|github.com/russross/blackfriday/v2|v2.1.0|间接依赖|go|
|golang.org/x/oauth2|v0.5.0|间接依赖|go|
|rexml|3.2.5|间接依赖|bundler|
|github.com/openshift/api|v3.9.0+incompatible|间接依赖|go|
|go.opencensus.io|v0.24.0|间接依赖|go|
|github.com/google/uuid|v1.3.0|直接依赖|go|
|go.starlark.net|v0.0.0-20200306205701-8dd3e2ee1dd5|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|jekyll-coffeescript|1.1.1|间接依赖|bundler|
|fortio.org/version|v1.0.2|间接依赖|go|
|github.com/cockroachdb/apd/v2|v2.0.2|间接依赖|go|
|coffee-script-source|1.11.1|间接依赖|bundler|
|github.com/dgryski/go-rendezvous|v0.0.0-20200823014737-9f7001d12a5f|间接依赖|go|
|github.com/exponent-io/jsonpath|v0.0.0-20151013193312-d6023ce2651d|间接依赖|go|
|github.com/gosimple/slug|v1.12.0|直接依赖|go|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|sigs.k8s.io/controller-runtime|v0.13.0|直接依赖|go|
|github.com/spf13/viper|v1.16.0|直接依赖|go|
|github.com/liggitt/tabwriter|v0.0.0-20181228230101-89fcab3d43de|间接依赖|go|
|google.golang.org/protobuf|v1.30.0|间接依赖|go|
|github.com/mailru/easyjson|v0.7.6|间接依赖|go|
|github.com/spf13/jwalterweatherman|v1.1.0|间接依赖|go|
|temple|0.10.2|间接依赖|bundler|
|github.com/jbenet/go-context|v0.0.0-20150711004518-d14ea06fba99|间接依赖|go|
|github.com/docker/docker|v20.10.24+incompatible|间接依赖|go|
|github.com/go-logr/logr|v1.2.4|间接依赖|go|
|github.com/zmap/zlint/v3|v3.4.1|间接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.3|间接依赖|go|
|actionmailbox|7.0.5|间接依赖|bundler|
|github.com/layer5io/meshery-operator|v0.6.10|直接依赖|go|
|github.com/google/s2a-go|v0.1.4|间接依赖|go|
|actionpack|7.0.5|间接依赖|bundler|
|github.com/go-task/slim-sprig|v0.0.0-20230315185526-52ccab3ef572|间接依赖|go|
|jekyll-seo-tag|2.8.0|间接依赖|bundler|
|github.com/briandowns/spinner|v1.19.0|直接依赖|go|
|github.com/docker/cli|v20.10.21+incompatible|直接依赖|go|
|golang.org/x/exp|v0.0.0-20230801115018-d63ba01acd4b|间接依赖|go|
|google.golang.org/grpc|v1.57.0|直接依赖|go|
|jekyll-avatar|0.7.0|间接依赖|bundler|
|github.com/docker/distribution|v2.8.2+incompatible|间接依赖|go|
|jekyll-theme-slate|0.2.0|间接依赖|bundler|
|jekyll-commonmark|1.4.0|间接依赖|bundler|
|github.com/jackc/pgio|v1.0.0|间接依赖|go|
|github.com/miekg/pkcs11|v1.1.1|间接依赖|go|
|haml|6.1.1|间接依赖|bundler|
|github.com/agnivade/levenshtein|v1.1.1|间接依赖|go|
|github.com/mitchellh/go-wordwrap|v1.0.1|间接依赖|go|
|github.com/dgryski/go-farm|v0.0.0-20200201041132-a6ae2369ad13|间接依赖|go|
|github.com/novln/docker-parser|v1.0.0|间接依赖|go|
|github.com/imdario/mergo|v0.3.15|间接依赖|go|
|github.com/rcrowley/go-metrics|v0.0.0-20200313005456-10cdbea86bc0|间接依赖|go|
|github.com/Azure/go-ansiterm|v0.0.0-20210617225240-d185dfc1b5a1|间接依赖|go|
|github.com/nsf/termbox-go|v1.1.1|直接依赖|go|
|golang.org/x/tools|v0.10.0|间接依赖|go|
|github.com/moby/sys/mountinfo|v0.6.2|间接依赖|go|
|github.com/chzyer/readline|v0.0.0-20180603132655-2972be24d48e|间接依赖|go|
|gorm.io/driver/sqlite|v1.4.4|间接依赖|go|
|actionview|7.0.5|间接依赖|bundler|
|github.com/go-openapi/jsonpointer|v0.19.5|间接依赖|go|
|k8s.io/apiextensions-apiserver|v0.26.1|直接依赖|go|
|sass-listen|4.0.0|间接依赖|bundler|
|github.com/google/btree|v1.1.2|间接依赖|go|
|mini_mime|1.1.2|间接依赖|bundler|
|google.golang.org/grpc|v1.54.0|间接依赖|go|
|jekyll-theme-minimal|0.2.0|间接依赖|bundler|
|github.com/mattn/go-runewidth|v0.0.9|间接依赖|go|
|golang.org/x/crypto|v0.5.0|间接依赖|go|
|github.com/golang/protobuf|v1.5.3|直接依赖|go|
|github.com/jinzhu/now|v1.1.5|间接依赖|go|
|golang.org/x/sync|v0.3.0|间接依赖|go|
|gorm.io/gorm|v1.25.2|直接依赖|go|
|github.com/lib/pq|v1.10.7|直接依赖|go|
|github.com/moby/sys/mount|v0.3.3|间接依赖|go|
|jekyll-paginate|1.1.0|间接依赖|bundler|
|net-smtp|0.3.3|间接依赖|bundler|
|github.com/OneOfOne/xxhash|v1.2.8|间接依赖|go|
|github.com/layer5io/meshkit|v0.6.49|间接依赖|go|
|github.com/tchap/go-patricia/v2|v2.3.1|间接依赖|go|
|mercenary|0.3.6|间接依赖|bundler|
|rack|2.2.7|间接依赖|bundler|
|github.com/nats-io/nuid|v1.0.1|间接依赖|go|
|jekyll-theme-cayman|0.2.0|间接依赖|bundler|
|github.com/gorilla/mux|v1.8.0|直接依赖|go|
|faraday|2.7.7|间接依赖|bundler|
|github.com/layer5io/meshsync|v0.6.11|直接依赖|go|
|forwardable-extended|2.6.0|间接依赖|bundler|
|github.com/spf13/cobra|v1.7.0|直接依赖|go|
|actionmailer|7.0.5|间接依赖|bundler|
|actiontext|7.0.5|间接依赖|bundler|
|jekyll|3.9.3|间接依赖|bundler|
|jekyll-theme-merlot|0.2.0|间接依赖|bundler|
|addressable|2.8.4|间接依赖|bundler|
|github.com/xlab/treeprint|v1.1.0|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20221012153701-172d655c2280|间接依赖|go|
|github.com/kevinburke/ssh_config|v1.2.0|间接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.1|间接依赖|go|
|github.com/qri-io/jsonschema|v0.2.1|直接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|bundler||间接依赖|bundler|
|k8s.io/kube-openapi|v0.0.0-20230109183929-3758b55a6596|间接依赖|go|
|golang.org/x/mod|v0.6.0-dev.0.20220419223038-86c51ed26bb4|间接依赖|go|
|github.com/moby/spdystream|v0.2.0|间接依赖|go|
|unf_ext|0.0.8.2|间接依赖|bundler|
|github.com/go-openapi/spec|v0.19.8|间接依赖|go|
|k8s.io/client-go|v0.26.0|间接依赖|go|
|k8s.io/apiserver|v0.26.1|间接依赖|go|
|github.com/google/gnostic|v0.5.7-v3refs|间接依赖|go|
|golang.org/x/text|v0.11.0|直接依赖|go|
|github.com/capnm/sysinfo|v0.0.0-20130621111458-5909a53897f3|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0|间接依赖|go|
|golang.org/x/text|v0.9.0|间接依赖|go|
|github.com/googleapis/enterprise-certificate-proxy|v0.2.4|间接依赖|go|
|github.com/mattn/go-sqlite3|v1.14.15|间接依赖|go|
|net-imap|0.3.6|间接依赖|bundler|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/jackc/pgconn|v1.13.0|间接依赖|go|
|kramdown-parser-gfm|1.1.0|间接依赖|bundler|
|loofah|2.21.3|间接依赖|bundler|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|golang.org/x/oauth2|v0.9.0|直接依赖|go|
|rack-test|2.1.0|间接依赖|bundler|
|k8s.io/component-base|v0.26.1|间接依赖|go|
|activesupport|7.0.5|间接依赖|bundler|
|cloud.google.com/go/compute|v1.19.3|间接依赖|go|
|thor|1.2.2|间接依赖|bundler|
|github.com/99designs/gqlgen|v0.17.28|直接依赖|go|
|k8s.io/client-go|v0.26.1|直接依赖|go|
|github.com/mattn/go-runewidth|v0.0.13|间接依赖|go|
|ethon|0.16.0|间接依赖|bundler|
|github.com/klauspost/compress|v1.14.4|间接依赖|go|
|rake|13.0.6|间接依赖|bundler|
|activejob|7.0.5|间接依赖|bundler|
|github.com/golang-jwt/jwt|v3.2.2+incompatible|直接依赖|go|
|rb-inotify|0.10.1|间接依赖|bundler|
|oras.land/oras-go|v1.2.2|间接依赖|go|
|github.com/jackc/pgproto3/v2|v2.3.1|间接依赖|go|
|kramdown|2.3.2|间接依赖|bundler|
|github.com/open-policy-agent/opa|v0.52.0|间接依赖|go|
|k8s.io/apimachinery|v0.26.1|直接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|间接依赖|go|
|github.com/mpvl/unique|v0.0.0-20150818121801-cbe035fff7de|间接依赖|go|
|github-pages-health-check|1.17.9|间接依赖|bundler|
|github.com/envoyproxy/go-control-plane|v0.11.1|直接依赖|go|
|github.com/prometheus/procfs|v0.10.1|间接依赖|go|
|graphql|2.0.23|间接依赖|bundler|
|fortio.org/dflag|v1.5.3|间接依赖|go|
|github.com/prometheus/common|v0.44.0|直接依赖|go|
|coffee-script|2.4.1|间接依赖|bundler|
|github.com/jinzhu/copier|v0.3.5|直接依赖|go|
|jekyll-swiss|1.0.0|间接依赖|bundler|
|activestorage|7.0.5|间接依赖|bundler|
|github.com/yashtewari/glob-intersection|v0.1.0|间接依赖|go|
|zeitwerk|2.6.8|间接依赖|bundler|
|github.com/xanzy/ssh-agent|v0.3.3|间接依赖|go|
|github.com/spf13/cast|v1.5.0|间接依赖|go|
|nio4r|2.5.9|间接依赖|bundler|
|github.com/prometheus/client_model|v0.3.0|间接依赖|go|
|golang.org/x/net|v0.12.0|间接依赖|go|
|k8s.io/klog/v2|v2.80.1|间接依赖|go|
|github.com/monochromegane/go-gitignore|v0.0.0-20200626010858-205db1a8cc00|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|间接依赖|go|
|graphql-docs|4.0.0|间接依赖|bundler|
|sigs.k8s.io/kustomize/api|v0.12.1|间接依赖|go|
|github.com/go-openapi/strfmt|v0.19.5|直接依赖|go|
|minitest|5.18.1|间接依赖|bundler|
|github.com/lann/builder|v0.0.0-20180802200727-47ae307949d0|间接依赖|go|
|github.com/huandu/xstrings|v1.3.3|间接依赖|go|
|k8s.io/kubectl|v0.26.0|间接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.0|间接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230803162519-f966b187b2e5|间接依赖|go|
|github.com/jmoiron/sqlx|v1.3.5|间接依赖|go|
|net-protocol|0.2.1|间接依赖|bundler|
|google.golang.org/grpc|v1.55.0|间接依赖|go|
|github.com/Masterminds/semver/v3|v3.2.0|间接依赖|go|
|marcel|1.0.2|间接依赖|bundler|
|net-pop|0.1.2|间接依赖|bundler|
|commonmarker|0.23.10|间接依赖|bundler|
|github.com/shopspring/decimal|v1.2.0|间接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.0|间接依赖|go|
|github.com/go-git/gcfg|v1.5.0|间接依赖|go|
|github.com/gofrs/uuid|v4.0.0+incompatible|直接依赖|go|
|github.com/grafana-tools/sdk|v0.0.0-20220919052116-6562121319fc|直接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|simpleidn|0.2.1|间接依赖|bundler|
|actioncable|7.0.5|间接依赖|bundler|
|github.com/qri-io/jsonpointer|v0.1.1|间接依赖|go|
|github.com/peterbourgon/diskv|v2.0.1+incompatible|间接依赖|go|
|jekyll-remote-theme|0.4.3|间接依赖|bundler|
|activerecord|7.0.5|间接依赖|bundler|
|typhoeus|1.4.0|间接依赖|bundler|
|github.com/google/gofuzz|v1.2.0|间接依赖|go|
|extended-markdown-filter|0.7.0|间接依赖|bundler|
|jemoji|0.12.0|间接依赖|bundler|
|golang.org/x/sync|v0.1.0|间接依赖|go|
|github.com/go-openapi/swag|v0.22.3|间接依赖|go|
|sass|3.7.4|间接依赖|bundler|
|golang.org/x/term|v0.7.0|间接依赖|go|
|gopkg.in/ini.v1|v1.67.0|间接依赖|go|
|github.com/fatih/color|v1.13.0|间接依赖|go|
|github.com/moby/locker|v1.0.1|间接依赖|go|
|golang.org/x/net|v0.9.0|间接依赖|go|
|railties|7.0.5|间接依赖|bundler|
|rails-html-sanitizer|1.6.0|间接依赖|bundler|
|github.com/jackc/chunkreader/v2|v2.0.1|间接依赖|go|
|jekyll-titles-from-headings|0.5.3|间接依赖|bundler|
|github.com/rivo/uniseg|v0.2.0|间接依赖|go|
|github.com/jinzhu/inflection|v1.0.0|间接依赖|go|
|github.com/gosimple/unidecode|v1.0.1|间接依赖|go|
|github.com/docker/libcompose|v0.4.0|间接依赖|go|
|jekyll-optional-front-matter|0.3.2|间接依赖|bundler|
|github.com/magiconair/properties|v1.8.7|间接依赖|go|
|k8s.io/utils|v0.0.0-20221107191617-1a15be271d1d|间接依赖|go|
|github.com/jarcoal/httpmock|v1.3.0|直接依赖|go|
|github.com/gregjones/httpcache|v0.0.0-20190611155906-901d90724c79|间接依赖|go|
|crass|1.0.6|间接依赖|bundler|
|golang.org/x/sys|v0.7.0|间接依赖|go|
|fortio.org/fortio|v1.58.0|直接依赖|go|
|k8s.io/klog/v2|v2.90.0|间接依赖|go|
|github.com/prometheus/procfs|v0.9.0|间接依赖|go|
|colorator|1.1.0|间接依赖|bundler|
|github.com/docker/docker-credential-helpers|v0.7.0|间接依赖|go|
|github.com/go-errors/errors|v1.4.2|直接依赖|go|
|eventmachine|1.2.7|间接依赖|bundler|
|github.com/go-openapi/jsonpointer|v0.19.6|间接依赖|go|
|github.com/joho/godotenv|v1.4.0|间接依赖|go|
|github.com/fvbommel/sortorder|v1.0.1|间接依赖|go|
|google.golang.org/protobuf|v1.31.0|直接依赖|go|
|jekyll-github-metadata|2.13.0|间接依赖|bundler|
|github.com/kubernetes/kompose|v1.28.0|间接依赖|go|
|github.com/envoyproxy/protoc-gen-validate|v1.0.2|间接依赖|go|
|github.com/go-git/go-billy/v5|v5.4.0|间接依赖|go|
|github.com/sirupsen/logrus|v1.9.0|间接依赖|go|
|k8s.io/apiserver|v0.26.0|间接依赖|go|
|timeout|0.4.0|间接依赖|bundler|
|golang.org/x/crypto|v0.10.0|间接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|sigs.k8s.io/kustomize/kyaml|v0.13.9|间接依赖|go|
|github.com/emicklei/go-restful/v3|v3.9.0|间接依赖|go|
|i18n|1.14.1|间接依赖|bundler|
|jekyll-sitemap|1.4.0|间接依赖|bundler|
|unf|0.1.4|间接依赖|bundler|
|safe_yaml|1.0.5|间接依赖|bundler|
|golang.org/x/sync|v0.2.0|间接依赖|go|
|github.com/oklog/ulid|v1.3.1|间接依赖|go|
|golang.org/x/term|v0.10.0|间接依赖|go|
|concurrent-ruby|1.2.2|间接依赖|bundler|
|k8s.io/cli-runtime|v0.26.0|间接依赖|go|
|cloud.google.com/go/compute/metadata|v0.2.3|间接依赖|go|
|jekyll-feed|0.15.1|间接依赖|bundler|
|sigs.k8s.io/json|v0.0.0-20220713155537-f223a00ba0e2|间接依赖|go|
|github.com/opencontainers/runc|v1.1.5|间接依赖|go|
|golang.org/x/sys|v0.0.0-20220722155257-8c9f86f7a55f|间接依赖|go|
|github.com/acomagu/bufpipe|v1.0.3|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.0-20210107192922-496545a6307b|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)