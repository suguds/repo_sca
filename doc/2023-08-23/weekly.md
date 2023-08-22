# ascoders/weekly安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694055693425664000.svg)](https://www.murphysec.com/console/report/1692967565751373824/1694055693425664000)

仓库描述：前端精读周刊。帮你理解最前沿、实用的技术。

仓库地址：[https://github.com/ascoders/weekly](https://github.com/ascoders/weekly)

| star：24947 | watch：1588 | fork：2928 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-14 09:03:58 | 许可证：- |
| 最近检测时间：2023-08-23 02:35:41 | 组件总数：132 | 漏洞总数：3 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|trim <0.0.3 存在正则表达式拒绝服务漏洞|拒绝服务|[MPS-2020-14926](https://www.oscs1024.com/hd/MPS-2020-14926)|CVE-2020-7753|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|minimatch 资源管理错误漏洞|拒绝服务|[MPS-2022-59845](https://www.oscs1024.com/hd/MPS-2022-59845)|CVE-2022-3517|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|minimatch|3.0.4|3.0.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|trim|0.0.1|0.0.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|semver|5.7.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|110|Low|
|ISC|12|Low|
|Apache-2.0|2|Low|
|CC-BY-3.0|1|Low|
|BSD-2-Clause|2|Low|
|BSD-3-Clause|1|Low|
|CC0-1.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|@babel/code-frame|7.14.5|直接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|unist-util-stringify-position|1.1.2|间接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|glob|7.1.7|间接依赖|npm|
|collapse-white-space|1.0.6|间接依赖|npm|
|hosted-git-info|2.8.9|间接依赖|npm|
|semver-compare|1.0.0|间接依赖|npm|
|slash|3.0.0|间接依赖|npm|
|validate-npm-package-license|3.0.4|间接依赖|npm|
|babel-runtime|6.26.0|间接依赖|npm|
|argparse|1.0.10|间接依赖|npm|
|x-is-string|0.1.0|间接依赖|npm|
|husky|3.1.0|直接依赖|npm|
|ci-info|2.0.0|间接依赖|npm|
|esm|3.2.25|直接依赖|npm|
|@types/node|16.4.10|间接依赖|npm|
|cross-spawn|6.0.5|间接依赖|npm|
|p-locate|4.1.0|间接依赖|npm|
|lint-md-cli|0.1.2|直接依赖|npm|
|caller-callsite|2.0.0|间接依赖|npm|
|repeat-string|1.6.1|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|callsites|2.0.0|间接依赖|npm|
|get-stream|4.1.0|间接依赖|npm|
|@types/vfile|3.0.2|间接依赖|npm|
|trough|1.0.5|间接依赖|npm|
|is-stream|1.1.0|间接依赖|npm|
|which|1.3.1|间接依赖|npm|
|babel-polyfill|6.26.0|间接依赖|npm|
|commander|2.20.3|间接依赖|npm|
|lines-and-columns|1.1.6|直接依赖|npm|
|shebang-regex|1.0.0|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|is-whitespace-character|1.0.4|间接依赖|npm|
|remark-parse|6.0.3|间接依赖|npm|
|character-reference-invalid|1.1.4|间接依赖|npm|
|character-entities|1.2.4|间接依赖|npm|
|spdx-exceptions|2.3.0|间接依赖|npm|
|npm-run-path|2.0.2|间接依赖|npm|
|minimatch|3.0.4|间接依赖|npm|
|p-finally|1.0.0|间接依赖|npm|
|@babel/helper-validator-identifier|7.14.9|间接依赖|npm|
|unist-util-remove-position|1.1.4|间接依赖|npm|
|type-fest|0.6.0|间接依赖|npm|
|vfile-location|2.0.6|间接依赖|npm|
|is-arrayish|0.2.1|间接依赖|npm|
|json-parse-even-better-errors|2.3.1|直接依赖|npm|
|unist-util-visit-parents|2.1.2|间接依赖|npm|
|json-parse-better-errors|1.0.2|间接依赖|npm|
|unist-util-visit|1.4.1|间接依赖|npm|
|opencollective-postinstall|2.0.3|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|color-name|1.1.3|间接依赖|npm|
|regenerator-runtime|0.10.5|间接依赖|npm|
|is-plain-obj|1.1.0|间接依赖|npm|
|is-alphabetical|1.0.4|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|@types/unist|2.0.6|间接依赖|npm|
|nice-try|1.0.5|间接依赖|npm|
|p-limit|2.3.0|间接依赖|npm|
|path-key|2.0.1|间接依赖|npm|
|resolve|1.20.0|间接依赖|npm|
|ast-plugin|0.0.7|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|resolve-from|3.0.0|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|lint-md|0.2.0|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|parse-entities|1.2.2|间接依赖|npm|
|@types/normalize-package-data|2.4.1|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|bail|1.0.5|间接依赖|npm|
|state-toggle|1.0.3|间接依赖|npm|
|core-js|2.6.12|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|is-alphanumerical|1.0.4|间接依赖|npm|
|is-word-character|1.0.4|间接依赖|npm|
|cosmiconfig|5.2.1|间接依赖|npm|
|character-entities-legacy|1.1.4|间接依赖|npm|
|is-decimal|1.0.4|间接依赖|npm|
|spdx-expression-parse|3.0.1|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|extend|3.0.2|间接依赖|npm|
|trim|0.0.1|间接依赖|npm|
|error-ex|1.3.2|间接依赖|npm|
|shebang-command|1.2.0|间接依赖|npm|
|markdown-escapes|1.0.4|间接依赖|npm|
|find-up|4.1.0|间接依赖|npm|
|caller-path|2.0.0|间接依赖|npm|
|normalize-package-data|2.5.0|间接依赖|npm|
|is-directory|0.3.1|间接依赖|npm|
|execa|1.0.0|间接依赖|npm|
|signal-exit|3.0.3|间接依赖|npm|
|locate-path|5.0.0|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|xtend|4.0.2|间接依赖|npm|
|path-exists|4.0.0|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|is-hexadecimal|1.0.4|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|js-yaml|3.14.1|间接依赖|npm|
|sprintf-js|1.0.3|间接依赖|npm|
|run-node|1.0.0|间接依赖|npm|
|is-core-module|2.5.0|间接依赖|npm|
|unified|7.1.0|间接依赖|npm|
|@babel/highlight|7.14.5|间接依赖|npm|
|pkg-dir|4.2.0|间接依赖|npm|
|pump|3.0.0|间接依赖|npm|
|trim-trailing-lines|1.1.4|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|vfile|3.0.1|间接依赖|npm|
|unherit|1.1.3|间接依赖|npm|
|@types/vfile-message|2.0.0|间接依赖|npm|
|get-stdin|7.0.0|间接依赖|npm|
|replace-ext|1.0.0|间接依赖|npm|
|spdx-correct|3.1.1|间接依赖|npm|
|spdx-license-ids|3.0.9|间接依赖|npm|
|esprima|4.0.1|间接依赖|npm|
|strip-eof|1.0.0|间接依赖|npm|
|import-fresh|2.0.0|间接依赖|npm|
|please-upgrade-node|3.2.0|间接依赖|npm|
|parse-json|4.0.0|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|end-of-stream|1.4.4|间接依赖|npm|
|semver|5.7.1|间接依赖|npm|
|read-pkg|5.2.0|间接依赖|npm|
|vfile-message|3.0.1|间接依赖|npm|
|is-buffer|2.0.5|间接依赖|npm|
|has|1.0.3|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)