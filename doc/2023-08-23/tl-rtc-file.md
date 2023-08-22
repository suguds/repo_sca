# tl-open-source/tl-rtc-file安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694056090991157248.svg)](https://www.murphysec.com/console/report/1694056090479452160/1694056090991157248)

仓库描述：webrtc file transfer tool，p2p网页在线文件传输，跨终端，不限平台，内网不限速，支持私有部署，支持多文件拖拽发送，支持本地屏幕录制，远程屏幕共享，远程音视频通话，密码房间，直播，oss云存储，中继服务设置，webrtc检测，统计，文字传输，公共聊天，远程画板，丰富的后台管理，实时执行日志展示，机器人告警通知等功能

仓库地址：[https://github.com/tl-open-source/tl-rtc-file](https://github.com/tl-open-source/tl-rtc-file)

| star：1497 | watch：7 | fork：149 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-20 23:29:36 | 许可证：MIT |
| 最近检测时间：2023-08-23 02:37:05 | 组件总数：343 | 漏洞总数：7 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Http-signature 安全漏洞|密码学签名的验证不恰当|[MPS-2018-6996](https://www.oscs1024.com/hd/MPS-2018-6996)|CVE-2017-16005|高危|
|Socketio Engineio 资源管理错误漏洞|拒绝服务|[MPS-2021-0191](https://www.oscs1024.com/hd/MPS-2021-0191)|CVE-2020-36048|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|tough-cookie 安全漏洞|原型污染|[MPS-2023-5130](https://www.oscs1024.com/hd/MPS-2023-5130)|CVE-2023-26136|严重|
|request SSRF防御绕过漏洞|SSRF|[MPS-2023-7722](https://www.oscs1024.com/hd/MPS-2023-7722)|CVE-2023-28155|中危|
|tough-cookie<4.1.3 存在原型污染漏洞|原型污染|[MPS-esyq-56vx](https://www.oscs1024.com/hd/MPS-esyq-56vx)||中危|
|protobuf.js 安全漏洞|原型污染|[MPS-ql7z-axpv](https://www.oscs1024.com/hd/MPS-ql7z-axpv)|CVE-2023-36665|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|protobufjs|6.11.3|7.2.4|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|engine.io|3.6.1|6.4.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tough-cookie|2.5.0|4.1.3|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|http-signature|1.2.0||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|semver|5.7.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|request|2.88.2||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|253|Low|
|ISC|33|Low|
|BSD-3-Clause|22|Low|
|Unlicense|1|Low|
|Apache-2.0|14|Low|
|BSD-2-Clause|3|Low|
|0BSD|1|Low|
|Python-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|@jridgewell/trace-mapping|0.3.18|间接依赖|npm|
|socket.io-parser|3.3.3|间接依赖|npm|
|emoji-regex|9.2.2|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|universalify|0.1.2|间接依赖|npm|
|protobufjs|7.2.4|间接依赖|npm|
|generate-function|2.3.1|间接依赖|npm|
|get-intrinsic|1.2.1|间接依赖|npm|
|parseuri|0.0.6|间接依赖|npm|
|base64id|2.0.0|间接依赖|npm|
|lodash|4.17.21|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|bcrypt-pbkdf|1.0.2|间接依赖|npm|
|@jridgewell/gen-mapping|0.3.3|间接依赖|npm|
|tweetnacl|0.14.5|间接依赖|npm|
|backo2|1.0.2|间接依赖|npm|
|@types/validator|13.7.17|间接依赖|npm|
|wrappy|1.0.2|间接依赖|npm|
|jsonfile|4.0.0|间接依赖|npm|
|parseqs|0.0.6|间接依赖|npm|
|socket.io-client|2.5.0|间接依赖|npm|
|ansi-styles|4.3.0|间接依赖|npm|
|@grpc/proto-loader|0.7.8|间接依赖|npm|
|@protobufjs/utf8|1.1.0|间接依赖|npm|
|yocto-queue|0.1.0|间接依赖|npm|
|@types/fs-extra|8.1.2|间接依赖|npm|
|finalhandler|1.2.0|间接依赖|npm|
|sequelize-pool|6.1.0|间接依赖|npm|
|path-type|4.0.0|间接依赖|npm|
|buffer-from|1.1.2|间接依赖|npm|
|vary|1.1.2|间接依赖|npm|
|color-name|1.1.4|间接依赖|npm|
|forever-agent|0.6.1|间接依赖|npm|
|blob|0.0.5|间接依赖|npm|
|ansi-colors|4.1.1|间接依赖|npm|
|fill-range|7.0.1|间接依赖|npm|
|combined-stream|1.0.8|间接依赖|npm|
|bytes|3.1.2|间接依赖|npm|
|jackspeak|2.2.1|间接依赖|npm|
|strip-ansi|6.0.1|间接依赖|npm|
|source-map-support|0.5.21|间接依赖|npm|
|to-array|0.1.4|间接依赖|npm|
|ecc-jsbn|0.1.2|间接依赖|npm|
|protobufjs|6.11.3|间接依赖|npm|
|merge2|1.4.1|间接依赖|npm|
|component-emitter|1.3.0|间接依赖|npm|
|ajv|6.12.6|间接依赖|npm|
|uuid|8.3.2|间接依赖|npm|
|source-map|0.6.1|间接依赖|npm|
|is-glob|4.0.3|间接依赖|npm|
|acorn|8.10.0|间接依赖|npm|
|tough-cookie|2.5.0|间接依赖|npm|
|@grpc/grpc-js|1.8.18|间接依赖|npm|
|retry-as-promised|7.0.4|间接依赖|npm|
|send|0.18.0|间接依赖|npm|
|@types/debug|4.1.8|间接依赖|npm|
|dotenv|16.3.1|间接依赖|npm|
|strip-json-comments|3.1.1|间接依赖|npm|
|socket.io-adapter|1.1.2|间接依赖|npm|
|is-number|7.0.0|间接依赖|npm|
|anymatch|3.1.3|间接依赖|npm|
|encodeurl|1.0.2|间接依赖|npm|
|shebang-regex|1.0.0|间接依赖|npm|
|workerpool|6.2.1|间接依赖|npm|
|aws4|1.12.0|间接依赖|npm|
|isstream|0.1.2|间接依赖|npm|
|regenerator-runtime|0.13.11|间接依赖|npm|
|yargs|17.7.2|间接依赖|npm|
|dir-glob|3.0.1|间接依赖|npm|
|lru-cache|10.0.0|间接依赖|npm|
|@nodelib/fs.scandir|2.1.5|间接依赖|npm|
|browser-stdout|1.3.1|间接依赖|npm|
|minimatch|9.0.3|间接依赖|npm|
|cookie|0.4.2|间接依赖|npm|
|@grpc/proto-loader|0.6.13|间接依赖|npm|
|yargs-unparser|2.0.0|间接依赖|npm|
|unpipe|1.0.0|间接依赖|npm|
|strip-ansi|7.1.0|间接依赖|npm|
|fresh|0.5.2|间接依赖|npm|
|@types/glob|7.2.0|间接依赖|npm|
|follow-redirects|1.15.2|间接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|braces|3.0.2|间接依赖|npm|
|debug|4.3.4|间接依赖|npm|
|tree-kill|1.2.2|间接依赖|npm|
|@jridgewell/set-array|1.1.2|间接依赖|npm|
|denque|2.1.0|间接依赖|npm|
|he|1.2.0|间接依赖|npm|
|p-locate|5.0.0|间接依赖|npm|
|escape-string-regexp|4.0.0|间接依赖|npm|
|string-width|5.1.2|间接依赖|npm|
|nanoid|3.3.3|间接依赖|npm|
|range-parser|1.2.1|间接依赖|npm|
|engine.io|3.6.1|间接依赖|npm|
|isarray|2.0.1|间接依赖|npm|
|negotiator|0.6.3|间接依赖|npm|
|p-limit|3.1.0|间接依赖|npm|
|har-validator|5.1.5|间接依赖|npm|
|@protobufjs/fetch|1.1.0|间接依赖|npm|
|wrap-ansi|7.0.0|间接依赖|npm|
|assert-plus|1.0.0|间接依赖|npm|
|cross-env|5.2.1|间接依赖|npm|
|@types/ms|0.7.31|间接依赖|npm|
|postcss|8.4.25|间接依赖|npm|
|extsprintf|1.3.0|间接依赖|npm|
|escape-html|1.0.3|间接依赖|npm|
|seq-queue|0.0.5|间接依赖|npm|
|long|4.0.0|间接依赖|npm|
|readdirp|3.6.0|间接依赖|npm|
|js-yaml|4.1.0|间接依赖|npm|
|asynckit|0.4.0|间接依赖|npm|
|http-signature|1.2.0|间接依赖|npm|
|shell-quote|1.8.1|间接依赖|npm|
|@nodelib/fs.walk|1.2.8|间接依赖|npm|
|moment-timezone|0.5.43|间接依赖|npm|
|cross-spawn|6.0.5|间接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|ansi-regex|6.0.1|间接依赖|npm|
|fs.realpath|1.0.0|间接依赖|npm|
|cliui|7.0.4|间接依赖|npm|
|engine.io-parser|2.2.1|间接依赖|npm|
|ms|2.1.3|间接依赖|npm|
|serve-static|1.15.0|间接依赖|npm|
|oauth-sign|0.9.0|间接依赖|npm|
|jsprim|1.4.2|间接依赖|npm|
|has-flag|4.0.0|间接依赖|npm|
|mime-db|1.52.0|间接依赖|npm|
|date-fns|2.30.0|间接依赖|npm|
|wkx|0.5.0|间接依赖|npm|
|path-to-regexp|0.1.7|间接依赖|npm|
|globby|10.0.1|间接依赖|npm|
|esbuild|0.18.11|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|aws-sign2|0.7.0|间接依赖|npm|
|object-inspect|1.12.3|间接依赖|npm|
|locate-path|6.0.0|间接依赖|npm|
|form-data|2.3.3|间接依赖|npm|
|arraybuffer.slice|0.0.7|间接依赖|npm|
|has-symbols|1.0.3|间接依赖|npm|
|has-cors|1.1.0|间接依赖|npm|
|colorette|1.4.0|间接依赖|npm|
|glob|7.2.3|间接依赖|npm|
|yeast|0.1.2|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|methods|1.1.2|间接依赖|npm|
|queue-microtask|1.2.3|间接依赖|npm|
|supports-color|7.2.0|间接依赖|npm|
|wrap-ansi|8.1.0|间接依赖|npm|
|@protobufjs/codegen|2.0.4|间接依赖|npm|
|tl-ngrpc|1.0.1|间接依赖|npm|
|xmlhttprequest-ssl|1.6.3|间接依赖|npm|
|yargs|16.2.0|间接依赖|npm|
|etag|1.8.1|间接依赖|npm|
|slash|3.0.0|间接依赖|npm|
|rxjs|7.8.1|间接依赖|npm|
|tunnel-agent|0.6.0|间接依赖|npm|
|spawn-command|0.0.2|间接依赖|npm|
|glob|10.3.1|间接依赖|npm|
|semver|5.7.1|间接依赖|npm|
|eastasianwidth|0.2.0|间接依赖|npm|
|component-bind|1.0.0|间接依赖|npm|
|randombytes|2.1.0|间接依赖|npm|
|sequelize|6.32.1|间接依赖|npm|
|chalk|4.1.2|间接依赖|npm|
|on-finished|2.4.1|间接依赖|npm|
|has-proto|1.0.1|间接依赖|npm|
|path-exists|4.0.0|间接依赖|npm|
|express|4.18.2|间接依赖|npm|
|lodash.camelcase|4.3.0|间接依赖|npm|
|@protobufjs/float|1.0.2|间接依赖|npm|
|nice-try|1.0.5|间接依赖|npm|
|iconv-lite|0.6.3|间接依赖|npm|
|which|1.3.1|间接依赖|npm|
|@babel/runtime|7.22.6|间接依赖|npm|
|minipass|6.0.2|间接依赖|npm|
|form-data|4.0.0|间接依赖|npm|
|ms|2.0.0|间接依赖|npm|
|jsbn|0.1.1|间接依赖|npm|
|socket.io|2.5.0|间接依赖|npm|
|@protobufjs/pool|1.1.0|间接依赖|npm|
|array-union|2.1.0|间接依赖|npm|
|destroy|1.2.0|间接依赖|npm|
|is-plain-object|3.0.1|间接依赖|npm|
|path-scurry|1.10.0|间接依赖|npm|
|lru-cache|7.18.3|间接依赖|npm|
|shebang-command|1.2.0|间接依赖|npm|
|cross-spawn|7.0.3|间接依赖|npm|
|is-typedarray|1.0.0|间接依赖|npm|
|nanoid|3.3.6|间接依赖|npm|
|setprototypeof|1.2.0|间接依赖|npm|
|moment|2.29.4|间接依赖|npm|
|tslib|2.6.1|间接依赖|npm|
|content-disposition|0.5.4|间接依赖|npm|
|lru-cache|6.0.0|间接依赖|npm|
|cookie-signature|1.0.6|间接依赖|npm|
|yallist|4.0.0|间接依赖|npm|
|has-binary2|1.0.3|间接依赖|npm|
|argparse|2.0.1|间接依赖|npm|
|mocha|10.2.0|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|asn1|0.2.6|间接依赖|npm|
|named-placeholders|1.1.3|间接依赖|npm|
|mime|1.6.0|间接依赖|npm|
|debug|2.6.9|间接依赖|npm|
|chokidar|3.5.3|间接依赖|npm|
|core-util-is|1.0.2|间接依赖|npm|
|path-is-absolute|1.0.1|间接依赖|npm|
|@types/long|4.0.2|间接依赖|npm|
|binary-extensions|2.2.0|间接依赖|npm|
|decamelize|4.0.0|间接依赖|npm|
|@protobufjs/inquire|1.1.0|间接依赖|npm|
|utils-merge|1.0.1|间接依赖|npm|
|qs|6.11.0|间接依赖|npm|
|micromatch|4.0.5|间接依赖|npm|
|parseurl|1.3.3|间接依赖|npm|
|commander|2.20.3|间接依赖|npm|
|toidentifier|1.0.1|间接依赖|npm|
|is-binary-path|2.1.0|间接依赖|npm|
|base64-arraybuffer|0.1.4|间接依赖|npm|
|dottie|2.0.6|间接依赖|npm|
|rollup-plugin-copy|3.4.0|间接依赖|npm|
|@nodelib/fs.stat|2.0.5|间接依赖|npm|
|raw-body|2.5.1|间接依赖|npm|
|emoji-regex|8.0.0|间接依赖|npm|
|@protobufjs/path|1.1.2|间接依赖|npm|
|@isaacs/cliui|8.0.2|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|dashdash|1.14.1|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|reusify|1.0.4|间接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|camelcase|6.3.0|间接依赖|npm|
|@jridgewell/source-map|0.3.5|间接依赖|npm|
|delayed-stream|1.0.0|间接依赖|npm|
|sshpk|1.17.0|间接依赖|npm|
|after|0.8.2|间接依赖|npm|
|extend|3.0.2|间接依赖|npm|
|caseless|0.12.0|间接依赖|npm|
|@types/minimatch|5.1.2|间接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.15|间接依赖|npm|
|qs|6.5.3|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|pg-connection-string|2.6.1|间接依赖|npm|
|google-protobuf|3.21.2|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|brace-expansion|2.0.1|间接依赖|npm|
|flat|5.0.2|间接依赖|npm|
|array-flatten|1.1.1|间接依赖|npm|
|@types/node|20.4.0|间接依赖|npm|
|fs-extra|8.1.0|间接依赖|npm|
|cookie|0.5.0|间接依赖|npm|
|json-schema|0.4.0|间接依赖|npm|
|axios|0.26.1|间接依赖|npm|
|validator|13.9.0|间接依赖|npm|
|component-inherit|0.0.3|间接依赖|npm|
|ansi-styles|6.2.1|间接依赖|npm|
|fastq|1.15.0|间接依赖|npm|
|sqlstring|2.3.3|间接依赖|npm|
|component-emitter|1.2.1|间接依赖|npm|
|picomatch|2.3.1|间接依赖|npm|
|media-typer|0.3.0|间接依赖|npm|
|mime-types|2.1.35|间接依赖|npm|
|ws|7.4.6|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|picocolors|1.0.0|间接依赖|npm|
|ee-first|1.1.1|间接依赖|npm|
|diff|5.0.0|间接依赖|npm|
|proxy-addr|2.0.7|间接依赖|npm|
|glob|7.2.0|间接依赖|npm|
|har-schema|2.0.0|间接依赖|npm|
|log-symbols|4.1.0|间接依赖|npm|
|graceful-fs|4.2.11|间接依赖|npm|
|long|5.2.3|间接依赖|npm|
|minimatch|5.0.1|间接依赖|npm|
|debug|3.1.0|间接依赖|npm|
|openai|3.3.0|间接依赖|npm|
|source-map-js|1.0.2|间接依赖|npm|
|performance-now|2.1.0|间接依赖|npm|
|getpass|0.1.7|间接依赖|npm|
|@protobufjs/aspromise|1.1.2|间接依赖|npm|
|terser|5.18.2|间接依赖|npm|
|is-plain-obj|2.1.0|间接依赖|npm|
|yargs-parser|20.2.4|间接依赖|npm|
|concurrently|8.2.0|间接依赖|npm|
|is-property|1.0.2|间接依赖|npm|
|safe-buffer|5.2.1|间接依赖|npm|
|vite|4.4.1|间接依赖|npm|
|minimatch|3.1.2|间接依赖|npm|
|request|2.88.2|间接依赖|npm|
|type-is|1.6.18|间接依赖|npm|
|content-type|1.0.5|间接依赖|npm|
|indexof|0.0.1|间接依赖|npm|
|run-parallel|1.2.0|间接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|@protobufjs/base64|1.1.2|间接依赖|npm|
|toposort-class|1.0.1|间接依赖|npm|
|is-extglob|2.1.1|间接依赖|npm|
|merge-descriptors|1.0.1|间接依赖|npm|
|call-bind|1.0.2|间接依赖|npm|
|supports-color|8.1.1|间接依赖|npm|
|find-up|5.0.0|间接依赖|npm|
|normalize-path|3.0.0|间接依赖|npm|
|mysql2|2.3.3|间接依赖|npm|
|serialize-javascript|6.0.0|间接依赖|npm|
|body-parser|1.20.1|间接依赖|npm|
|json-stringify-safe|5.0.1|间接依赖|npm|
|sequelize-pool|7.1.0|间接依赖|npm|
|@protobufjs/eventemitter|1.1.0|间接依赖|npm|
|ignore|5.2.4|间接依赖|npm|
|glob-parent|5.1.2|间接依赖|npm|
|uuid|3.4.0|间接依赖|npm|
|is-unicode-supported|0.1.0|间接依赖|npm|
|path-key|2.0.1|间接依赖|npm|
|statuses|2.0.1|间接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|verror|1.10.0|间接依赖|npm|
|string-width|4.2.3|间接依赖|npm|
|punycode|2.3.0|间接依赖|npm|
|http-errors|2.0.0|间接依赖|npm|
|y18n|5.0.8|间接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.14|间接依赖|npm|
|side-channel|1.0.4|间接依赖|npm|
|semver|7.5.3|间接依赖|npm|
|engine.io-client|3.5.3|间接依赖|npm|
|ipaddr.js|1.9.1|间接依赖|npm|
|color-convert|2.0.1|间接依赖|npm|
|signal-exit|4.0.2|间接依赖|npm|
|iconv-lite|0.4.24|间接依赖|npm|
|forwarded|0.2.0|间接依赖|npm|
|@jridgewell/resolve-uri|3.1.0|间接依赖|npm|
|accepts|1.3.8|间接依赖|npm|
|inflection|1.13.4|间接依赖|npm|
|socket.io-parser|3.4.3|间接依赖|npm|
|psl|1.9.0|间接依赖|npm|
|foreground-child|3.1.1|间接依赖|npm|
|depd|2.0.0|间接依赖|npm|
|to-regex-range|5.0.1|间接依赖|npm|
|rollup|3.26.2|间接依赖|npm|
|fast-glob|3.3.0|间接依赖|npm|
|debug|4.1.1|间接依赖|npm|
|isexe|2.0.0|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)