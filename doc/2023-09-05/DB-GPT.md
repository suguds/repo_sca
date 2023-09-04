# eosphoros-ai/DB-GPT安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698762324927365120.svg)](https://www.murphysec.com/console/report/1698762324671512576/1698762324927365120)

仓库描述：Revolutionizing Database Interactions with Private LLM Technology

仓库地址：[https://github.com/eosphoros-ai/DB-GPT](https://github.com/eosphoros-ai/DB-GPT)

| star：6427 | watch：65 | fork：938 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-03 18:32:11 | 许可证：MIT |
| 最近检测时间：2023-09-05 02:18:05 | 组件总数：90 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Gradio 输入验证错误漏洞||[MPS-f8mu-5xwo](https://www.oscs1024.com/hd/MPS-f8mu-5xwo)|CVE-2023-34239|严重|
|aiohttp 环境问题漏洞|HTTP请求走私|[MPS-ptqs-e23v](https://www.oscs1024.com/hd/MPS-ptqs-e23v)|CVE-2023-37276|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|aiohttp|3.8.4|3.8.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|gradio|3.23||间接依赖|建议修复|C:1|H:0|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Unlicense|1|Low|
|自定义许可证|8|Low|
|BSD-3-Clause|4|Low|
|Apache-2.0|16|Low|
|MIT|9|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|filelock|3.9.0|间接依赖|pip|
|WorkerApplyRequest||间接依赖|pip|
|Style||间接依赖|pip|
|chardet|5.1.0|间接依赖|pip|
|sqlparse|0.4.4|间接依赖|pip|
|requirements.txt||间接依赖|pip|
|DataNode||间接依赖|pip|
|sqlalchemy||间接依赖|pip|
|frozenlist|1.3.3|间接依赖|pip|
|transformers|4.31.0|间接依赖|pip|
|omegaconf|2.3.0|间接依赖|pip|
|as_completed||间接依赖|pip|
|DBSummary||间接依赖|pip|
|StoppingCriteriaList||间接依赖|pip|
|DBConfig||间接依赖|pip|
|Iterator||间接依赖|pip|
|List||间接依赖|pip|
|TextIteratorStreamer||间接依赖|pip|
|RemoteWorkerManager||间接依赖|pip|
|pilot||间接依赖|pip|
|File||间接依赖|pip|
|sphinx-typlog-theme|0.8.0|间接依赖|pip|
|LLM_MODEL_CONFIG||间接依赖|pip|
|ABC||间接依赖|pip|
|applications||间接依赖|pip|
|SeparatorStyle||间接依赖|pip|
|zipp|3.14.0|间接依赖|pip|
|async-timeout|4.0.2|间接依赖|pip|
|gradio-client|0.0.8|间接依赖|pip|
|pydantic||间接依赖|pip|
|diskcache|5.6.1|间接依赖|pip|
|tqdm|4.64.1|间接依赖|pip|
|sphinx_rtd_theme|1.0.0|间接依赖|pip|
|Any||间接依赖|pip|
|bardapi|0.1.29|间接依赖|pip|
|APIRouter||间接依赖|pip|
|timedelta||间接依赖|pip|
|autodoc_pydantic|1.8.0|间接依赖|pip|
|fields||间接依赖|pip|
|ChartRunData||间接依赖|pip|
|yarl|1.8.2|间接依赖|pip|
|fonttools|4.38.0|间接依赖|pip|
|Optional||间接依赖|pip|
|attrs|22.2.0|间接依赖|pip|
|Callable||间接依赖|pip|
|ChatDashboardOutputParser||间接依赖|pip|
|spacy|3.5.3|间接依赖|pip|
|ModelMessage||间接依赖|pip|
|huggingface-hub|0.14.1|间接依赖|pip|
|ThreadPoolExecutor||间接依赖|pip|
|KNOWLEDGE_UPLOAD_ROOT_PATH||间接依赖|pip|
|abstractmethod||间接依赖|pip|
|unstructured|0.6.3|间接依赖|pip|
|pyyaml|6.0|间接依赖|pip|
|sphinx-autobuild|2021.3.14|间接依赖|pip|
|webdataset|0.2.48|间接依赖|pip|
|ExampleType||间接依赖|pip|
|fastapi||间接依赖|pip|
|importlib-resources|5.12.0|间接依赖|pip|
|cchardet|2.1.7|间接依赖|pip|
|ModelMessageRoleType||间接依赖|pip|
|python-dateutil|2.8.2|间接依赖|pip|
|ChartItem||间接依赖|pip|
|multidict|6.0.4|间接依赖|pip|
|nbsphinx|0.8.9|间接依赖|pip|
|tenacity|8.2.2|间接依赖|pip|
|pydata-sphinx-theme|0.13.1|间接依赖|pip|
|pytesseract|0.3.10|间接依赖|pip|
|tokenizers|0.13.2|间接依赖|pip|
|Fore||间接依赖|pip|
|psutil|5.9.4|间接依赖|pip|
|TableSummary||间接依赖|pip|
|opencv-python|4.7.0.72|间接依赖|pip|
|python-dotenv|1.0.0|间接依赖|pip|
|accelerate|0.20.3|间接依赖|pip|
|NamedTuple||间接依赖|pip|
|sphinx|4.5.0|间接依赖|pip|
|FastAPI||间接依赖|pip|
|packaging|23.0|间接依赖|pip|
|gpt4all|0.3.0|间接依赖|pip|
|gradio|3.23|间接依赖|pip|
|aiohttp|3.8.4|间接依赖|pip|
|DbTypeInfo||间接依赖|pip|
|gTTS|2.3.1|间接依赖|pip|
|iopath|0.1.10|间接依赖|pip|
|aiosignal|1.3.1|间接依赖|pip|
|Dict||间接依赖|pip|
|dataclass||间接依赖|pip|
|pandas||间接依赖|pip|
|chromadb|0.3.22|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)