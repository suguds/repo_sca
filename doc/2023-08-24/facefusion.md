# facefusion/facefusion安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694413140111290368.svg)](https://www.murphysec.com/console/report/1693688505665675264/1694413140111290368)

仓库描述：Next generation face swapper and enhancer

仓库地址：[https://github.com/facefusion/facefusion](https://github.com/facefusion/facefusion)

| star：1738 | watch：21 | fork：129 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-23 22:50:07 | 许可证：- |
| 最近检测时间：2023-08-24 02:16:04 | 组件总数：24 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|
|Google TensorFlow 目录穿越漏洞|路径遍历|[MPS-2021-9211](https://www.oscs1024.com/hd/MPS-2021-9211)|CVE-2021-35958|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|tensorflow|2.13.0||间接依赖|建议修复|C:1|H:0|M:0|L:0|
|numpy|1.24.3||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|4|Low|
|Apache-2.0|4|Low|
|自定义许可证|2|Low|
|BSD-3-Clause|3|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|opencv-python|4.8.0.74|间接依赖|pip|
|gradio|3.40.1|间接依赖|pip|
|processors||间接依赖|pip|
|as_completed||间接依赖|pip|
|insightface|0.7.3|间接依赖|pip|
|numpy|1.24.3|间接依赖|pip|
|protobuf|4.23.4|间接依赖|pip|
|pillow|10.0.0|间接依赖|pip|
|opennsfw2|0.10.2|间接依赖|pip|
|about||间接依赖|pip|
|gfpgan|1.3.8|间接依赖|pip|
|List||间接依赖|pip|
|tqdm|4.65.0|间接依赖|pip|
|pytest|7.4.0|间接依赖|pip|
|Optional||间接依赖|pip|
|onnx|1.14.0|间接依赖|pip|
|tensorflow|2.13.0|间接依赖|pip|
|psutil|5.9.5|间接依赖|pip|
|Any||间接依赖|pip|
|conditional_download||间接依赖|pip|
|onnxruntime|1.15.1|间接依赖|pip|
|detect_fps||间接依赖|pip|
|ThreadPoolExecutor||间接依赖|pip|
|realesrgan|0.3.0|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)