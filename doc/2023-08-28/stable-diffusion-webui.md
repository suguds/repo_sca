# AUTOMATIC1111/stable-diffusion-webui安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695865977136046080.svg)](https://www.murphysec.com/console/report/1695865977081520128/1695865977136046080)

仓库描述：Stable Diffusion web UI

仓库地址：[https://github.com/AUTOMATIC1111/stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui)

| star：98935 | watch：841 | fork：19702 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-28 02:28:47 | 许可证：AGPL-3.0 |
| 最近检测时间：2023-08-28 02:29:19 | 组件总数：81 | 漏洞总数：3 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|
|piexif 存在路径遍历漏洞|路径遍历|[MPS-2022-15029](https://www.oscs1024.com/hd/MPS-2022-15029)||中危|
|Gradio 输入验证错误漏洞||[MPS-f8mu-5xwo](https://www.oscs1024.com/hd/MPS-f8mu-5xwo)|CVE-2023-34239|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|gradio|3.32.0|3.34.0|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|piexif|1.1.3||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|numpy|1.23.5||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|10|Low|
|MIT|8|Low|
|BSD-3-Clause|2|Low|
|Apache-2.0|6|Low|
|HPND|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|DataLoader||间接依赖|pip|
|Image||间接依赖|pip|
|realesrgan|0.3.0|间接依赖|pip|
|Optional||间接依赖|pip|
|piexif|1.1.3|间接依赖|pip|
|inflection|0.5.1|间接依赖|pip|
|call_queue||间接依赖|pip|
|sd_samplers_common||间接依赖|pip|
|sd_samplers||间接依赖|pip|
|sd_hijack_clip||间接依赖|pip|
|torchdiffeq|0.2.3|间接依赖|pip|
|extensions||间接依赖|pip|
|deepbooru||间接依赖|pip|
|GitPython|3.1.30|间接依赖|pip|
|sd_hijack||间接依赖|pip|
|jsonmerge|1.8.0|间接依赖|pip|
|script_path||间接依赖|pip|
|accelerate|0.18.0|间接依赖|pip|
|ui_tempdir||间接依赖|pip|
|torchsde|0.2.5|间接依赖|pip|
|ui_common||间接依赖|pip|
|Dict||间接依赖|pip|
|numpy|1.23.5|间接依赖|pip|
|Dataset||间接依赖|pip|
|basicsr|1.4.2|间接依赖|pip|
|processing||间接依赖|pip|
|ImageDraw||间接依赖|pip|
|Depends||间接依赖|pip|
|opts||间接依赖|pip|
|blendmodes|2022|间接依赖|pip|
|tomesd|0.1.2|间接依赖|pip|
|timm|0.6.7|间接依赖|pip|
|PngImagePlugin||间接依赖|pip|
|modules||间接依赖|pip|
|errors||间接依赖|pip|
|Pillow|9.5.0|间接依赖|pip|
|Upscaler||间接依赖|pip|
|PIL||间接依赖|pip|
|UpscalerData||间接依赖|pip|
|lark|1.1.2|间接依赖|pip|
|einops|0.4.1|间接依赖|pip|
|models_path||间接依赖|pip|
|gfpgan|1.3.8|间接依赖|pip|
|shared||间接依赖|pip|
|script_callbacks||间接依赖|pip|
|ImageOps||间接依赖|pip|
|transformers|4.25.1|间接依赖|pip|
|torch||间接依赖|pip|
|generation_parameters_copypaste||间接依赖|pip|
|modelloader||间接依赖|pip|
|sd_hijack_optimizations||间接依赖|pip|
|images||间接依赖|pip|
|localization||间接依赖|pip|
|repeat||间接依赖|pip|
|omegaconf|2.2.3|间接依赖|pip|
|rearrange||间接依赖|pip|
|BaseModel||间接依赖|pip|
|ui_extra_networks_user_metadata||间接依赖|pip|
|paths||间接依赖|pip|
|safetensors|0.3.1|间接依赖|pip|
|state||间接依赖|pip|
|gradio|3.32.0|间接依赖|pip|
|pytorch_lightning|1.9.4|间接依赖|pip|
|Field||间接依赖|pip|
|timer||间接依赖|pip|
|script_loading||间接依赖|pip|
|data_path||间接依赖|pip|
|open-clip-torch|2.20.0|间接依赖|pip|
|resize-right|0.0.2|间接依赖|pip|
|prompt_parser||间接依赖|pip|
|kornia|0.6.7|间接依赖|pip|
|paths_internal||间接依赖|pip|
|devices||间接依赖|pip|
|fastapi|0.94.0|间接依赖|pip|
|APIRouter||间接依赖|pip|
|scripts||间接依赖|pip|
|clean-fid|0.1.35|间接依赖|pip|
|scikit-image|0.20.0|间接依赖|pip|
|psutil|5.9.5|间接依赖|pip|
|ui_extra_networks||间接依赖|pip|
|httpcore|0.15|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)