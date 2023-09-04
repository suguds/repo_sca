# binary-husky/gpt_academic安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698762850939224064.svg)](https://www.murphysec.com/console/report/1698762850884698112/1698762850939224064)

仓库描述：为ChatGPT/GLM提供图形交互界面，特别优化论文阅读/润色/写作体验，模块化设计，支持自定义快捷按钮&函数插件，支持Python和C++等项目剖析&自译解功能，PDF/LaTex论文翻译&总结功能，支持并行问询多种LLM模型，支持chatglm2等本地模型。兼容文心一言, moss, llama2, rwkv, claude2, 通义千问, 书生, 讯飞星火等。

仓库地址：[https://github.com/binary-husky/gpt_academic](https://github.com/binary-husky/gpt_academic)

| star：40567 | watch：181 | fork：5332 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-04 12:39:25 | 许可证：GPL-3.0 |
| 最近检测时间：2023-09-05 02:20:10 | 组件总数：23 | 漏洞总数：3 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|PyPDF2 安全漏洞|不可达退出条件的循环（无限循环）|[MPS-1fz2-lk79](https://www.oscs1024.com/hd/MPS-1fz2-lk79)|CVE-2023-36464|中危|
|PyTorch 命令注入漏洞|代码注入|[MPS-2022-65270](https://www.oscs1024.com/hd/MPS-2022-65270)|CVE-2022-45907|严重|
|Requests Proxy-Authorization 标头泄露漏洞|未授权敏感信息泄露|[MPS-hr61-tzey](https://www.oscs1024.com/hd/MPS-hr61-tzey)|CVE-2023-32681|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|torch|1.10|1.13.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|requests|2.27.1|2.31.0|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|pypdf2|2.12.1||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|2|Low|
|MIT|4|Low|
|自定义许可证|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|adjust_theme||间接依赖|pip|
|requests|2.27.1|间接依赖|pip|
|write_results_to_file||间接依赖|pip|
|requirements.txt||间接依赖|pip|
|slack-sdk|3.21.3|间接依赖|pip|
|lru_cache||间接依赖|pip|
|update_ui||间接依赖|pip|
|transformers|4.25.1|间接依赖|pip|
|format_io||间接依赖|pip|
|tiktoken|0.3.3|间接依赖|pip|
|scipdf_parser|0.3|间接依赖|pip|
|pydantic|1.10.11|间接依赖|pip|
|request_llm/requirements_jittorllms.txt||间接依赖|pip|
|request_llm/requirements_newbing.txt||间接依赖|pip|
|find_free_port||间接依赖|pip|
|request_llm/requirements_chatglm.txt||间接依赖|pip|
|advanced_css||间接依赖|pip|
|wraps||间接依赖|pip|
|toolbox||间接依赖|pip|
|get_conf||间接依赖|pip|
|torch|1.10|间接依赖|pip|
|CatchException||间接依赖|pip|
|pypdf2|2.12.1|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)