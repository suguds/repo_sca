# huanghongxun/HMCL安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698397027670212608.svg)](https://www.murphysec.com/console/report/1698397027594715136/1698397027670212608)

仓库描述：A Minecraft Launcher which is multi-functional, cross-platform and popular

仓库地址：[https://github.com/huanghongxun/HMCL](https://github.com/huanghongxun/HMCL)

| star：5517 | watch：92 | fork：576 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-02 21:52:29 | 许可证：GPL-3.0 |
| 最近检测时间：2023-09-04 02:08:44 | 组件总数：18 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|NanoHTTPD 跨站脚本漏洞|XSS|[MPS-2021-1986](https://www.oscs1024.com/hd/MPS-2021-1986)|CVE-2020-13697|中危|
|NanoHTTPD 安全漏洞||[MPS-2022-5055](https://www.oscs1024.com/hd/MPS-2022-5055)|CVE-2022-21230|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.nanohttpd:nanohttpd|2.3.1||直接依赖|可选修复|C:0|H:0|M:2|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|2|Low|
|自定义许可证|2|Low|
|Apache-2.0|4|Low|
|BSD-3-Clause|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|:No dependencies||直接依赖|maven|
|libs:JFoenix||直接依赖|maven|
|ADVAPI32.dll||间接依赖||
|com.moandjiezana.toml:toml4j|0.7.2|直接依赖|maven|
|SHELL32.dll||间接依赖||
|org.jenkins-ci:constant-pool-scanner|1.2|直接依赖|maven|
|KERNEL32.dll||间接依赖||
|com.google.code.gson:gson|2.10.1|直接依赖|maven|
|org.glavo:simple-png-javafx|0.3.0|直接依赖|maven|
|com.github.steveice10:opennbt|1.5|直接依赖|maven|
|org.glavo:simple-png|0.3.0|间接依赖|maven|
|org.hildan.fxgson:fx-gson|5.0.0|直接依赖|maven|
|VERSION.dll||间接依赖||
|org.nanohttpd:nanohttpd|2.3.1|直接依赖|maven|
|USER32.dll||间接依赖||
|::HMCLCore||直接依赖|maven|
|org.tukaani:xz|1.9|直接依赖|maven|
|org.apache.commons:commons-compress|1.23.0|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)