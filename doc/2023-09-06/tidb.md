# pingcap/tidb安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699123135332007936.svg)](https://www.murphysec.com/console/report/1699123134862245888/1699123135332007936)

仓库描述：TiDB is an open-source, cloud-native, distributed, MySQL-Compatible database for elastic scale and real-time analytics. Try AI-powered Chat2Query free at : https://tidbcloud.com/free-trial

仓库地址：[https://github.com/pingcap/tidb](https://github.com/pingcap/tidb)

| star：34764 | watch：1285 | fork：5594 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-06 00:42:49 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-06 02:17:39 | 组件总数：535 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|semver|7.3.5|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|305|Low|
|BSD-3-Clause|72|Low|
|ISC|13|Low|
|GPL-3.0|1|Medium|
|Apache-2.0|110|Low|
|BSD-2-Clause|24|Low|
|CC-BY-4.0|1|Low|
|BSD-2-Clause-Views|1|Low|
|Unlicense|1|Low|
|CC0-1.0|1|Low|
|MPL-2.0|3|Low|
|0BSD|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/joho/sqltocsv|v0.0.0-20210428211105-a6d6801d59df|直接依赖|go|
|@webassemblyjs/ieee754|1.11.6|间接依赖|npm|
|@types/node|20.3.1|间接依赖|npm|
|github.com/twmb/murmur3|v1.1.6|直接依赖|go|
|signal-exit|3.0.5|间接依赖|npm|
|github.com/golang/protobuf|v1.5.3|直接依赖|go|
|browserslist|4.17.3|间接依赖|npm|
|github.com/golang-jwt/jwt|v3.2.1+incompatible|间接依赖|go|
|github.com/golangci/golangci-lint|v1.53.3|直接依赖|go|
|github.com/Masterminds/semver/v3|v3.1.1|间接依赖|go|
|golang.org/x/xerrors|v0.0.0-20220907171357-04be3eba64a2|间接依赖|go|
|isobject|3.0.1|间接依赖|npm|
|cloud.google.com/go/pubsub|v1.30.0|间接依赖|go|
|golang.org/x/sys|v0.11.0|直接依赖|go|
|jss-plugin-global|10.8.0|间接依赖|npm|
|supports-color|7.2.0|间接依赖|npm|
|typescript|4.4.3|直接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.14|间接依赖|npm|
|github.com/power-devops/perfstat|v0.0.0-20221212215047-62379fc7944b|间接依赖|go|
|github.com/coocood/rtutil|v0.0.0-20190304133409-c84515f646f2|间接依赖|go|
|rechoir|0.7.1|间接依赖|npm|
|nth-check|2.0.1|间接依赖|npm|
|electron-to-chromium|1.3.864|间接依赖|npm|
|modernc.org/mathutil|v1.6.0|间接依赖|go|
|github.com/gostaticanalysis/forcetypeassert|v0.1.0|直接依赖|go|
|@webassemblyjs/wast-printer|1.11.6|间接依赖|npm|
|github.com/robfig/cron/v3|v3.0.1|直接依赖|go|
|fill-range|7.0.1|间接依赖|npm|
|is-in-browser|1.1.3|间接依赖|npm|
|stathat.com/c/consistent|v1.0.0|间接依赖|go|
|css-select|4.1.3|间接依赖|npm|
|github.com/rogpeppe/go-internal|v1.11.0|间接依赖|go|
|fastest-levenshtein|1.0.12|间接依赖|npm|
|go.uber.org/atomic|v1.11.0|直接依赖|go|
|github.com/chavacava/garif|v0.0.0-20230519080132-4752330f72df|间接依赖|go|
|github.com/prometheus/procfs|v0.11.1|间接依赖|go|
|caniuse-lite|1.0.30001265|间接依赖|npm|
|github.com/stretchr/objx|v0.5.0|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/storage/azblob|v1.0.0|直接依赖|go|
|github.com/cockroachdb/logtags|v0.0.0-20190617123548-eb05cc24525f|间接依赖|go|
|@types/prop-types|15.7.4|间接依赖|npm|
|github.com/rcrowley/go-metrics|v0.0.0-20201227073835-cf1acfcdf475|间接依赖|go|
|@webassemblyjs/helper-wasm-section|1.11.6|间接依赖|npm|
|tapable|2.2.1|间接依赖|npm|
|tiny-invariant|1.1.0|间接依赖|npm|
|github.com/xitongsys/parquet-go-source|v0.0.0-20200817004010-026bad9b25d0|直接依赖|go|
|merge-stream|2.0.0|间接依赖|npm|
|github.com/mattn/go-runewidth|v0.0.14|间接依赖|go|
|glob-to-regexp|0.4.1|间接依赖|npm|
|modernc.org/strutil|v1.2.0|间接依赖|go|
|@xtuc/long|4.2.2|间接依赖|npm|
|github.com/shirou/gopsutil/v3|v3.23.5|直接依赖|go|
|github.com/grpc-ecosystem/go-grpc-prometheus|v1.2.0|间接依赖|go|
|@webpack-cli/serve|1.6.0|间接依赖|npm|
|github.com/pingcap/errors|v0.11.5-0.20210425183316-da1aaba5fb63|直接依赖|go|
|pretty-error|3.0.4|间接依赖|npm|
|cross-spawn|7.0.3|间接依赖|npm|
|github.com/shurcooL/httpfs|v0.0.0-20190707220628-8d4bc4ba7749|间接依赖|go|
|github.com/ngaut/pools|v0.0.0-20180318154953-b7bc8c42aac7|直接依赖|go|
|path-to-regexp|1.8.0|间接依赖|npm|
|github.com/coocood/freecache|v1.2.1|直接依赖|go|
|@webpack-cli/info|1.4.0|间接依赖|npm|
|github.com/spf13/cast|v1.5.0|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|kind-of|6.0.3|间接依赖|npm|
|dom-converter|0.2.0|间接依赖|npm|
|popper.js|1.16.1-lts|间接依赖|npm|
|github.com/goccy/go-json|v0.10.2|间接依赖|go|
|terser|4.8.1|间接依赖|npm|
|github.com/google/renameio/v2|v2.0.0|间接依赖|go|
|mimic-fn|2.1.0|间接依赖|npm|
|gopkg.in/natefinch/lumberjack.v2|v2.2.1|间接依赖|go|
|yallist|4.0.0|间接依赖|npm|
|@webassemblyjs/ast|1.11.6|间接依赖|npm|
|github.com/go-ldap/ldap/v3|v3.4.4|直接依赖|go|
|github.com/cespare/xxhash|v1.1.0|间接依赖|go|
|@webassemblyjs/floating-point-hex-parser|1.11.6|间接依赖|npm|
|@jridgewell/trace-mapping|0.3.18|间接依赖|npm|
|css-what|5.1.0|间接依赖|npm|
|is-stream|2.0.1|间接依赖|npm|
|github.com/cznic/sortutil|v0.0.0-20181122101858-f5f958428db8|直接依赖|go|
|k8s.io/utils|v0.0.0-20230209194617-a36077c30491|间接依赖|go|
|modernc.org/y|v1.0.9|直接依赖|go|
|github.com/felixge/httpsnoop|v1.0.2|间接依赖|go|
|lower-case|2.0.2|间接依赖|npm|
|@webassemblyjs/utf8|1.11.6|间接依赖|npm|
|@jridgewell/resolve-uri|3.1.0|间接依赖|npm|
|@types/json-schema|7.0.12|间接依赖|npm|
|ajv-keywords|3.5.2|间接依赖|npm|
|shebang-command|2.0.0|间接依赖|npm|
|@types/html-minifier-terser|5.1.2|间接依赖|npm|
|sourcegraph.com/sourcegraph/appdash-data|v0.0.0-20151005221446-73f23eafcf67|直接依赖|go|
|@webassemblyjs/wasm-edit|1.11.6|间接依赖|npm|
|github.com/pierrec/lz4|v2.6.1+incompatible|间接依赖|go|
|@types/history|4.7.9|间接依赖|npm|
|github.com/oklog/ulid|v1.3.1|间接依赖|go|
|github.com/go-ole/go-ole|v1.2.6|间接依赖|go|
|graceful-fs|4.2.11|间接依赖|npm|
|source-map-support|0.5.20|间接依赖|npm|
|@webassemblyjs/helper-buffer|1.11.6|间接依赖|npm|
|no-case|3.0.4|间接依赖|npm|
|github.com/lestrrat-go/option|v1.0.1|间接依赖|go|
|camel-case|4.1.2|间接依赖|npm|
|github.com/remyoudompheng/bigfft|v0.0.0-20230129092748-24d4a6f8daec|间接依赖|go|
|github.com/danjacques/gofslock|v0.0.0-20191023191349-0a45f885bc37|直接依赖|go|
|github.com/dgraph-io/ristretto|v0.1.1|直接依赖|go|
|github.com/sasha-s/go-deadlock|v0.2.0|直接依赖|go|
|go.opentelemetry.io/otel/sdk/metric|v0.20.0|间接依赖|go|
|github.com/sirupsen/logrus|v1.9.3|间接依赖|go|
|find-up|4.1.0|间接依赖|npm|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/vbauerster/mpb/v7|v7.5.3|直接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|github.com/opentracing/basictracer-go|v1.0.0|直接依赖|go|
|@types/react-transition-group|4.4.3|间接依赖|npm|
|jest-worker|27.5.1|间接依赖|npm|
|modernc.org/golex|v1.1.0|间接依赖|go|
|chalk|4.1.2|间接依赖|npm|
|github.com/lestrrat-go/httpcc|v1.0.1|间接依赖|go|
|@webassemblyjs/wasm-gen|1.11.6|间接依赖|npm|
|github.com/fatih/color|v1.15.0|直接依赖|go|
|github.com/google/licensecheck|v0.3.1|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/azcore|v1.6.0|直接依赖|go|
|github.com/go-logr/logr|v1.2.3|间接依赖|go|
|github.com/spf13/cobra|v1.7.0|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/internal|v1.3.0|间接依赖|go|
|go.etcd.io/etcd/server/v3|v3.5.2|直接依赖|go|
|js-tokens|4.0.0|间接依赖|npm|
|onetime|5.1.2|间接依赖|npm|
|github.com/apache/thrift|v0.13.1-0.20201008052519-daf620915714|间接依赖|go|
|github.com/googleapis/gax-go/v2|v2.7.1|间接依赖|go|
|github.com/cockroachdb/redact|v1.0.8|间接依赖|go|
|@types/estree|1.0.1|间接依赖|npm|
|modernc.org/sortutil|v1.1.1|间接依赖|go|
|github.com/cockroachdb/sentry-go|v0.6.1-cockroachdb.2|间接依赖|go|
|github.com/opentracing/opentracing-go|v1.2.0|直接依赖|go|
|memory-fs|0.5.0|间接依赖|npm|
|react-transition-group|4.4.2|间接依赖|npm|
|github.com/uber/jaeger-client-go|v2.22.1+incompatible|直接依赖|go|
|escalade|3.1.1|间接依赖|npm|
|is-core-module|2.7.0|间接依赖|npm|
|cloud.google.com/go/storage|v1.30.1|直接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|html-webpack-plugin|5.3.2|直接依赖|npm|
|relateurl|0.2.7|间接依赖|npm|
|cloud.google.com/go/compute|v1.19.0|间接依赖|go|
|es-module-lexer|1.3.0|间接依赖|npm|
|github.com/spkg/bom|v1.0.0|直接依赖|go|
|github.com/mitchellh/reflectwalk|v1.0.1|间接依赖|go|
|loose-envify|1.4.0|间接依赖|npm|
|sigs.k8s.io/yaml|v1.3.0|间接依赖|go|
|github.com/decred/dcrd/dcrec/secp256k1/v4|v4.2.0|间接依赖|go|
|github.com/shurcooL/vfsgen|v0.0.0-20181202132449-6a9ea43bcacd|间接依赖|go|
|github.com/Masterminds/goutils|v1.1.1|间接依赖|go|
|@material-ui/styles|4.11.4|间接依赖|npm|
|@webpack-cli/configtest|1.1.0|间接依赖|npm|
|github.com/wangjohn/quickselect|v0.0.0-20161129230411-ed8402a42d5f|直接依赖|go|
|github.com/rivo/uniseg|v0.4.4|间接依赖|go|
|k8s.io/apimachinery|v0.27.2|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|webpack|5.86.0|直接依赖|npm|
|github.com/kisielk/errcheck|v1.6.3|直接依赖|go|
|path-key|3.1.1|间接依赖|npm|
|@emotion/hash|0.8.0|间接依赖|npm|
|github.com/tiancaiamao/appdash|v0.0.0-20181126055449-889f96f722a2|直接依赖|go|
|github.com/golang/glog|v1.1.0|间接依赖|go|
|github.com/pingcap/errors|v0.11.5-0.20221009092201-b66cddb77c32|直接依赖|go|
|github.com/phayes/freeport|v0.0.0-20180830031419-95f893ade6f2|直接依赖|go|
|react-is|17.0.2|间接依赖|npm|
|github.com/tmc/grpc-websocket-proxy|v0.0.0-20201229170055-e5319fda7802|间接依赖|go|
|github.com/go-logfmt/logfmt|v0.5.1|间接依赖|go|
|wildcard|2.0.0|间接依赖|npm|
|watchpack|2.4.0|间接依赖|npm|
|golang.org/x/term|v0.11.0|直接依赖|go|
|github.com/AzureAD/microsoft-authentication-library-for-go|v0.5.1|间接依赖|go|
|bignumber.js|9.0.1|间接依赖|npm|
|github.com/coreos/go-semver|v0.3.0|直接依赖|go|
|github.com/prometheus/tsdb|v0.10.0|间接依赖|go|
|jss-plugin-camel-case|10.8.0|间接依赖|npm|
|github.com/shopspring/decimal|v1.2.0|间接依赖|go|
|object-assign|4.1.1|间接依赖|npm|
|github.com/jcmturner/aescts/v2|v2.0.0|间接依赖|go|
|colorette|2.0.16|间接依赖|npm|
|github.com/cockroachdb/pebble|v0.0.0-20220415182917-06c9d3be25b3|直接依赖|go|
|github.com/mitchellh/copystructure|v1.0.0|间接依赖|go|
|@material-ui/icons|4.11.2|直接依赖|npm|
|@webassemblyjs/helper-api-error|1.11.6|间接依赖|npm|
|github.com/nishanths/predeclared|v0.2.2|直接依赖|go|
|github.com/fatih/structtag|v1.2.0|间接依赖|go|
|go.etcd.io/bbolt|v1.3.6|间接依赖|go|
|has|1.0.3|间接依赖|npm|
|prr|1.0.1|间接依赖|npm|
|@types/eslint-scope|3.7.4|间接依赖|npm|
|github.com/pingcap/log|v1.1.0|直接依赖|go|
|resolve-cwd|3.0.0|间接依赖|npm|
|github.com/gorilla/websocket|v1.4.2|间接依赖|go|
|go.opentelemetry.io/otel/sdk|v0.20.0|间接依赖|go|
|string_decoder|1.1.1|间接依赖|npm|
|github.com/petermattis/goid|v0.0.0-20211229010228-4d14c490ee36|间接依赖|go|
|@material-ui/system|4.12.1|间接依赖|npm|
|github.com/huandu/xstrings|v1.3.1|间接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|enhanced-resolve|4.5.0|间接依赖|npm|
|domhandler|4.2.2|间接依赖|npm|
|github.com/form3tech-oss/jwt-go|v3.2.5+incompatible|间接依赖|go|
|honnef.co/go/tools|v0.4.5|直接依赖|go|
|core-util-is|1.0.3|间接依赖|npm|
|go.etcd.io/etcd/client/pkg/v3|v3.5.2|直接依赖|go|
|go.etcd.io/etcd/raft/v3|v3.5.2|间接依赖|go|
|webpack-merge|5.8.0|间接依赖|npm|
|github.com/iancoleman/strcase|v0.2.0|直接依赖|go|
|github.com/gorilla/handlers|v1.5.1|间接依赖|go|
|github.com/golangci/prealloc|v0.0.0-20180630174525-215b22d4de21|直接依赖|go|
|eslint-scope|5.1.1|间接依赖|npm|
|dom-serializer|1.3.2|间接依赖|npm|
|jss-plugin-props-sort|10.8.0|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|github.com/jedib0t/go-pretty/v6|v6.2.2|直接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp|v0.20.0|间接依赖|go|
|github.com/eapache/go-resiliency|v1.2.0|间接依赖|go|
|go.etcd.io/etcd/pkg/v3|v3.5.2|间接依赖|go|
|errno|0.1.8|间接依赖|npm|
|github.com/nbutton23/zxcvbn-go|v0.0.0-20210217022336-fa2cb2858354|间接依赖|go|
|github.com/stretchr/testify|v1.8.4|直接依赖|go|
|github.com/DATA-DOG/go-sqlmock|v1.5.0|直接依赖|go|
|github.com/cloudfoundry/gosigar|v1.3.6|直接依赖|go|
|sigs.k8s.io/json|v0.0.0-20221116044647-bc3834ca7abd|间接依赖|go|
|github.com/tdakkota/asciicheck|v0.2.0|直接依赖|go|
|github.com/Jeffail/gabs/v2|v2.5.1|直接依赖|go|
|github.com/pingcap/log|v1.1.1-0.20230317032135-a0d097d16e22|直接依赖|go|
|hoist-non-react-statics|3.3.2|间接依赖|npm|
|clone-deep|4.0.1|间接依赖|npm|
|tiny-warning|1.0.3|间接依赖|npm|
|regenerator-runtime|0.13.9|间接依赖|npm|
|github.com/Masterminds/sprig/v3|v3.2.2|间接依赖|go|
|html-minifier-terser|5.1.1|间接依赖|npm|
|picocolors|0.2.1|间接依赖|npm|
|punycode|2.3.0|间接依赖|npm|
|github.com/stathat/consistent|v1.0.0|直接依赖|go|
|@xtuc/ieee754|1.2.0|间接依赖|npm|
|github.com/lestrrat-go/iter|v1.0.2|间接依赖|go|
|@types/react-router-dom|5.3.1|直接依赖|npm|
|go.uber.org/multierr|v1.11.0|直接依赖|go|
|boolbase|1.0.0|间接依赖|npm|
|csstype|2.6.18|间接依赖|npm|
|mime-types|2.1.33|间接依赖|npm|
|import-local|3.0.3|间接依赖|npm|
|go.opentelemetry.io/proto/otlp|v0.7.0|间接依赖|go|
|github.com/spaolacci/murmur3|v1.1.0|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|webpack-cli|4.9.0|直接依赖|npm|
|entities|2.2.0|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|ts-loader|8.3.0|直接依赖|npm|
|github.com/hexops/gotextdiff|v1.0.3|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|github.com/shurcooL/httpgzip|v0.0.0-20190720172056-320755c1c1b0|直接依赖|go|
|go.opentelemetry.io/otel/trace|v0.20.0|间接依赖|go|
|npm-run-path|4.0.1|间接依赖|npm|
|github.com/gogo/protobuf|v1.3.2|直接依赖|go|
|chrome-trace-event|1.0.3|间接依赖|npm|
|renderkid|2.0.7|间接依赖|npm|
|go.uber.org/mock|v0.2.0|直接依赖|go|
|acorn|8.8.2|间接依赖|npm|
|github.com/google/gofuzz|v1.1.0|间接依赖|go|
|htmlparser2|6.1.0|间接依赖|npm|
|loader-utils|2.0.4|间接依赖|npm|
|google.golang.org/grpc|v1.54.0|直接依赖|go|
|ansi-regex|2.1.1|间接依赖|npm|
|events|3.3.0|间接依赖|npm|
|golang.org/x/crypto|v0.12.0|间接依赖|go|
|github.com/tikv/client-go/v2|v2.0.8-0.20230905034839-5dd12b06bc3c|直接依赖|go|
|google.golang.org/protobuf|v1.30.0|间接依赖|go|
|@types/react-router|5.1.17|间接依赖|npm|
|value-equal|1.0.1|间接依赖|npm|
|github.com/ngaut/sync2|v0.0.0-20141008032647-7a24ed77b2ef|直接依赖|go|
|github.com/mattn/go-isatty|v0.0.18|间接依赖|go|
|github.com/jcmturner/dnsutils/v2|v2.0.0|间接依赖|go|
|k8s.io/klog/v2|v2.90.1|间接依赖|go|
|react-dom|17.0.2|直接依赖|npm|
|github.com/google/go-cmp|v0.5.9|间接依赖|go|
|emojis-list|3.0.0|间接依赖|npm|
|commander|4.1.1|间接依赖|npm|
|github.com/Shopify/sarama|v1.29.0|直接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|github.com/coocood/bbloom|v0.0.0-20190830030839-58deb6228d64|间接依赖|go|
|github.com/go-kit/kit|v0.9.0|间接依赖|go|
|domelementtype|2.2.0|间接依赖|npm|
|github.com/tikv/pd/client|v0.0.0-20230728033905-31343e006842|直接依赖|go|
|github.com/tklauser/go-sysconf|v0.3.11|间接依赖|go|
|github.com/prometheus/client_golang|v1.16.0|直接依赖|go|
|github.com/yusufpapurcu/wmi|v1.2.3|间接依赖|go|
|github.com/prometheus/client_model|v0.4.0|直接依赖|go|
|github.com/olekukonko/tablewriter|v0.0.5|间接依赖|go|
|p-try|2.2.0|直接依赖|npm|
|github.com/soheilhy/cmux|v0.1.5|直接依赖|go|
|github.com/coreos/go-systemd/v22|v22.3.2|间接依赖|go|
|isexe|2.0.0|间接依赖|npm|
|resolve-pathname|3.0.0|间接依赖|npm|
|@webassemblyjs/wasm-opt|1.11.6|间接依赖|npm|
|github.com/pingcap/fn|v1.0.0|直接依赖|go|
|function-bind|1.1.1|间接依赖|npm|
|github.com/gostaticanalysis/comment|v1.4.2|间接依赖|go|
|mime-db|1.50.0|间接依赖|npm|
|github.com/xitongsys/parquet-go|v1.5.5-0.20201110004701-b09c49d6d457|直接依赖|go|
|github.com/fsouza/fake-gcs-server|v1.44.0|直接依赖|go|
|github.com/golangci/misspell|v0.4.0|直接依赖|go|
|golang.org/x/exp/typeparams|v0.0.0-20230224173230-c95f2b4c22f2|间接依赖|go|
|golang.org/x/text|v0.12.0|直接依赖|go|
|github.com/blacktear23/go-proxyprotocol|v1.0.6|直接依赖|go|
|dom-helpers|5.2.1|间接依赖|npm|
|clsx|1.1.1|间接依赖|npm|
|github.com/hashicorp/go-uuid|v1.0.2|间接依赖|go|
|github.com/emirpasic/gods|v1.18.1|直接依赖|go|
|github.com/bazelbuild/buildtools|v0.0.0-20230317132445-9c3c1fc0106e|直接依赖|go|
|react-router-dom|5.3.0|直接依赖|npm|
|github.com/google/uuid|v1.3.0|直接依赖|go|
|utila|0.4.0|间接依赖|npm|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|scheduler|0.20.2|间接依赖|npm|
|github.com/tklauser/numcpus|v0.6.0|间接依赖|go|
|github.com/kylelemons/godebug|v1.1.0|间接依赖|go|
|braces|3.0.2|间接依赖|npm|
|github.com/cznic/mathutil|v0.0.0-20181122101859-297441e03548|直接依赖|go|
|@discoveryjs/json-ext|0.5.5|间接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|isarray|0.0.1|间接依赖|npm|
|github.com/aliyun/alibaba-cloud-sdk-go|v1.61.1581|直接依赖|go|
|json-schema-traverse|0.4.1|间接依赖|npm|
|github.com/cheynewallace/tabby|v1.1.1|直接依赖|go|
|source-map|0.6.1|间接依赖|npm|
|github.com/charithe/durationcheck|v0.0.10|直接依赖|go|
|github.com/gostaticanalysis/analysisutil|v0.7.1|间接依赖|go|
|clean-css|4.2.3|间接依赖|npm|
|github.com/pingcap/tidb/parser|v0.0.0-20211011031125-9b13dc409c5e|直接依赖|go|
|github.com/bmatcuk/doublestar/v2|v2.0.4|间接依赖|go|
|github.com/pkg/browser|v0.0.0-20210115035449-ce105d075bb4|间接依赖|go|
|github.com/klauspost/compress|v1.16.5|直接依赖|go|
|pkg-dir|4.2.0|间接依赖|npm|
|esrecurse|4.3.0|间接依赖|npm|
|github.com/uber/jaeger-lib|v2.4.1+incompatible|间接依赖|go|
|picomatch|2.3.0|间接依赖|npm|
|tslib|2.3.1|间接依赖|npm|
|@types/react-dom|17.0.9|直接依赖|npm|
|github.com/pingcap/goleveldb|v0.0.0-20191226122134-f82aafb29989|间接依赖|go|
|@jridgewell/source-map|0.3.3|直接依赖|npm|
|envinfo|7.8.1|间接依赖|npm|
|github.com/golangci/gofmt|v0.0.0-20220901101216-f2edd75033f2|直接依赖|go|
|@material-ui/types|5.1.0|间接依赖|npm|
|github.com/shoenig/go-m1cpu|v0.1.6|间接依赖|go|
|sourcegraph.com/sourcegraph/appdash|v0.0.0-20190731080439-ebfcffb1b5c0|直接依赖|go|
|semver|7.3.5|间接依赖|npm|
|go.uber.org/zap|v1.25.0|直接依赖|go|
|github.com/jcmturner/gofork|v1.0.0|间接依赖|go|
|github.com/apache/skywalking-eyes|v0.4.0|直接依赖|go|
|github.com/lestrrat-go/jwx/v2|v2.0.11|直接依赖|go|
|github.com/segmentio/asm|v1.2.0|间接依赖|go|
|github.com/pkg/xattr|v0.4.9|间接依赖|go|
|randombytes|2.1.0|间接依赖|npm|
|github.com/ashanbrown/makezero|v1.1.1|直接依赖|go|
|micromatch|4.0.4|间接依赖|npm|
|google.golang.org/genproto|v0.0.0-20230410155749-daa745c078e1|间接依赖|go|
|github.com/prometheus/prometheus|v0.0.0-20190525122359-d20e84d0fb64|直接依赖|go|
|github.com/alecthomas/units|v0.0.0-20211218093645-b94a6e3cc137|间接依赖|go|
|neo-async|2.6.2|间接依赖|npm|
|github.com/butuzov/mirror|v1.1.0|直接依赖|go|
|github.com/lestrrat-go/httprc|v1.0.4|间接依赖|go|
|github.com/jonboulle/clockwork|v0.2.2|间接依赖|go|
|github.com/dustin/go-humanize|v1.0.0|间接依赖|go|
|strip-final-newline|2.0.0|间接依赖|npm|
|react|17.0.2|直接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/azidentity|v1.1.0|直接依赖|go|
|json-parse-even-better-errors|2.3.1|间接依赖|npm|
|estraverse|4.3.0|间接依赖|npm|
|go.opencensus.io|v0.24.0|直接依赖|go|
|readable-stream|2.3.7|间接依赖|npm|
|github.com/jellydator/ttlcache/v3|v3.0.1|直接依赖|go|
|github.com/HdrHistogram/hdrhistogram-go|v1.1.2|间接依赖|go|
|is-plain-object|2.0.4|间接依赖|npm|
|go.etcd.io/etcd/api/v3|v3.5.2|直接依赖|go|
|github.com/xiang90/probing|v0.0.0-20190116061207-43a291ad63a2|间接依赖|go|
|react-router|5.2.1|间接依赖|npm|
|golang.org/x/time|v0.3.0|直接依赖|go|
|domutils|2.8.0|间接依赖|npm|
|github.com/daixiang0/gci|v0.11.0|直接依赖|go|
|pascal-case|3.1.2|间接依赖|npm|
|ansi-styles|4.3.0|间接依赖|npm|
|github.com/timakin/bodyclose|v0.0.0-20230421092635-574207250966|直接依赖|go|
|go.opentelemetry.io/otel/sdk/export/metric|v0.20.0|间接依赖|go|
|go.uber.org/goleak|v1.2.1|直接依赖|go|
|history|4.10.1|间接依赖|npm|
|golang.org/x/net|v0.14.0|直接依赖|go|
|color-convert|2.0.1|间接依赖|npm|
|github.com/jingyugao/rowserrcheck|v1.1.1|直接依赖|go|
|lodash|4.17.21|间接依赖|npm|
|github.com/benbjohnson/clock|v1.3.5|间接依赖|go|
|go.etcd.io/etcd/client/v3|v3.5.2|直接依赖|go|
|github.com/VividCortex/ewma|v1.2.0|间接依赖|go|
|filesize|6.4.0|直接依赖|npm|
|big.js|5.2.2|间接依赖|npm|
|resolve-from|5.0.0|间接依赖|npm|
|shallow-clone|3.0.1|间接依赖|npm|
|github.com/kr/pretty|v0.3.1|间接依赖|go|
|safe-buffer|5.1.2|间接依赖|npm|
|github.com/Azure/go-ntlmssp|v0.0.0-20221128193559-754e69321358|间接依赖|go|
|strip-ansi|3.0.1|间接依赖|npm|
|lru-cache|6.0.0|间接依赖|npm|
|which|2.0.2|间接依赖|npm|
|jss-plugin-vendor-prefixer|10.8.0|间接依赖|npm|
|github.com/grpc-ecosystem/go-grpc-middleware|v1.3.0|直接依赖|go|
|terser-webpack-plugin|5.3.9|间接依赖|npm|
|gonum.org/v1/gonum|v0.8.2|间接依赖|go|
|go.opentelemetry.io/otel|v0.20.0|间接依赖|go|
|dot-case|3.0.4|间接依赖|npm|
|schema-utils|3.2.0|间接依赖|npm|
|golang.org/x/tools|v0.10.0|直接依赖|go|
|util-deprecate|1.0.2|间接依赖|npm|
|k8s.io/api|v0.27.2|直接依赖|go|
|github.com/mgechev/revive|v1.3.2|直接依赖|go|
|github.com/google/pprof|v0.0.0-20211122183932-1daafda22083|直接依赖|go|
|@babel/runtime|7.15.4|间接依赖|npm|
|github.com/lufia/plan9stats|v0.0.0-20230326075908-cb1d2100619a|间接依赖|go|
|fast-deep-equal|3.1.3|间接依赖|npm|
|json5|2.2.3|间接依赖|npm|
|@types/react|17.0.27|间接依赖|npm|
|cloud.google.com/go/compute/metadata|v0.2.3|间接依赖|go|
|p-locate|4.1.0|间接依赖|npm|
|github.com/Masterminds/semver|v1.5.0|直接依赖|go|
|github.com/eapache/go-xerial-snappy|v0.0.0-20180814174437-776d5712da21|间接依赖|go|
|github.com/imdario/mergo|v0.3.11|间接依赖|go|
|buffer-from|1.1.2|间接依赖|npm|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.3|间接依赖|go|
|is-number|7.0.0|间接依赖|npm|
|shebang-regex|3.0.0|间接依赖|npm|
|golang.org/x/exp|v0.0.0-20230711005742-c3f37128e5a4|直接依赖|go|
|human-signals|2.1.0|间接依赖|npm|
|hyphenate-style-name|1.0.4|间接依赖|npm|
|@types/scheduler|0.16.2|间接依赖|npm|
|jss-plugin-rule-value-function|10.8.0|间接依赖|npm|
|@jridgewell/gen-mapping|0.3.3|间接依赖|npm|
|he|1.2.0|间接依赖|npm|
|@material-ui/utils|4.11.2|间接依赖|npm|
|prop-types|15.7.2|间接依赖|npm|
|serialize-javascript|6.0.1|间接依赖|npm|
|github.com/jcmturner/gokrb5/v8|v8.4.2|间接依赖|go|
|github.com/lestrrat-go/blackmagic|v1.0.1|间接依赖|go|
|acorn-import-assertions|1.9.0|间接依赖|npm|
|github.com/eapache/queue|v1.1.0|间接依赖|go|
|github.com/cheggaaa/pb/v3|v3.0.8|直接依赖|go|
|github.com/klauspost/cpuid|v1.3.1|间接依赖|go|
|mini-create-react-context|0.4.1|间接依赖|npm|
|github.com/golang/snappy|v0.0.4|直接依赖|go|
|jss-plugin-default-unit|10.8.0|间接依赖|npm|
|github.com/kr/text|v0.2.0|间接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|间接依赖|go|
|ajv|6.12.6|间接依赖|npm|
|resolve|1.20.0|间接依赖|npm|
|modernc.org/parser|v1.1.0|直接依赖|go|
|github.com/gordonklaus/ineffassign|v0.0.0-20230610083614-0e73809eb601|直接依赖|go|
|google.golang.org/api|v0.114.0|直接依赖|go|
|go.opentelemetry.io/contrib|v0.20.0|间接依赖|go|
|github.com/docker/go-units|v0.4.0|直接依赖|go|
|github.com/golangci/gosec|v0.0.0-20180901114220-8afd9cbb6cfb|直接依赖|go|
|github.com/cznic/strutil|v0.0.0-20181122101858-275e90344537|直接依赖|go|
|github.com/carlmjohnson/flagext|v0.21.0|直接依赖|go|
|github.com/go-sql-driver/mysql|v1.7.1|直接依赖|go|
|color-name|1.1.4|间接依赖|npm|
|jss|10.8.0|间接依赖|npm|
|golang.org/x/oauth2|v0.8.0|直接依赖|go|
|github.com/ncw/directio|v1.0.5|间接依赖|go|
|locate-path|5.0.0|间接依赖|npm|
|github.com/googleapis/enterprise-certificate-proxy|v0.2.3|间接依赖|go|
|process-nextick-args|2.0.1|间接依赖|npm|
|@webassemblyjs/helper-wasm-bytecode|1.11.6|间接依赖|npm|
|github.com/gorilla/mux|v1.8.0|直接依赖|go|
|@material-ui/core|4.12.3|直接依赖|npm|
|json-bigint|1.0.0|直接依赖|npm|
|path-exists|4.0.0|间接依赖|npm|
|loader-runner|4.2.0|间接依赖|npm|
|github.com/cockroachdb/errors|v1.8.1|直接依赖|go|
|github.com/go-asn1-ber/asn1-ber|v1.5.4|间接依赖|go|
|cloud.google.com/go|v0.110.0|间接依赖|go|
|github.com/pingcap/kvproto|v0.0.0-20230825101459-934e842bfd6e|直接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|@webassemblyjs/helper-numbers|1.11.6|间接依赖|npm|
|node-releases|1.1.77|间接依赖|npm|
|github.com/fatanugraha/noloopclosure|v0.1.1|直接依赖|go|
|github.com/dgryski/go-farm|v0.0.0-20200201041132-a6ae2369ad13|直接依赖|go|
|github.com/DataDog/zstd|v1.4.5|间接依赖|go|
|github.com/BurntSushi/toml|v1.3.2|直接依赖|go|
|github.com/influxdata/tdigest|v0.0.1|直接依赖|go|
|interpret|2.2.0|间接依赖|npm|
|param-case|3.0.4|间接依赖|npm|
|v8-compile-cache|2.3.0|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|go.opentelemetry.io/otel/metric|v0.20.0|间接依赖|go|
|go.uber.org/goleak|v1.2.0|直接依赖|go|
|github.com/jcmturner/rpc/v2|v2.0.3|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|@jridgewell/set-array|1.1.2|间接依赖|npm|
|has-flag|4.0.0|间接依赖|npm|
|github.com/prometheus/common|v0.44.0|直接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|jss-plugin-nested|10.8.0|间接依赖|npm|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/kyoh86/exportloopref|v0.1.11|直接依赖|go|
|github.com/acarl005/stripansi|v0.0.0-20180116102854-5a71ef0e047d|间接依赖|go|
|golang.org/x/sync|v0.3.0|直接依赖|go|
|webpack-sources|3.2.3|间接依赖|npm|
|github.com/pingcap/failpoint|v0.0.0-20220801062533-2eaa32854a6c|直接依赖|go|
|cloud.google.com/go/iam|v0.13.0|间接依赖|go|
|go.etcd.io/etcd/client/v2|v2.305.2|间接依赖|go|
|css-vendor|2.0.8|间接依赖|npm|
|go.opentelemetry.io/contrib/instrumentation/google.golang.org/grpc/otelgrpc|v0.20.0|间接依赖|go|
|execa|5.1.1|间接依赖|npm|
|github.com/tiancaiamao/gp|v0.0.0-20221230034425-4025bc8a4d4a|直接依赖|go|
|github.com/bazelbuild/rules_go|v0.40.0|直接依赖|go|
|get-stream|6.0.1|间接依赖|npm|
|github.com/pingcap/tipb|v0.0.0-20230822064221-711da6fede03|直接依赖|go|
|github.com/google/skylark|v0.0.0-20181101142754-a5f7082aabed|直接依赖|go|
|golang.org/x/mod|v0.11.0|间接依赖|go|
|go.uber.org/automaxprocs|v1.5.3|直接依赖|go|
|github.com/google/btree|v1.1.2|直接依赖|go|
|github.com/pingcap/sysutil|v1.0.1-0.20230407040306-fb007c5aff21|直接依赖|go|
|@webassemblyjs/leb128|1.11.6|间接依赖|npm|
|@types/eslint|8.40.2|间接依赖|npm|
|github.com/aws/aws-sdk-go|v1.44.259|直接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway|v1.16.0|间接依赖|go|
|go.etcd.io/etcd/tests/v3|v3.5.2|直接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|直接依赖|go|
|github.com/pingcap/badger|v1.5.1-0.20230103063557-828f39b09b6d|直接依赖|go|
|@webassemblyjs/wasm-parser|1.11.6|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)