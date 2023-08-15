# microg/GmsCore安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1691511531168882688.svg)](https://www.murphysec.com/console/report/1691511531122745344/1691511531168882688)

仓库描述：Free implementation of Play Services

仓库地址：[https://github.com/microg/GmsCore](https://github.com/microg/GmsCore)

| star：5875 | watch：217 | fork：1213 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-14 05:11:48 | 许可证：- |
| 最近检测时间：2023-08-16 02:46:45 | 组件总数：16 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|MPS-mfku-xzh3|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.google.guava:guava|31.1-android|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|7|Low|
|CC0-1.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|androidx.browser:browser|1.4.0|直接依赖|maven|
|androidx.core:core|1.0.0|直接依赖|maven|
|com.google.guava:guava|31.1-android|直接依赖|maven|
|org.microg:vtm|0.9.1-mod|直接依赖|maven|
|de.hdodenhof:circleimageview|1.3.0|直接依赖|maven|
|androidx.collection:collection|1.0.0|直接依赖|maven|
|org.microg:vtm-extras|0.9.1-mod|直接依赖|maven|
|com.google.zxing:core|3.4.1|直接依赖|maven|
|org.microg:vtm-jts|0.9.1-mod|直接依赖|maven|
|org.microg:vtm-android|0.9.1-mod|直接依赖|maven|
|androidx.appcompat:appcompat|1.0.0|直接依赖|maven|
|info.armills.chromecast-java-api-v2:api-v2-raw-request|0.10.4-raw-request-1|直接依赖|maven|
|org.microg:address-formatter|0.3.1|直接依赖|maven|
|com.upokecenter:cbor|4.5.2|直接依赖|maven|
|org.maplibre.gl:android-sdk-turf|5.9.0|直接依赖|maven|
|org.microg.gms:conscrypt-gmscore|2.5.2|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)