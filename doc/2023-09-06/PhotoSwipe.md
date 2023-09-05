# dimsemenov/PhotoSwipe安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699129365237465088.svg)](https://www.murphysec.com/console/report/1699129364486684672/1699129365237465088)

仓库描述：JavaScript image gallery for mobile and desktop, modular, framework independent

仓库地址：[https://github.com/dimsemenov/PhotoSwipe](https://github.com/dimsemenov/PhotoSwipe)

| star：23164 | watch：539 | fork：3367 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-04 13:55:00 | 许可证：MIT |
| 最近检测时间：2023-09-06 02:36:27 | 组件总数：283 | 漏洞总数：4 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|terser 安全漏洞|ReDoS|[MPS-2022-5145](https://www.oscs1024.com/hd/MPS-2022-5145)|CVE-2022-25858|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|Tauri 原型污染漏洞|原型污染|[MPS-2022-65568](https://www.oscs1024.com/hd/MPS-2022-65568)|CVE-2022-46175|高危|
|word-wrap 安全漏洞|ReDoS|[MPS-2023-5109](https://www.oscs1024.com/hd/MPS-2023-5109)|CVE-2023-26115|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|json5|2.2.1|2.2.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|terser|5.7.0|5.14.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|word-wrap|1.2.3|1.2.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|semver|5.7.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|229|Low|
|ISC|26|Low|
|Apache-2.0|8|Low|
|BSD-2-Clause|8|Low|
|BSD-3-Clause|4|Low|
|Python-2.0|1|Low|
|CC0-1.0|1|Low|
|CC-BY-3.0|1|Low|
|0BSD|1|Low|
|CC-BY-4.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|through2|2.0.5|间接依赖|npm|
|micromatch|4.0.4|间接依赖|npm|
|strip-bom|3.0.0|间接依赖|npm|
|parent-module|1.0.1|间接依赖|npm|
|reusify|1.0.4|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|is-negative-zero|2.0.2|间接依赖|npm|
|merge2|1.4.1|间接依赖|npm|
|file-entry-cache|6.0.1|间接依赖|npm|
|run-parallel|1.2.0|间接依赖|npm|
|string-width|4.2.2|间接依赖|npm|
|@babel/plugin-syntax-class-properties|7.12.13|直接依赖|npm|
|p-limit|2.3.0|间接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|unbox-primitive|1.0.2|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|eslint-plugin-import|2.26.0|直接依赖|npm|
|is-fullwidth-code-point|2.0.0|间接依赖|npm|
|is-number|7.0.0|间接依赖|npm|
|gensync|1.0.0-beta.2|间接依赖|npm|
|natural-compare|1.4.0|间接依赖|npm|
|flatted|3.1.1|间接依赖|npm|
|@babel/types|7.22.11|间接依赖|npm|
|type-fest|0.20.2|间接依赖|npm|
|has-symbols|1.0.3|间接依赖|npm|
|resolve-from|4.0.0|间接依赖|npm|
|object.entries|1.1.5|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|fast-levenshtein|2.0.6|间接依赖|npm|
|@ampproject/remapping|2.2.0|间接依赖|npm|
|has-tostringtag|1.0.0|间接依赖|npm|
|cliui|5.0.0|间接依赖|npm|
|@babel/helper-function-name|7.17.9|间接依赖|npm|
|lodash.debounce|4.0.8|间接依赖|npm|
|internal-slot|1.0.3|间接依赖|npm|
|@babel/traverse|7.18.0|间接依赖|npm|
|array-union|2.1.0|间接依赖|npm|
|source-map-support|0.5.19|间接依赖|npm|
|balanced-match|1.0.0|间接依赖|npm|
|process-nextick-args|2.0.0|间接依赖|npm|
|define-properties|1.1.4|间接依赖|npm|
|to-fast-properties|2.0.0|间接依赖|npm|
|set-blocking|2.0.0|间接依赖|npm|
|@eslint/eslintrc|1.3.0|间接依赖|npm|
|@types/glob|7.1.3|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.13|间接依赖|npm|
|call-bind|1.0.2|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|acorn|8.7.1|间接依赖|npm|
|es-shim-unscopables|1.0.0|间接依赖|npm|
|hosted-git-info|2.8.9|间接依赖|npm|
|eslint-utils|3.0.0|间接依赖|npm|
|binary-extensions|2.2.0|间接依赖|npm|
|y18n|4.0.3|间接依赖|npm|
|@babel/generator|7.18.0|间接依赖|npm|
|is-core-module|2.9.0|间接依赖|npm|
|eslint-module-utils|2.7.3|间接依赖|npm|
|chokidar-cli|3.0.0|直接依赖|npm|
|array.prototype.flat|1.3.0|间接依赖|npm|
|function.prototype.name|1.1.5|间接依赖|npm|
|json-parse-even-better-errors|2.3.1|间接依赖|npm|
|picocolors|1.0.0|间接依赖|npm|
|colorette|1.2.2|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|@jridgewell/resolve-uri|3.0.7|间接依赖|npm|
|emoji-regex|7.0.3|间接依赖|npm|
|semver|5.7.0|间接依赖|npm|
|object.assign|4.1.2|间接依赖|npm|
|glob-parent|5.1.2|间接依赖|npm|
|esutils|2.0.2|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|node-releases|2.0.5|间接依赖|npm|
|lodash.merge|4.6.2|间接依赖|npm|
|es-abstract|1.20.1|间接依赖|npm|
|@babel/helper-skip-transparent-expression-wrappers|7.22.5|间接依赖|npm|
|lodash.throttle|4.1.1|间接依赖|npm|
|jest-worker|26.6.2|间接依赖|npm|
|is-plain-object|3.0.1|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|jsesc|2.5.2|间接依赖|npm|
|@nodelib/fs.stat|2.0.4|间接依赖|npm|
|@babel/helper-split-export-declaration|7.16.7|间接依赖|npm|
|chokidar|3.5.3|间接依赖|npm|
|isarray|1.0.0|间接依赖|npm|
|object.values|1.1.5|间接依赖|npm|
|acorn-jsx|5.3.2|间接依赖|npm|
|regexpp|3.2.0|间接依赖|npm|
|@babel/helper-compilation-targets|7.17.10|间接依赖|npm|
|serialize-javascript|4.0.0|间接依赖|npm|
|merge-stream|2.0.0|间接依赖|npm|
|decamelize|1.2.0|间接依赖|npm|
|esrecurse|4.3.0|间接依赖|npm|
|array-includes|3.1.5|间接依赖|npm|
|functional-red-black-tree|1.0.1|间接依赖|npm|
|argparse|2.0.1|间接依赖|npm|
|@babel/helpers|7.18.0|间接依赖|npm|
|supports-preserve-symlinks-flag|1.0.0|间接依赖|npm|
|error-ex|1.3.2|间接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|doctrine|3.0.0|间接依赖|npm|
|text-table|0.2.0|间接依赖|npm|
|is-symbol|1.0.4|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|spdx-license-ids|3.0.7|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|spdx-exceptions|2.3.0|间接依赖|npm|
|readdirp|3.6.0|间接依赖|npm|
|is-boolean-object|1.1.2|间接依赖|npm|
|levn|0.4.1|间接依赖|npm|
|@jridgewell/trace-mapping|0.3.13|间接依赖|npm|
|jsonfile|4.0.0|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|spdx-correct|3.1.1|间接依赖|npm|
|@types/json5|0.0.29|间接依赖|npm|
|optionator|0.9.1|间接依赖|npm|
|string_decoder|1.1.1|间接依赖|npm|
|eslint-visitor-keys|2.1.0|间接依赖|npm|
|noms|0.0.0|间接依赖|npm|
|which-module|2.0.0|间接依赖|npm|
|is-arrayish|0.2.1|间接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|@nodelib/fs.walk|1.2.6|间接依赖|npm|
|esquery|1.4.0|间接依赖|npm|
|spawn-command|0.0.2-1|间接依赖|npm|
|@babel/helper-hoist-variables|7.16.7|间接依赖|npm|
|locate-path|3.0.0|间接依赖|npm|
|@humanwhocodes/object-schema|1.2.1|间接依赖|npm|
|camelcase|5.3.1|间接依赖|npm|
|tslib|1.14.1|间接依赖|npm|
|@types/minimatch|3.0.4|间接依赖|npm|
|eslint-scope|5.1.1|间接依赖|npm|
|is-string|1.0.7|间接依赖|npm|
|yargs|13.3.2|间接依赖|npm|
|@rollup/plugin-babel|6.0.3|直接依赖|npm|
|has-bigints|1.0.2|间接依赖|npm|
|is-date-object|1.0.5|间接依赖|npm|
|path-exists|3.0.0|间接依赖|npm|
|strip-json-comments|3.1.1|间接依赖|npm|
|graceful-fs|4.1.15|间接依赖|npm|
|globby|10.0.1|间接依赖|npm|
|es-to-primitive|1.2.1|间接依赖|npm|
|functions-have-names|1.2.3|间接依赖|npm|
|commander|2.20.3|间接依赖|npm|
|browserslist|4.20.3|间接依赖|npm|
|is-shared-array-buffer|1.0.2|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|side-channel|1.0.4|间接依赖|npm|
|@babel/helper-environment-visitor|7.16.7|间接依赖|npm|
|fs-extra|8.1.0|间接依赖|npm|
|@babel/code-frame|7.16.7|间接依赖|npm|
|@jridgewell/set-array|1.1.1|间接依赖|npm|
|rimraf|3.0.2|间接依赖|npm|
|prelude-ls|1.2.1|间接依赖|npm|
|rxjs|6.6.7|间接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|buffer-from|1.1.1|间接依赖|npm|
|minimist|1.2.6|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|@jridgewell/gen-mapping|0.1.1|间接依赖|npm|
|wrap-ansi|5.1.0|间接依赖|npm|
|type-check|0.4.0|间接依赖|npm|
|find-up|3.0.0|间接依赖|npm|
|is-regex|1.1.4|间接依赖|npm|
|is-callable|1.2.4|间接依赖|npm|
|@types/estree|1.0.1|间接依赖|npm|
|copyfiles|2.4.1|直接依赖|npm|
|string.prototype.trimstart|1.0.5|间接依赖|npm|
|@babel/plugin-transform-optional-chaining|7.22.12|直接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|p-locate|3.0.0|间接依赖|npm|
|@babel/core|7.18.0|直接依赖|npm|
|@babel/helper-validator-identifier|7.22.5|间接依赖|npm|
|json5|2.2.1|间接依赖|npm|
|anymatch|3.1.2|间接依赖|npm|
|@babel/eslint-parser|7.17.0|直接依赖|npm|
|@humanwhocodes/config-array|0.9.5|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|fastq|1.11.0|间接依赖|npm|
|tsconfig-paths|3.14.1|间接依赖|npm|
|xtend|4.0.2|间接依赖|npm|
|ignore|5.2.0|间接依赖|npm|
|@babel/helper-string-parser|7.22.5|间接依赖|npm|
|js-yaml|4.1.0|间接依赖|npm|
|rollup-plugin-copy|3.4.0|直接依赖|npm|
|confusing-browser-globals|1.0.10|间接依赖|npm|
|caniuse-lite|1.0.30001342|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|@babel/helper-module-imports|7.22.5|间接依赖|npm|
|core-util-is|1.0.2|间接依赖|npm|
|is-number-object|1.0.7|间接依赖|npm|
|strip-ansi|6.0.1|间接依赖|npm|
|get-symbol-description|1.0.0|间接依赖|npm|
|convert-source-map|1.7.0|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|imurmurhash|0.1.4|间接依赖|npm|
|electron-to-chromium|1.4.138|间接依赖|npm|
|typescript|4.7.3|直接依赖|npm|
|universalify|0.1.2|间接依赖|npm|
|fast-glob|3.2.5|间接依赖|npm|
|@babel/helper-plugin-utils|7.22.5|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|color-name|1.1.3|间接依赖|npm|
|v8-compile-cache|2.3.0|间接依赖|npm|
|get-intrinsic|1.1.1|间接依赖|npm|
|isexe|2.0.0|直接依赖|npm|
|concurrently|6.0.2|直接依赖|npm|
|slash|3.0.0|间接依赖|npm|
|fsevents|2.3.2|间接依赖|npm|
|normalize-package-data|2.5.0|间接依赖|npm|
|@babel/plugin-syntax-optional-chaining|7.8.3|间接依赖|npm|
|resolve|1.22.0|间接依赖|npm|
|word-wrap|1.2.3|间接依赖|npm|
|estraverse|4.3.0|间接依赖|npm|
|inherits|2.0.3|间接依赖|npm|
|validate-npm-package-license|3.0.4|间接依赖|npm|
|@babel/highlight|7.17.9|间接依赖|npm|
|@nodelib/fs.scandir|2.1.4|间接依赖|npm|
|eslint|8.16.0|直接依赖|npm|
|parse-json|5.2.0|间接依赖|npm|
|require-main-filename|2.0.0|间接依赖|npm|
|which-boxed-primitive|1.0.2|间接依赖|npm|
|terser|5.7.0|间接依赖|npm|
|lines-and-columns|1.1.6|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|yargs-parser|13.1.2|间接依赖|npm|
|object-inspect|1.12.1|间接依赖|npm|
|import-fresh|3.3.0|间接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|globals|11.12.0|间接依赖|npm|
|is-binary-path|2.1.0|间接依赖|npm|
|randombytes|2.1.0|间接依赖|npm|
|@types/normalize-package-data|2.4.0|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|json-stable-stringify-without-jsonify|1.0.1|间接依赖|npm|
|@types/node|15.0.1|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|rollup|2.71.1|直接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|@babel/compat-data|7.17.10|间接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|string.prototype.trimend|1.0.5|间接依赖|npm|
|eslint-import-resolver-node|0.3.6|间接依赖|npm|
|dir-glob|3.0.1|间接依赖|npm|
|@babel/parser|7.18.0|间接依赖|npm|
|@types/fs-extra|8.1.1|间接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|picomatch|2.3.1|间接依赖|npm|
|@babel/helper-simple-access|7.17.7|间接依赖|npm|
|flat-cache|3.0.4|间接依赖|npm|
|estree-walker|2.0.2|间接依赖|npm|
|tree-kill|1.2.2|间接依赖|npm|
|read-pkg|5.2.0|间接依赖|npm|
|date-fns|2.21.1|间接依赖|npm|
|is-glob|4.0.3|间接依赖|npm|
|eslint-config-airbnb-base|15.0.0|直接依赖|npm|
|spdx-expression-parse|3.0.1|间接依赖|npm|
|glob|7.1.3|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|@babel/helper-module-transforms|7.18.0|间接依赖|npm|
|rollup-plugin-terser|7.0.2|直接依赖|npm|
|@babel/template|7.16.7|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|punycode|2.1.1|间接依赖|npm|
|regexp.prototype.flags|1.4.3|间接依赖|npm|
|@babel/helper-validator-option|7.16.7|间接依赖|npm|
|espree|9.3.2|间接依赖|npm|
|@rollup/pluginutils|5.0.4|间接依赖|npm|
|has-property-descriptors|1.0.0|间接依赖|npm|
|is-bigint|1.0.4|间接依赖|npm|
|untildify|4.0.0|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|source-map|0.7.3|间接依赖|npm|
|ajv|6.12.6|间接依赖|npm|
|is-weakref|1.0.2|间接依赖|npm|
|readable-stream|2.3.6|间接依赖|npm|
|object-keys|1.1.1|间接依赖|npm|
|deep-is|0.1.3|间接依赖|npm|
|callsites|3.1.0|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|debug|4.3.1|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)