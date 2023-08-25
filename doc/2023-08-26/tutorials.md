# eugenp/tutorials安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695134655098740736.svg)](https://www.murphysec.com/console/report/1693685729744809984/1695134655098740736)

仓库描述：Just Announced - "Learn Spring Security OAuth": 

仓库地址：[https://github.com/eugenp/tutorials](https://github.com/eugenp/tutorials)

| star：34767 | watch：1528 | fork：54006 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-26 01:47:38 | 许可证：MIT |
| 最近检测时间：2023-08-26 02:31:59 | 组件总数：12 | 漏洞总数：3 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache Commons IO 存在路径遍历漏洞|路径遍历|[MPS-2021-4531](https://www.oscs1024.com/hd/MPS-2021-4531)|CVE-2021-29425|中危|
|com.beust:jcommander 存在从非可信控制范围包含功能例程漏洞||[MPS-2022-12225](https://www.oscs1024.com/hd/MPS-2022-12225)||中危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.google.code.gson:gson|2.5|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.code.gson:gson|2.2.4|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|commons-io:commons-io|2.4|2.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|com.beust:jcommander|1.48|1.75|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|6|Low|
|Apache-2.0|5|Low|
|MIT|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|jaxen:jaxen|1.1.6|间接依赖|maven|
|commons-io:commons-io|2.4|间接依赖|maven|
|org.ow2.asm:asm|6.0|间接依赖|maven|
|net.sourceforge.pmd:pmd-java|6.0.1|直接依赖|maven|
|com.beust:jcommander|1.48|间接依赖|maven|
|com.google.code.gson:gson|2.2.4|间接依赖|maven|
|net.java.dev.javacc:javacc|5.0|间接依赖|maven|
|org.apache.commons:commons-lang3|3.7|间接依赖|maven|
|com.stripe:stripe-java|4.2.0|直接依赖|maven|
|net.sourceforge.pmd:pmd-core|6.0.1|直接依赖|maven|
|com.google.code.gson:gson|2.5|间接依赖|maven|
|net.sourceforge.saxon:saxon|9.1.0.8|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)