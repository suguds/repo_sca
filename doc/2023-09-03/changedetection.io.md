# dgtlmoon/changedetection.io安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698037745489592320.svg)](https://www.murphysec.com/console/report/1698037745367957504/1698037745489592320)

仓库描述：The best and simplest free open source website change detection, restock monitor and notification service. Restock Monitor, change detection. Designed for simplicity - Simply monitor which websites had a text change for free. Free Open source web page change detection, Website defacement monitoring, Price change and Price Drop notification

仓库地址：[https://github.com/dgtlmoon/changedetection.io](https://github.com/dgtlmoon/changedetection.io)

| star：10980 | watch：66 | fork：637 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-02 23:59:13 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-03 02:19:04 | 组件总数：21 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|urllib3 资源管理错误漏洞|拒绝服务|[MPS-2021-9054](https://www.oscs1024.com/hd/MPS-2021-9054)|CVE-2021-33503|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|urllib3|1.26|1.26.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|ISC|1|Low|
|MIT|3|Low|
|自定义许可证|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|live_server_setup||间接依赖|pip|
|dnspython|2.3.0|间接依赖|pip|
|set_original_response||间接依赖|pip|
|eventlet|0.31.0|间接依赖|pip|
|wtforms||间接依赖|pip|
|ConnectTimeout||间接依赖|pip|
|urllib3|1.26|间接依赖|pip|
|Resource||间接依赖|pip|
|flask||间接依赖|pip|
|restock_diff||间接依赖|pip|
|jsonschema|4.17.3|间接依赖|pip|
|ReadTimeout||间接依赖|pip|
|bs4||间接依赖|pip|
|playwright||间接依赖|pip|
|BaseLoader||间接依赖|pip|
|/requirements.txt||间接依赖|pip|
|text_json_diff||间接依赖|pip|
|Environment||间接依赖|pip|
|set_modified_response||间接依赖|pip|
|abort||间接依赖|pip|
|chardet|2.3.0|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)