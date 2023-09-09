# microsoft/Web-Dev-For-Beginners安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700578562247622656.svg)](https://www.murphysec.com/console/report/1695868888448135168/1700578562247622656)

仓库描述：24 Lessons, 12 Weeks, Get Started as a Web Developer

仓库地址：[https://github.com/microsoft/Web-Dev-For-Beginners](https://github.com/microsoft/Web-Dev-For-Beginners)

| star：75454 | watch：2655 | fork：11786 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-28 16:56:24 | 许可证：MIT |
| 最近检测时间：2023-09-10 02:36:07 | 组件总数：201 | 漏洞总数：8 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|colors.js  >1.4.0 DOS漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-19606](https://www.oscs1024.com/hd/MPS-2021-19606)|CVE-2021-23567|高危|
|npm markdown-link-extractor 安全漏洞|ReDoS|[MPS-2021-35112](https://www.oscs1024.com/hd/MPS-2021-35112)|CVE-2021-43308|高危|
|marked 存在拒绝服务漏洞||[MPS-2021-37038](https://www.oscs1024.com/hd/MPS-2021-37038)|CVE-2022-21680|高危|
|marked 存在拒绝服务漏洞|过度严格的正则表达式|[MPS-2021-37039](https://www.oscs1024.com/hd/MPS-2021-37039)|CVE-2022-21681|高危|
|marked 存在拒绝服务漏洞|拒绝服务|[MPS-2021-9993](https://www.oscs1024.com/hd/MPS-2021-9993)|CVE-2021-21306|高危|
|got 存在打开重定向漏洞|跨站重定向|[MPS-2022-19247](https://www.oscs1024.com/hd/MPS-2022-19247)|CVE-2022-33987|中危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|Tauri 原型污染漏洞|原型污染|[MPS-2022-65568](https://www.oscs1024.com/hd/MPS-2022-65568)|CVE-2022-46175|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|json5|0.5.1|2.2.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|markdown-link-extractor|1.3.1|4.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|colors|1.4.0||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|got|9.6.0|12.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|marked|1.2.9|4.0.10|间接依赖|可选修复|C:0|H:3|M:0|L:0|
|semver|6.3.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|159|Low|
|BSD-2-Clause|6|Low|
|ISC|28|Low|
|Apache-2.0|2|Low|
|BSD|1|Low|
|BSD-3-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|xdg-basedir|4.0.0|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|utils-merge|1.0.1|间接依赖|npm|
|configstore|5.0.1|间接依赖|npm|
|semver-diff|3.1.1|间接依赖|npm|
|glob|7.1.7|间接依赖|npm|
|js-yaml|3.14.1|间接依赖|npm|
|update-notifier|4.1.3|间接依赖|npm|
|rcfile|1.0.3|间接依赖|npm|
|is-npm|4.0.0|间接依赖|npm|
|registry-auth-token|4.2.1|间接依赖|npm|
|path-exists|4.0.0|间接依赖|npm|
|callsites|0.2.0|间接依赖|npm|
|is-installed-globally|0.3.2|间接依赖|npm|
|typedarray-to-buffer|3.1.5|间接依赖|npm|
|type-fest|0.8.1|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|argparse|1.0.10|间接依赖|npm|
|crypto-random-string|2.0.0|间接依赖|npm|
|package-json|6.5.0|间接依赖|npm|
|statuses|1.5.0|间接依赖|npm|
|latest-version|5.1.0|间接依赖|npm|
|setprototypeof|1.1.1|间接依赖|npm|
|got|9.6.0|间接依赖|npm|
|strip-ansi|6.0.1|间接依赖|npm|
|serve-static|1.14.1|间接依赖|npm|
|process-nextick-args|2.0.1|间接依赖|npm|
|dot-prop|5.3.0|间接依赖|npm|
|cli-boxes|2.2.1|间接依赖|npm|
|docsify-to-pdf|0.0.5|直接依赖|npm|
|parseurl|1.3.3|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|dompurify|2.2.9|间接依赖|npm|
|escape-html|1.0.3|间接依赖|npm|
|es6-promisify|5.0.0|间接依赖|npm|
|es6-promise|4.2.8|间接依赖|npm|
|puppeteer|1.20.0|间接依赖|npm|
|has-ansi|2.0.0|直接依赖|npm|
|mkdirp|0.5.5|间接依赖|npm|
|universalify|0.1.2|间接依赖|npm|
|unique-string|2.0.0|间接依赖|npm|
|depd|1.1.2|间接依赖|npm|
|buffer-from|1.1.1|间接依赖|npm|
|signal-exit|3.0.3|间接依赖|npm|
|pinkie-promise|2.0.1|直接依赖|npm|
|unpipe|1.0.0|间接依赖|npm|
|opencollective-postinstall|2.0.3|间接依赖|npm|
|figlet|1.5.0|间接依赖|npm|
|set-blocking|2.0.0|间接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|is-wsl|1.1.0|间接依赖|npm|
|y18n|4.0.3|间接依赖|npm|
|colors|1.4.0|间接依赖|npm|
|docsify|4.13.0|间接依赖|npm|
|string_decoder|1.1.1|间接依赖|npm|
|isarray|1.0.0|间接依赖|npm|
|destroy|1.0.4|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|min-indent|1.0.1|间接依赖|npm|
|connect-livereload|0.6.1|间接依赖|npm|
|is-typedarray|1.0.0|间接依赖|npm|
|picomatch|2.3.0|间接依赖|npm|
|rimraf|2.7.1|间接依赖|npm|
|ci-info|2.0.0|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|yargonaut|1.1.4|间接依赖|npm|
|yallist|3.1.1|间接依赖|npm|
|prismjs|1.27.0|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|cliui|6.0.0|间接依赖|npm|
|global-dirs|2.1.0|间接依赖|npm|
|object-keys|1.1.1|间接依赖|npm|
|etag|1.8.1|间接依赖|npm|
|pupa|2.1.1|间接依赖|npm|
|marked|1.2.9|间接依赖|npm|
|require-main-filename|2.0.0|间接依赖|npm|
|p-timeout|3.2.0|间接依赖|npm|
|medium-zoom|1.0.6|间接依赖|npm|
|locate-path|5.0.0|间接依赖|npm|
|term-size|2.2.1|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|readable-stream|2.3.7|间接依赖|npm|
|widest-line|3.1.0|间接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|yesno|0.2.1|间接依赖|npm|
|typedarray|0.0.6|间接依赖|npm|
|semver|6.3.0|间接依赖|npm|
|pend|1.2.0|间接依赖|npm|
|tinydate|1.3.0|间接依赖|npm|
|fd-slicer|1.1.0|间接依赖|npm|
|yargs|15.4.1|间接依赖|npm|
|get-port|5.1.1|间接依赖|npm|
|encodeurl|1.0.2|间接依赖|npm|
|mime|1.6.0|间接依赖|npm|
|binary-extensions|2.2.0|间接依赖|npm|
|write-file-atomic|3.0.3|间接依赖|npm|
|chokidar|3.5.2|间接依赖|npm|
|on-finished|2.3.0|间接依赖|npm|
|cp-file|7.0.0|间接依赖|npm|
|graceful-fs|4.2.6|间接依赖|npm|
|make-dir|3.1.0|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|fsevents|2.3.2|间接依赖|npm|
|lru-cache|5.1.1|间接依赖|npm|
|p-locate|4.1.0|间接依赖|npm|
|is-glob|4.0.1|间接依赖|npm|
|json5|0.5.1|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|string-width|4.2.2|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|pinkie|2.0.4|间接依赖|npm|
|is-yarn-global|0.3.0|间接依赖|npm|
|open|6.4.0|间接依赖|npm|
|http-errors|1.7.3|间接依赖|npm|
|strip-indent|3.0.0|间接依赖|npm|
|fresh|0.5.2|间接依赖|npm|
|progress|2.0.3|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|livereload|0.9.3|间接依赖|npm|
|readdirp|3.6.0|间接依赖|npm|
|escape-goat|2.1.1|间接依赖|npm|
|p-event|4.2.0|间接依赖|npm|
|is-obj|2.0.0|间接依赖|npm|
|docsify-server-renderer|4.12.1|间接依赖|npm|
|imurmurhash|0.1.4|间接依赖|npm|
|resolve-pathname|3.0.0|间接依赖|npm|
|node-fetch|2.6.7|间接依赖|npm|
|wrap-ansi|6.2.0|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|docsify-cli|4.4.4|间接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|agent-base|4.3.0|间接依赖|npm|
|sprintf-js|1.0.3|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|proxy-from-env|1.1.0|间接依赖|npm|
|boxen|4.2.0|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|is-url|1.2.4|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|find-free-port|2.0.0|间接依赖|npm|
|parent-require|1.0.0|间接依赖|npm|
|ms|2.0.0|间接依赖|npm|
|toidentifier|1.0.0|间接依赖|npm|
|ansi-colors|4.1.1|间接依赖|npm|
|yauzl|2.10.0|间接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|async-limiter|1.0.1|直接依赖|npm|
|jsonfile|4.0.0|间接依赖|npm|
|resolve-from|1.0.1|间接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|ini|1.3.7|间接依赖|npm|
|enquirer|2.3.6|间接依赖|npm|
|is-path-inside|3.0.3|间接依赖|npm|
|livereload-js|3.3.2|间接依赖|npm|
|which-module|2.0.0|间接依赖|npm|
|is-binary-path|2.1.0|间接依赖|npm|
|concat-stream|1.6.2|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|markdown-link-extractor|1.3.1|间接依赖|npm|
|buffer-crc32|0.2.13|间接依赖|npm|
|fs-extra|8.1.0|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|finalhandler|1.1.2|间接依赖|npm|
|registry-url|5.1.0|间接依赖|npm|
|decamelize|1.2.0|间接依赖|npm|
|p-finally|1.0.0|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|yargs-parser|18.1.3|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|is-ci|2.0.0|间接依赖|npm|
|debug|2.6.9|间接依赖|npm|
|glob-parent|5.1.2|间接依赖|npm|
|core-util-is|1.0.2|间接依赖|npm|
|connect|3.7.0|间接依赖|npm|
|send|0.17.1|间接依赖|npm|
|esprima|4.0.1|间接依赖|npm|
|nested-error-stacks|2.1.0|间接依赖|npm|
|connect-history-api-fallback|1.6.0|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|range-parser|1.2.1|间接依赖|npm|
|anymatch|3.1.2|间接依赖|npm|
|caller-path|0.1.0|间接依赖|npm|
|ee-first|1.1.1|间接依赖|npm|
|ansi-align|3.0.1|间接依赖|npm|
|opts|2.0.2|间接依赖|npm|
|whatwg-url|5.0.0|间接依赖|npm|
|import-lazy|2.1.0|间接依赖|npm|
|color-name|1.1.3|间接依赖|npm|
|ws|7.5.0|间接依赖|npm|
|camelcase|5.3.1|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|extract-zip|1.7.0|间接依赖|npm|
|minimist|1.2.6|间接依赖|npm|
|https-proxy-agent|2.2.4|间接依赖|npm|
|tweezer.js|1.5.0|间接依赖|npm|
|webidl-conversions|3.0.1|间接依赖|npm|
|require-uncached|1.0.3|间接依赖|npm|
|has-yarn|2.1.0|间接依赖|npm|
|tr46|0.0.3|间接依赖|npm|
|find-up|4.1.0|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)