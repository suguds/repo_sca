# magento/magento2安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696953310228410368.svg)](https://www.murphysec.com/console/report/1692604384456499200/1696953310228410368)

仓库描述：Prior to making any Submission(s), you must sign an Adobe Contributor License Agreement, available here at: https://opensource.adobe.com/cla.html. All Submissions you make to Adobe Inc. and its affiliates, assigns and subsidiaries (collectively “Adobe”) are subject to the terms of the Adobe Contributor License Agreement.

仓库地址：[https://github.com/magento/magento2](https://github.com/magento/magento2)

| star：10858 | watch：1274 | fork：9264 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-30 21:05:40 | 许可证：OSL-3.0 |
| 最近检测时间：2023-08-31 02:36:47 | 组件总数：136 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Sensio Labs Symfony 授权问题漏洞|授权机制不恰当|[MPS-2022-3861](https://www.oscs1024.com/hd/MPS-2022-3861)|CVE-2022-24894|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|symfony/http-kernel|v5.4.10|6.2.6|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|42|Low|
|MIT|72|Low|
|Apache-2.0|3|Low|
|LGPL-3.0|1|Medium|
|BSD-4-Clause|2|Low|
|LGPL-2.0|1|Medium|
|LGPL-2.1|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|laminas/laminas-eventmanager|3.9.0|间接依赖|composer|
|league/flysystem-aws-s3-v3|2.5.0|间接依赖|composer|
|laminas/laminas-stdlib|3.16.1|间接依赖|composer|
|symfony/polyfill-php81|v1.27.0|间接依赖|composer|
|laminas/laminas-escaper|2.12.0|间接依赖|composer|
|ralouphie/getallheaders|3.0.3|间接依赖|composer|
|aws/aws-sdk-php|3.275.1|间接依赖|composer|
|laminas/laminas-file|2.12.0|间接依赖|composer|
|elasticsearch/elasticsearch|v7.17.1|间接依赖|composer|
|laminas/laminas-json|3.5.0|间接依赖|composer|
|phpseclib/phpseclib|3.0.20|间接依赖|composer|
|symfony/filesystem|v6.3.1|间接依赖|composer|
|guzzlehttp/promises|1.5.3|间接依赖|composer|
|magento/zend-pdf|1.16.1|间接依赖|composer|
|league/mime-type-detection|1.11.0|间接依赖|composer|
|tedivm/jshrink|v1.4.0|间接依赖|composer|
|laminas/laminas-servicemanager|3.20.0|间接依赖|composer|
|magento/zend-exception|1.16.0|间接依赖|composer|
|laminas/laminas-di|3.11.0|间接依赖|composer|
|laminas/laminas-math|3.6.0|间接依赖|composer|
|justinrainbow/json-schema|5.2.12|间接依赖|composer|
|colinmollenhour/cache-backend-redis|1.14.2|间接依赖|composer|
|laminas/laminas-mvc|3.6.0|间接依赖|composer|
|seld/jsonlint|1.10.0|间接依赖|composer|
|laminas/laminas-zendframework-bridge|1.7.0|间接依赖|composer|
|monolog/monolog|2.9.1|间接依赖|composer|
|league/flysystem|2.5.0|间接依赖|composer|
|symfony/var-dumper|v6.3.1|间接依赖|composer|
|web-token/jwt-framework|3.1.2|间接依赖|composer|
|psr/http-factory|1.0.2|间接依赖|composer|
|container-interop/container-interop||间接依赖|composer|
|lib-libxml|*|间接依赖|composer|
|symfony/polyfill-ctype|v1.27.0|间接依赖|composer|
|fgrosse/phpasn1|v2.5.0|间接依赖|composer|
|psr/log|1.1.4|间接依赖|composer|
|magento/zend-db|1.16.0|间接依赖|composer|
|laminas/laminas-loader|2.9.0|间接依赖|composer|
|wikimedia/less.php|v3.2.0|间接依赖|composer|
|opensearch-project/opensearch-php|2.0.0|间接依赖|composer|
|laminas/laminas-filter|2.30.0|间接依赖|composer|
|laminas/laminas-feed|2.20.0|间接依赖|composer|
|symfony/event-dispatcher|v6.3.0|间接依赖|composer|
|magento/zend-log|1.16.0|间接依赖|composer|
|paragonie/random_compat|v9.99.100|间接依赖|composer|
|brick/varexporter|0.3.5|间接依赖|composer|
|magento/zend-loader|1.16.0|间接依赖|composer|
|symfony/polyfill-php73|v1.27.0|间接依赖|composer|
|nikic/php-parser|v4.16.0|间接依赖|composer|
|paragonie/constant_time_encoding|v2.6.3|间接依赖|composer|
|symfony/intl|v5.4.11|间接依赖|composer|
|symfony/console|v5.4.24|间接依赖|composer|
|psr/container|1.1.2|间接依赖|composer|
|pelago/emogrifier|v7.0.0|间接依赖|composer|
|symfony/polyfill-intl-grapheme|v1.27.0|间接依赖|composer|
|laminas/laminas-modulemanager|2.14.0|间接依赖|composer|
|guzzlehttp/psr7|2.5.0|间接依赖|composer|
|laminas/laminas-validator|2.29.0|间接依赖|composer|
|magento/composer-dependency-version-audit-plugin|0.1.1|间接依赖|composer|
|composer/composer|2.5.8|间接依赖|composer|
|laminas/laminas-i18n|2.21.0|间接依赖|composer|
|laminas/laminas-server|2.15.0|间接依赖|composer|
|composer/ca-bundle|1.3.6|间接依赖|composer|
|composer-plugin-api||间接依赖|composer|
|webonyx/graphql-php|v15.0.3|间接依赖|composer|
|doctrine/lexer|1.2.3|间接依赖|composer|
|aws/aws-crt-php|v1.2.1|间接依赖|composer|
|ezimuel/guzzlestreams|3.0.1|间接依赖|composer|
|composer/xdebug-handler|3.0.3|间接依赖|composer|
|symfony/http-kernel|v5.4.10|间接依赖|composer|
|laminas/laminas-http|2.18.0|间接依赖|composer|
|symfony/css-selector|v6.3.0|间接依赖|composer|
|laminas/laminas-router|3.11.0|间接依赖|composer|
|magento/composer|1.9.0|间接依赖|composer|
|composer/metadata-minifier|1.0.0|间接依赖|composer|
|symfony/polyfill-intl-normalizer|v1.27.0|间接依赖|composer|
|sabberworm/php-css-parser|8.4.0|间接依赖|composer|
|tubalmartin/cssmin|v4.1.1|间接依赖|composer|
|symfony/error-handler|v5.4.9|间接依赖|composer|
|ramsey/uuid|4.7.4|间接依赖|composer|
|doctrine/annotations|1.14.3|间接依赖|composer|
|laminas/laminas-mail|2.21.0|间接依赖|composer|
|colinmollenhour/cache-backend-file|v1.4.5|间接依赖|composer|
|phpseclib/mcrypt_compat|2.0.3|间接依赖|composer|
|laminas/laminas-recaptcha|3.6.0|间接依赖|composer|
|composer/spdx-licenses|1.5.7|间接依赖|composer|
|ezyang/htmlpurifier|v4.16.0|间接依赖|composer|
|ezimuel/ringphp|1.2.2|间接依赖|composer|
|spomky-labs/aes-key-wrap|v7.0.0|间接依赖|composer|
|symfony/process|v5.4.24|间接依赖|composer|
|symfony/string|v5.4.22|间接依赖|composer|
|webmozart/assert|1.11.0|间接依赖|composer|
|laminas/laminas-crypt|3.9.0|间接依赖|composer|
|php-amqplib/php-amqplib|v3.5.3|间接依赖|composer|
|ramsey/collection|2.0.0|间接依赖|composer|
|symfony/polyfill-php72|v1.27.0|间接依赖|composer|
|laminas/laminas-text|2.10.0|间接依赖|composer|
|laminas/laminas-config|3.8.0|间接依赖|composer|
|magento/zend-cache|1.16.0|间接依赖|composer|
|magento/zend-memory|1.16.0|间接依赖|composer|
|symfony/polyfill-php80|v1.27.0|间接依赖|composer|
|laminas/laminas-permissions-acl|2.13.0|间接依赖|composer|
|psr/http-client|1.0.2|间接依赖|composer|
|psr/cache|3.0.0|间接依赖|composer|
|symfony/finder|v5.4.21|间接依赖|composer|
|composer/pcre|3.1.0|间接依赖|composer|
|mtdowling/jmespath.php|2.6.1|间接依赖|composer|
|seld/phar-utils|1.2.1|间接依赖|composer|
|laminas/laminas-oauth|2.5.0|间接依赖|composer|
|magento/magento-composer-installer|0.4.0|间接依赖|composer|
|composer/semver|3.3.2|间接依赖|composer|
|guzzlehttp/guzzle|7.7.0|间接依赖|composer|
|webimpress/safe-writer|2.2.0|间接依赖|composer|
|laminas/laminas-view|2.25.0|间接依赖|composer|
|symfony/config|v5.4.11|间接依赖|composer|
|symfony/deprecation-contracts|v3.3.0|间接依赖|composer|
|laminas/laminas-session|2.16.0|间接依赖|composer|
|symfony/http-foundation|v5.4.25|间接依赖|composer|
|psr/http-message|1.1|间接依赖|composer|
|react/promise|v2.10.0|间接依赖|composer|
|symfony/event-dispatcher-contracts|v3.3.0|间接依赖|composer|
|colinmollenhour/php-redis-session-abstract|v1.5.0|间接依赖|composer|
|laminas/laminas-soap|2.12.0|间接依赖|composer|
|seld/signal-handler|2.0.1|间接依赖|composer|
|laminas/laminas-mime|2.11.0|间接依赖|composer|
|laminas/laminas-uri|2.10.0|间接依赖|composer|
|composer/class-map-generator|1.1.0|间接依赖|composer|
|laminas/laminas-captcha|2.15.0|间接依赖|composer|
|laminas/laminas-code|4.8.0|间接依赖|composer|
|laminas/laminas-db|2.16.3|间接依赖|composer|
|colinmollenhour/credis|v1.14.0|间接依赖|composer|
|symfony/polyfill-mbstring|v1.27.0|间接依赖|composer|
|symfony/polyfill-intl-idn|v1.27.0|间接依赖|composer|
|psr/event-dispatcher|1.0.0|间接依赖|composer|
|symfony/dependency-injection|v5.4.13|间接依赖|composer|
|symfony/service-contracts|v2.5.2|间接依赖|composer|
|brick/math|0.10.2|间接依赖|composer|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)