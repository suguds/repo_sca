# IDEA-Research/DWPose安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698038798322810880.svg)](https://www.murphysec.com/console/report/1692965311426220032/1698038798322810880)

仓库描述："Effective Whole-body Pose Estimation with Two-stages Distillation" (ICCV 2023, CV4Metaverse Workshop)

仓库地址：[https://github.com/IDEA-Research/DWPose](https://github.com/IDEA-Research/DWPose)

| star：1070 | watch：16 | fork：59 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-17 23:42:30 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-03 02:28:36 | 组件总数：79 | 漏洞总数：5 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|NumPy 安全漏洞|不充分的比较|[MPS-2021-25631](https://www.oscs1024.com/hd/MPS-2021-25631)|CVE-2021-34141|中危|
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|
|NumPy 安全漏洞|经典缓冲区溢出|[MPS-2021-32279](https://www.oscs1024.com/hd/MPS-2021-32279)|CVE-2021-41496|中危|
|loguru 代码注入漏洞|代码注入|[MPS-2022-1393](https://www.oscs1024.com/hd/MPS-2022-1393)|CVE-2022-0329|严重|
|PyTorch 命令注入漏洞|代码注入|[MPS-2022-65270](https://www.oscs1024.com/hd/MPS-2022-65270)|CVE-2022-45907|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|torch|1.2.0|1.13.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|loguru|0.6.0||间接依赖|建议修复|C:1|H:0|M:0|L:0|
|numpy|1.21.6|1.22.2|间接依赖|可选修复|C:0|H:0|M:3|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|6|Low|
|BSD-3-Clause|1|Low|
|GPL-3.0|1|Medium|
|自定义许可证|2|Low|
|Apache-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|repeat||间接依赖|pip|
|Resize||间接依赖|pip|
|is_tuple_of||间接依赖|pip|
|norm_normalize||间接依赖|pip|
|imread||间接依赖|pip|
|forward_adapted_unflatten||间接依赖|pip|
|squeeze||间接依赖|pip|
|forward_default||间接依赖|pip|
|disable_verbosity||间接依赖|pip|
|weight_reduce_loss||间接依赖|pip|
|setup||间接依赖|pip|
|get_class_weight||间接依赖|pip|
|geffnet||间接依赖|pip|
|ABCMeta||间接依赖|pip|
|onnxruntime-gpu|1.8.1|间接依赖|pip|
|abstractmethod||间接依赖|pip|
|numpy|1.21.6|间接依赖|pip|
|ColorMode||间接依赖|pip|
|share||间接依赖|pip|
|get_activation||间接依赖|pip|
|make_noise_disk||间接依赖|pip|
|List||间接依赖|pip|
|DropPath||间接依赖|pip|
|imsave||间接依赖|pip|
|CNNBlockBase||间接依赖|pip|
|T5EncoderModel||间接依赖|pip|
|ToTensor||间接依赖|pip|
|NormalizeImage||间接依赖|pip|
|Scale||间接依赖|pip|
|build_norm_layer||间接依赖|pip|
|make_beta_schedule||间接依赖|pip|
|rearrange||间接依赖|pip|
|Encoder||间接依赖|pip|
|Upsample||间接依赖|pip|
|Mlp||间接依赖|pip|
|build_upsample_layer||间接依赖|pip|
|T5Tokenizer||间接依赖|pip|
|EventWriter||间接依赖|pip|
|Registry||间接依赖|pip|
|onnxruntime|1.14.1|间接依赖|pip|
|find_packages||间接依赖|pip|
|build_from_cfg||间接依赖|pip|
|torch|1.2.0|间接依赖|pip|
|ImageDraw||间接依赖|pip|
|ToPILImage||间接依赖|pip|
|activations||间接依赖|pip|
|Conv2d||间接依赖|pip|
|ConvModule||间接依赖|pip|
|Image||间接依赖|pip|
|UpSampleGN||间接依赖|pip|
|mmpose||间接依赖|pip|
|scatter||间接依赖|pip|
|loguru|0.6.0|间接依赖|pip|
|deprecated_api_warning||间接依赖|pip|
|MMDataParallel||间接依赖|pip|
|build_conv_layer||间接依赖|pip|
|Visualizer||间接依赖|pip|
|constant_init||间接依赖|pip|
|ldm||间接依赖|pip|
|UpSampleBN||间接依赖|pip|
|requirements/build.txt||间接依赖|pip|
|make_backbone_default||间接依赖|pip|
|MMDistributedDataParallel||间接依赖|pip|
|get_event_storage||间接依赖|pip|
|extract_into_tensor||间接依赖|pip|
|resize_image||间接依赖|pip|
|mmengine||间接依赖|pip|
|collate||间接依赖|pip|
|torchvision|0.4.0|间接依赖|pip|
|annotator||间接依赖|pip|
|HWC3||间接依赖|pip|
|xavier_init||间接依赖|pip|
|build_activation_layer||间接依赖|pip|
|DepthwiseSeparableConvModule||间接依赖|pip|
|enable_sliced_attention||间接依赖|pip|
|img2mask||间接依赖|pip|
|Dict||间接依赖|pip|
|resize||间接依赖|pip|
|Decoder||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)