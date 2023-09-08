# chatchat-space/Langchain-Chatchat安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700213128340045824.svg)](https://www.murphysec.com/console/report/1692239221308022784/1700213128340045824)

仓库描述：Langchain-Chatchat（原Langchain-ChatGLM）基于 Langchain 与 ChatGLM 等语言模型的本地知识库问答 | Langchain-Chatchat (formerly langchain-ChatGLM), local knowledge based LLM (like ChatGLM) QA app with langchain 

仓库地址：[https://github.com/chatchat-space/Langchain-Chatchat](https://github.com/chatchat-space/Langchain-Chatchat)

| star：15361 | watch：170 | fork：2543 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-08 21:33:09 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-09 02:27:51 | 组件总数：38 | 漏洞总数：3 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|LangChain 代码注入漏洞|代码注入|[MPS-7jdv-a49n](https://www.oscs1024.com/hd/MPS-7jdv-a49n)|CVE-2023-36281|严重|
|langchain注入漏洞|注入|[MPS-x9qb-uct8](https://www.oscs1024.com/hd/MPS-x9qb-uct8)|CVE-2023-39659|严重|
|LangChain 安全漏洞|代码注入|[MPS-ze2c-1nou](https://www.oscs1024.com/hd/MPS-ze2c-1nou)|CVE-2023-39631|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|langchain|0.0.266||间接依赖|建议修复|C:3|H:0|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|4|Low|
|GPL-3.0-or-later|2|Low|
|Apache-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|Dict||间接依赖|pip|
|SQLAlchemy|2.0.19|间接依赖|pip|
|ThreadPoolExecutor||间接依赖|pip|
|File||间接依赖|pip|
|streamlit|1.26.0|间接依赖|pip|
|JsCode||间接依赖|pip|
|PyMuPDF|1.22.5|间接依赖|pip|
|BaseResponse||间接依赖|pip|
|server||间接依赖|pip|
|Awaitable||间接依赖|pip|
|sqlalchemy||间接依赖|pip|
|streamlit-option-menu|0.3.6|间接依赖|pip|
|FSCHAT_MODEL_WORKERS||间接依赖|pip|
|List||间接依赖|pip|
|rapidocr_onnxruntime|1.3.1|间接依赖|pip|
|api_address||间接依赖|pip|
|as_completed||间接依赖|pip|
|SupportedVSType||间接依赖|pip|
|transformers|4.31.0|间接依赖|pip|
|KBService||间接依赖|pip|
|langchain|0.0.266|间接依赖|pip|
|Form||间接依赖|pip|
|fschat|0.2.24|间接依赖|pip|
|NLTK_DATA_PATH||间接依赖|pip|
|LLM_MODEL||间接依赖|pip|
|streamlit-antd-components|0.1.11|间接依赖|pip|
|abstractmethod||间接依赖|pip|
|Literal||间接依赖|pip|
|Queue||间接依赖|pip|
|llm_model_dict||间接依赖|pip|
|ABC||间接依赖|pip|
|configs||间接依赖|pip|
|AgGrid||间接依赖|pip|
|streamlit-chatbox|1.1.6|间接依赖|pip|
|fastapi||间接依赖|pip|
|Process||间接依赖|pip|
|ListResponse||间接依赖|pip|
|streamlit-aggrid|0.3.4.post3|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)