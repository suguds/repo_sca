# aandrew-me/tgpt安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1697674238588747776.svg)](https://www.murphysec.com/console/report/1697674238550999040/1697674238588747776)

仓库描述：ChatGPT in terminal without needing API keys

仓库地址：[https://github.com/aandrew-me/tgpt](https://github.com/aandrew-me/tgpt)

| star：632 | watch：17 | fork：51 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-02 00:57:53 | 许可证：GPL-3.0 |
| 最近检测时间：2023-09-02 02:14:19 | 组件总数：31 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58307](https://www.oscs1024.com/hd/MPS-2022-58307)|CVE-2022-41723|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|golang.org/x/net|v0.6.0|0.7.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|10|Low|
|MIT|18|Low|
|Apache-2.0|2|Low|
|BSD-4-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|golang.org/x/text|v0.9.0|间接依赖|go|
|golang.org/x/sys|v0.8.0|间接依赖|go|
|github.com/charmbracelet/bubbletea|v0.24.0|直接依赖|go|
|github.com/tam7t/hpkp|v0.0.0-20160821193359-2b70b4024ed5|间接依赖|go|
|github.com/olekukonko/ts|v0.0.0-20171002115256-78ecb04241c0|直接依赖|go|
|github.com/charmbracelet/bubbles|v0.15.0|直接依赖|go|
|github.com/fatih/color|v1.15.0|直接依赖|go|
|github.com/aymanbagabas/go-osc52/v2|v2.0.1|间接依赖|go|
|github.com/atotto/clipboard|v0.1.4|间接依赖|go|
|github.com/mattn/go-runewidth|v0.0.14|间接依赖|go|
|golang.org/x/term|v0.8.0|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|github.com/muesli/ansi|v0.0.0-20211018074035-2e021307bc4b|间接依赖|go|
|github.com/rivo/uniseg|v0.2.0|间接依赖|go|
|github.com/bogdanfinn/utls|v1.5.16|间接依赖|go|
|github.com/mattn/go-localereader|v0.0.1|间接依赖|go|
|github.com/andybalholm/brotli|v1.0.4|间接依赖|go|
|github.com/klauspost/compress|v1.15.12|间接依赖|go|
|github.com/lucasb-eyer/go-colorful|v1.2.0|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.18|间接依赖|go|
|github.com/charmbracelet/lipgloss|v0.6.0|间接依赖|go|
|golang.org/x/crypto|v0.1.0|间接依赖|go|
|github.com/bogdanfinn/fhttp|v0.5.22|直接依赖|go|
|github.com/muesli/cancelreader|v0.2.2|间接依赖|go|
|github.com/containerd/console|v1.0.4-0.20230313162750-1ae8d489ac81|间接依赖|go|
|github.com/bogdanfinn/tls-client|v1.3.11|直接依赖|go|
|github.com/muesli/reflow|v0.3.0|间接依赖|go|
|golang.org/x/mod|v0.10.0|直接依赖|go|
|github.com/muesli/termenv|v0.15.1|间接依赖|go|
|golang.org/x/sync|v0.1.0|间接依赖|go|
|golang.org/x/net|v0.6.0|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)