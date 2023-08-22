# jesseduffield/lazydocker安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694049443614908416.svg)](https://www.murphysec.com/console/report/1694049443547799552/1694049443614908416)

仓库描述：The lazier way to manage everything docker

仓库地址：[https://github.com/jesseduffield/lazydocker](https://github.com/jesseduffield/lazydocker)

| star：29978 | watch：236 | fork：1033 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-11 23:27:25 | 许可证：MIT |
| 最近检测时间：2023-08-23 02:10:48 | 组件总数：56 | 漏洞总数：8 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Kubernetes API Server 资源管理错误漏洞|循环内过多的平台资源消耗|[MPS-2020-44793](https://www.oscs1024.com/hd/MPS-2020-44793)|CVE-2019-11254|中危|
|gopkg.in/yaml.v2 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13505](https://www.oscs1024.com/hd/MPS-2022-13505)||中危|
|Go-Yaml 安全漏洞||[MPS-2022-52765](https://www.oscs1024.com/hd/MPS-2022-52765)|CVE-2021-4235|中危|
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58307](https://www.oscs1024.com/hd/MPS-2022-58307)|CVE-2022-41723|高危|
|Go-Yaml 资源管理错误漏洞|拒绝服务|[MPS-2022-69639](https://www.oscs1024.com/hd/MPS-2022-69639)|CVE-2022-3064|高危|
|Moby 安全漏洞||[MPS-2023-8823](https://www.oscs1024.com/hd/MPS-2023-8823)|CVE-2023-28840|高危|
|Moby 安全漏洞||[MPS-2023-8824](https://www.oscs1024.com/hd/MPS-2023-8824)|CVE-2023-28841|中危|
|Moby 安全漏洞|对异常条件的处理不恰当|[MPS-2023-8826](https://www.oscs1024.com/hd/MPS-2023-8826)|CVE-2023-28842|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|golang.org/x/net|v0.0.0-20201021035429-f5854403a974|0.7.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|github.com/docker/docker|v20.10.15+incompatible|23.0.3|直接依赖|建议修复|C:0|H:1|M:2|L:0|
|gopkg.in/yaml.v2|v2.2.2|2.2.8|间接依赖|建议修复|C:0|H:1|M:3|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|16|Low|
|MIT|26|Low|
|BSD-3-Clause|13|Low|
|CC-BY-SA-4.0|1|Medium|
|Unlicense|1|Low|
|ISC|1|Low|
|BSD-2-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/cloudfoundry/jibber_jabber|v0.0.0-20151120183258-bcc4c8345a21|直接依赖|go|
|github.com/docker/go-units|v0.4.0|间接依赖|go|
|github.com/mcuadros/go-lookup|v0.0.0-20171110082742-5650f26be767|直接依赖|go|
|github.com/jesseduffield/kill|v0.0.0-20220618033138-bfbe04675d10|直接依赖|go|
|github.com/rivo/uniseg|v0.4.2|间接依赖|go|
|github.com/gdamore/encoding|v1.0.0|间接依赖|go|
|github.com/onsi/gomega|v1.5.0|间接依赖|go|
|github.com/gookit/color|v1.5.0|直接依赖|go|
|github.com/moby/term|v0.0.0-20210619224110-3f7ff695adc6|间接依赖|go|
|github.com/docker/docker|v20.10.15+incompatible|直接依赖|go|
|github.com/docker/go-connections|v0.4.0|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/goccy/go-yaml|v1.11.0|直接依赖|go|
|golang.org/x/exp|v0.0.0-20220428152302-39d4317da171|间接依赖|go|
|github.com/sasha-s/go-deadlock|v0.3.1|直接依赖|go|
|golang.org/x/term|v0.1.0|间接依赖|go|
|github.com/samber/lo|v1.31.0|直接依赖|go|
|github.com/stretchr/testify|v1.8.0|直接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0-rc1|间接依赖|go|
|github.com/gdamore/tcell/v2|v2.5.3|间接依赖|go|
|github.com/jesseduffield/lazycore|v0.0.0-20221023210126-718a4caea996|直接依赖|go|
|github.com/docker/distribution|v2.8.2+incompatible|间接依赖|go|
|github.com/konsorten/go-windows-terminal-sequences|v1.0.2|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|golang.org/x/xerrors|v0.0.0-20200804184101-5ec99f83aff1|直接依赖|go|
|github.com/integrii/flaggy|v1.4.0|直接依赖|go|
|github.com/mattn/go-isatty|v0.0.12|间接依赖|go|
|github.com/onsi/ginkgo|v1.8.0|间接依赖|go|
|github.com/Microsoft/go-winio|v0.4.14|间接依赖|go|
|gopkg.in/yaml.v2|v2.2.2|间接依赖|go|
|github.com/morikuni/aec|v0.0.0-20170113033406-39771216ff4c|间接依赖|go|
|github.com/OpenPeeDeeP/xdg|v0.2.1-0.20190312153938-4ba9e1eb294c|直接依赖|go|
|github.com/imdario/mergo|v0.3.8|直接依赖|go|
|github.com/fatih/color|v1.10.0|直接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/lucasb-eyer/go-colorful|v1.2.0|间接依赖|go|
|github.com/boz/go-throttle|v0.0.0-20160922054636-fdc4eab740c1|直接依赖|go|
|github.com/mgutz/str|v1.2.0|直接依赖|go|
|github.com/xo/terminfo|v0.0.0-20210125001918-ca9a967f8778|间接依赖|go|
|github.com/mattn/go-runewidth|v0.0.14|直接依赖|go|
|github.com/jesseduffield/asciigraph|v0.0.0-20190605104717-6d88e39309ee|直接依赖|go|
|github.com/jesseduffield/yaml|v0.0.0-20190702115811-b900b7e08b56|直接依赖|go|
|github.com/petermattis/goid|v0.0.0-20180202154549-b0b1615b78e5|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|直接依赖|go|
|github.com/opencontainers/image-spec|v1.0.2|间接依赖|go|
|gotest.tools/v3|v3.2.0|间接依赖|go|
|golang.org/x/time|v0.0.0-20190308202827-9d24e82272b4|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.8|间接依赖|go|
|github.com/sirupsen/logrus|v1.4.2|直接依赖|go|
|golang.org/x/text|v0.4.0|间接依赖|go|
|github.com/go-errors/errors|v1.4.2|直接依赖|go|
|github.com/jesseduffield/gocui|v0.3.1-0.20221023185936-ef06450f4fdc|直接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|golang.org/x/sys|v0.6.0|间接依赖|go|
|golang.org/x/net|v0.0.0-20201021035429-f5854403a974|间接依赖|go|
|github.com/spkg/bom|v0.0.0-20160624110644-59b7046e48ad|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)