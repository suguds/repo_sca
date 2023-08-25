# determined-ai/determined安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695139048925327360.svg)](https://www.murphysec.com/console/report/1695139041157476352/1695139048925327360)

仓库描述：Determined is a deep-learning platform that simplifies distributed training, hyperparameter tuning, experiment tracking, and resource management. Works with PyTorch and TensorFlow.

仓库地址：[https://github.com/determined-ai/determined](https://github.com/determined-ai/determined)

| star：2432 | watch：76 | fork：316 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-26 02:18:40 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-26 02:22:33 | 组件总数：498 | 漏洞总数：6 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|NumPy 缓冲区错误漏洞|经典缓冲区溢出|[MPS-2021-25101](https://www.oscs1024.com/hd/MPS-2021-25101)|CVE-2021-33430|中危|
|NumPy 安全漏洞|不充分的比较|[MPS-2021-25631](https://www.oscs1024.com/hd/MPS-2021-25631)|CVE-2021-34141|中危|
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|
|NumPy 安全漏洞|经典缓冲区溢出|[MPS-2021-32279](https://www.oscs1024.com/hd/MPS-2021-32279)|CVE-2021-41496|中危|
|Python 安全漏洞|ReDoS|[MPS-2022-57238](https://www.oscs1024.com/hd/MPS-2022-57238)|CVE-2022-40897|中危|
|PyTorch 命令注入漏洞|代码注入|[MPS-2022-65270](https://www.oscs1024.com/hd/MPS-2022-65270)|CVE-2022-45907|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|torch|1.11.0|1.13.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|numpy|1.20|1.22.2|间接依赖|可选修复|C:0|H:0|M:4|L:0|
|setuptools|59.5.0|65.5.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|219|Low|
|Apache-2.0|83|Low|
|BSD-3-Clause|41|Low|
|BSD-2-Clause|17|Low|
|MPL-2.0|6|Low|
|自定义许可证|9|Low|
|CC-BY-SA-4.0|2|Medium|
|ISC|4|Low|
|GPL-2.0|1|Medium|
|Unlicense|1|Low|
|Python-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|memoize-one|5.1.1|间接依赖|npm|
|github.com/jackc/pgtype|v1.8.0|直接依赖|go|
|Any||间接依赖|pip|
|constants||间接依赖|pip|
|github.com/soheilhy/cmux|v0.1.4|直接依赖|go|
|keras||间接依赖|pip|
|@lezer/common|1.0.2|间接依赖|npm|
|rstfmt|0.0.14|间接依赖|pip|
|@codemirror/lang-python|6.1.2|间接依赖|npm|
|OrderedDict||间接依赖|pip|
|@rc-component/portal|1.1.0|间接依赖|npm|
|@ant-design/icons|5.0.1|间接依赖|npm|
|micro-observables|1.7.2|间接依赖|npm|
|github.com/labstack/gommon|v0.4.0|直接依赖|go|
|@lezer/python|1.1.6|间接依赖|npm|
|rc-overflow|1.2.8|间接依赖|npm|
|IO||间接依赖|pip|
|github.com/Azure/go-ansiterm|v0.0.0-20210617225240-d185dfc1b5a1|间接依赖|go|
|react-window|1.8.8|间接依赖|npm|
|BertModel||间接依赖|pip|
|github.com/fsnotify/fsnotify|v1.5.4|间接依赖|go|
|prop-types|15.8.1|间接依赖|npm|
|markdown-to-jsx|7.1.9|间接依赖|npm|
|@ant-design/react-slick|1.0.0|间接依赖|npm|
|github.com/labstack/echo-contrib|v0.11.0|直接依赖|go|
|github.com/go-pg/zerochecker|v0.2.0|间接依赖|go|
|termcolor||间接依赖|pip|
|github.com/prometheus/common|v0.26.0|间接依赖|go|
|@remix-run/router|1.4.0|间接依赖|npm|
|_defaults||间接依赖|pip|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|@rc-component/mini-decimal|1.0.1|间接依赖|npm|
|shallowequal|1.1.0|间接依赖|npm|
|github.com/opentracing/opentracing-go|v1.2.0|直接依赖|go|
|Enum||间接依赖|pip|
|gopkg.in/ini.v1|v1.63.2|间接依赖|go|
|github.com/rogpeppe/go-internal|v1.9.0|间接依赖|go|
|github.com/xtgo/uuid|v0.0.0-20140804021211-a0b114877d4c|间接依赖|go|
|scheduler|0.23.0|间接依赖|npm|
|rc-input|0.1.4|间接依赖|npm|
|github.com/hashicorp/golang-lru|v0.5.1|间接依赖|go|
|github.com/sirupsen/logrus|v1.8.1|直接依赖|go|
|field||间接依赖|pip|
|github.com/prometheus/client_model|v0.2.0|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|rc-image|5.13.0|间接依赖|npm|
|github.com/go-logr/logr|v1.2.3|间接依赖|go|
|clsx|1.1.1|间接依赖|npm|
|namedtuple||间接依赖|pip|
|github.com/docker/docker|v20.10.24+incompatible|直接依赖|go|
|download||间接依赖|pip|
|air||间接依赖|pip|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.1.2|间接依赖|go|
|hoist-non-react-statics|3.3.2|间接依赖|npm|
|omnibar|2.3.5|间接依赖|npm|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|PyTorchTrial||间接依赖|pip|
|@uiw/react-codemirror|4.20.2|间接依赖|npm|
|PyTorchCallback||间接依赖|pip|
|Literal||间接依赖|pip|
|github.com/Masterminds/goutils|v1.1.1|间接依赖|go|
|gotest.tools/v3|v3.3.0|间接依赖|go|
|dom-align|1.12.3|间接依赖|npm|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|github.com/docker/libtrust|v0.0.0-20150114040149-fa567046d9b1|间接依赖|go|
|ansi-to-html|0.7.2|间接依赖|npm|
|flake8-comprehensions|2.2.0|间接依赖|pip|
|gpt-neox/requirements/requirements.txt||间接依赖|pip|
|google.golang.org/api|v0.56.0|直接依赖|go|
|gotest.tools|v2.2.0+incompatible|直接依赖|go|
|MissingMandatoryValue||间接依赖|pip|
|go.uber.org/atomic|v1.9.0|直接依赖|go|
|github.com/uptrace/bun/extra/bundebug|v1.1.14|直接依赖|go|
|errors||间接依赖|pip|
|dnd-core|16.0.1|间接依赖|npm|
|@ant-design/cssinjs|1.5.6|间接依赖|npm|
|github.com/fatih/color|v1.15.0|间接依赖|go|
|Tuple||间接依赖|pip|
|@codemirror/autocomplete|6.7.1|间接依赖|npm|
|rc-select|14.2.0|间接依赖|npm|
|gopkg.in/check.v1|v1.0.0-20201130134442-10cb98267c6c|间接依赖|go|
|sphinx-sitemap|2.2.0|间接依赖|pip|
|pyzmq|23.2.1|间接依赖|pip|
|github.com/opencontainers/go-digest|v1.0.0|间接依赖|go|
|js-yaml|4.1.0|间接依赖|npm|
|k8s.io/utils|v0.0.0-20210930125809-cb0fa318a74b|间接依赖|go|
|github.com/googleapis/gnostic|v0.5.5|间接依赖|go|
|rc-drawer|6.1.2|间接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|github.com/go-pg/pg/v10|v10.10.6|直接依赖|go|
|SUPPRESS||间接依赖|pip|
|k8s.io/apimachinery|v0.20.14|直接依赖|go|
|rc-dropdown|4.0.1|间接依赖|npm|
|Union||间接依赖|pip|
|pretty-bytes|6.1.0|间接依赖|npm|
|go.opentelemetry.io/otel/exporters/otlp/internal/retry|v1.6.1|间接依赖|go|
|github.com/google/go-cmp|v0.5.8|间接依赖|go|
|@ant-design/colors|7.0.0|间接依赖|npm|
|react-helmet-async|1.3.0|间接依赖|npm|
|determined||间接依赖|pip|
|toggle-selection|1.0.6|间接依赖|npm|
|@lezer/highlight|1.1.4|间接依赖|npm|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/uber/jaeger-client-go|v2.25.0+incompatible|直接依赖|go|
|github.com/stretchr/objx|v0.5.0|间接依赖|go|
|github.com/moby/term|v0.0.0-20210619224110-3f7ff695adc6|间接依赖|go|
|github.com/go-test/deep|v1.1.0|直接依赖|go|
|_utils||间接依赖|pip|
|rc-tooltip|5.2.2|间接依赖|npm|
|MetricReducer||间接依赖|pip|
|github.com/jackc/pgio|v1.0.0|间接依赖|go|
|github.com/docker/go-connections|v0.4.0|直接依赖|go|
|datasets|1.9.0|间接依赖|pip|
|github.com/docker/distribution|v2.8.2+incompatible|直接依赖|go|
|react-dom|18.2.0|间接依赖|npm|
|timedelta||间接依赖|pip|
|unique||间接依赖|pip|
|NamedTuple||间接依赖|pip|
|bump2version|1.0.1|间接依赖|pip|
|react-is|16.13.1|间接依赖|npm|
|go.opentelemetry.io/otel|v1.6.1|直接依赖|go|
|github.com/mitchellh/mapstructure|v1.4.2|间接依赖|go|
|github.com/hashicorp/go-cleanhttp|v0.5.2|直接依赖|go|
|rc-menu|9.8.2|间接依赖|npm|
|transformers|4.8.2|间接依赖|pip|
|ONE_OR_MORE||间接依赖|pip|
|github.com/ghodss/yaml|v1.0.1-0.20190212211648-25d852aebe32|直接依赖|go|
|gopkg.in/segmentio/analytics-go.v3|v3.1.0|直接依赖|go|
|SimpleHTTPRequestHandler||间接依赖|pip|
|rc-input-number|7.4.0|间接依赖|npm|
|make_generator_model||间接依赖|pip|
|github.com/davecgh/go-spew|v1.1.1|直接依赖|go|
|ArgsDescription||间接依赖|pip|
|react-responsive-carousel|3.2.23|间接依赖|npm|
|async-validator|4.2.5|间接依赖|npm|
|@react-dnd/asap|5.0.2|间接依赖|npm|
|github.com/bmizerany/assert|v0.0.0-20160611221934-b7ed37b82869|间接依赖|go|
|throttle-debounce|5.0.0|间接依赖|npm|
|@codemirror/commands|6.2.4|间接依赖|npm|
|screenfull|6.0.2|间接依赖|npm|
|github.com/aead/poly1305|v0.0.0-20180717145839-3fee0db0b635|间接依赖|go|
|github.com/docker/go-units|v0.4.0|直接依赖|go|
|flask||间接依赖|pip|
|@babel/runtime|7.20.1|间接依赖|npm|
|github.com/go-sql-driver/mysql|v1.6.0|间接依赖|go|
|Set||间接依赖|pip|
|ContextManager||间接依赖|pip|
|rc-notification|5.0.2|间接依赖|npm|
|github.com/kr/pretty|v0.3.0|间接依赖|go|
|boto3||间接依赖|pip|
|diffusers||间接依赖|pip|
|DatasetCatalog||间接依赖|pip|
|google.golang.org/protobuf|v1.28.0|直接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace/otlptracegrpc|v1.6.1|直接依赖|go|
|rc-segmented|2.1.0|间接依赖|npm|
|pytorch||间接依赖|pip|
|github.com/docker/docker-credential-helpers|v0.6.4|直接依赖|go|
|compute-scroll-into-view|2.0.4|间接依赖|npm|
|azure||间接依赖|pip|
|github.com/vmihailenco/tagparser/v2|v2.0.0|间接依赖|go|
|github.com/vmihailenco/bufpool|v0.1.11|间接依赖|go|
|SGD||间接依赖|pip|
|github.com/Azure/go-autorest|v14.2.0+incompatible|间接依赖|go|
|react-dnd-html5-backend|16.0.1|间接依赖|npm|
|scroll-into-view-if-needed|3.0.4|间接依赖|npm|
|github.com/matttproud/golang_protobuf_extensions|v1.0.1|间接依赖|go|
|github.com/go-pg/migrations/v8|v8.1.0|直接依赖|go|
|PRIMITIVES||间接依赖|pip|
|golang.org/x/exp|v0.0.0-20220328175248-053ad81199eb|直接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20211115234752-e816edb12b65|间接依赖|go|
|flake8-builtins|1.5.3|间接依赖|pip|
|mmcv-full|1.4.5|间接依赖|pip|
|github.com/shirou/gopsutil|v3.21.11+incompatible|直接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|rc-rate|2.9.1|间接依赖|npm|
|rc-resize-observer|1.2.0|间接依赖|npm|
|dayjs|1.11.7|间接依赖|npm|
|client||间接依赖|pip|
|immutable|4.3.0|间接依赖|npm|
|numpy|1.20|间接依赖|pip|
|csstype|3.1.1|间接依赖|npm|
|@codemirror/lint|6.2.1|间接依赖|npm|
|TrialSortBy||间接依赖|pip|
|github.com/docker/go-metrics|v0.0.1|间接依赖|go|
|github.com/valyala/bytebufferpool|v1.0.0|间接依赖|go|
|flake8-tuple|0.4.0|间接依赖|pip|
|json2mq|0.2.0|间接依赖|npm|
|deque||间接依赖|pip|
|DataLoader||间接依赖|pip|
|regenerator-runtime|0.13.11|间接依赖|npm|
|github.com/golang-jwt/jwt|v3.2.2+incompatible|间接依赖|go|
|ArgumentDefaultsHelpFormatter||间接依赖|pip|
|go.opentelemetry.io/otel/trace|v1.6.1|间接依赖|go|
|DistributedContext||间接依赖|pip|
|cloud.google.com/go|v0.94.0|直接依赖|go|
|@lezer/lr|1.3.4|间接依赖|npm|
|Deque||间接依赖|pip|
|qrcode.react|3.1.0|间接依赖|npm|
|react-dnd|16.0.1|间接依赖|npm|
|model_hub||间接依赖|pip|
|rc-picker|3.1.4|间接依赖|npm|
|github.com/grpc-ecosystem/grpc-gateway|v1.16.0|直接依赖|go|
|github.com/golang-jwt/jwt/v4|v4.4.3|直接依赖|go|
|go.opencensus.io|v0.23.0|间接依赖|go|
|github.com/emirpasic/gods|v1.18.1|直接依赖|go|
|github.com/stretchr/testify|v1.8.1|直接依赖|go|
|resize-observer-polyfill|1.5.1|间接依赖|npm|
|github.com/jackc/pgproto3/v2|v2.1.1|间接依赖|go|
|stylis|4.1.3|间接依赖|npm|
|Sequence||间接依赖|pip|
|rc-field-form|1.27.3|间接依赖|npm|
|github.com/vmihailenco/msgpack/v5|v5.3.5|间接依赖|go|
|@codemirror/language|6.7.0|间接依赖|npm|
|github.com/grpc-ecosystem/grpc-gateway/v2|v2.7.0|间接依赖|go|
|util||间接依赖|pip|
|google.golang.org/protobuf|v1.27.1|直接依赖|go|
|github.com/elastic/go-elasticsearch/v7|v7.9.0|直接依赖|go|
|github.com/prometheus/procfs|v0.6.0|间接依赖|go|
|react-router-dom|6.9.0|间接依赖|npm|
|github.com/golang/protobuf|v1.5.2|直接依赖|go|
|github.com/grpc-ecosystem/go-grpc-middleware|v1.3.0|直接依赖|go|
|golang.org/x/term|v0.5.0|间接依赖|go|
|experimental||间接依赖|pip|
|react-easy-swipe|0.0.21|间接依赖|npm|
|check||间接依赖|pip|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|model_def||间接依赖|pip|
|deepspeed|0.8.3|间接依赖|pip|
|github.com/spf13/jwalterweatherman|v1.1.0|间接依赖|go|
|required||间接依赖|pip|
|Generator||间接依赖|pip|
|MetadataCatalog||间接依赖|pip|
|github.com/Azure/go-autorest/autorest/adal|v0.9.15|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20211223182754-3ac035c7e7cb|直接依赖|go|
|Iterator||间接依赖|pip|
|BaseHTTPRequestHandler||间接依赖|pip|
|crelt|1.0.6|间接依赖|npm|
|flake8-quotes|2.1.0|间接依赖|pip|
|github.com/huandu/xstrings|v1.3.2|直接依赖|go|
|github.com/hashicorp/go-multierror|v1.1.1|直接依赖|go|
|@codemirror/lang-css|6.2.0|间接依赖|npm|
|flake8-colors|0.1.6|间接依赖|pip|
|Genotype||间接依赖|pip|
|ArgumentError||间接依赖|pip|
|dataclass||间接依赖|pip|
|core-js|3.32.0|间接依赖|npm|
|github.com/jackc/pgservicefile|v0.0.0-20200714003250-2b9c44734f2b|间接依赖|go|
|SquadFeatures||间接依赖|pip|
|flake8-import-restrictions|1.1.1|间接依赖|pip|
|github.com/prometheus/client_golang|v1.11.1|直接依赖|go|
|react-transition-group|4.4.5|间接依赖|npm|
|rc-collapse|3.4.2|间接依赖|npm|
|flake8-bugbear|19.8.0|间接依赖|pip|
|github.com/aead/chacha20|v0.0.0-20180709150244-8b13a72661da|间接依赖|go|
|codemirror|6.0.1|间接依赖|npm|
|gopkg.in/guregu/null.v3|v3.4.0|直接依赖|go|
|embedded_dropout||间接依赖|pip|
|golang.org/x/net|v0.7.0|直接依赖|go|
|k8s.io/client-go|v0.20.14|直接依赖|go|
|rc-motion|2.6.2|间接依赖|npm|
|github.com/jackc/chunkreader/v2|v2.0.1|间接依赖|go|
|MockMasterSearchRunner||间接依赖|pip|
|rc-textarea|0.4.7|间接依赖|npm|
|authentication||间接依赖|pip|
|react|18.2.0|间接依赖|npm|
|NTSC_Kind||间接依赖|pip|
|Type||间接依赖|pip|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|github.com/spf13/viper|v1.9.0|直接依赖|go|
|string-convert|0.2.1|间接依赖|npm|
|google.golang.org/grpc|v1.40.0|直接依赖|go|
|dom-helpers|5.2.1|间接依赖|npm|
|torchvision|0.12.0|间接依赖|pip|
|github.com/morikuni/aec|v1.0.0|间接依赖|go|
|TrialReference||间接依赖|pip|
|@lezer/html|1.3.4|间接依赖|npm|
|rc-pagination|3.2.0|间接依赖|npm|
|github.com/subosito/gotenv|v1.2.0|间接依赖|go|
|GraphConv||间接依赖|pip|
|SimulateMaster||间接依赖|pip|
|golang.org/x/oauth2|v0.0.0-20211104180415-d3ed0bb246c8|间接依赖|go|
|auto||间接依赖|pip|
|make_discriminator_model||间接依赖|pip|
|humanize-duration|3.28.0|间接依赖|npm|
|k8s.io/klog/v2|v2.30.0|间接依赖|go|
|github.com/spf13/cobra|v1.6.1|直接依赖|go|
|@lezer/javascript|1.4.3|间接依赖|npm|
|github.com/segmentio/backo-go|v0.0.0-20200129164019-23eae7c10bd3|间接依赖|go|
|golang.org/x/sys|v0.5.0|间接依赖|go|
|rc-tree-select|5.6.0|间接依赖|npm|
|@emotion/hash|0.8.0|间接依赖|npm|
|pydantic|2|间接依赖|pip|
|@hpe.com/glide-data-grid|5.2.1-pin-1274|间接依赖|npm|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|github.com/jackc/pgpassfile|v1.0.0|间接依赖|go|
|lodash|4.17.21|间接依赖|npm|
|@codemirror/view|6.12.0|间接依赖|npm|
|smoothscroll-polyfill|0.4.4|间接依赖|npm|
|io-ts|2.2.20|间接依赖|npm|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|storage||间接依赖|pip|
|sphinx|4.2.0|间接依赖|pip|
|invariant|2.2.4|间接依赖|npm|
|w3c-keyname|2.2.7|间接依赖|npm|
|golang.org/x/time|v0.0.0-20210723032227-1f47c861a9ac|直接依赖|go|
|uuid|9.0.0|间接依赖|npm|
|github.com/shopspring/decimal|v1.2.0|直接依赖|go|
|Arg||间接依赖|pip|
|github.com/mattn/go-isatty|v0.0.19|间接依赖|go|
|array-tree-filter|2.1.0|间接依赖|npm|
|Determined||间接依赖|pip|
|TYPE_CHECKING||间接依赖|pip|
|sphinx-reredirects|0.0.1|间接依赖|pip|
|horovod||间接依赖|pip|
|@ant-design/icons-svg|4.2.1|间接依赖|npm|
|github.com/yusufpapurcu/wmi|v1.2.2|间接依赖|go|
|pytest|6.0.1|间接依赖|pip|
|@codemirror/lang-javascript|6.1.8|间接依赖|npm|
|HTTPServer||间接依赖|pip|
|github.com/spf13/afero|v1.6.0|间接依赖|go|
|@codemirror/lang-markdown|6.1.1|间接依赖|npm|
|notebook||间接依赖|npm|
|github.com/Azure/go-autorest/logger|v0.2.1|间接依赖|go|
|@codemirror/search|6.4.0|间接依赖|npm|
|path-to-regexp|6.2.1|间接依赖|npm|
|api||间接依赖|pip|
|rc-util|5.27.2|间接依赖|npm|
|timezone||间接依赖|pip|
|gopkg.in/yaml.v3|v3.0.1|直接依赖|go|
|ModelSortBy||间接依赖|pip|
|github.com/Masterminds/semver/v3|v3.1.1|间接依赖|go|
|rc-align|4.0.12|间接依赖|npm|
|TFKerasTrialContext||间接依赖|pip|
|LockedDropout||间接依赖|pip|
|github.com/uber/jaeger-lib|v2.4.0+incompatible|间接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|间接依赖|go|
|mypy|0.910|间接依赖|pip|
|cast||间接依赖|pip|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|sphinx-tabs|3.0|间接依赖|pip|
|@react-dnd/shallowequal|4.0.2|间接依赖|npm|
|TopKPooling||间接依赖|pip|
|github.com/uptrace/bun/dialect/pgdialect|v1.1.14|直接依赖|go|
|github.com/gorilla/mux|v1.8.0|间接依赖|go|
|github.com/spf13/cast|v1.4.1|间接依赖|go|
|rc-slider|10.0.0|间接依赖|npm|
|torch|1.11.0|间接依赖|pip|
|github.com/Masterminds/sprig/v3|v3.2.2|直接依赖|go|
|rc-upload|4.3.1|间接依赖|npm|
|ManagedCluster||间接依赖|pip|
|sigs.k8s.io/yaml|v1.2.0|间接依赖|go|
|PreemptMode||间接依赖|pip|
|accelerate|0.12.0|间接依赖|pip|
|github.com/labstack/echo/v4|v4.9.1|直接依赖|go|
|github.com/pelletier/go-toml|v1.9.4|间接依赖|go|
|cloud.google.com/go/storage|v1.10.0|直接依赖|go|
|github.com/determined-ai/determined/proto|v0.0.0-00010101000000-000000000000|直接依赖|go|
|github.com/jackc/pgconn|v1.9.0|直接依赖|go|
|@rc-component/tour|1.1.0|间接依赖|npm|
|get_agent_data||间接依赖|pip|
|github.com/opencontainers/image-spec|v1.0.2|间接依赖|go|
|Session||间接依赖|pip|
|sprintf-js|1.1.2|间接依赖|npm|
|@react-dnd/invariant|4.0.2|间接依赖|npm|
|fp-ts|2.13.1|间接依赖|npm|
|github.com/jmoiron/sqlx|v1.2.1-0.20190826204134-d7d95172beb5|直接依赖|go|
|github.com/tklauser/numcpus|v0.6.0|间接依赖|go|
|github.com/tklauser/go-sysconf|v0.3.11|间接依赖|go|
|Iterable||间接依赖|pip|
|github.com/mitchellh/reflectwalk|v1.0.2|间接依赖|go|
|react-number-format|5.2.2|间接依赖|npm|
|go.opentelemetry.io/otel/sdk|v1.6.1|直接依赖|go|
|Optional||间接依赖|pip|
|github.com/gorilla/websocket|v1.5.0|直接依赖|go|
|sqlfluff|2.1.4|间接依赖|pip|
|events|3.3.0|间接依赖|npm|
|loose-envify|1.4.0|间接依赖|npm|
|yaml||间接依赖|pip|
|Callable||间接依赖|pip|
|object-assign|4.1.1|间接依赖|npm|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/aead/chacha20poly1305|v0.0.0-20170617001512-233f39982aeb|间接依赖|go|
|@lezer/css|1.1.2|间接依赖|npm|
|@lezer/markdown|1.0.2|间接依赖|npm|
|github.com/Azure/go-autorest/autorest/date|v0.3.0|间接依赖|go|
|golang.org/x/sys|v0.10.0|直接依赖|go|
|@rc-component/mutate-observer|1.0.0|间接依赖|npm|
|fuse.js|6.6.2|间接依赖|npm|
|rc-tree|5.7.2|间接依赖|npm|
|rc-virtual-list|3.4.13|间接依赖|npm|
|react-draggable|4.4.5|间接依赖|npm|
|github.com/google/gofuzz|v1.1.0|间接依赖|go|
|golang.org/x/text|v0.7.0|间接依赖|go|
|golang.org/x/crypto|v0.0.0-20220829220503-c86fa9a7ed90|直接依赖|go|
|style-mod|4.0.3|间接依赖|npm|
|github.com/grpc-ecosystem/go-grpc-prometheus|v1.2.0|直接依赖|go|
|flake8-docstrings|1.4.0|间接依赖|pip|
|load_dataset||间接依赖|pip|
|github.com/jackc/pgx/v4|v4.12.0|直接依赖|go|
|github.com/valyala/fasttemplate|v1.2.1|间接依赖|go|
|debug|4.3.4|间接依赖|npm|
|@codemirror/legacy-modes|6.3.2|间接依赖|npm|
|config||间接依赖|pip|
|github.com/o1egl/paseto|v1.0.0|直接依赖|go|
|save_checkpoint||间接依赖|pip|
|Dict||间接依赖|pip|
|rc-progress|3.4.1|间接依赖|npm|
|@codemirror/state|6.2.0|间接依赖|npm|
|load_checkpoint||间接依赖|pip|
|github.com/aws/aws-sdk-go|v1.40.34|直接依赖|go|
|setuptools|59.5.0|间接依赖|pip|
|github.com/coreos/go-systemd|v0.0.0-20190719114852-fd7a80b32e1f|直接依赖|go|
|logged_in_user||间接依赖|pip|
|react-router|6.9.0|间接依赖|npm|
|github.com/hashicorp/errwrap|v1.0.0|间接依赖|go|
|@rc-component/context|1.3.0|间接依赖|npm|
|argparse|2.0.1|间接依赖|npm|
|uplot|1.6.18|间接依赖|npm|
|js-sha512|0.8.0|间接依赖|npm|
|github.com/matttproud/golang_protobuf_extensions|v1.0.2-0.20181231171920-c182affec369|间接依赖|go|
|hermes-parallel-coordinates|0.6.17|间接依赖|npm|
|github.com/tmthrgd/go-hex|v0.0.0-20190904060850-447a3041c3bc|间接依赖|go|
|rc-tabs|12.5.6|间接依赖|npm|
|Optimizer||间接依赖|pip|
|h5py|3|间接依赖|pip|
|requirements/build.txt||间接依赖|pip|
|github.com/Azure/go-autorest/tracing|v0.6.0|间接依赖|go|
|github.com/santhosh-tekuri/jsonschema/v2|v2.2.0|直接依赖|go|
|golang.org/x/sync|v0.1.0|直接依赖|go|
|classnames|2.3.2|间接依赖|npm|
|mellium.im/sasl|v0.3.1|间接依赖|go|
|TFKerasTrial||间接依赖|pip|
|github.com/imdario/mergo|v0.3.12|间接依赖|go|
|rc-steps|6.0.0|间接依赖|npm|
|github.com/google/uuid|v1.3.0|直接依赖|go|
|github.com/go-ole/go-ole|v1.2.6|间接依赖|go|
|google.golang.org/grpc/examples|v0.0.0-20210525230658-4bae49e05b28|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|go.uber.org/atomic|v1.10.0|间接依赖|go|
|bindings||间接依赖|pip|
|tokenizers|0.13.3|间接依赖|pip|
|rc-cascader|3.8.0|间接依赖|npm|
|FileType||间接依赖|pip|
|entities|2.2.0|间接依赖|npm|
|k8s.io/api|v0.20.14|直接依赖|go|
|SquadV1Processor||间接依赖|pip|
|canvas-hypertxt|0.0.7|间接依赖|npm|
|github.com/inconshreveable/mousetrap|v1.0.1|间接依赖|go|
|github.com/Microsoft/go-winio|v0.5.0|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace|v1.6.1|直接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|google.golang.org/grpc|v1.45.0|直接依赖|go|
|github.com/uptrace/bun|v1.1.14|直接依赖|go|
|certs||间接依赖|pip|
|rc-table|7.30.3|间接依赖|npm|
|go.opentelemetry.io/contrib/instrumentation/github.com/labstack/echo/otelecho|v0.29.0|直接依赖|go|
|List||间接依赖|pip|
|rc-checkbox|2.3.2|间接依赖|npm|
|github.com/cenkalti/backoff/v4|v4.1.3|直接依赖|go|
|@emotion/unitless|0.7.5|间接依赖|npm|
|github.com/googleapis/gax-go/v2|v2.1.0|间接依赖|go|
|ADMIN_CREDENTIALS||间接依赖|pip|
|Namespace||间接依赖|pip|
|@codemirror/lang-html|6.4.3|间接依赖|npm|
|redux|4.2.1|间接依赖|npm|
|@codemirror/theme-one-dark|6.1.2|间接依赖|npm|
|copy-to-clipboard|3.3.1|间接依赖|npm|
|github.com/Azure/go-autorest/autorest|v0.11.20|间接依赖|go|
|flake8-commas|2.0.0|间接依赖|pip|
|tune||间接依赖|pip|
|antd|5.1.7|间接依赖|npm|
|sphinx-copybutton|0.4.0|间接依赖|pip|
|pillow|10.0.0|间接依赖|pip|
|sphinx-book-theme|1.0.0|间接依赖|pip|
|DictConfig||间接依赖|pip|
|marked|4.3.0|间接依赖|npm|
|github.com/jinzhu/inflection|v1.0.0|间接依赖|go|
|@uiw/codemirror-extensions-basic-setup|4.20.2|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|defaultdict||间接依赖|pip|
|github.com/dustinkirkland/golang-petname|v0.0.0-20191129215211-8e5a1ed0cff0|直接依赖|go|
|BertTokenizer||间接依赖|pip|
|go.opentelemetry.io/proto/otlp|v0.12.1|间接依赖|go|
|github.com/jinzhu/copier|v0.3.5|直接依赖|go|
|rc-trigger|5.3.4|间接依赖|npm|
|github.com/mitchellh/copystructure|v1.2.0|间接依赖|go|
|github.com/determined-ai/determined/master|v0.0.0|直接依赖|go|
|js-tokens|4.0.0|间接依赖|npm|
|github.com/cespare/xxhash/v2|v2.1.1|间接依赖|go|
|@ctrl/tinycolor|3.5.0|间接依赖|npm|
|github.com/magiconair/properties|v1.8.5|间接依赖|go|
|github.com/vmihailenco/tagparser|v0.1.2|间接依赖|go|
|react-fast-compare|3.2.0|间接依赖|npm|
|rc-mentions|1.13.1|间接依赖|npm|
|mmdet|2.21.0|间接依赖|pip|
|rc-switch|4.0.0|间接依赖|npm|
|rc-dialog|9.0.2|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)