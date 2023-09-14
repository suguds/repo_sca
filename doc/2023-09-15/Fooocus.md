# lllyasviel/Fooocus安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1702385685708455936.svg)](https://www.murphysec.com/console/report/1691513783125430272/1702385685708455936)

仓库描述：Focus on prompting and generating

仓库地址：[https://github.com/lllyasviel/Fooocus](https://github.com/lllyasviel/Fooocus)

| star：11637 | watch：108 | fork：797 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-14 18:19:20 | 许可证：GPL-3.0 |
| 最近检测时间：2023-09-15 02:16:23 | 组件总数：28 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|numpy|1.23.5||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|3|Low|
|自定义许可证|3|Low|
|BSD-3-Clause|2|Low|
|GPL-2.0|1|Medium|
|Apache-2.0|3|Low|
|HPND|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|apply_style||间接依赖|pip|
|einops|0.4.1|间接依赖|pip|
|scipy|1.9.3|间接依赖|pip|
|style_keys||间接依赖|pip|
|EmptyLatentImage||间接依赖|pip|
|omegaconf|2.2.3|间接依赖|pip|
|pytorch_lightning|1.9.4|间接依赖|pip|
|modules||间接依赖|pip|
|VAEDecode||间接依赖|pip|
|psutil|5.9.5|间接依赖|pip|
|pyyaml|6.0|间接依赖|pip|
|numpy|1.23.5|间接依赖|pip|
|pygit2|1.12.2|间接依赖|pip|
|is_installed||间接依赖|pip|
|torchsde|0.2.5|间接依赖|pip|
|aspect_ratios||间接依赖|pip|
|AutoModelForCausalLM||间接依赖|pip|
|run||间接依赖|pip|
|AutoTokenizer||间接依赖|pip|
|transformers|4.30.2|间接依赖|pip|
|SDXLRefiner||间接依赖|pip|
|accelerate|0.21.0|间接依赖|pip|
|gradio|3.39.0|间接依赖|pip|
|safetensors|0.3.1|间接依赖|pip|
|SDXL||间接依赖|pip|
|tqdm|4.64.1|间接依赖|pip|
|comfy||间接依赖|pip|
|Pillow|9.2.0|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)