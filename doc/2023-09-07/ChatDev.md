# OpenBMB/ChatDev安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699486722559705088.svg)](https://www.murphysec.com/console/report/1698037219079274496/1699486722559705088)

仓库描述：Create Customized Software using Natural Language Idea (through Multi-Agent Collaboration)

仓库地址：[https://github.com/OpenBMB/ChatDev](https://github.com/OpenBMB/ChatDev)

| star：3514 | watch：53 | fork：283 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-06 21:12:35 | 许可证：- |
| 最近检测时间：2023-09-07 02:17:02 | 组件总数：93 | 漏洞总数：4 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|
|UltraJSON 安全漏洞|越界写入|[MPS-2021-40089](https://www.oscs1024.com/hd/MPS-2021-40089)|CVE-2021-45958|中危|
|Certifi 数据伪造问题漏洞|对数据真实性的验证不充分|[MPS-ck78-r6zg](https://www.oscs1024.com/hd/MPS-ck78-r6zg)|CVE-2023-37920|严重|
|aiohttp 环境问题漏洞|HTTP请求走私|[MPS-ptqs-e23v](https://www.oscs1024.com/hd/MPS-ptqs-e23v)|CVE-2023-37276|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|aiohttp|3.8.4|3.8.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|certifi|2023.5.7|2023.7.22|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|numpy|1.24.3||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|ujson|5.7.0||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|31|Low|
|Apache-2.0|11|Low|
|自定义许可证|16|Low|
|HPND|1|Low|
|LGPL-3.0-or-later|2|Low|
|BSD-3-Clause|11|Low|
|MPL-2.0|2|Low|
|GPL-2.0-or-later|1|Low|
|LGPL-2.1-or-later|1|Low|
|GPL-3.0-only|1|Low|
|Unlicense|1|Low|
|BSD-2-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|jedi|0.18.2|间接依赖|pip|
|requests|2.31.0|间接依赖|pip|
|autopep8|1.6.0|间接依赖|pip|
|parso|0.8.3|间接依赖|pip|
|Flask-SocketIO|5.3.4|间接依赖|pip|
|docstring-to-markdown|0.11|间接依赖|pip|
|packaging|23.0|间接依赖|pip|
|regex|2023.6.3|间接依赖|pip|
|Pillow|9.5.0|间接依赖|pip|
|python-lsp-jsonrpc|1.0.0|间接依赖|pip|
|pytoolconfig|1.2.5|间接依赖|pip|
|aiosignal|1.3.1|间接依赖|pip|
|tkinter|8.6|间接依赖|pip|
|pre-commit|3.3.3|间接依赖|pip|
|pandas|1.1.4|间接依赖|pip|
|platformdirs|3.5.3|间接依赖|pip|
|Werkzeug|2.3.6|间接依赖|pip|
|blinker|1.6.2|间接依赖|pip|
|Jinja2|3.1.2|间接依赖|pip|
|jieba|0.42.1|间接依赖|pip|
|yarl|1.9.2|间接依赖|pip|
|ModelType||间接依赖|pip|
|wrapt|1.15.0|间接依赖|pip|
|colorama|0.4.6|间接依赖|pip|
|send_from_directory||间接依赖|pip|
|tqdm|4.65.0|间接依赖|pip|
|tenacity|8.2.2|间接依赖|pip|
|pycodestyle|2.10.0|间接依赖|pip|
|dill|0.3.6|间接依赖|pip|
|bidict|0.22.1|间接依赖|pip|
|pylint|2.17.0|间接依赖|pip|
|MarkupSafe|2.1.3|间接依赖|pip|
|cfgv|3.3.1|间接依赖|pip|
|pygame|2.5.1|间接依赖|pip|
|snowballstemmer|2.2.0|间接依赖|pip|
|PySocks|1.7.1|间接依赖|pip|
|tomli|2.0.1|间接依赖|pip|
|PyYAML|6.0|间接依赖|pip|
|charset-normalizer|3.1.0|间接依赖|pip|
|tiktoken|0.4.0|间接依赖|pip|
|TaskType||间接依赖|pip|
|ABC||间接依赖|pip|
|numpy|1.24.3|间接依赖|pip|
|astroid|2.15.0|间接依赖|pip|
|tomlkit|0.11.6|间接依赖|pip|
|toml|0.10.2|间接依赖|pip|
|matplotlib|3.4.3|间接依赖|pip|
|opencv-python|4.5.3.56|间接依赖|pip|
|pyflakes|3.0.1|间接依赖|pip|
|mobi|0.1.0|间接依赖|pip|
|python-socketio|5.8.0|间接依赖|pip|
|retrying|1.3.4|间接依赖|pip|
|rope|1.7.0|间接依赖|pip|
|ebooklib|0.17.1|间接依赖|pip|
|attrs|23.1.0|间接依赖|pip|
|PyPDF2|1.26.0|间接依赖|pip|
|itsdangerous|2.1.2|间接依赖|pip|
|flake8|6.0.0|间接依赖|pip|
|python-lsp-server|1.7.1|间接依赖|pip|
|identify|2.5.24|间接依赖|pip|
|pluggy|1.2.0|间接依赖|pip|
|nodeenv|1.8.0|间接依赖|pip|
|aiohttp|3.8.4|间接依赖|pip|
|importlib-metadata|6.8.0|间接依赖|pip|
|random|3.9.6|间接依赖|pip|
|click|8.1.6|间接依赖|pip|
|idna|3.4|间接依赖|pip|
|keyboard|0.13.5|间接依赖|pip|
|typing_extensions|4.5.0|间接依赖|pip|
|python-engineio|4.5.1|间接依赖|pip|
|certifi|2023.5.7|间接依赖|pip|
|distlib|0.3.6|间接依赖|pip|
|isort|5.12.0|间接依赖|pip|
|urllib3|2.0.3|间接依赖|pip|
|async-timeout|4.0.2|间接依赖|pip|
|abstractmethod||间接依赖|pip|
|pydocstyle|6.2.3|间接依赖|pip|
|whatthepatch|1.0.4|间接依赖|pip|
|filelock|3.12.2|间接依赖|pip|
|install|1.3.5|间接依赖|pip|
|six|1.16.0|间接依赖|pip|
|ujson|5.7.0|间接依赖|pip|
|Flask|2.3.2|间接依赖|pip|
|mccabe|0.7.0|间接依赖|pip|
|frozenlist|1.3.3|间接依赖|pip|
|openai|0.27.8|间接依赖|pip|
|timeout-decorator|0.5.0|间接依赖|pip|
|multidict|6.0.4|间接依赖|pip|
|lazy-object-proxy|1.9.0|间接依赖|pip|
|virtualenv|20.23.0|间接依赖|pip|
|yapf|0.32.0|间接依赖|pip|
|Markdown|3.4.4|间接依赖|pip|
|zipp|3.16.2|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)