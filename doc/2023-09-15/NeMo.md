# NVIDIA/NeMo安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1702387398377865216.svg)](https://www.murphysec.com/console/report/1702387398138789888/1702387398377865216)

仓库描述：NeMo: a toolkit for conversational AI

仓库地址：[https://github.com/NVIDIA/NeMo](https://github.com/NVIDIA/NeMo)

| star：7881 | watch：171 | fork：1793 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-15 01:23:17 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-15 02:23:24 | 组件总数：28 | 漏洞总数：4 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|nltk 安全漏洞|ReDoS|[MPS-2021-32644](https://www.oscs1024.com/hd/MPS-2021-32644)|CVE-2021-3842|高危|
|Natural Language Toolkit 资源管理错误漏洞|拒绝服务|[MPS-2021-36979](https://www.oscs1024.com/hd/MPS-2021-36979)|CVE-2021-43854|高危|
|Open Neural Network Exchange 路径遍历漏洞|路径遍历|[MPS-2022-5165](https://www.oscs1024.com/hd/MPS-2022-5165)|CVE-2022-25882|高危|
|SciPy 资源管理错误漏洞|UAF|[MPS-2023-10196](https://www.oscs1024.com/hd/MPS-2023-10196)|CVE-2023-29824|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|scipy|0.14|1.10.0rc1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|nltk|3.6.5|3.6.6|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|onnx|1.7.0|1.13.0|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|2|Low|
|ISC|2|Low|
|MIT|6|Low|
|Apache-2.0|5|Low|
|自定义许可证|3|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|nemo_text_processing|0.1.6rc0|间接依赖|pip|
|Jinja2|3.1|间接依赖|pip|
|youtokentome|1.0.5|间接依赖|pip|
|progress|1.5|间接依赖|pip|
|tabulate|0.8.7|间接依赖|pip|
|setuptools|65.5.1|间接依赖|pip|
|nltk|3.6.5|间接依赖|pip|
|sacremoses|0.0.43|间接依赖|pip|
|pydata-sphinx-theme|0.13.1|间接依赖|pip|
|onnx|1.7.0|间接依赖|pip|
|transformers|4.0.1|间接依赖|pip|
|torchmetrics|0.11.0|间接依赖|pip|
|textdistance|4.1.5|间接依赖|pip|
|dash|2.1.0|间接依赖|pip|
|matplotlib|3.3.2|间接依赖|pip|
|librosa|0.9.1|间接依赖|pip|
|megatron_core|0.2.0|间接依赖|pip|
|omegaconf|2.3|间接依赖|pip|
|jiwer|2.0.0|间接依赖|pip|
|$f||间接依赖|pip|
|sentencepiece|1.0.0|间接依赖|pip|
|black|19.10b0|间接依赖|pip|
|dash_bootstrap_components|1.0.3|间接依赖|pip|
|tqdm|4.41.0|间接依赖|pip|
|ctc_segmentation|1.7.1|间接依赖|pip|
|urllib3|2.0.0|间接依赖|pip|
|click|8.0.2|间接依赖|pip|
|scipy|0.14|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)