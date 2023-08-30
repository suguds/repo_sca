# denysdovhan/wtfjs安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696955040354099200.svg)](https://www.murphysec.com/console/report/1696955039825616896/1696955040354099200)

仓库描述：🤪 A list of funny and tricky JavaScript examples

仓库地址：[https://github.com/denysdovhan/wtfjs](https://github.com/denysdovhan/wtfjs)

| star：31646 | watch：543 | fork：2391 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-07-07 14:29:48 | 许可证：WTFPL |
| 最近检测时间：2023-08-31 02:36:36 | 组件总数：404 | 漏洞总数：8 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|marked 存在拒绝服务漏洞||[MPS-2021-37038](https://www.oscs1024.com/hd/MPS-2021-37038)|CVE-2022-21680|高危|
|marked 存在拒绝服务漏洞|过度严格的正则表达式|[MPS-2021-37039](https://www.oscs1024.com/hd/MPS-2021-37039)|CVE-2022-21681|高危|
|marked < 0.3.18 存在拒绝服务漏洞||[MPS-2022-12986](https://www.oscs1024.com/hd/MPS-2022-12986)||高危|
|marked 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13861](https://www.oscs1024.com/hd/MPS-2022-13861)||中危|
|marked<0.4.0 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13863](https://www.oscs1024.com/hd/MPS-2022-13863)||中危|
|marked<1.1.1 存在ReDoS漏洞|ReDoS|[MPS-2022-13864](https://www.oscs1024.com/hd/MPS-2022-13864)||中危|
|http-cache-semantics 安全漏洞|ReDoS|[MPS-2022-5164](https://www.oscs1024.com/hd/MPS-2022-5164)|CVE-2022-25881|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|marked|0.3.12|4.0.10|间接依赖|建议修复|C:0|H:3|M:3|L:0|
|http-cache-semantics|4.1.0|4.1.1|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|semver|5.4.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|ISC|37|Low|
|MIT|337|Low|
|BSD-2-Clause|9|Low|
|Apache-2.0|5|Low|
|BSD-3-Clause|2|Low|
|0BSD|1|Low|
|BSD-like|1|Low|
|自定义许可证|1|Low|
|Artistic-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|minimatch|3.1.2|间接依赖|npm|
|lodash.isstring|4.0.1|间接依赖|npm|
|@octokit/request-error|2.1.0|间接依赖|npm|
|bottleneck|2.19.5|间接依赖|npm|
|lodash.escaperegexp|4.1.2|间接依赖|npm|
|argv-formatter|1.0.0|间接依赖|npm|
|mdast-util-footnote|0.1.7|间接依赖|npm|
|globby|11.1.0|间接依赖|npm|
|micromark-extension-gfm-autolink-literal|0.5.7|间接依赖|npm|
|@octokit/request|5.6.3|间接依赖|npm|
|path-exists|4.0.0|间接依赖|npm|
|update-notifier|6.0.2|直接依赖|npm|
|@types/http-cache-semantics|4.0.1|间接依赖|npm|
|@babel/highlight|7.12.13|间接依赖|npm|
|spdx-correct|1.0.2|间接依赖|npm|
|mdast-util-frontmatter|0.2.0|间接依赖|npm|
|jsonparse|1.3.1|间接依赖|npm|
|osenv|0.1.5|间接依赖|npm|
|is-obj|2.0.0|间接依赖|npm|
|@babel/helper-validator-identifier|7.12.11|间接依赖|npm|
|proto-list|1.2.4|间接依赖|npm|
|supports-color|7.2.0|间接依赖|npm|
|prettier|2.8.0|直接依赖|npm|
|os-homedir|1.0.2|间接依赖|npm|
|xtend|4.0.1|间接依赖|npm|
|source-map|0.6.1|间接依赖|npm|
|lowercase-keys|3.0.0|间接依赖|npm|
|json-stringify-safe|5.0.1|间接依赖|npm|
|p-each-series|2.2.0|间接依赖|npm|
|underscore|1.13.3|间接依赖|npm|
|strip-ansi|7.0.1|间接依赖|npm|
|@babel/code-frame|7.12.13|间接依赖|npm|
|@octokit/auth-token|2.5.0|间接依赖|npm|
|xdg-basedir|5.1.0|间接依赖|npm|
|glob|7.2.0|间接依赖|npm|
|lilconfig|2.0.6|间接依赖|npm|
|micromark-extension-gfm|0.3.3|间接依赖|npm|
|mdast-util-gfm|0.1.2|间接依赖|npm|
|handlebars|4.7.7|间接依赖|npm|
|yargs-parser|20.2.9|间接依赖|npm|
|string-argv|0.3.1|间接依赖|npm|
|trim-newlines|3.0.1|间接依赖|npm|
|shebang-regex|3.0.0|间接依赖|npm|
|cross-spawn|7.0.3|间接依赖|npm|
|@octokit/graphql|4.8.0|间接依赖|npm|
|ci-info|3.3.2|间接依赖|npm|
|ansi-escapes|4.3.2|间接依赖|npm|
|package-json|8.1.0|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|aggregate-error|3.1.0|间接依赖|npm|
|longest-streak|2.0.4|间接依赖|npm|
|indent-string|4.0.0|间接依赖|npm|
|traverse|0.6.6|间接依赖|npm|
|is-decimal|1.0.4|间接依赖|npm|
|mdast-util-from-markdown|0.8.5|间接依赖|npm|
|is-yarn-global|0.4.0|间接依赖|npm|
|map-obj|1.0.1|间接依赖|npm|
|escape-goat|4.0.0|间接依赖|npm|
|semver-diff|3.1.1|间接依赖|npm|
|semver|5.4.1|间接依赖|npm|
|rimraf|3.0.2|间接依赖|npm|
|imurmurhash|0.1.4|间接依赖|npm|
|parse-json|5.2.0|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|find-versions|4.0.0|间接依赖|npm|
|stream-combiner2|1.1.1|间接依赖|npm|
|is-plain-object|5.0.0|间接依赖|npm|
|doctoc|2.2.0|直接依赖|npm|
|glob-parent|5.1.2|间接依赖|npm|
|npm-run-path|4.0.1|间接依赖|npm|
|write-file-atomic|3.0.3|间接依赖|npm|
|@types/minimist|1.2.2|间接依赖|npm|
|@semantic-release/release-notes-generator|10.0.3|间接依赖|npm|
|form-data-encoder|1.7.1|间接依赖|npm|
|read-pkg-up|7.0.1|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|@types/parse-json|4.0.0|间接依赖|npm|
|tslib|2.4.1|间接依赖|npm|
|ccount|1.1.0|间接依赖|npm|
|split2|3.2.2|间接依赖|npm|
|yocto-queue|0.1.0|直接依赖|npm|
|table-header|0.2.2|间接依赖|npm|
|is-alphanumerical|1.0.4|间接依赖|npm|
|global-dirs|3.0.0|间接依赖|npm|
|is-number|7.0.0|间接依赖|npm|
|ansi-regex|6.0.1|间接依赖|npm|
|redeyed|1.0.1|间接依赖|npm|
|hook-std|2.0.0|间接依赖|npm|
|issue-parser|6.0.0|间接依赖|npm|
|is-arrayish|0.2.1|间接依赖|npm|
|minimist-options|4.1.0|间接依赖|npm|
|strip-indent|3.0.0|间接依赖|npm|
|@pnpm/npm-conf|1.0.4|直接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|lines-and-columns|1.1.6|间接依赖|npm|
|callsites|3.1.0|间接依赖|npm|
|cli-truncate|3.1.0|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|varsize-string|2.2.2|间接依赖|npm|
|micromark-extension-gfm-table|0.4.3|间接依赖|npm|
|p-reduce|2.1.0|间接依赖|npm|
|http-cache-semantics|4.1.0|间接依赖|npm|
|default-pager|1.1.0|直接依赖|npm|
|load-json-file|4.0.0|间接依赖|npm|
|merge-stream|2.0.0|间接依赖|npm|
|pidtree|0.6.0|间接依赖|npm|
|debug|4.3.4|间接依赖|npm|
|figures|3.2.0|间接依赖|npm|
|is-buffer|2.0.5|间接依赖|npm|
|@pnpm/network.ca-file|1.0.1|间接依赖|npm|
|node-fetch|2.6.7|间接依赖|npm|
|@semantic-release/git|10.0.1|直接依赖|npm|
|@octokit/plugin-paginate-rest|2.17.0|间接依赖|npm|
|lodash.uniqby|4.7.0|间接依赖|npm|
|keyv|4.3.2|间接依赖|npm|
|jsonfile|6.1.0|间接依赖|npm|
|JSONStream|1.3.5|间接依赖|npm|
|shebang-command|2.0.0|间接依赖|npm|
|color-convert|1.9.0|间接依赖|npm|
|conventional-commits-filter|2.0.7|间接依赖|npm|
|repeat-string|1.6.1|间接依赖|npm|
|configstore|6.0.0|间接依赖|npm|
|is-installed-globally|0.4.0|间接依赖|npm|
|cli-cursor|3.1.0|间接依赖|npm|
|import-from|4.0.0|间接依赖|npm|
|url-join|4.0.1|间接依赖|npm|
|lodash.ismatch|4.4.0|间接依赖|npm|
|micromatch|4.0.5|间接依赖|npm|
|read-pkg|5.2.0|间接依赖|npm|
|dot-prop|5.3.0|间接依赖|npm|
|resolve-alpn|1.2.1|间接依赖|npm|
|conventional-changelog-angular|5.0.13|间接依赖|npm|
|delayed-stream|1.0.0|间接依赖|npm|
|@colors/colors|1.5.0|间接依赖|npm|
|mdast-util-to-string|2.0.0|间接依赖|npm|
|@semantic-release/github|8.0.4|间接依赖|npm|
|ignore|5.2.0|间接依赖|npm|
|human-signals|2.1.0|间接依赖|npm|
|wcstring|2.1.1|间接依赖|npm|
|@types/normalize-package-data|2.4.0|间接依赖|npm|
|p-limit|2.3.0|间接依赖|npm|
|cacheable-request|7.0.2|间接依赖|npm|
|inherits|2.0.3|间接依赖|npm|
|readable-stream|2.3.7|间接依赖|npm|
|before-after-hook|2.2.2|间接依赖|npm|
|@octokit/openapi-types|11.2.0|间接依赖|npm|
|@types/keyv|3.1.4|间接依赖|npm|
|into-stream|6.0.0|间接依赖|npm|
|text-table|0.2.0|间接依赖|npm|
|registry-auth-token|4.2.1|间接依赖|npm|
|eastasianwidth|0.2.0|间接依赖|npm|
|type-fest|0.16.0|间接依赖|npm|
|supports-hyperlinks|2.2.0|直接依赖|npm|
|node-emoji|1.11.0|直接依赖|npm|
|p-filter|2.1.0|间接依赖|npm|
|hard-rejection|2.1.0|间接依赖|npm|
|@textlint/ast-node-types|12.1.1|间接依赖|npm|
|colorette|2.0.19|间接依赖|npm|
|error-ex|1.3.1|间接依赖|npm|
|unified|9.2.2|间接依赖|npm|
|neo-async|2.6.2|间接依赖|npm|
|string-width|5.1.2|间接依赖|npm|
|rc|1.2.8|间接依赖|npm|
|lodash.capitalize|4.2.1|间接依赖|npm|
|parent-module|1.0.1|间接依赖|npm|
|parse-entities|2.0.0|间接依赖|npm|
|markdown-table|2.0.0|间接依赖|npm|
|cliui|7.0.4|间接依赖|npm|
|is-path-cwd|2.2.0|间接依赖|npm|
|decamelize|1.2.0|间接依赖|npm|
|validate-npm-package-license|3.0.1|间接依赖|npm|
|temp-dir|2.0.0|间接依赖|npm|
|bail|1.0.5|间接依赖|npm|
|graceful-fs|4.2.10|间接依赖|npm|
|config-chain|1.1.13|间接依赖|npm|
|domelementtype|2.3.0|间接依赖|npm|
|ansicolors|0.3.2|间接依赖|npm|
|is-plain-obj|1.1.0|间接依赖|npm|
|is-glob|4.0.3|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|is-core-module|2.9.0|间接依赖|npm|
|registry-url|6.0.1|间接依赖|npm|
|dateformat|3.0.3|间接依赖|npm|
|redent|3.0.0|间接依赖|npm|
|universalify|2.0.0|间接依赖|npm|
|which|2.0.2|间接依赖|npm|
|has-flag|4.0.0|间接依赖|npm|
|crypto-random-string|2.0.0|间接依赖|npm|
|husky|8.0.2|直接依赖|npm|
|lodash.isplainobject|4.0.6|间接依赖|npm|
|remark-frontmatter|3.0.0|间接依赖|npm|
|@textlint/markdown-to-ast|12.1.1|间接依赖|npm|
|string_decoder|1.1.1|间接依赖|npm|
|cosmiconfig|7.0.1|间接依赖|npm|
|marked|0.3.12|间接依赖|npm|
|wrap-ansi|7.0.0|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|pupa|3.1.0|间接依赖|npm|
|clean-stack|2.2.0|间接依赖|npm|
|yargs|16.2.0|间接依赖|npm|
|semver-regex|3.1.4|间接依赖|npm|
|rfdc|1.3.0|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|micromark-extension-footnote|0.3.2|间接依赖|npm|
|ansi-styles|4.3.0|间接依赖|npm|
|q|1.5.1|间接依赖|npm|
|pify|3.0.0|间接依赖|npm|
|universal-user-agent|6.0.0|间接依赖|npm|
|mdast-util-gfm-strikethrough|0.2.3|间接依赖|npm|
|@octokit/plugin-request-log|1.0.4|间接依赖|npm|
|mimic-response|1.0.1|间接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|mdast-util-to-markdown|0.6.5|间接依赖|npm|
|strip-json-comments|2.0.1|间接依赖|npm|
|listr2|5.0.6|间接依赖|npm|
|java-properties|1.0.2|间接依赖|npm|
|decamelize-keys|1.1.0|间接依赖|npm|
|is-stream|2.0.1|间接依赖|npm|
|@semantic-release/commit-analyzer|9.0.2|间接依赖|npm|
|astral-regex|2.0.0|直接依赖|npm|
|cacheable-lookup|6.0.4|间接依赖|npm|
|@types/retry|0.12.1|间接依赖|npm|
|micromark-extension-gfm-strikethrough|0.6.5|间接依赖|npm|
|mime|3.0.0|间接依赖|npm|
|hosted-git-info|2.8.9|间接依赖|npm|
|array-union|2.1.0|间接依赖|npm|
|fault|1.0.4|间接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|yallist|4.0.0|间接依赖|npm|
|lint-staged|13.0.4|直接依赖|npm|
|@octokit/core|3.6.0|间接依赖|npm|
|json-parse-even-better-errors|2.3.1|间接依赖|npm|
|@sindresorhus/is|4.6.0|间接依赖|npm|
|fast-glob|3.2.11|间接依赖|npm|
|slice-ansi|5.0.0|间接依赖|npm|
|is-path-inside|3.0.2|间接依赖|npm|
|object-inspect|1.12.2|间接依赖|npm|
|htmlparser2|7.2.0|间接依赖|npm|
|arrify|1.0.1|间接依赖|npm|
|domhandler|4.3.1|间接依赖|npm|
|cardinal|1.0.0|间接依赖|npm|
|is-text-path|1.0.1|间接依赖|npm|
|@types/cacheable-request|6.0.2|间接依赖|npm|
|domutils|2.8.0|间接依赖|npm|
|end-of-stream|1.4.4|间接依赖|npm|
|color-name|1.1.4|间接依赖|npm|
|env-ci|5.5.0|间接依赖|npm|
|duplexer2|0.1.4|间接依赖|npm|
|fs-extra|10.1.0|间接依赖|npm|
|@octokit/plugin-rest-endpoint-methods|5.13.0|间接依赖|npm|
|retry|0.13.1|间接依赖|npm|
|msee|0.3.5|直接依赖|npm|
|path-type|4.0.0|间接依赖|npm|
|cli-boxes|3.0.0|间接依赖|npm|
|mdast-util-find-and-replace|1.1.1|间接依赖|npm|
|get-stream|6.0.1|间接依赖|npm|
|p-locate|4.1.0|间接依赖|npm|
|got|12.1.0|间接依赖|npm|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|semantic-release|19.0.5|直接依赖|npm|
|camelcase|6.3.0|间接依赖|npm|
|y18n|5.0.8|间接依赖|npm|
|combined-stream-wait-for-it|1.1.0|间接依赖|npm|
|path-key|3.1.1|间接依赖|npm|
|micromark-extension-gfm-tagfilter|0.3.0|间接依赖|npm|
|wordwrap|1.0.0|间接依赖|npm|
|unist-util-stringify-position|2.0.3|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|defer-to-connect|2.0.1|间接依赖|npm|
|emoji-regex|6.1.3|间接依赖|npm|
|fromentries|1.3.2|间接依赖|npm|
|character-reference-invalid|1.1.4|间接依赖|npm|
|remark-gfm|1.0.0|间接依赖|npm|
|is-npm|6.0.0|间接依赖|npm|
|boxen|7.0.0|间接依赖|npm|
|micromark-extension-frontmatter|0.2.2|间接依赖|npm|
|entities|1.1.1|间接依赖|npm|
|@semantic-release/npm|9.0.1|间接依赖|npm|
|pump|3.0.0|直接依赖|npm|
|conventional-commits-parser|3.2.4|间接依赖|npm|
|@nodelib/fs.stat|2.0.5|间接依赖|npm|
|core-util-is|1.0.2|间接依赖|npm|
|tempy|1.0.1|间接依赖|npm|
|nerf-dart|1.0.0|间接依赖|npm|
|@nodelib/fs.walk|1.2.8|间接依赖|npm|
|through2|4.0.2|间接依赖|npm|
|latest-version|7.0.0|间接依赖|npm|
|is-ci|3.0.1|间接依赖|npm|
|through|2.3.8|间接依赖|npm|
|modify-values|1.0.1|间接依赖|npm|
|json-parse-better-errors|1.0.2|直接依赖|npm|
|format|0.2.2|间接依赖|npm|
|pkg-conf|2.1.0|间接依赖|npm|
|yaml|1.10.2|间接依赖|npm|
|import-lazy|4.0.0|间接依赖|npm|
|execa|5.1.1|间接依赖|npm|
|onetime|5.1.2|间接依赖|npm|
|@szmarczak/http-timer|5.0.1|间接依赖|npm|
|dir-glob|3.0.1|间接依赖|npm|
|os-tmpdir|1.0.2|间接依赖|npm|
|@types/unist|2.0.6|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|https-proxy-agent|5.0.1|间接依赖|npm|
|signale|1.4.0|间接依赖|npm|
|strip-bom|3.0.0|间接依赖|npm|
|signal-exit|3.0.7|间接依赖|npm|
|extend|3.0.2|间接依赖|npm|
|restore-cursor|3.1.0|间接依赖|npm|
|@types/responselike|1.0.0|间接依赖|npm|
|ini|1.3.8|间接依赖|npm|
|picomatch|2.3.1|间接依赖|npm|
|p-is-promise|3.0.0|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|log-update|4.0.0|间接依赖|npm|
|responselike|2.0.0|间接依赖|npm|
|array-ify|1.0.0|间接依赖|npm|
|deep-extend|0.6.0|间接依赖|npm|
|mdast-util-gfm-table|0.1.6|间接依赖|npm|
|isarray|1.0.0|间接依赖|npm|
|http2-wrapper|2.1.11|间接依赖|npm|
|p-map|4.0.0|间接依赖|npm|
|kind-of|6.0.3|间接依赖|npm|
|widest-line|4.0.1|间接依赖|npm|
|@nodelib/fs.scandir|2.1.5|间接依赖|npm|
|import-fresh|3.3.0|间接依赖|npm|
|git-log-parser|1.2.0|间接依赖|npm|
|@tootallnate/once|2.0.0|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|p-cancelable|3.0.0|间接依赖|npm|
|anchor-markdown-header|0.5.7|间接依赖|npm|
|process-nextick-args|2.0.1|间接依赖|npm|
|is-typedarray|1.0.0|间接依赖|npm|
|normalize-package-data|2.5.0|间接依赖|npm|
|remark-parse|9.0.0|间接依赖|npm|
|locate-path|5.0.0|间接依赖|npm|
|remark-footnotes|3.0.0|间接依赖|npm|
|resolve|1.19.0|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|fastq|1.13.0|间接依赖|npm|
|dom-serializer|1.4.1|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|merge2|1.4.1|间接依赖|npm|
|camelcase-keys|6.2.2|间接依赖|npm|
|meow|10.1.4|间接依赖|npm|
|abbrev|1.1.1|间接依赖|npm|
|is-hexadecimal|1.0.4|间接依赖|npm|
|update-section|0.3.3|间接依赖|npm|
|@types/node|18.0.0|间接依赖|npm|
|mimic-fn|2.1.0|间接依赖|npm|
|@octokit/rest|18.12.0|间接依赖|npm|
|find-up|4.1.0|间接依赖|npm|
|npm|8.12.0|间接依赖|npm|
|vfile|4.2.1|间接依赖|npm|
|spdx-expression-parse|1.0.4|间接依赖|npm|
|mdast-util-gfm-autolink-literal|0.1.3|间接依赖|npm|
|decompress-response|6.0.0|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|quick-lru|4.0.1|间接依赖|npm|
|slash|3.0.0|间接依赖|npm|
|p-retry|4.6.1|间接依赖|npm|
|agent-base|6.0.2|间接依赖|npm|
|has-yarn|3.0.0|间接依赖|npm|
|minimist|1.2.6|间接依赖|npm|
|http-proxy-agent|5.0.0|间接依赖|npm|
|cli-table3|0.6.2|间接依赖|npm|
|wcsize|1.0.0|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|@octokit/types|6.34.0|间接依赖|npm|
|split|1.0.1|间接依赖|npm|
|clone-response|1.0.2|间接依赖|npm|
|nopt|4.0.3|间接依赖|npm|
|zwitch|1.0.5|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|uglify-js|3.15.4|间接依赖|npm|
|typedarray-to-buffer|3.1.5|间接依赖|npm|
|commander|9.4.1|间接依赖|npm|
|conventional-changelog-writer|5.0.1|间接依赖|npm|
|compare-func|2.0.0|间接依赖|npm|
|from2|2.3.0|间接依赖|npm|
|strip-final-newline|2.0.0|间接依赖|npm|
|@octokit/endpoint|6.0.12|间接依赖|npm|
|esprima|3.0.0|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|mdast-util-gfm-task-list-item|0.1.6|间接依赖|npm|
|deprecation|2.3.1|间接依赖|npm|
|micromark-extension-gfm-task-list-item|0.3.3|间接依赖|npm|
|text-extensions|1.9.0|间接依赖|npm|
|vfile-message|2.0.4|间接依赖|npm|
|rxjs|7.5.7|间接依赖|npm|
|character-entities|1.2.4|间接依赖|npm|
|@types/mdast|3.0.10|间接依赖|npm|
|ansi-align|3.0.1|间接依赖|npm|
|character-entities-legacy|1.1.4|间接依赖|npm|
|normalize-url|6.1.0|间接依赖|npm|
|resolve-from|5.0.0|间接依赖|npm|
|unique-string|2.0.0|间接依赖|npm|
|micromark|2.11.4|间接依赖|npm|
|del|6.0.0|间接依赖|npm|
|spawn-error-forwarder|1.0.0|间接依赖|npm|
|@semantic-release/error|3.0.0|间接依赖|npm|
|lru-cache|6.0.0|直接依赖|npm|
|trough|1.0.5|间接依赖|npm|
|chalk|5.1.2|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)