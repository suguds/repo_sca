# kopia/kopia安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696586540062171136.svg)](https://www.murphysec.com/console/report/1696586540011839488/1696586540062171136)

仓库描述：Cross-platform backup tool for Windows, macOS & Linux with fast, incremental backups, client-side end-to-end encryption, compression and data deduplication. CLI and GUI included.

仓库地址：[https://github.com/kopia/kopia](https://github.com/kopia/kopia)

| star：4123 | watch：46 | fork：246 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-30 01:51:44 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-30 02:12:15 | 组件总数：356 | 漏洞总数：4 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google Chrome Mojo 安全漏洞|越界写入|[MPS-1k76-5oja](https://www.oscs1024.com/hd/MPS-1k76-5oja)|CVE-2023-3732|高危|
|ejs 存在服务端模板注入漏洞|注入|[MPS-2023-10199](https://www.oscs1024.com/hd/MPS-2023-10199)|CVE-2023-29827|严重|
|Google Chrome 安全漏洞|UAF|[MPS-6dbf-7lyp](https://www.oscs1024.com/hd/MPS-6dbf-7lyp)|CVE-2023-3730|高危|
|Google Chrome 安全漏洞|UAF|[MPS-yu0a-l27w](https://www.oscs1024.com/hd/MPS-yu0a-l27w)|CVE-2023-3728|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|ejs|3.1.9||间接依赖|建议修复|C:1|H:0|M:0|L:0|
|electron|25.3.2|25.4.0|直接依赖|建议修复|C:0|H:3|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|ISC|26|Low|
|MIT|221|Low|
|Apache-2.0|54|Low|
|BSD-3-Clause|32|Low|
|BSD-2-Clause|13|Low|
|WTFPL|2|Low|
|CC0-1.0|1|Low|
|Python-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|shebang-regex|3.0.0|间接依赖|npm|
|minipass|5.0.0|间接依赖|npm|
|config-file-ts|0.2.4|间接依赖|npm|
|dmg-builder|24.6.3|间接依赖|npm|
|end-of-stream|1.4.4|间接依赖|npm|
|playwright|1.36.2|直接依赖|npm|
|assert-plus|1.0.0|间接依赖|npm|
|form-data|4.0.0|间接依赖|npm|
|lodash.escaperegexp|4.1.2|间接依赖|npm|
|github.com/hashicorp/cronexpr|v1.1.2|直接依赖|go|
|github.com/frankban/quicktest|v1.13.1|间接依赖|go|
|github.com/chromedp/cdproto|v0.0.0-20230802225258-3cf4e6d46a89|直接依赖|go|
|applescript|1.0.0|间接依赖|npm|
|github.com/golang-jwt/jwt/v5|v5.0.0|间接依赖|go|
|iconv-lite|0.6.3|间接依赖|npm|
|combined-stream|1.0.8|间接依赖|npm|
|cloud.google.com/go/compute/metadata|v0.2.3|间接依赖|go|
|builder-util-runtime|9.2.1|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|detect-node|2.1.0|间接依赖|npm|
|isbinaryfile|5.0.0|间接依赖|npm|
|stat-mode|1.0.0|间接依赖|npm|
|go.opentelemetry.io/otel/sdk|v1.16.0|直接依赖|go|
|buffer|5.7.1|间接依赖|npm|
|shebang-command|2.0.0|间接依赖|npm|
|keyv|4.5.2|间接依赖|npm|
|iconv-corefoundation|1.1.7|间接依赖|npm|
|github.com/Azure/go-autorest/autorest/adal|v0.9.16|间接依赖|go|
|balanced-match|1.0.0|间接依赖|npm|
|fsevents|2.3.2|间接依赖|npm|
|at-least-node|1.0.0|直接依赖|npm|
|github.com/skratchdot/open-golang|v0.0.0-20200116055534-eef842397966|直接依赖|go|
|commander|5.1.0|间接依赖|npm|
|core-util-is|1.0.2|间接依赖|npm|
|compare-version|0.1.2|间接依赖|npm|
|regenerator-runtime|0.13.11|间接依赖|npm|
|json-buffer|3.0.1|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|@types/events|3.0.0|间接依赖|npm|
|escape-string-regexp|4.0.0|间接依赖|npm|
|github.com/alessio/shellescape|v1.4.1|间接依赖|go|
|golang.org/x/oauth2|v0.11.0|直接依赖|go|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|source-map|0.6.1|间接依赖|npm|
|dotenv-expand|5.1.0|间接依赖|npm|
|mime-types|2.1.35|间接依赖|npm|
|go.uber.org/zap|v1.25.0|直接依赖|go|
|resolve-alpn|1.2.1|间接依赖|npm|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230807174057-1744710a1577|间接依赖|go|
|source-map-support|0.5.21|间接依赖|npm|
|github.com/mattn/go-isatty|v0.0.19|间接依赖|go|
|ajv-keywords|3.5.2|间接依赖|npm|
|get-stream|5.2.0|间接依赖|npm|
|github.com/prometheus/client_golang|v1.16.0|直接依赖|go|
|github.com/chromedp/chromedp|v0.9.2|直接依赖|go|
|@types/keyv|3.1.4|间接依赖|npm|
|@types/responselike|1.0.0|间接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|github.com/prometheus/client_model|v0.4.0|直接依赖|go|
|github.com/edsrzf/mmap-go|v1.1.0|直接依赖|go|
|safer-buffer|2.1.2|间接依赖|npm|
|err-code|2.0.3|间接依赖|npm|
|cross-spawn|7.0.3|间接依赖|npm|
|github.com/alecthomas/units|v0.0.0-20211218093645-b94a6e3cc137|直接依赖|go|
|@malept/flatpak-bundler|0.4.0|间接依赖|npm|
|date-fns|2.30.0|间接依赖|npm|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|universalify|0.1.2|间接依赖|npm|
|github.com/prometheus/common|v0.44.0|直接依赖|go|
|github.com/pkg/sftp|v1.13.6|直接依赖|go|
|github.com/dustinkirkland/golang-petname|v0.0.0-20191129215211-8e5a1ed0cff0|直接依赖|go|
|json5|2.2.3|间接依赖|npm|
|github.com/gobwas/ws|v1.2.1|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|tar|6.1.15|间接依赖|npm|
|cli-truncate|2.1.0|间接依赖|npm|
|go.opentelemetry.io/otel|v1.16.0|直接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/pierrec/lz4|v2.6.1+incompatible|直接依赖|go|
|async-exit-hook|2.0.1|间接依赖|npm|
|fd-slicer|1.1.0|间接依赖|npm|
|gopkg.in/kothar/go-backblaze.v0|v0.0.0-20210124194846-35409b867216|直接依赖|go|
|brace-expansion|1.1.11|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/azcore|v1.7.1|直接依赖|go|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|buffer-crc32|0.2.13|间接依赖|npm|
|http2-wrapper|1.0.3|间接依赖|npm|
|@electron/asar|3.2.4|间接依赖|npm|
|electron|25.3.2|直接依赖|npm|
|winreg|1.2.4|间接依赖|npm|
|@electron/osx-sign|1.0.4|间接依赖|npm|
|https-proxy-agent|5.0.1|间接依赖|npm|
|bluebird-lst|1.0.9|间接依赖|npm|
|dmg-license|1.0.11|间接依赖|npm|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|type-fest|0.13.1|间接依赖|npm|
|github.com/googleapis/gax-go/v2|v2.12.0|间接依赖|go|
|@szmarczak/http-timer|4.0.6|间接依赖|npm|
|go.opencensus.io|v0.24.0|间接依赖|go|
|go.opentelemetry.io/otel/trace|v1.16.0|直接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|plist|3.1.0|间接依赖|npm|
|glob|7.1.6|间接依赖|npm|
|simple-update-notifier|2.0.0|间接依赖|npm|
|@develar/schema-utils|2.6.5|间接依赖|npm|
|tmp-promise|3.0.3|间接依赖|npm|
|semver|7.5.4|间接依赖|npm|
|typescript|4.9.5|间接依赖|npm|
|auto-launch|5.0.6|直接依赖|npm|
|yargs|17.7.2|间接依赖|npm|
|concurrently|8.2.0|直接依赖|npm|
|@types/minimatch|3.0.3|间接依赖|npm|
|slice-ansi|3.0.0|间接依赖|npm|
|uuid|9.0.0|直接依赖|npm|
|google.golang.org/grpc|v1.57.0|直接依赖|go|
|github.com/klauspost/cpuid/v2|v2.2.5|间接依赖|go|
|fs.realpath|1.0.0|间接依赖|npm|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|@types/debug|4.1.8|间接依赖|npm|
|electron-builder|24.6.3|直接依赖|npm|
|@types/plist|3.0.2|间接依赖|npm|
|github.com/studio-b12/gowebdav|v0.9.0|直接依赖|go|
|@types/http-cache-semantics|4.0.1|间接依赖|npm|
|async|3.2.4|间接依赖|npm|
|mimic-response|1.0.1|间接依赖|npm|
|global-agent|3.0.0|间接依赖|npm|
|google.golang.org/protobuf|v1.31.0|直接依赖|go|
|rimraf|3.0.2|间接依赖|npm|
|@babel/runtime|7.22.5|间接依赖|npm|
|bluebird|3.7.2|间接依赖|npm|
|sax|1.2.4|间接依赖|npm|
|y18n|5.0.8|间接依赖|npm|
|github.com/pkg/browser|v0.0.0-20210911075715-681adbf594b8|间接依赖|go|
|github.com/googleapis/enterprise-certificate-proxy|v0.2.5|间接依赖|go|
|github.com/golang/protobuf|v1.5.3|直接依赖|go|
|builder-util|24.5.0|间接依赖|npm|
|github.com/gobwas/httphead|v0.1.0|间接依赖|go|
|golang.org/x/sync|v0.3.0|直接依赖|go|
|escalade|3.1.1|间接依赖|npm|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|inherits|2.0.4|间接依赖|npm|
|github.com/dustin/go-humanize|v1.0.1|间接依赖|go|
|github.com/danieljoos/wincred|v1.2.0|间接依赖|go|
|shell-quote|1.8.1|间接依赖|npm|
|yauzl|2.10.0|间接依赖|npm|
|progress|2.0.3|间接依赖|npm|
|pump|3.0.0|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|got|11.8.6|间接依赖|npm|
|cloud.google.com/go|v0.110.6|间接依赖|go|
|mkdirp|0.5.5|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|utf8-byte-length|1.0.4|间接依赖|npm|
|sprintf-js|1.1.2|间接依赖|npm|
|github.com/klauspost/pgzip|v1.2.6|直接依赖|go|
|buffer-from|1.1.2|间接依赖|npm|
|@xmldom/xmldom|0.8.10|间接依赖|npm|
|@malept/cross-spawn-promise|1.1.1|间接依赖|npm|
|golang.org/x/term|v0.11.0|直接依赖|go|
|github.com/google/uuid|v1.3.1|直接依赖|go|
|asar|3.2.0|直接依赖|npm|
|github.com/felixge/fgprof|v0.9.3|间接依赖|go|
|json-stringify-safe|5.0.1|间接依赖|npm|
|go.opentelemetry.io/otel/metric|v1.16.0|间接依赖|go|
|cloud.google.com/go/compute|v1.23.0|间接依赖|go|
|github.com/minio/md5-simd|v1.1.2|间接依赖|go|
|mime-db|1.52.0|间接依赖|npm|
|github.com/AzureAD/microsoft-authentication-library-for-go|v1.1.1|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230803162519-f966b187b2e5|间接依赖|go|
|github.com/godbus/dbus/v5|v5.1.0|间接依赖|go|
|github.com/go-logr/logr|v1.2.4|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|@types/glob|7.1.1|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/azidentity|v1.3.1|直接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|google.golang.org/genproto/googleapis/api|v0.0.0-20230803162519-f966b187b2e5|间接依赖|go|
|http-proxy-agent|5.0.0|间接依赖|npm|
|agent-base|6.0.2|间接依赖|npm|
|dir-compare|3.3.0|间接依赖|npm|
|gopkg.in/ini.v1|v1.67.0|间接依赖|go|
|chownr|2.0.0|间接依赖|npm|
|truncate-utf8-bytes|1.0.2|间接依赖|npm|
|color-convert|2.0.1|间接依赖|npm|
|string-width|4.2.3|间接依赖|npm|
|yallist|4.0.0|间接依赖|npm|
|ieee754|1.2.1|间接依赖|npm|
|github.com/gobwas/pool|v0.2.1|间接依赖|go|
|defer-to-connect|2.0.1|间接依赖|npm|
|verror|1.10.1|间接依赖|npm|
|http-cache-semantics|4.1.1|间接依赖|npm|
|github.com/zeebo/blake3|v0.2.3|直接依赖|go|
|decompress-response|6.0.0|间接依赖|npm|
|delayed-stream|1.0.0|间接依赖|npm|
|tmp|0.2.1|间接依赖|npm|
|golang.org/x/sys|v0.11.0|直接依赖|go|
|golang.org/x/xerrors|v0.0.0-20220907171357-04be3eba64a2|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|直接依赖|go|
|globalthis|1.0.3|间接依赖|npm|
|playwright-core|1.36.2|间接依赖|npm|
|debug|4.3.4|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|crc|3.8.0|间接依赖|npm|
|@sindresorhus/is|4.6.0|间接依赖|npm|
|retry|0.12.0|间接依赖|npm|
|cliui|8.0.1|间接依赖|npm|
|fs-minipass|2.1.0|间接依赖|npm|
|github.com/Azure/azure-pipeline-go|v0.2.3|间接依赖|go|
|ms|2.1.2|间接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|filelist|1.0.4|间接依赖|npm|
|github.com/foomo/htpasswd|v0.0.0-20200116085101-e3a90e78da9c|直接依赖|go|
|pend|1.2.0|间接依赖|npm|
|yargs-parser|21.1.1|间接依赖|npm|
|github.com/minio/minio-go/v7|v7.0.62|直接依赖|go|
|go.opentelemetry.io/otel/exporters/jaeger|v1.16.0|直接依赖|go|
|@types/cacheable-request|6.0.3|间接依赖|npm|
|github.com/xhit/go-str2duration/v2|v2.1.0|间接依赖|go|
|google.golang.org/api|v0.138.0|直接依赖|go|
|github.com/minio/sha256-simd|v1.0.1|间接依赖|go|
|github.com/alecthomas/kingpin/v2|v2.3.2|直接依赖|go|
|github.com/hanwen/go-fuse/v2|v2.3.0|直接依赖|go|
|github.com/sanity-io/litter|v1.5.5|直接依赖|go|
|github.com/pkg/profile|v1.7.0|直接依赖|go|
|go.uber.org/multierr|v1.11.0|直接依赖|go|
|color-name|1.1.4|间接依赖|npm|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|lowercase-keys|2.0.0|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|electron-log|4.4.8|直接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|github.com/fatih/color|v1.15.0|直接依赖|go|
|p-cancelable|2.1.1|间接依赖|npm|
|path-key|3.1.1|间接依赖|npm|
|@tootallnate/once|2.0.0|间接依赖|npm|
|jsonfile|4.0.0|间接依赖|npm|
|js-yaml|4.1.0|间接依赖|npm|
|wrap-ansi|7.0.0|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|ajv|6.12.6|间接依赖|npm|
|ejs|3.1.9|间接依赖|npm|
|extract-zip|2.0.1|间接依赖|npm|
|@electron/get|2.0.2|间接依赖|npm|
|github.com/stretchr/testify|v1.8.4|直接依赖|go|
|minizlib|2.1.2|间接依赖|npm|
|lru-cache|6.0.0|间接依赖|npm|
|supports-color|7.2.0|间接依赖|npm|
|github.com/klauspost/compress|v1.16.7|直接依赖|go|
|clone-response|1.0.3|间接依赖|npm|
|smart-buffer|4.2.0|间接依赖|npm|
|semver-compare|1.0.0|间接依赖|npm|
|responselike|2.0.1|间接依赖|npm|
|github.com/gofrs/flock|v0.8.1|直接依赖|go|
|github.com/kylelemons/godebug|v1.1.0|直接依赖|go|
|which|2.0.2|间接依赖|npm|
|lazy-val|1.0.5|间接依赖|npm|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|sanitize-filename|1.6.3|间接依赖|npm|
|github.com/prometheus/procfs|v0.10.1|间接依赖|go|
|cloud.google.com/go/storage|v1.32.0|直接依赖|go|
|fast-deep-equal|3.1.3|间接依赖|npm|
|app-builder-lib|24.6.3|间接依赖|npm|
|strip-ansi|6.0.1|间接依赖|npm|
|github.com/GehirnInc/crypt|v0.0.0-20230320061759-8cc1b52080c5|间接依赖|go|
|github.com/google/docsy|v0.7.0|间接依赖|go|
|chalk|4.1.2|间接依赖|npm|
|github.com/google/readahead|v0.0.0-20161222183148-eaceba169032|间接依赖|go|
|quick-lru|5.1.1|间接依赖|npm|
|github.com/kr/fs|v0.1.0|间接依赖|go|
|app-builder-bin|4.0.0|间接依赖|npm|
|github.com/zalando/go-keyring|v0.2.3|直接依赖|go|
|github.com/mattn/go-ieproxy|v0.0.1|间接依赖|go|
|define-properties|1.2.0|间接依赖|npm|
|punycode|2.3.0|间接依赖|npm|
|es6-error|4.1.1|间接依赖|npm|
|@playwright/test|1.36.2|直接依赖|npm|
|xmlbuilder|15.1.1|间接依赖|npm|
|github.com/golang/glog|v1.1.1|间接依赖|go|
|github.com/kopia/htmluibuild|v0.0.0-20230716183504-d78b44b3a9bd|直接依赖|go|
|temp-file|3.4.0|间接依赖|npm|
|promise-retry|2.0.1|间接依赖|npm|
|extsprintf|1.4.1|间接依赖|npm|
|@electron/universal|1.3.4|间接依赖|npm|
|github.com/chromedp/sysutil|v1.0.0|间接依赖|go|
|github.com/pquerna/ffjson|v0.0.0-20190930134022-aa0246cd15f7|间接依赖|go|
|lodash.isequal|4.5.0|间接依赖|npm|
|golang.org/x/crypto|v0.12.0|直接依赖|go|
|@types/yauzl|2.10.0|间接依赖|npm|
|golang.org/x/text|v0.12.0|直接依赖|go|
|golang.org/x/net|v0.14.0|直接依赖|go|
|untildify|3.0.3|间接依赖|npm|
|electron-publish|24.5.0|间接依赖|npm|
|dotenv|16.3.1|间接依赖|npm|
|read-config-file|6.3.2|间接依赖|npm|
|jake|10.8.7|间接依赖|npm|
|is-ci|3.0.1|间接依赖|npm|
|hosted-git-info|4.1.0|间接依赖|npm|
|github.com/natefinch/atomic|v1.0.1|直接依赖|go|
|github.com/chmduquesne/rollinghash|v4.0.0+incompatible|直接依赖|go|
|github.com/rs/xid|v1.5.0|间接依赖|go|
|minimist|1.2.8|间接依赖|npm|
|cacheable-request|7.0.2|间接依赖|npm|
|@types/verror|1.10.6|间接依赖|npm|
|cloud.google.com/go/iam|v1.1.1|间接依赖|go|
|cacheable-lookup|5.0.4|间接依赖|npm|
|ci-info|3.8.0|间接依赖|npm|
|github.com/google/fswalker|v0.3.0|直接依赖|go|
|github.com/golang-jwt/jwt/v4|v4.5.0|直接依赖|go|
|tiny-typed-emitter|2.1.0|间接依赖|npm|
|github.com/google/docsy/dependencies|v0.7.0|间接依赖|go|
|sumchecker|3.0.1|间接依赖|npm|
|@types/ms|0.7.31|间接依赖|npm|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|buffer-equal|1.0.1|间接依赖|npm|
|spawn-command|0.0.2|间接依赖|npm|
|emoji-regex|8.0.0|间接依赖|npm|
|tree-kill|1.2.2|间接依赖|npm|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|electron-is-dev|2.0.0|直接依赖|npm|
|github.com/google/pprof|v0.0.0-20230602150820-91b7bce49751|间接依赖|go|
|boolean|3.2.0|间接依赖|npm|
|@types/node|18.15.11|间接依赖|npm|
|github.com/sirupsen/logrus|v1.9.3|间接依赖|go|
|argparse|2.0.1|间接依赖|npm|
|normalize-url|6.1.0|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/internal|v1.3.0|间接依赖|go|
|require-directory|2.1.1|间接依赖|npm|
|chromium-pickle-js|0.2.0|间接依赖|npm|
|serialize-error|7.0.1|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|matcher|3.0.0|间接依赖|npm|
|electron-updater|6.1.4|直接依赖|npm|
|node-addon-api|1.7.2|间接依赖|npm|
|base64-js|1.5.1|间接依赖|npm|
|github.com/google/s2a-go|v0.1.5|间接依赖|go|
|inflight|1.0.6|间接依赖|npm|
|golang.org/x/mod|v0.12.0|直接依赖|go|
|graceful-fs|4.2.8|间接依赖|npm|
|github.com/gorilla/mux|v1.8.0|直接依赖|go|
|env-paths|2.2.1|间接依赖|npm|
|asynckit|0.4.0|间接依赖|npm|
|golang.org/x/exp|v0.0.0-20230522175609-2e198f4a06a1|直接依赖|go|
|fs-extra|8.1.0|间接依赖|npm|
|mime|2.6.0|间接依赖|npm|
|rxjs|7.8.1|间接依赖|npm|
|roarr|2.15.4|间接依赖|npm|
|github.com/Azure/azure-storage-blob-go|v0.15.0|直接依赖|go|
|github.com/tg123/go-htpasswd|v1.2.1|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/storage/azblob|v1.1.0|直接依赖|go|
|ansi-styles|4.3.0|间接依赖|npm|
|7zip-bin|5.1.1|间接依赖|npm|
|github.com/klauspost/reedsolomon|v1.11.8|直接依赖|go|
|@types/fs-extra|9.0.13|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|@electron/notarize|2.1.0|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)