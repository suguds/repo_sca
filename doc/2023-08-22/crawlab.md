# crawlab-team/crawlab安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1693687315733241856.svg)](https://www.murphysec.com/console/report/1693687315691298816/1693687315733241856)

仓库描述：Distributed web crawler admin platform for spiders management regardless of languages and frameworks. 分布式爬虫管理平台，支持任何语言和框架

仓库地址：[https://github.com/crawlab-team/crawlab](https://github.com/crawlab-team/crawlab)

| star：10113 | watch：208 | fork：1665 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-16 11:14:12 | 许可证：BSD-3-Clause |
| 最近检测时间：2023-08-22 02:11:48 | 组件总数：143 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|jwt-go 安全漏洞|授权检查缺失|[MPS-2020-13786](https://www.oscs1024.com/hd/MPS-2020-13786)|CVE-2020-26160|高危|
|go.uuid 不安全的随机性漏洞|使用具有密码学弱点缺陷的PRNG|[MPS-2021-7854](https://www.oscs1024.com/hd/MPS-2021-7854)|CVE-2021-3538|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/satori/go.uuid|v1.2.0||间接依赖|建议修复|C:1|H:0|M:0|L:0|
|github.com/dgrijalva/jwt-go|v3.2.0+incompatible|4.0.0-preview1|间接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|70|Low|
|BSD-3-Clause|31|Low|
|Apache-2.0|35|Low|
|BSD-2-Clause|7|Low|
|ISC|1|Low|
|MPL-2.0|3|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/olekukonko/tablewriter|v0.0.1|间接依赖|go|
|gopkg.in/alexcesaro/quotedprintable.v3|v3.0.0-20150716171945-2caba252f4dc|间接依赖|go|
|github.com/crawlab-team/crawlab-fs|v0.6.0-beta.20211101.1940.0.20221218100256-a28d12756f73|间接依赖|go|
|github.com/tklauser/go-sysconf|v0.3.9|间接依赖|go|
|github.com/jackc/chunkreader/v2|v2.0.1|间接依赖|go|
|github.com/go-stack/stack|v1.8.0|间接依赖|go|
|github.com/jackc/pgpassfile|v1.0.0|间接依赖|go|
|github.com/segmentio/fasthash|v1.0.3|间接依赖|go|
|github.com/spf13/cobra|v1.3.0|间接依赖|go|
|github.com/go-playground/validator/v10|v10.14.0|间接依赖|go|
|github.com/upper/db/v4|v4.6.0|间接依赖|go|
|github.com/xdg-go/scram|v1.0.2|间接依赖|go|
|github.com/elastic/elastic-transport-go/v8|v8.2.0|间接依赖|go|
|github.com/vanng822/css|v0.0.0-20190504095207-a21e860bcd04|间接依赖|go|
|github.com/russross/blackfriday/v2|v2.1.0|间接依赖|go|
|github.com/jbenet/go-context|v0.0.0-20150711004518-d14ea06fba99|间接依赖|go|
|github.com/aokoli/goutils|v1.0.1|间接依赖|go|
|github.com/go-git/go-billy/v5|v5.4.1|间接依赖|go|
|github.com/go-git/go-git/v5|v5.7.0|间接依赖|go|
|github.com/apex/log|v1.9.0|间接依赖|go|
|github.com/jackc/pgproto3/v2|v2.2.0|间接依赖|go|
|github.com/mitchellh/mapstructure|v1.4.3|间接依赖|go|
|github.com/Masterminds/sprig|v2.16.0+incompatible|间接依赖|go|
|github.com/spf13/viper|v1.10.0|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.5.1|间接依赖|go|
|golang.org/x/arch|v0.3.0|间接依赖|go|
|github.com/joeshaw/multierror|v0.0.0-20140124173710-69b34d4ec901|间接依赖|go|
|github.com/jackc/pgservicefile|v0.0.0-20200714003250-2b9c44734f2b|间接依赖|go|
|github.com/gorilla/css|v1.0.0|间接依赖|go|
|go.mongodb.org/mongo-driver|v1.8.0|间接依赖|go|
|github.com/segmentio/kafka-go|v0.4.39|间接依赖|go|
|github.com/golang/snappy|v0.0.3|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|github.com/elastic/go-elasticsearch/v8|v8.7.0|间接依赖|go|
|github.com/thoas/go-funk|v0.9.1|间接依赖|go|
|github.com/spf13/cast|v1.4.1|间接依赖|go|
|github.com/crawlab-team/template-parser|v0.0.4-0.20221006034646-9bb77a7ae86e|间接依赖|go|
|github.com/shirou/gopsutil|v3.21.11+incompatible|间接依赖|go|
|github.com/ugorji/go/codec|v1.2.11|间接依赖|go|
|github.com/magiconair/properties|v1.8.5|间接依赖|go|
|golang.org/x/net|v0.11.0|间接依赖|go|
|github.com/Masterminds/semver|v1.4.2|间接依赖|go|
|github.com/sergi/go-diff|v1.3.1|间接依赖|go|
|github.com/crawlab-team/go-trace|v0.1.1|间接依赖|go|
|github.com/google/uuid|v1.3.0|间接依赖|go|
|github.com/goccy/go-json|v0.10.2|间接依赖|go|
|golang.org/x/text|v0.10.0|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20211208223120-3a66f561d7aa|间接依赖|go|
|gopkg.in/ini.v1|v1.66.2|间接依赖|go|
|gopkg.in/sourcemap.v1|v1.0.5|间接依赖|go|
|github.com/skeema/knownhosts|v1.1.1|间接依赖|go|
|github.com/emirpasic/gods|v1.18.1|间接依赖|go|
|github.com/ztrue/tracerr|v0.4.0|间接依赖|go|
|github.com/go-playground/locales|v0.14.1|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/yusufpapurcu/wmi|v1.2.2|间接依赖|go|
|github.com/jackc/pgconn|v1.11.0|间接依赖|go|
|github.com/huandu/xstrings|v1.2.0|间接依赖|go|
|github.com/pierrec/lz4/v4|v4.1.15|间接依赖|go|
|github.com/crawlab-team/crawlab-core|v0.6.3-0.20230804030437-664646cf1665|直接依赖|go|
|github.com/ReneKroon/ttlcache|v1.7.0|间接依赖|go|
|gopkg.in/warnings.v0|v0.1.2|间接依赖|go|
|github.com/klauspost/cpuid/v2|v2.2.4|间接依赖|go|
|github.com/pjbgf/sha1cd|v0.3.0|间接依赖|go|
|github.com/jackc/pgx/v4|v4.15.0|间接依赖|go|
|github.com/golang-sql/civil|v0.0.0-20190719163853-cb61b32ac6fe|间接依赖|go|
|github.com/klauspost/compress|v1.15.9|间接依赖|go|
|golang.org/x/sys|v0.9.0|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/dgrijalva/jwt-go|v3.2.0+incompatible|间接依赖|go|
|go.uber.org/dig|v1.10.0|间接依赖|go|
|github.com/gabriel-vasile/mimetype|v1.4.2|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|github.com/acomagu/bufpipe|v1.0.4|间接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|github.com/spf13/afero|v1.6.0|间接依赖|go|
|github.com/cloudflare/circl|v1.3.3|间接依赖|go|
|github.com/pelletier/go-toml|v1.9.4|间接依赖|go|
|github.com/imroc/req|v0.3.0|间接依赖|go|
|github.com/spf13/jwalterweatherman|v1.1.0|间接依赖|go|
|github.com/youmark/pkcs8|v0.0.0-20181117223130-1be2e3e5546d|间接依赖|go|
|github.com/leodido/go-urn|v1.2.4|间接依赖|go|
|github.com/denisenkom/go-mssqldb|v0.11.0|间接依赖|go|
|golang.org/x/tools|v0.10.0|间接依赖|go|
|github.com/golang/protobuf|v1.5.2|间接依赖|go|
|github.com/chenzhuoyu/base64x|v0.0.0-20221115062448-fe3a3abad311|间接依赖|go|
|google.golang.org/grpc|v1.42.0|间接依赖|go|
|github.com/go-sql-driver/mysql|v1.6.0|间接依赖|go|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|github.com/jackc/pgio|v1.0.0|间接依赖|go|
|golang.org/x/crypto|v0.10.0|间接依赖|go|
|github.com/grpc-ecosystem/go-grpc-middleware|v1.0.1-0.20190118093823-f849b5445de4|间接依赖|go|
|github.com/matcornic/hermes/v2|v2.1.0|间接依赖|go|
|github.com/gin-contrib/sse|v0.1.0|间接依赖|go|
|github.com/subosito/gotenv|v1.2.0|间接依赖|go|
|github.com/satori/go.uuid|v1.2.0|间接依赖|go|
|github.com/PuerkitoBio/goquery|v1.8.0|间接依赖|go|
|github.com/linxGnu/gumble|v1.0.0|间接依赖|go|
|github.com/blang/semver/v4|v4.0.0|间接依赖|go|
|golang.org/x/mod|v0.11.0|间接依赖|go|
|github.com/robfig/cron/v3|v3.0.0|间接依赖|go|
|github.com/cenkalti/backoff/v4|v4.1.0|间接依赖|go|
|github.com/vanng822/go-premailer|v0.0.0-20191214114701-be27abe028fe|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.19|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.0.0|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/crawlab-team/crawlab-db|v0.6.0-beta.20220417.1300.0.20221226064900-5a357ee73484|间接依赖|go|
|github.com/jaytaylor/html2text|v0.0.0-20180606194806-57d518f124b0|间接依赖|go|
|github.com/xanzy/ssh-agent|v0.3.3|间接依赖|go|
|github.com/crawlab-team/goseaweedfs|v0.6.0-beta.20211101.1936.0.20220912021203-dfee5f74dd69|间接依赖|go|
|github.com/andybalholm/cascadia|v1.3.1|间接依赖|go|
|github.com/pelletier/go-toml/v2|v2.0.8|间接依赖|go|
|github.com/twitchyliquid64/golang-asm|v0.15.1|间接依赖|go|
|github.com/crawlab-team/crawlab-grpc|v0.6.0-beta.20211219.1930.0.20221020032435-afa1c691f73c|间接依赖|go|
|github.com/lib/pq|v1.10.4|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|github.com/ProtonMail/go-crypto|v0.0.0-20230626094100-7e9e0395ebec|间接依赖|go|
|github.com/tklauser/numcpus|v0.3.0|间接依赖|go|
|google.golang.org/protobuf|v1.30.0|间接依赖|go|
|github.com/kevinburke/ssh_config|v1.2.0|间接依赖|go|
|github.com/crawlab-team/crawlab-vcs|v0.6.2-0.20230629045457-afe0be0e2185|间接依赖|go|
|github.com/bytedance/sonic|v1.9.1|间接依赖|go|
|github.com/go-ole/go-ole|v1.2.6|间接依赖|go|
|github.com/imdario/mergo|v0.3.16|间接依赖|go|
|github.com/xdg-go/pbkdf2|v1.0.0|间接依赖|go|
|github.com/ssor/bom|v0.0.0-20170718123548-6386211fdfcf|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/Microsoft/go-winio|v0.6.1|间接依赖|go|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|github.com/go-playground/universal-translator|v0.18.1|间接依赖|go|
|github.com/hashicorp/go-uuid|v1.0.1|间接依赖|go|
|github.com/gin-gonic/gin|v1.9.1|间接依赖|go|
|golang.org/x/sync|v0.3.0|间接依赖|go|
|github.com/olivere/elastic/v7|v7.0.15|间接依赖|go|
|github.com/xdg-go/stringprep|v1.0.2|间接依赖|go|
|github.com/mattn/go-sqlite3|v1.14.9|间接依赖|go|
|github.com/jackc/pgtype|v1.10.0|间接依赖|go|
|github.com/mattn/go-runewidth|v0.0.3|间接依赖|go|
|github.com/robertkrimen/otto|v0.0.0-20210614181706-373ff5438452|间接依赖|go|
|gopkg.in/gomail.v2|v2.0.0-20160411212932-81ebce5c23df|间接依赖|go|
|github.com/go-git/gcfg|v1.5.1-0.20230307220236-3a3c6141e376|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)