# 7eu7d7/HCP-Diffusion安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695140868305805312.svg)](https://www.murphysec.com/console/report/1695140867055902720/1695140868305805312)

仓库描述：A universal Stable-Diffusion toolbox

仓库地址：[https://github.com/7eu7d7/HCP-Diffusion](https://github.com/7eu7d7/HCP-Diffusion)

| star：645 | watch：19 | fork：52 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-24 21:14:23 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-26 02:27:52 | 组件总数：24 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|PyTorch 命令注入漏洞|代码注入|[MPS-2022-65270](https://www.oscs1024.com/hd/MPS-2022-65270)|CVE-2022-45907|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|torch|1.12.0|1.13.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|2|Low|
|自定义许可证|3|Low|
|Apache-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|hcpdiff||间接依赖|pip|
|Dict||间接依赖|pip|
|loguru||间接依赖|pip|
|Optional||间接依赖|pip|
|accelerate|0.15.0|间接依赖|pip|
|List||间接依赖|pip|
|dispatch_model||间接依赖|pip|
|CkptManagerPKL||间接依赖|pip|
|torchvision|0.13.0|间接依赖|pip|
|infer_auto_device_map||间接依赖|pip|
|save_emb||间接依赖|pip|
|RatioBucket||间接依赖|pip|
|transformers|4.25.1|间接依赖|pip|
|CkptManagerSafe||间接依赖|pip|
|einops|0.6.0|间接依赖|pip|
|colossalai|0.2.5|间接依赖|pip|
|Tuple||间接依赖|pip|
|Iterable||间接依赖|pip|
|import_text_encoder_class||间接依赖|pip|
|Union||间接依赖|pip|
|diffusers|0.17.1|间接依赖|pip|
|torch|1.12.0|间接依赖|pip|
|Trainer||间接依赖|pip|
|Any||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)