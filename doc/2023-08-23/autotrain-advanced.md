# huggingface/autotrain-advanced安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694052084180480000.svg)](https://www.murphysec.com/console/report/1694052083928821760/1694052084180480000)

仓库描述：🤗 AutoTrain Advanced

仓库地址：[https://github.com/huggingface/autotrain-advanced](https://github.com/huggingface/autotrain-advanced)

| star：1558 | watch：57 | fork：148 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-22 22:14:05 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-23 02:21:18 | 组件总数：52 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|loguru 代码注入漏洞|代码注入|[MPS-2022-1393](https://www.oscs1024.com/hd/MPS-2022-1393)|CVE-2022-0329|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|loguru|0.7.0||间接依赖|建议修复|C:1|H:0|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|5|Low|
|Apache-2.0|4|Low|
|MIT|5|Low|
|HPND|1|Low|
|BSD-3-Clause|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|Dataset||间接依赖|pip|
|utils||间接依赖|pip|
|DDPMScheduler||间接依赖|pip|
|_login_user||间接依赖|pip|
|AutoTrainDreamboothDataset||间接依赖|pip|
|Dict||间接依赖|pip|
|BaseModel||间接依赖|pip|
|AutoTrainDataset||间接依赖|pip|
|SpaceRunner||间接依赖|pip|
|scikit-learn|1.3.0|间接依赖|pip|
|TrainerControl||间接依赖|pip|
|evaluate|0.3.0|间接依赖|pip|
|VALID_IMAGE_EXTENSIONS||间接依赖|pip|
|XL_MODELS||间接依赖|pip|
|codecarbon|2.2.3|间接依赖|pip|
|tqdm|4.65.0|间接依赖|pip|
|load_dataset||间接依赖|pip|
|albumentations|1.3.1|间接依赖|pip|
|TrainerCallback||间接依赖|pip|
|logger||间接依赖|pip|
|einops|0.6.1|间接依赖|pip|
|AutoModelForCausalLM||间接依赖|pip|
|autotrain||间接依赖|pip|
|AutoencoderKL||间接依赖|pip|
|Pillow|10.0.0|间接依赖|pip|
|pydantic|1.10.11|间接依赖|pip|
|sentencepiece|0.1.99|间接依赖|pip|
|huggingface_hub|0.16.4|间接依赖|pip|
|jiwer|3.0.2|间接依赖|pip|
|sacremoses|0.0.53|间接依赖|pip|
|requests|2.31.0|间接依赖|pip|
|HfApi||间接依赖|pip|
|text_encoder_lora_state_dict||间接依赖|pip|
|gradio|3.39.0|间接依赖|pip|
|pandas|2.0.3|间接依赖|pip|
|loguru|0.7.0|间接依赖|pip|
|Any||间接依赖|pip|
|protobuf|4.23.4|间接依赖|pip|
|invisible-watermark|0.2.0|间接依赖|pip|
|Optional||间接依赖|pip|
|ipadic|1.0.0|间接依赖|pip|
|EndpointsRunner||间接依赖|pip|
|ProjectConfiguration||间接依赖|pip|
|werkzeug|2.3.6|间接依赖|pip|
|whoami||间接依赖|pip|
|joblib|1.3.1|间接依赖|pip|
|AutoTokenizer||间接依赖|pip|
|LoraLoaderMixin||间接依赖|pip|
|BACKEND_CHOICES||间接依赖|pip|
|Field||间接依赖|pip|
|List||间接依赖|pip|
|set_seed||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)