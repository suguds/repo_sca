# anlingyi/xechat-idea安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696946165215223808.svg)](https://www.murphysec.com/console/report/1696946165164892160/1696946165215223808)

仓库描述：让你能够在IDEA里实现聊天、下棋、斗地主！

仓库地址：[https://github.com/anlingyi/xechat-idea](https://github.com/anlingyi/xechat-idea)

| star：530 | watch：7 | fork：122 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-03-27 17:07:24 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-31 02:43:18 | 组件总数：47 | 漏洞总数：11 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|io.netty:netty-handler 存在证书验证不恰当漏洞|证书验证不恰当|[MPS-2022-12067](https://www.oscs1024.com/hd/MPS-2022-12067)||中危|
|Netty <4.1.86.Final 存在拒绝服务漏洞|未经控制的递归|[MPS-2022-58518](https://www.oscs1024.com/hd/MPS-2022-58518)|CVE-2022-41881|中危|
|Netty <4.1.86.Final 存在 CRLF 注入漏洞||[MPS-2022-58552](https://www.oscs1024.com/hd/MPS-2022-58552)|CVE-2022-41915|中危|
|Hutool 存在拒绝服务漏洞|越界写入|[MPS-2022-64976](https://www.oscs1024.com/hd/MPS-2022-64976)|CVE-2022-45688|中危|
|Hutool 存在拒绝服务漏洞|越界写入|[MPS-2022-64977](https://www.oscs1024.com/hd/MPS-2022-64977)|CVE-2022-45689|中危|
|Hutool 存在拒绝服务漏洞|越界写入|[MPS-2022-64978](https://www.oscs1024.com/hd/MPS-2022-64978)|CVE-2022-45690|中危|
|Hutool zip 拒绝服务漏洞||[MPS-2022-68308](https://www.oscs1024.com/hd/MPS-2022-68308)|CVE-2022-4565|中危|
|hutool 存在反序列化漏洞|反序列化|[MPS-2023-2460](https://www.oscs1024.com/hd/MPS-2023-2460)|CVE-2023-24162|高危|
|Hutool createTempFile函数敏感信息泄漏漏洞|未授权敏感信息泄露|[MPS-4soz-eyma](https://www.oscs1024.com/hd/MPS-4soz-eyma)|CVE-2023-33695|中危|
|Netty 资源管理错误漏洞|拒绝服务|[MPS-9u07-bna1](https://www.oscs1024.com/hd/MPS-9u07-bna1)|CVE-2023-34462|中危|
|HuTool XML外部实体注入漏洞|XXE|[MPS-xd3s-4gev](https://www.oscs1024.com/hd/MPS-xd3s-4gev)|CVE-2023-3276|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|cn.hutool:hutool-core|5.8.4|5.8.20|直接依赖|强烈建议修复|C:0|H:1|M:3|L:0|
|io.netty:netty-handler|4.1.77.Final|4.1.94.final|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|cn.hutool:hutool-json|5.8.4|5.8.11|直接依赖|可选修复|C:0|H:0|M:3|L:0|
|io.netty:netty-codec-http|4.1.77.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|io.netty:netty-codec-haproxy|4.1.77.Final|4.1.86.final|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|35|Low|
|自定义许可证|7|Low|
|EPL-1.0|2|Low|
|MIT|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|io.netty:netty-transport-sctp|4.1.77.Final|间接依赖|maven|
|io.netty:netty-common|4.1.77.Final|间接依赖|maven|
|cn.hutool:hutool-log|5.8.4|间接依赖|maven|
|io.netty:netty-codec|4.1.77.Final|间接依赖|maven|
|ch.qos.logback:logback-core|1.2.11|直接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.77.Final|间接依赖|maven|
|io.netty:netty-resolver-dns-native-macos|4.1.77.Final|间接依赖|maven|
|cn.hutool:hutool-http|5.8.4|直接依赖|maven|
|io.netty:netty-codec-socks|4.1.77.Final|间接依赖|maven|
|io.netty:netty-transport-udt|4.1.77.Final|间接依赖|maven|
|cn.6tail:lunar|1.2.24|直接依赖|maven|
|io.netty:netty-transport|4.1.77.Final|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|cn.hutool:hutool-cache|5.8.4|直接依赖|maven|
|io.netty:netty-transport-native-kqueue|4.1.77.Final|间接依赖|maven|
|io.netty:netty-codec-stomp|4.1.77.Final|间接依赖|maven|
|org.lionsoul:ip2region|2.6.4|直接依赖|maven|
|io.protostuff:protostuff-api|1.8.0|间接依赖|maven|
|cn.hutool:hutool-crypto|5.8.4|直接依赖|maven|
|io.netty:netty-codec-xml|4.1.77.Final|间接依赖|maven|
|io.netty:netty-buffer|4.1.77.Final|间接依赖|maven|
|io.netty:netty-codec-http2|4.1.77.Final|间接依赖|maven|
|io.netty:netty-handler|4.1.77.Final|间接依赖|maven|
|ch.qos.logback:logback-classic|1.2.11|直接依赖|maven|
|io.protostuff:protostuff-core|1.8.0|直接依赖|maven|
|io.netty:netty-codec-mqtt|4.1.77.Final|间接依赖|maven|
|io.netty:netty-codec-dns|4.1.77.Final|间接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.77.Final|间接依赖|maven|
|io.protostuff:protostuff-collectionschema|1.8.0|间接依赖|maven|
|io.protostuff:protostuff-runtime|1.8.0|直接依赖|maven|
|io.netty:netty-codec-smtp|4.1.77.Final|间接依赖|maven|
|io.netty:netty-codec-redis|4.1.77.Final|间接依赖|maven|
|io.netty:netty-codec-http|4.1.77.Final|间接依赖|maven|
|cn.xeblog:xechat-commons|1.6.5-beta|直接依赖|maven|
|io.netty:netty-transport-rxtx|4.1.77.Final|间接依赖|maven|
|io.netty:netty-codec-haproxy|4.1.77.Final|间接依赖|maven|
|io.netty:netty-resolver-dns-classes-macos|4.1.77.Final|间接依赖|maven|
|cn.hutool:hutool-core|5.8.4|直接依赖|maven|
|io.netty:netty-handler-proxy|4.1.77.Final|间接依赖|maven|
|io.netty:netty-codec-memcache|4.1.77.Final|间接依赖|maven|
|io.netty:netty-transport-classes-kqueue|4.1.77.Final|间接依赖|maven|
|io.netty:netty-all|4.1.77.Final|直接依赖|maven|
|io.netty:netty-resolver|4.1.77.Final|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.77.Final|间接依赖|maven|
|cn.hutool:hutool-setting|5.8.4|直接依赖|maven|
|io.netty:netty-resolver-dns|4.1.77.Final|间接依赖|maven|
|cn.hutool:hutool-json|5.8.4|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)