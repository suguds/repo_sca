# bumptech/glide安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694048648181932032.svg)](https://www.murphysec.com/console/report/1694048648098045952/1694048648181932032)

仓库描述：An image loading and caching library for Android focused on smooth scrolling

仓库地址：[https://github.com/bumptech/glide](https://github.com/bumptech/glide)

| star：33847 | watch：1053 | fork：6098 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-23 01:46:17 | 许可证：NOASSERTION |
| 最近检测时间：2023-08-23 02:14:07 | 组件总数：2 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.google.code.gson:gson|2.8.2|2.8.9|直接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|1|Low|
|BSD-2-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.google.code.gson:gson|2.8.2|直接依赖|maven|
|org.aomedia.avif.android:avif|0.11.1.3c786d2|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)