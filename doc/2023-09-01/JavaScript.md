# TheAlgorithms/JavaScript安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1697317313841029120.svg)](https://www.murphysec.com/console/report/1691879892432216064/1697317313841029120)

仓库描述：Algorithms and Data Structures implemented in JavaScript for beginners, following best practices.

仓库地址：[https://github.com/TheAlgorithms/JavaScript](https://github.com/TheAlgorithms/JavaScript)

| star：27596 | watch：587 | fork：4864 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-25 13:22:30 | 许可证：GPL-3.0 |
| 最近检测时间：2023-09-01 02:36:10 | 组件总数：466 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|word-wrap 安全漏洞|ReDoS|[MPS-2023-5109](https://www.oscs1024.com/hd/MPS-2023-5109)|CVE-2023-26115|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|word-wrap|1.2.3|1.2.4|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|semver|6.3.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|393|Low|
|ISC|29|Low|
|BSD-2-Clause|8|Low|
|BSD-3-Clause|14|Low|
|Apache-2.0|8|Low|
|CC-BY-4.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|string-length|4.0.2|间接依赖|npm|
|regenerate-unicode-properties|10.1.0|间接依赖|npm|
|jest-cli|29.2.0|间接依赖|npm|
|@babel/plugin-transform-modules-systemjs|7.19.0|间接依赖|npm|
|jest-config|29.2.0|间接依赖|npm|
|get-intrinsic|1.1.3|间接依赖|npm|
|json-parse-even-better-errors|2.3.1|间接依赖|npm|
|test-exclude|6.0.0|间接依赖|npm|
|lru-cache|6.0.0|直接依赖|npm|
|standard-engine|15.0.0|间接依赖|npm|
|eslint-module-utils|2.7.4|间接依赖|npm|
|functions-have-names|1.2.3|间接依赖|npm|
|@babel/generator|7.19.5|间接依赖|npm|
|react-is|18.2.0|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|js-sdsl|4.1.5|间接依赖|npm|
|@babel/plugin-transform-object-super|7.18.6|间接依赖|npm|
|esprima|4.0.1|间接依赖|npm|
|babel-jest|29.2.0|间接依赖|npm|
|makeerror|1.0.12|间接依赖|npm|
|side-channel|1.0.4|间接依赖|npm|
|debug|4.3.3|间接依赖|npm|
|prompts|2.4.2|间接依赖|npm|
|@babel/plugin-syntax-typescript|7.18.6|间接依赖|npm|
|@babel/preset-env|7.19.4|直接依赖|npm|
|pkg-conf|3.1.0|间接依赖|npm|
|glob-parent|5.1.2|间接依赖|npm|
|regexpu-core|5.2.1|间接依赖|npm|
|lodash.merge|4.6.2|间接依赖|npm|
|@jest/transform|29.2.0|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|eslint-plugin-promise|6.1.0|间接依赖|npm|
|path-exists|4.0.0|间接依赖|npm|
|@babel/helper-module-transforms|7.19.0|间接依赖|npm|
|@babel/plugin-proposal-dynamic-import|7.18.6|间接依赖|npm|
|@jest/reporters|29.2.0|间接依赖|npm|
|@babel/plugin-transform-computed-properties|7.18.9|间接依赖|npm|
|import-local|3.1.0|间接依赖|npm|
|espree|9.4.0|间接依赖|npm|
|@babel/plugin-transform-for-of|7.18.8|间接依赖|npm|
|walker|1.0.8|间接依赖|npm|
|js-yaml|3.14.1|间接依赖|npm|
|@babel/helper-hoist-variables|7.18.6|间接依赖|npm|
|@babel/plugin-syntax-async-generators|7.8.4|间接依赖|npm|
|fsevents|2.3.2|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|husky|8.0.1|直接依赖|npm|
|is-date-object|1.0.5|间接依赖|npm|
|convert-source-map|1.8.0|间接依赖|npm|
|istanbul-lib-instrument|5.1.0|间接依赖|npm|
|is-regex|1.1.4|间接依赖|npm|
|@babel/plugin-transform-block-scoping|7.19.4|间接依赖|npm|
|builtins|5.0.1|间接依赖|npm|
|collect-v8-coverage|1.0.1|间接依赖|npm|
|@babel/plugin-transform-new-target|7.18.6|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|@babel/plugin-proposal-async-generator-functions|7.19.1|间接依赖|npm|
|is-glob|4.0.3|间接依赖|npm|
|argparse|1.0.10|间接依赖|npm|
|eslint-visitor-keys|2.1.0|间接依赖|npm|
|path-key|3.1.1|间接依赖|npm|
|find-up|4.1.0|间接依赖|npm|
|dir-glob|3.0.1|间接依赖|npm|
|babel-preset-jest|29.2.0|间接依赖|npm|
|shebang-command|2.0.0|间接依赖|npm|
|ignore|5.2.0|间接依赖|npm|
|strip-json-comments|3.1.1|间接依赖|npm|
|sprintf-js|1.0.3|间接依赖|npm|
|@babel/plugin-transform-exponentiation-operator|7.18.6|间接依赖|npm|
|@babel/plugin-transform-dotall-regex|7.18.6|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|@babel/plugin-proposal-logical-assignment-operators|7.18.9|间接依赖|npm|
|@nodelib/fs.stat|2.0.5|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|jest-util|29.2.0|间接依赖|npm|
|@babel/plugin-transform-spread|7.19.0|间接依赖|npm|
|@types/json5|0.0.29|间接依赖|npm|
|make-dir|3.1.0|间接依赖|npm|
|co|4.6.0|间接依赖|npm|
|json-stable-stringify-without-jsonify|1.0.1|间接依赖|npm|
|jsx-ast-utils|3.3.3|间接依赖|npm|
|@babel/plugin-transform-shorthand-properties|7.18.6|间接依赖|npm|
|@babel/plugin-proposal-object-rest-spread|7.19.4|间接依赖|npm|
|@babel/parser|7.19.4|间接依赖|npm|
|is-generator-fn|2.1.0|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|signal-exit|3.0.7|间接依赖|npm|
|es-shim-unscopables|1.0.0|间接依赖|npm|
|json-parse-better-errors|1.0.2|直接依赖|npm|
|@babel/plugin-proposal-class-static-block|7.18.6|间接依赖|npm|
|is-core-module|2.10.0|间接依赖|npm|
|parent-module|1.0.1|间接依赖|npm|
|call-bind|1.0.2|间接依赖|npm|
|tsconfig-paths|3.14.1|间接依赖|npm|
|@babel/runtime|7.19.4|间接依赖|npm|
|object.hasown|1.1.1|间接依赖|npm|
|babel-plugin-dynamic-import-node|2.3.3|间接依赖|npm|
|kleur|3.0.3|间接依赖|npm|
|pify|4.0.1|间接依赖|npm|
|resolve-cwd|3.0.0|间接依赖|npm|
|@jest/source-map|29.2.0|间接依赖|npm|
|ajv|6.12.6|间接依赖|npm|
|eslint|8.25.0|间接依赖|npm|
|jest-resolve|29.2.0|间接依赖|npm|
|@jest/console|29.2.0|间接依赖|npm|
|ansi-escapes|4.3.2|间接依赖|npm|
|@babel/plugin-transform-named-capturing-groups-regex|7.19.1|间接依赖|npm|
|@types/prettier|2.7.1|间接依赖|npm|
|@babel/helper-function-name|7.19.0|间接依赖|npm|
|eslint-plugin-n|15.3.0|间接依赖|npm|
|bser|2.1.1|间接依赖|npm|
|node-releases|2.0.6|间接依赖|npm|
|unicode-canonical-property-names-ecmascript|2.0.0|间接依赖|npm|
|standard|17.0.0|直接依赖|npm|
|char-regex|1.0.2|间接依赖|npm|
|doctrine|3.0.0|间接依赖|npm|
|exit|0.1.2|间接依赖|npm|
|es-to-primitive|1.2.1|间接依赖|npm|
|@babel/plugin-proposal-nullish-coalescing-operator|7.18.6|间接依赖|npm|
|@babel/eslint-parser|7.19.1|直接依赖|npm|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|@types/stack-utils|2.0.1|间接依赖|npm|
|array-includes|3.1.5|间接依赖|npm|
|babel-preset-current-node-syntax|1.0.1|间接依赖|npm|
|@jest/test-sequencer|29.2.0|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|eslint-config-standard|17.0.0|间接依赖|npm|
|get-stdin|8.0.0|间接依赖|npm|
|@babel/helper-replace-supers|7.19.1|间接依赖|npm|
|string.prototype.matchall|4.0.7|间接依赖|npm|
|@jest/fake-timers|29.2.0|间接依赖|npm|
|anymatch|3.1.2|间接依赖|npm|
|@babel/helpers|7.19.4|间接依赖|npm|
|unicode-match-property-value-ecmascript|2.0.0|间接依赖|npm|
|es-abstract|1.20.4|间接依赖|npm|
|is-stream|2.0.1|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|object.values|1.1.5|间接依赖|npm|
|string.prototype.trimend|1.0.5|间接依赖|npm|
|@babel/plugin-syntax-optional-catch-binding|7.8.3|间接依赖|npm|
|jest-watcher|29.2.0|间接依赖|npm|
|source-map|0.6.1|间接依赖|npm|
|update-browserslist-db|1.0.10|间接依赖|npm|
|@sinonjs/commons|1.8.3|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|source-map-support|0.5.13|间接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|resolve.exports|1.1.0|间接依赖|npm|
|jest-validate|29.2.0|间接依赖|npm|
|jest-leak-detector|29.2.0|间接依赖|npm|
|@jest/expect|29.2.0|间接依赖|npm|
|@babel/plugin-transform-async-to-generator|7.18.6|间接依赖|npm|
|@babel/plugin-syntax-class-properties|7.12.13|间接依赖|npm|
|yocto-queue|0.1.0|直接依赖|npm|
|@babel/helper-simple-access|7.19.4|间接依赖|npm|
|rimraf|3.0.2|间接依赖|npm|
|eslint-scope|5.1.1|间接依赖|npm|
|@jest/schemas|29.0.0|间接依赖|npm|
|define-properties|1.1.4|间接依赖|npm|
|@babel/plugin-proposal-private-methods|7.18.6|间接依赖|npm|
|pirates|4.0.5|间接依赖|npm|
|punycode|2.1.1|间接依赖|npm|
|html-escaper|2.0.2|间接依赖|npm|
|which-boxed-primitive|1.0.2|间接依赖|npm|
|@types/graceful-fs|4.1.5|间接依赖|npm|
|@babel/helper-module-imports|7.18.6|间接依赖|npm|
|glob|7.2.0|间接依赖|npm|
|graceful-fs|4.2.10|间接依赖|npm|
|semver|6.3.0|间接依赖|npm|
|@babel/plugin-transform-reserved-words|7.18.6|间接依赖|npm|
|caniuse-lite|1.0.30001419|间接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.14|间接依赖|npm|
|fb-watchman|2.0.2|间接依赖|npm|
|@babel/plugin-transform-modules-umd|7.18.6|间接依赖|npm|
|object.assign|4.1.4|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|@types/istanbul-reports|3.0.1|间接依赖|npm|
|natural-compare|1.4.0|间接依赖|npm|
|jest-runner|29.2.0|间接依赖|npm|
|@babel/template|7.18.10|间接依赖|npm|
|@babel/helper-validator-option|7.18.6|间接依赖|npm|
|internal-slot|1.0.3|间接依赖|npm|
|@babel/plugin-transform-classes|7.19.0|间接依赖|npm|
|@babel/compat-data|7.19.4|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|pretty-format|29.2.0|间接依赖|npm|
|core-js-compat|3.25.5|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|@babel/helper-plugin-utils|7.19.0|间接依赖|npm|
|@jridgewell/set-array|1.1.2|间接依赖|npm|
|@types/babel__generator|7.6.4|间接依赖|npm|
|jsesc|2.5.2|间接依赖|npm|
|xdg-basedir|4.0.0|间接依赖|npm|
|write-file-atomic|4.0.2|间接依赖|npm|
|@babel/plugin-syntax-private-property-in-object|7.14.5|间接依赖|npm|
|picocolors|1.0.0|间接依赖|npm|
|regjsgen|0.7.1|间接依赖|npm|
|color-name|1.1.3|间接依赖|npm|
|@babel/plugin-transform-runtime|7.19.1|直接依赖|npm|
|which|2.0.2|间接依赖|npm|
|jest-matcher-utils|29.2.0|间接依赖|npm|
|esquery|1.4.0|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|human-signals|2.1.0|间接依赖|npm|
|@babel/plugin-transform-destructuring|7.19.4|间接依赖|npm|
|jest-worker|29.2.0|间接依赖|npm|
|unicode-match-property-ecmascript|2.0.0|间接依赖|npm|
|grapheme-splitter|1.0.4|间接依赖|npm|
|path-type|4.0.0|间接依赖|npm|
|resolve|1.20.0|间接依赖|npm|
|@babel/plugin-bugfix-safari-id-destructuring-collision-in-function-expression|7.18.6|间接依赖|npm|
|cross-spawn|7.0.3|间接依赖|npm|
|get-symbol-description|1.0.0|间接依赖|npm|
|is-negative-zero|2.0.2|间接依赖|npm|
|file-entry-cache|6.0.1|间接依赖|npm|
|jest-runtime|29.2.0|间接依赖|npm|
|loose-envify|1.4.0|间接依赖|npm|
|regexpp|3.2.0|间接依赖|npm|
|@babel/plugin-syntax-json-strings|7.8.3|间接依赖|npm|
|@jest/core|29.2.0|间接依赖|npm|
|type-fest|0.21.3|间接依赖|npm|
|@nodelib/fs.scandir|2.1.5|间接依赖|npm|
|object.fromentries|2.0.5|间接依赖|npm|
|array.prototype.flatmap|1.3.0|间接依赖|npm|
|deepmerge|4.2.2|间接依赖|npm|
|istanbul-lib-coverage|3.2.0|间接依赖|npm|
|@babel/helper-split-export-declaration|7.18.6|间接依赖|npm|
|@babel/plugin-proposal-optional-chaining|7.18.9|间接依赖|npm|
|@babel/plugin-transform-modules-amd|7.18.6|间接依赖|npm|
|picomatch|2.3.1|间接依赖|npm|
|babel-plugin-polyfill-corejs3|0.6.0|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|error-ex|1.3.2|间接依赖|npm|
|eslint-config-standard-jsx|11.0.0|间接依赖|npm|
|@babel/plugin-transform-arrow-functions|7.18.6|间接依赖|npm|
|@babel/plugin-transform-template-literals|7.18.9|间接依赖|npm|
|eslint-plugin-es|4.1.0|间接依赖|npm|
|electron-to-chromium|1.4.283|间接依赖|npm|
|jest-message-util|29.2.0|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|load-json-file|5.3.0|间接依赖|npm|
|@babel/plugin-syntax-optional-chaining|7.8.3|间接依赖|npm|
|unbox-primitive|1.0.2|间接依赖|npm|
|regenerator-runtime|0.13.10|间接依赖|npm|
|@babel/plugin-syntax-import-meta|7.10.4|间接依赖|npm|
|is-shared-array-buffer|1.0.2|间接依赖|npm|
|node-int64|0.4.0|间接依赖|npm|
|safe-regex-test|1.0.0|间接依赖|npm|
|@babel/helper-optimise-call-expression|7.18.6|间接依赖|npm|
|babel-plugin-polyfill-regenerator|0.4.1|间接依赖|npm|
|@babel/highlight|7.18.6|间接依赖|npm|
|@babel/plugin-transform-block-scoped-functions|7.18.6|间接依赖|npm|
|@babel/plugin-syntax-numeric-separator|7.10.4|间接依赖|npm|
|ci-info|3.5.0|间接依赖|npm|
|y18n|5.0.8|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|object-keys|1.1.1|间接依赖|npm|
|babel-plugin-istanbul|6.1.1|间接依赖|npm|
|@nicolo-ribaudo/eslint-scope-5-internals|5.1.1-v1|间接依赖|npm|
|@babel/plugin-transform-duplicate-keys|7.18.9|间接依赖|npm|
|jest-changed-files|29.2.0|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|@babel/plugin-proposal-json-strings|7.18.6|间接依赖|npm|
|array-union|2.1.0|直接依赖|npm|
|@babel/helper-create-class-features-plugin|7.19.0|间接依赖|npm|
|@istanbuljs/schema|0.1.3|间接依赖|npm|
|@types/istanbul-lib-report|3.0.0|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|regjsparser|0.9.1|间接依赖|npm|
|@types/babel__traverse|7.18.2|间接依赖|npm|
|deep-is|0.1.4|直接依赖|npm|
|@babel/plugin-proposal-class-properties|7.18.6|间接依赖|npm|
|string-width|4.2.3|间接依赖|npm|
|estraverse|5.3.0|间接依赖|npm|
|object-inspect|1.12.2|间接依赖|npm|
|fast-glob|3.2.12|间接依赖|npm|
|strip-bom|4.0.0|间接依赖|npm|
|jest-snapshot|29.2.0|间接依赖|npm|
|@babel/plugin-transform-typeof-symbol|7.18.9|间接依赖|npm|
|v8-to-istanbul|9.0.1|间接依赖|npm|
|@babel/plugin-transform-sticky-regex|7.18.6|间接依赖|npm|
|@babel/helper-skip-transparent-expression-wrappers|7.18.9|间接依赖|npm|
|prop-types|15.8.1|间接依赖|npm|
|@eslint/eslintrc|1.3.3|间接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|merge-stream|2.0.0|间接依赖|npm|
|p-limit|2.3.0|间接依赖|npm|
|@jridgewell/trace-mapping|0.3.17|间接依赖|npm|
|fast-levenshtein|2.0.6|直接依赖|npm|
|once|1.4.0|间接依赖|npm|
|shebang-regex|3.0.0|间接依赖|npm|
|esrecurse|4.3.0|间接依赖|npm|
|@babel/types|7.19.4|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|@babel/code-frame|7.18.6|间接依赖|npm|
|@jridgewell/resolve-uri|3.1.0|间接依赖|npm|
|@babel/traverse|7.19.4|间接依赖|npm|
|@humanwhocodes/config-array|0.10.7|间接依赖|npm|
|callsites|3.1.0|间接依赖|npm|
|@babel/plugin-syntax-dynamic-import|7.8.3|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|babel-plugin-polyfill-corejs2|0.3.3|间接依赖|npm|
|eslint-import-resolver-node|0.3.6|间接依赖|npm|
|has-symbols|1.0.3|间接依赖|npm|
|jest-circus|29.2.0|间接依赖|npm|
|@babel/helper-create-regexp-features-plugin|7.19.0|间接依赖|npm|
|@babel/plugin-proposal-private-property-in-object|7.18.6|间接依赖|npm|
|@types/yargs-parser|21.0.0|间接依赖|npm|
|gensync|1.0.0-beta.2|间接依赖|npm|
|@babel/plugin-proposal-optional-catch-binding|7.18.6|间接依赖|npm|
|@babel/helper-explode-assignable-expression|7.18.6|间接依赖|npm|
|istanbul-lib-report|3.0.0|间接依赖|npm|
|@babel/plugin-bugfix-v8-spread-parameters-in-optional-chaining|7.18.9|间接依赖|npm|
|wrap-ansi|7.0.0|间接依赖|npm|
|cliui|8.0.1|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|acorn-jsx|5.3.2|间接依赖|npm|
|@babel/helper-builder-binary-assignment-operator-visitor|7.18.9|间接依赖|npm|
|unicode-property-aliases-ecmascript|2.1.0|间接依赖|npm|
|esutils|2.0.3|间接依赖|npm|
|eslint-utils|3.0.0|间接依赖|npm|
|@babel/plugin-transform-modules-commonjs|7.18.6|间接依赖|npm|
|get-stream|6.0.1|间接依赖|npm|
|p-locate|4.1.0|间接依赖|npm|
|@babel/preset-modules|0.1.5|间接依赖|npm|
|@babel/plugin-syntax-jsx|7.18.6|间接依赖|npm|
|@humanwhocodes/module-importer|1.0.1|间接依赖|npm|
|jest-regex-util|29.2.0|间接依赖|npm|
|strip-final-newline|2.0.0|间接依赖|npm|
|@babel/plugin-transform-regenerator|7.18.6|间接依赖|npm|
|@babel/plugin-syntax-logical-assignment-operators|7.10.4|间接依赖|npm|
|@babel/plugin-syntax-import-assertions|7.18.6|间接依赖|npm|
|@jest/expect-utils|29.2.0|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|@babel/plugin-transform-literals|7.18.9|间接依赖|npm|
|sisteransi|1.0.5|间接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|@babel/plugin-transform-property-literals|7.18.6|间接依赖|npm|
|expect|29.2.0|间接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|yargs|17.6.0|间接依赖|npm|
|globals|11.12.0|间接依赖|npm|
|flat-cache|3.0.4|间接依赖|npm|
|emittery|0.10.2|间接依赖|npm|
|has-property-descriptors|1.0.0|间接依赖|npm|
|browserslist|4.21.4|间接依赖|npm|
|@babel/plugin-transform-unicode-regex|7.18.6|间接依赖|npm|
|regenerator-transform|0.15.0|间接依赖|npm|
|@babel/plugin-proposal-numeric-separator|7.18.6|间接依赖|npm|
|lodash.debounce|4.0.8|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|stack-utils|2.0.5|间接依赖|npm|
|lines-and-columns|1.2.4|间接依赖|npm|
|babel-plugin-jest-hoist|29.2.0|间接依赖|npm|
|eslint-plugin-react|7.31.10|间接依赖|npm|
|@types/node|18.11.0|间接依赖|npm|
|has-bigints|1.0.2|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|@istanbuljs/load-nyc-config|1.1.0|间接依赖|npm|
|@babel/helper-compilation-targets|7.19.3|间接依赖|npm|
|globby|13.1.2|间接依赖|npm|
|slash|3.0.0|间接依赖|npm|
|is-symbol|1.0.4|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|tmpl|1.0.5|间接依赖|npm|
|is-string|1.0.7|间接依赖|npm|
|eslint-plugin-import|2.26.0|间接依赖|npm|
|get-package-type|0.1.0|间接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|p-try|2.2.0|间接依赖|npm|
|fastq|1.13.0|间接依赖|npm|
|@babel/plugin-transform-function-name|7.18.9|间接依赖|npm|
|camelcase|5.3.1|间接依赖|npm|
|leven|3.1.0|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|mimic-fn|2.1.0|间接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|@sinclair/typebox|0.24.46|间接依赖|npm|
|acorn|8.8.0|间接依赖|npm|
|jest-diff|29.2.0|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|@babel/helper-wrap-function|7.19.0|间接依赖|npm|
|@babel/plugin-proposal-unicode-property-regex|7.18.6|间接依赖|npm|
|@jest/globals|29.2.0|间接依赖|npm|
|@babel/plugin-syntax-top-level-await|7.14.5|间接依赖|npm|
|@babel/helper-validator-identifier|7.19.1|间接依赖|npm|
|@babel/plugin-transform-parameters|7.18.8|间接依赖|npm|
|@babel/plugin-syntax-export-namespace-from|7.8.3|间接依赖|npm|
|@babel/helper-member-expression-to-functions|7.18.9|间接依赖|npm|
|jest-pnp-resolver|1.2.2|间接依赖|npm|
|jest-haste-map|29.2.0|间接依赖|npm|
|@ampproject/remapping|2.2.0|间接依赖|npm|
|@jridgewell/gen-mapping|0.1.1|间接依赖|npm|
|@types/babel__template|7.4.1|间接依赖|npm|
|@babel/helper-define-polyfill-provider|0.3.3|间接依赖|npm|
|array.prototype.flat|1.3.0|间接依赖|npm|
|parse-json|5.2.0|间接依赖|npm|
|is-callable|1.2.7|间接依赖|npm|
|word-wrap|1.2.3|直接依赖|npm|
|@jest/types|29.2.0|间接依赖|npm|
|to-fast-properties|2.0.0|间接依赖|npm|
|minimist|1.2.7|间接依赖|npm|
|import-fresh|3.3.0|间接依赖|npm|
|@babel/helper-environment-visitor|7.18.9|间接依赖|npm|
|detect-newline|3.1.0|间接依赖|npm|
|pkg-dir|4.2.0|间接依赖|npm|
|execa|5.1.1|间接依赖|npm|
|@sinonjs/fake-timers|9.1.2|间接依赖|npm|
|jest-environment-node|29.2.0|间接依赖|npm|
|@types/babel__core|7.1.19|间接依赖|npm|
|@babel/plugin-transform-unicode-escapes|7.18.10|间接依赖|npm|
|jest-resolve-dependencies|29.2.0|间接依赖|npm|
|is-weakref|1.0.2|间接依赖|npm|
|@types/istanbul-lib-coverage|2.0.4|间接依赖|npm|
|yallist|4.0.0|间接依赖|npm|
|emoji-regex|8.0.0|间接依赖|npm|
|strip-ansi|6.0.1|间接依赖|npm|
|istanbul-lib-source-maps|4.0.1|间接依赖|npm|
|regenerate|1.4.2|间接依赖|npm|
|@babel/helper-annotate-as-pure|7.18.6|间接依赖|npm|
|supports-preserve-symlinks-flag|1.0.0|直接依赖|npm|
|jest-get-type|29.2.0|间接依赖|npm|
|has-tostringtag|1.0.0|间接依赖|npm|
|@babel/plugin-transform-member-expression-literals|7.18.6|间接依赖|npm|
|object.entries|1.1.5|间接依赖|npm|
|@types/yargs|17.0.13|间接依赖|npm|
|merge2|1.4.1|间接依赖|npm|
|jest-mock|29.2.0|间接依赖|npm|
|@babel/plugin-syntax-object-rest-spread|7.8.3|间接依赖|npm|
|cjs-module-lexer|1.2.2|间接依赖|npm|
|@nodelib/fs.walk|1.2.8|间接依赖|npm|
|string.prototype.trimstart|1.0.5|间接依赖|npm|
|buffer-from|1.1.2|间接依赖|npm|
|function.prototype.name|1.1.5|间接依赖|npm|
|istanbul-reports|3.1.5|间接依赖|npm|
|yargs-parser|21.1.1|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|micromatch|4.0.5|间接依赖|npm|
|@types/jest|29.1.2|直接依赖|npm|
|onetime|5.1.2|间接依赖|npm|
|@jest/test-result|29.2.0|间接依赖|npm|
|npm-run-path|4.0.1|间接依赖|npm|
|jest-each|29.2.0|间接依赖|npm|
|@babel/plugin-syntax-nullish-coalescing-operator|7.8.3|间接依赖|npm|
|flatted|3.2.4|间接依赖|npm|
|jest-docblock|29.2.0|间接依赖|npm|
|@babel/helper-remap-async-to-generator|7.18.9|间接依赖|npm|
|@humanwhocodes/object-schema|1.2.1|间接依赖|npm|
|@babel/plugin-proposal-export-namespace-from|7.18.9|间接依赖|npm|
|dedent|0.7.0|间接依赖|npm|
|jest|29.2.0|直接依赖|npm|
|@babel/plugin-syntax-bigint|7.8.3|间接依赖|npm|
|@babel/plugin-syntax-class-static-block|7.14.5|间接依赖|npm|
|is-arrayish|0.2.1|间接依赖|npm|
|@babel/core|7.19.3|间接依赖|npm|
|@bcoe/v8-coverage|0.2.3|间接依赖|npm|
|@babel/helper-string-parser|7.19.4|间接依赖|npm|
|@jest/environment|29.2.0|间接依赖|npm|
|regexp.prototype.flags|1.4.3|间接依赖|npm|
|locate-path|5.0.0|间接依赖|npm|
|json5|2.2.3|间接依赖|npm|
|imurmurhash|0.1.4|间接依赖|npm|
|text-table|0.2.0|间接依赖|npm|
|resolve-from|5.0.0|间接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|diff-sequences|29.2.0|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)