# IceWhaleTech/CasaOS安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699484601067290624.svg)](https://www.murphysec.com/console/report/1694775371273953280/1699484601067290624)

仓库描述：CasaOS - A simple, easy-to-use, elegant open-source Personal Cloud system.

仓库地址：[https://github.com/IceWhaleTech/CasaOS](https://github.com/IceWhaleTech/CasaOS)

| star：14618 | watch：119 | fork：867 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-05 20:48:42 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-07 02:08:13 | 组件总数：129 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|go.uuid 不安全的随机性漏洞|使用具有密码学弱点缺陷的PRNG|[MPS-2021-7854](https://www.oscs1024.com/hd/MPS-2021-7854)|CVE-2021-3538|严重|
|Gin 安全漏洞|下载代码缺少完整性检查|[MPS-2023-9711](https://www.oscs1024.com/hd/MPS-2023-9711)|CVE-2023-29401|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/satori/go.uuid|v1.2.0||直接依赖|建议修复|C:1|H:0|M:0|L:0|
|github.com/gin-gonic/gin|v1.9.0|1.9.1|直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|23|Low|
|BSD-2-Clause|5|Low|
|MIT|68|Low|
|BSD-3-Clause|37|Low|
|ISC|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/chenzhuoyu/base64x|v0.0.0-20221115062448-fe3a3abad311|间接依赖|go|
|github.com/gorilla/websocket|v1.5.0|直接依赖|go|
|github.com/jinzhu/now|v1.1.5|间接依赖|go|
|github.com/golang/geo|v0.0.0-20210211234256-740aa86cb551|间接依赖|go|
|golang.org/x/exp|v0.0.0-20220303212507-bbda1eaf7a17|间接依赖|go|
|golang.org/x/arch|v0.3.0|间接依赖|go|
|github.com/dsoprea/go-utility/v2|v2.0.0-20221003172846-a3e1774ef349|间接依赖|go|
|modernc.org/memory|v1.5.0|间接依赖|go|
|github.com/power-devops/perfstat|v0.0.0-20221212215047-62379fc7944b|间接依赖|go|
|github.com/invopop/yaml|v0.2.0|间接依赖|go|
|github.com/gomodule/redigo|v1.8.9|直接依赖|go|
|github.com/samber/lo|v1.38.1|直接依赖|go|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|github.com/go-errors/errors|v1.4.2|间接依赖|go|
|github.com/klauspost/cpuid/v2|v2.2.4|间接依赖|go|
|github.com/coreos/go-systemd|v0.0.0-20191104093116-d3cd4ed1dbcf|直接依赖|go|
|google.golang.org/protobuf|v1.30.0|间接依赖|go|
|github.com/google/uuid|v1.3.0|间接依赖|go|
|github.com/valyala/fasttemplate|v1.2.2|间接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.6|间接依赖|go|
|github.com/gin-contrib/sse|v0.1.0|间接依赖|go|
|github.com/yusufpapurcu/wmi|v1.2.2|间接依赖|go|
|github.com/mohae/deepcopy|v0.0.0-20170929034955-c48cc78d4826|间接依赖|go|
|github.com/go-ole/go-ole|v1.2.6|间接依赖|go|
|github.com/go-resty/resty/v2|v2.7.0|直接依赖|go|
|github.com/ugorji/go/codec|v1.2.11|间接依赖|go|
|github.com/lufia/plan9stats|v0.0.0-20230110061619-bbe2e5e100de|间接依赖|go|
|github.com/google/go-querystring|v1.1.0|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/go-playground/universal-translator|v0.18.1|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/bytedance/sonic|v1.8.5|间接依赖|go|
|github.com/gorilla/mux|v1.8.0|间接依赖|go|
|github.com/go-ini/ini|v1.67.0|直接依赖|go|
|github.com/goccy/go-json|v0.10.2|间接依赖|go|
|github.com/dsoprea/go-exif/v3|v3.0.0-20221012082141-d21ac8e2de85|直接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|github.com/golang-jwt/jwt/v4|v4.5.0|间接依赖|go|
|github.com/geoffgarside/ber|v1.1.0|间接依赖|go|
|modernc.org/libc|v1.22.3|间接依赖|go|
|github.com/hirochachacha/go-smb2|v1.1.0|直接依赖|go|
|github.com/tidwall/pretty|v1.2.1|间接依赖|go|
|github.com/coreos/go-systemd/v22|v22.5.0|间接依赖|go|
|github.com/satori/go.uuid|v1.2.0|直接依赖|go|
|github.com/gin-gonic/gin|v1.9.0|直接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/shirou/gopsutil/v3|v3.23.2|直接依赖|go|
|github.com/mileusna/useragent|v1.2.1|直接依赖|go|
|github.com/leodido/go-urn|v1.2.3|间接依赖|go|
|github.com/klauspost/compress|v1.16.5|间接依赖|go|
|go.uber.org/goleak|v1.2.1|直接依赖|go|
|github.com/googollee/go-socket.io|v1.7.0|直接依赖|go|
|github.com/gin-contrib/gzip|v0.0.6|直接依赖|go|
|github.com/deepmap/oapi-codegen|v1.12.4|直接依赖|go|
|github.com/golang/mock|v1.6.0|直接依赖|go|
|github.com/golang-jwt/jwt|v3.2.2+incompatible|间接依赖|go|
|github.com/tidwall/gjson|v1.14.4|直接依赖|go|
|github.com/google/go-github/v36|v36.0.0|直接依赖|go|
|github.com/go-playground/validator/v10|v10.12.0|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|golang.org/x/image|v0.6.0|间接依赖|go|
|golang.org/x/text|v0.9.0|间接依赖|go|
|github.com/perimeterx/marshmallow|v1.1.4|间接依赖|go|
|github.com/twitchyliquid64/golang-asm|v0.15.1|间接依赖|go|
|github.com/benbjohnson/clock|v1.3.0|间接依赖|go|
|go.uber.org/zap|v1.24.0|直接依赖|go|
|github.com/moby/sys/mount|v0.3.3|直接依赖|go|
|golang.org/x/sync|v0.1.0|直接依赖|go|
|github.com/go-openapi/swag|v0.22.3|间接依赖|go|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|github.com/sirupsen/logrus|v1.9.0|直接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/golang/snappy|v0.0.4|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|github.com/kr/pretty|v0.3.1|间接依赖|go|
|github.com/nwaples/rardecode|v1.1.3|间接依赖|go|
|github.com/patrickmn/go-cache|v2.1.0+incompatible|直接依赖|go|
|golang.org/x/time|v0.3.0|间接依赖|go|
|github.com/deckarep/golang-set/v2|v2.3.0|直接依赖|go|
|github.com/json-iterator/go|v1.1.12|直接依赖|go|
|github.com/mattn/go-isatty|v0.0.18|间接依赖|go|
|github.com/stretchr/testify|v1.8.2|直接依赖|go|
|modernc.org/mathutil|v1.5.0|间接依赖|go|
|github.com/remyoudompheng/bigfft|v0.0.0-20230129092748-24d4a6f8daec|间接依赖|go|
|github.com/godbus/dbus/v5|v5.1.0|间接依赖|go|
|github.com/dustin/go-humanize|v1.0.1|间接依赖|go|
|github.com/robfig/cron/v3|v3.0.1|直接依赖|go|
|modernc.org/sqlite|v1.21.0|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|golang.org/x/crypto|v0.8.0|直接依赖|go|
|github.com/maruel/natural|v1.1.0|直接依赖|go|
|github.com/tklauser/numcpus|v0.6.0|间接依赖|go|
|github.com/labstack/echo/v4|v4.10.2|直接依赖|go|
|github.com/dsoprea/go-logging|v0.0.0-20200710184922-b02d349568dd|间接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|github.com/gofrs/uuid|v4.4.0+incompatible|间接依赖|go|
|github.com/glebarez/sqlite|v1.7.0|直接依赖|go|
|github.com/Curtis-Milo/nat-type-identifier-go|v0.0.0-20220215191915-18d42168c63d|直接依赖|go|
|github.com/mholt/archiver/v3|v3.5.1|直接依赖|go|
|github.com/andybalholm/brotli|v1.0.5|间接依赖|go|
|github.com/tidwall/match|v1.1.1|间接依赖|go|
|gotest.tools|v2.2.0+incompatible|直接依赖|go|
|github.com/tklauser/go-sysconf|v0.3.11|间接依赖|go|
|github.com/IceWhaleTech/CasaOS-Common|v0.4.7-alpha4|直接依赖|go|
|golang.org/x/net|v0.9.0|间接依赖|go|
|github.com/moby/sys/mountinfo|v0.6.2|直接依赖|go|
|go.uber.org/atomic|v1.10.0|间接依赖|go|
|gorm.io/gorm|v1.24.6|直接依赖|go|
|github.com/pelletier/go-toml/v2|v2.0.7|间接依赖|go|
|go.uber.org/multierr|v1.11.0|间接依赖|go|
|github.com/xi2/xz|v0.0.0-20171230120015-48954b6210f8|间接依赖|go|
|github.com/klauspost/pgzip|v1.2.5|间接依赖|go|
|github.com/go-playground/locales|v0.14.1|间接依赖|go|
|github.com/glebarez/go-sqlite|v1.21.0|间接依赖|go|
|github.com/disintegration/imaging|v1.6.2|直接依赖|go|
|github.com/valyala/bytebufferpool|v1.0.0|间接依赖|go|
|github.com/labstack/gommon|v0.4.0|间接依赖|go|
|github.com/apapsch/go-jsonmerge/v2|v2.0.0|间接依赖|go|
|golang.org/x/sys|v0.7.0|直接依赖|go|
|github.com/ulikunitz/xz|v0.5.11|间接依赖|go|
|github.com/pierrec/lz4/v4|v4.1.17|间接依赖|go|
|github.com/h2non/filetype|v1.1.3|直接依赖|go|
|github.com/google/go-cmp|v0.5.9|间接依赖|go|
|gopkg.in/natefinch/lumberjack.v2|v2.2.1|间接依赖|go|
|github.com/getkin/kin-openapi|v0.115.0|直接依赖|go|
|github.com/dsnet/compress|v0.0.2-0.20210315054119-f66993602bf5|间接依赖|go|
|golang.org/x/oauth2|v0.6.0|直接依赖|go|
|github.com/jinzhu/inflection|v1.0.0|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)