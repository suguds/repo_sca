# filamentphp/demo安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700939416876138496.svg)](https://www.murphysec.com/console/report/1692967033846517760/1700939416876138496)

仓库描述：Source code for the demo.filamentphp.com website.

仓库地址：[https://github.com/filamentphp/demo](https://github.com/filamentphp/demo)

| star：370 | watch：9 | fork：172 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-10 13:10:17 | 许可证：MIT |
| 最近检测时间：2023-09-11 02:29:05 | 组件总数：273 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Laravel v9.1.8 反序列化漏洞|反序列化|[MPS-2022-10162](https://www.oscs1024.com/hd/MPS-2022-10162)|CVE-2022-30778|严重|
|Vite 安全漏洞|使用不正确的解析名称或索引|[MPS-o473-85mg](https://www.oscs1024.com/hd/MPS-o473-85mg)|CVE-2023-34092|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|laravel/framework|v10.22.0||间接依赖|强烈建议修复|C:1|H:0|M:0|L:0|
|vite|3.0.4|4.3.9|直接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|207|Low|
|ISC|13|Low|
|LGPL-2.0|1|Medium|
|Apache-2.0|3|Low|
|BSD-3-Clause|6|Low|
|BSD-4-Clause|3|Low|
|GPL-2.0|1|Medium|
|GPL-3.0|1|Medium|
|CC-BY-4.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|guzzlehttp/promises|2.0.1|间接依赖|composer|
|spatie/laravel-settings|3.2.0|间接依赖|composer|
|laravel/framework|v10.22.0|间接依赖|composer|
|@jridgewell/gen-mapping|0.3.3|间接依赖|npm|
|dlv|1.1.3|间接依赖|npm|
|esbuild-netbsd-64|0.14.54|间接依赖|npm|
|@tailwindcss/forms|0.5.3|直接依赖|npm|
|squirephp/currencies-en|v3.4.2|间接依赖|composer|
|browserslist|4.21.9|间接依赖|npm|
|squirephp/currencies|v3.4.2|间接依赖|composer|
|minimatch|3.1.2|间接依赖|npm|
|doctrine/dbal|3.6.6|间接依赖|composer|
|doctrine/lexer|3.0.0|间接依赖|composer|
|symfony/mailer|v6.3.0|间接依赖|composer|
|esbuild-freebsd-64|0.14.54|间接依赖|npm|
|graham-campbell/result-type|v1.1.1|间接依赖|composer|
|illuminate/conditionable||间接依赖|composer|
|squirephp/countries|v3.4.2|间接依赖|composer|
|league/flysystem-local|3.16.0|间接依赖|composer|
|readdirp|3.6.0|间接依赖|npm|
|tailwindcss|3.3.2|直接依赖|npm|
|illuminate/auth||间接依赖|composer|
|esbuild-linux-64|0.14.54|间接依赖|npm|
|supports-preserve-symlinks-flag|1.0.0|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|spatie/temporary-directory|2.1.2|间接依赖|composer|
|filament/filament|v3.0.45|间接依赖|composer|
|esbuild-linux-s390x|0.14.54|间接依赖|npm|
|league/config|v1.2.0|间接依赖|composer|
|symfony/event-dispatcher|v6.3.2|间接依赖|composer|
|illuminate/database||间接依赖|composer|
|blade-ui-kit/blade-heroicons|2.1.0|间接依赖|composer|
|filament/forms|v3.0.45|间接依赖|composer|
|symfony/var-dumper|v6.3.4|间接依赖|composer|
|nanoid|3.3.6|间接依赖|npm|
|fastq|1.15.0|间接依赖|npm|
|esbuild-freebsd-arm64|0.14.54|间接依赖|npm|
|ryangjchandler/blade-capture-directive|v0.3.0|间接依赖|composer|
|is-binary-path|2.1.0|间接依赖|npm|
|symfony/polyfill-uuid|v1.28.0|间接依赖|composer|
|phpoption/phpoption|1.9.1|间接依赖|composer|
|symfony/html-sanitizer|v6.3.4|间接依赖|composer|
|filament/spatie-laravel-settings-plugin|v3.0.45|间接依赖|composer|
|blade-ui-kit/blade-icons|1.5.2|间接依赖|composer|
|normalize-range|0.1.2|间接依赖|npm|
|akaunting/laravel-money|2.1.0|间接依赖|composer|
|symfony/uid|v6.3.0|间接依赖|composer|
|league/glide|2.3.0|间接依赖|composer|
|squirephp/rule|v3.4.2|间接依赖|composer|
|league/flysystem|3.16.0|间接依赖|composer|
|tijsverkoyen/css-to-inline-styles|2.2.6|间接依赖|composer|
|filament/actions|v3.0.45|间接依赖|composer|
|any-promise|1.3.0|间接依赖|npm|
|postcss-selector-parser|6.0.10|间接依赖|npm|
|pify|2.3.0|间接依赖|npm|
|filament/spatie-laravel-media-library-plugin|v3.0.45|间接依赖|composer|
|symfony/http-foundation|v6.3.4|间接依赖|composer|
|esbuild-linux-32|0.14.54|间接依赖|npm|
|electron-to-chromium|1.4.433|间接依赖|npm|
|doctrine/event-manager|2.0.0|间接依赖|composer|
|rollup|2.77.2|间接依赖|npm|
|chokidar|3.5.3|间接依赖|npm|
|doctrine/deprecations|v1.1.1|间接依赖|composer|
|tabbable|5.3.3|间接依赖|npm|
|spatie/laravel-package-tools|1.16.1|间接依赖|composer|
|illuminate/support||间接依赖|composer|
|esbuild-linux-mips64le|0.14.54|间接依赖|npm|
|run-parallel|1.2.0|间接依赖|npm|
|@tailwindcss/typography|0.5.9|直接依赖|npm|
|tippy.js|6.3.7|直接依赖|npm|
|didyoumean|1.2.2|间接依赖|npm|
|lodash.merge|4.6.2|间接依赖|npm|
|flowframe/laravel-trend|v0.1.5|间接依赖|composer|
|wrappy|1.0.2|间接依赖|npm|
|illuminate/filesystem||间接依赖|composer|
|phpdocumentor/type-resolver|1.7.3|间接依赖|composer|
|camelcase-css|2.0.1|间接依赖|npm|
|ramsey/collection|2.0.0|间接依赖|composer|
|psr/log|3.0.0|间接依赖|composer|
|webmozart/assert|1.11.0|间接依赖|composer|
|psr/http-factory|1.0.2|间接依赖|composer|
|esbuild-sunos-64|0.14.54|间接依赖|npm|
|esbuild|0.14.54|间接依赖|npm|
|pirates|4.0.5|间接依赖|npm|
|phpstan/phpdoc-parser|1.24.0|间接依赖|composer|
|esbuild-linux-ppc64le|0.14.54|间接依赖|npm|
|monolog/monolog|3.4.0|间接依赖|composer|
|util-deprecate|1.0.2|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|is-core-module|2.12.1|间接依赖|npm|
|vite|3.0.4|直接依赖|npm|
|dflydev/dot-access-data|v3.0.2|间接依赖|composer|
|lodash.isplainobject|4.0.6|间接依赖|npm|
|nette/schema|v1.2.4|间接依赖|composer|
|laravel/sanctum|v3.3.0|间接依赖|composer|
|balanced-match|1.0.2|间接依赖|npm|
|symfony/event-dispatcher-contracts|v3.3.0|间接依赖|composer|
|laravel/tinker|v2.8.2|间接依赖|composer|
|fruitcake/php-cors|v1.2.0|间接依赖|composer|
|@jridgewell/resolve-uri|3.1.0|间接依赖|npm|
|glob|7.1.6|间接依赖|npm|
|symfony/polyfill-php80|v1.28.0|间接依赖|composer|
|symfony/polyfill-intl-grapheme|v1.28.0|间接依赖|composer|
|symfony/deprecation-contracts|v3.3.0|间接依赖|composer|
|esbuild-linux-arm64|0.14.54|间接依赖|npm|
|phpdocumentor/reflection-common|2.2.0|间接依赖|composer|
|illuminate/bus||间接依赖|composer|
|thenify|3.3.1|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|spatie/laravel-tags|4.5.1|间接依赖|composer|
|illuminate/pipeline||间接依赖|composer|
|@jridgewell/sourcemap-codec|1.4.15|间接依赖|npm|
|esbuild-windows-arm64|0.14.54|间接依赖|npm|
|symfony/error-handler|v6.3.2|间接依赖|composer|
|thenify-all|1.6.0|间接依赖|npm|
|@nodelib/fs.scandir|2.1.5|间接依赖|npm|
|danharrin/date-format-converter|v0.3.0|间接依赖|composer|
|read-cache|1.0.0|间接依赖|npm|
|esbuild-windows-64|0.14.54|间接依赖|npm|
|filament/notifications|v3.0.45|间接依赖|composer|
|autoprefixer|10.4.14|直接依赖|npm|
|spatie/color|1.5.3|间接依赖|composer|
|psr/http-client|1.0.2|间接依赖|composer|
|laravel-vite-plugin|0.5.3|直接依赖|npm|
|binary-extensions|2.2.0|间接依赖|npm|
|resolve|1.22.2|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|ramsey/uuid|4.7.4|间接依赖|composer|
|voku/portable-ascii|2.0.1|间接依赖|composer|
|spatie/image-optimizer|1.7.1|间接依赖|composer|
|fast-glob|3.2.12|间接依赖|npm|
|psy/psysh|v0.11.20|间接依赖|composer|
|@popperjs/core|2.11.8|间接依赖|npm|
|laravel/serializable-closure|v1.3.1|间接依赖|composer|
|psr/event-dispatcher|1.0.0|间接依赖|composer|
|nunomaduro/termwind|v1.15.1|间接依赖|composer|
|spatie/laravel-translatable|6.5.3|间接依赖|composer|
|is-glob|4.0.3|间接依赖|npm|
|league/uri|7.3.0|间接依赖|composer|
|lilconfig|2.1.0|间接依赖|npm|
|squirephp/repository|v3.4.2|间接依赖|composer|
|illuminate/validation||间接依赖|composer|
|@jridgewell/set-array|1.1.2|间接依赖|npm|
|psr/container|2.0.2|间接依赖|composer|
|illuminate/routing||间接依赖|composer|
|spatie/invade|1.1.1|间接依赖|composer|
|mz|2.7.0|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|fraction.js|4.2.0|间接依赖|npm|
|masterminds/html5|2.8.1|间接依赖|composer|
|@vue/reactivity|3.1.5|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|spatie/image|2.2.7|间接依赖|composer|
|@vue/shared|3.1.5|间接依赖|npm|
|esbuild-windows-32|0.14.54|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|illuminate/contracts||间接依赖|composer|
|spatie/eloquent-sortable|4.0.2|间接依赖|composer|
|symfony/polyfill-intl-normalizer|v1.28.0|间接依赖|composer|
|vite-plugin-full-reload|1.0.3|间接依赖|npm|
|illuminate/console||间接依赖|composer|
|brace-expansion|1.1.11|间接依赖|npm|
|squirephp/countries-en|v3.4.2|间接依赖|composer|
|filament/widgets|v3.0.45|间接依赖|composer|
|@alloc/quick-lru|5.2.0|间接依赖|npm|
|esbuild-openbsd-64|0.14.54|间接依赖|npm|
|update-browserslist-db|1.0.11|间接依赖|npm|
|filament/infolists|v3.0.45|间接依赖|composer|
|node-releases|2.0.12|间接依赖|npm|
|postcss-js|4.0.1|间接依赖|npm|
|commander|4.1.1|间接依赖|npm|
|filament/spatie-laravel-tags-plugin|v3.0.45|间接依赖|composer|
|postcss-load-config|4.0.1|间接依赖|npm|
|symfony/routing|v6.3.3|间接依赖|composer|
|illuminate/session||间接依赖|composer|
|symfony/translation-contracts|v3.3.0|间接依赖|composer|
|symfony/mime|v6.3.3|间接依赖|composer|
|psr/clock|1.0.0|间接依赖|composer|
|symfony/process|v6.3.4|间接依赖|composer|
|is-extglob|2.1.1|间接依赖|npm|
|merge2|1.4.1|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|object-hash|3.0.0|间接依赖|npm|
|squirephp/model|v3.4.2|间接依赖|composer|
|psr/http-message|2.0|间接依赖|composer|
|@jridgewell/trace-mapping|0.3.18|间接依赖|npm|
|nikic/php-parser|v4.17.1|间接依赖|composer|
|psr/simple-cache|3.0.0|间接依赖|composer|
|symfony/polyfill-php83|v1.28.0|间接依赖|composer|
|symfony/translation|v6.3.3|间接依赖|composer|
|maennchen/zipstream-php|3.1.0|间接依赖|composer|
|esbuild-android-64|0.14.54|间接依赖|npm|
|ralouphie/getallheaders|3.0.3|间接依赖|composer|
|league/mime-type-detection|1.13.0|间接依赖|composer|
|picocolors|1.0.0|间接依赖|npm|
|ts-interface-checker|0.1.13|间接依赖|npm|
|filament/tables|v3.0.45|间接依赖|composer|
|postcss-nested|6.0.1|间接依赖|npm|
|fsevents|2.3.2|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|yaml|2.3.1|间接依赖|npm|
|cssesc|3.0.0|间接依赖|npm|
|@nodelib/fs.stat|2.0.5|间接依赖|npm|
|kirschbaum-development/eloquent-power-joins|3.2.3|间接依赖|composer|
|guzzlehttp/uri-template|v1.0.2|间接依赖|composer|
|picomatch|2.3.1|间接依赖|npm|
|postcss-value-parser|4.2.0|间接依赖|npm|
|illuminate/collections||间接依赖|composer|
|livewire/livewire|v3.0.2|间接依赖|composer|
|filament/spatie-laravel-translatable-plugin|v3.0.45|间接依赖|composer|
|normalize-path|3.0.0|间接依赖|npm|
|esbuild-android-arm64|0.14.54|间接依赖|npm|
|laravel/prompts|v0.1.6|间接依赖|composer|
|psr/cache|3.0.0|间接依赖|composer|
|illuminate/notifications||间接依赖|composer|
|escalade|3.1.1|间接依赖|npm|
|is-number|7.0.0|间接依赖|npm|
|@esbuild/linux-loong64|0.14.54|间接依赖|npm|
|symfony/service-contracts|v3.3.0|间接依赖|composer|
|guzzlehttp/psr7|2.6.1|间接依赖|composer|
|esbuild-linux-riscv64|0.14.54|间接依赖|npm|
|composer-runtime-api||间接依赖|composer|
|symfony/polyfill-mbstring|v1.28.0|间接依赖|composer|
|symfony/string|v6.3.2|间接依赖|composer|
|symfony/polyfill-php72|v1.28.0|间接依赖|composer|
|symfony/finder|v6.3.3|间接依赖|composer|
|lodash.castarray|4.4.0|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|micromatch|4.0.5|间接依赖|npm|
|postcss-import|15.1.0|间接依赖|npm|
|illuminate/cookie||间接依赖|composer|
|symfony/polyfill-ctype|v1.28.0|间接依赖|composer|
|queue-microtask|1.2.3|间接依赖|npm|
|symfony/console|v6.3.4|间接依赖|composer|
|source-map-js|1.0.2|间接依赖|npm|
|brick/math|0.11.0|间接依赖|composer|
|danharrin/livewire-rate-limiting|v1.1.0|间接依赖|composer|
|dragonmantank/cron-expression|v3.3.3|间接依赖|composer|
|object-assign|4.1.1|间接依赖|npm|
|league/commonmark|2.4.1|间接依赖|composer|
|lines-and-columns|1.2.4|间接依赖|npm|
|illuminate/http||间接依赖|composer|
|filament/support|v3.0.45|间接依赖|composer|
|esbuild-linux-arm|0.14.54|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|php-64bit||间接依赖|composer|
|jiti|1.18.2|间接依赖|npm|
|esbuild-darwin-arm64|0.14.54|间接依赖|npm|
|spatie/laravel-medialibrary|10.12.2|间接依赖|composer|
|doctrine/inflector|2.0.8|间接依赖|composer|
|arg|5.0.2|间接依赖|npm|
|doctrine/cache|2.2.0|间接依赖|composer|
|caniuse-lite|1.0.30001504|间接依赖|npm|
|guzzlehttp/guzzle|7.8.0|间接依赖|composer|
|reusify|1.0.4|间接依赖|npm|
|alpinejs|3.10.3|直接依赖|npm|
|symfony/polyfill-intl-idn|v1.28.0|间接依赖|composer|
|postcss|8.4.24|间接依赖|npm|
|sucrase|3.32.0|间接依赖|npm|
|mini-svg-data-uri|1.4.4|间接依赖|npm|
|symfony/css-selector|v6.3.2|间接依赖|composer|
|egulias/email-validator|4.0.1|间接依赖|composer|
|glob-parent|6.0.2|间接依赖|npm|
|focus-trap|6.9.4|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|esbuild-darwin-64|0.14.54|间接依赖|npm|
|vlucas/phpdotenv|v5.5.0|间接依赖|composer|
|anymatch|3.1.2|间接依赖|npm|
|@nodelib/fs.walk|1.2.8|间接依赖|npm|
|symfony/http-kernel|v6.3.4|间接依赖|composer|
|illuminate/view||间接依赖|composer|
|@alpinejs/focus|3.10.3|直接依赖|npm|
|nesbot/carbon|2.70.0|间接依赖|composer|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)