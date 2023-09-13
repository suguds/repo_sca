# medcl/elasticsearch-analysis-ik安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1702020389277581312.svg)](https://www.murphysec.com/console/report/1702020389084643328/1702020389277581312)

仓库描述：The IK Analysis plugin integrates Lucene IK analyzer into elasticsearch, support customized dictionary.

仓库地址：[https://github.com/medcl/elasticsearch-analysis-ik](https://github.com/medcl/elasticsearch-analysis-ik)

| star：15488 | watch：605 | fork：3230 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-31 17:51:43 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-14 02:05:40 | 组件总数：35 | 漏洞总数：3 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Apache HttpClient URI解析错误漏洞|XSS|[MPS-2020-17341](https://www.oscs1024.com/hd/MPS-2020-17341)|CVE-2020-13956|中危|
|commons-codec:commons-codec 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-11853](https://www.oscs1024.com/hd/MPS-2022-11853)||低危|
|Apache HttpClient URI解析错误漏洞|相对路径遍历|[MPS-2022-12292](https://www.oscs1024.com/hd/MPS-2022-12292)||中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|commons-codec:commons-codec|1.9|1.13|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|org.apache.httpcomponents:httpclient|4.5.2|4.5.13|直接依赖|可选修复|C:0|H:0|M:2|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|10|Low|
|Apache-2.0|24|Low|
|MIT|1|Low|
|LGPL-2.1-or-later|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.elasticsearch:elasticsearch-plugin-classloader|8.4.1|间接依赖|maven|
|org.apache.lucene:lucene-suggest|9.3.0|间接依赖|maven|
|org.apache.lucene:lucene-grouping|9.3.0|间接依赖|maven|
|commons-codec:commons-codec|1.9|间接依赖|maven|
|org.apache.lucene:lucene-memory|9.3.0|间接依赖|maven|
|org.apache.lucene:lucene-sandbox|9.3.0|间接依赖|maven|
|org.apache.lucene:lucene-queryparser|9.3.0|间接依赖|maven|
|org.elasticsearch:elasticsearch-secure-sm|8.4.1|间接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.18.0|间接依赖|maven|
|org.apache.lucene:lucene-backward-codecs|9.3.0|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.4|间接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.9|间接依赖|maven|
|org.apache.lucene:lucene-analysis-common|9.3.0|间接依赖|maven|
|org.lz4:lz4-java|1.8.0|间接依赖|maven|
|net.sf.jopt-simple:jopt-simple|5.0.2|间接依赖|maven|
|org.apache.lucene:lucene-highlighter|9.3.0|间接依赖|maven|
|org.elasticsearch:elasticsearch-x-content|8.4.1|间接依赖|maven|
|com.carrotsearch:hppc|0.8.1|间接依赖|maven|
|co.elastic.logging:ecs-logging-core|1.2.0|间接依赖|maven|
|org.elasticsearch:elasticsearch-cli|8.4.1|间接依赖|maven|
|org.apache.lucene:lucene-core|9.3.0|间接依赖|maven|
|org.elasticsearch:elasticsearch-logging|8.4.1|间接依赖|maven|
|com.tdunning:t-digest|3.2|间接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.2|直接依赖|maven|
|org.apache.lucene:lucene-misc|9.3.0|间接依赖|maven|
|org.apache.lucene:lucene-queries|9.3.0|间接依赖|maven|
|org.elasticsearch:elasticsearch-core|8.4.1|间接依赖|maven|
|org.elasticsearch:elasticsearch-geo|8.4.1|间接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.18.0|直接依赖|maven|
|net.java.dev.jna:jna|5.10.0|间接依赖|maven|
|co.elastic.logging:log4j2-ecs-layout|1.2.0|间接依赖|maven|
|org.elasticsearch:elasticsearch-lz4|8.4.1|间接依赖|maven|
|org.elasticsearch:elasticsearch|8.4.1|直接依赖|maven|
|org.apache.lucene:lucene-join|9.3.0|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)