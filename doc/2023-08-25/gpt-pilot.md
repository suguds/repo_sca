# Pythagora-io/gpt-pilot安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694777088572551168.svg)](https://www.murphysec.com/console/report/1694777088312504320/1694777088572551168)

仓库描述：None

仓库地址：[https://github.com/Pythagora-io/gpt-pilot](https://github.com/Pythagora-io/gpt-pilot)

| star：231 | watch：6 | fork：17 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-24 13:34:43 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-25 02:22:07 | 组件总数：38 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Certifi 数据伪造问题漏洞|对数据真实性的验证不充分|[MPS-ck78-r6zg](https://www.oscs1024.com/hd/MPS-ck78-r6zg)|CVE-2023-37920|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|certifi|2023.5.7|2023.7.22|间接依赖|建议修复|C:1|H:0|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|11|Low|
|自定义许可证|5|Low|
|Apache-2.0|3|Low|
|BSD-3-Clause|4|Low|
|MPL-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|inquirer|3.1.3|间接依赖|pip|
|delete_unconnected_steps_from||间接依赖|pip|
|playhouse||间接依赖|pip|
|array_of_objects_to_string||间接依赖|pip|
|charset-normalizer|3.2.0|间接依赖|pip|
|idna|3.4|间接依赖|pip|
|database||间接依赖|pip|
|yaspin|2.4.0|间接依赖|pip|
|six|1.16.0|间接依赖|pip|
|regex|2023.6.3|间接依赖|pip|
|questionary|1.10.0|间接依赖|pip|
|urllib3|2.0.4|间接依赖|pip|
|distro|1.8.0|间接依赖|pip|
|save_command_run||间接依赖|pip|
|get_command_run_from_hash_id||间接依赖|pip|
|tiktoken|0.4.0|间接依赖|pip|
|prompt_toolkit||间接依赖|pip|
|psycopg2|2.9.6|间接依赖|pip|
|termcolor|2.3.0|间接依赖|pip|
|get_app||间接依赖|pip|
|execute_step||间接依赖|pip|
|python-dotenv|1.0.0|间接依赖|pip|
|Environment||间接依赖|pip|
|Jinja2|3.1.2|间接依赖|pip|
|requests|2.31.0|间接依赖|pip|
|MarkupSafe|2.1.3|间接依赖|pip|
|certifi|2023.5.7|间接依赖|pip|
|readchar|4.0.5|间接依赖|pip|
|FileSystemLoader||间接依赖|pip|
|wcwidth|0.2.6|间接依赖|pip|
|get_development_step_from_hash_id||间接依赖|pip|
|blessed|1.20.0|间接依赖|pip|
|prompt-toolkit|3.0.39|间接依赖|pip|
|save_development_step||间接依赖|pip|
|const||间接依赖|pip|
|python-editor|1.0.4|间接依赖|pip|
|peewee|3.16.2|间接依赖|pip|
|utils||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)