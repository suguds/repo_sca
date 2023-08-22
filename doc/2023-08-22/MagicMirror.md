# MichMich/MagicMirror安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1693694065433731072.svg)](https://www.murphysec.com/console/report/1693694065391788032/1693694065433731072)

仓库描述：MagicMirror² is an open source modular smart mirror platform. With a growing list of installable modules, the MagicMirror² allows you to convert your hallway or bathroom mirror into your personal assistant.

仓库地址：[https://github.com/MichMich/MagicMirror](https://github.com/MichMich/MagicMirror)

| star：17992 | watch：646 | fork：4038 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-20 22:43:40 | 许可证：MIT |
| 最近检测时间：2023-08-22 02:38:35 | 组件总数：663 | 漏洞总数：5 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google Chrome Mojo 安全漏洞|越界写入|[MPS-1k76-5oja](https://www.oscs1024.com/hd/MPS-1k76-5oja)|CVE-2023-3732|高危|
|colors.js  >1.4.0 DOS漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-19606](https://www.oscs1024.com/hd/MPS-2021-19606)|CVE-2021-23567|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|Google Chrome 安全漏洞|UAF|[MPS-6dbf-7lyp](https://www.oscs1024.com/hd/MPS-6dbf-7lyp)|CVE-2023-3730|高危|
|Google Chrome 安全漏洞|UAF|[MPS-yu0a-l27w](https://www.oscs1024.com/hd/MPS-yu0a-l27w)|CVE-2023-3728|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|electron|25.2.0|25.4.0|直接依赖|建议修复|C:0|H:3|M:0|L:0|
|colors|1.4.0||直接依赖|建议修复|C:0|H:1|M:0|L:0|
|semver|6.3.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|527|Low|
|BSD-2-Clause|15|Low|
|ISC|37|Low|
|BSD-3-Clause|29|Low|
|CC-BY-3.0|1|Low|
|Apache-2.0|17|Low|
|CC0-1.0|3|Low|
|Python-2.0|1|Low|
|0BSD|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|supports-hyperlinks|3.0.0|间接依赖|npm|
|estraverse|5.3.0|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|cssesc|3.0.0|间接依赖|npm|
|merge2|1.4.1|间接依赖|npm|
|colord|2.9.3|间接依赖|npm|
|moment|2.29.4|间接依赖|npm|
|on-finished|2.4.1|间接依赖|npm|
|responselike|2.0.1|间接依赖|npm|
|detect-newline|3.1.0|间接依赖|npm|
|nise|5.1.4|间接依赖|npm|
|babel-plugin-jest-hoist|29.5.0|间接依赖|npm|
|istanbul-lib-report|3.0.0|间接依赖|npm|
|asynckit|0.4.0|间接依赖|npm|
|has-flag|4.0.0|间接依赖|npm|
|spdx-exceptions|2.3.0|间接依赖|npm|
|@typescript-eslint/scope-manager|5.60.1|间接依赖|npm|
|find-up|5.0.0|间接依赖|npm|
|dir-glob|3.0.1|间接依赖|npm|
|array-differ|3.0.0|间接依赖|npm|
|call-bind|1.0.2|间接依赖|npm|
|for-each|0.3.3|间接依赖|npm|
|crypt|0.0.2|间接依赖|npm|
|delayed-stream|1.0.0|间接依赖|npm|
|@eslint-community/regexpp|4.4.0|间接依赖|npm|
|normalize-package-data|3.0.3|间接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|mathml-tag-names|2.1.3|间接依赖|npm|
|@babel/code-frame|7.22.5|间接依赖|npm|
|string.prototype.trimend|1.0.6|间接依赖|npm|
|@csstools/media-query-list-parser|2.1.1|间接依赖|npm|
|cookie-signature|1.0.6|间接依赖|npm|
|array-flatten|1.1.1|间接依赖|npm|
|mimic-fn|2.1.0|间接依赖|npm|
|has-tostringtag|1.0.0|间接依赖|npm|
|uglify-js|3.17.4|间接依赖|npm|
|@nodelib/fs.scandir|2.1.5|间接依赖|npm|
|tr46|4.1.1|间接依赖|npm|
|babel-preset-current-node-syntax|1.0.1|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|express|4.18.2|直接依赖|npm|
|fast-glob|3.2.12|间接依赖|npm|
|clarinet|0.12.5|间接依赖|npm|
|table|6.8.1|间接依赖|npm|
|jest-environment-node|29.5.0|间接依赖|npm|
|convert-source-map|2.0.0|间接依赖|npm|
|npm-run-path|4.0.1|间接依赖|npm|
|yargs|17.7.2|间接依赖|npm|
|array-buffer-byte-length|1.0.0|间接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|graceful-fs|4.2.11|间接依赖|npm|
|node-fetch|2.6.12|直接依赖|npm|
|merge-descriptors|1.0.1|间接依赖|npm|
|write-file-atomic|4.0.2|间接依赖|npm|
|object.values|1.1.6|间接依赖|npm|
|eslint-plugin-jest|27.2.2|直接依赖|npm|
|babel-jest|29.5.0|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|@babel/traverse|7.22.5|间接依赖|npm|
|https-proxy-agent|5.0.1|间接依赖|npm|
|flatted|3.2.7|间接依赖|npm|
|@jest/console|29.5.0|间接依赖|npm|
|is-generator-fn|2.1.0|间接依赖|npm|
|abab|2.0.6|间接依赖|npm|
|is-buffer|1.1.6|间接依赖|npm|
|@babel/plugin-syntax-import-meta|7.10.4|间接依赖|npm|
|@types/yargs|17.0.24|间接依赖|npm|
|object.assign|4.1.4|间接依赖|npm|
|jest-leak-detector|29.5.0|间接依赖|npm|
|socket.io-parser|4.2.4|间接依赖|npm|
|@types/istanbul-lib-coverage|2.0.4|间接依赖|npm|
|suncalc|1.9.0|直接依赖|npm|
|cssstyle|3.0.0|间接依赖|npm|
|colors|1.4.0|直接依赖|npm|
|rrweb-cssom|0.6.0|间接依赖|npm|
|@babel/plugin-syntax-nullish-coalescing-operator|7.8.3|间接依赖|npm|
|ansi-escapes|4.3.2|间接依赖|npm|
|esquery|1.5.0|间接依赖|npm|
|forwarded|0.2.0|间接依赖|npm|
|is-boolean-object|1.1.2|间接依赖|npm|
|end-of-stream|1.4.4|间接依赖|npm|
|html-escaper|2.0.2|间接依赖|npm|
|symbol-tree|3.2.4|间接依赖|npm|
|pump|3.0.0|间接依赖|npm|
|react-is|18.2.0|间接依赖|npm|
|progress|2.0.3|间接依赖|npm|
|module-alias|2.2.3|直接依赖|npm|
|css-functions-list|3.1.0|间接依赖|npm|
|@types/minimatch|3.0.5|间接依赖|npm|
|@typescript-eslint/types|5.60.1|间接依赖|npm|
|pure-rand|6.0.2|间接依赖|npm|
|rimraf|3.0.2|间接依赖|npm|
|whatwg-url|12.0.1|间接依赖|npm|
|lru-cache|5.1.1|间接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|@jest/reporters|29.5.0|间接依赖|npm|
|walker|1.0.8|间接依赖|npm|
|proxy-addr|2.0.7|间接依赖|npm|
|min-indent|1.0.1|间接依赖|npm|
|fd-slicer|1.1.0|间接依赖|npm|
|tmpl|1.0.5|间接依赖|npm|
|stack-utils|2.0.6|间接依赖|npm|
|shebang-command|2.0.0|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|http-cache-semantics|4.1.1|间接依赖|npm|
|resolve-alpn|1.2.1|间接依赖|npm|
|@babel/plugin-syntax-top-level-await|7.14.5|间接依赖|npm|
|punycode|2.3.0|间接依赖|npm|
|import-lazy|4.0.0|间接依赖|npm|
|normalize-url|6.1.0|间接依赖|npm|
|p-limit|3.1.0|间接依赖|npm|
|content-type|1.0.5|间接依赖|npm|
|@tootallnate/once|2.0.0|间接依赖|npm|
|cosmiconfig|8.2.0|间接依赖|npm|
|@types/babel__core|7.20.1|间接依赖|npm|
|@eslint/eslintrc|2.0.3|间接依赖|npm|
|is-path-inside|3.0.3|间接依赖|npm|
|is-regex|1.1.4|间接依赖|npm|
|@babel/plugin-syntax-optional-chaining|7.8.3|间接依赖|npm|
|raw-body|2.5.1|间接依赖|npm|
|@jest/test-sequencer|29.5.0|间接依赖|npm|
|diff-sequences|29.4.3|间接依赖|npm|
|unpipe|1.0.0|间接依赖|npm|
|uuid|9.0.0|间接依赖|npm|
|path-type|4.0.0|间接依赖|npm|
|postcss-resolve-nested-selector|0.1.1|间接依赖|npm|
|char-regex|1.0.2|间接依赖|npm|
|lowercase-keys|2.0.0|间接依赖|npm|
|json-parse-even-better-errors|2.3.1|间接依赖|npm|
|ip6|0.2.10|间接依赖|npm|
|array-includes|3.1.6|间接依赖|npm|
|@jest/source-map|29.4.3|间接依赖|npm|
|picocolors|1.0.0|间接依赖|npm|
|babel-preset-jest|29.5.0|间接依赖|npm|
|@istanbuljs/load-nyc-config|1.1.0|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|which|2.0.2|间接依赖|npm|
|typescript|5.1.6|直接依赖|npm|
|eslint-import-resolver-node|0.3.7|间接依赖|npm|
|multimatch|4.0.0|间接依赖|npm|
|@babel/plugin-syntax-typescript|7.22.5|间接依赖|npm|
|indent-string|4.0.0|间接依赖|npm|
|@types/babel__template|7.4.1|间接依赖|npm|
|levn|0.4.1|间接依赖|npm|
|keyv|4.5.2|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|gopd|1.0.1|间接依赖|npm|
|is-number|7.0.0|间接依赖|npm|
|p-locate|5.0.0|间接依赖|npm|
|global-agent|3.0.0|间接依赖|npm|
|shebang-regex|3.0.0|间接依赖|npm|
|@sindresorhus/is|4.6.0|间接依赖|npm|
|boolean|3.2.0|间接依赖|npm|
|decamelize|1.2.0|间接依赖|npm|
|resolve-cwd|3.0.0|间接依赖|npm|
|file-entry-cache|6.0.1|间接依赖|npm|
|acorn-jsx|5.3.2|间接依赖|npm|
|strip-ansi|6.0.1|间接依赖|npm|
|arrify|2.0.1|间接依赖|npm|
|got|11.8.6|间接依赖|npm|
|path-key|3.1.1|间接依赖|npm|
|js-sha256|0.9.0|间接依赖|npm|
|mdn-data|2.0.30|间接依赖|npm|
|destroy|1.2.0|间接依赖|npm|
|serve-static|1.15.0|间接依赖|npm|
|cliui|8.0.1|间接依赖|npm|
|ws|8.13.0|间接依赖|npm|
|encodeurl|1.0.2|间接依赖|npm|
|@types/babel__traverse|7.20.1|间接依赖|npm|
|@eslint-community/eslint-utils|4.3.0|间接依赖|npm|
|html-encoding-sniffer|3.0.0|间接依赖|npm|
|utils-merge|1.0.1|间接依赖|npm|
|resolve.exports|2.0.2|间接依赖|npm|
|ee-first|1.1.1|间接依赖|npm|
|@jest/schemas|29.4.3|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|kind-of|6.0.3|间接依赖|npm|
|flat-cache|3.0.4|间接依赖|npm|
|import-local|3.1.0|间接依赖|npm|
|@babel/core|7.22.5|间接依赖|npm|
|is-string|1.0.7|间接依赖|npm|
|form-data|4.0.0|间接依赖|npm|
|make-dir|3.1.0|间接依赖|npm|
|matcher|3.0.0|间接依赖|npm|
|@jest/core|29.5.0|间接依赖|npm|
|nwsapi|2.2.5|间接依赖|npm|
|gensync|1.0.0-beta.2|间接依赖|npm|
|postcss-media-query-parser|0.2.3|间接依赖|npm|
|style-search|0.1.0|间接依赖|npm|
|@nodelib/fs.stat|2.0.5|间接依赖|npm|
|@babel/parser|7.22.5|间接依赖|npm|
|p-try|2.2.0|直接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|@types/normalize-package-data|2.4.1|间接依赖|npm|
|lodash.merge|4.6.2|间接依赖|npm|
|internal-slot|1.0.5|间接依赖|npm|
|@jest/types|29.5.0|间接依赖|npm|
|is-core-module|2.12.1|间接依赖|npm|
|signal-exit|3.0.7|间接依赖|npm|
|@sinonjs/fake-timers|10.3.0|间接依赖|npm|
|object-keys|1.1.1|间接依赖|npm|
|is-bigint|1.0.4|间接依赖|npm|
|@babel/helper-function-name|7.22.5|间接依赖|npm|
|eslint-plugin-import|2.27.5|直接依赖|npm|
|eslint-scope|7.2.0|间接依赖|npm|
|@jest/fake-timers|29.5.0|间接依赖|npm|
|semver-compare|1.0.0|间接依赖|npm|
|color-convert|2.0.1|间接依赖|npm|
|@eslint/js|8.43.0|间接依赖|npm|
|defer-to-connect|2.0.1|间接依赖|npm|
|unbox-primitive|1.0.2|间接依赖|npm|
|known-css-properties|0.27.0|间接依赖|npm|
|luxon|1.28.1|间接依赖|npm|
|depd|2.0.0|间接依赖|npm|
|@types/semver|7.5.0|间接依赖|npm|
|@babel/plugin-syntax-object-rest-spread|7.8.3|间接依赖|npm|
|universalify|0.1.2|间接依赖|npm|
|stylelint|15.9.0|直接依赖|npm|
|ini|1.3.8|间接依赖|npm|
|md5|2.3.0|间接依赖|npm|
|has-bigints|1.0.2|间接依赖|npm|
|sumchecker|3.0.1|间接依赖|npm|
|@babel/plugin-syntax-json-strings|7.8.3|间接依赖|npm|
|minimist|1.2.8|间接依赖|npm|
|is-array-buffer|3.0.2|间接依赖|npm|
|read-pkg|5.2.0|间接依赖|npm|
|decompress-response|6.0.0|间接依赖|npm|
|xml-name-validator|4.0.0|间接依赖|npm|
|acorn|8.9.0|间接依赖|npm|
|html-tags|3.3.1|间接依赖|npm|
|@babel/helper-string-parser|7.22.5|间接依赖|npm|
|@jest/environment|29.5.0|间接依赖|npm|
|@csstools/css-tokenizer|2.1.1|间接依赖|npm|
|saxes|6.0.0|间接依赖|npm|
|@jest/expect|29.5.0|间接依赖|npm|
|ajv|6.12.6|间接依赖|npm|
|text-table|0.2.0|间接依赖|npm|
|@types/yargs-parser|21.0.0|间接依赖|npm|
|@babel/plugin-syntax-class-properties|7.12.13|间接依赖|npm|
|@jridgewell/trace-mapping|0.3.18|间接依赖|npm|
|natural-compare|1.4.0|间接依赖|npm|
|error-ex|1.3.2|间接依赖|npm|
|@babel/plugin-syntax-async-generators|7.8.4|间接依赖|npm|
|@types/json-schema|7.0.12|间接依赖|npm|
|@babel/types|7.22.5|间接依赖|npm|
|w3c-xmlserializer|4.0.0|间接依赖|npm|
|http-errors|2.0.0|间接依赖|npm|
|webidl-conversions|7.0.0|间接依赖|npm|
|source-map-support|0.5.13|间接依赖|npm|
|svg-tags|1.0.0|间接依赖|npm|
|cross-spawn|7.0.3|间接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|yocto-queue|0.1.0|间接依赖|npm|
|decamelize-keys|1.1.1|间接依赖|npm|
|http2-wrapper|1.0.3|间接依赖|npm|
|nanoid|3.3.6|间接依赖|npm|
|v8-to-istanbul|9.1.0|间接依赖|npm|
|negotiator|0.6.3|间接依赖|npm|
|@szmarczak/http-timer|4.0.6|间接依赖|npm|
|pkg-dir|4.2.0|间接依赖|npm|
|@aashutoshrathi/word-wrap|1.2.6|间接依赖|npm|
|run-parallel|1.2.0|间接依赖|npm|
|get-stream|5.2.0|间接依赖|npm|
|fastq|1.15.0|间接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|which-boxed-primitive|1.0.2|间接依赖|npm|
|map-obj|4.3.0|间接依赖|npm|
|js-sha512|0.8.0|间接依赖|npm|
|onetime|5.1.2|间接依赖|npm|
|@types/cacheable-request|6.0.3|间接依赖|npm|
|base64id|2.0.0|间接依赖|npm|
|requires-port|1.0.0|间接依赖|npm|
|es-set-tostringtag|2.0.1|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|spdx-correct|3.2.0|间接依赖|npm|
|engine.io|6.5.1|间接依赖|npm|
|redent|3.0.0|间接依赖|npm|
|camelcase|5.3.1|间接依赖|npm|
|color-name|1.1.4|间接依赖|npm|
|accepts|1.3.8|间接依赖|npm|
|resolve-from|4.0.0|间接依赖|npm|
|is-arrayish|0.2.1|间接依赖|npm|
|esutils|2.0.3|间接依赖|npm|
|cjs-module-lexer|1.2.3|间接依赖|npm|
|get-intrinsic|1.2.1|间接依赖|npm|
|css-tree|2.3.1|间接依赖|npm|
|url-parse|1.5.10|间接依赖|npm|
|playwright-core|1.35.1|间接依赖|npm|
|istanbul-lib-source-maps|4.0.1|间接依赖|npm|
|expect|29.5.0|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|jest-regex-util|29.4.3|间接依赖|npm|
|micromatch|4.0.5|间接依赖|npm|
|global-prefix|3.0.0|间接依赖|npm|
|deepmerge|4.3.1|间接依赖|npm|
|human-signals|2.1.0|间接依赖|npm|
|@types/stack-utils|2.0.1|间接依赖|npm|
|mime|1.6.0|间接依赖|npm|
|@humanwhocodes/config-array|0.11.10|间接依赖|npm|
|ipaddr.js|1.9.1|间接依赖|npm|
|is-potential-custom-element-name|1.0.1|间接依赖|npm|
|json-stringify-safe|5.0.1|间接依赖|npm|
|@jest/test-result|29.5.0|间接依赖|npm|
|handlebars|4.7.7|间接依赖|npm|
|agent-base|6.0.2|间接依赖|npm|
|commander|4.1.1|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|esrecurse|4.3.0|间接依赖|npm|
|quick-lru|5.1.1|间接依赖|npm|
|which-typed-array|1.1.9|间接依赖|npm|
|fastest-levenshtein|1.0.16|间接依赖|npm|
|json5|2.2.3|间接依赖|npm|
|jest-resolve-dependencies|29.5.0|间接依赖|npm|
|type-fest|0.20.2|间接依赖|npm|
|hosted-git-info|4.1.0|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|@es-joy/jsdoccomment|0.39.4|间接依赖|npm|
|jest-circus|29.5.0|间接依赖|npm|
|jest-get-type|29.4.3|间接依赖|npm|
|sinon|15.2.0|直接依赖|npm|
|functions-have-names|1.2.3|间接依赖|npm|
|exit|0.1.2|间接依赖|npm|
|@typescript-eslint/utils|5.60.1|间接依赖|npm|
|yauzl|2.10.0|间接依赖|npm|
|env-paths|2.2.1|间接依赖|npm|
|string.prototype.trimstart|1.0.6|间接依赖|npm|
|@babel/helper-module-imports|7.22.5|间接依赖|npm|
|escape-html|1.0.3|间接依赖|npm|
|vary|1.1.2|间接依赖|npm|
|stylelint-prettier|3.0.0|直接依赖|npm|
|ci-info|3.8.0|间接依赖|npm|
|jest-runner|29.5.0|间接依赖|npm|
|global-modules|2.0.0|间接依赖|npm|
|ignore|5.2.4|间接依赖|npm|
|jsesc|2.5.2|间接依赖|npm|
|slash|3.0.0|间接依赖|npm|
|es-abstract|1.21.2|间接依赖|npm|
|array.prototype.flatmap|1.3.1|间接依赖|npm|
|extract-zip|2.0.1|间接依赖|npm|
|eslint|8.43.0|直接依赖|npm|
|@typescript-eslint/typescript-estree|5.60.1|间接依赖|npm|
|@types/cors|2.8.13|间接依赖|npm|
|pretty-format|29.5.0|间接依赖|npm|
|are-docs-informative|0.0.2|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|is-symbol|1.0.4|间接依赖|npm|
|body-parser|1.20.1|间接依赖|npm|
|querystringify|2.2.0|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|sisteransi|1.0.5|间接依赖|npm|
|prompts|2.4.2|间接依赖|npm|
|jsdoc-type-pratt-parser|4.0.0|间接依赖|npm|
|whatwg-mimetype|3.0.0|间接依赖|npm|
|jest-runtime|29.5.0|间接依赖|npm|
|range-parser|1.2.1|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|has-property-descriptors|1.0.0|间接依赖|npm|
|jsdom|22.1.0|直接依赖|npm|
|@nodelib/fs.walk|1.2.8|间接依赖|npm|
|prettier-linter-helpers|1.0.0|间接依赖|npm|
|jest-snapshot|29.5.0|间接依赖|npm|
|supports-preserve-symlinks-flag|1.0.0|间接依赖|npm|
|is-negative-zero|2.0.2|间接依赖|npm|
|comment-parser|1.3.1|间接依赖|npm|
|@jridgewell/resolve-uri|3.1.0|间接依赖|npm|
|@types/istanbul-reports|3.0.1|间接依赖|npm|
|@types/babel__generator|7.6.4|间接依赖|npm|
|roarr|2.15.4|间接依赖|npm|
|trim-newlines|3.0.1|间接依赖|npm|
|@humanwhocodes/module-importer|1.0.1|间接依赖|npm|
|buffer-crc32|0.2.13|间接依赖|npm|
|string-width|4.2.3|间接依赖|npm|
|neo-async|2.6.2|间接依赖|npm|
|express-basic-auth|1.2.1|直接依赖|npm|
|mime-types|2.1.35|间接依赖|npm|
|is-typed-array|1.1.10|间接依赖|npm|
|is-weakref|1.0.2|间接依赖|npm|
|meow|9.0.0|间接依赖|npm|
|camelcase-keys|6.2.2|间接依赖|npm|
|electron|25.2.0|直接依赖|npm|
|wordwrap|1.0.0|间接依赖|npm|
|path-to-regexp|0.1.7|间接依赖|npm|
|@jest/transform|29.5.0|间接依赖|npm|
|replace-last|1.2.6|间接依赖|npm|
|http-proxy-agent|5.0.0|间接依赖|npm|
|collect-v8-coverage|1.0.1|间接依赖|npm|
|@babel/helper-validator-identifier|7.22.5|间接依赖|npm|
|base-64|0.1.0|间接依赖|npm|
|content-disposition|0.5.4|间接依赖|npm|
|send|0.18.0|间接依赖|npm|
|parent-module|1.0.1|间接依赖|npm|
|@socket.io/component-emitter|3.1.0|间接依赖|npm|
|combined-stream|1.0.8|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|finalhandler|1.2.0|间接依赖|npm|
|@types/http-cache-semantics|4.0.1|间接依赖|npm|
|@ampproject/remapping|2.2.1|间接依赖|npm|
|@types/json5|0.0.29|间接依赖|npm|
|has-proto|1.0.1|间接依赖|npm|
|@babel/helper-simple-access|7.22.5|间接依赖|npm|
|regexp.prototype.flags|1.5.0|间接依赖|npm|
|es-shim-unscopables|1.0.0|间接依赖|npm|
|slice-ansi|4.0.0|间接依赖|npm|
|bser|2.1.1|间接依赖|npm|
|picomatch|2.3.1|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|escape-string-regexp|4.0.0|间接依赖|npm|
|array.prototype.flat|1.3.1|间接依赖|npm|
|just-extend|4.2.1|间接依赖|npm|
|fast-levenshtein|2.0.6|间接依赖|npm|
|globjoin|0.1.4|间接依赖|npm|
|@csstools/selector-specificity|2.2.0|间接依赖|npm|
|digest-fetch|2.0.3|直接依赖|npm|
|deep-is|0.1.4|间接依赖|npm|
|entities|4.5.0|间接依赖|npm|
|ansi-styles|4.3.0|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|clone-response|1.0.3|间接依赖|npm|
|@babel/plugin-syntax-logical-assignment-operators|7.10.4|间接依赖|npm|
|fb-watchman|2.0.2|间接依赖|npm|
|p-cancelable|2.1.1|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|function.prototype.name|1.1.5|间接依赖|npm|
|node-int64|0.4.0|间接依赖|npm|
|@csstools/css-parser-algorithms|2.2.0|间接依赖|npm|
|is-builtin-module|3.2.1|间接依赖|npm|
|jest-worker|29.5.0|间接依赖|npm|
|supports-color|7.2.0|间接依赖|npm|
|@types/istanbul-lib-report|3.0.0|间接依赖|npm|
|@babel/plugin-syntax-numeric-separator|7.10.4|间接依赖|npm|
|is-shared-array-buffer|1.0.2|间接依赖|npm|
|semver|6.3.0|间接依赖|npm|
|optionator|0.9.3|间接依赖|npm|
|strip-json-comments|3.1.1|间接依赖|npm|
|argparse|2.0.1|间接依赖|npm|
|globals|13.20.0|间接依赖|npm|
|@babel/helper-split-export-declaration|7.22.5|间接依赖|npm|
|lodash.truncate|4.4.2|间接依赖|npm|
|jest-haste-map|29.5.0|间接依赖|npm|
|validate-npm-package-license|3.0.4|间接依赖|npm|
|jest-mock|29.5.0|间接依赖|npm|
|strip-indent|3.0.0|间接依赖|npm|
|serialize-error|7.0.1|间接依赖|npm|
|graphemer|1.4.0|间接依赖|npm|
|eslint-visitor-keys|3.4.1|间接依赖|npm|
|typed-array-length|1.0.4|间接依赖|npm|
|media-typer|0.3.0|间接依赖|npm|
|data-urls|4.0.0|间接依赖|npm|
|debug|4.3.4|间接依赖|npm|
|xmlchars|2.2.0|间接依赖|npm|
|@sinonjs/text-encoding|0.7.2|间接依赖|npm|
|statuses|2.0.1|间接依赖|npm|
|playwright|1.35.1|直接依赖|npm|
|@babel/plugin-syntax-jsx|7.22.5|间接依赖|npm|
|range_check|2.0.4|间接依赖|npm|
|@babel/helper-validator-option|7.22.5|间接依赖|npm|
|@types/prettier|2.7.3|间接依赖|npm|
|json-buffer|3.0.1|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|bytes|3.1.2|间接依赖|npm|
|@babel/highlight|7.22.5|间接依赖|npm|
|jest-util|29.5.0|间接依赖|npm|
|psl|1.9.0|间接依赖|npm|
|string-length|4.0.2|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|postcss-selector-parser|6.0.13|间接依赖|npm|
|jest|29.5.0|直接依赖|npm|
|minimist-options|4.1.0|间接依赖|npm|
|etag|1.8.1|间接依赖|npm|
|@types/yauzl|2.10.0|间接依赖|npm|
|fs-extra|8.1.0|间接依赖|npm|
|globby|11.1.0|间接依赖|npm|
|co|4.6.0|间接依赖|npm|
|is-date-object|1.0.5|间接依赖|npm|
|cookie|0.5.0|间接依赖|npm|
|cors|2.8.5|间接依赖|npm|
|stylelint-config-standard|33.0.0|直接依赖|npm|
|console-stamp|3.1.1|直接依赖|npm|
|has-symbols|1.0.3|间接依赖|npm|
|test-exclude|6.0.0|间接依赖|npm|
|spdx-expression-parse|3.0.1|间接依赖|npm|
|@istanbuljs/schema|0.1.3|间接依赖|npm|
|import-fresh|3.3.0|间接依赖|npm|
|buffer-from|1.1.2|间接依赖|npm|
|jest-config|29.5.0|间接依赖|npm|
|get-symbol-description|1.0.0|间接依赖|npm|
|fast-diff|1.3.0|间接依赖|npm|
|jest-resolve|29.5.0|间接依赖|npm|
|hard-rejection|2.1.0|间接依赖|npm|
|setprototypeof|1.2.0|间接依赖|npm|
|string.prototype.trim|1.2.7|间接依赖|npm|
|jest-changed-files|29.5.0|间接依赖|npm|
|emittery|0.13.1|间接依赖|npm|
|jest-message-util|29.5.0|间接依赖|npm|
|jest-validate|29.5.0|间接依赖|npm|
|eslint-module-utils|2.8.0|间接依赖|npm|
|axios|1.4.0|间接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|tslib|1.14.1|间接依赖|npm|
|source-map-js|1.0.2|间接依赖|npm|
|express-ipfilter|1.3.1|直接依赖|npm|
|eslint-plugin-prettier|4.2.1|直接依赖|npm|
|eslint-config-prettier|8.8.0|直接依赖|npm|
|require-from-string|2.0.2|直接依赖|npm|
|callsites|3.1.0|间接依赖|npm|
|jest-each|29.5.0|间接依赖|npm|
|object-inspect|1.12.3|间接依赖|npm|
|define-properties|1.2.0|间接依赖|npm|
|@babel/helper-module-transforms|7.22.5|间接依赖|npm|
|stylelint-config-recommended|12.0.0|间接依赖|npm|
|js-yaml|4.1.0|间接依赖|npm|
|pend|1.2.0|间接依赖|npm|
|envsub|4.1.0|直接依赖|npm|
|lodash.get|4.4.2|间接依赖|npm|
|sprintf-js|1.1.2|间接依赖|npm|
|@babel/plugin-syntax-bigint|7.8.3|间接依赖|npm|
|postcss-value-parser|4.2.0|间接依赖|npm|
|leven|3.1.0|间接依赖|npm|
|get-package-type|0.1.0|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|methods|1.1.2|间接依赖|npm|
|@types/minimist|1.2.2|间接依赖|npm|
|type-check|0.4.0|间接依赖|npm|
|dedent|0.7.0|间接依赖|npm|
|pirates|4.0.6|间接依赖|npm|
|emoji-regex|8.0.0|间接依赖|npm|
|cacheable-lookup|5.0.4|间接依赖|npm|
|y18n|5.0.8|间接依赖|npm|
|read-pkg-up|7.0.1|间接依赖|npm|
|globalthis|1.0.3|间接依赖|npm|
|husky|8.0.3|直接依赖|npm|
|bluebird|3.7.2|间接依赖|npm|
|@humanwhocodes/object-schema|1.2.1|间接依赖|npm|
|rrule|2.6.4|间接依赖|npm|
|is-glob|4.0.3|间接依赖|npm|
|yallist|3.1.1|间接依赖|npm|
|es-to-primitive|1.2.1|间接依赖|npm|
|follow-redirects|1.15.2|间接依赖|npm|
|spdx-license-ids|3.0.13|间接依赖|npm|
|@jridgewell/gen-mapping|0.3.3|间接依赖|npm|
|babel-plugin-istanbul|6.1.1|间接依赖|npm|
|proxy-from-env|1.1.0|间接依赖|npm|
|is-stream|2.0.1|间接依赖|npm|
|locate-path|6.0.0|间接依赖|npm|
|istanbul-reports|3.1.5|间接依赖|npm|
|moment-timezone|0.5.43|间接依赖|npm|
|mimic-response|1.0.1|间接依赖|npm|
|@types/responselike|1.0.0|间接依赖|npm|
|strip-bom|4.0.0|间接依赖|npm|
|json-stable-stringify-without-jsonify|1.0.1|间接依赖|npm|
|esprima|4.0.1|直接依赖|npm|
|@babel/helper-compilation-targets|7.22.5|间接依赖|npm|
|kleur|3.0.3|间接依赖|npm|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|jest-matcher-utils|29.5.0|间接依赖|npm|
|is-plain-obj|1.1.0|间接依赖|npm|
|@typescript-eslint/visitor-keys|5.60.1|间接依赖|npm|
|tsconfig-paths|3.14.2|间接依赖|npm|
|is-plain-object|5.0.0|间接依赖|npm|
|socket.io|4.7.1|直接依赖|npm|
|@jest/globals|29.5.0|间接依赖|npm|
|browserslist|4.21.9|间接依赖|npm|
|eslint-plugin-jsdoc|46.4.2|直接依赖|npm|
|parseurl|1.3.3|间接依赖|npm|
|cacheable-request|7.0.4|间接依赖|npm|
|queue-microtask|1.2.3|间接依赖|npm|
|postcss|8.4.24|间接依赖|npm|
|espree|9.5.2|间接依赖|npm|
|sax|1.2.4|间接依赖|npm|
|jest-docblock|29.4.3|间接依赖|npm|
|@sinonjs/samsam|8.0.0|间接依赖|npm|
|path-exists|4.0.0|间接依赖|npm|
|@types/keyv|3.1.4|间接依赖|npm|
|prettier|2.8.8|直接依赖|npm|
|toidentifier|1.0.1|间接依赖|npm|
|@babel/helper-hoist-variables|7.22.5|间接依赖|npm|
|doctrine|3.0.0|间接依赖|npm|
|engine.io-parser|5.1.0|间接依赖|npm|
|@babel/template|7.22.5|间接依赖|npm|
|side-channel|1.0.4|间接依赖|npm|
|@babel/helpers|7.22.5|间接依赖|npm|
|reusify|1.0.4|间接依赖|npm|
|yargs-parser|20.2.9|间接依赖|npm|
|@sinclair/typebox|0.25.24|间接依赖|npm|
|string.prototype.matchall|4.0.8|间接依赖|npm|
|istanbul-lib-coverage|3.2.0|间接依赖|npm|
|type-is|1.6.18|间接依赖|npm|
|ip|1.1.8|间接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|@types/cookie|0.4.1|间接依赖|npm|
|pretty-quick|3.1.3|直接依赖|npm|
|glob|7.2.3|间接依赖|npm|
|anymatch|3.1.3|间接依赖|npm|
|wrap-ansi|7.0.0|间接依赖|npm|
|jest-watcher|29.5.0|间接依赖|npm|
|fsevents|2.3.2|间接依赖|npm|
|postcss-safe-parser|6.0.0|间接依赖|npm|
|whatwg-encoding|2.0.0|间接依赖|npm|
|glob-parent|6.0.2|间接依赖|npm|
|helmet|7.0.0|直接依赖|npm|
|available-typed-arrays|1.0.5|间接依赖|npm|
|astral-regex|2.0.0|间接依赖|npm|
|decimal.js|10.4.3|间接依赖|npm|
|type-detect|4.0.8|间接依赖|npm|
|@babel/helper-environment-visitor|7.22.5|间接依赖|npm|
|safe-buffer|5.2.1|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|@babel/compat-data|7.22.5|间接依赖|npm|
|iconv-lite|0.6.3|间接依赖|npm|
|array-union|2.1.0|间接依赖|npm|
|domexception|4.0.0|间接依赖|npm|
|source-map|0.6.1|间接依赖|npm|
|@types/graceful-fs|4.1.6|间接依赖|npm|
|chalk|4.1.2|间接依赖|npm|
|socket.io-adapter|2.5.2|间接依赖|npm|
|@bcoe/v8-coverage|0.2.3|间接依赖|npm|
|charenc|0.0.2|间接依赖|npm|
|resolve|1.22.2|间接依赖|npm|
|merge-stream|2.0.0|间接依赖|npm|
|prelude-ls|1.2.1|间接依赖|npm|
|detect-node|2.1.0|间接依赖|npm|
|istanbul-lib-instrument|5.2.1|间接依赖|npm|
|qs|6.11.0|间接依赖|npm|
|makeerror|1.0.12|间接依赖|npm|
|@types/node|18.16.18|间接依赖|npm|
|is-number-object|1.0.7|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|tough-cookie|4.1.3|间接依赖|npm|
|basic-auth|2.0.1|间接依赖|npm|
|strip-final-newline|2.0.0|间接依赖|npm|
|@jridgewell/set-array|1.1.2|间接依赖|npm|
|es6-error|4.1.1|间接依赖|npm|
|@babel/plugin-syntax-optional-catch-binding|7.8.3|间接依赖|npm|
|isarray|0.0.1|直接依赖|npm|
|fresh|0.5.2|间接依赖|npm|
|jest-cli|29.5.0|间接依赖|npm|
|to-fast-properties|2.0.0|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|@electron/get|2.0.2|间接依赖|npm|
|parse-json|5.2.0|间接依赖|npm|
|jsonfile|4.0.0|间接依赖|npm|
|feedme|2.0.2|直接依赖|npm|
|tsutils|3.21.0|间接依赖|npm|
|parse5|7.1.2|间接依赖|npm|
|jest-diff|29.5.0|间接依赖|npm|
|dateformat|4.6.3|间接依赖|npm|
|safe-regex-test|1.0.0|间接依赖|npm|
|@babel/generator|7.22.5|间接依赖|npm|
|node-ical|0.16.1|直接依赖|npm|
|imurmurhash|0.1.4|间接依赖|npm|
|mri|1.2.0|间接依赖|npm|
|jest-pnp-resolver|1.2.3|间接依赖|npm|
|@babel/helper-plugin-utils|7.22.5|间接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.15|间接依赖|npm|
|@jest/expect-utils|29.5.0|间接依赖|npm|
|@sinonjs/commons|3.0.0|间接依赖|npm|
|execa|5.1.1|间接依赖|npm|
|builtin-modules|3.3.0|间接依赖|npm|
|lines-and-columns|1.2.4|间接依赖|npm|
|diff|4.0.2|间接依赖|npm|
|is-callable|1.2.7|间接依赖|npm|
|mime-db|1.52.0|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)