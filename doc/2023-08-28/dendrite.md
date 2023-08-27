# matrix-org/dendrite安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695863715524931584.svg)](https://www.murphysec.com/console/report/1695863715252301824/1695863715524931584)

仓库描述：Dendrite is a second-generation Matrix homeserver written in Go!

仓库地址：[https://github.com/matrix-org/dendrite](https://github.com/matrix-org/dendrite)

| star：4851 | watch：105 | fork：609 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-26 19:35:35 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-28 02:20:08 | 组件总数：240 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|github.com/codeclysm/extract 存在路径遍历漏洞|路径遍历|[MPS-2022-13341](https://www.oscs1024.com/hd/MPS-2022-13341)||中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/codeclysm/extract|v2.2.0+incompatible|3.0.1|直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|42|Low|
|Apache-2.0|52|Low|
|BSD-3-Clause|40|Low|
|LGPL-3.0|2|Medium|
|MPL-2.0|5|Low|
|自定义许可证|5|Low|
|Zlib|1|Low|
|ISC|2|Low|
|BSD-2-Clause|3|Low|
|CC-BY-SA-4.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|em-websocket|0.5.3|间接依赖|bundler|
|octokit|4.22.0|间接依赖|bundler|
|github.com/sirupsen/logrus|v1.9.3|直接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|golang.org/x/mobile|v0.0.0-20221020085226-b36e6246172e|直接依赖|go|
|pathutil|0.16.2|间接依赖|bundler|
|github.com/nats-io/nats-server/v2|v2.9.19|直接依赖|go|
|github.com/yggdrasil-network/yggdrasil-go|v0.4.6|直接依赖|go|
|github.com/neilalexander/utp|v0.1.1-0.20210727203401-54ae7b1cd5f9|直接依赖|go|
|github.com/docker/go-units|v0.5.0|间接依赖|go|
|golang.org/x/text|v0.12.0|间接依赖|go|
|github.com/blevesearch/upsidedown_store_api|v1.0.2|间接依赖|go|
|github.com/docker/distribution|v2.8.2+incompatible|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|sawyer|0.8.2|间接依赖|bundler|
|ethon|0.15.0|间接依赖|bundler|
|commonmarker|0.23.9|间接依赖|bundler|
|github.com/tidwall/gjson|v1.16.0|直接依赖|go|
|github.com/HdrHistogram/hdrhistogram-go|v1.1.2|间接依赖|go|
|jekyll-theme-leap-day|0.2.0|间接依赖|bundler|
|github.com/golang/snappy|v0.0.4|间接依赖|go|
|faraday-httpclient|1.0.1|间接依赖|bundler|
|jekyll-theme-primer|0.6.0|间接依赖|bundler|
|racc|1.6.2|间接依赖|bundler|
|safe_yaml|1.0.5|间接依赖|bundler|
|faraday-em_http|1.0.0|间接依赖|bundler|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/nats-io/nuid|v1.0.1|间接依赖|go|
|modernc.org/sqlite|v1.23.1|直接依赖|go|
|maunium.net/go/mautrix|v0.15.1|直接依赖|go|
|github.com/nats-io/nats.go|v1.27.0|直接依赖|go|
|github.com/kardianos/minwinsvc|v1.0.2|直接依赖|go|
|github.com/Masterminds/semver/v3|v3.1.1|直接依赖|go|
|golang.org/x/exp|v0.0.0-20230809150735-7b3493d9a819|直接依赖|go|
|unf_ext|0.0.8.1|间接依赖|bundler|
|golang.org/x/crypto|v0.12.0|直接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|github.com/uber/jaeger-lib|v2.4.1+incompatible|直接依赖|go|
|jekyll-theme-modernist|0.2.0|间接依赖|bundler|
|nhooyr.io/websocket|v1.8.7|直接依赖|go|
|modernc.org/cc/v3|v3.40.0|间接依赖|go|
|activesupport|6.0.6.1|间接依赖|bundler|
|modernc.org/mathutil|v1.5.0|间接依赖|go|
|github.com/blevesearch/zapx/v12|v12.3.7|间接依赖|go|
|html-pipeline|2.14.1|间接依赖|bundler|
|jekyll-gist|1.5.0|间接依赖|bundler|
|jekyll-relative-links|0.6.1|间接依赖|bundler|
|github.com/matrix-org/go-sqlite3-js|v0.0.0-20220419092513-28aa791a1c91|直接依赖|go|
|rouge|3.26.0|间接依赖|bundler|
|kramdown-parser-gfm|1.1.0|间接依赖|bundler|
|jekyll-theme-slate|0.2.0|间接依赖|bundler|
|github.com/stretchr/testify|v1.8.2|直接依赖|go|
|github.com/golang/mock|v1.6.0|间接依赖|go|
|simpleidn|0.2.1|间接依赖|bundler|
|github.com/quic-go/qtls-go1-20|v0.3.2|间接依赖|go|
|golang.org/x/mod|v0.12.0|间接依赖|go|
|modernc.org/libc|v1.22.5|间接依赖|go|
|faraday-retry|1.0.3|间接依赖|bundler|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|modernc.org/memory|v1.5.0|间接依赖|go|
|jekyll-mentions|1.6.0|间接依赖|bundler|
|github.com/blevesearch/zapx/v13|v13.3.7|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|直接依赖|go|
|minitest|5.17.0|间接依赖|bundler|
|unicode-display_width|1.8.0|间接依赖|bundler|
|http_parser.rb|0.8.0|间接依赖|bundler|
|github.com/blevesearch/geo|v0.1.17|间接依赖|go|
|liquid|4.0.3|间接依赖|bundler|
|github.com/google/pprof|v0.0.0-20230808223545-4887780b67fb|间接依赖|go|
|github.com/tidwall/pretty|v1.2.1|间接依赖|go|
|github.com/matrix-org/dugong|v0.0.0-20210921133753-66e6b1c67e2e|直接依赖|go|
|tzinfo|1.2.11|间接依赖|bundler|
|jekyll-theme-dinky|0.2.0|间接依赖|bundler|
|github.com/Arceliar/ironwood|v0.0.0-20221025225125-45b4281814c2|直接依赖|go|
|sql.js|git+ssh://git@github.com/neilalexander/sql.js.git#252a72bf57b0538cbd49bbd6f70af71e516966ae|直接依赖|npm|
|jekyll-paginate|1.1.0|间接依赖|bundler|
|rb-fsevent|0.11.1|间接依赖|bundler|
|github.com/juju/errors|v1.0.0|间接依赖|go|
|faraday-excon|1.1.0|间接依赖|bundler|
|gemoji|3.0.1|间接依赖|bundler|
|github.com/mschoch/smat|v0.2.0|间接依赖|go|
|rb-inotify|0.10.1|间接依赖|bundler|
|golang.org/x/term|v0.11.0|直接依赖|go|
|go.etcd.io/bbolt|v1.3.6|间接依赖|go|
|github.com/DATA-DOG/go-sqlmock|v1.5.0|直接依赖|go|
|dnsruby|1.61.9|间接依赖|bundler|
|github.com/patrickmn/go-cache|v2.1.0+incompatible|直接依赖|go|
|golang.org/x/sys|v0.11.0|间接依赖|go|
|terminal-table|1.8.0|间接依赖|bundler|
|github.com/blevesearch/zapx/v11|v11.3.7|间接依赖|go|
|github.com/matrix-org/util|v0.0.0-20221111132719-399730281e66|直接依赖|go|
|github.com/blevesearch/vellum|v1.0.9|间接依赖|go|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|eventmachine|1.2.7|间接依赖|bundler|
|github.com/docker/go-connections|v0.4.0|直接依赖|go|
|github.com/matrix-org/gomatrixserverlib|v0.0.0-20230823153616-484e7693bb8d|直接依赖|go|
|gopkg.in/h2non/bimg.v1|v1.1.9|直接依赖|go|
|github.com/matrix-org/gomatrix|v0.0.0-20220926102614-ceba4d9f7530|直接依赖|go|
|jekyll|3.9.2|间接依赖|bundler|
|go.uber.org/atomic|v1.10.0|直接依赖|go|
|github.com/prometheus/client_golang|v1.16.0|直接依赖|go|
|jekyll-theme-midnight|0.2.0|间接依赖|bundler|
|github.com/blevesearch/bleve_index_api|v1.0.5|间接依赖|go|
|github.com/minio/highwayhash|v1.0.2|间接依赖|go|
|jekyll-github-metadata|2.13.0|间接依赖|bundler|
|github.com/Microsoft/go-winio|v0.5.2|间接依赖|go|
|unf|0.1.4|间接依赖|bundler|
|github.com/mattn/go-sqlite3|v1.14.17|直接依赖|go|
|github.com/google/uuid|v1.3.0|直接依赖|go|
|github.com/uber/jaeger-client-go|v2.30.0+incompatible|直接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|jekyll-avatar|0.7.0|间接依赖|bundler|
|github.com/blevesearch/segment|v0.9.1|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|github.com/rs/zerolog|v1.29.1|间接依赖|go|
|github.com/opencontainers/image-spec|v1.0.3-0.20211202183452-c5a74bcca799|间接依赖|go|
|jemoji|0.12.0|间接依赖|bundler|
|github.com/blevesearch/zapx/v14|v14.3.7|间接依赖|go|
|jekyll-theme-merlot|0.2.0|间接依赖|bundler|
|github.com/nats-io/nkeys|v0.4.4|间接依赖|go|
|maunium.net/go/maulogger/v2|v2.4.1|间接依赖|go|
|minima|2.5.1|间接依赖|bundler|
|jekyll-commonmark-ghpages|0.2.0|间接依赖|bundler|
|faraday-multipart|1.0.3|间接依赖|bundler|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|jekyll-feed|0.15.1|间接依赖|bundler|
|github.com/Arceliar/phony|v0.0.0-20210209235338-dde1a8dca979|直接依赖|go|
|github.com/go-task/slim-sprig|v0.0.0-20230315185526-52ccab3ef572|间接依赖|go|
|github.com/rogpeppe/go-internal|v1.9.0|间接依赖|go|
|github.com/nfnt/resize|v0.0.0-20180221191011-83c6a9932646|直接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/opentracing/opentracing-go|v1.2.0|直接依赖|go|
|jekyll-theme-tactile|0.2.0|间接依赖|bundler|
|github.com/nats-io/jwt/v2|v2.4.1|间接依赖|go|
|github.com/morikuni/aec|v1.0.0|间接依赖|go|
|jekyll-theme-cayman|0.2.0|间接依赖|bundler|
|github.com/moby/term|v0.0.0-20220808134915-39b0c02b01ae|间接依赖|go|
|github.com/tidwall/match|v1.1.1|间接依赖|go|
|github.com/blevesearch/go-porterstemmer|v1.0.3|间接依赖|go|
|github.com/prometheus/procfs|v0.10.1|间接依赖|go|
|jekyll-remote-theme|0.4.3|间接依赖|bundler|
|github.com/blevesearch/gtreap|v0.1.1|间接依赖|go|
|i18n|0.9.5|间接依赖|bundler|
|jekyll-titles-from-headings|0.5.3|间接依赖|bundler|
|rexml|3.2.5|间接依赖|bundler|
|github.com/RoaringBitmap/roaring|v1.2.3|间接依赖|go|
|public_suffix|4.0.7|间接依赖|bundler|
|github.com/blevesearch/zapx/v15|v15.3.10|间接依赖|go|
|sass-listen|4.0.0|间接依赖|bundler|
|golang.org/x/tools|v0.12.0|间接依赖|go|
|typhoeus|1.4.0|间接依赖|bundler|
|github.com/MFAshby/stdemuxerhook|v1.0.0|直接依赖|go|
|execjs|2.8.1|间接依赖|bundler|
|github.com/golang/geo|v0.0.0-20210211234256-740aa86cb551|间接依赖|go|
|golang.org/x/sync|v0.3.0|直接依赖|go|
|jekyll-sass-converter|1.5.2|间接依赖|bundler|
|github.com/prometheus/client_model|v0.3.0|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.17|间接依赖|go|
|jekyll-readme-index|0.3.0|间接依赖|bundler|
|ruby2_keywords|0.0.5|间接依赖|bundler|
|github.com/dustin/go-humanize|v1.0.1|间接依赖|go|
|coffee-script|2.4.1|间接依赖|bundler|
|sass|3.7.4|间接依赖|bundler|
|github.com/prometheus/common|v0.42.0|间接依赖|go|
|github-pages|226|间接依赖|bundler|
|github.com/dgraph-io/ristretto|v0.1.1|直接依赖|go|
|concurrent-ruby|1.2.0|间接依赖|bundler|
|faraday-patron|1.0.0|间接依赖|bundler|
|jekyll-optional-front-matter|0.3.2|间接依赖|bundler|
|jekyll-theme-time-machine|0.2.0|间接依赖|bundler|
|github.com/blevesearch/bleve/v2|v2.3.8|直接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|github.com/onsi/ginkgo/v2|v2.11.0|间接依赖|go|
|github.com/blevesearch/scorch_segment_api/v2|v2.1.4|间接依赖|go|
|modernc.org/strutil|v1.1.3|间接依赖|go|
|jekyll-default-layout|0.1.4|间接依赖|bundler|
|modernc.org/opt|v0.1.3|间接依赖|go|
|golang.org/x/image|v0.5.0|直接依赖|go|
|modernc.org/token|v1.0.1|间接依赖|go|
|github.com/klauspost/compress|v1.16.5|间接依赖|go|
|github.com/h2non/filetype|v1.1.3|间接依赖|go|
|rubyzip|2.3.2|间接依赖|bundler|
|github.com/remyoudompheng/bigfft|v0.0.0-20230129092748-24d4a6f8daec|间接依赖|go|
|jekyll-theme-architect|0.2.0|间接依赖|bundler|
|jekyll-commonmark|1.4.0|间接依赖|bundler|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|jekyll-swiss|1.0.0|间接依赖|bundler|
|multipart-post|2.1.1|间接依赖|bundler|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/lib/pq|v1.10.9|直接依赖|go|
|github.com/gorilla/mux|v1.8.0|直接依赖|go|
|jekyll-include-cache|0.2.1|间接依赖|bundler|
|lukechampine.com/uint128|v1.2.0|间接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0|间接依赖|go|
|github.com/gorilla/websocket|v1.5.0|直接依赖|go|
|github.com/kballard/go-shellquote|v0.0.0-20180428030007-95032a82bc51|间接依赖|go|
|modernc.org/ccgo/v3|v3.16.13|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|nokogiri|1.14.3-x86_64-linux|间接依赖|bundler|
|ws|7.5.2|直接依赖|npm|
|jekyll-watch|2.2.1|间接依赖|bundler|
|github.com/docker/docker|v20.10.24+incompatible|直接依赖|go|
|jekyll-seo-tag|2.8.0|间接依赖|bundler|
|github.com/matrix-org/pinecone|v0.11.1-0.20230810010612-ea4c33717fd7|直接依赖|go|
|github.com/golang/glog|v1.0.0|间接依赖|go|
|colorator|1.1.0|间接依赖|bundler|
|isomorphic-ws|4.0.1|直接依赖|npm|
|jekyll-theme-hacker|0.2.0|间接依赖|bundler|
|faraday-net_http|1.0.1|间接依赖|bundler|
|jekyll-redirect-from|0.16.0|间接依赖|bundler|
|faraday-em_synchrony|1.0.0|间接依赖|bundler|
|github.com/codeclysm/extract|v2.2.0+incompatible|直接依赖|go|
|github.com/blevesearch/mmap-go|v1.0.4|间接依赖|go|
|faraday-net_http_persistent|1.2.0|间接依赖|bundler|
|thread_safe|0.3.6|间接依赖|bundler|
|google.golang.org/protobuf|v1.30.0|间接依赖|go|
|addressable|2.8.0|间接依赖|bundler|
|forwardable-extended|2.6.0|间接依赖|bundler|
|ffi|1.15.5|间接依赖|bundler|
|jekyll-coffeescript|1.1.1|间接依赖|bundler|
|gotest.tools/v3|v3.4.0|直接依赖|go|
|github.com/bits-and-blooms/bitset|v1.5.0|间接依赖|go|
|github.com/gologme/log|v1.3.0|直接依赖|go|
|listen|3.7.1|间接依赖|bundler|
|github.com/quic-go/quic-go|v0.37.4|间接依赖|go|
|coffee-script-source|1.11.1|间接依赖|bundler|
|mercenary|0.3.6|间接依赖|bundler|
|github.com/blevesearch/snowballstem|v0.9.0|间接依赖|go|
|github.com/tidwall/sjson|v1.2.5|直接依赖|go|
|github-pages-health-check|1.17.9|间接依赖|bundler|
|golang.org/x/time|v0.3.0|间接依赖|go|
|jekyll-theme-minimal|0.2.0|间接依赖|bundler|
|faraday-rack|1.0.0|间接依赖|bundler|
|kramdown|2.3.2|间接依赖|bundler|
|gopkg.in/macaroon.v2|v2.1.0|间接依赖|go|
|faraday|1.10.0|间接依赖|bundler|
|jekyll-sitemap|1.4.0|间接依赖|bundler|
|golang.org/x/net|v0.14.0|间接依赖|go|
|github.com/getsentry/sentry-go|v0.14.0|直接依赖|go|
|zeitwerk|2.6.6|间接依赖|bundler|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)