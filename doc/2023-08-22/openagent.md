# dot-agent/openagent安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1693689297663062016.svg)](https://www.murphysec.com/console/report/1693689297335906304/1693689297663062016)

仓库描述：Microservices approach to AGI. Modular components for AI apps or AGI agents. (... and solving some wicked LLM problems like ⚡ 2X  faster LLaMA 2)

仓库地址：[https://github.com/dot-agent/openagent](https://github.com/dot-agent/openagent)

| star：954 | watch：3 | fork：83 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-21 04:41:42 | 许可证：- |
| 最近检测时间：2023-08-22 02:19:42 | 组件总数：165 | 漏洞总数：6 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|
|httpx 存在输入验证不恰当漏洞|输入验证不恰当|[MPS-2022-14944](https://www.oscs1024.com/hd/MPS-2022-14944)||中危|
|rdflib 存在SSRF漏洞|SSRF|[MPS-2022-15111](https://www.oscs1024.com/hd/MPS-2022-15111)||高危|
|Requests Proxy-Authorization 标头泄露漏洞|未授权敏感信息泄露|[MPS-hr61-tzey](https://www.oscs1024.com/hd/MPS-hr61-tzey)|CVE-2023-32681|中危|
|LangChain SQL注入漏洞|SQL注入|[MPS-p829-6f3r](https://www.oscs1024.com/hd/MPS-p829-6f3r)|CVE-2023-36189|高危|
|aiohttp 环境问题漏洞|HTTP请求走私|[MPS-ptqs-e23v](https://www.oscs1024.com/hd/MPS-ptqs-e23v)|CVE-2023-37276|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|rdflib|7.0.0||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|langchain|0.0.253||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|aiohttp|3.8.4|3.8.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|requests|2.28.1|2.31.0|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|httpx|0.24.1||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|numpy|1.25.1||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|GPL-3.0-or-later|3|Low|
|LGPL-3.0|1|Medium|
|MIT|29|Low|
|Apache-2.0|22|Low|
|自定义许可证|14|Low|
|BSD-3-Clause|10|Low|
|GPL-3.0|2|Medium|
|HPND|1|Low|
|BSD-2-Clause|1|Low|
|ISC|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|typing_extensions|4.7.1|间接依赖|pip|
|PyMuPDF|1.21.1|间接依赖|pip|
|bibtexparser|1.4.0|间接依赖|pip|
|gql|3.4.1|间接依赖|pip|
|nltk|3.8.1|间接依赖|pip|
|pydrive|1.3.1|间接依赖|pip|
|sentencepiece|0.1.99|间接依赖|pip|
|flask||间接依赖|pip|
|html2text|2020.1.16|间接依赖|pip|
|pdf2image|1.16.3|间接依赖|pip|
|tiktoken|0.4.0|间接依赖|pip|
|jsonschema|4.18.6|间接依赖|pip|
|diskcache|5.6.1|间接依赖|pip|
|auth0_python|4.4.0|间接依赖|pip|
|Extra||间接依赖|pip|
|python-dotenv|1.0.0|间接依赖|pip|
|scikit_learn|1.3.0|间接依赖|pip|
|logout||间接依赖|pip|
|Callable||间接依赖|pip|
|tomli|2.0.1|间接依赖|pip|
|svglib|1.5.1|间接依赖|pip|
|deepspeed|0.10.0|间接依赖|pip|
|msal|1.22.0|间接依赖|pip|
|syncer|2.0.3|间接依赖|pip|
|databricks|0.2|间接依赖|pip|
|pymilvus|2.2.14|间接依赖|pip|
|abstractmethod||间接依赖|pip|
|python_graphql_client|0.4.3|间接依赖|pip|
|LLM||间接依赖|pip|
|Optional||间接依赖|pip|
|serpapi||间接依赖|pip|
|pymysql|1.1.0|间接依赖|pip|
|metal_sdk|2.0.1|间接依赖|pip|
|couchdb3|1.2.0|间接依赖|pip|
|login||间接依赖|pip|
|aleph_alpha_client|3.2.0|间接依赖|pip|
|LLMSession||间接依赖|pip|
|pydantic|1.10.11|间接依赖|pip|
|ipykernel|6.25.0|间接依赖|pip|
|torch|2.0.1|间接依赖|pip|
|export_agent_config||间接依赖|pip|
|whisper|1.1.10|间接依赖|pip|
|escape_template_block||间接依赖|pip|
|opendal|0.39.0|间接依赖|pip|
|dataclasses_json|0.5.8|间接依赖|pip|
|pypdf|3.15.0|间接依赖|pip|
|tensorflow_hub|0.14.0|间接依赖|pip|
|tensorflow_text|2.13.0|间接依赖|pip|
|nest_asyncio|1.5.6|间接依赖|pip|
|gkeepapi|0.14.2|间接依赖|pip|
|InstructorEmbedding|1.0.1|间接依赖|pip|
|google_auth_oauthlib|1.0.0|间接依赖|pip|
|huggingface_hub|0.16.4|间接依赖|pip|
|rdflib|7.0.0|间接依赖|pip|
|aioresponses|0.7.4|间接依赖|pip|
|app||间接依赖|pip|
|spotipy|2.23.0|间接依赖|pip|
|chainlit|0.6.1|间接依赖|pip|
|apify_client|1.3.1|间接依赖|pip|
|youtube_transcript_api|0.6.1|间接依赖|pip|
|fitz|0.0.1.dev2|间接依赖|pip|
|Coroutine||间接依赖|pip|
|beautifulsoup4|4.12.2|间接依赖|pip|
|qdrant_client|1.4.0|间接依赖|pip|
|osmxtract|0.0.1|间接依赖|pip|
|load_agent_config||间接依赖|pip|
|ClassVar||间接依赖|pip|
|filetype|1.2.0|间接依赖|pip|
|atlassian|0.0.0|间接依赖|pip|
|youtube_search|2.1.2|间接依赖|pip|
|slack_sdk|3.21.3|间接依赖|pip|
|azure_storage|0.37.0|间接依赖|pip|
|RequestsGetTool||间接依赖|pip|
|numpy|1.25.1|间接依赖|pip|
|google_api_python_client|2.95.0|间接依赖|pip|
|pandasai|0.8.2|间接依赖|pip|
|SQLAlchemy|2.0.19|间接依赖|pip|
|firebase_admin|6.2.0|间接依赖|pip|
|googlemaps|4.10.0|间接依赖|pip|
|Pillow|10.0.0|间接依赖|pip|
|responses|0.23.3|间接依赖|pip|
|pandas|2.0.2|间接依赖|pip|
|bilibili_api|9.1.0|间接依赖|pip|
|playwright|1.36.0|间接依赖|pip|
|lxml|4.9.3|间接依赖|pip|
|config||间接依赖|pip|
|pyparsing|3.1.1|间接依赖|pip|
|Type||间接依赖|pip|
|AsyncIter||间接依赖|pip|
|starlette|0.31.0|间接依赖|pip|
|praw|7.7.1|间接依赖|pip|
|RequestsPostTool||间接依赖|pip|
|ipython|8.14.0|间接依赖|pip|
|ebooklib|0.18|间接依赖|pip|
|python-socketio|5.8.0|间接依赖|pip|
|FastAPI||间接依赖|pip|
|docx2txt|0.8|间接依赖|pip|
|requests|2.28.1|间接依赖|pip|
|modelscope|1.8.1|间接依赖|pip|
|protobuf|4.23.4|间接依赖|pip|
|fastapi_socketio|0.0.10|间接依赖|pip|
|neo4j|5.11.0|间接依赖|pip|
|feedparser|6.0.10|间接依赖|pip|
|regex|2023.6.3|间接依赖|pip|
|PACKAGE_ROOT||间接依赖|pip|
|openapi_schema_pydantic|1.2.4|间接依赖|pip|
|pyairtable|2.0.0|间接依赖|pip|
|transformers||间接依赖|pip|
|uptrace|1.19.0|间接依赖|pip|
|fastapi|0.101.0|间接依赖|pip|
|retrying|1.3.4|间接依赖|pip|
|aiofiles|23.1.0|间接依赖|pip|
|List||间接依赖|pip|
|TYPE_CHECKING||间接依赖|pip|
|BaseModel||间接依赖|pip|
|PyYAML|6.0.1|间接依赖|pip|
|pytesseract|0.3.10|间接依赖|pip|
|snscrape|0.7.0.20230622|间接依赖|pip|
|aiohttp|3.8.4|间接依赖|pip|
|uvicorn|0.23.2|间接依赖|pip|
|Any||间接依赖|pip|
|sentence_transformers|2.2.2|间接依赖|pip|
|pyowm|3.3.0|间接依赖|pip|
|matplotlib|3.7.2|间接依赖|pip|
|SERPAPI_KEY||间接依赖|pip|
|pytest|7.4.0|间接依赖|pip|
|pexpect|4.8.0|间接依赖|pip|
|openagent||间接依赖|pip|
|pygtrie|2.5.0|间接依赖|pip|
|tweepy|4.14.0|间接依赖|pip|
|pydub|0.25.1|间接依赖|pip|
|spacy|3.6.0|间接依赖|pip|
|geopy|2.3.0|间接依赖|pip|
|feedly|0.11.3|间接依赖|pip|
|docarray|0.37.0|间接依赖|pip|
|yelpapi|2.5.0|间接依赖|pip|
|parse||间接依赖|pip|
|platformdirs|3.10.0|间接依赖|pip|
|tenacity|8.2.2|间接依赖|pip|
|zep_python|0.34|间接依赖|pip|
|HTTPException||间接依赖|pip|
|pyspark|3.4.1|间接依赖|pip|
|nbconvert|7.7.3|间接依赖|pip|
|asyncer|0.0.2|间接依赖|pip|
|click|8.1.3|间接依赖|pip|
|ABC||间接依赖|pip|
|print_ast||间接依赖|pip|
|pinecone_text|0.5.2|间接依赖|pip|
|xlrd|2.0.1|间接依赖|pip|
|chromadb|0.3.26|间接依赖|pip|
|llama_hub|0.0.18|间接依赖|pip|
|pymongo|4.4.1|间接依赖|pip|
|duckduckgo_search|3.8.4|间接依赖|pip|
|httpx|0.24.1|间接依赖|pip|
|Dict||间接依赖|pip|
|gptcache|0.1.36|间接依赖|pip|
|reportlab|4.0.4|间接依赖|pip|
|trafilatura|1.6.1|间接依赖|pip|
|langchain|0.0.253|间接依赖|pip|
|tqdm|4.65.0|间接依赖|pip|
|odps|3.5.1|间接依赖|pip|
|pdfminer|20191125|间接依赖|pip|
|boto3|1.26.159|间接依赖|pip|
|OPENAI_API_KEY||间接依赖|pip|
|watchfiles|0.19.0|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)