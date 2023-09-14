# photonstorm/phaser安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1702391567532818432.svg)](https://www.murphysec.com/console/report/1702391566907867136/1702391567532818432)

仓库描述：Phaser is a fun, free and fast 2D game framework for making HTML5 games for desktop and mobile web browsers, supporting Canvas and WebGL rendering.

仓库地址：[https://github.com/photonstorm/phaser](https://github.com/photonstorm/phaser)

| star：35192 | watch：1247 | fork：7058 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-14 18:47:36 | 许可证：MIT |
| 最近检测时间：2023-09-15 02:39:59 | 组件总数：275 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|word-wrap 安全漏洞|ReDoS|[MPS-2023-5109](https://www.oscs1024.com/hd/MPS-2023-5109)|CVE-2023-26115|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|word-wrap|1.2.3|1.2.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|semver|6.3.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|219|Low|
|ISC|18|Low|
|Apache-2.0|10|Low|
|BSD-3-Clause|5|Low|
|BSD-2-Clause|10|Low|
|Unlicense|1|Low|
|Python-2.0|1|Low|
|CC-BY-4.0|1|Low|
|CC0-1.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|object-assign|4.1.1|间接依赖|npm|
|@nodelib/fs.stat|2.0.5|间接依赖|npm|
|onetime|5.1.2|间接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|optionator|0.9.1|间接依赖|npm|
|is-number|7.0.0|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|@xtuc/long|4.2.2|间接依赖|npm|
|xdg-basedir|4.0.0|间接依赖|npm|
|remove-files-webpack-plugin|1.5.0|直接依赖|npm|
|punycode|2.1.1|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|source-map|0.7.4|间接依赖|npm|
|make-dir|3.1.0|间接依赖|npm|
|glob|7.2.3|间接依赖|npm|
|color-name|1.1.4|间接依赖|npm|
|pify|4.0.1|间接依赖|npm|
|esquery|1.4.2|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|resolve-cwd|3.0.0|间接依赖|npm|
|xmlcreate|2.0.4|间接依赖|npm|
|json-stable-stringify-without-jsonify|1.0.1|间接依赖|npm|
|envinfo|7.8.1|间接依赖|npm|
|reusify|1.0.4|间接依赖|npm|
|import-local|3.1.0|间接依赖|npm|
|cross-spawn|7.0.3|间接依赖|npm|
|get-stream|5.2.0|间接依赖|npm|
|mime-types|2.1.35|间接依赖|npm|
|clone-deep|4.0.1|间接依赖|npm|
|pinkie-promise|2.0.1|间接依赖|npm|
|vivid-cli|1.1.2|直接依赖|npm|
|dir-glob|2.2.2|直接依赖|npm|
|@jridgewell/resolve-uri|3.1.0|间接依赖|npm|
|doctrine|3.0.0|间接依赖|npm|
|webpack-shell-plugin|0.5.0|直接依赖|npm|
|tapable|2.2.1|间接依赖|npm|
|@types/glob|7.2.0|间接依赖|npm|
|indent-string|4.0.0|间接依赖|npm|
|esutils|2.0.3|间接依赖|npm|
|events|3.3.0|间接依赖|npm|
|enhanced-resolve|5.10.0|间接依赖|npm|
|@types/node|18.11.9|间接依赖|npm|
|@webassemblyjs/helper-api-error|1.11.1|间接依赖|npm|
|globals|13.20.0|间接依赖|npm|
|mime-db|1.52.0|间接依赖|npm|
|dts-dom|3.7.0|直接依赖|npm|
|process|0.11.10|间接依赖|npm|
|flat-cache|3.0.4|间接依赖|npm|
|@types/offscreencanvas|2019.7.0|直接依赖|npm|
|resolve|1.22.1|间接依赖|npm|
|picocolors|1.0.0|间接依赖|npm|
|@webassemblyjs/helper-wasm-bytecode|1.11.1|间接依赖|npm|
|mount-point|3.0.0|间接依赖|npm|
|path-type|3.0.0|间接依赖|npm|
|@webassemblyjs/wasm-opt|1.11.1|间接依赖|npm|
|@webassemblyjs/ast|1.11.1|间接依赖|npm|
|schema-utils|3.1.1|间接依赖|npm|
|util|0.10.4|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|catharsis|0.9.0|间接依赖|npm|
|xdg-trashdir|3.1.0|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|@webassemblyjs/wasm-gen|1.11.1|间接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.14|间接依赖|npm|
|strip-ansi|6.0.1|间接依赖|npm|
|node-sloc|0.2.1|直接依赖|npm|
|@discoveryjs/json-ext|0.5.7|间接依赖|npm|
|picomatch|2.3.1|间接依赖|npm|
|@webassemblyjs/wast-printer|1.11.1|间接依赖|npm|
|uc.micro|1.0.6|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|@types/webpack|5.28.0|间接依赖|npm|
|eslint-visitor-keys|3.4.0|间接依赖|npm|
|eslint-plugin-es5|1.5.0|直接依赖|npm|
|execa|2.1.0|间接依赖|npm|
|eventemitter3|5.0.0|直接依赖|npm|
|ignore|5.2.4|间接依赖|npm|
|@xtuc/ieee754|1.2.0|间接依赖|npm|
|slash|1.0.0|直接依赖|npm|
|trash|7.2.0|间接依赖|npm|
|browserslist|4.21.4|间接依赖|npm|
|levn|0.4.1|间接依赖|npm|
|requizzle|0.2.3|间接依赖|npm|
|loader-runner|4.3.0|间接依赖|npm|
|linkify-it|3.0.3|间接依赖|npm|
|markdown-it-anchor|8.6.5|间接依赖|npm|
|neo-async|2.6.2|间接依赖|npm|
|serialize-javascript|6.0.1|间接依赖|npm|
|taffydb|2.6.2|间接依赖|npm|
|natural-compare|1.4.0|间接依赖|npm|
|bluebird|3.7.2|间接依赖|npm|
|is-path-in-cwd|2.1.0|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|commander|2.20.3|间接依赖|npm|
|merge-stream|2.0.0|间接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|jsdoc|3.6.11|直接依赖|npm|
|json-parse-even-better-errors|2.3.1|间接依赖|npm|
|path|0.12.7|直接依赖|npm|
|exports-loader|4.0.0|直接依赖|npm|
|supports-color|7.2.0|间接依赖|npm|
|@eslint/js|8.38.0|间接依赖|npm|
|@eslint-community/regexpp|4.4.0|间接依赖|npm|
|fs-extra|11.1.1|直接依赖|npm|
|webpack-merge|5.8.0|间接依赖|npm|
|@types/json-schema|7.0.11|间接依赖|npm|
|typescript|5.0.4|直接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|is-core-module|2.11.0|间接依赖|npm|
|file-entry-cache|6.0.1|间接依赖|npm|
|@types/eslint|8.4.10|间接依赖|npm|
|signal-exit|3.0.7|间接依赖|npm|
|debug|4.3.4|间接依赖|npm|
|micromatch|4.0.5|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|isobject|3.0.1|间接依赖|npm|
|acorn-import-assertions|1.8.0|间接依赖|npm|
|uuid|8.3.2|间接依赖|npm|
|@webpack-cli/configtest|2.0.1|间接依赖|npm|
|js-yaml|4.1.0|间接依赖|npm|
|@types/minimatch|5.1.2|间接依赖|npm|
|shallow-clone|3.0.1|间接依赖|npm|
|randombytes|2.1.0|间接依赖|npm|
|p-map|2.1.0|间接依赖|npm|
|argparse|2.0.1|间接依赖|npm|
|js-sdsl|4.1.5|间接依赖|npm|
|interpret|3.1.1|间接依赖|npm|
|type-check|0.4.0|间接依赖|npm|
|mkdirp|1.0.4|间接依赖|npm|
|eslint|8.38.0|直接依赖|npm|
|@eslint/eslintrc|2.0.2|间接依赖|npm|
|@nodelib/fs.walk|1.2.8|间接依赖|npm|
|queue-microtask|1.2.3|间接依赖|npm|
|pkg-dir|4.2.0|间接依赖|npm|
|@webassemblyjs/ieee754|1.11.1|间接依赖|npm|
|clean-stack|2.2.0|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|caniuse-lite|1.0.30001431|间接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|@eslint-community/eslint-utils|4.2.0|间接依赖|npm|
|is-stream|2.0.1|间接依赖|npm|
|grapheme-splitter|1.0.4|间接依赖|npm|
|phaser3spectorjs|0.0.8|直接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|yocto-queue|0.1.0|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|jest-worker|27.5.1|间接依赖|npm|
|@webassemblyjs/leb128|1.11.1|间接依赖|npm|
|pinkie|2.0.4|间接依赖|npm|
|@nodelib/fs.scandir|2.1.5|间接依赖|npm|
|ansi-styles|4.3.0|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|ajv|6.12.6|间接依赖|npm|
|@webassemblyjs/floating-point-hex-parser|1.11.1|间接依赖|npm|
|update-browserslist-db|1.0.10|间接依赖|npm|
|fastq|1.13.0|间接依赖|npm|
|underscore|1.13.6|间接依赖|npm|
|move-file|2.1.0|间接依赖|npm|
|esrecurse|4.3.0|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|strip-json-comments|3.1.1|间接依赖|npm|
|word-wrap|1.2.3|间接依赖|npm|
|is-plain-object|2.0.4|间接依赖|npm|
|os-homedir|1.0.2|间接依赖|npm|
|es-module-lexer|1.2.1|间接依赖|npm|
|universalify|2.0.0|间接依赖|npm|
|@types/eslint-scope|3.7.4|间接依赖|npm|
|@types/mdurl|1.0.2|间接依赖|npm|
|@webassemblyjs/helper-wasm-section|1.11.1|间接依赖|npm|
|which|2.0.2|间接依赖|npm|
|@jridgewell/source-map|0.3.2|间接依赖|npm|
|@types/estree|1.0.0|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|p-finally|2.0.1|间接依赖|npm|
|path-is-inside|1.0.2|直接依赖|npm|
|imurmurhash|0.1.4|间接依赖|npm|
|@humanwhocodes/config-array|0.11.8|间接依赖|npm|
|rimraf|2.7.1|间接依赖|npm|
|aggregate-error|3.1.0|直接依赖|npm|
|is-path-inside|3.0.3|间接依赖|npm|
|@webpack-cli/serve|2.0.1|间接依赖|npm|
|webpack-sources|3.2.3|间接依赖|npm|
|marked|4.2.2|间接依赖|npm|
|chrome-trace-event|1.0.3|间接依赖|npm|
|electron-to-chromium|1.4.284|间接依赖|npm|
|path-key|3.1.1|间接依赖|npm|
|terser|5.16.6|间接依赖|npm|
|strip-final-newline|2.0.0|间接依赖|npm|
|@jridgewell/trace-mapping|0.3.17|间接依赖|npm|
|strip-comments|2.0.1|间接依赖|npm|
|wildcard|2.0.0|间接依赖|npm|
|@sindresorhus/df|3.1.1|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|estraverse|5.3.0|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|source-map-support|0.5.21|间接依赖|npm|
|glob-parent|6.0.2|间接依赖|npm|
|clean-webpack-plugin|4.0.0|直接依赖|npm|
|watchpack|2.4.0|间接依赖|npm|
|glob-to-regexp|0.4.1|间接依赖|npm|
|markdown-it|12.3.2|间接依赖|npm|
|entities|2.1.0|间接依赖|npm|
|array-uniq|1.0.3|间接依赖|npm|
|mdurl|1.0.1|间接依赖|npm|
|webpack|5.79.0|间接依赖|npm|
|@webpack-cli/info|2.0.1|间接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|imports-loader|4.0.1|直接依赖|npm|
|@stroncium/procfs|1.2.1|间接依赖|npm|
|lodash.merge|4.6.2|间接依赖|npm|
|p-limit|3.1.0|间接依赖|npm|
|acorn-jsx|5.3.2|间接依赖|npm|
|kind-of|6.0.3|间接依赖|npm|
|supports-preserve-symlinks-flag|1.0.0|间接依赖|npm|
|array-union|1.0.2|间接依赖|npm|
|has-flag|4.0.0|间接依赖|npm|
|@types/linkify-it|3.0.2|间接依赖|npm|
|ajv-keywords|3.5.2|间接依赖|npm|
|shebang-regex|3.0.0|间接依赖|npm|
|acorn|8.8.1|间接依赖|npm|
|webpack-cli|5.0.1|直接依赖|npm|
|@webassemblyjs/wasm-parser|1.11.1|间接依赖|npm|
|run-parallel|1.2.0|间接依赖|npm|
|del|4.1.1|间接依赖|npm|
|type-fest|0.20.2|间接依赖|npm|
|text-table|0.2.0|间接依赖|npm|
|find-up|5.0.0|间接依赖|npm|
|is-glob|4.0.3|间接依赖|npm|
|shebang-command|2.0.0|间接依赖|npm|
|eslint-scope|7.1.1|间接依赖|npm|
|minimist|1.2.7|间接依赖|npm|
|colorette|2.0.19|间接依赖|npm|
|semver|6.3.0|间接依赖|npm|
|@webassemblyjs/utf8|1.11.1|间接依赖|npm|
|deep-is|0.1.4|间接依赖|npm|
|parent-module|1.0.1|间接依赖|npm|
|@humanwhocodes/module-importer|1.0.1|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|node-releases|2.0.6|间接依赖|npm|
|resolve-from|4.0.0|间接依赖|npm|
|user-home|2.0.0|间接依赖|npm|
|prelude-ls|1.2.1|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|@webassemblyjs/helper-numbers|1.11.1|间接依赖|npm|
|color-convert|2.0.1|间接依赖|npm|
|globby|6.1.0|间接依赖|npm|
|path-exists|4.0.0|间接依赖|npm|
|@humanwhocodes/object-schema|1.2.1|间接依赖|npm|
|@webassemblyjs/wasm-edit|1.11.1|间接依赖|npm|
|terser-webpack-plugin|5.3.7|间接依赖|npm|
|chalk|4.1.2|间接依赖|npm|
|npm-run-path|3.1.0|间接依赖|npm|
|flatted|3.2.7|间接依赖|npm|
|p-locate|5.0.0|间接依赖|npm|
|@webassemblyjs/helper-buffer|1.11.1|间接依赖|npm|
|graceful-fs|4.2.10|间接依赖|npm|
|escape-string-regexp|4.0.0|间接依赖|npm|
|fast-levenshtein|2.0.6|间接依赖|npm|
|is-path-cwd|2.2.0|间接依赖|npm|
|@types/markdown-it|12.2.3|间接依赖|npm|
|import-fresh|3.3.0|间接依赖|npm|
|@babel/parser|7.20.3|间接依赖|npm|
|callsites|3.1.0|间接依赖|npm|
|js2xmlparser|4.0.2|间接依赖|npm|
|klaw|3.0.0|间接依赖|npm|
|locate-path|6.0.0|间接依赖|npm|
|rechoir|0.8.0|间接依赖|npm|
|espree|9.5.1|间接依赖|npm|
|p-try|2.2.0|直接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|jsonfile|6.1.0|间接依赖|npm|
|@types/source-map|0.5.7|直接依赖|npm|
|fastest-levenshtein|1.0.16|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)