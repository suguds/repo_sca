# Azure/azure-sdk-for-go安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694411423878045696.svg)](https://www.murphysec.com/console/report/1694411423823519744/1694411423878045696)

仓库描述：This repository is for active development of the Azure SDK for Go. For consumers of the SDK we recommend visiting our public developer docs at:

仓库地址：[https://github.com/Azure/azure-sdk-for-go](https://github.com/Azure/azure-sdk-for-go)

| star：1352 | watch：257 | fork：787 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-24 01:37:03 | 许可证：MIT |
| 最近检测时间：2023-08-24 02:10:15 | 组件总数：381 | 漏洞总数：4 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58307](https://www.oscs1024.com/hd/MPS-2022-58307)|CVE-2022-41723|高危|
|Go-Yaml 安全漏洞|反序列化|[MPS-2022-8233](https://www.oscs1024.com/hd/MPS-2022-8233)|CVE-2022-28948|高危|
|Google Go 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2022-9049](https://www.oscs1024.com/hd/MPS-2022-9049)|CVE-2022-29526|中危|
|CIRCL 安全漏洞|对异常条件的处理不恰当|[MPS-2023-9182](https://www.oscs1024.com/hd/MPS-2023-9182)|CVE-2023-1732|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/cloudflare/circl|v1.3.2|1.3.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|golang.org/x/net|v0.0.0-20220425223048-2871e0cb64e4|0.7.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|gopkg.in/yaml.v3|v3.0.0-20200313102051-9f266ea9e77c|3.0.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|gopkg.in/yaml.v3|v3.0.0-20210107192922-496545a6307b|3.0.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|golang.org/x/sys|v0.0.0-20211216021012-1d35b9e2eb4e|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|257|Low|
|Apache-2.0|29|Low|
|BSD-3-Clause|42|Low|
|BSD-2-Clause|10|Low|
|ISC|24|Low|
|0BSD|1|Low|
|MPL-2.0|2|Low|
|Python-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/Azure/azure-sdk-for-go/sdk/azidentity|v1.1.0|直接依赖|go|
|is-extglob|2.1.1|间接依赖|npm|
|node-watch|0.7.3|间接依赖|npm|
|github.com/kylelemons/godebug|v1.1.0|间接依赖|go|
|@azure-tools/typespec-autorest|0.31.0|间接依赖|npm|
|@cspell/dict-typescript|3.1.1|间接依赖|npm|
|mkdirp|2.1.6|间接依赖|npm|
|github.com/imdario/mergo|v0.3.14|间接依赖|go|
|@nodelib/fs.scandir|2.1.5|间接依赖|npm|
|github.com/google/uuid|v1.3.0|直接依赖|go|
|imurmurhash|0.1.4|间接依赖|npm|
|github.com/pjbgf/sha1cd|v0.3.0|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/resourcemanager/resources/armresources|v1.1.1|直接依赖|go|
|typedarray-to-buffer|3.1.5|间接依赖|npm|
|reusify|1.0.4|间接依赖|npm|
|github.com/AzureAD/microsoft-authentication-library-for-go|v1.1.1|直接依赖|go|
|cspell-grammar|6.31.1|间接依赖|npm|
|configstore|5.0.1|间接依赖|npm|
|@cspell/strong-weak-map|6.31.1|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|vscode-languageserver-types|3.17.3|间接依赖|npm|
|@cspell/dict-filetypes|3.0.1|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/internal|v1.0.0|间接依赖|go|
|go.opentelemetry.io/otel/metric|v1.16.0|间接依赖|go|
|yargs-parser|21.1.1|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|github.com/jbenet/go-context|v0.0.0-20150711004518-d14ea06fba99|间接依赖|go|
|nhooyr.io/websocket|v1.8.7|直接依赖|go|
|camel-case|4.1.2|间接依赖|npm|
|github.com/xanzy/ssh-agent|v0.3.3|间接依赖|go|
|clear-module|4.1.2|间接依赖|npm|
|commander|10.0.1|间接依赖|npm|
|golang.org/x/sys|v0.8.0|间接依赖|go|
|github.com/dnaeon/go-vcr|v1.2.0|间接依赖|go|
|@cspell/cspell-service-bus|6.31.1|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/azcore|v1.6.1|直接依赖|go|
|lru-cache|6.0.0|间接依赖|npm|
|change-case|4.1.2|间接依赖|npm|
|go.opentelemetry.io/otel|v1.16.0|直接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|golang.org/x/crypto|v0.0.0-20220511200225-c6db032c6c88|间接依赖|go|
|js-tokens|4.0.0|间接依赖|npm|
|vscode-languageserver-protocol|3.17.3|间接依赖|npm|
|@cspell/dict-k8s|1.0.1|间接依赖|npm|
|@cspell/dict-css|4.0.6|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/internal|v1.3.0|直接依赖|go|
|@cspell/dict-bash|4.1.1|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|@cspell/dict-dart|2.0.2|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go|v68.0.0+incompatible|直接依赖|go|
|cspell-trie-lib|6.31.1|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/resourcemanager/eventhub/armeventhub|v1.0.0|直接依赖|go|
|@babel/code-frame|7.21.4|间接依赖|npm|
|fastq|1.15.0|间接依赖|npm|
|is-obj|2.0.0|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/eng/tools/internal|v0.0.0-20230321110746-6cd8433da5d2|直接依赖|go|
|upper-case-first|2.0.2|间接依赖|npm|
|github.com/Azure/go-autorest/autorest|v0.11.18|直接依赖|go|
|@cspell/dict-elixir|4.0.3|间接依赖|npm|
|has-flag|4.0.0|间接依赖|npm|
|globby|13.1.4|间接依赖|npm|
|gopkg.in/yaml.v2|v2.4.0|直接依赖|go|
|@cspell/dict-php|4.0.1|间接依赖|npm|
|comment-json|4.2.3|间接依赖|npm|
|parent-module|2.0.0|间接依赖|npm|
|github.com/stretchr/testify|v1.8.2|直接依赖|go|
|github.com/Masterminds/semver|v1.5.0|直接依赖|go|
|yargs|17.7.2|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/azcore|v1.0.0|直接依赖|go|
|param-case|3.0.4|间接依赖|npm|
|github.com/golang-jwt/jwt/v5|v5.0.0|直接依赖|go|
|vscode-languageserver|8.1.0|间接依赖|npm|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|slash|4.0.0|间接依赖|npm|
|go.opentelemetry.io/otel/sdk|v1.16.0|直接依赖|go|
|@cspell/dict-ada|4.0.1|间接依赖|npm|
|ajv|8.12.0|间接依赖|npm|
|@cspell/dict-html|4.0.3|间接依赖|npm|
|github.com/Azure/go-autorest/logger|v0.2.1|间接依赖|go|
|tslib|2.6.0|间接依赖|npm|
|snake-case|3.0.4|间接依赖|npm|
|y18n|5.0.8|间接依赖|npm|
|github.com/AzureAD/microsoft-authentication-library-for-go|v0.9.0|间接依赖|go|
|@cspell/dict-r|2.0.1|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go|v63.3.0+incompatible|间接依赖|go|
|golang.org/x/net|v0.8.0|直接依赖|go|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|@typespec/openapi3|0.45.0|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/azidentity|v0.12.0|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/azcore|v1.8.0-beta.1|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/security/keyvault/azkeys|v1.0.0|直接依赖|go|
|@cspell/dict-golang|6.0.2|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/security/keyvault/internal|v1.0.0|直接依赖|go|
|golang.org/x/net|v0.0.0-20220425223048-2871e0cb64e4|间接依赖|go|
|import-fresh|3.3.0|间接依赖|npm|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|dir-glob|3.0.1|间接依赖|npm|
|mustache|4.2.0|间接依赖|npm|
|cosmiconfig|8.0.0|间接依赖|npm|
|@cspell/dict-fullstack|3.1.5|间接依赖|npm|
|@cspell/dict-swift|2.0.1|间接依赖|npm|
|gopkg.in/warnings.v0|v0.1.2|间接依赖|go|
|unique-string|2.0.0|间接依赖|npm|
|flatted|3.2.7|间接依赖|npm|
|@cspell/dict-haskell|4.0.1|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|golang.org/x/net|v0.7.0|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/resourcemanager/internal|v1.1.2|直接依赖|go|
|@cspell/dict-fonts|3.0.2|间接依赖|npm|
|is-glob|4.0.3|间接依赖|npm|
|chalk|4.1.2|间接依赖|npm|
|error-ex|1.3.2|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/resourcemanager/resources/armresources|v1.0.0|直接依赖|go|
|github.com/stretchr/testify|v1.7.2|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/resourcemanager/storage/armstorage|v1.2.0|直接依赖|go|
|constant-case|3.0.4|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/azcore|v1.6.0|直接依赖|go|
|go.opentelemetry.io/otel/trace|v1.16.0|直接依赖|go|
|golang.org/x/net|v0.13.0|间接依赖|go|
|github.com/kevinburke/ssh_config|v1.2.0|间接依赖|go|
|color-convert|2.0.1|间接依赖|npm|
|cliui|8.0.1|间接依赖|npm|
|@cspell/dict-companies|3.0.17|间接依赖|npm|
|@cspell/dict-aws|3.0.0|间接依赖|npm|
|semver|7.5.4|间接依赖|npm|
|repeat-string|1.6.1|间接依赖|npm|
|@cspell/dict-vue|3.0.0|间接依赖|npm|
|github.com/dnaeon/go-vcr|v1.1.0|直接依赖|go|
|@cspell/dict-python|4.1.2|间接依赖|npm|
|fast-glob|3.2.12|间接依赖|npm|
|github.com/sergi/go-diff|v1.3.1|间接依赖|go|
|@cspell/dict-gaming-terms|1.0.4|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|github.com/hashicorp/go-multierror|v1.1.1|直接依赖|go|
|wrap-ansi|7.0.0|间接依赖|npm|
|golang.org/x/sys|v0.5.0|间接依赖|go|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|github.com/golang/mock|v1.6.0|直接依赖|go|
|upper-case|2.0.2|间接依赖|npm|
|@babel/code-frame|7.22.5|间接依赖|npm|
|github.com/golang-jwt/jwt/v4|v4.5.0|间接依赖|go|
|emoji-regex|8.0.0|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/resourcemanager/containerregistry/armcontainerregistry|v0.6.0|直接依赖|go|
|@cspell/dict-cryptocurrencies|3.0.1|间接依赖|npm|
|google.golang.org/protobuf|v1.30.0|间接依赖|go|
|@typespec/compiler|0.45.2|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|@cspell/dynamic-import|6.31.1|间接依赖|npm|
|pascal-case|3.1.2|间接依赖|npm|
|cspell|6.31.2|直接依赖|npm|
|@cspell/dict-powershell|5.0.2|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/azidentity|v1.2.2|直接依赖|go|
|@cspell/dict-ruby|5.0.0|间接依赖|npm|
|golang.org/x/sys|v0.10.0|间接依赖|go|
|color-name|1.1.3|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/azcore|v1.4.0|直接依赖|go|
|micromatch|4.0.5|间接依赖|npm|
|path-type|4.0.0|间接依赖|npm|
|glob-parent|5.1.2|间接依赖|npm|
|gopkg.in/yaml.v3|v3.0.0-20210107192922-496545a6307b|间接依赖|go|
|@cspell/dict-dotnet|5.0.0|间接依赖|npm|
|golang.org/x/crypto|v0.9.0|间接依赖|go|
|golang.org/x/sys|v0.11.0|间接依赖|go|
|github.com/acomagu/bufpipe|v1.0.4|间接依赖|go|
|golang.org/x/text|v0.3.7|间接依赖|go|
|no-case|3.0.4|间接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|github.com/ProtonMail/go-crypto|v0.0.0-20230321155629-9a39f2531310|间接依赖|go|
|callsites|3.1.0|间接依赖|npm|
|is-number|7.0.0|间接依赖|npm|
|github.com/stretchr/testify|v1.7.0|直接依赖|go|
|sisteransi|1.0.5|间接依赖|npm|
|cspell-dictionary|6.31.1|间接依赖|npm|
|golang.org/x/crypto|v0.6.0|间接依赖|go|
|github.com/joho/godotenv|v1.5.1|直接依赖|go|
|@cspell/dict-cpp|5.0.3|间接依赖|npm|
|sentence-case|3.0.4|间接依赖|npm|
|go.opentelemetry.io/otel/exporters/jaeger|v1.16.0|直接依赖|go|
|fast-equals|4.0.3|间接依赖|npm|
|github.com/cloudflare/circl|v1.3.2|间接依赖|go|
|json-schema-traverse|1.0.0|间接依赖|npm|
|escape-string-regexp|1.0.5|直接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/azcore|v1.7.0|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/azidentity|v1.3.0|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/eng/tools/internal|v0.0.0-20230321225744-d732f7cc62b3|直接依赖|go|
|github.com/go-git/gcfg|v1.5.0|间接依赖|go|
|path-is-absolute|1.0.1|间接依赖|npm|
|golang.org/x/net|v0.12.0|间接依赖|go|
|cspell-lib|6.31.2|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/resourcemanager/containerservice/armcontainerservice|v1.0.0|直接依赖|go|
|find-up|5.0.0|间接依赖|npm|
|supports-color|7.2.0|间接依赖|npm|
|@cspell/dict-node|4.0.2|间接依赖|npm|
|@cspell/dict-html-symbol-entities|4.0.0|间接依赖|npm|
|ini|1.3.8|间接依赖|npm|
|is-typedarray|1.0.0|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/security/keyvault/azsecrets|v0.13.0|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/security/keyvault/azsecrets|v1.0.0|直接依赖|go|
|golang.org/x/net|v0.10.0|间接依赖|go|
|github.com/Azure/go-amqp|v1.0.0|直接依赖|go|
|@cspell/dict-scala|5.0.0|间接依赖|npm|
|core-util-is|1.0.3|间接依赖|npm|
|file-entry-cache|6.0.1|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/azidentity|v1.3.1|直接依赖|go|
|strip-ansi|6.0.1|间接依赖|npm|
|xdg-basedir|4.0.0|间接依赖|npm|
|is-arrayish|0.2.1|间接依赖|npm|
|color-name|1.1.4|间接依赖|npm|
|github.com/go-git/go-git/v5|v5.6.1|直接依赖|go|
|fast-glob|3.3.0|间接依赖|npm|
|golang.org/x/crypto|v0.11.0|间接依赖|go|
|has-flag|3.0.0|间接依赖|npm|
|array-timsort|1.0.3|间接依赖|npm|
|github.com/skeema/knownhosts|v1.1.0|间接依赖|go|
|global-dirs|0.1.1|间接依赖|npm|
|github.com/Azure/go-autorest|v14.2.0+incompatible|间接依赖|go|
|p-locate|5.0.0|间接依赖|npm|
|github.com/stretchr/testify|v1.8.4|直接依赖|go|
|locate-path|6.0.0|间接依赖|npm|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|p-limit|3.1.0|间接依赖|npm|
|github.com/google/go-github/v32|v32.1.0|直接依赖|go|
|@cspell/dict-en-gb|1.1.33|间接依赖|npm|
|github.com/gofrs/uuid|v3.3.0+incompatible|间接依赖|go|
|crypto-random-string|2.0.0|间接依赖|npm|
|picomatch|2.3.1|间接依赖|npm|
|@babel/highlight|7.22.5|间接依赖|npm|
|github.com/davecgh/go-spew|v1.1.0|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|golang.org/x/text|v0.11.0|间接依赖|go|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|github.com/AzureAD/microsoft-authentication-library-for-go|v0.7.0|间接依赖|go|
|resolve-from|5.0.0|间接依赖|npm|
|github.com/Microsoft/go-winio|v0.6.0|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.0-20200313102051-9f266ea9e77c|间接依赖|go|
|github.com/AzureAD/microsoft-authentication-library-for-go|v0.8.1|间接依赖|go|
|tr46|0.0.3|间接依赖|npm|
|github.com/ahmetb/go-linq/v3|v3.2.0|直接依赖|go|
|github.com/klauspost/compress|v1.10.3|间接依赖|go|
|once|1.4.0|间接依赖|npm|
|@cspell/dict-en-common-misspellings|1.0.2|间接依赖|npm|
|rimraf|3.0.2|间接依赖|npm|
|node-fetch|2.6.12|间接依赖|npm|
|graceful-fs|4.2.11|间接依赖|npm|
|golang.org/x/sys|v0.6.0|间接依赖|go|
|vscode-uri|3.0.7|间接依赖|npm|
|@cspell/dict-public-licenses|2.0.2|间接依赖|npm|
|github.com/go-logr/logr|v1.2.4|间接依赖|go|
|github.com/spf13/cobra|v1.6.1|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/data/aztables|v1.0.0|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/internal|v1.2.0|直接依赖|go|
|github.com/Azure/go-autorest/autorest/date|v0.3.0|间接依赖|go|
|github.com/Azure/azure-sdk-for-go|v46.3.0+incompatible|直接依赖|go|
|@cspell/cspell-pipe|6.31.1|间接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|github.com/emirpasic/gods|v1.18.1|间接依赖|go|
|color-convert|1.9.3|间接依赖|npm|
|github.com/pkg/browser|v0.0.0-20210911075715-681adbf594b8|间接依赖|go|
|fast-deep-equal|3.1.3|间接依赖|npm|
|gensequence|5.0.2|间接依赖|npm|
|path-case|3.0.4|间接依赖|npm|
|github.com/Azure/go-autorest/tracing|v0.6.0|间接依赖|go|
|github.com/golang-jwt/jwt/v4|v4.4.2|间接依赖|go|
|@nodelib/fs.stat|2.0.5|间接依赖|npm|
|parse-json|5.2.0|间接依赖|npm|
|github.com/pkg/browser|v0.0.0-20210115035449-ce105d075bb4|间接依赖|go|
|minimatch|3.1.2|间接依赖|npm|
|flat-cache|3.0.4|间接依赖|npm|
|@cspell/dict-software-terms|3.2.0|间接依赖|npm|
|@cspell/dict-git|2.0.0|间接依赖|npm|
|has-own-prop|2.0.0|间接依赖|npm|
|lines-and-columns|1.2.4|间接依赖|npm|
|prompts|2.4.2|间接依赖|npm|
|golang.org/x/text|v0.12.0|间接依赖|go|
|golang.org/x/sys|v0.7.0|间接依赖|go|
|github.com/go-git/go-billy/v5|v5.4.1|间接依赖|go|
|@cspell/dict-csharp|4.0.2|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/azidentity|v1.2.1|直接依赖|go|
|require-from-string|2.0.2|间接依赖|npm|
|esprima|4.0.1|间接依赖|npm|
|lower-case|2.0.2|间接依赖|npm|
|github.com/golang-jwt/jwt|v3.2.1+incompatible|间接依赖|go|
|golang.org/x/crypto|v0.12.0|直接依赖|go|
|chalk|2.4.2|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/azidentity|v1.2.0|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/resourcemanager/batch/armbatch|v1.2.1|直接依赖|go|
|github.com/joho/godotenv|v1.4.0|直接依赖|go|
|golang.org/x/crypto|v0.7.0|间接依赖|go|
|@cspell/dict-rust|4.0.1|间接依赖|npm|
|golang.org/x/mod|v0.9.0|间接依赖|go|
|@cspell/dict-svelte|1.0.2|间接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|@cspell/dict-sql|2.1.0|间接依赖|npm|
|code.cloudfoundry.org/clock|v0.0.0-20180518195852-02e53af36e6c|间接依赖|go|
|argparse|2.0.1|间接依赖|npm|
|@cspell/dict-en_us|4.3.4|间接依赖|npm|
|write-file-atomic|3.0.3|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/azcore|v1.5.0|直接依赖|go|
|to-regex-range|5.0.1|间接依赖|npm|
|vscode-languageserver-textdocument|1.0.8|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/resourcemanager/cosmos/armcosmos/v2|v2.5.0|直接依赖|go|
|cspell-gitignore|6.31.2|间接依赖|npm|
|golang.org/x/oauth2|v0.6.0|直接依赖|go|
|yallist|4.0.0|间接依赖|npm|
|cspell-io|6.31.2|间接依赖|npm|
|@cspell/dict-npm|5.0.7|间接依赖|npm|
|@typespec/lint|0.45.0|间接依赖|npm|
|path-exists|4.0.0|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/security/keyvault/internal|v0.8.0|间接依赖|go|
|run-parallel|1.2.0|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/security/keyvault/azcertificates|v0.11.0|直接依赖|go|
|ignore|5.2.4|间接依赖|npm|
|github.com/hashicorp/errwrap|v1.1.0|间接依赖|go|
|@cspell/cspell-types|6.31.1|间接依赖|npm|
|ansi-styles|4.3.0|间接依赖|npm|
|@cspell/dict-docker|1.1.6|间接依赖|npm|
|punycode|2.3.0|间接依赖|npm|
|js-yaml|4.1.0|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/storage/azblob|v1.0.0|直接依赖|go|
|webidl-conversions|3.0.1|间接依赖|npm|
|golang.org/x/tools|v0.7.0|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/internal|v1.1.2|间接依赖|go|
|@azure-tools/typespec-azure-core|0.31.0|间接依赖|npm|
|@babel/helper-validator-identifier|7.22.5|间接依赖|npm|
|github.com/stretchr/testify|v1.8.3|直接依赖|go|
|@cspell/dict-latex|4.0.0|间接依赖|npm|
|string-width|4.2.3|间接依赖|npm|
|golang.org/x/text|v0.8.0|间接依赖|go|
|github.com/stretchr/testify|v1.7.1|直接依赖|go|
|cspell-glob|6.31.2|间接依赖|npm|
|kleur|3.0.3|间接依赖|npm|
|golang.org/x/text|v0.7.0|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/resourcemanager/resources/armdeploymentscripts|v1.0.0|直接依赖|go|
|get-stdin|8.0.0|间接依赖|npm|
|github.com/google/uuid|v1.1.1|间接依赖|go|
|@cspell/dict-data-science|1.0.7|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/resourcemanager/managementgroups/armmanagementgroups|v1.0.0|直接依赖|go|
|whatwg-url|5.0.0|间接依赖|npm|
|golang.org/x/sys|v0.0.0-20211216021012-1d35b9e2eb4e|间接依赖|go|
|vscode-jsonrpc|8.1.0|间接依赖|npm|
|prettier|2.8.8|间接依赖|npm|
|dot-prop|5.3.0|间接依赖|npm|
|@cspell/cspell-bundled-dicts|6.31.2|间接依赖|npm|
|github.com/AzureAD/microsoft-authentication-library-for-go|v1.0.0|间接依赖|go|
|github.com/microsoft/azure-devops-go-api/azuredevops/v6|v6.0.1|直接依赖|go|
|make-dir|3.1.0|间接依赖|npm|
|@nodelib/fs.walk|1.2.8|间接依赖|npm|
|json-parse-even-better-errors|2.3.1|间接依赖|npm|
|@cspell/dict-django|4.1.0|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/resourcemanager/msi/armmsi|v0.6.0|直接依赖|go|
|github.com/microsoft/ApplicationInsights-Go|v0.4.4|直接依赖|go|
|merge2|1.4.1|间接依赖|npm|
|@cspell/dict-lua|4.0.1|间接依赖|npm|
|glob|7.2.3|间接依赖|npm|
|@cspell/dict-java|5.0.5|间接依赖|npm|
|github.com/jongio/azidext/go/azidext|v0.2.0|直接依赖|go|
|queue-microtask|1.2.3|间接依赖|npm|
|capital-case|1.0.4|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/azidentity|v1.0.0|直接依赖|go|
|github.com/AzureAD/microsoft-authentication-library-for-go|v0.4.0|间接依赖|go|
|github.com/google/go-querystring|v1.1.0|间接依赖|go|
|github.com/AzureAD/microsoft-authentication-library-for-go|v0.5.1|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/azcore|v1.8.0-beta.2|直接依赖|go|
|github.com/stretchr/testify|v1.8.1|直接依赖|go|
|github.com/Azure/go-autorest/autorest/adal|v0.9.23|间接依赖|go|
|dot-case|3.0.4|间接依赖|npm|
|import-meta-resolve|2.2.2|间接依赖|npm|
|picocolors|1.0.0|间接依赖|npm|
|@cspell/dict-lorem-ipsum|3.0.0|间接依赖|npm|
|golang.org/x/net|v0.14.0|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/azcore|v1.7.1|直接依赖|go|
|resolve-global|1.0.0|间接依赖|npm|
|github.com/joho/godotenv|v1.3.0|直接依赖|go|
|header-case|2.0.4|间接依赖|npm|
|golang.org/x/text|v0.9.0|间接依赖|go|
|signal-exit|3.0.7|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)