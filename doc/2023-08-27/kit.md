# go-kit/kit安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695498858820694016.svg)](https://www.murphysec.com/console/report/1691874982614683648/1695498858820694016)

仓库描述：A standard library for microservices.

仓库地址：[https://github.com/go-kit/kit](https://github.com/go-kit/kit)

| star：25334 | watch：685 | fork：2439 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-25 22:21:49 | 许可证：MIT |
| 最近检测时间：2023-08-27 02:10:14 | 组件总数：84 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58307](https://www.oscs1024.com/hd/MPS-2022-58307)|CVE-2022-41723|高危|
|Google Go 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2022-9049](https://www.oscs1024.com/hd/MPS-2022-9049)|CVE-2022-29526|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|golang.org/x/net|v0.0.0-20211216030914-fe4d6282115f|0.7.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|golang.org/x/sys|v0.0.0-20220823224334-20c2bfdbfe24|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|16|Low|
|MIT|27|Low|
|Apache-2.0|32|Low|
|BSD-2-Clause|4|Low|
|MPL-2.0|6|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|golang.org/x/sync|v0.0.0-20210220032951-036812b2e83c|直接依赖|go|
|github.com/golang/protobuf|v1.5.2|间接依赖|go|
|go.uber.org/atomic|v1.9.0|间接依赖|go|
|github.com/hudl/fargo|v1.4.0|直接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/prometheus/client_golang|v1.11.1|直接依赖|go|
|google.golang.org/grpc|v1.40.0|直接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|github.com/minio/highwayhash|v1.0.2|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/rabbitmq/amqp091-go|v1.2.0|直接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|github.com/fatih/color|v1.13.0|间接依赖|go|
|github.com/hashicorp/go-cleanhttp|v0.5.2|间接依赖|go|
|go.uber.org/multierr|v1.7.0|间接依赖|go|
|github.com/casbin/casbin/v2|v2.37.0|直接依赖|go|
|github.com/go-logfmt/logfmt|v0.5.1|间接依赖|go|
|github.com/klauspost/compress|v1.14.4|间接依赖|go|
|github.com/nats-io/nkeys|v0.3.0|间接依赖|go|
|golang.org/x/time|v0.0.0-20211116232009-f0f3c7e86c11|直接依赖|go|
|github.com/nats-io/nats.go|v1.15.0|直接依赖|go|
|github.com/openzipkin/zipkin-go|v0.2.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2|v1.9.1|直接依赖|go|
|github.com/nats-io/nuid|v1.0.1|间接依赖|go|
|github.com/hashicorp/consul/api|v1.14.0|直接依赖|go|
|golang.org/x/crypto|v0.0.0-20220315160706-3147a52a75dd|间接依赖|go|
|github.com/opentracing/opentracing-go|v1.2.0|直接依赖|go|
|github.com/aws/smithy-go|v1.8.0|间接依赖|go|
|github.com/hashicorp/serf|v0.10.0|间接依赖|go|
|github.com/prometheus/common|v0.30.0|间接依赖|go|
|github.com/coreos/go-systemd/v22|v22.3.2|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/cloudwatch|v1.8.1|直接依赖|go|
|go.etcd.io/etcd/api/v3|v3.5.0|间接依赖|go|
|github.com/aws/aws-sdk-go|v1.40.45|直接依赖|go|
|github.com/hashicorp/go-immutable-radix|v1.3.1|间接依赖|go|
|github.com/prometheus/procfs|v0.7.3|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/franela/goreq|v0.0.0-20171204163338-bcd34c9993f8|间接依赖|go|
|go.uber.org/zap|v1.19.1|直接依赖|go|
|golang.org/x/net|v0.0.0-20211216030914-fe4d6282115f|间接依赖|go|
|github.com/edsrzf/mmap-go|v1.0.0|间接依赖|go|
|golang.org/x/sys|v0.0.0-20220823224334-20c2bfdbfe24|间接依赖|go|
|github.com/op/go-logging|v0.0.0-20160315200505-970db520ece7|间接依赖|go|
|github.com/afex/hystrix-go|v0.0.0-20180502004556-fa1af6a1f4f5|直接依赖|go|
|github.com/performancecopilot/speed/v4|v4.0.0|直接依赖|go|
|github.com/sony/gobreaker|v0.4.1|直接依赖|go|
|github.com/prometheus/client_model|v0.2.0|间接依赖|go|
|github.com/nats-io/jwt/v2|v2.2.1-0.20220330180145-442af02fd36a|间接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/armon/go-metrics|v0.4.0|间接依赖|go|
|gopkg.in/gcfg.v1|v1.2.3|间接依赖|go|
|gopkg.in/warnings.v0|v0.1.2|间接依赖|go|
|github.com/go-kit/log|v0.2.0|直接依赖|go|
|github.com/Knetic/govaluate|v3.0.1-0.20171022003610-9aa49832a739+incompatible|间接依赖|go|
|github.com/golang-jwt/jwt/v4|v4.0.0|直接依赖|go|
|github.com/hashicorp/golang-lru|v0.5.4|间接依赖|go|
|go.etcd.io/etcd/client/pkg/v3|v3.5.0|直接依赖|go|
|github.com/influxdata/influxdb1-client|v0.0.0-20200827194710-b269163b24ab|直接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.0|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.16|间接依赖|go|
|github.com/hashicorp/go-rootcerts|v1.0.2|间接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.1|间接依赖|go|
|google.golang.org/protobuf|v1.27.1|直接依赖|go|
|github.com/streadway/handy|v0.0.0-20200128134331-0f66f006fb2e|直接依赖|go|
|golang.org/x/text|v0.3.7|间接依赖|go|
|github.com/sirupsen/logrus|v1.8.1|直接依赖|go|
|go.etcd.io/etcd/client/v2|v2.305.0|直接依赖|go|
|github.com/HdrHistogram/hdrhistogram-go|v1.1.2|间接依赖|go|
|github.com/miekg/dns|v1.1.43|间接依赖|go|
|go.opencensus.io|v0.23.0|直接依赖|go|
|github.com/cenkalti/backoff/v4|v4.1.1|间接依赖|go|
|github.com/go-zookeeper/zk|v1.0.2|直接依赖|go|
|github.com/VividCortex/gohistogram|v1.0.0|直接依赖|go|
|github.com/nats-io/nats-server/v2|v2.8.4|直接依赖|go|
|github.com/hashicorp/go-hclog|v1.2.2|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20210917145530-b395a37504d4|间接依赖|go|
|github.com/coreos/go-semver|v0.3.0|间接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.1.2|间接依赖|go|
|github.com/clbanning/mxj|v1.8.4|间接依赖|go|
|go.etcd.io/etcd/client/v3|v3.5.0|直接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)