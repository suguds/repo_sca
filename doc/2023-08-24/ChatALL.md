# sunner/ChatALL安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694419026913878016.svg)](https://www.murphysec.com/console/report/1694056222633582592/1694419026913878016)

仓库描述： Concurrently chat with ChatGPT, Bing Chat, Bard, Alpaca, Vicuna, Claude, ChatGLM, MOSS, 讯飞星火, 文心一言 and more, discover the best answers

仓库地址：[https://github.com/sunner/ChatALL](https://github.com/sunner/ChatALL)

| star：9064 | watch：79 | fork：1422 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-23 15:41:25 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-24 02:39:28 | 组件总数：571 | 漏洞总数：7 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Braintree sanitize-url 跨站脚本漏洞|XSS|[MPS-2021-19687](https://www.oscs1024.com/hd/MPS-2021-19687)|CVE-2021-23648|中危|
|Markdown-It 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-37028](https://www.oscs1024.com/hd/MPS-2021-37028)|CVE-2022-21670|中危|
|Mermaid 跨站脚本漏洞|XSS|[MPS-2022-11138](https://www.oscs1024.com/hd/MPS-2022-11138)|CVE-2022-31108|中危|
|markdown-it<10.0.0 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13854](https://www.oscs1024.com/hd/MPS-2022-13854)||中危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|ejs 存在服务端模板注入漏洞|注入|[MPS-2023-10199](https://www.oscs1024.com/hd/MPS-2023-10199)|CVE-2023-29827|严重|
|Braintree sanitize-url 跨站脚本漏洞|XSS|[MPS-2023-5609](https://www.oscs1024.com/hd/MPS-2023-5609)|CVE-2022-48345|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|ejs|3.1.9||间接依赖|建议修复|C:1|H:0|M:0|L:0|
|semver|5.7.2|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|markdown-it|8.4.2|12.3.2|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|@braintree/sanitize-url|3.1.0|6.0.1|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|semver|6.3.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|mermaid|8.14.0|9.1.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|416|Low|
|Apache-2.0|12|Low|
|ISC|69|Low|
|BSD-3-Clause|23|Low|
|Unlicense|3|Low|
|CC-BY-3.0|1|Low|
|BSD-2-Clause|14|Low|
|Python-2.0|1|Low|
|MPL-2.0|2|Low|
|WTFPL|2|Low|
|CC-BY-4.0|1|Low|
|CC0-1.0|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|function-bind|1.1.1|间接依赖|npm|
|event-target-shim|5.0.1|间接依赖|npm|
|@vant/use|1.5.2|间接依赖|npm|
|ejs|3.1.9|间接依赖|npm|
|compare-versions|6.1.0|间接依赖|npm|
|bluebird|3.7.2|间接依赖|npm|
|acorn|8.10.0|间接依赖|npm|
|compare-version|0.1.2|间接依赖|npm|
|mdurl|1.0.1|间接依赖|npm|
|update-electron-app|2.0.1|间接依赖|npm|
|cli-cursor|3.1.0|间接依赖|npm|
|fs-extra|9.1.0|间接依赖|npm|
|toml|3.0.0|间接依赖|npm|
|mime-types|2.1.35|间接依赖|npm|
|type-fest|0.6.0|间接依赖|npm|
|d3-quadtree|3.0.1|间接依赖|npm|
|randombytes|2.1.0|间接依赖|npm|
|flat|5.0.2|间接依赖|npm|
|@intlify/vue-devtools|9.2.2|间接依赖|npm|
|node-releases|2.0.13|间接依赖|npm|
|chalk|4.1.2|间接依赖|npm|
|is-wsl|2.2.0|间接依赖|npm|
|picomatch|2.3.1|间接依赖|npm|
|buffer-from|1.1.2|间接依赖|npm|
|@types/uuid|9.0.2|间接依赖|npm|
|d3-interpolate|3.0.1|间接依赖|npm|
|available-typed-arrays|1.0.5|间接依赖|npm|
|@webassemblyjs/leb128|1.11.6|间接依赖|npm|
|@intlify/shared|9.2.2|间接依赖|npm|
|toggle-selection|1.0.6|间接依赖|npm|
|commander|2.20.3|间接依赖|npm|
|xss|1.0.14|间接依赖|npm|
|minipass|3.3.6|间接依赖|npm|
|is-unicode-supported|0.1.0|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|d3-drag|3.0.0|间接依赖|npm|
|d3-hierarchy|3.1.2|间接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.15|间接依赖|npm|
|emoji-regex|8.0.0|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|string.prototype.trimstart|1.0.6|间接依赖|npm|
|d3-dsv|2.0.0|间接依赖|npm|
|js-message|1.0.7|间接依赖|npm|
|markdown-it-anchor|5.3.0|间接依赖|npm|
|glob-parent|5.1.2|间接依赖|npm|
|crypt|0.0.2|间接依赖|npm|
|ignore|5.2.4|间接依赖|npm|
|markdown-it|8.4.2|间接依赖|npm|
|semver|7.5.4|间接依赖|npm|
|string.prototype.trim|1.2.7|间接依赖|npm|
|js-yaml|3.14.1|间接依赖|npm|
|gopd|1.0.1|间接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|base-64|0.1.0|间接依赖|npm|
|tmp-promise|3.0.3|间接依赖|npm|
|is-arrayish|0.2.1|间接依赖|npm|
|launch-editor|2.6.0|间接依赖|npm|
|d3-time-format|4.1.0|间接依赖|npm|
|playwright-core|1.37.1|间接依赖|npm|
|flatted|3.2.7|间接依赖|npm|
|function.prototype.name|1.1.5|间接依赖|npm|
|@types/eslint|8.44.2|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|semver|6.3.1|间接依赖|npm|
|@braintree/sanitize-url|3.1.0|间接依赖|npm|
|spdx-exceptions|2.3.0|间接依赖|npm|
|jsonpointer|5.0.1|间接依赖|npm|
|d3|5.16.0|间接依赖|npm|
|cli-spinners|2.9.0|间接依赖|npm|
|webidl-conversions|3.0.1|间接依赖|npm|
|axios|1.4.0|间接依赖|npm|
|@jridgewell/resolve-uri|3.1.1|间接依赖|npm|
|has-property-descriptors|1.0.0|间接依赖|npm|
|chromium-pickle-js|0.2.0|间接依赖|npm|
|bluebird-lst|1.0.9|间接依赖|npm|
|serialize-javascript|6.0.1|间接依赖|npm|
|vue|3.3.4|间接依赖|npm|
|@vue/compiler-sfc|3.3.4|间接依赖|npm|
|resize-observer-polyfill|1.5.1|间接依赖|npm|
|enhanced-resolve|5.15.0|间接依赖|npm|
|follow-redirects|1.15.2|间接依赖|npm|
|es-set-tostringtag|2.0.1|间接依赖|npm|
|argparse|2.0.1|间接依赖|npm|
|d3-scale|4.0.2|间接依赖|npm|
|deepmerge|4.3.1|间接依赖|npm|
|abort-controller|3.0.0|间接依赖|npm|
|@webassemblyjs/wasm-parser|1.11.6|间接依赖|npm|
|whatwg-url|5.0.0|间接依赖|npm|
|ansi-styles|4.3.0|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|is-glob|4.0.3|间接依赖|npm|
|form-data-encoder|1.7.2|间接依赖|npm|
|chokidar|3.5.3|间接依赖|npm|
|validate-npm-package-license|3.0.4|间接依赖|npm|
|update-browserslist-db|1.0.11|间接依赖|npm|
|webpack-chain|6.5.1|间接依赖|npm|
|rimraf|3.0.2|间接依赖|npm|
|easy-stack|1.0.1|间接依赖|npm|
|is-url|1.2.4|间接依赖|npm|
|truncate-utf8-bytes|1.0.2|间接依赖|npm|
|y18n|5.0.8|间接依赖|npm|
|globby|9.2.0|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|highlight.js|10.7.3|间接依赖|npm|
|agentkeepalive|4.5.0|间接依赖|npm|
|is-weakref|1.0.2|间接依赖|npm|
|mime-db|1.52.0|间接依赖|npm|
|decamelize|1.2.0|间接依赖|npm|
|is-array-buffer|3.0.2|间接依赖|npm|
|esrecurse|4.3.0|间接依赖|npm|
|tar|6.1.15|间接依赖|npm|
|@xtuc/ieee754|1.2.0|间接依赖|npm|
|events|3.3.0|间接依赖|npm|
|@vue/reactivity|3.3.4|间接依赖|npm|
|execa|1.0.0|间接依赖|npm|
|yaml|2.3.1|间接依赖|npm|
|brace-expansion|2.0.1|间接依赖|npm|
|string-width|4.2.3|间接依赖|npm|
|d3-format|3.1.0|间接依赖|npm|
|yargs-parser|20.2.9|间接依赖|npm|
|@xtuc/long|4.2.2|间接依赖|npm|
|@types/normalize-package-data|2.4.1|间接依赖|npm|
|@types/eslint-scope|3.7.4|间接依赖|npm|
|@hapi/topo|5.1.0|间接依赖|npm|
|@intlify/message-compiler|9.2.2|间接依赖|npm|
|vuex|4.1.0|间接依赖|npm|
|d3-brush|3.0.0|间接依赖|npm|
|typed-array-byte-offset|1.0.0|间接依赖|npm|
|es-module-lexer|1.3.0|间接依赖|npm|
|entities|2.1.0|间接依赖|npm|
|promised-map|1.0.0|间接依赖|npm|
|section-matter|1.0.0|间接依赖|npm|
|yallist|4.0.0|间接依赖|npm|
|defaults|1.0.4|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|open|8.4.2|间接依赖|npm|
|bl|4.1.0|间接依赖|npm|
|@intlify/core-base|9.2.2|间接依赖|npm|
|has-symbols|1.0.3|间接依赖|npm|
|d3-collection|1.0.7|间接依赖|npm|
|is-date-object|1.0.5|间接依赖|npm|
|@anthropic-ai/sdk|0.5.10|间接依赖|npm|
|is-buffer|1.1.6|间接依赖|npm|
|@types/fs-extra|9.0.13|间接依赖|npm|
|punycode|2.3.0|间接依赖|npm|
|utf8-byte-length|1.0.4|间接依赖|npm|
|graceful-fs|4.2.11|间接依赖|npm|
|clone|1.0.4|间接依赖|npm|
|shebang-command|2.0.0|间接依赖|npm|
|mkdirp|1.0.4|间接依赖|npm|
|sanitize-filename|1.6.3|间接依赖|npm|
|uuid|9.0.0|间接依赖|npm|
|camelcase|6.3.0|间接依赖|npm|
|mermaid|8.14.0|间接依赖|npm|
|d3-axis|3.0.0|间接依赖|npm|
|@babel/parser|7.22.10|间接依赖|npm|
|path-key|2.0.1|间接依赖|npm|
|anymatch|3.1.3|间接依赖|npm|
|base64-js|1.5.1|间接依赖|npm|
|side-channel|1.0.4|间接依赖|npm|
|normalize-package-data|2.5.0|间接依赖|npm|
|vue-matomo|4.2.0|间接依赖|npm|
|ajv|6.12.6|间接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|@jridgewell/trace-mapping|0.3.19|间接依赖|npm|
|d3-zoom|3.0.0|间接依赖|npm|
|is-stream|1.1.0|间接依赖|npm|
|terser-webpack-plugin|5.3.9|间接依赖|npm|
|@types/glob|7.2.0|间接依赖|npm|
|minizlib|2.1.2|间接依赖|npm|
|object-keys|1.1.1|间接依赖|npm|
|chownr|2.0.0|间接依赖|npm|
|esprima|4.0.1|间接依赖|npm|
|markdown-it-table-of-contents|0.4.4|间接依赖|npm|
|buffer|5.7.1|间接依赖|npm|
|is-docker|2.2.1|间接依赖|npm|
|dmg-builder|24.6.3|间接依赖|npm|
|supports-preserve-symlinks-flag|1.0.0|间接依赖|npm|
|combined-stream|1.0.8|间接依赖|npm|
|jake|10.8.7|间接依赖|npm|
|lodash.merge|4.6.2|间接依赖|npm|
|commander|5.1.0|间接依赖|npm|
|ml-distance-euclidean|2.0.0|间接依赖|npm|
|commander|8.3.0|间接依赖|npm|
|read-pkg|5.2.0|间接依赖|npm|
|kind-of|6.0.3|间接依赖|npm|
|num-sort|2.1.0|间接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|linkify-it|3.0.3|间接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|log-symbols|4.1.0|间接依赖|npm|
|dotenv-expand|5.1.0|间接依赖|npm|
|d3-dispatch|3.0.1|间接依赖|npm|
|restore-cursor|3.1.0|间接依赖|npm|
|@vue/runtime-dom|3.3.4|间接依赖|npm|
|@webassemblyjs/wasm-opt|1.11.6|间接依赖|npm|
|nice-try|1.0.5|间接依赖|npm|
|@electron/asar|3.2.4|间接依赖|npm|
|object-hash|3.0.0|间接依赖|npm|
|clone-deep|4.0.1|间接依赖|npm|
|p-timeout|3.2.0|间接依赖|npm|
|@intlify/devtools-if|9.2.2|间接依赖|npm|
|async-exit-hook|2.0.1|间接依赖|npm|
|@sideway/pinpoint|2.0.0|间接依赖|npm|
|@soda/friendly-errors-webpack-plugin|1.8.1|间接依赖|npm|
|@develar/schema-utils|2.6.5|间接依赖|npm|
|@webassemblyjs/ast|1.11.6|间接依赖|npm|
|@mdi/font|7.2.96|间接依赖|npm|
|@types/json-schema|7.0.12|间接依赖|npm|
|@sideway/formula|3.0.1|间接依赖|npm|
|node-fetch|2.6.13|间接依赖|npm|
|typed-array-buffer|1.0.0|间接依赖|npm|
|estraverse|5.3.0|间接依赖|npm|
|@types/node|18.17.6|间接依赖|npm|
|fs-extra|10.1.0|间接依赖|npm|
|insert-text-at-cursor|0.3.0|间接依赖|npm|
|gray-matter|4.0.3|间接依赖|npm|
|d3-scale-chromatic|3.0.0|间接依赖|npm|
|dagre-d3|0.6.4|间接依赖|npm|
|glob|7.2.3|间接依赖|npm|
|@types/node|20.5.1|间接依赖|npm|
|strip-eof|1.0.0|间接依赖|npm|
|d3-force|3.0.0|间接依赖|npm|
|signal-exit|3.0.7|间接依赖|npm|
|is-binary-path|2.1.0|间接依赖|npm|
|is-extendable|0.1.1|间接依赖|npm|
|isbinaryfile|5.0.0|间接依赖|npm|
|d3-color|3.1.0|间接依赖|npm|
|builder-util|24.5.0|间接依赖|npm|
|vuex-persist|3.1.3|间接依赖|npm|
|regenerator-runtime|0.14.0|间接依赖|npm|
|web-streams-polyfill|4.0.0-beta.3|间接依赖|npm|
|iconv-lite|0.6.3|间接依赖|npm|
|@kangc/v-md-editor|2.3.17|间接依赖|npm|
|hosted-git-info|2.8.9|间接依赖|npm|
|uc.micro|1.0.6|间接依赖|npm|
|is-bigint|1.0.4|间接依赖|npm|
|dagre|0.8.5|间接依赖|npm|
|robust-predicates|3.0.2|间接依赖|npm|
|spdx-correct|3.2.0|间接依赖|npm|
|json-parse-even-better-errors|2.3.1|间接依赖|npm|
|@babel/highlight|7.22.10|间接依赖|npm|
|watchpack|2.4.0|间接依赖|npm|
|is-boolean-object|1.1.2|间接依赖|npm|
|@babel/helper-validator-identifier|7.22.5|间接依赖|npm|
|d3-path|3.1.0|间接依赖|npm|
|element-matches|0.1.2|间接依赖|npm|
|string_decoder|1.1.1|间接依赖|npm|
|d3-contour|4.0.2|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|websocket-as-promised|2.0.1|间接依赖|npm|
|langsmith|0.0.25|间接依赖|npm|
|@jridgewell/source-map|0.3.5|间接依赖|npm|
|cross-spawn|7.0.3|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|filelist|1.0.4|间接依赖|npm|
|d3-dsv|3.0.1|间接依赖|npm|
|read-config-file|6.3.2|间接依赖|npm|
|es-to-primitive|1.2.1|间接依赖|npm|
|vue3-shortkey|4.0.0|间接依赖|npm|
|@types/retry|0.12.0|间接依赖|npm|
|@webassemblyjs/wasm-gen|1.11.6|间接依赖|npm|
|cliui|7.0.4|间接依赖|npm|
|@electron/universal|1.3.4|间接依赖|npm|
|for-each|0.3.3|间接依赖|npm|
|form-data|4.0.0|间接依赖|npm|
|array-buffer-byte-length|1.0.0|间接依赖|npm|
|@webassemblyjs/utf8|1.11.6|间接依赖|npm|
|webpack-merge|5.9.0|间接依赖|npm|
|simple-update-notifier|2.0.0|间接依赖|npm|
|define-properties|1.2.0|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|fs-minipass|2.1.0|间接依赖|npm|
|typed-array-length|1.0.4|间接依赖|npm|
|retry|0.13.1|间接依赖|npm|
|proxy-from-env|1.1.0|间接依赖|npm|
|@types/minimatch|5.1.2|间接依赖|npm|
|asynckit|0.4.0|间接依赖|npm|
|d3-time|3.1.0|间接依赖|npm|
|execa|5.1.1|间接依赖|npm|
|@vue/shared|3.3.4|间接依赖|npm|
|event-pubsub|4.3.0|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|glob-to-regexp|0.4.1|间接依赖|npm|
|babel-plugin-prismjs|2.1.0|间接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|d3-chord|3.0.1|间接依赖|npm|
|@webassemblyjs/ieee754|1.11.6|间接依赖|npm|
|js-tiktoken|1.0.7|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|formdata-node|4.4.1|间接依赖|npm|
|has-proto|1.0.1|间接依赖|npm|
|@babel/runtime|7.22.10|间接依赖|npm|
|ajv-keywords|3.5.2|间接依赖|npm|
|humanize-ms|1.2.1|间接依赖|npm|
|graphlib|2.1.8|间接依赖|npm|
|is-plain-object|2.0.4|间接依赖|npm|
|katex|0.13.24|间接依赖|npm|
|debug|4.3.4|间接依赖|npm|
|source-map-support|0.5.21|间接依赖|npm|
|vue-i18n|9.2.2|间接依赖|npm|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|vuetify|3.3.13|间接依赖|npm|
|eslint-scope|5.1.1|间接依赖|npm|
|fs-extra|7.0.1|间接依赖|npm|
|langchain|0.0.131|间接依赖|npm|
|supports-color|8.1.1|间接依赖|npm|
|stackframe|1.3.4|间接依赖|npm|
|is-negative-zero|2.0.2|间接依赖|npm|
|joi|17.9.2|间接依赖|npm|
|node-domexception|1.0.0|间接依赖|npm|
|escape-html|1.0.3|间接依赖|npm|
|is-regex|1.1.4|间接依赖|npm|
|typescript|4.9.5|间接依赖|npm|
|d3-selection|3.0.0|间接依赖|npm|
|has-tostringtag|1.0.0|间接依赖|npm|
|dompurify|2.3.5|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|markdown-it-chain|1.3.0|间接依赖|npm|
|codemirror|5.65.14|间接依赖|npm|
|postcss|8.4.28|间接依赖|npm|
|@vue/devtools-api|6.5.0|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|@vant/popperjs|1.3.0|间接依赖|npm|
|json5|2.2.3|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|at-least-node|1.0.0|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|call-bind|1.0.2|间接依赖|npm|
|is-core-module|2.13.0|间接依赖|npm|
|typed-array-byte-length|1.0.0|间接依赖|npm|
|which|2.0.2|间接依赖|npm|
|shallow-clone|3.0.1|间接依赖|npm|
|d3-array|3.2.4|间接依赖|npm|
|is-ci|3.0.1|间接依赖|npm|
|extend-shallow|2.0.1|间接依赖|npm|
|caniuse-lite|1.0.30001522|间接依赖|npm|
|core-js|3.32.1|间接依赖|npm|
|functions-have-names|1.2.3|间接依赖|npm|
|tr46|0.0.3|间接依赖|npm|
|custom-event-polyfill|1.0.7|间接依赖|npm|
|d3-polygon|3.0.1|间接依赖|npm|
|is-number-object|1.0.7|间接依赖|npm|
|commander|7.2.0|间接依赖|npm|
|dotenv|9.0.2|间接依赖|npm|
|promise.prototype.finally|3.1.4|间接依赖|npm|
|stylis|4.3.0|间接依赖|npm|
|vue-cli-plugin-electron-builder|3.0.0-alpha.4|间接依赖|npm|
|@webassemblyjs/helper-api-error|1.11.6|间接依赖|npm|
|@vue/reactivity-transform|3.3.4|间接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|material-design-icons|3.0.1|间接依赖|npm|
|agent-base|6.0.2|间接依赖|npm|
|app-builder-bin|4.0.0|间接依赖|npm|
|parse-json|5.2.0|间接依赖|npm|
|source-map-js|1.0.2|间接依赖|npm|
|@sideway/address|4.1.4|间接依赖|npm|
|webpack-sources|3.2.3|间接依赖|npm|
|yargs|17.7.2|间接依赖|npm|
|openai|3.3.0|间接依赖|npm|
|merge-stream|2.0.0|间接依赖|npm|
|unbox-primitive|1.0.2|间接依赖|npm|
|wcwidth|1.0.1|间接依赖|npm|
|ml-distance|4.0.1|间接依赖|npm|
|form-data|3.0.1|间接依赖|npm|
|npm-run-path|2.0.2|间接依赖|npm|
|is-shared-array-buffer|1.0.2|间接依赖|npm|
|7zip-bin|5.1.1|间接依赖|npm|
|@types/ms|0.7.31|间接依赖|npm|
|minimatch|5.1.6|间接依赖|npm|
|cross-spawn|6.0.5|间接依赖|npm|
|xmlbuilder|15.1.1|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|readable-stream|3.6.2|间接依赖|npm|
|@webassemblyjs/wast-printer|1.11.6|间接依赖|npm|
|temp-file|3.4.0|间接依赖|npm|
|estraverse|4.3.0|间接依赖|npm|
|define-lazy-prop|2.0.0|间接依赖|npm|
|khroma|1.4.1|间接依赖|npm|
|deepmerge|1.5.2|间接依赖|npm|
|csstype|3.1.2|间接依赖|npm|
|markdown-it|12.3.2|间接依赖|npm|
|wildcard|2.0.1|间接依赖|npm|
|upath|1.2.0|间接依赖|npm|
|get-symbol-description|1.0.0|间接依赖|npm|
|es-abstract|1.22.1|间接依赖|npm|
|loader-runner|4.3.0|间接依赖|npm|
|magic-string|0.30.2|间接依赖|npm|
|regexp.prototype.flags|1.5.0|间接依赖|npm|
|estree-walker|2.0.2|间接依赖|npm|
|sortablejs|1.15.0|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|isbinaryfile|4.0.10|间接依赖|npm|
|get-stream|4.1.0|间接依赖|npm|
|@achrinza/node-ipc|9.2.7|间接依赖|npm|
|isarray|2.0.5|间接依赖|npm|
|d3-timer|3.0.1|间接依赖|npm|
|copy-to-clipboard|3.3.3|间接依赖|npm|
|moment-mini|2.29.4|间接依赖|npm|
|arraybuffer.prototype.slice|1.0.1|间接依赖|npm|
|yargs|16.2.0|间接依赖|npm|
|md5|2.3.0|间接依赖|npm|
|browserslist|4.21.10|间接依赖|npm|
|acorn-import-assertions|1.9.0|间接依赖|npm|
|p-queue|6.6.2|间接依赖|npm|
|path-key|3.1.1|间接依赖|npm|
|binary-extensions|2.2.0|间接依赖|npm|
|js-yaml|4.1.0|间接依赖|npm|
|ansi-styles|5.2.0|间接依赖|npm|
|picocolors|1.0.0|间接依赖|npm|
|tapable|2.2.1|间接依赖|npm|
|d3-voronoi|1.1.4|间接依赖|npm|
|@vue/runtime-core|3.3.4|间接依赖|npm|
|color-name|1.1.3|间接依赖|npm|
|webpack|5.88.2|间接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|semver|5.7.2|间接依赖|npm|
|promise-controller|1.0.0|间接依赖|npm|
|safe-regex-test|1.0.0|间接依赖|npm|
|ml-array-sum|1.1.6|间接依赖|npm|
|get-intrinsic|1.2.1|间接依赖|npm|
|d3-delaunay|6.0.4|间接依赖|npm|
|lazy-val|1.0.5|间接依赖|npm|
|@jridgewell/set-array|1.1.2|间接依赖|npm|
|tmp|0.2.1|间接依赖|npm|
|d3-ease|3.0.1|间接依赖|npm|
|@webassemblyjs/helper-wasm-section|1.11.6|间接依赖|npm|
|github-url-to-object|4.0.6|间接依赖|npm|
|string.prototype.trimend|1.0.6|间接依赖|npm|
|d3-shape|3.2.0|间接依赖|npm|
|dir-compare|3.3.0|间接依赖|npm|
|wrap-ansi|7.0.0|间接依赖|npm|
|openapi-types|12.1.3|间接依赖|npm|
|@vue/compiler-ssr|3.3.4|间接依赖|npm|
|is-number|7.0.0|间接依赖|npm|
|plist|3.1.0|间接依赖|npm|
|is-typed-array|1.1.12|间接依赖|npm|
|which-boxed-primitive|1.0.2|间接依赖|npm|
|expr-eval|2.0.2|间接依赖|npm|
|strip-ansi|6.0.1|间接依赖|npm|
|mime|2.6.0|间接依赖|npm|
|is-callable|1.2.7|间接依赖|npm|
|ci-info|3.8.0|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|d3-random|3.0.1|间接依赖|npm|
|resolve|1.22.4|间接依赖|npm|
|is-symbol|1.0.4|间接依赖|npm|
|sax|1.2.4|间接依赖|npm|
|builder-util-runtime|9.2.1|间接依赖|npm|
|onetime|5.1.2|间接依赖|npm|
|markdown-it-attrs|4.1.6|间接依赖|npm|
|error-stack-parser|2.1.4|间接依赖|npm|
|minipass|5.0.0|间接依赖|npm|
|rw|1.3.3|间接依赖|npm|
|mimic-fn|2.1.0|间接依赖|npm|
|chalk|3.0.0|间接依赖|npm|
|digest-fetch|1.3.0|间接依赖|npm|
|spdx-license-ids|3.0.13|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|markdown-it-container|3.0.0|间接依赖|npm|
|electron-is-dev|0.3.0|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|electron-publish|24.5.0|间接依赖|npm|
|ml-array-mean|1.1.6|间接依赖|npm|
|strip-bom-string|1.0.0|间接依赖|npm|
|stat-mode|1.0.0|间接依赖|npm|
|webpack-chain|4.12.1|间接依赖|npm|
|axios|0.26.1|间接依赖|npm|
|neo-async|2.6.2|间接依赖|npm|
|javascript-stringify|2.1.0|间接依赖|npm|
|universalify|2.0.0|间接依赖|npm|
|d3-fetch|3.0.1|间接依赖|npm|
|isobject|3.0.1|间接依赖|npm|
|@malept/cross-spawn-promise|1.1.1|间接依赖|npm|
|p-finally|1.0.0|间接依赖|npm|
|electron-builder|24.6.3|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|@jridgewell/gen-mapping|0.3.3|间接依赖|npm|
|zod-to-json-schema|3.21.4|间接依赖|npm|
|hash-sum|1.0.2|间接依赖|npm|
|eventemitter3|4.0.7|间接依赖|npm|
|zod|3.22.2|间接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|hosted-git-info|4.1.0|间接依赖|npm|
|internmap|2.0.3|间接依赖|npm|
|spdx-expression-parse|3.0.1|间接依赖|npm|
|ml-tree-similarity|1.0.0|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|lru-cache|6.0.0|间接依赖|npm|
|@vue/compiler-dom|3.3.4|间接依赖|npm|
|@vant/icons|1.8.0|间接依赖|npm|
|d3-geo|3.1.0|间接依赖|npm|
|cssfilter|0.0.10|间接依赖|npm|
|async|3.2.4|间接依赖|npm|
|which-typed-array|1.1.11|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|shebang-regex|3.0.0|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|@vue/cli-shared-utils|5.0.8|间接依赖|npm|
|@types/estree|1.0.1|间接依赖|npm|
|iconv-lite|0.4.24|间接依赖|npm|
|@webassemblyjs/helper-buffer|1.11.6|间接依赖|npm|
|config-file-ts|0.2.4|间接依赖|npm|
|vant|3.6.12|间接依赖|npm|
|@xmldom/xmldom|0.8.10|间接依赖|npm|
|@vuepress/shared-utils|1.9.10|间接依赖|npm|
|is-any-array|2.0.1|间接依赖|npm|
|@types/node-fetch|2.6.4|间接依赖|npm|
|@electron/notarize|1.2.4|间接依赖|npm|
|nanoid|3.3.6|间接依赖|npm|
|is-string|1.0.7|间接依赖|npm|
|has-bigints|1.0.2|间接依赖|npm|
|pump|3.0.0|间接依赖|npm|
|charenc|0.0.2|间接依赖|npm|
|@vue/server-renderer|3.3.4|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|@webassemblyjs/floating-point-hex-parser|1.11.6|间接依赖|npm|
|minimist|1.2.8|间接依赖|npm|
|ieee754|1.2.1|间接依赖|npm|
|shebang-loader|0.0.1|间接依赖|npm|
|chnl|1.2.0|间接依赖|npm|
|safe-buffer|5.2.1|间接依赖|npm|
|https-proxy-agent|5.0.1|间接依赖|npm|
|lines-and-columns|1.2.4|间接依赖|npm|
|@malept/flatpak-bundler|0.4.0|间接依赖|npm|
|http-proxy-agent|5.0.0|间接依赖|npm|
|markdown-it-emoji|1.4.0|间接依赖|npm|
|schema-utils|3.3.0|间接依赖|npm|
|@electron/osx-sign|1.0.5|间接依赖|npm|
|@hapi/hoek|9.3.0|间接依赖|npm|
|shell-quote|1.8.1|间接依赖|npm|
|object.assign|4.1.4|间接依赖|npm|
|@webassemblyjs/helper-wasm-bytecode|1.11.6|间接依赖|npm|
|ora|5.4.1|间接依赖|npm|
|@webassemblyjs/wasm-edit|1.11.6|间接依赖|npm|
|@node-ipc/js-queue|2.0.3|间接依赖|npm|
|katex|0.16.8|间接依赖|npm|
|terser|5.19.2|间接依赖|npm|
|globalthis|1.0.3|间接依赖|npm|
|jsonfile|6.1.0|间接依赖|npm|
|jest-worker|27.5.1|间接依赖|npm|
|prismjs|1.29.0|间接依赖|npm|
|commander|10.0.1|间接依赖|npm|
|electron-to-chromium|1.4.496|间接依赖|npm|
|delayed-stream|1.0.0|间接依赖|npm|
|@vuepress/markdown|1.9.10|间接依赖|npm|
|source-map|0.6.1|间接依赖|npm|
|d3|7.8.5|间接依赖|npm|
|@tootallnate/once|2.0.0|间接依赖|npm|
|object-inspect|1.12.3|间接依赖|npm|
|app-builder-lib|24.6.3|间接依赖|npm|
|d3-transition|3.0.1|间接依赖|npm|
|buffer-equal|1.0.1|间接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|readdirp|3.6.0|间接依赖|npm|
|@webassemblyjs/helper-numbers|1.11.6|间接依赖|npm|
|@types/debug|4.1.8|间接依赖|npm|
|error-ex|1.3.2|间接依赖|npm|
|end-of-stream|1.4.4|间接依赖|npm|
|binary-search|1.3.6|间接依赖|npm|
|delaunator|5.0.0|间接依赖|npm|
|p-retry|4.6.2|间接依赖|npm|
|async-lock|1.4.0|间接依赖|npm|
|internal-slot|1.0.5|间接依赖|npm|
|@babel/code-frame|7.22.10|间接依赖|npm|
|chrome-trace-event|1.0.3|间接依赖|npm|
|@vue/compiler-core|3.3.4|间接依赖|npm|
|safe-array-concat|1.0.0|间接依赖|npm|
|is-interactive|1.0.0|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)