# statamic/cms安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694779079969824768.svg)](https://www.murphysec.com/console/report/1694779079512645632/1694779079969824768)

仓库描述：The core Laravel CMS Composer package

仓库地址：[https://github.com/statamic/cms](https://github.com/statamic/cms)

| star：2917 | watch：30 | fork：409 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-25 00:20:59 | 许可证：NOASSERTION |
| 最近检测时间：2023-08-25 02:34:01 | 组件总数：276 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Laravel v9.1.8 反序列化漏洞|反序列化|[MPS-2022-10162](https://www.oscs1024.com/hd/MPS-2022-10162)|CVE-2022-30778|严重|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|laravel/framework|^9.50.0 || ^10.0||间接依赖|强烈建议修复|C:1|H:0|M:0|L:0|
|semver|5.7.2|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-2-Clause|8|Low|
|MIT|215|Low|
|BSD-3-Clause|8|Low|
|ISC|18|Low|
|Apache-2.0|4|Low|
|BSD-3-Clause-Clear|1|Low|
|Python-2.0|1|Low|
|Apache 2.0|1|Low|
|CC0-1.0|1|Low|
|Unlicense|2|Low|
|自定义许可证|1|Low|
|Public Domain|1|Low|
|LGPL-3.0|1|Medium|
|GPL-1.0|1|Medium|
|MPL-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|domutils|3.0.1|间接依赖|npm|
|prosemirror-state|1.4.2|间接依赖|npm|
|@tiptap/extension-table-header|2.0.2|间接依赖|npm|
|vue-countable|1.0.9|间接依赖|npm|
|@tiptap/extension-ordered-list|2.0.2|间接依赖|npm|
|speakingurl|14.0.1|间接依赖|npm|
|symfony/finder|v2.8.52|间接依赖|composer|
|@tiptap/extension-placeholder|2.0.2|间接依赖|npm|
|@remirror/core-helpers|2.0.1|间接依赖|npm|
|tree-helper|1.4.14|间接依赖|npm|
|lru-cache|4.1.5|间接依赖|npm|
|uniqid|5.4.0|间接依赖|npm|
|composer/ca-bundle|1.3.1|间接依赖|composer|
|vuex|3.6.2|间接依赖|npm|
|composer/semver|3.3.2|间接依赖|composer|
|once|1.4.0|间接依赖|npm|
|symfony/polyfill-mbstring|~1.0|间接依赖|composer|
|nopt|6.0.0|间接依赖|npm|
|http-parser-js|0.5.8|间接依赖|npm|
|moment|2.29.4|间接依赖|npm|
|@tiptap/extension-strike|2.0.2|间接依赖|npm|
|websocket-driver|0.7.4|间接依赖|npm|
|w3c-keyname|2.2.6|间接依赖|npm|
|type-fest|2.19.0|间接依赖|npm|
|linkify-it|4.0.1|间接依赖|npm|
|@tiptap/extension-hard-break|2.0.2|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|tippy.js|6.3.7|间接依赖|npm|
|postcss|8.4.21|间接依赖|npm|
|symfony/polyfill-php80|~1.15|间接依赖|composer|
|upload|1.3.2|间接依赖|npm|
|@tiptap/extension-code-block-lowlight|2.0.2|间接依赖|npm|
|laravel/helpers|^1.1|间接依赖|composer|
|asynckit|0.4.0|间接依赖|npm|
|vue-functions|1.0.6|间接依赖|npm|
|csso|5.0.5|间接依赖|npm|
|argparse|2.0.1|间接依赖|npm|
|@tiptap/extension-floating-menu|2.0.2|间接依赖|npm|
|league/csv|^9.0|间接依赖|composer|
|@tiptap/extension-character-count|2.0.2|间接依赖|npm|
|psr/container|^1.1|间接依赖|composer|
|composer/xdebug-handler|2.0.5|间接依赖|composer|
|source-map|0.6.1|间接依赖|npm|
|domelementtype|2.3.0|间接依赖|npm|
|js-beautify|1.14.7|间接依赖|npm|
|statamic/stringy|^3.1.2|间接依赖|composer|
|websocket-extensions|0.1.4|间接依赖|npm|
|editorconfig|0.15.3|间接依赖|npm|
|vue-toasted|1.1.28|间接依赖|npm|
|prosemirror-model|1.19.0|间接依赖|npm|
|prosemirror-tables|1.3.2|间接依赖|npm|
|laravel/framework|^9.50.0 || ^10.0|间接依赖|composer|
|@vue/reactivity|3.1.5|间接依赖|npm|
|spatie/blink|^1.3|间接依赖|composer|
|is-buffer|1.1.6|间接依赖|npm|
|v-calendar|2.4.1|间接依赖|npm|
|@tiptap/extension-typography|2.0.2|间接依赖|npm|
|symfony/process|v2.8.52|间接依赖|composer|
|floating-vue|1.0.0-beta.19|间接依赖|npm|
|prosemirror-collab|1.3.0|间接依赖|npm|
|is-whitespace|0.3.0|间接依赖|npm|
|regenerator-runtime|0.13.11|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|nth-check|2.1.1|间接依赖|npm|
|symfony/polyfill-intl-normalizer|~1.0|间接依赖|composer|
|rebing/graphql-laravel|^6.5 || ^8.0|间接依赖|composer|
|object.omit|3.0.0|间接依赖|npm|
|voku/portable-ascii|^1.6.1 || ^2.0|间接依赖|composer|
|prosemirror-dropcursor|1.8.0|间接依赖|npm|
|composer/composer|^1.10.22 || ^2.2.12|间接依赖|composer|
|symfony/polyfill-intl-grapheme|~1.0|间接依赖|composer|
|has-symbols|1.0.3|间接依赖|npm|
|is-extendable|0.1.1|间接依赖|npm|
|pixelfear/composer-dist-plugin|^0.1.4|间接依赖|composer|
|prosemirror-inputrules|1.2.0|间接依赖|npm|
|mousetrap|1.5.3|间接依赖|npm|
|@tiptap/extension-bullet-list|2.0.2|间接依赖|npm|
|domhandler|5.0.3|间接依赖|npm|
|nprogress|0.2.0|间接依赖|npm|
|orderedmap|2.1.0|间接依赖|npm|
|maennchen/zipstream-php|^2.2|间接依赖|composer|
|@tiptap/pm|2.0.2|间接依赖|npm|
|ajthinking/archetype|^1.0.3|间接依赖|composer|
|@types/object.omit|3.0.0|间接依赖|npm|
|@shopify/draggable|1.0.0-beta.12|间接依赖|npm|
|symfony/yaml|^4.1 || ^5.1 || ^6.0|间接依赖|composer|
|deepmerge|4.3.1|间接依赖|npm|
|symfony/var-exporter|^4.3 || ^5.1 || ^6.0|间接依赖|composer|
|portal-vue|1.5.1|间接依赖|npm|
|autosize|3.0.21|间接依赖|npm|
|mdn-data|2.0.30|间接依赖|npm|
|symfony/console|v2.8.52|间接依赖|composer|
|prosemirror-trailing-node|2.0.3|间接依赖|npm|
|follow-redirects|1.15.2|间接依赖|npm|
|abbrev|1.1.1|间接依赖|npm|
|axios|0.21.4|间接依赖|npm|
|@types/throttle-debounce|2.1.0|间接依赖|npm|
|justinrainbow/json-schema|5.2.11|间接依赖|composer|
|@tiptap/extension-table-cell|2.0.2|间接依赖|npm|
|@floating-ui/core|1.2.5|间接依赖|npm|
|kind-of|3.2.2|间接依赖|npm|
|symfony/polyfill-ctype|v1.19.0|间接依赖|composer|
|symfony/http-foundation|^4.3.3 || ^5.1.4 || ^6.0|间接依赖|composer|
|marked-plaintext|0.0.2|间接依赖|npm|
|league/glide|^1.1 || ^2.0|间接依赖|composer|
|symfony/filesystem|v2.8.52|间接依赖|composer|
|is-plain-object|2.0.4|间接依赖|npm|
|marked|4.3.0|间接依赖|npm|
|@remirror/types|1.0.0|间接依赖|npm|
|css-tree|2.3.1|间接依赖|npm|
|glob|8.1.0|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|prosemirror-history|1.3.0|间接依赖|npm|
|@vue/compiler-sfc|2.7.14|间接依赖|npm|
|tweetnacl|1.0.3|间接依赖|npm|
|laravel-echo|1.15.0|间接依赖|npm|
|prosemirror-transform|1.7.1|间接依赖|npm|
|case-anything|2.1.10|间接依赖|npm|
|object.pick|1.3.0|间接依赖|npm|
|resize-observer-polyfill|1.5.1|间接依赖|npm|
|date-fns-tz|1.3.8|间接依赖|npm|
|@tiptap/extension-table-row|2.0.2|间接依赖|npm|
|call-bind|1.0.2|间接依赖|npm|
|michelf/php-smartypants|^1.8.1|间接依赖|composer|
|symfony/string|^5.1|间接依赖|composer|
|@tiptap/extension-bold|2.0.2|间接依赖|npm|
|@tiptap/extension-subscript|2.0.2|间接依赖|npm|
|@tiptap/extension-underline|2.0.2|间接依赖|npm|
|@tiptap/extension-document|2.0.2|间接依赖|npm|
|escape-string-regexp|4.0.0|间接依赖|npm|
|draggable-helper|1.0.20|间接依赖|npm|
|@floating-ui/dom|0.1.10|间接依赖|npm|
|csstype|3.1.1|间接依赖|npm|
|vue|2.7.14|间接依赖|npm|
|side-channel|1.0.4|间接依赖|npm|
|css-tree|2.2.1|间接依赖|npm|
|entities|3.0.1|间接依赖|npm|
|format|0.2.2|间接依赖|npm|
|composer/metadata-minifier|1.0.0|间接依赖|composer|
|cookies-js|1.2.3|间接依赖|npm|
|MSVCR90.dll||间接依赖||
|seld/phar-utils|1.2.0|间接依赖|composer|
|symfony/deprecation-contracts|^2.1|间接依赖|composer|
|fast-deep-equal|3.1.3|间接依赖|npm|
|symfony/service-contracts|^1.1|^2|间接依赖|composer|
|prosemirror-schema-basic|1.2.1|间接依赖|npm|
|@tiptap/extension-history|2.0.2|间接依赖|npm|
|@tiptap/core|2.0.2|间接依赖|npm|
|@floating-ui/dom|1.2.5|间接依赖|npm|
|fuse.js|3.6.1|间接依赖|npm|
|rhukster/dom-sanitizer|^1.0.6|间接依赖|composer|
|@tiptap/extension-paragraph|2.0.2|间接依赖|npm|
|form-data|4.0.0|间接依赖|npm|
|make-error|1.3.6|间接依赖|npm|
|commander|2.20.3|间接依赖|npm|
|james-heinrich/getid3|^1.9.21|间接依赖|composer|
|dash-get|1.0.2|间接依赖|npm|
|mdurl|1.0.1|间接依赖|npm|
|core-js|3.29.1|间接依赖|npm|
|mime-types|2.1.35|间接依赖|npm|
|rope-sequence|1.3.3|间接依赖|npm|
|alpinejs|3.12.0|间接依赖|npm|
|pusher-js|4.4.0|间接依赖|npm|
|@types/hast|2.3.4|间接依赖|npm|
|react/promise|v1.2.1|间接依赖|composer|
|commander|7.2.0|间接依赖|npm|
|helper-js|1.4.38|间接依赖|npm|
|delayed-stream|1.0.0|间接依赖|npm|
|guzzlehttp/guzzle|^6.3 || ^7.0|间接依赖|composer|
|KERNEL32.dll||间接依赖||
|league/commonmark|^2.2|间接依赖|composer|
|proto-list|1.2.4|间接依赖|npm|
|source-map-js|1.0.2|间接依赖|npm|
|fault|2.0.1|间接依赖|npm|
|prosemirror-menu|1.2.1|间接依赖|npm|
|countable|3.0.1|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|body-scroll-lock|4.0.0-beta.0|间接依赖|npm|
|striptags|3.2.0|间接依赖|npm|
|mime-db|1.52.0|间接依赖|npm|
|prosemirror-view|1.30.2|间接依赖|npm|
|vue-resize|1.0.1|间接依赖|npm|
|@tiptap/extension-code|2.0.2|间接依赖|npm|
|pseudomap|1.0.2|间接依赖|npm|
|codemirror|5.65.12|间接依赖|npm|
|symfony/polyfill-ctype|~1.8|间接依赖|composer|
|inflight|1.0.6|间接依赖|npm|
|entities|4.4.0|间接依赖|npm|
|imask|6.6.0-alpha.0|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|prosemirror-keymap|1.2.1|间接依赖|npm|
|@types/unist|2.0.6|间接依赖|npm|
|@types/object.pick|1.3.2|间接依赖|npm|
|underscore|1.13.6|间接依赖|npm|
|ini|1.3.8|间接依赖|npm|
|vue-draggable-nested-tree|2.2.20|间接依赖|npm|
|prosemirror-schema-list|1.2.2|间接依赖|npm|
|throttle-debounce|3.0.1|间接依赖|npm|
|safe-buffer|5.2.1|间接依赖|npm|
|@tiptap/extension-heading|2.0.2|间接依赖|npm|
|wilderborn/partyline|^1.0|间接依赖|composer|
|@tiptap/extension-text-align|2.0.2|间接依赖|npm|
|sigmund|1.0.1|间接依赖|npm|
|drag-event-service|0.0.6|间接依赖|npm|
|prosemirror-commands|1.5.1|间接依赖|npm|
|config-chain|1.1.13|间接依赖|npm|
|pdfobject|2.2.8|间接依赖|npm|
|isobject|3.0.1|间接依赖|npm|
|xmlhttprequest|1.8.0|间接依赖|npm|
|@tiptap/extension-gapcursor|2.0.2|间接依赖|npm|
|validator|13.9.0|间接依赖|npm|
|symfony/polyfill-php80|^1.16|间接依赖|composer|
|vue-js-modal|2.0.1|间接依赖|npm|
|@tiptap/extension-dropcursor|2.0.2|间接依赖|npm|
|psr/log|^1 || ^2 || ^3|间接依赖|composer|
|pretty|2.0.0|间接依赖|npm|
|condense-newlines|0.2.1|间接依赖|npm|
|@tiptap/extension-horizontal-rule|2.0.2|间接依赖|npm|
|@trysound/sax|0.2.0|间接依赖|npm|
|@tiptap/extension-text|2.0.2|间接依赖|npm|
|crelt|1.0.5|间接依赖|npm|
|nanoid|3.3.6|间接依赖|npm|
|psr/log|1.1.4|间接依赖|composer|
|nesbot/carbon|^2.62.1|间接依赖|composer|
|@linaria/core|3.0.0-beta.13|间接依赖|npm|
|loose-envify|1.4.0|间接依赖|npm|
|composer/pcre|1.0.1|间接依赖|composer|
|svgo|3.0.2|间接依赖|npm|
|@vue/shared|3.1.5|间接依赖|npm|
|css-what|6.1.0|间接依赖|npm|
|extend-shallow|2.0.1|间接依赖|npm|
|object-inspect|1.12.3|间接依赖|npm|
|@tiptap/extension-superscript|2.0.2|间接依赖|npm|
|symfony/lock|^5.4|间接依赖|composer|
|@tiptap/extension-blockquote|2.0.2|间接依赖|npm|
|facade/ignition-contracts|^1.0|间接依赖|composer|
|seld/jsonlint|1.9.0|间接依赖|composer|
|picocolors|1.0.0|间接依赖|npm|
|MSVCP90.dll||间接依赖||
|prosemirror-gapcursor|1.3.1|间接依赖|npm|
|@tiptap/extension-italic|2.0.2|间接依赖|npm|
|boolbase|1.0.0|间接依赖|npm|
|@tiptap/extension-table|2.0.2|间接依赖|npm|
|css-select|5.1.0|间接依赖|npm|
|vue-clickaway|2.2.2|间接依赖|npm|
|prosemirror-changeset|2.2.0|间接依赖|npm|
|@tiptap/vue-2|2.0.2|间接依赖|npm|
|tweetnacl-util|0.15.1|间接依赖|npm|
|@remirror/core-constants|2.0.0|间接依赖|npm|
|@popperjs/core|2.11.7|间接依赖|npm|
|date-fns|2.29.3|间接依赖|npm|
|uc.micro|1.0.6|间接依赖|npm|
|@babel/parser|7.21.3|间接依赖|npm|
|ueberdosis/tiptap-php|^1.1|间接依赖|composer|
|qs|6.11.1|间接依赖|npm|
|symfony/polyfill-php73|^1.8|间接依赖|composer|
|composer/spdx-licenses|1.5.6|间接依赖|composer|
|inherits|2.0.4|间接依赖|npm|
|vue-select|3.20.2|间接依赖|npm|
|prosemirror-markdown|1.10.1|间接依赖|npm|
|is-extendable|1.0.1|间接依赖|npm|
|@tiptap/extension-bubble-menu|2.0.2|间接依赖|npm|
|markdown-it|13.0.1|间接依赖|npm|
|@babel/runtime|7.21.0|间接依赖|npm|
|symfony/polyfill-mbstring|v1.19.0|间接依赖|composer|
|faye-websocket|0.9.4|间接依赖|npm|
|highlight.js|11.7.0|间接依赖|npm|
|dom-serializer|2.0.0|间接依赖|npm|
|semver|5.7.2|间接依赖|npm|
|symfony/debug|v2.8.52|间接依赖|composer|
|get-intrinsic|1.2.0|间接依赖|npm|
|read-time-estimate|0.0.2|间接依赖|npm|
|@tiptap/extension-list-item|2.0.2|间接依赖|npm|
|combined-stream|1.0.8|间接依赖|npm|
|lowlight|2.8.1|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)