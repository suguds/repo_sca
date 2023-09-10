# assimon/dujiaoka安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700939548557180928.svg)](https://www.murphysec.com/console/report/1691878561173884928/1700939548557180928)

仓库描述：🦄独角数卡(自动售货系统)-开源站长自动化售货解决方案、高效、稳定、快速！🚀🚀🎉🎉

仓库地址：[https://github.com/assimon/dujiaoka](https://github.com/assimon/dujiaoka)

| star：6606 | watch：72 | fork：1753 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-21 10:54:16 | 许可证：MIT |
| 最近检测时间：2023-09-11 02:29:40 | 组件总数：85 | 漏洞总数：7 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Laravel Framework 安全漏洞|代码注入|[MPS-2019-1897](https://www.oscs1024.com/hd/MPS-2019-1897)|CVE-2019-9081|严重|
|Laravel v9.1.8 反序列化漏洞|反序列化|[MPS-2022-10162](https://www.oscs1024.com/hd/MPS-2022-10162)|CVE-2022-30778|严重|
|Sensio Labs Symfony 授权问题漏洞|授权机制不恰当|[MPS-2022-3861](https://www.oscs1024.com/hd/MPS-2022-3861)|CVE-2022-24894|高危|
|PSR-7 Message Implementation 安全漏洞|解释冲突|[MPS-2023-9403](https://www.oscs1024.com/hd/MPS-2023-9403)|CVE-2023-29197|高危|
|Laminas Project diactoros 拒绝服务漏洞|拒绝服务|[MPS-2023-9897](https://www.oscs1024.com/hd/MPS-2023-9897)|CVE-2023-29530|中危|
|Dcat Admin 跨站脚本漏洞|XSS|[MPS-5xhv-i37o](https://www.oscs1024.com/hd/MPS-5xhv-i37o)|CVE-2023-33736|中危|
|dcat-admin 存在存储型xss漏洞|XSS|[MPS-qse5-zowb](https://www.oscs1024.com/hd/MPS-qse5-zowb)||中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|laravel/framework|v6.20.42|8.83.24|间接依赖|强烈建议修复|C:2|H:0|M:0|L:0|
|guzzlehttp/psr7|1.9.0|2.4.5|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|dcat/laravel-admin|2.0.24-beta||间接依赖|可选修复|C:0|H:0|M:2|L:0|
|symfony/http-kernel|v4.4.39|6.2.6|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|76|Low|
|Apache-2.0|4|Low|
|BSD-3-Clause|6|Low|
|BSD-4-Clause|3|Low|
|LGPL-2.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|spatie/eloquent-sortable|3.11.0|间接依赖|composer|
|symfony/polyfill-php73|v1.25.0|间接依赖|composer|
|symfony/css-selector|v5.4.3|间接依赖|composer|
|jenssegers/agent|v2.6.4|间接依赖|composer|
|paragonie/random_compat|v9.99.100|间接依赖|composer|
|symfony/http-foundation|v4.4.39|间接依赖|composer|
|symfony/var-dumper|v4.4.39|间接依赖|composer|
|illuminate/filesystem||间接依赖|composer|
|germey/geetest|v3.1.0|间接依赖|composer|
|symfony/http-kernel|v4.4.39|间接依赖|composer|
|ralouphie/getallheaders|3.0.3|间接依赖|composer|
|symfony/mime|v5.4.3|间接依赖|composer|
|illuminate/session||间接依赖|composer|
|symfony/polyfill-intl-idn|v1.26.0|间接依赖|composer|
|psr/log|1.1.4|间接依赖|composer|
|laravel/tinker|v2.6.1|间接依赖|composer|
|symfony/polyfill-php80|v1.25.0|间接依赖|composer|
|league/flysystem|1.1.9|间接依赖|composer|
|dragonmantank/cron-expression|v2.3.1|间接依赖|composer|
|yansongda/pay|v2.10.2|间接依赖|composer|
|symfony/console|v4.4.38|间接依赖|composer|
|psr/http-client|1.0.1|间接依赖|composer|
|symfony/service-contracts|v2.5.0|间接依赖|composer|
|doctrine/inflector|2.0.4|间接依赖|composer|
|symfony/deprecation-contracts|v2.5.1|间接依赖|composer|
|symfony/translation-contracts|v2.5.0|间接依赖|composer|
|jaybizzle/crawler-detect|v1.2.106|间接依赖|composer|
|symfony/polyfill-ctype|v1.25.0|间接依赖|composer|
|fideloper/proxy|4.4.1|间接依赖|composer|
|symfony/polyfill-iconv|v1.25.0|间接依赖|composer|
|opis/closure|3.6.3|间接依赖|composer|
|amrshawky/laravel-currency|4.0.0|间接依赖|composer|
|egulias/email-validator|2.1.25|间接依赖|composer|
|stripe/stripe-php|v7.84.0|间接依赖|composer|
|symfony/routing|v4.4.37|间接依赖|composer|
|guzzlehttp/psr7|1.9.0|间接依赖|composer|
|symfony/error-handler|v4.4.37|间接依赖|composer|
|psr/simple-cache|1.0.1|间接依赖|composer|
|tijsverkoyen/css-to-inline-styles|2.2.4|间接依赖|composer|
|phpoption/phpoption|1.8.1|间接依赖|composer|
|yansongda/supports|v2.2.0|间接依赖|composer|
|mews/captcha|3.2.6|间接依赖|composer|
|illuminate/routing||间接依赖|composer|
|dcat/laravel-admin|2.0.24-beta|间接依赖|composer|
|league/commonmark|1.6.7|间接依赖|composer|
|illuminate/hashing||间接依赖|composer|
|box/spout|v3.3.0|间接依赖|composer|
|monolog/monolog|2.4.0|间接依赖|composer|
|psr/http-message|1.0.1|间接依赖|composer|
|swiftmailer/swiftmailer|v6.3.0|间接依赖|composer|
|nikic/php-parser|v4.10.5|间接依赖|composer|
|ramsey/uuid|3.9.6|间接依赖|composer|
|paypal/rest-api-sdk-php|1.14.0|间接依赖|composer|
|guzzlehttp/guzzle|7.4.5|间接依赖|composer|
|dcat/easy-excel|1.0.5|间接依赖|composer|
|psr/container|1.1.1|间接依赖|composer|
|symfony/finder|v4.4.37|间接依赖|composer|
|symfony/process|v4.4.37|间接依赖|composer|
|league/mime-type-detection|1.9.0|间接依赖|composer|
|doctrine/lexer|1.2.3|间接依赖|composer|
|guzzlehttp/promises|1.5.1|间接依赖|composer|
|vlucas/phpdotenv|v3.6.10|间接依赖|composer|
|laravel/framework|v6.20.42|间接依赖|composer|
|symfony/event-dispatcher-contracts|v1.1.11|间接依赖|composer|
|symfony/http-client-contracts|v2.5.0|间接依赖|composer|
|symfony/dom-crawler|v5.2.4|间接依赖|composer|
|illuminate/console||间接依赖|composer|
|illuminate/config||间接依赖|composer|
|bacon/bacon-qr-code|1.0.3|间接依赖|composer|
|xhat/payjs-laravel|1.6.0|间接依赖|composer|
|symfony/translation|v4.4.37|间接依赖|composer|
|symfony/polyfill-php72|v1.26.0|间接依赖|composer|
|symfony/polyfill-mbstring|v1.26.0|间接依赖|composer|
|illuminate/database||间接依赖|composer|
|psy/psysh|v0.10.8|间接依赖|composer|
|intervention/image|2.5.1|间接依赖|composer|
|symfony/event-dispatcher|v4.4.37|间接依赖|composer|
|mobiledetect/mobiledetectlib|2.8.37|间接依赖|composer|
|simplesoftwareio/simple-qrcode|2.0.0|间接依赖|composer|
|illuminate/contracts||间接依赖|composer|
|symfony/debug|v4.4.37|间接依赖|composer|
|illuminate/support||间接依赖|composer|
|amrshawky/currency|1.0.0|间接依赖|composer|
|nesbot/carbon|2.57.0|间接依赖|composer|
|symfony/polyfill-intl-normalizer|v1.26.0|间接依赖|composer|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)