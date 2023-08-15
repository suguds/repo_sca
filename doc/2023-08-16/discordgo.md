# bwmarrin/discordgo安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1691513381978001408.svg)](https://www.murphysec.com/console/report/1691513381885726720/1691513381978001408)

仓库描述： (Golang) Go bindings for Discord

仓库地址：[https://github.com/bwmarrin/discordgo](https://github.com/bwmarrin/discordgo)

| star：4175 | watch：56 | fork：854 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-15 03:04:23 | 许可证：- |
| 最近检测时间：2023-08-16 02:13:28 | 组件总数：8 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|MPS-2021-3359|授权检查错误|[MPS-2021-3359](https://www.oscs1024.com/hd/MPS-2021-3359)|CVE-2021-28681|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|github.com/pion/webrtc/v3|v3.0.0-20200721060053-ca3cc9d940bc|3.0.15|直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|3|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|golang.org/x/crypto|v0.0.0-20210421170649-83a5a9bb288b|直接依赖|go|
|golang.org/x/oauth2|v0.3.0|直接依赖|go|
|github.com/pion/webrtc/v3|v3.0.0-20200721060053-ca3cc9d940bc|直接依赖|go|
|github.com/pion/rtp|v1.6.0|直接依赖|go|
|github.com/bwmarrin/discordgo|v0.26.1|直接依赖|go|
|github.com/bwmarrin/discordgo|v0.21.1|直接依赖|go|
|github.com/gorilla/websocket|v1.4.2|直接依赖|go|
|github.com/joho/godotenv|v1.4.0|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)