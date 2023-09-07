# elastic/beats安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699848702944477184.svg)](https://www.murphysec.com/console/report/1699848702801870848/1699848702944477184)

仓库描述：:tropical_fish: Beats - Lightweight shippers for Elasticsearch & Logstash 

仓库地址：[https://github.com/elastic/beats](https://github.com/elastic/beats)

| star：11790 | watch：673 | fork：4802 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-08 00:57:50 | 许可证：NOASSERTION |
| 最近检测时间：2023-09-08 02:23:18 | 组件总数：447 | 漏洞总数：7 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Python 资源管理错误漏洞||[MPS-2020-15181](https://www.oscs1024.com/hd/MPS-2020-15181)|CVE-2020-14422|中危|
|Python 输入验证错误漏洞|输入验证不恰当|[MPS-2021-6340](https://www.oscs1024.com/hd/MPS-2021-6340)|CVE-2021-29921|严重|
|ipaddress 存在密码算法不安全漏洞|密码算法不安全|[MPS-2022-14951](https://www.oscs1024.com/hd/MPS-2022-14951)||中危|
|Certifi 存在数据真实性验证不充分漏洞|对数据真实性的验证不充分|[MPS-2022-1918](https://www.oscs1024.com/hd/MPS-2022-1918)|CVE-2022-23491|中危|
|redis-py 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2023-8854](https://www.oscs1024.com/hd/MPS-2023-8854)|CVE-2023-28858|中危|
|redis-py 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2023-8855](https://www.oscs1024.com/hd/MPS-2023-8855)|CVE-2023-28859|中危|
|Certifi 数据伪造问题漏洞|对数据真实性的验证不充分|[MPS-ck78-r6zg](https://www.oscs1024.com/hd/MPS-ck78-r6zg)|CVE-2023-37920|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|ipaddress|1.0.19||间接依赖|建议修复|C:1|H:0|M:2|L:0|
|certifi|2022.12.7|2023.7.22|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|redis|4.4.4|4.5.3|间接依赖|可选修复|C:0|H:0|M:2|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|190|Low|
|MIT|136|Low|
|BSD-2-Clause|12|Low|
|BSD-3-Clause|65|Low|
|自定义许可证|15|Low|
|MPL-2.0|13|Low|
|UPL-1.0|1|Low|
|GPL-2.0|2|Medium|
|ISC|3|Low|
|BSD-2-Clause-Views|2|Low|
|CC-BY-SA-4.0|2|Medium|
|MIT-0|1|Low|
|BSL-1.0|1|Low|
|NCSA|1|Low|
|CC-BY-3.0|1|Low|
|HPND|1|Low|
|Zlib|1|Low|
|OpenSSL|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/aws/aws-sdk-go-v2/internal/v4a|v1.0.14|间接依赖|go|
|github.com/prometheus/client_model|v0.2.0|直接依赖|go|
|pytest-timeout|1.4.2|间接依赖|pip|
|github.com/golang-jwt/jwt/v4|v4.5.0|间接依赖|go|
|pyasn1|0.4.8|间接依赖|pip|
|github.com/goccy/go-json|v0.10.2|间接依赖|go|
|github.com/google/gopacket|v1.1.19|直接依赖|go|
|github.com/Azure/azure-sdk-for-go|v59.0.0+incompatible|直接依赖|go|
|github.com/jcmturner/aescts/v2|v2.0.0|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|github.com/googleapis/gnostic|v0.5.5|间接依赖|go|
|github.com/opencontainers/image-spec|v1.0.2|间接依赖|go|
|github.com/digitalocean/go-libvirt|v0.0.0-20180301200012-6075ea3c39a1|直接依赖|go|
|github.com/yusufpapurcu/wmi|v1.2.2|间接依赖|go|
|pluggy|0.13.1|间接依赖|pip|
|github.com/mitchellh/iochan|v1.0.0|间接依赖|go|
|elasticsearch|7.1.0|间接依赖|pip|
|base||间接依赖|pip|
|PyYAML|5.3.1|间接依赖|pip|
|go.elastic.co/apm/module/apmelasticsearch/v2|v2.4.4|直接依赖|go|
|pyrsistent|0.16.0|间接依赖|pip|
|github.com/fatih/color|v1.13.0|直接依赖|go|
|packetbeat||间接依赖|pip|
|jmespath|0.9.5|间接依赖|pip|
|github.com/vmware/govmomi|v0.0.0-20170802214208-2cad15190b41|直接依赖|go|
|github.com/shopspring/decimal|v1.3.1|间接依赖|go|
|github.com/insomniacslk/dhcp|v0.0.0-20220119180841-3c283ff8b7dd|直接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|直接依赖|go|
|github.com/akavel/rsrc|v0.8.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/presigned-url|v1.9.17|间接依赖|go|
|github.com/mitchellh/hashstructure|v1.1.0|直接依赖|go|
|github.com/prometheus/client_golang|v1.11.1|间接依赖|go|
|github.com/pierrec/lz4/v4|v4.1.16|直接依赖|go|
|github.com/moby/spdystream|v0.2.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/kinesis|v1.15.8|直接依赖|go|
|github.com/joeshaw/multierror|v0.0.0-20140124173710-69b34d4ec901|直接依赖|go|
|golang.org/x/term|v0.11.0|间接依赖|go|
|github.com/fsnotify/fsevents|v0.1.1|直接依赖|go|
|github.com/lestrrat-go/blackmagic|v1.0.1|间接依赖|go|
|github.com/minio/c2goasm|v0.0.0-20190812172519-36a3d3bbc4f3|间接依赖|go|
|github.com/jcmturner/rpc/v2|v2.0.3|间接依赖|go|
|github.com/lestrrat-go/httpcc|v1.0.1|间接依赖|go|
|github.com/andrewkroh/sys|v0.0.0-20151128191922-287798fe3e43|直接依赖|go|
|github.com/ugorji/go/codec|v1.1.8|直接依赖|go|
|github.com/elastic/elastic-agent-libs|v0.3.13|直接依赖|go|
|github.com/bsm/sarama-cluster|v2.1.14-0.20180625083203-7e67d87a6b3f+incompatible|直接依赖|go|
|toml|0.10.1|间接依赖|pip|
|github.com/tklauser/go-sysconf|v0.3.10|间接依赖|go|
|golang.org/x/xerrors|v0.0.0-20220907171357-04be3eba64a2|间接依赖|go|
|github.com/hashicorp/go-multierror|v1.1.1|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/elasticloadbalancingv2|v1.18.4|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sts|v1.16.19|直接依赖|go|
|github.com/google/licenseclassifier|v0.0.0-20221004142553-c1ed8fcf4bab|间接依赖|go|
|github.com/lestrrat-go/httprc|v1.0.4|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|golang.org/x/sync|v0.1.0|直接依赖|go|
|websocket-client|0.47.0|间接依赖|pip|
|filebeat||间接依赖|pip|
|copytree||间接依赖|pip|
|github.com/aws/aws-sdk-go|v1.38.60|间接依赖|go|
|github.com/karrick/godirwalk|v1.17.0|间接依赖|go|
|python-dateutil|2.8.1|间接依赖|pip|
|github.com/kballard/go-shellquote|v0.0.0-20180428030007-95032a82bc51|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/costexplorer|v1.18.4|直接依赖|go|
|opentelemetry-exporter-otlp|1.11.0|间接依赖|pip|
|github.com/Azure/azure-sdk-for-go/sdk/resourcemanager/consumption/armconsumption|v1.0.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/s3shared|v1.13.17|间接依赖|go|
|golang.org/x/oauth2|v0.7.0|直接依赖|go|
|github.com/samuel/go-parser|v0.0.0-20130731160455-ca8abbf65d0e|间接依赖|go|
|github.com/klauspost/asmfmt|v1.3.2|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/go-test/deep|v1.0.7|直接依赖|go|
|github.com/mattn/go-runewidth|v0.0.9|间接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|github.com/Azure/go-autorest/autorest/to|v0.4.0|间接依赖|go|
|github.com/armon/go-radix|v1.0.0|间接依赖|go|
|texttable|0.9.1|间接依赖|pip|
|gopkg.in/jcmturner/goidentity.v3|v3.0.0|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.17|间接依赖|go|
|idna|2.6|间接依赖|pip|
|github.com/sanathkr/go-yaml|v0.0.0-20170819195128-ed9d249f429b|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ec2|v1.36.1|直接依赖|go|
|github.com/PaesslerAG/jsonpath|v0.1.1|直接依赖|go|
|github.com/prometheus/common|v0.30.0|直接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|间接依赖|go|
|github.com/fearful-symmetry/gomsr|v0.0.1|间接依赖|go|
|golang.org/x/time|v0.3.0|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/resourcemanager/resources/armresources|v1.0.0|直接依赖|go|
|github.com/cavaliercoder/badio|v0.0.0-20160213150051-ce5280129e9e|间接依赖|go|
|github.com/golang-sql/civil|v0.0.0-20190719163853-cb61b32ac6fe|间接依赖|go|
|github.com/Azure/go-amqp|v0.16.0|间接依赖|go|
|mvdan.cc/garble|v0.7.1|间接依赖|go|
|github.com/form3tech-oss/jwt-go|v3.2.5+incompatible|间接依赖|go|
|github.com/go-ole/go-ole|v1.2.6|间接依赖|go|
|github.com/sirupsen/logrus|v1.9.0|间接依赖|go|
|github.com/cyphar/filepath-securejoin|v0.2.3|间接依赖|go|
|chardet|3.0.4|间接依赖|pip|
|github.com/godror/godror|v0.33.2|直接依赖|go|
|code.cloudfoundry.org/gofileutils|v0.0.0-20170111115228-4d0c80011a0f|间接依赖|go|
|github.com/morikuni/aec|v1.0.0|间接依赖|go|
|github.com/cloudfoundry-community/go-cfclient|v0.0.0-20190808214049-35bcce23fc5f|直接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|cloud.google.com/go/bigquery|v1.44.0|直接依赖|go|
|github.com/miekg/dns|v1.1.42|直接依赖|go|
|github.com/sergi/go-diff|v1.3.1|间接依赖|go|
|github.com/stretchr/testify|v1.8.4|直接依赖|go|
|github.com/lestrrat-go/jwx/v2|v2.0.11|直接依赖|go|
|github.com/yuin/gopher-lua|v0.0.0-20170403160031-b402f3114ec7|间接依赖|go|
|github.com/elastic/elastic-agent-client/v7|v7.3.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sqs|v1.18.4|直接依赖|go|
|github.com/markbates/pkger|v0.17.1|间接依赖|go|
|github.com/golang-sql/sqlexp|v0.1.0|间接依赖|go|
|github.com/docker/go-units|v0.5.0|直接依赖|go|
|github.com/pierrre/gotestcover|v0.0.0-20160517101806-924dca7d15f0|直接依赖|go|
|github.com/minio/asm2plan9s|v0.0.0-20200509001527-cdd76441f9d8|间接依赖|go|
|github.com/armon/go-socks5|v0.0.0-20160902184237-e75332964ef5|直接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|pytest-rerunfailures|9.1.1|间接依赖|pip|
|heartbeat||间接依赖|pip|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|github.com/pkg/browser|v0.0.0-20210911075715-681adbf594b8|间接依赖|go|
|github.com/elastic/go-sysinfo|v1.11.1|直接依赖|go|
|github.com/cavaliercoder/go-rpm|v0.0.0-20190131055624-7a9c54e3d83e|直接依赖|go|
|github.com/dlclark/regexp2|v1.4.0|间接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.0|直接依赖|go|
|k8s.io/api|v0.23.4|直接依赖|go|
|github.com/youmark/pkcs8|v0.0.0-20201027041543-1326539a0a0a|间接依赖|go|
|github.com/gorilla/handlers|v1.5.1|直接依赖|go|
|github.com/dgraph-io/ristretto|v0.1.0|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|直接依赖|go|
|github.com/tklauser/numcpus|v0.4.0|间接依赖|go|
|github.com/hashicorp/nomad/api|v0.0.0-20201203164818-6318a8ac7bf8|直接依赖|go|
|cached-property|1.4.2|间接依赖|pip|
|github.com/dop251/goja_nodejs|v0.0.0-20171011081505-adff31b136e6|直接依赖|go|
|github.com/elastic/gosigar|v0.14.2|直接依赖|go|
|github.com/dnephin/pflag|v1.0.7|间接依赖|go|
|github.com/go-sourcemap/sourcemap|v2.1.2+incompatible|间接依赖|go|
|packaging|20.4|间接依赖|pip|
|github.com/aws/aws-sdk-go-v2/feature/s3/manager|v1.11.33|直接依赖|go|
|golang.org/x/exp|v0.0.0-20220921023135-46d9e7742f1e|间接依赖|go|
|github.com/google/uuid|v1.3.0|直接依赖|go|
|github.com/Azure/azure-storage-blob-go|v0.8.0|直接依赖|go|
|docker-pycreds|0.4.0|间接依赖|pip|
|TestCase||间接依赖|pip|
|github.com/aws/aws-sdk-go-v2/service/s3|v1.27.11|直接依赖|go|
|github.com/blakesmith/ar|v0.0.0-20150311145944-8bd4349a67f2|直接依赖|go|
|github.com/xdg/stringprep|v1.0.3|间接依赖|go|
|github.com/hashicorp/golang-lru|v0.5.4|直接依赖|go|
|github.com/go-logfmt/logfmt|v0.5.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/resourcegroupstaggingapi|v1.13.5|直接依赖|go|
|more-itertools|8.4.0|间接依赖|pip|
|cloud.google.com/go/iam|v0.8.0|间接依赖|go|
|github.com/hashicorp/go-rootcerts|v1.0.2|间接依赖|go|
|code.cloudfoundry.org/go-loggregator|v7.4.0+incompatible|直接依赖|go|
|github.com/prometheus/procfs|v0.9.0|直接依赖|go|
|cloud.google.com/go/compute/metadata|v0.2.3|间接依赖|go|
|kernel.org/pub/linux/libs/security/libcap/cap|v1.2.57|直接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/Azure/azure-event-hubs-go/v3|v3.3.15|直接依赖|go|
|google.golang.org/protobuf|v1.29.1|直接依赖|go|
|gopkg.in/jcmturner/aescts.v1|v1.0.1|间接依赖|go|
|github.com/lestrrat-go/iter|v1.0.2|间接依赖|go|
|pycodestyle|2.6.0|间接依赖|pip|
|jsonschema|3.2.0|间接依赖|pip|
|github.com/Masterminds/semver|v1.5.0|间接依赖|go|
|github.com/zeebo/xxh3|v1.0.2|间接依赖|go|
|six|1.15.0|间接依赖|pip|
|github.com/google/shlex|v0.0.0-20191202100458-e7afc7fbc510|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/cloudwatch|v1.26.0|直接依赖|go|
|go.elastic.co/fastjson|v1.1.0|间接依赖|go|
|github.com/hashicorp/errwrap|v1.1.0|间接依赖|go|
|github.com/googleapis/enterprise-certificate-proxy|v0.2.0|间接依赖|go|
|github.com/jonboulle/clockwork|v0.2.2|直接依赖|go|
|github.com/klauspost/compress|v1.16.5|间接依赖|go|
|github.com/elastic/toutoumomoma|v0.0.0-20221026030040-594ef30cb640|直接依赖|go|
|github.com/golang/protobuf|v1.5.2|直接依赖|go|
|github.com/klauspost/cpuid/v2|v2.0.9|间接依赖|go|
|golang.org/x/tools|v0.6.0|直接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.2-0.20181231171920-c182affec369|间接依赖|go|
|github.com/aerospike/aerospike-client-go|v1.27.1-0.20170612174108-0f3b54da6bdc|直接依赖|go|
|github.com/tsg/go-daemon|v0.0.0-20200207173439-e704b93fd89b|直接依赖|go|
|github.com/containerd/fifo|v1.0.0|直接依赖|go|
|termcolor|1.1.0|间接依赖|pip|
|setuptools|65.5.1|间接依赖|pip|
|github.com/Azure/azure-sdk-for-go/sdk/internal|v1.2.0|间接依赖|go|
|github.com/xdg-go/stringprep|v1.0.2|间接依赖|go|
|github.com/hashicorp/go-uuid|v1.0.2|间接依赖|go|
|aqwari.net/xml|v0.0.0-20210331023308-d9421b293817|间接依赖|go|
|github.com/stoewer/go-strcase|v1.2.0|间接依赖|go|
|github.com/hectane/go-acl|v0.0.0-20190604041725-da78bae5fc95|直接依赖|go|
|semver|2.8.1|间接依赖|pip|
|github.com/go-stack/stack|v1.8.0|间接依赖|go|
|pyparsing|2.4.7|间接依赖|pip|
|github.com/mattn/go-colorable|v0.1.12|直接依赖|go|
|go.uber.org/atomic|v1.10.0|直接依赖|go|
|github.com/godbus/dbus/v5|v5.0.6|直接依赖|go|
|io.dropwizard.metrics:metrics-servlets||直接依赖|maven|
|copyfile||间接依赖|pip|
|sigs.k8s.io/json|v0.0.0-20211020170558-c049b76a60c6|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/azcore|v1.4.0|直接依赖|go|
|github.com/docker/docker|v23.0.3+incompatible|直接依赖|go|
|cloud.google.com/go/longrunning|v0.3.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/accept-encoding|v1.9.9|间接依赖|go|
|iniconfig|1.0.1|间接依赖|pip|
|go.elastic.co/ecszap|v1.0.1|直接依赖|go|
|github.com/eapache/go-resiliency|v1.2.0|直接依赖|go|
|enum34|1.1.6|间接依赖|pip|
|github.com/sanathkr/yaml|v1.0.1-0.20170819201035-0056894fa522|间接依赖|go|
|go.elastic.co/apm/module/apmhttp/v2|v2.4.4|直接依赖|go|
|howett.net/plist|v1.0.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/config|v1.17.7|直接依赖|go|
|k8s.io/utils|v0.0.0-20211116205334-6203023598ed|间接依赖|go|
|github.com/Azure/go-ansiterm|v0.0.0-20210617225240-d185dfc1b5a1|间接依赖|go|
|kernel.org/pub/linux/libs/security/libcap/psx|v1.2.57|间接依赖|go|
|k8s.io/klog/v2|v2.30.0|间接依赖|go|
|github.com/googleapis/gax-go/v2|v2.7.0|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/azidentity|v1.2.2|直接依赖|go|
|github.com/elastic/go-elasticsearch/v8|v8.9.0|直接依赖|go|
|gopkg.in/jcmturner/dnsutils.v1|v1.0.1|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/iam|v1.18.4|直接依赖|go|
|github.com/go-logr/logr|v1.2.3|间接依赖|go|
|github.com/xdg-go/pbkdf2|v1.0.0|间接依赖|go|
|google.golang.org/api|v0.103.0|直接依赖|go|
|github.com/PaesslerAG/gval|v1.2.2|直接依赖|go|
|github.com/elastic/go-lookslike|v0.3.0|直接依赖|go|
|colorama|0.4.3|间接依赖|pip|
|github.com/Shopify/sarama|v1.27.0|直接依赖|go|
|github.com/jcmturner/gofork|v1.0.0|间接依赖|go|
|github.com/cespare/xxhash|v1.1.0|间接依赖|go|
|github.com/google/gofuzz|v1.2.0|间接依赖|go|
|code.cloudfoundry.org/go-diodes|v0.0.0-20190809170250-f77fb823c7ee|间接依赖|go|
|ipaddress|1.0.19|间接依赖|pip|
|github.com/aws/aws-sdk-go-v2/internal/endpoints/v2|v2.4.27|间接依赖|go|
|github.com/StackExchange/wmi|v1.2.1|直接依赖|go|
|github.com/h2non/filetype|v1.1.1|直接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/storage/azblob|v1.0.0|直接依赖|go|
|github.com/golang/snappy|v0.0.4|直接依赖|go|
|awscli|1.18.48|间接依赖|pip|
|github.com/Azure/go-autorest|v14.2.0+incompatible|间接依赖|go|
|github.com/docker/go-plugins-helpers|v0.0.0-20181025120712-1e6269c305b8|直接依赖|go|
|functionbeat||间接依赖|pip|
|github.com/google/flatbuffers|v23.3.3+incompatible|直接依赖|go|
|requests|2.31.0|间接依赖|pip|
|github.com/docker/go-connections|v0.4.0|直接依赖|go|
|github.com/devigned/tab|v0.1.2-0.20190607222403-0c15cf42f9a2|间接依赖|go|
|github.com/gorilla/mux|v1.8.0|直接依赖|go|
|github.com/denisenkom/go-mssqldb|v0.12.3|直接依赖|go|
|go.opencensus.io|v0.24.0|间接依赖|go|
|github.com/cloudfoundry/sonde-go|v0.0.0-20171206171820-b33733203bb4|直接依赖|go|
|botocore|1.15.48|间接依赖|pip|
|github.com/lib/pq|v1.10.3|直接依赖|go|
|github.com/fsnotify/fsnotify|v1.5.1|直接依赖|go|
|github.com/foxcpp/go-mockdns|v0.0.0-20201212160233-ede2f9158d15|直接依赖|go|
|KERNEL32.dll||间接依赖||
|github.com/golang/mock|v1.6.0|直接依赖|go|
|github.com/hashicorp/go-cleanhttp|v0.5.2|间接依赖|go|
|github.com/gofrs/flock|v0.8.1|直接依赖|go|
|github.com/elastic/go-concert|v0.2.0|直接依赖|go|
|Jinja2|2.11.3|间接依赖|pip|
|jsondiff|1.1.2|间接依赖|pip|
|github.com/coreos/go-systemd/v22|v22.3.2|直接依赖|go|
|github.com/pkg/xattr|v0.4.9|直接依赖|go|
|docker|4.1.0|间接依赖|pip|
|golang.org/x/lint|v0.0.0-20210508222113-6edffad5e616|直接依赖|go|
|github.com/Azure/go-autorest/tracing|v0.6.0|间接依赖|go|
|github.com/elastic/go-lumber|v0.1.2-0.20220819171948-335fde24ea0f|直接依赖|go|
|github.com/shirou/gopsutil|v3.21.11+incompatible|间接依赖|go|
|github.com/lestrrat-go/option|v1.0.1|间接依赖|go|
|github.com/Azure/go-autorest/autorest|v0.11.19|直接依赖|go|
|opentelemetry-sdk|1.11.0|间接依赖|pip|
|github.com/stretchr/objx|v0.5.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/credentials|v1.12.20|直接依赖|go|
|github.com/olekukonko/tablewriter|v0.0.5|直接依赖|go|
|redis|4.4.4|间接依赖|pip|
|github.com/elastic/go-ucfg|v0.8.6|直接依赖|go|
|github.com/evanphx/json-patch|v4.12.0+incompatible|间接依赖|go|
|github.com/jmoiron/sqlx|v1.3.1|直接依赖|go|
|github.com/urso/diag|v0.0.0-20200210123136-21b3cc8eb797|间接依赖|go|
|backports.ssl-match-hostname|3.5.0.1|间接依赖|pip|
|gopkg.in/jcmturner/rpc.v1|v1.1.0|间接依赖|go|
|github.com/jarcoal/httpmock|v1.0.4|直接依赖|go|
|docutils|0.15.2|间接依赖|pip|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|github.com/eapache/go-xerial-snappy|v0.0.0-20180814174437-776d5712da21|间接依赖|go|
|github.com/Azure/go-autorest/logger|v0.2.1|间接依赖|go|
|k8s.io/client-go|v0.23.4|直接依赖|go|
|google.golang.org/grpc|v1.53.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/cloudformation|v1.20.4|直接依赖|go|
|parameterized|0.7.0|间接依赖|pip|
|github.com/elastic/elastic-agent-autodiscover|v0.6.2|直接依赖|go|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|github.com/shirou/gopsutil/v3|v3.22.10|直接依赖|go|
|github.com/awslabs/kinesis-aggregation/go/v2|v2.0.0-20220623125934-28468a6701b5|直接依赖|go|
|github.com/Azure/go-autorest/autorest/adal|v0.9.14|直接依赖|go|
|github.com/apoydence/eachers|v0.0.0-20181020210610-23942921fe77|间接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0|间接依赖|go|
|XPackTest||间接依赖|pip|
|github.com/cespare/xxhash/v2|v2.2.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/configsources|v1.1.33|间接依赖|go|
|github.com/aws/aws-lambda-go|v1.13.3|直接依赖|go|
|github.com/jpillora/backoff|v1.0.0|间接依赖|go|
|github.com/imdario/mergo|v0.3.12|间接依赖|go|
|dockerpty|0.4.1|间接依赖|pip|
|sigs.k8s.io/yaml|v1.2.0|间接依赖|go|
|six|1.14.0|间接依赖|pip|
|github.com/gorhill/cronexpr|v0.0.0-20180427100037-88b0669f7d75|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ssooidc|v1.13.5|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/magefile/mage|v1.15.0|直接依赖|go|
|elasticsearch||间接依赖|pip|
|gotest.tools/gotestsum|v1.7.0|直接依赖|go|
|github.com/apache/arrow/go/v12|v12.0.1-0.20230605094802-c153c6d36ccf|直接依赖|go|
|opentelemetry-api|1.11.0|间接依赖|pip|
|github.com/eapache/queue|v1.1.0|间接依赖|go|
|golang.org/x/net|v0.10.0|直接依赖|go|
|Elasticsearch||间接依赖|pip|
|github.com/dgraph-io/badger/v3|v3.2103.1|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/checksum|v1.1.18|间接依赖|go|
|github.com/lufia/plan9stats|v0.0.0-20211012122336-39d0f177ccd0|间接依赖|go|
|github.com/hashicorp/go-version|v1.2.0|间接依赖|go|
|go.mongodb.org/mongo-driver|v1.5.1|直接依赖|go|
|gopkg.in/natefinch/lumberjack.v2|v2.0.0|直接依赖|go|
|github.com/antlr/antlr4/runtime/Go/antlr/v4|v4.0.0-20230305170008-8188dc5388df|间接依赖|go|
|github.com/xdg/scram|v1.0.3|直接依赖|go|
|github.com/felixge/httpsnoop|v1.0.1|间接依赖|go|
|github.com/jcmturner/dnsutils/v2|v2.0.0|间接依赖|go|
|github.com/elastic/go-structform|v0.0.10|直接依赖|go|
|golang.org/x/sys|v0.11.0|直接依赖|go|
|cloud.google.com/go/compute|v1.15.1|直接依赖|go|
|github.com/dolmen-go/contextio|v0.0.0-20200217195037-68fc5150bcd5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/organizations|v1.15.2|直接依赖|go|
|metricbeat||间接依赖|pip|
|go.elastic.co/apm/v2|v2.4.4|直接依赖|go|
|github.com/andybalholm/brotli|v1.0.5|间接依赖|go|
|stomp.py|4.1.22|间接依赖|pip|
|github.com/fearful-symmetry/gorapl|v0.0.4|直接依赖|go|
|github.com/Azure/azure-amqp-common-go/v3|v3.2.1|间接依赖|go|
|github.com/josephspurrier/goversioninfo|v0.0.0-20190209210621-63e6d1acd3dd|直接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20211115234752-e816edb12b65|间接依赖|go|
|github.com/aws/smithy-go|v1.13.5|直接依赖|go|
|github.com/mailru/easyjson|v0.7.6|间接依赖|go|
|gopkg.in/jcmturner/gokrb5.v7|v7.5.0|直接依赖|go|
|elasticsearch|7.8.1|间接依赖|pip|
|github.com/gorilla/websocket|v1.4.2|间接依赖|go|
|github.com/gomodule/redigo|v1.8.3|直接依赖|go|
|deepdiff|4.2.0|间接依赖|pip|
|github.com/gobuffalo/here|v0.6.7|间接依赖|go|
|cloud.google.com/go/redis|v1.10.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2|v1.18.0|直接依赖|go|
|github.com/gofrs/uuid|v4.4.0+incompatible|直接依赖|go|
|github.com/mitchellh/gox|v1.0.1|直接依赖|go|
|golang.org/x/crypto|v0.12.0|直接依赖|go|
|github.com/segmentio/asm|v1.2.0|间接依赖|go|
|github.com/docker/distribution|v2.8.2+incompatible|间接依赖|go|
|github.com/decred/dcrd/dcrec/secp256k1/v4|v4.2.0|间接依赖|go|
|importlib-metadata|1.7.0|间接依赖|pip|
|github.com/godror/knownpb|v0.1.0|间接依赖|go|
|py|1.11.0|间接依赖|pip|
|github.com/jcmturner/gokrb5/v8|v8.4.2|间接依赖|go|
|packet.dll||间接依赖||
|REGEXP_TYPE||间接依赖|pip|
|attrs|19.3.0|间接依赖|pip|
|autopep8|1.5.4|间接依赖|pip|
|cloud.google.com/go/pubsub|v1.27.1|直接依赖|go|
|cloud.google.com/go|v0.107.0|直接依赖|go|
|MarkupSafe|1.1.1|间接依赖|pip|
|github.com/elastic/go-windows|v1.0.1|间接依赖|go|
|github.com/gocarina/gocsv|v0.0.0-20170324095351-ffef3ffc77be|直接依赖|go|
|github.com/AzureAD/microsoft-authentication-library-for-go|v0.9.0|间接依赖|go|
|docker-compose|1.29.2|间接依赖|pip|
|github.com/aws/aws-sdk-go-v2/aws/protocol/eventstream|v1.4.8|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/rds|v1.20.1|直接依赖|go|
|github.com/davecgh/go-xdr|v0.0.0-20161123171359-e6a2ba005892|间接依赖|go|
|ordered-set|3.1.1|间接依赖|pip|
|github.com/aws/aws-sdk-go-v2/internal/ini|v1.3.24|间接依赖|go|
|cloud.google.com/go/monitoring|v1.9.0|直接依赖|go|
|kafka-python|1.4.3|间接依赖|pip|
|golang.org/x/mod|v0.9.0|直接依赖|go|
|github.com/apache/thrift|v0.18.1|间接依赖|go|
|github.com/elastic/elastic-agent-shipper-client|v0.5.1-0.20230228231646-f04347b666f3|直接依赖|go|
|github.com/dustin/go-humanize|v1.0.1|直接依赖|go|
|github.com/Azure/go-autorest/autorest/validation|v0.3.1|间接依赖|go|
|pytest|7.3.2|间接依赖|pip|
|github.com/elastic/elastic-agent-system-metrics|v0.6.1|直接依赖|go|
|go.etcd.io/bbolt|v1.3.6|直接依赖|go|
|go.uber.org/multierr|v1.10.0|直接依赖|go|
|github.com/rcrowley/go-metrics|v0.0.0-20201227073835-cf1acfcdf475|直接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|docopt|0.6.2|间接依赖|pip|
|github.com/aws/aws-sdk-go-v2/feature/ec2/imds|v1.12.17|直接依赖|go|
|github.com/samuel/go-thrift|v0.0.0-20140522043831-2187045faa54|直接依赖|go|
|github.com/go-sql-driver/mysql|v1.6.0|直接依赖|go|
|github.com/hashicorp/go-retryablehttp|v0.6.6|直接依赖|go|
|github.com/eclipse/paho.mqtt.golang|v1.3.5|直接依赖|go|
|github.com/cloudfoundry/noaa|v2.1.0+incompatible|直接依赖|go|
|github.com/osquery/osquery-go|v0.0.0-20220706183148-4e1f83012b42|直接依赖|go|
|github.com/google/cel-go|v0.15.3|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sso|v1.11.23|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/resourcemanager/costmanagement/armcostmanagement|v1.0.0|直接依赖|go|
|github.com/docker/go-metrics|v0.0.1|间接依赖|go|
|github.com/power-devops/perfstat|v0.0.0-20210106213030-5aafc221ea8c|间接依赖|go|
|gopkg.in/inf.v0|v0.9.1|直接依赖|go|
|github.com/kylelemons/godebug|v1.1.0|间接依赖|go|
|k8s.io/apimachinery|v0.23.4|直接依赖|go|
|github.com/otiai10/copy|v1.12.0|直接依赖|go|
|certifi|2022.12.7|间接依赖|pip|
|google.golang.org/genproto|v0.0.0-20230110181048-76db0878b65f|直接依赖|go|
|rsa|4.7.2|间接依赖|pip|
|github.com/elastic/go-perf|v0.0.0-20191212140718-9c656876f595|直接依赖|go|
|github.com/hashicorp/cronexpr|v1.1.0|间接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.1|间接依赖|go|
|github.com/elastic/go-licenser|v0.4.1|直接依赖|go|
|github.com/moby/term|v0.0.0-20221205130635-1aeaba878587|间接依赖|go|
|go.uber.org/zap|v1.24.0|直接依赖|go|
|github.com/elastic/go-seccomp-bpf|v1.3.0|直接依赖|go|
|go.elastic.co/go-licence-detector|v0.6.0|直接依赖|go|
|github.com/dop251/goja|v0.0.0-20200831102558-9af81ddcf0e1|直接依赖|go|
|github.com/elastic/mito|v1.5.0|直接依赖|go|
|github.com/elastic/elastic-transport-go/v8|v8.3.0|间接依赖|go|
|urllib3|1.26.5|间接依赖|pip|
|github.com/spf13/cobra|v1.7.0|直接依赖|go|
|github.com/mattn/go-ieproxy|v0.0.0-20191113090002-7c0f6868bffe|间接依赖|go|
|code.cloudfoundry.org/rfc5424|v0.0.0-20180905210152-236a6d29298a|间接依赖|go|
|cloud.google.com/go/storage|v1.27.0|直接依赖|go|
|github.com/prometheus/prometheus|v1.8.2-0.20210701133801-b0944590a1c9|直接依赖|go|
|github.com/xdg-go/scram|v1.0.2|间接依赖|go|
|github.com/elastic/go-libaudit/v2|v2.3.3|直接依赖|go|
|gotest.tools|v2.2.0+incompatible|直接依赖|go|
|github.com/Azure/azure-pipeline-go|v0.2.1|间接依赖|go|
|github.com/elastic/bayeux|v1.0.5|直接依赖|go|
|wcwidth|0.2.5|间接依赖|pip|
|github.com/awslabs/goformation/v4|v4.1.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/cloudwatchlogs|v1.15.5|直接依赖|go|
|TransportError||间接依赖|pip|
|github.com/rootless-containers/rootlesskit|v1.1.0|间接依赖|go|
|github.com/Azure/azure-sdk-for-go/sdk/resourcemanager/monitor/armmonitor|v0.8.0|直接依赖|go|
|github.com/Azure/go-autorest/autorest/date|v0.3.0|直接依赖|go|
|github.com/JohnCGriffin/overflow|v0.0.0-20211019200055-46fa312c352c|间接依赖|go|
|github.com/pierrec/lz4|v2.6.0+incompatible|间接依赖|go|
|github.com/coreos/pkg|v0.0.0-20180928190104-399ea9e2e55f|直接依赖|go|
|s3transfer|0.3.3|间接依赖|pip|
|github.com/Microsoft/go-winio|v0.6.1|直接依赖|go|
|github.com/urso/sderr|v0.0.0-20210525210834-52b04e8f5c71|直接依赖|go|
|golang.org/x/text|v0.12.0|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)