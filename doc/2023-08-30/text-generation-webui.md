# oobabooga/text-generation-webui安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696588912154992640.svg)](https://www.murphysec.com/console/report/1693689165144481792/1696588912154992640)

仓库描述：A Gradio web UI for Large Language Models. Supports transformers, GPTQ, llama.cpp (ggml/gguf), Llama models.

仓库地址：[https://github.com/oobabooga/text-generation-webui](https://github.com/oobabooga/text-generation-webui)

| star：22283 | watch：228 | fork：2918 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-29 14:23:16 | 许可证：AGPL-3.0 |
| 最近检测时间：2023-08-30 02:21:44 | 组件总数：66 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|
|Gradio 输入验证错误漏洞||[MPS-f8mu-5xwo](https://www.oscs1024.com/hd/MPS-f8mu-5xwo)|CVE-2023-34239|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|gradio|3.33.1|3.34.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|numpy|1.24||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|7|Low|
|HPND|1|Low|
|Apache-2.0|4|Low|
|BSD-3-Clause|2|Low|
|自定义许可证|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|AutoModelForCausalLM||间接依赖|pip|
|generate_basic_html||间接依赖|pip|
|deep-translator|1.9.2|间接依赖|pip|
|html_generator||间接依赖|pip|
|Tuple||间接依赖|pip|
|reload_model||间接依赖|pip|
|load_model||间接依赖|pip|
|beautifulsoup4|4.12.2|间接依赖|pip|
|modules||间接依赖|pip|
|Dict||间接依赖|pip|
|Callable||间接依赖|pip|
|BlipProcessor||间接依赖|pip|
|ctransformers||间接依赖|pip|
|encode||间接依赖|pip|
|make_thumbnail||间接依赖|pip|
|Pillow|9.5.0|间接依赖|pip|
|init_empty_weights||间接依赖|pip|
|List||间接依赖|pip|
|Dataset||间接依赖|pip|
|fastapi|0.95.2|间接依赖|pip|
|presets||间接依赖|pip|
|prompts||间接依赖|pip|
|OpenMonkeyPatch||间接依赖|pip|
|BaseHTTPRequestHandler||间接依赖|pip|
|sentence_transformers|2.2.2|间接依赖|pip|
|PIPELINE||间接依赖|pip|
|logits||间接依赖|pip|
|AutoConfig||间接依赖|pip|
|make_collector||间接依赖|pip|
|posthog|2.4.2|间接依赖|pip|
|PIPELINE_ARGS||间接依赖|pip|
|loaders||间接依赖|pip|
|chromadb|0.3.18|间接依赖|pip|
|chat||间接依赖|pip|
|debug_msg||间接依赖|pip|
|RoPE||间接依赖|pip|
|gradio_client|0.2.5|间接依赖|pip|
|gradio|3.33.1|间接依赖|pip|
|websockets|11.0.2|间接依赖|pip|
|shared||间接依赖|pip|
|generate_reply||间接依赖|pip|
|ui||间接依赖|pip|
|unload_model||间接依赖|pip|
|ThreadingHTTPServer||间接依赖|pip|
|RequestBlocker||间接依赖|pip|
|Any||间接依赖|pip|
|infer_auto_device_map||间接依赖|pip|
|BlipForConditionalGeneration||间接依赖|pip|
|float_list_to_base64||间接依赖|pip|
|generate_4chan_html||间接依赖|pip|
|chat_html_wrapper||间接依赖|pip|
|SpeechRecognition|3.10.0|间接依赖|pip|
|extensions||间接依赖|pip|
|load_dataset||间接依赖|pip|
|Image||间接依赖|pip|
|Optional||间接依赖|pip|
|add_chunks_to_collector||间接依赖|pip|
|exp||间接依赖|pip|
|aiofiles|23.1.0|间接依赖|pip|
|ImageOps||间接依赖|pip|
|log||间接依赖|pip|
|flask_cloudflared|0.0.12|间接依赖|pip|
|numpy|1.24|间接依赖|pip|
|requirements.txt||间接依赖|pip|
|sampler_hijack||间接依赖|pip|
|safetensors|0.3.2|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)