# rese1f/StableVideo安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694776429475880960.svg)](https://www.murphysec.com/console/report/1694776429261971456/1694776429475880960)

仓库描述：[ICCV 2023] StableVideo: Text-driven Consistency-aware Diffusion Video Editing

仓库地址：[https://github.com/rese1f/StableVideo](https://github.com/rese1f/StableVideo)

| star：433 | watch：13 | fork：23 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-24 00:15:51 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-25 02:19:41 | 组件总数：138 | 漏洞总数：5 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|
|pytorch-lightning 代码问题漏洞|反序列化|[MPS-2021-38670](https://www.oscs1024.com/hd/MPS-2021-38670)|CVE-2021-4118|高危|
|httpx 存在输入验证不恰当漏洞|输入验证不恰当|[MPS-2022-14944](https://www.oscs1024.com/hd/MPS-2022-14944)||中危|
|mpmath 存在ReDoS漏洞|ReDoS|[MPS-2022-14993](https://www.oscs1024.com/hd/MPS-2022-14993)||中危|
|pytorch-lightning 安全漏洞|代码注入|[MPS-2022-5528](https://www.oscs1024.com/hd/MPS-2022-5528)|CVE-2022-0845|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|pytorch-lightning|1.5.0|1.6.0rc0|间接依赖|建议修复|C:1|H:1|M:0|L:0|
|mpmath|1.3.0||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|httpx|0.24.1||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|numpy|1.25.2||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|31|Low|
|自定义许可证|22|Low|
|HPND|1|Low|
|BSD-3-Clause|11|Low|
|Apache-2.0|34|Low|
|BSD-2-Clause|4|Low|
|Unlicense|1|Low|
|Apache-2.0 OR MIT|2|Low|
|ISC|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|pyparsing|3.0.9|间接依赖|pip|
|oauthlib|3.2.2|间接依赖|pip|
|lit|16.0.6|间接依赖|pip|
|cycler|0.11.0|间接依赖|pip|
|rearrange||间接依赖|pip|
|packaging|23.1|间接依赖|pip|
|Pillow|10.0.0|间接依赖|pip|
|MarkupSafe|2.1.3|间接依赖|pip|
|ftfy|6.1.1|间接依赖|pip|
|annotated-types|0.5.0|间接依赖|pip|
|jsonschema|4.19.0|间接依赖|pip|
|nvidia-nvtx-cu11|11.7.91|间接依赖|pip|
|pyasn1|0.5.0|间接依赖|pip|
|nvidia-cuda-nvrtc-cu11|11.7.99|间接依赖|pip|
|PIL||间接依赖|pip|
|opencv-python|4.8.0.76|间接依赖|pip|
|yarl|1.9.2|间接依赖|pip|
|nvidia-cufft-cu11|10.9.0.58|间接依赖|pip|
|typing_extensions|4.7.1|间接依赖|pip|
|rsa|4.9|间接依赖|pip|
|filelock|3.12.2|间接依赖|pip|
|nvidia-cusparse-cu11|11.7.4.91|间接依赖|pip|
|absl-py|1.4.0|间接依赖|pip|
|safetensors|0.3.2|间接依赖|pip|
|sniffio|1.3.0|间接依赖|pip|
|charset-normalizer|3.2.0|间接依赖|pip|
|frozenlist|1.4.0|间接依赖|pip|
|orjson|3.9.5|间接依赖|pip|
|nvidia-nccl-cu11|2.14.3|间接依赖|pip|
|torch|2.0.1|间接依赖|pip|
|starlette|0.27.0|间接依赖|pip|
|aiofiles|23.2.1|间接依赖|pip|
|mpmath|1.3.0|间接依赖|pip|
|Werkzeug|2.3.7|间接依赖|pip|
|wcwidth|0.2.6|间接依赖|pip|
|linkify-it-py|2.0.2|间接依赖|pip|
|attrs|23.1.0|间接依赖|pip|
|urllib3|1.26.16|间接依赖|pip|
|pyDeprecate|0.3.1|间接依赖|pip|
|gradio_client|0.4.0|间接依赖|pip|
|nvidia-cublas-cu11|11.10.3.66|间接依赖|pip|
|einops|0.6.1|间接依赖|pip|
|toolz|0.12.0|间接依赖|pip|
|click|8.1.6|间接依赖|pip|
|grpcio|1.57.0|间接依赖|pip|
|huggingface-hub|0.16.4|间接依赖|pip|
|nvidia-cusolver-cu11|11.4.0.1|间接依赖|pip|
|omegaconf|2.3.0|间接依赖|pip|
|anyio|3.7.1|间接依赖|pip|
|httpcore|0.17.3|间接依赖|pip|
|pyasn1-modules|0.3.0|间接依赖|pip|
|requests|2.31.0|间接依赖|pip|
|google-auth-oauthlib|1.0.0|间接依赖|pip|
|matplotlib|3.7.2|间接依赖|pip|
|h11|0.14.0|间接依赖|pip|
|nvidia-cuda-runtime-cu11|11.7.99|间接依赖|pip|
|Image||间接依赖|pip|
|idna|3.4|间接依赖|pip|
|pandas|2.0.3|间接依赖|pip|
|google-auth|2.22.0|间接依赖|pip|
|httpx|0.24.1|间接依赖|pip|
|nvidia-curand-cu11|10.2.10.91|间接依赖|pip|
|nvidia-cuda-cupti-cu11|11.7.101|间接依赖|pip|
|tensorboard|2.14.0|间接依赖|pip|
|networkx|3.1|间接依赖|pip|
|ldm||间接依赖|pip|
|cmake|3.27.2|间接依赖|pip|
|requests-oauthlib|1.3.1|间接依赖|pip|
|mdit-py-plugins|0.3.3|间接依赖|pip|
|pydub|0.25.1|间接依赖|pip|
|jsonschema-specifications|2023.7.1|间接依赖|pip|
|six|1.16.0|间接依赖|pip|
|pytorch-lightning|1.5.0|间接依赖|pip|
|contourpy|1.1.0|间接依赖|pip|
|python-dateutil|2.8.2|间接依赖|pip|
|resize_image||间接依赖|pip|
|mdurl|0.1.2|间接依赖|pip|
|tensorboard-data-server|0.7.1|间接依赖|pip|
|aiohttp|3.8.5|间接依赖|pip|
|aiosignal|1.3.1|间接依赖|pip|
|Encoder||间接依赖|pip|
|torchmetrics|1.0.3|间接依赖|pip|
|ffmpy|0.3.1|间接依赖|pip|
|fonttools|4.42.0|间接依赖|pip|
|uc-micro-py|1.0.2|间接依赖|pip|
|Jinja2|3.1.2|间接依赖|pip|
|certifi|2023.7.22|间接依赖|pip|
|uvicorn|0.23.2|间接依赖|pip|
|altair|5.0.1|间接依赖|pip|
|nvidia-cudnn-cu11|8.5.0.96|间接依赖|pip|
|pytz|2023.3|间接依赖|pip|
|tzdata|2023.3|间接依赖|pip|
|regex|2023.8.8|间接依赖|pip|
|pydantic_core|2.4.0|间接依赖|pip|
|websockets|11.0.3|间接依赖|pip|
|triton|2.0.0|间接依赖|pip|
|fsspec|2023.6.0|间接依赖|pip|
|HWC3||间接依赖|pip|
|multidict|6.0.4|间接依赖|pip|
|Markdown|3.4.4|间接依赖|pip|
|lightning-utilities|0.9.0|间接依赖|pip|
|repeat||间接依赖|pip|
|semantic-version|2.10.0|间接依赖|pip|
|tokenizers|0.13.3|间接依赖|pip|
|T5Tokenizer||间接依赖|pip|
|make_beta_schedule||间接依赖|pip|
|rpds-py|0.9.2|间接依赖|pip|
|fastapi|0.101.1|间接依赖|pip|
|PyYAML|6.0.1|间接依赖|pip|
|importlib-resources|6.0.1|间接依赖|pip|
|imageio-ffmpeg|0.4.8|间接依赖|pip|
|extract_into_tensor||间接依赖|pip|
|Decoder||间接依赖|pip|
|sentencepiece|0.1.99|间接依赖|pip|
|timm|0.9.5|间接依赖|pip|
|open-clip-torch|2.20.0|间接依赖|pip|
|antlr4-python3-runtime|4.9.3|间接依赖|pip|
|protobuf|3.20.3|间接依赖|pip|
|transformers|4.31.0|间接依赖|pip|
|kiwisolver|1.4.4|间接依赖|pip|
|future|0.18.3|间接依赖|pip|
|torchvision|0.15.2|间接依赖|pip|
|numpy|1.25.2|间接依赖|pip|
|python-multipart|0.0.6|间接依赖|pip|
|tqdm|4.66.1|间接依赖|pip|
|referencing|0.30.2|间接依赖|pip|
|ImageDraw||间接依赖|pip|
|scipy|1.11.1|间接依赖|pip|
|async-timeout|4.0.3|间接依赖|pip|
|gradio|3.40.1|间接依赖|pip|
|markdown-it-py|2.2.0|间接依赖|pip|
|cachetools|5.3.1|间接依赖|pip|
|sympy|1.12|间接依赖|pip|
|pydantic|2.1.1|间接依赖|pip|
|imsave||间接依赖|pip|
|T5EncoderModel||间接依赖|pip|
|imread||间接依赖|pip|
|imageio|2.31.1|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)