# alexjustesen/speedtest-tracker安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698402836873527296.svg)](https://www.murphysec.com/console/report/1698402836781252608/1698402836873527296)

仓库描述：Speedtest Tracker is a self-hosted internet performance tracking application that runs speedtest checks against Ookla's Speedtest service.

仓库地址：[https://github.com/alexjustesen/speedtest-tracker](https://github.com/alexjustesen/speedtest-tracker)

| star：1212 | watch：18 | fork：44 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-31 20:26:49 | 许可证：MIT |
| 最近检测时间：2023-09-04 02:29:30 | 组件总数：132 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Laravel v9.1.8 反序列化漏洞|反序列化|[MPS-2022-10162](https://www.oscs1024.com/hd/MPS-2022-10162)|CVE-2022-30778|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|laravel/framework|v10.21.0||间接依赖|强烈建议修复|C:1|H:0|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|96|Low|
|LGPL-2.0|3|Medium|
|BSD-3-Clause|5|Low|
|BSD-4-Clause|3|Low|
|Apache-2.0|1|Low|
|GPL-2.0|1|Medium|
|GPL-3.0|1|Medium|
|LGPL-2.1|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|danharrin/date-format-converter|v0.3.0|间接依赖|composer|
|filament/filament|v2.17.52|间接依赖|composer|
|chrisullyott/php-filesize|v4.2.1|间接依赖|composer|
|voku/portable-ascii|2.0.1|间接依赖|composer|
|symfony/translation-contracts|v3.3.0|间接依赖|composer|
|symfony/polyfill-php83|v1.28.0|间接依赖|composer|
|graham-campbell/result-type|v1.1.1|间接依赖|composer|
|illuminate/routing||间接依赖|composer|
|laravel/tinker|v2.8.2|间接依赖|composer|
|blade-ui-kit/blade-heroicons|1.4.0|间接依赖|composer|
|guzzlehttp/promises|2.0.1|间接依赖|composer|
|nunomaduro/termwind|v1.15.1|间接依赖|composer|
|league/flysystem|3.15.1|间接依赖|composer|
|illuminate/http||间接依赖|composer|
|spatie/temporary-directory|2.1.2|间接依赖|composer|
|monolog/monolog|3.4.0|间接依赖|composer|
|blade-ui-kit/blade-icons|1.5.2|间接依赖|composer|
|myclabs/php-enum|1.8.4|间接依赖|composer|
|illuminate/database||间接依赖|composer|
|symfony/deprecation-contracts|v3.3.0|间接依赖|composer|
|league/config|v1.2.0|间接依赖|composer|
|dflydev/dot-access-data|v3.0.2|间接依赖|composer|
|league/uri-parser|1.4.1|间接依赖|composer|
|psr/http-factory|1.0.2|间接依赖|composer|
|squirephp/model|v3.4.2|间接依赖|composer|
|symfony/polyfill-intl-idn|v1.28.0|间接依赖|composer|
|laravel/sanctum|v3.2.6|间接依赖|composer|
|squirephp/rule|v3.4.2|间接依赖|composer|
|laravel/prompts|v0.1.6|间接依赖|composer|
|symfony/uid|v6.3.0|间接依赖|composer|
|symfony/http-kernel|v6.3.4|间接依赖|composer|
|symfony/polyfill-mbstring|v1.28.0|间接依赖|composer|
|phpdocumentor/type-resolver|1.7.3|间接依赖|composer|
|ezyang/htmlpurifier|v4.16.0|间接依赖|composer|
|symfony/polyfill-php72|v1.28.0|间接依赖|composer|
|squirephp/timezones-en|v3.4.2|间接依赖|composer|
|symfony/console|v6.3.4|间接依赖|composer|
|psr/log|3.0.0|间接依赖|composer|
|doctrine/cache|2.2.0|间接依赖|composer|
|symfony/mailer|v6.3.0|间接依赖|composer|
|guzzlehttp/uri-template|v1.0.2|间接依赖|composer|
|phpdocumentor/reflection-common|2.2.0|间接依赖|composer|
|filament/support|v2.17.52|间接依赖|composer|
|illuminate/cookie||间接依赖|composer|
|symfony/polyfill-intl-grapheme|v1.28.0|间接依赖|composer|
|influxdata/influxdb-client-php|2.9.0|间接依赖|composer|
|illuminate/collections||间接依赖|composer|
|egulias/email-validator|4.0.1|间接依赖|composer|
|illuminate/notifications||间接依赖|composer|
|laravel/framework|v10.21.0|间接依赖|composer|
|illuminate/support||间接依赖|composer|
|psr/http-client|1.0.2|间接依赖|composer|
|symfony/finder|v6.3.3|间接依赖|composer|
|psr/cache|3.0.0|间接依赖|composer|
|fruitcake/php-cors|v1.2.0|间接依赖|composer|
|guzzlehttp/guzzle|7.8.0|间接依赖|composer|
|livewire/livewire|v2.12.6|间接依赖|composer|
|doctrine/event-manager|2.0.0|间接依赖|composer|
|doctrine/lexer|3.0.0|间接依赖|composer|
|psr/http-message|1.1|间接依赖|composer|
|vlucas/phpdotenv|v5.5.0|间接依赖|composer|
|phpstan/phpdoc-parser|1.23.1|间接依赖|composer|
|symfony/http-foundation|v6.3.4|间接依赖|composer|
|doctrine/dbal|3.6.6|间接依赖|composer|
|nikic/php-parser|v4.17.1|间接依赖|composer|
|symfony/translation|v6.3.3|间接依赖|composer|
|spatie/invade|1.1.1|间接依赖|composer|
|psr/container|2.0.2|间接依赖|composer|
|illuminate/filesystem||间接依赖|composer|
|league/mime-type-detection|1.13.0|间接依赖|composer|
|filament/forms|v2.17.52|间接依赖|composer|
|symfony/service-contracts|v3.3.0|间接依赖|composer|
|illuminate/console||间接依赖|composer|
|illuminate/contracts||间接依赖|composer|
|psr/clock|1.0.0|间接依赖|composer|
|filament/spatie-laravel-settings-plugin|v2.17.52|间接依赖|composer|
|akaunting/laravel-money|4.0.1|间接依赖|composer|
|laravel/serializable-closure|v1.3.1|间接依赖|composer|
|composer/semver|3.3.2|间接依赖|composer|
|phpoption/phpoption|1.9.1|间接依赖|composer|
|symfony/mime|v6.3.3|间接依赖|composer|
|league/commonmark|2.4.0|间接依赖|composer|
|ryangjchandler/blade-capture-directive|v0.3.0|间接依赖|composer|
|illuminate/validation||间接依赖|composer|
|symfony/polyfill-intl-normalizer|v1.28.0|间接依赖|composer|
|symfony/routing|v6.3.3|间接依赖|composer|
|symfony/string|v6.3.2|间接依赖|composer|
|awcodes/filament-versions|v1.1.1|间接依赖|composer|
|markbaker/complex|3.0.2|间接依赖|composer|
|doctrine/deprecations|v1.1.1|间接依赖|composer|
|markbaker/matrix|3.0.1|间接依赖|composer|
|maennchen/zipstream-php|2.4.0|间接依赖|composer|
|ralouphie/getallheaders|3.0.3|间接依赖|composer|
|squirephp/repository|v3.4.2|间接依赖|composer|
|psr/event-dispatcher|1.0.0|间接依赖|composer|
|illuminate/view||间接依赖|composer|
|filament/tables|v2.17.52|间接依赖|composer|
|league/flysystem-local|3.15.0|间接依赖|composer|
|danharrin/livewire-rate-limiting|v1.1.0|间接依赖|composer|
|nette/schema|v1.2.4|间接依赖|composer|
|laravel-notification-channels/telegram|4.0.0|间接依赖|composer|
|symfony/polyfill-php80|v1.28.0|间接依赖|composer|
|webmozart/assert|1.11.0|间接依赖|composer|
|squirephp/timezones|v3.4.2|间接依赖|composer|
|illuminate/auth||间接依赖|composer|
|symfony/var-dumper|v6.3.4|间接依赖|composer|
|symfony/css-selector|v6.3.2|间接依赖|composer|
|phpoffice/phpspreadsheet|1.29.0|间接依赖|composer|
|nesbot/carbon|2.69.0|间接依赖|composer|
|brick/math|0.11.0|间接依赖|composer|
|dragonmantank/cron-expression|v3.3.3|间接依赖|composer|
|tijsverkoyen/css-to-inline-styles|2.2.6|间接依赖|composer|
|psy/psysh|v0.11.20|间接依赖|composer|
|symfony/event-dispatcher|v6.3.2|间接依赖|composer|
|masterminds/html5|2.8.1|间接依赖|composer|
|ramsey/uuid|4.7.4|间接依赖|composer|
|composer-runtime-api||间接依赖|composer|
|symfony/polyfill-uuid|v1.28.0|间接依赖|composer|
|symfony/process|v6.3.4|间接依赖|composer|
|symfony/error-handler|v6.3.2|间接依赖|composer|
|maatwebsite/excel|3.1.48|间接依赖|composer|
|psr/simple-cache|3.0.0|间接依赖|composer|
|illuminate/session||间接依赖|composer|
|doctrine/inflector|2.0.8|间接依赖|composer|
|spatie/laravel-package-tools|1.16.1|间接依赖|composer|
|symfony/event-dispatcher-contracts|v3.3.0|间接依赖|composer|
|guzzlehttp/psr7|2.6.1|间接依赖|composer|
|filament/notifications|v2.17.52|间接依赖|composer|
|tgalopin/html-sanitizer|1.5.0|间接依赖|composer|
|ramsey/collection|2.0.0|间接依赖|composer|
|spatie/laravel-settings|2.8.3|间接依赖|composer|
|symfony/polyfill-ctype|v1.28.0|间接依赖|composer|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)