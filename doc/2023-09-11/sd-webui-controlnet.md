# Mikubill/sd-webui-controlnet安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700936780941492224.svg)](https://www.murphysec.com/console/report/1698763639582490624/1700936780941492224)

仓库描述：WebUI extension for ControlNet

仓库地址：[https://github.com/Mikubill/sd-webui-controlnet](https://github.com/Mikubill/sd-webui-controlnet)

| star：12629 | watch：141 | fork：1597 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-09-10 22:49:37 | 许可证：GPL-3.0 |
| 最近检测时间：2023-09-11 02:18:55 | 组件总数：104 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|PyTorch 命令注入漏洞|代码注入|[MPS-2022-65270](https://www.oscs1024.com/hd/MPS-2022-65270)|CVE-2022-45907|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|torch|1.2.0|1.13.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|1|Low|
|自定义许可证|5|Low|
|MIT|5|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|Dict||间接依赖|pip|
|Body||间接依赖|pip|
|EventWriter||间接依赖|pip|
|xavier_init||间接依赖|pip|
|inference_detector||间接依赖|pip|
|norm_normalize||间接依赖|pip|
|Keypoint||间接依赖|pip|
|ConvModule||间接依赖|pip|
|Resize||间接依赖|pip|
|h3||间接依赖|pip|
|meta||间接依赖|pip|
|lowvram||间接依赖|pip|
|Scale||间接依赖|pip|
|masked_l1_loss||间接依赖|pip|
|NormalizeImage||间接依赖|pip|
|CNNBlockBase||间接依赖|pip|
|UpSampleGN||间接依赖|pip|
|Any||间接依赖|pip|
|CenterCrop||间接依赖|pip|
|RandomAffine||间接依赖|pip|
|resize||间接依赖|pip|
|UpSampleBN||间接依赖|pip|
|handDetect||间接依赖|pip|
|shared||间接依赖|pip|
|devices||间接依赖|pip|
|build_conv_layer||间接依赖|pip|
|CLIPVisionConfig||间接依赖|pip|
|IMAGENET_MEAN||间接依赖|pip|
|forward_default||间接依赖|pip|
|Visualizer||间接依赖|pip|
|load_file||间接依赖|pip|
|Mlp||间接依赖|pip|
|constant_init||间接依赖|pip|
|abstractmethod||间接依赖|pip|
|build_from_cfg||间接依赖|pip|
|init_segmentor||间接依赖|pip|
|geffnet||间接依赖|pip|
|faceDetect||间接依赖|pip|
|Upsample||间接依赖|pip|
|annotator||间接依赖|pip|
|colors||间接依赖|pip|
|init_detector||间接依赖|pip|
|DropPath||间接依赖|pip|
|get_unique_axis0||间接依赖|pip|
|colorbar||间接依赖|pip|
|internal_controlnet||间接依赖|pip|
|util||间接依赖|pip|
|MultiDilatedGlobalGenerator||间接依赖|pip|
|get_event_storage||间接依赖|pip|
|conv_nd||间接依赖|pip|
|make_backbone_default||间接依赖|pip|
|CLIPVisionModelWithProjection||间接依赖|pip|
|get_class_weight||间接依赖|pip|
|MMDistributedDataParallel||间接依赖|pip|
|is_tuple_of||间接依赖|pip|
|ABCMeta||间接依赖|pip|
|ColorMode||间接依赖|pip|
|torchvision|0.4.0|间接依赖|pip|
|build_activation_layer||间接依赖|pip|
|build_norm_layer||间接依赖|pip|
|Callable||间接依赖|pip|
|MMDataParallel||间接依赖|pip|
|List||间接依赖|pip|
|ToPILImage||间接依赖|pip|
|get_activation||间接依赖|pip|
|Adapter||间接依赖|pip|
|Registry||间接依赖|pip|
|torch|1.2.0|间接依赖|pip|
|encode_poses_as_json||间接依赖|pip|
|collate||间接依赖|pip|
|squeeze||间接依赖|pip|
|visualize_mask_and_images_batch||间接依赖|pip|
|deprecated_api_warning||间接依赖|pip|
|feature_matching_loss||间接依赖|pip|
|ToTensor||间接依赖|pip|
|Tuple||间接依赖|pip|
|GlobalGenerator||间接依赖|pip|
|opencv-python|4.8.0|间接依赖|pip|
|ui||间接依赖|pip|
|Resnet||间接依赖|pip|
|activations||间接依赖|pip|
|DepthwiseSeparableConvModule||间接依赖|pip|
|scripts||间接依赖|pip|
|Union||间接依赖|pip|
|weight_reduce_loss||间接依赖|pip|
|scatter||间接依赖|pip|
|linear||间接依赖|pip|
|NamedTuple||间接依赖|pip|
|ndarray_lru_cache||间接依赖|pip|
|BaseVisualizer||间接依赖|pip|
|modules||间接依赖|pip|
|build_upsample_layer||间接依赖|pip|
|Conv2d||间接依赖|pip|
|forward_adapted_unflatten||间接依赖|pip|
|Optional||间接依赖|pip|
|IMAGENET_STD||间接依赖|pip|
|save_file||间接依赖|pip|
|semantic_run||间接依赖|pip|
|PlugableAdapter||间接依赖|pip|
|inference_segmentor||间接依赖|pip|
|processing||间接依赖|pip|
|Resnext_torch||间接依赖|pip|
|make_detectron2_model||间接依赖|pip|
|PoseResult||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)