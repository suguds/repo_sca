# mautic/mautic安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1697677416554168320.svg)](https://www.murphysec.com/console/report/1695143074811699200/1697677416554168320)

仓库描述：Mautic: Open Source Marketing Automation Software.

仓库地址：[https://github.com/mautic/mautic](https://github.com/mautic/mautic)

| star：6020 | watch：303 | fork：2234 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-01 18:38:12 | 许可证：NOASSERTION |
| 最近检测时间：2023-09-02 02:28:04 | 组件总数：419 | 漏洞总数：2 |

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
|Apache-2.0|15|Low|
|ISC|26|Low|
|BSD-2-Clause|5|Low|
|LGPL-3.0|1|Medium|
|BSD-3-Clause|11|Low|
|LGPL-2.0|6|Medium|
|WTFPL|3|Low|
|自定义许可证|1|Low|
|LGPL-2.1|3|Medium|
|BSD-4-Clause|4|Low|
|0BSD|1|Low|
|GPL-3.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|eventemitter2|0.4.14|间接依赖|npm|
|aws/aws-sdk-php|3.271.0|间接依赖|composer|
|getobject|1.0.2|间接依赖|npm|
|composer/composer|2.2.18|间接依赖|composer|
|symfony/property-info|v6.0.19|间接依赖|composer|
|myclabs/php-enum|1.8.4|间接依赖|composer|
|less|4.1.2|间接依赖|npm|
|willdurand/jsonp-callback-validator|v2.0.0|间接依赖|composer|
|symfony/property-access|v5.4.22|间接依赖|composer|
|guzzlehttp/guzzle|7.6.1|间接依赖|composer|
|php-http/guzzle7-adapter|1.0.0|间接依赖|composer|
|psy/psysh|v0.10.12|间接依赖|composer|
|yargs|15.4.1|间接依赖|npm|
|symfony/amqp-messenger|v5.4.22|间接依赖|composer|
|league/flysystem-local|3.15.0|间接依赖|composer|
|codemirror|5.65.13|直接依赖|npm|
|underscore.string|3.3.6|间接依赖|npm|
|monolog/monolog|1.27.1|间接依赖|composer|
|path-root|0.1.1|间接依赖|npm|
|doctrine/inflector|2.0.6|间接依赖|composer|
|get-intrinsic|1.1.1|间接依赖|npm|
|symfony/validator|v5.4.22|间接依赖|composer|
|y18n|4.0.3|间接依赖|npm|
|make-dir|2.1.0|间接依赖|npm|
|jms/serializer|3.23.0|间接依赖|composer|
|emoji-regex|8.0.0|间接依赖|npm|
|friendsofphp/proxy-manager-lts|v1.0.12|间接依赖|composer|
|react/promise|v2.9.0|间接依赖|composer|
|symfony/monolog-bundle|v3.5.0|间接依赖|composer|
|locate-path|5.0.0|间接依赖|npm|
|symfony/security-csrf|v5.4.21|间接依赖|composer|
|entities|2.1.0|间接依赖|npm|
|colors|1.1.2|间接依赖|npm|
|side-channel|1.0.4|间接依赖|npm|
|doctrine/annotations|2.0.1|间接依赖|composer|
|symfony/mime|v5.4.23|间接依赖|composer|
|find-yarn-workspace-root|2.0.0|间接依赖|npm|
|seld/phar-utils|1.2.1|间接依赖|composer|
|is-plain-object|2.0.4|间接依赖|npm|
|composer/metadata-minifier|1.0.0|间接依赖|composer|
|safer-buffer|2.1.2|间接依赖|npm|
|symfony/security-bundle|v5.4.22|间接依赖|composer|
|knplabs/knp-menu|v3.3.0|间接依赖|composer|
|aws/aws-crt-php|v1.0.4|间接依赖|composer|
|object.map|1.0.1|间接依赖|npm|
|ckeditor4|4.21.0|直接依赖|npm|
|league/flysystem|3.15.1|间接依赖|composer|
|psr/log|1.1.4|间接依赖|composer|
|os-tmpdir|1.0.2|间接依赖|npm|
|modernizr|3.12.0|直接依赖|npm|
|extend|3.0.2|间接依赖|npm|
|has-symbols|1.0.3|间接依赖|npm|
|grunt-cli|1.4.3|间接依赖|npm|
|@claviska/jquery-minicolors|2.3.6|直接依赖|npm|
|is-windows|1.0.2|间接依赖|npm|
|ip2location/ip2location-php|7.2.5|间接依赖|composer|
|symfony/console|v5.4.22|间接依赖|composer|
|jms/serializer-bundle|5.1.0|间接依赖|composer|
|flagged-respawn|1.0.1|间接依赖|npm|
|symfony/messenger|v5.4.22|间接依赖|composer|
|paragonie/random_compat|v2.0.21|间接依赖|composer|
|symfony/polyfill-php72|v1.27.0|间接依赖|composer|
|guzzlehttp/psr7|2.4.5|间接依赖|composer|
|ramsey/collection|1.3.0|间接依赖|composer|
|yaml|2.2.2|间接依赖|npm|
|dropzone|4.3.0|直接依赖|npm|
|jquery.caret|0.3.1|直接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|qs|6.10.3|间接依赖|npm|
|grunt|1.6.1|直接依赖|npm|
|path-exists|4.0.0|间接依赖|npm|
|for-in|1.0.2|间接依赖|npm|
|throttleit|1.0.0|间接依赖|npm|
|at.js|1.5.4|直接依赖|npm|
|php-date-formatter|1.3.6|间接依赖|npm|
|symfony/polyfill-mbstring|v1.27.0|间接依赖|composer|
|parse-filepath|1.0.2|间接依赖|npm|
|symfony/dependency-injection|v5.4.24|间接依赖|composer|
|composer/spdx-licenses|1.5.7|间接依赖|composer|
|symfony/string|v6.0.19|间接依赖|composer|
|doctrine/deprecations|v1.0.0|间接依赖|composer|
|symfony/security-http|v5.4.22|间接依赖|composer|
|symfony/mailer|v5.4.22|间接依赖|composer|
|is-absolute|1.0.0|间接依赖|npm|
|sensio/framework-extra-bundle|v6.2.10|间接依赖|composer|
|symfony/error-handler|v5.4.24|间接依赖|composer|
|ralouphie/getallheaders|3.0.3|间接依赖|composer|
|js-cookie|2.2.1|直接依赖|npm|
|joomla/string|2.0.1|间接依赖|composer|
|symfony/intl|v5.4.22|间接依赖|composer|
|picomatch|2.3.1|间接依赖|npm|
|ci-info|3.8.0|间接依赖|npm|
|markdown-it|12.3.2|间接依赖|npm|
|doctrine/orm|2.15.1|间接依赖|composer|
|friendsofsymfony/oauth2-php|1.3.1|间接依赖|composer|
|psr/event-dispatcher|1.0.0|间接依赖|composer|
|fs-extra|9.1.0|间接依赖|npm|
|jquery|3.7.0|间接依赖|npm|
|set-blocking|2.0.0|间接依赖|npm|
|mrclay/props-dic|3.0.1|间接依赖|composer|
|beberlei/doctrineextensions|v1.3.0|间接依赖|composer|
|symfony/polyfill-intl-normalizer|v1.27.0|间接依赖|composer|
|wikimedia/less.php|v4.1.0|间接依赖|composer|
|symfony/filesystem|v5.4.23|间接依赖|composer|
|symfony/http-client-contracts|v2.5.2|间接依赖|composer|
|doctrine|3.0.0|间接依赖|npm|
|chart.js|2.9.4|直接依赖|npm|
|composer/package-versions-deprecated|1.11.99.1|间接依赖|composer|
|jquery.cookie|1.4.1|直接依赖|npm|
|ezyang/htmlpurifier|v4.14.0|间接依赖|composer|
|jsonfile|6.1.0|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|barryvdh/elfinder-flysystem-driver|v0.4.3|间接依赖|composer|
|once|1.4.0|间接依赖|npm|
|isobject|3.0.1|间接依赖|npm|
|jquery-ui-touch-punch|0.2.3|直接依赖|npm|
|global-prefix|1.0.2|间接依赖|npm|
|bandwidth-throttle/token-bucket|2.0.0|间接依赖|composer|
|camelcase|5.3.1|间接依赖|npm|
|image-size|0.5.5|间接依赖|npm|
|knplabs/knp-menu-bundle|v3.2.0|间接依赖|composer|
|patch-package|7.0.0|直接依赖|npm|
|at-least-node|1.0.0|间接依赖|npm|
|pda/pheanstalk|v4.0.4|间接依赖|composer|
|async|3.2.3|间接依赖|npm|
|symfony/expression-language|v5.4.21|间接依赖|composer|
|symfony/dotenv|v5.4.22|间接依赖|composer|
|tmp|0.0.33|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|tiny-emitter|2.1.0|间接依赖|npm|
|find-up|4.1.0|间接依赖|npm|
|mrclay/jsmin-php|2.4.3|间接依赖|composer|
|glob|7.1.7|间接依赖|npm|
|giggsey/locale|2.2|间接依赖|composer|
|wrap-ansi|6.2.0|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|ini|1.3.8|间接依赖|npm|
|litesaml/lightsaml|v4.1.4|间接依赖|composer|
|fs.realpath|1.0.0|间接依赖|npm|
|universalify|2.0.0|间接依赖|npm|
|file|0.2.2|间接依赖|npm|
|debug|3.2.7|间接依赖|npm|
|jquery.quicksearch|2.4.0|直接依赖|npm|
|slash|2.0.0|间接依赖|npm|
|psr/simple-cache|2.0.0|间接依赖|composer|
|body|5.1.0|间接依赖|npm|
|composer/semver|3.3.2|间接依赖|composer|
|seld/jsonlint|1.9.0|间接依赖|composer|
|doctrine/doctrine-migrations-bundle|3.2.2|间接依赖|composer|
|symfony/stopwatch|v5.4.21|间接依赖|composer|
|symfony/config|v5.4.21|间接依赖|composer|
|source-map|0.6.1|间接依赖|npm|
|matomo/device-detector|4.3.1|间接依赖|composer|
|cross-spawn|7.0.3|间接依赖|npm|
|micromatch|4.0.5|间接依赖|npm|
|composer/xdebug-handler|3.0.3|间接依赖|composer|
|livereload-js|2.4.0|间接依赖|npm|
|string-width|4.2.3|间接依赖|npm|
|pify|4.0.1|间接依赖|npm|
|symfony/deprecation-contracts|v2.5.2|间接依赖|composer|
|errno|0.1.8|间接依赖|npm|
|symfony/polyfill-php73|v1.27.0|间接依赖|composer|
|array-slice|1.1.0|间接依赖|npm|
|doctrine/data-fixtures|1.6.6|间接依赖|composer|
|supports-preserve-symlinks-flag|1.0.0|间接依赖|npm|
|decamelize|1.2.0|间接依赖|npm|
|symfony/polyfill-intl-idn|v1.27.0|间接依赖|composer|
|bytes|1.0.0|间接依赖|npm|
|rechoir|0.7.1|间接依赖|npm|
|symfony/templating|v5.4.21|间接依赖|composer|
|is-extglob|2.1.1|间接依赖|npm|
|doctrine/lexer|2.1.0|间接依赖|composer|
|php-amqplib/php-amqplib|v2.11.0|间接依赖|composer|
|sax|1.2.4|间接依赖|npm|
|array-each|1.0.1|间接依赖|npm|
|symfony/translation|v5.4.24|间接依赖|composer|
|justinrainbow/json-schema|5.2.12|间接依赖|composer|
|safe-buffer|5.2.1|间接依赖|npm|
|websocket-driver|0.7.4|间接依赖|npm|
|hooker|0.2.3|间接依赖|npm|
|psr/http-client|1.0.1|间接依赖|composer|
|helios-ag/fm-elfinder-bundle|12.3|间接依赖|composer|
|string_decoder|0.10.31|间接依赖|npm|
|exit|0.1.2|间接依赖|npm|
|guzzlehttp/oauth-subscriber|0.6.0|间接依赖|composer|
|symfony/yaml|v5.4.21|间接依赖|composer|
|which-module|2.0.1|间接依赖|npm|
|psr/cache|2.0.0|间接依赖|composer|
|php-http/httplug|2.3.0|间接依赖|composer|
|oneup/uploader-bundle|3.2.1|间接依赖|composer|
|psr/http-factory|1.0.1|间接依赖|composer|
|findup-sync|5.0.0|间接依赖|npm|
|strip-ansi|6.0.1|间接依赖|npm|
|studio-42/elfinder|2.1.62|间接依赖|composer|
|symfony/polyfill-ctype|v1.27.0|间接依赖|composer|
|object.pick|1.3.0|间接依赖|npm|
|maxmind-db/reader|v1.11.0|间接依赖|composer|
|php-amqplib/rabbitmq-bundle|2.5.3|间接依赖|composer|
|grunt-contrib-watch|1.1.0|直接依赖|npm|
|detect-file|1.0.0|间接依赖|npm|
|color-convert|2.0.1|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|make-iterator|1.0.1|间接依赖|npm|
|psr/container|1.1.2|间接依赖|composer|
|composer/installers|v1.12.0|间接依赖|composer|
|shebang-command|2.0.0|间接依赖|npm|
|esutils|2.0.3|间接依赖|npm|
|multiselect|0.9.12|直接依赖|npm|
|osenv|0.1.5|直接依赖|npm|
|is-docker|2.2.1|间接依赖|npm|
|symfony/doctrine-messenger|v5.4.21|间接依赖|composer|
|tubalmartin/cssmin|v4.1.1|间接依赖|composer|
|http-parser-js|0.5.6|间接依赖|npm|
|gaufrette/aws-s3-adapter|v0.4.0|间接依赖|composer|
|stack/builder|v1.0.6|间接依赖|composer|
|mime|1.6.0|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|doctrine/event-manager|1.2.0|间接依赖|composer|
|p-locate|4.1.0|间接依赖|npm|
|voku/portable-ascii|2.0.1|间接依赖|composer|
|gaufrette/extras|v0.1.0|间接依赖|composer|
|cliui|6.0.0|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|symfony/redis-messenger|v5.4.22|间接依赖|composer|
|jquery-mousewheel|3.1.13|间接依赖|npm|
|brick/math|0.11.0|间接依赖|composer|
|noxlogic/ratelimit-bundle|v1.19.0|间接依赖|composer|
|globule|1.3.3|间接依赖|npm|
|shufflejs|5.4.1|直接依赖|npm|
|league/mime-type-detection|1.11.0|间接依赖|composer|
|tightenco/collect|v8.83.23|间接依赖|composer|
|symfony/finder|v5.4.21|间接依赖|composer|
|doctrine/persistence|3.2.0|间接依赖|composer|
|voku/stop-words|2.0.1|间接依赖|composer|
|knplabs/gaufrette|v0.9.0|间接依赖|composer|
|tiny-lr|1.1.1|间接依赖|npm|
|composer-runtime-api||间接依赖|composer|
|grunt-legacy-log|3.0.0|间接依赖|npm|
|symfony/service-contracts|v2.5.2|间接依赖|composer|
|@yarnpkg/lockfile|1.1.0|间接依赖|npm|
|grunt-known-options|2.0.0|间接依赖|npm|
|os-homedir|1.0.2|间接依赖|npm|
|symfony/var-exporter|v6.0.19|间接依赖|composer|
|phpstan/phpdoc-parser|1.21.0|间接依赖|composer|
|doctrine/migrations|3.5.5|间接依赖|composer|
|twig/twig|v3.5.1|间接依赖|composer|
|inflight|1.0.6|间接依赖|npm|
|symfony/http-client|v5.4.22|间接依赖|composer|
|safe-json-parse|1.0.1|间接依赖|npm|
|needle|2.9.1|间接依赖|npm|
|chosen-js|1.8.7|直接依赖|npm|
|p-limit|2.3.0|间接依赖|npm|
|typeahead.js|0.11.1|直接依赖|npm|
|symfony/polyfill-intl-icu|v1.27.0|间接依赖|composer|
|matches-selector|1.2.0|间接依赖|npm|
|moment|2.29.4|间接依赖|npm|
|composer-plugin-api||间接依赖|composer|
|jsplumb|2.15.6|直接依赖|npm|
|doctrine/sql-formatter|1.1.3|间接依赖|composer|
|nikic/php-parser|v4.15.1|间接依赖|composer|
|requirejs|2.3.6|间接依赖|npm|
|ansi-styles|4.3.0|间接依赖|npm|
|symfony/process|v5.4.22|间接依赖|composer|
|copy-anything|2.0.6|间接依赖|npm|
|dateformat|4.6.3|间接依赖|npm|
|symfony/polyfill-php80|v1.27.0|间接依赖|composer|
|mrclay/minify|3.0.14|间接依赖|composer|
|symfony/routing|v5.4.22|间接依赖|composer|
|symfony/css-selector|v5.4.21|间接依赖|composer|
|mustangostang/spyc|0.6.3|间接依赖|composer|
|prr|1.0.1|间接依赖|npm|
|symfony/polyfill-intl-grapheme|v1.27.0|间接依赖|composer|
|uc.micro|1.0.6|间接依赖|npm|
|faye-websocket|0.10.0|间接依赖|npm|
|path-key|3.1.1|间接依赖|npm|
|minimist|1.2.8|间接依赖|npm|
|continuable-cache|0.3.1|间接依赖|npm|
|color-name|1.1.4|间接依赖|npm|
|parse-passwd|1.0.0|间接依赖|npm|
|symfony/monolog-bridge|v5.4.22|间接依赖|composer|
|fined|1.2.0|间接依赖|npm|
|theofidry/psysh-bundle|4.4.0|间接依赖|composer|
|php-http/promise|1.1.0|间接依赖|composer|
|symfony/doctrine-bridge|v5.4.22|间接依赖|composer|
|leezy/pheanstalk-bundle|dev-master|间接依赖|composer|
|array-parallel|0.1.3|间接依赖|npm|
|ms|2.1.3|间接依赖|npm|
|egulias/email-validator|3.2.5|间接依赖|composer|
|exercise/htmlpurifier-bundle|4.1.1|间接依赖|composer|
|symfony/event-dispatcher-contracts|v3.0.2|间接依赖|composer|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|symfony/cache|v5.4.23|间接依赖|composer|
|expand-tilde|2.0.2|间接依赖|npm|
|symfony/security-acl|v3.0.4|间接依赖|composer|
|lightsaml/sp-bundle|dev-symfony5|间接依赖|composer|
|abbrev|1.1.1|间接依赖|npm|
|jquery-datetimepicker|2.5.21|直接依赖|npm|
|mkdirp|0.5.5|间接依赖|npm|
|grunt-legacy-util|2.0.1|间接依赖|npm|
|symfony/twig-bundle|v5.4.21|间接依赖|composer|
|iconv-lite|0.4.24|间接依赖|npm|
|psr/http-message|1.0.1|间接依赖|composer|
|call-bind|1.0.2|间接依赖|npm|
|has-flag|4.0.0|直接依赖|npm|
|graceful-fs|4.2.10|间接依赖|npm|
|symfony/cache-contracts|v2.5.2|间接依赖|composer|
|symfony/translation-contracts|v2.5.2|间接依赖|composer|
|klaw-sync|6.0.0|间接依赖|npm|
|nopt|3.0.6|间接依赖|npm|
|open|7.4.2|间接依赖|npm|
|lightsaml/symfony-bridge|dev-symfony5|间接依赖|composer|
|predis/predis|v1.1.10|间接依赖|composer|
|linkify-it|3.0.3|间接依赖|npm|
|require-main-filename|2.0.0|间接依赖|npm|
|symfony/lock|v5.4.22|间接依赖|composer|
|braces|3.0.2|间接依赖|npm|
|websocket-extensions|0.1.4|间接依赖|npm|
|tslib|2.4.0|间接依赖|npm|
|parse-node-version|1.0.1|间接依赖|npm|
|kind-of|6.0.3|间接依赖|npm|
|symfony/twig-bridge|v5.4.22|间接依赖|composer|
|doctrine/doctrine-fixtures-bundle|3.4.4|间接依赖|composer|
|markbaker/complex|3.0.1|间接依赖|composer|
|semver|5.7.1|间接依赖|npm|
|jquery-ui|1.13.2|直接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|friendsofsymfony/oauth-server-bundle|dev-upgrade-2|间接依赖|composer|
|symfony/security-core|v5.4.22|间接依赖|composer|
|jvectormap-next|3.1.1|直接依赖|npm|
|which|2.0.2|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|vimeo-froogaloop2|0.1.1|直接依赖|npm|
|guzzlehttp/promises|1.5.3|间接依赖|composer|
|string-template|0.2.1|间接依赖|npm|
|giggsey/libphonenumber-for-php|8.12.56|间接依赖|composer|
|twilio/sdk|5.42.2|间接依赖|composer|
|symfony/http-foundation|v5.4.24|间接依赖|composer|
|path-is-absolute|1.0.1|间接依赖|npm|
|chartjs-color-string|0.6.0|间接依赖|npm|
|homedir-polyfill|1.0.3|间接依赖|npm|
|marcusschwarz/lesserphp|v0.5.5|间接依赖|composer|
|chartjs-color|2.4.1|间接依赖|npm|
|maennchen/zipstream-php|2.2.1|间接依赖|composer|
|rimraf|2.7.1|间接依赖|npm|
|global-modules|1.0.0|间接依赖|npm|
|symfony/polyfill-php81|v1.27.0|间接依赖|composer|
|geoip2/geoip2|v2.13.0|间接依赖|composer|
|willdurand/negotiation|3.1.0|间接依赖|composer|
|doctrine/cache|2.2.0|间接依赖|composer|
|symfony/security-guard|v5.4.22|间接依赖|composer|
|jms/metadata|2.6.1|间接依赖|composer|
|symfony/http-kernel|v5.4.24|间接依赖|composer|
|raw-body|1.1.7|间接依赖|npm|
|map-cache|0.2.2|间接依赖|npm|
|doctrine/instantiator|1.5.0|间接依赖|composer|
|error|7.2.1|间接依赖|npm|
|gaze|1.1.3|间接依赖|npm|
|intervention/httpauth|3.0.3|间接依赖|composer|
|mautic/core-lib|5.0.0-dev|间接依赖|composer|
|is-glob|4.0.3|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|object-inspect|1.12.0|间接依赖|npm|
|joomla/filter|1.4.4|间接依赖|composer|
|grunt-legacy-log-utils|2.1.0|间接依赖|npm|
|markbaker/matrix|3.0.0|间接依赖|composer|
|is-core-module|2.9.0|间接依赖|npm|
|liftup|3.0.1|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|mdurl|1.0.1|间接依赖|npm|
|jbroadway/urlify|1.2.4-stable|间接依赖|composer|
|yargs-parser|18.1.3|间接依赖|npm|
|symfony/form|v5.4.22|间接依赖|composer|
|intervention/image|2.7.2|间接依赖|composer|
|minimatch|3.0.8|间接依赖|npm|
|mousetrap|1.6.5|直接依赖|npm|
|has|1.0.3|间接依赖|npm|
|friendsofsymfony/rest-bundle|3.5.0|间接依赖|composer|
|symfony/event-dispatcher|v5.4.22|间接依赖|composer|
|doctrine/collections|1.8.0|间接依赖|composer|
|composer/ca-bundle|1.3.3|间接依赖|composer|
|resolve-dir|1.0.1|间接依赖|npm|
|js-yaml|3.14.1|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|kamermans/guzzle-oauth2-subscriber|v1.0.12|间接依赖|composer|
|phpseclib/phpseclib|2.0.38|间接依赖|composer|
|phpoffice/phpspreadsheet|1.24.1|间接依赖|composer|
|argparse|1.0.10|间接依赖|npm|
|simshaun/recurr|v5.0.1|间接依赖|composer|
|ramsey/uuid|4.7.4|间接依赖|composer|
|symfony/password-hasher|v6.0.19|间接依赖|composer|
|grunt-contrib-less|3.0.0|直接依赖|npm|
|v8flags|3.2.0|间接依赖|npm|
|symfony/asset|v5.4.21|间接依赖|composer|
|doctrine/doctrine-bundle|2.9.1|间接依赖|composer|
|get-caller-file|2.0.5|间接依赖|npm|
|composer/pcre|1.0.1|间接依赖|composer|
|is-wsl|2.2.0|间接依赖|npm|
|object.defaults|1.1.0|间接依赖|npm|
|symfony/framework-bundle|v5.4.24|间接依赖|composer|
|doctrine/common|3.4.3|间接依赖|composer|
|mtdowling/jmespath.php|2.6.1|间接依赖|composer|
|symfony/options-resolver|v5.4.21|间接依赖|composer|
|doctrine/dbal|3.6.2|间接依赖|composer|
|shebang-regex|3.0.0|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|symfony/var-dumper|v5.4.22|间接依赖|composer|
|interpret|1.1.0|间接依赖|npm|
|pimple/pimple|v3.5.0|间接依赖|composer|
|sprintf-js|1.0.3|间接依赖|npm|
|jquery-form|4.3.0|直接依赖|npm|
|is-what|3.14.1|间接依赖|npm|
|maxmind/web-service-common|v0.9.0|间接依赖|composer|
|resolve|1.22.0|间接依赖|npm|
|bootstrap|3.4.1|直接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|malkusch/lock|v1.4|间接依赖|composer|
|for-own|1.0.0|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|esprima|4.0.1|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)