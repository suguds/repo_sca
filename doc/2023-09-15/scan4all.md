# hktalent/scan4all安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1702385154122366976.svg)](https://www.murphysec.com/console/report/1702385154084618240/1702385154122366976)

仓库描述：Official repository  vuls Scan: 15000+PoCs; 23 kinds of application password crack; 7000+Web fingerprints; 146 protocols and 90000+ rules Port scanning; Fuzz, HW, awesome BugBounty( ͡° ͜ʖ ͡°)...

仓库地址：[https://github.com/hktalent/scan4all](https://github.com/hktalent/scan4all)

| star：3964 | watch：51 | fork：476 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-04 10:28:26 | 许可证：BSD-3-Clause |
| 最近检测时间：2023-09-15 02:15:38 | 组件总数：404 | 漏洞总数：20 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Http-signature 安全漏洞|密码学签名的验证不恰当|[MPS-2018-6996](https://www.oscs1024.com/hd/MPS-2018-6996)|CVE-2017-16005|高危|
|Ajv v6.12.2 输入验证错误漏洞|MAID|[MPS-2020-10525](https://www.oscs1024.com/hd/MPS-2020-10525)|CVE-2020-15366|中危|
|Ini <1.3.6原型污染漏洞|拒绝服务|[MPS-2020-17544](https://www.oscs1024.com/hd/MPS-2020-17544)|CVE-2020-7788|高危|
|minimist 原型污染漏洞|原型污染|[MPS-2020-3516](https://www.oscs1024.com/hd/MPS-2020-3516)|CVE-2020-7598|中危|
|node-tar 路径遍历漏洞|路径遍历|[MPS-2021-11547](https://www.oscs1024.com/hd/MPS-2021-11547)|CVE-2021-32804|高危|
|node-tar 路径遍历漏洞|在文件访问前对链接解析不恰当（链接跟随）|[MPS-2021-11548](https://www.oscs1024.com/hd/MPS-2021-11548)|CVE-2021-32803|高危|
|Npm Node-tar 后置链接漏洞||[MPS-2021-28486](https://www.oscs1024.com/hd/MPS-2021-28486)|CVE-2021-37701|高危|
|Npm Node-tar 后置链接漏洞||[MPS-2021-28488](https://www.oscs1024.com/hd/MPS-2021-28488)|CVE-2021-37712|高危|
|node-tar 路径遍历漏洞|路径遍历|[MPS-2021-28489](https://www.oscs1024.com/hd/MPS-2021-28489)|CVE-2021-37713|高危|
|json-schema 安全漏洞|原型污染|[MPS-2021-34478](https://www.oscs1024.com/hd/MPS-2021-34478)|CVE-2021-3918|严重|
|minimist 安全漏洞|原型污染|[MPS-2021-38405](https://www.oscs1024.com/hd/MPS-2021-38405)|CVE-2021-44906|严重|
|go.uuid 不安全的随机性漏洞|使用具有密码学弱点缺陷的PRNG|[MPS-2021-7854](https://www.oscs1024.com/hd/MPS-2021-7854)|CVE-2021-3538|严重|
|tar 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2022-14081](https://www.oscs1024.com/hd/MPS-2022-14081)||低危|
|Express 中的 qs 模块存在原型污染漏洞|原型污染|[MPS-2022-3967](https://www.oscs1024.com/hd/MPS-2022-3967)|CVE-2022-24999|高危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|minimatch 资源管理错误漏洞|拒绝服务|[MPS-2022-59845](https://www.oscs1024.com/hd/MPS-2022-59845)|CVE-2022-3517|高危|
|needle 存在Authorization请求头泄露漏洞|未授权敏感信息泄露|[MPS-2022-7866](https://www.oscs1024.com/hd/MPS-2022-7866)||中危|
|tough-cookie 安全漏洞|原型污染|[MPS-2023-5130](https://www.oscs1024.com/hd/MPS-2023-5130)|CVE-2023-26136|严重|
|request SSRF防御绕过漏洞|SSRF|[MPS-2023-7722](https://www.oscs1024.com/hd/MPS-2023-7722)|CVE-2023-28155|中危|
|tough-cookie<4.1.3 存在原型污染漏洞|原型污染|[MPS-esyq-56vx](https://www.oscs1024.com/hd/MPS-esyq-56vx)||中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|minimatch|3.0.4|3.0.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|json-schema|0.2.3|0.4.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|minimist|0.0.8|1.2.6|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|minimist|1.2.0|1.2.6|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|tar|4.4.8|6.1.9|间接依赖|建议修复|C:0|H:5|M:0|L:1|
|qs|6.5.2|6.10.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|github.com/satori/go.uuid|v1.2.0||直接依赖|建议修复|C:1|H:0|M:0|L:0|
|ini|1.3.5|1.3.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|http-signature|1.2.0||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|tough-cookie|2.5.0|4.1.3|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|needle|2.2.4|3.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|request|2.88.2||直接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|5.6.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|ajv|6.12.2|6.12.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|231|Low|
|ISC|38|Low|
|BSD-3-Clause|57|Low|
|Apache-2.0|45|Low|
|BSD-2-Clause|11|Low|
|MPL-2.0|8|Low|
|Unlicense|3|Low|
|GPL-3.0|1|Medium|
|ICU|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/olivere/elastic|v6.2.37+incompatible|直接依赖|go|
|abbrev|1.1.1|间接依赖|npm|
|github.com/projectdiscovery/iputil|v0.0.2|直接依赖|go|
|/usr/lib/libSystem.B.dylib||间接依赖||
|github.com/gofrs/uuid|v4.4.0+incompatible|间接依赖|go|
|github.com/spf13/cast|v1.5.1|间接依赖|go|
|extsprintf|1.3.0|间接依赖|npm|
|github.com/refraction-networking/utls|v1.5.2|间接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.0|间接依赖|go|
|path-is-absolute|1.0.1|间接依赖|npm|
|github.com/phayes/freeport|v0.0.0-20220201140144-74d24b5ae9f5|直接依赖|go|
|aws-sign2|0.7.0|间接依赖|npm|
|github.com/projectdiscovery/urlutil|v0.0.1|直接依赖|go|
|webidl-conversions|4.0.2|间接依赖|npm|
|github.com/pion/mdns|v0.0.8|间接依赖|go|
|github.com/c4milo/unpackit|v1.0.0|间接依赖|go|
|golang.org/x/time|v0.3.0|直接依赖|go|
|github.com/templexxx/xor|v0.0.0-20191217153810-f85b25db303b|间接依赖|go|
|github.com/projectdiscovery/naabu/v2|v2.1.7|直接依赖|go|
|minimist|1.2.0|间接依赖|npm|
|needle|2.2.4|间接依赖|npm|
|http-signature|1.2.0|间接依赖|npm|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|github.com/yusufpapurcu/wmi|v1.2.3|间接依赖|go|
|github.com/BurntSushi/toml|v1.2.0|间接依赖|go|
|github.com/nwaples/rardecode|v1.1.3|间接依赖|go|
|github.com/projectdiscovery/networkpolicy|v0.0.6|直接依赖|go|
|github.com/jcmturner/aescts/v2|v2.0.0|间接依赖|go|
|code-point-at|1.1.0|间接依赖|npm|
|github.com/rivo/uniseg|v0.4.4|间接依赖|go|
|are-we-there-yet|1.1.5|间接依赖|npm|
|jsprim|1.4.1|间接依赖|npm|
|github.com/gobwas/httphead|v0.1.0|间接依赖|go|
|github.com/panjf2000/ants/v2|v2.8.1|直接依赖|go|
|github.com/benbjohnson/clock|v1.3.5|间接依赖|go|
|ansi-regex|2.1.1|间接依赖|npm|
|google.golang.org/protobuf|v1.31.0|直接依赖|go|
|github.com/projectdiscovery/retryabledns|v1.0.35|间接依赖|go|
|github.com/projectdiscovery/retryablehttp-go|v1.0.24|直接依赖|go|
|github.com/quic-go/qtls-go1-20|v0.3.3|间接依赖|go|
|tunnel-agent|0.6.0|间接依赖|npm|
|github.com/pion/rtp|v1.8.1|间接依赖|go|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|github.com/satori/go.uuid|v1.2.0|直接依赖|go|
|form-data|2.3.3|间接依赖|npm|
|github.com/projectdiscovery/dnsx|v1.1.4|直接依赖|go|
|github.com/fortytw2/leaktest|v1.3.0|间接依赖|go|
|golang.org/x/crypto|v0.12.0|直接依赖|go|
|npm-bundled|1.0.6|间接依赖|npm|
|github.com/projectdiscovery/goconfig|v0.0.1|直接依赖|go|
|detect-libc|1.0.3|间接依赖|npm|
|github.com/magiconair/properties|v1.8.7|间接依赖|go|
|github.com/aymanbagabas/go-osc52/v2|v2.0.1|间接依赖|go|
|github.com/projectdiscovery/sliceutil|v0.0.1|直接依赖|go|
|github.com/gosuri/uiprogress|v0.0.1|间接依赖|go|
|github.com/spaolacci/murmur3|v1.1.0|直接依赖|go|
|psl|1.8.0|间接依赖|npm|
|node-pre-gyp|0.13.0|间接依赖|npm|
|github.com/projectdiscovery/httputil|v0.0.1|直接依赖|go|
|debug|2.6.9|间接依赖|npm|
|github.com/projectdiscovery/freeport|v0.0.5|间接依赖|go|
|semver|5.6.0|间接依赖|npm|
|npmlog|4.1.2|间接依赖|npm|
|github.com/charmbracelet/glamour|v0.6.0|间接依赖|go|
|github.com/masterzen/winrm|v0.0.0-20220917170901-b07f6cb0598d|直接依赖|go|
|github.com/xi2/xz|v0.0.0-20171230120015-48954b6210f8|间接依赖|go|
|github.com/gosuri/uilive|v0.0.4|间接依赖|go|
|tar|4.4.8|间接依赖|npm|
|github.com/gorilla/websocket|v1.5.0|直接依赖|go|
|github.com/urfave/cli/v2|v2.16.3|直接依赖|go|
|github.com/lunixbochs/struc|v0.0.0-20200707160740-784aaebc1d40|直接依赖|go|
|github.com/youmark/pkcs8|v0.0.0-20201027041543-1326539a0a0a|间接依赖|go|
|github.com/shirou/gopsutil/v3|v3.23.7|直接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|caseless|0.12.0|间接依赖|npm|
|github.com/spf13/afero|v1.9.5|间接依赖|go|
|golang.org/x/tools|v0.12.1-0.20230815132531-74c255bcf846|间接依赖|go|
|github.com/mattn/go-runewidth|v0.0.15|间接依赖|go|
|asynckit|0.4.0|间接依赖|npm|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|github.com/alecthomas/chroma|v0.10.0|间接依赖|go|
|safe-buffer|5.1.2|间接依赖|npm|
|ms|2.0.0|间接依赖|npm|
|github.com/mattn/go-isatty|v0.0.19|间接依赖|go|
|github.com/dustin/go-humanize|v1.0.1|间接依赖|go|
|github.com/Azure/go-ntlmssp|v0.0.0-20221128193559-754e69321358|间接依赖|go|
|github.com/rs/xid|v1.5.0|直接依赖|go|
|github.com/spf13/viper|v1.16.0|直接依赖|go|
|safe-buffer|5.2.1|间接依赖|npm|
|github.com/denisenkom/go-mssqldb|v0.12.3|直接依赖|go|
|has-unicode|2.0.1|间接依赖|npm|
|console-control-strings|1.1.0|间接依赖|npm|
|github.com/dsnet/compress|v0.0.1|间接依赖|go|
|fs.realpath|1.0.0|间接依赖|npm|
|github.com/pierrec/lz4|v2.6.1+incompatible|间接依赖|go|
|github.com/xrash/smetrics|v0.0.0-20201216005158-039620a65673|间接依赖|go|
|github.com/yuin/goldmark|v1.5.6|间接依赖|go|
|github.com/klauspost/compress|v1.16.7|间接依赖|go|
|ecc-jsbn|0.1.2|间接依赖|npm|
|github.com/tidwall/match|v1.1.1|间接依赖|go|
|sshpk|1.16.1|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|github.com/andybalholm/cascadia|v1.3.2|间接依赖|go|
|github.com/jlaffaye/ftp|v0.2.0|直接依赖|go|
|github.com/gobwas/ws|v1.3.0|间接依赖|go|
|go.mongodb.org/mongo-driver|v1.12.1|直接依赖|go|
|is-typedarray|1.0.0|间接依赖|npm|
|github.com/montanaflynn/stats|v0.7.1|间接依赖|go|
|fs-minipass|1.2.5|间接依赖|npm|
|golang.org/x/sys|v0.11.0|直接依赖|go|
|github.com/xdg-go/pbkdf2|v1.0.0|间接依赖|go|
|github.com/hashicorp/go-uuid|v1.0.3|间接依赖|go|
|github.com/jcmturner/goidentity/v6|v6.0.1|间接依赖|go|
|github.com/projectdiscovery/goflags|v0.1.18|直接依赖|go|
|github.com/gosnmp/gosnmp|v1.36.0|直接依赖|go|
|signal-exit|3.0.2|间接依赖|npm|
|github.com/projectdiscovery/rawhttp|v0.1.18|直接依赖|go|
|github.com/pion/dtls/v2|v2.2.7|间接依赖|go|
|github.com/spf13/jwalterweatherman|v1.1.0|间接依赖|go|
|github.com/pion/logging|v0.2.2|间接依赖|go|
|uri-js|4.2.2|间接依赖|npm|
|ini|1.3.5|间接依赖|npm|
|tough-cookie|2.5.0|间接依赖|npm|
|chownr|1.1.1|间接依赖|npm|
|github.com/ulikunitz/xz|v0.5.11|间接依赖|go|
|gorm.io/driver/mysql|v1.5.1|间接依赖|go|
|getpass|0.1.7|间接依赖|npm|
|glob|7.1.3|间接依赖|npm|
|github.com/muesli/termenv|v0.15.2|间接依赖|go|
|github.com/syndtr/goleveldb|v1.0.0|间接依赖|go|
|github.com/txthinking/runnergroup|v0.0.0-20230325130830-408dc5853f86|间接依赖|go|
|github.com/golang-sql/sqlexp|v0.1.0|间接依赖|go|
|github.com/PuerkitoBio/goquery|v1.8.1|直接依赖|go|
|github.com/go-sql-driver/mysql|v1.7.1|直接依赖|go|
|is-fullwidth-code-point|1.0.0|间接依赖|npm|
|github.com/stoewer/go-strcase|v1.3.0|间接依赖|go|
|string-width|2.1.1|间接依赖|npm|
|github.com/Ullaakut/nmap|v2.0.2+incompatible|直接依赖|go|
|github.com/golang/snappy|v0.0.4|间接依赖|go|
|github.com/weppos/publicsuffix-go|v0.30.2-0.20230730094716-a20f9abcc222|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/cloudflare/circl|v1.3.3|间接依赖|go|
|os-tmpdir|1.0.2|间接依赖|npm|
|minimist|0.0.8|间接依赖|npm|
|github.com/xtaci/kcp-go|v5.4.20+incompatible|间接依赖|go|
|isarray|1.0.0|间接依赖|npm|
|github.com/tklauser/go-sysconf|v0.3.12|间接依赖|go|
|github.com/patrickmn/go-cache|v2.1.0+incompatible|间接依赖|go|
|wrtc|0.4.7|直接依赖|npm|
|github.com/jinzhu/inflection|v1.0.0|间接依赖|go|
|github.com/cnf/structhash|v0.0.0-20201127153200-e1b16c1ebc08|间接依赖|go|
|github.com/deckarep/golang-set|v1.8.0|间接依赖|go|
|github.com/hbakhtiyor/strsim|v0.0.0-20190107154042-4d2bbb273edf|直接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/antlr/antlr4/runtime/Go/antlr/v4|v4.0.0-20230305170008-8188dc5388df|间接依赖|go|
|github.com/jcmturner/gofork|v1.7.6|间接依赖|go|
|go.uber.org/atomic|v1.11.0|间接依赖|go|
|github.com/bluele/gcache|v0.0.2|直接依赖|go|
|github.com/karlseguin/ccache|v2.0.3+incompatible|直接依赖|go|
|github.com/jcmturner/dnsutils/v2|v2.0.0|间接依赖|go|
|github.com/masterzen/simplexml|v0.0.0-20190410153822-31eea3082786|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|assert-plus|1.0.0|间接依赖|npm|
|github.com/hktalent/htmlquery|v0.0.0-20230303073607-1fbec5a16112|间接依赖|go|
|rc|1.2.8|间接依赖|npm|
|github.com/apex/log|v1.9.0|间接依赖|go|
|github.com/zmap/zcrypto|v0.0.0-20230829152017-3b5d61809233|间接依赖|go|
|aead.dev/minisign|v0.2.0|间接依赖|go|
|github.com/projectdiscovery/mapcidr|v1.1.2|直接依赖|go|
|readable-stream|2.3.6|间接依赖|npm|
|/usr/lib/libresolv.9.dylib||间接依赖||
|golang.org/x/net|v0.14.0|直接依赖|go|
|github.com/projectdiscovery/wappalyzergo|v0.0.109|直接依赖|go|
|github.com/lib/pq|v1.10.9|直接依赖|go|
|github.com/huin/asn1ber|v0.0.0-20120622192748-af09f62e6358|直接依赖|go|
|minimatch|3.0.4|间接依赖|npm|
|github.com/yuin/goldmark-emoji|v1.0.2|间接依赖|go|
|safer-buffer|2.1.2|间接依赖|npm|
|github.com/go-ole/go-ole|v1.3.0|间接依赖|go|
|github.com/chromedp/chromedp|v0.9.2|直接依赖|go|
|github.com/projectdiscovery/fdmax|v0.0.4|直接依赖|go|
|github.com/aymerick/douceur|v0.2.0|间接依赖|go|
|github.com/corpix/uarand|v0.2.0|直接依赖|go|
|github.com/pion/sctp|v1.8.8|间接依赖|go|
|github.com/tklauser/numcpus|v0.6.1|间接依赖|go|
|github.com/tidwall/btree|v1.6.0|间接依赖|go|
|github.com/lufia/plan9stats|v0.0.0-20230326075908-cb1d2100619a|间接依赖|go|
|github.com/gorilla/css|v1.0.0|间接依赖|go|
|delayed-stream|1.0.0|间接依赖|npm|
|github.com/tidwall/gjson|v1.16.0|间接依赖|go|
|github.com/gogf/gf|v1.16.9|间接依赖|go|
|github.com/projectdiscovery/ipranger|v0.0.9|直接依赖|go|
|github.com/pion/rtcp|v1.2.10|间接依赖|go|
|sax|1.2.4|间接依赖|npm|
|github.com/akrylysov/pogreb|v0.10.1|间接依赖|go|
|github.com/subosito/gotenv|v1.6.0|间接依赖|go|
|github.com/tidwall/grect|v0.1.4|间接依赖|go|
|github.com/projectdiscovery/cryptoutil|v1.0.0|直接依赖|go|
|github.com/hktalent/go-update|v0.0.0-20230526022740-3a2ce0d34057|间接依赖|go|
|set-blocking|2.0.0|间接依赖|npm|
|github.com/projectdiscovery/gologger|v1.1.11|直接依赖|go|
|github.com/dlclark/regexp2|v1.10.0|直接依赖|go|
|github.com/projectdiscovery/asnmap|v1.0.4|间接依赖|go|
|golang.org/x/mod|v0.12.0|间接依赖|go|
|github.com/projectdiscovery/uncover|v1.0.6|直接依赖|go|
|github.com/pion/randutil|v0.1.0|间接依赖|go|
|github.com/projectdiscovery/fileutil|v0.0.3|直接依赖|go|
|github.com/projectdiscovery/hmap|v0.0.16|直接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|punycode|2.1.1|间接依赖|npm|
|github.com/wsxiaoys/terminal|v0.0.0-20160513160801-0940f3fc43a0|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|直接依赖|go|
|github.com/google/go-github|v17.0.0+incompatible|间接依赖|go|
|github.com/dgraph-io/badger|v1.6.2|直接依赖|go|
|github.com/simonnilsson/ask|v0.4.0|直接依赖|go|
|fast-deep-equal|3.1.1|间接依赖|npm|
|github.com/pion/srtp/v2|v2.0.16|间接依赖|go|
|/System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation||间接依赖||
|github.com/hktalent/go-utils|v0.0.0-20230901081911-56ba7aaf0651|直接依赖|go|
|github.com/antlabs/strsim|v0.0.3|直接依赖|go|
|core-util-is|1.0.2|间接依赖|npm|
|minipass|2.3.5|间接依赖|npm|
|json-stringify-safe|5.0.1|间接依赖|npm|
|github.com/hashicorp/go-multierror|v1.1.1|间接依赖|go|
|go.etcd.io/bbolt|v1.3.7|间接依赖|go|
|github.com/dgryski/go-farm|v0.0.0-20200201041132-a6ae2369ad13|间接依赖|go|
|github.com/yl2chen/cidranger|v1.0.2|间接依赖|go|
|github.com/codegangsta/inject|v0.0.0-20150114235600-33e0aa1cb7c0|直接依赖|go|
|inherits|2.0.3|间接依赖|npm|
|gauge|2.7.4|间接依赖|npm|
|github.com/russross/blackfriday/v2|v2.1.0|间接依赖|go|
|tweetnacl|0.14.5|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|github.com/pion/turn/v2|v2.1.3|间接依赖|go|
|domexception|1.0.1|直接依赖|npm|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/pion/interceptor|v0.1.17|间接依赖|go|
|ajv|6.12.2|间接依赖|npm|
|json-schema-traverse|0.4.1|间接依赖|npm|
|bcrypt-pbkdf|1.0.2|间接依赖|npm|
|isstream|0.1.2|间接依赖|npm|
|gorm.io/gorm|v1.25.4|直接依赖|go|
|github.com/google/pprof|v0.0.0-20230821062121-407c9e7a662f|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|间接依赖|go|
|github.com/xdg-go/scram|v1.1.2|间接依赖|go|
|brace-expansion|1.1.11|间接依赖|npm|
|aws4|1.10.0|间接依赖|npm|
|github.com/Masterminds/semver/v3|v3.2.1|间接依赖|go|
|github.com/projectdiscovery/clistats|v0.0.19|直接依赖|go|
|oauth-sign|0.9.0|间接依赖|npm|
|github.com/dgraph-io/ristretto|v0.1.1|间接依赖|go|
|github.com/andybalholm/brotli|v1.0.5|间接依赖|go|
|github.com/pion/ice/v2|v2.3.10|间接依赖|go|
|github.com/emersion/go-message|v0.17.0|直接依赖|go|
|github.com/pion/webrtc/v3|v3.2.17|间接依赖|go|
|github.com/cpuguy83/go-md2man/v2|v2.0.2|间接依赖|go|
|github.com/coreos/etcd|v3.3.27+incompatible|间接依赖|go|
|github.com/gobwas/pool|v0.2.1|间接依赖|go|
|string-width|1.0.2|间接依赖|npm|
|github.com/klauspost/cpuid/v2|v2.2.5|间接依赖|go|
|golang.org/x/term|v0.11.0|间接依赖|go|
|github.com/projectdiscovery/ratelimit|v0.0.9|间接依赖|go|
|github.com/google/go-github/v30|v30.1.0|间接依赖|go|
|github.com/go-task/slim-sprig|v0.0.0-20230315185526-52ccab3ef572|间接依赖|go|
|github.com/hktalent/jarm-go|v0.0.0-20220918133110-7801447b6267|直接依赖|go|
|github.com/pion/stun|v0.6.1|间接依赖|go|
|strip-json-comments|2.0.1|间接依赖|npm|
|golang.org/x/oauth2|v0.11.0|间接依赖|go|
|github.com/antchfx/xpath|v1.2.4|间接依赖|go|
|yallist|3.0.3|间接依赖|npm|
|github.com/tidwall/buntdb|v1.3.0|间接依赖|go|
|github.com/klauspost/pgzip|v1.2.6|间接依赖|go|
|har-validator|5.1.3|间接依赖|npm|
|go.uber.org/multierr|v1.11.0|间接依赖|go|
|github.com/klauspost/reedsolomon|v1.11.8|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|github.com/zmap/rc2|v0.0.0-20190804163417-abaa70531248|间接依赖|go|
|nopt|4.0.1|间接依赖|npm|
|github.com/google/uuid|v1.3.1|间接依赖|go|
|github.com/antchfx/xmlquery|v1.3.17|直接依赖|go|
|github.com/asaskevich/govalidator|v0.0.0-20230301143203-a9d515a09cc2|直接依赖|go|
|iconv-lite|0.4.24|间接依赖|npm|
|string_decoder|1.1.1|间接依赖|npm|
|delegates|1.0.0|间接依赖|npm|
|github.com/Qianlitp/crawlergo|v0.4.3|直接依赖|go|
|github.com/templexxx/cpufeat|v0.0.0-20180724012125-cef66df7f161|间接依赖|go|
|aproba|1.2.0|间接依赖|npm|
|github.com/mattn/go-sqlite3|v1.14.17|间接依赖|go|
|go.uber.org/ratelimit|v0.3.0|直接依赖|go|
|google.golang.org/genproto/googleapis/api|v0.0.0-20230822172742-b8732ec3820d|直接依赖|go|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|github.com/xdg-go/stringprep|v1.0.4|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/google/go-querystring|v1.1.0|间接依赖|go|
|mime-db|1.44.0|间接依赖|npm|
|github.com/mholt/archiver|v3.1.1+incompatible|间接依赖|go|
|github.com/quic-go/qpack|v0.4.0|间接依赖|go|
|util-deprecate|1.0.2|间接依赖|npm|
|github.com/minio/selfupdate|v0.6.0|间接依赖|go|
|rimraf|2.6.3|间接依赖|npm|
|github.com/google/cel-go|v0.17.6|直接依赖|go|
|github.com/tidwall/tinyqueue|v0.1.1|间接依赖|go|
|osenv|0.1.5|间接依赖|npm|
|github.com/tidwall/pretty|v1.2.1|间接依赖|go|
|extsprintf|1.4.0|间接依赖|npm|
|github.com/ulule/deepcopier|v0.0.0-20200430083143-45decc6639b6|间接依赖|go|
|github.com/google/gopacket|v1.1.19|直接依赖|go|
|github.com/shoenig/go-m1cpu|v0.1.6|间接依赖|go|
|json-schema|0.2.3|间接依赖|npm|
|github.com/fatih/color|v1.15.0|间接依赖|go|
|gopkg.in/ini.v1|v1.67.0|间接依赖|go|
|github.com/chromedp/sysutil|v1.0.0|间接依赖|go|
|github.com/cheggaaa/pb/v3|v3.1.4|间接依赖|go|
|github.com/olekukonko/tablewriter|v0.0.5|间接依赖|go|
|github.com/stretchr/testify|v1.8.4|直接依赖|go|
|golang.org/x/exp|v0.0.0-20230817173708-d852ddb80c63|间接依赖|go|
|mime-types|2.1.27|间接依赖|npm|
|github.com/pelletier/go-toml/v2|v2.1.0|间接依赖|go|
|github.com/sijms/go-ora/v2|v2.7.17|直接依赖|go|
|github.com/txthinking/socks5|v0.0.0-20230325130024-4230056ae301|直接依赖|go|
|github.com/pion/transport/v2|v2.2.1|间接依赖|go|
|performance-now|2.1.0|间接依赖|npm|
|github.com/hktalent/PipelineHttp|v0.0.0-20230815034820-7ba060930550|直接依赖|go|
|github.com/dimchansky/utfbom|v1.1.1|间接依赖|go|
|github.com/stacktitan/smb|v0.0.0-20190531122847-da9a425dceb8|直接依赖|go|
|process-nextick-args|2.0.0|间接依赖|npm|
|github.com/boy-hack/ksubdomain|v1.9.5|直接依赖|go|
|github.com/AndreasBriese/bbloom|v0.0.0-20190825152654-46b345b51c96|间接依赖|go|
|deep-extend|0.6.0|间接依赖|npm|
|github.com/sirupsen/logrus|v1.9.0|间接依赖|go|
|verror|1.10.0|间接依赖|npm|
|request|2.88.2|直接依赖|npm|
|github.com/pion/sdp/v3|v3.0.6|间接依赖|go|
|gopkg.in/irc.v3|v3.1.4|直接依赖|go|
|os-homedir|1.0.2|间接依赖|npm|
|github.com/remeh/sizedwaitgroup|v1.0.0|直接依赖|go|
|github.com/jcmturner/rpc/v2|v2.0.3|间接依赖|go|
|wide-align|1.1.3|间接依赖|npm|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|github.com/projectdiscovery/fastdialer|v0.0.37|直接依赖|go|
|github.com/muesli/reflow|v0.3.0|间接依赖|go|
|github.com/logrusorgru/aurora|v2.0.3+incompatible|直接依赖|go|
|github.com/mfonda/simhash|v0.0.0-20151007195837-79f94a1100d6|直接依赖|go|
|github.com/lucasb-eyer/go-colorful|v1.2.0|间接依赖|go|
|forever-agent|0.6.1|间接依赖|npm|
|gorm.io/driver/sqlite|v1.5.3|直接依赖|go|
|asn1|0.2.4|间接依赖|npm|
|golang.org/x/text|v0.12.0|直接依赖|go|
|github.com/ammario/ipisp/v2|v2.0.0|直接依赖|go|
|strip-ansi|3.0.1|间接依赖|npm|
|github.com/emersion/go-textwrapper|v0.0.0-20200911093747-65d896831594|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/saintfish/chardet|v0.0.0-20230101081208-5e3ef4b5456d|间接依赖|go|
|qs|6.5.2|间接依赖|npm|
|github.com/icodeface/tls|v0.0.0-20190904083142-17aec93c60e5|直接依赖|go|
|github.com/jcmturner/gokrb5/v8|v8.4.4|间接依赖|go|
|jsbn|0.1.1|间接依赖|npm|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|github.com/miekg/dns|v1.1.55|间接依赖|go|
|github.com/VividCortex/ewma|v1.2.0|间接依赖|go|
|object-assign|4.1.1|间接依赖|npm|
|github.com/onsi/ginkgo/v2|v2.12.0|间接依赖|go|
|github.com/golang-sql/civil|v0.0.0-20220223132316-b832511892a9|间接依赖|go|
|mkdirp|0.5.1|间接依赖|npm|
|npm-packlist|1.4.1|间接依赖|npm|
|extend|3.0.2|间接依赖|npm|
|github.com/hashicorp/errwrap|v1.1.0|间接依赖|go|
|ignore-walk|3.0.1|间接依赖|npm|
|github.com/projectdiscovery/utils|v0.0.52|间接依赖|go|
|github.com/golang/glog|v1.1.2|间接依赖|go|
|github.com/antchfx/htmlquery|v1.3.0|直接依赖|go|
|github.com/projectdiscovery/cdncheck|v1.0.9|直接依赖|go|
|github.com/golang/mock|v1.6.0|间接依赖|go|
|wrappy|1.0.2|间接依赖|npm|
|github.com/chromedp/cdproto|v0.0.0-20230802225258-3cf4e6d46a89|直接依赖|go|
|uuid|3.4.0|间接依赖|npm|
|/usr/lib/libiconv.2.dylib||间接依赖||
|github.com/lcvvvv/gonmap|v1.2.1|直接依赖|go|
|dashdash|1.14.1|间接依赖|npm|
|combined-stream|1.0.8|间接依赖|npm|
|github.com/projectdiscovery/stringsutil|v0.0.2|直接依赖|go|
|github.com/gaukas/godicttls|v0.0.4|间接依赖|go|
|github.com/microcosm-cc/bluemonday|v1.0.25|直接依赖|go|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|github.com/pion/datachannel|v1.5.5|间接依赖|go|
|github.com/tjfoc/gmsm|v1.4.1|间接依赖|go|
|go.opentelemetry.io/otel|v1.14.0|间接依赖|go|
|github.com/go-routeros/routeros|v0.0.0-20210123142807-2a44d57c6730|直接依赖|go|
|github.com/projectdiscovery/blackrock|v0.0.1|直接依赖|go|
|github.com/jinzhu/now|v1.1.5|间接依赖|go|
|github.com/Mzack9999/go-http-digest-auth-client|v0.6.1-0.20220414142836-eb8883508809|间接依赖|go|
|gopkg.in/djherbis/times.v1|v1.3.0|间接依赖|go|
|github.com/power-devops/perfstat|v0.0.0-20221212215047-62379fc7944b|间接依赖|go|
|github.com/tidwall/rtred|v0.1.2|间接依赖|go|
|golang.org/x/sync|v0.3.0|间接依赖|go|
|minizlib|1.2.1|间接依赖|npm|
|har-schema|2.0.0|间接依赖|npm|
|/System/Library/Frameworks/Security.framework/Versions/A/Security||间接依赖||
|github.com/quic-go/quic-go|v0.38.1|间接依赖|go|
|github.com/ChrisTrenkamp/goxpath|v0.0.0-20210404020558-97928f7e12b6|间接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230822172742-b8732ec3820d|间接依赖|go|
|go.opentelemetry.io/otel/trace|v1.14.0|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)