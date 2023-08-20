# doocs/leetcode安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1693322945277747200.svg)](https://www.murphysec.com/console/report/1693322945239998464/1693322945277747200)

仓库描述：😏 LeetCode solutions in any programming language | 多种编程语言实现 LeetCode、《剑指 Offer（第 2 版）》、《程序员面试金典（第 6 版）》题解

仓库地址：[https://github.com/doocs/leetcode](https://github.com/doocs/leetcode)

| star：22919 | watch：275 | fork：4143 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-20 13:05:10 | 许可证：CC-BY-SA-4.0 |
| 最近检测时间：2023-08-21 02:07:12 | 组件总数：348 | 漏洞总数：5 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|marked 存在拒绝服务漏洞||[MPS-2021-37038](https://www.oscs1024.com/hd/MPS-2021-37038)|CVE-2022-21680|高危|
|marked 存在拒绝服务漏洞|过度严格的正则表达式|[MPS-2021-37039](https://www.oscs1024.com/hd/MPS-2021-37039)|CVE-2022-21681|高危|
|marked 存在拒绝服务漏洞|拒绝服务|[MPS-2021-9993](https://www.oscs1024.com/hd/MPS-2021-9993)|CVE-2021-21306|高危|
|got 存在打开重定向漏洞|跨站重定向|[MPS-2022-19247](https://www.oscs1024.com/hd/MPS-2022-19247)|CVE-2022-33987|中危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|marked|1.2.9|4.0.10|间接依赖|可选修复|C:0|H:3|M:0|L:0|
|semver|6.3.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|got|9.6.0|12.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|283|Low|
|ISC|32|Low|
|Apache-2.0|7|Low|
|BSD-2-Clause|6|Low|
|BSD-3-Clause|3|Low|
|Python-2.0|1|Low|
|0BSD|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|json-parse-even-better-errors|2.3.1|间接依赖|npm|
|error-ex|1.3.2|间接依赖|npm|
|@commitlint/types|17.4.4|间接依赖|npm|
|send|0.18.0|间接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|is-installed-globally|0.3.2|间接依赖|npm|
|glob|7.2.3|间接依赖|npm|
|@cspotcode/source-map-support|0.8.1|间接依赖|npm|
|@commitlint/read|17.5.1|间接依赖|npm|
|unique-string|2.0.0|间接依赖|npm|
|execa|7.1.1|间接依赖|npm|
|registry-auth-token|4.2.2|间接依赖|npm|
|make-error|1.3.6|间接依赖|npm|
|debug|2.6.9|间接依赖|npm|
|statuses|1.5.0|间接依赖|npm|
|urllib3|1.26.15|间接依赖|pip|
|js-yaml|4.1.0|间接依赖|npm|
|url-parse-lax|3.0.0|间接依赖|npm|
|has-ansi|2.0.0|直接依赖|npm|
|yargs-parser|18.1.3|间接依赖|npm|
|conventional-changelog-angular|5.0.13|间接依赖|npm|
|cosmiconfig-typescript-loader|4.3.0|间接依赖|npm|
|validate-npm-package-license|3.0.4|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|aggregate-error|3.1.0|间接依赖|npm|
|yargs|15.4.1|间接依赖|npm|
|get-port|5.1.1|间接依赖|npm|
|require-from-string|2.0.2|间接依赖|npm|
|configstore|5.0.1|间接依赖|npm|
|which-module|2.0.1|间接依赖|npm|
|@commitlint/parse|17.6.5|间接依赖|npm|
|@commitlint/format|17.4.4|间接依赖|npm|
|@commitlint/config-validator|17.4.4|间接依赖|npm|
|parseurl|1.3.3|间接依赖|npm|
|path-type|4.0.0|间接依赖|npm|
|fsevents|2.3.2|间接依赖|npm|
|conventional-changelog-conventionalcommits|5.0.0|间接依赖|npm|
|glob-parent|5.1.2|间接依赖|npm|
|graceful-fs|4.2.11|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|object-inspect|1.12.3|间接依赖|npm|
|escape-goat|2.1.1|间接依赖|npm|
|import-fresh|3.3.0|间接依赖|npm|
|cacheable-request|6.1.0|间接依赖|npm|
|end-of-stream|1.4.4|间接依赖|npm|
|signal-exit|3.0.7|间接依赖|npm|
|text-extensions|1.9.0|间接依赖|npm|
|rfdc|1.3.0|间接依赖|npm|
|arg|4.1.3|间接依赖|npm|
|@commitlint/cli|17.6.5|直接依赖|npm|
|acorn|8.8.2|间接依赖|npm|
|@babel/highlight|7.18.6|间接依赖|npm|
|mimic-response|1.0.1|间接依赖|npm|
|strip-ansi|7.1.0|间接依赖|npm|
|lines-and-columns|1.2.4|间接依赖|npm|
|@commitlint/config-conventional|17.6.5|直接依赖|npm|
|diff|4.0.2|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|read-pkg|5.2.0|间接依赖|npm|
|prettier|2.8.8|间接依赖|npm|
|livereload|0.9.3|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|http-errors|2.0.0|间接依赖|npm|
|node-fetch|2.6.11|间接依赖|npm|
|p-defer|1.0.0|间接依赖|npm|
|hard-rejection|2.1.0|间接依赖|npm|
|conventional-commits-parser|3.2.4|间接依赖|npm|
|@commitlint/lint|17.6.5|间接依赖|npm|
|imurmurhash|0.1.4|间接依赖|npm|
|camelcase|5.3.1|间接依赖|npm|
|decamelize-keys|1.1.1|间接依赖|npm|
|strip-indent|3.0.0|间接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|path-exists|4.0.0|间接依赖|npm|
|black|23.3.0|间接依赖|pip|
|opts|2.0.2|间接依赖|npm|
|require-main-filename|2.0.0|间接依赖|npm|
|p-map|4.0.0|间接依赖|npm|
|yaml|2.3.1|间接依赖|npm|
|range-parser|1.2.1|间接依赖|npm|
|p-cancelable|1.1.0|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|micromatch|4.0.5|间接依赖|npm|
|tweezer.js|1.5.0|间接依赖|npm|
|is-typedarray|1.0.0|间接依赖|npm|
|p-event|4.2.0|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|lodash.startcase|4.4.0|间接依赖|npm|
|figlet|1.6.0|间接依赖|npm|
|parent-require|1.0.0|间接依赖|npm|
|write-file-atomic|3.0.3|间接依赖|npm|
|fresh|0.5.2|间接依赖|npm|
|log-update|4.0.0|间接依赖|npm|
|connect-livereload|0.6.1|间接依赖|npm|
|@szmarczak/http-timer|1.1.2|间接依赖|npm|
|which|2.0.2|间接依赖|npm|
|ini|1.3.7|间接依赖|npm|
|cli-cursor|3.1.0|间接依赖|npm|
|@tsconfig/node10|1.0.9|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|lodash.isplainobject|4.0.6|间接依赖|npm|
|depd|2.0.0|间接依赖|npm|
|readable-stream|3.6.2|间接依赖|npm|
|registry-url|5.1.0|间接依赖|npm|
|acorn-walk|8.2.0|间接依赖|npm|
|indent-string|4.0.0|间接依赖|npm|
|picomatch|2.3.1|间接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.15|间接依赖|npm|
|is-obj|2.0.0|间接依赖|npm|
|astral-regex|2.0.0|直接依赖|npm|
|@types/minimist|1.2.2|间接依赖|npm|
|abstractmethod||间接依赖|pip|
|prettier-plugin-sql-cst|0.8.2|直接依赖|npm|
|string-width|5.1.2|间接依赖|npm|
|setprototypeof|1.2.0|间接依赖|npm|
|husky|8.0.3|直接依赖|npm|
|serve-static|1.15.0|间接依赖|npm|
|p-limit|2.3.0|间接依赖|npm|
|slice-ansi|5.0.0|间接依赖|npm|
|connect-history-api-fallback|1.6.0|间接依赖|npm|
|make-dir|3.1.0|间接依赖|npm|
|color-name|1.1.3|间接依赖|npm|
|is-binary-path|2.1.0|间接依赖|npm|
|cross-spawn|7.0.3|间接依赖|npm|
|resolve-global|1.0.0|间接依赖|npm|
|through2|4.0.2|间接依赖|npm|
|tr46|0.0.3|间接依赖|npm|
|to-readable-stream|1.0.0|间接依赖|npm|
|@tsconfig/node16|1.0.4|间接依赖|npm|
|Tuple||间接依赖|pip|
|pidtree|0.6.0|间接依赖|npm|
|opencollective-postinstall|2.0.3|间接依赖|npm|
|jsonparse|1.3.1|间接依赖|npm|
|map-obj|4.3.0|间接依赖|npm|
|@tsconfig/node14|1.0.3|间接依赖|npm|
|@commitlint/rules|17.6.5|间接依赖|npm|
|finalhandler|1.1.2|间接依赖|npm|
|update-notifier|4.1.3|间接依赖|npm|
|is-glob|4.0.3|间接依赖|npm|
|yn|3.1.1|间接依赖|npm|
|@commitlint/to-lines|17.4.0|间接依赖|npm|
|@babel/code-frame|7.21.4|间接依赖|npm|
|lint-staged|13.2.2|直接依赖|npm|
|semver-diff|3.1.1|间接依赖|npm|
|cliui|6.0.0|间接依赖|npm|
|get-stream|6.0.1|间接依赖|npm|
|p-timeout|3.2.0|间接依赖|npm|
|Requests|2.31.0|间接依赖|pip|
|y18n|4.0.3|间接依赖|npm|
|is-arrayish|0.2.1|间接依赖|npm|
|is-number|7.0.0|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|normalize-package-data|3.0.3|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|escalade|3.1.1|直接依赖|npm|
|sortedcontainers|2.4.0|间接依赖|pip|
|restore-cursor|3.1.0|间接依赖|npm|
|lowercase-keys|1.0.1|间接依赖|npm|
|List||间接依赖|pip|
|@commitlint/execute-rule|17.4.0|间接依赖|npm|
|prismjs|1.29.0|间接依赖|npm|
|decamelize|1.2.0|间接依赖|npm|
|is-plain-obj|1.1.0|间接依赖|npm|
|dargs|7.0.0|间接依赖|npm|
|ansi-align|3.0.1|间接依赖|npm|
|dot-prop|5.3.0|间接依赖|npm|
|redent|3.0.0|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|linguist-languages|7.21.0|间接依赖|npm|
|camelcase-keys|6.2.2|间接依赖|npm|
|mimic-fn|4.0.0|间接依赖|npm|
|path-key|3.1.1|间接依赖|npm|
|lru-cache|5.1.1|间接依赖|npm|
|resolve-from|5.0.0|间接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|semver|6.3.1|间接依赖|npm|
|typescript|5.1.3|间接依赖|npm|
|pump|3.0.0|直接依赖|npm|
|ms|2.0.0|间接依赖|npm|
|arrify|1.0.1|间接依赖|npm|
|clean-stack|2.2.0|间接依赖|npm|
|wrap-ansi|7.0.0|间接依赖|npm|
|ansi-regex|6.0.1|间接依赖|npm|
|is-ci|2.0.0|间接依赖|npm|
|json-schema-traverse|1.0.0|间接依赖|npm|
|ci-info|2.0.0|间接依赖|npm|
|map-age-cleaner|0.1.3|间接依赖|npm|
|medium-zoom|1.0.8|间接依赖|npm|
|ee-first|1.1.1|间接依赖|npm|
|on-finished|2.3.0|间接依赖|npm|
|string_decoder|1.3.0|间接依赖|npm|
|typedarray-to-buffer|3.1.5|间接依赖|npm|
|whatwg-url|5.0.0|间接依赖|npm|
|unpipe|1.0.0|间接依赖|npm|
|punycode|2.3.0|间接依赖|npm|
|ws|7.5.9|间接依赖|npm|
|listr2|5.0.8|间接依赖|npm|
|import-lazy|2.1.0|间接依赖|npm|
|hosted-git-info|4.1.0|间接依赖|npm|
|utils-merge|1.0.1|间接依赖|npm|
|term-size|2.2.1|间接依赖|npm|
|string-argv|0.3.2|间接依赖|npm|
|is-text-path|1.0.1|间接依赖|npm|
|through|2.3.8|间接依赖|npm|
|lodash.upperfirst|4.3.1|间接依赖|npm|
|find-up|4.1.0|间接依赖|npm|
|mime|1.6.0|间接依赖|npm|
|webidl-conversions|3.0.1|间接依赖|npm|
|cli-truncate|3.1.0|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|is-yarn-global|0.3.0|间接依赖|npm|
|parse-json|5.2.0|间接依赖|npm|
|human-signals|4.3.1|间接依赖|npm|
|@jridgewell/resolve-uri|3.1.1|间接依赖|npm|
|marked|1.2.9|间接依赖|npm|
|@commitlint/is-ignored|17.6.5|间接依赖|npm|
|lodash.uniq|4.5.0|间接依赖|npm|
|rxjs|7.8.1|间接依赖|npm|
|tinydate|1.3.0|间接依赖|npm|
|php-parser|3.1.5|间接依赖|npm|
|crypto-random-string|2.0.0|间接依赖|npm|
|global-dirs|2.1.0|间接依赖|npm|
|universalify|0.1.2|间接依赖|npm|
|has-yarn|2.1.0|间接依赖|npm|
|JSONStream|1.3.5|间接依赖|npm|
|minimist-options|4.1.0|间接依赖|npm|
|encodeurl|1.0.2|间接依赖|npm|
|resolve-pathname|3.0.0|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|parent-module|1.0.1|间接依赖|npm|
|@sindresorhus/is|0.14.0|间接依赖|npm|
|strip-final-newline|3.0.0|间接依赖|npm|
|boxen|4.2.0|间接依赖|npm|
|ajv|8.12.0|间接依赖|npm|
|package-json|6.5.0|间接依赖|npm|
|is-core-module|2.12.1|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|set-blocking|2.0.0|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|shebang-command|2.0.0|间接依赖|npm|
|read-pkg-up|7.0.1|间接依赖|npm|
|timezone||间接依赖|pip|
|yargonaut|1.1.4|间接依赖|npm|
|npm-run-path|5.1.0|间接依赖|npm|
|meow|8.1.2|间接依赖|npm|
|split2|3.2.2|间接依赖|npm|
|clang-format|1.8.0|直接依赖|npm|
|docsify-cli|4.4.4|直接依赖|npm|
|@commitlint/ensure|17.4.4|间接依赖|npm|
|lodash.mergewith|4.6.2|间接依赖|npm|
|compare-func|2.0.0|间接依赖|npm|
|xdg-basedir|4.0.0|间接依赖|npm|
|got|9.6.0|间接依赖|npm|
|supports-preserve-symlinks-flag|1.0.0|间接依赖|npm|
|anymatch|3.1.3|间接依赖|npm|
|ansi-colors|4.1.3|间接依赖|npm|
|latest-version|5.1.0|间接依赖|npm|
|array-ify|1.0.0|间接依赖|npm|
|docsify-server-renderer|4.13.0|间接依赖|npm|
|minimist|1.2.8|间接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|git-raw-commits|2.0.11|间接依赖|npm|
|ts-node|10.9.1|间接依赖|npm|
|cp-file|7.0.0|间接依赖|npm|
|shebang-regex|3.0.0|间接依赖|npm|
|pupa|2.1.1|间接依赖|npm|
|fs-extra|8.1.0|间接依赖|npm|
|lodash.camelcase|4.3.0|间接依赖|npm|
|yocto-queue|0.1.0|直接依赖|npm|
|merge-stream|2.0.0|间接依赖|npm|
|min-indent|1.0.1|间接依赖|npm|
|binary-extensions|2.2.0|间接依赖|npm|
|lodash.snakecase|4.1.1|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|destroy|1.2.0|间接依赖|npm|
|timedelta||间接依赖|pip|
|@commitlint/resolve-extends|17.4.4|间接依赖|npm|
|type-fest|0.21.3|间接依赖|npm|
|ABC||间接依赖|pip|
|open|6.4.0|间接依赖|npm|
|@commitlint/top-level|17.4.0|间接依赖|npm|
|ansi-escapes|4.3.2|间接依赖|npm|
|is-wsl|1.1.0|间接依赖|npm|
|chokidar|3.5.3|间接依赖|npm|
|yallist|3.1.1|间接依赖|npm|
|q|1.5.1|间接依赖|npm|
|create-require|1.1.1|间接依赖|npm|
|argparse|2.0.1|间接依赖|npm|
|is-fullwidth-code-point|4.0.0|间接依赖|npm|
|toidentifier|1.0.1|间接依赖|npm|
|resolve|1.22.2|间接依赖|npm|
|kind-of|6.0.3|间接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|mem|8.1.1|间接依赖|npm|
|duplexer3|0.1.5|间接依赖|npm|
|emoji-regex|9.2.2|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|readdirp|3.6.0|间接依赖|npm|
|callsites|3.1.0|间接依赖|npm|
|lodash.merge|4.6.2|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|@prettier/plugin-php|0.19.6|直接依赖|npm|
|quick-lru|4.0.1|间接依赖|npm|
|@jridgewell/trace-mapping|0.3.9|间接依赖|npm|
|p-locate|4.1.0|间接依赖|npm|
|v8-compile-cache-lib|3.0.1|间接依赖|npm|
|@tsconfig/node12|1.0.11|间接依赖|npm|
|commander|10.0.1|间接依赖|npm|
|@commitlint/message|17.4.2|间接依赖|npm|
|connect|3.7.0|间接依赖|npm|
|locate-path|5.0.0|间接依赖|npm|
|jsonfile|4.0.0|间接依赖|npm|
|async|3.2.4|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|p-finally|1.0.0|间接依赖|npm|
|trim-newlines|3.0.1|间接依赖|npm|
|@types/node|20.2.5|间接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|lilconfig|2.1.0|间接依赖|npm|
|etag|1.8.1|间接依赖|npm|
|decompress-response|3.3.0|间接依赖|npm|
|escape-html|1.0.3|间接依赖|npm|
|widest-line|3.1.0|间接依赖|npm|
|sql-parser-cst|0.17.1|间接依赖|npm|
|onetime|6.0.0|间接依赖|npm|
|docsify|4.13.0|间接依赖|npm|
|is-npm|4.0.0|间接依赖|npm|
|tslib|2.5.3|间接依赖|npm|
|lodash.kebabcase|4.1.1|间接依赖|npm|
|eastasianwidth|0.2.0|间接依赖|npm|
|rc|1.2.8|间接依赖|npm|
|@commitlint/load|17.5.0|间接依赖|npm|
|colorette|2.0.20|间接依赖|npm|
|enquirer|2.3.6|间接依赖|npm|
|is-path-inside|3.0.3|间接依赖|npm|
|cosmiconfig|8.2.0|间接依赖|npm|
|livereload-js|3.4.1|间接依赖|npm|
|nested-error-stacks|2.1.1|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|is-stream|3.0.0|间接依赖|npm|
|lodash.isfunction|3.0.9|间接依赖|npm|
|cli-boxes|2.2.1|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)