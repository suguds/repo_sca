# Dataherald/dataherald安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695141401330540544.svg)](https://www.murphysec.com/console/report/1695141399862534144/1695141401330540544)

仓库描述：None

仓库地址：[https://github.com/Dataherald/dataherald](https://github.com/Dataherald/dataherald)

| star：415 | watch：4 | fork：17 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-26 01:16:48 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-26 02:29:43 | 组件总数：49 | 漏洞总数：10 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|httpx 存在输入验证不恰当漏洞|输入验证不恰当|[MPS-2022-14944](https://www.oscs1024.com/hd/MPS-2022-14944)||中危|
|LangChain 注入漏洞|注入|[MPS-3udo-v1n0](https://www.oscs1024.com/hd/MPS-3udo-v1n0)|CVE-2023-36188|严重|
|langchain-0.0.194代码注入漏洞|代码注入|[MPS-84rc-nja1](https://www.oscs1024.com/hd/MPS-84rc-nja1)|CVE-2023-36095|严重|
|langchain-0.0.231代码注入漏洞|代码注入|[MPS-fv9p-y147](https://www.oscs1024.com/hd/MPS-fv9p-y147)|CVE-2023-38860|严重|
|OpenSSL 安全漏洞|过度迭代|[MPS-n3pe-ljgc](https://www.oscs1024.com/hd/MPS-n3pe-ljgc)|CVE-2023-3817|中危|
|LangChain SQL注入漏洞|SQL注入|[MPS-p829-6f3r](https://www.oscs1024.com/hd/MPS-p829-6f3r)|CVE-2023-36189|高危|
|LangChain 安全漏洞||[MPS-s5ul-own1](https://www.oscs1024.com/hd/MPS-s5ul-own1)|CVE-2023-36258|严重|
|python-cryptography 信任管理问题漏洞|证书验证不恰当|[MPS-sj5m-20tf](https://www.oscs1024.com/hd/MPS-sj5m-20tf)|CVE-2023-38325|高危|
|langchain注入漏洞|注入|[MPS-vszg-p7q8](https://www.oscs1024.com/hd/MPS-vszg-p7q8)|CVE-2023-38896|严重|
|langchain注入漏洞|注入|[MPS-x9qb-uct8](https://www.oscs1024.com/hd/MPS-x9qb-uct8)|CVE-2023-39659|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|cryptography|40.0.2|41.0.3|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|langchain|0.0.230|0.0.236|间接依赖|建议修复|C:6|H:1|M:0|L:0|
|httpx|0.24.1||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|8|Low|
|ISC|1|Low|
|BSD-3-Clause|2|Low|
|自定义许可证|6|Low|
|Apache-2.0|6|Low|
|PSF-2.0 AND (Apache-2.0 OR BSD-3-Clause)|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|mypy-extensions|1.0.0|间接依赖|pip|
|dnspython|2.3.0|间接依赖|pip|
|pydantic|1.10.9|间接依赖|pip|
|python-dotenv|1.0.0|间接依赖|pip|
|fastapi|0.98.0|间接依赖|pip|
|packaging|23.1|间接依赖|pip|
|sphinx-book-theme|1.0.1|间接依赖|pip|
|dataherald||间接依赖|pip|
|abstractmethod||间接依赖|pip|
|httpx|0.24.1|间接依赖|pip|
|Evaluator||间接依赖|pip|
|uvicorn|0.22.0|间接依赖|pip|
|GoldenRecordRequest||间接依赖|pip|
|sphinx|6.2.1|间接依赖|pip|
|Any||间接依赖|pip|
|pymongo|4.4.0|间接依赖|pip|
|pinecone-client|2.2.2|间接依赖|pip|
|openai|0.27.8|间接依赖|pip|
|sqlalchemy-databricks|0.2.0|间接依赖|pip|
|pytest-dotenv|0.5.2|间接依赖|pip|
|Dict||间接依赖|pip|
|ipdb|0.13.13|间接依赖|pip|
|Anthropic||间接依赖|pip|
|psycopg2|2.9.6|间接依赖|pip|
|chromadb|0.3.26|间接依赖|pip|
|sqlalchemy-bigquery|1.6.1|间接依赖|pip|
|List||间接依赖|pip|
|requests|2.31.0|间接依赖|pip|
|snowflake-connector-python|3.0.4|间接依赖|pip|
|openapi-schema-pydantic|1.2.4|间接依赖|pip|
|sshtunnel|0.4.0|间接依赖|pip|
|sql-metadata|2.8.0|间接依赖|pip|
|load-dotenv|0.1.0|间接依赖|pip|
|/app/requirements.txt||间接依赖|pip|
|langchain|0.0.230|间接依赖|pip|
|cryptography|40.0.2|间接依赖|pip|
|ChatGooglePalm||间接依赖|pip|
|bson||间接依赖|pip|
|Callable||间接依赖|pip|
|AlephAlpha||间接依赖|pip|
|GoldenRecord||间接依赖|pip|
|ChatAnthropic||间接依赖|pip|
|Evaluation||间接依赖|pip|
|ABC||间接依赖|pip|
|SQLAlchemy|1.4.49|间接依赖|pip|
|databricks-sql-connector|2.7.0|间接依赖|pip|
|sqlparse|0.4.4|间接依赖|pip|
|snowflake-sqlalchemy|1.4.7|间接依赖|pip|
|overrides|7.3.1|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)