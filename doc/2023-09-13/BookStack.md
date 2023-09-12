# BookStackApp/BookStack安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1701663966073847808.svg)](https://www.murphysec.com/console/report/1692966241889443840/1701663966073847808)

仓库描述：A platform to create documentation/wiki content built with PHP & Laravel

仓库地址：[https://github.com/BookStackApp/BookStack](https://github.com/BookStackApp/BookStack)

| star：12167 | watch：174 | fork：1579 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-12 19:37:14 | 许可证：MIT |
| 最近检测时间：2023-09-13 02:28:17 | 组件总数：157 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Laravel v9.1.8 反序列化漏洞|反序列化|[MPS-2022-10162](https://www.oscs1024.com/hd/MPS-2022-10162)|CVE-2022-30778|严重|
|dompdf/dompdf 存在代码注入漏洞|代码注入|[MPS-2022-14193](https://www.oscs1024.com/hd/MPS-2022-14193)||高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|laravel/framework|v9.52.15||间接依赖|强烈建议修复|C:1|H:0|M:0|L:0|
|dompdf/dompdf|v2.0.3||间接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|125|Low|
|GPL-2.0|2|Medium|
|GPL-3.0|2|Medium|
|BSD-3-Clause|10|Low|
|LGPL-2.0|3|Medium|
|LGPL-3.0|3|Medium|
|ISC|1|Low|
|Apache-2.0|3|Low|
|Python-2.0|1|Low|
|BSD-4-Clause|3|Low|
|BSD-2-Clause|1|Low|
|LGPL-2.1|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|symfony/polyfill-php72|v1.28.0|间接依赖|composer|
|@lezer/highlight|1.1.6|间接依赖|npm|
|laravel/socialite|v5.9.0|间接依赖|composer|
|symfony/string|v6.0.19|间接依赖|composer|
|aws/aws-crt-php|v1.2.2|间接依赖|composer|
|dflydev/dot-access-data|v3.0.2|间接依赖|composer|
|psr/container|2.0.2|间接依赖|composer|
|@codemirror/view|6.16.0|间接依赖|npm|
|@lezer/javascript|1.4.2|间接依赖|npm|
|symfony/polyfill-php80|v1.28.0|间接依赖|composer|
|@lezer/php|1.0.1|间接依赖|npm|
|laravel/framework|v9.52.15|间接依赖|composer|
|socialiteproviders/okta|4.3.0|间接依赖|composer|
|@codemirror/lang-markdown|6.2.0|间接依赖|npm|
|nette/utils|v4.0.1|间接依赖|composer|
|psr/simple-cache|3.0.0|间接依赖|composer|
|symfony/polyfill-php81|v1.28.0|间接依赖|composer|
|symfony/deprecation-contracts|v3.0.2|间接依赖|composer|
|@lezer/html|1.3.4|间接依赖|npm|
|symfony/http-kernel|v6.0.20|间接依赖|composer|
|nette/schema|v1.2.4|间接依赖|composer|
|league/commonmark|2.4.1|间接依赖|composer|
|@lezer/lr|1.3.3|间接依赖|npm|
|symfony/event-dispatcher-contracts|v3.0.2|间接依赖|composer|
|doctrine/lexer|2.1.0|间接依赖|composer|
|mdurl|1.0.1|间接依赖|npm|
|socialiteproviders/discord|4.2.0|间接依赖|composer|
|@codemirror/lang-php|6.0.1|间接依赖|npm|
|nunomaduro/termwind|v1.15.1|间接依赖|composer|
|psr/http-message|2.0|间接依赖|composer|
|league/oauth2-client|2.7.0|间接依赖|composer|
|sabberworm/php-css-parser|8.4.0|间接依赖|composer|
|@codemirror/autocomplete|6.9.0|间接依赖|npm|
|voku/portable-ascii|2.0.1|间接依赖|composer|
|w3c-keyname|2.2.6|间接依赖|npm|
|laravel/tinker|v2.8.2|间接依赖|composer|
|@lezer/common|1.0.2|间接依赖|npm|
|@codemirror/lang-css|6.2.1|间接依赖|npm|
|psr/cache|3.0.0|间接依赖|composer|
|@codemirror/legacy-modes|6.3.3|间接依赖|npm|
|league/flysystem|3.16.0|间接依赖|composer|
|illuminate/http||间接依赖|composer|
|phenx/php-font-lib|0.5.4|间接依赖|composer|
|@lezer/json|1.0.0|间接依赖|npm|
|psr/http-client|1.0.2|间接依赖|composer|
|barryvdh/laravel-snappy|v1.0.2|间接依赖|composer|
|markdown-it-task-lists|2.1.1|间接依赖|npm|
|egulias/email-validator|3.2.6|间接依赖|composer|
|ramsey/collection|1.3.0|间接依赖|composer|
|symfony/service-contracts|v3.0.2|间接依赖|composer|
|@codemirror/commands|6.2.4|间接依赖|npm|
|brick/math|0.11.0|间接依赖|composer|
|dragonmantank/cron-expression|v3.3.3|间接依赖|composer|
|@codemirror/state|6.2.1|间接依赖|npm|
|ssddanbrown/htmldiff|v1.0.2|间接依赖|composer|
|symfony/http-foundation|v6.0.20|间接依赖|composer|
|@codemirror/language|6.9.0|间接依赖|npm|
|symfony/polyfill-intl-normalizer|v1.28.0|间接依赖|composer|
|idb-keyval|6.2.1|间接依赖|npm|
|@lezer/xml|1.0.1|间接依赖|npm|
|@codemirror/lang-javascript|6.1.9|间接依赖|npm|
|pragmarx/google2fa|v8.0.1|间接依赖|composer|
|symfony/finder|v6.0.19|间接依赖|composer|
|symfony/console|v6.0.19|间接依赖|composer|
|argparse|2.0.1|间接依赖|npm|
|symfony/translation-contracts|v3.0.2|间接依赖|composer|
|league/config|v1.2.0|间接依赖|composer|
|laravel/serializable-closure|v1.3.1|间接依赖|composer|
|symfony/routing|v6.0.19|间接依赖|composer|
|aws/aws-sdk-php|3.281.3|间接依赖|composer|
|markdown-it|13.0.1|间接依赖|npm|
|fruitcake/php-cors|v1.2.0|间接依赖|composer|
|doctrine/deprecations|v1.1.1|间接依赖|composer|
|socialiteproviders/gitlab|4.1.0|间接依赖|composer|
|knplabs/knp-snappy|v1.4.3|间接依赖|composer|
|guzzlehttp/promises|2.0.1|间接依赖|composer|
|symfony/polyfill-intl-idn|v1.28.0|间接依赖|composer|
|symfony/event-dispatcher|v6.0.19|间接依赖|composer|
|nikic/php-parser|v4.17.1|间接依赖|composer|
|symfony/polyfill-ctype|v1.28.0|间接依赖|composer|
|@codemirror/lang-html|6.4.5|间接依赖|npm|
|@codemirror/theme-one-dark|6.1.2|间接依赖|npm|
|@ssddanbrown/codemirror-lang-smarty|1.0.0|间接依赖|npm|
|symfony/process|v6.0.19|间接依赖|composer|
|symfony/error-handler|v6.0.19|间接依赖|composer|
|doctrine/dbal|3.6.6|间接依赖|composer|
|@codemirror/search|6.3.0|间接依赖|npm|
|phpseclib/phpseclib|3.0.21|间接依赖|composer|
|socialiteproviders/manager|v4.4.0|间接依赖|composer|
|league/flysystem-local|3.16.0|间接依赖|composer|
|illuminate/contracts||间接依赖|composer|
|guzzlehttp/guzzle|7.8.0|间接依赖|composer|
|symfony/polyfill-intl-grapheme|v1.28.0|间接依赖|composer|
|guzzlehttp/psr7|2.6.1|间接依赖|composer|
|robrichards/xmlseclibs|3.1.1|间接依赖|composer|
|symfony/polyfill-mbstring|v1.28.0|间接依赖|composer|
|onelogin/php-saml|4.1.0|间接依赖|composer|
|barryvdh/laravel-dompdf|v2.0.1|间接依赖|composer|
|webmozart/assert|1.11.0|间接依赖|composer|
|socialiteproviders/microsoft-azure|5.1.0|间接依赖|composer|
|symfony/mailer||间接依赖|composer|
|@codemirror/lang-json|6.0.1|间接依赖|npm|
|graham-campbell/result-type|v1.1.1|间接依赖|composer|
|linkify-it|4.0.1|间接依赖|npm|
|phpoption/phpoption|1.9.1|间接依赖|composer|
|sortablejs|1.15.0|间接依赖|npm|
|symfony/css-selector|v6.0.19|间接依赖|composer|
|codemirror|6.0.1|间接依赖|npm|
|entities|3.0.1|间接依赖|npm|
|symfony/var-dumper|v6.0.19|间接依赖|composer|
|vlucas/phpdotenv|v5.5.0|间接依赖|composer|
|symfony/uid|v6.0.19|间接依赖|composer|
|dompdf/dompdf|v2.0.3|间接依赖|composer|
|illuminate/filesystem||间接依赖|composer|
|paragonie/constant_time_encoding|v2.6.3|间接依赖|composer|
|ralouphie/getallheaders|3.0.3|间接依赖|composer|
|psr/http-factory|1.0.2|间接依赖|composer|
|predis/predis|v2.2.1|间接依赖|composer|
|masterminds/html5|2.8.1|间接依赖|composer|
|psr/event-dispatcher|1.0.0|间接依赖|composer|
|league/flysystem-aws-s3-v3|3.16.0|间接依赖|composer|
|league/html-to-markdown|5.1.1|间接依赖|composer|
|symfony/translation|v6.0.19|间接依赖|composer|
|intervention/image|2.7.2|间接依赖|composer|
|composer-runtime-api||间接依赖|composer|
|mtdowling/jmespath.php|2.7.0|间接依赖|composer|
|doctrine/cache|2.2.0|间接依赖|composer|
|@lezer/css|1.1.1|间接依赖|npm|
|doctrine/inflector|2.0.8|间接依赖|composer|
|tijsverkoyen/css-to-inline-styles|2.2.6|间接依赖|composer|
|@codemirror/lint|6.2.1|间接依赖|npm|
|style-mod|4.0.3|间接依赖|npm|
|snabbdom|3.5.1|间接依赖|npm|
|doctrine/event-manager|1.2.0|间接依赖|composer|
|paragonie/random_compat|v9.99.100|间接依赖|composer|
|nesbot/carbon|2.70.0|间接依赖|composer|
|uc.micro|1.0.6|间接依赖|npm|
|ramsey/uuid|4.7.4|间接依赖|composer|
|monolog/monolog|2.9.1|间接依赖|composer|
|psr/log|3.0.0|间接依赖|composer|
|psy/psysh|v0.11.20|间接依赖|composer|
|crelt|1.0.5|间接依赖|npm|
|@codemirror/lang-xml|6.0.2|间接依赖|npm|
|@lezer/markdown|1.0.2|间接依赖|npm|
|illuminate/console||间接依赖|composer|
|symfony/polyfill-uuid|v1.28.0|间接依赖|composer|
|league/mime-type-detection|1.13.0|间接依赖|composer|
|@ssddanbrown/codemirror-lang-twig|1.0.0|间接依赖|npm|
|illuminate/support||间接依赖|composer|
|guzzlehttp/uri-template|v1.0.2|间接依赖|composer|
|socialiteproviders/twitch|5.3.1|间接依赖|composer|
|psr/clock|1.0.0|间接依赖|composer|
|league/oauth1-client|v1.10.1|间接依赖|composer|
|symfony/mime|v6.0.19|间接依赖|composer|
|bacon/bacon-qr-code|2.0.8|间接依赖|composer|
|phenx/php-svg-lib|0.5.0|间接依赖|composer|
|dasprid/enum|1.0.5|间接依赖|composer|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)