# idurar/idurar-erp-crm安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698765757064282112.svg)](https://www.murphysec.com/console/report/1696230499185156096/1698765757064282112)

仓库描述：Open Source ERP (Invoice / Inventory / Accounting / HR / CRM )  Based on Nodejs / React js  https://www.idurarapp.com

仓库地址：[https://github.com/idurar/idurar-erp-crm](https://github.com/idurar/idurar-erp-crm)

| star：1266 | watch：23 | fork：334 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-05 00:46:29 | 许可证：MIT |
| 最近检测时间：2023-09-05 02:31:51 | 组件总数：498 | 漏洞总数：12 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Http-signature 安全漏洞|密码学签名的验证不恰当|[MPS-2018-6996](https://www.oscs1024.com/hd/MPS-2018-6996)|CVE-2017-16005|高危|
|glob-parent < 5.1.2 存在拒绝服务漏洞|拒绝服务|[MPS-2021-7827](https://www.oscs1024.com/hd/MPS-2021-7827)|CVE-2020-28469|高危|
|got 存在打开重定向漏洞|跨站重定向|[MPS-2022-19247](https://www.oscs1024.com/hd/MPS-2022-19247)|CVE-2022-33987|中危|
|jsonwebtoken远程代码执行漏洞|代码注入|[MPS-2022-1956](https://www.oscs1024.com/hd/MPS-2022-1956)|CVE-2022-23529|高危|
|jsonwebtoken 加密问题漏洞|密码算法不安全|[MPS-2022-1966](https://www.oscs1024.com/hd/MPS-2022-1966)|CVE-2022-23539|高危|
|jsonwebtoken 数据伪造问题漏洞|密码学签名的验证不恰当|[MPS-2022-1967](https://www.oscs1024.com/hd/MPS-2022-1967)|CVE-2022-23540|高危|
|JsonWebToken < 9.0.0 存在身份验证绕过|身份验证不当|[MPS-2022-1968](https://www.oscs1024.com/hd/MPS-2022-1968)|CVE-2022-23541|中危|
|dicer 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5087](https://www.oscs1024.com/hd/MPS-2022-5087)|CVE-2022-24434|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|tough-cookie 安全漏洞|原型污染|[MPS-2023-5130](https://www.oscs1024.com/hd/MPS-2023-5130)|CVE-2023-26136|严重|
|request SSRF防御绕过漏洞|SSRF|[MPS-2023-7722](https://www.oscs1024.com/hd/MPS-2023-7722)|CVE-2023-28155|中危|
|tough-cookie<4.1.3 存在原型污染漏洞|原型污染|[MPS-esyq-56vx](https://www.oscs1024.com/hd/MPS-esyq-56vx)||中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|dicer|0.2.5||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|jsonwebtoken|8.5.1|9.0.0|直接依赖|建议修复|C:0|H:3|M:1|L:0|
|http-signature|1.2.0||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|glob-parent|3.1.0|6.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tough-cookie|2.5.0|4.1.3|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|request|2.88.2||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|got|6.7.1|12.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|5.7.2|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|343|Low|
|Apache-2.0|40|Low|
|GPL-2.0|1|Medium|
|ISC|34|Low|
|BSD-2-Clause|10|Low|
|BSD-3-Clause|8|Low|
|Unlicense|1|Low|
|0BSD|2|Low|
|Apache 2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|cookie-signature|1.0.6|间接依赖|npm|
|token-stream|1.0.0|间接依赖|npm|
|@smithy/querystring-builder|2.0.1|间接依赖|npm|
|asynckit|0.4.0|间接依赖|npm|
|babel-walk|3.0.0-canary-5|间接依赖|npm|
|@aws-sdk/util-user-agent-browser|3.378.0|间接依赖|npm|
|mongoose-sequence|5.3.1|直接依赖|npm|
|nopt|1.0.10|间接依赖|npm|
|lodash.isboolean|3.0.3|间接依赖|npm|
|@aws-sdk/types|3.378.0|间接依赖|npm|
|cookie|0.4.1|间接依赖|npm|
|@smithy/util-utf8|2.0.0|间接依赖|npm|
|class-utils|0.3.6|间接依赖|npm|
|assign-symbols|1.0.0|直接依赖|npm|
|ignore-by-default|1.0.1|间接依赖|npm|
|@aws-sdk/credential-provider-node|3.385.0|间接依赖|npm|
|@smithy/node-http-handler|2.0.1|间接依赖|npm|
|mquery|4.0.3|间接依赖|npm|
|use|3.1.1|间接依赖|npm|
|file-uri-to-path|1.0.0|间接依赖|npm|
|pend|1.2.0|间接依赖|npm|
|pinkie|2.0.4|间接依赖|npm|
|@aws-sdk/client-sso|3.382.0|间接依赖|npm|
|normalize-path|2.1.1|间接依赖|npm|
|bowser|2.11.0|间接依赖|npm|
|@babel/types|7.21.3|间接依赖|npm|
|split-string|3.1.0|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|form-data|2.3.3|间接依赖|npm|
|vary|1.1.2|间接依赖|npm|
|axios|1.4.0|间接依赖|npm|
|fragment-cache|0.2.1|间接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|call-bind|1.0.2|间接依赖|npm|
|registry-url|3.1.0|间接依赖|npm|
|promise|7.3.1|间接依赖|npm|
|mongodb|4.16.0|间接依赖|npm|
|make-dir|1.3.0|间接依赖|npm|
|domutils|3.1.0|间接依赖|npm|
|resolve|1.22.1|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|configstore|3.1.5|间接依赖|npm|
|send|0.18.0|间接依赖|npm|
|caseless|0.12.0|间接依赖|npm|
|with|7.0.2|间接依赖|npm|
|package-json|4.0.1|间接依赖|npm|
|lodash.includes|4.3.0|间接依赖|npm|
|unpipe|1.0.0|间接依赖|npm|
|path-is-inside|1.0.2|间接依赖|npm|
|tunnel-agent|0.6.0|间接依赖|npm|
|tough-cookie|2.5.0|间接依赖|npm|
|is-redirect|1.0.0|间接依赖|npm|
|snapdragon|0.8.2|间接依赖|npm|
|buffer-from|1.1.2|间接依赖|npm|
|saslprep|1.0.3|直接依赖|npm|
|@smithy/util-hex-encoding|2.0.0|间接依赖|npm|
|is-whitespace|0.3.0|间接依赖|npm|
|html-to-text|9.0.3|间接依赖|npm|
|util-deprecate|1.0.2|直接依赖|npm|
|mixin-deep|1.3.2|间接依赖|npm|
|helmet|4.6.0|直接依赖|npm|
|combined-stream|1.0.8|间接依赖|npm|
|@react-email/render|0.0.7|间接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|@smithy/shared-ini-file-loader|2.0.1|间接依赖|npm|
|media-typer|0.3.0|间接依赖|npm|
|ip|2.0.0|间接依赖|npm|
|setprototypeof|1.2.0|间接依赖|npm|
|js-beautify|1.14.9|间接依赖|npm|
|pify|3.0.0|间接依赖|npm|
|jwa|1.4.1|间接依赖|npm|
|@one-ini/wasm|0.1.1|间接依赖|npm|
|condense-newlines|0.2.1|间接依赖|npm|
|forever-agent|0.6.1|间接依赖|npm|
|@smithy/util-body-length-browser|2.0.0|间接依赖|npm|
|get-intrinsic|1.2.0|间接依赖|npm|
|is-descriptor|0.1.6|间接依赖|npm|
|@aws-crypto/supports-web-crypto|3.0.0|间接依赖|npm|
|base|0.11.2|间接依赖|npm|
|crypto-random-string|1.0.0|间接依赖|npm|
|@smithy/hash-node|2.0.1|间接依赖|npm|
|lodash.isnumber|3.0.3|间接依赖|npm|
|mime-db|1.52.0|间接依赖|npm|
|has-symbols|1.0.3|间接依赖|npm|
|cors|2.8.5|直接依赖|npm|
|path-to-regexp|0.1.7|间接依赖|npm|
|execa|0.7.0|间接依赖|npm|
|define-property|2.0.2|间接依赖|npm|
|undefsafe|2.0.5|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|har-validator|5.1.5|间接依赖|npm|
|minimatch|5.1.6|间接依赖|npm|
|cookie-parser|1.4.6|直接依赖|npm|
|@aws-sdk/credential-provider-web-identity|3.378.0|间接依赖|npm|
|cli-boxes|1.0.0|间接依赖|npm|
|import-lazy|2.1.0|间接依赖|npm|
|strip-eof|1.0.0|间接依赖|npm|
|mkdirp|0.5.6|间接依赖|npm|
|safe-regex|1.1.0|间接依赖|npm|
|dom-serializer|2.0.0|间接依赖|npm|
|camelcase|4.1.0|间接依赖|npm|
|map-cache|0.2.2|间接依赖|npm|
|minimist|1.2.8|间接依赖|npm|
|encodeurl|1.0.2|间接依赖|npm|
|widest-line|2.0.1|间接依赖|npm|
|@selderee/plugin-htmlparser2|0.10.0|间接依赖|npm|
|@aws-sdk/middleware-logger|3.378.0|间接依赖|npm|
|touch|3.1.0|间接依赖|npm|
|json-schema|0.4.0|间接依赖|npm|
|progress|1.1.8|间接依赖|npm|
|@smithy/credential-provider-imds|2.0.1|间接依赖|npm|
|ret|0.1.15|间接依赖|npm|
|term-size|1.2.0|间接依赖|npm|
|domhandler|5.0.3|间接依赖|npm|
|duplexer3|0.1.5|间接依赖|npm|
|has-tostringtag|1.0.0|间接依赖|npm|
|latest-version|3.1.0|间接依赖|npm|
|bcrypt-pbkdf|1.0.2|间接依赖|npm|
|ee-first|1.1.1|间接依赖|npm|
|@babel/helper-string-parser|7.19.4|间接依赖|npm|
|safe-buffer|5.2.1|间接依赖|npm|
|cookie|0.5.0|间接依赖|npm|
|pug-linker|4.0.0|间接依赖|npm|
|js-stringify|1.0.2|间接依赖|npm|
|npm-run-path|2.0.2|间接依赖|npm|
|pug-lexer|5.0.1|间接依赖|npm|
|strip-ansi|4.0.0|间接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|@babel/helper-validator-identifier|7.19.1|间接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|readable-stream|2.3.8|间接依赖|npm|
|ipaddr.js|1.9.1|间接依赖|npm|
|mongodb-connection-string-url|2.6.0|间接依赖|npm|
|@smithy/util-base64|2.0.0|间接依赖|npm|
|@smithy/is-array-buffer|2.0.0|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|asn1|0.2.6|间接依赖|npm|
|pug|3.0.2|直接依赖|npm|
|arr-flatten|1.1.0|间接依赖|npm|
|is-retry-allowed|1.2.0|间接依赖|npm|
|@aws-sdk/middleware-sdk-sts|3.379.1|间接依赖|npm|
|module-alias|2.2.2|直接依赖|npm|
|is-extendable|0.1.1|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|extend-shallow|3.0.2|间接依赖|npm|
|iconv-lite|0.4.24|间接依赖|npm|
|dashdash|1.14.1|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|yauzl|2.10.0|间接依赖|npm|
|toidentifier|1.0.1|间接依赖|npm|
|isarray|0.0.1|间接依赖|npm|
|semver|5.7.2|间接依赖|npm|
|performance-now|2.1.0|间接依赖|npm|
|@smithy/invalid-dependency|2.0.1|间接依赖|npm|
|qs|6.11.0|间接依赖|npm|
|decode-uri-component|0.2.2|间接依赖|npm|
|fd-slicer|1.1.0|间接依赖|npm|
|editorconfig|1.0.4|间接依赖|npm|
|registry-auth-token|3.4.0|间接依赖|npm|
|side-channel|1.0.4|间接依赖|npm|
|proto-list|1.2.4|间接依赖|npm|
|@smithy/fetch-http-handler|2.0.1|间接依赖|npm|
|yallist|4.0.0|间接依赖|npm|
|string_decoder|1.1.1|间接依赖|npm|
|fill-range|4.0.0|间接依赖|npm|
|component-emitter|1.3.0|间接依赖|npm|
|dot-prop|4.2.1|间接依赖|npm|
|url-parse-lax|1.0.0|间接依赖|npm|
|unique-string|1.0.0|间接依赖|npm|
|fs-extra|1.0.0|间接依赖|npm|
|moment|2.29.4|直接依赖|npm|
|uuid|8.3.2|间接依赖|npm|
|process-nextick-args|2.0.1|直接依赖|npm|
|@aws-sdk/middleware-signing|3.379.1|间接依赖|npm|
|@types/whatwg-url|8.2.2|间接依赖|npm|
|resend|0.17.2|直接依赖|npm|
|lru-cache|6.0.0|间接依赖|npm|
|forwarded|0.2.0|间接依赖|npm|
|psl|1.9.0|间接依赖|npm|
|update-notifier|2.5.0|间接依赖|npm|
|write-file-atomic|2.4.3|间接依赖|npm|
|character-parser|2.2.0|间接依赖|npm|
|dotenv|4.0.0|直接依赖|npm|
|extend-shallow|2.0.1|间接依赖|npm|
|pug-load|3.0.0|间接依赖|npm|
|@aws-sdk/util-endpoints|3.382.0|间接依赖|npm|
|lodash.once|4.1.1|间接依赖|npm|
|jsonwebtoken|8.5.1|直接依赖|npm|
|mongoose|6.11.5|直接依赖|npm|
|@aws-sdk/middleware-host-header|3.379.1|间接依赖|npm|
|get-stream|3.0.0|间接依赖|npm|
|kew|0.7.0|间接依赖|npm|
|bindings|1.5.0|间接依赖|npm|
|pug-walk|2.0.0|间接依赖|npm|
|global-dirs|0.1.1|间接依赖|npm|
|object-inspect|1.12.3|间接依赖|npm|
|@smithy/smithy-client|2.0.1|间接依赖|npm|
|currency.js|2.0.4|直接依赖|npm|
|@smithy/eventstream-codec|2.0.1|间接依赖|npm|
|@smithy/util-stream|2.0.1|间接依赖|npm|
|aws-sign2|0.7.0|间接依赖|npm|
|@smithy/config-resolver|2.0.1|间接依赖|npm|
|busboy|0.2.14|间接依赖|npm|
|pascalcase|0.1.1|间接依赖|npm|
|pug-parser|6.0.0|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|unzip-response|2.0.1|间接依赖|npm|
|abbrev|1.1.1|间接依赖|npm|
|fsevents|1.2.13|直接依赖|npm|
|is-core-module|2.11.0|间接依赖|npm|
|binary-extensions|1.13.1|间接依赖|npm|
|pug-strip-comments|2.0.0|间接依赖|npm|
|@smithy/util-retry|2.0.0|间接依赖|npm|
|tweetnacl|0.14.5|间接依赖|npm|
|nodemon|1.19.4|直接依赖|npm|
|@smithy/middleware-stack|2.0.0|间接依赖|npm|
|nanomatch|1.2.13|间接依赖|npm|
|lodash.isplainobject|4.0.6|间接依赖|npm|
|type-is|1.6.18|间接依赖|npm|
|destroy|1.2.0|间接依赖|npm|
|glob|7.1.1|直接依赖|npm|
|is-installed-globally|0.1.0|间接依赖|npm|
|@aws-sdk/util-locate-window|3.310.0|间接依赖|npm|
|@smithy/querystring-parser|2.0.1|间接依赖|npm|
|depd|2.0.0|间接依赖|npm|
|@aws-sdk/util-utf8-browser|3.259.0|间接依赖|npm|
|@smithy/middleware-endpoint|2.0.1|间接依赖|npm|
|@smithy/middleware-content-length|2.0.1|间接依赖|npm|
|bytes|3.1.2|间接依赖|npm|
|ecdsa-sig-formatter|1.0.11|间接依赖|npm|
|define-property|1.0.0|间接依赖|npm|
|peberminta|0.8.0|间接依赖|npm|
|ecc-jsbn|0.1.2|间接依赖|npm|
|@smithy/property-provider|2.0.1|间接依赖|npm|
|pretty|2.0.0|间接依赖|npm|
|@smithy/abort-controller|2.0.1|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|dicer|0.2.5|间接依赖|npm|
|doctypes|1.1.0|间接依赖|npm|
|jsbn|0.1.1|间接依赖|npm|
|readdirp|2.2.1|间接依赖|npm|
|micromatch|3.1.10|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|is-typedarray|1.0.0|间接依赖|npm|
|asap|2.0.6|间接依赖|npm|
|follow-redirects|1.15.2|间接依赖|npm|
|oauth-sign|0.9.0|间接依赖|npm|
|cache-base|1.0.1|间接依赖|npm|
|array-unique|0.3.2|间接依赖|npm|
|domelementtype|2.3.0|间接依赖|npm|
|@aws-sdk/client-sts|3.385.0|间接依赖|npm|
|http-signature|1.2.0|间接依赖|npm|
|repeat-element|1.1.4|间接依赖|npm|
|snapdragon-util|3.0.1|间接依赖|npm|
|signal-exit|3.0.7|间接依赖|npm|
|lodash.isstring|4.0.1|间接依赖|npm|
|regex-not|1.0.2|间接依赖|npm|
|is-glob|4.0.3|间接依赖|npm|
|@aws-crypto/util|3.0.0|间接依赖|npm|
|urix|0.1.0|间接依赖|npm|
|body-parser|1.20.1|间接依赖|npm|
|source-map|0.5.7|间接依赖|npm|
|tslib|2.6.1|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|hasha|2.2.0|间接依赖|npm|
|which|1.3.1|间接依赖|npm|
|anymatch|2.0.0|间接依赖|npm|
|concat-stream|1.6.2|间接依赖|npm|
|@smithy/types|2.0.2|间接依赖|npm|
|config-chain|1.1.13|间接依赖|npm|
|kind-of|6.0.3|间接依赖|npm|
|uuid|3.4.0|间接依赖|npm|
|to-fast-properties|2.0.0|间接依赖|npm|
|kind-of|3.2.2|间接依赖|npm|
|glob-parent|3.1.0|间接依赖|npm|
|kareem|2.5.1|间接依赖|npm|
|object.pick|1.3.0|间接依赖|npm|
|tslib|1.14.1|间接依赖|npm|
|es6-promise|4.2.8|间接依赖|npm|
|pstree.remy|1.1.8|间接依赖|npm|
|on-finished|2.4.1|间接依赖|npm|
|@aws-crypto/sha256-js|3.0.0|间接依赖|npm|
|fast-xml-parser|4.2.5|间接依赖|npm|
|bson|4.7.2|间接依赖|npm|
|@aws-sdk/middleware-user-agent|3.382.0|间接依赖|npm|
|to-regex-range|2.1.1|间接依赖|npm|
|fresh|0.5.2|间接依赖|npm|
|graceful-fs|4.2.11|直接依赖|npm|
|debug|4.3.4|间接依赖|npm|
|jstransformer|1.0.0|间接依赖|npm|
|@smithy/util-buffer-from|2.0.0|间接依赖|npm|
|range-parser|1.2.1|间接依赖|npm|
|readable-stream|1.1.14|间接依赖|npm|
|@types/node|20.4.8|间接依赖|npm|
|string_decoder|0.10.31|间接依赖|npm|
|append-field|1.0.0|间接依赖|npm|
|source-map-resolve|0.5.3|间接依赖|npm|
|webidl-conversions|7.0.0|间接依赖|npm|
|ansi-align|2.0.0|间接依赖|npm|
|@aws-sdk/credential-provider-cognito-identity|3.385.0|间接依赖|npm|
|source-map-url|0.4.1|间接依赖|npm|
|merge-descriptors|1.0.1|间接依赖|npm|
|async-each|1.0.6|间接依赖|npm|
|imurmurhash|0.1.4|间接依赖|npm|
|@aws-sdk/client-cognito-identity|3.385.0|间接依赖|npm|
|phantomjs-prebuilt|2.1.16|直接依赖|npm|
|is-path-inside|1.0.1|间接依赖|npm|
|@aws-sdk/credential-provider-ini|3.385.0|间接依赖|npm|
|extend|3.0.2|间接依赖|npm|
|content-type|1.0.5|间接依赖|npm|
|klaw|1.3.1|间接依赖|npm|
|remove-trailing-separator|1.1.0|直接依赖|npm|
|lowercase-keys|1.0.1|间接依赖|npm|
|proxy-from-env|1.1.0|间接依赖|npm|
|aws4|1.12.0|间接依赖|npm|
|assert-never|1.2.1|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|glob|8.1.0|间接依赖|npm|
|@smithy/node-config-provider|2.0.1|间接依赖|npm|
|pug-filters|4.0.0|间接依赖|npm|
|ini|1.3.8|间接依赖|npm|
|@smithy/util-body-length-node|2.0.0|间接依赖|npm|
|@smithy/signature-v4|2.0.1|间接依赖|npm|
|snapdragon-node|2.1.1|间接依赖|npm|
|is-stream|1.1.0|间接依赖|npm|
|qs|6.5.3|间接依赖|npm|
|@types/webidl-conversions|7.0.0|间接依赖|npm|
|commander|10.0.1|间接依赖|npm|
|is-binary-path|1.0.1|间接依赖|npm|
|buffer-equal-constant-time|1.0.1|间接依赖|npm|
|smart-buffer|4.2.0|间接依赖|npm|
|@aws-crypto/crc32|3.0.0|间接依赖|npm|
|@aws-sdk/credential-provider-sso|3.385.0|间接依赖|npm|
|atob|2.1.2|间接依赖|npm|
|is-promise|2.2.2|间接依赖|npm|
|negotiator|0.6.3|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|is-expression|4.0.0|间接依赖|npm|
|is-number|3.0.0|间接依赖|npm|
|sshpk|1.17.0|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|scheduler|0.23.0|间接依赖|npm|
|statuses|2.0.1|间接依赖|npm|
|repeat-string|1.6.1|间接依赖|npm|
|async|2.6.4|间接依赖|npm|
|base64-js|1.5.1|间接依赖|npm|
|is-ci|1.2.1|间接依赖|npm|
|rc|1.2.8|间接依赖|npm|
|parseurl|1.3.3|间接依赖|npm|
|path-dirname|1.0.2|间接依赖|npm|
|@smithy/util-defaults-mode-node|2.0.1|间接依赖|npm|
|selderee|0.10.0|间接依赖|npm|
|got|6.7.1|间接依赖|npm|
|@babel/parser|7.21.3|间接依赖|npm|
|pug-error|2.0.0|间接依赖|npm|
|create-error-class|3.0.2|间接依赖|npm|
|is-regex|1.1.4|间接依赖|npm|
|braces|2.3.2|间接依赖|npm|
|minimatch|9.0.1|间接依赖|npm|
|@smithy/url-parser|2.0.1|间接依赖|npm|
|semver-diff|2.1.0|间接依赖|npm|
|is-descriptor|1.0.2|间接依赖|npm|
|socks|2.7.1|间接依赖|npm|
|extract-zip|1.7.0|间接依赖|npm|
|nan|2.17.0|间接依赖|npm|
|@aws-sdk/credential-providers|3.385.0|直接依赖|npm|
|@aws-sdk/token-providers|3.385.0|间接依赖|npm|
|raw-body|2.5.1|间接依赖|npm|
|punycode|2.3.0|间接依赖|npm|
|@smithy/util-middleware|2.0.0|间接依赖|npm|
|memory-pager|1.5.0|间接依赖|npm|
|tr46|3.0.0|间接依赖|npm|
|proxy-addr|2.0.7|间接依赖|npm|
|@aws-crypto/ie11-detection|3.0.0|间接依赖|npm|
|assert-plus|1.0.0|间接依赖|npm|
|ajv|6.12.6|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|string-width|2.1.1|间接依赖|npm|
|is-windows|1.0.2|间接依赖|npm|
|react-dom|18.2.0|间接依赖|npm|
|jws|3.2.2|间接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|@smithy/util-uri-escape|2.0.0|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|debug|2.6.9|间接依赖|npm|
|boxen|1.3.0|间接依赖|npm|
|pseudomap|1.0.2|直接依赖|npm|
|throttleit|1.0.0|间接依赖|npm|
|is-extendable|1.0.1|间接依赖|npm|
|har-schema|2.0.0|间接依赖|npm|
|@aws-sdk/credential-provider-process|3.378.0|间接依赖|npm|
|buffer-crc32|0.2.13|间接依赖|npm|
|ieee754|1.2.1|间接依赖|npm|
|mpath|0.9.0|间接依赖|npm|
|supports-preserve-symlinks-flag|1.0.0|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|html-pdf|3.0.1|直接依赖|npm|
|request|2.88.2|间接依赖|npm|
|leac|0.6.0|间接依赖|npm|
|is-buffer|1.1.6|间接依赖|npm|
|core-util-is|1.0.2|间接依赖|npm|
|sift|16.0.1|间接依赖|npm|
|pug-code-gen|3.0.2|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|extsprintf|1.3.0|间接依赖|npm|
|is-obj|1.0.1|间接依赖|npm|
|bcryptjs|2.4.3|直接依赖|npm|
|array-flatten|1.1.1|间接依赖|npm|
|is-fullwidth-code-point|2.0.0|间接依赖|npm|
|form-data|4.0.0|间接依赖|npm|
|jsonfile|2.4.0|间接依赖|npm|
|isobject|3.0.1|间接依赖|npm|
|type-fest|3.13.0|间接依赖|npm|
|accepts|1.3.8|间接依赖|npm|
|typedarray|0.0.6|间接依赖|npm|
|loose-envify|1.4.0|间接依赖|npm|
|nopt|6.0.0|间接依赖|npm|
|@aws-sdk/util-user-agent-node|3.378.0|间接依赖|npm|
|whatwg-url|11.0.0|间接依赖|npm|
|ms|2.0.0|间接依赖|npm|
|arr-diff|4.0.0|间接依赖|npm|
|@aws-sdk/middleware-recursion-detection|3.378.0|间接依赖|npm|
|react|18.2.0|直接依赖|npm|
|ci-info|1.6.0|间接依赖|npm|
|lodash.isinteger|4.0.4|间接依赖|npm|
|@smithy/service-error-classification|2.0.0|间接依赖|npm|
|@smithy/middleware-serde|2.0.1|间接依赖|npm|
|p-finally|1.0.0|间接依赖|npm|
|sparse-bitfield|3.0.3|间接依赖|npm|
|http-errors|2.0.0|间接依赖|npm|
|resolve-url|0.2.1|间接依赖|npm|
|jsprim|1.4.2|间接依赖|npm|
|isstream|0.1.2|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|is-npm|1.0.0|间接依赖|npm|
|is-glob|3.1.0|间接依赖|npm|
|@smithy/middleware-retry|2.0.1|间接依赖|npm|
|acorn|7.4.1|间接依赖|npm|
|mongoose-autopopulate|0.14.0|直接依赖|npm|
|json-stringify-safe|5.0.1|间接依赖|npm|
|xtend|4.0.2|间接依赖|npm|
|pinkie-promise|2.0.1|间接依赖|npm|
|@smithy/protocol-http|2.0.1|间接依赖|npm|
|upath|1.2.0|间接依赖|npm|
|serve-static|1.15.0|间接依赖|npm|
|express|4.18.2|直接依赖|npm|
|@aws-sdk/credential-provider-env|3.378.0|间接依赖|npm|
|buffer|5.7.1|间接依赖|npm|
|constantinople|4.0.1|间接依赖|npm|
|xdg-basedir|3.0.0|间接依赖|npm|
|getpass|0.1.7|间接依赖|npm|
|htmlparser2|8.0.2|间接依赖|npm|
|entities|4.5.0|间接依赖|npm|
|streamsearch|0.1.2|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|etag|1.8.1|间接依赖|npm|
|deepmerge|4.3.1|间接依赖|npm|
|delayed-stream|1.0.0|间接依赖|npm|
|content-disposition|0.5.4|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|define-property|0.2.5|间接依赖|npm|
|methods|1.1.2|间接依赖|npm|
|color-name|1.1.3|间接依赖|npm|
|request-progress|2.0.1|间接依赖|npm|
|finalhandler|1.2.0|间接依赖|npm|
|mime-types|2.1.35|间接依赖|npm|
|verror|1.10.0|间接依赖|npm|
|timed-out|4.0.1|间接依赖|npm|
|core-util-is|1.0.3|间接依赖|npm|
|@smithy/util-defaults-mode-browser|2.0.1|间接依赖|npm|
|isarray|1.0.0|间接依赖|npm|
|extglob|2.0.4|间接依赖|npm|
|@aws-crypto/sha256-browser|3.0.0|间接依赖|npm|
|debug|3.2.7|间接依赖|npm|
|utils-merge|1.0.1|间接依赖|npm|
|ms|2.1.3|间接依赖|npm|
|to-regex|3.0.2|间接依赖|npm|
|void-elements|3.1.0|间接依赖|npm|
|ansi-regex|3.0.1|间接依赖|npm|
|parseley|0.11.0|间接依赖|npm|
|pug-runtime|3.0.1|间接依赖|npm|
|semver|7.5.4|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|pug-attrs|3.0.0|间接依赖|npm|
|@smithy/util-config-provider|2.0.0|间接依赖|npm|
|strnum|1.0.5|间接依赖|npm|
|chokidar|2.1.8|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|escape-html|1.0.3|间接依赖|npm|
|mime|1.6.0|间接依赖|npm|
|expand-brackets|2.1.4|间接依赖|npm|
|cross-spawn|5.1.0|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|multer|1.4.4|直接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)