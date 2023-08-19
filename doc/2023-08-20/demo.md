# filamentphp/demo安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692967034270142464.svg)](https://www.murphysec.com/console/report/1692967033846517760/1692967034270142464)

仓库描述：Source code for the demo.filamentphp.com website.

仓库地址：[https://github.com/filamentphp/demo](https://github.com/filamentphp/demo)

| star：325 | watch：8 | fork：153 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-18 05:53:33 | 许可证：MIT |
| 最近检测时间：2023-08-20 02:29:38 | 组件总数：273 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Laravel v9.1.8 反序列化漏洞|反序列化|[MPS-2022-10162](https://www.oscs1024.com/hd/MPS-2022-10162)|CVE-2022-30778|严重|
|Vite 安全漏洞|使用不正确的解析名称或索引|[MPS-o473-85mg](https://www.oscs1024.com/hd/MPS-o473-85mg)|CVE-2023-34092|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|laravel/framework|v10.19.0||间接依赖|强烈建议修复|C:1|H:0|M:0|L:0|
|vite|3.0.4|4.3.9|直接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|207|Low|
|ISC|13|Low|
|LGPL-2.0|1|Medium|
|BSD-3-Clause|6|Low|
|BSD-4-Clause|3|Low|
|Apache-2.0|3|Low|
|GPL-2.0|1|Medium|
|GPL-3.0|1|Medium|
|CC-BY-4.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|postcss-value-parser|4.2.0|间接依赖|npm|
|object-hash|3.0.0|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|@popperjs/core|2.11.8|间接依赖|npm|
|symfony/mime|v6.3.3|间接依赖|composer|
|symfony/finder|v6.3.3|间接依赖|composer|
|postcss|8.4.24|间接依赖|npm|
|jiti|1.18.2|间接依赖|npm|
|filament/filament|v3.0.25|间接依赖|composer|
|esbuild-windows-64|0.14.54|间接依赖|npm|
|tippy.js|6.3.7|直接依赖|npm|
|laravel/serializable-closure|v1.3.1|间接依赖|composer|
|filament/spatie-laravel-settings-plugin|v3.0.25|间接依赖|composer|
|squirephp/rule|v3.4.2|间接依赖|composer|
|@vue/shared|3.1.5|间接依赖|npm|
|symfony/string|v6.3.2|间接依赖|composer|
|illuminate/cookie||间接依赖|composer|
|@vue/reactivity|3.1.5|间接依赖|npm|
|symfony/translation|v6.3.3|间接依赖|composer|
|esbuild-freebsd-arm64|0.14.54|间接依赖|npm|
|illuminate/console||间接依赖|composer|
|laravel/tinker|v2.8.1|间接依赖|composer|
|has|1.0.3|间接依赖|npm|
|commander|4.1.1|间接依赖|npm|
|composer-runtime-api||间接依赖|composer|
|squirephp/repository|v3.4.2|间接依赖|composer|
|spatie/laravel-settings|3.2.0|间接依赖|composer|
|psr/clock|1.0.0|间接依赖|composer|
|is-core-module|2.12.1|间接依赖|npm|
|egulias/email-validator|4.0.1|间接依赖|composer|
|lodash.castarray|4.4.0|间接依赖|npm|
|squirephp/currencies-en|v3.4.2|间接依赖|composer|
|webmozart/assert|1.11.0|间接依赖|composer|
|picocolors|1.0.0|间接依赖|npm|
|dragonmantank/cron-expression|v3.3.3|间接依赖|composer|
|illuminate/notifications||间接依赖|composer|
|psr/simple-cache|3.0.0|间接依赖|composer|
|league/flysystem|3.15.1|间接依赖|composer|
|doctrine/dbal|3.6.6|间接依赖|composer|
|psr/cache|3.0.0|间接依赖|composer|
|util-deprecate|1.0.2|间接依赖|npm|
|spatie/laravel-package-tools|1.16.0|间接依赖|composer|
|laravel/prompts|v0.1.5|间接依赖|composer|
|spatie/temporary-directory|2.1.2|间接依赖|composer|
|esbuild-linux-arm64|0.14.54|间接依赖|npm|
|source-map-js|1.0.2|间接依赖|npm|
|squirephp/countries-en|v3.4.2|间接依赖|composer|
|illuminate/session||间接依赖|composer|
|esbuild-android-arm64|0.14.54|间接依赖|npm|
|arg|5.0.2|间接依赖|npm|
|symfony/deprecation-contracts|v3.3.0|间接依赖|composer|
|postcss-selector-parser|6.0.10|间接依赖|npm|
|@esbuild/linux-loong64|0.14.54|间接依赖|npm|
|@alpinejs/focus|3.10.3|直接依赖|npm|
|phpdocumentor/reflection-common|2.2.0|间接依赖|composer|
|ralouphie/getallheaders|3.0.3|间接依赖|composer|
|yaml|2.3.1|间接依赖|npm|
|is-number|7.0.0|间接依赖|npm|
|league/mime-type-detection|1.13.0|间接依赖|composer|
|tijsverkoyen/css-to-inline-styles|2.2.6|间接依赖|composer|
|laravel/framework|v10.19.0|间接依赖|composer|
|filament/tables|v3.0.25|间接依赖|composer|
|league/flysystem-local|3.15.0|间接依赖|composer|
|brick/math|0.11.0|间接依赖|composer|
|lodash.isplainobject|4.0.6|间接依赖|npm|
|@nodelib/fs.scandir|2.1.5|间接依赖|npm|
|nanoid|3.3.6|间接依赖|npm|
|guzzlehttp/psr7|2.6.0|间接依赖|composer|
|danharrin/date-format-converter|v0.3.0|间接依赖|composer|
|spatie/image-optimizer|1.7.1|间接依赖|composer|
|league/uri|6.8.0|间接依赖|composer|
|@jridgewell/set-array|1.1.2|间接依赖|npm|
|illuminate/pipeline||间接依赖|composer|
|esbuild-linux-arm|0.14.54|间接依赖|npm|
|illuminate/support||间接依赖|composer|
|esbuild-freebsd-64|0.14.54|间接依赖|npm|
|illuminate/routing||间接依赖|composer|
|esbuild-openbsd-64|0.14.54|间接依赖|npm|
|focus-trap|6.9.4|间接依赖|npm|
|supports-preserve-symlinks-flag|1.0.0|间接依赖|npm|
|monolog/monolog|3.4.0|间接依赖|composer|
|vite-plugin-full-reload|1.0.3|间接依赖|npm|
|illuminate/http||间接依赖|composer|
|symfony/event-dispatcher|v6.3.2|间接依赖|composer|
|nikic/php-parser|v4.17.1|间接依赖|composer|
|esbuild-windows-32|0.14.54|间接依赖|npm|
|fraction.js|4.2.0|间接依赖|npm|
|symfony/polyfill-uuid|v1.27.0|间接依赖|composer|
|spatie/image|2.2.7|间接依赖|composer|
|esbuild-darwin-64|0.14.54|间接依赖|npm|
|guzzlehttp/guzzle|7.7.0|间接依赖|composer|
|illuminate/collections||间接依赖|composer|
|chokidar|3.5.3|间接依赖|npm|
|picomatch|2.3.1|间接依赖|npm|
|@nodelib/fs.stat|2.0.5|间接依赖|npm|
|normalize-range|0.1.2|间接依赖|npm|
|postcss-load-config|4.0.1|间接依赖|npm|
|fsevents|2.3.2|间接依赖|npm|
|spatie/eloquent-sortable|4.0.2|间接依赖|composer|
|esbuild-linux-s390x|0.14.54|间接依赖|npm|
|thenify-all|1.6.0|间接依赖|npm|
|esbuild-sunos-64|0.14.54|间接依赖|npm|
|doctrine/lexer|3.0.0|间接依赖|composer|
|spatie/color|1.5.3|间接依赖|composer|
|queue-microtask|1.2.3|间接依赖|npm|
|pify|2.3.0|间接依赖|npm|
|filament/support|v3.0.25|间接依赖|composer|
|illuminate/view||间接依赖|composer|
|@jridgewell/sourcemap-codec|1.4.15|间接依赖|npm|
|illuminate/filesystem||间接依赖|composer|
|doctrine/inflector|2.0.8|间接依赖|composer|
|symfony/polyfill-mbstring|v1.27.0|间接依赖|composer|
|ramsey/uuid|4.7.4|间接依赖|composer|
|merge2|1.4.1|间接依赖|npm|
|micromatch|4.0.5|间接依赖|npm|
|ts-interface-checker|0.1.13|间接依赖|npm|
|esbuild|0.14.54|间接依赖|npm|
|psr/http-message|1.1|间接依赖|composer|
|phpoption/phpoption|1.9.1|间接依赖|composer|
|wrappy|1.0.2|间接依赖|npm|
|illuminate/contracts||间接依赖|composer|
|spatie/laravel-translatable|6.5.3|间接依赖|composer|
|symfony/html-sanitizer|v6.3.0|间接依赖|composer|
|@jridgewell/resolve-uri|3.1.0|间接依赖|npm|
|squirephp/model|v3.4.2|间接依赖|composer|
|psy/psysh|v0.11.20|间接依赖|composer|
|anymatch|3.1.2|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|spatie/invade|1.1.1|间接依赖|composer|
|rollup|2.77.2|间接依赖|npm|
|nunomaduro/termwind|v1.15.1|间接依赖|composer|
|lodash.merge|4.6.2|间接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|masterminds/html5|2.8.1|间接依赖|composer|
|squirephp/countries|v3.4.2|间接依赖|composer|
|psr/http-factory|1.0.2|间接依赖|composer|
|@alloc/quick-lru|5.2.0|间接依赖|npm|
|symfony/polyfill-intl-idn|v1.27.0|间接依赖|composer|
|illuminate/conditionable||间接依赖|composer|
|inherits|2.0.4|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|autoprefixer|10.4.14|直接依赖|npm|
|filament/spatie-laravel-media-library-plugin|v3.0.25|间接依赖|composer|
|kirschbaum-development/eloquent-power-joins|3.2.1|间接依赖|composer|
|@tailwindcss/typography|0.5.9|直接依赖|npm|
|spatie/laravel-tags|4.5.1|间接依赖|composer|
|psr/event-dispatcher|1.0.0|间接依赖|composer|
|fill-range|7.0.1|间接依赖|npm|
|illuminate/bus||间接依赖|composer|
|laravel-vite-plugin|0.5.3|直接依赖|npm|
|symfony/polyfill-php80|v1.27.0|间接依赖|composer|
|flowframe/laravel-trend|v0.1.5|间接依赖|composer|
|ramsey/collection|2.0.0|间接依赖|composer|
|esbuild-windows-arm64|0.14.54|间接依赖|npm|
|nesbot/carbon|2.69.0|间接依赖|composer|
|symfony/service-contracts|v3.3.0|间接依赖|composer|
|thenify|3.3.1|间接依赖|npm|
|any-promise|1.3.0|间接依赖|npm|
|fast-glob|3.2.12|间接依赖|npm|
|lilconfig|2.1.0|间接依赖|npm|
|livewire/livewire|v3.0.0-beta.9|间接依赖|composer|
|league/config|v1.2.0|间接依赖|composer|
|symfony/event-dispatcher-contracts|v3.3.0|间接依赖|composer|
|@tailwindcss/forms|0.5.3|直接依赖|npm|
|esbuild-linux-64|0.14.54|间接依赖|npm|
|@jridgewell/trace-mapping|0.3.18|间接依赖|npm|
|graham-campbell/result-type|v1.1.1|间接依赖|composer|
|esbuild-linux-mips64le|0.14.54|间接依赖|npm|
|nette/schema|v1.2.4|间接依赖|composer|
|doctrine/event-manager|2.0.0|间接依赖|composer|
|guzzlehttp/uri-template|v1.0.1|间接依赖|composer|
|brace-expansion|1.1.11|间接依赖|npm|
|is-glob|4.0.3|间接依赖|npm|
|mz|2.7.0|间接依赖|npm|
|symfony/error-handler|v6.3.2|间接依赖|composer|
|spatie/laravel-medialibrary|10.11.3|间接依赖|composer|
|filament/spatie-laravel-translatable-plugin|v3.0.25|间接依赖|composer|
|inflight|1.0.6|间接依赖|npm|
|run-parallel|1.2.0|间接依赖|npm|
|akaunting/laravel-money|2.1.0|间接依赖|composer|
|caniuse-lite|1.0.30001504|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|browserslist|4.21.9|间接依赖|npm|
|tabbable|5.3.3|间接依赖|npm|
|filament/notifications|v3.0.25|间接依赖|composer|
|illuminate/validation||间接依赖|composer|
|ryangjchandler/blade-capture-directive|v0.3.0|间接依赖|composer|
|glob-parent|6.0.2|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|node-releases|2.0.12|间接依赖|npm|
|sucrase|3.32.0|间接依赖|npm|
|symfony/translation-contracts|v3.3.0|间接依赖|composer|
|symfony/polyfill-intl-grapheme|v1.27.0|间接依赖|composer|
|phpstan/phpdoc-parser|1.23.1|间接依赖|composer|
|illuminate/database||间接依赖|composer|
|esbuild-linux-riscv64|0.14.54|间接依赖|npm|
|mini-svg-data-uri|1.4.4|间接依赖|npm|
|danharrin/livewire-rate-limiting|v1.1.0|间接依赖|composer|
|symfony/process|v6.3.2|间接依赖|composer|
|postcss-import|15.1.0|间接依赖|npm|
|postcss-js|4.0.1|间接依赖|npm|
|filament/widgets|v3.0.25|间接依赖|composer|
|readdirp|3.6.0|间接依赖|npm|
|update-browserslist-db|1.0.11|间接依赖|npm|
|is-binary-path|2.1.0|间接依赖|npm|
|reusify|1.0.4|间接依赖|npm|
|filament/forms|v3.0.25|间接依赖|composer|
|blade-ui-kit/blade-icons|1.5.2|间接依赖|composer|
|balanced-match|1.0.2|间接依赖|npm|
|postcss-nested|6.0.1|间接依赖|npm|
|symfony/polyfill-ctype|v1.27.0|间接依赖|composer|
|doctrine/cache|2.2.0|间接依赖|composer|
|dlv|1.1.3|间接依赖|npm|
|binary-extensions|2.2.0|间接依赖|npm|
|lines-and-columns|1.2.4|间接依赖|npm|
|symfony/http-foundation|v6.3.2|间接依赖|composer|
|psr/log|3.0.0|间接依赖|composer|
|illuminate/auth||间接依赖|composer|
|vlucas/phpdotenv|v5.5.0|间接依赖|composer|
|path-is-absolute|1.0.1|间接依赖|npm|
|phpdocumentor/type-resolver|1.7.3|间接依赖|composer|
|psr/container|2.0.2|间接依赖|composer|
|symfony/var-dumper|v6.3.3|间接依赖|composer|
|filament/infolists|v3.0.25|间接依赖|composer|
|dflydev/dot-access-data|v3.0.2|间接依赖|composer|
|league/commonmark|2.4.0|间接依赖|composer|
|blade-ui-kit/blade-heroicons|2.1.0|间接依赖|composer|
|alpinejs|3.10.3|直接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|maennchen/zipstream-php|3.1.0|间接依赖|composer|
|read-cache|1.0.0|间接依赖|npm|
|laravel/sanctum|v3.2.5|间接依赖|composer|
|tailwindcss|3.3.2|直接依赖|npm|
|voku/portable-ascii|2.0.1|间接依赖|composer|
|filament/actions|v3.0.25|间接依赖|composer|
|symfony/polyfill-php83|v1.27.0|间接依赖|composer|
|esbuild-darwin-arm64|0.14.54|间接依赖|npm|
|esbuild-linux-32|0.14.54|间接依赖|npm|
|symfony/uid|v6.3.0|间接依赖|composer|
|psr/http-client|1.0.2|间接依赖|composer|
|@jridgewell/gen-mapping|0.3.3|间接依赖|npm|
|symfony/console|v6.3.2|间接依赖|composer|
|league/glide|2.3.0|间接依赖|composer|
|normalize-path|3.0.0|间接依赖|npm|
|camelcase-css|2.0.1|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|glob|7.1.6|间接依赖|npm|
|doctrine/deprecations|v1.1.1|间接依赖|composer|
|esbuild-linux-ppc64le|0.14.54|间接依赖|npm|
|@nodelib/fs.walk|1.2.8|间接依赖|npm|
|symfony/css-selector|v6.3.2|间接依赖|composer|
|symfony/routing|v6.3.3|间接依赖|composer|
|fastq|1.15.0|间接依赖|npm|
|fruitcake/php-cors|v1.2.0|间接依赖|composer|
|esbuild-netbsd-64|0.14.54|间接依赖|npm|
|resolve|1.22.2|间接依赖|npm|
|filament/spatie-laravel-tags-plugin|v3.0.25|间接依赖|composer|
|symfony/polyfill-php72|v1.27.0|间接依赖|composer|
|didyoumean|1.2.2|间接依赖|npm|
|guzzlehttp/promises|2.0.1|间接依赖|composer|
|symfony/http-kernel|v6.3.3|间接依赖|composer|
|electron-to-chromium|1.4.433|间接依赖|npm|
|pirates|4.0.5|间接依赖|npm|
|vite|3.0.4|直接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|symfony/mailer|v6.3.0|间接依赖|composer|
|squirephp/currencies|v3.4.2|间接依赖|composer|
|php-64bit||间接依赖|composer|
|cssesc|3.0.0|间接依赖|npm|
|symfony/polyfill-intl-normalizer|v1.27.0|间接依赖|composer|
|esbuild-android-64|0.14.54|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)