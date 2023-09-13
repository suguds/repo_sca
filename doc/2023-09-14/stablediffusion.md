# Stability-AI/stablediffusion安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1702025264221519872.svg)](https://www.murphysec.com/console/report/1696226886978793472/1702025264221519872)

仓库描述：High-Resolution Image Synthesis with Latent Diffusion Models

仓库地址：[https://github.com/Stability-AI/stablediffusion](https://github.com/Stability-AI/stablediffusion)

| star：29833 | watch：370 | fork：3881 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-14 00:31:41 | 许可证：MIT |
| 最近检测时间：2023-09-14 02:30:47 | 组件总数：31 | 漏洞总数：6 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|pytorch-lightning 代码问题漏洞|反序列化|[MPS-2021-38670](https://www.oscs1024.com/hd/MPS-2021-38670)|CVE-2021-4118|高危|
|Streamlit 存在路径遍历漏洞|路径遍历|[MPS-2022-51432](https://www.oscs1024.com/hd/MPS-2022-51432)|CVE-2022-35918|高危|
|pytorch-lightning 安全漏洞|代码注入|[MPS-2022-5528](https://www.oscs1024.com/hd/MPS-2022-5528)|CVE-2022-0845|严重|
|Python 安全漏洞|ReDoS|[MPS-2022-57238](https://www.oscs1024.com/hd/MPS-2022-57238)|CVE-2022-40897|中危|
|Streamlit 跨站脚本漏洞|XSS|[MPS-2023-6767](https://www.oscs1024.com/hd/MPS-2023-6767)|CVE-2023-27494|中危|
|Gradio 输入验证错误漏洞||[MPS-f8mu-5xwo](https://www.oscs1024.com/hd/MPS-f8mu-5xwo)|CVE-2023-34239|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|streamlit|0.73.1|1.11.1|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|pytorch-lightning|1.4.2|1.6.0rc0|间接依赖|建议修复|C:1|H:1|M:0|L:0|
|gradio|3.13.2|3.34.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|setuptools|39.2.0|65.5.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|5|Low|
|Apache-2.0|6|Low|
|自定义许可证|3|Low|
|BSD-2-Clause|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|ldm||间接依赖|pip|
|einops|0.3.0|间接依赖|pip|
|streamlit-drawable-canvas|0.8.0|间接依赖|pip|
|rearrange||间接依赖|pip|
|kornia|0.6|间接依赖|pip|
|invisible-watermark|0.1.5|间接依赖|pip|
|open-clip-torch|2.7.0|间接依赖|pip|
|ImageDraw||间接依赖|pip|
|repeat||间接依赖|pip|
|extract_into_tensor||间接依赖|pip|
|setuptools|39.2.0|间接依赖|pip|
|albumentations|0.4.3|间接依赖|pip|
|imageio-ffmpeg|0.4.2|间接依赖|pip|
|Encoder||间接依赖|pip|
|pytorch-lightning|1.4.2|间接依赖|pip|
|test-tube|0.7.5|间接依赖|pip|
|make_beta_schedule||间接依赖|pip|
|streamlit|0.73.1|间接依赖|pip|
|webdataset|0.2.5|间接依赖|pip|
|imageio|2.9.0|间接依赖|pip|
|T5EncoderModel||间接依赖|pip|
|pudb|2019.2|间接依赖|pip|
|torchmetrics|0.6|间接依赖|pip|
|imread||间接依赖|pip|
|gradio|3.13.2|间接依赖|pip|
|imsave||间接依赖|pip|
|Decoder||间接依赖|pip|
|transformers|4.19.2|间接依赖|pip|
|Image||间接依赖|pip|
|omegaconf|2.1.1|间接依赖|pip|
|T5Tokenizer||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)