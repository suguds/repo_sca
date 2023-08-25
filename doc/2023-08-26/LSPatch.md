# LSPosed/LSPatch安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695134376994959360.svg)](https://www.murphysec.com/console/report/1695134368933507072/1695134376994959360)

仓库描述：LSPatch: A non-root Xposed framework extending from LSPosed

仓库地址：[https://github.com/LSPosed/LSPatch](https://github.com/LSPosed/LSPatch)

| star：3550 | watch：50 | fork：304 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-25 20:36:26 | 许可证：GPL-3.0 |
| 最近检测时间：2023-08-26 02:02:47 | 组件总数：13 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.bouncycastle:bcprov-jdk15on|1.70||直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|3|Low|
|Apache-2.0|4|Low|
|自定义许可证|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|dev.rikka.shizuku:api|13.1.2|直接依赖|maven|
|com.beust:jcommander|1.82|直接依赖|maven|
|dev.rikka.tools.refine:runtime|4.3.0|直接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.70|直接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.70|直接依赖|maven|
|androidx.navigation:navigation-compose|2.6.0|直接依赖|maven|
|dev.rikka.shizuku:provider|13.1.2|直接依赖|maven|
|androidx.core:core-ktx|1.10.1|直接依赖|maven|
|com.google.code.gson:gson|2.10.1|直接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|直接依赖|maven|
|androidx.activity:activity-compose|1.7.2|直接依赖|maven|
|androidx.lifecycle:lifecycle-viewmodel-compose|2.6.1|直接依赖|maven|
|commons-io:commons-io|2.13.0|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)