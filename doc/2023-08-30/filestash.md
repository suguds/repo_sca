# mickael-kerjean/filestash安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696593272633122816.svg)](https://www.murphysec.com/console/report/1696593272591179776/1696593272633122816)

仓库描述：🦄 A modern web client for SFTP, S3, FTP, WebDAV, Git, Minio, LDAP, CalDAV, CardDAV, Mysql, Backblaze, ...

仓库地址：[https://github.com/mickael-kerjean/filestash](https://github.com/mickael-kerjean/filestash)

| star：8311 | watch：106 | fork：599 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-24 12:56:33 | 许可证：AGPL-3.0 |
| 最近检测时间：2023-08-30 02:40:26 | 组件总数：123 | 漏洞总数：18 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|libjpeg-turbo 安全漏洞|空指针取消引用|[MPS-2017-11385](https://www.oscs1024.com/hd/MPS-2017-11385)|CVE-2017-15232|中危|
|libjpeg-turbo 缓冲区错误漏洞|越界读取|[MPS-2018-15262](https://www.oscs1024.com/hd/MPS-2018-15262)|CVE-2018-19664|中危|
|libjpeg-turbo 缓冲区错误漏洞||[MPS-2018-16156](https://www.oscs1024.com/hd/MPS-2018-16156)|CVE-2018-20330|高危|
|libjpeg 安全漏洞|过度迭代|[MPS-2018-7108](https://www.oscs1024.com/hd/MPS-2018-7108)|CVE-2018-11813|高危|
|libjpeg-turbo 安全漏洞|除零错误|[MPS-2018-8089](https://www.oscs1024.com/hd/MPS-2018-8089)|CVE-2018-1152|中危|
|libpng 数字错误漏洞||[MPS-2018-9315](https://www.oscs1024.com/hd/MPS-2018-9315)|CVE-2018-13785|中危|
|libpng 安全漏洞|输入验证不恰当|[MPS-2018-9648](https://www.oscs1024.com/hd/MPS-2018-9648)|CVE-2018-14048|中危|
|libpng 资源管理错误漏洞|UAF|[MPS-2019-1241](https://www.oscs1024.com/hd/MPS-2019-1241)|CVE-2019-7317|中危|
|libjpeg-turbo和MozJPEG 缓冲区错误漏洞|越界读取|[MPS-2019-2308](https://www.oscs1024.com/hd/MPS-2019-2308)|CVE-2018-14498|中危|
|libpng 缓冲区错误漏洞|越界写入|[MPS-2019-7748](https://www.oscs1024.com/hd/MPS-2019-7748)|CVE-2018-14550|高危|
|libjpeg 资源管理错误漏洞|不加限制或调节的资源分配|[MPS-2019-8198](https://www.oscs1024.com/hd/MPS-2019-8198)|CVE-2019-13960|中危|
|libjpeg-turbo 安全漏洞|空指针取消引用|[MPS-2020-35856](https://www.oscs1024.com/hd/MPS-2020-35856)|CVE-2020-35538|中危|
|libjpeg-turbo 缓冲区错误漏洞|越界读取|[MPS-2020-8147](https://www.oscs1024.com/hd/MPS-2020-8147)|CVE-2020-13790|高危|
|DRC libjpeg-turbo 数字错误漏洞|除零错误|[MPS-2021-2940](https://www.oscs1024.com/hd/MPS-2021-2940)|CVE-2021-20205|中危|
|Libjpeg-turbo 缓冲区错误漏洞|越界写入|[MPS-2021-7701](https://www.oscs1024.com/hd/MPS-2021-7701)|CVE-2020-17541|高危|
|libjpeg 缓冲区错误漏洞|越界写入|[MPS-2022-19241](https://www.oscs1024.com/hd/MPS-2022-19241)|CVE-2021-46822|中危|
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58311](https://www.oscs1024.com/hd/MPS-2022-58311)|CVE-2022-41727|中危|
|libjpeg-turbo 缓冲区错误漏洞|越界写入|[MPS-ntew-f62l](https://www.oscs1024.com/hd/MPS-ntew-f62l)|CVE-2023-2804|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|libpng|1.6.37||间接依赖|建议修复|C:0|H:1|M:2|L:0|
|libpng|1.6.36|1.6.37|间接依赖|建议修复|C:0|H:1|M:3|L:0|
|golang.org/x/image|v0.0.0-20211028202545-6944b10bf410|0.5.0|直接依赖|建议修复|C:0|H:0|M:1|L:0|
|libjpeg-turbo|1.5.2|3.0.0|间接依赖|建议修复|C:0|H:4|M:9|L:0|
|libjpeg-turbo|2.1.2|3.0.0|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|libjpeg-turbo|2.0.6|3.0.0|间接依赖|可选修复|C:0|H:0|M:4|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|51|Low|
|BSD-3-Clause|37|Low|
|Apache-2.0|18|Low|
|ISC|5|Low|
|BSD-2-Clause|12|Low|
|MPL-2.0|3|Low|
|Zlib|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/Azure/azure-sdk-for-go/sdk/azcore|v1.6.0|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/jonboulle/clockwork|v0.2.2|间接依赖|go|
|github.com/kr/fs|v0.1.0|间接依赖|go|
|gopkg.in/asn1-ber.v1|v1.0.0-20181015200546-f715ec2f112d|间接依赖|go|
|gopkg.in/ldap.v2|v2.5.1|直接依赖|go|
|modernc.org/token|v1.0.1|间接依赖|go|
|github.com/kylelemons/godebug|v1.1.0|间接依赖|go|
|github.com/duosecurity/duo_universal_golang|v1.0.3|直接依赖|go|
|github.com/tidwall/match|v1.1.1|间接依赖|go|
|gopkg.in/src-d/go-billy.v4|v4.3.2|间接依赖|go|
|github.com/mattermost/xml-roundtrip-validator|v0.1.0|间接依赖|go|
|google.golang.org/appengine|v1.5.0|间接依赖|go|
|github.com/aws/aws-sdk-go|v1.40.41|直接依赖|go|
|github.com/rasky/go-xdr|v0.0.0-20170124162913-1a41d1a06c93|间接依赖|go|
|github.com/AzureAD/microsoft-authentication-library-for-go|v1.0.0|间接依赖|go|
|github.com/creack/pty|v1.1.18|直接依赖|go|
|github.com/golang/protobuf|v1.3.1|间接依赖|go|
|github.com/tidwall/pretty|v1.2.0|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/golang-jwt/jwt/v4|v4.5.0|间接依赖|go|
|modernc.org/memory|v1.4.0|间接依赖|go|
|google.golang.org/api|v0.15.0|直接依赖|go|
|github.com/suyashkumar/dicom|v1.0.5|直接依赖|go|
|libjpeg-turbo|1.5.2|间接依赖||
|github.com/cretz/bine|v0.1.0|直接依赖|go|
|modernc.org/strutil|v1.1.3|间接依赖|go|
|github.com/vmware/go-nfs-client|v0.0.0-20190605212624-d43b92724c1b|直接依赖|go|
|github.com/jbenet/go-context|v0.0.0-20150711004518-d14ea06fba99|间接依赖|go|
|github.com/lestrrat-go/option|v1.0.0|间接依赖|go|
|github.com/sergi/go-diff|v1.0.0|间接依赖|go|
|github.com/mitchellh/hashstructure|v1.0.0|直接依赖|go|
|github.com/lestrrat-go/pdebug/v3|v3.0.1|间接依赖|go|
|github.com/spacemonkeygo/monkit/v3|v3.0.17|间接依赖|go|
|golang.org/x/crypto|v0.7.0|直接依赖|go|
|github.com/mickael-kerjean/saml|v0.0.0-20221221152539-19783715740c|直接依赖|go|
|github.com/lestrrat-go/jwx|v1.2.4|间接依赖|go|
|gopkg.in/warnings.v0|v0.1.2|间接依赖|go|
|github.com/tidwall/sjson|v1.0.4|直接依赖|go|
|go.opencensus.io|v0.21.0|间接依赖|go|
|github.com/src-d/gcfg|v1.4.0|间接依赖|go|
|github.com/gorilla/mux|v1.7.3|直接依赖|go|
|modernc.org/mathutil|v1.5.0|间接依赖|go|
|modernc.org/cc/v3|v3.38.1|间接依赖|go|
|github.com/mattn/go-sqlite3|v2.0.2+incompatible|直接依赖|go|
|github.com/geoffgarside/ber|v1.1.0|间接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|间接依赖|go|
|github.com/nfnt/resize|v0.0.0-20180221191011-83c6a9932646|间接依赖|go|
|github.com/emirpasic/gods|v1.12.0|间接依赖|go|
|github.com/prasad83/goftp|v0.0.0-20210325080443-f57aaed46a32|直接依赖|go|
|github.com/googleapis/gax-go/v2|v2.0.5|间接依赖|go|
|modernc.org/libc|v1.19.0|间接依赖|go|
|gopkg.in/src-d/go-git.v4|v4.13.1|直接依赖|go|
|github.com/stretchr/testify|v1.7.1|直接依赖|go|
|github.com/pkg/sftp|v1.11.0|直接依赖|go|
|modernc.org/ccgo/v3|v3.16.9|间接依赖|go|
|google.golang.org/grpc|v1.20.1|间接依赖|go|
|github.com/secsy/goftp|v0.0.0-20200609142545-aa2de14babf4|间接依赖|go|
|lukechampine.com/uint128|v1.1.1|间接依赖|go|
|github.com/tredoe/osutil|v1.0.6|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/azidentity|v1.3.0|直接依赖|go|
|github.com/decred/dcrd/dcrec/secp256k1/v3|v3.0.0|间接依赖|go|
|modernc.org/sqlite|v1.19.1|直接依赖|go|
|github.com/mickael-kerjean/net|v0.0.0-20191120063050-2457c043ba06|直接依赖|go|
|github.com/mattn/go-isatty|v0.0.16|间接依赖|go|
|github.com/remyoudompheng/bigfft|v0.0.0-20200410134404-eec4a21b6bb0|间接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|golang.org/x/sys|v0.6.0|间接依赖|go|
|gopkg.in/gomail.v2|v2.0.0-20160411212932-81ebce5c23df|直接依赖|go|
|golang.org/x/time|v0.0.0-20220722155302-e5dcc9cfc0b9|直接依赖|go|
|github.com/beevik/etree|v1.1.0|间接依赖|go|
|golang.org/x/tools|v0.6.0|间接依赖|go|
|github.com/gorilla/websocket|v1.4.1|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/storage/azblob|v1.0.0|直接依赖|go|
|storj.io/common|v0.0.0-20220414110316-a5cb7172d6bf|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/internal|v1.3.0|间接依赖|go|
|github.com/lestrrat-go/iter|v1.0.1|间接依赖|go|
|libpng|1.6.37|间接依赖||
|github.com/h2non/bimg|v1.1.5|直接依赖|go|
|github.com/pkg/browser|v0.0.0-20210911075715-681adbf594b8|间接依赖|go|
|github.com/wayneashleyberry/terminal-dimensions|v1.1.0|间接依赖|go|
|libpng|1.6.36|间接依赖||
|github.com/hirochachacha/go-smb2|v1.1.0|直接依赖|go|
|libjpeg-turbo|2.1.2|间接依赖||
|modernc.org/opt|v0.1.3|间接依赖|go|
|golang.org/x/net|v0.8.0|直接依赖|go|
|github.com/patrickmn/go-cache|v2.1.0+incompatible|直接依赖|go|
|github.com/qeesung/image2ascii|v1.0.1|直接依赖|go|
|github.com/tidwall/gjson|v1.13.0|直接依赖|go|
|cloud.google.com/go|v0.38.0|间接依赖|go|
|github.com/google/uuid|v1.3.0|间接依赖|go|
|github.com/vivint/infectious|v0.0.0-20200605153912-25a574ae18a3|间接依赖|go|
|github.com/kballard/go-shellquote|v0.0.0-20180428030007-95032a82bc51|间接依赖|go|
|storj.io/drpc|v0.0.30|间接依赖|go|
|libjpeg-turbo|2.0.6|间接依赖||
|gopkg.in/ldap.v3|v3.1.0|直接依赖|go|
|gopkg.in/alexcesaro/quotedprintable.v3|v3.0.0-20150716171945-2caba252f4dc|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20190502173448-54afdca5d873|间接依赖|go|
|golang.org/x/oauth2|v0.0.0-20200107190931-bf48bf16ab8d|直接依赖|go|
|github.com/srwiley/rasterx|v0.0.0-20220730225603-2ab79fcdd4ef|直接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|直接依赖|go|
|github.com/calebcase/tmpfile|v1.0.3|间接依赖|go|
|github.com/lestrrat-go/backoff/v2|v2.0.7|间接依赖|go|
|storj.io/uplink|v1.9.0|直接依赖|go|
|golang.org/x/image|v0.0.0-20211028202545-6944b10bf410|直接依赖|go|
|github.com/goccy/go-json|v0.7.4|间接依赖|go|
|github.com/russellhaering/goxmldsig|v1.1.1|间接依赖|go|
|github.com/go-sql-driver/mysql|v1.5.0|直接依赖|go|
|github.com/lestrrat-go/httpcc|v1.0.0|间接依赖|go|
|github.com/kevinburke/ssh_config|v0.0.0-20190725054713-01f96b0aa0cd|间接依赖|go|
|golang.org/x/sync|v0.1.0|直接依赖|go|
|github.com/hashicorp/golang-lru|v0.5.1|间接依赖|go|
|golang.org/x/text|v0.8.0|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/aybabtme/rgbterm|v0.0.0-20170906152045-cc83f3b3ce59|间接依赖|go|
|github.com/srwiley/oksvg|v0.0.0-20221011165216-be6e8873101c|直接依赖|go|
|github.com/xanzy/ssh-agent|v0.2.1|间接依赖|go|
|github.com/lestrrat-go/blackmagic|v1.0.0|间接依赖|go|
|github.com/crewjam/httperr|v0.2.0|间接依赖|go|
|github.com/zeebo/errs|v1.3.0|间接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|golang.org/x/mod|v0.8.0|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)