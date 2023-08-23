# bagisto/bagisto安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694415980620242944.svg)](https://www.murphysec.com/console/report/1694415979286454272/1694415980620242944)

仓库描述：Free and open source laravel eCommerce platform

仓库地址：[https://github.com/bagisto/bagisto](https://github.com/bagisto/bagisto)

| star：7342 | watch：143 | fork：1818 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-23 22:49:34 | 许可证：MIT |
| 最近检测时间：2023-08-24 02:27:42 | 组件总数：144 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Laravel v9.1.8 反序列化漏洞|反序列化|[MPS-2022-10162](https://www.oscs1024.com/hd/MPS-2022-10162)|CVE-2022-30778|严重|
|dompdf/dompdf 存在代码注入漏洞|代码注入|[MPS-2022-14193](https://www.oscs1024.com/hd/MPS-2022-14193)||高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|laravel/framework|v10.8.0||间接依赖|强烈建议修复|C:1|H:0|M:0|L:0|
|dompdf/dompdf|v2.0.3||间接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|115|Low|
|LGPL-3.0|4|Medium|
|BSD-3-Clause|5|Low|
|BSD-4-Clause|3|Low|
|Apache-2.0|4|Low|
|LGPL-2.0|5|Medium|
|ISC|1|Low|
|LGPL-2.1|2|Medium|
|GPL-2.0|1|Medium|
|GPL-3.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|ramsey/uuid|4.7.4|间接依赖|composer|
|ramsey/collection|2.0.0|间接依赖|composer|
|guzzlehttp/uri-template|v1.0.1|间接依赖|composer|
|phenx/php-svg-lib|0.5.0|间接依赖|composer|
|illuminate/http||间接依赖|composer|
|symfony/process|v6.2.8|间接依赖|composer|
|brick/math|0.11.0|间接依赖|composer|
|enshrined/svg-sanitize|0.16.0|间接依赖|composer|
|barryvdh/laravel-dompdf|v2.0.1|间接依赖|composer|
|paypal/paypalhttp|1.0.0|间接依赖|composer|
|cviebrock/laravel-elasticsearch|10.0.0|间接依赖|composer|
|maennchen/zipstream-php|v2.4.0|间接依赖|composer|
|nikic/php-parser|v4.15.4|间接依赖|composer|
|react/promise|v2.9.0|间接依赖|composer|
|symfony/polyfill-intl-idn|v1.27.0|间接依赖|composer|
|bagistobrasil/bagisto-product-social-share|0.1.4|间接依赖|composer|
|psr/log|3.0.0|间接依赖|composer|
|laravel/serializable-closure|v1.3.0|间接依赖|composer|
|symfony/console|v6.2.8|间接依赖|composer|
|symfony/mime|v6.2.7|间接依赖|composer|
|astrotomic/laravel-translatable|v11.12.1|间接依赖|composer|
|illuminate/events||间接依赖|composer|
|paragonie/random_compat|v9.99.100|间接依赖|composer|
|psr/simple-cache|3.0.0|间接依赖|composer|
|symfony/polyfill-uuid|v1.27.0|间接依赖|composer|
|nunomaduro/termwind|v1.15.1|间接依赖|composer|
|illuminate/validation||间接依赖|composer|
|laravel/framework|v10.8.0|间接依赖|composer|
|symfony/event-dispatcher-contracts|v3.2.1|间接依赖|composer|
|doctrine/deprecations|v1.0.0|间接依赖|composer|
|symfony/event-dispatcher|v6.2.8|间接依赖|composer|
|psr/container|2.0.2|间接依赖|composer|
|symfony/http-foundation|v6.2.8|间接依赖|composer|
|masterminds/html5|2.7.6|间接依赖|composer|
|diglactic/laravel-breadcrumbs|v8.1.1|间接依赖|composer|
|egulias/email-validator|4.0.1|间接依赖|composer|
|facade/ignition-contracts|1.0.2|间接依赖|composer|
|konekt/enum|4.0.2|间接依赖|composer|
|laravel/socialite|v5.6.1|间接依赖|composer|
|intervention/image|2.7.2|间接依赖|composer|
|league/flysystem|3.14.0|间接依赖|composer|
|kalnoy/nestedset|v6.0.2|间接依赖|composer|
|illuminate/config||间接依赖|composer|
|laravel/ui|v4.2.1|间接依赖|composer|
|symfony/translation-contracts|v3.2.1|间接依赖|composer|
|elasticsearch/elasticsearch|v7.17.2|间接依赖|composer|
|doctrine/lexer|3.0.0|间接依赖|composer|
|phenx/php-font-lib|0.5.4|间接依赖|composer|
|spatie/robots-txt|2.0.2|间接依赖|composer|
|league/mime-type-detection|1.11.0|间接依赖|composer|
|guzzlehttp/psr7|2.5.0|间接依赖|composer|
|fakerphp/faker|v1.21.0|间接依赖|composer|
|doctrine/cache|2.2.0|间接依赖|composer|
|guzzlehttp/promises|1.5.2|间接依赖|composer|
|psr/cache|3.0.0|间接依赖|composer|
|symfony/deprecation-contracts|v3.2.1|间接依赖|composer|
|illuminate/filesystem||间接依赖|composer|
|dflydev/dot-access-data|v3.0.2|间接依赖|composer|
|spatie/backtrace|1.4.0|间接依赖|composer|
|psr/http-factory|1.0.2|间接依赖|composer|
|symfony/http-kernel|v6.2.9|间接依赖|composer|
|spatie/laravel-sitemap|6.2.5|间接依赖|composer|
|symfony/polyfill-ctype|v1.27.0|间接依赖|composer|
|symfony/polyfill-php72|v1.27.0|间接依赖|composer|
|dragonmantank/cron-expression|v3.3.2|间接依赖|composer|
|illuminate/database||间接依赖|composer|
|psr/http-client|1.0.2|间接依赖|composer|
|symfony/finder|v6.2.7|间接依赖|composer|
|bagisto/laravel-datafaker|v2.0.0-ALPHA1|间接依赖|composer|
|illuminate/pagination||间接依赖|composer|
|paragonie/sodium_compat|v1.19.0|间接依赖|composer|
|league/commonmark|2.4.0|间接依赖|composer|
|laravel/sanctum|v3.2.1|间接依赖|composer|
|myclabs/php-enum|1.8.4|间接依赖|composer|
|doctrine/inflector|2.0.6|间接依赖|composer|
|spatie/laravel-ignition|2.1.0|间接依赖|composer|
|spatie/laravel-package-tools|1.14.2|间接依赖|composer|
|khaled.alshamaa/ar-php|v6.3.4|间接依赖|composer|
|konekt/concord|1.13.0|间接依赖|composer|
|spatie/crawler|7.1.3|间接依赖|composer|
|voku/portable-ascii|2.0.1|间接依赖|composer|
|composer/semver|3.3.2|间接依赖|composer|
|ezyang/htmlpurifier|v4.16.0|间接依赖|composer|
|illuminate/pipeline||间接依赖|composer|
|spatie/flare-client-php|1.3.6|间接依赖|composer|
|league/config|v1.2.0|间接依赖|composer|
|symfony/translation|v6.2.8|间接依赖|composer|
|tijsverkoyen/css-to-inline-styles|2.2.6|间接依赖|composer|
|spatie/ignition|1.5.0|间接依赖|composer|
|symfony/polyfill-mbstring|v1.27.0|间接依赖|composer|
|opis/closure|3.6.3|间接依赖|composer|
|fruitcake/php-cors|v1.2.0|间接依赖|composer|
|laravel/tinker|v2.8.1|间接依赖|composer|
|nicmart/tree|0.3.1|间接依赖|composer|
|pusher/pusher-php-server|7.2.2|间接依赖|composer|
|ezimuel/guzzlestreams|3.1.0|间接依赖|composer|
|illuminate/console||间接依赖|composer|
|spatie/temporary-directory|2.1.1|间接依赖|composer|
|konekt/enum-eloquent|1.9.0|间接依赖|composer|
|maatwebsite/excel|3.1.48|间接依赖|composer|
|paypal/paypal-checkout-sdk|1.0.1|间接依赖|composer|
|illuminate/contracts||间接依赖|composer|
|symfony/var-dumper|v6.2.8|间接依赖|composer|
|dompdf/dompdf|v2.0.3|间接依赖|composer|
|nette/schema|v1.2.3|间接依赖|composer|
|spatie/browsershot|3.57.6|间接依赖|composer|
|psy/psysh|v0.11.15|间接依赖|composer|
|doctrine/event-manager|2.0.0|间接依赖|composer|
|prettus/l5-repository|2.9.0|间接依赖|composer|
|symfony/service-contracts|v3.2.1|间接依赖|composer|
|vlucas/phpdotenv|v5.5.0|间接依赖|composer|
|composer-runtime-api||间接依赖|composer|
|illuminate/support||间接依赖|composer|
|symfony/polyfill-intl-normalizer|v1.27.0|间接依赖|composer|
|phpoption/phpoption|1.9.1|间接依赖|composer|
|symfony/error-handler|v6.2.9|间接依赖|composer|
|symfony/mailer|v6.2.8|间接依赖|composer|
|symfony/polyfill-php80|v1.27.0|间接依赖|composer|
|symfony/css-selector|v6.2.7|间接依赖|composer|
|symfony/dom-crawler|v6.2.9|间接依赖|composer|
|symfony/polyfill-intl-grapheme|v1.27.0|间接依赖|composer|
|ezimuel/ringphp|1.2.2|间接依赖|composer|
|guzzlehttp/guzzle|7.5.1|间接依赖|composer|
|spatie/image|2.2.5|间接依赖|composer|
|symfony/routing|v6.2.8|间接依赖|composer|
|nesbot/carbon|2.66.0|间接依赖|composer|
|psr/event-dispatcher|1.0.0|间接依赖|composer|
|markbaker/matrix|3.0.1|间接依赖|composer|
|sabberworm/php-css-parser|8.4.0|间接依赖|composer|
|prettus/laravel-validation|1.5.0|间接依赖|composer|
|intervention/imagecache|2.6.0|间接依赖|composer|
|symfony/string|v6.2.8|间接依赖|composer|
|monolog/monolog|3.3.1|间接依赖|composer|
|doctrine/dbal|3.6.2|间接依赖|composer|
|ralouphie/getallheaders|3.0.3|间接依赖|composer|
|symfony/uid|v6.2.7|间接依赖|composer|
|psr/http-message|1.1|间接依赖|composer|
|webmozart/assert|1.11.0|间接依赖|composer|
|phpoffice/phpspreadsheet|1.28.0|间接依赖|composer|
|markbaker/complex|3.0.2|间接依赖|composer|
|illuminate/collections||间接依赖|composer|
|league/oauth1-client|v1.10.1|间接依赖|composer|
|illuminate/cache||间接依赖|composer|
|graham-campbell/result-type|v1.1.1|间接依赖|composer|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)