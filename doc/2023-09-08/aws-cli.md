# aws/aws-cli安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699850027504812032.svg)](https://www.murphysec.com/console/report/1699850027139907584/1699850027504812032)

仓库描述：Universal Command Line Interface for Amazon Web Services

仓库地址：[https://github.com/aws/aws-cli](https://github.com/aws/aws-cli)

| star：14202 | watch：574 | fork：3871 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-08 00:58:03 | 许可证：NOASSERTION |
| 最近检测时间：2023-09-08 02:20:12 | 组件总数：22 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Python 安全漏洞|ReDoS|[MPS-2022-57238](https://www.oscs1024.com/hd/MPS-2022-57238)|CVE-2022-40897|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|setuptools|43.0|65.5.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|4|Low|
|自定义许可证|4|Low|
|Apache-2.0|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|AWSRequest||间接依赖|pip|
|is_windows||间接依赖|pip|
|pytest|7.4.0|间接依赖|pip|
|wheel|0.38.1|间接依赖|pip|
|Sphinx|1.4.9|间接依赖|pip|
|closing||间接依赖|pip|
|check-manifest|0.37|间接依赖|pip|
|jinja2|3.1|间接依赖|pip|
|coverage|5.5|间接依赖|pip|
|unpack_cli_arg||间接依赖|pip|
|tzutc||间接依赖|pip|
|unpack_argument||间接依赖|pip|
|tzlocal||间接依赖|pip|
|awscli||间接依赖|pip|
|contextmanager||间接依赖|pip|
|mock||间接依赖|pip|
|setuptools|43.0|间接依赖|pip|
|urlparse||间接依赖|pip|
|capture_output||间接依赖|pip|
|skip_if_windows||间接依赖|pip|
|CLIRunner||间接依赖|pip|
|pytest-cov|2.12.1|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)