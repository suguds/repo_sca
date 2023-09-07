# akaunting/akaunting安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699852809985114112.svg)](https://www.murphysec.com/console/report/1694778019133419520/1699852809985114112)

仓库描述：Free and Online Accounting Software

仓库地址：[https://github.com/akaunting/akaunting](https://github.com/akaunting/akaunting)

| star：6574 | watch：216 | fork：2130 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-07 21:05:13 | 许可证：GPL-3.0 |
| 最近检测时间：2023-09-08 02:32:05 | 组件总数：586 | 漏洞总数：21 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|lodash 存在拒绝服务漏洞|拒绝服务|[MPS-2019-1228](https://www.oscs1024.com/hd/MPS-2019-1228)|CVE-2018-16487|中危|
|lodash <4.7.11 正则表达式拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2019-8123](https://www.oscs1024.com/hd/MPS-2019-8123)|CVE-2019-1010266|中危|
|lodash 原型污染漏洞|拒绝服务|[MPS-2019-8636](https://www.oscs1024.com/hd/MPS-2019-8636)|CVE-2019-10744|严重|
|Ajv v6.12.2 输入验证错误漏洞|MAID|[MPS-2020-10525](https://www.oscs1024.com/hd/MPS-2020-10525)|CVE-2020-15366|中危|
|lodash <4.17.15 原型污染漏洞|原型污染|[MPS-2020-15679](https://www.oscs1024.com/hd/MPS-2020-15679)|CVE-2020-8203|高危|
|lodash 拒绝服务漏洞|拒绝服务|[MPS-2021-2574](https://www.oscs1024.com/hd/MPS-2021-2574)|CVE-2020-28500|中危|
|lodash 命令注入漏洞|代码注入|[MPS-2021-2638](https://www.oscs1024.com/hd/MPS-2021-2638)|CVE-2021-23337|高危|
|async-validator 正则表达式拒绝服务漏洞|ReDoS|[MPS-2021-33879](https://www.oscs1024.com/hd/MPS-2021-33879)|CVE-2021-3887|中危|
|ws 存在拒绝服务漏洞||[MPS-2021-7109](https://www.oscs1024.com/hd/MPS-2021-7109)|CVE-2021-32640|中危|
|Laravel v9.1.8 反序列化漏洞|反序列化|[MPS-2022-10162](https://www.oscs1024.com/hd/MPS-2022-10162)|CVE-2022-30778|严重|
|Moment.js 正则拒绝服务漏洞|拒绝服务|[MPS-2022-11159](https://www.oscs1024.com/hd/MPS-2022-11159)|CVE-2022-31129|高危|
|lodash<4.17.20 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13841](https://www.oscs1024.com/hd/MPS-2022-13841)||高危|
|lodash<4.17.17 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13842](https://www.oscs1024.com/hd/MPS-2022-13842)||高危|
|dompdf/dompdf 存在代码注入漏洞|代码注入|[MPS-2022-14193](https://www.oscs1024.com/hd/MPS-2022-14193)||高危|
|jsonwebtoken远程代码执行漏洞|代码注入|[MPS-2022-1956](https://www.oscs1024.com/hd/MPS-2022-1956)|CVE-2022-23529|高危|
|jsonwebtoken 加密问题漏洞|密码算法不安全|[MPS-2022-1966](https://www.oscs1024.com/hd/MPS-2022-1966)|CVE-2022-23539|高危|
|jsonwebtoken 数据伪造问题漏洞|密码学签名的验证不恰当|[MPS-2022-1967](https://www.oscs1024.com/hd/MPS-2022-1967)|CVE-2022-23540|高危|
|JsonWebToken < 9.0.0 存在身份验证绕过|身份验证不当|[MPS-2022-1968](https://www.oscs1024.com/hd/MPS-2022-1968)|CVE-2022-23541|中危|
|Moment.js 路径遍历漏洞|路径遍历|[MPS-2022-3752](https://www.oscs1024.com/hd/MPS-2022-3752)|CVE-2022-24785|中危|
|Express 中的 qs 模块存在原型污染漏洞|原型污染|[MPS-2022-3967](https://www.oscs1024.com/hd/MPS-2022-3967)|CVE-2022-24999|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|laravel/framework|v10.21.0||间接依赖|强烈建议修复|C:1|H:0|M:0|L:0|
|qs|6.5.2|6.10.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|dompdf/dompdf|v2.0.3||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|jsonwebtoken|8.5.0|9.0.0|间接依赖|建议修复|C:0|H:3|M:1|L:0|
|lodash|4.17.11|4.17.21|间接依赖|建议修复|C:1|H:4|M:1|L:0|
|express|4.16.4|4.17.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|lodash|4.17.5|4.17.21|间接依赖|建议修复|C:1|H:4|M:3|L:0|
|semver|7.5.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|moment|2.22.2|2.29.4|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|ws|6.2.0|7.4.6|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|6.3.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|ajv|6.10.0|6.12.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|async-validator|1.8.5|4.0.4|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|466|Low|
|BSD-3-Clause|32|Low|
|ISC|19|Low|
|BSD-2-Clause|2|Low|
|LGPL-3.0|3|Medium|
|LGPL-2.0|5|Medium|
|LGPL-2.1|2|Medium|
|Apache-2.0|12|Low|
|AGPL-3.0|2|High|
|BSD-4-Clause|4|Low|
|0BSD|1|Low|
|GPL-3.0|2|Medium|
|GPL-2.0|1|Medium|
|CC0-1.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|encodeurl|1.0.2|间接依赖|npm|
|timer2|1.0.0|间接依赖|npm|
|processenv|1.1.0|间接依赖|npm|
|utils-merge|1.0.1|间接依赖|npm|
|psr/http-factory|1.0.2|间接依赖|composer|
|finalhandler|1.1.1|间接依赖|npm|
|uuidv4|2.0.0|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|object-hash|3.0.0|间接依赖|npm|
|php-http/httplug|2.4.0|间接依赖|composer|
|hoa/event|1.17.01.13|间接依赖|composer|
|regenerator-runtime|0.13.11|间接依赖|npm|
|@algolia/logger-console|4.17.1|间接依赖|npm|
|hoa/protocol||间接依赖|composer|
|side-channel|1.0.4|间接依赖|npm|
|ralouphie/getallheaders|3.0.3|间接依赖|composer|
|sanmai/hoa-protocol|1.21|间接依赖|composer|
|string.prototype.trim|1.2.7|间接依赖|npm|
|league/flysystem-aws-s3-v3|3.15.0|间接依赖|composer|
|date-fns|2.30.0|间接依赖|npm|
|picomatch|2.3.1|间接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|postcss-selector-parser|6.0.13|间接依赖|npm|
|tsscmp|1.0.6|间接依赖|npm|
|symfony/polyfill-php80|v1.28.0|间接依赖|composer|
|for-each|0.3.3|间接依赖|npm|
|has-property-descriptors|1.0.0|间接依赖|npm|
|node-statsd|0.1.1|间接依赖|npm|
|hoa/ustring|4.17.01.16|间接依赖|composer|
|webmozart/assert|1.11.0|间接依赖|composer|
|symfony/translation|v6.3.3|间接依赖|composer|
|jenssegers/agent|v2.6.4|间接依赖|composer|
|send|0.16.2|间接依赖|npm|
|nocache|2.0.0|间接依赖|npm|
|lodash.includes|4.3.0|间接依赖|npm|
|gopd|1.0.1|间接依赖|npm|
|symfony/css-selector|v6.3.2|间接依赖|composer|
|function-bind|1.1.1|间接依赖|npm|
|negotiator|0.6.3|间接依赖|npm|
|is-core-module|2.12.1|间接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|@algolia/cache-browser-local-storage|4.17.1|间接依赖|npm|
|preact|10.12.1|间接依赖|npm|
|kkszymanowski/traitor|1.0.0|间接依赖|composer|
|buffer-more-ints|0.0.2|间接依赖|npm|
|http-interop/http-factory-guzzle|1.2.0|间接依赖|composer|
|symfony/http-foundation|v6.3.4|间接依赖|composer|
|stringify-object|3.3.0|间接依赖|npm|
|is-number|7.0.0|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|laravel/prompts|v0.1.6|间接依赖|composer|
|is-regex|1.1.4|间接依赖|npm|
|quill|1.3.7|间接依赖|npm|
|akaunting/module-paypal-standard|3.0.1|间接依赖|composer|
|markbaker/matrix|3.0.1|间接依赖|composer|
|ramsey/collection|2.0.0|间接依赖|composer|
|illuminate/contracts||间接依赖|composer|
|morgan|1.9.1|间接依赖|npm|
|php-64bit||间接依赖|composer|
|destroy|1.0.4|间接依赖|npm|
|asynckit|0.4.0|间接依赖|npm|
|@algolia/client-analytics|4.17.1|间接依赖|npm|
|@vue/compiler-sfc|2.7.14|间接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|split2|3.0.0|间接依赖|npm|
|akaunting/laravel-language|1.0.22|间接依赖|composer|
|symfony/http-client-contracts|v3.3.0|间接依赖|composer|
|@algolia/client-search|4.17.1|间接依赖|npm|
|proxy-from-env|1.1.0|间接依赖|npm|
|is-binary-path|2.1.0|间接依赖|npm|
|object-is|1.1.5|间接依赖|npm|
|akaunting/laravel-menu|3.1.0|间接依赖|composer|
|brace-expansion|1.1.11|间接依赖|npm|
|dompdf/dompdf|v2.0.3|间接依赖|composer|
|glightbox|3.2.0|间接依赖|npm|
|staudenmeir/eloquent-has-many-deep-contracts|v1.1|间接依赖|composer|
|arg|5.0.2|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|has-tostringtag|1.0.0|间接依赖|npm|
|cors|2.8.5|间接依赖|npm|
|symfony/translation-contracts|v3.3.0|间接依赖|composer|
|debug|2.6.9|间接依赖|npm|
|app-root-path|2.1.0|间接依赖|npm|
|is-string|1.0.7|间接依赖|npm|
|body-parser|1.18.3|间接依赖|npm|
|akaunting/laravel-firewall|2.1.5|间接依赖|composer|
|doctrine/dbal|3.6.6|间接依赖|composer|
|unpipe|1.0.0|间接依赖|npm|
|@algolia/client-account|4.17.1|间接依赖|npm|
|akaunting/laravel-debugbar-collector|2.1.1|间接依赖|composer|
|es-set-tostringtag|2.0.1|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|bkwld/cloner|3.11.1|间接依赖|composer|
|hoa/exception|1.17.01.16|间接依赖|composer|
|@babel/runtime|7.1.2|间接依赖|npm|
|illuminate/view||间接依赖|composer|
|regenerator-runtime|0.11.1|间接依赖|npm|
|serve-static|1.13.2|间接依赖|npm|
|moneyphp/money|v4.2.0|间接依赖|composer|
|flatpickr|4.6.13|间接依赖|npm|
|barryvdh/laravel-dompdf|v2.0.1|间接依赖|composer|
|symfony/options-resolver|v6.3.0|间接依赖|composer|
|league/oauth2-client|2.7.0|间接依赖|composer|
|symfony/error-handler|v6.3.2|间接依赖|composer|
|lodash.isboolean|3.0.3|间接依赖|npm|
|symfony/deprecation-contracts|v3.3.0|间接依赖|composer|
|get-intrinsic|1.2.1|间接依赖|npm|
|eventemitter3|2.0.3|间接依赖|npm|
|binary-extensions|2.2.0|间接依赖|npm|
|is-arguments|1.1.1|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|is-typed-array|1.1.10|间接依赖|npm|
|http-errors|1.6.3|间接依赖|npm|
|php-http/async-client-implementation||间接依赖|composer|
|once|1.4.0|间接依赖|npm|
|@sentry/vue|7.53.1|间接依赖|npm|
|object.assign|4.1.4|间接依赖|npm|
|akaunting/laravel-version|1.0.4|间接依赖|composer|
|@algolia/client-personalization|4.17.1|间接依赖|npm|
|uuid|3.3.2|间接依赖|npm|
|psr/http-client|1.0.2|间接依赖|composer|
|@docsearch/js|3.4.0|间接依赖|npm|
|vue-clipboard2|0.3.3|间接依赖|npm|
|resolve|1.22.2|间接依赖|npm|
|illuminate/session||间接依赖|composer|
|accepts|1.3.8|间接依赖|npm|
|is-array-buffer|3.0.2|间接依赖|npm|
|doctrine/event-manager|2.0.0|间接依赖|composer|
|async-limiter|1.0.1|间接依赖|npm|
|laravel/framework|v10.21.0|间接依赖|composer|
|camelcase-css|2.0.1|间接依赖|npm|
|doctrine/lexer|3.0.0|间接依赖|composer|
|@jridgewell/sourcemap-codec|1.4.14|间接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|lodash.isplainobject|4.0.6|间接依赖|npm|
|akaunting/laravel-apexcharts|3.0.1|间接依赖|composer|
|v-money|0.8.1|间接依赖|npm|
|guzzlehttp/guzzle|7.8.0|间接依赖|composer|
|dflydev/dot-access-data|v3.0.2|间接依赖|composer|
|illuminate/validation||间接依赖|composer|
|phpstan/phpdoc-parser|1.23.1|间接依赖|composer|
|laravel/ui|v4.2.2|间接依赖|composer|
|guzzlehttp/uri-template|v1.0.2|间接依赖|composer|
|typed-array-length|1.0.4|间接依赖|npm|
|hoa/iterator|2.17.01.10|间接依赖|composer|
|bugsnag/bugsnag|v3.29.1|间接依赖|composer|
|parseurl|1.3.3|间接依赖|npm|
|lines-and-columns|1.2.4|间接依赖|npm|
|psr/cache|3.0.0|间接依赖|composer|
|intervention/imagecache|2.6.0|间接依赖|composer|
|league/config|v1.2.0|间接依赖|composer|
|setprototypeof|1.1.0|间接依赖|npm|
|combined-stream|1.0.8|间接依赖|npm|
|@fullcalendar/daygrid|6.1.8|间接依赖|npm|
|object.getownpropertydescriptors|2.1.6|间接依赖|npm|
|ee-first|1.1.1|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|laravel/sanctum|v3.2.6|间接依赖|composer|
|lodash|4.17.11|间接依赖|npm|
|pify|2.3.0|间接依赖|npm|
|doctrine/deprecations|v1.1.1|间接依赖|composer|
|has-proto|1.0.1|间接依赖|npm|
|is-number-object|1.0.7|间接依赖|npm|
|internal-slot|1.0.5|间接依赖|npm|
|akaunting/laravel-module|3.0.1|间接依赖|composer|
|ecdsa-sig-formatter|1.0.11|间接依赖|npm|
|@sentry/tracing|7.53.1|间接依赖|npm|
|call-bind|1.0.2|间接依赖|npm|
|es-to-primitive|1.2.1|间接依赖|npm|
|commands-events|1.0.4|间接依赖|npm|
|functions-have-names|1.2.3|间接依赖|npm|
|symfony/uid|v6.3.0|间接依赖|composer|
|json-schema-traverse|0.4.1|间接依赖|npm|
|nikic/php-parser|v4.17.1|间接依赖|composer|
|doctrine/inflector|2.0.8|间接依赖|composer|
|varname|2.0.3|间接依赖|npm|
|retry|0.12.0|间接依赖|npm|
|qs|6.5.2|间接依赖|npm|
|tiny-emitter|2.1.0|间接依赖|npm|
|media-typer|0.3.0|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|@algolia/requester-browser-xhr|4.17.1|间接依赖|npm|
|opis/closure|3.6.3|间接依赖|composer|
|symfony/process|v6.3.4|间接依赖|composer|
|symfony/postmark-mailer|v6.3.0|间接依赖|composer|
|on-headers|1.0.2|间接依赖|npm|
|nesbot/carbon|2.69.0|间接依赖|composer|
|methods|1.1.2|间接依赖|npm|
|basic-auth|2.0.1|间接依赖|npm|
|glob-parent|6.0.2|间接依赖|npm|
|array-buffer-byte-length|1.0.0|间接依赖|npm|
|find-root|1.1.0|间接依赖|npm|
|good-listener|1.2.2|间接依赖|npm|
|@algolia/transporter|4.17.1|间接依赖|npm|
|hase|2.0.0|间接依赖|npm|
|@babel/parser|7.22.4|间接依赖|npm|
|livewire/livewire|v2.12.6|间接依赖|composer|
|lodash.isnumber|3.0.3|间接依赖|npm|
|php-http/message-factory|1.1.0|间接依赖|composer|
|draht|1.0.1|间接依赖|npm|
|symfony/mailgun-mailer|v6.3.2|间接依赖|composer|
|tslib|1.14.1|间接依赖|npm|
|chokidar|3.5.3|间接依赖|npm|
|postcss-value-parser|4.2.0|间接依赖|npm|
|@fullcalendar/core|6.1.8|间接依赖|npm|
|@nodelib/fs.stat|2.0.5|间接依赖|npm|
|es6-promise|4.2.8|间接依赖|npm|
|readdirp|3.6.0|间接依赖|npm|
|moment|2.22.2|间接依赖|npm|
|clone|2.1.2|间接依赖|npm|
|compression|1.7.3|间接依赖|npm|
|source-map-js|1.0.2|间接依赖|npm|
|parchment|1.1.4|间接依赖|npm|
|axios|1.4.0|间接依赖|npm|
|plank/laravel-mediable|5.9.1|间接依赖|composer|
|hoa/stream|1.17.02.21|间接依赖|composer|
|etag|1.8.1|间接依赖|npm|
|supports-preserve-symlinks-flag|1.0.0|间接依赖|npm|
|vlucas/phpdotenv|v5.5.0|间接依赖|composer|
|voku/portable-ascii|2.0.1|间接依赖|composer|
|@popperjs/core|2.11.8|间接依赖|npm|
|jws|3.2.2|间接依赖|npm|
|@docsearch/react|3.4.0|间接依赖|npm|
|composer/pcre|3.1.0|间接依赖|composer|
|composer/ca-bundle|1.3.7|间接依赖|composer|
|mime-db|1.52.0|间接依赖|npm|
|@sentry/replay|7.53.1|间接依赖|npm|
|merge2|1.4.1|间接依赖|npm|
|vue-router|3.6.5|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|simshaun/recurr|v5.0.1|间接依赖|composer|
|qs|6.11.2|间接依赖|npm|
|@docsearch/css|3.4.0|间接依赖|npm|
|postcss-load-config|4.0.1|间接依赖|npm|
|league/commonmark|2.4.1|间接依赖|composer|
|thenify-all|1.6.0|间接依赖|npm|
|nanoid|3.3.6|间接依赖|npm|
|php-http/client-common|2.7.0|间接依赖|composer|
|safe-array-concat|1.0.0|间接依赖|npm|
|fuse.js|6.6.2|间接依赖|npm|
|type-is|1.6.18|间接依赖|npm|
|symfony/string|v6.3.2|间接依赖|composer|
|inherits|2.0.3|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|symfony/event-dispatcher|v6.3.2|间接依赖|composer|
|throttle-debounce|1.1.0|间接依赖|npm|
|yallist|3.1.1|间接依赖|npm|
|nunomaduro/termwind|v1.15.1|间接依赖|composer|
|statuses|1.4.0|间接依赖|npm|
|doctrine/collections|1.8.0|间接依赖|composer|
|stethoskop|1.0.0|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|lorisleiva/laravel-search-string|v1.3.0|间接依赖|composer|
|semver|7.5.1|间接依赖|npm|
|dropzone|5.9.3|间接依赖|npm|
|doctrine/cache|2.2.0|间接依赖|composer|
|merge-descriptors|1.0.1|间接依赖|npm|
|vary|1.1.2|间接依赖|npm|
|core-util-is|1.0.3|间接依赖|npm|
|micromatch|4.0.5|间接依赖|npm|
|didyoumean|1.2.2|间接依赖|npm|
|balping/json-raw-encoder|v1.0.2|间接依赖|composer|
|symfony/polyfill-intl-grapheme|v1.28.0|间接依赖|composer|
|symfony/http-kernel|v6.3.4|间接依赖|composer|
|moment|2.29.4|间接依赖|npm|
|is-negative-zero|2.0.2|间接依赖|npm|
|brick/math|0.11.0|间接依赖|composer|
|clipboard|2.0.11|间接依赖|npm|
|object-keys|1.1.1|间接依赖|npm|
|maennchen/zipstream-php|3.1.0|间接依赖|composer|
|paragonie/random_compat|v9.99.100|间接依赖|composer|
|fastq|1.15.0|间接依赖|npm|
|@jridgewell/gen-mapping|0.3.3|间接依赖|npm|
|@themesberg/flowbite|1.3.0|间接依赖|npm|
|postcss-import|15.1.0|间接依赖|npm|
|lru-cache|5.1.1|间接依赖|npm|
|iconv-lite|0.4.23|间接依赖|npm|
|ws|6.2.0|间接依赖|npm|
|get-own-enumerable-property-symbols|3.0.2|间接依赖|npm|
|psr/clock|1.0.0|间接依赖|composer|
|maatwebsite/excel|3.1.48|间接依赖|composer|
|thenify|3.3.1|间接依赖|npm|
|omnipay/common|v3.2.1|间接依赖|composer|
|@tailwindcss/forms|0.5.3|间接依赖|npm|
|jaybizzle/crawler-detect|v1.2.116|间接依赖|composer|
|@babel/runtime|7.22.3|间接依赖|npm|
|amqplib|0.5.2|间接依赖|npm|
|normalize-wheel|1.0.1|间接依赖|npm|
|chalk|2.4.1|间接依赖|npm|
|illuminate/http||间接依赖|composer|
|aws/aws-sdk-php|3.280.0|间接依赖|composer|
|@babel/plugin-syntax-dynamic-import|7.8.3|间接依赖|npm|
|picocolors|1.0.0|间接依赖|npm|
|object-inspect|1.12.3|间接依赖|npm|
|@jridgewell/resolve-uri|3.1.0|间接依赖|npm|
|cssesc|3.0.0|间接依赖|npm|
|staudenmeir/eloquent-has-many-deep|v1.18.3|间接依赖|composer|
|lodash.isinteger|4.0.4|间接依赖|npm|
|json-schema|0.4.0|间接依赖|npm|
|@babel/runtime|7.2.0|间接依赖|npm|
|glob|7.1.6|间接依赖|npm|
|delegate|3.2.0|间接依赖|npm|
|phpdocumentor/reflection-common|2.2.0|间接依赖|composer|
|postcss-js|4.0.1|间接依赖|npm|
|es-abstract|1.21.2|间接依赖|npm|
|laravel/slack-notification-channel|v2.5.0|间接依赖|composer|
|league/flysystem-local|3.15.0|间接依赖|composer|
|select|1.1.2|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|guzzlehttp/psr7|2.6.1|间接依赖|composer|
|intervention/image|2.7.2|间接依赖|composer|
|akaunting/laravel-money|5.1.2|间接依赖|composer|
|string.prototype.trimstart|1.0.6|间接依赖|npm|
|@algolia/client-common|4.17.1|间接依赖|npm|
|csstype|3.1.2|间接依赖|npm|
|@algolia/autocomplete-preset-algolia|1.8.2|间接依赖|npm|
|ts-interface-checker|0.1.13|间接依赖|npm|
|akaunting/module-offline-payments|3.0.2|间接依赖|composer|
|genealabs/laravel-model-caching|0.13.4|间接依赖|composer|
|league/flysystem|3.15.1|间接依赖|composer|
|@alloc/quick-lru|5.2.0|间接依赖|npm|
|phpdocumentor/type-resolver|1.7.3|间接依赖|composer|
|tailwind|4.0.0|间接依赖|npm|
|@algolia/cache-in-memory|4.17.1|间接依赖|npm|
|form-data|4.0.0|间接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.15|间接依赖|npm|
|dragonmantank/cron-expression|v3.3.3|间接依赖|composer|
|babel-runtime|6.26.0|间接依赖|npm|
|@algolia/requester-common|4.17.1|间接依赖|npm|
|content-type|1.0.4|间接依赖|npm|
|symfony/var-dumper|v6.3.4|间接依赖|composer|
|path-parse|1.0.7|间接依赖|npm|
|has-bigints|1.0.2|间接依赖|npm|
|illuminate/cache||间接依赖|composer|
|phpoffice/phpspreadsheet|1.29.0|间接依赖|composer|
|@sentry/utils|7.53.1|间接依赖|npm|
|phenx/php-svg-lib|0.5.0|间接依赖|composer|
|semver|6.3.0|间接依赖|npm|
|sucrase|3.32.0|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|fresh|0.5.2|间接依赖|npm|
|lilconfig|2.1.0|间接依赖|npm|
|fast-glob|3.2.12|间接依赖|npm|
|egulias/email-validator|4.0.1|间接依赖|composer|
|@algolia/logger-common|4.17.1|间接依赖|npm|
|is-date-object|1.0.5|间接依赖|npm|
|illuminate/collections||间接依赖|composer|
|lodash.isstring|4.0.1|间接依赖|npm|
|laravel/serializable-closure|v1.3.1|间接依赖|composer|
|psr/http-factory-implementation||间接依赖|composer|
|is-glob|4.0.3|间接依赖|npm|
|illuminate/filesystem||间接依赖|composer|
|has-symbols|1.0.3|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|masterminds/html5|2.8.1|间接依赖|composer|
|hoa/consistency|1.17.05.02|间接依赖|composer|
|vue2-transitions|0.3.0|间接依赖|npm|
|aws/aws-crt-php|v1.2.2|间接依赖|composer|
|nette/schema|v1.2.4|间接依赖|composer|
|graham-campbell/result-type|v1.1.1|间接依赖|composer|
|balanced-match|1.0.2|间接依赖|npm|
|genealabs/laravel-pivot-events|10.0.1|间接依赖|composer|
|psr/http-message|2.0|间接依赖|composer|
|lodash.once|4.1.1|间接依赖|npm|
|illuminate/container||间接依赖|composer|
|illuminate/routing||间接依赖|composer|
|sentry/sdk|3.5.0|间接依赖|composer|
|eventemitter2|5.0.1|间接依赖|npm|
|composer/class-map-generator|1.1.0|间接依赖|composer|
|@babel/runtime|7.3.4|间接依赖|npm|
|is-symbol|1.0.4|间接依赖|npm|
|deep-equal|1.1.1|间接依赖|npm|
|crypto2|2.0.0|间接依赖|npm|
|is-weakref|1.0.2|间接依赖|npm|
|symfony/polyfill-mbstring|v1.28.0|间接依赖|composer|
|safer-buffer|2.1.2|间接依赖|npm|
|monolog/monolog|3.4.0|间接依赖|composer|
|on-finished|2.3.0|间接依赖|npm|
|safe-buffer|5.2.1|间接依赖|npm|
|phenx/php-font-lib|0.5.4|间接依赖|composer|
|@sentry/types|7.53.1|间接依赖|npm|
|datasette|1.0.1|间接依赖|npm|
|safe-regex-test|1.0.0|间接依赖|npm|
|laravel-mix-tailwind|0.1.2|间接依赖|npm|
|hoa/regex|1.17.01.13|间接依赖|composer|
|@fullcalendar/timegrid|6.1.8|间接依赖|npm|
|@algolia/autocomplete-core|1.8.2|间接依赖|npm|
|symfony/polyfill-intl-normalizer|v1.28.0|间接依赖|composer|
|@nodelib/fs.scandir|2.1.5|间接依赖|npm|
|sha-1|0.1.1|间接依赖|npm|
|asn1|0.2.3|间接依赖|npm|
|get-symbol-description|1.0.0|间接依赖|npm|
|queue-microtask|1.2.3|间接依赖|npm|
|laravel/tinker|v2.8.2|间接依赖|composer|
|readable-stream|1.1.14|间接依赖|npm|
|vee-validate|2.2.15|间接依赖|npm|
|cookie|0.3.1|间接依赖|npm|
|php-http/promise|1.1.0|间接依赖|composer|
|sabberworm/php-css-parser|8.4.0|间接依赖|composer|
|psy/psysh|v0.11.20|间接依赖|composer|
|bluebird|3.7.2|间接依赖|npm|
|buffer-equal-constant-time|1.0.1|间接依赖|npm|
|async-retry|1.2.3|间接依赖|npm|
|vue2-editor|2.10.3|间接依赖|npm|
|laravelcollective/html|v6.4.1|间接依赖|composer|
|dlv|1.1.3|间接依赖|npm|
|is-boolean-object|1.1.2|间接依赖|npm|
|akaunting/laravel-sortable|2.0.1|间接依赖|composer|
|lodash|4.17.5|间接依赖|npm|
|symfony/http-client|v6.3.2|间接依赖|composer|
|define-properties|1.2.0|间接依赖|npm|
|resize-observer-polyfill|1.5.1|间接依赖|npm|
|content-disposition|0.5.2|间接依赖|npm|
|async-validator|1.8.5|间接依赖|npm|
|psr/simple-cache|3.0.0|间接依赖|composer|
|quill-delta|3.6.3|间接依赖|npm|
|is-shared-array-buffer|1.0.2|间接依赖|npm|
|vue|2.7.14|间接依赖|npm|
|@sentry/core|7.53.1|间接依赖|npm|
|mobiledetect/mobiledetectlib|2.8.41|间接依赖|composer|
|anymatch|3.1.3|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|util.promisify|1.0.0|间接依赖|npm|
|@sentry-internal/tracing|7.53.1|间接依赖|npm|
|proxy-addr|2.0.7|间接依赖|npm|
|string_decoder|1.3.0|间接依赖|npm|
|composer-plugin-api||间接依赖|composer|
|@sentry/browser|7.53.1|间接依赖|npm|
|extend|3.0.2|间接依赖|npm|
|fruitcake/php-cors|v1.2.0|间接依赖|composer|
|symfony/polyfill-uuid|v1.28.0|间接依赖|composer|
|available-typed-arrays|1.0.5|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|stack-trace|0.0.10|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|nyholm/psr7|1.8.0|间接依赖|composer|
|composer-runtime-api||间接依赖|composer|
|@fullcalendar/interaction|6.1.8|间接依赖|npm|
|escape-html|1.0.3|间接依赖|npm|
|regexp.prototype.flags|1.5.0|间接依赖|npm|
|color-name|1.1.3|间接依赖|npm|
|node-rsa|0.4.2|间接依赖|npm|
|markbaker/complex|3.0.2|间接依赖|composer|
|wrappy|1.0.2|间接依赖|npm|
|punycode|2.3.0|间接依赖|npm|
|forwarded|0.2.0|间接依赖|npm|
|simple-icons/simple-icons|6.23.0|间接依赖|composer|
|mnsami/composer-custom-directory-installer|2.0.0|间接依赖|composer|
|php-http/discovery|1.19.1|间接依赖|composer|
|tailwindcss|3.3.2|间接依赖|npm|
|ms|2.0.0|间接依赖|npm|
|follow-redirects|1.15.2|间接依赖|npm|
|illuminate/console||间接依赖|composer|
|barryvdh/laravel-debugbar|v3.9.2|间接依赖|composer|
|unbox-primitive|1.0.2|间接依赖|npm|
|@nodelib/fs.walk|1.2.8|间接依赖|npm|
|element-ui|2.15.13|间接依赖|npm|
|ajv|6.10.0|间接依赖|npm|
|popper.js|1.16.1|间接依赖|npm|
|depd|1.1.2|间接依赖|npm|
|santigarcor/laratrust|7.2.0|间接依赖|composer|
|@jridgewell/trace-mapping|0.3.18|间接依赖|npm|
|jwa|1.4.1|间接依赖|npm|
|ezyang/htmlpurifier|v4.16.0|间接依赖|composer|
|laracasts/flash|3.2.2|间接依赖|composer|
|barryvdh/reflection-docblock|v2.1.1|间接依赖|composer|
|lusca|1.6.1|间接依赖|npm|
|is-callable|1.2.7|间接依赖|npm|
|symfony/routing|v6.3.3|间接依赖|composer|
|delayed-stream|1.0.0|间接依赖|npm|
|bitsyntax|0.0.4|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|postcss-nested|6.0.1|间接依赖|npm|
|hoa/file|1.17.07.11|间接依赖|composer|
|array.prototype.reduce|1.0.5|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|maximebf/debugbar|v1.18.2|间接依赖|composer|
|@algolia/autocomplete-shared|1.8.2|间接依赖|npm|
|bytes|3.0.0|间接依赖|npm|
|formats|1.0.0|间接依赖|npm|
|symfony/sendgrid-mailer|v6.3.0|间接依赖|composer|
|jean85/pretty-package-versions|2.0.5|间接依赖|composer|
|sentry/sentry|3.21.0|间接依赖|composer|
|compressible|2.0.18|间接依赖|npm|
|any-promise|1.3.0|间接依赖|npm|
|isarray|2.0.5|间接依赖|npm|
|composer/semver|3.3.2|间接依赖|composer|
|psr/log|3.0.0|间接依赖|composer|
|readable-stream|3.6.2|间接依赖|npm|
|ssr-window|4.0.2|间接依赖|npm|
|mtdowling/jmespath.php|2.7.0|间接依赖|composer|
|nprogress|0.2.0|间接依赖|npm|
|bugsnag/bugsnag-laravel|v2.26.0|间接依赖|composer|
|string.prototype.trimend|1.0.6|间接依赖|npm|
|globalthis|1.0.3|间接依赖|npm|
|league/mime-type-detection|1.13.0|间接依赖|composer|
|symfony/polyfill-ctype|v1.28.0|间接依赖|composer|
|vuedraggable|2.24.3|间接依赖|npm|
|symfony/service-contracts|v3.3.0|间接依赖|composer|
|glob-parent|5.1.2|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|symfony/polyfill-php83|v1.28.0|间接依赖|composer|
|illuminate/database||间接依赖|composer|
|sentry/sentry-laravel|3.7.3|间接依赖|composer|
|pirates|4.0.5|间接依赖|npm|
|symfony/finder|v6.3.3|间接依赖|composer|
|uuidv4|3.0.1|间接依赖|npm|
|babel-helper-vue-jsx-merge-props|2.0.3|间接依赖|npm|
|path-to-regexp|0.1.7|间接依赖|npm|
|es-array-method-boxes-properly|1.0.0|间接依赖|npm|
|mime|1.4.1|间接依赖|npm|
|hoa/visitor|2.17.01.16|间接依赖|composer|
|range-parser|1.2.1|间接依赖|npm|
|which-boxed-primitive|1.0.2|间接依赖|npm|
|jsonwebtoken|9.0.0|间接依赖|npm|
|akaunting/laravel-setting|1.2.8|间接依赖|composer|
|tijsverkoyen/css-to-inline-styles|2.2.6|间接依赖|composer|
|json-lines|1.0.0|间接依赖|npm|
|psr/event-dispatcher|1.0.0|间接依赖|composer|
|illuminate/notifications||间接依赖|composer|
|phpoption/phpoption|1.9.1|间接依赖|composer|
|graham-campbell/markdown|v15.0.0|间接依赖|composer|
|symfony/console|v6.3.4|间接依赖|composer|
|mini-svg-data-uri|1.4.4|间接依赖|npm|
|@jridgewell/set-array|1.1.2|间接依赖|npm|
|mime-types|2.1.35|间接依赖|npm|
|algoliasearch|4.17.1|间接依赖|npm|
|symfony/event-dispatcher-contracts|v3.3.0|间接依赖|composer|
|array-flatten|1.1.1|间接依赖|npm|
|php-http/message|1.16.0|间接依赖|composer|
|is-regexp|1.0.0|间接依赖|npm|
|clue/stream-filter|v1.6.0|间接依赖|composer|
|source-map|0.6.1|间接依赖|npm|
|guzzlehttp/promises|2.0.1|间接依赖|composer|
|commander|4.1.1|间接依赖|npm|
|core-js|2.6.12|间接依赖|npm|
|function.prototype.name|1.1.5|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|reusify|1.0.4|间接依赖|npm|
|swiper|9.3.2|间接依赖|npm|
|symfony/mime|v6.3.3|间接依赖|composer|
|@algolia/cache-common|4.17.1|间接依赖|npm|
|illuminate/support||间接依赖|composer|
|symfony/mailer|v6.3.0|间接依赖|composer|
|illuminate/config||间接依赖|composer|
|flaschenpost|1.1.3|间接依赖|npm|
|hoa/zformat|1.17.01.10|间接依赖|composer|
|symfony/polyfill-php72|v1.28.0|间接依赖|composer|
|read-cache|1.0.0|间接依赖|npm|
|jsonwebtoken|8.5.0|间接依赖|npm|
|php-http/guzzle7-adapter|1.0.0|间接依赖|composer|
|symfony/psr-http-message-bridge|v2.3.1|间接依赖|composer|
|cookie-signature|1.0.6|间接依赖|npm|
|limes|2.0.0|间接依赖|npm|
|ramsey/uuid|4.7.4|间接依赖|composer|
|postcss|8.4.24|间接依赖|npm|
|jiti|1.18.2|间接依赖|npm|
|raw-body|2.3.3|间接依赖|npm|
|barryvdh/laravel-ide-helper|v2.13.0|间接依赖|composer|
|@babel/helper-plugin-utils|7.21.5|间接依赖|npm|
|hoa/math|1.17.05.16|间接依赖|composer|
|fast-diff|1.1.2|间接依赖|npm|
|league/omnipay|v3.2.1|间接依赖|composer|
|@fullcalendar/vue|6.1.8|间接依赖|npm|
|symfony/polyfill-intl-idn|v1.28.0|间接依赖|composer|
|ipaddr.js|1.9.1|间接依赖|npm|
|mz|2.7.0|间接依赖|npm|
|akaunting/laravel-mutable-observer|2.0.1|间接依赖|composer|
|vue-flatpickr-component|8.1.8|间接依赖|npm|
|partof|1.0.0|间接依赖|npm|
|untildify|3.0.3|间接依赖|npm|
|hoa/compiler|3.17.08.08|间接依赖|composer|
|php-http/client-implementation||间接依赖|composer|
|psr/container|2.0.2|间接依赖|composer|
|deepmerge|1.5.2|间接依赖|npm|
|comparejs|1.0.0|间接依赖|npm|
|bugsnag/bugsnag-psr-logger|v2.0.0|间接依赖|composer|
|sortablejs|1.10.2|间接依赖|npm|
|riverskies/laravel-mobile-detect|1.3|间接依赖|composer|
|is-bigint|1.0.4|间接依赖|npm|
|is-obj|1.0.1|间接依赖|npm|
|staudenmeir/belongs-to-through|v2.13|间接依赖|composer|
|@algolia/requester-node-http|4.17.1|间接依赖|npm|
|which-typed-array|1.1.9|间接依赖|npm|
|express|4.16.4|间接依赖|npm|
|run-parallel|1.2.0|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)