# zabbix/zabbix安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1697316110427648000.svg)](https://www.murphysec.com/console/report/1697316109911748608/1697316110427648000)

仓库描述：Real-time monitoring of IT components and services, such as networks, servers, VMs, applications and the cloud.

仓库地址：[https://github.com/zabbix/zabbix](https://github.com/zabbix/zabbix)

| star：3225 | watch：124 | fork：877 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-31 23:00:53 | 许可证：GPL-2.0 |
| 最近检测时间：2023-09-01 02:32:55 | 组件总数：305 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|ejs 存在服务端模板注入漏洞|注入|[MPS-2023-10199](https://www.oscs1024.com/hd/MPS-2023-10199)|CVE-2023-29827|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|ejs|3.1.8||间接依赖|建议修复|C:1|H:0|M:0|L:0|
|semver|7.3.8|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|212|Low|
|ISC|51|Low|
|Apache-2.0|8|Low|
|UPL-1.0|1|Low|
|BSD-3-Clause|12|Low|
|自定义许可证|5|Low|
|BSD-2-Clause|11|Low|
|CC0-1.0|1|Low|
|MPL-2.0|1|Low|
|EPL-1.0|1|Low|
|Python-2.0|1|Low|
|EPL-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|string_decoder|1.1.1|间接依赖|npm|
|parse5|7.1.1|间接依赖|npm|
|socks|2.7.1|间接依赖|npm|
|@types/node|18.8.3|间接依赖|npm|
|lru-cache|7.14.0|间接依赖|npm|
|github.com/omeid/go-yarn|v0.0.1|直接依赖|go|
|github.com/gobwas/pool|v0.2.1|间接依赖|go|
|get-caller-file|2.0.5|间接依赖|npm|
|get-value|2.0.6|间接依赖|npm|
|svgo|2.8.0|间接依赖|npm|
|is-descriptor|1.0.2|间接依赖|npm|
|resolve-url|0.2.1|间接依赖|npm|
|union-value|1.0.1|间接依赖|npm|
|github.com/gobwas/httphead|v0.1.0|间接依赖|go|
|org.fusesource.jansi:jansi|1.9|直接依赖|maven|
|console-control-strings|1.1.0|间接依赖|npm|
|pascalcase|0.1.1|间接依赖|npm|
|process-nextick-args|2.0.1|间接依赖|npm|
|yargs|17.5.1|间接依赖|npm|
|semver|7.3.8|间接依赖|npm|
|github.com/godror/godror|v0.34.0|直接依赖|go|
|decode-uri-component|0.2.2|间接依赖|npm|
|source-map-resolve|0.5.3|间接依赖|npm|
|github.com/godror/knownpb|v0.1.0|间接依赖|go|
|balanced-match|1.0.2|间接依赖|npm|
|minipass-collect|1.0.2|间接依赖|npm|
|has-values|1.0.0|间接依赖|npm|
|@nodelib/fs.stat|2.0.5|间接依赖|npm|
|class-utils|0.3.6|间接依赖|npm|
|aggregate-error|3.1.0|间接依赖|npm|
|ttf2woff|3.0.0|间接依赖|npm|
|fast-glob|3.2.12|间接依赖|npm|
|ignore|5.2.0|间接依赖|npm|
|@types/ttf2woff2|2.0.0|间接依赖|npm|
|@types/fs-extra|9.0.13|间接依赖|npm|
|file-uri-to-path|1.0.0|间接依赖|npm|
|supports-color|7.2.0|间接依赖|npm|
|path-exists|4.0.0|间接依赖|npm|
|minipass-flush|1.0.5|间接依赖|npm|
|nopt|6.0.0|间接依赖|npm|
|kind-of|6.0.3|间接依赖|npm|
|github.com/Microsoft/go-winio|v0.6.1|直接依赖|go|
|org.codehaus.janino:commons-compiler|3.0.6|间接依赖|maven|
|git.zabbix.com/ap/plugin-support|v1.2.2-0.20230830115154-0cdc16dc3195|直接依赖|go|
|has-unicode|2.0.1|间接依赖|npm|
|github.com/gorilla/websocket|v1.4.2|间接依赖|go|
|which|2.0.2|间接依赖|npm|
|ejs|3.1.8|间接依赖|npm|
|github.com/gobwas/ws|v1.1.0|间接依赖|go|
|set-blocking|2.0.0|间接依赖|npm|
|csso|4.2.0|间接依赖|npm|
|atob|2.1.2|间接依赖|npm|
|depd|1.1.2|间接依赖|npm|
|ssri|9.0.1|间接依赖|npm|
|cheerio|1.0.0-rc.12|间接依赖|npm|
|@trysound/sax|0.2.0|间接依赖|npm|
|picocolors|1.0.0|间接依赖|npm|
|globby|11.1.0|间接依赖|npm|
|@types/ttf2eot|2.0.0|间接依赖|npm|
|domelementtype|2.3.0|间接依赖|npm|
|set-value|2.0.1|间接依赖|npm|
|is-buffer|1.1.6|直接依赖|npm|
|@nodelib/fs.walk|1.2.8|间接依赖|npm|
|picomatch|2.3.1|间接依赖|npm|
|maxstache-stream|1.0.4|间接依赖|npm|
|merge2|1.4.1|间接依赖|npm|
|colors-cli|1.0.28|间接依赖|npm|
|object-visit|1.0.1|间接依赖|npm|
|@tootallnate/once|2.0.0|间接依赖|npm|
|queue-microtask|1.2.3|间接依赖|npm|
|github.com/sokurenko/go-netstat|v1.0.0|直接依赖|go|
|svgpath|2.5.0|间接依赖|npm|
|nanomatch|1.2.13|直接依赖|npm|
|aproba|2.0.0|间接依赖|npm|
|domutils|3.0.1|间接依赖|npm|
|xtend|4.0.2|间接依赖|npm|
|wide-align|1.1.5|间接依赖|npm|
|gauge|4.0.4|间接依赖|npm|
|readdirp|2.2.1|间接依赖|npm|
|is-path-inside|3.0.3|间接依赖|npm|
|gopkg.in/asn1-ber.v1|v1.0.0-20181015200546-f715ec2f112d|间接依赖|go|
|http-cache-semantics|4.1.1|间接依赖|npm|
|mixin-deep|1.3.2|间接依赖|npm|
|extend-shallow|3.0.2|间接依赖|npm|
|core-util-is|1.0.3|间接依赖|npm|
|isarray|1.0.0|间接依赖|npm|
|svgicons2svgfont|12.0.0|间接依赖|npm|
|is-path-cwd|2.2.0|间接依赖|npm|
|env-paths|2.2.1|间接依赖|npm|
|regex-not|1.0.2|间接依赖|npm|
|source-map|0.6.1|间接依赖|npm|
|microbuffer|1.0.0|间接依赖|npm|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|lodash|4.17.21|间接依赖|npm|
|image2uri|1.0.5|间接依赖|npm|
|jake|10.8.5|间接依赖|npm|
|css-select|5.1.0|间接依赖|npm|
|http-proxy-agent|5.0.0|间接依赖|npm|
|are-we-there-yet|3.0.1|间接依赖|npm|
|stable|0.1.8|间接依赖|npm|
|tar|6.1.11|间接依赖|npm|
|javax.mail:mail|1.4|直接依赖|maven|
|y18n|5.0.8|间接依赖|npm|
|bindings|1.5.0|间接依赖|npm|
|arr-diff|4.0.0|间接依赖|npm|
|fragment-cache|0.2.1|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|urix|0.1.0|间接依赖|npm|
|has-flag|4.0.0|间接依赖|npm|
|object.pick|1.3.0|间接依赖|npm|
|symfony/yaml|v5.1.3|间接依赖|composer|
|safe-regex|1.1.0|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|yallist|4.0.0|间接依赖|npm|
|pako|1.0.11|间接依赖|npm|
|color-convert|2.0.1|间接依赖|npm|
|unset-value|1.0.0|间接依赖|npm|
|github.com/go-logr/logr|v1.2.3|间接依赖|go|
|signal-exit|3.0.7|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|@xmldom/xmldom|0.7.9|间接依赖|npm|
|posix-character-classes|0.1.1|间接依赖|npm|
|css-what|6.1.0|间接依赖|npm|
|@types/svgo|2.6.4|间接依赖|npm|
|snapdragon-node|2.1.1|直接依赖|npm|
|javax.activation:activation|1.1|间接依赖|maven|
|array-unique|0.3.2|间接依赖|npm|
|jsonfile|6.1.0|间接依赖|npm|
|golang.org/x/xerrors|v0.0.0-20220907171357-04be3eba64a2|间接依赖|go|
|isexe|2.0.0|间接依赖|npm|
|unique-filename|2.0.1|间接依赖|npm|
|golang.org/x/net|v0.14.0|间接依赖|go|
|snapdragon-util|3.0.1|间接依赖|npm|
|to-object-path|0.3.0|间接依赖|npm|
|fs-extra|10.1.0|间接依赖|npm|
|run-parallel|1.2.0|间接依赖|npm|
|abbrev|1.1.1|间接依赖|npm|
|entities|4.4.0|间接依赖|npm|
|static-extend|0.1.2|间接依赖|npm|
|mdn-data|2.0.14|间接依赖|npm|
|github.com/go-sql-driver/mysql|v1.6.0|直接依赖|go|
|agent-base|6.0.2|间接依赖|npm|
|ansi-styles|4.3.0|间接依赖|npm|
|nan|2.16.0|间接依赖|npm|
|domhandler|5.0.3|间接依赖|npm|
|graceful-fs|4.2.10|间接依赖|npm|
|expand-brackets|2.1.4|间接依赖|npm|
|is-lambda|1.0.1|间接依赖|npm|
|@nodelib/fs.scandir|2.1.5|间接依赖|npm|
|assign-symbols|1.0.0|间接依赖|npm|
|org.slf4j:slf4j-api|1.7.32|直接依赖|maven|
|github.com/goburrow/modbus|v0.1.0|直接依赖|go|
|svgtofont|3.18.0|直接依赖|npm|
|@types/svg2ttf|5.0.1|间接依赖|npm|
|minipass-fetch|2.1.2|间接依赖|npm|
|string-width|4.2.3|间接依赖|npm|
|cheerio-select|2.1.0|间接依赖|npm|
|org.codehaus.janino:janino|3.0.6|直接依赖|maven|
|split2|1.1.1|间接依赖|npm|
|minipass|3.3.4|间接依赖|npm|
|move-file|2.1.0|间接依赖|npm|
|promise-retry|2.0.1|间接依赖|npm|
|is-windows|1.0.2|间接依赖|npm|
|make-fetch-happen|10.2.1|间接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|@types/cheerio|0.22.31|间接依赖|npm|
|cubic2quad|1.2.1|间接依赖|npm|
|@types/ttf2woff|2.0.2|间接依赖|npm|
|strip-ansi|6.0.1|间接依赖|npm|
|dom-serializer|2.0.0|间接依赖|npm|
|svg-pathdata|6.0.3|间接依赖|npm|
|debug|4.3.4|间接依赖|npm|
|is-plain-object|2.0.4|间接依赖|npm|
|component-emitter|1.3.0|间接依赖|npm|
|github.com/memcachier/mc/v3|v3.0.3|直接依赖|go|
|infer-owner|1.0.4|间接依赖|npm|
|github.com/chromedp/chromedp|v0.8.7|直接依赖|go|
|wrappy|1.0.2|间接依赖|npm|
|glob|7.2.3|间接依赖|npm|
|async|3.2.4|间接依赖|npm|
|github.com/goburrow/serial|v0.1.0|间接依赖|go|
|once|1.4.0|间接依赖|npm|
|google.golang.org/protobuf|v1.27.1|间接依赖|go|
|@npmcli/fs|2.1.2|间接依赖|npm|
|minimist|1.2.6|间接依赖|npm|
|minipass-sized|1.0.3|间接依赖|npm|
|concat-map|0.0.1|间接依赖|npm|
|chalk|4.1.2|间接依赖|npm|
|socks-proxy-agent|7.0.0|间接依赖|npm|
|promise-inflight|1.0.1|间接依赖|npm|
|cache-base|1.0.1|间接依赖|npm|
|end-of-stream|1.4.4|间接依赖|npm|
|github.com/dustin/gomemcached|v0.0.0-20160817010731-a2284a01c143|直接依赖|go|
|encoding|0.1.13|间接依赖|npm|
|boolbase|1.0.0|间接依赖|npm|
|javax.servlet:javax.servlet-api|3.1.0|直接依赖|maven|
|golang.org/x/mod|v0.12.0|间接依赖|go|
|isobject|3.0.1|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|define-property|2.0.2|间接依赖|npm|
|npmlog|6.0.2|间接依赖|npm|
|for-in|1.0.2|间接依赖|npm|
|golang.org/x/sys|v0.11.0|直接依赖|go|
|mkdirp|0.5.6|间接依赖|npm|
|css-tree|1.1.3|间接依赖|npm|
|collection-visit|1.0.0|间接依赖|npm|
|err-code|2.0.3|间接依赖|npm|
|arr-flatten|1.1.0|直接依赖|npm|
|delegates|1.0.0|间接依赖|npm|
|p-map|4.0.0|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|negotiator|0.6.3|间接依赖|npm|
|copy-template-dir|1.4.0|间接依赖|npm|
|htmlparser2|8.0.1|间接依赖|npm|
|github.com/mediocregopher/radix/v3|v3.8.1|直接依赖|go|
|micromatch|4.0.5|间接依赖|npm|
|emoji-regex|8.0.0|间接依赖|npm|
|repeat-element|1.1.4|直接依赖|npm|
|map-cache|0.2.2|间接依赖|npm|
|base|0.11.2|间接依赖|npm|
|sax|1.2.4|间接依赖|npm|
|minizlib|2.1.2|间接依赖|npm|
|github.com/miekg/dns|v1.1.50|直接依赖|go|
|color-support|1.1.3|间接依赖|npm|
|ch.qos.logback:logback-core|1.2.9|直接依赖|maven|
|path-type|4.0.0|间接依赖|npm|
|util-deprecate|1.0.2|间接依赖|npm|
|is-accessor-descriptor|1.0.0|间接依赖|npm|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|clean-stack|2.2.0|间接依赖|npm|
|fs-minipass|2.1.0|间接依赖|npm|
|github.com/godbus/dbus/v5|v5.1.0|直接依赖|go|
|inflight|1.0.6|间接依赖|npm|
|slash|3.0.0|间接依赖|npm|
|@types/ejs|3.1.1|间接依赖|npm|
|argparse|2.0.1|间接依赖|npm|
|is-data-descriptor|1.0.0|间接依赖|npm|
|ret|0.1.15|间接依赖|npm|
|chownr|2.0.0|间接依赖|npm|
|dir-glob|3.0.1|间接依赖|npm|
|cacache|16.1.3|间接依赖|npm|
|is-glob|4.0.3|间接依赖|npm|
|node-gyp|9.2.0|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|has-value|1.0.0|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|to-regex|3.0.2|间接依赖|npm|
|maxstache|1.0.7|间接依赖|npm|
|snapdragon|0.8.2|间接依赖|npm|
|github.com/BurntSushi/locker|v0.0.0-20171006230638-a6e239ea1c69|直接依赖|go|
|escalade|3.1.1|间接依赖|npm|
|glob-parent|5.1.2|间接依赖|npm|
|humanize-ms|1.2.1|间接依赖|npm|
|golang.org/x/sync|v0.3.0|间接依赖|go|
|wrap-ansi|7.0.0|间接依赖|npm|
|through2|2.0.5|间接依赖|npm|
|use|3.1.1|间接依赖|npm|
|map-visit|1.0.0|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|github.com/go-ldap/ldap|v3.0.3+incompatible|直接依赖|go|
|is-extglob|2.1.1|间接依赖|npm|
|@types/svgicons2svgfont|10.0.1|间接依赖|npm|
|https-proxy-agent|5.0.1|间接依赖|npm|
|github.com/chromedp/cdproto|v0.0.0-20230220211738-2b1ec77315c9|直接依赖|go|
|github.com/go-ole/go-ole|v1.2.6|直接依赖|go|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|svg2ttf|6.0.3|间接依赖|npm|
|rimraf|3.0.2|间接依赖|npm|
|parse5-htmlparser2-tree-adapter|7.0.0|间接依赖|npm|
|golang.org/x/tools|v0.11.0|间接依赖|go|
|github.com/go-logfmt/logfmt|v0.5.1|间接依赖|go|
|ttf2eot|3.1.0|间接依赖|npm|
|agentkeepalive|4.2.1|间接依赖|npm|
|retry|0.12.0|间接依赖|npm|
|split-string|3.1.0|间接依赖|npm|
|@npmcli/move-file|2.0.1|间接依赖|npm|
|universalify|2.0.0|间接依赖|npm|
|readable-stream|2.3.7|间接依赖|npm|
|minipass-pipeline|1.2.4|间接依赖|npm|
|cliui|7.0.4|间接依赖|npm|
|del|6.1.1|间接依赖|npm|
|source-map-url|0.4.1|间接依赖|npm|
|ttf2woff2|4.0.5|间接依赖|npm|
|pump|1.0.3|间接依赖|npm|
|repeat-string|1.6.1|直接依赖|npm|
|github.com/mattn/go-sqlite3|v1.14.15|直接依赖|go|
|github.com/chromedp/sysutil|v1.0.0|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.5.4|直接依赖|go|
|object-copy|0.1.0|间接依赖|npm|
|github.com/eclipse/paho.mqtt.golang|v1.4.2|直接依赖|go|
|extglob|2.0.4|直接依赖|npm|
|array-union|2.1.0|间接依赖|npm|
|onelogin/php-saml|^4.0|间接依赖|composer|
|bufferstreams|3.0.0|间接依赖|npm|
|fastq|1.13.0|间接依赖|npm|
|yargs-parser|21.1.1|间接依赖|npm|
|nth-check|2.1.1|间接依赖|npm|
|noop2|2.0.0|间接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|filelist|1.0.4|间接依赖|npm|
|indent-string|4.0.0|间接依赖|npm|
|is-extendable|1.0.1|间接依赖|npm|
|arr-union|3.1.0|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|commander|9.4.1|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)