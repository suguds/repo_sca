# alibaba/transmittable-thread-local安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692598692089716736.svg)](https://www.murphysec.com/console/report/1692598691670286336/1692598692089716736)

仓库描述：📌 TransmittableThreadLocal (TTL), the missing Java™ std lib(simple & 0-dependency) for framework/middleware, provide an enhanced InheritableThreadLocal that transmits values between threads even using thread pooling components.

仓库地址：[https://github.com/alibaba/transmittable-thread-local](https://github.com/alibaba/transmittable-thread-local)

| star：6698 | watch：270 | fork：1607 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-15 11:31:07 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-19 02:06:46 | 组件总数：9 | 漏洞总数：0 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |





## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |





## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|7|Low|
|LGPL-2.1|2|Medium|
|MPL-1.1|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.google.code.findbugs:jsr305|3.0.2|直接依赖|maven|
|org.javassist:javassist|3.29.2-GA|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.9.0|间接依赖|maven|
|com.alibaba.ttl3:ttl-core|3.x-SNAPSHOT|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.9.0|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.9.0|间接依赖|maven|
|com.alibaba:transmittable-thread-local|3.x-SNAPSHOT|直接依赖|maven|
|org.jetbrains:annotations|24.0.1|直接依赖|maven|
|com.github.spotbugs:spotbugs-annotations|4.7.3|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)