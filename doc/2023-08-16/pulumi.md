# pulumi/pulumi安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1691513118894477312.svg)](https://www.murphysec.com/console/report/1691513118827368448/1691513118894477312)

仓库描述：Pulumi - Infrastructure as Code in any programming language. Build infrastructure intuitively on any cloud using familiar languages 🚀

仓库地址：[https://github.com/pulumi/pulumi](https://github.com/pulumi/pulumi)

| star：16938 | watch：173 | fork：939 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-12 11:13:13 | 许可证：- |
| 最近检测时间：2023-08-16 02:16:15 | 组件总数：854 | 漏洞总数：5 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|MPS-2021-3400|拒绝服务|[MPS-2021-3400](https://www.oscs1024.com/hd/MPS-2021-3400)|CVE-2021-23362|中危|
|MPS-2022-5166|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|MPS-2022-54598|ReDoS|[MPS-2022-54598](https://www.oscs1024.com/hd/MPS-2022-54598)||高危|
|MPS-2022-59845|拒绝服务|[MPS-2022-59845](https://www.oscs1024.com/hd/MPS-2022-59845)|CVE-2022-3517|高危|
|MPS-2023-9182|对异常条件的处理不恰当|[MPS-2023-9182](https://www.oscs1024.com/hd/MPS-2023-9182)|CVE-2023-1732|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|minimatch|3.0.4|3.0.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|mocha|9.2.2||直接依赖|建议修复|C:0|H:1|M:0|L:0|
|github.com/cloudflare/circl|v1.1.0|1.3.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|semver|7.3.7|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|semver|6.3.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|semver|5.7.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|hosted-git-info|2.8.8|3.0.8|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|ISC|65|Low|
|MIT|426|Low|
|BSD-2-Clause|12|Low|
|BSD-3-Clause|39|Low|
|CC0-1.0|3|Low|
|Apache-2.0|42|Low|
|0BSD|1|Low|
|Python-2.0|1|Low|
|CC-BY-3.0|1|Low|
|CC-BY-4.0|1|Low|
|GPL-2.0-or-later|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|y18n|5.0.8|间接依赖|npm|
|has-symbols|1.0.1|间接依赖|npm|
|@babel/helper-validator-identifier|7.19.1|间接依赖|npm|
|debug|4.3.3|间接依赖|npm|
|github.com/spf13/cast|v1.4.1|直接依赖|go|
|github.com/nightlyone/lockfile|v1.0.0|间接依赖|go|
|pkg-dir|7.0.0|直接依赖|npm|
|is-plain-obj|2.1.0|间接依赖|npm|
|github.com/AzureAD/microsoft-authentication-library-for-go|v0.4.0|间接依赖|go|
|estraverse|5.3.0|间接依赖|npm|
|aggregate-error|3.1.0|间接依赖|npm|
|eslint-module-utils|2.7.4|间接依赖|npm|
|is-core-module|2.12.1|间接依赖|npm|
|acorn-jsx|5.3.2|间接依赖|npm|
|spawn-wrap|2.0.0|间接依赖|npm|
|github.com/hashicorp/vault/api|v1.8.2|间接依赖|go|
|json-parse-better-errors|1.0.2|间接依赖|npm|
|string.prototype.trimstart|1.0.4|间接依赖|npm|
|github.com/zclconf/go-cty|v1.13.2|直接依赖|go|
|minimist|1.2.8|间接依赖|npm|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/go-git/go-billy/v5|v5.4.0|间接依赖|go|
|esrecurse|4.3.0|间接依赖|npm|
|semver|7.5.3|间接依赖|npm|
|asap|2.0.6|间接依赖|npm|
|ts-node|10.5.0|间接依赖|npm|
|object.assign|4.1.2|间接依赖|npm|
|google-protobuf|3.12.2|间接依赖|npm|
|type-detect|4.0.8|间接依赖|npm|
|gopkg.in/src-d/go-billy.v4|v4.3.2|间接依赖|go|
|globby|11.1.0|间接依赖|npm|
|mypy|0.991|间接依赖|pip|
|lodash.truncate|4.4.2|间接依赖|npm|
|@protobufjs/utf8|1.1.0|间接依赖|npm|
|github.com/google/shlex|v0.0.0-20191202100458-e7afc7fbc510|直接依赖|go|
|readdirp|3.6.0|间接依赖|npm|
|golang.org/x/term|v0.8.0|直接依赖|go|
|es-abstract|1.19.1|间接依赖|npm|
|resolve|1.22.1|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|log-symbols|4.1.0|间接依赖|npm|
|is-date-object|1.0.5|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|archy|1.0.0|间接依赖|npm|
|which|2.0.2|间接依赖|npm|
|@jridgewell/gen-mapping|0.3.3|间接依赖|npm|
|github.com/pulumi/pulumi-java/pkg|v0.9.0|直接依赖|go|
|process-on-spawn|1.0.0|间接依赖|npm|
|nyc|15.1.0|直接依赖|npm|
|@babel/helper-validator-option|7.21.0|间接依赖|npm|
|buffer-from|1.1.2|间接依赖|npm|
|is-weakref|1.0.2|间接依赖|npm|
|github.com/jbenet/go-context|v0.0.0-20150711004518-d14ea06fba99|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/s3shared|v1.13.9|间接依赖|go|
|astral-regex|2.0.0|间接依赖|npm|
|@sinonjs/samsam|6.1.1|间接依赖|npm|
|github.com/aws/aws-sdk-go-v2/credentials|v1.12.10|间接依赖|go|
|spdx-license-ids|3.0.12|间接依赖|npm|
|github.com/edsrzf/mmap-go|v1.1.0|直接依赖|go|
|go.opencensus.io|v0.24.0|间接依赖|go|
|inherits|2.0.4|间接依赖|npm|
|path-exists|4.0.0|间接依赖|npm|
|semver|7.5.2|直接依赖|npm|
|github.com/pgavlin/goldmark|v1.1.33-0.20200616210433-b5eb04559386|直接依赖|go|
|github.com/spf13/cobra|v1.7.0|直接依赖|go|
|diff|5.1.0|间接依赖|npm|
|github.com/pkg/browser|v0.0.0-20210115035449-ce105d075bb4|直接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230706204954-ccb25ca9f130|间接依赖|go|
|color-convert|2.0.1|间接依赖|npm|
|github.com/apparentlymart/go-textseg/v13|v13.0.0|间接依赖|go|
|@babel/highlight|7.18.6|间接依赖|npm|
|github.com/xeipuuv/gojsonpointer|v0.0.0-20180127040702-4e3ac2762d5f|间接依赖|go|
|github.com/power-devops/perfstat|v0.0.0-20210106213030-5aafc221ea8c|间接依赖|go|
|@opentelemetry/semantic-conventions|1.14.0|间接依赖|npm|
|glob|7.2.0|间接依赖|npm|
|object.getownpropertydescriptors|2.1.0|间接依赖|npm|
|black|1.0.0|间接依赖|pip|
|convert-source-map|1.9.0|间接依赖|npm|
|js-yaml|4.1.0|间接依赖|npm|
|which-boxed-primitive|1.0.2|间接依赖|npm|
|strip-ansi|6.0.1|间接依赖|npm|
|golang.org/x/sync|v0.2.0|直接依赖|go|
|escape-string-regexp|1.0.5|间接依赖|npm|
|github.com/AlecAivazis/survey/v2|v2.0.5|直接依赖|go|
|strip-final-newline|2.0.0|间接依赖|npm|
|@opentelemetry/resources|1.7.0|直接依赖|npm|
|js-yaml|3.14.1|直接依赖|npm|
|github.com/json-iterator/go|v1.1.12|直接依赖|go|
|@tsconfig/node12|1.0.9|间接依赖|npm|
|golang.org/x/time|v0.3.0|间接依赖|go|
|sphinx_rtd_theme|0.5.2|间接依赖|pip|
|github.com/sergi/go-diff|v1.2.0|间接依赖|go|
|cloud.google.com/go/compute/metadata|v0.2.3|间接依赖|go|
|has-symbols|1.0.3|间接依赖|npm|
|buffer-from|1.1.1|间接依赖|npm|
|github.com/aws/aws-sdk-go-v2/service/internal/accept-encoding|v1.9.3|间接依赖|go|
|@typescript-eslint/eslint-plugin|4.33.0|直接依赖|npm|
|natural-compare|1.4.0|间接依赖|npm|
|es-abstract|1.20.1|间接依赖|npm|
|semver|5.7.1|间接依赖|npm|
|fast-levenshtein|2.0.6|间接依赖|npm|
|github.com/mattn/go-isatty|v0.0.16|间接依赖|go|
|ts-node|7.0.1|直接依赖|npm|
|table|6.8.0|间接依赖|npm|
|github.com/Microsoft/go-winio|v0.5.2|直接依赖|go|
|github.com/go-git/gcfg|v1.5.0|间接依赖|go|
|github.com/hashicorp/go-cleanhttp|v0.5.2|间接依赖|go|
|strip-bom|4.0.0|间接依赖|npm|
|github.com/iancoleman/strcase|v0.2.0|直接依赖|go|
|p-try|2.2.0|间接依赖|npm|
|hasha|5.2.2|间接依赖|npm|
|github.com/pgavlin/diff|v0.0.0-20230503175810-113847418e2e|直接依赖|go|
|typescript|4.5.5|间接依赖|npm|
|github.com/pulumi/pulumi/sdk/v3|v3.78.1|直接依赖|go|
|github.com/zclconf/go-cty|v1.12.1|间接依赖|go|
|@types/node|18.7.18|间接依赖|npm|
|github.com/golang/protobuf|v1.5.3|直接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|直接依赖|go|
|ms|2.1.2|间接依赖|npm|
|json5|2.2.3|间接依赖|npm|
|@opentelemetry/api|1.2.0|直接依赖|npm|
|github.com/Azure/go-ansiterm|v0.0.0-20210617225240-d185dfc1b5a1|间接依赖|go|
|github.com/nxadm/tail|v1.4.8|直接依赖|go|
|resolve-from|4.0.0|间接依赖|npm|
|indent-string|4.0.0|间接依赖|npm|
|mockpackage|1.0.0|直接依赖|npm|
|github.com/hashicorp/errwrap|v1.0.0|间接依赖|go|
|gopkg.in/square/go-jose.v2|v2.6.0|间接依赖|go|
|golang.org/x/oauth2|v0.8.0|直接依赖|go|
|@cspotcode/source-map-support|0.7.0|间接依赖|npm|
|github.com/mitchellh/mapstructure|v1.5.0|间接依赖|go|
|@babel/helper-simple-access|7.20.2|间接依赖|npm|
|type-check|0.4.0|间接依赖|npm|
|github.com/aws/aws-sdk-go-v2/feature/ec2/imds|v1.12.9|间接依赖|go|
|browser-stdout|1.3.1|间接依赖|npm|
|@opentelemetry/core|1.7.0|间接依赖|npm|
|@opentelemetry/instrumentation|0.32.0|直接依赖|npm|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|v8-compile-cache-lib|3.0.0|间接依赖|npm|
|debug|2.6.9|间接依赖|npm|
|cloud.google.com/go|v0.110.4|间接依赖|go|
|p-limit|2.3.0|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|unbox-primitive|1.0.2|间接依赖|npm|
|google.golang.org/protobuf|v1.31.0|直接依赖|go|
|@babel/helper-hoist-variables|7.18.6|间接依赖|npm|
|eslint-utils|3.0.0|间接依赖|npm|
|github.com/cheggaaa/pb|v1.0.29|直接依赖|go|
|glob|7.1.6|间接依赖|npm|
|merge2|1.4.1|间接依赖|npm|
|github.com/google/uuid|v1.3.0|间接依赖|go|
|supports-preserve-symlinks-flag|1.0.0|间接依赖|npm|
|human-signals|2.1.0|间接依赖|npm|
|@opentelemetry/propagator-jaeger|1.14.0|间接依赖|npm|
|caching-transform|4.0.0|间接依赖|npm|
|array-union|2.1.0|间接依赖|npm|
|y18n|4.0.3|间接依赖|npm|
|readdir-scoped-modules|1.1.0|间接依赖|npm|
|github.com/xeipuuv/gojsonschema|v1.2.0|直接依赖|go|
|github.com/dimchansky/utfbom|v1.1.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/ini|v1.3.16|间接依赖|go|
|github.com/xeipuuv/gojsonreference|v0.0.0-20180127040603-bd5ef7bd5415|间接依赖|go|
|@opentelemetry/context-async-hooks|1.14.0|间接依赖|npm|
|cliui|6.0.0|间接依赖|npm|
|github.com/spf13/cast|v1.5.0|间接依赖|go|
|yargs|16.2.0|间接依赖|npm|
|@types/long|4.0.2|间接依赖|npm|
|github.com/aws/smithy-go|v1.13.5|间接依赖|go|
|is-stream|2.0.1|间接依赖|npm|
|has-symbols|1.0.2|间接依赖|npm|
|tslib|1.14.1|间接依赖|npm|
|github.com/pulumi/pulumi/sdk/v3|v3.40.1|直接依赖|go|
|globals|13.17.0|间接依赖|npm|
|eslint-plugin-import|2.26.0|直接依赖|npm|
|@babel/traverse|7.21.4|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|set-blocking|2.0.0|间接依赖|npm|
|github.com/spf13/cobra|v1.5.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sts|v1.16.10|直接依赖|go|
|@opentelemetry/semantic-conventions|1.6.0|间接依赖|npm|
|regexp.prototype.flags|1.4.3|间接依赖|npm|
|ms|2.0.0|间接依赖|npm|
|github.com/rivo/uniseg|v0.4.0|间接依赖|go|
|github.com/dustin/go-humanize|v1.0.0|直接依赖|go|
|github.com/hashicorp/go-multierror|v1.1.1|直接依赖|go|
|github.com/aead/chacha20|v0.0.0-20180709150244-8b13a72661da|间接依赖|go|
|@opentelemetry/sdk-trace-base|1.7.0|直接依赖|npm|
|github.com/imdario/mergo|v0.3.13|间接依赖|go|
|@opentelemetry/resources|1.14.0|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|p-locate|5.0.0|间接依赖|npm|
|test-exclude|6.0.0|间接依赖|npm|
|istanbul-lib-report|3.0.0|间接依赖|npm|
|@protobufjs/eventemitter|1.1.0|间接依赖|npm|
|github.com/aws/aws-sdk-go-v2/feature/s3/manager|v1.11.21|间接依赖|go|
|github.com/rogpeppe/go-internal|v1.8.1|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|间接依赖|go|
|github.com/segmentio/asm|v1.1.3|间接依赖|go|
|@typescript-eslint/visitor-keys|4.33.0|间接依赖|npm|
|sourcegraph.com/sourcegraph/appdash|v0.0.0-20211028080628-e2786a622600|直接依赖|go|
|typedarray-to-buffer|3.1.5|间接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|@typescript-eslint/scope-manager|4.33.0|间接依赖|npm|
|github.com/pulumi/pulumi/sdk/v3|v3.48.0|直接依赖|go|
|google.golang.org/api|v0.126.0|直接依赖|go|
|github.com/Azure/go-autorest/logger|v0.2.1|间接依赖|go|
|github.com/mitchellh/go-wordwrap|v1.0.1|间接依赖|go|
|release-zalgo|1.0.0|间接依赖|npm|
|@pulumi/query|0.3.0|直接依赖|npm|
|@opentelemetry/core|1.14.0|间接依赖|npm|
|github.com/Azure/go-autorest/tracing|v0.6.0|间接依赖|go|
|find-up|5.0.0|间接依赖|npm|
|object-keys|1.1.1|间接依赖|npm|
|estraverse|4.3.0|间接依赖|npm|
|github.com/mitchellh/go-testing-interface|v1.14.1|间接依赖|go|
|ini|2.0.0|直接依赖|npm|
|eslint-visitor-keys|2.1.0|间接依赖|npm|
|tsconfig-paths|3.14.1|间接依赖|npm|
|get-stream|6.0.1|间接依赖|npm|
|argparse|2.0.1|间接依赖|npm|
|golang.org/x/net|v0.10.0|直接依赖|go|
|@babel/helper-split-export-declaration|7.18.6|间接依赖|npm|
|github.com/stretchr/testify|v1.8.1|直接依赖|go|
|decamelize|4.0.0|间接依赖|npm|
|util-promisify|2.1.0|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|github.com/pulumi/pulumi-random/sdk/v4|v4.8.0|直接依赖|go|
|github.com/muesli/cancelreader|v0.2.2|直接依赖|go|
|path-exists|5.0.0|间接依赖|npm|
|@grpc/grpc-js|1.8.16|直接依赖|npm|
|mvdan.cc/gofumpt|v0.1.0|间接依赖|go|
|@babel/helper-environment-visitor|7.18.9|间接依赖|npm|
|github.com/blang/semver|v3.5.1+incompatible|直接依赖|go|
|gopkg.in/warnings.v0|v0.1.2|间接依赖|go|
|resolve-from|5.0.0|间接依赖|npm|
|gopkg.in/check.v1|v1.0.0-20201130134442-10cb98267c6c|间接依赖|go|
|acorn|7.4.1|间接依赖|npm|
|google.golang.org/grpc|v1.57.0|直接依赖|go|
|@types/node|10.17.27|间接依赖|npm|
|graceful-fs|4.2.9|间接依赖|npm|
|github.com/stretchr/testify|v1.8.0|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.12|间接依赖|go|
|lukechampine.com/frand|v1.4.2|直接依赖|go|
|levn|0.4.1|间接依赖|npm|
|github.com/hashicorp/go-sockaddr|v1.0.2|间接依赖|go|
|is-shared-array-buffer|1.0.2|间接依赖|npm|
|word-wrap|1.2.4|间接依赖|npm|
|@typescript-eslint/parser|4.33.0|直接依赖|npm|
|github.com/mattn/go-isatty|v0.0.14|间接依赖|go|
|define-properties|1.1.4|间接依赖|npm|
|flat|5.0.2|间接依赖|npm|
|es-shim-unscopables|1.0.0|间接依赖|npm|
|github.com/hashicorp/hcl/v2|v2.16.2|直接依赖|go|
|github.com/hashicorp/go-secure-stdlib/strutil|v0.1.2|间接依赖|go|
|@protobufjs/inquire|1.1.0|间接依赖|npm|
|slash|3.0.0|间接依赖|npm|
|github.com/stretchr/testify|v1.8.3|直接依赖|go|
|minimatch|3.0.4|间接依赖|npm|
|@nodelib/fs.scandir|2.1.5|间接依赖|npm|
|example.com/plugin|v1.2.3|直接依赖|go|
|github.com/pulumi/pulumi/sdk/v3|v3.60.1|直接依赖|go|
|github.com/hashicorp/go-plugin|v1.4.6|间接依赖|go|
|github.com/hashicorp/go-retryablehttp|v0.7.1|间接依赖|go|
|github.com/Azure/go-autorest/autorest/adal|v0.9.21|间接依赖|go|
|argparse|1.0.10|间接依赖|npm|
|@types/ini|1.3.31|直接依赖|npm|
|golang.org/x/sys|v0.9.0|间接依赖|go|
|has-bigints|1.0.2|间接依赖|npm|
|golang.org/x/crypto|v0.3.0|间接依赖|go|
|sourcegraph.com/sourcegraph/appdash|v0.0.0-20190731080439-ebfcffb1b5c0|间接依赖|go|
|github.com/tklauser/go-sysconf|v0.3.10|间接依赖|go|
|github.com/Netflix/go-expect|v0.0.0-20220104043353-73e0943537d2|直接依赖|go|
|github.com/shurcooL/vfsgen|v0.0.0-20200824052919-0d455de96546|间接依赖|go|
|safe-buffer|5.2.1|间接依赖|npm|
|github.com/pulumi/pulumi/sdk/v3|v3.51.1|直接依赖|go|
|github.com/hexops/gotextdiff|v1.0.3|直接依赖|go|
|@grpc/proto-loader|0.7.5|间接依赖|npm|
|@pulumi/pulumi|3.73.0|直接依赖|npm|
|github.com/cloudflare/circl|v1.3.3|间接依赖|go|
|github.com/pulumi/pulumi/pkg/v3|v3.0.0-00010101000000-000000000000|直接依赖|go|
|isarray|0.0.1|间接依赖|npm|
|github.com/davecgh/go-spew|v1.1.1|直接依赖|go|
|validate-npm-package-license|3.0.4|间接依赖|npm|
|is-binary-path|2.1.0|间接依赖|npm|
|find-up|4.1.0|间接依赖|npm|
|github.com/agext/levenshtein|v1.2.1|间接依赖|go|
|object-inspect|1.12.0|间接依赖|npm|
|@ampproject/remapping|2.2.1|间接依赖|npm|
|es-array-method-boxes-properly|1.0.0|间接依赖|npm|
|github.com/hexops/autogold|v1.3.0|直接依赖|go|
|@types/semver|5.5.0|直接依赖|npm|
|foreground-child|2.0.0|间接依赖|npm|
|@types/json-schema|7.0.11|间接依赖|npm|
|github.com/spf13/cobra|v1.4.0|间接依赖|go|
|diff|5.0.0|间接依赖|npm|
|github.com/pjbgf/sha1cd|v0.3.0|间接依赖|go|
|github.com/go-git/go-git/v5|v5.6.0|直接依赖|go|
|is-core-module|2.9.0|间接依赖|npm|
|typescript|3.8.3|直接依赖|npm|
|github.com/pulumi/pulumi/sdk/v3|v3.65.1|直接依赖|go|
|@types/sinonjs__fake-timers|8.1.2|间接依赖|npm|
|node-preload|0.2.1|间接依赖|npm|
|spdx-exceptions|2.3.0|间接依赖|npm|
|flatted|3.2.7|间接依赖|npm|
|github.com/lufia/plan9stats|v0.0.0-20211012122336-39d0f177ccd0|间接依赖|go|
|object.getownpropertydescriptors|2.1.4|间接依赖|npm|
|@tsconfig/node16|1.0.2|间接依赖|npm|
|github.com/santhosh-tekuri/jsonschema/v5|v5.0.0|直接依赖|go|
|make-dir|3.1.0|间接依赖|npm|
|myst-parser|0.15.1|间接依赖|pip|
|github.com/rivo/uniseg|v0.2.0|间接依赖|go|
|github.com/opentracing/basictracer-go|v1.0.0|间接依赖|go|
|is-windows|1.0.2|间接依赖|npm|
|jsesc|2.5.2|间接依赖|npm|
|github.com/sabhiram/go-gitignore|v0.0.0-20210923224102-525f6e181f06|直接依赖|go|
|he|1.2.0|间接依赖|npm|
|ajv|6.12.6|间接依赖|npm|
|github.com/aws/aws-sdk-go|v1.44.298|直接依赖|go|
|flat-cache|3.0.4|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/azcore|v1.1.1|间接依赖|go|
|string.prototype.trimend|1.0.1|间接依赖|npm|
|github.com/natefinch/atomic|v1.0.1|直接依赖|go|
|google.golang.org/genproto/googleapis/api|v0.0.0-20230706204954-ccb25ca9f130|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/presigned-url|v1.9.9|间接依赖|go|
|@babel/compat-data|7.21.4|间接依赖|npm|
|@jridgewell/trace-mapping|0.3.18|间接依赖|npm|
|yallist|3.1.1|间接依赖|npm|
|gopkg.in/yaml.v3|v3.0.1|直接依赖|go|
|path-to-regexp|1.8.0|间接依赖|npm|
|github.com/armon/go-radix|v1.0.0|间接依赖|go|
|serialize-javascript|6.0.0|间接依赖|npm|
|@types/normalize-package-data|2.4.1|直接依赖|npm|
|@typescript-eslint/typescript-estree|4.33.0|间接依赖|npm|
|diff|3.5.0|间接依赖|npm|
|@eslint/eslintrc|0.4.3|间接依赖|npm|
|github.com/Azure/go-autorest/autorest/azure/cli|v0.4.6|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.0.1|间接依赖|go|
|@rometools/cli-linux-x64|12.1.0|直接依赖|npm|
|github.com/googleapis/enterprise-certificate-proxy|v0.2.3|间接依赖|go|
|coverage|6.0.2|间接依赖|pip|
|gopkg.in/yaml.v3|v3.0.0|间接依赖|go|
|to-regex-range|5.0.1|间接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|github.com/Azure/go-autorest/autorest/azure/auth|v0.5.11|间接依赖|go|
|@types/node|18.0.0|间接依赖|npm|
|github.com/spf13/cobra|v1.6.1|直接依赖|go|
|micromatch|4.0.5|间接依赖|npm|
|caniuse-lite|1.0.30001477|间接依赖|npm|
|p-limit|3.1.0|间接依赖|npm|
|google-protobuf|3.20.1|间接依赖|npm|
|resolve|1.22.2|间接依赖|npm|
|object-inspect|1.12.2|间接依赖|npm|
|github.com/gorilla/mux|v1.8.0|直接依赖|go|
|github.com/cheggaaa/pb|v1.0.18|间接依赖|go|
|github.com/mxschmitt/golang-combinations|v1.0.0|直接依赖|go|
|gensync|1.0.0-beta.2|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|glob|7.2.3|间接依赖|npm|
|semver|7.3.7|间接依赖|npm|
|is-regex|1.1.4|间接依赖|npm|
|github.com/cloudflare/circl|v1.1.0|间接依赖|go|
|@logdna/tail-file|2.1.0|间接依赖|npm|
|define-properties|1.1.3|间接依赖|npm|
|object.assign|4.1.0|间接依赖|npm|
|eslint-import-resolver-node|0.3.6|间接依赖|npm|
|@grpc/grpc-js|1.3.8|间接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.14|间接依赖|npm|
|yargs-parser|20.2.9|间接依赖|npm|
|@babel/helpers|7.21.0|间接依赖|npm|
|functions-have-names|1.2.3|间接依赖|npm|
|@babel/template|7.20.7|间接依赖|npm|
|@babel/parser|7.21.4|间接依赖|npm|
|github.com/jmespath/go-jmespath|v0.4.0|间接依赖|go|
|get-package-type|0.1.0|间接依赖|npm|
|github.com/kr/pretty|v0.3.1|间接依赖|go|
|locate-path|7.2.0|间接依赖|npm|
|progress|2.0.3|间接依赖|npm|
|golang.org/x/crypto|v0.3.1-0.20221117191849-2c476679df9a|直接依赖|go|
|github.com/sabhiram/go-gitignore|v0.0.0-20180611051255-d3107576ba94|间接依赖|go|
|require-directory|2.1.1|间接依赖|npm|
|is-number-object|1.0.7|间接依赖|npm|
|mkdirp|0.5.5|直接依赖|npm|
|spdx-license-ids|3.0.5|间接依赖|npm|
|github.com/google/wire|v0.5.0|间接依赖|go|
|json5|1.0.2|间接依赖|npm|
|graceful-fs|4.2.4|间接依赖|npm|
|@opentelemetry/instrumentation-grpc|0.32.0|直接依赖|npm|
|object.getownpropertydescriptors|2.1.3|间接依赖|npm|
|fromentries|1.3.2|间接依赖|npm|
|istanbul-lib-coverage|3.2.0|间接依赖|npm|
|cross-spawn|7.0.3|间接依赖|npm|
|is-core-module|2.10.0|间接依赖|npm|
|is-unicode-supported|0.1.0|间接依赖|npm|
|github.com/rivo/uniseg|v0.4.4|直接依赖|go|
|github.com/HdrHistogram/hdrhistogram-go|v1.1.2|间接依赖|go|
|github.com/sergi/go-diff|v1.1.0|间接依赖|go|
|spdx-license-ids|3.0.11|间接依赖|npm|
|github.com/hashicorp/go-immutable-radix|v1.3.1|间接依赖|go|
|@protobufjs/codegen|2.0.4|间接依赖|npm|
|get-intrinsic|1.1.2|间接依赖|npm|
|@opentelemetry/exporter-zipkin|1.7.0|直接依赖|npm|
|@rometools/cli-win32-x64|12.1.0|直接依赖|npm|
|source-map-support|0.5.21|间接依赖|npm|
|string-width|4.2.3|间接依赖|npm|
|shebang-command|2.0.0|间接依赖|npm|
|istanbul-lib-hook|3.0.0|间接依赖|npm|
|github.com/hashicorp/hcl/v2|v2.16.1|直接依赖|go|
|strip-bom|3.0.0|间接依赖|npm|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|go.uber.org/atomic|v1.9.0|间接依赖|go|
|sphinx|4.0.2|间接依赖|pip|
|es6-error|4.1.1|间接依赖|npm|
|yocto-queue|0.1.0|间接依赖|npm|
|shimmer|1.2.1|间接依赖|npm|
|@istanbuljs/load-nyc-config|1.1.0|间接依赖|npm|
|github.com/mitchellh/go-wordwrap|v0.0.0-20150314170334-ad45545899c7|间接依赖|go|
|@opentelemetry/sdk-trace-node|1.7.0|直接依赖|npm|
|default-require-extensions|3.0.1|间接依赖|npm|
|istanbul-reports|3.1.5|间接依赖|npm|
|workerpool|6.2.0|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go|v66.0.0+incompatible|间接依赖|go|
|read-package-tree|5.3.1|直接依赖|npm|
|github.com/grpc-ecosystem/grpc-opentracing|v0.0.0-20180507213350-8e809c8a8645|直接依赖|go|
|ajv|8.11.0|间接依赖|npm|
|slice-ansi|4.0.0|间接依赖|npm|
|github.com/golang/glog|v1.1.0|直接依赖|go|
|github.com/creack/pty|v1.1.17|直接依赖|go|
|is-callable|1.2.4|间接依赖|npm|
|grpcio|1.56.2|间接依赖|pip|
|cloud.google.com/go/compute|v1.20.1|间接依赖|go|
|golang.org/x/crypto|v0.9.0|间接依赖|go|
|doctrine|3.0.0|间接依赖|npm|
|is-negative-zero|2.0.2|间接依赖|npm|
|fast-glob|3.2.12|间接依赖|npm|
|@humanwhocodes/object-schema|1.2.1|间接依赖|npm|
|sprintf-js|1.0.3|间接依赖|npm|
|github.com/moby/term|v0.0.0-20210619224110-3f7ff695adc6|直接依赖|go|
|ansi-styles|4.3.0|间接依赖|npm|
|supports-color|7.2.0|间接依赖|npm|
|@humanwhocodes/config-array|0.5.0|间接依赖|npm|
|array.prototype.flat|1.3.0|间接依赖|npm|
|acorn|8.7.0|间接依赖|npm|
|github.com/djherbis/times|v1.5.0|直接依赖|go|
|github.com/pulumi/pulumi/sdk/v3|v3.73.0|直接依赖|go|
|nanoid|3.3.1|间接依赖|npm|
|emoji-regex|8.0.0|间接依赖|npm|
|ignore|5.2.0|间接依赖|npm|
|@babel/helper-module-transforms|7.21.2|间接依赖|npm|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|shebang-regex|3.0.0|间接依赖|npm|
|find-up|6.3.0|间接依赖|npm|
|ansi-colors|4.1.1|间接依赖|npm|
|graceful-fs|4.2.11|间接依赖|npm|
|esquery|1.4.0|间接依赖|npm|
|json-stable-stringify-without-jsonify|1.0.1|间接依赖|npm|
|cliui|7.0.4|间接依赖|npm|
|hosted-git-info|4.1.0|间接依赖|npm|
|require-in-the-middle|5.2.0|间接依赖|npm|
|require-from-string|2.0.2|直接依赖|npm|
|@logdna/tail-file|2.2.0|直接依赖|npm|
|side-channel|1.0.4|间接依赖|npm|
|is-shared-array-buffer|1.0.1|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|@jridgewell/resolve-uri|3.1.0|间接依赖|npm|
|@protobufjs/base64|1.1.2|间接依赖|npm|
|github.com/golang-jwt/jwt|v3.2.1+incompatible|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|pkg-dir|4.2.0|间接依赖|npm|
|github.com/hexops/valast|v1.4.0|间接依赖|go|
|github.com/google/s2a-go|v0.1.4|间接依赖|go|
|github.com/pgavlin/text|v0.0.0-20230428184845-84c285f11d2f|间接依赖|go|
|get-symbol-description|1.0.0|间接依赖|npm|
|github.com/Azure/go-autorest/autorest|v0.11.28|间接依赖|go|
|github.com/kevinburke/ssh_config|v1.2.0|直接依赖|go|
|github.com/uber/jaeger-client-go|v2.22.1+incompatible|间接依赖|go|
|@protobufjs/pool|1.1.0|间接依赖|npm|
|Resource||间接依赖|pip|
|github.com/hashicorp/vault/sdk|v0.6.1|间接依赖|go|
|github.com/gofrs/uuid|v4.2.0+incompatible|直接依赖|go|
|yargs|15.4.1|间接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|github.com/mattn/go-runewidth|v0.0.8|间接依赖|go|
|yocto-queue|1.0.0|间接依赖|npm|
|@cspotcode/source-map-consumer|0.8.0|间接依赖|npm|
|rome|12.1.0|直接依赖|npm|
|punycode|2.1.1|间接依赖|npm|
|yargs-parser|20.2.4|间接依赖|npm|
|camelcase|6.3.0|间接依赖|npm|
|is-number|7.0.0|间接依赖|npm|
|@types/sinon|10.0.13|直接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|@nodelib/fs.walk|1.2.8|间接依赖|npm|
|functional-red-black-tree|1.0.1|间接依赖|npm|
|which-module|2.0.0|间接依赖|npm|
|prelude-ls|1.2.1|间接依赖|npm|
|github.com/aws/aws-sdk-go-v2/service/internal/checksum|v1.1.10|间接依赖|go|
|eslint-visitor-keys|1.3.0|间接依赖|npm|
|@types/js-yaml|3.12.7|直接依赖|npm|
|p-limit|4.0.0|间接依赖|npm|
|mkdirp|0.5.6|间接依赖|npm|
|ansi-colors|4.1.3|间接依赖|npm|
|github.com/src-d/gcfg|v1.4.0|间接依赖|go|
|github.com/acomagu/bufpipe|v1.0.3|间接依赖|go|
|Dict||间接依赖|pip|
|lru-cache|5.1.1|间接依赖|npm|
|eslint-scope|5.1.1|间接依赖|npm|
|github.com/stretchr/objx|v0.5.0|间接依赖|go|
|make-error|1.3.6|间接依赖|npm|
|object.assign|4.1.4|间接依赖|npm|
|github.com/aws/aws-sdk-go-v2|v1.17.3|直接依赖|go|
|github.com/shurcooL/go-goon|v0.0.0-20210110234559-7585751d9a17|间接依赖|go|
|spdx-expression-parse|3.0.1|间接依赖|npm|
|spdx-correct|3.1.1|间接依赖|npm|
|get-intrinsic|1.1.3|间接依赖|npm|
|object-inspect|1.8.0|间接依赖|npm|
|github.com/skeema/knownhosts|v1.1.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/kms|v1.18.1|直接依赖|go|
|es-to-primitive|1.2.1|间接依赖|npm|
|lru-cache|6.0.0|间接依赖|npm|
|type-fest|0.20.2|间接依赖|npm|
|github.com/nbutton23/zxcvbn-go|v0.0.0-20180912185939-ae427f1e4c1d|直接依赖|go|
|is-glob|4.0.3|间接依赖|npm|
|@opentelemetry/context-async-hooks|1.7.0|间接依赖|npm|
|semver|6.3.0|间接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|github.com/texttheater/golang-levenshtein|v1.0.1|直接依赖|go|
|github.com/ijc/Gotty|v0.0.0-20170406111628-a8b993ba6abd|直接依赖|go|
|source-map|0.6.1|间接依赖|npm|
|github.com/rogpeppe/go-internal|v1.9.0|直接依赖|go|
|debug|4.3.4|间接依赖|npm|
|cloud.google.com/go/storage|v1.30.1|直接依赖|go|
|doctrine|2.1.0|间接依赖|npm|
|module-details-from-path|1.0.3|间接依赖|npm|
|to-fast-properties|2.0.0|间接依赖|npm|
|github.com/fatih/color|v1.13.0|间接依赖|go|
|github.com/hashicorp/go-uuid|v1.0.3|间接依赖|go|
|github.com/google/go-querystring|v1.1.0|直接依赖|go|
|ignore|4.0.6|间接依赖|npm|
|@typescript-eslint/types|4.33.0|间接依赖|npm|
|example.com/dep|v1.5.0|直接依赖|go|
|require-main-filename|2.0.0|间接依赖|npm|
|text-table|0.2.0|间接依赖|npm|
|pgregory.net/rapid|v0.5.5|直接依赖|go|
|json-parse-even-better-errors|2.3.1|间接依赖|npm|
|strip-json-comments|3.1.1|间接依赖|npm|
|github.com/pulumi/pulumi/sdk/v3|v3.62.0|直接依赖|go|
|camelcase|5.3.1|间接依赖|npm|
|locate-path|6.0.0|间接依赖|npm|
|github.com/pulumi/pulumi-random/sdk/v4|v4.8.2|直接依赖|go|
|path-is-absolute|1.0.1|间接依赖|npm|
|acorn-walk|8.2.0|间接依赖|npm|
|object.values|1.1.5|间接依赖|npm|
|write-file-atomic|3.0.3|间接依赖|npm|
|string.prototype.trimend|1.0.5|间接依赖|npm|
|go.uber.org/atomic|v1.6.0|间接依赖|go|
|@babel/code-frame|7.12.11|间接依赖|npm|
|growl|1.10.5|间接依赖|npm|
|github.com/shurcooL/httpfs|v0.0.0-20190707220628-8d4bc4ba7749|间接依赖|go|
|@tsconfig/node14|1.0.1|间接依赖|npm|
|html-escaper|2.0.2|间接依赖|npm|
|wrap-ansi|7.0.0|间接依赖|npm|
|example.com/indirect-dep/v2|v2.1.0|直接依赖|go|
|electron-to-chromium|1.4.356|间接依赖|npm|
|string.prototype.trimstart|1.0.5|间接依赖|npm|
|@ungap/promise-all-settled|1.1.2|间接依赖|npm|
|google.golang.org/genproto|v0.0.0-20230726155614-23370e0ffb3e|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/storage/azblob|v0.4.1|间接依赖|go|
|string.prototype.trimend|1.0.4|间接依赖|npm|
|normalize-package-data|2.5.0|间接依赖|npm|
|@types/node|18.14.2|间接依赖|npm|
|es-abstract|1.17.6|间接依赖|npm|
|graceful-fs|4.2.10|间接依赖|npm|
|github.com/cpuguy83/go-md2man/v2|v2.0.2|间接依赖|go|
|golang.org/x/time|v0.0.0-20220722155302-e5dcc9cfc0b9|间接依赖|go|
|github.com/shirou/gopsutil/v3|v3.22.3|直接依赖|go|
|arg|4.1.3|间接依赖|npm|
|imurmurhash|0.1.4|间接依赖|npm|
|is-bigint|1.0.4|间接依赖|npm|
|type-fest|0.8.1|间接依赖|npm|
|github.com/opentracing/opentracing-go|v1.2.0|直接依赖|go|
|just-extend|4.2.1|间接依赖|npm|
|@types/split2|2.1.6|直接依赖|npm|
|Optional||间接依赖|pip|
|gopkg.in/tomb.v1|v1.0.0-20141024135613-dd632973f1e7|间接依赖|go|
|github.com/stretchr/testify|v1.7.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/aws/protocol/eventstream|v1.4.3|间接依赖|go|
|color-convert|1.9.3|间接依赖|npm|
|cloud.google.com/go/longrunning|v0.5.1|间接依赖|go|
|@babel/generator|7.21.4|间接依赖|npm|
|binary-extensions|2.2.0|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|@types/read-package-tree|5.2.0|直接依赖|npm|
|diff|4.0.2|间接依赖|npm|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|pylint|2.15.5|间接依赖|pip|
|json-schema-traverse|1.0.0|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|github.com/kballard/go-shellquote|v0.0.0-20180428030007-95032a82bc51|直接依赖|go|
|normalize-package-data|3.0.3|直接依赖|npm|
|import-fresh|3.3.0|间接依赖|npm|
|github.com/xanzy/ssh-agent|v0.3.3|间接依赖|go|
|minimist|1.2.7|间接依赖|npm|
|github.com/russross/blackfriday/v2|v2.1.0|间接依赖|go|
|github.com/mattn/go-runewidth|v0.0.13|间接依赖|go|
|minimist|1.2.6|间接依赖|npm|
|github.com/grapl-security/pulumi-hcp/sdk|v0.1.14|直接依赖|go|
|minimatch|4.2.1|间接依赖|npm|
|@opentelemetry/propagator-jaeger|1.7.0|间接依赖|npm|
|@babel/helper-compilation-targets|7.21.4|间接依赖|npm|
|esutils|2.0.3|间接依赖|npm|
|array-includes|3.1.5|间接依赖|npm|
|github.com/golang/snappy|v0.0.4|间接依赖|go|
|@types/mocha|2.2.48|直接依赖|npm|
|signal-exit|3.0.7|间接依赖|npm|
|github.com/hinshun/vt10x|v0.0.0-20220301184237-5011da428d02|直接依赖|go|
|tsutils|3.21.0|间接依赖|npm|
|enquirer|2.3.6|间接依赖|npm|
|github.com/tweekmonster/luser|v0.0.0-20161003172636-3fa38070dbd7|直接依赖|go|
|is-typedarray|1.0.0|间接依赖|npm|
|create-require|1.1.1|间接依赖|npm|
|github.com/Azure/go-autorest|v14.2.0+incompatible|间接依赖|go|
|upath|1.2.0|直接依赖|npm|
|is-callable|1.2.6|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|github.com/hashicorp/go-secure-stdlib/mlock|v0.1.2|间接依赖|go|
|github.com/djherbis/times|v1.2.0|间接依赖|go|
|arrify|1.0.1|直接依赖|npm|
|github.com/segmentio/encoding|v0.3.5|直接依赖|go|
|@sinonjs/fake-timers|9.1.2|间接依赖|npm|
|file-entry-cache|6.0.1|间接依赖|npm|
|dezalgo|1.0.3|间接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.15|间接依赖|npm|
|github.com/gliderlabs/ssh|v0.3.5|间接依赖|go|
|update-browserslist-db|1.0.10|间接依赖|npm|
|sinon|14.0.0|直接依赖|npm|
|github.com/aws/aws-sdk-go-v2/internal/configsources|v1.1.27|间接依赖|go|
|espree|7.3.1|间接依赖|npm|
|google-protobuf|3.21.0|直接依赖|npm|
|hosted-git-info|2.8.8|间接依赖|npm|
|golang.org/x/text|v0.9.0|间接依赖|go|
|github.com/pierrec/lz4|v2.6.1+incompatible|间接依赖|go|
|github.com/mitchellh/go-ps|v1.0.0|直接依赖|go|
|json-schema-traverse|0.4.1|间接依赖|npm|
|github.com/hashicorp/yamux|v0.1.1|间接依赖|go|
|has|1.0.3|间接依赖|npm|
|github.com/hashicorp/errwrap|v1.1.0|间接依赖|go|
|sphinx-tabs|3.1.0|间接依赖|pip|
|eslint|7.32.0|直接依赖|npm|
|istanbul-lib-source-maps|4.0.1|间接依赖|npm|
|github.com/yusufpapurcu/wmi|v1.2.2|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/s3|v1.27.2|间接依赖|go|
|@rometools/cli-darwin-x64|12.1.0|直接依赖|npm|
|@types/node|10.17.60|间接依赖|npm|
|ResourceProvider||间接依赖|pip|
|esprima|4.0.1|间接依赖|npm|
|@opentelemetry/semantic-conventions|1.7.0|直接依赖|npm|
|path-key|3.1.1|间接依赖|npm|
|github.com/golang-jwt/jwt/v4|v4.4.2|间接依赖|go|
|callsites|3.1.0|间接依赖|npm|
|github.com/pulumi/pulumi/sdk/v3|v3.35.3|直接依赖|go|
|github.com/oklog/run|v1.1.0|间接依赖|go|
|github.com/mgutz/ansi|v0.0.0-20170206155736-9520e82c474b|间接依赖|go|
|is-regex|1.1.0|间接依赖|npm|
|gocloud.dev|v0.27.0|直接依赖|go|
|anymatch|3.1.2|间接依赖|npm|
|long|4.0.0|间接依赖|npm|
|escape-string-regexp|4.0.0|间接依赖|npm|
|execa|5.1.1|直接依赖|npm|
|github.com/gofrs/uuid|v4.3.0+incompatible|间接依赖|go|
|wrap-ansi|6.2.0|间接依赖|npm|
|merge-stream|2.0.0|间接依赖|npm|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|istanbul-lib-instrument|4.0.3|间接依赖|npm|
|@protobufjs/aspromise|1.1.2|间接依赖|npm|
|p-locate|4.1.0|间接依赖|npm|
|npm-run-path|4.0.1|间接依赖|npm|
|@types/json5|0.0.29|间接依赖|npm|
|picomatch|2.3.1|间接依赖|npm|
|github.com/googleapis/gax-go/v2|v2.11.0|间接依赖|go|
|github.com/cenkalti/backoff/v3|v3.2.2|间接依赖|go|
|github.com/armon/go-metrics|v0.4.0|间接依赖|go|
|protobufjs|7.2.4|间接依赖|npm|
|@opentelemetry/api|1.4.1|间接依赖|npm|
|is-string|1.0.7|间接依赖|npm|
|github.com/Azure/go-autorest/autorest/date|v0.3.0|间接依赖|go|
|github.com/mitchellh/reflectwalk|v1.0.2|间接依赖|go|
|get-intrinsic|1.1.1|间接依赖|npm|
|@sinonjs/text-encoding|0.7.2|间接依赖|npm|
|glob-parent|5.1.2|间接依赖|npm|
|yargs-unparser|2.0.0|间接依赖|npm|
|supports-color|8.1.1|间接依赖|npm|
|github.com/pulumi/pulumi-yaml|v1.2.1|直接依赖|go|
|dezalgo|1.0.4|间接依赖|npm|
|@typescript-eslint/experimental-utils|4.33.0|间接依赖|npm|
|globals|11.12.0|间接依赖|npm|
|eslint-plugin-header|3.1.1|直接依赖|npm|
|github.com/hashicorp/go-multierror|v1.0.0|间接依赖|go|
|is-boolean-object|1.1.2|间接依赖|npm|
|color-name|1.1.4|间接依赖|npm|
|github.com/Azure/go-autorest/autorest/validation|v0.3.1|间接依赖|go|
|has-flag|4.0.0|间接依赖|npm|
|mimic-fn|2.1.0|间接依赖|npm|
|ms|2.1.3|间接依赖|npm|
|github.com/moby/moby|v23.0.3+incompatible|直接依赖|go|
|github.com/pulumi/pulumi/sdk/v3|v3.59.0|直接依赖|go|
|@protobufjs/path|1.1.2|间接依赖|npm|
|fsevents|2.3.2|直接依赖|npm|
|github.com/uber/jaeger-lib|v2.2.0+incompatible|间接依赖|go|
|append-transform|2.0.0|间接依赖|npm|
|golang.org/x/mod|v0.10.0|直接依赖|go|
|v8-compile-cache|2.3.0|间接依赖|npm|
|@sinonjs/commons|1.8.3|间接依赖|npm|
|has-property-descriptors|1.0.0|间接依赖|npm|
|@opentelemetry/sdk-trace-base|1.14.0|间接依赖|npm|
|unbox-primitive|1.0.1|间接依赖|npm|
|cloud.google.com/go/logging|v1.7.0|直接依赖|go|
|rimraf|3.0.2|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|lodash.camelcase|4.3.0|间接依赖|npm|
|github.com/go-ole/go-ole|v1.2.6|间接依赖|go|
|uri-js|4.4.1|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|github.com/fsnotify/fsnotify|v1.5.4|间接依赖|go|
|isexe|2.0.0|间接依赖|npm|
|github.com/texttheater/golang-levenshtein|v0.0.0-20191208221605-eb6844b05fc6|间接依赖|go|
|lodash.flattendeep|4.4.0|间接依赖|npm|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|@babel/types|7.21.4|间接依赖|npm|
|internal-slot|1.0.3|间接依赖|npm|
|github.com/hashicorp/go-rootcerts|v1.0.2|间接依赖|go|
|commondir|1.0.1|间接依赖|npm|
|is-symbol|1.0.4|间接依赖|npm|
|decamelize|1.2.0|间接依赖|npm|
|github.com/opentracing/opentracing-go|v1.1.0|间接依赖|go|
|github.com/uber/jaeger-client-go|v2.30.0+incompatible|直接依赖|go|
|github.com/hashicorp/golang-lru|v0.5.4|间接依赖|go|
|function.prototype.name|1.1.5|间接依赖|npm|
|find-cache-dir|3.3.2|间接依赖|npm|
|@babel/core|7.21.4|间接依赖|npm|
|is-callable|1.2.0|间接依赖|npm|
|@opentelemetry/sdk-trace-node|1.14.0|间接依赖|npm|
|@types/node|14.18.3|直接依赖|npm|
|github.com/gofrs/uuid|v3.3.0+incompatible|间接依赖|go|
|chalk|2.4.2|间接依赖|npm|
|uuid|8.3.2|间接依赖|npm|
|read-package-json|2.1.2|间接依赖|npm|
|github.com/hashicorp/go-version|v1.6.0|直接依赖|go|
|@rometools/cli-linux-arm64|12.1.0|直接依赖|npm|
|deep-is|0.1.4|间接依赖|npm|
|regexpp|3.2.0|间接依赖|npm|
|p-locate|6.0.0|间接依赖|npm|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|github.com/agext/levenshtein|v1.2.3|间接依赖|go|
|wrappy|1.0.2|间接依赖|npm|
|@babel/helper-module-imports|7.21.4|间接依赖|npm|
|github.com/sergi/go-diff|v1.3.1|直接依赖|go|
|gocloud.dev/secrets/hashivault|v0.27.0|直接依赖|go|
|istanbul-lib-processinfo|2.0.3|间接依赖|npm|
|github.com/aws/aws-sdk-go-v2/service/iam|v1.19.0|直接依赖|go|
|locate-path|5.0.0|间接依赖|npm|
|github.com/ryanuber/go-glob|v1.0.0|间接依赖|go|
|@istanbuljs/schema|0.1.3|间接依赖|npm|
|p-map|3.0.0|间接依赖|npm|
|github.com/aws/aws-sdk-go-v2/config|v1.15.15|直接依赖|go|
|github.com/emirpasic/gods|v1.18.1|间接依赖|go|
|github.com/spf13/afero|v1.9.5|直接依赖|go|
|array.prototype.reduce|1.0.4|间接依赖|npm|
|github.com/google/pprof|v0.0.0-20230406165453-00490a63f317|直接依赖|go|
|has-tostringtag|1.0.0|间接依赖|npm|
|optionator|0.9.1|间接依赖|npm|
|@opentelemetry/propagator-b3|1.14.0|间接依赖|npm|
|github.com/ProtonMail/go-crypto|v0.0.0-20221026131551-cf6655e29de4|间接依赖|go|
|github.com/gedex/inflector|v0.0.0-20170307190818-16278e9db813|直接依赖|go|
|node-releases|2.0.10|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/azidentity|v1.0.0|间接依赖|go|
|dir-glob|3.0.1|间接依赖|npm|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|yn|3.1.1|间接依赖|npm|
|eslint-utils|2.1.0|间接依赖|npm|
|google-protobuf|3.19.4|间接依赖|npm|
|@babel/helper-string-parser|7.19.4|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|github.com/hashicorp/go-secure-stdlib/parseutil|v0.1.6|间接依赖|go|
|github.com/mitchellh/copystructure|v1.2.0|直接依赖|go|
|github.com/mattn/go-isatty|v0.0.18|间接依赖|go|
|@opentelemetry/exporter-zipkin|1.14.0|间接依赖|npm|
|golang.org/x/xerrors|v0.0.0-20220907171357-04be3eba64a2|间接依赖|go|
|@rometools/cli-darwin-arm64|12.1.0|直接依赖|npm|
|github.com/pkg/term|v1.1.0|直接依赖|go|
|string.prototype.trimstart|1.0.1|间接依赖|npm|
|lodash.merge|4.6.2|间接依赖|npm|
|@opentelemetry/api-metrics|0.32.0|间接依赖|npm|
|github.com/BurntSushi/toml|v1.2.1|直接依赖|go|
|path-type|4.0.0|间接依赖|npm|
|pulumi||间接依赖|pip|
|clean-stack|2.2.0|间接依赖|npm|
|github.com/aws/aws-sdk-go-v2/internal/v4a|v1.0.6|间接依赖|go|
|pgregory.net/rapid|v0.6.1|直接依赖|go|
|chokidar|3.5.3|间接依赖|npm|
|lodash.get|4.4.2|间接依赖|npm|
|npm-normalize-package-bin|1.0.1|间接依赖|npm|
|github.com/tklauser/numcpus|v0.4.0|间接依赖|go|
|package-hash|4.0.0|间接依赖|npm|
|chalk|4.1.2|间接依赖|npm|
|github.com/aws/aws-sdk-go-v2/internal/endpoints/v2|v2.4.21|间接依赖|go|
|golang.org/x/sys|v0.8.0|直接依赖|go|
|cloud.google.com/go/iam|v1.1.1|间接依赖|go|
|es-abstract|1.20.2|间接依赖|npm|
|yallist|4.0.0|间接依赖|npm|
|golang.org/x/tools|v0.9.3|间接依赖|go|
|call-bind|1.0.2|间接依赖|npm|
|read-package-json|2.1.1|间接依赖|npm|
|@opentelemetry/propagator-b3|1.7.0|间接依赖|npm|
|onetime|5.1.2|间接依赖|npm|
|@babel/code-frame|7.21.4|间接依赖|npm|
|parent-module|1.0.1|间接依赖|npm|
|github.com/uber/jaeger-lib|v2.4.1+incompatible|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sso|v1.11.13|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.0.0|间接依赖|go|
|nise|5.1.1|间接依赖|npm|
|@types/minimist|1.2.2|直接依赖|npm|
|gopkg.in/src-d/go-git.v4|v4.13.1|间接依赖|go|
|github.com/hashicorp/go-hclog|v1.2.2|间接依赖|go|
|@protobufjs/float|1.0.2|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/internal|v1.0.0|间接依赖|go|
|@nodelib/fs.stat|2.0.5|间接依赖|npm|
|sourcegraph.com/sourcegraph/appdash-data|v0.0.0-20151005221446-73f23eafcf67|间接依赖|go|
|hosted-git-info|2.8.9|间接依赖|npm|
|randombytes|2.1.0|间接依赖|npm|
|github.com/ettle/strcase|v0.1.1|间接依赖|go|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|@protobufjs/fetch|1.1.0|间接依赖|npm|
|@types/node|17.0.20|间接依赖|npm|
|mocha|9.2.2|直接依赖|npm|
|browserslist|4.21.5|间接依赖|npm|
|cloud.google.com/go/kms|v1.12.1|间接依赖|go|
|github.com/Azure/go-autorest/autorest/to|v0.4.0|间接依赖|go|
|yargs-parser|18.1.3|间接依赖|npm|
|debug|3.2.7|间接依赖|npm|
|long|5.2.1|间接依赖|npm|
|@babel/helper-function-name|7.21.0|间接依赖|npm|
|fastq|1.13.0|间接依赖|npm|
|go.uber.org/atomic|v1.10.0|间接依赖|go|
|debuglog|1.0.1|间接依赖|npm|
|@jridgewell/set-array|1.1.2|间接依赖|npm|
|@rometools/cli-win32-arm64|12.1.0|直接依赖|npm|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|ansi-styles|3.2.1|间接依赖|npm|
|@tsconfig/node10|1.0.8|间接依赖|npm|
|github.com/opentracing/basictracer-go|v1.1.0|间接依赖|go|
|github.com/kylelemons/godebug|v1.1.0|间接依赖|go|
|yn|2.0.0|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)