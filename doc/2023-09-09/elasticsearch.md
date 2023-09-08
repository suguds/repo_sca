# elastic/elasticsearch安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700208843300667392.svg)](https://www.murphysec.com/console/report/1700208843229364224/1700208843300667392)

仓库描述：Free and Open, Distributed, RESTful Search Engine

仓库地址：[https://github.com/elastic/elasticsearch](https://github.com/elastic/elasticsearch)

| star：65015 | watch：2689 | fork：23532 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-09 01:49:41 | 许可证：NOASSERTION |
| 最近检测时间：2023-09-09 02:14:50 | 组件总数：28 | 漏洞总数：3 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|jsoup <1.14.2 存在拒绝服务漏洞||[MPS-2021-17634](https://www.oscs1024.com/hd/MPS-2021-17634)|CVE-2021-37714|高危|
|jsoup <1.15.3 存在反射型 XSS 漏洞|XSS|[MPS-2022-51547](https://www.oscs1024.com/hd/MPS-2022-51547)|CVE-2022-36033|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.jsoup:jsoup|1.13.1|1.15.3|直接依赖|可选修复|C:0|H:1|M:1|L:0|
|com.google.guava:guava|31.1-jre|32.0.0-jre|直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|10|Low|
|MIT|3|Low|
|BSD-3-Clause|6|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.apache.commons:commons-math3|3.2|直接依赖|maven|
|net.sf.jopt-simple:jopt-simple|4.6|直接依赖|maven|
|org.ow2.asm:asm-tree|7.2|直接依赖|maven|
|org.ow2.asm:asm-commons|7.2|直接依赖|maven|
|KERNEL32.dll||间接依赖||
|com.google.guava:failureaccess|1.0.1|直接依赖|maven|
|org.jsoup:jsoup|1.13.1|直接依赖|maven|
|msvcrt.dll||间接依赖||
|GDI32.dll||间接依赖||
|org.ow2.asm:asm-tree|9.5|直接依赖|maven|
|ADVAPI32.dll||间接依赖||
|SHLWAPI.dll||间接依赖||
|COMCTL32.dll||间接依赖||
|org.ow2.asm:asm|9.5|直接依赖|maven|
|org.ow2.asm:asm|7.2|直接依赖|maven|
|com.google.guava:guava|32.0.1-jre|直接依赖|maven|
|org.apache.commons:commons-compress|1.21|直接依赖|maven|
|co.elastic.apm:elastic-apm-agent|1.36.0|直接依赖|maven|
|USER32.dll||间接依赖||
|org.ow2.asm:asm-analysis|7.2|直接依赖|maven|
|joda-time:joda-time|2.10.10|直接依赖|maven|
|io.sgr:s2-geometry-library-java|1.0.1|直接依赖|maven|
|SHELL32.dll||间接依赖||
|com.github.javaparser:javaparser-core|3.18.0|直接依赖|maven|
|org.ojalgo:ojalgo|51.2.0|直接依赖|maven|
|com.google.guava:guava|31.1-jre|直接依赖|maven|
|com.carrotsearch:hppc|0.8.1|直接依赖|maven|
|COMDLG32.dll||间接依赖||


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)