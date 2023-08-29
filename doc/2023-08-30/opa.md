# open-policy-agent/opa安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696587328113172480.svg)](https://www.murphysec.com/console/report/1691874323597250560/1696587328113172480)

仓库描述：An open source, general-purpose policy engine.

仓库地址：[https://github.com/open-policy-agent/opa](https://github.com/open-policy-agent/opa)

| star：8382 | watch：122 | fork：1177 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-30 02:08:42 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-30 02:17:45 | 组件总数：92 | 漏洞总数：20 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|GNU Libiberty 安全漏洞|输入验证不恰当|[MPS-2017-1331](https://www.oscs1024.com/hd/MPS-2017-1331)|CVE-2016-6131|高危|
|libiberty 数字错误漏洞||[MPS-2017-2066](https://www.oscs1024.com/hd/MPS-2017-2066)|CVE-2016-2226|高危|
|libiberty 安全漏洞|UAF|[MPS-2017-2070](https://www.oscs1024.com/hd/MPS-2017-2070)|CVE-2016-4487|中危|
|libiberty 安全漏洞|UAF|[MPS-2017-2071](https://www.oscs1024.com/hd/MPS-2017-2071)|CVE-2016-4488|中危|
|libiberty 数字错误漏洞|整数溢出或环绕|[MPS-2017-2072](https://www.oscs1024.com/hd/MPS-2017-2072)|CVE-2016-4489|中危|
|libiberty 数字错误漏洞|整数溢出或环绕|[MPS-2017-2073](https://www.oscs1024.com/hd/MPS-2017-2073)|CVE-2016-4490|中危|
|libiberty 安全漏洞|缓冲区溢出|[MPS-2017-2074](https://www.oscs1024.com/hd/MPS-2017-2074)|CVE-2016-4491|中危|
|libiberty 缓冲区错误漏洞|缓冲区溢出|[MPS-2017-2075](https://www.oscs1024.com/hd/MPS-2017-2075)|CVE-2016-4492|中危|
|libiberty 安全漏洞|越界读取|[MPS-2017-2076](https://www.oscs1024.com/hd/MPS-2017-2076)|CVE-2016-4493|中危|
|GNU Binutils 安全漏洞|不可达退出条件的循环（无限循环）|[MPS-2018-14162](https://www.oscs1024.com/hd/MPS-2018-14162)|CVE-2018-18700|中危|
|GNU Binutils GNU libiberty 安全漏洞|拒绝服务|[MPS-2018-8266](https://www.oscs1024.com/hd/MPS-2018-8266)|CVE-2018-12698|高危|
|GNU Binutils 缓冲区错误漏洞|越界读取|[MPS-2019-1889](https://www.oscs1024.com/hd/MPS-2019-1889)|CVE-2019-9070|高危|
|GNU C Library 代码问题漏洞|数据处理错误|[MPS-2019-1956](https://www.oscs1024.com/hd/MPS-2019-1956)|CVE-2009-5155|高危|
|Wasmtime 资源管理错误漏洞|UAF|[MPS-2021-29766](https://www.oscs1024.com/hd/MPS-2021-29766)|CVE-2021-39216|中危|
|Wasmtime 缓冲区错误漏洞||[MPS-2021-29768](https://www.oscs1024.com/hd/MPS-2021-29768)|CVE-2021-39218|中危|
|Wasmtime 代码问题漏洞|使用不兼容类型访问资源（类型混淆）|[MPS-2021-29769](https://www.oscs1024.com/hd/MPS-2021-29769)|CVE-2021-39219|中危|
|GNU libiberty 缓冲区错误漏洞|缓冲区溢出|[MPS-2021-32366](https://www.oscs1024.com/hd/MPS-2021-32366)|CVE-2021-3826|高危|
|Wasmtime 安全漏洞|数值计算不正确|[MPS-2022-11134](https://www.oscs1024.com/hd/MPS-2022-11134)|CVE-2022-31104|中危|
|Wasmtime 缓冲区错误漏洞|使用未经初始化的指针|[MPS-2022-2063](https://www.oscs1024.com/hd/MPS-2022-2063)|CVE-2022-23636|高危|
|Wasmtime 安全漏洞|依赖未定义、未指明或实现定义的行为|[MPS-so3c-5pne](https://www.oscs1024.com/hd/MPS-so3c-5pne)|CVE-2023-30624|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|wasmtime|0.29.0|8.0.1|间接依赖|建议修复|C:0|H:2|M:4|L:0|
|gnulib|20200224||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|libiberty|9.1.0|20220713-1|间接依赖|建议修复|C:0|H:5|M:8|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|26|Low|
|BSD-3-Clause|19|Low|
|Apache-2.0|45|Low|
|GPL-2.0|1|Medium|
|GPL-3.0-or-later|1|Low|
|Unlicense|1|Low|
|LGPL-3.0-or-later|1|Low|
|CC-BY-SA-4.0|1|Medium|
|BSD-2-Clause|3|Low|
|ISC|1|Low|
|LGPL-2.1|1|Medium|
|BSD-2-Clause-Views|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|github.com/fortytw2/leaktest|v1.3.0|直接依赖|go|
|github.com/sergi/go-diff|v1.1.0|间接依赖|go|
|codespell|2.2.4|间接依赖|pip|
|go.uber.org/automaxprocs|v1.5.3|直接依赖|go|
|github.com/containerd/containerd|v1.7.4|直接依赖|go|
|bulma|0.9.3|直接依赖|npm|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|google.golang.org/protobuf|v1.30.0|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/yashtewari/glob-intersection|v0.2.0|直接依赖|go|
|github.com/moby/locker|v1.0.1|间接依赖|go|
|github.com/cenkalti/backoff/v4|v4.2.1|间接依赖|go|
|github.com/cespare/xxhash|v1.1.0|间接依赖|go|
|github.com/spf13/cobra|v1.7.0|直接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|直接依赖|go|
|golang.org/x/time|v0.3.0|直接依赖|go|
|github.com/xeipuuv/gojsonpointer|v0.0.0-20190905194746-02993c407bfb|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|github.com/peterh/liner|v1.2.2|直接依赖|go|
|github.com/prometheus/client_golang|v1.16.0|直接依赖|go|
|oras.land/oras-go/v2|v2.2.1|直接依赖|go|
|golang.org/x/net|v0.14.0|直接依赖|go|
|gnulib|20200224|间接依赖||
|github.com/felixge/httpsnoop|v1.0.3|间接依赖|go|
|go.opentelemetry.io/otel/sdk|v1.16.0|直接依赖|go|
|github.com/dgraph-io/badger/v3|v3.2103.5|直接依赖|go|
|github.com/golang/glog|v1.1.0|间接依赖|go|
|github.com/tchap/go-patricia/v2|v2.3.1|直接依赖|go|
|github.com/prometheus/common|v0.42.0|间接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway/v2|v2.7.0|间接依赖|go|
|github.com/kr/text|v0.2.0|间接依赖|go|
|google.golang.org/grpc|v1.57.0|直接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0|直接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace/otlptracegrpc|v1.16.0|直接依赖|go|
|wasmtime|0.29.0|间接依赖||
|github.com/dustin/go-humanize|v1.0.0|间接依赖|go|
|golang.org/x/sync|v0.3.0|间接依赖|go|
|github.com/go-logr/logr|v1.2.4|直接依赖|go|
|github.com/bytecodealliance/wasmtime-go/v3|v3.0.2|直接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|github.com/mattn/go-runewidth|v0.0.9|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/internal/retry|v1.16.0|间接依赖|go|
|github.com/prometheus/procfs|v0.10.1|间接依赖|go|
|github.com/ghodss/yaml|v1.0.0|直接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/net/http/otelhttp|v0.42.0|直接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/opencontainers/image-spec|v1.1.0-rc4|直接依赖|go|
|gopkg.in/check.v1|v1.0.0-20201130134442-10cb98267c6c|直接依赖|go|
|github.com/agnivade/levenshtein|v1.1.1|直接依赖|go|
|github.com/klauspost/compress|v1.16.0|间接依赖|go|
|github.com/sirupsen/logrus|v1.9.3|直接依赖|go|
|go.opentelemetry.io/otel/trace|v1.16.0|直接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|github.com/foxcpp/go-mockdns|v1.0.0|直接依赖|go|
|golang.org/x/text|v0.12.0|间接依赖|go|
|github.com/olekukonko/tablewriter|v0.0.5|直接依赖|go|
|github.com/russross/blackfriday/v2|v2.1.0|间接依赖|go|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|github.com/rogpeppe/go-internal|v1.9.0|间接依赖|go|
|github.com/google/flatbuffers|v1.12.1|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|go.opentelemetry.io/otel/exporters/otlp/otlptrace|v1.16.0|直接依赖|go|
|go.opentelemetry.io/otel/metric|v1.16.0|间接依赖|go|
|github.com/gobwas/glob|v0.2.3|直接依赖|go|
|golang.org/x/sys|v0.11.0|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|go.opentelemetry.io/otel|v1.16.0|直接依赖|go|
|google.golang.org/genproto/googleapis/api|v0.0.0-20230525234035-dd9d682886f9|间接依赖|go|
|github.com/gorilla/mux|v1.8.0|直接依赖|go|
|github.com/dgryski/go-farm|v0.0.0-20200201041132-a6ae2369ad13|间接依赖|go|
|github.com/dgraph-io/ristretto|v0.1.1|间接依赖|go|
|libiberty|9.1.0|间接依赖||
|github.com/kr/pretty|v0.3.1|间接依赖|go|
|github.com/cpuguy83/go-md2man/v2|v2.0.2|间接依赖|go|
|github.com/golang/protobuf|v1.5.3|直接依赖|go|
|github.com/rcrowley/go-metrics|v0.0.0-20200313005456-10cdbea86bc0|直接依赖|go|
|go.opencensus.io|v0.24.0|间接依赖|go|
|github.com/go-ini/ini|v1.67.0|直接依赖|go|
|github.com/golang/snappy|v0.0.4|间接依赖|go|
|go.opentelemetry.io/proto/otlp|v0.19.0|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230526161137-0005af68ea54|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|直接依赖|go|
|github.com/andreyvit/diff|v0.0.0-20170406064948-c7f18ee00883|直接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230525234030-28d5490b6b19|间接依赖|go|
|github.com/prometheus/client_model|v0.3.0|间接依赖|go|
|github.com/miekg/dns|v1.1.43|间接依赖|go|
|github.com/AdaLogics/go-fuzz-headers|v0.0.0-20230811130428-ced1acdcaa24|间接依赖|go|
|github.com/OneOfOne/xxhash|v1.2.8|直接依赖|go|
|github.com/xeipuuv/gojsonreference|v0.0.0-20180127040603-bd5ef7bd5415|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)