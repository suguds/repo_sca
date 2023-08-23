# volcano-sh/volcano安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694412152336375808.svg)](https://www.murphysec.com/console/report/1691513250268467200/1694412152336375808)

仓库描述：A Cloud Native Batch System (Project under CNCF)

仓库地址：[https://github.com/volcano-sh/volcano](https://github.com/volcano-sh/volcano)

| star：3265 | watch：89 | fork：777 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-23 14:42:03 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-24 02:12:44 | 组件总数：96 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Kubernetes 输入验证错误漏洞|访问控制不当|[MPS-2019-15838](https://www.oscs1024.com/hd/MPS-2019-15838)|CVE-2019-11255|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|k8s.io/kubernetes|v1.25.0||直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|52|Low|
|MIT|17|Low|
|BSD-3-Clause|24|Low|
|BSD-2-Clause|1|Low|
|ISC|1|Low|
|CC-BY-SA-4.0|1|Medium|
|MPL-2.0|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/google/gnostic|v0.5.7-v3refs|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|直接依赖|go|
|stathat.com/c/consistent|v1.0.0|直接依赖|go|
|github.com/go-openapi/jsonreference|v0.19.5|间接依赖|go|
|golang.org/x/mod|v0.8.0|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|github.com/agiledragon/gomonkey/v2|v2.2.0|直接依赖|go|
|sigs.k8s.io/controller-runtime|v0.13.0|直接依赖|go|
|github.com/google/go-cmp|v0.5.9|直接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|k8s.io/kube-scheduler|v0.0.0|间接依赖|go|
|k8s.io/api|v0.25.0|直接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|github.com/inconshreveable/mousetrap|v1.0.0|间接依赖|go|
|sigs.k8s.io/yaml|v1.3.0|直接依赖|go|
|github.com/prometheus/client_golang|v1.12.2|直接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|k8s.io/klog/v2|v2.80.1|直接依赖|go|
|k8s.io/gengo|v0.0.0-20211129171323-c02415ce4185|间接依赖|go|
|github.com/prometheus/procfs|v0.7.3|间接依赖|go|
|golang.org/x/oauth2|v0.0.0-20211104180415-d3ed0bb246c8|间接依赖|go|
|google.golang.org/grpc|v1.47.0|间接依赖|go|
|github.com/go-task/slim-sprig|v0.0.0-20210107165309-348f09dbbbc0|间接依赖|go|
|github.com/golang/protobuf|v1.5.2|间接依赖|go|
|k8s.io/code-generator|v0.25.0|直接依赖|go|
|golang.org/x/tools|v0.6.0|间接依赖|go|
|github.com/blang/semver/v4|v4.0.0|间接依赖|go|
|github.com/golang/mock|v1.6.0|直接依赖|go|
|github.com/onsi/ginkgo/v2|v2.8.3|直接依赖|go|
|github.com/google/gofuzz|v1.1.0|间接依赖|go|
|k8s.io/cloud-provider|v0.25.0|间接依赖|go|
|cloud.google.com/go|v0.97.0|间接依赖|go|
|golang.org/x/net|v0.7.0|间接依赖|go|
|k8s.io/mount-utils|v0.25.0|间接依赖|go|
|golang.org/x/term|v0.5.0|间接依赖|go|
|k8s.io/utils|v0.0.0-20220728103510-ee6ede2d64ed|直接依赖|go|
|k8s.io/component-helpers|v0.25.0|直接依赖|go|
|k8s.io/klog|v1.0.0|直接依赖|go|
|k8s.io/csi-translation-lib|v0.25.0|直接依赖|go|
|google.golang.org/protobuf|v1.28.0|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.5|间接依赖|go|
|golang.org/x/text|v0.7.0|间接依赖|go|
|k8s.io/client-go|v0.25.0|直接依赖|go|
|sigs.k8s.io/json|v0.0.0-20220713155537-f223a00ba0e2|间接依赖|go|
|github.com/google/pprof|v0.0.0-20210720184732-4bb14d4b1be1|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.5.4|直接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|k8s.io/apiserver|v0.25.0|直接依赖|go|
|github.com/google/uuid|v1.1.2|间接依赖|go|
|github.com/evanphx/json-patch/v5|v5.6.0|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|github.com/go-logr/logr|v1.2.3|间接依赖|go|
|github.com/imdario/mergo|v0.3.12|直接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.2-0.20181231171920-c182affec369|间接依赖|go|
|go.uber.org/automaxprocs|v1.4.0|直接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/opencontainers/selinux|v1.10.0|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/docker/distribution|v2.8.1+incompatible|间接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.0|直接依赖|go|
|github.com/prometheus/common|v0.32.1|直接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0|间接依赖|go|
|github.com/elastic/go-elasticsearch/v7|v7.17.7|直接依赖|go|
|github.com/hashicorp/errwrap|v1.0.0|间接依赖|go|
|k8s.io/component-base|v0.25.0|直接依赖|go|
|k8s.io/apimachinery|v0.25.0|直接依赖|go|
|github.com/emicklei/go-restful/v3|v3.8.0|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20220502173005-c8bf987b8c21|间接依赖|go|
|golang.org/x/crypto|v0.0.0-20220315160706-3147a52a75dd|直接依赖|go|
|volcano.sh/apis|v1.6.0-alpha.0.0.20230214095022-ad92502b1a57|直接依赖|go|
|github.com/mailru/easyjson|v0.7.6|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/evanphx/json-patch|v4.12.0+incompatible|间接依赖|go|
|golang.org/x/time|v0.0.0-20220609170525-579cf78fd858|直接依赖|go|
|github.com/PuerkitoBio/purell|v1.1.1|间接依赖|go|
|get_rank||间接依赖|pip|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.3|间接依赖|go|
|github.com/google/shlex|v0.0.0-20191202100458-e7afc7fbc510|直接依赖|go|
|github.com/go-openapi/swag|v0.19.14|间接依赖|go|
|github.com/prometheus/client_model|v0.2.0|间接依赖|go|
|github.com/PuerkitoBio/urlesc|v0.0.0-20170810143723-de5bf2ad4578|间接依赖|go|
|k8s.io/kubernetes|v1.25.0|直接依赖|go|
|github.com/hashicorp/go-multierror|v1.0.0|直接依赖|go|
|github.com/google/cadvisor|v0.45.0|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20220803162953-67bda5d908f1|间接依赖|go|
|golang.org/x/sys|v0.5.0|间接依赖|go|
|github.com/spf13/cobra|v1.4.0|直接依赖|go|
|github.com/onsi/gomega|v1.27.0|直接依赖|go|
|github.com/moby/sys/mountinfo|v0.6.0|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.1.2|间接依赖|go|
|init||间接依赖|pip|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)