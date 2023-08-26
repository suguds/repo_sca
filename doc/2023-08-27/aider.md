# paul-gauthier/aider安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695501897254658048.svg)](https://www.murphysec.com/console/report/1694777352574627840/1695501897254658048)

仓库描述：aider is AI pair programming in your terminal

仓库地址：[https://github.com/paul-gauthier/aider](https://github.com/paul-gauthier/aider)

| star：3560 | watch：56 | fork：534 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-25 22:17:00 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-27 02:22:43 | 组件总数：53 | 漏洞总数：4 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|
|Certifi 数据伪造问题漏洞|对数据真实性的验证不充分|[MPS-ck78-r6zg](https://www.oscs1024.com/hd/MPS-ck78-r6zg)|CVE-2023-37920|严重|
|Requests Proxy-Authorization 标头泄露漏洞|未授权敏感信息泄露|[MPS-hr61-tzey](https://www.oscs1024.com/hd/MPS-hr61-tzey)|CVE-2023-32681|中危|
|aiohttp 环境问题漏洞|HTTP请求走私|[MPS-ptqs-e23v](https://www.oscs1024.com/hd/MPS-ptqs-e23v)|CVE-2023-37276|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|certifi|2023.5.7|2023.7.22|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|aiohttp|3.8.4|3.8.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|requests|2.30.0|2.31.0|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|numpy|1.24.3||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|8|Low|
|MIT|12|Low|
|Apache-2.0|8|Low|
|BSD-3-Clause|3|Low|
|BSD-2-Clause|1|Low|
|MPL-2.0|1|Low|
|LGPL-3.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|defaultdict||间接依赖|pip|
|GitPython|3.1.31|间接依赖|pip|
|urllib3|2.0.2|间接依赖|pip|
|tiktoken|0.4.0|间接依赖|pip|
|find_packages||间接依赖|pip|
|voice||间接依赖|pip|
|charset-normalizer|3.1.0|间接依赖|pip|
|networkx|3.1|间接依赖|pip|
|aiosignal|1.3.1|间接依赖|pip|
|idna|3.4|间接依赖|pip|
|sounddevice|0.4.6|间接依赖|pip|
|diskcache|5.6.1|间接依赖|pip|
|rich|13.3.5|间接依赖|pip|
|prompt-toolkit|3.0.38|间接依赖|pip|
|multidict|6.0.4|间接依赖|pip|
|smmap|5.0.0|间接依赖|pip|
|/aider/requirements.txt||间接依赖|pip|
|prompts||间接依赖|pip|
|pytest|7.3.1|间接依赖|pip|
|frozenlist|1.3.3|间接依赖|pip|
|scipy|1.10.1|间接依赖|pip|
|Completer||间接依赖|pip|
|Pygments|2.15.1|间接依赖|pip|
|jsonschema|4.17.3|间接依赖|pip|
|__version__||间接依赖|pip|
|certifi|2023.5.7|间接依赖|pip|
|numpy|1.24.3|间接依赖|pip|
|main||间接依赖|pip|
|wcwidth|0.2.6|间接依赖|pip|
|AutoCompleter||间接依赖|pip|
|attrs|23.1.0|间接依赖|pip|
|check_gitignore||间接依赖|pip|
|openai|0.27.6|间接依赖|pip|
|PurePosixPath||间接依赖|pip|
|yarl|1.9.2|间接依赖|pip|
|markdown-it-py|2.2.0|间接依赖|pip|
|Path||间接依赖|pip|
|setup||间接依赖|pip|
|Completion||间接依赖|pip|
|models||间接依赖|pip|
|patch||间接依赖|pip|
|backoff|2.2.1|间接依赖|pip|
|aider||间接依赖|pip|
|async-timeout|4.0.2|间接依赖|pip|
|tqdm|4.65.0|间接依赖|pip|
|requests|2.30.0|间接依赖|pip|
|mdurl|0.1.2|间接依赖|pip|
|soundfile|0.12.1|间接依赖|pip|
|MagicMock||间接依赖|pip|
|Counter||间接依赖|pip|
|InputOutput||间接依赖|pip|
|gitdb|4.0.10|间接依赖|pip|
|aiohttp|3.8.4|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)