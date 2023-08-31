# answerdev/answer安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1697311338065125376.svg)](https://www.murphysec.com/console/report/1692962800975892480/1697311338065125376)

仓库描述：A Q&A platform software for teams at any scales. Whether it’s a community forum, help center, or knowledge management platform, you can always count on Answer.

仓库地址：[https://github.com/answerdev/answer](https://github.com/answerdev/answer)

| star：7540 | watch：64 | fork：488 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-31 16:17:13 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-01 02:12:34 | 组件总数：144 | 漏洞总数：6 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58311](https://www.oscs1024.com/hd/MPS-2022-58311)|CVE-2022-41727|中危|
|runc 安全漏洞|使用不正确的解析名称或索引|[MPS-2023-6887](https://www.oscs1024.com/hd/MPS-2023-6887)|CVE-2023-27561|高危|
|runc <1.1.5 AppArmor限制绕过漏洞|访问控制不当|[MPS-2023-8507](https://www.oscs1024.com/hd/MPS-2023-8507)|CVE-2023-28642|高危|
|Moby 安全漏洞||[MPS-2023-8823](https://www.oscs1024.com/hd/MPS-2023-8823)|CVE-2023-28840|高危|
|Moby 安全漏洞||[MPS-2023-8824](https://www.oscs1024.com/hd/MPS-2023-8824)|CVE-2023-28841|中危|
|Moby 安全漏洞||[MPS-2023-8826](https://www.oscs1024.com/hd/MPS-2023-8826)|CVE-2023-28842|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/docker/docker|v20.10.7+incompatible|23.0.3|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|golang.org/x/image|v0.1.0|0.5.0|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|github.com/opencontainers/runc|v1.1.2|1.1.5|间接依赖|建议修复|C:0|H:2|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|32|Low|
|MIT|68|Low|
|BSD-3-Clause|33|Low|
|GPL-3.0|1|Medium|
|GPL-3.0-or-later|1|Low|
|BSD-2-Clause|4|Low|
|ISC|1|Low|
|MPL-2.0|2|Low|
|CC-BY-SA-4.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/ory/dockertest/v3|v3.9.1|直接依赖|go|
|github.com/pelletier/go-toml/v2|v2.0.8|间接依赖|go|
|modernc.org/memory|v1.5.0|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.19|间接依赖|go|
|github.com/xeipuuv/gojsonschema|v1.2.0|间接依赖|go|
|github.com/swaggo/swag|v1.16.1|直接依赖|go|
|github.com/segmentfault/pacman/contrib/server/http|v0.0.0-20221018072427-a15dd1434e05|直接依赖|go|
|github.com/segmentfault/pacman/contrib/log/zap|v0.0.0-20221018072427-a15dd1434e05|直接依赖|go|
|github.com/gin-contrib/sse|v0.1.0|间接依赖|go|
|github.com/opencontainers/runc|v1.1.2|间接依赖|go|
|github.com/anargu/gin-brotli|v0.0.0-20220116052358-12bf532d5267|直接依赖|go|
|github.com/jinzhu/now|v1.1.5|直接依赖|go|
|github.com/bytedance/sonic|v1.9.1|间接依赖|go|
|github.com/stretchr/testify|v1.8.4|直接依赖|go|
|github.com/dsoprea/go-logging|v0.0.0-20190624164917-c4f10aab7696|间接依赖|go|
|github.com/segmentfault/pacman/contrib/conf/viper|v0.0.0-20221018072427-a15dd1434e05|直接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|lukechampine.com/uint128|v1.2.0|间接依赖|go|
|github.com/magiconair/properties|v1.8.6|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.0.1|间接依赖|go|
|github.com/twitchyliquid64/golang-asm|v0.15.1|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|直接依赖|go|
|xorm.io/xorm|v1.3.2|直接依赖|go|
|golang.org/x/net|v0.12.0|直接依赖|go|
|github.com/gorilla/css|v1.0.0|间接依赖|go|
|github.com/go-sql-driver/mysql|v1.6.0|直接依赖|go|
|golang.org/x/mod|v0.12.0|间接依赖|go|
|github.com/lestrrat-go/strftime|v1.0.6|间接依赖|go|
|github.com/kballard/go-shellquote|v0.0.0-20180428030007-95032a82bc51|间接依赖|go|
|github.com/disintegration/imaging|v1.6.2|直接依赖|go|
|golang.org/x/tools|v0.11.0|间接依赖|go|
|gopkg.in/gomail.v2|v2.0.0-20160411212932-81ebce5c23df|直接依赖|go|
|github.com/LinkinStars/go-i18n/v2|v2.2.2|间接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0|间接依赖|go|
|github.com/subosito/gotenv|v1.4.1|间接依赖|go|
|github.com/segmentfault/pacman|v1.0.5-0.20230822083413-c0075a2d401f|直接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|modernc.org/ccgo/v3|v3.16.13|间接依赖|go|
|go.uber.org/atomic|v1.10.0|间接依赖|go|
|github.com/spf13/cast|v1.5.0|间接依赖|go|
|github.com/spf13/jwalterweatherman|v1.1.0|间接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.0|间接依赖|go|
|xorm.io/builder|v0.3.12|直接依赖|go|
|github.com/docker/cli|v20.10.14+incompatible|间接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.2|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/gabriel-vasile/mimetype|v1.4.2|间接依赖|go|
|github.com/xeipuuv/gojsonreference|v0.0.0-20180127040603-bd5ef7bd5415|间接依赖|go|
|github.com/KyleBanks/depth|v1.2.1|间接依赖|go|
|github.com/dsoprea/go-jpeg-image-structure|v0.0.0-20190422055009-d6f9ba25cf48|间接依赖|go|
|github.com/jinzhu/copier|v0.3.5|直接依赖|go|
|github.com/scottleedavis/go-exif-remove|v0.0.0-20230314195146-7e059d593405|直接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/docker/docker|v20.10.7+incompatible|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/cenkalti/backoff/v4|v4.1.3|间接依赖|go|
|github.com/ugorji/go/codec|v1.2.11|间接依赖|go|
|golang.org/x/text|v0.11.0|间接依赖|go|
|github.com/google/uuid|v1.3.0|直接依赖|go|
|golang.org/x/arch|v0.3.0|间接依赖|go|
|github.com/Machiel/slugify|v1.0.1|直接依赖|go|
|github.com/go-errors/errors|v1.0.1|间接依赖|go|
|github.com/patrickmn/go-cache|v2.1.0+incompatible|间接依赖|go|
|github.com/spf13/viper|v1.13.0|间接依赖|go|
|github.com/dsoprea/go-exif|v0.0.0-20190901173045-3ce78807c90f|间接依赖|go|
|github.com/golang/mock|v1.6.0|直接依赖|go|
|github.com/pelletier/go-toml|v1.9.5|间接依赖|go|
|github.com/mojocn/base64Captcha|v1.3.5|直接依赖|go|
|github.com/robfig/cron/v3|v3.0.1|直接依赖|go|
|github.com/go-playground/validator/v10|v10.14.0|直接依赖|go|
|github.com/tidwall/match|v1.1.1|间接依赖|go|
|github.com/xeipuuv/gojsonpointer|v0.0.0-20180127040702-4e3ac2762d5f|间接依赖|go|
|gopkg.in/alexcesaro/quotedprintable.v3|v3.0.0-20150716171945-2caba252f4dc|间接依赖|go|
|github.com/sirupsen/logrus|v1.8.1|间接依赖|go|
|modernc.org/token|v1.0.1|间接依赖|go|
|github.com/klauspost/cpuid/v2|v2.2.4|间接依赖|go|
|modernc.org/opt|v0.1.3|间接依赖|go|
|github.com/grokify/html-strip-tags-go|v0.0.1|直接依赖|go|
|github.com/golang/geo|v0.0.0-20190812012225-f41920e961ce|间接依赖|go|
|github.com/leodido/go-urn|v1.2.4|间接依赖|go|
|google.golang.org/protobuf|v1.30.0|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|github.com/dsoprea/go-png-image-structure|v0.0.0-20190624104353-c9b28dcdc5c8|间接依赖|go|
|github.com/go-openapi/jsonpointer|v0.20.0|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|github.com/syndtr/goleveldb|v1.0.0|间接依赖|go|
|github.com/asaskevich/govalidator|v0.0.0-20210307081110-f21760c49a8d|直接依赖|go|
|github.com/go-openapi/spec|v0.20.9|间接依赖|go|
|github.com/google/shlex|v0.0.0-20191202100458-e7afc7fbc510|间接依赖|go|
|github.com/golang/freetype|v0.0.0-20170609003504-e2365dfdc4a0|间接依赖|go|
|modernc.org/cc/v3|v3.40.0|间接依赖|go|
|github.com/segmentfault/pacman/contrib/cache/memory|v0.0.0-20230822083413-c0075a2d401f|直接依赖|go|
|github.com/Nvveen/Gotty|v0.0.0-20120604004816-cd527374f1e5|间接依赖|go|
|github.com/imdario/mergo|v0.3.12|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|间接依赖|go|
|github.com/lib/pq|v1.10.7|直接依赖|go|
|github.com/go-playground/locales|v0.14.1|直接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|github.com/Masterminds/semver/v3|v3.1.1|直接依赖|go|
|github.com/Microsoft/go-winio|v0.5.2|间接依赖|go|
|github.com/containerd/continuity|v0.3.0|间接依赖|go|
|github.com/segmentfault/pacman/contrib/i18n|v0.0.0-20230516093754-b76aef1c1150|直接依赖|go|
|github.com/bwmarrin/snowflake|v0.3.0|直接依赖|go|
|go.uber.org/multierr|v1.8.0|间接依赖|go|
|github.com/Chain-Zhang/pinyin|v0.1.3|直接依赖|go|
|github.com/swaggo/gin-swagger|v1.5.3|直接依赖|go|
|modernc.org/mathutil|v1.5.0|间接依赖|go|
|github.com/Azure/go-ansiterm|v0.0.0-20170929234023-d6e3b3328b78|间接依赖|go|
|github.com/aymerick/douceur|v0.2.0|间接依赖|go|
|github.com/spf13/cobra|v1.6.1|直接依赖|go|
|github.com/docker/go-connections|v0.4.0|间接依赖|go|
|github.com/opencontainers/image-spec|v1.0.2|间接依赖|go|
|github.com/docker/go-units|v0.4.0|间接依赖|go|
|github.com/dustin/go-humanize|v1.0.1|间接依赖|go|
|golang.org/x/sys|v0.10.0|间接依赖|go|
|github.com/remyoudompheng/bigfft|v0.0.0-20230129092748-24d4a6f8daec|间接依赖|go|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|modernc.org/sqlite|v1.24.0|直接依赖|go|
|github.com/golang/snappy|v0.0.4|间接依赖|go|
|golang.org/x/image|v0.1.0|间接依赖|go|
|github.com/microcosm-cc/bluemonday|v1.0.21|直接依赖|go|
|go.uber.org/zap|v1.23.0|间接依赖|go|
|modernc.org/libc|v1.22.5|间接依赖|go|
|github.com/chenzhuoyu/base64x|v0.0.0-20221115062448-fe3a3abad311|间接依赖|go|
|github.com/moby/term|v0.0.0-20201216013528-df9cb8a40635|间接依赖|go|
|github.com/andybalholm/brotli|v1.0.4|间接依赖|go|
|golang.org/x/crypto|v0.11.0|直接依赖|go|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|github.com/go-playground/universal-translator|v0.18.1|直接依赖|go|
|github.com/google/wire|v0.5.0|直接依赖|go|
|github.com/lestrrat-go/file-rotatelogs|v2.4.0+incompatible|间接依赖|go|
|github.com/yuin/goldmark|v1.4.13|直接依赖|go|
|github.com/tidwall/gjson|v1.14.4|直接依赖|go|
|modernc.org/strutil|v1.1.3|间接依赖|go|
|github.com/spf13/afero|v1.9.2|间接依赖|go|
|github.com/goccy/go-json|v0.10.2|直接依赖|go|
|github.com/gin-gonic/gin|v1.9.1|直接依赖|go|
|sigs.k8s.io/yaml|v1.3.0|间接依赖|go|
|github.com/go-openapi/swag|v0.22.4|间接依赖|go|
|gopkg.in/ini.v1|v1.67.0|间接依赖|go|
|github.com/tidwall/pretty|v1.2.0|间接依赖|go|
|github.com/swaggo/files|v1.0.0|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)