# termux/termux-app安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695859593216614400.svg)](https://www.murphysec.com/console/report/1691052017564143616/1695859593216614400)

仓库描述：Termux - a terminal emulator application for Android OS extendible by variety of packages.

仓库地址：[https://github.com/termux/termux-app](https://github.com/termux/termux-app)

| star：24055 | watch：1095 | fork：2758 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-23 22:28:19 | 许可证：NOASSERTION |
| 最近检测时间：2023-08-28 02:08:10 | 组件总数：12 | 漏洞总数：4 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|commons-io:commons-io|2.5|2.7|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.google.guava:guava|24.1-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:2|L:1|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|3|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|commons-io:commons-io|2.5|直接依赖|maven|
|androidx.window:window|1.0.0-alpha09|直接依赖|maven|
|androidx.core:core|1.6.0|直接依赖|maven|
|androidx.preference:preference|1.1.1|直接依赖|maven|
|com.termux:termux-am-library|v2.0.0|直接依赖|maven|
|androidx.appcompat:appcompat|1.3.1|直接依赖|maven|
|com.google.guava:guava|24.1-jre|直接依赖|maven|
|androidx.annotation:annotation|1.3.0|直接依赖|maven|
|com.google.android.material:material|1.4.0|直接依赖|maven|
|androidx.viewpager:viewpager|1.0.0|直接依赖|maven|
|androidx.drawerlayout:drawerlayout|1.1.1|直接依赖|maven|
|org.lsposed.hiddenapibypass:hiddenapibypass|2.0|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)