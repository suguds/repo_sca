# meteor/meteor安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695144869809778688.svg)](https://www.murphysec.com/console/report/1695144869734281216/1695144869809778688)

仓库描述：Meteor, the JavaScript App Platform

仓库地址：[https://github.com/meteor/meteor](https://github.com/meteor/meteor)

| star：43655 | watch：1585 | fork：5293 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-25 04:33:50 | 许可证：NOASSERTION |
| 最近检测时间：2023-08-26 02:49:48 | 组件总数：361 | 漏洞总数：10 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|lodash 拒绝服务漏洞|拒绝服务|[MPS-2021-2574](https://www.oscs1024.com/hd/MPS-2021-2574)|CVE-2020-28500|中危|
|lodash 命令注入漏洞|代码注入|[MPS-2021-2638](https://www.oscs1024.com/hd/MPS-2021-2638)|CVE-2021-23337|高危|
|Ruy Adorno hosted-git-info 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-3400](https://www.oscs1024.com/hd/MPS-2021-3400)|CVE-2021-23362|中危|
|minimist 安全漏洞|原型污染|[MPS-2021-38405](https://www.oscs1024.com/hd/MPS-2021-38405)|CVE-2021-44906|严重|
|npm path-parse 安全漏洞|拒绝服务|[MPS-2021-6165](https://www.oscs1024.com/hd/MPS-2021-6165)|CVE-2021-23343|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|decode-uri-component <=0.2.0 存在输入验证不当漏洞|拒绝服务|[MPS-2022-56259](https://www.oscs1024.com/hd/MPS-2022-56259)|CVE-2022-38900|高危|
|minimatch 资源管理错误漏洞|拒绝服务|[MPS-2022-59845](https://www.oscs1024.com/hd/MPS-2022-59845)|CVE-2022-3517|高危|
|Tauri 原型污染漏洞|原型污染|[MPS-2022-65568](https://www.oscs1024.com/hd/MPS-2022-65568)|CVE-2022-46175|高危|
|word-wrap 安全漏洞|ReDoS|[MPS-2023-5109](https://www.oscs1024.com/hd/MPS-2023-5109)|CVE-2023-26115|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|path-parse|1.0.6|1.0.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|word-wrap|1.2.3|1.2.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|decode-uri-component|0.2.0|0.2.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|json5|1.0.1|2.2.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|minimatch|3.0.4|3.0.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|minimist|1.2.5|1.2.6|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|lodash|4.17.20|4.17.21|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|semver|5.7.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|hosted-git-info|2.8.8|3.0.8|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|303|Low|
|BSD-2-Clause|12|Low|
|0BSD|1|Low|
|ISC|22|Low|
|Apache-2.0|8|Low|
|BSD-3-Clause|4|Low|
|ODC-By-1.0|1|Low|
|MPL-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|@babel/helper-function-name|7.0.0-beta.52|间接依赖|npm|
|type-fest|0.6.0|直接依赖|npm|
|expand-brackets|2.1.4|间接依赖|npm|
|pluralize|7.0.0|直接依赖|npm|
|code-point-at|1.1.0|直接依赖|npm|
|lines-and-columns|1.1.6|直接依赖|npm|
|prettier-eslint|8.8.2|间接依赖|npm|
|extend-shallow|3.0.2|间接依赖|npm|
|isarray|1.0.0|间接依赖|npm|
|normalize-package-data|2.5.0|间接依赖|npm|
|read-pkg-up|2.0.0|间接依赖|npm|
|resolve|1.20.0|间接依赖|npm|
|husky|3.1.0|间接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|is-core-module|2.2.0|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|to-fast-properties|2.0.0|间接依赖|npm|
|spdx-expression-parse|3.0.1|间接依赖|npm|
|stringify-object|3.3.0|间接依赖|npm|
|is-directory|0.3.1|间接依赖|npm|
|listr-update-renderer|0.5.0|间接依赖|npm|
|core-js-pure|3.8.3|间接依赖|npm|
|safe-regex|1.1.0|间接依赖|npm|
|jest-get-type|22.4.3|间接依赖|npm|
|use|3.1.1|间接依赖|npm|
|tslib|1.14.1|间接依赖|npm|
|signal-exit|3.0.3|间接依赖|npm|
|is-date-object|1.0.2|间接依赖|npm|
|doctrine|3.0.0|间接依赖|npm|
|listr-silent-renderer|1.1.1|间接依赖|npm|
|cosmiconfig|5.2.1|间接依赖|npm|
|resolve-url|0.2.1|间接依赖|npm|
|resolve-from|4.0.0|间接依赖|npm|
|acorn-jsx|5.3.1|间接依赖|npm|
|deep-is|0.1.3|间接依赖|npm|
|@babel/runtime|7.12.13|间接依赖|npm|
|eslint-plugin-jest|21.27.2|间接依赖|npm|
|iconv-lite|0.4.24|间接依赖|npm|
|pkg-dir|2.0.0|间接依赖|npm|
|graceful-fs|4.2.6|间接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|@meteorjs/eslint-config-meteor|1.0.5|间接依赖|npm|
|object-inspect|1.9.0|间接依赖|npm|
|string-width|2.1.1|间接依赖|npm|
|is-promise|2.2.2|间接依赖|npm|
|eslint-plugin-jsx-a11y|6.4.1|间接依赖|npm|
|leven|2.1.0|间接依赖|npm|
|process-nextick-args|2.0.1|间接依赖|npm|
|eslint-config-airbnb-base|13.2.0|间接依赖|npm|
|is-windows|1.0.2|间接依赖|npm|
|is-stream|1.1.0|间接依赖|npm|
|esquery|1.4.0|间接依赖|npm|
|@quave/eslint-config-quave|1.0.3|直接依赖|npm|
|os-tmpdir|1.0.2|间接依赖|npm|
|tmp|0.0.33|间接依赖|npm|
|extglob|2.0.4|间接依赖|npm|
|shebang-regex|1.0.0|间接依赖|npm|
|array-includes|3.1.2|间接依赖|npm|
|is-resolvable|1.1.0|直接依赖|npm|
|@babel/template|7.0.0-beta.52|间接依赖|npm|
|staged-git-files|1.1.1|间接依赖|npm|
|globals|11.12.0|间接依赖|npm|
|is-arrayish|0.2.1|间接依赖|npm|
|emoji-regex|7.0.3|间接依赖|npm|
|@types/json5|0.0.29|间接依赖|npm|
|eslint-plugin-react|7.22.0|间接依赖|npm|
|@types/node|14.17.6|直接依赖|npm|
|typescript-eslint-parser|16.0.1|间接依赖|npm|
|minimist|1.2.5|间接依赖|npm|
|onetime|2.0.1|间接依赖|npm|
|find-up|2.1.0|间接依赖|npm|
|path-exists|3.0.0|间接依赖|npm|
|language-subtag-registry|0.3.21|间接依赖|npm|
|concat-stream|1.6.2|直接依赖|npm|
|ansi-regex|3.0.0|间接依赖|npm|
|@babel/highlight|7.0.0-beta.52|间接依赖|npm|
|is-accessor-descriptor|0.1.6|间接依赖|npm|
|locate-path|2.0.0|间接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|pify|2.3.0|间接依赖|npm|
|text-table|0.2.0|间接依赖|npm|
|arr-diff|4.0.0|间接依赖|npm|
|@babel/generator|7.0.0-beta.52|间接依赖|npm|
|atob|2.1.2|间接依赖|npm|
|eslint-utils|1.4.3|间接依赖|npm|
|@babel/code-frame|7.0.0-beta.52|间接依赖|npm|
|js-yaml|3.14.1|间接依赖|npm|
|array.prototype.flat|1.2.4|间接依赖|npm|
|json-parse-even-better-errors|2.3.1|直接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|pascalcase|0.1.1|间接依赖|npm|
|kind-of|6.0.3|间接依赖|npm|
|validate-npm-package-license|3.0.4|间接依赖|npm|
|damerau-levenshtein|1.0.6|间接依赖|npm|
|regexpp|2.0.1|间接依赖|npm|
|core-js|2.6.12|间接依赖|npm|
|require-uncached|1.0.3|直接依赖|npm|
|semver-compare|1.0.0|间接依赖|npm|
|lodash|4.17.20|间接依赖|npm|
|get-stdin|6.0.0|间接依赖|npm|
|jest-validate|23.6.0|间接依赖|npm|
|define-property|2.0.2|间接依赖|npm|
|object.entries|1.1.3|间接依赖|npm|
|babel-code-frame|6.26.0|直接依赖|npm|
|urix|0.1.0|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|find-parent-dir|0.3.0|间接依赖|npm|
|eslint-plugin-import|2.22.1|间接依赖|npm|
|eslint-config-airbnb|17.1.1|间接依赖|npm|
|ret|0.1.15|间接依赖|npm|
|buffer-from|1.1.1|间接依赖|npm|
|regexp.prototype.flags|1.3.1|间接依赖|npm|
|is-glob|4.0.1|间接依赖|npm|
|path-parse|1.0.6|间接依赖|npm|
|ansi-escapes|3.2.0|间接依赖|npm|
|which|1.3.1|间接依赖|npm|
|npm-which|3.0.1|间接依赖|npm|
|punycode|2.1.1|间接依赖|npm|
|shebang-command|1.2.0|间接依赖|npm|
|string.prototype.trimend|1.0.3|间接依赖|npm|
|functional-red-black-tree|1.0.1|间接依赖|npm|
|json-stable-stringify-without-jsonify|1.0.1|间接依赖|npm|
|arr-flatten|1.1.0|间接依赖|npm|
|posix-character-classes|0.1.1|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|log-symbols|2.2.0|间接依赖|npm|
|figures|2.0.0|间接依赖|npm|
|core-util-is|1.0.2|间接依赖|npm|
|spdx-correct|3.1.1|间接依赖|npm|
|number-is-nan|1.0.1|直接依赖|npm|
|is-data-descriptor|0.1.4|间接依赖|npm|
|npm-path|2.0.4|间接依赖|npm|
|is-descriptor|0.1.6|间接依赖|npm|
|run-async|2.4.1|间接依赖|npm|
|snapdragon|0.8.2|间接依赖|npm|
|@babel/helper-split-export-declaration|7.0.0-beta.52|间接依赖|npm|
|base|0.11.2|间接依赖|npm|
|dedent|0.7.0|间接依赖|npm|
|nice-try|1.0.5|间接依赖|npm|
|estraverse|4.3.0|间接依赖|npm|
|get-own-enumerable-property-symbols|3.0.2|间接依赖|npm|
|nanomatch|1.2.13|间接依赖|npm|
|define-properties|1.1.3|间接依赖|npm|
|color-name|1.1.3|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|path-is-inside|1.0.2|间接依赖|npm|
|file-entry-cache|5.0.1|间接依赖|npm|
|co|4.6.0|直接依赖|npm|
|callsites|3.1.0|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|is-obj|1.0.1|间接依赖|npm|
|@babel/helper-get-function-arity|7.0.0-beta.52|间接依赖|npm|
|eslint-plugin-react-hooks|3.0.0|间接依赖|npm|
|to-regex-range|2.1.1|间接依赖|npm|
|fragment-cache|0.2.1|间接依赖|npm|
|regenerator-runtime|0.13.7|间接依赖|npm|
|prettier|1.19.1|间接依赖|npm|
|slice-ansi|2.1.0|间接依赖|npm|
|esrecurse|4.3.0|间接依赖|npm|
|eslint-visitor-keys|1.3.0|间接依赖|npm|
|es-to-primitive|1.2.1|间接依赖|npm|
|commander|2.20.3|间接依赖|npm|
|get-stream|4.1.0|间接依赖|npm|
|caller-callsite|2.0.0|间接依赖|npm|
|restore-cursor|2.0.0|间接依赖|npm|
|hosted-git-info|2.8.8|间接依赖|npm|
|babel-runtime|6.26.0|间接依赖|npm|
|string.prototype.matchall|4.0.3|间接依赖|npm|
|class-utils|0.3.6|间接依赖|npm|
|debug|3.2.7|间接依赖|npm|
|load-json-file|2.0.0|间接依赖|npm|
|is-observable|1.1.0|间接依赖|npm|
|yallist|2.1.2|间接依赖|npm|
|ignore|4.0.6|间接依赖|npm|
|p-map|1.2.0|间接依赖|npm|
|tsconfig-paths|3.9.0|间接依赖|npm|
|minimatch|3.0.4|间接依赖|npm|
|@types/normalize-package-data|2.4.0|直接依赖|npm|
|json-parse-better-errors|1.0.2|直接依赖|npm|
|is-callable|1.2.3|间接依赖|npm|
|path-type|2.0.0|间接依赖|npm|
|decode-uri-component|0.2.0|间接依赖|npm|
|strip-bom|3.0.0|间接依赖|npm|
|strip-json-comments|2.0.1|间接依赖|npm|
|jsx-ast-utils|3.2.0|间接依赖|npm|
|source-map-resolve|0.5.3|间接依赖|npm|
|split-string|3.1.0|间接依赖|npm|
|run-node|1.0.0|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|isobject|3.0.1|间接依赖|npm|
|object.fromentries|2.0.3|间接依赖|npm|
|astral-regex|1.0.0|间接依赖|npm|
|language-tags|1.0.5|间接依赖|npm|
|p-locate|2.0.0|间接依赖|npm|
|dlv|1.1.3|间接依赖|npm|
|sprintf-js|1.0.3|间接依赖|npm|
|axobject-query|2.2.0|间接依赖|npm|
|type-check|0.3.2|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|call-bind|1.0.2|间接依赖|npm|
|typedarray|0.0.6|间接依赖|npm|
|parse-json|2.2.0|间接依赖|npm|
|json5|1.0.1|间接依赖|npm|
|is-extendable|0.1.1|间接依赖|npm|
|common-tags|1.8.0|间接依赖|npm|
|acorn|6.4.2|间接依赖|npm|
|prelude-ls|1.1.2|间接依赖|npm|
|pretty-format|23.6.0|间接依赖|npm|
|lint-staged|7.3.0|间接依赖|npm|
|mixin-deep|1.3.2|间接依赖|npm|
|pump|3.0.0|间接依赖|npm|
|to-regex|3.0.2|间接依赖|npm|
|import-fresh|3.3.0|间接依赖|npm|
|mkdirp|0.5.5|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|optionator|0.8.3|间接依赖|npm|
|string_decoder|1.1.1|间接依赖|npm|
|date-fns|1.30.1|间接依赖|npm|
|source-map|0.5.7|间接依赖|npm|
|semver|5.7.1|间接依赖|npm|
|esutils|2.0.3|间接依赖|npm|
|lodash.unescape|4.0.1|间接依赖|npm|
|through|2.3.8|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|is-number|3.0.0|间接依赖|npm|
|ajv|6.12.6|间接依赖|npm|
|object.assign|4.1.2|间接依赖|npm|
|confusing-browser-globals|1.0.10|间接依赖|npm|
|cli-truncate|0.2.1|间接依赖|npm|
|rx-lite-aggregates|4.0.8|直接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|rx-lite|4.0.8|间接依赖|npm|
|trim-right|1.0.1|间接依赖|npm|
|ci-info|2.0.0|间接依赖|npm|
|array-unique|0.3.2|间接依赖|npm|
|ajv-keywords|2.1.1|直接依赖|npm|
|listr|0.14.3|间接依赖|npm|
|regex-not|1.0.2|间接依赖|npm|
|is-negative-zero|2.0.1|间接依赖|npm|
|opencollective-postinstall|2.0.3|间接依赖|npm|
|side-channel|1.0.4|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|levn|0.3.0|间接依赖|npm|
|table|5.4.6|间接依赖|npm|
|any-observable|0.3.0|间接依赖|npm|
|@samverschueren/stream-to-observable|0.3.1|间接依赖|npm|
|@babel/traverse|7.0.0-beta.52|间接依赖|npm|
|micromatch|3.1.10|间接依赖|npm|
|listr-verbose-renderer|0.5.0|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|eslint-import-resolver-node|0.3.4|间接依赖|npm|
|is-fullwidth-code-point|2.0.0|间接依赖|npm|
|parent-module|1.0.1|间接依赖|npm|
|is-regexp|1.0.0|间接依赖|npm|
|object.values|1.1.2|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|fill-range|4.0.0|间接依赖|npm|
|progress|2.0.3|间接依赖|npm|
|axe-core|4.1.2|间接依赖|npm|
|aria-query|4.2.2|间接依赖|npm|
|@babel/runtime-corejs3|7.12.13|间接依赖|npm|
|string.prototype.trimstart|1.0.3|间接依赖|npm|
|rxjs|6.6.3|间接依赖|npm|
|execa|1.0.0|间接依赖|npm|
|object.pick|1.3.0|间接依赖|npm|
|map-cache|0.2.2|间接依赖|npm|
|please-upgrade-node|3.2.0|间接依赖|npm|
|prop-types|15.7.2|间接依赖|npm|
|@babel/helper-validator-identifier|7.12.11|直接依赖|npm|
|has-symbols|1.0.1|间接依赖|npm|
|react-is|16.13.1|间接依赖|npm|
|p-finally|1.0.0|间接依赖|npm|
|flat-cache|2.0.1|间接依赖|npm|
|argparse|1.0.10|间接依赖|npm|
|elegant-spinner|1.0.1|间接依赖|npm|
|symbol-observable|1.2.0|间接依赖|npm|
|pseudomap|1.0.2|间接依赖|npm|
|cross-spawn|6.0.5|间接依赖|npm|
|glob|7.1.6|间接依赖|npm|
|caller-path|2.0.0|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|eslint-scope|3.7.1|间接依赖|npm|
|rimraf|2.6.3|间接依赖|npm|
|require-relative|0.8.7|间接依赖|npm|
|circular-json|0.3.3|直接依赖|npm|
|write|1.0.3|间接依赖|npm|
|strip-eof|1.0.0|间接依赖|npm|
|repeat-string|1.6.1|间接依赖|npm|
|mute-stream|0.0.7|间接依赖|npm|
|external-editor|3.1.0|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|cache-base|1.0.1|间接依赖|npm|
|cli-width|2.2.1|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|imurmurhash|0.1.4|间接依赖|npm|
|loose-envify|1.4.0|间接依赖|npm|
|chardet|0.7.0|间接依赖|npm|
|lodash.merge|4.6.2|间接依赖|npm|
|get-intrinsic|1.1.1|间接依赖|npm|
|inquirer|6.5.2|间接依赖|npm|
|ms|2.1.3|间接依赖|npm|
|@babel/parser|7.0.0-beta.52|间接依赖|npm|
|loglevel-colored-level-prefix|1.0.0|间接依赖|npm|
|babel-eslint|9.0.0-beta.3|间接依赖|npm|
|error-ex|1.3.2|间接依赖|npm|
|wrap-ansi|3.0.1|间接依赖|npm|
|readable-stream|2.3.7|间接依赖|npm|
|eslint|5.16.0|间接依赖|npm|
|typescript|2.9.2|间接依赖|npm|
|jsesc|2.5.2|间接依赖|npm|
|cli-cursor|2.1.0|间接依赖|npm|
|eslint-module-utils|2.6.0|间接依赖|npm|
|ast-types-flow|0.0.7|间接依赖|npm|
|js-tokens|3.0.2|间接依赖|npm|
|npm-run-path|2.0.2|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|repeat-element|1.1.3|间接依赖|npm|
|lru-cache|4.1.5|直接依赖|npm|
|balanced-match|1.0.0|间接依赖|npm|
|is-buffer|1.1.6|直接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|source-map-url|0.4.1|间接依赖|npm|
|strip-ansi|4.0.0|间接依赖|npm|
|component-emitter|1.3.0|间接依赖|npm|
|eslint-import-resolver-meteor|0.4.0|间接依赖|npm|
|has-ansi|2.0.0|直接依赖|npm|
|object-keys|1.1.1|间接依赖|npm|
|log-update|2.3.0|间接依赖|npm|
|eslint-config-prettier|3.6.0|间接依赖|npm|
|esprima|4.0.1|间接依赖|npm|
|is-string|1.0.5|间接依赖|npm|
|eslint-plugin-meteor|5.2.0|间接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|snapdragon-util|3.0.1|间接依赖|npm|
|array.prototype.flatmap|1.2.4|间接依赖|npm|
|contains-path|0.1.0|间接依赖|npm|
|@babel/types|7.0.0-beta.52|间接依赖|npm|
|string-argv|0.0.2|间接依赖|npm|
|end-of-stream|1.4.4|间接依赖|npm|
|loglevel|1.7.1|间接依赖|npm|
|fast-levenshtein|2.0.6|间接依赖|npm|
|internal-slot|1.0.3|间接依赖|npm|
|is-symbol|1.0.3|间接依赖|npm|
|slash|3.0.0|间接依赖|npm|
|vue-eslint-parser|2.0.3|间接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|assign-symbols|1.0.0|间接依赖|npm|
|read-pkg|2.0.0|间接依赖|npm|
|path-key|2.0.1|间接依赖|npm|
|is-regex|1.1.2|间接依赖|npm|
|invariant|2.2.4|间接依赖|npm|
|indent-string|3.2.0|间接依赖|npm|
|braces|2.3.2|间接依赖|npm|
|flatted|2.0.2|间接依赖|npm|
|snapdragon-node|2.1.1|间接依赖|npm|
|espree|5.0.1|间接依赖|npm|
|es-abstract|1.18.0-next.2|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|natural-compare|1.4.0|间接依赖|npm|
|word-wrap|1.2.3|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)