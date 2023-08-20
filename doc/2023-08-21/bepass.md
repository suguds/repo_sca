# uoosef/bepass安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1693324796443381760.svg)](https://www.murphysec.com/console/report/1693324796367884288/1693324796443381760)

仓库描述：A simple DPI bypass tool written in go

仓库地址：[https://github.com/uoosef/bepass](https://github.com/uoosef/bepass)

| star：117 | watch：6 | fork：13 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-18 23:18:06 | 许可证：MIT |
| 最近检测时间：2023-08-21 02:11:13 | 组件总数：65 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58311](https://www.oscs1024.com/hd/MPS-2022-58311)|CVE-2022-41727|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|golang.org/x/image|v0.3.0|0.5.0|间接依赖|建议修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|8|Low|
|MIT|23|Low|
|BSD-3-Clause|24|Low|
|BSD-2-Clause|4|Low|
|Unlicense|4|Low|
|ISC|1|Low|
|MPL-2.0|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/v2pro/plz|v0.0.0-20221028024117-e5f9aec5b631|间接依赖|go|
|github.com/subosito/gotenv|v1.4.2|间接依赖|go|
|github.com/go-gl/glfw/v3.3/glfw|v0.0.0-20221017161538-93cebf72946b|间接依赖|go|
|github.com/go-gl/gl|v0.0.0-20211210172815-726fda9656d6|间接依赖|go|
|github.com/jsummers/gobmp|v0.0.0-20151104160322-e2ba15ffa76e|间接依赖|go|
|github.com/spf13/cast|v1.5.1|间接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.0|间接依赖|go|
|github.com/gaukas/godicttls|v0.0.4|间接依赖|go|
|github.com/fyne-io/image|v0.0.0-20220602074514-4956b0afb3d2|间接依赖|go|
|github.com/fredbi/uri|v0.1.0|间接依赖|go|
|github.com/fyne-io/glfw-js|v0.0.0-20220120001248-ee7290d23504|间接依赖|go|
|github.com/refraction-networking/utls|v1.4.3|直接依赖|go|
|github.com/magiconair/properties|v1.8.7|间接依赖|go|
|github.com/AdguardTeam/golibs|v0.10.9|间接依赖|go|
|github.com/gopherjs/gopherjs|v1.17.2|间接依赖|go|
|github.com/spf13/jwalterweatherman|v1.1.0|间接依赖|go|
|golang.org/x/tools|v0.11.0|间接依赖|go|
|golang.org/x/mod|v0.12.0|间接依赖|go|
|gopkg.in/ini.v1|v1.67.0|间接依赖|go|
|github.com/eycorsican/go-tun2socks|v0.0.0|直接依赖|go|
|golang.org/x/mobile|v0.0.0-20211207041440-4e6c2922fdee|间接依赖|go|
|golang.org/x/text|v0.12.0|间接依赖|go|
|github.com/ameshkov/dnsstamps|v1.0.3|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|github.com/go-text/typesetting|v0.0.0-20230405155246-bf9c697c6e16|间接依赖|go|
|github.com/djherbis/nio|v2.0.3+incompatible|间接依赖|go|
|github.com/stretchr/testify|v1.8.3|间接依赖|go|
|github.com/hashicorp/golang-lru|v0.5.4|间接依赖|go|
|golang.org/x/sys|v0.11.0|间接依赖|go|
|github.com/fyne-io/gl-js|v0.0.0-20220119005834-d2da28d9ccfe|间接依赖|go|
|github.com/srwiley/rasterx|v0.0.0-20210519020934-456a8d69b780|间接依赖|go|
|github.com/daeuniverse/softwind|v0.0.0-20230809141237-cbe650b0e27c|直接依赖|go|
|github.com/gorilla/websocket|v1.5.0|直接依赖|go|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|github.com/pelletier/go-toml/v2|v2.0.8|间接依赖|go|
|github.com/spf13/viper|v1.16.0|直接依赖|go|
|golang.org/x/image|v0.3.0|间接依赖|go|
|github.com/aead/chacha20|v0.0.0-20180709150244-8b13a72661da|间接依赖|go|
|honnef.co/go/js/dom|v0.0.0-20210725211120-f030747120f2|间接依赖|go|
|golang.org/x/net|v0.14.0|直接依赖|go|
|github.com/yuin/goldmark|v1.4.13|间接依赖|go|
|fyne.io/fyne/v2|v2.3.5|直接依赖|go|
|github.com/andybalholm/brotli|v1.0.5|间接依赖|go|
|github.com/tevino/abool|v1.2.0|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|间接依赖|go|
|fyne.io/systray|v1.10.1-0.20230602210930-b6a2d6ca2a7b|间接依赖|go|
|golang.org/x/crypto|v0.12.0|间接依赖|go|
|github.com/godbus/dbus/v5|v5.1.0|间接依赖|go|
|github.com/ameshkov/dnscrypt/v2|v2.2.7|直接依赖|go|
|github.com/aead/poly1305|v0.0.0-20180717145839-3fee0db0b635|间接依赖|go|
|github.com/quic-go/quic-go|v0.37.4|间接依赖|go|
|github.com/miekg/dns|v1.1.55|直接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/klauspost/compress|v1.16.7|间接依赖|go|
|github.com/djherbis/buffer|v1.2.0|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|github.com/spf13/cobra|v1.7.0|直接依赖|go|
|github.com/spf13/afero|v1.9.5|间接依赖|go|
|github.com/goki/freetype|v0.0.0-20220119013949-7a161fd3728c|间接依赖|go|
|github.com/elazarl/goproxy|v0.0.0-20230731152917-f99041a5c027|直接依赖|go|
|github.com/songgao/water|v0.0.0-20200317203138-2b4b6d7c09d8|直接依赖|go|
|github.com/srwiley/oksvg|v0.0.0-20220731023508-a61f04f16b76|间接依赖|go|
|github.com/eknkc/basex|v1.0.1|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)