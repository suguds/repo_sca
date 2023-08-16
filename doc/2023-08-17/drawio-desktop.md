# jgraph/drawio-desktop安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1691880300013707264.svg)](https://www.murphysec.com/console/report/1691880299183235072/1691880300013707264)

仓库描述：Official electron build of draw.io

仓库地址：[https://github.com/jgraph/drawio-desktop](https://github.com/jgraph/drawio-desktop)

| star：42194 | watch：510 | fork：4457 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-11 14:16:52 | 许可证：- |
| 最近检测时间：2023-08-17 02:31:16 | 组件总数：267 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|MPS-2022-5166|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|MPS-2023-10199|注入|[MPS-2023-10199](https://www.oscs1024.com/hd/MPS-2023-10199)|CVE-2023-29827|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|ejs|3.1.9||间接依赖|建议修复|C:1|H:0|M:0|L:0|
|semver|6.3.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|204|Low|
|ISC|28|Low|
|BSD-2-Clause|8|Low|
|0BSD|2|Low|
|Apache-2.0|8|Low|
|BSD-3-Clause|4|Low|
|WTFPL|2|Low|
|Python-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|extsprintf|1.4.1|间接依赖|npm|
|type-fest|0.13.1|间接依赖|npm|
|tmp-promise|3.0.3|间接依赖|npm|
|glob|7.2.3|间接依赖|npm|
|color-convert|2.0.1|间接依赖|npm|
|path-exists|3.0.0|间接依赖|npm|
|tar|6.1.15|间接依赖|npm|
|dmg-license|1.0.11|直接依赖|npm|
|hosted-git-info|4.1.0|间接依赖|npm|
|cross-spawn|7.0.3|间接依赖|npm|
|get-stream|5.2.0|间接依赖|npm|
|7zip-bin|5.1.1|间接依赖|npm|
|extract-zip|2.0.1|间接依赖|npm|
|@types/debug|4.1.8|间接依赖|npm|
|assert-plus|1.0.0|间接依赖|npm|
|@electron/universal|1.3.4|间接依赖|npm|
|env-paths|2.2.1|间接依赖|npm|
|onetime|5.1.2|间接依赖|npm|
|@tootallnate/once|2.0.0|间接依赖|npm|
|y18n|5.0.8|间接依赖|npm|
|conf|10.2.0|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|yargs|17.7.2|间接依赖|npm|
|json-schema-typed|7.0.3|间接依赖|npm|
|dot-prop|6.0.1|间接依赖|npm|
|tslib|2.6.1|间接依赖|npm|
|http-cache-semantics|4.1.1|间接依赖|npm|
|strip-ansi|6.0.1|间接依赖|npm|
|sumchecker|3.0.1|间接依赖|npm|
|@electron/asar|3.2.4|间接依赖|npm|
|p-locate|3.0.0|间接依赖|npm|
|asynckit|0.4.0|间接依赖|npm|
|cacheable-lookup|5.0.4|间接依赖|npm|
|ajv|6.12.6|间接依赖|npm|
|tslib|1.14.1|间接依赖|npm|
|@malept/flatpak-bundler|0.4.0|间接依赖|npm|
|object-keys|1.1.1|间接依赖|npm|
|wrap-ansi|7.0.0|间接依赖|npm|
|debug|4.3.4|间接依赖|npm|
|sprintf-js|1.1.2|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|@malept/cross-spawn-promise|1.1.1|间接依赖|npm|
|brace-expansion|2.0.1|间接依赖|npm|
|app-builder-bin|4.0.0|间接依赖|npm|
|supports-color|7.2.0|间接依赖|npm|
|buffer-equal|1.0.1|间接依赖|npm|
|@xmldom/xmldom|0.8.10|间接依赖|npm|
|node-addon-api|1.7.2|间接依赖|npm|
|pump|3.0.0|间接依赖|npm|
|form-data|4.0.0|间接依赖|npm|
|cacheable-request|7.0.4|间接依赖|npm|
|electron|25.5.0|直接依赖|npm|
|mime-db|1.52.0|间接依赖|npm|
|ajv|8.12.0|间接依赖|npm|
|typescript|4.9.5|间接依赖|npm|
|electron-progressbar|2.1.0|直接依赖|npm|
|serialize-error|7.0.1|间接依赖|npm|
|dotenv-expand|5.1.0|间接依赖|npm|
|shebang-regex|3.0.0|间接依赖|npm|
|compression|1.7.4|直接依赖|npm|
|lowercase-keys|2.0.0|间接依赖|npm|
|commander|5.1.0|间接依赖|npm|
|http2-wrapper|1.0.3|间接依赖|npm|
|es6-error|4.1.1|间接依赖|npm|
|builder-util|24.5.0|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|debounce-fn|4.0.0|间接依赖|npm|
|fs-minipass|2.1.0|间接依赖|npm|
|plist|3.1.0|间接依赖|npm|
|ansi-styles|4.3.0|间接依赖|npm|
|matcher|3.0.0|间接依赖|npm|
|astral-regex|2.0.0|间接依赖|npm|
|yallist|4.0.0|间接依赖|npm|
|graceful-fs|4.2.11|直接依赖|npm|
|cli-truncate|2.1.0|间接依赖|npm|
|path-key|3.1.1|间接依赖|npm|
|quick-lru|5.1.1|间接依赖|npm|
|core-util-is|1.0.2|间接依赖|npm|
|ms|2.0.0|间接依赖|npm|
|simple-update-notifier|2.0.0|间接依赖|npm|
|emoji-regex|8.0.0|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|@types/ms|0.7.31|间接依赖|npm|
|mimic-fn|3.1.0|间接依赖|npm|
|@sindresorhus/is|4.6.0|间接依赖|npm|
|accepts|1.3.8|间接依赖|npm|
|json5|2.2.3|间接依赖|npm|
|semver|7.5.4|间接依赖|npm|
|lodash.isequal|4.5.0|间接依赖|npm|
|buffer-from|1.1.2|间接依赖|npm|
|boolean|3.2.0|间接依赖|npm|
|dotenv|9.0.2|间接依赖|npm|
|http-proxy-agent|5.0.0|间接依赖|npm|
|jsonfile|4.0.0|间接依赖|npm|
|@types/responselike|1.0.0|间接依赖|npm|
|globalthis|1.0.3|间接依赖|npm|
|tmp|0.2.1|间接依赖|npm|
|chalk|4.1.2|间接依赖|npm|
|compare-version|0.1.2|间接依赖|npm|
|normalize-url|6.1.0|间接依赖|npm|
|combined-stream|1.0.8|间接依赖|npm|
|@types/node|18.17.4|间接依赖|npm|
|electron-updater|6.1.1|直接依赖|npm|
|@types/fs-extra|9.0.13|间接依赖|npm|
|semver|6.3.1|间接依赖|npm|
|global-agent|3.0.0|直接依赖|npm|
|stat-mode|1.0.0|间接依赖|npm|
|minizlib|2.1.2|间接依赖|npm|
|bluebird-lst|1.0.9|间接依赖|npm|
|iconv-lite|0.6.3|间接依赖|npm|
|@pdf-lib/standard-fonts|1.0.0|间接依赖|npm|
|define-properties|1.2.0|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|sax|1.2.4|间接依赖|npm|
|xmlbuilder|15.1.1|间接依赖|npm|
|chromium-pickle-js|0.2.0|间接依赖|npm|
|electron-store|8.1.0|直接依赖|npm|
|utf8-byte-length|1.0.4|间接依赖|npm|
|lru-cache|6.0.0|间接依赖|npm|
|lazy-val|1.0.5|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|punycode|2.3.0|间接依赖|npm|
|promise-retry|2.0.1|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|filelist|1.0.4|间接依赖|npm|
|retry|0.12.0|间接依赖|npm|
|locate-path|3.0.0|间接依赖|npm|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|minimatch|5.1.6|间接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|roarr|2.15.4|间接依赖|npm|
|app-builder-lib|24.6.3|间接依赖|npm|
|debug|2.6.9|间接依赖|npm|
|atomically|1.7.0|间接依赖|npm|
|rimraf|3.0.2|间接依赖|npm|
|@types/plist|3.0.2|间接依赖|npm|
|@types/http-cache-semantics|4.0.1|间接依赖|npm|
|at-least-node|1.0.0|间接依赖|npm|
|electron-builder|24.6.3|直接依赖|npm|
|@develar/schema-utils|2.6.5|间接依赖|npm|
|@electron/notarize|1.2.4|间接依赖|npm|
|err-code|2.0.3|间接依赖|npm|
|electron-log|4.4.8|直接依赖|npm|
|decompress-response|6.0.0|间接依赖|npm|
|detect-node|2.1.0|间接依赖|npm|
|@pdf-lib/upng|1.0.1|间接依赖|npm|
|bytes|3.0.0|间接依赖|npm|
|pako|1.0.11|间接依赖|npm|
|minipass|3.3.6|间接依赖|npm|
|config-file-ts|0.2.4|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|chownr|2.0.0|间接依赖|npm|
|electron-publish|24.5.0|间接依赖|npm|
|crc|4.3.2|直接依赖|npm|
|verror|1.10.1|间接依赖|npm|
|jsonfile|6.1.0|间接依赖|npm|
|get-intrinsic|1.2.1|间接依赖|npm|
|yargs-parser|21.1.1|间接依赖|npm|
|source-map-support|0.5.21|间接依赖|npm|
|argparse|2.0.1|间接依赖|npm|
|@types/node|20.4.9|间接依赖|npm|
|fs-extra|9.1.0|间接依赖|npm|
|fd-slicer|1.1.0|间接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|commander|11.0.0|直接依赖|npm|
|defer-to-connect|2.0.1|间接依赖|npm|
|minimist|1.2.8|间接依赖|npm|
|sanitize-filename|1.6.3|间接依赖|npm|
|on-headers|1.0.2|间接依赖|npm|
|rxjs|7.8.1|直接依赖|npm|
|buffer|5.7.1|间接依赖|npm|
|string-width|4.2.3|间接依赖|npm|
|temp-file|3.4.0|间接依赖|npm|
|escape-string-regexp|4.0.0|间接依赖|npm|
|truncate-utf8-bytes|1.0.2|间接依赖|npm|
|minipass|5.0.0|间接依赖|npm|
|semver-compare|1.0.0|间接依赖|npm|
|ieee754|1.2.1|间接依赖|npm|
|dmg-builder|24.6.3|间接依赖|npm|
|mimic-response|1.0.1|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|shebang-command|2.0.0|间接依赖|npm|
|mkdirp|1.0.4|间接依赖|npm|
|vary|1.1.2|间接依赖|npm|
|mime|2.6.0|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|negotiator|0.6.3|间接依赖|npm|
|@types/yauzl|2.10.0|直接依赖|npm|
|ci-info|3.8.0|间接依赖|npm|
|async-exit-hook|2.0.1|间接依赖|npm|
|ejs|3.1.9|间接依赖|npm|
|type-fest|2.19.0|间接依赖|npm|
|has-property-descriptors|1.0.0|间接依赖|npm|
|read-config-file|6.3.2|间接依赖|npm|
|js-yaml|4.1.0|间接依赖|npm|
|resolve-alpn|1.2.1|间接依赖|npm|
|yauzl|2.10.0|间接依赖|npm|
|pkg-up|3.1.0|间接依赖|npm|
|crc|3.8.0|间接依赖|npm|
|mimic-response|3.1.0|间接依赖|npm|
|universalify|2.0.0|间接依赖|npm|
|https-proxy-agent|5.0.1|间接依赖|npm|
|keyv|4.5.3|间接依赖|npm|
|dotenv|16.3.1|直接依赖|npm|
|which|2.0.2|间接依赖|npm|
|is-ci|3.0.1|间接依赖|npm|
|json-schema-traverse|1.0.0|间接依赖|npm|
|extend|3.0.2|间接依赖|npm|
|got|11.8.6|间接依赖|npm|
|async|3.2.4|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|progress|2.0.3|间接依赖|npm|
|@types/verror|1.10.6|间接依赖|npm|
|dir-compare|3.3.0|间接依赖|npm|
|responselike|2.0.1|间接依赖|npm|
|typed-emitter|2.1.0|间接依赖|npm|
|@electron/get|2.0.2|间接依赖|npm|
|isbinaryfile|4.0.10|间接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|compressible|2.0.18|间接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|delayed-stream|1.0.0|间接依赖|npm|
|mimic-fn|2.1.0|间接依赖|npm|
|find-up|3.0.0|间接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|json-stringify-safe|5.0.1|间接依赖|npm|
|builder-util-runtime|9.2.1|间接依赖|npm|
|universalify|0.1.2|间接依赖|npm|
|end-of-stream|1.4.4|间接依赖|npm|
|ajv-keywords|3.5.2|间接依赖|npm|
|@electron/osx-sign|1.0.4|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|@types/cacheable-request|6.0.3|间接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|has-flag|4.0.0|间接依赖|npm|
|color-name|1.1.4|间接依赖|npm|
|source-map|0.6.1|间接依赖|npm|
|pend|1.2.0|间接依赖|npm|
|clone-response|1.0.3|间接依赖|npm|
|base64-js|1.5.1|间接依赖|npm|
|ajv-formats|2.1.1|间接依赖|npm|
|fs-extra|8.1.0|间接依赖|npm|
|jake|10.8.7|间接依赖|npm|
|@electron/notarize|2.1.0|直接依赖|npm|
|bluebird|3.7.2|间接依赖|npm|
|cliui|8.0.1|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|agent-base|6.0.2|间接依赖|npm|
|isbinaryfile|5.0.0|间接依赖|npm|
|iconv-corefoundation|1.1.7|间接依赖|npm|
|@szmarczak/http-timer|4.0.6|间接依赖|npm|
|require-from-string|2.0.2|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|slice-ansi|3.0.0|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|
|mime-types|2.1.35|间接依赖|npm|
|fs-extra|10.1.0|间接依赖|npm|
|buffer-crc32|0.2.13|间接依赖|npm|
|p-cancelable|2.1.1|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|is-obj|2.0.0|间接依赖|npm|
|@types/keyv|3.1.4|间接依赖|npm|
|json-buffer|3.0.1|间接依赖|npm|
|lodash.escaperegexp|4.1.2|间接依赖|npm|
|pdf-lib|1.17.1|直接依赖|npm|
|smart-buffer|4.2.0|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)