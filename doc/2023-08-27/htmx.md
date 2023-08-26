# bigskysoftware/htmx安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695505076192702464.svg)](https://www.murphysec.com/console/report/1692242931783454720/1695505076192702464)

仓库描述：</> htmx - high power tools for HTML

仓库地址：[https://github.com/bigskysoftware/htmx](https://github.com/bigskysoftware/htmx)

| star：18793 | watch：136 | fork：665 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-27 02:28:49 | 许可证：BSD-2-Clause |
| 最近检测时间：2023-08-27 02:36:01 | 组件总数：192 | 漏洞总数：8 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|jwt-go 安全漏洞|授权检查缺失|[MPS-2020-13786](https://www.oscs1024.com/hd/MPS-2020-13786)|CVE-2020-26160|高危|
|Google chrome-launcher 操作系统命令注入漏洞|OS命令注入|[MPS-2020-6969](https://www.oscs1024.com/hd/MPS-2020-6969)|CVE-2020-7645|严重|
|trim-newlines 存在拒绝服务漏洞|拒绝服务|[MPS-2021-7398](https://www.oscs1024.com/hd/MPS-2021-7398)|CVE-2021-33623|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|LabStack LLC echo 输入验证错误漏洞|跨站重定向|[MPS-2022-58283](https://www.oscs1024.com/hd/MPS-2022-58283)|CVE-2022-40083|严重|
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58307](https://www.oscs1024.com/hd/MPS-2022-58307)|CVE-2022-41723|高危|
|minimatch 资源管理错误漏洞|拒绝服务|[MPS-2022-59845](https://www.oscs1024.com/hd/MPS-2022-59845)|CVE-2022-3517|高危|
|Google Go 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2022-9049](https://www.oscs1024.com/hd/MPS-2022-9049)|CVE-2022-29526|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/labstack/echo/v4|v4.3.0|4.9.0|直接依赖|建议修复|C:1|H:0|M:0|L:0|
|trim-newlines|2.0.0|4.0.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|minimatch|3.0.4|3.0.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|golang.org/x/net|v0.0.0-20210405180319-a5a99cb37ef4|0.7.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|chrome-launcher|0.11.2|0.13.2|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|github.com/dgrijalva/jwt-go|v3.2.0+incompatible|4.0.0-preview1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|golang.org/x/net|v0.0.0-20211015210444-4f30a5c0130f|0.7.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|golang.org/x/sys|v0.0.0-20211103235746-7861aae1554b|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|5.7.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|golang.org/x/sys|v0.0.0-20210630005230-0f9fa26af87c|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|ISC|20|Low|
|Apache-2.0|12|Low|
|BSD-3-Clause|21|Low|
|MIT|132|Low|
|BSD-2-Clause|3|Low|
|CC0-1.0|1|Low|
|CC-BY-3.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|fs.realpath|1.0.0|间接依赖|npm|
|typescript|4.9.5|直接依赖|npm|
|@sinonjs/fake-timers|6.0.1|间接依赖|npm|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|diff|5.0.0|间接依赖|npm|
|github.com/golang-jwt/jwt|v3.2.2+incompatible|间接依赖|go|
|github.com/benpate/derp|v0.20.0|直接依赖|go|
|type-detect|4.0.8|间接依赖|npm|
|read-pkg-up|3.0.0|间接依赖|npm|
|jszip|3.10.1|间接依赖|npm|
|immediate|3.0.6|间接依赖|npm|
|picomatch|2.2.2|直接依赖|npm|
|balanced-match|1.0.0|间接依赖|npm|
|pako|1.0.11|间接依赖|npm|
|read-pkg|3.0.0|间接依赖|npm|
|camelcase|6.3.0|间接依赖|npm|
|selenium-webdriver|4.8.2|间接依赖|npm|
|strip-indent|2.0.0|间接依赖|npm|
|graceful-fs|4.2.3|间接依赖|npm|
|meow|5.0.0|间接依赖|npm|
|assertion-error|1.1.0|间接依赖|npm|
|path-type|3.0.0|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|github.com/labstack/gommon|v0.3.0|间接依赖|go|
|github.com/labstack/gommon|v0.3.1|间接依赖|go|
|github.com/valyala/bytebufferpool|v1.0.0|间接依赖|go|
|is-obj|1.0.1|间接依赖|npm|
|sinon|9.2.4|直接依赖|npm|
|signal-exit|3.0.3|间接依赖|npm|
|github.com/mattn/go-colorable|v0.1.11|间接依赖|go|
|spdx-correct|3.1.0|间接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|github.com/mattn/go-isatty|v0.0.12|间接依赖|go|
|loupe|2.3.6|间接依赖|npm|
|deep-eql|4.1.3|间接依赖|npm|
|strip-json-comments|3.1.1|间接依赖|npm|
|golang.org/x/net|v0.7.0|直接依赖|go|
|arrify|1.0.1|间接依赖|npm|
|normalize-path|3.0.0|直接依赖|npm|
|locate-path|3.0.0|间接依赖|npm|
|fs-extra|9.1.0|直接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|quick-lru|1.1.0|间接依赖|npm|
|pify|3.0.0|间接依赖|npm|
|@sinonjs/samsam|5.3.1|间接依赖|npm|
|github.com/benpate/htmlconv|v0.3.0|直接依赖|go|
|golang.org/x/crypto|v0.1.0|间接依赖|go|
|to-regex-range|5.0.1|间接依赖|npm|
|mocha|10.2.0|直接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|@sinonjs/text-encoding|0.7.1|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|github.com/dgrijalva/jwt-go|v3.2.0+incompatible|间接依赖|go|
|is-plain-obj|1.1.0|间接依赖|npm|
|randombytes|2.1.0|间接依赖|npm|
|normalize-package-data|2.5.0|间接依赖|npm|
|pkg-dir|3.0.0|间接依赖|npm|
|chrome-launcher|0.11.2|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|yocto-queue|0.1.0|直接依赖|npm|
|p-locate|3.0.0|间接依赖|npm|
|isarray|0.0.1|间接依赖|npm|
|nanoscheduler|1.0.3|间接依赖|npm|
|commander|2.11.0|间接依赖|npm|
|github.com/pkg/browser|v0.0.0-20210911075715-681adbf594b8|直接依赖|go|
|require-directory|2.1.1|直接依赖|npm|
|nanotiming|7.3.1|间接依赖|npm|
|serialize-javascript|6.0.0|间接依赖|npm|
|color-name|1.1.3|间接依赖|npm|
|resolve|1.17.0|间接依赖|npm|
|golang.org/x/text|v0.3.6|间接依赖|go|
|setimmediate|1.0.5|间接依赖|npm|
|safe-buffer|5.2.1|间接依赖|npm|
|ws|7.4.6|间接依赖|npm|
|marky|1.2.1|间接依赖|npm|
|chrome-unmirror|0.1.0|间接依赖|npm|
|currently-unhandled|0.4.1|间接依赖|npm|
|check-error|1.0.2|间接依赖|npm|
|escalade|3.1.1|直接依赖|npm|
|loglevel|1.6.8|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|p-try|2.2.0|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|core-util-is|1.0.3|间接依赖|npm|
|load-json-file|4.0.0|间接依赖|npm|
|trim-newlines|2.0.0|间接依赖|npm|
|golang.org/x/net|v0.0.0-20211015210444-4f30a5c0130f|直接依赖|go|
|resolve-cwd|2.0.0|间接依赖|npm|
|braces|3.0.2|直接依赖|npm|
|golang.org/x/text|v0.3.7|间接依赖|go|
|golang.org/x/time|v0.0.0-20201208040808-7e3f01d25324|间接依赖|go|
|he|1.2.0|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|indent-string|3.2.0|间接依赖|npm|
|map-obj|2.0.0|间接依赖|npm|
|flat|5.0.2|间接依赖|npm|
|string-width|4.2.3|间接依赖|npm|
|array-find-index|1.0.2|间接依赖|npm|
|is-number|7.0.0|间接依赖|npm|
|workerpool|6.2.1|间接依赖|npm|
|chai|4.3.7|直接依赖|npm|
|get-func-name|2.0.0|间接依赖|npm|
|resolve-from|3.0.0|间接依赖|npm|
|nise|4.0.4|间接依赖|npm|
|remove-array-items|1.1.1|间接依赖|npm|
|rimraf|2.7.1|间接依赖|npm|
|spdx-expression-parse|3.0.0|间接依赖|npm|
|path-to-regexp|1.8.0|间接依赖|npm|
|loud-rejection|1.6.0|间接依赖|npm|
|uglify-js|3.17.4|直接依赖|npm|
|github.com/labstack/echo/v4|v4.9.0|直接依赖|go|
|find-up|3.0.0|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|github.com/mattn/go-isatty|v0.0.14|间接依赖|go|
|camelcase-keys|4.2.0|间接依赖|npm|
|@zbigg/treesync|0.3.0|间接依赖|npm|
|string_decoder|1.1.1|间接依赖|npm|
|golang.org/x/sys|v0.0.0-20210630005230-0f9fa26af87c|间接依赖|go|
|import-local|2.0.0|间接依赖|npm|
|is-binary-path|2.1.0|直接依赖|npm|
|is-wsl|2.1.1|间接依赖|npm|
|pathval|1.1.1|间接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|just-extend|4.1.1|间接依赖|npm|
|get-caller-file|2.0.5|直接依赖|npm|
|browser-stdout|1.3.1|间接依赖|npm|
|process-nextick-args|2.0.1|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|mocha-webdriver-runner|0.6.4|直接依赖|npm|
|minimist-options|3.0.2|间接依赖|npm|
|nanobus|4.4.0|间接依赖|npm|
|redent|2.0.0|间接依赖|npm|
|is-unicode-supported|0.1.0|间接依赖|npm|
|deep-assign|3.0.0|间接依赖|npm|
|lie|3.3.0|间接依赖|npm|
|minimatch|3.0.4|间接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|decamelize|1.2.0|间接依赖|npm|
|golang.org/x/text|v0.7.0|间接依赖|go|
|spdx-license-ids|3.0.5|间接依赖|npm|
|y18n|5.0.8|直接依赖|npm|
|github.com/valyala/fasttemplate|v1.2.1|间接依赖|go|
|path-parse|1.0.7|间接依赖|npm|
|ansi-colors|4.1.1|间接依赖|npm|
|github.com/stretchr/testify|v1.7.0|间接依赖|go|
|golang.org/x/sys|v0.0.0-20211103235746-7861aae1554b|间接依赖|go|
|nanoassert|1.1.0|间接依赖|npm|
|at-least-node|1.0.0|间接依赖|npm|
|golang.org/x/net|v0.0.0-20210405180319-a5a99cb37ef4|直接依赖|go|
|lighthouse-logger|1.2.0|间接依赖|npm|
|golang.org/x/crypto|v0.0.0-20210322153248-0c34fe9e7dc2|间接依赖|go|
|@sinonjs/commons|1.8.2|间接依赖|npm|
|@types/node|13.13.2|间接依赖|npm|
|cliui|7.0.4|直接依赖|npm|
|path-exists|3.0.0|间接依赖|npm|
|golang.org/x/crypto|v0.0.0-20210817164053-32db794688a5|间接依赖|go|
|validate-npm-package-license|3.0.4|间接依赖|npm|
|nanoid|3.3.3|间接依赖|npm|
|lodash.get|4.4.2|间接依赖|npm|
|is-glob|4.0.1|间接依赖|npm|
|tmp|0.2.1|间接依赖|npm|
|hosted-git-info|2.8.9|间接依赖|npm|
|yargs-unparser|2.0.0|间接依赖|npm|
|github.com/labstack/echo/v4|v4.3.0|直接依赖|go|
|glob|7.1.3|间接依赖|npm|
|github.com/mattn/go-colorable|v0.1.8|间接依赖|go|
|p-limit|2.3.0|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|debug|4.3.4|间接依赖|npm|
|emoji-regex|8.0.0|间接依赖|npm|
|strip-ansi|6.0.1|间接依赖|npm|
|decamelize-keys|1.1.0|间接依赖|npm|
|glob-parent|5.1.2|直接依赖|npm|
|ms|2.1.1|间接依赖|npm|
|parse-json|4.0.0|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|golang.org/x/sys|v0.5.0|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|readable-stream|2.3.8|间接依赖|npm|
|wrap-ansi|7.0.0|间接依赖|npm|
|chrome-remote-interface|0.28.1|间接依赖|npm|
|semver|5.7.1|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|chai-dom|1.11.0|直接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|binary-extensions|2.0.0|间接依赖|npm|
|supports-color|7.2.0|间接依赖|npm|
|spdx-exceptions|2.3.0|间接依赖|npm|
|mocha-chrome|2.2.0|直接依赖|npm|
|strip-bom|3.0.0|间接依赖|npm|
|log-symbols|4.1.0|间接依赖|npm|
|mock-socket|9.2.1|直接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)