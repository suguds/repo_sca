# mehdihadeli/go-ecommerce-microservices安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696223398785871872.svg)](https://www.murphysec.com/console/report/1695862539253800960/1696223398785871872)

仓库描述：🧺 A practical e-commerce microservices, built with golang, domain-driven design, cqrs, event sourcing, vertical slice architecture, event-driven architecture, and the latest technologies.

仓库地址：[https://github.com/mehdihadeli/go-ecommerce-microservices](https://github.com/mehdihadeli/go-ecommerce-microservices)

| star：530 | watch：13 | fork：42 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-28 02:09:23 | 许可证：MIT |
| 最近检测时间：2023-08-29 02:09:31 | 组件总数：235 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|go.uuid 不安全的随机性漏洞|使用具有密码学弱点缺陷的PRNG|[MPS-2021-7854](https://www.oscs1024.com/hd/MPS-2021-7854)|CVE-2021-3538|严重|
|fasthttp 安全漏洞|路径遍历|[MPS-2022-5051](https://www.oscs1024.com/hd/MPS-2022-5051)|CVE-2022-21221|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/satori/go.uuid|v1.2.0||直接依赖|建议修复|C:1|H:0|M:0|L:0|
|github.com/valyala/fasthttp|v1.27.0|1.34.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|29|Low|
|MIT|120|Low|
|Apache-2.0|72|Low|
|ISC|1|Low|
|MPL-2.0|3|Low|
|BSD-2-Clause|14|Low|
|CC-BY-SA-4.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|golang.org/x/tools|v0.7.0|间接依赖|go|
|github.com/brianvoe/gofakeit/v6|v6.21.0|直接依赖|go|
|github.com/xdg-go/pbkdf2|v1.0.0|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/prometheus/common|v0.42.0|间接依赖|go|
|github.com/hashicorp/go-multierror|v1.1.1|间接依赖|go|
|github.com/spf13/afero|v1.9.5|间接依赖|go|
|github.com/dgryski/go-rendezvous|v0.0.0-20200823014737-9f7001d12a5f|间接依赖|go|
|github.com/yudai/golcs|v0.0.0-20170316035057-ecda9a501e82|间接依赖|go|
|github.com/goccy/go-reflect|v1.2.0|直接依赖|go|
|github.com/caarlos0/env/v8|v8.0.0|直接依赖|go|
|github.com/satori/go.uuid|v1.2.0|直接依赖|go|
|github.com/youmark/pkcs8|v0.0.0-20181117223130-1be2e3e5546d|间接依赖|go|
|github.com/spf13/cobra|v1.7.0|直接依赖|go|
|github.com/jackc/pgservicefile|v0.0.0-20221227161230-091c0ba34f0a|间接依赖|go|
|github.com/fatih/structs|v1.0.0|间接依赖|go|
|gorm.io/driver/postgres|v1.5.2|直接依赖|go|
|github.com/prometheus/procfs|v0.9.0|间接依赖|go|
|github.com/xeipuuv/gojsonreference|v0.0.0-20180127040603-bd5ef7bd5415|间接依赖|go|
|github.com/Azure/go-ansiterm|v0.0.0-20210617225240-d185dfc1b5a1|间接依赖|go|
|gopkg.in/khaiql/dbcleaner.v2|v2.3.0|直接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|github.com/spf13/cast|v1.5.1|间接依赖|go|
|github.com/rabbitmq/amqp091-go|v1.8.1|直接依赖|go|
|github.com/labstack/echo/v4|v4.10.2|直接依赖|go|
|github.com/go-openapi/swag|v0.21.1|间接依赖|go|
|github.com/Nvveen/Gotty|v0.0.0-20120604004816-cd527374f1e5|间接依赖|go|
|github.com/alexflint/go-filemutex|v1.1.0|间接依赖|go|
|github.com/sergi/go-diff|v1.0.0|间接依赖|go|
|github.com/onsi/gomega|v1.27.6|间接依赖|go|
|github.com/google/uuid|v1.3.0|间接依赖|go|
|github.com/imkira/go-interpol|v1.0.0|间接依赖|go|
|github.com/mcuadros/go-defaults|v1.2.0|直接依赖|go|
|github.com/leodido/go-urn|v1.2.4|间接依赖|go|
|github.com/jmoiron/sqlx|v1.3.5|直接依赖|go|
|gopkg.in/ini.v1|v1.51.0|间接依赖|go|
|github.com/uptrace/bun/driver/pgdriver|v1.1.14|直接依赖|go|
|go.uber.org/atomic|v1.10.0|间接依赖|go|
|github.com/doug-martin/goqu/v9|v9.18.0|直接依赖|go|
|github.com/sirupsen/logrus|v1.9.2|直接依赖|go|
|github.com/nolleh/caption_json_formatter|v0.2.2|直接依赖|go|
|github.com/xeipuuv/gojsonpointer|v0.0.0-20190905194746-02993c407bfb|间接依赖|go|
|github.com/jackc/pgx/v5|v5.3.1|间接依赖|go|
|github.com/swaggo/swag|v1.16.1|直接依赖|go|
|github.com/testcontainers/testcontainers-go|v0.19.0|直接依赖|go|
|github.com/prometheus/client_model|v0.4.0|间接依赖|go|
|github.com/brianvoe/gofakeit/v6|v6.19.0|直接依赖|go|
|go.opentelemetry.io/otel/trace|v1.16.0|直接依赖|go|
|github.com/brianvoe/gofakeit/v6|v6.18.0|直接依赖|go|
|github.com/gobwas/glob|v0.2.3|间接依赖|go|
|github.com/mitchellh/go-wordwrap|v1.0.1|间接依赖|go|
|github.com/gavv/httpexpect/v2|v2.3.1|直接依赖|go|
|github.com/go-logr/logr|v1.2.4|间接依赖|go|
|github.com/opencontainers/image-spec|v1.1.0-rc4|间接依赖|go|
|github.com/containerd/continuity|v0.4.1|间接依赖|go|
|github.com/golang/snappy|v0.0.4|间接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/spf13/afero|v1.6.0|间接依赖|go|
|gorm.io/gorm|v1.25.1|直接依赖|go|
|go.opentelemetry.io/otel/sdk|v1.16.0|直接依赖|go|
|github.com/prometheus/client_golang|v1.15.1|直接依赖|go|
|github.com/docker/go-units|v0.5.0|间接依赖|go|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|go.uber.org/zap|v1.24.0|直接依赖|go|
|github.com/yalp/jsonpath|v0.0.0-20180802001716-5cc68e5049a0|间接依赖|go|
|moul.io/http2curl/v2|v2.3.0|间接依赖|go|
|go.opentelemetry.io/otel/exporters/jaeger|v1.16.0|直接依赖|go|
|github.com/mehdihadeli/go-ecommerce-microservices/internal/pkg|v0.0.0-00010101000000-000000000000|直接依赖|go|
|github.com/go-resty/resty/v2|v2.7.0|直接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|go.opentelemetry.io/otel/sdk/metric|v0.39.0|直接依赖|go|
|github.com/go-playground/locales|v0.14.1|间接依赖|go|
|github.com/xeipuuv/gojsonpointer|v0.0.0-20180127040702-4e3ac2762d5f|间接依赖|go|
|github.com/go-openapi/jsonreference|v0.19.6|间接依赖|go|
|dario.cat/mergo|v1.0.0|间接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|github.com/phayes/freeport|v0.0.0-20220201140144-74d24b5ae9f5|直接依赖|go|
|github.com/docker/distribution|v2.8.2+incompatible|间接依赖|go|
|github.com/grpc-ecosystem/go-grpc-middleware|v1.4.0|直接依赖|go|
|github.com/cpuguy83/dockercfg|v0.3.1|间接依赖|go|
|github.com/go-playground/validator|v9.31.0+incompatible|直接依赖|go|
|github.com/spf13/cast|v1.3.0|间接依赖|go|
|github.com/subosito/gotenv|v1.2.0|间接依赖|go|
|go.opentelemetry.io/contrib/propagators/ot|v1.17.0|直接依赖|go|
|github.com/PuerkitoBio/urlesc|v0.0.0-20170810143723-de5bf2ad4578|间接依赖|go|
|github.com/xeipuuv/gojsonschema|v1.2.0|间接依赖|go|
|github.com/swaggo/echo-swagger|v1.3.3|直接依赖|go|
|github.com/vmihailenco/tagparser/v2|v2.0.0|间接依赖|go|
|github.com/spf13/jwalterweatherman|v1.0.0|间接依赖|go|
|github.com/Microsoft/go-winio|v0.6.1|间接依赖|go|
|github.com/imdario/mergo|v0.3.13|间接依赖|go|
|github.com/goccy/go-json|v0.10.2|直接依赖|go|
|github.com/containerd/containerd|v1.7.3|间接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0|间接依赖|go|
|github.com/spf13/jwalterweatherman|v1.1.0|间接依赖|go|
|github.com/cenkalti/backoff/v4|v4.2.1|间接依赖|go|
|github.com/fatih/color|v1.13.0|间接依赖|go|
|github.com/moby/patternmatcher|v0.5.0|间接依赖|go|
|github.com/google/go-querystring|v1.1.0|间接依赖|go|
|github.com/docker/cli|v20.10.17+incompatible|间接依赖|go|
|github.com/solsw/generichelper|v0.4.0|间接依赖|go|
|golang.org/x/sys|v0.8.0|间接依赖|go|
|github.com/klauspost/compress|v1.16.5|间接依赖|go|
|golang.org/x/time|v0.3.0|间接依赖|go|
|github.com/spf13/viper|v1.16.0|直接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|github.com/xdg-go/stringprep|v1.0.3|间接依赖|go|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|go.opentelemetry.io/otel/exporters/prometheus|v0.39.0|直接依赖|go|
|github.com/avast/retry-go|v3.0.0+incompatible|直接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/solsw/collate|v0.1.0|间接依赖|go|
|go.opentelemetry.io/otel/exporters/stdout/stdouttrace|v1.16.0|直接依赖|go|
|github.com/valyala/fasthttp|v1.34.0|间接依赖|go|
|github.com/gavv/httpexpect/v2|v2.15.0|直接依赖|go|
|github.com/ahmetb/go-linq/v3|v3.2.0|直接依赖|go|
|github.com/uptrace/bun/dialect/pgdialect|v1.1.14|直接依赖|go|
|google.golang.org/grpc|v1.57.0|直接依赖|go|
|github.com/inconshreveable/mousetrap|v1.0.0|间接依赖|go|
|golang.org/x/sync|v0.1.0|间接依赖|go|
|github.com/moby/sys/sequential|v0.5.0|间接依赖|go|
|go.opentelemetry.io/otel/exporters/zipkin|v1.16.0|直接依赖|go|
|github.com/sanity-io/litter|v1.5.5|间接依赖|go|
|github.com/jackc/pgx/v4|v4.18.1|直接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/golang-migrate/migrate/v4|v4.15.2|直接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230525234030-28d5490b6b19|间接依赖|go|
|github.com/ory/dockertest/v3|v3.10.0|直接依赖|go|
|github.com/docker/docker|v24.0.5+incompatible|间接依赖|go|
|github.com/xdg-go/scram|v1.1.1|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|github.com/go-faster/errors|v0.6.1|间接依赖|go|
|go.opentelemetry.io/otel|v1.16.0|直接依赖|go|
|golang.org/x/net|v0.10.0|间接依赖|go|
|github.com/KyleBanks/depth|v1.2.1|间接依赖|go|
|github.com/opencontainers/runc|v1.1.5|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|github.com/subosito/gotenv|v1.4.2|间接依赖|go|
|github.com/lann/builder|v0.0.0-20180802200727-47ae307949d0|间接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.5|间接依赖|go|
|golang.org/x/exp|v0.0.0-20230510235704-dd950f8aeaea|间接依赖|go|
|github.com/fatih/structs|v1.1.0|间接依赖|go|
|github.com/elastic/elastic-transport-go/v8|v8.2.0|间接依赖|go|
|github.com/segmentio/asm|v1.2.0|间接依赖|go|
|github.com/jinzhu/now|v1.1.5|间接依赖|go|
|github.com/jackc/pgio|v1.0.0|间接依赖|go|
|github.com/openzipkin/zipkin-go|v0.4.1|间接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.0|直接依赖|go|
|go.mongodb.org/mongo-driver|v1.11.6|直接依赖|go|
|github.com/kamva/mgm/v3|v3.5.0|直接依赖|go|
|github.com/pierrec/lz4/v4|v4.1.17|间接依赖|go|
|github.com/docker/go-connections|v0.4.0|直接依赖|go|
|github.com/mattn/go-isatty|v0.0.19|间接依赖|go|
|go.uber.org/fx|v1.20.0|直接依赖|go|
|go.uber.org/multierr|v1.11.0|间接依赖|go|
|mellium.im/sasl|v0.3.1|间接依赖|go|
|github.com/imkira/go-interpol|v1.1.0|间接依赖|go|
|github.com/TylerBrock/colorjson|v0.0.0-20200706003622-8a50f05110d2|直接依赖|go|
|github.com/valyala/fasthttp|v1.27.0|间接依赖|go|
|github.com/vmihailenco/msgpack/v5|v5.3.5|间接依赖|go|
|golang.org/x/crypto|v0.9.0|间接依赖|go|
|github.com/iancoleman/strcase|v0.2.0|直接依赖|go|
|github.com/jinzhu/inflection|v1.0.0|间接依赖|go|
|github.com/orlangure/gnomock|v0.28.0|直接依赖|go|
|emperror.dev/errors|v0.8.1|直接依赖|go|
|github.com/valyala/fasttemplate|v1.2.2|间接依赖|go|
|github.com/go-faster/city|v1.0.1|间接依赖|go|
|github.com/google/shlex|v0.0.0-20191202100458-e7afc7fbc510|间接依赖|go|
|github.com/Masterminds/squirrel|v1.5.4|直接依赖|go|
|moul.io/http2curl|v1.0.1-0.20190925090545-5cd742060b0e|间接依赖|go|
|github.com/swaggo/files|v0.0.0-20220610200504-28940afbdbfe|间接依赖|go|
|github.com/solsw/go2linq/v2|v2.5.3|直接依赖|go|
|go.uber.org/dig|v1.17.0|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|gopkg.in/ini.v1|v1.67.0|间接依赖|go|
|github.com/jackc/puddle|v1.3.0|间接依赖|go|
|github.com/golang-jwt/jwt|v3.2.2+incompatible|间接依赖|go|
|go.opentelemetry.io/otel/metric|v1.16.0|直接依赖|go|
|github.com/golang/mock|v1.6.0|间接依赖|go|
|github.com/labstack/gommon|v0.4.0|间接依赖|go|
|github.com/go-openapi/spec|v0.20.4|间接依赖|go|
|github.com/elastic/go-elasticsearch/v8|v8.8.0|直接依赖|go|
|github.com/jackc/pgpassfile|v1.0.0|间接依赖|go|
|golang.org/x/mod|v0.9.0|间接依赖|go|
|github.com/spf13/viper|v1.7.0|直接依赖|go|
|google.golang.org/protobuf|v1.30.0|直接依赖|go|
|github.com/pelletier/go-toml/v2|v2.0.8|间接依赖|go|
|github.com/hokaccha/go-prettyjson|v0.0.0-20211117102719-0474bc63780f|间接依赖|go|
|github.com/andybalholm/brotli|v1.0.5|间接依赖|go|
|github.com/spf13/cobra|v1.1.3|直接依赖|go|
|github.com/morikuni/aec|v1.0.0|间接依赖|go|
|github.com/mehdihadeli/go-mediatr|v1.1.10|直接依赖|go|
|github.com/jackc/pgtype|v1.14.0|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230526161137-0005af68ea54|间接依赖|go|
|github.com/go-playground/universal-translator|v0.18.1|间接依赖|go|
|github.com/gorilla/websocket|v1.4.2|间接依赖|go|
|github.com/ClickHouse/clickhouse-go/v2|v2.9.1|间接依赖|go|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|github.com/montanaflynn/stats|v0.0.0-20171201202039-1bf9dbcd8cbe|间接依赖|go|
|github.com/jackc/chunkreader/v2|v2.0.1|间接依赖|go|
|github.com/hashicorp/errwrap|v1.1.0|间接依赖|go|
|github.com/jackc/pgproto3/v2|v2.3.2|间接依赖|go|
|github.com/PuerkitoBio/purell|v1.1.1|间接依赖|go|
|github.com/valyala/bytebufferpool|v1.0.0|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|间接依赖|go|
|github.com/michaelklishin/rabbit-hole|v1.5.0|直接依赖|go|
|github.com/yudai/gojsondiff|v1.0.0|间接依赖|go|
|github.com/lann/ps|v0.0.0-20150810152359-62de8c46ede0|间接依赖|go|
|github.com/stretchr/testify|v1.8.4|直接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/google.golang.org/grpc/otelgrpc|v0.42.0|直接依赖|go|
|github.com/streadway/amqp|v1.1.0|间接依赖|go|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|github.com/go-testfixtures/testfixtures/v3|v3.9.0|直接依赖|go|
|github.com/gofrs/uuid|v4.4.0+incompatible|直接依赖|go|
|github.com/EventStore/EventStore-Client-Go|v1.0.2|直接依赖|go|
|github.com/tmthrgd/go-hex|v0.0.0-20190904060850-447a3041c3bc|间接依赖|go|
|github.com/go-redis/redis/v8|v8.11.5|直接依赖|go|
|github.com/moby/term|v0.5.0|间接依赖|go|
|github.com/khaiql/dbcleaner|v2.3.0+incompatible|间接依赖|go|
|github.com/araddon/dateparse|v0.0.0-20210429162001-6b43995a97de|直接依赖|go|
|github.com/paulmach/orb|v0.9.0|间接依赖|go|
|github.com/ajg/form|v1.5.1|间接依赖|go|
|github.com/joho/godotenv|v1.5.1|直接依赖|go|
|github.com/uptrace/bun|v1.1.14|直接依赖|go|
|github.com/lib/pq|v1.10.9|直接依赖|go|
|github.com/jackc/pgconn|v1.14.0|直接依赖|go|
|github.com/shopspring/decimal|v1.3.1|间接依赖|go|
|github.com/magiconair/properties|v1.8.7|间接依赖|go|
|github.com/youmark/pkcs8|v0.0.0-20201027041543-1326539a0a0a|间接依赖|go|
|github.com/pelletier/go-toml|v1.9.5|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|golang.org/x/text|v0.9.0|间接依赖|go|
|github.com/stretchr/objx|v0.5.0|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|github.com/ClickHouse/ch-go|v0.55.0|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)