# mautic/mautic安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695143076002881536.svg)](https://www.murphysec.com/console/report/1695143074811699200/1695143076002881536)

仓库描述：Mautic: Open Source Marketing Automation Software.

仓库地址：[https://github.com/mautic/mautic](https://github.com/mautic/mautic)

| star：6012 | watch：302 | fork：2231 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-25 20:07:53 | 许可证：NOASSERTION |
| 最近检测时间：2023-08-26 02:36:55 | 组件总数：419 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|needle 存在Authorization请求头泄露漏洞|未授权敏感信息泄露|[MPS-2022-7866](https://www.oscs1024.com/hd/MPS-2022-7866)||中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|semver|5.7.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|needle|2.9.1|3.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|330|Low|
|ISC|26|Low|
|BSD-4-Clause|4|Low|
|LGPL-2.0|6|Medium|
|Apache-2.0|15|Low|
|0BSD|1|Low|
|LGPL-3.0|1|Medium|
|BSD-3-Clause|11|Low|
|BSD-2-Clause|5|Low|
|LGPL-2.1|3|Medium|
|WTFPL|3|Low|
|GPL-3.0|1|Medium|
|自定义许可证|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|friendsofsymfony/oauth2-php|1.3.1|间接依赖|composer|
|find-up|4.1.0|间接依赖|npm|
|semver|5.7.1|间接依赖|npm|
|leezy/pheanstalk-bundle|dev-master|间接依赖|composer|
|resolve|1.22.0|间接依赖|npm|
|require-main-filename|2.0.0|间接依赖|npm|
|brick/math|0.11.0|间接依赖|composer|
|extend|3.0.2|间接依赖|npm|
|guzzlehttp/promises|1.5.3|间接依赖|composer|
|grunt-legacy-log|3.0.0|间接依赖|npm|
|php-http/guzzle7-adapter|1.0.0|间接依赖|composer|
|doctrine/common|3.4.3|间接依赖|composer|
|psr/http-message|1.0.1|间接依赖|composer|
|symfony/yaml|v5.4.21|间接依赖|composer|
|jms/serializer|3.23.0|间接依赖|composer|
|gaufrette/extras|v0.1.0|间接依赖|composer|
|composer/metadata-minifier|1.0.0|间接依赖|composer|
|kamermans/guzzle-oauth2-subscriber|v1.0.12|间接依赖|composer|
|errno|0.1.8|间接依赖|npm|
|mkdirp|0.5.5|间接依赖|npm|
|websocket-driver|0.7.4|间接依赖|npm|
|iconv-lite|0.4.24|间接依赖|npm|
|symfony/options-resolver|v5.4.21|间接依赖|composer|
|object-assign|4.1.1|间接依赖|npm|
|tslib|2.4.0|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|symfony/security-core|v5.4.22|间接依赖|composer|
|doctrine/persistence|3.2.0|间接依赖|composer|
|jsplumb|2.15.6|直接依赖|npm|
|ini|1.3.8|间接依赖|npm|
|symfony/polyfill-php73|v1.27.0|间接依赖|composer|
|symfony/http-client-contracts|v2.5.2|间接依赖|composer|
|copy-anything|2.0.6|间接依赖|npm|
|composer/package-versions-deprecated|1.11.99.1|间接依赖|composer|
|brace-expansion|1.1.11|间接依赖|npm|
|doctrine/event-manager|1.2.0|间接依赖|composer|
|for-own|1.0.0|间接依赖|npm|
|mustangostang/spyc|0.6.3|间接依赖|composer|
|path-parse|1.0.7|间接依赖|npm|
|composer-runtime-api||间接依赖|composer|
|composer/spdx-licenses|1.5.7|间接依赖|composer|
|at-least-node|1.0.0|间接依赖|npm|
|glob|7.1.7|间接依赖|npm|
|ip2location/ip2location-php|7.2.5|间接依赖|composer|
|detect-file|1.0.0|间接依赖|npm|
|symfony/asset|v5.4.21|间接依赖|composer|
|litesaml/lightsaml|v4.1.4|间接依赖|composer|
|emoji-regex|8.0.0|间接依赖|npm|
|geoip2/geoip2|v2.13.0|间接依赖|composer|
|jquery.cookie|1.4.1|直接依赖|npm|
|stack/builder|v1.0.6|间接依赖|composer|
|os-homedir|1.0.2|间接依赖|npm|
|symfony/stopwatch|v5.4.21|间接依赖|composer|
|needle|2.9.1|间接依赖|npm|
|supports-preserve-symlinks-flag|1.0.0|间接依赖|npm|
|pify|4.0.1|间接依赖|npm|
|livereload-js|2.4.0|间接依赖|npm|
|symfony/templating|v5.4.21|间接依赖|composer|
|grunt-legacy-util|2.0.1|间接依赖|npm|
|symfony/polyfill-ctype|v1.27.0|间接依赖|composer|
|symfony/polyfill-php81|v1.27.0|间接依赖|composer|
|tubalmartin/cssmin|v4.1.1|间接依赖|composer|
|ansi-styles|4.3.0|间接依赖|npm|
|jquery.quicksearch|2.4.0|直接依赖|npm|
|nopt|3.0.6|间接依赖|npm|
|symfony/var-dumper|v5.4.22|间接依赖|composer|
|isexe|2.0.0|间接依赖|npm|
|symfony/cache-contracts|v2.5.2|间接依赖|composer|
|friendsofsymfony/oauth-server-bundle|dev-upgrade-2|间接依赖|composer|
|symfony/event-dispatcher|v5.4.22|间接依赖|composer|
|grunt-contrib-watch|1.1.0|直接依赖|npm|
|kind-of|6.0.3|间接依赖|npm|
|@claviska/jquery-minicolors|2.3.6|直接依赖|npm|
|once|1.4.0|间接依赖|npm|
|ralouphie/getallheaders|3.0.3|间接依赖|composer|
|jquery|3.7.0|间接依赖|npm|
|predis/predis|v1.1.10|间接依赖|composer|
|symfony/var-exporter|v6.0.19|间接依赖|composer|
|entities|2.1.0|间接依赖|npm|
|doctrine|3.0.0|间接依赖|npm|
|composer/pcre|1.0.1|间接依赖|composer|
|maennchen/zipstream-php|2.2.1|间接依赖|composer|
|symfony/mailer|v5.4.22|间接依赖|composer|
|doctrine/orm|2.15.1|间接依赖|composer|
|symfony/service-contracts|v2.5.2|间接依赖|composer|
|set-blocking|2.0.0|间接依赖|npm|
|tmp|0.0.33|间接依赖|npm|
|jquery-ui|1.13.2|直接依赖|npm|
|symfony/amqp-messenger|v5.4.22|间接依赖|composer|
|isobject|3.0.1|间接依赖|npm|
|is-what|3.14.1|间接依赖|npm|
|doctrine/migrations|3.5.5|间接依赖|composer|
|string_decoder|0.10.31|间接依赖|npm|
|symfony/polyfill-mbstring|v1.27.0|间接依赖|composer|
|parse-filepath|1.0.2|间接依赖|npm|
|less|4.1.2|间接依赖|npm|
|parse-passwd|1.0.0|间接依赖|npm|
|cross-spawn|7.0.3|间接依赖|npm|
|symfony/polyfill-intl-normalizer|v1.27.0|间接依赖|composer|
|symfony/password-hasher|v6.0.19|间接依赖|composer|
|symfony/error-handler|v5.4.24|间接依赖|composer|
|p-locate|4.1.0|间接依赖|npm|
|color-name|1.1.4|间接依赖|npm|
|shebang-command|2.0.0|间接依赖|npm|
|rechoir|0.7.1|间接依赖|npm|
|continuable-cache|0.3.1|间接依赖|npm|
|open|7.4.2|间接依赖|npm|
|nikic/php-parser|v4.15.1|间接依赖|composer|
|guzzlehttp/oauth-subscriber|0.6.0|间接依赖|composer|
|chart.js|2.9.4|直接依赖|npm|
|find-yarn-workspace-root|2.0.0|间接依赖|npm|
|symfony/framework-bundle|v5.4.24|间接依赖|composer|
|map-cache|0.2.2|间接依赖|npm|
|jquery-form|4.3.0|直接依赖|npm|
|homedir-polyfill|1.0.3|间接依赖|npm|
|doctrine/instantiator|1.5.0|间接依赖|composer|
|wikimedia/less.php|v4.1.0|间接依赖|composer|
|strip-ansi|6.0.1|间接依赖|npm|
|psr/log|1.1.4|间接依赖|composer|
|doctrine/doctrine-bundle|2.9.1|间接依赖|composer|
|doctrine/data-fixtures|1.6.6|间接依赖|composer|
|underscore.string|3.3.6|间接依赖|npm|
|is-wsl|2.2.0|间接依赖|npm|
|mousetrap|1.6.5|直接依赖|npm|
|getobject|1.0.2|间接依赖|npm|
|object.pick|1.3.0|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|call-bind|1.0.2|间接依赖|npm|
|yaml|2.2.2|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|knplabs/knp-menu|v3.3.0|间接依赖|composer|
|jms/serializer-bundle|5.1.0|间接依赖|composer|
|knplabs/knp-menu-bundle|v3.2.0|间接依赖|composer|
|resolve-dir|1.0.1|间接依赖|npm|
|league/flysystem|3.15.1|间接依赖|composer|
|willdurand/negotiation|3.1.0|间接依赖|composer|
|doctrine/lexer|2.1.0|间接依赖|composer|
|mime|1.6.0|间接依赖|npm|
|sensio/framework-extra-bundle|v6.2.10|间接依赖|composer|
|sprintf-js|1.0.3|间接依赖|npm|
|symfony/doctrine-bridge|v5.4.22|间接依赖|composer|
|simshaun/recurr|v5.0.1|间接依赖|composer|
|symfony/console|v5.4.22|间接依赖|composer|
|symfony/monolog-bridge|v5.4.22|间接依赖|composer|
|symfony/routing|v5.4.22|间接依赖|composer|
|doctrine/doctrine-fixtures-bundle|3.4.4|间接依赖|composer|
|path-exists|4.0.0|间接依赖|npm|
|voku/portable-ascii|2.0.1|间接依赖|composer|
|abbrev|1.1.1|间接依赖|npm|
|grunt|1.6.1|直接依赖|npm|
|symfony/twig-bundle|v5.4.21|间接依赖|composer|
|symfony/translation|v5.4.24|间接依赖|composer|
|symfony/filesystem|v5.4.23|间接依赖|composer|
|safer-buffer|2.1.2|间接依赖|npm|
|modernizr|3.12.0|直接依赖|npm|
|markdown-it|12.3.2|间接依赖|npm|
|doctrine/sql-formatter|1.1.3|间接依赖|composer|
|psr/simple-cache|2.0.0|间接依赖|composer|
|colors|1.1.2|间接依赖|npm|
|seld/phar-utils|1.2.1|间接依赖|composer|
|mtdowling/jmespath.php|2.6.1|间接依赖|composer|
|symfony/http-kernel|v5.4.24|间接依赖|composer|
|mrclay/props-dic|3.0.1|间接依赖|composer|
|object.defaults|1.1.0|间接依赖|npm|
|array-slice|1.1.0|间接依赖|npm|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|bandwidth-throttle/token-bucket|2.0.0|间接依赖|composer|
|php-amqplib/php-amqplib|v2.11.0|间接依赖|composer|
|symfony/security-csrf|v5.4.21|间接依赖|composer|
|symfony/finder|v5.4.21|间接依赖|composer|
|has-symbols|1.0.3|间接依赖|npm|
|gaze|1.1.3|间接依赖|npm|
|file|0.2.2|间接依赖|npm|
|doctrine/collections|1.8.0|间接依赖|composer|
|php-date-formatter|1.3.6|间接依赖|npm|
|doctrine/deprecations|v1.0.0|间接依赖|composer|
|phpoffice/phpspreadsheet|1.24.1|间接依赖|composer|
|php-http/promise|1.1.0|间接依赖|composer|
|websocket-extensions|0.1.4|间接依赖|npm|
|symfony/polyfill-intl-grapheme|v1.27.0|间接依赖|composer|
|patch-package|7.0.0|直接依赖|npm|
|giggsey/locale|2.2|间接依赖|composer|
|gaufrette/aws-s3-adapter|v0.4.0|间接依赖|composer|
|willdurand/jsonp-callback-validator|v2.0.0|间接依赖|composer|
|js-cookie|2.2.1|直接依赖|npm|
|knplabs/gaufrette|v0.9.0|间接依赖|composer|
|graceful-fs|4.2.10|间接依赖|npm|
|fined|1.2.0|间接依赖|npm|
|osenv|0.1.5|直接依赖|npm|
|twilio/sdk|5.42.2|间接依赖|composer|
|doctrine/dbal|3.6.2|间接依赖|composer|
|path-is-absolute|1.0.1|间接依赖|npm|
|chartjs-color|2.4.1|间接依赖|npm|
|mrclay/jsmin-php|2.4.3|间接依赖|composer|
|tiny-lr|1.1.1|间接依赖|npm|
|safe-json-parse|1.0.1|间接依赖|npm|
|justinrainbow/json-schema|5.2.12|间接依赖|composer|
|function-bind|1.1.1|间接依赖|npm|
|symfony/mime|v5.4.23|间接依赖|composer|
|linkify-it|3.0.3|间接依赖|npm|
|php-http/httplug|2.3.0|间接依赖|composer|
|rimraf|2.7.1|间接依赖|npm|
|symfony/polyfill-php72|v1.27.0|间接依赖|composer|
|require-directory|2.1.1|间接依赖|npm|
|error|7.2.1|间接依赖|npm|
|react/promise|v2.9.0|间接依赖|composer|
|symfony/event-dispatcher-contracts|v3.0.2|间接依赖|composer|
|is-windows|1.0.2|间接依赖|npm|
|chartjs-color-string|0.6.0|间接依赖|npm|
|aws/aws-crt-php|v1.0.4|间接依赖|composer|
|balanced-match|1.0.2|间接依赖|npm|
|grunt-legacy-log-utils|2.1.0|间接依赖|npm|
|globule|1.3.3|间接依赖|npm|
|doctrine/doctrine-migrations-bundle|3.2.2|间接依赖|composer|
|symfony/expression-language|v5.4.21|间接依赖|composer|
|which|2.0.2|间接依赖|npm|
|codemirror|5.65.13|直接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|prr|1.0.1|间接依赖|npm|
|composer/ca-bundle|1.3.3|间接依赖|composer|
|composer/composer|2.2.18|间接依赖|composer|
|monolog/monolog|1.27.1|间接依赖|composer|
|micromatch|4.0.5|间接依赖|npm|
|qs|6.10.3|间接依赖|npm|
|symfony/http-client|v5.4.22|间接依赖|composer|
|malkusch/lock|v1.4|间接依赖|composer|
|symfony/security-acl|v3.0.4|间接依赖|composer|
|string-template|0.2.1|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|helios-ag/fm-elfinder-bundle|12.3|间接依赖|composer|
|y18n|4.0.3|间接依赖|npm|
|liftup|3.0.1|间接依赖|npm|
|lightsaml/sp-bundle|dev-symfony5|间接依赖|composer|
|color-convert|2.0.1|间接依赖|npm|
|doctrine/annotations|2.0.1|间接依赖|composer|
|findup-sync|5.0.0|间接依赖|npm|
|symfony/cache|v5.4.23|间接依赖|composer|
|pimple/pimple|v3.5.0|间接依赖|composer|
|p-limit|2.3.0|间接依赖|npm|
|make-dir|2.1.0|间接依赖|npm|
|requirejs|2.3.6|间接依赖|npm|
|symfony/config|v5.4.21|间接依赖|composer|
|wrap-ansi|6.2.0|间接依赖|npm|
|image-size|0.5.5|间接依赖|npm|
|side-channel|1.0.4|间接依赖|npm|
|symfony/translation-contracts|v2.5.2|间接依赖|composer|
|inherits|2.0.4|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|shufflejs|5.4.1|直接依赖|npm|
|giggsey/libphonenumber-for-php|8.12.56|间接依赖|composer|
|symfony/security-guard|v5.4.22|间接依赖|composer|
|phpstan/phpdoc-parser|1.21.0|间接依赖|composer|
|psr/event-dispatcher|1.0.0|间接依赖|composer|
|@yarnpkg/lockfile|1.1.0|间接依赖|npm|
|symfony/deprecation-contracts|v2.5.2|间接依赖|composer|
|minimatch|3.0.8|间接依赖|npm|
|php-amqplib/rabbitmq-bundle|2.5.3|间接依赖|composer|
|is-docker|2.2.1|间接依赖|npm|
|array-each|1.0.1|间接依赖|npm|
|shebang-regex|3.0.0|间接依赖|npm|
|jquery-ui-touch-punch|0.2.3|直接依赖|npm|
|is-glob|4.0.3|间接依赖|npm|
|global-modules|1.0.0|间接依赖|npm|
|tightenco/collect|v8.83.23|间接依赖|composer|
|sax|1.2.4|间接依赖|npm|
|uc.micro|1.0.6|间接依赖|npm|
|grunt-contrib-less|3.0.0|直接依赖|npm|
|matches-selector|1.2.0|间接依赖|npm|
|faye-websocket|0.10.0|间接依赖|npm|
|object-inspect|1.12.0|间接依赖|npm|
|is-plain-object|2.0.4|间接依赖|npm|
|tiny-emitter|2.1.0|间接依赖|npm|
|psr/http-client|1.0.1|间接依赖|composer|
|ci-info|3.8.0|间接依赖|npm|
|symfony/form|v5.4.22|间接依赖|composer|
|symfony/monolog-bundle|v3.5.0|间接依赖|composer|
|theofidry/psysh-bundle|4.4.0|间接依赖|composer|
|symfony/polyfill-intl-icu|v1.27.0|间接依赖|composer|
|util-deprecate|1.0.2|间接依赖|npm|
|mrclay/minify|3.0.14|间接依赖|composer|
|dropzone|4.3.0|直接依赖|npm|
|bootstrap|3.4.1|直接依赖|npm|
|pda/pheanstalk|v4.0.4|间接依赖|composer|
|lodash|4.17.21|间接依赖|npm|
|decamelize|1.2.0|间接依赖|npm|
|maxmind-db/reader|v1.11.0|间接依赖|composer|
|joomla/filter|1.4.4|间接依赖|composer|
|raw-body|1.1.7|间接依赖|npm|
|at.js|1.5.4|直接依赖|npm|
|matomo/device-detector|4.3.1|间接依赖|composer|
|exercise/htmlpurifier-bundle|4.1.1|间接依赖|composer|
|concat-map|0.0.1|间接依赖|npm|
|make-iterator|1.0.1|间接依赖|npm|
|eventemitter2|0.4.14|间接依赖|npm|
|seld/jsonlint|1.9.0|间接依赖|composer|
|guzzlehttp/psr7|2.4.5|间接依赖|composer|
|grunt-known-options|2.0.0|间接依赖|npm|
|symfony/redis-messenger|v5.4.22|间接依赖|composer|
|yargs-parser|18.1.3|间接依赖|npm|
|for-in|1.0.2|间接依赖|npm|
|is-absolute|1.0.0|间接依赖|npm|
|jquery-datetimepicker|2.5.21|直接依赖|npm|
|minimist|1.2.8|间接依赖|npm|
|symfony/lock|v5.4.22|间接依赖|composer|
|psr/http-factory|1.0.1|间接依赖|composer|
|source-map|0.6.1|间接依赖|npm|
|psy/psysh|v0.10.12|间接依赖|composer|
|exit|0.1.2|间接依赖|npm|
|symfony/http-foundation|v5.4.24|间接依赖|composer|
|throttleit|1.0.0|间接依赖|npm|
|friendsofsymfony/rest-bundle|3.5.0|间接依赖|composer|
|friendsofphp/proxy-manager-lts|v1.0.12|间接依赖|composer|
|array-parallel|0.1.3|间接依赖|npm|
|is-core-module|2.9.0|间接依赖|npm|
|klaw-sync|6.0.0|间接依赖|npm|
|vimeo-froogaloop2|0.1.1|直接依赖|npm|
|moment|2.29.4|间接依赖|npm|
|os-tmpdir|1.0.2|间接依赖|npm|
|league/flysystem-local|3.15.0|间接依赖|composer|
|jms/metadata|2.6.1|间接依赖|composer|
|egulias/email-validator|3.2.5|间接依赖|composer|
|maxmind/web-service-common|v0.9.0|间接依赖|composer|
|slash|2.0.0|间接依赖|npm|
|interpret|1.1.0|间接依赖|npm|
|joomla/string|2.0.1|间接依赖|composer|
|cliui|6.0.0|间接依赖|npm|
|fs-extra|9.1.0|间接依赖|npm|
|symfony/property-info|v6.0.19|间接依赖|composer|
|symfony/validator|v5.4.22|间接依赖|composer|
|object.map|1.0.1|间接依赖|npm|
|bytes|1.0.0|间接依赖|npm|
|barryvdh/elfinder-flysystem-driver|v0.4.3|间接依赖|composer|
|ezyang/htmlpurifier|v4.14.0|间接依赖|composer|
|symfony/security-http|v5.4.22|间接依赖|composer|
|psr/container|1.1.2|间接依赖|composer|
|league/mime-type-detection|1.11.0|间接依赖|composer|
|multiselect|0.9.12|直接依赖|npm|
|jsonfile|6.1.0|间接依赖|npm|
|jquery.caret|0.3.1|直接依赖|npm|
|composer-plugin-api||间接依赖|composer|
|locate-path|5.0.0|间接依赖|npm|
|http-parser-js|0.5.6|间接依赖|npm|
|symfony/messenger|v5.4.22|间接依赖|composer|
|ramsey/collection|1.3.0|间接依赖|composer|
|composer/semver|3.3.2|间接依赖|composer|
|expand-tilde|2.0.2|间接依赖|npm|
|symfony/polyfill-intl-idn|v1.27.0|间接依赖|composer|
|psr/cache|2.0.0|间接依赖|composer|
|universalify|2.0.0|间接依赖|npm|
|marcusschwarz/lesserphp|v0.5.5|间接依赖|composer|
|hooker|0.2.3|间接依赖|npm|
|v8flags|3.2.0|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|ms|2.1.3|间接依赖|npm|
|symfony/css-selector|v5.4.21|间接依赖|composer|
|flagged-respawn|1.0.1|间接依赖|npm|
|lightsaml/symfony-bridge|dev-symfony5|间接依赖|composer|
|yargs|15.4.1|间接依赖|npm|
|body|5.1.0|间接依赖|npm|
|ramsey/uuid|4.7.4|间接依赖|composer|
|doctrine/inflector|2.0.6|间接依赖|composer|
|chosen-js|1.8.7|直接依赖|npm|
|dateformat|4.6.3|间接依赖|npm|
|symfony/dependency-injection|v5.4.24|间接依赖|composer|
|path-key|3.1.1|间接依赖|npm|
|studio-42/elfinder|2.1.62|间接依赖|composer|
|symfony/property-access|v5.4.22|间接依赖|composer|
|safe-buffer|5.2.1|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|twig/twig|v3.5.1|间接依赖|composer|
|js-yaml|3.14.1|间接依赖|npm|
|debug|3.2.7|间接依赖|npm|
|oneup/uploader-bundle|3.2.1|间接依赖|composer|
|ckeditor4|4.21.0|直接依赖|npm|
|markbaker/complex|3.0.1|间接依赖|composer|
|string-width|4.2.3|间接依赖|npm|
|get-intrinsic|1.1.1|间接依赖|npm|
|symfony/intl|v5.4.22|间接依赖|composer|
|argparse|1.0.10|间接依赖|npm|
|symfony/string|v6.0.19|间接依赖|composer|
|global-prefix|1.0.2|间接依赖|npm|
|mautic/core-lib|5.0.0-dev|间接依赖|composer|
|path-root|0.1.1|间接依赖|npm|
|symfony/process|v5.4.22|间接依赖|composer|
|aws/aws-sdk-php|3.271.0|间接依赖|composer|
|myclabs/php-enum|1.8.4|间接依赖|composer|
|symfony/dotenv|v5.4.22|间接依赖|composer|
|fs.realpath|1.0.0|间接依赖|npm|
|symfony/polyfill-php80|v1.27.0|间接依赖|composer|
|grunt-cli|1.4.3|间接依赖|npm|
|has-flag|4.0.0|直接依赖|npm|
|phpseclib/phpseclib|2.0.38|间接依赖|composer|
|intervention/httpauth|3.0.3|间接依赖|composer|
|composer/xdebug-handler|3.0.3|间接依赖|composer|
|beberlei/doctrineextensions|v1.3.0|间接依赖|composer|
|esutils|2.0.3|间接依赖|npm|
|camelcase|5.3.1|间接依赖|npm|
|mdurl|1.0.1|间接依赖|npm|
|doctrine/cache|2.2.0|间接依赖|composer|
|async|3.2.3|间接依赖|npm|
|voku/stop-words|2.0.1|间接依赖|composer|
|esprima|4.0.1|间接依赖|npm|
|composer/installers|v1.12.0|间接依赖|composer|
|jvectormap-next|3.1.1|直接依赖|npm|
|typeahead.js|0.11.1|直接依赖|npm|
|jquery-mousewheel|3.1.13|间接依赖|npm|
|which-module|2.0.1|间接依赖|npm|
|picomatch|2.3.1|间接依赖|npm|
|paragonie/random_compat|v2.0.21|间接依赖|composer|
|symfony/security-bundle|v5.4.22|间接依赖|composer|
|jbroadway/urlify|1.2.4-stable|间接依赖|composer|
|guzzlehttp/guzzle|7.6.1|间接依赖|composer|
|noxlogic/ratelimit-bundle|v1.19.0|间接依赖|composer|
|markbaker/matrix|3.0.0|间接依赖|composer|
|intervention/image|2.7.2|间接依赖|composer|
|symfony/twig-bridge|v5.4.22|间接依赖|composer|
|symfony/doctrine-messenger|v5.4.21|间接依赖|composer|
|parse-node-version|1.0.1|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)