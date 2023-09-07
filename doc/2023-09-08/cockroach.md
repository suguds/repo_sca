# cockroachdb/cockroach安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699847251086147584.svg)](https://www.murphysec.com/console/report/1699847251035815936/1699847251086147584)

仓库描述：CockroachDB - the open source, cloud-native distributed SQL database.

仓库地址：[https://github.com/cockroachdb/cockroach](https://github.com/cockroachdb/cockroach)

| star：27736 | watch：706 | fork：3522 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-08 02:08:32 | 许可证：NOASSERTION |
| 最近检测时间：2023-09-08 02:10:33 | 组件总数：487 | 漏洞总数：46 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|PostgreSQL JDBC <42.2.5 存在证书验证不当漏洞|对宿主不匹配的证书验证不恰当|[MPS-2018-11656](https://www.oscs1024.com/hd/MPS-2018-11656)|CVE-2018-10936|高危|
|Sequelize SQL注入漏洞|SQL注入|[MPS-2019-13441](https://www.oscs1024.com/hd/MPS-2019-13441)|CVE-2019-10752|严重|
|Sequelize SQL注入漏洞|SQL注入|[MPS-2019-13883](https://www.oscs1024.com/hd/MPS-2019-13883)|CVE-2019-10748|严重|
|lodash 原型污染漏洞|拒绝服务|[MPS-2019-8636](https://www.oscs1024.com/hd/MPS-2019-8636)|CVE-2019-10744|严重|
|jwt-go 安全漏洞|授权检查缺失|[MPS-2020-13786](https://www.oscs1024.com/hd/MPS-2020-13786)|CVE-2020-26160|高危|
|Junit 信息泄露漏洞|不安全的临时文件|[MPS-2020-15183](https://www.oscs1024.com/hd/MPS-2020-15183)|CVE-2020-15250|中危|
|lodash <4.17.15 原型污染漏洞|原型污染|[MPS-2020-15679](https://www.oscs1024.com/hd/MPS-2020-15679)|CVE-2020-8203|高危|
|minimist 原型污染漏洞|原型污染|[MPS-2020-3516](https://www.oscs1024.com/hd/MPS-2020-3516)|CVE-2020-7598|中危|
|PgJDBC <42.2.13 存在 XXE 漏洞|XXE|[MPS-2020-8204](https://www.oscs1024.com/hd/MPS-2020-8204)|CVE-2020-13692|高危|
|lodash 拒绝服务漏洞|拒绝服务|[MPS-2021-2574](https://www.oscs1024.com/hd/MPS-2021-2574)|CVE-2020-28500|中危|
|lodash 命令注入漏洞|代码注入|[MPS-2021-2638](https://www.oscs1024.com/hd/MPS-2021-2638)|CVE-2021-23337|高危|
|validator.js 拒绝服务漏洞|拒绝服务|[MPS-2021-31021](https://www.oscs1024.com/hd/MPS-2021-31021)|CVE-2021-3765|高危|
|quarkus 远程代码执行漏洞|初始化不恰当|[MPS-2021-37082](https://www.oscs1024.com/hd/MPS-2021-37082)|CVE-2022-21724|高危|
|minimist 安全漏洞|原型污染|[MPS-2021-38405](https://www.oscs1024.com/hd/MPS-2021-38405)|CVE-2021-44906|严重|
|Moment.js 正则拒绝服务漏洞|拒绝服务|[MPS-2022-11159](https://www.oscs1024.com/hd/MPS-2022-11159)|CVE-2022-31129|高危|
|diff 存在拒绝服务漏洞||[MPS-2022-12883](https://www.oscs1024.com/hd/MPS-2022-12883)||高危|
|vitess.io/vitess 存在跨站脚本漏洞|XSS|[MPS-2022-13515](https://www.oscs1024.com/hd/MPS-2022-13515)||中危|
|lodash<4.17.20 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13841](https://www.oscs1024.com/hd/MPS-2022-13841)||高危|
|lodash<4.17.17 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13842](https://www.oscs1024.com/hd/MPS-2022-13842)||高危|
|mocha < 6.0.0 存在ReDos漏洞|不正确的正则表达式|[MPS-2022-13886](https://www.oscs1024.com/hd/MPS-2022-13886)||中危|
|sequelize 存在拒绝服务漏洞|拒绝服务|[MPS-2022-14034](https://www.oscs1024.com/hd/MPS-2022-14034)||中危|
|validator<13.6.0 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2022-14122](https://www.oscs1024.com/hd/MPS-2022-14122)||中危|
|validator<13.6.0 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2022-14123](https://www.oscs1024.com/hd/MPS-2022-14123)||中危|
|validator<13.6.0 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2022-14124](https://www.oscs1024.com/hd/MPS-2022-14124)||中危|
|Moment.js 路径遍历漏洞|路径遍历|[MPS-2022-3752](https://www.oscs1024.com/hd/MPS-2022-3752)|CVE-2022-24785|中危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|sequelize SQL 注入漏洞|SQL注入|[MPS-2022-52071](https://www.oscs1024.com/hd/MPS-2022-52071)||高危|
|mocha ReDoS 漏洞|ReDoS|[MPS-2022-54598](https://www.oscs1024.com/hd/MPS-2022-54598)||高危|
|sequelize SQL注入|SQL注入|[MPS-2022-54713](https://www.oscs1024.com/hd/MPS-2022-54713)||严重|
|moment-timezone 存在命令注入|命令注入|[MPS-2022-56430](https://www.oscs1024.com/hd/MPS-2022-56430)||严重|
|postgresql <42.3.3 存在代码注入漏洞|代码注入|[MPS-2022-5828](https://www.oscs1024.com/hd/MPS-2022-5828)|CVE-2022-26520|严重|
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58307](https://www.oscs1024.com/hd/MPS-2022-58307)|CVE-2022-41723|高危|
|pgjdbc <42.5.1 存在信息泄露漏洞|不安全的临时文件|[MPS-2022-58583](https://www.oscs1024.com/hd/MPS-2022-58583)|CVE-2022-41946|中危|
|minimatch 资源管理错误漏洞|拒绝服务|[MPS-2022-59845](https://www.oscs1024.com/hd/MPS-2022-59845)|CVE-2022-3517|高危|
|Google Go 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2022-9049](https://www.oscs1024.com/hd/MPS-2022-9049)|CVE-2022-29526|中危|
|feathers-sequelize 安全漏洞|特殊元素过滤不恰当|[MPS-2023-0127](https://www.oscs1024.com/hd/MPS-2023-0127)|CVE-2023-22578|严重|
|feathers-sequelize 安全漏洞|SQL注入|[MPS-2023-0128](https://www.oscs1024.com/hd/MPS-2023-0128)|CVE-2023-22579|高危|
|Tiki Wiki CMS Groupware 信息泄露漏洞|用 PHP 编写的软件的弱点|[MPS-2023-0129](https://www.oscs1024.com/hd/MPS-2023-0129)|CVE-2023-22580|高危|
|Sequelize < 6.19.1 存在 SQL 注入漏洞|SQL注入|[MPS-2023-4688](https://www.oscs1024.com/hd/MPS-2023-4688)|CVE-2023-25813|高危|
|dottie 安全漏洞|原型污染|[MPS-2023-5126](https://www.oscs1024.com/hd/MPS-2023-5126)|CVE-2023-26132|高危|
|Moby 安全漏洞||[MPS-2023-8823](https://www.oscs1024.com/hd/MPS-2023-8823)|CVE-2023-28840|高危|
|Moby 安全漏洞||[MPS-2023-8824](https://www.oscs1024.com/hd/MPS-2023-8824)|CVE-2023-28841|中危|
|Moby 安全漏洞||[MPS-2023-8826](https://www.oscs1024.com/hd/MPS-2023-8826)|CVE-2023-28842|中危|
|Vitess 安全漏洞||[MPS-2023-9400](https://www.oscs1024.com/hd/MPS-2023-9400)|CVE-2023-29194|低危|
|Vitess 安全漏洞||[MPS-2023-9401](https://www.oscs1024.com/hd/MPS-2023-9401)|CVE-2023-29195|中危|
|gosnowflake 命令注入漏洞|命令注入|[MPS-20ay-lrc4](https://www.oscs1024.com/hd/MPS-20ay-lrc4)|CVE-2023-34231|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/docker/docker|v20.10.17+incompatible|23.0.3|直接依赖|建议修复|C:0|H:1|M:2|L:0|
|mocha|4.0.1|6.0.0|直接依赖|建议修复|C:0|H:1|M:1|L:0|
|moment-timezone|0.5.14|0.5.35|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|github.com/snowflakedb/gosnowflake|v1.3.4|1.6.19|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|validator|9.4.1|13.7.0|间接依赖|建议修复|C:0|H:1|M:3|L:0|
|github.com/dgrijalva/jwt-go|v3.2.0+incompatible|4.0.0-preview1|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|diff|3.3.1|3.5.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|golang.org/x/net|v0.0.0-20211008194852-3b03d305991f|0.7.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|dottie|2.0.0|2.0.4|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.postgresql:postgresql|42.1.4|42.5.1|直接依赖|建议修复|C:1|H:3|M:1|L:0|
|lodash|4.17.11|4.17.21|直接依赖|建议修复|C:1|H:4|M:1|L:0|
|minimatch|3.0.4|3.0.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|minimist|0.0.8|1.2.6|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|sequelize|4.37.1|6.29.0|直接依赖|建议修复|C:4|H:4|M:1|L:0|
|vitess.io/vitess|v0.0.0-00010101000000-000000000000|10.0.0-rc1|直接依赖|可选修复|C:0|H:0|M:2|L:1|
|golang.org/x/sys|v0.0.0-20220209214540-3681064d5158|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|semver|4.3.2|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|junit:junit|4.8.1|4.13.1|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|moment|2.21.0|2.29.4|间接依赖|可选修复|C:0|H:1|M:1|L:0|
|semver|5.5.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|197|Low|
|BSD-2-Clause|27|Low|
|Apache-2.0|170|Low|
|BSD-3-Clause|71|Low|
|自定义许可证|3|Low|
|CC0-1.0|3|Low|
|BSL-1.0|2|Low|
|NCSA|2|Low|
|CC-BY-3.0|2|Low|
|HPND|2|Low|
|Zlib|2|Low|
|OpenSSL|2|Low|
|ISC|12|Low|
|MPL-2.0|6|Low|
|WTFPL|1|Low|
|JSON|1|Low|
|BSD|1|Low|
|GPL-3.0|1|Medium|
|GPL-3.0-or-later|1|Low|
|BSD-2-Clause-Views|1|Low|
|Public Domain|1|Low|
|CC-BY-SA-4.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/marusama/semaphore|v0.0.0-20190110074507-6952cef993b2|直接依赖|go|
|github.com/golang-commonmark/html|v0.0.0-20180910111043-7d7c804e1d46|间接依赖|go|
|github.com/muesli/termenv|v0.13.0|间接依赖|go|
|github.com/xdg-go/stringprep|v1.0.4|直接依赖|go|
|golang.org/x/net|v0.0.0-20211008194852-3b03d305991f|间接依赖|go|
|github.com/Azure/go-ansiterm|v0.0.0-20210617225240-d185dfc1b5a1|间接依赖|go|
|pg|7.3.0|直接依赖|npm|
|github.com/gogo/googleapis|v1.4.1|间接依赖|go|
|postgres-date|1.0.3|间接依赖|npm|
|github.com/DataDog/zstd|v1.5.0|间接依赖|go|
|github.com/go-openapi/inflect|v0.19.0|间接依赖|go|
|github.com/go-logfmt/logfmt|v0.5.1|间接依赖|go|
|buffer-writer|1.0.1|间接依赖|npm|
|github.com/mattn/go-isatty|v0.0.17|直接依赖|go|
|github.com/sasha-s/go-deadlock|v0.3.1|直接依赖|go|
|github.com/go-kit/log|v0.2.1|间接依赖|go|
|github.com/spf13/cast|v1.3.1|间接依赖|go|
|github.com/apache/arrow/go/v11|v11.0.0|直接依赖|go|
|inflight|1.0.6|间接依赖|npm|
|is-bluebird|1.0.2|间接依赖|npm|
|uuid|3.2.1|间接依赖|npm|
|github.com/russross/blackfriday|v1.6.0|间接依赖|go|
|github.com/go-openapi/runtime|v0.19.29|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/config|v1.15.3|直接依赖|go|
|generic-pool|3.4.2|间接依赖|npm|
|google.golang.org/grpc/examples|v0.0.0-20210324172016-702608ffae4d|间接依赖|go|
|github.com/docker/distribution|v2.7.1+incompatible|直接依赖|go|
|gopkg.in/ini.v1|v1.67.0|间接依赖|go|
|github.com/cockroachdb/ttycolor|v0.0.0-20210902133924-c7d7dcdde4e8|直接依赖|go|
|github.com/Masterminds/sprig|v2.22.0+incompatible|间接依赖|go|
|toposort-class|1.0.1|间接依赖|npm|
|golang.org/x/net|v0.11.0|直接依赖|go|
|github.com/andybalholm/cascadia|v1.2.0|间接依赖|go|
|github.com/atotto/clipboard|v0.1.4|间接依赖|go|
|github.com/cockroachdb/tools|v0.0.0-20211112185054-642e51449b40|直接依赖|go|
|github.com/Azure/go-autorest/autorest/azure/cli|v0.4.3|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/rds|v1.18.4|直接依赖|go|
|github.com/cockroachdb/apd/v3|v3.2.0|直接依赖|go|
|github.com/spf13/afero|v1.9.2|直接依赖|go|
|github.com/golang-commonmark/puny|v0.0.0-20180910110745-050be392d8b8|间接依赖|go|
|github.com/kr/pretty|v0.3.0|间接依赖|go|
|github.com/lib/pq|v1.10.7|直接依赖|go|
|go.opentelemetry.io/proto/otlp|v0.11.0|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.0.0|间接依赖|go|
|terraformer|1.0.8|间接依赖|npm|
|github.com/zabawaba99/go-gitignore|v0.0.0-20200117185801-39e6bddfb292|直接依赖|go|
|github.com/hashicorp/go-uuid|v1.0.3|间接依赖|go|
|golang.org/x/exp|v0.0.0-20230626212559-97b1e661b5df|直接依赖|go|
|github.com/containerd/console|v1.0.3|间接依赖|go|
|github.com/rs/dnscache|v0.0.0-20230804202142-fc85eb664529|直接依赖|go|
|github.com/xdg-go/scram|v1.1.2|直接依赖|go|
|vitess.io/vitess|v0.0.0-00010101000000-000000000000|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/credentials|v1.11.2|间接依赖|go|
|github.com/prometheus/client_model|v0.3.0|直接依赖|go|
|go.opentelemetry.io/otel/exporters/zipkin|v1.0.0-RC3|直接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|间接依赖|go|
|github.com/slack-go/slack|v0.9.5|直接依赖|go|
|github.com/golang/mock|v1.6.0|直接依赖|go|
|github.com/muesli/ansi|v0.0.0-20211031195517-c9f0611b6c70|间接依赖|go|
|github.com/JohnCGriffin/overflow|v0.0.0-20211019200055-46fa312c352c|间接依赖|go|
|moment-timezone|0.5.14|间接依赖|npm|
|golang.org/x/exp/typeparams|v0.0.0-20221208152030-732eee02a75a|间接依赖|go|
|github.com/muesli/cancelreader|v0.2.2|间接依赖|go|
|github.com/klauspost/compress|v1.16.0|直接依赖|go|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|github.com/alessio/shellescape|v1.4.1|直接依赖|go|
|he|1.1.1|间接依赖|npm|
|minimatch|3.0.4|间接依赖|npm|
|commander|2.11.0|间接依赖|npm|
|inflection|1.12.0|间接依赖|npm|
|github.com/rivo/uniseg|v0.2.0|间接依赖|go|
|requirements.txt||间接依赖|pip|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace/otlptracegrpc|v1.3.0|直接依赖|go|
|github.com/leanovate/gopter|v0.2.5-0.20190402064358-634a59d12406|直接依赖|go|
|github.com/minio/sha256-simd|v1.0.0|间接依赖|go|
|github.com/magiconair/properties|v1.8.5|间接依赖|go|
|github.com/knz/bubbline|v0.0.0-20230422210153-e176cdfe1c43|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/storage/azblob|v0.6.1|直接依赖|go|
|github.com/cockroachdb/go-test-teamcity|v0.0.0-20191211140407-cff980ad0a55|直接依赖|go|
|github.com/montanaflynn/stats|v0.6.6|直接依赖|go|
|golang.org/x/term|v0.9.0|直接依赖|go|
|minimist|0.0.8|间接依赖|npm|
|github.com/power-devops/perfstat|v0.0.0-20210106213030-5aafc221ea8c|间接依赖|go|
|js-string-escape|1.0.1|间接依赖|npm|
|github.com/russross/blackfriday/v2|v2.1.0|间接依赖|go|
|github.com/elastic/gosigar|v0.14.1|直接依赖|go|
|path-is-absolute|1.0.1|间接依赖|npm|
|github.com/aws/aws-sdk-go-v2/internal/ini|v1.3.10|间接依赖|go|
|dottie|2.0.0|间接依赖|npm|
|github.com/opencontainers/image-spec|v1.0.3-0.20211202183452-c5a74bcca799|直接依赖|go|
|github.com/minio/c2goasm|v0.0.0-20190812172519-36a3d3bbc4f3|间接依赖|go|
|golang.org/x/tools|v0.10.0|直接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|直接依赖|go|
|github.com/docker/docker|v20.10.17+incompatible|直接依赖|go|
|github.com/robfig/cron/v3|v3.0.1|直接依赖|go|
|github.com/buchgr/bazel-remote|v1.3.3|直接依赖|go|
|github.com/tklauser/numcpus|v0.3.0|间接依赖|go|
|github.com/goware/modvendor|v0.5.0|直接依赖|go|
|github.com/petermattis/goid|v0.0.0-20211229010228-4d14c490ee36|直接依赖|go|
|github.com/twpayne/go-kml|v1.5.2|间接依赖|go|
|sequelize-cockroachdb|1.0.2|直接依赖|npm|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/cenkalti/backoff/v4|v4.1.3|间接依赖|go|
|github.com/knz/strtime|v0.0.0-20200318182718-be999391ffa9|直接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|直接依赖|go|
|github.com/mmatczuk/go_generics|v0.0.0-20181212143635-0aaa050f9bab|直接依赖|go|
|github.com/dave/dst|v0.24.0|直接依赖|go|
|github.com/jordanlewis/gcassert|v0.0.0-20230505190637-fed79d91cd5f|直接依赖|go|
|github.com/jcmturner/goidentity/v6|v6.0.1|间接依赖|go|
|github.com/lufia/iostat|v1.2.1|直接依赖|go|
|github.com/ghemawat/stream|v0.0.0-20171120220530-696b145b53b9|直接依赖|go|
|github.com/apache/thrift|v0.16.0|间接依赖|go|
|github.com/go-stack/stack|v1.8.0|间接依赖|go|
|github.com/jackc/pgio|v1.0.0|间接依赖|go|
|github.com/jaegertracing/jaeger|v1.18.1|直接依赖|go|
|diff|3.3.1|间接依赖|npm|
|github.com/PuerkitoBio/goquery|v1.5.1|直接依赖|go|
|github.com/lestrrat-go/jwx|v1.2.25|直接依赖|go|
|github.com/go-openapi/swag|v0.19.15|间接依赖|go|
|github.com/cockroachdb/errors|v1.10.1|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/configsources|v1.1.27|间接依赖|go|
|github.com/gorilla/handlers|v1.5.1|间接依赖|go|
|pg-types|1.13.0|间接依赖|npm|
|postgres-bytea|1.0.0|间接依赖|npm|
|github.com/spf13/cobra|v1.2.1|直接依赖|go|
|cloud.google.com/go|v0.110.0|间接依赖|go|
|github.com/fatih/color|v1.9.0|直接依赖|go|
|ms|2.0.0|间接依赖|npm|
|cloud.google.com/go/longrunning|v0.4.1|间接依赖|go|
|golang.org/x/crypto|v0.10.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sso|v1.11.3|间接依赖|go|
|github.com/cockroachdb/cmux|v0.0.0-20170110192607-30d10be49292|直接依赖|go|
|github.com/mozillazg/go-unidecode|v0.2.0|间接依赖|go|
|balanced-match|1.0.0|间接依赖|npm|
|github.com/tklauser/go-sysconf|v0.3.9|间接依赖|go|
|github.com/toqueteos/webbrowser|v1.2.0|间接依赖|go|
|github.com/aws/aws-sdk-go|v1.40.37|直接依赖|go|
|github.com/cockroachdb/cockroach-go/v2|v2.3.5|直接依赖|go|
|github.com/jackc/pgtype|v1.14.0|直接依赖|go|
|github.com/PuerkitoBio/purell|v1.1.1|间接依赖|go|
|github.com/snowflakedb/gosnowflake|v1.3.4|直接依赖|go|
|moment|2.21.0|间接依赖|npm|
|github.com/jackc/puddle|v1.3.0|间接依赖|go|
|github.com/client9/misspell|v0.3.4|直接依赖|go|
|pg-pool|2.0.3|间接依赖|npm|
|google.golang.org/grpc|v1.53.0|直接依赖|go|
|github.com/dgrijalva/jwt-go|v3.2.0+incompatible|间接依赖|go|
|github.com/jordan-wright/email|v4.0.1-0.20210109023952-943e75fe5223+incompatible|直接依赖|go|
|github.com/stretchr/testify|v1.8.4|直接依赖|go|
|github.com/Azure/go-autorest/autorest/to|v0.4.0|直接依赖|go|
|github.com/eapache/queue|v1.1.0|间接依赖|go|
|github.com/xdg-go/pbkdf2|v1.0.0|直接依赖|go|
|github.com/trivago/tgo|v1.0.7|间接依赖|go|
|github.com/go-openapi/errors|v0.20.0|间接依赖|go|
|github.com/aclements/go-moremath|v0.0.0-20210112150236-f10218a38794|间接依赖|go|
|go.uber.org/atomic|v1.10.0|间接依赖|go|
|github.com/alexbrainman/sspi|v0.0.0-20180613141037-e580b900e9f5|间接依赖|go|
|github.com/containerd/containerd|v1.6.18|直接依赖|go|
|go.opentelemetry.io/otel|v1.3.0|直接依赖|go|
|github.com/fatih/structs|v1.1.0|间接依赖|go|
|concat-map|0.0.1|间接依赖|npm|
|glob|7.1.2|间接依赖|npm|
|github.com/cockroachdb/stress|v0.0.0-20220803192808-1806698b1b7b|直接依赖|go|
|growl|1.10.3|间接依赖|npm|
|github.com/cockroachdb/gostdlib|v1.19.0|直接依赖|go|
|github.com/mozillazg/go-slugify|v0.2.0|直接依赖|go|
|github.com/eapache/go-xerial-snappy|v0.0.0-20230111030713-bf00bc1b83b6|间接依赖|go|
|github.com/morikuni/aec|v1.0.0|间接依赖|go|
|github.com/go-openapi/validate|v0.20.2|间接依赖|go|
|github.com/google/btree|v1.0.1|直接依赖|go|
|github.com/sahilm/fuzzy|v0.1.0|间接依赖|go|
|through|2.3.8|间接依赖|npm|
|github.com/klauspost/asmfmt|v1.3.2|间接依赖|go|
|github.com/googleapis/gax-go/v2|v2.7.0|直接依赖|go|
|github.com/golang/glog|v1.0.0|间接依赖|go|
|go.opentelemetry.io/otel/exporters/jaeger|v1.0.0-RC3|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/presigned-url|v1.9.3|间接依赖|go|
|debug|3.1.0|间接依赖|npm|
|shimmer|1.2.0|间接依赖|npm|
|github.com/maruel/panicparse/v2|v2.2.2|直接依赖|go|
|github.com/pelletier/go-toml|v1.9.5|间接依赖|go|
|github.com/Masterminds/goutils|v1.1.0|间接依赖|go|
|pg-types|1.12.1|间接依赖|npm|
|github.com/rogpeppe/go-internal|v1.11.0|间接依赖|go|
|pg-int8|1.0.1|间接依赖|npm|
|github.com/google/flatbuffers|v2.0.8+incompatible|直接依赖|go|
|github.com/gofrs/uuid|v4.0.0+incompatible|间接依赖|go|
|inherits|2.0.3|间接依赖|npm|
|github.com/rogpeppe/go-internal|v1.8.1|间接依赖|go|
|@types/node|9.4.7|间接依赖|npm|
|github.com/cockroachdb/logtags|v0.0.0-20211118104740-dabe8e521a4f|间接依赖|go|
|github.com/felixge/httpsnoop|v1.0.1|间接依赖|go|
|github.com/google/go-github|v17.0.0+incompatible|直接依赖|go|
|retry-as-promised|2.3.2|间接依赖|npm|
|pg|6.4.2|间接依赖|npm|
|github.com/golang/protobuf|v1.5.3|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/databasemigrationservice|v1.18.3|直接依赖|go|
|github.com/Azure/go-autorest/tracing|v0.6.0|间接依赖|go|
|sequelize|4.37.1|直接依赖|npm|
|github.com/zeebo/xxh3|v1.0.2|间接依赖|go|
|cloud.google.com/go/kms|v1.8.0|直接依赖|go|
|github.com/pkg/browser|v0.0.0-20210115035449-ce105d075bb4|直接依赖|go|
|github.com/docker/go-units|v0.4.0|间接依赖|go|
|github.com/klauspost/cpuid/v2|v2.0.9|间接依赖|go|
|github.com/linkedin/goavro/v2|v2.12.0|直接依赖|go|
|github.com/jackc/pgproto3/v2|v2.3.2|直接依赖|go|
|github.com/jcmturner/gofork|v1.0.0|间接依赖|go|
|github.com/go-openapi/analysis|v0.20.0|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/keyvault/internal|v0.7.0|间接依赖|go|
|github.com/apache/arrow/go/arrow|v0.0.0-20200923215132-ac86123a3f01|直接依赖|go|
|github.com/abbot/go-http-auth|v0.4.1-0.20181019201920-860ed7f246ff|间接依赖|go|
|github.com/jcmturner/rpc/v2|v2.0.2|间接依赖|go|
|@types/geojson|1.0.6|间接依赖|npm|
|github.com/cpuguy83/go-md2man/v2|v2.0.1|间接依赖|go|
|github.com/go-ole/go-ole|v1.2.6|间接依赖|go|
|github.com/lestrrat-go/httpcc|v1.0.1|间接依赖|go|
|github.com/lufia/plan9stats|v0.0.0-20211012122336-39d0f177ccd0|间接依赖|go|
|depd|1.1.2|间接依赖|npm|
|mocha|4.0.1|直接依赖|npm|
|github.com/minio/minio-go/v7|v7.0.21|间接依赖|go|
|github.com/getsentry/sentry-go|v0.12.0|间接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway|v1.16.0|直接依赖|go|
|google.golang.org/protobuf|v1.30.0|直接依赖|go|
|github.com/google/skylark|v0.0.0-20181101142754-a5f7082aabed|直接依赖|go|
|go.mongodb.org/mongo-driver|v1.5.1|间接依赖|go|
|github.com/hashicorp/go-uuid|v1.0.2|间接依赖|go|
|supports-color|4.4.0|间接依赖|npm|
|github.com/spf13/jwalterweatherman|v1.1.0|间接依赖|go|
|github.com/jcmturner/gokrb5/v8|v8.4.3|间接依赖|go|
|github.com/jcmturner/rpc/v2|v2.0.3|间接依赖|go|
|terraformer-wkt-parser|1.1.2|间接依赖|npm|
|go.opentelemetry.io/otel/trace|v1.3.0|直接依赖|go|
|cloud.google.com/go/iam|v0.12.0|间接依赖|go|
|github.com/axiomhq/hyperloglog|v0.0.0-20181223111420-4b99d0c2c99e|直接依赖|go|
|github.com/go-openapi/jsonreference|v0.19.5|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.5.1|直接依赖|go|
|google.golang.org/genproto|v0.0.0-20230227214838-9b19f0bdc514|直接依赖|go|
|fs.realpath|1.0.0|间接依赖|npm|
|github.com/golang-jwt/jwt/v4|v4.2.0|间接依赖|go|
|github.com/Azure/go-autorest/logger|v0.2.1|间接依赖|go|
|github.com/gofrs/flock|v0.8.1|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|org.postgresql:postgresql|42.1.4|直接依赖|maven|
|github.com/bufbuild/buf|v0.56.0|直接依赖|go|
|github.com/kisielk/errcheck|v1.6.1-0.20210625163953-8ddee489636a|直接依赖|go|
|github.com/minio/md5-simd|v1.1.2|间接依赖|go|
|github.com/coreos/go-oidc|v2.2.1+incompatible|直接依赖|go|
|github.com/golang-jwt/jwt|v3.2.2+incompatible|间接依赖|go|
|github.com/cockroachdb/errors|v1.9.0|直接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|直接依赖|go|
|github.com/Masterminds/semver|v1.5.0|间接依赖|go|
|github.com/irfansharif/recorder|v0.0.0-20211218081646-a21b46510fd6|直接依赖|go|
|github.com/docker/go-connections|v0.4.0|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/azidentity|v1.1.0|直接依赖|go|
|github.com/kevinburke/go-bindata|v3.13.0+incompatible|直接依赖|go|
|github.com/VividCortex/ewma|v1.1.1|直接依赖|go|
|junit:junit|4.8.1|直接依赖|maven|
|github.com/muesli/reflow|v0.3.0|间接依赖|go|
|postgres-array|1.0.2|间接依赖|npm|
|github.com/charmbracelet/bubbles|v0.15.1-0.20230123181021-a6a12c4a31eb|直接依赖|go|
|github.com/spf13/viper|v1.8.1|间接依赖|go|
|github.com/getsentry/sentry-go|v0.23.0|直接依赖|go|
|github.com/jackc/pgservicefile|v0.0.0-20221227161230-091c0ba34f0a|间接依赖|go|
|github.com/andy-kimball/arenaskl|v0.0.0-20200617143215-f701008588b9|直接依赖|go|
|github.com/hashicorp/errwrap|v1.1.0|间接依赖|go|
|github.com/eapache/go-resiliency|v1.3.0|间接依赖|go|
|github.com/urfave/cli/v2|v2.3.0|间接依赖|go|
|github.com/wadey/gocovmerge|v0.0.0-20160331181800-b5bfa59ec0ad|直接依赖|go|
|github.com/google/go-github/v42|v42.0.0|直接依赖|go|
|github.com/googleapis/enterprise-certificate-proxy|v0.2.3|间接依赖|go|
|github.com/djherbis/atime|v1.1.0|间接依赖|go|
|google.golang.org/api|v0.110.0|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/keyvault/azkeys|v0.9.0|直接依赖|go|
|brace-expansion|1.1.8|间接依赖|npm|
|github.com/mattn/goveralls|v0.0.2|直接依赖|go|
|github.com/hashicorp/go-multierror|v1.1.1|间接依赖|go|
|lodash|4.17.11|直接依赖|npm|
|github.com/golang-commonmark/markdown|v0.0.0-20180910011815-a8f139058164|直接依赖|go|
|golang.org/x/sys|v0.11.0|直接依赖|go|
|github.com/cockroachdb/returncheck|v0.0.0-20200612231554-92cdbca611dd|直接依赖|go|
|github.com/prometheus/client_golang|v1.16.0|直接依赖|go|
|github.com/mkungla/bexp/v3|v3.0.1|直接依赖|go|
|github.com/subosito/gotenv|v1.2.0|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/internal/retry|v1.3.0|间接依赖|go|
|semver|5.5.0|间接依赖|npm|
|github.com/imdario/mergo|v0.3.13|间接依赖|go|
|github.com/gorilla/mux|v1.8.0|直接依赖|go|
|github.com/asaskevich/govalidator|v0.0.0-20200907205600-7a23bdc65eef|间接依赖|go|
|github.com/google/shlex|v0.0.0-20191202100458-e7afc7fbc510|直接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|github.com/cockroachdb/datadriven|v1.0.3-0.20230801171734-e384cf455877|直接依赖|go|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ec2|v1.34.0|直接依赖|go|
|github.com/NYTimes/gziphandler|v0.0.0-20170623195520-56545f4a5d46|直接依赖|go|
|wrappy|1.0.2|间接依赖|npm|
|go.uber.org/multierr|v1.7.0|间接依赖|go|
|github.com/Azure/go-autorest/autorest/adal|v0.9.15|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sts|v1.16.3|间接依赖|go|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|wkx|0.4.4|间接依赖|npm|
|github.com/mitchellh/mapstructure|v1.5.0|间接依赖|go|
|cloud.google.com/go/compute/metadata|v0.2.3|间接依赖|go|
|github.com/pseudomuto/protokit|v0.2.0|间接依赖|go|
|packet-reader|0.3.1|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|github.com/bgentry/go-netrc|v0.0.0-20140422174119-9fd32a8b3d3d|间接依赖|go|
|semver|4.3.2|间接依赖|npm|
|github.com/aws/aws-sdk-go-v2/feature/ec2/imds|v1.12.3|间接依赖|go|
|github.com/kr/pretty|v0.3.1|直接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|github.com/lestrrat-go/backoff/v2|v2.0.8|间接依赖|go|
|github.com/dimchansky/utfbom|v1.1.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/secretsmanager|v1.18.2|直接依赖|go|
|go.opencensus.io|v0.24.0|间接依赖|go|
|github.com/pquerna/cachecontrol|v0.0.0-20200921180117-858c6e7e6b7e|间接依赖|go|
|github.com/Azure/go-autorest|v14.2.0+incompatible|间接依赖|go|
|github.com/BurntSushi/toml|v1.2.1|直接依赖|go|
|github.com/andybalholm/brotli|v1.0.5|间接依赖|go|
|golang.org/x/crypto|v0.0.0-20210921155107-089bfa567519|间接依赖|go|
|github.com/jackc/pgx/v5|v5.4.2|直接依赖|go|
|github.com/mostynb/go-grpc-compression|v1.1.12|间接依赖|go|
|github.com/MichaelTJones/walk|v0.0.0-20161122175330-4748e29d5718|直接依赖|go|
|github.com/pierrre/geohash|v1.0.0|直接依赖|go|
|github.com/otan/gopgkrb5|v1.0.3|直接依赖|go|
|github.com/cockroachdb/pebble|v0.0.0-20230905224231-5283f24b2a69|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/iam|v1.18.3|直接依赖|go|
|github.com/prometheus/procfs|v0.10.1|间接依赖|go|
|github.com/go-sql-driver/mysql|v1.6.0|直接依赖|go|
|github.com/minio/asm2plan9s|v0.0.0-20200509001527-cdd76441f9d8|间接依赖|go|
|github.com/lucasb-eyer/go-colorful|v1.2.0|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|github.com/jhump/protoreflect|v1.9.1-0.20210817181203-db1a327a393e|间接依赖|go|
|github.com/abourget/teamcity|v0.0.0-00010101000000-000000000000|直接依赖|go|
|github.com/mattn/go-runewidth|v0.0.14|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/guptarohit/asciigraph|v0.5.5|直接依赖|go|
|github.com/jessevdk/go-flags|v1.5.0|间接依赖|go|
|github.com/andygrunwald/go-jira|v1.14.0|直接依赖|go|
|github.com/cockroachdb/redact|v1.1.3|间接依赖|go|
|go.opentelemetry.io/otel/sdk|v1.3.0|直接依赖|go|
|pg-connection-string|0.1.3|间接依赖|npm|
|github.com/dgryski/go-metro|v0.0.0-20180109044635-280f6062b5bc|间接依赖|go|
|github.com/go-openapi/loads|v0.20.2|间接依赖|go|
|github.com/cockroachdb/tokenbucket|v0.0.0-20230807174530-cc333fc44b06|直接依赖|go|
|github.com/lestrrat-go/option|v1.0.0|间接依赖|go|
|github.com/blevesearch/snowballstem|v0.9.0|直接依赖|go|
|object-assign|4.1.0|间接依赖|npm|
|github.com/opennota/wd|v0.0.0-20180911144301-b446539ab1e7|间接依赖|go|
|github.com/Shopify/sarama|v1.38.1|直接依赖|go|
|golang.org/x/oauth2|v0.5.0|直接依赖|go|
|github.com/prometheus/prometheus|v1.8.2-0.20210914090109-37468d88dce8|直接依赖|go|
|github.com/ghodss/yaml|v1.0.0|间接依赖|go|
|golang.org/x/sys|v0.0.0-20220209214540-3681064d5158|间接依赖|go|
|validator|9.4.1|间接依赖|npm|
|github.com/codahale/hdrhistogram|v0.0.0-20161010025455-3a0bb77429bd|直接依赖|go|
|github.com/go-openapi/spec|v0.20.3|间接依赖|go|
|github.com/go-openapi/strfmt|v0.20.2|直接依赖|go|
|github.com/Azure/go-autorest/autorest/azure/auth|v0.5.8|直接依赖|go|
|github.com/kylelemons/godebug|v1.1.0|直接依赖|go|
|debug|2.6.9|间接依赖|npm|
|github.com/openzipkin/zipkin-go|v0.2.5|间接依赖|go|
|github.com/huandu/xstrings|v1.3.0|间接依赖|go|
|github.com/jackc/pgpassfile|v1.0.0|间接依赖|go|
|github.com/AzureAD/microsoft-authentication-library-for-go|v0.5.1|间接依赖|go|
|github.com/lestrrat-go/blackmagic|v1.0.1|间接依赖|go|
|github.com/charmbracelet/bubbletea|v0.23.1|间接依赖|go|
|gopkg.in/square/go-jose.v2|v2.5.1|间接依赖|go|
|github.com/lib/pq|v1.10.6|直接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|github.com/goccy/go-json|v0.9.11|间接依赖|go|
|github.com/Azure/go-autorest/autorest/date|v0.3.0|间接依赖|go|
|github.com/pierrec/lz4/v4|v4.1.17|直接依赖|go|
|github.com/jcmturner/dnsutils/v2|v2.0.0|间接依赖|go|
|golang.org/x/sync|v0.3.0|直接依赖|go|
|cls-bluebird|2.1.0|间接依赖|npm|
|github.com/mattn/go-localereader|v0.0.1|间接依赖|go|
|golang.org/x/time|v0.3.0|直接依赖|go|
|go.etcd.io/raft/v3|v3.0.0-20230717153924-72a6e6c9f3ee|直接依赖|go|
|github.com/gorilla/websocket|v1.4.2|间接依赖|go|
|postgres-interval|1.1.1|间接依赖|npm|
|github.com/klauspost/pgzip|v1.2.5|直接依赖|go|
|github.com/peterbourgon/g2s|v0.0.0-20170223122336-d4e7ad98afea|间接依赖|go|
|generic-pool|2.4.3|间接依赖|npm|
|github.com/kisielk/gotool|v1.0.0|直接依赖|go|
|github.com/bazelbuild/rules_go|v0.26.0|直接依赖|go|
|golang.org/x/text|v0.12.0|直接依赖|go|
|github.com/charmbracelet/lipgloss|v0.6.0|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|github.com/Azure/go-autorest/autorest/validation|v0.3.1|间接依赖|go|
|github.com/lestrrat-go/iter|v1.0.2|间接依赖|go|
|xtend|4.0.1|间接依赖|npm|
|github.com/jcmturner/gokrb5/v8|v8.2.0|间接依赖|go|
|github.com/aws/smithy-go|v1.13.5|间接依赖|go|
|github.com/cockroachdb/logtags|v0.0.0-20230118201751-21c54148d20b|直接依赖|go|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|github.com/golang-commonmark/mdurl|v0.0.0-20180910110917-8d018c6567d6|间接依赖|go|
|github.com/google/pprof|v0.0.0-20210827144239-02619b876842|直接依赖|go|
|github.com/go-logr/logr|v1.2.2|间接依赖|go|
|github.com/cockroachdb/redact|v1.1.5|直接依赖|go|
|github.com/twpayne/go-geom|v1.4.2|直接依赖|go|
|github.com/Azure/go-autorest/autorest|v0.11.20|直接依赖|go|
|github.com/Masterminds/semver/v3|v3.1.1|直接依赖|go|
|github.com/golang-commonmark/linkify|v0.0.0-20180910111149-f05efb453a0e|间接依赖|go|
|github.com/google/go-querystring|v1.1.0|间接依赖|go|
|github.com/gogo/status|v1.1.0|直接依赖|go|
|github.com/decred/dcrd/dcrec/secp256k1/v4|v4.1.0|间接依赖|go|
|github.com/twitchtv/twirp|v8.1.0+incompatible|间接依赖|go|
|github.com/shirou/gopsutil/v3|v3.21.12|直接依赖|go|
|honnef.co/go/tools|v0.4.5|直接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|直接依赖|go|
|github.com/gogo/protobuf|v1.3.2|直接依赖|go|
|github.com/prometheus/common|v0.42.0|直接依赖|go|
|github.com/cenkalti/backoff|v2.2.1+incompatible|直接依赖|go|
|golang.org/x/mod|v0.11.0|间接依赖|go|
|github.com/mattn/go-zglob|v0.0.3|间接依赖|go|
|github.com/mwitkow/go-proto-validators|v0.0.0-20180403085117-0950a7990007|间接依赖|go|
|github.com/mibk/dupl|v1.0.0|直接依赖|go|
|github.com/jackc/puddle/v2|v2.2.0|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/internal|v1.1.1|间接依赖|go|
|golang.org/x/xerrors|v0.0.0-20220907171357-04be3eba64a2|间接依赖|go|
|cloud.google.com/go/compute|v1.18.0|间接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/endpoints/v2|v2.4.21|间接依赖|go|
|github.com/Microsoft/go-winio|v0.5.2|间接依赖|go|
|github.com/golang/geo|v0.0.0-20200319012246-673a6f80352d|直接依赖|go|
|github.com/biogo/store|v0.0.0-20160505134755-913427a1d5e8|直接依赖|go|
|cloud.google.com/go/pubsub|v1.28.0|直接依赖|go|
|github.com/olekukonko/tablewriter|v0.0.5-0.20200416053754-163badb3bac6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2|v1.17.3|直接依赖|go|
|go.uber.org/zap|v1.19.0|间接依赖|go|
|github.com/cockroachdb/circuitbreaker|v2.2.2-0.20190114160014-a614b14ccf63+incompatible|直接依赖|go|
|github.com/facebookgo/clock|v0.0.0-20150410010913-600d898af40a|间接依赖|go|
|github.com/lib/pq/auth/kerberos|v0.0.0-20220516182748-8c6de565f76f|直接依赖|go|
|github.com/cockroachdb/crlfmt|v0.0.0-20221214225007-b2fc5c302548|直接依赖|go|
|github.com/pseudomuto/protoc-gen-doc|v1.3.2|直接依赖|go|
|has-flag|2.0.0|间接依赖|npm|
|github.com/pires/go-proxyproto|v0.7.0|直接依赖|go|
|github.com/slok/go-http-metrics|v0.10.0|间接依赖|go|
|github.com/sirupsen/logrus|v1.9.0|间接依赖|go|
|github.com/rcrowley/go-metrics|v0.0.0-20201227073835-cf1acfcdf475|直接依赖|go|
|github.com/pressly/goose/v3|v3.5.3|直接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|github.com/alexbrainman/sspi|v0.0.0-20210105120005-909beea2cc74|间接依赖|go|
|github.com/dustin/go-humanize|v1.0.0|直接依赖|go|
|github.com/jcmturner/gofork|v1.7.6|间接依赖|go|
|split|1.0.1|间接依赖|npm|
|github.com/PuerkitoBio/urlesc|v0.0.0-20170810143723-de5bf2ad4578|间接依赖|go|
|github.com/google/uuid|v1.3.0|直接依赖|go|
|github.com/oklog/ulid|v1.3.1|间接依赖|go|
|github.com/moby/term|v0.0.0-20210619224110-3f7ff695adc6|间接依赖|go|
|github.com/kr/text|v0.2.0|直接依赖|go|
|mkdirp|0.5.1|间接依赖|npm|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace|v1.3.0|间接依赖|go|
|pg-pool|1.8.0|间接依赖|npm|
|github.com/golang/snappy|v0.0.4|直接依赖|go|
|github.com/jcmturner/aescts/v2|v2.0.0|间接依赖|go|
|github.com/grpc-ecosystem/go-grpc-prometheus|v1.2.0|间接依赖|go|
|cloud.google.com/go/storage|v1.28.1|直接依赖|go|
|github.com/yusufpapurcu/wmi|v1.2.2|间接依赖|go|
|pg-error-codes|1.0.0|直接依赖|npm|
|github.com/pkg/profile|v1.6.0|间接依赖|go|
|github.com/rs/xid|v1.3.0|间接依赖|go|
|browser-stdout|1.3.0|间接依赖|npm|
|github.com/opencontainers/go-digest|v1.0.0|间接依赖|go|
|bluebird|3.5.1|间接依赖|npm|
|github.com/jackc/pgconn|v1.14.0|直接依赖|go|
|github.com/Azure/azure-sdk-for-go|v57.1.0+incompatible|直接依赖|go|
|github.com/edsrzf/mmap-go|v1.0.0|直接依赖|go|
|github.com/aymanbagabas/go-osc52|v1.0.3|间接依赖|go|
|github.com/mitchellh/copystructure|v1.0.0|间接依赖|go|
|github.com/go-swagger/go-swagger|v0.26.1|直接依赖|go|
|github.com/mitchellh/reflectwalk|v1.0.0|直接依赖|go|
|github.com/nightlyone/lockfile|v1.0.0|直接依赖|go|
|github.com/ianlancetaylor/demangle|v0.0.0-20200824232613-28f6c0f3b639|间接依赖|go|
|github.com/envoyproxy/protoc-gen-validate|v0.9.1|间接依赖|go|
|once|1.4.0|间接依赖|npm|
|github.com/Azure/azure-sdk-for-go/sdk/azcore|v1.3.0|直接依赖|go|
|github.com/fraugster/parquet-go|v0.10.0|直接依赖|go|
|github.com/jackc/pgx/v4|v4.18.1|直接依赖|go|
|github.com/emicklei/dot|v0.15.0|直接依赖|go|
|github.com/jackc/chunkreader/v2|v2.0.1|间接依赖|go|
|pgpass|1.0.2|间接依赖|npm|
|golang.org/x/perf|v0.0.0-20230113213139-801c7ef9e5c5|直接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.5|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)