# krayin/laravel-crm安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699852280605229056.svg)](https://www.murphysec.com/console/report/1699852279741202432/1699852280605229056)

仓库描述：Free & Opensource Laravel CRM solution for SMEs and Enterprises for complete customer lifecycle management.

仓库地址：[https://github.com/krayin/laravel-crm](https://github.com/krayin/laravel-crm)

| star：2551 | watch：32 | fork：390 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-08 15:36:12 | 许可证：MIT |
| 最近检测时间：2023-09-08 02:29:10 | 组件总数：105 | 漏洞总数：8 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Laravel v9.1.8 反序列化漏洞|反序列化|[MPS-2022-10162](https://www.oscs1024.com/hd/MPS-2022-10162)|CVE-2022-30778|严重|
|dompdf/dompdf 存在代码注入漏洞|代码注入|[MPS-2022-14193](https://www.oscs1024.com/hd/MPS-2022-14193)||高危|
|Sensio Labs Symfony 授权问题漏洞|授权机制不恰当|[MPS-2022-3861](https://www.oscs1024.com/hd/MPS-2022-3861)|CVE-2022-24894|高危|
|Dompdf 安全漏洞|对外部实体的文件或目录可访问|[MPS-2022-57837](https://www.oscs1024.com/hd/MPS-2022-57837)|CVE-2022-41343|高危|
|Dompdf 安全漏洞|授权检查错误|[MPS-2023-2187](https://www.oscs1024.com/hd/MPS-2023-2187)|CVE-2023-23924|严重|
|Dompdf <2.0.3 存在远程代码执行漏洞|解释冲突|[MPS-2023-3319](https://www.oscs1024.com/hd/MPS-2023-3319)|CVE-2023-24813|严重|
|PSR-7 Message Implementation 安全漏洞|解释冲突|[MPS-2023-9403](https://www.oscs1024.com/hd/MPS-2023-9403)|CVE-2023-29197|高危|
|Laminas Project diactoros 拒绝服务漏洞|拒绝服务|[MPS-2023-9897](https://www.oscs1024.com/hd/MPS-2023-9897)|CVE-2023-29530|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|laravel/framework|v9.29.0||间接依赖|强烈建议修复|C:1|H:0|M:0|L:0|
|guzzlehttp/psr7|2.4.1|2.4.5|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|dompdf/dompdf|v2.0.0|2.0.3|间接依赖|建议修复|C:2|H:2|M:0|L:0|
|symfony/http-kernel|v6.1.4|6.2.6|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|86|Low|
|LGPL-3.0|3|Medium|
|GPL-2.0|1|Medium|
|GPL-3.0|1|Medium|
|BSD-3-Clause|5|Low|
|Apache-2.0|2|Low|
|LGPL-2.1|2|Medium|
|BSD-4-Clause|3|Low|
|LGPL-2.0|5|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|sabberworm/php-css-parser|8.4.0|间接依赖|composer|
|brick/math|0.10.2|间接依赖|composer|
|symfony/error-handler|v6.1.3|间接依赖|composer|
|symfony/finder|v6.1.3|间接依赖|composer|
|psy/psysh|v0.11.8|间接依赖|composer|
|symfony/event-dispatcher|v6.1.0|间接依赖|composer|
|doctrine/event-manager|1.1.2|间接依赖|composer|
|phenx/php-svg-lib|0.4.1|间接依赖|composer|
|doctrine/lexer|1.2.3|间接依赖|composer|
|symfony/css-selector|v6.1.3|间接依赖|composer|
|nesbot/carbon|2.62.1|间接依赖|composer|
|symfony/mime|v6.1.4|间接依赖|composer|
|psr/http-message|1.0.1|间接依赖|composer|
|nette/schema|v1.2.2|间接依赖|composer|
|illuminate/pagination||间接依赖|composer|
|symfony/http-kernel|v6.1.4|间接依赖|composer|
|illuminate/support||间接依赖|composer|
|webmozart/assert|1.11.0|间接依赖|composer|
|ralouphie/getallheaders|3.0.3|间接依赖|composer|
|myclabs/php-enum|1.8.4|间接依赖|composer|
|psr/http-client|1.0.1|间接依赖|composer|
|phpoption/phpoption|1.9.0|间接依赖|composer|
|phpoffice/phpspreadsheet|1.24.1|间接依赖|composer|
|prettus/l5-repository|2.8.0|间接依赖|composer|
|psr/event-dispatcher|1.0.0|间接依赖|composer|
|dragonmantank/cron-expression|v3.3.2|间接依赖|composer|
|symfony/polyfill-intl-idn|v1.26.0|间接依赖|composer|
|nikic/php-parser|v4.15.1|间接依赖|composer|
|symfony/string|v6.1.4|间接依赖|composer|
|fruitcake/laravel-cors|v2.2.0|间接依赖|composer|
|illuminate/filesystem||间接依赖|composer|
|psr/container|2.0.2|间接依赖|composer|
|symfony/http-foundation|v6.1.4|间接依赖|composer|
|guzzlehttp/promises|1.5.2|间接依赖|composer|
|konekt/concord|1.11.0|间接依赖|composer|
|symfony/console|v6.1.4|间接依赖|composer|
|graham-campbell/result-type|v1.1.0|间接依赖|composer|
|egulias/email-validator|3.2.1|间接依赖|composer|
|illuminate/console||间接依赖|composer|
|voku/portable-ascii|2.0.1|间接依赖|composer|
|asm89/stack-cors|v2.1.1|间接依赖|composer|
|barryvdh/laravel-dompdf|v2.0.0|间接依赖|composer|
|symfony/polyfill-php80|v1.26.0|间接依赖|composer|
|doctrine/dbal|3.4.4|间接依赖|composer|
|dompdf/dompdf|v2.0.0|间接依赖|composer|
|krayin/rest-api|dev-master|间接依赖|composer|
|prettus/laravel-validation|1.4.0|间接依赖|composer|
|symfony/deprecation-contracts|v3.1.1|间接依赖|composer|
|laravel/tinker|v2.7.2|间接依赖|composer|
|illuminate/config||间接依赖|composer|
|laravel/sanctum|v2.15.1|间接依赖|composer|
|doctrine/cache|2.2.0|间接依赖|composer|
|league/flysystem|3.3.0|间接依赖|composer|
|psr/log|3.0.0|间接依赖|composer|
|composer-runtime-api||间接依赖|composer|
|illuminate/database||间接依赖|composer|
|psr/cache|3.0.0|间接依赖|composer|
|league/config|v1.1.1|间接依赖|composer|
|markbaker/complex|3.0.1|间接依赖|composer|
|doctrine/inflector|2.0.5|间接依赖|composer|
|laravel/ui|v3.4.6|间接依赖|composer|
|laravel/serializable-closure|v1.2.2|间接依赖|composer|
|ramsey/uuid|4.4.0|间接依赖|composer|
|markbaker/matrix|3.0.0|间接依赖|composer|
|ramsey/collection|1.2.2|间接依赖|composer|
|psr/simple-cache|2.0.0|间接依赖|composer|
|guzzlehttp/guzzle|7.5.0|间接依赖|composer|
|diglactic/laravel-breadcrumbs|v7.2.0|间接依赖|composer|
|konekt/enum|4.0.1|间接依赖|composer|
|symfony/var-dumper|v6.1.3|间接依赖|composer|
|guzzlehttp/psr7|2.4.1|间接依赖|composer|
|fruitcake/php-cors|v1.2.0|间接依赖|composer|
|league/mime-type-detection|1.11.0|间接依赖|composer|
|vlucas/phpdotenv|v5.4.1|间接依赖|composer|
|symfony/translation-contracts|v3.1.1|间接依赖|composer|
|symfony/routing|v6.1.3|间接依赖|composer|
|symfony/polyfill-mbstring|v1.26.0|间接依赖|composer|
|symfony/event-dispatcher-contracts|v3.1.1|间接依赖|composer|
|illuminate/validation||间接依赖|composer|
|tijsverkoyen/css-to-inline-styles|2.2.5|间接依赖|composer|
|maennchen/zipstream-php|2.2.1|间接依赖|composer|
|monolog/monolog|2.8.0|间接依赖|composer|
|nunomaduro/termwind|v1.14.0|间接依赖|composer|
|symfony/process|v6.1.3|间接依赖|composer|
|symfony/polyfill-intl-normalizer|v1.26.0|间接依赖|composer|
|laravel/framework|v9.29.0|间接依赖|composer|
|symfony/mailer|v6.1.4|间接依赖|composer|
|symfony/polyfill-intl-grapheme|v1.26.0|间接依赖|composer|
|facade/ignition-contracts|1.0.2|间接依赖|composer|
|masterminds/html5|2.7.6|间接依赖|composer|
|maatwebsite/excel|3.1.40|间接依赖|composer|
|symfony/polyfill-php72|v1.26.0|间接依赖|composer|
|symfony/polyfill-ctype|v1.26.0|间接依赖|composer|
|league/commonmark|2.3.5|间接依赖|composer|
|doctrine/deprecations|v1.0.0|间接依赖|composer|
|konekt/enum-eloquent|1.8.1|间接依赖|composer|
|phenx/php-font-lib|0.5.4|间接依赖|composer|
|illuminate/contracts||间接依赖|composer|
|symfony/service-contracts|v3.1.1|间接依赖|composer|
|dflydev/dot-access-data|v3.0.1|间接依赖|composer|
|symfony/polyfill-php81|v1.26.0|间接依赖|composer|
|ezyang/htmlpurifier|v4.14.0|间接依赖|composer|
|symfony/translation|v6.1.4|间接依赖|composer|
|psr/http-factory|1.0.1|间接依赖|composer|
|illuminate/http||间接依赖|composer|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)